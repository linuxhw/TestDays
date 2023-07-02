Manjaro - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Manjaro.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Manjaro/Desktop/README.md) and [notebooks](/Dist/Manjaro/Notebook/README.md).

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

Total: 10158

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Teclast       | F15Plus 2                   | Notebook    | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [292b7f6f0f](https://linux-hardware.org/?probe=292b7f6f0f) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [559c10480e](https://linux-hardware.org/?probe=559c10480e) | Jun 30, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [661dc06ef7](https://linux-hardware.org/?probe=661dc06ef7) | Jun 30, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e555922bb2](https://linux-hardware.org/?probe=e555922bb2) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | Notebook    | [954ac9a8e4](https://linux-hardware.org/?probe=954ac9a8e4) | Jun 30, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [265cbaedcc](https://linux-hardware.org/?probe=265cbaedcc) | Jun 30, 2023 |
| HP            | 89B5 A                      | Desktop     | [f0330163de](https://linux-hardware.org/?probe=f0330163de) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [9d40263129](https://linux-hardware.org/?probe=9d40263129) | Jun 30, 2023 |
| LG Electro... | 16Z90P-G.AA55H              | Notebook    | [4e47d108a0](https://linux-hardware.org/?probe=4e47d108a0) | Jun 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [1c349accca](https://linux-hardware.org/?probe=1c349accca) | Jun 29, 2023 |
| Alienware     | 17 R4                       | Notebook    | [e7f3110f1f](https://linux-hardware.org/?probe=e7f3110f1f) | Jun 29, 2023 |
| Google        | Reef                        | Notebook    | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b94582735c](https://linux-hardware.org/?probe=b94582735c) | Jun 28, 2023 |
| Acer          | Aspire VN7-593G             | Notebook    | [2302cbfba7](https://linux-hardware.org/?probe=2302cbfba7) | Jun 28, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [81bbfe3459](https://linux-hardware.org/?probe=81bbfe3459) | Jun 28, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [ebb41279ae](https://linux-hardware.org/?probe=ebb41279ae) | Jun 28, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [32e4f74711](https://linux-hardware.org/?probe=32e4f74711) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [2debd02f0c](https://linux-hardware.org/?probe=2debd02f0c) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [3b775b8099](https://linux-hardware.org/?probe=3b775b8099) | Jun 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [6f96789257](https://linux-hardware.org/?probe=6f96789257) | Jun 27, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [f46408c9b6](https://linux-hardware.org/?probe=f46408c9b6) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0c87fda1f9](https://linux-hardware.org/?probe=0c87fda1f9) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [f94b4ddd1b](https://linux-hardware.org/?probe=f94b4ddd1b) | Jun 27, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [5e1d8d04f2](https://linux-hardware.org/?probe=5e1d8d04f2) | Jun 26, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [6e179dbfb0](https://linux-hardware.org/?probe=6e179dbfb0) | Jun 26, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [9dbf9f98a6](https://linux-hardware.org/?probe=9dbf9f98a6) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [4518a77b73](https://linux-hardware.org/?probe=4518a77b73) | Jun 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [9af91d0ced](https://linux-hardware.org/?probe=9af91d0ced) | Jun 26, 2023 |
| HP            | 1493                        | Desktop     | [b22e0342bc](https://linux-hardware.org/?probe=b22e0342bc) | Jun 25, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [4493e92d84](https://linux-hardware.org/?probe=4493e92d84) | Jun 25, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [e460d017ec](https://linux-hardware.org/?probe=e460d017ec) | Jun 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14bd8b577f](https://linux-hardware.org/?probe=14bd8b577f) | Jun 25, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd418c39bf](https://linux-hardware.org/?probe=bd418c39bf) | Jun 25, 2023 |
| HP            | 8437                        | Desktop     | [477b6d5623](https://linux-hardware.org/?probe=477b6d5623) | Jun 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [df9521a37d](https://linux-hardware.org/?probe=df9521a37d) | Jun 24, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [090549881a](https://linux-hardware.org/?probe=090549881a) | Jun 24, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [85221c654f](https://linux-hardware.org/?probe=85221c654f) | Jun 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [01a9e10a34](https://linux-hardware.org/?probe=01a9e10a34) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [74b9f1b367](https://linux-hardware.org/?probe=74b9f1b367) | Jun 24, 2023 |
| MSI           | Z170A GAMING M3             | Desktop     | [96c2d6503c](https://linux-hardware.org/?probe=96c2d6503c) | Jun 24, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e23ab4ba9](https://linux-hardware.org/?probe=0e23ab4ba9) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [3e08f1644a](https://linux-hardware.org/?probe=3e08f1644a) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [574653afac](https://linux-hardware.org/?probe=574653afac) | Jun 24, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [fa6b09cc1d](https://linux-hardware.org/?probe=fa6b09cc1d) | Jun 23, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a3a840a283](https://linux-hardware.org/?probe=a3a840a283) | Jun 23, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [7ba7b1dc58](https://linux-hardware.org/?probe=7ba7b1dc58) | Jun 22, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [e72c8358c4](https://linux-hardware.org/?probe=e72c8358c4) | Jun 22, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [08974b3246](https://linux-hardware.org/?probe=08974b3246) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [38c278b214](https://linux-hardware.org/?probe=38c278b214) | Jun 22, 2023 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [816c32de98](https://linux-hardware.org/?probe=816c32de98) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [f1e506486c](https://linux-hardware.org/?probe=f1e506486c) | Jun 21, 2023 |
| ASRock        | B760M PG Riptide            | Desktop     | [a6a3ed2eae](https://linux-hardware.org/?probe=a6a3ed2eae) | Jun 21, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [edf3326608](https://linux-hardware.org/?probe=edf3326608) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Intel         | NUC7i3BNB J22859-308        | Mini pc     | [3b9990b59d](https://linux-hardware.org/?probe=3b9990b59d) | Jun 21, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [ba4e83abed](https://linux-hardware.org/?probe=ba4e83abed) | Jun 20, 2023 |
| ASRock        | Z590M-ITX/ax                | Desktop     | [5160dd29d0](https://linux-hardware.org/?probe=5160dd29d0) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5a51d4431b](https://linux-hardware.org/?probe=5a51d4431b) | Jun 20, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [8e74890c4f](https://linux-hardware.org/?probe=8e74890c4f) | Jun 19, 2023 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | Notebook    | [98f052ad58](https://linux-hardware.org/?probe=98f052ad58) | Jun 19, 2023 |
| Framework     | Laptop                      | Notebook    | [7d010a367e](https://linux-hardware.org/?probe=7d010a367e) | Jun 19, 2023 |
| MSI           | GT70 2OC/2OD                | Notebook    | [adee2af879](https://linux-hardware.org/?probe=adee2af879) | Jun 19, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [bfe09e12f0](https://linux-hardware.org/?probe=bfe09e12f0) | Jun 18, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [be5a148c53](https://linux-hardware.org/?probe=be5a148c53) | Jun 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | Notebook    | [591e97398c](https://linux-hardware.org/?probe=591e97398c) | Jun 18, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c454cb2cf0](https://linux-hardware.org/?probe=c454cb2cf0) | Jun 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [0875b8b413](https://linux-hardware.org/?probe=0875b8b413) | Jun 18, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [93e28671fa](https://linux-hardware.org/?probe=93e28671fa) | Jun 18, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [a281272278](https://linux-hardware.org/?probe=a281272278) | Jun 17, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [97a4ed6110](https://linux-hardware.org/?probe=97a4ed6110) | Jun 17, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [b4cd8c843f](https://linux-hardware.org/?probe=b4cd8c843f) | Jun 17, 2023 |
| Dell          | Latitude 5491               | Notebook    | [0673ab5ff5](https://linux-hardware.org/?probe=0673ab5ff5) | Jun 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bcb3a62b53](https://linux-hardware.org/?probe=bcb3a62b53) | Jun 17, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [777a9e4f49](https://linux-hardware.org/?probe=777a9e4f49) | Jun 17, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [5b54def91d](https://linux-hardware.org/?probe=5b54def91d) | Jun 16, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [8f65b1ab5b](https://linux-hardware.org/?probe=8f65b1ab5b) | Jun 16, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [38138ba23d](https://linux-hardware.org/?probe=38138ba23d) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [8124f64b22](https://linux-hardware.org/?probe=8124f64b22) | Jun 16, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c5491fb02f](https://linux-hardware.org/?probe=c5491fb02f) | Jun 16, 2023 |
| Dell          | Latitude E5400              | Notebook    | [f5d066d8fc](https://linux-hardware.org/?probe=f5d066d8fc) | Jun 16, 2023 |
| MSI           | X299 GAMING PRO CARBON A... | Desktop     | [6385c09651](https://linux-hardware.org/?probe=6385c09651) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [39b295867e](https://linux-hardware.org/?probe=39b295867e) | Jun 15, 2023 |
| Fujitsu       | D3162-C1 S26361-D3162-C1    | Desktop     | [31d4ce59c3](https://linux-hardware.org/?probe=31d4ce59c3) | Jun 15, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [da6bfc34aa](https://linux-hardware.org/?probe=da6bfc34aa) | Jun 15, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b1e56a3c92](https://linux-hardware.org/?probe=b1e56a3c92) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [3a944bbbd5](https://linux-hardware.org/?probe=3a944bbbd5) | Jun 15, 2023 |
| Unknown       | Unknown                     | Notebook    | [581aba0aa2](https://linux-hardware.org/?probe=581aba0aa2) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [8515730b56](https://linux-hardware.org/?probe=8515730b56) | Jun 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [3b552a7f4a](https://linux-hardware.org/?probe=3b552a7f4a) | Jun 15, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f6175fd764](https://linux-hardware.org/?probe=f6175fd764) | Jun 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [09b0f43143](https://linux-hardware.org/?probe=09b0f43143) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8f84dca464](https://linux-hardware.org/?probe=8f84dca464) | Jun 14, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [4402afe7ad](https://linux-hardware.org/?probe=4402afe7ad) | Jun 14, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [78c4871863](https://linux-hardware.org/?probe=78c4871863) | Jun 14, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [9ef5114c59](https://linux-hardware.org/?probe=9ef5114c59) | Jun 14, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [1c62ecb77d](https://linux-hardware.org/?probe=1c62ecb77d) | Jun 14, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [2eed8e0355](https://linux-hardware.org/?probe=2eed8e0355) | Jun 13, 2023 |
| Google        | Atlas                       | Notebook    | [ecd53b626a](https://linux-hardware.org/?probe=ecd53b626a) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | Notebook    | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| ASUSTek       | UX530UQ                     | Notebook    | [c952ec8390](https://linux-hardware.org/?probe=c952ec8390) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | Notebook    | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [e18c667ddc](https://linux-hardware.org/?probe=e18c667ddc) | Jun 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [cda9f3da9c](https://linux-hardware.org/?probe=cda9f3da9c) | Jun 13, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [311a7e116c](https://linux-hardware.org/?probe=311a7e116c) | Jun 13, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [9347870cd0](https://linux-hardware.org/?probe=9347870cd0) | Jun 13, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [a4c87fb2bc](https://linux-hardware.org/?probe=a4c87fb2bc) | Jun 12, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [ceae8212bf](https://linux-hardware.org/?probe=ceae8212bf) | Jun 12, 2023 |
| Acer          | Aspire A517-53G             | Notebook    | [2069778d1f](https://linux-hardware.org/?probe=2069778d1f) | Jun 12, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [705ad3c316](https://linux-hardware.org/?probe=705ad3c316) | Jun 12, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [3e121c01dd](https://linux-hardware.org/?probe=3e121c01dd) | Jun 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3918c9dc55](https://linux-hardware.org/?probe=3918c9dc55) | Jun 12, 2023 |
| Emdoor        | AG958                       | Notebook    | [1688cc07b6](https://linux-hardware.org/?probe=1688cc07b6) | Jun 11, 2023 |
| Dell          | Latitude 5580               | Notebook    | [1e37ff326f](https://linux-hardware.org/?probe=1e37ff326f) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | Notebook    | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | Notebook    | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [f62e645bd3](https://linux-hardware.org/?probe=f62e645bd3) | Jun 11, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [9747487f82](https://linux-hardware.org/?probe=9747487f82) | Jun 11, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [5275807836](https://linux-hardware.org/?probe=5275807836) | Jun 11, 2023 |
| HP            | ProBook 470 G0              | Notebook    | [d3fdf73c3e](https://linux-hardware.org/?probe=d3fdf73c3e) | Jun 10, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [af18d05812](https://linux-hardware.org/?probe=af18d05812) | Jun 10, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [e04ff9df40](https://linux-hardware.org/?probe=e04ff9df40) | Jun 10, 2023 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [450b8ab5a7](https://linux-hardware.org/?probe=450b8ab5a7) | Jun 10, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [ab5b79d6fd](https://linux-hardware.org/?probe=ab5b79d6fd) | Jun 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [fa84ae9906](https://linux-hardware.org/?probe=fa84ae9906) | Jun 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [4c9c3d929b](https://linux-hardware.org/?probe=4c9c3d929b) | Jun 10, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [03ef8fea42](https://linux-hardware.org/?probe=03ef8fea42) | Jun 10, 2023 |
| ASUSTek       | UX530UQ                     | Notebook    | [71d0ddd2f0](https://linux-hardware.org/?probe=71d0ddd2f0) | Jun 09, 2023 |
| HP            | 82C9                        | Desktop     | [b696990030](https://linux-hardware.org/?probe=b696990030) | Jun 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3742e80123](https://linux-hardware.org/?probe=3742e80123) | Jun 09, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [f4f543eaa6](https://linux-hardware.org/?probe=f4f543eaa6) | Jun 09, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [f7470e08b0](https://linux-hardware.org/?probe=f7470e08b0) | Jun 08, 2023 |
| HP            | 3397                        | Desktop     | [c754fea198](https://linux-hardware.org/?probe=c754fea198) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [31a7447d8b](https://linux-hardware.org/?probe=31a7447d8b) | Jun 08, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [bb571d888d](https://linux-hardware.org/?probe=bb571d888d) | Jun 08, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [267154b0d2](https://linux-hardware.org/?probe=267154b0d2) | Jun 08, 2023 |
| Dell          | XPS 17 9730                 | Notebook    | [5be9db17d1](https://linux-hardware.org/?probe=5be9db17d1) | Jun 08, 2023 |
| WOOKING       | X16                         | Notebook    | [aa543651fc](https://linux-hardware.org/?probe=aa543651fc) | Jun 08, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [302bb0628a](https://linux-hardware.org/?probe=302bb0628a) | Jun 08, 2023 |
| Multilaser    | UB820                       | All in one  | [7a1e5beb6e](https://linux-hardware.org/?probe=7a1e5beb6e) | Jun 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9f3038c25e](https://linux-hardware.org/?probe=9f3038c25e) | Jun 07, 2023 |
| HP            | 3397                        | Desktop     | [d86a6fc258](https://linux-hardware.org/?probe=d86a6fc258) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| Google        | Chell                       | Notebook    | [cace26f9f9](https://linux-hardware.org/?probe=cace26f9f9) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [cbb39d8d29](https://linux-hardware.org/?probe=cbb39d8d29) | Jun 07, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [47fd407976](https://linux-hardware.org/?probe=47fd407976) | Jun 07, 2023 |
| DIEBOLD       | B85H3-M5                    | Desktop     | [7e56b1fd68](https://linux-hardware.org/?probe=7e56b1fd68) | Jun 07, 2023 |
| Acer          | Aspire A314-36M             | Notebook    | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| Dell          | Latitude 5530               | Notebook    | [44aa9db289](https://linux-hardware.org/?probe=44aa9db289) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [77e1fa9533](https://linux-hardware.org/?probe=77e1fa9533) | Jun 06, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [c33bc572fd](https://linux-hardware.org/?probe=c33bc572fd) | Jun 06, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [bbbe24d6b6](https://linux-hardware.org/?probe=bbbe24d6b6) | Jun 06, 2023 |
| HP            | 8918                        | Desktop     | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [964cd10c8e](https://linux-hardware.org/?probe=964cd10c8e) | Jun 05, 2023 |
| Dell          | 055H3G A01                  | Desktop     | [3fc296df33](https://linux-hardware.org/?probe=3fc296df33) | Jun 05, 2023 |
| Dell          | Latitude 3340               | Notebook    | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [13f3f67373](https://linux-hardware.org/?probe=13f3f67373) | Jun 04, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [88fbd57dac](https://linux-hardware.org/?probe=88fbd57dac) | Jun 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [06752ca793](https://linux-hardware.org/?probe=06752ca793) | Jun 04, 2023 |
| MSI           | GS60 6QE                    | Notebook    | [65ea70f7fa](https://linux-hardware.org/?probe=65ea70f7fa) | Jun 03, 2023 |
| HONOR         | HGF-WX6                     | Notebook    | [13d0d7b145](https://linux-hardware.org/?probe=13d0d7b145) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [ccc6b5c4b5](https://linux-hardware.org/?probe=ccc6b5c4b5) | Jun 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [6a01df1d69](https://linux-hardware.org/?probe=6a01df1d69) | Jun 03, 2023 |
| HP            | 3397                        | Desktop     | [530b98edd5](https://linux-hardware.org/?probe=530b98edd5) | Jun 03, 2023 |
| HP            | 8918                        | Desktop     | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [31400c0b8a](https://linux-hardware.org/?probe=31400c0b8a) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [359d31bb8c](https://linux-hardware.org/?probe=359d31bb8c) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | Desktop     | [cdb426bfb4](https://linux-hardware.org/?probe=cdb426bfb4) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b34bb8b33a](https://linux-hardware.org/?probe=b34bb8b33a) | Jun 02, 2023 |
| Pegatron      | H81-M1                      | Desktop     | [35eb509619](https://linux-hardware.org/?probe=35eb509619) | Jun 02, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ccc7665f](https://linux-hardware.org/?probe=24ccc7665f) | Jun 01, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [af6c8f3355](https://linux-hardware.org/?probe=af6c8f3355) | Jun 01, 2023 |
| MSI           | U200                        | Notebook    | [a217267eb0](https://linux-hardware.org/?probe=a217267eb0) | Jun 01, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [d25f4736b7](https://linux-hardware.org/?probe=d25f4736b7) | Jun 01, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [fd232702db](https://linux-hardware.org/?probe=fd232702db) | Jun 01, 2023 |
| Lenovo        | 370B SDK0J40700 WIN 3258... | All in one  | [e98c5409ac](https://linux-hardware.org/?probe=e98c5409ac) | Jun 01, 2023 |
| MSI           | P55-GD55                    | Desktop     | [1400fdf705](https://linux-hardware.org/?probe=1400fdf705) | May 31, 2023 |
| Acer          | Aspire 3830TG               | Notebook    | [abd7d9a412](https://linux-hardware.org/?probe=abd7d9a412) | May 31, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [10f4ef3e86](https://linux-hardware.org/?probe=10f4ef3e86) | May 31, 2023 |
| Dell          | Precision 3550              | Notebook    | [bddf57400b](https://linux-hardware.org/?probe=bddf57400b) | May 31, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [f77ea94512](https://linux-hardware.org/?probe=f77ea94512) | May 31, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [a5ebbfe1ef](https://linux-hardware.org/?probe=a5ebbfe1ef) | May 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [75797b5ec9](https://linux-hardware.org/?probe=75797b5ec9) | May 31, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [3f08f70d3a](https://linux-hardware.org/?probe=3f08f70d3a) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [2139621391](https://linux-hardware.org/?probe=2139621391) | May 31, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [ebc3d97429](https://linux-hardware.org/?probe=ebc3d97429) | May 30, 2023 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [97382e45f8](https://linux-hardware.org/?probe=97382e45f8) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [ac2f40b972](https://linux-hardware.org/?probe=ac2f40b972) | May 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [f45bc9a282](https://linux-hardware.org/?probe=f45bc9a282) | May 30, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [676d83919f](https://linux-hardware.org/?probe=676d83919f) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [c507b25480](https://linux-hardware.org/?probe=c507b25480) | May 30, 2023 |
| HP            | 0B54h D                     | Desktop     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| HP            | 2B36                        | Desktop     | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [ebb5445720](https://linux-hardware.org/?probe=ebb5445720) | May 29, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [e29eb3dfcc](https://linux-hardware.org/?probe=e29eb3dfcc) | May 29, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d8aa236e2d](https://linux-hardware.org/?probe=d8aa236e2d) | May 28, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [40ba623a3e](https://linux-hardware.org/?probe=40ba623a3e) | May 28, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [c78b5e28f1](https://linux-hardware.org/?probe=c78b5e28f1) | May 28, 2023 |
| Lenovo        | ThinkPad X230 2325SV7       | Notebook    | [6affd0b8ee](https://linux-hardware.org/?probe=6affd0b8ee) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [972d01f49f](https://linux-hardware.org/?probe=972d01f49f) | May 28, 2023 |
| HP            | ProBook 6560b               | Notebook    | [9fd712c62d](https://linux-hardware.org/?probe=9fd712c62d) | May 28, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [4f1ff269d2](https://linux-hardware.org/?probe=4f1ff269d2) | May 28, 2023 |
| Unknown       | Unknown                     | Notebook    | [b294c91e3a](https://linux-hardware.org/?probe=b294c91e3a) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | Notebook    | [fb534d212e](https://linux-hardware.org/?probe=fb534d212e) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | Notebook    | [6b753016ff](https://linux-hardware.org/?probe=6b753016ff) | May 28, 2023 |
| Tactus        | GeoFlex 110                 | Convertible | [9ea6e59b81](https://linux-hardware.org/?probe=9ea6e59b81) | May 27, 2023 |
| Tactus        | GeoFlex 110                 | Convertible | [f898014dd5](https://linux-hardware.org/?probe=f898014dd5) | May 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [b7f46e7180](https://linux-hardware.org/?probe=b7f46e7180) | May 27, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [4945ea3fba](https://linux-hardware.org/?probe=4945ea3fba) | May 26, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [5098185f54](https://linux-hardware.org/?probe=5098185f54) | May 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS1AR00    | Notebook    | [a5301f505d](https://linux-hardware.org/?probe=a5301f505d) | May 25, 2023 |
| Intel         | DN2820FYK H24582-204        | Desktop     | [1987af2458](https://linux-hardware.org/?probe=1987af2458) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5c4649a83e](https://linux-hardware.org/?probe=5c4649a83e) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [a03284052b](https://linux-hardware.org/?probe=a03284052b) | May 24, 2023 |
| Unknown       | Unknown                     | Desktop     | [957b9f9de8](https://linux-hardware.org/?probe=957b9f9de8) | May 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [b5e28ef2ab](https://linux-hardware.org/?probe=b5e28ef2ab) | May 23, 2023 |
| HP            | 8876 11                     | Desktop     | [889144e990](https://linux-hardware.org/?probe=889144e990) | May 23, 2023 |
| AMI           | Intel                       | Desktop     | [9ddb291be3](https://linux-hardware.org/?probe=9ddb291be3) | May 22, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [f9103674dc](https://linux-hardware.org/?probe=f9103674dc) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [781e226978](https://linux-hardware.org/?probe=781e226978) | May 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [68caefd4e9](https://linux-hardware.org/?probe=68caefd4e9) | May 22, 2023 |
| Lenovo        | 3753 NOK                    | Desktop     | [f2971c14a7](https://linux-hardware.org/?probe=f2971c14a7) | May 21, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [60ec2d6e04](https://linux-hardware.org/?probe=60ec2d6e04) | May 21, 2023 |
| AMI           | Intel                       | Desktop     | [13f87e64f1](https://linux-hardware.org/?probe=13f87e64f1) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [2a95b22ac3](https://linux-hardware.org/?probe=2a95b22ac3) | May 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [19416d3973](https://linux-hardware.org/?probe=19416d3973) | May 21, 2023 |
| Unknown       | HX90                        | Desktop     | [d640a32296](https://linux-hardware.org/?probe=d640a32296) | May 21, 2023 |
| Getac         | V110G3                      | Notebook    | [4a80145aac](https://linux-hardware.org/?probe=4a80145aac) | May 21, 2023 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [953734fc80](https://linux-hardware.org/?probe=953734fc80) | May 20, 2023 |
| Lenovo        | 3714 NOK                    | Desktop     | [0da1ff78c6](https://linux-hardware.org/?probe=0da1ff78c6) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| MSI           | X370 GAMING M7 ACK          | Desktop     | [c59f2a4b1e](https://linux-hardware.org/?probe=c59f2a4b1e) | May 19, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| Getac         | V110G3                      | Notebook    | [1b04290d0e](https://linux-hardware.org/?probe=1b04290d0e) | May 19, 2023 |
| ASRock        | 890FX Deluxe4               | Desktop     | [c00eb20149](https://linux-hardware.org/?probe=c00eb20149) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6c83146909](https://linux-hardware.org/?probe=6c83146909) | May 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [1ed7f81c69](https://linux-hardware.org/?probe=1ed7f81c69) | May 18, 2023 |
| ASUSTek       | ROG Strix G733CX_G743CX     | Notebook    | [744f091c75](https://linux-hardware.org/?probe=744f091c75) | May 18, 2023 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [d98feea8ad](https://linux-hardware.org/?probe=d98feea8ad) | May 17, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a776d86dad](https://linux-hardware.org/?probe=a776d86dad) | May 17, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [81eee33114](https://linux-hardware.org/?probe=81eee33114) | May 17, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [77675ecccd](https://linux-hardware.org/?probe=77675ecccd) | May 17, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [a74974308d](https://linux-hardware.org/?probe=a74974308d) | May 16, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [8b1e6a5baf](https://linux-hardware.org/?probe=8b1e6a5baf) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [9dd2c4cbee](https://linux-hardware.org/?probe=9dd2c4cbee) | May 16, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [dfc49eb820](https://linux-hardware.org/?probe=dfc49eb820) | May 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [a4cbf66286](https://linux-hardware.org/?probe=a4cbf66286) | May 16, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [a1d85d1caf](https://linux-hardware.org/?probe=a1d85d1caf) | May 16, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [aeb8c0e04f](https://linux-hardware.org/?probe=aeb8c0e04f) | May 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [0770462dab](https://linux-hardware.org/?probe=0770462dab) | May 15, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [a6ffd0df31](https://linux-hardware.org/?probe=a6ffd0df31) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [9ed74f5d63](https://linux-hardware.org/?probe=9ed74f5d63) | May 15, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [b4ffbbf7d3](https://linux-hardware.org/?probe=b4ffbbf7d3) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [2df8fbd5a5](https://linux-hardware.org/?probe=2df8fbd5a5) | May 15, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [f732fbd488](https://linux-hardware.org/?probe=f732fbd488) | May 14, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [59214a0e61](https://linux-hardware.org/?probe=59214a0e61) | May 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [fb58a4d348](https://linux-hardware.org/?probe=fb58a4d348) | May 14, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [745ae69749](https://linux-hardware.org/?probe=745ae69749) | May 14, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [acc449dad2](https://linux-hardware.org/?probe=acc449dad2) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c164fc1080](https://linux-hardware.org/?probe=c164fc1080) | May 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b4c4fde79d](https://linux-hardware.org/?probe=b4c4fde79d) | May 14, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [970443eea3](https://linux-hardware.org/?probe=970443eea3) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [65374a707a](https://linux-hardware.org/?probe=65374a707a) | May 14, 2023 |
| Intel         | X79F1 V2.0                  | Desktop     | [a2446b63b3](https://linux-hardware.org/?probe=a2446b63b3) | May 14, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [f5cbf650c3](https://linux-hardware.org/?probe=f5cbf650c3) | May 14, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [58c658819c](https://linux-hardware.org/?probe=58c658819c) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [ef9c6905f1](https://linux-hardware.org/?probe=ef9c6905f1) | May 13, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [7f4f38aeb1](https://linux-hardware.org/?probe=7f4f38aeb1) | May 13, 2023 |
| Sony          | SVE1513Z1EB                 | Notebook    | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2674c1ddb6](https://linux-hardware.org/?probe=2674c1ddb6) | May 12, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [bb8fe2215b](https://linux-hardware.org/?probe=bb8fe2215b) | May 12, 2023 |
| HP            | 3047h                       | Desktop     | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [f9a67e4a1f](https://linux-hardware.org/?probe=f9a67e4a1f) | May 11, 2023 |
| MSI           | GT70 2PC                    | Notebook    | [c98c889dbf](https://linux-hardware.org/?probe=c98c889dbf) | May 11, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [e855bafa57](https://linux-hardware.org/?probe=e855bafa57) | May 11, 2023 |
| Dell          | Precision 7520              | Notebook    | [184802dbab](https://linux-hardware.org/?probe=184802dbab) | May 11, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4d4946eec9](https://linux-hardware.org/?probe=4d4946eec9) | May 11, 2023 |
| ASUSTek       | F1A75-M PRO/CSM             | Desktop     | [18a4110763](https://linux-hardware.org/?probe=18a4110763) | May 11, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [ec8e4b5f19](https://linux-hardware.org/?probe=ec8e4b5f19) | May 11, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [41eee30825](https://linux-hardware.org/?probe=41eee30825) | May 11, 2023 |
| Lenovo        | ThinkCentre M71z 1761E4U    | Desktop     | [a865f3d92e](https://linux-hardware.org/?probe=a865f3d92e) | May 11, 2023 |
| Dell          | Latitude E6440              | Notebook    | [ea902a82a4](https://linux-hardware.org/?probe=ea902a82a4) | May 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1e4f2a0daf](https://linux-hardware.org/?probe=1e4f2a0daf) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57a74239f8](https://linux-hardware.org/?probe=57a74239f8) | May 10, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [962ca6e507](https://linux-hardware.org/?probe=962ca6e507) | May 10, 2023 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [5921d78ceb](https://linux-hardware.org/?probe=5921d78ceb) | May 10, 2023 |
| Acer          | TravelMate P653-M           | Notebook    | [a0f805c8ca](https://linux-hardware.org/?probe=a0f805c8ca) | May 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [0b797e8428](https://linux-hardware.org/?probe=0b797e8428) | May 10, 2023 |
| Intel         | NUC13ANBi7 M89645-202       | Mini pc     | [6f1e53a7ec](https://linux-hardware.org/?probe=6f1e53a7ec) | May 10, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [69f4dd51d9](https://linux-hardware.org/?probe=69f4dd51d9) | May 10, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [532e5b78de](https://linux-hardware.org/?probe=532e5b78de) | May 09, 2023 |
| MSI           | B85-G43                     | Desktop     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [462a9b182b](https://linux-hardware.org/?probe=462a9b182b) | May 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [fa734dc49a](https://linux-hardware.org/?probe=fa734dc49a) | May 09, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [86136dd98f](https://linux-hardware.org/?probe=86136dd98f) | May 09, 2023 |
| ASRock        | N68-S3 UCC                  | Desktop     | [8a1fbe8e3c](https://linux-hardware.org/?probe=8a1fbe8e3c) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [503204d798](https://linux-hardware.org/?probe=503204d798) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e0fc6f7617](https://linux-hardware.org/?probe=e0fc6f7617) | May 08, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| Toshiba       | Satellite L855              | Notebook    | [5e78ff90cc](https://linux-hardware.org/?probe=5e78ff90cc) | May 08, 2023 |
| TUXEDO        | N24_25BU                    | Notebook    | [9cd4e499ae](https://linux-hardware.org/?probe=9cd4e499ae) | May 07, 2023 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [a9fe0fdf88](https://linux-hardware.org/?probe=a9fe0fdf88) | May 07, 2023 |
| Gateway       | RS780                       | Desktop     | [e04207a390](https://linux-hardware.org/?probe=e04207a390) | May 07, 2023 |
| Dell          | Inspiron 5585               | Notebook    | [f838e48bd3](https://linux-hardware.org/?probe=f838e48bd3) | May 07, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [87e972803c](https://linux-hardware.org/?probe=87e972803c) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a86bd404e0](https://linux-hardware.org/?probe=a86bd404e0) | May 07, 2023 |
| Intel         | H61                         | Desktop     | [c359f42a22](https://linux-hardware.org/?probe=c359f42a22) | May 07, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0c0ad48cc6](https://linux-hardware.org/?probe=0c0ad48cc6) | May 07, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [812ae9a763](https://linux-hardware.org/?probe=812ae9a763) | May 06, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [7ad914a8a9](https://linux-hardware.org/?probe=7ad914a8a9) | May 06, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [0a66f5d4e4](https://linux-hardware.org/?probe=0a66f5d4e4) | May 06, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [9b843f40a1](https://linux-hardware.org/?probe=9b843f40a1) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [4d21a72bfb](https://linux-hardware.org/?probe=4d21a72bfb) | May 05, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [ffab85a31a](https://linux-hardware.org/?probe=ffab85a31a) | May 05, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [dd238f7e60](https://linux-hardware.org/?probe=dd238f7e60) | May 04, 2023 |
| Gigabyte      | X99-Gaming 5                | Desktop     | [e1d1bdef81](https://linux-hardware.org/?probe=e1d1bdef81) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [6a70490cd6](https://linux-hardware.org/?probe=6a70490cd6) | May 03, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [19a489c33e](https://linux-hardware.org/?probe=19a489c33e) | May 03, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [c26b48854d](https://linux-hardware.org/?probe=c26b48854d) | May 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [5989cc1ac0](https://linux-hardware.org/?probe=5989cc1ac0) | May 03, 2023 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [9258699383](https://linux-hardware.org/?probe=9258699383) | May 03, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [1909560f36](https://linux-hardware.org/?probe=1909560f36) | May 02, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [553a101cf8](https://linux-hardware.org/?probe=553a101cf8) | May 02, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [c0f2b10022](https://linux-hardware.org/?probe=c0f2b10022) | May 02, 2023 |
| MECHREVO      | WUJIE16 Pro                 | Notebook    | [c19e8370e5](https://linux-hardware.org/?probe=c19e8370e5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [9cee4296b5](https://linux-hardware.org/?probe=9cee4296b5) | May 02, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a9406a1851](https://linux-hardware.org/?probe=a9406a1851) | May 02, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [17097573de](https://linux-hardware.org/?probe=17097573de) | May 02, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [09a404ced5](https://linux-hardware.org/?probe=09a404ced5) | May 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7ffccfda78](https://linux-hardware.org/?probe=7ffccfda78) | May 01, 2023 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [cf6a478eb1](https://linux-hardware.org/?probe=cf6a478eb1) | May 01, 2023 |
| ASRock        | B650 LiveMixer              | Desktop     | [aecb4b61b4](https://linux-hardware.org/?probe=aecb4b61b4) | May 01, 2023 |
| Shuttle       | DL20N                       | Desktop     | [3f97bcaa08](https://linux-hardware.org/?probe=3f97bcaa08) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [558cde0a43](https://linux-hardware.org/?probe=558cde0a43) | Apr 30, 2023 |
| Positivo      | POS-EIQ87CY POSITIVO        | Desktop     | [2e2b57b3ae](https://linux-hardware.org/?probe=2e2b57b3ae) | Apr 30, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [e47ae2080c](https://linux-hardware.org/?probe=e47ae2080c) | Apr 29, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3586d79ce4](https://linux-hardware.org/?probe=3586d79ce4) | Apr 29, 2023 |
| HP            | 845A                        | Desktop     | [d0aa2a4a7a](https://linux-hardware.org/?probe=d0aa2a4a7a) | Apr 29, 2023 |
| HP            | 845A                        | Desktop     | [f8bc4601ef](https://linux-hardware.org/?probe=f8bc4601ef) | Apr 29, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [f4eea7ce60](https://linux-hardware.org/?probe=f4eea7ce60) | Apr 29, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [f089770d02](https://linux-hardware.org/?probe=f089770d02) | Apr 28, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [89f52ca147](https://linux-hardware.org/?probe=89f52ca147) | Apr 28, 2023 |
| HP            | ENVY Notebook               | Notebook    | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [d4bb8a135d](https://linux-hardware.org/?probe=d4bb8a135d) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Pegatron      | Benicia                     | Desktop     | [930452646c](https://linux-hardware.org/?probe=930452646c) | Apr 28, 2023 |
| ASUSTek       | P9D-M Series                | Server      | [44b55b4721](https://linux-hardware.org/?probe=44b55b4721) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX Z370-I GAMING     | Desktop     | [e8886a7521](https://linux-hardware.org/?probe=e8886a7521) | Apr 28, 2023 |
| Multilaser    | UB820                       | All in one  | [3796d857b1](https://linux-hardware.org/?probe=3796d857b1) | Apr 28, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [3342a295e8](https://linux-hardware.org/?probe=3342a295e8) | Apr 28, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [38c117ee87](https://linux-hardware.org/?probe=38c117ee87) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fe959d51ab](https://linux-hardware.org/?probe=fe959d51ab) | Apr 27, 2023 |
| MECHREVO      | X3 Series GK7CP6R           | Notebook    | [c764a98c9d](https://linux-hardware.org/?probe=c764a98c9d) | Apr 27, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4fb9a937f3](https://linux-hardware.org/?probe=4fb9a937f3) | Apr 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f810923e5f](https://linux-hardware.org/?probe=f810923e5f) | Apr 27, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [3a1d89d5a0](https://linux-hardware.org/?probe=3a1d89d5a0) | Apr 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [d470349226](https://linux-hardware.org/?probe=d470349226) | Apr 26, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a0f1823b8e](https://linux-hardware.org/?probe=a0f1823b8e) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [6dec479f55](https://linux-hardware.org/?probe=6dec479f55) | Apr 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a2875a31b2](https://linux-hardware.org/?probe=a2875a31b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [20bf63821f](https://linux-hardware.org/?probe=20bf63821f) | Apr 25, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [5ac7debff3](https://linux-hardware.org/?probe=5ac7debff3) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [3c50d5d61c](https://linux-hardware.org/?probe=3c50d5d61c) | Apr 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [25ac3a297e](https://linux-hardware.org/?probe=25ac3a297e) | Apr 24, 2023 |
| Emdoor        | AG958                       | Notebook    | [a925cf244e](https://linux-hardware.org/?probe=a925cf244e) | Apr 24, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [0e85243397](https://linux-hardware.org/?probe=0e85243397) | Apr 23, 2023 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [f2d4f962d2](https://linux-hardware.org/?probe=f2d4f962d2) | Apr 23, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [e5c6fc2738](https://linux-hardware.org/?probe=e5c6fc2738) | Apr 23, 2023 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [f75685d3be](https://linux-hardware.org/?probe=f75685d3be) | Apr 23, 2023 |
| HUAWEI        | PUM-WDX9-PCB-B1 M1060       | Desktop     | [2c8835f2e2](https://linux-hardware.org/?probe=2c8835f2e2) | Apr 22, 2023 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [112a18b586](https://linux-hardware.org/?probe=112a18b586) | Apr 22, 2023 |
| Medion        | E4251                       | Notebook    | [76820d982c](https://linux-hardware.org/?probe=76820d982c) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Google        | Fleex                       | Notebook    | [19603bb256](https://linux-hardware.org/?probe=19603bb256) | Apr 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [519c11a569](https://linux-hardware.org/?probe=519c11a569) | Apr 21, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [6e1df0f6ee](https://linux-hardware.org/?probe=6e1df0f6ee) | Apr 21, 2023 |
| Emdoor        | AG958                       | Notebook    | [f7408488b4](https://linux-hardware.org/?probe=f7408488b4) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [cc1233b9b9](https://linux-hardware.org/?probe=cc1233b9b9) | Apr 21, 2023 |
| Lenovo        | 102F SDK0J40705 WIN 3425... | Desktop     | [15cc4335c7](https://linux-hardware.org/?probe=15cc4335c7) | Apr 21, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [3efc88e5df](https://linux-hardware.org/?probe=3efc88e5df) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [b0b94f2462](https://linux-hardware.org/?probe=b0b94f2462) | Apr 21, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [d429a2c865](https://linux-hardware.org/?probe=d429a2c865) | Apr 21, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [84a6fd49fa](https://linux-hardware.org/?probe=84a6fd49fa) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [5a9a6c553f](https://linux-hardware.org/?probe=5a9a6c553f) | Apr 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [87538ce2ba](https://linux-hardware.org/?probe=87538ce2ba) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8c9f6ec7ef](https://linux-hardware.org/?probe=8c9f6ec7ef) | Apr 20, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [648c4c3622](https://linux-hardware.org/?probe=648c4c3622) | Apr 20, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [f8519c5a20](https://linux-hardware.org/?probe=f8519c5a20) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Dell          | Precision 3550              | Notebook    | [2f1a7d66f4](https://linux-hardware.org/?probe=2f1a7d66f4) | Apr 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [cb5a9be901](https://linux-hardware.org/?probe=cb5a9be901) | Apr 19, 2023 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [701110cf4e](https://linux-hardware.org/?probe=701110cf4e) | Apr 19, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [023e96a6fd](https://linux-hardware.org/?probe=023e96a6fd) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [3d2366f479](https://linux-hardware.org/?probe=3d2366f479) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [e816e4de38](https://linux-hardware.org/?probe=e816e4de38) | Apr 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [e8e85fe2af](https://linux-hardware.org/?probe=e8e85fe2af) | Apr 18, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [49d7cdd068](https://linux-hardware.org/?probe=49d7cdd068) | Apr 18, 2023 |
| ASRock        | Z790 Taichi                 | Desktop     | [0d25cf28bc](https://linux-hardware.org/?probe=0d25cf28bc) | Apr 17, 2023 |
| MSI           | MS-B0A41                    | Desktop     | [5950f6e73c](https://linux-hardware.org/?probe=5950f6e73c) | Apr 17, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| Dell          | Precision 3571              | Notebook    | [d1fcff8b8f](https://linux-hardware.org/?probe=d1fcff8b8f) | Apr 17, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [058029e9f7](https://linux-hardware.org/?probe=058029e9f7) | Apr 17, 2023 |
| Dell          | 0P01GV A03                  | Desktop     | [ed2675881e](https://linux-hardware.org/?probe=ed2675881e) | Apr 17, 2023 |
| Dell          | Latitude 5500               | Notebook    | [f4ac637463](https://linux-hardware.org/?probe=f4ac637463) | Apr 16, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [286c8ef93c](https://linux-hardware.org/?probe=286c8ef93c) | Apr 16, 2023 |
| HP            | 158A                        | Desktop     | [56694ce9a3](https://linux-hardware.org/?probe=56694ce9a3) | Apr 16, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [0c49ead576](https://linux-hardware.org/?probe=0c49ead576) | Apr 16, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [3924bb4eb5](https://linux-hardware.org/?probe=3924bb4eb5) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2eb96e4d6e](https://linux-hardware.org/?probe=2eb96e4d6e) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7d34909c86](https://linux-hardware.org/?probe=7d34909c86) | Apr 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3e9d210a94](https://linux-hardware.org/?probe=3e9d210a94) | Apr 16, 2023 |
| Positivo      | C14CR01                     | Notebook    | [a5fc85315a](https://linux-hardware.org/?probe=a5fc85315a) | Apr 16, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [502263c435](https://linux-hardware.org/?probe=502263c435) | Apr 15, 2023 |
| HP            | 802E                        | Desktop     | [d6a1c8ad74](https://linux-hardware.org/?probe=d6a1c8ad74) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3a6ad12afa](https://linux-hardware.org/?probe=3a6ad12afa) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33c25e0c22](https://linux-hardware.org/?probe=33c25e0c22) | Apr 15, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [33936188c8](https://linux-hardware.org/?probe=33936188c8) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| ASUSTek       | GR6                         | Desktop     | [9cccf46449](https://linux-hardware.org/?probe=9cccf46449) | Apr 15, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [988cd72346](https://linux-hardware.org/?probe=988cd72346) | Apr 15, 2023 |
| AZW           | GT-R                        | Notebook    | [c37dabb7a7](https://linux-hardware.org/?probe=c37dabb7a7) | Apr 15, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [8aa8fd23c6](https://linux-hardware.org/?probe=8aa8fd23c6) | Apr 15, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [2b7836fd04](https://linux-hardware.org/?probe=2b7836fd04) | Apr 14, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Chuwi         | LapBook Pro                 | Notebook    | [3c8bbf6ec3](https://linux-hardware.org/?probe=3c8bbf6ec3) | Apr 14, 2023 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [b5ce8ee6ec](https://linux-hardware.org/?probe=b5ce8ee6ec) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bbc081e43e](https://linux-hardware.org/?probe=bbc081e43e) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a59a28162e](https://linux-hardware.org/?probe=a59a28162e) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [ea58c893c1](https://linux-hardware.org/?probe=ea58c893c1) | Apr 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [3637a41ac7](https://linux-hardware.org/?probe=3637a41ac7) | Apr 13, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [1b97e4ffc5](https://linux-hardware.org/?probe=1b97e4ffc5) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [7c28a5666c](https://linux-hardware.org/?probe=7c28a5666c) | Apr 12, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [402a94b1c0](https://linux-hardware.org/?probe=402a94b1c0) | Apr 12, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [d1ecfaf06b](https://linux-hardware.org/?probe=d1ecfaf06b) | Apr 12, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [426140ece2](https://linux-hardware.org/?probe=426140ece2) | Apr 12, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4e6c5f4b6](https://linux-hardware.org/?probe=f4e6c5f4b6) | Apr 12, 2023 |
| Dell          | Precision 5520              | Notebook    | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [6a1c34f539](https://linux-hardware.org/?probe=6a1c34f539) | Apr 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1429799ca6](https://linux-hardware.org/?probe=1429799ca6) | Apr 11, 2023 |
| HP            | 1495                        | Desktop     | [762886dcb0](https://linux-hardware.org/?probe=762886dcb0) | Apr 11, 2023 |
| Sony          | VPCSB2A7R                   | Notebook    | [1620c38937](https://linux-hardware.org/?probe=1620c38937) | Apr 11, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [8b8b7e1e4e](https://linux-hardware.org/?probe=8b8b7e1e4e) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [192ca29359](https://linux-hardware.org/?probe=192ca29359) | Apr 11, 2023 |
| Acer          | Spin SP314-54N              | Convertible | [8e2b7b11ec](https://linux-hardware.org/?probe=8e2b7b11ec) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | Notebook    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [d5e608b74e](https://linux-hardware.org/?probe=d5e608b74e) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [e9ba143773](https://linux-hardware.org/?probe=e9ba143773) | Apr 11, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [1daf1b0ff6](https://linux-hardware.org/?probe=1daf1b0ff6) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [1dad85ccf1](https://linux-hardware.org/?probe=1dad85ccf1) | Apr 10, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [1c3cfd94a3](https://linux-hardware.org/?probe=1c3cfd94a3) | Apr 09, 2023 |
| Lenovo        | SKYBAY SDK0J40679 WIN 32... | All in one  | [810692eb45](https://linux-hardware.org/?probe=810692eb45) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | Notebook    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6aae769b7a](https://linux-hardware.org/?probe=6aae769b7a) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [5a4d307476](https://linux-hardware.org/?probe=5a4d307476) | Apr 09, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e553db41a3](https://linux-hardware.org/?probe=e553db41a3) | Apr 08, 2023 |
| MACHENIKE     | T58-V                       | Notebook    | [9a70cca135](https://linux-hardware.org/?probe=9a70cca135) | Apr 08, 2023 |
| Huanan        | X99-F8                      | Desktop     | [4b020d6c5a](https://linux-hardware.org/?probe=4b020d6c5a) | Apr 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [15c7f69a52](https://linux-hardware.org/?probe=15c7f69a52) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [11cc5eca09](https://linux-hardware.org/?probe=11cc5eca09) | Apr 06, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [c2195f003d](https://linux-hardware.org/?probe=c2195f003d) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [be741560b8](https://linux-hardware.org/?probe=be741560b8) | Apr 06, 2023 |
| HP            | 21D0                        | Desktop     | [be69723341](https://linux-hardware.org/?probe=be69723341) | Apr 06, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [1190aa9be8](https://linux-hardware.org/?probe=1190aa9be8) | Apr 06, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [6611343c84](https://linux-hardware.org/?probe=6611343c84) | Apr 05, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [1dcee27dff](https://linux-hardware.org/?probe=1dcee27dff) | Apr 05, 2023 |
| HP            | 84FD                        | Desktop     | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [770d8a9253](https://linux-hardware.org/?probe=770d8a9253) | Apr 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [8c29713fe9](https://linux-hardware.org/?probe=8c29713fe9) | Apr 05, 2023 |
| LG Electro... | Kabylake Platform           | Notebook    | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | Notebook    | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [ba4ee67415](https://linux-hardware.org/?probe=ba4ee67415) | Apr 05, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [695bc9e499](https://linux-hardware.org/?probe=695bc9e499) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [73056011a2](https://linux-hardware.org/?probe=73056011a2) | Apr 04, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [882dc981fb](https://linux-hardware.org/?probe=882dc981fb) | Apr 04, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [0d1d784767](https://linux-hardware.org/?probe=0d1d784767) | Apr 04, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [5fb3f8e0ef](https://linux-hardware.org/?probe=5fb3f8e0ef) | Apr 04, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [906d900083](https://linux-hardware.org/?probe=906d900083) | Apr 04, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [74a232499a](https://linux-hardware.org/?probe=74a232499a) | Apr 04, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [303d201aa6](https://linux-hardware.org/?probe=303d201aa6) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| MSI           | H81M-E34                    | Desktop     | [5e24c6a44a](https://linux-hardware.org/?probe=5e24c6a44a) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4061ae40b8](https://linux-hardware.org/?probe=4061ae40b8) | Apr 03, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [c487bcedab](https://linux-hardware.org/?probe=c487bcedab) | Apr 03, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fc6e550ca1](https://linux-hardware.org/?probe=fc6e550ca1) | Apr 03, 2023 |
| Sony          | VPCF236FM                   | Notebook    | [d02623453c](https://linux-hardware.org/?probe=d02623453c) | Apr 03, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [161e53a104](https://linux-hardware.org/?probe=161e53a104) | Apr 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [ed69a3bba9](https://linux-hardware.org/?probe=ed69a3bba9) | Apr 02, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [9ccae5a498](https://linux-hardware.org/?probe=9ccae5a498) | Apr 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [7d6ecc10d8](https://linux-hardware.org/?probe=7d6ecc10d8) | Apr 02, 2023 |
| Gigabyte      | X670E AORUS MASTER          | Desktop     | [bb490db4a9](https://linux-hardware.org/?probe=bb490db4a9) | Apr 02, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [cff286981b](https://linux-hardware.org/?probe=cff286981b) | Apr 01, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [01517a396d](https://linux-hardware.org/?probe=01517a396d) | Apr 01, 2023 |
| HP            | 1495                        | Desktop     | [96ea87fbce](https://linux-hardware.org/?probe=96ea87fbce) | Apr 01, 2023 |
| Star Labs     | StarBook                    | Notebook    | [8712994e3c](https://linux-hardware.org/?probe=8712994e3c) | Apr 01, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [3093c50d3d](https://linux-hardware.org/?probe=3093c50d3d) | Mar 31, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e670f092d7](https://linux-hardware.org/?probe=e670f092d7) | Mar 31, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [47557561a9](https://linux-hardware.org/?probe=47557561a9) | Mar 31, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [d35ddee3e1](https://linux-hardware.org/?probe=d35ddee3e1) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| HP            | 250 G3                      | Notebook    | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | Notebook    | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [0672578da7](https://linux-hardware.org/?probe=0672578da7) | Mar 30, 2023 |
| Dell          | Precision M6400             | Notebook    | [293957e2c0](https://linux-hardware.org/?probe=293957e2c0) | Mar 30, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [c6e4da00ac](https://linux-hardware.org/?probe=c6e4da00ac) | Mar 30, 2023 |
| Framework     | Laptop                      | Notebook    | [ef17714efa](https://linux-hardware.org/?probe=ef17714efa) | Mar 30, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [13c66b0e69](https://linux-hardware.org/?probe=13c66b0e69) | Mar 30, 2023 |
| MSI           | H81M-E34                    | Desktop     | [ac06c6037f](https://linux-hardware.org/?probe=ac06c6037f) | Mar 30, 2023 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [eb153b5f5d](https://linux-hardware.org/?probe=eb153b5f5d) | Mar 29, 2023 |
| HP            | Notebook                    | Notebook    | [ea7c0e1a2c](https://linux-hardware.org/?probe=ea7c0e1a2c) | Mar 29, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [0921fd9096](https://linux-hardware.org/?probe=0921fd9096) | Mar 28, 2023 |
| ASRock        | B550 Taichi                 | Desktop     | [94d97c5e0c](https://linux-hardware.org/?probe=94d97c5e0c) | Mar 28, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [497266ad29](https://linux-hardware.org/?probe=497266ad29) | Mar 28, 2023 |
| HP            | 82BF                        | Mini pc     | [305883be65](https://linux-hardware.org/?probe=305883be65) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c393e49ce3](https://linux-hardware.org/?probe=c393e49ce3) | Mar 28, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e7608e5c20](https://linux-hardware.org/?probe=e7608e5c20) | Mar 28, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [20df1488bd](https://linux-hardware.org/?probe=20df1488bd) | Mar 28, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [d6a9697313](https://linux-hardware.org/?probe=d6a9697313) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [01a09bc2c7](https://linux-hardware.org/?probe=01a09bc2c7) | Mar 27, 2023 |
| Dell          | Precision 3571              | Notebook    | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Toshiba       | QOSMIO F750                 | Notebook    | [b52a3268f6](https://linux-hardware.org/?probe=b52a3268f6) | Mar 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [a438a0c994](https://linux-hardware.org/?probe=a438a0c994) | Mar 27, 2023 |
| Dell          | G15 5515                    | Notebook    | [9c13066534](https://linux-hardware.org/?probe=9c13066534) | Mar 27, 2023 |
| ASRock        | FM2A55M-HD+ R2.0            | Desktop     | [a45bc637c9](https://linux-hardware.org/?probe=a45bc637c9) | Mar 27, 2023 |
| MSI           | GT70 2PE                    | Notebook    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [aaae412a63](https://linux-hardware.org/?probe=aaae412a63) | Mar 26, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | Notebook    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [13e0523db8](https://linux-hardware.org/?probe=13e0523db8) | Mar 26, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [cf11e69c46](https://linux-hardware.org/?probe=cf11e69c46) | Mar 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [9e318501f5](https://linux-hardware.org/?probe=9e318501f5) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [bc2447e1e5](https://linux-hardware.org/?probe=bc2447e1e5) | Mar 25, 2023 |
| Lenovo        | 30D2 NOK                    | Desktop     | [dc62baadff](https://linux-hardware.org/?probe=dc62baadff) | Mar 25, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [f027c9ca09](https://linux-hardware.org/?probe=f027c9ca09) | Mar 25, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [e6ee9fc566](https://linux-hardware.org/?probe=e6ee9fc566) | Mar 25, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [e678dd580c](https://linux-hardware.org/?probe=e678dd580c) | Mar 25, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [36fece4941](https://linux-hardware.org/?probe=36fece4941) | Mar 24, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [38079fceb0](https://linux-hardware.org/?probe=38079fceb0) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [5377aa4b23](https://linux-hardware.org/?probe=5377aa4b23) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4731c6e59f](https://linux-hardware.org/?probe=4731c6e59f) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [127173d60b](https://linux-hardware.org/?probe=127173d60b) | Mar 23, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [f1292785cd](https://linux-hardware.org/?probe=f1292785cd) | Mar 23, 2023 |
| Multilaser    | UB820                       | All in one  | [9d056bd8e0](https://linux-hardware.org/?probe=9d056bd8e0) | Mar 23, 2023 |
| realme        | CloudProXXXX                | Notebook    | [aaafa41631](https://linux-hardware.org/?probe=aaafa41631) | Mar 23, 2023 |
| Dell          | XPS 9315                    | Notebook    | [b082aa6edf](https://linux-hardware.org/?probe=b082aa6edf) | Mar 22, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9a14590477](https://linux-hardware.org/?probe=9a14590477) | Mar 22, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [38f83864e4](https://linux-hardware.org/?probe=38f83864e4) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | Desktop     | [4b80817d4b](https://linux-hardware.org/?probe=4b80817d4b) | Mar 22, 2023 |
| OEM           | H110 Ver:2.21               | Desktop     | [9c01b0ee80](https://linux-hardware.org/?probe=9c01b0ee80) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [90ef1729ef](https://linux-hardware.org/?probe=90ef1729ef) | Mar 22, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [48f86bde7c](https://linux-hardware.org/?probe=48f86bde7c) | Mar 22, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [88d49f423d](https://linux-hardware.org/?probe=88d49f423d) | Mar 22, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [893f51c005](https://linux-hardware.org/?probe=893f51c005) | Mar 21, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [a1e76aa5c1](https://linux-hardware.org/?probe=a1e76aa5c1) | Mar 21, 2023 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [2184cf01f3](https://linux-hardware.org/?probe=2184cf01f3) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [cd12accab0](https://linux-hardware.org/?probe=cd12accab0) | Mar 21, 2023 |
| Intel         | NUC12WSBv7 M36952-400       | Mini pc     | [f7ecd6ff17](https://linux-hardware.org/?probe=f7ecd6ff17) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [20b2caf568](https://linux-hardware.org/?probe=20b2caf568) | Mar 20, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [0a71696d3b](https://linux-hardware.org/?probe=0a71696d3b) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [3f233b6f9d](https://linux-hardware.org/?probe=3f233b6f9d) | Mar 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [b6ffb56057](https://linux-hardware.org/?probe=b6ffb56057) | Mar 20, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5eee23b1db](https://linux-hardware.org/?probe=5eee23b1db) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [e1c4772d0d](https://linux-hardware.org/?probe=e1c4772d0d) | Mar 19, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [68cf28bafe](https://linux-hardware.org/?probe=68cf28bafe) | Mar 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S64C00    | Notebook    | [d91384b02c](https://linux-hardware.org/?probe=d91384b02c) | Mar 19, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [d7ed5ce80d](https://linux-hardware.org/?probe=d7ed5ce80d) | Mar 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [a6fa212cf2](https://linux-hardware.org/?probe=a6fa212cf2) | Mar 19, 2023 |
| ASRock        | B360M Pro4                  | Desktop     | [e5be65dd5e](https://linux-hardware.org/?probe=e5be65dd5e) | Mar 19, 2023 |
| HP            | 8056                        | Desktop     | [fa7f589aea](https://linux-hardware.org/?probe=fa7f589aea) | Mar 19, 2023 |
| HP            | 245 G8                      | Notebook    | [5b1606146f](https://linux-hardware.org/?probe=5b1606146f) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [add9634ad5](https://linux-hardware.org/?probe=add9634ad5) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [e2cfab15ef](https://linux-hardware.org/?probe=e2cfab15ef) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [75dd9244fb](https://linux-hardware.org/?probe=75dd9244fb) | Mar 18, 2023 |
| Sony          | SVZ1311C5E                  | Notebook    | [e433359eb9](https://linux-hardware.org/?probe=e433359eb9) | Mar 18, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6565aa43e3](https://linux-hardware.org/?probe=6565aa43e3) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [8a94a38026](https://linux-hardware.org/?probe=8a94a38026) | Mar 18, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [31851c4e15](https://linux-hardware.org/?probe=31851c4e15) | Mar 18, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [c1e90dd1a3](https://linux-hardware.org/?probe=c1e90dd1a3) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [3b10072541](https://linux-hardware.org/?probe=3b10072541) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ecc76a5003](https://linux-hardware.org/?probe=ecc76a5003) | Mar 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [4ff2145364](https://linux-hardware.org/?probe=4ff2145364) | Mar 17, 2023 |
| HP            | 2B36                        | Desktop     | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [dd58f68013](https://linux-hardware.org/?probe=dd58f68013) | Mar 17, 2023 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [fe5cfbcd29](https://linux-hardware.org/?probe=fe5cfbcd29) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [fbf7dd9d94](https://linux-hardware.org/?probe=fbf7dd9d94) | Mar 17, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [c325d4fcb0](https://linux-hardware.org/?probe=c325d4fcb0) | Mar 17, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [e41f82bcfd](https://linux-hardware.org/?probe=e41f82bcfd) | Mar 16, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [d6def0b0aa](https://linux-hardware.org/?probe=d6def0b0aa) | Mar 16, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [abe67692b9](https://linux-hardware.org/?probe=abe67692b9) | Mar 16, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [1a4e62a4a5](https://linux-hardware.org/?probe=1a4e62a4a5) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [b34a55307e](https://linux-hardware.org/?probe=b34a55307e) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2eff18f570](https://linux-hardware.org/?probe=2eff18f570) | Mar 16, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [2c0d31ff9e](https://linux-hardware.org/?probe=2c0d31ff9e) | Mar 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [a99c892744](https://linux-hardware.org/?probe=a99c892744) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [40c232c45d](https://linux-hardware.org/?probe=40c232c45d) | Mar 16, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [175eb36378](https://linux-hardware.org/?probe=175eb36378) | Mar 16, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [73a4a38e57](https://linux-hardware.org/?probe=73a4a38e57) | Mar 15, 2023 |
| Intel         | H61 V1.1                    | Desktop     | [eaa24cb538](https://linux-hardware.org/?probe=eaa24cb538) | Mar 15, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [4853be01f6](https://linux-hardware.org/?probe=4853be01f6) | Mar 14, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| Sony          | VPCEB4L1E                   | Notebook    | [d91d243c75](https://linux-hardware.org/?probe=d91d243c75) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [39ded01df5](https://linux-hardware.org/?probe=39ded01df5) | Mar 14, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [529e83761c](https://linux-hardware.org/?probe=529e83761c) | Mar 14, 2023 |
| ASRock        | Z270 Gaming K6              | Desktop     | [3afad06d79](https://linux-hardware.org/?probe=3afad06d79) | Mar 14, 2023 |
| Dell          | G5 5587                     | Notebook    | [4ff3c98faf](https://linux-hardware.org/?probe=4ff3c98faf) | Mar 14, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [5997bff822](https://linux-hardware.org/?probe=5997bff822) | Mar 14, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b4f32e23c4](https://linux-hardware.org/?probe=b4f32e23c4) | Mar 14, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [74cdc2f679](https://linux-hardware.org/?probe=74cdc2f679) | Mar 14, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [d53fa296bf](https://linux-hardware.org/?probe=d53fa296bf) | Mar 14, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [954055245e](https://linux-hardware.org/?probe=954055245e) | Mar 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3dc28679cc](https://linux-hardware.org/?probe=3dc28679cc) | Mar 14, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [e1c3ac639e](https://linux-hardware.org/?probe=e1c3ac639e) | Mar 14, 2023 |
| Positivo      | Q464B                       | Notebook    | [5bd9649f43](https://linux-hardware.org/?probe=5bd9649f43) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [9f6119111f](https://linux-hardware.org/?probe=9f6119111f) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [e1fc53bd25](https://linux-hardware.org/?probe=e1fc53bd25) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1C20... | Notebook    | [41cee24fa8](https://linux-hardware.org/?probe=41cee24fa8) | Mar 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b0834fe20e](https://linux-hardware.org/?probe=b0834fe20e) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [5329567562](https://linux-hardware.org/?probe=5329567562) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| Biostar       | A960D+V3                    | Desktop     | [e18f6a3a84](https://linux-hardware.org/?probe=e18f6a3a84) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [abb73d2e5f](https://linux-hardware.org/?probe=abb73d2e5f) | Mar 13, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [44fc80c7d5](https://linux-hardware.org/?probe=44fc80c7d5) | Mar 13, 2023 |
| Huanan        | X99-F8                      | Desktop     | [2bd21ce3b3](https://linux-hardware.org/?probe=2bd21ce3b3) | Mar 13, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [8f1fe0703b](https://linux-hardware.org/?probe=8f1fe0703b) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [999c455869](https://linux-hardware.org/?probe=999c455869) | Mar 12, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [d5a4dbf55c](https://linux-hardware.org/?probe=d5a4dbf55c) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | Desktop     | [ebb7252eb5](https://linux-hardware.org/?probe=ebb7252eb5) | Mar 12, 2023 |
| EVGA          | X570 FTW WIFI.0             | Desktop     | [74001bfcc3](https://linux-hardware.org/?probe=74001bfcc3) | Mar 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ad61830c15](https://linux-hardware.org/?probe=ad61830c15) | Mar 12, 2023 |
| GPD           | G1621-02                    | Notebook    | [21394d0975](https://linux-hardware.org/?probe=21394d0975) | Mar 12, 2023 |
| Medion        | E4251                       | Notebook    | [8b057f3a15](https://linux-hardware.org/?probe=8b057f3a15) | Mar 12, 2023 |
| Lenovo        | ThinkPad T420s 4174CN5      | Notebook    | [2fde637fe7](https://linux-hardware.org/?probe=2fde637fe7) | Mar 12, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [f4d8b766a9](https://linux-hardware.org/?probe=f4d8b766a9) | Mar 12, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [593c3e084d](https://linux-hardware.org/?probe=593c3e084d) | Mar 12, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [cc73320a47](https://linux-hardware.org/?probe=cc73320a47) | Mar 12, 2023 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [9e24f3fc16](https://linux-hardware.org/?probe=9e24f3fc16) | Mar 12, 2023 |
| HP            | 212B                        | Desktop     | [0d3860ffc6](https://linux-hardware.org/?probe=0d3860ffc6) | Mar 11, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [ac6452184d](https://linux-hardware.org/?probe=ac6452184d) | Mar 11, 2023 |
| MSI           | X99A SLI PLUS               | Desktop     | [77566542fd](https://linux-hardware.org/?probe=77566542fd) | Mar 11, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2a7d9091ff](https://linux-hardware.org/?probe=2a7d9091ff) | Mar 11, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [5dfc4ceb2a](https://linux-hardware.org/?probe=5dfc4ceb2a) | Mar 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [e5f5d4a3d5](https://linux-hardware.org/?probe=e5f5d4a3d5) | Mar 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [5d585fb91b](https://linux-hardware.org/?probe=5d585fb91b) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [e7682656f1](https://linux-hardware.org/?probe=e7682656f1) | Mar 11, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [b53c65e6c9](https://linux-hardware.org/?probe=b53c65e6c9) | Mar 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [d8941697fd](https://linux-hardware.org/?probe=d8941697fd) | Mar 09, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [29a2c22865](https://linux-hardware.org/?probe=29a2c22865) | Mar 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [dba3d6498b](https://linux-hardware.org/?probe=dba3d6498b) | Mar 09, 2023 |
| Dell          | Latitude 5590               | Notebook    | [d7d667d45f](https://linux-hardware.org/?probe=d7d667d45f) | Mar 09, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [add9ea7c34](https://linux-hardware.org/?probe=add9ea7c34) | Mar 09, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [e8e1e04dbd](https://linux-hardware.org/?probe=e8e1e04dbd) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [3f6f0bc1a2](https://linux-hardware.org/?probe=3f6f0bc1a2) | Mar 08, 2023 |
| Itautec       | Infoway w7440               | Notebook    | [04d6eb5847](https://linux-hardware.org/?probe=04d6eb5847) | Mar 08, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [f066452d7d](https://linux-hardware.org/?probe=f066452d7d) | Mar 08, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [2dd91e2cd2](https://linux-hardware.org/?probe=2dd91e2cd2) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [141222a198](https://linux-hardware.org/?probe=141222a198) | Mar 08, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [2f2541bbf1](https://linux-hardware.org/?probe=2f2541bbf1) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [4cc3cc4c17](https://linux-hardware.org/?probe=4cc3cc4c17) | Mar 08, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [4b82b56d82](https://linux-hardware.org/?probe=4b82b56d82) | Mar 08, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [3d321d8069](https://linux-hardware.org/?probe=3d321d8069) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [3d14886d4c](https://linux-hardware.org/?probe=3d14886d4c) | Mar 07, 2023 |
| Infinix       | INBOOK X2 GEN11             | Notebook    | [124b1af920](https://linux-hardware.org/?probe=124b1af920) | Mar 07, 2023 |
| Dell          | Latitude 5330               | Notebook    | [c99cbe9970](https://linux-hardware.org/?probe=c99cbe9970) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [be51d02a20](https://linux-hardware.org/?probe=be51d02a20) | Mar 06, 2023 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [d62df340f9](https://linux-hardware.org/?probe=d62df340f9) | Mar 06, 2023 |
| ASRock        | AB350 Gaming K4             | Desktop     | [896ea5798f](https://linux-hardware.org/?probe=896ea5798f) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | Notebook    | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [8b7f7b9440](https://linux-hardware.org/?probe=8b7f7b9440) | Mar 05, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [24b5bddf1d](https://linux-hardware.org/?probe=24b5bddf1d) | Mar 05, 2023 |
| HP            | 8597                        | Desktop     | [17c1e6efd7](https://linux-hardware.org/?probe=17c1e6efd7) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| Google        | Delbin                      | Notebook    | [3817b0d62d](https://linux-hardware.org/?probe=3817b0d62d) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [859a660d90](https://linux-hardware.org/?probe=859a660d90) | Mar 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [cb13decef3](https://linux-hardware.org/?probe=cb13decef3) | Mar 05, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ab48c17484](https://linux-hardware.org/?probe=ab48c17484) | Mar 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ce8df757cc](https://linux-hardware.org/?probe=ce8df757cc) | Mar 04, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [50a27abb52](https://linux-hardware.org/?probe=50a27abb52) | Mar 04, 2023 |
| LG Electro... | 22V240 FAB3                 | All in one  | [163c52fd3c](https://linux-hardware.org/?probe=163c52fd3c) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [645b47cfa2](https://linux-hardware.org/?probe=645b47cfa2) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [c3043c0cba](https://linux-hardware.org/?probe=c3043c0cba) | Mar 03, 2023 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4a80c78c43](https://linux-hardware.org/?probe=4a80c78c43) | Mar 03, 2023 |
| Biostar       | B450MX-S                    | Desktop     | [7dfed91b1f](https://linux-hardware.org/?probe=7dfed91b1f) | Mar 03, 2023 |
| HP            | 212B                        | Desktop     | [45dec8a39c](https://linux-hardware.org/?probe=45dec8a39c) | Mar 03, 2023 |
| Dell          | Latitude 5421               | Notebook    | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [150a75757b](https://linux-hardware.org/?probe=150a75757b) | Mar 02, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [8bc604606b](https://linux-hardware.org/?probe=8bc604606b) | Mar 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d209549d77](https://linux-hardware.org/?probe=d209549d77) | Mar 02, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [4e540e33b1](https://linux-hardware.org/?probe=4e540e33b1) | Mar 01, 2023 |
| Positivo      | C14CR21                     | Notebook    | [d0041f93e1](https://linux-hardware.org/?probe=d0041f93e1) | Mar 01, 2023 |
| HP            | EliteBook 755 G5            | Notebook    | [4ce3aba673](https://linux-hardware.org/?probe=4ce3aba673) | Feb 28, 2023 |
| Dell          | Latitude E7450              | Notebook    | [0e5fe9d2a7](https://linux-hardware.org/?probe=0e5fe9d2a7) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | Notebook    | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [3ab9ad10d8](https://linux-hardware.org/?probe=3ab9ad10d8) | Feb 28, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [e888e1330d](https://linux-hardware.org/?probe=e888e1330d) | Feb 27, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [18fdb45ec1](https://linux-hardware.org/?probe=18fdb45ec1) | Feb 27, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [66b1256bd3](https://linux-hardware.org/?probe=66b1256bd3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [4630f9a67c](https://linux-hardware.org/?probe=4630f9a67c) | Feb 27, 2023 |
| AZW           | GTR V01                     | Mini pc     | [c788211e6d](https://linux-hardware.org/?probe=c788211e6d) | Feb 27, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [4f55a08266](https://linux-hardware.org/?probe=4f55a08266) | Feb 27, 2023 |
| Kllisre       | X79 V2.72S                  | Desktop     | [eb7e4b521c](https://linux-hardware.org/?probe=eb7e4b521c) | Feb 26, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [169d8ef4a8](https://linux-hardware.org/?probe=169d8ef4a8) | Feb 26, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [1213e49ca8](https://linux-hardware.org/?probe=1213e49ca8) | Feb 26, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | Notebook    | [da19f23a14](https://linux-hardware.org/?probe=da19f23a14) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [97b08529eb](https://linux-hardware.org/?probe=97b08529eb) | Feb 26, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [d3d04b2a1e](https://linux-hardware.org/?probe=d3d04b2a1e) | Feb 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| System76      | Serval WS                   | Notebook    | [1b136ec80d](https://linux-hardware.org/?probe=1b136ec80d) | Feb 25, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [f80e5503fc](https://linux-hardware.org/?probe=f80e5503fc) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| HP            | G60                         | Notebook    | [6e4b159708](https://linux-hardware.org/?probe=6e4b159708) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [e63cbac447](https://linux-hardware.org/?probe=e63cbac447) | Feb 25, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [4af0524a44](https://linux-hardware.org/?probe=4af0524a44) | Feb 25, 2023 |
| AZW           | SER                         | Mini pc     | [bca19a22d8](https://linux-hardware.org/?probe=bca19a22d8) | Feb 25, 2023 |
| ASUSTek       | TP500LB                     | Notebook    | [63f7dd2e91](https://linux-hardware.org/?probe=63f7dd2e91) | Feb 24, 2023 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [2ea850fc7e](https://linux-hardware.org/?probe=2ea850fc7e) | Feb 24, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [e27e1cd0e8](https://linux-hardware.org/?probe=e27e1cd0e8) | Feb 24, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [408bb96959](https://linux-hardware.org/?probe=408bb96959) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [fea6031cfe](https://linux-hardware.org/?probe=fea6031cfe) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4cf00365ff](https://linux-hardware.org/?probe=4cf00365ff) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [93dfbdd8cd](https://linux-hardware.org/?probe=93dfbdd8cd) | Feb 24, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [aef7584b8c](https://linux-hardware.org/?probe=aef7584b8c) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [79aa51c612](https://linux-hardware.org/?probe=79aa51c612) | Feb 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [a0bf98bcab](https://linux-hardware.org/?probe=a0bf98bcab) | Feb 23, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [300d88af87](https://linux-hardware.org/?probe=300d88af87) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [f3bb3aa940](https://linux-hardware.org/?probe=f3bb3aa940) | Feb 23, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [7d1b0e3db5](https://linux-hardware.org/?probe=7d1b0e3db5) | Feb 23, 2023 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [b2ae4d0b42](https://linux-hardware.org/?probe=b2ae4d0b42) | Feb 23, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ead0af8ae4](https://linux-hardware.org/?probe=ead0af8ae4) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [235831e22a](https://linux-hardware.org/?probe=235831e22a) | Feb 23, 2023 |
| Dell          | Latitude E5470              | Notebook    | [12a8a55fca](https://linux-hardware.org/?probe=12a8a55fca) | Feb 23, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [af2a414265](https://linux-hardware.org/?probe=af2a414265) | Feb 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [55c6dbae70](https://linux-hardware.org/?probe=55c6dbae70) | Feb 23, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f0cb288b9f](https://linux-hardware.org/?probe=f0cb288b9f) | Feb 23, 2023 |
| Dell          | Latitude 7410               | Notebook    | [dfa449b870](https://linux-hardware.org/?probe=dfa449b870) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [a39eba7e6a](https://linux-hardware.org/?probe=a39eba7e6a) | Feb 22, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [87a9510543](https://linux-hardware.org/?probe=87a9510543) | Feb 22, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [63636ce164](https://linux-hardware.org/?probe=63636ce164) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f98cec9924](https://linux-hardware.org/?probe=f98cec9924) | Feb 22, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [8be573974d](https://linux-hardware.org/?probe=8be573974d) | Feb 22, 2023 |
| Lenovo        | ThinkPad T460 20FMS06V00    | Notebook    | [d2aa21118e](https://linux-hardware.org/?probe=d2aa21118e) | Feb 21, 2023 |
| Gigabyte      | AORUS 17 XE4                | Notebook    | [b674e3e1e0](https://linux-hardware.org/?probe=b674e3e1e0) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64b7226700](https://linux-hardware.org/?probe=64b7226700) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [cb6168e276](https://linux-hardware.org/?probe=cb6168e276) | Feb 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [97b147476a](https://linux-hardware.org/?probe=97b147476a) | Feb 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [42750c43b5](https://linux-hardware.org/?probe=42750c43b5) | Feb 20, 2023 |
| ASUSTek       | X99-M WS                    | Desktop     | [69eb540783](https://linux-hardware.org/?probe=69eb540783) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [d8afec7717](https://linux-hardware.org/?probe=d8afec7717) | Feb 20, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [a3f369f79b](https://linux-hardware.org/?probe=a3f369f79b) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| ASRock        | X570 Taichi Razer Editio... | Desktop     | [3f44c52c3e](https://linux-hardware.org/?probe=3f44c52c3e) | Feb 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [35d0544ea5](https://linux-hardware.org/?probe=35d0544ea5) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [cc447f6c07](https://linux-hardware.org/?probe=cc447f6c07) | Feb 19, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [470ceee356](https://linux-hardware.org/?probe=470ceee356) | Feb 19, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [703cc27199](https://linux-hardware.org/?probe=703cc27199) | Feb 19, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [f8e02626c5](https://linux-hardware.org/?probe=f8e02626c5) | Feb 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [2c41f563a1](https://linux-hardware.org/?probe=2c41f563a1) | Feb 19, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | Notebook    | [28e6263489](https://linux-hardware.org/?probe=28e6263489) | Feb 19, 2023 |
| MSI           | B85M-P33 V2                 | Desktop     | [b78aee1c5a](https://linux-hardware.org/?probe=b78aee1c5a) | Feb 19, 2023 |
| HP            | Notebook                    | Notebook    | [2c17c1256f](https://linux-hardware.org/?probe=2c17c1256f) | Feb 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [f73ae7038f](https://linux-hardware.org/?probe=f73ae7038f) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [45631ae666](https://linux-hardware.org/?probe=45631ae666) | Feb 18, 2023 |
| Dell          | 0X9M3X A04                  | Desktop     | [9b13a670c5](https://linux-hardware.org/?probe=9b13a670c5) | Feb 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ab3e07326a](https://linux-hardware.org/?probe=ab3e07326a) | Feb 18, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [3599b137c4](https://linux-hardware.org/?probe=3599b137c4) | Feb 18, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [d6b212b427](https://linux-hardware.org/?probe=d6b212b427) | Feb 18, 2023 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [df01e5357c](https://linux-hardware.org/?probe=df01e5357c) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [13485dcee3](https://linux-hardware.org/?probe=13485dcee3) | Feb 18, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [06d9c4427a](https://linux-hardware.org/?probe=06d9c4427a) | Feb 18, 2023 |
| Dell          | G3 3590                     | Notebook    | [a8a3df007f](https://linux-hardware.org/?probe=a8a3df007f) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| Intel         | H61                         | Desktop     | [c1a0ccd450](https://linux-hardware.org/?probe=c1a0ccd450) | Feb 17, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [9be992efd0](https://linux-hardware.org/?probe=9be992efd0) | Feb 17, 2023 |
| MSI           | 970A-G43                    | Desktop     | [e02e6e5509](https://linux-hardware.org/?probe=e02e6e5509) | Feb 17, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [43fbbe7df5](https://linux-hardware.org/?probe=43fbbe7df5) | Feb 17, 2023 |
| HP            | 8053                        | Desktop     | [adbabb5537](https://linux-hardware.org/?probe=adbabb5537) | Feb 17, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [7e8c7de460](https://linux-hardware.org/?probe=7e8c7de460) | Feb 17, 2023 |
| TUXEDO        | Stellaris Intel Gen4        | Notebook    | [5e35f0aecc](https://linux-hardware.org/?probe=5e35f0aecc) | Feb 17, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [dc2acd10eb](https://linux-hardware.org/?probe=dc2acd10eb) | Feb 17, 2023 |
| Jumper        | EZbook                      | Notebook    | [82ba62c4b0](https://linux-hardware.org/?probe=82ba62c4b0) | Feb 16, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [e01cd81ae1](https://linux-hardware.org/?probe=e01cd81ae1) | Feb 16, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d98e6087da](https://linux-hardware.org/?probe=d98e6087da) | Feb 16, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [baa2750a13](https://linux-hardware.org/?probe=baa2750a13) | Feb 16, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [c113bd50f3](https://linux-hardware.org/?probe=c113bd50f3) | Feb 16, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [aa7bf98168](https://linux-hardware.org/?probe=aa7bf98168) | Feb 16, 2023 |
| Jumper        | EZbook                      | Notebook    | [1009011b57](https://linux-hardware.org/?probe=1009011b57) | Feb 16, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e5e721aaf2](https://linux-hardware.org/?probe=e5e721aaf2) | Feb 16, 2023 |
| Google        | Robo360                     | Notebook    | [744490a82c](https://linux-hardware.org/?probe=744490a82c) | Feb 16, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [a3b4daa09d](https://linux-hardware.org/?probe=a3b4daa09d) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [3e6dcbc3f9](https://linux-hardware.org/?probe=3e6dcbc3f9) | Feb 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [e4ee3e1438](https://linux-hardware.org/?probe=e4ee3e1438) | Feb 15, 2023 |
| Google        | Robo360                     | Notebook    | [573d036948](https://linux-hardware.org/?probe=573d036948) | Feb 15, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [713f522b92](https://linux-hardware.org/?probe=713f522b92) | Feb 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [6569b3d50d](https://linux-hardware.org/?probe=6569b3d50d) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [1ebc6ae882](https://linux-hardware.org/?probe=1ebc6ae882) | Feb 14, 2023 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [beaef7f0ab](https://linux-hardware.org/?probe=beaef7f0ab) | Feb 14, 2023 |
| Dell          | XPS 9320                    | Notebook    | [10eb3017b5](https://linux-hardware.org/?probe=10eb3017b5) | Feb 13, 2023 |
| Acer          | TravelMate P215-52          | Notebook    | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Acer          | Aspire E5-771G              | Notebook    | [d1abb191dd](https://linux-hardware.org/?probe=d1abb191dd) | Feb 13, 2023 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [348fef3dbb](https://linux-hardware.org/?probe=348fef3dbb) | Feb 13, 2023 |
| Shuttle       | FX79R                       | Desktop     | [b1631ebb53](https://linux-hardware.org/?probe=b1631ebb53) | Feb 13, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [8583704242](https://linux-hardware.org/?probe=8583704242) | Feb 13, 2023 |
| Dell          | Latitude 7490               | Notebook    | [c3f07cbb13](https://linux-hardware.org/?probe=c3f07cbb13) | Feb 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [8f7f52dcaa](https://linux-hardware.org/?probe=8f7f52dcaa) | Feb 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7711c96063](https://linux-hardware.org/?probe=7711c96063) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [88b290f249](https://linux-hardware.org/?probe=88b290f249) | Feb 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [6eb24e6e38](https://linux-hardware.org/?probe=6eb24e6e38) | Feb 13, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [59c1fdfad6](https://linux-hardware.org/?probe=59c1fdfad6) | Feb 12, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [769e8c51f0](https://linux-hardware.org/?probe=769e8c51f0) | Feb 12, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | Notebook    | [fb8b46669e](https://linux-hardware.org/?probe=fb8b46669e) | Feb 12, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [785e6e2876](https://linux-hardware.org/?probe=785e6e2876) | Feb 12, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [f12982699d](https://linux-hardware.org/?probe=f12982699d) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [0a3aa89ac9](https://linux-hardware.org/?probe=0a3aa89ac9) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [69cd397ac6](https://linux-hardware.org/?probe=69cd397ac6) | Feb 12, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35781b31c5](https://linux-hardware.org/?probe=35781b31c5) | Feb 12, 2023 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [ca16764b59](https://linux-hardware.org/?probe=ca16764b59) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [2e006be72e](https://linux-hardware.org/?probe=2e006be72e) | Feb 11, 2023 |
| HP            | 3397                        | Desktop     | [b22590d882](https://linux-hardware.org/?probe=b22590d882) | Feb 11, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [cb5573dd52](https://linux-hardware.org/?probe=cb5573dd52) | Feb 11, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [cbdda8d7e0](https://linux-hardware.org/?probe=cbdda8d7e0) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [07eabc1dbf](https://linux-hardware.org/?probe=07eabc1dbf) | Feb 11, 2023 |
| Lenovo        | ThinkPad P51 20HJS02000     | Notebook    | [335f1a844e](https://linux-hardware.org/?probe=335f1a844e) | Feb 11, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [270400302e](https://linux-hardware.org/?probe=270400302e) | Feb 10, 2023 |
| Dell          | 0T568R A00                  | Desktop     | [fedf0db748](https://linux-hardware.org/?probe=fedf0db748) | Feb 10, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [e6bcd546ae](https://linux-hardware.org/?probe=e6bcd546ae) | Feb 10, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [2a39868a05](https://linux-hardware.org/?probe=2a39868a05) | Feb 10, 2023 |
| MSI           | GE60 2QE                    | Notebook    | [4d8865f2bd](https://linux-hardware.org/?probe=4d8865f2bd) | Feb 10, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [ef2d2504b8](https://linux-hardware.org/?probe=ef2d2504b8) | Feb 10, 2023 |
| Dell          | Precision 3571              | Notebook    | [85985612ac](https://linux-hardware.org/?probe=85985612ac) | Feb 10, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [a068db4d61](https://linux-hardware.org/?probe=a068db4d61) | Feb 10, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [c81083cd55](https://linux-hardware.org/?probe=c81083cd55) | Feb 10, 2023 |
| ASRock        | Z77 Extreme3                | Desktop     | [0efa8164b3](https://linux-hardware.org/?probe=0efa8164b3) | Feb 10, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [7a116a53c6](https://linux-hardware.org/?probe=7a116a53c6) | Feb 09, 2023 |
| Gigabyte      | Z87N-WIFI                   | Desktop     | [530627f086](https://linux-hardware.org/?probe=530627f086) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1f4b88ad7f](https://linux-hardware.org/?probe=1f4b88ad7f) | Feb 09, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [9decf03532](https://linux-hardware.org/?probe=9decf03532) | Feb 09, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [157c2ef73f](https://linux-hardware.org/?probe=157c2ef73f) | Feb 09, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [29e3ebe102](https://linux-hardware.org/?probe=29e3ebe102) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [f5dbc828f3](https://linux-hardware.org/?probe=f5dbc828f3) | Feb 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [95f88cc4d8](https://linux-hardware.org/?probe=95f88cc4d8) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [dd0daa720e](https://linux-hardware.org/?probe=dd0daa720e) | Feb 08, 2023 |
| ASRock        | B460M-HDV                   | Desktop     | [4684c0511e](https://linux-hardware.org/?probe=4684c0511e) | Feb 08, 2023 |
| ASUSTek       | X99-PRO/USB                 | Desktop     | [d1f6f6da3a](https://linux-hardware.org/?probe=d1f6f6da3a) | Feb 08, 2023 |
| Dell          | 0VNGWR A00                  | All in one  | [9baaf935a7](https://linux-hardware.org/?probe=9baaf935a7) | Feb 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [5c86b33fdd](https://linux-hardware.org/?probe=5c86b33fdd) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [3089398556](https://linux-hardware.org/?probe=3089398556) | Feb 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a73dfae3f](https://linux-hardware.org/?probe=9a73dfae3f) | Feb 08, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [07d8f7c1da](https://linux-hardware.org/?probe=07d8f7c1da) | Feb 08, 2023 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [7a2dd12cd8](https://linux-hardware.org/?probe=7a2dd12cd8) | Feb 08, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [dd8fbe3d62](https://linux-hardware.org/?probe=dd8fbe3d62) | Feb 08, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9d81046c8b](https://linux-hardware.org/?probe=9d81046c8b) | Feb 07, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [df487953da](https://linux-hardware.org/?probe=df487953da) | Feb 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [a8aa5d2d58](https://linux-hardware.org/?probe=a8aa5d2d58) | Feb 07, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [ad723064e1](https://linux-hardware.org/?probe=ad723064e1) | Feb 06, 2023 |
| ASUSTek       | X550VXK                     | Notebook    | [e7a0aa4ff9](https://linux-hardware.org/?probe=e7a0aa4ff9) | Feb 06, 2023 |
| Dell          | 0W2F8G A00                  | Desktop     | [b0694cfc5c](https://linux-hardware.org/?probe=b0694cfc5c) | Feb 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [66201d26d7](https://linux-hardware.org/?probe=66201d26d7) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| HP            | 3397                        | Desktop     | [a8f8381e48](https://linux-hardware.org/?probe=a8f8381e48) | Feb 05, 2023 |
| HP            | 3397                        | Desktop     | [c41ab8c19e](https://linux-hardware.org/?probe=c41ab8c19e) | Feb 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [add74ba4b4](https://linux-hardware.org/?probe=add74ba4b4) | Feb 05, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [4d3066b96e](https://linux-hardware.org/?probe=4d3066b96e) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | Notebook    | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [898b87361c](https://linux-hardware.org/?probe=898b87361c) | Feb 05, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [f3cc45d12e](https://linux-hardware.org/?probe=f3cc45d12e) | Feb 05, 2023 |
| Timi          | A34S                        | Notebook    | [97aed45fe2](https://linux-hardware.org/?probe=97aed45fe2) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [66a494b2ec](https://linux-hardware.org/?probe=66a494b2ec) | Feb 04, 2023 |
| MSI           | MEG Z390 ACE                | Desktop     | [0528b7476a](https://linux-hardware.org/?probe=0528b7476a) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [3f0bf3e580](https://linux-hardware.org/?probe=3f0bf3e580) | Feb 04, 2023 |
| Timi          | A34S                        | Notebook    | [55208c4210](https://linux-hardware.org/?probe=55208c4210) | Feb 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1998f6f225](https://linux-hardware.org/?probe=1998f6f225) | Feb 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [a9e735ed75](https://linux-hardware.org/?probe=a9e735ed75) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [139605fcc1](https://linux-hardware.org/?probe=139605fcc1) | Feb 03, 2023 |
| Intel         | H61                         | Desktop     | [4189171d59](https://linux-hardware.org/?probe=4189171d59) | Feb 03, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [62882a0c3e](https://linux-hardware.org/?probe=62882a0c3e) | Feb 03, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [19b6a074e8](https://linux-hardware.org/?probe=19b6a074e8) | Feb 03, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [81f824a063](https://linux-hardware.org/?probe=81f824a063) | Feb 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Acer          | Predator PH315-55           | Notebook    | [9f90c06d52](https://linux-hardware.org/?probe=9f90c06d52) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| GPD           | G1619-04                    | Notebook    | [958fa49a0e](https://linux-hardware.org/?probe=958fa49a0e) | Feb 02, 2023 |
| Acer          | TravelMate P633-M           | Notebook    | [b9bb5f3746](https://linux-hardware.org/?probe=b9bb5f3746) | Feb 02, 2023 |
| Dell          | Vostro 5481                 | Notebook    | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [3a2665872a](https://linux-hardware.org/?probe=3a2665872a) | Feb 02, 2023 |
| Gigabyte      | Z77M-D3H-MVP                | Desktop     | [9b2f47d039](https://linux-hardware.org/?probe=9b2f47d039) | Feb 02, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [4f59d41c11](https://linux-hardware.org/?probe=4f59d41c11) | Feb 02, 2023 |
| Dell          | Latitude 7430               | Notebook    | [44d6dd63ce](https://linux-hardware.org/?probe=44d6dd63ce) | Feb 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAP7 8... | Notebook    | [b829e9afbd](https://linux-hardware.org/?probe=b829e9afbd) | Feb 01, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [4f06c55846](https://linux-hardware.org/?probe=4f06c55846) | Feb 01, 2023 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [115de2faed](https://linux-hardware.org/?probe=115de2faed) | Feb 01, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| Unknown       | ARM5                        | Mini pc     | [aad3a07e37](https://linux-hardware.org/?probe=aad3a07e37) | Jan 31, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [41ad246a0b](https://linux-hardware.org/?probe=41ad246a0b) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [02c8ae01d1](https://linux-hardware.org/?probe=02c8ae01d1) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [93f5ac8f6d](https://linux-hardware.org/?probe=93f5ac8f6d) | Jan 30, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [bacea93055](https://linux-hardware.org/?probe=bacea93055) | Jan 30, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [88de348bef](https://linux-hardware.org/?probe=88de348bef) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [070a09add8](https://linux-hardware.org/?probe=070a09add8) | Jan 30, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [8cca3cb036](https://linux-hardware.org/?probe=8cca3cb036) | Jan 30, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5d6a22838](https://linux-hardware.org/?probe=a5d6a22838) | Jan 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [3c0723977c](https://linux-hardware.org/?probe=3c0723977c) | Jan 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [02580dd501](https://linux-hardware.org/?probe=02580dd501) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8a324e4189](https://linux-hardware.org/?probe=8a324e4189) | Jan 30, 2023 |
| HP            | OMEN by Laptop 15z-en100    | Notebook    | [0c91238954](https://linux-hardware.org/?probe=0c91238954) | Jan 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [830de1d797](https://linux-hardware.org/?probe=830de1d797) | Jan 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [42a753536d](https://linux-hardware.org/?probe=42a753536d) | Jan 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [2fee4a59ba](https://linux-hardware.org/?probe=2fee4a59ba) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [8b5c80cad4](https://linux-hardware.org/?probe=8b5c80cad4) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [2658d00cd2](https://linux-hardware.org/?probe=2658d00cd2) | Jan 28, 2023 |
| MSI           | Modern 14 A10RB             | Notebook    | [619a49b55d](https://linux-hardware.org/?probe=619a49b55d) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [31bda5eb31](https://linux-hardware.org/?probe=31bda5eb31) | Jan 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1aa83fb987](https://linux-hardware.org/?probe=1aa83fb987) | Jan 28, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [d4c609c373](https://linux-hardware.org/?probe=d4c609c373) | Jan 27, 2023 |
| Lenovo        | ThinkPad E485 20KUCTO1WW    | Notebook    | [49e82c2714](https://linux-hardware.org/?probe=49e82c2714) | Jan 27, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Manjaro/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Manjaro        | 2839      | 38.91%  |
| Manjaro 22.0.0 | 323       | 4.43%   |
| Manjaro 20.1   | 291       | 3.99%   |
| Manjaro 20.2.1 | 283       | 3.88%   |
| Manjaro 20.2   | 243       | 3.33%   |
| Manjaro 20.0.3 | 223       | 3.06%   |
| Manjaro 21.2.6 | 176       | 2.41%   |
| Manjaro 21.1.0 | 149       | 2.04%   |
| Manjaro 18.1.5 | 143       | 1.96%   |
| Manjaro 21.2.0 | 127       | 1.74%   |
| Manjaro 21.2.5 | 126       | 1.73%   |
| Manjaro 21.1.6 | 114       | 1.56%   |
| Manjaro 21.0.7 | 113       | 1.55%   |
| Manjaro 20.0   | 101       | 1.38%   |
| Manjaro 19.0.2 | 97        | 1.33%   |
| Manjaro 18.0.4 | 96        | 1.32%   |
| Manjaro 21.0   | 87        | 1.19%   |
| Manjaro 21.0.5 | 80        | 1.1%    |
| Manjaro 20.1.2 | 80        | 1.1%    |
| Manjaro 21.2.3 | 74        | 1.01%   |
| Manjaro 21.2.1 | 73        | 1%      |
| Manjaro 22.1.0 | 72        | 0.99%   |
| Manjaro 20.1.1 | 71        | 0.97%   |
| Manjaro 20.0.1 | 69        | 0.95%   |
| Manjaro 23.0.0 | 56        | 0.77%   |
| Manjaro 22.0.4 | 56        | 0.77%   |
| Manjaro 21.3.7 | 56        | 0.77%   |
| Manjaro 21.3.6 | 50        | 0.69%   |
| Manjaro 21.0.4 | 50        | 0.69%   |
| Manjaro 21.2.2 | 46        | 0.63%   |
| Manjaro 21.2.4 | 45        | 0.62%   |
| Manjaro 21.1.2 | 41        | 0.56%   |
| Manjaro 21.1.4 | 37        | 0.51%   |
| Manjaro 21.0.1 | 36        | 0.49%   |
| Manjaro 22.0.5 | 35        | 0.48%   |
| Manjaro 21.0.2 | 34        | 0.47%   |
| Manjaro 21.3.1 | 32        | 0.44%   |
| Manjaro 21.3.0 | 31        | 0.42%   |
| Manjaro 21.0.3 | 31        | 0.42%   |
| Manjaro 22.1.1 | 30        | 0.41%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Manjaro | 6689      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.9.16-1-MANJARO  | 294       | 3.69%   |
| 5.13.19-2-MANJARO | 180       | 2.26%   |
| 5.8.6-1-MANJARO   | 140       | 1.76%   |
| 5.9.11-3-MANJARO  | 129       | 1.62%   |
| 5.8.11-1-MANJARO  | 122       | 1.53%   |
| 5.15.28-1-MANJARO | 118       | 1.48%   |
| 5.10.42-1-MANJARO | 102       | 1.28%   |
| 6.1.1-1-MANJARO   | 101       | 1.27%   |
| 5.8.18-1-MANJARO  | 101       | 1.27%   |
| 5.15.32-1-MANJARO | 100       | 1.26%   |
| 6.1.12-1-MANJARO  | 86        | 1.08%   |
| 5.15.12-1-MANJARO | 82        | 1.03%   |
| 5.6.16-1-MANJARO  | 74        | 0.93%   |
| 5.15.60-1-MANJARO | 74        | 0.93%   |
| 5.8.16-2-MANJARO  | 73        | 0.92%   |
| 5.10.2-2-MANJARO  | 65        | 0.82%   |
| 5.15.65-1-MANJARO | 62        | 0.78%   |
| 5.7.9-1-MANJARO   | 61        | 0.77%   |
| 5.10.36-2-MANJARO | 61        | 0.77%   |
| 5.6.19-2-MANJARO  | 60        | 0.75%   |
| 5.10.7-3-MANJARO  | 60        | 0.75%   |
| 6.1.31-2-MANJARO  | 58        | 0.73%   |
| 5.7.0-3-MANJARO   | 58        | 0.73%   |
| 5.8.3-2-MANJARO   | 57        | 0.72%   |
| 5.6.15-1-MANJARO  | 57        | 0.72%   |
| 5.12.9-1-MANJARO  | 54        | 0.68%   |
| 5.7.17-2-MANJARO  | 52        | 0.65%   |
| 5.15.78-1-MANJARO | 51        | 0.64%   |
| 5.15.41-1-MANJARO | 51        | 0.64%   |
| 5.14.10-1-MANJARO | 51        | 0.64%   |
| 5.9.1-1-MANJARO   | 50        | 0.63%   |
| 5.17.1-3-MANJARO  | 49        | 0.62%   |
| 5.16.14-1-MANJARO | 49        | 0.62%   |
| 5.10.23-1-MANJARO | 49        | 0.62%   |
| 5.15.74-3-MANJARO | 48        | 0.6%    |
| 5.15.7-1-MANJARO  | 48        | 0.6%    |
| 5.11.6-1-MANJARO  | 47        | 0.59%   |
| 5.15.85-1-MANJARO | 45        | 0.57%   |
| 5.15.25-1-MANJARO | 45        | 0.57%   |
| 5.10.34-1-MANJARO | 45        | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.9.16  | 294       | 3.69%   |
| 5.13.19 | 181       | 2.27%   |
| 5.8.6   | 140       | 1.76%   |
| 5.9.11  | 136       | 1.71%   |
| 5.8.11  | 123       | 1.55%   |
| 5.15.28 | 118       | 1.48%   |
| 5.10.42 | 102       | 1.28%   |
| 6.1.1   | 101       | 1.27%   |
| 5.8.18  | 101       | 1.27%   |
| 5.15.32 | 101       | 1.27%   |
| 6.1.12  | 86        | 1.08%   |
| 5.15.12 | 82        | 1.03%   |
| 5.8.16  | 74        | 0.93%   |
| 5.6.16  | 74        | 0.93%   |
| 5.15.60 | 74        | 0.93%   |
| 5.7.0   | 73        | 0.92%   |
| 5.9.1   | 69        | 0.87%   |
| 5.6.19  | 66        | 0.83%   |
| 5.10.2  | 65        | 0.82%   |
| 6.1.31  | 64        | 0.8%    |
| 5.15.65 | 62        | 0.78%   |
| 5.10.7  | 62        | 0.78%   |
| 5.7.9   | 61        | 0.77%   |
| 5.17.1  | 61        | 0.77%   |
| 5.10.36 | 61        | 0.77%   |
| 5.8.3   | 58        | 0.73%   |
| 5.6.15  | 57        | 0.72%   |
| 5.12.9  | 54        | 0.68%   |
| 5.7.17  | 53        | 0.67%   |
| 5.15.78 | 51        | 0.64%   |
| 5.15.41 | 51        | 0.64%   |
| 5.14.10 | 51        | 0.64%   |
| 5.15.7  | 50        | 0.63%   |
| 5.16.14 | 49        | 0.62%   |
| 5.15.74 | 49        | 0.62%   |
| 5.10.23 | 49        | 0.62%   |
| 5.11.6  | 48        | 0.6%    |
| 5.6.12  | 46        | 0.58%   |
| 5.15.2  | 46        | 0.58%   |
| 5.15.85 | 45        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 1250      | 16.71%  |
| 5.10    | 920       | 12.3%   |
| 5.4     | 630       | 8.42%   |
| 5.9     | 590       | 7.89%   |
| 5.8     | 553       | 7.39%   |
| 6.1     | 534       | 7.14%   |
| 5.6     | 393       | 5.25%   |
| 5.13    | 358       | 4.79%   |
| 5.7     | 264       | 3.53%   |
| 4.19    | 198       | 2.65%   |
| 5.11    | 185       | 2.47%   |
| 5.16    | 175       | 2.34%   |
| 5.12    | 157       | 2.1%    |
| 5.14    | 153       | 2.05%   |
| 6.0     | 151       | 2.02%   |
| 5.17    | 142       | 1.9%    |
| 5.19    | 138       | 1.85%   |
| 5.18    | 130       | 1.74%   |
| 5.5     | 109       | 1.46%   |
| 5.3     | 92        | 1.23%   |
| 6.2     | 83        | 1.11%   |
| 6.3     | 74        | 0.99%   |
| 4.14    | 60        | 0.8%    |
| 5.2     | 41        | 0.55%   |
| 5.0     | 30        | 0.4%    |
| 5.1     | 26        | 0.35%   |
| 4.20    | 14        | 0.19%   |
| 4.18    | 12        | 0.16%   |
| 4.9     | 4         | 0.05%   |
| 4.16    | 4         | 0.05%   |
| 4.17    | 3         | 0.04%   |
| 6.4     | 2         | 0.03%   |
| 4.7     | 2         | 0.03%   |
| 4.4     | 2         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 6686      | 99.96%  |
| i686    | 2         | 0.03%   |
| aarch64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| KDE5                     | 2531      | 36.54%  |
| XFCE                     | 1474      | 21.28%  |
| GNOME                    | 1449      | 20.92%  |
| KDE                      | 560       | 8.09%   |
| Unknown                  | 316       | 4.56%   |
| X-Cinnamon               | 177       | 2.56%   |
| i3                       | 131       | 1.89%   |
| MATE                     | 64        | 0.92%   |
| Cinnamon                 | 56        | 0.81%   |
| Deepin                   | 50        | 0.72%   |
| Budgie                   | 31        | 0.45%   |
| awesome                  | 18        | 0.26%   |
| LXQt                     | 16        | 0.23%   |
| Sway                     | 12        | 0.17%   |
| LXDE                     | 7         | 0.1%    |
| bspwm                    | 5         | 0.07%   |
| i3-with-shmlog           | 4         | 0.06%   |
| GNOME Classic            | 3         | 0.04%   |
| DWM                      | 3         | 0.04%   |
| Yaru:ubuntu:GNOME        | 2         | 0.03%   |
| qtile                    | 2         | 0.03%   |
| leftwm                   | 2         | 0.03%   |
| ICEWM                    | 2         | 0.03%   |
| GNOME Flashback          | 2         | 0.03%   |
| Enlightenment            | 2         | 0.03%   |
| xinitrc                  | 1         | 0.01%   |
| Unity                    | 1         | 0.01%   |
| swayLANG=en_CA.UTF-8     | 1         | 0.01%   |
| openbox                  | 1         | 0.01%   |
| Hyprland                 | 1         | 0.01%   |
| herbstluftwm             | 1         | 0.01%   |
| /usr/bin/openbox-session | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5772      | 84.84%  |
| Wayland | 825       | 12.13%  |
| Unknown | 139       | 2.04%   |
| Tty     | 67        | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2819      | 41.06%  |
| SDDM    | 1746      | 25.43%  |
| LightDM | 1179      | 17.17%  |
| GDM     | 877       | 12.77%  |
| TDM     | 218       | 3.18%   |
| LXDM    | 10        | 0.15%   |
| GREETD  | 7         | 0.1%    |
| SLiM    | 3         | 0.04%   |
| XDM     | 2         | 0.03%   |
| Ly      | 2         | 0.03%   |
| LYNDE   | 1         | 0.01%   |
| CDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2809      | 41.41%  |
| de_DE   | 536       | 7.9%    |
| ru_RU   | 476       | 7.02%   |
| en_GB   | 462       | 6.81%   |
| Unknown | 417       | 6.15%   |
| pt_BR   | 280       | 4.13%   |
| fr_FR   | 182       | 2.68%   |
| en_CA   | 150       | 2.21%   |
| es_ES   | 146       | 2.15%   |
| it_IT   | 145       | 2.14%   |
| pl_PL   | 122       | 1.8%    |
| en_AU   | 88        | 1.3%    |
| en_IN   | 80        | 1.18%   |
| es_MX   | 59        | 0.87%   |
| zh_CN   | 52        | 0.77%   |
| de_AT   | 46        | 0.68%   |
| nl_NL   | 41        | 0.6%    |
| ru_UA   | 39        | 0.57%   |
| es_AR   | 33        | 0.49%   |
| en_IE   | 29        | 0.43%   |
| sv_SE   | 27        | 0.4%    |
| fi_FI   | 24        | 0.35%   |
| es_CL   | 23        | 0.34%   |
| cs_CZ   | 23        | 0.34%   |
| pt_PT   | 22        | 0.32%   |
| hu_HU   | 22        | 0.32%   |
| C       | 22        | 0.32%   |
| tr_TR   | 21        | 0.31%   |
| de_CH   | 21        | 0.31%   |
| en_ZA   | 19        | 0.28%   |
| en_NZ   | 19        | 0.28%   |
| en_DK   | 19        | 0.28%   |
| uk_UA   | 17        | 0.25%   |
| es_CO   | 17        | 0.25%   |
| fr_CA   | 16        | 0.24%   |
| en_PH   | 16        | 0.24%   |
| en_IL   | 13        | 0.19%   |
| nl_BE   | 12        | 0.18%   |
| da_DK   | 12        | 0.18%   |
| ja_JP   | 11        | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3762      | 55.24%  |
| EFI  | 3048      | 44.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5639      | 83.29%  |
| Btrfs    | 678       | 10.01%  |
| Overlay  | 139       | 2.05%   |
| Unknown  | 129       | 1.91%   |
| Xfs      | 81        | 1.2%    |
| Tmpfs    | 58        | 0.86%   |
| F2fs     | 26        | 0.38%   |
| Ext3     | 5         | 0.07%   |
| Ext2     | 5         | 0.07%   |
| Zfs      | 4         | 0.06%   |
| Reiserfs | 3         | 0.04%   |
| XXXX     | 1         | 0.01%   |
| XXXfs    | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3171      | 46.43%  |
| Unknown | 3063      | 44.85%  |
| MBR     | 595       | 8.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5943      | 87.49%  |
| Yes       | 850       | 12.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4620      | 67.9%   |
| Yes       | 2184      | 32.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 1229      | 18.37%  |
| Lenovo              | 1068      | 15.97%  |
| Hewlett-Packard     | 863       | 12.9%   |
| Dell                | 718       | 10.73%  |
| Gigabyte Technology | 536       | 8.01%   |
| MSI                 | 524       | 7.83%   |
| Acer                | 338       | 5.05%   |
| ASRock              | 284       | 4.25%   |
| Apple               | 135       | 2.02%   |
| Intel               | 94        | 1.41%   |
| Samsung Electronics | 67        | 1%      |
| Toshiba             | 65        | 0.97%   |
| HUAWEI              | 64        | 0.96%   |
| Unknown             | 46        | 0.69%   |
| Timi                | 39        | 0.58%   |
| Fujitsu             | 37        | 0.55%   |
| Sony                | 33        | 0.49%   |
| Google              | 31        | 0.46%   |
| Notebook            | 29        | 0.43%   |
| Microsoft           | 20        | 0.3%    |
| Biostar             | 20        | 0.3%    |
| TUXEDO              | 18        | 0.27%   |
| Pegatron            | 18        | 0.27%   |
| Medion              | 18        | 0.27%   |
| Alienware           | 18        | 0.27%   |
| AZW                 | 17        | 0.25%   |
| Razer               | 15        | 0.22%   |
| Positivo            | 15        | 0.22%   |
| Schenker            | 13        | 0.19%   |
| Huanan              | 13        | 0.19%   |
| LG Electronics      | 12        | 0.18%   |
| HONOR               | 11        | 0.16%   |
| Foxconn             | 11        | 0.16%   |
| Packard Bell        | 10        | 0.15%   |
| System76            | 9         | 0.13%   |
| BESSTAR Tech        | 9         | 0.13%   |
| Chuwi               | 8         | 0.12%   |
| ZOTAC               | 7         | 0.1%    |
| TrekStor            | 7         | 0.1%    |
| Panasonic           | 7         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| ASUS All Series                     | 71        | 1.06%   |
| Unknown                             | 58        | 0.87%   |
| MSI MS-7C37                         | 31        | 0.46%   |
| Gigabyte B450M DS3H                 | 28        | 0.42%   |
| MSI MS-7C02                         | 26        | 0.39%   |
| HP Notebook                         | 22        | 0.33%   |
| ASUS TUF Gaming X570-PLUS           | 22        | 0.33%   |
| ASUS PRIME A320M-K                  | 19        | 0.28%   |
| MSI MS-7C91                         | 18        | 0.27%   |
| MSI MS-7B86                         | 17        | 0.25%   |
| ASRock B450M Pro4                   | 16        | 0.24%   |
| MSI MS-7B79                         | 15        | 0.22%   |
| Lenovo IdeaPad 5 15ARE05 81YQ       | 14        | 0.21%   |
| ASUS ROG STRIX B450-F GAMING        | 14        | 0.21%   |
| Lenovo Legion 5 15ARH05 82B5        | 13        | 0.19%   |
| Gigabyte X570 AORUS ELITE           | 13        | 0.19%   |
| Dell XPS 15 9500                    | 13        | 0.19%   |
| Dell XPS 13 9310                    | 13        | 0.19%   |
| ASUS ROG STRIX B550-F GAMING        | 13        | 0.19%   |
| MSI MS-7A38                         | 12        | 0.18%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2   | 12        | 0.18%   |
| HP Pavilion Notebook                | 12        | 0.18%   |
| Dell OptiPlex 9020                  | 12        | 0.18%   |
| ASUS TUF Gaming B550M-PLUS          | 12        | 0.18%   |
| ASUS PRIME B450M-A                  | 12        | 0.18%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 11        | 0.16%   |
| Gigabyte B450 AORUS M               | 11        | 0.16%   |
| Gigabyte 970A-DS3P                  | 11        | 0.16%   |
| Dell OptiPlex 7010                  | 11        | 0.16%   |
| ASUS PRIME B350-PLUS                | 11        | 0.16%   |
| MSI MS-7B89                         | 10        | 0.15%   |
| HP Pavilion dv7                     | 10        | 0.15%   |
| HP Laptop 15-bs0xx                  | 10        | 0.15%   |
| Gigabyte X570 AORUS MASTER          | 10        | 0.15%   |
| Gigabyte X470 AORUS ULTRA GAMING    | 10        | 0.15%   |
| Dell Inspiron 3542                  | 10        | 0.15%   |
| ASUS ROG STRIX X570-E GAMING        | 10        | 0.15%   |
| MSI MS-7817                         | 9         | 0.13%   |
| MSI MS-7693                         | 9         | 0.13%   |
| HP Pavilion g6                      | 9         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 446       | 6.67%   |
| Lenovo IdeaPad     | 257       | 3.84%   |
| Acer Aspire        | 211       | 3.15%   |
| ASUS ROG           | 209       | 3.12%   |
| Dell Inspiron      | 203       | 3.03%   |
| HP Pavilion        | 169       | 2.53%   |
| ASUS PRIME         | 162       | 2.42%   |
| Dell Latitude      | 149       | 2.23%   |
| Dell XPS           | 119       | 1.78%   |
| ASUS TUF           | 113       | 1.69%   |
| HP Laptop          | 102       | 1.52%   |
| HP ProBook         | 100       | 1.49%   |
| HP EliteBook       | 100       | 1.49%   |
| Dell OptiPlex      | 85        | 1.27%   |
| ASUS VivoBook      | 83        | 1.24%   |
| Lenovo Legion      | 73        | 1.09%   |
| HP ENVY            | 72        | 1.08%   |
| ASUS All           | 71        | 1.06%   |
| Dell Precision     | 68        | 1.02%   |
| Unknown            | 58        | 0.87%   |
| Toshiba Satellite  | 56        | 0.84%   |
| Lenovo Yoga        | 52        | 0.78%   |
| HP Compaq          | 52        | 0.78%   |
| Gigabyte X570      | 47        | 0.7%    |
| Gigabyte B450M     | 45        | 0.67%   |
| Dell Vostro        | 44        | 0.66%   |
| Acer Swift         | 38        | 0.57%   |
| ASUS ZenBook       | 37        | 0.55%   |
| HP OMEN            | 35        | 0.52%   |
| Gigabyte B450      | 34        | 0.51%   |
| Acer Nitro         | 32        | 0.48%   |
| MSI MS-7C37        | 31        | 0.46%   |
| MSI MS-7C02        | 26        | 0.39%   |
| Lenovo ThinkBook   | 26        | 0.39%   |
| ASUS ASUS          | 26        | 0.39%   |
| ASRock B450M       | 26        | 0.39%   |
| Lenovo ThinkCentre | 25        | 0.37%   |
| Fujitsu LIFEBOOK   | 25        | 0.37%   |
| Lenovo IdeaPadFlex | 22        | 0.33%   |
| HP Notebook        | 22        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 898       | 13.43%  |
| 2018    | 845       | 12.63%  |
| 2020    | 840       | 12.56%  |
| 2017    | 563       | 8.42%   |
| 2021    | 501       | 7.49%   |
| 2012    | 483       | 7.22%   |
| 2013    | 393       | 5.88%   |
| 2014    | 368       | 5.5%    |
| 2011    | 346       | 5.17%   |
| 2015    | 343       | 5.13%   |
| 2016    | 337       | 5.04%   |
| 2010    | 204       | 3.05%   |
| 2022    | 188       | 2.81%   |
| 2009    | 136       | 2.03%   |
| 2008    | 123       | 1.84%   |
| 2007    | 72        | 1.08%   |
| 2006    | 20        | 0.3%    |
| 2023    | 18        | 0.27%   |
| Unknown | 6         | 0.09%   |
| 2005    | 5         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 3703      | 55.36%  |
| Desktop     | 2564      | 38.33%  |
| Convertible | 239       | 3.57%   |
| Mini pc     | 80        | 1.2%    |
| All in one  | 50        | 0.75%   |
| Tablet      | 44        | 0.66%   |
| Server      | 8         | 0.12%   |
| Phone       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6685      | 99.9%   |
| Enabled  | 7         | 0.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6640      | 99.27%  |
| Yes  | 49        | 0.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1832      | 27.01%  |
| 4.01-8.0        | 1497      | 22.07%  |
| 8.01-16.0       | 1336      | 19.7%   |
| 32.01-64.0      | 868       | 12.8%   |
| 3.01-4.0        | 764       | 11.26%  |
| 64.01-256.0     | 185       | 2.73%   |
| 24.01-32.0      | 158       | 2.33%   |
| 1.01-2.0        | 106       | 1.56%   |
| 2.01-3.0        | 34        | 0.5%    |
| More than 256.0 | 2         | 0.03%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 2.01-3.0        | 1920      | 25.71%  |
| 1.01-2.0        | 1776      | 23.78%  |
| 4.01-8.0        | 1669      | 22.35%  |
| 3.01-4.0        | 1268      | 16.98%  |
| 8.01-16.0       | 503       | 6.73%   |
| 0.51-1.0        | 216       | 2.89%   |
| 16.01-24.0      | 63        | 0.84%   |
| 24.01-32.0      | 21        | 0.28%   |
| 0.01-0.5        | 20        | 0.27%   |
| 32.01-64.0      | 11        | 0.15%   |
| More than 256.0 | 1         | 0.01%   |
| 64.01-256.0     | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3496      | 50.67%  |
| 2      | 1963      | 28.45%  |
| 3      | 692       | 10.03%  |
| 4      | 369       | 5.35%   |
| 5      | 200       | 2.9%    |
| 6      | 75        | 1.09%   |
| 7      | 38        | 0.55%   |
| 0      | 31        | 0.45%   |
| 8      | 15        | 0.22%   |
| 9      | 10        | 0.14%   |
| 11     | 4         | 0.06%   |
| 10     | 3         | 0.04%   |
| 12     | 2         | 0.03%   |
| 20     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4885      | 72.37%  |
| Yes       | 1865      | 27.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5576      | 83.22%  |
| No        | 1124      | 16.78%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5280      | 78.43%  |
| No        | 1452      | 21.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4488      | 66.35%  |
| No        | 2276      | 33.65%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1129      | 16.76%  |
| Germany      | 788       | 11.7%   |
| Russia       | 599       | 8.89%   |
| Brazil       | 397       | 5.89%   |
| France       | 250       | 3.71%   |
| UK           | 242       | 3.59%   |
| Canada       | 221       | 3.28%   |
| Italy        | 219       | 3.25%   |
| Spain        | 198       | 2.94%   |
| Poland       | 194       | 2.88%   |
| Netherlands  | 154       | 2.29%   |
| Ukraine      | 146       | 2.17%   |
| India        | 127       | 1.89%   |
| Australia    | 99        | 1.47%   |
| Austria      | 96        | 1.43%   |
| Mexico       | 94        | 1.4%    |
| Sweden       | 92        | 1.37%   |
| China        | 71        | 1.05%   |
| Switzerland  | 65        | 0.96%   |
| Turkey       | 63        | 0.94%   |
| Belgium      | 62        | 0.92%   |
| Finland      | 61        | 0.91%   |
| Romania      | 60        | 0.89%   |
| Portugal     | 53        | 0.79%   |
| Czechia      | 53        | 0.79%   |
| Hungary      | 52        | 0.77%   |
| Argentina    | 51        | 0.76%   |
| Indonesia    | 48        | 0.71%   |
| Greece       | 46        | 0.68%   |
| Bulgaria     | 46        | 0.68%   |
| Norway       | 45        | 0.67%   |
| Belarus      | 42        | 0.62%   |
| Denmark      | 39        | 0.58%   |
| Colombia     | 31        | 0.46%   |
| Chile        | 31        | 0.46%   |
| Taiwan       | 29        | 0.43%   |
| Bangladesh   | 28        | 0.42%   |
| South Africa | 27        | 0.4%    |
| Israel       | 27        | 0.4%    |
| Japan        | 25        | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 142       | 2%      |
| St Petersburg     | 78        | 1.1%    |
| Vienna            | 58        | 0.82%   |
| Berlin            | 56        | 0.79%   |
| Paris             | 48        | 0.68%   |
| Sao Paulo         | 45        | 0.63%   |
| Warsaw            | 43        | 0.6%    |
| Kyiv              | 42        | 0.59%   |
| Amsterdam         | 40        | 0.56%   |
| Toronto           | 34        | 0.48%   |
| Milan             | 33        | 0.46%   |
| Frankfurt am Main | 33        | 0.46%   |
| Madrid            | 30        | 0.42%   |
| Hamburg           | 30        | 0.42%   |
| Munich            | 29        | 0.41%   |
| Rome              | 28        | 0.39%   |
| Helsinki          | 28        | 0.39%   |
| Stockholm         | 26        | 0.37%   |
| Istanbul          | 26        | 0.37%   |
| Minsk             | 25        | 0.35%   |
| Melbourne         | 25        | 0.35%   |
| Athens            | 25        | 0.35%   |
| Barcelona         | 24        | 0.34%   |
| Sydney            | 23        | 0.32%   |
| London            | 23        | 0.32%   |
| Bucharest         | 23        | 0.32%   |
| Bengaluru         | 23        | 0.32%   |
| Novosibirsk       | 22        | 0.31%   |
| Mexico City       | 22        | 0.31%   |
| Cologne           | 22        | 0.31%   |
| Sofia             | 21        | 0.3%    |
| Rio de Janeiro    | 21        | 0.3%    |
| Krakow            | 21        | 0.3%    |
| Prague            | 20        | 0.28%   |
| Budapest          | 20        | 0.28%   |
| Yekaterinburg     | 19        | 0.27%   |
| Dhaka             | 19        | 0.27%   |
| Montreal          | 18        | 0.25%   |
| Los Angeles       | 18        | 0.25%   |
| Stuttgart         | 17        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1906      | 2938   | 17.27%  |
| WDC                         | 1556      | 2367   | 14.1%   |
| Seagate                     | 1494      | 2250   | 13.54%  |
| Toshiba                     | 704       | 866    | 6.38%   |
| SanDisk                     | 659       | 860    | 5.97%   |
| Kingston                    | 635       | 833    | 5.75%   |
| Crucial                     | 467       | 661    | 4.23%   |
| Unknown                     | 340       | 450    | 3.08%   |
| Intel                       | 312       | 413    | 2.83%   |
| SK hynix                    | 309       | 376    | 2.8%    |
| Hitachi                     | 229       | 305    | 2.08%   |
| HGST                        | 213       | 277    | 1.93%   |
| Micron Technology           | 172       | 214    | 1.56%   |
| A-DATA Technology           | 149       | 200    | 1.35%   |
| Phison                      | 130       | 179    | 1.18%   |
| China                       | 104       | 136    | 0.94%   |
| Apple                       | 80        | 99     | 0.72%   |
| KIOXIA                      | 79        | 93     | 0.72%   |
| Silicon Motion              | 77        | 104    | 0.7%    |
| Micron/Crucial Technology   | 74        | 91     | 0.67%   |
| Phison Electronics          | 60        | 65     | 0.54%   |
| Transcend                   | 58        | 64     | 0.53%   |
| PNY                         | 54        | 80     | 0.49%   |
| SPCC                        | 51        | 60     | 0.46%   |
| OCZ                         | 49        | 67     | 0.44%   |
| Intenso                     | 48        | 65     | 0.43%   |
| Patriot                     | 47        | 56     | 0.43%   |
| GOODRAM                     | 45        | 69     | 0.41%   |
| XPG                         | 43        | 54     | 0.39%   |
| JMicron Technology          | 43        | 51     | 0.39%   |
| Plextor                     | 36        | 48     | 0.33%   |
| Corsair                     | 35        | 46     | 0.32%   |
| LITEONIT                    | 33        | 42     | 0.3%    |
| LITEON                      | 32        | 35     | 0.29%   |
| Kingston Technology Company | 32        | 33     | 0.29%   |
| Realtek Semiconductor       | 30        | 38     | 0.27%   |
| Team                        | 24        | 31     | 0.22%   |
| Lexar                       | 24        | 26     | 0.22%   |
| ADATA Technology            | 24        | 30     | 0.22%   |
| Hewlett-Packard             | 21        | 29     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 131       | 1.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 116       | 0.94%   |
| Samsung SSD 860 EVO 500GB                           | 111       | 0.9%    |
| Seagate ST1000LM035-1RK172 1TB                      | 108       | 0.87%   |
| Samsung SSD 850 EVO 500GB                           | 88        | 0.71%   |
| Samsung NVMe SSD Drive 512GB                        | 86        | 0.69%   |
| Samsung NVMe SSD Drive 500GB                        | 83        | 0.67%   |
| Samsung NVMe SSD Drive 1TB                          | 82        | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB                      | 81        | 0.65%   |
| Samsung SSD 850 EVO 250GB                           | 81        | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 80        | 0.65%   |
| Crucial CT500MX500SSD1 500GB                        | 79        | 0.64%   |
| Seagate ST2000DM008-2FR102 2TB                      | 76        | 0.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 69        | 0.56%   |
| Samsung SSD 860 EVO 1TB                             | 66        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                         | 66        | 0.53%   |
| Toshiba MQ01ABD100 1TB                              | 64        | 0.52%   |
| Kingston SA400S37480G 480GB SSD                     | 64        | 0.52%   |
| HGST HTS721010A9E630 1TB                            | 64        | 0.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 62        | 0.5%    |
| Samsung NVMe SSD Drive 256GB                        | 61        | 0.49%   |
| Toshiba DT01ACA100 1TB                              | 59        | 0.48%   |
| Toshiba MQ04ABF100 1TB                              | 58        | 0.47%   |
| Samsung SSD 860 EVO 250GB                           | 58        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 57        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                       | 55        | 0.44%   |
| Seagate Expansion 1TB                               | 55        | 0.44%   |
| Crucial CT240BX500SSD1 240GB                        | 54        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB                        | 52        | 0.42%   |
| Unknown MMC Card  64GB                              | 50        | 0.4%    |
| Unknown SD/MMC/MS PRO 250GB                         | 48        | 0.39%   |
| Toshiba MQ01ABF050 500GB                            | 46        | 0.37%   |
| Seagate ST500DM002-1BD142 500GB                     | 45        | 0.36%   |
| SanDisk NVMe SSD Drive 500GB                        | 45        | 0.36%   |
| Intel NVMe SSD Drive 512GB                          | 44        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB                      | 42        | 0.34%   |
| SanDisk NVMe SSD Drive 1TB                          | 42        | 0.34%   |
| Seagate ST2000DM006-2DM164 2TB                      | 41        | 0.33%   |
| Unknown MMC Card  32GB                              | 39        | 0.31%   |
| Kingston SV300S37A120G 120GB SSD                    | 39        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1457      | 2181   | 36.73%  |
| WDC                 | 1239      | 1873   | 31.23%  |
| Toshiba             | 515       | 632    | 12.98%  |
| Hitachi             | 229       | 305    | 5.77%   |
| HGST                | 212       | 276    | 5.34%   |
| Samsung Electronics | 154       | 233    | 3.88%   |
| Unknown             | 54        | 66     | 1.36%   |
| Fujitsu             | 18        | 19     | 0.45%   |
| Apple               | 17        | 22     | 0.43%   |
| Maxtor              | 13        | 15     | 0.33%   |
| USB3.0              | 8         | 8      | 0.2%    |
| Intenso             | 8         | 12     | 0.2%    |
| ASMT                | 7         | 13     | 0.18%   |
| ASMedia             | 5         | 7      | 0.13%   |
| JMicron Technology  | 4         | 8      | 0.1%    |
| Hewlett-Packard     | 4         | 4      | 0.1%    |
| HGST HTS            | 3         | 3      | 0.08%   |
| USB                 | 2         | 2      | 0.05%   |
| SSK                 | 2         | 3      | 0.05%   |
| Maxone              | 2         | 2      | 0.05%   |
| Apricorn            | 2         | 2      | 0.05%   |
| SABRENT             | 1         | 1      | 0.03%   |
| QNAP                | 1         | 1      | 0.03%   |
| Pioneer             | 1         | 3      | 0.03%   |
| PHD 3.0             | 1         | 1      | 0.03%   |
| MaxDigital          | 1         | 1      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| Lenovo              | 1         | 1      | 0.03%   |
| KESU                | 1         | 1      | 0.03%   |
| Inateck             | 1         | 1      | 0.03%   |
| IBM/Hitachi         | 1         | 1      | 0.03%   |
| ACASIS              | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 928       | 1319   | 24.89%  |
| Kingston            | 508       | 657    | 13.63%  |
| Crucial             | 426       | 611    | 11.43%  |
| SanDisk             | 314       | 409    | 8.42%   |
| WDC                 | 230       | 306    | 6.17%   |
| A-DATA Technology   | 120       | 161    | 3.22%   |
| China               | 103       | 135    | 2.76%   |
| Intel               | 95        | 120    | 2.55%   |
| Micron Technology   | 70        | 88     | 1.88%   |
| SK hynix            | 60        | 71     | 1.61%   |
| Toshiba             | 55        | 70     | 1.48%   |
| Transcend           | 51        | 56     | 1.37%   |
| OCZ                 | 49        | 67     | 1.31%   |
| PNY                 | 48        | 74     | 1.29%   |
| Apple               | 46        | 52     | 1.23%   |
| Patriot             | 44        | 53     | 1.18%   |
| GOODRAM             | 43        | 67     | 1.15%   |
| SPCC                | 40        | 48     | 1.07%   |
| Plextor             | 33        | 45     | 0.89%   |
| LITEONIT            | 33        | 42     | 0.89%   |
| Intenso             | 32        | 43     | 0.86%   |
| LITEON              | 26        | 29     | 0.7%    |
| Corsair             | 24        | 33     | 0.64%   |
| Lexar               | 23        | 25     | 0.62%   |
| Team                | 20        | 27     | 0.54%   |
| Apacer              | 20        | 22     | 0.54%   |
| Seagate             | 17        | 24     | 0.46%   |
| KingSpec            | 17        | 20     | 0.46%   |
| Netac               | 13        | 20     | 0.35%   |
| Gigabyte Technology | 13        | 18     | 0.35%   |
| Leven               | 11        | 12     | 0.3%    |
| KingDian            | 11        | 11     | 0.3%    |
| TO Exter            | 9         | 11     | 0.24%   |
| Hewlett-Packard     | 9         | 13     | 0.24%   |
| ASMT                | 9         | 13     | 0.24%   |
| Unknown             | 8         | 11     | 0.21%   |
| Mushkin             | 7         | 8      | 0.19%   |
| NGFF                | 6         | 6      | 0.16%   |
| Hoodisk             | 6         | 6      | 0.16%   |
| External            | 6         | 8      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3224      | 5700   | 33.38%  |
| SSD     | 3152      | 5001   | 32.63%  |
| NVMe    | 2859      | 4136   | 29.6%   |
| MMC     | 261       | 335    | 2.7%    |
| Unknown | 163       | 214    | 1.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 4826      | 10276  | 57.47%  |
| NVMe | 2847      | 4090   | 33.9%   |
| SAS  | 464       | 685    | 5.53%   |
| MMC  | 261       | 335    | 3.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3490      | 5734   | 51.27%  |
| 0.51-1.0   | 2208      | 3251   | 32.44%  |
| 1.01-2.0   | 626       | 914    | 9.2%    |
| 3.01-4.0   | 180       | 288    | 2.64%   |
| 4.01-10.0  | 153       | 276    | 2.25%   |
| 2.01-3.0   | 134       | 207    | 1.97%   |
| 10.01-20.0 | 16        | 31     | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1612      | 22.96%  |
| 251-500        | 1564      | 22.28%  |
| 501-1000       | 1121      | 15.97%  |
| 1001-2000      | 797       | 11.35%  |
| More than 3000 | 478       | 6.81%   |
| Unknown        | 406       | 5.78%   |
| 51-100         | 367       | 5.23%   |
| 2001-3000      | 311       | 4.43%   |
| 1-20           | 198       | 2.82%   |
| 21-50          | 166       | 2.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1450      | 19.77%  |
| 101-250        | 1195      | 16.29%  |
| 21-50          | 1191      | 16.24%  |
| 51-100         | 991       | 13.51%  |
| 251-500        | 798       | 10.88%  |
| 501-1000       | 621       | 8.47%   |
| Unknown        | 406       | 5.53%   |
| 1001-2000      | 368       | 5.02%   |
| More than 3000 | 181       | 2.47%   |
| 2001-3000      | 130       | 1.77%   |
| 0              | 5         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 11        | 12     | 1.96%   |
| HGST HTS545050A7E680 500GB                          | 10        | 10     | 1.79%   |
| HGST HTS721010A9E630 1TB                            | 9         | 9      | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 8         | 8      | 1.43%   |
| Toshiba MQ01ABD100 1TB                              | 7         | 9      | 1.25%   |
| Seagate ST500DM002-1BD142 500GB                     | 7         | 9      | 1.25%   |
| HGST HTS545050A7E380 500GB                          | 7         | 7      | 1.25%   |
| Toshiba MQ01ABD050 500GB                            | 6         | 6      | 1.07%   |
| Seagate ST500LT012-9WS142 500GB                     | 6         | 23     | 1.07%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 6         | 6      | 1.07%   |
| WDC WD5000AAKX-001CA0 500GB                         | 5         | 7      | 0.89%   |
| WDC WD10EARS-00Y5B1 1TB                             | 5         | 5      | 0.89%   |
| Seagate ST9320325AS 320GB                           | 5         | 6      | 0.89%   |
| Samsung Electronics HD103SJ 1TB                     | 5         | 5      | 0.89%   |
| Hitachi HDS721010CLA332 1TB                         | 5         | 5      | 0.89%   |
| Crucial CT525MX300SSD1 528GB                        | 5         | 5      | 0.89%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 4         | 4      | 0.71%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 4      | 0.71%   |
| Seagate ST9500325AS 500GB                           | 4         | 5      | 0.71%   |
| Seagate ST3500413AS 500GB                           | 4         | 5      | 0.71%   |
| Seagate ST1000DX001-1CM162 1TB                      | 4         | 6      | 0.71%   |
| Samsung Electronics SSD 960 EVO 250GB               | 4         | 5      | 0.71%   |
| Samsung Electronics HD103UJ 1TB                     | 4         | 6      | 0.71%   |
| Hitachi HTS723232A7A364 320GB                       | 4         | 4      | 0.71%   |
| HGST HTS725050A7E630 500GB                          | 4         | 4      | 0.71%   |
| HGST HTS541010A9E680 1TB                            | 4         | 4      | 0.71%   |
| WDC WD15EARS-00MVWB0 1TB                            | 3         | 3      | 0.54%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 4      | 0.54%   |
| WDC WD10EZEX-00RKKA0 1TB                            | 3         | 3      | 0.54%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 3         | 3      | 0.54%   |
| WDC WD10EARX-00N0YB0 1TB                            | 3         | 4      | 0.54%   |
| Seagate ST9750420AS 752GB                           | 3         | 3      | 0.54%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 4      | 0.54%   |
| Seagate ST4000DM000-1F2168 4TB                      | 3         | 10     | 0.54%   |
| Seagate ST31000524AS 1TB                            | 3         | 5      | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB                      | 3         | 3      | 0.54%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 3         | 3      | 0.54%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 3         | 3      | 0.54%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 3      | 0.54%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 3      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 146       | 213    | 26.74%  |
| WDC                 | 126       | 147    | 23.08%  |
| Samsung Electronics | 43        | 50     | 7.88%   |
| HGST                | 41        | 41     | 7.51%   |
| Hitachi             | 38        | 41     | 6.96%   |
| Toshiba             | 36        | 43     | 6.59%   |
| Crucial             | 16        | 19     | 2.93%   |
| SanDisk             | 15        | 18     | 2.75%   |
| Kingston            | 15        | 15     | 2.75%   |
| Intel               | 15        | 17     | 2.75%   |
| SK hynix            | 9         | 14     | 1.65%   |
| A-DATA Technology   | 8         | 9      | 1.47%   |
| Micron Technology   | 6         | 8      | 1.1%    |
| LITEON              | 3         | 3      | 0.55%   |
| Transcend           | 2         | 2      | 0.37%   |
| OCZ                 | 2         | 2      | 0.37%   |
| KingSpec            | 2         | 3      | 0.37%   |
| Corsair             | 2         | 6      | 0.37%   |
| ASMT                | 2         | 6      | 0.37%   |
| Apacer              | 2         | 2      | 0.37%   |
| TwinMOS             | 1         | 1      | 0.18%   |
| SPCC                | 1         | 1      | 0.18%   |
| Realtek             | 1         | 1      | 0.18%   |
| Phison              | 1         | 2      | 0.18%   |
| Patriot             | 1         | 1      | 0.18%   |
| Maxtor              | 1         | 1      | 0.18%   |
| MaxDigital          | 1         | 1      | 0.18%   |
| MARSHAL             | 1         | 1      | 0.18%   |
| LITEONIT            | 1         | 1      | 0.18%   |
| Intenso             | 1         | 4      | 0.18%   |
| IM3D                | 1         | 1      | 0.18%   |
| Hewlett-Packard     | 1         | 1      | 0.18%   |
| Fujitsu             | 1         | 1      | 0.18%   |
| Faspeed             | 1         | 1      | 0.18%   |
| Drevo               | 1         | 1      | 0.18%   |
| Apple               | 1         | 1      | 0.18%   |
| Unknown             | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 145       | 210    | 35.98%  |
| WDC                 | 123       | 144    | 30.52%  |
| HGST                | 41        | 41     | 10.17%  |
| Hitachi             | 38        | 41     | 9.43%   |
| Toshiba             | 32        | 39     | 7.94%   |
| Samsung Electronics | 20        | 25     | 4.96%   |
| Maxtor              | 1         | 1      | 0.25%   |
| MaxDigital          | 1         | 1      | 0.25%   |
| MARSHAL             | 1         | 1      | 0.25%   |
| Fujitsu             | 1         | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 382       | 504    | 73.18%  |
| SSD  | 116       | 149    | 22.22%  |
| NVMe | 24        | 27     | 4.6%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WDS256G1X0C-00ENX0 256GB                     | 1         | 1      | 6.67%   |
| WDC WD3200BPVT-24ZEST0 320GB                     | 1         | 1      | 6.67%   |
| WDC WD1600BEKT-75PVMT0 160GB                     | 1         | 1      | 6.67%   |
| WDC WD1600AAJS-65WAA0 160GB                      | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 6.67%   |
| Toshiba MK1059GSM 1TB                            | 1         | 1      | 6.67%   |
| Seagate ST9640320AS 640GB                        | 1         | 1      | 6.67%   |
| Seagate ST3500418AS 500GB                        | 1         | 1      | 6.67%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 6.67%   |
| Seagate ST31000524AS 1TB                         | 1         | 2      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 1      | 6.67%   |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 6.67%   |
| Hitachi HDS721010CLA332 1TB                      | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 33.33%  |
| Seagate             | 4         | 5      | 26.67%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 2         | 2      | 13.33%  |
| Kingston            | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4308      | 9525   | 58.11%  |
| Works    | 2588      | 5165   | 34.91%  |
| Malfunc  | 503       | 680    | 6.78%   |
| Failed   | 15        | 16     | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3976      | 43.6%   |
| AMD                              | 1786      | 19.59%  |
| Samsung Electronics              | 1052      | 11.54%  |
| SanDisk                          | 482       | 5.29%   |
| SK hynix                         | 246       | 2.7%    |
| Phison Electronics               | 207       | 2.27%   |
| ASMedia Technology               | 169       | 1.85%   |
| Kingston Technology Company      | 163       | 1.79%   |
| Toshiba America Info Systems     | 129       | 1.41%   |
| Micron/Crucial Technology        | 116       | 1.27%   |
| Micron Technology                | 101       | 1.11%   |
| Silicon Motion                   | 94        | 1.03%   |
| KIOXIA                           | 91        | 1%      |
| Marvell Technology Group         | 79        | 0.87%   |
| ADATA Technology                 | 77        | 0.84%   |
| JMicron Technology               | 63        | 0.69%   |
| Nvidia                           | 61        | 0.67%   |
| Realtek Semiconductor            | 44        | 0.48%   |
| Union Memory (Shenzhen)          | 30        | 0.33%   |
| Solid State Storage Technology   | 20        | 0.22%   |
| Lite-On Technology               | 17        | 0.19%   |
| Apple                            | 17        | 0.19%   |
| Seagate Technology               | 14        | 0.15%   |
| Shenzhen Longsys Electronics     | 12        | 0.13%   |
| LSI Logic / Symbios Logic        | 9         | 0.1%    |
| VIA Technologies                 | 8         | 0.09%   |
| Silicon Image                    | 6         | 0.07%   |
| Lenovo                           | 6         | 0.07%   |
| Broadcom / LSI                   | 6         | 0.07%   |
| Yangtze Memory Technologies      | 5         | 0.05%   |
| Biwin Storage Technology         | 5         | 0.05%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.04%   |
| Adaptec                          | 4         | 0.04%   |
| Transcend                        | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| INNOGRIT                         | 3         | 0.03%   |
| Silicon Integrated Systems [SiS] | 2         | 0.02%   |
| Solidigm                         | 1         | 0.01%   |
| Promise Technology               | 1         | 0.01%   |
| PMC-Sierra                       | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1344      | 13%     |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 583       | 5.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 372       | 3.6%    |
| AMD 400 Series Chipset SATA Controller                                         | 350       | 3.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 278       | 2.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 263       | 2.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 240       | 2.32%   |
| Samsung NVMe SSD Controller 980                                                | 168       | 1.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 167       | 1.62%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 166       | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 165       | 1.6%    |
| AMD 500 Series Chipset SATA Controller                                         | 159       | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 158       | 1.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 146       | 1.41%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 142       | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 141       | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 136       | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 131       | 1.27%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 130       | 1.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 127       | 1.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 121       | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 119       | 1.15%   |
| Intel SSD 660P Series                                                          | 117       | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 116       | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 112       | 1.08%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 105       | 1.02%   |
| Phison E12 NVMe Controller                                                     | 98        | 0.95%   |
| Intel SATA Controller [RAID mode]                                              | 94        | 0.91%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 91        | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 89        | 0.86%   |
| Intel Comet Lake SATA AHCI Controller                                          | 86        | 0.83%   |
| AMD 300 Series Chipset SATA Controller                                         | 86        | 0.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 81        | 0.78%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 73        | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 72        | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 71        | 0.69%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 70        | 0.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 62        | 0.6%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 61        | 0.59%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 61        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5083      | 56.71%  |
| NVMe | 2857      | 31.88%  |
| RAID | 501       | 5.59%   |
| IDE  | 499       | 5.57%   |
| SAS  | 20        | 0.22%   |
| SCSI | 3         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 4526      | 67.65%  |
| AMD    | 2163      | 32.33%  |
| ARM    | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 133       | 1.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 93        | 1.39%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 81        | 1.21%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 80        | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 75        | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 74        | 1.1%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 74        | 1.1%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 71        | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 70        | 1.04%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 69        | 1.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 66        | 0.98%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 65        | 0.97%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 63        | 0.94%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 62        | 0.92%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 61        | 0.91%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 54        | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 53        | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 52        | 0.78%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 50        | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 48        | 0.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 47        | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 45        | 0.67%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 45        | 0.67%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 44        | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 43        | 0.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 41        | 0.61%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 41        | 0.61%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 40        | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 39        | 0.58%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 37        | 0.55%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 35        | 0.52%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 35        | 0.52%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 34        | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 33        | 0.49%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 33        | 0.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 32        | 0.48%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 32        | 0.48%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 29        | 0.43%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 29        | 0.43%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 29        | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1492      | 22.26%  |
| Intel Core i7           | 1411      | 21.05%  |
| AMD Ryzen 5             | 714       | 10.65%  |
| AMD Ryzen 7             | 589       | 8.79%   |
| Intel Core i3           | 405       | 6.04%   |
| Other                   | 371       | 5.53%   |
| Intel Celeron           | 218       | 3.25%   |
| AMD Ryzen 9             | 166       | 2.48%   |
| Intel Core 2 Duo        | 145       | 2.16%   |
| Intel Xeon              | 131       | 1.95%   |
| Intel Pentium           | 120       | 1.79%   |
| AMD FX                  | 118       | 1.76%   |
| AMD Ryzen 3             | 104       | 1.55%   |
| Intel Core i9           | 48        | 0.72%   |
| Intel Atom              | 47        | 0.7%    |
| AMD A10                 | 44        | 0.66%   |
| Intel Pentium Dual-Core | 43        | 0.64%   |
| AMD Ryzen 7 PRO         | 41        | 0.61%   |
| AMD A8                  | 40        | 0.6%    |
| AMD A4                  | 35        | 0.52%   |
| AMD Ryzen Threadripper  | 30        | 0.45%   |
| AMD A6                  | 30        | 0.45%   |
| AMD Phenom II X4        | 29        | 0.43%   |
| Intel Core 2 Quad       | 28        | 0.42%   |
| Intel Pentium Silver    | 24        | 0.36%   |
| Intel Core 2            | 23        | 0.34%   |
| AMD E1                  | 21        | 0.31%   |
| AMD Athlon II X2        | 21        | 0.31%   |
| AMD Athlon              | 21        | 0.31%   |
| AMD E                   | 19        | 0.28%   |
| AMD Ryzen 5 PRO         | 15        | 0.22%   |
| AMD Phenom II X6        | 12        | 0.18%   |
| AMD Athlon 64 X2        | 12        | 0.18%   |
| AMD E2                  | 10        | 0.15%   |
| Intel Pentium Gold      | 9         | 0.13%   |
| Intel Genuine           | 9         | 0.13%   |
| AMD Athlon X4           | 9         | 0.13%   |
| AMD Athlon II X4        | 9         | 0.13%   |
| Intel Pentium Dual      | 7         | 0.1%    |
| Intel Core m3           | 7         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 2456      | 36.65%  |
| 2       | 2079      | 31.03%  |
| 6       | 1013      | 15.12%  |
| 8       | 761       | 11.36%  |
| 12      | 140       | 2.09%   |
| 16      | 76        | 1.13%   |
| 3       | 51        | 0.76%   |
| 1       | 45        | 0.67%   |
| 10      | 32        | 0.48%   |
| 14      | 31        | 0.46%   |
| 24      | 7         | 0.1%    |
| 32      | 5         | 0.07%   |
| Unknown | 3         | 0.04%   |
| 20      | 2         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 6665      | 99.64%  |
| 2      | 23        | 0.34%   |
| 4      | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5090      | 75.98%  |
| 1       | 1606      | 23.97%  |
| Unknown | 3         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 6593      | 98.46%  |
| Unknown        | 102       | 1.52%   |
| 64-bit         | 1         | 0.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3394      | 49.02%  |
| 0x306a9    | 216       | 3.12%   |
| 0x906ea    | 183       | 2.64%   |
| 0x306c3    | 167       | 2.41%   |
| 0x206a7    | 146       | 2.11%   |
| 0x08701021 | 136       | 1.96%   |
| 0x806ea    | 132       | 1.91%   |
| 0x806ec    | 127       | 1.83%   |
| 0x806c1    | 110       | 1.59%   |
| 0x0800820d | 103       | 1.49%   |
| 0x806e9    | 97        | 1.4%    |
| 0x906e9    | 87        | 1.26%   |
| 0x406e3    | 84        | 1.21%   |
| 0x506e3    | 82        | 1.18%   |
| 0x08701013 | 78        | 1.13%   |
| 0x40651    | 77        | 1.11%   |
| 0x0a50000c | 72        | 1.04%   |
| 0x08108102 | 71        | 1.03%   |
| 0x08600106 | 70        | 1.01%   |
| 0x1067a    | 69        | 1%      |
| 0x08108109 | 66        | 0.95%   |
| 0x306d4    | 62        | 0.9%    |
| 0x706e5    | 49        | 0.71%   |
| 0x06000852 | 49        | 0.71%   |
| 0xa0652    | 47        | 0.68%   |
| 0x08600104 | 47        | 0.68%   |
| 0x08600103 | 47        | 0.68%   |
| 0x806eb    | 45        | 0.65%   |
| 0x08608103 | 42        | 0.61%   |
| 0x20655    | 33        | 0.48%   |
| 0x08001138 | 32        | 0.46%   |
| 0x906a3    | 28        | 0.4%    |
| 0x010000c8 | 28        | 0.4%    |
| 0x0810100b | 26        | 0.38%   |
| 0x906ed    | 24        | 0.35%   |
| 0x406c4    | 24        | 0.35%   |
| 0x0a201016 | 24        | 0.35%   |
| 0x306f2    | 23        | 0.33%   |
| 0x08600102 | 23        | 0.33%   |
| 0x06001119 | 23        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1296      | 19.33%  |
| Zen 2            | 614       | 9.16%   |
| Haswell          | 577       | 8.61%   |
| IvyBridge        | 432       | 6.44%   |
| Zen+             | 430       | 6.41%   |
| SandyBridge      | 376       | 5.61%   |
| Skylake          | 353       | 5.27%   |
| Zen 3            | 296       | 4.42%   |
| Unknown          | 236       | 3.52%   |
| Zen              | 211       | 3.15%   |
| Penryn           | 195       | 2.91%   |
| TigerLake        | 193       | 2.88%   |
| Broadwell        | 170       | 2.54%   |
| CometLake        | 155       | 2.31%   |
| Piledriver       | 151       | 2.25%   |
| Westmere         | 129       | 1.92%   |
| Silvermont       | 117       | 1.75%   |
| IceLake          | 109       | 1.63%   |
| K10              | 94        | 1.4%    |
| Goldmont plus    | 86        | 1.28%   |
| Core             | 78        | 1.16%   |
| Excavator        | 67        | 1%      |
| Alderlake Hybrid | 54        | 0.81%   |
| Goldmont         | 47        | 0.7%    |
| Nehalem          | 44        | 0.66%   |
| Bobcat           | 32        | 0.48%   |
| Steamroller      | 31        | 0.46%   |
| Puma             | 25        | 0.37%   |
| Jaguar           | 24        | 0.36%   |
| K8 Hammer        | 23        | 0.34%   |
| Bulldozer        | 18        | 0.27%   |
| K10 Llano        | 14        | 0.21%   |
| Bonnell          | 13        | 0.19%   |
| NetBurst         | 6         | 0.09%   |
| K8 & K10 hybrid  | 5         | 0.07%   |
| Tremont          | 3         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 3458      | 42.15%  |
| Nvidia                     | 2646      | 32.25%  |
| AMD                        | 2091      | 25.49%  |
| ASPEED Technology          | 5         | 0.06%   |
| ATI Technologies           | 3         | 0.04%   |
| Matrox Electronics Systems | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 259       | 3.09%   |
| AMD Renoir                                                                               | 257       | 3.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 242       | 2.88%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 229       | 2.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 221       | 2.63%   |
| Intel UHD Graphics 620                                                                   | 212       | 2.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 208       | 2.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 173       | 2.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 171       | 2.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 169       | 2.01%   |
| Intel HD Graphics 620                                                                    | 154       | 1.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 145       | 1.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 131       | 1.56%   |
| Intel HD Graphics 5500                                                                   | 131       | 1.56%   |
| Intel HD Graphics 630                                                                    | 124       | 1.48%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 119       | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 106       | 1.26%   |
| Intel HD Graphics 530                                                                    | 99        | 1.18%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 96        | 1.14%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 91        | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 90        | 1.07%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 89        | 1.06%   |
| AMD Lucienne                                                                             | 83        | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 74        | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 73        | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 73        | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 70        | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 70        | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 68        | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 68        | 0.81%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 63        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 61        | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 59        | 0.7%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 55        | 0.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 55        | 0.66%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 52        | 0.62%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 50        | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 48        | 0.57%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 47        | 0.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 46        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2186      | 32.42%  |
| 1 x AMD            | 1642      | 24.35%  |
| 1 x Nvidia         | 1360      | 20.17%  |
| Intel + Nvidia     | 1053      | 15.62%  |
| AMD + Nvidia       | 202       | 3%      |
| Intel + AMD        | 143       | 2.12%   |
| 2 x AMD            | 114       | 1.69%   |
| 2 x Nvidia         | 29        | 0.43%   |
| 1 x ASPEED         | 4         | 0.06%   |
| Other              | 3         | 0.04%   |
| 2 x Intel          | 2         | 0.03%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| Nvidia + ASPEED    | 1         | 0.01%   |
| 1 x Matrox         | 1         | 0.01%   |
| Intel + 2 x AMD    | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 4908      | 72.53%  |
| Proprietary | 1844      | 27.25%  |
| Unknown     | 15        | 0.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4263      | 62.37%  |
| 1.01-2.0   | 573       | 8.38%   |
| 7.01-8.0   | 440       | 6.44%   |
| 0.01-0.5   | 437       | 6.39%   |
| 3.01-4.0   | 399       | 5.84%   |
| 0.51-1.0   | 282       | 4.13%   |
| 5.01-6.0   | 242       | 3.54%   |
| 8.01-16.0  | 117       | 1.71%   |
| 2.01-3.0   | 63        | 0.92%   |
| 16.01-24.0 | 17        | 0.25%   |
| 4.01-5.0   | 2         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 867       | 11.03%  |
| AU Optronics            | 805       | 10.24%  |
| BOE                     | 714       | 9.08%   |
| LG Display              | 702       | 8.93%   |
| Chimei Innolux          | 686       | 8.72%   |
| Goldstar                | 447       | 5.68%   |
| Dell                    | 427       | 5.43%   |
| Acer                    | 294       | 3.74%   |
| AOC                     | 238       | 3.03%   |
| BenQ                    | 223       | 2.84%   |
| Ancor Communications    | 222       | 2.82%   |
| Hewlett-Packard         | 206       | 2.62%   |
| Philips                 | 171       | 2.17%   |
| Sharp                   | 164       | 2.09%   |
| Lenovo                  | 127       | 1.62%   |
| Apple                   | 119       | 1.51%   |
| LG Electronics          | 107       | 1.36%   |
| PANDA                   | 99        | 1.26%   |
| ViewSonic               | 94        | 1.2%    |
| ASUSTek Computer        | 83        | 1.06%   |
| Chi Mei Optoelectronics | 82        | 1.04%   |
| Iiyama                  | 63        | 0.8%    |
| Unknown                 | 49        | 0.62%   |
| Sony                    | 42        | 0.53%   |
| InfoVision              | 42        | 0.53%   |
| Unknown                 | 38        | 0.48%   |
| Panasonic               | 28        | 0.36%   |
| CSO                     | 28        | 0.36%   |
| MSI                     | 26        | 0.33%   |
| Vizio                   | 24        | 0.31%   |
| Eizo                    | 24        | 0.31%   |
| NEC Computers           | 22        | 0.28%   |
| TMX                     | 21        | 0.27%   |
| Fujitsu Siemens         | 21        | 0.27%   |
| Sceptre Tech            | 20        | 0.25%   |
| Toshiba                 | 18        | 0.23%   |
| LGD                     | 17        | 0.22%   |
| LG Philips              | 17        | 0.22%   |
| Gigabyte Technology     | 17        | 0.22%   |
| AUS                     | 17        | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 46        | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 43        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 41        | 0.5%    |
| Unknown                                                                  | 38        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 34        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 31        | 0.38%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 29        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 22        | 0.27%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 21        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 21        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 20        | 0.24%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch             | 20        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 20        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 19        | 0.23%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 18        | 0.22%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 18        | 0.22%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 17        | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 16        | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 16        | 0.2%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 16        | 0.2%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.2%    |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 15        | 0.18%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 15        | 0.18%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 14        | 0.17%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 14        | 0.17%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 14        | 0.17%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 13        | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 13        | 0.16%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 13        | 0.16%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.16%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.15%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch             | 12        | 0.15%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 12        | 0.15%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 12        | 0.15%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 12        | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3572      | 47.68%  |
| 1366x768 (WXGA)    | 1090      | 14.55%  |
| 3840x2160 (4K)     | 506       | 6.75%   |
| 2560x1440 (QHD)    | 440       | 5.87%   |
| 1600x900 (HD+)     | 203       | 2.71%   |
| Unknown            | 196       | 2.62%   |
| 1920x1200 (WUXGA)  | 165       | 2.2%    |
| 1680x1050 (WSXGA+) | 159       | 2.12%   |
| 1280x1024 (SXGA)   | 142       | 1.9%    |
| 1440x900 (WXGA+)   | 134       | 1.79%   |
| 3440x1440          | 102       | 1.36%   |
| 2560x1080          | 101       | 1.35%   |
| 1280x800 (WXGA)    | 88        | 1.17%   |
| 3840x1080          | 80        | 1.07%   |
| 2560x1600          | 66        | 0.88%   |
| 1360x768           | 43        | 0.57%   |
| 2880x1800          | 41        | 0.55%   |
| 3840x2400          | 25        | 0.33%   |
| 2160x1440          | 25        | 0.33%   |
| 1920x540           | 18        | 0.24%   |
| 4480x1440          | 13        | 0.17%   |
| 3840x1600          | 13        | 0.17%   |
| 3200x1800 (QHD+)   | 13        | 0.17%   |
| 1280x720 (HD)      | 12        | 0.16%   |
| 5120x1440          | 11        | 0.15%   |
| 5760x1080          | 10        | 0.13%   |
| 3456x2160          | 10        | 0.13%   |
| 3200x2000          | 10        | 0.13%   |
| 2256x1504          | 10        | 0.13%   |
| 1024x768 (XGA)     | 10        | 0.13%   |
| 1600x1200          | 9         | 0.12%   |
| 5760x2160          | 8         | 0.11%   |
| 2736x1824          | 8         | 0.11%   |
| 3600x1080          | 7         | 0.09%   |
| 3286x1080          | 7         | 0.09%   |
| 1920x1280          | 7         | 0.09%   |
| 3840x1200          | 6         | 0.08%   |
| 3000x2000          | 6         | 0.08%   |
| 3520x1080          | 5         | 0.07%   |
| 3360x1080          | 5         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1934      | 25.04%  |
| 13      | 744       | 9.63%   |
| Unknown | 614       | 7.95%   |
| 14      | 606       | 7.85%   |
| 27      | 597       | 7.73%   |
| 24      | 586       | 7.59%   |
| 23      | 475       | 6.15%   |
| 21      | 406       | 5.26%   |
| 17      | 335       | 4.34%   |
| 31      | 178       | 2.3%    |
| 34      | 158       | 2.05%   |
| 19      | 154       | 1.99%   |
| 12      | 107       | 1.39%   |
| 22      | 104       | 1.35%   |
| 18      | 94        | 1.22%   |
| 20      | 79        | 1.02%   |
| 11      | 66        | 0.85%   |
| 16      | 61        | 0.79%   |
| 84      | 51        | 0.66%   |
| 40      | 35        | 0.45%   |
| 32      | 33        | 0.43%   |
| 72      | 30        | 0.39%   |
| 54      | 28        | 0.36%   |
| 25      | 26        | 0.34%   |
| 28      | 19        | 0.25%   |
| 26      | 19        | 0.25%   |
| 48      | 16        | 0.21%   |
| 37      | 16        | 0.21%   |
| 65      | 15        | 0.19%   |
| 49      | 13        | 0.17%   |
| 33      | 12        | 0.16%   |
| 42      | 10        | 0.13%   |
| 29      | 10        | 0.13%   |
| 43      | 9         | 0.12%   |
| 52      | 8         | 0.1%    |
| 36      | 8         | 0.1%    |
| 35      | 8         | 0.1%    |
| 46      | 7         | 0.09%   |
| 10      | 7         | 0.09%   |
| 39      | 6         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 2964      | 39.23%  |
| 501-600     | 1503      | 19.89%  |
| 401-500     | 740       | 9.79%   |
| Unknown     | 614       | 8.13%   |
| 201-300     | 552       | 7.31%   |
| 351-400     | 418       | 5.53%   |
| 601-700     | 268       | 3.55%   |
| 701-800     | 210       | 2.78%   |
| 1001-1500   | 102       | 1.35%   |
| 1501-2000   | 91        | 1.2%    |
| 801-900     | 70        | 0.93%   |
| 901-1000    | 19        | 0.25%   |
| 101-200     | 4         | 0.05%   |
| 1-100       | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5138      | 74.62%  |
| 16/10   | 694       | 10.08%  |
| Unknown | 566       | 8.22%   |
| 21/9    | 181       | 2.63%   |
| 5/4     | 132       | 1.92%   |
| 3/2     | 93        | 1.35%   |
| 4/3     | 41        | 0.6%    |
| 32/9    | 21        | 0.3%    |
| 6/5     | 6         | 0.09%   |
| 0.62    | 3         | 0.04%   |
| 3.40    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 0.56    | 2         | 0.03%   |
| 3.20    | 1         | 0.01%   |
| 1.03    | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.58    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1930      | 25.26%  |
| 201-250        | 1266      | 16.57%  |
| 81-90          | 1046      | 13.69%  |
| Unknown        | 614       | 8.03%   |
| 301-350        | 608       | 7.96%   |
| 351-500        | 410       | 5.37%   |
| 151-200        | 325       | 4.25%   |
| 71-80          | 308       | 4.03%   |
| 121-130        | 239       | 3.13%   |
| 251-300        | 199       | 2.6%    |
| More than 1000 | 166       | 2.17%   |
| 141-150        | 129       | 1.69%   |
| 501-1000       | 113       | 1.48%   |
| 61-70          | 91        | 1.19%   |
| 51-60          | 69        | 0.9%    |
| 111-120        | 54        | 0.71%   |
| 131-140        | 44        | 0.58%   |
| 91-100         | 20        | 0.26%   |
| 41-50          | 6         | 0.08%   |
| 1-40           | 5         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 2166      | 29.2%   |
| 51-100        | 2145      | 28.92%  |
| 101-120       | 1665      | 22.45%  |
| Unknown       | 614       | 8.28%   |
| 161-240       | 484       | 6.53%   |
| More than 240 | 203       | 2.74%   |
| 1-50          | 140       | 1.89%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5284      | 77.32%  |
| 2     | 1319      | 19.3%   |
| 3     | 158       | 2.31%   |
| 0     | 59        | 0.86%   |
| 4     | 14        | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3781      | 37.63%  |
| Intel                             | 3461      | 34.45%  |
| Qualcomm Atheros                  | 1004      | 9.99%   |
| Broadcom                          | 410       | 4.08%   |
| MediaTek                          | 142       | 1.41%   |
| Ralink Technology                 | 129       | 1.28%   |
| TP-Link                           | 128       | 1.27%   |
| Broadcom Limited                  | 96        | 0.96%   |
| Ralink                            | 71        | 0.71%   |
| Marvell Technology Group          | 59        | 0.59%   |
| Microsoft                         | 50        | 0.5%    |
| Nvidia                            | 44        | 0.44%   |
| Xiaomi                            | 43        | 0.43%   |
| Samsung Electronics               | 42        | 0.42%   |
| ASIX Electronics                  | 40        | 0.4%    |
| Sierra Wireless                   | 35        | 0.35%   |
| Qualcomm Atheros Communications   | 32        | 0.32%   |
| Aquantia                          | 32        | 0.32%   |
| Huawei Technologies               | 29        | 0.29%   |
| ASUSTek Computer                  | 29        | 0.29%   |
| Lenovo                            | 28        | 0.28%   |
| NetGear                           | 25        | 0.25%   |
| DisplayLink                       | 23        | 0.23%   |
| Dell                              | 22        | 0.22%   |
| D-Link                            | 22        | 0.22%   |
| Qualcomm                          | 21        | 0.21%   |
| Linksys                           | 19        | 0.19%   |
| JMicron Technology                | 17        | 0.17%   |
| Hewlett-Packard                   | 16        | 0.16%   |
| Edimax Technology                 | 14        | 0.14%   |
| Ericsson Business Mobile Networks | 12        | 0.12%   |
| D-Link System                     | 10        | 0.1%    |
| OnePlus Technology (Shenzhen)     | 9         | 0.09%   |
| Microchip Technology              | 9         | 0.09%   |
| Google                            | 9         | 0.09%   |
| Motorola PCS                      | 8         | 0.08%   |
| Fibocom                           | 8         | 0.08%   |
| Mellanox Technologies             | 7         | 0.07%   |
| Apple                             | 7         | 0.07%   |
| ZyXEL Communications              | 6         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2647      | 22.42%  |
| Intel Wi-Fi 6 AX200                                               | 509       | 4.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 354       | 3%      |
| Intel I211 Gigabit Network Connection                             | 287       | 2.43%   |
| Intel Wireless 8265 / 8275                                        | 240       | 2.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 204       | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 203       | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 188       | 1.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 180       | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 174       | 1.47%   |
| Intel Wireless 7265                                               | 168       | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 156       | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 149       | 1.26%   |
| Intel Wireless 7260                                               | 143       | 1.21%   |
| Intel Wi-Fi 6 AX201                                               | 139       | 1.18%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 130       | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 128       | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 125       | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 112       | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 109       | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 109       | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 105       | 0.89%   |
| Intel Wireless 8260                                               | 105       | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 100       | 0.85%   |
| Intel Wireless 3165                                               | 97        | 0.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 93        | 0.79%   |
| Intel Wireless-AC 9260                                            | 93        | 0.79%   |
| Intel Ethernet Controller I225-V                                  | 91        | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 84        | 0.71%   |
| Intel Ethernet Connection I217-LM                                 | 77        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 74        | 0.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 73        | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 70        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 62        | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 59        | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 57        | 0.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 56        | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 55        | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 53        | 0.45%   |
| Intel Ethernet Connection I217-V                                  | 50        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2708      | 48.35%  |
| Realtek Semiconductor                 | 970       | 17.32%  |
| Qualcomm Atheros                      | 783       | 13.98%  |
| Broadcom                              | 301       | 5.37%   |
| Ralink Technology                     | 129       | 2.3%    |
| MediaTek                              | 128       | 2.29%   |
| TP-Link                               | 121       | 2.16%   |
| Ralink                                | 71        | 1.27%   |
| Broadcom Limited                      | 71        | 1.27%   |
| Microsoft                             | 47        | 0.84%   |
| Sierra Wireless                       | 35        | 0.62%   |
| Qualcomm Atheros Communications       | 32        | 0.57%   |
| ASUSTek Computer                      | 27        | 0.48%   |
| NetGear                               | 25        | 0.45%   |
| D-Link                                | 22        | 0.39%   |
| Linksys                               | 18        | 0.32%   |
| Dell                                  | 16        | 0.29%   |
| Marvell Technology Group              | 14        | 0.25%   |
| Edimax Technology                     | 14        | 0.25%   |
| Qualcomm                              | 10        | 0.18%   |
| Fibocom                               | 8         | 0.14%   |
| D-Link System                         | 7         | 0.12%   |
| ZyXEL Communications                  | 6         | 0.11%   |
| Hewlett-Packard                       | 5         | 0.09%   |
| Belkin Components                     | 4         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.07%   |
| ZyDAS                                 | 3         | 0.05%   |
| Quectel Wireless Solutions            | 3         | 0.05%   |
| Mercucys                              | 3         | 0.05%   |
| IMC Networks                          | 3         | 0.05%   |
| Samsung Electronics                   | 2         | 0.04%   |
| Realtek                               | 2         | 0.04%   |
| AVM                                   | 2         | 0.04%   |
| Xiaomi                                | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Senao                                 | 1         | 0.02%   |
| Philips (or NXP)                      | 1         | 0.02%   |
| Fujitsu Siemens Computers             | 1         | 0.02%   |
| Encore Electronics                    | 1         | 0.02%   |
| Apple                                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 509       | 9.01%   |
| Intel Wireless 8265 / 8275                                     | 240       | 4.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 188       | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 180       | 3.19%   |
| Intel Wireless 7265                                            | 168       | 2.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 156       | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 149       | 2.64%   |
| Intel Wireless 7260                                            | 143       | 2.53%   |
| Intel Wi-Fi 6 AX201                                            | 139       | 2.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 130       | 2.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 125       | 2.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 112       | 1.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 109       | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 109       | 1.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 105       | 1.86%   |
| Intel Wireless 8260                                            | 105       | 1.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 100       | 1.77%   |
| Intel Wireless 3165                                            | 97        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 93        | 1.65%   |
| Intel Wireless-AC 9260                                         | 93        | 1.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 84        | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 74        | 1.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 73        | 1.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 70        | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 59        | 1.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 56        | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 55        | 0.97%   |
| Intel Wireless 3160                                            | 48        | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 45        | 0.8%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 45        | 0.8%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 44        | 0.78%   |
| Realtek 802.11ac NIC                                           | 44        | 0.78%   |
| Ralink MT7601U Wireless Adapter                                | 42        | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 42        | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 42        | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 41        | 0.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 41        | 0.73%   |
| Broadcom BCM43142 802.11b/g/n                                  | 40        | 0.71%   |
| Intel Centrino Wireless-N 2230                                 | 37        | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 36        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3386      | 57.33%  |
| Intel                                  | 1602      | 27.12%  |
| Qualcomm Atheros                       | 306       | 5.18%   |
| Broadcom                               | 164       | 2.78%   |
| Marvell Technology Group               | 45        | 0.76%   |
| Nvidia                                 | 44        | 0.75%   |
| Xiaomi                                 | 41        | 0.69%   |
| ASIX Electronics                       | 40        | 0.68%   |
| Aquantia                               | 32        | 0.54%   |
| Lenovo                                 | 28        | 0.47%   |
| Broadcom Limited                       | 28        | 0.47%   |
| Samsung Electronics                    | 23        | 0.39%   |
| DisplayLink                            | 23        | 0.39%   |
| Huawei Technologies                    | 19        | 0.32%   |
| JMicron Technology                     | 17        | 0.29%   |
| MediaTek                               | 11        | 0.19%   |
| Qualcomm                               | 10        | 0.17%   |
| Google                                 | 9         | 0.15%   |
| TP-Link                                | 7         | 0.12%   |
| Mellanox Technologies                  | 7         | 0.12%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.1%    |
| Apple                                  | 6         | 0.1%    |
| OPPO Electronics                       | 5         | 0.08%   |
| Motorola PCS                           | 5         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.07%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| Microsoft                              | 3         | 0.05%   |
| ICS Advent                             | 3         | 0.05%   |
| Hewlett-Packard                        | 3         | 0.05%   |
| D-Link System                          | 3         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| National Semiconductor                 | 2         | 0.03%   |
| HMD Global                             | 2         | 0.03%   |
| Foxconn / Hon Hai                      | 2         | 0.03%   |
| Attansic Technology                    | 2         | 0.03%   |
| ASUSTek Computer                       | 2         | 0.03%   |
| VIA Technologies                       | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.02%   |
| NetXen Incorporated                    | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2647      | 43.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 354       | 5.85%   |
| Intel I211 Gigabit Network Connection                             | 287       | 4.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 204       | 3.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 203       | 3.35%   |
| Realtek RTL8125 2.5GbE Controller                                 | 174       | 2.88%   |
| Intel Ethernet Connection (2) I219-V                              | 128       | 2.12%   |
| Intel Ethernet Controller I225-V                                  | 91        | 1.5%    |
| Intel Ethernet Connection I217-LM                                 | 77        | 1.27%   |
| Intel Ethernet Connection (7) I219-V                              | 62        | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 57        | 0.94%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 53        | 0.88%   |
| Intel Ethernet Connection I217-V                                  | 50        | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 50        | 0.83%   |
| Intel Ethernet Connection (4) I219-V                              | 47        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 43        | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 42        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 41        | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 37        | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 35        | 0.58%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 33        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 33        | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 31        | 0.51%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 31        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 31        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 30        | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 28        | 0.46%   |
| Intel 82577LM Gigabit Network Connection                          | 28        | 0.46%   |
| Intel Ethernet Connection (6) I219-V                              | 27        | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 26        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 26        | 0.43%   |
| Intel Ethernet Connection (10) I219-V                             | 26        | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 23        | 0.38%   |
| Intel 82574L Gigabit Network Connection                           | 23        | 0.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 23        | 0.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 23        | 0.38%   |
| Intel I210 Gigabit Network Connection                             | 22        | 0.36%   |
| Intel Ethernet Connection I219-V                                  | 21        | 0.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 21        | 0.35%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 20        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5563      | 50.81%  |
| WiFi     | 5280      | 48.22%  |
| Modem    | 95        | 0.87%   |
| Unknown  | 11        | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4134      | 59.03%  |
| Ethernet | 2869      | 40.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 3518      | 52.36%  |
| 1     | 2952      | 43.94%  |
| 3     | 158       | 2.35%   |
| 0     | 72        | 1.07%   |
| 4     | 9         | 0.13%   |
| 5     | 8         | 0.12%   |
| 8     | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 5651      | 83.02%  |
| Yes  | 1156      | 16.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2314      | 50.79%  |
| Realtek Semiconductor           | 498       | 10.93%  |
| Cambridge Silicon Radio         | 343       | 7.53%   |
| Qualcomm Atheros Communications | 336       | 7.37%   |
| IMC Networks                    | 188       | 4.13%   |
| Broadcom                        | 153       | 3.36%   |
| Lite-On Technology              | 149       | 3.27%   |
| Apple                           | 117       | 2.57%   |
| ASUSTek Computer                | 109       | 2.39%   |
| Foxconn / Hon Hai               | 94        | 2.06%   |
| Realtek                         | 44        | 0.97%   |
| Ralink                          | 25        | 0.55%   |
| Dell                            | 24        | 0.53%   |
| MediaTek                        | 23        | 0.5%    |
| Hewlett-Packard                 | 20        | 0.44%   |
| TP-Link                         | 15        | 0.33%   |
| Toshiba                         | 15        | 0.33%   |
| Marvell Semiconductor           | 11        | 0.24%   |
| Foxconn International           | 9         | 0.2%    |
| Edimax Technology               | 9         | 0.2%    |
| Opticis                         | 8         | 0.18%   |
| Dynex                           | 7         | 0.15%   |
| Ralink Technology               | 6         | 0.13%   |
| Alps Electric                   | 6         | 0.13%   |
| HTC (High Tech Computer)        | 5         | 0.11%   |
| Belkin Components               | 5         | 0.11%   |
| SINO WEALTH                     | 4         | 0.09%   |
| Conwise Technology              | 4         | 0.09%   |
| Askey Computer                  | 4         | 0.09%   |
| Integrated System Solution      | 3         | 0.07%   |
| Fujitsu                         | 2         | 0.04%   |
| USI                             | 1         | 0.02%   |
| Sitecom Europe                  | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| D-Link                          | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 754       | 16.52%  |
| Intel AX200 Bluetooth                               | 482       | 10.56%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 348       | 7.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 343       | 7.52%   |
| Intel AX201 Bluetooth                               | 340       | 7.45%   |
| Realtek Bluetooth Radio                             | 322       | 7.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 167       | 3.66%   |
| Realtek  Bluetooth 4.2 Adapter                      | 129       | 2.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 108       | 2.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 88        | 1.93%   |
| IMC Networks Bluetooth Radio                        | 78        | 1.71%   |
| Intel AX210 Bluetooth                               | 66        | 1.45%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 64        | 1.4%    |
| Intel Bluetooth Device                              | 51        | 1.12%   |
| Apple Bluetooth USB Host Controller                 | 50        | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 49        | 1.07%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 46        | 1.01%   |
| Apple Bluetooth Host Controller                     | 46        | 1.01%   |
| Realtek Bluetooth Radio                             | 44        | 0.96%   |
| Lite-On Bluetooth Device                            | 44        | 0.96%   |
| IMC Networks Bluetooth Device                       | 43        | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 41        | 0.9%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 40        | 0.88%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 39        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 38        | 0.83%   |
| IMC Networks Wireless_Device                        | 37        | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 36        | 0.79%   |
| Ralink RT3290 Bluetooth                             | 25        | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 23        | 0.5%    |
| MediaTek Wireless_Device                            | 21        | 0.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.42%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 19        | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.37%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.37%   |
| ASUS Bluetooth Radio                                | 17        | 0.37%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 16        | 0.35%   |
| Realtek RTL8821A Bluetooth                          | 16        | 0.35%   |
| Lite-On Wireless_Device                             | 16        | 0.35%   |
| ASUS ASUS USB-BT500                                 | 16        | 0.35%   |
| TP-Link UB500 Adapter                               | 15        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 4416      | 43.94%  |
| AMD                                  | 2465      | 24.52%  |
| Nvidia                               | 1801      | 17.92%  |
| C-Media Electronics                  | 231       | 2.3%    |
| Logitech                             | 96        | 0.96%   |
| Creative Labs                        | 71        | 0.71%   |
| Kingston Technology                  | 63        | 0.63%   |
| JMTek                                | 55        | 0.55%   |
| Texas Instruments                    | 47        | 0.47%   |
| SteelSeries ApS                      | 41        | 0.41%   |
| Realtek Semiconductor                | 38        | 0.38%   |
| Razer USA                            | 36        | 0.36%   |
| Creative Technology                  | 36        | 0.36%   |
| Corsair                              | 36        | 0.36%   |
| Generalplus Technology               | 35        | 0.35%   |
| Focusrite-Novation                   | 33        | 0.33%   |
| ASUSTek Computer                     | 30        | 0.3%    |
| Blue Microphones                     | 28        | 0.28%   |
| Plantronics                          | 27        | 0.27%   |
| Lenovo                               | 27        | 0.27%   |
| GN Netcom                            | 27        | 0.27%   |
| BEHRINGER International              | 22        | 0.22%   |
| GYROCOM C&C                          | 17        | 0.17%   |
| Sony                                 | 16        | 0.16%   |
| Apple                                | 14        | 0.14%   |
| Sennheiser Communications            | 13        | 0.13%   |
| Samson Technologies                  | 13        | 0.13%   |
| M-Audio                              | 11        | 0.11%   |
| VIA Technologies                     | 10        | 0.1%    |
| RODE Microphones                     | 10        | 0.1%    |
| Turtle Beach                         | 9         | 0.09%   |
| SAVITECH                             | 9         | 0.09%   |
| Giga-Byte Technology                 | 9         | 0.09%   |
| XMOS                                 | 8         | 0.08%   |
| Audio-Technica                       | 8         | 0.08%   |
| Astro Gaming                         | 8         | 0.08%   |
| Yamaha                               | 7         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 7         | 0.07%   |
| Microsoft                            | 7         | 0.07%   |
| Micro Star International             | 7         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 884       | 7.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 550       | 4.53%   |
| AMD Starship/Matisse HD Audio Controller                                   | 448       | 3.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 439       | 3.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 422       | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 338       | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                 | 329       | 2.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 305       | 2.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 304       | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 273       | 2.25%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 244       | 2.01%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 209       | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 198       | 1.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 193       | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 192       | 1.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 179       | 1.47%   |
| Intel 8 Series HD Audio Controller                                         | 175       | 1.44%   |
| Intel Haswell-ULT HD Audio Controller                                      | 174       | 1.43%   |
| AMD FCH Azalia Controller                                                  | 160       | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 155       | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 155       | 1.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 154       | 1.27%   |
| Nvidia GP106 High Definition Audio Controller                              | 152       | 1.25%   |
| Intel 200 Series PCH HD Audio                                              | 144       | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 141       | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 140       | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 138       | 1.14%   |
| AMD Navi 10 HDMI Audio                                                     | 122       | 1%      |
| Intel CM238 HD Audio Controller                                            | 106       | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                              | 105       | 0.86%   |
| Nvidia TU106 High Definition Audio Controller                              | 105       | 0.86%   |
| Intel Comet Lake PCH cAVS                                                  | 103       | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 101       | 0.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 100       | 0.82%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 99        | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 92        | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 86        | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 85        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 85        | 0.7%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 84        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1062      | 22.69%  |
| SK hynix                     | 702       | 15%     |
| Kingston                     | 561       | 11.99%  |
| Micron Technology            | 482       | 10.3%   |
| Corsair                      | 347       | 7.41%   |
| Unknown                      | 308       | 6.58%   |
| Crucial                      | 304       | 6.5%    |
| G.Skill                      | 258       | 5.51%   |
| A-DATA Technology            | 111       | 2.37%   |
| Ramaxel Technology           | 73        | 1.56%   |
| Elpida                       | 60        | 1.28%   |
| Team                         | 51        | 1.09%   |
| Patriot                      | 47        | 1%      |
| Nanya Technology             | 42        | 0.9%    |
| Unknown (ABCD)               | 32        | 0.68%   |
| GOODRAM                      | 28        | 0.6%    |
| Smart                        | 22        | 0.47%   |
| Transcend                    | 20        | 0.43%   |
| Unknown                      | 19        | 0.41%   |
| AMD                          | 11        | 0.24%   |
| Apacer                       | 10        | 0.21%   |
| Silicon Power                | 7         | 0.15%   |
| Kllisre                      | 7         | 0.15%   |
| ASint Technology             | 7         | 0.15%   |
| PNY                          | 5         | 0.11%   |
| GeIL                         | 5         | 0.11%   |
| Teikon                       | 4         | 0.09%   |
| Smart Brazil                 | 4         | 0.09%   |
| Qumo                         | 4         | 0.09%   |
| Neo Forza                    | 4         | 0.09%   |
| Kingmax                      | 4         | 0.09%   |
| Goldkey                      | 4         | 0.09%   |
| Atermiter                    | 4         | 0.09%   |
| SHARETRONIC                  | 3         | 0.06%   |
| Patriot Memory (PDP Systems) | 3         | 0.06%   |
| CSX                          | 3         | 0.06%   |
| Avant                        | 3         | 0.06%   |
| Unknown (08C8)               | 2         | 0.04%   |
| TwinMOS                      | 2         | 0.04%   |
| Timetec                      | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 58        | 1.16%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 57        | 1.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 47        | 0.94%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 45        | 0.9%    |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 45        | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 40        | 0.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 37        | 0.74%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 36        | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 34        | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 32        | 0.64%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 32        | 0.64%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 30        | 0.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 27        | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 27        | 0.54%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 26        | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 22        | 0.44%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 22        | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 21        | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 20        | 0.4%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 20        | 0.4%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.4%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 20        | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.38%   |
| Unknown                                                          | 19        | 0.38%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 18        | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.34%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 17        | 0.34%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 17        | 0.34%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 17        | 0.34%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 16        | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 16        | 0.32%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 16        | 0.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 15        | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2284      | 56.6%   |
| DDR3    | 1134      | 28.1%   |
| LPDDR4  | 167       | 4.14%   |
| LPDDR3  | 128       | 3.17%   |
| Unknown | 85        | 2.11%   |
| DDR2    | 77        | 1.91%   |
| SDRAM   | 73        | 1.81%   |
| DDR5    | 53        | 1.31%   |
| LPDDR5  | 18        | 0.45%   |
| DDR     | 13        | 0.32%   |
| DRAM    | 3         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2196      | 54.52%  |
| DIMM         | 1436      | 35.65%  |
| Row Of Chips | 356       | 8.84%   |
| Chip         | 21        | 0.52%   |
| Unknown      | 13        | 0.32%   |
| RIMM         | 3         | 0.07%   |
| FB-DIMM      | 3         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1941      | 44.35%  |
| 4096  | 1160      | 26.5%   |
| 16384 | 694       | 15.86%  |
| 2048  | 355       | 8.11%   |
| 32768 | 151       | 3.45%   |
| 1024  | 69        | 1.58%   |
| 512   | 5         | 0.11%   |
| 65536 | 1         | 0.02%   |
| 3072  | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 788       | 17.82%  |
| 2667    | 755       | 17.08%  |
| 3200    | 744       | 16.83%  |
| 2400    | 348       | 7.87%   |
| 2133    | 239       | 5.41%   |
| 1333    | 205       | 4.64%   |
| 3600    | 182       | 4.12%   |
| 1867    | 102       | 2.31%   |
| 1334    | 101       | 2.28%   |
| 3266    | 73        | 1.65%   |
| 4267    | 72        | 1.63%   |
| 800     | 57        | 1.29%   |
| 3400    | 53        | 1.2%    |
| 3000    | 53        | 1.2%    |
| 667     | 51        | 1.15%   |
| 4800    | 40        | 0.9%    |
| Unknown | 39        | 0.88%   |
| 1866    | 35        | 0.79%   |
| 3800    | 33        | 0.75%   |
| 3733    | 33        | 0.75%   |
| 3533    | 33        | 0.75%   |
| 1067    | 33        | 0.75%   |
| 3866    | 29        | 0.66%   |
| 4199    | 25        | 0.57%   |
| 3466    | 25        | 0.57%   |
| 2933    | 22        | 0.5%    |
| 1066    | 22        | 0.5%    |
| 4266    | 19        | 0.43%   |
| 6400    | 18        | 0.41%   |
| 2666    | 16        | 0.36%   |
| 2800    | 15        | 0.34%   |
| 1800    | 15        | 0.34%   |
| 2048    | 12        | 0.27%   |
| 3666    | 10        | 0.23%   |
| 975     | 9         | 0.2%    |
| 8400    | 7         | 0.16%   |
| 333     | 7         | 0.16%   |
| 6000    | 6         | 0.14%   |
| 5200    | 6         | 0.14%   |
| 3534    | 6         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 59        | 39.07%  |
| Brother Industries    | 26        | 17.22%  |
| Canon                 | 20        | 13.25%  |
| Seiko Epson           | 14        | 9.27%   |
| Samsung Electronics   | 9         | 5.96%   |
| Pantum                | 3         | 1.99%   |
| Apple                 | 3         | 1.99%   |
| Xerox                 | 2         | 1.32%   |
| Ricoh                 | 2         | 1.32%   |
| Prolific Technology   | 2         | 1.32%   |
| Dymo-CoStar           | 2         | 1.32%   |
| Zebra                 | 1         | 0.66%   |
| Xiaomi                | 1         | 0.66%   |
| STMicroelectronics    | 1         | 0.66%   |
| Sagem                 | 1         | 0.66%   |
| QinHeng Electronics   | 1         | 0.66%   |
| Oki Data              | 1         | 0.66%   |
| Lexmark International | 1         | 0.66%   |
| Kyocera               | 1         | 0.66%   |
| Graphtec America      | 1         | 0.66%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP OfficeJet 5200 series                                  | 4         | 2.63%   |
| HP LaserJet 1300                                          | 3         | 1.97%   |
| HP ENVY 4520 series                                       | 3         | 1.97%   |
| Apple Gamesir-T1s 2.0b                                    | 3         | 1.97%   |
| Xerox Phaser 3020                                         | 2         | 1.32%   |
| Seiko Epson L120 Series                                   | 2         | 1.32%   |
| Samsung ML-1640 Series Laser Printer                      | 2         | 1.32%   |
| Prolific PL2305 Parallel Port                             | 2         | 1.32%   |
| HP Officejet 2620 series                                  | 2         | 1.32%   |
| HP DeskJet 4530 series                                    | 2         | 1.32%   |
| HP DeskJet 3630 series                                    | 2         | 1.32%   |
| HP DeskJet 2700 series                                    | 2         | 1.32%   |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 1.32%   |
| HP DeskJet 2130 series                                    | 2         | 1.32%   |
| HP Color LaserJet Pro M453-4                              | 2         | 1.32%   |
| Canon PIXMA MX340                                         | 2         | 1.32%   |
| Canon PIXMA MG2500 Series                                 | 2         | 1.32%   |
| Canon MG5700 series                                       | 2         | 1.32%   |
| Canon G3010 series                                        | 2         | 1.32%   |
| Brother MFC-L2710DW series                                | 2         | 1.32%   |
| Brother HL-L2300D series                                  | 2         | 1.32%   |
| Brother HL-5370DW series                                  | 2         | 1.32%   |
| Brother DCP-7040                                          | 2         | 1.32%   |
| Zebra ZTC ZC100                                           | 1         | 0.66%   |
| Xiaomi MiMouse 2                                          | 1         | 0.66%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 0.66%   |
| Seiko Epson XP-4100 Series                                | 1         | 0.66%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 0.66%   |
| Seiko Epson Printer                                       | 1         | 0.66%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 0.66%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.66%   |
| Seiko Epson L805 Series                                   | 1         | 0.66%   |
| Seiko Epson L4260 Series                                  | 1         | 0.66%   |
| Seiko Epson L365 Series                                   | 1         | 0.66%   |
| Seiko Epson L355 Series                                   | 1         | 0.66%   |
| Seiko Epson ET-4760 Series                                | 1         | 0.66%   |
| Seiko Epson ET-3850 Series                                | 1         | 0.66%   |
| Seiko Epson ET-2810 Series                                | 1         | 0.66%   |
| Seiko Epson ET-2710 Series                                | 1         | 0.66%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 0.66%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 20        | 64.52%  |
| Seiko Epson        | 5         | 16.13%  |
| Hewlett-Packard    | 2         | 6.45%   |
| Visioneer          | 1         | 3.23%   |
| Ultima Electronics | 1         | 3.23%   |
| Mustek Systems     | 1         | 3.23%   |
| AGFA-Gevaert NV    | 1         | 3.23%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                                               | 5         | 16.13%  |
| Canon CanoScan LiDE 110                                                               | 5         | 16.13%  |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 2         | 6.45%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 2         | 6.45%   |
| Canon CanoScan LIDE 25                                                                | 2         | 6.45%   |
| Visioneer OneTouch 5300 USB                                                           | 1         | 3.23%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 3.23%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 3.23%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 3.23%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 1         | 3.23%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 3.23%   |
| HP ScanJet 3500c                                                                      | 1         | 3.23%   |
| HP ScanJet 3400cse                                                                    | 1         | 3.23%   |
| Canon CanoScan LiDE 90                                                                | 1         | 3.23%   |
| Canon CanoScan LiDE 500F                                                              | 1         | 3.23%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 3.23%   |
| Canon CanoScan LiDE 210                                                               | 1         | 3.23%   |
| Canon CanoScan LiDE 200                                                               | 1         | 3.23%   |
| Canon CanoScan LiDE 120                                                               | 1         | 3.23%   |
| AGFA-Gevaert NV SnapScan e26                                                          | 1         | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 860       | 19.88%  |
| IMC Networks                           | 505       | 11.67%  |
| Microdia                               | 336       | 7.77%   |
| Realtek Semiconductor                  | 320       | 7.4%    |
| Logitech                               | 312       | 7.21%   |
| Quanta                                 | 235       | 5.43%   |
| Sunplus Innovation Technology          | 192       | 4.44%   |
| Bison Electronics                      | 173       | 4%      |
| Acer                                   | 151       | 3.49%   |
| Cheng Uei Precision Industry (Foxlink) | 149       | 3.44%   |
| Syntek                                 | 118       | 2.73%   |
| Lite-On Technology                     | 115       | 2.66%   |
| Apple                                  | 98        | 2.27%   |
| Suyin                                  | 93        | 2.15%   |
| Microsoft                              | 69        | 1.6%    |
| Silicon Motion                         | 58        | 1.34%   |
| Luxvisions Innotech Limited            | 57        | 1.32%   |
| Alcor Micro                            | 52        | 1.2%    |
| Samsung Electronics                    | 48        | 1.11%   |
| Z-Star Microelectronics                | 26        | 0.6%    |
| Ricoh                                  | 21        | 0.49%   |
| Sonix Technology                       | 18        | 0.42%   |
| Creative Technology                    | 15        | 0.35%   |
| Lenovo                                 | 14        | 0.32%   |
| MacroSilicon                           | 13        | 0.3%    |
| Importek                               | 13        | 0.3%    |
| GEMBIRD                                | 13        | 0.3%    |
| Generalplus Technology                 | 11        | 0.25%   |
| Primax Electronics                     | 10        | 0.23%   |
| SunplusIT                              | 9         | 0.21%   |
| LG Electronics                         | 9         | 0.21%   |
| Genesys Logic                          | 9         | 0.21%   |
| ARC International                      | 9         | 0.21%   |
| KYE Systems (Mouse Systems)            | 8         | 0.18%   |
| Google                                 | 8         | 0.18%   |
| DigiTech                               | 7         | 0.16%   |
| Cubeternet                             | 7         | 0.16%   |
| ALi                                    | 7         | 0.16%   |
| 2M UVC CAMERA                          | 7         | 0.16%   |
| USB Camera                             | 6         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 217       | 4.98%   |
| IMC Networks Integrated Camera                      | 168       | 3.86%   |
| Microdia Integrated_Webcam_HD                       | 145       | 3.33%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 127       | 2.91%   |
| Realtek Integrated_Webcam_HD                        | 120       | 2.75%   |
| Chicony HD WebCam                                   | 88        | 2.02%   |
| Syntek Integrated Camera                            | 80        | 1.84%   |
| Logitech Webcam C270                                | 73        | 1.68%   |
| Sunplus Integrated_Webcam_HD                        | 58        | 1.33%   |
| Bison Integrated Camera                             | 57        | 1.31%   |
| Logitech HD Pro Webcam C920                         | 54        | 1.24%   |
| Acer Integrated Camera                              | 51        | 1.17%   |
| Samsung Galaxy A5 (MTP)                             | 48        | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 47        | 1.08%   |
| Lite-On Integrated Camera                           | 39        | 0.9%    |
| Chicony HP Wide Vision HD Camera                    | 36        | 0.83%   |
| Quanta HP TrueVision HD Camera                      | 35        | 0.8%    |
| Quanta HD User Facing                               | 34        | 0.78%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 34        | 0.78%   |
| Chicony HP HD Camera                                | 31        | 0.71%   |
| Acer HD Webcam                                      | 30        | 0.69%   |
| Chicony USB2.0 Camera                               | 29        | 0.67%   |
| Chicony HD User Facing                              | 27        | 0.62%   |
| Microsoft LifeCam HD-3000                           | 26        | 0.6%    |
| Lite-On HP HD Camera                                | 26        | 0.6%    |
| Microdia Webcam Vitade AF                           | 25        | 0.57%   |
| Logitech C922 Pro Stream Webcam                     | 25        | 0.57%   |
| Chicony USB2.0 HD UVC WebCam                        | 25        | 0.57%   |
| Bison SunplusIT Integrated Camera                   | 25        | 0.57%   |
| Realtek USB Camera                                  | 24        | 0.55%   |
| Quanta HP Wide Vision HD Camera                     | 24        | 0.55%   |
| Microdia Integrated Webcam                          | 24        | 0.55%   |
| Chicony Lenovo EasyCamera                           | 24        | 0.55%   |
| Chicony EasyCamera                                  | 24        | 0.55%   |
| Chicony HP Truevision HD                            | 23        | 0.53%   |
| Acer Lenovo EasyCamera                              | 23        | 0.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 22        | 0.5%    |
| IMC Networks HD Camera                              | 22        | 0.5%    |
| Syntek Lenovo EasyCamera                            | 21        | 0.48%   |
| IMC Networks HP TrueVision HD Camera                | 21        | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 276       | 31.12%  |
| Validity Sensors                   | 256       | 28.86%  |
| Shenzhen Goodix Technology         | 181       | 20.41%  |
| Elan Microelectronics              | 65        | 7.33%   |
| LighTuning Technology              | 37        | 4.17%   |
| Upek                               | 27        | 3.04%   |
| AuthenTec                          | 22        | 2.48%   |
| STMicroelectronics                 | 8         | 0.9%    |
| Samsung Electronics                | 6         | 0.68%   |
| Focal-systems.Corp                 | 4         | 0.45%   |
| DigitalPersona                     | 2         | 0.23%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.11%   |
| HOLTEK                             | 1         | 0.11%   |
| Futronic Technology                | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 87        | 9.81%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 66        | 7.44%   |
| Shenzhen Goodix Fingerprint Reader                                         | 65        | 7.33%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 52        | 5.86%   |
| Elan ELAN:Fingerprint                                                      | 40        | 4.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 37        | 4.17%   |
| Synaptics UWP WBDI                                                         | 37        | 4.17%   |
| Validity Sensors Synaptics WBDI                                            | 31        | 3.49%   |
| Synaptics WBDI                                                             | 29        | 3.27%   |
| Shenzhen Goodix FingerPrint                                                | 29        | 3.27%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 3.16%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 2.71%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 24        | 2.71%   |
| Synaptics  WBDI                                                            | 23        | 2.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 2.59%   |
| Elan ELAN:ARM-M4                                                           | 21        | 2.37%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.14%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 18        | 2.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 18        | 2.03%   |
| Validity Sensors VFS491                                                    | 16        | 1.8%    |
| Validity Sensors Fingerprint scanner                                       | 15        | 1.69%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 15        | 1.69%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 13        | 1.47%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 1.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 12        | 1.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 10        | 1.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1.01%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 9         | 1.01%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 0.9%    |
| Synaptics UWP WBDI Device                                                  | 7         | 0.79%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.79%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 0.68%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.68%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 0.56%   |
| Synaptics WBDI Device                                                      | 5         | 0.56%   |
| AuthenTec AES2810                                                          | 5         | 0.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.45%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 4         | 0.45%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 0.45%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 0.45%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 97        | 35.14%  |
| Broadcom                          | 93        | 33.7%   |
| Upek                              | 16        | 5.8%    |
| O2 Micro                          | 16        | 5.8%    |
| Lenovo                            | 16        | 5.8%    |
| Yubico.com                        | 9         | 3.26%   |
| Gemalto (was Gemplus)             | 9         | 3.26%   |
| VASCO Data Security International | 4         | 1.45%   |
| Realtek Semiconductor             | 4         | 1.45%   |
| OmniKey                           | 3         | 1.09%   |
| SCM Microsystems                  | 1         | 0.36%   |
| Reiner SCT Kartensysteme          | 1         | 0.36%   |
| Hewlett-Packard                   | 1         | 0.36%   |
| Clay Logic                        | 1         | 0.36%   |
| Cherry                            | 1         | 0.36%   |
| C3PO                              | 1         | 0.36%   |
| BIT4ID                            | 1         | 0.36%   |
| Aladdin Knowledge Systems         | 1         | 0.36%   |
| Advanced Card Systems             | 1         | 0.36%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 96        | 34.78%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 12.68%  |
| Broadcom 5880                                                                | 27        | 9.78%   |
| Broadcom 58200                                                               | 19        | 6.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 5.8%    |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.8%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 5.43%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 4.35%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 7         | 2.54%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 6         | 2.17%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 1.45%   |
| OmniKey 3x21 Smart Card Reader                                               | 3         | 1.09%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.72%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 2         | 0.72%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.72%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.36%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.36%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.36%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.36%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.36%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.36%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 0.36%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.36%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.36%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.36%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.36%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.36%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.36%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.36%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 4749      | 69.59%  |
| 1     | 1697      | 24.87%  |
| 2     | 347       | 5.08%   |
| 3     | 28        | 0.41%   |
| 4     | 3         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 871       | 36.16%  |
| Graphics card            | 410       | 17.02%  |
| Net/wireless             | 318       | 13.2%   |
| Chipcard                 | 242       | 10.05%  |
| Multimedia controller    | 193       | 8.01%   |
| Camera                   | 84        | 3.49%   |
| Net/ethernet             | 62        | 2.57%   |
| Unassigned class         | 55        | 2.28%   |
| Bluetooth                | 46        | 1.91%   |
| Sound                    | 27        | 1.12%   |
| Communication controller | 24        | 1%      |
| Storage                  | 21        | 0.87%   |
| Card reader              | 16        | 0.66%   |
| Dvb card                 | 13        | 0.54%   |
| Network                  | 8         | 0.33%   |
| Storage/raid             | 6         | 0.25%   |
| Modem                    | 5         | 0.21%   |
| Video                    | 2         | 0.08%   |
| Storage/nvme             | 2         | 0.08%   |
| Storage/ide              | 2         | 0.08%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ata              | 1         | 0.04%   |

