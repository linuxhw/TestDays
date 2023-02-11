Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

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

Total: 2747

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | Mac-F2268DC8                | All in one  | [b13dd2d455](https://linux-hardware.org/?probe=b13dd2d455) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [c4869ecf2c](https://linux-hardware.org/?probe=c4869ecf2c) | Feb 01, 2023 |
| Acer          | Predator PH517-61           | Notebook    | [b16ddc31d8](https://linux-hardware.org/?probe=b16ddc31d8) | Feb 01, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | Notebook    | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [228ab40738](https://linux-hardware.org/?probe=228ab40738) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [7636aeaacc](https://linux-hardware.org/?probe=7636aeaacc) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [84278c514e](https://linux-hardware.org/?probe=84278c514e) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [e91278bf3b](https://linux-hardware.org/?probe=e91278bf3b) | Jan 31, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [230b38f8e6](https://linux-hardware.org/?probe=230b38f8e6) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [82d317899e](https://linux-hardware.org/?probe=82d317899e) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [33ae030343](https://linux-hardware.org/?probe=33ae030343) | Jan 31, 2023 |
| Intel         | NUC6i5SYB H81131-504        | Mini pc     | [d079e3930d](https://linux-hardware.org/?probe=d079e3930d) | Jan 31, 2023 |
| MSI           | PRO Z690-P DDR4             | Desktop     | [a434328de5](https://linux-hardware.org/?probe=a434328de5) | Jan 30, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [f012d6d71c](https://linux-hardware.org/?probe=f012d6d71c) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [1228d6d0f7](https://linux-hardware.org/?probe=1228d6d0f7) | Jan 30, 2023 |
| Dell          | G15 5511                    | Notebook    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [a96d93846a](https://linux-hardware.org/?probe=a96d93846a) | Jan 30, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | Notebook    | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3d555e69f7](https://linux-hardware.org/?probe=3d555e69f7) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0966ae419c](https://linux-hardware.org/?probe=0966ae419c) | Jan 30, 2023 |
| Intel         | H61                         | Desktop     | [87a72c61f2](https://linux-hardware.org/?probe=87a72c61f2) | Jan 29, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [b07e189d3c](https://linux-hardware.org/?probe=b07e189d3c) | Jan 29, 2023 |
| Dell          | G15 5515                    | Notebook    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [6b71ec1a01](https://linux-hardware.org/?probe=6b71ec1a01) | Jan 28, 2023 |
| Gigabyte      | H77M-D3H                    | Desktop     | [a9367f87d4](https://linux-hardware.org/?probe=a9367f87d4) | Jan 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [697b0d8654](https://linux-hardware.org/?probe=697b0d8654) | Jan 28, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [c74b6b90f0](https://linux-hardware.org/?probe=c74b6b90f0) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| ASUSTek       | ET2321I                     | Notebook    | [dbb162975e](https://linux-hardware.org/?probe=dbb162975e) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [549b690251](https://linux-hardware.org/?probe=549b690251) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | Notebook    | [cbbd1d3e3e](https://linux-hardware.org/?probe=cbbd1d3e3e) | Jan 28, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [684b829dbb](https://linux-hardware.org/?probe=684b829dbb) | Jan 28, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [995da6b474](https://linux-hardware.org/?probe=995da6b474) | Jan 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ce2955973a](https://linux-hardware.org/?probe=ce2955973a) | Jan 27, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [55d50f6d18](https://linux-hardware.org/?probe=55d50f6d18) | Jan 27, 2023 |
| System76      | Lemur Pro                   | Notebook    | [40c5731c48](https://linux-hardware.org/?probe=40c5731c48) | Jan 27, 2023 |
| HP            | 1495                        | Desktop     | [8c1f7b5fbd](https://linux-hardware.org/?probe=8c1f7b5fbd) | Jan 27, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [c2a36422b4](https://linux-hardware.org/?probe=c2a36422b4) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [df315d8050](https://linux-hardware.org/?probe=df315d8050) | Jan 27, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [14a0252d88](https://linux-hardware.org/?probe=14a0252d88) | Jan 27, 2023 |
| Clevo         | W150HNM/W170HN              | Notebook    | [63709a14ca](https://linux-hardware.org/?probe=63709a14ca) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [0b70a364b7](https://linux-hardware.org/?probe=0b70a364b7) | Jan 27, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [a42ba7ef9e](https://linux-hardware.org/?probe=a42ba7ef9e) | Jan 26, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [1f8bd6b38e](https://linux-hardware.org/?probe=1f8bd6b38e) | Jan 26, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [df04ffbd50](https://linux-hardware.org/?probe=df04ffbd50) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [b2ffc58bb1](https://linux-hardware.org/?probe=b2ffc58bb1) | Jan 26, 2023 |
| Dell          | G3 3590                     | Notebook    | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| System76      | Lemur Pro                   | Notebook    | [097cd4c9f8](https://linux-hardware.org/?probe=097cd4c9f8) | Jan 26, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2fe7cc7865](https://linux-hardware.org/?probe=2fe7cc7865) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [e32b0f2c79](https://linux-hardware.org/?probe=e32b0f2c79) | Jan 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c7c957ccb3](https://linux-hardware.org/?probe=c7c957ccb3) | Jan 25, 2023 |
| HP            | ProBook 6550b               | Notebook    | [c7983e417c](https://linux-hardware.org/?probe=c7983e417c) | Jan 25, 2023 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | Notebook    | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| Dell          | Inspiron 13-7353            | Notebook    | [5ebcba8c52](https://linux-hardware.org/?probe=5ebcba8c52) | Jan 25, 2023 |
| Dell          | Latitude E7240              | Notebook    | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [935a295b28](https://linux-hardware.org/?probe=935a295b28) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| MeLE          | Rev GMLR1                   | Mini pc     | [1f294d6a67](https://linux-hardware.org/?probe=1f294d6a67) | Jan 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [be7339e967](https://linux-hardware.org/?probe=be7339e967) | Jan 24, 2023 |
| Acer          | Aspire M3970                | Desktop     | [c822a510e5](https://linux-hardware.org/?probe=c822a510e5) | Jan 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [1c05334105](https://linux-hardware.org/?probe=1c05334105) | Jan 24, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | Notebook    | [73a0023203](https://linux-hardware.org/?probe=73a0023203) | Jan 24, 2023 |
| Google        | Link                        | Notebook    | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [f6e09cc9fb](https://linux-hardware.org/?probe=f6e09cc9fb) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [306e6ae925](https://linux-hardware.org/?probe=306e6ae925) | Jan 23, 2023 |
| ASUSTek       | Rampage II GENE             | Desktop     | [112b5304d9](https://linux-hardware.org/?probe=112b5304d9) | Jan 23, 2023 |
| MACHINIST     | X79 Z9-D7 V2.0              | Desktop     | [9d5d06d342](https://linux-hardware.org/?probe=9d5d06d342) | Jan 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bfb889f5d5](https://linux-hardware.org/?probe=bfb889f5d5) | Jan 23, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6597dd71bc](https://linux-hardware.org/?probe=6597dd71bc) | Jan 23, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [8f19cbfb31](https://linux-hardware.org/?probe=8f19cbfb31) | Jan 22, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Purism        | Librem 15 v3                | Notebook    | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| MSI           | H81M-E34                    | Desktop     | [c11041ba13](https://linux-hardware.org/?probe=c11041ba13) | Jan 22, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [eec3fddef5](https://linux-hardware.org/?probe=eec3fddef5) | Jan 22, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [758ea69493](https://linux-hardware.org/?probe=758ea69493) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4f65820da4](https://linux-hardware.org/?probe=4f65820da4) | Jan 22, 2023 |
| Dell          | Latitude E5470              | Notebook    | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [d1b63bbd2d](https://linux-hardware.org/?probe=d1b63bbd2d) | Jan 22, 2023 |
| HP            | Notebook                    | Notebook    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [01e83b7640](https://linux-hardware.org/?probe=01e83b7640) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [ebab459512](https://linux-hardware.org/?probe=ebab459512) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [70b4ca8de7](https://linux-hardware.org/?probe=70b4ca8de7) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [1a27b660c2](https://linux-hardware.org/?probe=1a27b660c2) | Jan 21, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [6dd531590e](https://linux-hardware.org/?probe=6dd531590e) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Dell          | Latitude 5300               | Notebook    | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [bd601f83d3](https://linux-hardware.org/?probe=bd601f83d3) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [d203633f83](https://linux-hardware.org/?probe=d203633f83) | Jan 21, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [ce0ba337df](https://linux-hardware.org/?probe=ce0ba337df) | Jan 21, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [e47d5b2419](https://linux-hardware.org/?probe=e47d5b2419) | Jan 21, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | Notebook    | [1da6722b35](https://linux-hardware.org/?probe=1da6722b35) | Jan 21, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [011553878f](https://linux-hardware.org/?probe=011553878f) | Jan 21, 2023 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [b7b8f92df1](https://linux-hardware.org/?probe=b7b8f92df1) | Jan 21, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | Notebook    | [e1003a85c9](https://linux-hardware.org/?probe=e1003a85c9) | Jan 20, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [2ad3ad8258](https://linux-hardware.org/?probe=2ad3ad8258) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | Notebook    | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [a10fc5f5a9](https://linux-hardware.org/?probe=a10fc5f5a9) | Jan 20, 2023 |
| Dell          | Latitude E7240              | Notebook    | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [266b8bc492](https://linux-hardware.org/?probe=266b8bc492) | Jan 20, 2023 |
| Alienware     | 0N43JM A00                  | Desktop     | [06a6ec74c0](https://linux-hardware.org/?probe=06a6ec74c0) | Jan 20, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0bf7ea6726](https://linux-hardware.org/?probe=0bf7ea6726) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| Lenovo        | 3767 WIN SDK0T76461 3422... | All in one  | [f9f38488a8](https://linux-hardware.org/?probe=f9f38488a8) | Jan 19, 2023 |
| Dell          | Latitude E7240              | Notebook    | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| ASRock        | X99 Professional Gaming ... | Desktop     | [0fbcb3df67](https://linux-hardware.org/?probe=0fbcb3df67) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [cbad1c4df4](https://linux-hardware.org/?probe=cbad1c4df4) | Jan 19, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [b318baed4f](https://linux-hardware.org/?probe=b318baed4f) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [3ff2eaf5ed](https://linux-hardware.org/?probe=3ff2eaf5ed) | Jan 19, 2023 |
| Dell          | Inspiron 5491 2n1           | Convertible | [061608feaa](https://linux-hardware.org/?probe=061608feaa) | Jan 19, 2023 |
| Razer         | Blade                       | Notebook    | [b3f154ac11](https://linux-hardware.org/?probe=b3f154ac11) | Jan 19, 2023 |
| Dell          | G5 5590                     | Notebook    | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| ASUSTek       | P6T SE                      | Desktop     | [d13ca33fcf](https://linux-hardware.org/?probe=d13ca33fcf) | Jan 18, 2023 |
| Dell          | Latitude E6540              | Notebook    | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | Notebook    | [933f67b6b5](https://linux-hardware.org/?probe=933f67b6b5) | Jan 18, 2023 |
| Dell          | Precision 7670              | Notebook    | [5c70243651](https://linux-hardware.org/?probe=5c70243651) | Jan 18, 2023 |
| Intel         | NUC12EDBi9 M27907-302       | Mini pc     | [b43c8a95b7](https://linux-hardware.org/?probe=b43c8a95b7) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | Notebook    | [48a56bd8c2](https://linux-hardware.org/?probe=48a56bd8c2) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [ac28c1fba4](https://linux-hardware.org/?probe=ac28c1fba4) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [45e2d0fb2d](https://linux-hardware.org/?probe=45e2d0fb2d) | Jan 18, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [b5b4cde08e](https://linux-hardware.org/?probe=b5b4cde08e) | Jan 18, 2023 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [3ee772766c](https://linux-hardware.org/?probe=3ee772766c) | Jan 18, 2023 |
| Dell          | Latitude E5440              | Notebook    | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [ebc45fdfd5](https://linux-hardware.org/?probe=ebc45fdfd5) | Jan 18, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [0eae2f92fa](https://linux-hardware.org/?probe=0eae2f92fa) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [f908807ed9](https://linux-hardware.org/?probe=f908807ed9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [8bf0f8c8fe](https://linux-hardware.org/?probe=8bf0f8c8fe) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [24d62d6974](https://linux-hardware.org/?probe=24d62d6974) | Jan 17, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [564482477e](https://linux-hardware.org/?probe=564482477e) | Jan 17, 2023 |
| Framework     | Laptop                      | Notebook    | [e94774a411](https://linux-hardware.org/?probe=e94774a411) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6e8f360d6e](https://linux-hardware.org/?probe=6e8f360d6e) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [a71c911bcf](https://linux-hardware.org/?probe=a71c911bcf) | Jan 17, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [22fca13d2b](https://linux-hardware.org/?probe=22fca13d2b) | Jan 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [2ba8d32a71](https://linux-hardware.org/?probe=2ba8d32a71) | Jan 17, 2023 |
| Gateway       | WG43M                       | Desktop     | [af3a009366](https://linux-hardware.org/?probe=af3a009366) | Jan 17, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [48cc2e0e69](https://linux-hardware.org/?probe=48cc2e0e69) | Jan 17, 2023 |
| Gateway       | WG43M                       | Desktop     | [b0aa3af22f](https://linux-hardware.org/?probe=b0aa3af22f) | Jan 17, 2023 |
| ASRock        | H87 Performance             | Desktop     | [9e2cd66ef5](https://linux-hardware.org/?probe=9e2cd66ef5) | Jan 16, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [2e65fc8357](https://linux-hardware.org/?probe=2e65fc8357) | Jan 16, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [ba736834cd](https://linux-hardware.org/?probe=ba736834cd) | Jan 16, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [ef934af180](https://linux-hardware.org/?probe=ef934af180) | Jan 16, 2023 |
| Acer          | Aspire 5625G                | Notebook    | [244d8473fc](https://linux-hardware.org/?probe=244d8473fc) | Jan 16, 2023 |
| Dell          | Latitude E7240              | Notebook    | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [7eabefdc79](https://linux-hardware.org/?probe=7eabefdc79) | Jan 16, 2023 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [8c43e56714](https://linux-hardware.org/?probe=8c43e56714) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| System76      | Lemur Pro                   | Notebook    | [fde9d32359](https://linux-hardware.org/?probe=fde9d32359) | Jan 16, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [01f850d2fb](https://linux-hardware.org/?probe=01f850d2fb) | Jan 15, 2023 |
| Dell          | 0PXWHK A00                  | Desktop     | [82f04ecd77](https://linux-hardware.org/?probe=82f04ecd77) | Jan 15, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [64b089dfb7](https://linux-hardware.org/?probe=64b089dfb7) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| Dell          | 0PXWHK A00                  | Desktop     | [25db796fd6](https://linux-hardware.org/?probe=25db796fd6) | Jan 14, 2023 |
| MAXSUN        | MS-TZZ B460M                | Desktop     | [14758fc3e7](https://linux-hardware.org/?probe=14758fc3e7) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [d3896698c8](https://linux-hardware.org/?probe=d3896698c8) | Jan 14, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [ffb8653d34](https://linux-hardware.org/?probe=ffb8653d34) | Jan 14, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [a92296f2e7](https://linux-hardware.org/?probe=a92296f2e7) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Precision 3571              | Notebook    | [c71e32c6ea](https://linux-hardware.org/?probe=c71e32c6ea) | Jan 14, 2023 |
| Acer          | Predator PT315-52           | Notebook    | [149941b52c](https://linux-hardware.org/?probe=149941b52c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| Acer          | Aspire XC-603G              | Desktop     | [21e24944ad](https://linux-hardware.org/?probe=21e24944ad) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| System76      | Oryx Pro                    | Notebook    | [da1374fa1c](https://linux-hardware.org/?probe=da1374fa1c) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [4ce5e1fd02](https://linux-hardware.org/?probe=4ce5e1fd02) | Jan 14, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [4c3d300ccc](https://linux-hardware.org/?probe=4c3d300ccc) | Jan 14, 2023 |
| ASUSTek       | M4A78                       | Desktop     | [09560460b9](https://linux-hardware.org/?probe=09560460b9) | Jan 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| ASUSTek       | P9X79-E WS                  | Desktop     | [e868d6909e](https://linux-hardware.org/?probe=e868d6909e) | Jan 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [2860788f11](https://linux-hardware.org/?probe=2860788f11) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [c01da2fcf9](https://linux-hardware.org/?probe=c01da2fcf9) | Jan 14, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [d4a8ff871f](https://linux-hardware.org/?probe=d4a8ff871f) | Jan 14, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [10a9c33aed](https://linux-hardware.org/?probe=10a9c33aed) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Dell          | Latitude 5300               | Notebook    | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [1921b19009](https://linux-hardware.org/?probe=1921b19009) | Jan 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [1ad37ae4cc](https://linux-hardware.org/?probe=1ad37ae4cc) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | Notebook    | [96a079dbf8](https://linux-hardware.org/?probe=96a079dbf8) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | Notebook    | [53b39e47e9](https://linux-hardware.org/?probe=53b39e47e9) | Jan 13, 2023 |
| HP            | 8299                        | Desktop     | [e4e0920f71](https://linux-hardware.org/?probe=e4e0920f71) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | Notebook    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [f7304c0af2](https://linux-hardware.org/?probe=f7304c0af2) | Jan 12, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [22f9a03d68](https://linux-hardware.org/?probe=22f9a03d68) | Jan 12, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Dell          | Latitude E7240              | Notebook    | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| ASUSTek       | H61M-E                      | Desktop     | [38691cf2cc](https://linux-hardware.org/?probe=38691cf2cc) | Jan 11, 2023 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Acer          | TravelMate P245-M           | Notebook    | [1722e41c8d](https://linux-hardware.org/?probe=1722e41c8d) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| Lenovo        | ThinkCentre M71e 3157W8B    | Desktop     | [70078ceabd](https://linux-hardware.org/?probe=70078ceabd) | Jan 11, 2023 |
| Dell          | Inspiron 14 7420 2-in-1     | Convertible | [aa36c50a9f](https://linux-hardware.org/?probe=aa36c50a9f) | Jan 11, 2023 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [ae12526ceb](https://linux-hardware.org/?probe=ae12526ceb) | Jan 11, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [6694d6e805](https://linux-hardware.org/?probe=6694d6e805) | Jan 11, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [8d12a9a7ea](https://linux-hardware.org/?probe=8d12a9a7ea) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [456445a93c](https://linux-hardware.org/?probe=456445a93c) | Jan 10, 2023 |
| Dell          | Latitude E7240              | Notebook    | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| ReachingTe... | DreamQuest Pro 2022         | Mini pc     | [06eee6367f](https://linux-hardware.org/?probe=06eee6367f) | Jan 10, 2023 |
| ASUSTek       | P9X79-E WS                  | Desktop     | [f3b4e5135f](https://linux-hardware.org/?probe=f3b4e5135f) | Jan 10, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [547fc87531](https://linux-hardware.org/?probe=547fc87531) | Jan 10, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [f03ae5d905](https://linux-hardware.org/?probe=f03ae5d905) | Jan 10, 2023 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [9645ad91cc](https://linux-hardware.org/?probe=9645ad91cc) | Jan 10, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [0eb6418a53](https://linux-hardware.org/?probe=0eb6418a53) | Jan 10, 2023 |
| HP            | 8433 11                     | Desktop     | [5e26cba33b](https://linux-hardware.org/?probe=5e26cba33b) | Jan 10, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E30013... | Tablet      | [4bcaff2f2b](https://linux-hardware.org/?probe=4bcaff2f2b) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [a9ee630b0b](https://linux-hardware.org/?probe=a9ee630b0b) | Jan 09, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [b39213e4d0](https://linux-hardware.org/?probe=b39213e4d0) | Jan 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [aef797585c](https://linux-hardware.org/?probe=aef797585c) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [3982bc570e](https://linux-hardware.org/?probe=3982bc570e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [1829eed17a](https://linux-hardware.org/?probe=1829eed17a) | Jan 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [e64cca399f](https://linux-hardware.org/?probe=e64cca399f) | Jan 09, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [e7d2bcfcfb](https://linux-hardware.org/?probe=e7d2bcfcfb) | Jan 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| ASRock        | X370 Gaming K4              | Desktop     | [0ed2f96ba8](https://linux-hardware.org/?probe=0ed2f96ba8) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [36ed66f057](https://linux-hardware.org/?probe=36ed66f057) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [1b055dc79d](https://linux-hardware.org/?probe=1b055dc79d) | Jan 08, 2023 |
| Wortmann      | NA92                        | All in one  | [7e4e12aab4](https://linux-hardware.org/?probe=7e4e12aab4) | Jan 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [22b35f0197](https://linux-hardware.org/?probe=22b35f0197) | Jan 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [07cc23f1cd](https://linux-hardware.org/?probe=07cc23f1cd) | Jan 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d784655474](https://linux-hardware.org/?probe=d784655474) | Jan 08, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [0b85968e35](https://linux-hardware.org/?probe=0b85968e35) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [15f31fc9a5](https://linux-hardware.org/?probe=15f31fc9a5) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| HP            | ENVY dv6                    | Notebook    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [f191d63ace](https://linux-hardware.org/?probe=f191d63ace) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [4673ec60ea](https://linux-hardware.org/?probe=4673ec60ea) | Jan 07, 2023 |
| HP            | 2B4B                        | Desktop     | [57273c7b72](https://linux-hardware.org/?probe=57273c7b72) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| Dell          | 04GJJT A00                  | Desktop     | [85142569a6](https://linux-hardware.org/?probe=85142569a6) | Jan 07, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [b598f4182c](https://linux-hardware.org/?probe=b598f4182c) | Jan 07, 2023 |
| System76      | Bonobo WS                   | Notebook    | [afb9abd3c6](https://linux-hardware.org/?probe=afb9abd3c6) | Jan 07, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [ab9f1d1812](https://linux-hardware.org/?probe=ab9f1d1812) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [bf425a41f8](https://linux-hardware.org/?probe=bf425a41f8) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [89eccb038f](https://linux-hardware.org/?probe=89eccb038f) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Dell          | Latitude 7520               | Notebook    | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| Dell          | Precision M4700             | Notebook    | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f2024a8808](https://linux-hardware.org/?probe=f2024a8808) | Jan 06, 2023 |
| Acer          | Aspire M3970                | Desktop     | [2ef35b6d4b](https://linux-hardware.org/?probe=2ef35b6d4b) | Jan 05, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [0abf746107](https://linux-hardware.org/?probe=0abf746107) | Jan 05, 2023 |
| Dell          | Latitude E7240              | Notebook    | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [1396e4d561](https://linux-hardware.org/?probe=1396e4d561) | Jan 05, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| Intel         | HM570                       | Desktop     | [8728d2372a](https://linux-hardware.org/?probe=8728d2372a) | Jan 05, 2023 |
| AZW           | GTR V02                     | Desktop     | [2cf7a814cb](https://linux-hardware.org/?probe=2cf7a814cb) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [4f54cd1f61](https://linux-hardware.org/?probe=4f54cd1f61) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [0393900e99](https://linux-hardware.org/?probe=0393900e99) | Jan 05, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [04ca884448](https://linux-hardware.org/?probe=04ca884448) | Jan 05, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [98fafd877d](https://linux-hardware.org/?probe=98fafd877d) | Jan 04, 2023 |
| HP            | 3047h                       | Desktop     | [2c75b0b4ee](https://linux-hardware.org/?probe=2c75b0b4ee) | Jan 04, 2023 |
| System76      | Gazelle                     | Notebook    | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [81269f2363](https://linux-hardware.org/?probe=81269f2363) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Datto         | Unknown                     | Notebook    | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [afb6056f1d](https://linux-hardware.org/?probe=afb6056f1d) | Jan 04, 2023 |
| ASRock        | 760GM-HDV                   | Desktop     | [f994e91031](https://linux-hardware.org/?probe=f994e91031) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d50cf83414](https://linux-hardware.org/?probe=d50cf83414) | Jan 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6da268e22f](https://linux-hardware.org/?probe=6da268e22f) | Jan 03, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [78367dd37f](https://linux-hardware.org/?probe=78367dd37f) | Jan 03, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bd01380cb3](https://linux-hardware.org/?probe=bd01380cb3) | Jan 03, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [741f0d79a1](https://linux-hardware.org/?probe=741f0d79a1) | Jan 03, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [f6d1d35842](https://linux-hardware.org/?probe=f6d1d35842) | Jan 02, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [71ebcdc5ff](https://linux-hardware.org/?probe=71ebcdc5ff) | Jan 02, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [e8ad216a59](https://linux-hardware.org/?probe=e8ad216a59) | Jan 02, 2023 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [097761efca](https://linux-hardware.org/?probe=097761efca) | Jan 02, 2023 |
| Panasonic     | FZ55-1                      | Notebook    | [b09d64c936](https://linux-hardware.org/?probe=b09d64c936) | Jan 02, 2023 |
| ASUSTek       | P6T                         | Desktop     | [e648b2523e](https://linux-hardware.org/?probe=e648b2523e) | Jan 02, 2023 |
| Acer          | Aspire XC-603G              | Desktop     | [b2e25a20de](https://linux-hardware.org/?probe=b2e25a20de) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | Notebook    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0e4b6aa6c2](https://linux-hardware.org/?probe=0e4b6aa6c2) | Jan 02, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [1490ccc480](https://linux-hardware.org/?probe=1490ccc480) | Jan 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e26cc7285f](https://linux-hardware.org/?probe=e26cc7285f) | Jan 02, 2023 |
| Win elemen... | M600                        | Desktop     | [5d4320db68](https://linux-hardware.org/?probe=5d4320db68) | Jan 02, 2023 |
| Dell          | Latitude E7240              | Notebook    | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [9be0f7265e](https://linux-hardware.org/?probe=9be0f7265e) | Jan 02, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [5e52308407](https://linux-hardware.org/?probe=5e52308407) | Jan 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [d841c27fe1](https://linux-hardware.org/?probe=d841c27fe1) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | Notebook    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| MSI           | PRO B550-VC                 | Desktop     | [f5574e6e00](https://linux-hardware.org/?probe=f5574e6e00) | Jan 01, 2023 |
| Dell          | Latitude E7270              | Notebook    | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Dell          | XPS 9320                    | Notebook    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [a53517f382](https://linux-hardware.org/?probe=a53517f382) | Jan 01, 2023 |
| Dell          | XPS 9320                    | Notebook    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [28f9b91b32](https://linux-hardware.org/?probe=28f9b91b32) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6b98637c82](https://linux-hardware.org/?probe=6b98637c82) | Jan 01, 2023 |
| Acer          | Aspire XC-603G              | Desktop     | [660548d31c](https://linux-hardware.org/?probe=660548d31c) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a51048ad0a](https://linux-hardware.org/?probe=a51048ad0a) | Jan 01, 2023 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [e5f5073bcd](https://linux-hardware.org/?probe=e5f5073bcd) | Dec 31, 2022 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [a470da90e8](https://linux-hardware.org/?probe=a470da90e8) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [5b204eade4](https://linux-hardware.org/?probe=5b204eade4) | Dec 31, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [ad32666c8c](https://linux-hardware.org/?probe=ad32666c8c) | Dec 31, 2022 |
| ASUSTek       | Z97-A                       | Desktop     | [6f61aac097](https://linux-hardware.org/?probe=6f61aac097) | Dec 31, 2022 |
| HP            | EliteBook 8740w (WH274UT... | Notebook    | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | Notebook    | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | G3 3500                     | Notebook    | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [17fc3a4abc](https://linux-hardware.org/?probe=17fc3a4abc) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [85bfa942e6](https://linux-hardware.org/?probe=85bfa942e6) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [4b3cfd1d9c](https://linux-hardware.org/?probe=4b3cfd1d9c) | Dec 30, 2022 |
| Dell          | G5 5590                     | Notebook    | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [17f72460f6](https://linux-hardware.org/?probe=17f72460f6) | Dec 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | ThinkPad W510 4389W14       | Notebook    | [c83a9ac8a9](https://linux-hardware.org/?probe=c83a9ac8a9) | Dec 29, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [467a749806](https://linux-hardware.org/?probe=467a749806) | Dec 29, 2022 |
| Acer          | Aspire XC-603G              | Desktop     | [08dc8ac6b7](https://linux-hardware.org/?probe=08dc8ac6b7) | Dec 29, 2022 |
| System76      | Lemur Pro                   | Notebook    | [0a61e4fe8d](https://linux-hardware.org/?probe=0a61e4fe8d) | Dec 29, 2022 |
| HP            | ENVY dv7                    | Notebook    | [97e029af78](https://linux-hardware.org/?probe=97e029af78) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2bd4899c8a](https://linux-hardware.org/?probe=2bd4899c8a) | Dec 29, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [19c8814aba](https://linux-hardware.org/?probe=19c8814aba) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [919cfc2c9c](https://linux-hardware.org/?probe=919cfc2c9c) | Dec 29, 2022 |
| Dell          | 0NNGP2 A00                  | Desktop     | [12638171d9](https://linux-hardware.org/?probe=12638171d9) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| ASUSTek       | P453UA                      | Notebook    | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| Lenovo        | No DPK                      | Desktop     | [944f84567a](https://linux-hardware.org/?probe=944f84567a) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Alienware     | M11x R2                     | Notebook    | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| ASRock        | Z790M-ITX WiFi              | Desktop     | [c1c0ab5824](https://linux-hardware.org/?probe=c1c0ab5824) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Dell          | 00CV7F A00                  | Desktop     | [49a36278c4](https://linux-hardware.org/?probe=49a36278c4) | Dec 28, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [e4255e8ed7](https://linux-hardware.org/?probe=e4255e8ed7) | Dec 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [2522f716da](https://linux-hardware.org/?probe=2522f716da) | Dec 28, 2022 |
| HP            | 2B4B                        | Desktop     | [b07e2ecc23](https://linux-hardware.org/?probe=b07e2ecc23) | Dec 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [1522e4a536](https://linux-hardware.org/?probe=1522e4a536) | Dec 28, 2022 |
| Acer          | Aspire XC-603G              | Desktop     | [e8adbb63a4](https://linux-hardware.org/?probe=e8adbb63a4) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [20ca7dd779](https://linux-hardware.org/?probe=20ca7dd779) | Dec 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [dab993d989](https://linux-hardware.org/?probe=dab993d989) | Dec 27, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ee1658b320](https://linux-hardware.org/?probe=ee1658b320) | Dec 27, 2022 |
| HP            | 876C SMVB                   | Desktop     | [7926807626](https://linux-hardware.org/?probe=7926807626) | Dec 27, 2022 |
| Microsoft     | Surface Book                | Tablet      | [c374cd1b63](https://linux-hardware.org/?probe=c374cd1b63) | Dec 27, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [9c65749eb1](https://linux-hardware.org/?probe=9c65749eb1) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [470c8d54ba](https://linux-hardware.org/?probe=470c8d54ba) | Dec 27, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [c62b37d15c](https://linux-hardware.org/?probe=c62b37d15c) | Dec 27, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [89d9265559](https://linux-hardware.org/?probe=89d9265559) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [c0a659dbb1](https://linux-hardware.org/?probe=c0a659dbb1) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [4403153e04](https://linux-hardware.org/?probe=4403153e04) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [eb6c6ee49e](https://linux-hardware.org/?probe=eb6c6ee49e) | Dec 26, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [748284a21e](https://linux-hardware.org/?probe=748284a21e) | Dec 26, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [bddcc1503f](https://linux-hardware.org/?probe=bddcc1503f) | Dec 26, 2022 |
| Microsoft     | Surface Book                | Tablet      | [e9380c21e6](https://linux-hardware.org/?probe=e9380c21e6) | Dec 26, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | Notebook    | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| GPD           | G1621-02                    | Notebook    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [576fb3852f](https://linux-hardware.org/?probe=576fb3852f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [5ca8ddb512](https://linux-hardware.org/?probe=5ca8ddb512) | Dec 24, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [c49123106a](https://linux-hardware.org/?probe=c49123106a) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [de111c3be5](https://linux-hardware.org/?probe=de111c3be5) | Dec 24, 2022 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [857cb922f9](https://linux-hardware.org/?probe=857cb922f9) | Dec 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [8e6bdc1809](https://linux-hardware.org/?probe=8e6bdc1809) | Dec 24, 2022 |
| System76      | Pangolin                    | Notebook    | [2ee273cbcf](https://linux-hardware.org/?probe=2ee273cbcf) | Dec 24, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [b88840bfdf](https://linux-hardware.org/?probe=b88840bfdf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [53aa474cf5](https://linux-hardware.org/?probe=53aa474cf5) | Dec 23, 2022 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [44d3b06704](https://linux-hardware.org/?probe=44d3b06704) | Dec 23, 2022 |
| Timi          | TM1703                      | Notebook    | [5e25655f36](https://linux-hardware.org/?probe=5e25655f36) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | Notebook    | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Dell          | Latitude E7240              | Notebook    | [918223cece](https://linux-hardware.org/?probe=918223cece) | Dec 23, 2022 |
| Medion        | X6816                       | Notebook    | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | Notebook    | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Dell          | Latitude E7240              | Notebook    | [7bd2309063](https://linux-hardware.org/?probe=7bd2309063) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [d7b8ef01e2](https://linux-hardware.org/?probe=d7b8ef01e2) | Dec 23, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [313bf04928](https://linux-hardware.org/?probe=313bf04928) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [341becfd8a](https://linux-hardware.org/?probe=341becfd8a) | Dec 22, 2022 |
| Gigabyte      | MJPLNBB-00                  | Desktop     | [17c300ac96](https://linux-hardware.org/?probe=17c300ac96) | Dec 22, 2022 |
| Intel         | NUC10i3FNB M38070-306       | Mini pc     | [24e1fb5674](https://linux-hardware.org/?probe=24e1fb5674) | Dec 22, 2022 |
| Lenovo        | SDK0H15299 WIN              | All in one  | [837c6c4be9](https://linux-hardware.org/?probe=837c6c4be9) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | Notebook    | [e60df2d8ba](https://linux-hardware.org/?probe=e60df2d8ba) | Dec 22, 2022 |
| Acer          | Swift SF314-512             | Notebook    | [505ab3f60a](https://linux-hardware.org/?probe=505ab3f60a) | Dec 22, 2022 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [7402ac8671](https://linux-hardware.org/?probe=7402ac8671) | Dec 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d81efafde1](https://linux-hardware.org/?probe=d81efafde1) | Dec 22, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [1ef05442e9](https://linux-hardware.org/?probe=1ef05442e9) | Dec 22, 2022 |
| System76      | Lemur Pro                   | Notebook    | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | Notebook    | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Dell          | Precision 3520              | Notebook    | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| MSI           | B85M-E45                    | Desktop     | [b60edb092f](https://linux-hardware.org/?probe=b60edb092f) | Dec 21, 2022 |
| ASUSTek       | Strix 15 GL503GE            | Notebook    | [0377cc3170](https://linux-hardware.org/?probe=0377cc3170) | Dec 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [545294a23a](https://linux-hardware.org/?probe=545294a23a) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7d5914dcb2](https://linux-hardware.org/?probe=7d5914dcb2) | Dec 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [07dc9b96c1](https://linux-hardware.org/?probe=07dc9b96c1) | Dec 21, 2022 |
| Dell          | 02GDWG A00                  | Desktop     | [d20f5b0751](https://linux-hardware.org/?probe=d20f5b0751) | Dec 21, 2022 |
| Dell          | Latitude E7240              | Notebook    | [a368a7be00](https://linux-hardware.org/?probe=a368a7be00) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | Notebook    | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| Intel         | X99 V1.x                    | Desktop     | [5e961d12dc](https://linux-hardware.org/?probe=5e961d12dc) | Dec 21, 2022 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [5ab7ccb4cc](https://linux-hardware.org/?probe=5ab7ccb4cc) | Dec 20, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [d5a877b2c6](https://linux-hardware.org/?probe=d5a877b2c6) | Dec 20, 2022 |
| Supermicro    | X9DR3-F                     | Desktop     | [0a1557ab4a](https://linux-hardware.org/?probe=0a1557ab4a) | Dec 20, 2022 |
| HP            | 18E7                        | Desktop     | [c3b91e80df](https://linux-hardware.org/?probe=c3b91e80df) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [03dfcb8079](https://linux-hardware.org/?probe=03dfcb8079) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1f6885ef2f](https://linux-hardware.org/?probe=1f6885ef2f) | Dec 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c7b01f9875](https://linux-hardware.org/?probe=c7b01f9875) | Dec 19, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c168fe495f](https://linux-hardware.org/?probe=c168fe495f) | Dec 19, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [418178c3ca](https://linux-hardware.org/?probe=418178c3ca) | Dec 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | Notebook    | [76771fa0aa](https://linux-hardware.org/?probe=76771fa0aa) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| System76      | Gazelle                     | Notebook    | [da46fb926a](https://linux-hardware.org/?probe=da46fb926a) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d179359230](https://linux-hardware.org/?probe=d179359230) | Dec 18, 2022 |
| HP            | 8433 11                     | Desktop     | [4368b19d60](https://linux-hardware.org/?probe=4368b19d60) | Dec 18, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [e680612eb4](https://linux-hardware.org/?probe=e680612eb4) | Dec 18, 2022 |
| Lenovo        | ThinkPad Edge E430 62718... | Notebook    | [92fede3d5a](https://linux-hardware.org/?probe=92fede3d5a) | Dec 18, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [163b883ce2](https://linux-hardware.org/?probe=163b883ce2) | Dec 17, 2022 |
| Samsung       | 730QED                      | Convertible | [8ac065bd83](https://linux-hardware.org/?probe=8ac065bd83) | Dec 17, 2022 |
| Avell High... | B.ON                        | Notebook    | [9661ece374](https://linux-hardware.org/?probe=9661ece374) | Dec 17, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [1641d91910](https://linux-hardware.org/?probe=1641d91910) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2a0f5be3bf](https://linux-hardware.org/?probe=2a0f5be3bf) | Dec 17, 2022 |
| Dell          | 02GDWG A00                  | Desktop     | [d7e869aded](https://linux-hardware.org/?probe=d7e869aded) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [988a2e80c0](https://linux-hardware.org/?probe=988a2e80c0) | Dec 17, 2022 |
| Dell          | 02GDWG A00                  | Desktop     | [f12e6b75b5](https://linux-hardware.org/?probe=f12e6b75b5) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [b31e9dfa64](https://linux-hardware.org/?probe=b31e9dfa64) | Dec 16, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [893af38c43](https://linux-hardware.org/?probe=893af38c43) | Dec 16, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [90912f0bba](https://linux-hardware.org/?probe=90912f0bba) | Dec 16, 2022 |
| HP            | Pavilion x360 2-in-1 Lap... | Convertible | [00437ce174](https://linux-hardware.org/?probe=00437ce174) | Dec 16, 2022 |
| Dell          | Inspiron 5458               | Notebook    | [8ed4687f2f](https://linux-hardware.org/?probe=8ed4687f2f) | Dec 16, 2022 |
| System76      | Gazelle                     | Notebook    | [b5ef8cec53](https://linux-hardware.org/?probe=b5ef8cec53) | Dec 16, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [575a61802b](https://linux-hardware.org/?probe=575a61802b) | Dec 16, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [9cff930a2e](https://linux-hardware.org/?probe=9cff930a2e) | Dec 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [0b1367de2f](https://linux-hardware.org/?probe=0b1367de2f) | Dec 16, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [3b744c3d0c](https://linux-hardware.org/?probe=3b744c3d0c) | Dec 16, 2022 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [3986f30292](https://linux-hardware.org/?probe=3986f30292) | Dec 16, 2022 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [60848aa48e](https://linux-hardware.org/?probe=60848aa48e) | Dec 16, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [af4e397bbe](https://linux-hardware.org/?probe=af4e397bbe) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [544e464dab](https://linux-hardware.org/?probe=544e464dab) | Dec 15, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [d2065497b9](https://linux-hardware.org/?probe=d2065497b9) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [1d1a225cde](https://linux-hardware.org/?probe=1d1a225cde) | Dec 15, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [e6f5c32627](https://linux-hardware.org/?probe=e6f5c32627) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | Notebook    | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Fujitsu       | FMVNS6C3                    | Notebook    | [d7a6961431](https://linux-hardware.org/?probe=d7a6961431) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [35ef32b165](https://linux-hardware.org/?probe=35ef32b165) | Dec 14, 2022 |
| Supermicro    | X8DT3                       | Server      | [c2bd925732](https://linux-hardware.org/?probe=c2bd925732) | Dec 14, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [a22dd35e04](https://linux-hardware.org/?probe=a22dd35e04) | Dec 14, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [b4d843d4c2](https://linux-hardware.org/?probe=b4d843d4c2) | Dec 14, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [d0c2bf600a](https://linux-hardware.org/?probe=d0c2bf600a) | Dec 14, 2022 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [d1eaff3d4b](https://linux-hardware.org/?probe=d1eaff3d4b) | Dec 14, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [08e4e03d36](https://linux-hardware.org/?probe=08e4e03d36) | Dec 13, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [3a6a347ff9](https://linux-hardware.org/?probe=3a6a347ff9) | Dec 13, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| Lenovo        | ThinkPad T530 23943J8       | Notebook    | [e5d69d9f81](https://linux-hardware.org/?probe=e5d69d9f81) | Dec 13, 2022 |
| Acer          | Aspire T3-100               | Desktop     | [918ad73eb1](https://linux-hardware.org/?probe=918ad73eb1) | Dec 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e583774bc6](https://linux-hardware.org/?probe=e583774bc6) | Dec 13, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| System76      | Gazelle                     | Notebook    | [8498636db6](https://linux-hardware.org/?probe=8498636db6) | Dec 12, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7d1cc147b9](https://linux-hardware.org/?probe=7d1cc147b9) | Dec 12, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | Notebook    | [d438f3f50a](https://linux-hardware.org/?probe=d438f3f50a) | Dec 12, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | Notebook    | [7ffd00681b](https://linux-hardware.org/?probe=7ffd00681b) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d6dddd9632](https://linux-hardware.org/?probe=d6dddd9632) | Dec 11, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [b85a211b25](https://linux-hardware.org/?probe=b85a211b25) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8b4b187193](https://linux-hardware.org/?probe=8b4b187193) | Dec 11, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [cdc6f36d8c](https://linux-hardware.org/?probe=cdc6f36d8c) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| System76      | Gazelle                     | Notebook    | [8b0297b19e](https://linux-hardware.org/?probe=8b0297b19e) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| Fujitsu       | FMVNS6C3                    | Notebook    | [2cdacbc923](https://linux-hardware.org/?probe=2cdacbc923) | Dec 11, 2022 |
| ASRock        | X570 Extreme4 WiFi ax       | Desktop     | [8f45bcde64](https://linux-hardware.org/?probe=8f45bcde64) | Dec 11, 2022 |
| Dell          | 02GDWG A00                  | Desktop     | [229065f67f](https://linux-hardware.org/?probe=229065f67f) | Dec 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| MSI           | A55M-E33                    | Desktop     | [327967e6a4](https://linux-hardware.org/?probe=327967e6a4) | Dec 11, 2022 |
| Dell          | 02GDWG A00                  | Desktop     | [5cea05fe88](https://linux-hardware.org/?probe=5cea05fe88) | Dec 11, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [55a5f34bf0](https://linux-hardware.org/?probe=55a5f34bf0) | Dec 10, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d83227cce9](https://linux-hardware.org/?probe=d83227cce9) | Dec 10, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [05f65af47e](https://linux-hardware.org/?probe=05f65af47e) | Dec 10, 2022 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [8f571548fd](https://linux-hardware.org/?probe=8f571548fd) | Dec 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8f38dcc9d4](https://linux-hardware.org/?probe=8f38dcc9d4) | Dec 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [e8d8a922a2](https://linux-hardware.org/?probe=e8d8a922a2) | Dec 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [560e61c57f](https://linux-hardware.org/?probe=560e61c57f) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [040652df3d](https://linux-hardware.org/?probe=040652df3d) | Dec 10, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [94a6153aeb](https://linux-hardware.org/?probe=94a6153aeb) | Dec 09, 2022 |
| Samsung       | 730QED                      | Convertible | [1c1a65cd12](https://linux-hardware.org/?probe=1c1a65cd12) | Dec 09, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [9c4d6a19fe](https://linux-hardware.org/?probe=9c4d6a19fe) | Dec 09, 2022 |
| Lenovo        | G470 20078                  | Notebook    | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2dc32e31b3](https://linux-hardware.org/?probe=2dc32e31b3) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1b848d1587](https://linux-hardware.org/?probe=1b848d1587) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [e8fe4392be](https://linux-hardware.org/?probe=e8fe4392be) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [cf32d7158c](https://linux-hardware.org/?probe=cf32d7158c) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [ef20df1d4f](https://linux-hardware.org/?probe=ef20df1d4f) | Dec 09, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e61897fa56](https://linux-hardware.org/?probe=e61897fa56) | Dec 09, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1280df2c5d](https://linux-hardware.org/?probe=1280df2c5d) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [8ce314db56](https://linux-hardware.org/?probe=8ce314db56) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [858f06f0e5](https://linux-hardware.org/?probe=858f06f0e5) | Dec 08, 2022 |
| Acer          | TravelMate P214-41-G2       | Notebook    | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [f9629ee2d7](https://linux-hardware.org/?probe=f9629ee2d7) | Dec 08, 2022 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [300d062122](https://linux-hardware.org/?probe=300d062122) | Dec 08, 2022 |
| Dell          | G15 5515                    | Notebook    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| MSI           | PRO Z790-A WIFI             | Desktop     | [9dfb20d74f](https://linux-hardware.org/?probe=9dfb20d74f) | Dec 08, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [f000ea7b78](https://linux-hardware.org/?probe=f000ea7b78) | Dec 08, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [d2c01d70df](https://linux-hardware.org/?probe=d2c01d70df) | Dec 08, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | Notebook    | [1646f1763d](https://linux-hardware.org/?probe=1646f1763d) | Dec 08, 2022 |
| Avell High... | A62 LIV                     | Notebook    | [a4f96694c4](https://linux-hardware.org/?probe=a4f96694c4) | Dec 07, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [1a4bdc4874](https://linux-hardware.org/?probe=1a4bdc4874) | Dec 07, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [0789961766](https://linux-hardware.org/?probe=0789961766) | Dec 07, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [c376825cca](https://linux-hardware.org/?probe=c376825cca) | Dec 07, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [7eebb7f601](https://linux-hardware.org/?probe=7eebb7f601) | Dec 07, 2022 |
| Dell          | Latitude E7240              | Notebook    | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| HP            | ENVY 17                     | Notebook    | [a19d90a89f](https://linux-hardware.org/?probe=a19d90a89f) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [7abcfecd34](https://linux-hardware.org/?probe=7abcfecd34) | Dec 07, 2022 |
| Dell          | Inspiron 1750               | Notebook    | [e369c14198](https://linux-hardware.org/?probe=e369c14198) | Dec 07, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [6abdbbb7e7](https://linux-hardware.org/?probe=6abdbbb7e7) | Dec 07, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [64abd8c6fe](https://linux-hardware.org/?probe=64abd8c6fe) | Dec 06, 2022 |
| Fujitsu       | FMVNS6C3                    | Notebook    | [5b60c9dfd0](https://linux-hardware.org/?probe=5b60c9dfd0) | Dec 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3c65af8425](https://linux-hardware.org/?probe=3c65af8425) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [6ff5feb92c](https://linux-hardware.org/?probe=6ff5feb92c) | Dec 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d66311f833](https://linux-hardware.org/?probe=d66311f833) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [05f4b7d7cf](https://linux-hardware.org/?probe=05f4b7d7cf) | Dec 06, 2022 |
| MSI           | B150M MORTAR                | Desktop     | [9a87b35e1c](https://linux-hardware.org/?probe=9a87b35e1c) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [310ff494e7](https://linux-hardware.org/?probe=310ff494e7) | Dec 06, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [c0f26cbe79](https://linux-hardware.org/?probe=c0f26cbe79) | Dec 06, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [df9ebcbba6](https://linux-hardware.org/?probe=df9ebcbba6) | Dec 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [86cd634760](https://linux-hardware.org/?probe=86cd634760) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | Notebook    | [6f0ceb7a46](https://linux-hardware.org/?probe=6f0ceb7a46) | Dec 05, 2022 |
| Dell          | G5 5505                     | Notebook    | [f19a76c344](https://linux-hardware.org/?probe=f19a76c344) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [69cc6b3ad3](https://linux-hardware.org/?probe=69cc6b3ad3) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | UL50VT                      | Notebook    | [ff4edb7010](https://linux-hardware.org/?probe=ff4edb7010) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [b9d333782f](https://linux-hardware.org/?probe=b9d333782f) | Dec 05, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [86e9e1e21e](https://linux-hardware.org/?probe=86e9e1e21e) | Dec 05, 2022 |
| HP            | ProBook 6450b               | Notebook    | [f602f6c0bc](https://linux-hardware.org/?probe=f602f6c0bc) | Dec 05, 2022 |
| HP            | ProBook 6450b               | Notebook    | [de39c86a4c](https://linux-hardware.org/?probe=de39c86a4c) | Dec 05, 2022 |
| System76      | Gazelle                     | Notebook    | [deb2c9b6c9](https://linux-hardware.org/?probe=deb2c9b6c9) | Dec 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7687bdc111](https://linux-hardware.org/?probe=7687bdc111) | Dec 04, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [33f26cca4f](https://linux-hardware.org/?probe=33f26cca4f) | Dec 04, 2022 |
| HP            | Notebook                    | Notebook    | [610cea9ebc](https://linux-hardware.org/?probe=610cea9ebc) | Dec 04, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [c74d870263](https://linux-hardware.org/?probe=c74d870263) | Dec 04, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6f34110d45](https://linux-hardware.org/?probe=6f34110d45) | Dec 04, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [2607a15d58](https://linux-hardware.org/?probe=2607a15d58) | Dec 03, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [76cd787c24](https://linux-hardware.org/?probe=76cd787c24) | Dec 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [6913ec89c8](https://linux-hardware.org/?probe=6913ec89c8) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [dd1874248c](https://linux-hardware.org/?probe=dd1874248c) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [eaf129dcfe](https://linux-hardware.org/?probe=eaf129dcfe) | Dec 02, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [8e1a0482b0](https://linux-hardware.org/?probe=8e1a0482b0) | Dec 02, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [1f96acf40f](https://linux-hardware.org/?probe=1f96acf40f) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [8e317647dc](https://linux-hardware.org/?probe=8e317647dc) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | Notebook    | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
| HP            | Notebook                    | Notebook    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [9c5bc7ca10](https://linux-hardware.org/?probe=9c5bc7ca10) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [953943c231](https://linux-hardware.org/?probe=953943c231) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [0e0ed0822c](https://linux-hardware.org/?probe=0e0ed0822c) | Dec 02, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [adeb151478](https://linux-hardware.org/?probe=adeb151478) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Dell          | 0W7H8C A09                  | Server      | [6d411b5c44](https://linux-hardware.org/?probe=6d411b5c44) | Dec 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [562e1f4b92](https://linux-hardware.org/?probe=562e1f4b92) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [c8d4cd1faf](https://linux-hardware.org/?probe=c8d4cd1faf) | Dec 01, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [866e8151d7](https://linux-hardware.org/?probe=866e8151d7) | Dec 01, 2022 |
| HP            | Pavilion dv7                | Notebook    | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [7096492ea2](https://linux-hardware.org/?probe=7096492ea2) | Dec 01, 2022 |
| Dell          | 07JJ74 A01                  | Server      | [cb373247ed](https://linux-hardware.org/?probe=cb373247ed) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [62ae8cb7dc](https://linux-hardware.org/?probe=62ae8cb7dc) | Dec 01, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [a7ae37f43e](https://linux-hardware.org/?probe=a7ae37f43e) | Dec 01, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ce6f6fcaad](https://linux-hardware.org/?probe=ce6f6fcaad) | Dec 01, 2022 |
| Unknown       | 1.0                         | Desktop     | [c8cfeaf2be](https://linux-hardware.org/?probe=c8cfeaf2be) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | Notebook    | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [f8a7663037](https://linux-hardware.org/?probe=f8a7663037) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [b840a0d02e](https://linux-hardware.org/?probe=b840a0d02e) | Dec 01, 2022 |
| Google        | Cyan                        | Notebook    | [4aa7125981](https://linux-hardware.org/?probe=4aa7125981) | Nov 30, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [66b6e49eb5](https://linux-hardware.org/?probe=66b6e49eb5) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9ad34fe6e2](https://linux-hardware.org/?probe=9ad34fe6e2) | Nov 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [99e23cf04d](https://linux-hardware.org/?probe=99e23cf04d) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [b12534f13d](https://linux-hardware.org/?probe=b12534f13d) | Nov 30, 2022 |
| ASRock        | H77M                        | Desktop     | [ffa3496b0d](https://linux-hardware.org/?probe=ffa3496b0d) | Nov 30, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [a42a4d6080](https://linux-hardware.org/?probe=a42a4d6080) | Nov 29, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [48319e6f46](https://linux-hardware.org/?probe=48319e6f46) | Nov 29, 2022 |
| Dell          | Latitude E7240              | Notebook    | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | Notebook    | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | Notebook    | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | Notebook    | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Dell          | Latitude 5411               | Notebook    | [122facad78](https://linux-hardware.org/?probe=122facad78) | Nov 28, 2022 |
| HP            | Pavilion dv7                | Notebook    | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [40c84f5af9](https://linux-hardware.org/?probe=40c84f5af9) | Nov 28, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [151f18b424](https://linux-hardware.org/?probe=151f18b424) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [c0c2f77cdb](https://linux-hardware.org/?probe=c0c2f77cdb) | Nov 28, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [4918810cd1](https://linux-hardware.org/?probe=4918810cd1) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [dee60b9f35](https://linux-hardware.org/?probe=dee60b9f35) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [1651962e5a](https://linux-hardware.org/?probe=1651962e5a) | Nov 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Clevo         | W55xEU                      | Notebook    | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| MSI           | GP72 7RDX                   | Notebook    | [648eb6d88a](https://linux-hardware.org/?probe=648eb6d88a) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [7837242848](https://linux-hardware.org/?probe=7837242848) | Nov 27, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [bf6fc6fd49](https://linux-hardware.org/?probe=bf6fc6fd49) | Nov 27, 2022 |
| Dell          | Latitude E6230              | Notebook    | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | Notebook    | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [1a50d26810](https://linux-hardware.org/?probe=1a50d26810) | Nov 27, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [b924b1fdd6](https://linux-hardware.org/?probe=b924b1fdd6) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| HP            | 872E                        | Mini pc     | [9d8a2595d7](https://linux-hardware.org/?probe=9d8a2595d7) | Nov 27, 2022 |
| Alienware     | 17                          | Notebook    | [08ebf1e9a2](https://linux-hardware.org/?probe=08ebf1e9a2) | Nov 27, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [49dc64dc76](https://linux-hardware.org/?probe=49dc64dc76) | Nov 27, 2022 |
| MSI           | Z97A GAMING 7               | Desktop     | [74341c948b](https://linux-hardware.org/?probe=74341c948b) | Nov 27, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [1e016dcb9b](https://linux-hardware.org/?probe=1e016dcb9b) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [015854e59a](https://linux-hardware.org/?probe=015854e59a) | Nov 26, 2022 |
| Dell          | 04MFRM A02                  | Desktop     | [43239e45b1](https://linux-hardware.org/?probe=43239e45b1) | Nov 26, 2022 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [a8a722921c](https://linux-hardware.org/?probe=a8a722921c) | Nov 26, 2022 |
| HP            | ZBook 15                    | Notebook    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | Notebook    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | Notebook    | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| HP            | 872E                        | Mini pc     | [c7ff015966](https://linux-hardware.org/?probe=c7ff015966) | Nov 26, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [3afe7122f3](https://linux-hardware.org/?probe=3afe7122f3) | Nov 26, 2022 |
| HUAWEI        | MRGF-XX                     | Notebook    | [f60090b407](https://linux-hardware.org/?probe=f60090b407) | Nov 26, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [8268fc2c12](https://linux-hardware.org/?probe=8268fc2c12) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| Gigabyte      | Z77-HD3                     | Desktop     | [e3b7bbc736](https://linux-hardware.org/?probe=e3b7bbc736) | Nov 25, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [ecfe0cfab0](https://linux-hardware.org/?probe=ecfe0cfab0) | Nov 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| Pegatron      | 2A9A                        | Desktop     | [ee74398a78](https://linux-hardware.org/?probe=ee74398a78) | Nov 25, 2022 |
| ASRock        | Z170 Gaming K6              | Desktop     | [de7addf17b](https://linux-hardware.org/?probe=de7addf17b) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [bb91371617](https://linux-hardware.org/?probe=bb91371617) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [c72c157583](https://linux-hardware.org/?probe=c72c157583) | Nov 24, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [bd50429870](https://linux-hardware.org/?probe=bd50429870) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [154702cbc6](https://linux-hardware.org/?probe=154702cbc6) | Nov 23, 2022 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [880f8b9c45](https://linux-hardware.org/?probe=880f8b9c45) | Nov 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| HP            | G62                         | Notebook    | [754a471519](https://linux-hardware.org/?probe=754a471519) | Nov 23, 2022 |
| HP            | 8309                        | Desktop     | [8329dc7b8d](https://linux-hardware.org/?probe=8329dc7b8d) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [4b44aea106](https://linux-hardware.org/?probe=4b44aea106) | Nov 23, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [1c232e6d70](https://linux-hardware.org/?probe=1c232e6d70) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | Notebook    | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Dell          | Latitude E7470              | Notebook    | [03725ebee3](https://linux-hardware.org/?probe=03725ebee3) | Nov 22, 2022 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [dc74022dc5](https://linux-hardware.org/?probe=dc74022dc5) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | Notebook    | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9a3ff03cbb](https://linux-hardware.org/?probe=9a3ff03cbb) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | Notebook    | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [e29dda268c](https://linux-hardware.org/?probe=e29dda268c) | Nov 21, 2022 |
| MSI           | Katana GF76 11UG            | Notebook    | [9627a23b1f](https://linux-hardware.org/?probe=9627a23b1f) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| ASRock        | H310CM-HG4                  | Desktop     | [d4f3608765](https://linux-hardware.org/?probe=d4f3608765) | Nov 21, 2022 |
| Dell          | Precision 7670              | Notebook    | [93f14c8b55](https://linux-hardware.org/?probe=93f14c8b55) | Nov 21, 2022 |
| Alienware     | 17                          | Notebook    | [16b37ce649](https://linux-hardware.org/?probe=16b37ce649) | Nov 21, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [5ec428f8b3](https://linux-hardware.org/?probe=5ec428f8b3) | Nov 21, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d24d3cbf1f](https://linux-hardware.org/?probe=d24d3cbf1f) | Nov 21, 2022 |
| BESSTAR Te... | DMAF5 V1.0                  | Desktop     | [eed1e72aba](https://linux-hardware.org/?probe=eed1e72aba) | Nov 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | Notebook    | [6355251bd6](https://linux-hardware.org/?probe=6355251bd6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | Notebook    | [6eb57e34de](https://linux-hardware.org/?probe=6eb57e34de) | Nov 20, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [412c1923c5](https://linux-hardware.org/?probe=412c1923c5) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [a1b9357fc6](https://linux-hardware.org/?probe=a1b9357fc6) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | Notebook    | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| HP            | ProBook 6450b               | Notebook    | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [41ffb4e75f](https://linux-hardware.org/?probe=41ffb4e75f) | Nov 19, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Dell          | Precision M4400             | Notebook    | [715efc61ae](https://linux-hardware.org/?probe=715efc61ae) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [884474637c](https://linux-hardware.org/?probe=884474637c) | Nov 18, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0b7bd42177](https://linux-hardware.org/?probe=0b7bd42177) | Nov 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | Notebook    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| Gigabyte      | H81M-S1                     | Desktop     | [4498bc64bc](https://linux-hardware.org/?probe=4498bc64bc) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | Notebook    | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Lenovo        | ThinkPad T550 20CJS18S00    | Notebook    | [ba94994594](https://linux-hardware.org/?probe=ba94994594) | Nov 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [078e04eb73](https://linux-hardware.org/?probe=078e04eb73) | Nov 17, 2022 |
| Dell          | G15 5515                    | Notebook    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [33f2716179](https://linux-hardware.org/?probe=33f2716179) | Nov 17, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [478fa166bd](https://linux-hardware.org/?probe=478fa166bd) | Nov 17, 2022 |
| HP            | 805D                        | Desktop     | [cb811984e0](https://linux-hardware.org/?probe=cb811984e0) | Nov 17, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [b696d9eae7](https://linux-hardware.org/?probe=b696d9eae7) | Nov 16, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [0a623c060a](https://linux-hardware.org/?probe=0a623c060a) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | Notebook    | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c6f5c91413](https://linux-hardware.org/?probe=c6f5c91413) | Nov 16, 2022 |
| HP            | ZBook 14 G2                 | Notebook    | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | Notebook    | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| Dell          | 04MFRM A02                  | Desktop     | [677ab8eb16](https://linux-hardware.org/?probe=677ab8eb16) | Nov 16, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [9b870d8287](https://linux-hardware.org/?probe=9b870d8287) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| ATOPNUC       | MA90                        | Mini pc     | [e48bf6df91](https://linux-hardware.org/?probe=e48bf6df91) | Nov 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [2f6204153a](https://linux-hardware.org/?probe=2f6204153a) | Nov 15, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [bc5218c5da](https://linux-hardware.org/?probe=bc5218c5da) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | Notebook    | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [a7e5419c89](https://linux-hardware.org/?probe=a7e5419c89) | Nov 15, 2022 |
| System76      | Oryx Pro                    | Notebook    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | Notebook    | [426dec8739](https://linux-hardware.org/?probe=426dec8739) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | Notebook    | [f55f35c2fe](https://linux-hardware.org/?probe=f55f35c2fe) | Nov 15, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [965a35d0b0](https://linux-hardware.org/?probe=965a35d0b0) | Nov 15, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| HP            | 1998                        | Desktop     | [ddcba37929](https://linux-hardware.org/?probe=ddcba37929) | Nov 14, 2022 |
| HP            | 1998                        | Desktop     | [5249f1cdd7](https://linux-hardware.org/?probe=5249f1cdd7) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | Notebook    | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [e1f2995c6f](https://linux-hardware.org/?probe=e1f2995c6f) | Nov 14, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [43214de971](https://linux-hardware.org/?probe=43214de971) | Nov 13, 2022 |
| Timi          | TM1613                      | Notebook    | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [7de064ae3a](https://linux-hardware.org/?probe=7de064ae3a) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | Notebook    | [25b89592e0](https://linux-hardware.org/?probe=25b89592e0) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [1e4f22395f](https://linux-hardware.org/?probe=1e4f22395f) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [7325cce71f](https://linux-hardware.org/?probe=7325cce71f) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | Notebook    | [86b0a359fa](https://linux-hardware.org/?probe=86b0a359fa) | Nov 13, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [bf79743ff5](https://linux-hardware.org/?probe=bf79743ff5) | Nov 13, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d433817b4f](https://linux-hardware.org/?probe=d433817b4f) | Nov 13, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [8104152607](https://linux-hardware.org/?probe=8104152607) | Nov 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3e75f5aa87](https://linux-hardware.org/?probe=3e75f5aa87) | Nov 12, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [94e5dec391](https://linux-hardware.org/?probe=94e5dec391) | Nov 12, 2022 |
| Dell          | Latitude E7270              | Notebook    | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | 0P4T42 A01                  | All in one  | [c6cc7b7785](https://linux-hardware.org/?probe=c6cc7b7785) | Nov 12, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [c6b54c443e](https://linux-hardware.org/?probe=c6b54c443e) | Nov 12, 2022 |
| Google        | Shyvana                     | Notebook    | [2df69a0782](https://linux-hardware.org/?probe=2df69a0782) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Precision M4700             | Notebook    | [4fc304d429](https://linux-hardware.org/?probe=4fc304d429) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [8472557f0d](https://linux-hardware.org/?probe=8472557f0d) | Nov 11, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [4ed347e186](https://linux-hardware.org/?probe=4ed347e186) | Nov 11, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [1ce532916f](https://linux-hardware.org/?probe=1ce532916f) | Nov 11, 2022 |
| System76      | Lemur Pro                   | Notebook    | [7df985e36a](https://linux-hardware.org/?probe=7df985e36a) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b4aa454d9a](https://linux-hardware.org/?probe=b4aa454d9a) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e5fa54bf6f](https://linux-hardware.org/?probe=e5fa54bf6f) | Nov 10, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [933683bc04](https://linux-hardware.org/?probe=933683bc04) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [d2e25c9c4e](https://linux-hardware.org/?probe=d2e25c9c4e) | Nov 10, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [4ff6488cb2](https://linux-hardware.org/?probe=4ff6488cb2) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [89aa240b37](https://linux-hardware.org/?probe=89aa240b37) | Nov 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [de9c1a6f3e](https://linux-hardware.org/?probe=de9c1a6f3e) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [12c406f96b](https://linux-hardware.org/?probe=12c406f96b) | Nov 09, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fcd0449df8](https://linux-hardware.org/?probe=fcd0449df8) | Nov 09, 2022 |
| MSI           | MS-1688                     | Notebook    | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [e7fb74c85e](https://linux-hardware.org/?probe=e7fb74c85e) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| System76      | Thelio thelio-r2            | Desktop     | [0c282237ab](https://linux-hardware.org/?probe=0c282237ab) | Nov 08, 2022 |
| ASUSTek       | ROG STRIX B550-XE GAMING... | Desktop     | [fa94f8afc5](https://linux-hardware.org/?probe=fa94f8afc5) | Nov 08, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [c4afe62f3b](https://linux-hardware.org/?probe=c4afe62f3b) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [43db111de5](https://linux-hardware.org/?probe=43db111de5) | Nov 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [ba3abf3883](https://linux-hardware.org/?probe=ba3abf3883) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | Notebook    | [ca4bb217ab](https://linux-hardware.org/?probe=ca4bb217ab) | Nov 07, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [29c3e37808](https://linux-hardware.org/?probe=29c3e37808) | Nov 06, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [cb778b5593](https://linux-hardware.org/?probe=cb778b5593) | Nov 06, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| Dell          | G7 7700                     | Notebook    | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [2a2464e0a3](https://linux-hardware.org/?probe=2a2464e0a3) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [eded2f5469](https://linux-hardware.org/?probe=eded2f5469) | Nov 06, 2022 |
| Intel         | P61A-D3                     | Desktop     | [5561c81cf4](https://linux-hardware.org/?probe=5561c81cf4) | Nov 06, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [ba76e04444](https://linux-hardware.org/?probe=ba76e04444) | Nov 06, 2022 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [cd2a716a60](https://linux-hardware.org/?probe=cd2a716a60) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [1cc6297ab8](https://linux-hardware.org/?probe=1cc6297ab8) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | Notebook    | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bad7b9a014](https://linux-hardware.org/?probe=bad7b9a014) | Nov 05, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | Notebook    | [d10e0ce942](https://linux-hardware.org/?probe=d10e0ce942) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [4abe56ea2e](https://linux-hardware.org/?probe=4abe56ea2e) | Nov 05, 2022 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [f4b9627a4a](https://linux-hardware.org/?probe=f4b9627a4a) | Nov 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [b0600fe299](https://linux-hardware.org/?probe=b0600fe299) | Nov 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [5b939b71c7](https://linux-hardware.org/?probe=5b939b71c7) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [2eb5db395b](https://linux-hardware.org/?probe=2eb5db395b) | Nov 05, 2022 |
| Lenovo        | ThinkCentre M91p 4518RS8    | Desktop     | [00fc5e3a1b](https://linux-hardware.org/?probe=00fc5e3a1b) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | Notebook    | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [99f51ff157](https://linux-hardware.org/?probe=99f51ff157) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [58989ea140](https://linux-hardware.org/?probe=58989ea140) | Nov 04, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [17157970ee](https://linux-hardware.org/?probe=17157970ee) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [7479ad8a79](https://linux-hardware.org/?probe=7479ad8a79) | Nov 04, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4be0967ca1](https://linux-hardware.org/?probe=4be0967ca1) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | Notebook    | [0622b6fa8f](https://linux-hardware.org/?probe=0622b6fa8f) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | Notebook    | [bec7082d7a](https://linux-hardware.org/?probe=bec7082d7a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [fa19e49b0a](https://linux-hardware.org/?probe=fa19e49b0a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [d63435720c](https://linux-hardware.org/?probe=d63435720c) | Nov 04, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [c868e47483](https://linux-hardware.org/?probe=c868e47483) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f391e8dce8](https://linux-hardware.org/?probe=f391e8dce8) | Nov 03, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [a43927efff](https://linux-hardware.org/?probe=a43927efff) | Nov 03, 2022 |
| Dell          | Precision 14 5470           | Notebook    | [dab29b7f5b](https://linux-hardware.org/?probe=dab29b7f5b) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [2394d00673](https://linux-hardware.org/?probe=2394d00673) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [39e7abb29a](https://linux-hardware.org/?probe=39e7abb29a) | Nov 03, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [42edcc018a](https://linux-hardware.org/?probe=42edcc018a) | Nov 03, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [77f847ca29](https://linux-hardware.org/?probe=77f847ca29) | Nov 02, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [d9de10d93e](https://linux-hardware.org/?probe=d9de10d93e) | Nov 02, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [4191ce8788](https://linux-hardware.org/?probe=4191ce8788) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Microsoft     | Surface Book                | Tablet      | [e4a7690a77](https://linux-hardware.org/?probe=e4a7690a77) | Nov 02, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4e97493141](https://linux-hardware.org/?probe=4e97493141) | Nov 02, 2022 |
| HP            | 212A                        | Desktop     | [80abe48959](https://linux-hardware.org/?probe=80abe48959) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | Notebook    | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| Fujitsu       | LIFEBOOK A532               | Notebook    | [d4af3b0745](https://linux-hardware.org/?probe=d4af3b0745) | Nov 01, 2022 |
| Intel Clie... | CMCN1CC                     | Notebook    | [719731b244](https://linux-hardware.org/?probe=719731b244) | Nov 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e08326bc94](https://linux-hardware.org/?probe=e08326bc94) | Nov 01, 2022 |
| Dell          | G5 5587                     | Notebook    | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | Notebook    | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [0f62f6f3b1](https://linux-hardware.org/?probe=0f62f6f3b1) | Nov 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [11de150949](https://linux-hardware.org/?probe=11de150949) | Nov 01, 2022 |
| Dell          | Latitude E7240              | Notebook    | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| ASUSTek       | H97-PRO                     | Desktop     | [bae404d45c](https://linux-hardware.org/?probe=bae404d45c) | Oct 31, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d284b1709a](https://linux-hardware.org/?probe=d284b1709a) | Oct 31, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [87187c0e23](https://linux-hardware.org/?probe=87187c0e23) | Oct 31, 2022 |
| Sony          | VAIO                        | All in one  | [cefad415d0](https://linux-hardware.org/?probe=cefad415d0) | Oct 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4c3ae53c16](https://linux-hardware.org/?probe=4c3ae53c16) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | Notebook    | [c6a13e1ab3](https://linux-hardware.org/?probe=c6a13e1ab3) | Oct 31, 2022 |
| Dell          | 02P9X9 A00                  | Server      | [4fa081a282](https://linux-hardware.org/?probe=4fa081a282) | Oct 31, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [43a99f49f8](https://linux-hardware.org/?probe=43a99f49f8) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Precision M6700             | Notebook    | [e5952f6f57](https://linux-hardware.org/?probe=e5952f6f57) | Oct 31, 2022 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [f2893aaedf](https://linux-hardware.org/?probe=f2893aaedf) | Oct 31, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [56ee27b737](https://linux-hardware.org/?probe=56ee27b737) | Oct 31, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [64d1c159aa](https://linux-hardware.org/?probe=64d1c159aa) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e638ed7bd3](https://linux-hardware.org/?probe=e638ed7bd3) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| HP            | 3048h                       | Desktop     | [6ce1d2bf43](https://linux-hardware.org/?probe=6ce1d2bf43) | Oct 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [189fca8ab3](https://linux-hardware.org/?probe=189fca8ab3) | Oct 30, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [71f32a229a](https://linux-hardware.org/?probe=71f32a229a) | Oct 30, 2022 |
| HP            | Pavilion dv7                | Notebook    | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [4bc0220a01](https://linux-hardware.org/?probe=4bc0220a01) | Oct 30, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bd18c2b33d](https://linux-hardware.org/?probe=bd18c2b33d) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| Apple         | MacBookPro3,1               | Notebook    | [27a5553057](https://linux-hardware.org/?probe=27a5553057) | Oct 29, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0616272661](https://linux-hardware.org/?probe=0616272661) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GE60 0NC\0ND                | Notebook    | [79bd38da8f](https://linux-hardware.org/?probe=79bd38da8f) | Oct 29, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| ASUSTek       | ZenBook Q406DA              | Convertible | [f8bae249b9](https://linux-hardware.org/?probe=f8bae249b9) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [1c5d979ba1](https://linux-hardware.org/?probe=1c5d979ba1) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [77ef1a661c](https://linux-hardware.org/?probe=77ef1a661c) | Oct 29, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [cc0f34a2fa](https://linux-hardware.org/?probe=cc0f34a2fa) | Oct 29, 2022 |
| Intel         | B75                         | Desktop     | [59cc97d6c7](https://linux-hardware.org/?probe=59cc97d6c7) | Oct 28, 2022 |
| MSI           | Prestige 15 A12UC           | Notebook    | [3d4c4364f1](https://linux-hardware.org/?probe=3d4c4364f1) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | Notebook    | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [9dcb685f5e](https://linux-hardware.org/?probe=9dcb685f5e) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [df9ef8c115](https://linux-hardware.org/?probe=df9ef8c115) | Oct 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c9cd061f05](https://linux-hardware.org/?probe=c9cd061f05) | Oct 28, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [2fdc53f0f3](https://linux-hardware.org/?probe=2fdc53f0f3) | Oct 28, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [04d54cb9c8](https://linux-hardware.org/?probe=04d54cb9c8) | Oct 28, 2022 |
| Dell          | Precision 5530              | Notebook    | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [d04e962e56](https://linux-hardware.org/?probe=d04e962e56) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | Notebook    | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | Desktop     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [b82aebb005](https://linux-hardware.org/?probe=b82aebb005) | Oct 28, 2022 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [9031f7b82b](https://linux-hardware.org/?probe=9031f7b82b) | Oct 27, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [f27c4e1041](https://linux-hardware.org/?probe=f27c4e1041) | Oct 27, 2022 |
| System76      | Oryx Pro                    | Notebook    | [ff42b6e74a](https://linux-hardware.org/?probe=ff42b6e74a) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | Notebook    | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [e7db99be75](https://linux-hardware.org/?probe=e7db99be75) | Oct 27, 2022 |
| MSI           | B85-G43                     | Desktop     | [48ac016cd9](https://linux-hardware.org/?probe=48ac016cd9) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | Notebook    | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9e7c028b0b](https://linux-hardware.org/?probe=9e7c028b0b) | Oct 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [022cfe6707](https://linux-hardware.org/?probe=022cfe6707) | Oct 26, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [97d2bacb5d](https://linux-hardware.org/?probe=97d2bacb5d) | Oct 26, 2022 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [cb657f604d](https://linux-hardware.org/?probe=cb657f604d) | Oct 26, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [81371581d1](https://linux-hardware.org/?probe=81371581d1) | Oct 26, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                              | Computers | Percent |
|--------------------------------------|-----------|---------|
| 5.19.0-76051900-generic              | 441       | 20.52%  |
| 5.17.5-76051705-generic              | 411       | 19.13%  |
| 6.0.6-76060006-generic               | 293       | 13.63%  |
| 6.0.12-76060006-generic              | 272       | 12.66%  |
| 5.18.10-76051810-generic             | 204       | 9.49%   |
| 5.17.15-76051715-generic             | 184       | 8.56%   |
| 5.16.19-76051619-generic             | 119       | 5.54%   |
| 6.0.2-76060002-generic               | 86        | 4%      |
| 5.19.16-76051916-generic             | 43        | 2%      |
| 6.0.3-76060003-generic               | 39        | 1.81%   |
| 5.16.15-76051615-generic             | 3         | 0.14%   |
| 6.1.8-060108-generic                 | 2         | 0.09%   |
| 6.1.0-x64v1-xanmod1                  | 2         | 0.09%   |
| 6.0.9-060009-generic                 | 2         | 0.09%   |
| 6.0.2-x64v1-xanmod1                  | 2         | 0.09%   |
| 5.19.12-xanmod1                      | 2         | 0.09%   |
| 5.17.7-051707-generic                | 2         | 0.09%   |
| 5.17.5-051705-generic                | 2         | 0.09%   |
| 6.1.7-060107-generic                 | 1         | 0.05%   |
| 6.1.2-surface                        | 1         | 0.05%   |
| 6.1.0-2.1-liquorix-amd64             | 1         | 0.05%   |
| 6.1.0-060100rc5-generic              | 1         | 0.05%   |
| 6.0.9-x64v1-xanmod1                  | 1         | 0.05%   |
| 6.0.8-x64v1-xanmod1                  | 1         | 0.05%   |
| 6.0.7-x64v1-xanmod1                  | 1         | 0.05%   |
| 6.0.6-060006-generic                 | 1         | 0.05%   |
| 6.0.2-x64v2-xanmod1                  | 1         | 0.05%   |
| 6.0.12-x64v1-xanmod1                 | 1         | 0.05%   |
| 6.0.10-x64v1-xanmod1                 | 1         | 0.05%   |
| 6.0.0-060000rc1daily20220820-generic | 1         | 0.05%   |
| 6.0.0-060000-generic                 | 1         | 0.05%   |
| 5.4.210-whitehax0r                   | 1         | 0.05%   |
| 5.19.6-xanmod1-x64v2                 | 1         | 0.05%   |
| 5.19.4-xanmod1                       | 1         | 0.05%   |
| 5.19.3-051903-generic                | 1         | 0.05%   |
| 5.19.14-xanmod1                      | 1         | 0.05%   |
| 5.19.0-xanmod1-x64v2                 | 1         | 0.05%   |
| 5.19.0-rc1+                          | 1         | 0.05%   |
| 5.19.0-051900-generic                | 1         | 0.05%   |
| 5.18.6-xanmod1                       | 1         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 444       | 20.66%  |
| 5.17.5  | 414       | 19.26%  |
| 6.0.6   | 294       | 13.68%  |
| 6.0.12  | 273       | 12.7%   |
| 5.18.10 | 204       | 9.49%   |
| 5.17.15 | 184       | 8.56%   |
| 5.16.19 | 119       | 5.54%   |
| 6.0.2   | 89        | 4.14%   |
| 5.19.16 | 43        | 2%      |
| 6.0.3   | 39        | 1.81%   |
| 6.1.0   | 4         | 0.19%   |
| 6.0.9   | 3         | 0.14%   |
| 5.16.15 | 3         | 0.14%   |
| 5.15.0  | 3         | 0.14%   |
| 6.1.8   | 2         | 0.09%   |
| 6.0.0   | 2         | 0.09%   |
| 5.19.12 | 2         | 0.09%   |
| 5.18.0  | 2         | 0.09%   |
| 5.17.7  | 2         | 0.09%   |
| 6.1.7   | 1         | 0.05%   |
| 6.1.2   | 1         | 0.05%   |
| 6.0.8   | 1         | 0.05%   |
| 6.0.7   | 1         | 0.05%   |
| 6.0.10  | 1         | 0.05%   |
| 5.4.210 | 1         | 0.05%   |
| 5.19.6  | 1         | 0.05%   |
| 5.19.4  | 1         | 0.05%   |
| 5.19.3  | 1         | 0.05%   |
| 5.19.14 | 1         | 0.05%   |
| 5.18.6  | 1         | 0.05%   |
| 5.18.4  | 1         | 0.05%   |
| 5.18.16 | 1         | 0.05%   |
| 5.18.11 | 1         | 0.05%   |
| 5.17.9  | 1         | 0.05%   |
| 5.17.6  | 1         | 0.05%   |
| 5.17.4  | 1         | 0.05%   |
| 5.17.2  | 1         | 0.05%   |
| 5.17.14 | 1         | 0.05%   |
| 5.17.0  | 1         | 0.05%   |
| 5.16.11 | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 683       | 32.34%  |
| 5.17    | 593       | 28.08%  |
| 5.19    | 489       | 23.15%  |
| 5.18    | 210       | 9.94%   |
| 5.16    | 123       | 5.82%   |
| 6.1     | 8         | 0.38%   |
| 5.15    | 5         | 0.24%   |
| 5.4     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1985      | 99.9%   |
| aarch64 | 2         | 0.1%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1936      | 97.19%  |
| KDE5            | 28        | 1.41%   |
| Unknown         | 10        | 0.5%    |
| X-Cinnamon      | 8         | 0.4%    |
| LXQt            | 3         | 0.15%   |
| GNOME Flashback | 3         | 0.15%   |
| Cinnamon        | 2         | 0.1%    |
| XFCE            | 1         | 0.05%   |
| Unity           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1900      | 95.05%  |
| Wayland | 88        | 4.4%    |
| Unknown | 8         | 0.4%    |
| Tty     | 3         | 0.15%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1508      | 75.4%   |
| GDM3    | 481       | 24.05%  |
| SDDM    | 5         | 0.25%   |
| GDM     | 5         | 0.25%   |
| LightDM | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1197      | 59.91%  |
| en_GB   | 140       | 7.01%   |
| pt_BR   | 114       | 5.71%   |
| de_DE   | 77        | 3.85%   |
| C       | 57        | 2.85%   |
| en_AU   | 49        | 2.45%   |
| it_IT   | 48        | 2.4%    |
| en_CA   | 41        | 2.05%   |
| fr_FR   | 34        | 1.7%    |
| es_ES   | 24        | 1.2%    |
| pl_PL   | 20        | 1%      |
| ru_RU   | 18        | 0.9%    |
| sv_SE   | 12        | 0.6%    |
| nl_NL   | 11        | 0.55%   |
| nb_NO   | 11        | 0.55%   |
| fi_FI   | 10        | 0.5%    |
| en_IE   | 10        | 0.5%    |
| Unknown | 10        | 0.5%    |
| en_IN   | 9         | 0.45%   |
| fr_CA   | 7         | 0.35%   |
| es_CL   | 7         | 0.35%   |
| es_AR   | 7         | 0.35%   |
| pt_PT   | 6         | 0.3%    |
| ja_JP   | 6         | 0.3%    |
| es_MX   | 6         | 0.3%    |
| en_NZ   | 6         | 0.3%    |
| de_CH   | 6         | 0.3%    |
| de_AT   | 5         | 0.25%   |
| en_ZA   | 4         | 0.2%    |
| en_DK   | 4         | 0.2%    |
| da_DK   | 4         | 0.2%    |
| tr_TR   | 3         | 0.15%   |
| ro_RO   | 3         | 0.15%   |
| fr_CH   | 3         | 0.15%   |
| es_CO   | 3         | 0.15%   |
| cs_CZ   | 3         | 0.15%   |
| zh_TW   | 2         | 0.1%    |
| fr_BE   | 2         | 0.1%    |
| es_UY   | 2         | 0.1%    |
| en_SG   | 2         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1532      | 76.68%  |
| EFI  | 466       | 23.32%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1880      | 94.47%  |
| Btrfs   | 64        | 3.22%   |
| Overlay | 38        | 1.91%   |
| Xfs     | 5         | 0.25%   |
| Zfs     | 2         | 0.1%    |
| Unknown | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1498      | 74.9%   |
| GPT     | 473       | 23.65%  |
| MBR     | 29        | 1.45%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1927      | 96.74%  |
| Yes       | 65        | 3.26%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1794      | 90.02%  |
| Yes       | 199       | 9.98%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ASUSTek Computer       | 374       | 18.82%  |
| Lenovo                 | 279       | 14.04%  |
| Dell                   | 251       | 12.63%  |
| Hewlett-Packard        | 217       | 10.92%  |
| MSI                    | 148       | 7.45%   |
| Gigabyte Technology    | 122       | 6.14%   |
| Apple                  | 95        | 4.78%   |
| Acer                   | 95        | 4.78%   |
| ASRock                 | 70        | 3.52%   |
| System76               | 48        | 2.42%   |
| Intel                  | 30        | 1.51%   |
| Toshiba                | 23        | 1.16%   |
| Samsung Electronics    | 22        | 1.11%   |
| HUAWEI                 | 18        | 0.91%   |
| Alienware              | 13        | 0.65%   |
| Microsoft              | 11        | 0.55%   |
| Fujitsu                | 11        | 0.55%   |
| Google                 | 9         | 0.45%   |
| Unknown                | 9         | 0.45%   |
| GPU Company            | 8         | 0.4%    |
| Sony                   | 7         | 0.35%   |
| Timi                   | 6         | 0.3%    |
| Notebook               | 6         | 0.3%    |
| Framework              | 6         | 0.3%    |
| Razer                  | 5         | 0.25%   |
| Avell High Performance | 5         | 0.25%   |
| Supermicro             | 4         | 0.2%    |
| Pegatron               | 4         | 0.2%    |
| MACHINIST              | 4         | 0.2%    |
| BESSTAR Tech           | 4         | 0.2%    |
| AZW                    | 4         | 0.2%    |
| Positivo               | 3         | 0.15%   |
| PC Specialist          | 3         | 0.15%   |
| Medion                 | 3         | 0.15%   |
| LG Electronics         | 3         | 0.15%   |
| HONOR                  | 3         | 0.15%   |
| Foxconn                | 3         | 0.15%   |
| Clevo                  | 3         | 0.15%   |
| Wortmann AG            | 2         | 0.1%    |
| Valve                  | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| System76 Oryx Pro                        | 13        | 0.65%   |
| ASUS All Series                          | 13        | 0.65%   |
| Unknown                                  | 13        | 0.65%   |
| System76 Lemur Pro                       | 11        | 0.55%   |
| ASUS TUF Gaming B550-PLUS                | 8         | 0.4%    |
| ASUS ROG STRIX B550-I GAMING             | 8         | 0.4%    |
| ASUS ROG STRIX B550-F GAMING             | 8         | 0.4%    |
| ASUS ROG STRIX B450-F GAMING             | 7         | 0.35%   |
| Apple MacBookAir7,2                      | 7         | 0.35%   |
| Apple MacBookAir6,2                      | 7         | 0.35%   |
| System76 Gazelle                         | 6         | 0.3%    |
| Lenovo IdeaPad S145-15API 81V7           | 6         | 0.3%    |
| Gigabyte B450 AORUS M                    | 6         | 0.3%    |
| Dell XPS 15 9520                         | 6         | 0.3%    |
| Apple MacBookPro9,2                      | 6         | 0.3%    |
| Apple MacBookPro12,1                     | 6         | 0.3%    |
| System76 Thelio                          | 5         | 0.25%   |
| MSI MS-7D54                              | 5         | 0.25%   |
| Gigabyte X570 AORUS ELITE                | 5         | 0.25%   |
| Dell Latitude E7240                      | 5         | 0.25%   |
| ASUS ROG CROSSHAIR VIII DARK HERO        | 5         | 0.25%   |
| Apple MacBookPro7,1                      | 5         | 0.25%   |
| Acer Aspire A515-45                      | 5         | 0.25%   |
| MSI MS-7C56                              | 4         | 0.2%    |
| MSI MS-7B86                              | 4         | 0.2%    |
| MSI MS-7A34                              | 4         | 0.2%    |
| Lenovo Legion 5 15ACH6H 82JU             | 4         | 0.2%    |
| HP Notebook                              | 4         | 0.2%    |
| HP Dev One Notebook PC                   | 4         | 0.2%    |
| Gigabyte B450M DS3H                      | 4         | 0.2%    |
| Framework Laptop                         | 4         | 0.2%    |
| Dell XPS 13 9360                         | 4         | 0.2%    |
| Dell XPS 13 9310                         | 4         | 0.2%    |
| Dell XPS 13 9305                         | 4         | 0.2%    |
| Dell Latitude E7270                      | 4         | 0.2%    |
| Dell Latitude E6540                      | 4         | 0.2%    |
| ASUS VivoBook_ASUSLaptop TP420UA_TM420UA | 4         | 0.2%    |
| ASUS TUF Gaming B550M-PLUS               | 4         | 0.2%    |
| ASUS PRIME B550M-A                       | 4         | 0.2%    |
| ASUS PRIME B450M-A                       | 4         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 102       | 5.13%   |
| ASUS ROG           | 102       | 5.13%   |
| Dell Inspiron      | 70        | 3.52%   |
| Lenovo IdeaPad     | 61        | 3.07%   |
| Acer Aspire        | 59        | 2.97%   |
| Dell Latitude      | 51        | 2.57%   |
| Dell XPS           | 47        | 2.37%   |
| HP Pavilion        | 36        | 1.81%   |
| ASUS PRIME         | 36        | 1.81%   |
| ASUS TUF           | 35        | 1.76%   |
| Dell Precision     | 31        | 1.56%   |
| ASUS VivoBook      | 30        | 1.51%   |
| Lenovo Legion      | 29        | 1.46%   |
| HP EliteBook       | 26        | 1.31%   |
| HP Laptop          | 25        | 1.26%   |
| HP ENVY            | 24        | 1.21%   |
| HP ProBook         | 21        | 1.06%   |
| Toshiba Satellite  | 20        | 1.01%   |
| Lenovo Yoga        | 18        | 0.91%   |
| Lenovo ThinkCentre | 18        | 0.91%   |
| ASUS ASUS          | 18        | 0.91%   |
| Dell OptiPlex      | 16        | 0.81%   |
| Gigabyte B450      | 14        | 0.7%    |
| Dell Vostro        | 14        | 0.7%    |
| ASUS Zenbook       | 14        | 0.7%    |
| System76 Oryx      | 13        | 0.65%   |
| HP Compaq          | 13        | 0.65%   |
| ASUS All           | 13        | 0.65%   |
| Acer Swift         | 13        | 0.65%   |
| Unknown            | 13        | 0.65%   |
| HP ZBook           | 12        | 0.6%    |
| Gigabyte X570      | 12        | 0.6%    |
| System76 Lemur     | 11        | 0.55%   |
| Microsoft Surface  | 11        | 0.55%   |
| HP OMEN            | 11        | 0.55%   |
| Acer Nitro         | 11        | 0.55%   |
| Lenovo ThinkBook   | 9         | 0.45%   |
| HP EliteDesk       | 9         | 0.45%   |
| Apple MacBookPro11 | 9         | 0.45%   |
| System76 Thelio    | 8         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 311       | 15.65%  |
| 2020    | 277       | 13.94%  |
| 2019    | 197       | 9.91%   |
| 2018    | 189       | 9.51%   |
| 2022    | 172       | 8.66%   |
| 2013    | 110       | 5.54%   |
| 2012    | 110       | 5.54%   |
| 2016    | 107       | 5.39%   |
| 2017    | 105       | 5.28%   |
| 2014    | 92        | 4.63%   |
| 2015    | 86        | 4.33%   |
| 2011    | 81        | 4.08%   |
| 2010    | 62        | 3.12%   |
| 2009    | 52        | 2.62%   |
| 2008    | 21        | 1.06%   |
| 2007    | 11        | 0.55%   |
| Unknown | 3         | 0.15%   |
| 2006    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1140      | 57.37%  |
| Desktop        | 683       | 34.37%  |
| Convertible    | 79        | 3.98%   |
| Mini pc        | 33        | 1.66%   |
| All in one     | 24        | 1.21%   |
| Tablet         | 19        | 0.96%   |
| Server         | 6         | 0.3%    |
| System on chip | 3         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1986      | 99.95%  |
| Enabled  | 1         | 0.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1948      | 98.04%  |
| Yes  | 39        | 1.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 551       | 27.55%  |
| 4.01-8.0        | 445       | 22.25%  |
| 8.01-16.0       | 363       | 18.15%  |
| 32.01-64.0      | 321       | 16.05%  |
| 3.01-4.0        | 177       | 8.85%   |
| 64.01-256.0     | 94        | 4.7%    |
| 24.01-32.0      | 39        | 1.95%   |
| 1.01-2.0        | 4         | 0.2%    |
| More than 256.0 | 3         | 0.15%   |
| 2.01-3.0        | 3         | 0.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 670       | 31.62%  |
| 4.01-8.0    | 553       | 26.1%   |
| 3.01-4.0    | 503       | 23.74%  |
| 1.01-2.0    | 225       | 10.62%  |
| 8.01-16.0   | 134       | 6.32%   |
| 16.01-24.0  | 23        | 1.09%   |
| 24.01-32.0  | 5         | 0.24%   |
| 32.01-64.0  | 4         | 0.19%   |
| 64.01-256.0 | 2         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1166      | 58.24%  |
| 2      | 520       | 25.97%  |
| 3      | 170       | 8.49%   |
| 4      | 69        | 3.45%   |
| 5      | 36        | 1.8%    |
| 6      | 18        | 0.9%    |
| 7      | 9         | 0.45%   |
| 0      | 7         | 0.35%   |
| 9      | 3         | 0.15%   |
| 10     | 2         | 0.1%    |
| 19     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1528      | 76.71%  |
| Yes       | 464       | 23.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1614      | 80.94%  |
| No        | 380       | 19.06%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1673      | 84.03%  |
| No        | 318       | 15.97%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1445      | 72.36%  |
| No        | 552       | 27.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 609       | 30.5%   |
| Brazil       | 152       | 7.61%   |
| Germany      | 120       | 6.01%   |
| Canada       | 96        | 4.81%   |
| UK           | 91        | 4.56%   |
| Italy        | 89        | 4.46%   |
| Australia    | 65        | 3.25%   |
| India        | 58        | 2.9%    |
| France       | 53        | 2.65%   |
| Netherlands  | 40        | 2%      |
| Russia       | 35        | 1.75%   |
| Norway       | 32        | 1.6%    |
| Sweden       | 28        | 1.4%    |
| Spain        | 28        | 1.4%    |
| Poland       | 28        | 1.4%    |
| Greece       | 23        | 1.15%   |
| Finland      | 23        | 1.15%   |
| Switzerland  | 22        | 1.1%    |
| Mexico       | 20        | 1%      |
| Portugal     | 19        | 0.95%   |
| Austria      | 18        | 0.9%    |
| Argentina    | 17        | 0.85%   |
| Romania      | 16        | 0.8%    |
| Turkey       | 15        | 0.75%   |
| Belgium      | 15        | 0.75%   |
| New Zealand  | 14        | 0.7%    |
| Indonesia    | 14        | 0.7%    |
| Philippines  | 13        | 0.65%   |
| Japan        | 13        | 0.65%   |
| Ireland      | 13        | 0.65%   |
| Chile        | 13        | 0.65%   |
| Thailand     | 12        | 0.6%    |
| Hungary      | 12        | 0.6%    |
| Denmark      | 11        | 0.55%   |
| South Africa | 9         | 0.45%   |
| Serbia       | 9         | 0.45%   |
| Colombia     | 8         | 0.4%    |
| Bulgaria     | 8         | 0.4%    |
| Hong Kong    | 7         | 0.35%   |
| Egypt        | 7         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Milan            | 18        | 0.88%   |
| Berlin           | 17        | 0.83%   |
| Brisbane         | 16        | 0.78%   |
| Melbourne        | 15        | 0.73%   |
| Rio de Janeiro   | 14        | 0.68%   |
| Helsinki         | 13        | 0.64%   |
| Vienna           | 12        | 0.59%   |
| Sydney           | 12        | 0.59%   |
| Sao Paulo        | 12        | 0.59%   |
| Rome             | 12        | 0.59%   |
| Istanbul         | 12        | 0.59%   |
| Zurich           | 10        | 0.49%   |
| Seattle          | 10        | 0.49%   |
| Oslo             | 10        | 0.49%   |
| London           | 10        | 0.49%   |
| Moscow           | 9         | 0.44%   |
| Mannheim         | 8         | 0.39%   |
| Chicago          | 8         | 0.39%   |
| Bengaluru        | 8         | 0.39%   |
| St Petersburg    | 7         | 0.34%   |
| San Antonio      | 7         | 0.34%   |
| Paris            | 7         | 0.34%   |
| Madrid           | 7         | 0.34%   |
| Lisbon           | 7         | 0.34%   |
| Edmonton         | 7         | 0.34%   |
| Dallas           | 7         | 0.34%   |
| Belgrade         | 7         | 0.34%   |
| Athens           | 7         | 0.34%   |
| Toronto          | 6         | 0.29%   |
| Singapore        | 6         | 0.29%   |
| San José        | 6         | 0.29%   |
| San Francisco    | 6         | 0.29%   |
| Portland         | 6         | 0.29%   |
| Minneapolis      | 6         | 0.29%   |
| Lincoln          | 6         | 0.29%   |
| Jakarta          | 6         | 0.29%   |
| Dublin           | 6         | 0.29%   |
| Colorado Springs | 6         | 0.29%   |
| Cleveland        | 6         | 0.29%   |
| Calgary          | 6         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 583       | 801    | 19.3%   |
| WDC                         | 348       | 460    | 11.52%  |
| Seagate                     | 330       | 456    | 10.93%  |
| SanDisk                     | 230       | 280    | 7.62%   |
| Kingston                    | 151       | 177    | 5%      |
| Toshiba                     | 148       | 166    | 4.9%    |
| Crucial                     | 142       | 188    | 4.7%    |
| SK hynix                    | 110       | 127    | 3.64%   |
| Intel                       | 82        | 101    | 2.72%   |
| Unknown                     | 74        | 99     | 2.45%   |
| Micron Technology           | 69        | 79     | 2.28%   |
| Apple                       | 52        | 59     | 1.72%   |
| Hitachi                     | 46        | 62     | 1.52%   |
| Phison                      | 44        | 55     | 1.46%   |
| A-DATA Technology           | 42        | 46     | 1.39%   |
| HGST                        | 41        | 45     | 1.36%   |
| Micron/Crucial Technology   | 35        | 41     | 1.16%   |
| Phison Electronics          | 32        | 44     | 1.06%   |
| PNY                         | 31        | 40     | 1.03%   |
| KIOXIA                      | 31        | 33     | 1.03%   |
| Silicon Motion              | 29        | 37     | 0.96%   |
| China                       | 24        | 29     | 0.79%   |
| SPCC                        | 18        | 23     | 0.6%    |
| Netac                       | 18        | 18     | 0.6%    |
| Intenso                     | 14        | 14     | 0.46%   |
| LITEON                      | 12        | 15     | 0.4%    |
| Unknown                     | 12        | 13     | 0.4%    |
| Team                        | 10        | 12     | 0.33%   |
| Patriot                     | 9         | 11     | 0.3%    |
| OCZ                         | 9         | 11     | 0.3%    |
| LITEONIT                    | 9         | 12     | 0.3%    |
| Lexar                       | 9         | 9      | 0.3%    |
| Kingston Technology Company | 9         | 10     | 0.3%    |
| KingSpec                    | 9         | 10     | 0.3%    |
| ADATA Technology            | 9         | 9      | 0.3%    |
| XPG                         | 8         | 10     | 0.26%   |
| Union Memory (Shenzhen)     | 8         | 10     | 0.26%   |
| Realtek Semiconductor       | 8         | 8      | 0.26%   |
| Hewlett-Packard             | 7         | 7      | 0.23%   |
| JMicron Technology          | 6         | 15     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB  | 49        | 1.46%   |
| Kingston SA400S37240G 240GB SSD                      | 40        | 1.19%   |
| Samsung NVMe SSD Drive 1TB                           | 36        | 1.07%   |
| SanDisk NVMe SSD Drive 1TB                           | 31        | 0.92%   |
| Samsung NVMe SSD Drive 500GB                         | 29        | 0.86%   |
| Seagate ST2000DM008-2FR102 2TB                       | 27        | 0.81%   |
| Samsung SSD 850 EVO 500GB                            | 26        | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 26        | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB                       | 23        | 0.69%   |
| Crucial CT1000MX500SSD1 1TB                          | 23        | 0.69%   |
| Samsung SSD 860 EVO 1TB                              | 22        | 0.66%   |
| Samsung SSD 850 EVO 250GB                            | 22        | 0.66%   |
| Samsung NVMe SSD Drive 512GB                         | 22        | 0.66%   |
| Kingston SA400S37480G 480GB SSD                      | 22        | 0.66%   |
| Samsung NVMe SSD Drive 2TB                           | 20        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                       | 19        | 0.57%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 19        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB  | 19        | 0.57%   |
| Samsung SSD 860 EVO 500GB                            | 18        | 0.54%   |
| Crucial CT240BX500SSD1 240GB                         | 18        | 0.54%   |
| Kingston SA400S37120G 120GB SSD                      | 17        | 0.51%   |
| SanDisk NVMe SSD Drive 512GB                         | 16        | 0.48%   |
| Crucial CT500MX500SSD1 500GB                         | 16        | 0.48%   |
| SK hynix NVMe SSD Drive 512GB                        | 15        | 0.45%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 15        | 0.45%   |
| Phison E12 NVMe Controller 1TB                       | 15        | 0.45%   |
| Toshiba MQ01ABD100 1TB                               | 14        | 0.42%   |
| Seagate Expansion 240GB                              | 14        | 0.42%   |
| SanDisk NVMe SSD Drive 500GB                         | 14        | 0.42%   |
| Crucial CT1000BX500SSD1 1TB                          | 14        | 0.42%   |
| Unknown MMC Card  64GB                               | 13        | 0.39%   |
| Seagate ST1000DM003-1ER162 1TB                       | 13        | 0.39%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB       | 13        | 0.39%   |
| Samsung SSD 970 EVO Plus 1TB                         | 13        | 0.39%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 13        | 0.39%   |
| HGST HTS721010A9E630 1TB                             | 13        | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                     | 12        | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 12        | 0.36%   |
| Unknown MMC Card  128GB                              | 12        | 0.36%   |
| Unknown                                              | 12        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 319       | 437    | 38.86%  |
| WDC                 | 247       | 325    | 30.09%  |
| Toshiba             | 99        | 112    | 12.06%  |
| Hitachi             | 46        | 62     | 5.6%    |
| HGST                | 41        | 45     | 4.99%   |
| Samsung Electronics | 24        | 30     | 2.92%   |
| Apple               | 14        | 16     | 1.71%   |
| Unknown             | 10        | 14     | 1.22%   |
| Fujitsu             | 4         | 5      | 0.49%   |
| SABRENT             | 3         | 5      | 0.37%   |
| Maxtor              | 3         | 3      | 0.37%   |
| JMicron Technology  | 2         | 7      | 0.24%   |
| Intenso             | 2         | 2      | 0.24%   |
| ASMT                | 2         | 3      | 0.24%   |
| USB3.0              | 1         | 1      | 0.12%   |
| RSH-339             | 1         | 1      | 0.12%   |
| HGST HDN            | 1         | 1      | 0.12%   |
| ASMedia             | 1         | 1      | 0.12%   |
| Asm                 | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 229       | 307    | 23.2%   |
| Crucial             | 127       | 165    | 12.87%  |
| Kingston            | 118       | 134    | 11.96%  |
| SanDisk             | 84        | 97     | 8.51%   |
| WDC                 | 67        | 80     | 6.79%   |
| Apple               | 33        | 35     | 3.34%   |
| PNY                 | 30        | 39     | 3.04%   |
| A-DATA Technology   | 27        | 30     | 2.74%   |
| China               | 23        | 28     | 2.33%   |
| Intel               | 20        | 21     | 2.03%   |
| SK hynix            | 16        | 19     | 1.62%   |
| Netac               | 16        | 16     | 1.62%   |
| SPCC                | 14        | 15     | 1.42%   |
| Toshiba             | 13        | 13     | 1.32%   |
| Micron Technology   | 12        | 12     | 1.22%   |
| LITEON              | 11        | 14     | 1.11%   |
| Patriot             | 9         | 11     | 0.91%   |
| OCZ                 | 9         | 11     | 0.91%   |
| LITEONIT            | 9         | 12     | 0.91%   |
| KingSpec            | 9         | 10     | 0.91%   |
| Intenso             | 8         | 8      | 0.81%   |
| Team                | 6         | 8      | 0.61%   |
| Lexar               | 6         | 6      | 0.61%   |
| Hewlett-Packard     | 5         | 5      | 0.51%   |
| GOODRAM             | 5         | 5      | 0.51%   |
| KingDian            | 4         | 5      | 0.41%   |
| Seagate             | 3         | 3      | 0.3%    |
| MyDigitalSSD        | 3         | 3      | 0.3%    |
| JMicron Technology  | 3         | 3      | 0.3%    |
| Apacer              | 3         | 7      | 0.3%    |
| Unknown             | 3         | 3      | 0.3%    |
| TrekStor            | 2         | 2      | 0.2%    |
| Transcend           | 2         | 4      | 0.2%    |
| TO Exter            | 2         | 2      | 0.2%    |
| PNY USB             | 2         | 2      | 0.2%    |
| Mushkin             | 2         | 3      | 0.2%    |
| INTEL SS            | 2         | 3      | 0.2%    |
| FORESEE             | 2         | 3      | 0.2%    |
| Fanxiang            | 2         | 2      | 0.2%    |
| Corsair             | 2         | 3      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1025      | 1414   | 37.86%  |
| SSD     | 865       | 1196   | 31.95%  |
| HDD     | 695       | 1071   | 25.67%  |
| MMC     | 62        | 71     | 2.29%   |
| Unknown | 60        | 87     | 2.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1254      | 2168   | 50.81%  |
| NVMe | 1024      | 1411   | 41.49%  |
| SAS  | 128       | 189    | 5.19%   |
| MMC  | 62        | 71     | 2.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 855       | 1189   | 51.63%  |
| 0.51-1.0   | 519       | 670    | 31.34%  |
| 1.01-2.0   | 167       | 220    | 10.08%  |
| 3.01-4.0   | 47        | 72     | 2.84%   |
| 4.01-10.0  | 40        | 63     | 2.42%   |
| 2.01-3.0   | 25        | 42     | 1.51%   |
| 10.01-20.0 | 3         | 11     | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 561       | 27.68%  |
| 251-500        | 514       | 25.36%  |
| 501-1000       | 437       | 21.56%  |
| 1001-2000      | 196       | 9.67%   |
| More than 3000 | 98        | 4.83%   |
| 2001-3000      | 73        | 3.6%    |
| 51-100         | 57        | 2.81%   |
| 1-20           | 48        | 2.37%   |
| 21-50          | 33        | 1.63%   |
| Unknown        | 10        | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 621       | 29.67%  |
| 21-50          | 449       | 21.45%  |
| 101-250        | 323       | 15.43%  |
| 51-100         | 260       | 12.42%  |
| 251-500        | 203       | 9.7%    |
| 501-1000       | 108       | 5.16%   |
| 1001-2000      | 63        | 3.01%   |
| More than 3000 | 35        | 1.67%   |
| 2001-3000      | 21        | 1%      |
| Unknown        | 10        | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| HGST HTS725050A7E630 500GB                   | 3         | 4      | 4.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB           | 2         | 2      | 3.23%   |
| WDC WDS240G2G0A-00JH30 240GB SSD             | 1         | 1      | 1.61%   |
| WDC WD60EFRX-68L0BN1 6TB                     | 1         | 1      | 1.61%   |
| WDC WD5001AALS-00J7B1 500GB                  | 1         | 1      | 1.61%   |
| WDC WD5000AADS-00S9B0 500GB                  | 1         | 1      | 1.61%   |
| WDC WD20EFRX-68AX9N0 2TB                     | 1         | 4      | 1.61%   |
| WDC WD10SPZX-22Z10T0 1TB                     | 1         | 1      | 1.61%   |
| WDC WD10JPVX-60JC3T1 1TB                     | 1         | 1      | 1.61%   |
| WDC WD10JPVX-60JC3T0 1TB                     | 1         | 1      | 1.61%   |
| WDC WD10EZEX-60WN4A0 1TB                     | 1         | 1      | 1.61%   |
| WDC WD1002FAEX-00Z3A0 1TB                    | 1         | 1      | 1.61%   |
| WDC WD1001FALS-00E8B0 1TB                    | 1         | 1      | 1.61%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB         | 1         | 1      | 1.61%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD     | 1         | 1      | 1.61%   |
| Toshiba MQ04ABF100 1TB                       | 1         | 1      | 1.61%   |
| Toshiba MQ01ACF050 500GB                     | 1         | 1      | 1.61%   |
| Toshiba MK1655GSX 160GB                      | 1         | 1      | 1.61%   |
| Team TM8FP4004T 4TB                          | 1         | 1      | 1.61%   |
| SK hynix PC711 HFS001TDE9X073N 1TB           | 1         | 1      | 1.61%   |
| SK hynix HFS512G39TND-N210A 512GB SSD        | 1         | 1      | 1.61%   |
| SK hynix BC501 NVMe Solid State Drive 512GB  | 1         | 1      | 1.61%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 1.61%   |
| Seagate ST500LM030-2E717D 500GB              | 1         | 1      | 1.61%   |
| Seagate ST5000LM000-2AN170 5TB               | 1         | 1      | 1.61%   |
| Seagate ST320LM001 HN-M320MBB 320GB          | 1         | 1      | 1.61%   |
| Seagate ST2000DM008-2FR102 2TB               | 1         | 1      | 1.61%   |
| Seagate ST2000DM006-2DM164 2TB               | 1         | 1      | 1.61%   |
| Seagate ST2000DM001-1CH164 2TB               | 1         | 1      | 1.61%   |
| Seagate ST1500DL003-9VT16L 1TB               | 1         | 1      | 1.61%   |
| Seagate ST1000LX015-1U7172 1TB               | 1         | 1      | 1.61%   |
| Seagate Expansion Desk 6TB                   | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 850 PRO 256GB        | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 850 EVO 500GB        | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 850 EVO 250GB        | 1         | 1      | 1.61%   |
| Samsung Electronics SSD 840 PRO Series 512GB | 1         | 1      | 1.61%   |
| Samsung Electronics MZVKW512HMJP-00000 512GB | 1         | 1      | 1.61%   |
| Samsung Electronics HD502HI 500GB            | 1         | 1      | 1.61%   |
| Samsung Electronics HD103SI 1TB              | 1         | 1      | 1.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 12        | 15     | 20%     |
| Seagate             | 10        | 12     | 16.67%  |
| Samsung Electronics | 8         | 8      | 13.33%  |
| Toshiba             | 4         | 4      | 6.67%   |
| HGST                | 4         | 5      | 6.67%   |
| SK hynix            | 3         | 3      | 5%      |
| Hitachi             | 3         | 5      | 5%      |
| Micron Technology   | 2         | 3      | 3.33%   |
| Kingston            | 2         | 2      | 3.33%   |
| Intel               | 2         | 2      | 3.33%   |
| Crucial             | 2         | 2      | 3.33%   |
| A-DATA Technology   | 2         | 2      | 3.33%   |
| Team                | 1         | 1      | 1.67%   |
| SABRENT             | 1         | 1      | 1.67%   |
| Plextor             | 1         | 1      | 1.67%   |
| Lexar               | 1         | 1      | 1.67%   |
| Leven               | 1         | 1      | 1.67%   |
| BAITITON            | 1         | 1      | 1.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 13     | 30.3%   |
| Seagate             | 10        | 12     | 30.3%   |
| HGST                | 4         | 5      | 12.12%  |
| Toshiba             | 3         | 3      | 9.09%   |
| Hitachi             | 3         | 5      | 9.09%   |
| Samsung Electronics | 2         | 2      | 6.06%   |
| SABRENT             | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 41     | 53.45%  |
| SSD  | 18        | 18     | 31.03%  |
| NVMe | 9         | 10     | 15.52%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 50%     |
| KingDian S400 120GB SSD           | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| KingDian            | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1551      | 2992   | 73.4%   |
| Works    | 504       | 776    | 23.85%  |
| Malfunc  | 56        | 69     | 2.65%   |
| Failed   | 2         | 2      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1115      | 39.22%  |
| AMD                            | 508       | 17.87%  |
| Samsung Electronics            | 402       | 14.14%  |
| SanDisk                        | 190       | 6.68%   |
| SK hynix                       | 94        | 3.31%   |
| Phison Electronics             | 80        | 2.81%   |
| Micron Technology              | 57        | 2%      |
| Micron/Crucial Technology      | 50        | 1.76%   |
| Kingston Technology Company    | 41        | 1.44%   |
| ASMedia Technology             | 41        | 1.44%   |
| Toshiba America Info Systems   | 37        | 1.3%    |
| Silicon Motion                 | 33        | 1.16%   |
| KIOXIA                         | 32        | 1.13%   |
| Nvidia                         | 29        | 1.02%   |
| ADATA Technology               | 26        | 0.91%   |
| Marvell Technology Group       | 23        | 0.81%   |
| Realtek Semiconductor          | 12        | 0.42%   |
| Solid State Storage Technology | 11        | 0.39%   |
| Union Memory (Shenzhen)        | 10        | 0.35%   |
| JMicron Technology             | 9         | 0.32%   |
| Seagate Technology             | 7         | 0.25%   |
| Apple                          | 6         | 0.21%   |
| Shenzhen Longsys Electronics   | 5         | 0.18%   |
| Broadcom / LSI                 | 5         | 0.18%   |
| LSI Logic / Symbios Logic      | 4         | 0.14%   |
| INNOGRIT                       | 4         | 0.14%   |
| Lite-On Technology             | 3         | 0.11%   |
| Silicon Image                  | 2         | 0.07%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.07%   |
| Yangtze Memory Technologies    | 1         | 0.04%   |
| VIA Technologies               | 1         | 0.04%   |
| O2 Micro                       | 1         | 0.04%   |
| Netac Technology               | 1         | 0.04%   |
| Hewlett-Packard                | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 364       | 11.59%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 176       | 5.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 91        | 2.9%    |
| AMD 500 Series Chipset SATA Controller                                         | 85        | 2.71%   |
| AMD 400 Series Chipset SATA Controller                                         | 84        | 2.68%   |
| Samsung NVMe SSD Controller 980                                                | 82        | 2.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 82        | 2.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 81        | 2.58%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 67        | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 67        | 2.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 64        | 2.04%   |
| Micron Non-Volatile memory controller                                          | 56        | 1.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 51        | 1.62%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 50        | 1.59%   |
| SanDisk Non-Volatile memory controller                                         | 48        | 1.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 44        | 1.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 44        | 1.4%    |
| Phison E12 NVMe Controller                                                     | 40        | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 39        | 1.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 39        | 1.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 38        | 1.21%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 38        | 1.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 38        | 1.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 34        | 1.08%   |
| Intel SSD 660P Series                                                          | 33        | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 31        | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 29        | 0.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 28        | 0.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 28        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 27        | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 27        | 0.86%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 26        | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 25        | 0.8%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 24        | 0.76%   |
| Intel SATA Controller [RAID mode]                                              | 24        | 0.76%   |
| Kingston Company Company Non-Volatile memory controller                        | 23        | 0.73%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 22        | 0.7%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 22        | 0.7%    |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 21        | 0.67%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 20        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1429      | 51.61%  |
| NVMe | 1021      | 36.87%  |
| RAID | 191       | 6.9%    |
| IDE  | 119       | 4.3%    |
| SAS  | 9         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1335      | 67.19%  |
| AMD    | 650       | 32.71%  |
| ARM    | 2         | 0.1%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 35        | 1.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 34        | 1.71%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 30        | 1.51%   |
| AMD Ryzen 5 3600 6-Core Processor             | 30        | 1.51%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 27        | 1.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 23        | 1.16%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 22        | 1.11%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 21        | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 21        | 1.06%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 20        | 1.01%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 0.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 18        | 0.9%    |
| Intel 12th Gen Core i7-12700H                 | 18        | 0.9%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 18        | 0.9%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 18        | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 0.85%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 17        | 0.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 16        | 0.8%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.8%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 0.75%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 15        | 0.75%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 15        | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 14        | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 14        | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 0.7%    |
| AMD Ryzen 7 5700G with Radeon Graphics        | 14        | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 0.6%    |
| AMD Ryzen 7 2700X Eight-Core Processor        | 12        | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.55%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 11        | 0.55%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 11        | 0.55%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 0.55%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 11        | 0.55%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 10        | 0.5%    |
| Intel Core i7-6700K CPU @ 4.00GHz             | 10        | 0.5%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 10        | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 9         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 423       | 21.28%  |
| Intel Core i5           | 382       | 19.22%  |
| Other                   | 244       | 12.27%  |
| AMD Ryzen 5             | 212       | 10.66%  |
| AMD Ryzen 7             | 197       | 9.91%   |
| Intel Core i3           | 90        | 4.53%   |
| AMD Ryzen 9             | 76        | 3.82%   |
| Intel Core 2 Duo        | 46        | 2.31%   |
| Intel Celeron           | 46        | 2.31%   |
| Intel Xeon              | 37        | 1.86%   |
| AMD Ryzen 3             | 24        | 1.21%   |
| AMD FX                  | 22        | 1.11%   |
| Intel Pentium           | 17        | 0.86%   |
| Intel Core i9           | 17        | 0.86%   |
| AMD A8                  | 14        | 0.7%    |
| AMD A10                 | 14        | 0.7%    |
| AMD Ryzen 7 PRO         | 12        | 0.6%    |
| AMD A6                  | 10        | 0.5%    |
| Intel Core 2 Quad       | 9         | 0.45%   |
| AMD Ryzen 5 PRO         | 8         | 0.4%    |
| AMD Ryzen Threadripper  | 7         | 0.35%   |
| AMD A4                  | 7         | 0.35%   |
| Intel Pentium Gold      | 6         | 0.3%    |
| Intel Pentium Dual-Core | 6         | 0.3%    |
| AMD Athlon              | 5         | 0.25%   |
| Intel Pentium Silver    | 4         | 0.2%    |
| Intel Atom              | 4         | 0.2%    |
| AMD Ryzen 3 PRO         | 4         | 0.2%    |
| AMD Athlon II X2        | 4         | 0.2%    |
| Intel Core 2            | 3         | 0.15%   |
| AMD Phenom              | 3         | 0.15%   |
| AMD Athlon II X4        | 3         | 0.15%   |
| Intel Pentium Dual      | 2         | 0.1%    |
| Intel Pentium D         | 2         | 0.1%    |
| Intel Genuine           | 2         | 0.1%    |
| Intel Core m5           | 2         | 0.1%    |
| AMD Phenom II X6        | 2         | 0.1%    |
| AMD Phenom II X4        | 2         | 0.1%    |
| AMD Phenom II           | 2         | 0.1%    |
| AMD E1                  | 2         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 698       | 35.11%  |
| 2       | 508       | 25.55%  |
| 8       | 300       | 15.09%  |
| 6       | 299       | 15.04%  |
| 12      | 57        | 2.87%   |
| 16      | 36        | 1.81%   |
| 14      | 33        | 1.66%   |
| 10      | 26        | 1.31%   |
| 3       | 11        | 0.55%   |
| 1       | 9         | 0.45%   |
| 24      | 4         | 0.2%    |
| 32      | 2         | 0.1%    |
| Unknown | 2         | 0.1%    |
| 64      | 1         | 0.05%   |
| 40      | 1         | 0.05%   |
| 18      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1976      | 99.45%  |
| 2       | 9         | 0.45%   |
| Unknown | 2         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1633      | 82.18%  |
| 1       | 352       | 17.72%  |
| Unknown | 2         | 0.1%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1986      | 99.95%  |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1487      | 73.83%  |
| 0x806c1    | 44        | 2.18%   |
| 0x0a50000c | 31        | 1.54%   |
| 0x806ec    | 26        | 1.29%   |
| 0x806d1    | 23        | 1.14%   |
| 0x906a3    | 21        | 1.04%   |
| 0x806ea    | 20        | 0.99%   |
| 0xa0652    | 18        | 0.89%   |
| 0x906ea    | 18        | 0.89%   |
| 0x306a9    | 18        | 0.89%   |
| 0x08701021 | 18        | 0.89%   |
| 0x08600106 | 16        | 0.79%   |
| 0x08608103 | 14        | 0.7%    |
| 0x506e3    | 13        | 0.65%   |
| 0x406e3    | 12        | 0.6%    |
| 0x206a7    | 12        | 0.6%    |
| 0x906e9    | 11        | 0.55%   |
| 0x306c3    | 11        | 0.55%   |
| 0x0a201016 | 11        | 0.55%   |
| 0x08108109 | 11        | 0.55%   |
| 0x0800820d | 11        | 0.55%   |
| 0x906a4    | 10        | 0.5%    |
| 0x806e9    | 10        | 0.5%    |
| 0x40651    | 10        | 0.5%    |
| 0x0a404101 | 10        | 0.5%    |
| 0x706e5    | 8         | 0.4%    |
| 0x08600104 | 8         | 0.4%    |
| 0x706a8    | 7         | 0.35%   |
| 0x306d4    | 6         | 0.3%    |
| 0x1067a    | 6         | 0.3%    |
| 0x906ec    | 5         | 0.25%   |
| 0x806eb    | 5         | 0.25%   |
| 0x90672    | 4         | 0.2%    |
| 0x0a404102 | 4         | 0.2%    |
| 0x08701013 | 4         | 0.2%    |
| 0xa0660    | 3         | 0.15%   |
| 0x906ed    | 3         | 0.15%   |
| 0x806c2    | 3         | 0.15%   |
| 0x50657    | 3         | 0.15%   |
| 0x0a50000d | 3         | 0.15%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 306       | 15.38%  |
| Zen 3            | 192       | 9.65%   |
| Unknown          | 173       | 8.69%   |
| Haswell          | 167       | 8.39%   |
| Zen 2            | 142       | 7.14%   |
| IvyBridge        | 105       | 5.28%   |
| Skylake          | 102       | 5.13%   |
| SandyBridge      | 102       | 5.13%   |
| TigerLake        | 98        | 4.92%   |
| Zen+             | 95        | 4.77%   |
| CometLake        | 65        | 3.27%   |
| Penryn           | 57        | 2.86%   |
| Broadwell        | 50        | 2.51%   |
| Icelake          | 44        | 2.21%   |
| Zen              | 41        | 2.06%   |
| Westmere         | 38        | 1.91%   |
| Piledriver       | 35        | 1.76%   |
| Alderlake Hybrid | 33        | 1.66%   |
| Silvermont       | 21        | 1.06%   |
| Nehalem          | 20        | 1.01%   |
| K10              | 19        | 0.95%   |
| Goldmont plus    | 19        | 0.95%   |
| Excavator        | 16        | 0.8%    |
| Puma             | 11        | 0.55%   |
| Core             | 11        | 0.55%   |
| Steamroller      | 9         | 0.45%   |
| K10 Llano        | 6         | 0.3%    |
| Goldmont         | 4         | 0.2%    |
| K8 Hammer        | 3         | 0.15%   |
| NetBurst         | 2         | 0.1%    |
| Jaguar           | 2         | 0.1%    |
| Tremont          | 1         | 0.05%   |
| Bobcat           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1021      | 41.95%  |
| Nvidia                     | 778       | 31.96%  |
| AMD                        | 631       | 25.92%  |
| Matrox Electronics Systems | 4         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 90        | 3.61%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 82        | 3.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 71        | 2.85%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 62        | 2.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 58        | 2.33%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 57        | 2.29%   |
| AMD Renoir                                                                  | 56        | 2.25%   |
| Intel UHD Graphics 620                                                      | 51        | 2.05%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 47        | 1.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 45        | 1.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 44        | 1.77%   |
| AMD Lucienne                                                                | 44        | 1.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 38        | 1.53%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 38        | 1.53%   |
| Intel HD Graphics 620                                                       | 36        | 1.45%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 34        | 1.36%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 34        | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 32        | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 32        | 1.28%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 32        | 1.28%   |
| Intel HD Graphics 5500                                                      | 29        | 1.16%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 27        | 1.08%   |
| Intel HD Graphics 630                                                       | 26        | 1.04%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 25        | 1%      |
| Intel Core Processor Integrated Graphics Controller                         | 24        | 0.96%   |
| AMD Rembrandt [Radeon 680M]                                                 | 24        | 0.96%   |
| Intel HD Graphics 530                                                       | 23        | 0.92%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 22        | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 21        | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21        | 0.84%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 21        | 0.84%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 19        | 0.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 17        | 0.68%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 17        | 0.68%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 17        | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 16        | 0.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 16        | 0.64%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 15        | 0.6%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                | 15        | 0.6%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 15        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 669       | 33.45%  |
| 1 x AMD              | 472       | 23.6%   |
| 1 x Nvidia           | 389       | 19.45%  |
| Intel + Nvidia       | 291       | 14.55%  |
| AMD + Nvidia         | 84        | 4.2%    |
| Intel + AMD          | 38        | 1.9%    |
| 2 x AMD              | 37        | 1.85%   |
| 2 x Nvidia           | 9         | 0.45%   |
| 1 x Matrox           | 4         | 0.2%    |
| Other                | 3         | 0.15%   |
| Intel + 2 x Nvidia   | 2         | 0.1%    |
| 2 x AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + 2 x Nvidia     | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1318      | 65.83%  |
| Proprietary | 636       | 31.77%  |
| Unknown     | 48        | 2.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1593      | 78.94%  |
| 7.01-8.0   | 89        | 4.41%   |
| 1.01-2.0   | 74        | 3.67%   |
| 0.01-0.5   | 67        | 3.32%   |
| 3.01-4.0   | 65        | 3.22%   |
| 5.01-6.0   | 56        | 2.78%   |
| 8.01-16.0  | 43        | 2.13%   |
| 0.51-1.0   | 15        | 0.74%   |
| 2.01-3.0   | 12        | 0.59%   |
| 16.01-24.0 | 3         | 0.15%   |
| 32.01-64.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 279       | 12.11%  |
| Samsung Electronics     | 255       | 11.07%  |
| BOE                     | 221       | 9.59%   |
| Chimei Innolux          | 200       | 8.68%   |
| LG Display              | 195       | 8.46%   |
| Goldstar                | 155       | 6.73%   |
| Dell                    | 146       | 6.34%   |
| Apple                   | 76        | 3.3%    |
| Acer                    | 70        | 3.04%   |
| Hewlett-Packard         | 65        | 2.82%   |
| AOC                     | 57        | 2.47%   |
| Sharp                   | 52        | 2.26%   |
| ASUSTek Computer        | 51        | 2.21%   |
| Ancor Communications    | 47        | 2.04%   |
| BenQ                    | 44        | 1.91%   |
| PANDA                   | 40        | 1.74%   |
| Lenovo                  | 40        | 1.74%   |
| Philips                 | 28        | 1.22%   |
| InfoVision              | 18        | 0.78%   |
| MSI                     | 17        | 0.74%   |
| Iiyama                  | 15        | 0.65%   |
| ViewSonic               | 14        | 0.61%   |
| CSO                     | 14        | 0.61%   |
| Sony                    | 11        | 0.48%   |
| Chi Mei Optoelectronics | 11        | 0.48%   |
| Sceptre Tech            | 10        | 0.43%   |
| Panasonic               | 9         | 0.39%   |
| NEC Computers           | 8         | 0.35%   |
| Gigabyte Technology     | 8         | 0.35%   |
| TMX                     | 7         | 0.3%    |
| Vizio                   | 6         | 0.26%   |
| Unknown                 | 6         | 0.26%   |
| Vestel Elektronik       | 5         | 0.22%   |
| Eizo                    | 5         | 0.22%   |
| Viotek                  | 4         | 0.17%   |
| Toshiba                 | 4         | 0.17%   |
| Hitachi                 | 4         | 0.17%   |
| Valve                   | 3         | 0.13%   |
| Pioneer                 | 3         | 0.13%   |
| ONN                     | 3         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 15        | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 15        | 0.63%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 13        | 0.55%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 12        | 0.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 11        | 0.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 10        | 0.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 9         | 0.38%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.34%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 8         | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 7         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 7         | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 7         | 0.3%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 6         | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 6         | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 6         | 0.25%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 6         | 0.25%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x194mm 15.5-inch        | 6         | 0.25%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 6         | 0.25%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 5         | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 5         | 0.21%   |
| Samsung Electronics LC49G95T SAM7053 3840x1080 1193x336mm 48.8-inch   | 5         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.21%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 5         | 0.21%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 5         | 0.21%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 5         | 0.21%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5         | 0.21%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 5         | 0.21%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 5         | 0.21%   |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                     | 5         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.21%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 5         | 0.21%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 5         | 0.21%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 5         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1048      | 48.12%  |
| 1366x768 (WXGA)    | 293       | 13.45%  |
| 3840x2160 (4K)     | 179       | 8.22%   |
| 2560x1440 (QHD)    | 148       | 6.8%    |
| 1920x1200 (WUXGA)  | 70        | 3.21%   |
| 1600x900 (HD+)     | 64        | 2.94%   |
| 3440x1440          | 48        | 2.2%    |
| 2560x1080          | 41        | 1.88%   |
| 2560x1600          | 39        | 1.79%   |
| 1440x900 (WXGA+)   | 36        | 1.65%   |
| 1280x1024 (SXGA)   | 29        | 1.33%   |
| 1680x1050 (WSXGA+) | 28        | 1.29%   |
| 2880x1800          | 25        | 1.15%   |
| 1280x800 (WXGA)    | 20        | 0.92%   |
| 3840x1080          | 13        | 0.6%    |
| 3840x2400          | 9         | 0.41%   |
| 1920x540           | 9         | 0.41%   |
| 1360x768           | 9         | 0.41%   |
| 2160x1440          | 8         | 0.37%   |
| 2256x1504          | 7         | 0.32%   |
| 3840x1600          | 5         | 0.23%   |
| 3456x2160          | 4         | 0.18%   |
| 3200x2000          | 4         | 0.18%   |
| 3200x1800 (QHD+)   | 4         | 0.18%   |
| 1600x1200          | 4         | 0.18%   |
| 1024x768 (XGA)     | 4         | 0.18%   |
| Unknown            | 4         | 0.18%   |
| 3000x2000          | 3         | 0.14%   |
| 2736x1824          | 3         | 0.14%   |
| 1280x720 (HD)      | 3         | 0.14%   |
| 800x1280           | 2         | 0.09%   |
| 3840x1100          | 2         | 0.09%   |
| 1920x1280          | 2         | 0.09%   |
| 3840x1200          | 1         | 0.05%   |
| 3280x1080          | 1         | 0.05%   |
| 3120x2080          | 1         | 0.05%   |
| 3072x1920          | 1         | 0.05%   |
| 3040x900           | 1         | 0.05%   |
| 2880x1600          | 1         | 0.05%   |
| 2560x1700          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 586       | 25.41%  |
| 13      | 265       | 11.49%  |
| 27      | 205       | 8.89%   |
| 14      | 171       | 7.42%   |
| 24      | 168       | 7.29%   |
| 23      | 146       | 6.33%   |
| 17      | 110       | 4.77%   |
| 21      | 94        | 4.08%   |
| 31      | 88        | 3.82%   |
| 34      | 82        | 3.56%   |
| 12      | 38        | 1.65%   |
| 19      | 35        | 1.52%   |
| Unknown | 35        | 1.52%   |
| 16      | 32        | 1.39%   |
| 32      | 26        | 1.13%   |
| 22      | 22        | 0.95%   |
| 18      | 22        | 0.95%   |
| 84      | 21        | 0.91%   |
| 20      | 18        | 0.78%   |
| 72      | 16        | 0.69%   |
| 48      | 13        | 0.56%   |
| 11      | 13        | 0.56%   |
| 28      | 10        | 0.43%   |
| 40      | 9         | 0.39%   |
| 25      | 9         | 0.39%   |
| 54      | 7         | 0.3%    |
| 37      | 7         | 0.3%    |
| 35      | 7         | 0.3%    |
| 26      | 7         | 0.3%    |
| 49      | 4         | 0.17%   |
| 47      | 4         | 0.17%   |
| 46      | 4         | 0.17%   |
| 33      | 4         | 0.17%   |
| 29      | 4         | 0.17%   |
| 65      | 3         | 0.13%   |
| 42      | 3         | 0.13%   |
| 75      | 2         | 0.09%   |
| 57      | 2         | 0.09%   |
| 52      | 2         | 0.09%   |
| 44      | 2         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 913       | 40.45%  |
| 501-600     | 469       | 20.78%  |
| 201-300     | 193       | 8.55%   |
| 401-500     | 170       | 7.53%   |
| 601-700     | 129       | 5.72%   |
| 351-400     | 123       | 5.45%   |
| 701-800     | 112       | 4.96%   |
| 1501-2000   | 41        | 1.82%   |
| 1001-1500   | 41        | 1.82%   |
| Unknown     | 35        | 1.55%   |
| 801-900     | 25        | 1.11%   |
| 901-1000    | 5         | 0.22%   |
| 1-100       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1588      | 77.77%  |
| 16/10   | 248       | 12.14%  |
| 21/9    | 97        | 4.75%   |
| 5/4     | 31        | 1.52%   |
| 3/2     | 25        | 1.22%   |
| 32/9    | 17        | 0.83%   |
| Unknown | 16        | 0.78%   |
| 4/3     | 12        | 0.59%   |
| 3.40    | 2         | 0.1%    |
| 6/5     | 1         | 0.05%   |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 0.67    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 586       | 25.78%  |
| 81-90          | 332       | 14.61%  |
| 201-250        | 329       | 14.47%  |
| 301-350        | 211       | 9.28%   |
| 351-500        | 209       | 9.19%   |
| 71-80          | 106       | 4.66%   |
| 121-130        | 89        | 3.92%   |
| 151-200        | 78        | 3.43%   |
| 251-300        | 71        | 3.12%   |
| More than 1000 | 59        | 2.6%    |
| 501-1000       | 45        | 1.98%   |
| 141-150        | 36        | 1.58%   |
| Unknown        | 35        | 1.54%   |
| 61-70          | 30        | 1.32%   |
| 111-120        | 29        | 1.28%   |
| 51-60          | 15        | 0.66%   |
| 131-140        | 6         | 0.26%   |
| 91-100         | 6         | 0.26%   |
| 1-40           | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 704       | 31.99%  |
| 51-100        | 651       | 29.58%  |
| 101-120       | 498       | 22.63%  |
| 161-240       | 194       | 8.81%   |
| More than 240 | 70        | 3.18%   |
| 1-50          | 49        | 2.23%   |
| Unknown       | 35        | 1.59%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1524      | 75.75%  |
| 2     | 363       | 18.04%  |
| 0     | 63        | 3.13%   |
| 3     | 56        | 2.78%   |
| 4     | 5         | 0.25%   |
| 6     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1071      | 35.43%  |
| Intel                             | 1054      | 34.87%  |
| Qualcomm Atheros                  | 297       | 9.82%   |
| Broadcom                          | 158       | 5.23%   |
| MediaTek                          | 81        | 2.68%   |
| Broadcom Limited                  | 54        | 1.79%   |
| TP-Link                           | 32        | 1.06%   |
| Marvell Technology Group          | 24        | 0.79%   |
| ASIX Electronics                  | 22        | 0.73%   |
| Ralink Technology                 | 20        | 0.66%   |
| Nvidia                            | 20        | 0.66%   |
| Samsung Electronics               | 17        | 0.56%   |
| NetGear                           | 14        | 0.46%   |
| DisplayLink                       | 13        | 0.43%   |
| Ralink                            | 12        | 0.4%    |
| Xiaomi                            | 11        | 0.36%   |
| Microsoft                         | 8         | 0.26%   |
| InterBiometrics                   | 8         | 0.26%   |
| Dell                              | 8         | 0.26%   |
| D-Link                            | 8         | 0.26%   |
| Aquantia                          | 8         | 0.26%   |
| Qualcomm                          | 7         | 0.23%   |
| Lenovo                            | 7         | 0.23%   |
| Sierra Wireless                   | 6         | 0.2%    |
| ASUSTek Computer                  | 5         | 0.17%   |
| Qualcomm Atheros Communications   | 4         | 0.13%   |
| JMicron Technology                | 4         | 0.13%   |
| Huawei Technologies               | 4         | 0.13%   |
| Google                            | 4         | 0.13%   |
| OPPO Electronics                  | 3         | 0.1%    |
| Hewlett-Packard                   | 3         | 0.1%    |
| D-Link System                     | 3         | 0.1%    |
| U-Blox                            | 2         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| Mellanox Technologies             | 2         | 0.07%   |
| Ericsson Business Mobile Networks | 2         | 0.07%   |
| Apple                             | 2         | 0.07%   |
| Accton Technology                 | 2         | 0.07%   |
| VIA Technologies                  | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 698       | 19.63%  |
| Intel Wi-Fi 6 AX200                                               | 179       | 5.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 98        | 2.76%   |
| Intel I211 Gigabit Network Connection                             | 87        | 2.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 77        | 2.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 76        | 2.14%   |
| Intel Wi-Fi 6 AX201                                               | 74        | 2.08%   |
| Intel Ethernet Controller I225-V                                  | 66        | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 58        | 1.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 54        | 1.52%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 52        | 1.46%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 49        | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 46        | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 43        | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 43        | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 42        | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 41        | 1.15%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 40        | 1.12%   |
| Intel Wireless 7265                                               | 39        | 1.1%    |
| Intel Wireless 8260                                               | 38        | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 37        | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 37        | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 35        | 0.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 34        | 0.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 33        | 0.93%   |
| Intel Wireless 7260                                               | 32        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 30        | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 28        | 0.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 28        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 26        | 0.73%   |
| Intel Wireless-AC 9260                                            | 26        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 0.7%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 24        | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 23        | 0.65%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 22        | 0.62%   |
| Realtek 802.11ac NIC                                              | 19        | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                     | 18        | 0.51%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.51%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 17        | 0.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 16        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 866       | 49.26%  |
| Realtek Semiconductor                 | 265       | 15.07%  |
| Qualcomm Atheros                      | 238       | 13.54%  |
| Broadcom                              | 124       | 7.05%   |
| MediaTek                              | 80        | 4.55%   |
| Broadcom Limited                      | 45        | 2.56%   |
| TP-Link                               | 26        | 1.48%   |
| Ralink Technology                     | 20        | 1.14%   |
| NetGear                               | 14        | 0.8%    |
| Ralink                                | 12        | 0.68%   |
| Microsoft                             | 8         | 0.46%   |
| Marvell Technology Group              | 8         | 0.46%   |
| Dell                                  | 8         | 0.46%   |
| D-Link                                | 7         | 0.4%    |
| Sierra Wireless                       | 6         | 0.34%   |
| Qualcomm                              | 6         | 0.34%   |
| Qualcomm Atheros Communications       | 4         | 0.23%   |
| ASUSTek Computer                      | 4         | 0.23%   |
| D-Link System                         | 3         | 0.17%   |
| Accton Technology                     | 2         | 0.11%   |
| Sitecom Europe                        | 1         | 0.06%   |
| Micro Star International              | 1         | 0.06%   |
| Linksys                               | 1         | 0.06%   |
| IMC Networks                          | 1         | 0.06%   |
| Hewlett-Packard                       | 1         | 0.06%   |
| Gemtek                                | 1         | 0.06%   |
| Fibocom                               | 1         | 0.06%   |
| Edimax Technology                     | 1         | 0.06%   |
| Belkin Components                     | 1         | 0.06%   |
| AVM                                   | 1         | 0.06%   |
| Arduino SA                            | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 179       | 10.1%   |
| Intel Wi-Fi 6 AX201                                            | 74        | 4.18%   |
| Intel Wireless 8265 / 8275                                     | 58        | 3.27%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 52        | 2.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 49        | 2.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 46        | 2.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 43        | 2.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 43        | 2.43%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 42        | 2.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 41        | 2.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 40        | 2.26%   |
| Intel Wireless 7265                                            | 39        | 2.2%    |
| Intel Wireless 8260                                            | 38        | 2.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 37        | 2.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 37        | 2.09%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 35        | 1.98%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 34        | 1.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 33        | 1.86%   |
| Intel Wireless 7260                                            | 32        | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 30        | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 28        | 1.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 26        | 1.47%   |
| Intel Wireless-AC 9260                                         | 26        | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 24        | 1.35%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 23        | 1.3%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 22        | 1.24%   |
| Realtek 802.11ac NIC                                           | 19        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                  | 18        | 1.02%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 17        | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 16        | 0.9%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 0.9%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 15        | 0.85%   |
| Realtek Realtek Network controller                             | 15        | 0.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 14        | 0.79%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 0.73%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 13        | 0.73%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 12        | 0.68%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 12        | 0.68%   |
| Intel Wireless 3165                                            | 11        | 0.62%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 11        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 950       | 55.14%  |
| Intel                         | 474       | 27.51%  |
| Qualcomm Atheros              | 80        | 4.64%   |
| Broadcom                      | 63        | 3.66%   |
| ASIX Electronics              | 22        | 1.28%   |
| Nvidia                        | 20        | 1.16%   |
| Samsung Electronics           | 17        | 0.99%   |
| Marvell Technology Group      | 16        | 0.93%   |
| DisplayLink                   | 13        | 0.75%   |
| Xiaomi                        | 11        | 0.64%   |
| Broadcom Limited              | 9         | 0.52%   |
| Aquantia                      | 8         | 0.46%   |
| Lenovo                        | 7         | 0.41%   |
| TP-Link                       | 6         | 0.35%   |
| JMicron Technology            | 4         | 0.23%   |
| Google                        | 4         | 0.23%   |
| OPPO Electronics              | 3         | 0.17%   |
| Huawei Technologies           | 3         | 0.17%   |
| OnePlus Technology (Shenzhen) | 2         | 0.12%   |
| Motorola PCS                  | 2         | 0.12%   |
| Mellanox Technologies         | 2         | 0.12%   |
| Apple                         | 2         | 0.12%   |
| VIA Technologies              | 1         | 0.06%   |
| Qualcomm                      | 1         | 0.06%   |
| Hewlett-Packard               | 1         | 0.06%   |
| D-Link                        | 1         | 0.06%   |
| ASUSTek Computer              | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 698       | 39.66%  |
| Realtek RTL8125 2.5GbE Controller                                 | 98        | 5.57%   |
| Intel I211 Gigabit Network Connection                             | 87        | 4.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 77        | 4.38%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 76        | 4.32%   |
| Intel Ethernet Controller I225-V                                  | 66        | 3.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 54        | 3.07%   |
| Intel Ethernet Connection I217-LM                                 | 28        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                              | 25        | 1.42%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 1.02%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 0.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 13        | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.74%   |
| Nvidia MCP79 Ethernet                                             | 12        | 0.68%   |
| Intel Ethernet Connection (2) I218-V                              | 12        | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 9         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 9         | 0.51%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 8         | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.4%    |
| Intel Ethernet Connection I219-V                                  | 7         | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 6         | 0.34%   |
| Intel I210 Gigabit Network Connection                             | 6         | 0.34%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.34%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 6         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1674      | 50.6%   |
| Ethernet | 1610      | 48.67%  |
| Modem    | 18        | 0.54%   |
| Unknown  | 6         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1305      | 62.32%  |
| Ethernet | 789       | 37.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1098      | 55.2%   |
| 1     | 808       | 40.62%  |
| 3     | 58        | 2.92%   |
| 0     | 21        | 1.06%   |
| 4     | 4         | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1393      | 69.62%  |
| Yes  | 608       | 30.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 782       | 53.67%  |
| Realtek Semiconductor           | 124       | 8.51%   |
| Qualcomm Atheros Communications | 103       | 7.07%   |
| Apple                           | 91        | 6.25%   |
| IMC Networks                    | 71        | 4.87%   |
| Cambridge Silicon Radio         | 65        | 4.46%   |
| Foxconn / Hon Hai               | 49        | 3.36%   |
| Lite-On Technology              | 42        | 2.88%   |
| Broadcom                        | 35        | 2.4%    |
| ASUSTek Computer                | 18        | 1.24%   |
| MediaTek                        | 11        | 0.75%   |
| Toshiba                         | 8         | 0.55%   |
| Marvell Semiconductor           | 8         | 0.55%   |
| Dell                            | 8         | 0.55%   |
| Realtek                         | 7         | 0.48%   |
| Hewlett-Packard                 | 6         | 0.41%   |
| TP-Link                         | 4         | 0.27%   |
| Opticis                         | 3         | 0.21%   |
| Foxconn International           | 3         | 0.21%   |
| Dynex                           | 3         | 0.21%   |
| Taiyo Yuden                     | 2         | 0.14%   |
| Ralink                          | 2         | 0.14%   |
| Micro Star International        | 2         | 0.14%   |
| USI                             | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |
| SIN                             | 1         | 0.07%   |
| Ralink Technology               | 1         | 0.07%   |
| Integrated System Solution      | 1         | 0.07%   |
| HTC (High Tech Computer)        | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |
| Actions                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                              | 222       | 15.23%  |
| Intel Bluetooth wireless interface                  | 176       | 12.07%  |
| Intel AX200 Bluetooth                               | 169       | 11.59%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 96        | 6.58%   |
| Realtek Bluetooth Radio                             | 90        | 6.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 65        | 4.46%   |
| Qualcomm Atheros  Bluetooth Device                  | 57        | 3.91%   |
| Apple Bluetooth USB Host Controller                 | 38        | 2.61%   |
| Apple Bluetooth Host Controller                     | 38        | 2.61%   |
| Intel AX210 Bluetooth                               | 36        | 2.47%   |
| Intel Wireless-AC 3168 Bluetooth                    | 35        | 2.4%    |
| IMC Networks Wireless_Device                        | 30        | 2.06%   |
| Realtek  Bluetooth 4.2 Adapter                      | 26        | 1.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 25        | 1.71%   |
| Foxconn / Hon Hai Wireless_Device                   | 23        | 1.58%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 17        | 1.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 0.96%   |
| IMC Networks Bluetooth Radio                        | 14        | 0.96%   |
| IMC Networks Bluetooth Device                       | 14        | 0.96%   |
| Lite-On Bluetooth Device                            | 13        | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 11        | 0.75%   |
| MediaTek Wireless_Device                            | 11        | 0.75%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 10        | 0.69%   |
| Lite-On Wireless_Device                             | 10        | 0.69%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.55%   |
| Realtek Bluetooth Radio                             | 7         | 0.48%   |
| Marvell Bluetooth and Wireless LAN Composite        | 7         | 0.48%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.48%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.48%   |
| Apple Bluetooth HCI                                 | 7         | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 6         | 0.41%   |
| Lite-On Bluetooth Radio                             | 6         | 0.41%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.41%   |
| ASUS ASUS USB-BT500                                 | 6         | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.34%   |
| IMC Networks Bluetooth USB Host Controller          | 5         | 0.34%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.34%   |
| ASUS Bluetooth Radio                                | 5         | 0.34%   |
| TP-Link TPuLink UB500 Adapter                       | 4         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1288      | 42.06%  |
| AMD                                  | 740       | 24.17%  |
| Nvidia                               | 612       | 19.99%  |
| C-Media Electronics                  | 50        | 1.63%   |
| Logitech                             | 33        | 1.08%   |
| Kingston Technology                  | 21        | 0.69%   |
| Razer USA                            | 20        | 0.65%   |
| JMTek                                | 19        | 0.62%   |
| Focusrite-Novation                   | 17        | 0.56%   |
| ASUSTek Computer                     | 16        | 0.52%   |
| Creative Labs                        | 15        | 0.49%   |
| Texas Instruments                    | 12        | 0.39%   |
| GN Netcom                            | 12        | 0.39%   |
| Generalplus Technology               | 12        | 0.39%   |
| Micro Star International             | 11        | 0.36%   |
| Lenovo                               | 10        | 0.33%   |
| Corsair                              | 10        | 0.33%   |
| SteelSeries ApS                      | 9         | 0.29%   |
| Realtek Semiconductor                | 9         | 0.29%   |
| Sony                                 | 8         | 0.26%   |
| Hewlett-Packard                      | 8         | 0.26%   |
| Blue Microphones                     | 7         | 0.23%   |
| Creative Technology                  | 6         | 0.2%    |
| Apple                                | 5         | 0.16%   |
| Tenx Technology                      | 4         | 0.13%   |
| Plantronics                          | 4         | 0.13%   |
| FiiO Electronics Technology          | 4         | 0.13%   |
| Astro Gaming                         | 4         | 0.13%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.1%    |
| Mackie Designs                       | 3         | 0.1%    |
| Jieli Technology                     | 3         | 0.1%    |
| DSEA A/S                             | 3         | 0.1%    |
| Antlion Audio                        | 3         | 0.1%    |
| Yamaha                               | 2         | 0.07%   |
| Valve Software                       | 2         | 0.07%   |
| Turtle Beach                         | 2         | 0.07%   |
| Trust                                | 2         | 0.07%   |
| Sennheiser Communications            | 2         | 0.07%   |
| SAVITECH                             | 2         | 0.07%   |
| Samsung Electronics                  | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 304       | 8.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 178       | 4.8%    |
| AMD Starship/Matisse HD Audio Controller                                   | 169       | 4.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 139       | 3.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 104       | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 98        | 2.64%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 89        | 2.4%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 86        | 2.32%   |
| Intel Cannon Lake PCH cAVS                                                 | 78        | 2.1%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 76        | 2.05%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 69        | 1.86%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 61        | 1.64%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 59        | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 57        | 1.54%   |
| Intel Haswell-ULT HD Audio Controller                                      | 57        | 1.54%   |
| Nvidia GA104 High Definition Audio Controller                              | 56        | 1.51%   |
| Intel 8 Series HD Audio Controller                                         | 56        | 1.51%   |
| Nvidia GA106 High Definition Audio Controller                              | 53        | 1.43%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 52        | 1.4%    |
| Nvidia TU116 High Definition Audio Controller                              | 50        | 1.35%   |
| Intel Comet Lake PCH cAVS                                                  | 50        | 1.35%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 47        | 1.27%   |
| Intel Broadwell-U Audio Controller                                         | 46        | 1.24%   |
| Nvidia TU106 High Definition Audio Controller                              | 45        | 1.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 45        | 1.21%   |
| Nvidia GP107GL High Definition Audio Controller                            | 44        | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 44        | 1.19%   |
| AMD FCH Azalia Controller                                                  | 41        | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 40        | 1.08%   |
| Nvidia GP104 High Definition Audio Controller                              | 40        | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 40        | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                              | 39        | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                               | 37        | 1%      |
| AMD SBx00 Azalia (Intel HDA)                                               | 34        | 0.92%   |
| Intel 200 Series PCH HD Audio                                              | 33        | 0.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 32        | 0.86%   |
| Intel CM238 HD Audio Controller                                            | 30        | 0.81%   |
| Nvidia TU104 HD Audio Controller                                           | 29        | 0.78%   |
| Nvidia Audio device                                                        | 29        | 0.78%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 27        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 163       | 26%     |
| SK hynix                     | 114       | 18.18%  |
| Micron Technology            | 83        | 13.24%  |
| Kingston                     | 51        | 8.13%   |
| Corsair                      | 44        | 7.02%   |
| Crucial                      | 35        | 5.58%   |
| G.Skill                      | 25        | 3.99%   |
| Unknown                      | 19        | 3.03%   |
| Team                         | 16        | 2.55%   |
| Unknown                      | 12        | 1.91%   |
| A-DATA Technology            | 10        | 1.59%   |
| Smart                        | 6         | 0.96%   |
| Neo Forza                    | 6         | 0.96%   |
| Goldkey                      | 6         | 0.96%   |
| Unknown (ABCD)               | 4         | 0.64%   |
| Elpida                       | 4         | 0.64%   |
| Ramaxel Technology           | 3         | 0.48%   |
| PNY                          | 3         | 0.48%   |
| Nanya Technology             | 3         | 0.48%   |
| Avant                        | 3         | 0.48%   |
| Teikon                       | 2         | 0.32%   |
| Smart Brazil                 | 2         | 0.32%   |
| GSkill                       | 2         | 0.32%   |
| Gold Key                     | 2         | 0.32%   |
| Unknown (8A02)               | 1         | 0.16%   |
| Transcend                    | 1         | 0.16%   |
| Timetec                      | 1         | 0.16%   |
| Patriot Memory (PDP Systems) | 1         | 0.16%   |
| Patriot Memory               | 1         | 0.16%   |
| Patriot                      | 1         | 0.16%   |
| GeIL                         | 1         | 0.16%   |
| ChangXin Memory              | 1         | 0.16%   |
| Apacer                       | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 1.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.83%   |
| Unknown                                                          | 12        | 1.83%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.37%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 1.22%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 1.22%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 8         | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 6         | 0.91%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.91%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.91%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 6         | 0.91%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.91%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 6         | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8192MB SODIMM DDR4 3200MT/s          | 6         | 0.91%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 6         | 0.91%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s              | 5         | 0.76%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 5         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.76%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.76%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.76%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.76%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.76%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.61%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.61%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.61%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 4         | 0.61%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.61%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.61%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 4         | 0.61%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.61%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.46%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.46%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.46%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.46%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.46%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.46%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 376       | 68.86%  |
| DDR3    | 74        | 13.55%  |
| LPDDR4  | 36        | 6.59%   |
| DDR5    | 19        | 3.48%   |
| LPDDR3  | 16        | 2.93%   |
| LPDDR5  | 15        | 2.75%   |
| DDR2    | 5         | 0.92%   |
| SDRAM   | 3         | 0.55%   |
| Unknown | 2         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 347       | 62.3%   |
| DIMM         | 122       | 21.9%   |
| Row Of Chips | 85        | 15.26%  |
| Chip         | 3         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 278       | 47.52%  |
| 4096  | 119       | 20.34%  |
| 16384 | 117       | 20%     |
| 32768 | 39        | 6.67%   |
| 2048  | 29        | 4.96%   |
| 1024  | 3         | 0.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 184       | 31.56%  |
| 2667  | 95        | 16.3%   |
| 1600  | 53        | 9.09%   |
| 2400  | 38        | 6.52%   |
| 3600  | 30        | 5.15%   |
| 2133  | 25        | 4.29%   |
| 4267  | 22        | 3.77%   |
| 4800  | 18        | 3.09%   |
| 6400  | 16        | 2.74%   |
| 1333  | 12        | 2.06%   |
| 3733  | 7         | 1.2%    |
| 3466  | 7         | 1.2%    |
| 8400  | 6         | 1.03%   |
| 3800  | 6         | 1.03%   |
| 3266  | 6         | 1.03%   |
| 1334  | 6         | 1.03%   |
| 3000  | 5         | 0.86%   |
| 2933  | 5         | 0.86%   |
| 1867  | 5         | 0.86%   |
| 1067  | 5         | 0.86%   |
| 800   | 5         | 0.86%   |
| 4266  | 4         | 0.69%   |
| 3400  | 3         | 0.51%   |
| 3866  | 2         | 0.34%   |
| 3333  | 2         | 0.34%   |
| 3100  | 2         | 0.34%   |
| 2800  | 2         | 0.34%   |
| 2666  | 2         | 0.34%   |
| 2048  | 2         | 0.34%   |
| 1866  | 2         | 0.34%   |
| 4199  | 1         | 0.17%   |
| 4000  | 1         | 0.17%   |
| 3666  | 1         | 0.17%   |
| 3066  | 1         | 0.17%   |
| 2733  | 1         | 0.17%   |
| 1200  | 1         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 28.57%  |
| Brother Industries  | 8         | 22.86%  |
| Canon               | 7         | 20%     |
| Samsung Electronics | 3         | 8.57%   |
| Seiko Epson         | 2         | 5.71%   |
| Xerox               | 1         | 2.86%   |
| QinHeng Electronics | 1         | 2.86%   |
| Prolific Technology | 1         | 2.86%   |
| ICS Advent          | 1         | 2.86%   |
| Dymo-CoStar         | 1         | 2.86%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Brother HL-2130 series                 | 3         | 8.33%   |
| Xerox B215                             | 1         | 2.78%   |
| Seiko Epson WF-4830 Series             | 1         | 2.78%   |
| Seiko Epson ET-2800 Series             | 1         | 2.78%   |
| Samsung SCX-3400 Series                | 1         | 2.78%   |
| Samsung ML-191x/ML-252x Laser Printer  | 1         | 2.78%   |
| Samsung M2070 Series                   | 1         | 2.78%   |
| QinHeng CH340S                         | 1         | 2.78%   |
| Prolific PL2305 Parallel Port          | 1         | 2.78%   |
| ICS Advent Parallel Adapter            | 1         | 2.78%   |
| HP PSC-1315/PSC-1317                   | 1         | 2.78%   |
| HP OfficeJet Pro 9010 series           | 1         | 2.78%   |
| HP LaserJet Professional P1102w        | 1         | 2.78%   |
| HP LaserJet P2035                      | 1         | 2.78%   |
| HP LaserJet 3050                       | 1         | 2.78%   |
| HP LaserJet 1010                       | 1         | 2.78%   |
| HP Ink Tank Wireless 410 series        | 1         | 2.78%   |
| HP ENVY Pro 6400 series                | 1         | 2.78%   |
| HP ENVY 5000 series                    | 1         | 2.78%   |
| HP Color LaserJet CP2025dn             | 1         | 2.78%   |
| Dymo-CoStar DYMO LabelWriter 4XL       | 1         | 2.78%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 2.78%   |
| Canon TS9100 series                    | 1         | 2.78%   |
| Canon TR8500 series                    | 1         | 2.78%   |
| Canon Pro9000II series                 | 1         | 2.78%   |
| Canon PIXMA MX920 Series               | 1         | 2.78%   |
| Canon PIXMA MP240                      | 1         | 2.78%   |
| Canon PIXMA MG2500 Series              | 1         | 2.78%   |
| Canon E400 series                      | 1         | 2.78%   |
| Brother MFC-L2700DW                    | 1         | 2.78%   |
| Brother MFC-5440CN                     | 1         | 2.78%   |
| Brother HL-L2370DW series              | 1         | 2.78%   |
| Brother HL-3140CW series               | 1         | 2.78%   |
| Brother HL-2270DW Laser Printer        | 1         | 2.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 3         | 75%     |
| Mustek Systems | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB | 1         | 25%     |
| Canon CanoScan N650U/N656U         | 1         | 25%     |
| Canon CanoScan LiDE 60             | 1         | 25%     |
| Canon CanoScan LiDE 200            | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 255       | 19.39%  |
| Acer                                   | 127       | 9.66%   |
| IMC Networks                           | 122       | 9.28%   |
| Microdia                               | 120       | 9.13%   |
| Realtek Semiconductor                  | 98        | 7.45%   |
| Logitech                               | 84        | 6.39%   |
| Quanta                                 | 72        | 5.48%   |
| Apple                                  | 69        | 5.25%   |
| Sunplus Innovation Technology          | 63        | 4.79%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 2.66%   |
| Syntek                                 | 32        | 2.43%   |
| Luxvisions Innotech Limited            | 29        | 2.21%   |
| Suyin                                  | 21        | 1.6%    |
| Lite-On Technology                     | 21        | 1.6%    |
| Microsoft                              | 19        | 1.44%   |
| Sonix Technology                       | 13        | 0.99%   |
| Samsung Electronics                    | 13        | 0.99%   |
| SunplusIT                              | 12        | 0.91%   |
| Silicon Motion                         | 12        | 0.91%   |
| Razer USA                              | 8         | 0.61%   |
| Z-Star Microelectronics                | 6         | 0.46%   |
| MacroSilicon                           | 5         | 0.38%   |
| Jieli Technology                       | 5         | 0.38%   |
| Generalplus Technology                 | 5         | 0.38%   |
| ARC International                      | 5         | 0.38%   |
| LG Electronics                         | 4         | 0.3%    |
| Alcor Micro                            | 4         | 0.3%    |
| Ricoh                                  | 3         | 0.23%   |
| Primax Electronics                     | 3         | 0.23%   |
| Cubeternet                             | 3         | 0.23%   |
| Creative Technology                    | 3         | 0.23%   |
| AVerMedia Technologies                 | 3         | 0.23%   |
| Valve Software                         | 2         | 0.15%   |
| Unknown                                | 2         | 0.15%   |
| Sunplus IT                             | 2         | 0.15%   |
| Lenovo                                 | 2         | 0.15%   |
| KYE Systems (Mouse Systems)            | 2         | 0.15%   |
| icSpring                               | 2         | 0.15%   |
| HRY                                    | 2         | 0.15%   |
| Xiaomi                                 | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 53        | 3.99%   |
| Chicony Integrated Camera                | 52        | 3.92%   |
| IMC Networks USB2.0 HD UVC WebCam        | 48        | 3.61%   |
| Realtek Integrated_Webcam_HD             | 40        | 3.01%   |
| IMC Networks Integrated Camera           | 30        | 2.26%   |
| Chicony HD WebCam                        | 27        | 2.03%   |
| Acer Integrated Camera                   | 27        | 2.03%   |
| Syntek Integrated Camera                 | 25        | 1.88%   |
| Logitech Webcam C270                     | 22        | 1.66%   |
| Chicony USB2.0 Camera                    | 22        | 1.66%   |
| Acer BisonCam,NB Pro                     | 22        | 1.66%   |
| Apple Built-in iSight                    | 21        | 1.58%   |
| Acer HD Webcam                           | 21        | 1.58%   |
| Apple iPhone 5/5C/5S/6/SE                | 20        | 1.51%   |
| Quanta HD User Facing                    | 16        | 1.2%    |
| Apple FaceTime HD Camera (Built-in)      | 16        | 1.2%    |
| Sunplus Integrated_Webcam_HD             | 15        | 1.13%   |
| Samsung Galaxy A5 (MTP)                  | 13        | 0.98%   |
| Quanta HP HD Camera                      | 13        | 0.98%   |
| Microdia USB 2.0 Camera                  | 13        | 0.98%   |
| Logitech HD Pro Webcam C920              | 13        | 0.98%   |
| Microdia Integrated Webcam               | 11        | 0.83%   |
| Chicony USB2.0 VGA UVC WebCam            | 11        | 0.83%   |
| Chicony HP HD Camera                     | 11        | 0.83%   |
| Chicony HD User Facing                   | 11        | 0.83%   |
| Apple FaceTime HD Camera                 | 11        | 0.83%   |
| Sonix USB2.0 HD UVC WebCam               | 10        | 0.75%   |
| Logitech C922 Pro Stream Webcam          | 10        | 0.75%   |
| Chicony Integrated Camera (1280x720@30)  | 10        | 0.75%   |
| Luxvisions Innotech Limited HP HD Camera | 9         | 0.68%   |
| Lite-On Integrated Camera                | 9         | 0.68%   |
| Acer SunplusIT Integrated Camera         | 9         | 0.68%   |
| Acer Lenovo EasyCamera                   | 9         | 0.68%   |
| Microdia Webcam Vitade AF                | 8         | 0.6%    |
| Quanta HP Wide Vision HD Camera          | 7         | 0.53%   |
| Microdia Integrated_Webcam_FHD           | 7         | 0.53%   |
| Microdia Integrated Webcam HD            | 7         | 0.53%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 7         | 0.53%   |
| Chicony USB 2.0 Camera                   | 7         | 0.53%   |
| Chicony HP Wide Vision HD Camera         | 7         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 87        | 36.71%  |
| Validity Sensors                   | 57        | 24.05%  |
| Shenzhen Goodix Technology         | 48        | 20.25%  |
| LighTuning Technology              | 12        | 5.06%   |
| Elan Microelectronics              | 12        | 5.06%   |
| Upek                               | 6         | 2.53%   |
| AuthenTec                          | 5         | 2.11%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.27%   |
| Focal-systems.Corp                 | 3         | 1.27%   |
| HOLTEK                             | 2         | 0.84%   |
| Samsung Electronics                | 1         | 0.42%   |
| DigitalPersona                     | 1         | 0.42%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 36        | 15.19%  |
| Shenzhen Goodix  Fingerprint Device                                        | 22        | 9.28%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 8.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 6.75%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 5.06%   |
| Shenzhen Goodix FingerPrint                                                | 10        | 4.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 3.8%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 3.8%    |
| Elan ELAN:ARM-M4                                                           | 9         | 3.8%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 2.95%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 2.53%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.11%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 2.11%   |
| Synaptics WBDI Device                                                      | 5         | 2.11%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 2.11%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 2.11%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.69%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.69%   |
| Synaptics  WBDI                                                            | 4         | 1.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.27%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.27%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.27%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.27%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.27%   |
| Elan ELAN:Fingerprint                                                      | 3         | 1.27%   |
| Validity Sensors VFS491                                                    | 2         | 0.84%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.84%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.84%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.84%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.84%   |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 0.84%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.84%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.42%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.42%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.42%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.42%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.42%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.42%   |
| AuthenTec AES2810                                                          | 1         | 0.42%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 38        | 48.1%   |
| Alcor Micro           | 24        | 30.38%  |
| O2 Micro              | 5         | 6.33%   |
| Lenovo                | 4         | 5.06%   |
| Upek                  | 3         | 3.8%    |
| OmniKey               | 2         | 2.53%   |
| SCM Microsystems      | 1         | 1.27%   |
| Clay Logic            | 1         | 1.27%   |
| Advanced Card Systems | 1         | 1.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 30.38%  |
| Broadcom 5880                                                                | 11        | 13.92%  |
| Broadcom 58200                                                               | 11        | 13.92%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 12.66%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 7.59%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 5.06%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 5.06%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 3.8%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.27%   |
| OmniKey CardMan 4321                                                         | 1         | 1.27%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 1.27%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.27%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.27%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 1.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1362      | 67.79%  |
| 1     | 521       | 25.93%  |
| 2     | 106       | 5.28%   |
| 3     | 18        | 0.9%    |
| 4     | 2         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 228       | 29.69%  |
| Multimedia controller    | 115       | 14.97%  |
| Net/wireless             | 112       | 14.58%  |
| Graphics card            | 94        | 12.24%  |
| Chipcard                 | 74        | 9.64%   |
| Bluetooth                | 41        | 5.34%   |
| Camera                   | 24        | 3.13%   |
| Sound                    | 15        | 1.95%   |
| Communication controller | 13        | 1.69%   |
| Net/ethernet             | 12        | 1.56%   |
| Unassigned class         | 10        | 1.3%    |
| Network                  | 9         | 1.17%   |
| Storage                  | 6         | 0.78%   |
| Storage/ide              | 4         | 0.52%   |
| Modem                    | 4         | 0.52%   |
| Card reader              | 4         | 0.52%   |
| Wireless                 | 1         | 0.13%   |
| Storage/raid             | 1         | 0.13%   |
| Storage/nvme             | 1         | 0.13%   |

