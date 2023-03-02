LMDE 5 - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for LMDE 5.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/LMDE_5/Desktop/README.md) and [notebooks](/Dist/LMDE_5/Notebook/README.md).

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

Total: 399

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Supermicro    | X10SAE                      | Server      | [fff44d7132](https://linux-hardware.org/?probe=fff44d7132) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [c1b163bee0](https://linux-hardware.org/?probe=c1b163bee0) | Feb 25, 2023 |
| Toshiba       | Satellite L300              | Notebook    | [76e5b62eec](https://linux-hardware.org/?probe=76e5b62eec) | Feb 25, 2023 |
| Supermicro    | X10SAE                      | Server      | [b968ea6172](https://linux-hardware.org/?probe=b968ea6172) | Feb 25, 2023 |
| HP            | 2000                        | Notebook    | [2e234233cc](https://linux-hardware.org/?probe=2e234233cc) | Feb 25, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [5ad40efe5c](https://linux-hardware.org/?probe=5ad40efe5c) | Feb 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [08d9bfbb41](https://linux-hardware.org/?probe=08d9bfbb41) | Feb 24, 2023 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [d39a85e759](https://linux-hardware.org/?probe=d39a85e759) | Feb 24, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [7acab84e04](https://linux-hardware.org/?probe=7acab84e04) | Feb 22, 2023 |
| Medion        | MS-7800                     | Desktop     | [2f542347f9](https://linux-hardware.org/?probe=2f542347f9) | Feb 19, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [aa5d23bc20](https://linux-hardware.org/?probe=aa5d23bc20) | Feb 19, 2023 |
| Dell          | 0NK70N A03                  | Desktop     | [3da6e11665](https://linux-hardware.org/?probe=3da6e11665) | Feb 18, 2023 |
| itel Mobil... | SPIRIT 2                    | Notebook    | [8c370ddf38](https://linux-hardware.org/?probe=8c370ddf38) | Feb 17, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [bcae3260be](https://linux-hardware.org/?probe=bcae3260be) | Feb 17, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [2c98a8340f](https://linux-hardware.org/?probe=2c98a8340f) | Feb 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [392442adfb](https://linux-hardware.org/?probe=392442adfb) | Feb 16, 2023 |
| Dell          | 0MF24N A03                  | Desktop     | [e48d83d96d](https://linux-hardware.org/?probe=e48d83d96d) | Feb 15, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [da4802f871](https://linux-hardware.org/?probe=da4802f871) | Feb 12, 2023 |
| Fanless Mi... | Rev JSL8                    | Mini pc     | [861c0d497e](https://linux-hardware.org/?probe=861c0d497e) | Feb 12, 2023 |
| Compaq        | 420                         | Notebook    | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [b8854f5844](https://linux-hardware.org/?probe=b8854f5844) | Feb 12, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [20bcead0e8](https://linux-hardware.org/?probe=20bcead0e8) | Feb 11, 2023 |
| Star Labs     | StarBook                    | Notebook    | [08e31c8ad5](https://linux-hardware.org/?probe=08e31c8ad5) | Feb 10, 2023 |
| HP            | 843C                        | Desktop     | [02ddbb64e8](https://linux-hardware.org/?probe=02ddbb64e8) | Feb 09, 2023 |
| Dell          | Precision M4800             | Notebook    | [3f97bef125](https://linux-hardware.org/?probe=3f97bef125) | Feb 08, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [3e0851346e](https://linux-hardware.org/?probe=3e0851346e) | Feb 08, 2023 |
| TUXEDO        | N8xxEZ                      | Notebook    | [680bdf5ada](https://linux-hardware.org/?probe=680bdf5ada) | Feb 07, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e96f495083](https://linux-hardware.org/?probe=e96f495083) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [4df21dd9fa](https://linux-hardware.org/?probe=4df21dd9fa) | Feb 05, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [e42e3a74b4](https://linux-hardware.org/?probe=e42e3a74b4) | Feb 05, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [1985f76677](https://linux-hardware.org/?probe=1985f76677) | Feb 05, 2023 |
| Lenovo        | ThinkPad X260 20F6S02A00    | Notebook    | [3301121a5c](https://linux-hardware.org/?probe=3301121a5c) | Feb 04, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [ea50188d5c](https://linux-hardware.org/?probe=ea50188d5c) | Jan 31, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [6c094e2027](https://linux-hardware.org/?probe=6c094e2027) | Jan 31, 2023 |
| ASUSTek       | P7P55D                      | Desktop     | [981ae95b2a](https://linux-hardware.org/?probe=981ae95b2a) | Jan 31, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [5e5231a159](https://linux-hardware.org/?probe=5e5231a159) | Jan 31, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [c5999dc406](https://linux-hardware.org/?probe=c5999dc406) | Jan 29, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| Acer          | Aspire 3810T                | Notebook    | [a7b93a7119](https://linux-hardware.org/?probe=a7b93a7119) | Jan 29, 2023 |
| Google        | Candy                       | Notebook    | [2b2368d61b](https://linux-hardware.org/?probe=2b2368d61b) | Jan 28, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [40152faf5b](https://linux-hardware.org/?probe=40152faf5b) | Jan 28, 2023 |
| Acer          | Aspire 3810T                | Notebook    | [c77f7df143](https://linux-hardware.org/?probe=c77f7df143) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Intel         | H61M-DS2V                   | Desktop     | [0591a32a07](https://linux-hardware.org/?probe=0591a32a07) | Jan 25, 2023 |
| Compaq        | 420                         | Notebook    | [9ed9e081c4](https://linux-hardware.org/?probe=9ed9e081c4) | Jan 24, 2023 |
| ASRock        | Z87 Pro3                    | Desktop     | [0ab0dbb821](https://linux-hardware.org/?probe=0ab0dbb821) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| Dell          | 0C27VV A01                  | Desktop     | [e43d24d2b6](https://linux-hardware.org/?probe=e43d24d2b6) | Jan 23, 2023 |
| Toshiba       | Satellite L305              | Notebook    | [d1a0c1ddf7](https://linux-hardware.org/?probe=d1a0c1ddf7) | Jan 23, 2023 |
| Dell          | Precision 5520              | Notebook    | [f2b0c15a6d](https://linux-hardware.org/?probe=f2b0c15a6d) | Jan 22, 2023 |
| Dell          | Precision 5520              | Notebook    | [c202a2fa19](https://linux-hardware.org/?probe=c202a2fa19) | Jan 22, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [76a4c34a41](https://linux-hardware.org/?probe=76a4c34a41) | Jan 21, 2023 |
| Fujitsu       | M2010                       | Notebook    | [dec6151200](https://linux-hardware.org/?probe=dec6151200) | Jan 20, 2023 |
| Toshiba       | PORTEGE M780                | Notebook    | [cf65ef4cf0](https://linux-hardware.org/?probe=cf65ef4cf0) | Jan 20, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c5dd2e8482](https://linux-hardware.org/?probe=c5dd2e8482) | Jan 19, 2023 |
| Google        | Candy                       | Notebook    | [f1609bed25](https://linux-hardware.org/?probe=f1609bed25) | Jan 16, 2023 |
| Toshiba       | PORTEGE Z30-B               | Notebook    | [4c5c663576](https://linux-hardware.org/?probe=4c5c663576) | Jan 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [0153a9926a](https://linux-hardware.org/?probe=0153a9926a) | Jan 13, 2023 |
| Lenovo        | B560                        | Notebook    | [e5a272b9c1](https://linux-hardware.org/?probe=e5a272b9c1) | Jan 13, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| Gigabyte      | H310M S2H                   | Desktop     | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [3a9bdd2358](https://linux-hardware.org/?probe=3a9bdd2358) | Jan 12, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [563d7aaba5](https://linux-hardware.org/?probe=563d7aaba5) | Jan 12, 2023 |
| ADVANSUS      | 945G                        | Desktop     | [db0f184e3f](https://linux-hardware.org/?probe=db0f184e3f) | Jan 11, 2023 |
| Intel         | B75                         | Desktop     | [ec08587a4a](https://linux-hardware.org/?probe=ec08587a4a) | Jan 09, 2023 |
| ASUSTek       | K54L                        | Notebook    | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [96cf85d764](https://linux-hardware.org/?probe=96cf85d764) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| MSI           | FM2-A55M-E33                | Desktop     | [1ce8a2718b](https://linux-hardware.org/?probe=1ce8a2718b) | Jan 07, 2023 |
| Acer          | Aspire XC-780               | Desktop     | [66823871a5](https://linux-hardware.org/?probe=66823871a5) | Jan 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [ed8c1ab25e](https://linux-hardware.org/?probe=ed8c1ab25e) | Jan 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [fa19ac7348](https://linux-hardware.org/?probe=fa19ac7348) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Dell          | Vostro 1700                 | Notebook    | [66199c3f54](https://linux-hardware.org/?probe=66199c3f54) | Jan 02, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [fb967bb48d](https://linux-hardware.org/?probe=fb967bb48d) | Jan 01, 2023 |
| ASUSTek       | ROG STRIX Z490-H GAMING     | Desktop     | [12c1c0d9a0](https://linux-hardware.org/?probe=12c1c0d9a0) | Jan 01, 2023 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [cb55beafca](https://linux-hardware.org/?probe=cb55beafca) | Dec 30, 2022 |
| Fujitsu       | D3003-S2 S26361-D3003-S2    | Desktop     | [938db016a2](https://linux-hardware.org/?probe=938db016a2) | Dec 30, 2022 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [6b61c9a811](https://linux-hardware.org/?probe=6b61c9a811) | Dec 28, 2022 |
| Google        | Ultima                      | Notebook    | [b389ad5a98](https://linux-hardware.org/?probe=b389ad5a98) | Dec 27, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [82b0efdce8](https://linux-hardware.org/?probe=82b0efdce8) | Dec 25, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [9a2f55886f](https://linux-hardware.org/?probe=9a2f55886f) | Dec 25, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [571afe8b70](https://linux-hardware.org/?probe=571afe8b70) | Dec 24, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b03e4717c0](https://linux-hardware.org/?probe=b03e4717c0) | Dec 22, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [bc0e60b586](https://linux-hardware.org/?probe=bc0e60b586) | Dec 21, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [2e8ecb2ca4](https://linux-hardware.org/?probe=2e8ecb2ca4) | Dec 20, 2022 |
| TUXEDO        | N8xxEZ                      | Notebook    | [1055ea57f9](https://linux-hardware.org/?probe=1055ea57f9) | Dec 20, 2022 |
| ASUSTek       | X550VC                      | Notebook    | [5d5f66f67a](https://linux-hardware.org/?probe=5d5f66f67a) | Dec 20, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [f80de6076d](https://linux-hardware.org/?probe=f80de6076d) | Dec 18, 2022 |
| HP            | Notebook                    | Notebook    | [ef017285ee](https://linux-hardware.org/?probe=ef017285ee) | Dec 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [91c790d54e](https://linux-hardware.org/?probe=91c790d54e) | Dec 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [917150ffce](https://linux-hardware.org/?probe=917150ffce) | Dec 18, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [770334f093](https://linux-hardware.org/?probe=770334f093) | Dec 16, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [26a498297f](https://linux-hardware.org/?probe=26a498297f) | Dec 16, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [76e4dff90a](https://linux-hardware.org/?probe=76e4dff90a) | Dec 13, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6988ab07fe](https://linux-hardware.org/?probe=6988ab07fe) | Dec 12, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [6ec6d4563d](https://linux-hardware.org/?probe=6ec6d4563d) | Dec 12, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [b29a792d69](https://linux-hardware.org/?probe=b29a792d69) | Dec 12, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [129c077e02](https://linux-hardware.org/?probe=129c077e02) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | Notebook    | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [8f9e4c0e26](https://linux-hardware.org/?probe=8f9e4c0e26) | Dec 10, 2022 |
| HP            | Madoo                       | Notebook    | [6a38e78ecf](https://linux-hardware.org/?probe=6a38e78ecf) | Dec 10, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [5a75bbfc48](https://linux-hardware.org/?probe=5a75bbfc48) | Dec 09, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [5a1593a360](https://linux-hardware.org/?probe=5a1593a360) | Dec 08, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [6e40fd6fd3](https://linux-hardware.org/?probe=6e40fd6fd3) | Dec 08, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [83117100d0](https://linux-hardware.org/?probe=83117100d0) | Dec 08, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e810c5c2eb](https://linux-hardware.org/?probe=e810c5c2eb) | Dec 08, 2022 |
| Acer          | TravelMate 4070             | Notebook    | [ec589662a2](https://linux-hardware.org/?probe=ec589662a2) | Dec 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [7ef192d30d](https://linux-hardware.org/?probe=7ef192d30d) | Dec 06, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [bb589ef99d](https://linux-hardware.org/?probe=bb589ef99d) | Dec 04, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [a1d27bfc48](https://linux-hardware.org/?probe=a1d27bfc48) | Dec 04, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [b41442c5a1](https://linux-hardware.org/?probe=b41442c5a1) | Dec 01, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [b8145a2349](https://linux-hardware.org/?probe=b8145a2349) | Dec 01, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| HP            | Mini 110-1100               | Notebook    | [8f28854dfa](https://linux-hardware.org/?probe=8f28854dfa) | Nov 28, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e1dcd6d119](https://linux-hardware.org/?probe=e1dcd6d119) | Nov 28, 2022 |
| HP            | 8299                        | Desktop     | [8f6b89bf07](https://linux-hardware.org/?probe=8f6b89bf07) | Nov 25, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [3ca3320525](https://linux-hardware.org/?probe=3ca3320525) | Nov 24, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2bfa796e90](https://linux-hardware.org/?probe=2bfa796e90) | Nov 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [afcb386e71](https://linux-hardware.org/?probe=afcb386e71) | Nov 23, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [98fac29e02](https://linux-hardware.org/?probe=98fac29e02) | Nov 22, 2022 |
| Lenovo        | ThinkPad W510 43192PU       | Notebook    | [53882f751e](https://linux-hardware.org/?probe=53882f751e) | Nov 22, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1ad4dcb28a](https://linux-hardware.org/?probe=1ad4dcb28a) | Nov 22, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [f2a00a7bb3](https://linux-hardware.org/?probe=f2a00a7bb3) | Nov 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [d93b2b9778](https://linux-hardware.org/?probe=d93b2b9778) | Nov 21, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [486c850cd6](https://linux-hardware.org/?probe=486c850cd6) | Nov 20, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [3f043b96c0](https://linux-hardware.org/?probe=3f043b96c0) | Nov 19, 2022 |
| Dell          | G15 5510                    | Notebook    | [5d9d96d71e](https://linux-hardware.org/?probe=5d9d96d71e) | Nov 16, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e656990178](https://linux-hardware.org/?probe=e656990178) | Nov 16, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [5e87654e7a](https://linux-hardware.org/?probe=5e87654e7a) | Nov 14, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [33d278cd7a](https://linux-hardware.org/?probe=33d278cd7a) | Nov 12, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [95f38cc8d9](https://linux-hardware.org/?probe=95f38cc8d9) | Nov 12, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [721020a0fe](https://linux-hardware.org/?probe=721020a0fe) | Nov 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b9f262d40b](https://linux-hardware.org/?probe=b9f262d40b) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [9e5c4960c3](https://linux-hardware.org/?probe=9e5c4960c3) | Nov 10, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [a8c3b285d0](https://linux-hardware.org/?probe=a8c3b285d0) | Nov 10, 2022 |
| HP            | ProBook 650 G4              | Notebook    | [2aec71897b](https://linux-hardware.org/?probe=2aec71897b) | Nov 08, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [2e0c6e37a4](https://linux-hardware.org/?probe=2e0c6e37a4) | Nov 07, 2022 |
| HP            | Unknown                     | Notebook    | [fe07901ad1](https://linux-hardware.org/?probe=fe07901ad1) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [495b046a6b](https://linux-hardware.org/?probe=495b046a6b) | Nov 06, 2022 |
| Dell          | 0N826N A03                  | Desktop     | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [8d633d6712](https://linux-hardware.org/?probe=8d633d6712) | Nov 05, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [d23c74b1f2](https://linux-hardware.org/?probe=d23c74b1f2) | Nov 05, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [8ac5a3b401](https://linux-hardware.org/?probe=8ac5a3b401) | Nov 03, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [077d7d4379](https://linux-hardware.org/?probe=077d7d4379) | Nov 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ba31f00bbd](https://linux-hardware.org/?probe=ba31f00bbd) | Oct 31, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [0c281b6b5e](https://linux-hardware.org/?probe=0c281b6b5e) | Oct 29, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7bf16d5a25](https://linux-hardware.org/?probe=7bf16d5a25) | Oct 25, 2022 |
| ASUSTek       | X510UQR                     | Notebook    | [c03f0f4b6a](https://linux-hardware.org/?probe=c03f0f4b6a) | Oct 24, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [774861eae7](https://linux-hardware.org/?probe=774861eae7) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [3b8452c3c6](https://linux-hardware.org/?probe=3b8452c3c6) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [a5d65724fa](https://linux-hardware.org/?probe=a5d65724fa) | Oct 21, 2022 |
| HP            | 8299                        | Desktop     | [2b4c3924e4](https://linux-hardware.org/?probe=2b4c3924e4) | Oct 20, 2022 |
| Dell          | XPS L701X                   | Notebook    | [53c5b7ea24](https://linux-hardware.org/?probe=53c5b7ea24) | Oct 18, 2022 |
| HP            | 8299                        | Desktop     | [bf86078a8f](https://linux-hardware.org/?probe=bf86078a8f) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [09dcc1a805](https://linux-hardware.org/?probe=09dcc1a805) | Oct 18, 2022 |
| Toshiba       | Satellite L855D             | Notebook    | [ac86cf3035](https://linux-hardware.org/?probe=ac86cf3035) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| Sony          | SVF1532W4E                  | Notebook    | [e66750b690](https://linux-hardware.org/?probe=e66750b690) | Oct 18, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [19d09fb082](https://linux-hardware.org/?probe=19d09fb082) | Oct 17, 2022 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [9f3307c5d0](https://linux-hardware.org/?probe=9f3307c5d0) | Oct 17, 2022 |
| Dell          | 0D735T A00                  | Desktop     | [20d0bc0836](https://linux-hardware.org/?probe=20d0bc0836) | Oct 12, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0526dffee9](https://linux-hardware.org/?probe=0526dffee9) | Oct 11, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| AZW           | MINI S                      | Desktop     | [c5be5052a0](https://linux-hardware.org/?probe=c5be5052a0) | Oct 09, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [2ee3173d51](https://linux-hardware.org/?probe=2ee3173d51) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [36ad4bb59b](https://linux-hardware.org/?probe=36ad4bb59b) | Oct 06, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [de85238b42](https://linux-hardware.org/?probe=de85238b42) | Oct 05, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [b340ade9c9](https://linux-hardware.org/?probe=b340ade9c9) | Oct 05, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [e31e511d7b](https://linux-hardware.org/?probe=e31e511d7b) | Oct 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [bc6ad9af3e](https://linux-hardware.org/?probe=bc6ad9af3e) | Oct 03, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [230a36c236](https://linux-hardware.org/?probe=230a36c236) | Oct 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | Inspiron 5420               | Notebook    | [71f7e67ca7](https://linux-hardware.org/?probe=71f7e67ca7) | Oct 01, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [f7f5368662](https://linux-hardware.org/?probe=f7f5368662) | Sep 28, 2022 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [fb983c65ac](https://linux-hardware.org/?probe=fb983c65ac) | Sep 28, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7b1ea76e92](https://linux-hardware.org/?probe=7b1ea76e92) | Sep 26, 2022 |
| Dell          | 082WXT A01                  | Desktop     | [7c4445ad04](https://linux-hardware.org/?probe=7c4445ad04) | Sep 26, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [d277bf47ec](https://linux-hardware.org/?probe=d277bf47ec) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [fb7029173f](https://linux-hardware.org/?probe=fb7029173f) | Sep 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ff09bb4e1](https://linux-hardware.org/?probe=8ff09bb4e1) | Sep 22, 2022 |
| Gateway       | DX4870                      | Desktop     | [fd5b76e786](https://linux-hardware.org/?probe=fd5b76e786) | Sep 22, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| Digiboard     | NM70-TI                     | Desktop     | [84e21c8253](https://linux-hardware.org/?probe=84e21c8253) | Sep 21, 2022 |
| Medion        | P15648                      | Notebook    | [e3d7873a30](https://linux-hardware.org/?probe=e3d7873a30) | Sep 19, 2022 |
| Dell          | 0XC837                      | Desktop     | [94ad27e346](https://linux-hardware.org/?probe=94ad27e346) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [df362e9796](https://linux-hardware.org/?probe=df362e9796) | Sep 18, 2022 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [a251261add](https://linux-hardware.org/?probe=a251261add) | Sep 18, 2022 |
| MSI           | B360M MORTAR                | Desktop     | [cdcff8c15d](https://linux-hardware.org/?probe=cdcff8c15d) | Sep 18, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | G72                         | Notebook    | [d00cd9a9bd](https://linux-hardware.org/?probe=d00cd9a9bd) | Sep 14, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Dell          | 0FJ030                      | Desktop     | [bf789b5c5f](https://linux-hardware.org/?probe=bf789b5c5f) | Sep 10, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [acbb191061](https://linux-hardware.org/?probe=acbb191061) | Sep 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [65ef8d235d](https://linux-hardware.org/?probe=65ef8d235d) | Sep 08, 2022 |
| Pegatron      | 2A9Eh                       | Desktop     | [2c7b59f70b](https://linux-hardware.org/?probe=2c7b59f70b) | Sep 08, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [c92f578a36](https://linux-hardware.org/?probe=c92f578a36) | Sep 07, 2022 |
| Lenovo        | Yoga 2 11 20332             | Notebook    | [9b6635c1db](https://linux-hardware.org/?probe=9b6635c1db) | Sep 06, 2022 |
| Dell          | Latitude E6430              | Notebook    | [b8b0464d70](https://linux-hardware.org/?probe=b8b0464d70) | Sep 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [9842cac1de](https://linux-hardware.org/?probe=9842cac1de) | Sep 04, 2022 |
| eMachines     | EL1352G                     | Desktop     | [2547a277f7](https://linux-hardware.org/?probe=2547a277f7) | Sep 04, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [db2b212059](https://linux-hardware.org/?probe=db2b212059) | Sep 03, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [632cd1e47d](https://linux-hardware.org/?probe=632cd1e47d) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [98812c04d7](https://linux-hardware.org/?probe=98812c04d7) | Sep 03, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [6fe42dd16d](https://linux-hardware.org/?probe=6fe42dd16d) | Sep 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [8e05735fc7](https://linux-hardware.org/?probe=8e05735fc7) | Sep 02, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3728476d21](https://linux-hardware.org/?probe=3728476d21) | Aug 31, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [38e6481a65](https://linux-hardware.org/?probe=38e6481a65) | Aug 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [eb89774723](https://linux-hardware.org/?probe=eb89774723) | Aug 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| MSI           | Z170A GAMING PRO            | Desktop     | [f86bc78c33](https://linux-hardware.org/?probe=f86bc78c33) | Aug 27, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [da93b01660](https://linux-hardware.org/?probe=da93b01660) | Aug 22, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8b1d8459e2](https://linux-hardware.org/?probe=8b1d8459e2) | Aug 20, 2022 |
| MSI           | B85I                        | Desktop     | [454972a062](https://linux-hardware.org/?probe=454972a062) | Aug 19, 2022 |
| Microtech     | ebookPro                    | Notebook    | [b6c6859a02](https://linux-hardware.org/?probe=b6c6859a02) | Aug 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | Notebook    | [ee7cbda038](https://linux-hardware.org/?probe=ee7cbda038) | Aug 17, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [3de3bd4b06](https://linux-hardware.org/?probe=3de3bd4b06) | Aug 15, 2022 |
| Dell          | Latitude E5540              | Notebook    | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [3b01398aeb](https://linux-hardware.org/?probe=3b01398aeb) | Aug 11, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [68c8f97537](https://linux-hardware.org/?probe=68c8f97537) | Aug 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [527a0607d8](https://linux-hardware.org/?probe=527a0607d8) | Aug 08, 2022 |
| Wortmann      | TERRA_MOBILE_1713A          | Notebook    | [09f3eadbcf](https://linux-hardware.org/?probe=09f3eadbcf) | Aug 07, 2022 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [5c3cec3fb9](https://linux-hardware.org/?probe=5c3cec3fb9) | Aug 03, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [07f925d91c](https://linux-hardware.org/?probe=07f925d91c) | Aug 03, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [dfe7ba57b8](https://linux-hardware.org/?probe=dfe7ba57b8) | Jul 31, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [683cd6273f](https://linux-hardware.org/?probe=683cd6273f) | Jul 30, 2022 |
| Framework     | Laptop                      | Notebook    | [426cf376b2](https://linux-hardware.org/?probe=426cf376b2) | Jul 30, 2022 |
| Dell          | Latitude E5540              | Notebook    | [67063fe669](https://linux-hardware.org/?probe=67063fe669) | Jul 30, 2022 |
| Dell          | 0CRWCR A01                  | All in one  | [e1cd0b697d](https://linux-hardware.org/?probe=e1cd0b697d) | Jul 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [21fc33de37](https://linux-hardware.org/?probe=21fc33de37) | Jul 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b664049a0](https://linux-hardware.org/?probe=0b664049a0) | Jul 28, 2022 |
| Microtech     | ebookPro                    | Notebook    | [12215b6984](https://linux-hardware.org/?probe=12215b6984) | Jul 27, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [df4af55b5b](https://linux-hardware.org/?probe=df4af55b5b) | Jul 26, 2022 |
| Lenovo        | ThinkPad T61 7661A16        | Notebook    | [892a11d89d](https://linux-hardware.org/?probe=892a11d89d) | Jul 26, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [47420083a3](https://linux-hardware.org/?probe=47420083a3) | Jul 23, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [1754eeae39](https://linux-hardware.org/?probe=1754eeae39) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a05a04fae5](https://linux-hardware.org/?probe=a05a04fae5) | Jul 21, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [67c590c532](https://linux-hardware.org/?probe=67c590c532) | Jul 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [fdaa3bac93](https://linux-hardware.org/?probe=fdaa3bac93) | Jul 20, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [786f399d7a](https://linux-hardware.org/?probe=786f399d7a) | Jul 19, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [19d55ade50](https://linux-hardware.org/?probe=19d55ade50) | Jul 19, 2022 |
| HP            | 8433 11                     | Desktop     | [85ecad964d](https://linux-hardware.org/?probe=85ecad964d) | Jul 17, 2022 |
| HP            | 8433 11                     | Desktop     | [7f6ec63dc8](https://linux-hardware.org/?probe=7f6ec63dc8) | Jul 17, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [cf03561efa](https://linux-hardware.org/?probe=cf03561efa) | Jul 17, 2022 |
| ASUSTek       | BM6820_BM6620_BP6320-8      | Desktop     | [8d8c845646](https://linux-hardware.org/?probe=8d8c845646) | Jul 17, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3d9f189ad0](https://linux-hardware.org/?probe=3d9f189ad0) | Jul 13, 2022 |
| Google        | Akemi                       | Notebook    | [d4a36d2743](https://linux-hardware.org/?probe=d4a36d2743) | Jul 13, 2022 |
| MSI           | GL73 8SE                    | Notebook    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [24cd72e0bf](https://linux-hardware.org/?probe=24cd72e0bf) | Jul 08, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9be78f4466](https://linux-hardware.org/?probe=9be78f4466) | Jul 07, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [12e48a7c0a](https://linux-hardware.org/?probe=12e48a7c0a) | Jul 06, 2022 |
| AMI           | T3 MRD                      | Notebook    | [bf634565fd](https://linux-hardware.org/?probe=bf634565fd) | Jul 02, 2022 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [efc2332724](https://linux-hardware.org/?probe=efc2332724) | Jul 02, 2022 |
| Sony          | SVE1512G1RW                 | Notebook    | [cf5ff8285e](https://linux-hardware.org/?probe=cf5ff8285e) | Jul 02, 2022 |
| HP            | Pavilion 17                 | Notebook    | [1efb06e77e](https://linux-hardware.org/?probe=1efb06e77e) | Jul 01, 2022 |
| HP            | Compaq 15                   | Notebook    | [fb14abab4d](https://linux-hardware.org/?probe=fb14abab4d) | Jun 30, 2022 |
| Framework     | Laptop                      | Notebook    | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [e848f3258c](https://linux-hardware.org/?probe=e848f3258c) | Jun 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [a8b7e4a9fe](https://linux-hardware.org/?probe=a8b7e4a9fe) | Jun 26, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [f54df47fa0](https://linux-hardware.org/?probe=f54df47fa0) | Jun 25, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1eaa95f069](https://linux-hardware.org/?probe=1eaa95f069) | Jun 24, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [0d72ab6a71](https://linux-hardware.org/?probe=0d72ab6a71) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [64e65ab80b](https://linux-hardware.org/?probe=64e65ab80b) | Jun 24, 2022 |
| HP            | Laptop 15z-ef2xxx           | Notebook    | [879d7a231f](https://linux-hardware.org/?probe=879d7a231f) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [a55d01829f](https://linux-hardware.org/?probe=a55d01829f) | Jun 23, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [14135356d6](https://linux-hardware.org/?probe=14135356d6) | Jun 20, 2022 |
| MSI           | U180                        | Notebook    | [7aa374e07e](https://linux-hardware.org/?probe=7aa374e07e) | Jun 20, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [348ec06fd0](https://linux-hardware.org/?probe=348ec06fd0) | Jun 18, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [88294cb5aa](https://linux-hardware.org/?probe=88294cb5aa) | Jun 12, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [281724432e](https://linux-hardware.org/?probe=281724432e) | Jun 12, 2022 |
| Acer          | Aspire One 522              | Notebook    | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [efd1e69f79](https://linux-hardware.org/?probe=efd1e69f79) | Jun 09, 2022 |
| Lenovo        | 3731 NOK                    | Desktop     | [1da6b9f6c0](https://linux-hardware.org/?probe=1da6b9f6c0) | Jun 09, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [519a18864f](https://linux-hardware.org/?probe=519a18864f) | Jun 09, 2022 |
| Sony          | SVE1713Y1RB                 | Notebook    | [4a1bc35dda](https://linux-hardware.org/?probe=4a1bc35dda) | Jun 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [57582f68b6](https://linux-hardware.org/?probe=57582f68b6) | Jun 08, 2022 |
| Dell          | 0XR1GT A00                  | Desktop     | [8c3fd28612](https://linux-hardware.org/?probe=8c3fd28612) | Jun 08, 2022 |
| Multilaser    | PC150                       | Notebook    | [ee0a35cc62](https://linux-hardware.org/?probe=ee0a35cc62) | Jun 08, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [870233669c](https://linux-hardware.org/?probe=870233669c) | Jun 07, 2022 |
| Alienware     | 14                          | Notebook    | [7dabcbc673](https://linux-hardware.org/?probe=7dabcbc673) | Jun 07, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [6f8785bd56](https://linux-hardware.org/?probe=6f8785bd56) | May 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [0e59a69b8d](https://linux-hardware.org/?probe=0e59a69b8d) | May 30, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [ba204646ba](https://linux-hardware.org/?probe=ba204646ba) | May 25, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Acer          | Seawolf                     | Desktop     | [dccbcb7ef3](https://linux-hardware.org/?probe=dccbcb7ef3) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [67aa7158d3](https://linux-hardware.org/?probe=67aa7158d3) | May 24, 2022 |
| HP            | Laptop 14-df0xxx            | Notebook    | [94992083bc](https://linux-hardware.org/?probe=94992083bc) | May 24, 2022 |
| Acer          | Aspire One 522              | Notebook    | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Intel         | DQ77MK AAG39642-400         | Desktop     | [f694bcfbc5](https://linux-hardware.org/?probe=f694bcfbc5) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [8757941b52](https://linux-hardware.org/?probe=8757941b52) | May 17, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [91700e1cb8](https://linux-hardware.org/?probe=91700e1cb8) | May 16, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [63950495b3](https://linux-hardware.org/?probe=63950495b3) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [e9310a7ede](https://linux-hardware.org/?probe=e9310a7ede) | May 15, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [3f8becd67d](https://linux-hardware.org/?probe=3f8becd67d) | May 15, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [399deea7b9](https://linux-hardware.org/?probe=399deea7b9) | May 15, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [d01652f69f](https://linux-hardware.org/?probe=d01652f69f) | May 15, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [4b0c466a88](https://linux-hardware.org/?probe=4b0c466a88) | May 15, 2022 |
| Howard Com... | R7X                         | Notebook    | [bc6d6a31eb](https://linux-hardware.org/?probe=bc6d6a31eb) | May 13, 2022 |
| HP            | Notebook                    | Notebook    | [200c1dabff](https://linux-hardware.org/?probe=200c1dabff) | May 09, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0d64940271](https://linux-hardware.org/?probe=0d64940271) | May 09, 2022 |
| HP            | ENVY 17                     | Notebook    | [a503de2c1f](https://linux-hardware.org/?probe=a503de2c1f) | May 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [54815db142](https://linux-hardware.org/?probe=54815db142) | May 07, 2022 |
| ASUSTek       | VivoBook E14 E402YA_L402... | Notebook    | [57e085245c](https://linux-hardware.org/?probe=57e085245c) | May 07, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [1441dfb79e](https://linux-hardware.org/?probe=1441dfb79e) | May 07, 2022 |
| HP            | 158B                        | Desktop     | [a613debdee](https://linux-hardware.org/?probe=a613debdee) | May 06, 2022 |
| HP            | 158B                        | Desktop     | [21f9c188f3](https://linux-hardware.org/?probe=21f9c188f3) | May 06, 2022 |
| Philco        | 10D                         | Notebook    | [d2f71d99cd](https://linux-hardware.org/?probe=d2f71d99cd) | May 05, 2022 |
| Philco        | 10D                         | Notebook    | [9882f4ca80](https://linux-hardware.org/?probe=9882f4ca80) | May 05, 2022 |
| HP            | 339A                        | Desktop     | [d58b95ebb1](https://linux-hardware.org/?probe=d58b95ebb1) | May 05, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [a7305e2070](https://linux-hardware.org/?probe=a7305e2070) | May 04, 2022 |
| Lenovo        | ThinkPad T480 20L6S1RN00    | Notebook    | [eb55b73c5a](https://linux-hardware.org/?probe=eb55b73c5a) | May 03, 2022 |
| Toshiba       | Satellite M55               | Notebook    | [9d5733c6fc](https://linux-hardware.org/?probe=9d5733c6fc) | May 02, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [c45a37ce5d](https://linux-hardware.org/?probe=c45a37ce5d) | May 01, 2022 |
| HP            | Presario C500 (GF581UA#A... | Notebook    | [0e01914db4](https://linux-hardware.org/?probe=0e01914db4) | Apr 30, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [53bceed0aa](https://linux-hardware.org/?probe=53bceed0aa) | Apr 29, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [e9376d24f0](https://linux-hardware.org/?probe=e9376d24f0) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [d0fae524f9](https://linux-hardware.org/?probe=d0fae524f9) | Apr 29, 2022 |
| Acer          | AOD270                      | Notebook    | [44d897bc15](https://linux-hardware.org/?probe=44d897bc15) | Apr 29, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [00a648bda6](https://linux-hardware.org/?probe=00a648bda6) | Apr 28, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [4646f6cd23](https://linux-hardware.org/?probe=4646f6cd23) | Apr 28, 2022 |
| Samsung       | 730QDA                      | Convertible | [6d4573984e](https://linux-hardware.org/?probe=6d4573984e) | Apr 28, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ff8e46a260](https://linux-hardware.org/?probe=ff8e46a260) | Apr 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [0a6534997e](https://linux-hardware.org/?probe=0a6534997e) | Apr 27, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [ccb4d8201f](https://linux-hardware.org/?probe=ccb4d8201f) | Apr 24, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce4f3d8ec8](https://linux-hardware.org/?probe=ce4f3d8ec8) | Apr 24, 2022 |
| Dixonsxp      | Unknown                     | Notebook    | [65e40dacf4](https://linux-hardware.org/?probe=65e40dacf4) | Apr 20, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [b7df060840](https://linux-hardware.org/?probe=b7df060840) | Apr 19, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [70fe08376f](https://linux-hardware.org/?probe=70fe08376f) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [b544c48421](https://linux-hardware.org/?probe=b544c48421) | Apr 19, 2022 |
| Dell          | 0CU568 A00                  | Desktop     | [84f7029c22](https://linux-hardware.org/?probe=84f7029c22) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [7f0bad47af](https://linux-hardware.org/?probe=7f0bad47af) | Apr 19, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [3a0c54144d](https://linux-hardware.org/?probe=3a0c54144d) | Apr 19, 2022 |
| Dell          | 0X574R                      | Notebook    | [6da5c2339f](https://linux-hardware.org/?probe=6da5c2339f) | Apr 18, 2022 |
| HP            | 14                          | Notebook    | [71f296bd93](https://linux-hardware.org/?probe=71f296bd93) | Apr 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [78396d572c](https://linux-hardware.org/?probe=78396d572c) | Apr 15, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Acer          | AOA110                      | Notebook    | [cba10fc182](https://linux-hardware.org/?probe=cba10fc182) | Apr 13, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [ed40a9ddc1](https://linux-hardware.org/?probe=ed40a9ddc1) | Apr 12, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a137f0540](https://linux-hardware.org/?probe=9a137f0540) | Apr 12, 2022 |
| MSI           | Z170A GAMING M5             | Desktop     | [8f2e10cbf3](https://linux-hardware.org/?probe=8f2e10cbf3) | Apr 12, 2022 |
| Howard Com... | R7X                         | Notebook    | [e0f3701b1b](https://linux-hardware.org/?probe=e0f3701b1b) | Apr 12, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2a33f087e6](https://linux-hardware.org/?probe=2a33f087e6) | Apr 11, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [05b9ec80c6](https://linux-hardware.org/?probe=05b9ec80c6) | Apr 11, 2022 |
| Howard Com... | R7X                         | Notebook    | [5885bbaa90](https://linux-hardware.org/?probe=5885bbaa90) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [4d5998459b](https://linux-hardware.org/?probe=4d5998459b) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | Notebook    | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| Acer          | WG43M                       | Desktop     | [c7cb6ee141](https://linux-hardware.org/?probe=c7cb6ee141) | Apr 08, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [28371c08c2](https://linux-hardware.org/?probe=28371c08c2) | Apr 08, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [613d6e7d3c](https://linux-hardware.org/?probe=613d6e7d3c) | Apr 07, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9f1a76acb8](https://linux-hardware.org/?probe=9f1a76acb8) | Apr 06, 2022 |
| Dell          | Latitude 5511               | Notebook    | [2cb0a3e451](https://linux-hardware.org/?probe=2cb0a3e451) | Apr 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [18a4ba3137](https://linux-hardware.org/?probe=18a4ba3137) | Apr 06, 2022 |
| Dell          | Precision 7520              | Notebook    | [7404842400](https://linux-hardware.org/?probe=7404842400) | Apr 05, 2022 |
| ASUSTek       | P6T                         | Desktop     | [5ed6ed355f](https://linux-hardware.org/?probe=5ed6ed355f) | Apr 04, 2022 |
| Panasonic     | CF-H2BJJHZDE                | Tablet      | [50e0a85fd3](https://linux-hardware.org/?probe=50e0a85fd3) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [b5b25093ba](https://linux-hardware.org/?probe=b5b25093ba) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6107c72fb2](https://linux-hardware.org/?probe=6107c72fb2) | Apr 03, 2022 |
| LincPlus      | LINNCPLUS P1                | Notebook    | [22406313dc](https://linux-hardware.org/?probe=22406313dc) | Apr 02, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [699e7d272d](https://linux-hardware.org/?probe=699e7d272d) | Apr 02, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [387b77f172](https://linux-hardware.org/?probe=387b77f172) | Apr 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0609df27fa](https://linux-hardware.org/?probe=0609df27fa) | Mar 31, 2022 |
| Packard Be... | DOT S                       | Notebook    | [85e7386152](https://linux-hardware.org/?probe=85e7386152) | Mar 28, 2022 |
| Packard Be... | DOT S                       | Notebook    | [edef12b9d5](https://linux-hardware.org/?probe=edef12b9d5) | Mar 28, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [b2e70b8251](https://linux-hardware.org/?probe=b2e70b8251) | Mar 28, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [1e0a28c8f3](https://linux-hardware.org/?probe=1e0a28c8f3) | Mar 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [01815a09bb](https://linux-hardware.org/?probe=01815a09bb) | Mar 27, 2022 |
| Toshiba       | Satellite L455              | Notebook    | [90334cf68d](https://linux-hardware.org/?probe=90334cf68d) | Mar 26, 2022 |
| Dell          | Precision M4400             | Notebook    | [5172327d82](https://linux-hardware.org/?probe=5172327d82) | Mar 25, 2022 |
| Medion        | E6220                       | Notebook    | [e739ef27a1](https://linux-hardware.org/?probe=e739ef27a1) | Mar 24, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [3f4c13ee47](https://linux-hardware.org/?probe=3f4c13ee47) | Mar 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f8561c65dc](https://linux-hardware.org/?probe=f8561c65dc) | Mar 21, 2022 |
| HP            | 0AE8h C                     | Desktop     | [d3980b5b59](https://linux-hardware.org/?probe=d3980b5b59) | Mar 14, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [261e6c0463](https://linux-hardware.org/?probe=261e6c0463) | Mar 02, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [25f6ef89f9](https://linux-hardware.org/?probe=25f6ef89f9) | Mar 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.0-12-amd64          | 41        | 13.27%  |
| 5.10.0-19-amd64          | 37        | 11.97%  |
| 5.10.0-21-amd64          | 33        | 10.68%  |
| 5.10.0-14-amd64          | 30        | 9.71%   |
| 5.10.0-20-amd64          | 29        | 9.39%   |
| 5.10.0-13-amd64          | 27        | 8.74%   |
| 5.10.0-18-amd64          | 25        | 8.09%   |
| 5.10.0-17-amd64          | 21        | 6.8%    |
| 5.10.0-15-amd64          | 19        | 6.15%   |
| 5.10.0-16-amd64          | 14        | 4.53%   |
| 5.10.0-13-686            | 6         | 1.94%   |
| 5.18.0-0.bpo.1-amd64     | 4         | 1.29%   |
| 5.16.0-0.bpo.4-amd64     | 3         | 0.97%   |
| 5.19.0-0.deb11.2-amd64   | 2         | 0.65%   |
| 5.10.0-12-686            | 2         | 0.65%   |
| 6.1.11-x64v1-xanmod1     | 1         | 0.32%   |
| 6.0.2-x64v2-rt11-xanmod1 | 1         | 0.32%   |
| 6.0.0-0.deb11.2-amd64    | 1         | 0.32%   |
| 5.19.10-xanmod1          | 1         | 0.32%   |
| 5.18.0-4-amd64           | 1         | 0.32%   |
| 5.18.0-3-amd64           | 1         | 0.32%   |
| 5.16.0-0.bpo.3-amd64     | 1         | 0.32%   |
| 5.15.78-xanmod1          | 1         | 0.32%   |
| 5.15.70-xanmod1          | 1         | 0.32%   |
| 5.15.0-0.bpo.3-amd64     | 1         | 0.32%   |
| 5.10.0-20-686            | 1         | 0.32%   |
| 5.10.0-19-686            | 1         | 0.32%   |
| 5.10.0-17-686            | 1         | 0.32%   |
| 5.10.0-14-686            | 1         | 0.32%   |
| 5.10.0-11-686            | 1         | 0.32%   |
| 4.19.0-23-amd64          | 1         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 270       | 93.43%  |
| 5.18.0  | 6         | 2.08%   |
| 5.16.0  | 3         | 1.04%   |
| 5.19.0  | 2         | 0.69%   |
| 6.1.11  | 1         | 0.35%   |
| 6.0.2   | 1         | 0.35%   |
| 6.0.0   | 1         | 0.35%   |
| 5.19.10 | 1         | 0.35%   |
| 5.15.78 | 1         | 0.35%   |
| 5.15.70 | 1         | 0.35%   |
| 5.15.0  | 1         | 0.35%   |
| 4.19.0  | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 270       | 93.75%  |
| 5.18    | 6         | 2.08%   |
| 5.19    | 3         | 1.04%   |
| 5.16    | 3         | 1.04%   |
| 6.0     | 2         | 0.69%   |
| 5.15    | 2         | 0.69%   |
| 6.1     | 1         | 0.35%   |
| 4.19    | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 272       | 95.44%  |
| i686   | 13        | 4.56%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| X-Cinnamon | 255       | 89.16%  |
| Cinnamon   | 22        | 7.69%   |
| MATE       | 3         | 1.05%   |
| XFCE       | 2         | 0.7%    |
| KDE5       | 1         | 0.35%   |
| KDE        | 1         | 0.35%   |
| awesome    | 1         | 0.35%   |
| Unknown    | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 285       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 176       | 61.32%  |
| LightDM | 108       | 37.63%  |
| SDDM    | 2         | 0.7%    |
| GDM     | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 96        | 33.57%  |
| de_DE | 42        | 14.69%  |
| ru_RU | 28        | 9.79%   |
| pt_BR | 20        | 6.99%   |
| fr_FR | 14        | 4.9%    |
| en_GB | 14        | 4.9%    |
| it_IT | 11        | 3.85%   |
| es_ES | 8         | 2.8%    |
| pl_PL | 6         | 2.1%    |
| en_CA | 4         | 1.4%    |
| es_MX | 3         | 1.05%   |
| tr_TR | 2         | 0.7%    |
| sv_SE | 2         | 0.7%    |
| ko_KR | 2         | 0.7%    |
| fr_CA | 2         | 0.7%    |
| fr_BE | 2         | 0.7%    |
| es_BO | 2         | 0.7%    |
| en_NZ | 2         | 0.7%    |
| en_IE | 2         | 0.7%    |
| da_DK | 2         | 0.7%    |
| cs_CZ | 2         | 0.7%    |
| sk_SK | 1         | 0.35%   |
| ru_UA | 1         | 0.35%   |
| pt_PT | 1         | 0.35%   |
| nn_NO | 1         | 0.35%   |
| nl_AW | 1         | 0.35%   |
| it_CH | 1         | 0.35%   |
| hu_HU | 1         | 0.35%   |
| es_VE | 1         | 0.35%   |
| es_PE | 1         | 0.35%   |
| es_NI | 1         | 0.35%   |
| es_EC | 1         | 0.35%   |
| es_CR | 1         | 0.35%   |
| en_ZA | 1         | 0.35%   |
| en_SG | 1         | 0.35%   |
| en_IN | 1         | 0.35%   |
| en_AU | 1         | 0.35%   |
| el_GR | 1         | 0.35%   |
| de_CH | 1         | 0.35%   |
| de_AT | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 169       | 59.09%  |
| BIOS | 117       | 40.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 263       | 92.28%  |
| Tmpfs   | 7         | 2.46%   |
| Btrfs   | 7         | 2.46%   |
| Overlay | 6         | 2.11%   |
| Xfs     | 2         | 0.7%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 176       | 61.32%  |
| GPT     | 77        | 26.83%  |
| MBR     | 34        | 11.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 262       | 91.61%  |
| Yes       | 24        | 8.39%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 251       | 87.76%  |
| Yes       | 35        | 12.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 51        | 17.89%  |
| Lenovo              | 41        | 14.39%  |
| Dell                | 38        | 13.33%  |
| ASUSTek Computer    | 36        | 12.63%  |
| Acer                | 20        | 7.02%   |
| Gigabyte Technology | 14        | 4.91%   |
| MSI                 | 13        | 4.56%   |
| Apple               | 9         | 3.16%   |
| Toshiba             | 7         | 2.46%   |
| Fujitsu             | 5         | 1.75%   |
| Samsung Electronics | 4         | 1.4%    |
| ASRock              | 4         | 1.4%    |
| Sony                | 3         | 1.05%   |
| Medion              | 3         | 1.05%   |
| Intel               | 3         | 1.05%   |
| Google              | 3         | 1.05%   |
| Compaq              | 2         | 0.7%    |
| Unknown             | 2         | 0.7%    |
| Wortmann AG         | 1         | 0.35%   |
| TUXEDO              | 1         | 0.35%   |
| Supermicro          | 1         | 0.35%   |
| Star Labs           | 1         | 0.35%   |
| SiYW                | 1         | 0.35%   |
| Philco              | 1         | 0.35%   |
| Pegatron            | 1         | 0.35%   |
| Panasonic           | 1         | 0.35%   |
| Packard Bell        | 1         | 0.35%   |
| Multilaser          | 1         | 0.35%   |
| Microtech           | 1         | 0.35%   |
| LincPlus            | 1         | 0.35%   |
| Kruger&Matz         | 1         | 0.35%   |
| itel Mobile Limited | 1         | 0.35%   |
| Howard Computers    | 1         | 0.35%   |
| Gateway             | 1         | 0.35%   |
| Framework           | 1         | 0.35%   |
| Foxconn             | 1         | 0.35%   |
| Fanless Mini PC     | 1         | 0.35%   |
| eMachines           | 1         | 0.35%   |
| Dynabook            | 1         | 0.35%   |
| Dixonsxp            | 1         | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 4         | 1.4%    |
| Lenovo IdeaPad 3 15ITL6 82H8        | 2         | 0.7%    |
| Lenovo IdeaPad 3 15ADA05 81W1       | 2         | 0.7%    |
| Lenovo G500 20236                   | 2         | 0.7%    |
| HP Notebook                         | 2         | 0.7%    |
| HP Laptop 15z-ef2xxx                | 2         | 0.7%    |
| HP Laptop 15-dw3xxx                 | 2         | 0.7%    |
| HP 250 G8 Notebook PC               | 2         | 0.7%    |
| Gigabyte B450 AORUS M               | 2         | 0.7%    |
| Dell Latitude E6400                 | 2         | 0.7%    |
| Dell Latitude E5540                 | 2         | 0.7%    |
| Compaq 420                          | 2         | 0.7%    |
| ASUS PRIME B350M-A                  | 2         | 0.7%    |
| Acer Aspire E1-570G                 | 2         | 0.7%    |
| Acer Aspire 5930                    | 2         | 0.7%    |
| Wortmann AG TERRA_MOBILE_1713A      | 1         | 0.35%   |
| TUXEDO N8xxEZ                       | 1         | 0.35%   |
| Toshiba Satellite M55               | 1         | 0.35%   |
| Toshiba Satellite L855D             | 1         | 0.35%   |
| Toshiba Satellite L455              | 1         | 0.35%   |
| Toshiba Satellite L305              | 1         | 0.35%   |
| Toshiba Satellite L300              | 1         | 0.35%   |
| Toshiba PORTEGE Z30-B               | 1         | 0.35%   |
| Toshiba PORTEGE M780                | 1         | 0.35%   |
| Supermicro X10SAE                   | 1         | 0.35%   |
| Star Labs StarBook                  | 1         | 0.35%   |
| Sony SVF1532W4E                     | 1         | 0.35%   |
| Sony SVE1713Y1RB                    | 1         | 0.35%   |
| Sony SVE1512G1RW                    | 1         | 0.35%   |
| SiYW V200 Series                    | 1         | 0.35%   |
| Samsung RV415/RV515                 | 1         | 0.35%   |
| Samsung DeskTop System              | 1         | 0.35%   |
| Samsung 730QDA                      | 1         | 0.35%   |
| Samsung 355V4C/356V4C/3445VC/3545VC | 1         | 0.35%   |
| Philco 10D                          | 1         | 0.35%   |
| Pegatron Pro 3015 Microtower PC     | 1         | 0.35%   |
| Panasonic CF-H2BJJHZDE              | 1         | 0.35%   |
| Packard Bell DOT S                  | 1         | 0.35%   |
| Multilaser PC150                    | 1         | 0.35%   |
| MSI U180                            | 1         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 16        | 5.61%   |
| Lenovo ThinkPad    | 13        | 4.56%   |
| HP Laptop          | 11        | 3.86%   |
| Lenovo IdeaPad     | 10        | 3.51%   |
| Dell Latitude      | 9         | 3.16%   |
| Dell Precision     | 8         | 2.81%   |
| Dell Inspiron      | 8         | 2.81%   |
| HP EliteBook       | 6         | 2.11%   |
| ASUS PRIME         | 6         | 2.11%   |
| Toshiba Satellite  | 5         | 1.75%   |
| HP Pavilion        | 5         | 1.75%   |
| Dell Vostro        | 5         | 1.75%   |
| ASUS VivoBook      | 5         | 1.75%   |
| HP ProBook         | 4         | 1.4%    |
| ASUS ROG           | 4         | 1.4%    |
| Unknown            | 4         | 1.4%    |
| HP Compaq          | 3         | 1.05%   |
| Gigabyte B450      | 3         | 1.05%   |
| Dell XPS           | 3         | 1.05%   |
| Dell OptiPlex      | 3         | 1.05%   |
| Toshiba PORTEGE    | 2         | 0.7%    |
| Lenovo Yoga        | 2         | 0.7%    |
| Lenovo ThinkCentre | 2         | 0.7%    |
| Lenovo ThinkBook   | 2         | 0.7%    |
| Lenovo Legion      | 2         | 0.7%    |
| Lenovo G500        | 2         | 0.7%    |
| HP ZBook           | 2         | 0.7%    |
| HP Notebook        | 2         | 0.7%    |
| HP 255             | 2         | 0.7%    |
| HP 250             | 2         | 0.7%    |
| Gigabyte B450M     | 2         | 0.7%    |
| Fujitsu LIFEBOOK   | 2         | 0.7%    |
| Compaq 420         | 2         | 0.7%    |
| Wortmann AG TERRA  | 1         | 0.35%   |
| TUXEDO N8xxEZ      | 1         | 0.35%   |
| Supermicro X10SAE  | 1         | 0.35%   |
| Star Labs StarBook | 1         | 0.35%   |
| Sony SVF1532W4E    | 1         | 0.35%   |
| Sony SVE1713Y1RB   | 1         | 0.35%   |
| Sony SVE1512G1RW   | 1         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 34        | 11.93%  |
| 2018 | 28        | 9.82%   |
| 2012 | 27        | 9.47%   |
| 2020 | 23        | 8.07%   |
| 2013 | 21        | 7.37%   |
| 2019 | 16        | 5.61%   |
| 2017 | 16        | 5.61%   |
| 2010 | 16        | 5.61%   |
| 2009 | 16        | 5.61%   |
| 2015 | 15        | 5.26%   |
| 2016 | 14        | 4.91%   |
| 2022 | 13        | 4.56%   |
| 2011 | 13        | 4.56%   |
| 2014 | 10        | 3.51%   |
| 2008 | 9         | 3.16%   |
| 2007 | 8         | 2.81%   |
| 2006 | 5         | 1.75%   |
| 2023 | 1         | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 182       | 63.86%  |
| Desktop     | 90        | 31.58%  |
| Convertible | 4         | 1.4%    |
| Mini pc     | 3         | 1.05%   |
| All in one  | 3         | 1.05%   |
| Tablet      | 2         | 0.7%    |
| Server      | 1         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 260       | 90.59%  |
| Enabled  | 27        | 9.41%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 280       | 98.25%  |
| Yes  | 5         | 1.75%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 76        | 26.57%  |
| 16.01-24.0      | 52        | 18.18%  |
| 3.01-4.0        | 51        | 17.83%  |
| 8.01-16.0       | 51        | 17.83%  |
| 32.01-64.0      | 24        | 8.39%   |
| 1.01-2.0        | 15        | 5.24%   |
| 2.01-3.0        | 8         | 2.8%    |
| 64.01-256.0     | 4         | 1.4%    |
| 24.01-32.0      | 3         | 1.05%   |
| More than 256.0 | 1         | 0.35%   |
| 0.51-1.0        | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 124       | 41.2%   |
| 2.01-3.0   | 97        | 32.23%  |
| 3.01-4.0   | 30        | 9.97%   |
| 4.01-8.0   | 28        | 9.3%    |
| 0.51-1.0   | 17        | 5.65%   |
| 8.01-16.0  | 3         | 1%      |
| 32.01-64.0 | 1         | 0.33%   |
| 24.01-32.0 | 1         | 0.33%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 190       | 65.74%  |
| 2      | 60        | 20.76%  |
| 3      | 24        | 8.3%    |
| 4      | 8         | 2.77%   |
| 5      | 5         | 1.73%   |
| 6      | 2         | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 62.94%  |
| Yes       | 106       | 37.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 239       | 83.86%  |
| No        | 46        | 16.14%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 231       | 80.77%  |
| No        | 55        | 19.23%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 55.94%  |
| No        | 126       | 44.06%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 55        | 19.16%  |
| Germany      | 45        | 15.68%  |
| Russia       | 28        | 9.76%   |
| Brazil       | 21        | 7.32%   |
| Italy        | 17        | 5.92%   |
| France       | 16        | 5.57%   |
| UK           | 11        | 3.83%   |
| Canada       | 9         | 3.14%   |
| Spain        | 8         | 2.79%   |
| Poland       | 8         | 2.79%   |
| Sweden       | 4         | 1.39%   |
| Mexico       | 4         | 1.39%   |
| Belgium      | 4         | 1.39%   |
| Belarus      | 4         | 1.39%   |
| Turkey       | 3         | 1.05%   |
| Vietnam      | 2         | 0.7%    |
| Venezuela    | 2         | 0.7%    |
| South Korea  | 2         | 0.7%    |
| Romania      | 2         | 0.7%    |
| Portugal     | 2         | 0.7%    |
| New Zealand  | 2         | 0.7%    |
| Kazakhstan   | 2         | 0.7%    |
| Hungary      | 2         | 0.7%    |
| Greece       | 2         | 0.7%    |
| Denmark      | 2         | 0.7%    |
| Chile        | 2         | 0.7%    |
| Bolivia      | 2         | 0.7%    |
| Austria      | 2         | 0.7%    |
| Australia    | 2         | 0.7%    |
| Ukraine      | 1         | 0.35%   |
| South Africa | 1         | 0.35%   |
| Slovenia     | 1         | 0.35%   |
| Slovakia     | 1         | 0.35%   |
| Serbia       | 1         | 0.35%   |
| Peru         | 1         | 0.35%   |
| Paraguay     | 1         | 0.35%   |
| Norway       | 1         | 0.35%   |
| Nicaragua    | 1         | 0.35%   |
| Netherlands  | 1         | 0.35%   |
| Malaysia     | 1         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Moscow                | 7         | 2.4%    |
| Berlin                | 5         | 1.71%   |
| St Petersburg         | 3         | 1.03%   |
| Rome                  | 3         | 1.03%   |
| Munich                | 3         | 1.03%   |
| Miami                 | 3         | 1.03%   |
| Krakow                | 3         | 1.03%   |
| Frankfurt am Main     | 3         | 1.03%   |
| Vancouver             | 2         | 0.68%   |
| Sao Paulo             | 2         | 0.68%   |
| San Jose              | 2         | 0.68%   |
| Oruro                 | 2         | 0.68%   |
| Nuremberg             | 2         | 0.68%   |
| Neasden               | 2         | 0.68%   |
| Montreal              | 2         | 0.68%   |
| Melbourne             | 2         | 0.68%   |
| Mannheim              | 2         | 0.68%   |
| Madrid                | 2         | 0.68%   |
| London                | 2         | 0.68%   |
| Hrodna                | 2         | 0.68%   |
| Hamburg               | 2         | 0.68%   |
| Freiburg im Breisgau  | 2         | 0.68%   |
| Bend                  | 2         | 0.68%   |
| Belém                | 2         | 0.68%   |
| Auckland              | 2         | 0.68%   |
| Astana                | 2         | 0.68%   |
| Zaragoza              | 1         | 0.34%   |
| Yekaterinburg         | 1         | 0.34%   |
| Wroclaw               | 1         | 0.34%   |
| Weimar                | 1         | 0.34%   |
| Washington            | 1         | 0.34%   |
| Voronezh              | 1         | 0.34%   |
| Volta Redonda         | 1         | 0.34%   |
| Volos                 | 1         | 0.34%   |
| Vitória da Conquista | 1         | 0.34%   |
| Vincennes             | 1         | 0.34%   |
| Vilshofen             | 1         | 0.34%   |
| Vilnius               | 1         | 0.34%   |
| Villeneuve-d'Ascq     | 1         | 0.34%   |
| Villefontaine         | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 58        | 79     | 14.43%  |
| Seagate                        | 56        | 72     | 13.93%  |
| Samsung Electronics            | 53        | 79     | 13.18%  |
| SanDisk                        | 24        | 28     | 5.97%   |
| Kingston                       | 23        | 28     | 5.72%   |
| Unknown                        | 20        | 28     | 4.98%   |
| Toshiba                        | 18        | 20     | 4.48%   |
| Crucial                        | 16        | 17     | 3.98%   |
| Hitachi                        | 13        | 14     | 3.23%   |
| SK hynix                       | 11        | 12     | 2.74%   |
| Intel                          | 8         | 8      | 1.99%   |
| A-DATA Technology              | 8         | 9      | 1.99%   |
| Micron Technology              | 7         | 7      | 1.74%   |
| Apple                          | 7         | 12     | 1.74%   |
| China                          | 6         | 7      | 1.49%   |
| PNY                            | 5         | 6      | 1.24%   |
| HGST                           | 4         | 5      | 1%      |
| Phison                         | 3         | 3      | 0.75%   |
| Patriot                        | 3         | 3      | 0.75%   |
| Unknown                        | 3         | 4      | 0.75%   |
| Transcend                      | 2         | 3      | 0.5%    |
| Team                           | 2         | 2      | 0.5%    |
| SPCC                           | 2         | 2      | 0.5%    |
| KIOXIA                         | 2         | 5      | 0.5%    |
| KingSpec                       | 2         | 2      | 0.5%    |
| Intenso                        | 2         | 2      | 0.5%    |
| Gigabyte Technology            | 2         | 4      | 0.5%    |
| Fujitsu                        | 2         | 2      | 0.5%    |
| ADATA Technology               | 2         | 2      | 0.5%    |
| XrayDisk                       | 1         | 2      | 0.25%   |
| WALRAM                         | 1         | 1      | 0.25%   |
| Union Memory                   | 1         | 1      | 0.25%   |
| UMIS                           | 1         | 1      | 0.25%   |
| TGT                            | 1         | 1      | 0.25%   |
| TakeMS                         | 1         | 1      | 0.25%   |
| Star Drive                     | 1         | 1      | 0.25%   |
| SSD PHIS                       | 1         | 1      | 0.25%   |
| Solid State Storage Technology | 1         | 1      | 0.25%   |
| Silicon Motion                 | 1         | 1      | 0.25%   |
| ShiJi                          | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 7         | 1.6%    |
| Samsung SSD 850 EVO 250GB                           | 7         | 1.6%    |
| Kingston SA400S37240G 240GB SSD                     | 6         | 1.37%   |
| Samsung SSD 850 EVO 500GB                           | 5         | 1.14%   |
| Kingston SA400S37120G 120GB SSD                     | 5         | 1.14%   |
| Unknown SD/MMC/MS PRO 16GB                          | 4         | 0.92%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 0.92%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 0.92%   |
| Seagate ST500DM002-1BD142 500GB                     | 3         | 0.69%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 3         | 0.69%   |
| SanDisk NVMe SSD Drive 256GB                        | 3         | 0.69%   |
| Samsung SSD 980 PRO 1TB                             | 3         | 0.69%   |
| Samsung SSD 980 1TB                                 | 3         | 0.69%   |
| Samsung SSD 970 EVO 500GB                           | 3         | 0.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 3         | 0.69%   |
| Micron NVMe SSD Drive 512GB                         | 3         | 0.69%   |
| Crucial CT480BX500SSD1 480GB                        | 3         | 0.69%   |
| Unknown                                             | 3         | 0.69%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.46%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 2         | 0.46%   |
| WDC WD3200BEVT-60ZCT1 320GB                         | 2         | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2         | 0.46%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB                | 2         | 0.46%   |
| Unknown SC128  128GB                                | 2         | 0.46%   |
| Unknown MMC Card  64GB                              | 2         | 0.46%   |
| Unknown MMC Card  32GB                              | 2         | 0.46%   |
| Unknown MMC Card  128GB                             | 2         | 0.46%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.46%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB             | 2         | 0.46%   |
| Seagate ST9250315AS 250GB                           | 2         | 0.46%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 0.46%   |
| Seagate ST3320418AS 320GB                           | 2         | 0.46%   |
| Seagate ST3250318AS 250GB                           | 2         | 0.46%   |
| Seagate ST31500341AS 1TB                            | 2         | 0.46%   |
| Seagate ST2000LX001-1RG174 2TB                      | 2         | 0.46%   |
| Seagate ST2000DM008-2FR102 2TB                      | 2         | 0.46%   |
| Seagate ST1000LM048-2E7172 1TB                      | 2         | 0.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.46%   |
| Seagate ST1000LM014-1EJ164 1TB                      | 2         | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB                      | 2         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 56        | 71     | 37.58%  |
| WDC                 | 46        | 65     | 30.87%  |
| Toshiba             | 14        | 16     | 9.4%    |
| Hitachi             | 13        | 14     | 8.72%   |
| Samsung Electronics | 5         | 7      | 3.36%   |
| Unknown             | 4         | 4      | 2.68%   |
| HGST                | 4         | 5      | 2.68%   |
| Intenso             | 2         | 2      | 1.34%   |
| Fujitsu             | 2         | 2      | 1.34%   |
| SABRENT             | 1         | 1      | 0.67%   |
| ASMedia             | 1         | 1      | 0.67%   |
| Apple               | 1         | 1      | 0.67%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 36     | 17.57%  |
| Kingston            | 20        | 25     | 13.51%  |
| Crucial             | 15        | 16     | 10.14%  |
| SanDisk             | 11        | 12     | 7.43%   |
| A-DATA Technology   | 8         | 9      | 5.41%   |
| WDC                 | 6         | 6      | 4.05%   |
| China               | 6         | 7      | 4.05%   |
| PNY                 | 5         | 6      | 3.38%   |
| Apple               | 5         | 5      | 3.38%   |
| Intel               | 4         | 4      | 2.7%    |
| Toshiba             | 3         | 3      | 2.03%   |
| Patriot             | 3         | 3      | 2.03%   |
| Unknown             | 3         | 4      | 2.03%   |
| Transcend           | 2         | 3      | 1.35%   |
| Team                | 2         | 2      | 1.35%   |
| SK hynix            | 2         | 2      | 1.35%   |
| Micron Technology   | 2         | 2      | 1.35%   |
| KingSpec            | 2         | 2      | 1.35%   |
| Gigabyte Technology | 2         | 4      | 1.35%   |
| TakeMS              | 1         | 1      | 0.68%   |
| SSD PHIS            | 1         | 1      | 0.68%   |
| SPCC                | 1         | 1      | 0.68%   |
| ORICO               | 1         | 1      | 0.68%   |
| OCZ-VERTEX          | 1         | 1      | 0.68%   |
| Netac               | 1         | 1      | 0.68%   |
| Microtech           | 1         | 2      | 0.68%   |
| LITEON              | 1         | 1      | 0.68%   |
| Lexar               | 1         | 1      | 0.68%   |
| Initio              | 1         | 1      | 0.68%   |
| HXY                 | 1         | 1      | 0.68%   |
| Hewlett-Packard     | 1         | 1      | 0.68%   |
| GOODRAM             | 1         | 1      | 0.68%   |
| FORESEE             | 1         | 2      | 0.68%   |
| Emtec               | 1         | 1      | 0.68%   |
| Corsair             | 1         | 1      | 0.68%   |
| BHT                 | 1         | 2      | 0.68%   |
| ASMT                | 1         | 1      | 0.68%   |
| Apacer              | 1         | 1      | 0.68%   |
| Acer                | 1         | 1      | 0.68%   |
| 2.5''               | 1         | 1      | 0.68%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 131       | 189    | 35.6%   |
| SSD     | 130       | 175    | 35.33%  |
| NVMe    | 79        | 107    | 21.47%  |
| MMC     | 16        | 23     | 4.35%   |
| Unknown | 12        | 14     | 3.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 217       | 353    | 65.96%  |
| NVMe | 79        | 107    | 24.01%  |
| SAS  | 17        | 25     | 5.17%   |
| MMC  | 16        | 23     | 4.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 168       | 239    | 65.12%  |
| 0.51-1.0   | 65        | 92     | 25.19%  |
| 1.01-2.0   | 10        | 12     | 3.88%   |
| 3.01-4.0   | 7         | 10     | 2.71%   |
| 2.01-3.0   | 4         | 7      | 1.55%   |
| 4.01-10.0  | 4         | 4      | 1.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 92        | 31.83%  |
| 251-500        | 70        | 24.22%  |
| 501-1000       | 39        | 13.49%  |
| 1001-2000      | 28        | 9.69%   |
| 51-100         | 16        | 5.54%   |
| 1-20           | 12        | 4.15%   |
| More than 3000 | 11        | 3.81%   |
| 21-50          | 11        | 3.81%   |
| 2001-3000      | 10        | 3.46%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 127       | 42.62%  |
| 21-50          | 57        | 19.13%  |
| 51-100         | 32        | 10.74%  |
| 101-250        | 31        | 10.4%   |
| 501-1000       | 20        | 6.71%   |
| 251-500        | 18        | 6.04%   |
| 1001-2000      | 6         | 2.01%   |
| 2001-3000      | 4         | 1.34%   |
| More than 3000 | 3         | 1.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 5%      |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 5%      |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 5%      |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 1         | 1      | 5%      |
| Seagate ST9250315AS 250GB             | 1         | 1      | 5%      |
| Seagate ST500LT032-1E9142 500GB       | 1         | 1      | 5%      |
| Seagate ST500LT012-1DG142 500GB       | 1         | 1      | 5%      |
| Seagate ST3250318AS 250GB             | 1         | 1      | 5%      |
| Seagate ST2000DX001-1CM164 2TB        | 1         | 1      | 5%      |
| Seagate ST1000LM048-2E7172 1TB        | 1         | 1      | 5%      |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 2      | 5%      |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 5%      |
| Samsung Electronics SSD 850 EVO 500GB | 1         | 1      | 5%      |
| Samsung Electronics HM160HC 160GB     | 1         | 1      | 5%      |
| Phison ES 512GB                       | 1         | 1      | 5%      |
| Intel SSDSCKKF256G8 SATA 256GB        | 1         | 1      | 5%      |
| Intel SSDSC2CT240A3 240GB             | 1         | 1      | 5%      |
| Hitachi HTS547575A9E384 752GB         | 1         | 1      | 5%      |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 5%      |
| HGST HTS545050A7E680 500GB            | 1         | 1      | 5%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 31.58%  |
| Samsung Electronics | 4         | 5      | 21.05%  |
| Intel               | 2         | 2      | 10.53%  |
| Hitachi             | 2         | 2      | 10.53%  |
| WDC                 | 1         | 2      | 5.26%   |
| Toshiba             | 1         | 1      | 5.26%   |
| SK hynix            | 1         | 1      | 5.26%   |
| Phison              | 1         | 1      | 5.26%   |
| HGST                | 1         | 1      | 5.26%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 54.55%  |
| Hitachi             | 2         | 2      | 18.18%  |
| WDC                 | 1         | 2      | 9.09%   |
| Samsung Electronics | 1         | 1      | 9.09%   |
| HGST                | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 12     | 57.89%  |
| SSD  | 5         | 5      | 26.32%  |
| NVMe | 3         | 4      | 15.79%  |

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
| Detected | 193       | 336    | 62.06%  |
| Works    | 99        | 151    | 31.83%  |
| Malfunc  | 19        | 21     | 6.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 198       | 56.41%  |
| AMD                            | 54        | 15.38%  |
| Samsung Electronics            | 28        | 7.98%   |
| SanDisk                        | 17        | 4.84%   |
| SK hynix                       | 9         | 2.56%   |
| Phison Electronics             | 6         | 1.71%   |
| Micron Technology              | 5         | 1.42%   |
| Nvidia                         | 4         | 1.14%   |
| ASMedia Technology             | 4         | 1.14%   |
| Marvell Technology Group       | 3         | 0.85%   |
| KIOXIA                         | 3         | 0.85%   |
| Kingston Technology Company    | 3         | 0.85%   |
| JMicron Technology             | 3         | 0.85%   |
| Broadcom / LSI                 | 3         | 0.85%   |
| Union Memory (Shenzhen)        | 2         | 0.57%   |
| Micron/Crucial Technology      | 2         | 0.57%   |
| ADATA Technology               | 2         | 0.57%   |
| Toshiba America Info Systems   | 1         | 0.28%   |
| Solid State Storage Technology | 1         | 0.28%   |
| Silicon Motion                 | 1         | 0.28%   |
| LSI Logic / Symbios Logic      | 1         | 0.28%   |
| Apple                          | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 41        | 10%     |
| Intel Volume Management Device NVMe RAID Controller                              | 16        | 3.9%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 3.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 14        | 3.41%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 3.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 12        | 2.93%   |
| Samsung NVMe SSD Controller 980                                                  | 11        | 2.68%   |
| Intel Tiger Lake-LP SATA Controller                                              | 10        | 2.44%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 10        | 2.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 9         | 2.2%    |
| AMD 400 Series Chipset SATA Controller                                           | 9         | 2.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 8         | 1.95%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 8         | 1.95%   |
| SanDisk Non-Volatile memory controller                                           | 7         | 1.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 1.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 7         | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 7         | 1.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 1.71%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 6         | 1.46%   |
| Micron Non-Volatile memory controller                                            | 5         | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 5         | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 1.22%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 4         | 0.98%   |
| Phison PS5013 E13 NVMe Controller                                                | 4         | 0.98%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 4         | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 0.98%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 4         | 0.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 4         | 0.98%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 4         | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 3         | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 3         | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                               | 3         | 0.73%   |
| Intel Jasper Lake SATA AHCI Controller                                           | 3         | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.73%   |
| Intel C600/X79 series chipset IDE-r Controller                                   | 3         | 0.73%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 3         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 214       | 57.84%  |
| NVMe | 80        | 21.62%  |
| IDE  | 38        | 10.27%  |
| RAID | 34        | 9.19%   |
| SAS  | 3         | 0.81%   |
| SCSI | 1         | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 218       | 76.49%  |
| AMD    | 67        | 23.51%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 9         | 3.15%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 6         | 2.1%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 5         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 5         | 1.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 1.4%    |
| Intel Atom CPU N2600 @ 1.60GHz              | 4         | 1.4%    |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 4         | 1.4%    |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 1.4%    |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.05%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 3         | 1.05%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 3         | 1.05%   |
| Intel Xeon CPU E5-2687W 0 @ 3.10GHz         | 2         | 0.7%    |
| Intel Pentium M processor 1.73GHz           | 2         | 0.7%    |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 0.7%    |
| Intel Pentium CPU P6000 @ 1.87GHz           | 2         | 0.7%    |
| Intel Pentium CPU N3700 @ 1.60GHz           | 2         | 0.7%    |
| Intel Pentium CPU G645 @ 2.90GHz            | 2         | 0.7%    |
| Intel Core i7-9700K CPU @ 3.60GHz           | 2         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.7%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 2         | 0.7%    |
| Intel Core i7-3770 CPU @ 3.40GHz            | 2         | 0.7%    |
| Intel Core i7-3612QM CPU @ 2.10GHz          | 2         | 0.7%    |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.7%    |
| Intel Core i7 CPU Q 720 @ 1.60GHz           | 2         | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz           | 2         | 0.7%    |
| Intel Core i5-6600K CPU @ 3.50GHz           | 2         | 0.7%    |
| Intel Core i3-4010U CPU @ 1.70GHz           | 2         | 0.7%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 2         | 0.7%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz        | 2         | 0.7%    |
| Intel Celeron N5105 @ 2.00GHz               | 2         | 0.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz           | 2         | 0.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz           | 2         | 0.7%    |
| Intel Atom CPU N270 @ 1.60GHz               | 2         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics      | 2         | 0.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics      | 2         | 0.7%    |
| AMD Ryzen 5 3350G with Radeon Vega Graphics | 2         | 0.7%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 2         | 0.7%    |
| AMD Ryzen 3 3250U with Radeon Graphics      | 2         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 53        | 18.53%  |
| Intel Core i7           | 39        | 13.64%  |
| Other                   | 27        | 9.44%   |
| Intel Core i3           | 21        | 7.34%   |
| AMD Ryzen 5             | 17        | 5.94%   |
| Intel Celeron           | 15        | 5.24%   |
| AMD Ryzen 7             | 15        | 5.24%   |
| Intel Core 2 Duo        | 13        | 4.55%   |
| Intel Pentium           | 11        | 3.85%   |
| Intel Xeon              | 9         | 3.15%   |
| Intel Atom              | 9         | 3.15%   |
| AMD Ryzen 3             | 7         | 2.45%   |
| Intel Pentium Gold      | 3         | 1.05%   |
| Intel Pentium Dual-Core | 3         | 1.05%   |
| Intel Core 2 Quad       | 3         | 1.05%   |
| Intel Core 2            | 3         | 1.05%   |
| AMD A4                  | 3         | 1.05%   |
| Intel Pentium Silver    | 2         | 0.7%    |
| Intel Pentium M         | 2         | 0.7%    |
| Intel Pentium D         | 2         | 0.7%    |
| Intel Celeron M         | 2         | 0.7%    |
| AMD Ryzen 9             | 2         | 0.7%    |
| AMD FX                  | 2         | 0.7%    |
| AMD E2                  | 2         | 0.7%    |
| AMD E1                  | 2         | 0.7%    |
| AMD Athlon II X2        | 2         | 0.7%    |
| AMD Athlon              | 2         | 0.7%    |
| AMD A8                  | 2         | 0.7%    |
| AMD A10                 | 2         | 0.7%    |
| Intel Pentium Dual      | 1         | 0.35%   |
| Intel Genuine           | 1         | 0.35%   |
| Intel Core i9           | 1         | 0.35%   |
| Intel Core 2 Extreme    | 1         | 0.35%   |
| AMD Phenom II X6        | 1         | 0.35%   |
| AMD Phenom II X4        | 1         | 0.35%   |
| AMD G                   | 1         | 0.35%   |
| AMD E                   | 1         | 0.35%   |
| AMD C-50                | 1         | 0.35%   |
| AMD Athlon II           | 1         | 0.35%   |
| AMD A6                  | 1         | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 132       | 46.15%  |
| 4      | 96        | 33.57%  |
| 8      | 23        | 8.04%   |
| 6      | 20        | 6.99%   |
| 1      | 9         | 3.15%   |
| 16     | 5         | 1.75%   |
| 12     | 1         | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 279       | 97.89%  |
| 2      | 6         | 2.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 184       | 64.34%  |
| 1      | 102       | 35.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 278       | 97.54%  |
| 32-bit         | 7         | 2.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306a9    | 25        | 8.59%   |
| 0x806c1    | 19        | 6.53%   |
| 0x206a7    | 15        | 5.15%   |
| Unknown    | 13        | 4.47%   |
| 0x306c3    | 11        | 3.78%   |
| 0x1067a    | 11        | 3.78%   |
| 0x08108109 | 11        | 3.78%   |
| 0x406e3    | 9         | 3.09%   |
| 0x40651    | 9         | 3.09%   |
| 0x6fd      | 7         | 2.41%   |
| 0x08608103 | 7         | 2.41%   |
| 0x806ec    | 6         | 2.06%   |
| 0x506e3    | 6         | 2.06%   |
| 0x906ea    | 5         | 1.72%   |
| 0x806ea    | 5         | 1.72%   |
| 0x806e9    | 5         | 1.72%   |
| 0x406c4    | 5         | 1.72%   |
| 0x106e5    | 5         | 1.72%   |
| 0x906c0    | 4         | 1.37%   |
| 0x30661    | 4         | 1.37%   |
| 0x20655    | 4         | 1.37%   |
| 0x0a50000c | 4         | 1.37%   |
| 0x06006705 | 4         | 1.37%   |
| 0xa0671    | 3         | 1.03%   |
| 0x906ed    | 3         | 1.03%   |
| 0x906e9    | 3         | 1.03%   |
| 0x706a1    | 3         | 1.03%   |
| 0x6f6      | 3         | 1.03%   |
| 0x20652    | 3         | 1.03%   |
| 0x106c2    | 3         | 1.03%   |
| 0x10676    | 3         | 1.03%   |
| 0x08701021 | 3         | 1.03%   |
| 0x0800820d | 3         | 1.03%   |
| 0x06001119 | 3         | 1.03%   |
| 0x010000c8 | 3         | 1.03%   |
| 0xa0652    | 2         | 0.69%   |
| 0x90675    | 2         | 0.69%   |
| 0x806eb    | 2         | 0.69%   |
| 0x706e5    | 2         | 0.69%   |
| 0x6d8      | 2         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 29        | 10.1%   |
| IvyBridge     | 27        | 9.41%   |
| TigerLake     | 20        | 6.97%   |
| Haswell       | 20        | 6.97%   |
| SandyBridge   | 18        | 6.27%   |
| Zen+          | 15        | 5.23%   |
| Skylake       | 15        | 5.23%   |
| Unknown       | 15        | 5.23%   |
| Penryn        | 14        | 4.88%   |
| Core          | 12        | 4.18%   |
| Zen 3         | 10        | 3.48%   |
| Silvermont    | 10        | 3.48%   |
| Westmere      | 9         | 3.14%   |
| Bonnell       | 8         | 2.79%   |
| Nehalem       | 6         | 2.09%   |
| Excavator     | 6         | 2.09%   |
| Zen 2         | 5         | 1.74%   |
| Zen           | 5         | 1.74%   |
| Piledriver    | 5         | 1.74%   |
| K10           | 5         | 1.74%   |
| Tremont       | 4         | 1.39%   |
| Goldmont plus | 4         | 1.39%   |
| CometLake     | 4         | 1.39%   |
| P6            | 3         | 1.05%   |
| NetBurst      | 3         | 1.05%   |
| IceLake       | 3         | 1.05%   |
| Broadwell     | 3         | 1.05%   |
| Bobcat        | 3         | 1.05%   |
| Puma          | 2         | 0.7%    |
| Jaguar        | 2         | 0.7%    |
| Goldmont      | 1         | 0.35%   |
| Bulldozer     | 1         | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 161       | 49.39%  |
| Nvidia | 96        | 29.45%  |
| AMD    | 69        | 21.17%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 4.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 3.83%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 3.54%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 3.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 2.65%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.65%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 2.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.06%   |
| AMD Lucienne                                                                             | 7         | 2.06%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 1.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 1.47%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.47%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 5         | 1.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.47%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.47%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.18%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 1.18%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 4         | 1.18%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.18%   |
| Intel JasperLake [UHD Graphics]                                                          | 4         | 1.18%   |
| Intel HD Graphics 620                                                                    | 4         | 1.18%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.18%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.18%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 3         | 0.88%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3         | 0.88%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 3         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.88%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 0.88%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 2         | 0.59%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.59%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 2         | 0.59%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 2         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 127       | 44.25%  |
| 1 x Nvidia     | 63        | 21.95%  |
| 1 x AMD        | 53        | 18.47%  |
| Intel + Nvidia | 28        | 9.76%   |
| 2 x AMD        | 6         | 2.09%   |
| AMD + Nvidia   | 6         | 2.09%   |
| Intel + AMD    | 4         | 1.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 236       | 81.94%  |
| Proprietary | 33        | 11.46%  |
| Unknown     | 19        | 6.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 153       | 52.76%  |
| 0.01-0.5   | 45        | 15.52%  |
| 1.01-2.0   | 42        | 14.48%  |
| 0.51-1.0   | 18        | 6.21%   |
| 3.01-4.0   | 17        | 5.86%   |
| 5.01-6.0   | 6         | 2.07%   |
| 7.01-8.0   | 4         | 1.38%   |
| 2.01-3.0   | 2         | 0.69%   |
| 8.01-16.0  | 2         | 0.69%   |
| 16.01-24.0 | 1         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 39        | 13.78%  |
| LG Display              | 30        | 10.6%   |
| Chimei Innolux          | 28        | 9.89%   |
| BOE                     | 27        | 9.54%   |
| Samsung Electronics     | 26        | 9.19%   |
| Goldstar                | 15        | 5.3%    |
| Acer                    | 10        | 3.53%   |
| Dell                    | 9         | 3.18%   |
| Apple                   | 9         | 3.18%   |
| Hewlett-Packard         | 8         | 2.83%   |
| Philips                 | 6         | 2.12%   |
| BenQ                    | 6         | 2.12%   |
| Unknown                 | 5         | 1.77%   |
| Sharp                   | 5         | 1.77%   |
| LG Philips              | 5         | 1.77%   |
| InfoVision              | 5         | 1.77%   |
| Chi Mei Optoelectronics | 5         | 1.77%   |
| Lenovo                  | 4         | 1.41%   |
| HannStar                | 4         | 1.41%   |
| AOC                     | 3         | 1.06%   |
| Ancor Communications    | 3         | 1.06%   |
| SLD                     | 2         | 0.71%   |
| Sceptre Tech            | 2         | 0.71%   |
| PANDA                   | 2         | 0.71%   |
| Insignia                | 2         | 0.71%   |
| Iiyama                  | 2         | 0.71%   |
| ___                     | 1         | 0.35%   |
| ViewSonic               | 1         | 0.35%   |
| Vestel Elektronik       | 1         | 0.35%   |
| Unknown (XXX)           | 1         | 0.35%   |
| TR_                     | 1         | 0.35%   |
| Sony                    | 1         | 0.35%   |
| SKY                     | 1         | 0.35%   |
| Quanta Display          | 1         | 0.35%   |
| PLN                     | 1         | 0.35%   |
| Planar                  | 1         | 0.35%   |
| Panasonic               | 1         | 0.35%   |
| Packard Bell            | 1         | 0.35%   |
| MStar                   | 1         | 0.35%   |
| Medion                  | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 3         | 1.03%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3         | 1.03%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO3791 1920x1080 344x194mm 15.5-inch       | 3         | 1.03%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.03%   |
| SLD LCD Monitor SLD003C 1366x768 309x173mm 13.9-inch                 | 2         | 0.68%   |
| Sceptre Tech Sceptre B34 SPT0D52 2560x1080 797x334mm 34.0-inch       | 2         | 0.68%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch | 2         | 0.68%   |
| Philips PHL 242V8 PHLC219 1920x1080 527x296mm 23.8-inch              | 2         | 0.68%   |
| LG Philips LCD Monitor LPL0140 1440x900 304x190mm 14.1-inch          | 2         | 0.68%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 2         | 0.68%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch          | 2         | 0.68%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 2         | 0.68%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch      | 2         | 0.68%   |
| Chimei Innolux LCD Monitor CMN153B 1920x1080 344x193mm 15.5-inch     | 2         | 0.68%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 2         | 0.68%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch       | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 2         | 0.68%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 2         | 0.68%   |
| ___ LCDTV16 ___0101 1360x768                                         | 1         | 0.34%   |
| ViewSonic VG2230wm VSCA21E 1680x1050 474x296mm 22.0-inch             | 1         | 0.34%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                     | 1         | 0.34%   |
| Unknown LCDTV14 0101 1360x768 1600x900mm 72.3-inch                   | 1         | 0.34%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                | 1         | 0.34%   |
| Unknown LCD Monitor SAMSUNG 1366x768                                 | 1         | 0.34%   |
| Unknown LCD Monitor SAMSUNG                                          | 1         | 0.34%   |
| Unknown LCD Monitor Dell SE2717H/HX 1920x1080                        | 1         | 0.34%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1         | 0.34%   |
| TR_ LCD Monitor TR_5511 1366x768 518x333mm 24.2-inch                 | 1         | 0.34%   |
| Sony LCD Monitor TV 3840x1080                                        | 1         | 0.34%   |
| SKY TV-monitor SKY1402 3840x2160 708x398mm 32.0-inch                 | 1         | 0.34%   |
| SKY TV SKY1502 3840x2160 708x398mm 32.0-inch                         | 1         | 0.34%   |
| SKY TV SKY1502 3840x2160 1150x650mm 52.0-inch                        | 1         | 0.34%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 0.34%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch              | 1         | 0.34%   |
| Sharp LQ133M1JW02 SHP141A 1920x1080 294x165mm 13.3-inch              | 1         | 0.34%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch              | 1         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 117       | 43.01%  |
| 1366x768 (WXGA)    | 64        | 23.53%  |
| 1600x900 (HD+)     | 12        | 4.41%   |
| 3840x2160 (4K)     | 10        | 3.68%   |
| 1920x1200 (WUXGA)  | 9         | 3.31%   |
| 1680x1050 (WSXGA+) | 8         | 2.94%   |
| 1440x900 (WXGA+)   | 7         | 2.57%   |
| 1280x800 (WXGA)    | 7         | 2.57%   |
| 1024x600           | 6         | 2.21%   |
| 2560x1440 (QHD)    | 5         | 1.84%   |
| 2560x1080          | 5         | 1.84%   |
| 1280x1024 (SXGA)   | 4         | 1.47%   |
| 3440x1440          | 3         | 1.1%    |
| Unknown            | 3         | 1.1%    |
| 3840x1080          | 2         | 0.74%   |
| 2880x1800          | 2         | 0.74%   |
| 1360x768           | 2         | 0.74%   |
| 4480x1440          | 1         | 0.37%   |
| 2560x1600          | 1         | 0.37%   |
| 2256x1504          | 1         | 0.37%   |
| 1280x768           | 1         | 0.37%   |
| 1280x720 (HD)      | 1         | 0.37%   |
| 1024x768 (XGA)     | 1         | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 94        | 32.98%  |
| 13      | 30        | 10.53%  |
| Unknown | 22        | 7.72%   |
| 14      | 20        | 7.02%   |
| 24      | 18        | 6.32%   |
| 17      | 16        | 5.61%   |
| 21      | 13        | 4.56%   |
| 27      | 10        | 3.51%   |
| 23      | 10        | 3.51%   |
| 34      | 6         | 2.11%   |
| 10      | 6         | 2.11%   |
| 22      | 4         | 1.4%    |
| 20      | 4         | 1.4%    |
| 18      | 4         | 1.4%    |
| 12      | 4         | 1.4%    |
| 11      | 4         | 1.4%    |
| 31      | 3         | 1.05%   |
| 19      | 3         | 1.05%   |
| 72      | 2         | 0.7%    |
| 32      | 2         | 0.7%    |
| 84      | 1         | 0.35%   |
| 64      | 1         | 0.35%   |
| 54      | 1         | 0.35%   |
| 52      | 1         | 0.35%   |
| 40      | 1         | 0.35%   |
| 33      | 1         | 0.35%   |
| 28      | 1         | 0.35%   |
| 25      | 1         | 0.35%   |
| 16      | 1         | 0.35%   |
| 8       | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 129       | 46.74%  |
| 501-600     | 35        | 12.68%  |
| 201-300     | 28        | 10.14%  |
| 401-500     | 23        | 8.33%   |
| Unknown     | 22        | 7.97%   |
| 351-400     | 18        | 6.52%   |
| 701-800     | 9         | 3.26%   |
| 601-700     | 5         | 1.81%   |
| 1501-2000   | 3         | 1.09%   |
| 1001-1500   | 2         | 0.72%   |
| 801-900     | 1         | 0.36%   |
| 101-200     | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 194       | 74.33%  |
| 16/10   | 33        | 12.64%  |
| Unknown | 20        | 7.66%   |
| 21/9    | 8         | 3.07%   |
| 5/4     | 4         | 1.53%   |
| 4/3     | 1         | 0.38%   |
| 3/2     | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 94        | 33.33%  |
| 81-90          | 37        | 13.12%  |
| 201-250        | 36        | 12.77%  |
| Unknown        | 22        | 7.8%    |
| 71-80          | 13        | 4.61%   |
| 351-500        | 12        | 4.26%   |
| 301-350        | 10        | 3.55%   |
| 121-130        | 10        | 3.55%   |
| 251-300        | 9         | 3.19%   |
| 151-200        | 7         | 2.48%   |
| 41-50          | 6         | 2.13%   |
| 141-150        | 6         | 2.13%   |
| More than 1000 | 5         | 1.77%   |
| 61-70          | 4         | 1.42%   |
| 51-60          | 4         | 1.42%   |
| 131-140        | 4         | 1.42%   |
| 1-40           | 1         | 0.35%   |
| 501-1000       | 1         | 0.35%   |
| 91-100         | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 82        | 29.5%   |
| 101-120       | 80        | 28.78%  |
| 51-100        | 76        | 27.34%  |
| Unknown       | 22        | 7.91%   |
| 161-240       | 12        | 4.32%   |
| More than 240 | 3         | 1.08%   |
| 1-50          | 3         | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 238       | 82.07%  |
| 2     | 31        | 10.69%  |
| 0     | 18        | 6.21%   |
| 3     | 3         | 1.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 153       | 36.52%  |
| Intel                         | 131       | 31.26%  |
| Qualcomm Atheros              | 48        | 11.46%  |
| Broadcom                      | 28        | 6.68%   |
| TP-Link                       | 7         | 1.67%   |
| Broadcom Limited              | 7         | 1.67%   |
| Ralink Technology             | 6         | 1.43%   |
| Marvell Technology Group      | 5         | 1.19%   |
| Nvidia                        | 4         | 0.95%   |
| MediaTek                      | 4         | 0.95%   |
| Xiaomi                        | 2         | 0.48%   |
| Samsung Electronics           | 2         | 0.48%   |
| Ralink                        | 2         | 0.48%   |
| Huawei Technologies           | 2         | 0.48%   |
| Spreadtrum Communications     | 1         | 0.24%   |
| Sierra Wireless               | 1         | 0.24%   |
| Qualcomm                      | 1         | 0.24%   |
| OnePlus Technology (Shenzhen) | 1         | 0.24%   |
| NetGear                       | 1         | 0.24%   |
| Microchip Technology          | 1         | 0.24%   |
| Mercucys                      | 1         | 0.24%   |
| Lenovo                        | 1         | 0.24%   |
| JMicron Technology            | 1         | 0.24%   |
| IMC Networks                  | 1         | 0.24%   |
| HTC (High Tech Computer)      | 1         | 0.24%   |
| Hewlett-Packard               | 1         | 0.24%   |
| Google                        | 1         | 0.24%   |
| FIBOCOM                       | 1         | 0.24%   |
| Edimax Technology             | 1         | 0.24%   |
| Dell                          | 1         | 0.24%   |
| Davicom Semiconductor         | 1         | 0.24%   |
| Belkin Components             | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 90        | 17.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 4.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 15        | 2.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 2.74%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 1.57%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.57%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 1.57%   |
| Intel Wireless 3165                                               | 7         | 1.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.17%   |
| Intel Wireless 8260                                               | 6         | 1.17%   |
| Intel Wireless 7260                                               | 6         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.98%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 5         | 0.98%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 4         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                             | 4         | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.78%   |
| Intel Wireless 7265                                               | 4         | 0.78%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.78%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 3         | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.59%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 3         | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.59%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 0.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.59%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.59%   |
| Intel WiFi Link 5100                                              | 3         | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.59%   |
| Intel Wi-Fi 6 AX201 160MHz                                        | 3         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 96        | 39.34%  |
| Realtek Semiconductor | 61        | 25%     |
| Qualcomm Atheros      | 34        | 13.93%  |
| Broadcom              | 21        | 8.61%   |
| TP-Link               | 7         | 2.87%   |
| Ralink Technology     | 6         | 2.46%   |
| Broadcom Limited      | 6         | 2.46%   |
| MediaTek              | 3         | 1.23%   |
| Ralink                | 2         | 0.82%   |
| Xiaomi                | 1         | 0.41%   |
| Sierra Wireless       | 1         | 0.41%   |
| NetGear               | 1         | 0.41%   |
| Mercucys              | 1         | 0.41%   |
| IMC Networks          | 1         | 0.41%   |
| FIBOCOM               | 1         | 0.41%   |
| Edimax Technology     | 1         | 0.41%   |
| Belkin Components     | 1         | 0.41%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 15        | 6%      |
| Intel Wi-Fi 6 AX201                                            | 11        | 4.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 3.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 3.2%    |
| Intel Wireless 8265 / 8275                                     | 8         | 3.2%    |
| Intel Wi-Fi 6 AX200                                            | 8         | 3.2%    |
| Intel Wireless 3165                                            | 7         | 2.8%    |
| Intel Wireless 8260                                            | 6         | 2.4%    |
| Intel Wireless 7260                                            | 6         | 2.4%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 2.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 5         | 2%      |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 4         | 1.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 1.6%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4         | 1.6%    |
| Intel Wireless 7265                                            | 4         | 1.6%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 1.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 1.2%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 3         | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.2%    |
| Intel WiFi Link 5100                                           | 3         | 1.2%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 3         | 1.2%    |
| Intel Wi-Fi 6 AX201 160MHz                                     | 3         | 1.2%    |
| Intel Ultimate N WiFi Link 5300                                | 3         | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.2%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.2%    |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.2%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 2         | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 2         | 0.8%    |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 2         | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.8%    |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.8%    |
| Realtek RTL8188SU 802.11n WLAN Adapter                         | 2         | 0.8%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 2         | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 128       | 50.39%  |
| Intel                         | 70        | 27.56%  |
| Qualcomm Atheros              | 22        | 8.66%   |
| Broadcom                      | 8         | 3.15%   |
| Marvell Technology Group      | 5         | 1.97%   |
| Nvidia                        | 4         | 1.57%   |
| Samsung Electronics           | 2         | 0.79%   |
| Huawei Technologies           | 2         | 0.79%   |
| Xiaomi                        | 1         | 0.39%   |
| Spreadtrum Communications     | 1         | 0.39%   |
| Qualcomm                      | 1         | 0.39%   |
| OnePlus Technology (Shenzhen) | 1         | 0.39%   |
| Microchip Technology          | 1         | 0.39%   |
| MediaTek                      | 1         | 0.39%   |
| Lenovo                        | 1         | 0.39%   |
| JMicron Technology            | 1         | 0.39%   |
| HTC (High Tech Computer)      | 1         | 0.39%   |
| Hewlett-Packard               | 1         | 0.39%   |
| Google                        | 1         | 0.39%   |
| Davicom Semiconductor         | 1         | 0.39%   |
| Broadcom Limited              | 1         | 0.39%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 90        | 34.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 8.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 5.41%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.93%   |
| Intel Ethernet Connection I219-V                                  | 5         | 1.93%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 1.54%   |
| Intel I211 Gigabit Network Connection                             | 4         | 1.54%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.54%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.54%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 1.54%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 3         | 1.16%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 1.16%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 1.16%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.77%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.77%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.77%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.77%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2         | 0.77%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.77%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.77%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.77%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.77%   |
| Intel 82574L Gigabit Network Connection                           | 2         | 0.77%   |
| Intel 82573L Gigabit Ethernet Controller                          | 2         | 0.77%   |
| Huawei MLA-L11                                                    | 2         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.39%   |
| Spreadtrum Unisoc Phone                                           | 1         | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 238       | 50.53%  |
| WiFi     | 231       | 49.04%  |
| Modem    | 2         | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 162       | 54.36%  |
| Ethernet | 136       | 45.64%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 160       | 56.14%  |
| 1     | 116       | 40.7%   |
| 0     | 8         | 2.81%   |
| 3     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 201       | 70.03%  |
| Yes  | 86        | 29.97%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 73        | 45.34%  |
| Realtek Semiconductor           | 31        | 19.25%  |
| Foxconn / Hon Hai               | 10        | 6.21%   |
| Qualcomm Atheros Communications | 7         | 4.35%   |
| Broadcom                        | 7         | 4.35%   |
| Apple                           | 7         | 4.35%   |
| Lite-On Technology              | 6         | 3.73%   |
| Cambridge Silicon Radio         | 6         | 3.73%   |
| Dell                            | 5         | 3.11%   |
| Hewlett-Packard                 | 4         | 2.48%   |
| IMC Networks                    | 3         | 1.86%   |
| Foxconn International           | 2         | 1.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 29        | 18.01%  |
| Realtek Bluetooth Radio                                     | 21        | 13.04%  |
| Intel AX201 Bluetooth                                       | 16        | 9.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 13        | 8.07%   |
| Intel AX200 Bluetooth                                       | 7         | 4.35%   |
| Realtek  Bluetooth 4.2 Adapter                              | 6         | 3.73%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 6         | 3.73%   |
| Foxconn / Hon Hai Wireless_Device                           | 4         | 2.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                  | 3         | 1.86%   |
| Realtek RTL8821A Bluetooth                                  | 2         | 1.24%   |
| Qualcomm Atheros  Bluetooth Device                          | 2         | 1.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 2         | 1.24%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                       | 2         | 1.24%   |
| Lite-On Bluetooth Device                                    | 2         | 1.24%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 1.24%   |
| Intel Wireless-AC 3168 Bluetooth                            | 2         | 1.24%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter            | 2         | 1.24%   |
| Intel AX210 Bluetooth                                       | 2         | 1.24%   |
| HP Broadcom 2070 Bluetooth Combo                            | 2         | 1.24%   |
| Foxconn International BCM43142A0 Bluetooth module           | 2         | 1.24%   |
| Foxconn / Hon Hai Bluetooth Device                          | 2         | 1.24%   |
| Dell Wireless 370 Bluetooth Mini-card                       | 2         | 1.24%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 1.24%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                        | 2         | 1.24%   |
| Apple Bluetooth USB Host Controller                         | 2         | 1.24%   |
| Apple Bluetooth Host Controller                             | 2         | 1.24%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                     | 1         | 0.62%   |
| Realtek RTL8723B Bluetooth                                  | 1         | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                            | 1         | 0.62%   |
| IMC Networks Bluetooth Radio                                | 1         | 0.62%   |
| IMC Networks Bluetooth Device                               | 1         | 0.62%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter           | 1         | 0.62%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 0.62%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 0.62%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller             | 1         | 0.62%   |
| Foxconn / Hon Hai BCM43142A0                                | 1         | 0.62%   |
| Foxconn / Hon Hai Acer Module                               | 1         | 0.62%   |
| Foxconn / Hon Hai Acer Bluetooth module                     | 1         | 0.62%   |
| Dell BT Mini-Receiver                                       | 1         | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 212       | 56.23%  |
| AMD                                  | 78        | 20.69%  |
| Nvidia                               | 69        | 18.3%   |
| C-Media Electronics                  | 3         | 0.8%    |
| Texas Instruments                    | 2         | 0.53%   |
| JMTek                                | 2         | 0.53%   |
| GN Netcom                            | 2         | 0.53%   |
| Yamaha                               | 1         | 0.27%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.27%   |
| Sony                                 | 1         | 0.27%   |
| Realtek Semiconductor                | 1         | 0.27%   |
| Native Instruments                   | 1         | 0.27%   |
| Micro Star International             | 1         | 0.27%   |
| Logitech                             | 1         | 0.27%   |
| Generalplus Technology               | 1         | 0.27%   |
| Audioengine                          | 1         | 0.27%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 33        | 7.33%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 5.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 20        | 4.44%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 4.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 16        | 3.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 3.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 14        | 3.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 13        | 2.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 2.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 2.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 9         | 2%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 2%      |
| Intel 8 Series HD Audio Controller                                                                | 9         | 2%      |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 1.78%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.78%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.78%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.33%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.11%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.11%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.11%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.11%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 5         | 1.11%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.89%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 4         | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.89%   |
| Intel Jasper Lake HD Audio                                                                        | 4         | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.89%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 4         | 0.89%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.89%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 4         | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.67%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 37        | 28.03%  |
| SK hynix                     | 22        | 16.67%  |
| Unknown                      | 17        | 12.88%  |
| Micron Technology            | 12        | 9.09%   |
| Kingston                     | 9         | 6.82%   |
| Crucial                      | 7         | 5.3%    |
| Corsair                      | 5         | 3.79%   |
| G.Skill                      | 4         | 3.03%   |
| Nanya Technology             | 3         | 2.27%   |
| A-DATA Technology            | 3         | 2.27%   |
| Unknown (ABCD)               | 2         | 1.52%   |
| Ramaxel Technology           | 2         | 1.52%   |
| Unknown                      | 2         | 1.52%   |
| Strontium                    | 1         | 0.76%   |
| Smart                        | 1         | 0.76%   |
| Patriot Memory (PDP Systems) | 1         | 0.76%   |
| Lexar Co Limited             | 1         | 0.76%   |
| GSkill                       | 1         | 0.76%   |
| Elpida                       | 1         | 0.76%   |
| AVEXIR                       | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 2         | 1.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.41%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 1.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.41%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.41%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.41%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.41%   |
| Unknown                                                          | 2         | 1.41%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.7%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.7%    |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 0.7%    |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 1         | 0.7%    |
| Unknown RAM Module 4GB DIMM DDR3 1066MT/s                        | 1         | 0.7%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.7%    |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 1         | 0.7%    |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 0.7%    |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 1         | 0.7%    |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR2                               | 1         | 0.7%    |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.7%    |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 0.7%    |
| Unknown RAM D4 8G 8GB DIMM DDR4 2666MT/s                         | 1         | 0.7%    |
| Strontium RAM SRT4G86S0-H9H 4GB SODIMM DDR3 1067MT/s             | 1         | 0.7%    |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 1         | 0.7%    |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 0.7%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 1         | 0.7%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 0.7%    |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 1         | 0.7%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT425S6AFR6A-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |
| SK hynix RAM HMT325S6EFR8A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.7%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 54        | 46.55%  |
| DDR3    | 40        | 34.48%  |
| DDR2    | 9         | 7.76%   |
| SDRAM   | 6         | 5.17%   |
| LPDDR4  | 3         | 2.59%   |
| Unknown | 2         | 1.72%   |
| LPDDR3  | 1         | 0.86%   |
| DDR     | 1         | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 82        | 70.69%  |
| DIMM         | 29        | 25%     |
| Row Of Chips | 4         | 3.45%   |
| Unknown      | 1         | 0.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 45        | 35.43%  |
| 4096  | 33        | 25.98%  |
| 2048  | 23        | 18.11%  |
| 16384 | 16        | 12.6%   |
| 1024  | 5         | 3.94%   |
| 32768 | 4         | 3.15%   |
| 512   | 1         | 0.79%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 27        | 22.13%  |
| 1600    | 25        | 20.49%  |
| 2667    | 15        | 12.3%   |
| 2400    | 10        | 8.2%    |
| 667     | 6         | 4.92%   |
| 1333    | 5         | 4.1%    |
| 1334    | 4         | 3.28%   |
| 1067    | 4         | 3.28%   |
| Unknown | 4         | 3.28%   |
| 4199    | 2         | 1.64%   |
| 3600    | 2         | 1.64%   |
| 2133    | 2         | 1.64%   |
| 1867    | 2         | 1.64%   |
| 1866    | 2         | 1.64%   |
| 533     | 2         | 1.64%   |
| 4267    | 1         | 0.82%   |
| 3733    | 1         | 0.82%   |
| 3400    | 1         | 0.82%   |
| 3266    | 1         | 0.82%   |
| 2666    | 1         | 0.82%   |
| 2267    | 1         | 0.82%   |
| 2048    | 1         | 0.82%   |
| 1200    | 1         | 0.82%   |
| 1066    | 1         | 0.82%   |
| 800     | 1         | 0.82%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 1         | 25%     |
| Konica Minolta     | 1         | 25%     |
| Hewlett-Packard    | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Seiko Epson ET-2820 Series | 1         | 25%     |
| Konica Minolta 185         | 1         | 25%     |
| HP OfficeJet Pro 8730      | 1         | 25%     |
| Brother MFC-L2685DW        | 1         | 25%     |

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


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 33        | 18.54%  |
| Microdia                               | 18        | 10.11%  |
| IMC Networks                           | 16        | 8.99%   |
| Acer                                   | 13        | 7.3%    |
| Suyin                                  | 11        | 6.18%   |
| Realtek Semiconductor                  | 11        | 6.18%   |
| Sunplus Innovation Technology          | 10        | 5.62%   |
| Quanta                                 | 10        | 5.62%   |
| Luxvisions Innotech Limited            | 7         | 3.93%   |
| Logitech                               | 6         | 3.37%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.37%   |
| Alcor Micro                            | 5         | 2.81%   |
| Apple                                  | 4         | 2.25%   |
| Syntek                                 | 3         | 1.69%   |
| Z-Star Microelectronics                | 2         | 1.12%   |
| Silicon Motion                         | 2         | 1.12%   |
| Lenovo                                 | 2         | 1.12%   |
| Importek                               | 2         | 1.12%   |
| Huawei Technologies                    | 2         | 1.12%   |
| Creative Technology                    | 2         | 1.12%   |
| Bison Electronics                      | 2         | 1.12%   |
| Unknown                                | 1         | 0.56%   |
| Pixart Imaging                         | 1         | 0.56%   |
| OmniVision Technologies                | 1         | 0.56%   |
| MacroSilicon                           | 1         | 0.56%   |
| Lite-On Technology                     | 1         | 0.56%   |
| Intel                                  | 1         | 0.56%   |
| icSpring                               | 1         | 0.56%   |
| eMPIA Technology                       | 1         | 0.56%   |
| DLEQNA19IFK6G2                         | 1         | 0.56%   |
| ARC International                      | 1         | 0.56%   |
| ALi                                    | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 10        | 5.62%   |
| Chicony Integrated Camera                            | 9         | 5.06%   |
| Acer Integrated Camera                               | 8         | 4.49%   |
| IMC Networks Integrated Camera                       | 4         | 2.25%   |
| Chicony HP TrueVision HD Camera                      | 4         | 2.25%   |
| Chicony HD WebCam                                    | 4         | 2.25%   |
| Syntek Integrated Camera                             | 3         | 1.69%   |
| Realtek MTD camera                                   | 3         | 1.69%   |
| Realtek Lenovo EasyCamera                            | 3         | 1.69%   |
| Quanta HP TrueVision HD Camera                       | 3         | 1.69%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 1.69%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 3         | 1.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 1.69%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 3         | 1.69%   |
| Suyin HP TrueVision HD                               | 2         | 1.12%   |
| Suyin Acer HD Crystal Eye webcam                     | 2         | 1.12%   |
| Sunplus HD WebCam                                    | 2         | 1.12%   |
| Sunplus FHD Camera Microphone                        | 2         | 1.12%   |
| Quanta HP Webcam                                     | 2         | 1.12%   |
| Quanta HP HD Camera                                  | 2         | 1.12%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 2         | 1.12%   |
| Microdia CameraA                                     | 2         | 1.12%   |
| IMC Networks EasyCamera                              | 2         | 1.12%   |
| Huawei HD Webcam                                     | 2         | 1.12%   |
| Chicony HP HD Camera                                 | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam     | 2         | 1.12%   |
| Bison USB2.0 Camera                                  | 2         | 1.12%   |
| Apple Built-in iSight                                | 2         | 1.12%   |
| Alcor Micro USB Camera                               | 2         | 1.12%   |
| Z-Star WebCam SC-03FFL11739P                         | 1         | 0.56%   |
| Z-Star Venus USB2.0 Camera                           | 1         | 0.56%   |
| Unknown 720p HD Camera                               | 1         | 0.56%   |
| Suyin Lenovo EasyCamera                              | 1         | 0.56%   |
| Suyin Integrated_Webcam_HD                           | 1         | 0.56%   |
| Suyin HP Webcam-101                                  | 1         | 0.56%   |
| Suyin HD WebCam                                      | 1         | 0.56%   |
| Suyin Acer/Lenovo Webcam [CN0316]                    | 1         | 0.56%   |
| Suyin Acer CrystalEye Webcam                         | 1         | 0.56%   |
| Suyin 1.3M HD WebCam                                 | 1         | 0.56%   |
| Sunplus USB Camera                                   | 1         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 12        | 44.44%  |
| Synaptics                  | 3         | 11.11%  |
| AuthenTec                  | 3         | 11.11%  |
| Shenzhen Goodix Technology | 2         | 7.41%   |
| Upek                       | 1         | 3.7%    |
| STMicroelectronics         | 1         | 3.7%    |
| Samsung Electronics        | 1         | 3.7%    |
| Microsoft                  | 1         | 3.7%    |
| LighTuning Technology      | 1         | 3.7%    |
| Focal-systems.Corp         | 1         | 3.7%    |
| Elan Microelectronics      | 1         | 3.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 3         | 11.11%  |
| Unknown                                                | 3         | 11.11%  |
| Validity Sensors Synaptics WBDI                        | 2         | 7.41%   |
| Shenzhen Goodix  FingerPrint Device                    | 2         | 7.41%   |
| AuthenTec AES1600                                      | 2         | 7.41%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 3.7%    |
| Validity Sensors VFS491                                | 1         | 3.7%    |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 3.7%    |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 3.7%    |
| Validity Sensors VFS Fingerprint sensor                | 1         | 3.7%    |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 3.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 3.7%    |
| STMicroelectronics Fingerprint Reader                  | 1         | 3.7%    |
| Samsung Fingerprint Sensor Device - 730B               | 1         | 3.7%    |
| Microsoft Fingerprint Reader                           | 1         | 3.7%    |
| LighTuning Fingerprint Reader                          | 1         | 3.7%    |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 3.7%    |
| Elan ELAN:Fingerprint                                  | 1         | 3.7%    |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 50%     |
| O2 Micro    | 2         | 20%     |
| Alcor Micro | 2         | 20%     |
| Lenovo      | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                          | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor | 3         | 30%     |
| O2 Micro OZ776 CCID Smartcard Reader           | 2         | 20%     |
| Alcor Micro AU9540 Smartcard Reader            | 2         | 20%     |
| Lenovo Integrated Smart Card Reader            | 1         | 10%     |
| Broadcom 5880                                  | 1         | 10%     |
| Broadcom 58200                                 | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 196       | 67.12%  |
| 1     | 81        | 27.74%  |
| 2     | 13        | 4.45%   |
| 4     | 1         | 0.34%   |
| 3     | 1         | 0.34%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 28        | 24.78%  |
| Net/wireless             | 26        | 23.01%  |
| Fingerprint reader       | 26        | 23.01%  |
| Multimedia controller    | 15        | 13.27%  |
| Chipcard                 | 9         | 7.96%   |
| Communication controller | 3         | 2.65%   |
| Unassigned class         | 1         | 0.88%   |
| Storage/raid             | 1         | 0.88%   |
| Dvb card                 | 1         | 0.88%   |
| Card reader              | 1         | 0.88%   |
| Camera                   | 1         | 0.88%   |
| Bluetooth                | 1         | 0.88%   |

