Ubuntu Budgie - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Ubuntu Budgie.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_Budgie/Desktop/README.md) and [notebooks](/Dist/Ubuntu_Budgie/Notebook/README.md).

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

Total: 701

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [6ace557278](https://linux-hardware.org/?probe=6ace557278) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [ef265ae548](https://linux-hardware.org/?probe=ef265ae548) | Apr 29, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [c1be74b619](https://linux-hardware.org/?probe=c1be74b619) | Apr 25, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [089d81a936](https://linux-hardware.org/?probe=089d81a936) | Apr 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [967eac195b](https://linux-hardware.org/?probe=967eac195b) | Apr 23, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [51daefb9d3](https://linux-hardware.org/?probe=51daefb9d3) | Apr 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [3b76e2f5ab](https://linux-hardware.org/?probe=3b76e2f5ab) | Apr 21, 2022 |
| Lenovo        | ThinkPad T430s 2356H83      | Notebook    | [714396bc62](https://linux-hardware.org/?probe=714396bc62) | Apr 20, 2022 |
| Lenovo        | ThinkPad E15 20RD003KHV     | Notebook    | [70547d6581](https://linux-hardware.org/?probe=70547d6581) | Apr 19, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [d2125b0881](https://linux-hardware.org/?probe=d2125b0881) | Apr 19, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [37fa300c26](https://linux-hardware.org/?probe=37fa300c26) | Apr 18, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [c1a5e02fa5](https://linux-hardware.org/?probe=c1a5e02fa5) | Apr 17, 2022 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [96eae556f2](https://linux-hardware.org/?probe=96eae556f2) | Apr 15, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [ca66ed7272](https://linux-hardware.org/?probe=ca66ed7272) | Apr 14, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| MSI           | H81M-E33                    | Desktop     | [33547f6d85](https://linux-hardware.org/?probe=33547f6d85) | Apr 11, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a75a1551fa](https://linux-hardware.org/?probe=a75a1551fa) | Apr 09, 2022 |
| Alienware     | m15                         | Notebook    | [0cd462faaa](https://linux-hardware.org/?probe=0cd462faaa) | Apr 07, 2022 |
| Lenovo        | ThinkPad E490 20N9001MBR    | Notebook    | [1b041100a3](https://linux-hardware.org/?probe=1b041100a3) | Apr 07, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [cda73dafa0](https://linux-hardware.org/?probe=cda73dafa0) | Apr 04, 2022 |
| TUXEDO        | InfinityBook S 14 v5        | Notebook    | [6a5061e741](https://linux-hardware.org/?probe=6a5061e741) | Apr 03, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [860fedd7f0](https://linux-hardware.org/?probe=860fedd7f0) | Apr 01, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [995691e022](https://linux-hardware.org/?probe=995691e022) | Apr 01, 2022 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [847b8f0788](https://linux-hardware.org/?probe=847b8f0788) | Apr 01, 2022 |
| Packard Be... | ENLE11BZ                    | Notebook    | [4fb836698c](https://linux-hardware.org/?probe=4fb836698c) | Mar 26, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [2b82008ffc](https://linux-hardware.org/?probe=2b82008ffc) | Mar 23, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| ASUSTek       | G752VY                      | Notebook    | [ffc0cdf0bd](https://linux-hardware.org/?probe=ffc0cdf0bd) | Mar 22, 2022 |
| HP            | 8158 A01                    | Mini pc     | [3ba669d072](https://linux-hardware.org/?probe=3ba669d072) | Mar 20, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [ca76b3a899](https://linux-hardware.org/?probe=ca76b3a899) | Mar 18, 2022 |
| Dell          | 03YJM6 A00                  | All in one  | [f444e85d64](https://linux-hardware.org/?probe=f444e85d64) | Mar 18, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [63ea3e99c5](https://linux-hardware.org/?probe=63ea3e99c5) | Mar 14, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [08525a320d](https://linux-hardware.org/?probe=08525a320d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T480 20L6SDR21A    | Notebook    | [b61991cef4](https://linux-hardware.org/?probe=b61991cef4) | Mar 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [22452f39c2](https://linux-hardware.org/?probe=22452f39c2) | Mar 11, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [42921aebfd](https://linux-hardware.org/?probe=42921aebfd) | Mar 10, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [be60e729e2](https://linux-hardware.org/?probe=be60e729e2) | Mar 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| HP            | Pavilion dm4                | Notebook    | [4786fbfbdd](https://linux-hardware.org/?probe=4786fbfbdd) | Mar 04, 2022 |
| HP            | Pavilion dm4                | Notebook    | [8adb026a31](https://linux-hardware.org/?probe=8adb026a31) | Mar 04, 2022 |
| Google        | Rammus                      | Notebook    | [a326a69db9](https://linux-hardware.org/?probe=a326a69db9) | Mar 02, 2022 |
| Google        | Rammus                      | Notebook    | [b395780983](https://linux-hardware.org/?probe=b395780983) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [5be284f90d](https://linux-hardware.org/?probe=5be284f90d) | Feb 26, 2022 |
| Microsoft     | Surface Book                | Tablet      | [a94d46ec1d](https://linux-hardware.org/?probe=a94d46ec1d) | Feb 25, 2022 |
| Microsoft     | Surface Book                | Tablet      | [f62d16f3b1](https://linux-hardware.org/?probe=f62d16f3b1) | Feb 25, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7fa418eb00](https://linux-hardware.org/?probe=7fa418eb00) | Feb 25, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [0ed28fa881](https://linux-hardware.org/?probe=0ed28fa881) | Feb 23, 2022 |
| HP            | Compaq Presario C700        | Notebook    | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9b8714532b](https://linux-hardware.org/?probe=9b8714532b) | Feb 20, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [e58eb70913](https://linux-hardware.org/?probe=e58eb70913) | Feb 19, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [20834c0dba](https://linux-hardware.org/?probe=20834c0dba) | Feb 17, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [536a1e49b0](https://linux-hardware.org/?probe=536a1e49b0) | Feb 17, 2022 |
| Dell          | 0RW199                      | Desktop     | [5cf70558c8](https://linux-hardware.org/?probe=5cf70558c8) | Feb 14, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [88768afd55](https://linux-hardware.org/?probe=88768afd55) | Feb 10, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [74c94f396f](https://linux-hardware.org/?probe=74c94f396f) | Feb 10, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [07233a144c](https://linux-hardware.org/?probe=07233a144c) | Feb 09, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2dd47c0a4b](https://linux-hardware.org/?probe=2dd47c0a4b) | Feb 08, 2022 |
| Viglen        | VUB1                        | Notebook    | [13f512e2d1](https://linux-hardware.org/?probe=13f512e2d1) | Feb 08, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [87e9ca3a01](https://linux-hardware.org/?probe=87e9ca3a01) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [de6e279575](https://linux-hardware.org/?probe=de6e279575) | Feb 07, 2022 |
| Razer         | Blade Stealth               | Notebook    | [c85996c28c](https://linux-hardware.org/?probe=c85996c28c) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [46ba4fcc12](https://linux-hardware.org/?probe=46ba4fcc12) | Feb 04, 2022 |
| Acer          | Aspire 8940G                | Notebook    | [686119ea77](https://linux-hardware.org/?probe=686119ea77) | Feb 03, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [9072890c1d](https://linux-hardware.org/?probe=9072890c1d) | Feb 02, 2022 |
| Sony          | SVS13A25PBS                 | Notebook    | [894e40654e](https://linux-hardware.org/?probe=894e40654e) | Feb 02, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [81f3f014e7](https://linux-hardware.org/?probe=81f3f014e7) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [f9e76db452](https://linux-hardware.org/?probe=f9e76db452) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [74533ff76f](https://linux-hardware.org/?probe=74533ff76f) | Jan 28, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [77a04d958e](https://linux-hardware.org/?probe=77a04d958e) | Jan 27, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [6f4c9d5553](https://linux-hardware.org/?probe=6f4c9d5553) | Jan 27, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [1a5d62c5fb](https://linux-hardware.org/?probe=1a5d62c5fb) | Jan 27, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [07192f2b7d](https://linux-hardware.org/?probe=07192f2b7d) | Jan 27, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [f7fafa6976](https://linux-hardware.org/?probe=f7fafa6976) | Jan 26, 2022 |
| TUXEDO        | Book XP1511                 | Notebook    | [9a62ad3fe4](https://linux-hardware.org/?probe=9a62ad3fe4) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [909aca1407](https://linux-hardware.org/?probe=909aca1407) | Jan 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e45b9230c9](https://linux-hardware.org/?probe=e45b9230c9) | Jan 19, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [edc7be1068](https://linux-hardware.org/?probe=edc7be1068) | Jan 18, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [249a326a8b](https://linux-hardware.org/?probe=249a326a8b) | Jan 17, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [98ff0f7580](https://linux-hardware.org/?probe=98ff0f7580) | Jan 17, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [585aa2aa39](https://linux-hardware.org/?probe=585aa2aa39) | Jan 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [e324ae4a05](https://linux-hardware.org/?probe=e324ae4a05) | Jan 16, 2022 |
| Viglen        | VUB1                        | Notebook    | [d16d7f30b3](https://linux-hardware.org/?probe=d16d7f30b3) | Jan 16, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [d7414a7101](https://linux-hardware.org/?probe=d7414a7101) | Jan 15, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [dd6c66b4dc](https://linux-hardware.org/?probe=dd6c66b4dc) | Jan 15, 2022 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [e4d4e112f7](https://linux-hardware.org/?probe=e4d4e112f7) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [03a777b7b1](https://linux-hardware.org/?probe=03a777b7b1) | Jan 13, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [43ea5ed123](https://linux-hardware.org/?probe=43ea5ed123) | Jan 12, 2022 |
| ASRock        | 4X4-4000 Series             | Desktop     | [172d5b0abc](https://linux-hardware.org/?probe=172d5b0abc) | Jan 12, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [ecaadc9cb3](https://linux-hardware.org/?probe=ecaadc9cb3) | Jan 04, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [bd181b10da](https://linux-hardware.org/?probe=bd181b10da) | Jan 04, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e55162d481](https://linux-hardware.org/?probe=e55162d481) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ee6ede67e9](https://linux-hardware.org/?probe=ee6ede67e9) | Jan 02, 2022 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [a76fb98d8d](https://linux-hardware.org/?probe=a76fb98d8d) | Jan 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [339ee3ca1c](https://linux-hardware.org/?probe=339ee3ca1c) | Dec 28, 2021 |
| Lenovo        | V310-15ISK 80SY             | Notebook    | [16855d1282](https://linux-hardware.org/?probe=16855d1282) | Dec 27, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [14323d7f2a](https://linux-hardware.org/?probe=14323d7f2a) | Dec 27, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| Teclast       | X6 plus                     | Tablet      | [d476f875d2](https://linux-hardware.org/?probe=d476f875d2) | Dec 23, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c860a1c3c5](https://linux-hardware.org/?probe=c860a1c3c5) | Dec 22, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [f0e03ffaed](https://linux-hardware.org/?probe=f0e03ffaed) | Dec 22, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [ddf55561ad](https://linux-hardware.org/?probe=ddf55561ad) | Dec 21, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [a3639ffcd5](https://linux-hardware.org/?probe=a3639ffcd5) | Dec 21, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [8e1c093fb8](https://linux-hardware.org/?probe=8e1c093fb8) | Dec 20, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [7eabc884a6](https://linux-hardware.org/?probe=7eabc884a6) | Dec 19, 2021 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [d416ec7878](https://linux-hardware.org/?probe=d416ec7878) | Dec 17, 2021 |
| HP            | Pavilion dm1                | Notebook    | [5e63d24312](https://linux-hardware.org/?probe=5e63d24312) | Dec 17, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [f586c51674](https://linux-hardware.org/?probe=f586c51674) | Dec 17, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [2aaaff47a4](https://linux-hardware.org/?probe=2aaaff47a4) | Dec 17, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [d34989fcaa](https://linux-hardware.org/?probe=d34989fcaa) | Dec 16, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7587f8f78a](https://linux-hardware.org/?probe=7587f8f78a) | Dec 16, 2021 |
| Acer          | E3-112M-C6BV                | Notebook    | [81a7f64292](https://linux-hardware.org/?probe=81a7f64292) | Dec 15, 2021 |
| ASRock        | H61M-HVS                    | Desktop     | [bd9653afdd](https://linux-hardware.org/?probe=bd9653afdd) | Dec 15, 2021 |
| HP            | Pavilion tx1000             | Notebook    | [e568b07f70](https://linux-hardware.org/?probe=e568b07f70) | Dec 14, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [49234a5c74](https://linux-hardware.org/?probe=49234a5c74) | Dec 10, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [7cf830d39e](https://linux-hardware.org/?probe=7cf830d39e) | Dec 10, 2021 |
| Lenovo        | ThinkPad W530 244743G       | Notebook    | [4aff204627](https://linux-hardware.org/?probe=4aff204627) | Dec 10, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [b6c63776b5](https://linux-hardware.org/?probe=b6c63776b5) | Dec 10, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b2d2913170](https://linux-hardware.org/?probe=b2d2913170) | Dec 07, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [429851405d](https://linux-hardware.org/?probe=429851405d) | Dec 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [ade1f1db1a](https://linux-hardware.org/?probe=ade1f1db1a) | Dec 07, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [9721dbfb66](https://linux-hardware.org/?probe=9721dbfb66) | Dec 07, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [6e77546d03](https://linux-hardware.org/?probe=6e77546d03) | Dec 06, 2021 |
| Toshiba       | Satellite S55-C             | Notebook    | [0e41e47583](https://linux-hardware.org/?probe=0e41e47583) | Dec 05, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [126c160ef3](https://linux-hardware.org/?probe=126c160ef3) | Dec 04, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [088fab187c](https://linux-hardware.org/?probe=088fab187c) | Dec 03, 2021 |
| Sony          | VPCEA47FX                   | Notebook    | [2f6f3b14de](https://linux-hardware.org/?probe=2f6f3b14de) | Dec 03, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [945995abf6](https://linux-hardware.org/?probe=945995abf6) | Dec 02, 2021 |
| Dell          | 0Y2MRG A00                  | Desktop     | [35a82530fb](https://linux-hardware.org/?probe=35a82530fb) | Dec 02, 2021 |
| Sony          | VPCEJ1L1E                   | Notebook    | [a48a00bdbc](https://linux-hardware.org/?probe=a48a00bdbc) | Dec 02, 2021 |
| TUXEDO        | P95_HP                      | Notebook    | [859d674cfe](https://linux-hardware.org/?probe=859d674cfe) | Dec 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [e62e98d46d](https://linux-hardware.org/?probe=e62e98d46d) | Nov 30, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3cea520e1f](https://linux-hardware.org/?probe=3cea520e1f) | Nov 29, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [3fbd626bf6](https://linux-hardware.org/?probe=3fbd626bf6) | Nov 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [ba184983ea](https://linux-hardware.org/?probe=ba184983ea) | Nov 27, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cd9d182e6e](https://linux-hardware.org/?probe=cd9d182e6e) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| HP            | 0A5Ch                       | Desktop     | [4858eb5c73](https://linux-hardware.org/?probe=4858eb5c73) | Nov 21, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [b397fce5b8](https://linux-hardware.org/?probe=b397fce5b8) | Nov 20, 2021 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [61f2f6aeab](https://linux-hardware.org/?probe=61f2f6aeab) | Nov 19, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [008cd729a5](https://linux-hardware.org/?probe=008cd729a5) | Nov 14, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [cb21aae05f](https://linux-hardware.org/?probe=cb21aae05f) | Nov 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [ed14b60c7a](https://linux-hardware.org/?probe=ed14b60c7a) | Nov 05, 2021 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [f18f314bc7](https://linux-hardware.org/?probe=f18f314bc7) | Nov 01, 2021 |
| Dell          | Inspiron 5515               | Notebook    | [35d04dc3b9](https://linux-hardware.org/?probe=35d04dc3b9) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [ef04c3c27a](https://linux-hardware.org/?probe=ef04c3c27a) | Oct 31, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [8ecbd29abd](https://linux-hardware.org/?probe=8ecbd29abd) | Oct 29, 2021 |
| TUXEDO        | Book XP15 / XP17 Gen12      | Notebook    | [4a518a759f](https://linux-hardware.org/?probe=4a518a759f) | Oct 25, 2021 |
| Apple         | MacBookPro8,2               | Notebook    | [571936bc0d](https://linux-hardware.org/?probe=571936bc0d) | Oct 23, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [6a3a81abd6](https://linux-hardware.org/?probe=6a3a81abd6) | Oct 22, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [2f0f49590b](https://linux-hardware.org/?probe=2f0f49590b) | Oct 22, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [90e49546c2](https://linux-hardware.org/?probe=90e49546c2) | Oct 21, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [cc51204b2c](https://linux-hardware.org/?probe=cc51204b2c) | Oct 20, 2021 |
| Acer          | Aspire 4752                 | Notebook    | [c4e21818b1](https://linux-hardware.org/?probe=c4e21818b1) | Oct 20, 2021 |
| HP            | 0A5Ch                       | Desktop     | [8d102a03f6](https://linux-hardware.org/?probe=8d102a03f6) | Oct 19, 2021 |
| HP            | 0A5Ch                       | Desktop     | [139efd1a3d](https://linux-hardware.org/?probe=139efd1a3d) | Oct 19, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4cb5912db3](https://linux-hardware.org/?probe=4cb5912db3) | Oct 15, 2021 |
| Lenovo        | G570 4334                   | Notebook    | [7a9034f398](https://linux-hardware.org/?probe=7a9034f398) | Oct 12, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [b665ef94e7](https://linux-hardware.org/?probe=b665ef94e7) | Oct 01, 2021 |
| ASUSTek       | X302LJ                      | Notebook    | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Lenovo        | ThinkPad T440 20B7S0F100    | Notebook    | [9710e6ad6f](https://linux-hardware.org/?probe=9710e6ad6f) | Sep 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [b640e5da6d](https://linux-hardware.org/?probe=b640e5da6d) | Sep 17, 2021 |
| Lenovo        | IdeaPad Flex 5 14ITL05 8... | Convertible | [feb38e948d](https://linux-hardware.org/?probe=feb38e948d) | Sep 13, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [3ea6af2159](https://linux-hardware.org/?probe=3ea6af2159) | Sep 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [981856c740](https://linux-hardware.org/?probe=981856c740) | Sep 09, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [17c9df42cd](https://linux-hardware.org/?probe=17c9df42cd) | Sep 07, 2021 |
| ASRock        | Z370M Pro4                  | Desktop     | [01d203a7af](https://linux-hardware.org/?probe=01d203a7af) | Sep 07, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [4b6f0833eb](https://linux-hardware.org/?probe=4b6f0833eb) | Sep 02, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | Notebook    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [d0b29312b8](https://linux-hardware.org/?probe=d0b29312b8) | Aug 31, 2021 |
| HP            | x360 310 G2 PC              | Notebook    | [429d94dd0f](https://linux-hardware.org/?probe=429d94dd0f) | Aug 31, 2021 |
| FUJITSU CL... | LIFEBOOK U9311A             | Notebook    | [7d5eeb6448](https://linux-hardware.org/?probe=7d5eeb6448) | Aug 30, 2021 |
| Dell          | XPS 15 9560                 | Notebook    | [55f224e5c3](https://linux-hardware.org/?probe=55f224e5c3) | Aug 26, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [aabe23e7a8](https://linux-hardware.org/?probe=aabe23e7a8) | Aug 20, 2021 |
| ASRock        | H61M-VG3                    | Desktop     | [7257c7b0bb](https://linux-hardware.org/?probe=7257c7b0bb) | Aug 20, 2021 |
| Google        | Peppy                       | Notebook    | [b0be7ddeac](https://linux-hardware.org/?probe=b0be7ddeac) | Aug 18, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [15b41a9b17](https://linux-hardware.org/?probe=15b41a9b17) | Aug 16, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [dcbe85bfb3](https://linux-hardware.org/?probe=dcbe85bfb3) | Aug 16, 2021 |
| TUXEDO        | Book XP1511                 | Notebook    | [7526222677](https://linux-hardware.org/?probe=7526222677) | Aug 15, 2021 |
| TUXEDO        | Book XP1511                 | Notebook    | [3312e66e9f](https://linux-hardware.org/?probe=3312e66e9f) | Aug 15, 2021 |
| Unknown       | Unknown                     | Notebook    | [8ffbb927af](https://linux-hardware.org/?probe=8ffbb927af) | Aug 13, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [53a8be279f](https://linux-hardware.org/?probe=53a8be279f) | Aug 12, 2021 |
| Lenovo        | ThinkPad E490 20N8S07A00    | Notebook    | [bd4a6e1eaf](https://linux-hardware.org/?probe=bd4a6e1eaf) | Aug 05, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [c62d162396](https://linux-hardware.org/?probe=c62d162396) | Aug 02, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7b213037a5](https://linux-hardware.org/?probe=7b213037a5) | Jul 31, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [cd96dbf86a](https://linux-hardware.org/?probe=cd96dbf86a) | Jul 30, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [4d91af39ee](https://linux-hardware.org/?probe=4d91af39ee) | Jul 30, 2021 |
| TUXEDO        | TUXEDO_Book_XA1510          | Notebook    | [bc0cfb6203](https://linux-hardware.org/?probe=bc0cfb6203) | Jul 29, 2021 |
| TUXEDO        | P95_HR                      | Notebook    | [60f8b3ac61](https://linux-hardware.org/?probe=60f8b3ac61) | Jul 26, 2021 |
| PC Special... | OctaneVI 15                 | Notebook    | [05e8f69907](https://linux-hardware.org/?probe=05e8f69907) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [6afad8262f](https://linux-hardware.org/?probe=6afad8262f) | Jul 26, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6f7de51af1](https://linux-hardware.org/?probe=6f7de51af1) | Jul 25, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [b983e48d71](https://linux-hardware.org/?probe=b983e48d71) | Jul 24, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [18951b50fd](https://linux-hardware.org/?probe=18951b50fd) | Jul 23, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [2335f32be7](https://linux-hardware.org/?probe=2335f32be7) | Jul 22, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [abea66177f](https://linux-hardware.org/?probe=abea66177f) | Jul 20, 2021 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [157b9695ae](https://linux-hardware.org/?probe=157b9695ae) | Jul 15, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e0f1466068](https://linux-hardware.org/?probe=e0f1466068) | Jul 09, 2021 |
| HP            | 1588h                       | Desktop     | [28a2da9b7f](https://linux-hardware.org/?probe=28a2da9b7f) | Jul 05, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [b2586cfeba](https://linux-hardware.org/?probe=b2586cfeba) | Jul 05, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [19f235e9dd](https://linux-hardware.org/?probe=19f235e9dd) | Jul 04, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [cd4215f3d2](https://linux-hardware.org/?probe=cd4215f3d2) | Jul 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [bbda9475cc](https://linux-hardware.org/?probe=bbda9475cc) | Jul 02, 2021 |
| Dell          | 048DY8 A01                  | Desktop     | [04c41fe4c2](https://linux-hardware.org/?probe=04c41fe4c2) | Jun 30, 2021 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [1c72549a32](https://linux-hardware.org/?probe=1c72549a32) | Jun 29, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [d2d1c6e65e](https://linux-hardware.org/?probe=d2d1c6e65e) | Jun 28, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [5e91d6296d](https://linux-hardware.org/?probe=5e91d6296d) | Jun 27, 2021 |
| Lenovo        | ThinkPad T490 20RY0005US    | Notebook    | [4e3ee76cd4](https://linux-hardware.org/?probe=4e3ee76cd4) | Jun 27, 2021 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [d90efe186a](https://linux-hardware.org/?probe=d90efe186a) | Jun 25, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f8795e30bf](https://linux-hardware.org/?probe=f8795e30bf) | Jun 24, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [143827e2e8](https://linux-hardware.org/?probe=143827e2e8) | Jun 16, 2021 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [ebcfe7dad0](https://linux-hardware.org/?probe=ebcfe7dad0) | Jun 16, 2021 |
| HP            | Notebook                    | Notebook    | [43b2a0f397](https://linux-hardware.org/?probe=43b2a0f397) | Jun 16, 2021 |
| BANGHO        | MAX G5 i1                   | Notebook    | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| HP            | 1998                        | Desktop     | [7b400d8da6](https://linux-hardware.org/?probe=7b400d8da6) | Jun 11, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [f19856109a](https://linux-hardware.org/?probe=f19856109a) | Jun 09, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [a53633e2b1](https://linux-hardware.org/?probe=a53633e2b1) | Jun 09, 2021 |
| HP            | 1998                        | Desktop     | [304ce6f1c4](https://linux-hardware.org/?probe=304ce6f1c4) | Jun 02, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [3984b7401d](https://linux-hardware.org/?probe=3984b7401d) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [0f80210c56](https://linux-hardware.org/?probe=0f80210c56) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | Notebook    | [8f5cb26311](https://linux-hardware.org/?probe=8f5cb26311) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b7f26cced7](https://linux-hardware.org/?probe=b7f26cced7) | Jun 01, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [6a63f48182](https://linux-hardware.org/?probe=6a63f48182) | May 29, 2021 |
| AWOW          | AK41                        | Notebook    | [ca1ba6ce75](https://linux-hardware.org/?probe=ca1ba6ce75) | May 27, 2021 |
| Dell          | Latitude E6410              | Notebook    | [124fdcdccb](https://linux-hardware.org/?probe=124fdcdccb) | May 25, 2021 |
| Dell          | Latitude E6410              | Notebook    | [5715f12aee](https://linux-hardware.org/?probe=5715f12aee) | May 24, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [34d9279028](https://linux-hardware.org/?probe=34d9279028) | May 24, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [d39c5e1f70](https://linux-hardware.org/?probe=d39c5e1f70) | May 23, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [583824ad87](https://linux-hardware.org/?probe=583824ad87) | May 21, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [ad8fffaf05](https://linux-hardware.org/?probe=ad8fffaf05) | May 20, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [75877fb3b1](https://linux-hardware.org/?probe=75877fb3b1) | May 19, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [91cee123e9](https://linux-hardware.org/?probe=91cee123e9) | May 19, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [fb4667be90](https://linux-hardware.org/?probe=fb4667be90) | May 19, 2021 |
| Dell          | Latitude E6540              | Notebook    | [6399cecb6f](https://linux-hardware.org/?probe=6399cecb6f) | May 19, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [5533f32102](https://linux-hardware.org/?probe=5533f32102) | May 18, 2021 |
| Toshiba       | Satellite P300              | Notebook    | [62ac427393](https://linux-hardware.org/?probe=62ac427393) | May 16, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ec195ffe95](https://linux-hardware.org/?probe=ec195ffe95) | May 12, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [69f20a4010](https://linux-hardware.org/?probe=69f20a4010) | May 12, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7aa1f41d1e](https://linux-hardware.org/?probe=7aa1f41d1e) | May 12, 2021 |
| Dell          | Latitude 5480               | Notebook    | [e6d8aca46a](https://linux-hardware.org/?probe=e6d8aca46a) | May 11, 2021 |
| Packard Be... | EasyNote TM98               | Notebook    | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [8260769b47](https://linux-hardware.org/?probe=8260769b47) | May 01, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [a2fb8f6b18](https://linux-hardware.org/?probe=a2fb8f6b18) | May 01, 2021 |
| Dell          | Latitude D531               | Notebook    | [096370a055](https://linux-hardware.org/?probe=096370a055) | Apr 29, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [fbba77b949](https://linux-hardware.org/?probe=fbba77b949) | Apr 28, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [aba1faeb69](https://linux-hardware.org/?probe=aba1faeb69) | Apr 28, 2021 |
| Dell          | Vostro 5460                 | Notebook    | [cf32099d64](https://linux-hardware.org/?probe=cf32099d64) | Apr 27, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [d7318b3c30](https://linux-hardware.org/?probe=d7318b3c30) | Apr 26, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ceee3d709c](https://linux-hardware.org/?probe=ceee3d709c) | Apr 26, 2021 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [289b0a89c0](https://linux-hardware.org/?probe=289b0a89c0) | Apr 25, 2021 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [2c0a43e573](https://linux-hardware.org/?probe=2c0a43e573) | Apr 24, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [28751098a6](https://linux-hardware.org/?probe=28751098a6) | Apr 23, 2021 |
| HP            | Pavilion g6                 | Notebook    | [e22e43c0b5](https://linux-hardware.org/?probe=e22e43c0b5) | Apr 22, 2021 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [c2c4591ef9](https://linux-hardware.org/?probe=c2c4591ef9) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [0d25287be0](https://linux-hardware.org/?probe=0d25287be0) | Apr 16, 2021 |
| TUXEDO        | Polaris 17 AMD Gen1         | Notebook    | [a74abd0b52](https://linux-hardware.org/?probe=a74abd0b52) | Apr 16, 2021 |
| Sony          | SVS13A25PBS                 | Notebook    | [c693fe6603](https://linux-hardware.org/?probe=c693fe6603) | Apr 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09dc9d1375](https://linux-hardware.org/?probe=09dc9d1375) | Apr 14, 2021 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [e0fa7ade7a](https://linux-hardware.org/?probe=e0fa7ade7a) | Apr 06, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9c8b7bc48a](https://linux-hardware.org/?probe=9c8b7bc48a) | Apr 06, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [3c414d527a](https://linux-hardware.org/?probe=3c414d527a) | Apr 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [383e2af37d](https://linux-hardware.org/?probe=383e2af37d) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire E1-431               | Notebook    | [0a6108eb22](https://linux-hardware.org/?probe=0a6108eb22) | Apr 04, 2021 |
| Huanan        | X79 249PC V2.2              | Desktop     | [787866050a](https://linux-hardware.org/?probe=787866050a) | Apr 03, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [104c966a1a](https://linux-hardware.org/?probe=104c966a1a) | Mar 30, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7fbbadb983](https://linux-hardware.org/?probe=7fbbadb983) | Mar 27, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [87168e11ee](https://linux-hardware.org/?probe=87168e11ee) | Mar 26, 2021 |
| Pegatron      | IPI43-TTM                   | Desktop     | [72adf1881e](https://linux-hardware.org/?probe=72adf1881e) | Mar 26, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [f769aaeedd](https://linux-hardware.org/?probe=f769aaeedd) | Mar 26, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| ASUSTek       | Z77-A                       | Desktop     | [ca21510412](https://linux-hardware.org/?probe=ca21510412) | Mar 23, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4c755699d3](https://linux-hardware.org/?probe=4c755699d3) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [835766dc3a](https://linux-hardware.org/?probe=835766dc3a) | Mar 21, 2021 |
| Lenovo        | ThinkPad P43s 20RHS00100    | Notebook    | [fb954b806d](https://linux-hardware.org/?probe=fb954b806d) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [153e336d81](https://linux-hardware.org/?probe=153e336d81) | Mar 21, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [fa3b417784](https://linux-hardware.org/?probe=fa3b417784) | Mar 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [282adc38a9](https://linux-hardware.org/?probe=282adc38a9) | Mar 20, 2021 |
| Unknown       | Unknown                     | Notebook    | [c368ac7bac](https://linux-hardware.org/?probe=c368ac7bac) | Mar 20, 2021 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [83f55d5bf7](https://linux-hardware.org/?probe=83f55d5bf7) | Mar 20, 2021 |
| HP            | 3031h                       | Desktop     | [ee5e7baf77](https://linux-hardware.org/?probe=ee5e7baf77) | Mar 16, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [0cc10a7f8b](https://linux-hardware.org/?probe=0cc10a7f8b) | Mar 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [17a2a64f30](https://linux-hardware.org/?probe=17a2a64f30) | Mar 10, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [26c69c1a34](https://linux-hardware.org/?probe=26c69c1a34) | Mar 07, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [d9cc78fcff](https://linux-hardware.org/?probe=d9cc78fcff) | Mar 07, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [79b5c4e048](https://linux-hardware.org/?probe=79b5c4e048) | Mar 07, 2021 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [2e450a6687](https://linux-hardware.org/?probe=2e450a6687) | Mar 06, 2021 |
| HP            | ENVY 15                     | Notebook    | [5c1bfc1459](https://linux-hardware.org/?probe=5c1bfc1459) | Mar 05, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [12171a4cf1](https://linux-hardware.org/?probe=12171a4cf1) | Mar 04, 2021 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [bc79c52365](https://linux-hardware.org/?probe=bc79c52365) | Mar 04, 2021 |
| Timi          | TM1701                      | Notebook    | [a47b371c00](https://linux-hardware.org/?probe=a47b371c00) | Mar 03, 2021 |
| Dell          | 0KJCC5 A00                  | Desktop     | [5587c00381](https://linux-hardware.org/?probe=5587c00381) | Mar 02, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [d1866f15b4](https://linux-hardware.org/?probe=d1866f15b4) | Mar 02, 2021 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [12212ad362](https://linux-hardware.org/?probe=12212ad362) | Feb 27, 2021 |
| Dell          | Latitude 5590               | Notebook    | [95fa6d8570](https://linux-hardware.org/?probe=95fa6d8570) | Feb 26, 2021 |
| Dell          | Latitude 7490               | Notebook    | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6d24d073b](https://linux-hardware.org/?probe=c6d24d073b) | Feb 25, 2021 |
| Unknown       | Unknown                     | Desktop     | [f97163d774](https://linux-hardware.org/?probe=f97163d774) | Feb 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [290d20ab8b](https://linux-hardware.org/?probe=290d20ab8b) | Feb 23, 2021 |
| HP            | ENVY 15 x360 PC             | Notebook    | [1a67eafe01](https://linux-hardware.org/?probe=1a67eafe01) | Feb 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [ba125a9cb8](https://linux-hardware.org/?probe=ba125a9cb8) | Feb 22, 2021 |
| BCM           | RX965Q                      | Desktop     | [889ee09398](https://linux-hardware.org/?probe=889ee09398) | Feb 21, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [10e0380862](https://linux-hardware.org/?probe=10e0380862) | Feb 19, 2021 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [f747681c25](https://linux-hardware.org/?probe=f747681c25) | Feb 19, 2021 |
| ASUSTek       | H61M-A                      | Desktop     | [2b8de1db1f](https://linux-hardware.org/?probe=2b8de1db1f) | Feb 19, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [745c1185fd](https://linux-hardware.org/?probe=745c1185fd) | Feb 18, 2021 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [ffbb4c8bec](https://linux-hardware.org/?probe=ffbb4c8bec) | Feb 17, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [d470929ba8](https://linux-hardware.org/?probe=d470929ba8) | Feb 14, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [24a9ae34ed](https://linux-hardware.org/?probe=24a9ae34ed) | Feb 13, 2021 |
| Lenovo        | 36F2 SDK0J40700 WIN 3258... | All in one  | [f172b5b1ea](https://linux-hardware.org/?probe=f172b5b1ea) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [5f9a9ff276](https://linux-hardware.org/?probe=5f9a9ff276) | Feb 13, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d8069f1e01](https://linux-hardware.org/?probe=d8069f1e01) | Feb 12, 2021 |
| Lenovo        | ThinkPad P1 20MES01400      | Notebook    | [640ff77fea](https://linux-hardware.org/?probe=640ff77fea) | Feb 11, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [13979999ed](https://linux-hardware.org/?probe=13979999ed) | Feb 07, 2021 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [2028548034](https://linux-hardware.org/?probe=2028548034) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [f48bc9fc78](https://linux-hardware.org/?probe=f48bc9fc78) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [1f3b4b8203](https://linux-hardware.org/?probe=1f3b4b8203) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [005301f0e8](https://linux-hardware.org/?probe=005301f0e8) | Feb 07, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [3ab207950b](https://linux-hardware.org/?probe=3ab207950b) | Feb 06, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [48a778609f](https://linux-hardware.org/?probe=48a778609f) | Feb 06, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [db6b98f685](https://linux-hardware.org/?probe=db6b98f685) | Feb 05, 2021 |
| HP            | ZBook Studio G3             | Notebook    | [6f207e9b7f](https://linux-hardware.org/?probe=6f207e9b7f) | Feb 04, 2021 |
| Dell          | Latitude 5580               | Notebook    | [b9ac308476](https://linux-hardware.org/?probe=b9ac308476) | Feb 04, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [771cb653c6](https://linux-hardware.org/?probe=771cb653c6) | Feb 03, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c94818db0e](https://linux-hardware.org/?probe=c94818db0e) | Feb 03, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | Notebook    | [748cc10c8c](https://linux-hardware.org/?probe=748cc10c8c) | Feb 03, 2021 |
| ASUSTek       | X551CA                      | Notebook    | [1857586e3a](https://linux-hardware.org/?probe=1857586e3a) | Feb 03, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [e4689416a8](https://linux-hardware.org/?probe=e4689416a8) | Feb 02, 2021 |
| Positivo      | C14CR21TV                   | Notebook    | [2133a41335](https://linux-hardware.org/?probe=2133a41335) | Feb 02, 2021 |
| MSI           | Prestige 14 A10SC           | Notebook    | [4af6bad702](https://linux-hardware.org/?probe=4af6bad702) | Jan 31, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3d2867cd98](https://linux-hardware.org/?probe=3d2867cd98) | Jan 30, 2021 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [f519b82ae5](https://linux-hardware.org/?probe=f519b82ae5) | Jan 26, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [47517be667](https://linux-hardware.org/?probe=47517be667) | Jan 23, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2ade08670a](https://linux-hardware.org/?probe=2ade08670a) | Jan 22, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3d5f8c3cd2](https://linux-hardware.org/?probe=3d5f8c3cd2) | Jan 21, 2021 |
| MSI           | GP73 Leopard 8RE            | Notebook    | [c554fa2a9d](https://linux-hardware.org/?probe=c554fa2a9d) | Jan 17, 2021 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [bb89e367c8](https://linux-hardware.org/?probe=bb89e367c8) | Jan 17, 2021 |
| Dell          | XPS L322X                   | Notebook    | [e65c21cdd5](https://linux-hardware.org/?probe=e65c21cdd5) | Jan 16, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [3a07ab383e](https://linux-hardware.org/?probe=3a07ab383e) | Jan 15, 2021 |
| ASUSTek       | N53SM                       | Notebook    | [41bf2f638a](https://linux-hardware.org/?probe=41bf2f638a) | Jan 13, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bb66f59b76](https://linux-hardware.org/?probe=bb66f59b76) | Jan 12, 2021 |
| HP            | 1589                        | Desktop     | [fe93b414cb](https://linux-hardware.org/?probe=fe93b414cb) | Jan 09, 2021 |
| MSI           | GE70 2PC\2PE                | Notebook    | [805e6fac6b](https://linux-hardware.org/?probe=805e6fac6b) | Jan 08, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [92c9f3e6c5](https://linux-hardware.org/?probe=92c9f3e6c5) | Jan 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [276dda536a](https://linux-hardware.org/?probe=276dda536a) | Jan 06, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [e894de170a](https://linux-hardware.org/?probe=e894de170a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [bff63b3c48](https://linux-hardware.org/?probe=bff63b3c48) | Jan 05, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [450e8c59cc](https://linux-hardware.org/?probe=450e8c59cc) | Jan 02, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [4122ea4b04](https://linux-hardware.org/?probe=4122ea4b04) | Jan 02, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [8c4fc87665](https://linux-hardware.org/?probe=8c4fc87665) | Jan 02, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [a80e8c5eb0](https://linux-hardware.org/?probe=a80e8c5eb0) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| eMachines     | EZ1600                      | All in one  | [2c5f74bdac](https://linux-hardware.org/?probe=2c5f74bdac) | Jan 01, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [1effa5938b](https://linux-hardware.org/?probe=1effa5938b) | Dec 31, 2020 |
| Toshiba       | Satellite P750              | Notebook    | [3d7045dbbf](https://linux-hardware.org/?probe=3d7045dbbf) | Dec 28, 2020 |
| eMachines     | EZ1600                      | All in one  | [452894ee3d](https://linux-hardware.org/?probe=452894ee3d) | Dec 28, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0d1e39a79a](https://linux-hardware.org/?probe=0d1e39a79a) | Dec 27, 2020 |
| HP            | Pavilion 17                 | Notebook    | [b07af847e2](https://linux-hardware.org/?probe=b07af847e2) | Dec 26, 2020 |
| eMachines     | EZ1600                      | All in one  | [2181178e2b](https://linux-hardware.org/?probe=2181178e2b) | Dec 25, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [e06953d2f0](https://linux-hardware.org/?probe=e06953d2f0) | Dec 25, 2020 |
| Dell          | 0PK096                      | Desktop     | [e1a520e089](https://linux-hardware.org/?probe=e1a520e089) | Dec 24, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [6260a9fb0f](https://linux-hardware.org/?probe=6260a9fb0f) | Dec 22, 2020 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [4f8b9f90d8](https://linux-hardware.org/?probe=4f8b9f90d8) | Dec 21, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c671dc11ee](https://linux-hardware.org/?probe=c671dc11ee) | Dec 20, 2020 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [c32461bc20](https://linux-hardware.org/?probe=c32461bc20) | Dec 19, 2020 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [c85ead3218](https://linux-hardware.org/?probe=c85ead3218) | Dec 19, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [05c93972e0](https://linux-hardware.org/?probe=05c93972e0) | Dec 16, 2020 |
| Unknown       | Unknown                     | Notebook    | [e81e3d85d6](https://linux-hardware.org/?probe=e81e3d85d6) | Dec 15, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [ff0cd7f2bc](https://linux-hardware.org/?probe=ff0cd7f2bc) | Dec 13, 2020 |
| ASUSTek       | F9E                         | Notebook    | [0070b5eda7](https://linux-hardware.org/?probe=0070b5eda7) | Dec 12, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [27239584b2](https://linux-hardware.org/?probe=27239584b2) | Dec 12, 2020 |
| HP            | EliteBook 850 G1            | Notebook    | [671d151ab9](https://linux-hardware.org/?probe=671d151ab9) | Dec 12, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [a603cda0d7](https://linux-hardware.org/?probe=a603cda0d7) | Dec 12, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [8937271376](https://linux-hardware.org/?probe=8937271376) | Dec 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c04e40195e](https://linux-hardware.org/?probe=c04e40195e) | Dec 11, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [ccb7d3edd7](https://linux-hardware.org/?probe=ccb7d3edd7) | Dec 10, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [d65d3733f6](https://linux-hardware.org/?probe=d65d3733f6) | Dec 07, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [25ff6d84d0](https://linux-hardware.org/?probe=25ff6d84d0) | Dec 07, 2020 |
| HP            | Pavilion dv1000 (EW999LA... | Notebook    | [6675bde630](https://linux-hardware.org/?probe=6675bde630) | Dec 07, 2020 |
| ASRock        | P67 Extreme4                | Desktop     | [ca2f3a785a](https://linux-hardware.org/?probe=ca2f3a785a) | Dec 06, 2020 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [d47823099d](https://linux-hardware.org/?probe=d47823099d) | Dec 02, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [465bfd7567](https://linux-hardware.org/?probe=465bfd7567) | Nov 28, 2020 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [77dc96c206](https://linux-hardware.org/?probe=77dc96c206) | Nov 27, 2020 |
| LattePanda    | Alpha                       | Desktop     | [706f930815](https://linux-hardware.org/?probe=706f930815) | Nov 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [c620f65d2b](https://linux-hardware.org/?probe=c620f65d2b) | Nov 25, 2020 |
| Acer          | Aspire E1-532               | Notebook    | [c4db9a001e](https://linux-hardware.org/?probe=c4db9a001e) | Nov 25, 2020 |
| LattePanda    | Alpha                       | Desktop     | [a5c3e54e65](https://linux-hardware.org/?probe=a5c3e54e65) | Nov 24, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [f391747dd0](https://linux-hardware.org/?probe=f391747dd0) | Nov 24, 2020 |
| Gigabyte      | 970A-D3P                    | Desktop     | [304945ac43](https://linux-hardware.org/?probe=304945ac43) | Nov 23, 2020 |
| Packard Be... | EasyNote LE69KB             | Notebook    | [0afa851fa7](https://linux-hardware.org/?probe=0afa851fa7) | Nov 22, 2020 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [8bbc1a2d1c](https://linux-hardware.org/?probe=8bbc1a2d1c) | Nov 22, 2020 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [732043cc5f](https://linux-hardware.org/?probe=732043cc5f) | Nov 21, 2020 |
| ASUSTek       | P8Z68-V                     | Desktop     | [643bb20dc1](https://linux-hardware.org/?probe=643bb20dc1) | Nov 20, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [81d47c5bbd](https://linux-hardware.org/?probe=81d47c5bbd) | Nov 14, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e51b8a2e3d](https://linux-hardware.org/?probe=e51b8a2e3d) | Nov 14, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7e8af2342a](https://linux-hardware.org/?probe=7e8af2342a) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [d95e3b8198](https://linux-hardware.org/?probe=d95e3b8198) | Nov 12, 2020 |
| ASUSTek       | K52De                       | Notebook    | [9aec230d46](https://linux-hardware.org/?probe=9aec230d46) | Nov 12, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [bb3de0e33d](https://linux-hardware.org/?probe=bb3de0e33d) | Nov 08, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [3d1548beea](https://linux-hardware.org/?probe=3d1548beea) | Nov 06, 2020 |
| Sony          | SVS13A25PBS                 | Notebook    | [ec54069f90](https://linux-hardware.org/?probe=ec54069f90) | Nov 06, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [ccab34bcd7](https://linux-hardware.org/?probe=ccab34bcd7) | Nov 03, 2020 |
| Lenovo        | IdeaPad S100 20109          | Notebook    | [8f26323f1e](https://linux-hardware.org/?probe=8f26323f1e) | Nov 02, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [f403df4c45](https://linux-hardware.org/?probe=f403df4c45) | Nov 01, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [2e03e273f1](https://linux-hardware.org/?probe=2e03e273f1) | Oct 31, 2020 |
| Lenovo        | ThinkPad L450 20DT001HUK    | Notebook    | [4a619e003e](https://linux-hardware.org/?probe=4a619e003e) | Oct 31, 2020 |
| Gigabyte      | TRX40 DESIGNARE             | Desktop     | [eb2134b274](https://linux-hardware.org/?probe=eb2134b274) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [e59b548946](https://linux-hardware.org/?probe=e59b548946) | Oct 31, 2020 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [39348ac053](https://linux-hardware.org/?probe=39348ac053) | Oct 31, 2020 |
| Apple         | Mac-F2218FC8                | All in one  | [b72a5d9506](https://linux-hardware.org/?probe=b72a5d9506) | Oct 31, 2020 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [58b6426d57](https://linux-hardware.org/?probe=58b6426d57) | Oct 30, 2020 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [7e515b01ea](https://linux-hardware.org/?probe=7e515b01ea) | Oct 30, 2020 |
| Acer          | Aspire SW3-016              | Notebook    | [be195992d0](https://linux-hardware.org/?probe=be195992d0) | Oct 30, 2020 |
| Dell          | Latitude E6540              | Notebook    | [45ad219146](https://linux-hardware.org/?probe=45ad219146) | Oct 29, 2020 |
| ASUSTek       | TUF GAMING X570-PLUS        | Desktop     | [aead0dde26](https://linux-hardware.org/?probe=aead0dde26) | Oct 27, 2020 |
| HP            | ZBook 14                    | Notebook    | [b282051085](https://linux-hardware.org/?probe=b282051085) | Oct 27, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [7a593747a4](https://linux-hardware.org/?probe=7a593747a4) | Oct 26, 2020 |
| HP            | Elite x2 1012 G1            | Notebook    | [82ff46fe7f](https://linux-hardware.org/?probe=82ff46fe7f) | Oct 26, 2020 |
| HP            | Stream 7 Tablet             | Tablet      | [1cb5fb4518](https://linux-hardware.org/?probe=1cb5fb4518) | Oct 25, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [b5a98b7ffa](https://linux-hardware.org/?probe=b5a98b7ffa) | Oct 24, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [a5246866a5](https://linux-hardware.org/?probe=a5246866a5) | Oct 21, 2020 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [19879c3493](https://linux-hardware.org/?probe=19879c3493) | Oct 21, 2020 |
| Dell          | Latitude 5400               | Notebook    | [9594ef7488](https://linux-hardware.org/?probe=9594ef7488) | Oct 20, 2020 |
| Dell          | Latitude 5400               | Notebook    | [d016f37257](https://linux-hardware.org/?probe=d016f37257) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [e8076a87a0](https://linux-hardware.org/?probe=e8076a87a0) | Oct 20, 2020 |
| HP            | 1998                        | Desktop     | [69ed04c55d](https://linux-hardware.org/?probe=69ed04c55d) | Oct 20, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [25565a3bbf](https://linux-hardware.org/?probe=25565a3bbf) | Oct 19, 2020 |
| Apple         | Mac-F4208DC8 PVT            | Desktop     | [3aa954c07b](https://linux-hardware.org/?probe=3aa954c07b) | Oct 19, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7c78d9b4da](https://linux-hardware.org/?probe=7c78d9b4da) | Oct 18, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ca85fa1d88](https://linux-hardware.org/?probe=ca85fa1d88) | Oct 18, 2020 |
| ASRock        | Q1900B-ITX                  | Desktop     | [527411a589](https://linux-hardware.org/?probe=527411a589) | Oct 15, 2020 |
| Unknown       | Unknown                     | Desktop     | [f82db8cb1c](https://linux-hardware.org/?probe=f82db8cb1c) | Oct 13, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [3d2cb2e4d1](https://linux-hardware.org/?probe=3d2cb2e4d1) | Oct 12, 2020 |
| AAEON         | UP-APL01 V0.4               | Desktop     | [16d3bf5578](https://linux-hardware.org/?probe=16d3bf5578) | Oct 12, 2020 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [9d2f2dbd87](https://linux-hardware.org/?probe=9d2f2dbd87) | Oct 12, 2020 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [2f2b699bf6](https://linux-hardware.org/?probe=2f2b699bf6) | Oct 11, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| Lenovo        | 20SL                        | Notebook    | [bda45231ce](https://linux-hardware.org/?probe=bda45231ce) | Oct 07, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [3f17f3c6e8](https://linux-hardware.org/?probe=3f17f3c6e8) | Oct 06, 2020 |
| TUXEDO        | P7xxTM1                     | Notebook    | [1c64a38e1e](https://linux-hardware.org/?probe=1c64a38e1e) | Oct 05, 2020 |
| Dell          | 0M9KCM A00                  | Desktop     | [f884d19586](https://linux-hardware.org/?probe=f884d19586) | Oct 02, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [4a62de4c07](https://linux-hardware.org/?probe=4a62de4c07) | Oct 01, 2020 |
| MSI           | Modern 14 A10RB             | Notebook    | [67d9e1d5e4](https://linux-hardware.org/?probe=67d9e1d5e4) | Sep 30, 2020 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [a996c3d55c](https://linux-hardware.org/?probe=a996c3d55c) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | UX430UQ                     | Notebook    | [c201929d1a](https://linux-hardware.org/?probe=c201929d1a) | Sep 27, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [5b7738af52](https://linux-hardware.org/?probe=5b7738af52) | Sep 23, 2020 |
| Dell          | Latitude 5400               | Notebook    | [763c1287a5](https://linux-hardware.org/?probe=763c1287a5) | Sep 23, 2020 |
| Dell          | 0RY007                      | Desktop     | [b1ca551538](https://linux-hardware.org/?probe=b1ca551538) | Sep 22, 2020 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [663a5ef41a](https://linux-hardware.org/?probe=663a5ef41a) | Sep 21, 2020 |
| Dell          | 0200DY A03                  | Desktop     | [e91f9c04b9](https://linux-hardware.org/?probe=e91f9c04b9) | Sep 21, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [d746ae5a52](https://linux-hardware.org/?probe=d746ae5a52) | Sep 19, 2020 |
| HP            | ProBook 4730s               | Notebook    | [4363da5d51](https://linux-hardware.org/?probe=4363da5d51) | Sep 19, 2020 |
| Dell          | Inspiron 7560               | Notebook    | [4a1a3140a7](https://linux-hardware.org/?probe=4a1a3140a7) | Sep 15, 2020 |
| Radxa         | ROCK Pi 4A                  | Soc         | [b335776d4a](https://linux-hardware.org/?probe=b335776d4a) | Sep 14, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1037d2b746](https://linux-hardware.org/?probe=1037d2b746) | Sep 09, 2020 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [b3d6fb36eb](https://linux-hardware.org/?probe=b3d6fb36eb) | Sep 08, 2020 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [0ce417fed7](https://linux-hardware.org/?probe=0ce417fed7) | Sep 08, 2020 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [d36f3124d1](https://linux-hardware.org/?probe=d36f3124d1) | Sep 06, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [e90f4fb0e5](https://linux-hardware.org/?probe=e90f4fb0e5) | Sep 06, 2020 |
| PCSMART       | 6.0                         | Desktop     | [e95fadbdfe](https://linux-hardware.org/?probe=e95fadbdfe) | Sep 05, 2020 |
| MSI           | Z97 GAMING 5                | Desktop     | [3f1b387a92](https://linux-hardware.org/?probe=3f1b387a92) | Sep 04, 2020 |
| HP            | Pavilion g6                 | Notebook    | [522ff3c9c7](https://linux-hardware.org/?probe=522ff3c9c7) | Sep 03, 2020 |
| Dell          | G7 7588                     | Notebook    | [d6cd49b568](https://linux-hardware.org/?probe=d6cd49b568) | Sep 02, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [bc9c588fd8](https://linux-hardware.org/?probe=bc9c588fd8) | Aug 30, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [5377671241](https://linux-hardware.org/?probe=5377671241) | Aug 27, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [2ceaeaf356](https://linux-hardware.org/?probe=2ceaeaf356) | Aug 27, 2020 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [ed4a78cd06](https://linux-hardware.org/?probe=ed4a78cd06) | Aug 24, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [bf9ae88e59](https://linux-hardware.org/?probe=bf9ae88e59) | Aug 20, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [c168661ada](https://linux-hardware.org/?probe=c168661ada) | Aug 20, 2020 |
| ASUSTek       | U47A                        | Notebook    | [39d5bde56a](https://linux-hardware.org/?probe=39d5bde56a) | Aug 19, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [957889f93d](https://linux-hardware.org/?probe=957889f93d) | Aug 18, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [75f32f4978](https://linux-hardware.org/?probe=75f32f4978) | Aug 16, 2020 |
| Sony          | VPCEK20AL                   | Notebook    | [2147eeff89](https://linux-hardware.org/?probe=2147eeff89) | Aug 16, 2020 |
| MSI           | Prestige 15 A10SC           | Notebook    | [4cea086204](https://linux-hardware.org/?probe=4cea086204) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [d24b0f8f6a](https://linux-hardware.org/?probe=d24b0f8f6a) | Aug 16, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [2703fac7a8](https://linux-hardware.org/?probe=2703fac7a8) | Aug 16, 2020 |
| Dell          | Inspiron 11-3168            | Notebook    | [6bdfa3f1ad](https://linux-hardware.org/?probe=6bdfa3f1ad) | Aug 16, 2020 |
| ASUSTek       | U47A                        | Notebook    | [55022416f8](https://linux-hardware.org/?probe=55022416f8) | Aug 14, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [ac036c1715](https://linux-hardware.org/?probe=ac036c1715) | Aug 14, 2020 |
| ASUSTek       | U47A                        | Notebook    | [1c4676a5d6](https://linux-hardware.org/?probe=1c4676a5d6) | Aug 13, 2020 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [c908fd4599](https://linux-hardware.org/?probe=c908fd4599) | Aug 07, 2020 |
| Standard      | MT40II                      | Notebook    | [974f5398ca](https://linux-hardware.org/?probe=974f5398ca) | Aug 06, 2020 |
| Lenovo        | ThinkPad T430s 23539WU      | Notebook    | [3ff86ae696](https://linux-hardware.org/?probe=3ff86ae696) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [5caeef5a4f](https://linux-hardware.org/?probe=5caeef5a4f) | Aug 03, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [89e1df883c](https://linux-hardware.org/?probe=89e1df883c) | Aug 01, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [545f6ed65f](https://linux-hardware.org/?probe=545f6ed65f) | Jul 31, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [d943208a7c](https://linux-hardware.org/?probe=d943208a7c) | Jul 30, 2020 |
| Apple         | MacBook3,1                  | Notebook    | [7da122d44a](https://linux-hardware.org/?probe=7da122d44a) | Jul 29, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [cb5d511453](https://linux-hardware.org/?probe=cb5d511453) | Jul 28, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [999f65d55e](https://linux-hardware.org/?probe=999f65d55e) | Jul 28, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [87d7bc3077](https://linux-hardware.org/?probe=87d7bc3077) | Jul 28, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [6a0fabe139](https://linux-hardware.org/?probe=6a0fabe139) | Jul 28, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [ad54591d3a](https://linux-hardware.org/?probe=ad54591d3a) | Jul 27, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [ccd785c473](https://linux-hardware.org/?probe=ccd785c473) | Jul 27, 2020 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [f38e8a0201](https://linux-hardware.org/?probe=f38e8a0201) | Jul 26, 2020 |
| HP            | 82F2                        | Desktop     | [172d6aed2a](https://linux-hardware.org/?probe=172d6aed2a) | Jul 26, 2020 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [0479f5e75d](https://linux-hardware.org/?probe=0479f5e75d) | Jul 26, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [2e6c21ed23](https://linux-hardware.org/?probe=2e6c21ed23) | Jul 26, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4f80b590f5](https://linux-hardware.org/?probe=4f80b590f5) | Jul 25, 2020 |
| HP            | Pavilion 14                 | Notebook    | [3243fbe29b](https://linux-hardware.org/?probe=3243fbe29b) | Jul 25, 2020 |
| HP            | Pavilion dv6                | Notebook    | [24b46efa49](https://linux-hardware.org/?probe=24b46efa49) | Jul 25, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [dd251c0a0c](https://linux-hardware.org/?probe=dd251c0a0c) | Jul 25, 2020 |
| Dell          | Latitude E6320              | Notebook    | [d9ac43486e](https://linux-hardware.org/?probe=d9ac43486e) | Jul 25, 2020 |
| HP            | 3397                        | Desktop     | [edd52c2428](https://linux-hardware.org/?probe=edd52c2428) | Jul 24, 2020 |
| HP            | 3397                        | Desktop     | [20b3d353d8](https://linux-hardware.org/?probe=20b3d353d8) | Jul 24, 2020 |
| Gigabyte      | H61M-S1                     | Desktop     | [3ce4143dee](https://linux-hardware.org/?probe=3ce4143dee) | Jul 24, 2020 |
| Dell          | G3 3579                     | Notebook    | [b129bccbcf](https://linux-hardware.org/?probe=b129bccbcf) | Jul 24, 2020 |
| Dell          | G7 7588                     | Notebook    | [cb6c4a378b](https://linux-hardware.org/?probe=cb6c4a378b) | Jul 24, 2020 |
| Dell          | Inspiron 5437               | Notebook    | [bae63d5905](https://linux-hardware.org/?probe=bae63d5905) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [a4ff18fb01](https://linux-hardware.org/?probe=a4ff18fb01) | Jul 24, 2020 |
| Acer          | Aspire A315-41              | Notebook    | [689b63d743](https://linux-hardware.org/?probe=689b63d743) | Jul 24, 2020 |
| ASUSTek       | K53E                        | Notebook    | [965c0a5e03](https://linux-hardware.org/?probe=965c0a5e03) | Jul 20, 2020 |
| MSI           | GL62M 7RD                   | Notebook    | [ddfb055569](https://linux-hardware.org/?probe=ddfb055569) | Jul 18, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [12a4926d36](https://linux-hardware.org/?probe=12a4926d36) | Jul 17, 2020 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [534a204796](https://linux-hardware.org/?probe=534a204796) | Jul 17, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [fcc0f73453](https://linux-hardware.org/?probe=fcc0f73453) | Jul 15, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [7d642bd7dc](https://linux-hardware.org/?probe=7d642bd7dc) | Jul 14, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [76752b2d00](https://linux-hardware.org/?probe=76752b2d00) | Jul 13, 2020 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [8639032305](https://linux-hardware.org/?probe=8639032305) | Jul 13, 2020 |
| Dell          | 0P301D A02                  | Desktop     | [709ca37e1e](https://linux-hardware.org/?probe=709ca37e1e) | Jul 12, 2020 |
| MSI           | GP72 7RE                    | Notebook    | [66efd09dbc](https://linux-hardware.org/?probe=66efd09dbc) | Jul 12, 2020 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [c7cdebaa45](https://linux-hardware.org/?probe=c7cdebaa45) | Jul 09, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [a8f39d2061](https://linux-hardware.org/?probe=a8f39d2061) | Jul 08, 2020 |
| HP            | EliteBook 840 G6            | Notebook    | [1a175eee47](https://linux-hardware.org/?probe=1a175eee47) | Jul 07, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [803b8c9adc](https://linux-hardware.org/?probe=803b8c9adc) | Jul 06, 2020 |
| Dell          | Inspiron 3537               | Notebook    | [38640e68c7](https://linux-hardware.org/?probe=38640e68c7) | Jul 06, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [e2f2937842](https://linux-hardware.org/?probe=e2f2937842) | Jul 05, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e6480fdb93](https://linux-hardware.org/?probe=e6480fdb93) | Jul 04, 2020 |
| Dell          | XPS L401X                   | Notebook    | [291b1c0a01](https://linux-hardware.org/?probe=291b1c0a01) | Jul 03, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [c67e3d5b3d](https://linux-hardware.org/?probe=c67e3d5b3d) | Jul 02, 2020 |
| ASUSTek       | M51AC                       | Desktop     | [6af32ff946](https://linux-hardware.org/?probe=6af32ff946) | Jul 01, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [dd10caa4c9](https://linux-hardware.org/?probe=dd10caa4c9) | Jun 26, 2020 |
| Dell          | Latitude E6220              | Notebook    | [2177469041](https://linux-hardware.org/?probe=2177469041) | Jun 25, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [33d1532efd](https://linux-hardware.org/?probe=33d1532efd) | Jun 23, 2020 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [110bf098e8](https://linux-hardware.org/?probe=110bf098e8) | Jun 22, 2020 |
| Dell          | 09KPNV A00                  | Desktop     | [9f63cccd5c](https://linux-hardware.org/?probe=9f63cccd5c) | Jun 21, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a9c582ba02](https://linux-hardware.org/?probe=a9c582ba02) | Jun 19, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [311c0852f2](https://linux-hardware.org/?probe=311c0852f2) | Jun 18, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [b51cceda3f](https://linux-hardware.org/?probe=b51cceda3f) | Jun 17, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [52d48f4c11](https://linux-hardware.org/?probe=52d48f4c11) | Jun 17, 2020 |
| TUXEDO        | InfinityBook Pro 15 v4      | Notebook    | [7d351b71dc](https://linux-hardware.org/?probe=7d351b71dc) | Jun 17, 2020 |
| HP            | ENVY 17                     | Notebook    | [8ee27ae156](https://linux-hardware.org/?probe=8ee27ae156) | Jun 16, 2020 |
| Dell          | Inspiron 7590               | Notebook    | [1e4d9a97b8](https://linux-hardware.org/?probe=1e4d9a97b8) | Jun 15, 2020 |
| Sony          | VPCCW25FL                   | Notebook    | [2e9d3ed45b](https://linux-hardware.org/?probe=2e9d3ed45b) | Jun 14, 2020 |
| HP            | ENVY 17                     | Notebook    | [6717ca8025](https://linux-hardware.org/?probe=6717ca8025) | Jun 14, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [7c4e814d03](https://linux-hardware.org/?probe=7c4e814d03) | Jun 13, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [10875bae28](https://linux-hardware.org/?probe=10875bae28) | Jun 13, 2020 |
| Acer          | Aspire V3-572G              | Notebook    | [d780f9b6ef](https://linux-hardware.org/?probe=d780f9b6ef) | Jun 13, 2020 |
| ASUSTek       | X540LA                      | Notebook    | [99651c1c86](https://linux-hardware.org/?probe=99651c1c86) | Jun 12, 2020 |
| HP            | ENVY 17                     | Notebook    | [19571ad1c9](https://linux-hardware.org/?probe=19571ad1c9) | Jun 11, 2020 |
| HP            | ENVY 15                     | Notebook    | [3fa91961e1](https://linux-hardware.org/?probe=3fa91961e1) | Jun 07, 2020 |
| HP            | ENVY 17                     | Notebook    | [16c895ce30](https://linux-hardware.org/?probe=16c895ce30) | Jun 07, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [95097be9d3](https://linux-hardware.org/?probe=95097be9d3) | Jun 02, 2020 |
| Acer          | Aspire ZC-105               | All in one  | [42b2dbab31](https://linux-hardware.org/?probe=42b2dbab31) | Jun 01, 2020 |
| Lenovo        | ThinkPad X230 23257G6       | Notebook    | [d4c8c1735b](https://linux-hardware.org/?probe=d4c8c1735b) | May 31, 2020 |
| HUAWEI        | MACH-WX9                    | Notebook    | [f3ca082840](https://linux-hardware.org/?probe=f3ca082840) | May 31, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6ad038b762](https://linux-hardware.org/?probe=6ad038b762) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [fbbc2c4d98](https://linux-hardware.org/?probe=fbbc2c4d98) | May 30, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [ca71847ca1](https://linux-hardware.org/?probe=ca71847ca1) | May 30, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [3552bfc82b](https://linux-hardware.org/?probe=3552bfc82b) | May 29, 2020 |
| HP            | ENVY 17                     | Notebook    | [0bb6be8c85](https://linux-hardware.org/?probe=0bb6be8c85) | May 27, 2020 |
| HP            | ENVY 17                     | Notebook    | [4f1caa50f6](https://linux-hardware.org/?probe=4f1caa50f6) | May 27, 2020 |
| Lenovo        | ThinkPad X260 20F5S2HF06    | Notebook    | [fb34ca6c06](https://linux-hardware.org/?probe=fb34ca6c06) | May 26, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [49486e2abf](https://linux-hardware.org/?probe=49486e2abf) | May 24, 2020 |
| Lenovo        | ThinkPad T430 2349P74       | Notebook    | [50dbda3211](https://linux-hardware.org/?probe=50dbda3211) | May 21, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [cdaf886b58](https://linux-hardware.org/?probe=cdaf886b58) | May 20, 2020 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [e8b5bf55c7](https://linux-hardware.org/?probe=e8b5bf55c7) | May 20, 2020 |
| ASUSTek       | S400CA                      | Notebook    | [3e3bb3f13e](https://linux-hardware.org/?probe=3e3bb3f13e) | May 19, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [23cb30a022](https://linux-hardware.org/?probe=23cb30a022) | May 16, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [d28985973f](https://linux-hardware.org/?probe=d28985973f) | May 16, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [7eea93aa65](https://linux-hardware.org/?probe=7eea93aa65) | May 16, 2020 |
| Dell          | 0J32FG A06                  | Desktop     | [d5d2970bc5](https://linux-hardware.org/?probe=d5d2970bc5) | May 15, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [70c167639c](https://linux-hardware.org/?probe=70c167639c) | May 15, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [9eb9f125bf](https://linux-hardware.org/?probe=9eb9f125bf) | May 15, 2020 |
| Dell          | Latitude 5400               | Notebook    | [cfdf75da7b](https://linux-hardware.org/?probe=cfdf75da7b) | May 14, 2020 |
| Acer          | Swift SF315-52              | Notebook    | [39a7bd47d7](https://linux-hardware.org/?probe=39a7bd47d7) | May 12, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [4e4bcc14f1](https://linux-hardware.org/?probe=4e4bcc14f1) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [e4d76f72dc](https://linux-hardware.org/?probe=e4d76f72dc) | May 11, 2020 |
| Lenovo        | G550 2958                   | Notebook    | [ea8d2d9296](https://linux-hardware.org/?probe=ea8d2d9296) | May 11, 2020 |
| Dell          | 0TNXNR A01                  | Desktop     | [c16ecd859c](https://linux-hardware.org/?probe=c16ecd859c) | May 11, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [f06dc42b2a](https://linux-hardware.org/?probe=f06dc42b2a) | May 10, 2020 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [eb7d6f2ec3](https://linux-hardware.org/?probe=eb7d6f2ec3) | May 10, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [36f3db3281](https://linux-hardware.org/?probe=36f3db3281) | May 10, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [3a72ff2108](https://linux-hardware.org/?probe=3a72ff2108) | May 09, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [e9d31442df](https://linux-hardware.org/?probe=e9d31442df) | May 09, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [51bb777f10](https://linux-hardware.org/?probe=51bb777f10) | May 08, 2020 |
| ASUSTek       | S551LN                      | Notebook    | [b81e2e0679](https://linux-hardware.org/?probe=b81e2e0679) | May 08, 2020 |
| Quanta        | QL3 TBD                     | Notebook    | [680a32b94c](https://linux-hardware.org/?probe=680a32b94c) | May 08, 2020 |
| Gigabyte      | GB-BKi7A-7500               | Notebook    | [a4c4bc09fb](https://linux-hardware.org/?probe=a4c4bc09fb) | May 08, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [5c81f4ef61](https://linux-hardware.org/?probe=5c81f4ef61) | May 07, 2020 |
| ASUSTek       | G55VW                       | Notebook    | [9cb0c68aa1](https://linux-hardware.org/?probe=9cb0c68aa1) | May 07, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [e2fca9899f](https://linux-hardware.org/?probe=e2fca9899f) | May 07, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [0b67b7c423](https://linux-hardware.org/?probe=0b67b7c423) | May 06, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [6fc5f4e0be](https://linux-hardware.org/?probe=6fc5f4e0be) | May 06, 2020 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [2e108e8f82](https://linux-hardware.org/?probe=2e108e8f82) | May 06, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [181868c1fe](https://linux-hardware.org/?probe=181868c1fe) | May 05, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ac74330be2](https://linux-hardware.org/?probe=ac74330be2) | May 03, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [1778c8dba1](https://linux-hardware.org/?probe=1778c8dba1) | May 03, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [e2ab63b529](https://linux-hardware.org/?probe=e2ab63b529) | May 02, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c17fa3f327](https://linux-hardware.org/?probe=c17fa3f327) | May 02, 2020 |
| HP            | Notebook                    | Notebook    | [d666fee133](https://linux-hardware.org/?probe=d666fee133) | May 02, 2020 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [f5c70a1643](https://linux-hardware.org/?probe=f5c70a1643) | Apr 30, 2020 |
| Lenovo        | ThinkPad W530 2447GW3       | Notebook    | [69f36d1be1](https://linux-hardware.org/?probe=69f36d1be1) | Apr 30, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [7db8dc0e44](https://linux-hardware.org/?probe=7db8dc0e44) | Apr 28, 2020 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [6982ff0a12](https://linux-hardware.org/?probe=6982ff0a12) | Apr 25, 2020 |
| Lenovo        | ThinkPad X230 2306CTO       | Notebook    | [80111dac4b](https://linux-hardware.org/?probe=80111dac4b) | Apr 24, 2020 |
| Dell          | Latitude 5400               | Notebook    | [7319cff553](https://linux-hardware.org/?probe=7319cff553) | Apr 22, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [cba2c66659](https://linux-hardware.org/?probe=cba2c66659) | Apr 20, 2020 |
| HP            | 0A80h                       | Desktop     | [f51e29fc6f](https://linux-hardware.org/?probe=f51e29fc6f) | Apr 13, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e2fabad799](https://linux-hardware.org/?probe=e2fabad799) | Apr 13, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [3db29a7f67](https://linux-hardware.org/?probe=3db29a7f67) | Apr 12, 2020 |
| ASRock        | N68C-S UCC                  | Desktop     | [c6df4257a4](https://linux-hardware.org/?probe=c6df4257a4) | Apr 11, 2020 |
| Lenovo        | ThinkPad T410 2537H21       | Notebook    | [0140b2344a](https://linux-hardware.org/?probe=0140b2344a) | Apr 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [d39e8563ca](https://linux-hardware.org/?probe=d39e8563ca) | Apr 07, 2020 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [f309322c77](https://linux-hardware.org/?probe=f309322c77) | Apr 04, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [c17da47049](https://linux-hardware.org/?probe=c17da47049) | Apr 03, 2020 |
| HP            | Spectre x360 Convertible... | Convertible | [18f447ca5d](https://linux-hardware.org/?probe=18f447ca5d) | Apr 03, 2020 |
| HP            | 8433 11                     | Desktop     | [e20dd4e4a3](https://linux-hardware.org/?probe=e20dd4e4a3) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [eafaace7ee](https://linux-hardware.org/?probe=eafaace7ee) | Apr 02, 2020 |
| HP            | 8433 11                     | Desktop     | [0e29f294ba](https://linux-hardware.org/?probe=0e29f294ba) | Apr 02, 2020 |
| HP            | 84EE 1100                   | All in one  | [870857c93c](https://linux-hardware.org/?probe=870857c93c) | Mar 30, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [5a5984be1c](https://linux-hardware.org/?probe=5a5984be1c) | Mar 29, 2020 |
| Dell          | Inspiron 5770               | Notebook    | [afcbaaf5c5](https://linux-hardware.org/?probe=afcbaaf5c5) | Mar 29, 2020 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [5b8ef620f7](https://linux-hardware.org/?probe=5b8ef620f7) | Mar 27, 2020 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [384177f515](https://linux-hardware.org/?probe=384177f515) | Mar 23, 2020 |
| HP            | Compaq 6720s                | Notebook    | [7a81993a9b](https://linux-hardware.org/?probe=7a81993a9b) | Mar 22, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [477afd03f4](https://linux-hardware.org/?probe=477afd03f4) | Mar 21, 2020 |
| Dell          | 0J32FG A06                  | Desktop     | [efb8737ca2](https://linux-hardware.org/?probe=efb8737ca2) | Mar 20, 2020 |
| Lenovo        | ThinkPad P53 20QQS1JE00     | Notebook    | [6692834531](https://linux-hardware.org/?probe=6692834531) | Mar 18, 2020 |
| ASUSTek       | X750JB                      | Notebook    | [6d8e7e2bf9](https://linux-hardware.org/?probe=6d8e7e2bf9) | Mar 15, 2020 |
| MSI           | Z270-A PRO                  | Desktop     | [5e41eb4c66](https://linux-hardware.org/?probe=5e41eb4c66) | Mar 14, 2020 |
| Dell          | Latitude 5400               | Notebook    | [3bda0aef33](https://linux-hardware.org/?probe=3bda0aef33) | Mar 14, 2020 |
| HP            | 2000                        | Notebook    | [fa3539bb75](https://linux-hardware.org/?probe=fa3539bb75) | Mar 14, 2020 |
| Standard      | MT40II                      | Notebook    | [f11c251d38](https://linux-hardware.org/?probe=f11c251d38) | Mar 13, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [210b1c0abf](https://linux-hardware.org/?probe=210b1c0abf) | Mar 13, 2020 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [9ca13583bb](https://linux-hardware.org/?probe=9ca13583bb) | Mar 09, 2020 |
| Dell          | Latitude E6420              | Notebook    | [7653562a2f](https://linux-hardware.org/?probe=7653562a2f) | Mar 07, 2020 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | Notebook    | [c4b9b4ab26](https://linux-hardware.org/?probe=c4b9b4ab26) | Mar 07, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e008a514e](https://linux-hardware.org/?probe=1e008a514e) | Mar 06, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [01c8982ddb](https://linux-hardware.org/?probe=01c8982ddb) | Mar 06, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [4b844d95eb](https://linux-hardware.org/?probe=4b844d95eb) | Mar 05, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [b88f46d2eb](https://linux-hardware.org/?probe=b88f46d2eb) | Mar 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [1dba6c5acf](https://linux-hardware.org/?probe=1dba6c5acf) | Mar 03, 2020 |
| Dell          | XPS 13 9380                 | Notebook    | [5a7b311c84](https://linux-hardware.org/?probe=5a7b311c84) | Mar 02, 2020 |
| ASUSTek       | N751JK                      | Notebook    | [a08a81ed83](https://linux-hardware.org/?probe=a08a81ed83) | Mar 01, 2020 |
| eMachines     | EL1852G                     | Desktop     | [e90ac3f652](https://linux-hardware.org/?probe=e90ac3f652) | Feb 27, 2020 |
| HP            | ENVY x360 Convertible       | Convertible | [d98a9e0c48](https://linux-hardware.org/?probe=d98a9e0c48) | Feb 27, 2020 |
| Intel         | DQ965CO AAD34641-506        | Desktop     | [3c3c53b8e5](https://linux-hardware.org/?probe=3c3c53b8e5) | Feb 26, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [435f7d1017](https://linux-hardware.org/?probe=435f7d1017) | Feb 21, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [45382a84f3](https://linux-hardware.org/?probe=45382a84f3) | Feb 21, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [002a2b6abe](https://linux-hardware.org/?probe=002a2b6abe) | Feb 21, 2020 |
| HP            | 2215                        | Desktop     | [f9ecf106d2](https://linux-hardware.org/?probe=f9ecf106d2) | Feb 19, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [9e101537c5](https://linux-hardware.org/?probe=9e101537c5) | Feb 17, 2020 |
| Acer          | Veriton L4610G              | Desktop     | [e38723516e](https://linux-hardware.org/?probe=e38723516e) | Feb 17, 2020 |
| Acer          | Veriton L4610G              | Desktop     | [aef314a65c](https://linux-hardware.org/?probe=aef314a65c) | Feb 17, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [31a6b6bac8](https://linux-hardware.org/?probe=31a6b6bac8) | Feb 15, 2020 |
| Gigabyte      | Z68M-D2H                    | Desktop     | [6cfda70306](https://linux-hardware.org/?probe=6cfda70306) | Feb 15, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [ac2755b222](https://linux-hardware.org/?probe=ac2755b222) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [7f2259cf54](https://linux-hardware.org/?probe=7f2259cf54) | Feb 12, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [317f9ded14](https://linux-hardware.org/?probe=317f9ded14) | Feb 12, 2020 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [e5b58a2f40](https://linux-hardware.org/?probe=e5b58a2f40) | Feb 08, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [81d2b1c515](https://linux-hardware.org/?probe=81d2b1c515) | Jan 25, 2020 |
| Intel         | ChiefRiver                  | Desktop     | [1ca590a614](https://linux-hardware.org/?probe=1ca590a614) | Jan 22, 2020 |
| Unknown       | Unknown                     | Notebook    | [5603e706a3](https://linux-hardware.org/?probe=5603e706a3) | Jan 19, 2020 |
| Dell          | 0C27VV A01                  | Desktop     | [b896b0fef0](https://linux-hardware.org/?probe=b896b0fef0) | Jan 18, 2020 |
| Gigabyte      | MSH87TN-00                  | Desktop     | [624e731bcd](https://linux-hardware.org/?probe=624e731bcd) | Jan 16, 2020 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [912a2fc0df](https://linux-hardware.org/?probe=912a2fc0df) | Jan 16, 2020 |
| Gigabyte      | P55A-UD4P                   | Desktop     | [df0bc17152](https://linux-hardware.org/?probe=df0bc17152) | Jan 13, 2020 |
| HP            | 2000                        | Notebook    | [adde2680e0](https://linux-hardware.org/?probe=adde2680e0) | Jan 08, 2020 |
| Lenovo        | ThinkPad T530 23943V0       | Notebook    | [fdb43e275c](https://linux-hardware.org/?probe=fdb43e275c) | Jan 05, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [ae8aac83f4](https://linux-hardware.org/?probe=ae8aac83f4) | Jan 05, 2020 |
| TUXEDO        | Unknown                     | Notebook    | [282e4941e2](https://linux-hardware.org/?probe=282e4941e2) | Dec 27, 2019 |
| HP            | Compaq 8460p USAO           | Notebook    | [3eab448396](https://linux-hardware.org/?probe=3eab448396) | Dec 21, 2019 |
| ASUSTek       | N751JK                      | Notebook    | [a6b5f083ca](https://linux-hardware.org/?probe=a6b5f083ca) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | Notebook    | [f35ce62181](https://linux-hardware.org/?probe=f35ce62181) | Nov 21, 2019 |
| ASUSTek       | N751JK                      | Notebook    | [2c44aa3122](https://linux-hardware.org/?probe=2c44aa3122) | Nov 21, 2019 |
| Supermicro    | X9DRT                       | Server      | [f5f0a90676](https://linux-hardware.org/?probe=f5f0a90676) | Nov 19, 2019 |
| Dell          | Inspiron 5559               | Notebook    | [6571c933d2](https://linux-hardware.org/?probe=6571c933d2) | Mar 08, 2019 |
| ASUSTek       | T102HA                      | Tablet      | [7c47ab2fd4](https://linux-hardware.org/?probe=7c47ab2fd4) | Jun 14, 2018 |
| Dell          | 0G9322                      | Desktop     | [62b841a44f](https://linux-hardware.org/?probe=62b841a44f) | Jun 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu Budgie 20.04 | 239       | 51.73%  |
| Ubuntu Budgie 20.10 | 61        | 13.2%   |
| Ubuntu Budgie 21.10 | 50        | 10.82%  |
| Ubuntu Budgie 18.04 | 37        | 8.01%   |
| Ubuntu Budgie 21.04 | 35        | 7.58%   |
| Ubuntu Budgie 19.10 | 29        | 6.28%   |
| Ubuntu Budgie 22.04 | 6         | 1.3%    |
| Ubuntu Budgie       | 3         | 0.65%   |
| Ubuntu Budgie 16.04 | 2         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu Budgie | 449       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 26        | 5.13%   |
| 5.3.0-40-generic  | 15        | 2.96%   |
| 5.13.0-22-generic | 14        | 2.76%   |
| 5.4.0-40-generic  | 13        | 2.56%   |
| 5.4.0-52-generic  | 10        | 1.97%   |
| 5.4.0-37-generic  | 10        | 1.97%   |
| 5.4.0-29-generic  | 10        | 1.97%   |
| 5.4.0-58-generic  | 9         | 1.78%   |
| 5.4.0-48-generic  | 9         | 1.78%   |
| 5.13.0-39-generic | 9         | 1.78%   |
| 5.13.0-28-generic | 9         | 1.78%   |
| 5.13.0-19-generic | 9         | 1.78%   |
| 5.8.0-48-generic  | 8         | 1.58%   |
| 5.8.0-44-generic  | 8         | 1.58%   |
| 5.8.0-41-generic  | 8         | 1.58%   |
| 5.8.0-43-generic  | 7         | 1.38%   |
| 5.4.0-47-generic  | 7         | 1.38%   |
| 5.4.0-33-generic  | 7         | 1.38%   |
| 5.13.0-30-generic | 7         | 1.38%   |
| 5.8.0-53-generic  | 6         | 1.18%   |
| 5.8.0-45-generic  | 6         | 1.18%   |
| 5.8.0-29-generic  | 6         | 1.18%   |
| 5.4.0-31-generic  | 6         | 1.18%   |
| 5.13.0-35-generic | 6         | 1.18%   |
| 5.11.0-41-generic | 6         | 1.18%   |
| 5.8.0-33-generic  | 5         | 0.99%   |
| 5.8.0-25-generic  | 5         | 0.99%   |
| 5.4.0-91-generic  | 5         | 0.99%   |
| 5.4.0-66-generic  | 5         | 0.99%   |
| 5.4.0-65-generic  | 5         | 0.99%   |
| 5.4.0-45-generic  | 5         | 0.99%   |
| 5.3.0-42-generic  | 5         | 0.99%   |
| 5.3.0-26-generic  | 5         | 0.99%   |
| 5.11.0-22-generic | 5         | 0.99%   |
| 5.11.0-16-generic | 5         | 0.99%   |
| 5.8.0-59-generic  | 4         | 0.79%   |
| 5.8.0-26-generic  | 4         | 0.79%   |
| 5.4.0-72-generic  | 4         | 0.79%   |
| 5.4.0-59-generic  | 4         | 0.79%   |
| 5.4.0-28-generic  | 4         | 0.79%   |
| 5.13.0-40-generic | 4         | 0.79%   |
| 5.13.0-27-generic | 4         | 0.79%   |
| 5.11.0-34-generic | 4         | 0.79%   |
| 5.11.0-25-generic | 4         | 0.79%   |
| 5.11.0-18-generic | 4         | 0.79%   |
| 5.8.0-50-generic  | 3         | 0.59%   |
| 5.8.0-31-generic  | 3         | 0.59%   |
| 5.4.0-80-generic  | 3         | 0.59%   |
| 5.4.0-73-generic  | 3         | 0.59%   |
| 5.4.0-62-generic  | 3         | 0.59%   |
| 5.4.0-54-generic  | 3         | 0.59%   |
| 5.4.0-26-generic  | 3         | 0.59%   |
| 5.3.0-24-generic  | 3         | 0.59%   |
| 5.13.0-25-generic | 3         | 0.59%   |
| 5.13.0-21-generic | 3         | 0.59%   |
| 5.13.0-20-generic | 3         | 0.59%   |
| 5.11.0-38-generic | 3         | 0.59%   |
| 5.11.0-31-generic | 3         | 0.59%   |
| 5.11.0-27-generic | 3         | 0.59%   |
| 5.11.0-17-generic | 3         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 167       | 35.76%  |
| 5.8.0   | 89        | 19.06%  |
| 5.13.0  | 71        | 15.2%   |
| 5.11.0  | 51        | 10.92%  |
| 5.3.0   | 42        | 8.99%   |
| 4.15.0  | 12        | 2.57%   |
| 5.15.0  | 5         | 1.07%   |
| 5.6.0   | 3         | 0.64%   |
| 5.0.0   | 3         | 0.64%   |
| 5.6.7   | 2         | 0.43%   |
| 5.12.0  | 2         | 0.43%   |
| 5.10.0  | 2         | 0.43%   |
| 4.18.0  | 2         | 0.43%   |
| 5.9.1   | 1         | 0.21%   |
| 5.9.0   | 1         | 0.21%   |
| 5.8.6   | 1         | 0.21%   |
| 5.8.11  | 1         | 0.21%   |
| 5.7.7   | 1         | 0.21%   |
| 5.5.8   | 1         | 0.21%   |
| 5.5.0   | 1         | 0.21%   |
| 5.17.2  | 1         | 0.21%   |
| 5.17.1  | 1         | 0.21%   |
| 5.16.2  | 1         | 0.21%   |
| 5.16.14 | 1         | 0.21%   |
| 5.15.11 | 1         | 0.21%   |
| 5.14.2  | 1         | 0.21%   |
| 5.14.1  | 1         | 0.21%   |
| 5.10.11 | 1         | 0.21%   |
| 4.4.0   | 1         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 167       | 35.84%  |
| 5.8     | 91        | 19.53%  |
| 5.13    | 71        | 15.24%  |
| 5.11    | 51        | 10.94%  |
| 5.3     | 42        | 9.01%   |
| 4.15    | 12        | 2.58%   |
| 5.15    | 6         | 1.29%   |
| 5.6     | 5         | 1.07%   |
| 5.10    | 3         | 0.64%   |
| 5.0     | 3         | 0.64%   |
| 5.9     | 2         | 0.43%   |
| 5.5     | 2         | 0.43%   |
| 5.17    | 2         | 0.43%   |
| 5.16    | 2         | 0.43%   |
| 5.12    | 2         | 0.43%   |
| 4.18    | 2         | 0.43%   |
| 5.7     | 1         | 0.21%   |
| 5.14    | 1         | 0.21%   |
| 4.4     | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 436       | 97.1%   |
| i686    | 9         | 2%      |
| aarch64 | 3         | 0.67%   |
| armv7l  | 1         | 0.22%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Budgie | 440       | 98%     |
| GNOME  | 7         | 1.56%   |
| XFCE   | 1         | 0.22%   |
| KDE    | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 438       | 97.55%  |
| Wayland | 9         | 2%      |
| Tty     | 2         | 0.45%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 221       | 48.57%  |
| LightDM | 103       | 22.64%  |
| TDM     | 91        | 20%     |
| GDM     | 31        | 6.81%   |
| GDM3    | 7         | 1.54%   |
| SDDM    | 2         | 0.44%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 166       | 36.89%  |
| de_DE   | 59        | 13.11%  |
| pt_BR   | 31        | 6.89%   |
| fr_FR   | 28        | 6.22%   |
| en_GB   | 23        | 5.11%   |
| en_CA   | 18        | 4%      |
| it_IT   | 12        | 2.67%   |
| ru_RU   | 11        | 2.44%   |
| es_AR   | 9         | 2%      |
| en_IN   | 9         | 2%      |
| es_MX   | 8         | 1.78%   |
| en_AU   | 8         | 1.78%   |
| es_ES   | 7         | 1.56%   |
| Unknown | 6         | 1.33%   |
| pl_PL   | 4         | 0.89%   |
| es_CL   | 4         | 0.89%   |
| C       | 4         | 0.89%   |
| uk_UA   | 3         | 0.67%   |
| pt_PT   | 3         | 0.67%   |
| nl_NL   | 3         | 0.67%   |
| de_AT   | 3         | 0.67%   |
| zh_TW   | 2         | 0.44%   |
| hu_HU   | 2         | 0.44%   |
| fi_FI   | 2         | 0.44%   |
| es_CO   | 2         | 0.44%   |
| en_IE   | 2         | 0.44%   |
| de_CH   | 2         | 0.44%   |
| zh_CN   | 1         | 0.22%   |
| tr_TR   | 1         | 0.22%   |
| sv_SE   | 1         | 0.22%   |
| ru_UA   | 1         | 0.22%   |
| ro_RO   | 1         | 0.22%   |
| nl_BE   | 1         | 0.22%   |
| nb_NO   | 1         | 0.22%   |
| lv_LV   | 1         | 0.22%   |
| ja_JP   | 1         | 0.22%   |
| id_ID   | 1         | 0.22%   |
| fr_CH   | 1         | 0.22%   |
| fr_CA   | 1         | 0.22%   |
| es_US   | 1         | 0.22%   |
| es_SV   | 1         | 0.22%   |
| es_GT   | 1         | 0.22%   |
| en_ZA   | 1         | 0.22%   |
| en_SG   | 1         | 0.22%   |
| en_IL   | 1         | 0.22%   |
| bg_BG   | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 260       | 56.52%  |
| BIOS | 200       | 43.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 422       | 93.78%  |
| Zfs     | 13        | 2.89%   |
| Overlay | 7         | 1.56%   |
| Btrfs   | 5         | 1.11%   |
| Xfs     | 2         | 0.44%   |
| Jfs     | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 265       | 58.5%   |
| GPT     | 153       | 33.77%  |
| MBR     | 35        | 7.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 397       | 87.06%  |
| Yes       | 59        | 12.94%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 313       | 68.79%  |
| Yes       | 142       | 31.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUSTek Computer                 | 69        | 15.37%  |
| Hewlett-Packard                  | 65        | 14.48%  |
| Lenovo                           | 60        | 13.36%  |
| Dell                             | 55        | 12.25%  |
| TUXEDO                           | 33        | 7.35%   |
| Gigabyte Technology              | 26        | 5.79%   |
| Apple                            | 22        | 4.9%    |
| MSI                              | 21        | 4.68%   |
| Acer                             | 21        | 4.68%   |
| ASRock                           | 11        | 2.45%   |
| Intel                            | 6         | 1.34%   |
| Sony                             | 5         | 1.11%   |
| Samsung Electronics              | 5         | 1.11%   |
| HUAWEI                           | 5         | 1.11%   |
| Unknown                          | 5         | 1.11%   |
| Toshiba                          | 3         | 0.67%   |
| Raspberry Pi Foundation          | 3         | 0.67%   |
| Packard Bell                     | 3         | 0.67%   |
| Fujitsu                          | 3         | 0.67%   |
| Standard                         | 2         | 0.45%   |
| Google                           | 2         | 0.45%   |
| eMachines                        | 2         | 0.45%   |
| Viglen                           | 1         | 0.22%   |
| Timi                             | 1         | 0.22%   |
| Teclast                          | 1         | 0.22%   |
| Supermicro                       | 1         | 0.22%   |
| Razer                            | 1         | 0.22%   |
| Radxa                            | 1         | 0.22%   |
| Quanta                           | 1         | 0.22%   |
| Positivo                         | 1         | 0.22%   |
| Pegatron                         | 1         | 0.22%   |
| PCSMART                          | 1         | 0.22%   |
| PC Specialist                    | 1         | 0.22%   |
| Microsoft                        | 1         | 0.22%   |
| LattePanda                       | 1         | 0.22%   |
| Huanan                           | 1         | 0.22%   |
| GPU Company                      | 1         | 0.22%   |
| FUJITSU CLIENT COMPUTING LIMITED | 1         | 0.22%   |
| EVOO                             | 1         | 0.22%   |
| Biostar                          | 1         | 0.22%   |
| BCM                              | 1         | 0.22%   |
| BANGHO                           | 1         | 0.22%   |
| AWOW                             | 1         | 0.22%   |
| Alienware                        | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 15        | 3.34%   |
| ASUS All Series                        | 5         | 1.11%   |
| TUXEDO Polaris 15 AMD Gen1             | 2         | 0.45%   |
| TUXEDO InfinityBook S 15 Gen6          | 2         | 0.45%   |
| TUXEDO InfinityBook S 14 Gen6          | 2         | 0.45%   |
| TUXEDO InfinityBook Pro 14 Gen6        | 2         | 0.45%   |
| TUXEDO Aura 15 Gen1                    | 2         | 0.45%   |
| Standard MT40II                        | 2         | 0.45%   |
| MSI MS-7C84                            | 2         | 0.45%   |
| Lenovo IdeaPad 330S-15ARR 81FB         | 2         | 0.45%   |
| Lenovo IdeaPad 320-15IKB 80XL          | 2         | 0.45%   |
| HP ZBook Studio G3                     | 2         | 0.45%   |
| HP Pavilion g6                         | 2         | 0.45%   |
| HP Notebook                            | 2         | 0.45%   |
| HP ENVY 15                             | 2         | 0.45%   |
| HP EliteDesk 800 G1 SFF                | 2         | 0.45%   |
| HP 2000                                | 2         | 0.45%   |
| Gigabyte Z68M-D2H                      | 2         | 0.45%   |
| Gigabyte AB350-Gaming 3                | 2         | 0.45%   |
| Dell XPS 13 9380                       | 2         | 0.45%   |
| Dell Precision WorkStation T3500       | 2         | 0.45%   |
| Dell OptiPlex 9010                     | 2         | 0.45%   |
| Dell OptiPlex 780                      | 2         | 0.45%   |
| Dell Latitude E6540                    | 2         | 0.45%   |
| Dell Latitude 5400                     | 2         | 0.45%   |
| Dell Inspiron 5570                     | 2         | 0.45%   |
| ASUS VivoBook_ASUSLaptop X571GT_F571GT | 2         | 0.45%   |
| ASUS P8H77-M PRO                       | 2         | 0.45%   |
| Apple MacPro1,1                        | 2         | 0.45%   |
| Apple MacBookPro8,1                    | 2         | 0.45%   |
| Acer TravelMate P446-M                 | 2         | 0.45%   |
| Viglen VUB1                            | 1         | 0.22%   |
| TUXEDO TUXEDO_Book_XA1510              | 1         | 0.22%   |
| TUXEDO Stellaris Intel Gen3 (TGL)      | 1         | 0.22%   |
| TUXEDO Stellaris AMD Gen3 (CZN)        | 1         | 0.22%   |
| TUXEDO Pulse 15 Gen1                   | 1         | 0.22%   |
| TUXEDO Polaris AMD Gen3 (CZN)          | 1         | 0.22%   |
| TUXEDO Polaris 17 AMD Gen1             | 1         | 0.22%   |
| TUXEDO P95_HR                          | 1         | 0.22%   |
| TUXEDO P95_HP                          | 1         | 0.22%   |
| TUXEDO P7xxTM1                         | 1         | 0.22%   |
| TUXEDO InfinityBook S 14 v5            | 1         | 0.22%   |
| TUXEDO InfinityBook Pro 15 v4          | 1         | 0.22%   |
| TUXEDO Book XP1511                     | 1         | 0.22%   |
| TUXEDO Book XP15 / XP17 Gen12          | 1         | 0.22%   |
| Toshiba Satellite S55-C                | 1         | 0.22%   |
| Toshiba Satellite P750                 | 1         | 0.22%   |
| Toshiba Satellite P300                 | 1         | 0.22%   |
| Timi TM1701                            | 1         | 0.22%   |
| Teclast X6 plus                        | 1         | 0.22%   |
| Supermicro X9DRT                       | 1         | 0.22%   |
| Sony VPCEK20AL                         | 1         | 0.22%   |
| Sony VPCEJ1L1E                         | 1         | 0.22%   |
| Sony VPCEA47FX                         | 1         | 0.22%   |
| Sony VPCCW25FL                         | 1         | 0.22%   |
| Sony SVS13A25PBS                       | 1         | 0.22%   |
| Samsung 905S3G/906S3G/915S3G/9305SG    | 1         | 0.22%   |
| Samsung 530U3C/530U4C/532U3C           | 1         | 0.22%   |
| Samsung 340XAA/350XAA/550XAA           | 1         | 0.22%   |
| Samsung 305V4A/305V5A                  | 1         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 27        | 6.01%   |
| Dell Latitude         | 15        | 3.34%   |
| Dell Inspiron         | 15        | 3.34%   |
| Unknown               | 15        | 3.34%   |
| HP Pavilion           | 13        | 2.9%    |
| Acer Aspire           | 13        | 2.9%    |
| Lenovo IdeaPad        | 12        | 2.67%   |
| Dell XPS              | 9         | 2%      |
| TUXEDO InfinityBook   | 8         | 1.78%   |
| HP EliteBook          | 8         | 1.78%   |
| HP ENVY               | 7         | 1.56%   |
| Dell OptiPlex         | 7         | 1.56%   |
| ASUS ROG              | 7         | 1.56%   |
| HP Compaq             | 6         | 1.34%   |
| HP Spectre            | 5         | 1.11%   |
| Dell Precision        | 5         | 1.11%   |
| ASUS VivoBook         | 5         | 1.11%   |
| ASUS PRIME            | 5         | 1.11%   |
| ASUS All              | 5         | 1.11%   |
| TUXEDO Polaris        | 4         | 0.89%   |
| HP ZBook              | 4         | 0.89%   |
| HP Laptop             | 4         | 0.89%   |
| Acer Swift            | 4         | 0.89%   |
| Toshiba Satellite     | 3         | 0.67%   |
| RPi Raspberry         | 3         | 0.67%   |
| Lenovo Yoga           | 3         | 0.67%   |
| Lenovo ThinkBook      | 3         | 0.67%   |
| HP ProBook            | 3         | 0.67%   |
| HP EliteDesk          | 3         | 0.67%   |
| ASUS TUF              | 3         | 0.67%   |
| ASUS P8H77-M          | 3         | 0.67%   |
| Apple MacBookPro8     | 3         | 0.67%   |
| TUXEDO Stellaris      | 2         | 0.45%   |
| TUXEDO P95            | 2         | 0.45%   |
| TUXEDO Book           | 2         | 0.45%   |
| TUXEDO Aura           | 2         | 0.45%   |
| Standard MT40II       | 2         | 0.45%   |
| Packard Bell EasyNote | 2         | 0.45%   |
| MSI Prestige          | 2         | 0.45%   |
| MSI MS-7C84           | 2         | 0.45%   |
| Lenovo IdeaCentre     | 2         | 0.45%   |
| HP Stream             | 2         | 0.45%   |
| HP Notebook           | 2         | 0.45%   |
| HP 2000               | 2         | 0.45%   |
| Gigabyte Z68M-D2H     | 2         | 0.45%   |
| Gigabyte B360         | 2         | 0.45%   |
| Gigabyte AB350-Gaming | 2         | 0.45%   |
| Fujitsu LIFEBOOK      | 2         | 0.45%   |
| Dell Vostro           | 2         | 0.45%   |
| ASUS P8Z68-V          | 2         | 0.45%   |
| ASRock B550           | 2         | 0.45%   |
| Apple MacPro1         | 2         | 0.45%   |
| Apple MacBookPro11    | 2         | 0.45%   |
| Apple iMac18          | 2         | 0.45%   |
| Acer TravelMate       | 2         | 0.45%   |
| Viglen VUB1           | 1         | 0.22%   |
| TUXEDO TUXEDO         | 1         | 0.22%   |
| TUXEDO Pulse          | 1         | 0.22%   |
| TUXEDO P7xxTM1        | 1         | 0.22%   |
| Timi TM1701           | 1         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 60        | 13.36%  |
| 2018    | 55        | 12.25%  |
| 2020    | 48        | 10.69%  |
| 2017    | 37        | 8.24%   |
| 2011    | 35        | 7.8%    |
| 2013    | 33        | 7.35%   |
| 2012    | 33        | 7.35%   |
| 2015    | 23        | 5.12%   |
| 2014    | 23        | 5.12%   |
| 2016    | 21        | 4.68%   |
| 2021    | 19        | 4.23%   |
| 2010    | 18        | 4.01%   |
| 2009    | 15        | 3.34%   |
| 2007    | 13        | 2.9%    |
| 2008    | 12        | 2.67%   |
| Unknown | 3         | 0.67%   |
| 2022    | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 277       | 61.69%  |
| Desktop        | 134       | 29.84%  |
| All in one     | 12        | 2.67%   |
| Convertible    | 11        | 2.45%   |
| Tablet         | 5         | 1.11%   |
| Mini pc        | 5         | 1.11%   |
| System on chip | 4         | 0.89%   |
| Server         | 1         | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 412       | 91.76%  |
| Enabled  | 37        | 8.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 447       | 99.55%  |
| Yes  | 2         | 0.45%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 115       | 25.33%  |
| 4.01-8.0    | 103       | 22.69%  |
| 3.01-4.0    | 75        | 16.52%  |
| 8.01-16.0   | 74        | 16.3%   |
| 32.01-64.0  | 50        | 11.01%  |
| 64.01-256.0 | 19        | 4.19%   |
| 1.01-2.0    | 8         | 1.76%   |
| 24.01-32.0  | 5         | 1.1%    |
| 2.01-3.0    | 3         | 0.66%   |
| 0.51-1.0    | 2         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 150       | 30.99%  |
| 1.01-2.0   | 130       | 26.86%  |
| 4.01-8.0   | 88        | 18.18%  |
| 3.01-4.0   | 81        | 16.74%  |
| 8.01-16.0  | 23        | 4.75%   |
| 0.51-1.0   | 9         | 1.86%   |
| 32.01-64.0 | 1         | 0.21%   |
| 16.01-24.0 | 1         | 0.21%   |
| 0.01-0.5   | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 270       | 58.82%  |
| 2      | 119       | 25.93%  |
| 3      | 33        | 7.19%   |
| 4      | 16        | 3.49%   |
| 5      | 12        | 2.61%   |
| 8      | 4         | 0.87%   |
| 6      | 3         | 0.65%   |
| 11     | 1         | 0.22%   |
| 9      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 284       | 62.97%  |
| Yes       | 167       | 37.03%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 381       | 84.67%  |
| No        | 69        | 15.33%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 372       | 82.48%  |
| No        | 79        | 17.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 316       | 69.76%  |
| No        | 137       | 30.24%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| USA                | 84        | 18.67%  |
| Germany            | 67        | 14.89%  |
| Brazil             | 32        | 7.11%   |
| France             | 30        | 6.67%   |
| Canada             | 17        | 3.78%   |
| UK                 | 15        | 3.33%   |
| Italy              | 15        | 3.33%   |
| Russia             | 13        | 2.89%   |
| India              | 11        | 2.44%   |
| Argentina          | 11        | 2.44%   |
| Poland             | 10        | 2.22%   |
| Netherlands        | 10        | 2.22%   |
| Mexico             | 10        | 2.22%   |
| Spain              | 8         | 1.78%   |
| Australia          | 8         | 1.78%   |
| Ukraine            | 7         | 1.56%   |
| Switzerland        | 7         | 1.56%   |
| Norway             | 6         | 1.33%   |
| Austria            | 6         | 1.33%   |
| Portugal           | 5         | 1.11%   |
| Japan              | 5         | 1.11%   |
| Sweden             | 4         | 0.89%   |
| Hungary            | 4         | 0.89%   |
| Finland            | 4         | 0.89%   |
| Chile              | 4         | 0.89%   |
| Turkey             | 3         | 0.67%   |
| South Africa       | 3         | 0.67%   |
| Ireland            | 3         | 0.67%   |
| Iran               | 3         | 0.67%   |
| Greece             | 3         | 0.67%   |
| Dominican Republic | 3         | 0.67%   |
| Croatia            | 3         | 0.67%   |
| Colombia           | 3         | 0.67%   |
| Belgium            | 3         | 0.67%   |
| Romania            | 2         | 0.44%   |
| Malaysia           | 2         | 0.44%   |
| Indonesia          | 2         | 0.44%   |
| Thailand           | 1         | 0.22%   |
| Taiwan             | 1         | 0.22%   |
| Slovenia           | 1         | 0.22%   |
| Slovakia           | 1         | 0.22%   |
| Singapore          | 1         | 0.22%   |
| Serbia             | 1         | 0.22%   |
| Saudi Arabia       | 1         | 0.22%   |
| Puerto Rico        | 1         | 0.22%   |
| Philippines        | 1         | 0.22%   |
| Myanmar            | 1         | 0.22%   |
| Libya              | 1         | 0.22%   |
| Latvia             | 1         | 0.22%   |
| Kenya              | 1         | 0.22%   |
| Jordan             | 1         | 0.22%   |
| Israel             | 1         | 0.22%   |
| Hong Kong          | 1         | 0.22%   |
| Honduras           | 1         | 0.22%   |
| Guatemala          | 1         | 0.22%   |
| Ghana              | 1         | 0.22%   |
| El Salvador        | 1         | 0.22%   |
| Egypt              | 1         | 0.22%   |
| Ecuador            | 1         | 0.22%   |
| Bulgaria           | 1         | 0.22%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Sao Paulo               | 6         | 1.3%    |
| Ravensburg              | 4         | 0.86%   |
| Paris                   | 4         | 0.86%   |
| Munich                  | 4         | 0.86%   |
| Moscow                  | 4         | 0.86%   |
| Hamburg                 | 4         | 0.86%   |
| Berlin                  | 4         | 0.86%   |
| Zagreb                  | 3         | 0.65%   |
| Tehran                  | 3         | 0.65%   |
| Sydney                  | 3         | 0.65%   |
| Stuttgart               | 3         | 0.65%   |
| Santo Domingo Este      | 3         | 0.65%   |
| Montreal                | 3         | 0.65%   |
| Miami                   | 3         | 0.65%   |
| Los Angeles             | 3         | 0.65%   |
| Lisbon                  | 3         | 0.65%   |
| Dublin                  | 3         | 0.65%   |
| Budapest                | 3         | 0.65%   |
| Athens                  | 3         | 0.65%   |
| Zabrze                  | 2         | 0.43%   |
| Wilchingen, Osterfingen | 2         | 0.43%   |
| Vienna                  | 2         | 0.43%   |
| Uman                    | 2         | 0.43%   |
| Trondheim               | 2         | 0.43%   |
| TimiИ™oara           | 2         | 0.43%   |
| St Petersburg           | 2         | 0.43%   |
| San Jose                | 2         | 0.43%   |
| San Francisco           | 2         | 0.43%   |
| San Antonio             | 2         | 0.43%   |
| Salt Lake City          | 2         | 0.43%   |
| Pune                    | 2         | 0.43%   |
| Oslo                    | 2         | 0.43%   |
| NiterГіi              | 2         | 0.43%   |
| MaringГЎ              | 2         | 0.43%   |
| Llavallol               | 2         | 0.43%   |
| Laupen                  | 2         | 0.43%   |
| Kyiv                    | 2         | 0.43%   |
| Frankfurt am Main       | 2         | 0.43%   |
| Dresden                 | 2         | 0.43%   |
| Dallas                  | 2         | 0.43%   |
| Cologne                 | 2         | 0.43%   |
| BrasГ­lia             | 2         | 0.43%   |
| BogotÃ¡               | 2         | 0.43%   |
| Belo Horizonte          | 2         | 0.43%   |
| Barcelona               | 2         | 0.43%   |
| Bamberg                 | 2         | 0.43%   |
| Austin                  | 2         | 0.43%   |
| ЕљwinoujЕ›cie      | 1         | 0.22%   |
| Zheleznodorozhnyy       | 1         | 0.22%   |
| Zapopan                 | 1         | 0.22%   |
| Yuma                    | 1         | 0.22%   |
| Yangon                  | 1         | 0.22%   |
| WГјrzburg             | 1         | 0.22%   |
| Wolfsburg               | 1         | 0.22%   |
| Woking                  | 1         | 0.22%   |
| Wilderness Rim          | 1         | 0.22%   |
| Westland                | 1         | 0.22%   |
| West Lafayette          | 1         | 0.22%   |
| West End                | 1         | 0.22%   |
| West Des Moines         | 1         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives  | Percent |
|---------------------------|-----------|---------|---------|
| Samsung Electronics       | 129       | 181     | 19.4%   |
| WDC                       | 96        | 139     | 14.44%  |
| Seagate                   | 93        | 136     | 13.98%  |
| Toshiba                   | 45        | 48      | 6.77%   |
| Sandisk                   | 40        | 50      | 6.02%   |
| Unknown                   | 30        | 36      | 4.51%   |
| Kingston                  | 28        | 37      | 4.21%   |
| Intel                     | 21        | 34      | 3.16%   |
| Hitachi                   | 19        | 26      | 2.86%   |
| Crucial                   | 18        | 20      | 2.71%   |
| SK Hynix                  | 13        | 15      | 1.95%   |
| HGST                      | 11        | 15      | 1.65%   |
| Phison                    | 10        | 15      | 1.5%    |
| A-DATA Technology         | 10        | 13      | 1.5%    |
| China                     | 9         | 10      | 1.35%   |
| Apple                     | 9         | 11      | 1.35%   |
| PNY                       | 7         | 10      | 1.05%   |
| Micron Technology         | 7         | 10      | 1.05%   |
| SPCC                      | 6         | 8       | 0.9%    |
| Patriot                   | 3         | 4       | 0.45%   |
| Micron/Crucial Technology | 3         | 3       | 0.45%   |
| KIOXIA                    | 3         | 3       | 0.45%   |
| OCZ                       | 2         | 4       | 0.3%    |
| MAXTOR                    | 2         | 5       | 0.3%    |
| LITEON                    | 2         | 2       | 0.3%    |
| Lenovo                    | 2         | 2       | 0.3%    |
| LaCie                     | 2         | 2       | 0.3%    |
| JMicron                   | 2         | 3       | 0.3%    |
| Intenso                   | 2         | 3       | 0.3%    |
| HS-SSD-C100               | 2         | 2       | 0.3%    |
| Gigabyte Technology       | 2         | 2       | 0.3%    |
| Apacer                    | 2         | 2       | 0.3%    |
| AMD                       | 2         | 17      | 0.3%    |
| Zheino                    | 1         | 1       | 0.15%   |
| XrayDisk                  | 1         | 1       | 0.15%   |
| Vaseky                    | 1         | 1       | 0.15%   |
| USB30                     | 1         | 1       | 0.15%   |
| USB3.0                    | 1         | 1       | 0.15%   |
| Union Memory              | 1         | 1       | 0.15%   |
| Transcend                 | 1         | 1       | 0.15%   |
| Teclast                   | 1         | 1       | 0.15%   |
| TDAS                      | 1         | 3       | 0.15%   |
| Silicon Motion            | 1         | 1       | 0.15%   |
| SABRENT                   | 1         | 1       | 0.15%   |
| Realtek Semiconductor     | 1         | 1       | 0.15%   |
| PLEXTOR                   | 1         | 1       | 0.15%   |
| Phison Electronics        | 1         | 1       | 0.15%   |
| OWC                       | 1         | 1       | 0.15%   |
| Netac                     | 1         | 1       | 0.15%   |
| MDT                       | 1         | 1       | 0.15%   |
| LITEONIT                  | 1         | 1       | 0.15%   |
| LDLC                      | 1         | 1       | 0.15%   |
| KingSpec                  | 1         | 1       | 0.15%   |
| KingDian                  | 1         | 1       | 0.15%   |
| KimMiDi                   | 1         | 1       | 0.15%   |
| HP Phison                 | 1         | 1       | 0.15%   |
| Hewlett-Packard           | 1         | Unknown | 0.15%   |
| GOODRAM                   | 1         | 1       | 0.15%   |
| GALAX TA                  | 1         | 1       | 0.15%   |
| Fujitsu                   | 1         | 1       | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 9         | 1.2%    |
| Samsung NVMe SSD Drive 512GB       | 9         | 1.2%    |
| Unknown MMC Card  64GB             | 8         | 1.07%   |
| Samsung NVMe SSD Drive 500GB       | 8         | 1.07%   |
| Samsung NVMe SSD Drive 1TB         | 7         | 0.94%   |
| Seagate ST9500325AS 500GB          | 6         | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.8%    |
| Samsung SSD 860 QVO 1TB            | 6         | 0.8%    |
| Kingston SA400S37240G 240GB SSD    | 6         | 0.8%    |
| Unknown MMC Card  32GB             | 5         | 0.67%   |
| Toshiba MQ04ABF100 1TB             | 5         | 0.67%   |
| SK Hynix NVMe SSD Drive 256GB      | 5         | 0.67%   |
| Seagate ST500DM002-1BD142 500GB    | 5         | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB     | 5         | 0.67%   |
| SanDisk SDSSDA240G 240GB           | 5         | 0.67%   |
| Samsung SSD 850 EVO 500GB          | 5         | 0.67%   |
| Samsung NVMe SSD Drive 256GB       | 5         | 0.67%   |
| Kingston SA400S37480G 480GB SSD    | 5         | 0.67%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 4         | 0.54%   |
| Toshiba MQ01ABD100 1TB             | 4         | 0.54%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 0.54%   |
| Sandisk NVMe SSD Drive 512GB       | 4         | 0.54%   |
| Samsung SSD 970 EVO Plus 500GB     | 4         | 0.54%   |
| Samsung SSD 970 EVO Plus 1TB       | 4         | 0.54%   |
| Samsung SSD 860 EVO M.2 250GB      | 4         | 0.54%   |
| Samsung SSD 860 EVO 250GB          | 4         | 0.54%   |
| Samsung SSD 750 EVO 250GB          | 4         | 0.54%   |
| Samsung NVMe SSD Drive 2TB         | 4         | 0.54%   |
| Samsung NVMe SSD Drive 250GB       | 4         | 0.54%   |
| Intel NVMe SSD Drive 512GB         | 4         | 0.54%   |
| China SATA SSD 240GB               | 4         | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 3         | 0.4%    |
| WDC WD5000AAKX-001CA0 500GB        | 3         | 0.4%    |
| WDC WD10JPVX-22JC3T0 1TB           | 3         | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.4%    |
| Unknown SD/MMC/MS PRO 16GB         | 3         | 0.4%    |
| Unknown MMC Card  16GB             | 3         | 0.4%    |
| Seagate ST4000DM000-1F2168 4TB     | 3         | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB     | 3         | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB     | 3         | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB     | 3         | 0.4%    |
| Seagate ST1000LX015-1U7172 1TB     | 3         | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB     | 3         | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB     | 3         | 0.4%    |
| SanDisk SDSSDA120G 120GB           | 3         | 0.4%    |
| Samsung SSD 970 EVO 500GB          | 3         | 0.4%    |
| Samsung SSD 860 EVO M.2 500GB      | 3         | 0.4%    |
| Samsung SSD 850 EVO 250GB          | 3         | 0.4%    |
| Phison NVMe SSD Drive 1TB          | 3         | 0.4%    |
| Micron/Crucial NVMe SSD Drive 1TB  | 3         | 0.4%    |
| Intel NVMe SSD Drive 32GB          | 3         | 0.4%    |
| Hitachi HTS545050A7E380 500GB      | 3         | 0.4%    |
| WDC WDS500G2B0B-00YS70 500GB SSD   | 2         | 0.27%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 2         | 0.27%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 2         | 0.27%   |
| WDC WD7501AALS-00J7B1 752GB        | 2         | 0.27%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 2         | 0.27%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 0.27%   |
| WDC WD10SPZX-60Z10T0 1TB           | 2         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 90        | 133    | 37.04%  |
| WDC                 | 72        | 111    | 29.63%  |
| Toshiba             | 36        | 39     | 14.81%  |
| Hitachi             | 19        | 26     | 7.82%   |
| HGST                | 11        | 15     | 4.53%   |
| Samsung Electronics | 4         | 4      | 1.65%   |
| Unknown             | 3         | 3      | 1.23%   |
| Apple               | 3         | 3      | 1.23%   |
| MAXTOR              | 2         | 5      | 0.82%   |
| USB3.0              | 1         | 1      | 0.41%   |
| SABRENT             | 1         | 1      | 0.41%   |
| Fujitsu             | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 70        | 93     | 29.91%  |
| SanDisk             | 28        | 35     | 11.97%  |
| Kingston            | 26        | 33     | 11.11%  |
| Crucial             | 16        | 18     | 6.84%   |
| WDC                 | 15        | 16     | 6.41%   |
| China               | 9         | 10     | 3.85%   |
| A-DATA Technology   | 9         | 12     | 3.85%   |
| SPCC                | 6         | 8      | 2.56%   |
| PNY                 | 6         | 9      | 2.56%   |
| Intel               | 5         | 5      | 2.14%   |
| Apple               | 5         | 5      | 2.14%   |
| Patriot             | 3         | 4      | 1.28%   |
| Micron Technology   | 3         | 5      | 1.28%   |
| Seagate             | 2         | 2      | 0.85%   |
| LITEON              | 2         | 2      | 0.85%   |
| Intenso             | 2         | 3      | 0.85%   |
| Gigabyte Technology | 2         | 2      | 0.85%   |
| Apacer              | 2         | 2      | 0.85%   |
| AMD                 | 2         | 17     | 0.85%   |
| Zheino              | 1         | 1      | 0.43%   |
| Vaseky              | 1         | 1      | 0.43%   |
| USB30               | 1         | 1      | 0.43%   |
| Unknown             | 1         | 1      | 0.43%   |
| Transcend           | 1         | 1      | 0.43%   |
| Toshiba             | 1         | 1      | 0.43%   |
| Teclast             | 1         | 1      | 0.43%   |
| SK Hynix            | 1         | 1      | 0.43%   |
| PLEXTOR             | 1         | 1      | 0.43%   |
| OWC                 | 1         | 1      | 0.43%   |
| OCZ                 | 1         | 1      | 0.43%   |
| Netac               | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| KingSpec            | 1         | 1      | 0.43%   |
| KingDian            | 1         | 1      | 0.43%   |
| JMicron             | 1         | 1      | 0.43%   |
| HP Phison           | 1         | 1      | 0.43%   |
| GOODRAM             | 1         | 1      | 0.43%   |
| DOGFISH             | 1         | 1      | 0.43%   |
| BIWIN               | 1         | 1      | 0.43%   |
| Axiom               | 1         | 1      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 207       | 342    | 34.62%  |
| SSD     | 197       | 302    | 32.94%  |
| NVMe    | 153       | 209    | 25.59%  |
| MMC     | 27        | 32     | 4.52%   |
| Unknown | 14        | 17     | 2.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 322       | 634    | 61.33%  |
| NVMe | 153       | 209    | 29.14%  |
| MMC  | 27        | 32     | 5.14%   |
| SAS  | 23        | 27     | 4.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 243       | 389    | 58.13%  |
| 0.51-1.0   | 125       | 179    | 29.9%   |
| 1.01-2.0   | 29        | 47     | 6.94%   |
| 3.01-4.0   | 13        | 20     | 3.11%   |
| 4.01-10.0  | 5         | 6      | 1.2%    |
| 2.01-3.0   | 3         | 3      | 0.72%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 134       | 28.88%  |
| 251-500        | 129       | 27.8%   |
| 501-1000       | 74        | 15.95%  |
| 51-100         | 30        | 6.47%   |
| 1001-2000      | 29        | 6.25%   |
| 21-50          | 20        | 4.31%   |
| More than 3000 | 17        | 3.66%   |
| 1-20           | 13        | 2.8%    |
| 2001-3000      | 11        | 2.37%   |
| Unknown        | 7         | 1.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 158       | 33.55%  |
| 101-250        | 85        | 18.05%  |
| 21-50          | 82        | 17.41%  |
| 51-100         | 55        | 11.68%  |
| 251-500        | 41        | 8.7%    |
| 501-1000       | 20        | 4.25%   |
| 1001-2000      | 15        | 3.18%   |
| Unknown        | 7         | 1.49%   |
| More than 3000 | 6         | 1.27%   |
| 2001-3000      | 2         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 3         | 3      | 7.32%   |
| WDC WD5000AAKX-001CA0 500GB         | 2         | 2      | 4.88%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 4.88%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 4.88%   |
| WDC WD6400BPVT-60HXZT3 640GB        | 1         | 1      | 2.44%   |
| WDC WD6000HLHX-01JJPV0 600GB        | 1         | 1      | 2.44%   |
| WDC WD5000BPVT-00HXZT1 500GB        | 1         | 1      | 2.44%   |
| WDC WD5000AVCS-632DY1 500GB         | 1         | 1      | 2.44%   |
| WDC WD4003FZEX-00Z4SA0 4TB          | 1         | 1      | 2.44%   |
| WDC WD2500AAJS-60M0A0 250GB         | 1         | 1      | 2.44%   |
| WDC WD20EFRX-68EUZN0 2TB            | 1         | 2      | 2.44%   |
| WDC WD10EZEX-00RKKA0 1TB            | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB            | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 2.44%   |
| Toshiba MK5055GSX 500GB             | 1         | 1      | 2.44%   |
| Toshiba MK2561GSYN 250GB            | 1         | 1      | 2.44%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 2.44%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 2.44%   |
| Seagate ST5000DM000-1FK178 5TB      | 1         | 1      | 2.44%   |
| Seagate ST3500320AS 500GB           | 1         | 1      | 2.44%   |
| Seagate ST3320620AS 320GB           | 1         | 1      | 2.44%   |
| Seagate ST3160815AS 160GB           | 1         | 1      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 2.44%   |
| Seagate ST1000DX001-1NS162 1TB      | 1         | 1      | 2.44%   |
| Seagate ST1000DM003-1SB102 1TB      | 1         | 1      | 2.44%   |
| PNY SSD2SC120G3LC709B121-460I 120GB | 1         | 1      | 2.44%   |
| Patriot Pyro m3 240GB SSD           | 1         | 1      | 2.44%   |
| MAXTOR STM3250310AS 250GB           | 1         | 1      | 2.44%   |
| MAXTOR 6B200M0 208GB                | 1         | 2      | 2.44%   |
| Kingston SNS4151S316G 16GB SSD      | 1         | 1      | 2.44%   |
| HP Phison PSSBN032GA27MC1 32GB SSD  | 1         | 1      | 2.44%   |
| Hitachi HTS545025B9SA02 250GB       | 1         | 1      | 2.44%   |
| Hitachi HDS721032CLA362 320GB       | 1         | 1      | 2.44%   |
| HGST HTS725032A7E630 320GB          | 1         | 2      | 2.44%   |
| HGST HTS541075A9E680 752GB          | 1         | 1      | 2.44%   |
| Crucial CT500P1SSD8 500GB           | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 14        | 14     | 34.15%  |
| WDC       | 10        | 11     | 24.39%  |
| Toshiba   | 6         | 6      | 14.63%  |
| MAXTOR    | 2         | 3      | 4.88%   |
| Hitachi   | 2         | 2      | 4.88%   |
| HGST      | 2         | 3      | 4.88%   |
| PNY       | 1         | 1      | 2.44%   |
| Patriot   | 1         | 1      | 2.44%   |
| Kingston  | 1         | 1      | 2.44%   |
| HP Phison | 1         | 1      | 2.44%   |
| Crucial   | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 14     | 38.89%  |
| WDC     | 10        | 11     | 27.78%  |
| Toshiba | 6         | 6      | 16.67%  |
| MAXTOR  | 2         | 3      | 5.56%   |
| Hitachi | 2         | 2      | 5.56%   |
| HGST    | 2         | 3      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 39     | 86.11%  |
| SSD  | 4         | 4      | 11.11%  |
| NVMe | 1         | 1      | 2.78%   |

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
| Detected | 284       | 594    | 58.32%  |
| Works    | 167       | 264    | 34.29%  |
| Malfunc  | 36        | 44     | 7.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 317       | 57.32%  |
| Samsung Electronics           | 68        | 12.3%   |
| AMD                           | 62        | 11.21%  |
| Sandisk                       | 22        | 3.98%   |
| Phison Electronics            | 12        | 2.17%   |
| SK Hynix                      | 11        | 1.99%   |
| Marvell Technology Group      | 9         | 1.63%   |
| Toshiba America Info Systems  | 8         | 1.45%   |
| Micron/Crucial Technology     | 5         | 0.9%    |
| JMicron Technology            | 5         | 0.9%    |
| ASMedia Technology            | 5         | 0.9%    |
| Micron Technology             | 4         | 0.72%   |
| Silicon Motion                | 3         | 0.54%   |
| Nvidia                        | 3         | 0.54%   |
| KIOXIA                        | 3         | 0.54%   |
| Kingston Technology Company   | 3         | 0.54%   |
| Realtek Semiconductor         | 2         | 0.36%   |
| Lenovo                        | 2         | 0.36%   |
| ADATA Technology              | 2         | 0.36%   |
| Union Memory (Shenzhen)       | 1         | 0.18%   |
| Silicon Image                 | 1         | 0.18%   |
| Shenzhen Longsys Electronics  | 1         | 0.18%   |
| OCZ Technology Group          | 1         | 0.18%   |
| Integrated Technology Express | 1         | 0.18%   |
| Apple                         | 1         | 0.18%   |
| Adaptec                       | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 46        | 7.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 42        | 6.71%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 30        | 4.79%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 26        | 4.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 19        | 3.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 18        | 2.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 17        | 2.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13        | 2.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 12        | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 1.92%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 11        | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 10        | 1.6%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 9         | 1.44%   |
| Intel SATA Controller [RAID mode]                                                       | 9         | 1.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 1.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 1.44%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 8         | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                                  | 8         | 1.28%   |
| Samsung NVMe SSD Controller 980                                                         | 7         | 1.12%   |
| Phison E12 NVMe Controller                                                              | 7         | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 7         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 7         | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 7         | 1.12%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 7         | 1.12%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 7         | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 7         | 1.12%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 1.12%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 0.96%   |
| Intel SSD 660P Series                                                                   | 6         | 0.96%   |
| Intel Non-Volatile memory controller                                                    | 6         | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 0.96%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 5         | 0.8%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 5         | 0.8%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 5         | 0.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 0.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 0.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 5         | 0.8%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5         | 0.8%    |
| Sandisk PC SN520 NVMe SSD                                                               | 4         | 0.64%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 4         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.64%   |
| Micron Non-Volatile memory controller                                                   | 4         | 0.64%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 0.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 4         | 0.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 4         | 0.64%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 4         | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 0.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 3         | 0.48%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 0.48%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 3         | 0.48%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 3         | 0.48%   |
| KIOXIA Non-Volatile memory controller                                                   | 3         | 0.48%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 3         | 0.48%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 3         | 0.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 3         | 0.48%   |
| Intel 631xESB/632xESB IDE Controller                                                    | 3         | 0.48%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 0.48%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 0.48%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.48%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.48%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 322       | 57.6%   |
| NVMe | 155       | 27.73%  |
| IDE  | 48        | 8.59%   |
| RAID | 32        | 5.72%   |
| SAS  | 2         | 0.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 368       | 81.96%  |
| AMD    | 77        | 17.15%  |
| ARM    | 4         | 0.89%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 15        | 3.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 2.22%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 2%      |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 1.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 1.78%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 6         | 1.33%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 5         | 1.11%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 5         | 1.11%   |
| Intel Core i7-10710U CPU @ 1.10GHz            | 5         | 1.11%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 1.11%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 5         | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.89%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.89%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 4         | 0.89%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.89%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.89%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.89%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.89%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 3         | 0.67%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.67%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 3         | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 3         | 0.67%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 3         | 0.67%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.67%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 0.67%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 3         | 0.67%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.67%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.67%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.67%   |
| ARM Processor                                 | 3         | 0.67%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 0.67%   |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 0.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.67%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 0.67%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.67%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 3         | 0.67%   |
| Intel Xeon CPU 5150 @ 2.66GHz                 | 2         | 0.44%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 2         | 0.44%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 2         | 0.44%   |
| Intel Pentium CPU B950 @ 2.10GHz              | 2         | 0.44%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.44%   |
| Intel Core i7-9700K CPU @ 3.60GHz             | 2         | 0.44%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.44%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.44%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 2         | 0.44%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.44%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.44%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz            | 2         | 0.44%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.44%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.44%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.44%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.44%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 2         | 0.44%   |
| Intel Core i7-2600K CPU @ 3.40GHz             | 2         | 0.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.44%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 148       | 32.89%  |
| Intel Core i5           | 95        | 21.11%  |
| Intel Core i3           | 27        | 6%      |
| AMD Ryzen 5             | 23        | 5.11%   |
| Other                   | 21        | 4.67%   |
| AMD Ryzen 7             | 18        | 4%      |
| Intel Core 2 Duo        | 16        | 3.56%   |
| Intel Celeron           | 13        | 2.89%   |
| Intel Xeon              | 10        | 2.22%   |
| Intel Pentium           | 10        | 2.22%   |
| Intel Atom              | 7         | 1.56%   |
| Intel Core i9           | 5         | 1.11%   |
| Intel Core 2            | 5         | 1.11%   |
| Intel Pentium Dual      | 4         | 0.89%   |
| AMD Ryzen 9             | 4         | 0.89%   |
| AMD Ryzen 3             | 4         | 0.89%   |
| Intel Pentium Silver    | 3         | 0.67%   |
| Intel Genuine           | 3         | 0.67%   |
| AMD FX                  | 3         | 0.67%   |
| AMD E                   | 3         | 0.67%   |
| AMD A8                  | 3         | 0.67%   |
| AMD A6                  | 3         | 0.67%   |
| Intel Pentium Dual-Core | 2         | 0.44%   |
| Intel Core m3           | 2         | 0.44%   |
| AMD Turion 64 X2 Mobile | 2         | 0.44%   |
| AMD E1                  | 2         | 0.44%   |
| AMD A10                 | 2         | 0.44%   |
| Intel Pentium 4         | 1         | 0.22%   |
| Intel Core m5           | 1         | 0.22%   |
| Intel Core 2 Quad       | 1         | 0.22%   |
| ARM BCM                 | 1         | 0.22%   |
| AMD Sempron             | 1         | 0.22%   |
| AMD Ryzen Threadripper  | 1         | 0.22%   |
| AMD Quad-Core           | 1         | 0.22%   |
| AMD Phenom II X6        | 1         | 0.22%   |
| AMD Phenom II X2        | 1         | 0.22%   |
| AMD Embedded            | 1         | 0.22%   |
| AMD Athlon II           | 1         | 0.22%   |
| AMD A4                  | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 192       | 42.76%  |
| 2      | 161       | 35.86%  |
| 6      | 44        | 9.8%    |
| 8      | 36        | 8.02%   |
| 1      | 6         | 1.34%   |
| 16     | 4         | 0.89%   |
| 12     | 2         | 0.45%   |
| 3      | 2         | 0.45%   |
| 24     | 1         | 0.22%   |
| 14     | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 442       | 98.44%  |
| 2      | 7         | 1.56%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 318       | 70.67%  |
| 1      | 132       | 29.33%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 443       | 98.66%  |
| 32-bit         | 3         | 0.67%   |
| Unknown        | 3         | 0.67%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 116       | 25.11%  |
| 0x206a7    | 29        | 6.28%   |
| 0x306a9    | 28        | 6.06%   |
| 0x806ec    | 22        | 4.76%   |
| 0x306c3    | 21        | 4.55%   |
| 0x906ea    | 16        | 3.46%   |
| 0x806ea    | 15        | 3.25%   |
| 0x806e9    | 13        | 2.81%   |
| 0x40651    | 12        | 2.6%    |
| 0x1067a    | 12        | 2.6%    |
| 0x906e9    | 10        | 2.16%   |
| 0x806c1    | 10        | 2.16%   |
| 0x406e3    | 9         | 1.95%   |
| 0x506e3    | 8         | 1.73%   |
| 0x306d4    | 7         | 1.52%   |
| 0x806eb    | 6         | 1.3%    |
| 0x08600103 | 6         | 1.3%    |
| 0x30678    | 5         | 1.08%   |
| 0x106e5    | 5         | 1.08%   |
| 0xa0652    | 4         | 0.87%   |
| 0x706e5    | 4         | 0.87%   |
| 0x6fd      | 4         | 0.87%   |
| 0x20655    | 4         | 0.87%   |
| 0x08701021 | 4         | 0.87%   |
| 0x08108109 | 4         | 0.87%   |
| 0x0810100b | 4         | 0.87%   |
| 0x0800820d | 4         | 0.87%   |
| 0xa0660    | 3         | 0.65%   |
| 0x906ed    | 3         | 0.65%   |
| 0x906ec    | 3         | 0.65%   |
| 0x706a1    | 3         | 0.65%   |
| 0x6f6      | 3         | 0.65%   |
| 0x6f2      | 3         | 0.65%   |
| 0x406c4    | 3         | 0.65%   |
| 0x406c3    | 3         | 0.65%   |
| 0x10676    | 3         | 0.65%   |
| 0x0a50000c | 3         | 0.65%   |
| 0x08600104 | 3         | 0.65%   |
| 0x0600611a | 3         | 0.65%   |
| 0x05000119 | 3         | 0.65%   |
| 0x206d7    | 2         | 0.43%   |
| 0x20652    | 2         | 0.43%   |
| 0x08701013 | 2         | 0.43%   |
| 0x08600106 | 2         | 0.43%   |
| 0x0700010f | 2         | 0.43%   |
| 0x06000852 | 2         | 0.43%   |
| 0xf34      | 1         | 0.22%   |
| 0xa0671    | 1         | 0.22%   |
| 0xa0655    | 1         | 0.22%   |
| 0x906c0    | 1         | 0.22%   |
| 0x906a3    | 1         | 0.22%   |
| 0x806d1    | 1         | 0.22%   |
| 0x706a8    | 1         | 0.22%   |
| 0x6fb      | 1         | 0.22%   |
| 0x6fa      | 1         | 0.22%   |
| 0x506c9    | 1         | 0.22%   |
| 0x40661    | 1         | 0.22%   |
| 0x306f2    | 1         | 0.22%   |
| 0x306e4    | 1         | 0.22%   |
| 0x206c2    | 1         | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 117       | 26.06%  |
| IvyBridge        | 39        | 8.69%   |
| SandyBridge      | 38        | 8.46%   |
| Haswell          | 38        | 8.46%   |
| Zen 2            | 27        | 6.01%   |
| Skylake          | 19        | 4.23%   |
| Penryn           | 18        | 4.01%   |
| Core             | 14        | 3.12%   |
| Silvermont       | 13        | 2.9%    |
| TigerLake        | 12        | 2.67%   |
| CometLake        | 12        | 2.67%   |
| Zen+             | 10        | 2.23%   |
| Westmere         | 10        | 2.23%   |
| Broadwell        | 9         | 2%      |
| Zen              | 8         | 1.78%   |
| IceLake          | 8         | 1.78%   |
| Nehalem          | 7         | 1.56%   |
| Goldmont plus    | 7         | 1.56%   |
| Excavator        | 6         | 1.34%   |
| Unknown          | 5         | 1.11%   |
| Zen 3            | 4         | 0.89%   |
| Piledriver       | 4         | 0.89%   |
| K10              | 4         | 0.89%   |
| Puma             | 3         | 0.67%   |
| Jaguar           | 3         | 0.67%   |
| Bobcat           | 3         | 0.67%   |
| K8 Hammer        | 2         | 0.45%   |
| Bonnell          | 2         | 0.45%   |
| Tremont          | 1         | 0.22%   |
| Steamroller      | 1         | 0.22%   |
| P6               | 1         | 0.22%   |
| NetBurst         | 1         | 0.22%   |
| K10 Llano        | 1         | 0.22%   |
| Goldmont         | 1         | 0.22%   |
| Alderlake Hybrid | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 291       | 53.39%  |
| Nvidia                     | 150       | 27.52%  |
| AMD                        | 102       | 18.72%  |
| Matrox Electronics Systems | 1         | 0.18%   |
| ASPEED Technology          | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 5.23%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 3.96%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 3.96%   |
| Intel UHD Graphics 620                                                                   | 21        | 3.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 2.34%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 2.34%   |
| AMD Renoir                                                                               | 13        | 2.34%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 13        | 2.34%   |
| Intel HD Graphics 620                                                                    | 12        | 2.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 10        | 1.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 9         | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 1.44%   |
| Intel HD Graphics 630                                                                    | 8         | 1.44%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.26%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.26%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 6         | 1.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.9%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.9%    |
| Intel Comet Lake UHD Graphics                                                            | 5         | 0.9%    |
| Intel 82Q963/Q965 Integrated Graphics Controller                                         | 5         | 0.9%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.72%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 4         | 0.72%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.72%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 4         | 0.72%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.72%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 4         | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 4         | 0.72%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.54%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.54%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.54%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 0.54%   |
| Intel HD Graphics 530                                                                    | 3         | 0.54%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.54%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 0.54%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 3         | 0.54%   |
| AMD Cezanne                                                                              | 3         | 0.54%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.54%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.36%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.36%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 2         | 0.36%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.36%   |
| Nvidia GP108GLM [Quadro P520]                                                            | 2         | 0.36%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.36%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 207       | 45.49%  |
| 1 x AMD         | 74        | 16.26%  |
| 1 x Nvidia      | 73        | 16.04%  |
| Intel + Nvidia  | 66        | 14.51%  |
| Intel + AMD     | 15        | 3.3%    |
| AMD + Nvidia    | 9         | 1.98%   |
| Other           | 4         | 0.88%   |
| 2 x AMD         | 3         | 0.66%   |
| 2 x Nvidia      | 1         | 0.22%   |
| 2 x Intel       | 1         | 0.22%   |
| Nvidia + Matrox | 1         | 0.22%   |
| 1 x ASPEED      | 1         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 330       | 72.05%  |
| Proprietary | 115       | 25.11%  |
| Unknown     | 13        | 2.84%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 276       | 59.87%  |
| 1.01-2.0   | 52        | 11.28%  |
| 3.01-4.0   | 32        | 6.94%   |
| 0.01-0.5   | 29        | 6.29%   |
| 7.01-8.0   | 25        | 5.42%   |
| 5.01-6.0   | 22        | 4.77%   |
| 0.51-1.0   | 22        | 4.77%   |
| 2.01-3.0   | 2         | 0.43%   |
| 8.01-16.0  | 1         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 65        | 12.43%  |
| Chimei Innolux          | 64        | 12.24%  |
| Samsung Electronics     | 59        | 11.28%  |
| BOE                     | 41        | 7.84%   |
| LG Display              | 40        | 7.65%   |
| Dell                    | 38        | 7.27%   |
| Goldstar                | 21        | 4.02%   |
| Hewlett-Packard         | 17        | 3.25%   |
| Apple                   | 16        | 3.06%   |
| Acer                    | 15        | 2.87%   |
| AOC                     | 12        | 2.29%   |
| Ancor Communications    | 12        | 2.29%   |
| BenQ                    | 9         | 1.72%   |
| Sharp                   | 8         | 1.53%   |
| Chi Mei Optoelectronics | 8         | 1.53%   |
| Unknown                 | 7         | 1.34%   |
| Philips                 | 7         | 1.34%   |
| Lenovo                  | 7         | 1.34%   |
| PANDA                   | 6         | 1.15%   |
| ASUSTek Computer        | 6         | 1.15%   |
| LG Electronics          | 4         | 0.76%   |
| InfoVision              | 4         | 0.76%   |
| Iiyama                  | 4         | 0.76%   |
| Idek Iiyama             | 4         | 0.76%   |
| LGD                     | 3         | 0.57%   |
| Fujitsu Siemens         | 3         | 0.57%   |
| Eizo                    | 3         | 0.57%   |
| ViewSonic               | 2         | 0.38%   |
| Sony                    | 2         | 0.38%   |
| Sceptre Tech            | 2         | 0.38%   |
| MStar                   | 2         | 0.38%   |
| Medion                  | 2         | 0.38%   |
| AGO                     | 2         | 0.38%   |
| Vizio                   | 1         | 0.19%   |
| VIZ                     | 1         | 0.19%   |
| Vestel Elektronik       | 1         | 0.19%   |
| UPD                     | 1         | 0.19%   |
| Unknown (AAA)           | 1         | 0.19%   |
| Sun                     | 1         | 0.19%   |
| RTK                     | 1         | 0.19%   |
| Pioneer Electronic      | 1         | 0.19%   |
| Panasonic               | 1         | 0.19%   |
| Orion                   | 1         | 0.19%   |
| NEC Computers           | 1         | 0.19%   |
| MPI                     | 1         | 0.19%   |
| Microstep               | 1         | 0.19%   |
| LG Philips              | 1         | 0.19%   |
| Lacie                   | 1         | 0.19%   |
| KTC                     | 1         | 0.19%   |
| JDI                     | 1         | 0.19%   |
| ITE                     | 1         | 0.19%   |
| Insignia                | 1         | 0.19%   |
| InnoLux Display         | 1         | 0.19%   |
| Hyundai ImageQuest      | 1         | 0.19%   |
| Huion                   | 1         | 0.19%   |
| HCD                     | 1         | 0.19%   |
| HannStar                | 1         | 0.19%   |
| GDH                     | 1         | 0.19%   |
| Daewoo                  | 1         | 0.19%   |
| CSO                     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 5         | 0.9%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 4         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch        | 4         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 3         | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch         | 3         | 0.54%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                   | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch          | 3         | 0.54%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 3         | 0.54%   |
| Unknown LCD Monitor SAMSUNG                                             | 2         | 0.36%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch       | 2         | 0.36%   |
| Samsung Electronics S27B550 SAM091B 1920x1080 598x336mm 27.0-inch       | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch    | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 2         | 0.36%   |
| Samsung Electronics LCD Monitor SAM0BB4 3840x2160 1872x1053mm 84.6-inch | 2         | 0.36%   |
| Samsung Electronics LCD Monitor C34H89x 3440x1440                       | 2         | 0.36%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                 | 2         | 0.36%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                 | 2         | 0.36%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch                 | 2         | 0.36%   |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                        | 2         | 0.36%   |
| LGD LCD Monitor 1920x1080                                               | 2         | 0.36%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch            | 2         | 0.36%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch            | 2         | 0.36%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 2         | 0.36%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 2         | 0.36%   |
| InfoVision LCD Monitor IVO0579 1366x768 310x170mm 13.9-inch             | 2         | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                | 2         | 0.36%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2         | 0.36%   |
| Dell U3415W DELA0AA 3440x1440 800x330mm 34.1-inch                       | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15D7 1920x1080 344x193mm 15.5-inch        | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15BA 1920x1080 344x194mm 15.5-inch        | 2         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch         | 2         | 0.36%   |
| BOE LCD Monitor BOE0974 2560x1440 344x194mm 15.5-inch                   | 2         | 0.36%   |
| BenQ GW2780 BNQ78E6 1920x1080 600x340mm 27.2-inch                       | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch          | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch           | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO282B 3840x2160 293x165mm 13.2-inch          | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch           | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO13ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.36%   |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch           | 2         | 0.36%   |
| Ancor Communications ASUS PB238 ACI23A2 1920x1080 509x286mm 23.0-inch   | 2         | 0.36%   |
| Ancor Communications ASUS PA238 ACI23B1 1920x1080 509x286mm 23.0-inch   | 2         | 0.36%   |
| Vizio M260VA VIZ0067 1360x768 575x323mm 26.0-inch                       | 1         | 0.18%   |
| Vizio D55u-D1 VIZ1011 3840x2160 1209x680mm 54.6-inch                    | 1         | 0.18%   |
| VIZ LCD Monitor M50-C1 3840x2160                                        | 1         | 0.18%   |
| ViewSonic VX2476 Series VSC9939 1920x1080 527x296mm 23.8-inch           | 1         | 0.18%   |
| ViewSonic VA903 SERIES VSC111E 1280x1024 376x301mm 19.0-inch            | 1         | 0.18%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch    | 1         | 0.18%   |
| UPD LCD801 UPD4843 1920x1080 708x398mm 32.0-inch                        | 1         | 0.18%   |
| Unknown LCD Monitor Sony Nvidia Default Flat Panel 1366x768             | 1         | 0.18%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                   | 1         | 0.18%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                    | 1         | 0.18%   |
| Unknown LCD Monitor GTW KX2153                                          | 1         | 0.18%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 216       | 43.37%  |
| 1366x768 (WXGA)    | 94        | 18.88%  |
| 3840x2160 (4K)     | 28        | 5.62%   |
| 2560x1440 (QHD)    | 20        | 4.02%   |
| 1600x900 (HD+)     | 15        | 3.01%   |
| 1280x1024 (SXGA)   | 15        | 3.01%   |
| Unknown            | 14        | 2.81%   |
| 1920x1200 (WUXGA)  | 12        | 2.41%   |
| 1280x800 (WXGA)    | 10        | 2.01%   |
| 3440x1440          | 8         | 1.61%   |
| 2560x1080          | 8         | 1.61%   |
| 1680x1050 (WSXGA+) | 8         | 1.61%   |
| 3840x1080          | 6         | 1.2%    |
| 1440x900 (WXGA+)   | 5         | 1%      |
| 3200x1800 (QHD+)   | 4         | 0.8%    |
| 2880x1800          | 3         | 0.6%    |
| 2560x1600          | 3         | 0.6%    |
| 3520x1080          | 2         | 0.4%    |
| 2160x1440          | 2         | 0.4%    |
| 1600x1200          | 2         | 0.4%    |
| 7680x2160          | 1         | 0.2%    |
| 5760x2160          | 1         | 0.2%    |
| 4480x1080          | 1         | 0.2%    |
| 3840x2400          | 1         | 0.2%    |
| 3840x1440          | 1         | 0.2%    |
| 3840x1200          | 1         | 0.2%    |
| 3840x1100          | 1         | 0.2%    |
| 3600x1080          | 1         | 0.2%    |
| 3000x2000          | 1         | 0.2%    |
| 2880x1920          | 1         | 0.2%    |
| 2646x768           | 1         | 0.2%    |
| 2560x1024          | 1         | 0.2%    |
| 2390x768           | 1         | 0.2%    |
| 2288x1287          | 1         | 0.2%    |
| 2256x1504          | 1         | 0.2%    |
| 2048x1152          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1920x1280          | 1         | 0.2%    |
| 1400x1050          | 1         | 0.2%    |
| 1360x768           | 1         | 0.2%    |
| 1280x960           | 1         | 0.2%    |
| 1280x768           | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 135       | 26.01%  |
| 13      | 66        | 12.72%  |
| Unknown | 48        | 9.25%   |
| 14      | 43        | 8.29%   |
| 24      | 37        | 7.13%   |
| 27      | 34        | 6.55%   |
| 23      | 30        | 5.78%   |
| 17      | 22        | 4.24%   |
| 21      | 17        | 3.28%   |
| 19      | 12        | 2.31%   |
| 34      | 11        | 2.12%   |
| 12      | 8         | 1.54%   |
| 11      | 8         | 1.54%   |
| 31      | 7         | 1.35%   |
| 18      | 5         | 0.96%   |
| 54      | 4         | 0.77%   |
| 22      | 4         | 0.77%   |
| 20      | 4         | 0.77%   |
| 84      | 3         | 0.58%   |
| 52      | 2         | 0.39%   |
| 48      | 2         | 0.39%   |
| 32      | 2         | 0.39%   |
| 29      | 2         | 0.39%   |
| 28      | 2         | 0.39%   |
| 142     | 1         | 0.19%   |
| 72      | 1         | 0.19%   |
| 63      | 1         | 0.19%   |
| 46      | 1         | 0.19%   |
| 44      | 1         | 0.19%   |
| 42      | 1         | 0.19%   |
| 40      | 1         | 0.19%   |
| 37      | 1         | 0.19%   |
| 25      | 1         | 0.19%   |
| 16      | 1         | 0.19%   |
| 8       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 209       | 40.5%   |
| 501-600        | 94        | 18.22%  |
| 201-300        | 52        | 10.08%  |
| Unknown        | 48        | 9.3%    |
| 401-500        | 33        | 6.4%    |
| 351-400        | 30        | 5.81%   |
| 601-700        | 17        | 3.29%   |
| 701-800        | 13        | 2.52%   |
| 1001-1500      | 10        | 1.94%   |
| 1501-2000      | 4         | 0.78%   |
| 801-900        | 2         | 0.39%   |
| 901-1000       | 2         | 0.39%   |
| More than 2000 | 1         | 0.19%   |
| 101-200        | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 328       | 71.3%   |
| 16/10   | 44        | 9.57%   |
| Unknown | 43        | 9.35%   |
| 5/4     | 13        | 2.83%   |
| 21/9    | 13        | 2.83%   |
| 4/3     | 8         | 1.74%   |
| 3/2     | 6         | 1.3%    |
| 32/9    | 2         | 0.43%   |
| 6/5     | 1         | 0.22%   |
| 3.40    | 1         | 0.22%   |
| 1.00    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 133       | 25.83%  |
| 81-90          | 79        | 15.34%  |
| 201-250        | 65        | 12.62%  |
| Unknown        | 48        | 9.32%   |
| 301-350        | 34        | 6.6%    |
| 71-80          | 32        | 6.21%   |
| 351-500        | 22        | 4.27%   |
| 151-200        | 20        | 3.88%   |
| 251-300        | 18        | 3.5%    |
| 121-130        | 15        | 2.91%   |
| More than 1000 | 13        | 2.52%   |
| 51-60          | 9         | 1.75%   |
| 141-150        | 9         | 1.75%   |
| 501-1000       | 6         | 1.17%   |
| 61-70          | 5         | 0.97%   |
| 131-140        | 4         | 0.78%   |
| 91-100         | 2         | 0.39%   |
| 1-40           | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 137       | 27.35%  |
| 121-160       | 132       | 26.35%  |
| 101-120       | 116       | 23.15%  |
| Unknown       | 48        | 9.58%   |
| 161-240       | 35        | 6.99%   |
| More than 240 | 20        | 3.99%   |
| 1-50          | 13        | 2.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 343       | 74.73%  |
| 2     | 88        | 19.17%  |
| 3     | 14        | 3.05%   |
| 0     | 13        | 2.83%   |
| 4     | 1         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 247       | 35.34%  |
| Realtek Semiconductor                 | 235       | 33.62%  |
| Qualcomm Atheros                      | 84        | 12.02%  |
| Broadcom                              | 44        | 6.29%   |
| Broadcom Limited                      | 13        | 1.86%   |
| Marvell Technology Group              | 8         | 1.14%   |
| Ralink Technology                     | 7         | 1%      |
| Ralink                                | 7         | 1%      |
| Xiaomi                                | 3         | 0.43%   |
| Qualcomm Atheros Communications       | 3         | 0.43%   |
| Nvidia                                | 3         | 0.43%   |
| Microsoft                             | 3         | 0.43%   |
| Hewlett-Packard                       | 3         | 0.43%   |
| D-Link System                         | 3         | 0.43%   |
| ASIX Electronics                      | 3         | 0.43%   |
| Sierra Wireless                       | 2         | 0.29%   |
| OnePlus Technology (Shenzhen)         | 2         | 0.29%   |
| MEDIATEK                              | 2         | 0.29%   |
| Linksys                               | 2         | 0.29%   |
| Lenovo                                | 2         | 0.29%   |
| JMicron Technology                    | 2         | 0.29%   |
| Huawei Technologies                   | 2         | 0.29%   |
| Wacom                                 | 1         | 0.14%   |
| TP-Link                               | 1         | 0.14%   |
| Samsung Electronics                   | 1         | 0.14%   |
| Novatek Microelectronics              | 1         | 0.14%   |
| NetGear                               | 1         | 0.14%   |
| Mercucys                              | 1         | 0.14%   |
| Luminary Micro                        | 1         | 0.14%   |
| Google                                | 1         | 0.14%   |
| Exar                                  | 1         | 0.14%   |
| Ericsson Business Mobile Networks     | 1         | 0.14%   |
| Edimax Technology                     | 1         | 0.14%   |
| DisplayLink                           | 1         | 0.14%   |
| Dell                                  | 1         | 0.14%   |
| D-Link                                | 1         | 0.14%   |
| BUFFALO                               | 1         | 0.14%   |
| Belkin Components                     | 1         | 0.14%   |
| ASUSTek Computer                      | 1         | 0.14%   |
| Apple                                 | 1         | 0.14%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 151       | 18.44%  |
| Intel Wi-Fi 6 AX200                                               | 42        | 5.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 27        | 3.3%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 26        | 3.17%   |
| Intel Wireless 8265 / 8275                                        | 23        | 2.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 2.08%   |
| Intel Wireless-AC 9260                                            | 17        | 2.08%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 1.47%   |
| Intel Wireless 7265                                               | 12        | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 1.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 1.34%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 10        | 1.22%   |
| Intel Wireless 8260                                               | 9         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.1%    |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.73%   |
| Intel Wireless 7260                                               | 6         | 0.73%   |
| Intel I211 Gigabit Network Connection                             | 6         | 0.73%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.61%   |
| Intel Wireless 3165                                               | 5         | 0.61%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 5         | 0.61%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.61%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.49%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 4         | 0.49%   |
| Intel Centrino Ultimate-N 6300                                    | 4         | 0.49%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.49%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.37%   |
| Realtek 802.11ac NIC                                              | 3         | 0.37%   |
| Ralink MT7601U Wireless Adapter                                   | 3         | 0.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.37%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3         | 0.37%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.37%   |
| Intel WiFi Link 5100                                              | 3         | 0.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 0.37%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.37%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.37%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.37%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.37%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.37%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.37%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 202       | 51.4%   |
| Qualcomm Atheros                      | 66        | 16.79%  |
| Realtek Semiconductor                 | 47        | 11.96%  |
| Broadcom                              | 29        | 7.38%   |
| Broadcom Limited                      | 10        | 2.54%   |
| Ralink Technology                     | 7         | 1.78%   |
| Ralink                                | 7         | 1.78%   |
| Qualcomm Atheros Communications       | 3         | 0.76%   |
| Microsoft                             | 3         | 0.76%   |
| Sierra Wireless                       | 2         | 0.51%   |
| MEDIATEK                              | 2         | 0.51%   |
| Linksys                               | 2         | 0.51%   |
| D-Link System                         | 2         | 0.51%   |
| Wacom                                 | 1         | 0.25%   |
| TP-Link                               | 1         | 0.25%   |
| NetGear                               | 1         | 0.25%   |
| Mercucys                              | 1         | 0.25%   |
| Marvell Technology Group              | 1         | 0.25%   |
| Edimax Technology                     | 1         | 0.25%   |
| D-Link                                | 1         | 0.25%   |
| BUFFALO                               | 1         | 0.25%   |
| Belkin Components                     | 1         | 0.25%   |
| ASUSTek Computer                      | 1         | 0.25%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 42        | 10.63%  |
| Intel Wireless 8265 / 8275                                     | 23        | 5.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 4.3%    |
| Intel Wireless-AC 9260                                         | 17        | 4.3%    |
| Intel Wireless 7265                                            | 12        | 3.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 3.04%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 2.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 2.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 10        | 2.53%   |
| Intel Wireless 8260                                            | 9         | 2.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 8         | 2.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 1.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 1.52%   |
| Intel Wireless 7260                                            | 6         | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 1.27%   |
| Intel Wireless 3165                                            | 5         | 1.27%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 1.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 1.01%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.01%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 1.01%   |
| Realtek 802.11ac NIC                                           | 3         | 0.76%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.76%   |
| Qualcomm Atheros AR9271 802.11n                                | 3         | 0.76%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 0.76%   |
| Intel WiFi Link 5100                                           | 3         | 0.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 0.76%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.76%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.76%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.76%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 0.76%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 0.76%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.51%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.51%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 0.51%   |
| Ralink RT5372 Wireless Adapter                                 | 2         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.51%   |
| Microsoft Xbox 360 Wireless Adapter                            | 2         | 0.51%   |
| Linksys WUSB54GC v1 802.11g Adapter [Ralink RT73]              | 2         | 0.51%   |
| Intel Wireless 3160                                            | 2         | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 0.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 0.51%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.51%   |
| Intel Centrino Wireless-N 2200                                 | 2         | 0.51%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 2         | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 213       | 52.72%  |
| Intel                         | 111       | 27.48%  |
| Qualcomm Atheros              | 25        | 6.19%   |
| Broadcom                      | 24        | 5.94%   |
| Marvell Technology Group      | 7         | 1.73%   |
| Xiaomi                        | 3         | 0.74%   |
| Nvidia                        | 3         | 0.74%   |
| Broadcom Limited              | 3         | 0.74%   |
| ASIX Electronics              | 3         | 0.74%   |
| OnePlus Technology (Shenzhen) | 2         | 0.5%    |
| Lenovo                        | 2         | 0.5%    |
| JMicron Technology            | 2         | 0.5%    |
| Samsung Electronics           | 1         | 0.25%   |
| Hewlett-Packard               | 1         | 0.25%   |
| Google                        | 1         | 0.25%   |
| DisplayLink                   | 1         | 0.25%   |
| D-Link System                 | 1         | 0.25%   |
| Apple                         | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 151       | 36.39%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 27        | 6.51%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 26        | 6.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 22        | 5.3%    |
| Realtek RTL8125 2.5GbE Controller                                              | 12        | 2.89%   |
| Intel Ethernet Connection (7) I219-V                                           | 8         | 1.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 1.69%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 1.69%   |
| Intel I211 Gigabit Network Connection                                          | 6         | 1.45%   |
| Intel Ethernet Connection (6) I219-V                                           | 6         | 1.45%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 1.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                                          | 5         | 1.2%    |
| Intel Ethernet Connection (2) I219-V                                           | 5         | 1.2%    |
| Intel 82579V Gigabit Network Connection                                        | 5         | 1.2%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 4         | 0.96%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.72%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 3         | 0.72%   |
| Intel I210 Gigabit Network Connection                                          | 3         | 0.72%   |
| Intel Ethernet Controller I225-V                                               | 3         | 0.72%   |
| Intel Ethernet Connection I219-LM                                              | 3         | 0.72%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 0.72%   |
| Intel Ethernet Connection (6) I219-LM                                          | 3         | 0.72%   |
| Intel Ethernet Connection (2) I218-V                                           | 3         | 0.72%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 0.72%   |
| Intel 82566DM Gigabit Network Connection                                       | 3         | 0.72%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 3         | 0.72%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 3         | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 2         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.48%   |
| OnePlus (Shenzhen) AC2001                                                      | 2         | 0.48%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.48%   |
| Intel I350 Gigabit Network Connection                                          | 2         | 0.48%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.48%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.48%   |
| Intel 82577LM Gigabit Network Connection                                       | 2         | 0.48%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 2         | 0.48%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                        | 2         | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 2         | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.24%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.24%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.24%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.24%   |
| Nvidia MCP79 Ethernet                                                          | 1         | 0.24%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.24%   |
| Nvidia MCP51 Ethernet Controller                                               | 1         | 0.24%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.24%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.24%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 1         | 0.24%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.24%   |
| Lenovo Thinkpad USB LAN                                                        | 1         | 0.24%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 1         | 0.24%   |
| Intel PRO/100 VE Network Connection                                            | 1         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 381       | 50%     |
| WiFi     | 372       | 48.82%  |
| Modem    | 9         | 1.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 337       | 55.61%  |
| Ethernet | 268       | 44.22%  |
| Modem    | 1         | 0.17%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 266       | 59.11%  |
| 1     | 161       | 35.78%  |
| 3     | 12        | 2.67%   |
| 0     | 11        | 2.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 395       | 86.81%  |
| Yes  | 60        | 13.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 165       | 51.72%  |
| Qualcomm Atheros Communications | 28        | 8.78%   |
| Cambridge Silicon Radio         | 21        | 6.58%   |
| Realtek Semiconductor           | 20        | 6.27%   |
| Apple                           | 18        | 5.64%   |
| Broadcom                        | 14        | 4.39%   |
| Lite-On Technology              | 10        | 3.13%   |
| IMC Networks                    | 8         | 2.51%   |
| Foxconn / Hon Hai               | 8         | 2.51%   |
| Hewlett-Packard                 | 5         | 1.57%   |
| Dell                            | 4         | 1.25%   |
| Realtek                         | 3         | 0.94%   |
| Ralink                          | 3         | 0.94%   |
| ASUSTek Computer                | 3         | 0.94%   |
| Toshiba                         | 2         | 0.63%   |
| Belkin Components               | 2         | 0.63%   |
| Unknown                         | 1         | 0.31%   |
| MediaTek                        | 1         | 0.31%   |
| Marvell Semiconductor           | 1         | 0.31%   |
| Integrated System Solution      | 1         | 0.31%   |
| Foxconn International           | 1         | 0.31%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 56        | 17.55%  |
| Intel AX200 Bluetooth                                                               | 40        | 12.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 6.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 21        | 6.58%   |
| Intel Bluetooth Device                                                              | 18        | 5.64%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 17        | 5.33%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 4.08%   |
| Realtek Bluetooth Radio                                                             | 9         | 2.82%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 8         | 2.51%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 1.88%   |
| Lite-On Bluetooth Device                                                            | 6         | 1.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.88%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 1.88%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.57%   |
| Apple Bluetooth Host Controller                                                     | 5         | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 1.25%   |
| IMC Networks Bluetooth Device                                                       | 4         | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 1.25%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 1.25%   |
| Realtek Bluetooth Radio                                                             | 3         | 0.94%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.94%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.94%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 3         | 0.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.94%   |
| Apple Bluetooth HCI                                                                 | 3         | 0.94%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 0.63%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.63%   |
| Intel AX210 Bluetooth                                                               | 2         | 0.63%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.63%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.63%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 2         | 0.63%   |
| Unknown Bluetooth Device                                                            | 1         | 0.31%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.31%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.31%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.31%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.31%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.31%   |
| MediaTek Wireless_Device                                                            | 1         | 0.31%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.31%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.31%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.31%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.31%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 1         | 0.31%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.31%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.31%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology                         | 1         | 0.31%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.31%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.31%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.31%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 1         | 0.31%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 1         | 0.31%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.31%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.31%   |
| Broadcom BRCM2070 BT 2.1 + HS USB Module                                            | 1         | 0.31%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                                    | 1         | 0.31%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.31%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 1         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 356       | 56.24%  |
| Nvidia                    | 105       | 16.59%  |
| AMD                       | 102       | 16.11%  |
| C-Media Electronics       | 9         | 1.42%   |
| Realtek Semiconductor     | 7         | 1.11%   |
| Logitech                  | 6         | 0.95%   |
| JMTek                     | 4         | 0.63%   |
| GN Netcom                 | 4         | 0.63%   |
| Creative Labs             | 4         | 0.63%   |
| Sennheiser Communications | 3         | 0.47%   |
| Kingston Technology       | 3         | 0.47%   |
| Creative Technology       | 3         | 0.47%   |
| Samson Technologies       | 2         | 0.32%   |
| Focusrite-Novation        | 2         | 0.32%   |
| Blue Microphones          | 2         | 0.32%   |
| XMOS                      | 1         | 0.16%   |
| Texas Instruments         | 1         | 0.16%   |
| SteelSeries ApS           | 1         | 0.16%   |
| Razer USA                 | 1         | 0.16%   |
| Plantronics               | 1         | 0.16%   |
| OPPO Electronics          | 1         | 0.16%   |
| No brand                  | 1         | 0.16%   |
| Native Instruments        | 1         | 0.16%   |
| Nam Tai E&E Products      | 1         | 0.16%   |
| Microsoft                 | 1         | 0.16%   |
| M-Audio                   | 1         | 0.16%   |
| Lenovo                    | 1         | 0.16%   |
| Hewlett-Packard           | 1         | 0.16%   |
| Giga-Byte Technology      | 1         | 0.16%   |
| Generalplus Technology    | 1         | 0.16%   |
| Conexant Systems          | 1         | 0.16%   |
| CMX Systems               | 1         | 0.16%   |
| Cambridge Audio           | 1         | 0.16%   |
| Bose                      | 1         | 0.16%   |
| Apple                     | 1         | 0.16%   |
| AKAI Professional M.I.    | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 48        | 6.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 38        | 5.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 34        | 4.65%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 28        | 3.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 24        | 3.28%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 3.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 20        | 2.74%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 18        | 2.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 2.33%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 14        | 1.92%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 14        | 1.92%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 13        | 1.78%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 1.78%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 1.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 1.78%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 13        | 1.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 1.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 1.64%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 1.5%    |
| AMD FCH Azalia Controller                                                                         | 11        | 1.5%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.23%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 1.23%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 1.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 1.09%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.09%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.09%   |
| Realtek Semiconductor USB Audio                                                                   | 7         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 0.96%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 0.96%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 7         | 0.96%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 6         | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.68%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 0.68%   |
| Nvidia TU104 HD Audio Controller                                                                  | 4         | 0.55%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 0.55%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.55%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 0.55%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 4         | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 0.55%   |
| AMD Navi 10 HDMI Audio                                                                            | 4         | 0.55%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.55%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.55%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.41%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.41%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.41%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.41%   |
| Nvidia Audio device                                                                               | 3         | 0.41%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 80        | 27.97%  |
| SK Hynix            | 59        | 20.63%  |
| Kingston            | 26        | 9.09%   |
| Micron Technology   | 25        | 8.74%   |
| Unknown             | 19        | 6.64%   |
| Crucial             | 17        | 5.94%   |
| Corsair             | 10        | 3.5%    |
| Ramaxel Technology  | 9         | 3.15%   |
| G.Skill             | 6         | 2.1%    |
| A-DATA Technology   | 5         | 1.75%   |
| Unknown (ABCD)      | 3         | 1.05%   |
| Team                | 3         | 1.05%   |
| Smart               | 2         | 0.7%    |
| PNY                 | 2         | 0.7%    |
| Nanya Technology    | 2         | 0.7%    |
| Unknown             | 2         | 0.7%    |
| Unknown (F301)      | 1         | 0.35%   |
| Unknown (0x873E)    | 1         | 0.35%   |
| Transcend           | 1         | 0.35%   |
| TIMETEC             | 1         | 0.35%   |
| Teikon              | 1         | 0.35%   |
| SMART Brazil        | 1         | 0.35%   |
| Sesame              | 1         | 0.35%   |
| Patriot             | 1         | 0.35%   |
| Kingmax             | 1         | 0.35%   |
| GOODRAM             | 1         | 0.35%   |
| Goldkey             | 1         | 0.35%   |
| Elpida              | 1         | 0.35%   |
| Cors                | 1         | 0.35%   |
| Avant               | 1         | 0.35%   |
| ASint Technology    | 1         | 0.35%   |
| Apacer              | 1         | 0.35%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 5         | 1.65%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 5         | 1.65%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 1.65%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 5         | 1.65%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.32%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 4         | 1.32%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 0.99%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.99%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 3         | 0.99%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.99%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.99%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.99%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 0.99%   |
| Samsung RAM K4EBE304EC-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.99%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.99%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.99%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 2         | 0.66%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.66%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 2         | 0.66%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.66%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 2         | 0.66%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.66%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.66%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.66%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.66%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.66%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 2         | 0.66%   |
| Kingston RAM 9905403-199.A00LF 4GB DIMM DDR3 1600MT/s            | 2         | 0.66%   |
| Crucial RAM BLS4G4D240FSB.8FBD 4GB DIMM DDR4 2400MT/s            | 2         | 0.66%   |
| Corsair RAM CMW32GX4M2C3200C16 16384MB DIMM DDR4 3200MT/s        | 2         | 0.66%   |
| Unknown                                                          | 2         | 0.66%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.33%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s                     | 1         | 0.33%   |
| Unknown RAM Module 512MB DIMM 533MT/s                            | 1         | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.33%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 1         | 0.33%   |
| Unknown RAM Module 4096MB SODIMM DDR2 667MT/s                    | 1         | 0.33%   |
| Unknown RAM Module 4096MB SODIMM                                 | 1         | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR 1066MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                           | 1         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3 1066MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.33%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 0.33%   |
| Unknown RAM Module 2048MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR 1066MT/s                      | 1         | 0.33%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 1         | 0.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.33%   |
| Unknown RAM Module 1024MB DIMM DDR2                              | 1         | 0.33%   |
| Unknown (F301) RAM G2RT-4AFT00 16384MB SODIMM DDR4 2667MT/s      | 1         | 0.33%   |
| Unknown (0x873E) RAM Module 8192MB DIMM DDR3 1333MT/s            | 1         | 0.33%   |
| Transcend RAM Module 2048MB DIMM DDR2 800MT/s                    | 1         | 0.33%   |
| TIMETEC RAM ED3-1600 8192MB DIMM DDR3 1600MT/s                   | 1         | 0.33%   |
| Teikon RAM TMT451S6BFR8A-PBAJ 4096MB SODIMM DDR3 1600MT/s        | 1         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 116       | 46.59%  |
| DDR3    | 89        | 35.74%  |
| LPDDR3  | 13        | 5.22%   |
| LPDDR4  | 9         | 3.61%   |
| DDR2    | 9         | 3.61%   |
| SDRAM   | 7         | 2.81%   |
| Unknown | 4         | 1.61%   |
| DDR     | 2         | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 159       | 64.9%   |
| DIMM         | 60        | 24.49%  |
| Row Of Chips | 21        | 8.57%   |
| FB-DIMM      | 2         | 0.82%   |
| RIMM         | 1         | 0.41%   |
| Chip         | 1         | 0.41%   |
| Unknown      | 1         | 0.41%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 96        | 35.42%  |
| 4096  | 86        | 31.73%  |
| 16384 | 40        | 14.76%  |
| 2048  | 27        | 9.96%   |
| 32768 | 11        | 4.06%   |
| 1024  | 9         | 3.32%   |
| 512   | 2         | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 61        | 22.26%  |
| 2667    | 60        | 21.9%   |
| 3200    | 27        | 9.85%   |
| 2400    | 22        | 8.03%   |
| 2133    | 19        | 6.93%   |
| 1333    | 19        | 6.93%   |
| 1334    | 7         | 2.55%   |
| 667     | 6         | 2.19%   |
| Unknown | 6         | 2.19%   |
| 3266    | 5         | 1.82%   |
| 1867    | 5         | 1.82%   |
| 1067    | 4         | 1.46%   |
| 800     | 4         | 1.46%   |
| 4267    | 3         | 1.09%   |
| 4199    | 3         | 1.09%   |
| 3600    | 3         | 1.09%   |
| 1066    | 3         | 1.09%   |
| 533     | 3         | 1.09%   |
| 4266    | 1         | 0.36%   |
| 3733    | 1         | 0.36%   |
| 3500    | 1         | 0.36%   |
| 3466    | 1         | 0.36%   |
| 3007    | 1         | 0.36%   |
| 3000    | 1         | 0.36%   |
| 2933    | 1         | 0.36%   |
| 2666    | 1         | 0.36%   |
| 2134    | 1         | 0.36%   |
| 2048    | 1         | 0.36%   |
| 1866    | 1         | 0.36%   |
| 1800    | 1         | 0.36%   |
| 1639    | 1         | 0.36%   |
| 400     | 1         | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 30%     |
| Canon               | 3         | 30%     |
| Sharp               | 1         | 10%     |
| Samsung Electronics | 1         | 10%     |
| Fuji Xerox          | 1         | 10%     |
| Brother Industries  | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Sharp AL-2030                 | 1         | 10%     |
| Samsung M2020 Series          | 1         | 10%     |
| HP Deskjet 3050 J610 series   | 1         | 10%     |
| HP Deskjet 2540 series        | 1         | 10%     |
| HP DeskJet 2130 series        | 1         | 10%     |
| Fuji Xerox DocuPrint CM305 df | 1         | 10%     |
| Canon TR7500 series           | 1         | 10%     |
| Canon MF4010 series           | 1         | 10%     |
| Canon MF240 Series V4         | 1         | 10%     |
| Brother MFC-1810              | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 33.33%  |
| Canon CanoScan LiDE 120 | 1         | 33.33%  |
| Canon CanoScan LiDE 110 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 72        | 23.38%  |
| Acer                                   | 28        | 9.09%   |
| Sunplus Innovation Technology          | 26        | 8.44%   |
| Realtek Semiconductor                  | 26        | 8.44%   |
| Microdia                               | 24        | 7.79%   |
| IMC Networks                           | 24        | 7.79%   |
| Apple                                  | 16        | 5.19%   |
| Logitech                               | 15        | 4.87%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 3.9%    |
| Suyin                                  | 8         | 2.6%    |
| Quanta                                 | 8         | 2.6%    |
| Syntek                                 | 7         | 2.27%   |
| Silicon Motion                         | 6         | 1.95%   |
| Lite-On Technology                     | 5         | 1.62%   |
| Ricoh                                  | 3         | 0.97%   |
| Microsoft                              | 3         | 0.97%   |
| Generalplus Technology                 | 3         | 0.97%   |
| Luxvisions Innotech Limited            | 2         | 0.65%   |
| LG Electronics                         | 2         | 0.65%   |
| ARC International                      | 2         | 0.65%   |
| Z-Star Microelectronics                | 1         | 0.32%   |
| USB Camera                             | 1         | 0.32%   |
| Tobii Technology AB                    | 1         | 0.32%   |
| Sonix Technology                       | 1         | 0.32%   |
| Samsung Electronics                    | 1         | 0.32%   |
| Primax Electronics                     | 1         | 0.32%   |
| OPPO Electronics                       | 1         | 0.32%   |
| Omnivision                             | 1         | 0.32%   |
| Linux Foundation                       | 1         | 0.32%   |
| IPEVO                                  | 1         | 0.32%   |
| Importek                               | 1         | 0.32%   |
| Guillemot                              | 1         | 0.32%   |
| Cubeternet                             | 1         | 0.32%   |
| Creative Technology                    | 1         | 0.32%   |
| Alcor Micro                            | 1         | 0.32%   |
| Unknown                                | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony USB2.0 Camera                                   | 14        | 4.52%   |
| Chicony HD Webcam                                       | 12        | 3.87%   |
| Chicony Integrated Camera                               | 10        | 3.23%   |
| Microdia Integrated_Webcam_HD                           | 9         | 2.9%    |
| Realtek Integrated_Webcam_HD                            | 8         | 2.58%   |
| IMC Networks Integrated Camera                          | 8         | 2.58%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 6         | 1.94%   |
| Acer Integrated Camera                                  | 6         | 1.94%   |
| Chicony HP HD Camera                                    | 5         | 1.61%   |
| Apple FaceTime HD Camera (Built-in)                     | 5         | 1.61%   |
| Acer HD Webcam                                          | 5         | 1.61%   |
| Acer BisonCam,NB Pro                                    | 5         | 1.61%   |
| Sunplus HD WebCam                                       | 4         | 1.29%   |
| IMC Networks VGA UVC WebCam                             | 4         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 4         | 1.29%   |
| Apple FaceTime HD Camera                                | 4         | 1.29%   |
| Apple Built-in iSight                                   | 4         | 1.29%   |
| Sunplus Asus Webcam                                     | 3         | 0.97%   |
| Realtek USB2.0 HD UVC WebCam                            | 3         | 0.97%   |
| Realtek Integrated Webcam                               | 3         | 0.97%   |
| Microdia Sonix USB 2.0 Camera                           | 3         | 0.97%   |
| Logitech HD Pro Webcam C920                             | 3         | 0.97%   |
| Chicony Integrated Camera [ThinkPad]                    | 3         | 0.97%   |
| Chicony Integrated Camera (1280x720@30)                 | 3         | 0.97%   |
| Apple iPhone 5/5C/5S/6/SE                               | 3         | 0.97%   |
| Acer BisonCam, NB Pro                                   | 3         | 0.97%   |
| Syntek Integrated Camera                                | 2         | 0.65%   |
| Syntek EasyCamera                                       | 2         | 0.65%   |
| Suyin HP Truevision HD                                  | 2         | 0.65%   |
| Sunplus USB Camera                                      | 2         | 0.65%   |
| Sunplus Lenovo EasyCamera                               | 2         | 0.65%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 0.65%   |
| Sunplus Integrated_Webcam_FHD                           | 2         | 0.65%   |
| Sunplus HP HD Webcam [Fixed]                            | 2         | 0.65%   |
| Sunplus HD User Facing                                  | 2         | 0.65%   |
| Realtek Lenovo EasyCamera                               | 2         | 0.65%   |
| Realtek HP "Truevision HD" laptop camera                | 2         | 0.65%   |
| Realtek HD WebCam                                       | 2         | 0.65%   |
| Microsoft LifeCam HD-3000                               | 2         | 0.65%   |
| Logitech Webcam C270                                    | 2         | 0.65%   |
| Logitech Webcam B500                                    | 2         | 0.65%   |
| IMC Networks ov9734_azurewave_camera                    | 2         | 0.65%   |
| IMC Networks HD Camera                                  | 2         | 0.65%   |
| Generalplus GENERAL WEBCAM                              | 2         | 0.65%   |
| Chicony thinkpad t430s camera                           | 2         | 0.65%   |
| Chicony HP Wide Vision FHD Camera                       | 2         | 0.65%   |
| Chicony HD WebCam (Asus N-series)                       | 2         | 0.65%   |
| Chicony FJ Camera                                       | 2         | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 2         | 0.65%   |
| ARC International Camera                                | 2         | 0.65%   |
| Acer SunplusIT Integrated Camera                        | 2         | 0.65%   |
| Acer EasyCamera                                         | 2         | 0.65%   |
| Z-Star Lenovo EasyCamera                                | 1         | 0.32%   |
| USB Camera USB Camera                                   | 1         | 0.32%   |
| Tobii AB EyeChip                                        | 1         | 0.32%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                    | 1         | 0.32%   |
| Syntek USB2.0 Camera                                    | 1         | 0.32%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.32%   |
| Suyin Webcam-101                                        | 1         | 0.32%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 30        | 41.1%   |
| Validity Sensors           | 22        | 30.14%  |
| Shenzhen Goodix Technology | 9         | 12.33%  |
| LighTuning Technology      | 6         | 8.22%   |
| Elan Microelectronics      | 4         | 5.48%   |
| AuthenTec                  | 2         | 2.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 12        | 16.44%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 9.59%   |
| Shenzhen Goodix  Fingerprint Device                                        | 7         | 9.59%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 8.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.48%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 5.48%   |
| Synaptics WBDI Device                                                      | 4         | 5.48%   |
| Elan ELAN:Fingerprint                                                      | 4         | 5.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 4.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 4.11%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.74%   |
| Validity Sensors VFS491                                                    | 2         | 2.74%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 2.74%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2.74%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 2.74%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1.37%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.37%   |
| Synaptics  WBDI                                                            | 1         | 1.37%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.37%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.37%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.37%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.37%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.37%   |
| AuthenTec AES1600                                                          | 1         | 1.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 47.37%  |
| Upek        | 5         | 26.32%  |
| Alcor Micro | 3         | 15.79%  |
| Lenovo      | 2         | 10.53%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 26.32%  |
| Broadcom BCM5880 Secure Applications Processor                               | 3         | 15.79%  |
| Broadcom 5880                                                                | 3         | 15.79%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 15.79%  |
| Lenovo Integrated Smart Card Reader                                          | 2         | 10.53%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 10.53%  |
| Broadcom 58200                                                               | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 308       | 67.84%  |
| 1     | 118       | 25.99%  |
| 2     | 25        | 5.51%   |
| 3     | 2         | 0.44%   |
| 4     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 72        | 42.86%  |
| Graphics card            | 32        | 19.05%  |
| Chipcard                 | 18        | 10.71%  |
| Net/wireless             | 13        | 7.74%   |
| Communication controller | 13        | 7.74%   |
| Multimedia controller    | 4         | 2.38%   |
| Camera                   | 4         | 2.38%   |
| Storage                  | 3         | 1.79%   |
| Card reader              | 3         | 1.79%   |
| Bluetooth                | 3         | 1.79%   |
| Unassigned class         | 1         | 0.6%    |
| Sound                    | 1         | 0.6%    |
| Net/ethernet             | 1         | 0.6%    |

