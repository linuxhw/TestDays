Linux in Bulgaria - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bulgaria/Desktop/README.md) and [notebooks](/Location/Bulgaria/Notebook/README.md).

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

Total: 1781

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 18E7                        | Desktop     | [84caef4dde](https://linux-hardware.org/?probe=84caef4dde) | Feb 02, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [e87efb031b](https://linux-hardware.org/?probe=e87efb031b) | Feb 02, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bb16eb2e4a](https://linux-hardware.org/?probe=bb16eb2e4a) | Feb 01, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [bc55b0bd50](https://linux-hardware.org/?probe=bc55b0bd50) | Feb 01, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [62254b1636](https://linux-hardware.org/?probe=62254b1636) | Jan 31, 2024 |
| Acer          | Aspire A315-41              | Notebook    | [a78d79030e](https://linux-hardware.org/?probe=a78d79030e) | Jan 30, 2024 |
| Dell          | Studio 1747                 | Notebook    | [b43d9b4a13](https://linux-hardware.org/?probe=b43d9b4a13) | Jan 29, 2024 |
| Dell          | Studio 1747                 | Notebook    | [9fe0b059bc](https://linux-hardware.org/?probe=9fe0b059bc) | Jan 29, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [49e891b67d](https://linux-hardware.org/?probe=49e891b67d) | Jan 28, 2024 |
| Dell          | 01W23F A05                  | Server      | [93f017d8b0](https://linux-hardware.org/?probe=93f017d8b0) | Jan 27, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9b55015259](https://linux-hardware.org/?probe=9b55015259) | Jan 26, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3cecdef02f](https://linux-hardware.org/?probe=3cecdef02f) | Jan 26, 2024 |
| ASUSTek       | M2N-E SLI                   | Desktop     | [32d1dff107](https://linux-hardware.org/?probe=32d1dff107) | Jan 26, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [44539fb8b1](https://linux-hardware.org/?probe=44539fb8b1) | Jan 25, 2024 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [dc93e0097a](https://linux-hardware.org/?probe=dc93e0097a) | Jan 25, 2024 |
| HP            | 3648h                       | Desktop     | [3905de5f4f](https://linux-hardware.org/?probe=3905de5f4f) | Jan 24, 2024 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [be74f076bd](https://linux-hardware.org/?probe=be74f076bd) | Jan 23, 2024 |
| Dell          | Latitude 7280               | Notebook    | [21e6e4a581](https://linux-hardware.org/?probe=21e6e4a581) | Jan 22, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [0b0db0e2ef](https://linux-hardware.org/?probe=0b0db0e2ef) | Jan 22, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [36cb9057d7](https://linux-hardware.org/?probe=36cb9057d7) | Jan 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [f6204361d0](https://linux-hardware.org/?probe=f6204361d0) | Jan 19, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [12539bda5e](https://linux-hardware.org/?probe=12539bda5e) | Jan 19, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [667df4a998](https://linux-hardware.org/?probe=667df4a998) | Jan 17, 2024 |
| HP            | 255 G3                      | Notebook    | [7f8af802a0](https://linux-hardware.org/?probe=7f8af802a0) | Jan 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [82f1c7e4f3](https://linux-hardware.org/?probe=82f1c7e4f3) | Jan 14, 2024 |
| HP            | EliteBook 745 G5            | Notebook    | [64314a5149](https://linux-hardware.org/?probe=64314a5149) | Jan 13, 2024 |
| ASUSTek       | PRIME Z690-P                | Desktop     | [b37b59525e](https://linux-hardware.org/?probe=b37b59525e) | Jan 12, 2024 |
| Dell          | Latitude 5431               | Notebook    | [45d7b96fb3](https://linux-hardware.org/?probe=45d7b96fb3) | Jan 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a249210b7f](https://linux-hardware.org/?probe=a249210b7f) | Jan 11, 2024 |
| Dell          | Latitude E7470              | Notebook    | [2d36d1a363](https://linux-hardware.org/?probe=2d36d1a363) | Jan 11, 2024 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [f46fcb5ee9](https://linux-hardware.org/?probe=f46fcb5ee9) | Jan 10, 2024 |
| MSI           | Katana GF66 12UG            | Notebook    | [d4affacb08](https://linux-hardware.org/?probe=d4affacb08) | Jan 08, 2024 |
| Dell          | Latitude 7280               | Notebook    | [9557a37753](https://linux-hardware.org/?probe=9557a37753) | Jan 05, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | Notebook    | [41a278e922](https://linux-hardware.org/?probe=41a278e922) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [26ec173956](https://linux-hardware.org/?probe=26ec173956) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [514f7e46c3](https://linux-hardware.org/?probe=514f7e46c3) | Jan 04, 2024 |
| Dell          | Latitude D630               | Notebook    | [e48315d3aa](https://linux-hardware.org/?probe=e48315d3aa) | Jan 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [88f364d196](https://linux-hardware.org/?probe=88f364d196) | Jan 03, 2024 |
| ASRock        | Z87 Extreme4                | Desktop     | [eb75366525](https://linux-hardware.org/?probe=eb75366525) | Jan 03, 2024 |
| ASRock        | Z87 Extreme4                | Desktop     | [2b8d61b50d](https://linux-hardware.org/?probe=2b8d61b50d) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [15ae58d88c](https://linux-hardware.org/?probe=15ae58d88c) | Jan 03, 2024 |
| Lenovo        | G500 20236                  | Notebook    | [c9312cc676](https://linux-hardware.org/?probe=c9312cc676) | Jan 03, 2024 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c106ff91a5](https://linux-hardware.org/?probe=c106ff91a5) | Jan 02, 2024 |
| Sony          | VGN-CS21Z_Q                 | Notebook    | [6c9140100e](https://linux-hardware.org/?probe=6c9140100e) | Dec 30, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [8651fcb2dc](https://linux-hardware.org/?probe=8651fcb2dc) | Dec 30, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [63af20b791](https://linux-hardware.org/?probe=63af20b791) | Dec 29, 2023 |
| Dell          | Precision 5560              | Notebook    | [3555a4c2fa](https://linux-hardware.org/?probe=3555a4c2fa) | Dec 29, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c8430d442b](https://linux-hardware.org/?probe=c8430d442b) | Dec 29, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [87e63ff33e](https://linux-hardware.org/?probe=87e63ff33e) | Dec 27, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [2eb4d57b39](https://linux-hardware.org/?probe=2eb4d57b39) | Dec 27, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d412fe88ac](https://linux-hardware.org/?probe=d412fe88ac) | Dec 27, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [5aae59ec96](https://linux-hardware.org/?probe=5aae59ec96) | Dec 27, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [217704dcb3](https://linux-hardware.org/?probe=217704dcb3) | Dec 27, 2023 |
| Biostar       | H61MHV3                     | Desktop     | [f03f05706c](https://linux-hardware.org/?probe=f03f05706c) | Dec 26, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [ec9fe6e527](https://linux-hardware.org/?probe=ec9fe6e527) | Dec 26, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [148b2b7232](https://linux-hardware.org/?probe=148b2b7232) | Dec 25, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [1ef527f93a](https://linux-hardware.org/?probe=1ef527f93a) | Dec 24, 2023 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [09ab03cdcd](https://linux-hardware.org/?probe=09ab03cdcd) | Dec 19, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f210e0dd64](https://linux-hardware.org/?probe=f210e0dd64) | Dec 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7b209666a3](https://linux-hardware.org/?probe=7b209666a3) | Dec 16, 2023 |
| MSI           | PRO B650M-P                 | Desktop     | [acee62fb75](https://linux-hardware.org/?probe=acee62fb75) | Dec 13, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [c6c8d22a8e](https://linux-hardware.org/?probe=c6c8d22a8e) | Dec 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [f18bd26311](https://linux-hardware.org/?probe=f18bd26311) | Dec 13, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [ce858f7f7c](https://linux-hardware.org/?probe=ce858f7f7c) | Dec 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [c71041fa59](https://linux-hardware.org/?probe=c71041fa59) | Dec 12, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [a4bdf16134](https://linux-hardware.org/?probe=a4bdf16134) | Dec 12, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [1bec383138](https://linux-hardware.org/?probe=1bec383138) | Dec 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [11ae906f6f](https://linux-hardware.org/?probe=11ae906f6f) | Dec 11, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [fc475e4cd3](https://linux-hardware.org/?probe=fc475e4cd3) | Dec 11, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [0841e29863](https://linux-hardware.org/?probe=0841e29863) | Dec 10, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [b2743fd826](https://linux-hardware.org/?probe=b2743fd826) | Dec 09, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [3c17f8cde4](https://linux-hardware.org/?probe=3c17f8cde4) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [7fdc3ff8fd](https://linux-hardware.org/?probe=7fdc3ff8fd) | Dec 08, 2023 |
| Dell          | 0GM819                      | Desktop     | [8ff7ec90b2](https://linux-hardware.org/?probe=8ff7ec90b2) | Dec 05, 2023 |
| Lenovo        | 3000 G410                   | Notebook    | [439199aff4](https://linux-hardware.org/?probe=439199aff4) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4cbc340e7c](https://linux-hardware.org/?probe=4cbc340e7c) | Dec 01, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [487fe9610f](https://linux-hardware.org/?probe=487fe9610f) | Nov 30, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [80e09b727b](https://linux-hardware.org/?probe=80e09b727b) | Nov 30, 2023 |
| HP            | EliteBook 8530p             | Notebook    | [d4dbee494a](https://linux-hardware.org/?probe=d4dbee494a) | Nov 29, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [99719fb0f6](https://linux-hardware.org/?probe=99719fb0f6) | Nov 27, 2023 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [eec1358334](https://linux-hardware.org/?probe=eec1358334) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | Desktop     | [e3473e64c5](https://linux-hardware.org/?probe=e3473e64c5) | Nov 27, 2023 |
| ECS           | H81H3-M3                    | Desktop     | [c9b79740d2](https://linux-hardware.org/?probe=c9b79740d2) | Nov 27, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DV0Y    | Notebook    | [c68289cf4c](https://linux-hardware.org/?probe=c68289cf4c) | Nov 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [de192ce8b7](https://linux-hardware.org/?probe=de192ce8b7) | Nov 26, 2023 |
| HP            | Pavilion dv5                | Notebook    | [51fc2d77fc](https://linux-hardware.org/?probe=51fc2d77fc) | Nov 26, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [e604b5ce78](https://linux-hardware.org/?probe=e604b5ce78) | Nov 25, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [d979c6298f](https://linux-hardware.org/?probe=d979c6298f) | Nov 24, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [9a8395f2ac](https://linux-hardware.org/?probe=9a8395f2ac) | Nov 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [2ab4754aa8](https://linux-hardware.org/?probe=2ab4754aa8) | Nov 23, 2023 |
| Lenovo        | Legion Slim 5 16APH8 82Y... | Notebook    | [6f740bc140](https://linux-hardware.org/?probe=6f740bc140) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [9315424410](https://linux-hardware.org/?probe=9315424410) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [5e92402cde](https://linux-hardware.org/?probe=5e92402cde) | Nov 21, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [eb5f5d4b24](https://linux-hardware.org/?probe=eb5f5d4b24) | Nov 19, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [576d311bde](https://linux-hardware.org/?probe=576d311bde) | Nov 18, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a8cc099fb1](https://linux-hardware.org/?probe=a8cc099fb1) | Nov 18, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [60a416739f](https://linux-hardware.org/?probe=60a416739f) | Nov 17, 2023 |
| Lenovo        | ThinkPad X270 20HMS76D02    | Notebook    | [7da50d5ad3](https://linux-hardware.org/?probe=7da50d5ad3) | Nov 17, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [c7b3d39644](https://linux-hardware.org/?probe=c7b3d39644) | Nov 17, 2023 |
| ASRock        | J3455M                      | Desktop     | [6a3463b7e9](https://linux-hardware.org/?probe=6a3463b7e9) | Nov 15, 2023 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [2e60a77926](https://linux-hardware.org/?probe=2e60a77926) | Nov 14, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [de5f1aa77e](https://linux-hardware.org/?probe=de5f1aa77e) | Nov 11, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c59084f5fe](https://linux-hardware.org/?probe=c59084f5fe) | Nov 09, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [0cdc1967cc](https://linux-hardware.org/?probe=0cdc1967cc) | Nov 09, 2023 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [4a2561319d](https://linux-hardware.org/?probe=4a2561319d) | Nov 08, 2023 |
| Lenovo        | ThinkPad X230 23252EG       | Notebook    | [143a351fe0](https://linux-hardware.org/?probe=143a351fe0) | Nov 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [25ab11fca1](https://linux-hardware.org/?probe=25ab11fca1) | Nov 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [03f6022593](https://linux-hardware.org/?probe=03f6022593) | Nov 07, 2023 |
| HP            | Spectre Pro x360 G2         | Convertible | [de099b29d0](https://linux-hardware.org/?probe=de099b29d0) | Nov 06, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | Notebook    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| Lenovo        | ThinkPad L540 20AUS0YU00    | Notebook    | [16b302d74a](https://linux-hardware.org/?probe=16b302d74a) | Nov 02, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ebfb135726](https://linux-hardware.org/?probe=ebfb135726) | Nov 01, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c06d2e60fc](https://linux-hardware.org/?probe=c06d2e60fc) | Nov 01, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [09b312b58c](https://linux-hardware.org/?probe=09b312b58c) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| Acer          | Aspire 5810T                | Notebook    | [9b65c56faa](https://linux-hardware.org/?probe=9b65c56faa) | Oct 29, 2023 |
| MSI           | PRO B650M-P                 | Desktop     | [521367f574](https://linux-hardware.org/?probe=521367f574) | Oct 29, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [d5afb1c9da](https://linux-hardware.org/?probe=d5afb1c9da) | Oct 25, 2023 |
| Sony          | SVE1712V1EB                 | Notebook    | [3b8803286b](https://linux-hardware.org/?probe=3b8803286b) | Oct 25, 2023 |
| Sony          | SVE1712V1EB                 | Notebook    | [63963cbe04](https://linux-hardware.org/?probe=63963cbe04) | Oct 25, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [e0591a946d](https://linux-hardware.org/?probe=e0591a946d) | Oct 25, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [9c136d661d](https://linux-hardware.org/?probe=9c136d661d) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349B74       | Notebook    | [7f7998c326](https://linux-hardware.org/?probe=7f7998c326) | Oct 22, 2023 |
| ASRock        | H77 Pro4/MVP                | Desktop     | [102735d7e5](https://linux-hardware.org/?probe=102735d7e5) | Oct 21, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [6c4a10bf6e](https://linux-hardware.org/?probe=6c4a10bf6e) | Oct 18, 2023 |
| Gigabyte      | Z590 VISION D               | Desktop     | [f9d3acd4e2](https://linux-hardware.org/?probe=f9d3acd4e2) | Oct 16, 2023 |
| Dell          | Latitude E5410              | Notebook    | [b1559718de](https://linux-hardware.org/?probe=b1559718de) | Oct 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [5b0b094b32](https://linux-hardware.org/?probe=5b0b094b32) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [ca22dfa5cd](https://linux-hardware.org/?probe=ca22dfa5cd) | Oct 14, 2023 |
| ASUSTek       | X542UQ                      | Notebook    | [b795b184d0](https://linux-hardware.org/?probe=b795b184d0) | Oct 14, 2023 |
| ASUSTek       | K73SV                       | Notebook    | [63341aa786](https://linux-hardware.org/?probe=63341aa786) | Oct 13, 2023 |
| ASRock        | B550 Steel Legend           | Desktop     | [c699787ab8](https://linux-hardware.org/?probe=c699787ab8) | Oct 11, 2023 |
| Gigabyte      | M52L-S3P                    | Desktop     | [a3b9e5b40c](https://linux-hardware.org/?probe=a3b9e5b40c) | Oct 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [ec7aee0455](https://linux-hardware.org/?probe=ec7aee0455) | Oct 10, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [e06a9dcd7d](https://linux-hardware.org/?probe=e06a9dcd7d) | Oct 09, 2023 |
| Lenovo        | ThinkPad X200 7458Y28       | Notebook    | [ad9893f44c](https://linux-hardware.org/?probe=ad9893f44c) | Oct 09, 2023 |
| HP            | 635                         | Notebook    | [ef474a26d0](https://linux-hardware.org/?probe=ef474a26d0) | Oct 07, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [93e298660d](https://linux-hardware.org/?probe=93e298660d) | Oct 07, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [233fe08ffd](https://linux-hardware.org/?probe=233fe08ffd) | Oct 07, 2023 |
| AWOW          | AL34                        | Desktop     | [8933a81f53](https://linux-hardware.org/?probe=8933a81f53) | Oct 07, 2023 |
| ONDA          | V80 PLUS                    | Notebook    | [8651e33f83](https://linux-hardware.org/?probe=8651e33f83) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [5584c834bc](https://linux-hardware.org/?probe=5584c834bc) | Oct 04, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [56a4c9aa55](https://linux-hardware.org/?probe=56a4c9aa55) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e705d58ab0](https://linux-hardware.org/?probe=e705d58ab0) | Oct 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d5de51003e](https://linux-hardware.org/?probe=d5de51003e) | Oct 03, 2023 |
| MSI           | A320M GRENADE               | Desktop     | [efd92c3198](https://linux-hardware.org/?probe=efd92c3198) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [6d78bda800](https://linux-hardware.org/?probe=6d78bda800) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Lenovo        | ThinkPad W540 20BG001EUK    | Notebook    | [55f747d352](https://linux-hardware.org/?probe=55f747d352) | Oct 01, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [3b76e2cd65](https://linux-hardware.org/?probe=3b76e2cd65) | Sep 26, 2023 |
| Dell          | Precision 5510              | Notebook    | [34ddd03339](https://linux-hardware.org/?probe=34ddd03339) | Sep 25, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [03aa0d1366](https://linux-hardware.org/?probe=03aa0d1366) | Sep 25, 2023 |
| HP            | 3047h                       | Desktop     | [03fd91188a](https://linux-hardware.org/?probe=03fd91188a) | Sep 24, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [844c35381f](https://linux-hardware.org/?probe=844c35381f) | Sep 23, 2023 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [7e69c8e2e1](https://linux-hardware.org/?probe=7e69c8e2e1) | Sep 23, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [589716b973](https://linux-hardware.org/?probe=589716b973) | Sep 23, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [925fed495b](https://linux-hardware.org/?probe=925fed495b) | Sep 21, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [6c75af44c4](https://linux-hardware.org/?probe=6c75af44c4) | Sep 21, 2023 |
| HP            | 3047h                       | Desktop     | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| Shenzhen M... | F7BSC                       | Desktop     | [a6d51b9c90](https://linux-hardware.org/?probe=a6d51b9c90) | Sep 16, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [08e8a9a1a7](https://linux-hardware.org/?probe=08e8a9a1a7) | Sep 14, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [966d90cbc8](https://linux-hardware.org/?probe=966d90cbc8) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [4ec1be4c03](https://linux-hardware.org/?probe=4ec1be4c03) | Sep 13, 2023 |
| Timi          | A30                         | Notebook    | [7e932a59a6](https://linux-hardware.org/?probe=7e932a59a6) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [744362d446](https://linux-hardware.org/?probe=744362d446) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [82d4f51421](https://linux-hardware.org/?probe=82d4f51421) | Sep 12, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [ae29792d70](https://linux-hardware.org/?probe=ae29792d70) | Sep 11, 2023 |
| ASRock        | H81 Pro BTC                 | Desktop     | [33891eebf8](https://linux-hardware.org/?probe=33891eebf8) | Sep 10, 2023 |
| Dell          | Latitude 5431               | Notebook    | [41e4734fc7](https://linux-hardware.org/?probe=41e4734fc7) | Sep 09, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [0405093009](https://linux-hardware.org/?probe=0405093009) | Sep 09, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [2e5644f065](https://linux-hardware.org/?probe=2e5644f065) | Sep 08, 2023 |
| Dell          | Latitude 5431               | Notebook    | [b2d976a088](https://linux-hardware.org/?probe=b2d976a088) | Sep 08, 2023 |
| MSI           | Bravo 15 C7VF               | Notebook    | [72b288770a](https://linux-hardware.org/?probe=72b288770a) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [34fb398b78](https://linux-hardware.org/?probe=34fb398b78) | Sep 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [19d11f7098](https://linux-hardware.org/?probe=19d11f7098) | Sep 06, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [784e1f216e](https://linux-hardware.org/?probe=784e1f216e) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [a17f1582d4](https://linux-hardware.org/?probe=a17f1582d4) | Sep 05, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [ca342c2a7e](https://linux-hardware.org/?probe=ca342c2a7e) | Sep 05, 2023 |
| Lenovo        | ThinkPad T430 2349KQ3       | Notebook    | [287ea35176](https://linux-hardware.org/?probe=287ea35176) | Sep 05, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [245964564e](https://linux-hardware.org/?probe=245964564e) | Sep 04, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [27684bd06d](https://linux-hardware.org/?probe=27684bd06d) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [479e3b96b2](https://linux-hardware.org/?probe=479e3b96b2) | Sep 04, 2023 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [49101faf53](https://linux-hardware.org/?probe=49101faf53) | Sep 02, 2023 |
| HP            | 1497                        | Desktop     | [43c8de838b](https://linux-hardware.org/?probe=43c8de838b) | Sep 02, 2023 |
| ASUSTek       | P5P43TD                     | Desktop     | [f21550a5b3](https://linux-hardware.org/?probe=f21550a5b3) | Sep 02, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [3db7c113f4](https://linux-hardware.org/?probe=3db7c113f4) | Sep 01, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [ae4d140b96](https://linux-hardware.org/?probe=ae4d140b96) | Aug 31, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [84578c86e7](https://linux-hardware.org/?probe=84578c86e7) | Aug 30, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [6dc701c67d](https://linux-hardware.org/?probe=6dc701c67d) | Aug 29, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [f1b8efb723](https://linux-hardware.org/?probe=f1b8efb723) | Aug 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [85640356ad](https://linux-hardware.org/?probe=85640356ad) | Aug 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [6b6ec006aa](https://linux-hardware.org/?probe=6b6ec006aa) | Aug 28, 2023 |
| Dell          | Precision M4600             | Notebook    | [b7fca4d2f9](https://linux-hardware.org/?probe=b7fca4d2f9) | Aug 27, 2023 |
| Lenovo        | ThinkPad T530 2394D27       | Notebook    | [3dac98b5a5](https://linux-hardware.org/?probe=3dac98b5a5) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [d4cf1916d2](https://linux-hardware.org/?probe=d4cf1916d2) | Aug 26, 2023 |
| Dell          | Studio 1747                 | Notebook    | [e1fe0ee217](https://linux-hardware.org/?probe=e1fe0ee217) | Aug 25, 2023 |
| Dell          | 03NVJ6 A01                  | Desktop     | [71102ac92b](https://linux-hardware.org/?probe=71102ac92b) | Aug 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [74ff13d301](https://linux-hardware.org/?probe=74ff13d301) | Aug 23, 2023 |
| MSI           | GL65 9SE                    | Notebook    | [aa162e5634](https://linux-hardware.org/?probe=aa162e5634) | Aug 22, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [e1a9713e26](https://linux-hardware.org/?probe=e1a9713e26) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [551dc38c00](https://linux-hardware.org/?probe=551dc38c00) | Aug 19, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [0bbf9ab6c2](https://linux-hardware.org/?probe=0bbf9ab6c2) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [f719885fe3](https://linux-hardware.org/?probe=f719885fe3) | Aug 18, 2023 |
| Microsoft     | Surface Laptop 3            | Tablet      | [66691707c9](https://linux-hardware.org/?probe=66691707c9) | Aug 16, 2023 |
| Lenovo        | ThinkPad X395 20NL000HGE    | Notebook    | [3dacfd8a02](https://linux-hardware.org/?probe=3dacfd8a02) | Aug 16, 2023 |
| Dell          | Latitude E4300              | Notebook    | [7c153c96f5](https://linux-hardware.org/?probe=7c153c96f5) | Aug 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [30e2a20d37](https://linux-hardware.org/?probe=30e2a20d37) | Aug 15, 2023 |
| Dell          | Latitude E4300              | Notebook    | [ec4bac7b02](https://linux-hardware.org/?probe=ec4bac7b02) | Aug 14, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [f8c24a1b02](https://linux-hardware.org/?probe=f8c24a1b02) | Aug 11, 2023 |
| Dell          | Precision M4600             | Notebook    | [f97367efac](https://linux-hardware.org/?probe=f97367efac) | Aug 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [89e3ef8e6c](https://linux-hardware.org/?probe=89e3ef8e6c) | Aug 10, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [7723e84488](https://linux-hardware.org/?probe=7723e84488) | Aug 09, 2023 |
| Dell          | Latitude E4300              | Notebook    | [9ae3d19a62](https://linux-hardware.org/?probe=9ae3d19a62) | Aug 09, 2023 |
| Lenovo        | ThinkPad X220 4290W35       | Notebook    | [64db00247d](https://linux-hardware.org/?probe=64db00247d) | Aug 09, 2023 |
| Dell          | Vostro 1700                 | Notebook    | [009c767dae](https://linux-hardware.org/?probe=009c767dae) | Aug 07, 2023 |
| Dell          | Precision 7750              | Notebook    | [cebb7f5165](https://linux-hardware.org/?probe=cebb7f5165) | Aug 06, 2023 |
| HP            | 198E                        | Desktop     | [34023c0d62](https://linux-hardware.org/?probe=34023c0d62) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [75c36d43c3](https://linux-hardware.org/?probe=75c36d43c3) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | Notebook    | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| HP            | ProBook 4530s               | Notebook    | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| HP            | ProLiant DL580 G7           | Server      | [5a9a1e320d](https://linux-hardware.org/?probe=5a9a1e320d) | Jul 24, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [b957598d8e](https://linux-hardware.org/?probe=b957598d8e) | Jul 22, 2023 |
| TUXEDO        | Gemini Gen2                 | Notebook    | [94fe3784a3](https://linux-hardware.org/?probe=94fe3784a3) | Jul 22, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [957a1037ee](https://linux-hardware.org/?probe=957a1037ee) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [ca2f317f1a](https://linux-hardware.org/?probe=ca2f317f1a) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [9f14acd318](https://linux-hardware.org/?probe=9f14acd318) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | Notebook    | [968f0d7741](https://linux-hardware.org/?probe=968f0d7741) | Jul 22, 2023 |
| Acer          | Extensa 215-31              | Notebook    | [e937f82e9d](https://linux-hardware.org/?probe=e937f82e9d) | Jul 22, 2023 |
| HP            | 635                         | Notebook    | [bb148a8b2b](https://linux-hardware.org/?probe=bb148a8b2b) | Jul 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| Dell          | Latitude 7275               | Tablet      | [fdeba04a06](https://linux-hardware.org/?probe=fdeba04a06) | Jul 19, 2023 |
| HP            | ProBook 6570b               | Notebook    | [0a74371e23](https://linux-hardware.org/?probe=0a74371e23) | Jul 18, 2023 |
| Dell          | Inspiron 3551               | Notebook    | [543382ea16](https://linux-hardware.org/?probe=543382ea16) | Jul 16, 2023 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [cd17b6716c](https://linux-hardware.org/?probe=cd17b6716c) | Jul 16, 2023 |
| Dell          | Inspiron 3551               | Notebook    | [74050e892f](https://linux-hardware.org/?probe=74050e892f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7ef2028b06](https://linux-hardware.org/?probe=7ef2028b06) | Jul 13, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [639eb4733c](https://linux-hardware.org/?probe=639eb4733c) | Jul 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | Notebook    | [e40458ffe3](https://linux-hardware.org/?probe=e40458ffe3) | Jul 12, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [8267a42a4f](https://linux-hardware.org/?probe=8267a42a4f) | Jul 11, 2023 |
| Dell          | G15 5511                    | Notebook    | [eebe5b09c0](https://linux-hardware.org/?probe=eebe5b09c0) | Jul 08, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [27f1fe9389](https://linux-hardware.org/?probe=27f1fe9389) | Jul 06, 2023 |
| HP            | Notebook                    | Notebook    | [19d38aa402](https://linux-hardware.org/?probe=19d38aa402) | Jul 05, 2023 |
| HP            | Notebook                    | Notebook    | [ac7ccc907b](https://linux-hardware.org/?probe=ac7ccc907b) | Jul 05, 2023 |
| ASRock        | Z370M Pro4                  | Desktop     | [5b561a0e00](https://linux-hardware.org/?probe=5b561a0e00) | Jul 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e6d6494e7a](https://linux-hardware.org/?probe=e6d6494e7a) | Jul 05, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [b2b20dd3f1](https://linux-hardware.org/?probe=b2b20dd3f1) | Jun 26, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [356b066ca9](https://linux-hardware.org/?probe=356b066ca9) | Jun 24, 2023 |
| ASUSTek       | G551JM                      | Notebook    | [04f17cc1d0](https://linux-hardware.org/?probe=04f17cc1d0) | Jun 24, 2023 |
| Dell          | Latitude 3180               | Notebook    | [a9a4a63807](https://linux-hardware.org/?probe=a9a4a63807) | Jun 24, 2023 |
| ASUSTek       | Maximus VIII RANGER Modi... | Desktop     | [d24120bc4e](https://linux-hardware.org/?probe=d24120bc4e) | Jun 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [7de42486fb](https://linux-hardware.org/?probe=7de42486fb) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [b61cc560f8](https://linux-hardware.org/?probe=b61cc560f8) | Jun 21, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [7423b661e5](https://linux-hardware.org/?probe=7423b661e5) | Jun 20, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [d8d9101ef6](https://linux-hardware.org/?probe=d8d9101ef6) | Jun 19, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [3c0316ef92](https://linux-hardware.org/?probe=3c0316ef92) | Jun 18, 2023 |
| Lenovo        | ThinkPad X230 2325CL7       | Notebook    | [baadfc7e98](https://linux-hardware.org/?probe=baadfc7e98) | Jun 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [5c365e154b](https://linux-hardware.org/?probe=5c365e154b) | Jun 17, 2023 |
| Lenovo        | Unknown                     | Notebook    | [cd3733c1d5](https://linux-hardware.org/?probe=cd3733c1d5) | Jun 16, 2023 |
| Lenovo        | Unknown                     | Notebook    | [e80d3a47d8](https://linux-hardware.org/?probe=e80d3a47d8) | Jun 16, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a6fb35a2d8](https://linux-hardware.org/?probe=a6fb35a2d8) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [29085f8fb4](https://linux-hardware.org/?probe=29085f8fb4) | Jun 10, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a4d08407bb](https://linux-hardware.org/?probe=a4d08407bb) | Jun 09, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [3d694e1b9a](https://linux-hardware.org/?probe=3d694e1b9a) | Jun 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [6de4ea13fe](https://linux-hardware.org/?probe=6de4ea13fe) | Jun 08, 2023 |
| Dell          | Precision 7710              | Notebook    | [f1b57ded18](https://linux-hardware.org/?probe=f1b57ded18) | Jun 08, 2023 |
| Dell          | Latitude 3350               | Notebook    | [ef85473c50](https://linux-hardware.org/?probe=ef85473c50) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [413aba0d3f](https://linux-hardware.org/?probe=413aba0d3f) | Jun 04, 2023 |
| Cube          | i16-L                       | Notebook    | [5e0bd26a26](https://linux-hardware.org/?probe=5e0bd26a26) | Jun 04, 2023 |
| HP            | 3047h                       | Desktop     | [1825675e99](https://linux-hardware.org/?probe=1825675e99) | Jun 03, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [de331bfb5c](https://linux-hardware.org/?probe=de331bfb5c) | Jun 02, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS4LL00    | Notebook    | [7519448ca8](https://linux-hardware.org/?probe=7519448ca8) | May 30, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [94e5a63c07](https://linux-hardware.org/?probe=94e5a63c07) | May 29, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [aeb6fa2258](https://linux-hardware.org/?probe=aeb6fa2258) | May 26, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [5dd56ed986](https://linux-hardware.org/?probe=5dd56ed986) | May 25, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [f0e96b17d7](https://linux-hardware.org/?probe=f0e96b17d7) | May 24, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [02d5fa9cc3](https://linux-hardware.org/?probe=02d5fa9cc3) | May 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [563922ce1c](https://linux-hardware.org/?probe=563922ce1c) | May 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [87bf7a95c8](https://linux-hardware.org/?probe=87bf7a95c8) | May 21, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0eec4b5bbe](https://linux-hardware.org/?probe=0eec4b5bbe) | May 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4280ce2bd4](https://linux-hardware.org/?probe=4280ce2bd4) | May 15, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [92c052d9b4](https://linux-hardware.org/?probe=92c052d9b4) | May 14, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [bd9eca79bb](https://linux-hardware.org/?probe=bd9eca79bb) | May 13, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [32fba9e487](https://linux-hardware.org/?probe=32fba9e487) | May 09, 2023 |
| Beelink       | BT3 PRO                     | Notebook    | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [dc317ab270](https://linux-hardware.org/?probe=dc317ab270) | May 06, 2023 |
| ASRock        | H370 Pro4                   | Desktop     | [afffccef92](https://linux-hardware.org/?probe=afffccef92) | May 05, 2023 |
| Lenovo        | ThinkPad Edge E530 62723... | Notebook    | [61e998f782](https://linux-hardware.org/?probe=61e998f782) | May 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P WIFI           | Desktop     | [8b4f50125b](https://linux-hardware.org/?probe=8b4f50125b) | May 02, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [ea5b56dbca](https://linux-hardware.org/?probe=ea5b56dbca) | May 01, 2023 |
| HP            | ZBook Firefly 15 inch G8... | Notebook    | [e67706f385](https://linux-hardware.org/?probe=e67706f385) | May 01, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [388b693b6d](https://linux-hardware.org/?probe=388b693b6d) | May 01, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [01c8d89ab9](https://linux-hardware.org/?probe=01c8d89ab9) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [450682b3fc](https://linux-hardware.org/?probe=450682b3fc) | Apr 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5d0819f25c](https://linux-hardware.org/?probe=5d0819f25c) | Apr 28, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [3d73e4cd7e](https://linux-hardware.org/?probe=3d73e4cd7e) | Apr 27, 2023 |
| Dell          | Latitude E4300              | Notebook    | [c61dbb5c53](https://linux-hardware.org/?probe=c61dbb5c53) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | Notebook    | [765b52074c](https://linux-hardware.org/?probe=765b52074c) | Apr 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C8S... | Notebook    | [9cd6c064cc](https://linux-hardware.org/?probe=9cd6c064cc) | Apr 25, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| HP            | 8056                        | Desktop     | [a7686ee1af](https://linux-hardware.org/?probe=a7686ee1af) | Apr 24, 2023 |
| Dell          | Latitude E4300              | Notebook    | [94773cc3da](https://linux-hardware.org/?probe=94773cc3da) | Apr 24, 2023 |
| Dell          | Latitude E4300              | Notebook    | [8bdf03bc75](https://linux-hardware.org/?probe=8bdf03bc75) | Apr 24, 2023 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [78c1951456](https://linux-hardware.org/?probe=78c1951456) | Apr 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [22594512d1](https://linux-hardware.org/?probe=22594512d1) | Apr 23, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [13b6b127e6](https://linux-hardware.org/?probe=13b6b127e6) | Apr 22, 2023 |
| HP            | ProBook 4540s               | Notebook    | [12ee30d786](https://linux-hardware.org/?probe=12ee30d786) | Apr 22, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [4dc6862db9](https://linux-hardware.org/?probe=4dc6862db9) | Apr 21, 2023 |
| ASRock        | Z97X Killer                 | Desktop     | [d258d06b23](https://linux-hardware.org/?probe=d258d06b23) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [7afa5cded3](https://linux-hardware.org/?probe=7afa5cded3) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [3b0ab63643](https://linux-hardware.org/?probe=3b0ab63643) | Apr 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [f05e3341d3](https://linux-hardware.org/?probe=f05e3341d3) | Apr 17, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [fd256ca124](https://linux-hardware.org/?probe=fd256ca124) | Apr 16, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [16ce6e54e0](https://linux-hardware.org/?probe=16ce6e54e0) | Apr 12, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [1f19b2c0dc](https://linux-hardware.org/?probe=1f19b2c0dc) | Apr 11, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [ca9fe9c7f1](https://linux-hardware.org/?probe=ca9fe9c7f1) | Apr 09, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [5bd37d599e](https://linux-hardware.org/?probe=5bd37d599e) | Apr 09, 2023 |
| Dell          | 0F373D A00                  | Desktop     | [e42bdc9769](https://linux-hardware.org/?probe=e42bdc9769) | Apr 09, 2023 |
| ASUSTek       | P5K                         | Desktop     | [ea3489709c](https://linux-hardware.org/?probe=ea3489709c) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [37194169cd](https://linux-hardware.org/?probe=37194169cd) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [2acb260eb1](https://linux-hardware.org/?probe=2acb260eb1) | Apr 07, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [3fdeb525d1](https://linux-hardware.org/?probe=3fdeb525d1) | Apr 06, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [06d1f0e63f](https://linux-hardware.org/?probe=06d1f0e63f) | Apr 06, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [afdf8d46a2](https://linux-hardware.org/?probe=afdf8d46a2) | Apr 05, 2023 |
| HP            | Notebook                    | Notebook    | [935131a649](https://linux-hardware.org/?probe=935131a649) | Apr 04, 2023 |
| HP            | Notebook                    | Notebook    | [f35bee3b90](https://linux-hardware.org/?probe=f35bee3b90) | Apr 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [90b9eaf3fe](https://linux-hardware.org/?probe=90b9eaf3fe) | Apr 02, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [cf9da855fc](https://linux-hardware.org/?probe=cf9da855fc) | Apr 02, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [2b9356529f](https://linux-hardware.org/?probe=2b9356529f) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | Notebook    | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [efc8399ce9](https://linux-hardware.org/?probe=efc8399ce9) | Apr 01, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [88caf7c0d1](https://linux-hardware.org/?probe=88caf7c0d1) | Mar 28, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53cd93c3f5](https://linux-hardware.org/?probe=53cd93c3f5) | Mar 28, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [33608bbcda](https://linux-hardware.org/?probe=33608bbcda) | Mar 27, 2023 |
| HP            | 8954                        | Desktop     | [e7a2f29df5](https://linux-hardware.org/?probe=e7a2f29df5) | Mar 27, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [ec1dd7f3ab](https://linux-hardware.org/?probe=ec1dd7f3ab) | Mar 26, 2023 |
| Lenovo        | ThinkPad T580 20LAS1KA0R    | Notebook    | [db00c2ed37](https://linux-hardware.org/?probe=db00c2ed37) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [7fa1fc4759](https://linux-hardware.org/?probe=7fa1fc4759) | Mar 26, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [cca501adf9](https://linux-hardware.org/?probe=cca501adf9) | Mar 26, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [f5a9d12043](https://linux-hardware.org/?probe=f5a9d12043) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [41289d94bf](https://linux-hardware.org/?probe=41289d94bf) | Mar 25, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [1ccaab03c4](https://linux-hardware.org/?probe=1ccaab03c4) | Mar 25, 2023 |
| Toshiba       | Satellite C850-140          | Notebook    | [6682022c49](https://linux-hardware.org/?probe=6682022c49) | Mar 24, 2023 |
| Gigabyte      | M52S-S3P                    | Desktop     | [c9ac6eb940](https://linux-hardware.org/?probe=c9ac6eb940) | Mar 24, 2023 |
| ASUSTek       | P5KC                        | Desktop     | [3c4c536325](https://linux-hardware.org/?probe=3c4c536325) | Mar 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [9795961bca](https://linux-hardware.org/?probe=9795961bca) | Mar 22, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [821914dc88](https://linux-hardware.org/?probe=821914dc88) | Mar 22, 2023 |
| HP            | Pavilion g6                 | Notebook    | [abd4bb0963](https://linux-hardware.org/?probe=abd4bb0963) | Mar 21, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4dcebf6a41](https://linux-hardware.org/?probe=4dcebf6a41) | Mar 21, 2023 |
| HP            | ProBook 6475b               | Notebook    | [1b7a5f385c](https://linux-hardware.org/?probe=1b7a5f385c) | Mar 18, 2023 |
| HP            | ProBook 6475b               | Notebook    | [0fd12da29b](https://linux-hardware.org/?probe=0fd12da29b) | Mar 18, 2023 |
| HP            | ProBook 6475b               | Notebook    | [701aca7f61](https://linux-hardware.org/?probe=701aca7f61) | Mar 18, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Notebook    | [2a6ded1018](https://linux-hardware.org/?probe=2a6ded1018) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [03123126d0](https://linux-hardware.org/?probe=03123126d0) | Mar 16, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [47df31e0fb](https://linux-hardware.org/?probe=47df31e0fb) | Mar 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [c14956dd2d](https://linux-hardware.org/?probe=c14956dd2d) | Mar 12, 2023 |
| Acer          | Aspire 5333                 | Notebook    | [214db069e4](https://linux-hardware.org/?probe=214db069e4) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [65c2aab8aa](https://linux-hardware.org/?probe=65c2aab8aa) | Mar 11, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [95da35c192](https://linux-hardware.org/?probe=95da35c192) | Mar 11, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | Desktop     | [0d5c00b6fa](https://linux-hardware.org/?probe=0d5c00b6fa) | Mar 11, 2023 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [e03e243c84](https://linux-hardware.org/?probe=e03e243c84) | Mar 11, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Notebook    | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Notebook    | [969ab4279f](https://linux-hardware.org/?probe=969ab4279f) | Mar 10, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | Notebook    | [99e2790846](https://linux-hardware.org/?probe=99e2790846) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [4374107e07](https://linux-hardware.org/?probe=4374107e07) | Mar 10, 2023 |
| HP            | ProBook 6460b               | Notebook    | [7a01d6124d](https://linux-hardware.org/?probe=7a01d6124d) | Mar 10, 2023 |
| Dell          | Latitude E4300              | Notebook    | [3c777f1c07](https://linux-hardware.org/?probe=3c777f1c07) | Mar 10, 2023 |
| HP            | ProBook 6475b               | Notebook    | [be06cdc105](https://linux-hardware.org/?probe=be06cdc105) | Mar 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [42a0b7428f](https://linux-hardware.org/?probe=42a0b7428f) | Mar 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [daefae334b](https://linux-hardware.org/?probe=daefae334b) | Mar 04, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [c803be2765](https://linux-hardware.org/?probe=c803be2765) | Mar 02, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [f4b107fbf3](https://linux-hardware.org/?probe=f4b107fbf3) | Mar 02, 2023 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | Notebook    | [c068117b39](https://linux-hardware.org/?probe=c068117b39) | Mar 01, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [c3d0c5da79](https://linux-hardware.org/?probe=c3d0c5da79) | Mar 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [df09052bac](https://linux-hardware.org/?probe=df09052bac) | Mar 01, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [cbea73a793](https://linux-hardware.org/?probe=cbea73a793) | Feb 27, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [3e9f2feeaa](https://linux-hardware.org/?probe=3e9f2feeaa) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [54e5bda708](https://linux-hardware.org/?probe=54e5bda708) | Feb 26, 2023 |
| HP            | Notebook                    | Notebook    | [ab0dddc914](https://linux-hardware.org/?probe=ab0dddc914) | Feb 26, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [f9cae700c7](https://linux-hardware.org/?probe=f9cae700c7) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [83af08dd1d](https://linux-hardware.org/?probe=83af08dd1d) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c5a45c78fc](https://linux-hardware.org/?probe=c5a45c78fc) | Feb 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [4f7bbbdd28](https://linux-hardware.org/?probe=4f7bbbdd28) | Feb 24, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [69475d0fa7](https://linux-hardware.org/?probe=69475d0fa7) | Feb 23, 2023 |
| Google        | Astronaut                   | Notebook    | [71e8582f54](https://linux-hardware.org/?probe=71e8582f54) | Feb 22, 2023 |
| Google        | Astronaut                   | Notebook    | [4949e50dad](https://linux-hardware.org/?probe=4949e50dad) | Feb 22, 2023 |
| HP            | Notebook                    | Notebook    | [f6d3ba25ba](https://linux-hardware.org/?probe=f6d3ba25ba) | Feb 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [74b6676de3](https://linux-hardware.org/?probe=74b6676de3) | Feb 19, 2023 |
| Dell          | 0NNNCT A01                  | Desktop     | [a301dac224](https://linux-hardware.org/?probe=a301dac224) | Feb 18, 2023 |
| HP            | Notebook                    | Notebook    | [9fe647f9a1](https://linux-hardware.org/?probe=9fe647f9a1) | Feb 15, 2023 |
| HP            | Notebook                    | Notebook    | [c4516fb37a](https://linux-hardware.org/?probe=c4516fb37a) | Feb 15, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5ebabab1c5](https://linux-hardware.org/?probe=5ebabab1c5) | Feb 14, 2023 |
| HP            | ProBook 6460b               | Notebook    | [5436445da0](https://linux-hardware.org/?probe=5436445da0) | Feb 13, 2023 |
| HP            | ProBook 6460b               | Notebook    | [ba14b45543](https://linux-hardware.org/?probe=ba14b45543) | Feb 13, 2023 |
| Valve         | Jupiter                     | Notebook    | [1df562d2d8](https://linux-hardware.org/?probe=1df562d2d8) | Feb 13, 2023 |
| Dell          | Precision M4700             | Notebook    | [6c3746d120](https://linux-hardware.org/?probe=6c3746d120) | Feb 12, 2023 |
| Dell          | Latitude E7470              | Notebook    | [9b58106fd6](https://linux-hardware.org/?probe=9b58106fd6) | Feb 12, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [5afe7ebf87](https://linux-hardware.org/?probe=5afe7ebf87) | Feb 11, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [65ebc31f26](https://linux-hardware.org/?probe=65ebc31f26) | Feb 08, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9f2664ae2a](https://linux-hardware.org/?probe=9f2664ae2a) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ee5a11ee81](https://linux-hardware.org/?probe=ee5a11ee81) | Feb 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5df3b5ad7e](https://linux-hardware.org/?probe=5df3b5ad7e) | Feb 08, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [7e8f09a90e](https://linux-hardware.org/?probe=7e8f09a90e) | Feb 07, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [b3169f788f](https://linux-hardware.org/?probe=b3169f788f) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [e55411b47c](https://linux-hardware.org/?probe=e55411b47c) | Feb 06, 2023 |
| Dell          | Precision M4700             | Notebook    | [c2075893d4](https://linux-hardware.org/?probe=c2075893d4) | Feb 05, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [7037d37121](https://linux-hardware.org/?probe=7037d37121) | Feb 05, 2023 |
| Dell          | 0T10XW A02                  | Desktop     | [10e5f7904a](https://linux-hardware.org/?probe=10e5f7904a) | Feb 02, 2023 |
| Dell          | Precision 5540              | Notebook    | [de6a1c523e](https://linux-hardware.org/?probe=de6a1c523e) | Jan 28, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [eabdd1585c](https://linux-hardware.org/?probe=eabdd1585c) | Jan 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [303593899d](https://linux-hardware.org/?probe=303593899d) | Jan 26, 2023 |
| HP            | Pavilion g6                 | Notebook    | [c34bc63cb0](https://linux-hardware.org/?probe=c34bc63cb0) | Jan 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a9a199e6f7](https://linux-hardware.org/?probe=a9a199e6f7) | Jan 24, 2023 |
| Dell          | 0J3C2F A02                  | Desktop     | [e4b2eae84b](https://linux-hardware.org/?probe=e4b2eae84b) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [e70af512c8](https://linux-hardware.org/?probe=e70af512c8) | Jan 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [e7548596d1](https://linux-hardware.org/?probe=e7548596d1) | Jan 19, 2023 |
| ASRock        | H81M-ITX                    | Desktop     | [036832c7d1](https://linux-hardware.org/?probe=036832c7d1) | Jan 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [ca332b4905](https://linux-hardware.org/?probe=ca332b4905) | Jan 13, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [5ee23ee475](https://linux-hardware.org/?probe=5ee23ee475) | Jan 12, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [ac83d70d3f](https://linux-hardware.org/?probe=ac83d70d3f) | Jan 11, 2023 |
| ASUSTek       | B150-PLUS                   | Desktop     | [30b776e4e8](https://linux-hardware.org/?probe=30b776e4e8) | Jan 11, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | B150-PLUS                   | Desktop     | [7cd86f1bf1](https://linux-hardware.org/?probe=7cd86f1bf1) | Jan 10, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6aa615094c](https://linux-hardware.org/?probe=6aa615094c) | Jan 10, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [183b311eb2](https://linux-hardware.org/?probe=183b311eb2) | Jan 09, 2023 |
| Google        | Kled                        | Notebook    | [6380ae012e](https://linux-hardware.org/?probe=6380ae012e) | Jan 07, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [a03991ee08](https://linux-hardware.org/?probe=a03991ee08) | Jan 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| System76      | Gazelle                     | Notebook    | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| Fujitsu       | D3076-S1 S26361-D3076-S1    | Desktop     | [10b0d01482](https://linux-hardware.org/?probe=10b0d01482) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [1872e26e1c](https://linux-hardware.org/?probe=1872e26e1c) | Jan 04, 2023 |
| Dell          | Precision M6400             | Notebook    | [8f1b979d06](https://linux-hardware.org/?probe=8f1b979d06) | Jan 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [be5212ebcc](https://linux-hardware.org/?probe=be5212ebcc) | Jan 03, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [c87645ef7b](https://linux-hardware.org/?probe=c87645ef7b) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [c51bc128e2](https://linux-hardware.org/?probe=c51bc128e2) | Dec 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [32b2d1e76f](https://linux-hardware.org/?probe=32b2d1e76f) | Dec 26, 2022 |
| Acer          | Aspire A515-47              | Notebook    | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Dell          | Latitude E5410              | Notebook    | [969f85bfc3](https://linux-hardware.org/?probe=969f85bfc3) | Dec 21, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a4aed5865b](https://linux-hardware.org/?probe=a4aed5865b) | Dec 18, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [532dc55c4b](https://linux-hardware.org/?probe=532dc55c4b) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [a560caaec5](https://linux-hardware.org/?probe=a560caaec5) | Dec 17, 2022 |
| Gigabyte      | B460M AORUS PRO             | Desktop     | [6deb38fb48](https://linux-hardware.org/?probe=6deb38fb48) | Dec 17, 2022 |
| Acer          | AO756                       | Notebook    | [ebc4d7cfcb](https://linux-hardware.org/?probe=ebc4d7cfcb) | Dec 16, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [9feb549665](https://linux-hardware.org/?probe=9feb549665) | Dec 15, 2022 |
| Lenovo        | ThinkPad X200s 74695XG      | Notebook    | [9bc0315222](https://linux-hardware.org/?probe=9bc0315222) | Dec 14, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [936608196d](https://linux-hardware.org/?probe=936608196d) | Dec 14, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [6987aeacd5](https://linux-hardware.org/?probe=6987aeacd5) | Dec 13, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [46c656a547](https://linux-hardware.org/?probe=46c656a547) | Dec 13, 2022 |
| Dell          | Precision 5510              | Notebook    | [f464385b16](https://linux-hardware.org/?probe=f464385b16) | Dec 13, 2022 |
| Dell          | Precision 5510              | Notebook    | [f4188b30c9](https://linux-hardware.org/?probe=f4188b30c9) | Dec 13, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [57ab22c9c2](https://linux-hardware.org/?probe=57ab22c9c2) | Dec 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [b3f0bf2008](https://linux-hardware.org/?probe=b3f0bf2008) | Dec 11, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [7ea67f4c69](https://linux-hardware.org/?probe=7ea67f4c69) | Dec 11, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [9158c39614](https://linux-hardware.org/?probe=9158c39614) | Dec 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [ad09795330](https://linux-hardware.org/?probe=ad09795330) | Dec 09, 2022 |
| Acer          | Aspire ES1-731G             | Notebook    | [589cce31c8](https://linux-hardware.org/?probe=589cce31c8) | Dec 09, 2022 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [ff0997b72a](https://linux-hardware.org/?probe=ff0997b72a) | Dec 09, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [aae285b0ea](https://linux-hardware.org/?probe=aae285b0ea) | Dec 09, 2022 |
| HP            | 3047h                       | Desktop     | [223495dbab](https://linux-hardware.org/?probe=223495dbab) | Dec 08, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [01e7f95a23](https://linux-hardware.org/?probe=01e7f95a23) | Dec 07, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [c3b6c86431](https://linux-hardware.org/?probe=c3b6c86431) | Dec 07, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5ff0fd5395](https://linux-hardware.org/?probe=5ff0fd5395) | Dec 06, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [e2ffdfc5a8](https://linux-hardware.org/?probe=e2ffdfc5a8) | Dec 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ccf3e1f074](https://linux-hardware.org/?probe=ccf3e1f074) | Dec 05, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60b1be0a32](https://linux-hardware.org/?probe=60b1be0a32) | Dec 05, 2022 |
| MSI           | X470 GAMING PRO             | Desktop     | [6ca3196f35](https://linux-hardware.org/?probe=6ca3196f35) | Dec 05, 2022 |
| Dell          | Vostro 5620                 | Notebook    | [50acc3b3b8](https://linux-hardware.org/?probe=50acc3b3b8) | Dec 04, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [c79b15a3cf](https://linux-hardware.org/?probe=c79b15a3cf) | Dec 03, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [9da9a87b5b](https://linux-hardware.org/?probe=9da9a87b5b) | Dec 03, 2022 |
| Acer          | Aspire ES1-731G             | Notebook    | [06918f4cc5](https://linux-hardware.org/?probe=06918f4cc5) | Dec 03, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [3e9458fd24](https://linux-hardware.org/?probe=3e9458fd24) | Dec 02, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | Notebook    | [2d4a014ef1](https://linux-hardware.org/?probe=2d4a014ef1) | Dec 01, 2022 |
| Lenovo        | ThinkPad T480S 20L8SBTD0... | Notebook    | [e1cec664eb](https://linux-hardware.org/?probe=e1cec664eb) | Dec 01, 2022 |
| Acer          | AO756                       | Notebook    | [c1ff6fe10c](https://linux-hardware.org/?probe=c1ff6fe10c) | Nov 29, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Dell          | 0J8G6F A03                  | Desktop     | [1424a94eb0](https://linux-hardware.org/?probe=1424a94eb0) | Nov 29, 2022 |
| Acer          | AO756                       | Notebook    | [fa5c9df13a](https://linux-hardware.org/?probe=fa5c9df13a) | Nov 27, 2022 |
| Acer          | AO756                       | Notebook    | [d390d588fe](https://linux-hardware.org/?probe=d390d588fe) | Nov 27, 2022 |
| HP            | 1589                        | Desktop     | [4e67735055](https://linux-hardware.org/?probe=4e67735055) | Nov 27, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [82be349d91](https://linux-hardware.org/?probe=82be349d91) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d480b7ef56](https://linux-hardware.org/?probe=d480b7ef56) | Nov 25, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d3b2f8aaf7](https://linux-hardware.org/?probe=d3b2f8aaf7) | Nov 25, 2022 |
| Dell          | Latitude 5420               | Notebook    | [797ac58b69](https://linux-hardware.org/?probe=797ac58b69) | Nov 23, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [07210e29c5](https://linux-hardware.org/?probe=07210e29c5) | Nov 21, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [210dd0f9f5](https://linux-hardware.org/?probe=210dd0f9f5) | Nov 20, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [faa15c49ae](https://linux-hardware.org/?probe=faa15c49ae) | Nov 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6c5f37f683](https://linux-hardware.org/?probe=6c5f37f683) | Nov 19, 2022 |
| Dell          | Vostro 15 5501              | Notebook    | [ea1dbc4f7c](https://linux-hardware.org/?probe=ea1dbc4f7c) | Nov 18, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [d053fe8efe](https://linux-hardware.org/?probe=d053fe8efe) | Nov 16, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [5468f11c01](https://linux-hardware.org/?probe=5468f11c01) | Nov 15, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2T40... | Notebook    | [f77af97294](https://linux-hardware.org/?probe=f77af97294) | Nov 13, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [b995c794aa](https://linux-hardware.org/?probe=b995c794aa) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [8a5e954190](https://linux-hardware.org/?probe=8a5e954190) | Nov 10, 2022 |
| Dell          | Vostro 5402                 | Notebook    | [cca85a282e](https://linux-hardware.org/?probe=cca85a282e) | Nov 09, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [b1a9ec43d4](https://linux-hardware.org/?probe=b1a9ec43d4) | Nov 07, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [519c833f31](https://linux-hardware.org/?probe=519c833f31) | Nov 06, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f57f494508](https://linux-hardware.org/?probe=f57f494508) | Nov 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [b59f9dcf48](https://linux-hardware.org/?probe=b59f9dcf48) | Nov 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [832ebcb956](https://linux-hardware.org/?probe=832ebcb956) | Nov 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4f5b04e8d9](https://linux-hardware.org/?probe=4f5b04e8d9) | Nov 03, 2022 |
| Dell          | Vostro 1310                 | Notebook    | [0ae18c6c3b](https://linux-hardware.org/?probe=0ae18c6c3b) | Nov 03, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [e941d01470](https://linux-hardware.org/?probe=e941d01470) | Nov 02, 2022 |
| HP            | EliteBook 2730p             | Notebook    | [79830976d8](https://linux-hardware.org/?probe=79830976d8) | Nov 02, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [4e69212184](https://linux-hardware.org/?probe=4e69212184) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook W700GV... | Notebook    | [bf22c22bb4](https://linux-hardware.org/?probe=bf22c22bb4) | Oct 31, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [60ca16eaff](https://linux-hardware.org/?probe=60ca16eaff) | Oct 30, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [ded0ce1d3e](https://linux-hardware.org/?probe=ded0ce1d3e) | Oct 29, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [73f4952d74](https://linux-hardware.org/?probe=73f4952d74) | Oct 29, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [1b3bb91776](https://linux-hardware.org/?probe=1b3bb91776) | Oct 29, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [ced3daa1b6](https://linux-hardware.org/?probe=ced3daa1b6) | Oct 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [81231e9517](https://linux-hardware.org/?probe=81231e9517) | Oct 26, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [79144ee806](https://linux-hardware.org/?probe=79144ee806) | Oct 25, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| HP            | 8061                        | Desktop     | [8692ad745b](https://linux-hardware.org/?probe=8692ad745b) | Oct 19, 2022 |
| Acer          | Aspire 5830T                | Notebook    | [2423f8bf08](https://linux-hardware.org/?probe=2423f8bf08) | Oct 18, 2022 |
| Toshiba       | Satellite L775-125          | Notebook    | [fbe4f1922c](https://linux-hardware.org/?probe=fbe4f1922c) | Oct 18, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [54d2ded2b2](https://linux-hardware.org/?probe=54d2ded2b2) | Oct 17, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fa5c67a5b1](https://linux-hardware.org/?probe=fa5c67a5b1) | Oct 16, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [a17c987ea8](https://linux-hardware.org/?probe=a17c987ea8) | Oct 16, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [17c133e933](https://linux-hardware.org/?probe=17c133e933) | Oct 15, 2022 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [b50165d9c9](https://linux-hardware.org/?probe=b50165d9c9) | Oct 11, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| Dell          | 07N90W A00                  | Desktop     | [1f2485fab4](https://linux-hardware.org/?probe=1f2485fab4) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [866d1ad750](https://linux-hardware.org/?probe=866d1ad750) | Oct 07, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [304c12788b](https://linux-hardware.org/?probe=304c12788b) | Oct 06, 2022 |
| Intel         | D34010WYK H14771-303        | Desktop     | [e58d9849a5](https://linux-hardware.org/?probe=e58d9849a5) | Oct 06, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8f41682975](https://linux-hardware.org/?probe=8f41682975) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| Samsung       | Galaxy TabPro S             | Tablet      | [25deda3e27](https://linux-hardware.org/?probe=25deda3e27) | Oct 02, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [b4b9ca9ae4](https://linux-hardware.org/?probe=b4b9ca9ae4) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [bb2c7c1b05](https://linux-hardware.org/?probe=bb2c7c1b05) | Sep 17, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [a6082da5f7](https://linux-hardware.org/?probe=a6082da5f7) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [889c55b24d](https://linux-hardware.org/?probe=889c55b24d) | Sep 15, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [f9c010c1a9](https://linux-hardware.org/?probe=f9c010c1a9) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [cb134441f2](https://linux-hardware.org/?probe=cb134441f2) | Sep 13, 2022 |
| HP            | 3047h                       | Desktop     | [097b5b2f29](https://linux-hardware.org/?probe=097b5b2f29) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [8afd29a71f](https://linux-hardware.org/?probe=8afd29a71f) | Sep 09, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [611d7b9001](https://linux-hardware.org/?probe=611d7b9001) | Sep 07, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [7479eb6186](https://linux-hardware.org/?probe=7479eb6186) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [00e103f0a0](https://linux-hardware.org/?probe=00e103f0a0) | Sep 05, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3438959476](https://linux-hardware.org/?probe=3438959476) | Sep 05, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [a7708366c2](https://linux-hardware.org/?probe=a7708366c2) | Sep 05, 2022 |
| Lenovo        | ThinkPad P52 20MAS07F04     | Notebook    | [fe662b0bd6](https://linux-hardware.org/?probe=fe662b0bd6) | Sep 03, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Dell          | Latitude E5270              | Notebook    | [d61a2cd74a](https://linux-hardware.org/?probe=d61a2cd74a) | Aug 30, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [3239a22fc0](https://linux-hardware.org/?probe=3239a22fc0) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [e4cdaf6b35](https://linux-hardware.org/?probe=e4cdaf6b35) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7f2e793766](https://linux-hardware.org/?probe=7f2e793766) | Aug 27, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [8aeb1b057b](https://linux-hardware.org/?probe=8aeb1b057b) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f4d9682f50](https://linux-hardware.org/?probe=f4d9682f50) | Aug 27, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [5c8244526c](https://linux-hardware.org/?probe=5c8244526c) | Aug 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [8047eeecb4](https://linux-hardware.org/?probe=8047eeecb4) | Aug 20, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [bd4737dfcf](https://linux-hardware.org/?probe=bd4737dfcf) | Aug 18, 2022 |
| Lenovo        | Unknown                     | Notebook    | [d6a318092b](https://linux-hardware.org/?probe=d6a318092b) | Aug 16, 2022 |
| Lenovo        | Unknown                     | Notebook    | [a8af2e8de4](https://linux-hardware.org/?probe=a8af2e8de4) | Aug 16, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [45ddbf814d](https://linux-hardware.org/?probe=45ddbf814d) | Aug 14, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c92d457cd6](https://linux-hardware.org/?probe=c92d457cd6) | Aug 13, 2022 |
| ASUSTek       | M2VTVM-VM890                | Desktop     | [8a822a57e8](https://linux-hardware.org/?probe=8a822a57e8) | Aug 13, 2022 |
| Toshiba       | PT10F                       | Notebook    | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| Foxconn       | 2A8C                        | Desktop     | [747ba68b28](https://linux-hardware.org/?probe=747ba68b28) | Aug 10, 2022 |
| Apple         | MacBookPro16,4              | Notebook    | [7571d6d783](https://linux-hardware.org/?probe=7571d6d783) | Aug 09, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1b55fc7b56](https://linux-hardware.org/?probe=1b55fc7b56) | Aug 09, 2022 |
| Lenovo        | Unknown                     | Notebook    | [4fe504845e](https://linux-hardware.org/?probe=4fe504845e) | Aug 07, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [616c57c367](https://linux-hardware.org/?probe=616c57c367) | Aug 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [e0129903ae](https://linux-hardware.org/?probe=e0129903ae) | Aug 04, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [7e9c9d2fc4](https://linux-hardware.org/?probe=7e9c9d2fc4) | Jul 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [faf9360275](https://linux-hardware.org/?probe=faf9360275) | Jul 26, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f00c831f5b](https://linux-hardware.org/?probe=f00c831f5b) | Jul 25, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [58f727d948](https://linux-hardware.org/?probe=58f727d948) | Jul 25, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1449b21f55](https://linux-hardware.org/?probe=1449b21f55) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [3e14a0baf3](https://linux-hardware.org/?probe=3e14a0baf3) | Jul 22, 2022 |
| HP            | 1495                        | Desktop     | [1706c61a6c](https://linux-hardware.org/?probe=1706c61a6c) | Jul 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9c98b2fcd6](https://linux-hardware.org/?probe=9c98b2fcd6) | Jul 21, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f42ed5053a](https://linux-hardware.org/?probe=f42ed5053a) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Thecus        | N2810 0001                  | Desktop     | [dd4d9fb1d5](https://linux-hardware.org/?probe=dd4d9fb1d5) | Jul 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [3dddb3aac3](https://linux-hardware.org/?probe=3dddb3aac3) | Jul 20, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [c88ac89032](https://linux-hardware.org/?probe=c88ac89032) | Jul 20, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [69bd504820](https://linux-hardware.org/?probe=69bd504820) | Jul 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [4b2f1f5d39](https://linux-hardware.org/?probe=4b2f1f5d39) | Jul 16, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | Notebook    | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [4245ef07db](https://linux-hardware.org/?probe=4245ef07db) | Jul 10, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [1dafd7beed](https://linux-hardware.org/?probe=1dafd7beed) | Jul 09, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [25c94a11f7](https://linux-hardware.org/?probe=25c94a11f7) | Jul 08, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [5ac5b5f182](https://linux-hardware.org/?probe=5ac5b5f182) | Jul 06, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [292aa38957](https://linux-hardware.org/?probe=292aa38957) | Jul 05, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [4df74c5b84](https://linux-hardware.org/?probe=4df74c5b84) | Jul 05, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [426bb60e88](https://linux-hardware.org/?probe=426bb60e88) | Jul 04, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [5de569a33e](https://linux-hardware.org/?probe=5de569a33e) | Jun 29, 2022 |
| ASRock        | N68-S                       | Desktop     | [cf9108c19a](https://linux-hardware.org/?probe=cf9108c19a) | Jun 28, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [6542ea7dff](https://linux-hardware.org/?probe=6542ea7dff) | Jun 27, 2022 |
| ASRock        | 890GM Pro3 R2.0             | Desktop     | [4b7b86cf21](https://linux-hardware.org/?probe=4b7b86cf21) | Jun 27, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [dfab1b501e](https://linux-hardware.org/?probe=dfab1b501e) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [3cbcb5e5d5](https://linux-hardware.org/?probe=3cbcb5e5d5) | Jun 26, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [d93da606dc](https://linux-hardware.org/?probe=d93da606dc) | Jun 26, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e4aeec08da](https://linux-hardware.org/?probe=e4aeec08da) | Jun 25, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [00089c4dbe](https://linux-hardware.org/?probe=00089c4dbe) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [868525a45e](https://linux-hardware.org/?probe=868525a45e) | Jun 25, 2022 |
| Acer          | Aspire 5736Z                | Notebook    | [ba78e0dde2](https://linux-hardware.org/?probe=ba78e0dde2) | Jun 24, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [22c8672cea](https://linux-hardware.org/?probe=22c8672cea) | Jun 23, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [673bd13d0a](https://linux-hardware.org/?probe=673bd13d0a) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [2c0dd875b3](https://linux-hardware.org/?probe=2c0dd875b3) | Jun 21, 2022 |
| HP            | ProLiant ML350 G5           | Desktop     | [57a6a7a493](https://linux-hardware.org/?probe=57a6a7a493) | Jun 20, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [fd83a38364](https://linux-hardware.org/?probe=fd83a38364) | Jun 15, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [489dd3049e](https://linux-hardware.org/?probe=489dd3049e) | Jun 13, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [34d266accd](https://linux-hardware.org/?probe=34d266accd) | Jun 12, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [c7243df0c6](https://linux-hardware.org/?probe=c7243df0c6) | Jun 12, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [a93743e1a0](https://linux-hardware.org/?probe=a93743e1a0) | Jun 11, 2022 |
| HP            | 872D                        | Desktop     | [c27f333c46](https://linux-hardware.org/?probe=c27f333c46) | Jun 08, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Acer          | Aspire A315-32              | Notebook    | [124288f4e9](https://linux-hardware.org/?probe=124288f4e9) | Jun 05, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [b3399223ef](https://linux-hardware.org/?probe=b3399223ef) | Jun 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [630b63edff](https://linux-hardware.org/?probe=630b63edff) | Jun 02, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [ac99467383](https://linux-hardware.org/?probe=ac99467383) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [164d02e437](https://linux-hardware.org/?probe=164d02e437) | Jun 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [e0d6b45da8](https://linux-hardware.org/?probe=e0d6b45da8) | May 31, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [ce6b717155](https://linux-hardware.org/?probe=ce6b717155) | May 30, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [0086280448](https://linux-hardware.org/?probe=0086280448) | May 28, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [a434348da9](https://linux-hardware.org/?probe=a434348da9) | May 26, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4dabec8399](https://linux-hardware.org/?probe=4dabec8399) | May 26, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [24b9b9fc85](https://linux-hardware.org/?probe=24b9b9fc85) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [7d581f520f](https://linux-hardware.org/?probe=7d581f520f) | May 25, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [6be38c26b4](https://linux-hardware.org/?probe=6be38c26b4) | May 25, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [c941dc302f](https://linux-hardware.org/?probe=c941dc302f) | May 23, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [596b029521](https://linux-hardware.org/?probe=596b029521) | May 21, 2022 |
| HP            | Compaq 6735s                | Notebook    | [bcd9db6031](https://linux-hardware.org/?probe=bcd9db6031) | May 20, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [7c8ef0ae32](https://linux-hardware.org/?probe=7c8ef0ae32) | May 18, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [21b3b45491](https://linux-hardware.org/?probe=21b3b45491) | May 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [81e0a19eaa](https://linux-hardware.org/?probe=81e0a19eaa) | May 16, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [7de7df5240](https://linux-hardware.org/?probe=7de7df5240) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [99976087b6](https://linux-hardware.org/?probe=99976087b6) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [8eff9fb0c8](https://linux-hardware.org/?probe=8eff9fb0c8) | May 15, 2022 |
| Toshiba       | Satellite L50-A-115         | Notebook    | [186b630cd2](https://linux-hardware.org/?probe=186b630cd2) | May 15, 2022 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [09912cea2f](https://linux-hardware.org/?probe=09912cea2f) | May 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e7fcde8001](https://linux-hardware.org/?probe=e7fcde8001) | May 14, 2022 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [ea492e2997](https://linux-hardware.org/?probe=ea492e2997) | May 13, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [25654025a8](https://linux-hardware.org/?probe=25654025a8) | May 13, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [1dcd852fff](https://linux-hardware.org/?probe=1dcd852fff) | May 12, 2022 |
| Pegatron      | 2A99h                       | Desktop     | [6a47713af6](https://linux-hardware.org/?probe=6a47713af6) | May 12, 2022 |
| Acer          | Predator G3-605             | Desktop     | [fb7a7e74d1](https://linux-hardware.org/?probe=fb7a7e74d1) | May 11, 2022 |
| Gigabyte      | H97N                        | Desktop     | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [ff7adfb82a](https://linux-hardware.org/?probe=ff7adfb82a) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [c40273d0bc](https://linux-hardware.org/?probe=c40273d0bc) | Apr 29, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [58539bbf0a](https://linux-hardware.org/?probe=58539bbf0a) | Apr 29, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ab21675303](https://linux-hardware.org/?probe=ab21675303) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| MSI           | PRO B660-A DDR4             | Desktop     | [ec79dfd8b1](https://linux-hardware.org/?probe=ec79dfd8b1) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | Notebook    | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [86aeb14193](https://linux-hardware.org/?probe=86aeb14193) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| Dell          | Precision M6800             | Notebook    | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [33d09ef3fd](https://linux-hardware.org/?probe=33d09ef3fd) | Apr 15, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [fc67b2d51e](https://linux-hardware.org/?probe=fc67b2d51e) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [071753c493](https://linux-hardware.org/?probe=071753c493) | Mar 31, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5215972642](https://linux-hardware.org/?probe=5215972642) | Mar 31, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [4153c10d0b](https://linux-hardware.org/?probe=4153c10d0b) | Mar 31, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | Notebook    | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| Toshiba       | Satellite C855-2G8          | Notebook    | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [19fbf78cc0](https://linux-hardware.org/?probe=19fbf78cc0) | Mar 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [38c8508bc0](https://linux-hardware.org/?probe=38c8508bc0) | Mar 10, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [82005c3638](https://linux-hardware.org/?probe=82005c3638) | Mar 08, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [441febf3e4](https://linux-hardware.org/?probe=441febf3e4) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | Notebook    | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [5914978461](https://linux-hardware.org/?probe=5914978461) | Mar 04, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [e604cd4180](https://linux-hardware.org/?probe=e604cd4180) | Mar 03, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [50e3ff9809](https://linux-hardware.org/?probe=50e3ff9809) | Mar 03, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [43f47c3d8e](https://linux-hardware.org/?probe=43f47c3d8e) | Feb 28, 2022 |
| ASUSTek       | N551VW                      | Notebook    | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [fb6d74d159](https://linux-hardware.org/?probe=fb6d74d159) | Feb 21, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [dc3262a408](https://linux-hardware.org/?probe=dc3262a408) | Feb 20, 2022 |
| Dell          | Inspiron 1011               | Notebook    | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [d12f767e54](https://linux-hardware.org/?probe=d12f767e54) | Feb 19, 2022 |
| Lenovo        | ThinkCentre M58p 6234A1G    | Desktop     | [1cbf260df6](https://linux-hardware.org/?probe=1cbf260df6) | Feb 18, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [61c7fe5dfd](https://linux-hardware.org/?probe=61c7fe5dfd) | Feb 18, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [2024310fec](https://linux-hardware.org/?probe=2024310fec) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [afe18260fc](https://linux-hardware.org/?probe=afe18260fc) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c38638517e](https://linux-hardware.org/?probe=c38638517e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [64b2c75dae](https://linux-hardware.org/?probe=64b2c75dae) | Feb 16, 2022 |
| HP            | Pavilion 15                 | Notebook    | [191168c7ae](https://linux-hardware.org/?probe=191168c7ae) | Feb 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [88a943ec80](https://linux-hardware.org/?probe=88a943ec80) | Feb 16, 2022 |
| Dell          | Latitude E6330              | Notebook    | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | Pavilion dm1                | Notebook    | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| Dell          | Inspiron 5482               | Convertible | [17584ae0e4](https://linux-hardware.org/?probe=17584ae0e4) | Feb 12, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a032ab36a8](https://linux-hardware.org/?probe=a032ab36a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0ec31586a1](https://linux-hardware.org/?probe=0ec31586a1) | Feb 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [72991a7822](https://linux-hardware.org/?probe=72991a7822) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V                    | Desktop     | [d00c78fd08](https://linux-hardware.org/?probe=d00c78fd08) | Feb 08, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [e4acc07d44](https://linux-hardware.org/?probe=e4acc07d44) | Feb 06, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [788939c01d](https://linux-hardware.org/?probe=788939c01d) | Feb 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [4f7256df40](https://linux-hardware.org/?probe=4f7256df40) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [2d5857b9ff](https://linux-hardware.org/?probe=2d5857b9ff) | Jan 27, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Intel         | X99                         | Desktop     | [f4a0c1aaaa](https://linux-hardware.org/?probe=f4a0c1aaaa) | Jan 20, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [821f3261c2](https://linux-hardware.org/?probe=821f3261c2) | Jan 18, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [71cab3efa8](https://linux-hardware.org/?probe=71cab3efa8) | Jan 18, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [83ddee52ce](https://linux-hardware.org/?probe=83ddee52ce) | Jan 14, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [d027268e2b](https://linux-hardware.org/?probe=d027268e2b) | Jan 14, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [a9ed1157c0](https://linux-hardware.org/?probe=a9ed1157c0) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [3467478289](https://linux-hardware.org/?probe=3467478289) | Jan 13, 2022 |
| Dell          | Latitude E4300              | Notebook    | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [f23503b603](https://linux-hardware.org/?probe=f23503b603) | Jan 10, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [881a1adf4c](https://linux-hardware.org/?probe=881a1adf4c) | Jan 07, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [8520c449b6](https://linux-hardware.org/?probe=8520c449b6) | Jan 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ca928a7784](https://linux-hardware.org/?probe=ca928a7784) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | Notebook    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [7add8fadfa](https://linux-hardware.org/?probe=7add8fadfa) | Jan 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e8cfb51ca5](https://linux-hardware.org/?probe=e8cfb51ca5) | Jan 04, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| HP            | 3397                        | Desktop     | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | Notebook    | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [50045a522a](https://linux-hardware.org/?probe=50045a522a) | Dec 30, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| ASUSTek       | P5E                         | Desktop     | [1d3ece3005](https://linux-hardware.org/?probe=1d3ece3005) | Dec 29, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | Notebook    | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [19959c7845](https://linux-hardware.org/?probe=19959c7845) | Dec 26, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | Notebook    | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8ff289917](https://linux-hardware.org/?probe=b8ff289917) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [ae120235f1](https://linux-hardware.org/?probe=ae120235f1) | Dec 21, 2021 |
| Toshiba       | Equium A60                  | Notebook    | [206f662171](https://linux-hardware.org/?probe=206f662171) | Dec 20, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [f67c56ba50](https://linux-hardware.org/?probe=f67c56ba50) | Dec 18, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [65ec484cf7](https://linux-hardware.org/?probe=65ec484cf7) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ab70f6516f](https://linux-hardware.org/?probe=ab70f6516f) | Dec 16, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [785650303f](https://linux-hardware.org/?probe=785650303f) | Dec 13, 2021 |
| HP            | ProBook 4540s               | Notebook    | [da7b06db3f](https://linux-hardware.org/?probe=da7b06db3f) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2f607ba3fb](https://linux-hardware.org/?probe=2f607ba3fb) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5ef3ccbbd8](https://linux-hardware.org/?probe=5ef3ccbbd8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [03ba9fdf17](https://linux-hardware.org/?probe=03ba9fdf17) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6424339164](https://linux-hardware.org/?probe=6424339164) | Dec 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [a5c3366e73](https://linux-hardware.org/?probe=a5c3366e73) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Dell          | Vostro 1014                 | Notebook    | [d1be779708](https://linux-hardware.org/?probe=d1be779708) | Dec 08, 2021 |
| Dell          | Latitude 5520               | Notebook    | [4609e387e3](https://linux-hardware.org/?probe=4609e387e3) | Dec 07, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [5dde6ac6a6](https://linux-hardware.org/?probe=5dde6ac6a6) | Dec 05, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [7530a42730](https://linux-hardware.org/?probe=7530a42730) | Dec 03, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [5774bcc229](https://linux-hardware.org/?probe=5774bcc229) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | Notebook    | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f0dbaf192c](https://linux-hardware.org/?probe=f0dbaf192c) | Nov 25, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f0c1e81fb5](https://linux-hardware.org/?probe=f0c1e81fb5) | Nov 25, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0e34595bcc](https://linux-hardware.org/?probe=0e34595bcc) | Nov 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [e2de67ba78](https://linux-hardware.org/?probe=e2de67ba78) | Nov 23, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [bd12b5a969](https://linux-hardware.org/?probe=bd12b5a969) | Nov 21, 2021 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [de3fb571bb](https://linux-hardware.org/?probe=de3fb571bb) | Nov 20, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [dfc2c68c8d](https://linux-hardware.org/?probe=dfc2c68c8d) | Nov 19, 2021 |
| Acer          | Predator G3-605             | Desktop     | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| Dell          | Latitude E6430              | Notebook    | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [ad46c0b68f](https://linux-hardware.org/?probe=ad46c0b68f) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2aa779c174](https://linux-hardware.org/?probe=2aa779c174) | Nov 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [a6509cbba9](https://linux-hardware.org/?probe=a6509cbba9) | Nov 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| Acer          | Aspire A315-35              | Notebook    | [4ac11dfcbe](https://linux-hardware.org/?probe=4ac11dfcbe) | Nov 03, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [1c57a8d14c](https://linux-hardware.org/?probe=1c57a8d14c) | Nov 02, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [66255ca7b5](https://linux-hardware.org/?probe=66255ca7b5) | Oct 30, 2021 |
| ASUSTek       | N551VW                      | Notebook    | [5d4bce82bd](https://linux-hardware.org/?probe=5d4bce82bd) | Oct 30, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8cae94b7f8](https://linux-hardware.org/?probe=8cae94b7f8) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a92566ee89](https://linux-hardware.org/?probe=a92566ee89) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6d4dad5754](https://linux-hardware.org/?probe=6d4dad5754) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [82c79fb7be](https://linux-hardware.org/?probe=82c79fb7be) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3ab004eed4](https://linux-hardware.org/?probe=3ab004eed4) | Oct 17, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| ASRock        | H81M-HDS                    | Desktop     | [300c7e725d](https://linux-hardware.org/?probe=300c7e725d) | Oct 10, 2021 |
| HP            | Pavilion dv7                | Notebook    | [dfccb89900](https://linux-hardware.org/?probe=dfccb89900) | Oct 09, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [637dbbacba](https://linux-hardware.org/?probe=637dbbacba) | Oct 08, 2021 |
| Acer          | Aspire A515-52G             | Notebook    | [bb5c8d6628](https://linux-hardware.org/?probe=bb5c8d6628) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [6b1e235a76](https://linux-hardware.org/?probe=6b1e235a76) | Sep 28, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1121eb673b](https://linux-hardware.org/?probe=1121eb673b) | Sep 27, 2021 |
| Acer          | Extensa 5630                | Notebook    | [3bb0bc9c4d](https://linux-hardware.org/?probe=3bb0bc9c4d) | Sep 25, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b6a9870be5](https://linux-hardware.org/?probe=b6a9870be5) | Sep 22, 2021 |
| Lenovo        | IdeaPad Creator 5 16ACH6... | Notebook    | [7251798837](https://linux-hardware.org/?probe=7251798837) | Sep 20, 2021 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | Notebook    | [e6cd50fc3c](https://linux-hardware.org/?probe=e6cd50fc3c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | Notebook    | [7854f1ed77](https://linux-hardware.org/?probe=7854f1ed77) | Sep 18, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [3be61fa185](https://linux-hardware.org/?probe=3be61fa185) | Sep 11, 2021 |
| Lenovo        | ThinkStation D20 4158E93    | Desktop     | [fde770f309](https://linux-hardware.org/?probe=fde770f309) | Sep 11, 2021 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [59ce224e2b](https://linux-hardware.org/?probe=59ce224e2b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [dce0b57cdc](https://linux-hardware.org/?probe=dce0b57cdc) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [d54f16f7e3](https://linux-hardware.org/?probe=d54f16f7e3) | Sep 07, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [a95e304baf](https://linux-hardware.org/?probe=a95e304baf) | Sep 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [a37b749b27](https://linux-hardware.org/?probe=a37b749b27) | Sep 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [92e21fb915](https://linux-hardware.org/?probe=92e21fb915) | Sep 06, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | Notebook    | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [7c76ac10d8](https://linux-hardware.org/?probe=7c76ac10d8) | Sep 04, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [d831e8693d](https://linux-hardware.org/?probe=d831e8693d) | Sep 04, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [9300181bad](https://linux-hardware.org/?probe=9300181bad) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [ce4010bf4f](https://linux-hardware.org/?probe=ce4010bf4f) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [afa0ef75a7](https://linux-hardware.org/?probe=afa0ef75a7) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [2f2e0ec5bf](https://linux-hardware.org/?probe=2f2e0ec5bf) | Aug 31, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [7d634f76ad](https://linux-hardware.org/?probe=7d634f76ad) | Aug 31, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [9eb666fd13](https://linux-hardware.org/?probe=9eb666fd13) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [8a976ca31c](https://linux-hardware.org/?probe=8a976ca31c) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [8f10e30326](https://linux-hardware.org/?probe=8f10e30326) | Aug 28, 2021 |
| HP            | 18E4                        | Desktop     | [81c51891c9](https://linux-hardware.org/?probe=81c51891c9) | Aug 27, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1df5582ca4](https://linux-hardware.org/?probe=1df5582ca4) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8461b48819](https://linux-hardware.org/?probe=8461b48819) | Aug 19, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [257e2c9dd4](https://linux-hardware.org/?probe=257e2c9dd4) | Aug 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [59f5bb4379](https://linux-hardware.org/?probe=59f5bb4379) | Aug 18, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3bfb2e6910](https://linux-hardware.org/?probe=3bfb2e6910) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [f7de5020c6](https://linux-hardware.org/?probe=f7de5020c6) | Aug 16, 2021 |
| MSI           | A68HM-P33 V2                | Desktop     | [4c3bedddac](https://linux-hardware.org/?probe=4c3bedddac) | Aug 14, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [bb46750dfa](https://linux-hardware.org/?probe=bb46750dfa) | Aug 12, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [4fce5e2d88](https://linux-hardware.org/?probe=4fce5e2d88) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [ef7f570d01](https://linux-hardware.org/?probe=ef7f570d01) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [0c191944fc](https://linux-hardware.org/?probe=0c191944fc) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [a08f9bd38d](https://linux-hardware.org/?probe=a08f9bd38d) | Aug 02, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [d4bc0c2e33](https://linux-hardware.org/?probe=d4bc0c2e33) | Jul 30, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [f015614a5c](https://linux-hardware.org/?probe=f015614a5c) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [93b4e5b92a](https://linux-hardware.org/?probe=93b4e5b92a) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Acer          | Aspire A717-72G             | Notebook    | [1d1f8cb836](https://linux-hardware.org/?probe=1d1f8cb836) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| HP            | ProBook 6450b               | Notebook    | [557056dd22](https://linux-hardware.org/?probe=557056dd22) | Jul 24, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [6c5a4659b1](https://linux-hardware.org/?probe=6c5a4659b1) | Jul 23, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [67512f199f](https://linux-hardware.org/?probe=67512f199f) | Jul 23, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [712382158a](https://linux-hardware.org/?probe=712382158a) | Jul 23, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [b39264f1fa](https://linux-hardware.org/?probe=b39264f1fa) | Jul 22, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [6e77984276](https://linux-hardware.org/?probe=6e77984276) | Jul 20, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [5d62f330ba](https://linux-hardware.org/?probe=5d62f330ba) | Jul 18, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [a26a16fb20](https://linux-hardware.org/?probe=a26a16fb20) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [c18e377104](https://linux-hardware.org/?probe=c18e377104) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [baf3a7a407](https://linux-hardware.org/?probe=baf3a7a407) | Jul 16, 2021 |
| HP            | ProBook 6450b               | Notebook    | [f596a27975](https://linux-hardware.org/?probe=f596a27975) | Jul 16, 2021 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [d3f2c6d8d8](https://linux-hardware.org/?probe=d3f2c6d8d8) | Jul 13, 2021 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [5ce964530d](https://linux-hardware.org/?probe=5ce964530d) | Jul 13, 2021 |
| Acer          | Predator G9-792             | Notebook    | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| HP            | ProBook 6450b               | Notebook    | [d9d8115d98](https://linux-hardware.org/?probe=d9d8115d98) | Jul 11, 2021 |
| HP            | ProBook 6450b               | Notebook    | [c3bdfd8206](https://linux-hardware.org/?probe=c3bdfd8206) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad P52 20MAS07F04     | Notebook    | [4d35b037dd](https://linux-hardware.org/?probe=4d35b037dd) | Jul 04, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | Notebook    | [d3b33778bb](https://linux-hardware.org/?probe=d3b33778bb) | Jul 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | Notebook    | [3c45c3cf29](https://linux-hardware.org/?probe=3c45c3cf29) | Jul 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [13af782a58](https://linux-hardware.org/?probe=13af782a58) | Jun 29, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Bulgaria/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 117       | 9.32%   |
| Ubuntu 18.04                 | 80        | 6.37%   |
| Ubuntu 22.04                 | 75        | 5.98%   |
| Debian 11                    | 36        | 2.87%   |
| OpenMandriva 4.2             | 29        | 2.31%   |
| Manjaro                      | 23        | 1.83%   |
| OpenMandriva 4.3             | 22        | 1.75%   |
| Fedora 38                    | 21        | 1.67%   |
| Arch Rolling                 | 21        | 1.67%   |
| ROSA R11                     | 18        | 1.43%   |
| Pop!_OS 22.04                | 18        | 1.43%   |
| openSUSE Tumbleweed-XXXXXXXX | 18        | 1.43%   |
| ArcoLinux Rolling            | 18        | 1.43%   |
| Linux Mint 20.1              | 17        | 1.35%   |
| KDE neon 20.04               | 17        | 1.35%   |
| Zorin 16                     | 16        | 1.27%   |
| ROSA R10                     | 16        | 1.27%   |
| Arch                         | 16        | 1.27%   |
| Ubuntu 22.10                 | 15        | 1.2%    |
| Linux Mint 20.3              | 15        | 1.2%    |
| Linux Mint 19.3              | 14        | 1.12%   |
| Ubuntu 19.04                 | 13        | 1.04%   |
| Linux Mint 21.1              | 13        | 1.04%   |
| Linux Mint 20.2              | 13        | 1.04%   |
| Linux Mint 20                | 13        | 1.04%   |
| Kubuntu 20.04                | 13        | 1.04%   |
| Zorin 15                     | 12        | 0.96%   |
| Xubuntu 18.04                | 12        | 0.96%   |
| OpenMandriva 23.03           | 12        | 0.96%   |
| Ubuntu 19.10                 | 11        | 0.88%   |
| Linux Mint 21.2              | 11        | 0.88%   |
| Xubuntu 20.04                | 10        | 0.8%    |
| Ubuntu 20.10                 | 10        | 0.8%    |
| Pop!_OS 20.10                | 10        | 0.8%    |
| OpenMandriva 23.08           | 10        | 0.8%    |
| Fedora 33                    | 10        | 0.8%    |
| LMDE 4                       | 9         | 0.72%   |
| Kubuntu 22.04                | 9         | 0.72%   |
| Fedora 39                    | 9         | 0.72%   |
| Ubuntu 23.04                 | 8         | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 336       | 29.34%  |
| Linux Mint    | 97        | 8.47%   |
| OpenMandriva  | 83        | 7.25%   |
| Fedora        | 68        | 5.94%   |
| Debian        | 54        | 4.72%   |
| Manjaro       | 52        | 4.54%   |
| ROSA          | 51        | 4.45%   |
| Pop!_OS       | 46        | 4.02%   |
| Arch          | 35        | 3.06%   |
| Zorin         | 29        | 2.53%   |
| Endless       | 28        | 2.45%   |
| Xubuntu       | 27        | 2.36%   |
| Kubuntu       | 27        | 2.36%   |
| KDE neon      | 27        | 2.36%   |
| openSUSE      | 23        | 2.01%   |
| ArcoLinux     | 20        | 1.75%   |
| Kali          | 18        | 1.57%   |
| Ubuntu Unity  | 12        | 1.05%   |
| Clear Linux   | 12        | 1.05%   |
| LMDE          | 9         | 0.79%   |
| CentOS        | 8         | 0.7%    |
| Lubuntu       | 7         | 0.61%   |
| Gentoo        | 6         | 0.52%   |
| Elementary    | 6         | 0.52%   |
| EndeavourOS   | 5         | 0.44%   |
| Artix         | 5         | 0.44%   |
| Ubuntu MATE   | 4         | 0.35%   |
| SteamOS       | 4         | 0.35%   |
| Void Linux    | 3         | 0.26%   |
| Parrot        | 3         | 0.26%   |
| MX            | 3         | 0.26%   |
| Xero          | 2         | 0.17%   |
| Ubuntu Studio | 2         | 0.17%   |
| Ubuntu Budgie | 2         | 0.17%   |
| Novos         | 2         | 0.17%   |
| NixOS         | 2         | 0.17%   |
| Mageia        | 2         | 0.17%   |
| Deepin        | 2         | 0.17%   |
| BunsenLabs    | 2         | 0.17%   |
| TUXEDO OS     | 1         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 29        | 2.1%    |
| 5.16.7-desktop-1omv4003         | 21        | 1.52%   |
| 5.4.0-42-generic                | 17        | 1.23%   |
| 5.4.0-58-generic                | 13        | 0.94%   |
| 5.15.0-56-generic               | 13        | 0.94%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 13        | 0.94%   |
| 6.2.6-desktop-1omv2390          | 11        | 0.8%    |
| 5.3.0-40-generic                | 10        | 0.72%   |
| 5.9.16-1-MANJARO                | 8         | 0.58%   |
| 5.4.0-26-generic                | 8         | 0.58%   |
| 6.4.11-desktop-1omv2390         | 7         | 0.51%   |
| 6.2.0-39-generic                | 7         | 0.51%   |
| 5.4.0-48-generic                | 7         | 0.51%   |
| 5.4.0-29-generic                | 7         | 0.51%   |
| 5.3.0-28-generic                | 7         | 0.51%   |
| 5.10.0-8-amd64                  | 7         | 0.51%   |
| 5.0.0-37-generic                | 7         | 0.51%   |
| 6.2.6-76060206-generic          | 6         | 0.43%   |
| 6.2.0-26-generic                | 6         | 0.43%   |
| 5.8.0-14-generic                | 6         | 0.43%   |
| 5.4.0-65-generic                | 6         | 0.43%   |
| 5.4.0-56-generic                | 6         | 0.43%   |
| 5.4.0-40-generic                | 6         | 0.43%   |
| 5.3.0-46-generic                | 6         | 0.43%   |
| 5.3.0-42-generic                | 6         | 0.43%   |
| 5.11.0-37-generic               | 6         | 0.43%   |
| 5.11.0-27-generic               | 6         | 0.43%   |
| 5.0.0-23-generic                | 6         | 0.43%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 6         | 0.43%   |
| 4.15.0-20-generic               | 6         | 0.43%   |
| 6.5.0-14-generic                | 5         | 0.36%   |
| 6.1.1-desktop-1omv2290          | 5         | 0.36%   |
| 5.8.0-7642-generic              | 5         | 0.36%   |
| 5.8.0-43-generic                | 5         | 0.36%   |
| 5.4.0-91-generic                | 5         | 0.36%   |
| 5.4.0-90-generic                | 5         | 0.36%   |
| 5.4.0-77-generic                | 5         | 0.36%   |
| 5.4.0-67-generic                | 5         | 0.36%   |
| 5.4.0-19-generic                | 5         | 0.36%   |
| 5.19.0-35-generic               | 5         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 170       | 12.99%  |
| 5.15.0  | 100       | 7.64%   |
| 4.15.0  | 80        | 6.11%   |
| 5.8.0   | 54        | 4.13%   |
| 5.3.0   | 49        | 3.74%   |
| 6.2.0   | 40        | 3.06%   |
| 5.11.0  | 40        | 3.06%   |
| 5.19.0  | 38        | 2.9%    |
| 5.10.0  | 38        | 2.9%    |
| 5.13.0  | 37        | 2.83%   |
| 5.0.0   | 37        | 2.83%   |
| 5.10.14 | 30        | 2.29%   |
| 4.18.0  | 23        | 1.76%   |
| 5.16.7  | 21        | 1.6%    |
| 6.2.6   | 18        | 1.38%   |
| 6.5.0   | 15        | 1.15%   |
| 6.1.0   | 13        | 0.99%   |
| 4.19.0  | 13        | 0.99%   |
| 5.9.16  | 11        | 0.84%   |
| 4.9.20  | 9         | 0.69%   |
| 6.4.11  | 8         | 0.61%   |
| 6.1.1   | 8         | 0.61%   |
| 5.17.5  | 8         | 0.61%   |
| 5.14.0  | 7         | 0.53%   |
| 6.6.8   | 6         | 0.46%   |
| 6.0.0   | 6         | 0.46%   |
| 5.18.0  | 6         | 0.46%   |
| 4.9.60  | 6         | 0.46%   |
| 4.4.0   | 6         | 0.46%   |
| 6.5.5   | 5         | 0.38%   |
| 6.2.9   | 5         | 0.38%   |
| 5.8.18  | 5         | 0.38%   |
| 4.9.124 | 5         | 0.38%   |
| 6.5.7   | 4         | 0.31%   |
| 6.4.8   | 4         | 0.31%   |
| 6.0.12  | 4         | 0.31%   |
| 5.8.11  | 4         | 0.31%   |
| 5.6.8   | 4         | 0.31%   |
| 5.6.0   | 4         | 0.31%   |
| 5.16.0  | 4         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 180       | 14.06%  |
| 5.15    | 132       | 10.31%  |
| 5.10    | 95        | 7.42%   |
| 4.15    | 80        | 6.25%   |
| 6.2     | 75        | 5.86%   |
| 5.8     | 67        | 5.23%   |
| 5.3     | 58        | 4.53%   |
| 5.11    | 52        | 4.06%   |
| 5.19    | 47        | 3.67%   |
| 5.13    | 43        | 3.36%   |
| 6.1     | 40        | 3.13%   |
| 5.16    | 40        | 3.13%   |
| 5.0     | 40        | 3.13%   |
| 6.5     | 37        | 2.89%   |
| 6.4     | 26        | 2.03%   |
| 4.9     | 26        | 2.03%   |
| 4.18    | 24        | 1.88%   |
| 6.6     | 23        | 1.8%    |
| 5.17    | 20        | 1.56%   |
| 6.0     | 18        | 1.41%   |
| 4.19    | 18        | 1.41%   |
| 5.9     | 17        | 1.33%   |
| 5.14    | 17        | 1.33%   |
| 5.6     | 16        | 1.25%   |
| 6.3     | 14        | 1.09%   |
| 5.18    | 13        | 1.02%   |
| 5.7     | 12        | 0.94%   |
| 5.12    | 12        | 0.94%   |
| 5.5     | 7         | 0.55%   |
| 4.4     | 6         | 0.47%   |
| 5.2     | 5         | 0.39%   |
| 4.1     | 4         | 0.31%   |
| 6.7     | 3         | 0.23%   |
| 5.1     | 3         | 0.23%   |
| 3.10    | 3         | 0.23%   |
| 6.8     | 1         | 0.08%   |
| 4.7     | 1         | 0.08%   |
| 4.20    | 1         | 0.08%   |
| 4.13    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1068      | 97.09%  |
| i686    | 30        | 2.73%   |
| aarch64 | 2         | 0.18%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 456       | 38.81%  |
| KDE5             | 221       | 18.81%  |
| Unknown          | 134       | 11.4%   |
| XFCE             | 106       | 9.02%   |
| X-Cinnamon       | 78        | 6.64%   |
| KDE4             | 33        | 2.81%   |
| KDE              | 29        | 2.47%   |
| MATE             | 28        | 2.38%   |
| Cinnamon         | 20        | 1.7%    |
| Unity            | 12        | 1.02%   |
| LXQt             | 12        | 1.02%   |
| i3               | 7         | 0.6%    |
| Pantheon         | 6         | 0.51%   |
| GNOME Flashback  | 5         | 0.43%   |
| Budgie           | 5         | 0.43%   |
| Deepin           | 4         | 0.34%   |
| GNOME Classic    | 3         | 0.26%   |
| bspwm            | 3         | 0.26%   |
| xmonad           | 2         | 0.17%   |
| qtile            | 2         | 0.17%   |
| LXDE             | 2         | 0.17%   |
| lightdm-xsession | 2         | 0.17%   |
| trinity          | 1         | 0.09%   |
| sway             | 1         | 0.09%   |
| icewm            | 1         | 0.09%   |
| DWM              | 1         | 0.09%   |
| awesome          | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 876       | 76.57%  |
| Wayland | 179       | 15.65%  |
| Unknown | 69        | 6.03%   |
| Tty     | 20        | 1.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 539       | 46.87%  |
| SDDM    | 200       | 17.39%  |
| GDM3    | 130       | 11.3%   |
| LightDM | 120       | 10.43%  |
| GDM     | 93        | 8.09%   |
| TDM     | 33        | 2.87%   |
| KDM     | 32        | 2.78%   |
| XDM     | 2         | 0.17%   |
| MDM     | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 713       | 62.65%  |
| bg_BG   | 199       | 17.49%  |
| Unknown | 143       | 12.57%  |
| en_GB   | 25        | 2.2%    |
| C       | 22        | 1.93%   |
| ru_RU   | 9         | 0.79%   |
| de_DE   | 7         | 0.62%   |
| POSIX   | 2         | 0.18%   |
| it_IT   | 2         | 0.18%   |
| C.UTF8  | 2         | 0.18%   |
| uk_UA   | 1         | 0.09%   |
| tr_TR   | 1         | 0.09%   |
| sv_SE   | 1         | 0.09%   |
| ru_UA   | 1         | 0.09%   |
| ia_FR   | 1         | 0.09%   |
| hu_HU   | 1         | 0.09%   |
| fr_FR   | 1         | 0.09%   |
| es_ES   | 1         | 0.09%   |
| en_NZ   | 1         | 0.09%   |
| en_DK   | 1         | 0.09%   |
| en_CA   | 1         | 0.09%   |
| en_AU   | 1         | 0.09%   |
| en_AG   | 1         | 0.09%   |
| Default | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 624       | 55.37%  |
| EFI  | 503       | 44.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 826       | 72.65%  |
| Btrfs   | 94        | 8.27%   |
| Overlay | 83        | 7.3%    |
| Unknown | 56        | 4.93%   |
| Tmpfs   | 40        | 3.52%   |
| Xfs     | 20        | 1.76%   |
| Zfs     | 9         | 0.79%   |
| Ext3    | 4         | 0.35%   |
| Ext2    | 3         | 0.26%   |
| Jfs     | 1         | 0.09%   |
| F2fs    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 560       | 49.43%  |
| GPT     | 414       | 36.54%  |
| MBR     | 159       | 14.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 953       | 84.86%  |
| Yes       | 170       | 15.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 768       | 68.69%  |
| Yes       | 350       | 31.31%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 215       | 19.58%  |
| ASUSTek Computer                     | 186       | 16.94%  |
| Hewlett-Packard                      | 154       | 14.03%  |
| Dell                                 | 136       | 12.39%  |
| ASRock                               | 79        | 7.19%   |
| Acer                                 | 74        | 6.74%   |
| Gigabyte Technology                  | 66        | 6.01%   |
| MSI                                  | 40        | 3.64%   |
| Toshiba                              | 32        | 2.91%   |
| Fujitsu                              | 17        | 1.55%   |
| Apple                                | 13        | 1.18%   |
| Intel                                | 10        | 0.91%   |
| Fujitsu Siemens                      | 6         | 0.55%   |
| Foxconn                              | 6         | 0.55%   |
| AMI                                  | 5         | 0.46%   |
| Valve                                | 4         | 0.36%   |
| Sony                                 | 4         | 0.36%   |
| Samsung Electronics                  | 4         | 0.36%   |
| Unknown                              | 4         | 0.36%   |
| TUXEDO                               | 3         | 0.27%   |
| Pegatron                             | 3         | 0.27%   |
| Packard Bell                         | 3         | 0.27%   |
| HUAWEI                               | 3         | 0.27%   |
| Wibtek                               | 2         | 0.18%   |
| Medion                               | 2         | 0.18%   |
| Google                               | 2         | 0.18%   |
| ECS                                  | 2         | 0.18%   |
| Timi                                 | 1         | 0.09%   |
| Thecus                               | 1         | 0.09%   |
| System76                             | 1         | 0.09%   |
| Supermicro                           | 1         | 0.09%   |
| Shuttle                              | 1         | 0.09%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.09%   |
| Seco                                 | 1         | 0.09%   |
| Razer                                | 1         | 0.09%   |
| Radxa                                | 1         | 0.09%   |
| Pine Microsystems                    | 1         | 0.09%   |
| ONDA                                 | 1         | 0.09%   |
| Notebook                             | 1         | 0.09%   |
| MiTAC                                | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 8         | 0.73%   |
| ASUS All Series                            | 7         | 0.64%   |
| Lenovo G500 20236                          | 5         | 0.46%   |
| Dell Inspiron N5110                        | 5         | 0.46%   |
| Valve Jupiter                              | 4         | 0.36%   |
| Lenovo H520S 2561                          | 4         | 0.36%   |
| HP ProBook 4540s                           | 4         | 0.36%   |
| HP ProBook 450 G8 Notebook PC              | 4         | 0.36%   |
| ASUS X541NA                                | 4         | 0.36%   |
| MSI MS-7C56                                | 3         | 0.27%   |
| MSI MS-7C37                                | 3         | 0.27%   |
| Lenovo Y520-15IKBN 80WK                    | 3         | 0.27%   |
| HP ProBook 450 G0                          | 3         | 0.27%   |
| HP Pavilion 15                             | 3         | 0.27%   |
| HP Notebook                                | 3         | 0.27%   |
| HP 255 G8 Notebook PC                      | 3         | 0.27%   |
| Gigabyte B550 GAMING X V2                  | 3         | 0.27%   |
| Dell Precision M4600                       | 3         | 0.27%   |
| Dell OptiPlex 780                          | 3         | 0.27%   |
| Dell Latitude E6410                        | 3         | 0.27%   |
| Dell Latitude E4300                        | 3         | 0.27%   |
| ASUS VivoBook_ASUSLaptop M1605YA_M1605YA   | 3         | 0.27%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.27%   |
| ASUS N551VW                                | 3         | 0.27%   |
| ASRock Z97 Anniversary                     | 3         | 0.27%   |
| ASRock B450M Steel Legend                  | 3         | 0.27%   |
| Acer Aspire 5738                           | 3         | 0.27%   |
| Wibtek H61-M HDMI2                         | 2         | 0.18%   |
| Toshiba Satellite L300                     | 2         | 0.18%   |
| Toshiba Satellite C50-A-19T                | 2         | 0.18%   |
| Toshiba Satellite A300                     | 2         | 0.18%   |
| Toshiba Satellite A200                     | 2         | 0.18%   |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.18%   |
| MSI Modern 15 A5M                          | 2         | 0.18%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.18%   |
| Lenovo ThinkPad X220 4291IR6               | 2         | 0.18%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1D900   | 2         | 0.18%   |
| Lenovo ThinkPad T460 20FN003LUK            | 2         | 0.18%   |
| Lenovo ThinkPad T420 4236A87               | 2         | 0.18%   |
| Lenovo ThinkPad T14 Gen 1 20S0000NBM       | 2         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 98        | 8.93%   |
| Acer Aspire        | 51        | 4.64%   |
| Dell Latitude      | 40        | 3.64%   |
| Lenovo IdeaPad     | 39        | 3.55%   |
| HP ProBook         | 33        | 3.01%   |
| Dell Inspiron      | 31        | 2.82%   |
| Toshiba Satellite  | 26        | 2.37%   |
| HP Compaq          | 25        | 2.28%   |
| HP Pavilion        | 24        | 2.19%   |
| ASUS VivoBook      | 24        | 2.19%   |
| HP EliteBook       | 23        | 2.09%   |
| Dell Precision     | 18        | 1.64%   |
| ASUS ROG           | 18        | 1.64%   |
| Dell OptiPlex      | 16        | 1.46%   |
| Dell Vostro        | 15        | 1.37%   |
| Lenovo Legion      | 13        | 1.18%   |
| ASUS PRIME         | 13        | 1.18%   |
| Lenovo ThinkCentre | 9         | 0.82%   |
| Fujitsu ESPRIMO    | 9         | 0.82%   |
| Lenovo Yoga        | 8         | 0.73%   |
| Unknown            | 8         | 0.73%   |
| HP 255             | 7         | 0.64%   |
| ASUS All           | 7         | 0.64%   |
| HP Laptop          | 6         | 0.55%   |
| Dell XPS           | 6         | 0.55%   |
| ASUS TUF           | 6         | 0.55%   |
| Acer Nitro         | 6         | 0.55%   |
| MSI Modern         | 5         | 0.46%   |
| Lenovo ThinkBook   | 5         | 0.46%   |
| Lenovo G500        | 5         | 0.46%   |
| ASUS P5K           | 5         | 0.46%   |
| ASUS ASUS          | 5         | 0.46%   |
| Valve Jupiter      | 4         | 0.36%   |
| Lenovo V15         | 4         | 0.36%   |
| Lenovo H520S       | 4         | 0.36%   |
| HP ProDesk         | 4         | 0.36%   |
| HP 250             | 4         | 0.36%   |
| Gigabyte B550      | 4         | 0.36%   |
| ASUS Zenbook       | 4         | 0.36%   |
| ASUS X541NA        | 4         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 93        | 8.47%   |
| 2019    | 90        | 8.2%    |
| 2020    | 87        | 7.92%   |
| 2012    | 87        | 7.92%   |
| 2013    | 81        | 7.38%   |
| 2017    | 79        | 7.19%   |
| 2018    | 77        | 7.01%   |
| 2014    | 69        | 6.28%   |
| 2021    | 64        | 5.83%   |
| 2015    | 58        | 5.28%   |
| 2008    | 56        | 5.1%    |
| 2010    | 55        | 5.01%   |
| 2022    | 50        | 4.55%   |
| 2009    | 46        | 4.19%   |
| 2007    | 36        | 3.28%   |
| 2016    | 33        | 3.01%   |
| 2006    | 16        | 1.46%   |
| 2023    | 14        | 1.28%   |
| 2005    | 3         | 0.27%   |
| 2004    | 2         | 0.18%   |
| Unknown | 2         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 674       | 61.38%  |
| Desktop        | 389       | 35.43%  |
| Convertible    | 12        | 1.09%   |
| Mini pc        | 9         | 0.82%   |
| All in one     | 6         | 0.55%   |
| Tablet         | 4         | 0.36%   |
| Server         | 2         | 0.18%   |
| Phone          | 1         | 0.09%   |
| System on chip | 1         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1041      | 94.38%  |
| Enabled  | 62        | 5.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1094      | 99.64%  |
| Yes  | 4         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 284       | 25.24%  |
| 8.01-16.0       | 216       | 19.2%   |
| 3.01-4.0        | 214       | 19.02%  |
| 16.01-24.0      | 188       | 16.71%  |
| 32.01-64.0      | 103       | 9.16%   |
| 1.01-2.0        | 35        | 3.11%   |
| 24.01-32.0      | 33        | 2.93%   |
| 2.01-3.0        | 25        | 2.22%   |
| 64.01-256.0     | 21        | 1.87%   |
| 0.51-1.0        | 4         | 0.36%   |
| More than 256.0 | 2         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 382       | 30.39%  |
| 2.01-3.0   | 338       | 26.89%  |
| 4.01-8.0   | 193       | 15.35%  |
| 3.01-4.0   | 184       | 14.64%  |
| 0.51-1.0   | 85        | 6.76%   |
| 8.01-16.0  | 57        | 4.53%   |
| 16.01-24.0 | 7         | 0.56%   |
| 0.01-0.5   | 7         | 0.56%   |
| 24.01-32.0 | 2         | 0.16%   |
| 32.01-64.0 | 1         | 0.08%   |
| Unknown    | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 692       | 61.08%  |
| 2      | 292       | 25.77%  |
| 3      | 77        | 6.8%    |
| 4      | 26        | 2.29%   |
| 5      | 20        | 1.77%   |
| 6      | 11        | 0.97%   |
| 0      | 8         | 0.71%   |
| 8      | 3         | 0.26%   |
| 7      | 2         | 0.18%   |
| 11     | 1         | 0.09%   |
| 9      | 1         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 669       | 60.16%  |
| Yes       | 443       | 39.84%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 987       | 89.56%  |
| No        | 115       | 10.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 813       | 73.71%  |
| No        | 290       | 26.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 654       | 58.81%  |
| No        | 458       | 41.19%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Bulgaria | 1098      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Sofia               | 572       | 49.35%  |
| Varna               | 93        | 8.02%   |
| Plovdiv             | 76        | 6.56%   |
| Burgas              | 50        | 4.31%   |
| Stara Zagora        | 24        | 2.07%   |
| Rousse              | 17        | 1.47%   |
| Pernik              | 17        | 1.47%   |
| Pleven              | 15        | 1.29%   |
| Yambol              | 13        | 1.12%   |
| Veliko Tarnovo      | 12        | 1.04%   |
| Shumen              | 12        | 1.04%   |
| Montana             | 11        | 0.95%   |
| Haskovo             | 11        | 0.95%   |
| Dobrich             | 11        | 0.95%   |
| Gabrovo             | 10        | 0.86%   |
| Pazardzhik          | 9         | 0.78%   |
| Sliven              | 8         | 0.69%   |
| Kazanlak            | 8         | 0.69%   |
| Asenovgrad          | 8         | 0.69%   |
| Blagoevgrad         | 7         | 0.6%    |
| Razgrad             | 6         | 0.52%   |
| Vratsa              | 5         | 0.43%   |
| Vidin               | 5         | 0.43%   |
| Svilengrad          | 5         | 0.43%   |
| Sistov              | 4         | 0.35%   |
| Kyustendil          | 4         | 0.35%   |
| Karlovo             | 4         | 0.35%   |
| Gorna Oryahovitsa   | 4         | 0.35%   |
| Svoge               | 3         | 0.26%   |
| Smolyan             | 3         | 0.26%   |
| Silistra            | 3         | 0.26%   |
| Nesebar             | 3         | 0.26%   |
| Kardzhali           | 3         | 0.26%   |
| Dimitrovgrad        | 3         | 0.26%   |
| Velingrad           | 2         | 0.17%   |
| Troyan Municipality | 2         | 0.17%   |
| Targovishte         | 2         | 0.17%   |
| Slashten            | 2         | 0.17%   |
| Sevlievo            | 2         | 0.17%   |
| Septemvri           | 2         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 238       | 355    | 14.88%  |
| Seagate                     | 227       | 343    | 14.2%   |
| WDC                         | 217       | 325    | 13.57%  |
| Toshiba                     | 120       | 162    | 7.5%    |
| Kingston                    | 93        | 139    | 5.82%   |
| Hitachi                     | 84        | 111    | 5.25%   |
| SanDisk                     | 61        | 75     | 3.81%   |
| A-DATA Technology           | 56        | 74     | 3.5%    |
| Intel                       | 50        | 69     | 3.13%   |
| Unknown                     | 47        | 61     | 2.94%   |
| HGST                        | 41        | 62     | 2.56%   |
| SK hynix                    | 34        | 44     | 2.13%   |
| Micron Technology           | 31        | 35     | 1.94%   |
| Crucial                     | 29        | 45     | 1.81%   |
| SPCC                        | 21        | 26     | 1.31%   |
| Team                        | 19        | 20     | 1.19%   |
| KIOXIA                      | 16        | 17     | 1%      |
| China                       | 15        | 19     | 0.94%   |
| Transcend                   | 14        | 15     | 0.88%   |
| Phison Electronics          | 12        | 18     | 0.75%   |
| Kingston Technology Company | 10        | 12     | 0.63%   |
| KingSpec                    | 10        | 12     | 0.63%   |
| Fujitsu                     | 9         | 12     | 0.56%   |
| Silicon Motion              | 8         | 11     | 0.5%    |
| Phison                      | 8         | 8      | 0.5%    |
| Realtek Semiconductor       | 7         | 11     | 0.44%   |
| Patriot                     | 7         | 9      | 0.44%   |
| Maxtor                      | 7         | 13     | 0.44%   |
| LITEON                      | 7         | 9      | 0.44%   |
| PNY                         | 6         | 6      | 0.38%   |
| JMicron Technology          | 6         | 9      | 0.38%   |
| Apple                       | 6         | 8      | 0.38%   |
| XPG                         | 5         | 7      | 0.31%   |
| Intenso                     | 5         | 5      | 0.31%   |
| TO Exter                    | 4         | 4      | 0.25%   |
| LITEONIT                    | 4         | 4      | 0.25%   |
| GOODRAM                     | 4         | 4      | 0.25%   |
| Union Memory (Shenzhen)     | 3         | 6      | 0.19%   |
| Teclast                     | 3         | 3      | 0.19%   |
| Lexar                       | 3         | 3      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 19        | 1.09%   |
| Seagate ST500DM002-1BD142 500GB                    | 18        | 1.04%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 18        | 1.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 18        | 1.04%   |
| Kingston SA400S37120G 120GB SSD                    | 17        | 0.98%   |
| Kingston SA400S37240G 240GB SSD                    | 16        | 0.92%   |
| Toshiba MQ01ABF050 500GB                           | 15        | 0.86%   |
| Toshiba MQ01ABD100 1TB                             | 15        | 0.86%   |
| Samsung SSD 860 EVO 250GB                          | 15        | 0.86%   |
| Samsung SSD 850 EVO 250GB                          | 15        | 0.86%   |
| HGST HTS721010A9E630 1TB                           | 15        | 0.86%   |
| Seagate ST1000DM010-2EP102 1TB                     | 13        | 0.75%   |
| Samsung SSD 860 EVO 500GB                          | 13        | 0.75%   |
| Samsung NVMe SSD Drive 512GB                       | 12        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                    | 11        | 0.63%   |
| Seagate ST1000DM003-1ER162 1TB                     | 10        | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 9         | 0.52%   |
| Toshiba DT01ACA100 1TB                             | 9         | 0.52%   |
| Unknown MMC Card  32GB                             | 8         | 0.46%   |
| SPCC Solid State Disk 512GB                        | 8         | 0.46%   |
| SanDisk NVMe SSD Drive 512GB                       | 8         | 0.46%   |
| Samsung SSD 850 PRO 256GB                          | 8         | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB | 8         | 0.46%   |
| Hitachi HDP725050GLA360 500GB                      | 8         | 0.46%   |
| HGST HTS541010A9E680 1TB                           | 8         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 7         | 0.4%    |
| Unknown MMC Card  64GB                             | 7         | 0.4%    |
| Toshiba DT01ACA050 500GB                           | 7         | 0.4%    |
| Samsung SSD 850 EVO 500GB                          | 7         | 0.4%    |
| Samsung NVMe SSD Drive 500GB                       | 7         | 0.4%    |
| Kingston SV300S37A120G 120GB SSD                   | 7         | 0.4%    |
| Intel SSDSC2CW120A3 120GB                          | 7         | 0.4%    |
| A-DATA SU650 240GB SSD                             | 7         | 0.4%    |
| Toshiba MQ04ABF100 1TB                             | 6         | 0.35%   |
| Seagate ST500LT012-1DG142 500GB                    | 6         | 0.35%   |
| Samsung SSD 970 EVO Plus 500GB                     | 6         | 0.35%   |
| Samsung SSD 970 EVO 250GB                          | 6         | 0.35%   |
| Hitachi HDS721050CLA362 500GB                      | 6         | 0.35%   |
| A-DATA SU650 120GB SSD                             | 6         | 0.35%   |
| WDC WD2003FZEX-00SRLA0 2TB                         | 5         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 224       | 338    | 32.75%  |
| WDC                 | 192       | 281    | 28.07%  |
| Toshiba             | 96        | 129    | 14.04%  |
| Hitachi             | 84        | 111    | 12.28%  |
| HGST                | 41        | 62     | 5.99%   |
| Samsung Electronics | 10        | 13     | 1.46%   |
| Fujitsu             | 9         | 12     | 1.32%   |
| Maxtor              | 7         | 13     | 1.02%   |
| JMicron Technology  | 5         | 6      | 0.73%   |
| TO Exter            | 4         | 4      | 0.58%   |
| Unknown             | 3         | 4      | 0.44%   |
| ExcelStor           | 3         | 7      | 0.44%   |
| StoreJet            | 1         | 1      | 0.15%   |
| SSK                 | 1         | 1      | 0.15%   |
| IBM/Hitachi         | 1         | 2      | 0.15%   |
| HGST HTS            | 1         | 1      | 0.15%   |
| Hewlett-Packard     | 1         | 1      | 0.15%   |
| Apple               | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 115       | 149    | 23.09%  |
| Kingston            | 68        | 90     | 13.65%  |
| A-DATA Technology   | 48        | 64     | 9.64%   |
| SanDisk             | 32        | 38     | 6.43%   |
| Crucial             | 26        | 40     | 5.22%   |
| WDC                 | 21        | 31     | 4.22%   |
| Intel               | 21        | 29     | 4.22%   |
| Team                | 19        | 20     | 3.82%   |
| SPCC                | 19        | 24     | 3.82%   |
| China               | 15        | 19     | 3.01%   |
| Transcend           | 12        | 13     | 2.41%   |
| KingSpec            | 10        | 12     | 2.01%   |
| Micron Technology   | 9         | 10     | 1.81%   |
| Toshiba             | 8         | 9      | 1.61%   |
| Patriot             | 7         | 9      | 1.41%   |
| LITEON              | 7         | 9      | 1.41%   |
| PNY                 | 6         | 6      | 1.2%    |
| Intenso             | 5         | 5      | 1%      |
| LITEONIT            | 4         | 4      | 0.8%    |
| GOODRAM             | 4         | 4      | 0.8%    |
| Apple               | 4         | 6      | 0.8%    |
| Teclast             | 3         | 3      | 0.6%    |
| Lexar               | 3         | 3      | 0.6%    |
| AMD                 | 3         | 5      | 0.6%    |
| Verbatim            | 2         | 2      | 0.4%    |
| SK hynix            | 2         | 2      | 0.4%    |
| Seagate             | 2         | 3      | 0.4%    |
| OCZ                 | 2         | 2      | 0.4%    |
| Innodisk            | 2         | 2      | 0.4%    |
| XrayDisk            | 1         | 1      | 0.2%    |
| XPG                 | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |
| Origin              | 1         | 3      | 0.2%    |
| OCZ-VERTEX3         | 1         | 1      | 0.2%    |
| Netac               | 1         | 4      | 0.2%    |
| HS-SSD-C100         | 1         | 1      | 0.2%    |
| HPE                 | 1         | 1      | 0.2%    |
| Gigabyte Technology | 1         | 10     | 0.2%    |
| FORESEE             | 1         | 2      | 0.2%    |
| Emtec               | 1         | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 592       | 987    | 40.91%  |
| SSD     | 446       | 648    | 30.82%  |
| NVMe    | 359       | 547    | 24.81%  |
| MMC     | 40        | 49     | 2.76%   |
| Unknown | 10        | 14     | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 832       | 1597   | 65.25%  |
| NVMe | 358       | 545    | 28.08%  |
| SAS  | 45        | 54     | 3.53%   |
| MMC  | 40        | 49     | 3.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 637       | 994    | 61.13%  |
| 0.51-1.0   | 315       | 484    | 30.23%  |
| 1.01-2.0   | 45        | 65     | 4.32%   |
| 3.01-4.0   | 21        | 42     | 2.02%   |
| 2.01-3.0   | 12        | 19     | 1.15%   |
| 4.01-10.0  | 8         | 13     | 0.77%   |
| 10.01-20.0 | 4         | 18     | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 296       | 25.28%  |
| 251-500        | 274       | 23.4%   |
| 501-1000       | 184       | 15.71%  |
| 1001-2000      | 104       | 8.88%   |
| 1-20           | 93        | 7.94%   |
| 51-100         | 81        | 6.92%   |
| 21-50          | 48        | 4.1%    |
| More than 3000 | 41        | 3.5%    |
| Unknown        | 29        | 2.48%   |
| 2001-3000      | 21        | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 456       | 36.63%  |
| 21-50          | 212       | 17.03%  |
| 101-250        | 162       | 13.01%  |
| 51-100         | 148       | 11.89%  |
| 251-500        | 95        | 7.63%   |
| 501-1000       | 81        | 6.51%   |
| 1001-2000      | 37        | 2.97%   |
| Unknown        | 29        | 2.33%   |
| More than 3000 | 14        | 1.12%   |
| 2001-3000      | 11        | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD6000HLHX-01JJPV0 600GB        | 3         | 4      | 2.44%   |
| Seagate ST9500325AS 500GB           | 3         | 3      | 2.44%   |
| Seagate ST500DM002-1BD142 500GB     | 3         | 3      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 3      | 2.44%   |
| Samsung Electronics SSD 870 EVO 1TB | 3         | 3      | 2.44%   |
| WDC WD5000AAKX-603CA0 500GB         | 2         | 6      | 1.63%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 1.63%   |
| Toshiba MQ01ABD100 1TB              | 2         | 2      | 1.63%   |
| Seagate ST2000DM001-1CH164 2TB      | 2         | 2      | 1.63%   |
| Kingston SA400S37480G 480GB SSD     | 2         | 2      | 1.63%   |
| KingSpec P3-128 128GB SSD           | 2         | 3      | 1.63%   |
| Intel SSDSC2CW120A3 120GB           | 2         | 2      | 1.63%   |
| Hitachi HDP725050GLA360 500GB       | 2         | 2      | 1.63%   |
| HGST HTS721010A9E630 1TB            | 2         | 2      | 1.63%   |
| China SSD 120GB                     | 2         | 2      | 1.63%   |
| A-DATA Technology SU900 256GB SSD   | 2         | 2      | 1.63%   |
| A-DATA Technology SU650 120GB SSD   | 2         | 2      | 1.63%   |
| WDC WDS100T2B0B-00YS70 1TB SSD      | 1         | 1      | 0.81%   |
| WDC WD5000LPVX-60V0TT0 500GB        | 1         | 1      | 0.81%   |
| WDC WD5000LPVX-55V0TT0 500GB        | 1         | 1      | 0.81%   |
| WDC WD5000BEVT-75A0RT0 500GB        | 1         | 1      | 0.81%   |
| WDC WD5000AADS-00S9B0 500GB         | 1         | 2      | 0.81%   |
| WDC WD5000AACS-00G8B1 500GB         | 1         | 1      | 0.81%   |
| WDC WD40PURX-64GVNY0 4TB            | 1         | 1      | 0.81%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 1      | 0.81%   |
| WDC WD3200AAJS-07M0A0 320GB         | 1         | 2      | 0.81%   |
| WDC WD2500JS-00MHB0 250GB           | 1         | 1      | 0.81%   |
| WDC WD2500AAKX-753CA1 250GB         | 1         | 1      | 0.81%   |
| WDC WD1600BEVT-80A23T0 160GB        | 1         | 1      | 0.81%   |
| WDC WD15EARS-00S8B1 1TB             | 1         | 1      | 0.81%   |
| WDC WD10EFRX-68PJCN0 1TB            | 1         | 2      | 0.81%   |
| WDC WD10EARS-00MVWB0 1TB            | 1         | 1      | 0.81%   |
| WDC WD1003FZEX-00K3CA0 1TB          | 1         | 1      | 0.81%   |
| Toshiba MQ01ABD050 500GB            | 1         | 1      | 0.81%   |
| Toshiba MK3252GSX 320GB             | 1         | 1      | 0.81%   |
| Toshiba MK2552GSX 250GB             | 1         | 3      | 0.81%   |
| Toshiba MK2035GSS 200GB             | 1         | 1      | 0.81%   |
| Toshiba MK1637GSX 160GB             | 1         | 1      | 0.81%   |
| Toshiba HDWD120 2TB                 | 1         | 1      | 0.81%   |
| Toshiba DT01ACA300 3TB              | 1         | 1      | 0.81%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 26        | 28     | 21.14%  |
| WDC                 | 21        | 29     | 17.07%  |
| Hitachi             | 14        | 15     | 11.38%  |
| Toshiba             | 12        | 14     | 9.76%   |
| A-DATA Technology   | 10        | 10     | 8.13%   |
| Samsung Electronics | 7         | 8      | 5.69%   |
| Intel               | 7         | 9      | 5.69%   |
| Kingston            | 5         | 5      | 4.07%   |
| SPCC                | 3         | 3      | 2.44%   |
| Maxtor              | 3         | 4      | 2.44%   |
| KingSpec            | 3         | 4      | 2.44%   |
| SanDisk             | 2         | 2      | 1.63%   |
| HGST                | 2         | 2      | 1.63%   |
| ExcelStor           | 2         | 3      | 1.63%   |
| China               | 2         | 2      | 1.63%   |
| SK hynix            | 1         | 1      | 0.81%   |
| Patriot             | 1         | 1      | 0.81%   |
| Lenovo              | 1         | 1      | 0.81%   |
| Fujitsu             | 1         | 2      | 0.81%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 26        | 28     | 32.5%   |
| WDC       | 20        | 28     | 25%     |
| Hitachi   | 14        | 15     | 17.5%   |
| Toshiba   | 12        | 14     | 15%     |
| Maxtor    | 3         | 4      | 3.75%   |
| HGST      | 2         | 2      | 2.5%    |
| ExcelStor | 2         | 3      | 2.5%    |
| Fujitsu   | 1         | 2      | 1.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 77        | 96     | 65.81%  |
| SSD  | 33        | 39     | 28.21%  |
| NVMe | 7         | 8      | 5.98%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT3 752GB | 1         | 1      | 33.33%  |
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 33.33%  |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 66.67%  |
| HGST   | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 658       | 1314   | 54.56%  |
| Works    | 434       | 785    | 35.99%  |
| Malfunc  | 111       | 143    | 9.2%    |
| Failed   | 3         | 3      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 758       | 54.53%  |
| AMD                              | 186       | 13.38%  |
| Samsung Electronics              | 137       | 9.86%   |
| SanDisk                          | 40        | 2.88%   |
| Kingston Technology Company      | 33        | 2.37%   |
| SK hynix                         | 32        | 2.3%    |
| Micron Technology                | 22        | 1.58%   |
| Phison Electronics               | 21        | 1.51%   |
| Nvidia                           | 21        | 1.51%   |
| JMicron Technology               | 19        | 1.37%   |
| KIOXIA                           | 18        | 1.29%   |
| ASMedia Technology               | 18        | 1.29%   |
| Toshiba America Info Systems     | 15        | 1.08%   |
| Realtek Semiconductor            | 14        | 1.01%   |
| Marvell Technology Group         | 11        | 0.79%   |
| Silicon Motion                   | 10        | 0.72%   |
| ADATA Technology                 | 10        | 0.72%   |
| Micron/Crucial Technology        | 5         | 0.36%   |
| Union Memory (Shenzhen)          | 4         | 0.29%   |
| VIA Technologies                 | 2         | 0.14%   |
| Transcend                        | 2         | 0.14%   |
| Lenovo                           | 2         | 0.14%   |
| Hewlett-Packard                  | 2         | 0.14%   |
| Solid State Storage Technology   | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| O2 Micro                         | 1         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.07%   |
| LSI Logic / Symbios Logic        | 1         | 0.07%   |
| Integrated Technology Express    | 1         | 0.07%   |
| Chelsio Communications           | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 118       | 7.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 69        | 4.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 65        | 4.02%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 53        | 3.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 48        | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 43        | 2.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 35        | 2.17%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 35        | 2.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 30        | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 28        | 1.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 26        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 23        | 1.42%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 21        | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 20        | 1.24%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 19        | 1.18%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 19        | 1.18%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 19        | 1.18%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 18        | 1.11%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 18        | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 17        | 1.05%   |
| AMD 400 Series Chipset SATA Controller                                         | 17        | 1.05%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 16        | 0.99%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 16        | 0.99%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 15        | 0.93%   |
| Intel SATA Controller [RAID mode]                                              | 15        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 15        | 0.93%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 14        | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 13        | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 13        | 0.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 13        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 13        | 0.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 13        | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.74%   |
| Nvidia MCP61 SATA Controller                                                   | 12        | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                            | 12        | 0.74%   |
| Intel SSD 660P Series                                                          | 12        | 0.74%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 12        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 12        | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 12        | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 778       | 55.22%  |
| NVMe | 363       | 25.76%  |
| IDE  | 181       | 12.85%  |
| RAID | 84        | 5.96%   |
| SAS  | 2         | 0.14%   |
| SCSI | 1         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 829       | 75.5%   |
| AMD          | 266       | 24.23%  |
| ARM          | 2         | 0.18%   |
| CentaurHauls | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 13        | 1.18%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 12        | 1.09%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 11        | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz        | 11        | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz       | 10        | 0.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 9         | 0.82%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 9         | 0.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 8         | 0.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 8         | 0.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 8         | 0.73%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 7         | 0.64%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 7         | 0.64%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 7         | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz        | 7         | 0.64%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 7         | 0.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 7         | 0.64%   |
| AMD Ryzen 7 5700U with Radeon Graphics   | 7         | 0.64%   |
| AMD Ryzen 7 4800H with Radeon Graphics   | 7         | 0.64%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 6         | 0.54%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 6         | 0.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 6         | 0.54%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 6         | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 6         | 0.54%   |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 6         | 0.54%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 6         | 0.54%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 6         | 0.54%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 6         | 0.54%   |
| AMD Ryzen 5 5600X 6-Core Processor       | 6         | 0.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 6         | 0.54%   |
| AMD Ryzen 5 3600 6-Core Processor        | 6         | 0.54%   |
| AMD Ryzen 5 1600 Six-Core Processor      | 6         | 0.54%   |
| AMD Ryzen 3 3250U with Radeon Graphics   | 6         | 0.54%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 5         | 0.45%   |
| Intel Pentium CPU 2020M @ 2.40GHz        | 5         | 0.45%   |
| Intel Core i7-8700 CPU @ 3.20GHz         | 5         | 0.45%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 5         | 0.45%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 5         | 0.45%   |
| Intel Core i7-3632QM CPU @ 2.20GHz       | 5         | 0.45%   |
| Intel Core i5-6200U CPU @ 2.30GHz        | 5         | 0.45%   |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 5         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 224       | 20.35%  |
| Intel Core i7           | 199       | 18.07%  |
| Intel Core i3           | 80        | 7.27%   |
| Other                   | 72        | 6.54%   |
| AMD Ryzen 5             | 59        | 5.36%   |
| Intel Core 2 Duo        | 58        | 5.27%   |
| AMD Ryzen 7             | 55        | 5%      |
| Intel Celeron           | 50        | 4.54%   |
| Intel Pentium           | 42        | 3.81%   |
| Intel Xeon              | 23        | 2.09%   |
| AMD Ryzen 9             | 17        | 1.54%   |
| Intel Core 2 Quad       | 16        | 1.45%   |
| AMD Ryzen 3             | 16        | 1.45%   |
| Intel Pentium Dual-Core | 13        | 1.18%   |
| Intel Atom              | 13        | 1.18%   |
| AMD Athlon 64 X2        | 12        | 1.09%   |
| AMD FX                  | 11        | 1%      |
| Intel Pentium Dual      | 10        | 0.91%   |
| AMD Ryzen 7 PRO         | 9         | 0.82%   |
| AMD Ryzen 5 PRO         | 8         | 0.73%   |
| Intel Core i9           | 7         | 0.64%   |
| Intel Core 2            | 7         | 0.64%   |
| AMD Phenom II X4        | 7         | 0.64%   |
| AMD Athlon II X2        | 7         | 0.64%   |
| AMD A8                  | 7         | 0.64%   |
| Intel Pentium Silver    | 6         | 0.54%   |
| AMD A6                  | 6         | 0.54%   |
| AMD Athlon 64           | 5         | 0.45%   |
| AMD E1                  | 4         | 0.36%   |
| AMD A10                 | 4         | 0.36%   |
| Intel Genuine           | 3         | 0.27%   |
| AMD Sempron             | 3         | 0.27%   |
| AMD E                   | 3         | 0.27%   |
| AMD Athlon II X4        | 3         | 0.27%   |
| Intel Pentium M         | 2         | 0.18%   |
| Intel Pentium Gold      | 2         | 0.18%   |
| Intel Core m3           | 2         | 0.18%   |
| Intel Celeron Dual-Core | 2         | 0.18%   |
| AMD Turion 64 X2 Mobile | 2         | 0.18%   |
| AMD Phenom II X6        | 2         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 457       | 41.47%  |
| 4       | 360       | 32.67%  |
| 6       | 114       | 10.34%  |
| 8       | 82        | 7.44%   |
| 1       | 28        | 2.54%   |
| 12      | 19        | 1.72%   |
| 10      | 12        | 1.09%   |
| 3       | 11        | 1%      |
| 16      | 7         | 0.64%   |
| 14      | 6         | 0.54%   |
| 24      | 2         | 0.18%   |
| Unknown | 2         | 0.18%   |
| 40      | 1         | 0.09%   |
| 18      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1093      | 99.54%  |
| 2      | 4         | 0.36%   |
| 4      | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 701       | 63.61%  |
| 1       | 398       | 36.12%  |
| Unknown | 2         | 0.18%   |
| 4       | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1068      | 96.56%  |
| Unknown        | 26        | 2.35%   |
| 32-bit         | 11        | 0.99%   |
| 64-bit         | 1         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 354       | 30.52%  |
| 0x306a9    | 68        | 5.86%   |
| 0x206a7    | 67        | 5.78%   |
| 0x306c3    | 51        | 4.4%    |
| 0x1067a    | 42        | 3.62%   |
| 0x806ec    | 27        | 2.33%   |
| 0x906ea    | 26        | 2.24%   |
| 0x506e3    | 24        | 2.07%   |
| 0x306d4    | 23        | 1.98%   |
| 0x906e9    | 20        | 1.72%   |
| 0x20655    | 20        | 1.72%   |
| 0x6fd      | 19        | 1.64%   |
| 0x406e3    | 19        | 1.64%   |
| 0x40651    | 19        | 1.64%   |
| 0x806ea    | 16        | 1.38%   |
| 0x806c1    | 16        | 1.38%   |
| 0x10676    | 14        | 1.21%   |
| 0x706a1    | 12        | 1.03%   |
| 0x506c9    | 12        | 1.03%   |
| 0x010000c8 | 12        | 1.03%   |
| 0x08108109 | 11        | 0.95%   |
| 0x0a50000c | 10        | 0.86%   |
| 0x08608103 | 10        | 0.86%   |
| 0x6fb      | 9         | 0.78%   |
| 0x806e9    | 8         | 0.69%   |
| 0x406c3    | 7         | 0.6%    |
| 0x0a50000d | 7         | 0.6%    |
| 0x08108102 | 7         | 0.6%    |
| 0xa0652    | 6         | 0.52%   |
| 0x806eb    | 6         | 0.52%   |
| 0x6f6      | 6         | 0.52%   |
| 0x306f2    | 6         | 0.52%   |
| 0x0a404102 | 6         | 0.52%   |
| 0x08701021 | 6         | 0.52%   |
| 0x08600106 | 6         | 0.52%   |
| 0x08600104 | 6         | 0.52%   |
| 0x0800820d | 6         | 0.52%   |
| 0x906a4    | 5         | 0.43%   |
| 0x706e5    | 5         | 0.43%   |
| 0x0a201009 | 5         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 147       | 13.36%  |
| Haswell          | 102       | 9.27%   |
| IvyBridge        | 98        | 8.91%   |
| SandyBridge      | 88        | 8%      |
| Penryn           | 74        | 6.73%   |
| Unknown          | 57        | 5.18%   |
| Skylake          | 54        | 4.91%   |
| Zen 3            | 47        | 4.27%   |
| Core             | 41        | 3.73%   |
| Zen 2            | 38        | 3.45%   |
| Westmere         | 32        | 2.91%   |
| Zen+             | 30        | 2.73%   |
| K10              | 29        | 2.64%   |
| TigerLake        | 28        | 2.55%   |
| Broadwell        | 28        | 2.55%   |
| Silvermont       | 21        | 1.91%   |
| K8 Hammer        | 21        | 1.91%   |
| Alderlake Hybrid | 21        | 1.91%   |
| CometLake        | 19        | 1.73%   |
| Zen              | 15        | 1.36%   |
| Piledriver       | 15        | 1.36%   |
| Goldmont plus    | 15        | 1.36%   |
| Goldmont         | 14        | 1.27%   |
| IceLake          | 13        | 1.18%   |
| Nehalem          | 7         | 0.64%   |
| Excavator        | 7         | 0.64%   |
| Bonnell          | 7         | 0.64%   |
| Steamroller      | 5         | 0.45%   |
| P6               | 5         | 0.45%   |
| Jaguar           | 5         | 0.45%   |
| Bobcat           | 4         | 0.36%   |
| Puma             | 3         | 0.27%   |
| K10 Llano        | 3         | 0.27%   |
| Bulldozer        | 3         | 0.27%   |
| NetBurst         | 2         | 0.18%   |
| Tremont          | 1         | 0.09%   |
| K8 & K10 hybrid  | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 646       | 47.29%  |
| Nvidia                           | 388       | 28.4%   |
| AMD                              | 329       | 24.08%  |
| VIA Technologies                 | 1         | 0.07%   |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Matrox Electronics Systems       | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 67        | 4.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 62        | 4.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 1.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 26        | 1.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 1.78%   |
| Intel HD Graphics 5500                                                                   | 25        | 1.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 25        | 1.78%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 25        | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 24        | 1.71%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 1.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 22        | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 1.42%   |
| Intel HD Graphics 630                                                                    | 20        | 1.42%   |
| Intel UHD Graphics 620                                                                   | 17        | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 17        | 1.21%   |
| Intel HD Graphics 530                                                                    | 16        | 1.14%   |
| AMD Lucienne                                                                             | 15        | 1.07%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 15        | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1%      |
| Intel HD Graphics 620                                                                    | 13        | 0.93%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 0.85%   |
| AMD Rembrandt [Radeon 680M]                                                              | 12        | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.71%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 0.71%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 10        | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 0.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 0.64%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 0.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.64%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 8         | 0.57%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.57%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 8         | 0.57%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 409       | 36.75%  |
| 1 x AMD        | 248       | 22.28%  |
| Intel + Nvidia | 183       | 16.44%  |
| 1 x Nvidia     | 178       | 15.99%  |
| Intel + AMD    | 42        | 3.77%   |
| AMD + Nvidia   | 27        | 2.43%   |
| 2 x AMD        | 17        | 1.53%   |
| Other          | 3         | 0.27%   |
| 2 x Intel      | 2         | 0.18%   |
| 2 x Nvidia     | 1         | 0.09%   |
| 1 x VIA        | 1         | 0.09%   |
| 1 x SiS        | 1         | 0.09%   |
| 1 x Matrox     | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 866       | 77.18%  |
| Proprietary | 209       | 18.63%  |
| Unknown     | 47        | 4.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 608       | 53.05%  |
| 1.01-2.0   | 157       | 13.7%   |
| 0.01-0.5   | 122       | 10.65%  |
| 3.01-4.0   | 88        | 7.68%   |
| 0.51-1.0   | 82        | 7.16%   |
| 7.01-8.0   | 42        | 3.66%   |
| 5.01-6.0   | 27        | 2.36%   |
| 8.01-16.0  | 11        | 0.96%   |
| 2.01-3.0   | 6         | 0.52%   |
| 16.01-24.0 | 3         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 175       | 14.82%  |
| AU Optronics            | 119       | 10.08%  |
| Samsung Electronics     | 117       | 9.91%   |
| Chimei Innolux          | 91        | 7.71%   |
| BOE                     | 91        | 7.71%   |
| Dell                    | 82        | 6.94%   |
| Goldstar                | 50        | 4.23%   |
| Philips                 | 48        | 4.06%   |
| Acer                    | 39        | 3.3%    |
| Hewlett-Packard         | 32        | 2.71%   |
| Lenovo                  | 30        | 2.54%   |
| AOC                     | 30        | 2.54%   |
| Ancor Communications    | 25        | 2.12%   |
| Chi Mei Optoelectronics | 21        | 1.78%   |
| BenQ                    | 20        | 1.69%   |
| Sharp                   | 14        | 1.19%   |
| PANDA                   | 14        | 1.19%   |
| LG Philips              | 11        | 0.93%   |
| Fujitsu Siemens         | 10        | 0.85%   |
| Apple                   | 10        | 0.85%   |
| Panasonic               | 9         | 0.76%   |
| LG Electronics          | 9         | 0.76%   |
| ASUSTek Computer        | 8         | 0.68%   |
| Sony                    | 7         | 0.59%   |
| MSI                     | 7         | 0.59%   |
| Vestel Elektronik       | 6         | 0.51%   |
| NEC Computers           | 6         | 0.51%   |
| HannStar                | 6         | 0.51%   |
| Eizo                    | 6         | 0.51%   |
| CSO                     | 6         | 0.51%   |
| Unknown                 | 4         | 0.34%   |
| Toshiba                 | 4         | 0.34%   |
| Iiyama                  | 4         | 0.34%   |
| CPT                     | 4         | 0.34%   |
| ViewSonic               | 3         | 0.25%   |
| Valve                   | 3         | 0.25%   |
| InfoVision              | 3         | 0.25%   |
| Gigabyte Technology     | 3         | 0.25%   |
| Belinea                 | 3         | 0.25%   |
| WST                     | 2         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 1.06%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.65%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.57%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch     | 6         | 0.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 6         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.49%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.41%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 5         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 4         | 0.33%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch    | 4         | 0.33%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 4         | 0.33%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 4         | 0.33%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 4         | 0.33%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 0.33%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 4         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.33%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 4         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 4         | 0.33%   |
| AOC 2460 AOC2460 1920x1080 531x299mm 24.0-inch                           | 4         | 0.33%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 3         | 0.24%   |
| Samsung Electronics SMXL2270HD SAM072B 1920x1080 476x268mm 21.5-inch     | 3         | 0.24%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 3         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4141 3840x2160 344x194mm 15.5-inch    | 3         | 0.24%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 3         | 0.24%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 3         | 0.24%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 3         | 0.24%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 340x190mm 15.3-inch            | 3         | 0.24%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.24%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.24%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.24%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 3         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 508       | 44.68%  |
| 1366x768 (WXGA)    | 196       | 17.24%  |
| 3840x2160 (4K)     | 55        | 4.84%   |
| 2560x1440 (QHD)    | 52        | 4.57%   |
| 1280x1024 (SXGA)   | 48        | 4.22%   |
| 1600x900 (HD+)     | 41        | 3.61%   |
| 1680x1050 (WSXGA+) | 40        | 3.52%   |
| 1280x800 (WXGA)    | 35        | 3.08%   |
| 1920x1200 (WUXGA)  | 34        | 2.99%   |
| 1440x900 (WXGA+)   | 21        | 1.85%   |
| Unknown            | 14        | 1.23%   |
| 2560x1600          | 12        | 1.06%   |
| 2560x1080          | 12        | 1.06%   |
| 3440x1440          | 7         | 0.62%   |
| 3840x1080          | 5         | 0.44%   |
| 1024x600           | 5         | 0.44%   |
| 800x1280           | 4         | 0.35%   |
| 2880x1800          | 4         | 0.35%   |
| 1360x768           | 4         | 0.35%   |
| 1024x768 (XGA)     | 4         | 0.35%   |
| 3840x1200          | 3         | 0.26%   |
| 1600x1200          | 3         | 0.26%   |
| 1400x1050          | 3         | 0.26%   |
| 1280x720 (HD)      | 3         | 0.26%   |
| 3840x2400          | 2         | 0.18%   |
| 3200x1080          | 2         | 0.18%   |
| 2288x1287          | 2         | 0.18%   |
| 2256x1504          | 2         | 0.18%   |
| 2160x1440          | 2         | 0.18%   |
| 800x480            | 1         | 0.09%   |
| 6784x2160          | 1         | 0.09%   |
| 6400x1080          | 1         | 0.09%   |
| 5120x1080          | 1         | 0.09%   |
| 4240x1440          | 1         | 0.09%   |
| 3600x1200          | 1         | 0.09%   |
| 3456x2160          | 1         | 0.09%   |
| 3200x1800 (QHD+)   | 1         | 0.09%   |
| 3000x2000          | 1         | 0.09%   |
| 2048x1152          | 1         | 0.09%   |
| 1921x1080          | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 375       | 31.65%  |
| 24      | 85        | 7.17%   |
| 13      | 78        | 6.58%   |
| 14      | 73        | 6.16%   |
| 17      | 72        | 6.08%   |
| 23      | 71        | 5.99%   |
| 21      | 69        | 5.82%   |
| 27      | 60        | 5.06%   |
| Unknown | 53        | 4.47%   |
| 19      | 34        | 2.87%   |
| 12      | 32        | 2.7%    |
| 22      | 26        | 2.19%   |
| 16      | 19        | 1.6%    |
| 20      | 18        | 1.52%   |
| 84      | 17        | 1.43%   |
| 34      | 15        | 1.27%   |
| 31      | 13        | 1.1%    |
| 18      | 13        | 1.1%    |
| 54      | 7         | 0.59%   |
| 11      | 7         | 0.59%   |
| 25      | 6         | 0.51%   |
| 10      | 6         | 0.51%   |
| 40      | 5         | 0.42%   |
| 32      | 4         | 0.34%   |
| 72      | 3         | 0.25%   |
| 65      | 3         | 0.25%   |
| 29      | 3         | 0.25%   |
| 28      | 3         | 0.25%   |
| 7       | 3         | 0.25%   |
| 33      | 2         | 0.17%   |
| 26      | 2         | 0.17%   |
| 142     | 1         | 0.08%   |
| 75      | 1         | 0.08%   |
| 55      | 1         | 0.08%   |
| 52      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |
| 30      | 1         | 0.08%   |
| 3       | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 520       | 44.29%  |
| 501-600        | 204       | 17.38%  |
| 401-500        | 138       | 11.75%  |
| 201-300        | 85        | 7.24%   |
| 351-400        | 79        | 6.73%   |
| Unknown        | 53        | 4.51%   |
| 601-700        | 29        | 2.47%   |
| 701-800        | 21        | 1.79%   |
| 1501-2000      | 21        | 1.79%   |
| 1001-1500      | 13        | 1.11%   |
| 801-900        | 6         | 0.51%   |
| 1-100          | 4         | 0.34%   |
| More than 2000 | 1         | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 777       | 72.35%  |
| 16/10   | 156       | 14.53%  |
| 5/4     | 47        | 4.38%   |
| Unknown | 47        | 4.38%   |
| 21/9    | 19        | 1.77%   |
| 4/3     | 13        | 1.21%   |
| 3/2     | 7         | 0.65%   |
| 0.67    | 3         | 0.28%   |
| 6/5     | 2         | 0.19%   |
| 1.00    | 2         | 0.19%   |
| 32/9    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 373       | 31.88%  |
| 201-250        | 191       | 16.32%  |
| 81-90          | 119       | 10.17%  |
| 151-200        | 73        | 6.24%   |
| 301-350        | 65        | 5.56%   |
| Unknown        | 53        | 4.53%   |
| 121-130        | 42        | 3.59%   |
| 251-300        | 38        | 3.25%   |
| 351-500        | 37        | 3.16%   |
| 141-150        | 35        | 2.99%   |
| 71-80          | 34        | 2.91%   |
| More than 1000 | 32        | 2.74%   |
| 61-70          | 29        | 2.48%   |
| 111-120        | 18        | 1.54%   |
| 51-60          | 7         | 0.6%    |
| 501-1000       | 7         | 0.6%    |
| 41-50          | 6         | 0.51%   |
| 131-140        | 6         | 0.51%   |
| 1-40           | 4         | 0.34%   |
| 91-100         | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 369       | 32.2%   |
| 121-160       | 342       | 29.84%  |
| 101-120       | 282       | 24.61%  |
| 161-240       | 59        | 5.15%   |
| Unknown       | 53        | 4.62%   |
| More than 240 | 21        | 1.83%   |
| 1-50          | 20        | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 897       | 79.17%  |
| 2     | 160       | 14.12%  |
| 0     | 55        | 4.85%   |
| 3     | 20        | 1.77%   |
| 4     | 1         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 584       | 34.45%  |
| Intel                             | 531       | 31.33%  |
| Qualcomm Atheros                  | 183       | 10.8%   |
| Broadcom                          | 88        | 5.19%   |
| MediaTek                          | 38        | 2.24%   |
| TP-Link                           | 35        | 2.06%   |
| Broadcom Limited                  | 33        | 1.95%   |
| Ralink                            | 23        | 1.36%   |
| Nvidia                            | 21        | 1.24%   |
| Ralink Technology                 | 17        | 1%      |
| Marvell Technology Group          | 17        | 1%      |
| Qualcomm Atheros Communications   | 16        | 0.94%   |
| Ericsson Business Mobile Networks | 15        | 0.88%   |
| Sierra Wireless                   | 11        | 0.65%   |
| D-Link                            | 7         | 0.41%   |
| Dell                              | 5         | 0.29%   |
| Xiaomi                            | 4         | 0.24%   |
| Sundance Technology Inc / IC Plus | 4         | 0.24%   |
| Samsung Electronics               | 4         | 0.24%   |
| Microsoft                         | 4         | 0.24%   |
| Lenovo                            | 4         | 0.24%   |
| Huawei Technologies               | 4         | 0.24%   |
| Hewlett-Packard                   | 4         | 0.24%   |
| DisplayLink                       | 4         | 0.24%   |
| ASIX Electronics                  | 4         | 0.24%   |
| Aquantia                          | 3         | 0.18%   |
| AMD                               | 3         | 0.18%   |
| Toshiba                           | 2         | 0.12%   |
| Motorola PCS                      | 2         | 0.12%   |
| Google                            | 2         | 0.12%   |
| Davicom Semiconductor             | 2         | 0.12%   |
| D-Link System                     | 2         | 0.12%   |
| Chelsio Communications            | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.06%   |
| Razer USA                         | 1         | 0.06%   |
| Quectel Wireless Solutions        | 1         | 0.06%   |
| Qualcomm                          | 1         | 0.06%   |
| NetXen Incorporated               | 1         | 0.06%   |
| NetGear                           | 1         | 0.06%   |
| Micro Star International          | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 390       | 19.71%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 72        | 3.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 58        | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 32        | 1.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 32        | 1.62%   |
| Intel Wireless 8265 / 8275                                             | 31        | 1.57%   |
| Intel Wi-Fi 6 AX200                                                    | 29        | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 25        | 1.26%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 25        | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 24        | 1.21%   |
| Intel Wireless 7265                                                    | 24        | 1.21%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 23        | 1.16%   |
| Intel Wireless 7260                                                    | 23        | 1.16%   |
| Intel Wi-Fi 6 AX201                                                    | 23        | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 21        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 20        | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                      | 19        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 18        | 0.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 18        | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 16        | 0.81%   |
| Qualcomm Atheros AR9271 802.11n                                        | 15        | 0.76%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 15        | 0.76%   |
| Intel Wireless 8260                                                    | 15        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 15        | 0.76%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 14        | 0.71%   |
| Intel Wireless 3160                                                    | 14        | 0.71%   |
| Intel I211 Gigabit Network Connection                                  | 14        | 0.71%   |
| Intel Ethernet Connection I217-LM                                      | 14        | 0.71%   |
| Broadcom BCM43142 802.11b/g/n                                          | 14        | 0.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 13        | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 13        | 0.66%   |
| Intel 82579V Gigabit Network Connection                                | 13        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 12        | 0.61%   |
| Nvidia MCP61 Ethernet                                                  | 12        | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 12        | 0.61%   |
| Intel WiFi Link 5100                                                   | 12        | 0.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 12        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                               | 12        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 11        | 0.56%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 11        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 400       | 45.92%  |
| Qualcomm Atheros                      | 134       | 15.38%  |
| Realtek Semiconductor                 | 117       | 13.43%  |
| Broadcom                              | 55        | 6.31%   |
| MediaTek                              | 37        | 4.25%   |
| TP-Link                               | 29        | 3.33%   |
| Ralink                                | 23        | 2.64%   |
| Ralink Technology                     | 17        | 1.95%   |
| Qualcomm Atheros Communications       | 16        | 1.84%   |
| Sierra Wireless                       | 11        | 1.26%   |
| Broadcom Limited                      | 11        | 1.26%   |
| Microsoft                             | 4         | 0.46%   |
| D-Link                                | 4         | 0.46%   |
| Ericsson Business Mobile Networks     | 2         | 0.23%   |
| Dell                                  | 2         | 0.23%   |
| Quectel Wireless Solutions            | 1         | 0.11%   |
| Qualcomm                              | 1         | 0.11%   |
| NetGear                               | 1         | 0.11%   |
| Micro Star International              | 1         | 0.11%   |
| Hewlett-Packard                       | 1         | 0.11%   |
| Gemtek                                | 1         | 0.11%   |
| Fibocom                               | 1         | 0.11%   |
| ASUSTek Computer                      | 1         | 0.11%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.11%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 32        | 3.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 32        | 3.66%   |
| Intel Wireless 8265 / 8275                                     | 31        | 3.54%   |
| Intel Wi-Fi 6 AX200                                            | 29        | 3.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 25        | 2.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 24        | 2.74%   |
| Intel Wireless 7265                                            | 24        | 2.74%   |
| Intel Wireless 7260                                            | 23        | 2.63%   |
| Intel Wi-Fi 6 AX201                                            | 23        | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 21        | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 20        | 2.29%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 18        | 2.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 16        | 1.83%   |
| Qualcomm Atheros AR9271 802.11n                                | 15        | 1.71%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 15        | 1.71%   |
| Intel Wireless 8260                                            | 15        | 1.71%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 15        | 1.71%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 14        | 1.6%    |
| Intel Wireless 3160                                            | 14        | 1.6%    |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 1.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 13        | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 1.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 12        | 1.37%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 12        | 1.37%   |
| Intel WiFi Link 5100                                           | 12        | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 1.26%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 11        | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 11        | 1.26%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 10        | 1.14%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 10        | 1.14%   |
| Intel Centrino Ultimate-N 6300                                 | 10        | 1.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 1.14%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 9         | 1.03%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 9         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 9         | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 8         | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 8         | 0.91%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 7         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 530       | 50.52%  |
| Intel                             | 294       | 28.03%  |
| Qualcomm Atheros                  | 67        | 6.39%   |
| Broadcom                          | 41        | 3.91%   |
| Broadcom Limited                  | 22        | 2.1%    |
| Nvidia                            | 21        | 2%      |
| Marvell Technology Group          | 17        | 1.62%   |
| TP-Link                           | 6         | 0.57%   |
| Xiaomi                            | 4         | 0.38%   |
| Sundance Technology Inc / IC Plus | 4         | 0.38%   |
| Samsung Electronics               | 4         | 0.38%   |
| DisplayLink                       | 4         | 0.38%   |
| ASIX Electronics                  | 4         | 0.38%   |
| Lenovo                            | 3         | 0.29%   |
| Huawei Technologies               | 3         | 0.29%   |
| D-Link                            | 3         | 0.29%   |
| Aquantia                          | 3         | 0.29%   |
| Motorola PCS                      | 2         | 0.19%   |
| Google                            | 2         | 0.19%   |
| Davicom Semiconductor             | 2         | 0.19%   |
| D-Link System                     | 2         | 0.19%   |
| Chelsio Communications            | 2         | 0.19%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.1%    |
| NetXen Incorporated               | 1         | 0.1%    |
| MediaTek                          | 1         | 0.1%    |
| JMicron Technology                | 1         | 0.1%    |
| ICS Advent                        | 1         | 0.1%    |
| Cypress Semiconductor             | 1         | 0.1%    |
| Attansic Technology               | 1         | 0.1%    |
| Apple                             | 1         | 0.1%    |
| 3Com                              | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller     | 390       | 36.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                      | 72        | 6.7%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                      | 58        | 5.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                   | 25        | 2.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                      | 23        | 2.14%   |
| Realtek RTL8125 2.5GbE Controller                                          | 19        | 1.77%   |
| Intel Ethernet Connection (2) I219-V                                       | 18        | 1.68%   |
| Intel I211 Gigabit Network Connection                                      | 14        | 1.3%    |
| Intel Ethernet Connection I217-LM                                          | 14        | 1.3%    |
| Intel 82579V Gigabit Network Connection                                    | 13        | 1.21%   |
| Nvidia MCP61 Ethernet                                                      | 12        | 1.12%   |
| Intel 82567LM Gigabit Network Connection                                   | 12        | 1.12%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                     | 11        | 1.02%   |
| Intel Ethernet Controller I225-V                                           | 11        | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                                      | 11        | 1.02%   |
| Intel Ethernet Connection (7) I219-V                                       | 10        | 0.93%   |
| Intel Ethernet Connection I219-LM                                          | 9         | 0.84%   |
| Intel Ethernet Connection I217-V                                           | 9         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                                   | 9         | 0.84%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                           | 9         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                              | 8         | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet             | 8         | 0.74%   |
| Intel Ethernet Connection I218-LM                                          | 8         | 0.74%   |
| Intel Ethernet Connection (6) I219-V                                       | 8         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                                      | 8         | 0.74%   |
| Intel Ethernet Connection (2) I218-V                                       | 7         | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                                 | 7         | 0.65%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]            | 6         | 0.56%   |
| Realtek Killer E2600 GbE Controller                                        | 6         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                   | 6         | 0.56%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                    | 6         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                  | 5         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                  | 5         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                                      | 5         | 0.47%   |
| Intel Ethernet Connection (4) I219-V                                       | 5         | 0.47%   |
| Intel Ethernet Connection (16) I219-V                                      | 5         | 0.47%   |
| Intel 82566DM-2 Gigabit Network Connection                                 | 5         | 0.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                            | 5         | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                             | 4         | 0.37%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY | 4         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 987       | 53.96%  |
| WiFi     | 812       | 44.4%   |
| Modem    | 30        | 1.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 639       | 55.37%  |
| Ethernet | 515       | 44.63%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 645       | 58.42%  |
| 1     | 423       | 38.32%  |
| 3     | 20        | 1.81%   |
| 0     | 10        | 0.91%   |
| 4     | 4         | 0.36%   |
| 7     | 1         | 0.09%   |
| 5     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1069      | 96.22%  |
| Yes  | 42        | 3.78%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 284       | 42.51%  |
| Realtek Semiconductor           | 58        | 8.68%   |
| Qualcomm Atheros Communications | 45        | 6.74%   |
| IMC Networks                    | 40        | 5.99%   |
| Broadcom                        | 38        | 5.69%   |
| Cambridge Silicon Radio         | 37        | 5.54%   |
| Foxconn / Hon Hai               | 29        | 4.34%   |
| Lite-On Technology              | 28        | 4.19%   |
| Toshiba                         | 16        | 2.4%    |
| Dell                            | 15        | 2.25%   |
| Hewlett-Packard                 | 14        | 2.1%    |
| Apple                           | 14        | 2.1%    |
| Ralink                          | 11        | 1.65%   |
| ASUSTek Computer                | 9         | 1.35%   |
| MediaTek                        | 8         | 1.2%    |
| Integrated System Solution      | 7         | 1.05%   |
| Foxconn International           | 6         | 0.9%    |
| TP-Link                         | 2         | 0.3%    |
| Realtek                         | 2         | 0.3%    |
| Ralink Technology               | 2         | 0.3%    |
| Logitech                        | 1         | 0.15%   |
| Belkin Components               | 1         | 0.15%   |
| Unknown                         | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 107       | 16.02%  |
| Intel AX201 Bluetooth                                 | 59        | 8.83%   |
| Realtek Bluetooth Radio                               | 48        | 7.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 46        | 6.89%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 37        | 5.54%   |
| Intel AX200 Bluetooth                                 | 28        | 4.19%   |
| Qualcomm Atheros  Bluetooth Device                    | 25        | 3.74%   |
| IMC Networks Bluetooth Radio                          | 18        | 2.69%   |
| Intel Bluetooth Device                                | 15        | 2.25%   |
| Foxconn / Hon Hai Wireless_Device                     | 14        | 2.1%    |
| IMC Networks Wireless_Device                          | 13        | 1.95%   |
| Ralink RT3290 Bluetooth                               | 11        | 1.65%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 9         | 1.35%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 9         | 1.35%   |
| Lite-On Bluetooth Device                              | 9         | 1.35%   |
| Intel AX210 Bluetooth                                 | 9         | 1.35%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 8         | 1.2%    |
| IMC Networks Bluetooth Device                         | 8         | 1.2%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 8         | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device                    | 8         | 1.2%    |
| MediaTek Wireless_Device                              | 7         | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 7         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 7         | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                           | 7         | 1.05%   |
| Toshiba Integrated Bluetooth HCI                      | 6         | 0.9%    |
| HP Broadcom 2070 Bluetooth Combo                      | 6         | 0.9%    |
| Foxconn International BCM43142A0 Bluetooth module     | 6         | 0.9%    |
| Apple Bluetooth Host Controller                       | 6         | 0.9%    |
| Intel Wireless-AC 3168 Bluetooth                      | 5         | 0.75%   |
| Dell DW375 Bluetooth Module                           | 5         | 0.75%   |
| Realtek RTL8723B Bluetooth                            | 4         | 0.6%    |
| Realtek  Bluetooth 4.2 Adapter                        | 4         | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 4         | 0.6%    |
| Lite-On Atheros AR3012 Bluetooth                      | 4         | 0.6%    |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 4         | 0.6%    |
| Foxconn / Hon Hai BCM20702A0                          | 4         | 0.6%    |
| Dell BCM20702A0 Bluetooth Module                      | 4         | 0.6%    |
| Apple Bluetooth USB Host Controller                   | 4         | 0.6%    |
| Toshiba RT Bluetooth Radio                            | 3         | 0.45%   |
| Toshiba Bluetooth Device                              | 3         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 804       | 52.58%  |
| AMD                                          | 322       | 21.06%  |
| Nvidia                                       | 264       | 17.27%  |
| C-Media Electronics                          | 25        | 1.64%   |
| Creative Labs                                | 13        | 0.85%   |
| GN Netcom                                    | 8         | 0.52%   |
| Texas Instruments                            | 7         | 0.46%   |
| Razer USA                                    | 7         | 0.46%   |
| Plantronics                                  | 6         | 0.39%   |
| Lenovo                                       | 6         | 0.39%   |
| Logitech                                     | 5         | 0.33%   |
| Creative Technology                          | 5         | 0.33%   |
| ASUSTek Computer                             | 5         | 0.33%   |
| Trust                                        | 4         | 0.26%   |
| VIA Technologies                             | 3         | 0.2%    |
| Tenx Technology                              | 3         | 0.2%    |
| Realtek Semiconductor                        | 3         | 0.2%    |
| JMTek                                        | 3         | 0.2%    |
| Generalplus Technology                       | 3         | 0.2%    |
| Thesycon Systemsoftware & Consulting         | 2         | 0.13%   |
| Micro Star International                     | 2         | 0.13%   |
| Dell                                         | 2         | 0.13%   |
| Corsair                                      | 2         | 0.13%   |
| BEHRINGER International                      | 2         | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.07%   |
| ZOOM                                         | 1         | 0.07%   |
| SteelSeries ApS                              | 1         | 0.07%   |
| Sony                                         | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.07%   |
| Samson Technologies                          | 1         | 0.07%   |
| Roland                                       | 1         | 0.07%   |
| Ploytec                                      | 1         | 0.07%   |
| OPPO Electronics                             | 1         | 0.07%   |
| No brand                                     | 1         | 0.07%   |
| Native Instruments                           | 1         | 0.07%   |
| NAD Electronics                              | 1         | 0.07%   |
| M-Audio                                      | 1         | 0.07%   |
| Kingston Technology                          | 1         | 0.07%   |
| Hewlett-Packard                              | 1         | 0.07%   |
| GYROCOM C&C                                  | 1         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 115       | 6.28%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 89        | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 88        | 4.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 60        | 3.28%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 60        | 3.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 59        | 3.22%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 57        | 3.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 54        | 2.95%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 39        | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 38        | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 33        | 1.8%    |
| AMD Starship/Matisse HD Audio Controller                                   | 32        | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 28        | 1.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 28        | 1.53%   |
| Intel Broadwell-U Audio Controller                                         | 28        | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 28        | 1.53%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 27        | 1.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 25        | 1.37%   |
| AMD FCH Azalia Controller                                                  | 25        | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                              | 24        | 1.31%   |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 24        | 1.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22        | 1.2%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 21        | 1.15%   |
| Intel 200 Series PCH HD Audio                                              | 21        | 1.15%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 21        | 1.15%   |
| Nvidia GP106 High Definition Audio Controller                              | 20        | 1.09%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 20        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 19        | 1.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 17        | 0.93%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 16        | 0.87%   |
| Intel CM238 HD Audio Controller                                            | 16        | 0.87%   |
| Nvidia GF119 HDMI Audio Controller                                         | 15        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 15        | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15        | 0.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 14        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 14        | 0.77%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 14        | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                              | 13        | 0.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 13        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 140       | 19.5%   |
| SK hynix                                | 123       | 17.13%  |
| Kingston                                | 113       | 15.74%  |
| Micron Technology                       | 72        | 10.03%  |
| Unknown                                 | 65        | 9.05%   |
| Corsair                                 | 39        | 5.43%   |
| A-DATA Technology                       | 37        | 5.15%   |
| Ramaxel Technology                      | 21        | 2.92%   |
| Team                                    | 15        | 2.09%   |
| Nanya Technology                        | 14        | 1.95%   |
| Transcend                               | 12        | 1.67%   |
| Crucial                                 | 12        | 1.67%   |
| Elpida                                  | 10        | 1.39%   |
| G.Skill                                 | 9         | 1.25%   |
| Apacer                                  | 6         | 0.84%   |
| Unknown                                 | 6         | 0.84%   |
| GOODRAM                                 | 3         | 0.42%   |
| Unknown (ABCD)                          | 2         | 0.28%   |
| Silicon Power Computer & Communications | 2         | 0.28%   |
| Silicon Power                           | 2         | 0.28%   |
| pqi                                     | 2         | 0.28%   |
| Atermiter                               | 2         | 0.28%   |
| ASint Technology                        | 2         | 0.28%   |
| Unifosa                                 | 1         | 0.14%   |
| Thermaltake                             | 1         | 0.14%   |
| Qimonda                                 | 1         | 0.14%   |
| Patriot                                 | 1         | 0.14%   |
| Neo Forza                               | 1         | 0.14%   |
| HBS                                     | 1         | 0.14%   |
| fef5                                    | 1         | 0.14%   |
| CSX                                     | 1         | 0.14%   |
| A Force                                 | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 10        | 1.29%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 8         | 1.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 6         | 0.77%   |
| Unknown                                                    | 6         | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 5         | 0.64%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 5         | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 5         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 5         | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 5         | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s   | 5         | 0.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 5         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s       | 5         | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 5         | 0.64%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s      | 5         | 0.64%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 4         | 0.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 4         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 4         | 0.52%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s      | 4         | 0.52%   |
| Ramaxel RAM RMT3160ED58E9W1600 4096MB SODIMM DDR3 1600MT/s | 4         | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s       | 4         | 0.52%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 4         | 0.52%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 4         | 0.52%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                 | 4         | 0.52%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 3         | 0.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 3         | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 3         | 0.39%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s     | 3         | 0.39%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s    | 3         | 0.39%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 3         | 0.39%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 3         | 0.39%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s      | 3         | 0.39%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s   | 3         | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s      | 3         | 0.39%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s     | 3         | 0.39%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s      | 3         | 0.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s      | 3         | 0.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s      | 3         | 0.39%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s  | 3         | 0.39%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s       | 3         | 0.39%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s    | 3         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 253       | 42.52%  |
| DDR3    | 225       | 37.82%  |
| DDR2    | 29        | 4.87%   |
| SDRAM   | 19        | 3.19%   |
| Unknown | 19        | 3.19%   |
| DDR5    | 17        | 2.86%   |
| LPDDR4  | 8         | 1.34%   |
| LPDDR5  | 7         | 1.18%   |
| DDR     | 7         | 1.18%   |
| LPDDR3  | 6         | 1.01%   |
| DRAM    | 5         | 0.84%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 358       | 61.2%   |
| DIMM         | 203       | 34.7%   |
| Row Of Chips | 16        | 2.74%   |
| Chip         | 4         | 0.68%   |
| FB-DIMM      | 2         | 0.34%   |
| RIMM         | 1         | 0.17%   |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 222       | 34.31%  |
| 4096    | 186       | 28.75%  |
| 16384   | 95        | 14.68%  |
| 2048    | 82        | 12.67%  |
| 32768   | 30        | 4.64%   |
| 1024    | 26        | 4.02%   |
| 512     | 3         | 0.46%   |
| 49152   | 1         | 0.15%   |
| 256     | 1         | 0.15%   |
| Unknown | 1         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 143       | 21.9%   |
| 3200    | 104       | 15.93%  |
| 2667    | 81        | 12.4%   |
| 1333    | 49        | 7.5%    |
| 2400    | 33        | 5.05%   |
| 1334    | 31        | 4.75%   |
| 2133    | 20        | 3.06%   |
| 667     | 18        | 2.76%   |
| 800     | 17        | 2.6%    |
| 3600    | 16        | 2.45%   |
| Unknown | 16        | 2.45%   |
| 4800    | 10        | 1.53%   |
| 1867    | 9         | 1.38%   |
| 6400    | 7         | 1.07%   |
| 1067    | 7         | 1.07%   |
| 1066    | 7         | 1.07%   |
| 5600    | 6         | 0.92%   |
| 3266    | 6         | 0.92%   |
| 4199    | 4         | 0.61%   |
| 3800    | 4         | 0.61%   |
| 3733    | 4         | 0.61%   |
| 3466    | 4         | 0.61%   |
| 3000    | 4         | 0.61%   |
| 2048    | 4         | 0.61%   |
| 1866    | 4         | 0.61%   |
| 1800    | 4         | 0.61%   |
| 333     | 4         | 0.61%   |
| 2933    | 3         | 0.46%   |
| 2666    | 3         | 0.46%   |
| 400     | 3         | 0.46%   |
| 4266    | 2         | 0.31%   |
| 3533    | 2         | 0.31%   |
| 3400    | 2         | 0.31%   |
| 3333    | 2         | 0.31%   |
| 2800    | 2         | 0.31%   |
| 2200    | 2         | 0.31%   |
| 975     | 2         | 0.31%   |
| 57535   | 1         | 0.15%   |
| 6000    | 1         | 0.15%   |
| 4267    | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 7         | 26.92%  |
| Samsung Electronics | 4         | 15.38%  |
| Brother Industries  | 4         | 15.38%  |
| Xerox               | 3         | 11.54%  |
| Canon               | 2         | 7.69%   |
| STMicroelectronics  | 1         | 3.85%   |
| Seiko Epson         | 1         | 3.85%   |
| Prolific Technology | 1         | 3.85%   |
| Kyocera             | 1         | 3.85%   |
| Citizen             | 1         | 3.85%   |
| ATEN International  | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                          | 2         | 7.69%   |
| Xerox Phaser 3140 and 3155                                | 1         | 3.85%   |
| Xerox Phaser 3020                                         | 1         | 3.85%   |
| Xerox Phaser 3010                                         | 1         | 3.85%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.85%   |
| Seiko Epson L3150 Series                                  | 1         | 3.85%   |
| Samsung Xerox Phaser 3117 Laser Printer                   | 1         | 3.85%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 3.85%   |
| Samsung M332x 382x 402x Series                            | 1         | 3.85%   |
| Samsung M267x 287x Series                                 | 1         | 3.85%   |
| Prolific PL2305 Parallel Port                             | 1         | 3.85%   |
| Kyocera ECOSYS P2040dn                                    | 1         | 3.85%   |
| HP LaserJet Professional P1566                            | 1         | 3.85%   |
| HP LaserJet P1102                                         | 1         | 3.85%   |
| HP LaserJet 4350                                          | 1         | 3.85%   |
| HP LaserJet 1018                                          | 1         | 3.85%   |
| HP DeskJet 4530 series                                    | 1         | 3.85%   |
| Citizen Barcode Printer                                   | 1         | 3.85%   |
| Canon PIXMA MP240                                         | 1         | 3.85%   |
| Canon MF3200 series                                       | 1         | 3.85%   |
| Brother Printer                                           | 1         | 3.85%   |
| Brother MFC-B7715DW series                                | 1         | 3.85%   |
| Brother DCP-T300                                          | 1         | 3.85%   |
| Brother DCP-7055 scanner/printer                          | 1         | 3.85%   |
| ATEN International UC-1284B Printer Port                  | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 50%     |
| Mustek Systems  | 1         | 25%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22        | 1         | 25%     |
| HP Scanjet G2710                   | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 25%     |
| Canon CanoScan LiDE 110            | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 157       | 23.5%   |
| IMC Networks                           | 74        | 11.08%  |
| Microdia                               | 59        | 8.83%   |
| Realtek Semiconductor                  | 49        | 7.34%   |
| Sunplus Innovation Technology          | 41        | 6.14%   |
| Quanta                                 | 41        | 6.14%   |
| Bison Electronics                      | 37        | 5.54%   |
| Acer                                   | 27        | 4.04%   |
| Suyin                                  | 18        | 2.69%   |
| Logitech                               | 17        | 2.54%   |
| Syntek                                 | 16        | 2.4%    |
| Lite-On Technology                     | 16        | 2.4%    |
| Cheng Uei Precision Industry (Foxlink) | 15        | 2.25%   |
| Luxvisions Innotech Limited            | 13        | 1.95%   |
| Z-Star Microelectronics                | 10        | 1.5%    |
| Apple                                  | 10        | 1.5%    |
| Alcor Micro                            | 8         | 1.2%    |
| Microsoft                              | 7         | 1.05%   |
| Silicon Motion                         | 6         | 0.9%    |
| Sonix Technology                       | 5         | 0.75%   |
| Lenovo                                 | 5         | 0.75%   |
| Samsung Electronics                    | 3         | 0.45%   |
| Ricoh                                  | 3         | 0.45%   |
| Creative Technology                    | 3         | 0.45%   |
| Unknown                                | 2         | 0.3%    |
| Primax Electronics                     | 2         | 0.3%    |
| Importek                               | 2         | 0.3%    |
| Hewlett-Packard                        | 2         | 0.3%    |
| Generalplus Technology                 | 2         | 0.3%    |
| Aveo Technology                        | 2         | 0.3%    |
| Alpha Imaging Technology               | 2         | 0.3%    |
| ALi                                    | 2         | 0.3%    |
| 8SSC21K12273V1SR33X2817                | 2         | 0.3%    |
| Xiongmai                               | 1         | 0.15%   |
| Sunplus Technology                     | 1         | 0.15%   |
| Razer USA                              | 1         | 0.15%   |
| Pixart Imaging                         | 1         | 0.15%   |
| OmniVision Technologies                | 1         | 0.15%   |
| Google                                 | 1         | 0.15%   |
| Genesys Logic                          | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 36        | 5.39%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 23        | 3.44%   |
| IMC Networks Integrated Camera                      | 21        | 3.14%   |
| Microdia Integrated_Webcam_HD                       | 17        | 2.54%   |
| Chicony HD WebCam                                   | 16        | 2.4%    |
| Realtek Integrated_Webcam_HD                        | 13        | 1.95%   |
| Bison Integrated Camera                             | 13        | 1.95%   |
| Sunplus Integrated_Webcam_HD                        | 12        | 1.8%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 1.8%    |
| Quanta HP HD Camera                                 | 9         | 1.35%   |
| Chicony TOSHIBA Web Camera - HD                     | 9         | 1.35%   |
| Syntek Integrated Camera                            | 8         | 1.2%    |
| Realtek Lenovo EasyCamera                           | 8         | 1.2%    |
| Bison Lenovo EasyCamera                             | 8         | 1.2%    |
| Acer SunplusIT Integrated Camera                    | 8         | 1.2%    |
| Quanta HD User Facing                               | 6         | 0.9%    |
| Microdia Integrated Webcam                          | 6         | 0.9%    |
| Chicony USB 2.0 Camera                              | 6         | 0.9%    |
| Acer Integrated Camera                              | 6         | 0.9%    |
| Z-Star A4 TECH HD PC Camera                         | 5         | 0.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 5         | 0.75%   |
| Quanta HD Webcam                                    | 5         | 0.75%   |
| Microdia Camera                                     | 5         | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.75%   |
| Logitech Webcam C270                                | 5         | 0.75%   |
| Lite-On HP HD Webcam                                | 5         | 0.75%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 5         | 0.75%   |
| Chicony Lenovo EasyCamera                           | 5         | 0.75%   |
| Chicony HD WebCam (Asus N-series)                   | 5         | 0.75%   |
| Acer HD Webcam                                      | 5         | 0.75%   |
| Sunplus Laptop Integrated Webcam HD                 | 4         | 0.6%    |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 0.6%    |
| Quanta VGA WebCam                                   | 4         | 0.6%    |
| Quanta HP TrueVision HD Camera                      | 4         | 0.6%    |
| Quanta ACER HD User Facing                          | 4         | 0.6%    |
| Microdia Laptop_Integrated_Webcam_HD                | 4         | 0.6%    |
| Lite-On Integrated Camera                           | 4         | 0.6%    |
| IMC Networks UVC VGA Webcam                         | 4         | 0.6%    |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.6%    |
| Chicony HP HD Webcam                                | 4         | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 44        | 36.97%  |
| Synaptics                          | 36        | 30.25%  |
| AuthenTec                          | 15        | 12.61%  |
| Shenzhen Goodix Technology         | 8         | 6.72%   |
| Upek                               | 6         | 5.04%   |
| Elan Microelectronics              | 5         | 4.2%    |
| LighTuning Technology              | 3         | 2.52%   |
| STMicroelectronics                 | 1         | 0.84%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.84%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 13.45%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 10.08%  |
| AuthenTec AES2810                                                          | 8         | 6.72%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 5.04%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 4.2%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 4.2%    |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 4.2%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 3.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 3.36%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 3.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.52%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.52%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.68%   |
| Validity Sensors VFS491                                                    | 2         | 1.68%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.68%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.68%   |
| Synaptics WBDI                                                             | 2         | 1.68%   |
| Synaptics  WBDI                                                            | 2         | 1.68%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.68%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 1.68%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.68%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.68%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.84%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.84%   |
| Synaptics TouchPad                                                         | 1         | 0.84%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.84%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.84%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.84%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.84%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.84%   |
| AuthenTec AES1600                                                          | 1         | 0.84%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 29        | 34.52%  |
| Alcor Micro           | 28        | 33.33%  |
| Upek                  | 7         | 8.33%   |
| O2 Micro              | 6         | 7.14%   |
| Advanced Card Systems | 5         | 5.95%   |
| Lenovo                | 4         | 4.76%   |
| SCM Microsystems      | 2         | 2.38%   |
| OmniKey               | 2         | 2.38%   |
| Clay Logic            | 1         | 1.19%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 28        | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 14.29%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 7.14%   |
| Broadcom 5880                                                                | 6         | 7.14%   |
| Broadcom 58200                                                               | 6         | 7.14%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 4.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 4.76%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.38%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 2.38%   |
| Advanced Card Systems ACR39U                                                 | 2         | 2.38%   |
| Advanced Card Systems ACR122U                                                | 2         | 2.38%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.19%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.19%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.19%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 765       | 67.05%  |
| 1     | 298       | 26.12%  |
| 2     | 70        | 6.13%   |
| 3     | 5         | 0.44%   |
| 7     | 1         | 0.09%   |
| 5     | 1         | 0.09%   |
| 4     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 119       | 27.17%  |
| Graphics card            | 99        | 22.6%   |
| Chipcard                 | 70        | 15.98%  |
| Net/wireless             | 44        | 10.05%  |
| Multimedia controller    | 24        | 5.48%   |
| Bluetooth                | 18        | 4.11%   |
| Camera                   | 11        | 2.51%   |
| Storage                  | 10        | 2.28%   |
| Communication controller | 10        | 2.28%   |
| Unassigned class         | 8         | 1.83%   |
| Net/ethernet             | 6         | 1.37%   |
| Card reader              | 6         | 1.37%   |
| Sound                    | 4         | 0.91%   |
| Firewire controller      | 3         | 0.68%   |
| Network                  | 2         | 0.46%   |
| Modem                    | 2         | 0.46%   |
| Storage/ata              | 1         | 0.23%   |
| Flash memory             | 1         | 0.23%   |

