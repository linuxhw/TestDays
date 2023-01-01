Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

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

Total: 4564

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2c31fd54e4](https://linux-hardware.org/?probe=2c31fd54e4) | Jan 01, 2023 |
| Acer          | Spin SP513-54N              | Convertible | [0cb6dfa7ce](https://linux-hardware.org/?probe=0cb6dfa7ce) | Dec 31, 2022 |
| Dell          | 0PTTT9 A00                  | Desktop     | [7f2851fcf5](https://linux-hardware.org/?probe=7f2851fcf5) | Dec 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c4eccac7c7](https://linux-hardware.org/?probe=c4eccac7c7) | Dec 31, 2022 |
| MSI           | B360M BAZOOKA               | Desktop     | [ad26afeb83](https://linux-hardware.org/?probe=ad26afeb83) | Dec 31, 2022 |
| HP            | Notebook                    | Notebook    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Radxa         | ROCK 5B                     | Soc         | [d864d2a31b](https://linux-hardware.org/?probe=d864d2a31b) | Dec 30, 2022 |
| Notebook      | P17SM                       | Notebook    | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | Notebook    | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [fdd6af96b3](https://linux-hardware.org/?probe=fdd6af96b3) | Dec 30, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1c7a329282](https://linux-hardware.org/?probe=1c7a329282) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| BESSTAR Te... | HM80                        | Desktop     | [9af0f05e7e](https://linux-hardware.org/?probe=9af0f05e7e) | Dec 29, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [87e8ae1350](https://linux-hardware.org/?probe=87e8ae1350) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | Notebook    | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| HP            | 8399                        | Desktop     | [204c8c0a3f](https://linux-hardware.org/?probe=204c8c0a3f) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | Desktop     | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [52b38cee5c](https://linux-hardware.org/?probe=52b38cee5c) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [742c9ebcca](https://linux-hardware.org/?probe=742c9ebcca) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [9e95c7e7c7](https://linux-hardware.org/?probe=9e95c7e7c7) | Dec 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [2c2bf7f512](https://linux-hardware.org/?probe=2c2bf7f512) | Dec 28, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [19f962298b](https://linux-hardware.org/?probe=19f962298b) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [9d2542cf36](https://linux-hardware.org/?probe=9d2542cf36) | Dec 27, 2022 |
| Dell          | 0PV9DG A01                  | Server      | [7f408923fa](https://linux-hardware.org/?probe=7f408923fa) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | Notebook    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | Notebook    | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f2998cdede](https://linux-hardware.org/?probe=f2998cdede) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| HP            | Beats 15                    | Notebook    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Dell          | Inspiron 5775               | Notebook    | [cfb1c3fcd6](https://linux-hardware.org/?probe=cfb1c3fcd6) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | Notebook    | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [227a5cc570](https://linux-hardware.org/?probe=227a5cc570) | Dec 26, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8d9b11c617](https://linux-hardware.org/?probe=8d9b11c617) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| Acer          | Aspire A517-53              | Notebook    | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [3d538213fc](https://linux-hardware.org/?probe=3d538213fc) | Dec 25, 2022 |
| Dell          | Inspiron 7706 2n1           | Convertible | [7bf95eb194](https://linux-hardware.org/?probe=7bf95eb194) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [3672c73d5a](https://linux-hardware.org/?probe=3672c73d5a) | Dec 24, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | Notebook    | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | Notebook    | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [7b79249b18](https://linux-hardware.org/?probe=7b79249b18) | Dec 23, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [af0433651a](https://linux-hardware.org/?probe=af0433651a) | Dec 22, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion dv7                | Notebook    | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| SGIN          | laptop                      | Notebook    | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | Notebook    | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [dca79c9d6d](https://linux-hardware.org/?probe=dca79c9d6d) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| HP            | Sona                        | Notebook    | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | Notebook    | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [3d563943d4](https://linux-hardware.org/?probe=3d563943d4) | Dec 20, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [44cdfa03bf](https://linux-hardware.org/?probe=44cdfa03bf) | Dec 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d5d8eaf2b9](https://linux-hardware.org/?probe=d5d8eaf2b9) | Dec 19, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [a683e4f3c9](https://linux-hardware.org/?probe=a683e4f3c9) | Dec 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [60a56500f1](https://linux-hardware.org/?probe=60a56500f1) | Dec 18, 2022 |
| Dell          | Precision 5540              | Notebook    | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1cbc80c6fb](https://linux-hardware.org/?probe=1cbc80c6fb) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [db147cf534](https://linux-hardware.org/?probe=db147cf534) | Dec 17, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [fa2cc2d975](https://linux-hardware.org/?probe=fa2cc2d975) | Dec 17, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [c2eff145f7](https://linux-hardware.org/?probe=c2eff145f7) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [9b51850f9d](https://linux-hardware.org/?probe=9b51850f9d) | Dec 17, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [7739bbf37e](https://linux-hardware.org/?probe=7739bbf37e) | Dec 16, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [645efe8dd2](https://linux-hardware.org/?probe=645efe8dd2) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [dabf78159d](https://linux-hardware.org/?probe=dabf78159d) | Dec 15, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | Notebook    | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [89166d1da4](https://linux-hardware.org/?probe=89166d1da4) | Dec 15, 2022 |
| Lenovo        | NOK                         | Desktop     | [01d1b7fdb7](https://linux-hardware.org/?probe=01d1b7fdb7) | Dec 15, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [9e9573c0c5](https://linux-hardware.org/?probe=9e9573c0c5) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [aad5a91184](https://linux-hardware.org/?probe=aad5a91184) | Dec 14, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [c428800285](https://linux-hardware.org/?probe=c428800285) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Lenovo        | ThinkPad T61 7665VJM        | Notebook    | [f1ff113e65](https://linux-hardware.org/?probe=f1ff113e65) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [895bd1b0b2](https://linux-hardware.org/?probe=895bd1b0b2) | Dec 13, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [c18a20ec35](https://linux-hardware.org/?probe=c18a20ec35) | Dec 13, 2022 |
| Acer          | Nitro AN517-54              | Notebook    | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | Notebook    | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| ASUSTek       | H170-PRO                    | Desktop     | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [c5220a0b87](https://linux-hardware.org/?probe=c5220a0b87) | Dec 11, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| ASRock        | H570 Steel Legend           | Desktop     | [ef9d66faf0](https://linux-hardware.org/?probe=ef9d66faf0) | Dec 11, 2022 |
| HP            | Pavilion g7                 | Notebook    | [94cc8be22c](https://linux-hardware.org/?probe=94cc8be22c) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | Notebook    | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [1168ac14f5](https://linux-hardware.org/?probe=1168ac14f5) | Dec 09, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [3892b54ac4](https://linux-hardware.org/?probe=3892b54ac4) | Dec 08, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [8745419f51](https://linux-hardware.org/?probe=8745419f51) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | Notebook    | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| Lenovo        | ThinkSystem SR358FV2 Res... | Server      | [3702b80721](https://linux-hardware.org/?probe=3702b80721) | Dec 07, 2022 |
| AZW           | S3                          | Mini pc     | [3f05394ddc](https://linux-hardware.org/?probe=3f05394ddc) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | Notebook    | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [55e56516e5](https://linux-hardware.org/?probe=55e56516e5) | Dec 06, 2022 |
| HP            | Beats 15                    | Notebook    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| HP            | 550                         | Notebook    | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| ASRock        | B660M Pro RS                | Desktop     | [0a1500b793](https://linux-hardware.org/?probe=0a1500b793) | Dec 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [eced972f80](https://linux-hardware.org/?probe=eced972f80) | Dec 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [d37c93af89](https://linux-hardware.org/?probe=d37c93af89) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [fb233e5dc1](https://linux-hardware.org/?probe=fb233e5dc1) | Dec 05, 2022 |
| Lenovo        | Tilapia CRB                 | Desktop     | [a32aaf0f8c](https://linux-hardware.org/?probe=a32aaf0f8c) | Dec 05, 2022 |
| HP            | EliteBook x360 1040 G5      | Convertible | [02c80899f7](https://linux-hardware.org/?probe=02c80899f7) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| Monster       | TULPAR T7 V21.6             | Notebook    | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | Notebook    | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [36ef5b0deb](https://linux-hardware.org/?probe=36ef5b0deb) | Dec 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [23f903a61d](https://linux-hardware.org/?probe=23f903a61d) | Dec 03, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [db7e5686f3](https://linux-hardware.org/?probe=db7e5686f3) | Dec 03, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | Notebook    | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [5b17c3205f](https://linux-hardware.org/?probe=5b17c3205f) | Dec 03, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [dc233f857f](https://linux-hardware.org/?probe=dc233f857f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | Notebook    | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | Notebook    | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Google        | Kled                        | Notebook    | [06c52b65d2](https://linux-hardware.org/?probe=06c52b65d2) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1b361e2f17](https://linux-hardware.org/?probe=1b361e2f17) | Dec 02, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [57b5a73c5d](https://linux-hardware.org/?probe=57b5a73c5d) | Dec 01, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9866b7f07f](https://linux-hardware.org/?probe=9866b7f07f) | Dec 01, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [0a012accfd](https://linux-hardware.org/?probe=0a012accfd) | Dec 01, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| System76      | Thelio thelio-r1            | Desktop     | [76343aa234](https://linux-hardware.org/?probe=76343aa234) | Dec 01, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [ca277bb16c](https://linux-hardware.org/?probe=ca277bb16c) | Nov 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [1c30aa7bcd](https://linux-hardware.org/?probe=1c30aa7bcd) | Nov 30, 2022 |
| Haier         | A1420EM                     | Notebook    | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | Desktop     | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d233ee2114](https://linux-hardware.org/?probe=d233ee2114) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3a64631617](https://linux-hardware.org/?probe=3a64631617) | Nov 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fc681f2f42](https://linux-hardware.org/?probe=fc681f2f42) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [a92a0830e9](https://linux-hardware.org/?probe=a92a0830e9) | Nov 30, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [12492cb99a](https://linux-hardware.org/?probe=12492cb99a) | Nov 29, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [92afc95831](https://linux-hardware.org/?probe=92afc95831) | Nov 29, 2022 |
| Razer         | Blade Stealth               | Notebook    | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8f17b6a915](https://linux-hardware.org/?probe=8f17b6a915) | Nov 29, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [f2c8b52293](https://linux-hardware.org/?probe=f2c8b52293) | Nov 28, 2022 |
| Dell          | G3 3779                     | Notebook    | [3e85396dae](https://linux-hardware.org/?probe=3e85396dae) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | Notebook    | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Medion        | TJ4125                      | Desktop     | [a1c7ac96d3](https://linux-hardware.org/?probe=a1c7ac96d3) | Nov 27, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Dell          | G3 3779                     | Notebook    | [2def46f37c](https://linux-hardware.org/?probe=2def46f37c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | Notebook    | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [e3c2051d8f](https://linux-hardware.org/?probe=e3c2051d8f) | Nov 26, 2022 |
| Monster       | TULPAR T7                   | Notebook    | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Toshiba       | Satellite C670D-126         | Notebook    | [6c2fc84bf2](https://linux-hardware.org/?probe=6c2fc84bf2) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| GPD           | G1621-02                    | Notebook    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [348f786878](https://linux-hardware.org/?probe=348f786878) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Unknown       | HX90                        | Desktop     | [e1bd045aaa](https://linux-hardware.org/?probe=e1bd045aaa) | Nov 24, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [601fd47da1](https://linux-hardware.org/?probe=601fd47da1) | Nov 24, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [e47ce764e1](https://linux-hardware.org/?probe=e47ce764e1) | Nov 24, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [6d3657ecde](https://linux-hardware.org/?probe=6d3657ecde) | Nov 23, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [f396cc27ff](https://linux-hardware.org/?probe=f396cc27ff) | Nov 23, 2022 |
| AZW           | SEi                         | Desktop     | [deace4a3d6](https://linux-hardware.org/?probe=deace4a3d6) | Nov 23, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [1bed000f1a](https://linux-hardware.org/?probe=1bed000f1a) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Intel         | NUC12WSBi7 M46422-302       | Mini pc     | [d876db7f78](https://linux-hardware.org/?probe=d876db7f78) | Nov 22, 2022 |
| Dell          | Latitude 5410               | Notebook    | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [498c078586](https://linux-hardware.org/?probe=498c078586) | Nov 21, 2022 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [abda5b4aaf](https://linux-hardware.org/?probe=abda5b4aaf) | Nov 21, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| Dell          | 0XPDFK A01                  | Desktop     | [1332a048d4](https://linux-hardware.org/?probe=1332a048d4) | Nov 21, 2022 |
| HP            | Unknown                     | Notebook    | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| HP            | 845A                        | Desktop     | [330b46ea11](https://linux-hardware.org/?probe=330b46ea11) | Nov 20, 2022 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [e4514feafe](https://linux-hardware.org/?probe=e4514feafe) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | Notebook    | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7a30c89c58](https://linux-hardware.org/?probe=7a30c89c58) | Nov 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [87c95f019e](https://linux-hardware.org/?probe=87c95f019e) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | Notebook    | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| Toshiba       | Satellite C670D-126         | Notebook    | [17e464f802](https://linux-hardware.org/?probe=17e464f802) | Nov 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [0734f58b03](https://linux-hardware.org/?probe=0734f58b03) | Nov 18, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | Notebook    | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [e1b586a15a](https://linux-hardware.org/?probe=e1b586a15a) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| Unknown       | Unknown                     | Desktop     | [554da2ef73](https://linux-hardware.org/?probe=554da2ef73) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | Notebook    | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [dbbfcd826c](https://linux-hardware.org/?probe=dbbfcd826c) | Nov 18, 2022 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [3491c5eef1](https://linux-hardware.org/?probe=3491c5eef1) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [86026bcc45](https://linux-hardware.org/?probe=86026bcc45) | Nov 17, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [aa5d7dc8a0](https://linux-hardware.org/?probe=aa5d7dc8a0) | Nov 17, 2022 |
| ASRock        | B560M-ITX/ac                | Desktop     | [c8f725f9cd](https://linux-hardware.org/?probe=c8f725f9cd) | Nov 17, 2022 |
| ASUSTek       | TUF Z270 MARK 1             | Desktop     | [dc1aa01b01](https://linux-hardware.org/?probe=dc1aa01b01) | Nov 17, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [df66428cab](https://linux-hardware.org/?probe=df66428cab) | Nov 17, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | Notebook    | [cc20cc9828](https://linux-hardware.org/?probe=cc20cc9828) | Nov 16, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [e7152e6cb3](https://linux-hardware.org/?probe=e7152e6cb3) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [a30ec58d99](https://linux-hardware.org/?probe=a30ec58d99) | Nov 16, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [5e42accb39](https://linux-hardware.org/?probe=5e42accb39) | Nov 16, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [8e4ab9c969](https://linux-hardware.org/?probe=8e4ab9c969) | Nov 16, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [2ff36bc758](https://linux-hardware.org/?probe=2ff36bc758) | Nov 16, 2022 |
| Dell          | Latitude E7250              | Notebook    | [907a7245b4](https://linux-hardware.org/?probe=907a7245b4) | Nov 15, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [12fe5843d1](https://linux-hardware.org/?probe=12fe5843d1) | Nov 15, 2022 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [6f1cef8a17](https://linux-hardware.org/?probe=6f1cef8a17) | Nov 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [04a6897f33](https://linux-hardware.org/?probe=04a6897f33) | Nov 15, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [22b0ad0cb0](https://linux-hardware.org/?probe=22b0ad0cb0) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [ea0093a1f6](https://linux-hardware.org/?probe=ea0093a1f6) | Nov 15, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [9d013ae9aa](https://linux-hardware.org/?probe=9d013ae9aa) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | Notebook    | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Dell          | Precision 7510              | Notebook    | [111903e578](https://linux-hardware.org/?probe=111903e578) | Nov 14, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [d22c86a486](https://linux-hardware.org/?probe=d22c86a486) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [f588871a3a](https://linux-hardware.org/?probe=f588871a3a) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [5086b0aa3e](https://linux-hardware.org/?probe=5086b0aa3e) | Nov 14, 2022 |
| Gigabyte      | GA-MA790FX-DS5              | Desktop     | [63bba2efec](https://linux-hardware.org/?probe=63bba2efec) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | Notebook    | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [e0edc946f9](https://linux-hardware.org/?probe=e0edc946f9) | Nov 13, 2022 |
| Supermicro    | X9DAL                       | Desktop     | [56d4bd9f26](https://linux-hardware.org/?probe=56d4bd9f26) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | Notebook    | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [733739e049](https://linux-hardware.org/?probe=733739e049) | Nov 12, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | Notebook    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Google        | Celes                       | Notebook    | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | Notebook    | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| ASRock        | B75M                        | Desktop     | [7da4910326](https://linux-hardware.org/?probe=7da4910326) | Nov 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a8145bf5ce](https://linux-hardware.org/?probe=a8145bf5ce) | Nov 12, 2022 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [c22a4715da](https://linux-hardware.org/?probe=c22a4715da) | Nov 12, 2022 |
| Timi          | TM1703                      | Notebook    | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [518979e264](https://linux-hardware.org/?probe=518979e264) | Nov 11, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d020fa04fe](https://linux-hardware.org/?probe=d020fa04fe) | Nov 11, 2022 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [72773d35e0](https://linux-hardware.org/?probe=72773d35e0) | Nov 11, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a9a0e77be4](https://linux-hardware.org/?probe=a9a0e77be4) | Nov 11, 2022 |
| ASRock        | X99 Extreme4                | Desktop     | [00da120cde](https://linux-hardware.org/?probe=00da120cde) | Nov 11, 2022 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [d5b955a7b3](https://linux-hardware.org/?probe=d5b955a7b3) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| Dell          | 0773VG A00                  | Desktop     | [2ffe6c18f7](https://linux-hardware.org/?probe=2ffe6c18f7) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | Notebook    | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [ffa33ab238](https://linux-hardware.org/?probe=ffa33ab238) | Nov 10, 2022 |
| Samsung       | 950QED                      | Convertible | [c68fd01b4c](https://linux-hardware.org/?probe=c68fd01b4c) | Nov 10, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6531f0596d](https://linux-hardware.org/?probe=6531f0596d) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | Notebook    | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | Notebook    | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | Notebook    | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| HP            | Laptop 17-ca2xxx            | Notebook    | [a31e9f30cc](https://linux-hardware.org/?probe=a31e9f30cc) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [a72c604f03](https://linux-hardware.org/?probe=a72c604f03) | Nov 09, 2022 |
| Dell          | 0PGKWF A02                  | Desktop     | [d123f535c1](https://linux-hardware.org/?probe=d123f535c1) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | Notebook    | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8ba7f1aa17](https://linux-hardware.org/?probe=8ba7f1aa17) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [c08b835f58](https://linux-hardware.org/?probe=c08b835f58) | Nov 07, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | Notebook    | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [16b7880c43](https://linux-hardware.org/?probe=16b7880c43) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a734aa34bf](https://linux-hardware.org/?probe=a734aa34bf) | Nov 07, 2022 |
| Gigabyte      | B660M D3H DDR4              | Desktop     | [64aed4564c](https://linux-hardware.org/?probe=64aed4564c) | Nov 07, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8ef47e1adb](https://linux-hardware.org/?probe=8ef47e1adb) | Nov 06, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [83a24172bd](https://linux-hardware.org/?probe=83a24172bd) | Nov 06, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d29197ed66](https://linux-hardware.org/?probe=d29197ed66) | Nov 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [317efeba98](https://linux-hardware.org/?probe=317efeba98) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [8be58df3e0](https://linux-hardware.org/?probe=8be58df3e0) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e5684c9b19](https://linux-hardware.org/?probe=e5684c9b19) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | Notebook    | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| Dell          | 0HV8FN A01                  | Desktop     | [e77651313c](https://linux-hardware.org/?probe=e77651313c) | Nov 04, 2022 |
| Dell          | 0HV8FN A01                  | Desktop     | [7a28d76fe6](https://linux-hardware.org/?probe=7a28d76fe6) | Nov 04, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [95729b1578](https://linux-hardware.org/?probe=95729b1578) | Nov 04, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [c4b2b4072b](https://linux-hardware.org/?probe=c4b2b4072b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | Notebook    | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db852ba394](https://linux-hardware.org/?probe=db852ba394) | Nov 03, 2022 |
| Dell          | Latitude E6320              | Notebook    | [b66269072e](https://linux-hardware.org/?probe=b66269072e) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [df76e744d7](https://linux-hardware.org/?probe=df76e744d7) | Nov 02, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [760c526784](https://linux-hardware.org/?probe=760c526784) | Nov 02, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [fba864b37c](https://linux-hardware.org/?probe=fba864b37c) | Nov 02, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e4dfd41fa4](https://linux-hardware.org/?probe=e4dfd41fa4) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [4f1e0d9702](https://linux-hardware.org/?probe=4f1e0d9702) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [842320d7b3](https://linux-hardware.org/?probe=842320d7b3) | Nov 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7b42bc51be](https://linux-hardware.org/?probe=7b42bc51be) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | Notebook    | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [caffb9ebd7](https://linux-hardware.org/?probe=caffb9ebd7) | Nov 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [50d2f412f0](https://linux-hardware.org/?probe=50d2f412f0) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [722ae37952](https://linux-hardware.org/?probe=722ae37952) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [77ccdee0fe](https://linux-hardware.org/?probe=77ccdee0fe) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [27b07caa39](https://linux-hardware.org/?probe=27b07caa39) | Oct 31, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [865aef7529](https://linux-hardware.org/?probe=865aef7529) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [1e0daee604](https://linux-hardware.org/?probe=1e0daee604) | Oct 30, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| Shuttle       | FH61R                       | Desktop     | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| EVGA          | 122-CK-NF68 2               | Desktop     | [91b3144c5c](https://linux-hardware.org/?probe=91b3144c5c) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7047610fd9](https://linux-hardware.org/?probe=7047610fd9) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [883100c74f](https://linux-hardware.org/?probe=883100c74f) | Oct 29, 2022 |
| Google        | Kench                       | Desktop     | [faf24fddcd](https://linux-hardware.org/?probe=faf24fddcd) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [629858e96c](https://linux-hardware.org/?probe=629858e96c) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| Dell          | Latitude 5521               | Notebook    | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Dell          | 0KRC95 A02                  | Desktop     | [8afc3da46d](https://linux-hardware.org/?probe=8afc3da46d) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [c33d6de923](https://linux-hardware.org/?probe=c33d6de923) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | Notebook    | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| HP            | 844C                        | Desktop     | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [abe170cf19](https://linux-hardware.org/?probe=abe170cf19) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [3acf0ca326](https://linux-hardware.org/?probe=3acf0ca326) | Oct 26, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | Notebook    | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [94fa6196b8](https://linux-hardware.org/?probe=94fa6196b8) | Oct 25, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [20df7ad008](https://linux-hardware.org/?probe=20df7ad008) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| Sony          | VAIO                        | All in one  | [27e76b1c76](https://linux-hardware.org/?probe=27e76b1c76) | Oct 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6a9d81591f](https://linux-hardware.org/?probe=6a9d81591f) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | Notebook    | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [daa76e4b78](https://linux-hardware.org/?probe=daa76e4b78) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [65c39a9702](https://linux-hardware.org/?probe=65c39a9702) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [f42213926f](https://linux-hardware.org/?probe=f42213926f) | Oct 24, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [aaf3b72437](https://linux-hardware.org/?probe=aaf3b72437) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| Dell          | 0RW199                      | Desktop     | [dc99b64e62](https://linux-hardware.org/?probe=dc99b64e62) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | Notebook    | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [21db3e8ee8](https://linux-hardware.org/?probe=21db3e8ee8) | Oct 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ddc08ffe48](https://linux-hardware.org/?probe=ddc08ffe48) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [a9de489f26](https://linux-hardware.org/?probe=a9de489f26) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Haier         | A1420EM                     | Notebook    | [62ce3535b2](https://linux-hardware.org/?probe=62ce3535b2) | Oct 19, 2022 |
| Haier         | A1420EM                     | Notebook    | [a50bc27e31](https://linux-hardware.org/?probe=a50bc27e31) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | Notebook    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [1066d54fec](https://linux-hardware.org/?probe=1066d54fec) | Oct 18, 2022 |
| Gigabyte      | MX33-BS0-00 00010001        | Server      | [abfee9c5f7](https://linux-hardware.org/?probe=abfee9c5f7) | Oct 18, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| AZW           | SER V01                     | Mini pc     | [b106ebaef6](https://linux-hardware.org/?probe=b106ebaef6) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | Desktop     | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| Dell          | Precision 3570              | Notebook    | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [159150cc56](https://linux-hardware.org/?probe=159150cc56) | Oct 17, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| JWIPC         | A320I S1                    | Desktop     | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c22c1df016](https://linux-hardware.org/?probe=c22c1df016) | Oct 15, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Latitude E6420              | Notebook    | [f39e0305c5](https://linux-hardware.org/?probe=f39e0305c5) | Oct 13, 2022 |
| Dell          | Precision M6700             | Notebook    | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [2813d441b5](https://linux-hardware.org/?probe=2813d441b5) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [4039ed6d6f](https://linux-hardware.org/?probe=4039ed6d6f) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [7c58857f43](https://linux-hardware.org/?probe=7c58857f43) | Oct 11, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [7a11da121e](https://linux-hardware.org/?probe=7a11da121e) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Acer          | Aspire G7750                | Desktop     | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| Medion        | H110H4-EM2                  | Desktop     | [7bd38709d3](https://linux-hardware.org/?probe=7bd38709d3) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| LG Electro... | 16T90P-K.ADB9U1             | Convertible | [7242c5df58](https://linux-hardware.org/?probe=7242c5df58) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | Notebook    | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| ASRock        | A75M                        | Desktop     | [b3df324d02](https://linux-hardware.org/?probe=b3df324d02) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| MSI           | B150 PC MATE                | Desktop     | [d4a4eaeb7d](https://linux-hardware.org/?probe=d4a4eaeb7d) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [8a89e7f4da](https://linux-hardware.org/?probe=8a89e7f4da) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| Dell          | 0C27VV A00                  | Desktop     | [0866f99d43](https://linux-hardware.org/?probe=0866f99d43) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [236a43a0ce](https://linux-hardware.org/?probe=236a43a0ce) | Oct 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [84ba2e1db1](https://linux-hardware.org/?probe=84ba2e1db1) | Oct 05, 2022 |
| HP            | Compaq 15                   | Notebook    | [bba22531ad](https://linux-hardware.org/?probe=bba22531ad) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| HP            | Compaq 15                   | Notebook    | [0f48335990](https://linux-hardware.org/?probe=0f48335990) | Oct 05, 2022 |
| Intel         | W7645                       | Notebook    | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [bc05c332e6](https://linux-hardware.org/?probe=bc05c332e6) | Oct 04, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| LG Electro... | 16T90P-K.ADB9U1             | Convertible | [d5bbcb7c9b](https://linux-hardware.org/?probe=d5bbcb7c9b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [76709f5d09](https://linux-hardware.org/?probe=76709f5d09) | Oct 04, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [eb5e8725ae](https://linux-hardware.org/?probe=eb5e8725ae) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [6e0ea7e989](https://linux-hardware.org/?probe=6e0ea7e989) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Gateway       | DX4850                      | Desktop     | [419e3338fb](https://linux-hardware.org/?probe=419e3338fb) | Oct 02, 2022 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [b9f2861719](https://linux-hardware.org/?probe=b9f2861719) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [08db9e8d75](https://linux-hardware.org/?probe=08db9e8d75) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [e38fd71e40](https://linux-hardware.org/?probe=e38fd71e40) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [2b78a7c7f1](https://linux-hardware.org/?probe=2b78a7c7f1) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [4b198e87aa](https://linux-hardware.org/?probe=4b198e87aa) | Sep 28, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | Desktop     | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [541a21ceb8](https://linux-hardware.org/?probe=541a21ceb8) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| Dell          | Latitude E5400              | Notebook    | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | Desktop     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | Pavilion 14                 | Notebook    | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| AZW           | SER                         | Mini pc     | [9e9ee5be74](https://linux-hardware.org/?probe=9e9ee5be74) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [2a27e3cb58](https://linux-hardware.org/?probe=2a27e3cb58) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [f52114ac39](https://linux-hardware.org/?probe=f52114ac39) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Acer          | Aspire G7750                | Desktop     | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Google        | Blooglet                    | Notebook    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [97b748d5d3](https://linux-hardware.org/?probe=97b748d5d3) | Sep 16, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Dell          | Latitude 7430               | Notebook    | [4fdf1a303c](https://linux-hardware.org/?probe=4fdf1a303c) | Sep 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| Google        | Treeya                      | Notebook    | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [eb49db3a8c](https://linux-hardware.org/?probe=eb49db3a8c) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [356956ad10](https://linux-hardware.org/?probe=356956ad10) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [8aac6d779b](https://linux-hardware.org/?probe=8aac6d779b) | Sep 13, 2022 |
| Unknown       | Unknown                     | Other       | [1e94b50834](https://linux-hardware.org/?probe=1e94b50834) | Sep 12, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | Notebook    | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [1634db2e78](https://linux-hardware.org/?probe=1634db2e78) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Dell          | Latitude 7430               | Notebook    | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b50a1bc29b](https://linux-hardware.org/?probe=b50a1bc29b) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Acer          | Predator G3-571             | Notebook    | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| MSI           | Z97-G43                     | Desktop     | [eeea153bb2](https://linux-hardware.org/?probe=eeea153bb2) | Sep 06, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [8a1c5532d6](https://linux-hardware.org/?probe=8a1c5532d6) | Sep 06, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5c53e30fe6](https://linux-hardware.org/?probe=5c53e30fe6) | Sep 06, 2022 |
| HP            | 2B3E                        | All in one  | [4ccdce6df9](https://linux-hardware.org/?probe=4ccdce6df9) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [d496e01f0e](https://linux-hardware.org/?probe=d496e01f0e) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| HP            | Notebook                    | Notebook    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [71ff7749aa](https://linux-hardware.org/?probe=71ff7749aa) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0789b27bdb](https://linux-hardware.org/?probe=0789b27bdb) | Sep 02, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [33784347f5](https://linux-hardware.org/?probe=33784347f5) | Sep 02, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [e93c1732ec](https://linux-hardware.org/?probe=e93c1732ec) | Sep 02, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [f77ecfe3bc](https://linux-hardware.org/?probe=f77ecfe3bc) | Sep 02, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [27840cf8d2](https://linux-hardware.org/?probe=27840cf8d2) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [b99f4a264b](https://linux-hardware.org/?probe=b99f4a264b) | Sep 01, 2022 |
| ASUSTek       | P5K/EPU                     | Desktop     | [196d56922a](https://linux-hardware.org/?probe=196d56922a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [373a11a297](https://linux-hardware.org/?probe=373a11a297) | Aug 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| Lenovo        | 32E4 SDK0J40697 WIN 3305... | Mini pc     | [3825d0ce9c](https://linux-hardware.org/?probe=3825d0ce9c) | Aug 29, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | Notebook    | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| ASRock        | B450M/ac R2.0               | Desktop     | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8517e82248](https://linux-hardware.org/?probe=8517e82248) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [676e223d96](https://linux-hardware.org/?probe=676e223d96) | Aug 25, 2022 |
| HP            | ProBook 4540s               | Notebook    | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | Notebook    | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [348dc86c64](https://linux-hardware.org/?probe=348dc86c64) | Aug 23, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [83e175bed9](https://linux-hardware.org/?probe=83e175bed9) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [10973eca34](https://linux-hardware.org/?probe=10973eca34) | Aug 22, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | Notebook    | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [bdc4179004](https://linux-hardware.org/?probe=bdc4179004) | Aug 21, 2022 |
| HP            | ProBook 6570b               | Notebook    | [eba0cd02ec](https://linux-hardware.org/?probe=eba0cd02ec) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| Dell          | G3 3779                     | Notebook    | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| MSI           | GF75 Thin 10SCXR            | Notebook    | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | Notebook    | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Samsung       | 950QDB                      | Convertible | [d4fc73ce00](https://linux-hardware.org/?probe=d4fc73ce00) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| ASUSTek       | Z10PC-D8 Series             | Desktop     | [1cb7c569c1](https://linux-hardware.org/?probe=1cb7c569c1) | Aug 17, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | Notebook    | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | Desktop     | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [96b090be6a](https://linux-hardware.org/?probe=96b090be6a) | Aug 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b490a791c0](https://linux-hardware.org/?probe=b490a791c0) | Aug 15, 2022 |
| Dell          | Precision 3571              | Notebook    | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | Desktop     | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [30820abfa2](https://linux-hardware.org/?probe=30820abfa2) | Aug 14, 2022 |
| ASUSTek       | NAGAMI                      | Desktop     | [c6c8918483](https://linux-hardware.org/?probe=c6c8918483) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | Desktop     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [18f3dd56e8](https://linux-hardware.org/?probe=18f3dd56e8) | Aug 11, 2022 |
| Panasonic     | CF-53JSWZGFF                | Notebook    | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| HP            | 8459                        | Desktop     | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Dell          | Latitude 5590               | Notebook    | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Timi          | TM1709                      | Notebook    | [26b592f734](https://linux-hardware.org/?probe=26b592f734) | Aug 11, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| Unknown       | Unknown                     | Other       | [23e67d3f72](https://linux-hardware.org/?probe=23e67d3f72) | Aug 10, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0acbdaf806](https://linux-hardware.org/?probe=0acbdaf806) | Aug 10, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | Notebook    | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5b7d298ca6](https://linux-hardware.org/?probe=5b7d298ca6) | Aug 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| HP            | 212A                        | Desktop     | [3b1662cede](https://linux-hardware.org/?probe=3b1662cede) | Aug 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [b2e805c687](https://linux-hardware.org/?probe=b2e805c687) | Aug 07, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23905636a4](https://linux-hardware.org/?probe=23905636a4) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9893d12c54](https://linux-hardware.org/?probe=9893d12c54) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| Dell          | Precision 7530              | Notebook    | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| VIT           | P2402                       | Notebook    | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [3a73f1ffdd](https://linux-hardware.org/?probe=3a73f1ffdd) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9814fa3bca](https://linux-hardware.org/?probe=9814fa3bca) | Aug 03, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| VIT           | P2402                       | Notebook    | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [83e4b444ae](https://linux-hardware.org/?probe=83e4b444ae) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [4e335cb7ce](https://linux-hardware.org/?probe=4e335cb7ce) | Aug 01, 2022 |
| Intel         | Unknown                     | Notebook    | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b99b5ef83f](https://linux-hardware.org/?probe=b99b5ef83f) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [3898ce2b5f](https://linux-hardware.org/?probe=3898ce2b5f) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [4ae44495ba](https://linux-hardware.org/?probe=4ae44495ba) | Jul 30, 2022 |
| Dell          | 0F8098                      | Desktop     | [4e6058685a](https://linux-hardware.org/?probe=4e6058685a) | Jul 30, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| HP            | 158A                        | Desktop     | [788844c3df](https://linux-hardware.org/?probe=788844c3df) | Jul 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [1b47c32e5d](https://linux-hardware.org/?probe=1b47c32e5d) | Jul 29, 2022 |
| HP            | 8754                        | Mini pc     | [1b0ae59d1f](https://linux-hardware.org/?probe=1b0ae59d1f) | Jul 28, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2d3706b78b](https://linux-hardware.org/?probe=2d3706b78b) | Jul 28, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| Dell          | Latitude 5590               | Notebook    | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [8b027b07d9](https://linux-hardware.org/?probe=8b027b07d9) | Jul 27, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [2b505d28f7](https://linux-hardware.org/?probe=2b505d28f7) | Jul 27, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [51bf4e60d3](https://linux-hardware.org/?probe=51bf4e60d3) | Jul 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| HP            | 86E9 A                      | Desktop     | [6634eaee32](https://linux-hardware.org/?probe=6634eaee32) | Jul 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [3e40b1abe6](https://linux-hardware.org/?probe=3e40b1abe6) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [158c8d142b](https://linux-hardware.org/?probe=158c8d142b) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [88530d3d60](https://linux-hardware.org/?probe=88530d3d60) | Jul 23, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [24bc799d14](https://linux-hardware.org/?probe=24bc799d14) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | Notebook    | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [379da1a196](https://linux-hardware.org/?probe=379da1a196) | Jul 21, 2022 |
| HP            | 8054                        | Desktop     | [466d7f5591](https://linux-hardware.org/?probe=466d7f5591) | Jul 21, 2022 |
| HP            | 18E9                        | Desktop     | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| Lenovo        | ThinkPad E570 20H5006TFR    | Notebook    | [1a1220dc79](https://linux-hardware.org/?probe=1a1220dc79) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [468283ab86](https://linux-hardware.org/?probe=468283ab86) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | Notebook    | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6670624ed](https://linux-hardware.org/?probe=f6670624ed) | Jul 16, 2022 |
| Standard      | Unknown                     | Notebook    | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | 1790                        | Desktop     | [ff91b0d921](https://linux-hardware.org/?probe=ff91b0d921) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [02a5205d57](https://linux-hardware.org/?probe=02a5205d57) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | Notebook    | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [3ea67a64cb](https://linux-hardware.org/?probe=3ea67a64cb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| ASRock        | J4105M                      | Desktop     | [509b122b9b](https://linux-hardware.org/?probe=509b122b9b) | Jul 12, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| Dell          | Latitude E5520              | Notebook    | [e04cdad7b7](https://linux-hardware.org/?probe=e04cdad7b7) | Jul 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0967e17760](https://linux-hardware.org/?probe=0967e17760) | Jul 11, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [392310b916](https://linux-hardware.org/?probe=392310b916) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | Notebook    | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| Lenovo        | IdeaPad Y430 2781           | Notebook    | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | Notebook    | [435e7998bd](https://linux-hardware.org/?probe=435e7998bd) | Jul 08, 2022 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| HP            | G42                         | Notebook    | [4a57fd54c6](https://linux-hardware.org/?probe=4a57fd54c6) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | Notebook    | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| HP            | 620                         | Notebook    | [cc970fdd77](https://linux-hardware.org/?probe=cc970fdd77) | Jul 02, 2022 |
| Lenovo        | ThinkPad T420 4180M8P       | Notebook    | [8a94c5bc15](https://linux-hardware.org/?probe=8a94c5bc15) | Jul 02, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HP            | 8459                        | Desktop     | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [91408af847](https://linux-hardware.org/?probe=91408af847) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | Desktop     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [32e2995911](https://linux-hardware.org/?probe=32e2995911) | Jun 30, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [530c44caa8](https://linux-hardware.org/?probe=530c44caa8) | Jun 30, 2022 |
| Jumper        | EZpad                       | Notebook    | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [faaa7b9c81](https://linux-hardware.org/?probe=faaa7b9c81) | Jun 29, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| Haier         | A1420EM                     | Notebook    | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [183f3e59fb](https://linux-hardware.org/?probe=183f3e59fb) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| Intel         | X99                         | Desktop     | [4322217bc5](https://linux-hardware.org/?probe=4322217bc5) | Jun 26, 2022 |
| HP            | 15                          | Notebook    | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Medion        | E3216 MD60900               | Convertible | [2890f2581b](https://linux-hardware.org/?probe=2890f2581b) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [554ba1726f](https://linux-hardware.org/?probe=554ba1726f) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3dffa312da](https://linux-hardware.org/?probe=3dffa312da) | Jun 24, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [10d0c2a6ea](https://linux-hardware.org/?probe=10d0c2a6ea) | Jun 24, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ece1eb60ef](https://linux-hardware.org/?probe=ece1eb60ef) | Jun 24, 2022 |
| Dell          | Latitude XT3                | Notebook    | [87377f03e2](https://linux-hardware.org/?probe=87377f03e2) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| ABIT          | IP35 Pro                    | Desktop     | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [ba64ef130a](https://linux-hardware.org/?probe=ba64ef130a) | Jun 23, 2022 |
| Clevo         | Modified by dsanke          | Notebook    | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2727a44bcd](https://linux-hardware.org/?probe=2727a44bcd) | Jun 22, 2022 |
| ASUSTek       | GR8                         | Notebook    | [90afe7bdd7](https://linux-hardware.org/?probe=90afe7bdd7) | Jun 20, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Medion        | AXIR                        | All in one  | [c3acbcaea0](https://linux-hardware.org/?probe=c3acbcaea0) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| Packard Be... | H17HV                       | Notebook    | [daa945363e](https://linux-hardware.org/?probe=daa945363e) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | Notebook    | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| HP            | 0A60h                       | Desktop     | [cb42238223](https://linux-hardware.org/?probe=cb42238223) | Jun 17, 2022 |
| ASRock        | B85M DASH/OL R2.0           | Desktop     | [c5763f8865](https://linux-hardware.org/?probe=c5763f8865) | Jun 17, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bf18000c3c](https://linux-hardware.org/?probe=bf18000c3c) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | Notebook    | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| ASUSTek       | X99-A/USB                   | Desktop     | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7adac78ac0](https://linux-hardware.org/?probe=7adac78ac0) | Jun 15, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [b4a87914f3](https://linux-hardware.org/?probe=b4a87914f3) | Jun 15, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [91316a0904](https://linux-hardware.org/?probe=91316a0904) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | Notebook    | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| HP            | 620                         | Notebook    | [fe1a420f17](https://linux-hardware.org/?probe=fe1a420f17) | Jun 13, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [8b6f8e8952](https://linux-hardware.org/?probe=8b6f8e8952) | Jun 13, 2022 |
| Jumper        | EZpad                       | Notebook    | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 1428               | Notebook    | [e47c98983f](https://linux-hardware.org/?probe=e47c98983f) | Jun 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [13a04a66d8](https://linux-hardware.org/?probe=13a04a66d8) | Jun 12, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7f7678265b](https://linux-hardware.org/?probe=7f7678265b) | Jun 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c8d1e1be32](https://linux-hardware.org/?probe=c8d1e1be32) | Jun 10, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | 0A98h                       | Desktop     | [d3c54ab2d6](https://linux-hardware.org/?probe=d3c54ab2d6) | Jun 10, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| HP            | Pavilion dv6                | Notebook    | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | Notebook    | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| AZW           | Gemini J45                  | Desktop     | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [54a2c4fa94](https://linux-hardware.org/?probe=54a2c4fa94) | Jun 08, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [82aa782cce](https://linux-hardware.org/?probe=82aa782cce) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3a58a9889b](https://linux-hardware.org/?probe=3a58a9889b) | Jun 08, 2022 |
| HP            | 620                         | Notebook    | [1adcb99573](https://linux-hardware.org/?probe=1adcb99573) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [42aaad44bc](https://linux-hardware.org/?probe=42aaad44bc) | Jun 06, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [acf0372bdc](https://linux-hardware.org/?probe=acf0372bdc) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| ASUSTek       | WS X299 PRO                 | Desktop     | [219d19f97e](https://linux-hardware.org/?probe=219d19f97e) | Jun 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Toshiba       | Satellite C75D-A            | Notebook    | [a5aee20b56](https://linux-hardware.org/?probe=a5aee20b56) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| Positivo      | Q464C                       | Notebook    | [e00b91e529](https://linux-hardware.org/?probe=e00b91e529) | Jun 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [eb62d09265](https://linux-hardware.org/?probe=eb62d09265) | Jun 05, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1380      | 41.89%  |
| Kubuntu 22.04   | 543       | 16.48%  |
| Kubuntu 20.10   | 256       | 7.77%   |
| Kubuntu 21.10   | 242       | 7.35%   |
| Kubuntu 21.04   | 214       | 6.5%    |
| Kubuntu 18.04   | 198       | 6.01%   |
| Kubuntu 19.10   | 178       | 5.4%    |
| Kubuntu 22.10   | 111       | 3.37%   |
| Kubuntu 11      | 81        | 2.46%   |
| Kubuntu 11.1    | 26        | 0.79%   |
| Kubuntu 19.04   | 22        | 0.67%   |
| Kubuntu 16.04   | 13        | 0.39%   |
| Kubuntu         | 8         | 0.24%   |
| Kubuntu 18.10   | 7         | 0.21%   |
| Kubuntu 2.0     | 6         | 0.18%   |
| Kubuntu 17.10   | 3         | 0.09%   |
| Kubuntu 17.04   | 2         | 0.06%   |
| Kubuntu 14.04   | 2         | 0.06%   |
| Kubuntu 20.08.3 | 1         | 0.03%   |
| Kubuntu 12.04   | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 3153      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 2.86%   |
| 5.15.0-52-generic | 84        | 2.33%   |
| 5.4.0-52-generic  | 68        | 1.89%   |
| 5.4.0-58-generic  | 59        | 1.64%   |
| 5.4.0-48-generic  | 59        | 1.64%   |
| 5.15.0-48-generic | 58        | 1.61%   |
| 5.15.0-56-generic | 54        | 1.5%    |
| 5.19.0-23-generic | 52        | 1.44%   |
| 5.15.0-46-generic | 52        | 1.44%   |
| 5.13.0-39-generic | 52        | 1.44%   |
| 5.4.0-40-generic  | 47        | 1.3%    |
| 5.13.0-28-generic | 44        | 1.22%   |
| 5.15.0-43-generic | 39        | 1.08%   |
| 5.15.0-41-generic | 39        | 1.08%   |
| 5.15.0-47-generic | 38        | 1.05%   |
| 5.11.0-37-generic | 38        | 1.05%   |
| 5.11.0-25-generic | 38        | 1.05%   |
| 5.13.0-30-generic | 37        | 1.03%   |
| 5.4.0-47-generic  | 36        | 1%      |
| 5.15.0-53-generic | 36        | 1%      |
| 5.4.0-65-generic  | 35        | 0.97%   |
| 5.8.0-48-generic  | 34        | 0.94%   |
| 5.3.0-40-generic  | 34        | 0.94%   |
| 5.4.0-37-generic  | 33        | 0.92%   |
| 5.4.0-29-generic  | 33        | 0.92%   |
| 5.13.0-22-generic | 31        | 0.86%   |
| 5.4.0-45-generic  | 30        | 0.83%   |
| 5.8.0-50-generic  | 29        | 0.8%    |
| 5.19.0-26-generic | 29        | 0.8%    |
| 5.13.0-35-generic | 29        | 0.8%    |
| 5.8.0-63-generic  | 28        | 0.78%   |
| 5.4.0-54-generic  | 28        | 0.78%   |
| 5.3.0-26-generic  | 28        | 0.78%   |
| 5.13.0-40-generic | 28        | 0.78%   |
| 5.8.0-44-generic  | 27        | 0.75%   |
| 5.8.0-43-generic  | 27        | 0.75%   |
| 5.15.0-50-generic | 26        | 0.72%   |
| 5.15.0-40-generic | 26        | 0.72%   |
| 5.11.0-22-generic | 26        | 0.72%   |
| 5.4.0-26-generic  | 25        | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 930       | 27.79%  |
| 5.15.0  | 586       | 17.51%  |
| 5.13.0  | 407       | 12.16%  |
| 5.8.0   | 406       | 12.13%  |
| 5.11.0  | 326       | 9.74%   |
| 5.3.0   | 224       | 6.69%   |
| 5.19.0  | 96        | 2.87%   |
| 4.15.0  | 69        | 2.06%   |
| 5.0.0   | 36        | 1.08%   |
| 5.10.0  | 17        | 0.51%   |
| 5.17.0  | 16        | 0.48%   |
| 5.6.0   | 15        | 0.45%   |
| 4.4.0   | 10        | 0.3%    |
| 4.18.0  | 8         | 0.24%   |
| 5.14.0  | 7         | 0.21%   |
| 6.0.0   | 6         | 0.18%   |
| 5.9.0   | 5         | 0.15%   |
| 5.7.0   | 4         | 0.12%   |
| 6.0.9   | 3         | 0.09%   |
| 5.8.18  | 3         | 0.09%   |
| 5.18.4  | 3         | 0.09%   |
| 5.16.0  | 3         | 0.09%   |
| 5.12.8  | 3         | 0.09%   |
| 5.12.0  | 3         | 0.09%   |
| 4.13.0  | 3         | 0.09%   |
| 4.10.0  | 3         | 0.09%   |
| 6.0.7   | 2         | 0.06%   |
| 6.0.6   | 2         | 0.06%   |
| 6.0.1   | 2         | 0.06%   |
| 5.9.16  | 2         | 0.06%   |
| 5.9.10  | 2         | 0.06%   |
| 5.8.5   | 2         | 0.06%   |
| 5.8.2   | 2         | 0.06%   |
| 5.8.12  | 2         | 0.06%   |
| 5.8.1   | 2         | 0.06%   |
| 5.7.10  | 2         | 0.06%   |
| 5.7.1   | 2         | 0.06%   |
| 5.5.13  | 2         | 0.06%   |
| 5.19.5  | 2         | 0.06%   |
| 5.18.10 | 2         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 937       | 28.03%  |
| 5.15    | 600       | 17.95%  |
| 5.8     | 422       | 12.62%  |
| 5.13    | 417       | 12.47%  |
| 5.11    | 332       | 9.93%   |
| 5.3     | 227       | 6.79%   |
| 5.19    | 102       | 3.05%   |
| 4.15    | 70        | 2.09%   |
| 5.0     | 37        | 1.11%   |
| 5.10    | 29        | 0.87%   |
| 5.17    | 23        | 0.69%   |
| 5.6     | 20        | 0.6%    |
| 6.0     | 17        | 0.51%   |
| 5.14    | 16        | 0.48%   |
| 5.9     | 13        | 0.39%   |
| 5.12    | 13        | 0.39%   |
| 5.7     | 11        | 0.33%   |
| 5.18    | 10        | 0.3%    |
| 5.16    | 10        | 0.3%    |
| 4.4     | 10        | 0.3%    |
| 4.18    | 10        | 0.3%    |
| 5.5     | 5         | 0.15%   |
| 4.13    | 3         | 0.09%   |
| 4.10    | 3         | 0.09%   |
| 5.1     | 2         | 0.06%   |
| 6.1     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3135      | 99.43%  |
| i686    | 12        | 0.38%   |
| aarch64 | 5         | 0.16%   |
| riscv64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 2267      | 70.6%   |
| KDE        | 896       | 27.9%   |
| GNOME      | 14        | 0.44%   |
| Cinnamon   | 9         | 0.28%   |
| Budgie     | 7         | 0.22%   |
| MATE       | 6         | 0.19%   |
| KDE4       | 3         | 0.09%   |
| XFCE       | 2         | 0.06%   |
| LXQt       | 2         | 0.06%   |
| X-Cinnamon | 1         | 0.03%   |
| Unity      | 1         | 0.03%   |
| i3         | 1         | 0.03%   |
| GNUstep    | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3045      | 95.97%  |
| Wayland | 94        | 2.96%   |
| Tty     | 33        | 1.04%   |
| Web     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1820      | 56.61%  |
| Unknown | 1169      | 36.36%  |
| GDM     | 107       | 3.33%   |
| LightDM | 48        | 1.49%   |
| GDM3    | 47        | 1.46%   |
| TDM     | 21        | 0.65%   |
| SLiM    | 2         | 0.06%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1317      | 41.35%  |
| de_DE   | 254       | 7.97%   |
| ru_RU   | 166       | 5.21%   |
| pt_BR   | 149       | 4.68%   |
| fr_FR   | 148       | 4.65%   |
| en_GB   | 147       | 4.62%   |
| it_IT   | 137       | 4.3%    |
| Unknown | 77        | 2.42%   |
| en_CA   | 66        | 2.07%   |
| es_ES   | 64        | 2.01%   |
| en_AU   | 64        | 2.01%   |
| pl_PL   | 60        | 1.88%   |
| en_IN   | 55        | 1.73%   |
| C       | 33        | 1.04%   |
| hu_HU   | 27        | 0.85%   |
| ru_UA   | 23        | 0.72%   |
| es_MX   | 23        | 0.72%   |
| es_AR   | 21        | 0.66%   |
| en_ZA   | 20        | 0.63%   |
| cs_CZ   | 19        | 0.6%    |
| nl_NL   | 17        | 0.53%   |
| de_AT   | 17        | 0.53%   |
| en_NZ   | 16        | 0.5%    |
| de_CH   | 12        | 0.38%   |
| tr_TR   | 10        | 0.31%   |
| pt_PT   | 10        | 0.31%   |
| sv_SE   | 9         | 0.28%   |
| es_CO   | 9         | 0.28%   |
| en_PH   | 9         | 0.28%   |
| en_IL   | 9         | 0.28%   |
| el_GR   | 9         | 0.28%   |
| uk_UA   | 8         | 0.25%   |
| es_CL   | 8         | 0.25%   |
| en_IE   | 8         | 0.25%   |
| sl_SI   | 7         | 0.22%   |
| nl_BE   | 7         | 0.22%   |
| fi_FI   | 7         | 0.22%   |
| es_VE   | 7         | 0.22%   |
| zh_CN   | 6         | 0.19%   |
| sk_SK   | 6         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1772      | 55.32%  |
| BIOS | 1431      | 44.68%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2895      | 91.21%  |
| Btrfs    | 123       | 3.88%   |
| Overlay  | 80        | 2.52%   |
| Xfs      | 34        | 1.07%   |
| Zfs      | 18        | 0.57%   |
| Unknown  | 12        | 0.38%   |
| Ext3     | 4         | 0.13%   |
| Ext2     | 4         | 0.13%   |
| XXXX     | 1         | 0.03%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| ExX4     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1485      | 46.33%  |
| Unknown | 1410      | 43.99%  |
| MBR     | 310       | 9.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2757      | 86.45%  |
| Yes       | 432       | 13.55%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1940      | 60.8%   |
| Yes       | 1251      | 39.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 506       | 16.05%  |
| Lenovo              | 474       | 15.03%  |
| Dell                | 445       | 14.11%  |
| Hewlett-Packard     | 431       | 13.67%  |
| Gigabyte Technology | 257       | 8.15%   |
| MSI                 | 211       | 6.69%   |
| Acer                | 145       | 4.6%    |
| ASRock              | 120       | 3.81%   |
| Apple               | 41        | 1.3%    |
| Samsung Electronics | 40        | 1.27%   |
| Intel               | 34        | 1.08%   |
| HUAWEI              | 30        | 0.95%   |
| Unknown             | 26        | 0.82%   |
| Toshiba             | 24        | 0.76%   |
| Notebook            | 20        | 0.63%   |
| TUXEDO              | 19        | 0.6%    |
| Sony                | 19        | 0.6%    |
| Google              | 17        | 0.54%   |
| Fujitsu             | 17        | 0.54%   |
| Timi                | 13        | 0.41%   |
| Pegatron            | 13        | 0.41%   |
| Positivo            | 12        | 0.38%   |
| Medion              | 11        | 0.35%   |
| Biostar             | 10        | 0.32%   |
| Foxconn             | 9         | 0.29%   |
| Alienware           | 9         | 0.29%   |
| ZOTAC               | 8         | 0.25%   |
| Packard Bell        | 8         | 0.25%   |
| Microsoft           | 8         | 0.25%   |
| Supermicro          | 7         | 0.22%   |
| ECS                 | 7         | 0.22%   |
| System76            | 6         | 0.19%   |
| PC Specialist       | 6         | 0.19%   |
| LG Electronics      | 6         | 0.19%   |
| Chuwi               | 6         | 0.19%   |
| AZW                 | 6         | 0.19%   |
| Shuttle             | 5         | 0.16%   |
| Razer               | 5         | 0.16%   |
| Panasonic           | 5         | 0.16%   |
| Huanan              | 5         | 0.16%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| ASUS All Series               | 39        | 1.24%   |
| Unknown                       | 39        | 1.24%   |
| Gigabyte B450M DS3H           | 11        | 0.35%   |
| ASUS ROG STRIX B550-F GAMING  | 10        | 0.32%   |
| MSI MS-7C37                   | 9         | 0.29%   |
| MSI MS-7B79                   | 9         | 0.29%   |
| HP Pavilion g6                | 9         | 0.29%   |
| HP Pavilion dv6               | 9         | 0.29%   |
| HP Notebook                   | 9         | 0.29%   |
| HUAWEI NBLK-WAX9X             | 8         | 0.25%   |
| Dell XPS 15 9560              | 8         | 0.25%   |
| Dell OptiPlex 9020            | 8         | 0.25%   |
| ASUS ROG STRIX X570-E GAMING  | 8         | 0.25%   |
| ASUS PRIME B350-PLUS          | 8         | 0.25%   |
| HP Pavilion dv7               | 7         | 0.22%   |
| Gigabyte X570 AORUS MASTER    | 7         | 0.22%   |
| Gigabyte 970A-DS3P            | 7         | 0.22%   |
| Dell OptiPlex 7010            | 7         | 0.22%   |
| ASUS PRIME B450M-A            | 7         | 0.22%   |
| MSI MS-7A34                   | 6         | 0.19%   |
| MSI MS-7817                   | 6         | 0.19%   |
| HP Pavilion 15                | 6         | 0.19%   |
| HP EliteBook 840 G5           | 6         | 0.19%   |
| HP EliteBook 840 G3           | 6         | 0.19%   |
| Gigabyte A320M-S2H            | 6         | 0.19%   |
| Dell XPS 15 9570              | 6         | 0.19%   |
| MSI MS-7C02                   | 5         | 0.16%   |
| HP EliteBook 840 G6           | 5         | 0.16%   |
| Dell XPS 8700                 | 5         | 0.16%   |
| Dell XPS 15 7590              | 5         | 0.16%   |
| Dell XPS 13 9310              | 5         | 0.16%   |
| Dell Latitude E6540           | 5         | 0.16%   |
| Dell Latitude 5480            | 5         | 0.16%   |
| ASUS PRIME X570-P             | 5         | 0.16%   |
| ASRock AB350 Pro4             | 5         | 0.16%   |
| MSI MS-7996                   | 4         | 0.13%   |
| MSI MS-7693                   | 4         | 0.13%   |
| Lenovo Legion Y530-15ICH 81FV | 4         | 0.13%   |
| Lenovo IdeaPad 330-15IKB 81DE | 4         | 0.13%   |
| Lenovo G50-70 20351           | 4         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 217       | 6.88%   |
| Dell Latitude      | 118       | 3.74%   |
| Dell Inspiron      | 112       | 3.55%   |
| Acer Aspire        | 94        | 2.98%   |
| HP Pavilion        | 91        | 2.89%   |
| Lenovo IdeaPad     | 84        | 2.66%   |
| ASUS ROG           | 69        | 2.19%   |
| Dell XPS           | 65        | 2.06%   |
| ASUS PRIME         | 65        | 2.06%   |
| HP ProBook         | 55        | 1.74%   |
| HP EliteBook       | 53        | 1.68%   |
| HP Laptop          | 46        | 1.46%   |
| Dell Precision     | 45        | 1.43%   |
| Dell OptiPlex      | 44        | 1.4%    |
| ASUS All           | 39        | 1.24%   |
| Unknown            | 39        | 1.24%   |
| ASUS VivoBook      | 37        | 1.17%   |
| ASUS TUF           | 34        | 1.08%   |
| Lenovo ThinkCentre | 28        | 0.89%   |
| Dell Vostro        | 27        | 0.86%   |
| HP Compaq          | 26        | 0.82%   |
| Lenovo Yoga        | 24        | 0.76%   |
| HP ENVY            | 24        | 0.76%   |
| Toshiba Satellite  | 20        | 0.63%   |
| Lenovo ThinkBook   | 19        | 0.6%    |
| Lenovo Legion      | 19        | 0.6%    |
| Acer Nitro         | 19        | 0.6%    |
| Gigabyte B450M     | 18        | 0.57%   |
| Gigabyte X570      | 17        | 0.54%   |
| ASUS ZenBook       | 16        | 0.51%   |
| ASUS ASUS          | 14        | 0.44%   |
| Acer Swift         | 12        | 0.38%   |
| HP Spectre         | 11        | 0.35%   |
| Gigabyte A320M-S2H | 10        | 0.32%   |
| MSI MS-7C37        | 9         | 0.29%   |
| MSI MS-7B79        | 9         | 0.29%   |
| HP ZBook           | 9         | 0.29%   |
| HP Notebook        | 9         | 0.29%   |
| HP EliteDesk       | 9         | 0.29%   |
| Gigabyte B550      | 9         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 398       | 12.62%  |
| 2020    | 384       | 12.18%  |
| 2018    | 368       | 11.67%  |
| 2017    | 239       | 7.58%   |
| 2021    | 233       | 7.39%   |
| 2013    | 225       | 7.14%   |
| 2012    | 224       | 7.1%    |
| 2014    | 196       | 6.22%   |
| 2011    | 195       | 6.18%   |
| 2016    | 157       | 4.98%   |
| 2015    | 147       | 4.66%   |
| 2010    | 110       | 3.49%   |
| 2008    | 88        | 2.79%   |
| 2009    | 78        | 2.47%   |
| 2022    | 57        | 1.81%   |
| 2007    | 34        | 1.08%   |
| 2006    | 9         | 0.29%   |
| Unknown | 7         | 0.22%   |
| 2005    | 3         | 0.1%    |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1745      | 55.34%  |
| Desktop        | 1192      | 37.81%  |
| Convertible    | 106       | 3.36%   |
| Mini pc        | 43        | 1.36%   |
| All in one     | 28        | 0.89%   |
| Tablet         | 21        | 0.67%   |
| Server         | 13        | 0.41%   |
| System on chip | 4         | 0.13%   |
| Other          | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2906      | 91.61%  |
| Enabled  | 266       | 8.39%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3130      | 99.27%  |
| Yes  | 23        | 0.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 824       | 25.92%  |
| 4.01-8.0    | 704       | 22.15%  |
| 8.01-16.0   | 593       | 18.65%  |
| 32.01-64.0  | 423       | 13.31%  |
| 3.01-4.0    | 394       | 12.39%  |
| 64.01-256.0 | 95        | 2.99%   |
| 24.01-32.0  | 77        | 2.42%   |
| 1.01-2.0    | 48        | 1.51%   |
| 2.01-3.0    | 21        | 0.66%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 885       | 25.98%  |
| 1.01-2.0    | 802       | 23.54%  |
| 4.01-8.0    | 765       | 22.45%  |
| 3.01-4.0    | 559       | 16.41%  |
| 8.01-16.0   | 253       | 7.43%   |
| 0.51-1.0    | 83        | 2.44%   |
| 16.01-24.0  | 36        | 1.06%   |
| 24.01-32.0  | 11        | 0.32%   |
| 32.01-64.0  | 6         | 0.18%   |
| 0.01-0.5    | 5         | 0.15%   |
| 64.01-256.0 | 1         | 0.03%   |
| Unknown     | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1724      | 53.26%  |
| 2      | 878       | 27.12%  |
| 3      | 296       | 9.14%   |
| 4      | 166       | 5.13%   |
| 5      | 85        | 2.63%   |
| 6      | 40        | 1.24%   |
| 7      | 19        | 0.59%   |
| 0      | 11        | 0.34%   |
| 8      | 6         | 0.19%   |
| 9      | 4         | 0.12%   |
| 10     | 3         | 0.09%   |
| 12     | 2         | 0.06%   |
| 11     | 2         | 0.06%   |
| 13     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2115      | 66.53%  |
| Yes       | 1064      | 33.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2686      | 85.08%  |
| No        | 471       | 14.92%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2441      | 77.1%   |
| No        | 725       | 22.9%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2079      | 65.36%  |
| No        | 1102      | 34.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 583       | 18.45%  |
| Germany      | 341       | 10.79%  |
| Russia       | 231       | 7.31%   |
| Brazil       | 195       | 6.17%   |
| France       | 186       | 5.89%   |
| Italy        | 178       | 5.63%   |
| UK           | 135       | 4.27%   |
| Spain        | 94        | 2.97%   |
| Poland       | 82        | 2.59%   |
| Canada       | 75        | 2.37%   |
| Netherlands  | 74        | 2.34%   |
| Ukraine      | 63        | 1.99%   |
| Australia    | 62        | 1.96%   |
| India        | 57        | 1.8%    |
| Hungary      | 43        | 1.36%   |
| Switzerland  | 42        | 1.33%   |
| Mexico       | 42        | 1.33%   |
| Czechia      | 34        | 1.08%   |
| Argentina    | 32        | 1.01%   |
| Belgium      | 28        | 0.89%   |
| Austria      | 28        | 0.89%   |
| Indonesia    | 23        | 0.73%   |
| Greece       | 23        | 0.73%   |
| South Africa | 22        | 0.7%    |
| Turkey       | 20        | 0.63%   |
| Bulgaria     | 20        | 0.63%   |
| Sweden       | 19        | 0.6%    |
| Romania      | 19        | 0.6%    |
| Slovenia     | 17        | 0.54%   |
| Finland      | 17        | 0.54%   |
| Denmark      | 17        | 0.54%   |
| New Zealand  | 16        | 0.51%   |
| Portugal     | 15        | 0.47%   |
| Belarus      | 15        | 0.47%   |
| Serbia       | 14        | 0.44%   |
| Colombia     | 14        | 0.44%   |
| Israel       | 13        | 0.41%   |
| China        | 13        | 0.41%   |
| Slovakia     | 12        | 0.38%   |
| Ireland      | 12        | 0.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 63        | 1.92%   |
| Berlin            | 36        | 1.09%   |
| St Petersburg     | 28        | 0.85%   |
| Paris             | 28        | 0.85%   |
| Milan             | 28        | 0.85%   |
| Warsaw            | 24        | 0.73%   |
| Rome              | 24        | 0.73%   |
| Hamburg           | 22        | 0.67%   |
| Sao Paulo         | 21        | 0.64%   |
| Budapest          | 21        | 0.64%   |
| Sydney            | 18        | 0.55%   |
| Rio de Janeiro    | 18        | 0.55%   |
| Kyiv              | 18        | 0.55%   |
| Amsterdam         | 18        | 0.55%   |
| Zurich            | 17        | 0.52%   |
| Madrid            | 16        | 0.49%   |
| Cologne           | 16        | 0.49%   |
| Munich            | 15        | 0.46%   |
| Vienna            | 14        | 0.43%   |
| Melbourne         | 14        | 0.43%   |
| Sofia             | 13        | 0.4%    |
| Frankfurt am Main | 13        | 0.4%    |
| Prague            | 12        | 0.36%   |
| Novosibirsk       | 12        | 0.36%   |
| Minsk             | 12        | 0.36%   |
| London            | 11        | 0.33%   |
| Dallas            | 11        | 0.33%   |
| Belgrade          | 11        | 0.33%   |
| Athens            | 11        | 0.33%   |
| Seattle           | 10        | 0.3%    |
| Jakarta           | 10        | 0.3%    |
| Auckland          | 10        | 0.3%    |
| Wroclaw           | 9         | 0.27%   |
| Los Angeles       | 9         | 0.27%   |
| Phoenix           | 8         | 0.24%   |
| Miami             | 8         | 0.24%   |
| Marseille         | 8         | 0.24%   |
| Krakow            | 8         | 0.24%   |
| Jacksonville      | 8         | 0.24%   |
| Dublin            | 8         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 899       | 1349   | 18.03%  |
| WDC                       | 746       | 1203   | 14.96%  |
| Seagate                   | 665       | 989    | 13.34%  |
| Toshiba                   | 307       | 404    | 6.16%   |
| Kingston                  | 298       | 355    | 5.98%   |
| SanDisk                   | 261       | 307    | 5.23%   |
| Crucial                   | 201       | 249    | 4.03%   |
| Unknown                   | 168       | 210    | 3.37%   |
| Intel                     | 148       | 197    | 2.97%   |
| Hitachi                   | 133       | 159    | 2.67%   |
| SK hynix                  | 128       | 151    | 2.57%   |
| HGST                      | 96        | 124    | 1.93%   |
| Micron Technology         | 78        | 86     | 1.56%   |
| A-DATA Technology         | 70        | 76     | 1.4%    |
| Phison                    | 44        | 58     | 0.88%   |
| KIOXIA                    | 40        | 44     | 0.8%    |
| China                     | 33        | 43     | 0.66%   |
| Silicon Motion            | 32        | 36     | 0.64%   |
| Apple                     | 29        | 33     | 0.58%   |
| Transcend                 | 28        | 30     | 0.56%   |
| PNY                       | 27        | 31     | 0.54%   |
| Intenso                   | 27        | 31     | 0.54%   |
| Patriot                   | 24        | 32     | 0.48%   |
| SPCC                      | 23        | 28     | 0.46%   |
| LITEON                    | 23        | 25     | 0.46%   |
| OCZ                       | 22        | 29     | 0.44%   |
| Corsair                   | 20        | 32     | 0.4%    |
| Maxtor                    | 18        | 19     | 0.36%   |
| GOODRAM                   | 17        | 32     | 0.34%   |
| JMicron Technology        | 16        | 18     | 0.32%   |
| XPG                       | 14        | 15     | 0.28%   |
| Unknown                   | 14        | 14     | 0.28%   |
| KingSpec                  | 13        | 15     | 0.26%   |
| SABRENT                   | 12        | 15     | 0.24%   |
| Micron/Crucial Technology | 12        | 15     | 0.24%   |
| Team                      | 11        | 12     | 0.22%   |
| LITEONIT                  | 11        | 13     | 0.22%   |
| Fujitsu                   | 11        | 14     | 0.22%   |
| Gigabyte Technology       | 10        | 11     | 0.2%    |
| Mushkin                   | 9         | 10     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 54        | 0.96%   |
| Kingston SA400S37240G 240GB SSD    | 51        | 0.91%   |
| Samsung SSD 850 EVO 500GB          | 47        | 0.84%   |
| Samsung SSD 850 EVO 250GB          | 44        | 0.79%   |
| Samsung SSD 860 EVO 1TB            | 37        | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB     | 36        | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 34        | 0.61%   |
| Kingston SA400S37480G 480GB SSD    | 34        | 0.61%   |
| Samsung NVMe SSD Drive 500GB       | 33        | 0.59%   |
| Toshiba MQ01ABD100 1TB             | 31        | 0.55%   |
| Samsung NVMe SSD Drive 1TB         | 30        | 0.54%   |
| Samsung NVMe SSD Drive 512GB       | 28        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB        | 28        | 0.5%    |
| Unknown MMC Card  32GB             | 27        | 0.48%   |
| Toshiba MQ04ABF100 1TB             | 27        | 0.48%   |
| HGST HTS721010A9E630 1TB           | 27        | 0.48%   |
| Unknown MMC Card  64GB             | 24        | 0.43%   |
| Seagate ST1000DM010-2EP102 1TB     | 23        | 0.41%   |
| Samsung SSD 970 EVO Plus 500GB     | 23        | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB       | 23        | 0.41%   |
| WDC WD10EZEX-08WN4A0 1TB           | 22        | 0.39%   |
| Crucial CT500MX500SSD1 500GB       | 21        | 0.38%   |
| Seagate ST4000DM004-2CV104 4TB     | 20        | 0.36%   |
| Toshiba HDWD110 1TB                | 19        | 0.34%   |
| Toshiba DT01ACA100 1TB             | 19        | 0.34%   |
| Seagate ST500DM002-1BD142 500GB    | 19        | 0.34%   |
| Seagate ST1000DM003-1ER162 1TB     | 19        | 0.34%   |
| Seagate ST500LT012-1DG142 500GB    | 18        | 0.32%   |
| Seagate ST2000DM001-1ER164 2TB     | 18        | 0.32%   |
| Seagate ST1000DM003-1CH162 1TB     | 18        | 0.32%   |
| SanDisk SSD PLUS 240GB             | 18        | 0.32%   |
| Samsung SSD 860 EVO 250GB          | 18        | 0.32%   |
| Kingston SA400S37120G 120GB SSD    | 18        | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 17        | 0.3%    |
| Seagate ST2000DM008-2FR102 2TB     | 17        | 0.3%    |
| Seagate Expansion 4TB              | 17        | 0.3%    |
| SanDisk NVMe SSD Drive 512GB       | 17        | 0.3%    |
| Kingston SV300S37A120G 120GB SSD   | 17        | 0.3%    |
| Kingston SA2000M81000G 1TB         | 17        | 0.3%    |
| Samsung SSD 860 QVO 1TB            | 16        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 648       | 957    | 35.16%  |
| WDC                 | 571       | 952    | 30.98%  |
| Toshiba             | 215       | 284    | 11.67%  |
| Hitachi             | 133       | 159    | 7.22%   |
| Samsung Electronics | 98        | 147    | 5.32%   |
| HGST                | 95        | 123    | 5.15%   |
| Unknown             | 20        | 23     | 1.09%   |
| Maxtor              | 17        | 18     | 0.92%   |
| Fujitsu             | 10        | 13     | 0.54%   |
| Apple               | 10        | 10     | 0.54%   |
| ASMT                | 6         | 7      | 0.33%   |
| Hewlett-Packard     | 3         | 5      | 0.16%   |
| USB3.0              | 2         | 2      | 0.11%   |
| SAGE                | 2         | 2      | 0.11%   |
| JMicron Technology  | 2         | 2      | 0.11%   |
| WD MediaMax         | 1         | 1      | 0.05%   |
| USB                 | 1         | 1      | 0.05%   |
| Magnetic Data       | 1         | 2      | 0.05%   |
| LIO-ORG             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| ipTIME              | 1         | 1      | 0.05%   |
| IET                 | 1         | 1      | 0.05%   |
| HPE                 | 1         | 6      | 0.05%   |
| HGST HTS            | 1         | 1      | 0.05%   |
| ASMedia             | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 472       | 651    | 27.33%  |
| Kingston            | 225       | 267    | 13.03%  |
| SanDisk             | 173       | 203    | 10.02%  |
| Crucial             | 171       | 216    | 9.9%    |
| WDC                 | 88        | 112    | 5.1%    |
| Intel               | 50        | 59     | 2.9%    |
| A-DATA Technology   | 48        | 53     | 2.78%   |
| China               | 32        | 42     | 1.85%   |
| Toshiba             | 31        | 45     | 1.8%    |
| Micron Technology   | 31        | 34     | 1.8%    |
| Patriot             | 24        | 32     | 1.39%   |
| SK hynix            | 23        | 25     | 1.33%   |
| PNY                 | 23        | 27     | 1.33%   |
| Intenso             | 23        | 26     | 1.33%   |
| Transcend           | 22        | 22     | 1.27%   |
| OCZ                 | 22        | 29     | 1.27%   |
| SPCC                | 20        | 24     | 1.16%   |
| LITEON              | 18        | 19     | 1.04%   |
| GOODRAM             | 17        | 32     | 0.98%   |
| KingSpec            | 13        | 15     | 0.75%   |
| LITEONIT            | 11        | 13     | 0.64%   |
| Corsair             | 11        | 21     | 0.64%   |
| Apple               | 11        | 11     | 0.64%   |
| Team                | 10        | 10     | 0.58%   |
| Apacer              | 9         | 14     | 0.52%   |
| Mushkin             | 8         | 9      | 0.46%   |
| JMicron Technology  | 7         | 8      | 0.41%   |
| Verbatim            | 6         | 7      | 0.35%   |
| Plextor             | 6         | 7      | 0.35%   |
| Emtec               | 6         | 6      | 0.35%   |
| Lexar               | 5         | 6      | 0.29%   |
| Dogfish             | 5         | 5      | 0.29%   |
| Unknown             | 5         | 5      | 0.29%   |
| Unknown             | 4         | 4      | 0.23%   |
| Seagate             | 4         | 9      | 0.23%   |
| Netac               | 4         | 5      | 0.23%   |
| KingDian            | 4         | 5      | 0.23%   |
| Gigabyte Technology | 4         | 4      | 0.23%   |
| Drevo               | 4         | 5      | 0.23%   |
| Zheino              | 3         | 5      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1482      | 2182   | 33.7%   |
| HDD     | 1479      | 2721   | 33.63%  |
| NVMe    | 1220      | 1639   | 27.74%  |
| MMC     | 147       | 183    | 3.34%   |
| Unknown | 70        | 95     | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2290      | 4741   | 59.65%  |
| NVMe | 1210      | 1616   | 31.52%  |
| SAS  | 192       | 280    | 5%      |
| MMC  | 147       | 183    | 3.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1621      | 2513   | 50.91%  |
| 0.51-1.0   | 986       | 1464   | 30.97%  |
| 1.01-2.0   | 309       | 477    | 9.7%    |
| 3.01-4.0   | 126       | 222    | 3.96%   |
| 2.01-3.0   | 76        | 108    | 2.39%   |
| 4.01-10.0  | 58        | 105    | 1.82%   |
| 10.01-20.0 | 8         | 14     | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 812       | 24.89%  |
| 251-500        | 786       | 24.09%  |
| 501-1000       | 597       | 18.3%   |
| 1001-2000      | 329       | 10.08%  |
| More than 3000 | 240       | 7.36%   |
| 51-100         | 174       | 5.33%   |
| 2001-3000      | 142       | 4.35%   |
| 1-20           | 89        | 2.73%   |
| 21-50          | 80        | 2.45%   |
| Unknown        | 14        | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 786       | 23.41%  |
| 101-250        | 564       | 16.8%   |
| 21-50          | 532       | 15.84%  |
| 51-100         | 440       | 13.1%   |
| 251-500        | 393       | 11.7%   |
| 501-1000       | 294       | 8.76%   |
| 1001-2000      | 164       | 4.88%   |
| More than 3000 | 115       | 3.42%   |
| 2001-3000      | 56        | 1.67%   |
| Unknown        | 14        | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB             | 6         | 7      | 1.66%   |
| Seagate ST31000524AS 1TB             | 5         | 6      | 1.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 11     | 1.38%   |
| Seagate ST500LT012-9WS142 500GB      | 4         | 4      | 1.1%    |
| Seagate ST500DM002-1BD142 500GB      | 4         | 4      | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 4      | 1.1%    |
| Seagate ST1000DM003-1CH162 1TB       | 4         | 9      | 1.1%    |
| Toshiba MQ04ABF100 1TB               | 3         | 3      | 0.83%   |
| Toshiba MQ01ABD100 1TB               | 3         | 5      | 0.83%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 3      | 0.83%   |
| Seagate ST31000528AS 1TB             | 3         | 3      | 0.83%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.83%   |
| Kingston SV300S37A120G 120GB SSD     | 3         | 3      | 0.83%   |
| Hitachi HTS547564A9E384 640GB        | 3         | 3      | 0.83%   |
| HGST HTS545050A7E680 500GB           | 3         | 3      | 0.83%   |
| Crucial CT525MX300SSD1 528GB         | 3         | 3      | 0.83%   |
| Crucial CT1050MX300SSD1 1TB          | 3         | 3      | 0.83%   |
| WDC WD5000AAKS-00V1A0 500GB          | 2         | 3      | 0.55%   |
| WDC WD5000AAKS-00A7B0 500GB          | 2         | 2      | 0.55%   |
| WDC WD3200JD-22KLB0 320GB            | 2         | 2      | 0.55%   |
| WDC WD30EZRX-00MMMB0 3TB             | 2         | 2      | 0.55%   |
| WDC WD20EFRX-68EUZN0 2TB             | 2         | 4      | 0.55%   |
| WDC WD20EARX-00PASB0 2TB             | 2         | 2      | 0.55%   |
| WDC WD15EARS-00Z5B1 1TB              | 2         | 2      | 0.55%   |
| WDC WD10EZEX-08WN4A0 1TB             | 2         | 2      | 0.55%   |
| WDC WD1001FALS-40U9B0 1TB            | 2         | 2      | 0.55%   |
| Toshiba MK1652GSX 160GB              | 2         | 2      | 0.55%   |
| Toshiba HDWD110 1TB                  | 2         | 2      | 0.55%   |
| SK hynix SC401 SATA 512GB SSD        | 2         | 2      | 0.55%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 0.55%   |
| Seagate ST9500325AS 500GB            | 2         | 2      | 0.55%   |
| Seagate ST9250315AS 250GB            | 2         | 3      | 0.55%   |
| Seagate ST500LT012-1DG142 500GB      | 2         | 2      | 0.55%   |
| Seagate ST500LM000-1EJ162 500GB      | 2         | 2      | 0.55%   |
| Seagate ST3500418AS 500GB            | 2         | 2      | 0.55%   |
| Seagate ST32000542AS 2TB             | 2         | 2      | 0.55%   |
| Seagate ST3160827AS 160GB            | 2         | 2      | 0.55%   |
| Seagate ST1000DM003-1SB102 1TB       | 2         | 2      | 0.55%   |
| SanDisk SSD PLUS 240GB               | 2         | 2      | 0.55%   |
| SanDisk SSD PLUS 240 GB              | 2         | 2      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 99     | 22.29%  |
| WDC                 | 75        | 95     | 21.43%  |
| Samsung Electronics | 35        | 41     | 10%     |
| Toshiba             | 30        | 35     | 8.57%   |
| Hitachi             | 25        | 25     | 7.14%   |
| Crucial             | 17        | 21     | 4.86%   |
| HGST                | 14        | 15     | 4%      |
| SanDisk             | 13        | 13     | 3.71%   |
| Intel               | 11        | 11     | 3.14%   |
| SK hynix            | 9         | 9      | 2.57%   |
| Kingston            | 8         | 8      | 2.29%   |
| Micron Technology   | 5         | 5      | 1.43%   |
| A-DATA Technology   | 5         | 5      | 1.43%   |
| OCZ                 | 3         | 3      | 0.86%   |
| Maxtor              | 3         | 4      | 0.86%   |
| Apple               | 3         | 3      | 0.86%   |
| Fujitsu             | 2         | 2      | 0.57%   |
| Zheino              | 1         | 2      | 0.29%   |
| XPG                 | 1         | 1      | 0.29%   |
| VISIPRO             | 1         | 1      | 0.29%   |
| VENO                | 1         | 1      | 0.29%   |
| tecmiyo             | 1         | 3      | 0.29%   |
| SPCC                | 1         | 1      | 0.29%   |
| R580                | 1         | 1      | 0.29%   |
| Neo                 | 1         | 1      | 0.29%   |
| Mushkin             | 1         | 1      | 0.29%   |
| LITEONIT            | 1         | 1      | 0.29%   |
| Drevo               | 1         | 1      | 0.29%   |
| BAITITON            | 1         | 1      | 0.29%   |
| ASMT                | 1         | 1      | 0.29%   |
| ASENNO              | 1         | 1      | 0.29%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 78        | 99     | 32.23%  |
| WDC                 | 73        | 93     | 30.17%  |
| Toshiba             | 26        | 31     | 10.74%  |
| Hitachi             | 25        | 25     | 10.33%  |
| Samsung Electronics | 17        | 22     | 7.02%   |
| HGST                | 14        | 15     | 5.79%   |
| Maxtor              | 3         | 4      | 1.24%   |
| Apple               | 3         | 3      | 1.24%   |
| Fujitsu             | 2         | 2      | 0.83%   |
| ASMT                | 1         | 1      | 0.41%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 221       | 295    | 67.58%  |
| SSD  | 87        | 97     | 26.61%  |
| NVMe | 19        | 19     | 5.81%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB         | 1         | 1      | 20%     |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 20%     |
| OCZ VERTEX460A 480GB SSD          | 1         | 1      | 20%     |
| Intel SSDSC2KB960G8 960GB         | 1         | 1      | 20%     |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| OCZ                 | 1         | 1      | 20%     |
| Intel               | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1615      | 2843   | 45.54%  |
| Detected | 1609      | 3561   | 45.38%  |
| Malfunc  | 318       | 411    | 8.97%   |
| Failed   | 4         | 5      | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2023      | 48.32%  |
| AMD                              | 726       | 17.34%  |
| Samsung Electronics              | 410       | 9.79%   |
| SanDisk                          | 202       | 4.82%   |
| SK hynix                         | 104       | 2.48%   |
| Kingston Technology Company      | 81        | 1.93%   |
| ASMedia Technology               | 75        | 1.79%   |
| Toshiba America Info Systems     | 73        | 1.74%   |
| Phison Electronics               | 68        | 1.62%   |
| Micron Technology                | 48        | 1.15%   |
| Silicon Motion                   | 44        | 1.05%   |
| JMicron Technology               | 44        | 1.05%   |
| Micron/Crucial Technology        | 42        | 1%      |
| Marvell Technology Group         | 37        | 0.88%   |
| KIOXIA                           | 35        | 0.84%   |
| Nvidia                           | 33        | 0.79%   |
| ADATA Technology                 | 33        | 0.79%   |
| Realtek Semiconductor            | 16        | 0.38%   |
| Solid State Storage Technology   | 12        | 0.29%   |
| Broadcom / LSI                   | 12        | 0.29%   |
| Lite-On Technology               | 10        | 0.24%   |
| Union Memory (Shenzhen)          | 8         | 0.19%   |
| VIA Technologies                 | 7         | 0.17%   |
| Silicon Image                    | 7         | 0.17%   |
| LSI Logic / Symbios Logic        | 7         | 0.17%   |
| Apple                            | 6         | 0.14%   |
| Seagate Technology               | 4         | 0.1%    |
| Lenovo                           | 4         | 0.1%    |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| Integrated Technology Express    | 2         | 0.05%   |
| INNOGRIT                         | 2         | 0.05%   |
| Adaptec                          | 2         | 0.05%   |
| Zhaoxin                          | 1         | 0.02%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| Promise Technology               | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| 3ware                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 517       | 10.84%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 248       | 5.2%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 175       | 3.67%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 160       | 3.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 141       | 2.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 129       | 2.7%    |
| AMD 400 Series Chipset SATA Controller                                         | 108       | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 91        | 1.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 81        | 1.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 81        | 1.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 79        | 1.66%   |
| Intel Volume Management Device NVMe RAID Controller                            | 78        | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 75        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 69        | 1.45%   |
| Samsung NVMe SSD Controller 980                                                | 68        | 1.43%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 68        | 1.43%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 64        | 1.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 61        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                         | 58        | 1.22%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 56        | 1.17%   |
| Intel SSD 660P Series                                                          | 55        | 1.15%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 51        | 1.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 51        | 1.07%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 50        | 1.05%   |
| Micron Non-Volatile memory controller                                          | 48        | 1.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 47        | 0.99%   |
| Intel SATA Controller [RAID mode]                                              | 47        | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                          | 47        | 0.99%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 47        | 0.99%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 42        | 0.88%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 39        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 39        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 39        | 0.82%   |
| AMD 300 Series Chipset SATA Controller                                         | 39        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 37        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 37        | 0.78%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 34        | 0.71%   |
| AMD FCH SATA Controller D                                                      | 34        | 0.71%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 33        | 0.69%   |
| Phison E12 NVMe Controller                                                     | 33        | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2357      | 56.25%  |
| NVMe | 1208      | 28.83%  |
| RAID | 306       | 7.3%    |
| IDE  | 302       | 7.21%   |
| SAS  | 11        | 0.26%   |
| SCSI | 6         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2277      | 72.22%  |
| AMD           | 869       | 27.56%  |
| ARM           | 3         | 0.1%    |
| sifive,u74-mc | 1         | 0.03%   |
| QUALCOMM      | 1         | 0.03%   |
| Phytium       | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 51        | 1.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 42        | 1.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 42        | 1.33%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 36        | 1.14%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 36        | 1.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 35        | 1.11%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 34        | 1.08%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 34        | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 34        | 1.08%   |
| AMD Ryzen 5 3600 6-Core Processor             | 34        | 1.08%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 31        | 0.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 0.95%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 0.92%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 27        | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.82%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 25        | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 24        | 0.76%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 22        | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 22        | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.66%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 20        | 0.63%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 18        | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 18        | 0.57%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 18        | 0.57%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 17        | 0.54%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 17        | 0.54%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 17        | 0.54%   |
| AMD FX-8350 Eight-Core Processor              | 17        | 0.54%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.51%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 16        | 0.51%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 15        | 0.47%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 15        | 0.47%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 15        | 0.47%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 15        | 0.47%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 15        | 0.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 14        | 0.44%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 14        | 0.44%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 14        | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 755       | 23.89%  |
| Intel Core i5           | 701       | 22.18%  |
| AMD Ryzen 5             | 248       | 7.85%   |
| Other                   | 204       | 6.46%   |
| AMD Ryzen 7             | 194       | 6.14%   |
| Intel Core i3           | 169       | 5.35%   |
| Intel Celeron           | 107       | 3.39%   |
| Intel Core 2 Duo        | 78        | 2.47%   |
| Intel Xeon              | 73        | 2.31%   |
| AMD Ryzen 9             | 69        | 2.18%   |
| Intel Pentium           | 60        | 1.9%    |
| AMD FX                  | 58        | 1.84%   |
| AMD Ryzen 3             | 38        | 1.2%    |
| Intel Core i9           | 29        | 0.92%   |
| AMD A10                 | 29        | 0.92%   |
| Intel Atom              | 25        | 0.79%   |
| AMD A8                  | 24        | 0.76%   |
| AMD A6                  | 24        | 0.76%   |
| Intel Pentium Dual-Core | 22        | 0.7%    |
| AMD Ryzen 7 PRO         | 21        | 0.66%   |
| Intel Core 2 Quad       | 19        | 0.6%    |
| AMD Phenom II X4        | 19        | 0.6%    |
| AMD Athlon II X4        | 14        | 0.44%   |
| AMD A4                  | 13        | 0.41%   |
| Intel Pentium Silver    | 12        | 0.38%   |
| AMD Ryzen 5 PRO         | 11        | 0.35%   |
| AMD Athlon              | 9         | 0.28%   |
| Intel Genuine           | 8         | 0.25%   |
| AMD Ryzen Threadripper  | 8         | 0.25%   |
| AMD E1                  | 8         | 0.25%   |
| AMD E                   | 8         | 0.25%   |
| AMD Athlon II X2        | 8         | 0.25%   |
| Intel Pentium Dual      | 7         | 0.22%   |
| AMD Athlon 64 X2        | 7         | 0.22%   |
| AMD Phenom II X6        | 6         | 0.19%   |
| AMD E2                  | 6         | 0.19%   |
| Intel Core m3           | 5         | 0.16%   |
| Intel Core 2            | 5         | 0.16%   |
| Intel Celeron Dual-Core | 5         | 0.16%   |
| AMD Phenom II X2        | 5         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1288      | 40.77%  |
| 2       | 1021      | 32.32%  |
| 6       | 404       | 12.79%  |
| 8       | 284       | 8.99%   |
| 12      | 57        | 1.8%    |
| 1       | 33        | 1.04%   |
| 16      | 30        | 0.95%   |
| 14      | 14        | 0.44%   |
| 10      | 10        | 0.32%   |
| 3       | 5         | 0.16%   |
| 20      | 3         | 0.09%   |
| 32      | 2         | 0.06%   |
| 24      | 2         | 0.06%   |
| 18      | 2         | 0.06%   |
| Unknown | 2         | 0.06%   |
| 64      | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3128      | 99.21%  |
| 2       | 21        | 0.67%   |
| Unknown | 2         | 0.06%   |
| 4       | 1         | 0.03%   |
| 3       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2357      | 74.59%  |
| 1       | 801       | 25.35%  |
| Unknown | 2         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3148      | 99.84%  |
| 32-bit         | 2         | 0.06%   |
| Unknown        | 2         | 0.06%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 759       | 23.4%   |
| 0x306a9    | 164       | 5.06%   |
| 0x306c3    | 150       | 4.62%   |
| 0x206a7    | 150       | 4.62%   |
| 0x906ea    | 112       | 3.45%   |
| 0x806ec    | 96        | 2.96%   |
| 0x806c1    | 85        | 2.62%   |
| 0x806ea    | 84        | 2.59%   |
| 0x40651    | 79        | 2.44%   |
| 0x1067a    | 72        | 2.22%   |
| 0x906e9    | 70        | 2.16%   |
| 0x806e9    | 69        | 2.13%   |
| 0x08701021 | 67        | 2.07%   |
| 0x506e3    | 62        | 1.91%   |
| 0x406e3    | 53        | 1.63%   |
| 0x08108109 | 48        | 1.48%   |
| 0x0800820d | 45        | 1.39%   |
| 0x306d4    | 42        | 1.29%   |
| 0x0a50000c | 39        | 1.2%    |
| 0x08600106 | 39        | 1.2%    |
| 0x08701013 | 38        | 1.17%   |
| 0x06000852 | 37        | 1.14%   |
| 0x08108102 | 34        | 1.05%   |
| 0xa0652    | 33        | 1.02%   |
| 0x806eb    | 32        | 0.99%   |
| 0x706e5    | 31        | 0.96%   |
| 0x906ed    | 26        | 0.8%    |
| 0x010000c8 | 26        | 0.8%    |
| 0x20655    | 25        | 0.77%   |
| 0x706a1    | 22        | 0.68%   |
| 0x406c4    | 21        | 0.65%   |
| 0x706a8    | 19        | 0.59%   |
| 0x906a3    | 18        | 0.55%   |
| 0x30678    | 18        | 0.55%   |
| 0x10676    | 18        | 0.55%   |
| 0x08608103 | 18        | 0.55%   |
| 0x06001119 | 18        | 0.55%   |
| 0x6fb      | 17        | 0.52%   |
| 0x08600104 | 17        | 0.52%   |
| 0x806d1    | 16        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 622       | 19.67%  |
| Haswell          | 318       | 10.06%  |
| IvyBridge        | 220       | 6.96%   |
| Zen 2            | 218       | 6.89%   |
| SandyBridge      | 195       | 6.17%   |
| Zen+             | 161       | 5.09%   |
| Skylake          | 156       | 4.93%   |
| TigerLake        | 121       | 3.83%   |
| Penryn           | 108       | 3.42%   |
| Zen 3            | 106       | 3.35%   |
| Zen              | 81        | 2.56%   |
| CometLake        | 80        | 2.53%   |
| Piledriver       | 75        | 2.37%   |
| Unknown          | 69        | 2.18%   |
| IceLake          | 64        | 2.02%   |
| Westmere         | 62        | 1.96%   |
| K10              | 61        | 1.93%   |
| Goldmont plus    | 57        | 1.8%    |
| Broadwell        | 57        | 1.8%    |
| Silvermont       | 53        | 1.68%   |
| Core             | 50        | 1.58%   |
| Excavator        | 36        | 1.14%   |
| Nehalem          | 35        | 1.11%   |
| Alderlake Hybrid | 26        | 0.82%   |
| Goldmont         | 19        | 0.6%    |
| Puma             | 17        | 0.54%   |
| Steamroller      | 16        | 0.51%   |
| K10 Llano        | 16        | 0.51%   |
| K8 Hammer        | 14        | 0.44%   |
| Bobcat           | 14        | 0.44%   |
| Jaguar           | 13        | 0.41%   |
| NetBurst         | 7         | 0.22%   |
| Bulldozer        | 7         | 0.22%   |
| Bonnell          | 5         | 0.16%   |
| Tremont          | 1         | 0.03%   |
| K8 & K10 hybrid  | 1         | 0.03%   |
| K6               | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1744      | 45.73%  |
| Nvidia                           | 1168      | 30.62%  |
| AMD                              | 887       | 23.26%  |
| ASPEED Technology                | 7         | 0.18%   |
| Matrox Electronics Systems       | 5         | 0.13%   |
| Zhaoxin                          | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 132       | 3.38%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 123       | 3.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 112       | 2.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 109       | 2.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 100       | 2.56%   |
| AMD Renoir                                                                               | 94        | 2.41%   |
| Intel UHD Graphics 620                                                                   | 93        | 2.38%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 86        | 2.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 85        | 2.18%   |
| Intel HD Graphics 620                                                                    | 79        | 2.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 73        | 1.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 67        | 1.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 64        | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 62        | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 61        | 1.56%   |
| Intel HD Graphics 630                                                                    | 54        | 1.38%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 49        | 1.25%   |
| Intel HD Graphics 5500                                                                   | 47        | 1.2%    |
| Intel HD Graphics 530                                                                    | 47        | 1.2%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 46        | 1.18%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 46        | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 43        | 1.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 41        | 1.05%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 37        | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 32        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 31        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 31        | 0.79%   |
| AMD Lucienne                                                                             | 29        | 0.74%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 28        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 28        | 0.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 0.69%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 27        | 0.69%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 22        | 0.56%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 22        | 0.56%   |
| Intel Iris Plus Graphics G7                                                              | 22        | 0.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 0.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 21        | 0.54%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 21        | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 20        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1144      | 36.15%  |
| 1 x AMD                  | 695       | 21.96%  |
| 1 x Nvidia               | 611       | 19.3%   |
| Intel + Nvidia           | 484       | 15.29%  |
| Intel + AMD              | 89        | 2.81%   |
| 2 x AMD                  | 53        | 1.67%   |
| AMD + Nvidia             | 51        | 1.61%   |
| 2 x Nvidia               | 14        | 0.44%   |
| Other                    | 6         | 0.19%   |
| 1 x ASPEED               | 4         | 0.13%   |
| Nvidia + ASPEED          | 3         | 0.09%   |
| 3 x Nvidia               | 2         | 0.06%   |
| Nvidia + Matrox          | 2         | 0.06%   |
| 1 x Matrox               | 2         | 0.06%   |
| 2 x Intel                | 1         | 0.03%   |
| 1 x Zhaoxin              | 1         | 0.03%   |
| 1 x SiS                  | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |
| AMD + Matrox             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2293      | 71.9%   |
| Proprietary | 833       | 26.12%  |
| Unknown     | 63        | 1.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1692      | 52.37%  |
| 1.01-2.0   | 402       | 12.44%  |
| 0.01-0.5   | 285       | 8.82%   |
| 3.01-4.0   | 260       | 8.05%   |
| 0.51-1.0   | 252       | 7.8%    |
| 7.01-8.0   | 168       | 5.2%    |
| 5.01-6.0   | 95        | 2.94%   |
| 8.01-16.0  | 37        | 1.15%   |
| 2.01-3.0   | 32        | 0.99%   |
| 16.01-24.0 | 4         | 0.12%   |
| 4.01-5.0   | 3         | 0.09%   |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 471       | 12.65%  |
| AU Optronics            | 407       | 10.93%  |
| LG Display              | 330       | 8.86%   |
| BOE                     | 306       | 8.22%   |
| Chimei Innolux          | 299       | 8.03%   |
| Dell                    | 249       | 6.69%   |
| Goldstar                | 204       | 5.48%   |
| Acer                    | 140       | 3.76%   |
| Hewlett-Packard         | 129       | 3.46%   |
| BenQ                    | 102       | 2.74%   |
| Ancor Communications    | 96        | 2.58%   |
| Sharp                   | 92        | 2.47%   |
| AOC                     | 91        | 2.44%   |
| Philips                 | 87        | 2.34%   |
| Lenovo                  | 51        | 1.37%   |
| ViewSonic               | 49        | 1.32%   |
| Iiyama                  | 42        | 1.13%   |
| Chi Mei Optoelectronics | 42        | 1.13%   |
| PANDA                   | 39        | 1.05%   |
| ASUSTek Computer        | 36        | 0.97%   |
| Apple                   | 34        | 0.91%   |
| LG Electronics          | 29        | 0.78%   |
| InfoVision              | 27        | 0.73%   |
| Unknown                 | 22        | 0.59%   |
| Sony                    | 20        | 0.54%   |
| Panasonic               | 18        | 0.48%   |
| NEC Computers           | 17        | 0.46%   |
| HannStar                | 12        | 0.32%   |
| Eizo                    | 11        | 0.3%    |
| Sceptre Tech            | 10        | 0.27%   |
| Toshiba                 | 9         | 0.24%   |
| MSI                     | 9         | 0.24%   |
| Medion                  | 9         | 0.24%   |
| CSO                     | 9         | 0.24%   |
| Vizio                   | 8         | 0.21%   |
| Vestel Elektronik       | 7         | 0.19%   |
| Idek Iiyama             | 7         | 0.19%   |
| LG Philips              | 6         | 0.16%   |
| HKC                     | 5         | 0.13%   |
| Gigabyte Technology     | 5         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 20        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 17        | 0.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 17        | 0.44%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 16        | 0.41%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 15        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 15        | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 14        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 13        | 0.33%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 12        | 0.31%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 11        | 0.28%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 11        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 10        | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 10        | 0.26%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 10        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 9         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 9         | 0.23%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 8         | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 8         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 8         | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 8         | 0.21%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 8         | 0.21%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 8         | 0.21%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 8         | 0.21%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 7         | 0.18%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 7         | 0.18%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 7         | 0.18%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 7         | 0.18%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch          | 7         | 0.18%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 7         | 0.18%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.18%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 6         | 0.15%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 6         | 0.15%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 6         | 0.15%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 6         | 0.15%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.15%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 6         | 0.15%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 6         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1685      | 47.96%  |
| 1366x768 (WXGA)    | 520       | 14.8%   |
| 3840x2160 (4K)     | 249       | 7.09%   |
| 2560x1440 (QHD)    | 177       | 5.04%   |
| 1600x900 (HD+)     | 130       | 3.7%    |
| 1920x1200 (WUXGA)  | 107       | 3.05%   |
| 1680x1050 (WSXGA+) | 88        | 2.5%    |
| 1280x1024 (SXGA)   | 76        | 2.16%   |
| Unknown            | 69        | 1.96%   |
| 1440x900 (WXGA+)   | 45        | 1.28%   |
| 3440x1440          | 41        | 1.17%   |
| 2560x1080          | 39        | 1.11%   |
| 1280x800 (WXGA)    | 36        | 1.02%   |
| 3840x1080          | 29        | 0.83%   |
| 1360x768           | 25        | 0.71%   |
| 2560x1600          | 24        | 0.68%   |
| 2880x1800          | 17        | 0.48%   |
| 2160x1440          | 14        | 0.4%    |
| 3840x2400          | 12        | 0.34%   |
| 1024x768 (XGA)     | 11        | 0.31%   |
| 3840x1200          | 9         | 0.26%   |
| 1920x540           | 9         | 0.26%   |
| 1600x1200          | 9         | 0.26%   |
| 3200x1800 (QHD+)   | 7         | 0.2%    |
| 4480x1440          | 6         | 0.17%   |
| 2240x1400          | 5         | 0.14%   |
| 1920x1280          | 5         | 0.14%   |
| 3840x1600          | 4         | 0.11%   |
| 2256x1504          | 4         | 0.11%   |
| 5760x1080          | 3         | 0.09%   |
| 3600x1080          | 3         | 0.09%   |
| 3456x2160          | 3         | 0.09%   |
| 3200x1080          | 3         | 0.09%   |
| 2736x1824          | 3         | 0.09%   |
| 2520x1680          | 3         | 0.09%   |
| 2288x1287          | 3         | 0.09%   |
| 1280x720 (HD)      | 3         | 0.09%   |
| 7680x2160          | 2         | 0.06%   |
| 5760x2160          | 2         | 0.06%   |
| 4480x1080          | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 914       | 24.64%  |
| 27      | 317       | 8.55%   |
| 13      | 308       | 8.3%    |
| 24      | 306       | 8.25%   |
| 14      | 276       | 7.44%   |
| 23      | 265       | 7.14%   |
| 17      | 216       | 5.82%   |
| Unknown | 216       | 5.82%   |
| 21      | 200       | 5.39%   |
| 31      | 85        | 2.29%   |
| 34      | 72        | 1.94%   |
| 19      | 69        | 1.86%   |
| 22      | 59        | 1.59%   |
| 20      | 51        | 1.38%   |
| 12      | 48        | 1.29%   |
| 18      | 41        | 1.11%   |
| 11      | 38        | 1.02%   |
| 16      | 27        | 0.73%   |
| 84      | 23        | 0.62%   |
| 25      | 22        | 0.59%   |
| 32      | 20        | 0.54%   |
| 54      | 17        | 0.46%   |
| 72      | 16        | 0.43%   |
| 26      | 10        | 0.27%   |
| 40      | 8         | 0.22%   |
| 47      | 6         | 0.16%   |
| 46      | 6         | 0.16%   |
| 42      | 6         | 0.16%   |
| 52      | 5         | 0.13%   |
| 48      | 5         | 0.13%   |
| 37      | 5         | 0.13%   |
| 28      | 5         | 0.13%   |
| 60      | 4         | 0.11%   |
| 39      | 4         | 0.11%   |
| 10      | 4         | 0.11%   |
| 74      | 3         | 0.08%   |
| 49      | 3         | 0.08%   |
| 43      | 3         | 0.08%   |
| 36      | 3         | 0.08%   |
| 29      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1369      | 38%     |
| 501-600        | 802       | 22.26%  |
| 401-500        | 371       | 10.3%   |
| 351-400        | 250       | 6.94%   |
| 201-300        | 242       | 6.72%   |
| Unknown        | 216       | 6%      |
| 601-700        | 127       | 3.52%   |
| 701-800        | 96        | 2.66%   |
| 1001-1500      | 54        | 1.5%    |
| 1501-2000      | 44        | 1.22%   |
| 801-900        | 18        | 0.5%    |
| 901-1000       | 9         | 0.25%   |
| More than 2000 | 2         | 0.06%   |
| 1-100          | 2         | 0.06%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2474      | 76.26%  |
| 16/10   | 345       | 10.64%  |
| Unknown | 190       | 5.86%   |
| 21/9    | 79        | 2.44%   |
| 5/4     | 74        | 2.28%   |
| 3/2     | 37        | 1.14%   |
| 4/3     | 25        | 0.77%   |
| 32/9    | 10        | 0.31%   |
| 6/5     | 2         | 0.06%   |
| 1.96    | 2         | 0.06%   |
| 1.00    | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |
| 1.98    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 914       | 25.11%  |
| 201-250        | 626       | 17.2%   |
| 81-90          | 451       | 12.39%  |
| 301-350        | 323       | 8.87%   |
| Unknown        | 216       | 5.93%   |
| 351-500        | 183       | 5.03%   |
| 151-200        | 173       | 4.75%   |
| 121-130        | 157       | 4.31%   |
| 71-80          | 140       | 3.85%   |
| 251-300        | 125       | 3.43%   |
| More than 1000 | 80        | 2.2%    |
| 141-150        | 70        | 1.92%   |
| 501-1000       | 48        | 1.32%   |
| 61-70          | 40        | 1.1%    |
| 51-60          | 39        | 1.07%   |
| 131-140        | 21        | 0.58%   |
| 111-120        | 20        | 0.55%   |
| 91-100         | 7         | 0.19%   |
| 41-50          | 4         | 0.11%   |
| 1-40           | 3         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1113      | 31.49%  |
| 121-160       | 1016      | 28.74%  |
| 101-120       | 793       | 22.43%  |
| Unknown       | 216       | 6.11%   |
| 161-240       | 210       | 5.94%   |
| More than 240 | 108       | 3.06%   |
| 1-50          | 79        | 2.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2388      | 74.23%  |
| 2     | 672       | 20.89%  |
| 3     | 80        | 2.49%   |
| 0     | 68        | 2.11%   |
| 4     | 9         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1815      | 38.05%  |
| Intel                             | 1623      | 34.03%  |
| Qualcomm Atheros                  | 492       | 10.31%  |
| Broadcom                          | 207       | 4.34%   |
| Ralink Technology                 | 58        | 1.22%   |
| MediaTek                          | 58        | 1.22%   |
| TP-Link                           | 57        | 1.19%   |
| Ralink                            | 42        | 0.88%   |
| Broadcom Limited                  | 35        | 0.73%   |
| Marvell Technology Group          | 29        | 0.61%   |
| Nvidia                            | 27        | 0.57%   |
| Samsung Electronics               | 20        | 0.42%   |
| ASIX Electronics                  | 18        | 0.38%   |
| Qualcomm Atheros Communications   | 17        | 0.36%   |
| Aquantia                          | 17        | 0.36%   |
| NetGear                           | 16        | 0.34%   |
| Microsoft                         | 16        | 0.34%   |
| DisplayLink                       | 15        | 0.31%   |
| Xiaomi                            | 14        | 0.29%   |
| Huawei Technologies               | 14        | 0.29%   |
| Qualcomm                          | 12        | 0.25%   |
| Sierra Wireless                   | 11        | 0.23%   |
| Lenovo                            | 11        | 0.23%   |
| D-Link                            | 11        | 0.23%   |
| Dell                              | 10        | 0.21%   |
| Ericsson Business Mobile Networks | 9         | 0.19%   |
| Edimax Technology                 | 8         | 0.17%   |
| Linksys                           | 7         | 0.15%   |
| ASUSTek Computer                  | 7         | 0.15%   |
| JMicron Technology                | 6         | 0.13%   |
| D-Link System                     | 6         | 0.13%   |
| Apple                             | 6         | 0.13%   |
| Hewlett-Packard                   | 4         | 0.08%   |
| Google                            | 4         | 0.08%   |
| Fibocom                           | 4         | 0.08%   |
| Belkin Components                 | 4         | 0.08%   |
| AVM                               | 4         | 0.08%   |
| VIA Technologies                  | 3         | 0.06%   |
| T & A Mobile Phones               | 3         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1274      | 22.86%  |
| Intel Wi-Fi 6 AX200                                               | 195       | 3.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 167       | 3%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 114       | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 108       | 1.94%   |
| Intel I211 Gigabit Network Connection                             | 105       | 1.88%   |
| Intel Wireless 8265 / 8275                                        | 103       | 1.85%   |
| Intel Wi-Fi 6 AX201                                               | 87        | 1.56%   |
| Intel Wireless 7260                                               | 81        | 1.45%   |
| Realtek RTL8125 2.5GbE Controller                                 | 80        | 1.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 80        | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 78        | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 78        | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 71        | 1.27%   |
| Intel Wireless 7265                                               | 70        | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 66        | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 65        | 1.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 60        | 1.08%   |
| Intel Ethernet Connection (2) I219-V                              | 56        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 55        | 0.99%   |
| Intel Wireless 3165                                               | 52        | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 51        | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 47        | 0.84%   |
| Intel Wireless-AC 9260                                            | 46        | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 46        | 0.83%   |
| Intel Wireless 8260                                               | 43        | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 42        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 37        | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 36        | 0.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 34        | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 34        | 0.61%   |
| Intel Ethernet Controller I225-V                                  | 33        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 33        | 0.59%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 32        | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 30        | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 29        | 0.52%   |
| Ralink MT7601U Wireless Adapter                                   | 28        | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 28        | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 26        | 0.47%   |
| Intel Wireless 3160                                               | 23        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1248      | 48.58%  |
| Realtek Semiconductor           | 415       | 16.15%  |
| Qualcomm Atheros                | 384       | 14.95%  |
| Broadcom                        | 143       | 5.57%   |
| Ralink Technology               | 58        | 2.26%   |
| MediaTek                        | 54        | 2.1%    |
| TP-Link                         | 51        | 1.99%   |
| Ralink                          | 42        | 1.63%   |
| Broadcom Limited                | 29        | 1.13%   |
| Qualcomm Atheros Communications | 17        | 0.66%   |
| NetGear                         | 16        | 0.62%   |
| Microsoft                       | 15        | 0.58%   |
| Sierra Wireless                 | 11        | 0.43%   |
| D-Link                          | 11        | 0.43%   |
| Edimax Technology               | 8         | 0.31%   |
| Qualcomm                        | 7         | 0.27%   |
| ASUSTek Computer                | 7         | 0.27%   |
| Marvell Technology Group        | 6         | 0.23%   |
| Linksys                         | 6         | 0.23%   |
| Dell                            | 5         | 0.19%   |
| Fibocom                         | 4         | 0.16%   |
| D-Link System                   | 4         | 0.16%   |
| Belkin Components               | 4         | 0.16%   |
| AVM                             | 4         | 0.16%   |
| Wacom                           | 2         | 0.08%   |
| Mercucys                        | 2         | 0.08%   |
| ZyXEL Communications            | 1         | 0.04%   |
| ZyDAS                           | 1         | 0.04%   |
| Wilocity                        | 1         | 0.04%   |
| Texas Instruments               | 1         | 0.04%   |
| Tenda                           | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Philips (or NXP)                | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| LG Electronics                  | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| Hewlett-Packard                 | 1         | 0.04%   |
| Guillemot                       | 1         | 0.04%   |
| Gemtek                          | 1         | 0.04%   |
| AirTies Wireless Networks       | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 195       | 7.53%   |
| Intel Wireless 8265 / 8275                                     | 103       | 3.98%   |
| Intel Wi-Fi 6 AX201                                            | 87        | 3.36%   |
| Intel Wireless 7260                                            | 81        | 3.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 80        | 3.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 78        | 3.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 78        | 3.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 71        | 2.74%   |
| Intel Wireless 7265                                            | 70        | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 66        | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 65        | 2.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 60        | 2.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 55        | 2.13%   |
| Intel Wireless 3165                                            | 52        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 51        | 1.97%   |
| Intel Wireless-AC 9260                                         | 46        | 1.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 46        | 1.78%   |
| Intel Wireless 8260                                            | 43        | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 42        | 1.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 37        | 1.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 36        | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 34        | 1.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 33        | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 32        | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 29        | 1.12%   |
| Ralink MT7601U Wireless Adapter                                | 28        | 1.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 26        | 1%      |
| Intel Wireless 3160                                            | 23        | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 23        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 22        | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 22        | 0.85%   |
| Realtek 802.11n WLAN Adapter                                   | 22        | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 22        | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                  | 22        | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 21        | 0.81%   |
| Realtek 802.11ac NIC                                           | 20        | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 20        | 0.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 20        | 0.77%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 18        | 0.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 17        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1638      | 57.07%  |
| Intel                            | 790       | 27.53%  |
| Qualcomm Atheros                 | 141       | 4.91%   |
| Broadcom                         | 81        | 2.82%   |
| Nvidia                           | 27        | 0.94%   |
| Marvell Technology Group         | 23        | 0.8%    |
| Samsung Electronics              | 20        | 0.7%    |
| ASIX Electronics                 | 18        | 0.63%   |
| Aquantia                         | 17        | 0.59%   |
| DisplayLink                      | 15        | 0.52%   |
| Xiaomi                           | 14        | 0.49%   |
| Lenovo                           | 11        | 0.38%   |
| Huawei Technologies              | 11        | 0.38%   |
| Broadcom Limited                 | 7         | 0.24%   |
| TP-Link                          | 6         | 0.21%   |
| JMicron Technology               | 6         | 0.21%   |
| Apple                            | 6         | 0.21%   |
| Qualcomm                         | 5         | 0.17%   |
| MediaTek                         | 4         | 0.14%   |
| Google                           | 4         | 0.14%   |
| VIA Technologies                 | 3         | 0.1%    |
| T & A Mobile Phones              | 3         | 0.1%    |
| ZTE WCDMA Technologies MSM       | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| D-Link System                    | 2         | 0.07%   |
| 3Com                             | 2         | 0.07%   |
| QNAP System                      | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.03%   |
| Motorola PCS                     | 1         | 0.03%   |
| Motorola BCS                     | 1         | 0.03%   |
| Microsoft                        | 1         | 0.03%   |
| Mellanox Technologies            | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| ICS Advent                       | 1         | 0.03%   |
| HMD Global                       | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| Elecom                           | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1274      | 43.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 167       | 5.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 114       | 3.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 108       | 3.66%   |
| Intel I211 Gigabit Network Connection                             | 105       | 3.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 80        | 2.71%   |
| Intel Ethernet Connection (2) I219-V                              | 56        | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 47        | 1.59%   |
| Intel Ethernet Connection (7) I219-V                              | 34        | 1.15%   |
| Intel Ethernet Controller I225-V                                  | 33        | 1.12%   |
| Intel Ethernet Connection (4) I219-LM                             | 30        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                             | 28        | 0.95%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.78%   |
| Intel 82579V Gigabit Network Connection                           | 23        | 0.78%   |
| Intel Ethernet Connection (2) I218-V                              | 21        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 20        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.61%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.58%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 17        | 0.58%   |
| Intel Ethernet Connection (6) I219-V                              | 17        | 0.58%   |
| Intel 82574L Gigabit Network Connection                           | 17        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 15        | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 14        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 13        | 0.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 0.44%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.37%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 11        | 0.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10        | 0.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 10        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2682      | 51.99%  |
| WiFi     | 2442      | 47.33%  |
| Modem    | 33        | 0.64%   |
| Unknown  | 2         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1909      | 57.16%  |
| Ethernet | 1430      | 42.81%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1698      | 53.8%   |
| 1     | 1322      | 41.89%  |
| 3     | 72        | 2.28%   |
| 0     | 49        | 1.55%   |
| 4     | 12        | 0.38%   |
| 6     | 3         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 2656      | 83.18%  |
| Yes     | 536       | 16.79%  |
| Unknown | 1         | 0.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1057      | 50.14%  |
| Realtek Semiconductor           | 209       | 9.91%   |
| Qualcomm Atheros Communications | 171       | 8.11%   |
| Cambridge Silicon Radio         | 158       | 7.5%    |
| Broadcom                        | 113       | 5.36%   |
| IMC Networks                    | 77        | 3.65%   |
| Lite-On Technology              | 69        | 3.27%   |
| Foxconn / Hon Hai               | 51        | 2.42%   |
| ASUSTek Computer                | 34        | 1.61%   |
| Apple                           | 34        | 1.61%   |
| Dell                            | 29        | 1.38%   |
| Realtek                         | 22        | 1.04%   |
| Hewlett-Packard                 | 12        | 0.57%   |
| Toshiba                         | 10        | 0.47%   |
| Ralink                          | 10        | 0.47%   |
| Marvell Semiconductor           | 7         | 0.33%   |
| Foxconn International           | 7         | 0.33%   |
| Ralink Technology               | 5         | 0.24%   |
| MediaTek                        | 5         | 0.24%   |
| Dynex                           | 4         | 0.19%   |
| Alps Electric                   | 4         | 0.19%   |
| TP-Link                         | 3         | 0.14%   |
| Edimax Technology               | 3         | 0.14%   |
| Unknown                         | 2         | 0.09%   |
| Taiyo Yuden                     | 2         | 0.09%   |
| Integrated System Solution      | 2         | 0.09%   |
| Belkin Components               | 2         | 0.09%   |
| Micro Star International        | 1         | 0.05%   |
| Kensington                      | 1         | 0.05%   |
| D-Link                          | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |
| Corsair                         | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 355       | 16.82%  |
| Intel AX201 Bluetooth                               | 200       | 9.47%   |
| Intel AX200 Bluetooth                               | 189       | 8.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 159       | 7.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 158       | 7.48%   |
| Realtek Bluetooth Radio                             | 127       | 6.02%   |
| Qualcomm Atheros  Bluetooth Device                  | 86        | 4.07%   |
| Realtek  Bluetooth 4.2 Adapter                      | 66        | 3.13%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 43        | 2.04%   |
| Intel Wireless-AC 3168 Bluetooth                    | 35        | 1.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 1.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 26        | 1.23%   |
| Lite-On Bluetooth Device                            | 26        | 1.23%   |
| IMC Networks Bluetooth Radio                        | 26        | 1.23%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 25        | 1.18%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 1.09%   |
| Realtek Bluetooth Radio                             | 22        | 1.04%   |
| Intel AX210 Bluetooth                               | 19        | 0.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 19        | 0.9%    |
| Intel Bluetooth Device                              | 18        | 0.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 17        | 0.81%   |
| IMC Networks Bluetooth Device                       | 17        | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 17        | 0.81%   |
| IMC Networks Wireless_Device                        | 16        | 0.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.71%   |
| Apple Bluetooth USB Host Controller                 | 14        | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.62%   |
| Apple Bluetooth Host Controller                     | 13        | 0.62%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.52%   |
| ASUS Bluetooth Device                               | 11        | 0.52%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 10        | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.43%   |
| Lite-On Wireless_Device                             | 9         | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.38%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2216      | 47.85%  |
| AMD                        | 1022      | 22.07%  |
| Nvidia                     | 841       | 18.16%  |
| C-Media Electronics        | 87        | 1.88%   |
| Logitech                   | 36        | 0.78%   |
| Creative Labs              | 33        | 0.71%   |
| GN Netcom                  | 30        | 0.65%   |
| Realtek Semiconductor      | 26        | 0.56%   |
| JMTek                      | 24        | 0.52%   |
| Texas Instruments          | 18        | 0.39%   |
| Razer USA                  | 14        | 0.3%    |
| Plantronics                | 14        | 0.3%    |
| Generalplus Technology     | 14        | 0.3%    |
| Creative Technology        | 14        | 0.3%    |
| Corsair                    | 14        | 0.3%    |
| ASUSTek Computer           | 14        | 0.3%    |
| Lenovo                     | 10        | 0.22%   |
| Kingston Technology        | 9         | 0.19%   |
| SteelSeries ApS            | 8         | 0.17%   |
| Focusrite-Novation         | 8         | 0.17%   |
| Blue Microphones           | 8         | 0.17%   |
| Tenx Technology            | 7         | 0.15%   |
| Sony                       | 7         | 0.15%   |
| Hewlett-Packard            | 7         | 0.15%   |
| VIA Technologies           | 6         | 0.13%   |
| Dell                       | 5         | 0.11%   |
| Yamaha                     | 4         | 0.09%   |
| SAVITECH                   | 4         | 0.09%   |
| BEHRINGER International    | 4         | 0.09%   |
| ZOOM                       | 3         | 0.06%   |
| Unknown                    | 3         | 0.06%   |
| Trust                      | 3         | 0.06%   |
| TerraTec Electronic        | 3         | 0.06%   |
| Samson Technologies        | 3         | 0.06%   |
| Roland                     | 3         | 0.06%   |
| RODE Microphones           | 3         | 0.06%   |
| QinHeng Electronics        | 3         | 0.06%   |
| PreSonus Audio Electronics | 3         | 0.06%   |
| ONN                        | 3         | 0.06%   |
| M-Audio                    | 3         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 322       | 5.83%   |
| Intel Sunrise Point-LP HD Audio                                            | 252       | 4.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 203       | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 183       | 3.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 177       | 3.2%    |
| Intel Cannon Lake PCH cAVS                                                 | 163       | 2.95%   |
| AMD Starship/Matisse HD Audio Controller                                   | 163       | 2.95%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 158       | 2.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 139       | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 124       | 2.24%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 121       | 2.19%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 112       | 2.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 101       | 1.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 101       | 1.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 98        | 1.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 91        | 1.65%   |
| AMD FCH Azalia Controller                                                  | 91        | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                      | 88        | 1.59%   |
| Intel 8 Series HD Audio Controller                                         | 87        | 1.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 72        | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                               | 70        | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 69        | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 64        | 1.16%   |
| Nvidia TU116 High Definition Audio Controller                              | 59        | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 59        | 1.07%   |
| Intel 200 Series PCH HD Audio                                              | 59        | 1.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 57        | 1.03%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 54        | 0.98%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 54        | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 53        | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 52        | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 52        | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 51        | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 51        | 0.92%   |
| AMD Kabini HDMI/DP Audio                                                   | 44        | 0.8%    |
| Nvidia GP104 High Definition Audio Controller                              | 43        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 43        | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 41        | 0.74%   |
| Intel CM238 HD Audio Controller                                            | 39        | 0.71%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 38        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 511       | 21.79%  |
| SK hynix            | 381       | 16.25%  |
| Kingston            | 309       | 13.18%  |
| Micron Technology   | 225       | 9.59%   |
| Unknown             | 167       | 7.12%   |
| Crucial             | 166       | 7.08%   |
| Corsair             | 148       | 6.31%   |
| G.Skill             | 107       | 4.56%   |
| A-DATA Technology   | 45        | 1.92%   |
| Ramaxel Technology  | 36        | 1.54%   |
| Elpida              | 30        | 1.28%   |
| Unknown (ABCD)      | 27        | 1.15%   |
| Nanya Technology    | 25        | 1.07%   |
| Team                | 20        | 0.85%   |
| Patriot             | 16        | 0.68%   |
| Transcend           | 13        | 0.55%   |
| Smart               | 13        | 0.55%   |
| Unknown             | 13        | 0.55%   |
| GOODRAM             | 8         | 0.34%   |
| AMD                 | 6         | 0.26%   |
| Smart Brazil        | 5         | 0.21%   |
| Silicon Power       | 5         | 0.21%   |
| Apacer              | 5         | 0.21%   |
| Wilk                | 4         | 0.17%   |
| Teikon              | 4         | 0.17%   |
| SHARETRONIC         | 3         | 0.13%   |
| CSX                 | 3         | 0.13%   |
| ASint Technology    | 3         | 0.13%   |
| Unifosa             | 2         | 0.09%   |
| Reboto              | 2         | 0.09%   |
| PNY                 | 2         | 0.09%   |
| Kllisre             | 2         | 0.09%   |
| Kingmax             | 2         | 0.09%   |
| Imation             | 2         | 0.09%   |
| Hewlett-Packard     | 2         | 0.09%   |
| Goldkey             | 2         | 0.09%   |
| GLOWAY              | 2         | 0.09%   |
| GeIL                | 2         | 0.09%   |
| Avant               | 2         | 0.09%   |
| Atermiter           | 2         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 0.99%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 0.91%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 22        | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 0.67%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 16        | 0.63%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 16        | 0.63%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.55%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 14        | 0.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 13        | 0.51%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 13        | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.51%   |
| Unknown                                                          | 13        | 0.51%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.47%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.47%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.43%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 11        | 0.43%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.4%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 9         | 0.36%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.36%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.36%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 9         | 0.36%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.32%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 8         | 0.32%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.32%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 8         | 0.32%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1149      | 56.91%  |
| DDR3    | 590       | 29.22%  |
| LPDDR4  | 79        | 3.91%   |
| Unknown | 49        | 2.43%   |
| LPDDR3  | 48        | 2.38%   |
| DDR2    | 47        | 2.33%   |
| SDRAM   | 31        | 1.54%   |
| DDR5    | 12        | 0.59%   |
| DDR     | 7         | 0.35%   |
| LPDDR5  | 6         | 0.3%    |
| DRAM    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1166      | 57.61%  |
| DIMM         | 699       | 34.54%  |
| Row Of Chips | 137       | 6.77%   |
| Chip         | 12        | 0.59%   |
| Unknown      | 5         | 0.25%   |
| FB-DIMM      | 3         | 0.15%   |
| RIMM         | 2         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 944       | 42.83%  |
| 4096  | 573       | 26%     |
| 16384 | 400       | 18.15%  |
| 2048  | 194       | 8.8%    |
| 32768 | 63        | 2.86%   |
| 1024  | 27        | 1.23%   |
| 512   | 1         | 0.05%   |
| 256   | 1         | 0.05%   |
| 128   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 412       | 18.81%  |
| 1600    | 405       | 18.49%  |
| 3200    | 350       | 15.98%  |
| 2400    | 191       | 8.72%   |
| 1333    | 137       | 6.26%   |
| 2133    | 115       | 5.25%   |
| 3600    | 77        | 3.52%   |
| 1334    | 55        | 2.51%   |
| 4267    | 34        | 1.55%   |
| 800     | 32        | 1.46%   |
| 1867    | 31        | 1.42%   |
| 667     | 26        | 1.19%   |
| 2666    | 23        | 1.05%   |
| 3000    | 21        | 0.96%   |
| 3400    | 20        | 0.91%   |
| Unknown | 20        | 0.91%   |
| 3266    | 18        | 0.82%   |
| 3733    | 15        | 0.68%   |
| 3800    | 14        | 0.64%   |
| 1067    | 14        | 0.64%   |
| 1066    | 14        | 0.64%   |
| 8400    | 12        | 0.55%   |
| 2933    | 12        | 0.55%   |
| 3466    | 11        | 0.5%    |
| 4800    | 10        | 0.46%   |
| 1866    | 10        | 0.46%   |
| 4199    | 9         | 0.41%   |
| 3866    | 9         | 0.41%   |
| 2800    | 7         | 0.32%   |
| 6400    | 6         | 0.27%   |
| 4266    | 6         | 0.27%   |
| 400     | 6         | 0.27%   |
| 3333    | 5         | 0.23%   |
| 3151    | 5         | 0.23%   |
| 3066    | 5         | 0.23%   |
| 2048    | 5         | 0.23%   |
| 1800    | 5         | 0.23%   |
| 2000    | 4         | 0.18%   |
| 3666    | 3         | 0.14%   |
| 975     | 3         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 42        | 40.38%  |
| Brother Industries     | 22        | 21.15%  |
| Seiko Epson            | 10        | 9.62%   |
| Samsung Electronics    | 10        | 9.62%   |
| Canon                  | 8         | 7.69%   |
| Xerox                  | 2         | 1.92%   |
| Zebra                  | 1         | 0.96%   |
| SAT                    | 1         | 0.96%   |
| Prolific Technology    | 1         | 0.96%   |
| Pantum                 | 1         | 0.96%   |
| Panasonic (Matsushita) | 1         | 0.96%   |
| Kyocera                | 1         | 0.96%   |
| ICS Advent             | 1         | 0.96%   |
| Dymo-CoStar            | 1         | 0.96%   |
| Datamax-O'Neil         | 1         | 0.96%   |
| Apple                  | 1         | 0.96%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                           | 3         | 2.83%   |
| Seiko Epson L3110 Series                               | 2         | 1.89%   |
| Samsung M2070 Series                                   | 2         | 1.89%   |
| HP OfficeJet Pro 7740 series                           | 2         | 1.89%   |
| HP LaserJet 1018                                       | 2         | 1.89%   |
| HP ENVY 4500 series                                    | 2         | 1.89%   |
| HP DeskJet 2620 All-in-One Printer                     | 2         | 1.89%   |
| Brother HL-L2320D series                               | 2         | 1.89%   |
| Brother HL-2230 series                                 | 2         | 1.89%   |
| Zebra ZTC LP2844-Z-200dpi                              | 1         | 0.94%   |
| Xerox Phaser 6500DN                                    | 1         | 0.94%   |
| Xerox Phaser 3140 and 3155                             | 1         | 0.94%   |
| Seiko Epson XP-3100 Series                             | 1         | 0.94%   |
| Seiko Epson XP-2100 Series                             | 1         | 0.94%   |
| Seiko Epson WF-2530 Series                             | 1         | 0.94%   |
| Seiko Epson Printer                                    | 1         | 0.94%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 0.94%   |
| Seiko Epson L3150 Series                               | 1         | 0.94%   |
| Seiko Epson L220 Series                                | 1         | 0.94%   |
| Seiko Epson L120 Series                                | 1         | 0.94%   |
| SAT SAT38TUSE                                          | 1         | 0.94%   |
| Samsung Xerox Phaser 3117 Laser Printer                | 1         | 0.94%   |
| Samsung SCX-3200 Series                                | 1         | 0.94%   |
| Samsung ML-2250 Series                                 | 1         | 0.94%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 0.94%   |
| Samsung M262x/M282x Xpress Series Laser Printer        | 1         | 0.94%   |
| Samsung CLX-3180 Series                                | 1         | 0.94%   |
| Samsung CLX-3170 Series                                | 1         | 0.94%   |
| Samsung CLP-360 Series                                 | 1         | 0.94%   |
| Prolific PL2305 Parallel Port                          | 1         | 0.94%   |
| Pantum P2200 series                                    | 1         | 0.94%   |
| Panasonic (Matsushita) KX-MB1500RU                     | 1         | 0.94%   |
| Kyocera Mita FS-820                                    | 1         | 0.94%   |
| ICS Advent Parallel Adapter                            | 1         | 0.94%   |
| HP OfficeJet Pro 9010 series                           | 1         | 0.94%   |
| HP OfficeJet 9010 series                               | 1         | 0.94%   |
| HP OfficeJet 5500 series                               | 1         | 0.94%   |
| HP OfficeJet 4650 series                               | 1         | 0.94%   |
| HP Officejet 4630 series                               | 1         | 0.94%   |
| HP OfficeJet 3830 series                               | 1         | 0.94%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 12        | 50%     |
| Seiko Epson     | 6         | 25%     |
| Mustek Systems  | 3         | 12.5%   |
| Hewlett-Packard | 3         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 2         | 8.33%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 8.33%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2         | 8.33%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 2         | 8.33%   |
| Canon CanoScan LiDE 220                                 | 2         | 8.33%   |
| Canon CanoScan LiDE 110                                 | 2         | 8.33%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 4.17%   |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 4.17%   |
| Mustek Systems SNAPSCAN e22                             | 1         | 4.17%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 4.17%   |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 4.17%   |
| HP ScanJet G4010                                        | 1         | 4.17%   |
| HP ScanJet 82x0C                                        | 1         | 4.17%   |
| HP ScanJet 3770                                         | 1         | 4.17%   |
| Canon CanoScan LiDE 60                                  | 1         | 4.17%   |
| Canon CanoScan LIDE 25                                  | 1         | 4.17%   |
| Canon CanoScan LiDE 210                                 | 1         | 4.17%   |
| Canon CanoScan LiDE 120                                 | 1         | 4.17%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 408       | 19.29%  |
| IMC Networks                           | 201       | 9.5%    |
| Microdia                               | 193       | 9.13%   |
| Acer                                   | 173       | 8.18%   |
| Logitech                               | 168       | 7.94%   |
| Realtek Semiconductor                  | 163       | 7.71%   |
| Sunplus Innovation Technology          | 105       | 4.96%   |
| Quanta                                 | 103       | 4.87%   |
| Cheng Uei Precision Industry (Foxlink) | 85        | 4.02%   |
| Suyin                                  | 43        | 2.03%   |
| Syntek                                 | 40        | 1.89%   |
| Silicon Motion                         | 40        | 1.89%   |
| Lite-On Technology                     | 38        | 1.8%    |
| Apple                                  | 35        | 1.65%   |
| Microsoft                              | 33        | 1.56%   |
| Luxvisions Innotech Limited            | 29        | 1.37%   |
| Alcor Micro                            | 27        | 1.28%   |
| Samsung Electronics                    | 22        | 1.04%   |
| Ricoh                                  | 16        | 0.76%   |
| Z-Star Microelectronics                | 12        | 0.57%   |
| Lenovo                                 | 12        | 0.57%   |
| Generalplus Technology                 | 12        | 0.57%   |
| KYE Systems (Mouse Systems)            | 8         | 0.38%   |
| Genesys Logic                          | 8         | 0.38%   |
| Huawei Technologies                    | 7         | 0.33%   |
| Y Media                                | 6         | 0.28%   |
| SunplusIT                              | 6         | 0.28%   |
| Sunplus Technology                     | 6         | 0.28%   |
| MacroSilicon                           | 6         | 0.28%   |
| Cubeternet                             | 6         | 0.28%   |
| ARC International                      | 6         | 0.28%   |
| Unknown                                | 5         | 0.24%   |
| Sonix Technology                       | 5         | 0.24%   |
| Importek                               | 5         | 0.24%   |
| Intel                                  | 4         | 0.19%   |
| GEMBIRD                                | 4         | 0.19%   |
| DJJHFA1BIF5595                         | 4         | 0.19%   |
| Creative Technology                    | 4         | 0.19%   |
| USB Camera                             | 3         | 0.14%   |
| Razer USA                              | 3         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 88        | 4.12%   |
| Microdia Integrated_Webcam_HD                                              | 81        | 3.79%   |
| Realtek Integrated_Webcam_HD                                               | 77        | 3.6%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 61        | 2.85%   |
| Acer Integrated Camera                                                     | 60        | 2.81%   |
| IMC Networks Integrated Camera                                             | 59        | 2.76%   |
| Sunplus Integrated_Webcam_HD                                               | 47        | 2.2%    |
| Chicony HD WebCam                                                          | 43        | 2.01%   |
| Logitech HD Pro Webcam C920                                                | 36        | 1.68%   |
| Logitech Webcam C270                                                       | 35        | 1.64%   |
| Chicony USB2.0 Camera                                                      | 28        | 1.31%   |
| Syntek Integrated Camera                                                   | 27        | 1.26%   |
| Chicony HP HD Camera                                                       | 26        | 1.22%   |
| Acer Lenovo EasyCamera                                                     | 25        | 1.17%   |
| Samsung Galaxy A5 (MTP)                                                    | 21        | 0.98%   |
| Microdia Integrated Webcam                                                 | 21        | 0.98%   |
| Chicony HD User Facing                                                     | 21        | 0.98%   |
| Quanta HD User Facing                                                      | 20        | 0.94%   |
| Microdia USB 2.0 Camera                                                    | 19        | 0.89%   |
| Acer HD Webcam                                                             | 18        | 0.84%   |
| Microdia Webcam Vitade AF                                                  | 17        | 0.8%    |
| Lite-On Integrated Camera                                                  | 15        | 0.7%    |
| Chicony HP Wide Vision HD Camera                                           | 15        | 0.7%    |
| Acer BisonCam, NB Pro                                                      | 15        | 0.7%    |
| Quanta HP TrueVision HD Camera                                             | 14        | 0.66%   |
| Quanta HP HD Camera                                                        | 14        | 0.66%   |
| Microsoft LifeCam HD-3000                                                  | 14        | 0.66%   |
| Chicony HP Truevision HD                                                   | 14        | 0.66%   |
| Apple iPhone5/5C/5S/6                                                      | 14        | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 13        | 0.61%   |
| Chicony Integrated Camera (1280x720@30)                                    | 13        | 0.61%   |
| Alcor Micro USB 2.0 Camera                                                 | 13        | 0.61%   |
| Realtek USB Camera                                                         | 12        | 0.56%   |
| Chicony USB 2.0 Camera                                                     | 12        | 0.56%   |
| Quanta HD Webcam                                                           | 11        | 0.51%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 11        | 0.51%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 11        | 0.51%   |
| Acer BisonCam,NB Pro                                                       | 11        | 0.51%   |
| Realtek Integrated Webcam                                                  | 10        | 0.47%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 10        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 139       | 31.66%  |
| Validity Sensors           | 115       | 26.2%   |
| Shenzhen Goodix Technology | 86        | 19.59%  |
| Elan Microelectronics      | 34        | 7.74%   |
| Upek                       | 21        | 4.78%   |
| AuthenTec                  | 20        | 4.56%   |
| LighTuning Technology      | 15        | 3.42%   |
| STMicroelectronics         | 6         | 1.37%   |
| Focal-systems.Corp         | 2         | 0.46%   |
| DigitalPersona             | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 47        | 10.71%  |
| Shenzhen Goodix  FingerPrint Device                                        | 46        | 10.48%  |
| Unknown                                                                    | 42        | 9.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 25        | 5.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 4.78%   |
| Elan ELAN:Fingerprint                                                      | 21        | 4.78%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 4.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 4.1%    |
| Shenzhen Goodix FingerPrint                                                | 15        | 3.42%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 2.96%   |
| Validity Sensors Synaptics WBDI                                            | 12        | 2.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 2.51%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 2.51%   |
| Elan ELAN:ARM-M4                                                           | 11        | 2.51%   |
| Synaptics  WBDI                                                            | 10        | 2.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 2.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 9         | 2.05%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 1.82%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 1.82%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.59%   |
| AuthenTec AES2810                                                          | 7         | 1.59%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.37%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.14%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.14%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 0.91%   |
| Validity Sensors VFS491                                                    | 4         | 0.91%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.91%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.68%   |
| Synaptics WBDI Device                                                      | 2         | 0.46%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.46%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.46%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.46%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.23%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.23%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 76        | 41.08%  |
| Alcor Micro               | 49        | 26.49%  |
| Upek                      | 13        | 7.03%   |
| O2 Micro                  | 8         | 4.32%   |
| Lenovo                    | 7         | 3.78%   |
| SCM Microsystems          | 4         | 2.16%   |
| Advanced Card Systems     | 4         | 2.16%   |
| OmniKey                   | 3         | 1.62%   |
| Gemalto (was Gemplus)     | 3         | 1.62%   |
| Yubico.com                | 2         | 1.08%   |
| Reiner SCT Kartensysteme  | 2         | 1.08%   |
| Realtek Semiconductor     | 2         | 1.08%   |
| Fujitsu Siemens Computers | 2         | 1.08%   |
| BIT4ID                    | 2         | 1.08%   |
| Watchdata                 | 1         | 0.54%   |
| In Focus Systems          | 1         | 0.54%   |
| Giesecke & Devrient       | 1         | 0.54%   |
| Clay Logic                | 1         | 0.54%   |
| Chicony Electronics       | 1         | 0.54%   |
| Aladdin R.D.              | 1         | 0.54%   |
| Aladdin Knowledge Systems | 1         | 0.54%   |
| Aktiv                     | 1         | 0.54%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 47        | 25.41%  |
| Broadcom 5880                                                                | 21        | 11.35%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 10.81%  |
| Broadcom 58200                                                               | 19        | 10.27%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 7.57%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 13        | 7.03%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 4.32%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.78%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 2.16%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.62%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.08%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 2         | 1.08%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.08%   |
| OmniKey CardMan 1021                                                         | 2         | 1.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.08%   |
| BIT4ID miniLector EVO                                                        | 2         | 1.08%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.08%   |
| Watchdata USB Key                                                            | 1         | 0.54%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.54%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.54%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.54%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.54%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.54%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.54%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.54%   |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.54%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.54%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.54%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.54%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.54%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.54%   |
| Aktiv Rutoken lite                                                           | 1         | 0.54%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2203      | 68.69%  |
| 1     | 809       | 25.23%  |
| 2     | 161       | 5.02%   |
| 3     | 15        | 0.47%   |
| 4     | 8         | 0.25%   |
| 6     | 4         | 0.12%   |
| 7     | 3         | 0.09%   |
| 5     | 3         | 0.09%   |
| 9     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 432       | 35.5%   |
| Graphics card            | 202       | 16.6%   |
| Chipcard                 | 159       | 13.06%  |
| Net/wireless             | 143       | 11.75%  |
| Multimedia controller    | 48        | 3.94%   |
| Camera                   | 45        | 3.7%    |
| Sound                    | 37        | 3.04%   |
| Bluetooth                | 33        | 2.71%   |
| Communication controller | 32        | 2.63%   |
| Unassigned class         | 29        | 2.38%   |
| Card reader              | 16        | 1.31%   |
| Storage                  | 13        | 1.07%   |
| Net/ethernet             | 9         | 0.74%   |
| Network                  | 6         | 0.49%   |
| Storage/ide              | 4         | 0.33%   |
| Modem                    | 4         | 0.33%   |
| Firewire controller      | 3         | 0.25%   |
| Dvb card                 | 2         | 0.16%   |

