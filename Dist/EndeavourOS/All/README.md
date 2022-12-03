EndeavourOS - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/EndeavourOS/Desktop/README.md) and [notebooks](/Dist/EndeavourOS/Notebook/README.md).

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

Total: 976

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | GS75 Stealth 8SG            | Notebook    | [70be467762](https://linux-hardware.org/?probe=70be467762) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| HP            | ENVY 17                     | Notebook    | [4a784f4642](https://linux-hardware.org/?probe=4a784f4642) | Nov 27, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [3ce1a2c42a](https://linux-hardware.org/?probe=3ce1a2c42a) | Nov 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [4e7809f7f6](https://linux-hardware.org/?probe=4e7809f7f6) | Nov 27, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1deadcff69](https://linux-hardware.org/?probe=1deadcff69) | Nov 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d5d04cf0f9](https://linux-hardware.org/?probe=d5d04cf0f9) | Nov 26, 2022 |
| HP            | 18E4                        | Desktop     | [d72a174606](https://linux-hardware.org/?probe=d72a174606) | Nov 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f76927c5ef](https://linux-hardware.org/?probe=f76927c5ef) | Nov 26, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [63521d3e8d](https://linux-hardware.org/?probe=63521d3e8d) | Nov 26, 2022 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [5b19381bf6](https://linux-hardware.org/?probe=5b19381bf6) | Nov 26, 2022 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [1878ce00d7](https://linux-hardware.org/?probe=1878ce00d7) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| Lenovo        | ThinkPad T440s 20ARA12UM... | Notebook    | [5e1b88160e](https://linux-hardware.org/?probe=5e1b88160e) | Nov 25, 2022 |
| HP            | 18E4                        | Desktop     | [4a4ac150b6](https://linux-hardware.org/?probe=4a4ac150b6) | Nov 24, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [2b2778b81a](https://linux-hardware.org/?probe=2b2778b81a) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1986287453](https://linux-hardware.org/?probe=1986287453) | Nov 24, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | 15                          | Notebook    | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| HP            | 18E4                        | Desktop     | [ff954b29c9](https://linux-hardware.org/?probe=ff954b29c9) | Nov 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| MSI           | B360 GAMING PLUS            | Desktop     | [6552f5cfc9](https://linux-hardware.org/?probe=6552f5cfc9) | Nov 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [01810a4098](https://linux-hardware.org/?probe=01810a4098) | Nov 17, 2022 |
| HP            | 18E4                        | Desktop     | [37dd18c268](https://linux-hardware.org/?probe=37dd18c268) | Nov 17, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [8c63644200](https://linux-hardware.org/?probe=8c63644200) | Nov 14, 2022 |
| HP            | 3397                        | Desktop     | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| HP            | 18E4                        | Desktop     | [be545cc91f](https://linux-hardware.org/?probe=be545cc91f) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [7aeba8b69a](https://linux-hardware.org/?probe=7aeba8b69a) | Nov 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | Notebook    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [0527a7a983](https://linux-hardware.org/?probe=0527a7a983) | Nov 07, 2022 |
| Lenovo        | ThinkPad T520 42406AG       | Notebook    | [1038487513](https://linux-hardware.org/?probe=1038487513) | Nov 06, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d137598aff](https://linux-hardware.org/?probe=d137598aff) | Nov 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [31cae1e989](https://linux-hardware.org/?probe=31cae1e989) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| HP            | 18E4                        | Desktop     | [66463ac87d](https://linux-hardware.org/?probe=66463ac87d) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU    | Notebook    | [9e1b981f01](https://linux-hardware.org/?probe=9e1b981f01) | Nov 03, 2022 |
| HP            | 18E4                        | Desktop     | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | Notebook    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| HP            | 18E7                        | Desktop     | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [5e32f7b38b](https://linux-hardware.org/?probe=5e32f7b38b) | Oct 28, 2022 |
| HP            | 18E4                        | Desktop     | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [264d164669](https://linux-hardware.org/?probe=264d164669) | Oct 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7be37b6a2d](https://linux-hardware.org/?probe=7be37b6a2d) | Oct 27, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [7e1a95e569](https://linux-hardware.org/?probe=7e1a95e569) | Oct 26, 2022 |
| Acer          | Extensa 2540                | Notebook    | [367660309f](https://linux-hardware.org/?probe=367660309f) | Oct 26, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3848afd2c8](https://linux-hardware.org/?probe=3848afd2c8) | Oct 26, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [be4e6c1903](https://linux-hardware.org/?probe=be4e6c1903) | Oct 25, 2022 |
| HP            | 650                         | Notebook    | [d7b73bebc7](https://linux-hardware.org/?probe=d7b73bebc7) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3ab5922ddf](https://linux-hardware.org/?probe=3ab5922ddf) | Oct 25, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [95707c7cd5](https://linux-hardware.org/?probe=95707c7cd5) | Oct 25, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [17a0e006d0](https://linux-hardware.org/?probe=17a0e006d0) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [c6966a0df9](https://linux-hardware.org/?probe=c6966a0df9) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [5b4ecfb7e9](https://linux-hardware.org/?probe=5b4ecfb7e9) | Oct 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [0312fb4d88](https://linux-hardware.org/?probe=0312fb4d88) | Oct 21, 2022 |
| HP            | 18E4                        | Desktop     | [dfbdab6987](https://linux-hardware.org/?probe=dfbdab6987) | Oct 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [d6275970a0](https://linux-hardware.org/?probe=d6275970a0) | Oct 21, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [0fd75382e9](https://linux-hardware.org/?probe=0fd75382e9) | Oct 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [facb462239](https://linux-hardware.org/?probe=facb462239) | Oct 20, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c8997eb831](https://linux-hardware.org/?probe=c8997eb831) | Oct 20, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8105425af8](https://linux-hardware.org/?probe=8105425af8) | Oct 20, 2022 |
| MSI           | GE75 Raider 10SF            | Notebook    | [dd4102e2e7](https://linux-hardware.org/?probe=dd4102e2e7) | Oct 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [01338c4f3c](https://linux-hardware.org/?probe=01338c4f3c) | Oct 19, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [d7784759fb](https://linux-hardware.org/?probe=d7784759fb) | Oct 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [5e31cc470c](https://linux-hardware.org/?probe=5e31cc470c) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [28d9942c9f](https://linux-hardware.org/?probe=28d9942c9f) | Oct 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3a6855c328](https://linux-hardware.org/?probe=3a6855c328) | Oct 15, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bf1677e47c](https://linux-hardware.org/?probe=bf1677e47c) | Oct 14, 2022 |
| Google        | Liara                       | Notebook    | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [1927ae6949](https://linux-hardware.org/?probe=1927ae6949) | Oct 12, 2022 |
| Lenovo        | V110-15AST 80TD             | Notebook    | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [261f171b10](https://linux-hardware.org/?probe=261f171b10) | Oct 12, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [95daf6fc30](https://linux-hardware.org/?probe=95daf6fc30) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| HP            | 18E4                        | Desktop     | [6603067eba](https://linux-hardware.org/?probe=6603067eba) | Oct 10, 2022 |
| Acer          | Swift SF314-51              | Notebook    | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [90c1d12ca3](https://linux-hardware.org/?probe=90c1d12ca3) | Oct 07, 2022 |
| Packard Be... | EasyNote TJ65               | Notebook    | [bb815f037b](https://linux-hardware.org/?probe=bb815f037b) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| HP            | 18E4                        | Desktop     | [53c6bf7af4](https://linux-hardware.org/?probe=53c6bf7af4) | Oct 06, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1f77699521](https://linux-hardware.org/?probe=1f77699521) | Oct 03, 2022 |
| iRU           | v1.0                        | Mini pc     | [388d438bbc](https://linux-hardware.org/?probe=388d438bbc) | Oct 03, 2022 |
| HP            | 250 G4                      | Notebook    | [7c892fab7a](https://linux-hardware.org/?probe=7c892fab7a) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1a2e047ca1](https://linux-hardware.org/?probe=1a2e047ca1) | Oct 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [75e1aeaff5](https://linux-hardware.org/?probe=75e1aeaff5) | Oct 02, 2022 |
| Dell          | 0JYH5J A00                  | All in one  | [348bc23246](https://linux-hardware.org/?probe=348bc23246) | Oct 01, 2022 |
| MSI           | GF65 Thin 9SD               | Notebook    | [a761de487d](https://linux-hardware.org/?probe=a761de487d) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1570daf698](https://linux-hardware.org/?probe=1570daf698) | Sep 29, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [f9eecf6781](https://linux-hardware.org/?probe=f9eecf6781) | Sep 28, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [658f9b891f](https://linux-hardware.org/?probe=658f9b891f) | Sep 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | Desktop     | [6e96f4620a](https://linux-hardware.org/?probe=6e96f4620a) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | Desktop     | [acb677ddeb](https://linux-hardware.org/?probe=acb677ddeb) | Sep 25, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [fe99b8a461](https://linux-hardware.org/?probe=fe99b8a461) | Sep 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [164ad85233](https://linux-hardware.org/?probe=164ad85233) | Sep 23, 2022 |
| HP            | 250 G4                      | Notebook    | [5d4c56fe14](https://linux-hardware.org/?probe=5d4c56fe14) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| AZW           | SEi                         | Desktop     | [579b2be420](https://linux-hardware.org/?probe=579b2be420) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [031f4bb4f1](https://linux-hardware.org/?probe=031f4bb4f1) | Sep 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [6f43da7fb4](https://linux-hardware.org/?probe=6f43da7fb4) | Sep 22, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [e6cb381fd2](https://linux-hardware.org/?probe=e6cb381fd2) | Sep 21, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [d0f94bde46](https://linux-hardware.org/?probe=d0f94bde46) | Sep 21, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [7ae4855566](https://linux-hardware.org/?probe=7ae4855566) | Sep 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f4f33e2362](https://linux-hardware.org/?probe=f4f33e2362) | Sep 20, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [e8f0a018c9](https://linux-hardware.org/?probe=e8f0a018c9) | Sep 19, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [579f73fc88](https://linux-hardware.org/?probe=579f73fc88) | Sep 19, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [543fad9f1c](https://linux-hardware.org/?probe=543fad9f1c) | Sep 18, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4f1e683ced](https://linux-hardware.org/?probe=4f1e683ced) | Sep 16, 2022 |
| HP            | 1998                        | Desktop     | [f3ef7a85fe](https://linux-hardware.org/?probe=f3ef7a85fe) | Sep 16, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [465e8d2c86](https://linux-hardware.org/?probe=465e8d2c86) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | Notebook    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| Gigabyte      | AORUS 15G XC                | Notebook    | [4b0e97e947](https://linux-hardware.org/?probe=4b0e97e947) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [39c0297cb1](https://linux-hardware.org/?probe=39c0297cb1) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Timi          | TM1703                      | Notebook    | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [df80ca89ee](https://linux-hardware.org/?probe=df80ca89ee) | Sep 08, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9690933a68](https://linux-hardware.org/?probe=9690933a68) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| Timi          | TM1703                      | Notebook    | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [dd3b771e55](https://linux-hardware.org/?probe=dd3b771e55) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | Notebook    | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [0e4f12b377](https://linux-hardware.org/?probe=0e4f12b377) | Sep 04, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | Notebook    | [2667cd1609](https://linux-hardware.org/?probe=2667cd1609) | Sep 03, 2022 |
| Dell          | 0HMF7C A01                  | Desktop     | [292123f83b](https://linux-hardware.org/?probe=292123f83b) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [05221c6c18](https://linux-hardware.org/?probe=05221c6c18) | Sep 03, 2022 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [2fb52eb1a8](https://linux-hardware.org/?probe=2fb52eb1a8) | Sep 03, 2022 |
| ASUSTek       | X580VN                      | Notebook    | [fe8f1a7e6f](https://linux-hardware.org/?probe=fe8f1a7e6f) | Sep 03, 2022 |
| HP            | OMEN by Laptop 16z-c000     | Notebook    | [edc4a4ce85](https://linux-hardware.org/?probe=edc4a4ce85) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [3a8cfc8781](https://linux-hardware.org/?probe=3a8cfc8781) | Sep 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [297cab0eb2](https://linux-hardware.org/?probe=297cab0eb2) | Sep 01, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [18822e9fbe](https://linux-hardware.org/?probe=18822e9fbe) | Sep 01, 2022 |
| HP            | 18E7                        | Desktop     | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [94b00f5da5](https://linux-hardware.org/?probe=94b00f5da5) | Aug 27, 2022 |
| Google        | Peppy                       | Notebook    | [be4ecba4dc](https://linux-hardware.org/?probe=be4ecba4dc) | Aug 26, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [de2984c01a](https://linux-hardware.org/?probe=de2984c01a) | Aug 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [005afabbff](https://linux-hardware.org/?probe=005afabbff) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9b5ba9f755](https://linux-hardware.org/?probe=9b5ba9f755) | Aug 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [eec78b1552](https://linux-hardware.org/?probe=eec78b1552) | Aug 17, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fb77adfb99](https://linux-hardware.org/?probe=fb77adfb99) | Aug 16, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [2aa966d8af](https://linux-hardware.org/?probe=2aa966d8af) | Aug 14, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [94fb37c745](https://linux-hardware.org/?probe=94fb37c745) | Aug 14, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [94579c3a70](https://linux-hardware.org/?probe=94579c3a70) | Aug 13, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [b391d570ba](https://linux-hardware.org/?probe=b391d570ba) | Aug 12, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [9e297d5dde](https://linux-hardware.org/?probe=9e297d5dde) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [a76e460266](https://linux-hardware.org/?probe=a76e460266) | Aug 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [d76760ffa4](https://linux-hardware.org/?probe=d76760ffa4) | Aug 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c257fb6e7](https://linux-hardware.org/?probe=9c257fb6e7) | Aug 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c5e5976db](https://linux-hardware.org/?probe=9c5e5976db) | Aug 08, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [ddbb081e21](https://linux-hardware.org/?probe=ddbb081e21) | Aug 08, 2022 |
| AZW           | U59                         | Desktop     | [33aea75ff4](https://linux-hardware.org/?probe=33aea75ff4) | Aug 07, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3ef9c93317](https://linux-hardware.org/?probe=3ef9c93317) | Aug 06, 2022 |
| Dell          | 0JYH5J A00                  | All in one  | [7940378ce2](https://linux-hardware.org/?probe=7940378ce2) | Aug 06, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [d1079f3fba](https://linux-hardware.org/?probe=d1079f3fba) | Aug 04, 2022 |
| Positivo      | S14BW01                     | Notebook    | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ec13dcb17f](https://linux-hardware.org/?probe=ec13dcb17f) | Aug 01, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [0bcc9863e3](https://linux-hardware.org/?probe=0bcc9863e3) | Jul 31, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [7a5337e18d](https://linux-hardware.org/?probe=7a5337e18d) | Jul 28, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [b6dea628df](https://linux-hardware.org/?probe=b6dea628df) | Jul 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [60b06048f3](https://linux-hardware.org/?probe=60b06048f3) | Jul 24, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [06dd902359](https://linux-hardware.org/?probe=06dd902359) | Jul 23, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [00f490c5d0](https://linux-hardware.org/?probe=00f490c5d0) | Jul 22, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [b3f65d7c35](https://linux-hardware.org/?probe=b3f65d7c35) | Jul 21, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [d7e2758b93](https://linux-hardware.org/?probe=d7e2758b93) | Jul 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| Samsung       | DeskTop System              | Desktop     | [d0d33ec330](https://linux-hardware.org/?probe=d0d33ec330) | Jul 19, 2022 |
| Samsung       | DeskTop System              | Desktop     | [3af9bcc9cb](https://linux-hardware.org/?probe=3af9bcc9cb) | Jul 19, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [76b994344e](https://linux-hardware.org/?probe=76b994344e) | Jul 19, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [10be1cd329](https://linux-hardware.org/?probe=10be1cd329) | Jul 18, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | Notebook    | [1a394fdf59](https://linux-hardware.org/?probe=1a394fdf59) | Jul 18, 2022 |
| Lenovo        | ThinkPad E595 20NF001HGE    | Notebook    | [9d3a54dbcf](https://linux-hardware.org/?probe=9d3a54dbcf) | Jul 17, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85a02f5d41](https://linux-hardware.org/?probe=85a02f5d41) | Jul 15, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HP            | 158B                        | Desktop     | [1f3ebf7ecf](https://linux-hardware.org/?probe=1f3ebf7ecf) | Jul 07, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [b92830b100](https://linux-hardware.org/?probe=b92830b100) | Jul 03, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [36dcdacdb1](https://linux-hardware.org/?probe=36dcdacdb1) | Jul 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5dd727cd5e](https://linux-hardware.org/?probe=5dd727cd5e) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [9aa0a38b17](https://linux-hardware.org/?probe=9aa0a38b17) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [b9b09609b8](https://linux-hardware.org/?probe=b9b09609b8) | Jul 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [7528e47074](https://linux-hardware.org/?probe=7528e47074) | Jun 24, 2022 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| MSI           | B450 TOMAHAWK               | Notebook    | [b9a8ce148e](https://linux-hardware.org/?probe=b9a8ce148e) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [16d7a07f8f](https://linux-hardware.org/?probe=16d7a07f8f) | Jun 20, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b0cc04798d](https://linux-hardware.org/?probe=b0cc04798d) | Jun 18, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [dc04d6eb1a](https://linux-hardware.org/?probe=dc04d6eb1a) | Jun 18, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [5c9a2e5312](https://linux-hardware.org/?probe=5c9a2e5312) | Jun 16, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [82a66444ec](https://linux-hardware.org/?probe=82a66444ec) | Jun 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| Dell          | Latitude XT                 | Notebook    | [6ca0e5ca92](https://linux-hardware.org/?probe=6ca0e5ca92) | Jun 14, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9275d3d785](https://linux-hardware.org/?probe=9275d3d785) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| MSI           | B450 TOMAHAWK               | Notebook    | [ed5235f3f4](https://linux-hardware.org/?probe=ed5235f3f4) | Jun 09, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| Lenovo        | SKYBAY No DPK               | All in one  | [c27da0faa9](https://linux-hardware.org/?probe=c27da0faa9) | Jun 06, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [343315ec17](https://linux-hardware.org/?probe=343315ec17) | Jun 06, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [5c7a9690cf](https://linux-hardware.org/?probe=5c7a9690cf) | Jun 05, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [cb5ea65a1d](https://linux-hardware.org/?probe=cb5ea65a1d) | Jun 04, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [e75c214872](https://linux-hardware.org/?probe=e75c214872) | Jun 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [eaff4f6db6](https://linux-hardware.org/?probe=eaff4f6db6) | Jun 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [fb18d30478](https://linux-hardware.org/?probe=fb18d30478) | Jun 02, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [e9721391d2](https://linux-hardware.org/?probe=e9721391d2) | Jun 01, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [394d112de5](https://linux-hardware.org/?probe=394d112de5) | May 31, 2022 |
| Dell          | Latitude 5289               | Notebook    | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [462a42a8c9](https://linux-hardware.org/?probe=462a42a8c9) | May 28, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [0075e2d9df](https://linux-hardware.org/?probe=0075e2d9df) | May 28, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [4ef7645f2d](https://linux-hardware.org/?probe=4ef7645f2d) | May 28, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [d17aaf4cc5](https://linux-hardware.org/?probe=d17aaf4cc5) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 81X2          | Convertible | [df65cb7a9e](https://linux-hardware.org/?probe=df65cb7a9e) | May 26, 2022 |
| Sony          | VPCCA17FX                   | Notebook    | [4ced9d5222](https://linux-hardware.org/?probe=4ced9d5222) | May 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [52b94e68a9](https://linux-hardware.org/?probe=52b94e68a9) | May 23, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4495957eae](https://linux-hardware.org/?probe=4495957eae) | May 23, 2022 |
| HP            | 0A08h                       | Desktop     | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| Timi          | A35S                        | Notebook    | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| ASRock        | A320M/ac                    | Desktop     | [78ee9c8853](https://linux-hardware.org/?probe=78ee9c8853) | May 20, 2022 |
| HP            | 3647h                       | Desktop     | [eccb82bec8](https://linux-hardware.org/?probe=eccb82bec8) | May 20, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [0bc568827c](https://linux-hardware.org/?probe=0bc568827c) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [bc731dc190](https://linux-hardware.org/?probe=bc731dc190) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [aa810f6e41](https://linux-hardware.org/?probe=aa810f6e41) | May 18, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [798bcbfce3](https://linux-hardware.org/?probe=798bcbfce3) | May 17, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [c4e15012d5](https://linux-hardware.org/?probe=c4e15012d5) | May 15, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| HP            | Notebook                    | Notebook    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b5145fe094](https://linux-hardware.org/?probe=b5145fe094) | May 08, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [3d921b618b](https://linux-hardware.org/?probe=3d921b618b) | May 07, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [3dbf93ec7f](https://linux-hardware.org/?probe=3dbf93ec7f) | May 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [c08f733706](https://linux-hardware.org/?probe=c08f733706) | May 05, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [7354dedb38](https://linux-hardware.org/?probe=7354dedb38) | May 03, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [bcc65ca336](https://linux-hardware.org/?probe=bcc65ca336) | May 03, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [e40e784775](https://linux-hardware.org/?probe=e40e784775) | May 03, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [1d4a595342](https://linux-hardware.org/?probe=1d4a595342) | May 02, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [b212517217](https://linux-hardware.org/?probe=b212517217) | May 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [79a3d8d3f6](https://linux-hardware.org/?probe=79a3d8d3f6) | May 01, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [06b533396d](https://linux-hardware.org/?probe=06b533396d) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | Notebook    | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [af3efcde26](https://linux-hardware.org/?probe=af3efcde26) | Apr 29, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e45e120b35](https://linux-hardware.org/?probe=e45e120b35) | Apr 29, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [5754b2db0d](https://linux-hardware.org/?probe=5754b2db0d) | Apr 29, 2022 |
| Lenovo        | SKYBAY No DPK               | All in one  | [41f38e1f81](https://linux-hardware.org/?probe=41f38e1f81) | Apr 28, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [4185312ca8](https://linux-hardware.org/?probe=4185312ca8) | Apr 27, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [88248eb2e6](https://linux-hardware.org/?probe=88248eb2e6) | Apr 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a7eeea4f7c](https://linux-hardware.org/?probe=a7eeea4f7c) | Apr 27, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [0199a1bcec](https://linux-hardware.org/?probe=0199a1bcec) | Apr 24, 2022 |
| Dell          | Latitude 7280               | Notebook    | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [3d667e4edf](https://linux-hardware.org/?probe=3d667e4edf) | Apr 21, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [5fdc5a8e7b](https://linux-hardware.org/?probe=5fdc5a8e7b) | Apr 21, 2022 |
| Google        | Celes                       | Notebook    | [a1a2262b88](https://linux-hardware.org/?probe=a1a2262b88) | Apr 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [5a58c1f799](https://linux-hardware.org/?probe=5a58c1f799) | Apr 18, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [583693a1a9](https://linux-hardware.org/?probe=583693a1a9) | Apr 17, 2022 |
| ASUSTek       | Zephyrus M GU502GV_GU502... | Notebook    | [10a97e42a3](https://linux-hardware.org/?probe=10a97e42a3) | Apr 17, 2022 |
| Google        | Candy                       | Notebook    | [77b6731597](https://linux-hardware.org/?probe=77b6731597) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [2b3ac63766](https://linux-hardware.org/?probe=2b3ac63766) | Apr 16, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [a892a2412c](https://linux-hardware.org/?probe=a892a2412c) | Apr 15, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a2947cf99b](https://linux-hardware.org/?probe=a2947cf99b) | Apr 15, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a6c14df869](https://linux-hardware.org/?probe=a6c14df869) | Apr 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [939dbc38d3](https://linux-hardware.org/?probe=939dbc38d3) | Apr 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| Acer          | Swift SF314-57G             | Notebook    | [b9b31b0528](https://linux-hardware.org/?probe=b9b31b0528) | Apr 14, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8ea05feeaf](https://linux-hardware.org/?probe=8ea05feeaf) | Apr 13, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [1a48a9a11d](https://linux-hardware.org/?probe=1a48a9a11d) | Apr 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1ff04268cf](https://linux-hardware.org/?probe=1ff04268cf) | Apr 13, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [d90283da2d](https://linux-hardware.org/?probe=d90283da2d) | Apr 13, 2022 |
| MSI           | Modern 15 A11M              | Notebook    | [c3202f68fc](https://linux-hardware.org/?probe=c3202f68fc) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [32f07398c4](https://linux-hardware.org/?probe=32f07398c4) | Apr 12, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [bbaa6e145b](https://linux-hardware.org/?probe=bbaa6e145b) | Apr 12, 2022 |
| ILLEGEAR      | ROGUE                       | Notebook    | [441caeb4e6](https://linux-hardware.org/?probe=441caeb4e6) | Apr 12, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [13df82ae45](https://linux-hardware.org/?probe=13df82ae45) | Apr 12, 2022 |
| Packard Be... | EasyNote ENTG71BM           | Notebook    | [44520b705b](https://linux-hardware.org/?probe=44520b705b) | Apr 11, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [69f81b5d41](https://linux-hardware.org/?probe=69f81b5d41) | Apr 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [31aefcd602](https://linux-hardware.org/?probe=31aefcd602) | Apr 10, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [64ac971253](https://linux-hardware.org/?probe=64ac971253) | Apr 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [183521cdae](https://linux-hardware.org/?probe=183521cdae) | Apr 07, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [febbb5b9a2](https://linux-hardware.org/?probe=febbb5b9a2) | Apr 06, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [3327822265](https://linux-hardware.org/?probe=3327822265) | Apr 06, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9170392920](https://linux-hardware.org/?probe=9170392920) | Apr 04, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [87acd223c9](https://linux-hardware.org/?probe=87acd223c9) | Apr 04, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [0127833323](https://linux-hardware.org/?probe=0127833323) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [b8d47c54c3](https://linux-hardware.org/?probe=b8d47c54c3) | Apr 03, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [53da5b2d7c](https://linux-hardware.org/?probe=53da5b2d7c) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a69ec475f7](https://linux-hardware.org/?probe=a69ec475f7) | Apr 03, 2022 |
| Samsung       | 930QCA                      | Convertible | [d5991ba91f](https://linux-hardware.org/?probe=d5991ba91f) | Apr 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [376167460b](https://linux-hardware.org/?probe=376167460b) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [58413a83b2](https://linux-hardware.org/?probe=58413a83b2) | Mar 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [d895af2b46](https://linux-hardware.org/?probe=d895af2b46) | Mar 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [ee491ed7f4](https://linux-hardware.org/?probe=ee491ed7f4) | Mar 29, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [f9c192cd71](https://linux-hardware.org/?probe=f9c192cd71) | Mar 29, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4a8c48df20](https://linux-hardware.org/?probe=4a8c48df20) | Mar 28, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [2d57761ba8](https://linux-hardware.org/?probe=2d57761ba8) | Mar 26, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [dc38374e42](https://linux-hardware.org/?probe=dc38374e42) | Mar 26, 2022 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [50bcf21472](https://linux-hardware.org/?probe=50bcf21472) | Mar 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [921004463e](https://linux-hardware.org/?probe=921004463e) | Mar 23, 2022 |
| Samsung       | 950QDB                      | Convertible | [97642a3dca](https://linux-hardware.org/?probe=97642a3dca) | Mar 23, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [3500cd92bf](https://linux-hardware.org/?probe=3500cd92bf) | Mar 19, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [4b3b3cfc11](https://linux-hardware.org/?probe=4b3b3cfc11) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [59bd959d3e](https://linux-hardware.org/?probe=59bd959d3e) | Mar 19, 2022 |
| Acer          | Extensa 2520                | Notebook    | [f070f33060](https://linux-hardware.org/?probe=f070f33060) | Mar 19, 2022 |
| Acer          | Extensa 2520                | Notebook    | [f2003c1f90](https://linux-hardware.org/?probe=f2003c1f90) | Mar 19, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [632814d6a3](https://linux-hardware.org/?probe=632814d6a3) | Mar 18, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [7e64ef177c](https://linux-hardware.org/?probe=7e64ef177c) | Mar 18, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [06a3e2150b](https://linux-hardware.org/?probe=06a3e2150b) | Mar 16, 2022 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [73e48f6dc4](https://linux-hardware.org/?probe=73e48f6dc4) | Mar 16, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [d742a1c2fa](https://linux-hardware.org/?probe=d742a1c2fa) | Mar 16, 2022 |
| Toshiba       | Satellite Pro C50-A-1E6     | Notebook    | [ad8e612da5](https://linux-hardware.org/?probe=ad8e612da5) | Mar 15, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [a0a0ba299e](https://linux-hardware.org/?probe=a0a0ba299e) | Mar 15, 2022 |
| Google        | Akemi                       | Notebook    | [6a52c103e9](https://linux-hardware.org/?probe=6a52c103e9) | Mar 14, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [88296140c2](https://linux-hardware.org/?probe=88296140c2) | Mar 11, 2022 |
| Dell          | Precision M6800             | Notebook    | [239dd5797a](https://linux-hardware.org/?probe=239dd5797a) | Mar 10, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| Unknown       | Unknown                     | Notebook    | [23c7cd9c12](https://linux-hardware.org/?probe=23c7cd9c12) | Mar 09, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [e8f9fb7d24](https://linux-hardware.org/?probe=e8f9fb7d24) | Mar 09, 2022 |
| Acer          | Aspire E5-575               | Notebook    | [bc5e48379d](https://linux-hardware.org/?probe=bc5e48379d) | Mar 07, 2022 |
| Lenovo        | ThinkPad Edge 0578BBA       | Notebook    | [cf314fb57a](https://linux-hardware.org/?probe=cf314fb57a) | Mar 07, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [2d2bd57c8b](https://linux-hardware.org/?probe=2d2bd57c8b) | Mar 06, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d9773ef48d](https://linux-hardware.org/?probe=d9773ef48d) | Mar 06, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [4b2fe6657c](https://linux-hardware.org/?probe=4b2fe6657c) | Mar 04, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [677fa0d0a3](https://linux-hardware.org/?probe=677fa0d0a3) | Mar 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [e81420b85c](https://linux-hardware.org/?probe=e81420b85c) | Mar 01, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [d3cc5d36be](https://linux-hardware.org/?probe=d3cc5d36be) | Feb 27, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [35ad54efc7](https://linux-hardware.org/?probe=35ad54efc7) | Feb 26, 2022 |
| Eluktronic... | Prometheus XVII             | Notebook    | [0797cebf2d](https://linux-hardware.org/?probe=0797cebf2d) | Feb 26, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f4bc34ce43](https://linux-hardware.org/?probe=f4bc34ce43) | Feb 23, 2022 |
| Dell          | Latitude 3420               | Notebook    | [fb586744c3](https://linux-hardware.org/?probe=fb586744c3) | Feb 22, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [655c17b9ff](https://linux-hardware.org/?probe=655c17b9ff) | Feb 20, 2022 |
| Radxa         | ROCK Pi X v1.4              | Notebook    | [dd6d9dc630](https://linux-hardware.org/?probe=dd6d9dc630) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4f87ec9849](https://linux-hardware.org/?probe=4f87ec9849) | Feb 19, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [973e1c8d91](https://linux-hardware.org/?probe=973e1c8d91) | Feb 19, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [90e932e714](https://linux-hardware.org/?probe=90e932e714) | Feb 19, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7ad21cbc90](https://linux-hardware.org/?probe=7ad21cbc90) | Feb 19, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [2bfd36f050](https://linux-hardware.org/?probe=2bfd36f050) | Feb 18, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [c75a02af0d](https://linux-hardware.org/?probe=c75a02af0d) | Feb 18, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d98a594e28](https://linux-hardware.org/?probe=d98a594e28) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | Notebook    | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Eluktronic... | Prometheus XVII             | Notebook    | [36436d1aff](https://linux-hardware.org/?probe=36436d1aff) | Feb 17, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [5c8d71134e](https://linux-hardware.org/?probe=5c8d71134e) | Feb 16, 2022 |
| MSI           | B450 TOMAHAWK               | Notebook    | [63d492d4bb](https://linux-hardware.org/?probe=63d492d4bb) | Feb 16, 2022 |
| ASUSTek       | UX490UA                     | Notebook    | [5e40078555](https://linux-hardware.org/?probe=5e40078555) | Feb 14, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [879969adee](https://linux-hardware.org/?probe=879969adee) | Feb 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2afbdea066](https://linux-hardware.org/?probe=2afbdea066) | Feb 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [f84892675f](https://linux-hardware.org/?probe=f84892675f) | Feb 12, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [dda932e1ae](https://linux-hardware.org/?probe=dda932e1ae) | Feb 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [c79fe1743d](https://linux-hardware.org/?probe=c79fe1743d) | Feb 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a8c18662ff](https://linux-hardware.org/?probe=a8c18662ff) | Feb 10, 2022 |
| Dell          | G3 3500                     | Notebook    | [92ee625013](https://linux-hardware.org/?probe=92ee625013) | Feb 09, 2022 |
| HP            | Pavilion 10 TS              | Notebook    | [1228be8404](https://linux-hardware.org/?probe=1228be8404) | Feb 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c408e51e91](https://linux-hardware.org/?probe=c408e51e91) | Feb 08, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [a39c608f4c](https://linux-hardware.org/?probe=a39c608f4c) | Feb 07, 2022 |
| Dell          | Latitude E4310              | Notebook    | [ef92697af7](https://linux-hardware.org/?probe=ef92697af7) | Feb 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [919eb44cc5](https://linux-hardware.org/?probe=919eb44cc5) | Feb 07, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [9bbd70f06c](https://linux-hardware.org/?probe=9bbd70f06c) | Feb 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [28bb1241de](https://linux-hardware.org/?probe=28bb1241de) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [64e32a1354](https://linux-hardware.org/?probe=64e32a1354) | Feb 02, 2022 |
| Notebook      | NH5x_7xDPx                  | Notebook    | [a43204a8d7](https://linux-hardware.org/?probe=a43204a8d7) | Feb 02, 2022 |
| HP            | 1905                        | Desktop     | [8014fae46e](https://linux-hardware.org/?probe=8014fae46e) | Feb 02, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4998bf6630](https://linux-hardware.org/?probe=4998bf6630) | Feb 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [c2b7d7cdd1](https://linux-hardware.org/?probe=c2b7d7cdd1) | Feb 02, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [3deec16346](https://linux-hardware.org/?probe=3deec16346) | Feb 02, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [ee91c21eb4](https://linux-hardware.org/?probe=ee91c21eb4) | Feb 01, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b8f0614b9c](https://linux-hardware.org/?probe=b8f0614b9c) | Feb 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [be25fc4f46](https://linux-hardware.org/?probe=be25fc4f46) | Feb 01, 2022 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [de0d67e8c4](https://linux-hardware.org/?probe=de0d67e8c4) | Jan 31, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8c455b3274](https://linux-hardware.org/?probe=8c455b3274) | Jan 30, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [ecb2fdb4a3](https://linux-hardware.org/?probe=ecb2fdb4a3) | Jan 29, 2022 |
| MSI           | B75MA-P45                   | Desktop     | [4108d2071b](https://linux-hardware.org/?probe=4108d2071b) | Jan 28, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [670589ec65](https://linux-hardware.org/?probe=670589ec65) | Jan 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5c5ac9fe1d](https://linux-hardware.org/?probe=5c5ac9fe1d) | Jan 26, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [317ebaa644](https://linux-hardware.org/?probe=317ebaa644) | Jan 26, 2022 |
| ASRock        | A320M-HD                    | Desktop     | [215b5c3802](https://linux-hardware.org/?probe=215b5c3802) | Jan 23, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [1dfd5b5461](https://linux-hardware.org/?probe=1dfd5b5461) | Jan 23, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [cc0c86531b](https://linux-hardware.org/?probe=cc0c86531b) | Jan 22, 2022 |
| MSI           | B150M ECO                   | Desktop     | [d484e899ef](https://linux-hardware.org/?probe=d484e899ef) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [56e21b8bd6](https://linux-hardware.org/?probe=56e21b8bd6) | Jan 22, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [6586f2d78f](https://linux-hardware.org/?probe=6586f2d78f) | Jan 22, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [a8cf42152e](https://linux-hardware.org/?probe=a8cf42152e) | Jan 21, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [3b7c230363](https://linux-hardware.org/?probe=3b7c230363) | Jan 21, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [b09195fb3c](https://linux-hardware.org/?probe=b09195fb3c) | Jan 20, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [211aac7b59](https://linux-hardware.org/?probe=211aac7b59) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | Notebook    | [206ce8c174](https://linux-hardware.org/?probe=206ce8c174) | Jan 18, 2022 |
| ASUSTek       | K45VD                       | Notebook    | [6eafcfd89d](https://linux-hardware.org/?probe=6eafcfd89d) | Jan 18, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [57e7500f2a](https://linux-hardware.org/?probe=57e7500f2a) | Jan 17, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Acer          | Swift SF514-54T             | Notebook    | [dffa1b1708](https://linux-hardware.org/?probe=dffa1b1708) | Jan 14, 2022 |
| Acer          | Swift SF514-54T             | Notebook    | [cf529c7ad0](https://linux-hardware.org/?probe=cf529c7ad0) | Jan 14, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [e1f153a5e6](https://linux-hardware.org/?probe=e1f153a5e6) | Jan 14, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [5ca44fe54c](https://linux-hardware.org/?probe=5ca44fe54c) | Jan 10, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [0462560ab2](https://linux-hardware.org/?probe=0462560ab2) | Jan 10, 2022 |
| ASRock        | FM2A88X Pro3+               | Desktop     | [1cc054ed3f](https://linux-hardware.org/?probe=1cc054ed3f) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [568c503df0](https://linux-hardware.org/?probe=568c503df0) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb627691ce](https://linux-hardware.org/?probe=fb627691ce) | Jan 07, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [2542ffac8a](https://linux-hardware.org/?probe=2542ffac8a) | Jan 06, 2022 |
| Lenovo        | ThinkPad X240 20AMA2F8MS    | Notebook    | [7b5c7a047a](https://linux-hardware.org/?probe=7b5c7a047a) | Jan 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c22ba841f6](https://linux-hardware.org/?probe=c22ba841f6) | Jan 06, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [2e5c796311](https://linux-hardware.org/?probe=2e5c796311) | Jan 06, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [be76fa91bc](https://linux-hardware.org/?probe=be76fa91bc) | Jan 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [8e11cb731a](https://linux-hardware.org/?probe=8e11cb731a) | Jan 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [b58f7257b9](https://linux-hardware.org/?probe=b58f7257b9) | Jan 05, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [be129c3a7a](https://linux-hardware.org/?probe=be129c3a7a) | Jan 05, 2022 |
| Lenovo        | ThinkPad T560 20FJS4FV00    | Notebook    | [4bd9bb5f20](https://linux-hardware.org/?probe=4bd9bb5f20) | Jan 05, 2022 |
| MSI           | GP66 Leopard 10UH           | Notebook    | [e9689e292c](https://linux-hardware.org/?probe=e9689e292c) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [aa4f09754b](https://linux-hardware.org/?probe=aa4f09754b) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [411cf580b4](https://linux-hardware.org/?probe=411cf580b4) | Jan 04, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [5ce6cac5cb](https://linux-hardware.org/?probe=5ce6cac5cb) | Jan 04, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [608af1b572](https://linux-hardware.org/?probe=608af1b572) | Jan 04, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c804b37a93](https://linux-hardware.org/?probe=c804b37a93) | Jan 04, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [c10faa4e15](https://linux-hardware.org/?probe=c10faa4e15) | Jan 04, 2022 |
| ASUSTek       | N43SL                       | Notebook    | [8468a0ab83](https://linux-hardware.org/?probe=8468a0ab83) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [9b8e2862e0](https://linux-hardware.org/?probe=9b8e2862e0) | Jan 04, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [ab40f6782f](https://linux-hardware.org/?probe=ab40f6782f) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [d770cc3fe5](https://linux-hardware.org/?probe=d770cc3fe5) | Jan 04, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [56db8627d8](https://linux-hardware.org/?probe=56db8627d8) | Jan 04, 2022 |
| Positivo      | POS-PIH81DI                 | Desktop     | [c2f06752f5](https://linux-hardware.org/?probe=c2f06752f5) | Jan 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5ce8d98461](https://linux-hardware.org/?probe=5ce8d98461) | Jan 04, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [4020ca9754](https://linux-hardware.org/?probe=4020ca9754) | Jan 04, 2022 |
| Timi          | A35S                        | Notebook    | [2dafd53d09](https://linux-hardware.org/?probe=2dafd53d09) | Jan 04, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [12ce36d52f](https://linux-hardware.org/?probe=12ce36d52f) | Jan 03, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [2edffdea76](https://linux-hardware.org/?probe=2edffdea76) | Jan 03, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [1ebd581629](https://linux-hardware.org/?probe=1ebd581629) | Jan 01, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [a611e12778](https://linux-hardware.org/?probe=a611e12778) | Dec 31, 2021 |
| Dell          | Precision 5560              | Notebook    | [04cb5954e9](https://linux-hardware.org/?probe=04cb5954e9) | Dec 31, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [89d144f949](https://linux-hardware.org/?probe=89d144f949) | Dec 31, 2021 |
| ASRock        | B450 Steel Legend           | Desktop     | [9a67c15230](https://linux-hardware.org/?probe=9a67c15230) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [211b09522f](https://linux-hardware.org/?probe=211b09522f) | Dec 31, 2021 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [e4d3f29412](https://linux-hardware.org/?probe=e4d3f29412) | Dec 30, 2021 |
| MSI           | B450 TOMAHAWK               | Notebook    | [c85d7c78e7](https://linux-hardware.org/?probe=c85d7c78e7) | Dec 28, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [b608797946](https://linux-hardware.org/?probe=b608797946) | Dec 28, 2021 |
| LattePanda    | Alpha                       | Desktop     | [497e370fc3](https://linux-hardware.org/?probe=497e370fc3) | Dec 26, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [abb80ccd85](https://linux-hardware.org/?probe=abb80ccd85) | Dec 25, 2021 |
| LattePanda    | Alpha                       | Desktop     | [442f08d351](https://linux-hardware.org/?probe=442f08d351) | Dec 24, 2021 |
| Gigabyte      | M68M-S2P                    | Desktop     | [c06c8838d2](https://linux-hardware.org/?probe=c06c8838d2) | Dec 24, 2021 |
| Lenovo        | SKYBAY SDK0J40709 WIN 32... | All in one  | [a4a8130a06](https://linux-hardware.org/?probe=a4a8130a06) | Dec 24, 2021 |
| Acer          | Aspire XC-1660G V:1.1       | Desktop     | [c460e492aa](https://linux-hardware.org/?probe=c460e492aa) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [756df875af](https://linux-hardware.org/?probe=756df875af) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [cd01eec1a8](https://linux-hardware.org/?probe=cd01eec1a8) | Dec 23, 2021 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [4d153ddb81](https://linux-hardware.org/?probe=4d153ddb81) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [deb1a17957](https://linux-hardware.org/?probe=deb1a17957) | Dec 23, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [ca89ed6eab](https://linux-hardware.org/?probe=ca89ed6eab) | Dec 23, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [17067982ca](https://linux-hardware.org/?probe=17067982ca) | Dec 23, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [384617e5a7](https://linux-hardware.org/?probe=384617e5a7) | Dec 22, 2021 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [8c9fc05c39](https://linux-hardware.org/?probe=8c9fc05c39) | Dec 22, 2021 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [aa7388fdd1](https://linux-hardware.org/?probe=aa7388fdd1) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [a1b24f9ab7](https://linux-hardware.org/?probe=a1b24f9ab7) | Dec 21, 2021 |
| Unknown       | Unknown                     | Notebook    | [0fb793d2a7](https://linux-hardware.org/?probe=0fb793d2a7) | Dec 21, 2021 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [f51d57d3bc](https://linux-hardware.org/?probe=f51d57d3bc) | Dec 21, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [7a6594a954](https://linux-hardware.org/?probe=7a6594a954) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [ac70723f1b](https://linux-hardware.org/?probe=ac70723f1b) | Dec 18, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| MSI           | Modern 14 B5M               | Notebook    | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Unknown       | Intel X79                   | Desktop     | [767fb84ac9](https://linux-hardware.org/?probe=767fb84ac9) | Dec 17, 2021 |
| Dell          | 0HD5W2 A01                  | Desktop     | [72329a4b56](https://linux-hardware.org/?probe=72329a4b56) | Dec 17, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0LU0... | Notebook    | [ab6c683160](https://linux-hardware.org/?probe=ab6c683160) | Dec 16, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [16daa16444](https://linux-hardware.org/?probe=16daa16444) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [bc313ce031](https://linux-hardware.org/?probe=bc313ce031) | Dec 15, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [8c9d779e45](https://linux-hardware.org/?probe=8c9d779e45) | Dec 14, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a34aa5357b](https://linux-hardware.org/?probe=a34aa5357b) | Dec 14, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [93957ddac1](https://linux-hardware.org/?probe=93957ddac1) | Dec 13, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [6d5612f136](https://linux-hardware.org/?probe=6d5612f136) | Dec 13, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [641af2bfa6](https://linux-hardware.org/?probe=641af2bfa6) | Dec 13, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [bdfec258d5](https://linux-hardware.org/?probe=bdfec258d5) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fce8b9430](https://linux-hardware.org/?probe=9fce8b9430) | Dec 12, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d1e767dfde](https://linux-hardware.org/?probe=d1e767dfde) | Dec 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [96e7ac029b](https://linux-hardware.org/?probe=96e7ac029b) | Dec 10, 2021 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [939be3ba51](https://linux-hardware.org/?probe=939be3ba51) | Dec 10, 2021 |
| MSI           | Prestige 15 A10SC           | Notebook    | [706fc926ca](https://linux-hardware.org/?probe=706fc926ca) | Dec 08, 2021 |
| Dell          | Latitude 7480               | Notebook    | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [2070780ca9](https://linux-hardware.org/?probe=2070780ca9) | Dec 07, 2021 |
| Framework     | Laptop                      | Notebook    | [c1a31372f4](https://linux-hardware.org/?probe=c1a31372f4) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [41dec8d290](https://linux-hardware.org/?probe=41dec8d290) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [b49088935d](https://linux-hardware.org/?probe=b49088935d) | Dec 04, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [7cdf0f8f44](https://linux-hardware.org/?probe=7cdf0f8f44) | Dec 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [78c796c1fc](https://linux-hardware.org/?probe=78c796c1fc) | Dec 02, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | Bravo 15 B5DD               | Notebook    | [fc7c1ff3c8](https://linux-hardware.org/?probe=fc7c1ff3c8) | Nov 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [b862ee20d9](https://linux-hardware.org/?probe=b862ee20d9) | Nov 24, 2021 |
| Unknown       | Unknown                     | Notebook    | [0555569b70](https://linux-hardware.org/?probe=0555569b70) | Nov 24, 2021 |
| MSI           | B350 PC MATE                | Desktop     | [7fbe80215d](https://linux-hardware.org/?probe=7fbe80215d) | Nov 24, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [2b67e46016](https://linux-hardware.org/?probe=2b67e46016) | Nov 24, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [d0d56860bb](https://linux-hardware.org/?probe=d0d56860bb) | Nov 24, 2021 |
| MSI           | GS63VR 6RF                  | Notebook    | [2d9061c72e](https://linux-hardware.org/?probe=2d9061c72e) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [85338e8b09](https://linux-hardware.org/?probe=85338e8b09) | Nov 23, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [df651ff7ad](https://linux-hardware.org/?probe=df651ff7ad) | Nov 23, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [e6eb602b05](https://linux-hardware.org/?probe=e6eb602b05) | Nov 22, 2021 |
| HP            | 15 TS                       | Notebook    | [50a260e4dc](https://linux-hardware.org/?probe=50a260e4dc) | Nov 21, 2021 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [a3d3e0eecd](https://linux-hardware.org/?probe=a3d3e0eecd) | Nov 20, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [89ea080ce0](https://linux-hardware.org/?probe=89ea080ce0) | Nov 20, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [ec54ffae7a](https://linux-hardware.org/?probe=ec54ffae7a) | Nov 18, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [505925412f](https://linux-hardware.org/?probe=505925412f) | Nov 18, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [778d32ce4b](https://linux-hardware.org/?probe=778d32ce4b) | Nov 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [9fc3f12603](https://linux-hardware.org/?probe=9fc3f12603) | Nov 16, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [be03431631](https://linux-hardware.org/?probe=be03431631) | Nov 15, 2021 |
| HUAWEI        | HN-WX9X                     | Notebook    | [22c7f120ab](https://linux-hardware.org/?probe=22c7f120ab) | Nov 13, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [7ebeace900](https://linux-hardware.org/?probe=7ebeace900) | Nov 13, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [dfe40a023a](https://linux-hardware.org/?probe=dfe40a023a) | Nov 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [1336c9e31c](https://linux-hardware.org/?probe=1336c9e31c) | Nov 12, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [1cfd4ee9f9](https://linux-hardware.org/?probe=1cfd4ee9f9) | Nov 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [c11672a55e](https://linux-hardware.org/?probe=c11672a55e) | Nov 11, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [c9e5138184](https://linux-hardware.org/?probe=c9e5138184) | Nov 07, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [22ce2703b9](https://linux-hardware.org/?probe=22ce2703b9) | Nov 07, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [5d0bad7c15](https://linux-hardware.org/?probe=5d0bad7c15) | Nov 06, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [e95d2fa980](https://linux-hardware.org/?probe=e95d2fa980) | Nov 05, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [85dff2829f](https://linux-hardware.org/?probe=85dff2829f) | Nov 03, 2021 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f57c7bbe97](https://linux-hardware.org/?probe=f57c7bbe97) | Nov 03, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [222ce004da](https://linux-hardware.org/?probe=222ce004da) | Nov 01, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [ca3c48f689](https://linux-hardware.org/?probe=ca3c48f689) | Oct 30, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [79e6ef3655](https://linux-hardware.org/?probe=79e6ef3655) | Oct 29, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [6db3b9d661](https://linux-hardware.org/?probe=6db3b9d661) | Oct 29, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [3fcea4d382](https://linux-hardware.org/?probe=3fcea4d382) | Oct 29, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [cce67d37aa](https://linux-hardware.org/?probe=cce67d37aa) | Oct 28, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [689f9368f1](https://linux-hardware.org/?probe=689f9368f1) | Oct 23, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [7b3cdda6e2](https://linux-hardware.org/?probe=7b3cdda6e2) | Oct 20, 2021 |
| HP            | ENVY 6                      | Notebook    | [94471889b0](https://linux-hardware.org/?probe=94471889b0) | Oct 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [ff566c77ce](https://linux-hardware.org/?probe=ff566c77ce) | Oct 17, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [2d3f367fa7](https://linux-hardware.org/?probe=2d3f367fa7) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [6e745a1ec9](https://linux-hardware.org/?probe=6e745a1ec9) | Oct 17, 2021 |
| Dell          | Latitude E6410              | Notebook    | [68d7531397](https://linux-hardware.org/?probe=68d7531397) | Oct 17, 2021 |
| Apple         | MacBookPro16,2              | Notebook    | [8d0e93e90f](https://linux-hardware.org/?probe=8d0e93e90f) | Oct 16, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [cb03c494cb](https://linux-hardware.org/?probe=cb03c494cb) | Oct 15, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [87ab64b604](https://linux-hardware.org/?probe=87ab64b604) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [cef9098008](https://linux-hardware.org/?probe=cef9098008) | Oct 14, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [718bd26737](https://linux-hardware.org/?probe=718bd26737) | Oct 14, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| Dell          | Precision M4400             | Notebook    | [bae8becab1](https://linux-hardware.org/?probe=bae8becab1) | Oct 11, 2021 |
| Google        | Kindred                     | Notebook    | [9420945432](https://linux-hardware.org/?probe=9420945432) | Oct 10, 2021 |
| Dell          | Latitude E4300              | Notebook    | [c486155f48](https://linux-hardware.org/?probe=c486155f48) | Oct 10, 2021 |
| Dell          | Latitude E4300              | Notebook    | [52e0d626fa](https://linux-hardware.org/?probe=52e0d626fa) | Oct 10, 2021 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [7f47afdf06](https://linux-hardware.org/?probe=7f47afdf06) | Oct 10, 2021 |
| UMAX          | J42 Nano                    | Desktop     | [fd40a94769](https://linux-hardware.org/?probe=fd40a94769) | Oct 09, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [cc7d0245a7](https://linux-hardware.org/?probe=cc7d0245a7) | Oct 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [ebfe78c927](https://linux-hardware.org/?probe=ebfe78c927) | Oct 08, 2021 |
| Dell          | G3 3500                     | Notebook    | [b4e985bcba](https://linux-hardware.org/?probe=b4e985bcba) | Oct 08, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [849ca2da3d](https://linux-hardware.org/?probe=849ca2da3d) | Oct 06, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0923a8b728](https://linux-hardware.org/?probe=0923a8b728) | Oct 05, 2021 |
| Dell          | Precision M4400             | Notebook    | [ab43bad624](https://linux-hardware.org/?probe=ab43bad624) | Oct 04, 2021 |
| Gigabyte      | B550 VISION D               | Desktop     | [e8a2ba9952](https://linux-hardware.org/?probe=e8a2ba9952) | Oct 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9c8bc954a7](https://linux-hardware.org/?probe=9c8bc954a7) | Oct 02, 2021 |
| MSI           | G41M-P33 Combo              | Desktop     | [ec8e63e96e](https://linux-hardware.org/?probe=ec8e63e96e) | Oct 01, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [dc91b564a8](https://linux-hardware.org/?probe=dc91b564a8) | Sep 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [86c4b5769f](https://linux-hardware.org/?probe=86c4b5769f) | Sep 28, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [263233be76](https://linux-hardware.org/?probe=263233be76) | Sep 28, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2a6a76f702](https://linux-hardware.org/?probe=2a6a76f702) | Sep 26, 2021 |
| Lenovo        | ThinkPad T480 20L6S3S500    | Notebook    | [067f3cf110](https://linux-hardware.org/?probe=067f3cf110) | Sep 26, 2021 |
| Lenovo        | ThinkPad T470 20HES2SF00    | Notebook    | [9cf10e22a6](https://linux-hardware.org/?probe=9cf10e22a6) | Sep 25, 2021 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a20f426eed](https://linux-hardware.org/?probe=a20f426eed) | Sep 25, 2021 |
| Lenovo        | ThinkPad E460 20ET004LGE    | Notebook    | [b64e2c4a07](https://linux-hardware.org/?probe=b64e2c4a07) | Sep 25, 2021 |
| Microsoft     | Surface Pro 6               | Tablet      | [c11a70be9e](https://linux-hardware.org/?probe=c11a70be9e) | Sep 24, 2021 |
| Dell          | Precision 3560              | Notebook    | [d9b527db16](https://linux-hardware.org/?probe=d9b527db16) | Sep 22, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1e1e40ce8b](https://linux-hardware.org/?probe=1e1e40ce8b) | Sep 22, 2021 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [711e2e3960](https://linux-hardware.org/?probe=711e2e3960) | Sep 22, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [35cbc8e5b5](https://linux-hardware.org/?probe=35cbc8e5b5) | Sep 19, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [860fb3dc8c](https://linux-hardware.org/?probe=860fb3dc8c) | Sep 19, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [8ffa4dd273](https://linux-hardware.org/?probe=8ffa4dd273) | Sep 18, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [3a7231ce53](https://linux-hardware.org/?probe=3a7231ce53) | Sep 17, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [60555ce93d](https://linux-hardware.org/?probe=60555ce93d) | Sep 16, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [8dfad66767](https://linux-hardware.org/?probe=8dfad66767) | Sep 16, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [3e845646c9](https://linux-hardware.org/?probe=3e845646c9) | Sep 15, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | Notebook    | [0fe0fa66d6](https://linux-hardware.org/?probe=0fe0fa66d6) | Sep 14, 2021 |
| Dynabook      | Satellite Pro C50-E-109     | Notebook    | [d5e170957e](https://linux-hardware.org/?probe=d5e170957e) | Sep 14, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [8f215120c2](https://linux-hardware.org/?probe=8f215120c2) | Sep 13, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [33cee010e8](https://linux-hardware.org/?probe=33cee010e8) | Sep 12, 2021 |
| Dell          | 0JYH5J A00                  | All in one  | [f05e2951a1](https://linux-hardware.org/?probe=f05e2951a1) | Sep 11, 2021 |
| HP            | 8430 1000                   | All in one  | [56c6d48f6e](https://linux-hardware.org/?probe=56c6d48f6e) | Sep 11, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [c06b4b30a0](https://linux-hardware.org/?probe=c06b4b30a0) | Sep 10, 2021 |
| AMI           | Intel                       | Notebook    | [49dd022241](https://linux-hardware.org/?probe=49dd022241) | Sep 10, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [0c83ae1e11](https://linux-hardware.org/?probe=0c83ae1e11) | Sep 10, 2021 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [167df4c15e](https://linux-hardware.org/?probe=167df4c15e) | Sep 09, 2021 |
| Dell          | Latitude E4310              | Notebook    | [34c3815468](https://linux-hardware.org/?probe=34c3815468) | Sep 02, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [12cf057e04](https://linux-hardware.org/?probe=12cf057e04) | Sep 02, 2021 |
| TrekStor      | Primebook P14               | Notebook    | [026e7277ee](https://linux-hardware.org/?probe=026e7277ee) | Sep 02, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| Dell          | Precision M4400             | Notebook    | [289a2606bd](https://linux-hardware.org/?probe=289a2606bd) | Sep 02, 2021 |
| Intel         | DH55HC AAE70933-504         | Desktop     | [2880661f42](https://linux-hardware.org/?probe=2880661f42) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [581b1be43c](https://linux-hardware.org/?probe=581b1be43c) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3ab28e58e](https://linux-hardware.org/?probe=d3ab28e58e) | Aug 30, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [24a34a526e](https://linux-hardware.org/?probe=24a34a526e) | Aug 28, 2021 |
| Lenovo        | IdeaPad 510S-14IKB 80UV     | Notebook    | [146390e85e](https://linux-hardware.org/?probe=146390e85e) | Aug 25, 2021 |
| ASUSTek       | G752VT                      | Notebook    | [23dea85a93](https://linux-hardware.org/?probe=23dea85a93) | Aug 24, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [1c75e967eb](https://linux-hardware.org/?probe=1c75e967eb) | Aug 24, 2021 |
| HP            | 8906 SMVB                   | Desktop     | [ea16eee1c7](https://linux-hardware.org/?probe=ea16eee1c7) | Aug 24, 2021 |
| Dell          | Latitude E7440              | Notebook    | [0de5415ad7](https://linux-hardware.org/?probe=0de5415ad7) | Aug 22, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [4c8282bb42](https://linux-hardware.org/?probe=4c8282bb42) | Aug 16, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [2e16baa112](https://linux-hardware.org/?probe=2e16baa112) | Aug 14, 2021 |
| Dell          | Inspiron 5577               | Notebook    | [ae8d8171a7](https://linux-hardware.org/?probe=ae8d8171a7) | Aug 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [71645376f3](https://linux-hardware.org/?probe=71645376f3) | Aug 13, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [5d560f16cc](https://linux-hardware.org/?probe=5d560f16cc) | Aug 12, 2021 |
| Lenovo        | IdeaPad 320-15IKB Touch ... | Notebook    | [9be95b3419](https://linux-hardware.org/?probe=9be95b3419) | Aug 12, 2021 |
| HP            | EliteBook 745 G6            | Notebook    | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9adf19d9c0](https://linux-hardware.org/?probe=9adf19d9c0) | Aug 10, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | Notebook    | [52118232ff](https://linux-hardware.org/?probe=52118232ff) | Aug 10, 2021 |
| Gigabyte      | P35-DS3R                    | Desktop     | [421cd7ce36](https://linux-hardware.org/?probe=421cd7ce36) | Aug 09, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [8e9d51a941](https://linux-hardware.org/?probe=8e9d51a941) | Aug 07, 2021 |
| Dell          | 0K240Y A01                  | Desktop     | [5cc92cb5ac](https://linux-hardware.org/?probe=5cc92cb5ac) | Aug 04, 2021 |
| Notebook      | W65_67SZ                    | Notebook    | [ddd6f26db4](https://linux-hardware.org/?probe=ddd6f26db4) | Aug 03, 2021 |
| ASUSTek       | PN50                        | Mini pc     | [1af0342def](https://linux-hardware.org/?probe=1af0342def) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1ccf2e3d28](https://linux-hardware.org/?probe=1ccf2e3d28) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [b5b8bac74a](https://linux-hardware.org/?probe=b5b8bac74a) | Jul 26, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [12d6be24d7](https://linux-hardware.org/?probe=12d6be24d7) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [816edfa4bb](https://linux-hardware.org/?probe=816edfa4bb) | Jul 25, 2021 |
| Acer          | Aspire C27-962              | All in one  | [75e1d7295c](https://linux-hardware.org/?probe=75e1d7295c) | Jul 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [a5959b657f](https://linux-hardware.org/?probe=a5959b657f) | Jul 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [f8f9bf0717](https://linux-hardware.org/?probe=f8f9bf0717) | Jul 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [7cdf389d4c](https://linux-hardware.org/?probe=7cdf389d4c) | Jul 22, 2021 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | Notebook    | [4421b175f7](https://linux-hardware.org/?probe=4421b175f7) | Jul 16, 2021 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [8d7689bceb](https://linux-hardware.org/?probe=8d7689bceb) | Jul 14, 2021 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [404eae69f4](https://linux-hardware.org/?probe=404eae69f4) | Jul 14, 2021 |
| Acer          | Predator G9-792             | Notebook    | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [f36328f6b3](https://linux-hardware.org/?probe=f36328f6b3) | Jul 12, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [c79cfacd5e](https://linux-hardware.org/?probe=c79cfacd5e) | Jul 05, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [282a2e2926](https://linux-hardware.org/?probe=282a2e2926) | Jul 04, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [14b3d46ef8](https://linux-hardware.org/?probe=14b3d46ef8) | Jul 03, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [62f256e36e](https://linux-hardware.org/?probe=62f256e36e) | Jul 03, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [3be93cbc0c](https://linux-hardware.org/?probe=3be93cbc0c) | Jul 03, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [fd48c4cd51](https://linux-hardware.org/?probe=fd48c4cd51) | Jul 02, 2021 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [487ca6235b](https://linux-hardware.org/?probe=487ca6235b) | Jul 02, 2021 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [181cfa9437](https://linux-hardware.org/?probe=181cfa9437) | Jul 01, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [a92028f13a](https://linux-hardware.org/?probe=a92028f13a) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | Notebook    | [56a361debf](https://linux-hardware.org/?probe=56a361debf) | Jul 01, 2021 |
| Lenovo        | ThinkPad T450s 20BW0007U... | Notebook    | [431df4bc98](https://linux-hardware.org/?probe=431df4bc98) | Jul 01, 2021 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [625c876e08](https://linux-hardware.org/?probe=625c876e08) | Jun 30, 2021 |
| Dell          | G7 7588                     | Notebook    | [259694c4a1](https://linux-hardware.org/?probe=259694c4a1) | Jun 27, 2021 |
| Pine Micro... | Pine64 Pinebook Pro         | Notebook    | [d2f1ec957f](https://linux-hardware.org/?probe=d2f1ec957f) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [4b70691f2e](https://linux-hardware.org/?probe=4b70691f2e) | Jun 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [397e22935b](https://linux-hardware.org/?probe=397e22935b) | Jun 25, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [10c5bbf0f8](https://linux-hardware.org/?probe=10c5bbf0f8) | Jun 18, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2762be36c4](https://linux-hardware.org/?probe=2762be36c4) | Jun 14, 2021 |
| ASUSTek       | F1A55-M LX                  | Desktop     | [9e7c39435d](https://linux-hardware.org/?probe=9e7c39435d) | Jun 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [48bda0fbd3](https://linux-hardware.org/?probe=48bda0fbd3) | Jun 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ed31182c51](https://linux-hardware.org/?probe=ed31182c51) | Jun 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [117372a8ff](https://linux-hardware.org/?probe=117372a8ff) | Jun 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [6b6205bc5d](https://linux-hardware.org/?probe=6b6205bc5d) | May 31, 2021 |
| HP            | EliteBook Revolve 810       | Notebook    | [24758ed5b3](https://linux-hardware.org/?probe=24758ed5b3) | May 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cad013a6a5](https://linux-hardware.org/?probe=cad013a6a5) | May 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | Notebook    | [4c600416f9](https://linux-hardware.org/?probe=4c600416f9) | May 28, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [b86bb4b6c9](https://linux-hardware.org/?probe=b86bb4b6c9) | May 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [99ab618bee](https://linux-hardware.org/?probe=99ab618bee) | May 25, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | Notebook    | [684dfb967f](https://linux-hardware.org/?probe=684dfb967f) | May 22, 2021 |
| Schenker      | XMG NEO 15(E20, RTX 20xx... | Notebook    | [c18360d17e](https://linux-hardware.org/?probe=c18360d17e) | May 22, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c1b869c13a](https://linux-hardware.org/?probe=c1b869c13a) | May 22, 2021 |
| Acer          | Swift SF314-51              | Notebook    | [a666be1df5](https://linux-hardware.org/?probe=a666be1df5) | May 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [457597b9d1](https://linux-hardware.org/?probe=457597b9d1) | May 21, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [e18030e5f0](https://linux-hardware.org/?probe=e18030e5f0) | May 20, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [7e5dbc86b9](https://linux-hardware.org/?probe=7e5dbc86b9) | May 20, 2021 |
| Dell          | Inspiron 7386               | Convertible | [42442e4d61](https://linux-hardware.org/?probe=42442e4d61) | May 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [14b3851754](https://linux-hardware.org/?probe=14b3851754) | May 20, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [585db3001d](https://linux-hardware.org/?probe=585db3001d) | May 19, 2021 |
| Notebook      | NS50MU                      | Notebook    | [8e08645823](https://linux-hardware.org/?probe=8e08645823) | May 19, 2021 |
| Lenovo        | ThinkPad P51 20HHCT01WW     | Notebook    | [3f42eaf28b](https://linux-hardware.org/?probe=3f42eaf28b) | May 19, 2021 |
| HP            | 2B36                        | Desktop     | [62135f1e45](https://linux-hardware.org/?probe=62135f1e45) | May 19, 2021 |
| MSI           | GE72 6QD                    | Notebook    | [7637f1ad9c](https://linux-hardware.org/?probe=7637f1ad9c) | May 19, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fec75a202e](https://linux-hardware.org/?probe=fec75a202e) | May 19, 2021 |
| Dell          | Inspiron 7386               | Convertible | [c6f4d6de84](https://linux-hardware.org/?probe=c6f4d6de84) | May 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [634c63d316](https://linux-hardware.org/?probe=634c63d316) | May 15, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [17af51e9b1](https://linux-hardware.org/?probe=17af51e9b1) | May 14, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9048b606d2](https://linux-hardware.org/?probe=9048b606d2) | May 13, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [fc96347868](https://linux-hardware.org/?probe=fc96347868) | May 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f02e90a00f](https://linux-hardware.org/?probe=f02e90a00f) | May 11, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [ec0cb83241](https://linux-hardware.org/?probe=ec0cb83241) | May 10, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3490... | Notebook    | [b3a5056cbf](https://linux-hardware.org/?probe=b3a5056cbf) | May 07, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [365c656e4a](https://linux-hardware.org/?probe=365c656e4a) | May 05, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [fca3b0c89b](https://linux-hardware.org/?probe=fca3b0c89b) | May 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9e8b256742](https://linux-hardware.org/?probe=9e8b256742) | May 03, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [e7cd00034c](https://linux-hardware.org/?probe=e7cd00034c) | May 02, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [39f6decf99](https://linux-hardware.org/?probe=39f6decf99) | May 02, 2021 |
| HP            | 255 G4                      | Notebook    | [9070448ace](https://linux-hardware.org/?probe=9070448ace) | May 01, 2021 |
| Lenovo        | ThinkPad T61 7659W1W        | Notebook    | [c366a3e7a2](https://linux-hardware.org/?probe=c366a3e7a2) | May 01, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [3d3ef81b3b](https://linux-hardware.org/?probe=3d3ef81b3b) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [d90f10abcd](https://linux-hardware.org/?probe=d90f10abcd) | Apr 29, 2021 |
| HP            | Stream Laptop 14-CB1xxx     | Notebook    | [b27160a3cb](https://linux-hardware.org/?probe=b27160a3cb) | Apr 29, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [dd68978e2b](https://linux-hardware.org/?probe=dd68978e2b) | Apr 28, 2021 |
| Lenovo        | ThinkStation C20 426593U    | Desktop     | [7ee064e334](https://linux-hardware.org/?probe=7ee064e334) | Apr 27, 2021 |
| Acer          | Extensa 2510                | Notebook    | [1f257d3f4e](https://linux-hardware.org/?probe=1f257d3f4e) | Apr 25, 2021 |
| Lenovo        | E31-80 80MX                 | Notebook    | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [764390758a](https://linux-hardware.org/?probe=764390758a) | Apr 21, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [eabc0fa5e5](https://linux-hardware.org/?probe=eabc0fa5e5) | Apr 21, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [8276e1fb2f](https://linux-hardware.org/?probe=8276e1fb2f) | Apr 20, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [cf4d5786e5](https://linux-hardware.org/?probe=cf4d5786e5) | Apr 19, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [fae6227cfc](https://linux-hardware.org/?probe=fae6227cfc) | Apr 19, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [0685ce717e](https://linux-hardware.org/?probe=0685ce717e) | Apr 16, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [a635a3acb3](https://linux-hardware.org/?probe=a635a3acb3) | Apr 13, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e08e82478f](https://linux-hardware.org/?probe=e08e82478f) | Apr 12, 2021 |
| Toshiba       | Satellite P750              | Notebook    | [d248a5f049](https://linux-hardware.org/?probe=d248a5f049) | Apr 11, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d53c2a8b0e](https://linux-hardware.org/?probe=d53c2a8b0e) | Apr 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Dell          | Inspiron 5391               | Notebook    | [80bf268441](https://linux-hardware.org/?probe=80bf268441) | Apr 08, 2021 |
| Dell          | 0080PM A00                  | Desktop     | [efc9497e6d](https://linux-hardware.org/?probe=efc9497e6d) | Apr 08, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [63e7ed5aa3](https://linux-hardware.org/?probe=63e7ed5aa3) | Apr 07, 2021 |
| Lenovo        | 36EB NOK                    | Desktop     | [2c6f4de8b9](https://linux-hardware.org/?probe=2c6f4de8b9) | Apr 06, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [08f8da317e](https://linux-hardware.org/?probe=08f8da317e) | Apr 03, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [9e5b4c92f4](https://linux-hardware.org/?probe=9e5b4c92f4) | Apr 01, 2021 |
| Toshiba       | Satellite L50D-B            | Notebook    | [6fdb3a7d9e](https://linux-hardware.org/?probe=6fdb3a7d9e) | Mar 31, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [90f906f5f9](https://linux-hardware.org/?probe=90f906f5f9) | Mar 31, 2021 |
| Gigabyte      | Z390 GAMING SLI-CF          | Desktop     | [b2fa0502d0](https://linux-hardware.org/?probe=b2fa0502d0) | Mar 31, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [269185aba1](https://linux-hardware.org/?probe=269185aba1) | Mar 28, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [dccf080cd2](https://linux-hardware.org/?probe=dccf080cd2) | Mar 26, 2021 |
| Dell          | G7 7588                     | Notebook    | [95e0518b2c](https://linux-hardware.org/?probe=95e0518b2c) | Mar 25, 2021 |
| Dell          | Latitude 5300               | Notebook    | [efd4a051e5](https://linux-hardware.org/?probe=efd4a051e5) | Mar 23, 2021 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [2290f44e04](https://linux-hardware.org/?probe=2290f44e04) | Mar 23, 2021 |
| Lenovo        | ThinkPad L460 20FV002EBR    | Notebook    | [f19448d66f](https://linux-hardware.org/?probe=f19448d66f) | Mar 19, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0debcb68ae](https://linux-hardware.org/?probe=0debcb68ae) | Mar 18, 2021 |
| Lenovo        | ThinkPad T520 4239CTO       | Notebook    | [e03adb0720](https://linux-hardware.org/?probe=e03adb0720) | Mar 17, 2021 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [31baa57d40](https://linux-hardware.org/?probe=31baa57d40) | Mar 17, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [13dfc4a9af](https://linux-hardware.org/?probe=13dfc4a9af) | Mar 17, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [7c5776953c](https://linux-hardware.org/?probe=7c5776953c) | Mar 15, 2021 |
| Lenovo        | ThinkPad Yoga 460 20ELS0... | Convertible | [4983586fe5](https://linux-hardware.org/?probe=4983586fe5) | Mar 12, 2021 |
| Dell          | G5 5505                     | Notebook    | [e8e38279d3](https://linux-hardware.org/?probe=e8e38279d3) | Mar 11, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [062dfb8010](https://linux-hardware.org/?probe=062dfb8010) | Mar 09, 2021 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [41de0a7ee7](https://linux-hardware.org/?probe=41de0a7ee7) | Mar 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [eec4ef3dce](https://linux-hardware.org/?probe=eec4ef3dce) | Mar 07, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [bd3a730b32](https://linux-hardware.org/?probe=bd3a730b32) | Mar 03, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [88635c9f76](https://linux-hardware.org/?probe=88635c9f76) | Feb 23, 2021 |
| Gigabyte      | AERO 15XV8                  | Notebook    | [c4ecc96eae](https://linux-hardware.org/?probe=c4ecc96eae) | Feb 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f9b4d57c67](https://linux-hardware.org/?probe=f9b4d57c67) | Feb 18, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [93115f0746](https://linux-hardware.org/?probe=93115f0746) | Feb 14, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [1bd84f7c03](https://linux-hardware.org/?probe=1bd84f7c03) | Feb 13, 2021 |
| HP            | ZBook 15                    | Notebook    | [dc1d23b1c6](https://linux-hardware.org/?probe=dc1d23b1c6) | Feb 12, 2021 |
| MSI           | Z87-G45 GAMING              | Desktop     | [67ca38a642](https://linux-hardware.org/?probe=67ca38a642) | Feb 12, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [72f95227fd](https://linux-hardware.org/?probe=72f95227fd) | Feb 11, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [130e9bdb5c](https://linux-hardware.org/?probe=130e9bdb5c) | Feb 11, 2021 |
| MSI           | Z87-G45 GAMING              | Desktop     | [e6937666ae](https://linux-hardware.org/?probe=e6937666ae) | Feb 11, 2021 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [e11200bd19](https://linux-hardware.org/?probe=e11200bd19) | Feb 10, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [75fc956099](https://linux-hardware.org/?probe=75fc956099) | Feb 10, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [cef326fa21](https://linux-hardware.org/?probe=cef326fa21) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [43bb3ec644](https://linux-hardware.org/?probe=43bb3ec644) | Feb 08, 2021 |
| Lenovo        | ThinkPad X140e 20BL000BU... | Notebook    | [5856d93198](https://linux-hardware.org/?probe=5856d93198) | Feb 07, 2021 |
| HP            | ENVY Notebook               | Notebook    | [4f20314e69](https://linux-hardware.org/?probe=4f20314e69) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4f64a771ff](https://linux-hardware.org/?probe=4f64a771ff) | Feb 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4d8f4f66c7](https://linux-hardware.org/?probe=4d8f4f66c7) | Jan 31, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [311f54d837](https://linux-hardware.org/?probe=311f54d837) | Jan 28, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [4b469e2e7e](https://linux-hardware.org/?probe=4b469e2e7e) | Jan 23, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [335242ec06](https://linux-hardware.org/?probe=335242ec06) | Jan 20, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [43b3323a07](https://linux-hardware.org/?probe=43b3323a07) | Jan 18, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [a0c3014b22](https://linux-hardware.org/?probe=a0c3014b22) | Jan 17, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [396227c9b5](https://linux-hardware.org/?probe=396227c9b5) | Jan 14, 2021 |
| Lenovo        | ThinkPad T510 4384FF3       | Notebook    | [9fd64a3945](https://linux-hardware.org/?probe=9fd64a3945) | Jan 11, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [929b0edb33](https://linux-hardware.org/?probe=929b0edb33) | Jan 11, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [6499961dbf](https://linux-hardware.org/?probe=6499961dbf) | Jan 09, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [2df429a577](https://linux-hardware.org/?probe=2df429a577) | Jan 06, 2021 |
| ASUSTek       | T102HA                      | Tablet      | [5df2e0f87d](https://linux-hardware.org/?probe=5df2e0f87d) | Jan 06, 2021 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [3d8c62e8fe](https://linux-hardware.org/?probe=3d8c62e8fe) | Jan 04, 2021 |
| ASUSTek       | Z87-PRO                     | Desktop     | [2ab19967fa](https://linux-hardware.org/?probe=2ab19967fa) | Dec 30, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [4d27980548](https://linux-hardware.org/?probe=4d27980548) | Dec 27, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [08895b552f](https://linux-hardware.org/?probe=08895b552f) | Dec 27, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [f2b808bdd1](https://linux-hardware.org/?probe=f2b808bdd1) | Dec 24, 2020 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [8b792fe096](https://linux-hardware.org/?probe=8b792fe096) | Dec 23, 2020 |
| HP            | 1905                        | Desktop     | [63771015f5](https://linux-hardware.org/?probe=63771015f5) | Dec 22, 2020 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7807b04ff](https://linux-hardware.org/?probe=c7807b04ff) | Dec 20, 2020 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| HP            | EliteBook Revolve 810       | Notebook    | [b6b29c8237](https://linux-hardware.org/?probe=b6b29c8237) | Dec 17, 2020 |
| Apple         | MacBookAir4,2               | Notebook    | [a3ebd820e2](https://linux-hardware.org/?probe=a3ebd820e2) | Dec 17, 2020 |
| Alienware     | 14                          | Notebook    | [3211a0e18d](https://linux-hardware.org/?probe=3211a0e18d) | Dec 12, 2020 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [a138dbf3ac](https://linux-hardware.org/?probe=a138dbf3ac) | Dec 08, 2020 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [00dc0236a1](https://linux-hardware.org/?probe=00dc0236a1) | Dec 07, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [75384533dc](https://linux-hardware.org/?probe=75384533dc) | Dec 06, 2020 |
| Dell          | Precision M6600             | Notebook    | [c3eafadf96](https://linux-hardware.org/?probe=c3eafadf96) | Dec 05, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7e7ad00d75](https://linux-hardware.org/?probe=7e7ad00d75) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [7e75c8dc00](https://linux-hardware.org/?probe=7e75c8dc00) | Dec 01, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [2381ec1bad](https://linux-hardware.org/?probe=2381ec1bad) | Nov 30, 2020 |
| MSI           | GT80S 6QE                   | Notebook    | [a938950688](https://linux-hardware.org/?probe=a938950688) | Nov 28, 2020 |
| MSI           | GT80S 6QE                   | Notebook    | [a07d34dcff](https://linux-hardware.org/?probe=a07d34dcff) | Nov 28, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [0ffe9c1f28](https://linux-hardware.org/?probe=0ffe9c1f28) | Nov 27, 2020 |
| Dell          | Precision M6600             | Notebook    | [990be59736](https://linux-hardware.org/?probe=990be59736) | Nov 21, 2020 |
| ASUSTek       | X550CL                      | Notebook    | [5315051a75](https://linux-hardware.org/?probe=5315051a75) | Nov 21, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [34e2c6b1de](https://linux-hardware.org/?probe=34e2c6b1de) | Nov 21, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2a4a52111f](https://linux-hardware.org/?probe=2a4a52111f) | Nov 21, 2020 |
| Dell          | 0KRC95 A02                  | Desktop     | [af91587001](https://linux-hardware.org/?probe=af91587001) | Nov 19, 2020 |
| Acer          | Aspire V3-575G              | Notebook    | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| Dell          | 0D4VY1 A00                  | All in one  | [071c584451](https://linux-hardware.org/?probe=071c584451) | Nov 18, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [1a46306857](https://linux-hardware.org/?probe=1a46306857) | Nov 16, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [3de701fc00](https://linux-hardware.org/?probe=3de701fc00) | Nov 12, 2020 |
| ASRock        | Z77 Extreme4                | Desktop     | [64d986c0ec](https://linux-hardware.org/?probe=64d986c0ec) | Nov 12, 2020 |
| Dell          | 0KRC95 A02                  | Desktop     | [6471eccd57](https://linux-hardware.org/?probe=6471eccd57) | Nov 11, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [9737ecaee9](https://linux-hardware.org/?probe=9737ecaee9) | Nov 06, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7a14486580](https://linux-hardware.org/?probe=7a14486580) | Nov 04, 2020 |
| Timi          | TM1607                      | Notebook    | [dbe64c3d75](https://linux-hardware.org/?probe=dbe64c3d75) | Nov 02, 2020 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [518c70a58e](https://linux-hardware.org/?probe=518c70a58e) | Nov 02, 2020 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [fa6d538a50](https://linux-hardware.org/?probe=fa6d538a50) | Oct 31, 2020 |
| HP            | 8455                        | Desktop     | [0671b6f4da](https://linux-hardware.org/?probe=0671b6f4da) | Oct 27, 2020 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [5cdfdbceae](https://linux-hardware.org/?probe=5cdfdbceae) | Oct 26, 2020 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [130d636b9e](https://linux-hardware.org/?probe=130d636b9e) | Oct 26, 2020 |
| HP            | 8455                        | Desktop     | [e37d606b6b](https://linux-hardware.org/?probe=e37d606b6b) | Oct 26, 2020 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3e19ade739](https://linux-hardware.org/?probe=3e19ade739) | Oct 25, 2020 |
| HP            | Notebook                    | Notebook    | [fe4c2b1ca0](https://linux-hardware.org/?probe=fe4c2b1ca0) | Oct 25, 2020 |
| Dell          | 0G214D A00                  | Desktop     | [21319d118b](https://linux-hardware.org/?probe=21319d118b) | Oct 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [1e6190a4f2](https://linux-hardware.org/?probe=1e6190a4f2) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [d3265c616b](https://linux-hardware.org/?probe=d3265c616b) | Oct 21, 2020 |
| Dell          | Inspiron 7559               | Notebook    | [01f75c41ed](https://linux-hardware.org/?probe=01f75c41ed) | Oct 20, 2020 |
| Microsoft     | Surface Laptop              | Tablet      | [26578393cc](https://linux-hardware.org/?probe=26578393cc) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [502cfa6428](https://linux-hardware.org/?probe=502cfa6428) | Oct 15, 2020 |
| Dell          | Inspiron 3493               | Notebook    | [459870a593](https://linux-hardware.org/?probe=459870a593) | Oct 14, 2020 |
| Lenovo        | MIIX 510-12ISK 80U1         | Tablet      | [eab288b1e2](https://linux-hardware.org/?probe=eab288b1e2) | Oct 13, 2020 |
| ASUSTek       | GL702ZC                     | Notebook    | [c90edc1b80](https://linux-hardware.org/?probe=c90edc1b80) | Oct 12, 2020 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [2abc472e43](https://linux-hardware.org/?probe=2abc472e43) | Oct 08, 2020 |
| Acer          | Aspire E5-573               | Notebook    | [89237e04fc](https://linux-hardware.org/?probe=89237e04fc) | Oct 04, 2020 |
| Unknown       | Unknown                     | Notebook    | [e50c3910d9](https://linux-hardware.org/?probe=e50c3910d9) | Oct 02, 2020 |
| MSI           | MS-7366                     | Desktop     | [ada828f120](https://linux-hardware.org/?probe=ada828f120) | Sep 29, 2020 |
| Dell          | 096JG8 A01                  | Desktop     | [a031f4a8a2](https://linux-hardware.org/?probe=a031f4a8a2) | Sep 29, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [4ec2f0a6cc](https://linux-hardware.org/?probe=4ec2f0a6cc) | Sep 29, 2020 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [ee969068e8](https://linux-hardware.org/?probe=ee969068e8) | Sep 28, 2020 |
| Dell          | G3 3579                     | Notebook    | [6853280510](https://linux-hardware.org/?probe=6853280510) | Sep 28, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a4e794299b](https://linux-hardware.org/?probe=a4e794299b) | Sep 28, 2020 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [ba15c37977](https://linux-hardware.org/?probe=ba15c37977) | Sep 28, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [f12775338c](https://linux-hardware.org/?probe=f12775338c) | Sep 27, 2020 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [9499adb6fc](https://linux-hardware.org/?probe=9499adb6fc) | Sep 26, 2020 |
| MSI           | MS-7366                     | Desktop     | [9938e6501b](https://linux-hardware.org/?probe=9938e6501b) | Sep 24, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [34f1896f7e](https://linux-hardware.org/?probe=34f1896f7e) | Sep 23, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [17e933a69c](https://linux-hardware.org/?probe=17e933a69c) | Sep 21, 2020 |
| HP            | 1497                        | Desktop     | [7cb2cee563](https://linux-hardware.org/?probe=7cb2cee563) | Sep 19, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [41b9e8cb16](https://linux-hardware.org/?probe=41b9e8cb16) | Sep 15, 2020 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [50a3035c47](https://linux-hardware.org/?probe=50a3035c47) | Sep 12, 2020 |
| Acer          | TravelMate P633-M           | Notebook    | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3919584d23](https://linux-hardware.org/?probe=3919584d23) | Sep 06, 2020 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [8802aa3282](https://linux-hardware.org/?probe=8802aa3282) | Sep 04, 2020 |
| Dell          | Latitude E6440              | Notebook    | [ddd1e2f728](https://linux-hardware.org/?probe=ddd1e2f728) | Sep 03, 2020 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [8b75181a08](https://linux-hardware.org/?probe=8b75181a08) | Sep 03, 2020 |
| ASUSTek       | UX310UA                     | Notebook    | [90e38ace34](https://linux-hardware.org/?probe=90e38ace34) | Sep 03, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [028f3ba060](https://linux-hardware.org/?probe=028f3ba060) | Sep 03, 2020 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [662f61d283](https://linux-hardware.org/?probe=662f61d283) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [143c679f1a](https://linux-hardware.org/?probe=143c679f1a) | Sep 03, 2020 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2ab9b15cb6](https://linux-hardware.org/?probe=2ab9b15cb6) | Sep 03, 2020 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [f70636a60c](https://linux-hardware.org/?probe=f70636a60c) | Sep 02, 2020 |
| HP            | EliteBook 840 G5            | Notebook    | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [82736e9fa5](https://linux-hardware.org/?probe=82736e9fa5) | Aug 23, 2020 |
| Dell          | Latitude E6430              | Notebook    | [8dab7d4223](https://linux-hardware.org/?probe=8dab7d4223) | Aug 15, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [8790b1b459](https://linux-hardware.org/?probe=8790b1b459) | Aug 12, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [e94f81e5f1](https://linux-hardware.org/?probe=e94f81e5f1) | Aug 12, 2020 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [844cca1bee](https://linux-hardware.org/?probe=844cca1bee) | Aug 09, 2020 |
| ASUSTek       | PRIME X570-P                | Desktop     | [cb7a700ec4](https://linux-hardware.org/?probe=cb7a700ec4) | Aug 07, 2020 |
| Dell          | Inspiron 5485 2n1           | Convertible | [b6c573f5aa](https://linux-hardware.org/?probe=b6c573f5aa) | Aug 05, 2020 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [935afc3dde](https://linux-hardware.org/?probe=935afc3dde) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | Notebook    | [fd00cb49a3](https://linux-hardware.org/?probe=fd00cb49a3) | Jul 27, 2020 |
| Lenovo        | ThinkPad X240 20AMS2QDOC    | Notebook    | [4830a55da9](https://linux-hardware.org/?probe=4830a55da9) | Jul 27, 2020 |
| Dell          | Latitude 7400               | Notebook    | [69e41d5126](https://linux-hardware.org/?probe=69e41d5126) | Jul 20, 2020 |
| Dell          | Latitude 7400               | Notebook    | [42561b6e01](https://linux-hardware.org/?probe=42561b6e01) | Jul 20, 2020 |
| Dell          | Latitude 7400               | Notebook    | [606ef1afa8](https://linux-hardware.org/?probe=606ef1afa8) | Jul 17, 2020 |
| Lenovo        | ThinkPad E595 20NFS0TD00    | Notebook    | [7fbac3cf0a](https://linux-hardware.org/?probe=7fbac3cf0a) | Jul 16, 2020 |
| Gigabyte      | B365M DS3H                  | Desktop     | [79c5cea1c1](https://linux-hardware.org/?probe=79c5cea1c1) | Jul 14, 2020 |
| Lenovo        | ThinkPad T460 20FMS2J000    | Notebook    | [ed0f57c08d](https://linux-hardware.org/?probe=ed0f57c08d) | Jul 14, 2020 |
| Fujitsu       | D2778-B1 S26361-D2778-B1    | Desktop     | [54774ae912](https://linux-hardware.org/?probe=54774ae912) | Jul 14, 2020 |
| Fujitsu       | D2618-C1 S26361-D2618-C1    | Desktop     | [85295c522b](https://linux-hardware.org/?probe=85295c522b) | Jul 14, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [6e3c82fbca](https://linux-hardware.org/?probe=6e3c82fbca) | Jul 13, 2020 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [d0c246206e](https://linux-hardware.org/?probe=d0c246206e) | Jul 13, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5ed412893a](https://linux-hardware.org/?probe=5ed412893a) | Jul 12, 2020 |
| Gigabyte      | B365M DS3H                  | Desktop     | [8baccc57ec](https://linux-hardware.org/?probe=8baccc57ec) | Jul 12, 2020 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [b81603bb8b](https://linux-hardware.org/?probe=b81603bb8b) | Jul 12, 2020 |
| MSI           | B450-A PRO MAX              | Desktop     | [22ee76b578](https://linux-hardware.org/?probe=22ee76b578) | Jun 29, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | Notebook    | [fc1d360821](https://linux-hardware.org/?probe=fc1d360821) | Jun 29, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1708b21dab](https://linux-hardware.org/?probe=1708b21dab) | Jun 28, 2020 |
| Microsoft     | Surface Book 2              | Tablet      | [d0d3d517ef](https://linux-hardware.org/?probe=d0d3d517ef) | Jun 16, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eb81165361](https://linux-hardware.org/?probe=eb81165361) | May 31, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [a2e2a6cf66](https://linux-hardware.org/?probe=a2e2a6cf66) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [0ae18cfc51](https://linux-hardware.org/?probe=0ae18cfc51) | May 05, 2020 |
| Gigabyte      | B85M-D3H                    | Desktop     | [adba7e2f11](https://linux-hardware.org/?probe=adba7e2f11) | Apr 24, 2020 |
| Lenovo        | G505s 20255                 | Notebook    | [21f31cf2d0](https://linux-hardware.org/?probe=21f31cf2d0) | Apr 21, 2020 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0b8f4015fa](https://linux-hardware.org/?probe=0b8f4015fa) | Feb 19, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [5a1d01743b](https://linux-hardware.org/?probe=5a1d01743b) | Feb 12, 2020 |
| HP            | EliteBook 8770w             | Notebook    | [44b687a5ef](https://linux-hardware.org/?probe=44b687a5ef) | Jan 31, 2020 |
| HP            | EliteBook 830 G6            | Notebook    | [c4078ad25e](https://linux-hardware.org/?probe=c4078ad25e) | Jan 25, 2020 |
| Acer          | Aspire ES1-520              | Notebook    | [12a0136c2d](https://linux-hardware.org/?probe=12a0136c2d) | Jan 20, 2020 |
| Shinelon C... | W65KJ1_KK1                  | Notebook    | [924a887f7d](https://linux-hardware.org/?probe=924a887f7d) | Dec 09, 2019 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [d5c741f8df](https://linux-hardware.org/?probe=d5c741f8df) | Dec 08, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [32f5e3b842](https://linux-hardware.org/?probe=32f5e3b842) | Nov 21, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4d0de4b06b](https://linux-hardware.org/?probe=4d0de4b06b) | Nov 19, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [791bd283a6](https://linux-hardware.org/?probe=791bd283a6) | Nov 18, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [50ea35444e](https://linux-hardware.org/?probe=50ea35444e) | Nov 17, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [42a25ee1f6](https://linux-hardware.org/?probe=42a25ee1f6) | Nov 08, 2019 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [587cf1258f](https://linux-hardware.org/?probe=587cf1258f) | Nov 07, 2019 |
| HP            | Spectre x360 Convertible... | Convertible | [90c646de9c](https://linux-hardware.org/?probe=90c646de9c) | Sep 13, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [3477d2f29e](https://linux-hardware.org/?probe=3477d2f29e) | Sep 10, 2019 |
| Dell          | Inspiron 7520               | Notebook    | [80bdb92976](https://linux-hardware.org/?probe=80bdb92976) | Sep 10, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 533       | 77.58%  |
| EndeavourOS         | 154       | 22.42%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| EndeavourOS | 679       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.12-arch1-1   | 20        | 2.56%   |
| 6.0.2-arch1-1     | 11        | 1.41%   |
| 5.17.1-arch1-1    | 11        | 1.41%   |
| 5.17.5-arch1-1    | 10        | 1.28%   |
| 6.0.9-arch1-1     | 9         | 1.15%   |
| 6.0.2-zen1-1-zen  | 9         | 1.15%   |
| 5.15.10-arch1-1   | 9         | 1.15%   |
| 5.19.7-arch1-1    | 8         | 1.03%   |
| 5.17.9-arch1-1    | 8         | 1.03%   |
| 5.15.7-arch1-1    | 8         | 1.03%   |
| 5.14.9-arch2-1    | 8         | 1.03%   |
| 5.13.13-arch1-1   | 8         | 1.03%   |
| 5.11.11-arch1-1   | 8         | 1.03%   |
| 5.9.14-arch1-1    | 7         | 0.9%    |
| 5.19.12-arch1-1   | 7         | 0.9%    |
| 5.18.16-arch1-1   | 7         | 0.9%    |
| 5.18.12-arch1-1   | 7         | 0.9%    |
| 5.16.10-arch1-1   | 7         | 0.9%    |
| 6.0.6-arch1-1     | 6         | 0.77%   |
| 5.9.1-arch1-1     | 6         | 0.77%   |
| 5.7.7-arch1-1     | 6         | 0.77%   |
| 5.19.11-arch1-1   | 6         | 0.77%   |
| 5.16.2-arch1-1    | 6         | 0.77%   |
| 5.15.4-arch1-1    | 6         | 0.77%   |
| 5.7.8-arch1-1     | 5         | 0.64%   |
| 5.19.9-zen1-1-zen | 5         | 0.64%   |
| 5.19.6-zen1-1-zen | 5         | 0.64%   |
| 5.19.13-arch1-1   | 5         | 0.64%   |
| 5.19.10-arch1-1   | 5         | 0.64%   |
| 5.18.3-arch1-1    | 5         | 0.64%   |
| 5.17.4-arch1-1    | 5         | 0.64%   |
| 5.16.8-arch1-1    | 5         | 0.64%   |
| 5.16.4-arch1-1    | 5         | 0.64%   |
| 5.16.16-arch1-1   | 5         | 0.64%   |
| 5.15.8-arch1-1    | 5         | 0.64%   |
| 5.15.74-1-lts     | 5         | 0.64%   |
| 5.15.2-arch1-1    | 5         | 0.64%   |
| 5.15.11-arch2-1   | 5         | 0.64%   |
| 5.14.2-arch1-2    | 5         | 0.64%   |
| 5.14.14-arch1-1   | 5         | 0.64%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.12 | 28        | 3.59%   |
| 6.0.2   | 21        | 2.69%   |
| 5.17.1  | 15        | 1.92%   |
| 5.17.5  | 14        | 1.79%   |
| 6.0.9   | 12        | 1.54%   |
| 6.0.6   | 12        | 1.54%   |
| 5.13.13 | 12        | 1.54%   |
| 5.18.12 | 11        | 1.41%   |
| 5.17.9  | 11        | 1.41%   |
| 5.19.9  | 10        | 1.28%   |
| 5.19.7  | 10        | 1.28%   |
| 5.14.9  | 10        | 1.28%   |
| 5.19.13 | 9         | 1.15%   |
| 5.18.16 | 9         | 1.15%   |
| 5.15.7  | 9         | 1.15%   |
| 5.15.4  | 9         | 1.15%   |
| 5.15.10 | 9         | 1.15%   |
| 5.11.11 | 9         | 1.15%   |
| 5.9.1   | 8         | 1.03%   |
| 5.19.12 | 8         | 1.03%   |
| 5.16.16 | 8         | 1.03%   |
| 5.15.2  | 8         | 1.03%   |
| 5.12.13 | 8         | 1.03%   |
| 5.11.16 | 8         | 1.03%   |
| 5.9.14  | 7         | 0.9%    |
| 5.8.5   | 7         | 0.9%    |
| 5.19.6  | 7         | 0.9%    |
| 5.19.11 | 7         | 0.9%    |
| 5.18.3  | 7         | 0.9%    |
| 5.16.4  | 7         | 0.9%    |
| 5.16.2  | 7         | 0.9%    |
| 5.16.10 | 7         | 0.9%    |
| 5.7.7   | 6         | 0.77%   |
| 5.19.10 | 6         | 0.77%   |
| 5.18.1  | 6         | 0.77%   |
| 5.17.4  | 6         | 0.77%   |
| 5.17.3  | 6         | 0.77%   |
| 5.16.8  | 6         | 0.77%   |
| 5.15.6  | 6         | 0.77%   |
| 5.15.11 | 6         | 0.77%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 131       | 17.33%  |
| 5.19    | 77        | 10.19%  |
| 5.16    | 66        | 8.73%   |
| 5.17    | 64        | 8.47%   |
| 6.0     | 61        | 8.07%   |
| 5.18    | 58        | 7.67%   |
| 5.14    | 52        | 6.88%   |
| 5.12    | 38        | 5.03%   |
| 5.10    | 38        | 5.03%   |
| 5.11    | 37        | 4.89%   |
| 5.9     | 35        | 4.63%   |
| 5.13    | 35        | 4.63%   |
| 5.8     | 24        | 3.17%   |
| 5.7     | 21        | 2.78%   |
| 5.4     | 7         | 0.93%   |
| 5.6     | 5         | 0.66%   |
| 5.5     | 2         | 0.26%   |
| 4.19    | 2         | 0.26%   |
| 5.2     | 1         | 0.13%   |
| 5.17.1  | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 678       | 99.85%  |
| aarch64 | 1         | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 244       | 34.41%  |
| GNOME           | 165       | 23.27%  |
| XFCE            | 135       | 19.04%  |
| X-Cinnamon      | 30        | 4.23%   |
| i3              | 24        | 3.39%   |
| KDE             | 22        | 3.1%    |
| Budgie          | 17        | 2.4%    |
| Cinnamon        | 15        | 2.12%   |
| Unknown         | 14        | 1.97%   |
| sway            | 7         | 0.99%   |
| MATE            | 7         | 0.99%   |
| LXQt            | 7         | 0.99%   |
| GNOME Flashback | 4         | 0.56%   |
| Deepin          | 4         | 0.56%   |
| awesome         | 3         | 0.42%   |
| openbox         | 2         | 0.28%   |
| Hyprland        | 2         | 0.28%   |
| bspwm           | 2         | 0.28%   |
| qtile           | 1         | 0.14%   |
| LXDE            | 1         | 0.14%   |
| LeftWM          | 1         | 0.14%   |
| jwm             | 1         | 0.14%   |
| herbstluftwm    | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 529       | 76.22%  |
| Wayland | 131       | 18.88%  |
| Tty     | 21        | 3.03%   |
| Unknown | 12        | 1.73%   |
| Web     | 1         | 0.14%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 205       | 29.33%  |
| Unknown | 176       | 25.18%  |
| SDDM    | 168       | 24.03%  |
| GDM     | 102       | 14.59%  |
| TDM     | 48        | 6.87%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 334       | 49.05%  |
| en_GB   | 48        | 7.05%   |
| it_IT   | 39        | 5.73%   |
| de_DE   | 38        | 5.58%   |
| en_CA   | 33        | 4.85%   |
| fr_FR   | 18        | 2.64%   |
| ru_RU   | 14        | 2.06%   |
| en_IN   | 12        | 1.76%   |
| en_AU   | 12        | 1.76%   |
| pl_PL   | 11        | 1.62%   |
| Unknown | 11        | 1.62%   |
| es_ES   | 9         | 1.32%   |
| pt_BR   | 7         | 1.03%   |
| en_DK   | 7         | 1.03%   |
| nl_NL   | 6         | 0.88%   |
| es_AR   | 6         | 0.88%   |
| en_AG   | 6         | 0.88%   |
| tr_TR   | 5         | 0.73%   |
| fi_FI   | 5         | 0.73%   |
| es_MX   | 5         | 0.73%   |
| sv_SE   | 4         | 0.59%   |
| nl_BE   | 4         | 0.59%   |
| en_PH   | 4         | 0.59%   |
| en_NZ   | 4         | 0.59%   |
| pt_PT   | 3         | 0.44%   |
| en_HK   | 3         | 0.44%   |
| de_AT   | 3         | 0.44%   |
| ru_UA   | 2         | 0.29%   |
| hu_HU   | 2         | 0.29%   |
| en_ZA   | 2         | 0.29%   |
| en_SG   | 2         | 0.29%   |
| de_CH   | 2         | 0.29%   |
| cs_CZ   | 2         | 0.29%   |
| sr_RS   | 1         | 0.15%   |
| sl_SI   | 1         | 0.15%   |
| sk_SK   | 1         | 0.15%   |
| ko_KR   | 1         | 0.15%   |
| id_ID   | 1         | 0.15%   |
| hr_HR   | 1         | 0.15%   |
| fr_CA   | 1         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 445       | 64.77%  |
| BIOS | 242       | 35.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 486       | 71.26%  |
| Btrfs   | 172       | 25.22%  |
| Overlay | 12        | 1.76%   |
| Xfs     | 6         | 0.88%   |
| F2fs    | 2         | 0.29%   |
| Unknown | 2         | 0.29%   |
| XXX4    | 1         | 0.15%   |
| Ext2    | 1         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 451       | 65.74%  |
| Unknown | 184       | 26.82%  |
| MBR     | 51        | 7.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 586       | 85.8%   |
| Yes       | 97        | 14.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 472       | 68.21%  |
| Yes       | 220       | 31.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 128       | 18.85%  |
| ASUSTek Computer    | 127       | 18.7%   |
| Hewlett-Packard     | 83        | 12.22%  |
| MSI                 | 65        | 9.57%   |
| Dell                | 64        | 9.43%   |
| Gigabyte Technology | 52        | 7.66%   |
| Acer                | 32        | 4.71%   |
| ASRock              | 25        | 3.68%   |
| Apple               | 17        | 2.5%    |
| HUAWEI              | 9         | 1.33%   |
| Microsoft           | 8         | 1.18%   |
| Timi                | 6         | 0.88%   |
| Samsung Electronics | 6         | 0.88%   |
| Google              | 6         | 0.88%   |
| Toshiba             | 4         | 0.59%   |
| Unknown             | 4         | 0.59%   |
| Schenker            | 3         | 0.44%   |
| ZOTAC               | 2         | 0.29%   |
| TrekStor            | 2         | 0.29%   |
| Positivo            | 2         | 0.29%   |
| Packard Bell        | 2         | 0.29%   |
| Notebook            | 2         | 0.29%   |
| Intel               | 2         | 0.29%   |
| Fujitsu             | 2         | 0.29%   |
| Biostar             | 2         | 0.29%   |
| AZW                 | 2         | 0.29%   |
| AMI                 | 2         | 0.29%   |
| UMAX                | 1         | 0.15%   |
| TUXEDO              | 1         | 0.15%   |
| Sony                | 1         | 0.15%   |
| Shinelon Computer   | 1         | 0.15%   |
| Razer               | 1         | 0.15%   |
| Radxa               | 1         | 0.15%   |
| Pine Microsystems   | 1         | 0.15%   |
| Medion              | 1         | 0.15%   |
| LG Electronics      | 1         | 0.15%   |
| LattePanda          | 1         | 0.15%   |
| iRU                 | 1         | 0.15%   |
| ILLEGEAR            | 1         | 0.15%   |
| Huanan              | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 9         | 1.33%   |
| ASUS All Series                       | 7         | 1.03%   |
| MSI MS-7C02                           | 4         | 0.59%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.59%   |
| ASUS ROG STRIX X570-E GAMING          | 4         | 0.59%   |
| ASRock B450 Pro4                      | 4         | 0.59%   |
| Apple MacBookAir7,2                   | 4         | 0.59%   |
| Unknown                               | 4         | 0.59%   |
| MSI MS-7C91                           | 3         | 0.44%   |
| MSI MS-7A38                           | 3         | 0.44%   |
| MSI Modern 14 B5M                     | 3         | 0.44%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.44%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.44%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.44%   |
| Gigabyte B550M AORUS PRO              | 3         | 0.44%   |
| ASUS TUF Gaming X570-PLUS             | 3         | 0.44%   |
| ASRock B450M Pro4                     | 3         | 0.44%   |
| Timi A35S                             | 2         | 0.29%   |
| Samsung 340XAA/350XAA/550XAA          | 2         | 0.29%   |
| MSI MS-7C84                           | 2         | 0.29%   |
| MSI MS-7B86                           | 2         | 0.29%   |
| MSI MS-7850                           | 2         | 0.29%   |
| MSI MS-7798                           | 2         | 0.29%   |
| Microsoft Surface Laptop Go           | 2         | 0.29%   |
| Microsoft Surface Go                  | 2         | 0.29%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 82MS    | 2         | 0.29%   |
| Lenovo Yoga 6 13ALC6 82ND             | 2         | 0.29%   |
| Lenovo ThinkPad T14 Gen 3 21CFCTO1WW  | 2         | 0.29%   |
| Lenovo ThinkPad T14 Gen 1 20UD0013MB  | 2         | 0.29%   |
| Lenovo IdeaPad Flex-14API 81SS        | 2         | 0.29%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 2         | 0.29%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 2         | 0.29%   |
| HUAWEI MACH-WX9                       | 2         | 0.29%   |
| HP Z230 Tower Workstation             | 2         | 0.29%   |
| HP ProDesk 600 G1 SFF                 | 2         | 0.29%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 2         | 0.29%   |
| HP Notebook                           | 2         | 0.29%   |
| HP Laptop 15-da0xxx                   | 2         | 0.29%   |
| HP ENVY x360 Convertible 15-ee0xxx    | 2         | 0.29%   |
| HP ENVY Laptop 13-ba0xxx              | 2         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 60        | 8.84%   |
| ASUS ROG           | 35        | 5.15%   |
| Lenovo IdeaPad     | 27        | 3.98%   |
| Dell Inspiron      | 19        | 2.8%    |
| HP Pavilion        | 18        | 2.65%   |
| Acer Aspire        | 18        | 2.65%   |
| Dell Latitude      | 17        | 2.5%    |
| ASUS TUF           | 16        | 2.36%   |
| ASUS PRIME         | 13        | 1.91%   |
| Lenovo Yoga        | 12        | 1.77%   |
| HP Laptop          | 10        | 1.47%   |
| HP ENVY            | 10        | 1.47%   |
| MSI MS-7C37        | 9         | 1.33%   |
| HP EliteBook       | 9         | 1.33%   |
| Microsoft Surface  | 8         | 1.18%   |
| Dell OptiPlex      | 8         | 1.18%   |
| ASUS All           | 7         | 1.03%   |
| Dell Precision     | 6         | 0.88%   |
| ASRock B450        | 6         | 0.88%   |
| Lenovo ThinkBook   | 5         | 0.74%   |
| Gigabyte B450      | 5         | 0.74%   |
| Dell XPS           | 5         | 0.74%   |
| Toshiba Satellite  | 4         | 0.59%   |
| MSI MS-7C02        | 4         | 0.59%   |
| MSI Modern         | 4         | 0.59%   |
| Lenovo ThinkCentre | 4         | 0.59%   |
| Lenovo IdeaCentre  | 4         | 0.59%   |
| HP 255             | 4         | 0.59%   |
| Gigabyte X570      | 4         | 0.59%   |
| Gigabyte B550M     | 4         | 0.59%   |
| Gigabyte B550      | 4         | 0.59%   |
| ASUS VivoBook      | 4         | 0.59%   |
| ASUS ASUS          | 4         | 0.59%   |
| ASRock B550M       | 4         | 0.59%   |
| Apple MacBookAir7  | 4         | 0.59%   |
| Acer Swift         | 4         | 0.59%   |
| Unknown            | 4         | 0.59%   |
| Schenker XMG       | 3         | 0.44%   |
| MSI Prestige       | 3         | 0.44%   |
| MSI MS-7C91        | 3         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 103       | 15.17%  |
| 2018    | 96        | 14.14%  |
| 2019    | 94        | 13.84%  |
| 2021    | 86        | 12.67%  |
| 2013    | 46        | 6.77%   |
| 2017    | 43        | 6.33%   |
| 2016    | 40        | 5.89%   |
| 2015    | 35        | 5.15%   |
| 2012    | 30        | 4.42%   |
| 2014    | 29        | 4.27%   |
| 2022    | 21        | 3.09%   |
| 2011    | 21        | 3.09%   |
| 2009    | 10        | 1.47%   |
| 2008    | 10        | 1.47%   |
| 2010    | 9         | 1.33%   |
| 2007    | 5         | 0.74%   |
| Unknown | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 383       | 56.41%  |
| Desktop     | 237       | 34.9%   |
| Convertible | 32        | 4.71%   |
| All in one  | 10        | 1.47%   |
| Tablet      | 9         | 1.33%   |
| Mini pc     | 7         | 1.03%   |
| Server      | 1         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 678       | 99.85%  |
| Enabled  | 1         | 0.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 673       | 99.12%  |
| Yes  | 6         | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 188       | 27.49%  |
| 4.01-8.0    | 156       | 22.81%  |
| 8.01-16.0   | 150       | 21.93%  |
| 32.01-64.0  | 92        | 13.45%  |
| 3.01-4.0    | 59        | 8.63%   |
| 24.01-32.0  | 21        | 3.07%   |
| 64.01-256.0 | 14        | 2.05%   |
| 1.01-2.0    | 4         | 0.58%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 188       | 25.44%  |
| 1.01-2.0   | 177       | 23.95%  |
| 4.01-8.0   | 163       | 22.06%  |
| 3.01-4.0   | 131       | 17.73%  |
| 8.01-16.0  | 45        | 6.09%   |
| 0.51-1.0   | 25        | 3.38%   |
| 16.01-24.0 | 5         | 0.68%   |
| 24.01-32.0 | 3         | 0.41%   |
| 0.01-0.5   | 2         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 365       | 52.29%  |
| 2      | 185       | 26.5%   |
| 3      | 65        | 9.31%   |
| 4      | 45        | 6.45%   |
| 5      | 24        | 3.44%   |
| 6      | 6         | 0.86%   |
| 7      | 3         | 0.43%   |
| 0      | 3         | 0.43%   |
| 9      | 1         | 0.14%   |
| 8      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 540       | 79.18%  |
| Yes       | 142       | 20.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 563       | 82.55%  |
| No        | 119       | 17.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 562       | 82.28%  |
| No        | 121       | 17.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 520       | 75.91%  |
| No        | 165       | 24.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 156       | 22.84%  |
| Germany     | 60        | 8.78%   |
| Italy       | 52        | 7.61%   |
| Canada      | 35        | 5.12%   |
| France      | 31        | 4.54%   |
| Poland      | 20        | 2.93%   |
| Netherlands | 20        | 2.93%   |
| UK          | 19        | 2.78%   |
| Brazil      | 19        | 2.78%   |
| India       | 18        | 2.64%   |
| Russia      | 17        | 2.49%   |
| Spain       | 14        | 2.05%   |
| Finland     | 14        | 2.05%   |
| Australia   | 14        | 2.05%   |
| Belgium     | 13        | 1.9%    |
| Turkey      | 12        | 1.76%   |
| Sweden      | 10        | 1.46%   |
| Austria     | 10        | 1.46%   |
| Mexico      | 9         | 1.32%   |
| Argentina   | 9         | 1.32%   |
| Indonesia   | 6         | 0.88%   |
| Hong Kong   | 6         | 0.88%   |
| Denmark     | 6         | 0.88%   |
| Ukraine     | 5         | 0.73%   |
| Switzerland | 5         | 0.73%   |
| Slovenia    | 5         | 0.73%   |
| Portugal    | 5         | 0.73%   |
| Norway      | 5         | 0.73%   |
| Malaysia    | 5         | 0.73%   |
| Czechia     | 5         | 0.73%   |
| Vietnam     | 4         | 0.59%   |
| Romania     | 4         | 0.59%   |
| Philippines | 4         | 0.59%   |
| New Zealand | 4         | 0.59%   |
| Greece      | 4         | 0.59%   |
| South Korea | 3         | 0.44%   |
| Singapore   | 3         | 0.44%   |
| Serbia      | 3         | 0.44%   |
| Hungary     | 3         | 0.44%   |
| Croatia     | 3         | 0.44%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Montreal          | 11        | 1.55%   |
| Helsinki          | 8         | 1.13%   |
| Berlin            | 8         | 1.13%   |
| Toms River        | 7         | 0.98%   |
| St Petersburg     | 7         | 0.98%   |
| Amsterdam         | 7         | 0.98%   |
| Sydney            | 6         | 0.84%   |
| Istanbul          | 6         | 0.84%   |
| Toronto           | 5         | 0.7%    |
| Paris             | 5         | 0.7%    |
| Barberton         | 5         | 0.7%    |
| Warsaw            | 4         | 0.56%   |
| Victoria          | 4         | 0.56%   |
| Turin             | 4         | 0.56%   |
| Rome              | 4         | 0.56%   |
| Ottawa            | 4         | 0.56%   |
| Moscow            | 4         | 0.56%   |
| Milan             | 4         | 0.56%   |
| Leipzig           | 4         | 0.56%   |
| Jacksonville      | 4         | 0.56%   |
| Hamburg           | 4         | 0.56%   |
| Zurich            | 3         | 0.42%   |
| Wroclaw           | 3         | 0.42%   |
| Villa Ballester   | 3         | 0.42%   |
| Singapore         | 3         | 0.42%   |
| Severna Park      | 3         | 0.42%   |
| Phoenix           | 3         | 0.42%   |
| Oldenburg         | 3         | 0.42%   |
| Manama            | 3         | 0.42%   |
| Madrid            | 3         | 0.42%   |
| Lyon              | 3         | 0.42%   |
| London            | 3         | 0.42%   |
| Frankfurt am Main | 3         | 0.42%   |
| Florence          | 3         | 0.42%   |
| Düsseldorf       | 3         | 0.42%   |
| Central           | 3         | 0.42%   |
| Brussels          | 3         | 0.42%   |
| Belgrade          | 3         | 0.42%   |
| Zapopan           | 2         | 0.28%   |
| Vienna            | 2         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 228       | 341    | 20.6%   |
| WDC                         | 147       | 219    | 13.28%  |
| Seagate                     | 136       | 185    | 12.29%  |
| Kingston                    | 70        | 101    | 6.32%   |
| SanDisk                     | 60        | 69     | 5.42%   |
| Toshiba                     | 48        | 57     | 4.34%   |
| Crucial                     | 46        | 67     | 4.16%   |
| SK hynix                    | 37        | 42     | 3.34%   |
| Intel                       | 28        | 37     | 2.53%   |
| Unknown                     | 23        | 31     | 2.08%   |
| Micron Technology           | 21        | 23     | 1.9%    |
| Phison                      | 18        | 19     | 1.63%   |
| HGST                        | 18        | 22     | 1.63%   |
| Hitachi                     | 17        | 18     | 1.54%   |
| A-DATA Technology           | 14        | 21     | 1.26%   |
| Apple                       | 12        | 17     | 1.08%   |
| KIOXIA                      | 11        | 11     | 0.99%   |
| China                       | 10        | 10     | 0.9%    |
| Corsair                     | 8         | 8      | 0.72%   |
| PNY                         | 7         | 7      | 0.63%   |
| SPCC                        | 6         | 6      | 0.54%   |
| Phison Electronics          | 6         | 6      | 0.54%   |
| XPG                         | 5         | 5      | 0.45%   |
| Transcend                   | 5         | 6      | 0.45%   |
| OCZ                         | 5         | 5      | 0.45%   |
| Micron/Crucial Technology   | 5         | 6      | 0.45%   |
| LITEONIT                    | 5         | 6      | 0.45%   |
| Kingston Technology Company | 5         | 7      | 0.45%   |
| Gigabyte Technology         | 5         | 7      | 0.45%   |
| SABRENT                     | 4         | 5      | 0.36%   |
| Intenso                     | 4         | 5      | 0.36%   |
| Patriot                     | 3         | 5      | 0.27%   |
| Mushkin                     | 3         | 3      | 0.27%   |
| Maxone                      | 3         | 3      | 0.27%   |
| JMicron Technology          | 3         | 3      | 0.27%   |
| AMicro                      | 3         | 4      | 0.27%   |
| WDC WDS                     | 2         | 2      | 0.18%   |
| USB3.1                      | 2         | 3      | 0.18%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.18%   |
| StoreJet                    | 2         | 2      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST2000DM008-2FR102 2TB                       | 18        | 1.44%   |
| Samsung SSD 860 EVO 1TB                              | 17        | 1.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 14        | 1.12%   |
| Samsung SSD 860 EVO 500GB                            | 13        | 1.04%   |
| Kingston SA400S37120G 120GB SSD                      | 12        | 0.96%   |
| Seagate ST1000LM035-1RK172 1TB                       | 11        | 0.88%   |
| Samsung SSD 850 EVO 500GB                            | 11        | 0.88%   |
| Kingston SA400S37240G 240GB SSD                      | 11        | 0.88%   |
| Samsung SSD 850 EVO 250GB                            | 10        | 0.8%    |
| Crucial CT500MX500SSD1 500GB                         | 10        | 0.8%    |
| WDC WD10EZEX-08WN4A0 1TB                             | 9         | 0.72%   |
| Seagate ST4000DM004-2CV104 4TB                       | 9         | 0.72%   |
| Samsung SSD 870 QVO 1TB                              | 9         | 0.72%   |
| Samsung SSD 860 EVO 250GB                            | 9         | 0.72%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 8         | 0.64%   |
| Samsung SSD 970 EVO 500GB                            | 8         | 0.64%   |
| HGST HTS721010A9E630 1TB                             | 8         | 0.64%   |
| Seagate ST500LT012-1DG142 500GB                      | 7         | 0.56%   |
| Samsung NVMe SSD Drive 512GB                         | 7         | 0.56%   |
| Samsung NVMe SSD Drive 1TB                           | 7         | 0.56%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 6         | 0.48%   |
| Unknown SD/MMC/MS PRO 8GB                            | 6         | 0.48%   |
| Seagate ST2000DM006-2DM164 2TB                       | 6         | 0.48%   |
| Seagate ST1000DM010-2EP102 1TB                       | 6         | 0.48%   |
| Samsung SSD 870 EVO 250GB                            | 6         | 0.48%   |
| Kingston SA400S37480G 480GB SSD                      | 6         | 0.48%   |
| SK hynix HFM001TD3JX013N 1024GB                      | 5         | 0.4%    |
| Seagate Expansion Desk 8TB                           | 5         | 0.4%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 5         | 0.4%    |
| Samsung SSD 980 500GB                                | 5         | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB                       | 5         | 0.4%    |
| Samsung SSD 970 EVO 1TB                              | 5         | 0.4%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 5         | 0.4%    |
| Samsung NVMe SSD Drive 250GB                         | 5         | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 5         | 0.4%    |
| KIOXIA KBG40ZNV512G 512GB                            | 5         | 0.4%    |
| Hitachi HTS545050A7E380 500GB                        | 5         | 0.4%    |
| Crucial CT240BX500SSD1 240GB                         | 5         | 0.4%    |
| Crucial CT1000MX500SSD1 1TB                          | 5         | 0.4%    |
| WDC WDS100T3X0C-00SJG0 1TB                           | 4         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 129       | 174    | 40.44%  |
| WDC                 | 97        | 137    | 30.41%  |
| Toshiba             | 28        | 31     | 8.78%   |
| HGST                | 18        | 22     | 5.64%   |
| Hitachi             | 17        | 18     | 5.33%   |
| Samsung Electronics | 9         | 18     | 2.82%   |
| Unknown             | 6         | 6      | 1.88%   |
| Maxone              | 3         | 3      | 0.94%   |
| Fujitsu             | 2         | 2      | 0.63%   |
| ASMT                | 2         | 4      | 0.63%   |
| StoreJet            | 1         | 1      | 0.31%   |
| RSH-319             | 1         | 2      | 0.31%   |
| PI-041              | 1         | 1      | 0.31%   |
| Maxtor              | 1         | 1      | 0.31%   |
| JMicron Technology  | 1         | 1      | 0.31%   |
| HPE                 | 1         | 1      | 0.31%   |
| Generic-            | 1         | 1      | 0.31%   |
| ASMedia             | 1         | 1      | 0.31%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 130       | 173    | 30.88%  |
| Kingston            | 50        | 75     | 11.88%  |
| Crucial             | 39        | 51     | 9.26%   |
| WDC                 | 32        | 41     | 7.6%    |
| SanDisk             | 29        | 35     | 6.89%   |
| China               | 10        | 10     | 2.38%   |
| Micron Technology   | 9         | 11     | 2.14%   |
| Toshiba             | 8         | 10     | 1.9%    |
| A-DATA Technology   | 8         | 9      | 1.9%    |
| SK hynix            | 7         | 8      | 1.66%   |
| Intel               | 7         | 10     | 1.66%   |
| Apple               | 7         | 10     | 1.66%   |
| OCZ                 | 5         | 5      | 1.19%   |
| LITEONIT            | 5         | 6      | 1.19%   |
| Transcend           | 4         | 4      | 0.95%   |
| SPCC                | 4         | 4      | 0.95%   |
| Seagate             | 4         | 6      | 0.95%   |
| PNY                 | 4         | 4      | 0.95%   |
| Intenso             | 4         | 5      | 0.95%   |
| Gigabyte Technology | 4         | 5      | 0.95%   |
| Corsair             | 4         | 4      | 0.95%   |
| Patriot             | 3         | 5      | 0.71%   |
| Mushkin             | 3         | 3      | 0.71%   |
| WDC WDS             | 2         | 2      | 0.48%   |
| Phison              | 2         | 2      | 0.48%   |
| Leven               | 2         | 3      | 0.48%   |
| KingSpec            | 2         | 2      | 0.48%   |
| GOODRAM             | 2         | 2      | 0.48%   |
| Zheino              | 1         | 1      | 0.24%   |
| WALTON              | 1         | 1      | 0.24%   |
| V-GeN               | 1         | 1      | 0.24%   |
| USB3.0              | 1         | 1      | 0.24%   |
| Unknown             | 1         | 2      | 0.24%   |
| UMAX                | 1         | 1      | 0.24%   |
| Timetec             | 1         | 2      | 0.24%   |
| Teclast             | 1         | 3      | 0.24%   |
| Team                | 1         | 2      | 0.24%   |
| StoreJet            | 1         | 1      | 0.24%   |
| Plextor             | 1         | 2      | 0.24%   |
| Pioneer             | 1         | 3      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 344       | 471    | 35.21%  |
| SSD     | 338       | 545    | 34.6%   |
| HDD     | 264       | 424    | 27.02%  |
| MMC     | 16        | 22     | 1.64%   |
| Unknown | 15        | 19     | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 450       | 912    | 51.9%   |
| NVMe | 341       | 462    | 39.33%  |
| SAS  | 60        | 85     | 6.92%   |
| MMC  | 16        | 22     | 1.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 324       | 537    | 49.69%  |
| 0.51-1.0   | 205       | 271    | 31.44%  |
| 1.01-2.0   | 66        | 86     | 10.12%  |
| 3.01-4.0   | 25        | 39     | 3.83%   |
| 4.01-10.0  | 15        | 18     | 2.3%    |
| 2.01-3.0   | 14        | 15     | 2.15%   |
| 10.01-20.0 | 3         | 3      | 0.46%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 151       | 21.48%  |
| 251-500        | 136       | 19.35%  |
| 1001-2000      | 112       | 15.93%  |
| 501-1000       | 101       | 14.37%  |
| More than 3000 | 63        | 8.96%   |
| Unknown        | 44        | 6.26%   |
| 2001-3000      | 38        | 5.41%   |
| 51-100         | 27        | 3.84%   |
| 1-20           | 20        | 2.84%   |
| 21-50          | 11        | 1.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 151       | 20.46%  |
| 101-250        | 125       | 16.94%  |
| 21-50          | 100       | 13.55%  |
| 51-100         | 98        | 13.28%  |
| 251-500        | 75        | 10.16%  |
| 501-1000       | 62        | 8.4%    |
| 1001-2000      | 51        | 6.91%   |
| Unknown        | 44        | 5.96%   |
| More than 3000 | 18        | 2.44%   |
| 2001-3000      | 12        | 1.63%   |
| 0              | 2         | 0.27%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Hitachi HTS545050A7E380 500GB            | 3         | 3      | 4.84%   |
| HGST HTS721010A9E630 1TB                 | 3         | 3      | 4.84%   |
| Samsung Electronics SSD 970 EVO 500GB    | 2         | 2      | 3.23%   |
| HGST HTS545050A7E680 500GB               | 2         | 3      | 3.23%   |
| XPG GAMMIX S11 480GB                     | 1         | 1      | 1.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 1.61%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 1         | 1      | 1.61%   |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 1.61%   |
| WDC WD5000AZRX-00A8LB0 500GB             | 1         | 1      | 1.61%   |
| WDC WD5000AVDS-63U7B1 500GB              | 1         | 1      | 1.61%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1         | 2      | 1.61%   |
| WDC WD20EARX-00PASB0 2TB                 | 1         | 1      | 1.61%   |
| WDC WD2003FZEX-00Z4SA0 2TB               | 1         | 1      | 1.61%   |
| WDC WD2002FYPS-01U1B0 2TB                | 1         | 1      | 1.61%   |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 1      | 1.61%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.61%   |
| WDC WD10EACS-00D6B1 1TB                  | 1         | 1      | 1.61%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 1         | 1      | 1.61%   |
| Transcend TS240GMTS420S 240GB SSD        | 1         | 1      | 1.61%   |
| Toshiba MK5055GSXF 500GB                 | 1         | 1      | 1.61%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 1.61%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 1.61%   |
| SK hynix SC308 SATA 128GB SSD            | 1         | 1      | 1.61%   |
| SK hynix HFS512G39TND-N210A 512GB SSD    | 1         | 1      | 1.61%   |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 1         | 1      | 1.61%   |
| Seagate ST9320325AS 320GB                | 1         | 4      | 1.61%   |
| Seagate ST6000VX0023-2EF110 6TB          | 1         | 1      | 1.61%   |
| Seagate ST500LX012-SSHD-8GB              | 1         | 1      | 1.61%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1      | 1.61%   |
| Seagate ST500LM021-1KJ152 500GB          | 1         | 1      | 1.61%   |
| Seagate ST3320620AS 320GB                | 1         | 1      | 1.61%   |
| Seagate ST2000DX002-2DV164 2TB           | 1         | 1      | 1.61%   |
| Seagate ST1000LM049-2GH172 1TB           | 1         | 1      | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 2      | 1.61%   |
| Seagate ST1000DM003-1ER162 1TB           | 1         | 2      | 1.61%   |
| SanDisk SSD PLUS 240GB                   | 1         | 1      | 1.61%   |
| SanDisk SDSSDA240G 240GB                 | 1         | 2      | 1.61%   |
| Samsung Electronics SSD 980 1TB          | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 960 EVO 500GB    | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 840 Series 120GB | 1         | 1      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 14     | 20%     |
| Seagate             | 9         | 15     | 15%     |
| Samsung Electronics | 8         | 8      | 13.33%  |
| Hitachi             | 5         | 5      | 8.33%   |
| HGST                | 5         | 6      | 8.33%   |
| Toshiba             | 3         | 3      | 5%      |
| SK hynix            | 3         | 3      | 5%      |
| SanDisk             | 2         | 3      | 3.33%   |
| Kingston            | 2         | 2      | 3.33%   |
| Crucial             | 2         | 6      | 3.33%   |
| XPG                 | 1         | 1      | 1.67%   |
| Transcend           | 1         | 1      | 1.67%   |
| OCZ                 | 1         | 1      | 1.67%   |
| Intel               | 1         | 1      | 1.67%   |
| Fujitsu             | 1         | 1      | 1.67%   |
| Drevo               | 1         | 1      | 1.67%   |
| Corsair             | 1         | 1      | 1.67%   |
| ASMT                | 1         | 2      | 1.67%   |
| Apple               | 1         | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 11     | 29.41%  |
| Seagate             | 9         | 15     | 26.47%  |
| Hitachi             | 5         | 5      | 14.71%  |
| HGST                | 5         | 6      | 14.71%  |
| Toshiba             | 2         | 2      | 5.88%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| Fujitsu             | 1         | 1      | 2.94%   |
| ASMT                | 1         | 2      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 43     | 56.67%  |
| SSD  | 20        | 26     | 33.33%  |
| NVMe | 6         | 6      | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HD252HJ 250GB | 1         | 1      | 33.33%  |
| LITEON CA3-8D512 512GB            | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| LITEON              | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 464       | 900    | 60.81%  |
| Detected | 238       | 502    | 31.19%  |
| Malfunc  | 58        | 75     | 7.6%    |
| Failed   | 3         | 4      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 378       | 39.92%  |
| AMD                            | 170       | 17.95%  |
| Samsung Electronics            | 120       | 12.67%  |
| SanDisk                        | 63        | 6.65%   |
| Phison Electronics             | 30        | 3.17%   |
| SK hynix                       | 29        | 3.06%   |
| Kingston Technology Company    | 26        | 2.75%   |
| ASMedia Technology             | 23        | 2.43%   |
| Micron Technology              | 13        | 1.37%   |
| KIOXIA                         | 13        | 1.37%   |
| Toshiba America Info Systems   | 12        | 1.27%   |
| Micron/Crucial Technology      | 12        | 1.27%   |
| ADATA Technology               | 8         | 0.84%   |
| Marvell Technology Group       | 7         | 0.74%   |
| JMicron Technology             | 6         | 0.63%   |
| Solid State Storage Technology | 5         | 0.53%   |
| Realtek Semiconductor          | 5         | 0.53%   |
| Apple                          | 5         | 0.53%   |
| Silicon Motion                 | 4         | 0.42%   |
| Nvidia                         | 4         | 0.42%   |
| Union Memory (Shenzhen)        | 3         | 0.32%   |
| Seagate Technology             | 3         | 0.32%   |
| Lite-On Technology             | 2         | 0.21%   |
| Lenovo                         | 2         | 0.21%   |
| Yangtze Memory Technologies    | 1         | 0.11%   |
| Transcend                      | 1         | 0.11%   |
| LSI Logic / Symbios Logic      | 1         | 0.11%   |
| Broadcom / LSI                 | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 128       | 12.46%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 62        | 6.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 50        | 4.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 39        | 3.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 34        | 3.31%   |
| Samsung NVMe SSD Controller 980                                                | 30        | 2.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 27        | 2.63%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 23        | 2.24%   |
| AMD 500 Series Chipset SATA Controller                                         | 19        | 1.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 18        | 1.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 18        | 1.75%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 17        | 1.66%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 16        | 1.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 15        | 1.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 15        | 1.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 14        | 1.36%   |
| Phison E12 NVMe Controller                                                     | 14        | 1.36%   |
| Micron Non-Volatile memory controller                                          | 13        | 1.27%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 12        | 1.17%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 12        | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 1.17%   |
| Intel SSD 660P Series                                                          | 12        | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 12        | 1.17%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 12        | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 11        | 1.07%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 10        | 0.97%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 10        | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                               | 10        | 0.97%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 10        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 0.97%   |
| SanDisk Non-Volatile memory controller                                         | 9         | 0.88%   |
| Kingston Company Company Non-Volatile memory controller                        | 9         | 0.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 9         | 0.88%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 0.88%   |
| Kingston Company A2000 NVMe SSD                                                | 8         | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 8         | 0.78%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 0.68%   |
| Intel SATA Controller [RAID mode]                                              | 7         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 488       | 54.04%  |
| NVMe | 339       | 37.54%  |
| RAID | 51        | 5.65%   |
| IDE  | 23        | 2.55%   |
| SAS  | 2         | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 444       | 65.39%  |
| AMD    | 234       | 34.46%  |
| ARM    | 1         | 0.15%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 5600X 6-Core Processor            | 13        | 1.91%   |
| AMD Ryzen 5 3600 6-Core Processor             | 13        | 1.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 1.62%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.62%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 11        | 1.62%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 11        | 1.62%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 1.47%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 1.33%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 9         | 1.33%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.33%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 1.18%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 1.03%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 7         | 1.03%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 1.03%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 7         | 1.03%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 7         | 1.03%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.03%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.88%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 0.88%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 6         | 0.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 0.88%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 0.88%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 0.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 5         | 0.74%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 0.74%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 5         | 0.74%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 0.74%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 0.74%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 5         | 0.74%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.59%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 4         | 0.59%   |
| Intel Core i7-4770K CPU @ 3.50GHz             | 4         | 0.59%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.59%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.59%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 4         | 0.59%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 4         | 0.59%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 4         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 166       | 24.45%  |
| Intel Core i7           | 137       | 20.18%  |
| AMD Ryzen 5             | 82        | 12.08%  |
| AMD Ryzen 7             | 68        | 10.01%  |
| Other                   | 47        | 6.92%   |
| Intel Core i3           | 31        | 4.57%   |
| AMD Ryzen 9             | 29        | 4.27%   |
| Intel Celeron           | 24        | 3.53%   |
| Intel Core 2 Duo        | 12        | 1.77%   |
| Intel Xeon              | 11        | 1.62%   |
| AMD Ryzen 7 PRO         | 10        | 1.47%   |
| AMD Ryzen 3             | 10        | 1.47%   |
| AMD A4                  | 8         | 1.18%   |
| Intel Pentium           | 6         | 0.88%   |
| AMD A8                  | 4         | 0.59%   |
| Intel Core i9           | 3         | 0.44%   |
| Intel Core 2 Quad       | 3         | 0.44%   |
| AMD Ryzen Threadripper  | 3         | 0.44%   |
| AMD FX                  | 3         | 0.44%   |
| Intel Pentium Dual-Core | 2         | 0.29%   |
| Intel Core m3           | 2         | 0.29%   |
| AMD Ryzen 5 PRO         | 2         | 0.29%   |
| AMD E1                  | 2         | 0.29%   |
| AMD A10                 | 2         | 0.29%   |
| Intel Pentium Gold      | 1         | 0.15%   |
| Intel Pentium Dual      | 1         | 0.15%   |
| Intel Core m5           | 1         | 0.15%   |
| Intel Core 2 Extreme    | 1         | 0.15%   |
| Intel Core 2            | 1         | 0.15%   |
| Intel Atom              | 1         | 0.15%   |
| AMD Phenom II X4        | 1         | 0.15%   |
| AMD E                   | 1         | 0.15%   |
| AMD Athlon X4           | 1         | 0.15%   |
| AMD Athlon II X4        | 1         | 0.15%   |
| AMD Athlon II           | 1         | 0.15%   |
| AMD Athlon              | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 252       | 37.06%  |
| 2      | 182       | 26.76%  |
| 6      | 106       | 15.59%  |
| 8      | 104       | 15.29%  |
| 12     | 19        | 2.79%   |
| 10     | 6         | 0.88%   |
| 16     | 5         | 0.74%   |
| 14     | 3         | 0.44%   |
| 3      | 2         | 0.29%   |
| 32     | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 675       | 99.26%  |
| 2      | 5         | 0.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 537       | 79.09%  |
| 1      | 142       | 20.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 676       | 99.56%  |
| Unknown        | 2         | 0.29%   |
| 64-bit         | 1         | 0.15%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 212       | 30.77%  |
| 0x306c3    | 29        | 4.21%   |
| 0x08701021 | 25        | 3.63%   |
| 0x306a9    | 22        | 3.19%   |
| 0x0a50000c | 22        | 3.19%   |
| 0x406e3    | 21        | 3.05%   |
| 0x806ea    | 20        | 2.9%    |
| 0x906ea    | 19        | 2.76%   |
| 0x806e9    | 18        | 2.61%   |
| 0x506e3    | 18        | 2.61%   |
| 0x806ec    | 14        | 2.03%   |
| 0x906e9    | 13        | 1.89%   |
| 0x806c1    | 13        | 1.89%   |
| 0x40651    | 13        | 1.89%   |
| 0x08600104 | 13        | 1.89%   |
| 0x08600106 | 12        | 1.74%   |
| 0x706e5    | 11        | 1.6%    |
| 0x08108109 | 11        | 1.6%    |
| 0x08608103 | 10        | 1.45%   |
| 0x0a201009 | 9         | 1.31%   |
| 0x206a7    | 8         | 1.16%   |
| 0x08701013 | 8         | 1.16%   |
| 0x706a1    | 7         | 1.02%   |
| 0x306d4    | 7         | 1.02%   |
| 0x1067a    | 7         | 1.02%   |
| 0xa0652    | 6         | 0.87%   |
| 0x806d1    | 6         | 0.87%   |
| 0x08108102 | 6         | 0.87%   |
| 0x406c4    | 5         | 0.73%   |
| 0x0a201016 | 5         | 0.73%   |
| 0x06006705 | 5         | 0.73%   |
| 0xa0655    | 4         | 0.58%   |
| 0x906a3    | 4         | 0.58%   |
| 0x806eb    | 4         | 0.58%   |
| 0x08600102 | 4         | 0.58%   |
| 0x0800820d | 4         | 0.58%   |
| 0x08001137 | 4         | 0.58%   |
| 0xa0653    | 3         | 0.44%   |
| 0x906ed    | 3         | 0.44%   |
| 0x706a8    | 3         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 132       | 19.41%  |
| Zen 2            | 87        | 12.79%  |
| Haswell          | 64        | 9.41%   |
| Zen 3            | 53        | 7.79%   |
| Skylake          | 51        | 7.5%    |
| Zen+             | 32        | 4.71%   |
| IvyBridge        | 32        | 4.71%   |
| Unknown          | 26        | 3.82%   |
| Icelake          | 23        | 3.38%   |
| CometLake        | 21        | 3.09%   |
| TigerLake        | 20        | 2.94%   |
| Zen              | 16        | 2.35%   |
| SandyBridge      | 16        | 2.35%   |
| Broadwell        | 14        | 2.06%   |
| Penryn           | 13        | 1.91%   |
| Silvermont       | 11        | 1.62%   |
| Excavator        | 11        | 1.62%   |
| Goldmont plus    | 10        | 1.47%   |
| Westmere         | 8         | 1.18%   |
| Core             | 8         | 1.18%   |
| Alderlake Hybrid | 7         | 1.03%   |
| Jaguar           | 6         | 0.88%   |
| Nehalem          | 5         | 0.74%   |
| Piledriver       | 4         | 0.59%   |
| Puma             | 2         | 0.29%   |
| K10              | 2         | 0.29%   |
| Tremont          | 1         | 0.15%   |
| Steamroller      | 1         | 0.15%   |
| K10 Llano        | 1         | 0.15%   |
| Goldmont         | 1         | 0.15%   |
| Bulldozer        | 1         | 0.15%   |
| Bobcat           | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 338       | 40.53%  |
| Nvidia | 261       | 31.29%  |
| AMD    | 235       | 28.18%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                               | 40        | 4.69%   |
| Intel UHD Graphics 620                                                                   | 29        | 3.4%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 28        | 3.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 27        | 3.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 2.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 24        | 2.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 2.46%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 2.11%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 17        | 2%      |
| Intel HD Graphics 620                                                                    | 17        | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 1.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 13        | 1.53%   |
| AMD Lucienne                                                                             | 13        | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 12        | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 12        | 1.41%   |
| Intel HD Graphics 530                                                                    | 11        | 1.29%   |
| Intel HD Graphics 630                                                                    | 10        | 1.17%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.17%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 1.17%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 10        | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 1.06%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 9         | 1.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.06%   |
| Intel HD Graphics 5500                                                                   | 9         | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 1.06%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 9         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.94%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 8         | 0.94%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8         | 0.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 0.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 0.82%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 7         | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 7         | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.82%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 7         | 0.82%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 0.82%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 6         | 0.7%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 210       | 30.75%  |
| 1 x AMD        | 177       | 25.92%  |
| 1 x Nvidia     | 130       | 19.03%  |
| Intel + Nvidia | 104       | 15.23%  |
| AMD + Nvidia   | 25        | 3.66%   |
| Intel + AMD    | 18        | 2.64%   |
| 2 x AMD        | 17        | 2.49%   |
| Other          | 1         | 0.15%   |
| 2 x Nvidia     | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 482       | 70.88%  |
| Proprietary | 197       | 28.97%  |
| Unknown     | 1         | 0.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 373       | 54.06%  |
| 0.01-0.5   | 77        | 11.16%  |
| 1.01-2.0   | 57        | 8.26%   |
| 7.01-8.0   | 56        | 8.12%   |
| 3.01-4.0   | 51        | 7.39%   |
| 0.51-1.0   | 25        | 3.62%   |
| 5.01-6.0   | 24        | 3.48%   |
| 8.01-16.0  | 19        | 2.75%   |
| 2.01-3.0   | 7         | 1.01%   |
| 16.01-24.0 | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 95        | 11.42%  |
| Samsung Electronics     | 91        | 10.94%  |
| BOE                     | 79        | 9.5%    |
| Chimei Innolux          | 69        | 8.29%   |
| LG Display              | 67        | 8.05%   |
| Goldstar                | 43        | 5.17%   |
| Dell                    | 43        | 5.17%   |
| Acer                    | 31        | 3.73%   |
| AOC                     | 29        | 3.49%   |
| Ancor Communications    | 26        | 3.13%   |
| BenQ                    | 25        | 3%      |
| Lenovo                  | 21        | 2.52%   |
| Hewlett-Packard         | 19        | 2.28%   |
| Apple                   | 17        | 2.04%   |
| PANDA                   | 16        | 1.92%   |
| Sharp                   | 15        | 1.8%    |
| ASUSTek Computer        | 13        | 1.56%   |
| Philips                 | 11        | 1.32%   |
| ViewSonic               | 10        | 1.2%    |
| InfoVision              | 10        | 1.2%    |
| Iiyama                  | 9         | 1.08%   |
| Vizio                   | 7         | 0.84%   |
| Gigabyte Technology     | 6         | 0.72%   |
| Sony                    | 5         | 0.6%    |
| Chi Mei Optoelectronics | 4         | 0.48%   |
| Sceptre Tech            | 3         | 0.36%   |
| RTK                     | 3         | 0.36%   |
| Panasonic               | 3         | 0.36%   |
| LG Electronics          | 3         | 0.36%   |
| Fujitsu Siemens         | 3         | 0.36%   |
| Eizo                    | 3         | 0.36%   |
| CSO                     | 3         | 0.36%   |
| Valve                   | 2         | 0.24%   |
| Unknown                 | 2         | 0.24%   |
| Toshiba                 | 2         | 0.24%   |
| TMX                     | 2         | 0.24%   |
| Pixio                   | 2         | 0.24%   |
| MSI                     | 2         | 0.24%   |
| Lenovo Group Limited    | 2         | 0.24%   |
| JDI                     | 2         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 7         | 0.82%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 6         | 0.7%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 6         | 0.7%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 5         | 0.58%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch         | 5         | 0.58%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 5         | 0.58%   |
| AOC Q27G2G4 AOC2702 2560x1440 597x336mm 27.0-inch                    | 5         | 0.58%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch    | 4         | 0.47%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 4         | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 4         | 0.47%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch         | 4         | 0.47%   |
| Goldstar LG ULTRAGEAR GSM5B7F 2560x1440 600x340mm 27.2-inch          | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 4         | 0.47%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch        | 3         | 0.35%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch              | 3         | 0.35%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch    | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 3         | 0.35%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 3         | 0.35%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 3         | 0.35%   |
| InfoVision LCD Monitor IVO8544 1920x1080 294x165mm 13.3-inch         | 3         | 0.35%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch          | 3         | 0.35%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch       | 3         | 0.35%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch       | 3         | 0.35%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                    | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch     | 3         | 0.35%   |
| BOE LCD Monitor BOE0973 2560x1440 344x194mm 15.5-inch                | 3         | 0.35%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 3         | 0.35%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                 | 3         | 0.35%   |
| BenQ RL2455 BNQ7F1C 1920x1080 531x298mm 24.0-inch                    | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO315C 1366x768 256x144mm 11.6-inch        | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.35%   |
| AOC 24P1X AOC2401 1920x1200 518x324mm 24.1-inch                      | 3         | 0.35%   |
| Ancor Communications VS248 ACI2498 1920x1080 530x300mm 24.0-inch     | 3         | 0.35%   |
| Vizio D43f-F1 VIZ1027 1920x1080 940x529mm 42.5-inch                  | 2         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 388       | 49.05%  |
| 1366x768 (WXGA)    | 107       | 13.53%  |
| 2560x1440 (QHD)    | 72        | 9.1%    |
| 3840x2160 (4K)     | 57        | 7.21%   |
| 1920x1200 (WUXGA)  | 21        | 2.65%   |
| 1440x900 (WXGA+)   | 15        | 1.9%    |
| 1280x1024 (SXGA)   | 13        | 1.64%   |
| 2560x1600          | 12        | 1.52%   |
| 1680x1050 (WSXGA+) | 11        | 1.39%   |
| 1600x900 (HD+)     | 11        | 1.39%   |
| Unknown            | 10        | 1.26%   |
| 2560x1080          | 9         | 1.14%   |
| 3440x1440          | 7         | 0.88%   |
| 2880x1800          | 6         | 0.76%   |
| 1280x800 (WXGA)    | 6         | 0.76%   |
| 2160x1440          | 5         | 0.63%   |
| 3840x1080          | 4         | 0.51%   |
| 2736x1824          | 4         | 0.51%   |
| 1360x768           | 4         | 0.51%   |
| 3840x2400          | 2         | 0.25%   |
| 3840x1600          | 2         | 0.25%   |
| 3456x2160          | 2         | 0.25%   |
| 3000x2000          | 2         | 0.25%   |
| 1920x540           | 2         | 0.25%   |
| 1800x1200          | 2         | 0.25%   |
| 9840x3840          | 1         | 0.13%   |
| 4480x1440          | 1         | 0.13%   |
| 3840x1440          | 1         | 0.13%   |
| 3840x1200          | 1         | 0.13%   |
| 3520x1080          | 1         | 0.13%   |
| 3240x2160          | 1         | 0.13%   |
| 3200x2000          | 1         | 0.13%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 3200x1080          | 1         | 0.13%   |
| 3072x1920          | 1         | 0.13%   |
| 2880x1920          | 1         | 0.13%   |
| 2880x1700          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 2240x1400          | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 183       | 22.05%  |
| 13      | 98        | 11.81%  |
| 27      | 90        | 10.84%  |
| 24      | 88        | 10.6%   |
| 14      | 66        | 7.95%   |
| 23      | 45        | 5.42%   |
| 21      | 35        | 4.22%   |
| 17      | 33        | 3.98%   |
| Unknown | 23        | 2.77%   |
| 31      | 22        | 2.65%   |
| 34      | 18        | 2.17%   |
| 12      | 15        | 1.81%   |
| 19      | 13        | 1.57%   |
| 22      | 12        | 1.45%   |
| 18      | 12        | 1.45%   |
| 16      | 11        | 1.33%   |
| 11      | 8         | 0.96%   |
| 20      | 7         | 0.84%   |
| 54      | 6         | 0.72%   |
| 84      | 4         | 0.48%   |
| 49      | 4         | 0.48%   |
| 32      | 4         | 0.48%   |
| 10      | 4         | 0.48%   |
| 72      | 3         | 0.36%   |
| 46      | 3         | 0.36%   |
| 42      | 2         | 0.24%   |
| 37      | 2         | 0.24%   |
| 28      | 2         | 0.24%   |
| 26      | 2         | 0.24%   |
| 25      | 2         | 0.24%   |
| 74      | 1         | 0.12%   |
| 69      | 1         | 0.12%   |
| 65      | 1         | 0.12%   |
| 60      | 1         | 0.12%   |
| 58      | 1         | 0.12%   |
| 57      | 1         | 0.12%   |
| 52      | 1         | 0.12%   |
| 50      | 1         | 0.12%   |
| 48      | 1         | 0.12%   |
| 47      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 304       | 37.72%  |
| 501-600     | 201       | 24.94%  |
| 201-300     | 79        | 9.8%    |
| 401-500     | 71        | 8.81%   |
| 351-400     | 40        | 4.96%   |
| 601-700     | 32        | 3.97%   |
| 701-800     | 23        | 2.85%   |
| Unknown     | 23        | 2.85%   |
| 1001-1500   | 19        | 2.36%   |
| 1501-2000   | 9         | 1.12%   |
| 801-900     | 2         | 0.25%   |
| 901-1000    | 2         | 0.25%   |
| 101-200     | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 565       | 78.36%  |
| 16/10   | 81        | 11.23%  |
| Unknown | 20        | 2.77%   |
| 3/2     | 17        | 2.36%   |
| 21/9    | 17        | 2.36%   |
| 5/4     | 9         | 1.25%   |
| 4/3     | 4         | 0.55%   |
| 32/9    | 4         | 0.55%   |
| 6/5     | 2         | 0.28%   |
| 2.65    | 1         | 0.14%   |
| 0.62    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 184       | 22.58%  |
| 201-250        | 136       | 16.69%  |
| 81-90          | 124       | 15.21%  |
| 301-350        | 92        | 11.29%  |
| 71-80          | 46        | 5.64%   |
| 351-500        | 44        | 5.4%    |
| 251-300        | 32        | 3.93%   |
| 121-130        | 26        | 3.19%   |
| 151-200        | 24        | 2.94%   |
| Unknown        | 23        | 2.82%   |
| More than 1000 | 21        | 2.58%   |
| 141-150        | 15        | 1.84%   |
| 501-1000       | 13        | 1.6%    |
| 61-70          | 9         | 1.1%    |
| 111-120        | 9         | 1.1%    |
| 51-60          | 8         | 0.98%   |
| 41-50          | 4         | 0.49%   |
| 131-140        | 4         | 0.49%   |
| 1-40           | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 240       | 30.73%  |
| 51-100        | 229       | 29.32%  |
| 101-120       | 169       | 21.64%  |
| 161-240       | 72        | 9.22%   |
| More than 240 | 26        | 3.33%   |
| Unknown       | 23        | 2.94%   |
| 1-50          | 22        | 2.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 524       | 75.72%  |
| 2     | 150       | 21.68%  |
| 3     | 15        | 2.17%   |
| 4     | 2         | 0.29%   |
| 0     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 413       | 39.3%   |
| Intel                             | 377       | 35.87%  |
| Qualcomm Atheros                  | 81        | 7.71%   |
| Broadcom                          | 36        | 3.43%   |
| MediaTek                          | 21        | 2%      |
| ASIX Electronics                  | 15        | 1.43%   |
| TP-Link                           | 12        | 1.14%   |
| Microsoft                         | 9         | 0.86%   |
| D-Link                            | 8         | 0.76%   |
| Broadcom Limited                  | 7         | 0.67%   |
| Sierra Wireless                   | 6         | 0.57%   |
| Ralink Technology                 | 5         | 0.48%   |
| Ralink                            | 5         | 0.48%   |
| Marvell Technology Group          | 4         | 0.38%   |
| Lenovo                            | 4         | 0.38%   |
| Hewlett-Packard                   | 4         | 0.38%   |
| Samsung Electronics               | 3         | 0.29%   |
| DisplayLink                       | 3         | 0.29%   |
| Aquantia                          | 3         | 0.29%   |
| Apple                             | 3         | 0.29%   |
| Xiaomi                            | 2         | 0.19%   |
| Qualcomm                          | 2         | 0.19%   |
| Nvidia                            | 2         | 0.19%   |
| NetGear                           | 2         | 0.19%   |
| Microchip Technology              | 2         | 0.19%   |
| Huawei Technologies               | 2         | 0.19%   |
| Google                            | 2         | 0.19%   |
| Ericsson Business Mobile Networks | 2         | 0.19%   |
| Cypress Semiconductor             | 2         | 0.19%   |
| Wilocity                          | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| OPPO Electronics                  | 1         | 0.1%    |
| Motorola PCS                      | 1         | 0.1%    |
| Linksys                           | 1         | 0.1%    |
| InterBiometrics                   | 1         | 0.1%    |
| ICS Advent                        | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| Exar                              | 1         | 0.1%    |
| Edimax Technology                 | 1         | 0.1%    |
| D-Link System                     | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 280       | 22.35%  |
| Intel Wi-Fi 6 AX200                                               | 72        | 5.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 34        | 2.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 2.47%   |
| Intel I211 Gigabit Network Connection                             | 28        | 2.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 2.08%   |
| Intel Wireless 8265 / 8275                                        | 26        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23        | 1.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 21        | 1.68%   |
| Intel Wireless 7260                                               | 19        | 1.52%   |
| Intel Wireless 7265                                               | 18        | 1.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 16        | 1.28%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 1.28%   |
| Intel Wireless 8260                                               | 15        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 1.2%    |
| Intel Wireless 3165                                               | 14        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 13        | 1.04%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 13        | 1.04%   |
| Intel Wi-Fi 6 AX201                                               | 13        | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 13        | 1.04%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 1.04%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 12        | 0.96%   |
| Intel Ethernet Connection (2) I219-V                              | 12        | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 0.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 0.96%   |
| Intel Wireless-AC 9260                                            | 11        | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 11        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.8%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 0.8%    |
| Intel Ethernet Controller I225-V                                  | 9         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 8         | 0.64%   |
| Realtek 802.11ac NIC                                              | 8         | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 8         | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.64%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 8         | 0.64%   |
| D-Link 802.11ac NIC                                               | 8         | 0.64%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 0.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 324       | 53.64%  |
| Realtek Semiconductor                 | 100       | 16.56%  |
| Qualcomm Atheros                      | 66        | 10.93%  |
| Broadcom                              | 28        | 4.64%   |
| MediaTek                              | 20        | 3.31%   |
| TP-Link                               | 10        | 1.66%   |
| Microsoft                             | 8         | 1.32%   |
| D-Link                                | 8         | 1.32%   |
| Sierra Wireless                       | 6         | 0.99%   |
| Broadcom Limited                      | 6         | 0.99%   |
| Ralink Technology                     | 5         | 0.83%   |
| Ralink                                | 5         | 0.83%   |
| Marvell Technology Group              | 4         | 0.66%   |
| Qualcomm                              | 2         | 0.33%   |
| Wilocity                              | 1         | 0.17%   |
| Samsung Electronics                   | 1         | 0.17%   |
| Qualcomm Atheros Communications       | 1         | 0.17%   |
| NetGear                               | 1         | 0.17%   |
| Linksys                               | 1         | 0.17%   |
| Hewlett-Packard                       | 1         | 0.17%   |
| Fibocom                               | 1         | 0.17%   |
| Edimax Technology                     | 1         | 0.17%   |
| D-Link System                         | 1         | 0.17%   |
| Belkin Components                     | 1         | 0.17%   |
| AVM                                   | 1         | 0.17%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 72        | 11.78%  |
| Intel Wireless 8265 / 8275                                    | 26        | 4.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 23        | 3.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 21        | 3.44%   |
| Intel Wireless 7260                                           | 19        | 3.11%   |
| Intel Wireless 7265                                           | 18        | 2.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 16        | 2.62%   |
| Intel Wireless 8260                                           | 15        | 2.45%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 15        | 2.45%   |
| Intel Wireless 3165                                           | 14        | 2.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 13        | 2.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 13        | 2.13%   |
| Intel Wi-Fi 6 AX201                                           | 13        | 2.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 13        | 2.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 12        | 1.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 12        | 1.96%   |
| Intel Wireless-AC 9260                                        | 11        | 1.8%    |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 11        | 1.8%    |
| Intel Comet Lake PCH CNVi WiFi                                | 10        | 1.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 8         | 1.31%   |
| Realtek 802.11ac NIC                                          | 8         | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 8         | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 8         | 1.31%   |
| D-Link 802.11ac NIC                                           | 8         | 1.31%   |
| Broadcom BCM43142 802.11b/g/n                                 | 8         | 1.31%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 7         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 7         | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 7         | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 7         | 1.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 6         | 0.98%   |
| Intel Wireless 3160                                           | 6         | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 6         | 0.98%   |
| TP-Link 802.11ac NIC                                          | 5         | 0.82%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 5         | 0.82%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 5         | 0.82%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 5         | 0.82%   |
| Intel Centrino Advanced-N 6235                                | 5         | 0.82%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 5         | 0.82%   |
| Sierra Wireless EM7455                                        | 4         | 0.65%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 4         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 373       | 60.65%  |
| Intel                 | 157       | 25.53%  |
| Qualcomm Atheros      | 24        | 3.9%    |
| ASIX Electronics      | 15        | 2.44%   |
| Broadcom              | 13        | 2.11%   |
| Lenovo                | 4         | 0.65%   |
| DisplayLink           | 3         | 0.49%   |
| Aquantia              | 3         | 0.49%   |
| Apple                 | 3         | 0.49%   |
| Xiaomi                | 2         | 0.33%   |
| TP-Link               | 2         | 0.33%   |
| Samsung Electronics   | 2         | 0.33%   |
| Nvidia                | 2         | 0.33%   |
| Google                | 2         | 0.33%   |
| Cypress Semiconductor | 2         | 0.33%   |
| OPPO Electronics      | 1         | 0.16%   |
| NetGear               | 1         | 0.16%   |
| Motorola PCS          | 1         | 0.16%   |
| Microsoft             | 1         | 0.16%   |
| MediaTek              | 1         | 0.16%   |
| ICS Advent            | 1         | 0.16%   |
| D-Link                | 1         | 0.16%   |
| Broadcom Limited      | 1         | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 280       | 44.44%  |
| Realtek RTL8125 2.5GbE Controller                                 | 34        | 5.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31        | 4.92%   |
| Intel I211 Gigabit Network Connection                             | 28        | 4.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 4.13%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 2.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 2.06%   |
| Intel Ethernet Connection (2) I219-V                              | 12        | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 1.9%    |
| Intel Ethernet Connection (7) I219-V                              | 10        | 1.59%   |
| Intel Ethernet Controller I225-V                                  | 9         | 1.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 1.27%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.27%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.11%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.63%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.63%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.63%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 3         | 0.48%   |
| Realtek Realtek Ethernet controller                               | 3         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.48%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.48%   |
| Apple iBridge                                                     | 3         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.32%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.32%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.32%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.32%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]       | 2         | 0.32%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.32%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 561       | 49.51%  |
| Ethernet | 560       | 49.43%  |
| Modem    | 11        | 0.97%   |
| Unknown  | 1         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 450       | 61.56%  |
| Ethernet | 281       | 38.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 365       | 53.44%  |
| 1     | 285       | 41.73%  |
| 3     | 24        | 3.51%   |
| 0     | 5         | 0.73%   |
| 4     | 4         | 0.59%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 539       | 77.78%  |
| Yes  | 154       | 22.22%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 295       | 54.63%  |
| Realtek Semiconductor           | 71        | 13.15%  |
| Qualcomm Atheros Communications | 29        | 5.37%   |
| Cambridge Silicon Radio         | 26        | 4.81%   |
| Broadcom                        | 22        | 4.07%   |
| IMC Networks                    | 18        | 3.33%   |
| Lite-On Technology              | 16        | 2.96%   |
| Foxconn / Hon Hai               | 12        | 2.22%   |
| Apple                           | 12        | 2.22%   |
| ASUSTek Computer                | 11        | 2.04%   |
| Realtek                         | 5         | 0.93%   |
| Toshiba                         | 3         | 0.56%   |
| MediaTek                        | 3         | 0.56%   |
| Marvell Semiconductor           | 3         | 0.56%   |
| Dell                            | 3         | 0.56%   |
| USI                             | 2         | 0.37%   |
| TP-Link                         | 2         | 0.37%   |
| Ralink                          | 2         | 0.37%   |
| HTC (High Tech Computer)        | 2         | 0.37%   |
| Opticis                         | 1         | 0.19%   |
| Foxconn International           | 1         | 0.19%   |
| Dynex                           | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 107       | 19.78%  |
| Intel AX200 Bluetooth                                                | 70        | 12.94%  |
| Realtek Bluetooth Radio                                              | 53        | 9.8%    |
| Intel AX201 Bluetooth                                                | 44        | 8.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 32        | 5.91%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 26        | 4.81%   |
| Qualcomm Atheros  Bluetooth Device                                   | 19        | 3.51%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 15        | 2.77%   |
| Intel AX210 Bluetooth                                                | 13        | 2.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 10        | 1.85%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 8         | 1.48%   |
| Apple Bluetooth USB Host Controller                                  | 8         | 1.48%   |
| Intel Bluetooth Device                                               | 7         | 1.29%   |
| IMC Networks Wireless_Device                                         | 7         | 1.29%   |
| IMC Networks Bluetooth Radio                                         | 7         | 1.29%   |
| Foxconn / Hon Hai Wireless_Device                                    | 6         | 1.11%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 6         | 1.11%   |
| Realtek Bluetooth Radio                                              | 5         | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 5         | 0.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 5         | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4         | 0.74%   |
| Lite-On Bluetooth Device                                             | 4         | 0.74%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 4         | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 4         | 0.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 3         | 0.55%   |
| MediaTek Wireless_Device                                             | 3         | 0.55%   |
| Marvell Bluetooth and Wireless LAN Composite                         | 3         | 0.55%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 3         | 0.55%   |
| USI Bluetooth Device                                                 | 2         | 0.37%   |
| TP-Link UB500 Adapter                                                | 2         | 0.37%   |
| Toshiba Atheros AR3012 Bluetooth                                     | 2         | 0.37%   |
| Realtek RTL8821A Bluetooth                                           | 2         | 0.37%   |
| Ralink RT3290 Bluetooth                                              | 2         | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 2         | 0.37%   |
| Lite-On Bluetooth Radio                                              | 2         | 0.37%   |
| IMC Networks Bluetooth Device                                        | 2         | 0.37%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 2         | 0.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                    | 2         | 0.37%   |
| Broadcom BCM43142 Bluetooth 4.0                                      | 2         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 435       | 39.51%  |
| AMD                                             | 266       | 24.16%  |
| Nvidia                                          | 198       | 17.98%  |
| C-Media Electronics                             | 25        | 2.27%   |
| Logitech                                        | 15        | 1.36%   |
| Texas Instruments                               | 14        | 1.27%   |
| SteelSeries ApS                                 | 14        | 1.27%   |
| JMTek                                           | 9         | 0.82%   |
| Creative Labs                                   | 8         | 0.73%   |
| Kingston Technology                             | 7         | 0.64%   |
| Sony                                            | 6         | 0.54%   |
| Corsair                                         | 6         | 0.54%   |
| Razer USA                                       | 5         | 0.45%   |
| NAD Electronics                                 | 5         | 0.45%   |
| Lenovo                                          | 5         | 0.45%   |
| KORG                                            | 5         | 0.45%   |
| Focusrite-Novation                              | 5         | 0.45%   |
| Creative Technology                             | 5         | 0.45%   |
| AKAI                                            | 5         | 0.45%   |
| Realtek Semiconductor                           | 4         | 0.36%   |
| Blue Microphones                                | 4         | 0.36%   |
| Valve Software                                  | 3         | 0.27%   |
| Samson Technologies                             | 3         | 0.27%   |
| RODE Microphones                                | 3         | 0.27%   |
| GYROCOM C&C                                     | 3         | 0.27%   |
| Apple                                           | 3         | 0.27%   |
| XMOS                                            | 2         | 0.18%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.18%   |
| Sennheiser Communications                       | 2         | 0.18%   |
| M-Audio                                         | 2         | 0.18%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.18%   |
| KTMicro                                         | 2         | 0.18%   |
| Generalplus Technology                          | 2         | 0.18%   |
| AKAI Professional M.I.                          | 2         | 0.18%   |
| YZ Technology                                   | 1         | 0.09%   |
| Xilinx                                          | 1         | 0.09%   |
| VIA Technologies                                | 1         | 0.09%   |
| Trust                                           | 1         | 0.09%   |
| Tdlasunnic                                      | 1         | 0.09%   |
| Solid State System                              | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 114       | 8.47%   |
| Intel Sunrise Point-LP HD Audio                                            | 79        | 5.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 76        | 5.65%   |
| AMD Starship/Matisse HD Audio Controller                                   | 65        | 4.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 40        | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                 | 33        | 2.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 2.23%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 29        | 2.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 28        | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 26        | 1.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 26        | 1.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 25        | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 24        | 1.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 20        | 1.49%   |
| Nvidia GA104 High Definition Audio Controller                              | 19        | 1.41%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 18        | 1.34%   |
| Nvidia TU106 High Definition Audio Controller                              | 17        | 1.26%   |
| Nvidia GP104 High Definition Audio Controller                              | 17        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 17        | 1.26%   |
| Intel 8 Series HD Audio Controller                                         | 17        | 1.26%   |
| Intel Comet Lake PCH cAVS                                                  | 15        | 1.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15        | 1.11%   |
| AMD Navi 10 HDMI Audio                                                     | 15        | 1.11%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 1.04%   |
| Nvidia TU116 High Definition Audio Controller                              | 13        | 0.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 13        | 0.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 13        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 12        | 0.89%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 0.89%   |
| Intel 200 Series PCH HD Audio                                              | 12        | 0.89%   |
| AMD FCH Azalia Controller                                                  | 12        | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 0.82%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 0.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 0.82%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 11        | 0.82%   |
| AMD Kabini HDMI/DP Audio                                                   | 11        | 0.82%   |
| Nvidia GK104 HDMI Audio Controller                                         | 10        | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 10        | 0.74%   |
| Nvidia GM204 High Definition Audio Controller                              | 9         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 156       | 26.31%  |
| SK hynix            | 103       | 17.37%  |
| Micron Technology   | 65        | 10.96%  |
| Kingston            | 45        | 7.59%   |
| Corsair             | 44        | 7.42%   |
| G.Skill             | 42        | 7.08%   |
| Crucial             | 32        | 5.4%    |
| Unknown             | 27        | 4.55%   |
| A-DATA Technology   | 12        | 2.02%   |
| Team                | 10        | 1.69%   |
| Patriot             | 10        | 1.69%   |
| Ramaxel Technology  | 9         | 1.52%   |
| Unknown (ABCD)      | 6         | 1.01%   |
| Elpida              | 4         | 0.67%   |
| Unknown             | 4         | 0.67%   |
| Shenzhen Mic        | 2         | 0.34%   |
| Nanya Technology    | 2         | 0.34%   |
| GOODRAM             | 2         | 0.34%   |
| Golden Empire       | 2         | 0.34%   |
| V-GeN               | 1         | 0.17%   |
| Unknown (0x5846)    | 1         | 0.17%   |
| Toshiba             | 1         | 0.17%   |
| Teikon              | 1         | 0.17%   |
| Strontium           | 1         | 0.17%   |
| Smart Brazil        | 1         | 0.17%   |
| Smart               | 1         | 0.17%   |
| Sesame              | 1         | 0.17%   |
| Qimonda             | 1         | 0.17%   |
| PNY                 | 1         | 0.17%   |
| Neo Forza           | 1         | 0.17%   |
| Magnum Tech         | 1         | 0.17%   |
| Kllisre             | 1         | 0.17%   |
| KLEVV               | 1         | 0.17%   |
| GeIL                | 1         | 0.17%   |
| AMD                 | 1         | 0.17%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 2.47%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 12        | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 11        | 1.69%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 9         | 1.39%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 9         | 1.39%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 1.08%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 0.92%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 6         | 0.92%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.92%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.92%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.77%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.77%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.77%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.77%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 5         | 0.77%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 0.62%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.62%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.62%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.62%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.62%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s          | 4         | 0.62%   |
| Unknown                                                          | 4         | 0.62%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 3         | 0.46%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.46%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.46%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.46%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.46%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.46%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.46%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s            | 3         | 0.46%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 3         | 0.46%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 320       | 62.38%  |
| DDR3    | 120       | 23.39%  |
| LPDDR4  | 26        | 5.07%   |
| LPDDR3  | 19        | 3.7%    |
| DDR2    | 9         | 1.75%   |
| SDRAM   | 7         | 1.36%   |
| Unknown | 6         | 1.17%   |
| LPDDR5  | 3         | 0.58%   |
| DDR5    | 2         | 0.39%   |
| DDR     | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 293       | 57.34%  |
| DIMM         | 160       | 31.31%  |
| Row Of Chips | 49        | 9.59%   |
| Chip         | 6         | 1.17%   |
| RIMM         | 1         | 0.2%    |
| FB-DIMM      | 1         | 0.2%    |
| Unknown      | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 268       | 48.64%  |
| 4096  | 150       | 27.22%  |
| 16384 | 80        | 14.52%  |
| 2048  | 34        | 6.17%   |
| 32768 | 17        | 3.09%   |
| 1024  | 2         | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 141       | 25.31%  |
| 1600    | 95        | 17.06%  |
| 2667    | 88        | 15.8%   |
| 2400    | 33        | 5.92%   |
| 3600    | 29        | 5.21%   |
| 2133    | 29        | 5.21%   |
| 1333    | 18        | 3.23%   |
| 3266    | 16        | 2.87%   |
| 1867    | 16        | 2.87%   |
| 4267    | 7         | 1.26%   |
| 3466    | 6         | 1.08%   |
| 1334    | 6         | 1.08%   |
| 800     | 6         | 1.08%   |
| 3400    | 5         | 0.9%    |
| 3000    | 5         | 0.9%    |
| 4800    | 4         | 0.72%   |
| 3866    | 4         | 0.72%   |
| 3733    | 4         | 0.72%   |
| 6400    | 3         | 0.54%   |
| 3800    | 3         | 0.54%   |
| 2048    | 3         | 0.54%   |
| 1800    | 3         | 0.54%   |
| 667     | 3         | 0.54%   |
| Unknown | 3         | 0.54%   |
| 4266    | 2         | 0.36%   |
| 3500    | 2         | 0.36%   |
| 3333    | 2         | 0.36%   |
| 2733    | 2         | 0.36%   |
| 2666    | 2         | 0.36%   |
| 1648    | 2         | 0.36%   |
| 1066    | 2         | 0.36%   |
| 65535   | 1         | 0.18%   |
| 4333    | 1         | 0.18%   |
| 4000    | 1         | 0.18%   |
| 3151    | 1         | 0.18%   |
| 3134    | 1         | 0.18%   |
| 3066    | 1         | 0.18%   |
| 2933    | 1         | 0.18%   |
| 2800    | 1         | 0.18%   |
| 2267    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 33.33%  |
| Prolific Technology | 2         | 22.22%  |
| Hewlett-Packard     | 2         | 22.22%  |
| Seiko Epson         | 1         | 11.11%  |
| Pantum              | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port | 2         | 22.22%  |
| Seiko Epson WF-2010 Series    | 1         | 11.11%  |
| Pantum P2500W series          | 1         | 11.11%  |
| HP ENVY 5540 series           | 1         | 11.11%  |
| HP DeskJet 2130 series        | 1         | 11.11%  |
| Brother Printer               | 1         | 11.11%  |
| Brother HL-2130 series        | 1         | 11.11%  |
| Brother DCP-9015CDW           | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 91        | 19.57%  |
| IMC Networks                           | 60        | 12.9%   |
| Logitech                               | 43        | 9.25%   |
| Acer                                   | 39        | 8.39%   |
| Microdia                               | 30        | 6.45%   |
| Realtek Semiconductor                  | 25        | 5.38%   |
| Cheng Uei Precision Industry (Foxlink) | 21        | 4.52%   |
| Quanta                                 | 19        | 4.09%   |
| Apple                                  | 18        | 3.87%   |
| Syntek                                 | 17        | 3.66%   |
| Sunplus Innovation Technology          | 17        | 3.66%   |
| Lite-On Technology                     | 17        | 3.66%   |
| Microsoft                              | 5         | 1.08%   |
| Suyin                                  | 4         | 0.86%   |
| Samsung Electronics                    | 4         | 0.86%   |
| Lenovo                                 | 4         | 0.86%   |
| Valve Software                         | 3         | 0.65%   |
| Silicon Motion                         | 3         | 0.65%   |
| Luxvisions Innotech Limited            | 3         | 0.65%   |
| Hewlett-Packard                        | 3         | 0.65%   |
| Unknown                                | 2         | 0.43%   |
| Sonix Technology                       | 2         | 0.43%   |
| Primax Electronics                     | 2         | 0.43%   |
| MacroSilicon                           | 2         | 0.43%   |
| Intel                                  | 2         | 0.43%   |
| Google                                 | 2         | 0.43%   |
| GEMBIRD                                | 2         | 0.43%   |
| Alcor Micro                            | 2         | 0.43%   |
| Y Media                                | 1         | 0.22%   |
| Xiaomi                                 | 1         | 0.22%   |
| WCM_USB                                | 1         | 0.22%   |
| Trust                                  | 1         | 0.22%   |
| Tobii Technology AB                    | 1         | 0.22%   |
| Sunplus IT                             | 1         | 0.22%   |
| Sony                                   | 1         | 0.22%   |
| SN0002                                 | 1         | 0.22%   |
| SJ-180517-N                            | 1         | 0.22%   |
| S1F0009330LB620L4100030N               | 1         | 0.22%   |
| Ricoh                                  | 1         | 0.22%   |
| Razer USA                              | 1         | 0.22%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 26        | 5.57%   |
| IMC Networks Integrated Camera                   | 24        | 5.14%   |
| IMC Networks USB2.0 HD UVC WebCam                | 21        | 4.5%    |
| Chicony HD WebCam                                | 16        | 3.43%   |
| Acer Integrated Camera                           | 15        | 3.21%   |
| Syntek Integrated Camera                         | 11        | 2.36%   |
| Microdia Integrated_Webcam_HD                    | 11        | 2.36%   |
| Realtek Integrated_Webcam_HD                     | 10        | 2.14%   |
| Logitech HD Pro Webcam C920                      | 10        | 2.14%   |
| Logitech Webcam C270                             | 8         | 1.71%   |
| Apple iPhone 5/5C/5S/6/SE                        | 8         | 1.71%   |
| Acer HD Webcam                                   | 7         | 1.5%    |
| Chicony HP Wide Vision HD Camera                 | 6         | 1.28%   |
| Apple FaceTime HD Camera (Built-in)              | 6         | 1.28%   |
| Quanta HP TrueVision HD Camera                   | 5         | 1.07%   |
| Microdia Integrated Webcam                       | 5         | 1.07%   |
| Logitech C922 Pro Stream Webcam                  | 5         | 1.07%   |
| Lite-On Integrated Camera                        | 5         | 1.07%   |
| Chicony USB2.0 HD UVC WebCam                     | 5         | 1.07%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 5         | 1.07%   |
| Acer EasyCamera                                  | 5         | 1.07%   |
| Sunplus Integrated_Webcam_HD                     | 4         | 0.86%   |
| Sunplus HD WebCam                                | 4         | 0.86%   |
| Samsung Galaxy series, misc. (MTP mode)          | 4         | 0.86%   |
| Lite-On HP Webcam                                | 4         | 0.86%   |
| Chicony VGA WebCam                               | 4         | 0.86%   |
| Chicony HD User Facing                           | 4         | 0.86%   |
| Valve Software 3D Camera                         | 3         | 0.64%   |
| Syntek Lenovo EasyCamera                         | 3         | 0.64%   |
| Syntek EasyCamera                                | 3         | 0.64%   |
| Quanta HP Wide Vision HD Camera                  | 3         | 0.64%   |
| Quanta HP HD Camera                              | 3         | 0.64%   |
| Microdia Webcam Vitade AF                        | 3         | 0.64%   |
| Microdia USB 2.0 Camera                          | 3         | 0.64%   |
| Logitech Webcam C310                             | 3         | 0.64%   |
| Lite-On HP Wide Vision HD Camera                 | 3         | 0.64%   |
| IMC Networks ov9734_azurewave_camera             | 3         | 0.64%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 3         | 0.64%   |
| Chicony HP Webcam                                | 3         | 0.64%   |
| Chicony EasyCamera                               | 3         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 34        | 38.64%  |
| Validity Sensors           | 20        | 22.73%  |
| Shenzhen Goodix Technology | 15        | 17.05%  |
| Elan Microelectronics      | 9         | 10.23%  |
| LighTuning Technology      | 5         | 5.68%   |
| Upek                       | 3         | 3.41%   |
| Samsung Electronics        | 1         | 1.14%   |
| AuthenTec                  | 1         | 1.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 14        | 15.91%  |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 10.23%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 7.95%   |
| Synaptics  WBDI                                                            | 6         | 6.82%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 6.82%   |
| Elan ELAN:Fingerprint                                                      | 6         | 6.82%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 5.68%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 5.68%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 4.55%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 3.41%   |
| Elan ELAN:ARM-M4                                                           | 3         | 3.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 2.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.27%   |
| Validity Sensors VFS491                                                    | 1         | 1.14%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.14%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.14%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.14%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 1.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.14%   |
| AuthenTec AES2810                                                          | 1         | 1.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 15        | 50%     |
| Alcor Micro | 11        | 36.67%  |
| Lenovo      | 2         | 6.67%   |
| O2 Micro    | 1         | 3.33%   |
| HID Global  | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 35.48%  |
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 29.03%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 9.68%   |
| Broadcom 58200                                                               | 3         | 9.68%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 6.45%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.23%   |
| HID Global USB Reader V3                                                     | 1         | 3.23%   |
| Broadcom 5880                                                                | 1         | 3.23%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 468       | 67.05%  |
| 1     | 188       | 26.93%  |
| 2     | 40        | 5.73%   |
| 3     | 2         | 0.29%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 88        | 33.85%  |
| Net/ethernet             | 40        | 15.38%  |
| Chipcard                 | 29        | 11.15%  |
| Multimedia controller    | 24        | 9.23%   |
| Graphics card            | 24        | 9.23%   |
| Net/wireless             | 19        | 7.31%   |
| Camera                   | 13        | 5%      |
| Bluetooth                | 8         | 3.08%   |
| Network                  | 7         | 2.69%   |
| Storage                  | 2         | 0.77%   |
| Sound                    | 2         | 0.77%   |
| Unassigned class         | 1         | 0.38%   |
| Modem                    | 1         | 0.38%   |
| Dvb card                 | 1         | 0.38%   |
| Communication controller | 1         | 0.38%   |

