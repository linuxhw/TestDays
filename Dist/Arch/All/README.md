Arch - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for Arch.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Arch/Desktop/README.md) and [notebooks](/Dist/Arch/Notebook/README.md).

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

Total: 6918

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| UNOWHY        | Y13G012S4EI                 | Notebook    | [014d8c23f8](https://linux-hardware.org/?probe=014d8c23f8) | Oct 01, 2022 |
| Google        | Blooglet                    | Notebook    | [0081fa7064](https://linux-hardware.org/?probe=0081fa7064) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0a022a22c6](https://linux-hardware.org/?probe=0a022a22c6) | Oct 01, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [6f96dc34e2](https://linux-hardware.org/?probe=6f96dc34e2) | Oct 01, 2022 |
| HP            | 655                         | Notebook    | [6b10f9eda8](https://linux-hardware.org/?probe=6b10f9eda8) | Oct 01, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [fca2e4409a](https://linux-hardware.org/?probe=fca2e4409a) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [82e89b9263](https://linux-hardware.org/?probe=82e89b9263) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e64a9cf0e2](https://linux-hardware.org/?probe=e64a9cf0e2) | Oct 01, 2022 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [cffd9dadf8](https://linux-hardware.org/?probe=cffd9dadf8) | Oct 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4d1cbd14c2](https://linux-hardware.org/?probe=4d1cbd14c2) | Oct 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [00ded2a3ed](https://linux-hardware.org/?probe=00ded2a3ed) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bc6bcfe3f2](https://linux-hardware.org/?probe=bc6bcfe3f2) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [2d1e938e68](https://linux-hardware.org/?probe=2d1e938e68) | Oct 01, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [cfd0c22e29](https://linux-hardware.org/?probe=cfd0c22e29) | Sep 30, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [71ef5c4f0e](https://linux-hardware.org/?probe=71ef5c4f0e) | Sep 30, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [97e7d2d80f](https://linux-hardware.org/?probe=97e7d2d80f) | Sep 30, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [16f1ddb076](https://linux-hardware.org/?probe=16f1ddb076) | Sep 30, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1472407523](https://linux-hardware.org/?probe=1472407523) | Sep 30, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c4ccdf9992](https://linux-hardware.org/?probe=c4ccdf9992) | Sep 30, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [8ded1bb1f8](https://linux-hardware.org/?probe=8ded1bb1f8) | Sep 30, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [aa0eeeda6b](https://linux-hardware.org/?probe=aa0eeeda6b) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | Notebook    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| TUXEDO        | Book_XA1510                 | Notebook    | [f39b64916d](https://linux-hardware.org/?probe=f39b64916d) | Sep 29, 2022 |
| HP            | 8464                        | Desktop     | [52d29e8721](https://linux-hardware.org/?probe=52d29e8721) | Sep 29, 2022 |
| Lenovo        | ThinkPad T430 23501K0       | Notebook    | [124afba97e](https://linux-hardware.org/?probe=124afba97e) | Sep 28, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [ec3962c685](https://linux-hardware.org/?probe=ec3962c685) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [b12e5d06a3](https://linux-hardware.org/?probe=b12e5d06a3) | Sep 28, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [10b723415e](https://linux-hardware.org/?probe=10b723415e) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [960c35d712](https://linux-hardware.org/?probe=960c35d712) | Sep 28, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [216b090c47](https://linux-hardware.org/?probe=216b090c47) | Sep 28, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d4797ada2a](https://linux-hardware.org/?probe=d4797ada2a) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [4073c084df](https://linux-hardware.org/?probe=4073c084df) | Sep 28, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [03fff6add6](https://linux-hardware.org/?probe=03fff6add6) | Sep 27, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [3553d42d14](https://linux-hardware.org/?probe=3553d42d14) | Sep 27, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [88f0d42935](https://linux-hardware.org/?probe=88f0d42935) | Sep 27, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d7dcd834e2](https://linux-hardware.org/?probe=d7dcd834e2) | Sep 27, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | Notebook    | [56131c4db0](https://linux-hardware.org/?probe=56131c4db0) | Sep 27, 2022 |
| Timi          | TM1604                      | Notebook    | [2ee795db1a](https://linux-hardware.org/?probe=2ee795db1a) | Sep 27, 2022 |
| ASRock        | AB350 Gaming K4             | Desktop     | [184070d232](https://linux-hardware.org/?probe=184070d232) | Sep 26, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [89303afdb5](https://linux-hardware.org/?probe=89303afdb5) | Sep 26, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [e53b87c0fd](https://linux-hardware.org/?probe=e53b87c0fd) | Sep 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [95c0fd6047](https://linux-hardware.org/?probe=95c0fd6047) | Sep 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d9187e470e](https://linux-hardware.org/?probe=d9187e470e) | Sep 26, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [7bb3e847e2](https://linux-hardware.org/?probe=7bb3e847e2) | Sep 26, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [dce9d30a10](https://linux-hardware.org/?probe=dce9d30a10) | Sep 26, 2022 |
| Dell          | G15 5511                    | Notebook    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [75087953dd](https://linux-hardware.org/?probe=75087953dd) | Sep 26, 2022 |
| Gigabyte      | H61M-S2P-R3                 | Desktop     | [21d9eb0a71](https://linux-hardware.org/?probe=21d9eb0a71) | Sep 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [109d0ef34c](https://linux-hardware.org/?probe=109d0ef34c) | Sep 26, 2022 |
| MSI           | GS65 Stealth 9SE            | Notebook    | [0c8e0eb1f5](https://linux-hardware.org/?probe=0c8e0eb1f5) | Sep 26, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [6af4756d35](https://linux-hardware.org/?probe=6af4756d35) | Sep 25, 2022 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [382798365a](https://linux-hardware.org/?probe=382798365a) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0f4b7501b3](https://linux-hardware.org/?probe=0f4b7501b3) | Sep 25, 2022 |
| Intel         | NUC11ATBC4 M53051-302       | Mini pc     | [a398ca1184](https://linux-hardware.org/?probe=a398ca1184) | Sep 25, 2022 |
| ASUSTek       | PRIME Z590M-PLUS            | Desktop     | [ba4b216db1](https://linux-hardware.org/?probe=ba4b216db1) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [c6c3ce5c04](https://linux-hardware.org/?probe=c6c3ce5c04) | Sep 25, 2022 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [e939330716](https://linux-hardware.org/?probe=e939330716) | Sep 25, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [18246c5a9e](https://linux-hardware.org/?probe=18246c5a9e) | Sep 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [1ccf6c5c41](https://linux-hardware.org/?probe=1ccf6c5c41) | Sep 25, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0047e2de0e](https://linux-hardware.org/?probe=0047e2de0e) | Sep 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [bdc8453efc](https://linux-hardware.org/?probe=bdc8453efc) | Sep 24, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [0a4522a059](https://linux-hardware.org/?probe=0a4522a059) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | Notebook    | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [54bafde5a9](https://linux-hardware.org/?probe=54bafde5a9) | Sep 24, 2022 |
| Dell          | Precision 7560              | Notebook    | [8124a7a3eb](https://linux-hardware.org/?probe=8124a7a3eb) | Sep 24, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [7565f85860](https://linux-hardware.org/?probe=7565f85860) | Sep 24, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [efe1609ac0](https://linux-hardware.org/?probe=efe1609ac0) | Sep 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [6ccd3b916a](https://linux-hardware.org/?probe=6ccd3b916a) | Sep 24, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2b886fd64c](https://linux-hardware.org/?probe=2b886fd64c) | Sep 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [055cd5f884](https://linux-hardware.org/?probe=055cd5f884) | Sep 23, 2022 |
| Lenovo        | ThinkPad P52s 20LCS03L38    | Notebook    | [5d9c8cd268](https://linux-hardware.org/?probe=5d9c8cd268) | Sep 23, 2022 |
| Intel         | NUC8BEB J72688-309          | Mini pc     | [7d035aef45](https://linux-hardware.org/?probe=7d035aef45) | Sep 23, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [31f002c762](https://linux-hardware.org/?probe=31f002c762) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [17ff3f8067](https://linux-hardware.org/?probe=17ff3f8067) | Sep 22, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Gigabyte      | Z690 AORUS ELITE AX DDR4    | Desktop     | [74dcd96704](https://linux-hardware.org/?probe=74dcd96704) | Sep 22, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [672d6f2fc8](https://linux-hardware.org/?probe=672d6f2fc8) | Sep 22, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [5657597c18](https://linux-hardware.org/?probe=5657597c18) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a766b7b9d0](https://linux-hardware.org/?probe=a766b7b9d0) | Sep 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [34fea4fedc](https://linux-hardware.org/?probe=34fea4fedc) | Sep 22, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [d79e046c6d](https://linux-hardware.org/?probe=d79e046c6d) | Sep 22, 2022 |
| Intel         | DN2800MT AAG23738-801       | Desktop     | [0019b51cff](https://linux-hardware.org/?probe=0019b51cff) | Sep 21, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [52bb32a60c](https://linux-hardware.org/?probe=52bb32a60c) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| ASRock        | Z690 Pro RS                 | Desktop     | [787589762f](https://linux-hardware.org/?probe=787589762f) | Sep 21, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [628fd0d32d](https://linux-hardware.org/?probe=628fd0d32d) | Sep 21, 2022 |
| Intel         | H55                         | Desktop     | [6de435d14c](https://linux-hardware.org/?probe=6de435d14c) | Sep 20, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [88cbbeaee6](https://linux-hardware.org/?probe=88cbbeaee6) | Sep 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [3aeb184ce4](https://linux-hardware.org/?probe=3aeb184ce4) | Sep 20, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [6fc004b792](https://linux-hardware.org/?probe=6fc004b792) | Sep 20, 2022 |
| HP            | EliteBook 850 G3            | Notebook    | [7bbcf621e1](https://linux-hardware.org/?probe=7bbcf621e1) | Sep 20, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [16d661b4e5](https://linux-hardware.org/?probe=16d661b4e5) | Sep 20, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [06d6be8b85](https://linux-hardware.org/?probe=06d6be8b85) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [b84e8d2682](https://linux-hardware.org/?probe=b84e8d2682) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [4779dfc2b0](https://linux-hardware.org/?probe=4779dfc2b0) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [37673aa4e2](https://linux-hardware.org/?probe=37673aa4e2) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [38234e238c](https://linux-hardware.org/?probe=38234e238c) | Sep 20, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a1f237c86a](https://linux-hardware.org/?probe=a1f237c86a) | Sep 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [b07937de6a](https://linux-hardware.org/?probe=b07937de6a) | Sep 20, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [54d0318e27](https://linux-hardware.org/?probe=54d0318e27) | Sep 20, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [97426638ff](https://linux-hardware.org/?probe=97426638ff) | Sep 20, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [5367a8e71f](https://linux-hardware.org/?probe=5367a8e71f) | Sep 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b6192d691a](https://linux-hardware.org/?probe=b6192d691a) | Sep 20, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [fed50b9211](https://linux-hardware.org/?probe=fed50b9211) | Sep 19, 2022 |
| Gigabyte      | A520M DS3H AC               | Desktop     | [9d26eb4243](https://linux-hardware.org/?probe=9d26eb4243) | Sep 19, 2022 |
| Huanan        | X99-F8 Gaming 2021          | Desktop     | [8a290737bd](https://linux-hardware.org/?probe=8a290737bd) | Sep 19, 2022 |
| Dell          | Latitude 7390               | Notebook    | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [8c4a94cb33](https://linux-hardware.org/?probe=8c4a94cb33) | Sep 19, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [42bc6e4e69](https://linux-hardware.org/?probe=42bc6e4e69) | Sep 19, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a479d9ef5f](https://linux-hardware.org/?probe=a479d9ef5f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [e149495b74](https://linux-hardware.org/?probe=e149495b74) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [57ab60faec](https://linux-hardware.org/?probe=57ab60faec) | Sep 19, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [3862ccf53f](https://linux-hardware.org/?probe=3862ccf53f) | Sep 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f52b35d82d](https://linux-hardware.org/?probe=f52b35d82d) | Sep 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [06f5febda2](https://linux-hardware.org/?probe=06f5febda2) | Sep 19, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [9d61a37458](https://linux-hardware.org/?probe=9d61a37458) | Sep 19, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [58d84150d6](https://linux-hardware.org/?probe=58d84150d6) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [cd1441d5a4](https://linux-hardware.org/?probe=cd1441d5a4) | Sep 18, 2022 |
| PCWare        | IPMH110G                    | Desktop     | [6ba309be15](https://linux-hardware.org/?probe=6ba309be15) | Sep 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [aa3908e5fc](https://linux-hardware.org/?probe=aa3908e5fc) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [36a7673265](https://linux-hardware.org/?probe=36a7673265) | Sep 17, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [980e4272fb](https://linux-hardware.org/?probe=980e4272fb) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [abca74f17e](https://linux-hardware.org/?probe=abca74f17e) | Sep 17, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e6c4a47a86](https://linux-hardware.org/?probe=e6c4a47a86) | Sep 17, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [3ba3a4becf](https://linux-hardware.org/?probe=3ba3a4becf) | Sep 16, 2022 |
| Gateway       | SX2803                      | Desktop     | [870c8a3ff4](https://linux-hardware.org/?probe=870c8a3ff4) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fbe2b37462](https://linux-hardware.org/?probe=fbe2b37462) | Sep 16, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a26e1ad502](https://linux-hardware.org/?probe=a26e1ad502) | Sep 15, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [800fd51ccb](https://linux-hardware.org/?probe=800fd51ccb) | Sep 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6ff152e455](https://linux-hardware.org/?probe=6ff152e455) | Sep 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [9e0c10b8e3](https://linux-hardware.org/?probe=9e0c10b8e3) | Sep 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7f6ce1e4ea](https://linux-hardware.org/?probe=7f6ce1e4ea) | Sep 14, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [efde420a70](https://linux-hardware.org/?probe=efde420a70) | Sep 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [d0d43b3cc5](https://linux-hardware.org/?probe=d0d43b3cc5) | Sep 14, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [b7ed5c7f4a](https://linux-hardware.org/?probe=b7ed5c7f4a) | Sep 14, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [962c59a3ba](https://linux-hardware.org/?probe=962c59a3ba) | Sep 13, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| Acer          | Aspire X3990                | Desktop     | [64cddc5f85](https://linux-hardware.org/?probe=64cddc5f85) | Sep 13, 2022 |
| Samsung       | 950XED                      | Notebook    | [f8a15210f0](https://linux-hardware.org/?probe=f8a15210f0) | Sep 13, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3c37d36ba8](https://linux-hardware.org/?probe=3c37d36ba8) | Sep 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6ddf2bafef](https://linux-hardware.org/?probe=6ddf2bafef) | Sep 13, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [2de3999743](https://linux-hardware.org/?probe=2de3999743) | Sep 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1b8d9a04ae](https://linux-hardware.org/?probe=1b8d9a04ae) | Sep 13, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [5ae6fea41e](https://linux-hardware.org/?probe=5ae6fea41e) | Sep 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [93567a4d15](https://linux-hardware.org/?probe=93567a4d15) | Sep 13, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [7fb82d496f](https://linux-hardware.org/?probe=7fb82d496f) | Sep 12, 2022 |
| Dell          | Vostro 3491                 | Notebook    | [24d4349627](https://linux-hardware.org/?probe=24d4349627) | Sep 12, 2022 |
| Toshiba       | Satellite U845W             | Notebook    | [030a371841](https://linux-hardware.org/?probe=030a371841) | Sep 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [321432c752](https://linux-hardware.org/?probe=321432c752) | Sep 12, 2022 |
| HP            | 3047h                       | Desktop     | [097b5b2f29](https://linux-hardware.org/?probe=097b5b2f29) | Sep 12, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [8b44500d70](https://linux-hardware.org/?probe=8b44500d70) | Sep 12, 2022 |
| Chuwi         | UBook                       | Tablet      | [89a54f0af1](https://linux-hardware.org/?probe=89a54f0af1) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [410b905321](https://linux-hardware.org/?probe=410b905321) | Sep 11, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [c55fd8d477](https://linux-hardware.org/?probe=c55fd8d477) | Sep 11, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [c59ebfd9e8](https://linux-hardware.org/?probe=c59ebfd9e8) | Sep 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [46c51b7097](https://linux-hardware.org/?probe=46c51b7097) | Sep 11, 2022 |
| Dell          | Latitude 7424 Rugged Ext... | Notebook    | [0e5e98a9e2](https://linux-hardware.org/?probe=0e5e98a9e2) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d2c057ed6e](https://linux-hardware.org/?probe=d2c057ed6e) | Sep 11, 2022 |
| Lenovo        | Yoga 720-15IKB              | Convertible | [078c865d26](https://linux-hardware.org/?probe=078c865d26) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | Notebook    | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ee06685499](https://linux-hardware.org/?probe=ee06685499) | Sep 11, 2022 |
| Samsung       | 750XED                      | Notebook    | [ea68f0910d](https://linux-hardware.org/?probe=ea68f0910d) | Sep 10, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [be7516b088](https://linux-hardware.org/?probe=be7516b088) | Sep 10, 2022 |
| Samsung       | 750XED                      | Notebook    | [475088329e](https://linux-hardware.org/?probe=475088329e) | Sep 10, 2022 |
| Framework     | Laptop                      | Notebook    | [b0b7801b11](https://linux-hardware.org/?probe=b0b7801b11) | Sep 10, 2022 |
| Lenovo        | ThinkPad X230 23252QG       | Notebook    | [4146ff55f9](https://linux-hardware.org/?probe=4146ff55f9) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [3c214d75b2](https://linux-hardware.org/?probe=3c214d75b2) | Sep 10, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e8c2730c9](https://linux-hardware.org/?probe=1e8c2730c9) | Sep 10, 2022 |
| Dell          | 0VNM11 A00                  | Desktop     | [9ae0ae5ac4](https://linux-hardware.org/?probe=9ae0ae5ac4) | Sep 10, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [80626826a3](https://linux-hardware.org/?probe=80626826a3) | Sep 10, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [4911a898bd](https://linux-hardware.org/?probe=4911a898bd) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d9c6274ead](https://linux-hardware.org/?probe=d9c6274ead) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f5c538e2c7](https://linux-hardware.org/?probe=f5c538e2c7) | Sep 09, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [c61b5df29b](https://linux-hardware.org/?probe=c61b5df29b) | Sep 09, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [8e84bc9dac](https://linux-hardware.org/?probe=8e84bc9dac) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [43311add57](https://linux-hardware.org/?probe=43311add57) | Sep 09, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c13cd2c2ac](https://linux-hardware.org/?probe=c13cd2c2ac) | Sep 09, 2022 |
| Medion        | S4216                       | Notebook    | [1f1e6b24bf](https://linux-hardware.org/?probe=1f1e6b24bf) | Sep 08, 2022 |
| Dell          | Latitude 7350               | Notebook    | [4a30d9431e](https://linux-hardware.org/?probe=4a30d9431e) | Sep 08, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [718876491c](https://linux-hardware.org/?probe=718876491c) | Sep 08, 2022 |
| MSI           | B550M-A PRO                 | Desktop     | [b2cd3df6bc](https://linux-hardware.org/?probe=b2cd3df6bc) | Sep 08, 2022 |
| Google        | Rabbid                      | Notebook    | [636b8205ae](https://linux-hardware.org/?probe=636b8205ae) | Sep 08, 2022 |
| Google        | Rabbid                      | Notebook    | [f33074ee09](https://linux-hardware.org/?probe=f33074ee09) | Sep 08, 2022 |
| LG Electro... | 17Z90P-G.AA86D              | Notebook    | [1f304e9792](https://linux-hardware.org/?probe=1f304e9792) | Sep 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [a5fdc97073](https://linux-hardware.org/?probe=a5fdc97073) | Sep 07, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [c89a7d5488](https://linux-hardware.org/?probe=c89a7d5488) | Sep 07, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [52f4b6e022](https://linux-hardware.org/?probe=52f4b6e022) | Sep 07, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [b5270dfd32](https://linux-hardware.org/?probe=b5270dfd32) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e88363a341](https://linux-hardware.org/?probe=e88363a341) | Sep 07, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [c8a237d75e](https://linux-hardware.org/?probe=c8a237d75e) | Sep 07, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [ec22409311](https://linux-hardware.org/?probe=ec22409311) | Sep 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [803410686e](https://linux-hardware.org/?probe=803410686e) | Sep 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [2d00daa9f6](https://linux-hardware.org/?probe=2d00daa9f6) | Sep 07, 2022 |
| Fujitsu       | LIFEBOOK U9311X             | Convertible | [934e3e7ff1](https://linux-hardware.org/?probe=934e3e7ff1) | Sep 06, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [893afb133c](https://linux-hardware.org/?probe=893afb133c) | Sep 06, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [bddf00d17f](https://linux-hardware.org/?probe=bddf00d17f) | Sep 06, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5733156bf5](https://linux-hardware.org/?probe=5733156bf5) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [a4f8e52425](https://linux-hardware.org/?probe=a4f8e52425) | Sep 06, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d88badf739](https://linux-hardware.org/?probe=d88badf739) | Sep 06, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [3ce6c0f44c](https://linux-hardware.org/?probe=3ce6c0f44c) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [0daca2662d](https://linux-hardware.org/?probe=0daca2662d) | Sep 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [acb5c353ed](https://linux-hardware.org/?probe=acb5c353ed) | Sep 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [d55d359a3e](https://linux-hardware.org/?probe=d55d359a3e) | Sep 05, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e37ba07a92](https://linux-hardware.org/?probe=e37ba07a92) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [7eba2962c6](https://linux-hardware.org/?probe=7eba2962c6) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [92d04feeca](https://linux-hardware.org/?probe=92d04feeca) | Sep 05, 2022 |
| Dell          | Precision 3571              | Notebook    | [d9939fbfd4](https://linux-hardware.org/?probe=d9939fbfd4) | Sep 05, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e12af15c84](https://linux-hardware.org/?probe=e12af15c84) | Sep 05, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [43f7cbff06](https://linux-hardware.org/?probe=43f7cbff06) | Sep 05, 2022 |
| Google        | Coral                       | Notebook    | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [aa90cb0d30](https://linux-hardware.org/?probe=aa90cb0d30) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [bf4936f3bc](https://linux-hardware.org/?probe=bf4936f3bc) | Sep 04, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [a746f6faa6](https://linux-hardware.org/?probe=a746f6faa6) | Sep 04, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [c9d51bfae8](https://linux-hardware.org/?probe=c9d51bfae8) | Sep 04, 2022 |
| Samsung       | 950QDB                      | Convertible | [ec7cdfdff7](https://linux-hardware.org/?probe=ec7cdfdff7) | Sep 04, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [3064d08dc1](https://linux-hardware.org/?probe=3064d08dc1) | Sep 03, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [87a6f9162a](https://linux-hardware.org/?probe=87a6f9162a) | Sep 03, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [6de688d21a](https://linux-hardware.org/?probe=6de688d21a) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e30f86bc30](https://linux-hardware.org/?probe=e30f86bc30) | Sep 03, 2022 |
| Dell          | Latitude 7350               | Notebook    | [f52406cbf2](https://linux-hardware.org/?probe=f52406cbf2) | Sep 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b313706909](https://linux-hardware.org/?probe=b313706909) | Sep 03, 2022 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [0151fa47ef](https://linux-hardware.org/?probe=0151fa47ef) | Sep 03, 2022 |
| TUXEDO        | Book_XA1510                 | Notebook    | [e379f966da](https://linux-hardware.org/?probe=e379f966da) | Sep 03, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [0f5aab705f](https://linux-hardware.org/?probe=0f5aab705f) | Sep 03, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [7ec410bfe6](https://linux-hardware.org/?probe=7ec410bfe6) | Sep 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [08cfa37b81](https://linux-hardware.org/?probe=08cfa37b81) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [9c22b70a4f](https://linux-hardware.org/?probe=9c22b70a4f) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [5d6b0d60df](https://linux-hardware.org/?probe=5d6b0d60df) | Sep 03, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [65bfdaa6ea](https://linux-hardware.org/?probe=65bfdaa6ea) | Sep 03, 2022 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [4d9025cf5c](https://linux-hardware.org/?probe=4d9025cf5c) | Sep 03, 2022 |
| HP            | 15                          | Notebook    | [48493c0282](https://linux-hardware.org/?probe=48493c0282) | Sep 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [2199481d0a](https://linux-hardware.org/?probe=2199481d0a) | Sep 03, 2022 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [4489539bae](https://linux-hardware.org/?probe=4489539bae) | Sep 03, 2022 |
| Lenovo        | ThinkPad L390 20NSS11E00    | Notebook    | [d5dbbd658f](https://linux-hardware.org/?probe=d5dbbd658f) | Sep 03, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [e7e5ddf474](https://linux-hardware.org/?probe=e7e5ddf474) | Sep 03, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [a20f64b93b](https://linux-hardware.org/?probe=a20f64b93b) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [7c04c344cb](https://linux-hardware.org/?probe=7c04c344cb) | Sep 02, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7829cfc920](https://linux-hardware.org/?probe=7829cfc920) | Sep 02, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [b06eacf424](https://linux-hardware.org/?probe=b06eacf424) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [cd935b0146](https://linux-hardware.org/?probe=cd935b0146) | Sep 02, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| MSI           | X99A GAMING 7               | Desktop     | [347f4d8534](https://linux-hardware.org/?probe=347f4d8534) | Sep 02, 2022 |
| Gigabyte      | H310N x.x                   | Desktop     | [c6c8617f48](https://linux-hardware.org/?probe=c6c8617f48) | Sep 02, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [f1cfdb5e32](https://linux-hardware.org/?probe=f1cfdb5e32) | Sep 02, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [fadbc676b4](https://linux-hardware.org/?probe=fadbc676b4) | Sep 02, 2022 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [d510db88c4](https://linux-hardware.org/?probe=d510db88c4) | Sep 02, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [4f9267de27](https://linux-hardware.org/?probe=4f9267de27) | Sep 02, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [6456a1b04f](https://linux-hardware.org/?probe=6456a1b04f) | Sep 02, 2022 |
| Acer          | Aspire 4349                 | Notebook    | [1918459ea4](https://linux-hardware.org/?probe=1918459ea4) | Sep 02, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [cfdc88587a](https://linux-hardware.org/?probe=cfdc88587a) | Sep 02, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b0750b0e0a](https://linux-hardware.org/?probe=b0750b0e0a) | Sep 02, 2022 |
| HP            | EliteBook x360 830 G6       | Convertible | [751aeabd5d](https://linux-hardware.org/?probe=751aeabd5d) | Sep 01, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [f88772c4dc](https://linux-hardware.org/?probe=f88772c4dc) | Sep 01, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [0cb5fbde81](https://linux-hardware.org/?probe=0cb5fbde81) | Sep 01, 2022 |
| Purism        | Librem 14                   | Notebook    | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8fc60cb459](https://linux-hardware.org/?probe=8fc60cb459) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [c9841acd77](https://linux-hardware.org/?probe=c9841acd77) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [8e1734f31a](https://linux-hardware.org/?probe=8e1734f31a) | Sep 01, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [7ff88a93c2](https://linux-hardware.org/?probe=7ff88a93c2) | Sep 01, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [c63c5e6700](https://linux-hardware.org/?probe=c63c5e6700) | Aug 31, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [bbe5fe0eac](https://linux-hardware.org/?probe=bbe5fe0eac) | Aug 31, 2022 |
| HP            | 18E5                        | Desktop     | [e7c5ab6cc4](https://linux-hardware.org/?probe=e7c5ab6cc4) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | Notebook    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | Notebook    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Notebook      | NH5xAx                      | Notebook    | [e8487cd15f](https://linux-hardware.org/?probe=e8487cd15f) | Aug 31, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [ef34b3c3aa](https://linux-hardware.org/?probe=ef34b3c3aa) | Aug 31, 2022 |
| 16512-2316... | MPG X570 GAMING EDGE WIF... | Desktop     | [d523a89d9b](https://linux-hardware.org/?probe=d523a89d9b) | Aug 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [3d7c0ee13d](https://linux-hardware.org/?probe=3d7c0ee13d) | Aug 30, 2022 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [dcdfb21686](https://linux-hardware.org/?probe=dcdfb21686) | Aug 30, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [393cb25da2](https://linux-hardware.org/?probe=393cb25da2) | Aug 30, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [c5a0ce2143](https://linux-hardware.org/?probe=c5a0ce2143) | Aug 30, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [2e6d572c33](https://linux-hardware.org/?probe=2e6d572c33) | Aug 30, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [d972083fa3](https://linux-hardware.org/?probe=d972083fa3) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [4ea311ca8e](https://linux-hardware.org/?probe=4ea311ca8e) | Aug 30, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [1a8ff186c7](https://linux-hardware.org/?probe=1a8ff186c7) | Aug 29, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [4b37519faf](https://linux-hardware.org/?probe=4b37519faf) | Aug 29, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1ff074d641](https://linux-hardware.org/?probe=1ff074d641) | Aug 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c44a50e117](https://linux-hardware.org/?probe=c44a50e117) | Aug 29, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [e3e8a26940](https://linux-hardware.org/?probe=e3e8a26940) | Aug 29, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [c107217cf8](https://linux-hardware.org/?probe=c107217cf8) | Aug 28, 2022 |
| MSI           | B75A-G41                    | Desktop     | [1d0e275f3e](https://linux-hardware.org/?probe=1d0e275f3e) | Aug 28, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [9a83e7ee58](https://linux-hardware.org/?probe=9a83e7ee58) | Aug 28, 2022 |
| Framework     | Laptop                      | Notebook    | [71c896cd39](https://linux-hardware.org/?probe=71c896cd39) | Aug 28, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [b40621d5f6](https://linux-hardware.org/?probe=b40621d5f6) | Aug 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | Notebook    | [1d29556c76](https://linux-hardware.org/?probe=1d29556c76) | Aug 28, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [25e4d6c064](https://linux-hardware.org/?probe=25e4d6c064) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| BBEN          | G16                         | Notebook    | [6b0b170e1c](https://linux-hardware.org/?probe=6b0b170e1c) | Aug 28, 2022 |
| BBEN          | G16                         | Notebook    | [66fc9bd46b](https://linux-hardware.org/?probe=66fc9bd46b) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [638f08fc43](https://linux-hardware.org/?probe=638f08fc43) | Aug 27, 2022 |
| Dell          | Latitude 3150               | Notebook    | [09f1514148](https://linux-hardware.org/?probe=09f1514148) | Aug 27, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [8ccf243309](https://linux-hardware.org/?probe=8ccf243309) | Aug 27, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [24164369fd](https://linux-hardware.org/?probe=24164369fd) | Aug 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8841ba5f53](https://linux-hardware.org/?probe=8841ba5f53) | Aug 27, 2022 |
| HP            | 8054                        | Desktop     | [af4f950786](https://linux-hardware.org/?probe=af4f950786) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [37bdc91d97](https://linux-hardware.org/?probe=37bdc91d97) | Aug 26, 2022 |
| Dell          | Latitude 7350               | Notebook    | [c784fd2743](https://linux-hardware.org/?probe=c784fd2743) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [c0b89ea222](https://linux-hardware.org/?probe=c0b89ea222) | Aug 26, 2022 |
| Lenovo        | ThinkPad T430 2344BMU       | Notebook    | [c164d20c15](https://linux-hardware.org/?probe=c164d20c15) | Aug 26, 2022 |
| Dell          | Latitude 7424 Rugged Ext... | Notebook    | [9770e301cd](https://linux-hardware.org/?probe=9770e301cd) | Aug 26, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [5c8244526c](https://linux-hardware.org/?probe=5c8244526c) | Aug 25, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [da0b51aa63](https://linux-hardware.org/?probe=da0b51aa63) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d8286d5ca0](https://linux-hardware.org/?probe=d8286d5ca0) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b7263cf041](https://linux-hardware.org/?probe=b7263cf041) | Aug 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [13cd1e5eed](https://linux-hardware.org/?probe=13cd1e5eed) | Aug 25, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [866cc080e0](https://linux-hardware.org/?probe=866cc080e0) | Aug 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fcfd89bb32](https://linux-hardware.org/?probe=fcfd89bb32) | Aug 25, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [c579b49e4c](https://linux-hardware.org/?probe=c579b49e4c) | Aug 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [156da35e98](https://linux-hardware.org/?probe=156da35e98) | Aug 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b8af477a84](https://linux-hardware.org/?probe=b8af477a84) | Aug 24, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [e51675ce88](https://linux-hardware.org/?probe=e51675ce88) | Aug 24, 2022 |
| ASRock        | AD2550-ITX                  | Desktop     | [79e491790d](https://linux-hardware.org/?probe=79e491790d) | Aug 24, 2022 |
| ASUSTek       | X751LD                      | Notebook    | [7ce95dab0a](https://linux-hardware.org/?probe=7ce95dab0a) | Aug 24, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [e3d3a359b5](https://linux-hardware.org/?probe=e3d3a359b5) | Aug 24, 2022 |
| MSI           | MEG Z490 GODLIKE            | Desktop     | [eb92b93947](https://linux-hardware.org/?probe=eb92b93947) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Samsung       | 730QAA                      | Convertible | [be9b44a8c5](https://linux-hardware.org/?probe=be9b44a8c5) | Aug 24, 2022 |
| Dell          | XPS L421X                   | Notebook    | [227df9dc9e](https://linux-hardware.org/?probe=227df9dc9e) | Aug 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8af1d0e421](https://linux-hardware.org/?probe=8af1d0e421) | Aug 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| LG Electro... | S430-G.BC33P1               | Notebook    | [d0b4cf47fe](https://linux-hardware.org/?probe=d0b4cf47fe) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1d0c242f30](https://linux-hardware.org/?probe=1d0c242f30) | Aug 23, 2022 |
| Acer          | Swift SF114-33              | Notebook    | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| MSI           | GS73VR 6RF                  | Notebook    | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| MSI           | Z87-GD65 GAMING             | Desktop     | [f6f358dde8](https://linux-hardware.org/?probe=f6f358dde8) | Aug 23, 2022 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [d7dee32799](https://linux-hardware.org/?probe=d7dee32799) | Aug 23, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [7004b23b33](https://linux-hardware.org/?probe=7004b23b33) | Aug 23, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [46c6096b6e](https://linux-hardware.org/?probe=46c6096b6e) | Aug 23, 2022 |
| ASRock        | Z170M Pro4S                 | Desktop     | [0bfb94df6e](https://linux-hardware.org/?probe=0bfb94df6e) | Aug 23, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [93f28535f8](https://linux-hardware.org/?probe=93f28535f8) | Aug 23, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [6cc47c9a0d](https://linux-hardware.org/?probe=6cc47c9a0d) | Aug 23, 2022 |
| Acer          | Predator G3-710             | Desktop     | [7a58c9348e](https://linux-hardware.org/?probe=7a58c9348e) | Aug 22, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [e3169f9b1c](https://linux-hardware.org/?probe=e3169f9b1c) | Aug 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [0d626db6e1](https://linux-hardware.org/?probe=0d626db6e1) | Aug 22, 2022 |
| ASRock        | Z75 Pro3                    | Desktop     | [4fbe3d2710](https://linux-hardware.org/?probe=4fbe3d2710) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [d08e00053f](https://linux-hardware.org/?probe=d08e00053f) | Aug 22, 2022 |
| Dell          | 052RF2 A01                  | Server      | [82830908ab](https://linux-hardware.org/?probe=82830908ab) | Aug 22, 2022 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [8898d24c48](https://linux-hardware.org/?probe=8898d24c48) | Aug 22, 2022 |
| Toshiba       | Satellite P55t-C            | Notebook    | [70560700a6](https://linux-hardware.org/?probe=70560700a6) | Aug 22, 2022 |
| ASUSTek       | X555UB                      | Notebook    | [a1db92c63c](https://linux-hardware.org/?probe=a1db92c63c) | Aug 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [ada7663387](https://linux-hardware.org/?probe=ada7663387) | Aug 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [14cade3bfe](https://linux-hardware.org/?probe=14cade3bfe) | Aug 21, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [750425c2c2](https://linux-hardware.org/?probe=750425c2c2) | Aug 21, 2022 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [4875c1533b](https://linux-hardware.org/?probe=4875c1533b) | Aug 21, 2022 |
| BBEN          | G16                         | Notebook    | [f9768aedb9](https://linux-hardware.org/?probe=f9768aedb9) | Aug 21, 2022 |
| BBEN          | G16                         | Notebook    | [d491f08ce0](https://linux-hardware.org/?probe=d491f08ce0) | Aug 21, 2022 |
| HP            | Pavilion g4                 | Notebook    | [f8c2fc628e](https://linux-hardware.org/?probe=f8c2fc628e) | Aug 21, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [e31fb3f3cf](https://linux-hardware.org/?probe=e31fb3f3cf) | Aug 21, 2022 |
| HP            | ENVY 15                     | Notebook    | [5d984dedf6](https://linux-hardware.org/?probe=5d984dedf6) | Aug 20, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [9a8166de9b](https://linux-hardware.org/?probe=9a8166de9b) | Aug 20, 2022 |
| realme        | RMNBXXXX                    | Notebook    | [d98be8821f](https://linux-hardware.org/?probe=d98be8821f) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [c1b5d9ffc1](https://linux-hardware.org/?probe=c1b5d9ffc1) | Aug 19, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [001ac5c374](https://linux-hardware.org/?probe=001ac5c374) | Aug 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c6bb19402d](https://linux-hardware.org/?probe=c6bb19402d) | Aug 19, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [e32743d60f](https://linux-hardware.org/?probe=e32743d60f) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Framework     | Laptop                      | Notebook    | [a8988f1665](https://linux-hardware.org/?probe=a8988f1665) | Aug 18, 2022 |
| Dell          | Latitude 7390               | Notebook    | [d726450b55](https://linux-hardware.org/?probe=d726450b55) | Aug 18, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [83d7ac44e3](https://linux-hardware.org/?probe=83d7ac44e3) | Aug 18, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [16b9aa5d1b](https://linux-hardware.org/?probe=16b9aa5d1b) | Aug 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | Notebook    | [0dbc32a26d](https://linux-hardware.org/?probe=0dbc32a26d) | Aug 17, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [6a95ac6709](https://linux-hardware.org/?probe=6a95ac6709) | Aug 17, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [abad46b854](https://linux-hardware.org/?probe=abad46b854) | Aug 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| TPVAOC        | AA183M                      | Notebook    | [089472ea13](https://linux-hardware.org/?probe=089472ea13) | Aug 16, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [3e3ab3842f](https://linux-hardware.org/?probe=3e3ab3842f) | Aug 16, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [1d2b1aa4bf](https://linux-hardware.org/?probe=1d2b1aa4bf) | Aug 16, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8341abd9e2](https://linux-hardware.org/?probe=8341abd9e2) | Aug 16, 2022 |
| Lenovo        | Yoga 720-15IKB              | Convertible | [33bd89a7e0](https://linux-hardware.org/?probe=33bd89a7e0) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| HP            | ENVY m7                     | Notebook    | [9142b4fff0](https://linux-hardware.org/?probe=9142b4fff0) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | Notebook    | [0a48289c39](https://linux-hardware.org/?probe=0a48289c39) | Aug 16, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [71395858f4](https://linux-hardware.org/?probe=71395858f4) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [3799febe71](https://linux-hardware.org/?probe=3799febe71) | Aug 16, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [35cd057234](https://linux-hardware.org/?probe=35cd057234) | Aug 16, 2022 |
| Dell          | 0H21J3 A04                  | Server      | [14f7add408](https://linux-hardware.org/?probe=14f7add408) | Aug 16, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [f223d64d8f](https://linux-hardware.org/?probe=f223d64d8f) | Aug 15, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [855a5955c8](https://linux-hardware.org/?probe=855a5955c8) | Aug 15, 2022 |
| Acer          | Celadon-RN                  | Notebook    | [043b0c9fd7](https://linux-hardware.org/?probe=043b0c9fd7) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [4e05ac232c](https://linux-hardware.org/?probe=4e05ac232c) | Aug 15, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [08bf3d620e](https://linux-hardware.org/?probe=08bf3d620e) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | Notebook    | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1e198f7c54](https://linux-hardware.org/?probe=1e198f7c54) | Aug 15, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [1db8ed0da4](https://linux-hardware.org/?probe=1db8ed0da4) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [105367d5d6](https://linux-hardware.org/?probe=105367d5d6) | Aug 14, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [7817924a07](https://linux-hardware.org/?probe=7817924a07) | Aug 14, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [286fd1791a](https://linux-hardware.org/?probe=286fd1791a) | Aug 14, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [d0831907e8](https://linux-hardware.org/?probe=d0831907e8) | Aug 14, 2022 |
| Dell          | 0978PJ A03                  | Server      | [382f999542](https://linux-hardware.org/?probe=382f999542) | Aug 14, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4e7f1dc861](https://linux-hardware.org/?probe=4e7f1dc861) | Aug 13, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97f75c2be0](https://linux-hardware.org/?probe=97f75c2be0) | Aug 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1C00... | Notebook    | [dbbae31450](https://linux-hardware.org/?probe=dbbae31450) | Aug 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [ee2f627cb6](https://linux-hardware.org/?probe=ee2f627cb6) | Aug 13, 2022 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Convertible | [c926de11d3](https://linux-hardware.org/?probe=c926de11d3) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [c001e6e62b](https://linux-hardware.org/?probe=c001e6e62b) | Aug 12, 2022 |
| ASUSTek       | GL552VX                     | Notebook    | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [0045f412a9](https://linux-hardware.org/?probe=0045f412a9) | Aug 12, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [c63936c0ef](https://linux-hardware.org/?probe=c63936c0ef) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [e3be6b79c1](https://linux-hardware.org/?probe=e3be6b79c1) | Aug 12, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [fad6aace6a](https://linux-hardware.org/?probe=fad6aace6a) | Aug 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [69843536ef](https://linux-hardware.org/?probe=69843536ef) | Aug 11, 2022 |
| HP            | 2B4B                        | Desktop     | [6763057a55](https://linux-hardware.org/?probe=6763057a55) | Aug 11, 2022 |
| HP            | ProBook 640 G5              | Notebook    | [321cb5faf4](https://linux-hardware.org/?probe=321cb5faf4) | Aug 11, 2022 |
| HP            | ProBook 640 G5              | Notebook    | [b71c89e139](https://linux-hardware.org/?probe=b71c89e139) | Aug 11, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [3f67c470be](https://linux-hardware.org/?probe=3f67c470be) | Aug 11, 2022 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [673ef8a276](https://linux-hardware.org/?probe=673ef8a276) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [d61320f9c5](https://linux-hardware.org/?probe=d61320f9c5) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [bc7a8afe56](https://linux-hardware.org/?probe=bc7a8afe56) | Aug 11, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [27b3fb870a](https://linux-hardware.org/?probe=27b3fb870a) | Aug 11, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [94a67b764b](https://linux-hardware.org/?probe=94a67b764b) | Aug 11, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [0009de2dbb](https://linux-hardware.org/?probe=0009de2dbb) | Aug 11, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [534c1142c2](https://linux-hardware.org/?probe=534c1142c2) | Aug 10, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0724d34f68](https://linux-hardware.org/?probe=0724d34f68) | Aug 10, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [644f2ccaaf](https://linux-hardware.org/?probe=644f2ccaaf) | Aug 10, 2022 |
| Lenovo        | IdeaPad Y410P 20216         | Notebook    | [df3068aea1](https://linux-hardware.org/?probe=df3068aea1) | Aug 10, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5c904a18b2](https://linux-hardware.org/?probe=5c904a18b2) | Aug 10, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [aebd9902eb](https://linux-hardware.org/?probe=aebd9902eb) | Aug 10, 2022 |
| MSI           | GP66 Leopard 11UH           | Notebook    | [a85b442a71](https://linux-hardware.org/?probe=a85b442a71) | Aug 09, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [598febc046](https://linux-hardware.org/?probe=598febc046) | Aug 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e59d15ee54](https://linux-hardware.org/?probe=e59d15ee54) | Aug 09, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [7cca0b0d07](https://linux-hardware.org/?probe=7cca0b0d07) | Aug 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [1b55fc7b56](https://linux-hardware.org/?probe=1b55fc7b56) | Aug 09, 2022 |
| ECS           | A55F-M4                     | Desktop     | [9c032723ab](https://linux-hardware.org/?probe=9c032723ab) | Aug 09, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [73e439f7f9](https://linux-hardware.org/?probe=73e439f7f9) | Aug 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [fc8542afef](https://linux-hardware.org/?probe=fc8542afef) | Aug 09, 2022 |
| Alienware     | x15 R1                      | Notebook    | [59b6412e2f](https://linux-hardware.org/?probe=59b6412e2f) | Aug 09, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [726b790d1a](https://linux-hardware.org/?probe=726b790d1a) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1636ef38d5](https://linux-hardware.org/?probe=1636ef38d5) | Aug 09, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [16b59e0aae](https://linux-hardware.org/?probe=16b59e0aae) | Aug 08, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [f833eca9da](https://linux-hardware.org/?probe=f833eca9da) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330s-15ARR 81FB     | Notebook    | [4546912e7b](https://linux-hardware.org/?probe=4546912e7b) | Aug 08, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [b075418a73](https://linux-hardware.org/?probe=b075418a73) | Aug 07, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [949598482f](https://linux-hardware.org/?probe=949598482f) | Aug 07, 2022 |
| ASRock        | H81M-HDS                    | Desktop     | [1d636956f2](https://linux-hardware.org/?probe=1d636956f2) | Aug 07, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [409cc97b53](https://linux-hardware.org/?probe=409cc97b53) | Aug 07, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [457fa11671](https://linux-hardware.org/?probe=457fa11671) | Aug 07, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3f8908c77d](https://linux-hardware.org/?probe=3f8908c77d) | Aug 07, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | Notebook    | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [3f71cac385](https://linux-hardware.org/?probe=3f71cac385) | Aug 06, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [9bc488a1b5](https://linux-hardware.org/?probe=9bc488a1b5) | Aug 06, 2022 |
| Acer          | Predator G3-571             | Notebook    | [e5e720b21b](https://linux-hardware.org/?probe=e5e720b21b) | Aug 06, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [21d06392bc](https://linux-hardware.org/?probe=21d06392bc) | Aug 06, 2022 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [3c42214ad0](https://linux-hardware.org/?probe=3c42214ad0) | Aug 06, 2022 |
| Lenovo        | ThinkPad T61 6457VE6        | Notebook    | [a6a1de13e4](https://linux-hardware.org/?probe=a6a1de13e4) | Aug 05, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [36bc9464db](https://linux-hardware.org/?probe=36bc9464db) | Aug 05, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [034cd98301](https://linux-hardware.org/?probe=034cd98301) | Aug 05, 2022 |
| Dell          | Latitude E5440              | Notebook    | [7d828eb093](https://linux-hardware.org/?probe=7d828eb093) | Aug 05, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [dd98f4e118](https://linux-hardware.org/?probe=dd98f4e118) | Aug 05, 2022 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [ab52d0fc52](https://linux-hardware.org/?probe=ab52d0fc52) | Aug 05, 2022 |
| Lenovo        | Legion R70002021 82JW       | Notebook    | [7a3c7a2886](https://linux-hardware.org/?probe=7a3c7a2886) | Aug 04, 2022 |
| Dell          | Latitude 7350               | Notebook    | [7e1a521215](https://linux-hardware.org/?probe=7e1a521215) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2f1b2efe5b](https://linux-hardware.org/?probe=2f1b2efe5b) | Aug 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [900f1d3f01](https://linux-hardware.org/?probe=900f1d3f01) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [4c75e1d374](https://linux-hardware.org/?probe=4c75e1d374) | Aug 03, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [76414b53ee](https://linux-hardware.org/?probe=76414b53ee) | Aug 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [66c117c18e](https://linux-hardware.org/?probe=66c117c18e) | Aug 03, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [62a6f6b85a](https://linux-hardware.org/?probe=62a6f6b85a) | Aug 02, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [f93096f2ff](https://linux-hardware.org/?probe=f93096f2ff) | Aug 02, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [9beb1b8221](https://linux-hardware.org/?probe=9beb1b8221) | Aug 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [563bd9cecd](https://linux-hardware.org/?probe=563bd9cecd) | Aug 02, 2022 |
| ASRock        | X370 Pro4                   | Desktop     | [674f15b7f7](https://linux-hardware.org/?probe=674f15b7f7) | Aug 02, 2022 |
| ASRock        | X370 Pro4                   | Desktop     | [3f9dca3a33](https://linux-hardware.org/?probe=3f9dca3a33) | Aug 02, 2022 |
| ASRock        | X370 Pro4                   | Desktop     | [d907eedbad](https://linux-hardware.org/?probe=d907eedbad) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | Notebook    | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [dd8b9dc221](https://linux-hardware.org/?probe=dd8b9dc221) | Aug 02, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [049630bcaa](https://linux-hardware.org/?probe=049630bcaa) | Aug 02, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [a008ad925d](https://linux-hardware.org/?probe=a008ad925d) | Aug 01, 2022 |
| Acidanther... | MacBookPro13,1              | Notebook    | [5c8158f059](https://linux-hardware.org/?probe=5c8158f059) | Aug 01, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64a21844e4](https://linux-hardware.org/?probe=64a21844e4) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [afab893436](https://linux-hardware.org/?probe=afab893436) | Aug 01, 2022 |
| HP            | Spectre                     | Convertible | [60d75d422c](https://linux-hardware.org/?probe=60d75d422c) | Aug 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [eafb78a31c](https://linux-hardware.org/?probe=eafb78a31c) | Aug 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [d77ac14ae9](https://linux-hardware.org/?probe=d77ac14ae9) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | Notebook    | [65d5b19d40](https://linux-hardware.org/?probe=65d5b19d40) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | Notebook    | [35304c2321](https://linux-hardware.org/?probe=35304c2321) | Aug 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [b2385a694b](https://linux-hardware.org/?probe=b2385a694b) | Jul 31, 2022 |
| Toshiba       | dynabook Satellite B35/R    | Notebook    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4fba223020](https://linux-hardware.org/?probe=4fba223020) | Jul 31, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0709f2eed9](https://linux-hardware.org/?probe=0709f2eed9) | Jul 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| HP            | 21B4 A01                    | Desktop     | [474779f0b9](https://linux-hardware.org/?probe=474779f0b9) | Jul 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d31203b4de](https://linux-hardware.org/?probe=d31203b4de) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [3b08b42260](https://linux-hardware.org/?probe=3b08b42260) | Jul 30, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [7589775fb4](https://linux-hardware.org/?probe=7589775fb4) | Jul 30, 2022 |
| Lenovo        | ThinkPad E480 20KN001QRT    | Notebook    | [e0e0792a71](https://linux-hardware.org/?probe=e0e0792a71) | Jul 30, 2022 |
| Clevo         | W150HNM/W170HN              | Notebook    | [31c83153b5](https://linux-hardware.org/?probe=31c83153b5) | Jul 29, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [a6113f2e35](https://linux-hardware.org/?probe=a6113f2e35) | Jul 29, 2022 |
| Toshiba       | Satellite L70-B             | Notebook    | [bee2cdca79](https://linux-hardware.org/?probe=bee2cdca79) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ef7aa9cb2e](https://linux-hardware.org/?probe=ef7aa9cb2e) | Jul 29, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [be7cc4f033](https://linux-hardware.org/?probe=be7cc4f033) | Jul 29, 2022 |
| Dell          | Latitude 5480               | Notebook    | [2e2d540cb0](https://linux-hardware.org/?probe=2e2d540cb0) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8345e7dd74](https://linux-hardware.org/?probe=8345e7dd74) | Jul 29, 2022 |
| Framework     | Laptop                      | Notebook    | [626e3266c7](https://linux-hardware.org/?probe=626e3266c7) | Jul 29, 2022 |
| HP            | ZBook 15v G5                | Notebook    | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bc1a82a647](https://linux-hardware.org/?probe=bc1a82a647) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| Timi          | TM1703                      | Notebook    | [b3c578658f](https://linux-hardware.org/?probe=b3c578658f) | Jul 28, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [8d87e3bb3b](https://linux-hardware.org/?probe=8d87e3bb3b) | Jul 28, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [3c665fb25f](https://linux-hardware.org/?probe=3c665fb25f) | Jul 28, 2022 |
| Lenovo        | ThinkPad X230 2325TXV       | Notebook    | [2c5c6ba837](https://linux-hardware.org/?probe=2c5c6ba837) | Jul 28, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c3f34f2c91](https://linux-hardware.org/?probe=c3f34f2c91) | Jul 28, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b547e23eb1](https://linux-hardware.org/?probe=b547e23eb1) | Jul 28, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [1d04421fd5](https://linux-hardware.org/?probe=1d04421fd5) | Jul 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7d9d58c2da](https://linux-hardware.org/?probe=7d9d58c2da) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [ae478a8f82](https://linux-hardware.org/?probe=ae478a8f82) | Jul 27, 2022 |
| Samsung       | 935XDB                      | Notebook    | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [75c2236b06](https://linux-hardware.org/?probe=75c2236b06) | Jul 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [6577d30f3e](https://linux-hardware.org/?probe=6577d30f3e) | Jul 26, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [8ff77bee59](https://linux-hardware.org/?probe=8ff77bee59) | Jul 26, 2022 |
| Alienware     | m15 R4                      | Notebook    | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [70ddacf43f](https://linux-hardware.org/?probe=70ddacf43f) | Jul 25, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [960fefaee7](https://linux-hardware.org/?probe=960fefaee7) | Jul 25, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [b63e85ff7e](https://linux-hardware.org/?probe=b63e85ff7e) | Jul 25, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [c7c46e080e](https://linux-hardware.org/?probe=c7c46e080e) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | Notebook    | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [669bb060e5](https://linux-hardware.org/?probe=669bb060e5) | Jul 25, 2022 |
| Samsung       | 950QDB                      | Convertible | [b606f34f7e](https://linux-hardware.org/?probe=b606f34f7e) | Jul 24, 2022 |
| Dell          | Vostro 3491                 | Notebook    | [6ce65dccb7](https://linux-hardware.org/?probe=6ce65dccb7) | Jul 24, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [0dc55c5b73](https://linux-hardware.org/?probe=0dc55c5b73) | Jul 24, 2022 |
| Samsung       | 950QDB                      | Convertible | [a823d9679a](https://linux-hardware.org/?probe=a823d9679a) | Jul 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ce2ecc0fd8](https://linux-hardware.org/?probe=ce2ecc0fd8) | Jul 24, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a1aa08113d](https://linux-hardware.org/?probe=a1aa08113d) | Jul 24, 2022 |
| Timi          | RedmiBook 14 II             | Notebook    | [cd8d5a1ee6](https://linux-hardware.org/?probe=cd8d5a1ee6) | Jul 24, 2022 |
| Lenovo        | ThinkPad X280 20KES2SN00    | Notebook    | [202423ba73](https://linux-hardware.org/?probe=202423ba73) | Jul 24, 2022 |
| Google        | Wolf                        | Notebook    | [f2397aadef](https://linux-hardware.org/?probe=f2397aadef) | Jul 23, 2022 |
| Google        | Wolf                        | Notebook    | [ffa74c4dc0](https://linux-hardware.org/?probe=ffa74c4dc0) | Jul 23, 2022 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [e8da564bb8](https://linux-hardware.org/?probe=e8da564bb8) | Jul 23, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [492b4e1236](https://linux-hardware.org/?probe=492b4e1236) | Jul 23, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [51d002e1b7](https://linux-hardware.org/?probe=51d002e1b7) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [41d0e95039](https://linux-hardware.org/?probe=41d0e95039) | Jul 23, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [bfbbb40d56](https://linux-hardware.org/?probe=bfbbb40d56) | Jul 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [0b6a41a9b8](https://linux-hardware.org/?probe=0b6a41a9b8) | Jul 22, 2022 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [3428364c49](https://linux-hardware.org/?probe=3428364c49) | Jul 22, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [540a660447](https://linux-hardware.org/?probe=540a660447) | Jul 22, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [7a5b89e10c](https://linux-hardware.org/?probe=7a5b89e10c) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [b8ce5a0377](https://linux-hardware.org/?probe=b8ce5a0377) | Jul 22, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [afb076562c](https://linux-hardware.org/?probe=afb076562c) | Jul 21, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| HP            | 8704                        | Desktop     | [eaa4bc0059](https://linux-hardware.org/?probe=eaa4bc0059) | Jul 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [8505a7d575](https://linux-hardware.org/?probe=8505a7d575) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [7ff3bd3639](https://linux-hardware.org/?probe=7ff3bd3639) | Jul 20, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [d101f95ac2](https://linux-hardware.org/?probe=d101f95ac2) | Jul 20, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Convertible | [6dfbd97685](https://linux-hardware.org/?probe=6dfbd97685) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [9558ff01e9](https://linux-hardware.org/?probe=9558ff01e9) | Jul 20, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8a0136fd65](https://linux-hardware.org/?probe=8a0136fd65) | Jul 20, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [52ca04ad6b](https://linux-hardware.org/?probe=52ca04ad6b) | Jul 20, 2022 |
| Lenovo        | V570 HuronRiver Platform    | Notebook    | [7e317412e0](https://linux-hardware.org/?probe=7e317412e0) | Jul 20, 2022 |
| Machinist/... | X99Z GAMING Beta            | Desktop     | [4f26d9126f](https://linux-hardware.org/?probe=4f26d9126f) | Jul 20, 2022 |
| HP            | ProBook 640 G5              | Notebook    | [36a725c595](https://linux-hardware.org/?probe=36a725c595) | Jul 19, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [795808bf39](https://linux-hardware.org/?probe=795808bf39) | Jul 19, 2022 |
| MSI           | A320M BAZOOKA               | Desktop     | [d1a4b7b468](https://linux-hardware.org/?probe=d1a4b7b468) | Jul 19, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [8d6d581aac](https://linux-hardware.org/?probe=8d6d581aac) | Jul 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [68023f05e9](https://linux-hardware.org/?probe=68023f05e9) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | Notebook    | [cafc6119f3](https://linux-hardware.org/?probe=cafc6119f3) | Jul 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f37266608c](https://linux-hardware.org/?probe=f37266608c) | Jul 18, 2022 |
| MSI           | GS75 Stealth 9SF            | Notebook    | [24e8aca8d1](https://linux-hardware.org/?probe=24e8aca8d1) | Jul 17, 2022 |
| System76      | Lemur Pro                   | Notebook    | [a4adde6cf9](https://linux-hardware.org/?probe=a4adde6cf9) | Jul 17, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [dc94f6ef14](https://linux-hardware.org/?probe=dc94f6ef14) | Jul 17, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e1313016ee](https://linux-hardware.org/?probe=e1313016ee) | Jul 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [05c33c9ff5](https://linux-hardware.org/?probe=05c33c9ff5) | Jul 17, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [321c1a6e7a](https://linux-hardware.org/?probe=321c1a6e7a) | Jul 17, 2022 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [5096e0dfea](https://linux-hardware.org/?probe=5096e0dfea) | Jul 17, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [ebcca43b7f](https://linux-hardware.org/?probe=ebcca43b7f) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [e94cde9ec6](https://linux-hardware.org/?probe=e94cde9ec6) | Jul 17, 2022 |
| Dell          | Latitude E6540              | Notebook    | [595eeced49](https://linux-hardware.org/?probe=595eeced49) | Jul 16, 2022 |
| Dell          | Latitude E6540              | Notebook    | [804dad339b](https://linux-hardware.org/?probe=804dad339b) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6e936c29d](https://linux-hardware.org/?probe=a6e936c29d) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d465259da1](https://linux-hardware.org/?probe=d465259da1) | Jul 16, 2022 |
| HP            | ProBook 640 G5              | Notebook    | [93e838afb1](https://linux-hardware.org/?probe=93e838afb1) | Jul 16, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [1dc42453a1](https://linux-hardware.org/?probe=1dc42453a1) | Jul 15, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [164d1ff988](https://linux-hardware.org/?probe=164d1ff988) | Jul 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e4530dd7b4](https://linux-hardware.org/?probe=e4530dd7b4) | Jul 15, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [6ff44b9490](https://linux-hardware.org/?probe=6ff44b9490) | Jul 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [c475c84f19](https://linux-hardware.org/?probe=c475c84f19) | Jul 15, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [c21885de7f](https://linux-hardware.org/?probe=c21885de7f) | Jul 15, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [b5f57e7b95](https://linux-hardware.org/?probe=b5f57e7b95) | Jul 14, 2022 |
| Hyperbook     | Z15 Zen                     | Notebook    | [41129ecc5e](https://linux-hardware.org/?probe=41129ecc5e) | Jul 14, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [831f0fd0f1](https://linux-hardware.org/?probe=831f0fd0f1) | Jul 14, 2022 |
| Dell          | Inspiron 7570               | Notebook    | [872ca81b40](https://linux-hardware.org/?probe=872ca81b40) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [896226e566](https://linux-hardware.org/?probe=896226e566) | Jul 13, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | Notebook    | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| MSI           | H77MA-G43                   | Desktop     | [4cb547564b](https://linux-hardware.org/?probe=4cb547564b) | Jul 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ac37352e9b](https://linux-hardware.org/?probe=ac37352e9b) | Jul 13, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [6021e75347](https://linux-hardware.org/?probe=6021e75347) | Jul 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [eb05f4aed9](https://linux-hardware.org/?probe=eb05f4aed9) | Jul 13, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [5170dca44d](https://linux-hardware.org/?probe=5170dca44d) | Jul 13, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [4816483377](https://linux-hardware.org/?probe=4816483377) | Jul 13, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [05d81c0d1e](https://linux-hardware.org/?probe=05d81c0d1e) | Jul 13, 2022 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [ac5f241f98](https://linux-hardware.org/?probe=ac5f241f98) | Jul 13, 2022 |
| Toshiba       | Satellite M645              | Notebook    | [0149367a4e](https://linux-hardware.org/?probe=0149367a4e) | Jul 12, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e96661c5ec](https://linux-hardware.org/?probe=e96661c5ec) | Jul 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [eac5600627](https://linux-hardware.org/?probe=eac5600627) | Jul 12, 2022 |
| MSI           | X99S GAMING 9 AC            | Desktop     | [5f682aadd5](https://linux-hardware.org/?probe=5f682aadd5) | Jul 12, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [d9122a14c0](https://linux-hardware.org/?probe=d9122a14c0) | Jul 12, 2022 |
| Unknown       | 1.0                         | Desktop     | [24e4b4e948](https://linux-hardware.org/?probe=24e4b4e948) | Jul 12, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [a4bc7e790c](https://linux-hardware.org/?probe=a4bc7e790c) | Jul 11, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [6a065093ba](https://linux-hardware.org/?probe=6a065093ba) | Jul 10, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [1478a70c4b](https://linux-hardware.org/?probe=1478a70c4b) | Jul 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [57227ff9c1](https://linux-hardware.org/?probe=57227ff9c1) | Jul 10, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [144a2f33ee](https://linux-hardware.org/?probe=144a2f33ee) | Jul 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [de4d640168](https://linux-hardware.org/?probe=de4d640168) | Jul 10, 2022 |
| Lenovo        | 1030 SDK0E50510 WIN 2625... | Desktop     | [bc7d8ae7c7](https://linux-hardware.org/?probe=bc7d8ae7c7) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| HP            | 85BA 00100                  | All in one  | [3acda0ef6a](https://linux-hardware.org/?probe=3acda0ef6a) | Jul 08, 2022 |
| ASUSTek       | U36SG                       | Notebook    | [878e0283d9](https://linux-hardware.org/?probe=878e0283d9) | Jul 08, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [32d1c38bf4](https://linux-hardware.org/?probe=32d1c38bf4) | Jul 08, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d6664c4c1b](https://linux-hardware.org/?probe=d6664c4c1b) | Jul 08, 2022 |
| ASUSTek       | GL702VSK                    | Notebook    | [4fe32d25e5](https://linux-hardware.org/?probe=4fe32d25e5) | Jul 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8b1d9534ff](https://linux-hardware.org/?probe=8b1d9534ff) | Jul 07, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [62fb099dfd](https://linux-hardware.org/?probe=62fb099dfd) | Jul 07, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [bb0bb0b58f](https://linux-hardware.org/?probe=bb0bb0b58f) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [f7ecc76d69](https://linux-hardware.org/?probe=f7ecc76d69) | Jul 07, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [e04f1fc85c](https://linux-hardware.org/?probe=e04f1fc85c) | Jul 07, 2022 |
| Dell          | 0YC03K A03                  | Desktop     | [ecb4303984](https://linux-hardware.org/?probe=ecb4303984) | Jul 07, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [36546bd458](https://linux-hardware.org/?probe=36546bd458) | Jul 06, 2022 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [b523713f83](https://linux-hardware.org/?probe=b523713f83) | Jul 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [b80097333e](https://linux-hardware.org/?probe=b80097333e) | Jul 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [8e7d7a945f](https://linux-hardware.org/?probe=8e7d7a945f) | Jul 06, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [92b59598e5](https://linux-hardware.org/?probe=92b59598e5) | Jul 06, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [cfe354b7b2](https://linux-hardware.org/?probe=cfe354b7b2) | Jul 06, 2022 |
| MSI           | GP66 Leopard 10UH           | Notebook    | [dcbe6f403d](https://linux-hardware.org/?probe=dcbe6f403d) | Jul 06, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [a03e04d76a](https://linux-hardware.org/?probe=a03e04d76a) | Jul 05, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9ad51a3a2c](https://linux-hardware.org/?probe=9ad51a3a2c) | Jul 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [341858c479](https://linux-hardware.org/?probe=341858c479) | Jul 05, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [de014d917d](https://linux-hardware.org/?probe=de014d917d) | Jul 05, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [bc37067029](https://linux-hardware.org/?probe=bc37067029) | Jul 05, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [83af97ccc6](https://linux-hardware.org/?probe=83af97ccc6) | Jul 04, 2022 |
| Acer          | Aspire E5-522               | Notebook    | [9693c1d4ff](https://linux-hardware.org/?probe=9693c1d4ff) | Jul 04, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS            | Desktop     | [df4856796e](https://linux-hardware.org/?probe=df4856796e) | Jul 04, 2022 |
| Medion        | B250H4-EM                   | Desktop     | [2c42d7ef06](https://linux-hardware.org/?probe=2c42d7ef06) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [4829f98af6](https://linux-hardware.org/?probe=4829f98af6) | Jul 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e2ff106ce0](https://linux-hardware.org/?probe=e2ff106ce0) | Jul 03, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [fed0993c92](https://linux-hardware.org/?probe=fed0993c92) | Jul 03, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [ce9585eac5](https://linux-hardware.org/?probe=ce9585eac5) | Jul 03, 2022 |
| MSI           | B365M PRO-VDH               | Desktop     | [8ce7059868](https://linux-hardware.org/?probe=8ce7059868) | Jul 03, 2022 |
| Dell          | Latitude 5285               | Tablet      | [cf54a0fd6c](https://linux-hardware.org/?probe=cf54a0fd6c) | Jul 03, 2022 |
| Intel         | HuronRiver Platform         | Notebook    | [c0d79569d8](https://linux-hardware.org/?probe=c0d79569d8) | Jul 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ffde44eef6](https://linux-hardware.org/?probe=ffde44eef6) | Jul 02, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [70e0a9a17c](https://linux-hardware.org/?probe=70e0a9a17c) | Jul 02, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [5393a13046](https://linux-hardware.org/?probe=5393a13046) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [eedac976d8](https://linux-hardware.org/?probe=eedac976d8) | Jul 02, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [aad648ac8d](https://linux-hardware.org/?probe=aad648ac8d) | Jul 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [5950f35d56](https://linux-hardware.org/?probe=5950f35d56) | Jul 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [301d0caf4d](https://linux-hardware.org/?probe=301d0caf4d) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [5f076638f4](https://linux-hardware.org/?probe=5f076638f4) | Jul 01, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9f4f6d2323](https://linux-hardware.org/?probe=9f4f6d2323) | Jul 01, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [7e809da3ad](https://linux-hardware.org/?probe=7e809da3ad) | Jul 01, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | Notebook    | [27cd378ed6](https://linux-hardware.org/?probe=27cd378ed6) | Jul 01, 2022 |
| HP            | Pavilion g4                 | Notebook    | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [03dd055ce5](https://linux-hardware.org/?probe=03dd055ce5) | Jun 30, 2022 |
| Dell          | XPS M1330                   | Notebook    | [b891e49fac](https://linux-hardware.org/?probe=b891e49fac) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [7287dd0ad5](https://linux-hardware.org/?probe=7287dd0ad5) | Jun 30, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3c478faa0c](https://linux-hardware.org/?probe=3c478faa0c) | Jun 30, 2022 |
| Gigabyte      | AX370-Gaming 5              | Desktop     | [bd54eb7f9c](https://linux-hardware.org/?probe=bd54eb7f9c) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [96b07cbbd5](https://linux-hardware.org/?probe=96b07cbbd5) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [2ae62ac227](https://linux-hardware.org/?probe=2ae62ac227) | Jun 30, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [0a047126ba](https://linux-hardware.org/?probe=0a047126ba) | Jun 30, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e7f3ea5cf5](https://linux-hardware.org/?probe=e7f3ea5cf5) | Jun 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e594fe8eb6](https://linux-hardware.org/?probe=e594fe8eb6) | Jun 29, 2022 |
| Gigabyte      | X570S AORUS ELITE AX        | Desktop     | [ec8f2e717c](https://linux-hardware.org/?probe=ec8f2e717c) | Jun 29, 2022 |
| Infinix       | INBOOK X2                   | Notebook    | [1c87102f96](https://linux-hardware.org/?probe=1c87102f96) | Jun 29, 2022 |
| Lenovo        | ThinkPad P50 20EQS5M100     | Notebook    | [d0b6aa0a1a](https://linux-hardware.org/?probe=d0b6aa0a1a) | Jun 29, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [6dfee96211](https://linux-hardware.org/?probe=6dfee96211) | Jun 29, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [6a2b56796c](https://linux-hardware.org/?probe=6a2b56796c) | Jun 28, 2022 |
| Acer          | Aspire M5-582PT             | Notebook    | [e159de9f3e](https://linux-hardware.org/?probe=e159de9f3e) | Jun 28, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [79a978476b](https://linux-hardware.org/?probe=79a978476b) | Jun 28, 2022 |
| Dell          | Latitude 7350               | Notebook    | [427cc37d76](https://linux-hardware.org/?probe=427cc37d76) | Jun 28, 2022 |
| Dell          | Latitude 7350               | Notebook    | [65d1c5c6f5](https://linux-hardware.org/?probe=65d1c5c6f5) | Jun 28, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [20054c6da2](https://linux-hardware.org/?probe=20054c6da2) | Jun 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS6XC00    | Notebook    | [a4b9098138](https://linux-hardware.org/?probe=a4b9098138) | Jun 26, 2022 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [088e3e2f28](https://linux-hardware.org/?probe=088e3e2f28) | Jun 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0beecf61e4](https://linux-hardware.org/?probe=0beecf61e4) | Jun 26, 2022 |
| MSI           | B250 GAMING M3              | Desktop     | [f79c31ad28](https://linux-hardware.org/?probe=f79c31ad28) | Jun 26, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [70a0ba730c](https://linux-hardware.org/?probe=70a0ba730c) | Jun 26, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [72286bac00](https://linux-hardware.org/?probe=72286bac00) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [68e2e0bbdb](https://linux-hardware.org/?probe=68e2e0bbdb) | Jun 25, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [a84e0d9197](https://linux-hardware.org/?probe=a84e0d9197) | Jun 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| Dell          | Latitude 5420               | Notebook    | [2149a24612](https://linux-hardware.org/?probe=2149a24612) | Jun 25, 2022 |
| Dell          | Latitude 5490               | Notebook    | [4c3d48724c](https://linux-hardware.org/?probe=4c3d48724c) | Jun 25, 2022 |
| Dell          | Latitude 5490               | Notebook    | [3bb8a81dbf](https://linux-hardware.org/?probe=3bb8a81dbf) | Jun 25, 2022 |
| ASUSTek       | G551JM                      | Notebook    | [2d8e7ffcb2](https://linux-hardware.org/?probe=2d8e7ffcb2) | Jun 24, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e575e05b18](https://linux-hardware.org/?probe=e575e05b18) | Jun 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a2f3ee6e42](https://linux-hardware.org/?probe=a2f3ee6e42) | Jun 24, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | Notebook    | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [a10adc5a33](https://linux-hardware.org/?probe=a10adc5a33) | Jun 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [08e5f734f9](https://linux-hardware.org/?probe=08e5f734f9) | Jun 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [95d5fd3cd1](https://linux-hardware.org/?probe=95d5fd3cd1) | Jun 24, 2022 |
| ASRock        | X370 Taichi                 | Desktop     | [788acf13f2](https://linux-hardware.org/?probe=788acf13f2) | Jun 24, 2022 |
| Acer          | Nitro AN715-51              | Notebook    | [a8df58056b](https://linux-hardware.org/?probe=a8df58056b) | Jun 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS6XC00    | Notebook    | [55e631d9b6](https://linux-hardware.org/?probe=55e631d9b6) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | Notebook    | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a1a0b3b43b](https://linux-hardware.org/?probe=a1a0b3b43b) | Jun 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [2d50f4b4d8](https://linux-hardware.org/?probe=2d50f4b4d8) | Jun 23, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [c4b2a02630](https://linux-hardware.org/?probe=c4b2a02630) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f2b61e1e02](https://linux-hardware.org/?probe=f2b61e1e02) | Jun 23, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [906b1f465e](https://linux-hardware.org/?probe=906b1f465e) | Jun 23, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [165a04e05f](https://linux-hardware.org/?probe=165a04e05f) | Jun 23, 2022 |
| Razer         | Blade                       | Notebook    | [6c8b201cd9](https://linux-hardware.org/?probe=6c8b201cd9) | Jun 23, 2022 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [257f40005f](https://linux-hardware.org/?probe=257f40005f) | Jun 23, 2022 |
| ASRock        | X370 Pro4                   | Desktop     | [df6751dcaa](https://linux-hardware.org/?probe=df6751dcaa) | Jun 22, 2022 |
| Apple         | Mac-F2208EC8                | Mini pc     | [2ca2a822ed](https://linux-hardware.org/?probe=2ca2a822ed) | Jun 22, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [c8b0e5e0ca](https://linux-hardware.org/?probe=c8b0e5e0ca) | Jun 22, 2022 |
| Acer          | H110H4-M14 P21-A2E          | Desktop     | [f3c553d3f0](https://linux-hardware.org/?probe=f3c553d3f0) | Jun 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [51ec938467](https://linux-hardware.org/?probe=51ec938467) | Jun 22, 2022 |
| Acer          | H110H4-M14 P21-A2E          | Desktop     | [17e46ecec3](https://linux-hardware.org/?probe=17e46ecec3) | Jun 22, 2022 |
| HP            | 2B4B                        | Desktop     | [fe2eceeeda](https://linux-hardware.org/?probe=fe2eceeeda) | Jun 22, 2022 |
| LG Electro... | 15Z95N-G.AAC6U1             | Notebook    | [c5b4596c19](https://linux-hardware.org/?probe=c5b4596c19) | Jun 22, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [5fc2a02e85](https://linux-hardware.org/?probe=5fc2a02e85) | Jun 22, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [84a4eb23c6](https://linux-hardware.org/?probe=84a4eb23c6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | Notebook    | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a8d78740e8](https://linux-hardware.org/?probe=a8d78740e8) | Jun 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [4539c26ede](https://linux-hardware.org/?probe=4539c26ede) | Jun 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [cf80e45435](https://linux-hardware.org/?probe=cf80e45435) | Jun 21, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [35f551b127](https://linux-hardware.org/?probe=35f551b127) | Jun 21, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [2530e2e400](https://linux-hardware.org/?probe=2530e2e400) | Jun 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [9a9dd8fa0c](https://linux-hardware.org/?probe=9a9dd8fa0c) | Jun 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [ff5ed1835c](https://linux-hardware.org/?probe=ff5ed1835c) | Jun 20, 2022 |
| Philco        | OEM                         | Notebook    | [bee7961704](https://linux-hardware.org/?probe=bee7961704) | Jun 20, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [9eb7129a46](https://linux-hardware.org/?probe=9eb7129a46) | Jun 20, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [1052591535](https://linux-hardware.org/?probe=1052591535) | Jun 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [8e8fcfc4bf](https://linux-hardware.org/?probe=8e8fcfc4bf) | Jun 20, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [4e9034764b](https://linux-hardware.org/?probe=4e9034764b) | Jun 20, 2022 |
| HP            | ENVY dv7                    | Notebook    | [22dec86487](https://linux-hardware.org/?probe=22dec86487) | Jun 20, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [ddd610d863](https://linux-hardware.org/?probe=ddd610d863) | Jun 20, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4879f19d4a](https://linux-hardware.org/?probe=4879f19d4a) | Jun 20, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [999d6e4735](https://linux-hardware.org/?probe=999d6e4735) | Jun 20, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b841edf2b7](https://linux-hardware.org/?probe=b841edf2b7) | Jun 19, 2022 |
| Framework     | Laptop                      | Notebook    | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [42b74b0907](https://linux-hardware.org/?probe=42b74b0907) | Jun 19, 2022 |
| Toshiba       | Satellite Click 10 LX5W-... | Notebook    | [b8f87c8ede](https://linux-hardware.org/?probe=b8f87c8ede) | Jun 19, 2022 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [8cff182bbf](https://linux-hardware.org/?probe=8cff182bbf) | Jun 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [67faa5fcd3](https://linux-hardware.org/?probe=67faa5fcd3) | Jun 19, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [90012988e8](https://linux-hardware.org/?probe=90012988e8) | Jun 19, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [b93d65dd64](https://linux-hardware.org/?probe=b93d65dd64) | Jun 18, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [fcbbdaf844](https://linux-hardware.org/?probe=fcbbdaf844) | Jun 18, 2022 |
| Lenovo        | MIIX 3-830 80JB             | Tablet      | [621742ba14](https://linux-hardware.org/?probe=621742ba14) | Jun 18, 2022 |
| HUAWEI        | KPR-WX9                     | Notebook    | [4c08060155](https://linux-hardware.org/?probe=4c08060155) | Jun 18, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [e19c095325](https://linux-hardware.org/?probe=e19c095325) | Jun 18, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [c59a0a5413](https://linux-hardware.org/?probe=c59a0a5413) | Jun 18, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [31cdb7f2fc](https://linux-hardware.org/?probe=31cdb7f2fc) | Jun 17, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [9ed8b5c759](https://linux-hardware.org/?probe=9ed8b5c759) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | Notebook    | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Dell          | Latitude E5450              | Notebook    | [42f5a53e24](https://linux-hardware.org/?probe=42f5a53e24) | Jun 16, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7eee6145a1](https://linux-hardware.org/?probe=7eee6145a1) | Jun 16, 2022 |
| ASUSTek       | X411UA                      | Notebook    | [da7deca26c](https://linux-hardware.org/?probe=da7deca26c) | Jun 16, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [20105d0e64](https://linux-hardware.org/?probe=20105d0e64) | Jun 16, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [c414ab98c5](https://linux-hardware.org/?probe=c414ab98c5) | Jun 16, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [ffcca1ccac](https://linux-hardware.org/?probe=ffcca1ccac) | Jun 16, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [738709ae5d](https://linux-hardware.org/?probe=738709ae5d) | Jun 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | Notebook    | [27d9d9e55e](https://linux-hardware.org/?probe=27d9d9e55e) | Jun 16, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | Notebook    | [51042aca4a](https://linux-hardware.org/?probe=51042aca4a) | Jun 15, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [5afd9dcda0](https://linux-hardware.org/?probe=5afd9dcda0) | Jun 15, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [b6cdb73504](https://linux-hardware.org/?probe=b6cdb73504) | Jun 15, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [4b2037715f](https://linux-hardware.org/?probe=4b2037715f) | Jun 15, 2022 |
| Lenovo        | ThinkPad E490 20N8002APB    | Notebook    | [3a17ac0192](https://linux-hardware.org/?probe=3a17ac0192) | Jun 15, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [670d05fbe3](https://linux-hardware.org/?probe=670d05fbe3) | Jun 15, 2022 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [971f310609](https://linux-hardware.org/?probe=971f310609) | Jun 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [c856f6d54f](https://linux-hardware.org/?probe=c856f6d54f) | Jun 14, 2022 |
| Timi          | TM1701                      | Notebook    | [e57d1ac956](https://linux-hardware.org/?probe=e57d1ac956) | Jun 14, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | Notebook    | [ee0b4c4389](https://linux-hardware.org/?probe=ee0b4c4389) | Jun 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [c87c87881e](https://linux-hardware.org/?probe=c87c87881e) | Jun 14, 2022 |
| Google        | Quawks                      | Notebook    | [c513bb8294](https://linux-hardware.org/?probe=c513bb8294) | Jun 14, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [44eccb41e1](https://linux-hardware.org/?probe=44eccb41e1) | Jun 14, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [002c21e90f](https://linux-hardware.org/?probe=002c21e90f) | Jun 14, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dfa7cc38e7](https://linux-hardware.org/?probe=dfa7cc38e7) | Jun 14, 2022 |
| ASUSTek       | U36SG                       | Notebook    | [d5c67322d4](https://linux-hardware.org/?probe=d5c67322d4) | Jun 14, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [0f745d7bc7](https://linux-hardware.org/?probe=0f745d7bc7) | Jun 13, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [cdc0b49b72](https://linux-hardware.org/?probe=cdc0b49b72) | Jun 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e33ea31f97](https://linux-hardware.org/?probe=e33ea31f97) | Jun 13, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [5f5c3fcba9](https://linux-hardware.org/?probe=5f5c3fcba9) | Jun 13, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [d827dcbe06](https://linux-hardware.org/?probe=d827dcbe06) | Jun 13, 2022 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [859d1ddbb0](https://linux-hardware.org/?probe=859d1ddbb0) | Jun 13, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [049e305b33](https://linux-hardware.org/?probe=049e305b33) | Jun 13, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [f3cb75acef](https://linux-hardware.org/?probe=f3cb75acef) | Jun 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0d74445d24](https://linux-hardware.org/?probe=0d74445d24) | Jun 13, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [7cc9d90361](https://linux-hardware.org/?probe=7cc9d90361) | Jun 12, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ac1f1fe24f](https://linux-hardware.org/?probe=ac1f1fe24f) | Jun 12, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [db209b6bf1](https://linux-hardware.org/?probe=db209b6bf1) | Jun 12, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [9a5b9400a1](https://linux-hardware.org/?probe=9a5b9400a1) | Jun 12, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d8ae63f677](https://linux-hardware.org/?probe=d8ae63f677) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [52efea465c](https://linux-hardware.org/?probe=52efea465c) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [731e6f4aa8](https://linux-hardware.org/?probe=731e6f4aa8) | Jun 12, 2022 |
| Dell          | Precision 7520              | Notebook    | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [564e15d66b](https://linux-hardware.org/?probe=564e15d66b) | Jun 11, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e414ea3e15](https://linux-hardware.org/?probe=e414ea3e15) | Jun 11, 2022 |
| Alienware     | m15 R4                      | Notebook    | [5299db8f70](https://linux-hardware.org/?probe=5299db8f70) | Jun 11, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c1bde29740](https://linux-hardware.org/?probe=c1bde29740) | Jun 11, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [d5d6eeb639](https://linux-hardware.org/?probe=d5d6eeb639) | Jun 11, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [c8f8c1a8e3](https://linux-hardware.org/?probe=c8f8c1a8e3) | Jun 10, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [148d14437b](https://linux-hardware.org/?probe=148d14437b) | Jun 10, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [693e499a6d](https://linux-hardware.org/?probe=693e499a6d) | Jun 10, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [91580d9a20](https://linux-hardware.org/?probe=91580d9a20) | Jun 10, 2022 |
| Fujitsu       | LIFEBOOK E556               | Notebook    | [1dd2b6a645](https://linux-hardware.org/?probe=1dd2b6a645) | Jun 10, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [31275cdf72](https://linux-hardware.org/?probe=31275cdf72) | Jun 10, 2022 |
| Acer          | WG43M                       | Desktop     | [bdd6d72374](https://linux-hardware.org/?probe=bdd6d72374) | Jun 10, 2022 |
| Lenovo        | ThinkPad X230 2325TXV       | Notebook    | [67f152d520](https://linux-hardware.org/?probe=67f152d520) | Jun 10, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [9198e2d64c](https://linux-hardware.org/?probe=9198e2d64c) | Jun 10, 2022 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [9e574bef7c](https://linux-hardware.org/?probe=9e574bef7c) | Jun 10, 2022 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [e33e73a70f](https://linux-hardware.org/?probe=e33e73a70f) | Jun 10, 2022 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [958f8bb25b](https://linux-hardware.org/?probe=958f8bb25b) | Jun 09, 2022 |
| Lenovo        | Unknown                     | Notebook    | [2921bcaa1c](https://linux-hardware.org/?probe=2921bcaa1c) | Jun 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [dcfb1c33aa](https://linux-hardware.org/?probe=dcfb1c33aa) | Jun 09, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bfe8486e59](https://linux-hardware.org/?probe=bfe8486e59) | Jun 09, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [44aa7de1c8](https://linux-hardware.org/?probe=44aa7de1c8) | Jun 08, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a144e0b75e](https://linux-hardware.org/?probe=a144e0b75e) | Jun 08, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [630d0bc381](https://linux-hardware.org/?probe=630d0bc381) | Jun 08, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f2b810d97f](https://linux-hardware.org/?probe=f2b810d97f) | Jun 08, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d984f403e9](https://linux-hardware.org/?probe=d984f403e9) | Jun 08, 2022 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [73e68df88c](https://linux-hardware.org/?probe=73e68df88c) | Jun 08, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [737a4183c8](https://linux-hardware.org/?probe=737a4183c8) | Jun 07, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [59f197c68d](https://linux-hardware.org/?probe=59f197c68d) | Jun 07, 2022 |
| Acer          | WG43M                       | Desktop     | [70d3c85c47](https://linux-hardware.org/?probe=70d3c85c47) | Jun 07, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [5a7be822e3](https://linux-hardware.org/?probe=5a7be822e3) | Jun 07, 2022 |
| Dell          | Precision 5550              | Notebook    | [a4bf41771c](https://linux-hardware.org/?probe=a4bf41771c) | Jun 07, 2022 |
| ASRock        | Z97M Anniversary            | Desktop     | [1855124dd3](https://linux-hardware.org/?probe=1855124dd3) | Jun 07, 2022 |
| Samsung       | 740U5M                      | Convertible | [df817ce700](https://linux-hardware.org/?probe=df817ce700) | Jun 07, 2022 |
| Lenovo        | ThinkPad T495 20NJ0007US    | Notebook    | [2b3ee11cad](https://linux-hardware.org/?probe=2b3ee11cad) | Jun 07, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [e445d85039](https://linux-hardware.org/?probe=e445d85039) | Jun 06, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [73ba6fe3c0](https://linux-hardware.org/?probe=73ba6fe3c0) | Jun 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [aab255864c](https://linux-hardware.org/?probe=aab255864c) | Jun 06, 2022 |
| Huanan        | X79-ZD3                     | Desktop     | [e1a7cd65ab](https://linux-hardware.org/?probe=e1a7cd65ab) | Jun 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [0546f2fdfd](https://linux-hardware.org/?probe=0546f2fdfd) | Jun 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [228fe8f3f1](https://linux-hardware.org/?probe=228fe8f3f1) | Jun 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [5d9a12a88d](https://linux-hardware.org/?probe=5d9a12a88d) | Jun 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [9a2ab90fd4](https://linux-hardware.org/?probe=9a2ab90fd4) | Jun 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [6d46a6107c](https://linux-hardware.org/?probe=6d46a6107c) | Jun 06, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f4dcc8e7a1](https://linux-hardware.org/?probe=f4dcc8e7a1) | Jun 06, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d944531fed](https://linux-hardware.org/?probe=d944531fed) | Jun 06, 2022 |
| Dell          | 0YXT71 A02                  | Desktop     | [4dd5ceef26](https://linux-hardware.org/?probe=4dd5ceef26) | Jun 05, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [4746fe546b](https://linux-hardware.org/?probe=4746fe546b) | Jun 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| Dell          | G3 3500                     | Notebook    | [6734206fa0](https://linux-hardware.org/?probe=6734206fa0) | Jun 05, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [72dd09a86a](https://linux-hardware.org/?probe=72dd09a86a) | Jun 05, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [6c408a6fd7](https://linux-hardware.org/?probe=6c408a6fd7) | Jun 05, 2022 |
| Fujitsu       | LIFEBOOK U937               | Notebook    | [44d3d1edad](https://linux-hardware.org/?probe=44d3d1edad) | Jun 04, 2022 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [9207d2f2d8](https://linux-hardware.org/?probe=9207d2f2d8) | Jun 04, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [95af0fa349](https://linux-hardware.org/?probe=95af0fa349) | Jun 04, 2022 |
| TUXEDO        | Book_XA1510                 | Notebook    | [6738253853](https://linux-hardware.org/?probe=6738253853) | Jun 04, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [66cc7342ec](https://linux-hardware.org/?probe=66cc7342ec) | Jun 04, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [883f386564](https://linux-hardware.org/?probe=883f386564) | Jun 03, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [ecd590c347](https://linux-hardware.org/?probe=ecd590c347) | Jun 03, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [d8348d5353](https://linux-hardware.org/?probe=d8348d5353) | Jun 03, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [84d1d3efdc](https://linux-hardware.org/?probe=84d1d3efdc) | Jun 03, 2022 |
| Huanan        | X79-8D VAA31                | Desktop     | [eefff24cc2](https://linux-hardware.org/?probe=eefff24cc2) | Jun 03, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [0fe589689b](https://linux-hardware.org/?probe=0fe589689b) | Jun 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [35ff0536a6](https://linux-hardware.org/?probe=35ff0536a6) | Jun 02, 2022 |
| Dell          | Latitude 9420               | Notebook    | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | Notebook    | [fd7f5dd506](https://linux-hardware.org/?probe=fd7f5dd506) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | Notebook    | [84efabac8f](https://linux-hardware.org/?probe=84efabac8f) | Jun 01, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [4ae400000f](https://linux-hardware.org/?probe=4ae400000f) | Jun 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [156b265da0](https://linux-hardware.org/?probe=156b265da0) | Jun 01, 2022 |
| Gigabyte      | 970A-UD3                    | Desktop     | [c56522071c](https://linux-hardware.org/?probe=c56522071c) | Jun 01, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [58051fe7e2](https://linux-hardware.org/?probe=58051fe7e2) | Jun 01, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [d561d8dbdb](https://linux-hardware.org/?probe=d561d8dbdb) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | Notebook    | [460e11ebe2](https://linux-hardware.org/?probe=460e11ebe2) | May 31, 2022 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [5b8924befc](https://linux-hardware.org/?probe=5b8924befc) | May 31, 2022 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [ec75dd8324](https://linux-hardware.org/?probe=ec75dd8324) | May 31, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ed68bc8e1d](https://linux-hardware.org/?probe=ed68bc8e1d) | May 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [3195728920](https://linux-hardware.org/?probe=3195728920) | May 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [799a25df83](https://linux-hardware.org/?probe=799a25df83) | May 31, 2022 |
| Dell          | Latitude 5511               | Notebook    | [ef262c4020](https://linux-hardware.org/?probe=ef262c4020) | May 31, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2f14b6956f](https://linux-hardware.org/?probe=2f14b6956f) | May 31, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6560268d80](https://linux-hardware.org/?probe=6560268d80) | May 31, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f2500a22ea](https://linux-hardware.org/?probe=f2500a22ea) | May 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [deaac8464e](https://linux-hardware.org/?probe=deaac8464e) | May 31, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [6b22d31e8e](https://linux-hardware.org/?probe=6b22d31e8e) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [580abb0cf9](https://linux-hardware.org/?probe=580abb0cf9) | May 30, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | Notebook    | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| Lenovo        | Yoga Duet IML 2020 82E9     | Tablet      | [63eab4a6b5](https://linux-hardware.org/?probe=63eab4a6b5) | May 30, 2022 |
| Dell          | Latitude 5511               | Notebook    | [33b796acff](https://linux-hardware.org/?probe=33b796acff) | May 30, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [a1e7cf7158](https://linux-hardware.org/?probe=a1e7cf7158) | May 30, 2022 |
| MSI           | B365M PRO-VH                | Desktop     | [4d4ea4beec](https://linux-hardware.org/?probe=4d4ea4beec) | May 30, 2022 |
| ASUSTek       | X555UQ                      | Notebook    | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| Huanan        | X99-TF                      | Desktop     | [cb08cd42a9](https://linux-hardware.org/?probe=cb08cd42a9) | May 30, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [3299abfc78](https://linux-hardware.org/?probe=3299abfc78) | May 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2ce35a0cba](https://linux-hardware.org/?probe=2ce35a0cba) | May 30, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [3bb74db496](https://linux-hardware.org/?probe=3bb74db496) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [c71a8e9817](https://linux-hardware.org/?probe=c71a8e9817) | May 29, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [ca67455f28](https://linux-hardware.org/?probe=ca67455f28) | May 29, 2022 |
| Timi          | TM1604                      | Notebook    | [cd9b839800](https://linux-hardware.org/?probe=cd9b839800) | May 29, 2022 |
| Gigabyte      | X570 UD                     | Desktop     | [627604d5dc](https://linux-hardware.org/?probe=627604d5dc) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | Notebook    | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [1c71dac18b](https://linux-hardware.org/?probe=1c71dac18b) | May 29, 2022 |
| ASUSTek       | GL502VSK                    | Notebook    | [44fb5da9d6](https://linux-hardware.org/?probe=44fb5da9d6) | May 29, 2022 |
| eMachines     | eM350                       | Notebook    | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [09aa4c998d](https://linux-hardware.org/?probe=09aa4c998d) | May 28, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c84d9cc3c4](https://linux-hardware.org/?probe=c84d9cc3c4) | May 28, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6b3439b423](https://linux-hardware.org/?probe=6b3439b423) | May 28, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [cd703bd1b1](https://linux-hardware.org/?probe=cd703bd1b1) | May 28, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [f67fdd8166](https://linux-hardware.org/?probe=f67fdd8166) | May 28, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1238dba054](https://linux-hardware.org/?probe=1238dba054) | May 28, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [cf38cf9584](https://linux-hardware.org/?probe=cf38cf9584) | May 28, 2022 |
| ASUSTek       | G750JX                      | Notebook    | [dfb08cef0b](https://linux-hardware.org/?probe=dfb08cef0b) | May 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [09a0a17046](https://linux-hardware.org/?probe=09a0a17046) | May 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [caeeaac144](https://linux-hardware.org/?probe=caeeaac144) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [ae044ab2d9](https://linux-hardware.org/?probe=ae044ab2d9) | May 28, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e64dfe3f6f](https://linux-hardware.org/?probe=e64dfe3f6f) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [b8c8e8baef](https://linux-hardware.org/?probe=b8c8e8baef) | May 27, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [74c7a449f9](https://linux-hardware.org/?probe=74c7a449f9) | May 27, 2022 |
| Dell          | 0T7D40 A00                  | Desktop     | [c9c3fd7a7e](https://linux-hardware.org/?probe=c9c3fd7a7e) | May 27, 2022 |
| HP            | 0A80h                       | Desktop     | [7e5c6cf61e](https://linux-hardware.org/?probe=7e5c6cf61e) | May 27, 2022 |
| ASRock        | FM2A75M-DGS                 | Desktop     | [73260214ee](https://linux-hardware.org/?probe=73260214ee) | May 27, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [72ead90cb6](https://linux-hardware.org/?probe=72ead90cb6) | May 26, 2022 |
| System76      | Lemur Pro                   | Notebook    | [dcfd3abdd6](https://linux-hardware.org/?probe=dcfd3abdd6) | May 26, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d6bd3ae553](https://linux-hardware.org/?probe=d6bd3ae553) | May 26, 2022 |
| Dell          | G15 5515                    | Notebook    | [4f47780467](https://linux-hardware.org/?probe=4f47780467) | May 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [4673dbdffc](https://linux-hardware.org/?probe=4673dbdffc) | May 26, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [1eecb7a012](https://linux-hardware.org/?probe=1eecb7a012) | May 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c035632382](https://linux-hardware.org/?probe=c035632382) | May 26, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [2eb4f98b37](https://linux-hardware.org/?probe=2eb4f98b37) | May 26, 2022 |
| Acer          | Aspire A515-46              | Notebook    | [e004aa3fd2](https://linux-hardware.org/?probe=e004aa3fd2) | May 25, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [09ba129a3b](https://linux-hardware.org/?probe=09ba129a3b) | May 25, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [fc5aa62215](https://linux-hardware.org/?probe=fc5aa62215) | May 25, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [13006f8cc4](https://linux-hardware.org/?probe=13006f8cc4) | May 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | Notebook    | [4b23940919](https://linux-hardware.org/?probe=4b23940919) | May 25, 2022 |
| Acer          | WG43M                       | Desktop     | [ae5adc512f](https://linux-hardware.org/?probe=ae5adc512f) | May 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c8051b3bfc](https://linux-hardware.org/?probe=c8051b3bfc) | May 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [4140810d35](https://linux-hardware.org/?probe=4140810d35) | May 24, 2022 |
| HP            | 83EF                        | Desktop     | [4f52313cee](https://linux-hardware.org/?probe=4f52313cee) | May 24, 2022 |
| System76      | Oryx Pro                    | Notebook    | [f95bed2419](https://linux-hardware.org/?probe=f95bed2419) | May 24, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [76789ea4f5](https://linux-hardware.org/?probe=76789ea4f5) | May 24, 2022 |
| System76      | Oryx Pro                    | Notebook    | [10502c5379](https://linux-hardware.org/?probe=10502c5379) | May 24, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [65710bb1bc](https://linux-hardware.org/?probe=65710bb1bc) | May 23, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [872649a8b4](https://linux-hardware.org/?probe=872649a8b4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5c74b9f6e4](https://linux-hardware.org/?probe=5c74b9f6e4) | May 23, 2022 |
| HP            | Pavilion 15                 | Notebook    | [ca77af8ab9](https://linux-hardware.org/?probe=ca77af8ab9) | May 23, 2022 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [51ce08137b](https://linux-hardware.org/?probe=51ce08137b) | May 23, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [0c144ce08f](https://linux-hardware.org/?probe=0c144ce08f) | May 22, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5ab3662d65](https://linux-hardware.org/?probe=5ab3662d65) | May 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [fe1d187774](https://linux-hardware.org/?probe=fe1d187774) | May 22, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [47b2310054](https://linux-hardware.org/?probe=47b2310054) | May 22, 2022 |
| Google        | Quawks                      | Notebook    | [cb763161cf](https://linux-hardware.org/?probe=cb763161cf) | May 22, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [01b1caa77a](https://linux-hardware.org/?probe=01b1caa77a) | May 21, 2022 |
| Gigabyte      | Z97P-D3                     | Desktop     | [1b7bdd0f65](https://linux-hardware.org/?probe=1b7bdd0f65) | May 21, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [f0fb1b2fc1](https://linux-hardware.org/?probe=f0fb1b2fc1) | May 21, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [77ee982546](https://linux-hardware.org/?probe=77ee982546) | May 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f2c0dedc02](https://linux-hardware.org/?probe=f2c0dedc02) | May 20, 2022 |
| Lenovo        | NOK                         | Desktop     | [567c167a97](https://linux-hardware.org/?probe=567c167a97) | May 20, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [99283be07b](https://linux-hardware.org/?probe=99283be07b) | May 20, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [ee62ecda2e](https://linux-hardware.org/?probe=ee62ecda2e) | May 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [e9a6f0bd85](https://linux-hardware.org/?probe=e9a6f0bd85) | May 19, 2022 |
| Google        | Caroline                    | Notebook    | [2b665e84d3](https://linux-hardware.org/?probe=2b665e84d3) | May 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Arch             | 2994      | 60.14%  |
| Arch Rolling     | 1960      | 39.37%  |
| Arch V20.4.11    | 3         | 0.06%   |
| Arch V19.11.3    | 3         | 0.06%   |
| Arch V20.5.7     | 2         | 0.04%   |
| Arch V20.3.4     | 2         | 0.04%   |
| Arch V19.04.4    | 2         | 0.04%   |
| Arch Workstation | 1         | 0.02%   |
| Arch V6.9.2      | 1         | 0.02%   |
| Arch V19.09.1    | 1         | 0.02%   |
| Arch V19.07.9    | 1         | 0.02%   |
| Arch V19.07.11   | 1         | 0.02%   |
| Arch V19.06.1    | 1         | 0.02%   |
| Arch V19.05.2    | 1         | 0.02%   |
| Arch V19.01.4    | 1         | 0.02%   |
| Arch Breaking    | 1         | 0.02%   |
| Arch 2020.09.05  | 1         | 0.02%   |
| Arch 20.08.3     | 1         | 0.02%   |
| Arch 2.7         | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| Arch | 4866      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 85        | 1.48%   |
| 5.8.5-arch1-1   | 70        | 1.22%   |
| 5.9.14-arch1-1  | 61        | 1.06%   |
| 5.9.1-arch1-1   | 60        | 1.05%   |
| 5.17.5-arch1-1  | 53        | 0.92%   |
| 5.8.12-arch1-1  | 49        | 0.86%   |
| 5.17.9-arch1-1  | 49        | 0.86%   |
| 5.8.10-arch1-1  | 48        | 0.84%   |
| 5.8.14-arch1-1  | 47        | 0.82%   |
| 5.7.12-arch1-1  | 46        | 0.8%    |
| 5.13.13-arch1-1 | 45        | 0.79%   |
| 5.8.1-arch1-1   | 43        | 0.75%   |
| 5.11.16-arch1-1 | 42        | 0.73%   |
| 5.6.15-arch1-1  | 37        | 0.65%   |
| 5.18.16-arch1-1 | 35        | 0.61%   |
| 5.11.6-arch1-1  | 34        | 0.59%   |
| 5.11.11-arch1-1 | 34        | 0.59%   |
| 5.18.1-arch1-1  | 33        | 0.58%   |
| 5.12.15-arch1-1 | 33        | 0.58%   |
| 5.10.16-arch1-1 | 33        | 0.58%   |
| 5.8.3-arch1-1   | 31        | 0.54%   |
| 5.15.7-arch1-1  | 31        | 0.54%   |
| 5.14.14-arch1-1 | 31        | 0.54%   |
| 5.9.11-arch2-1  | 30        | 0.52%   |
| 5.9.10-arch1-1  | 30        | 0.52%   |
| 5.19.7-arch1-1  | 30        | 0.52%   |
| 5.13.12-arch1-1 | 30        | 0.52%   |
| 5.7.6-arch1-1   | 29        | 0.51%   |
| 5.6.13-arch1-1  | 29        | 0.51%   |
| 5.18.5-arch1-1  | 29        | 0.51%   |
| 5.11.2-arch1-1  | 29        | 0.51%   |
| 5.12.14-arch1-1 | 28        | 0.49%   |
| 5.14.8-arch1-1  | 27        | 0.47%   |
| 5.8.7-arch1-1   | 26        | 0.45%   |
| 5.18.14-arch1-1 | 26        | 0.45%   |
| 5.16.16-arch1-1 | 26        | 0.45%   |
| 5.9.8-arch1-1   | 25        | 0.44%   |
| 5.6.4-arch1-1   | 25        | 0.44%   |
| 5.4.13-arch1-1  | 25        | 0.44%   |
| 5.19.9-arch1-1  | 25        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.17.1  | 105       | 1.83%   |
| 5.8.5   | 92        | 1.61%   |
| 5.9.1   | 77        | 1.34%   |
| 5.8.12  | 74        | 1.29%   |
| 5.9.14  | 72        | 1.26%   |
| 5.17.5  | 70        | 1.22%   |
| 5.8.14  | 63        | 1.1%    |
| 5.8.10  | 62        | 1.08%   |
| 5.17.9  | 59        | 1.03%   |
| 5.13.13 | 56        | 0.98%   |
| 5.8.1   | 53        | 0.93%   |
| 5.7.12  | 53        | 0.93%   |
| 5.11.6  | 52        | 0.91%   |
| 5.11.16 | 51        | 0.89%   |
| 5.11.2  | 43        | 0.75%   |
| 5.18.16 | 42        | 0.73%   |
| 5.12.15 | 42        | 0.73%   |
| 5.10.16 | 42        | 0.73%   |
| 5.11.11 | 41        | 0.72%   |
| 5.19.7  | 39        | 0.68%   |
| 5.18.1  | 39        | 0.68%   |
| 5.7.6   | 38        | 0.66%   |
| 5.6.15  | 38        | 0.66%   |
| 5.15.7  | 38        | 0.66%   |
| 5.14.14 | 38        | 0.66%   |
| 5.12.14 | 38        | 0.66%   |
| 5.16.2  | 37        | 0.65%   |
| 5.8.3   | 36        | 0.63%   |
| 5.16.16 | 36        | 0.63%   |
| 5.14.8  | 36        | 0.63%   |
| 5.13.12 | 36        | 0.63%   |
| 5.12.9  | 36        | 0.63%   |
| 5.9.11  | 35        | 0.61%   |
| 5.6.13  | 35        | 0.61%   |
| 5.18.5  | 35        | 0.61%   |
| 5.18.3  | 35        | 0.61%   |
| 5.9.8   | 32        | 0.56%   |
| 5.9.10  | 32        | 0.56%   |
| 5.4.13  | 32        | 0.56%   |
| 5.19.9  | 31        | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.8     | 523       | 9.46%   |
| 5.15    | 396       | 7.17%   |
| 5.9     | 384       | 6.95%   |
| 5.18    | 356       | 6.44%   |
| 5.10    | 354       | 6.41%   |
| 5.4     | 353       | 6.39%   |
| 5.11    | 350       | 6.33%   |
| 5.17    | 340       | 6.15%   |
| 5.12    | 309       | 5.59%   |
| 5.16    | 305       | 5.52%   |
| 5.19    | 275       | 4.98%   |
| 5.6     | 263       | 4.76%   |
| 5.7     | 260       | 4.71%   |
| 5.14    | 236       | 4.27%   |
| 5.13    | 233       | 4.22%   |
| 5.5     | 148       | 2.68%   |
| 5.3     | 114       | 2.06%   |
| 4.19    | 56        | 1.01%   |
| 5.2     | 54        | 0.98%   |
| 5.0     | 41        | 0.74%   |
| 4.18    | 37        | 0.67%   |
| 5.1     | 32        | 0.58%   |
| 4.20    | 22        | 0.4%    |
| 4.17    | 19        | 0.34%   |
| 4.15    | 14        | 0.25%   |
| 4.14    | 10        | 0.18%   |
| 4.16    | 9         | 0.16%   |
| 4.9     | 5         | 0.09%   |
| 4.7     | 4         | 0.07%   |
| 4.6     | 4         | 0.07%   |
| 4.11    | 4         | 0.07%   |
| 6.0     | 3         | 0.05%   |
| 4.8     | 3         | 0.05%   |
| 4.4     | 3         | 0.05%   |
| 4.13    | 3         | 0.05%   |
| 4.10    | 2         | 0.04%   |
| 4.12    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 4862      | 99.92%  |
| i686   | 4         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 1632      | 32.17%  |
| KDE5                     | 1136      | 22.39%  |
| Unknown                  | 706       | 13.92%  |
| XFCE                     | 420       | 8.28%   |
| KDE                      | 285       | 5.62%   |
| i3                       | 260       | 5.13%   |
| Budgie                   | 77        | 1.52%   |
| MATE                     | 76        | 1.5%    |
| Cinnamon                 | 72        | 1.42%   |
| X-Cinnamon               | 64        | 1.26%   |
| Deepin                   | 59        | 1.16%   |
| sway                     | 54        | 1.06%   |
| LXQt                     | 41        | 0.81%   |
| LXDE                     | 29        | 0.57%   |
| bspwm                    | 26        | 0.51%   |
| awesome                  | 24        | 0.47%   |
| openbox                  | 16        | 0.32%   |
| GNOME Flashback          | 15        | 0.3%    |
| qtile                    | 14        | 0.28%   |
| xmonad                   | 11        | 0.22%   |
| Unity                    | 8         | 0.16%   |
| DWM                      | 7         | 0.14%   |
| GNOME Classic            | 5         | 0.1%    |
| i3-with-shmlog           | 4         | 0.08%   |
| Enlightenment            | 4         | 0.08%   |
| Hyprland                 | 3         | 0.06%   |
| river                    | 2         | 0.04%   |
| LeftWM                   | 2         | 0.04%   |
| jwm                      | 2         | 0.04%   |
| ICEWM                    | 2         | 0.04%   |
| GNUstep                  | 2         | 0.04%   |
| dusk                     | 2         | 0.04%   |
| default                  | 2         | 0.04%   |
| /usr/bin/openbox-session | 2         | 0.04%   |
| Yaru:ubuntu:GNOME        | 1         | 0.02%   |
| xinitrc                  | 1         | 0.02%   |
| X-Generic                | 1         | 0.02%   |
| Wayfire                  | 1         | 0.02%   |
| sway:Unity               | 1         | 0.02%   |
| Pantheon                 | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3133      | 62.27%  |
| Wayland | 1057      | 21.01%  |
| Tty     | 488       | 9.7%    |
| Unknown | 352       | 7%      |
| Web     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2110      | 41.97%  |
| SDDM    | 1122      | 22.32%  |
| GDM     | 718       | 14.28%  |
| LightDM | 488       | 9.71%   |
| TDM     | 398       | 7.92%   |
| Ly      | 55        | 1.09%   |
| XDM     | 54        | 1.07%   |
| LXDM    | 43        | 0.86%   |
| SLiM    | 22        | 0.44%   |
| GREETD  | 9         | 0.18%   |
| NODM    | 4         | 0.08%   |
| XINIT   | 1         | 0.02%   |
| MDM     | 1         | 0.02%   |
| KDM     | 1         | 0.02%   |
| EMPTTY  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 2419      | 48.54%  |
| Unknown    | 576       | 11.56%  |
| en_GB      | 293       | 5.88%   |
| C          | 212       | 4.25%   |
| de_DE      | 209       | 4.19%   |
| ru_RU      | 143       | 2.87%   |
| pt_BR      | 138       | 2.77%   |
| fr_FR      | 117       | 2.35%   |
| it_IT      | 103       | 2.07%   |
| pl_PL      | 70        | 1.4%    |
| es_ES      | 57        | 1.14%   |
| en_IN      | 56        | 1.12%   |
| en_CA      | 56        | 1.12%   |
| en_AU      | 47        | 0.94%   |
| zh_CN      | 43        | 0.86%   |
| en_IE      | 28        | 0.56%   |
| es_MX      | 20        | 0.4%    |
| en_DK      | 19        | 0.38%   |
| de_AT      | 19        | 0.38%   |
| hu_HU      | 17        | 0.34%   |
| es_AR      | 16        | 0.32%   |
| en_NZ      | 15        | 0.3%    |
| nl_NL      | 14        | 0.28%   |
| tr_TR      | 13        | 0.26%   |
| ru_UA      | 13        | 0.26%   |
| es_CL      | 12        | 0.24%   |
| ja_JP      | 11        | 0.22%   |
| cs_CZ      | 11        | 0.22%   |
| es_CO      | 10        | 0.2%    |
| en_US.UTF8 | 10        | 0.2%    |
| en_SG      | 10        | 0.2%    |
| pt_PT      | 9         | 0.18%   |
| en_DE      | 9         | 0.18%   |
| uk_UA      | 7         | 0.14%   |
| sv_SE      | 7         | 0.14%   |
| lv_LV      | 7         | 0.14%   |
| en_ZA      | 7         | 0.14%   |
| de_CH      | 7         | 0.14%   |
| ca_ES      | 7         | 0.14%   |
| zh_TW      | 6         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 3083      | 61.94%  |
| BIOS | 1894      | 38.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3586      | 72.69%  |
| Btrfs    | 901       | 18.26%  |
| Unknown  | 176       | 3.57%   |
| Xfs      | 125       | 2.53%   |
| F2fs     | 74        | 1.5%    |
| Overlay  | 28        | 0.57%   |
| Zfs      | 25        | 0.51%   |
| Ext2     | 8         | 0.16%   |
| XXXXX    | 4         | 0.08%   |
| Ext3     | 2         | 0.04%   |
| XXX4     | 1         | 0.02%   |
| Reiserfs | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 3090      | 62.51%  |
| Unknown | 1411      | 28.55%  |
| MBR     | 442       | 8.94%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4228      | 85.69%  |
| Yes       | 706       | 14.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3388      | 68.53%  |
| Yes       | 1556      | 31.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 941       | 19.34%  |
| Lenovo                 | 872       | 17.92%  |
| Dell                   | 525       | 10.79%  |
| Hewlett-Packard        | 496       | 10.19%  |
| MSI                    | 410       | 8.43%   |
| Gigabyte Technology    | 407       | 8.36%   |
| ASRock                 | 266       | 5.47%   |
| Acer                   | 235       | 4.83%   |
| Apple                  | 77        | 1.58%   |
| Intel                  | 62        | 1.27%   |
| Samsung Electronics    | 53        | 1.09%   |
| HUAWEI                 | 43        | 0.88%   |
| Toshiba                | 36        | 0.74%   |
| Notebook               | 26        | 0.53%   |
| Unknown                | 24        | 0.49%   |
| Microsoft              | 22        | 0.45%   |
| Google                 | 19        | 0.39%   |
| Sony                   | 18        | 0.37%   |
| Timi                   | 16        | 0.33%   |
| Framework              | 16        | 0.33%   |
| TUXEDO                 | 14        | 0.29%   |
| Razer                  | 13        | 0.27%   |
| Fujitsu                | 13        | 0.27%   |
| Biostar                | 13        | 0.27%   |
| Alienware              | 13        | 0.27%   |
| Pegatron               | 10        | 0.21%   |
| LG Electronics         | 10        | 0.21%   |
| ECS                    | 10        | 0.21%   |
| Medion                 | 9         | 0.18%   |
| System76               | 8         | 0.16%   |
| Positivo               | 8         | 0.16%   |
| Supermicro             | 7         | 0.14%   |
| Schenker               | 7         | 0.14%   |
| Packard Bell           | 7         | 0.14%   |
| Avell High Performance | 7         | 0.14%   |
| MECHREVO               | 6         | 0.12%   |
| Huanan                 | 6         | 0.12%   |
| Chuwi                  | 6         | 0.12%   |
| ZOTAC                  | 4         | 0.08%   |
| Teclast                | 4         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| ASUS All Series                  | 54        | 1.11%   |
| Unknown                          | 44        | 0.9%    |
| MSI MS-7C37                      | 26        | 0.53%   |
| ASUS TUF Gaming X570-PLUS        | 24        | 0.49%   |
| MSI MS-7C02                      | 21        | 0.43%   |
| MSI MS-7B86                      | 20        | 0.41%   |
| Gigabyte B450M DS3H              | 19        | 0.39%   |
| MSI MS-7A34                      | 16        | 0.33%   |
| Framework Laptop                 | 15        | 0.31%   |
| ASUS PRIME X470-PRO              | 15        | 0.31%   |
| MSI MS-7C91                      | 14        | 0.29%   |
| MSI MS-7A38                      | 14        | 0.29%   |
| Dell XPS 15 9570                 | 14        | 0.29%   |
| ASUS ROG STRIX B450-F GAMING     | 14        | 0.29%   |
| MSI MS-7B89                      | 13        | 0.27%   |
| HP Notebook                      | 13        | 0.27%   |
| Gigabyte X470 AORUS ULTRA GAMING | 13        | 0.27%   |
| ASUS PRIME X370-PRO              | 13        | 0.27%   |
| ASUS PRIME B450M-A               | 13        | 0.27%   |
| Dell XPS 15 9500                 | 12        | 0.25%   |
| MSI MS-7B79                      | 11        | 0.23%   |
| Gigabyte X570 AORUS ELITE        | 11        | 0.23%   |
| Gigabyte 970A-DS3P               | 11        | 0.23%   |
| Dell XPS 13 9360                 | 10        | 0.21%   |
| Dell Inspiron 15 7000 Gaming     | 10        | 0.21%   |
| ASUS ROG STRIX X570-E GAMING     | 10        | 0.21%   |
| ASUS ROG STRIX B550-F GAMING     | 10        | 0.21%   |
| ASRock X570 Taichi               | 10        | 0.21%   |
| HP EliteBook 840 G6              | 9         | 0.18%   |
| Dell XPS 15 7590                 | 9         | 0.18%   |
| Dell XPS 13 9380                 | 9         | 0.18%   |
| Dell XPS 13 9370                 | 9         | 0.18%   |
| ASUS ROG STRIX X470-F GAMING     | 9         | 0.18%   |
| Lenovo IdeaPad 5 14ARE05 81YM    | 8         | 0.16%   |
| HUAWEI NBLK-WAX9X                | 8         | 0.16%   |
| HP EliteBook x360 1030 G2        | 8         | 0.16%   |
| Gigabyte X570 I AORUS PRO WIFI   | 8         | 0.16%   |
| Gigabyte B550I AORUS PRO AX      | 8         | 0.16%   |
| Gigabyte B450 AORUS M            | 8         | 0.16%   |
| Gigabyte B450 AORUS ELITE        | 8         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 479       | 9.84%   |
| ASUS ROG           | 166       | 3.41%   |
| ASUS PRIME         | 149       | 3.06%   |
| Lenovo IdeaPad     | 147       | 3.02%   |
| Dell Inspiron      | 137       | 2.82%   |
| Acer Aspire        | 136       | 2.79%   |
| Dell XPS           | 125       | 2.57%   |
| Dell Latitude      | 112       | 2.3%    |
| ASUS TUF           | 106       | 2.18%   |
| HP Pavilion        | 87        | 1.79%   |
| HP EliteBook       | 84        | 1.73%   |
| ASUS All           | 54        | 1.11%   |
| HP ENVY            | 52        | 1.07%   |
| Lenovo Legion      | 50        | 1.03%   |
| Lenovo Yoga        | 47        | 0.97%   |
| HP Laptop          | 47        | 0.97%   |
| ASUS VivoBook      | 47        | 0.97%   |
| Dell Precision     | 46        | 0.95%   |
| Gigabyte X570      | 45        | 0.92%   |
| HP ProBook         | 44        | 0.9%    |
| Unknown            | 44        | 0.9%    |
| Dell OptiPlex      | 40        | 0.82%   |
| Acer Nitro         | 34        | 0.7%    |
| Toshiba Satellite  | 28        | 0.58%   |
| Gigabyte B450M     | 28        | 0.58%   |
| Dell Vostro        | 27        | 0.55%   |
| MSI MS-7C37        | 26        | 0.53%   |
| ASRock X570        | 26        | 0.53%   |
| Gigabyte B450      | 25        | 0.51%   |
| Acer Swift         | 24        | 0.49%   |
| HP Spectre         | 23        | 0.47%   |
| Microsoft Surface  | 22        | 0.45%   |
| MSI MS-7C02        | 21        | 0.43%   |
| MSI MS-7B86        | 20        | 0.41%   |
| ASUS STRIX         | 20        | 0.41%   |
| Lenovo ThinkCentre | 19        | 0.39%   |
| HP OMEN            | 19        | 0.39%   |
| HP Compaq          | 19        | 0.39%   |
| ASUS ZenBook       | 19        | 0.39%   |
| ASUS ASUS          | 18        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 771       | 15.84%  |
| 2019    | 732       | 15.04%  |
| 2020    | 601       | 12.35%  |
| 2017    | 458       | 9.41%   |
| 2021    | 340       | 6.99%   |
| 2016    | 300       | 6.17%   |
| 2012    | 284       | 5.84%   |
| 2013    | 272       | 5.59%   |
| 2015    | 265       | 5.45%   |
| 2014    | 254       | 5.22%   |
| 2011    | 225       | 4.62%   |
| 2010    | 126       | 2.59%   |
| 2008    | 76        | 1.56%   |
| 2009    | 67        | 1.38%   |
| 2022    | 56        | 1.15%   |
| 2007    | 24        | 0.49%   |
| 2006    | 9         | 0.18%   |
| Unknown | 3         | 0.06%   |
| 2005    | 2         | 0.04%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2613      | 53.7%   |
| Desktop     | 1946      | 39.99%  |
| Convertible | 170       | 3.49%   |
| Tablet      | 44        | 0.9%    |
| Mini pc     | 44        | 0.9%    |
| All in one  | 30        | 0.62%   |
| Server      | 18        | 0.37%   |
| Stick pc    | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4835      | 99.2%   |
| Enabled  | 39        | 0.8%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4831      | 99.28%  |
| Yes  | 35        | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 1463      | 29.62%  |
| 8.01-16.0       | 959       | 19.42%  |
| 4.01-8.0        | 918       | 18.59%  |
| 32.01-64.0      | 762       | 15.43%  |
| 3.01-4.0        | 431       | 8.73%   |
| 64.01-256.0     | 176       | 3.56%   |
| 24.01-32.0      | 116       | 2.35%   |
| 1.01-2.0        | 66        | 1.34%   |
| 2.01-3.0        | 28        | 0.57%   |
| 0.51-1.0        | 11        | 0.22%   |
| More than 256.0 | 7         | 0.14%   |
| Unknown         | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1278      | 23.83%  |
| 1.01-2.0    | 1228      | 22.9%   |
| 4.01-8.0    | 1216      | 22.67%  |
| 3.01-4.0    | 841       | 15.68%  |
| 8.01-16.0   | 422       | 7.87%   |
| 0.51-1.0    | 204       | 3.8%    |
| 16.01-24.0  | 77        | 1.44%   |
| 0.01-0.5    | 50        | 0.93%   |
| 24.01-32.0  | 31        | 0.58%   |
| 32.01-64.0  | 13        | 0.24%   |
| Unknown     | 2         | 0.04%   |
| 64.01-256.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2426      | 48.49%  |
| 2      | 1401      | 28%     |
| 3      | 573       | 11.45%  |
| 4      | 271       | 5.42%   |
| 5      | 157       | 3.14%   |
| 6      | 69        | 1.38%   |
| 7      | 40        | 0.8%    |
| 0      | 19        | 0.38%   |
| 8      | 17        | 0.34%   |
| 9      | 15        | 0.3%    |
| 11     | 4         | 0.08%   |
| 12     | 3         | 0.06%   |
| 10     | 3         | 0.06%   |
| 14     | 2         | 0.04%   |
| 22     | 1         | 0.02%   |
| 17     | 1         | 0.02%   |
| 15     | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3784      | 77.27%  |
| Yes       | 1113      | 22.73%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4135      | 84.66%  |
| No        | 749       | 15.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3746      | 76.57%  |
| No        | 1146      | 23.43%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3333      | 67.69%  |
| No        | 1591      | 32.31%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 947       | 19.33%  |
| Germany     | 481       | 9.82%   |
| Russia      | 318       | 6.49%   |
| Brazil      | 262       | 5.35%   |
| France      | 225       | 4.59%   |
| UK          | 193       | 3.94%   |
| Italy       | 177       | 3.61%   |
| India       | 157       | 3.21%   |
| Poland      | 146       | 2.98%   |
| Canada      | 129       | 2.63%   |
| Spain       | 112       | 2.29%   |
| Netherlands | 103       | 2.1%    |
| Ukraine     | 86        | 1.76%   |
| Austria     | 81        | 1.65%   |
| China       | 80        | 1.63%   |
| Australia   | 80        | 1.63%   |
| Sweden      | 77        | 1.57%   |
| Turkey      | 55        | 1.12%   |
| Finland     | 54        | 1.1%    |
| Switzerland | 47        | 0.96%   |
| Mexico      | 45        | 0.92%   |
| Czechia     | 44        | 0.9%    |
| Belgium     | 44        | 0.9%    |
| Hungary     | 41        | 0.84%   |
| Romania     | 39        | 0.8%    |
| Greece      | 38        | 0.78%   |
| Argentina   | 36        | 0.73%   |
| Indonesia   | 35        | 0.71%   |
| Norway      | 33        | 0.67%   |
| Japan       | 32        | 0.65%   |
| Chile       | 31        | 0.63%   |
| Iran        | 29        | 0.59%   |
| Vietnam     | 27        | 0.55%   |
| Portugal    | 27        | 0.55%   |
| New Zealand | 26        | 0.53%   |
| Denmark     | 26        | 0.53%   |
| Colombia    | 25        | 0.51%   |
| Serbia      | 22        | 0.45%   |
| Bulgaria    | 21        | 0.43%   |
| Lithuania   | 19        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 89        | 1.72%   |
| Paris             | 52        | 1.01%   |
| St Petersburg     | 50        | 0.97%   |
| Berlin            | 45        | 0.87%   |
| Vienna            | 43        | 0.83%   |
| Sao Paulo         | 42        | 0.81%   |
| Warsaw            | 38        | 0.74%   |
| Munich            | 32        | 0.62%   |
| Helsinki          | 29        | 0.56%   |
| Frankfurt am Main | 28        | 0.54%   |
| Amsterdam         | 27        | 0.52%   |
| Sydney            | 25        | 0.48%   |
| Melbourne         | 25        | 0.48%   |
| Los Angeles       | 23        | 0.45%   |
| Kyiv              | 23        | 0.45%   |
| Hamburg           | 22        | 0.43%   |
| Milan             | 21        | 0.41%   |
| London            | 21        | 0.41%   |
| Prague            | 20        | 0.39%   |
| New York          | 20        | 0.39%   |
| Athens            | 20        | 0.39%   |
| Valencia          | 19        | 0.37%   |
| Istanbul          | 18        | 0.35%   |
| Budapest          | 18        | 0.35%   |
| Bengaluru         | 18        | 0.35%   |
| Krakow            | 17        | 0.33%   |
| Cologne           | 17        | 0.33%   |
| Seattle           | 16        | 0.31%   |
| Montreal          | 16        | 0.31%   |
| Madrid            | 16        | 0.31%   |
| Dallas            | 16        | 0.31%   |
| Shanghai          | 15        | 0.29%   |
| Belgrade          | 15        | 0.29%   |
| Beijing           | 15        | 0.29%   |
| Zurich            | 14        | 0.27%   |
| Stockholm         | 14        | 0.27%   |
| Singapore         | 14        | 0.27%   |
| Rome              | 14        | 0.27%   |
| Phoenix           | 14        | 0.27%   |
| Barcelona         | 14        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 1643      | 2591   | 20.21%  |
| WDC                       | 1236      | 1893   | 15.2%   |
| Seagate                   | 1037      | 1565   | 12.76%  |
| Toshiba                   | 562       | 743    | 6.91%   |
| SanDisk                   | 504       | 665    | 6.2%    |
| Kingston                  | 430       | 557    | 5.29%   |
| Crucial                   | 362       | 511    | 4.45%   |
| SK hynix                  | 244       | 292    | 3%      |
| Intel                     | 226       | 299    | 2.78%   |
| Unknown                   | 202       | 244    | 2.48%   |
| HGST                      | 148       | 185    | 1.82%   |
| Hitachi                   | 139       | 172    | 1.71%   |
| A-DATA Technology         | 129       | 181    | 1.59%   |
| Micron Technology         | 112       | 132    | 1.38%   |
| Phison                    | 108       | 141    | 1.33%   |
| Apple                     | 51        | 62     | 0.63%   |
| China                     | 49        | 60     | 0.6%    |
| Silicon Motion            | 48        | 57     | 0.59%   |
| OCZ                       | 45        | 61     | 0.55%   |
| Corsair                   | 45        | 58     | 0.55%   |
| SPCC                      | 41        | 45     | 0.5%    |
| Transcend                 | 39        | 49     | 0.48%   |
| LITEON                    | 36        | 39     | 0.44%   |
| KIOXIA                    | 35        | 46     | 0.43%   |
| Patriot                   | 34        | 40     | 0.42%   |
| PNY                       | 33        | 39     | 0.41%   |
| Micron/Crucial Technology | 32        | 38     | 0.39%   |
| XPG                       | 26        | 36     | 0.32%   |
| GOODRAM                   | 22        | 25     | 0.27%   |
| Hewlett-Packard           | 20        | 21     | 0.25%   |
| Plextor                   | 19        | 28     | 0.23%   |
| Lenovo                    | 17        | 19     | 0.21%   |
| Lexar                     | 15        | 19     | 0.18%   |
| JMicron Technology        | 15        | 15     | 0.18%   |
| Gigabyte Technology       | 15        | 17     | 0.18%   |
| SABRENT                   | 14        | 15     | 0.17%   |
| Realtek Semiconductor     | 14        | 17     | 0.17%   |
| Phison Electronics        | 14        | 16     | 0.17%   |
| Intenso                   | 14        | 15     | 0.17%   |
| LITEONIT                  | 13        | 13     | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB                           | 100       | 1.08%   |
| Samsung SSD 860 EVO 500GB                           | 93        | 1%      |
| Seagate ST1000LM035-1RK172 1TB                      | 84        | 0.9%    |
| Samsung NVMe SSD Drive 512GB                        | 82        | 0.88%   |
| Samsung SSD 970 EVO Plus 1TB                        | 75        | 0.81%   |
| Samsung SSD 860 EVO 1TB                             | 72        | 0.77%   |
| Samsung SSD 850 EVO 250GB                           | 72        | 0.77%   |
| Kingston SA400S37240G 240GB SSD                     | 72        | 0.77%   |
| Samsung NVMe SSD Drive 1TB                          | 67        | 0.72%   |
| Samsung SSD 970 EVO Plus 500GB                      | 64        | 0.69%   |
| Samsung NVMe SSD Drive 500GB                        | 64        | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB                      | 58        | 0.62%   |
| Crucial CT500MX500SSD1 500GB                        | 56        | 0.6%    |
| Crucial CT1000MX500SSD1 1TB                         | 52        | 0.56%   |
| Toshiba MQ01ABD100 1TB                              | 51        | 0.55%   |
| Kingston SA400S37120G 120GB SSD                     | 51        | 0.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 50        | 0.54%   |
| SanDisk NVMe SSD Drive 1TB                          | 49        | 0.53%   |
| HGST HTS721010A9E630 1TB                            | 49        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB                        | 48        | 0.52%   |
| Samsung NVMe SSD Drive 256GB                        | 48        | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB                      | 47        | 0.51%   |
| Samsung SSD 860 EVO 250GB                           | 46        | 0.49%   |
| SK hynix NVMe SSD Drive 512GB                       | 43        | 0.46%   |
| Kingston SA400S37480G 480GB SSD                     | 43        | 0.46%   |
| Toshiba DT01ACA100 1TB                              | 42        | 0.45%   |
| Seagate ST2000DM006-2DM164 2TB                      | 42        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 39        | 0.42%   |
| Seagate ST500DM002-1BD142 500GB                     | 39        | 0.42%   |
| Seagate ST4000DM004-2CV104 4TB                      | 37        | 0.4%    |
| Samsung SSD 860 QVO 1TB                             | 37        | 0.4%    |
| Toshiba MQ04ABF100 1TB                              | 36        | 0.39%   |
| Samsung SSD 970 EVO 500GB                           | 36        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD                    | 36        | 0.39%   |
| Samsung SSD 840 EVO 250GB                           | 35        | 0.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 34        | 0.37%   |
| Toshiba HDWD110 1TB                                 | 32        | 0.34%   |
| Samsung SSD 970 EVO 1TB                             | 32        | 0.34%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 31        | 0.33%   |
| Crucial CT240BX500SSD1 240GB                        | 30        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1018      | 1530   | 36.31%  |
| WDC                 | 928       | 1401   | 33.1%   |
| Toshiba             | 394       | 511    | 14.05%  |
| HGST                | 146       | 183    | 5.21%   |
| Hitachi             | 139       | 172    | 4.96%   |
| Samsung Electronics | 95        | 128    | 3.39%   |
| Unknown             | 23        | 28     | 0.82%   |
| Apple               | 19        | 19     | 0.68%   |
| Fujitsu             | 8         | 8      | 0.29%   |
| Maxtor              | 5         | 5      | 0.18%   |
| ASMT                | 5         | 5      | 0.18%   |
| USB3.0              | 2         | 3      | 0.07%   |
| Hewlett-Packard     | 2         | 2      | 0.07%   |
| USB                 | 1         | 1      | 0.04%   |
| TrueNAS             | 1         | 1      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| SAGE                | 1         | 1      | 0.04%   |
| RSH-319             | 1         | 1      | 0.04%   |
| PHD 3.0             | 1         | 1      | 0.04%   |
| NeoTech             | 1         | 1      | 0.04%   |
| Maxone              | 1         | 1      | 0.04%   |
| MaxDigital          | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LIO-ORG             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| KESU                | 1         | 1      | 0.04%   |
| Intenso             | 1         | 1      | 0.04%   |
| H/W                 | 1         | 1      | 0.04%   |
| Generic-            | 1         | 1      | 0.04%   |
| Config              | 1         | 1      | 0.04%   |
| ASUSTOR             | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 822       | 1170   | 28.97%  |
| Kingston            | 342       | 432    | 12.05%  |
| Crucial             | 323       | 454    | 11.39%  |
| SanDisk             | 290       | 394    | 10.22%  |
| WDC                 | 193       | 251    | 6.8%    |
| A-DATA Technology   | 83        | 122    | 2.93%   |
| Intel               | 70        | 82     | 2.47%   |
| China               | 49        | 60     | 1.73%   |
| Toshiba             | 47        | 74     | 1.66%   |
| SK hynix            | 45        | 53     | 1.59%   |
| OCZ                 | 45        | 61     | 1.59%   |
| Micron Technology   | 38        | 47     | 1.34%   |
| Transcend           | 37        | 47     | 1.3%    |
| Patriot             | 34        | 40     | 1.2%    |
| SPCC                | 33        | 35     | 1.16%   |
| LITEON              | 31        | 33     | 1.09%   |
| PNY                 | 28        | 34     | 0.99%   |
| Apple               | 24        | 25     | 0.85%   |
| GOODRAM             | 20        | 23     | 0.7%    |
| Corsair             | 19        | 24     | 0.67%   |
| Plextor             | 16        | 17     | 0.56%   |
| LITEONIT            | 13        | 13     | 0.46%   |
| Lexar               | 13        | 16     | 0.46%   |
| KingSpec            | 13        | 14     | 0.46%   |
| Intenso             | 13        | 14     | 0.46%   |
| Hewlett-Packard     | 9         | 9      | 0.32%   |
| Mushkin             | 8         | 13     | 0.28%   |
| Seagate             | 7         | 7      | 0.25%   |
| Netac               | 7         | 7      | 0.25%   |
| Gigabyte Technology | 7         | 7      | 0.25%   |
| TO Exter            | 6         | 7      | 0.21%   |
| Team                | 6         | 6      | 0.21%   |
| FORESEE             | 6         | 8      | 0.21%   |
| ASMT                | 6         | 7      | 0.21%   |
| KingDian            | 5         | 6      | 0.18%   |
| Unknown             | 4         | 4      | 0.14%   |
| AMD                 | 4         | 5      | 0.14%   |
| Teclast             | 3         | 3      | 0.11%   |
| TCSUNBOW            | 3         | 4      | 0.11%   |
| Phison              | 3         | 3      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 2360      | 3770   | 32.84%  |
| HDD     | 2304      | 4015   | 32.06%  |
| NVMe    | 2289      | 3365   | 31.85%  |
| MMC     | 169       | 204    | 2.35%   |
| Unknown | 65        | 73     | 0.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3424      | 7565   | 55.95%  |
| NVMe | 2273      | 3329   | 37.14%  |
| SAS  | 254       | 329    | 4.15%   |
| MMC  | 169       | 204    | 2.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2460      | 3908   | 49.11%  |
| 0.51-1.0   | 1575      | 2298   | 31.44%  |
| 1.01-2.0   | 530       | 797    | 10.58%  |
| 3.01-4.0   | 182       | 305    | 3.63%   |
| 4.01-10.0  | 124       | 243    | 2.48%   |
| 2.01-3.0   | 119       | 185    | 2.38%   |
| 10.01-20.0 | 19        | 49     | 0.38%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1104      | 21.74%  |
| 251-500        | 1096      | 21.58%  |
| 501-1000       | 958       | 18.86%  |
| 1001-2000      | 679       | 13.37%  |
| More than 3000 | 493       | 9.71%   |
| 2001-3000      | 275       | 5.41%   |
| 51-100         | 196       | 3.86%   |
| Unknown        | 132       | 2.6%    |
| 21-50          | 79        | 1.56%   |
| 1-20           | 67        | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 955       | 18.12%  |
| 101-250        | 915       | 17.36%  |
| 21-50          | 736       | 13.96%  |
| 251-500        | 664       | 12.6%   |
| 51-100         | 651       | 12.35%  |
| 501-1000       | 557       | 10.57%  |
| 1001-2000      | 340       | 6.45%   |
| More than 3000 | 186       | 3.53%   |
| 2001-3000      | 135       | 2.56%   |
| Unknown        | 132       | 2.5%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 11        | 13     | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB        | 10        | 10     | 1.72%   |
| HGST HTS721010A9E630 1TB              | 8         | 8      | 1.37%   |
| HGST HTS541010A9E680 1TB              | 7         | 7      | 1.2%    |
| WDC WD20EZRZ-00Z5HB0 2TB              | 6         | 6      | 1.03%   |
| OCZ VERTEX4 256GB SSD                 | 6         | 9      | 1.03%   |
| Kingston SV300S37A120G 120GB SSD      | 6         | 6      | 1.03%   |
| WDC WD5000AAKX-001CA0 500GB           | 5         | 6      | 0.86%   |
| Toshiba MQ01ABD100 1TB                | 5         | 8      | 0.86%   |
| Seagate ST500LT012-1DG142 500GB       | 5         | 5      | 0.86%   |
| Seagate ST31000528AS 1TB              | 5         | 5      | 0.86%   |
| Seagate ST2000DM006-2DM164 2TB        | 5         | 6      | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 5         | 7      | 0.86%   |
| Seagate ST1000LM014-SSHD-8GB          | 5         | 5      | 0.86%   |
| Samsung Electronics SSD 960 EVO 250GB | 5         | 11     | 0.86%   |
| HGST HTS725050A7E630 500GB            | 5         | 5      | 0.86%   |
| HGST HTS545050A7E680 500GB            | 5         | 6      | 0.86%   |
| WDC WD20EARX-00PASB0 2TB              | 4         | 4      | 0.69%   |
| WDC WD20EARS-00MVWB0 2TB              | 4         | 5      | 0.69%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 4         | 4      | 0.69%   |
| Seagate ST9500325AS 500GB             | 4         | 4      | 0.69%   |
| Seagate ST2000LM007-1R8174 2TB        | 4         | 4      | 0.69%   |
| Seagate ST1000LX015-1U7172 1TB        | 4         | 5      | 0.69%   |
| Seagate ST1000DM003-9YN162 1TB        | 4         | 4      | 0.69%   |
| Samsung Electronics HD103SJ 1TB       | 4         | 6      | 0.69%   |
| LITEON CV8-8E128-HP 128GB SSD         | 4         | 4      | 0.69%   |
| WDC WD10EARS-00Y5B1 1TB               | 3         | 4      | 0.52%   |
| Toshiba MK3261GSYN 320GB              | 3         | 3      | 0.52%   |
| Seagate ST9250315AS 250GB             | 3         | 3      | 0.52%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.52%   |
| Seagate ST500LM021-1KJ152 500GB       | 3         | 3      | 0.52%   |
| Seagate ST4000DM004-2CV104 4TB        | 3         | 3      | 0.52%   |
| Seagate ST3500418AS 500GB             | 3         | 4      | 0.52%   |
| Seagate ST3500312CS 500GB             | 3         | 4      | 0.52%   |
| Seagate ST3320620AS 320GB             | 3         | 3      | 0.52%   |
| Seagate ST31000524AS 1TB              | 3         | 3      | 0.52%   |
| Seagate ST2000LX001-1RG174 2TB        | 3         | 3      | 0.52%   |
| Seagate ST2000DM001-1ER164 2TB        | 3         | 3      | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB        | 3         | 3      | 0.52%   |
| SanDisk SD7UB3Q256G1001 256GB SSD     | 3         | 3      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 160       | 188    | 28.52%  |
| WDC                 | 123       | 157    | 21.93%  |
| Samsung Electronics | 48        | 63     | 8.56%   |
| Toshiba             | 41        | 52     | 7.31%   |
| Hitachi             | 35        | 38     | 6.24%   |
| HGST                | 30        | 31     | 5.35%   |
| Kingston            | 18        | 19     | 3.21%   |
| Intel               | 15        | 17     | 2.67%   |
| SanDisk             | 14        | 15     | 2.5%    |
| Crucial             | 13        | 15     | 2.32%   |
| SK hynix            | 10        | 11     | 1.78%   |
| OCZ                 | 10        | 17     | 1.78%   |
| A-DATA Technology   | 6         | 7      | 1.07%   |
| LITEON              | 5         | 5      | 0.89%   |
| Transcend           | 3         | 6      | 0.53%   |
| Hewlett-Packard     | 3         | 3      | 0.53%   |
| Drevo               | 3         | 4      | 0.53%   |
| Corsair             | 3         | 3      | 0.53%   |
| SPCC                | 2         | 3      | 0.36%   |
| Plextor             | 2         | 9      | 0.36%   |
| Patriot             | 2         | 2      | 0.36%   |
| Micron Technology   | 2         | 3      | 0.36%   |
| ASMT                | 2         | 2      | 0.36%   |
| XrayDisk            | 1         | 1      | 0.18%   |
| SSSTC               | 1         | 1      | 0.18%   |
| PNY                 | 1         | 2      | 0.18%   |
| KingSpec            | 1         | 1      | 0.18%   |
| Kingrich            | 1         | 1      | 0.18%   |
| JMicron Technology  | 1         | 1      | 0.18%   |
| INNOVATION IT       | 1         | 1      | 0.18%   |
| Gigabyte Technology | 1         | 1      | 0.18%   |
| China               | 1         | 1      | 0.18%   |
| BAITITON            | 1         | 3      | 0.18%   |
| Apple               | 1         | 1      | 0.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 160       | 188    | 39.7%   |
| WDC                 | 119       | 152    | 29.53%  |
| Toshiba             | 36        | 47     | 8.93%   |
| Hitachi             | 35        | 38     | 8.68%   |
| HGST                | 30        | 31     | 7.44%   |
| Samsung Electronics | 20        | 24     | 4.96%   |
| Hewlett-Packard     | 1         | 1      | 0.25%   |
| ASMT                | 1         | 1      | 0.25%   |
| Apple               | 1         | 1      | 0.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 373       | 483    | 70.78%  |
| SSD  | 124       | 153    | 23.53%  |
| NVMe | 30        | 48     | 5.69%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Kingston SV300S37A120G 120GB SSD                 | 2         | 2      | 20%     |
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1         | 1      | 10%     |
| WDC WD2500BEVT-22ZCT0 250GB                      | 1         | 1      | 10%     |
| Transcend TS128GMTE850 128GB                     | 1         | 1      | 10%     |
| Seagate ST32000644NS 2TB                         | 1         | 1      | 10%     |
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 10%     |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 10%     |
| Samsung Electronics HM251JI 250GB                | 1         | 1      | 10%     |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 10%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 4      | 30%     |
| WDC                 | 2         | 2      | 20%     |
| Kingston            | 2         | 2      | 20%     |
| Transcend           | 1         | 1      | 10%     |
| Seagate             | 1         | 1      | 10%     |
| Phison              | 1         | 1      | 10%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2551      | 5647   | 46.16%  |
| Detected | 2458      | 5085   | 44.48%  |
| Malfunc  | 507       | 684    | 9.17%   |
| Failed   | 10        | 11     | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2797      | 41.22%  |
| AMD                              | 1332      | 19.63%  |
| Samsung Electronics              | 937       | 13.81%  |
| SanDisk                          | 373       | 5.5%    |
| SK hynix                         | 196       | 2.89%   |
| Phison Electronics               | 168       | 2.48%   |
| ASMedia Technology               | 148       | 2.18%   |
| Toshiba America Info Systems     | 121       | 1.78%   |
| Kingston Technology Company      | 101       | 1.49%   |
| Micron Technology                | 79        | 1.16%   |
| ADATA Technology                 | 70        | 1.03%   |
| Silicon Motion                   | 69        | 1.02%   |
| Micron/Crucial Technology        | 68        | 1%      |
| Marvell Technology Group         | 62        | 0.91%   |
| KIOXIA                           | 40        | 0.59%   |
| JMicron Technology               | 34        | 0.5%    |
| Realtek Semiconductor            | 25        | 0.37%   |
| Union Memory (Shenzhen)          | 18        | 0.27%   |
| Lite-On Technology               | 16        | 0.24%   |
| Lenovo                           | 15        | 0.22%   |
| Nvidia                           | 14        | 0.21%   |
| Broadcom / LSI                   | 12        | 0.18%   |
| Apple                            | 12        | 0.18%   |
| LSI Logic / Symbios Logic        | 11        | 0.16%   |
| Adaptec                          | 8         | 0.12%   |
| Silicon Image                    | 7         | 0.1%    |
| Yangtze Memory Technologies      | 6         | 0.09%   |
| VIA Technologies                 | 6         | 0.09%   |
| Solid State Storage Technology   | 6         | 0.09%   |
| Seagate Technology               | 6         | 0.09%   |
| Hewlett-Packard                  | 6         | 0.09%   |
| Silicon Integrated Systems [SiS] | 4         | 0.06%   |
| Shenzhen Longsys Electronics     | 4         | 0.06%   |
| OCZ Technology Group             | 4         | 0.06%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.04%   |
| Unknown                          | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Biwin Storage Technology         | 2         | 0.03%   |
| Promise Technology               | 1         | 0.01%   |
| ATTO Technology                  | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1023      | 13.4%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 601       | 7.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 335       | 4.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 286       | 3.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 188       | 2.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 170       | 2.23%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 162       | 2.12%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 160       | 2.1%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 143       | 1.87%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 143       | 1.87%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 135       | 1.77%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 134       | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                         | 118       | 1.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 112       | 1.47%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 109       | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 108       | 1.41%   |
| Samsung NVMe SSD Controller 980                                                | 102       | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 100       | 1.31%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 99        | 1.3%    |
| Phison E12 NVMe Controller                                                     | 94        | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 94        | 1.23%   |
| Intel SSD 660P Series                                                          | 83        | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 77        | 1.01%   |
| Micron Non-Volatile memory controller                                          | 77        | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 76        | 1%      |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 73        | 0.96%   |
| SK hynix Gold P31 SSD                                                          | 70        | 0.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 69        | 0.9%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 68        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 65        | 0.85%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 59        | 0.77%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 59        | 0.77%   |
| AMD 300 Series Chipset SATA Controller                                         | 59        | 0.77%   |
| Intel SATA Controller [RAID mode]                                              | 58        | 0.76%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 57        | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 55        | 0.72%   |
| AMD X370 Series Chipset SATA Controller                                        | 55        | 0.72%   |
| Intel Volume Management Device NVMe RAID Controller                            | 53        | 0.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 51        | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 48        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3682      | 56.03%  |
| NVMe | 2288      | 34.81%  |
| RAID | 309       | 4.7%    |
| IDE  | 269       | 4.09%   |
| SAS  | 16        | 0.24%   |
| SCSI | 8         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 3280      | 67.41%  |
| AMD    | 1586      | 32.59%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 92        | 1.89%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 90        | 1.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 83        | 1.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 76        | 1.56%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 71        | 1.46%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 68        | 1.39%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 62        | 1.27%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 62        | 1.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 60        | 1.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 59        | 1.21%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 58        | 1.19%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 57        | 1.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 48        | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 43        | 0.88%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 42        | 0.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 41        | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 40        | 0.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 40        | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 39        | 0.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 38        | 0.78%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 37        | 0.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 0.74%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 35        | 0.72%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 35        | 0.72%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 35        | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 34        | 0.7%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 32        | 0.66%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 32        | 0.66%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 32        | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 30        | 0.61%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 30        | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 30        | 0.61%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 29        | 0.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 27        | 0.55%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 27        | 0.55%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 26        | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 26        | 0.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 26        | 0.53%   |
| AMD Ryzen 7 2700 Eight-Core Processor         | 26        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1192      | 24.47%  |
| Intel Core i5           | 1079      | 22.15%  |
| AMD Ryzen 5             | 517       | 10.61%  |
| AMD Ryzen 7             | 469       | 9.63%   |
| Intel Core i3           | 239       | 4.91%   |
| Other                   | 215       | 4.41%   |
| AMD Ryzen 9             | 158       | 3.24%   |
| Intel Celeron           | 120       | 2.46%   |
| Intel Xeon              | 96        | 1.97%   |
| Intel Core 2 Duo        | 85        | 1.75%   |
| AMD FX                  | 78        | 1.6%    |
| Intel Pentium           | 77        | 1.58%   |
| AMD Ryzen 3             | 75        | 1.54%   |
| Intel Core i9           | 55        | 1.13%   |
| AMD Ryzen 7 PRO         | 50        | 1.03%   |
| Intel Atom              | 40        | 0.82%   |
| AMD Ryzen Threadripper  | 26        | 0.53%   |
| AMD A8                  | 25        | 0.51%   |
| Intel Core 2 Quad       | 21        | 0.43%   |
| AMD Ryzen 5 PRO         | 21        | 0.43%   |
| AMD A6                  | 21        | 0.43%   |
| AMD A10                 | 20        | 0.41%   |
| Intel Pentium Dual-Core | 17        | 0.35%   |
| AMD Athlon              | 15        | 0.31%   |
| AMD A4                  | 14        | 0.29%   |
| AMD Phenom II X4        | 13        | 0.27%   |
| Intel Pentium Silver    | 12        | 0.25%   |
| Intel Genuine           | 7         | 0.14%   |
| Intel Core m3           | 7         | 0.14%   |
| Intel Core 2            | 7         | 0.14%   |
| AMD E2                  | 7         | 0.14%   |
| AMD E                   | 7         | 0.14%   |
| AMD Athlon II X2        | 7         | 0.14%   |
| AMD Phenom II X6        | 6         | 0.12%   |
| AMD Athlon II X4        | 6         | 0.12%   |
| AMD Athlon 64 X2        | 6         | 0.12%   |
| Intel Pentium Dual      | 5         | 0.1%    |
| Intel Core m5           | 5         | 0.1%    |
| AMD E1                  | 4         | 0.08%   |
| Intel Pentium 4         | 3         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1912      | 39.23%  |
| 2       | 1306      | 26.8%   |
| 6       | 745       | 15.29%  |
| 8       | 642       | 13.17%  |
| 12      | 109       | 2.24%   |
| 16      | 61        | 1.25%   |
| 1       | 29        | 0.59%   |
| 3       | 24        | 0.49%   |
| 10      | 13        | 0.27%   |
| 24      | 8         | 0.16%   |
| 14      | 7         | 0.14%   |
| 32      | 6         | 0.12%   |
| 64      | 4         | 0.08%   |
| 18      | 2         | 0.04%   |
| Unknown | 2         | 0.04%   |
| 40      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 20      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4840      | 99.47%  |
| 2      | 26        | 0.53%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3825      | 78.48%  |
| 1       | 1047      | 21.48%  |
| Unknown | 2         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4758      | 97.58%  |
| Unknown        | 114       | 2.34%   |
| 32-bit         | 4         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1384      | 27.32%  |
| 0x306a9    | 192       | 3.79%   |
| 0x306c3    | 188       | 3.71%   |
| 0x906ea    | 185       | 3.65%   |
| 0x08701021 | 169       | 3.34%   |
| 0x206a7    | 163       | 3.22%   |
| 0x906e9    | 158       | 3.12%   |
| 0x806ea    | 150       | 2.96%   |
| 0x0800820d | 130       | 2.57%   |
| 0x806ec    | 122       | 2.41%   |
| 0x506e3    | 114       | 2.25%   |
| 0x406e3    | 105       | 2.07%   |
| 0x806e9    | 93        | 1.84%   |
| 0x806c1    | 92        | 1.82%   |
| 0x08701013 | 90        | 1.78%   |
| 0x306d4    | 87        | 1.72%   |
| 0x08108102 | 81        | 1.6%    |
| 0x40651    | 80        | 1.58%   |
| 0x08600106 | 65        | 1.28%   |
| 0x1067a    | 62        | 1.22%   |
| 0x0a50000c | 62        | 1.22%   |
| 0x08108109 | 59        | 1.16%   |
| 0xa0652    | 53        | 1.05%   |
| 0x08001138 | 53        | 1.05%   |
| 0x20655    | 46        | 0.91%   |
| 0x08600104 | 46        | 0.91%   |
| 0x0a201009 | 45        | 0.89%   |
| 0x806eb    | 41        | 0.81%   |
| 0x08600103 | 40        | 0.79%   |
| 0x0810100b | 35        | 0.69%   |
| 0x0a201016 | 34        | 0.67%   |
| 0x906ed    | 31        | 0.61%   |
| 0x706e5    | 29        | 0.57%   |
| 0x06000852 | 26        | 0.51%   |
| 0x08001137 | 24        | 0.47%   |
| 0x406c4    | 23        | 0.45%   |
| 0x706a1    | 21        | 0.41%   |
| 0x506c9    | 21        | 0.41%   |
| 0x10676    | 21        | 0.41%   |
| 0x08101016 | 20        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1124      | 23.05%  |
| Zen 2            | 514       | 10.54%  |
| Haswell          | 393       | 8.06%   |
| Zen+             | 350       | 7.18%   |
| Skylake          | 324       | 6.64%   |
| IvyBridge        | 271       | 5.56%   |
| SandyBridge      | 237       | 4.86%   |
| Zen 3            | 219       | 4.49%   |
| Zen              | 195       | 4%      |
| TigerLake        | 132       | 2.71%   |
| Broadwell        | 127       | 2.6%    |
| CometLake        | 121       | 2.48%   |
| Penryn           | 119       | 2.44%   |
| Unknown          | 99        | 2.03%   |
| Piledriver       | 94        | 1.93%   |
| Westmere         | 80        | 1.64%   |
| Silvermont       | 76        | 1.56%   |
| IceLake          | 70        | 1.44%   |
| K10              | 45        | 0.92%   |
| Goldmont plus    | 41        | 0.84%   |
| Core             | 33        | 0.68%   |
| Excavator        | 32        | 0.66%   |
| Nehalem          | 31        | 0.64%   |
| Goldmont         | 26        | 0.53%   |
| K10 Llano        | 18        | 0.37%   |
| Bonnell          | 17        | 0.35%   |
| Alderlake Hybrid | 16        | 0.33%   |
| Steamroller      | 15        | 0.31%   |
| Bobcat           | 14        | 0.29%   |
| Jaguar           | 10        | 0.21%   |
| Puma             | 9         | 0.18%   |
| K8 Hammer        | 9         | 0.18%   |
| Bulldozer        | 5         | 0.1%    |
| Tremont          | 4         | 0.08%   |
| NetBurst         | 4         | 0.08%   |
| P6               | 2         | 0.04%   |
| K8 & K10 hybrid  | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2517      | 41.73%  |
| Nvidia                           | 1899      | 31.49%  |
| AMD                              | 1588      | 26.33%  |
| Matrox Electronics Systems       | 11        | 0.18%   |
| ASPEED Technology                | 9         | 0.15%   |
| Silicon Integrated Systems [SiS] | 4         | 0.07%   |
| ATI Technologies                 | 2         | 0.03%   |
| VIA Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 251       | 4.08%   |
| Intel UHD Graphics 620                                                                   | 196       | 3.18%   |
| AMD Renoir                                                                               | 182       | 2.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 178       | 2.89%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 162       | 2.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 161       | 2.62%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 160       | 2.6%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 144       | 2.34%   |
| Intel HD Graphics 630                                                                    | 134       | 2.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 125       | 2.03%   |
| Intel HD Graphics 620                                                                    | 121       | 1.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 117       | 1.9%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 111       | 1.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 108       | 1.75%   |
| Intel HD Graphics 5500                                                                   | 94        | 1.53%   |
| AMD Cezanne                                                                              | 90        | 1.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 81        | 1.32%   |
| Intel HD Graphics 530                                                                    | 80        | 1.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 75        | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 74        | 1.2%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 73        | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 70        | 1.14%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 68        | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 66        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 65        | 1.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 64        | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 57        | 0.93%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 55        | 0.89%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 49        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 48        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 48        | 0.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 47        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 45        | 0.73%   |
| AMD Lucienne                                                                             | 45        | 0.73%   |
| Nvidia GP108M [GeForce MX150]                                                            | 44        | 0.71%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                                 | 43        | 0.7%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 41        | 0.67%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 40        | 0.65%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 38        | 0.62%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 37        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1531      | 31.2%   |
| 1 x AMD                  | 1236      | 25.19%  |
| 1 x Nvidia               | 938       | 19.12%  |
| Intel + Nvidia           | 787       | 16.04%  |
| AMD + Nvidia             | 149       | 3.04%   |
| Intel + AMD              | 134       | 2.73%   |
| 2 x AMD                  | 68        | 1.39%   |
| 2 x Nvidia               | 25        | 0.51%   |
| 1 x Matrox               | 9         | 0.18%   |
| Other                    | 5         | 0.1%    |
| 1 x ASPEED               | 5         | 0.1%    |
| 1 x SiS                  | 4         | 0.08%   |
| 2 x Intel                | 3         | 0.06%   |
| AMD + ASPEED             | 3         | 0.06%   |
| Intel + 2 x Nvidia       | 2         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.04%   |
| AMD + Matrox             | 2         | 0.04%   |
| 3 x Nvidia               | 1         | 0.02%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.02%   |
| 1 x VIA                  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3536      | 71.93%  |
| Proprietary | 1337      | 27.2%   |
| Unknown     | 43        | 0.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2628      | 52.5%   |
| 7.01-8.0   | 509       | 10.17%  |
| 1.01-2.0   | 505       | 10.09%  |
| 3.01-4.0   | 415       | 8.29%   |
| 0.01-0.5   | 355       | 7.09%   |
| 0.51-1.0   | 222       | 4.43%   |
| 5.01-6.0   | 201       | 4.02%   |
| 8.01-16.0  | 121       | 2.42%   |
| 2.01-3.0   | 43        | 0.86%   |
| 16.01-24.0 | 4         | 0.08%   |
| 4.01-5.0   | 3         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 685       | 11.43%  |
| Samsung Electronics     | 642       | 10.71%  |
| BOE                     | 496       | 8.28%   |
| LG Display              | 464       | 7.74%   |
| Dell                    | 452       | 7.54%   |
| Chimei Innolux          | 438       | 7.31%   |
| Goldstar                | 376       | 6.28%   |
| Acer                    | 247       | 4.12%   |
| AOC                     | 203       | 3.39%   |
| BenQ                    | 191       | 3.19%   |
| Hewlett-Packard         | 172       | 2.87%   |
| Ancor Communications    | 171       | 2.85%   |
| Sharp                   | 158       | 2.64%   |
| Philips                 | 126       | 2.1%    |
| Lenovo                  | 103       | 1.72%   |
| ViewSonic               | 78        | 1.3%    |
| PANDA                   | 78        | 1.3%    |
| Iiyama                  | 71        | 1.18%   |
| Apple                   | 71        | 1.18%   |
| ASUSTek Computer        | 60        | 1%      |
| InfoVision              | 46        | 0.77%   |
| LG Electronics          | 40        | 0.67%   |
| Sony                    | 34        | 0.57%   |
| Unknown                 | 32        | 0.53%   |
| NEC Computers           | 32        | 0.53%   |
| MSI                     | 27        | 0.45%   |
| Chi Mei Optoelectronics | 27        | 0.45%   |
| Eizo                    | 22        | 0.37%   |
| CSO                     | 22        | 0.37%   |
| Panasonic               | 16        | 0.27%   |
| Fujitsu Siemens         | 16        | 0.27%   |
| Toshiba                 | 15        | 0.25%   |
| Sceptre Tech            | 15        | 0.25%   |
| Gigabyte Technology     | 15        | 0.25%   |
| Vizio                   | 13        | 0.22%   |
| HannStar                | 13        | 0.22%   |
| Valve                   | 10        | 0.17%   |
| Pixio                   | 9         | 0.15%   |
| Medion                  | 9         | 0.15%   |
| Hitachi                 | 9         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 39        | 0.62%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 39        | 0.62%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 29        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 27        | 0.43%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 25        | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 25        | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 22        | 0.35%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 21        | 0.33%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 21        | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 21        | 0.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 20        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 20        | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 19        | 0.3%    |
| Goldstar 27GL850 GSM5B7F 2560x1440 600x340mm 27.2-inch               | 18        | 0.29%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                    | 18        | 0.29%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 17        | 0.27%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                   | 17        | 0.27%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 16        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 15        | 0.24%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                | 15        | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch | 14        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.22%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 14        | 0.22%   |
| Ancor Communications VG248 ACI24A4 1920x1080 530x300mm 24.0-inch     | 14        | 0.22%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 13        | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 13        | 0.21%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 13        | 0.21%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 13        | 0.21%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                      | 13        | 0.21%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 12        | 0.19%   |
| Goldstar LG HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch             | 12        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 12        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 12        | 0.19%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 12        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 12        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch    | 11        | 0.18%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 11        | 0.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 11        | 0.18%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 11        | 0.18%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 11        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2741      | 48.62%  |
| 1366x768 (WXGA)    | 675       | 11.97%  |
| 3840x2160 (4K)     | 465       | 8.25%   |
| 2560x1440 (QHD)    | 427       | 7.57%   |
| 1600x900 (HD+)     | 166       | 2.94%   |
| 1920x1200 (WUXGA)  | 155       | 2.75%   |
| 1680x1050 (WSXGA+) | 122       | 2.16%   |
| 1280x1024 (SXGA)   | 99        | 1.76%   |
| 3440x1440          | 95        | 1.68%   |
| Unknown            | 92        | 1.63%   |
| 1440x900 (WXGA+)   | 78        | 1.38%   |
| 2560x1080          | 68        | 1.21%   |
| 1280x800 (WXGA)    | 51        | 0.9%    |
| 3840x1080          | 37        | 0.66%   |
| 1360x768           | 34        | 0.6%    |
| 2560x1600          | 32        | 0.57%   |
| 2880x1800          | 25        | 0.44%   |
| 3840x2400          | 24        | 0.43%   |
| 3200x1800 (QHD+)   | 18        | 0.32%   |
| 2256x1504          | 18        | 0.32%   |
| 3840x1600          | 17        | 0.3%    |
| 2160x1440          | 16        | 0.28%   |
| 1920x540           | 13        | 0.23%   |
| 2736x1824          | 10        | 0.18%   |
| 7680x2160          | 9         | 0.16%   |
| 3000x2000          | 9         | 0.16%   |
| 1024x768 (XGA)     | 7         | 0.12%   |
| 5120x1440          | 6         | 0.11%   |
| 4480x1440          | 6         | 0.11%   |
| 3072x1920          | 6         | 0.11%   |
| 1920x1280          | 6         | 0.11%   |
| 1280x720 (HD)      | 6         | 0.11%   |
| 1024x600           | 6         | 0.11%   |
| 1600x1200          | 5         | 0.09%   |
| 6400x2160          | 4         | 0.07%   |
| 6400x1440          | 4         | 0.07%   |
| 5760x1080          | 4         | 0.07%   |
| 3840x1200          | 4         | 0.07%   |
| 3286x1080          | 4         | 0.07%   |
| 2240x1400          | 4         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1324      | 22.23%  |
| 27      | 611       | 10.26%  |
| 24      | 600       | 10.07%  |
| 13      | 594       | 9.97%   |
| 14      | 476       | 7.99%   |
| 23      | 417       | 7%      |
| 21      | 343       | 5.76%   |
| Unknown | 281       | 4.72%   |
| 17      | 212       | 3.56%   |
| 34      | 134       | 2.25%   |
| 19      | 125       | 2.1%    |
| 31      | 121       | 2.03%   |
| 12      | 109       | 1.83%   |
| 22      | 82        | 1.38%   |
| 18      | 80        | 1.34%   |
| 20      | 60        | 1.01%   |
| 11      | 40        | 0.67%   |
| 84      | 34        | 0.57%   |
| 25      | 34        | 0.57%   |
| 72      | 30        | 0.5%    |
| 16      | 30        | 0.5%    |
| 54      | 19        | 0.32%   |
| 28      | 19        | 0.32%   |
| 48      | 18        | 0.3%    |
| 26      | 17        | 0.29%   |
| 10      | 15        | 0.25%   |
| 37      | 14        | 0.24%   |
| 32      | 14        | 0.24%   |
| 40      | 11        | 0.18%   |
| 29      | 11        | 0.18%   |
| 46      | 9         | 0.15%   |
| 35      | 7         | 0.12%   |
| 33      | 7         | 0.12%   |
| 49      | 6         | 0.1%    |
| 43      | 5         | 0.08%   |
| 42      | 5         | 0.08%   |
| 39      | 5         | 0.08%   |
| 74      | 4         | 0.07%   |
| 65      | 4         | 0.07%   |
| 57      | 3         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 2089      | 36.39%  |
| 501-600     | 1448      | 25.23%  |
| 401-500     | 607       | 10.57%  |
| 201-300     | 489       | 8.52%   |
| Unknown     | 281       | 4.9%    |
| 351-400     | 266       | 4.63%   |
| 601-700     | 208       | 3.62%   |
| 701-800     | 157       | 2.74%   |
| 1001-1500   | 72        | 1.25%   |
| 1501-2000   | 70        | 1.22%   |
| 801-900     | 39        | 0.68%   |
| 901-1000    | 12        | 0.21%   |
| 101-200     | 2         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3984      | 76.99%  |
| 16/10   | 540       | 10.43%  |
| Unknown | 242       | 4.68%   |
| 21/9    | 166       | 3.21%   |
| 5/4     | 101       | 1.95%   |
| 3/2     | 83        | 1.6%    |
| 4/3     | 25        | 0.48%   |
| 32/9    | 24        | 0.46%   |
| 2.65    | 3         | 0.06%   |
| 0.62    | 2         | 0.04%   |
| 3.40    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.96    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.57    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1321      | 22.57%  |
| 201-250        | 1119      | 19.12%  |
| 81-90          | 795       | 13.58%  |
| 301-350        | 626       | 10.69%  |
| 351-500        | 297       | 5.07%   |
| Unknown        | 281       | 4.8%    |
| 71-80          | 275       | 4.7%    |
| 151-200        | 245       | 4.19%   |
| 251-300        | 234       | 4%      |
| 121-130        | 147       | 2.51%   |
| 141-150        | 113       | 1.93%   |
| More than 1000 | 109       | 1.86%   |
| 61-70          | 100       | 1.71%   |
| 501-1000       | 77        | 1.32%   |
| 51-60          | 41        | 0.7%    |
| 111-120        | 22        | 0.38%   |
| 131-140        | 19        | 0.32%   |
| 91-100         | 17        | 0.29%   |
| 41-50          | 15        | 0.26%   |
| 1-40           | 1         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1705      | 30.28%  |
| 121-160       | 1676      | 29.76%  |
| 101-120       | 1252      | 22.23%  |
| 161-240       | 431       | 7.65%   |
| Unknown       | 281       | 4.99%   |
| More than 240 | 199       | 3.53%   |
| 1-50          | 87        | 1.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3608      | 72.3%   |
| 2     | 1092      | 21.88%  |
| 3     | 182       | 3.65%   |
| 0     | 92        | 1.84%   |
| 4     | 14        | 0.28%   |
| 5     | 2         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2770      | 38.14%  |
| Realtek Semiconductor             | 2620      | 36.07%  |
| Qualcomm Atheros                  | 748       | 10.3%   |
| Broadcom                          | 266       | 3.66%   |
| Ralink Technology                 | 66        | 0.91%   |
| MediaTek                          | 66        | 0.91%   |
| TP-Link                           | 65        | 0.89%   |
| Microsoft                         | 52        | 0.72%   |
| Marvell Technology Group          | 45        | 0.62%   |
| Broadcom Limited                  | 45        | 0.62%   |
| Ralink                            | 41        | 0.56%   |
| Lenovo                            | 35        | 0.48%   |
| ASIX Electronics                  | 31        | 0.43%   |
| Sierra Wireless                   | 25        | 0.34%   |
| Ericsson Business Mobile Networks | 24        | 0.33%   |
| Aquantia                          | 21        | 0.29%   |
| Samsung Electronics               | 20        | 0.28%   |
| Xiaomi                            | 19        | 0.26%   |
| DisplayLink                       | 19        | 0.26%   |
| D-Link                            | 19        | 0.26%   |
| Qualcomm                          | 18        | 0.25%   |
| NetGear                           | 18        | 0.25%   |
| Hewlett-Packard                   | 14        | 0.19%   |
| Qualcomm Atheros Communications   | 13        | 0.18%   |
| Apple                             | 13        | 0.18%   |
| Nvidia                            | 12        | 0.17%   |
| Huawei Technologies               | 12        | 0.17%   |
| Dell                              | 12        | 0.17%   |
| Microchip Technology              | 10        | 0.14%   |
| Google                            | 10        | 0.14%   |
| Mellanox Technologies             | 9         | 0.12%   |
| Linksys                           | 7         | 0.1%    |
| D-Link System                     | 7         | 0.1%    |
| Cypress Semiconductor             | 7         | 0.1%    |
| JMicron Technology                | 6         | 0.08%   |
| Edimax Technology                 | 6         | 0.08%   |
| ASUSTek Computer                  | 6         | 0.08%   |
| FIBOCOM                           | 5         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.06%   |
| Oculus VR                         | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1901      | 22.22%  |
| Intel Wi-Fi 6 AX200                                               | 442       | 5.17%   |
| Intel I211 Gigabit Network Connection                             | 316       | 3.69%   |
| Intel Wireless 8265 / 8275                                        | 216       | 2.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 208       | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 150       | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 149       | 1.74%   |
| Intel Ethernet Connection (2) I219-V                              | 145       | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 142       | 1.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 132       | 1.54%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 131       | 1.53%   |
| Realtek RTL8125 2.5GbE Controller                                 | 124       | 1.45%   |
| Intel Wireless 8260                                               | 116       | 1.36%   |
| Intel Wireless 7265                                               | 116       | 1.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 106       | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 95        | 1.11%   |
| Intel Wi-Fi 6 AX201                                               | 92        | 1.08%   |
| Intel Wireless 7260                                               | 87        | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 86        | 1.01%   |
| Intel Wireless-AC 9260                                            | 85        | 0.99%   |
| Intel Wireless 3165                                               | 81        | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 80        | 0.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 78        | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 77        | 0.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 74        | 0.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 74        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 69        | 0.81%   |
| Intel Ethernet Connection (7) I219-V                              | 65        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 65        | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 63        | 0.74%   |
| Intel Ethernet Connection I217-LM                                 | 56        | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 53        | 0.62%   |
| Intel Ethernet Controller I225-V                                  | 48        | 0.56%   |
| Intel Ethernet Connection (4) I219-V                              | 48        | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 47        | 0.55%   |
| Intel Wireless 3160                                               | 47        | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 45        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                              | 43        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 0.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 37        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2147      | 54.6%   |
| Qualcomm Atheros                  | 576       | 14.65%  |
| Realtek Semiconductor             | 530       | 13.48%  |
| Broadcom                          | 204       | 5.19%   |
| Ralink Technology                 | 66        | 1.68%   |
| MediaTek                          | 62        | 1.58%   |
| TP-Link                           | 55        | 1.4%    |
| Microsoft                         | 47        | 1.2%    |
| Ralink                            | 41        | 1.04%   |
| Broadcom Limited                  | 34        | 0.86%   |
| Sierra Wireless                   | 25        | 0.64%   |
| NetGear                           | 16        | 0.41%   |
| D-Link                            | 16        | 0.41%   |
| Qualcomm                          | 15        | 0.38%   |
| Marvell Technology Group          | 14        | 0.36%   |
| Qualcomm Atheros Communications   | 13        | 0.33%   |
| Ericsson Business Mobile Networks | 10        | 0.25%   |
| Linksys                           | 7         | 0.18%   |
| Edimax Technology                 | 6         | 0.15%   |
| Dell                              | 6         | 0.15%   |
| ASUSTek Computer                  | 6         | 0.15%   |
| Hewlett-Packard                   | 5         | 0.13%   |
| FIBOCOM                           | 5         | 0.13%   |
| AVM                               | 4         | 0.1%    |
| Wilocity                          | 3         | 0.08%   |
| Mercucys                          | 3         | 0.08%   |
| D-Link System                     | 3         | 0.08%   |
| Belkin Components                 | 3         | 0.08%   |
| Xiaomi                            | 2         | 0.05%   |
| Micro Star International          | 2         | 0.05%   |
| IMC Networks                      | 2         | 0.05%   |
| ZyXEL Communications              | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| Sagem                             | 1         | 0.03%   |
| AboCom Systems                    | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 442       | 11.19%  |
| Intel Wireless 8265 / 8275                                     | 216       | 5.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 142       | 3.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 132       | 3.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 131       | 3.32%   |
| Intel Wireless 8260                                            | 116       | 2.94%   |
| Intel Wireless 7265                                            | 116       | 2.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 106       | 2.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 95        | 2.41%   |
| Intel Wi-Fi 6 AX201                                            | 92        | 2.33%   |
| Intel Wireless 7260                                            | 87        | 2.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 86        | 2.18%   |
| Intel Wireless-AC 9260                                         | 85        | 2.15%   |
| Intel Wireless 3165                                            | 81        | 2.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 80        | 2.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 78        | 1.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 77        | 1.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 74        | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 74        | 1.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 69        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 65        | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 63        | 1.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 53        | 1.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 47        | 1.19%   |
| Intel Wireless 3160                                            | 47        | 1.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 37        | 0.94%   |
| Realtek 802.11ac NIC                                           | 37        | 0.94%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 36        | 0.91%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 34        | 0.86%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 33        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 32        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 30        | 0.76%   |
| Microsoft Xbox 360 Wireless Adapter                            | 27        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 26        | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 24        | 0.61%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 24        | 0.61%   |
| Intel Centrino Advanced-N 6235                                 | 23        | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                  | 23        | 0.58%   |
| Ralink MT7601U Wireless Adapter                                | 22        | 0.56%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 21        | 0.53%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                        | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Realtek Semiconductor                         | 2391      | 54.11%  |
| Intel                                         | 1398      | 31.64%  |
| Qualcomm Atheros                              | 223       | 5.05%   |
| Broadcom                                      | 97        | 2.2%    |
| Lenovo                                        | 35        | 0.79%   |
| Marvell Technology Group                      | 31        | 0.7%    |
| ASIX Electronics                              | 31        | 0.7%    |
| Aquantia                                      | 21        | 0.48%   |
| Samsung Electronics                           | 20        | 0.45%   |
| DisplayLink                                   | 19        | 0.43%   |
| Xiaomi                                        | 17        | 0.38%   |
| Apple                                         | 13        | 0.29%   |
| Nvidia                                        | 12        | 0.27%   |
| Broadcom Limited                              | 11        | 0.25%   |
| TP-Link                                       | 10        | 0.23%   |
| Mellanox Technologies                         | 9         | 0.2%    |
| Google                                        | 9         | 0.2%    |
| Cypress Semiconductor                         | 7         | 0.16%   |
| JMicron Technology                            | 6         | 0.14%   |
| Huawei Technologies                           | 6         | 0.14%   |
| Microsoft                                     | 5         | 0.11%   |
| Silicon Integrated Systems [SiS]              | 4         | 0.09%   |
| MediaTek                                      | 4         | 0.09%   |
| D-Link System                                 | 4         | 0.09%   |
| Qualcomm                                      | 3         | 0.07%   |
| OPPO Electronics                              | 3         | 0.07%   |
| ICS Advent                                    | 3         | 0.07%   |
| Hewlett-Packard                               | 3         | 0.07%   |
| D-Link                                        | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM                    | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)                 | 2         | 0.05%   |
| NetGear                                       | 2         | 0.05%   |
| Motorola PCS                                  | 2         | 0.05%   |
| HMD Global                                    | 2         | 0.05%   |
| VIA Technologies                              | 1         | 0.02%   |
| Standard Microsystems [SMC]                   | 1         | 0.02%   |
| QNAP System                                   | 1         | 0.02%   |
| Netchip Technology                            | 1         | 0.02%   |
| Linux 2.6.35.3-571-gcca29a0 with fsl-usb2-udc | 1         | 0.02%   |
| LG Electronics                                | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1901      | 41.96%  |
| Intel I211 Gigabit Network Connection                             | 316       | 6.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 208       | 4.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 150       | 3.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 149       | 3.29%   |
| Intel Ethernet Connection (2) I219-V                              | 145       | 3.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 124       | 2.74%   |
| Intel Ethernet Connection (7) I219-V                              | 65        | 1.43%   |
| Intel Ethernet Connection I217-LM                                 | 56        | 1.24%   |
| Intel Ethernet Controller I225-V                                  | 48        | 1.06%   |
| Intel Ethernet Connection (4) I219-V                              | 48        | 1.06%   |
| Intel Ethernet Connection (6) I219-V                              | 45        | 0.99%   |
| Intel Ethernet Connection (2) I218-V                              | 43        | 0.95%   |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 36        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 36        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 33        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                             | 32        | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 32        | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 31        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 30        | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 26        | 0.57%   |
| Intel I210 Gigabit Network Connection                             | 25        | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 25        | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 24        | 0.53%   |
| Intel 82577LM Gigabit Network Connection                          | 24        | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 22        | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                             | 21        | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 20        | 0.44%   |
| Intel 82574L Gigabit Network Connection                           | 20        | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 19        | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 18        | 0.4%    |
| Intel Ethernet Connection I219-V                                  | 17        | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 16        | 0.35%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 15        | 0.33%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.29%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.29%   |
| Intel Ethernet Connection (5) I219-LM                             | 12        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4127      | 51.95%  |
| WiFi     | 3743      | 47.12%  |
| Modem    | 66        | 0.83%   |
| Unknown  | 8         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2857      | 55.71%  |
| Ethernet | 2269      | 44.25%  |
| Modem    | 2         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2611      | 53.49%  |
| 1     | 2065      | 42.31%  |
| 3     | 145       | 2.97%   |
| 0     | 38        | 0.78%   |
| 4     | 15        | 0.31%   |
| 6     | 4         | 0.08%   |
| 5     | 3         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4246      | 86.09%  |
| Yes  | 686       | 13.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1851      | 54.8%   |
| Realtek Semiconductor           | 275       | 8.14%   |
| Cambridge Silicon Radio         | 255       | 7.55%   |
| Qualcomm Atheros Communications | 218       | 6.45%   |
| Broadcom                        | 146       | 4.32%   |
| Lite-On Technology              | 111       | 3.29%   |
| IMC Networks                    | 111       | 3.29%   |
| ASUSTek Computer                | 91        | 2.69%   |
| Foxconn / Hon Hai               | 74        | 2.19%   |
| Apple                           | 71        | 2.1%    |
| Realtek                         | 31        | 0.92%   |
| Dell                            | 27        | 0.8%    |
| Hewlett-Packard                 | 15        | 0.44%   |
| Marvell Semiconductor           | 13        | 0.38%   |
| HTC (High Tech Computer)        | 13        | 0.38%   |
| Toshiba                         | 9         | 0.27%   |
| Ralink                          | 9         | 0.27%   |
| MediaTek                        | 9         | 0.27%   |
| TP-Link                         | 6         | 0.18%   |
| Foxconn International           | 6         | 0.18%   |
| Edimax Technology               | 6         | 0.18%   |
| USI                             | 3         | 0.09%   |
| Micro Star International        | 3         | 0.09%   |
| Integrated System Solution      | 3         | 0.09%   |
| Dynex                           | 3         | 0.09%   |
| Chicony Electronics             | 3         | 0.09%   |
| Unknown                         | 2         | 0.06%   |
| Ralink Technology               | 2         | 0.06%   |
| Belkin Components               | 2         | 0.06%   |
| Askey Computer                  | 2         | 0.06%   |
| Alps Electric                   | 2         | 0.06%   |
| Syntek                          | 1         | 0.03%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Roper                           | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Corsair                         | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 639       | 18.88%  |
| Intel AX200 Bluetooth                                                | 418       | 12.35%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 255       | 7.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 253       | 7.47%   |
| Intel AX201 Bluetooth                                                | 233       | 6.88%   |
| Realtek Bluetooth Radio                                              | 173       | 5.11%   |
| Qualcomm Atheros  Bluetooth Device                                   | 113       | 3.34%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 102       | 3.01%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 80        | 2.36%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 70        | 2.07%   |
| Intel AX210 Bluetooth                                                | 69        | 2.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 47        | 1.39%   |
| Lite-On Bluetooth Device                                             | 44        | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                        | 41        | 1.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 37        | 1.09%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 37        | 1.09%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 37        | 1.09%   |
| IMC Networks Bluetooth Radio                                         | 36        | 1.06%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 35        | 1.03%   |
| Realtek Bluetooth Radio                                              | 31        | 0.92%   |
| IMC Networks Bluetooth Device                                        | 31        | 0.92%   |
| Apple Bluetooth USB Host Controller                                  | 30        | 0.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 29        | 0.86%   |
| IMC Networks Wireless_Device                                         | 25        | 0.74%   |
| Apple Bluetooth Host Controller                                      | 25        | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 23        | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 22        | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 19        | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 18        | 0.53%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 16        | 0.47%   |
| Foxconn / Hon Hai Wireless_Device                                    | 15        | 0.44%   |
| Intel Bluetooth Device                                               | 14        | 0.41%   |
| ASUS Bluetooth Radio                                                 | 14        | 0.41%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 13        | 0.38%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 12        | 0.35%   |
| Realtek RTL8723B Bluetooth                                           | 11        | 0.32%   |
| Dell DW375 Bluetooth Module                                          | 11        | 0.32%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 11        | 0.32%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 10        | 0.3%    |
| Lite-On Wireless_Device                                              | 10        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3176      | 41.38%  |
| AMD                                  | 1845      | 24.04%  |
| Nvidia                               | 1408      | 18.34%  |
| C-Media Electronics                  | 181       | 2.36%   |
| Logitech                             | 87        | 1.13%   |
| Kingston Technology                  | 58        | 0.76%   |
| Focusrite-Novation                   | 57        | 0.74%   |
| Texas Instruments                    | 51        | 0.66%   |
| SteelSeries ApS                      | 47        | 0.61%   |
| Realtek Semiconductor                | 44        | 0.57%   |
| JMTek                                | 44        | 0.57%   |
| Creative Labs                        | 39        | 0.51%   |
| Razer USA                            | 38        | 0.5%    |
| Lenovo                               | 37        | 0.48%   |
| Creative Technology                  | 34        | 0.44%   |
| Corsair                              | 33        | 0.43%   |
| Blue Microphones                     | 29        | 0.38%   |
| Samson Technologies                  | 21        | 0.27%   |
| Valve Software                       | 18        | 0.23%   |
| GYROCOM C&C                          | 17        | 0.22%   |
| GN Netcom                            | 17        | 0.22%   |
| Apple                                | 17        | 0.22%   |
| BEHRINGER International              | 15        | 0.2%    |
| Yamaha                               | 14        | 0.18%   |
| Generalplus Technology               | 14        | 0.18%   |
| SAVITECH                             | 13        | 0.17%   |
| Plantronics                          | 13        | 0.17%   |
| ASUSTek Computer                     | 13        | 0.17%   |
| XMOS                                 | 11        | 0.14%   |
| Sony                                 | 10        | 0.13%   |
| RODE Microphones                     | 10        | 0.13%   |
| Audio-Technica                       | 10        | 0.13%   |
| FiiO Electronics Technology          | 9         | 0.12%   |
| Dell                                 | 9         | 0.12%   |
| Sennheiser Communications            | 8         | 0.1%    |
| Microsoft                            | 7         | 0.09%   |
| M-Audio                              | 7         | 0.09%   |
| Giga-Byte Technology                 | 7         | 0.09%   |
| Cambridge Silicon Radio              | 7         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 6         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 578       | 6.28%   |
| Intel Sunrise Point-LP HD Audio                                            | 474       | 5.15%   |
| AMD Starship/Matisse HD Audio Controller                                   | 426       | 4.63%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 282       | 3.06%   |
| Intel Cannon Lake PCH cAVS                                                 | 274       | 2.98%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 269       | 2.92%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 261       | 2.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 251       | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 218       | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 210       | 2.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 196       | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 194       | 2.11%   |
| Nvidia GP107GL High Definition Audio Controller                            | 162       | 1.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 157       | 1.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 147       | 1.6%    |
| Intel 200 Series PCH HD Audio                                              | 147       | 1.6%    |
| Nvidia GP104 High Definition Audio Controller                              | 145       | 1.57%   |
| AMD Navi 10 HDMI Audio                                                     | 142       | 1.54%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 132       | 1.43%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 128       | 1.39%   |
| Nvidia GP106 High Definition Audio Controller                              | 118       | 1.28%   |
| Intel Broadwell-U Audio Controller                                         | 112       | 1.22%   |
| Intel Haswell-ULT HD Audio Controller                                      | 109       | 1.18%   |
| Intel 8 Series HD Audio Controller                                         | 109       | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 107       | 1.16%   |
| Intel CM238 HD Audio Controller                                            | 104       | 1.13%   |
| Nvidia TU106 High Definition Audio Controller                              | 102       | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                              | 92        | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 91        | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 89        | 0.97%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 89        | 0.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 84        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                               | 80        | 0.87%   |
| Nvidia TU104 HD Audio Controller                                           | 77        | 0.84%   |
| AMD FCH Azalia Controller                                                  | 73        | 0.79%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 72        | 0.78%   |
| Nvidia GM204 High Definition Audio Controller                              | 68        | 0.74%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 68        | 0.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 68        | 0.74%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 61        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 841       | 20.35%  |
| SK hynix            | 631       | 15.27%  |
| Kingston            | 533       | 12.9%   |
| Corsair             | 434       | 10.5%   |
| Micron Technology   | 377       | 9.12%   |
| Crucial             | 330       | 7.99%   |
| G.Skill             | 273       | 6.61%   |
| Unknown             | 227       | 5.49%   |
| A-DATA Technology   | 80        | 1.94%   |
| Ramaxel Technology  | 72        | 1.74%   |
| Elpida              | 43        | 1.04%   |
| Patriot             | 38        | 0.92%   |
| Team                | 32        | 0.77%   |
| Goodram             | 21        | 0.51%   |
| Unknown (ABCD)      | 18        | 0.44%   |
| Nanya Technology    | 18        | 0.44%   |
| Smart               | 17        | 0.41%   |
| Transcend           | 13        | 0.31%   |
| PNY                 | 10        | 0.24%   |
| Goldkey             | 9         | 0.22%   |
| AMD                 | 9         | 0.22%   |
| Unknown             | 8         | 0.19%   |
| Apacer              | 6         | 0.15%   |
| Teikon              | 5         | 0.12%   |
| Smart Brazil        | 5         | 0.12%   |
| GeIL                | 5         | 0.12%   |
| Silicon Power       | 4         | 0.1%    |
| Neo Forza           | 4         | 0.1%    |
| Golden Empire       | 4         | 0.1%    |
| Wilk Elektronik     | 3         | 0.07%   |
| V-GeN               | 3         | 0.07%   |
| KLEVV               | 3         | 0.07%   |
| Kingmax             | 3         | 0.07%   |
| Avant               | 3         | 0.07%   |
| 48spaces            | 3         | 0.07%   |
| Thermaltake         | 2         | 0.05%   |
| Kllisre             | 2         | 0.05%   |
| High Bridge         | 2         | 0.05%   |
| Hewlett-Packard     | 2         | 0.05%   |
| Axiom               | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 56        | 1.26%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 54        | 1.22%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 51        | 1.15%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 45        | 1.02%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 45        | 1.02%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 37        | 0.84%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 32        | 0.72%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 23        | 0.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 22        | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 20        | 0.45%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 20        | 0.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 19        | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 19        | 0.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 19        | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 0.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 19        | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.43%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 19        | 0.43%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                | 19        | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.41%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 18        | 0.41%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 17        | 0.38%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.38%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 17        | 0.38%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 17        | 0.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 16        | 0.36%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 16        | 0.36%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 16        | 0.36%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3200MT/s              | 16        | 0.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 15        | 0.34%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 15        | 0.34%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 15        | 0.34%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 14        | 0.32%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 13        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 2229      | 62.77%  |
| DDR3    | 916       | 25.8%   |
| LPDDR4  | 116       | 3.27%   |
| LPDDR3  | 111       | 3.13%   |
| Unknown | 54        | 1.52%   |
| DDR2    | 47        | 1.32%   |
| SDRAM   | 46        | 1.3%    |
| LPDDR5  | 14        | 0.39%   |
| DDR     | 10        | 0.28%   |
| DDR5    | 7         | 0.2%    |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1836      | 51.82%  |
| DIMM         | 1412      | 39.85%  |
| Row Of Chips | 256       | 7.23%   |
| Chip         | 28        | 0.79%   |
| Unknown      | 8         | 0.23%   |
| RIMM         | 2         | 0.06%   |
| FB-DIMM      | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1761      | 45.84%  |
| 4096  | 930       | 24.21%  |
| 16384 | 683       | 17.78%  |
| 2048  | 264       | 6.87%   |
| 32768 | 150       | 3.9%    |
| 1024  | 47        | 1.22%   |
| 512   | 6         | 0.16%   |
| 65536 | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 675       | 17.3%   |
| 3200    | 608       | 15.58%  |
| 1600    | 607       | 15.56%  |
| 2400    | 353       | 9.05%   |
| 2133    | 232       | 5.95%   |
| 3600    | 207       | 5.3%    |
| 1333    | 169       | 4.33%   |
| 1867    | 102       | 2.61%   |
| 3466    | 88        | 2.26%   |
| 1334    | 80        | 2.05%   |
| 3266    | 64        | 1.64%   |
| 2933    | 60        | 1.54%   |
| 4267    | 59        | 1.51%   |
| 3000    | 50        | 1.28%   |
| 3400    | 40        | 1.03%   |
| 667     | 40        | 1.03%   |
| 3733    | 36        | 0.92%   |
| Unknown | 28        | 0.72%   |
| 1067    | 27        | 0.69%   |
| 2800    | 26        | 0.67%   |
| 1866    | 26        | 0.67%   |
| 1066    | 25        | 0.64%   |
| 2666    | 23        | 0.59%   |
| 3800    | 21        | 0.54%   |
| 800     | 20        | 0.51%   |
| 8400    | 14        | 0.36%   |
| 6400    | 14        | 0.36%   |
| 4199    | 14        | 0.36%   |
| 4266    | 12        | 0.31%   |
| 4800    | 10        | 0.26%   |
| 3333    | 10        | 0.26%   |
| 400     | 10        | 0.26%   |
| 3666    | 9         | 0.23%   |
| 2733    | 9         | 0.23%   |
| 2048    | 9         | 0.23%   |
| 4000    | 8         | 0.21%   |
| 3066    | 8         | 0.21%   |
| 1800    | 8         | 0.21%   |
| 3866    | 7         | 0.18%   |
| 3151    | 7         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 27        | 35.53%  |
| Brother Industries       | 15        | 19.74%  |
| Samsung Electronics      | 12        | 15.79%  |
| Canon                    | 8         | 10.53%  |
| Seiko Epson              | 3         | 3.95%   |
| Prolific Technology      | 3         | 3.95%   |
| Dymo-CoStar              | 3         | 3.95%   |
| Zebra                    | 1         | 1.32%   |
| STMicroelectronics       | 1         | 1.32%   |
| Ricoh                    | 1         | 1.32%   |
| Magic Control Technology | 1         | 1.32%   |
| Fuji Xerox               | 1         | 1.32%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung M2070 Series                                      | 3         | 3.95%   |
| Prolific PL2305 Parallel Port                             | 3         | 3.95%   |
| HP DeskJet 2130 series                                    | 3         | 3.95%   |
| Samsung SCX-4100 Scanner                                  | 2         | 2.63%   |
| HP Officejet Pro 8100                                     | 2         | 2.63%   |
| HP LaserJet P2015 series                                  | 2         | 2.63%   |
| HP Deskjet 3050 J610 series                               | 2         | 2.63%   |
| HP DeskJet 2620 All-in-One Printer                        | 2         | 2.63%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 2.63%   |
| Brother Printer                                           | 2         | 2.63%   |
| Brother HL-5370DW series                                  | 2         | 2.63%   |
| Zebra LP2844 Printer                                      | 1         | 1.32%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.32%   |
| Seiko Epson XP-7100 Series                                | 1         | 1.32%   |
| Seiko Epson WF-2530 Series                                | 1         | 1.32%   |
| Seiko Epson Printer                                       | 1         | 1.32%   |
| Samsung SCX-4200 series                                   | 1         | 1.32%   |
| Samsung SCX-3200 Series                                   | 1         | 1.32%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.32%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1.32%   |
| Samsung M2020 Series                                      | 1         | 1.32%   |
| Samsung CLP-325 Color Laser Printer                       | 1         | 1.32%   |
| Samsung C1860 Series                                      | 1         | 1.32%   |
| Ricoh SP 150SU                                            | 1         | 1.32%   |
| Magic Control BAY-3U1S1P Parallel Port                    | 1         | 1.32%   |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1.32%   |
| HP Officejet 4500 G510g-m                                 | 1         | 1.32%   |
| HP LaserJet P1005                                         | 1         | 1.32%   |
| HP LaserJet M14-M17                                       | 1         | 1.32%   |
| HP LaserJet 1320                                          | 1         | 1.32%   |
| HP LaserJet 1200                                          | 1         | 1.32%   |
| HP LaserJet 1022                                          | 1         | 1.32%   |
| HP LaserJet 1020                                          | 1         | 1.32%   |
| HP LaserJet 1018                                          | 1         | 1.32%   |
| HP LaserJet 1012                                          | 1         | 1.32%   |
| HP ENVY 5540 series                                       | 1         | 1.32%   |
| HP ENVY 5000 series                                       | 1         | 1.32%   |
| HP DeskJet F4200 series                                   | 1         | 1.32%   |
| HP DeskJet 840c                                           | 1         | 1.32%   |
| HP DeskJet 4100 series                                    | 1         | 1.32%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 8         | 61.54%  |
| Seiko Epson    | 3         | 23.08%  |
| Mustek Systems | 2         | 15.38%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan N650U/N656U                                  | 2         | 15.38%  |
| Canon CanoScan LiDE 200                                     | 2         | 15.38%  |
| Seiko Epson GT-X820 [Perfection V600 Photo]                 | 1         | 7.69%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]     | 1         | 7.69%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 7.69%   |
| Mustek Systems ScanExpress 1200 UB                          | 1         | 7.69%   |
| Mustek Systems BearPaw 1200 CU Plus                         | 1         | 7.69%   |
| Canon CanoScan LiDE 60                                      | 1         | 7.69%   |
| Canon CanoScan LIDE 25                                      | 1         | 7.69%   |
| Canon CanoScan LiDE 210                                     | 1         | 7.69%   |
| Canon CanoScan LiDE 110                                     | 1         | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 624       | 20.18%  |
| IMC Networks                           | 323       | 10.45%  |
| Logitech                               | 280       | 9.06%   |
| Microdia                               | 260       | 8.41%   |
| Acer                                   | 260       | 8.41%   |
| Realtek Semiconductor                  | 219       | 7.08%   |
| Quanta                                 | 156       | 5.05%   |
| Sunplus Innovation Technology          | 139       | 4.5%    |
| Cheng Uei Precision Industry (Foxlink) | 105       | 3.4%    |
| Lite-On Technology                     | 82        | 2.65%   |
| Syntek                                 | 80        | 2.59%   |
| Apple                                  | 71        | 2.3%    |
| Suyin                                  | 53        | 1.71%   |
| Microsoft                              | 40        | 1.29%   |
| Silicon Motion                         | 38        | 1.23%   |
| Samsung Electronics                    | 38        | 1.23%   |
| Alcor Micro                            | 33        | 1.07%   |
| Luxvisions Innotech Limited            | 30        | 0.97%   |
| Lenovo                                 | 22        | 0.71%   |
| Z-Star Microelectronics                | 20        | 0.65%   |
| Valve Software                         | 16        | 0.52%   |
| MacroSilicon                           | 16        | 0.52%   |
| Ricoh                                  | 10        | 0.32%   |
| ARC International                      | 10        | 0.32%   |
| Unknown                                | 9         | 0.29%   |
| Razer USA                              | 9         | 0.29%   |
| ALi                                    | 9         | 0.29%   |
| Primax Electronics                     | 8         | 0.26%   |
| KYE Systems (Mouse Systems)            | 8         | 0.26%   |
| Importek                               | 8         | 0.26%   |
| Sonix Technology                       | 7         | 0.23%   |
| Generalplus Technology                 | 7         | 0.23%   |
| SunplusIT                              | 6         | 0.19%   |
| LG Electronics                         | 6         | 0.19%   |
| Creative Technology                    | 6         | 0.19%   |
| Jieli Technology                       | 5         | 0.16%   |
| Huawei Technologies                    | 4         | 0.13%   |
| Google                                 | 4         | 0.13%   |
| Cubeternet                             | 4         | 0.13%   |
| YGTek                                  | 3         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 179       | 5.72%   |
| Microdia Integrated_Webcam_HD                                              | 129       | 4.12%   |
| IMC Networks Integrated Camera                                             | 116       | 3.7%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 90        | 2.87%   |
| Acer Integrated Camera                                                     | 90        | 2.87%   |
| Realtek Integrated_Webcam_HD                                               | 80        | 2.55%   |
| Chicony HD WebCam                                                          | 74        | 2.36%   |
| Logitech HD Pro Webcam C920                                                | 61        | 1.95%   |
| Sunplus Integrated_Webcam_HD                                               | 54        | 1.72%   |
| Logitech Webcam C270                                                       | 50        | 1.6%    |
| Syntek Integrated Camera                                                   | 46        | 1.47%   |
| Samsung Galaxy A5 (MTP)                                                    | 38        | 1.21%   |
| Lite-On Integrated Camera                                                  | 38        | 1.21%   |
| Quanta HD User Facing                                                      | 37        | 1.18%   |
| Acer HD Webcam                                                             | 31        | 0.99%   |
| Acer SunplusIT Integrated Camera                                           | 30        | 0.96%   |
| Chicony Integrated Camera (1280x720@30)                                    | 28        | 0.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 27        | 0.86%   |
| Chicony HP Wide Vision HD Camera                                           | 27        | 0.86%   |
| Chicony USB2.0 Camera                                                      | 26        | 0.83%   |
| Apple FaceTime HD Camera (Built-in)                                        | 26        | 0.83%   |
| Logitech C922 Pro Stream Webcam                                            | 22        | 0.7%    |
| Chicony HP HD Camera                                                       | 22        | 0.7%    |
| Apple iPhone5/5C/5S/6                                                      | 22        | 0.7%    |
| Chicony EasyCamera                                                         | 21        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 21        | 0.67%   |
| Microdia Integrated Webcam                                                 | 20        | 0.64%   |
| Chicony HD User Facing                                                     | 20        | 0.64%   |
| Acer Lenovo EasyCamera                                                     | 20        | 0.64%   |
| Realtek USB Camera                                                         | 19        | 0.61%   |
| Realtek Integrated Webcam                                                  | 19        | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                                               | 19        | 0.61%   |
| Syntek Lenovo EasyCamera                                                   | 18        | 0.57%   |
| Logitech Webcam C310                                                       | 18        | 0.57%   |
| IMC Networks ov9734_azurewave_camera                                       | 18        | 0.57%   |
| Sunplus HD WebCam                                                          | 17        | 0.54%   |
| Quanta VGA WebCam                                                          | 17        | 0.54%   |
| Microdia Webcam Vitade AF                                                  | 17        | 0.54%   |
| Acer EasyCamera                                                            | 17        | 0.54%   |
| Valve Software 3D Camera                                                   | 16        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 255       | 38.99%  |
| Validity Sensors                   | 174       | 26.61%  |
| Shenzhen Goodix Technology         | 111       | 16.97%  |
| Elan Microelectronics              | 34        | 5.2%    |
| LighTuning Technology              | 25        | 3.82%   |
| Upek                               | 23        | 3.52%   |
| AuthenTec                          | 19        | 2.91%   |
| STMicroelectronics                 | 8         | 1.22%   |
| Samsung Electronics                | 3         | 0.46%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.15%   |
| Microsoft                          | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 97        | 14.83%  |
| Unknown                                                                    | 57        | 8.72%   |
| Shenzhen Goodix  Fingerprint Device                                        | 54        | 8.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 37        | 5.66%   |
| Shenzhen Goodix Fingerprint Reader                                         | 36        | 5.5%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 32        | 4.89%   |
| Elan ELAN:Fingerprint                                                      | 26        | 3.98%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 3.67%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 21        | 3.21%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 3.21%   |
| Shenzhen Goodix FingerPrint                                                | 21        | 3.21%   |
| Synaptics  WBDI                                                            | 20        | 3.06%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.6%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 2.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 15        | 2.29%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 15        | 2.29%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 2.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 12        | 1.83%   |
| Validity Sensors VFS491                                                    | 11        | 1.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 11        | 1.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 1.68%   |
| AuthenTec AES2810                                                          | 10        | 1.53%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.38%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 1.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 1.07%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.92%   |
| Elan ELAN:ARM-M4                                                           | 6         | 0.92%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.61%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 0.46%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.46%   |
| Synaptics WBDI Device                                                      | 3         | 0.46%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.31%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.31%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.31%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.31%   |
| Samsung Fingerprint Device                                                 | 2         | 0.31%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.31%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.31%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 104       | 39.69%  |
| Broadcom                          | 91        | 34.73%  |
| Upek                              | 16        | 6.11%   |
| Lenovo                            | 10        | 3.82%   |
| Clay Logic                        | 7         | 2.67%   |
| Yubico.com                        | 5         | 1.91%   |
| O2 Micro                          | 5         | 1.91%   |
| Advanced Card Systems             | 5         | 1.91%   |
| SCM Microsystems                  | 4         | 1.53%   |
| Reiner SCT Kartensysteme          | 4         | 1.53%   |
| Gemalto (was Gemplus)             | 3         | 1.15%   |
| Aladdin Knowledge Systems         | 2         | 0.76%   |
| VASCO Data Security International | 1         | 0.38%   |
| OmniKey                           | 1         | 0.38%   |
| Hewlett-Packard                   | 1         | 0.38%   |
| Fujitsu Siemens Computers         | 1         | 0.38%   |
| Aladdin R.D.                      | 1         | 0.38%   |
| Aktiv                             | 1         | 0.38%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 102       | 38.93%  |
| Broadcom 5880                                                                | 26        | 9.92%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 23        | 8.78%   |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 7.63%   |
| Broadcom 58200                                                               | 20        | 7.63%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 6.11%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 3.82%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 1.91%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 1.53%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 1.15%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 3         | 1.15%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.76%   |
| Reiner SCT Kartensysteme cyberJack one                                       | 2         | 0.76%   |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.76%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.76%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.76%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.38%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.38%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.38%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.38%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.38%   |
| OmniKey Smart Card Reader USB                                                | 1         | 0.38%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.38%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.38%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.38%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.38%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.38%   |
| Fujitsu Siemens Computers Keyboard KB100 SCR eSIG                            | 1         | 0.38%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.38%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.38%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.38%   |
| Aktiv Rutoken lite                                                           | 1         | 0.38%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.38%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.38%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3513      | 70.68%  |
| 1     | 1158      | 23.3%   |
| 2     | 234       | 4.71%   |
| 3     | 55        | 1.11%   |
| 4     | 8         | 0.16%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 641       | 36.15%  |
| Graphics card            | 310       | 17.48%  |
| Chipcard                 | 227       | 12.8%   |
| Net/wireless             | 154       | 8.69%   |
| Multimedia controller    | 110       | 6.2%    |
| Camera                   | 100       | 5.64%   |
| Unassigned class         | 47        | 2.65%   |
| Communication controller | 37        | 2.09%   |
| Bluetooth                | 35        | 1.97%   |
| Sound                    | 28        | 1.58%   |
| Net/ethernet             | 20        | 1.13%   |
| Network                  | 17        | 0.96%   |
| Storage                  | 16        | 0.9%    |
| Card reader              | 11        | 0.62%   |
| Modem                    | 4         | 0.23%   |
| Dvb card                 | 4         | 0.23%   |
| Wireless                 | 2         | 0.11%   |
| Storage/raid             | 2         | 0.11%   |
| Storage/nvme             | 2         | 0.11%   |
| Storage/ide              | 2         | 0.11%   |
| Tv card                  | 1         | 0.06%   |
| Storage/ata              | 1         | 0.06%   |
| Flash memory             | 1         | 0.06%   |
| Firewire controller      | 1         | 0.06%   |

