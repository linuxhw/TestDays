Linux in Finland - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Finland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Finland/Desktop/README.md) and [notebooks](/Location/Finland/Notebook/README.md).

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

Total: 1724

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [347dc56d43](https://linux-hardware.org/?probe=347dc56d43) | Dec 30, 2022 |
| HP            | 339A                        | Desktop     | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [33fd3ed258](https://linux-hardware.org/?probe=33fd3ed258) | Dec 29, 2022 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [c1c0ab5824](https://linux-hardware.org/?probe=c1c0ab5824) | Dec 28, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [43a0d87199](https://linux-hardware.org/?probe=43a0d87199) | Dec 28, 2022 |
| MouseCompu... | BC-MB1485UD11A-191          | Convertible | [b24a434561](https://linux-hardware.org/?probe=b24a434561) | Dec 27, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [bef58a2317](https://linux-hardware.org/?probe=bef58a2317) | Dec 26, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [7a7d8227ee](https://linux-hardware.org/?probe=7a7d8227ee) | Dec 25, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | Notebook    | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [3d63d2fe51](https://linux-hardware.org/?probe=3d63d2fe51) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [3cfcfad4ba](https://linux-hardware.org/?probe=3cfcfad4ba) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7714ba77eb](https://linux-hardware.org/?probe=7714ba77eb) | Dec 21, 2022 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [ef5cd85ef3](https://linux-hardware.org/?probe=ef5cd85ef3) | Dec 20, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | Notebook    | [9e860431a0](https://linux-hardware.org/?probe=9e860431a0) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8c140bbafc](https://linux-hardware.org/?probe=8c140bbafc) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5981154034](https://linux-hardware.org/?probe=5981154034) | Dec 20, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0361b1083f](https://linux-hardware.org/?probe=0361b1083f) | Dec 20, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [262a879a99](https://linux-hardware.org/?probe=262a879a99) | Dec 19, 2022 |
| Lenovo        | ThinkPad P73 20QR0028GE     | Notebook    | [8e689417f3](https://linux-hardware.org/?probe=8e689417f3) | Dec 16, 2022 |
| HP            | 829E                        | Mini pc     | [dccdfac601](https://linux-hardware.org/?probe=dccdfac601) | Dec 15, 2022 |
| HP            | 829E                        | Mini pc     | [10b9e184e1](https://linux-hardware.org/?probe=10b9e184e1) | Dec 15, 2022 |
| Lenovo        | ThinkPad T480s 20L8S4GU0... | Notebook    | [bed7f6d44e](https://linux-hardware.org/?probe=bed7f6d44e) | Dec 14, 2022 |
| Lenovo        | ThinkPad Helix 2nd 20CG0... | Tablet      | [e32ae95f08](https://linux-hardware.org/?probe=e32ae95f08) | Dec 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [66b2e8e737](https://linux-hardware.org/?probe=66b2e8e737) | Dec 14, 2022 |
| Acer          | Predator G9-591             | Notebook    | [838b0e0f8c](https://linux-hardware.org/?probe=838b0e0f8c) | Dec 13, 2022 |
| Acer          | Aspire A315-43              | Notebook    | [6d77f1e173](https://linux-hardware.org/?probe=6d77f1e173) | Dec 13, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9787630f1c](https://linux-hardware.org/?probe=9787630f1c) | Dec 12, 2022 |
| ASUSTek       | H170-PRO                    | Desktop     | [0a28fbd557](https://linux-hardware.org/?probe=0a28fbd557) | Dec 12, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [fa85be7b33](https://linux-hardware.org/?probe=fa85be7b33) | Dec 12, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [ab1dd22124](https://linux-hardware.org/?probe=ab1dd22124) | Dec 10, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c8890a2f74](https://linux-hardware.org/?probe=c8890a2f74) | Dec 09, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f1ac9526c5](https://linux-hardware.org/?probe=f1ac9526c5) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| ASUSTek       | P5Q-E                       | Desktop     | [fb93b5bdfa](https://linux-hardware.org/?probe=fb93b5bdfa) | Dec 06, 2022 |
| Acer          | Predator G9-591             | Notebook    | [6e8fe2e030](https://linux-hardware.org/?probe=6e8fe2e030) | Dec 06, 2022 |
| Dell          | Latitude E6440              | Notebook    | [425331326b](https://linux-hardware.org/?probe=425331326b) | Dec 06, 2022 |
| Valve         | Jupiter                     | Notebook    | [19f5d58b52](https://linux-hardware.org/?probe=19f5d58b52) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [504a0286fb](https://linux-hardware.org/?probe=504a0286fb) | Dec 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [4a2e796be8](https://linux-hardware.org/?probe=4a2e796be8) | Dec 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [8de79673ea](https://linux-hardware.org/?probe=8de79673ea) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e2f97abdea](https://linux-hardware.org/?probe=e2f97abdea) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [89e97c7099](https://linux-hardware.org/?probe=89e97c7099) | Nov 29, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [95b1694080](https://linux-hardware.org/?probe=95b1694080) | Nov 28, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [ae85dba67e](https://linux-hardware.org/?probe=ae85dba67e) | Nov 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [1e84d5c704](https://linux-hardware.org/?probe=1e84d5c704) | Nov 28, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [ccc431ef2e](https://linux-hardware.org/?probe=ccc431ef2e) | Nov 28, 2022 |
| HP            | 872E                        | Mini pc     | [9d8a2595d7](https://linux-hardware.org/?probe=9d8a2595d7) | Nov 27, 2022 |
| Lenovo        | ThinkPad T490 20N3000KMH    | Notebook    | [028c06fcdc](https://linux-hardware.org/?probe=028c06fcdc) | Nov 27, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [05983f8566](https://linux-hardware.org/?probe=05983f8566) | Nov 26, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2813bdf250](https://linux-hardware.org/?probe=2813bdf250) | Nov 26, 2022 |
| HP            | 872E                        | Mini pc     | [c7ff015966](https://linux-hardware.org/?probe=c7ff015966) | Nov 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ab6ce548bc](https://linux-hardware.org/?probe=ab6ce548bc) | Nov 26, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [5b0f04d592](https://linux-hardware.org/?probe=5b0f04d592) | Nov 25, 2022 |
| Dell          | Latitude 5410               | Notebook    | [1eeb98c3b0](https://linux-hardware.org/?probe=1eeb98c3b0) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| Dell          | Latitude 5410               | Notebook    | [a9b8b4208d](https://linux-hardware.org/?probe=a9b8b4208d) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [db9c9330b7](https://linux-hardware.org/?probe=db9c9330b7) | Nov 23, 2022 |
| ASUSTek       | PRIME Z690-P                | Notebook    | [436bd74a38](https://linux-hardware.org/?probe=436bd74a38) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [07d9dc965a](https://linux-hardware.org/?probe=07d9dc965a) | Nov 20, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [9484c00cb6](https://linux-hardware.org/?probe=9484c00cb6) | Nov 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [dd13c1df3f](https://linux-hardware.org/?probe=dd13c1df3f) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f5fd3e9e4b](https://linux-hardware.org/?probe=f5fd3e9e4b) | Nov 16, 2022 |
| Intel         | D53427RKE G87971-406        | Desktop     | [e3bc504c6e](https://linux-hardware.org/?probe=e3bc504c6e) | Nov 15, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1472f0a14e](https://linux-hardware.org/?probe=1472f0a14e) | Nov 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [6a4c697203](https://linux-hardware.org/?probe=6a4c697203) | Nov 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [074c3a8b43](https://linux-hardware.org/?probe=074c3a8b43) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [b0d1cd283f](https://linux-hardware.org/?probe=b0d1cd283f) | Nov 14, 2022 |
| HP            | Notebook                    | Notebook    | [95ecccf4c7](https://linux-hardware.org/?probe=95ecccf4c7) | Nov 14, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [00db55919b](https://linux-hardware.org/?probe=00db55919b) | Nov 14, 2022 |
| HP            | 1998                        | Desktop     | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | Desktop     | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2a6473f450](https://linux-hardware.org/?probe=2a6473f450) | Nov 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a0d94329a6](https://linux-hardware.org/?probe=a0d94329a6) | Nov 13, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [c1044ebf60](https://linux-hardware.org/?probe=c1044ebf60) | Nov 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [0d8609e1ed](https://linux-hardware.org/?probe=0d8609e1ed) | Nov 13, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [cee6d10d17](https://linux-hardware.org/?probe=cee6d10d17) | Nov 13, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9f0e94860c](https://linux-hardware.org/?probe=9f0e94860c) | Nov 12, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed46e3161](https://linux-hardware.org/?probe=fed46e3161) | Nov 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [81f59ba6f5](https://linux-hardware.org/?probe=81f59ba6f5) | Nov 11, 2022 |
| HP            | 8054                        | Desktop     | [08a9a98d04](https://linux-hardware.org/?probe=08a9a98d04) | Nov 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3fe8b5fef3](https://linux-hardware.org/?probe=3fe8b5fef3) | Nov 10, 2022 |
| HP            | 8054                        | Desktop     | [4ce3ccc26d](https://linux-hardware.org/?probe=4ce3ccc26d) | Nov 09, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [dc9837cefc](https://linux-hardware.org/?probe=dc9837cefc) | Nov 09, 2022 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [9746d693c3](https://linux-hardware.org/?probe=9746d693c3) | Nov 08, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [6921f657bf](https://linux-hardware.org/?probe=6921f657bf) | Nov 07, 2022 |
| Lenovo        | ThinkPad T420 4238LY7       | Notebook    | [c5cf611a37](https://linux-hardware.org/?probe=c5cf611a37) | Nov 07, 2022 |
| MSI           | GP66 Leopard 11UG           | Notebook    | [0dab96ade2](https://linux-hardware.org/?probe=0dab96ade2) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [012705552d](https://linux-hardware.org/?probe=012705552d) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9af713ef6e](https://linux-hardware.org/?probe=9af713ef6e) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [dae32fcba7](https://linux-hardware.org/?probe=dae32fcba7) | Nov 04, 2022 |
| Acer          | Predator G9-591             | Notebook    | [ca65bba88a](https://linux-hardware.org/?probe=ca65bba88a) | Nov 03, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [4b9071c932](https://linux-hardware.org/?probe=4b9071c932) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| Dell          | Latitude E6330              | Notebook    | [51ded2feb1](https://linux-hardware.org/?probe=51ded2feb1) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [479fdd085d](https://linux-hardware.org/?probe=479fdd085d) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [dfde89926c](https://linux-hardware.org/?probe=dfde89926c) | Oct 31, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [135f93d663](https://linux-hardware.org/?probe=135f93d663) | Oct 31, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [cbdfd56f05](https://linux-hardware.org/?probe=cbdfd56f05) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [031a5998a5](https://linux-hardware.org/?probe=031a5998a5) | Oct 30, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [34061efe0c](https://linux-hardware.org/?probe=34061efe0c) | Oct 25, 2022 |
| HP            | ZBook 15                    | Notebook    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| HP            | 805A                        | Desktop     | [dbe3ff75e8](https://linux-hardware.org/?probe=dbe3ff75e8) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES21434    | Notebook    | [39ff1846e3](https://linux-hardware.org/?probe=39ff1846e3) | Oct 23, 2022 |
| Fujitsu       | D2759 S26361-D2759-A13 W... | Server      | [c4c0b53877](https://linux-hardware.org/?probe=c4c0b53877) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [59f7d0820f](https://linux-hardware.org/?probe=59f7d0820f) | Oct 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [f81a40a71c](https://linux-hardware.org/?probe=f81a40a71c) | Oct 20, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [48d48d4c8e](https://linux-hardware.org/?probe=48d48d4c8e) | Oct 19, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7207f549c7](https://linux-hardware.org/?probe=7207f549c7) | Oct 18, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [dfdde1675c](https://linux-hardware.org/?probe=dfdde1675c) | Oct 17, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [2495f40df9](https://linux-hardware.org/?probe=2495f40df9) | Oct 16, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ba8acdb280](https://linux-hardware.org/?probe=ba8acdb280) | Oct 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d18c649cb6](https://linux-hardware.org/?probe=d18c649cb6) | Oct 15, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [14891d8a26](https://linux-hardware.org/?probe=14891d8a26) | Oct 13, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [682dcf0b87](https://linux-hardware.org/?probe=682dcf0b87) | Oct 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f9dc4fff88](https://linux-hardware.org/?probe=f9dc4fff88) | Oct 12, 2022 |
| Alienware     | 15 R3                       | Notebook    | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [60b02deb7f](https://linux-hardware.org/?probe=60b02deb7f) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [703ab6caa2](https://linux-hardware.org/?probe=703ab6caa2) | Oct 10, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [29f7444a6e](https://linux-hardware.org/?probe=29f7444a6e) | Oct 10, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [49fff6123f](https://linux-hardware.org/?probe=49fff6123f) | Oct 10, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [b87998cf32](https://linux-hardware.org/?probe=b87998cf32) | Oct 09, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [0272592d8e](https://linux-hardware.org/?probe=0272592d8e) | Oct 08, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [05e6a5cb26](https://linux-hardware.org/?probe=05e6a5cb26) | Oct 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d2f6a610d9](https://linux-hardware.org/?probe=d2f6a610d9) | Oct 06, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bc1f7e7d02](https://linux-hardware.org/?probe=bc1f7e7d02) | Oct 06, 2022 |
| Lenovo        | T530-28ICB                  | Desktop     | [175a71260e](https://linux-hardware.org/?probe=175a71260e) | Oct 06, 2022 |
| Google        | Banon                       | Notebook    | [269a819905](https://linux-hardware.org/?probe=269a819905) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [08a298f14e](https://linux-hardware.org/?probe=08a298f14e) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [33cb2c0dce](https://linux-hardware.org/?probe=33cb2c0dce) | Oct 03, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [12486e4114](https://linux-hardware.org/?probe=12486e4114) | Oct 03, 2022 |
| Alienware     | 15 R3                       | Notebook    | [28e4e84fb1](https://linux-hardware.org/?probe=28e4e84fb1) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0c25e7e0a0](https://linux-hardware.org/?probe=0c25e7e0a0) | Oct 02, 2022 |
| Dell          | Latitude 5480               | Notebook    | [ec9593f051](https://linux-hardware.org/?probe=ec9593f051) | Oct 01, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [2f3c79dd55](https://linux-hardware.org/?probe=2f3c79dd55) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [a64f339e70](https://linux-hardware.org/?probe=a64f339e70) | Sep 28, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [03ac8c5daa](https://linux-hardware.org/?probe=03ac8c5daa) | Sep 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0f4b7501b3](https://linux-hardware.org/?probe=0f4b7501b3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee8183722c](https://linux-hardware.org/?probe=ee8183722c) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [d603e07087](https://linux-hardware.org/?probe=d603e07087) | Sep 24, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a2ebf20cd0](https://linux-hardware.org/?probe=a2ebf20cd0) | Sep 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ac59b4138c](https://linux-hardware.org/?probe=ac59b4138c) | Sep 23, 2022 |
| HP            | 0AA0h                       | Desktop     | [5757039d29](https://linux-hardware.org/?probe=5757039d29) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [2e5553125e](https://linux-hardware.org/?probe=2e5553125e) | Sep 21, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e46ce42e90](https://linux-hardware.org/?probe=e46ce42e90) | Sep 20, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [2293724ae2](https://linux-hardware.org/?probe=2293724ae2) | Sep 19, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [d44ac0cc2a](https://linux-hardware.org/?probe=d44ac0cc2a) | Sep 19, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [8b24c3dd3b](https://linux-hardware.org/?probe=8b24c3dd3b) | Sep 19, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [09db514840](https://linux-hardware.org/?probe=09db514840) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [b2a1aea8e2](https://linux-hardware.org/?probe=b2a1aea8e2) | Sep 17, 2022 |
| ZMY           | D1500 Ver.A                 | Server      | [a99d672930](https://linux-hardware.org/?probe=a99d672930) | Sep 15, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [e620df9580](https://linux-hardware.org/?probe=e620df9580) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4a436fb179](https://linux-hardware.org/?probe=4a436fb179) | Sep 14, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [1b5e2c2e0a](https://linux-hardware.org/?probe=1b5e2c2e0a) | Sep 13, 2022 |
| ASRock        | H97M Anniversary            | Desktop     | [649c5fb453](https://linux-hardware.org/?probe=649c5fb453) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [3f56f510f8](https://linux-hardware.org/?probe=3f56f510f8) | Sep 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [940507a1ec](https://linux-hardware.org/?probe=940507a1ec) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6168b7089f](https://linux-hardware.org/?probe=6168b7089f) | Sep 11, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [4a00a1ca0b](https://linux-hardware.org/?probe=4a00a1ca0b) | Sep 10, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [bb1af3736f](https://linux-hardware.org/?probe=bb1af3736f) | Sep 10, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [40ad505314](https://linux-hardware.org/?probe=40ad505314) | Sep 10, 2022 |
| Dell          | 0TTDMJ A00                  | Desktop     | [66aa958693](https://linux-hardware.org/?probe=66aa958693) | Sep 08, 2022 |
| Dell          | Latitude E6220              | Notebook    | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| HP            | ProBook 4730s               | Notebook    | [5d0a59d50b](https://linux-hardware.org/?probe=5d0a59d50b) | Sep 05, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [3a599be2f2](https://linux-hardware.org/?probe=3a599be2f2) | Sep 03, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [22131a6ec5](https://linux-hardware.org/?probe=22131a6ec5) | Sep 03, 2022 |
| HP            | 805A                        | Desktop     | [477936d851](https://linux-hardware.org/?probe=477936d851) | Aug 30, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2fd4ef02b3](https://linux-hardware.org/?probe=2fd4ef02b3) | Aug 30, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [4b37519faf](https://linux-hardware.org/?probe=4b37519faf) | Aug 29, 2022 |
| HP            | 339A                        | Desktop     | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | Notebook    | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [a180ab604a](https://linux-hardware.org/?probe=a180ab604a) | Aug 26, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [6bcc6b550f](https://linux-hardware.org/?probe=6bcc6b550f) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| Acer          | Predator G3620              | Desktop     | [b79ed7b47b](https://linux-hardware.org/?probe=b79ed7b47b) | Aug 23, 2022 |
| HP            | Compaq 6735s                | Notebook    | [4e52bb6ecb](https://linux-hardware.org/?probe=4e52bb6ecb) | Aug 23, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [1d0c242f30](https://linux-hardware.org/?probe=1d0c242f30) | Aug 23, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [1231c2fabe](https://linux-hardware.org/?probe=1231c2fabe) | Aug 23, 2022 |
| Acer          | Enduro EUN314-51WG          | Notebook    | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| ASRock        | Z75 Pro3                    | Desktop     | [4fbe3d2710](https://linux-hardware.org/?probe=4fbe3d2710) | Aug 22, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| Alienware     | 15 R3                       | Notebook    | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| Raspberry ... | Raspberry Pi Model B Plu... | Soc         | [7deff7707e](https://linux-hardware.org/?probe=7deff7707e) | Aug 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [8834646a81](https://linux-hardware.org/?probe=8834646a81) | Aug 19, 2022 |
| Acer          | Predator PO5-600s V:1.0     | Desktop     | [6e8b922033](https://linux-hardware.org/?probe=6e8b922033) | Aug 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [eaea01215e](https://linux-hardware.org/?probe=eaea01215e) | Aug 17, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [9d82dca288](https://linux-hardware.org/?probe=9d82dca288) | Aug 17, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X501A1                      | Notebook    | [d021969767](https://linux-hardware.org/?probe=d021969767) | Aug 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| Acer          | Aspire VN7-571G             | Notebook    | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a5ef05aaff](https://linux-hardware.org/?probe=a5ef05aaff) | Aug 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [bd608fb7bc](https://linux-hardware.org/?probe=bd608fb7bc) | Aug 13, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| HP            | 805A                        | Desktop     | [c7671a704a](https://linux-hardware.org/?probe=c7671a704a) | Aug 11, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [c2acc2d803](https://linux-hardware.org/?probe=c2acc2d803) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [ea9b6a4757](https://linux-hardware.org/?probe=ea9b6a4757) | Aug 10, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [4e9256cf7f](https://linux-hardware.org/?probe=4e9256cf7f) | Aug 10, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [2539e9f908](https://linux-hardware.org/?probe=2539e9f908) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [db843c1cae](https://linux-hardware.org/?probe=db843c1cae) | Aug 07, 2022 |
| HP            | 1497                        | Desktop     | [2fe6cb5b2c](https://linux-hardware.org/?probe=2fe6cb5b2c) | Aug 07, 2022 |
| HP            | 1497                        | Desktop     | [24959f2c80](https://linux-hardware.org/?probe=24959f2c80) | Aug 07, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [0f1a9e4af2](https://linux-hardware.org/?probe=0f1a9e4af2) | Aug 06, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fa0a089121](https://linux-hardware.org/?probe=fa0a089121) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [a284074100](https://linux-hardware.org/?probe=a284074100) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [f14436327b](https://linux-hardware.org/?probe=f14436327b) | Aug 04, 2022 |
| HP            | Laptop 14-dg0xxx            | Notebook    | [365fe3e266](https://linux-hardware.org/?probe=365fe3e266) | Aug 03, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [da1731c1d2](https://linux-hardware.org/?probe=da1731c1d2) | Aug 03, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [d5e820b393](https://linux-hardware.org/?probe=d5e820b393) | Aug 03, 2022 |
| Pine Micro... | Pine64 PinePhonePro         | Phone       | [2cea7378e8](https://linux-hardware.org/?probe=2cea7378e8) | Aug 03, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [09cd376e43](https://linux-hardware.org/?probe=09cd376e43) | Aug 02, 2022 |
| HP            | Compaq 2510p                | Notebook    | [b61ccedd14](https://linux-hardware.org/?probe=b61ccedd14) | Jul 31, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [8693dca4f6](https://linux-hardware.org/?probe=8693dca4f6) | Jul 30, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [dca4c898f8](https://linux-hardware.org/?probe=dca4c898f8) | Jul 29, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [2bc22894c8](https://linux-hardware.org/?probe=2bc22894c8) | Jul 29, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ca37936b6f](https://linux-hardware.org/?probe=ca37936b6f) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| HP            | Laptop 14-dg0xxx            | Notebook    | [fa46d23eda](https://linux-hardware.org/?probe=fa46d23eda) | Jul 27, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d2eb8a032b](https://linux-hardware.org/?probe=d2eb8a032b) | Jul 26, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [70ddacf43f](https://linux-hardware.org/?probe=70ddacf43f) | Jul 25, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1578510bc0](https://linux-hardware.org/?probe=1578510bc0) | Jul 25, 2022 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | Desktop     | [cda18f8739](https://linux-hardware.org/?probe=cda18f8739) | Jul 22, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [c35f07bb03](https://linux-hardware.org/?probe=c35f07bb03) | Jul 21, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [a1cab26fa9](https://linux-hardware.org/?probe=a1cab26fa9) | Jul 21, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [b35dabeb45](https://linux-hardware.org/?probe=b35dabeb45) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [2625b243eb](https://linux-hardware.org/?probe=2625b243eb) | Jul 20, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [25728e964b](https://linux-hardware.org/?probe=25728e964b) | Jul 20, 2022 |
| ASUSTek       | Pro WS 565-ACE              | Desktop     | [9558ff01e9](https://linux-hardware.org/?probe=9558ff01e9) | Jul 20, 2022 |
| Gigabyte      | MP32-AR1-00 01010101        | Server      | [e93d3eae0d](https://linux-hardware.org/?probe=e93d3eae0d) | Jul 20, 2022 |
| HP            | G62                         | Notebook    | [bc85466c3f](https://linux-hardware.org/?probe=bc85466c3f) | Jul 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [96c65556bb](https://linux-hardware.org/?probe=96c65556bb) | Jul 18, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [e540c6e30d](https://linux-hardware.org/?probe=e540c6e30d) | Jul 18, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [a471c15853](https://linux-hardware.org/?probe=a471c15853) | Jul 17, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [34ff1068ca](https://linux-hardware.org/?probe=34ff1068ca) | Jul 14, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [27f79db974](https://linux-hardware.org/?probe=27f79db974) | Jul 13, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [f4f2c80cdd](https://linux-hardware.org/?probe=f4f2c80cdd) | Jul 09, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [57517e2dc2](https://linux-hardware.org/?probe=57517e2dc2) | Jul 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3a5fc098c4](https://linux-hardware.org/?probe=3a5fc098c4) | Jul 08, 2022 |
| Dell          | 0GM819                      | Desktop     | [3d18cc2632](https://linux-hardware.org/?probe=3d18cc2632) | Jul 08, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [a93792aef3](https://linux-hardware.org/?probe=a93792aef3) | Jul 07, 2022 |
| HUAWEI        | VLT-WX0                     | Notebook    | [9467db0d89](https://linux-hardware.org/?probe=9467db0d89) | Jul 06, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f525b5f3b0](https://linux-hardware.org/?probe=f525b5f3b0) | Jul 04, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | Notebook    | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| HP            | 829E                        | Mini pc     | [91fee1441e](https://linux-hardware.org/?probe=91fee1441e) | Jul 01, 2022 |
| HP            | 3647h                       | Desktop     | [f59774eab5](https://linux-hardware.org/?probe=f59774eab5) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | Notebook    | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [8ecea7fce7](https://linux-hardware.org/?probe=8ecea7fce7) | Jun 28, 2022 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [c62062eac9](https://linux-hardware.org/?probe=c62062eac9) | Jun 24, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f3d1eeadb3](https://linux-hardware.org/?probe=f3d1eeadb3) | Jun 23, 2022 |
| Medion        | AXA                         | All in one  | [0cbda6d693](https://linux-hardware.org/?probe=0cbda6d693) | Jun 23, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f0d321b741](https://linux-hardware.org/?probe=f0d321b741) | Jun 22, 2022 |
| Lenovo        | ThinkPad T480 20L60034MX    | Notebook    | [179d10e315](https://linux-hardware.org/?probe=179d10e315) | Jun 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a69564b477](https://linux-hardware.org/?probe=a69564b477) | Jun 17, 2022 |
| Dell          | Latitude E7440              | Notebook    | [41acc5e2ba](https://linux-hardware.org/?probe=41acc5e2ba) | Jun 17, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [139ffc0039](https://linux-hardware.org/?probe=139ffc0039) | Jun 16, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [16e086c77f](https://linux-hardware.org/?probe=16e086c77f) | Jun 16, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f339cce523](https://linux-hardware.org/?probe=f339cce523) | Jun 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [36bf4dc378](https://linux-hardware.org/?probe=36bf4dc378) | Jun 13, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [d4bfcc2d6d](https://linux-hardware.org/?probe=d4bfcc2d6d) | Jun 12, 2022 |
| Dell          | 0RW203                      | Desktop     | [d53558bc85](https://linux-hardware.org/?probe=d53558bc85) | Jun 12, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d2861687ff](https://linux-hardware.org/?probe=d2861687ff) | Jun 12, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [f2351bb361](https://linux-hardware.org/?probe=f2351bb361) | Jun 11, 2022 |
| HP            | G62                         | Notebook    | [de2464c378](https://linux-hardware.org/?probe=de2464c378) | Jun 08, 2022 |
| HP            | Elite Dragonfly Max Note... | Convertible | [3b16bdeb2c](https://linux-hardware.org/?probe=3b16bdeb2c) | Jun 06, 2022 |
| Supermicro    | X10SBA-LA                   | Desktop     | [4b46c69e08](https://linux-hardware.org/?probe=4b46c69e08) | Jun 03, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [dff99aa7e6](https://linux-hardware.org/?probe=dff99aa7e6) | May 30, 2022 |
| HP            | 1998                        | Desktop     | [48be2e4a99](https://linux-hardware.org/?probe=48be2e4a99) | May 30, 2022 |
| HP            | 1998                        | Desktop     | [d68e99102e](https://linux-hardware.org/?probe=d68e99102e) | May 29, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [6e41ef26bf](https://linux-hardware.org/?probe=6e41ef26bf) | May 29, 2022 |
| Unknown       | Unknown                     | Phone       | [63d3c9a3b6](https://linux-hardware.org/?probe=63d3c9a3b6) | May 28, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [3a472b96d3](https://linux-hardware.org/?probe=3a472b96d3) | May 27, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [7f3e3aada0](https://linux-hardware.org/?probe=7f3e3aada0) | May 27, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9430147fab](https://linux-hardware.org/?probe=9430147fab) | May 27, 2022 |
| Dell          | Latitude 3520               | Notebook    | [6c5618416d](https://linux-hardware.org/?probe=6c5618416d) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | Notebook    | [018e2a8bff](https://linux-hardware.org/?probe=018e2a8bff) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q50021MX    | Notebook    | [6d4ab67cb8](https://linux-hardware.org/?probe=6d4ab67cb8) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 81X2          | Convertible | [df65cb7a9e](https://linux-hardware.org/?probe=df65cb7a9e) | May 26, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [18ec1a6a1a](https://linux-hardware.org/?probe=18ec1a6a1a) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [1ca9184b98](https://linux-hardware.org/?probe=1ca9184b98) | May 22, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [152469abdd](https://linux-hardware.org/?probe=152469abdd) | May 22, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a84132c514](https://linux-hardware.org/?probe=a84132c514) | May 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0e42effbfb](https://linux-hardware.org/?probe=0e42effbfb) | May 17, 2022 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [d52e9e2938](https://linux-hardware.org/?probe=d52e9e2938) | May 17, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [f06eee580b](https://linux-hardware.org/?probe=f06eee580b) | May 16, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [d2e3603431](https://linux-hardware.org/?probe=d2e3603431) | May 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [244be4f232](https://linux-hardware.org/?probe=244be4f232) | May 15, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [587c1deb4c](https://linux-hardware.org/?probe=587c1deb4c) | May 15, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [7cbd29cc48](https://linux-hardware.org/?probe=7cbd29cc48) | May 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2f3b6548d0](https://linux-hardware.org/?probe=2f3b6548d0) | May 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [826dfbee64](https://linux-hardware.org/?probe=826dfbee64) | May 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| Dell          | Latitude E6330              | Notebook    | [0065ab0681](https://linux-hardware.org/?probe=0065ab0681) | May 12, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [d94b81d9d3](https://linux-hardware.org/?probe=d94b81d9d3) | May 12, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| HP            | 805F                        | Desktop     | [466bb8cc36](https://linux-hardware.org/?probe=466bb8cc36) | May 10, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [65d7984ad4](https://linux-hardware.org/?probe=65d7984ad4) | May 09, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [b4ecefaba5](https://linux-hardware.org/?probe=b4ecefaba5) | May 09, 2022 |
| Acer          | RS780HVF                    | Desktop     | [431353b969](https://linux-hardware.org/?probe=431353b969) | May 09, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [df57c0ad60](https://linux-hardware.org/?probe=df57c0ad60) | May 09, 2022 |
| MSI           | Z87M GAMING                 | Desktop     | [7e95657ad7](https://linux-hardware.org/?probe=7e95657ad7) | May 08, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [537def711a](https://linux-hardware.org/?probe=537def711a) | May 08, 2022 |
| Acer          | RS780HVF                    | Desktop     | [1f30630929](https://linux-hardware.org/?probe=1f30630929) | May 08, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [f12944a9bd](https://linux-hardware.org/?probe=f12944a9bd) | May 07, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8ecadc1bad](https://linux-hardware.org/?probe=8ecadc1bad) | May 05, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Acer          | H57M01                      | Desktop     | [180132b3e1](https://linux-hardware.org/?probe=180132b3e1) | May 03, 2022 |
| Acer          | FX58M                       | Desktop     | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [83ca73d4cd](https://linux-hardware.org/?probe=83ca73d4cd) | May 03, 2022 |
| HP            | 1589                        | Desktop     | [79df2c00dc](https://linux-hardware.org/?probe=79df2c00dc) | May 03, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [fcca76f1e5](https://linux-hardware.org/?probe=fcca76f1e5) | May 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a90e6b2be7](https://linux-hardware.org/?probe=a90e6b2be7) | Apr 30, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| Dell          | Latitude E6330              | Notebook    | [c78066bc19](https://linux-hardware.org/?probe=c78066bc19) | Apr 29, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [2e84d98937](https://linux-hardware.org/?probe=2e84d98937) | Apr 29, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [31bc958302](https://linux-hardware.org/?probe=31bc958302) | Apr 26, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [8446691cb3](https://linux-hardware.org/?probe=8446691cb3) | Apr 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2717caa7f5](https://linux-hardware.org/?probe=2717caa7f5) | Apr 25, 2022 |
| Lenovo        | ThinkPad X230 2324GA7       | Notebook    | [a5138b511d](https://linux-hardware.org/?probe=a5138b511d) | Apr 25, 2022 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [f656f0d16f](https://linux-hardware.org/?probe=f656f0d16f) | Apr 24, 2022 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [1612f46137](https://linux-hardware.org/?probe=1612f46137) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e83ffcb04f](https://linux-hardware.org/?probe=e83ffcb04f) | Apr 24, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [25e6181500](https://linux-hardware.org/?probe=25e6181500) | Apr 24, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [cd1bc2095f](https://linux-hardware.org/?probe=cd1bc2095f) | Apr 22, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [33afc70a54](https://linux-hardware.org/?probe=33afc70a54) | Apr 22, 2022 |
| Acer          | Aspire 7530G                | Notebook    | [710b429d94](https://linux-hardware.org/?probe=710b429d94) | Apr 21, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [822db71f7a](https://linux-hardware.org/?probe=822db71f7a) | Apr 21, 2022 |
| ASRock        | Z87 Extreme6                | Desktop     | [d7e24821ee](https://linux-hardware.org/?probe=d7e24821ee) | Apr 18, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | Notebook    | [5a93c8e68c](https://linux-hardware.org/?probe=5a93c8e68c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T480 20L6S93F00    | Notebook    | [b8c57e6b8a](https://linux-hardware.org/?probe=b8c57e6b8a) | Apr 14, 2022 |
| MSI           | Indio                       | Desktop     | [ca3a24d84d](https://linux-hardware.org/?probe=ca3a24d84d) | Apr 13, 2022 |
| HP            | Notebook                    | Notebook    | [24faf4835d](https://linux-hardware.org/?probe=24faf4835d) | Apr 10, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [2d4574e9fe](https://linux-hardware.org/?probe=2d4574e9fe) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [b0ffa911b5](https://linux-hardware.org/?probe=b0ffa911b5) | Apr 10, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [5264d55ce2](https://linux-hardware.org/?probe=5264d55ce2) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [1a910e93c5](https://linux-hardware.org/?probe=1a910e93c5) | Apr 09, 2022 |
| ASUSTek       | AM1M-A                      | Desktop     | [2d350f40d2](https://linux-hardware.org/?probe=2d350f40d2) | Apr 09, 2022 |
| Acer          | Batman A01                  | Desktop     | [a102f85d9d](https://linux-hardware.org/?probe=a102f85d9d) | Apr 08, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [1a1c86083e](https://linux-hardware.org/?probe=1a1c86083e) | Apr 07, 2022 |
| HP            | 18E7                        | Desktop     | [35dbcc5737](https://linux-hardware.org/?probe=35dbcc5737) | Apr 07, 2022 |
| MSI           | GV62 8RD                    | Notebook    | [2e43728adb](https://linux-hardware.org/?probe=2e43728adb) | Apr 06, 2022 |
| ASUSTek       | B150M-K                     | Desktop     | [016a08bf47](https://linux-hardware.org/?probe=016a08bf47) | Apr 04, 2022 |
| Acer          | Aspire TC-120               | Desktop     | [a92d7ab62a](https://linux-hardware.org/?probe=a92d7ab62a) | Apr 02, 2022 |
| ASRock        | B85M-ITX                    | Desktop     | [1a2849588f](https://linux-hardware.org/?probe=1a2849588f) | Apr 01, 2022 |
| HP            | 3047h                       | Desktop     | [356fac6a3a](https://linux-hardware.org/?probe=356fac6a3a) | Apr 01, 2022 |
| HP            | 3047h                       | Desktop     | [d4c9852b3c](https://linux-hardware.org/?probe=d4c9852b3c) | Apr 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [07efb6a561](https://linux-hardware.org/?probe=07efb6a561) | Apr 01, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [52598b41a6](https://linux-hardware.org/?probe=52598b41a6) | Mar 31, 2022 |
| Dell          | Latitude 5480               | Notebook    | [2d431aae25](https://linux-hardware.org/?probe=2d431aae25) | Mar 29, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [79c9d66395](https://linux-hardware.org/?probe=79c9d66395) | Mar 26, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [913cf55cc3](https://linux-hardware.org/?probe=913cf55cc3) | Mar 25, 2022 |
| Lenovo        | ThinkPad X230 2325BN8       | Notebook    | [3ad2d0f3ee](https://linux-hardware.org/?probe=3ad2d0f3ee) | Mar 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04T0P    | Notebook    | [d5b5eeffc8](https://linux-hardware.org/?probe=d5b5eeffc8) | Mar 25, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7b835e9a57](https://linux-hardware.org/?probe=7b835e9a57) | Mar 23, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [069ce018ad](https://linux-hardware.org/?probe=069ce018ad) | Mar 22, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | Notebook    | [bf87e829d7](https://linux-hardware.org/?probe=bf87e829d7) | Mar 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [78ae0419a3](https://linux-hardware.org/?probe=78ae0419a3) | Mar 14, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [ba2686174e](https://linux-hardware.org/?probe=ba2686174e) | Mar 13, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6b32e0c788](https://linux-hardware.org/?probe=6b32e0c788) | Mar 10, 2022 |
| Acer          | AO725                       | Notebook    | [70febdd28f](https://linux-hardware.org/?probe=70febdd28f) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S1MN00    | Notebook    | [0f20b300ec](https://linux-hardware.org/?probe=0f20b300ec) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| HP            | G62                         | Notebook    | [67bc301ee6](https://linux-hardware.org/?probe=67bc301ee6) | Mar 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f351d9839b](https://linux-hardware.org/?probe=f351d9839b) | Mar 09, 2022 |
| Acer          | FX58M                       | Desktop     | [7404e9534e](https://linux-hardware.org/?probe=7404e9534e) | Mar 09, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [32556e3c15](https://linux-hardware.org/?probe=32556e3c15) | Mar 09, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [2142681934](https://linux-hardware.org/?probe=2142681934) | Mar 06, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| ASUSTek       | Maximus VIII IMPACT         | Desktop     | [2e19b36624](https://linux-hardware.org/?probe=2e19b36624) | Mar 03, 2022 |
| Lenovo        | ThinkPad 13 20GJ0048MS      | Notebook    | [6590a539cf](https://linux-hardware.org/?probe=6590a539cf) | Mar 02, 2022 |
| Fujitsu       | AMILO Pi 3560               | Notebook    | [ea68b8ed21](https://linux-hardware.org/?probe=ea68b8ed21) | Mar 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [0278765ef8](https://linux-hardware.org/?probe=0278765ef8) | Feb 28, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c08be74242](https://linux-hardware.org/?probe=c08be74242) | Feb 27, 2022 |
| Acer          | Aspire XC-105               | Desktop     | [0dd55e5b26](https://linux-hardware.org/?probe=0dd55e5b26) | Feb 26, 2022 |
| ABIT          | IP35                        | Desktop     | [278dd592cc](https://linux-hardware.org/?probe=278dd592cc) | Feb 26, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [cfdffcf6ab](https://linux-hardware.org/?probe=cfdffcf6ab) | Feb 26, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [02ac351573](https://linux-hardware.org/?probe=02ac351573) | Feb 25, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [f12d1e47df](https://linux-hardware.org/?probe=f12d1e47df) | Feb 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [fa5d4846df](https://linux-hardware.org/?probe=fa5d4846df) | Feb 23, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [5fe85bba2e](https://linux-hardware.org/?probe=5fe85bba2e) | Feb 22, 2022 |
| HP            | G62                         | Notebook    | [337afde8c1](https://linux-hardware.org/?probe=337afde8c1) | Feb 21, 2022 |
| HP            | G62                         | Notebook    | [a175af3dd6](https://linux-hardware.org/?probe=a175af3dd6) | Feb 21, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [811ec775f8](https://linux-hardware.org/?probe=811ec775f8) | Feb 19, 2022 |
| powerinter... | Cepter N510-03              | Notebook    | [cd6804144d](https://linux-hardware.org/?probe=cd6804144d) | Feb 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS0U50... | Notebook    | [a114b7030f](https://linux-hardware.org/?probe=a114b7030f) | Feb 17, 2022 |
| Lenovo        | ThinkPad E14 20RA001LMX     | Notebook    | [19edff5659](https://linux-hardware.org/?probe=19edff5659) | Feb 17, 2022 |
| HP            | Compaq 6910p (GB951EA#AK... | Notebook    | [b136dd5def](https://linux-hardware.org/?probe=b136dd5def) | Feb 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [deb108070d](https://linux-hardware.org/?probe=deb108070d) | Feb 15, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [87db259935](https://linux-hardware.org/?probe=87db259935) | Feb 15, 2022 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [8b588bf90b](https://linux-hardware.org/?probe=8b588bf90b) | Feb 15, 2022 |
| Lenovo        | ThinkPad X230 23252SG       | Notebook    | [a5179b9681](https://linux-hardware.org/?probe=a5179b9681) | Feb 15, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [7cdffcccb7](https://linux-hardware.org/?probe=7cdffcccb7) | Feb 13, 2022 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [0ba38c6605](https://linux-hardware.org/?probe=0ba38c6605) | Feb 13, 2022 |
| Dell          | Latitude E5420              | Notebook    | [f016e9f3ad](https://linux-hardware.org/?probe=f016e9f3ad) | Feb 12, 2022 |
| Dell          | Latitude E5420              | Notebook    | [8843a735a0](https://linux-hardware.org/?probe=8843a735a0) | Feb 12, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [61e1bce7ae](https://linux-hardware.org/?probe=61e1bce7ae) | Feb 12, 2022 |
| ASRock        | 890FX Deluxe4               | Desktop     | [33a47b3c4b](https://linux-hardware.org/?probe=33a47b3c4b) | Feb 11, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [040550cdaa](https://linux-hardware.org/?probe=040550cdaa) | Feb 11, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [766e937263](https://linux-hardware.org/?probe=766e937263) | Feb 10, 2022 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [ba2262bba5](https://linux-hardware.org/?probe=ba2262bba5) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | Notebook    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [3d76f83751](https://linux-hardware.org/?probe=3d76f83751) | Feb 10, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [75b31509a3](https://linux-hardware.org/?probe=75b31509a3) | Feb 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [72b880911a](https://linux-hardware.org/?probe=72b880911a) | Feb 08, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [88fdd17fc6](https://linux-hardware.org/?probe=88fdd17fc6) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [22be2d64a2](https://linux-hardware.org/?probe=22be2d64a2) | Feb 06, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [e0765c9f5a](https://linux-hardware.org/?probe=e0765c9f5a) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [6160f71e77](https://linux-hardware.org/?probe=6160f71e77) | Feb 05, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [035ccaeec8](https://linux-hardware.org/?probe=035ccaeec8) | Feb 04, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [cba6a6b5a6](https://linux-hardware.org/?probe=cba6a6b5a6) | Feb 02, 2022 |
| Dell          | 051FJ8 A00                  | Desktop     | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [e83deb15fd](https://linux-hardware.org/?probe=e83deb15fd) | Jan 31, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [5f6a8cf57f](https://linux-hardware.org/?probe=5f6a8cf57f) | Jan 29, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [9ff78b6d13](https://linux-hardware.org/?probe=9ff78b6d13) | Jan 29, 2022 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f76e2b6c0f](https://linux-hardware.org/?probe=f76e2b6c0f) | Jan 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| Lenovo        | ThinkPad X390 20Q00057MX    | Notebook    | [326cb714f0](https://linux-hardware.org/?probe=326cb714f0) | Jan 27, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [a31ae712c0](https://linux-hardware.org/?probe=a31ae712c0) | Jan 26, 2022 |
| HP            | Compaq Presario CQ70        | Notebook    | [82a45a6067](https://linux-hardware.org/?probe=82a45a6067) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [ef779f5d49](https://linux-hardware.org/?probe=ef779f5d49) | Jan 26, 2022 |
| ASRock        | AB350M-HDV                  | Desktop     | [cf5823e07b](https://linux-hardware.org/?probe=cf5823e07b) | Jan 26, 2022 |
| Packard Be... | IMEDIA S3840                | Desktop     | [eff4bf09ec](https://linux-hardware.org/?probe=eff4bf09ec) | Jan 26, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [7078a1a373](https://linux-hardware.org/?probe=7078a1a373) | Jan 25, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [63d4ce1086](https://linux-hardware.org/?probe=63d4ce1086) | Jan 23, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [b9d8fc0e46](https://linux-hardware.org/?probe=b9d8fc0e46) | Jan 23, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [88049a6cee](https://linux-hardware.org/?probe=88049a6cee) | Jan 22, 2022 |
| Lenovo        | ThinkPad T430 2351AK9       | Notebook    | [19f50b09d5](https://linux-hardware.org/?probe=19f50b09d5) | Jan 21, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [8f7c57b03f](https://linux-hardware.org/?probe=8f7c57b03f) | Jan 18, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [5f904131f5](https://linux-hardware.org/?probe=5f904131f5) | Jan 18, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [f6beec1048](https://linux-hardware.org/?probe=f6beec1048) | Jan 18, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [06c4be96aa](https://linux-hardware.org/?probe=06c4be96aa) | Jan 17, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [39b90ab9c3](https://linux-hardware.org/?probe=39b90ab9c3) | Jan 17, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | Notebook    | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| HP            | 18E5                        | Desktop     | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [3417abe371](https://linux-hardware.org/?probe=3417abe371) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [caa528d6e0](https://linux-hardware.org/?probe=caa528d6e0) | Jan 15, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [3d2a67265f](https://linux-hardware.org/?probe=3d2a67265f) | Jan 15, 2022 |
| HP            | 1495                        | Desktop     | [ea7df45832](https://linux-hardware.org/?probe=ea7df45832) | Jan 14, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [c2406eee73](https://linux-hardware.org/?probe=c2406eee73) | Jan 13, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [4bbc688f9d](https://linux-hardware.org/?probe=4bbc688f9d) | Jan 13, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [e82feb71d2](https://linux-hardware.org/?probe=e82feb71d2) | Jan 12, 2022 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [0529614510](https://linux-hardware.org/?probe=0529614510) | Jan 12, 2022 |
| Toshiba       | Satellite P870              | Notebook    | [e046040d73](https://linux-hardware.org/?probe=e046040d73) | Jan 11, 2022 |
| HP            | Notebook                    | Notebook    | [0667124a5f](https://linux-hardware.org/?probe=0667124a5f) | Jan 10, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [1da9aea182](https://linux-hardware.org/?probe=1da9aea182) | Jan 10, 2022 |
| Sony          | VGN-FZ21Z                   | Notebook    | [6291085e58](https://linux-hardware.org/?probe=6291085e58) | Jan 09, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [cdf5230fdb](https://linux-hardware.org/?probe=cdf5230fdb) | Jan 09, 2022 |
| HP            | 3646h                       | Desktop     | [85edd0c1bf](https://linux-hardware.org/?probe=85edd0c1bf) | Jan 08, 2022 |
| HP            | 3646h                       | Desktop     | [616a0acd31](https://linux-hardware.org/?probe=616a0acd31) | Jan 08, 2022 |
| Sony          | VGN-FZ21Z                   | Notebook    | [c4ac286105](https://linux-hardware.org/?probe=c4ac286105) | Jan 08, 2022 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [72fa18d5dd](https://linux-hardware.org/?probe=72fa18d5dd) | Jan 08, 2022 |
| MSI           | H110M ECO                   | Desktop     | [c056a2eafa](https://linux-hardware.org/?probe=c056a2eafa) | Jan 07, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [1644301279](https://linux-hardware.org/?probe=1644301279) | Jan 07, 2022 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [6f8a6d74e4](https://linux-hardware.org/?probe=6f8a6d74e4) | Jan 07, 2022 |
| ASUSTek       | UL30A                       | Notebook    | [b2682cb5fe](https://linux-hardware.org/?probe=b2682cb5fe) | Jan 06, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | Notebook    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Acer          | WMCP78M                     | Desktop     | [250fa57c5d](https://linux-hardware.org/?probe=250fa57c5d) | Jan 05, 2022 |
| Lenovo        | ThinkPad E14 20RA001BMX     | Notebook    | [b34ccf2c06](https://linux-hardware.org/?probe=b34ccf2c06) | Jan 05, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [c28c0f7f40](https://linux-hardware.org/?probe=c28c0f7f40) | Jan 04, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [0731f1a6d9](https://linux-hardware.org/?probe=0731f1a6d9) | Jan 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [5dd20e2872](https://linux-hardware.org/?probe=5dd20e2872) | Jan 03, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [4ed85a0f7a](https://linux-hardware.org/?probe=4ed85a0f7a) | Dec 30, 2021 |
| HP            | 3397                        | Desktop     | [188bb8c669](https://linux-hardware.org/?probe=188bb8c669) | Dec 28, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | Notebook    | [25a59e69c1](https://linux-hardware.org/?probe=25a59e69c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X61 7674CT0        | Notebook    | [a5b0d0a06a](https://linux-hardware.org/?probe=a5b0d0a06a) | Dec 25, 2021 |
| Acer          | Swift SF314-52              | Notebook    | [67fb871b2f](https://linux-hardware.org/?probe=67fb871b2f) | Dec 24, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [462b93b05b](https://linux-hardware.org/?probe=462b93b05b) | Dec 20, 2021 |
| Apple         | Mac-F2238AC8                | All in one  | [4384deed19](https://linux-hardware.org/?probe=4384deed19) | Dec 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [83e6ab3542](https://linux-hardware.org/?probe=83e6ab3542) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Dell          | Latitude 5490               | Notebook    | [a9261b4529](https://linux-hardware.org/?probe=a9261b4529) | Dec 16, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [4365a457d8](https://linux-hardware.org/?probe=4365a457d8) | Dec 15, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a1c07a7e6a](https://linux-hardware.org/?probe=a1c07a7e6a) | Dec 15, 2021 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [0ca333f8b0](https://linux-hardware.org/?probe=0ca333f8b0) | Dec 15, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [002a05b1c7](https://linux-hardware.org/?probe=002a05b1c7) | Dec 14, 2021 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [81873c2912](https://linux-hardware.org/?probe=81873c2912) | Dec 14, 2021 |
| Dell          | Precision 7510              | Notebook    | [59a0d1a314](https://linux-hardware.org/?probe=59a0d1a314) | Dec 13, 2021 |
| Schenker      | XMG_APEX15_XAP15E20         | Notebook    | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| HP            | Pavilion 15                 | Notebook    | [9b61f8e080](https://linux-hardware.org/?probe=9b61f8e080) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Samsung       | 750XDA                      | Notebook    | [30d61197a1](https://linux-hardware.org/?probe=30d61197a1) | Dec 09, 2021 |
| HP            | 340 G5                      | Notebook    | [8ed2eec9b4](https://linux-hardware.org/?probe=8ed2eec9b4) | Dec 07, 2021 |
| Dell          | Latitude E6400              | Notebook    | [b8e56749b8](https://linux-hardware.org/?probe=b8e56749b8) | Dec 03, 2021 |
| Lenovo        | ThinkPad W540 20BH002NMS    | Notebook    | [52d66e95f4](https://linux-hardware.org/?probe=52d66e95f4) | Dec 01, 2021 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [bc8359d097](https://linux-hardware.org/?probe=bc8359d097) | Dec 01, 2021 |
| ASUSTek       | Z97-C                       | Desktop     | [3284718afd](https://linux-hardware.org/?probe=3284718afd) | Dec 01, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [493153bf7c](https://linux-hardware.org/?probe=493153bf7c) | Nov 30, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [b98f644a91](https://linux-hardware.org/?probe=b98f644a91) | Nov 30, 2021 |
| HP            | 3646h                       | Desktop     | [e7069f8a3b](https://linux-hardware.org/?probe=e7069f8a3b) | Nov 29, 2021 |
| HP            | 3646h                       | Desktop     | [a46d638004](https://linux-hardware.org/?probe=a46d638004) | Nov 29, 2021 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [71d6a80bd1](https://linux-hardware.org/?probe=71d6a80bd1) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6591fce926](https://linux-hardware.org/?probe=6591fce926) | Nov 27, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [9ae82b251b](https://linux-hardware.org/?probe=9ae82b251b) | Nov 26, 2021 |
| Intel         | NUC8BEB J72688-305          | Mini pc     | [65d49ae483](https://linux-hardware.org/?probe=65d49ae483) | Nov 26, 2021 |
| Apple         | MacBookAir6,2               | Notebook    | [c5ba70d401](https://linux-hardware.org/?probe=c5ba70d401) | Nov 24, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [3355d6fd50](https://linux-hardware.org/?probe=3355d6fd50) | Nov 24, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [9b0bfd9c19](https://linux-hardware.org/?probe=9b0bfd9c19) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [f62619c698](https://linux-hardware.org/?probe=f62619c698) | Nov 24, 2021 |
| Acer          | WMCP78M                     | Desktop     | [5930f530bb](https://linux-hardware.org/?probe=5930f530bb) | Nov 24, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [9476bb5e05](https://linux-hardware.org/?probe=9476bb5e05) | Nov 24, 2021 |
| HP            | 3647h                       | Desktop     | [e3d0601f0b](https://linux-hardware.org/?probe=e3d0601f0b) | Nov 23, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [613686da3f](https://linux-hardware.org/?probe=613686da3f) | Nov 22, 2021 |
| HP            | 8433 11                     | Desktop     | [e88c3d4a94](https://linux-hardware.org/?probe=e88c3d4a94) | Nov 22, 2021 |
| HP            | EliteBook 835 G7 Noteboo... | Notebook    | [cdf3297bef](https://linux-hardware.org/?probe=cdf3297bef) | Nov 21, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [89c87a0f8c](https://linux-hardware.org/?probe=89c87a0f8c) | Nov 21, 2021 |
| Google        | Relm                        | Notebook    | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [11710ca51d](https://linux-hardware.org/?probe=11710ca51d) | Nov 21, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [3ea389d8ff](https://linux-hardware.org/?probe=3ea389d8ff) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| Lenovo        | ThinkStation S20 4157FY2    | Desktop     | [b05be2384d](https://linux-hardware.org/?probe=b05be2384d) | Nov 20, 2021 |
| Dell          | Latitude E6420              | Notebook    | [2e2b68b190](https://linux-hardware.org/?probe=2e2b68b190) | Nov 20, 2021 |
| HP            | Pavilion 17                 | Notebook    | [a633bbd978](https://linux-hardware.org/?probe=a633bbd978) | Nov 20, 2021 |
| Acer          | Aspire A715-42G             | Notebook    | [19f48288ec](https://linux-hardware.org/?probe=19f48288ec) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0581432da](https://linux-hardware.org/?probe=d0581432da) | Nov 20, 2021 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [646919d578](https://linux-hardware.org/?probe=646919d578) | Nov 20, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [972f96ba1d](https://linux-hardware.org/?probe=972f96ba1d) | Nov 17, 2021 |
| Lenovo        | ThinkPad T530 24341G0       | Notebook    | [0dcfa8bdc7](https://linux-hardware.org/?probe=0dcfa8bdc7) | Nov 17, 2021 |
| Dell          | Latitude 7420               | Notebook    | [52bd94ce90](https://linux-hardware.org/?probe=52bd94ce90) | Nov 17, 2021 |
| HP            | EliteBook 8560w             | Notebook    | [5bed28d52e](https://linux-hardware.org/?probe=5bed28d52e) | Nov 15, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [da8846a5fd](https://linux-hardware.org/?probe=da8846a5fd) | Nov 14, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [d004277425](https://linux-hardware.org/?probe=d004277425) | Nov 14, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [1d72b572ac](https://linux-hardware.org/?probe=1d72b572ac) | Nov 14, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | Notebook    | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| ASUSTek       | N53SN                       | Notebook    | [438a1236fb](https://linux-hardware.org/?probe=438a1236fb) | Nov 11, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | Notebook    | [7a1824b26a](https://linux-hardware.org/?probe=7a1824b26a) | Nov 11, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| HP            | 1495                        | Desktop     | [d66a2a8cf5](https://linux-hardware.org/?probe=d66a2a8cf5) | Nov 10, 2021 |
| Lenovo        | Kabini CRB 31900003 STD     | Desktop     | [4d94fd8ba6](https://linux-hardware.org/?probe=4d94fd8ba6) | Nov 10, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [d2d03753ee](https://linux-hardware.org/?probe=d2d03753ee) | Nov 09, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [b98565dc8e](https://linux-hardware.org/?probe=b98565dc8e) | Nov 09, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [224597688f](https://linux-hardware.org/?probe=224597688f) | Nov 09, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [0aeea3a3c9](https://linux-hardware.org/?probe=0aeea3a3c9) | Nov 09, 2021 |
| HP            | 1495                        | Desktop     | [22bbd228cb](https://linux-hardware.org/?probe=22bbd228cb) | Nov 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [536b4200f8](https://linux-hardware.org/?probe=536b4200f8) | Nov 07, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [33a5ffbf9a](https://linux-hardware.org/?probe=33a5ffbf9a) | Nov 07, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [748d879ed2](https://linux-hardware.org/?probe=748d879ed2) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [8cf09365a4](https://linux-hardware.org/?probe=8cf09365a4) | Nov 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [10faa36c81](https://linux-hardware.org/?probe=10faa36c81) | Nov 06, 2021 |
| ASUSTek       | A_F_K20CE                   | Desktop     | [a40335233e](https://linux-hardware.org/?probe=a40335233e) | Nov 04, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [32b0b7b787](https://linux-hardware.org/?probe=32b0b7b787) | Nov 04, 2021 |
| ABIT          | AI7                         | Desktop     | [75f77dabe1](https://linux-hardware.org/?probe=75f77dabe1) | Nov 03, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [ae1af68eae](https://linux-hardware.org/?probe=ae1af68eae) | Nov 03, 2021 |
| Samsung       | R530/R730                   | Notebook    | [a62fb59972](https://linux-hardware.org/?probe=a62fb59972) | Nov 03, 2021 |
| Intel         | S1200RP G62251-405          | Server      | [798cf3cc96](https://linux-hardware.org/?probe=798cf3cc96) | Nov 02, 2021 |
| ASUSTek       | M2N-E                       | Desktop     | [dfa80f4b9f](https://linux-hardware.org/?probe=dfa80f4b9f) | Oct 31, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [b4c3816a33](https://linux-hardware.org/?probe=b4c3816a33) | Oct 30, 2021 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [1217a94f61](https://linux-hardware.org/?probe=1217a94f61) | Oct 26, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [e10152abc8](https://linux-hardware.org/?probe=e10152abc8) | Oct 25, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [0f6daccd63](https://linux-hardware.org/?probe=0f6daccd63) | Oct 25, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [e74dc83f0a](https://linux-hardware.org/?probe=e74dc83f0a) | Oct 24, 2021 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [5b429fd560](https://linux-hardware.org/?probe=5b429fd560) | Oct 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [477512ba5c](https://linux-hardware.org/?probe=477512ba5c) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [c487ba6138](https://linux-hardware.org/?probe=c487ba6138) | Oct 22, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| HP            | Compaq 6735s                | Notebook    | [25c73d7c4d](https://linux-hardware.org/?probe=25c73d7c4d) | Oct 20, 2021 |
| HP            | 158B                        | Desktop     | [24399f4e69](https://linux-hardware.org/?probe=24399f4e69) | Oct 20, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [594815bb9d](https://linux-hardware.org/?probe=594815bb9d) | Oct 17, 2021 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [d89008ef64](https://linux-hardware.org/?probe=d89008ef64) | Oct 16, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [8961245abb](https://linux-hardware.org/?probe=8961245abb) | Oct 15, 2021 |
| Acer          | Aspire 7530G                | Notebook    | [09694e2816](https://linux-hardware.org/?probe=09694e2816) | Oct 15, 2021 |
| HP            | ProBook 655 G1              | Notebook    | [5a67ea75fe](https://linux-hardware.org/?probe=5a67ea75fe) | Oct 14, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [072dab3e8c](https://linux-hardware.org/?probe=072dab3e8c) | Oct 14, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [18263076ea](https://linux-hardware.org/?probe=18263076ea) | Oct 14, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [cf747bee4e](https://linux-hardware.org/?probe=cf747bee4e) | Oct 13, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [e8ad89cb87](https://linux-hardware.org/?probe=e8ad89cb87) | Oct 12, 2021 |
| HP            | 21D0                        | Desktop     | [4cee9a5c3d](https://linux-hardware.org/?probe=4cee9a5c3d) | Oct 11, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [7fbd3218a8](https://linux-hardware.org/?probe=7fbd3218a8) | Oct 11, 2021 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [818fe93a6d](https://linux-hardware.org/?probe=818fe93a6d) | Oct 10, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [319f2002de](https://linux-hardware.org/?probe=319f2002de) | Oct 09, 2021 |
| Dell          | 0YC523                      | Desktop     | [cf8d063deb](https://linux-hardware.org/?probe=cf8d063deb) | Oct 09, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [a9d87f6d4e](https://linux-hardware.org/?probe=a9d87f6d4e) | Oct 08, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | Notebook    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [2fe4152b53](https://linux-hardware.org/?probe=2fe4152b53) | Oct 07, 2021 |
| Acer          | Swift SF314-54              | Notebook    | [26501031e8](https://linux-hardware.org/?probe=26501031e8) | Oct 07, 2021 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [28eb3733ca](https://linux-hardware.org/?probe=28eb3733ca) | Oct 06, 2021 |
| Fujitsu       | D3031 S26361-D3031-A100-... | Server      | [8028a9757c](https://linux-hardware.org/?probe=8028a9757c) | Oct 06, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [e7742aa472](https://linux-hardware.org/?probe=e7742aa472) | Oct 03, 2021 |
| Fujitsu       | D3003-A1 S26361-D3003-A1    | Desktop     | [0c5e4a2345](https://linux-hardware.org/?probe=0c5e4a2345) | Oct 02, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [31df81c76d](https://linux-hardware.org/?probe=31df81c76d) | Sep 30, 2021 |
| HP            | 0AACh                       | Desktop     | [37766217ae](https://linux-hardware.org/?probe=37766217ae) | Sep 30, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [ba4f1bda7d](https://linux-hardware.org/?probe=ba4f1bda7d) | Sep 30, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [8fa77435f7](https://linux-hardware.org/?probe=8fa77435f7) | Sep 29, 2021 |
| Medion        | B460H6-EM                   | Desktop     | [b461764429](https://linux-hardware.org/?probe=b461764429) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [171fc1cb46](https://linux-hardware.org/?probe=171fc1cb46) | Sep 27, 2021 |
| Acer          | Aspire 5738                 | Notebook    | [f9373d8ba5](https://linux-hardware.org/?probe=f9373d8ba5) | Sep 27, 2021 |
| MSI           | MS-7211                     | Desktop     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [89783ad217](https://linux-hardware.org/?probe=89783ad217) | Sep 24, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [867138c338](https://linux-hardware.org/?probe=867138c338) | Sep 22, 2021 |
| Lenovo        | ThinkPad X230 204016Z1ZS    | Notebook    | [eb1d7abffc](https://linux-hardware.org/?probe=eb1d7abffc) | Sep 21, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | Desktop     | [7ded59f42f](https://linux-hardware.org/?probe=7ded59f42f) | Sep 21, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [a4488fd2fe](https://linux-hardware.org/?probe=a4488fd2fe) | Sep 19, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [f9509414bc](https://linux-hardware.org/?probe=f9509414bc) | Sep 18, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [506a3682b9](https://linux-hardware.org/?probe=506a3682b9) | Sep 15, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [badf707f13](https://linux-hardware.org/?probe=badf707f13) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c8e465fcb0](https://linux-hardware.org/?probe=c8e465fcb0) | Sep 14, 2021 |
| Unknown       | Unknown                     | Notebook    | [6670bba1d8](https://linux-hardware.org/?probe=6670bba1d8) | Sep 13, 2021 |
| Unknown       | Unknown                     | Notebook    | [94e64b5b30](https://linux-hardware.org/?probe=94e64b5b30) | Sep 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [0a2430ae78](https://linux-hardware.org/?probe=0a2430ae78) | Sep 10, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [7fdf917680](https://linux-hardware.org/?probe=7fdf917680) | Sep 09, 2021 |
| Dell          | Latitude 7420               | Notebook    | [225b6a0d52](https://linux-hardware.org/?probe=225b6a0d52) | Sep 09, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | Notebook    | [d05cb87743](https://linux-hardware.org/?probe=d05cb87743) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [00e399c8d4](https://linux-hardware.org/?probe=00e399c8d4) | Sep 07, 2021 |
| Dell          | Latitude E6430              | Notebook    | [e02c871576](https://linux-hardware.org/?probe=e02c871576) | Sep 06, 2021 |
| Dell          | Latitude E6430              | Notebook    | [5d2627b08e](https://linux-hardware.org/?probe=5d2627b08e) | Sep 06, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [78fc85808c](https://linux-hardware.org/?probe=78fc85808c) | Sep 05, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [22390a295d](https://linux-hardware.org/?probe=22390a295d) | Sep 04, 2021 |
| Fujitsu       | LIFEBOOK U9310              | Notebook    | [48113d6636](https://linux-hardware.org/?probe=48113d6636) | Sep 02, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [7467c9452c](https://linux-hardware.org/?probe=7467c9452c) | Sep 01, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [08ad3775b8](https://linux-hardware.org/?probe=08ad3775b8) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | Notebook    | [8e46956f05](https://linux-hardware.org/?probe=8e46956f05) | Aug 31, 2021 |
| Acer          | Nitro AN517-52              | Notebook    | [d534aba928](https://linux-hardware.org/?probe=d534aba928) | Aug 31, 2021 |
| Lenovo        | ThinkPad T420 4180WDN       | Notebook    | [8512904445](https://linux-hardware.org/?probe=8512904445) | Aug 29, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [93e2baa57a](https://linux-hardware.org/?probe=93e2baa57a) | Aug 29, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [b8aadba448](https://linux-hardware.org/?probe=b8aadba448) | Aug 28, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [adfa074262](https://linux-hardware.org/?probe=adfa074262) | Aug 28, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [f15a7392b9](https://linux-hardware.org/?probe=f15a7392b9) | Aug 27, 2021 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [bee6b88bab](https://linux-hardware.org/?probe=bee6b88bab) | Aug 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [fa40b359a1](https://linux-hardware.org/?probe=fa40b359a1) | Aug 27, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [cf76a62cf4](https://linux-hardware.org/?probe=cf76a62cf4) | Aug 26, 2021 |
| Fujitsu Si... | AMILO Li3910                | Notebook    | [4198aeb0a0](https://linux-hardware.org/?probe=4198aeb0a0) | Aug 26, 2021 |
| Dell          | Latitude 5480               | Notebook    | [3374e57369](https://linux-hardware.org/?probe=3374e57369) | Aug 25, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [fe8aa54fcd](https://linux-hardware.org/?probe=fe8aa54fcd) | Aug 25, 2021 |
| HP            | Compaq 8710w (GC124EA#AK... | Notebook    | [d7475c57ca](https://linux-hardware.org/?probe=d7475c57ca) | Aug 24, 2021 |
| HP            | ProBook 6360b               | Notebook    | [f8a9a512b2](https://linux-hardware.org/?probe=f8a9a512b2) | Aug 24, 2021 |
| HP            | ProBook 6360b               | Notebook    | [beb76e16b5](https://linux-hardware.org/?probe=beb76e16b5) | Aug 24, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [bf921c6ff6](https://linux-hardware.org/?probe=bf921c6ff6) | Aug 23, 2021 |
| Dell          | Latitude 7490               | Notebook    | [b4759deb9a](https://linux-hardware.org/?probe=b4759deb9a) | Aug 21, 2021 |
| Acer          | RS780HVF                    | Desktop     | [f051228785](https://linux-hardware.org/?probe=f051228785) | Aug 21, 2021 |
| HP            | EliteBook 8560p             | Notebook    | [97a8f28916](https://linux-hardware.org/?probe=97a8f28916) | Aug 21, 2021 |
| HP            | 255 G1                      | Notebook    | [4998946adc](https://linux-hardware.org/?probe=4998946adc) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [33bfc09a3a](https://linux-hardware.org/?probe=33bfc09a3a) | Aug 17, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [78377f3635](https://linux-hardware.org/?probe=78377f3635) | Aug 17, 2021 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [e91d03b0c4](https://linux-hardware.org/?probe=e91d03b0c4) | Aug 17, 2021 |
| Dell          | Latitude E6430              | Notebook    | [afe966ff62](https://linux-hardware.org/?probe=afe966ff62) | Aug 17, 2021 |
| Dell          | Latitude E6500              | Notebook    | [a707e64d52](https://linux-hardware.org/?probe=a707e64d52) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [8bf626f6b3](https://linux-hardware.org/?probe=8bf626f6b3) | Aug 15, 2021 |
| Acer          | RS780HVF                    | Desktop     | [32c3b00b51](https://linux-hardware.org/?probe=32c3b00b51) | Aug 14, 2021 |
| Acer          | RS780HVF                    | Desktop     | [858844ae39](https://linux-hardware.org/?probe=858844ae39) | Aug 14, 2021 |
| Acer          | Predator G3-710             | Desktop     | [bc8ec0cacc](https://linux-hardware.org/?probe=bc8ec0cacc) | Aug 14, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [b656e3aec4](https://linux-hardware.org/?probe=b656e3aec4) | Aug 14, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [e302074e5e](https://linux-hardware.org/?probe=e302074e5e) | Aug 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [11f9ccb3ad](https://linux-hardware.org/?probe=11f9ccb3ad) | Aug 13, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | Notebook    | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [21b619d91b](https://linux-hardware.org/?probe=21b619d91b) | Aug 11, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| Apple         | Mac-F2268CC8                | All in one  | [33a532dde2](https://linux-hardware.org/?probe=33a532dde2) | Aug 09, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [8d464633db](https://linux-hardware.org/?probe=8d464633db) | Aug 08, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [bd3d1ed844](https://linux-hardware.org/?probe=bd3d1ed844) | Aug 08, 2021 |
| Lenovo        | ThinkPad X270 20HMS70400    | Notebook    | [6b647baf7c](https://linux-hardware.org/?probe=6b647baf7c) | Aug 07, 2021 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [ab5514ae70](https://linux-hardware.org/?probe=ab5514ae70) | Aug 06, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [779374b300](https://linux-hardware.org/?probe=779374b300) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | Notebook    | [47fca1c82c](https://linux-hardware.org/?probe=47fca1c82c) | Aug 05, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [a5d694843c](https://linux-hardware.org/?probe=a5d694843c) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 2518A3G       | Notebook    | [0297e70b90](https://linux-hardware.org/?probe=0297e70b90) | Aug 04, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [ec6b248ebe](https://linux-hardware.org/?probe=ec6b248ebe) | Aug 03, 2021 |
| ASRock        | 939A785GMH/128M             | Desktop     | [fe09c8fdc1](https://linux-hardware.org/?probe=fe09c8fdc1) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440p 20AN007FM... | Notebook    | [ba75506849](https://linux-hardware.org/?probe=ba75506849) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [d6735c5f18](https://linux-hardware.org/?probe=d6735c5f18) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [734237b1dc](https://linux-hardware.org/?probe=734237b1dc) | Aug 02, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9ce0842819](https://linux-hardware.org/?probe=9ce0842819) | Aug 02, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0451bc276f](https://linux-hardware.org/?probe=0451bc276f) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [754750effc](https://linux-hardware.org/?probe=754750effc) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0f19cc3c0e](https://linux-hardware.org/?probe=0f19cc3c0e) | Jul 31, 2021 |
| ASUSTek       | P5K-VM                      | Desktop     | [1b2a02afbe](https://linux-hardware.org/?probe=1b2a02afbe) | Jul 31, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [abb1e8ea82](https://linux-hardware.org/?probe=abb1e8ea82) | Jul 31, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [6e097e987f](https://linux-hardware.org/?probe=6e097e987f) | Jul 29, 2021 |
| HP            | 8437                        | Desktop     | [06f61b9a3f](https://linux-hardware.org/?probe=06f61b9a3f) | Jul 27, 2021 |
| HP            | 8437                        | Desktop     | [3e06775292](https://linux-hardware.org/?probe=3e06775292) | Jul 27, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Fujitsu       | LIFEBOOK A530               | Notebook    | [643094a68a](https://linux-hardware.org/?probe=643094a68a) | Jul 26, 2021 |
| Acer          | AO725                       | Notebook    | [4e27f519f7](https://linux-hardware.org/?probe=4e27f519f7) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| Sony          | VPCEH3D0E                   | Notebook    | [2d04f2e0e8](https://linux-hardware.org/?probe=2d04f2e0e8) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| HP            | 8437                        | Desktop     | [0764df2f0a](https://linux-hardware.org/?probe=0764df2f0a) | Jul 24, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [2c81844355](https://linux-hardware.org/?probe=2c81844355) | Jul 23, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [6863bea30a](https://linux-hardware.org/?probe=6863bea30a) | Jul 23, 2021 |
| ASRock        | 939A785GMH/128M             | Desktop     | [f363c1063a](https://linux-hardware.org/?probe=f363c1063a) | Jul 22, 2021 |
| Gigabyte      | Z270X-Gaming K5             | Desktop     | [384c090a20](https://linux-hardware.org/?probe=384c090a20) | Jul 22, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QTS0... | Notebook    | [550f9db7cd](https://linux-hardware.org/?probe=550f9db7cd) | Jul 22, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [99b906c497](https://linux-hardware.org/?probe=99b906c497) | Jul 21, 2021 |
| Dell          | 0GH911                      | Desktop     | [2aa93c89cd](https://linux-hardware.org/?probe=2aa93c89cd) | Jul 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Dell          | 0VHWTR A01                  | Desktop     | [5116710fe0](https://linux-hardware.org/?probe=5116710fe0) | Jul 20, 2021 |
| HP            | 802F                        | Desktop     | [469561ff27](https://linux-hardware.org/?probe=469561ff27) | Jul 20, 2021 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [4f9f3cbb83](https://linux-hardware.org/?probe=4f9f3cbb83) | Jul 18, 2021 |
| ASUSTek       | NARRA2                      | Desktop     | [e7e7f905c7](https://linux-hardware.org/?probe=e7e7f905c7) | Jul 17, 2021 |
| ASUSTek       | NARRA2                      | Desktop     | [40f65831a3](https://linux-hardware.org/?probe=40f65831a3) | Jul 17, 2021 |
| MSI           | GS60 2PC Ghost              | Notebook    | [cf537038dd](https://linux-hardware.org/?probe=cf537038dd) | Jul 17, 2021 |
| Dell          | Latitude E7470              | Notebook    | [8c32d73d55](https://linux-hardware.org/?probe=8c32d73d55) | Jul 16, 2021 |
| Dell          | Latitude E7470              | Notebook    | [22583cadb6](https://linux-hardware.org/?probe=22583cadb6) | Jul 14, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [532e266dcb](https://linux-hardware.org/?probe=532e266dcb) | Jul 13, 2021 |
| Acer          | Swift SF515-51T             | Notebook    | [f5ec156890](https://linux-hardware.org/?probe=f5ec156890) | Jul 12, 2021 |
| Samsung       | R530/R730                   | Notebook    | [103edb36d2](https://linux-hardware.org/?probe=103edb36d2) | Jul 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d52de582e8](https://linux-hardware.org/?probe=d52de582e8) | Jul 10, 2021 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [517a612c58](https://linux-hardware.org/?probe=517a612c58) | Jul 10, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [9f1b7a37f2](https://linux-hardware.org/?probe=9f1b7a37f2) | Jul 07, 2021 |
| Dell          | G7 7700                     | Notebook    | [6fc41408bf](https://linux-hardware.org/?probe=6fc41408bf) | Jul 07, 2021 |
| Pegatron      | 2AB6                        | Desktop     | [d5eb8c32fb](https://linux-hardware.org/?probe=d5eb8c32fb) | Jul 06, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [557af42b3d](https://linux-hardware.org/?probe=557af42b3d) | Jul 03, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | Notebook    | [def9f42f6c](https://linux-hardware.org/?probe=def9f42f6c) | Jul 02, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [cbb60edb8c](https://linux-hardware.org/?probe=cbb60edb8c) | Jul 02, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [26a655c4b4](https://linux-hardware.org/?probe=26a655c4b4) | Jul 02, 2021 |
| Dell          | Precision 5540              | Notebook    | [a685a9c5bb](https://linux-hardware.org/?probe=a685a9c5bb) | Jun 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | Notebook    | [e2743844ad](https://linux-hardware.org/?probe=e2743844ad) | Jun 29, 2021 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [2043830384](https://linux-hardware.org/?probe=2043830384) | Jun 26, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [39f8c7f885](https://linux-hardware.org/?probe=39f8c7f885) | Jun 26, 2021 |
| ASUSTek       | VivoBook E14 E402YA_R417... | Notebook    | [110b313bc0](https://linux-hardware.org/?probe=110b313bc0) | Jun 25, 2021 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [52199864f7](https://linux-hardware.org/?probe=52199864f7) | Jun 24, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e966d318da](https://linux-hardware.org/?probe=e966d318da) | Jun 23, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [7767a1cde7](https://linux-hardware.org/?probe=7767a1cde7) | Jun 23, 2021 |
| Dell          | Precision 5550              | Notebook    | [646d84cc95](https://linux-hardware.org/?probe=646d84cc95) | Jun 23, 2021 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [fa3749c0c0](https://linux-hardware.org/?probe=fa3749c0c0) | Jun 22, 2021 |
| IBM           | ThinkPad T43 2668F7G        | Notebook    | [93c8e53b04](https://linux-hardware.org/?probe=93c8e53b04) | Jun 15, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [8ec235f1f1](https://linux-hardware.org/?probe=8ec235f1f1) | Jun 13, 2021 |
| Timi          | RedmiBook 13 R              | Notebook    | [ce648ba480](https://linux-hardware.org/?probe=ce648ba480) | Jun 12, 2021 |
| Dell          | 0GH911                      | Desktop     | [3d8aec55af](https://linux-hardware.org/?probe=3d8aec55af) | Jun 10, 2021 |
| HP            | Compaq 8510p                | Notebook    | [c371bbdff4](https://linux-hardware.org/?probe=c371bbdff4) | Jun 09, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [54b62ad499](https://linux-hardware.org/?probe=54b62ad499) | Jun 08, 2021 |
| ASUSTek       | K53U                        | Notebook    | [3acb45024a](https://linux-hardware.org/?probe=3acb45024a) | Jun 08, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [e0db4d0875](https://linux-hardware.org/?probe=e0db4d0875) | Jun 08, 2021 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | Notebook    | [3764e87d16](https://linux-hardware.org/?probe=3764e87d16) | Jun 07, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [493278d567](https://linux-hardware.org/?probe=493278d567) | Jun 05, 2021 |
| ASRockRack    | B450D4U-V1L                 | Desktop     | [49a0eec9f5](https://linux-hardware.org/?probe=49a0eec9f5) | Jun 05, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [a750453ba5](https://linux-hardware.org/?probe=a750453ba5) | Jun 04, 2021 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [421fa035ee](https://linux-hardware.org/?probe=421fa035ee) | Jun 03, 2021 |
| Dell          | Latitude E7470              | Notebook    | [6be76778ae](https://linux-hardware.org/?probe=6be76778ae) | Jun 03, 2021 |
| Gigabyte      | B360HD3PLM-CF               | Desktop     | [a434845c16](https://linux-hardware.org/?probe=a434845c16) | Jun 03, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [baad40baaa](https://linux-hardware.org/?probe=baad40baaa) | Jun 01, 2021 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [ef97789a6a](https://linux-hardware.org/?probe=ef97789a6a) | May 27, 2021 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [a266b8dd81](https://linux-hardware.org/?probe=a266b8dd81) | May 27, 2021 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [30e8995988](https://linux-hardware.org/?probe=30e8995988) | May 27, 2021 |
| HP            | Compaq 8510p                | Notebook    | [7e17cf2706](https://linux-hardware.org/?probe=7e17cf2706) | May 26, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [541b3e9cba](https://linux-hardware.org/?probe=541b3e9cba) | May 25, 2021 |
| MSI           | Z370 PC PRO                 | Desktop     | [ddfe32e6ab](https://linux-hardware.org/?probe=ddfe32e6ab) | May 25, 2021 |
| Acer          | Aspire 8950G                | Notebook    | [d65fb86955](https://linux-hardware.org/?probe=d65fb86955) | May 22, 2021 |
| ASUSTek       | P7P55D EVO                  | Desktop     | [66c62dc8f8](https://linux-hardware.org/?probe=66c62dc8f8) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [1b1a173884](https://linux-hardware.org/?probe=1b1a173884) | May 22, 2021 |
| HP            | 8433 11                     | Desktop     | [8670420e76](https://linux-hardware.org/?probe=8670420e76) | May 21, 2021 |
| HP            | 350 G1                      | Notebook    | [949ae1ce88](https://linux-hardware.org/?probe=949ae1ce88) | May 20, 2021 |
| ASRock        | X99M Extreme4               | Desktop     | [fba004a752](https://linux-hardware.org/?probe=fba004a752) | May 20, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [60eb674c8f](https://linux-hardware.org/?probe=60eb674c8f) | May 19, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [fa879ee1d2](https://linux-hardware.org/?probe=fa879ee1d2) | May 19, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [249ab0aa24](https://linux-hardware.org/?probe=249ab0aa24) | May 19, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [09351c4654](https://linux-hardware.org/?probe=09351c4654) | May 18, 2021 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [d75aff5a0a](https://linux-hardware.org/?probe=d75aff5a0a) | May 16, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [8b2100d9ad](https://linux-hardware.org/?probe=8b2100d9ad) | May 14, 2021 |
| HP            | EliteBook 2170p             | Notebook    | [6e4a5f9c76](https://linux-hardware.org/?probe=6e4a5f9c76) | May 13, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [d125abf69e](https://linux-hardware.org/?probe=d125abf69e) | May 12, 2021 |
| ASRock        | Z77 Pro3                    | Desktop     | [a981f9a0c5](https://linux-hardware.org/?probe=a981f9a0c5) | May 12, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ab2366fd14](https://linux-hardware.org/?probe=ab2366fd14) | May 11, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [714a70d40a](https://linux-hardware.org/?probe=714a70d40a) | May 07, 2021 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [4482a1fb69](https://linux-hardware.org/?probe=4482a1fb69) | May 06, 2021 |
| ASUSTek       | UN45H                       | Desktop     | [efc8ac4c79](https://linux-hardware.org/?probe=efc8ac4c79) | May 06, 2021 |
| ASRock        | Z77 Pro3                    | Desktop     | [3ea8d93c76](https://linux-hardware.org/?probe=3ea8d93c76) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [a32714d409](https://linux-hardware.org/?probe=a32714d409) | May 05, 2021 |
| Dell          | Latitude 7400               | Notebook    | [eb8ca2d9d2](https://linux-hardware.org/?probe=eb8ca2d9d2) | May 05, 2021 |
| Dell          | Latitude E7270              | Notebook    | [6708f53385](https://linux-hardware.org/?probe=6708f53385) | May 04, 2021 |
| HP            | 3647h                       | Desktop     | [bd39210291](https://linux-hardware.org/?probe=bd39210291) | May 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [9482db99b9](https://linux-hardware.org/?probe=9482db99b9) | May 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [4af6233f97](https://linux-hardware.org/?probe=4af6233f97) | May 03, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [ef52974aaf](https://linux-hardware.org/?probe=ef52974aaf) | May 03, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [1c94c5b005](https://linux-hardware.org/?probe=1c94c5b005) | May 03, 2021 |
| Intel         | NUC7i7DNB J83500-205        | Mini pc     | [9eb409c988](https://linux-hardware.org/?probe=9eb409c988) | May 02, 2021 |
| MSI           | 2A9C                        | Desktop     | [fbb37a1ceb](https://linux-hardware.org/?probe=fbb37a1ceb) | May 02, 2021 |
| MSI           | 2A9C                        | Desktop     | [1b4573b9c5](https://linux-hardware.org/?probe=1b4573b9c5) | May 02, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [4ab0e6b099](https://linux-hardware.org/?probe=4ab0e6b099) | May 01, 2021 |
| Supermicro    | A2SDi-4C-HLN4F              | Server      | [40e07b4dad](https://linux-hardware.org/?probe=40e07b4dad) | Apr 26, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [93eb4a6a39](https://linux-hardware.org/?probe=93eb4a6a39) | Apr 24, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [470be454f6](https://linux-hardware.org/?probe=470be454f6) | Apr 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c586a3a771](https://linux-hardware.org/?probe=c586a3a771) | Apr 20, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [7e5ffea0b6](https://linux-hardware.org/?probe=7e5ffea0b6) | Apr 20, 2021 |
| Lenovo        | B70-80 80MR                 | Notebook    | [edef8dfd8b](https://linux-hardware.org/?probe=edef8dfd8b) | Apr 19, 2021 |
| HP            | 1998                        | Desktop     | [9bb6ae0565](https://linux-hardware.org/?probe=9bb6ae0565) | Apr 18, 2021 |
| ZOTAC         | ZBOX EN970                  | Mini pc     | [6a0c5e5bda](https://linux-hardware.org/?probe=6a0c5e5bda) | Apr 18, 2021 |
| ASRock        | Z87 Extreme6                | Desktop     | [6ac1485bc6](https://linux-hardware.org/?probe=6ac1485bc6) | Apr 17, 2021 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [d01dac7a8f](https://linux-hardware.org/?probe=d01dac7a8f) | Apr 16, 2021 |
| Lenovo        | B50-45 80F0                 | Notebook    | [0558c9e99e](https://linux-hardware.org/?probe=0558c9e99e) | Apr 16, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [7ca0cd3696](https://linux-hardware.org/?probe=7ca0cd3696) | Apr 15, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [3274addf89](https://linux-hardware.org/?probe=3274addf89) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9776a806ac](https://linux-hardware.org/?probe=9776a806ac) | Apr 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [597f1536e2](https://linux-hardware.org/?probe=597f1536e2) | Apr 13, 2021 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [8a8adf8790](https://linux-hardware.org/?probe=8a8adf8790) | Apr 12, 2021 |
| Pegatron      | APX85-GS                    | Desktop     | [3a6accac1f](https://linux-hardware.org/?probe=3a6accac1f) | Apr 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [12fb9fd662](https://linux-hardware.org/?probe=12fb9fd662) | Apr 12, 2021 |
| ASUSTek       | P5E                         | Desktop     | [8689ac73b3](https://linux-hardware.org/?probe=8689ac73b3) | Apr 11, 2021 |
| Pegatron      | 2A99                        | Desktop     | [07a84a3b4d](https://linux-hardware.org/?probe=07a84a3b4d) | Apr 11, 2021 |
| MSI           | GL62M 7REX                  | Notebook    | [8ee2678b38](https://linux-hardware.org/?probe=8ee2678b38) | Apr 10, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [258fbf86ed](https://linux-hardware.org/?probe=258fbf86ed) | Apr 09, 2021 |
| HP            | 0A00h                       | Desktop     | [144a5f7819](https://linux-hardware.org/?probe=144a5f7819) | Apr 09, 2021 |
| ASUSTek       | G751JT                      | Notebook    | [4f88289a8c](https://linux-hardware.org/?probe=4f88289a8c) | Apr 08, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [055066b50a](https://linux-hardware.org/?probe=055066b50a) | Apr 08, 2021 |
| Pegatron      | 2A72h                       | Desktop     | [e1fff3ade4](https://linux-hardware.org/?probe=e1fff3ade4) | Apr 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [c480530d42](https://linux-hardware.org/?probe=c480530d42) | Apr 07, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ecae2e7ad8](https://linux-hardware.org/?probe=ecae2e7ad8) | Apr 06, 2021 |
| Samsung       | R530/R730                   | Notebook    | [0085bebd03](https://linux-hardware.org/?probe=0085bebd03) | Apr 05, 2021 |
| Lenovo        | B50-70 80EU                 | Notebook    | [6534232c53](https://linux-hardware.org/?probe=6534232c53) | Apr 04, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [88b1b582b5](https://linux-hardware.org/?probe=88b1b582b5) | Apr 01, 2021 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [e88c887878](https://linux-hardware.org/?probe=e88c887878) | Apr 01, 2021 |
| HP            | EliteBook 755 G2            | Notebook    | [12cd60c247](https://linux-hardware.org/?probe=12cd60c247) | Mar 31, 2021 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [4ac35c901a](https://linux-hardware.org/?probe=4ac35c901a) | Mar 30, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [2838e1ca6c](https://linux-hardware.org/?probe=2838e1ca6c) | Mar 30, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [d8f1bccb78](https://linux-hardware.org/?probe=d8f1bccb78) | Mar 29, 2021 |
| ASRock        | ALiveNF6G-GLAN              | Desktop     | [1f409f9bf1](https://linux-hardware.org/?probe=1f409f9bf1) | Mar 28, 2021 |
| Lenovo        | ThinkPad T430 2349UWT       | Notebook    | [d6edf7c2df](https://linux-hardware.org/?probe=d6edf7c2df) | Mar 28, 2021 |
| HP            | 1589                        | Desktop     | [8b3a28644e](https://linux-hardware.org/?probe=8b3a28644e) | Mar 28, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [25fd34ad8f](https://linux-hardware.org/?probe=25fd34ad8f) | Mar 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [54845ca16f](https://linux-hardware.org/?probe=54845ca16f) | Mar 27, 2021 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [354da6602b](https://linux-hardware.org/?probe=354da6602b) | Mar 27, 2021 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [04469024ca](https://linux-hardware.org/?probe=04469024ca) | Mar 27, 2021 |
| HP            | 8054                        | Desktop     | [b3bc9388b0](https://linux-hardware.org/?probe=b3bc9388b0) | Mar 27, 2021 |
| HP            | 1589                        | Desktop     | [7b3c9bf186](https://linux-hardware.org/?probe=7b3c9bf186) | Mar 27, 2021 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [1f11381bfb](https://linux-hardware.org/?probe=1f11381bfb) | Mar 27, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [c412261d89](https://linux-hardware.org/?probe=c412261d89) | Mar 26, 2021 |
| HP            | ZBook 15 G4                 | Notebook    | [4d3778017f](https://linux-hardware.org/?probe=4d3778017f) | Mar 25, 2021 |
| Samsung       | SF311/SF411/SF511           | Notebook    | [fb1261d331](https://linux-hardware.org/?probe=fb1261d331) | Mar 25, 2021 |
| HP            | 802F                        | Desktop     | [ae40d5cbc9](https://linux-hardware.org/?probe=ae40d5cbc9) | Mar 24, 2021 |
| ASUSTek       | P7H55D-M EVO                | Desktop     | [ccb057337e](https://linux-hardware.org/?probe=ccb057337e) | Mar 23, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [91409f3c71](https://linux-hardware.org/?probe=91409f3c71) | Mar 23, 2021 |
| Shuttle       | FZ77                        | Desktop     | [ca3dfc266d](https://linux-hardware.org/?probe=ca3dfc266d) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [63c58340d1](https://linux-hardware.org/?probe=63c58340d1) | Mar 20, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0debcb68ae](https://linux-hardware.org/?probe=0debcb68ae) | Mar 18, 2021 |
| Lenovo        | B50-45 80F0                 | Notebook    | [9af2b46c0a](https://linux-hardware.org/?probe=9af2b46c0a) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [50b82af935](https://linux-hardware.org/?probe=50b82af935) | Mar 18, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [72fc5ffa15](https://linux-hardware.org/?probe=72fc5ffa15) | Mar 18, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [3c98763834](https://linux-hardware.org/?probe=3c98763834) | Mar 17, 2021 |
| HP            | 1495                        | Desktop     | [23947d4a1e](https://linux-hardware.org/?probe=23947d4a1e) | Mar 17, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [48f8273cdb](https://linux-hardware.org/?probe=48f8273cdb) | Mar 16, 2021 |
| Unknown       | Unknown                     | Desktop     | [e9c99960d1](https://linux-hardware.org/?probe=e9c99960d1) | Mar 16, 2021 |
| ASUSTek       | P5N32-E SLI                 | Desktop     | [11caeb50ac](https://linux-hardware.org/?probe=11caeb50ac) | Mar 16, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [3d16f2ffb4](https://linux-hardware.org/?probe=3d16f2ffb4) | Mar 16, 2021 |
| Acer          | Aspire C24-865              | All in one  | [6dc98b8074](https://linux-hardware.org/?probe=6dc98b8074) | Mar 16, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [2cbefa6c90](https://linux-hardware.org/?probe=2cbefa6c90) | Mar 15, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [db3ab2a133](https://linux-hardware.org/?probe=db3ab2a133) | Mar 15, 2021 |
| HP            | 8267 A01                    | Mini pc     | [3aa09cf72a](https://linux-hardware.org/?probe=3aa09cf72a) | Mar 15, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [ad7470fc89](https://linux-hardware.org/?probe=ad7470fc89) | Mar 15, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [2417d2d1b5](https://linux-hardware.org/?probe=2417d2d1b5) | Mar 14, 2021 |
| MSI           | H81M-P33                    | Desktop     | [9487818af0](https://linux-hardware.org/?probe=9487818af0) | Mar 13, 2021 |
| HP            | 859C                        | Desktop     | [6434de9da7](https://linux-hardware.org/?probe=6434de9da7) | Mar 13, 2021 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [feedeb2b69](https://linux-hardware.org/?probe=feedeb2b69) | Mar 12, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [c6866f0d34](https://linux-hardware.org/?probe=c6866f0d34) | Mar 10, 2021 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [112bdb4e2a](https://linux-hardware.org/?probe=112bdb4e2a) | Mar 09, 2021 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [e83e8ffa64](https://linux-hardware.org/?probe=e83e8ffa64) | Mar 08, 2021 |
| Lenovo        | ThinkPad T450 20BV001YMS    | Notebook    | [57449243ca](https://linux-hardware.org/?probe=57449243ca) | Mar 07, 2021 |
| Gigabyte      | MZ31-AR0-00 01010101        | Server      | [6d486a7ee9](https://linux-hardware.org/?probe=6d486a7ee9) | Mar 05, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [ee5505ce8e](https://linux-hardware.org/?probe=ee5505ce8e) | Mar 05, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [c4548cb133](https://linux-hardware.org/?probe=c4548cb133) | Mar 04, 2021 |
| ASUSTek       | P5E                         | Desktop     | [adac4a8f70](https://linux-hardware.org/?probe=adac4a8f70) | Mar 04, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [857a1c6e52](https://linux-hardware.org/?probe=857a1c6e52) | Mar 04, 2021 |
| Intel         | DH77KC AAG39641-401         | Desktop     | [1af2ede26c](https://linux-hardware.org/?probe=1af2ede26c) | Mar 03, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [3e423c7d87](https://linux-hardware.org/?probe=3e423c7d87) | Mar 03, 2021 |
| ASUSTek       | UX32A                       | Notebook    | [7debc0a27d](https://linux-hardware.org/?probe=7debc0a27d) | Mar 02, 2021 |
| ASRock        | 990FX Extreme6              | Desktop     | [8b50e7792e](https://linux-hardware.org/?probe=8b50e7792e) | Mar 02, 2021 |
| Gigabyte      | Z490 VISION D               | Desktop     | [0ac71fbeba](https://linux-hardware.org/?probe=0ac71fbeba) | Feb 28, 2021 |
| Lenovo        | ThinkPad E580 20KS001RMX    | Notebook    | [5bcb97d47f](https://linux-hardware.org/?probe=5bcb97d47f) | Feb 28, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [1f91d9a631](https://linux-hardware.org/?probe=1f91d9a631) | Feb 27, 2021 |
| ASRock        | P67 Extreme4                | Desktop     | [ad443f47c2](https://linux-hardware.org/?probe=ad443f47c2) | Feb 27, 2021 |
| ASUSTek       | X551CAP                     | Notebook    | [987d795cb7](https://linux-hardware.org/?probe=987d795cb7) | Feb 27, 2021 |
| ASUSTek       | K54C                        | Notebook    | [467c86ad9a](https://linux-hardware.org/?probe=467c86ad9a) | Feb 26, 2021 |
| Dell          | Latitude E7470              | Notebook    | [93cf5a0e8b](https://linux-hardware.org/?probe=93cf5a0e8b) | Feb 26, 2021 |
| Acer          | Aspire A315-42              | Notebook    | [9a68092d87](https://linux-hardware.org/?probe=9a68092d87) | Feb 25, 2021 |
| ASUSTek       | K70IO                       | Notebook    | [49623c33e1](https://linux-hardware.org/?probe=49623c33e1) | Feb 25, 2021 |
| HP            | 805A                        | Desktop     | [26d9d2a996](https://linux-hardware.org/?probe=26d9d2a996) | Feb 25, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [cd111b2c04](https://linux-hardware.org/?probe=cd111b2c04) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M91p 7033J54    | Desktop     | [762e158923](https://linux-hardware.org/?probe=762e158923) | Feb 25, 2021 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [bcbcbdf158](https://linux-hardware.org/?probe=bcbcbdf158) | Feb 25, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [5af628a455](https://linux-hardware.org/?probe=5af628a455) | Feb 25, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [90fa6e7434](https://linux-hardware.org/?probe=90fa6e7434) | Feb 24, 2021 |
| Lenovo        | ThinkCentre M90 5485W45     | Desktop     | [601807d0e7](https://linux-hardware.org/?probe=601807d0e7) | Feb 24, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [84ddb6cbec](https://linux-hardware.org/?probe=84ddb6cbec) | Feb 24, 2021 |
| Lenovo        | ThinkPad T410 2518A3G       | Notebook    | [8a3e6146db](https://linux-hardware.org/?probe=8a3e6146db) | Feb 23, 2021 |
| Dell          | 0C27VV A01                  | Desktop     | [d47c258b89](https://linux-hardware.org/?probe=d47c258b89) | Feb 22, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [ccd37902d0](https://linux-hardware.org/?probe=ccd37902d0) | Feb 22, 2021 |
| Dell          | 0YC523                      | Desktop     | [d805d39715](https://linux-hardware.org/?probe=d805d39715) | Feb 22, 2021 |
| Acer          | Swift SF315-52              | Notebook    | [50065d2efb](https://linux-hardware.org/?probe=50065d2efb) | Feb 20, 2021 |
| HP            | Presario CQ56               | Notebook    | [54f5681a51](https://linux-hardware.org/?probe=54f5681a51) | Feb 20, 2021 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [c116602ad6](https://linux-hardware.org/?probe=c116602ad6) | Feb 18, 2021 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [b1e9a3d14d](https://linux-hardware.org/?probe=b1e9a3d14d) | Feb 18, 2021 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [d90fd08234](https://linux-hardware.org/?probe=d90fd08234) | Feb 17, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [544e6bde0b](https://linux-hardware.org/?probe=544e6bde0b) | Feb 17, 2021 |
| ECS           | Nettle3                     | Desktop     | [fb2a315c43](https://linux-hardware.org/?probe=fb2a315c43) | Feb 16, 2021 |
| Lenovo        | ThinkPad L490 20Q50020MX    | Notebook    | [24fb34852c](https://linux-hardware.org/?probe=24fb34852c) | Feb 16, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [d91ab98cb0](https://linux-hardware.org/?probe=d91ab98cb0) | Feb 16, 2021 |
| Dell          | 060K5C A04                  | Server      | [33fde2b5fb](https://linux-hardware.org/?probe=33fde2b5fb) | Feb 15, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [33e13fb990](https://linux-hardware.org/?probe=33e13fb990) | Feb 14, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [ce117380dd](https://linux-hardware.org/?probe=ce117380dd) | Feb 14, 2021 |
| HP            | EliteBook 2560p             | Notebook    | [573a6ae3c7](https://linux-hardware.org/?probe=573a6ae3c7) | Feb 14, 2021 |
| HP            | EliteBook 6930p             | Notebook    | [2941ebcde6](https://linux-hardware.org/?probe=2941ebcde6) | Feb 13, 2021 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [21e0385b49](https://linux-hardware.org/?probe=21e0385b49) | Feb 13, 2021 |
| Lenovo        | 30BC SDK0J40705 WIN 3425... | Desktop     | [9862174836](https://linux-hardware.org/?probe=9862174836) | Feb 13, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [d87dd2f698](https://linux-hardware.org/?probe=d87dd2f698) | Feb 12, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [99f3171b76](https://linux-hardware.org/?probe=99f3171b76) | Feb 10, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [e052a51f58](https://linux-hardware.org/?probe=e052a51f58) | Feb 10, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [dee973015c](https://linux-hardware.org/?probe=dee973015c) | Feb 09, 2021 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [c0ada2d30c](https://linux-hardware.org/?probe=c0ada2d30c) | Feb 08, 2021 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [71a56734c1](https://linux-hardware.org/?probe=71a56734c1) | Feb 07, 2021 |
| Dell          | Latitude E5470              | Notebook    | [562dbbdcdd](https://linux-hardware.org/?probe=562dbbdcdd) | Feb 07, 2021 |
| Fujitsu Si... | D2811-A1 S26361-D2811-A1    | Desktop     | [826729feac](https://linux-hardware.org/?probe=826729feac) | Feb 07, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [389456d6b7](https://linux-hardware.org/?probe=389456d6b7) | Feb 06, 2021 |
| Acer          | TravelMate 5744             | Notebook    | [78690829c5](https://linux-hardware.org/?probe=78690829c5) | Feb 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [8370d569ed](https://linux-hardware.org/?probe=8370d569ed) | Feb 06, 2021 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [3e78bc9f2c](https://linux-hardware.org/?probe=3e78bc9f2c) | Feb 06, 2021 |
| Dell          | Precision 3520              | Notebook    | [1e72fdbddc](https://linux-hardware.org/?probe=1e72fdbddc) | Feb 05, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [95af098c68](https://linux-hardware.org/?probe=95af098c68) | Feb 05, 2021 |
| HP            | 0A64h                       | Desktop     | [6b5e34333d](https://linux-hardware.org/?probe=6b5e34333d) | Feb 04, 2021 |
| ASRock        | 990FX Extreme3              | Desktop     | [e5ac3cd7e2](https://linux-hardware.org/?probe=e5ac3cd7e2) | Feb 04, 2021 |
| Dell          | Precision 3520              | Notebook    | [fb3da7ea03](https://linux-hardware.org/?probe=fb3da7ea03) | Feb 04, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [47d61a08a0](https://linux-hardware.org/?probe=47d61a08a0) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | Desktop     | [e546964d97](https://linux-hardware.org/?probe=e546964d97) | Jan 31, 2021 |
| Lenovo        | IC 310S-08IGM               | Desktop     | [80124b02cf](https://linux-hardware.org/?probe=80124b02cf) | Jan 31, 2021 |
| Samsung       | R530/R730                   | Notebook    | [9b9a4ce82c](https://linux-hardware.org/?probe=9b9a4ce82c) | Jan 31, 2021 |
| ASUSTek       | K73TA                       | Notebook    | [2b15e899ed](https://linux-hardware.org/?probe=2b15e899ed) | Jan 30, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [20789a4459](https://linux-hardware.org/?probe=20789a4459) | Jan 30, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [c0c66476fe](https://linux-hardware.org/?probe=c0c66476fe) | Jan 30, 2021 |
| ASUSTek       | K73TA                       | Notebook    | [0e4b16a1c5](https://linux-hardware.org/?probe=0e4b16a1c5) | Jan 30, 2021 |
| ASUSTek       | P5G41T-M LX PLUS            | Desktop     | [ef58793cd1](https://linux-hardware.org/?probe=ef58793cd1) | Jan 29, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [3d1daadbf9](https://linux-hardware.org/?probe=3d1daadbf9) | Jan 28, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [897d7d00d7](https://linux-hardware.org/?probe=897d7d00d7) | Jan 27, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [591c655546](https://linux-hardware.org/?probe=591c655546) | Jan 27, 2021 |
| HP            | Stream x360 Convertible ... | Convertible | [10f4ad2179](https://linux-hardware.org/?probe=10f4ad2179) | Jan 27, 2021 |
| HP            | ProBook 430 G1              | Notebook    | [bc43832b9f](https://linux-hardware.org/?probe=bc43832b9f) | Jan 27, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [2d3b61aa15](https://linux-hardware.org/?probe=2d3b61aa15) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [07c16b45cb](https://linux-hardware.org/?probe=07c16b45cb) | Jan 26, 2021 |
| Lenovo        | ThinkPad T430 2349W2P       | Notebook    | [58c2f66dd6](https://linux-hardware.org/?probe=58c2f66dd6) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| Acer          | Aspire SW5-012              | Notebook    | [0903507e18](https://linux-hardware.org/?probe=0903507e18) | Jan 25, 2021 |
| Acer          | Extensa 5220                | Notebook    | [5d121bc112](https://linux-hardware.org/?probe=5d121bc112) | Jan 25, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [aaedd808e4](https://linux-hardware.org/?probe=aaedd808e4) | Jan 25, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [e6dcbd8319](https://linux-hardware.org/?probe=e6dcbd8319) | Jan 24, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [7718bb2939](https://linux-hardware.org/?probe=7718bb2939) | Jan 24, 2021 |
| Acer          | Extensa 5220                | Notebook    | [138ec8e43b](https://linux-hardware.org/?probe=138ec8e43b) | Jan 24, 2021 |
| AOpen         | D1007 0BB4                  | Desktop     | [8e09b52f79](https://linux-hardware.org/?probe=8e09b52f79) | Jan 24, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [c50f23fd8b](https://linux-hardware.org/?probe=c50f23fd8b) | Jan 23, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [6a6277a771](https://linux-hardware.org/?probe=6a6277a771) | Jan 22, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Finland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 182       | 14.42%  |
| Ubuntu 18.04                 | 103       | 8.16%   |
| Ubuntu 22.04                 | 48        | 3.8%    |
| OpenMandriva 4.2             | 33        | 2.61%   |
| Arch Rolling                 | 32        | 2.54%   |
| Debian 11                    | 27        | 2.14%   |
| Arch                         | 27        | 2.14%   |
| Linux Mint 20                | 24        | 1.9%    |
| Ubuntu 21.04                 | 23        | 1.82%   |
| Manjaro                      | 23        | 1.82%   |
| Pop!_OS 22.04                | 22        | 1.74%   |
| OpenMandriva 4.3             | 21        | 1.66%   |
| Linux Mint 20.1              | 21        | 1.66%   |
| Pop!_OS 21.04                | 20        | 1.58%   |
| Ubuntu 20.10                 | 19        | 1.51%   |
| Fedora 36                    | 19        | 1.51%   |
| Xubuntu 20.04                | 18        | 1.43%   |
| Linux Mint 19.3              | 17        | 1.35%   |
| Fedora 33                    | 17        | 1.35%   |
| Ubuntu 21.10                 | 16        | 1.27%   |
| Pop!_OS 20.04                | 16        | 1.27%   |
| Gentoo 2.7                   | 15        | 1.19%   |
| Fedora 32                    | 15        | 1.19%   |
| Debian 10                    | 15        | 1.19%   |
| Linux Mint 20.2              | 14        | 1.11%   |
| Fedora 34                    | 14        | 1.11%   |
| Fedora 31                    | 14        | 1.11%   |
| EndeavourOS Rolling          | 14        | 1.11%   |
| Ubuntu 19.10                 | 13        | 1.03%   |
| ArcoLinux Rolling            | 13        | 1.03%   |
| Linux Mint 20.3              | 12        | 0.95%   |
| Zorin 16                     | 11        | 0.87%   |
| Xubuntu 18.04                | 11        | 0.87%   |
| Pop!_OS 21.10                | 11        | 0.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 11        | 0.87%   |
| KDE neon 20.04               | 10        | 0.79%   |
| Debian Testing               | 10        | 0.79%   |
| Ubuntu 19.04                 | 9         | 0.71%   |
| Gentoo 2.6                   | 9         | 0.71%   |
| Pop!_OS 20.10                | 8         | 0.63%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Ubuntu           | 405       | 33.95%  |
| Linux Mint       | 91        | 7.63%   |
| Fedora           | 86        | 7.21%   |
| Pop!_OS          | 74        | 6.2%    |
| OpenMandriva     | 61        | 5.11%   |
| Arch             | 59        | 4.95%   |
| Manjaro          | 56        | 4.69%   |
| Debian           | 55        | 4.61%   |
| Xubuntu          | 39        | 3.27%   |
| ROSA             | 25        | 2.1%    |
| Gentoo           | 25        | 2.1%    |
| Kubuntu          | 17        | 1.42%   |
| openSUSE         | 16        | 1.34%   |
| EndeavourOS      | 16        | 1.34%   |
| Zorin            | 15        | 1.26%   |
| ArcoLinux        | 15        | 1.26%   |
| Ubuntu MATE      | 13        | 1.09%   |
| Lubuntu          | 12        | 1.01%   |
| KDE neon         | 12        | 1.01%   |
| CentOS           | 11        | 0.92%   |
| MX               | 7         | 0.59%   |
| Elementary       | 7         | 0.59%   |
| Kali             | 6         | 0.5%    |
| BlackPanther     | 6         | 0.5%    |
| Ubuntu Unity     | 5         | 0.42%   |
| Peppermint       | 5         | 0.42%   |
| Ubuntu Budgie    | 4         | 0.34%   |
| Garuda Linux     | 4         | 0.34%   |
| Endless          | 4         | 0.34%   |
| Clear Linux      | 4         | 0.34%   |
| RHEL             | 3         | 0.25%   |
| LMDE             | 3         | 0.25%   |
| Raspbian         | 2         | 0.17%   |
| Parrot           | 2         | 0.17%   |
| org.kde.Platform | 2         | 0.17%   |
| Oracle Linux     | 2         | 0.17%   |
| Nobara           | 2         | 0.17%   |
| Devuan           | 2         | 0.17%   |
| Artix            | 2         | 0.17%   |
| antergos         | 2         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.4.0-42-generic                   | 37        | 2.69%   |
| 5.10.14-desktop-1omv4002           | 32        | 2.33%   |
| 5.16.7-desktop-1omv4003            | 20        | 1.45%   |
| 5.4.0-58-generic                   | 18        | 1.31%   |
| 5.4.0-48-generic                   | 16        | 1.16%   |
| 5.4.0-47-generic                   | 16        | 1.16%   |
| 5.4.0-52-generic                   | 12        | 0.87%   |
| 5.3.0-40-generic                   | 12        | 0.87%   |
| 5.11.0-7620-generic                | 12        | 0.87%   |
| 5.8.0-44-generic                   | 10        | 0.73%   |
| 5.15.0-52-generic                  | 10        | 0.73%   |
| 5.8.0-41-generic                   | 9         | 0.65%   |
| 5.4.0-65-generic                   | 9         | 0.65%   |
| 5.4.0-56-generic                   | 9         | 0.65%   |
| 5.4.0-53-generic                   | 9         | 0.65%   |
| 5.15.0-48-generic                  | 9         | 0.65%   |
| 5.15.0-46-generic                  | 9         | 0.65%   |
| 5.4.0-45-generic                   | 8         | 0.58%   |
| 5.13.0-7620-generic                | 8         | 0.58%   |
| 5.8.0-43-generic                   | 7         | 0.51%   |
| 5.4.0-92-generic                   | 7         | 0.51%   |
| 5.4.0-66-generic                   | 7         | 0.51%   |
| 5.4.0-54-generic                   | 7         | 0.51%   |
| 5.3.0-46-generic                   | 7         | 0.51%   |
| 5.3.0-42-generic                   | 7         | 0.51%   |
| 5.19.0-76051900-generic            | 7         | 0.51%   |
| 5.15.0-41-generic                  | 7         | 0.51%   |
| 5.15.0-27-generic                  | 7         | 0.51%   |
| 5.11.0-25-generic                  | 7         | 0.51%   |
| 5.8.0-7630-generic                 | 6         | 0.44%   |
| 5.4.0-7634-generic                 | 6         | 0.44%   |
| 5.4.0-51-generic                   | 6         | 0.44%   |
| 5.15.0-56-generic                  | 6         | 0.44%   |
| 5.15.0-47-generic                  | 6         | 0.44%   |
| 5.13.0-30-generic                  | 6         | 0.44%   |
| 5.13.0-22-generic                  | 6         | 0.44%   |
| 5.11.0-41-generic                  | 6         | 0.44%   |
| 5.11.0-34-generic                  | 6         | 0.44%   |
| 5.11.0-27-generic                  | 6         | 0.44%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 6         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 252       | 19.24%  |
| 5.8.0   | 81        | 6.18%   |
| 5.15.0  | 80        | 6.11%   |
| 4.15.0  | 78        | 5.95%   |
| 5.11.0  | 73        | 5.57%   |
| 5.3.0   | 49        | 3.74%   |
| 5.13.0  | 48        | 3.66%   |
| 5.10.14 | 33        | 2.52%   |
| 5.10.0  | 27        | 2.06%   |
| 5.0.0   | 26        | 1.98%   |
| 4.18.0  | 23        | 1.76%   |
| 5.16.7  | 20        | 1.53%   |
| 4.19.0  | 19        | 1.45%   |
| 5.19.0  | 12        | 0.92%   |
| 5.17.5  | 9         | 0.69%   |
| 5.14.0  | 8         | 0.61%   |
| 4.18.16 | 7         | 0.53%   |
| 5.10.74 | 6         | 0.46%   |
| 4.9.60  | 6         | 0.46%   |
| 3.10.0  | 6         | 0.46%   |
| 6.0.6   | 5         | 0.38%   |
| 6.0.5   | 5         | 0.38%   |
| 5.15.15 | 5         | 0.38%   |
| 5.14.14 | 5         | 0.38%   |
| 5.12.4  | 5         | 0.38%   |
| 5.11.14 | 5         | 0.38%   |
| 6.0.8   | 4         | 0.31%   |
| 6.0.7   | 4         | 0.31%   |
| 6.0.12  | 4         | 0.31%   |
| 5.9.0   | 4         | 0.31%   |
| 5.8.11  | 4         | 0.31%   |
| 5.6.0   | 4         | 0.31%   |
| 5.3.18  | 4         | 0.31%   |
| 5.16.13 | 4         | 0.31%   |
| 5.15.28 | 4         | 0.31%   |
| 5.13.9  | 4         | 0.31%   |
| 5.11.2  | 4         | 0.31%   |
| 6.0.11  | 3         | 0.23%   |
| 5.9.16  | 3         | 0.23%   |
| 5.9.11  | 3         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 277       | 21.49%  |
| 5.15    | 137       | 10.63%  |
| 5.8     | 106       | 8.22%   |
| 5.10    | 96        | 7.45%   |
| 5.11    | 95        | 7.37%   |
| 4.15    | 79        | 6.13%   |
| 5.13    | 64        | 4.97%   |
| 5.3     | 62        | 4.81%   |
| 5.16    | 43        | 3.34%   |
| 6.0     | 33        | 2.56%   |
| 4.18    | 31        | 2.4%    |
| 5.17    | 29        | 2.25%   |
| 5.19    | 28        | 2.17%   |
| 5.0     | 27        | 2.09%   |
| 4.19    | 24        | 1.86%   |
| 5.14    | 20        | 1.55%   |
| 5.9     | 18        | 1.4%    |
| 5.7     | 17        | 1.32%   |
| 5.18    | 17        | 1.32%   |
| 5.12    | 17        | 1.32%   |
| 5.6     | 14        | 1.09%   |
| 4.9     | 14        | 1.09%   |
| 5.5     | 13        | 1.01%   |
| 3.10    | 6         | 0.47%   |
| 4.1     | 4         | 0.31%   |
| 6.1     | 3         | 0.23%   |
| 5.2     | 3         | 0.23%   |
| 4.4     | 3         | 0.23%   |
| 5.1     | 2         | 0.16%   |
| 4.13    | 2         | 0.16%   |
| 4.20    | 1         | 0.08%   |
| 4.17    | 1         | 0.08%   |
| 4.14    | 1         | 0.08%   |
| 4.12    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1114      | 96.45%  |
| i686    | 30        | 2.6%    |
| aarch64 | 9         | 0.78%   |
| armv7l  | 1         | 0.09%   |
| armv6l  | 1         | 0.09%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 516       | 42.82%  |
| KDE5             | 196       | 16.27%  |
| Unknown          | 172       | 14.27%  |
| XFCE             | 96        | 7.97%   |
| X-Cinnamon       | 59        | 4.9%    |
| MATE             | 38        | 3.15%   |
| KDE              | 23        | 1.91%   |
| LXQt             | 13        | 1.08%   |
| KDE4             | 13        | 1.08%   |
| Cinnamon         | 13        | 1.08%   |
| i3               | 9         | 0.75%   |
| GNOME Flashback  | 9         | 0.75%   |
| LXDE             | 7         | 0.58%   |
| Budgie           | 7         | 0.58%   |
| Pantheon         | 6         | 0.5%    |
| lightdm-xsession | 6         | 0.5%    |
| Unity            | 5         | 0.41%   |
| DWM              | 3         | 0.25%   |
| Deepin           | 3         | 0.25%   |
| bspwm            | 3         | 0.25%   |
| sway             | 2         | 0.17%   |
| LeftWM           | 2         | 0.17%   |
| xubuntu          | 1         | 0.08%   |
| xmonad           | 1         | 0.08%   |
| sway:Unity       | 1         | 0.08%   |
| GNOME Classic    | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 887       | 74.98%  |
| Wayland | 169       | 14.29%  |
| Unknown | 77        | 6.51%   |
| Tty     | 48        | 4.06%   |
| Web     | 2         | 0.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 601       | 49.79%  |
| SDDM    | 175       | 14.5%   |
| GDM     | 167       | 13.84%  |
| LightDM | 99        | 8.2%    |
| GDM3    | 86        | 7.13%   |
| TDM     | 61        | 5.05%   |
| KDM     | 14        | 1.16%   |
| XDM     | 1         | 0.08%   |
| SLiM    | 1         | 0.08%   |
| Ly      | 1         | 0.08%   |
| LXDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 499       | 42.22%  |
| fi_FI       | 381       | 32.23%  |
| Unknown     | 138       | 11.68%  |
| en_GB       | 69        | 5.84%   |
| C           | 22        | 1.86%   |
| ru_RU       | 21        | 1.78%   |
| en_FI       | 6         | 0.51%   |
| sv_FI       | 5         | 0.42%   |
| sv_SE       | 4         | 0.34%   |
| C.UTF8      | 4         | 0.34%   |
| pl_PL       | 3         | 0.25%   |
| fr_FR       | 3         | 0.25%   |
| en_DK       | 3         | 0.25%   |
| it_IT       | 2         | 0.17%   |
| et_EE       | 2         | 0.17%   |
| en_SE       | 2         | 0.17%   |
| en_IE       | 2         | 0.17%   |
| en_AG       | 2         | 0.17%   |
| de_DE       | 2         | 0.17%   |
| zh_CN       | 1         | 0.08%   |
| UTF-8       | 1         | 0.08%   |
| ja_JP       | 1         | 0.08%   |
| is_IS       | 1         | 0.08%   |
| ia_FR       | 1         | 0.08%   |
| hu_HU       | 1         | 0.08%   |
| fr_CA       | 1         | 0.08%   |
| es_ES       | 1         | 0.08%   |
| en_US.utf-8 | 1         | 0.08%   |
| en_NG       | 1         | 0.08%   |
| en_CA       | 1         | 0.08%   |
| af_ZA       | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 619       | 52.41%  |
| EFI  | 562       | 47.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 885       | 75.06%  |
| Btrfs   | 123       | 10.43%  |
| Overlay | 83        | 7.04%   |
| Unknown | 42        | 3.56%   |
| Xfs     | 26        | 2.21%   |
| Zfs     | 12        | 1.02%   |
| Ext3    | 3         | 0.25%   |
| Ext2    | 3         | 0.25%   |
| F2fs    | 2         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 596       | 50.47%  |
| GPT     | 429       | 36.33%  |
| MBR     | 156       | 13.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1001      | 85.41%  |
| Yes       | 171       | 14.59%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 861       | 73.46%  |
| Yes       | 311       | 26.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 256       | 22.18%  |
| Lenovo                  | 218       | 18.89%  |
| Hewlett-Packard         | 186       | 16.12%  |
| Dell                    | 88        | 7.63%   |
| Acer                    | 67        | 5.81%   |
| MSI                     | 64        | 5.55%   |
| Gigabyte Technology     | 54        | 4.68%   |
| ASRock                  | 45        | 3.9%    |
| Fujitsu                 | 29        | 2.51%   |
| Apple                   | 21        | 1.82%   |
| Samsung Electronics     | 18        | 1.56%   |
| Intel                   | 16        | 1.39%   |
| Fujitsu Siemens         | 10        | 0.87%   |
| Pegatron                | 8         | 0.69%   |
| Foxconn                 | 8         | 0.69%   |
| Raspberry Pi Foundation | 7         | 0.61%   |
| Packard Bell            | 7         | 0.61%   |
| Toshiba                 | 5         | 0.43%   |
| Supermicro              | 4         | 0.35%   |
| Sony                    | 4         | 0.35%   |
| HUAWEI                  | 4         | 0.35%   |
| Unknown                 | 4         | 0.35%   |
| Timi                    | 2         | 0.17%   |
| Medion                  | 2         | 0.17%   |
| Google                  | 2         | 0.17%   |
| ASRockRack              | 2         | 0.17%   |
| AOpen                   | 2         | 0.17%   |
| AMI                     | 2         | 0.17%   |
| ABIT                    | 2         | 0.17%   |
| ZOTAC                   | 1         | 0.09%   |
| ZMY                     | 1         | 0.09%   |
| Xunlong                 | 1         | 0.09%   |
| WeiBu                   | 1         | 0.09%   |
| Valve                   | 1         | 0.09%   |
| Shuttle                 | 1         | 0.09%   |
| Seco                    | 1         | 0.09%   |
| powerinternational      | 1         | 0.09%   |
| Pine Microsystems       | 1         | 0.09%   |
| Notebook                | 1         | 0.09%   |
| MouseComputer           | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUS All Series                      | 23        | 1.99%   |
| HP EliteDesk 800 G1 SFF              | 9         | 0.78%   |
| MSI MS-7C37                          | 6         | 0.52%   |
| ASUS TUF Gaming X570-PLUS            | 6         | 0.52%   |
| Unknown                              | 5         | 0.43%   |
| MSI MS-7A38                          | 4         | 0.35%   |
| Gigabyte X570 AORUS ELITE            | 4         | 0.35%   |
| ASUS Pro WS 565-ACE                  | 4         | 0.35%   |
| ASUS PRIME X370-PRO                  | 4         | 0.35%   |
| ASUS PRIME B350-PLUS                 | 4         | 0.35%   |
| ASUS M5A97 R2.0                      | 4         | 0.35%   |
| Samsung R530/R730                    | 3         | 0.26%   |
| MSI MS-7B89                          | 3         | 0.26%   |
| MSI MS-7B48                          | 3         | 0.26%   |
| Lenovo Yoga Slim 7 14ARE05 82A2      | 3         | 0.26%   |
| Lenovo V145-15AST 81MT               | 3         | 0.26%   |
| Lenovo ThinkPad T420 4180PBG         | 3         | 0.26%   |
| Lenovo MIIX 310-10ICR 80SG           | 3         | 0.26%   |
| HP ProDesk 600 G3 DM                 | 3         | 0.26%   |
| HP Pavilion dv6                      | 3         | 0.26%   |
| HP EliteBook 8460p                   | 3         | 0.26%   |
| HP EliteBook 840 G7 Notebook PC      | 3         | 0.26%   |
| HP EliteBook 820 G1                  | 3         | 0.26%   |
| HP EliteBook 2560p                   | 3         | 0.26%   |
| HP Compaq 8200 Elite SFF PC          | 3         | 0.26%   |
| Fujitsu Siemens ESPRIMO Mobile D9500 | 3         | 0.26%   |
| Fujitsu LIFEBOOK A530                | 3         | 0.26%   |
| Dell XPS 13 9380                     | 3         | 0.26%   |
| Dell OptiPlex 780                    | 3         | 0.26%   |
| Dell Latitude 7490                   | 3         | 0.26%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 3         | 0.26%   |
| ASUS TUF B450-PLUS GAMING            | 3         | 0.26%   |
| ASUS ROG STRIX Z370-F GAMING         | 3         | 0.26%   |
| ASUS ROG STRIX B550-I GAMING         | 3         | 0.26%   |
| ASUS ROG STRIX B550-F GAMING         | 3         | 0.26%   |
| ASUS PRIME B450-PLUS                 | 3         | 0.26%   |
| ASUS E402NA                          | 3         | 0.26%   |
| ASRock B450M-HDV R4.0                | 3         | 0.26%   |
| Acer Aspire X3300                    | 3         | 0.26%   |
| Toshiba Satellite C660               | 2         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 132       | 11.44%  |
| Acer Aspire             | 44        | 3.81%   |
| HP EliteBook            | 41        | 3.55%   |
| Dell Latitude           | 36        | 3.12%   |
| ASUS PRIME              | 36        | 3.12%   |
| HP Compaq               | 33        | 2.86%   |
| HP Pavilion             | 27        | 2.34%   |
| ASUS ROG                | 24        | 2.08%   |
| ASUS All                | 23        | 1.99%   |
| Lenovo IdeaPad          | 20        | 1.73%   |
| ASUS TUF                | 17        | 1.47%   |
| Dell XPS                | 15        | 1.3%    |
| Dell OptiPlex           | 15        | 1.3%    |
| Lenovo Yoga             | 14        | 1.21%   |
| HP EliteDesk            | 13        | 1.13%   |
| Fujitsu LIFEBOOK        | 12        | 1.04%   |
| Dell Precision          | 12        | 1.04%   |
| Lenovo ThinkCentre      | 11        | 0.95%   |
| HP ProBook              | 11        | 0.95%   |
| HP ProDesk              | 10        | 0.87%   |
| ASUS VivoBook           | 10        | 0.87%   |
| Fujitsu ESPRIMO         | 9         | 0.78%   |
| ASUS M5A97              | 8         | 0.69%   |
| RPi Raspberry           | 7         | 0.61%   |
| Gigabyte X570           | 7         | 0.61%   |
| Fujitsu Siemens ESPRIMO | 7         | 0.61%   |
| MSI MS-7C37             | 6         | 0.52%   |
| HP ZBook                | 6         | 0.52%   |
| HP Laptop               | 6         | 0.52%   |
| Toshiba Satellite       | 5         | 0.43%   |
| Lenovo Legion           | 5         | 0.43%   |
| Dell Inspiron           | 5         | 0.43%   |
| ASUS Pro                | 5         | 0.43%   |
| Acer Swift              | 5         | 0.43%   |
| Acer Predator           | 5         | 0.43%   |
| Unknown                 | 5         | 0.43%   |
| Packard Bell EasyNote   | 4         | 0.35%   |
| MSI MS-7A38             | 4         | 0.35%   |
| Gigabyte B550           | 4         | 0.35%   |
| ASRock B450M-HDV        | 4         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 119       | 10.31%  |
| 2012    | 104       | 9.01%   |
| 2018    | 99        | 8.58%   |
| 2013    | 93        | 8.06%   |
| 2011    | 92        | 7.97%   |
| 2020    | 91        | 7.89%   |
| 2017    | 91        | 7.89%   |
| 2015    | 68        | 5.89%   |
| 2014    | 64        | 5.55%   |
| 2008    | 59        | 5.11%   |
| 2016    | 54        | 4.68%   |
| 2009    | 53        | 4.59%   |
| 2010    | 52        | 4.51%   |
| 2021    | 40        | 3.47%   |
| 2007    | 32        | 2.77%   |
| 2022    | 16        | 1.39%   |
| 2006    | 12        | 1.04%   |
| Unknown | 8         | 0.69%   |
| 2005    | 5         | 0.43%   |
| 2004    | 2         | 0.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 584       | 50.61%  |
| Desktop        | 496       | 42.98%  |
| Convertible    | 20        | 1.73%   |
| Mini pc        | 16        | 1.39%   |
| All in one     | 11        | 0.95%   |
| Server         | 10        | 0.87%   |
| System on chip | 8         | 0.69%   |
| Tablet         | 7         | 0.61%   |
| Phone          | 2         | 0.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1065      | 91.89%  |
| Enabled  | 94        | 8.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1152      | 99.83%  |
| Yes  | 2         | 0.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 253       | 21.64%  |
| 16.01-24.0      | 253       | 21.64%  |
| 3.01-4.0        | 239       | 20.44%  |
| 8.01-16.0       | 174       | 14.88%  |
| 32.01-64.0      | 123       | 10.52%  |
| 1.01-2.0        | 40        | 3.42%   |
| 64.01-256.0     | 37        | 3.17%   |
| 24.01-32.0      | 21        | 1.8%    |
| 2.01-3.0        | 18        | 1.54%   |
| 0.51-1.0        | 6         | 0.51%   |
| More than 256.0 | 4         | 0.34%   |
| 0.01-0.5        | 1         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 449       | 35.22%  |
| 2.01-3.0    | 291       | 22.82%  |
| 4.01-8.0    | 177       | 13.88%  |
| 3.01-4.0    | 151       | 11.84%  |
| 0.51-1.0    | 101       | 7.92%   |
| 8.01-16.0   | 64        | 5.02%   |
| 0.01-0.5    | 20        | 1.57%   |
| 16.01-24.0  | 10        | 0.78%   |
| 32.01-64.0  | 5         | 0.39%   |
| 24.01-32.0  | 4         | 0.31%   |
| 64.01-256.0 | 2         | 0.16%   |
| 0           | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 694       | 58.47%  |
| 2      | 250       | 21.06%  |
| 3      | 107       | 9.01%   |
| 4      | 50        | 4.21%   |
| 5      | 29        | 2.44%   |
| 0      | 20        | 1.68%   |
| 6      | 14        | 1.18%   |
| 7      | 8         | 0.67%   |
| 9      | 6         | 0.51%   |
| 8      | 5         | 0.42%   |
| 10     | 2         | 0.17%   |
| 23     | 1         | 0.08%   |
| 11     | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 694       | 59.52%  |
| Yes       | 472       | 40.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1036      | 89.54%  |
| No        | 121       | 10.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 815       | 70.26%  |
| No        | 345       | 29.74%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 643       | 55.24%  |
| No        | 521       | 44.76%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Finland | 1154      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Helsinki     | 527       | 42.6%   |
| Tampere      | 112       | 9.05%   |
| Turku        | 98        | 7.92%   |
| Oulu         | 59        | 4.77%   |
| Espoo        | 58        | 4.69%   |
| Kuopio       | 34        | 2.75%   |
| Lahti        | 28        | 2.26%   |
| Jyväskylä  | 28        | 2.26%   |
| Vantaa       | 27        | 2.18%   |
| Vaasa        | 15        | 1.21%   |
| Raisio       | 15        | 1.21%   |
| Tuusula      | 13        | 1.05%   |
| Joensuu      | 11        | 0.89%   |
| Lappeenranta | 10        | 0.81%   |
| Hyvinkaeae   | 10        | 0.81%   |
| Raahe        | 9         | 0.73%   |
| Pori         | 8         | 0.65%   |
| Salo         | 5         | 0.4%    |
| Kotka        | 5         | 0.4%    |
| Tenala       | 4         | 0.32%   |
| Solv         | 4         | 0.32%   |
| Seinäjoki   | 4         | 0.32%   |
| Kouvola      | 4         | 0.32%   |
| Klaukkala    | 4         | 0.32%   |
| Järvenpää | 4         | 0.32%   |
| Hämeenlinna | 4         | 0.32%   |
| Rusko        | 3         | 0.24%   |
| Riihimäki   | 3         | 0.24%   |
| Rauma        | 3         | 0.24%   |
| Porlammi     | 3         | 0.24%   |
| Mäntsälä  | 3         | 0.24%   |
| Lempäälä  | 3         | 0.24%   |
| Kokkola      | 3         | 0.24%   |
| Kerava       | 3         | 0.24%   |
| Heinola      | 3         | 0.24%   |
| Hanko        | 3         | 0.24%   |
| Urjala       | 2         | 0.16%   |
| Tupos        | 2         | 0.16%   |
| Tarvasjoki   | 2         | 0.16%   |
| Sastamala    | 2         | 0.16%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 350       | 550    | 20.59%  |
| WDC                         | 249       | 435    | 14.65%  |
| Seagate                     | 217       | 346    | 12.76%  |
| Kingston                    | 196       | 278    | 11.53%  |
| Toshiba                     | 85        | 134    | 5%      |
| Intel                       | 65        | 81     | 3.82%   |
| Hitachi                     | 61        | 84     | 3.59%   |
| Unknown                     | 60        | 87     | 3.53%   |
| SanDisk                     | 52        | 61     | 3.06%   |
| SK hynix                    | 51        | 65     | 3%      |
| Crucial                     | 44        | 53     | 2.59%   |
| Micron Technology           | 28        | 56     | 1.65%   |
| HGST                        | 27        | 50     | 1.59%   |
| A-DATA Technology           | 23        | 31     | 1.35%   |
| Corsair                     | 13        | 15     | 0.76%   |
| PNY                         | 12        | 13     | 0.71%   |
| Maxtor                      | 12        | 19     | 0.71%   |
| Transcend                   | 11        | 12     | 0.65%   |
| OCZ                         | 11        | 16     | 0.65%   |
| Phison                      | 10        | 11     | 0.59%   |
| KIOXIA                      | 10        | 10     | 0.59%   |
| Fujitsu                     | 10        | 13     | 0.59%   |
| Apple                       | 9         | 11     | 0.53%   |
| Verbatim                    | 7         | 10     | 0.41%   |
| LITEON                      | 7         | 9      | 0.41%   |
| LITEONIT                    | 5         | 7      | 0.29%   |
| Intenso                     | 5         | 5      | 0.29%   |
| China                       | 5         | 5      | 0.29%   |
| XPG                         | 4         | 5      | 0.24%   |
| Patriot                     | 4         | 7      | 0.24%   |
| Kingston Technology Company | 4         | 4      | 0.24%   |
| UMIS                        | 3         | 3      | 0.18%   |
| HUAWEI                      | 3         | 3      | 0.18%   |
| Hewlett-Packard             | 3         | 4      | 0.18%   |
| ASMT                        | 3         | 3      | 0.18%   |
| Plextor                     | 2         | 2      | 0.12%   |
| OCZ-VERTEX3                 | 2         | 2      | 0.12%   |
| OCZ-VERTEX                  | 2         | 2      | 0.12%   |
| Lexar                       | 2         | 2      | 0.12%   |
| Lenovo                      | 2         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 29        | 1.51%   |
| Kingston SA400S37240G 240GB SSD                     | 29        | 1.51%   |
| Kingston SA400S37120G 120GB SSD                     | 22        | 1.15%   |
| Samsung SSD 850 EVO 500GB                           | 21        | 1.09%   |
| Kingston SA400S37480G 480GB SSD                     | 18        | 0.94%   |
| Samsung NVMe SSD Drive 500GB                        | 17        | 0.89%   |
| Kingston SV300S37A120G 120GB SSD                    | 16        | 0.83%   |
| Unknown MMC Card  64GB                              | 15        | 0.78%   |
| Kingston SV300S37A240G 240GB SSD                    | 13        | 0.68%   |
| Kingston SHFS37A120G 120GB SSD                      | 13        | 0.68%   |
| Seagate ST9500325AS 500GB                           | 12        | 0.63%   |
| Samsung SSD 860 EVO 500GB                           | 12        | 0.63%   |
| Seagate ST500DM002-1BD142 500GB                     | 11        | 0.57%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 11        | 0.57%   |
| HGST HTS721010A9E630 1TB                            | 11        | 0.57%   |
| Unknown MMC Card  32GB                              | 10        | 0.52%   |
| Samsung NVMe SSD Drive 512GB                        | 10        | 0.52%   |
| Samsung NVMe SSD Drive 1TB                          | 10        | 0.52%   |
| Samsung HD103SJ 1TB                                 | 10        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                         | 9         | 0.47%   |
| WDC WD40EFRX-68WT0N0 4TB                            | 8         | 0.42%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 8         | 0.42%   |
| Toshiba DT01ACA300 3TB                              | 8         | 0.42%   |
| Samsung SSD 960 EVO 500GB                           | 8         | 0.42%   |
| Samsung SSD 860 EVO 1TB                             | 8         | 0.42%   |
| Samsung HD501LJ 500GB                               | 8         | 0.42%   |
| PNY CS900 120GB SSD                                 | 8         | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 7         | 0.36%   |
| SK hynix NVMe SSD Drive 256GB                       | 7         | 0.36%   |
| Seagate ST500LT012-1DG142 500GB                     | 7         | 0.36%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB                      | 7         | 0.36%   |
| Seagate Expansion 4TB                               | 7         | 0.36%   |
| Samsung SSD 840 EVO 120GB                           | 7         | 0.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 7         | 0.36%   |
| Intel SSDPEKNW010T8 1TB                             | 7         | 0.36%   |
| Toshiba NVMe SSD Drive 256GB                        | 6         | 0.31%   |
| Toshiba MQ01ABD100 1TB                              | 6         | 0.31%   |
| SK hynix NVMe SSD Drive 512GB                       | 6         | 0.31%   |
| Seagate ST4000DM004-2CV104 4TB                      | 6         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 210       | 334    | 33.07%  |
| WDC                 | 204       | 357    | 32.13%  |
| Hitachi             | 61        | 84     | 9.61%   |
| Toshiba             | 57        | 88     | 8.98%   |
| Samsung Electronics | 42        | 60     | 6.61%   |
| HGST                | 27        | 50     | 4.25%   |
| Maxtor              | 12        | 19     | 1.89%   |
| Fujitsu             | 10        | 13     | 1.57%   |
| Unknown             | 3         | 3      | 0.47%   |
| Intenso             | 2         | 2      | 0.31%   |
| ASMT                | 2         | 2      | 0.31%   |
| Apple               | 2         | 2      | 0.31%   |
| RSH-339             | 1         | 1      | 0.16%   |
| JMicron Technology  | 1         | 3      | 0.16%   |
| Hewlett-Packard     | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 201       | 289    | 30.45%  |
| Kingston            | 172       | 247    | 26.06%  |
| Crucial             | 42        | 51     | 6.36%   |
| WDC                 | 37        | 52     | 5.61%   |
| Intel               | 30        | 42     | 4.55%   |
| SanDisk             | 25        | 31     | 3.79%   |
| Micron Technology   | 20        | 47     | 3.03%   |
| A-DATA Technology   | 12        | 17     | 1.82%   |
| Transcend           | 11        | 12     | 1.67%   |
| PNY                 | 11        | 12     | 1.67%   |
| OCZ                 | 11        | 16     | 1.67%   |
| Toshiba             | 10        | 18     | 1.52%   |
| SK hynix            | 10        | 19     | 1.52%   |
| Verbatim            | 7         | 10     | 1.06%   |
| LITEON              | 7         | 9      | 1.06%   |
| Corsair             | 7         | 8      | 1.06%   |
| Apple               | 6         | 7      | 0.91%   |
| LITEONIT            | 5         | 7      | 0.76%   |
| China               | 5         | 5      | 0.76%   |
| Patriot             | 4         | 7      | 0.61%   |
| Intenso             | 3         | 3      | 0.45%   |
| Plextor             | 2         | 2      | 0.3%    |
| OCZ-VERTEX3         | 2         | 2      | 0.3%    |
| OCZ-VERTEX          | 2         | 2      | 0.3%    |
| Hewlett-Packard     | 2         | 3      | 0.3%    |
| BHT                 | 2         | 4      | 0.3%    |
| Vaseky              | 1         | 1      | 0.15%   |
| Unknown             | 1         | 1      | 0.15%   |
| TSA                 | 1         | 1      | 0.15%   |
| TO Exter            | 1         | 1      | 0.15%   |
| SPCC                | 1         | 1      | 0.15%   |
| Seagate             | 1         | 1      | 0.15%   |
| Ramsta              | 1         | 1      | 0.15%   |
| JMicron Technology  | 1         | 1      | 0.15%   |
| GOODRAM             | 1         | 1      | 0.15%   |
| FORESEE             | 1         | 1      | 0.15%   |
| CT240BX5            | 1         | 1      | 0.15%   |
| ATP                 | 1         | 1      | 0.15%   |
| ASMT                | 1         | 1      | 0.15%   |
| Unknown             | 1         | 1      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 566       | 936    | 37.31%  |
| HDD     | 525       | 1019   | 34.61%  |
| NVMe    | 350       | 483    | 23.07%  |
| MMC     | 59        | 82     | 3.89%   |
| Unknown | 17        | 26     | 1.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 885       | 1898   | 65.9%   |
| NVMe | 349       | 481    | 25.99%  |
| MMC  | 59        | 82     | 4.39%   |
| SAS  | 50        | 85     | 3.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 722       | 1209   | 62.3%   |
| 0.51-1.0   | 270       | 380    | 23.3%   |
| 1.01-2.0   | 70        | 136    | 6.04%   |
| 3.01-4.0   | 37        | 94     | 3.19%   |
| 4.01-10.0  | 30        | 73     | 2.59%   |
| 2.01-3.0   | 29        | 62     | 2.5%    |
| 10.01-20.0 | 1         | 1      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 347       | 28.75%  |
| 251-500        | 233       | 19.3%   |
| 501-1000       | 154       | 12.76%  |
| 51-100         | 92        | 7.62%   |
| More than 3000 | 81        | 6.71%   |
| 1-20           | 79        | 6.55%   |
| 1001-2000      | 78        | 6.46%   |
| Unknown        | 58        | 4.81%   |
| 21-50          | 43        | 3.56%   |
| 2001-3000      | 42        | 3.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 475       | 38%     |
| 21-50          | 209       | 16.72%  |
| 101-250        | 129       | 10.32%  |
| 51-100         | 129       | 10.32%  |
| 251-500        | 78        | 6.24%   |
| 501-1000       | 71        | 5.68%   |
| Unknown        | 58        | 4.64%   |
| 1001-2000      | 43        | 3.44%   |
| More than 3000 | 33        | 2.64%   |
| 2001-3000      | 25        | 2%      |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD40EFRX-68WT0N0 4TB                       | 4         | 6      | 3.36%   |
| Seagate ST9500325AS 500GB                      | 3         | 4      | 2.52%   |
| Samsung Electronics HD103SJ 1TB                | 3         | 4      | 2.52%   |
| Kingston SHFS37A120G 120GB SSD                 | 3         | 4      | 2.52%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 1.68%   |
| Samsung Electronics SSD 850 EVO 1TB            | 2         | 2      | 1.68%   |
| Micron Technology MTFDDAK512MAM-1K1 512GB SSD  | 2         | 2      | 1.68%   |
| Micron Technology 1100_MTFDDAK512TBN 512GB SSD | 2         | 4      | 1.68%   |
| Maxtor 7Y250M0 250GB                           | 2         | 2      | 1.68%   |
| Intel SSDSA2M080G2GC 80GB                      | 2         | 2      | 1.68%   |
| HGST HTS725050A7E630 500GB                     | 2         | 2      | 1.68%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 0.84%   |
| WDC WD6400AAKS-07A7B0 640GB                    | 1         | 1      | 0.84%   |
| WDC WD50EZRZ-32RWYB1 5TB                       | 1         | 1      | 0.84%   |
| WDC WD5000ABPS-01ZZB0 500GB                    | 1         | 1      | 0.84%   |
| WDC WD5000AAKX-00ERMA0 500GB                   | 1         | 1      | 0.84%   |
| WDC WD5000AAKS-22A7B0 500GB                    | 1         | 1      | 0.84%   |
| WDC WD3200BEVT-22ZCT0 320GB                    | 1         | 1      | 0.84%   |
| WDC WD3200AAKS-00L9A0 320GB                    | 1         | 1      | 0.84%   |
| WDC WD3200AAJS-60Z0A0 320GB                    | 1         | 1      | 0.84%   |
| WDC WD3200AAJS-00RYA0 320GB                    | 1         | 1      | 0.84%   |
| WDC WD30EFRX-68EUZN0 3TB                       | 1         | 1      | 0.84%   |
| WDC WD2500AAJS-00V4A0 250GB                    | 1         | 1      | 0.84%   |
| WDC WD2002FAEX-007BA0 2TB                      | 1         | 1      | 0.84%   |
| WDC WD1600BJKT-75F4T0 160GB                    | 1         | 1      | 0.84%   |
| WDC WD10JUCT-63CYNY0 1TB                       | 1         | 1      | 0.84%   |
| WDC WD10EZEX-60ZF5A0 1TB                       | 1         | 1      | 0.84%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 1      | 0.84%   |
| WDC WD10EADX-22TDHB0 1TB                       | 1         | 1      | 0.84%   |
| WDC WD10EADS-22M2B0 1TB                        | 1         | 1      | 0.84%   |
| Vaseky V800/60G 64GB                           | 1         | 1      | 0.84%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 0.84%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 0.84%   |
| Toshiba MK8052GSX 80GB                         | 1         | 1      | 0.84%   |
| Toshiba MK7575GSX 752GB                        | 1         | 1      | 0.84%   |
| Toshiba MK1652GSX 160GB                        | 1         | 1      | 0.84%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD        | 1         | 1      | 0.84%   |
| Toshiba HDWA120 2TB                            | 1         | 1      | 0.84%   |
| Toshiba DT01ACA100 1TB                         | 1         | 1      | 0.84%   |
| Toshiba DT01ABA200 2TB                         | 1         | 1      | 0.84%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 28     | 21.55%  |
| WDC                 | 22        | 25     | 18.97%  |
| Samsung Electronics | 11        | 14     | 9.48%   |
| Kingston            | 10        | 11     | 8.62%   |
| Toshiba             | 9         | 9      | 7.76%   |
| Hitachi             | 9         | 17     | 7.76%   |
| Micron Technology   | 5         | 7      | 4.31%   |
| Intel               | 5         | 5      | 4.31%   |
| HGST                | 5         | 5      | 4.31%   |
| Maxtor              | 3         | 3      | 2.59%   |
| SK hynix            | 2         | 2      | 1.72%   |
| Fujitsu             | 2         | 3      | 1.72%   |
| Vaseky              | 1         | 1      | 0.86%   |
| SanDisk             | 1         | 1      | 0.86%   |
| PNY                 | 1         | 1      | 0.86%   |
| OCZ                 | 1         | 1      | 0.86%   |
| LITEONIT            | 1         | 1      | 0.86%   |
| Corsair             | 1         | 1      | 0.86%   |
| ATP                 | 1         | 1      | 0.86%   |
| A-DATA Technology   | 1         | 1      | 0.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 28     | 32.47%  |
| WDC                 | 21        | 24     | 27.27%  |
| Hitachi             | 9         | 17     | 11.69%  |
| Toshiba             | 8         | 8      | 10.39%  |
| HGST                | 5         | 5      | 6.49%   |
| Samsung Electronics | 4         | 5      | 5.19%   |
| Maxtor              | 3         | 3      | 3.9%    |
| Fujitsu             | 2         | 3      | 2.6%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 75        | 93     | 65.22%  |
| SSD  | 34        | 37     | 29.57%  |
| NVMe | 6         | 7      | 5.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3250318AS 250GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 651       | 1394   | 52.12%  |
| Works    | 485       | 1014   | 38.83%  |
| Malfunc  | 112       | 137    | 8.97%   |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 732       | 50.21%  |
| AMD                              | 256       | 17.56%  |
| Samsung Electronics              | 144       | 9.88%   |
| SanDisk                          | 43        | 2.95%   |
| SK hynix                         | 39        | 2.67%   |
| ASMedia Technology               | 34        | 2.33%   |
| Nvidia                           | 32        | 2.19%   |
| Kingston Technology Company      | 28        | 1.92%   |
| JMicron Technology               | 23        | 1.58%   |
| Toshiba America Info Systems     | 20        | 1.37%   |
| Phison Electronics               | 20        | 1.37%   |
| ADATA Technology                 | 16        | 1.1%    |
| Marvell Technology Group         | 13        | 0.89%   |
| KIOXIA                           | 10        | 0.69%   |
| Micron Technology                | 8         | 0.55%   |
| VIA Technologies                 | 6         | 0.41%   |
| Broadcom / LSI                   | 5         | 0.34%   |
| Union Memory (Shenzhen)          | 4         | 0.27%   |
| Seagate Technology               | 4         | 0.27%   |
| LSI Logic / Symbios Logic        | 4         | 0.27%   |
| Silicon Integrated Systems [SiS] | 3         | 0.21%   |
| Realtek Semiconductor            | 3         | 0.21%   |
| Solid State Storage Technology   | 2         | 0.14%   |
| Micron/Crucial Technology        | 2         | 0.14%   |
| Lenovo                           | 2         | 0.14%   |
| Yangtze Memory Technologies      | 1         | 0.07%   |
| Silicon Motion                   | 1         | 0.07%   |
| Lite-On Technology               | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |
| Adaptec                          | 1         | 0.07%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                            | Computers | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 167       | 9.74%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 85        | 4.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 59        | 3.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 48        | 2.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 45        | 2.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 43        | 2.51%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 43        | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 36        | 2.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 36        | 2.1%    |
| AMD 400 Series Chipset SATA Controller                                           | 36        | 2.1%    |
| ASMedia ASM1062 Serial ATA Controller                                            | 32        | 1.87%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 30        | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 30        | 1.75%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 27        | 1.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 25        | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 25        | 1.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 25        | 1.46%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 23        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 22        | 1.28%   |
| AMD 500 Series Chipset SATA Controller                                           | 21        | 1.22%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 19        | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 19        | 1.11%   |
| Intel SSD 660P Series                                                            | 18        | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 18        | 1.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 17        | 0.99%   |
| Kingston Company A2000 NVMe SSD                                                  | 17        | 0.99%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 17        | 0.99%   |
| Intel SATA Controller [RAID mode]                                                | 17        | 0.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 17        | 0.99%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 16        | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                           | 16        | 0.93%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 14        | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                              | 14        | 0.82%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 14        | 0.82%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 13        | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 13        | 0.76%   |
| Phison E12 NVMe Controller                                                       | 13        | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 13        | 0.76%   |
| Nvidia MCP61 SATA Controller                                                     | 12        | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 12        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 875       | 59.16%  |
| NVMe | 353       | 23.87%  |
| IDE  | 180       | 12.17%  |
| RAID | 62        | 4.19%   |
| SAS  | 6         | 0.41%   |
| SCSI | 3         | 0.2%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 830       | 71.92%  |
| AMD          | 312       | 27.04%  |
| ARM          | 10        | 0.87%   |
| QUALCOMM     | 1         | 0.09%   |
| CentaurHauls | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz       | 16        | 1.38%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 15        | 1.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz       | 13        | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 13        | 1.12%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 13        | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 1.04%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 11        | 0.95%   |
| AMD Ryzen 5 3600 6-Core Processor       | 11        | 0.95%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 10        | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 9         | 0.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 9         | 0.78%   |
| Intel Core i5-3470 CPU @ 3.20GHz        | 9         | 0.78%   |
| AMD Ryzen 7 1700 Eight-Core Processor   | 9         | 0.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz        | 8         | 0.69%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 8         | 0.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 0.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz       | 7         | 0.61%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 7         | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 7         | 0.61%   |
| Intel Core i5-6600K CPU @ 3.50GHz       | 7         | 0.61%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 7         | 0.61%   |
| Intel Core i5-2400 CPU @ 3.10GHz        | 7         | 0.61%   |
| ARM Processor                           | 7         | 0.61%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 7         | 0.61%   |
| AMD Ryzen 5 2600 Six-Core Processor     | 7         | 0.61%   |
| AMD FX-8350 Eight-Core Processor        | 7         | 0.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 0.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 6         | 0.52%   |
| Intel Core i5-6500 CPU @ 3.20GHz        | 6         | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 6         | 0.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 6         | 0.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 6         | 0.52%   |
| Intel Core i5-2500K CPU @ 3.30GHz       | 6         | 0.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 6         | 0.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 6         | 0.52%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 6         | 0.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 0.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 6         | 0.52%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 6         | 0.52%   |
| Intel Core i7-8700K CPU @ 3.70GHz       | 5         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 290       | 25.13%  |
| Intel Core i7                  | 200       | 17.33%  |
| Intel Core i3                  | 65        | 5.63%   |
| AMD Ryzen 7                    | 61        | 5.29%   |
| AMD Ryzen 5                    | 60        | 5.2%    |
| Intel Celeron                  | 58        | 5.03%   |
| Intel Core 2 Duo               | 57        | 4.94%   |
| Other                          | 38        | 3.29%   |
| Intel Pentium                  | 33        | 2.86%   |
| AMD Ryzen 9                    | 29        | 2.51%   |
| Intel Xeon                     | 27        | 2.34%   |
| AMD FX                         | 20        | 1.73%   |
| Intel Atom                     | 18        | 1.56%   |
| Intel Pentium Dual-Core        | 14        | 1.21%   |
| AMD Ryzen 3                    | 13        | 1.13%   |
| AMD Athlon II X2               | 12        | 1.04%   |
| AMD Phenom II X4               | 10        | 0.87%   |
| AMD E1                         | 10        | 0.87%   |
| AMD Athlon 64 X2               | 9         | 0.78%   |
| AMD Ryzen 7 PRO                | 8         | 0.69%   |
| Intel Genuine                  | 7         | 0.61%   |
| Intel Core 2 Quad              | 7         | 0.61%   |
| AMD A8                         | 7         | 0.61%   |
| AMD A10                        | 7         | 0.61%   |
| Intel Core 2                   | 6         | 0.52%   |
| AMD A4                         | 6         | 0.52%   |
| Intel Core i9                  | 5         | 0.43%   |
| AMD Phenom                     | 5         | 0.43%   |
| Intel Pentium Dual             | 4         | 0.35%   |
| Intel Pentium 4                | 3         | 0.26%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.26%   |
| AMD Ryzen 3 PRO                | 3         | 0.26%   |
| AMD EPYC                       | 3         | 0.26%   |
| AMD E2                         | 3         | 0.26%   |
| AMD Athlon II X4               | 3         | 0.26%   |
| AMD Athlon                     | 3         | 0.26%   |
| AMD A6                         | 3         | 0.26%   |
| Intel Core Duo                 | 2         | 0.17%   |
| ARM BCM                        | 2         | 0.17%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 467       | 40.43%  |
| 4       | 429       | 37.14%  |
| 6       | 95        | 8.23%   |
| 8       | 84        | 7.27%   |
| 1       | 25        | 2.16%   |
| 12      | 18        | 1.56%   |
| 16      | 15        | 1.3%    |
| 3       | 11        | 0.95%   |
| 10      | 3         | 0.26%   |
| 24      | 2         | 0.17%   |
| 14      | 2         | 0.17%   |
| 80      | 1         | 0.09%   |
| 32      | 1         | 0.09%   |
| 5       | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1151      | 99.74%  |
| 2       | 2         | 0.17%   |
| Unknown | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 716       | 61.94%  |
| 1       | 439       | 37.98%  |
| Unknown | 1         | 0.09%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1126      | 97.24%  |
| Unknown        | 20        | 1.73%   |
| 32-bit         | 11        | 0.95%   |
| 64-bit         | 1         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 277       | 23.28%  |
| 0x206a7    | 72        | 6.05%   |
| 0x306a9    | 64        | 5.38%   |
| 0x306c3    | 55        | 4.62%   |
| 0x1067a    | 43        | 3.61%   |
| 0x506e3    | 41        | 3.45%   |
| 0x806ec    | 34        | 2.86%   |
| 0x806ea    | 24        | 2.02%   |
| 0x40651    | 24        | 2.02%   |
| 0x406e3    | 23        | 1.93%   |
| 0x906ea    | 21        | 1.76%   |
| 0x08701021 | 21        | 1.76%   |
| 0x906e9    | 19        | 1.6%    |
| 0x306d4    | 17        | 1.43%   |
| 0x30678    | 16        | 1.34%   |
| 0x20655    | 16        | 1.34%   |
| 0x10676    | 16        | 1.34%   |
| 0x406c4    | 15        | 1.26%   |
| 0x0a201016 | 15        | 1.26%   |
| 0x806e9    | 14        | 1.18%   |
| 0x20652    | 14        | 1.18%   |
| 0x0800820d | 14        | 1.18%   |
| 0x806c1    | 13        | 1.09%   |
| 0x6fd      | 13        | 1.09%   |
| 0x08701013 | 13        | 1.09%   |
| 0x06000852 | 12        | 1.01%   |
| 0x010000c8 | 12        | 1.01%   |
| 0x6fb      | 10        | 0.84%   |
| 0xa0652    | 9         | 0.76%   |
| 0x906eb    | 8         | 0.67%   |
| 0x506c9    | 8         | 0.67%   |
| 0x08600106 | 8         | 0.67%   |
| 0x706e5    | 7         | 0.59%   |
| 0x08108102 | 7         | 0.59%   |
| 0x06001119 | 7         | 0.59%   |
| 0x906ed    | 6         | 0.5%    |
| 0x806eb    | 6         | 0.5%    |
| 0x706a1    | 6         | 0.5%    |
| 0x08001138 | 6         | 0.5%    |
| 0x05000119 | 6         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 168       | 14.53%  |
| Haswell          | 111       | 9.6%    |
| SandyBridge      | 95        | 8.22%   |
| Skylake          | 79        | 6.83%   |
| IvyBridge        | 78        | 6.75%   |
| Zen 2            | 65        | 5.62%   |
| Penryn           | 62        | 5.36%   |
| Silvermont       | 41        | 3.55%   |
| Zen 3            | 40        | 3.46%   |
| Core             | 40        | 3.46%   |
| K10              | 37        | 3.2%    |
| Zen              | 36        | 3.11%   |
| Zen+             | 34        | 2.94%   |
| Westmere         | 34        | 2.94%   |
| Unknown          | 29        | 2.51%   |
| Piledriver       | 26        | 2.25%   |
| Broadwell        | 21        | 1.82%   |
| K8 Hammer        | 19        | 1.64%   |
| CometLake        | 18        | 1.56%   |
| TigerLake        | 16        | 1.38%   |
| Icelake          | 14        | 1.21%   |
| Nehalem          | 12        | 1.04%   |
| Goldmont         | 10        | 0.87%   |
| Excavator        | 10        | 0.87%   |
| Puma             | 8         | 0.69%   |
| Goldmont plus    | 8         | 0.69%   |
| Bobcat           | 7         | 0.61%   |
| P6               | 6         | 0.52%   |
| Jaguar           | 6         | 0.52%   |
| Bonnell          | 6         | 0.52%   |
| Steamroller      | 5         | 0.43%   |
| NetBurst         | 5         | 0.43%   |
| K8 & K10 hybrid  | 4         | 0.35%   |
| Bulldozer        | 4         | 0.35%   |
| K10 Llano        | 1         | 0.09%   |
| Alderlake Hybrid | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 606       | 46.22%  |
| Nvidia                                       | 385       | 29.37%  |
| AMD                                          | 294       | 22.43%  |
| ASPEED Technology                            | 13        | 0.99%   |
| Matrox Electronics Systems                   | 5         | 0.38%   |
| Silicon Motion                               | 3         | 0.23%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.23%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.08%   |
| VIA Technologies                             | 1         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 70        | 5.14%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 43        | 3.16%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 32        | 2.35%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 32        | 2.35%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 30        | 2.2%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 29        | 2.13%   |
| Intel UHD Graphics 620                                                                   | 26        | 1.91%   |
| Intel HD Graphics 530                                                                    | 26        | 1.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 25        | 1.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 1.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 21        | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 1.47%   |
| AMD Renoir                                                                               | 20        | 1.47%   |
| Intel HD Graphics 620                                                                    | 18        | 1.32%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 18        | 1.32%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 17        | 1.25%   |
| Intel HD Graphics 5500                                                                   | 16        | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.18%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 14        | 1.03%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 14        | 1.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 14        | 1.03%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 13        | 0.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11        | 0.81%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 11        | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.73%   |
| Nvidia GT218 [GeForce 210]                                                               | 10        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 10        | 0.73%   |
| Intel HD Graphics 630                                                                    | 10        | 0.73%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 10        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 10        | 0.73%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 9         | 0.66%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 9         | 0.66%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 8         | 0.59%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 8         | 0.59%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 8         | 0.59%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 470       | 40.31%  |
| 1 x Nvidia         | 261       | 22.38%  |
| 1 x AMD            | 239       | 20.5%   |
| Intel + Nvidia     | 99        | 8.49%   |
| Intel + AMD        | 19        | 1.63%   |
| 2 x AMD            | 18        | 1.54%   |
| AMD + Nvidia       | 17        | 1.46%   |
| 1 x ASPEED         | 13        | 1.11%   |
| Other              | 10        | 0.86%   |
| 2 x Nvidia         | 6         | 0.51%   |
| 1 x Matrox         | 4         | 0.34%   |
| 1 x SiS            | 3         | 0.26%   |
| 1 x Silicon Motion | 3         | 0.26%   |
| 2 x Intel          | 1         | 0.09%   |
| 1 x XGI            | 1         | 0.09%   |
| 1 x VIA            | 1         | 0.09%   |
| Nvidia + Matrox    | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 877       | 74.83%  |
| Proprietary | 232       | 19.8%   |
| Unknown     | 63        | 5.38%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 637       | 53.76%  |
| 0.01-0.5   | 135       | 11.39%  |
| 1.01-2.0   | 130       | 10.97%  |
| 0.51-1.0   | 83        | 7%      |
| 3.01-4.0   | 80        | 6.75%   |
| 7.01-8.0   | 71        | 5.99%   |
| 5.01-6.0   | 25        | 2.11%   |
| 2.01-3.0   | 11        | 0.93%   |
| 8.01-16.0  | 9         | 0.76%   |
| 16.01-24.0 | 4         | 0.34%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 195       | 15.22%  |
| AU Optronics            | 142       | 11.09%  |
| LG Display              | 116       | 9.06%   |
| Chimei Innolux          | 72        | 5.62%   |
| Dell                    | 71        | 5.54%   |
| BenQ                    | 66        | 5.15%   |
| Hewlett-Packard         | 60        | 4.68%   |
| BOE                     | 59        | 4.61%   |
| Acer                    | 55        | 4.29%   |
| Ancor Communications    | 53        | 4.14%   |
| Lenovo                  | 51        | 3.98%   |
| Goldstar                | 46        | 3.59%   |
| Fujitsu Siemens         | 21        | 1.64%   |
| Philips                 | 20        | 1.56%   |
| Apple                   | 20        | 1.56%   |
| AOC                     | 20        | 1.56%   |
| Sony                    | 19        | 1.48%   |
| ASUSTek Computer        | 19        | 1.48%   |
| Sharp                   | 17        | 1.33%   |
| ViewSonic               | 14        | 1.09%   |
| InfoVision              | 14        | 1.09%   |
| Eizo                    | 10        | 0.78%   |
| Chi Mei Optoelectronics | 9         | 0.7%    |
| LG Philips              | 8         | 0.62%   |
| Vestel Elektronik       | 6         | 0.47%   |
| Unknown                 | 6         | 0.47%   |
| Toshiba                 | 6         | 0.47%   |
| LG Electronics          | 6         | 0.47%   |
| CSO                     | 6         | 0.47%   |
| Panasonic               | 5         | 0.39%   |
| PANDA                   | 4         | 0.31%   |
| FUS                     | 4         | 0.31%   |
| CPT                     | 4         | 0.31%   |
| Packard Bell            | 3         | 0.23%   |
| Onkyo                   | 3         | 0.23%   |
| NEC Computers           | 3         | 0.23%   |
| Lenovo Group Limited    | 3         | 0.23%   |
| Iiyama                  | 3         | 0.23%   |
| IBM                     | 3         | 0.23%   |
| Valve                   | 2         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.53%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.53%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 890x500mm 40.2-inch  | 6         | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.45%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.38%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 5         | 0.38%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 5         | 0.38%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 4         | 0.3%    |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 4         | 0.3%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 4         | 0.3%    |
| LG Display LCD Monitor LGD01DD 1600x900 382x215mm 17.3-inch           | 4         | 0.3%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch               | 4         | 0.3%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 4         | 0.3%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14A7 1920x1080 308x173mm 13.9-inch      | 4         | 0.3%    |
| BenQ XL2411Z BNQ7F32 1920x1080 531x298mm 24.0-inch                    | 4         | 0.3%    |
| BenQ XL2411Z BNQ7F31 1920x1080 531x298mm 24.0-inch                    | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 4         | 0.3%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 4         | 0.3%    |
| Ancor Communications VE247 ACI2493 1920x1080 530x300mm 24.0-inch      | 4         | 0.3%    |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 4         | 0.3%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 3         | 0.23%   |
| Samsung Electronics T24D390 SAM0B6C 1920x1080 521x293mm 23.5-inch     | 3         | 0.23%   |
| Samsung Electronics SyncMaster SAM027F 1680x1050 474x296mm 22.0-inch  | 3         | 0.23%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 340x190mm 15.3-inch  | 3         | 0.23%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                     | 3         | 0.23%   |
| Samsung Electronics CF791 SAM0DC4 3440x1440 797x333mm 34.0-inch       | 3         | 0.23%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 3         | 0.23%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 3         | 0.23%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.23%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 3         | 0.23%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 3         | 0.23%   |
| Lenovo P27h-20 LEN61E9 2560x1440 609x349mm 27.6-inch                  | 3         | 0.23%   |
| Lenovo LEN L27q-10 LEN65CE 2560x1440 597x336mm 27.0-inch              | 3         | 0.23%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 3         | 0.23%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 3         | 0.23%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 3         | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 513       | 41.64%  |
| 1366x768 (WXGA)    | 154       | 12.5%   |
| 3840x2160 (4K)     | 80        | 6.49%   |
| 2560x1440 (QHD)    | 75        | 6.09%   |
| 1920x1200 (WUXGA)  | 61        | 4.95%   |
| 1680x1050 (WSXGA+) | 56        | 4.55%   |
| 1600x900 (HD+)     | 54        | 4.38%   |
| 1280x1024 (SXGA)   | 46        | 3.73%   |
| 1440x900 (WXGA+)   | 31        | 2.52%   |
| 1280x800 (WXGA)    | 29        | 2.35%   |
| Unknown            | 26        | 2.11%   |
| 3440x1440          | 16        | 1.3%    |
| 1360x768           | 13        | 1.06%   |
| 3840x1080          | 10        | 0.81%   |
| 3840x2400          | 6         | 0.49%   |
| 2560x1600          | 6         | 0.49%   |
| 1600x1200          | 5         | 0.41%   |
| 4480x1440          | 4         | 0.32%   |
| 1920x540           | 4         | 0.32%   |
| 1280x720 (HD)      | 4         | 0.32%   |
| 1024x600           | 4         | 0.32%   |
| 3200x1800 (QHD+)   | 3         | 0.24%   |
| 2560x1080          | 3         | 0.24%   |
| 5760x2160          | 2         | 0.16%   |
| 5120x1440          | 2         | 0.16%   |
| 3840x1200          | 2         | 0.16%   |
| 3360x1050          | 2         | 0.16%   |
| 2880x1800          | 2         | 0.16%   |
| 1400x1050          | 2         | 0.16%   |
| 800x1280           | 1         | 0.08%   |
| 5760x1440          | 1         | 0.08%   |
| 5280x1080          | 1         | 0.08%   |
| 3840x1600          | 1         | 0.08%   |
| 3520x1200          | 1         | 0.08%   |
| 3000x2000          | 1         | 0.08%   |
| 2800x1752          | 1         | 0.08%   |
| 2736x1824          | 1         | 0.08%   |
| 2560x2880          | 1         | 0.08%   |
| 2304x1440          | 1         | 0.08%   |
| 2160x1200          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 238       | 18.81%  |
| 24      | 132       | 10.43%  |
| 13      | 111       | 8.77%   |
| 27      | 107       | 8.46%   |
| 14      | 107       | 8.46%   |
| 23      | 97        | 7.67%   |
| Unknown | 91        | 7.19%   |
| 17      | 60        | 4.74%   |
| 22      | 40        | 3.16%   |
| 19      | 38        | 3%      |
| 12      | 33        | 2.61%   |
| 21      | 31        | 2.45%   |
| 31      | 26        | 2.06%   |
| 84      | 20        | 1.58%   |
| 34      | 15        | 1.19%   |
| 11      | 15        | 1.19%   |
| 18      | 14        | 1.11%   |
| 32      | 11        | 0.87%   |
| 20      | 11        | 0.87%   |
| 25      | 10        | 0.79%   |
| 72      | 9         | 0.71%   |
| 55      | 5         | 0.4%    |
| 40      | 5         | 0.4%    |
| 54      | 4         | 0.32%   |
| 28      | 4         | 0.32%   |
| 26      | 4         | 0.32%   |
| 10      | 4         | 0.32%   |
| 75      | 3         | 0.24%   |
| 65      | 3         | 0.24%   |
| 16      | 3         | 0.24%   |
| 48      | 2         | 0.16%   |
| 29      | 2         | 0.16%   |
| 66      | 1         | 0.08%   |
| 58      | 1         | 0.08%   |
| 49      | 1         | 0.08%   |
| 47      | 1         | 0.08%   |
| 46      | 1         | 0.08%   |
| 39      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |
| 36      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 404       | 32.85%  |
| 501-600     | 302       | 24.55%  |
| 201-300     | 106       | 8.62%   |
| 401-500     | 98        | 7.97%   |
| 351-400     | 95        | 7.72%   |
| Unknown     | 91        | 7.4%    |
| 601-700     | 49        | 3.98%   |
| 1501-2000   | 32        | 2.6%    |
| 701-800     | 28        | 2.28%   |
| 1001-1500   | 17        | 1.38%   |
| 801-900     | 7         | 0.57%   |
| 1-100       | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 788       | 68.94%  |
| 16/10   | 192       | 16.8%   |
| Unknown | 75        | 6.56%   |
| 5/4     | 44        | 3.85%   |
| 21/9    | 18        | 1.57%   |
| 4/3     | 8         | 0.7%    |
| 3/2     | 8         | 0.7%    |
| 32/9    | 4         | 0.35%   |
| 6/5     | 2         | 0.17%   |
| 0.89    | 1         | 0.09%   |
| 0.67    | 1         | 0.09%   |
| 0.62    | 1         | 0.09%   |
| 0.45    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 238       | 19.12%  |
| 201-250        | 219       | 17.59%  |
| 81-90          | 174       | 13.98%  |
| 301-350        | 110       | 8.84%   |
| Unknown        | 91        | 7.31%   |
| 251-300        | 69        | 5.54%   |
| 151-200        | 61        | 4.9%    |
| 351-500        | 58        | 4.66%   |
| More than 1000 | 46        | 3.69%   |
| 71-80          | 43        | 3.45%   |
| 121-130        | 42        | 3.37%   |
| 61-70          | 33        | 2.65%   |
| 141-150        | 18        | 1.45%   |
| 51-60          | 15        | 1.2%    |
| 501-1000       | 12        | 0.96%   |
| 131-140        | 7         | 0.56%   |
| 41-50          | 4         | 0.32%   |
| 111-120        | 4         | 0.32%   |
| 1-40           | 1         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 432       | 35.7%   |
| 121-160       | 331       | 27.36%  |
| 101-120       | 255       | 21.07%  |
| Unknown       | 91        | 7.52%   |
| 161-240       | 50        | 4.13%   |
| 1-50          | 31        | 2.56%   |
| More than 240 | 20        | 1.65%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 898       | 76.04%  |
| 2     | 190       | 16.09%  |
| 0     | 67        | 5.67%   |
| 3     | 24        | 2.03%   |
| 4     | 2         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 621       | 35.75%  |
| Realtek Semiconductor                  | 511       | 29.42%  |
| Qualcomm Atheros                       | 159       | 9.15%   |
| Broadcom                               | 90        | 5.18%   |
| Huawei Technologies                    | 25        | 1.44%   |
| Nvidia                                 | 24        | 1.38%   |
| Marvell Technology Group               | 24        | 1.38%   |
| Ralink                                 | 22        | 1.27%   |
| MediaTek                               | 20        | 1.15%   |
| TP-Link                                | 19        | 1.09%   |
| Ericsson Business Mobile Networks      | 18        | 1.04%   |
| Hewlett-Packard                        | 17        | 0.98%   |
| Broadcom Limited                       | 17        | 0.98%   |
| ASUSTek Computer                       | 16        | 0.92%   |
| Samsung Electronics                    | 14        | 0.81%   |
| Ralink Technology                      | 12        | 0.69%   |
| Dell                                   | 9         | 0.52%   |
| ZyXEL Communications                   | 7         | 0.4%    |
| Microsoft                              | 7         | 0.4%    |
| Lenovo                                 | 7         | 0.4%    |
| Sierra Wireless                        | 6         | 0.35%   |
| OnePlus Technology (Shenzhen)          | 6         | 0.35%   |
| Microchip Technology                   | 5         | 0.29%   |
| Fibocom                                | 5         | 0.29%   |
| D-Link System                          | 5         | 0.29%   |
| ASIX Electronics                       | 5         | 0.29%   |
| Motorola PCS                           | 4         | 0.23%   |
| HMD Global                             | 4         | 0.23%   |
| Xiaomi                                 | 3         | 0.17%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.17%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.17%   |
| Qualcomm                               | 3         | 0.17%   |
| Gemtek                                 | 3         | 0.17%   |
| BUFFALO                                | 3         | 0.17%   |
| Aquantia                               | 3         | 0.17%   |
| 3Com                                   | 3         | 0.17%   |
| Linksys                                | 2         | 0.12%   |
| Edimax Technology                      | 2         | 0.12%   |
| DisplayLink                            | 2         | 0.12%   |
| D-Link                                 | 2         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 383       | 18.3%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 3.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 2.05%   |
| Intel Wi-Fi 6 AX200                                               | 41        | 1.96%   |
| Intel I211 Gigabit Network Connection                             | 40        | 1.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 38        | 1.82%   |
| Intel Wireless 8265 / 8275                                        | 30        | 1.43%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 29        | 1.39%   |
| Intel Wireless 7260                                               | 28        | 1.34%   |
| Intel Wireless 7265                                               | 26        | 1.24%   |
| Intel Wireless 8260                                               | 25        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 22        | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 1%      |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 21        | 1%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 20        | 0.96%   |
| Intel I210 Gigabit Network Connection                             | 18        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 0.81%   |
| Intel Wi-Fi 6 AX201                                               | 16        | 0.76%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 16        | 0.76%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 15        | 0.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 14        | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 14        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 13        | 0.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 13        | 0.62%   |
| Intel Ethernet Controller I225-V                                  | 12        | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 0.57%   |
| Intel Centrino Ultimate-N 6300                                    | 12        | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 11        | 0.53%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 11        | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 11        | 0.53%   |
| Intel Wireless 3165                                               | 11        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 416       | 48.09%  |
| Qualcomm Atheros                | 131       | 15.14%  |
| Realtek Semiconductor           | 111       | 12.83%  |
| Broadcom                        | 59        | 6.82%   |
| Ralink                          | 22        | 2.54%   |
| TP-Link                         | 18        | 2.08%   |
| MediaTek                        | 16        | 1.85%   |
| ASUSTek Computer                | 16        | 1.85%   |
| Ralink Technology               | 12        | 1.39%   |
| Broadcom Limited                | 10        | 1.16%   |
| ZyXEL Communications            | 7         | 0.81%   |
| Microsoft                       | 7         | 0.81%   |
| Sierra Wireless                 | 6         | 0.69%   |
| Hewlett-Packard                 | 6         | 0.69%   |
| Fibocom                         | 5         | 0.58%   |
| Dell                            | 5         | 0.58%   |
| D-Link System                   | 4         | 0.46%   |
| Gemtek                          | 3         | 0.35%   |
| BUFFALO                         | 3         | 0.35%   |
| Edimax Technology               | 2         | 0.23%   |
| ZyDAS                           | 1         | 0.12%   |
| Qualcomm Atheros Communications | 1         | 0.12%   |
| NetGear                         | 1         | 0.12%   |
| Marvell Technology Group        | 1         | 0.12%   |
| Linksys                         | 1         | 0.12%   |
| D-Link                          | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 41        | 4.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 38        | 4.38%   |
| Intel Wireless 8265 / 8275                                              | 30        | 3.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 3.34%   |
| Intel Wireless 7260                                                     | 28        | 3.23%   |
| Intel Wireless 7265                                                     | 26        | 3%      |
| Intel Wireless 8260                                                     | 25        | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 2.54%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 21        | 2.42%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 2.31%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 17        | 1.96%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 1.85%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 1.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 15        | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 14        | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 1.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 1.5%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 1.38%   |
| Intel Centrino Ultimate-N 6300                                          | 12        | 1.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 1.27%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 11        | 1.27%   |
| Intel Wireless 3165                                                     | 11        | 1.27%   |
| Intel Centrino Advanced-N 6235                                          | 11        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 11        | 1.27%   |
| Intel Wireless-AC 9260                                                  | 10        | 1.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 1.04%   |
| Intel Wireless 3160                                                     | 9         | 1.04%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.92%   |
| Intel Centrino Advanced-N 6200                                          | 8         | 0.92%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 8         | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.92%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.81%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.81%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.81%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                      | 7         | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 479       | 42.09%  |
| Intel                                  | 426       | 37.43%  |
| Broadcom                               | 42        | 3.69%   |
| Qualcomm Atheros                       | 39        | 3.43%   |
| Nvidia                                 | 24        | 2.11%   |
| Marvell Technology Group               | 23        | 2.02%   |
| Huawei Technologies                    | 18        | 1.58%   |
| Samsung Electronics                    | 14        | 1.23%   |
| Lenovo                                 | 7         | 0.62%   |
| Broadcom Limited                       | 7         | 0.62%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.44%   |
| ASIX Electronics                       | 5         | 0.44%   |
| MediaTek                               | 4         | 0.35%   |
| HMD Global                             | 4         | 0.35%   |
| Xiaomi                                 | 3         | 0.26%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.26%   |
| Silicon Integrated Systems [SiS]       | 3         | 0.26%   |
| Qualcomm                               | 3         | 0.26%   |
| Aquantia                               | 3         | 0.26%   |
| 3Com                                   | 3         | 0.26%   |
| TP-Link                                | 2         | 0.18%   |
| Motorola PCS                           | 2         | 0.18%   |
| Hewlett-Packard                        | 2         | 0.18%   |
| DisplayLink                            | 2         | 0.18%   |
| VIA Technologies                       | 1         | 0.09%   |
| Standard Microsystems                  | 1         | 0.09%   |
| OPPO Electronics                       | 1         | 0.09%   |
| Microchip Technology                   | 1         | 0.09%   |
| Linksys                                | 1         | 0.09%   |
| ICS Advent                             | 1         | 0.09%   |
| Google                                 | 1         | 0.09%   |
| Foxconn / Hon Hai                      | 1         | 0.09%   |
| D-Link System                          | 1         | 0.09%   |
| D-Link                                 | 1         | 0.09%   |
| Attansic Technology                    | 1         | 0.09%   |
| Apple                                  | 1         | 0.09%   |
| American Megatrends                    | 1         | 0.09%   |
| AMD                                    | 1         | 0.09%   |
| ADMtek                                 | 1         | 0.09%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 383       | 32.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 76        | 6.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 43        | 3.69%   |
| Intel I211 Gigabit Network Connection                             | 40        | 3.43%   |
| Intel Ethernet Connection (2) I219-V                              | 24        | 2.06%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 1.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 21        | 1.8%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 20        | 1.72%   |
| Intel I210 Gigabit Network Connection                             | 18        | 1.54%   |
| Intel Ethernet Connection (6) I219-V                              | 16        | 1.37%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 1.37%   |
| Intel 82579V Gigabit Network Connection                           | 14        | 1.2%    |
| Intel Ethernet Controller I225-V                                  | 12        | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.03%   |
| Nvidia MCP61 Ethernet                                             | 11        | 0.94%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.94%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.94%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 0.86%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.86%   |
| Intel Ethernet Connection (2) I218-V                              | 10        | 0.86%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 10        | 0.86%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.86%   |
| Huawei STK-L21                                                    | 10        | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.77%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.69%   |
| Intel I350 Gigabit Network Connection                             | 8         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                          | 8         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 7         | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.6%    |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.6%    |
| Huawei E353/E3131                                                 | 6         | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.43%   |
| OnePlus (Shenzhen) OnePlus                                        | 5         | 0.43%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 0.43%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 0.43%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1035      | 54.36%  |
| WiFi     | 812       | 42.65%  |
| Modem    | 53        | 2.78%   |
| Unknown  | 4         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 591       | 50.77%  |
| Ethernet | 572       | 49.14%  |
| Unknown  | 1         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 628       | 54.09%  |
| 1     | 471       | 40.57%  |
| 3     | 26        | 2.24%   |
| 0     | 25        | 2.15%   |
| 4     | 6         | 0.52%   |
| 5     | 5         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 983       | 82.88%  |
| Yes  | 203       | 17.12%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 299       | 45.72%  |
| Broadcom                        | 56        | 8.56%   |
| Realtek Semiconductor           | 46        | 7.03%   |
| Cambridge Silicon Radio         | 44        | 6.73%   |
| Qualcomm Atheros Communications | 40        | 6.12%   |
| ASUSTek Computer                | 35        | 5.35%   |
| IMC Networks                    | 24        | 3.67%   |
| Apple                           | 23        | 3.52%   |
| Foxconn / Hon Hai               | 21        | 3.21%   |
| Lite-On Technology              | 15        | 2.29%   |
| Hewlett-Packard                 | 13        | 1.99%   |
| Dell                            | 9         | 1.38%   |
| Askey Computer                  | 6         | 0.92%   |
| Ralink                          | 4         | 0.61%   |
| HTC (High Tech Computer)        | 4         | 0.61%   |
| Foxconn International           | 4         | 0.61%   |
| MediaTek                        | 2         | 0.31%   |
| Edimax Technology               | 2         | 0.31%   |
| Toshiba                         | 1         | 0.15%   |
| Taiyo Yuden                     | 1         | 0.15%   |
| Realtek                         | 1         | 0.15%   |
| Marvell Semiconductor           | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |
| Belkin Components               | 1         | 0.15%   |
| Alps Electric                   | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 124       | 18.93%  |
| Intel AX201 Bluetooth                                                | 51        | 7.79%   |
| Intel AX200 Bluetooth                                                | 45        | 6.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 44        | 6.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 34        | 5.19%   |
| Realtek Bluetooth Radio                                              | 24        | 3.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 21        | 3.21%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 15        | 2.29%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 14        | 2.14%   |
| Qualcomm Atheros  Bluetooth Device                                   | 14        | 2.14%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 13        | 1.98%   |
| Broadcom BCM2045B (BDC-2.1)                                          | 12        | 1.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 11        | 1.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 10        | 1.53%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 9         | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 9         | 1.37%   |
| IMC Networks Bluetooth Device                                        | 9         | 1.37%   |
| Apple Bluetooth USB Host Controller                                  | 8         | 1.22%   |
| IMC Networks Bluetooth Radio                                         | 7         | 1.07%   |
| HP Broadcom 2070 Bluetooth Combo                                     | 7         | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                                   | 7         | 1.07%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                        | 6         | 0.92%   |
| Foxconn / Hon Hai Wireless_Device                                    | 6         | 0.92%   |
| Broadcom HP Portable Bumble Bee                                      | 6         | 0.92%   |
| Askey Bluetooth Device                                               | 6         | 0.92%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 6         | 0.92%   |
| Realtek RTL8723B Bluetooth                                           | 5         | 0.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 5         | 0.76%   |
| Lite-On Bluetooth Device                                             | 5         | 0.76%   |
| Apple Bluetooth Host Controller                                      | 5         | 0.76%   |
| Ralink RT3290 Bluetooth                                              | 4         | 0.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 4         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                                     | 4         | 0.61%   |
| Intel AX210 Bluetooth                                                | 4         | 0.61%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 4         | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module                    | 4         | 0.61%   |
| Broadcom HP Portable SoftSailing                                     | 4         | 0.61%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                   | 4         | 0.61%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                     | 4         | 0.61%   |
| Broadcom BCM2045 Bluetooth                                           | 4         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 777       | 47.26%  |
| AMD                                  | 337       | 20.5%   |
| Nvidia                               | 322       | 19.59%  |
| C-Media Electronics                  | 23        | 1.4%    |
| Logitech                             | 18        | 1.09%   |
| Creative Labs                        | 12        | 0.73%   |
| ASUSTek Computer                     | 10        | 0.61%   |
| Realtek Semiconductor                | 8         | 0.49%   |
| Kingston Technology                  | 8         | 0.49%   |
| Creative Technology                  | 8         | 0.49%   |
| Texas Instruments                    | 7         | 0.43%   |
| SteelSeries ApS                      | 7         | 0.43%   |
| GN Netcom                            | 7         | 0.43%   |
| Razer USA                            | 6         | 0.36%   |
| VIA Technologies                     | 5         | 0.3%    |
| RODE Microphones                     | 5         | 0.3%    |
| Plantronics                          | 5         | 0.3%    |
| Lenovo                               | 4         | 0.24%   |
| GYROCOM C&C                          | 4         | 0.24%   |
| Focusrite-Novation                   | 4         | 0.24%   |
| Blue Microphones                     | 4         | 0.24%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.18%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.18%   |
| Sennheiser Communications            | 3         | 0.18%   |
| M-Audio                              | 3         | 0.18%   |
| Corsair                              | 3         | 0.18%   |
| Turtle Beach                         | 2         | 0.12%   |
| SAVITECH                             | 2         | 0.12%   |
| Microsoft                            | 2         | 0.12%   |
| Hewlett-Packard                      | 2         | 0.12%   |
| DSEA A/S                             | 2         | 0.12%   |
| DigiTech                             | 2         | 0.12%   |
| Cambridge Audio                      | 2         | 0.12%   |
| AudioQuest                           | 2         | 0.12%   |
| ZOOM                                 | 1         | 0.06%   |
| Yamaha                               | 1         | 0.06%   |
| XMOS                                 | 1         | 0.06%   |
| Valve Software                       | 1         | 0.06%   |
| Trust                                | 1         | 0.06%   |
| Thomann                              | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 92        | 4.75%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 74        | 3.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 72        | 3.72%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 68        | 3.51%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 66        | 3.41%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 57        | 2.94%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 55        | 2.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 45        | 2.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 43        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 38        | 1.96%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 36        | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 34        | 1.76%   |
| AMD FCH Azalia Controller                                                                         | 34        | 1.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 34        | 1.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 33        | 1.7%    |
| Intel Cannon Lake PCH cAVS                                                                        | 33        | 1.7%    |
| Intel 8 Series HD Audio Controller                                                                | 32        | 1.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 1.6%    |
| Nvidia GP104 High Definition Audio Controller                                                     | 30        | 1.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 28        | 1.45%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 1.34%   |
| Intel 200 Series PCH HD Audio                                                                     | 26        | 1.34%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 23        | 1.19%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 23        | 1.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 22        | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 0.98%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 18        | 0.93%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 0.93%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 17        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 17        | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 16        | 0.83%   |
| Nvidia High Definition Audio Controller                                                           | 16        | 0.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 16        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 0.77%   |
| Intel CM238 HD Audio Controller                                                                   | 14        | 0.72%   |
| AMD Navi 10 HDMI Audio                                                                            | 14        | 0.72%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 13        | 0.67%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 13        | 0.67%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 13        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 187       | 24.87%  |
| Kingston            | 146       | 19.41%  |
| SK hynix            | 122       | 16.22%  |
| Unknown             | 69        | 9.18%   |
| Micron Technology   | 67        | 8.91%   |
| Corsair             | 40        | 5.32%   |
| G.Skill             | 32        | 4.26%   |
| Crucial             | 28        | 3.72%   |
| Elpida              | 14        | 1.86%   |
| Ramaxel Technology  | 12        | 1.6%    |
| A-DATA Technology   | 11        | 1.46%   |
| Nanya Technology    | 7         | 0.93%   |
| Qimonda             | 3         | 0.4%    |
| Team                | 2         | 0.27%   |
| Unknown (ABCD)      | 1         | 0.13%   |
| PUSKILL             | 1         | 0.13%   |
| pqi                 | 1         | 0.13%   |
| Patriot             | 1         | 0.13%   |
| Hitachi             | 1         | 0.13%   |
| GOODRAM             | 1         | 0.13%   |
| GIGA-BYTE           | 1         | 0.13%   |
| ChangXin Memory     | 1         | 0.13%   |
| ASint Technology    | 1         | 0.13%   |
| Apacer              | 1         | 0.13%   |
| 48spaces            | 1         | 0.13%   |
| Unknown             | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s     | 12        | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 9         | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s | 9         | 1.1%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 8         | 0.98%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s    | 8         | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 8         | 0.98%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 8         | 0.98%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s      | 7         | 0.86%   |
| Kingston RAM KHX1600C10D3/8G 8192MB DIMM DDR3 1600MT/s   | 7         | 0.86%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 6         | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 6         | 0.74%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s    | 6         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 5         | 0.61%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s | 5         | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 5         | 0.61%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 5         | 0.61%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 5         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR2                    | 4         | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 4         | 0.49%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s   | 4         | 0.49%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s    | 4         | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s    | 4         | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s    | 4         | 0.49%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s    | 4         | 0.49%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s   | 4         | 0.49%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 4         | 0.49%   |
| Kingston RAM KHX1600C10D3/4G 4GB DIMM DDR3 1866MT/s      | 4         | 0.49%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 3         | 0.37%   |
| Unknown RAM Module 2048MB SODIMM DDR2                    | 3         | 0.37%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s              | 3         | 0.37%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.37%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s   | 3         | 0.37%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s  | 3         | 0.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s   | 3         | 0.37%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s              | 3         | 0.37%   |
| Samsung RAM Module 2GB SODIMM DDR3 1333MT/s              | 3         | 0.37%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s    | 3         | 0.37%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 3         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 298       | 44.35%  |
| DDR3    | 243       | 36.16%  |
| DDR2    | 54        | 8.04%   |
| SDRAM   | 21        | 3.13%   |
| LPDDR3  | 16        | 2.38%   |
| LPDDR4  | 15        | 2.23%   |
| Unknown | 15        | 2.23%   |
| DDR     | 6         | 0.89%   |
| DDR5    | 3         | 0.45%   |
| DRAM    | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 344       | 51.65%  |
| DIMM         | 282       | 42.34%  |
| Row Of Chips | 32        | 4.8%    |
| Chip         | 4         | 0.6%    |
| RIMM         | 2         | 0.3%    |
| FB-DIMM      | 1         | 0.15%   |
| Unknown      | 1         | 0.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 248       | 34.4%   |
| 4096  | 201       | 27.88%  |
| 2048  | 109       | 15.12%  |
| 16384 | 94        | 13.04%  |
| 1024  | 33        | 4.58%   |
| 32768 | 31        | 4.3%    |
| 512   | 5         | 0.69%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 141       | 19.5%   |
| 2667    | 83        | 11.48%  |
| 3200    | 82        | 11.34%  |
| 1333    | 51        | 7.05%   |
| 2400    | 45        | 6.22%   |
| 2133    | 41        | 5.67%   |
| 667     | 33        | 4.56%   |
| 1334    | 29        | 4.01%   |
| 3600    | 28        | 3.87%   |
| 800     | 23        | 3.18%   |
| 1867    | 21        | 2.9%    |
| 3466    | 14        | 1.94%   |
| Unknown | 13        | 1.8%    |
| 1067    | 9         | 1.24%   |
| 4267    | 8         | 1.11%   |
| 2933    | 8         | 1.11%   |
| 4199    | 7         | 0.97%   |
| 3800    | 7         | 0.97%   |
| 3733    | 6         | 0.83%   |
| 1066    | 6         | 0.83%   |
| 3266    | 5         | 0.69%   |
| 3000    | 5         | 0.69%   |
| 2048    | 5         | 0.69%   |
| 533     | 5         | 0.69%   |
| 2800    | 4         | 0.55%   |
| 2200    | 4         | 0.55%   |
| 1866    | 4         | 0.55%   |
| 4800    | 3         | 0.41%   |
| 3866    | 3         | 0.41%   |
| 975     | 3         | 0.41%   |
| 49926   | 2         | 0.28%   |
| 4266    | 2         | 0.28%   |
| 3400    | 2         | 0.28%   |
| 3333    | 2         | 0.28%   |
| 3100    | 2         | 0.28%   |
| 2666    | 2         | 0.28%   |
| 1800    | 2         | 0.28%   |
| 1639    | 2         | 0.28%   |
| 8192    | 1         | 0.14%   |
| 4000    | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 10        | 34.48%  |
| Samsung Electronics   | 5         | 17.24%  |
| Canon                 | 4         | 13.79%  |
| Seiko Epson           | 3         | 10.34%  |
| Brother Industries    | 2         | 6.9%    |
| Xerox                 | 1         | 3.45%   |
| Prolific Technology   | 1         | 3.45%   |
| Pantum                | 1         | 3.45%   |
| Lexmark International | 1         | 3.45%   |
| Dell                  | 1         | 3.45%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-1660 Series              | 2         | 6.9%    |
| Xerox Phaser 6500DN                 | 1         | 3.45%   |
| Seiko Epson XP-510 Series           | 1         | 3.45%   |
| Seiko Epson Printer                 | 1         | 3.45%   |
| Seiko Epson L555 Series             | 1         | 3.45%   |
| Samsung M2020 Series                | 1         | 3.45%   |
| Samsung CLP-325 Color Laser Printer | 1         | 3.45%   |
| Samsung C43x Series                 | 1         | 3.45%   |
| Prolific PL2305 Parallel Port       | 1         | 3.45%   |
| Pantum P2500W series                | 1         | 3.45%   |
| Lexmark International 2400 series   | 1         | 3.45%   |
| HP PSC 1100 series                  | 1         | 3.45%   |
| HP OfficeJet Pro 69                 | 1         | 3.45%   |
| HP OfficeJet 5200 series            | 1         | 3.45%   |
| HP LaserJet Professional P 1102w    | 1         | 3.45%   |
| HP LaserJet Pro M148-M149           | 1         | 3.45%   |
| HP LaserJet P2055 series            | 1         | 3.45%   |
| HP LaserJet P2015 series            | 1         | 3.45%   |
| HP DeskJet F300 series              | 1         | 3.45%   |
| HP DeskJet 960c                     | 1         | 3.45%   |
| HP DeskJet 2130 series              | 1         | 3.45%   |
| Dell Laser Printer 1720             | 1         | 3.45%   |
| Canon TS3300 series                 | 1         | 3.45%   |
| Canon TS3100 series                 | 1         | 3.45%   |
| Canon PIXMA MG3100 Series           | 1         | 3.45%   |
| Canon LBP6000                       | 1         | 3.45%   |
| Brother MFC-7460DN                  | 1         | 3.45%   |
| Brother DCP-7055 scanner/printer    | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 5         | 83.33%  |
| Seiko Epson | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan N650U/N656U            | 2         | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 16.67%  |
| Canon CanoScan LiDE 200               | 1         | 16.67%  |
| Canon CanoScan LiDE 110               | 1         | 16.67%  |
| Canon CanoScan LiDE 100               | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 183       | 30.35%  |
| IMC Networks                           | 52        | 8.62%   |
| Microdia                               | 45        | 7.46%   |
| Logitech                               | 43        | 7.13%   |
| Acer                                   | 42        | 6.97%   |
| Realtek Semiconductor                  | 38        | 6.3%    |
| Sunplus Innovation Technology          | 25        | 4.15%   |
| Quanta                                 | 25        | 4.15%   |
| Cheng Uei Precision Industry (Foxlink) | 21        | 3.48%   |
| Suyin                                  | 19        | 3.15%   |
| Apple                                  | 19        | 3.15%   |
| Syntek                                 | 13        | 2.16%   |
| Lite-On Technology                     | 12        | 1.99%   |
| Silicon Motion                         | 9         | 1.49%   |
| Lenovo                                 | 9         | 1.49%   |
| Microsoft                              | 7         | 1.16%   |
| Samsung Electronics                    | 5         | 0.83%   |
| Z-Star Microelectronics                | 4         | 0.66%   |
| Primax Electronics                     | 4         | 0.66%   |
| Ricoh                                  | 3         | 0.5%    |
| ALi                                    | 3         | 0.5%    |
| Alcor Micro                            | 3         | 0.5%    |
| Importek                               | 2         | 0.33%   |
| DigiTech                               | 2         | 0.33%   |
| Valve Software                         | 1         | 0.17%   |
| Trust                                  | 1         | 0.17%   |
| SunplusIT                              | 1         | 0.17%   |
| STEREOLABS                             | 1         | 0.17%   |
| Sonix Technology                       | 1         | 0.17%   |
| OnePlus                                | 1         | 0.17%   |
| Omnivision                             | 1         | 0.17%   |
| MacroSilicon                           | 1         | 0.17%   |
| Luxvisions Innotech Limited            | 1         | 0.17%   |
| LG Electronics                         | 1         | 0.17%   |
| Hewlett-Packard                        | 1         | 0.17%   |
| Google                                 | 1         | 0.17%   |
| Generalplus Technology                 | 1         | 0.17%   |
| DJJHFA1BIF5595                         | 1         | 0.17%   |
| Creative Technology                    | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 46        | 7.6%    |
| Microdia Integrated_Webcam_HD            | 20        | 3.31%   |
| Acer Integrated Camera                   | 17        | 2.81%   |
| IMC Networks Integrated Camera           | 16        | 2.64%   |
| Realtek Integrated_Webcam_HD             | 13        | 2.15%   |
| IMC Networks USB2.0 HD UVC WebCam        | 12        | 1.98%   |
| Chicony HP HD Camera                     | 10        | 1.65%   |
| Logitech Webcam C270                     | 9         | 1.49%   |
| Chicony HP HD Webcam                     | 9         | 1.49%   |
| Chicony HD WebCam                        | 9         | 1.49%   |
| Syntek Integrated Camera                 | 8         | 1.32%   |
| Logitech HD Pro Webcam C920              | 8         | 1.32%   |
| Chicony FJ Camera                        | 7         | 1.16%   |
| Acer Lenovo EasyCamera                   | 7         | 1.16%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 6         | 0.99%   |
| Chicony USB2.0 HD UVC WebCam             | 6         | 0.99%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 6         | 0.99%   |
| Chicony Integrated Camera (1280x720@30)  | 6         | 0.99%   |
| Chicony EasyCamera                       | 6         | 0.99%   |
| Sunplus HD WebCam                        | 5         | 0.83%   |
| Samsung Galaxy A5 (MTP)                  | 5         | 0.83%   |
| Realtek USB Camera                       | 5         | 0.83%   |
| Realtek Lenovo EasyCamera                | 5         | 0.83%   |
| Quanta HP Webcam                         | 5         | 0.83%   |
| Microsoft LifeCam HD-3000                | 5         | 0.83%   |
| Lite-On Integrated Camera                | 5         | 0.83%   |
| Chicony Integrated HP HD Webcam          | 5         | 0.83%   |
| Chicony Integrated Camera [ThinkPad]     | 5         | 0.83%   |
| Apple FaceTime HD Camera (Built-in)      | 5         | 0.83%   |
| Sunplus Integrated_Webcam_HD             | 4         | 0.66%   |
| Quanta USB webcam                        | 4         | 0.66%   |
| Quanta HD User Facing                    | 4         | 0.66%   |
| Primax HP HD Webcam [Fixed]              | 4         | 0.66%   |
| Microdia Integrated Webcam               | 4         | 0.66%   |
| Logitech Webcam C930e                    | 4         | 0.66%   |
| Logitech StreamCam                       | 4         | 0.66%   |
| Lenovo UVC Camera                        | 4         | 0.66%   |
| Lenovo Integrated Webcam [R5U877]        | 4         | 0.66%   |
| Chicony VGA WebCam                       | 4         | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam            | 4         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 59        | 40.14%  |
| Synaptics                  | 32        | 21.77%  |
| Shenzhen Goodix Technology | 15        | 10.2%   |
| AuthenTec                  | 12        | 8.16%   |
| Upek                       | 11        | 7.48%   |
| STMicroelectronics         | 9         | 6.12%   |
| LighTuning Technology      | 6         | 4.08%   |
| Elan Microelectronics      | 2         | 1.36%   |
| Microsoft                  | 1         | 0.68%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 16        | 10.88%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 10.2%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 7.48%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 6.12%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 6.12%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 5.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 4.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 4.76%   |
| Shenzhen Goodix  FingerPrint Device                                        | 7         | 4.76%   |
| AuthenTec AES2810                                                          | 7         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 3.4%    |
| Shenzhen Goodix FingerPrint                                                | 5         | 3.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.4%    |
| Validity Sensors VFS491                                                    | 3         | 2.04%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.04%   |
| Unknown                                                                    | 3         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.36%   |
| Synaptics  WBDI                                                            | 2         | 1.36%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.36%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.36%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.68%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.68%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.68%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.68%   |
| Microsoft Fingerprint Reader                                               | 1         | 0.68%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.68%   |
| Elan ELAN:Fingerprint                                                      | 1         | 0.68%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.68%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 44        | 44.44%  |
| Broadcom                  | 29        | 29.29%  |
| Lenovo                    | 9         | 9.09%   |
| Upek                      | 6         | 6.06%   |
| SCM Microsystems          | 3         | 3.03%   |
| O2 Micro                  | 3         | 3.03%   |
| Fujitsu Siemens Computers | 3         | 3.03%   |
| OmniKey                   | 1         | 1.01%   |
| Advanced Card Systems     | 1         | 1.01%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 44        | 44.44%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 9.09%   |
| Broadcom 5880                                                                | 9         | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 6.06%   |
| Broadcom 58200                                                               | 6         | 6.06%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 4.04%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 3.03%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.03%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 3         | 3.03%   |
| OmniKey CardMan 1021                                                         | 1         | 1.01%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.01%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.01%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 796       | 67.69%  |
| 1     | 284       | 24.15%  |
| 2     | 76        | 6.46%   |
| 3     | 11        | 0.94%   |
| 5     | 4         | 0.34%   |
| 4     | 3         | 0.26%   |
| 6     | 2         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 146       | 29.74%  |
| Chipcard                 | 88        | 17.92%  |
| Graphics card            | 84        | 17.11%  |
| Net/wireless             | 57        | 11.61%  |
| Multimedia controller    | 19        | 3.87%   |
| Communication controller | 19        | 3.87%   |
| Camera                   | 12        | 2.44%   |
| Bluetooth                | 11        | 2.24%   |
| Unassigned class         | 10        | 2.04%   |
| Storage                  | 9         | 1.83%   |
| Net/ethernet             | 9         | 1.83%   |
| Sound                    | 7         | 1.43%   |
| Card reader              | 7         | 1.43%   |
| Storage/raid             | 3         | 0.61%   |
| Modem                    | 3         | 0.61%   |
| Firewire controller      | 3         | 0.61%   |
| Storage/nvme             | 1         | 0.2%    |
| Network                  | 1         | 0.2%    |
| Flash memory             | 1         | 0.2%    |
| Dvb card                 | 1         | 0.2%    |

