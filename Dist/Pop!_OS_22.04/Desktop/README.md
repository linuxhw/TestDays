Pop!_OS 22.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 613

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | MPG B550I GAMING EDGE WI... | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4e97493141](https://linux-hardware.org/?probe=4e97493141) | Nov 02, 2022 |
| HP            | 212A                        | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| ASUSTek       | H110M-D                     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | [11de150949](https://linux-hardware.org/?probe=11de150949) | Nov 01, 2022 |
| ASUSTek       | H97-PRO                     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4c3ae53c16](https://linux-hardware.org/?probe=4c3ae53c16) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| MSI           | B450 GAMING PLUS MAX        | [e638ed7bd3](https://linux-hardware.org/?probe=e638ed7bd3) | Oct 30, 2022 |
| HP            | 3048h                       | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| Intel         | B75                         | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| MSI           | B85-G43                     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| ASUSTek       | Maximus VIII HERO           | [cb657f604d](https://linux-hardware.org/?probe=cb657f604d) | Oct 26, 2022 |
| Pegatron      | 2AD5                        | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [58af9b9a77](https://linux-hardware.org/?probe=58af9b9a77) | Oct 26, 2022 |
| Gigabyte      | B450 AORUS M                | [1603f6064b](https://linux-hardware.org/?probe=1603f6064b) | Oct 26, 2022 |
| Gigabyte      | Z690 UD DDR4                | [c838769296](https://linux-hardware.org/?probe=c838769296) | Oct 25, 2022 |
| MSI           | H61M-P31/W8                 | [7ba2ecf5f0](https://linux-hardware.org/?probe=7ba2ecf5f0) | Oct 25, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | [3cd266dbbb](https://linux-hardware.org/?probe=3cd266dbbb) | Oct 25, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [c77d3dfeba](https://linux-hardware.org/?probe=c77d3dfeba) | Oct 25, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | [df05c11ff4](https://linux-hardware.org/?probe=df05c11ff4) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| Gigabyte      | H310M H                     | [3a8627fb53](https://linux-hardware.org/?probe=3a8627fb53) | Oct 24, 2022 |
| MSI           | 970A-G46                    | [38541ac772](https://linux-hardware.org/?probe=38541ac772) | Oct 24, 2022 |
| ASUSTek       | A88X-PLUS                   | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [04ea0c7dd2](https://linux-hardware.org/?probe=04ea0c7dd2) | Oct 23, 2022 |
| Lenovo        | SHARKBAY NOK                | [153aaa07cd](https://linux-hardware.org/?probe=153aaa07cd) | Oct 23, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [cfb362baf3](https://linux-hardware.org/?probe=cfb362baf3) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [e14654d246](https://linux-hardware.org/?probe=e14654d246) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [c0867dfce4](https://linux-hardware.org/?probe=c0867dfce4) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [6199e2daaa](https://linux-hardware.org/?probe=6199e2daaa) | Oct 22, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | [dc48a995c4](https://linux-hardware.org/?probe=dc48a995c4) | Oct 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | [32cd9cd246](https://linux-hardware.org/?probe=32cd9cd246) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [b2cc208474](https://linux-hardware.org/?probe=b2cc208474) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASRock        | A320M-HD                    | [d8f21a8ec6](https://linux-hardware.org/?probe=d8f21a8ec6) | Oct 22, 2022 |
| ASRock        | B550M Pro4                  | [9f293160d5](https://linux-hardware.org/?probe=9f293160d5) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [15c764f6fa](https://linux-hardware.org/?probe=15c764f6fa) | Oct 21, 2022 |
| ASRock        | B450M Steel Legend          | [2a9b4f61c6](https://linux-hardware.org/?probe=2a9b4f61c6) | Oct 21, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [fb86c213ca](https://linux-hardware.org/?probe=fb86c213ca) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [02b0d2ded2](https://linux-hardware.org/?probe=02b0d2ded2) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [86950688ac](https://linux-hardware.org/?probe=86950688ac) | Oct 20, 2022 |
| Dell          | 0HY175 A03                  | [ede27fb1d0](https://linux-hardware.org/?probe=ede27fb1d0) | Oct 19, 2022 |
| Gigabyte      | X79-UP4                     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [c84509fb21](https://linux-hardware.org/?probe=c84509fb21) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [e3ce426450](https://linux-hardware.org/?probe=e3ce426450) | Oct 18, 2022 |
| HP            | 339A                        | [e168e3b75b](https://linux-hardware.org/?probe=e168e3b75b) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [40c27af11f](https://linux-hardware.org/?probe=40c27af11f) | Oct 17, 2022 |
| ASRock        | X300M-STX                   | [25fdbfba33](https://linux-hardware.org/?probe=25fdbfba33) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [0a30a79788](https://linux-hardware.org/?probe=0a30a79788) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [a4f5a5b0be](https://linux-hardware.org/?probe=a4f5a5b0be) | Oct 17, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| MSI           | Z590-A PRO                  | [e2991c4619](https://linux-hardware.org/?probe=e2991c4619) | Oct 17, 2022 |
| MSI           | MEG X570 UNIFY              | [0ec570b33c](https://linux-hardware.org/?probe=0ec570b33c) | Oct 16, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | [def577cdb8](https://linux-hardware.org/?probe=def577cdb8) | Oct 16, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [bf7cebc10e](https://linux-hardware.org/?probe=bf7cebc10e) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [0e0a3b9cf0](https://linux-hardware.org/?probe=0e0a3b9cf0) | Oct 16, 2022 |
| ASUSTek       | PRIME H270-PRO              | [3c2eef945d](https://linux-hardware.org/?probe=3c2eef945d) | Oct 16, 2022 |
| ASRock        | X570 Phantom Gaming 4 Wi... | [d91f9fb542](https://linux-hardware.org/?probe=d91f9fb542) | Oct 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [daaa9d8dcc](https://linux-hardware.org/?probe=daaa9d8dcc) | Oct 16, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [b7ebef4e11](https://linux-hardware.org/?probe=b7ebef4e11) | Oct 15, 2022 |
| Lenovo        | ThinkCentre M90 5536A76     | [d6f13cdb14](https://linux-hardware.org/?probe=d6f13cdb14) | Oct 15, 2022 |
| ASRock        | B450 Steel Legend           | [b1de0617da](https://linux-hardware.org/?probe=b1de0617da) | Oct 15, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [2e1434c4ff](https://linux-hardware.org/?probe=2e1434c4ff) | Oct 14, 2022 |
| ASRock        | X570 Taichi                 | [6b78ca11b4](https://linux-hardware.org/?probe=6b78ca11b4) | Oct 14, 2022 |
| Pegatron      | 2AD5                        | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| MSI           | B450M MORTAR MAX            | [c82722f056](https://linux-hardware.org/?probe=c82722f056) | Oct 12, 2022 |
| ASRock        | B450 Gaming K4              | [4b0116a8c6](https://linux-hardware.org/?probe=4b0116a8c6) | Oct 12, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [3462676a1d](https://linux-hardware.org/?probe=3462676a1d) | Oct 10, 2022 |
| Dell          | 0GM819                      | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [e26fca4929](https://linux-hardware.org/?probe=e26fca4929) | Oct 09, 2022 |
| Dell          | 0J3C2F A01                  | [d1001275c6](https://linux-hardware.org/?probe=d1001275c6) | Oct 09, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 1       | [324f177fa7](https://linux-hardware.org/?probe=324f177fa7) | Oct 08, 2022 |
| ASUSTek       | PRIME B450M-K               | [53ca822dcd](https://linux-hardware.org/?probe=53ca822dcd) | Oct 07, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [8ad48ccaec](https://linux-hardware.org/?probe=8ad48ccaec) | Oct 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [9525ea0de3](https://linux-hardware.org/?probe=9525ea0de3) | Oct 07, 2022 |
| ASUSTek       | PRIME X570-PRO              | [83a49e76b9](https://linux-hardware.org/?probe=83a49e76b9) | Oct 06, 2022 |
| ASRock        | B450M/ac                    | [af66fef71a](https://linux-hardware.org/?probe=af66fef71a) | Oct 06, 2022 |
| HP            | 3398                        | [c70e10b68b](https://linux-hardware.org/?probe=c70e10b68b) | Oct 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [512c095e83](https://linux-hardware.org/?probe=512c095e83) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [9232451f1a](https://linux-hardware.org/?probe=9232451f1a) | Oct 06, 2022 |
| HP            | 3398                        | [7dd62dded1](https://linux-hardware.org/?probe=7dd62dded1) | Oct 05, 2022 |
| Intel         | DQ35JO AAD82085-801         | [4056c37c50](https://linux-hardware.org/?probe=4056c37c50) | Oct 04, 2022 |
| ASUSTek       | Maximus VII HERO            | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [54c3aa5cc5](https://linux-hardware.org/?probe=54c3aa5cc5) | Oct 02, 2022 |
| Dell          | 0KWVT8 A03                  | [ae706e478d](https://linux-hardware.org/?probe=ae706e478d) | Oct 02, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [692b59019a](https://linux-hardware.org/?probe=692b59019a) | Oct 01, 2022 |
| ASUSTek       | GRYPHON Z87                 | [3f01bbaa12](https://linux-hardware.org/?probe=3f01bbaa12) | Sep 30, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [7a2f334861](https://linux-hardware.org/?probe=7a2f334861) | Sep 29, 2022 |
| ASUSTek       | Maximus VII HERO            | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| Dell          | 0NDYHG A01                  | [7a5df20f28](https://linux-hardware.org/?probe=7a5df20f28) | Sep 28, 2022 |
| Dell          | 09M8Y8 A01                  | [f129c4da4a](https://linux-hardware.org/?probe=f129c4da4a) | Sep 28, 2022 |
| HP            | 83E9                        | [c24faa3c5b](https://linux-hardware.org/?probe=c24faa3c5b) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2c52de3e56](https://linux-hardware.org/?probe=2c52de3e56) | Sep 27, 2022 |
| Gigabyte      | Z170MX-Gaming 5             | [fbc760a09c](https://linux-hardware.org/?probe=fbc760a09c) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| ASRock        | H97M Anniversary            | [289532b8bb](https://linux-hardware.org/?probe=289532b8bb) | Sep 24, 2022 |
| MSI           | Z97-G55 SLI                 | [dc60d66502](https://linux-hardware.org/?probe=dc60d66502) | Sep 24, 2022 |
| System76      | Thelio Mira                 | [2e9601d2a2](https://linux-hardware.org/?probe=2e9601d2a2) | Sep 24, 2022 |
| ASRock        | X570M Pro4                  | [9e8207dfb7](https://linux-hardware.org/?probe=9e8207dfb7) | Sep 23, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [59c4a7e761](https://linux-hardware.org/?probe=59c4a7e761) | Sep 23, 2022 |
| MSI           | Z97-G55 SLI                 | [27b47d5592](https://linux-hardware.org/?probe=27b47d5592) | Sep 23, 2022 |
| Dell          | 0HHV7N A00                  | [cda6d76f04](https://linux-hardware.org/?probe=cda6d76f04) | Sep 22, 2022 |
| ASRock        | 4X4-V1000                   | [e73062fe01](https://linux-hardware.org/?probe=e73062fe01) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [dc49b2baf4](https://linux-hardware.org/?probe=dc49b2baf4) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [07dd388834](https://linux-hardware.org/?probe=07dd388834) | Sep 21, 2022 |
| Dell          | 09M8Y8 A01                  | [2c7466119d](https://linux-hardware.org/?probe=2c7466119d) | Sep 21, 2022 |
| HP            | 1589                        | [da376a40a1](https://linux-hardware.org/?probe=da376a40a1) | Sep 20, 2022 |
| Gigabyte      | EX58-UD4P                   | [394aad4be9](https://linux-hardware.org/?probe=394aad4be9) | Sep 20, 2022 |
| ASRock        | AB350 Pro4                  | [61a4ab7c20](https://linux-hardware.org/?probe=61a4ab7c20) | Sep 20, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [df0348739e](https://linux-hardware.org/?probe=df0348739e) | Sep 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [a0d6f208fb](https://linux-hardware.org/?probe=a0d6f208fb) | Sep 19, 2022 |
| Gigabyte      | B450 AORUS M                | [136eca7e32](https://linux-hardware.org/?probe=136eca7e32) | Sep 19, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [83b0a59729](https://linux-hardware.org/?probe=83b0a59729) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [fa4082533e](https://linux-hardware.org/?probe=fa4082533e) | Sep 18, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [a418c3e997](https://linux-hardware.org/?probe=a418c3e997) | Sep 18, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [bd7ddbf9f7](https://linux-hardware.org/?probe=bd7ddbf9f7) | Sep 18, 2022 |
| Alienware     | 0CPDXD A00                  | [f65bdb053d](https://linux-hardware.org/?probe=f65bdb053d) | Sep 18, 2022 |
| ASUSTek       | PRIME A520M-A II            | [0bec316a0b](https://linux-hardware.org/?probe=0bec316a0b) | Sep 17, 2022 |
| Minix         | NEO Z83-4 V1.1              | [545552c43e](https://linux-hardware.org/?probe=545552c43e) | Sep 16, 2022 |
| NZXT          | N7 B550                     | [7deb3849db](https://linux-hardware.org/?probe=7deb3849db) | Sep 16, 2022 |
| ASRock        | Z97 Extreme6                | [2c90f58ae4](https://linux-hardware.org/?probe=2c90f58ae4) | Sep 16, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [3f9fc3fc62](https://linux-hardware.org/?probe=3f9fc3fc62) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [6de8f25119](https://linux-hardware.org/?probe=6de8f25119) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [9c97b9e2c1](https://linux-hardware.org/?probe=9c97b9e2c1) | Sep 14, 2022 |
| MACHINIST     | X99-RS9 V3.0                | [64795f6f69](https://linux-hardware.org/?probe=64795f6f69) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [cacc85ca2e](https://linux-hardware.org/?probe=cacc85ca2e) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [0c6d5b57dd](https://linux-hardware.org/?probe=0c6d5b57dd) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | [89fb49d843](https://linux-hardware.org/?probe=89fb49d843) | Sep 13, 2022 |
| ASUSTek       | P8P67 DELUXE                | [a385e1220b](https://linux-hardware.org/?probe=a385e1220b) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | [4fbc7a765f](https://linux-hardware.org/?probe=4fbc7a765f) | Sep 12, 2022 |
| ECS           | Nettle3                     | [23f7f8708c](https://linux-hardware.org/?probe=23f7f8708c) | Sep 12, 2022 |
| System76      | Thelio thelio-r2            | [2f6745bad5](https://linux-hardware.org/?probe=2f6745bad5) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [ce4fc6576c](https://linux-hardware.org/?probe=ce4fc6576c) | Sep 11, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | [29da7835e4](https://linux-hardware.org/?probe=29da7835e4) | Sep 10, 2022 |
| ASUSTek       | M4N72-E                     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b3aa7bd9ca](https://linux-hardware.org/?probe=b3aa7bd9ca) | Sep 09, 2022 |
| Unknown       | Unknown                     | [87f754ac29](https://linux-hardware.org/?probe=87f754ac29) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [1be1b9b040](https://linux-hardware.org/?probe=1be1b9b040) | Sep 09, 2022 |
| Intel         | X99                         | [9ebaa38244](https://linux-hardware.org/?probe=9ebaa38244) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [dbfdcae895](https://linux-hardware.org/?probe=dbfdcae895) | Sep 08, 2022 |
| LattePanda    | 3 Delta CDJQ-BS-7-S70JR1... | [4167167e38](https://linux-hardware.org/?probe=4167167e38) | Sep 08, 2022 |
| Dell          | 0TTDMJ A00                  | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| ASRock        | B450M/ac                    | [efb78c5d25](https://linux-hardware.org/?probe=efb78c5d25) | Sep 07, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [483a414289](https://linux-hardware.org/?probe=483a414289) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [0efcfb2037](https://linux-hardware.org/?probe=0efcfb2037) | Sep 07, 2022 |
| Acer          | 1.0                         | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| Gigabyte      | Z77-D3H                     | [47d065ed5c](https://linux-hardware.org/?probe=47d065ed5c) | Sep 06, 2022 |
| Dell          | 088DT1 A01                  | [c17c4d475f](https://linux-hardware.org/?probe=c17c4d475f) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [8b964572d7](https://linux-hardware.org/?probe=8b964572d7) | Sep 04, 2022 |
| Alienware     | 0NWN7M A00                  | [e254b049c3](https://linux-hardware.org/?probe=e254b049c3) | Sep 04, 2022 |
| Dell          | 0KWVT8 A03                  | [bd0c518002](https://linux-hardware.org/?probe=bd0c518002) | Sep 03, 2022 |
| ASUSTek       | PRIME B550M-A               | [81eb6e9f4e](https://linux-hardware.org/?probe=81eb6e9f4e) | Sep 03, 2022 |
| ASUSTek       | M5A97                       | [de7dc826b0](https://linux-hardware.org/?probe=de7dc826b0) | Sep 03, 2022 |
| Intel         | DX58SO AAE29331-702         | [24c48ddc3e](https://linux-hardware.org/?probe=24c48ddc3e) | Sep 03, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [7b914b0347](https://linux-hardware.org/?probe=7b914b0347) | Sep 03, 2022 |
| HP            | 1497                        | [a8566c45a9](https://linux-hardware.org/?probe=a8566c45a9) | Sep 03, 2022 |
| MSI           | MEG Z390 ACE                | [1f702cfc06](https://linux-hardware.org/?probe=1f702cfc06) | Sep 03, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | [39cb364d6f](https://linux-hardware.org/?probe=39cb364d6f) | Sep 03, 2022 |
| MSI           | B450 GAMING PLUS            | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Gigabyte      | H61M-S1                     | [b54a09966b](https://linux-hardware.org/?probe=b54a09966b) | Sep 02, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d664029076](https://linux-hardware.org/?probe=d664029076) | Sep 02, 2022 |
| HP            | 87D6 SMVB                   | [8efd1ba4e0](https://linux-hardware.org/?probe=8efd1ba4e0) | Sep 02, 2022 |
| Gigabyte      | B85M-HD3                    | [4f4717cb85](https://linux-hardware.org/?probe=4f4717cb85) | Sep 02, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [fb12fe29dd](https://linux-hardware.org/?probe=fb12fe29dd) | Sep 01, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [e311938d4a](https://linux-hardware.org/?probe=e311938d4a) | Sep 01, 2022 |
| ASRock        | B450M/ac                    | [393a08345e](https://linux-hardware.org/?probe=393a08345e) | Sep 01, 2022 |
| Acer          | Aspire X3400                | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [1dd7a06125](https://linux-hardware.org/?probe=1dd7a06125) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| Lenovo        | MAHOBAY                     | [53af4f5de7](https://linux-hardware.org/?probe=53af4f5de7) | Aug 30, 2022 |
| ASRock        | B450M Pro4 R2.0             | [d0ca11a18a](https://linux-hardware.org/?probe=d0ca11a18a) | Aug 29, 2022 |
| ASRock        | B450M Pro4 R2.0             | [fb155ef3bd](https://linux-hardware.org/?probe=fb155ef3bd) | Aug 29, 2022 |
| Dell          | 0KWVT8 A03                  | [b91ce43523](https://linux-hardware.org/?probe=b91ce43523) | Aug 29, 2022 |
| HP            | 1497                        | [625185d1db](https://linux-hardware.org/?probe=625185d1db) | Aug 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [281360b58a](https://linux-hardware.org/?probe=281360b58a) | Aug 29, 2022 |
| BESSTAR Te... | UM700                       | [13fdf5ef5e](https://linux-hardware.org/?probe=13fdf5ef5e) | Aug 29, 2022 |
| MSI           | B450M MORTAR MAX            | [2d89536f80](https://linux-hardware.org/?probe=2d89536f80) | Aug 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [a328df0016](https://linux-hardware.org/?probe=a328df0016) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [3a448c33f9](https://linux-hardware.org/?probe=3a448c33f9) | Aug 28, 2022 |
| MSI           | B450 TOMAHAWK               | [4210c6a219](https://linux-hardware.org/?probe=4210c6a219) | Aug 28, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| Lenovo        | Bantry CRB 31900058 STD     | [d0c37f7188](https://linux-hardware.org/?probe=d0c37f7188) | Aug 28, 2022 |
| Gigabyte      | H67A-USB3-B3                | [b04fc1333e](https://linux-hardware.org/?probe=b04fc1333e) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [a90735a9e9](https://linux-hardware.org/?probe=a90735a9e9) | Aug 27, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [704ce84e6a](https://linux-hardware.org/?probe=704ce84e6a) | Aug 27, 2022 |
| ASRock        | B560 Steel Legend           | [55ebdff357](https://linux-hardware.org/?probe=55ebdff357) | Aug 26, 2022 |
| HP            | 1850                        | [85b5eedc40](https://linux-hardware.org/?probe=85b5eedc40) | Aug 26, 2022 |
| ASRock        | X570 Creator                | [612ada6405](https://linux-hardware.org/?probe=612ada6405) | Aug 26, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [d988a14a82](https://linux-hardware.org/?probe=d988a14a82) | Aug 26, 2022 |
| Acer          | Aspire X3400                | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| Dell          | 0KWVT8 A03                  | [967ff51388](https://linux-hardware.org/?probe=967ff51388) | Aug 24, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [18102e8a9a](https://linux-hardware.org/?probe=18102e8a9a) | Aug 24, 2022 |
| ASRock        | B660-ITX                    | [316ae22af8](https://linux-hardware.org/?probe=316ae22af8) | Aug 24, 2022 |
| HP            | 3647h                       | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [beb3c92510](https://linux-hardware.org/?probe=beb3c92510) | Aug 23, 2022 |
| MSI           | PRO Z690-A DDR4             | [8e57e188c9](https://linux-hardware.org/?probe=8e57e188c9) | Aug 23, 2022 |
| ASUSTek       | P9X79 LE                    | [1fbde15177](https://linux-hardware.org/?probe=1fbde15177) | Aug 22, 2022 |
| ASRock        | X470 Taichi                 | [8f7d642c46](https://linux-hardware.org/?probe=8f7d642c46) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [e8bee7737a](https://linux-hardware.org/?probe=e8bee7737a) | Aug 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | [b182084c88](https://linux-hardware.org/?probe=b182084c88) | Aug 22, 2022 |
| MSI           | FM2-A55M-E33                | [fac0116bf7](https://linux-hardware.org/?probe=fac0116bf7) | Aug 21, 2022 |
| Gigabyte      | M68MT-S2P                   | [23c07b5d2b](https://linux-hardware.org/?probe=23c07b5d2b) | Aug 21, 2022 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [c717f7c6d5](https://linux-hardware.org/?probe=c717f7c6d5) | Aug 21, 2022 |
| MSI           | Z170A PC MATE               | [8df71394cd](https://linux-hardware.org/?probe=8df71394cd) | Aug 20, 2022 |
| Gigabyte      | B550M DS3H                  | [774796ffbd](https://linux-hardware.org/?probe=774796ffbd) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [3a7a62f6f8](https://linux-hardware.org/?probe=3a7a62f6f8) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [93c5d7b0f9](https://linux-hardware.org/?probe=93c5d7b0f9) | Aug 19, 2022 |
| Dell          | 0KWVT8 A03                  | [7af77fd850](https://linux-hardware.org/?probe=7af77fd850) | Aug 18, 2022 |
| Gigabyte      | X299 AORUS MASTER           | [8d76a030ca](https://linux-hardware.org/?probe=8d76a030ca) | Aug 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8a1a495053](https://linux-hardware.org/?probe=8a1a495053) | Aug 18, 2022 |
| ASUSTek       | B150M-C/BR                  | [b15c721e4c](https://linux-hardware.org/?probe=b15c721e4c) | Aug 18, 2022 |
| Acer          | Predator PO5-600s V:1.0     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| MSI           | B450-A PRO MAX              | [9a1a049600](https://linux-hardware.org/?probe=9a1a049600) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [169469e8b6](https://linux-hardware.org/?probe=169469e8b6) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1e4e125d11](https://linux-hardware.org/?probe=1e4e125d11) | Aug 17, 2022 |
| HP            | 2215                        | [71a33dc713](https://linux-hardware.org/?probe=71a33dc713) | Aug 17, 2022 |
| HP            | 2215                        | [aa386126ad](https://linux-hardware.org/?probe=aa386126ad) | Aug 17, 2022 |
| MSI           | H110M PRO-VH PLUS           | [e6e4efd93a](https://linux-hardware.org/?probe=e6e4efd93a) | Aug 17, 2022 |
| Gigabyte      | GA-MA770T-UD3P              | [8441adcca9](https://linux-hardware.org/?probe=8441adcca9) | Aug 17, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [5c2c3d81ef](https://linux-hardware.org/?probe=5c2c3d81ef) | Aug 16, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [0a5775d3a8](https://linux-hardware.org/?probe=0a5775d3a8) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [e75de6c205](https://linux-hardware.org/?probe=e75de6c205) | Aug 15, 2022 |
| Gigabyte      | Z77X-UD5H                   | [5262ee60e8](https://linux-hardware.org/?probe=5262ee60e8) | Aug 14, 2022 |
| HP            | 8054                        | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [5a5538ce52](https://linux-hardware.org/?probe=5a5538ce52) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | [5ef85261aa](https://linux-hardware.org/?probe=5ef85261aa) | Aug 13, 2022 |
| Gigabyte      | H97N-WIFI                   | [966a3e1593](https://linux-hardware.org/?probe=966a3e1593) | Aug 13, 2022 |
| BESSTAR Te... | UM700                       | [81a59240ea](https://linux-hardware.org/?probe=81a59240ea) | Aug 13, 2022 |
| Gigabyte      | GA-A55M-DS2                 | [29e8c10282](https://linux-hardware.org/?probe=29e8c10282) | Aug 13, 2022 |
| MSI           | Z87-G45 GAMING              | [2f541727e1](https://linux-hardware.org/?probe=2f541727e1) | Aug 12, 2022 |
| ASRock        | A320M                       | [1e0a574078](https://linux-hardware.org/?probe=1e0a574078) | Aug 12, 2022 |
| ASUSTek       | H97-PLUS                    | [4ca1b1050d](https://linux-hardware.org/?probe=4ca1b1050d) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A               | [230d7247c0](https://linux-hardware.org/?probe=230d7247c0) | Aug 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [aebe04abda](https://linux-hardware.org/?probe=aebe04abda) | Aug 11, 2022 |
| HP            | 3397                        | [9beccd0ca8](https://linux-hardware.org/?probe=9beccd0ca8) | Aug 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | [d0b0186eb9](https://linux-hardware.org/?probe=d0b0186eb9) | Aug 09, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [80bb75a792](https://linux-hardware.org/?probe=80bb75a792) | Aug 07, 2022 |
| ASUSTek       | Z87-K                       | [d1954b42ae](https://linux-hardware.org/?probe=d1954b42ae) | Aug 06, 2022 |
| HP            | 1998                        | [5164a156e2](https://linux-hardware.org/?probe=5164a156e2) | Aug 05, 2022 |
| Intel         | D955XBK AAC96732-501        | [d6463d7629](https://linux-hardware.org/?probe=d6463d7629) | Aug 05, 2022 |
| MSI           | 970A-G43                    | [a77e1878ae](https://linux-hardware.org/?probe=a77e1878ae) | Aug 05, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [56b0b42020](https://linux-hardware.org/?probe=56b0b42020) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [585bf3495e](https://linux-hardware.org/?probe=585bf3495e) | Aug 04, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [2d017b110e](https://linux-hardware.org/?probe=2d017b110e) | Aug 04, 2022 |
| Gigabyte      | AX370-Gaming K7             | [14447cf212](https://linux-hardware.org/?probe=14447cf212) | Aug 04, 2022 |
| ASUSTek       | P8Z77-V LK                  | [9878a3365c](https://linux-hardware.org/?probe=9878a3365c) | Aug 03, 2022 |
| Intel         | D955XBK AAC96732-501        | [ed4b3ec577](https://linux-hardware.org/?probe=ed4b3ec577) | Aug 03, 2022 |
| Intel         | DP55WB AAE64798-208         | [0c66cac06d](https://linux-hardware.org/?probe=0c66cac06d) | Aug 03, 2022 |
| ASUSTek       | PRIME B550M-A               | [3f1ccf427a](https://linux-hardware.org/?probe=3f1ccf427a) | Aug 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [73b2c51a7e](https://linux-hardware.org/?probe=73b2c51a7e) | Aug 02, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [6127d6e7a3](https://linux-hardware.org/?probe=6127d6e7a3) | Aug 02, 2022 |
| Gigabyte      | A520I AC                    | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| EVGA          | 134-KS-E377                 | [2624cfe274](https://linux-hardware.org/?probe=2624cfe274) | Jul 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [cc3deb0a17](https://linux-hardware.org/?probe=cc3deb0a17) | Jul 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| MSI           | MEG Z690 UNIFY              | [571f500e5e](https://linux-hardware.org/?probe=571f500e5e) | Jul 30, 2022 |
| Dell          | 0TP412                      | [c6138574f4](https://linux-hardware.org/?probe=c6138574f4) | Jul 30, 2022 |
| Gigabyte      | A520I AC                    | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| MSI           | B450M MORTAR MAX            | [1316e90024](https://linux-hardware.org/?probe=1316e90024) | Jul 30, 2022 |
| HP            | 2215                        | [6e351e6da3](https://linux-hardware.org/?probe=6e351e6da3) | Jul 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [622aa6421e](https://linux-hardware.org/?probe=622aa6421e) | Jul 29, 2022 |
| Alienware     | 02XRCM A00                  | [d8c0404bad](https://linux-hardware.org/?probe=d8c0404bad) | Jul 29, 2022 |
| MACHINIST     | X79 V2.82H                  | [29694e2098](https://linux-hardware.org/?probe=29694e2098) | Jul 29, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [b25ca31168](https://linux-hardware.org/?probe=b25ca31168) | Jul 27, 2022 |
| MSI           | PRO Z690-A DDR4             | [2d81f40aad](https://linux-hardware.org/?probe=2d81f40aad) | Jul 27, 2022 |
| ASUSTek       | Z170M-PLUS                  | [8d563bf194](https://linux-hardware.org/?probe=8d563bf194) | Jul 27, 2022 |
| Dell          | 0F896N A02                  | [ede9425ed8](https://linux-hardware.org/?probe=ede9425ed8) | Jul 27, 2022 |
| Gigabyte      | Z170X-Gaming 3              | [a3c2fdccfc](https://linux-hardware.org/?probe=a3c2fdccfc) | Jul 27, 2022 |
| ASUSTek       | PRIME B450M-A               | [4812de622f](https://linux-hardware.org/?probe=4812de622f) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASUSTek       | PRIME Z390-A                | [b8e8d2b6c4](https://linux-hardware.org/?probe=b8e8d2b6c4) | Jul 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [567addf380](https://linux-hardware.org/?probe=567addf380) | Jul 24, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [221bb14fbd](https://linux-hardware.org/?probe=221bb14fbd) | Jul 24, 2022 |
| MSI           | MEG X570 ACE                | [f13fde648e](https://linux-hardware.org/?probe=f13fde648e) | Jul 23, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [8f131b55b9](https://linux-hardware.org/?probe=8f131b55b9) | Jul 22, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | [1fef57c873](https://linux-hardware.org/?probe=1fef57c873) | Jul 22, 2022 |
| Gigabyte      | H110M-S2H-CF                | [f70ea66873](https://linux-hardware.org/?probe=f70ea66873) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [9689ac8020](https://linux-hardware.org/?probe=9689ac8020) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5a52692425](https://linux-hardware.org/?probe=5a52692425) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f524dac3fa](https://linux-hardware.org/?probe=f524dac3fa) | Jul 20, 2022 |
| MSI           | Z590-A PRO                  | [9500cfd7e1](https://linux-hardware.org/?probe=9500cfd7e1) | Jul 19, 2022 |
| Dell          | 02YYK5 A01                  | [94b2dc99fa](https://linux-hardware.org/?probe=94b2dc99fa) | Jul 19, 2022 |
| Lenovo        | MAHOBAY                     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| Gigabyte      | B75M-D3H                    | [1c0d0a79d1](https://linux-hardware.org/?probe=1c0d0a79d1) | Jul 17, 2022 |
| Lenovo        | 30BE SDK0J40705 WIN 3425... | [3c55557131](https://linux-hardware.org/?probe=3c55557131) | Jul 17, 2022 |
| Gigabyte      | H97M-Gaming 3               | [a72ad8ba14](https://linux-hardware.org/?probe=a72ad8ba14) | Jul 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | [36ad4a7384](https://linux-hardware.org/?probe=36ad4a7384) | Jul 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [a23b73c3ff](https://linux-hardware.org/?probe=a23b73c3ff) | Jul 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [2e73a9947c](https://linux-hardware.org/?probe=2e73a9947c) | Jul 15, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [c9ff108124](https://linux-hardware.org/?probe=c9ff108124) | Jul 15, 2022 |
| Lenovo        | ThinkCentre M90p 5864A1U    | [406232d6c2](https://linux-hardware.org/?probe=406232d6c2) | Jul 15, 2022 |
| MSI           | Z170A GAMING M5             | [16d2d7469b](https://linux-hardware.org/?probe=16d2d7469b) | Jul 15, 2022 |
| Gigabyte      | H310M S2 x.x                | [a55538b651](https://linux-hardware.org/?probe=a55538b651) | Jul 14, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [608d209fe5](https://linux-hardware.org/?probe=608d209fe5) | Jul 14, 2022 |
| ASRock        | Z77 Pro4-M                  | [69b486ea31](https://linux-hardware.org/?probe=69b486ea31) | Jul 14, 2022 |
| Dell          | 02YYK5 A01                  | [ca4bfe598b](https://linux-hardware.org/?probe=ca4bfe598b) | Jul 14, 2022 |
| ASUSTek       | M4A79XTD EVO                | [b12edadc03](https://linux-hardware.org/?probe=b12edadc03) | Jul 13, 2022 |
| ASRock        | B450M Steel Legend          | [3732c0ad0c](https://linux-hardware.org/?probe=3732c0ad0c) | Jul 13, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | [a6d5a615d0](https://linux-hardware.org/?probe=a6d5a615d0) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [97b45f9af7](https://linux-hardware.org/?probe=97b45f9af7) | Jul 12, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d7e4d34816](https://linux-hardware.org/?probe=d7e4d34816) | Jul 12, 2022 |
| Gigabyte      | GB-BRR7H-4800               | [a3c14e06c9](https://linux-hardware.org/?probe=a3c14e06c9) | Jul 11, 2022 |
| MSI           | P67A-C43                    | [c76725f62c](https://linux-hardware.org/?probe=c76725f62c) | Jul 11, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [84e5c2ab51](https://linux-hardware.org/?probe=84e5c2ab51) | Jul 11, 2022 |
| ASUSTek       | P5Q-PRO                     | [ad6eedb5e5](https://linux-hardware.org/?probe=ad6eedb5e5) | Jul 10, 2022 |
| ASUSTek       | Z170-A                      | [1ac13f76b1](https://linux-hardware.org/?probe=1ac13f76b1) | Jul 10, 2022 |
| Dell          | 042P49 A02                  | [1b8b98b54d](https://linux-hardware.org/?probe=1b8b98b54d) | Jul 10, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [0e0d93b899](https://linux-hardware.org/?probe=0e0d93b899) | Jul 10, 2022 |
| ASUSTek       | P5Q-PRO                     | [9860ca66f6](https://linux-hardware.org/?probe=9860ca66f6) | Jul 09, 2022 |
| Gigabyte      | B450 AORUS M                | [5d50b40871](https://linux-hardware.org/?probe=5d50b40871) | Jul 09, 2022 |
| HP            | 1495                        | [3e67bd3405](https://linux-hardware.org/?probe=3e67bd3405) | Jul 09, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [a374367376](https://linux-hardware.org/?probe=a374367376) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [fe383d7488](https://linux-hardware.org/?probe=fe383d7488) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [786c9e341c](https://linux-hardware.org/?probe=786c9e341c) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [833f3df27a](https://linux-hardware.org/?probe=833f3df27a) | Jul 09, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [199e7db55a](https://linux-hardware.org/?probe=199e7db55a) | Jul 09, 2022 |
| Gigabyte      | B550 AORUS PRO AX           | [9ad45447d4](https://linux-hardware.org/?probe=9ad45447d4) | Jul 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [6ebe4f89b7](https://linux-hardware.org/?probe=6ebe4f89b7) | Jul 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [3458084b51](https://linux-hardware.org/?probe=3458084b51) | Jul 08, 2022 |
| HP            | 3398                        | [fb1290d5b3](https://linux-hardware.org/?probe=fb1290d5b3) | Jul 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | [8b1a622249](https://linux-hardware.org/?probe=8b1a622249) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [9c2efc454e](https://linux-hardware.org/?probe=9c2efc454e) | Jul 06, 2022 |
| Intel         | DQ35JO AAD82085-801         | [eb5d4499aa](https://linux-hardware.org/?probe=eb5d4499aa) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | [e068e197b4](https://linux-hardware.org/?probe=e068e197b4) | Jul 06, 2022 |
| Dell          | 0200DY A00                  | [442b0c2a46](https://linux-hardware.org/?probe=442b0c2a46) | Jul 06, 2022 |
| Soyo          | SY-A68M FS V2.0             | [ab243c130a](https://linux-hardware.org/?probe=ab243c130a) | Jul 06, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [7a6f484b16](https://linux-hardware.org/?probe=7a6f484b16) | Jul 06, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [bfa2b2f092](https://linux-hardware.org/?probe=bfa2b2f092) | Jul 05, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [161f8c2665](https://linux-hardware.org/?probe=161f8c2665) | Jul 03, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [15118ef9fd](https://linux-hardware.org/?probe=15118ef9fd) | Jul 03, 2022 |
| HP            | 18E7                        | [8f2b2cb5e5](https://linux-hardware.org/?probe=8f2b2cb5e5) | Jul 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [7da3547526](https://linux-hardware.org/?probe=7da3547526) | Jul 01, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d979555615](https://linux-hardware.org/?probe=d979555615) | Jul 01, 2022 |
| ASRock        | B450 Gaming K4              | [2bdfc5f472](https://linux-hardware.org/?probe=2bdfc5f472) | Jul 01, 2022 |
| MSI           | B250M PRO-VD                | [b48e88849b](https://linux-hardware.org/?probe=b48e88849b) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [8c29343495](https://linux-hardware.org/?probe=8c29343495) | Jul 01, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2631bf2ae1](https://linux-hardware.org/?probe=2631bf2ae1) | Jul 01, 2022 |
| HP            | 18E7                        | [1808b6dee4](https://linux-hardware.org/?probe=1808b6dee4) | Jul 01, 2022 |
| Dell          | 0HHV7N A00                  | [41255f7150](https://linux-hardware.org/?probe=41255f7150) | Jun 30, 2022 |
| ASRock        | X399 Taichi                 | [caea75035f](https://linux-hardware.org/?probe=caea75035f) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [b85b1f9277](https://linux-hardware.org/?probe=b85b1f9277) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS M                | [67dc174a62](https://linux-hardware.org/?probe=67dc174a62) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [94d44ae5f2](https://linux-hardware.org/?probe=94d44ae5f2) | Jun 29, 2022 |
| Lenovo        | 36C5 NOK                    | [cd5e39b07a](https://linux-hardware.org/?probe=cd5e39b07a) | Jun 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | [f01192b57e](https://linux-hardware.org/?probe=f01192b57e) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [0a66ce61c6](https://linux-hardware.org/?probe=0a66ce61c6) | Jun 29, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | [f2b790de57](https://linux-hardware.org/?probe=f2b790de57) | Jun 29, 2022 |
| HP            | 3647h                       | [3227f38f98](https://linux-hardware.org/?probe=3227f38f98) | Jun 28, 2022 |
| Gigabyte      | Z170-Gaming K3              | [70dc9ba605](https://linux-hardware.org/?probe=70dc9ba605) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [8efb1d3556](https://linux-hardware.org/?probe=8efb1d3556) | Jun 28, 2022 |
| MSI           | B250M PRO-VD                | [5b239d8bba](https://linux-hardware.org/?probe=5b239d8bba) | Jun 28, 2022 |
| ASRock        | B450 Gaming K4              | [6ecc609381](https://linux-hardware.org/?probe=6ecc609381) | Jun 27, 2022 |
| ASRock        | B450 Steel Legend           | [6f8f8a9df6](https://linux-hardware.org/?probe=6f8f8a9df6) | Jun 26, 2022 |
| ASRock        | B450 Steel Legend           | [547aab5039](https://linux-hardware.org/?probe=547aab5039) | Jun 26, 2022 |
| ASUSTek       | VM40B                       | [35f67bace1](https://linux-hardware.org/?probe=35f67bace1) | Jun 26, 2022 |
| Dell          | 0D6H9T A00                  | [fd65f44d25](https://linux-hardware.org/?probe=fd65f44d25) | Jun 26, 2022 |
| MSI           | MPG B460I GAMING EDGE WI... | [01fcd4495e](https://linux-hardware.org/?probe=01fcd4495e) | Jun 25, 2022 |
| Dell          | 040DDP A00                  | [02721926a7](https://linux-hardware.org/?probe=02721926a7) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| ASUSTek       | LEUCITE                     | [c4d2ed5723](https://linux-hardware.org/?probe=c4d2ed5723) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| Dell          | 0WMJ54 A01                  | [ee865231c1](https://linux-hardware.org/?probe=ee865231c1) | Jun 24, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [055977bdee](https://linux-hardware.org/?probe=055977bdee) | Jun 23, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [1e7e58ae1d](https://linux-hardware.org/?probe=1e7e58ae1d) | Jun 23, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [0bd1e7d592](https://linux-hardware.org/?probe=0bd1e7d592) | Jun 23, 2022 |
| ASUSTek       | PRIME B550M-A               | [d4492d1e5d](https://linux-hardware.org/?probe=d4492d1e5d) | Jun 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [ae30cadddf](https://linux-hardware.org/?probe=ae30cadddf) | Jun 22, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [21d1dc43e6](https://linux-hardware.org/?probe=21d1dc43e6) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [27bc9defca](https://linux-hardware.org/?probe=27bc9defca) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [941b96e6ab](https://linux-hardware.org/?probe=941b96e6ab) | Jun 22, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [d5fd58e3b0](https://linux-hardware.org/?probe=d5fd58e3b0) | Jun 21, 2022 |
| ASUSTek       | PRIME Z370-A                | [8dca736a46](https://linux-hardware.org/?probe=8dca736a46) | Jun 21, 2022 |
| ASUSTek       | P7H55-M LX                  | [f747d1bfd3](https://linux-hardware.org/?probe=f747d1bfd3) | Jun 21, 2022 |
| System76      | Thelio thelio-r2            | [b9b9d5ffda](https://linux-hardware.org/?probe=b9b9d5ffda) | Jun 21, 2022 |
| MSI           | B550M-A PRO                 | [1765b91360](https://linux-hardware.org/?probe=1765b91360) | Jun 21, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [6ddca91c97](https://linux-hardware.org/?probe=6ddca91c97) | Jun 21, 2022 |
| Biostar       | N68S3+                      | [efe83d16ac](https://linux-hardware.org/?probe=efe83d16ac) | Jun 21, 2022 |
| Intel         | MAHOBAY                     | [f615165669](https://linux-hardware.org/?probe=f615165669) | Jun 21, 2022 |
| ASRock        | B450 Gaming K4              | [230bdf84a1](https://linux-hardware.org/?probe=230bdf84a1) | Jun 20, 2022 |
| MSI           | MPG Z490 GAMING PLUS        | [ec3bc83e7a](https://linux-hardware.org/?probe=ec3bc83e7a) | Jun 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [d5af99ece6](https://linux-hardware.org/?probe=d5af99ece6) | Jun 20, 2022 |
| ASUSTek       | P8Z77-V LX                  | [ad271e0eec](https://linux-hardware.org/?probe=ad271e0eec) | Jun 19, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | [3d4d492e9d](https://linux-hardware.org/?probe=3d4d492e9d) | Jun 19, 2022 |
| Dell          | 0YXT71 A03                  | [890e65c781](https://linux-hardware.org/?probe=890e65c781) | Jun 19, 2022 |
| HP            | 158B                        | [b66a2770e7](https://linux-hardware.org/?probe=b66a2770e7) | Jun 18, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6ba04b0f37](https://linux-hardware.org/?probe=6ba04b0f37) | Jun 18, 2022 |
| BESSTAR Te... | UM700                       | [d0c247db91](https://linux-hardware.org/?probe=d0c247db91) | Jun 17, 2022 |
| Intel         | MAHOBAY                     | [755ead951d](https://linux-hardware.org/?probe=755ead951d) | Jun 17, 2022 |
| Gigabyte      | B450M DS3H WIFI-CF          | [5241a60357](https://linux-hardware.org/?probe=5241a60357) | Jun 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [f4178c276d](https://linux-hardware.org/?probe=f4178c276d) | Jun 16, 2022 |
| Intel         | MAHOBAY                     | [91039940ea](https://linux-hardware.org/?probe=91039940ea) | Jun 16, 2022 |
| Lenovo        | 3715 SDK0L77769 WIN 3423... | [16d122d03e](https://linux-hardware.org/?probe=16d122d03e) | Jun 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [24140a62de](https://linux-hardware.org/?probe=24140a62de) | Jun 16, 2022 |
| Foxconn       | G41MX/G41MX-K 2.0 1.0       | [f5af934210](https://linux-hardware.org/?probe=f5af934210) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| MSI           | B450 TOMAHAWK               | [e11d001f52](https://linux-hardware.org/?probe=e11d001f52) | Jun 15, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [29cfeda814](https://linux-hardware.org/?probe=29cfeda814) | Jun 15, 2022 |
| Gigabyte      | 970A-DS3P                   | [b12643d9ac](https://linux-hardware.org/?probe=b12643d9ac) | Jun 15, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [d4e4001c4c](https://linux-hardware.org/?probe=d4e4001c4c) | Jun 15, 2022 |
| Medion        | MS-7728                     | [ae02539c17](https://linux-hardware.org/?probe=ae02539c17) | Jun 15, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | [5be4039515](https://linux-hardware.org/?probe=5be4039515) | Jun 15, 2022 |
| ASUSTek       | TUF X299 MARK 2             | [507c214577](https://linux-hardware.org/?probe=507c214577) | Jun 15, 2022 |
| MSI           | B550-A PRO                  | [f7201ee1de](https://linux-hardware.org/?probe=f7201ee1de) | Jun 14, 2022 |
| HP            | 1905                        | [b3d0170095](https://linux-hardware.org/?probe=b3d0170095) | Jun 14, 2022 |
| HP            | 18E7                        | [9f82638329](https://linux-hardware.org/?probe=9f82638329) | Jun 14, 2022 |
| Lenovo        | 0B98401 PRO                 | [23de86aa97](https://linux-hardware.org/?probe=23de86aa97) | Jun 14, 2022 |
| Alienware     | 0R3FWM A00                  | [6690a39447](https://linux-hardware.org/?probe=6690a39447) | Jun 13, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [f9e74fdcd3](https://linux-hardware.org/?probe=f9e74fdcd3) | Jun 13, 2022 |
| Dell          | 073MMW A03                  | [3e206d2462](https://linux-hardware.org/?probe=3e206d2462) | Jun 13, 2022 |
| ASUSTek       | Z87-K                       | [cafc34944d](https://linux-hardware.org/?probe=cafc34944d) | Jun 13, 2022 |
| MSI           | B350 PC MATE                | [baf792ad50](https://linux-hardware.org/?probe=baf792ad50) | Jun 12, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [a332c946a2](https://linux-hardware.org/?probe=a332c946a2) | Jun 11, 2022 |
| Gigabyte      | G1.Sniper M3-CF             | [d02f89642d](https://linux-hardware.org/?probe=d02f89642d) | Jun 11, 2022 |
| ASUSTek       | ROG STRIX B560-F GAMING ... | [a4277bcba9](https://linux-hardware.org/?probe=a4277bcba9) | Jun 11, 2022 |
| MSI           | MEG X570 ACE                | [d88374c06d](https://linux-hardware.org/?probe=d88374c06d) | Jun 11, 2022 |
| Unknown       | Unknown                     | [19d1362c66](https://linux-hardware.org/?probe=19d1362c66) | Jun 10, 2022 |
| Gigabyte      | H87M-HD3                    | [eadd724efa](https://linux-hardware.org/?probe=eadd724efa) | Jun 10, 2022 |
| MSI           | H97 GAMING 3                | [839bbee3fa](https://linux-hardware.org/?probe=839bbee3fa) | Jun 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [1fef4f1cf3](https://linux-hardware.org/?probe=1fef4f1cf3) | Jun 10, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [9c7b34c996](https://linux-hardware.org/?probe=9c7b34c996) | Jun 09, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [44a6f3e33d](https://linux-hardware.org/?probe=44a6f3e33d) | Jun 07, 2022 |
| Gigabyte      | Z390 UD                     | [cd4b8b609f](https://linux-hardware.org/?probe=cd4b8b609f) | Jun 07, 2022 |
| Dell          | 0JW6C6 A01                  | [34d9fc3968](https://linux-hardware.org/?probe=34d9fc3968) | Jun 06, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [a0c155ffb9](https://linux-hardware.org/?probe=a0c155ffb9) | Jun 05, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [816b4e757d](https://linux-hardware.org/?probe=816b4e757d) | Jun 05, 2022 |
| ASUSTek       | Rampage V EDITION 10        | [e92e195362](https://linux-hardware.org/?probe=e92e195362) | Jun 05, 2022 |
| ASUSTek       | P8Z68-V LX                  | [e7e3608105](https://linux-hardware.org/?probe=e7e3608105) | Jun 04, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | [a65dd5834e](https://linux-hardware.org/?probe=a65dd5834e) | Jun 04, 2022 |
| ASUSTek       | P6X58D PREMIUM              | [81bfe17cb5](https://linux-hardware.org/?probe=81bfe17cb5) | Jun 04, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | [95db56a864](https://linux-hardware.org/?probe=95db56a864) | Jun 03, 2022 |
| ASUSTek       | Z87-K                       | [915e2819c0](https://linux-hardware.org/?probe=915e2819c0) | Jun 02, 2022 |
| ASRock        | Z390 Phantom Gaming SLI/... | [5f40da7ae9](https://linux-hardware.org/?probe=5f40da7ae9) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [5348dd6576](https://linux-hardware.org/?probe=5348dd6576) | Jun 01, 2022 |
| ASUSTek       | PRIME Z590-A                | [fa29e357fa](https://linux-hardware.org/?probe=fa29e357fa) | Jun 01, 2022 |
| ASUSTek       | F2A85-M                     | [82b4935292](https://linux-hardware.org/?probe=82b4935292) | Jun 01, 2022 |
| MSI           | Z170A MPOWER GAMING TITA... | [538feade4f](https://linux-hardware.org/?probe=538feade4f) | May 31, 2022 |
| ASUSTek       | PRIME A320M-K               | [bee74ec003](https://linux-hardware.org/?probe=bee74ec003) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [136730f4ac](https://linux-hardware.org/?probe=136730f4ac) | May 31, 2022 |
| ASRock        | B450 Steel Legend           | [62b7e9aacd](https://linux-hardware.org/?probe=62b7e9aacd) | May 31, 2022 |
| System76      | Thelio Major thelio-majo... | [291730a3bb](https://linux-hardware.org/?probe=291730a3bb) | May 31, 2022 |
| Dell          | 0Y2MRG A00                  | [013e0da975](https://linux-hardware.org/?probe=013e0da975) | May 30, 2022 |
| Dell          | 0D02VH A01                  | [fc97b0a5bf](https://linux-hardware.org/?probe=fc97b0a5bf) | May 30, 2022 |
| ASUSTek       | PRIME Z590-A                | [1058cdf867](https://linux-hardware.org/?probe=1058cdf867) | May 30, 2022 |
| HP            | 8266                        | [d0e35451ab](https://linux-hardware.org/?probe=d0e35451ab) | May 29, 2022 |
| Gigabyte      | H270-Gaming 3               | [c28c21c4d8](https://linux-hardware.org/?probe=c28c21c4d8) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [5d899f8fc5](https://linux-hardware.org/?probe=5d899f8fc5) | May 29, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d1923db949](https://linux-hardware.org/?probe=d1923db949) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [b78390767c](https://linux-hardware.org/?probe=b78390767c) | May 28, 2022 |
| MSI           | MS-7717                     | [101b488b80](https://linux-hardware.org/?probe=101b488b80) | May 28, 2022 |
| MSI           | MS-7717                     | [9b0c2d0d8c](https://linux-hardware.org/?probe=9b0c2d0d8c) | May 28, 2022 |
| ASRock        | B450 Steel Legend           | [5d47d967ba](https://linux-hardware.org/?probe=5d47d967ba) | May 28, 2022 |
| Dell          | 040DDP A01                  | [925d3dce8d](https://linux-hardware.org/?probe=925d3dce8d) | May 28, 2022 |
| HP            | 158B                        | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | [bdf54228e5](https://linux-hardware.org/?probe=bdf54228e5) | May 27, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [f5195788f8](https://linux-hardware.org/?probe=f5195788f8) | May 27, 2022 |
| ASUSTek       | PRIME Z270-A                | [5d1ee4048a](https://linux-hardware.org/?probe=5d1ee4048a) | May 27, 2022 |
| ASUSTek       | P5KPL-SE                    | [c4b27d79ef](https://linux-hardware.org/?probe=c4b27d79ef) | May 26, 2022 |
| ASUSTek       | P5QPL-AM                    | [938ab3ec5c](https://linux-hardware.org/?probe=938ab3ec5c) | May 26, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [ae0ada290a](https://linux-hardware.org/?probe=ae0ada290a) | May 26, 2022 |
| ASRock        | H670M-ITX/ax                | [b3f7ff3d98](https://linux-hardware.org/?probe=b3f7ff3d98) | May 25, 2022 |
| ASUSTek       | M5A78L/USB3                 | [852a292ba3](https://linux-hardware.org/?probe=852a292ba3) | May 25, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [4738560555](https://linux-hardware.org/?probe=4738560555) | May 25, 2022 |
| HP            | 8703                        | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| ASRock        | H470M-ITX/ac                | [181f7decc6](https://linux-hardware.org/?probe=181f7decc6) | May 24, 2022 |
| Dell          | 0Y2MRG A00                  | [08527b166e](https://linux-hardware.org/?probe=08527b166e) | May 24, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | [1122022ae1](https://linux-hardware.org/?probe=1122022ae1) | May 24, 2022 |
| SIEMENS       | A5E02122237 ES010           | [3d7173e7a3](https://linux-hardware.org/?probe=3d7173e7a3) | May 24, 2022 |
| Lenovo        | MAHOBAY                     | [dbfb736222](https://linux-hardware.org/?probe=dbfb736222) | May 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [78bb2ba75c](https://linux-hardware.org/?probe=78bb2ba75c) | May 23, 2022 |
| Foxconn       | 2ABF                        | [39f9e9e717](https://linux-hardware.org/?probe=39f9e9e717) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [21818b99b4](https://linux-hardware.org/?probe=21818b99b4) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [f1db82519f](https://linux-hardware.org/?probe=f1db82519f) | May 22, 2022 |
| MSI           | MEG Z390 ACE                | [0065576586](https://linux-hardware.org/?probe=0065576586) | May 22, 2022 |
| Gigabyte      | H67N-USB3-B3                | [382f206597](https://linux-hardware.org/?probe=382f206597) | May 21, 2022 |
| ASRock        | B450 Steel Legend           | [3c436952c7](https://linux-hardware.org/?probe=3c436952c7) | May 21, 2022 |
| ASUSTek       | P7P55D-E LX                 | [358e85c524](https://linux-hardware.org/?probe=358e85c524) | May 21, 2022 |
| MSI           | B250M PRO-VD                | [540e0831b1](https://linux-hardware.org/?probe=540e0831b1) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [a810336f3f](https://linux-hardware.org/?probe=a810336f3f) | May 20, 2022 |
| ASRock        | TRX40 Creator               | [6993400976](https://linux-hardware.org/?probe=6993400976) | May 20, 2022 |
| Gigabyte      | GA-78LMT-S2P                | [2211d5c2a2](https://linux-hardware.org/?probe=2211d5c2a2) | May 20, 2022 |
| ASUSTek       | H110M-R                     | [7cae58580a](https://linux-hardware.org/?probe=7cae58580a) | May 20, 2022 |
| ASRock        | Z390 Phantom Gaming 4-IB    | [543ab770e8](https://linux-hardware.org/?probe=543ab770e8) | May 20, 2022 |
| Positivo      | POS-MI945AA                 | [0f9875e8fc](https://linux-hardware.org/?probe=0f9875e8fc) | May 19, 2022 |
| Lenovo        | MAHOBAY                     | [fa1f318919](https://linux-hardware.org/?probe=fa1f318919) | May 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [d94f4b0a43](https://linux-hardware.org/?probe=d94f4b0a43) | May 19, 2022 |
| Gigabyte      | B450 AORUS M                | [5ddfbf547b](https://linux-hardware.org/?probe=5ddfbf547b) | May 19, 2022 |
| Supermicro    | X8SIL                       | [66e8a4001f](https://linux-hardware.org/?probe=66e8a4001f) | May 18, 2022 |
| MSI           | B350M MORTAR                | [fd66fd9a5a](https://linux-hardware.org/?probe=fd66fd9a5a) | May 18, 2022 |
| Supermicro    | X8SIL                       | [5cb6f1067b](https://linux-hardware.org/?probe=5cb6f1067b) | May 18, 2022 |
| HP            | 8054                        | [725f204fd0](https://linux-hardware.org/?probe=725f204fd0) | May 18, 2022 |
| ASUSTek       | GA15DH                      | [ca68812bf2](https://linux-hardware.org/?probe=ca68812bf2) | May 17, 2022 |
| MSI           | Z270-A PRO                  | [f005623f03](https://linux-hardware.org/?probe=f005623f03) | May 17, 2022 |
| ASUSTek       | AM1M-A/BR                   | [e23e8291e0](https://linux-hardware.org/?probe=e23e8291e0) | May 17, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | [2f7a99c28b](https://linux-hardware.org/?probe=2f7a99c28b) | May 17, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [ee4e4a7bc7](https://linux-hardware.org/?probe=ee4e4a7bc7) | May 17, 2022 |
| Dell          | 040DDP A00                  | [4806ca2a7e](https://linux-hardware.org/?probe=4806ca2a7e) | May 17, 2022 |
| Gigabyte      | H310M S2H x.x               | [4d76b03e66](https://linux-hardware.org/?probe=4d76b03e66) | May 17, 2022 |
| ASUSTek       | Z87-K                       | [2daea316b2](https://linux-hardware.org/?probe=2daea316b2) | May 16, 2022 |
| MSI           | MPG X570 GAMING PLUS        | [91d8b47a30](https://linux-hardware.org/?probe=91d8b47a30) | May 15, 2022 |
| ASRock        | B550 Phantom Gaming-ITX/... | [608664ce7a](https://linux-hardware.org/?probe=608664ce7a) | May 15, 2022 |
| Dell          | 0CRH6C A02                  | [655afd62e6](https://linux-hardware.org/?probe=655afd62e6) | May 14, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [a049c51989](https://linux-hardware.org/?probe=a049c51989) | May 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | [cb7b6b9cde](https://linux-hardware.org/?probe=cb7b6b9cde) | May 14, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [0cc824e2a5](https://linux-hardware.org/?probe=0cc824e2a5) | May 13, 2022 |
| NZXT          | N7 B550                     | [73441bbfc4](https://linux-hardware.org/?probe=73441bbfc4) | May 12, 2022 |
| Unknown       | BTC79X5                     | [42b222eb65](https://linux-hardware.org/?probe=42b222eb65) | May 12, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| AZW           | BT3 X                       | [a17cb64acb](https://linux-hardware.org/?probe=a17cb64acb) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [ee225906fc](https://linux-hardware.org/?probe=ee225906fc) | May 12, 2022 |
| Lenovo        | 0B98401 PRO                 | [16911d5e64](https://linux-hardware.org/?probe=16911d5e64) | May 11, 2022 |
| Gigabyte      | B660 AORUS MASTER DDR4      | [e5981a9f20](https://linux-hardware.org/?probe=e5981a9f20) | May 11, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [1d4364ac51](https://linux-hardware.org/?probe=1d4364ac51) | May 10, 2022 |
| NZXT          | N7 B550                     | [147247dfb6](https://linux-hardware.org/?probe=147247dfb6) | May 10, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [396a39e5a6](https://linux-hardware.org/?probe=396a39e5a6) | May 10, 2022 |
| ASRock        | X370 Professional Gaming    | [1e22ba0468](https://linux-hardware.org/?probe=1e22ba0468) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [0b3cda16db](https://linux-hardware.org/?probe=0b3cda16db) | May 10, 2022 |
| ASUSTek       | PRIME B450M-A               | [90190717eb](https://linux-hardware.org/?probe=90190717eb) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| ASUSTek       | Z97-AR                      | [29c93ea162](https://linux-hardware.org/?probe=29c93ea162) | May 09, 2022 |
| Gigabyte      | B450 AORUS M                | [cd1aff125e](https://linux-hardware.org/?probe=cd1aff125e) | May 09, 2022 |
| SIEMENS       | A5E02122237 ES010           | [cc728f6c38](https://linux-hardware.org/?probe=cc728f6c38) | May 09, 2022 |
| ASRock        | X299 Taichi CLX             | [47a45fca48](https://linux-hardware.org/?probe=47a45fca48) | May 08, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8964a4c5ec](https://linux-hardware.org/?probe=8964a4c5ec) | May 08, 2022 |
| ECS           | Nettle3                     | [36f8cde007](https://linux-hardware.org/?probe=36f8cde007) | May 08, 2022 |
| ASUSTek       | PRIME X570-P                | [65d94c8458](https://linux-hardware.org/?probe=65d94c8458) | May 08, 2022 |
| ECS           | Nettle3                     | [646fb53a2c](https://linux-hardware.org/?probe=646fb53a2c) | May 07, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [61a4daec98](https://linux-hardware.org/?probe=61a4daec98) | May 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [180dd73bd6](https://linux-hardware.org/?probe=180dd73bd6) | May 07, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [f71ca35596](https://linux-hardware.org/?probe=f71ca35596) | May 06, 2022 |
| MSI           | B450-A PRO                  | [5b5ceb0f53](https://linux-hardware.org/?probe=5b5ceb0f53) | May 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| ASRock        | 970M Pro3                   | [2853128cd0](https://linux-hardware.org/?probe=2853128cd0) | May 05, 2022 |
| ASRock        | 970M Pro3                   | [5f51fd4cf8](https://linux-hardware.org/?probe=5f51fd4cf8) | May 05, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7b7f29e504](https://linux-hardware.org/?probe=7b7f29e504) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [e133868179](https://linux-hardware.org/?probe=e133868179) | May 05, 2022 |
| ASRock        | X470 Taichi                 | [93d6fb1610](https://linux-hardware.org/?probe=93d6fb1610) | May 05, 2022 |
| ASRock        | A320M-HDV R4.0              | [36cabd86ba](https://linux-hardware.org/?probe=36cabd86ba) | May 04, 2022 |
| ASUSTek       | B85M-E                      | [2b6338d755](https://linux-hardware.org/?probe=2b6338d755) | May 04, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [7196bf2ec6](https://linux-hardware.org/?probe=7196bf2ec6) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [f20f31b107](https://linux-hardware.org/?probe=f20f31b107) | May 03, 2022 |
| ASRock        | 970M Pro3                   | [73a563257a](https://linux-hardware.org/?probe=73a563257a) | May 03, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [65a2309744](https://linux-hardware.org/?probe=65a2309744) | May 03, 2022 |
| Alienware     | 0CPDXD A00                  | [17da14a17d](https://linux-hardware.org/?probe=17da14a17d) | May 03, 2022 |
| ASUSTek       | B85M-E                      | [9645231d87](https://linux-hardware.org/?probe=9645231d87) | May 03, 2022 |
| MSI           | B450I GAMING PLUS AC        | [c0ef0738b5](https://linux-hardware.org/?probe=c0ef0738b5) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [4a09f5d3f3](https://linux-hardware.org/?probe=4a09f5d3f3) | May 02, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [ab716981c3](https://linux-hardware.org/?probe=ab716981c3) | May 02, 2022 |
| Alienware     | 0P0JWX A00                  | [e6e1548aa1](https://linux-hardware.org/?probe=e6e1548aa1) | May 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | [a456619489](https://linux-hardware.org/?probe=a456619489) | May 02, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [dec71580c4](https://linux-hardware.org/?probe=dec71580c4) | May 01, 2022 |
| Gigabyte      | X570S AERO G                | [ab6b8eaa71](https://linux-hardware.org/?probe=ab6b8eaa71) | May 01, 2022 |
| MSI           | 970 GAMING                  | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ecc527cb4b](https://linux-hardware.org/?probe=ecc527cb4b) | May 01, 2022 |
| ASRock        | B450 Steel Legend           | [ca217fe968](https://linux-hardware.org/?probe=ca217fe968) | May 01, 2022 |
| MSI           | B450M GAMING PLUS           | [0929d58de7](https://linux-hardware.org/?probe=0929d58de7) | Apr 30, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | [3edd5f05f7](https://linux-hardware.org/?probe=3edd5f05f7) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [d45e1e88db](https://linux-hardware.org/?probe=d45e1e88db) | Apr 30, 2022 |
| ASRock        | X99 Extreme4                | [41cec63ac6](https://linux-hardware.org/?probe=41cec63ac6) | Apr 30, 2022 |
| EVGA          | X58 SLI Classified Tyler... | [07254f2dbb](https://linux-hardware.org/?probe=07254f2dbb) | Apr 30, 2022 |
| ASUSTek       | PRIME H510M-E               | [5c9e5fc14c](https://linux-hardware.org/?probe=5c9e5fc14c) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | [bce425f138](https://linux-hardware.org/?probe=bce425f138) | Apr 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [7b292b972d](https://linux-hardware.org/?probe=7b292b972d) | Apr 29, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e37bc471b1](https://linux-hardware.org/?probe=e37bc471b1) | Apr 29, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | [2b7167b16e](https://linux-hardware.org/?probe=2b7167b16e) | Apr 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [aed5ee3ded](https://linux-hardware.org/?probe=aed5ee3ded) | Apr 28, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ab83eedd1f](https://linux-hardware.org/?probe=ab83eedd1f) | Apr 28, 2022 |
| MSI           | H55M-E23                    | [4ab5f58470](https://linux-hardware.org/?probe=4ab5f58470) | Apr 28, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [46430e1117](https://linux-hardware.org/?probe=46430e1117) | Apr 28, 2022 |
| Dell          | 09KPNV A00                  | [5046e0575b](https://linux-hardware.org/?probe=5046e0575b) | Apr 28, 2022 |
| Dell          | 0NW73C A00                  | [344e2b816e](https://linux-hardware.org/?probe=344e2b816e) | Apr 28, 2022 |
| Dell          | 088DT1 A01                  | [b664b8720e](https://linux-hardware.org/?probe=b664b8720e) | Apr 28, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [19e0445e6f](https://linux-hardware.org/?probe=19e0445e6f) | Apr 27, 2022 |
| Dell          | 0R1PCR A00                  | [feec38a0f5](https://linux-hardware.org/?probe=feec38a0f5) | Apr 27, 2022 |
| Unknown       | Unknown                     | [82ad7e86b5](https://linux-hardware.org/?probe=82ad7e86b5) | Apr 27, 2022 |
| ASUSTek       | GA15DH                      | [30a22d7be3](https://linux-hardware.org/?probe=30a22d7be3) | Apr 27, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | [4b9faf4848](https://linux-hardware.org/?probe=4b9faf4848) | Apr 26, 2022 |
| System76      | Thelio thelio-r2            | [aae937be8b](https://linux-hardware.org/?probe=aae937be8b) | Apr 25, 2022 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [fabaa5b3ab](https://linux-hardware.org/?probe=fabaa5b3ab) | Apr 24, 2022 |
| MSI           | B250M BAZOOKA               | [91392a601e](https://linux-hardware.org/?probe=91392a601e) | Apr 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Desktops | Percent |
|---------------------------|----------|---------|
| 5.17.5-76051705-generic   | 155      | 30.57%  |
| 5.19.0-76051900-generic   | 137      | 27.02%  |
| 5.18.10-76051810-generic  | 70       | 13.81%  |
| 5.17.15-76051715-generic  | 64       | 12.62%  |
| 5.16.19-76051619-generic  | 40       | 7.89%   |
| 5.19.16-76051916-generic  | 17       | 3.35%   |
| 6.0.2-76060002-generic    | 15       | 2.96%   |
| 6.0.3-76060003-generic    | 1        | 0.2%    |
| 6.0.2-x64v1-xanmod1       | 1        | 0.2%    |
| 5.4.210-whitehax0r        | 1        | 0.2%    |
| 5.19.6-xanmod1-x64v2      | 1        | 0.2%    |
| 5.18.0-9.1-liquorix-amd64 | 1        | 0.2%    |
| 5.17.4-051704-generic     | 1        | 0.2%    |
| 5.17.14-xanmod1           | 1        | 0.2%    |
| 5.16.15-76051615-generic  | 1        | 0.2%    |
| 5.15.15-76051515-generic  | 1        | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.5  | 155      | 30.57%  |
| 5.19.0  | 137      | 27.02%  |
| 5.18.10 | 70       | 13.81%  |
| 5.17.15 | 64       | 12.62%  |
| 5.16.19 | 40       | 7.89%   |
| 5.19.16 | 17       | 3.35%   |
| 6.0.2   | 16       | 3.16%   |
| 6.0.3   | 1        | 0.2%    |
| 5.4.210 | 1        | 0.2%    |
| 5.19.6  | 1        | 0.2%    |
| 5.18.0  | 1        | 0.2%    |
| 5.17.4  | 1        | 0.2%    |
| 5.17.14 | 1        | 0.2%    |
| 5.16.15 | 1        | 0.2%    |
| 5.15.15 | 1        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17    | 214      | 42.89%  |
| 5.19    | 154      | 30.86%  |
| 5.18    | 71       | 14.23%  |
| 5.16    | 41       | 8.22%   |
| 6.0     | 17       | 3.41%   |
| 5.4     | 1        | 0.2%    |
| 5.15    | 1        | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 474      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 454      | 95.78%  |
| KDE5            | 12       | 2.53%   |
| X-Cinnamon      | 3        | 0.63%   |
| Unknown         | 2        | 0.42%   |
| LXQt            | 1        | 0.21%   |
| GNOME Flashback | 1        | 0.21%   |
| Cinnamon        | 1        | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 465      | 98.1%   |
| Wayland | 7        | 1.48%   |
| Tty     | 1        | 0.21%   |
| Unknown | 1        | 0.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 398      | 83.97%  |
| GDM3    | 70       | 14.77%  |
| SDDM    | 4        | 0.84%   |
| GDM     | 2        | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 277      | 58.32%  |
| en_GB   | 29       | 6.11%   |
| pt_BR   | 28       | 5.89%   |
| de_DE   | 21       | 4.42%   |
| C       | 19       | 4%      |
| en_CA   | 14       | 2.95%   |
| fr_FR   | 12       | 2.53%   |
| en_AU   | 12       | 2.53%   |
| it_IT   | 9        | 1.89%   |
| pl_PL   | 6        | 1.26%   |
| es_ES   | 6        | 1.26%   |
| sv_SE   | 4        | 0.84%   |
| nl_NL   | 3        | 0.63%   |
| fi_FI   | 3        | 0.63%   |
| es_CL   | 3        | 0.63%   |
| en_IN   | 3        | 0.63%   |
| Unknown | 3        | 0.63%   |
| zh_TW   | 2        | 0.42%   |
| ja_JP   | 2        | 0.42%   |
| en_DK   | 2        | 0.42%   |
| de_AT   | 2        | 0.42%   |
| cs_CZ   | 2        | 0.42%   |
| ru_RU   | 1        | 0.21%   |
| ro_RO   | 1        | 0.21%   |
| pt_PT   | 1        | 0.21%   |
| nl_BE   | 1        | 0.21%   |
| nb_NO   | 1        | 0.21%   |
| fr_CH   | 1        | 0.21%   |
| fr_BE   | 1        | 0.21%   |
| es_UY   | 1        | 0.21%   |
| es_DO   | 1        | 0.21%   |
| en_IL   | 1        | 0.21%   |
| en_IE   | 1        | 0.21%   |
| en_FI   | 1        | 0.21%   |
| da_DK   | 1        | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 408      | 86.08%  |
| EFI  | 66       | 13.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 450      | 94.94%  |
| Overlay | 12       | 2.53%   |
| Btrfs   | 11       | 2.32%   |
| Xfs     | 1        | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 396      | 83.54%  |
| GPT     | 73       | 15.4%   |
| MBR     | 5        | 1.05%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 457      | 96.41%  |
| Yes       | 17       | 3.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 423      | 89.24%  |
| Yes       | 51       | 10.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 146      | 30.8%   |
| Gigabyte Technology | 90       | 18.99%  |
| MSI                 | 71       | 14.98%  |
| ASRock              | 41       | 8.65%   |
| Dell                | 31       | 6.54%   |
| Hewlett-Packard     | 24       | 5.06%   |
| Lenovo              | 18       | 3.8%    |
| Intel               | 8        | 1.69%   |
| System76            | 5        | 1.05%   |
| Alienware           | 5        | 1.05%   |
| Unknown             | 4        | 0.84%   |
| MACHINIST           | 3        | 0.63%   |
| Acer                | 3        | 0.63%   |
| Pegatron            | 2        | 0.42%   |
| NZXT                | 2        | 0.42%   |
| Fujitsu             | 2        | 0.42%   |
| Foxconn             | 2        | 0.42%   |
| EVGA                | 2        | 0.42%   |
| ECS                 | 2        | 0.42%   |
| BESSTAR Tech        | 2        | 0.42%   |
| Supermicro          | 1        | 0.21%   |
| Soyo                | 1        | 0.21%   |
| SIEMENS             | 1        | 0.21%   |
| Positivo            | 1        | 0.21%   |
| Minix               | 1        | 0.21%   |
| Medion              | 1        | 0.21%   |
| LattePanda          | 1        | 0.21%   |
| Biostar             | 1        | 0.21%   |
| AZW                 | 1        | 0.21%   |
| Apple               | 1        | 0.21%   |
| Acidanthera         | 1        | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                              | Desktops | Percent |
|-----------------------------------|----------|---------|
| ASUS All Series                   | 11       | 2.32%   |
| Gigabyte B450 AORUS M             | 6        | 1.27%   |
| ASUS TUF Gaming B550-PLUS         | 6        | 1.27%   |
| Gigabyte X570 AORUS ELITE         | 5        | 1.05%   |
| ASUS ROG STRIX B550-I GAMING      | 5        | 1.05%   |
| ASUS ROG STRIX B550-F GAMING      | 5        | 1.05%   |
| ASUS ROG STRIX B450-F GAMING      | 5        | 1.05%   |
| MSI MS-7B86                       | 4        | 0.84%   |
| Gigabyte B450M DS3H               | 4        | 0.84%   |
| ASUS ROG CROSSHAIR VIII DARK HERO | 4        | 0.84%   |
| ASUS PRIME B450M-A                | 4        | 0.84%   |
| Unknown                           | 4        | 0.84%   |
| System76 Thelio                   | 3        | 0.63%   |
| MSI MS-7D54                       | 3        | 0.63%   |
| MSI MS-7D25                       | 3        | 0.63%   |
| MSI MS-7C37                       | 3        | 0.63%   |
| MSI MS-7C35                       | 3        | 0.63%   |
| MSI MS-7C02                       | 3        | 0.63%   |
| MSI MS-7693                       | 3        | 0.63%   |
| HP Compaq Elite 8300 USDT         | 3        | 0.63%   |
| Gigabyte X570 AORUS MASTER        | 3        | 0.63%   |
| Gigabyte B550 AORUS ELITE V2      | 3        | 0.63%   |
| Dell OptiPlex 3020                | 3        | 0.63%   |
| ASUS TUF Gaming B550M-PLUS        | 3        | 0.63%   |
| ASUS ROG CROSSHAIR VIII HERO      | 3        | 0.63%   |
| ASUS P6X58D PREMIUM               | 3        | 0.63%   |
| ASRock B450 Gaming K4             | 3        | 0.63%   |
| NZXT N7 B550                      | 2        | 0.42%   |
| MSI MS-7D32                       | 2        | 0.42%   |
| MSI MS-7D09                       | 2        | 0.42%   |
| MSI MS-7C91                       | 2        | 0.42%   |
| MSI MS-7C56                       | 2        | 0.42%   |
| MSI MS-7B89                       | 2        | 0.42%   |
| MSI MS-7B17                       | 2        | 0.42%   |
| MSI MS-7B12                       | 2        | 0.42%   |
| MSI MS-7A32                       | 2        | 0.42%   |
| HP ProDesk 600 G1 SFF             | 2        | 0.42%   |
| HP EliteDesk 705 G1 SFF           | 2        | 0.42%   |
| Gigabyte Z170-HD3P                | 2        | 0.42%   |
| Gigabyte Z170-Gaming K3           | 2        | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 48       | 10.13%  |
| ASUS PRIME             | 25       | 5.27%   |
| ASUS TUF               | 23       | 4.85%   |
| Lenovo ThinkCentre     | 12       | 2.53%   |
| Gigabyte X570          | 12       | 2.53%   |
| Dell OptiPlex          | 12       | 2.53%   |
| ASUS All               | 11       | 2.32%   |
| HP Compaq              | 10       | 2.11%   |
| Gigabyte B450          | 9        | 1.9%    |
| Dell Precision         | 9        | 1.9%    |
| HP EliteDesk           | 6        | 1.27%   |
| Gigabyte B550          | 6        | 1.27%   |
| Gigabyte B450M         | 6        | 1.27%   |
| System76 Thelio        | 5        | 1.05%   |
| Dell Inspiron          | 5        | 1.05%   |
| ASRock B450            | 5        | 1.05%   |
| Alienware Aurora       | 5        | 1.05%   |
| MSI MS-7B86            | 4        | 0.84%   |
| Dell XPS               | 4        | 0.84%   |
| ASRock X570            | 4        | 0.84%   |
| ASRock B450M           | 4        | 0.84%   |
| Unknown                | 4        | 0.84%   |
| MSI MS-7D54            | 3        | 0.63%   |
| MSI MS-7D25            | 3        | 0.63%   |
| MSI MS-7C37            | 3        | 0.63%   |
| MSI MS-7C35            | 3        | 0.63%   |
| MSI MS-7C02            | 3        | 0.63%   |
| MSI MS-7693            | 3        | 0.63%   |
| Lenovo IdeaCentre      | 3        | 0.63%   |
| Gigabyte H310M         | 3        | 0.63%   |
| Gigabyte GA-78LMT-USB3 | 3        | 0.63%   |
| Gigabyte B550M         | 3        | 0.63%   |
| Gigabyte AB350-Gaming  | 3        | 0.63%   |
| ASUS P6X58D            | 3        | 0.63%   |
| NZXT N7                | 2        | 0.42%   |
| MSI MS-7D32            | 2        | 0.42%   |
| MSI MS-7D09            | 2        | 0.42%   |
| MSI MS-7C91            | 2        | 0.42%   |
| MSI MS-7C56            | 2        | 0.42%   |
| MSI MS-7B89            | 2        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 73       | 15.4%   |
| 2020 | 69       | 14.56%  |
| 2019 | 53       | 11.18%  |
| 2021 | 51       | 10.76%  |
| 2014 | 31       | 6.54%   |
| 2012 | 29       | 6.12%   |
| 2017 | 25       | 5.27%   |
| 2013 | 25       | 5.27%   |
| 2016 | 23       | 4.85%   |
| 2011 | 21       | 4.43%   |
| 2022 | 20       | 4.22%   |
| 2010 | 16       | 3.38%   |
| 2015 | 14       | 2.95%   |
| 2009 | 12       | 2.53%   |
| 2008 | 6        | 1.27%   |
| 2007 | 5        | 1.05%   |
| 2006 | 1        | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 474      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 473      | 99.79%  |
| Enabled  | 1        | 0.21%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 474      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 157      | 32.64%  |
| 32.01-64.0      | 133      | 27.65%  |
| 8.01-16.0       | 74       | 15.38%  |
| 64.01-256.0     | 44       | 9.15%   |
| 4.01-8.0        | 40       | 8.32%   |
| 3.01-4.0        | 21       | 4.37%   |
| 24.01-32.0      | 8        | 1.66%   |
| More than 256.0 | 2        | 0.42%   |
| 2.01-3.0        | 1        | 0.21%   |
| 1.01-2.0        | 1        | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 141      | 27.7%   |
| 2.01-3.0    | 141      | 27.7%   |
| 3.01-4.0    | 122      | 23.97%  |
| 1.01-2.0    | 59       | 11.59%  |
| 8.01-16.0   | 31       | 6.09%   |
| 16.01-24.0  | 10       | 1.96%   |
| 32.01-64.0  | 4        | 0.79%   |
| 64.01-256.0 | 1        | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 154      | 32.29%  |
| 1      | 128      | 26.83%  |
| 3      | 101      | 21.17%  |
| 4      | 42       | 8.81%   |
| 5      | 23       | 4.82%   |
| 6      | 15       | 3.14%   |
| 7      | 6        | 1.26%   |
| 9      | 3        | 0.63%   |
| 10     | 2        | 0.42%   |
| 19     | 1        | 0.21%   |
| 11     | 1        | 0.21%   |
| 0      | 1        | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 344      | 72.42%  |
| Yes       | 131      | 27.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 467      | 98.52%  |
| No        | 7        | 1.48%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 265      | 55.79%  |
| No        | 210      | 44.21%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 260      | 54.62%  |
| Yes       | 216      | 45.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 183      | 38.36%  |
| Brazil       | 31       | 6.5%    |
| Germany      | 28       | 5.87%   |
| Canada       | 23       | 4.82%   |
| UK           | 21       | 4.4%    |
| Italy        | 17       | 3.56%   |
| France       | 16       | 3.35%   |
| Australia    | 16       | 3.35%   |
| Netherlands  | 12       | 2.52%   |
| Poland       | 9        | 1.89%   |
| Norway       | 9        | 1.89%   |
| Sweden       | 7        | 1.47%   |
| Spain        | 7        | 1.47%   |
| Finland      | 7        | 1.47%   |
| Austria      | 6        | 1.26%   |
| Ireland      | 5        | 1.05%   |
| Greece       | 5        | 1.05%   |
| Switzerland  | 4        | 0.84%   |
| Portugal     | 4        | 0.84%   |
| Mexico       | 4        | 0.84%   |
| Japan        | 4        | 0.84%   |
| India        | 4        | 0.84%   |
| Hong Kong    | 4        | 0.84%   |
| Belgium      | 4        | 0.84%   |
| Thailand     | 3        | 0.63%   |
| South Africa | 3        | 0.63%   |
| Russia       | 3        | 0.63%   |
| Romania      | 3        | 0.63%   |
| Philippines  | 3        | 0.63%   |
| Denmark      | 3        | 0.63%   |
| Czechia      | 3        | 0.63%   |
| Chile        | 3        | 0.63%   |
| Slovakia     | 2        | 0.42%   |
| Lithuania    | 2        | 0.42%   |
| Uruguay      | 1        | 0.21%   |
| Turkey       | 1        | 0.21%   |
| Tunisia      | 1        | 0.21%   |
| South Korea  | 1        | 0.21%   |
| Slovenia     | 1        | 0.21%   |
| Serbia       | 1        | 0.21%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Berlin            | 6        | 1.25%   |
| Seattle           | 5        | 1.04%   |
| San Francisco     | 5        | 1.04%   |
| Milan             | 5        | 1.04%   |
| Vienna            | 4        | 0.83%   |
| Rio de Janeiro    | 4        | 0.83%   |
| Sydney            | 3        | 0.62%   |
| Sao Paulo         | 3        | 0.62%   |
| Paris             | 3        | 0.62%   |
| Miami             | 3        | 0.62%   |
| Melbourne         | 3        | 0.62%   |
| Madrid            | 3        | 0.62%   |
| Helsinki          | 3        | 0.62%   |
| Dublin            | 3        | 0.62%   |
| Cleveland         | 3        | 0.62%   |
| Central           | 3        | 0.62%   |
| Bedford           | 3        | 0.62%   |
| Adelaide          | 3        | 0.62%   |
| Zurich            | 2        | 0.42%   |
| Weimar            | 2        | 0.42%   |
| Trondheim         | 2        | 0.42%   |
| Springfield       | 2        | 0.42%   |
| Sapporo           | 2        | 0.42%   |
| Richmond          | 2        | 0.42%   |
| Recife            | 2        | 0.42%   |
| Orange            | 2        | 0.42%   |
| Ogden             | 2        | 0.42%   |
| Montreal          | 2        | 0.42%   |
| Merced            | 2        | 0.42%   |
| Mannheim          | 2        | 0.42%   |
| Ludwigsburg       | 2        | 0.42%   |
| Lisbon            | 2        | 0.42%   |
| Kolkata           | 2        | 0.42%   |
| Juiz de Fora      | 2        | 0.42%   |
| Joinville         | 2        | 0.42%   |
| Halifax           | 2        | 0.42%   |
| Goiânia          | 2        | 0.42%   |
| Fresno            | 2        | 0.42%   |
| Frankfurt am Main | 2        | 0.42%   |
| Fort Collins      | 2        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Samsung Electronics       | 177      | 265    | 18.04%  |
| Seagate                   | 168      | 241    | 17.13%  |
| WDC                       | 151      | 218    | 15.39%  |
| SanDisk                   | 63       | 75     | 6.42%   |
| Crucial                   | 63       | 94     | 6.42%   |
| Kingston                  | 47       | 60     | 4.79%   |
| Toshiba                   | 45       | 51     | 4.59%   |
| Hitachi                   | 22       | 29     | 2.24%   |
| Phison                    | 21       | 30     | 2.14%   |
| Intel                     | 19       | 21     | 1.94%   |
| A-DATA Technology         | 16       | 17     | 1.63%   |
| Micron/Crucial Technology | 14       | 17     | 1.43%   |
| Silicon Motion            | 13       | 18     | 1.33%   |
| China                     | 11       | 13     | 1.12%   |
| PNY                       | 9        | 13     | 0.92%   |
| Phison Electronics        | 9        | 14     | 0.92%   |
| Unknown                   | 8        | 17     | 0.82%   |
| SPCC                      | 8        | 11     | 0.82%   |
| SK hynix                  | 8        | 9      | 0.82%   |
| Micron Technology         | 8        | 10     | 0.82%   |
| Patriot                   | 5        | 6      | 0.51%   |
| OCZ                       | 5        | 7      | 0.51%   |
| HGST                      | 5        | 6      | 0.51%   |
| XPG                       | 4        | 4      | 0.41%   |
| Realtek Semiconductor     | 4        | 4      | 0.41%   |
| Netac                     | 4        | 4      | 0.41%   |
| JMicron Technology        | 4        | 13     | 0.41%   |
| Intenso                   | 4        | 4      | 0.41%   |
| Hewlett-Packard           | 4        | 4      | 0.41%   |
| Team                      | 3        | 5      | 0.31%   |
| Maxtor                    | 3        | 3      | 0.31%   |
| Lexar                     | 3        | 3      | 0.31%   |
| Corsair                   | 3        | 5      | 0.31%   |
| Apple                     | 3        | 3      | 0.31%   |
| WALRAM                    | 2        | 2      | 0.2%    |
| T-FORCE                   | 2        | 3      | 0.2%    |
| Mushkin                   | 2        | 3      | 0.2%    |
| LITEON                    | 2        | 3      | 0.2%    |
| Fujitsu                   | 2        | 3      | 0.2%    |
| ADATA Technology          | 2        | 2      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Desktops | Percent |
|-----------------------------------------------------|----------|---------|
| Samsung NVMe SSD Drive 1TB                          | 25       | 2.14%   |
| Seagate ST2000DM008-2FR102 2TB                      | 21       | 1.8%    |
| Samsung NVMe SSD Drive 500GB                        | 18       | 1.54%   |
| Samsung SSD 860 EVO 1TB                             | 15       | 1.29%   |
| SanDisk NVMe SSD Drive 1TB                          | 14       | 1.2%    |
| Seagate ST1000DM010-2EP102 1TB                      | 13       | 1.11%   |
| Samsung SSD 850 EVO 250GB                           | 13       | 1.11%   |
| Crucial CT1000MX500SSD1 1TB                         | 12       | 1.03%   |
| Samsung SSD 850 EVO 500GB                           | 11       | 0.94%   |
| Seagate ST1000DM003-1ER162 1TB                      | 10       | 0.86%   |
| Samsung NVMe SSD Drive 2TB                          | 10       | 0.86%   |
| Kingston SA400S37240G 240GB SSD                     | 10       | 0.86%   |
| Seagate ST500DM002-1BD142 500GB                     | 9        | 0.77%   |
| Seagate ST1000DM003-1CH162 1TB                      | 9        | 0.77%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 8        | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB                      | 8        | 0.69%   |
| Samsung SSD 860 EVO 500GB                           | 8        | 0.69%   |
| Kingston SV300S37A120G 120GB SSD                    | 8        | 0.69%   |
| Kingston SA400S37120G 120GB SSD                     | 8        | 0.69%   |
| Crucial CT500MX500SSD1 500GB                        | 8        | 0.69%   |
| SanDisk NVMe SSD Drive 500GB                        | 7        | 0.6%    |
| Phison NVMe SSD Drive 1TB                           | 7        | 0.6%    |
| Micron/Crucial NVMe SSD Drive 1TB                   | 7        | 0.6%    |
| Crucial CT2000MX500SSD1 2TB                         | 7        | 0.6%    |
| Crucial CT1000BX500SSD1 1TB                         | 7        | 0.6%    |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 6        | 0.51%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 6        | 0.51%   |
| Toshiba DT01ACA100 1TB                              | 6        | 0.51%   |
| Seagate ST8000DM004-2CX188 8TB                      | 6        | 0.51%   |
| Seagate Expansion 2TB                               | 6        | 0.51%   |
| Phison E12 NVMe Controller 2TB                      | 6        | 0.51%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 5        | 0.43%   |
| Toshiba HDWD120 2TB                                 | 5        | 0.43%   |
| Toshiba DT01ACA200 2TB                              | 5        | 0.43%   |
| Seagate ST31000528AS 1TB                            | 5        | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 5        | 0.43%   |
| Seagate NVMe SSD Drive 1TB                          | 5        | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB                        | 5        | 0.43%   |
| Samsung SSD 850 EVO 1TB                             | 5        | 0.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 5        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 160      | 227    | 42.33%  |
| WDC                 | 124      | 174    | 32.8%   |
| Toshiba             | 40       | 46     | 10.58%  |
| Hitachi             | 22       | 29     | 5.82%   |
| Samsung Electronics | 15       | 19     | 3.97%   |
| HGST                | 5        | 6      | 1.32%   |
| Apple               | 3        | 3      | 0.79%   |
| Unknown             | 2        | 6      | 0.53%   |
| Maxtor              | 2        | 2      | 0.53%   |
| JMicron Technology  | 2        | 7      | 0.53%   |
| SABRENT             | 1        | 1      | 0.26%   |
| Fujitsu             | 1        | 2      | 0.26%   |
| ASMT                | 1        | 1      | 0.26%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 88       | 124    | 25.43%  |
| Crucial             | 59       | 86     | 17.05%  |
| Kingston            | 41       | 50     | 11.85%  |
| WDC                 | 27       | 34     | 7.8%    |
| SanDisk             | 24       | 27     | 6.94%   |
| A-DATA Technology   | 13       | 14     | 3.76%   |
| China               | 10       | 12     | 2.89%   |
| PNY                 | 9        | 13     | 2.6%    |
| Intel               | 8        | 8      | 2.31%   |
| SPCC                | 6        | 7      | 1.73%   |
| Patriot             | 5        | 6      | 1.45%   |
| OCZ                 | 5        | 7      | 1.45%   |
| SK hynix            | 4        | 5      | 1.16%   |
| Netac               | 4        | 4      | 1.16%   |
| Toshiba             | 3        | 3      | 0.87%   |
| Team                | 3        | 5      | 0.87%   |
| Micron Technology   | 3        | 3      | 0.87%   |
| Lexar               | 3        | 3      | 0.87%   |
| Hewlett-Packard     | 3        | 3      | 0.87%   |
| Seagate             | 2        | 2      | 0.58%   |
| Mushkin             | 2        | 3      | 0.58%   |
| Intenso             | 2        | 2      | 0.58%   |
| Yeyian              | 1        | 1      | 0.29%   |
| Transcend           | 1        | 2      | 0.29%   |
| TO Exter            | 1        | 1      | 0.29%   |
| TCSUNBOW            | 1        | 1      | 0.29%   |
| PNY USB             | 1        | 1      | 0.29%   |
| Plextor             | 1        | 1      | 0.29%   |
| Maxtor              | 1        | 1      | 0.29%   |
| LITEON              | 1        | 2      | 0.29%   |
| KingDian            | 1        | 1      | 0.29%   |
| HS-SSD-E100N        | 1        | 1      | 0.29%   |
| GOODRAM             | 1        | 1      | 0.29%   |
| Gigabyte Technology | 1        | 1      | 0.29%   |
| Fujitsu             | 1        | 1      | 0.29%   |
| FORESEE             | 1        | 2      | 0.29%   |
| Fanxiang            | 1        | 1      | 0.29%   |
| Emtec               | 1        | 1      | 0.29%   |
| Digital             | 1        | 1      | 0.29%   |
| Corsair             | 1        | 2      | 0.29%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 289      | 523    | 35.12%  |
| SSD     | 285      | 447    | 34.63%  |
| NVMe    | 220      | 337    | 26.73%  |
| Unknown | 26       | 40     | 3.16%   |
| MMC     | 3        | 4      | 0.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 411      | 944    | 60.98%  |
| NVMe | 220      | 336    | 32.64%  |
| SAS  | 40       | 67     | 5.93%   |
| MMC  | 3        | 4      | 0.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 270      | 421    | 41.28%  |
| 0.51-1.0   | 201      | 290    | 30.73%  |
| 1.01-2.0   | 107      | 140    | 16.36%  |
| 3.01-4.0   | 31       | 44     | 4.74%   |
| 4.01-10.0  | 22       | 38     | 3.36%   |
| 2.01-3.0   | 20       | 26     | 3.06%   |
| 10.01-20.0 | 3        | 11     | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 501-1000       | 109      | 22.52%  |
| 251-500        | 88       | 18.18%  |
| 101-250        | 87       | 17.98%  |
| 1001-2000      | 78       | 16.12%  |
| More than 3000 | 56       | 11.57%  |
| 2001-3000      | 32       | 6.61%   |
| 1-20           | 14       | 2.89%   |
| 51-100         | 9        | 1.86%   |
| 21-50          | 7        | 1.45%   |
| Unknown        | 4        | 0.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 117      | 23.54%  |
| 21-50          | 86       | 17.3%   |
| 101-250        | 67       | 13.48%  |
| 51-100         | 61       | 12.27%  |
| 251-500        | 54       | 10.87%  |
| 501-1000       | 37       | 7.44%   |
| 1001-2000      | 36       | 7.24%   |
| More than 3000 | 24       | 4.83%   |
| 2001-3000      | 11       | 2.21%   |
| Unknown        | 4        | 0.8%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Desktops | Drives | Percent |
|----------------------------------------------|----------|--------|---------|
| WDC WD60EFRX-68L0BN1 6TB                     | 1        | 1      | 4.17%   |
| WDC WD5001AALS-00J7B1 500GB                  | 1        | 1      | 4.17%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1        | 1      | 4.17%   |
| WDC WD20EFRX-68AX9N0 2TB                     | 1        | 2      | 4.17%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1        | 1      | 4.17%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1        | 1      | 4.17%   |
| WDC WD1001FALS-00E8B0 1TB                    | 1        | 1      | 4.17%   |
| Seagate ST5000LM000-2AN170 5TB               | 1        | 1      | 4.17%   |
| Seagate ST320LM001 HN-M320MBB 320GB          | 1        | 1      | 4.17%   |
| Seagate ST2000DM008-2FR102 2TB               | 1        | 1      | 4.17%   |
| Seagate ST2000DM006-2DM164 2TB               | 1        | 1      | 4.17%   |
| Seagate Expansion Desk 8TB                   | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 850 PRO 256GB        | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 850 EVO 250GB        | 1        | 1      | 4.17%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 1        | 1      | 4.17%   |
| Samsung Electronics HD103SI 1TB              | 1        | 1      | 4.17%   |
| SABRENT Disk 500GB                           | 1        | 1      | 4.17%   |
| Plextor PX-128M6M 128GB SSD                  | 1        | 1      | 4.17%   |
| Kingston SV300S37A240G 240GB SSD             | 1        | 1      | 4.17%   |
| Hitachi HDP725050GLA360 500GB                | 1        | 1      | 4.17%   |
| HGST HTS725050A7E630 500GB                   | 1        | 1      | 4.17%   |
| Crucial CT525MX300SSD1 528GB                 | 1        | 1      | 4.17%   |
| BAITITON BT58SSD08M 128GB                    | 1        | 1      | 4.17%   |
| A-DATA Technology SU800 512GB SSD            | 1        | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 30.43%  |
| Seagate             | 4        | 5      | 17.39%  |
| Samsung Electronics | 4        | 4      | 17.39%  |
| SABRENT             | 1        | 1      | 4.35%   |
| Plextor             | 1        | 1      | 4.35%   |
| Kingston            | 1        | 1      | 4.35%   |
| Hitachi             | 1        | 1      | 4.35%   |
| HGST                | 1        | 1      | 4.35%   |
| Crucial             | 1        | 1      | 4.35%   |
| BAITITON            | 1        | 1      | 4.35%   |
| A-DATA Technology   | 1        | 1      | 4.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 7        | 8      | 46.67%  |
| Seagate             | 4        | 5      | 26.67%  |
| Samsung Electronics | 1        | 1      | 6.67%   |
| SABRENT             | 1        | 1      | 6.67%   |
| Hitachi             | 1        | 1      | 6.67%   |
| HGST                | 1        | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 14       | 17     | 63.64%  |
| SSD  | 8        | 8      | 36.36%  |

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


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 404      | 1129   | 79.37%  |
| Works    | 85       | 197    | 16.7%   |
| Malfunc  | 20       | 25     | 3.93%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Desktops | Percent |
|--------------------------------|----------|---------|
| Intel                          | 243      | 30.72%  |
| AMD                            | 230      | 29.08%  |
| Samsung Electronics            | 102      | 12.9%   |
| SanDisk                        | 47       | 5.94%   |
| Phison Electronics             | 34       | 4.3%    |
| ASMedia Technology             | 26       | 3.29%   |
| Micron/Crucial Technology      | 19       | 2.4%    |
| Silicon Motion                 | 15       | 1.9%    |
| Marvell Technology Group       | 11       | 1.39%   |
| Kingston Technology Company    | 8        | 1.01%   |
| Nvidia                         | 7        | 0.88%   |
| ADATA Technology               | 7        | 0.88%   |
| Seagate Technology             | 6        | 0.76%   |
| Realtek Semiconductor          | 6        | 0.76%   |
| JMicron Technology             | 6        | 0.76%   |
| Micron Technology              | 5        | 0.63%   |
| SK hynix                       | 4        | 0.51%   |
| Toshiba America Info Systems   | 3        | 0.38%   |
| Broadcom / LSI                 | 3        | 0.38%   |
| Silicon Image                  | 2        | 0.25%   |
| LSI Logic / Symbios Logic      | 2        | 0.25%   |
| VIA Technologies               | 1        | 0.13%   |
| Unknown                        | 1        | 0.13%   |
| Solid State Storage Technology | 1        | 0.13%   |
| Lite-On Technology             | 1        | 0.13%   |
| KIOXIA                         | 1        | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 147      | 15.56%  |
| AMD 400 Series Chipset SATA Controller                                                  | 63       | 6.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 55       | 5.82%   |
| AMD 500 Series Chipset SATA Controller                                                  | 48       | 5.08%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 28       | 2.96%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 24       | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 23       | 2.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 22       | 2.33%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 21       | 2.22%   |
| Phison E12 NVMe Controller                                                              | 18       | 1.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 17       | 1.8%    |
| Samsung NVMe SSD Controller 980                                                         | 15       | 1.59%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 14       | 1.48%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 14       | 1.48%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 1.48%   |
| Intel SATA Controller [RAID mode]                                                       | 13       | 1.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 13       | 1.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 13       | 1.38%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 12       | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 12       | 1.27%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 12       | 1.27%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 11       | 1.16%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 10       | 1.06%   |
| AMD 300 Series Chipset SATA Controller                                                  | 10       | 1.06%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 8        | 0.85%   |
| SanDisk Non-Volatile memory controller                                                  | 7        | 0.74%   |
| Intel SSD 660P Series                                                                   | 7        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 7        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 7        | 0.74%   |
| AMD X370 Series Chipset SATA Controller                                                 | 7        | 0.74%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 6        | 0.63%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 6        | 0.63%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 6        | 0.63%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 6        | 0.63%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                              | 6        | 0.63%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6        | 0.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 6        | 0.63%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 5        | 0.53%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 419      | 57.01%  |
| NVMe | 221      | 30.07%  |
| IDE  | 63       | 8.57%   |
| RAID | 26       | 3.54%   |
| SAS  | 6        | 0.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 238      | 50.21%  |
| Intel  | 236      | 49.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 22       | 4.63%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 18       | 3.79%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 15       | 3.16%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 15       | 3.16%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 11       | 2.32%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 10       | 2.11%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 10       | 2.11%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 8        | 1.68%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 1.68%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 8        | 1.68%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 7        | 1.47%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 6        | 1.26%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 6        | 1.26%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 6        | 1.26%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 5        | 1.05%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 5        | 1.05%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 5        | 1.05%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 5        | 1.05%   |
| AMD Ryzen 9 3950X 16-Core Processor         | 5        | 1.05%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 5        | 1.05%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 5        | 1.05%   |
| AMD FX-8350 Eight-Core Processor            | 5        | 1.05%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 4        | 0.84%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 4        | 0.84%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 4        | 0.84%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 4        | 0.84%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 4        | 0.84%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 4        | 0.84%   |
| AMD Ryzen 7 1800X Eight-Core Processor      | 4        | 0.84%   |
| AMD Ryzen 7 1700 Eight-Core Processor       | 4        | 0.84%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 4        | 0.84%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 0.84%   |
| AMD FX-6300 Six-Core Processor              | 4        | 0.84%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 3        | 0.63%   |
| Intel Core i7-9700K CPU @ 3.60GHz           | 3        | 0.63%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 3        | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 3        | 0.63%   |
| Intel Core i7 CPU 950 @ 3.07GHz             | 3        | 0.63%   |
| Intel Core i7 CPU 920 @ 2.67GHz             | 3        | 0.63%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3        | 0.63%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 5             | 82       | 17.26%  |
| Intel Core i7           | 72       | 15.16%  |
| Intel Core i5           | 67       | 14.11%  |
| AMD Ryzen 7             | 66       | 13.89%  |
| AMD Ryzen 9             | 37       | 7.79%   |
| Other                   | 23       | 4.84%   |
| Intel Xeon              | 20       | 4.21%   |
| Intel Core i3           | 18       | 3.79%   |
| AMD FX                  | 14       | 2.95%   |
| Intel Core i9           | 10       | 2.11%   |
| AMD Ryzen 3             | 6        | 1.26%   |
| Intel Core 2 Quad       | 5        | 1.05%   |
| Intel Celeron           | 5        | 1.05%   |
| AMD Ryzen Threadripper  | 5        | 1.05%   |
| Intel Pentium Gold      | 4        | 0.84%   |
| AMD A8                  | 4        | 0.84%   |
| Intel Pentium           | 3        | 0.63%   |
| AMD Phenom              | 3        | 0.63%   |
| Intel Pentium Dual      | 2        | 0.42%   |
| Intel Pentium D         | 2        | 0.42%   |
| Intel Core 2 Duo        | 2        | 0.42%   |
| Intel Core 2            | 2        | 0.42%   |
| AMD Phenom II X6        | 2        | 0.42%   |
| AMD Phenom II X4        | 2        | 0.42%   |
| AMD Athlon II X4        | 2        | 0.42%   |
| AMD Athlon II X2        | 2        | 0.42%   |
| AMD Athlon              | 2        | 0.42%   |
| AMD A4                  | 2        | 0.42%   |
| Intel Pentium Dual-Core | 1        | 0.21%   |
| Intel Atom              | 1        | 0.21%   |
| AMD Sempron             | 1        | 0.21%   |
| AMD Ryzen Embedded      | 1        | 0.21%   |
| AMD Ryzen 5 PRO         | 1        | 0.21%   |
| AMD PRO A10             | 1        | 0.21%   |
| AMD Phenom II X3        | 1        | 0.21%   |
| AMD Athlon X4           | 1        | 0.21%   |
| AMD Athlon 64           | 1        | 0.21%   |
| AMD A6                  | 1        | 0.21%   |
| AMD A10                 | 1        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 155      | 32.63%  |
| 6      | 107      | 22.53%  |
| 8      | 88       | 18.53%  |
| 2      | 51       | 10.74%  |
| 12     | 26       | 5.47%   |
| 16     | 23       | 4.84%   |
| 10     | 8        | 1.68%   |
| 3      | 7        | 1.47%   |
| 24     | 3        | 0.63%   |
| 1      | 3        | 0.63%   |
| 32     | 2        | 0.42%   |
| 18     | 1        | 0.21%   |
| 14     | 1        | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 471      | 99.37%  |
| 2      | 3        | 0.63%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 356      | 75.11%  |
| 1      | 118      | 24.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 474      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 390      | 81.93%  |
| 0x08701021 | 12       | 2.52%   |
| 0x0a201016 | 7        | 1.47%   |
| 0x0800820d | 7        | 1.47%   |
| 0x906ec    | 5        | 1.05%   |
| 0x206a7    | 5        | 1.05%   |
| 0x306a9    | 4        | 0.84%   |
| 0x08701013 | 4        | 0.84%   |
| 0x906e9    | 3        | 0.63%   |
| 0x90672    | 3        | 0.63%   |
| 0x506e3    | 3        | 0.63%   |
| 0x08108109 | 3        | 0.63%   |
| 0x08001138 | 3        | 0.63%   |
| 0x06003106 | 3        | 0.63%   |
| 0xa0671    | 2        | 0.42%   |
| 0xa0653    | 2        | 0.42%   |
| 0x906ea    | 2        | 0.42%   |
| 0x50657    | 2        | 0.42%   |
| 0x306c3    | 2        | 0.42%   |
| 0x08001137 | 2        | 0.42%   |
| 0xa0655    | 1        | 0.21%   |
| 0x906ed    | 1        | 0.21%   |
| 0x906c0    | 1        | 0.21%   |
| 0x0a601201 | 1        | 0.21%   |
| 0x0a201205 | 1        | 0.21%   |
| 0x0a201006 | 1        | 0.21%   |
| 0x08301039 | 1        | 0.21%   |
| 0x08101016 | 1        | 0.21%   |
| 0x08001129 | 1        | 0.21%   |
| 0x07013005 | 1        | 0.21%   |
| 0x0600611a | 1        | 0.21%   |
| 0x06000852 | 1        | 0.21%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 80       | 16.84%  |
| Zen 2            | 65       | 13.68%  |
| Haswell          | 45       | 9.47%   |
| KabyLake         | 37       | 7.79%   |
| Zen+             | 34       | 7.16%   |
| IvyBridge        | 31       | 6.53%   |
| Skylake          | 27       | 5.68%   |
| Unknown          | 25       | 5.26%   |
| SandyBridge      | 20       | 4.21%   |
| Zen              | 18       | 3.79%   |
| Piledriver       | 16       | 3.37%   |
| Nehalem          | 12       | 2.53%   |
| K10              | 12       | 2.53%   |
| CometLake        | 12       | 2.53%   |
| Penryn           | 8        | 1.68%   |
| Westmere         | 5        | 1.05%   |
| Steamroller      | 5        | 1.05%   |
| Core             | 5        | 1.05%   |
| Broadwell        | 4        | 0.84%   |
| Alderlake Hybrid | 3        | 0.63%   |
| Silvermont       | 2        | 0.42%   |
| NetBurst         | 2        | 0.42%   |
| Excavator        | 2        | 0.42%   |
| K8 Hammer        | 1        | 0.21%   |
| K10 Llano        | 1        | 0.21%   |
| Jaguar           | 1        | 0.21%   |
| Icelake          | 1        | 0.21%   |
| Goldmont         | 1        | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 246      | 48.71%  |
| AMD                        | 183      | 36.24%  |
| Intel                      | 75       | 14.85%  |
| Matrox Electronics Systems | 1        | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 21       | 4.05%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 17       | 3.28%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 16       | 3.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 15       | 2.89%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 15       | 2.89%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 13       | 2.5%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 12       | 2.31%   |
| AMD Cezanne                                                                 | 12       | 2.31%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11       | 2.12%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 10       | 1.93%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 9        | 1.73%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 1.73%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 8        | 1.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 7        | 1.35%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 7        | 1.35%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 7        | 1.35%   |
| Intel AlderLake-S GT1                                                       | 7        | 1.35%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.35%   |
| Nvidia TU116 [GeForce GTX 1660]                                             | 6        | 1.16%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 6        | 1.16%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 6        | 1.16%   |
| Nvidia GA104 [GeForce RTX 3070 Ti]                                          | 6        | 1.16%   |
| Nvidia GA102 [GeForce RTX 3080 Lite Hash Rate]                              | 6        | 1.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 6        | 1.16%   |
| Intel HD Graphics 530                                                       | 6        | 1.16%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                          | 5        | 0.96%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 5        | 0.96%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.96%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 5        | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                              | 5        | 0.96%   |
| Nvidia GA106 [GeForce RTX 3060]                                             | 5        | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5        | 0.96%   |
| AMD Navi 24 [Radeon RX 6400 / 6500 XT]                                      | 5        | 0.96%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 5        | 0.96%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4        | 0.77%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 4        | 0.77%   |
| Nvidia TU102 [GeForce RTX 2080 Ti]                                          | 4        | 0.77%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 0.77%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 4        | 0.77%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 232      | 48.23%  |
| 1 x AMD              | 171      | 35.55%  |
| 1 x Intel            | 50       | 10.4%   |
| 2 x AMD              | 7        | 1.46%   |
| Intel + Nvidia       | 7        | 1.46%   |
| 2 x Nvidia           | 5        | 1.04%   |
| Intel + AMD          | 3        | 0.62%   |
| AMD + Nvidia         | 2        | 0.42%   |
| Other                | 1        | 0.21%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.21%   |
| 1 x Matrox           | 1        | 0.21%   |
| AMD + 2 x Nvidia     | 1        | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 251      | 52.29%  |
| Proprietary | 213      | 44.38%  |
| Unknown     | 16       | 3.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 292      | 60.71%  |
| 7.01-8.0   | 51       | 10.6%   |
| 1.01-2.0   | 33       | 6.86%   |
| 8.01-16.0  | 31       | 6.44%   |
| 5.01-6.0   | 30       | 6.24%   |
| 3.01-4.0   | 28       | 5.82%   |
| 2.01-3.0   | 7        | 1.46%   |
| 0.51-1.0   | 4        | 0.83%   |
| 16.01-24.0 | 2        | 0.42%   |
| 0.01-0.5   | 2        | 0.42%   |
| 32.01-64.0 | 1        | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 93       | 17.42%  |
| Goldstar             | 65       | 12.17%  |
| Dell                 | 61       | 11.42%  |
| Hewlett-Packard      | 37       | 6.93%   |
| AOC                  | 33       | 6.18%   |
| Ancor Communications | 33       | 6.18%   |
| Acer                 | 30       | 5.62%   |
| BenQ                 | 26       | 4.87%   |
| ASUSTek Computer     | 26       | 4.87%   |
| Philips              | 11       | 2.06%   |
| Lenovo               | 11       | 2.06%   |
| MSI                  | 8        | 1.5%    |
| Iiyama               | 7        | 1.31%   |
| Sceptre Tech         | 6        | 1.12%   |
| NEC Computers        | 6        | 1.12%   |
| Gigabyte Technology  | 5        | 0.94%   |
| ViewSonic            | 4        | 0.75%   |
| Unknown              | 4        | 0.75%   |
| Viotek               | 3        | 0.56%   |
| Sony                 | 3        | 0.56%   |
| Vizio                | 2        | 0.37%   |
| Vestel Elektronik    | 2        | 0.37%   |
| Valve                | 2        | 0.37%   |
| Toshiba              | 2        | 0.37%   |
| Sharp                | 2        | 0.37%   |
| Mi                   | 2        | 0.37%   |
| LLL                  | 2        | 0.37%   |
| LG Electronics       | 2        | 0.37%   |
| ITE                  | 2        | 0.37%   |
| HUAWEI               | 2        | 0.37%   |
| GDH                  | 2        | 0.37%   |
| Eizo                 | 2        | 0.37%   |
| Arnos Instruments    | 2        | 0.37%   |
| ___                  | 1        | 0.19%   |
| VOXICON              | 1        | 0.19%   |
| Unknown (XXX)        | 1        | 0.19%   |
| TXD                  | 1        | 0.19%   |
| Targa Visionary      | 1        | 0.19%   |
| STD                  | 1        | 0.19%   |
| SKY                  | 1        | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Desktops | Percent |
|-------------------------------------------------------------------------|----------|---------|
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch        | 5        | 0.89%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch     | 4        | 0.72%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                | 4        | 0.72%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 4        | 0.72%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                        | 4        | 0.72%   |
| AOC 2460G5 AOC0001 1920x1080 531x299mm 24.0-inch                        | 4        | 0.72%   |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch   | 4        | 0.72%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch       | 3        | 0.54%   |
| Samsung Electronics LC32G7xT SAM7058 2560x1440 698x393mm 31.5-inch      | 3        | 0.54%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch       | 3        | 0.54%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                     | 3        | 0.54%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                  | 3        | 0.54%   |
| BenQ PD3200U BNQ8025 3840x2160 708x399mm 32.0-inch                      | 3        | 0.54%   |
| ASUSTek Computer VG249 AUS2421 1920x1080 527x296mm 23.8-inch            | 3        | 0.54%   |
| Ancor Communications VG248 ACI24E1 1920x1080 531x299mm 24.0-inch        | 3        | 0.54%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch  | 2        | 0.36%   |
| Valve Index HMD VLV91A8                                                 | 2        | 0.36%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch       | 2        | 0.36%   |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 2        | 0.36%   |
| Samsung Electronics LS24AG30x SAM7178 1920x1080 527x296mm 23.8-inch     | 2        | 0.36%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2        | 0.36%   |
| Samsung Electronics LC34G55T SAM711A 3440x1440 798x334mm 34.1-inch      | 2        | 0.36%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch      | 2        | 0.36%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch       | 2        | 0.36%   |
| Samsung Electronics C27FG7x SAM0E41 1920x1080 598x337mm 27.0-inch       | 2        | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch       | 2        | 0.36%   |
| Philips PHL 322E1 PHLC20F 1920x1080 698x393mm 31.5-inch                 | 2        | 0.36%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch                | 2        | 0.36%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                 | 2        | 0.36%   |
| MSI G273 MSI3CA7 1920x1080 597x336mm 27.0-inch                          | 2        | 0.36%   |
| Mi Monitor XMI3444 3440x1440 800x330mm 34.1-inch                        | 2        | 0.36%   |
| LLL LRK32G30RQ LLL4200 1920x1080 983x576mm 44.9-inch                    | 2        | 0.36%   |
| Iiyama PL3461WQ IVM7615 3440x1440 800x335mm 34.1-inch                   | 2        | 0.36%   |
| HUAWEI AD80HW HWV2402 1920x1080 527x296mm 23.8-inch                     | 2        | 0.36%   |
| Hewlett-Packard 2310 HWP288F 1920x1080 510x287mm 23.0-inch              | 2        | 0.36%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch              | 2        | 0.36%   |
| Goldstar ULTRAWIDE GSM76E4 3440x1440 800x335mm 34.1-inch                | 2        | 0.36%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                 | 2        | 0.36%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 2        | 0.36%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                 | 2        | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 239      | 47.14%  |
| 3840x2160 (4K)     | 74       | 14.6%   |
| 2560x1440 (QHD)    | 53       | 10.45%  |
| 3440x1440          | 23       | 4.54%   |
| 2560x1080          | 18       | 3.55%   |
| 1680x1050 (WSXGA+) | 17       | 3.35%   |
| 1366x768 (WXGA)    | 15       | 2.96%   |
| 1280x1024 (SXGA)   | 14       | 2.76%   |
| 1920x1200 (WUXGA)  | 11       | 2.17%   |
| 1600x900 (HD+)     | 8        | 1.58%   |
| 3840x1080          | 6        | 1.18%   |
| 1920x540           | 5        | 0.99%   |
| 1440x900 (WXGA+)   | 4        | 0.79%   |
| 1360x768           | 4        | 0.79%   |
| 3840x1600          | 3        | 0.59%   |
| 1024x768 (XGA)     | 3        | 0.59%   |
| Unknown            | 3        | 0.59%   |
| 3280x1080          | 1        | 0.2%    |
| 3040x900           | 1        | 0.2%    |
| 2880x1600          | 1        | 0.2%    |
| 2560x1600          | 1        | 0.2%    |
| 1600x1200          | 1        | 0.2%    |
| 1280x800 (WXGA)    | 1        | 0.2%    |
| 1280x720 (HD)      | 1        | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 92       | 17.56%  |
| 24      | 88       | 16.79%  |
| 23      | 63       | 12.02%  |
| 21      | 44       | 8.4%    |
| 31      | 43       | 8.21%   |
| 34      | 37       | 7.06%   |
| Unknown | 19       | 3.63%   |
| 22      | 13       | 2.48%   |
| 18      | 13       | 2.48%   |
| 19      | 12       | 2.29%   |
| 32      | 11       | 2.1%    |
| 72      | 10       | 1.91%   |
| 17      | 9        | 1.72%   |
| 84      | 8        | 1.53%   |
| 20      | 7        | 1.34%   |
| 48      | 6        | 1.15%   |
| 25      | 6        | 1.15%   |
| 15      | 6        | 1.15%   |
| 28      | 5        | 0.95%   |
| 54      | 4        | 0.76%   |
| 37      | 4        | 0.76%   |
| 26      | 4        | 0.76%   |
| 46      | 3        | 0.57%   |
| 65      | 2        | 0.38%   |
| 52      | 2        | 0.38%   |
| 44      | 2        | 0.38%   |
| 35      | 2        | 0.38%   |
| 69      | 1        | 0.19%   |
| 61      | 1        | 0.19%   |
| 49      | 1        | 0.19%   |
| 47      | 1        | 0.19%   |
| 42      | 1        | 0.19%   |
| 36      | 1        | 0.19%   |
| 33      | 1        | 0.19%   |
| 30      | 1        | 0.19%   |
| 29      | 1        | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Desktops | Percent |
|-------------|----------|---------|
| 501-600     | 222      | 44.05%  |
| 401-500     | 80       | 15.87%  |
| 601-700     | 63       | 12.5%   |
| 701-800     | 49       | 9.72%   |
| 1001-1500   | 20       | 3.97%   |
| 1501-2000   | 19       | 3.77%   |
| Unknown     | 19       | 3.77%   |
| 301-350     | 15       | 2.98%   |
| 801-900     | 7        | 1.39%   |
| 351-400     | 7        | 1.39%   |
| 901-1000    | 3        | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 354      | 74.06%  |
| 21/9    | 45       | 9.41%   |
| 16/10   | 41       | 8.58%   |
| 5/4     | 15       | 3.14%   |
| Unknown | 10       | 2.09%   |
| 32/9    | 8        | 1.67%   |
| 4/3     | 5        | 1.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 160      | 31.62%  |
| 301-350        | 96       | 18.97%  |
| 351-500        | 95       | 18.77%  |
| 251-300        | 32       | 6.32%   |
| 151-200        | 31       | 6.13%   |
| More than 1000 | 28       | 5.53%   |
| 141-150        | 21       | 4.15%   |
| Unknown        | 19       | 3.75%   |
| 501-1000       | 18       | 3.56%   |
| 101-110        | 6        | 1.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Desktops | Percent |
|---------------|----------|---------|
| 51-100        | 290      | 61.05%  |
| 101-120       | 103      | 21.68%  |
| 121-160       | 30       | 6.32%   |
| 1-50          | 22       | 4.63%   |
| Unknown       | 19       | 4%      |
| 161-240       | 10       | 2.11%   |
| More than 240 | 1        | 0.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 345      | 72.33%  |
| 2     | 97       | 20.34%  |
| 0     | 18       | 3.77%   |
| 3     | 14       | 2.94%   |
| 4     | 2        | 0.42%   |
| 6     | 1        | 0.21%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 272      | 38.8%   |
| Intel                           | 258      | 36.8%   |
| Qualcomm Atheros                | 40       | 5.71%   |
| Broadcom                        | 24       | 3.42%   |
| TP-Link                         | 12       | 1.71%   |
| MediaTek                        | 10       | 1.43%   |
| Ralink Technology               | 9        | 1.28%   |
| NetGear                         | 7        | 1%      |
| Aquantia                        | 7        | 1%      |
| Nvidia                          | 6        | 0.86%   |
| Microsoft                       | 6        | 0.86%   |
| InterBiometrics                 | 5        | 0.71%   |
| Xiaomi                          | 4        | 0.57%   |
| Samsung Electronics             | 4        | 0.57%   |
| Ralink                          | 4        | 0.57%   |
| Qualcomm Atheros Communications | 3        | 0.43%   |
| D-Link                          | 3        | 0.43%   |
| ASUSTek Computer                | 3        | 0.43%   |
| Mellanox Technologies           | 2        | 0.29%   |
| Huawei Technologies             | 2        | 0.29%   |
| Google                          | 2        | 0.29%   |
| Broadcom Limited                | 2        | 0.29%   |
| STMicroelectronics              | 1        | 0.14%   |
| Sitecom Europe                  | 1        | 0.14%   |
| SIEMENS                         | 1        | 0.14%   |
| Qualcomm                        | 1        | 0.14%   |
| OPPO Electronics                | 1        | 0.14%   |
| Micro Star International        | 1        | 0.14%   |
| Marvell Technology Group        | 1        | 0.14%   |
| Manta                           | 1        | 0.14%   |
| IMC Networks                    | 1        | 0.14%   |
| Hyperkin                        | 1        | 0.14%   |
| Gemtek                          | 1        | 0.14%   |
| DisplayLink                     | 1        | 0.14%   |
| D-Link System                   | 1        | 0.14%   |
| Belkin Components               | 1        | 0.14%   |
| AVM                             | 1        | 0.14%   |
| Unknown                         | 1        | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 182      | 22.06%  |
| Intel I211 Gigabit Network Connection                             | 67       | 8.12%   |
| Intel Wi-Fi 6 AX200                                               | 66       | 8%      |
| Realtek RTL8125 2.5GbE Controller                                 | 59       | 7.15%   |
| Intel Ethernet Controller I225-V                                  | 34       | 4.12%   |
| Intel Ethernet Connection (2) I219-V                              | 20       | 2.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20       | 2.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 16       | 1.94%   |
| Intel Ethernet Connection I217-LM                                 | 13       | 1.58%   |
| Realtek 802.11ac NIC                                              | 11       | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11       | 1.33%   |
| Intel Wireless-AC 9260                                            | 10       | 1.21%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 1.21%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 10       | 1.21%   |
| Intel Ethernet Connection (2) I218-V                              | 8        | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8        | 0.97%   |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 8        | 0.97%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 7        | 0.85%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7        | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.61%   |
| InterBiometrics Io                                                | 5        | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 5        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5        | 0.61%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.61%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.48%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 4        | 0.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4        | 0.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4        | 0.48%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.48%   |
| NetGear A6210                                                     | 4        | 0.48%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4        | 0.48%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3        | 0.36%   |
| Realtek 802.11ac WLAN Adapter                                     | 3        | 0.36%   |
| Ralink MT7601U Wireless Adapter                                   | 3        | 0.36%   |
| Qualcomm Atheros AR9271 802.11n                                   | 3        | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 138      | 49.29%  |
| Realtek Semiconductor           | 47       | 16.79%  |
| Qualcomm Atheros                | 18       | 6.43%   |
| Broadcom                        | 16       | 5.71%   |
| TP-Link                         | 10       | 3.57%   |
| MediaTek                        | 10       | 3.57%   |
| Ralink Technology               | 9        | 3.21%   |
| NetGear                         | 7        | 2.5%    |
| Microsoft                       | 6        | 2.14%   |
| Ralink                          | 4        | 1.43%   |
| Qualcomm Atheros Communications | 3        | 1.07%   |
| ASUSTek Computer                | 3        | 1.07%   |
| D-Link                          | 2        | 0.71%   |
| Sitecom Europe                  | 1        | 0.36%   |
| Micro Star International        | 1        | 0.36%   |
| IMC Networks                    | 1        | 0.36%   |
| Gemtek                          | 1        | 0.36%   |
| D-Link System                   | 1        | 0.36%   |
| Belkin Components               | 1        | 0.36%   |
| AVM                             | 1        | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                           | 66       | 23.4%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 16       | 5.67%   |
| Realtek 802.11ac NIC                                          | 11       | 3.9%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 11       | 3.9%    |
| Intel Wireless-AC 9260                                        | 10       | 3.55%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 10       | 3.55%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 8        | 2.84%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 8        | 2.84%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 7        | 2.48%   |
| Intel Comet Lake PCH CNVi WiFi                                | 5        | 1.77%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 4        | 1.42%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 4        | 1.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 4        | 1.42%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 4        | 1.42%   |
| NetGear A6210                                                 | 4        | 1.42%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 4        | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 3        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 3        | 1.06%   |
| Realtek 802.11ac WLAN Adapter                                 | 3        | 1.06%   |
| Ralink MT7601U Wireless Adapter                               | 3        | 1.06%   |
| Qualcomm Atheros AR9271 802.11n                               | 3        | 1.06%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]   | 3        | 1.06%   |
| Microsoft XBOX ACC                                            | 3        | 1.06%   |
| Microsoft Xbox 360 Wireless Adapter                           | 3        | 1.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3        | 1.06%   |
| Intel Wireless Gigabit 17265                                  | 3        | 1.06%   |
| Intel Wireless 7265                                           | 3        | 1.06%   |
| Intel Wireless 7260                                           | 3        | 1.06%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 2        | 0.71%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 2        | 0.71%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 2        | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                         | 2        | 0.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 2        | 0.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 2        | 0.71%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter              | 2        | 0.71%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter            | 2        | 0.71%   |
| Intel Wireless 8265 / 8275                                    | 2        | 0.71%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2        | 0.71%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter            | 2        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 248      | 47.6%   |
| Intel                    | 205      | 39.35%  |
| Qualcomm Atheros         | 23       | 4.41%   |
| Broadcom                 | 9        | 1.73%   |
| Aquantia                 | 7        | 1.34%   |
| Nvidia                   | 6        | 1.15%   |
| Xiaomi                   | 4        | 0.77%   |
| Samsung Electronics      | 4        | 0.77%   |
| TP-Link                  | 2        | 0.38%   |
| Mellanox Technologies    | 2        | 0.38%   |
| Huawei Technologies      | 2        | 0.38%   |
| Google                   | 2        | 0.38%   |
| Broadcom Limited         | 2        | 0.38%   |
| Qualcomm                 | 1        | 0.19%   |
| OPPO Electronics         | 1        | 0.19%   |
| Marvell Technology Group | 1        | 0.19%   |
| DisplayLink              | 1        | 0.19%   |
| D-Link                   | 1        | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 182      | 34.15%  |
| Intel I211 Gigabit Network Connection                             | 67       | 12.57%  |
| Realtek RTL8125 2.5GbE Controller                                 | 59       | 11.07%  |
| Intel Ethernet Controller I225-V                                  | 34       | 6.38%   |
| Intel Ethernet Connection (2) I219-V                              | 20       | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 20       | 3.75%   |
| Intel Ethernet Connection I217-LM                                 | 13       | 2.44%   |
| Intel Ethernet Connection (7) I219-V                              | 10       | 1.88%   |
| Intel Ethernet Connection (2) I218-V                              | 8        | 1.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7        | 1.31%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 1.31%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6        | 1.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5        | 0.94%   |
| Intel Ethernet Connection I217-V                                  | 5        | 0.94%   |
| Intel 82579V Gigabit Network Connection                           | 5        | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4        | 0.75%   |
| Nvidia MCP61 Ethernet                                             | 4        | 0.75%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4        | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3        | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 3        | 0.56%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                  | 3        | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2        | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2        | 0.38%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2        | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.38%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2        | 0.38%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2        | 0.38%   |
| Nvidia MCP77 Ethernet                                             | 2        | 0.38%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2        | 0.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 2        | 0.38%   |
| Intel Ethernet Connection (17) I219-V                             | 2        | 0.38%   |
| Intel Ethernet Connection (14) I219-V                             | 2        | 0.38%   |
| Intel 82578DM Gigabit Network Connection                          | 2        | 0.38%   |
| Intel 82574L Gigabit Network Connection                           | 2        | 0.38%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2        | 0.38%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 2        | 0.38%   |
| Huawei LYA-L09                                                    | 2        | 0.38%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2        | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1        | 0.19%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1        | 0.19%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 468      | 62.9%   |
| WiFi     | 266      | 35.75%  |
| Modem    | 7        | 0.94%   |
| Unknown  | 3        | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 359      | 72.38%  |
| WiFi     | 137      | 27.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 253      | 53.26%  |
| 2     | 178      | 37.47%  |
| 3     | 35       | 7.37%   |
| 0     | 7        | 1.47%   |
| 4     | 2        | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 330      | 69.18%  |
| Yes  | 147      | 30.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 125      | 56.31%  |
| Cambridge Silicon Radio         | 42       | 18.92%  |
| ASUSTek Computer                | 13       | 5.86%   |
| Realtek Semiconductor           | 7        | 3.15%   |
| Qualcomm Atheros Communications | 7        | 3.15%   |
| Broadcom                        | 7        | 3.15%   |
| MediaTek                        | 4        | 1.8%    |
| Foxconn / Hon Hai               | 4        | 1.8%    |
| Apple                           | 4        | 1.8%    |
| TP-Link                         | 3        | 1.35%   |
| Micro Star International        | 1        | 0.45%   |
| IMC Networks                    | 1        | 0.45%   |
| HTC (High Tech Computer)        | 1        | 0.45%   |
| Edimax Technology               | 1        | 0.45%   |
| Dynex                           | 1        | 0.45%   |
| Belkin Components               | 1        | 0.45%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 60       | 27.03%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 42       | 18.92%  |
| Intel Wireless-AC 3168 Bluetooth                                     | 15       | 6.76%   |
| Intel AX201 Bluetooth                                                | 14       | 6.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 9        | 4.05%   |
| Intel Bluetooth wireless interface                                   | 9        | 4.05%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 8        | 3.6%    |
| Intel AX210 Bluetooth                                                | 8        | 3.6%    |
| Realtek Bluetooth Radio                                              | 5        | 2.25%   |
| ASUS ASUS USB-BT500                                                  | 5        | 2.25%   |
| MediaTek Wireless_Device                                             | 4        | 1.8%    |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4        | 1.8%    |
| ASUS Bluetooth Radio                                                 | 4        | 1.8%    |
| TP-Link TPuLink UB500 Adapter                                        | 3        | 1.35%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3        | 1.35%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 2        | 0.9%    |
| Intel Bluetooth Device                                               | 2        | 0.9%    |
| Foxconn / Hon Hai Wireless_Device                                    | 2        | 0.9%    |
| Foxconn / Hon Hai Bluetooth Device                                   | 2        | 0.9%    |
| Broadcom BCM43142 Bluetooth 4.0                                      | 2        | 0.9%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 2        | 0.9%    |
| Apple Bluetooth USB Host Controller                                  | 2        | 0.9%    |
| Realtek RTL8821A Bluetooth                                           | 1        | 0.45%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1        | 0.45%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 1        | 0.45%   |
| Qualcomm Atheros Bluetooth                                           | 1        | 0.45%   |
| Micro Star International Bluetooth Device                            | 1        | 0.45%   |
| IMC Networks Bluetooth Radio                                         | 1        | 0.45%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1        | 0.45%   |
| Edimax Bluetooth Adapter                                             | 1        | 0.45%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0]             | 1        | 0.45%   |
| Broadcom BCM2035 Bluetooth dongle                                    | 1        | 0.45%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 1        | 0.45%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 1        | 0.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 1        | 0.45%   |
| Apple Bluetooth Host Controller                                      | 1        | 0.45%   |
| Apple Bluetooth HCI                                                  | 1        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Desktops | Percent |
|--------------------------------------|----------|---------|
| AMD                                  | 280      | 29.47%  |
| Nvidia                               | 243      | 25.58%  |
| Intel                                | 226      | 23.79%  |
| C-Media Electronics                  | 23       | 2.42%   |
| Logitech                             | 17       | 1.79%   |
| Kingston Technology                  | 12       | 1.26%   |
| Razer USA                            | 11       | 1.16%   |
| JMTek                                | 10       | 1.05%   |
| Creative Labs                        | 10       | 1.05%   |
| Focusrite-Novation                   | 9        | 0.95%   |
| ASUSTek Computer                     | 7        | 0.74%   |
| Blue Microphones                     | 6        | 0.63%   |
| Texas Instruments                    | 5        | 0.53%   |
| Micro Star International             | 5        | 0.53%   |
| Generalplus Technology               | 5        | 0.53%   |
| Creative Technology                  | 5        | 0.53%   |
| Corsair                              | 5        | 0.53%   |
| SteelSeries ApS                      | 4        | 0.42%   |
| GN Netcom                            | 3        | 0.32%   |
| Valve Software                       | 2        | 0.21%   |
| Trust                                | 2        | 0.21%   |
| Thesycon Systemsoftware & Consulting | 2        | 0.21%   |
| Tenx Technology                      | 2        | 0.21%   |
| Mackie Designs                       | 2        | 0.21%   |
| M-Audio                              | 2        | 0.21%   |
| BEHRINGER International              | 2        | 0.21%   |
| Astro Gaming                         | 2        | 0.21%   |
| Antlion Audio                        | 2        | 0.21%   |
| Yamaha                               | 1        | 0.11%   |
| USB MIDI                             | 1        | 0.11%   |
| Unknown                              | 1        | 0.11%   |
| Turtle Beach                         | 1        | 0.11%   |
| Sony                                 | 1        | 0.11%   |
| Solid State System                   | 1        | 0.11%   |
| Shure                                | 1        | 0.11%   |
| Shenzhen Rapoo Technology            | 1        | 0.11%   |
| Sennheiser Communications            | 1        | 0.11%   |
| SAVITECH                             | 1        | 0.11%   |
| Samsung Electronics                  | 1        | 0.11%   |
| Samson Technologies                  | 1        | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 120      | 10.76%  |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 54       | 4.84%   |
| AMD Family 17h/19h HD Audio Controller                                     | 39       | 3.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 35       | 3.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27       | 2.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 25       | 2.24%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 23       | 2.06%   |
| Intel 200 Series PCH HD Audio                                              | 23       | 2.06%   |
| Nvidia TU116 High Definition Audio Controller                              | 22       | 1.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22       | 1.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21       | 1.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 21       | 1.88%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 21       | 1.88%   |
| Nvidia TU104 HD Audio Controller                                           | 20       | 1.79%   |
| Nvidia GP106 High Definition Audio Controller                              | 20       | 1.79%   |
| Nvidia GP104 High Definition Audio Controller                              | 20       | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 19       | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                 | 17       | 1.52%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 17       | 1.52%   |
| Nvidia GA102 High Definition Audio Controller                              | 16       | 1.43%   |
| Nvidia GA104 High Definition Audio Controller                              | 15       | 1.35%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 15       | 1.35%   |
| Nvidia GA106 High Definition Audio Controller                              | 14       | 1.26%   |
| Intel Alder Lake-S HD Audio Controller                                     | 14       | 1.26%   |
| AMD Navi 10 HDMI Audio                                                     | 14       | 1.26%   |
| Nvidia TU106 High Definition Audio Controller                              | 13       | 1.17%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 13       | 1.17%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 12       | 1.08%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 10       | 0.9%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10       | 0.9%    |
| AMD FCH Azalia Controller                                                  | 10       | 0.9%    |
| Nvidia GP108 High Definition Audio Controller                              | 9        | 0.81%   |
| Kingston Technology HyperX 7.1 Audio                                       | 9        | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 9        | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 8        | 0.72%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 0.63%   |
| Nvidia GK104 HDMI Audio Controller                                         | 7        | 0.63%   |
| JMTek USB PnP Audio Device                                                 | 7        | 0.63%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 7        | 0.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Corsair             | 32       | 34.04%  |
| G.Skill             | 13       | 13.83%  |
| Kingston            | 12       | 12.77%  |
| Samsung Electronics | 8        | 8.51%   |
| Team                | 7        | 7.45%   |
| Unknown             | 6        | 6.38%   |
| Crucial             | 5        | 5.32%   |
| Micron Technology   | 4        | 4.26%   |
| SK hynix            | 2        | 2.13%   |
| Unknown             | 2        | 2.13%   |
| Teikon              | 1        | 1.06%   |
| Patriot Memory      | 1        | 1.06%   |
| Avant               | 1        | 1.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s  | 7        | 7.07%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 4        | 4.04%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s     | 4        | 4.04%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s       | 2        | 2.02%   |
| G.Skill RAM F4-3600C18-8GVK 8GB DIMM DDR4 3600MT/s        | 2        | 2.02%   |
| G.Skill RAM F4-3600C18-8GTZRX 8GB DIMM DDR4 3600MT/s      | 2        | 2.02%   |
| Unknown                                                   | 2        | 2.02%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                 | 1        | 1.01%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                      | 1        | 1.01%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                      | 1        | 1.01%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                      | 1        | 1.01%   |
| Unknown RAM Module 16GB DIMM DDR4 3600MT/s                | 1        | 1.01%   |
| Unknown RAM 3600 C20 Series 32GB DIMM DDR4 3666MT/s       | 1        | 1.01%   |
| Unknown RAM 3600 C17 Series 8GB DIMM DDR4 3200MT/s        | 1        | 1.01%   |
| Teikon RAM TMT451U6BFR8C-PBHJ 4GB DIMM DDR3 1600MT/s      | 1        | 1.01%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3000MT/s        | 1        | 1.01%   |
| Team RAM TEAMGROUP-UD4-3000 8192MB DIMM DDR4 3067MT/s     | 1        | 1.01%   |
| Team RAM TEAMGROUP-UD4-2400 16GB DIMM DDR4 2400MT/s       | 1        | 1.01%   |
| SK hynix RAM HMT351U6CFR8C-PBA 2GB DIMM DDR3 1600MT/s     | 1        | 1.01%   |
| SK hynix RAM HMA82GU6DJR8N-WM 16GB DIMM DDR4 2933MT/s     | 1        | 1.01%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR4 2933MT/s       | 1        | 1.01%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 1.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 1        | 1.01%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s     | 1        | 1.01%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s       | 1        | 1.01%   |
| Samsung RAM M378B5173EB0-CK0 4096MB DIMM DDR3 1600MT/s    | 1        | 1.01%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s       | 1        | 1.01%   |
| Patriot Memory RAM 4400 C19 Series 8GB DIMM DDR4 3000MT/s | 1        | 1.01%   |
| Micron RAM M378A1K43BB2G3A141 8GB DIMM DDR4 2400MT/s      | 1        | 1.01%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 1        | 1.01%   |
| Micron RAM 8ATF2G64AZ-3G2B1 16GB DIMM DDR4 3200MT/s       | 1        | 1.01%   |
| Micron RAM 16JTF51264AZ-1G4M1 4GB DIMM DDR3 1333MT/s      | 1        | 1.01%   |
| Kingston RAM Module 16GB DIMM DDR4 2666MT/s               | 1        | 1.01%   |
| Kingston RAM KVT8FP-HYC 4GB DIMM DDR3 1600MT/s            | 1        | 1.01%   |
| Kingston RAM KHX3600C18D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 1.01%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s    | 1        | 1.01%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s       | 1        | 1.01%   |
| Kingston RAM KHX2133C14/8G 8GB DIMM DDR4 2400MT/s         | 1        | 1.01%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3600MT/s     | 1        | 1.01%   |
| Kingston RAM CL16-18-18 D4-3000 8GB DIMM DDR4 3000MT/s    | 1        | 1.01%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 69       | 79.31%  |
| DDR3    | 14       | 16.09%  |
| Unknown | 2        | 2.3%    |
| LPDDR4  | 1        | 1.15%   |
| DDR5    | 1        | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 82       | 94.25%  |
| SODIMM       | 4        | 4.6%    |
| Row Of Chips | 1        | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 43       | 46.74%  |
| 16384 | 23       | 25%     |
| 4096  | 16       | 17.39%  |
| 32768 | 9        | 9.78%   |
| 2048  | 1        | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 23       | 25%     |
| 3200  | 14       | 15.22%  |
| 1600  | 11       | 11.96%  |
| 3800  | 5        | 5.43%   |
| 2400  | 5        | 5.43%   |
| 1333  | 5        | 5.43%   |
| 3466  | 4        | 4.35%   |
| 3000  | 4        | 4.35%   |
| 2933  | 3        | 3.26%   |
| 2667  | 2        | 2.17%   |
| 2666  | 2        | 2.17%   |
| 2133  | 2        | 2.17%   |
| 4800  | 1        | 1.09%   |
| 4000  | 1        | 1.09%   |
| 3866  | 1        | 1.09%   |
| 3733  | 1        | 1.09%   |
| 3666  | 1        | 1.09%   |
| 3400  | 1        | 1.09%   |
| 3266  | 1        | 1.09%   |
| 3100  | 1        | 1.09%   |
| 3067  | 1        | 1.09%   |
| 2800  | 1        | 1.09%   |
| 2733  | 1        | 1.09%   |
| 1866  | 1        | 1.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Brother Industries  | 6        | 30%     |
| Samsung Electronics | 3        | 15%     |
| Hewlett-Packard     | 3        | 15%     |
| Canon               | 3        | 15%     |
| Seiko Epson         | 2        | 10%     |
| QinHeng Electronics | 1        | 5%      |
| Prolific Technology | 1        | 5%      |
| Dymo-CoStar         | 1        | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Brother HL-2130 series                 | 2        | 9.52%   |
| Seiko Epson WF-4830 Series             | 1        | 4.76%   |
| Seiko Epson ET-2800 Series             | 1        | 4.76%   |
| Samsung SCX-3400 Series                | 1        | 4.76%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1        | 4.76%   |
| Samsung M2070 Series                   | 1        | 4.76%   |
| QinHeng CH340S                         | 1        | 4.76%   |
| Prolific PL2305 Parallel Port          | 1        | 4.76%   |
| HP PSC-1315/PSC-1317                   | 1        | 4.76%   |
| HP LaserJet P2035                      | 1        | 4.76%   |
| HP ENVY Pro 6400 series                | 1        | 4.76%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1        | 4.76%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1        | 4.76%   |
| Canon TR8500 series                    | 1        | 4.76%   |
| Canon Pro9000II series                 | 1        | 4.76%   |
| Canon PIXMA MP240                      | 1        | 4.76%   |
| Brother MFC-L2700DW                    | 1        | 4.76%   |
| Brother MFC-5440CN                     | 1        | 4.76%   |
| Brother HL-3140CW series               | 1        | 4.76%   |
| Brother HL-2270DW Laser Printer        | 1        | 4.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| Canon          | 3        | 75%     |
| Mustek Systems | 1        | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Desktops | Percent |
|------------------------------------|----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1        | 25%     |
| Canon CanoScan N650U/N656U         | 1        | 25%     |
| Canon CanoScan LiDE 60             | 1        | 25%     |
| Canon CanoScan LiDE 200            | 1        | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 49       | 40.5%   |
| Sunplus Innovation Technology | 7        | 5.79%   |
| Microdia                      | 7        | 5.79%   |
| Samsung Electronics           | 5        | 4.13%   |
| Microsoft                     | 5        | 4.13%   |
| MacroSilicon                  | 4        | 3.31%   |
| Jieli Technology              | 4        | 3.31%   |
| Razer USA                     | 3        | 2.48%   |
| ARC International             | 3        | 2.48%   |
| Apple                         | 3        | 2.48%   |
| Valve Software                | 2        | 1.65%   |
| Sunplus IT                    | 2        | 1.65%   |
| Realtek Semiconductor         | 2        | 1.65%   |
| Cubeternet                    | 2        | 1.65%   |
| Creative Technology           | 2        | 1.65%   |
| AVerMedia Technologies        | 2        | 1.65%   |
| Z-Star Microelectronics       | 1        | 0.83%   |
| YGTek                         | 1        | 0.83%   |
| XHT-210518                    | 1        | 0.83%   |
| WaveRider Communications      | 1        | 0.83%   |
| Trust                         | 1        | 0.83%   |
| SN0002                        | 1        | 0.83%   |
| Novatek Microelectronics      | 1        | 0.83%   |
| LG Electronics                | 1        | 0.83%   |
| Lenovo                        | 1        | 0.83%   |
| KYE Systems (Mouse Systems)   | 1        | 0.83%   |
| icSpring                      | 1        | 0.83%   |
| HTC (High Tech Computer)      | 1        | 0.83%   |
| Hewlett-Packard               | 1        | 0.83%   |
| GenesysLogic Technology       | 1        | 0.83%   |
| Genesys Logic                 | 1        | 0.83%   |
| Generalplus Technology        | 1        | 0.83%   |
| eMeet                         | 1        | 0.83%   |
| Celestron                     | 1        | 0.83%   |
| 2M UVC CAMERA                 | 1        | 0.83%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Desktops | Percent |
|-----------------------------------------|----------|---------|
| Logitech Webcam C270                    | 12       | 9.92%   |
| Logitech HD Pro Webcam C920             | 10       | 8.26%   |
| Samsung Galaxy series, misc. (MTP mode) | 5        | 4.13%   |
| Logitech C922 Pro Stream Webcam         | 5        | 4.13%   |
| MacroSilicon USB Video                  | 4        | 3.31%   |
| Logitech Webcam C925e                   | 4        | 3.31%   |
| Jieli USB PHY 2.0                       | 4        | 3.31%   |
| Razer USA Gaming Webcam [Kiyo]          | 3        | 2.48%   |
| Microdia USB 2.0 Camera                 | 3        | 2.48%   |
| Logitech BRIO Ultra HD Webcam           | 3        | 2.48%   |
| ARC International Camera                | 3        | 2.48%   |
| Apple iPhone 5/5C/5S/6/SE               | 3        | 2.48%   |
| Valve Software 3D Camera                | 2        | 1.65%   |
| Sunplus IT AUKEY PC-LM1 USB Camera      | 2        | 1.65%   |
| Sunplus SPCA2281 Web Camera             | 2        | 1.65%   |
| Sunplus Full HD webcam                  | 2        | 1.65%   |
| Microsoft LifeCam HD-3000               | 2        | 1.65%   |
| Microsoft LifeCam Cinema                | 2        | 1.65%   |
| Microdia USB Live camera                | 2        | 1.65%   |
| Logitech Webcam C930e                   | 2        | 1.65%   |
| Logitech StreamCam                      | 2        | 1.65%   |
| Logitech HD Webcam C615                 | 2        | 1.65%   |
| Logitech HD Webcam C525                 | 2        | 1.65%   |
| Logitech C920 PRO HD Webcam             | 2        | 1.65%   |
| AVerMedia Live Streamer CAM 313         | 2        | 1.65%   |
| Z-Star USB2.0 Camera                    | 1        | 0.83%   |
| YGTek Webcam                            | 1        | 0.83%   |
| XHT-210518 EC500X                       | 1        | 0.83%   |
| WaveRider USB Live camera               | 1        | 0.83%   |
| Trust USB Camera                        | 1        | 0.83%   |
| Sunplus USB 2.0 Camera                  | 1        | 0.83%   |
| Sunplus HD 720P webcam                  | 1        | 0.83%   |
| Sunplus ezcap U3 capture                | 1        | 0.83%   |
| SN0002 1080P Web Camera                 | 1        | 0.83%   |
| Realtek USB Camera                      | 1        | 0.83%   |
| Realtek FULL HD 1080P Webcam            | 1        | 0.83%   |
| Novatek T2S Webcam                      | 1        | 0.83%   |
| Microsoft MicrosoftÂ LifeCam Studio    | 1        | 0.83%   |
| Microdia Webcam Vitade AF               | 1        | 0.83%   |
| Microdia Integrated Camera              | 1        | 0.83%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor         | Desktops | Percent |
|----------------|----------|---------|
| DigitalPersona | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                             | Desktops | Percent |
|-----------------------------------|----------|---------|
| DigitalPersona Fingerprint Reader | 1        | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| SCM Microsystems      | 1        | 33.33%  |
| Alcor Micro           | 1        | 33.33%  |
| Advanced Card Systems | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1        | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                    | 1        | 33.33%  |
| Advanced Card Systems ACR1252 Dual Reader              | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 398      | 83.61%  |
| 1     | 68       | 14.29%  |
| 2     | 9        | 1.89%   |
| 3     | 1        | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 30       | 35.29%  |
| Graphics card            | 18       | 21.18%  |
| Bluetooth                | 8        | 9.41%   |
| Unassigned class         | 7        | 8.24%   |
| Sound                    | 6        | 7.06%   |
| Net/ethernet             | 5        | 5.88%   |
| Chipcard                 | 3        | 3.53%   |
| Network                  | 2        | 2.35%   |
| Multimedia controller    | 2        | 2.35%   |
| Communication controller | 2        | 2.35%   |
| Storage/ide              | 1        | 1.18%   |
| Fingerprint reader       | 1        | 1.18%   |

