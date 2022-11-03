Linux in Norway - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Norway.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 496

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | X99A RAIDER                 | [36eda457da](https://linux-hardware.org/?probe=36eda457da) | Nov 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4e260473ba](https://linux-hardware.org/?probe=4e260473ba) | Nov 02, 2022 |
| MSI           | X99A RAIDER                 | [2f3428a435](https://linux-hardware.org/?probe=2f3428a435) | Nov 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cf7b016772](https://linux-hardware.org/?probe=cf7b016772) | Nov 01, 2022 |
| MSI           | X99A RAIDER                 | [2f41c9eaa5](https://linux-hardware.org/?probe=2f41c9eaa5) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5bd92395da](https://linux-hardware.org/?probe=5bd92395da) | Oct 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c8392f24d9](https://linux-hardware.org/?probe=c8392f24d9) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | [7ddd09eeec](https://linux-hardware.org/?probe=7ddd09eeec) | Oct 30, 2022 |
| MSI           | X99A RAIDER                 | [782207dfcf](https://linux-hardware.org/?probe=782207dfcf) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [75b050a9f0](https://linux-hardware.org/?probe=75b050a9f0) | Oct 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bd9367f2b7](https://linux-hardware.org/?probe=bd9367f2b7) | Oct 27, 2022 |
| MSI           | X299 SLI PLUS               | [4b79f3c1e6](https://linux-hardware.org/?probe=4b79f3c1e6) | Oct 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [317d318d85](https://linux-hardware.org/?probe=317d318d85) | Oct 26, 2022 |
| HP            | 828A                        | [2123f2610c](https://linux-hardware.org/?probe=2123f2610c) | Oct 24, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [da8a11aac5](https://linux-hardware.org/?probe=da8a11aac5) | Oct 19, 2022 |
| Gigabyte      | X99-UD7 WIFI-CF             | [9c484b6d22](https://linux-hardware.org/?probe=9c484b6d22) | Oct 18, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d53b4edda1](https://linux-hardware.org/?probe=d53b4edda1) | Oct 18, 2022 |
| ASRock        | Z97E-ITX/ac                 | [2ae712a746](https://linux-hardware.org/?probe=2ae712a746) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | [e8e5ae4784](https://linux-hardware.org/?probe=e8e5ae4784) | Oct 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [e618e79bd5](https://linux-hardware.org/?probe=e618e79bd5) | Oct 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2412a53d05](https://linux-hardware.org/?probe=2412a53d05) | Oct 12, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | [c3513de476](https://linux-hardware.org/?probe=c3513de476) | Oct 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [60037612c1](https://linux-hardware.org/?probe=60037612c1) | Oct 11, 2022 |
| MSI           | Z170-A PRO                  | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| Gigabyte      | B450 GAMING X               | [a297c351ed](https://linux-hardware.org/?probe=a297c351ed) | Oct 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [512c095e83](https://linux-hardware.org/?probe=512c095e83) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6a5822719f](https://linux-hardware.org/?probe=6a5822719f) | Oct 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [51c401fd4e](https://linux-hardware.org/?probe=51c401fd4e) | Oct 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [80a70e8f6e](https://linux-hardware.org/?probe=80a70e8f6e) | Oct 03, 2022 |
| ASRock        | Z97 Pro4                    | [d0465080bf](https://linux-hardware.org/?probe=d0465080bf) | Oct 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a0d36f3810](https://linux-hardware.org/?probe=a0d36f3810) | Oct 02, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [fca2e4409a](https://linux-hardware.org/?probe=fca2e4409a) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [186495d063](https://linux-hardware.org/?probe=186495d063) | Oct 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6553398b7d](https://linux-hardware.org/?probe=6553398b7d) | Sep 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [362c6b7436](https://linux-hardware.org/?probe=362c6b7436) | Sep 29, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | [3553d42d14](https://linux-hardware.org/?probe=3553d42d14) | Sep 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | [778f7340fa](https://linux-hardware.org/?probe=778f7340fa) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a4b47e7325](https://linux-hardware.org/?probe=a4b47e7325) | Sep 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ab2e3b1767](https://linux-hardware.org/?probe=ab2e3b1767) | Sep 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [0f750af134](https://linux-hardware.org/?probe=0f750af134) | Sep 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [bfb470649a](https://linux-hardware.org/?probe=bfb470649a) | Sep 22, 2022 |
| HP            | 8594                        | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [754dfba736](https://linux-hardware.org/?probe=754dfba736) | Sep 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [fa5f7f7245](https://linux-hardware.org/?probe=fa5f7f7245) | Sep 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5233832be3](https://linux-hardware.org/?probe=5233832be3) | Sep 19, 2022 |
| ASRock        | FM2A88X Extreme6+           | [7161071790](https://linux-hardware.org/?probe=7161071790) | Sep 18, 2022 |
| HP            | 805D                        | [8acaebbd42](https://linux-hardware.org/?probe=8acaebbd42) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [37d6996290](https://linux-hardware.org/?probe=37d6996290) | Sep 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a6e7414518](https://linux-hardware.org/?probe=a6e7414518) | Sep 13, 2022 |
| MSI           | Z97M-G43                    | [706804a4e2](https://linux-hardware.org/?probe=706804a4e2) | Sep 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d85067b0f0](https://linux-hardware.org/?probe=d85067b0f0) | Sep 11, 2022 |
| ASRock        | FM2A88X Extreme6+           | [20ee71a4d6](https://linux-hardware.org/?probe=20ee71a4d6) | Sep 10, 2022 |
| MSI           | P67A-C45                    | [4221289e11](https://linux-hardware.org/?probe=4221289e11) | Sep 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dad765ca9e](https://linux-hardware.org/?probe=dad765ca9e) | Sep 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [0df0bba932](https://linux-hardware.org/?probe=0df0bba932) | Sep 05, 2022 |
| ASRock        | FM2A88X Extreme6+           | [446e2d292a](https://linux-hardware.org/?probe=446e2d292a) | Sep 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [689c3aa34d](https://linux-hardware.org/?probe=689c3aa34d) | Sep 01, 2022 |
| Acer          | Aspire X3400                | [705a3242ae](https://linux-hardware.org/?probe=705a3242ae) | Sep 01, 2022 |
| Acer          | Aspire X3400                | [cb5288e92d](https://linux-hardware.org/?probe=cb5288e92d) | Aug 31, 2022 |
| Acer          | Aspire X3400                | [5e9e5dd1ce](https://linux-hardware.org/?probe=5e9e5dd1ce) | Aug 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [df96c4acaf](https://linux-hardware.org/?probe=df96c4acaf) | Aug 31, 2022 |
| Dell          | 0NW6H5 A00                  | [d4de10030b](https://linux-hardware.org/?probe=d4de10030b) | Aug 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [eba231b7db](https://linux-hardware.org/?probe=eba231b7db) | Aug 30, 2022 |
| MSI           | P67A-C45                    | [5ffb676e01](https://linux-hardware.org/?probe=5ffb676e01) | Aug 27, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ff55a7dbf1](https://linux-hardware.org/?probe=ff55a7dbf1) | Aug 26, 2022 |
| Acer          | Aspire X3400                | [81acff75f6](https://linux-hardware.org/?probe=81acff75f6) | Aug 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f80abd07f3](https://linux-hardware.org/?probe=f80abd07f3) | Aug 25, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [8118d6f78c](https://linux-hardware.org/?probe=8118d6f78c) | Aug 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [d98e5c8b5e](https://linux-hardware.org/?probe=d98e5c8b5e) | Aug 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [3f83c9e402](https://linux-hardware.org/?probe=3f83c9e402) | Aug 16, 2022 |
| ASRock        | FM2A88X Extreme6+           | [1298facab1](https://linux-hardware.org/?probe=1298facab1) | Aug 15, 2022 |
| ASRock        | FM2A88X Extreme6+           | [91a2943c51](https://linux-hardware.org/?probe=91a2943c51) | Aug 09, 2022 |
| ASRock        | FM2A88X Extreme6+           | [244025d59e](https://linux-hardware.org/?probe=244025d59e) | Aug 08, 2022 |
| ASUSTek       | P9X79 LE                    | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9320816ca5](https://linux-hardware.org/?probe=9320816ca5) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | [48606f92a6](https://linux-hardware.org/?probe=48606f92a6) | Aug 05, 2022 |
| ASUSTek       | P9X79                       | [c55f1b0a46](https://linux-hardware.org/?probe=c55f1b0a46) | Aug 05, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [324410a493](https://linux-hardware.org/?probe=324410a493) | Aug 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b224ef1b8d](https://linux-hardware.org/?probe=b224ef1b8d) | Aug 04, 2022 |
| ASRock        | FM2A88X Extreme6+           | [015ec264f5](https://linux-hardware.org/?probe=015ec264f5) | Aug 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8ea1e0f22c](https://linux-hardware.org/?probe=8ea1e0f22c) | Aug 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9dd9d17e79](https://linux-hardware.org/?probe=9dd9d17e79) | Jul 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9a7de8cc64](https://linux-hardware.org/?probe=9a7de8cc64) | Jul 30, 2022 |
| Intel         | TR440BXA A16643-311         | [e6245255f4](https://linux-hardware.org/?probe=e6245255f4) | Jul 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [c0ce536184](https://linux-hardware.org/?probe=c0ce536184) | Jul 29, 2022 |
| ASRock        | H77M-ITX                    | [ca0d4b7108](https://linux-hardware.org/?probe=ca0d4b7108) | Jul 28, 2022 |
| ASUSTek       | VC65                        | [b43ad009f1](https://linux-hardware.org/?probe=b43ad009f1) | Jul 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a9c3256946](https://linux-hardware.org/?probe=a9c3256946) | Jul 28, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [e214df8838](https://linux-hardware.org/?probe=e214df8838) | Jul 27, 2022 |
| ASRock        | H77M-ITX                    | [78a53c9be0](https://linux-hardware.org/?probe=78a53c9be0) | Jul 26, 2022 |
| ASRock        | H77M-ITX                    | [8c749dd7e6](https://linux-hardware.org/?probe=8c749dd7e6) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [1361193180](https://linux-hardware.org/?probe=1361193180) | Jul 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [2632256ed7](https://linux-hardware.org/?probe=2632256ed7) | Jul 25, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8bb191bc8f](https://linux-hardware.org/?probe=8bb191bc8f) | Jul 24, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | [aa2242c51f](https://linux-hardware.org/?probe=aa2242c51f) | Jul 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9c1f5f7a4e](https://linux-hardware.org/?probe=9c1f5f7a4e) | Jul 23, 2022 |
| ASRock        | FM2A88X Extreme6+           | [d758abd21c](https://linux-hardware.org/?probe=d758abd21c) | Jul 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [b54cb1f930](https://linux-hardware.org/?probe=b54cb1f930) | Jul 21, 2022 |
| ASRock        | FM2A88X Extreme6+           | [8cae76caea](https://linux-hardware.org/?probe=8cae76caea) | Jul 20, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ce2e8f2a2a](https://linux-hardware.org/?probe=ce2e8f2a2a) | Jul 12, 2022 |
| ASRock        | FM2A88X Extreme6+           | [84f993f04d](https://linux-hardware.org/?probe=84f993f04d) | Jul 11, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| ASRock        | FM2A88X Extreme6+           | [1bec4af414](https://linux-hardware.org/?probe=1bec4af414) | Jul 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [a658ebf5e9](https://linux-hardware.org/?probe=a658ebf5e9) | Jul 01, 2022 |
| ASUSTek       | TUF B350M-PLUS GAMING       | [a082da0857](https://linux-hardware.org/?probe=a082da0857) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [163a5c29e6](https://linux-hardware.org/?probe=163a5c29e6) | Jun 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [66b8ec6b28](https://linux-hardware.org/?probe=66b8ec6b28) | Jun 29, 2022 |
| ASRock        | FM2A88X Extreme6+           | [4801136187](https://linux-hardware.org/?probe=4801136187) | Jun 18, 2022 |
| MSI           | X99A RAIDER                 | [550772184f](https://linux-hardware.org/?probe=550772184f) | Jun 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [f54dda344d](https://linux-hardware.org/?probe=f54dda344d) | Jun 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [680bf4c033](https://linux-hardware.org/?probe=680bf4c033) | Jun 17, 2022 |
| ASRock        | FM2A88X Extreme6+           | [7990c32699](https://linux-hardware.org/?probe=7990c32699) | Jun 14, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dcd3256961](https://linux-hardware.org/?probe=dcd3256961) | Jun 13, 2022 |
| ASRock        | FM2A88X Extreme6+           | [5a835b2aa6](https://linux-hardware.org/?probe=5a835b2aa6) | Jun 07, 2022 |
| ASRock        | FM2A88X Extreme6+           | [838e0b8e42](https://linux-hardware.org/?probe=838e0b8e42) | Jun 06, 2022 |
| ASRock        | FM2A88X Extreme6+           | [cb07ae6e24](https://linux-hardware.org/?probe=cb07ae6e24) | Jun 02, 2022 |
| ASRock        | FM2A88X Extreme6+           | [dd51d706e3](https://linux-hardware.org/?probe=dd51d706e3) | Jun 01, 2022 |
| Unknown       | Unknown                     | [c2d6d647d8](https://linux-hardware.org/?probe=c2d6d647d8) | May 31, 2022 |
| ASRock        | FM2A88X Extreme6+           | [85a456dd94](https://linux-hardware.org/?probe=85a456dd94) | May 31, 2022 |
| Unknown       | Unknown                     | [59d0634230](https://linux-hardware.org/?probe=59d0634230) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [ff73ff1ea6](https://linux-hardware.org/?probe=ff73ff1ea6) | May 30, 2022 |
| ASRock        | FM2A88X Extreme6+           | [3487c76d47](https://linux-hardware.org/?probe=3487c76d47) | May 29, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| ASRock        | FM2A88X Extreme6+           | [db4eade79e](https://linux-hardware.org/?probe=db4eade79e) | May 28, 2022 |
| MSI           | X99A RAIDER                 | [8226c07ba6](https://linux-hardware.org/?probe=8226c07ba6) | May 27, 2022 |
| Gigabyte      | F2A68HM-DS2                 | [1fa6bb2d62](https://linux-hardware.org/?probe=1fa6bb2d62) | May 26, 2022 |
| ASRock        | FM2A88X Extreme6+           | [19d23eb25f](https://linux-hardware.org/?probe=19d23eb25f) | May 22, 2022 |
| ASRock        | FM2A88X Extreme6+           | [f5ea71aeb2](https://linux-hardware.org/?probe=f5ea71aeb2) | May 21, 2022 |
| ASUSTek       | Pro WS X570-ACE             | [79682a20fa](https://linux-hardware.org/?probe=79682a20fa) | May 16, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d1dbcd7651](https://linux-hardware.org/?probe=d1dbcd7651) | May 16, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | [d4e303b92c](https://linux-hardware.org/?probe=d4e303b92c) | May 15, 2022 |
| Gigabyte      | Z170-Gaming K3              | [768acb5df2](https://linux-hardware.org/?probe=768acb5df2) | May 12, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [927afa0c20](https://linux-hardware.org/?probe=927afa0c20) | May 11, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [b9766a94d7](https://linux-hardware.org/?probe=b9766a94d7) | May 11, 2022 |
| ASUSTek       | Z170-A                      | [97e2613936](https://linux-hardware.org/?probe=97e2613936) | May 08, 2022 |
| Gigabyte      | X570 GAMING X               | [ffc6dac164](https://linux-hardware.org/?probe=ffc6dac164) | May 07, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [afac7f7fb3](https://linux-hardware.org/?probe=afac7f7fb3) | May 07, 2022 |
| Gigabyte      | X570 GAMING X               | [816a78b4cd](https://linux-hardware.org/?probe=816a78b4cd) | May 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | [6f9cfe324a](https://linux-hardware.org/?probe=6f9cfe324a) | May 05, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [7d9a2b425f](https://linux-hardware.org/?probe=7d9a2b425f) | May 03, 2022 |
| MSI           | 970 GAMING                  | [32052450db](https://linux-hardware.org/?probe=32052450db) | May 01, 2022 |
| Gigabyte      | X570 AORUS ELITE            | [8db041a1e4](https://linux-hardware.org/?probe=8db041a1e4) | May 01, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [5456280ec0](https://linux-hardware.org/?probe=5456280ec0) | Apr 26, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [dbaaf867f6](https://linux-hardware.org/?probe=dbaaf867f6) | Apr 25, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b9ea98672f](https://linux-hardware.org/?probe=b9ea98672f) | Apr 23, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [c3f809fc02](https://linux-hardware.org/?probe=c3f809fc02) | Apr 23, 2022 |
| Acer          | Predator G3610              | [a53edf84d4](https://linux-hardware.org/?probe=a53edf84d4) | Apr 22, 2022 |
| ASUSTek       | PRIME X399-A                | [e595903b64](https://linux-hardware.org/?probe=e595903b64) | Apr 18, 2022 |
| ASUSTek       | PRIME X399-A                | [b2fe9a09fd](https://linux-hardware.org/?probe=b2fe9a09fd) | Apr 17, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | [1211bed149](https://linux-hardware.org/?probe=1211bed149) | Apr 13, 2022 |
| MSI           | Z390-A PRO                  | [bfec30bf8d](https://linux-hardware.org/?probe=bfec30bf8d) | Apr 13, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [e2cbc23977](https://linux-hardware.org/?probe=e2cbc23977) | Apr 12, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [486b6a5d64](https://linux-hardware.org/?probe=486b6a5d64) | Apr 10, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [ec3689ffdc](https://linux-hardware.org/?probe=ec3689ffdc) | Apr 10, 2022 |
| Dell          | 0MN1TX A02                  | [cf2e65caf4](https://linux-hardware.org/?probe=cf2e65caf4) | Apr 10, 2022 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | [c344a9c7b9](https://linux-hardware.org/?probe=c344a9c7b9) | Apr 10, 2022 |
| ASRock        | FM2A88X Extreme6+           | [6eb6b5ebaf](https://linux-hardware.org/?probe=6eb6b5ebaf) | Apr 08, 2022 |
| MSI           | B350M MORTAR ARCTIC         | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [448e59a9a6](https://linux-hardware.org/?probe=448e59a9a6) | Apr 02, 2022 |
| Acer          | Aspire X3400                | [47097032fd](https://linux-hardware.org/?probe=47097032fd) | Mar 31, 2022 |
| Dell          | 0MN1TX A02                  | [f9be94fa9b](https://linux-hardware.org/?probe=f9be94fa9b) | Mar 31, 2022 |
| ASUSTek       | M2R-FVM                     | [94beabac6e](https://linux-hardware.org/?probe=94beabac6e) | Mar 30, 2022 |
| ASUSTek       | M2R-FVM                     | [76ec39764b](https://linux-hardware.org/?probe=76ec39764b) | Mar 26, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [6190e57794](https://linux-hardware.org/?probe=6190e57794) | Mar 25, 2022 |
| ASUSTek       | M2R-FVM                     | [eaaef17c19](https://linux-hardware.org/?probe=eaaef17c19) | Mar 25, 2022 |
| ASUSTek       | X99-A                       | [b071309501](https://linux-hardware.org/?probe=b071309501) | Mar 23, 2022 |
| ASUSTek       | M2R-FVM                     | [eb934cc46a](https://linux-hardware.org/?probe=eb934cc46a) | Mar 23, 2022 |
| Dell          | 0YNVJG A01                  | [7a52c137cf](https://linux-hardware.org/?probe=7a52c137cf) | Mar 18, 2022 |
| MSI           | Z170A PC MATE               | [56c1c58549](https://linux-hardware.org/?probe=56c1c58549) | Mar 15, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Gigabyte      | 970A-DS3P                   | [eaae14de4f](https://linux-hardware.org/?probe=eaae14de4f) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [f1b0d6e847](https://linux-hardware.org/?probe=f1b0d6e847) | Mar 03, 2022 |
| Gigabyte      | 970A-DS3P                   | [54ae8c7668](https://linux-hardware.org/?probe=54ae8c7668) | Mar 01, 2022 |
| Gigabyte      | 970A-DS3P                   | [ad43671e4c](https://linux-hardware.org/?probe=ad43671e4c) | Mar 01, 2022 |
| ASRock        | FM2A88X Extreme6+           | [9d178352ca](https://linux-hardware.org/?probe=9d178352ca) | Mar 01, 2022 |
| Lenovo        | SHARKBAY NO DPK             | [9670ab829e](https://linux-hardware.org/?probe=9670ab829e) | Feb 26, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | [d61754bba9](https://linux-hardware.org/?probe=d61754bba9) | Feb 26, 2022 |
| MSI           | 990FXA-GD65                 | [290919912c](https://linux-hardware.org/?probe=290919912c) | Feb 26, 2022 |
| Lenovo        | 0B98401 PRO                 | [c332efa9f8](https://linux-hardware.org/?probe=c332efa9f8) | Feb 24, 2022 |
| Lenovo        | MAHOBAY NO DPK              | [1c6d204561](https://linux-hardware.org/?probe=1c6d204561) | Feb 24, 2022 |
| ASRock        | FM2A88X Extreme6+           | [67deab7343](https://linux-hardware.org/?probe=67deab7343) | Feb 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [160ecaffd8](https://linux-hardware.org/?probe=160ecaffd8) | Feb 21, 2022 |
| ASUSTek       | SABERTOOTH P67              | [2ad209abc4](https://linux-hardware.org/?probe=2ad209abc4) | Feb 12, 2022 |
| ASUSTek       | Maximus VIII HERO           | [ef92dfd4f1](https://linux-hardware.org/?probe=ef92dfd4f1) | Feb 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [ccd7847b28](https://linux-hardware.org/?probe=ccd7847b28) | Jan 30, 2022 |
| ASRock        | ION3D-HT                    | [5a4158f549](https://linux-hardware.org/?probe=5a4158f549) | Jan 29, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [908edb3724](https://linux-hardware.org/?probe=908edb3724) | Jan 27, 2022 |
| Intel         | D54250WYK H13922-303        | [8b6b3d70bf](https://linux-hardware.org/?probe=8b6b3d70bf) | Jan 26, 2022 |
| Gigabyte      | 970A-DS3P                   | [b96e414ae9](https://linux-hardware.org/?probe=b96e414ae9) | Jan 21, 2022 |
| Gigabyte      | 970A-DS3P                   | [96047ce382](https://linux-hardware.org/?probe=96047ce382) | Jan 19, 2022 |
| ASRock        | Z87 Killer                  | [6931f1ca2f](https://linux-hardware.org/?probe=6931f1ca2f) | Jan 17, 2022 |
| MSI           | P67A-C45                    | [953176b34f](https://linux-hardware.org/?probe=953176b34f) | Jan 17, 2022 |
| ASUSTek       | P5L8L-SE                    | [459b062c3e](https://linux-hardware.org/?probe=459b062c3e) | Jan 14, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [7921e32637](https://linux-hardware.org/?probe=7921e32637) | Jan 14, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | [7b12fb3749](https://linux-hardware.org/?probe=7b12fb3749) | Jan 14, 2022 |
| Acer          | Aspire X3400                | [6833137bc8](https://linux-hardware.org/?probe=6833137bc8) | Jan 02, 2022 |
| MSI           | H110M PRO-VH                | [a32495b8e4](https://linux-hardware.org/?probe=a32495b8e4) | Jan 02, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [b86150c4bd](https://linux-hardware.org/?probe=b86150c4bd) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [923f77a787](https://linux-hardware.org/?probe=923f77a787) | Dec 16, 2021 |
| ASUSTek       | SABERTOOTH P67              | [af2732b8a5](https://linux-hardware.org/?probe=af2732b8a5) | Dec 15, 2021 |
| ASUSTek       | TUF Gaming B550-PRO         | [62f4289baa](https://linux-hardware.org/?probe=62f4289baa) | Dec 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | [12da1dc78f](https://linux-hardware.org/?probe=12da1dc78f) | Dec 14, 2021 |
| Lenovo        | SHARKBAY NOK                | [882e308c93](https://linux-hardware.org/?probe=882e308c93) | Dec 11, 2021 |
| ASRockRack    | ROMED8-2T                   | [87b9d0f1e5](https://linux-hardware.org/?probe=87b9d0f1e5) | Dec 04, 2021 |
| ASRockRack    | ROMED8-2T                   | [071e272398](https://linux-hardware.org/?probe=071e272398) | Dec 04, 2021 |
| ASRock        | B450M Steel Legend          | [5c0f6b8395](https://linux-hardware.org/?probe=5c0f6b8395) | Nov 28, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [fb92bb54af](https://linux-hardware.org/?probe=fb92bb54af) | Nov 28, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [7c0e3a92a5](https://linux-hardware.org/?probe=7c0e3a92a5) | Nov 26, 2021 |
| ASUSTek       | ROG Maximus Z690 HERO       | [f3e1cfcdab](https://linux-hardware.org/?probe=f3e1cfcdab) | Nov 26, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [846877b55f](https://linux-hardware.org/?probe=846877b55f) | Nov 25, 2021 |
| MSI           | H170 GAMING M3              | [e9a754ed5c](https://linux-hardware.org/?probe=e9a754ed5c) | Nov 24, 2021 |
| Gigabyte      | Z170-Gaming K3              | [496b525711](https://linux-hardware.org/?probe=496b525711) | Nov 24, 2021 |
| ASRock        | X99M Extreme4               | [3f738eedfc](https://linux-hardware.org/?probe=3f738eedfc) | Nov 22, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [756684e469](https://linux-hardware.org/?probe=756684e469) | Nov 20, 2021 |
| Acer          | EG43M                       | [03dc3c8d61](https://linux-hardware.org/?probe=03dc3c8d61) | Nov 20, 2021 |
| ASUSTek       | P8Z77-V LX                  | [6807e3fa8c](https://linux-hardware.org/?probe=6807e3fa8c) | Nov 18, 2021 |
| HP            | 8056                        | [f62a924908](https://linux-hardware.org/?probe=f62a924908) | Nov 16, 2021 |
| Gigabyte      | H87N-WIFI                   | [b19a68b774](https://linux-hardware.org/?probe=b19a68b774) | Nov 13, 2021 |
| MSI           | B75MA-P45                   | [8196870f95](https://linux-hardware.org/?probe=8196870f95) | Nov 11, 2021 |
| Gigabyte      | F2A78M-D3H                  | [43e09b8e80](https://linux-hardware.org/?probe=43e09b8e80) | Nov 05, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [4615791bf1](https://linux-hardware.org/?probe=4615791bf1) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | [0cc8ca1a78](https://linux-hardware.org/?probe=0cc8ca1a78) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [688a36c9df](https://linux-hardware.org/?probe=688a36c9df) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [ccce1ad4e4](https://linux-hardware.org/?probe=ccce1ad4e4) | Oct 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | [a96916c86f](https://linux-hardware.org/?probe=a96916c86f) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [3862cf57e0](https://linux-hardware.org/?probe=3862cf57e0) | Oct 25, 2021 |
| MSI           | Z77A-GD65                   | [5273767a7e](https://linux-hardware.org/?probe=5273767a7e) | Oct 22, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [666f084a0f](https://linux-hardware.org/?probe=666f084a0f) | Oct 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | [395d19ae36](https://linux-hardware.org/?probe=395d19ae36) | Oct 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | [f4442e94e7](https://linux-hardware.org/?probe=f4442e94e7) | Oct 21, 2021 |
| HP            | 1998                        | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Pegatron      | 2AC3                        | [ae8b02d9cb](https://linux-hardware.org/?probe=ae8b02d9cb) | Oct 21, 2021 |
| ASUSTek       | PRIME B460M-A               | [6db5e9be6b](https://linux-hardware.org/?probe=6db5e9be6b) | Oct 19, 2021 |
| Dell          | 0D28YY A02                  | [237a82041b](https://linux-hardware.org/?probe=237a82041b) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS ELITE            | [bc7f078524](https://linux-hardware.org/?probe=bc7f078524) | Oct 07, 2021 |
| Packard Be... | IXTREME M5120               | [315bbefc53](https://linux-hardware.org/?probe=315bbefc53) | Oct 06, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [c9022127a9](https://linux-hardware.org/?probe=c9022127a9) | Oct 03, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [99b237ae08](https://linux-hardware.org/?probe=99b237ae08) | Oct 02, 2021 |
| HP            | 8056                        | [2199f7a715](https://linux-hardware.org/?probe=2199f7a715) | Sep 26, 2021 |
| ASUSTek       | PRIME B350M-A               | [3808823182](https://linux-hardware.org/?probe=3808823182) | Sep 23, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [f28906612f](https://linux-hardware.org/?probe=f28906612f) | Sep 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [17ad477c6f](https://linux-hardware.org/?probe=17ad477c6f) | Sep 21, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [a122cb5006](https://linux-hardware.org/?probe=a122cb5006) | Sep 19, 2021 |
| Acer          | EG43M                       | [03cff58061](https://linux-hardware.org/?probe=03cff58061) | Sep 17, 2021 |
| HP            | 8056                        | [61c50556d0](https://linux-hardware.org/?probe=61c50556d0) | Sep 13, 2021 |
| ASUSTek       | Z170-A                      | [630fec5a83](https://linux-hardware.org/?probe=630fec5a83) | Sep 11, 2021 |
| Gigabyte      | J3455N-D3H                  | [24bc89b42a](https://linux-hardware.org/?probe=24bc89b42a) | Aug 31, 2021 |
| HP            | 0B40h                       | [da95bc989c](https://linux-hardware.org/?probe=da95bc989c) | Aug 30, 2021 |
| Supermicro    | X10DAI                      | [078ab4c114](https://linux-hardware.org/?probe=078ab4c114) | Aug 24, 2021 |
| ASRock        | X370 Gaming-ITX/ac          | [5909ea8d8d](https://linux-hardware.org/?probe=5909ea8d8d) | Aug 20, 2021 |
| HP            | 802E                        | [35a2f000fd](https://linux-hardware.org/?probe=35a2f000fd) | Aug 19, 2021 |
| ASUSTek       | B150M-C                     | [794387ddd6](https://linux-hardware.org/?probe=794387ddd6) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | [eaac722778](https://linux-hardware.org/?probe=eaac722778) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | [a24db8e84d](https://linux-hardware.org/?probe=a24db8e84d) | Aug 16, 2021 |
| ASUSTek       | PRIME Z270-A                | [51b28dbd02](https://linux-hardware.org/?probe=51b28dbd02) | Aug 16, 2021 |
| Acer          | Aspire X3400                | [0a158e8bce](https://linux-hardware.org/?probe=0a158e8bce) | Aug 13, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [034630b7f9](https://linux-hardware.org/?probe=034630b7f9) | Aug 11, 2021 |
| Acer          | Aspire X3400                | [6836f60d13](https://linux-hardware.org/?probe=6836f60d13) | Aug 11, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [a1768aa578](https://linux-hardware.org/?probe=a1768aa578) | Aug 06, 2021 |
| Fujitsu Si... | D2264-A1 S26361-D2264-A1    | [52aa712b0c](https://linux-hardware.org/?probe=52aa712b0c) | Aug 05, 2021 |
| HP            | 3397                        | [d5add95307](https://linux-hardware.org/?probe=d5add95307) | Aug 05, 2021 |
| ASRock        | Z370M-ITX/ac                | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Wibtek        | TH61G-S                     | [346ae2c85d](https://linux-hardware.org/?probe=346ae2c85d) | Jul 29, 2021 |
| HP            | 87D6 SMVB                   | [77f9eee003](https://linux-hardware.org/?probe=77f9eee003) | Jul 28, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [88d668c3ab](https://linux-hardware.org/?probe=88d668c3ab) | Jul 27, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| ASRock        | B450 Gaming K4              | [563a58b492](https://linux-hardware.org/?probe=563a58b492) | Jul 24, 2021 |
| ASRock        | X570 Steel Legend           | [6f026a93d1](https://linux-hardware.org/?probe=6f026a93d1) | Jul 17, 2021 |
| ASRock        | X570 Steel Legend           | [af12b529b0](https://linux-hardware.org/?probe=af12b529b0) | Jul 17, 2021 |
| Gigabyte      | B550 AORUS MASTER           | [35bf19b527](https://linux-hardware.org/?probe=35bf19b527) | Jul 13, 2021 |
| HP            | 872B                        | [319ce0e306](https://linux-hardware.org/?probe=319ce0e306) | Jul 13, 2021 |
| Gigabyte      | B450 AORUS PRO-CF           | [ef051fc485](https://linux-hardware.org/?probe=ef051fc485) | Jul 04, 2021 |
| HP            | 1998                        | [8f095c8449](https://linux-hardware.org/?probe=8f095c8449) | Jul 01, 2021 |
| ASUSTek       | P5G41T-M                    | [8553d8a919](https://linux-hardware.org/?probe=8553d8a919) | Jun 30, 2021 |
| ASUSTek       | M5A97 R2.0                  | [04c4ddf9b0](https://linux-hardware.org/?probe=04c4ddf9b0) | Jun 29, 2021 |
| Acer          | EG43LMK                     | [5df39d6ba0](https://linux-hardware.org/?probe=5df39d6ba0) | Jun 26, 2021 |
| MSI           | B85M-E45                    | [5508d6a84e](https://linux-hardware.org/?probe=5508d6a84e) | Jun 23, 2021 |
| MSI           | B75MA-P45                   | [0ccd0cdf44](https://linux-hardware.org/?probe=0ccd0cdf44) | Jun 15, 2021 |
| Dell          | 02YYK5 A01                  | [74a4b076a9](https://linux-hardware.org/?probe=74a4b076a9) | Jun 13, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [8081e6a752](https://linux-hardware.org/?probe=8081e6a752) | Jun 12, 2021 |
| ASUSTek       | X99-DELUXE                  | [382c24055c](https://linux-hardware.org/?probe=382c24055c) | Jun 09, 2021 |
| Lenovo        | SDK0E50510 WIN              | [9cfdd32388](https://linux-hardware.org/?probe=9cfdd32388) | Jun 04, 2021 |
| ASUSTek       | PRIME B460M-A               | [5125306d59](https://linux-hardware.org/?probe=5125306d59) | May 31, 2021 |
| ASUSTek       | M5A97 R2.0                  | [f0145b568f](https://linux-hardware.org/?probe=f0145b568f) | May 27, 2021 |
| ASUSTek       | Maximus VIII HERO           | [4550202db3](https://linux-hardware.org/?probe=4550202db3) | May 15, 2021 |
| Gigabyte      | GA-970A-UD3                 | [1cf830acd9](https://linux-hardware.org/?probe=1cf830acd9) | May 13, 2021 |
| Gigabyte      | X99-UD7 WIFI-CF             | [87d92ce1b4](https://linux-hardware.org/?probe=87d92ce1b4) | May 08, 2021 |
| Gigabyte      | X99-UD7 WIFI-CF             | [766557aeb8](https://linux-hardware.org/?probe=766557aeb8) | May 07, 2021 |
| Dell          | 0M9KCM A02                  | [c016fc8897](https://linux-hardware.org/?probe=c016fc8897) | May 03, 2021 |
| ASUSTek       | PRIME Z490-A                | [af5179a1f9](https://linux-hardware.org/?probe=af5179a1f9) | Apr 30, 2021 |
| Dell          | 02YYK5 A01                  | [bd1254fe8d](https://linux-hardware.org/?probe=bd1254fe8d) | Apr 28, 2021 |
| MSI           | Z97S SLI Krait Edition      | [afb9057dda](https://linux-hardware.org/?probe=afb9057dda) | Apr 16, 2021 |
| ASRock        | X470 Taichi Ultimate        | [7ab07ae1e9](https://linux-hardware.org/?probe=7ab07ae1e9) | Apr 11, 2021 |
| ASRock        | X470 Taichi Ultimate        | [174dc97643](https://linux-hardware.org/?probe=174dc97643) | Apr 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2116d4313c](https://linux-hardware.org/?probe=2116d4313c) | Apr 11, 2021 |
| Dell          | 0WMJ54 A01                  | [59c7b4d6ff](https://linux-hardware.org/?probe=59c7b4d6ff) | Apr 10, 2021 |
| ASUSTek       | F2A85-M                     | [9548d9f0c6](https://linux-hardware.org/?probe=9548d9f0c6) | Apr 06, 2021 |
| ASUSTek       | PRIME Z490-A                | [9db70676f4](https://linux-hardware.org/?probe=9db70676f4) | Apr 05, 2021 |
| HP            | 1790                        | [d03e7a12c6](https://linux-hardware.org/?probe=d03e7a12c6) | Apr 04, 2021 |
| Gigabyte      | X570 AORUS XTREME           | [39f6ad5463](https://linux-hardware.org/?probe=39f6ad5463) | Apr 04, 2021 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | [393b9a2647](https://linux-hardware.org/?probe=393b9a2647) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | [6a1ee4ca94](https://linux-hardware.org/?probe=6a1ee4ca94) | Mar 31, 2021 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [394a2510d4](https://linux-hardware.org/?probe=394a2510d4) | Mar 31, 2021 |
| Cisco Syst... | UCSB-B200-M4 73-15862-03    | [4c55de0b30](https://linux-hardware.org/?probe=4c55de0b30) | Mar 31, 2021 |
| ASRock        | B450M Pro4-F                | [c7223020fe](https://linux-hardware.org/?probe=c7223020fe) | Mar 25, 2021 |
| ASUSTek       | PRIME X470-PRO              | [c3f70afbd8](https://linux-hardware.org/?probe=c3f70afbd8) | Mar 18, 2021 |
| ASUSTek       | M4A79T Deluxe               | [2ccff038d2](https://linux-hardware.org/?probe=2ccff038d2) | Mar 16, 2021 |
| HP            | 802F                        | [9ea8632891](https://linux-hardware.org/?probe=9ea8632891) | Mar 14, 2021 |
| MSI           | X99A RAIDER                 | [6f27ffd7aa](https://linux-hardware.org/?probe=6f27ffd7aa) | Mar 13, 2021 |
| ASUSTek       | ROG STRIX B360-H GAMING     | [9625a9c184](https://linux-hardware.org/?probe=9625a9c184) | Feb 26, 2021 |
| Dell          | 0NK70N A03                  | [5354c0cb90](https://linux-hardware.org/?probe=5354c0cb90) | Feb 22, 2021 |
| HP            | 2B35                        | [ab5c723699](https://linux-hardware.org/?probe=ab5c723699) | Feb 20, 2021 |
| MSI           | MEG X570 UNIFY              | [455cf08e86](https://linux-hardware.org/?probe=455cf08e86) | Feb 20, 2021 |
| Dell          | 0MN1TX A01                  | [ebc826cccc](https://linux-hardware.org/?probe=ebc826cccc) | Feb 18, 2021 |
| Acer          | Predator G3-605             | [f1a8ae2c26](https://linux-hardware.org/?probe=f1a8ae2c26) | Feb 17, 2021 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [c445cf637b](https://linux-hardware.org/?probe=c445cf637b) | Feb 15, 2021 |
| MSI           | X299 SLI PLUS               | [1499657b8c](https://linux-hardware.org/?probe=1499657b8c) | Feb 13, 2021 |
| ASUSTek       | STRIX Z270F GAMING          | [743d5820cc](https://linux-hardware.org/?probe=743d5820cc) | Feb 13, 2021 |
| ASRock        | X570 Taichi                 | [96d6904297](https://linux-hardware.org/?probe=96d6904297) | Feb 01, 2021 |
| ASUSTek       | P8Z77-M                     | [d60b967710](https://linux-hardware.org/?probe=d60b967710) | Jan 22, 2021 |
| Dell          | 00V62H A00                  | [3d8b11fbf3](https://linux-hardware.org/?probe=3d8b11fbf3) | Jan 20, 2021 |
| ASUSTek       | Z170 PRO GAMING             | [7a840d41b2](https://linux-hardware.org/?probe=7a840d41b2) | Jan 19, 2021 |
| MSI           | MAG B550M MORTAR            | [0900f71645](https://linux-hardware.org/?probe=0900f71645) | Jan 17, 2021 |
| ASUSTek       | PRIME Z270-P                | [d3150c1175](https://linux-hardware.org/?probe=d3150c1175) | Jan 14, 2021 |
| Acidanther... | Mac-F60DEB81FF30ACF6 Mac... | [772bf2459f](https://linux-hardware.org/?probe=772bf2459f) | Jan 11, 2021 |
| MSI           | B350M MORTAR ARCTIC         | [0d39b0f1de](https://linux-hardware.org/?probe=0d39b0f1de) | Jan 10, 2021 |
| Dell          | 0VD5HY A00                  | [470703f4af](https://linux-hardware.org/?probe=470703f4af) | Dec 27, 2020 |
| ASUSTek       | ROG Maximus XII FORMULA     | [656256db83](https://linux-hardware.org/?probe=656256db83) | Dec 22, 2020 |
| Gigabyte      | B550 AORUS PRO              | [1520dcde71](https://linux-hardware.org/?probe=1520dcde71) | Dec 20, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [03fbf815fb](https://linux-hardware.org/?probe=03fbf815fb) | Dec 19, 2020 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [6cff41d0d5](https://linux-hardware.org/?probe=6cff41d0d5) | Dec 18, 2020 |
| ASUSTek       | ROG STRIX B460-F GAMING     | [3673aeec97](https://linux-hardware.org/?probe=3673aeec97) | Dec 07, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [e9fb942639](https://linux-hardware.org/?probe=e9fb942639) | Dec 04, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [38c026cbb9](https://linux-hardware.org/?probe=38c026cbb9) | Nov 28, 2020 |
| Lenovo        | 0800-E3G                    | [82f0cc6d73](https://linux-hardware.org/?probe=82f0cc6d73) | Nov 24, 2020 |
| Lenovo        | 0800-E3G                    | [f7a3cae158](https://linux-hardware.org/?probe=f7a3cae158) | Nov 24, 2020 |
| HP            | 0AA8h                       | [5b9abc7e6e](https://linux-hardware.org/?probe=5b9abc7e6e) | Nov 21, 2020 |
| ASUSTek       | SABERTOOTH Z77              | [4497d1907e](https://linux-hardware.org/?probe=4497d1907e) | Nov 21, 2020 |
| ASUSTek       | P8Z77-V PRO/THUNDERBOLT     | [1945ae5a25](https://linux-hardware.org/?probe=1945ae5a25) | Nov 16, 2020 |
| ASUSTek       | P9X79 LE                    | [535bb960c8](https://linux-hardware.org/?probe=535bb960c8) | Nov 09, 2020 |
| ASUSTek       | PRIME X370-PRO              | [8cc1c3b402](https://linux-hardware.org/?probe=8cc1c3b402) | Nov 05, 2020 |
| ASUSTek       | PRIME X570-P                | [7cc067fb03](https://linux-hardware.org/?probe=7cc067fb03) | Nov 03, 2020 |
| ASUSTek       | PRIME X570-P                | [2a45f74eda](https://linux-hardware.org/?probe=2a45f74eda) | Nov 02, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [d44d323649](https://linux-hardware.org/?probe=d44d323649) | Oct 31, 2020 |
| Gigabyte      | GA-970A-UD3                 | [1e3afeadf1](https://linux-hardware.org/?probe=1e3afeadf1) | Oct 31, 2020 |
| Gigabyte      | GA-970A-UD3                 | [c36062c763](https://linux-hardware.org/?probe=c36062c763) | Oct 31, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [509ec4584c](https://linux-hardware.org/?probe=509ec4584c) | Oct 31, 2020 |
| ASUSTek       | P8Z77-M                     | [ca7e76d821](https://linux-hardware.org/?probe=ca7e76d821) | Oct 30, 2020 |
| ASUSTek       | PRIME X370-PRO              | [01bfabd117](https://linux-hardware.org/?probe=01bfabd117) | Oct 29, 2020 |
| Gigabyte      | 970A-DS3P                   | [4c38164a20](https://linux-hardware.org/?probe=4c38164a20) | Oct 21, 2020 |
| ASRock        | X570 Extreme4               | [40e091c5f4](https://linux-hardware.org/?probe=40e091c5f4) | Oct 16, 2020 |
| Dell          | 00V62H A01                  | [d246c4d7c9](https://linux-hardware.org/?probe=d246c4d7c9) | Oct 15, 2020 |
| ASRock        | FM2A75M-HD+                 | [eb66178779](https://linux-hardware.org/?probe=eb66178779) | Oct 13, 2020 |
| ASRock        | X570 Extreme4               | [cad3c5d0ba](https://linux-hardware.org/?probe=cad3c5d0ba) | Oct 13, 2020 |
| Gigabyte      | MQLP5AP-00                  | [bec4249ac9](https://linux-hardware.org/?probe=bec4249ac9) | Oct 12, 2020 |
| ASUSTek       | STRIX Z270E GAMING          | [80b8079281](https://linux-hardware.org/?probe=80b8079281) | Oct 02, 2020 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [4fa10cd09d](https://linux-hardware.org/?probe=4fa10cd09d) | Sep 30, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [07fab4cd26](https://linux-hardware.org/?probe=07fab4cd26) | Sep 29, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [7e8f9659ac](https://linux-hardware.org/?probe=7e8f9659ac) | Sep 28, 2020 |
| Gigabyte      | H310N                       | [af0cc1312f](https://linux-hardware.org/?probe=af0cc1312f) | Sep 28, 2020 |
| MSI           | X99A RAIDER                 | [dad099d968](https://linux-hardware.org/?probe=dad099d968) | Sep 28, 2020 |
| ASRock        | X570 Taichi                 | [60d17efc7c](https://linux-hardware.org/?probe=60d17efc7c) | Sep 25, 2020 |
| Lenovo        | SHARKBAY SDK0J40705 WIN ... | [a7176bb601](https://linux-hardware.org/?probe=a7176bb601) | Sep 15, 2020 |
| ASUSTek       | P9X79 LE                    | [6cb5707322](https://linux-hardware.org/?probe=6cb5707322) | Sep 15, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [576daf4d41](https://linux-hardware.org/?probe=576daf4d41) | Sep 15, 2020 |
| ASUSTek       | SABERTOOTH Z87              | [726f3b1370](https://linux-hardware.org/?probe=726f3b1370) | Sep 14, 2020 |
| ASUSTek       | SABERTOOTH Z87              | [d6885cac52](https://linux-hardware.org/?probe=d6885cac52) | Sep 14, 2020 |
| ASUSTek       | NARRA2                      | [54160f4cb5](https://linux-hardware.org/?probe=54160f4cb5) | Sep 10, 2020 |
| ASUSTek       | EX-A320M-GAMING             | [f604a231fa](https://linux-hardware.org/?probe=f604a231fa) | Sep 10, 2020 |
| ASUSTek       | PRIME X570-P                | [08210e360a](https://linux-hardware.org/?probe=08210e360a) | Sep 10, 2020 |
| ASUSTek       | X99-E WS                    | [e37af5c1c2](https://linux-hardware.org/?probe=e37af5c1c2) | Sep 05, 2020 |
| Gigabyte      | 970A-DS3P                   | [b1248e2b3b](https://linux-hardware.org/?probe=b1248e2b3b) | Sep 05, 2020 |
| MSI           | B350 TOMAHAWK               | [cf16a05fb6](https://linux-hardware.org/?probe=cf16a05fb6) | Sep 03, 2020 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8f3f962b06](https://linux-hardware.org/?probe=8f3f962b06) | Sep 03, 2020 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [b3bb6fe3dc](https://linux-hardware.org/?probe=b3bb6fe3dc) | Aug 27, 2020 |
| MSI           | Z97S SLI Krait Edition      | [c4b10f778e](https://linux-hardware.org/?probe=c4b10f778e) | Aug 25, 2020 |
| ASUSTek       | X99-E WS                    | [ed9d8c885d](https://linux-hardware.org/?probe=ed9d8c885d) | Aug 25, 2020 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | [a59b0acdfe](https://linux-hardware.org/?probe=a59b0acdfe) | Aug 24, 2020 |
| ASUSTek       | PRIME Z270-P                | [904934805a](https://linux-hardware.org/?probe=904934805a) | Aug 19, 2020 |
| ASUSTek       | Z170-P                      | [b15339e143](https://linux-hardware.org/?probe=b15339e143) | Aug 17, 2020 |
| Gigabyte      | Z490I AORUS ULTRA           | [58dce1215c](https://linux-hardware.org/?probe=58dce1215c) | Aug 13, 2020 |
| MSI           | B350M MORTAR ARCTIC         | [c6d5a14495](https://linux-hardware.org/?probe=c6d5a14495) | Aug 12, 2020 |
| MSI           | B350M MORTAR ARCTIC         | [143846fb82](https://linux-hardware.org/?probe=143846fb82) | Aug 12, 2020 |
| ASUSTek       | GRYPHON Z97 ARMOR EDITIO... | [e0855b4bf3](https://linux-hardware.org/?probe=e0855b4bf3) | Aug 09, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [9b4f4dc28b](https://linux-hardware.org/?probe=9b4f4dc28b) | Aug 07, 2020 |
| MSI           | Z87-G45 GAMING              | [edfa113106](https://linux-hardware.org/?probe=edfa113106) | Aug 03, 2020 |
| ASUSTek       | B85M-G                      | [917bed383b](https://linux-hardware.org/?probe=917bed383b) | Jul 26, 2020 |
| Gigabyte      | GA-MA770T-UD3P              | [552295571e](https://linux-hardware.org/?probe=552295571e) | Jul 26, 2020 |
| MSI           | Z87-G45 GAMING              | [c91081e069](https://linux-hardware.org/?probe=c91081e069) | Jul 26, 2020 |
| ASUSTek       | B85M-G                      | [475dbf0ad7](https://linux-hardware.org/?probe=475dbf0ad7) | Jul 25, 2020 |
| MSI           | Z87-G45 GAMING              | [cd32144f93](https://linux-hardware.org/?probe=cd32144f93) | Jul 25, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [c6f296962b](https://linux-hardware.org/?probe=c6f296962b) | Jul 23, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [76fb21829c](https://linux-hardware.org/?probe=76fb21829c) | Jul 07, 2020 |
| ASRock        | KBL-NUC                     | [0fb87b772d](https://linux-hardware.org/?probe=0fb87b772d) | Jul 05, 2020 |
| ASUSTek       | TUF Z270 MARK 2             | [e6aca4abae](https://linux-hardware.org/?probe=e6aca4abae) | Jul 01, 2020 |
| ASUSTek       | TUF Z270 MARK 2             | [3662f6e30e](https://linux-hardware.org/?probe=3662f6e30e) | Jul 01, 2020 |
| ASUSTek       | PRIME X570-P                | [d7dfd2a0d2](https://linux-hardware.org/?probe=d7dfd2a0d2) | Jun 30, 2020 |
| ASUSTek       | X99-E WS                    | [b1bdbcd5d8](https://linux-hardware.org/?probe=b1bdbcd5d8) | Jun 24, 2020 |
| Dell          | 02K9CR A01                  | [823eca4894](https://linux-hardware.org/?probe=823eca4894) | Jun 22, 2020 |
| ASUSTek       | PRIME X570-P                | [16394021f5](https://linux-hardware.org/?probe=16394021f5) | Jun 21, 2020 |
| ASUSTek       | PRIME X570-P                | [392a2f214f](https://linux-hardware.org/?probe=392a2f214f) | Jun 20, 2020 |
| ASUSTek       | Z170-P                      | [7bbf45616d](https://linux-hardware.org/?probe=7bbf45616d) | Jun 11, 2020 |
| ASUSTek       | SABERTOOTH X58              | [b96a58003f](https://linux-hardware.org/?probe=b96a58003f) | Jun 02, 2020 |
| ASUSTek       | M5A97 R2.0                  | [f83c6bc99a](https://linux-hardware.org/?probe=f83c6bc99a) | May 28, 2020 |
| ASUSTek       | M5A97 R2.0                  | [4479197ed4](https://linux-hardware.org/?probe=4479197ed4) | May 23, 2020 |
| ASUSTek       | ROG STRIX B360-F GAMING     | [0580ffcbce](https://linux-hardware.org/?probe=0580ffcbce) | May 18, 2020 |
| ASUSTek       | SABERTOOTH X58              | [0ac27b4c34](https://linux-hardware.org/?probe=0ac27b4c34) | May 18, 2020 |
| ASUSTek       | SABERTOOTH X58              | [bc5ccb2621](https://linux-hardware.org/?probe=bc5ccb2621) | May 18, 2020 |
| ASUSTek       | CROSSHAIR VI HERO           | [386740675c](https://linux-hardware.org/?probe=386740675c) | May 13, 2020 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [98d3987a61](https://linux-hardware.org/?probe=98d3987a61) | May 06, 2020 |
| ASUSTek       | H81I-PLUS                   | [33d922e46d](https://linux-hardware.org/?probe=33d922e46d) | May 05, 2020 |
| ASUSTek       | P8H77-I                     | [cd6981fca0](https://linux-hardware.org/?probe=cd6981fca0) | Apr 28, 2020 |
| ASUSTek       | P8H77-I                     | [9fdad4ca4b](https://linux-hardware.org/?probe=9fdad4ca4b) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [5cae2ee3d0](https://linux-hardware.org/?probe=5cae2ee3d0) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [a5bf0d9b6b](https://linux-hardware.org/?probe=a5bf0d9b6b) | Apr 28, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | [4e2748672a](https://linux-hardware.org/?probe=4e2748672a) | Apr 28, 2020 |
| HP            | 3397                        | [e6727c485f](https://linux-hardware.org/?probe=e6727c485f) | Apr 27, 2020 |
| Lenovo        | 0x30F617AA SDK0J40697 WI... | [6a5b331028](https://linux-hardware.org/?probe=6a5b331028) | Apr 11, 2020 |
| ASRock        | X99M Extreme4               | [45030fab5d](https://linux-hardware.org/?probe=45030fab5d) | Apr 11, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [a71754c00c](https://linux-hardware.org/?probe=a71754c00c) | Apr 07, 2020 |
| Gigabyte      | GA-MA785GT-UD3H             | [2557527190](https://linux-hardware.org/?probe=2557527190) | Apr 06, 2020 |
| ASUSTek       | X99-E WS                    | [cab8397e58](https://linux-hardware.org/?probe=cab8397e58) | Apr 05, 2020 |
| HP            | 0A68h                       | [21961765f3](https://linux-hardware.org/?probe=21961765f3) | Apr 04, 2020 |
| ASUSTek       | X99-E WS                    | [535aa9a5c6](https://linux-hardware.org/?probe=535aa9a5c6) | Apr 01, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [83594d554f](https://linux-hardware.org/?probe=83594d554f) | Mar 26, 2020 |
| HP            | 0A68h                       | [e48c1d8956](https://linux-hardware.org/?probe=e48c1d8956) | Mar 21, 2020 |
| MSI           | Z270 GAMING PRO CARBON      | [a5c1f26d9c](https://linux-hardware.org/?probe=a5c1f26d9c) | Mar 21, 2020 |
| MSI           | B450M BAZOOKA               | [a97b201643](https://linux-hardware.org/?probe=a97b201643) | Mar 19, 2020 |
| MSI           | Z270 GAMING PRO CARBON      | [731ed47f34](https://linux-hardware.org/?probe=731ed47f34) | Mar 17, 2020 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | [b5a0ec3283](https://linux-hardware.org/?probe=b5a0ec3283) | Mar 16, 2020 |
| Gigabyte      | B450 AORUS M                | [3c6e4bca36](https://linux-hardware.org/?probe=3c6e4bca36) | Mar 13, 2020 |
| Shuttle       | FS35V4                      | [c52e6f6535](https://linux-hardware.org/?probe=c52e6f6535) | Mar 02, 2020 |
| ASUSTek       | P8Z77-V PRO                 | [5d7f28b50a](https://linux-hardware.org/?probe=5d7f28b50a) | Feb 29, 2020 |
| ASUSTek       | PRIME H270-PLUS             | [c89b46d092](https://linux-hardware.org/?probe=c89b46d092) | Feb 25, 2020 |
| Shuttle       | FS35V4                      | [86b9422986](https://linux-hardware.org/?probe=86b9422986) | Feb 23, 2020 |
| Pegatron      | 2AB5                        | [8cd66072e1](https://linux-hardware.org/?probe=8cd66072e1) | Feb 21, 2020 |
| Gigabyte      | Z270N-WIFI-CF               | [765c227e7c](https://linux-hardware.org/?probe=765c227e7c) | Feb 21, 2020 |
| ASRock        | H81M-ITX/WiFi               | [4b746c7d20](https://linux-hardware.org/?probe=4b746c7d20) | Feb 19, 2020 |
| Gigabyte      | GA-970A-UD3                 | [9d30831796](https://linux-hardware.org/?probe=9d30831796) | Feb 17, 2020 |
| Gigabyte      | GA-970A-UD3                 | [3d45ca6f5b](https://linux-hardware.org/?probe=3d45ca6f5b) | Feb 17, 2020 |
| Dell          | 0DF42J A00                  | [315459c675](https://linux-hardware.org/?probe=315459c675) | Feb 16, 2020 |
| ASUSTek       | Maximus VIII RANGER         | [0be68258a3](https://linux-hardware.org/?probe=0be68258a3) | Feb 11, 2020 |
| Acer          | FRS690L                     | [da0aa833d2](https://linux-hardware.org/?probe=da0aa833d2) | Feb 07, 2020 |
| Acer          | FRS690L                     | [d2f7944838](https://linux-hardware.org/?probe=d2f7944838) | Feb 07, 2020 |
| Acer          | FRS690L                     | [52e677d939](https://linux-hardware.org/?probe=52e677d939) | Feb 07, 2020 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [174e1402cf](https://linux-hardware.org/?probe=174e1402cf) | Feb 03, 2020 |
| Dell          | 0MN1TX A02                  | [5c482e9676](https://linux-hardware.org/?probe=5c482e9676) | Jan 18, 2020 |
| Dell          | 0MN1TX A02                  | [5f652869cd](https://linux-hardware.org/?probe=5f652869cd) | Jan 18, 2020 |
| ASRock        | H81M-ITX/WiFi               | [b4fc494391](https://linux-hardware.org/?probe=b4fc494391) | Dec 30, 2019 |
| MSI           | MPG X570 GAMING EDGE WIF... | [6df8cd9ddd](https://linux-hardware.org/?probe=6df8cd9ddd) | Dec 20, 2019 |
| ASUSTek       | P7P55D                      | [a630b7494e](https://linux-hardware.org/?probe=a630b7494e) | Dec 07, 2019 |
| ASUSTek       | Z170-A                      | [23b0f48535](https://linux-hardware.org/?probe=23b0f48535) | Nov 24, 2019 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [2581a2d661](https://linux-hardware.org/?probe=2581a2d661) | Nov 16, 2019 |
| Dell          | 06X1TJ A01                  | [9da4eeda28](https://linux-hardware.org/?probe=9da4eeda28) | Nov 05, 2019 |
| ASUSTek       | P9D WS                      | [549ecf66d0](https://linux-hardware.org/?probe=549ecf66d0) | Oct 23, 2019 |
| HP            | 2AE2                        | [ac16964bc3](https://linux-hardware.org/?probe=ac16964bc3) | Oct 15, 2019 |
| HP            | 2AE2                        | [ea13e02e53](https://linux-hardware.org/?probe=ea13e02e53) | Oct 01, 2019 |
| ASUSTek       | A8NE-FM                     | [741f8cff05](https://linux-hardware.org/?probe=741f8cff05) | Sep 29, 2019 |
| ASUSTek       | H87I-PLUS                   | [b74b1c5ad4](https://linux-hardware.org/?probe=b74b1c5ad4) | Sep 05, 2019 |
| ASUSTek       | M5A78L-M/USB3               | [7c2f30c389](https://linux-hardware.org/?probe=7c2f30c389) | Aug 25, 2019 |
| MSI           | 2AE0                        | [e8c2927bde](https://linux-hardware.org/?probe=e8c2927bde) | Aug 03, 2019 |
| MSI           | B450-A PRO                  | [b1e465082e](https://linux-hardware.org/?probe=b1e465082e) | Aug 02, 2019 |
| MSI           | B450-A PRO                  | [a1382a1557](https://linux-hardware.org/?probe=a1382a1557) | Jul 30, 2019 |
| ASRock        | Z390 Taichi Ultimate        | [62a28aa523](https://linux-hardware.org/?probe=62a28aa523) | Jul 30, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [cdc565d73d](https://linux-hardware.org/?probe=cdc565d73d) | Jul 23, 2019 |
| MSI           | Z97-G43 GAMING              | [5c83686f9c](https://linux-hardware.org/?probe=5c83686f9c) | Jul 14, 2019 |
| MSI           | H87I                        | [b0be456a64](https://linux-hardware.org/?probe=b0be456a64) | Jul 10, 2019 |
| ASUSTek       | B85M-G                      | [08d84a1ff9](https://linux-hardware.org/?probe=08d84a1ff9) | Jul 09, 2019 |
| HP            | 2AE2                        | [7827916e15](https://linux-hardware.org/?probe=7827916e15) | Jul 01, 2019 |
| HP            | 2AE2                        | [b999d6bd6d](https://linux-hardware.org/?probe=b999d6bd6d) | Jun 17, 2019 |
| ASUSTek       | SABERTOOTH P67              | [0eef21306d](https://linux-hardware.org/?probe=0eef21306d) | Jun 17, 2019 |
| Dell          | 06X1TJ A01                  | [9a78ee6839](https://linux-hardware.org/?probe=9a78ee6839) | May 28, 2019 |
| MSI           | X299 SLI PLUS               | [692c95368a](https://linux-hardware.org/?probe=692c95368a) | May 06, 2019 |
| ASUSTek       | STRIX H270I GAMING          | [fc59e7df18](https://linux-hardware.org/?probe=fc59e7df18) | May 04, 2019 |
| ASUSTek       | STRIX H270I GAMING          | [106016dd36](https://linux-hardware.org/?probe=106016dd36) | Apr 28, 2019 |
| ASUSTek       | STRIX H270I GAMING          | [2786657449](https://linux-hardware.org/?probe=2786657449) | Apr 12, 2019 |
| Intel         | DG45FC AAE27730-308         | [459dc2d57f](https://linux-hardware.org/?probe=459dc2d57f) | Apr 08, 2019 |
| Gigabyte      | Z97MX-Gaming 5              | [d94ade2c40](https://linux-hardware.org/?probe=d94ade2c40) | Mar 27, 2019 |
| Dell          | 0K240Y A01                  | [4683a284a4](https://linux-hardware.org/?probe=4683a284a4) | Mar 26, 2019 |
| MSI           | 2AE0                        | [5585935586](https://linux-hardware.org/?probe=5585935586) | Mar 25, 2019 |
| Dell          | 0HN7XN A01                  | [0b8a535d2a](https://linux-hardware.org/?probe=0b8a535d2a) | Mar 16, 2019 |
| ASUSTek       | SABERTOOTH P67              | [eaa09576b4](https://linux-hardware.org/?probe=eaa09576b4) | Mar 12, 2019 |
| Pegatron      | 2A72h                       | [aa54b4c1d3](https://linux-hardware.org/?probe=aa54b4c1d3) | Mar 07, 2019 |
| MSI           | Z68A-GD65                   | [883872e8b0](https://linux-hardware.org/?probe=883872e8b0) | Feb 18, 2019 |
| ASUSTek       | B85M-G                      | [b45f44a0f7](https://linux-hardware.org/?probe=b45f44a0f7) | Jan 23, 2019 |
| Lenovo        | 36EF SDK0J40700 WIN 3258... | [b077a03fb3](https://linux-hardware.org/?probe=b077a03fb3) | Jan 07, 2019 |
| HP            | 0B54h D                     | [1456dd6d91](https://linux-hardware.org/?probe=1456dd6d91) | Jan 06, 2019 |
| Dell          | 0RW203                      | [7773935ee9](https://linux-hardware.org/?probe=7773935ee9) | Dec 23, 2018 |
| Dell          | 0RW203                      | [bb86cab506](https://linux-hardware.org/?probe=bb86cab506) | Dec 23, 2018 |
| ASUSTek       | SABERTOOTH Z77              | [41b6e4c6b2](https://linux-hardware.org/?probe=41b6e4c6b2) | Dec 06, 2018 |
| ASUSTek       | EB1501P                     | [4a6eb1071a](https://linux-hardware.org/?probe=4a6eb1071a) | Oct 21, 2018 |
| Gigabyte      | F2A75M-D3H                  | [41a0eb1b0d](https://linux-hardware.org/?probe=41a0eb1b0d) | Oct 06, 2018 |
| ASUSTek       | AM1I-A                      | [e6a8378a5b](https://linux-hardware.org/?probe=e6a8378a5b) | Jun 15, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 40       | 12.82%  |
| Ubuntu 18.04                 | 22       | 7.05%   |
| Zorin 16                     | 9        | 2.88%   |
| Pop!_OS 22.04                | 9        | 2.88%   |
| Arch Rolling                 | 9        | 2.88%   |
| Ubuntu 18.10                 | 8        | 2.56%   |
| OpenMandriva 4.2             | 8        | 2.56%   |
| Arch                         | 8        | 2.56%   |
| Ubuntu 19.10                 | 7        | 2.24%   |
| Fedora 35                    | 7        | 2.24%   |
| Debian 11                    | 7        | 2.24%   |
| ArcoLinux Rolling            | 7        | 2.24%   |
| Ubuntu 22.04                 | 6        | 1.92%   |
| Pop!_OS 21.04                | 6        | 1.92%   |
| OpenMandriva 4.3             | 6        | 1.92%   |
| Fedora 36                    | 6        | 1.92%   |
| Fedora 32                    | 6        | 1.92%   |
| Ubuntu 20.10                 | 5        | 1.6%    |
| Pop!_OS 20.04                | 5        | 1.6%    |
| Manjaro                      | 5        | 1.6%    |
| Zorin 15                     | 4        | 1.28%   |
| Ubuntu 21.10                 | 4        | 1.28%   |
| Ubuntu 19.04                 | 4        | 1.28%   |
| Pop!_OS 21.10                | 4        | 1.28%   |
| Pop!_OS 20.10                | 4        | 1.28%   |
| openSUSE Tumbleweed-XXXXXXXX | 4        | 1.28%   |
| Linux Mint 20.2              | 4        | 1.28%   |
| Linux Mint 20.1              | 4        | 1.28%   |
| KDE neon 20.04               | 4        | 1.28%   |
| Fedora 34                    | 4        | 1.28%   |
| Fedora 33                    | 4        | 1.28%   |
| Debian 10                    | 4        | 1.28%   |
| Ubuntu 21.04                 | 3        | 0.96%   |
| OpenMandriva 4.50            | 3        | 0.96%   |
| Manjaro 20.1                 | 3        | 0.96%   |
| Linux Mint 19.1              | 3        | 0.96%   |
| Kubuntu 20.04                | 3        | 0.96%   |
| Gentoo 2.7                   | 3        | 0.96%   |
| Fedora 31                    | 3        | 0.96%   |
| Manjaro 20.2.1               | 2        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 94       | 31.54%  |
| Fedora        | 29       | 9.73%   |
| Pop!_OS       | 24       | 8.05%   |
| Manjaro       | 18       | 6.04%   |
| OpenMandriva  | 17       | 5.7%    |
| Linux Mint    | 17       | 5.7%    |
| Arch          | 17       | 5.7%    |
| Debian        | 14       | 4.7%    |
| Zorin         | 13       | 4.36%   |
| ArcoLinux     | 7        | 2.35%   |
| openSUSE      | 6        | 2.01%   |
| KDE neon      | 5        | 1.68%   |
| Xubuntu       | 4        | 1.34%   |
| Kubuntu       | 4        | 1.34%   |
| Gentoo        | 4        | 1.34%   |
| Clear Linux   | 4        | 1.34%   |
| ROSA          | 3        | 1.01%   |
| Ubuntu Budgie | 2        | 0.67%   |
| EndeavourOS   | 2        | 0.67%   |
| CentOS        | 2        | 0.67%   |
| Alpine        | 2        | 0.67%   |
| Ubuntu Studio | 1        | 0.34%   |
| Ubuntu MATE   | 1        | 0.34%   |
| Solus         | 1        | 0.34%   |
| Rocky Linux   | 1        | 0.34%   |
| Nobara        | 1        | 0.34%   |
| LMDE          | 1        | 0.34%   |
| Kali          | 1        | 0.34%   |
| Garuda Linux  | 1        | 0.34%   |
| Feren OS      | 1        | 0.34%   |
| Elementary    | 1        | 0.34%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 8        | 2.31%   |
| 5.16.7-desktop-1omv4003  | 6        | 1.73%   |
| 4.18.0-16-generic        | 6        | 1.73%   |
| 5.11.0-38-generic        | 5        | 1.45%   |
| 5.4.0-47-generic         | 4        | 1.16%   |
| 5.4.0-42-generic         | 4        | 1.16%   |
| 5.19.0-76051900-generic  | 4        | 1.16%   |
| 5.15.0-41-generic        | 4        | 1.16%   |
| 5.8.0-7630-generic       | 3        | 0.87%   |
| 5.4.0-74-generic         | 3        | 0.87%   |
| 5.4.0-51-generic         | 3        | 0.87%   |
| 5.4.0-29-generic         | 3        | 0.87%   |
| 5.3.0-28-generic         | 3        | 0.87%   |
| 5.3.0-18-generic         | 3        | 0.87%   |
| 5.15.7-arch1-1           | 3        | 0.87%   |
| 5.13.0-40-generic        | 3        | 0.87%   |
| 5.13.0-21-generic        | 3        | 0.87%   |
| 5.11.0-7620-generic      | 3        | 0.87%   |
| 5.11.0-27-generic        | 3        | 0.87%   |
| 5.0.0-20-generic         | 3        | 0.87%   |
| 5.9.16-1-MANJARO         | 2        | 0.58%   |
| 5.8.0-48-generic         | 2        | 0.58%   |
| 5.8.0-43-generic         | 2        | 0.58%   |
| 5.8.0-26-generic         | 2        | 0.58%   |
| 5.7.9-arch1-1            | 2        | 0.58%   |
| 5.5.5-200.fc31.x86_64    | 2        | 0.58%   |
| 5.4.0-91-generic         | 2        | 0.58%   |
| 5.4.0-89-generic         | 2        | 0.58%   |
| 5.4.0-80-generic         | 2        | 0.58%   |
| 5.4.0-77-generic         | 2        | 0.58%   |
| 5.4.0-7642-generic       | 2        | 0.58%   |
| 5.4.0-72-generic         | 2        | 0.58%   |
| 5.4.0-70-generic         | 2        | 0.58%   |
| 5.4.0-58-generic         | 2        | 0.58%   |
| 5.4.0-48-generic         | 2        | 0.58%   |
| 5.4.0-37-generic         | 2        | 0.58%   |
| 5.4.0-26-generic         | 2        | 0.58%   |
| 5.4.0-100-generic        | 2        | 0.58%   |
| 5.3.0-46-generic         | 2        | 0.58%   |
| 5.3.0-45-generic         | 2        | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 49       | 14.98%  |
| 5.11.0  | 20       | 6.12%   |
| 5.3.0   | 16       | 4.89%   |
| 4.18.0  | 16       | 4.89%   |
| 5.8.0   | 15       | 4.59%   |
| 5.13.0  | 15       | 4.59%   |
| 4.15.0  | 11       | 3.36%   |
| 5.15.0  | 9        | 2.75%   |
| 5.0.0   | 9        | 2.75%   |
| 5.10.14 | 8        | 2.45%   |
| 5.10.0  | 8        | 2.45%   |
| 5.16.7  | 6        | 1.83%   |
| 5.16.0  | 5        | 1.53%   |
| 4.19.0  | 5        | 1.53%   |
| 5.19.0  | 4        | 1.22%   |
| 5.9.16  | 3        | 0.92%   |
| 5.17.5  | 3        | 0.92%   |
| 5.15.7  | 3        | 0.92%   |
| 5.15.4  | 3        | 0.92%   |
| 5.14.10 | 3        | 0.92%   |
| 5.9.11  | 2        | 0.61%   |
| 5.8.6   | 2        | 0.61%   |
| 5.8.12  | 2        | 0.61%   |
| 5.7.9   | 2        | 0.61%   |
| 5.7.17  | 2        | 0.61%   |
| 5.7.12  | 2        | 0.61%   |
| 5.6.0   | 2        | 0.61%   |
| 5.5.5   | 2        | 0.61%   |
| 5.19.12 | 2        | 0.61%   |
| 5.18.10 | 2        | 0.61%   |
| 5.17.6  | 2        | 0.61%   |
| 5.17.4  | 2        | 0.61%   |
| 5.16.9  | 2        | 0.61%   |
| 5.16.18 | 2        | 0.61%   |
| 5.15.8  | 2        | 0.61%   |
| 5.15.15 | 2        | 0.61%   |
| 5.13.4  | 2        | 0.61%   |
| 5.12.9  | 2        | 0.61%   |
| 5.11.11 | 2        | 0.61%   |
| 6.0.3   | 1        | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 54       | 16.67%  |
| 5.15    | 28       | 8.64%   |
| 5.8     | 24       | 7.41%   |
| 5.11    | 23       | 7.1%    |
| 5.13    | 22       | 6.79%   |
| 5.10    | 19       | 5.86%   |
| 5.3     | 17       | 5.25%   |
| 5.16    | 17       | 5.25%   |
| 4.18    | 16       | 4.94%   |
| 5.19    | 13       | 4.01%   |
| 5.17    | 11       | 3.4%    |
| 4.15    | 11       | 3.4%    |
| 5.0     | 10       | 3.09%   |
| 5.9     | 9        | 2.78%   |
| 5.7     | 8        | 2.47%   |
| 5.14    | 7        | 2.16%   |
| 5.5     | 6        | 1.85%   |
| 5.18    | 6        | 1.85%   |
| 5.12    | 6        | 1.85%   |
| 4.19    | 5        | 1.54%   |
| 5.6     | 4        | 1.23%   |
| 6.0     | 2        | 0.62%   |
| 4.9     | 1        | 0.31%   |
| 4.4     | 1        | 0.31%   |
| 4.12    | 1        | 0.31%   |
| 4.10    | 1        | 0.31%   |
| 4.1     | 1        | 0.31%   |
| 3.10    | 1        | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 286      | 99.31%  |
| i686   | 2        | 0.69%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 138      | 46.15%  |
| Unknown         | 53       | 17.73%  |
| KDE5            | 46       | 15.38%  |
| XFCE            | 19       | 6.35%   |
| X-Cinnamon      | 11       | 3.68%   |
| KDE             | 11       | 3.68%   |
| i3              | 5        | 1.67%   |
| Budgie          | 4        | 1.34%   |
| Cinnamon        | 3        | 1%      |
| MATE            | 2        | 0.67%   |
| qtile           | 1        | 0.33%   |
| Pantheon        | 1        | 0.33%   |
| LXDE            | 1        | 0.33%   |
| LeftWM          | 1        | 0.33%   |
| KDE4            | 1        | 0.33%   |
| i3-with-shmlog  | 1        | 0.33%   |
| GNOME Flashback | 1        | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 233      | 77.67%  |
| Wayland | 32       | 10.67%  |
| Unknown | 22       | 7.33%   |
| Tty     | 13       | 4.33%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 173      | 57.67%  |
| SDDM    | 40       | 13.33%  |
| GDM     | 40       | 13.33%  |
| LightDM | 19       | 6.33%   |
| GDM3    | 19       | 6.33%   |
| TDM     | 8        | 2.67%   |
| KDM     | 1        | 0.33%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Desktops | Percent |
|---------|----------|---------|
| en_US   | 140      | 47.62%  |
| nb_NO   | 59       | 20.07%  |
| Unknown | 41       | 13.95%  |
| en_GB   | 25       | 8.5%    |
| C       | 7        | 2.38%   |
| nn_NO   | 5        | 1.7%    |
| en_DK   | 5        | 1.7%    |
| de_DE   | 3        | 1.02%   |
| fr_FR   | 2        | 0.68%   |
| ru_RU   | 1        | 0.34%   |
| pt_PT   | 1        | 0.34%   |
| POSIX   | 1        | 0.34%   |
| pl_PL   | 1        | 0.34%   |
| es_ES   | 1        | 0.34%   |
| en_CA   | 1        | 0.34%   |
| en_AG   | 1        | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 156      | 52.88%  |
| EFI  | 139      | 47.12%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 225      | 77.05%  |
| Btrfs   | 33       | 11.3%   |
| Overlay | 15       | 5.14%   |
| Unknown | 9        | 3.08%   |
| Xfs     | 4        | 1.37%   |
| Zfs     | 3        | 1.03%   |
| Ext2    | 3        | 1.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 170      | 58.02%  |
| GPT     | 96       | 32.76%  |
| MBR     | 27       | 9.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 235      | 79.12%  |
| Yes       | 62       | 20.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 190      | 64.41%  |
| Yes       | 105      | 35.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 121      | 42.01%  |
| Gigabyte Technology | 41       | 14.24%  |
| MSI                 | 34       | 11.81%  |
| ASRock              | 21       | 7.29%   |
| Dell                | 19       | 6.6%    |
| Hewlett-Packard     | 17       | 5.9%    |
| Lenovo              | 12       | 4.17%   |
| Acer                | 6        | 2.08%   |
| Pegatron            | 3        | 1.04%   |
| Intel               | 3        | 1.04%   |
| Wibtek              | 1        | 0.35%   |
| Supermicro          | 1        | 0.35%   |
| Shuttle             | 1        | 0.35%   |
| Packard Bell        | 1        | 0.35%   |
| Lenovo Product      | 1        | 0.35%   |
| Fujitsu Siemens     | 1        | 0.35%   |
| Fujitsu             | 1        | 0.35%   |
| Cisco Systems       | 1        | 0.35%   |
| ASRockRack          | 1        | 0.35%   |
| Acidanthera         | 1        | 0.35%   |
| Unknown             | 1        | 0.35%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS All Series                            | 13       | 4.51%   |
| ASUS ROG STRIX X570-F GAMING               | 4        | 1.39%   |
| ASUS ROG STRIX B360-F GAMING               | 4        | 1.39%   |
| ASUS M2R-FVM                               | 4        | 1.39%   |
| MSI MS-7885                                | 3        | 1.04%   |
| Gigabyte GA-970A-UD3                       | 3        | 1.04%   |
| Dell OptiPlex 9020                         | 3        | 1.04%   |
| Dell OptiPlex 7010                         | 3        | 1.04%   |
| ASUS SABERTOOTH P67                        | 3        | 1.04%   |
| ASUS ROG STRIX B550-I GAMING               | 3        | 1.04%   |
| ASUS PRIME X570-P                          | 3        | 1.04%   |
| ASUS P9X79 LE                              | 3        | 1.04%   |
| MSI MS-7A37                                | 2        | 0.69%   |
| MSI MS-7971                                | 2        | 0.69%   |
| Gigabyte Z490I AORUS ULTRA                 | 2        | 0.69%   |
| Gigabyte X570 AORUS ELITE                  | 2        | 0.69%   |
| Gigabyte 970A-DS3P                         | 2        | 0.69%   |
| ASUS Z170 PRO GAMING                       | 2        | 0.69%   |
| ASUS SABERTOOTH Z77                        | 2        | 0.69%   |
| ASUS ROG STRIX X470-F GAMING               | 2        | 0.69%   |
| ASUS ROG STRIX B550-E GAMING               | 2        | 0.69%   |
| ASUS ROG STRIX B460-F GAMING               | 2        | 0.69%   |
| ASUS ROG STRIX B450-F GAMING               | 2        | 0.69%   |
| ASUS PRIME Z270-P                          | 2        | 0.69%   |
| ASUS PRIME X370-PRO                        | 2        | 0.69%   |
| ASUS P8Z77-V LX                            | 2        | 0.69%   |
| ASUS Maximus VIII HERO                     | 2        | 0.69%   |
| ASUS M5A97 R2.0                            | 2        | 0.69%   |
| ASUS EX-A320M-GAMING                       | 2        | 0.69%   |
| ASUS CROSSHAIR VI HERO                     | 2        | 0.69%   |
| ASRock X570 Taichi                         | 2        | 0.69%   |
| Wibtek TH61G-S                             | 1        | 0.35%   |
| Supermicro SYS-7038A-I                     | 1        | 0.35%   |
| Shuttle XS35V4                             | 1        | 0.35%   |
| Pegatron TouchSmart 7320 Lavaca-B EU L6 PC | 1        | 0.35%   |
| Pegatron h8-1080sc                         | 1        | 0.35%   |
| Pegatron Compaq dx2450 Microtower PC       | 1        | 0.35%   |
| Packard Bell IXTREME M5120                 | 1        | 0.35%   |
| MSI MS-7D54                                | 1        | 0.35%   |
| MSI MS-7C94                                | 1        | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Desktops | Percent |
|------------------------|----------|---------|
| ASUS ROG               | 32       | 11.11%  |
| ASUS PRIME             | 17       | 5.9%    |
| Dell OptiPlex          | 13       | 4.51%   |
| ASUS All               | 13       | 4.51%   |
| Lenovo ThinkCentre     | 6        | 2.08%   |
| Gigabyte X570          | 6        | 2.08%   |
| ASUS TUF               | 6        | 2.08%   |
| ASUS SABERTOOTH        | 6        | 2.08%   |
| Gigabyte B450          | 5        | 1.74%   |
| HP EliteDesk           | 4        | 1.39%   |
| Gigabyte B550          | 4        | 1.39%   |
| Dell Precision         | 4        | 1.39%   |
| ASUS STRIX             | 4        | 1.39%   |
| ASUS P9X79             | 4        | 1.39%   |
| ASUS P8Z77-V           | 4        | 1.39%   |
| ASUS M2R-FVM           | 4        | 1.39%   |
| ASUS CROSSHAIR         | 4        | 1.39%   |
| ASRock X570            | 4        | 1.39%   |
| MSI MS-7885            | 3        | 1.04%   |
| Gigabyte GA-970A-UD3   | 3        | 1.04%   |
| ASUS Maximus           | 3        | 1.04%   |
| ASUS M5A97             | 3        | 1.04%   |
| MSI MS-7A37            | 2        | 0.69%   |
| MSI MS-7971            | 2        | 0.69%   |
| Lenovo IdeaCentre      | 2        | 0.69%   |
| HP Z240                | 2        | 0.69%   |
| HP Compaq              | 2        | 0.69%   |
| Gigabyte Z490I         | 2        | 0.69%   |
| Gigabyte 970A-DS3P     | 2        | 0.69%   |
| ASUS Z170              | 2        | 0.69%   |
| ASUS EX-A320M-GAMING   | 2        | 0.69%   |
| ASRock B450M           | 2        | 0.69%   |
| ASRock B450            | 2        | 0.69%   |
| Acer Predator          | 2        | 0.69%   |
| Acer Aspire            | 2        | 0.69%   |
| Wibtek TH61G-S         | 1        | 0.35%   |
| Supermicro SYS-7038A-I | 1        | 0.35%   |
| Shuttle XS35V4         | 1        | 0.35%   |
| Pegatron TouchSmart    | 1        | 0.35%   |
| Pegatron h8-1080sc     | 1        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 33       | 11.46%  |
| 2018 | 33       | 11.46%  |
| 2020 | 30       | 10.42%  |
| 2015 | 27       | 9.38%   |
| 2013 | 27       | 9.38%   |
| 2012 | 27       | 9.38%   |
| 2017 | 22       | 7.64%   |
| 2014 | 20       | 6.94%   |
| 2016 | 13       | 4.51%   |
| 2011 | 13       | 4.51%   |
| 2021 | 10       | 3.47%   |
| 2010 | 10       | 3.47%   |
| 2009 | 8        | 2.78%   |
| 2006 | 5        | 1.74%   |
| 2008 | 3        | 1.04%   |
| 2007 | 3        | 1.04%   |
| 2005 | 2        | 0.69%   |
| 2022 | 1        | 0.35%   |
| 2001 | 1        | 0.35%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 288      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 280      | 95.89%  |
| Enabled  | 12       | 4.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 288      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 92       | 31.62%  |
| 32.01-64.0      | 76       | 26.12%  |
| 8.01-16.0       | 40       | 13.75%  |
| 4.01-8.0        | 29       | 9.97%   |
| 3.01-4.0        | 22       | 7.56%   |
| 64.01-256.0     | 21       | 7.22%   |
| 24.01-32.0      | 5        | 1.72%   |
| More than 256.0 | 2        | 0.69%   |
| 1.01-2.0        | 2        | 0.69%   |
| 2.01-3.0        | 1        | 0.34%   |
| 0.01-0.5        | 1        | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 80       | 24.32%  |
| 4.01-8.0    | 77       | 23.4%   |
| 2.01-3.0    | 59       | 17.93%  |
| 3.01-4.0    | 49       | 14.89%  |
| 8.01-16.0   | 28       | 8.51%   |
| 0.51-1.0    | 17       | 5.17%   |
| 16.01-24.0  | 8        | 2.43%   |
| 0.01-0.5    | 4        | 1.22%   |
| 32.01-64.0  | 3        | 0.91%   |
| 24.01-32.0  | 3        | 0.91%   |
| 64.01-256.0 | 1        | 0.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 87       | 29.39%  |
| 2      | 72       | 24.32%  |
| 3      | 51       | 17.23%  |
| 4      | 38       | 12.84%  |
| 6      | 15       | 5.07%   |
| 5      | 15       | 5.07%   |
| 7      | 6        | 2.03%   |
| 0      | 5        | 1.69%   |
| 8      | 3        | 1.01%   |
| 11     | 2        | 0.68%   |
| 9      | 2        | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 188      | 64.38%  |
| Yes       | 104      | 35.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 285      | 98.96%  |
| No        | 3        | 1.04%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 147      | 50.87%  |
| Yes       | 142      | 49.13%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 184      | 63.23%  |
| Yes       | 107      | 36.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Norway  | 288      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Oslo         | 60       | 19.8%   |
| Trondheim    | 22       | 7.26%   |
| Stavanger    | 13       | 4.29%   |
| Kristiansand | 10       | 3.3%    |
| Bergen       | 9        | 2.97%   |
| Sandefjord   | 6        | 1.98%   |
| Ålesund     | 6        | 1.98%   |
| Skien        | 5        | 1.65%   |
| Fornebu      | 5        | 1.65%   |
| Drammen      | 5        | 1.65%   |
| Nesttun      | 4        | 1.32%   |
| Kongsberg    | 4        | 1.32%   |
| Tromsø      | 3        | 0.99%   |
| Sarpsborg    | 3        | 0.99%   |
| Mo i Rana    | 3        | 0.99%   |
| Lillehammer  | 3        | 0.99%   |
| Heimdal      | 3        | 0.99%   |
| Harstad      | 3        | 0.99%   |
| Fetsund      | 3        | 0.99%   |
| Arendal      | 3        | 0.99%   |
| Vollen       | 2        | 0.66%   |
| Vennesla     | 2        | 0.66%   |
| Vanse        | 2        | 0.66%   |
| Storebo      | 2        | 0.66%   |
| Stokmarknes  | 2        | 0.66%   |
| Stjordal     | 2        | 0.66%   |
| Soreide      | 2        | 0.66%   |
| Sandnes      | 2        | 0.66%   |
| Ramfjordbotn | 2        | 0.66%   |
| Porsgrunn    | 2        | 0.66%   |
| Mysen        | 2        | 0.66%   |
| Mjondalen    | 2        | 0.66%   |
| Lillestrøm  | 2        | 0.66%   |
| Lillesand    | 2        | 0.66%   |
| Larvik       | 2        | 0.66%   |
| Kopervik     | 2        | 0.66%   |
| Jessheim     | 2        | 0.66%   |
| Honefoss     | 2        | 0.66%   |
| Holter       | 2        | 0.66%   |
| Haugesund    | 2        | 0.66%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Desktops | Drives  | Percent |
|---------------------|----------|---------|---------|
| Samsung Electronics | 146      | 252     | 25.57%  |
| Seagate             | 108      | 214     | 18.91%  |
| WDC                 | 83       | 195     | 14.54%  |
| Kingston            | 54       | 78      | 9.46%   |
| Crucial             | 24       | 44      | 4.2%    |
| Intel               | 23       | 29      | 4.03%   |
| Toshiba             | 18       | 22      | 3.15%   |
| Corsair             | 17       | 26      | 2.98%   |
| Phison              | 13       | 17      | 2.28%   |
| Hitachi             | 13       | 18      | 2.28%   |
| SanDisk             | 10       | 15      | 1.75%   |
| HGST                | 10       | 17      | 1.75%   |
| OCZ                 | 9        | 9       | 1.58%   |
| PNY                 | 4        | 6       | 0.7%    |
| Micron Technology   | 4        | 6       | 0.7%    |
| LITEONIT            | 4        | 4       | 0.7%    |
| Intenso             | 3        | 3       | 0.53%   |
| Apple               | 3        | 3       | 0.53%   |
| A-DATA Technology   | 3        | 3       | 0.53%   |
| Unknown             | 2        | 2       | 0.35%   |
| SK hynix            | 2        | 2       | 0.35%   |
| Silicon Motion      | 2        | 3       | 0.35%   |
| LITEON              | 2        | 2       | 0.35%   |
| Unknown             | 2        | 3       | 0.35%   |
| SPCC                | 1        | 1       | 0.18%   |
| SandForce           | 1        | 2       | 0.18%   |
| Radeon              | 1        | 1       | 0.18%   |
| Netac               | 1        | 1       | 0.18%   |
| MBED                | 1        | 1       | 0.18%   |
| LDLC                | 1        | 1       | 0.18%   |
| KingSpec            | 1        | 2       | 0.18%   |
| JMicron Technology  | 1        | Unknown | 0.18%   |
| IET                 | 1        | 2       | 0.18%   |
| Goodram             | 1        | 1       | 0.18%   |
| China               | 1        | 1       | 0.18%   |
| Advantech           | 1        | 1       | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Desktops | Percent |
|----------------------------------------|----------|---------|
| Samsung SSD 860 EVO 1TB                | 11       | 1.53%   |
| Samsung SSD 850 EVO 250GB              | 11       | 1.53%   |
| Samsung SSD 850 EVO 500GB              | 10       | 1.39%   |
| Samsung SSD 840 EVO 250GB              | 10       | 1.39%   |
| Seagate ST4000DM004-2CV104 4TB         | 9        | 1.25%   |
| Kingston SV300S37A120G 120GB SSD       | 9        | 1.25%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 8        | 1.11%   |
| WDC WD30EFRX-68EUZN0 3TB               | 7        | 0.97%   |
| Seagate ST2000DM001-1ER164 2TB         | 7        | 0.97%   |
| Samsung SSD 970 EVO Plus 1TB           | 7        | 0.97%   |
| Samsung SSD 860 EVO 500GB              | 7        | 0.97%   |
| Samsung NVMe SSD Drive 500GB           | 7        | 0.97%   |
| Samsung NVMe SSD Drive 1TB             | 7        | 0.97%   |
| Kingston NVMe SSD Drive 1TB            | 7        | 0.97%   |
| Seagate ST1000DM003-1CH162 1TB         | 6        | 0.84%   |
| Seagate ST1000DM010-2EP102 1TB         | 5        | 0.7%    |
| Samsung SSD 860 EVO 250GB              | 5        | 0.7%    |
| Samsung SSD 840 EVO 120GB              | 5        | 0.7%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 5        | 0.7%    |
| Phison NVMe SSD Drive 1TB              | 5        | 0.7%    |
| Toshiba HDWD110 1TB                    | 4        | 0.56%   |
| Seagate ST500DM002-1BD142 500GB        | 4        | 0.56%   |
| Seagate ST4000VN008-2DR166 4TB         | 4        | 0.56%   |
| Seagate ST2000DM006-2DM164 2TB         | 4        | 0.56%   |
| Seagate ST2000DM001-9YN164 2TB         | 4        | 0.56%   |
| Seagate Expansion 2TB                  | 4        | 0.56%   |
| Seagate Backup+ Hub BK 4TB             | 4        | 0.56%   |
| Samsung NVMe SSD Drive 512GB           | 4        | 0.56%   |
| Samsung NVMe SSD Drive 250GB           | 4        | 0.56%   |
| Samsung MZ7LF192HCGS-000L1 192GB SSD   | 4        | 0.56%   |
| Samsung HD753LJ 752GB                  | 4        | 0.56%   |
| Samsung HD103SJ 1TB                    | 4        | 0.56%   |
| Kingston SV300S37A240G 240GB SSD       | 4        | 0.56%   |
| Kingston SUV400S37240G 240GB SSD       | 4        | 0.56%   |
| Kingston SA2000M81000G 1TB             | 4        | 0.56%   |
| WDC WD30EFRX-68AX9N0 3TB               | 3        | 0.42%   |
| WDC WD10EALX-009BA0 1TB                | 3        | 0.42%   |
| WDC WD1003FZEX-00MK2A0 1TB             | 3        | 0.42%   |
| Toshiba NVMe SSD Drive 256GB           | 3        | 0.42%   |
| Seagate ST8000VN004-2M2101 8TB         | 3        | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 105      | 210    | 43.39%  |
| WDC                 | 71       | 163    | 29.34%  |
| Samsung Electronics | 22       | 34     | 9.09%   |
| Toshiba             | 14       | 15     | 5.79%   |
| Hitachi             | 13       | 18     | 5.37%   |
| HGST                | 10       | 17     | 4.13%   |
| Apple               | 3        | 3      | 1.24%   |
| Unknown             | 1        | 1      | 0.41%   |
| Intenso             | 1        | 1      | 0.41%   |
| IET                 | 1        | 2      | 0.41%   |
| Unknown             | 1        | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 95       | 141    | 40.95%  |
| Kingston            | 38       | 50     | 16.38%  |
| Crucial             | 22       | 42     | 9.48%   |
| Intel               | 15       | 20     | 6.47%   |
| WDC                 | 12       | 22     | 5.17%   |
| Corsair             | 10       | 14     | 4.31%   |
| OCZ                 | 9        | 9      | 3.88%   |
| SanDisk             | 5        | 5      | 2.16%   |
| PNY                 | 4        | 6      | 1.72%   |
| LITEONIT            | 4        | 4      | 1.72%   |
| Micron Technology   | 3        | 5      | 1.29%   |
| A-DATA Technology   | 3        | 3      | 1.29%   |
| LITEON              | 2        | 2      | 0.86%   |
| SPCC                | 1        | 1      | 0.43%   |
| SK hynix            | 1        | 1      | 0.43%   |
| SandForce           | 1        | 2      | 0.43%   |
| Radeon              | 1        | 1      | 0.43%   |
| LDLC                | 1        | 1      | 0.43%   |
| KingSpec            | 1        | 2      | 0.43%   |
| Intenso             | 1        | 1      | 0.43%   |
| Goodram             | 1        | 1      | 0.43%   |
| China               | 1        | 1      | 0.43%   |
| Unknown             | 1        | 2      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 187      | 465    | 38.09%  |
| SSD     | 185      | 336    | 37.68%  |
| NVMe    | 111      | 179    | 22.61%  |
| Unknown | 8        | 7      | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 249      | 771    | 64.68%  |
| NVMe | 111      | 179    | 28.83%  |
| SAS  | 25       | 37     | 6.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 192      | 356    | 44.04%  |
| 0.51-1.0   | 111      | 170    | 25.46%  |
| 1.01-2.0   | 50       | 92     | 11.47%  |
| 3.01-4.0   | 33       | 60     | 7.57%   |
| 2.01-3.0   | 30       | 64     | 6.88%   |
| 4.01-10.0  | 20       | 59     | 4.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 66       | 21.57%  |
| More than 3000 | 50       | 16.34%  |
| 501-1000       | 45       | 14.71%  |
| 251-500        | 43       | 14.05%  |
| 1001-2000      | 39       | 12.75%  |
| 2001-3000      | 19       | 6.21%   |
| Unknown        | 16       | 5.23%   |
| 1-20           | 14       | 4.58%   |
| 51-100         | 10       | 3.27%   |
| 21-50          | 4        | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 89       | 27.81%  |
| 101-250        | 36       | 11.25%  |
| 501-1000       | 36       | 11.25%  |
| 51-100         | 33       | 10.31%  |
| 251-500        | 29       | 9.06%   |
| 1001-2000      | 26       | 8.13%   |
| 21-50          | 23       | 7.19%   |
| More than 3000 | 22       | 6.88%   |
| Unknown        | 16       | 5%      |
| 2001-3000      | 9        | 2.81%   |
| 0              | 1        | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                  | Desktops | Drives | Percent |
|----------------------------------------|----------|--------|---------|
| WDC WD5000AAKS-00UU3A0 500GB           | 2        | 5      | 5.26%   |
| WDC WD30EFRX-68EUZN0 3TB               | 2        | 2      | 5.26%   |
| Seagate ST31000524AS 1TB               | 2        | 2      | 5.26%   |
| WDC WD800JB-00CRA1 80GB                | 1        | 1      | 2.63%   |
| WDC WD800BB-00CAA1 80GB                | 1        | 1      | 2.63%   |
| WDC WD60EFRX-68L0BN1 6TB               | 1        | 1      | 2.63%   |
| WDC WD5000AAJS-00YFA0 500GB            | 1        | 1      | 2.63%   |
| WDC WD3200AAKS-00V1A0 320GB            | 1        | 1      | 2.63%   |
| WDC WD10EALX-009BA0 1TB                | 1        | 1      | 2.63%   |
| WDC WD1002FAEX-00Z3A0 1TB              | 1        | 1      | 2.63%   |
| Toshiba HDWD110 1TB                    | 1        | 1      | 2.63%   |
| Seagate ST9250827AS 250GB              | 1        | 1      | 2.63%   |
| Seagate ST4000VN008-2DR166 4TB         | 1        | 1      | 2.63%   |
| Seagate ST4000LM024-2AN17V 4TB         | 1        | 1      | 2.63%   |
| Seagate ST3500418AS 500GB              | 1        | 1      | 2.63%   |
| Seagate ST31000528AS 1TB               | 1        | 1      | 2.63%   |
| Seagate ST3000DM008-2DM166 3TB         | 1        | 1      | 2.63%   |
| Seagate ST3000DM001-1CH166 3TB         | 1        | 10     | 2.63%   |
| Seagate ST2000DM001-1E6164 2TB         | 1        | 1      | 2.63%   |
| Seagate ST1000DM010-2EP102 1TB         | 1        | 1      | 2.63%   |
| Seagate ST1000DM003-1CH162 1TB         | 1        | 1      | 2.63%   |
| SanDisk SSD PLUS 1000GB                | 1        | 1      | 2.63%   |
| Samsung Electronics SSD 970 EVO 500GB  | 1        | 1      | 2.63%   |
| Samsung Electronics SSD 840 EVO 250GB  | 1        | 1      | 2.63%   |
| Samsung Electronics SP1614C 160GB      | 1        | 1      | 2.63%   |
| OCZ VERTEX3 240GB SSD                  | 1        | 1      | 2.63%   |
| LITEON LCH-256V2S-11 2.5 7mm 256GB SSD | 1        | 1      | 2.63%   |
| LITEON IT LCS-256L9S-HP 256GB SSD      | 1        | 1      | 2.63%   |
| Intel SSDSC2CT120A3 120GB              | 1        | 1      | 2.63%   |
| Intel SSDSC2BF180A4H 180GB             | 1        | 1      | 2.63%   |
| Intel SSDPEKKW256G7 256GB              | 1        | 1      | 2.63%   |
| Hitachi HTS541612J9SA00 120GB          | 1        | 1      | 2.63%   |
| Hitachi HDS722020ALA330 2TB            | 1        | 1      | 2.63%   |
| HGST HDS724040ALE640 4TB               | 1        | 2      | 2.63%   |
| Crucial CT1000P1SSD8 1TB               | 1        | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 21     | 30.56%  |
| WDC                 | 10       | 14     | 27.78%  |
| Samsung Electronics | 3        | 3      | 8.33%   |
| Intel               | 3        | 3      | 8.33%   |
| LITEON              | 2        | 2      | 5.56%   |
| Hitachi             | 2        | 2      | 5.56%   |
| Toshiba             | 1        | 1      | 2.78%   |
| SanDisk             | 1        | 1      | 2.78%   |
| OCZ                 | 1        | 1      | 2.78%   |
| HGST                | 1        | 2      | 2.78%   |
| Crucial             | 1        | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 11       | 21     | 42.31%  |
| WDC                 | 10       | 14     | 38.46%  |
| Hitachi             | 2        | 2      | 7.69%   |
| Toshiba             | 1        | 1      | 3.85%   |
| Samsung Electronics | 1        | 1      | 3.85%   |
| HGST                | 1        | 2      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 24       | 41     | 70.59%  |
| SSD  | 7        | 7      | 20.59%  |
| NVMe | 3        | 3      | 8.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB    | 3        | 3      | 75%     |
| Kingston SV300S37A120G 120GB SSD | 1        | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Apple    | 3        | 3      | 75%     |
| Kingston | 1        | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 177      | 590    | 53.64%  |
| Works    | 116      | 342    | 35.15%  |
| Malfunc  | 33       | 51     | 10%     |
| Failed   | 4        | 4      | 1.21%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 175      | 38.8%   |
| AMD                              | 111      | 24.61%  |
| Samsung Electronics              | 56       | 12.42%  |
| ASMedia Technology               | 23       | 5.1%    |
| Phison Electronics               | 19       | 4.21%   |
| Kingston Technology Company      | 19       | 4.21%   |
| SanDisk                          | 12       | 2.66%   |
| LSI Logic / Symbios Logic        | 6        | 1.33%   |
| Nvidia                           | 5        | 1.11%   |
| JMicron Technology               | 5        | 1.11%   |
| Toshiba America Info Systems     | 4        | 0.89%   |
| Marvell Technology Group         | 4        | 0.89%   |
| Silicon Motion                   | 2        | 0.44%   |
| Micron/Crucial Technology        | 2        | 0.44%   |
| Broadcom / LSI                   | 2        | 0.44%   |
| SK hynix                         | 1        | 0.22%   |
| Silicon Integrated Systems [SiS] | 1        | 0.22%   |
| Silicon Image                    | 1        | 0.22%   |
| Seagate Technology               | 1        | 0.22%   |
| Micron Technology                | 1        | 0.22%   |
| ADATA Technology                 | 1        | 0.22%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Desktops | Percent |
|----------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 69       | 12.68%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 33       | 6.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 23       | 4.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 23       | 4.23%   |
| ASMedia ASM1062 Serial ATA Controller                                            | 22       | 4.04%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 20       | 3.68%   |
| AMD 400 Series Chipset SATA Controller                                           | 20       | 3.68%   |
| Intel SATA Controller [RAID mode]                                                | 18       | 3.31%   |
| AMD 500 Series Chipset SATA Controller                                           | 18       | 3.31%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]     | 17       | 3.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                 | 17       | 3.13%   |
| Kingston Company A2000 NVMe SSD                                                  | 13       | 2.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11       | 2.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 10       | 1.84%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                       | 10       | 1.84%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 9        | 1.65%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                 | 9        | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller    | 9        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 9        | 1.65%   |
| Phison E12 NVMe Controller                                                       | 8        | 1.47%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                        | 7        | 1.29%   |
| AMD 300 Series Chipset SATA Controller                                           | 6        | 1.1%    |
| Intel SSD 660P Series                                                            | 5        | 0.92%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                        | 5        | 0.92%   |
| AMD X370 Series Chipset SATA Controller                                          | 5        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 5        | 0.92%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 5        | 0.92%   |
| AMD SB600 IDE                                                                    | 5        | 0.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4        | 0.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 4        | 0.74%   |
| Kingston Company KC2000 NVMe SSD                                                 | 4        | 0.74%   |
| JMicron JMB362 SATA Controller                                                   | 4        | 0.74%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4        | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4        | 0.74%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 3        | 0.55%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 3        | 0.55%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                | 3        | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3        | 0.55%   |
| AMD FCH IDE Controller                                                           | 3        | 0.55%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 2        | 0.37%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 255      | 58.62%  |
| NVMe | 112      | 25.75%  |
| IDE  | 38       | 8.74%   |
| RAID | 24       | 5.52%   |
| SAS  | 3        | 0.69%   |
| SCSI | 3        | 0.69%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 171      | 59.38%  |
| AMD    | 117      | 40.63%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor        | 10       | 3.46%   |
| AMD Ryzen 7 2700X Eight-Core Processor     | 8        | 2.77%   |
| AMD Ryzen 5 5600X 6-Core Processor         | 8        | 2.77%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 7        | 2.42%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 7        | 2.42%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 6        | 2.08%   |
| AMD Ryzen 5 3600 6-Core Processor          | 6        | 2.08%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 5        | 1.73%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 5        | 1.73%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 5        | 1.73%   |
| Intel Core i7-5820K CPU @ 3.30GHz          | 4        | 1.38%   |
| Intel Core i7-3770K CPU @ 3.50GHz          | 4        | 1.38%   |
| Intel Core i7-2600K CPU @ 3.40GHz          | 4        | 1.38%   |
| Intel Core i5-4460 CPU @ 3.20GHz           | 4        | 1.38%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 4        | 1.38%   |
| AMD Ryzen 5 1600 Six-Core Processor        | 4        | 1.38%   |
| AMD Athlon 64 X2 Dual Core Processor 5400+ | 4        | 1.38%   |
| Intel Core i9-9900K CPU @ 3.60GHz          | 3        | 1.04%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 3        | 1.04%   |
| Intel Core i7-7700 CPU @ 3.60GHz           | 3        | 1.04%   |
| Intel Core i7-6800K CPU @ 3.40GHz          | 3        | 1.04%   |
| Intel Core i7-3820 CPU @ 3.60GHz           | 3        | 1.04%   |
| Intel Core i5-9600K CPU @ 3.70GHz          | 3        | 1.04%   |
| Intel Core i5-6600K CPU @ 3.50GHz          | 3        | 1.04%   |
| Intel Core i5-4590 CPU @ 3.30GHz           | 3        | 1.04%   |
| AMD Ryzen 7 1700 Eight-Core Processor      | 3        | 1.04%   |
| AMD Ryzen 5 2600 Six-Core Processor        | 3        | 1.04%   |
| AMD FX-8350 Eight-Core Processor           | 3        | 1.04%   |
| AMD FX-6300 Six-Core Processor             | 3        | 1.04%   |
| Intel Xeon CPU E5-1650 v3 @ 3.50GHz        | 2        | 0.69%   |
| Intel Core i9-10900 CPU @ 2.80GHz          | 2        | 0.69%   |
| Intel Core i7-9700K CPU @ 3.60GHz          | 2        | 0.69%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 2        | 0.69%   |
| Intel Core i7-6700 CPU @ 3.40GHz           | 2        | 0.69%   |
| Intel Core i7-2600 CPU @ 3.40GHz           | 2        | 0.69%   |
| Intel Core i5-7400 CPU @ 3.00GHz           | 2        | 0.69%   |
| Intel Core i5-6600 CPU @ 3.30GHz           | 2        | 0.69%   |
| Intel Core i5-6400 CPU @ 2.70GHz           | 2        | 0.69%   |
| Intel Core i5-4670K CPU @ 3.40GHz          | 2        | 0.69%   |
| Intel Core i5-4570S CPU @ 2.90GHz          | 2        | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i7           | 62       | 21.45%  |
| Intel Core i5           | 53       | 18.34%  |
| AMD Ryzen 7             | 28       | 9.69%   |
| AMD Ryzen 5             | 26       | 9%      |
| AMD Ryzen 9             | 21       | 7.27%   |
| Intel Core i3           | 13       | 4.5%    |
| Intel Xeon              | 11       | 3.81%   |
| AMD FX                  | 11       | 3.81%   |
| Intel Core i9           | 9        | 3.11%   |
| AMD Athlon 64 X2        | 6        | 2.08%   |
| Other                   | 5        | 1.73%   |
| Intel Pentium           | 5        | 1.73%   |
| AMD A10                 | 4        | 1.38%   |
| Intel Celeron           | 3        | 1.04%   |
| AMD Phenom II X4        | 3        | 1.04%   |
| Intel Pentium Dual-Core | 2        | 0.69%   |
| Intel Core 2 Duo        | 2        | 0.69%   |
| Intel Core 2            | 2        | 0.69%   |
| Intel Atom              | 2        | 0.69%   |
| AMD Ryzen Threadripper  | 2        | 0.69%   |
| AMD Athlon II X4        | 2        | 0.69%   |
| AMD Athlon              | 2        | 0.69%   |
| AMD A4                  | 2        | 0.69%   |
| Intel Pentium III       | 1        | 0.35%   |
| Intel Pentium Dual      | 1        | 0.35%   |
| Intel Core 2 Quad       | 1        | 0.35%   |
| AMD Sempron             | 1        | 0.35%   |
| AMD Ryzen 7 PRO         | 1        | 0.35%   |
| AMD Ryzen 3             | 1        | 0.35%   |
| AMD Phenom II X6        | 1        | 0.35%   |
| AMD EPYC                | 1        | 0.35%   |
| AMD Dual Core Opteron   | 1        | 0.35%   |
| AMD Athlon II X2        | 1        | 0.35%   |
| AMD Athlon Dual Core    | 1        | 0.35%   |
| AMD A8                  | 1        | 0.35%   |
| AMD A6                  | 1        | 0.35%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 106      | 36.68%  |
| 6      | 51       | 17.65%  |
| 2      | 47       | 16.26%  |
| 8      | 40       | 13.84%  |
| 12     | 16       | 5.54%   |
| 16     | 9        | 3.11%   |
| 10     | 6        | 2.08%   |
| 3      | 6        | 2.08%   |
| 1      | 5        | 1.73%   |
| 32     | 1        | 0.35%   |
| 28     | 1        | 0.35%   |
| 24     | 1        | 0.35%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 283      | 98.26%  |
| 2      | 5        | 1.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 201      | 69.79%  |
| 1      | 87       | 30.21%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 283      | 98.26%  |
| Unknown        | 4        | 1.39%   |
| 32-bit         | 1        | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 81       | 27.27%  |
| 0x306c3    | 27       | 9.09%   |
| 0x306a9    | 18       | 6.06%   |
| 0x08701021 | 15       | 5.05%   |
| 0x506e3    | 14       | 4.71%   |
| 0x906e9    | 12       | 4.04%   |
| 0x206a7    | 8        | 2.69%   |
| 0x08701013 | 8        | 2.69%   |
| 0x306f2    | 6        | 2.02%   |
| 0x0a201016 | 6        | 2.02%   |
| 0x06000852 | 6        | 2.02%   |
| 0x906ea    | 5        | 1.68%   |
| 0x0a201009 | 5        | 1.68%   |
| 0x06001119 | 5        | 1.68%   |
| 0x906ed    | 4        | 1.35%   |
| 0x406f1    | 4        | 1.35%   |
| 0x206d7    | 4        | 1.35%   |
| 0x1067a    | 4        | 1.35%   |
| 0x0a201204 | 4        | 1.35%   |
| 0x0800820d | 4        | 1.35%   |
| 0x906ec    | 3        | 1.01%   |
| 0xa0655    | 2        | 0.67%   |
| 0xa0653    | 2        | 0.67%   |
| 0x6fb      | 2        | 0.67%   |
| 0x6f6      | 2        | 0.67%   |
| 0x106e5    | 2        | 0.67%   |
| 0x106ca    | 2        | 0.67%   |
| 0x0a50000c | 2        | 0.67%   |
| 0x08001129 | 2        | 0.67%   |
| 0x06003104 | 2        | 0.67%   |
| 0x0600063e | 2        | 0.67%   |
| 0x010000c8 | 2        | 0.67%   |
| 0xa0671    | 1        | 0.34%   |
| 0x906eb    | 1        | 0.34%   |
| 0x90672    | 1        | 0.34%   |
| 0x806e9    | 1        | 0.34%   |
| 0x6fd      | 1        | 0.34%   |
| 0x68a      | 1        | 0.34%   |
| 0x506c9    | 1        | 0.34%   |
| 0x50657    | 1        | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 39       | 13.54%  |
| KabyLake         | 33       | 11.46%  |
| Zen 2            | 31       | 10.76%  |
| Zen 3            | 25       | 8.68%   |
| Skylake          | 23       | 7.99%   |
| IvyBridge        | 22       | 7.64%   |
| Zen+             | 14       | 4.86%   |
| SandyBridge      | 14       | 4.86%   |
| Piledriver       | 14       | 4.86%   |
| Zen              | 11       | 3.82%   |
| K8 Hammer        | 9        | 3.13%   |
| CometLake        | 8        | 2.78%   |
| K10              | 7        | 2.43%   |
| Broadwell        | 7        | 2.43%   |
| Core             | 5        | 1.74%   |
| Penryn           | 4        | 1.39%   |
| Westmere         | 3        | 1.04%   |
| Nehalem          | 3        | 1.04%   |
| Bulldozer        | 3        | 1.04%   |
| Unknown          | 3        | 1.04%   |
| Steamroller      | 2        | 0.69%   |
| Bonnell          | 2        | 0.69%   |
| TigerLake        | 1        | 0.35%   |
| Silvermont       | 1        | 0.35%   |
| P6               | 1        | 0.35%   |
| Jaguar           | 1        | 0.35%   |
| Goldmont         | 1        | 0.35%   |
| Alderlake Hybrid | 1        | 0.35%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 141      | 45.48%  |
| AMD                        | 97       | 31.29%  |
| Intel                      | 70       | 22.58%  |
| Matrox Electronics Systems | 2        | 0.65%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21       | 6.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 16       | 5.11%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 14       | 4.47%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 10       | 3.19%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 10       | 3.19%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 9        | 2.88%   |
| Intel HD Graphics 530                                                       | 8        | 2.56%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 7        | 2.24%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 2.24%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 6        | 1.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 5        | 1.6%    |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 5        | 1.6%    |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5        | 1.6%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 1.6%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 5        | 1.6%    |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 4        | 1.28%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 4        | 1.28%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.28%   |
| Nvidia GF108 [GeForce GT 630]                                               | 4        | 1.28%   |
| Nvidia GA104 [GeForce RTX 3070]                                             | 4        | 1.28%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 4        | 1.28%   |
| Intel HD Graphics 630                                                       | 4        | 1.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.28%   |
| Nvidia GK208B [GeForce GT 730]                                              | 3        | 0.96%   |
| Nvidia GK110 [GeForce GTX 780]                                              | 3        | 0.96%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 3        | 0.96%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 0.96%   |
| AMD Pitcairn PRO [Radeon HD 7850 / R7 265 / R9 270 1024SP]                  | 3        | 0.96%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 3        | 0.96%   |
| AMD Navi 14 [Radeon RX 5500/5500M / Pro 5500M]                              | 3        | 0.96%   |
| AMD Cezanne                                                                 | 3        | 0.96%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 2        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                       | 2        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 2        | 0.64%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                       | 2        | 0.64%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.64%   |
| Nvidia GT218 [ION]                                                          | 2        | 0.64%   |
| Nvidia GK104 [GeForce GTX 770]                                              | 2        | 0.64%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2        | 0.64%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 2        | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x Nvidia     | 129      | 44.03%  |
| 1 x AMD        | 90       | 30.72%  |
| 1 x Intel      | 57       | 19.45%  |
| Intel + Nvidia | 4        | 1.37%   |
| AMD + Nvidia   | 4        | 1.37%   |
| 2 x Nvidia     | 3        | 1.02%   |
| Intel + AMD    | 3        | 1.02%   |
| 1 x Matrox     | 2        | 0.68%   |
| Other          | 1        | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 186      | 62.42%  |
| Proprietary | 99       | 33.22%  |
| Unknown     | 13       | 4.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 106      | 35.57%  |
| 7.01-8.0   | 53       | 17.79%  |
| 1.01-2.0   | 40       | 13.42%  |
| 3.01-4.0   | 23       | 7.72%   |
| 0.01-0.5   | 18       | 6.04%   |
| 5.01-6.0   | 15       | 5.03%   |
| 0.51-1.0   | 15       | 5.03%   |
| 8.01-16.0  | 14       | 4.7%    |
| 2.01-3.0   | 10       | 3.36%   |
| 4.01-5.0   | 2        | 0.67%   |
| 16.01-24.0 | 2        | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 69       | 21.04%  |
| Dell                 | 39       | 11.89%  |
| AOC                  | 29       | 8.84%   |
| Acer                 | 28       | 8.54%   |
| BenQ                 | 26       | 7.93%   |
| Ancor Communications | 23       | 7.01%   |
| Philips              | 21       | 6.4%    |
| Hewlett-Packard      | 15       | 4.57%   |
| ASUSTek Computer     | 11       | 3.35%   |
| Lenovo               | 8        | 2.44%   |
| Goldstar             | 7        | 2.13%   |
| NEC Computers        | 5        | 1.52%   |
| LG Electronics       | 4        | 1.22%   |
| Unknown              | 3        | 0.91%   |
| HVR                  | 3        | 0.91%   |
| Grundig              | 3        | 0.91%   |
| Eizo                 | 3        | 0.91%   |
| AUS                  | 3        | 0.91%   |
| VOXICON              | 2        | 0.61%   |
| Sony                 | 2        | 0.61%   |
| Iiyama               | 2        | 0.61%   |
| Denver               | 2        | 0.61%   |
| ViewSonic            | 1        | 0.3%    |
| Vestel Elektronik    | 1        | 0.3%    |
| Vestel               | 1        | 0.3%    |
| Toshiba              | 1        | 0.3%    |
| Sharp                | 1        | 0.3%    |
| Positivo             | 1        | 0.3%    |
| Pioneer Electronic   | 1        | 0.3%    |
| Panasonic            | 1        | 0.3%    |
| Packard Bell         | 1        | 0.3%    |
| MSI                  | 1        | 0.3%    |
| Medion               | 1        | 0.3%    |
| Matrox               | 1        | 0.3%    |
| Lenovo Group Limited | 1        | 0.3%    |
| ITE                  | 1        | 0.3%    |
| Gigabyte Technology  | 1        | 0.3%    |
| FUS                  | 1        | 0.3%    |
| CVT                  | 1        | 0.3%    |
| Compaq Computer      | 1        | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Samsung Electronics C49RG9x SAM0F9C 3840x1080 1193x336mm 48.8-inch     | 5        | 1.41%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                      | 5        | 1.41%   |
| Samsung Electronics SyncMaster SAM0255 1680x1050 474x296mm 22.0-inch   | 4        | 1.13%   |
| ASUSTek Computer VG245 AUS24A1 1920x1080 531x299mm 24.0-inch           | 4        | 1.13%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                       | 4        | 1.13%   |
| HVR HTC-VIVE HVRAA01 2160x1200                                         | 3        | 0.85%   |
| Hewlett-Packard Z32x HWP3275 3840x2160 697x392mm 31.5-inch             | 3        | 0.85%   |
| Grundig WXGA GRU4448 1600x1200                                         | 3        | 0.85%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                     | 3        | 0.85%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 0.85%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                     | 3        | 0.85%   |
| AOC AG273QS3R4 AOC2730 2560x1440 597x336mm 27.0-inch                   | 3        | 0.85%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                        | 3        | 0.85%   |
| Ancor Communications ASUS VN247 ACI24C3 1920x1080 520x290mm 23.4-inch  | 3        | 0.85%   |
| Samsung Electronics SyncMaster SAM05CD 1920x1080                       | 2        | 0.56%   |
| Samsung Electronics SyncMaster SAM0302 1680x1050 459x296mm 21.5-inch   | 2        | 0.56%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch       | 2        | 0.56%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.56%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch      | 2        | 0.56%   |
| Samsung Electronics LCD Monitor SAM0F0B 3840x2160 1210x680mm 54.6-inch | 2        | 0.56%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch    | 2        | 0.56%   |
| Samsung Electronics C34H89x SAM0E25 3440x1440 797x333mm 34.0-inch      | 2        | 0.56%   |
| Samsung Electronics C32HG7x SAM0E14 2560x1440 700x390mm 31.5-inch      | 2        | 0.56%   |
| Philips LCD Monitor FTV 1920x1080                                      | 2        | 0.56%   |
| LG Electronics LCD Monitor LG TV SSCR2 3840x2160                       | 2        | 0.56%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch              | 2        | 0.56%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2        | 0.56%   |
| Eizo S2402W ENC1996 1920x1200 519x324mm 24.1-inch                      | 2        | 0.56%   |
| Dell P2212H DELA07F 1920x1080 531x299mm 24.0-inch                      | 2        | 0.56%   |
| BenQ LCD Monitor BNQ7D04 1920x1080 480x270mm 21.7-inch                 | 2        | 0.56%   |
| BenQ G2420HD BNQ7840 1920x1080 531x299mm 24.0-inch                     | 2        | 0.56%   |
| BenQ G2411HD BNQ7825 1920x1080 531x299mm 24.0-inch                     | 2        | 0.56%   |
| ASUSTek Computer VZ249 AUS24CC 1920x1080 527x296mm 23.8-inch           | 2        | 0.56%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2        | 0.56%   |
| AOC AG352QG2 AOC3520 2560x1080 820x346mm 35.0-inch                     | 2        | 0.56%   |
| Ancor Communications VG248 ACI24A5 1920x1080 531x299mm 24.0-inch       | 2        | 0.56%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 2        | 0.56%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.56%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch  | 2        | 0.56%   |
| Ancor Communications ASUS MG279 ACI27A7 2560x1440 597x336mm 27.0-inch  | 2        | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 130      | 40.63%  |
| 3840x2160 (4K)     | 44       | 13.75%  |
| 2560x1440 (QHD)    | 38       | 11.88%  |
| 1920x1200 (WUXGA)  | 22       | 6.88%   |
| 3440x1440          | 20       | 6.25%   |
| 3840x1080          | 11       | 3.44%   |
| Unknown            | 11       | 3.44%   |
| 1680x1050 (WSXGA+) | 9        | 2.81%   |
| 1280x1024 (SXGA)   | 6        | 1.88%   |
| 2560x1080          | 4        | 1.25%   |
| 1600x1200          | 4        | 1.25%   |
| 3840x1600          | 3        | 0.94%   |
| 2160x1200          | 3        | 0.94%   |
| 5120x1440          | 2        | 0.63%   |
| 4480x1440          | 2        | 0.63%   |
| 1360x768           | 2        | 0.63%   |
| 7680x1440          | 1        | 0.31%   |
| 7680x1080          | 1        | 0.31%   |
| 5760x2160          | 1        | 0.31%   |
| 5360x1440          | 1        | 0.31%   |
| 3840x1200          | 1        | 0.31%   |
| 3840x1024          | 1        | 0.31%   |
| 2560x1600          | 1        | 0.31%   |
| 2288x1287          | 1        | 0.31%   |
| 1280x720 (HD)      | 1        | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 24      | 79       | 24.69%  |
| 27      | 61       | 19.06%  |
| Unknown | 47       | 14.69%  |
| 23      | 27       | 8.44%   |
| 34      | 18       | 5.63%   |
| 31      | 14       | 4.38%   |
| 21      | 11       | 3.44%   |
| 84      | 8        | 2.5%    |
| 48      | 8        | 2.5%    |
| 22      | 7        | 2.19%   |
| 54      | 5        | 1.56%   |
| 19      | 5        | 1.56%   |
| 25      | 4        | 1.25%   |
| 37      | 3        | 0.94%   |
| 35      | 3        | 0.94%   |
| 32      | 3        | 0.94%   |
| 20      | 3        | 0.94%   |
| 33      | 2        | 0.63%   |
| 142     | 1        | 0.31%   |
| 72      | 1        | 0.31%   |
| 65      | 1        | 0.31%   |
| 60      | 1        | 0.31%   |
| 55      | 1        | 0.31%   |
| 44      | 1        | 0.31%   |
| 43      | 1        | 0.31%   |
| 40      | 1        | 0.31%   |
| 39      | 1        | 0.31%   |
| 30      | 1        | 0.31%   |
| 26      | 1        | 0.31%   |
| 18      | 1        | 0.31%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 148      | 49.33%  |
| Unknown        | 47       | 15.67%  |
| 701-800        | 22       | 7.33%   |
| 601-700        | 22       | 7.33%   |
| 401-500        | 19       | 6.33%   |
| 1001-1500      | 16       | 5.33%   |
| 801-900        | 9        | 3%      |
| 1501-2000      | 9        | 3%      |
| 351-400        | 6        | 2%      |
| More than 2000 | 1        | 0.33%   |
| 901-1000       | 1        | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 174      | 59.18%  |
| Unknown | 38       | 12.93%  |
| 16/10   | 37       | 12.59%  |
| 21/9    | 24       | 8.16%   |
| 32/9    | 8        | 2.72%   |
| 5/4     | 5        | 1.7%    |
| 4/3     | 3        | 1.02%   |
| 3/2     | 2        | 0.68%   |
| 6/5     | 1        | 0.34%   |
| 3.76    | 1        | 0.34%   |
| 1.00    | 1        | 0.34%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 88       | 28.48%  |
| 301-350        | 62       | 20.06%  |
| Unknown        | 47       | 15.21%  |
| 351-500        | 40       | 12.94%  |
| 251-300        | 30       | 9.71%   |
| More than 1000 | 18       | 5.83%   |
| 501-1000       | 13       | 4.21%   |
| 151-200        | 11       | 3.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 162      | 54.36%  |
| 101-120 | 55       | 18.46%  |
| Unknown | 47       | 15.77%  |
| 121-160 | 14       | 4.7%    |
| 1-50    | 12       | 4.03%   |
| 161-240 | 8        | 2.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 197      | 67.01%  |
| 2     | 63       | 21.43%  |
| 0     | 21       | 7.14%   |
| 3     | 11       | 3.74%   |
| 4     | 2        | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Desktops | Percent |
|----------------------------------------|----------|---------|
| Intel                                  | 171      | 40.81%  |
| Realtek Semiconductor                  | 126      | 30.07%  |
| Qualcomm Atheros                       | 21       | 5.01%   |
| Broadcom                               | 16       | 3.82%   |
| NetGear                                | 10       | 2.39%   |
| Ralink                                 | 7        | 1.67%   |
| Ralink Technology                      | 6        | 1.43%   |
| TP-Link                                | 5        | 1.19%   |
| Nvidia                                 | 5        | 1.19%   |
| ASUSTek Computer                       | 5        | 1.19%   |
| Samsung Electronics                    | 4        | 0.95%   |
| Motorola PCS                           | 4        | 0.95%   |
| Linksys                                | 4        | 0.95%   |
| Aquantia                               | 4        | 0.95%   |
| Microchip Technology                   | 3        | 0.72%   |
| Marvell Technology Group               | 3        | 0.72%   |
| Chu Yuen Enterprise                    | 3        | 0.72%   |
| ASIX Electronics                       | 3        | 0.72%   |
| Sigma Designs                          | 2        | 0.48%   |
| Qualcomm Atheros Communications        | 2        | 0.48%   |
| Microsoft                              | 2        | 0.48%   |
| Winbond Electronics                    | 1        | 0.24%   |
| Wacom                                  | 1        | 0.24%   |
| Sony Ericsson Mobile Communications AB | 1        | 0.24%   |
| SEGGER                                 | 1        | 0.24%   |
| OnePlus                                | 1        | 0.24%   |
| MediaTek                               | 1        | 0.24%   |
| Huawei Technologies                    | 1        | 0.24%   |
| Holtek Semiconductor                   | 1        | 0.24%   |
| DisplayLink                            | 1        | 0.24%   |
| Cisco Systems                          | 1        | 0.24%   |
| ATEN International                     | 1        | 0.24%   |
| Arduino SA                             | 1        | 0.24%   |
| 3Com                                   | 1        | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 100      | 20.2%   |
| Intel I211 Gigabit Network Connection                             | 40       | 8.08%   |
| Intel Wi-Fi 6 AX200                                               | 32       | 6.46%   |
| Intel Ethernet Connection (2) I219-V                              | 20       | 4.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15       | 3.03%   |
| Intel Ethernet Controller I225-V                                  | 14       | 2.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 2.22%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 2.02%   |
| Intel Ethernet Connection (2) I218-V                              | 10       | 2.02%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 1.82%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 1.82%   |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]       | 8        | 1.62%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7        | 1.41%   |
| Intel I210 Gigabit Network Connection                             | 6        | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6        | 1.21%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.01%   |
| Intel Wireless-AC 9260                                            | 5        | 1.01%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 1.01%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.01%   |
| Motorola PCS Moto E LTE                                           | 4        | 0.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4        | 0.81%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.61%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3        | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3        | 0.61%   |
| Microchip HTC Hub Controller                                      | 3        | 0.61%   |
| Intel Wireless 7265                                               | 3        | 0.61%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.61%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3        | 0.61%   |
| Intel Centrino Wireless-N 2230                                    | 3        | 0.61%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.61%   |
| Chu Yuen Enterprise GN-WB32L 802.11n USB WLAN Card                | 3        | 0.61%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 3        | 0.61%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2        | 0.4%    |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                   | 2        | 0.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2        | 0.4%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2        | 0.4%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.4%    |
| Realtek 802.11ac NIC                                              | 2        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 69       | 46%     |
| Realtek Semiconductor           | 15       | 10%     |
| Broadcom                        | 11       | 7.33%   |
| Qualcomm Atheros                | 10       | 6.67%   |
| NetGear                         | 10       | 6.67%   |
| Ralink                          | 7        | 4.67%   |
| Ralink Technology               | 6        | 4%      |
| TP-Link                         | 5        | 3.33%   |
| ASUSTek Computer                | 5        | 3.33%   |
| Linksys                         | 3        | 2%      |
| Chu Yuen Enterprise             | 3        | 2%      |
| Qualcomm Atheros Communications | 2        | 1.33%   |
| Microsoft                       | 2        | 1.33%   |
| Wacom                           | 1        | 0.67%   |
| MediaTek                        | 1        | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 32       | 21.33%  |
| NetGear A6100 AC600 DB Wireless Adapter [Realtek RTL8811AU]    | 8        | 5.33%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 7        | 4.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6        | 4%      |
| Intel Wireless-AC 9260                                         | 5        | 3.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4        | 2.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 3        | 2%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3        | 2%      |
| Intel Wireless 7265                                            | 3        | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 3        | 2%      |
| Intel Centrino Wireless-N 2230                                 | 3        | 2%      |
| Chu Yuen Enterprise GN-WB32L 802.11n USB WLAN Card             | 3        | 2%      |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 3        | 2%      |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2        | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2        | 1.33%   |
| Realtek 802.11ac NIC                                           | 2        | 1.33%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 2        | 1.33%   |
| Ralink RT5592 PCIe Wireless Network Adapter                    | 2        | 1.33%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 2        | 1.33%   |
| Ralink RT2561/RT61 802.11g PCI                                 | 2        | 1.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2        | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                | 2        | 1.33%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2        | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2        | 1.33%   |
| Linksys WUSB6400M                                              | 2        | 1.33%   |
| Intel Wireless 8265 / 8275                                     | 2        | 1.33%   |
| Intel Wireless 8260                                            | 2        | 1.33%   |
| Intel Wireless 7260                                            | 2        | 1.33%   |
| Intel Wireless 3160                                            | 2        | 1.33%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                       | 1        | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1        | 0.67%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                     | 1        | 0.67%   |
| TP-Link Archer T4U ver.3                                       | 1        | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1        | 0.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1        | 0.67%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1        | 0.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1        | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 1        | 0.67%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Intel                    | 150      | 47.62%  |
| Realtek Semiconductor    | 121      | 38.41%  |
| Qualcomm Atheros         | 13       | 4.13%   |
| Nvidia                   | 5        | 1.59%   |
| Broadcom                 | 5        | 1.59%   |
| Samsung Electronics      | 4        | 1.27%   |
| Aquantia                 | 4        | 1.27%   |
| Marvell Technology Group | 3        | 0.95%   |
| ASIX Electronics         | 3        | 0.95%   |
| OnePlus                  | 1        | 0.32%   |
| Linksys                  | 1        | 0.32%   |
| Huawei Technologies      | 1        | 0.32%   |
| DisplayLink              | 1        | 0.32%   |
| Cisco Systems            | 1        | 0.32%   |
| ATEN International       | 1        | 0.32%   |
| 3Com                     | 1        | 0.32%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 100      | 30.21%  |
| Intel I211 Gigabit Network Connection                             | 40       | 12.08%  |
| Intel Ethernet Connection (2) I219-V                              | 20       | 6.04%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15       | 4.53%   |
| Intel Ethernet Controller I225-V                                  | 14       | 4.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11       | 3.32%   |
| Intel Ethernet Connection I217-LM                                 | 10       | 3.02%   |
| Intel Ethernet Connection (2) I218-V                              | 10       | 3.02%   |
| Intel Ethernet Connection (7) I219-V                              | 9        | 2.72%   |
| Intel 82579V Gigabit Network Connection                           | 9        | 2.72%   |
| Intel I210 Gigabit Network Connection                             | 6        | 1.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5        | 1.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 5        | 1.51%   |
| Intel 82574L Gigabit Network Connection                           | 5        | 1.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3        | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 3        | 0.91%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.91%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 3        | 0.91%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2        | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2        | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.6%    |
| Nvidia MCP77 Ethernet                                             | 2        | 0.6%    |
| Nvidia MCP61 Ethernet                                             | 2        | 0.6%    |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 2        | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 2        | 0.6%    |
| Intel Ethernet Connection (2) I218-LM                             | 2        | 0.6%    |
| Intel Ethernet Connection (12) I219-V                             | 2        | 0.6%    |
| Intel 82557/8/9/0/1 Ethernet Pro 100                              | 2        | 0.6%    |
| ASIX AX88772                                                      | 2        | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.3%    |
| Realtek RTL-8129                                                  | 1        | 0.3%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1        | 0.3%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1        | 0.3%    |
| OnePlus OnePlus                                                   | 1        | 0.3%    |
| Nvidia CK804 Ethernet Controller                                  | 1        | 0.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 285      | 64.63%  |
| WiFi     | 142      | 32.2%   |
| Modem    | 8        | 1.81%   |
| Unknown  | 6        | 1.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 225      | 75.5%   |
| WiFi     | 72       | 24.16%  |
| Unknown  | 1        | 0.34%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 164      | 56.55%  |
| 2     | 103      | 35.52%  |
| 3     | 19       | 6.55%   |
| 0     | 3        | 1.03%   |
| 4     | 1        | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 265      | 89.83%  |
| Yes  | 30       | 10.17%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 59       | 54.63%  |
| Cambridge Silicon Radio         | 20       | 18.52%  |
| ASUSTek Computer                | 11       | 10.19%  |
| Realtek Semiconductor           | 4        | 3.7%    |
| Belkin Components               | 4        | 3.7%    |
| HTC (High Tech Computer)        | 3        | 2.78%   |
| Broadcom                        | 3        | 2.78%   |
| Qualcomm Atheros Communications | 1        | 0.93%   |
| MediaTek                        | 1        | 0.93%   |
| Integrated System Solution      | 1        | 0.93%   |
| IMC Networks                    | 1        | 0.93%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Intel AX200 Bluetooth                                                | 27       | 24.77%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 20       | 18.35%  |
| Intel Bluetooth wireless interface                                   | 11       | 10.09%  |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 7        | 6.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 5        | 4.59%   |
| Realtek Bluetooth Radio                                              | 4        | 3.67%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 4        | 3.67%   |
| Intel AX210 Bluetooth                                                | 4        | 3.67%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 3        | 2.75%   |
| Intel AX201 Bluetooth                                                | 3        | 2.75%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3        | 2.75%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 3        | 2.75%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 2        | 1.83%   |
| ASUS ASUS USB-BT500                                                  | 2        | 1.83%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 1        | 0.92%   |
| MediaTek Wireless_Device                                             | 1        | 0.92%   |
| Intel Bluetooth Device                                               | 1        | 0.92%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 1        | 0.92%   |
| Integrated System Solution Bluetooth Device                          | 1        | 0.92%   |
| IMC Networks BCM20702A0                                              | 1        | 0.92%   |
| Broadcom Bluetooth 3.0 Device                                        | 1        | 0.92%   |
| Broadcom Bluetooth 2.1 Device                                        | 1        | 0.92%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 1        | 0.92%   |
| Belkin Components Bluetooth Mini Dongle                              | 1        | 0.92%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE                | 1        | 0.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Intel                                        | 163      | 27.72%  |
| AMD                                          | 146      | 24.83%  |
| Nvidia                                       | 140      | 23.81%  |
| C-Media Electronics                          | 20       | 3.4%    |
| SteelSeries ApS                              | 14       | 2.38%   |
| Logitech                                     | 12       | 2.04%   |
| Kingston Technology                          | 7        | 1.19%   |
| Blue Microphones                             | 7        | 1.19%   |
| Focusrite-Novation                           | 5        | 0.85%   |
| Creative Labs                                | 5        | 0.85%   |
| Corsair                                      | 5        | 0.85%   |
| Texas Instruments                            | 4        | 0.68%   |
| SAVITECH                                     | 4        | 0.68%   |
| GN Netcom                                    | 4        | 0.68%   |
| ASUSTek Computer                             | 4        | 0.68%   |
| Realtek Semiconductor                        | 3        | 0.51%   |
| Razer USA                                    | 3        | 0.51%   |
| Creative Technology                          | 3        | 0.51%   |
| Yamaha                                       | 2        | 0.34%   |
| XMOS                                         | 2        | 0.34%   |
| RODE Microphones                             | 2        | 0.34%   |
| M-Audio                                      | 2        | 0.34%   |
| GYROCOM C&C                                  | 2        | 0.34%   |
| FiiO Electronics Technology                  | 2        | 0.34%   |
| Asahi Kasei Microsystems                     | 2        | 0.34%   |
| Zoran Co. Personal Media Division (Nogatech) | 1        | 0.17%   |
| www.hirestech.com 2010 REV 1.4               | 1        | 0.17%   |
| Sony                                         | 1        | 0.17%   |
| Silicon Integrated Systems [SiS]             | 1        | 0.17%   |
| Shenzhen Riitek Technology                   | 1        | 0.17%   |
| Schiit Audio                                 | 1        | 0.17%   |
| Samson Technologies                          | 1        | 0.17%   |
| ROCCAT                                       | 1        | 0.17%   |
| PS Audio                                     | 1        | 0.17%   |
| Plantronics                                  | 1        | 0.17%   |
| Nektar                                       | 1        | 0.17%   |
| Musical Fidelity                             | 1        | 0.17%   |
| Micronas                                     | 1        | 0.17%   |
| Micro Star International                     | 1        | 0.17%   |
| Mackie Designs                               | 1        | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 51       | 7.57%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 24       | 3.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 22       | 3.26%   |
| Nvidia GP104 High Definition Audio Controller                              | 21       | 3.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 21       | 3.12%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 21       | 3.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 20       | 2.97%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20       | 2.97%   |
| Intel 200 Series PCH HD Audio                                              | 18       | 2.67%   |
| Nvidia GP106 High Definition Audio Controller                              | 17       | 2.52%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16       | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 1.93%   |
| AMD Navi 10 HDMI Audio                                                     | 13       | 1.93%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 12       | 1.78%   |
| Nvidia GA104 High Definition Audio Controller                              | 11       | 1.63%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 10       | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 10       | 1.48%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 10       | 1.48%   |
| Nvidia GA102 High Definition Audio Controller                              | 9        | 1.34%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 9        | 1.34%   |
| AMD FCH Azalia Controller                                                  | 9        | 1.34%   |
| AMD Family 17h/19h HD Audio Controller                                     | 8        | 1.19%   |
| SteelSeries ApS SteelSeries Arctis 7                                       | 7        | 1.04%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 1.04%   |
| Nvidia GM204 High Definition Audio Controller                              | 7        | 1.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7        | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 7        | 1.04%   |
| Nvidia TU104 HD Audio Controller                                           | 6        | 0.89%   |
| Nvidia GK104 HDMI Audio Controller                                         | 6        | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 6        | 0.89%   |
| Kingston Technology HyperX 7.1 Audio                                       | 6        | 0.89%   |
| Blue Microphones Yeti Stereo Microphone                                    | 6        | 0.89%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5        | 0.74%   |
| Intel C600/X79 series chipset High Definition Audio Controller             | 5        | 0.74%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5        | 0.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 5        | 0.74%   |
| Nvidia High Definition Audio Controller                                    | 4        | 0.59%   |
| Nvidia GP102 HDMI Audio Controller                                         | 4        | 0.59%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.59%   |
| Nvidia GK110 High Definition Audio Controller                              | 4        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 42       | 24.14%  |
| Corsair             | 37       | 21.26%  |
| Crucial             | 24       | 13.79%  |
| Unknown             | 16       | 9.2%    |
| SK hynix            | 16       | 9.2%    |
| G.Skill             | 15       | 8.62%   |
| Samsung Electronics | 10       | 5.75%   |
| Micron Technology   | 5        | 2.87%   |
| Ramaxel Technology  | 3        | 1.72%   |
| Patriot             | 1        | 0.57%   |
| GeIL                | 1        | 0.57%   |
| Elpida              | 1        | 0.57%   |
| Apacer              | 1        | 0.57%   |
| A-DATA Technology   | 1        | 0.57%   |
| Unknown             | 1        | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s   | 6        | 3.26%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                 | 5        | 2.72%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s   | 4        | 2.17%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s | 4        | 2.17%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s   | 3        | 1.63%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s        | 3        | 1.63%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s      | 3        | 1.63%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1600MT/s    | 3        | 1.63%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s    | 3        | 1.63%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                     | 2        | 1.09%   |
| SK hynix RAM HMT41GU6BFR8A-PB 8GB DIMM DDR3 2000MT/s     | 2        | 1.09%   |
| Kingston RAM KHX3000C15D4/8GX 8192MB DIMM DDR4 3400MT/s  | 2        | 1.09%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s        | 2        | 1.09%   |
| Kingston RAM KHX2666C16/16G 16384MB DIMM DDR4 3200MT/s   | 2        | 1.09%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s      | 2        | 1.09%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s      | 2        | 1.09%   |
| Kingston RAM KHX1600C10D3/8GX 8GB DIMM DDR3 1600MT/s     | 2        | 1.09%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s    | 2        | 1.09%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s    | 2        | 1.09%   |
| G.Skill RAM F4-3600C16-16GTZN 16GB DIMM DDR4 3733MT/s    | 2        | 1.09%   |
| Crucial RAM CT102464BA1339.C16 8GB DIMM DDR3 1333MT/s    | 2        | 1.09%   |
| Crucial RAM BL16G36C16U4B.M16FE1 16GB DIMM DDR4 3600MT/s | 2        | 1.09%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s      | 2        | 1.09%   |
| Corsair RAM CMK8GX4M1A2400C14 8192MB DIMM DDR4 2800MT/s  | 2        | 1.09%   |
| Corsair RAM CMK32GX4M2A2666C16 16GB DIMM DDR4 3100MT/s   | 2        | 1.09%   |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s             | 1        | 0.54%   |
| Unknown RAM Module 4GB DIMM DDR3 667MT/s                 | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s             | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                  | 1        | 0.54%   |
| Unknown RAM Module 4096MB DIMM                           | 1        | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 1        | 0.54%   |
| Unknown RAM Module 2GB DIMM DDR 1066MT/s                 | 1        | 0.54%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s            | 1        | 0.54%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s              | 1        | 0.54%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                 | 1        | 0.54%   |
| Unknown RAM Module 1024MB DIMM 1600MT/s                  | 1        | 0.54%   |
| SK hynix RAM Module 8GB DIMM DDR3 1600MT/s               | 1        | 0.54%   |
| SK hynix RAM Module 4GB DIMM DDR3 1333MT/s               | 1        | 0.54%   |
| SK hynix RAM HYMP512U72CP8-Y5 1024MB DIMM DDR2 667MT/s   | 1        | 0.54%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR 667MT/s       | 1        | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 84       | 54.9%   |
| DDR3    | 50       | 32.68%  |
| DDR2    | 10       | 6.54%   |
| Unknown | 5        | 3.27%   |
| SDRAM   | 3        | 1.96%   |
| DDR     | 1        | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 145      | 95.39%  |
| SODIMM | 7        | 4.61%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 65       | 40.12%  |
| 16384 | 41       | 25.31%  |
| 4096  | 33       | 20.37%  |
| 2048  | 12       | 7.41%   |
| 32768 | 6        | 3.7%    |
| 1024  | 4        | 2.47%   |
| 128   | 1        | 0.62%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 30       | 17.75%  |
| 3600    | 18       | 10.65%  |
| 2400    | 15       | 8.88%   |
| 1333    | 15       | 8.88%   |
| 3200    | 14       | 8.28%   |
| 3400    | 11       | 6.51%   |
| 667     | 10       | 5.92%   |
| 2133    | 9        | 5.33%   |
| 3466    | 5        | 2.96%   |
| 3000    | 4        | 2.37%   |
| 3866    | 3        | 1.78%   |
| 3733    | 3        | 1.78%   |
| 2800    | 3        | 1.78%   |
| 1867    | 3        | 1.78%   |
| 1800    | 3        | 1.78%   |
| 3333    | 2        | 1.18%   |
| 3151    | 2        | 1.18%   |
| 3100    | 2        | 1.18%   |
| 2933    | 2        | 1.18%   |
| 2000    | 2        | 1.18%   |
| 1066    | 2        | 1.18%   |
| 4800    | 1        | 0.59%   |
| 4000    | 1        | 0.59%   |
| 3533    | 1        | 0.59%   |
| 2733    | 1        | 0.59%   |
| 2667    | 1        | 0.59%   |
| 2666    | 1        | 0.59%   |
| 2187    | 1        | 0.59%   |
| 2048    | 1        | 0.59%   |
| 800     | 1        | 0.59%   |
| 100     | 1        | 0.59%   |
| Unknown | 1        | 0.59%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 4        | 40%     |
| Brother Industries  | 3        | 30%     |
| Samsung Electronics | 1        | 10%     |
| Pantum              | 1        | 10%     |
| Canon               | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Desktops | Percent |
|--------------------------------------|----------|---------|
| Samsung M2020 Series                 | 1        | 10%     |
| Pantum P2500W series                 | 1        | 10%     |
| HP LaserJet Professional P 1102w     | 1        | 10%     |
| HP ENVY Photo 6200 series            | 1        | 10%     |
| HP DeskJet F300 series               | 1        | 10%     |
| HP Deskjet 2540 series               | 1        | 10%     |
| Canon PIXMA MX530 Series             | 1        | 10%     |
| Brother QL-800 P-touch Label Printer | 1        | 10%     |
| Brother QL-550 printer               | 1        | 10%     |
| Brother DCP-8085DN                   | 1        | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Canon  | 2        | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Canon CanoScan LiDE 200 | 1        | 50%     |
| Canon CanoScan LiDE 110 | 1        | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 37       | 52.86%  |
| Microsoft                     | 5        | 7.14%   |
| Microdia                      | 5        | 7.14%   |
| Creative Technology           | 5        | 7.14%   |
| Sunplus Innovation Technology | 2        | 2.86%   |
| MacroSilicon                  | 2        | 2.86%   |
| Cubeternet                    | 2        | 2.86%   |
| Chicony Electronics           | 2        | 2.86%   |
| Apple                         | 2        | 2.86%   |
| Z-Star Microelectronics       | 1        | 1.43%   |
| Technologies                  | 1        | 1.43%   |
| Samsung Electronics           | 1        | 1.43%   |
| Razer USA                     | 1        | 1.43%   |
| Novatek Microelectronics      | 1        | 1.43%   |
| Elgato Systems                | 1        | 1.43%   |
| ARC International             | 1        | 1.43%   |
| Alcor Micro                   | 1        | 1.43%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Logitech HD Pro Webcam C920                                         | 6        | 8.45%   |
| Logitech C922 Pro Stream Webcam                                     | 6        | 8.45%   |
| Logitech Webcam C270                                                | 5        | 7.04%   |
| Creative Live! Cam Chat HD [VF0700]                                 | 4        | 5.63%   |
| Microsoft LifeCam Cinema                                            | 3        | 4.23%   |
| Logitech Webcam C930e                                               | 3        | 4.23%   |
| Microdia Camera                                                     | 2        | 2.82%   |
| MacroSilicon USB Video                                              | 2        | 2.82%   |
| Logitech Webcam C925e                                               | 2        | 2.82%   |
| Logitech Webcam C170                                                | 2        | 2.82%   |
| Logitech QuickCam Pro 9000                                          | 2        | 2.82%   |
| Logitech Logi 4K Stream Edition                                     | 2        | 2.82%   |
| Logitech HD Webcam C525                                             | 2        | 2.82%   |
| Logitech B525 HD Webcam                                             | 2        | 2.82%   |
| Apple iPhone 5/5C/5S/6/SE                                           | 2        | 2.82%   |
| Z-Star Lenovo ThinkCentre Web Camera                                | 1        | 1.41%   |
| Technologies ZED 2i                                                 | 1        | 1.41%   |
| Sunplus Sandberg USB Webcam Pro                                     | 1        | 1.41%   |
| Sunplus HD 720P webcam                                              | 1        | 1.41%   |
| Samsung Galaxy series, misc. (MTP mode)                             | 1        | 1.41%   |
| Razer USA Gaming Webcam [Kiyo]                                      | 1        | 1.41%   |
| Novatek HP High Definition 2MP Webcam                               | 1        | 1.41%   |
| Microsoft LifeCam Studio                                            | 1        | 1.41%   |
| Microsoft LifeCam HD-3000                                           | 1        | 1.41%   |
| Microdia USB Live camera                                            | 1        | 1.41%   |
| Microdia PC Microscope camera                                       | 1        | 1.41%   |
| Microdia AUKEY PCâW1                                           | 1        | 1.41%   |
| Logitech Webcam C310                                                | 1        | 1.41%   |
| Logitech StreamCam                                                  | 1        | 1.41%   |
| Logitech QuickCam E 3500                                            | 1        | 1.41%   |
| Logitech HD Webcam C615                                             | 1        | 1.41%   |
| Logitech C920 PRO HD Webcam                                         | 1        | 1.41%   |
| Logitech BRIO Ultra HD Webcam                                       | 1        | 1.41%   |
| Elgato Systems Elgato Facecam                                       | 1        | 1.41%   |
| Cubeternet Live Streaming USB Device                                | 1        | 1.41%   |
| Cubeternet EtronTech CMOS based eSP570 WebCam [Onyx Titanium TC101] | 1        | 1.41%   |
| Creative Live! Cam Optia                                            | 1        | 1.41%   |
| Chicony USB2.0 FHD UVC WebCam                                       | 1        | 1.41%   |
| Chicony ASUS USB2.0 Webcam                                          | 1        | 1.41%   |
| ARC International Camera                                            | 1        | 1.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

Zero info for selected period =(

Fingerprint Model
-----------------

Fingerprint sensor models

Zero info for selected period =(

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor     | Desktops | Percent |
|------------|----------|---------|
| OmniKey    | 2        | 66.67%  |
| Yubico.com | 1        | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                       | Desktops | Percent |
|-----------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121 | 2        | 66.67%  |
| Yubico.com Yubikey 4/5 CCID | 1        | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 229      | 78.97%  |
| 1     | 49       | 16.9%   |
| 2     | 9        | 3.1%    |
| 3     | 3        | 1.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Net/wireless             | 25       | 35.21%  |
| Graphics card            | 15       | 21.13%  |
| Unassigned class         | 14       | 19.72%  |
| Sound                    | 4        | 5.63%   |
| Wireless                 | 3        | 4.23%   |
| Net/ethernet             | 2        | 2.82%   |
| Chipcard                 | 2        | 2.82%   |
| Bluetooth                | 2        | 2.82%   |
| Multimedia controller    | 1        | 1.41%   |
| Dvb card                 | 1        | 1.41%   |
| Communication controller | 1        | 1.41%   |
| Camera                   | 1        | 1.41%   |

