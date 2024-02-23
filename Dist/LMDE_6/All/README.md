LMDE 6 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 6.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_6/Desktop/README.md) and [notebooks](/Dist/LMDE_6/Notebook/README.md).

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

Total: 270

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | Q87M-D2H                    | Desktop     | [4c5e48c75f](https://linux-hardware.org/?probe=4c5e48c75f) | Feb 02, 2024 |
| Inventec      | DQ Class A02                | Desktop     | [4cb447dae2](https://linux-hardware.org/?probe=4cb447dae2) | Feb 02, 2024 |
| MSI           | Thin GF63 12HW              | Notebook    | [b5b16477c3](https://linux-hardware.org/?probe=b5b16477c3) | Feb 02, 2024 |
| Dell          | Latitude 7280               | Notebook    | [c94b45b8f4](https://linux-hardware.org/?probe=c94b45b8f4) | Feb 02, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [78ef1fbd6c](https://linux-hardware.org/?probe=78ef1fbd6c) | Jan 31, 2024 |
| Medion        | TJ4125                      | Desktop     | [2705de4986](https://linux-hardware.org/?probe=2705de4986) | Jan 31, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [78a08c286e](https://linux-hardware.org/?probe=78a08c286e) | Jan 30, 2024 |
| Acer          | Aspire E1-572G              | Notebook    | [a23343d32d](https://linux-hardware.org/?probe=a23343d32d) | Jan 30, 2024 |
| MSI           | MS-7345                     | Desktop     | [3453f85c21](https://linux-hardware.org/?probe=3453f85c21) | Jan 30, 2024 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [429541ce17](https://linux-hardware.org/?probe=429541ce17) | Jan 29, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [c7a52fe756](https://linux-hardware.org/?probe=c7a52fe756) | Jan 29, 2024 |
| HP            | 805D                        | Desktop     | [81113f9b0d](https://linux-hardware.org/?probe=81113f9b0d) | Jan 29, 2024 |
| Fanless Mi... | Rev JSL62                   | Mini pc     | [f0e620b88a](https://linux-hardware.org/?probe=f0e620b88a) | Jan 29, 2024 |
| Medion        | P7612                       | Notebook    | [875d083de0](https://linux-hardware.org/?probe=875d083de0) | Jan 29, 2024 |
| HP            | Compaq 615                  | Notebook    | [907b046dda](https://linux-hardware.org/?probe=907b046dda) | Jan 29, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [79381fe2e8](https://linux-hardware.org/?probe=79381fe2e8) | Jan 29, 2024 |
| Lenovo        | ThinkPad X230 2325SU3       | Notebook    | [664fffd47e](https://linux-hardware.org/?probe=664fffd47e) | Jan 29, 2024 |
| Lenovo        | ThinkPad X230 2325SU3       | Notebook    | [cc42f2d5e4](https://linux-hardware.org/?probe=cc42f2d5e4) | Jan 29, 2024 |
| ASUSTek       | PRIME X670-P                | Desktop     | [08b5799cfd](https://linux-hardware.org/?probe=08b5799cfd) | Jan 27, 2024 |
| Acer          | Aspire E5-575               | Notebook    | [6764984d72](https://linux-hardware.org/?probe=6764984d72) | Jan 26, 2024 |
| MSI           | MAG B560 TORPEDO            | Desktop     | [30954e841f](https://linux-hardware.org/?probe=30954e841f) | Jan 26, 2024 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [56bd222ae5](https://linux-hardware.org/?probe=56bd222ae5) | Jan 24, 2024 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [7cd83ff81e](https://linux-hardware.org/?probe=7cd83ff81e) | Jan 23, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ed52617ade](https://linux-hardware.org/?probe=ed52617ade) | Jan 23, 2024 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [b8a8ce8fc0](https://linux-hardware.org/?probe=b8a8ce8fc0) | Jan 23, 2024 |
| Dell          | Latitude D610               | Notebook    | [b1f24babef](https://linux-hardware.org/?probe=b1f24babef) | Jan 22, 2024 |
| ASRock        | Z690 Pro RS                 | Desktop     | [4083a31da9](https://linux-hardware.org/?probe=4083a31da9) | Jan 21, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [61f93014cf](https://linux-hardware.org/?probe=61f93014cf) | Jan 21, 2024 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [52318f5ae6](https://linux-hardware.org/?probe=52318f5ae6) | Jan 20, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [b2d419f7dc](https://linux-hardware.org/?probe=b2d419f7dc) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [d40c2f48dd](https://linux-hardware.org/?probe=d40c2f48dd) | Jan 18, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [323c35348f](https://linux-hardware.org/?probe=323c35348f) | Jan 16, 2024 |
| ASUSTek       | P7P55D-E                    | Desktop     | [bb8785aa08](https://linux-hardware.org/?probe=bb8785aa08) | Jan 15, 2024 |
| Lenovo        | ThinkPad X61 76754BJ        | Notebook    | [42f1380b4e](https://linux-hardware.org/?probe=42f1380b4e) | Jan 15, 2024 |
| MSI           | MEG X670E ACE               | Desktop     | [08ee758712](https://linux-hardware.org/?probe=08ee758712) | Jan 15, 2024 |
| ASRock        | Z97 Pro4                    | Desktop     | [e3ef5ae05b](https://linux-hardware.org/?probe=e3ef5ae05b) | Jan 14, 2024 |
| Lenovo        | ThinkPad T400 6474EU3       | Notebook    | [0d9d328c8d](https://linux-hardware.org/?probe=0d9d328c8d) | Jan 14, 2024 |
| Dell          | Inspiron 15-3552            | Notebook    | [2a9bde666e](https://linux-hardware.org/?probe=2a9bde666e) | Jan 13, 2024 |
| Dell          | Inspiron 15-3552            | Notebook    | [87e8f38d79](https://linux-hardware.org/?probe=87e8f38d79) | Jan 13, 2024 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [516c8f6f9c](https://linux-hardware.org/?probe=516c8f6f9c) | Jan 13, 2024 |
| Gigabyte      | GA-78LMT-S2P 78LMT2         | Desktop     | [b81e3342c6](https://linux-hardware.org/?probe=b81e3342c6) | Jan 13, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [70dedc5c9d](https://linux-hardware.org/?probe=70dedc5c9d) | Jan 12, 2024 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [a358114f21](https://linux-hardware.org/?probe=a358114f21) | Jan 12, 2024 |
| Lenovo        | ThinkPad X1 Carbon 34601... | Notebook    | [bdfab62447](https://linux-hardware.org/?probe=bdfab62447) | Jan 12, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6b5cc546b5](https://linux-hardware.org/?probe=6b5cc546b5) | Jan 12, 2024 |
| MSI           | Z390-A PRO                  | Desktop     | [538119eb86](https://linux-hardware.org/?probe=538119eb86) | Jan 11, 2024 |
| MSI           | B350M BAZOOKA               | Desktop     | [fab33560f3](https://linux-hardware.org/?probe=fab33560f3) | Jan 10, 2024 |
| VALE          | Notebook Classic C171V      | Notebook    | [8ecf376e28](https://linux-hardware.org/?probe=8ecf376e28) | Jan 10, 2024 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [c9096376d8](https://linux-hardware.org/?probe=c9096376d8) | Jan 09, 2024 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [702eef24cf](https://linux-hardware.org/?probe=702eef24cf) | Jan 09, 2024 |
| Lenovo        | IdeaPad Y530                | Notebook    | [344509ac97](https://linux-hardware.org/?probe=344509ac97) | Jan 08, 2024 |
| Notebook      | W35xSTQ_370ST               | Notebook    | [a2f670a8f0](https://linux-hardware.org/?probe=a2f670a8f0) | Jan 08, 2024 |
| Dell          | Latitude E6320              | Notebook    | [75e562d28a](https://linux-hardware.org/?probe=75e562d28a) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [2c36dcaa22](https://linux-hardware.org/?probe=2c36dcaa22) | Jan 07, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [e2e58f59b7](https://linux-hardware.org/?probe=e2e58f59b7) | Jan 06, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ff9686f03c](https://linux-hardware.org/?probe=ff9686f03c) | Jan 06, 2024 |
| Google        | Swanky                      | Notebook    | [1b6173f1e0](https://linux-hardware.org/?probe=1b6173f1e0) | Jan 05, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [de8842c748](https://linux-hardware.org/?probe=de8842c748) | Jan 04, 2024 |
| Apple         | MacBookAir7,1               | Notebook    | [5596e9e3a7](https://linux-hardware.org/?probe=5596e9e3a7) | Jan 04, 2024 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [a04f45ddfb](https://linux-hardware.org/?probe=a04f45ddfb) | Jan 03, 2024 |
| Dell          | Latitude E6320              | Notebook    | [e6fec1134a](https://linux-hardware.org/?probe=e6fec1134a) | Jan 03, 2024 |
| Medion        | TJ4125                      | Desktop     | [ca0e4105c2](https://linux-hardware.org/?probe=ca0e4105c2) | Jan 02, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [26f77fa950](https://linux-hardware.org/?probe=26f77fa950) | Jan 02, 2024 |
| Dell          | Latitude E6320              | Notebook    | [1833dcdd43](https://linux-hardware.org/?probe=1833dcdd43) | Dec 31, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [9e622b4006](https://linux-hardware.org/?probe=9e622b4006) | Dec 31, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [0f440edfb5](https://linux-hardware.org/?probe=0f440edfb5) | Dec 31, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [edbe61f4fa](https://linux-hardware.org/?probe=edbe61f4fa) | Dec 31, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [fc3a637b52](https://linux-hardware.org/?probe=fc3a637b52) | Dec 31, 2023 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [86a499d322](https://linux-hardware.org/?probe=86a499d322) | Dec 30, 2023 |
| Sony          | VGN-FW21E                   | Notebook    | [52ff803e03](https://linux-hardware.org/?probe=52ff803e03) | Dec 29, 2023 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [c2a3ce3927](https://linux-hardware.org/?probe=c2a3ce3927) | Dec 29, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [05e0faf913](https://linux-hardware.org/?probe=05e0faf913) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [242659bbee](https://linux-hardware.org/?probe=242659bbee) | Dec 27, 2023 |
| Dell          | 0RW199                      | Desktop     | [906719d239](https://linux-hardware.org/?probe=906719d239) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3673afc1cd](https://linux-hardware.org/?probe=3673afc1cd) | Dec 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [9b570f14f6](https://linux-hardware.org/?probe=9b570f14f6) | Dec 26, 2023 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [d3e1c0dbdc](https://linux-hardware.org/?probe=d3e1c0dbdc) | Dec 25, 2023 |
| HP            | 090Ch                       | Desktop     | [06e9f893bc](https://linux-hardware.org/?probe=06e9f893bc) | Dec 25, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4b2ed8b976](https://linux-hardware.org/?probe=4b2ed8b976) | Dec 23, 2023 |
| ASUSTek       | X99-A II                    | Desktop     | [37e4430c0e](https://linux-hardware.org/?probe=37e4430c0e) | Dec 23, 2023 |
| ASRock        | Z97 Pro4                    | Desktop     | [f8e2df67b1](https://linux-hardware.org/?probe=f8e2df67b1) | Dec 23, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [db8c00daf3](https://linux-hardware.org/?probe=db8c00daf3) | Dec 22, 2023 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [942da4e853](https://linux-hardware.org/?probe=942da4e853) | Dec 20, 2023 |
| Lenovo        | 317C NOK                    | Desktop     | [87064e6d98](https://linux-hardware.org/?probe=87064e6d98) | Dec 20, 2023 |
| Medion        | TJ4125                      | Desktop     | [8fce958467](https://linux-hardware.org/?probe=8fce958467) | Dec 20, 2023 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [a1f4076586](https://linux-hardware.org/?probe=a1f4076586) | Dec 19, 2023 |
| Sony          | SVE1511A1EW                 | Notebook    | [2f0fde3487](https://linux-hardware.org/?probe=2f0fde3487) | Dec 19, 2023 |
| Sony          | SVE1511A1EW                 | Notebook    | [e5531ecc00](https://linux-hardware.org/?probe=e5531ecc00) | Dec 19, 2023 |
| Medion        | TJ4125                      | Desktop     | [c7eeb77279](https://linux-hardware.org/?probe=c7eeb77279) | Dec 18, 2023 |
| Irbis         | NB264                       | Notebook    | [8c32d8fb0b](https://linux-hardware.org/?probe=8c32d8fb0b) | Dec 18, 2023 |
| Medion        | E6214                       | Notebook    | [1bc5839854](https://linux-hardware.org/?probe=1bc5839854) | Dec 17, 2023 |
| Medion        | E6214                       | Notebook    | [5269b6e576](https://linux-hardware.org/?probe=5269b6e576) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [378b82ce2f](https://linux-hardware.org/?probe=378b82ce2f) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [e7f9b37ee3](https://linux-hardware.org/?probe=e7f9b37ee3) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [935f688c90](https://linux-hardware.org/?probe=935f688c90) | Dec 17, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f53d129b3d](https://linux-hardware.org/?probe=f53d129b3d) | Dec 17, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6b3cd841db](https://linux-hardware.org/?probe=6b3cd841db) | Dec 17, 2023 |
| Medion        | TJ4125                      | Desktop     | [7556d73046](https://linux-hardware.org/?probe=7556d73046) | Dec 17, 2023 |
| Dell          | Latitude E6430              | Notebook    | [13af5c2dc4](https://linux-hardware.org/?probe=13af5c2dc4) | Dec 17, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [0b4a9d3a4e](https://linux-hardware.org/?probe=0b4a9d3a4e) | Dec 16, 2023 |
| Lenovo        | ThinkPad X230 2325BA3       | Notebook    | [1c573f00c0](https://linux-hardware.org/?probe=1c573f00c0) | Dec 16, 2023 |
| Medion        | E6214                       | Notebook    | [806be57bd5](https://linux-hardware.org/?probe=806be57bd5) | Dec 16, 2023 |
| Apple         | Mac-F4208EAA PVT            | Mini pc     | [973e09e6eb](https://linux-hardware.org/?probe=973e09e6eb) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8f7755936c](https://linux-hardware.org/?probe=8f7755936c) | Dec 14, 2023 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [91ec51ebf5](https://linux-hardware.org/?probe=91ec51ebf5) | Dec 12, 2023 |
| Lenovo        | 30BB SDK0J40709 WIN 3259... | All in one  | [9d9d96201b](https://linux-hardware.org/?probe=9d9d96201b) | Dec 12, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [e71cda8b04](https://linux-hardware.org/?probe=e71cda8b04) | Dec 12, 2023 |
| Acer          | Aspire Z3-615               | All in one  | [c3d3cc14e8](https://linux-hardware.org/?probe=c3d3cc14e8) | Dec 12, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [3184d3c38b](https://linux-hardware.org/?probe=3184d3c38b) | Dec 11, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [78562df77d](https://linux-hardware.org/?probe=78562df77d) | Dec 11, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [205a5c1696](https://linux-hardware.org/?probe=205a5c1696) | Dec 10, 2023 |
| Dell          | Precision 3550              | Notebook    | [0235a02831](https://linux-hardware.org/?probe=0235a02831) | Dec 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [71de71e3f4](https://linux-hardware.org/?probe=71de71e3f4) | Dec 10, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [64b0038221](https://linux-hardware.org/?probe=64b0038221) | Dec 10, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [408ad7dd06](https://linux-hardware.org/?probe=408ad7dd06) | Dec 10, 2023 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [eaedc51abc](https://linux-hardware.org/?probe=eaedc51abc) | Dec 10, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [0d970bde9a](https://linux-hardware.org/?probe=0d970bde9a) | Dec 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4525b7e30c](https://linux-hardware.org/?probe=4525b7e30c) | Dec 09, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [42a7acfe4b](https://linux-hardware.org/?probe=42a7acfe4b) | Dec 09, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b553ec2266](https://linux-hardware.org/?probe=b553ec2266) | Dec 08, 2023 |
| ASUSTek       | Rampage III Extreme         | Desktop     | [d4d934c9be](https://linux-hardware.org/?probe=d4d934c9be) | Dec 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [7144bda606](https://linux-hardware.org/?probe=7144bda606) | Dec 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [748534900a](https://linux-hardware.org/?probe=748534900a) | Dec 04, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6fca6c7335](https://linux-hardware.org/?probe=6fca6c7335) | Dec 03, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [e6fd8cf7f1](https://linux-hardware.org/?probe=e6fd8cf7f1) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [e33632af4f](https://linux-hardware.org/?probe=e33632af4f) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [f86dd8a709](https://linux-hardware.org/?probe=f86dd8a709) | Dec 02, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [b53f576b27](https://linux-hardware.org/?probe=b53f576b27) | Dec 02, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [75dcedad41](https://linux-hardware.org/?probe=75dcedad41) | Nov 30, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [8a91691d0b](https://linux-hardware.org/?probe=8a91691d0b) | Nov 30, 2023 |
| Alienware     | 17                          | Notebook    | [1c23fa6051](https://linux-hardware.org/?probe=1c23fa6051) | Nov 29, 2023 |
| LETSUNG       | Unknown                     | Notebook    | [bfbf7dfeaa](https://linux-hardware.org/?probe=bfbf7dfeaa) | Nov 27, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [9fa48c41da](https://linux-hardware.org/?probe=9fa48c41da) | Nov 27, 2023 |
| Lenovo        | ThinkPad W541 20EGS07C01    | Notebook    | [c05294f5f5](https://linux-hardware.org/?probe=c05294f5f5) | Nov 26, 2023 |
| Gigabyte      | B560M D3H                   | Desktop     | [8a894da286](https://linux-hardware.org/?probe=8a894da286) | Nov 26, 2023 |
| Lenovo        | ThinkPad W541 20EGS07C01    | Notebook    | [dc051898f5](https://linux-hardware.org/?probe=dc051898f5) | Nov 26, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [1a31182007](https://linux-hardware.org/?probe=1a31182007) | Nov 26, 2023 |
| Medion        | E6214                       | Notebook    | [83d5d32938](https://linux-hardware.org/?probe=83d5d32938) | Nov 26, 2023 |
| Shenzhen M... | F7BRC                       | Desktop     | [9ff2c76737](https://linux-hardware.org/?probe=9ff2c76737) | Nov 26, 2023 |
| HP            | Pavilion TS Sleekbook 15    | Notebook    | [3a3a75aa94](https://linux-hardware.org/?probe=3a3a75aa94) | Nov 26, 2023 |
| MSI           | MAG B760M MORTAR WIFI DD... | Desktop     | [b11fcf42c2](https://linux-hardware.org/?probe=b11fcf42c2) | Nov 25, 2023 |
| HP            | Pavilion TS Sleekbook 15    | Notebook    | [9c76ca1014](https://linux-hardware.org/?probe=9c76ca1014) | Nov 25, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7fce567d9e](https://linux-hardware.org/?probe=7fce567d9e) | Nov 25, 2023 |
| HP            | 245 G7                      | Notebook    | [42ee8e6975](https://linux-hardware.org/?probe=42ee8e6975) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [8131bff614](https://linux-hardware.org/?probe=8131bff614) | Nov 25, 2023 |
| Medion        | TJ4125                      | Desktop     | [512206df27](https://linux-hardware.org/?probe=512206df27) | Nov 24, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [81d1db42ea](https://linux-hardware.org/?probe=81d1db42ea) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a8b99ab7f3](https://linux-hardware.org/?probe=a8b99ab7f3) | Nov 23, 2023 |
| HP            | 829A                        | Mini pc     | [b8edb25d4c](https://linux-hardware.org/?probe=b8edb25d4c) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [af55920808](https://linux-hardware.org/?probe=af55920808) | Nov 23, 2023 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [b564a39ed5](https://linux-hardware.org/?probe=b564a39ed5) | Nov 22, 2023 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [ce96501574](https://linux-hardware.org/?probe=ce96501574) | Nov 22, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [a0f12099c5](https://linux-hardware.org/?probe=a0f12099c5) | Nov 22, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [9f4829b792](https://linux-hardware.org/?probe=9f4829b792) | Nov 22, 2023 |
| HP            | 8158 A01                    | Mini pc     | [5132b64a8a](https://linux-hardware.org/?probe=5132b64a8a) | Nov 22, 2023 |
| Soyo          | SY-N3150L Quad              | Desktop     | [7fd72fcced](https://linux-hardware.org/?probe=7fd72fcced) | Nov 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [b12a3ea8d6](https://linux-hardware.org/?probe=b12a3ea8d6) | Nov 21, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7239efa8fe](https://linux-hardware.org/?probe=7239efa8fe) | Nov 20, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [085623428e](https://linux-hardware.org/?probe=085623428e) | Nov 19, 2023 |
| Acer          | Aspire X3400                | Desktop     | [26cedbdbde](https://linux-hardware.org/?probe=26cedbdbde) | Nov 19, 2023 |
| Acer          | Aspire X3400                | Desktop     | [83890ec21c](https://linux-hardware.org/?probe=83890ec21c) | Nov 19, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [e65cf40bcb](https://linux-hardware.org/?probe=e65cf40bcb) | Nov 19, 2023 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [672ed26145](https://linux-hardware.org/?probe=672ed26145) | Nov 17, 2023 |
| ASUSTek       | EB1035                      | All in one  | [c42d11074a](https://linux-hardware.org/?probe=c42d11074a) | Nov 17, 2023 |
| ASUSTek       | EB1035                      | All in one  | [04b01b0be5](https://linux-hardware.org/?probe=04b01b0be5) | Nov 17, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [f6d6d655df](https://linux-hardware.org/?probe=f6d6d655df) | Nov 16, 2023 |
| HP            | 8265                        | Desktop     | [d3f5c1d6ce](https://linux-hardware.org/?probe=d3f5c1d6ce) | Nov 15, 2023 |
| Toshiba       | Satellite Pro L100          | Notebook    | [429902b4e5](https://linux-hardware.org/?probe=429902b4e5) | Nov 15, 2023 |
| Acer          | AOA110                      | Notebook    | [a6b7a86c67](https://linux-hardware.org/?probe=a6b7a86c67) | Nov 14, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [087220685a](https://linux-hardware.org/?probe=087220685a) | Nov 14, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [c4b486ecb1](https://linux-hardware.org/?probe=c4b486ecb1) | Nov 13, 2023 |
| Toshiba       | Satellite Pro L100          | Notebook    | [ade0fd48dc](https://linux-hardware.org/?probe=ade0fd48dc) | Nov 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [c00b5e7c16](https://linux-hardware.org/?probe=c00b5e7c16) | Nov 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [e45cab7f2c](https://linux-hardware.org/?probe=e45cab7f2c) | Nov 12, 2023 |
| Medion        | TJ4125                      | Desktop     | [1e0f7cdf34](https://linux-hardware.org/?probe=1e0f7cdf34) | Nov 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [feaa9f3eac](https://linux-hardware.org/?probe=feaa9f3eac) | Nov 11, 2023 |
| Medion        | TJ4125                      | Desktop     | [ab37177769](https://linux-hardware.org/?probe=ab37177769) | Nov 10, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [80bba409c5](https://linux-hardware.org/?probe=80bba409c5) | Nov 10, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [54073a3305](https://linux-hardware.org/?probe=54073a3305) | Nov 09, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [4dbd78f68d](https://linux-hardware.org/?probe=4dbd78f68d) | Nov 09, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [c594d3daae](https://linux-hardware.org/?probe=c594d3daae) | Nov 09, 2023 |
| IBM           | ThinkPad T40 23736G4        | Notebook    | [5c1d0bcbb2](https://linux-hardware.org/?probe=5c1d0bcbb2) | Nov 08, 2023 |
| Dell          | 0HH807                      | Desktop     | [300ee3d8f5](https://linux-hardware.org/?probe=300ee3d8f5) | Nov 08, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [8d5332d643](https://linux-hardware.org/?probe=8d5332d643) | Nov 07, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [f51da852ca](https://linux-hardware.org/?probe=f51da852ca) | Nov 07, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [35b7b043ff](https://linux-hardware.org/?probe=35b7b043ff) | Nov 07, 2023 |
| Google        | Akemi                       | Notebook    | [f19a7fb862](https://linux-hardware.org/?probe=f19a7fb862) | Nov 06, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [d86018bbd8](https://linux-hardware.org/?probe=d86018bbd8) | Nov 06, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [bfe1423965](https://linux-hardware.org/?probe=bfe1423965) | Nov 06, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [39e8a692ae](https://linux-hardware.org/?probe=39e8a692ae) | Nov 05, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [62a888f71c](https://linux-hardware.org/?probe=62a888f71c) | Nov 05, 2023 |
| Medion        | TJ4125                      | Desktop     | [65a059325e](https://linux-hardware.org/?probe=65a059325e) | Nov 05, 2023 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [ef6c15830d](https://linux-hardware.org/?probe=ef6c15830d) | Nov 05, 2023 |
| Google        | Akemi                       | Notebook    | [350f53d84a](https://linux-hardware.org/?probe=350f53d84a) | Nov 05, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [b77c593ace](https://linux-hardware.org/?probe=b77c593ace) | Nov 04, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1c80cbda1c](https://linux-hardware.org/?probe=1c80cbda1c) | Nov 04, 2023 |
| Medion        | E6214                       | Notebook    | [776be82bf6](https://linux-hardware.org/?probe=776be82bf6) | Nov 04, 2023 |
| HP            | 246 G6 Notebook PC          | Notebook    | [cd997e5a97](https://linux-hardware.org/?probe=cd997e5a97) | Nov 03, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [b73e7cf536](https://linux-hardware.org/?probe=b73e7cf536) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a0c7507d6d](https://linux-hardware.org/?probe=a0c7507d6d) | Nov 03, 2023 |
| Google        | Akemi                       | Notebook    | [20ec65943c](https://linux-hardware.org/?probe=20ec65943c) | Nov 02, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [ae6c835796](https://linux-hardware.org/?probe=ae6c835796) | Nov 02, 2023 |
| ASUSTek       | X456UR                      | Notebook    | [9a0a4dfd02](https://linux-hardware.org/?probe=9a0a4dfd02) | Nov 02, 2023 |
| ASRock        | Z97 Pro4                    | Desktop     | [6fa2a70f99](https://linux-hardware.org/?probe=6fa2a70f99) | Nov 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [826dc000ff](https://linux-hardware.org/?probe=826dc000ff) | Nov 01, 2023 |
| HP            | Notebook                    | Notebook    | [b1491b73ae](https://linux-hardware.org/?probe=b1491b73ae) | Oct 31, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [1107919053](https://linux-hardware.org/?probe=1107919053) | Oct 31, 2023 |
| HP            | 18EB                        | Desktop     | [83596ab9d9](https://linux-hardware.org/?probe=83596ab9d9) | Oct 31, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [e741e073e0](https://linux-hardware.org/?probe=e741e073e0) | Oct 30, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [810297d46b](https://linux-hardware.org/?probe=810297d46b) | Oct 30, 2023 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [aed94a16c1](https://linux-hardware.org/?probe=aed94a16c1) | Oct 30, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [082e5b7e0b](https://linux-hardware.org/?probe=082e5b7e0b) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [1267d6df00](https://linux-hardware.org/?probe=1267d6df00) | Oct 29, 2023 |
| Trigkey       | Green G4 10                 | Desktop     | [bb72f6af02](https://linux-hardware.org/?probe=bb72f6af02) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9f0452aba6](https://linux-hardware.org/?probe=9f0452aba6) | Oct 29, 2023 |
| Lenovo        | ThinkPad T420 4236W1Y       | Notebook    | [2ff5cba7a7](https://linux-hardware.org/?probe=2ff5cba7a7) | Oct 29, 2023 |
| Medion        | TJ4125                      | Desktop     | [f791cf88cb](https://linux-hardware.org/?probe=f791cf88cb) | Oct 27, 2023 |
| Dell          | 0HH807                      | Desktop     | [7f15d65c22](https://linux-hardware.org/?probe=7f15d65c22) | Oct 27, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a899ecd171](https://linux-hardware.org/?probe=a899ecd171) | Oct 27, 2023 |
| Toshiba       | Satellite L745              | Notebook    | [c126c9e041](https://linux-hardware.org/?probe=c126c9e041) | Oct 27, 2023 |
| Avell High... | 1513 Mxti                   | Notebook    | [9f5d60c02b](https://linux-hardware.org/?probe=9f5d60c02b) | Oct 27, 2023 |
| Unknown       | P4M800CE-8237               | Desktop     | [bf22b887f8](https://linux-hardware.org/?probe=bf22b887f8) | Oct 26, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [884529eef1](https://linux-hardware.org/?probe=884529eef1) | Oct 26, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [f32e8922c8](https://linux-hardware.org/?probe=f32e8922c8) | Oct 26, 2023 |
| ASRock        | Z97 Pro4                    | Desktop     | [bcf737a9cd](https://linux-hardware.org/?probe=bcf737a9cd) | Oct 25, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD000... | Notebook    | [4e393023d7](https://linux-hardware.org/?probe=4e393023d7) | Oct 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [251baa33d7](https://linux-hardware.org/?probe=251baa33d7) | Oct 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [a06cdb13fc](https://linux-hardware.org/?probe=a06cdb13fc) | Oct 23, 2023 |
| Framework     | Laptop                      | Notebook    | [f78c8c1b58](https://linux-hardware.org/?probe=f78c8c1b58) | Oct 22, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b9698d48be](https://linux-hardware.org/?probe=b9698d48be) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [77fb62615e](https://linux-hardware.org/?probe=77fb62615e) | Oct 22, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [74d5de2172](https://linux-hardware.org/?probe=74d5de2172) | Oct 21, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4633508fb0](https://linux-hardware.org/?probe=4633508fb0) | Oct 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [d5669e2ea8](https://linux-hardware.org/?probe=d5669e2ea8) | Oct 19, 2023 |
| Acer          | Predator G3-605             | Desktop     | [d3b59b34a0](https://linux-hardware.org/?probe=d3b59b34a0) | Oct 19, 2023 |
| Alienware     | 13                          | Notebook    | [15e7dfbbab](https://linux-hardware.org/?probe=15e7dfbbab) | Oct 19, 2023 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [5064906065](https://linux-hardware.org/?probe=5064906065) | Oct 18, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [041aba02ce](https://linux-hardware.org/?probe=041aba02ce) | Oct 17, 2023 |
| HP            | 843B                        | Desktop     | [0e5a69e3ab](https://linux-hardware.org/?probe=0e5a69e3ab) | Oct 17, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [1d624b8227](https://linux-hardware.org/?probe=1d624b8227) | Oct 17, 2023 |
| Alienware     | 13                          | Notebook    | [24ce621e56](https://linux-hardware.org/?probe=24ce621e56) | Oct 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2G90... | Notebook    | [36282033c6](https://linux-hardware.org/?probe=36282033c6) | Oct 15, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [cf68d0c810](https://linux-hardware.org/?probe=cf68d0c810) | Oct 14, 2023 |
| HP            | ENVY dv7                    | Notebook    | [0972d8543e](https://linux-hardware.org/?probe=0972d8543e) | Oct 14, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [b0bc91de7a](https://linux-hardware.org/?probe=b0bc91de7a) | Oct 14, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [809ff050d7](https://linux-hardware.org/?probe=809ff050d7) | Oct 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [abfe76b2c9](https://linux-hardware.org/?probe=abfe76b2c9) | Oct 13, 2023 |
| Dell          | Latitude E6520              | Notebook    | [e29f6e9ba8](https://linux-hardware.org/?probe=e29f6e9ba8) | Oct 11, 2023 |
| Acer          | AOD270                      | Notebook    | [b45399c83c](https://linux-hardware.org/?probe=b45399c83c) | Oct 11, 2023 |
| Medion        | TJ4125                      | Desktop     | [e60adf45ac](https://linux-hardware.org/?probe=e60adf45ac) | Oct 10, 2023 |
| Lenovo        | ThinkPad T490 20N3S7DP00    | Notebook    | [eb9d7ec72c](https://linux-hardware.org/?probe=eb9d7ec72c) | Oct 10, 2023 |
| Gigabyte      | A520M S2H                   | Desktop     | [d71ced0f1d](https://linux-hardware.org/?probe=d71ced0f1d) | Oct 08, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [7bd89c0f18](https://linux-hardware.org/?probe=7bd89c0f18) | Oct 07, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [04473f37e9](https://linux-hardware.org/?probe=04473f37e9) | Oct 07, 2023 |
| Lenovo        | ThinkPad T430 2349STC       | Notebook    | [53e8d1302b](https://linux-hardware.org/?probe=53e8d1302b) | Oct 05, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bfed98df15](https://linux-hardware.org/?probe=bfed98df15) | Oct 04, 2023 |
| Lenovo        | ThinkPad T420s 4176W23      | Notebook    | [0d27b7532c](https://linux-hardware.org/?probe=0d27b7532c) | Oct 02, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [271131f10a](https://linux-hardware.org/?probe=271131f10a) | Oct 01, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [438271a68c](https://linux-hardware.org/?probe=438271a68c) | Oct 01, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [f7375967ee](https://linux-hardware.org/?probe=f7375967ee) | Sep 30, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [4d2f60a496](https://linux-hardware.org/?probe=4d2f60a496) | Sep 29, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [99fb3ec5e9](https://linux-hardware.org/?probe=99fb3ec5e9) | Sep 29, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7fb0e4c19c](https://linux-hardware.org/?probe=7fb0e4c19c) | Sep 28, 2023 |
| Dell          | Latitude E5570              | Notebook    | [150f9e624b](https://linux-hardware.org/?probe=150f9e624b) | Sep 28, 2023 |
| HP            | 620                         | Notebook    | [1bdfd56638](https://linux-hardware.org/?probe=1bdfd56638) | Sep 27, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [5fa6a632ae](https://linux-hardware.org/?probe=5fa6a632ae) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [d56ff45f03](https://linux-hardware.org/?probe=d56ff45f03) | Sep 17, 2023 |
| HP            | Compaq Mini 311-1100        | Notebook    | [eefc7ef22f](https://linux-hardware.org/?probe=eefc7ef22f) | Sep 17, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [11d9d55772](https://linux-hardware.org/?probe=11d9d55772) | Sep 17, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [807a40b618](https://linux-hardware.org/?probe=807a40b618) | Sep 15, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.1.0-13-amd64           | 65        | 34.21%  |
| 6.1.0-12-amd64           | 40        | 21.05%  |
| 6.1.0-17-amd64           | 36        | 18.95%  |
| 6.1.0-16-amd64           | 16        | 8.42%   |
| 6.1.0-15-amd64           | 7         | 3.68%   |
| 6.1.0-12-686             | 6         | 3.16%   |
| 6.1.0-14-amd64           | 4         | 2.11%   |
| 6.5.0-0.deb12.4-amd64    | 3         | 1.58%   |
| 6.6.2-x64v4-xanmod1      | 1         | 0.53%   |
| 6.6.11-x64v3-xanmod1     | 1         | 0.53%   |
| 6.5.11-asus-vivobook     | 1         | 0.53%   |
| 6.5.10-asus-vivobook     | 1         | 0.53%   |
| 6.5.0-0.deb12.1-rt-amd64 | 1         | 0.53%   |
| 6.5.0-0.deb12.1-amd64    | 1         | 0.53%   |
| 6.4.0-0.deb12.2-amd64    | 1         | 0.53%   |
| 6.1.0-17-686             | 1         | 0.53%   |
| 6.1.0-16-686             | 1         | 0.53%   |
| 6.1.0-13-686-pae         | 1         | 0.53%   |
| 6.1.0-13-686             | 1         | 0.53%   |
| 6.1.0-11-amd64           | 1         | 0.53%   |
| 5.10.0-25-amd64          | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 172       | 93.99%  |
| 6.5.0   | 5         | 2.73%   |
| 6.6.2   | 1         | 0.55%   |
| 6.6.11  | 1         | 0.55%   |
| 6.5.11  | 1         | 0.55%   |
| 6.5.10  | 1         | 0.55%   |
| 6.4.0   | 1         | 0.55%   |
| 5.10.0  | 1         | 0.55%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 172       | 94.51%  |
| 6.5     | 6         | 3.3%    |
| 6.6     | 2         | 1.1%    |
| 6.4     | 1         | 0.55%   |
| 5.10    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 171       | 94.48%  |
| i686   | 10        | 5.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 168       | 91.8%   |
| Cinnamon   | 6         | 3.28%   |
| Unknown    | 4         | 2.19%   |
| LXDE       | 2         | 1.09%   |
| XFCE       | 1         | 0.55%   |
| MATE       | 1         | 0.55%   |
| KDE5       | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 179       | 98.9%   |
| Wayland | 1         | 0.55%   |
| Tty     | 1         | 0.55%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 99        | 54.4%   |
| Unknown | 82        | 45.05%  |
| GDM3    | 1         | 0.55%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 73        | 40.33%  |
| de_DE   | 28        | 15.47%  |
| en_GB   | 14        | 7.73%   |
| it_IT   | 12        | 6.63%   |
| fr_FR   | 11        | 6.08%   |
| pt_BR   | 7         | 3.87%   |
| pl_PL   | 6         | 3.31%   |
| es_ES   | 4         | 2.21%   |
| Unknown | 4         | 2.21%   |
| ru_RU   | 3         | 1.66%   |
| nl_NL   | 3         | 1.66%   |
| hu_HU   | 3         | 1.66%   |
| es_BO   | 2         | 1.1%    |
| cs_CZ   | 2         | 1.1%    |
| nl_BE   | 1         | 0.55%   |
| hr_HR   | 1         | 0.55%   |
| gl_ES   | 1         | 0.55%   |
| fr_CA   | 1         | 0.55%   |
| es_AR   | 1         | 0.55%   |
| en_NZ   | 1         | 0.55%   |
| en_IN   | 1         | 0.55%   |
| en_AU   | 1         | 0.55%   |
| el_GR   | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 120       | 65.57%  |
| BIOS | 63        | 34.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 146       | 80.22%  |
| Overlay | 14        | 7.69%   |
| Tmpfs   | 11        | 6.04%   |
| Btrfs   | 10        | 5.49%   |
| Xfs     | 1         | 0.55%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 78        | 42.86%  |
| GPT     | 73        | 40.11%  |
| MBR     | 31        | 17.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 160       | 87.91%  |
| Yes       | 22        | 12.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 80.77%  |
| Yes       | 35        | 19.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 30        | 16.57%  |
| ASUSTek Computer                     | 29        | 16.02%  |
| Hewlett-Packard                      | 28        | 15.47%  |
| Dell                                 | 15        | 8.29%   |
| MSI                                  | 13        | 7.18%   |
| Gigabyte Technology                  | 12        | 6.63%   |
| Apple                                | 9         | 4.97%   |
| Acer                                 | 9         | 4.97%   |
| ASRock                               | 6         | 3.31%   |
| Medion                               | 3         | 1.66%   |
| Unknown                              | 3         | 1.66%   |
| Toshiba                              | 2         | 1.1%    |
| Sony                                 | 2         | 1.1%    |
| Intel                                | 2         | 1.1%    |
| HUAWEI                               | 2         | 1.1%    |
| Fujitsu                              | 2         | 1.1%    |
| Alienware                            | 2         | 1.1%    |
| VALE                                 | 1         | 0.55%   |
| TUXEDO                               | 1         | 0.55%   |
| Trigkey                              | 1         | 0.55%   |
| Soyo                                 | 1         | 0.55%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.55%   |
| LETSUNG                              | 1         | 0.55%   |
| Inventec                             | 1         | 0.55%   |
| IBM                                  | 1         | 0.55%   |
| Google                               | 1         | 0.55%   |
| Framework                            | 1         | 0.55%   |
| Fanless Mini PC                      | 1         | 0.55%   |
| Avell High Performance               | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown                                             | 4         | 2.21%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA            | 3         | 1.66%   |
| Gigabyte A520M S2H                                  | 2         | 1.1%    |
| Dell OptiPlex 7010                                  | 2         | 1.1%    |
| Apple iMac5,1                                       | 2         | 1.1%    |
| Acer Aspire E5-575                                  | 2         | 1.1%    |
| VALE Notebook Classic C171V                         | 1         | 0.55%   |
| TUXEDO Pulse 14 Gen1                                | 1         | 0.55%   |
| Trigkey Green G4                                    | 1         | 0.55%   |
| Toshiba Satellite Pro L100                          | 1         | 0.55%   |
| Toshiba Satellite L745                              | 1         | 0.55%   |
| Soyo SY-N3150L Quad                                 | 1         | 0.55%   |
| Sony VGN-FW21E                                      | 1         | 0.55%   |
| Sony SVE1511A1EW                                    | 1         | 0.55%   |
| Shenzhen Meigao Electronic Equipment Mercury series | 1         | 0.55%   |
| MSI Thin GF63 12HW                                  | 1         | 0.55%   |
| MSI MS-7E07                                         | 1         | 0.55%   |
| MSI MS-7E01                                         | 1         | 0.55%   |
| MSI MS-7D69                                         | 1         | 0.55%   |
| MSI MS-7D15                                         | 1         | 0.55%   |
| MSI MS-7C84                                         | 1         | 0.55%   |
| MSI MS-7C56                                         | 1         | 0.55%   |
| MSI MS-7C37                                         | 1         | 0.55%   |
| MSI MS-7B98                                         | 1         | 0.55%   |
| MSI MS-7A38                                         | 1         | 0.55%   |
| MSI MS-7798                                         | 1         | 0.55%   |
| MSI MS-7345                                         | 1         | 0.55%   |
| MSI GF63 Thin 11UC                                  | 1         | 0.55%   |
| Medion S23003                                       | 1         | 0.55%   |
| Medion P7612                                        | 1         | 0.55%   |
| Medion E6214                                        | 1         | 0.55%   |
| Lenovo Yoga Slim 7 14ARE05 82A2                     | 1         | 0.55%   |
| Lenovo V50t-13IMB 11HD000DUM                        | 1         | 0.55%   |
| Lenovo ThinkPad Z13 Gen 1 21D2001PUS                | 1         | 0.55%   |
| Lenovo ThinkPad X61 76754BJ                         | 1         | 0.55%   |
| Lenovo ThinkPad X230 2325SU3                        | 1         | 0.55%   |
| Lenovo ThinkPad X230 2325BA3                        | 1         | 0.55%   |
| Lenovo ThinkPad X1 Extreme 20MGS1QU00               | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS05100            | 1         | 0.55%   |
| Lenovo ThinkPad X1 Carbon 34601C8                   | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                         | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo ThinkPad                              | 18        | 9.94%   |
| Lenovo IdeaPad                               | 6         | 3.31%   |
| HP Pavilion                                  | 6         | 3.31%   |
| Dell Latitude                                | 6         | 3.31%   |
| ASUS VivoBook                                | 6         | 3.31%   |
| Acer Aspire                                  | 6         | 3.31%   |
| ASUS PRIME                                   | 4         | 2.21%   |
| Unknown                                      | 4         | 2.21%   |
| HP ENVY                                      | 3         | 1.66%   |
| Dell OptiPlex                                | 3         | 1.66%   |
| ASUS TUF                                     | 3         | 1.66%   |
| ASUS ROG                                     | 3         | 1.66%   |
| Toshiba Satellite                            | 2         | 1.1%    |
| HP ProDesk                                   | 2         | 1.1%    |
| HP ProBook                                   | 2         | 1.1%    |
| HP Compaq                                    | 2         | 1.1%    |
| HP 250                                       | 2         | 1.1%    |
| Gigabyte B450                                | 2         | 1.1%    |
| Gigabyte A520M                               | 2         | 1.1%    |
| Dell XPS                                     | 2         | 1.1%    |
| Dell Precision                               | 2         | 1.1%    |
| ASUS P5G41T-M                                | 2         | 1.1%    |
| ASRock X670E                                 | 2         | 1.1%    |
| Apple iMac5                                  | 2         | 1.1%    |
| VALE Notebook                                | 1         | 0.55%   |
| TUXEDO Pulse                                 | 1         | 0.55%   |
| Trigkey Green                                | 1         | 0.55%   |
| Soyo SY-N3150L                               | 1         | 0.55%   |
| Sony VGN-FW21E                               | 1         | 0.55%   |
| Sony SVE1511A1EW                             | 1         | 0.55%   |
| Shenzhen Meigao Electronic Equipment Mercury | 1         | 0.55%   |
| MSI Thin                                     | 1         | 0.55%   |
| MSI MS-7E07                                  | 1         | 0.55%   |
| MSI MS-7E01                                  | 1         | 0.55%   |
| MSI MS-7D69                                  | 1         | 0.55%   |
| MSI MS-7D15                                  | 1         | 0.55%   |
| MSI MS-7C84                                  | 1         | 0.55%   |
| MSI MS-7C56                                  | 1         | 0.55%   |
| MSI MS-7C37                                  | 1         | 0.55%   |
| MSI MS-7B98                                  | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2023    | 17        | 9.39%   |
| 2021    | 15        | 8.29%   |
| 2022    | 13        | 7.18%   |
| 2018    | 13        | 7.18%   |
| 2016    | 13        | 7.18%   |
| 2020    | 12        | 6.63%   |
| 2019    | 11        | 6.08%   |
| 2017    | 11        | 6.08%   |
| 2012    | 11        | 6.08%   |
| 2008    | 10        | 5.52%   |
| 2015    | 9         | 4.97%   |
| 2013    | 9         | 4.97%   |
| 2010    | 8         | 4.42%   |
| 2014    | 7         | 3.87%   |
| 2011    | 6         | 3.31%   |
| 2007    | 6         | 3.31%   |
| 2009    | 4         | 2.21%   |
| 2006    | 2         | 1.1%    |
| 2005    | 1         | 0.55%   |
| 2004    | 1         | 0.55%   |
| 2003    | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 97        | 53.59%  |
| Desktop     | 68        | 37.57%  |
| All in one  | 8         | 4.42%   |
| Mini pc     | 6         | 3.31%   |
| Convertible | 2         | 1.1%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 165       | 91.16%  |
| Enabled  | 16        | 8.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 180       | 99.45%  |
| Yes  | 1         | 0.55%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 58        | 31.87%  |
| 16.01-24.0  | 34        | 18.68%  |
| 3.01-4.0    | 22        | 12.09%  |
| 8.01-16.0   | 22        | 12.09%  |
| 32.01-64.0  | 16        | 8.79%   |
| 64.01-256.0 | 11        | 6.04%   |
| 24.01-32.0  | 9         | 4.95%   |
| 1.01-2.0    | 7         | 3.85%   |
| 0.51-1.0    | 2         | 1.1%    |
| 2.01-3.0    | 1         | 0.55%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 63        | 32.81%  |
| 1.01-2.0   | 53        | 27.6%   |
| 4.01-8.0   | 37        | 19.27%  |
| 3.01-4.0   | 25        | 13.02%  |
| 8.01-16.0  | 7         | 3.65%   |
| 0.51-1.0   | 5         | 2.6%    |
| 16.01-24.0 | 1         | 0.52%   |
| 0.01-0.5   | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 104       | 57.14%  |
| 2      | 40        | 21.98%  |
| 3      | 21        | 11.54%  |
| 4      | 7         | 3.85%   |
| 5      | 4         | 2.2%    |
| 0      | 3         | 1.65%   |
| 7      | 2         | 1.1%    |
| 10     | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 120       | 66.3%   |
| Yes       | 61        | 33.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 85.64%  |
| No        | 26        | 14.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 148       | 81.77%  |
| No        | 33        | 18.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 68.13%  |
| No        | 58        | 31.87%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| Germany                | 40        | 22.1%   |
| USA                    | 30        | 16.57%  |
| Italy                  | 20        | 11.05%  |
| France                 | 10        | 5.52%   |
| UK                     | 9         | 4.97%   |
| Brazil                 | 8         | 4.42%   |
| Poland                 | 7         | 3.87%   |
| Netherlands            | 5         | 2.76%   |
| Canada                 | 5         | 2.76%   |
| Spain                  | 4         | 2.21%   |
| India                  | 4         | 2.21%   |
| Russia                 | 3         | 1.66%   |
| Hungary                | 3         | 1.66%   |
| Belgium                | 3         | 1.66%   |
| Saudi Arabia           | 2         | 1.1%    |
| New Zealand            | 2         | 1.1%    |
| Indonesia              | 2         | 1.1%    |
| Czechia                | 2         | 1.1%    |
| Bolivia                | 2         | 1.1%    |
| Austria                | 2         | 1.1%    |
| Ukraine                | 1         | 0.55%   |
| Switzerland            | 1         | 0.55%   |
| Romania                | 1         | 0.55%   |
| Puerto Rico            | 1         | 0.55%   |
| Philippines            | 1         | 0.55%   |
| Norway                 | 1         | 0.55%   |
| Morocco                | 1         | 0.55%   |
| Malta                  | 1         | 0.55%   |
| Malaysia               | 1         | 0.55%   |
| Iran                   | 1         | 0.55%   |
| Greece                 | 1         | 0.55%   |
| Georgia                | 1         | 0.55%   |
| Ecuador                | 1         | 0.55%   |
| Cyprus                 | 1         | 0.55%   |
| Croatia                | 1         | 0.55%   |
| Bosnia and Herzegovina | 1         | 0.55%   |
| Australia              | 1         | 0.55%   |
| Argentina              | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Delligsen       | 4         | 2.13%   |
| Milan           | 3         | 1.6%    |
| Bologna         | 3         | 1.6%    |
| Berlin          | 3         | 1.6%    |
| Aalten          | 3         | 1.6%    |
| Vienna          | 2         | 1.06%   |
| Traunstein      | 2         | 1.06%   |
| Rennes          | 2         | 1.06%   |
| Ratingen        | 2         | 1.06%   |
| Parshall        | 2         | 1.06%   |
| Milano          | 2         | 1.06%   |
| Lambeth         | 2         | 1.06%   |
| Krakow          | 2         | 1.06%   |
| Florence        | 2         | 1.06%   |
| Fitchburg       | 2         | 1.06%   |
| Dallas          | 2         | 1.06%   |
| Bonn            | 2         | 1.06%   |
| Bogor           | 2         | 1.06%   |
| Birmingham      | 2         | 1.06%   |
| Auckland        | 2         | 1.06%   |
| Zuidhorn        | 1         | 0.53%   |
| Yanbu           | 1         | 0.53%   |
| Wittingen       | 1         | 0.53%   |
| Wisconsin Dells | 1         | 0.53%   |
| Winnipeg        | 1         | 0.53%   |
| Wasilla         | 1         | 0.53%   |
| Warsaw          | 1         | 0.53%   |
| Verona          | 1         | 0.53%   |
| Vassenden       | 1         | 0.53%   |
| Valletta        | 1         | 0.53%   |
| Valencia        | 1         | 0.53%   |
| Tsqaltubo       | 1         | 0.53%   |
| Toa Baja        | 1         | 0.53%   |
| Thrissur        | 1         | 0.53%   |
| Sydney          | 1         | 0.53%   |
| Sumy            | 1         | 0.53%   |
| Strzelno        | 1         | 0.53%   |
| South Bend      | 1         | 0.53%   |
| Šlapanice      | 1         | 0.53%   |
| Sisak           | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 46        | 54     | 15.81%  |
| WDC                         | 37        | 50     | 12.71%  |
| Seagate                     | 37        | 46     | 12.71%  |
| Toshiba                     | 15        | 16     | 5.15%   |
| Kingston                    | 15        | 28     | 5.15%   |
| SanDisk                     | 12        | 14     | 4.12%   |
| Crucial                     | 11        | 11     | 3.78%   |
| Unknown                     | 9         | 13     | 3.09%   |
| Micron Technology           | 7         | 7      | 2.41%   |
| China                       | 7         | 8      | 2.41%   |
| Unknown                     | 6         | 7      | 2.06%   |
| PNY                         | 5         | 8      | 1.72%   |
| Hitachi                     | 5         | 6      | 1.72%   |
| A-DATA Technology           | 5         | 5      | 1.72%   |
| SK hynix                    | 4         | 4      | 1.37%   |
| Micron/Crucial Technology   | 4         | 6      | 1.37%   |
| Apple                       | 4         | 4      | 1.37%   |
| Transcend                   | 3         | 3      | 1.03%   |
| Team                        | 3         | 3      | 1.03%   |
| Phison                      | 3         | 6      | 1.03%   |
| JMicron Technology          | 3         | 3      | 1.03%   |
| Intenso                     | 3         | 3      | 1.03%   |
| Intel                       | 3         | 3      | 1.03%   |
| Apacer                      | 3         | 4      | 1.03%   |
| ADATA Technology            | 3         | 3      | 1.03%   |
| SPCC                        | 2         | 2      | 0.69%   |
| Silicon Motion              | 2         | 2      | 0.69%   |
| Realtek                     | 2         | 2      | 0.69%   |
| Phison Electronics          | 2         | 2      | 0.69%   |
| Patriot                     | 2         | 2      | 0.69%   |
| Maxtor                      | 2         | 2      | 0.69%   |
| KIOXIA                      | 2         | 2      | 0.69%   |
| Kingston Technology Company | 2         | 2      | 0.69%   |
| HGST                        | 2         | 2      | 0.69%   |
| Gigabyte Technology         | 2         | 2      | 0.69%   |
| Verbatim                    | 1         | 2      | 0.34%   |
| USB3.0                      | 1         | 1      | 0.34%   |
| TO Exter                    | 1         | 1      | 0.34%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.34%   |
| Lexar                       | 1         | 1      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 6         | 1.94%   |
| Unknown                                                         | 6         | 1.94%   |
| Kingston SA400S37480G 480GB SSD                                 | 5         | 1.61%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 4         | 1.29%   |
| SanDisk NVMe SSD Drive 2TB                                      | 4         | 1.29%   |
| Seagate ST9500325AS 500GB                                       | 3         | 0.97%   |
| Seagate Expansion Desk 8TB                                      | 3         | 0.97%   |
| Samsung MZVLQ1T0HALB-00000 1TB                                  | 3         | 0.97%   |
| Kingston SA400S37240G 240GB SSD                                 | 3         | 0.97%   |
| China SATA SSD 240GB                                            | 3         | 0.97%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                | 2         | 0.65%   |
| WDC WD10SPZX-24Z10 1TB                                          | 2         | 0.65%   |
| Toshiba MQ01ABD100 1TB                                          | 2         | 0.65%   |
| Toshiba HDWE160 6TB                                             | 2         | 0.65%   |
| Team T253512GB SSD                                              | 2         | 0.65%   |
| Seagate ST8000DM004-2U9188 8TB                                  | 2         | 0.65%   |
| Seagate ST500LM021-1KJ152 500GB                                 | 2         | 0.65%   |
| Seagate Desktop 8TB                                             | 2         | 0.65%   |
| SanDisk NVMe SSD Drive 1TB                                      | 2         | 0.65%   |
| Samsung SSD 980 1TB                                             | 2         | 0.65%   |
| Samsung SSD 870 EVO 500GB                                       | 2         | 0.65%   |
| Samsung SSD 860 EVO 250GB                                       | 2         | 0.65%   |
| Samsung SSD 860 EVO 1TB                                         | 2         | 0.65%   |
| Realtek RTL9210B-CG 1024GB                                      | 2         | 0.65%   |
| Phison PS5013 E13 NVMe Controller 256GB                         | 2         | 0.65%   |
| Patriot Burst 240GB SSD                                         | 2         | 0.65%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                             | 2         | 0.65%   |
| Kingston SUV400S37240G 240GB SSD                                | 2         | 0.65%   |
| JMicron Generic 8GB                                             | 2         | 0.65%   |
| Crucial CT500MX500SSD1 500GB                                    | 2         | 0.65%   |
| Crucial CT1000BX500SSD1 1TB                                     | 2         | 0.65%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 2TB | 2         | 0.65%   |
| WDC WDS500G3X0C-00SJG0 500GB                                    | 1         | 0.32%   |
| WDC WDS500G2B0B-00YS70 500GB SSD                                | 1         | 0.32%   |
| WDC WDS500G2B0A 500GB SSD                                       | 1         | 0.32%   |
| WDC WDS400T2B0A-00SM50 4TB SSD                                  | 1         | 0.32%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                                | 1         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                                | 1         | 0.32%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                                | 1         | 0.32%   |
| WDC WDS100T3X0C-00SJG0 1TB                                      | 1         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 37        | 46     | 38.14%  |
| WDC                 | 23        | 35     | 23.71%  |
| Toshiba             | 13        | 14     | 13.4%   |
| Hitachi             | 5         | 6      | 5.15%   |
| Apple               | 3         | 3      | 3.09%   |
| Samsung Electronics | 2         | 2      | 2.06%   |
| Maxtor              | 2         | 2      | 2.06%   |
| JMicron Technology  | 2         | 2      | 2.06%   |
| HGST                | 2         | 2      | 2.06%   |
| USB3.0              | 1         | 1      | 1.03%   |
| Unknown             | 1         | 1      | 1.03%   |
| TO Exter            | 1         | 1      | 1.03%   |
| IBM/Hitachi         | 1         | 1      | 1.03%   |
| Fujitsu             | 1         | 1      | 1.03%   |
| External            | 1         | 1      | 1.03%   |
| DC-624e             | 1         | 1      | 1.03%   |
| Unknown             | 1         | 1      | 1.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 21     | 18.37%  |
| Kingston            | 13        | 21     | 13.27%  |
| WDC                 | 9         | 9      | 9.18%   |
| Crucial             | 9         | 9      | 9.18%   |
| China               | 7         | 8      | 7.14%   |
| SanDisk             | 6         | 6      | 6.12%   |
| PNY                 | 5         | 8      | 5.1%    |
| A-DATA Technology   | 4         | 4      | 4.08%   |
| Transcend           | 3         | 3      | 3.06%   |
| Team                | 3         | 3      | 3.06%   |
| Apacer              | 3         | 4      | 3.06%   |
| SPCC                | 2         | 2      | 2.04%   |
| Phison              | 2         | 5      | 2.04%   |
| Patriot             | 2         | 2      | 2.04%   |
| Intenso             | 2         | 2      | 2.04%   |
| Gigabyte Technology | 2         | 2      | 2.04%   |
| Verbatim            | 1         | 2      | 1.02%   |
| Toshiba             | 1         | 1      | 1.02%   |
| Micron Technology   | 1         | 1      | 1.02%   |
| Intel               | 1         | 1      | 1.02%   |
| Hewlett-Packard     | 1         | 1      | 1.02%   |
| Fanxiang            | 1         | 1      | 1.02%   |
| ASMT109x            | 1         | 1      | 1.02%   |
| Unknown             | 1         | 1      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 88        | 118    | 34.38%  |
| HDD     | 78        | 120    | 30.47%  |
| NVMe    | 74        | 96     | 28.91%  |
| MMC     | 9         | 11     | 3.52%   |
| Unknown | 7         | 10     | 2.73%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 132       | 226    | 56.65%  |
| NVMe | 73        | 94     | 31.33%  |
| SAS  | 19        | 24     | 8.15%   |
| MMC  | 9         | 11     | 3.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 95        | 129    | 53.67%  |
| 0.51-1.0   | 48        | 57     | 27.12%  |
| 1.01-2.0   | 15        | 24     | 8.47%   |
| 4.01-10.0  | 9         | 12     | 5.08%   |
| 3.01-4.0   | 7         | 12     | 3.95%   |
| 10.01-20.0 | 2         | 3      | 1.13%   |
| 2.01-3.0   | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 44        | 24.18%  |
| 501-1000       | 40        | 21.98%  |
| 251-500        | 34        | 18.68%  |
| 1-20           | 15        | 8.24%   |
| More than 3000 | 13        | 7.14%   |
| 1001-2000      | 12        | 6.59%   |
| 51-100         | 9         | 4.95%   |
| 2001-3000      | 6         | 3.3%    |
| 21-50          | 5         | 2.75%   |
| Unknown        | 4         | 2.2%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 65        | 34.39%  |
| 21-50          | 40        | 21.16%  |
| 101-250        | 24        | 12.7%   |
| 51-100         | 23        | 12.17%  |
| 251-500        | 13        | 6.88%   |
| 501-1000       | 8         | 4.23%   |
| More than 3000 | 5         | 2.65%   |
| 1001-2000      | 5         | 2.65%   |
| Unknown        | 4         | 2.12%   |
| 2001-3000      | 2         | 1.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 2         | 2      | 10.53%  |
| WDC WD10SPZX-24Z10 1TB                              | 1         | 1      | 5.26%   |
| WDC WD10EZRZ-00HTKB0 1TB                            | 1         | 1      | 5.26%   |
| Transcend TS512GMTS430S 512GB SSD                   | 1         | 1      | 5.26%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 1      | 5.26%   |
| Seagate ST500LM021-1KJ152 500GB                     | 1         | 1      | 5.26%   |
| Seagate ST31000524AS 1TB                            | 1         | 1      | 5.26%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 1         | 1      | 5.26%   |
| Samsung Electronics HD103UJ 1TB                     | 1         | 1      | 5.26%   |
| Micron Technology MTFDDAK512MAY-1AE1ZABHA 512GB SSD | 1         | 1      | 5.26%   |
| Maxtor 6E040L0 40GB                                 | 1         | 1      | 5.26%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 5.26%   |
| Kingston SKC2500M8500G 500GB                        | 1         | 1      | 5.26%   |
| Kingston SA400S37240G 240GB SSD                     | 1         | 1      | 5.26%   |
| IBM/Hitachi IC35L040AVER07-0 41GB                   | 1         | 1      | 5.26%   |
| Hitachi HTS548080M9AT00 80GB                        | 1         | 1      | 5.26%   |
| Hitachi HTS543232L9A300 320GB                       | 1         | 1      | 5.26%   |
| A-DATA Technology SU800 128GB SSD                   | 1         | 1      | 5.26%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 26.32%  |
| Kingston            | 3         | 3      | 15.79%  |
| WDC                 | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| Transcend           | 1         | 1      | 5.26%   |
| Toshiba             | 1         | 1      | 5.26%   |
| Samsung Electronics | 1         | 1      | 5.26%   |
| Micron Technology   | 1         | 1      | 5.26%   |
| Maxtor              | 1         | 1      | 5.26%   |
| IBM/Hitachi         | 1         | 1      | 5.26%   |
| A-DATA Technology   | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 41.67%  |
| WDC                 | 2         | 2      | 16.67%  |
| Hitachi             | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |
| Maxtor              | 1         | 1      | 8.33%   |
| IBM/Hitachi         | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 12     | 63.16%  |
| SSD  | 6         | 6      | 31.58%  |
| NVMe | 1         | 1      | 5.26%   |

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
| Detected | 99        | 197    | 48.29%  |
| Works    | 87        | 139    | 42.44%  |
| Malfunc  | 19        | 19     | 9.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 116       | 47.93%  |
| AMD                           | 37        | 15.29%  |
| Samsung Electronics           | 26        | 10.74%  |
| SanDisk                       | 10        | 4.13%   |
| Micron Technology             | 6         | 2.48%   |
| Micron/Crucial Technology     | 5         | 2.07%   |
| Kingston Technology Company   | 5         | 2.07%   |
| SK hynix                      | 4         | 1.65%   |
| Phison Electronics            | 4         | 1.65%   |
| Marvell Technology Group      | 4         | 1.65%   |
| ASMedia Technology            | 4         | 1.65%   |
| ADATA Technology              | 4         | 1.65%   |
| KIOXIA                        | 3         | 1.24%   |
| Silicon Motion                | 2         | 0.83%   |
| Nvidia                        | 2         | 0.83%   |
| JMicron Technology            | 2         | 0.83%   |
| VIA Technologies              | 1         | 0.41%   |
| Toshiba America Info Systems  | 1         | 0.41%   |
| Shenzhen Longsys Electronics  | 1         | 0.41%   |
| MAXIO Technology (Hangzhou)   | 1         | 0.41%   |
| Integrated Technology Express | 1         | 0.41%   |
| INNOGRIT                      | 1         | 0.41%   |
| Broadcom / LSI                | 1         | 0.41%   |
| Apple                         | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 21        | 7.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 11        | 3.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 3.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 3.21%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 7         | 2.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 7         | 2.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.14%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 5         | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 1.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 5         | 1.79%   |
| AMD 600 Series Chipset SATA Controller                                         | 5         | 1.79%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 4         | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 1.43%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 4         | 1.43%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 4         | 1.43%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 1.43%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.43%   |
| Sandisk WD Black SN850X NVMe SSD                                               | 3         | 1.07%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 1.07%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.07%   |
| Intel Raptor Lake SATA AHCI Controller                                         | 3         | 1.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.07%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.07%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 3         | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 3         | 1.07%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 1.07%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.71%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.71%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.71%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 2         | 0.71%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.71%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 2         | 0.71%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.71%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 0.71%   |
| Marvell Group 88SE9123 PCIe SATA 6.0 Gb/s controller                           | 2         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 118       | 48.76%  |
| NVMe | 72        | 29.75%  |
| IDE  | 26        | 10.74%  |
| RAID | 25        | 10.33%  |
| SAS  | 1         | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 132       | 72.93%  |
| AMD    | 49        | 27.07%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 1.66%   |
| Intel 13th Gen Core i9-13900H               | 3         | 1.66%   |
| Intel N100                                  | 2         | 1.1%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 2         | 1.1%    |
| Intel Core i7-4790 CPU @ 3.60GHz            | 2         | 1.1%    |
| Intel Core i7-2620M CPU @ 2.70GHz           | 2         | 1.1%    |
| Intel Core i5-7500 CPU @ 3.40GHz            | 2         | 1.1%    |
| Intel Core i5-7300U CPU @ 2.60GHz           | 2         | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 2         | 1.1%    |
| Intel Core i5-4260U CPU @ 1.40GHz           | 2         | 1.1%    |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.1%    |
| Intel Core i3-6006U CPU @ 2.00GHz           | 2         | 1.1%    |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 2         | 1.1%    |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 1.1%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.1%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.1%    |
| AMD Ryzen 9 7950X 16-Core Processor         | 2         | 1.1%    |
| AMD Ryzen 7 PRO 6850U with Radeon Graphics  | 2         | 1.1%    |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2         | 1.1%    |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.1%    |
| AMD Ryzen 5 4500U with Radeon Graphics      | 2         | 1.1%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics | 2         | 1.1%    |
| Intel Xeon CPU X5482 @ 3.20GHz              | 1         | 0.55%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz         | 1         | 0.55%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 1         | 0.55%   |
| Intel Pentium M processor 1500MHz           | 1         | 0.55%   |
| Intel Pentium M processor 1.86GHz           | 1         | 0.55%   |
| Intel Pentium Dual-Core CPU E6700 @ 3.20GHz | 1         | 0.55%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz | 1         | 0.55%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 1         | 0.55%   |
| Intel Pentium Dual CPU E2180 @ 2.00GHz      | 1         | 0.55%   |
| Intel Pentium D CPU 3.00GHz                 | 1         | 0.55%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 1         | 0.55%   |
| Intel Pentium CPU B970 @ 2.30GHz            | 1         | 0.55%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1         | 0.55%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 1         | 0.55%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 1         | 0.55%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 1         | 0.55%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 21.55%  |
| Intel Core i7           | 25        | 13.81%  |
| Other                   | 24        | 13.26%  |
| AMD Ryzen 5             | 11        | 6.08%   |
| Intel Core i3           | 10        | 5.52%   |
| Intel Celeron           | 9         | 4.97%   |
| AMD Ryzen 7             | 9         | 4.97%   |
| Intel Core 2 Duo        | 6         | 3.31%   |
| AMD Ryzen 9             | 6         | 3.31%   |
| AMD Ryzen 3             | 4         | 2.21%   |
| Intel Pentium Dual-Core | 3         | 1.66%   |
| Intel Core 2            | 3         | 1.66%   |
| Intel Xeon              | 2         | 1.1%    |
| Intel Pentium M         | 2         | 1.1%    |
| Intel Pentium           | 2         | 1.1%    |
| Intel Atom              | 2         | 1.1%    |
| AMD Sempron             | 2         | 1.1%    |
| AMD Ryzen 7 PRO         | 2         | 1.1%    |
| AMD FX                  | 2         | 1.1%    |
| AMD E2                  | 2         | 1.1%    |
| Intel Pentium Silver    | 1         | 0.55%   |
| Intel Pentium Dual      | 1         | 0.55%   |
| Intel Pentium D         | 1         | 0.55%   |
| Intel Pentium 4         | 1         | 0.55%   |
| Intel Core i9           | 1         | 0.55%   |
| Intel Core 2 Quad       | 1         | 0.55%   |
| Intel Celeron M         | 1         | 0.55%   |
| AMD Phenom II X6        | 1         | 0.55%   |
| AMD Phenom II X4        | 1         | 0.55%   |
| AMD GX                  | 1         | 0.55%   |
| AMD Embedded            | 1         | 0.55%   |
| AMD E1                  | 1         | 0.55%   |
| AMD Athlon II X2        | 1         | 0.55%   |
| AMD Athlon              | 1         | 0.55%   |
| AMD A8                  | 1         | 0.55%   |
| AMD A6                  | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 69        | 38.12%  |
| 4      | 47        | 25.97%  |
| 6      | 21        | 11.6%   |
| 8      | 16        | 8.84%   |
| 1      | 11        | 6.08%   |
| 16     | 5         | 2.76%   |
| 14     | 5         | 2.76%   |
| 10     | 4         | 2.21%   |
| 12     | 2         | 1.1%    |
| 24     | 1         | 0.55%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 179       | 98.9%   |
| 2      | 2         | 1.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 119       | 65.75%  |
| 1      | 62        | 34.25%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 174       | 96.13%  |
| 32-bit         | 7         | 3.87%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 18        | 9.89%   |
| 0x206a7    | 11        | 6.04%   |
| 0x306c3    | 9         | 4.95%   |
| 0x306a9    | 9         | 4.95%   |
| 0x1067a    | 7         | 3.85%   |
| 0x806e9    | 5         | 2.75%   |
| 0x906e9    | 4         | 2.2%    |
| 0x806c1    | 4         | 2.2%    |
| 0x406e3    | 4         | 2.2%    |
| 0x40651    | 4         | 2.2%    |
| 0x906ea    | 3         | 1.65%   |
| 0x806ec    | 3         | 1.65%   |
| 0x706a8    | 3         | 1.65%   |
| 0x0a50000d | 3         | 1.65%   |
| 0x0810100b | 3         | 1.65%   |
| 0x010000c8 | 3         | 1.65%   |
| 0xb06e0    | 2         | 1.1%    |
| 0xb06a3    | 2         | 1.1%    |
| 0xb0671    | 2         | 1.1%    |
| 0xa0653    | 2         | 1.1%    |
| 0x906c0    | 2         | 1.1%    |
| 0x90672    | 2         | 1.1%    |
| 0x6f6      | 2         | 1.1%    |
| 0x6d8      | 2         | 1.1%    |
| 0x506e3    | 2         | 1.1%    |
| 0x406c3    | 2         | 1.1%    |
| 0x306d4    | 2         | 1.1%    |
| 0x106c2    | 2         | 1.1%    |
| 0x10676    | 2         | 1.1%    |
| 0x0a601206 | 2         | 1.1%    |
| 0x0a601203 | 2         | 1.1%    |
| 0x0a50000c | 2         | 1.1%    |
| 0x0a404102 | 2         | 1.1%    |
| 0x08600106 | 2         | 1.1%    |
| 0x08001138 | 2         | 1.1%    |
| 0x06006704 | 2         | 1.1%    |
| 0x06000852 | 2         | 1.1%    |
| 0xf62      | 1         | 0.55%   |
| 0xf41      | 1         | 0.55%   |
| 0xf29      | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 12.15%  |
| Haswell          | 14        | 7.73%   |
| Alderlake Hybrid | 14        | 7.73%   |
| SandyBridge      | 11        | 6.08%   |
| Unknown          | 11        | 6.08%   |
| IvyBridge        | 10        | 5.52%   |
| Skylake          | 9         | 4.97%   |
| Penryn           | 9         | 4.97%   |
| Zen 3            | 8         | 4.42%   |
| Zen              | 7         | 3.87%   |
| Core             | 6         | 3.31%   |
| Zen 2            | 5         | 2.76%   |
| Broadwell        | 5         | 2.76%   |
| TigerLake        | 4         | 2.21%   |
| Silvermont       | 4         | 2.21%   |
| K10              | 4         | 2.21%   |
| Excavator        | 4         | 2.21%   |
| Zen+             | 3         | 1.66%   |
| Piledriver       | 3         | 1.66%   |
| P6               | 3         | 1.66%   |
| NetBurst         | 3         | 1.66%   |
| IceLake          | 3         | 1.66%   |
| Goldmont plus    | 3         | 1.66%   |
| CometLake        | 3         | 1.66%   |
| Westmere         | 2         | 1.1%    |
| Tremont          | 2         | 1.1%    |
| Puma             | 2         | 1.1%    |
| Gracemont        | 2         | 1.1%    |
| Bonnell          | 2         | 1.1%    |
| Nehalem          | 1         | 0.55%   |
| K8 & K10 hybrid  | 1         | 0.55%   |
| Jaguar           | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 103       | 50%     |
| AMD    | 59        | 28.64%  |
| Nvidia | 44        | 21.36%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 4.61%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 2.3%    |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 5         | 2.3%    |
| Intel HD Graphics 620                                                                    | 5         | 2.3%    |
| AMD Raphael                                                                              | 5         | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 1.84%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 4         | 1.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 1.38%   |
| Intel HD Graphics 630                                                                    | 3         | 1.38%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.38%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.38%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.38%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.38%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 3         | 1.38%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.92%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.92%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.92%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.92%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.92%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.92%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.92%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.92%   |
| Intel HD Graphics 530                                                                    | 2         | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.92%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 2         | 0.92%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 2         | 0.92%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 2         | 0.92%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.92%   |
| AMD RV530/M56-P [Mobility Radeon X1600]                                                  | 2         | 0.92%   |
| AMD RS780L [Radeon 3000]                                                                 | 2         | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 0.92%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 76        | 41.99%  |
| 1 x AMD        | 46        | 25.41%  |
| 1 x Nvidia     | 25        | 13.81%  |
| Intel + Nvidia | 16        | 8.84%   |
| 2 x AMD        | 7         | 3.87%   |
| 2 x Intel      | 4         | 2.21%   |
| Intel + AMD    | 4         | 2.21%   |
| AMD + Nvidia   | 2         | 1.1%    |
| 2 x Nvidia     | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 165       | 91.16%  |
| Proprietary | 14        | 7.73%   |
| Unknown     | 2         | 1.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 53.04%  |
| 0.01-0.5   | 29        | 16.02%  |
| 1.01-2.0   | 16        | 8.84%   |
| 0.51-1.0   | 12        | 6.63%   |
| 7.01-8.0   | 9         | 4.97%   |
| 3.01-4.0   | 9         | 4.97%   |
| 5.01-6.0   | 4         | 2.21%   |
| 8.01-16.0  | 3         | 1.66%   |
| 2.01-3.0   | 2         | 1.1%    |
| 16.01-24.0 | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 23        | 12.04%  |
| AU Optronics            | 23        | 12.04%  |
| Samsung Electronics     | 20        | 10.47%  |
| Chimei Innolux          | 16        | 8.38%   |
| LG Display              | 13        | 6.81%   |
| Goldstar                | 10        | 5.24%   |
| Dell                    | 8         | 4.19%   |
| Lenovo                  | 7         | 3.66%   |
| Hewlett-Packard         | 7         | 3.66%   |
| Acer                    | 7         | 3.66%   |
| Philips                 | 6         | 3.14%   |
| Apple                   | 6         | 3.14%   |
| Ancor Communications    | 5         | 2.62%   |
| Sharp                   | 4         | 2.09%   |
| Iiyama                  | 4         | 2.09%   |
| AOC                     | 4         | 2.09%   |
| Panasonic               | 2         | 1.05%   |
| Mi                      | 2         | 1.05%   |
| HUAWEI                  | 2         | 1.05%   |
| GreenWood               | 2         | 1.05%   |
| Eizo                    | 2         | 1.05%   |
| ViewSonic               | 1         | 0.52%   |
| Unknown                 | 1         | 0.52%   |
| STA                     | 1         | 0.52%   |
| Sceptre                 | 1         | 0.52%   |
| RGT                     | 1         | 0.52%   |
| Quanta Display          | 1         | 0.52%   |
| PANDA                   | 1         | 0.52%   |
| NEC Computers           | 1         | 0.52%   |
| LG Electronics          | 1         | 0.52%   |
| LBT                     | 1         | 0.52%   |
| InnoLux Display         | 1         | 0.52%   |
| InfoVision              | 1         | 0.52%   |
| Idek Iiyama             | 1         | 0.52%   |
| Hitachi                 | 1         | 0.52%   |
| Grundig                 | 1         | 0.52%   |
| Gigabyte Technology     | 1         | 0.52%   |
| Chi Mei Optoelectronics | 1         | 0.52%   |
| Belinea                 | 1         | 0.52%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch       | 3         | 1.55%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch        | 3         | 1.55%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch       | 2         | 1.03%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch    | 2         | 1.03%   |
| Philips 247E4 PHLC0C0 1920x1080 521x293mm 23.5-inch                     | 2         | 1.03%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch            | 2         | 1.03%   |
| Lenovo LEN G32qc-10 LEN66A2 2560x1440 698x392mm 31.5-inch               | 2         | 1.03%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                    | 2         | 1.03%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2         | 1.03%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch        | 2         | 1.03%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                    | 2         | 1.03%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch          | 2         | 1.03%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                        | 2         | 1.03%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                  | 1         | 0.52%   |
| Unknown LCD Monitor CSO 2560x1600                                       | 1         | 0.52%   |
| STA LCD Monitor STA5DCA 1366x768 256x144mm 11.6-inch                    | 1         | 0.52%   |
| Sharp LQ156M1JW09 SHP14D3 1920x1080 344x194mm 15.5-inch                 | 1         | 0.52%   |
| Sharp LCD Monitor SHP1518 1920x1200 366x229mm 17.0-inch                 | 1         | 0.52%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                 | 1         | 0.52%   |
| Sharp LCD Monitor SHP13B4 1024x768 304x228mm 15.0-inch                  | 1         | 0.52%   |
| Sceptre LCD Monitor M24 3840x1080                                       | 1         | 0.52%   |
| Sceptre LCD Monitor M24                                                 | 1         | 0.52%   |
| Samsung Electronics T27D390 SAM0B71 1920x1080 598x336mm 27.0-inch       | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM059A 1920x1080 477x268mm 21.5-inch    | 1         | 0.52%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch     | 1         | 0.52%   |
| Samsung Electronics S32D850 SAM0BCC 2560x1440 708x398mm 32.0-inch       | 1         | 0.52%   |
| Samsung Electronics S24C450 SAM09CB 1920x1080 531x299mm 24.0-inch       | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM0DF6 3840x2160 890x500mm 40.2-inch   | 1         | 0.52%   |
| Samsung Electronics LCD Monitor SAM094D 1920x1080 1210x680mm 54.6-inch  | 1         | 0.52%   |
| Samsung Electronics C32JG5x SAM0F54 2560x1440 697x392mm 31.5-inch       | 1         | 0.52%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1         | 0.52%   |
| RGT LCD Monitor RGT1252 1920x1080 1020x570mm 46.0-inch                  | 1         | 0.52%   |
| Quanta Display LCD Monitor QDS0015 1024x768 285x214mm 14.0-inch         | 1         | 0.52%   |
| Philips LCD Monitor PHL BDM4065 3840x2160                               | 1         | 0.52%   |
| Philips LCD Monitor FTV 1920x1080                                       | 1         | 0.52%   |
| Philips 247EL PHLC084 1920x1080 521x293mm 23.5-inch                     | 1         | 0.52%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 78        | 42.16%  |
| 1366x768 (WXGA)    | 35        | 18.92%  |
| 3840x2160 (4K)     | 19        | 10.27%  |
| 2560x1440 (QHD)    | 9         | 4.86%   |
| 1920x1200 (WUXGA)  | 9         | 4.86%   |
| 1600x900 (HD+)     | 6         | 3.24%   |
| 3440x1440          | 4         | 2.16%   |
| 1680x1050 (WSXGA+) | 4         | 2.16%   |
| 1440x900 (WXGA+)   | 3         | 1.62%   |
| 1280x800 (WXGA)    | 3         | 1.62%   |
| 1280x1024 (SXGA)   | 3         | 1.62%   |
| 1024x768 (XGA)     | 3         | 1.62%   |
| 2560x1600          | 2         | 1.08%   |
| 3840x1080          | 1         | 0.54%   |
| 2560x1080          | 1         | 0.54%   |
| 2256x1504          | 1         | 0.54%   |
| 2160x1440          | 1         | 0.54%   |
| 1920x1280          | 1         | 0.54%   |
| 1024x600           | 1         | 0.54%   |
| Unknown            | 1         | 0.54%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 45        | 23.44%  |
| 13      | 18        | 9.38%   |
| 24      | 15        | 7.81%   |
| 21      | 13        | 6.77%   |
| 27      | 11        | 5.73%   |
| 17      | 11        | 5.73%   |
| 14      | 11        | 5.73%   |
| 23      | 10        | 5.21%   |
| 31      | 6         | 3.13%   |
| Unknown | 6         | 3.13%   |
| 34      | 5         | 2.6%    |
| 22      | 5         | 2.6%    |
| 19      | 5         | 2.6%    |
| 16      | 5         | 2.6%    |
| 12      | 4         | 2.08%   |
| 84      | 3         | 1.56%   |
| 11      | 3         | 1.56%   |
| 54      | 2         | 1.04%   |
| 42      | 2         | 1.04%   |
| 32      | 2         | 1.04%   |
| 20      | 2         | 1.04%   |
| 18      | 2         | 1.04%   |
| 72      | 1         | 0.52%   |
| 46      | 1         | 0.52%   |
| 40      | 1         | 0.52%   |
| 26      | 1         | 0.52%   |
| 8       | 1         | 0.52%   |
| 7       | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 34.21%  |
| 501-600     | 36        | 18.95%  |
| 401-500     | 23        | 12.11%  |
| 201-300     | 18        | 9.47%   |
| 351-400     | 17        | 8.95%   |
| 701-800     | 7         | 3.68%   |
| 601-700     | 6         | 3.16%   |
| Unknown     | 6         | 3.16%   |
| 1501-2000   | 4         | 2.11%   |
| 1001-1500   | 3         | 1.58%   |
| 101-200     | 2         | 1.05%   |
| 901-1000    | 2         | 1.05%   |
| 801-900     | 1         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 140       | 76.92%  |
| 16/10   | 22        | 12.09%  |
| Unknown | 6         | 3.3%    |
| 21/9    | 5         | 2.75%   |
| 5/4     | 3         | 1.65%   |
| 4/3     | 3         | 1.65%   |
| 3/2     | 3         | 1.65%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 24.47%  |
| 201-250        | 33        | 17.55%  |
| 81-90          | 22        | 11.7%   |
| 351-500        | 13        | 6.91%   |
| 301-350        | 12        | 6.38%   |
| 121-130        | 10        | 5.32%   |
| 151-200        | 8         | 4.26%   |
| 71-80          | 7         | 3.72%   |
| More than 1000 | 6         | 3.19%   |
| Unknown        | 6         | 3.19%   |
| 251-300        | 5         | 2.66%   |
| 111-120        | 4         | 2.13%   |
| 501-1000       | 4         | 2.13%   |
| 61-70          | 3         | 1.6%    |
| 51-60          | 3         | 1.6%    |
| 1-40           | 2         | 1.06%   |
| 141-150        | 2         | 1.06%   |
| 131-140        | 1         | 0.53%   |
| 91-100         | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 63        | 33.69%  |
| 101-120       | 52        | 27.81%  |
| 121-160       | 44        | 23.53%  |
| 161-240       | 16        | 8.56%   |
| Unknown       | 6         | 3.21%   |
| More than 240 | 4         | 2.14%   |
| 1-50          | 2         | 1.07%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 164       | 90.11%  |
| 2     | 15        | 8.24%   |
| 4     | 1         | 0.55%   |
| 3     | 1         | 0.55%   |
| 0     | 1         | 0.55%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 99        | 36.94%  |
| Intel                                 | 82        | 30.6%   |
| Qualcomm Atheros                      | 27        | 10.07%  |
| Broadcom                              | 12        | 4.48%   |
| Broadcom Limited                      | 8         | 2.99%   |
| MediaTek                              | 7         | 2.61%   |
| Marvell Technology Group              | 6         | 2.24%   |
| Ralink Technology                     | 3         | 1.12%   |
| TP-Link                               | 2         | 0.75%   |
| Samsung Electronics                   | 2         | 0.75%   |
| Ralink                                | 2         | 0.75%   |
| Qualcomm                              | 2         | 0.75%   |
| Nvidia                                | 2         | 0.75%   |
| Dell                                  | 2         | 0.75%   |
| ASIX Electronics                      | 2         | 0.75%   |
| VIA Technologies                      | 1         | 0.37%   |
| Sierra Wireless                       | 1         | 0.37%   |
| Lenovo                                | 1         | 0.37%   |
| Ericsson Business Mobile Networks     | 1         | 0.37%   |
| Edimax Technology                     | 1         | 0.37%   |
| DisplayLink                           | 1         | 0.37%   |
| D-Link                                | 1         | 0.37%   |
| Cisco Aironet Wireless Communications | 1         | 0.37%   |
| Aquantia                              | 1         | 0.37%   |
| AMD                                   | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 61        | 18.65%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 3.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 3.06%   |
| Realtek RTL8125 2.5GbE Controller                                       | 9         | 2.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 9         | 2.75%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 6         | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.53%   |
| Intel Wireless 7260                                                     | 5         | 1.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.22%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.22%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.22%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 1.22%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                       | 4         | 1.22%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 0.92%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 3         | 0.92%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 3         | 0.92%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                 | 3         | 0.92%   |
| Intel Wireless 8265 / 8275                                              | 3         | 0.92%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 3         | 0.92%   |
| Intel Ethernet Connection I219-LM                                       | 3         | 0.92%   |
| Intel Ethernet Connection I217-LM                                       | 3         | 0.92%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 0.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 2         | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 2         | 0.61%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 2         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 0.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.61%   |
| Intel Wireless 8260                                                     | 2         | 0.61%   |
| Intel Wireless 7265                                                     | 2         | 0.61%   |
| Intel Wireless 3165                                                     | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 63        | 40.65%  |
| Realtek Semiconductor                 | 36        | 23.23%  |
| Qualcomm Atheros                      | 21        | 13.55%  |
| Broadcom                              | 8         | 5.16%   |
| MediaTek                              | 7         | 4.52%   |
| Broadcom Limited                      | 5         | 3.23%   |
| Ralink Technology                     | 3         | 1.94%   |
| TP-Link                               | 2         | 1.29%   |
| Ralink                                | 2         | 1.29%   |
| Qualcomm                              | 2         | 1.29%   |
| Dell                                  | 2         | 1.29%   |
| Sierra Wireless                       | 1         | 0.65%   |
| Edimax Technology                     | 1         | 0.65%   |
| D-Link                                | 1         | 0.65%   |
| Cisco Aironet Wireless Communications | 1         | 0.65%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 6.33%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 6         | 3.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 3.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 3.16%   |
| Intel Wireless 7260                                                     | 5         | 3.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.53%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 2.53%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 4         | 2.53%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 3         | 1.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 3         | 1.9%    |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 3         | 1.9%    |
| Intel Wireless 8265 / 8275                                              | 3         | 1.9%    |
| Intel Raptor Lake-S PCH CNVi WiFi                                       | 3         | 1.9%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 2         | 1.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 1.27%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 2         | 1.27%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.27%   |
| Qualcomm QCNFA765 Wireless Network Adapter                              | 2         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 2         | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.27%   |
| Intel Wireless 8260                                                     | 2         | 1.27%   |
| Intel Wireless 7265                                                     | 2         | 1.27%   |
| Intel Wireless 3165                                                     | 2         | 1.27%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 2         | 1.27%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2         | 1.27%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 2         | 1.27%   |
| Broadcom Limited BCM4321 802.11a/b/g/n                                  | 2         | 1.27%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.27%   |
| TP-Link RTL8812AU Archer T4U 802.11ac                                   | 1         | 0.63%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                                  | 1         | 0.63%   |
| Sierra Wireless EM7345 4G LTE                                           | 1         | 0.63%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.63%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 1         | 0.63%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                         | 1         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 83        | 50.92%  |
| Intel                    | 45        | 27.61%  |
| Qualcomm Atheros         | 8         | 4.91%   |
| Broadcom                 | 8         | 4.91%   |
| Marvell Technology Group | 6         | 3.68%   |
| Broadcom Limited         | 3         | 1.84%   |
| Samsung Electronics      | 2         | 1.23%   |
| Nvidia                   | 2         | 1.23%   |
| ASIX Electronics         | 2         | 1.23%   |
| VIA Technologies         | 1         | 0.61%   |
| Lenovo                   | 1         | 0.61%   |
| DisplayLink              | 1         | 0.61%   |
| Aquantia                 | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 61        | 36.75%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 6.63%   |
| Realtek RTL8125 2.5GbE Controller                                      | 9         | 5.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 9         | 5.42%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 4         | 2.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.81%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 3         | 1.81%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 3         | 1.81%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.81%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 1.2%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 1.2%    |
| Intel I211 Gigabit Network Connection                                  | 2         | 1.2%    |
| Intel Ethernet Connection (7) I219-V                                   | 2         | 1.2%    |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 1.2%    |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 1.2%    |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 1         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.6%    |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.6%    |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.6%    |
| Nvidia MCP77 Ethernet                                                  | 1         | 0.6%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 1         | 0.6%    |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 1         | 0.6%    |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                   | 1         | 0.6%    |
| Lenovo ThinkPad Lan                                                    | 1         | 0.6%    |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.6%    |
| Intel Ethernet Controller I226-V                                       | 1         | 0.6%    |
| Intel Ethernet Controller I225-V                                       | 1         | 0.6%    |
| Intel Ethernet Connection I217-V                                       | 1         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.6%    |
| Intel Ethernet Connection (5) I219-LM                                  | 1         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                  | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.6%    |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.6%    |
| Intel Ethernet Connection (17) I219-V                                  | 1         | 0.6%    |
| Intel Ethernet Connection (16) I219-LM                                 | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 156       | 50.98%  |
| WiFi     | 147       | 48.04%  |
| Modem    | 3         | 0.98%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 102       | 52.85%  |
| Ethernet | 91        | 47.15%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 103       | 56.59%  |
| 1     | 71        | 39.01%  |
| 3     | 7         | 3.85%   |
| 0     | 1         | 0.55%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 116       | 63.74%  |
| Yes  | 66        | 36.26%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 40.32%  |
| Realtek Semiconductor           | 17        | 13.71%  |
| IMC Networks                    | 9         | 7.26%   |
| Apple                           | 9         | 7.26%   |
| Qualcomm Atheros Communications | 8         | 6.45%   |
| Cambridge Silicon Radio         | 6         | 4.84%   |
| Broadcom                        | 6         | 4.84%   |
| Lite-On Technology              | 4         | 3.23%   |
| MediaTek                        | 3         | 2.42%   |
| USI                             | 2         | 1.61%   |
| Realtek                         | 2         | 1.61%   |
| Dell                            | 2         | 1.61%   |
| Ralink                          | 1         | 0.81%   |
| Integrated System Solution      | 1         | 0.81%   |
| Hewlett-Packard                 | 1         | 0.81%   |
| Foxconn / Hon Hai               | 1         | 0.81%   |
| ASUSTek Computer                | 1         | 0.81%   |
| Unknown                         | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 15        | 12.1%   |
| Realtek Bluetooth Radio                             | 14        | 11.29%  |
| Intel Bluetooth Device                              | 8         | 6.45%   |
| Intel AX201 Bluetooth                               | 7         | 5.65%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 6         | 4.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 4.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 4.03%   |
| Intel AX210 Bluetooth                               | 5         | 4.03%   |
| Intel Wireless-AC 3168 Bluetooth                    | 4         | 3.23%   |
| Intel AX200 Bluetooth                               | 4         | 3.23%   |
| IMC Networks Wireless_Device                        | 4         | 3.23%   |
| Apple Bluetooth Host Controller                     | 4         | 3.23%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 2.42%   |
| MediaTek Wireless_Device                            | 3         | 2.42%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.42%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 2.42%   |
| Apple Bluetooth HCI                                 | 3         | 2.42%   |
| USI Bluetooth Device                                | 2         | 1.61%   |
| Realtek Bluetooth Radio                             | 2         | 1.61%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 1.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 1.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.61%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.61%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.81%   |
| Integrated System Solution Bluetooth Device         | 1         | 0.81%   |
| IMC Networks Bluetooth Device                       | 1         | 0.81%   |
| IMC Networks BCM20702A0                             | 1         | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.81%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.81%   |
| Dell Wireless 350 Bluetooth                         | 1         | 0.81%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.81%   |
| Broadcom HP Portable Valentine                      | 1         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 1         | 0.81%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 1         | 0.81%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.81%   |
| Unknown                                             | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 126       | 49.61%  |
| AMD                                          | 61        | 24.02%  |
| Nvidia                                       | 38        | 14.96%  |
| JMTek                                        | 3         | 1.18%   |
| Creative Labs                                | 3         | 1.18%   |
| Texas Instruments                            | 2         | 0.79%   |
| Micro Star International                     | 2         | 0.79%   |
| Creative Technology                          | 2         | 0.79%   |
| C-Media Electronics                          | 2         | 0.79%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.39%   |
| VIA Technologies                             | 1         | 0.39%   |
| Sennheiser Communications                    | 1         | 0.39%   |
| M-Audio                                      | 1         | 0.39%   |
| Logitech                                     | 1         | 0.39%   |
| Hewlett-Packard                              | 1         | 0.39%   |
| GN Netcom                                    | 1         | 0.39%   |
| Generalplus Technology                       | 1         | 0.39%   |
| Focusrite-Novation                           | 1         | 0.39%   |
| BR23                                         | 1         | 0.39%   |
| Blue Microphones                             | 1         | 0.39%   |
| ASUSTek Computer                             | 1         | 0.39%   |
| Astro Gaming                                 | 1         | 0.39%   |
| ASRock                                       | 1         | 0.39%   |
| Altec Lansing Technologies                   | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 26        | 8.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 13        | 4.21%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 12        | 3.88%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 3.56%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 9         | 2.91%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 7         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.94%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 5         | 1.62%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 1.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 4         | 1.29%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 1.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.29%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 4         | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.29%   |
| AMD FCH Azalia Controller                                                                         | 4         | 1.29%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.29%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 3         | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.97%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.97%   |
| Nvidia Audio device                                                                               | 3         | 0.97%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.97%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 3         | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.97%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.97%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.97%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 27        | 23.68%  |
| SK hynix                     | 23        | 20.18%  |
| Kingston                     | 13        | 11.4%   |
| Unknown                      | 12        | 10.53%  |
| Micron Technology            | 12        | 10.53%  |
| G.Skill                      | 4         | 3.51%   |
| Corsair                      | 4         | 3.51%   |
| Crucial                      | 3         | 2.63%   |
| Team                         | 2         | 1.75%   |
| Elpida                       | 2         | 1.75%   |
| A-DATA Technology            | 2         | 1.75%   |
| Unknown                      | 2         | 1.75%   |
| Unknown (ABCD)               | 1         | 0.88%   |
| Super Talent                 | 1         | 0.88%   |
| Smart                        | 1         | 0.88%   |
| Ramaxel Technology           | 1         | 0.88%   |
| Patriot Memory (PDP Systems) | 1         | 0.88%   |
| Nanya Technology             | 1         | 0.88%   |
| Mushkin                      | 1         | 0.88%   |
| Avant                        | 1         | 0.88%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 4         | 3.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 3         | 2.38%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s       | 3         | 2.38%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s           | 3         | 2.38%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                     | 2         | 1.59%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                           | 2         | 1.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.59%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 1.59%   |
| Unknown                                                        | 2         | 1.59%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.79%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 0.79%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 1         | 0.79%   |
| Unknown RAM Module 512MB DIMM                                  | 1         | 0.79%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                      | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 1         | 0.79%   |
| Unknown RAM Module 2GB SODIMM DDR2                             | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR 667MT/s                        | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM 1066MT/s                           | 1         | 0.79%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 0.79%   |
| Unknown RAM Module 1GB DIMM                                    | 1         | 0.79%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 1         | 0.79%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s           | 1         | 0.79%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s          | 1         | 0.79%   |
| Super Talent RAM Module 2GB DIMM DDR2 667MT/s                  | 1         | 0.79%   |
| Smart RAM SF464128CK8IWGKFEG 4GB SODIMM DDR4 2400MT/s          | 1         | 0.79%   |
| SK hynix RAM Module 512MB SODIMM DDR2 533MT/s                  | 1         | 0.79%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                   | 1         | 0.79%   |
| SK hynix RAM Module 2GB DIMM DDR3 1333MT/s                     | 1         | 0.79%   |
| SK hynix RAM Module 1GB SODIMM DDR 667MT/s                     | 1         | 0.79%   |
| SK hynix RAM Module 1GB DIMM DDR2 667MT/s                      | 1         | 0.79%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                  | 1         | 0.79%   |
| SK hynix RAM HYMP564U64CP8-Y5 512MB DIMM DDR 667MT/s           | 1         | 0.79%   |
| SK hynix RAM HYMP125U64CP8-Y5 2GB DIMM DDR 667MT/s             | 1         | 0.79%   |
| SK hynix RAM HMT425S6CFR6C-PB 2GB SODIMM DDR3 1600MT/s         | 1         | 0.79%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s         | 1         | 0.79%   |
| SK hynix RAM HMT41GR7AFR4C-RD 8GB DIMM DDR3 1867MT/s           | 1         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 1         | 0.79%   |
| SK hynix RAM HMT31GR7CFR4C-PB 8GB DIMM DDR3 1600MT/s           | 1         | 0.79%   |
| SK hynix RAM HMT112S6BFR6C-G7 1GB SODIMM DDR3 1067MT/s         | 1         | 0.79%   |
| SK hynix RAM HMT112S6AFR8C-G7 1GB SODIMM DDR3 1066MT/s         | 1         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 41        | 40.2%   |
| DDR3    | 27        | 26.47%  |
| DDR2    | 8         | 7.84%   |
| SDRAM   | 5         | 4.9%    |
| LPDDR5  | 5         | 4.9%    |
| DDR5    | 5         | 4.9%    |
| DDR     | 4         | 3.92%   |
| LPDDR4  | 3         | 2.94%   |
| Unknown | 3         | 2.94%   |
| DRAM    | 1         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 59.41%  |
| DIMM         | 32        | 31.68%  |
| Row Of Chips | 6         | 5.94%   |
| Chip         | 3         | 2.97%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 34        | 30.09%  |
| 4096  | 30        | 26.55%  |
| 16384 | 15        | 13.27%  |
| 2048  | 15        | 13.27%  |
| 1024  | 7         | 6.19%   |
| 512   | 6         | 5.31%   |
| 32768 | 5         | 4.42%   |
| 49152 | 1         | 0.88%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 22        | 20.37%  |
| 1600    | 19        | 17.59%  |
| 2667    | 10        | 9.26%   |
| 667     | 9         | 8.33%   |
| 2133    | 5         | 4.63%   |
| 6400    | 4         | 3.7%    |
| 2400    | 4         | 3.7%    |
| Unknown | 4         | 3.7%    |
| 4800    | 3         | 2.78%   |
| 3266    | 3         | 2.78%   |
| 1333    | 3         | 2.78%   |
| 1066    | 3         | 2.78%   |
| 533     | 3         | 2.78%   |
| 6000    | 2         | 1.85%   |
| 2048    | 2         | 1.85%   |
| 1867    | 2         | 1.85%   |
| 1067    | 2         | 1.85%   |
| 5500    | 1         | 0.93%   |
| 4266    | 1         | 0.93%   |
| 4199    | 1         | 0.93%   |
| 3733    | 1         | 0.93%   |
| 3600    | 1         | 0.93%   |
| 3400    | 1         | 0.93%   |
| 1866    | 1         | 0.93%   |
| 1334    | 1         | 0.93%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 3         | 50%     |
| Seiko Epson           | 1         | 16.67%  |
| Lexmark International | 1         | 16.67%  |
| Canon                 | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson ET-1810 Series    | 1         | 16.67%  |
| Lexmark International MX310dn | 1         | 16.67%  |
| HP LaserJet Pro M404-M405     | 1         | 16.67%  |
| HP DeskJet F4200 series       | 1         | 16.67%  |
| HP DeskJet 4100 series        | 1         | 16.67%  |
| Canon TR4600 series           | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 21        | 21.21%  |
| Bison Electronics                      | 13        | 13.13%  |
| IMC Networks                           | 10        | 10.1%   |
| Logitech                               | 8         | 8.08%   |
| Sunplus Innovation Technology          | 7         | 7.07%   |
| Quanta                                 | 7         | 7.07%   |
| Microdia                               | 7         | 7.07%   |
| Apple                                  | 6         | 6.06%   |
| Realtek Semiconductor                  | 3         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.03%   |
| Suyin                                  | 2         | 2.02%   |
| Sonix Technology                       | 2         | 2.02%   |
| Ricoh                                  | 2         | 2.02%   |
| Acer                                   | 2         | 2.02%   |
| ShineTech                              | 1         | 1.01%   |
| MacroSilicon                           | 1         | 1.01%   |
| Luxvisions Innotech Limited            | 1         | 1.01%   |
| Lite-On Technology                     | 1         | 1.01%   |
| KYE Systems (Mouse Systems)            | 1         | 1.01%   |
| Alcor Micro                            | 1         | 1.01%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 7         | 7.07%   |
| Bison Integrated Camera                           | 6         | 6.06%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 5         | 5.05%   |
| Microdia Integrated_Webcam_HD                     | 3         | 3.03%   |
| Apple FaceTime HD Camera (Built-in)               | 3         | 3.03%   |
| Realtek Integrated_Webcam_HD                      | 2         | 2.02%   |
| Microdia Sonix USB 2.0 Camera                     | 2         | 2.02%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 2         | 2.02%   |
| IMC Networks Integrated Camera                    | 2         | 2.02%   |
| Chicony HP Truevision HD                          | 2         | 2.02%   |
| Chicony HP HD Camera                              | 2         | 2.02%   |
| Chicony HD Webcam                                 | 2         | 2.02%   |
| Bison Integrated RGB Camera                       | 2         | 2.02%   |
| Apple Built-in iSight [Micron]                    | 2         | 2.02%   |
| Suyin HD WebCam                                   | 1         | 1.01%   |
| Suyin Acer CrystalEye Webcam                      | 1         | 1.01%   |
| Sunplus Laptop_Integrated_Webcam_HD               | 1         | 1.01%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 1         | 1.01%   |
| Sunplus Laptop Integrated Webcam FHD              | 1         | 1.01%   |
| Sunplus Integrated_Webcam_FHD                     | 1         | 1.01%   |
| Sunplus Hy-FHD(9807)-Camera                       | 1         | 1.01%   |
| Sunplus HP TrueVision HD Camera                   | 1         | 1.01%   |
| Sunplus FHD Camera Microphone                     | 1         | 1.01%   |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 1.01%   |
| Sonix USB2.0 FHD UVC WebCam                       | 1         | 1.01%   |
| ShineTech USB2.0 HD UVC WebCam                    | 1         | 1.01%   |
| Ricoh USB2.0 Camera                               | 1         | 1.01%   |
| Ricoh Sony Vaio Integrated Webcam                 | 1         | 1.01%   |
| Realtek USB2.0-Camera                             | 1         | 1.01%   |
| Quanta VGA WebCam                                 | 1         | 1.01%   |
| Quanta ov9734_techfront_camera                    | 1         | 1.01%   |
| Quanta HP Wide Vision HD Camera                   | 1         | 1.01%   |
| Quanta HP TrueVision HD Camera                    | 1         | 1.01%   |
| Quanta HP True Vision 5MP Camera                  | 1         | 1.01%   |
| Quanta HP HD Camera                               | 1         | 1.01%   |
| Quanta HD WebCam                                  | 1         | 1.01%   |
| Microdia Laptop_Integrated_Webcam_E4HD            | 1         | 1.01%   |
| Microdia Integrated Webcam                        | 1         | 1.01%   |
| MacroSilicon ClearClick                           | 1         | 1.01%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 1.01%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 6         | 31.58%  |
| Validity Sensors           | 5         | 26.32%  |
| Shenzhen Goodix Technology | 3         | 15.79%  |
| Elan Microelectronics      | 2         | 10.53%  |
| Upek                       | 1         | 5.26%   |
| STMicroelectronics         | 1         | 5.26%   |
| Microsoft                  | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor           | 2         | 10.53%  |
| Shenzhen Goodix  Fingerprint Device                    | 2         | 10.53%  |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 1         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 5.26%   |
| Validity Sensors Fingerprint scanner                   | 1         | 5.26%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 5.26%   |
| Synaptics WBDI                                         | 1         | 5.26%   |
| Synaptics UWP WBDI Device                              | 1         | 5.26%   |
| Synaptics UWP WBDI                                     | 1         | 5.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 5.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 5.26%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 5.26%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 5.26%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 5.26%   |
| Microsoft Fingerprint Reader                           | 1         | 5.26%   |
| Elan ELAN:Fingerprint                                  | 1         | 5.26%   |
| Elan ELAN:ARM-M4                                       | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 33.33%  |
| Lenovo      | 3         | 25%     |
| Alcor Micro | 3         | 25%     |
| Upek        | 2         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Lenovo Integrated Smart Card Reader                                          | 3         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 8.33%   |
| Broadcom 5880                                                                | 1         | 8.33%   |
| Broadcom 58200                                                               | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 128       | 69.95%  |
| 1     | 45        | 24.59%  |
| 2     | 7         | 3.83%   |
| 3     | 3         | 1.64%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 19        | 28.79%  |
| Graphics card            | 12        | 18.18%  |
| Chipcard                 | 12        | 18.18%  |
| Net/wireless             | 8         | 12.12%  |
| Multimedia controller    | 6         | 9.09%   |
| Communication controller | 2         | 3.03%   |
| Bluetooth                | 2         | 3.03%   |
| Unassigned class         | 1         | 1.52%   |
| Storage/nvme             | 1         | 1.52%   |
| Storage                  | 1         | 1.52%   |
| Card reader              | 1         | 1.52%   |
| Camera                   | 1         | 1.52%   |

