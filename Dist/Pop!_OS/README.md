Pop!_OS - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Pop!_OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS/Desktop/README.md) and [notebooks](/Dist/Pop!_OS/Notebook/README.md).

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

Total: 12163

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
| Lenovo        | ThinkPad T460s 20FAS2M30... | Notebook    | [f201c986f0](https://linux-hardware.org/?probe=f201c986f0) | Jan 25, 2023 |
| Dell          | Inspiron 13-7353            | Notebook    | [5ebcba8c52](https://linux-hardware.org/?probe=5ebcba8c52) | Jan 25, 2023 |
| Dell          | Latitude E7240              | Notebook    | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | System Inspiron N7110       | Notebook    | [935a295b28](https://linux-hardware.org/?probe=935a295b28) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | Notebook    | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [10f149abb7](https://linux-hardware.org/?probe=10f149abb7) | Jan 24, 2023 |
| MeLE          | Rev GMLR1                   | Mini pc     | [1f294d6a67](https://linux-hardware.org/?probe=1f294d6a67) | Jan 24, 2023 |
| Dell          | 02P9X9 A00                  | Server      | [be7339e967](https://linux-hardware.org/?probe=be7339e967) | Jan 24, 2023 |
| Acer          | Aspire M3970                | Desktop     | [c822a510e5](https://linux-hardware.org/?probe=c822a510e5) | Jan 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3221475cc8](https://linux-hardware.org/?probe=3221475cc8) | Jan 24, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [1c05334105](https://linux-hardware.org/?probe=1c05334105) | Jan 24, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | Notebook    | [73a0023203](https://linux-hardware.org/?probe=73a0023203) | Jan 24, 2023 |
| Google        | Link                        | Notebook    | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [4f5be0720a](https://linux-hardware.org/?probe=4f5be0720a) | Jan 23, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [c87ce45f84](https://linux-hardware.org/?probe=c87ce45f84) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [f6e09cc9fb](https://linux-hardware.org/?probe=f6e09cc9fb) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [306e6ae925](https://linux-hardware.org/?probe=306e6ae925) | Jan 23, 2023 |
| ASUSTek       | Rampage II GENE             | Desktop     | [112b5304d9](https://linux-hardware.org/?probe=112b5304d9) | Jan 23, 2023 |
| MACHINIST     | X79 Z9-D7 V2.0              | Desktop     | [9d5d06d342](https://linux-hardware.org/?probe=9d5d06d342) | Jan 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [75acbba6b1](https://linux-hardware.org/?probe=75acbba6b1) | Jan 23, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [82b094a66b](https://linux-hardware.org/?probe=82b094a66b) | Jan 23, 2023 |
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
| Lenovo        | ThinkPad T460s 20FAS2M30... | Notebook    | [641654df50](https://linux-hardware.org/?probe=641654df50) | Jan 19, 2023 |
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
| Lenovo        | ThinkPad T460s 20FAS2M30... | Notebook    | [1178b43f82](https://linux-hardware.org/?probe=1178b43f82) | Jan 05, 2023 |
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
| Intel         | DP55WB AAE64798-206         | Desktop     | [2373b5141b](https://linux-hardware.org/?probe=2373b5141b) | Dec 29, 2022 |
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
| Sony          | SVF15213CBB                 | Notebook    | [f8a95f249c](https://linux-hardware.org/?probe=f8a95f249c) | Dec 26, 2022 |
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
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [33fce09f33](https://linux-hardware.org/?probe=33fce09f33) | Dec 20, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [858931394a](https://linux-hardware.org/?probe=858931394a) | Dec 20, 2022 |
| HP            | 18E7                        | Desktop     | [c3b91e80df](https://linux-hardware.org/?probe=c3b91e80df) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [03dfcb8079](https://linux-hardware.org/?probe=03dfcb8079) | Dec 19, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [1f6885ef2f](https://linux-hardware.org/?probe=1f6885ef2f) | Dec 19, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [cdbf94efce](https://linux-hardware.org/?probe=cdbf94efce) | Dec 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c7b01f9875](https://linux-hardware.org/?probe=c7b01f9875) | Dec 19, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c168fe495f](https://linux-hardware.org/?probe=c168fe495f) | Dec 19, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
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
| Intel         | X79M-S                      | Desktop     | [f99b1f2b67](https://linux-hardware.org/?probe=f99b1f2b67) | Dec 16, 2022 |
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
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [30cc472125](https://linux-hardware.org/?probe=30cc472125) | Dec 08, 2022 |
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
| ASUSTek       | PRIME B450M-K               | Desktop     | [7e82777792](https://linux-hardware.org/?probe=7e82777792) | Dec 06, 2022 |
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
| Dell          | Inspiron 7720               | Notebook    | [a75b9a21f9](https://linux-hardware.org/?probe=a75b9a21f9) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [ae4fc56cb3](https://linux-hardware.org/?probe=ae4fc56cb3) | Nov 23, 2022 |
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
| MSI           | 2AE0                        | Desktop     | [cfb41eba48](https://linux-hardware.org/?probe=cfb41eba48) | Nov 19, 2022 |
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
| Positivo      | POS-EIH61CR POSITIVO        | Desktop     | [81bd40e949](https://linux-hardware.org/?probe=81bd40e949) | Nov 10, 2022 |
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
| System76      | Galago Pro                  | Notebook    | [8728b448e9](https://linux-hardware.org/?probe=8728b448e9) | Nov 05, 2022 |
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
| Colorful T... | A320M-K PRO YV14            | Desktop     | [cf54f0dbf3](https://linux-hardware.org/?probe=cf54f0dbf3) | Nov 03, 2022 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [5059f2f52e](https://linux-hardware.org/?probe=5059f2f52e) | Nov 03, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Pop!_OS 20.04 | 2120      | 24.25%  |
| Pop!_OS 22.04 | 1987      | 22.73%  |
| Pop!_OS 21.04 | 1800      | 20.59%  |
| Pop!_OS 20.10 | 1650      | 18.87%  |
| Pop!_OS 21.10 | 1111      | 12.71%  |
| Pop!_OS 19.10 | 47        | 0.54%   |
| Pop!_OS 19.04 | 12        | 0.14%   |
| Pop!_OS 18.04 | 11        | 0.13%   |
| Pop!_OS 18.10 | 5         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Pop!_OS | 8251      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.11.0-7620-generic      | 837       | 8.96%   |
| 5.8.0-7630-generic       | 741       | 7.94%   |
| 5.4.0-7634-generic       | 666       | 7.13%   |
| 5.13.0-7614-generic      | 496       | 5.31%   |
| 5.8.0-7642-generic       | 482       | 5.16%   |
| 5.4.0-7642-generic       | 465       | 4.98%   |
| 5.17.5-76051705-generic  | 453       | 4.85%   |
| 5.19.0-76051900-generic  | 441       | 4.72%   |
| 5.11.0-7614-generic      | 437       | 4.68%   |
| 5.13.0-7620-generic      | 413       | 4.42%   |
| 6.0.6-76060006-generic   | 293       | 3.14%   |
| 5.15.15-76051515-generic | 280       | 3%      |
| 6.0.12-76060006-generic  | 273       | 2.92%   |
| 5.16.11-76051611-generic | 262       | 2.81%   |
| 5.15.5-76051505-generic  | 236       | 2.53%   |
| 5.11.0-7612-generic      | 226       | 2.42%   |
| 5.18.10-76051810-generic | 209       | 2.24%   |
| 5.8.0-7625-generic       | 195       | 2.09%   |
| 5.17.15-76051715-generic | 188       | 2.01%   |
| 5.11.0-7633-generic      | 180       | 1.93%   |
| 5.16.19-76051619-generic | 178       | 1.91%   |
| 5.15.8-76051508-generic  | 171       | 1.83%   |
| 5.16.15-76051615-generic | 150       | 1.61%   |
| 5.4.0-7626-generic       | 144       | 1.54%   |
| 5.15.11-76051511-generic | 114       | 1.22%   |
| 5.15.23-76051523-generic | 91        | 0.97%   |
| 6.0.2-76060002-generic   | 86        | 0.92%   |
| 5.4.0-7625-generic       | 74        | 0.79%   |
| 5.4.0-7629-generic       | 62        | 0.66%   |
| 5.19.16-76051916-generic | 43        | 0.46%   |
| 6.0.3-76060003-generic   | 39        | 0.42%   |
| 5.3.0-7625-generic       | 16        | 0.17%   |
| 5.3.0-7629-generic       | 10        | 0.11%   |
| 5.3.0-7648-generic       | 9         | 0.1%    |
| 5.11.0-051100-generic    | 9         | 0.1%    |
| 5.4.0-7624-generic       | 6         | 0.06%   |
| 5.13.0-1011-raspi        | 6         | 0.06%   |
| 5.3.0-22-generic         | 5         | 0.05%   |
| 5.15.0-76051500-generic  | 5         | 0.05%   |
| 5.8.5-xanmod1            | 4         | 0.04%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 1624      | 17.79%  |
| 5.4.0   | 1370      | 15%     |
| 5.8.0   | 1358      | 14.87%  |
| 5.13.0  | 911       | 9.98%   |
| 5.17.5  | 456       | 4.99%   |
| 5.19.0  | 444       | 4.86%   |
| 6.0.6   | 294       | 3.22%   |
| 5.15.15 | 281       | 3.08%   |
| 6.0.12  | 274       | 3%      |
| 5.16.11 | 262       | 2.87%   |
| 5.15.5  | 236       | 2.58%   |
| 5.18.10 | 209       | 2.29%   |
| 5.17.15 | 188       | 2.06%   |
| 5.16.19 | 178       | 1.95%   |
| 5.15.8  | 171       | 1.87%   |
| 5.16.15 | 150       | 1.64%   |
| 5.15.11 | 114       | 1.25%   |
| 5.15.23 | 91        | 1%      |
| 6.0.2   | 89        | 0.97%   |
| 5.3.0   | 51        | 0.56%   |
| 5.19.16 | 43        | 0.47%   |
| 6.0.3   | 39        | 0.43%   |
| 5.0.0   | 12        | 0.13%   |
| 5.15.0  | 9         | 0.1%    |
| 5.8.5   | 8         | 0.09%   |
| 5.7.0   | 8         | 0.09%   |
| 5.8.12  | 7         | 0.08%   |
| 4.18.0  | 7         | 0.08%   |
| 5.13.12 | 6         | 0.07%   |
| 5.10.0  | 6         | 0.07%   |
| 5.8.6   | 5         | 0.05%   |
| 5.6.16  | 5         | 0.05%   |
| 6.1.0   | 4         | 0.04%   |
| 5.7.8   | 4         | 0.04%   |
| 5.7.1   | 4         | 0.04%   |
| 5.14.0  | 4         | 0.04%   |
| 5.12.14 | 4         | 0.04%   |
| 6.0.9   | 3         | 0.03%   |
| 5.9.1   | 3         | 0.03%   |
| 5.8.9   | 3         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 1633      | 18.06%  |
| 5.8     | 1395      | 15.42%  |
| 5.4     | 1374      | 15.19%  |
| 5.13    | 930       | 10.28%  |
| 5.15    | 898       | 9.93%   |
| 6.0     | 684       | 7.56%   |
| 5.17    | 643       | 7.11%   |
| 5.16    | 579       | 6.4%    |
| 5.19    | 489       | 5.41%   |
| 5.18    | 216       | 2.39%   |
| 5.3     | 51        | 0.56%   |
| 5.10    | 28        | 0.31%   |
| 5.7     | 27        | 0.3%    |
| 5.12    | 18        | 0.2%    |
| 5.14    | 16        | 0.18%   |
| 5.9     | 15        | 0.17%   |
| 5.6     | 15        | 0.17%   |
| 5.0     | 12        | 0.13%   |
| 6.1     | 8         | 0.09%   |
| 4.18    | 8         | 0.09%   |
| 4.15    | 3         | 0.03%   |
| 5.1     | 1         | 0.01%   |
| 4.9     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 8235      | 99.81%  |
| aarch64 | 16        | 0.19%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 7990      | 96.25%  |
| KDE5            | 70        | 0.84%   |
| KDE             | 59        | 0.71%   |
| Unknown         | 54        | 0.65%   |
| X-Cinnamon      | 36        | 0.43%   |
| MATE            | 19        | 0.23%   |
| XFCE            | 16        | 0.19%   |
| GNOME Flashback | 15        | 0.18%   |
| Cinnamon        | 13        | 0.16%   |
| LXQt            | 11        | 0.13%   |
| Budgie          | 6         | 0.07%   |
| Unity           | 5         | 0.06%   |
| i3              | 3         | 0.04%   |
| pop             | 1         | 0.01%   |
| Pantheon        | 1         | 0.01%   |
| Deepin          | 1         | 0.01%   |
| awesome         | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 8029      | 96.82%  |
| Wayland | 228       | 2.75%   |
| Unknown | 23        | 0.28%   |
| Tty     | 13        | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6619      | 79.42%  |
| GDM     | 1198      | 14.37%  |
| GDM3    | 492       | 5.9%    |
| SDDM    | 14        | 0.17%   |
| TDM     | 8         | 0.1%    |
| LightDM | 3         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 4725      | 56.86%  |
| en_GB   | 632       | 7.61%   |
| pt_BR   | 601       | 7.23%   |
| de_DE   | 388       | 4.67%   |
| C       | 252       | 3.03%   |
| en_AU   | 213       | 2.56%   |
| en_CA   | 187       | 2.25%   |
| fr_FR   | 164       | 1.97%   |
| it_IT   | 148       | 1.78%   |
| es_ES   | 135       | 1.62%   |
| ru_RU   | 107       | 1.29%   |
| pl_PL   | 74        | 0.89%   |
| Unknown | 71        | 0.85%   |
| sv_SE   | 55        | 0.66%   |
| nl_NL   | 53        | 0.64%   |
| pt_PT   | 52        | 0.63%   |
| en_IN   | 34        | 0.41%   |
| fi_FI   | 29        | 0.35%   |
| nb_NO   | 23        | 0.28%   |
| en_ZA   | 23        | 0.28%   |
| es_MX   | 22        | 0.26%   |
| fr_CA   | 21        | 0.25%   |
| es_AR   | 21        | 0.25%   |
| en_NZ   | 18        | 0.22%   |
| tr_TR   | 16        | 0.19%   |
| en_DK   | 16        | 0.19%   |
| es_CL   | 13        | 0.16%   |
| da_DK   | 13        | 0.16%   |
| sk_SK   | 12        | 0.14%   |
| hu_HU   | 12        | 0.14%   |
| hr_HR   | 12        | 0.14%   |
| en_IE   | 12        | 0.14%   |
| cs_CZ   | 12        | 0.14%   |
| nl_BE   | 11        | 0.13%   |
| ja_JP   | 11        | 0.13%   |
| zh_TW   | 10        | 0.12%   |
| ro_RO   | 9         | 0.11%   |
| de_CH   | 9         | 0.11%   |
| de_AT   | 9         | 0.11%   |
| zh_CN   | 7         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 6145      | 73.44%  |
| EFI  | 2222      | 26.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 7911      | 95.58%  |
| Btrfs   | 185       | 2.24%   |
| Overlay | 136       | 1.64%   |
| Xfs     | 25        | 0.3%    |
| Unknown | 13        | 0.16%   |
| Zfs     | 6         | 0.07%   |
| Ext2    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6577      | 79.07%  |
| GPT     | 1563      | 18.79%  |
| MBR     | 178       | 2.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 8052      | 97.22%  |
| Yes       | 230       | 2.78%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7549      | 91.03%  |
| Yes       | 744       | 8.97%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1449      | 17.56%  |
| Dell                    | 1101      | 13.34%  |
| Lenovo                  | 1083      | 13.13%  |
| Hewlett-Packard         | 871       | 10.56%  |
| Gigabyte Technology     | 632       | 7.66%   |
| MSI                     | 627       | 7.6%    |
| Acer                    | 397       | 4.81%   |
| Apple                   | 338       | 4.1%    |
| ASRock                  | 329       | 3.99%   |
| System76                | 200       | 2.42%   |
| Intel                   | 119       | 1.44%   |
| Toshiba                 | 91        | 1.1%    |
| Samsung Electronics     | 87        | 1.05%   |
| HUAWEI                  | 56        | 0.68%   |
| Alienware               | 51        | 0.62%   |
| Sony                    | 48        | 0.58%   |
| Notebook                | 42        | 0.51%   |
| Microsoft               | 42        | 0.51%   |
| Fujitsu                 | 40        | 0.48%   |
| Google                  | 36        | 0.44%   |
| Positivo                | 34        | 0.41%   |
| Unknown                 | 32        | 0.39%   |
| Pegatron                | 27        | 0.33%   |
| Razer                   | 21        | 0.25%   |
| Medion                  | 21        | 0.25%   |
| Timi                    | 17        | 0.21%   |
| Supermicro              | 17        | 0.21%   |
| Raspberry Pi Foundation | 16        | 0.19%   |
| PC Specialist           | 16        | 0.19%   |
| Foxconn                 | 16        | 0.19%   |
| Biostar                 | 16        | 0.19%   |
| LG Electronics          | 15        | 0.18%   |
| ECS                     | 15        | 0.18%   |
| Gateway                 | 13        | 0.16%   |
| Framework               | 12        | 0.15%   |
| TUXEDO                  | 11        | 0.13%   |
| Packard Bell            | 11        | 0.13%   |
| GPU Company             | 11        | 0.13%   |
| Avell High Performance  | 10        | 0.12%   |
| Huanan                  | 9         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUS All Series                | 81        | 0.98%   |
| Unknown                        | 45        | 0.55%   |
| System76 Oryx Pro              | 42        | 0.51%   |
| System76 Lemur Pro             | 37        | 0.45%   |
| ASUS TUF Gaming X570-PLUS      | 37        | 0.45%   |
| Gigabyte B450M DS3H            | 33        | 0.4%    |
| MSI MS-7C02                    | 29        | 0.35%   |
| Dell XPS 15 7590               | 29        | 0.35%   |
| ASUS ROG STRIX B450-F GAMING   | 27        | 0.33%   |
| MSI MS-7C37                    | 26        | 0.32%   |
| MSI MS-7B86                    | 25        | 0.3%    |
| Apple MacBookPro9,2            | 23        | 0.28%   |
| System76 Gazelle               | 22        | 0.27%   |
| ASUS ROG STRIX B550-F GAMING   | 22        | 0.27%   |
| Dell OptiPlex 9020             | 21        | 0.25%   |
| ASUS PRIME B450M-A             | 21        | 0.25%   |
| System76 Thelio                | 20        | 0.24%   |
| System76 Galago Pro            | 20        | 0.24%   |
| Dell XPS 15 9500               | 20        | 0.24%   |
| HP Pavilion Notebook           | 19        | 0.23%   |
| HP Notebook                    | 18        | 0.22%   |
| Gigabyte X570 AORUS ELITE      | 18        | 0.22%   |
| Apple MacBookPro12,1           | 17        | 0.21%   |
| System76 Darter Pro            | 16        | 0.19%   |
| ASRock B450M Pro4              | 16        | 0.19%   |
| Apple MacBookPro8,1            | 16        | 0.19%   |
| HP Pavilion dv6                | 15        | 0.18%   |
| HP Pavilion 15                 | 15        | 0.18%   |
| Dell OptiPlex 7010             | 15        | 0.18%   |
| ASRock B450M Steel Legend      | 15        | 0.18%   |
| Gigabyte A320M-S2H             | 14        | 0.17%   |
| Dell XPS 15 9560               | 14        | 0.17%   |
| Apple MacBookAir7,2            | 14        | 0.17%   |
| Apple MacBookAir6,2            | 14        | 0.17%   |
| MSI MS-7C91                    | 13        | 0.16%   |
| Lenovo IdeaPad S145-15API 81V7 | 13        | 0.16%   |
| Gigabyte B450 I AORUS PRO WIFI | 13        | 0.16%   |
| Dell Latitude E6420            | 13        | 0.16%   |
| Apple MacBookPro7,1            | 13        | 0.16%   |
| RPi Raspberry Pi               | 12        | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 451       | 5.47%   |
| Dell Inspiron      | 317       | 3.84%   |
| ASUS ROG           | 280       | 3.39%   |
| Acer Aspire        | 269       | 3.26%   |
| Lenovo IdeaPad     | 250       | 3.03%   |
| Dell Latitude      | 203       | 2.46%   |
| Dell XPS           | 200       | 2.42%   |
| ASUS PRIME         | 169       | 2.05%   |
| HP Pavilion        | 168       | 2.04%   |
| ASUS TUF           | 143       | 1.73%   |
| Dell OptiPlex      | 135       | 1.64%   |
| HP EliteBook       | 98        | 1.19%   |
| Dell Precision     | 96        | 1.16%   |
| HP Laptop          | 88        | 1.07%   |
| ASUS VivoBook      | 84        | 1.02%   |
| ASUS All           | 81        | 0.98%   |
| Toshiba Satellite  | 79        | 0.96%   |
| HP ENVY            | 74        | 0.9%    |
| HP ProBook         | 73        | 0.88%   |
| Lenovo Legion      | 70        | 0.85%   |
| HP Compaq          | 69        | 0.84%   |
| Gigabyte X570      | 66        | 0.8%    |
| Lenovo Yoga        | 60        | 0.73%   |
| Dell Vostro        | 57        | 0.69%   |
| Lenovo ThinkCentre | 53        | 0.64%   |
| Gigabyte B450      | 49        | 0.59%   |
| Gigabyte B450M     | 46        | 0.56%   |
| Acer Nitro         | 45        | 0.55%   |
| Unknown            | 45        | 0.55%   |
| System76 Oryx      | 42        | 0.51%   |
| Microsoft Surface  | 42        | 0.51%   |
| ASUS ASUS          | 42        | 0.51%   |
| System76 Lemur     | 40        | 0.48%   |
| ASRock B450M       | 37        | 0.45%   |
| HP OMEN            | 35        | 0.42%   |
| ASUS ZenBook       | 33        | 0.4%    |
| ASRock X570        | 32        | 0.39%   |
| Acer Swift         | 32        | 0.39%   |
| System76 Thelio    | 31        | 0.38%   |
| Apple MacBookPro9  | 30        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1077      | 13.05%  |
| 2020    | 1002      | 12.14%  |
| 2018    | 992       | 12.02%  |
| 2021    | 663       | 8.04%   |
| 2012    | 614       | 7.44%   |
| 2017    | 580       | 7.03%   |
| 2013    | 511       | 6.19%   |
| 2011    | 483       | 5.85%   |
| 2015    | 437       | 5.3%    |
| 2014    | 429       | 5.2%    |
| 2016    | 421       | 5.1%    |
| 2010    | 320       | 3.88%   |
| 2009    | 235       | 2.85%   |
| 2022    | 179       | 2.17%   |
| 2008    | 176       | 2.13%   |
| 2007    | 92        | 1.12%   |
| 2006    | 21        | 0.25%   |
| Unknown | 17        | 0.21%   |
| 2005    | 1         | 0.01%   |
| 2004    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4508      | 54.64%  |
| Desktop        | 3169      | 38.41%  |
| Convertible    | 228       | 2.76%   |
| Mini pc        | 103       | 1.25%   |
| All in one     | 101       | 1.22%   |
| Tablet         | 99        | 1.2%    |
| Server         | 25        | 0.3%    |
| System on chip | 17        | 0.21%   |
| Stick pc       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 8246      | 99.94%  |
| Enabled  | 5         | 0.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8111      | 98.3%   |
| Yes  | 140       | 1.7%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 2191      | 26.22%  |
| 4.01-8.0        | 1813      | 21.69%  |
| 8.01-16.0       | 1558      | 18.64%  |
| 32.01-64.0      | 1124      | 13.45%  |
| 3.01-4.0        | 1041      | 12.46%  |
| 64.01-256.0     | 302       | 3.61%   |
| 24.01-32.0      | 163       | 1.95%   |
| 1.01-2.0        | 111       | 1.33%   |
| 2.01-3.0        | 43        | 0.51%   |
| More than 256.0 | 10        | 0.12%   |
| 0.51-1.0        | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 2793      | 31.01%  |
| 1.01-2.0    | 2345      | 26.03%  |
| 4.01-8.0    | 1713      | 19.02%  |
| 3.01-4.0    | 1659      | 18.42%  |
| 8.01-16.0   | 387       | 4.3%    |
| 16.01-24.0  | 56        | 0.62%   |
| 24.01-32.0  | 20        | 0.22%   |
| 0.51-1.0    | 18        | 0.2%    |
| 32.01-64.0  | 12        | 0.13%   |
| 64.01-256.0 | 4         | 0.04%   |
| 0.01-0.5    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 4693      | 55.62%  |
| 2      | 2287      | 27.1%   |
| 3      | 751       | 8.9%    |
| 4      | 375       | 4.44%   |
| 5      | 157       | 1.86%   |
| 6      | 67        | 0.79%   |
| 0      | 48        | 0.57%   |
| 7      | 27        | 0.32%   |
| 8      | 9         | 0.11%   |
| 11     | 8         | 0.09%   |
| 9      | 7         | 0.08%   |
| 10     | 3         | 0.04%   |
| 23     | 1         | 0.01%   |
| 20     | 1         | 0.01%   |
| 19     | 1         | 0.01%   |
| 14     | 1         | 0.01%   |
| 13     | 1         | 0.01%   |
| 12     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5845      | 70.47%  |
| Yes       | 2449      | 29.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7032      | 84.92%  |
| No        | 1249      | 15.08%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6667      | 80.41%  |
| No        | 1624      | 19.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5553      | 66.64%  |
| No        | 2780      | 33.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 2487      | 30%     |
| Brazil       | 800       | 9.65%   |
| Germany      | 543       | 6.55%   |
| UK           | 419       | 5.05%   |
| Canada       | 366       | 4.41%   |
| Australia    | 244       | 2.94%   |
| India        | 242       | 2.92%   |
| Italy        | 239       | 2.88%   |
| France       | 212       | 2.56%   |
| Netherlands  | 186       | 2.24%   |
| Sweden       | 142       | 1.71%   |
| Russia       | 137       | 1.65%   |
| Poland       | 125       | 1.51%   |
| Spain        | 112       | 1.35%   |
| Portugal     | 92        | 1.11%   |
| Mexico       | 91        | 1.1%    |
| Switzerland  | 85        | 1.03%   |
| South Africa | 83        | 1%      |
| Romania      | 83        | 1%      |
| Norway       | 77        | 0.93%   |
| Finland      | 75        | 0.9%    |
| Austria      | 63        | 0.76%   |
| Greece       | 62        | 0.75%   |
| Belgium      | 60        | 0.72%   |
| Argentina    | 60        | 0.72%   |
| Philippines  | 58        | 0.7%    |
| New Zealand  | 58        | 0.7%    |
| Denmark      | 52        | 0.63%   |
| Turkey       | 50        | 0.6%    |
| Indonesia    | 47        | 0.57%   |
| Chile        | 41        | 0.49%   |
| Japan        | 38        | 0.46%   |
| Ireland      | 37        | 0.45%   |
| Czechia      | 36        | 0.43%   |
| Hungary      | 35        | 0.42%   |
| Bulgaria     | 35        | 0.42%   |
| Croatia      | 32        | 0.39%   |
| Malaysia     | 31        | 0.37%   |
| Ukraine      | 30        | 0.36%   |
| Israel       | 28        | 0.34%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 93        | 1.08%   |
| Sydney         | 65        | 0.75%   |
| Melbourne      | 49        | 0.57%   |
| Berlin         | 49        | 0.57%   |
| Rio de Janeiro | 48        | 0.56%   |
| Brisbane       | 47        | 0.54%   |
| Milan          | 45        | 0.52%   |
| Vienna         | 41        | 0.48%   |
| London         | 38        | 0.44%   |
| Helsinki       | 37        | 0.43%   |
| Dallas         | 36        | 0.42%   |
| Moscow         | 35        | 0.41%   |
| Warsaw         | 34        | 0.39%   |
| Bengaluru      | 33        | 0.38%   |
| Rome           | 31        | 0.36%   |
| Paris          | 31        | 0.36%   |
| Athens         | 31        | 0.36%   |
| Amsterdam      | 31        | 0.36%   |
| Chicago        | 30        | 0.35%   |
| New York       | 29        | 0.34%   |
| Bucharest      | 29        | 0.34%   |
| Zurich         | 28        | 0.32%   |
| Toronto        | 28        | 0.32%   |
| Miami          | 27        | 0.31%   |
| Auckland       | 27        | 0.31%   |
| Montreal       | 26        | 0.3%    |
| Denver         | 26        | 0.3%    |
| Madrid         | 25        | 0.29%   |
| Los Angeles    | 25        | 0.29%   |
| Johannesburg   | 25        | 0.29%   |
| Istanbul       | 25        | 0.29%   |
| Calgary        | 25        | 0.29%   |
| Sofia          | 24        | 0.28%   |
| Edmonton       | 24        | 0.28%   |
| Seattle        | 23        | 0.27%   |
| Lisbon         | 23        | 0.27%   |
| Zagreb         | 22        | 0.26%   |
| Singapore      | 22        | 0.26%   |
| Dublin         | 22        | 0.26%   |
| Brasília      | 22        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 2282      | 3446   | 17.97%  |
| WDC                       | 1726      | 2389   | 13.59%  |
| Seagate                   | 1725      | 2472   | 13.58%  |
| SanDisk                   | 842       | 1103   | 6.63%   |
| Kingston                  | 714       | 897    | 5.62%   |
| Toshiba                   | 680       | 827    | 5.35%   |
| Crucial                   | 512       | 667    | 4.03%   |
| Unknown                   | 411       | 526    | 3.24%   |
| Intel                     | 356       | 474    | 2.8%    |
| SK hynix                  | 353       | 453    | 2.78%   |
| Hitachi                   | 260       | 326    | 2.05%   |
| Phison                    | 228       | 319    | 1.79%   |
| HGST                      | 217       | 259    | 1.71%   |
| Micron Technology         | 192       | 226    | 1.51%   |
| A-DATA Technology         | 191       | 239    | 1.5%    |
| Apple                     | 156       | 181    | 1.23%   |
| PNY                       | 121       | 152    | 0.95%   |
| Silicon Motion            | 114       | 154    | 0.9%    |
| China                     | 112       | 150    | 0.88%   |
| Micron/Crucial Technology | 108       | 140    | 0.85%   |
| KIOXIA                    | 62        | 73     | 0.49%   |
| LITEON                    | 57        | 68     | 0.45%   |
| OCZ                       | 55        | 70     | 0.43%   |
| SPCC                      | 54        | 70     | 0.43%   |
| XPG                       | 47        | 62     | 0.37%   |
| Team                      | 42        | 50     | 0.33%   |
| Corsair                   | 42        | 55     | 0.33%   |
| Transcend                 | 41        | 48     | 0.32%   |
| Patriot                   | 40        | 54     | 0.31%   |
| Realtek Semiconductor     | 38        | 43     | 0.3%    |
| Phison Electronics        | 38        | 50     | 0.3%    |
| LITEONIT                  | 37        | 46     | 0.29%   |
| Maxtor                    | 35        | 36     | 0.28%   |
| JMicron Technology        | 30        | 46     | 0.24%   |
| Intenso                   | 29        | 31     | 0.23%   |
| Lexar                     | 27        | 28     | 0.21%   |
| KingSpec                  | 27        | 32     | 0.21%   |
| Hewlett-Packard           | 27        | 34     | 0.21%   |
| ADATA Technology          | 27        | 36     | 0.21%   |
| Netac                     | 25        | 26     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 1TB                          | 197       | 1.4%    |
| Kingston SA400S37240G 240GB SSD                     | 190       | 1.35%   |
| Samsung NVMe SSD Drive 500GB                        | 178       | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB                      | 119       | 0.85%   |
| Samsung NVMe SSD Drive 512GB                        | 118       | 0.84%   |
| Samsung SSD 850 EVO 250GB                           | 115       | 0.82%   |
| SanDisk NVMe SSD Drive 1TB                          | 107       | 0.76%   |
| Samsung SSD 860 EVO 500GB                           | 105       | 0.75%   |
| Samsung SSD 850 EVO 500GB                           | 103       | 0.73%   |
| Unknown MMC Card  64GB                              | 102       | 0.73%   |
| Seagate ST2000DM008-2FR102 2TB                      | 96        | 0.68%   |
| SanDisk NVMe SSD Drive 500GB                        | 96        | 0.68%   |
| Samsung SSD 860 EVO 1TB                             | 95        | 0.68%   |
| Seagate ST1000DM010-2EP102 1TB                      | 91        | 0.65%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 91        | 0.65%   |
| Kingston SA400S37120G 120GB SSD                     | 87        | 0.62%   |
| Kingston SA400S37480G 480GB SSD                     | 82        | 0.58%   |
| HGST HTS721010A9E630 1TB                            | 79        | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 76        | 0.54%   |
| Seagate ST500DM002-1BD142 500GB                     | 74        | 0.53%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 74        | 0.53%   |
| Toshiba MQ01ABD100 1TB                              | 73        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                         | 73        | 0.52%   |
| SanDisk NVMe SSD Drive 512GB                        | 70        | 0.5%    |
| Crucial CT500MX500SSD1 500GB                        | 70        | 0.5%    |
| Intel NVMe SSD Drive 512GB                          | 69        | 0.49%   |
| Unknown MMC Card  32GB                              | 66        | 0.47%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 65        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                       | 61        | 0.43%   |
| Crucial CT240BX500SSD1 240GB                        | 60        | 0.43%   |
| Samsung NVMe SSD Drive 2TB                          | 59        | 0.42%   |
| Samsung NVMe SSD Drive 1024GB                       | 58        | 0.41%   |
| Unknown MMC Card  128GB                             | 52        | 0.37%   |
| Samsung SSD 970 EVO Plus 1TB                        | 52        | 0.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 52        | 0.37%   |
| Intel NVMe SSD Drive 1024GB                         | 52        | 0.37%   |
| Seagate Expansion 240GB                             | 51        | 0.36%   |
| Samsung SSD 860 EVO 250GB                           | 51        | 0.36%   |
| Phison NVMe SSD Drive 1TB                           | 49        | 0.35%   |
| Micron/Crucial NVMe SSD Drive 1TB                   | 49        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1670      | 2348   | 38.83%  |
| WDC                 | 1325      | 1819   | 30.81%  |
| Toshiba             | 481       | 575    | 11.18%  |
| Hitachi             | 260       | 326    | 6.05%   |
| HGST                | 217       | 259    | 5.05%   |
| Samsung Electronics | 136       | 160    | 3.16%   |
| Unknown             | 50        | 62     | 1.16%   |
| Apple               | 45        | 55     | 1.05%   |
| Maxtor              | 27        | 28     | 0.63%   |
| Fujitsu             | 23        | 25     | 0.53%   |
| SABRENT             | 17        | 20     | 0.4%    |
| ASMT                | 14        | 20     | 0.33%   |
| JMicron Technology  | 5         | 13     | 0.12%   |
| USB                 | 3         | 4      | 0.07%   |
| Intenso             | 3         | 3      | 0.07%   |
| Hewlett-Packard     | 3         | 5      | 0.07%   |
| ExcelStor           | 3         | 3      | 0.07%   |
| RSH-339             | 2         | 2      | 0.05%   |
| Magnetic Data       | 2         | 2      | 0.05%   |
| HGST HTS            | 2         | 2      | 0.05%   |
| USB3.0              | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| OEM                 | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| LaCie               | 1         | 1      | 0.02%   |
| HGST HDN            | 1         | 1      | 0.02%   |
| H/W                 | 1         | 1      | 0.02%   |
| Glyph               | 1         | 2      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| ASMT109x            | 1         | 1      | 0.02%   |
| ASMedia             | 1         | 1      | 0.02%   |
| Asm                 | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1086      | 1581   | 24.42%  |
| Kingston            | 582       | 716    | 13.09%  |
| Crucial             | 475       | 618    | 10.68%  |
| SanDisk             | 416       | 526    | 9.35%   |
| WDC                 | 305       | 381    | 6.86%   |
| A-DATA Technology   | 149       | 188    | 3.35%   |
| PNY                 | 118       | 149    | 2.65%   |
| China               | 110       | 148    | 2.47%   |
| Intel               | 102       | 121    | 2.29%   |
| Apple               | 94        | 100    | 2.11%   |
| SK hynix            | 82        | 105    | 1.84%   |
| Micron Technology   | 71        | 78     | 1.6%    |
| Toshiba             | 67        | 78     | 1.51%   |
| OCZ                 | 54        | 66     | 1.21%   |
| LITEON              | 53        | 64     | 1.19%   |
| SPCC                | 49        | 60     | 1.1%    |
| Transcend           | 40        | 47     | 0.9%    |
| Patriot             | 40        | 54     | 0.9%    |
| LITEONIT            | 37        | 46     | 0.83%   |
| Team                | 35        | 43     | 0.79%   |
| Corsair             | 32        | 39     | 0.72%   |
| Seagate             | 31        | 46     | 0.7%    |
| KingSpec            | 26        | 31     | 0.58%   |
| Lexar               | 24        | 25     | 0.54%   |
| Netac               | 22        | 23     | 0.49%   |
| Hewlett-Packard     | 20        | 25     | 0.45%   |
| Intenso             | 18        | 20     | 0.4%    |
| GOODRAM             | 15        | 17     | 0.34%   |
| Apacer              | 15        | 22     | 0.34%   |
| JMicron Technology  | 14        | 15     | 0.31%   |
| KingDian            | 13        | 17     | 0.29%   |
| TO Exter            | 12        | 15     | 0.27%   |
| Plextor             | 12        | 16     | 0.27%   |
| Gigabyte Technology | 12        | 14     | 0.27%   |
| Mushkin             | 10        | 12     | 0.22%   |
| Dogfish             | 9         | 12     | 0.2%    |
| Maxtor              | 8         | 8      | 0.18%   |
| OWC                 | 7         | 16     | 0.16%   |
| PNY USB             | 6         | 13     | 0.13%   |
| FORESEE             | 6         | 8      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 3864      | 5753   | 33.9%   |
| HDD     | 3666      | 5749   | 32.16%  |
| NVMe    | 3344      | 4937   | 29.34%  |
| MMC     | 316       | 391    | 2.77%   |
| Unknown | 209       | 290    | 1.83%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5964      | 11078  | 59%     |
| NVMe | 3339      | 4920   | 33.03%  |
| SAS  | 490       | 731    | 4.85%   |
| MMC  | 316       | 391    | 3.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 4361      | 6522   | 55.55%  |
| 0.51-1.0   | 2368      | 3251   | 30.16%  |
| 1.01-2.0   | 636       | 907    | 8.1%    |
| 3.01-4.0   | 196       | 314    | 2.5%    |
| 4.01-10.0  | 137       | 253    | 1.75%   |
| 2.01-3.0   | 135       | 209    | 1.72%   |
| 10.01-20.0 | 18        | 46     | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2559      | 29.85%  |
| 251-500        | 2132      | 24.87%  |
| 501-1000       | 1587      | 18.51%  |
| 1001-2000      | 794       | 9.26%   |
| 51-100         | 396       | 4.62%   |
| More than 3000 | 393       | 4.58%   |
| 2001-3000      | 263       | 3.07%   |
| 1-20           | 202       | 2.36%   |
| 21-50          | 193       | 2.25%   |
| Unknown        | 53        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3361      | 37.51%  |
| 21-50          | 1779      | 19.85%  |
| 101-250        | 1113      | 12.42%  |
| 51-100         | 1057      | 11.8%   |
| 251-500        | 672       | 7.5%    |
| 501-1000       | 436       | 4.87%   |
| 1001-2000      | 261       | 2.91%   |
| More than 3000 | 143       | 1.6%    |
| 2001-3000      | 85        | 0.95%   |
| Unknown        | 53        | 0.59%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 7      | 2.77%   |
| HGST HTS725050A7E630 500GB            | 6         | 9      | 2.37%   |
| HGST HTS721010A9E630 1TB              | 5         | 5      | 1.98%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 1.58%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 1.58%   |
| WDC WD10JPCX-24UE4T0 1TB              | 3         | 3      | 1.19%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 4      | 1.19%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 1.19%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 1.19%   |
| Seagate ST500DM002-1BD142 500GB       | 3         | 3      | 1.19%   |
| Seagate ST1500DL003-9VT16L 1TB        | 3         | 4      | 1.19%   |
| Seagate ST1000LX015-1U7172 1TB        | 3         | 3      | 1.19%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 3      | 1.19%   |
| Samsung Electronics HD502HI 500GB     | 3         | 4      | 1.19%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 5      | 1.19%   |
| Kingston SA400S37120G 120GB SSD       | 3         | 4      | 1.19%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 5      | 1.19%   |
| Crucial CT525MX300SSD1 528GB          | 3         | 3      | 1.19%   |
| Crucial CT1000P1SSD8 1TB              | 3         | 3      | 1.19%   |
| WDC WD3200AAKS-75B3A0 320GB           | 2         | 2      | 0.79%   |
| WDC WD10EZEX-60WN4A0 1TB              | 2         | 2      | 0.79%   |
| WDC WD1002FAEX-00Z3A0 1TB             | 2         | 2      | 0.79%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.79%   |
| Toshiba HDWD110 1TB                   | 2         | 2      | 0.79%   |
| Seagate ST9750420AS 752GB             | 2         | 2      | 0.79%   |
| Seagate ST9500325AS 500GB             | 2         | 3      | 0.79%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.79%   |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 2      | 0.79%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 2         | 2      | 0.79%   |
| Samsung Electronics SSD 850 EVO 500GB | 2         | 2      | 0.79%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 2      | 0.79%   |
| Kingston SUV400S37120G 120GB SSD      | 2         | 2      | 0.79%   |
| Hitachi HDP725050GLA360 500GB         | 2         | 2      | 0.79%   |
| A-DATA Technology SU800 512GB SSD     | 2         | 2      | 0.79%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.4%    |
| WDC WD7500BPVT-60HXZT1 752GB          | 1         | 1      | 0.4%    |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.4%    |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.4%    |
| WDC WD60EFRX-68L0BN1 6TB              | 1         | 1      | 0.4%    |
| WDC WD5001AALS-00J7B1 500GB           | 1         | 1      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 71     | 24.9%   |
| WDC                 | 51        | 59     | 20.48%  |
| Samsung Electronics | 25        | 30     | 10.04%  |
| Toshiba             | 17        | 18     | 6.83%   |
| HGST                | 17        | 20     | 6.83%   |
| Kingston            | 12        | 15     | 4.82%   |
| Hitachi             | 12        | 15     | 4.82%   |
| Crucial             | 9         | 9      | 3.61%   |
| SK hynix            | 7         | 9      | 2.81%   |
| Intel               | 7         | 7      | 2.81%   |
| Micron Technology   | 6         | 7      | 2.41%   |
| A-DATA Technology   | 6         | 6      | 2.41%   |
| SanDisk             | 3         | 3      | 1.2%    |
| China               | 2         | 2      | 0.8%    |
| Team                | 1         | 1      | 0.4%    |
| SPCC                | 1         | 1      | 0.4%    |
| SABRENT             | 1         | 1      | 0.4%    |
| S3+                 | 1         | 1      | 0.4%    |
| Plextor             | 1         | 1      | 0.4%    |
| Maxtor              | 1         | 1      | 0.4%    |
| LITEON              | 1         | 1      | 0.4%    |
| Lexar               | 1         | 1      | 0.4%    |
| Leven               | 1         | 1      | 0.4%    |
| Intenso             | 1         | 1      | 0.4%    |
| BAITITON            | 1         | 1      | 0.4%    |
| ASMT                | 1         | 1      | 0.4%    |
| Apple               | 1         | 1      | 0.4%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 62        | 71     | 36.69%  |
| WDC                 | 49        | 57     | 28.99%  |
| HGST                | 17        | 20     | 10.06%  |
| Toshiba             | 15        | 15     | 8.88%   |
| Hitachi             | 12        | 15     | 7.1%    |
| Samsung Electronics | 10        | 11     | 5.92%   |
| SABRENT             | 1         | 1      | 0.59%   |
| Maxtor              | 1         | 1      | 0.59%   |
| ASMT                | 1         | 1      | 0.59%   |
| Apple               | 1         | 1      | 0.59%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 157       | 193    | 66.24%  |
| SSD  | 60        | 70     | 25.32%  |
| NVMe | 20        | 21     | 8.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST3500418ASQ 500GB        | 1         | 1      | 25%     |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 25%     |
| Patriot Pyro SSD 120GB            | 1         | 2      | 25%     |
| KingDian S400 120GB SSD           | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |
| Patriot             | 1         | 2      | 25%     |
| KingDian            | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 6685      | 13980  | 77.27%  |
| Works    | 1732      | 2850   | 20.02%  |
| Malfunc  | 230       | 284    | 2.66%   |
| Failed   | 4         | 5      | 0.05%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5096      | 45.3%   |
| AMD                              | 2042      | 18.15%  |
| Samsung Electronics              | 1334      | 11.86%  |
| SanDisk                          | 562       | 5%      |
| Phison Electronics               | 277       | 2.46%   |
| SK hynix                         | 270       | 2.4%    |
| ASMedia Technology               | 191       | 1.7%    |
| Toshiba America Info Systems     | 146       | 1.3%    |
| Nvidia                           | 146       | 1.3%    |
| Kingston Technology Company      | 144       | 1.28%   |
| Micron/Crucial Technology        | 140       | 1.24%   |
| Silicon Motion                   | 126       | 1.12%   |
| Micron Technology                | 124       | 1.1%    |
| ADATA Technology                 | 103       | 0.92%   |
| Marvell Technology Group         | 101       | 0.9%    |
| JMicron Technology               | 82        | 0.73%   |
| KIOXIA                           | 66        | 0.59%   |
| Realtek Semiconductor            | 51        | 0.45%   |
| Union Memory (Shenzhen)          | 34        | 0.3%    |
| Solid State Storage Technology   | 32        | 0.28%   |
| Broadcom / LSI                   | 25        | 0.22%   |
| Seagate Technology               | 24        | 0.21%   |
| LSI Logic / Symbios Logic        | 19        | 0.17%   |
| Apple                            | 19        | 0.17%   |
| Lite-On Technology               | 16        | 0.14%   |
| Shenzhen Longsys Electronics     | 12        | 0.11%   |
| VIA Technologies                 | 10        | 0.09%   |
| Silicon Integrated Systems [SiS] | 10        | 0.09%   |
| Silicon Image                    | 7         | 0.06%   |
| Lenovo                           | 7         | 0.06%   |
| INNOGRIT                         | 6         | 0.05%   |
| Hewlett-Packard                  | 5         | 0.04%   |
| Adaptec                          | 5         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.04%   |
| HighPoint Technologies           | 3         | 0.03%   |
| OCZ Technology Group             | 2         | 0.02%   |
| Yangtze Memory Technologies      | 1         | 0.01%   |
| Transcend                        | 1         | 0.01%   |
| O2 Micro                         | 1         | 0.01%   |
| Netac Technology                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1529      | 12.03%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 766       | 6.03%   |
| AMD 400 Series Chipset SATA Controller                                         | 428       | 3.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 415       | 3.27%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 338       | 2.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 331       | 2.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 313       | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 255       | 2.01%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 231       | 1.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 213       | 1.68%   |
| AMD 500 Series Chipset SATA Controller                                         | 201       | 1.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 182       | 1.43%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 182       | 1.43%   |
| Samsung NVMe SSD Controller 980                                                | 175       | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 172       | 1.35%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 162       | 1.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 162       | 1.27%   |
| Intel Volume Management Device NVMe RAID Controller                            | 160       | 1.26%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 154       | 1.21%   |
| Intel SATA Controller [RAID mode]                                              | 153       | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 149       | 1.17%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 147       | 1.16%   |
| Phison E12 NVMe Controller                                                     | 146       | 1.15%   |
| Intel SSD 660P Series                                                          | 139       | 1.09%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 133       | 1.05%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 126       | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 125       | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                          | 124       | 0.98%   |
| Micron Non-Volatile memory controller                                          | 122       | 0.96%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 118       | 0.93%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 109       | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 109       | 0.86%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 106       | 0.83%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 97        | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 97        | 0.76%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 95        | 0.75%   |
| SanDisk Non-Volatile memory controller                                         | 93        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 93        | 0.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 89        | 0.7%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 81        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 6241      | 56.47%  |
| NVMe | 3339      | 30.21%  |
| RAID | 720       | 6.52%   |
| IDE  | 700       | 6.33%   |
| SAS  | 37        | 0.33%   |
| SCSI | 14        | 0.13%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 5838      | 70.76%  |
| AMD    | 2397      | 29.05%  |
| ARM    | 16        | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 144       | 1.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 116       | 1.4%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 111       | 1.34%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 100       | 1.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 95        | 1.15%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 95        | 1.15%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 89        | 1.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 81        | 0.98%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 76        | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 71        | 0.86%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 71        | 0.86%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 70        | 0.85%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 69        | 0.83%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 68        | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 67        | 0.81%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 66        | 0.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 64        | 0.77%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 64        | 0.77%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 59        | 0.71%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 55        | 0.66%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 54        | 0.65%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 51        | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 50        | 0.6%    |
| AMD Ryzen 5 1600 Six-Core Processor           | 50        | 0.6%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 47        | 0.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 47        | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 45        | 0.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 44        | 0.53%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 43        | 0.52%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 43        | 0.52%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 43        | 0.52%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 42        | 0.51%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 42        | 0.51%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 40        | 0.48%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 40        | 0.48%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 40        | 0.48%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 40        | 0.48%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 39        | 0.47%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 39        | 0.47%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 39        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1980      | 23.96%  |
| Intel Core i5           | 1827      | 22.11%  |
| AMD Ryzen 5             | 777       | 9.4%    |
| AMD Ryzen 7             | 591       | 7.15%   |
| Other                   | 478       | 5.78%   |
| Intel Core i3           | 466       | 5.64%   |
| Intel Core 2 Duo        | 237       | 2.87%   |
| AMD Ryzen 9             | 226       | 2.73%   |
| Intel Celeron           | 209       | 2.53%   |
| Intel Xeon              | 178       | 2.15%   |
| AMD Ryzen 3             | 121       | 1.46%   |
| AMD FX                  | 120       | 1.45%   |
| Intel Pentium           | 103       | 1.25%   |
| Intel Core i9           | 103       | 1.25%   |
| AMD A6                  | 63        | 0.76%   |
| Intel Atom              | 61        | 0.74%   |
| Intel Pentium Dual-Core | 60        | 0.73%   |
| AMD A8                  | 59        | 0.71%   |
| AMD A10                 | 56        | 0.68%   |
| Intel Core 2 Quad       | 49        | 0.59%   |
| AMD Ryzen Threadripper  | 45        | 0.54%   |
| AMD A4                  | 37        | 0.45%   |
| Intel Core 2            | 32        | 0.39%   |
| AMD Phenom II X4        | 31        | 0.38%   |
| AMD Ryzen 7 PRO         | 30        | 0.36%   |
| AMD Athlon              | 27        | 0.33%   |
| Intel Pentium Dual      | 21        | 0.25%   |
| AMD Athlon II X2        | 21        | 0.25%   |
| AMD Ryzen 5 PRO         | 19        | 0.23%   |
| Intel Genuine           | 16        | 0.19%   |
| Intel Core m3           | 16        | 0.19%   |
| AMD E1                  | 13        | 0.16%   |
| AMD Athlon II X4        | 13        | 0.16%   |
| AMD Phenom II X6        | 12        | 0.15%   |
| AMD Athlon 64 X2        | 12        | 0.15%   |
| AMD E                   | 11        | 0.13%   |
| Intel Pentium Silver    | 10        | 0.12%   |
| Intel Pentium Gold      | 9         | 0.11%   |
| AMD Phenom              | 9         | 0.11%   |
| AMD E2                  | 9         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 3090      | 37.39%  |
| 2       | 2597      | 31.43%  |
| 6       | 1179      | 14.27%  |
| 8       | 899       | 10.88%  |
| 12      | 174       | 2.11%   |
| 16      | 81        | 0.98%   |
| 1       | 55        | 0.67%   |
| 10      | 51        | 0.62%   |
| 3       | 50        | 0.61%   |
| 14      | 39        | 0.47%   |
| 24      | 18        | 0.22%   |
| 32      | 16        | 0.19%   |
| Unknown | 5         | 0.06%   |
| 64      | 4         | 0.05%   |
| 40      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 20      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 7       | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8200      | 99.37%  |
| 2       | 47        | 0.57%   |
| Unknown | 5         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6309      | 76.36%  |
| 1       | 1948      | 23.58%  |
| Unknown | 5         | 0.06%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 8227      | 99.71%  |
| 64-bit         | 13        | 0.16%   |
| Unknown        | 11        | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5523      | 65.31%  |
| 0x906ea    | 190       | 2.25%   |
| 0x306a9    | 163       | 1.93%   |
| 0x206a7    | 145       | 1.71%   |
| 0x306c3    | 132       | 1.56%   |
| 0x806ec    | 124       | 1.47%   |
| 0x806ea    | 122       | 1.44%   |
| 0x806c1    | 111       | 1.31%   |
| 0x08701021 | 101       | 1.19%   |
| 0x406e3    | 93        | 1.1%    |
| 0x906e9    | 88        | 1.04%   |
| 0x40651    | 84        | 0.99%   |
| 0x506e3    | 78        | 0.92%   |
| 0x806e9    | 77        | 0.91%   |
| 0x08701013 | 75        | 0.89%   |
| 0xa0652    | 73        | 0.86%   |
| 0x0800820d | 73        | 0.86%   |
| 0x1067a    | 61        | 0.72%   |
| 0x0a50000c | 53        | 0.63%   |
| 0x08108109 | 51        | 0.6%    |
| 0x08108102 | 47        | 0.56%   |
| 0x906ed    | 43        | 0.51%   |
| 0x08600106 | 43        | 0.51%   |
| 0x306d4    | 41        | 0.48%   |
| 0x806eb    | 37        | 0.44%   |
| 0x806d1    | 37        | 0.44%   |
| 0x20655    | 30        | 0.35%   |
| 0x706e5    | 27        | 0.32%   |
| 0x08001138 | 27        | 0.32%   |
| 0x406c4    | 26        | 0.31%   |
| 0x08600104 | 25        | 0.3%    |
| 0x0810100b | 25        | 0.3%    |
| 0x06000852 | 24        | 0.28%   |
| 0x906a3    | 23        | 0.27%   |
| 0x0a201016 | 23        | 0.27%   |
| 0x08608103 | 23        | 0.27%   |
| 0x06006705 | 19        | 0.22%   |
| 0x06001119 | 19        | 0.22%   |
| 0x706a1    | 18        | 0.21%   |
| 0x08600103 | 17        | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1520      | 18.39%  |
| Haswell          | 766       | 9.27%   |
| Zen 2            | 681       | 8.24%   |
| IvyBridge        | 571       | 6.91%   |
| SandyBridge      | 563       | 6.81%   |
| Skylake          | 467       | 5.65%   |
| Zen+             | 451       | 5.46%   |
| Zen 3            | 374       | 4.53%   |
| Penryn           | 304       | 3.68%   |
| CometLake        | 276       | 3.34%   |
| Unknown          | 273       | 3.3%    |
| TigerLake        | 241       | 2.92%   |
| Zen              | 219       | 2.65%   |
| Westmere         | 201       | 2.43%   |
| Broadwell        | 174       | 2.11%   |
| Piledriver       | 173       | 2.09%   |
| Silvermont       | 139       | 1.68%   |
| Core             | 133       | 1.61%   |
| K10              | 109       | 1.32%   |
| IceLake          | 108       | 1.31%   |
| Nehalem          | 92        | 1.11%   |
| Excavator        | 83        | 1%      |
| Goldmont plus    | 66        | 0.8%    |
| Puma             | 42        | 0.51%   |
| Steamroller      | 37        | 0.45%   |
| Alderlake Hybrid | 36        | 0.44%   |
| Goldmont         | 31        | 0.38%   |
| K8 Hammer        | 29        | 0.35%   |
| Bobcat           | 26        | 0.31%   |
| K10 Llano        | 25        | 0.3%    |
| Jaguar           | 19        | 0.23%   |
| Bulldozer        | 13        | 0.16%   |
| NetBurst         | 8         | 0.1%    |
| K8 & K10 hybrid  | 7         | 0.08%   |
| Bonnell          | 6         | 0.07%   |
| Tremont          | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4321      | 42.95%  |
| Nvidia                           | 3354      | 33.34%  |
| AMD                              | 2359      | 23.45%  |
| Matrox Electronics Systems       | 14        | 0.14%   |
| Silicon Integrated Systems [SiS] | 8         | 0.08%   |
| ASPEED Technology                | 3         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 392       | 3.8%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 310       | 3%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 308       | 2.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 253       | 2.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 250       | 2.42%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 242       | 2.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 226       | 2.19%   |
| Intel UHD Graphics 620                                                                   | 223       | 2.16%   |
| AMD Renoir                                                                               | 205       | 1.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 185       | 1.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 160       | 1.55%   |
| Intel HD Graphics 620                                                                    | 160       | 1.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 155       | 1.5%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 152       | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 146       | 1.41%   |
| Intel HD Graphics 630                                                                    | 144       | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 132       | 1.28%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 121       | 1.17%   |
| Intel Core Processor Integrated Graphics Controller                                      | 117       | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 115       | 1.11%   |
| Intel HD Graphics 5500                                                                   | 114       | 1.1%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 111       | 1.08%   |
| Intel HD Graphics 530                                                                    | 110       | 1.07%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 104       | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 91        | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 84        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 83        | 0.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 81        | 0.78%   |
| AMD Lucienne                                                                             | 81        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 75        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 74        | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 72        | 0.7%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 68        | 0.66%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 65        | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 64        | 0.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 62        | 0.6%    |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 61        | 0.59%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 59        | 0.57%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 58        | 0.56%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 55        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2817      | 33.8%   |
| 1 x Nvidia              | 1852      | 22.22%  |
| 1 x AMD                 | 1800      | 21.6%   |
| Intel + Nvidia          | 1210      | 14.52%  |
| AMD + Nvidia            | 225       | 2.7%    |
| Intel + AMD             | 202       | 2.42%   |
| 2 x AMD                 | 136       | 1.63%   |
| 2 x Nvidia              | 42        | 0.5%    |
| Other                   | 17        | 0.2%    |
| 1 x SiS                 | 8         | 0.1%    |
| 1 x Matrox              | 8         | 0.1%    |
| Nvidia + Matrox         | 3         | 0.04%   |
| Nvidia + ASPEED         | 3         | 0.04%   |
| Intel + 2 x Nvidia      | 3         | 0.04%   |
| AMD + Matrox            | 2         | 0.02%   |
| 5 x Nvidia              | 1         | 0.01%   |
| 4 x Nvidia              | 1         | 0.01%   |
| 3 x Nvidia              | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 5300      | 63.52%  |
| Proprietary | 2692      | 32.26%  |
| Unknown     | 352       | 4.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 5553      | 65.93%  |
| 1.01-2.0   | 631       | 7.49%   |
| 3.01-4.0   | 593       | 7.04%   |
| 7.01-8.0   | 546       | 6.48%   |
| 5.01-6.0   | 414       | 4.92%   |
| 0.01-0.5   | 259       | 3.08%   |
| 0.51-1.0   | 179       | 2.13%   |
| 8.01-16.0  | 144       | 1.71%   |
| 2.01-3.0   | 80        | 0.95%   |
| 16.01-24.0 | 18        | 0.21%   |
| 4.01-5.0   | 3         | 0.04%   |
| 32.01-64.0 | 1         | 0.01%   |
| 24.01-32.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1131      | 12.07%  |
| AU Optronics            | 1018      | 10.86%  |
| Chimei Innolux          | 802       | 8.56%   |
| LG Display              | 800       | 8.54%   |
| BOE                     | 718       | 7.66%   |
| Goldstar                | 619       | 6.6%    |
| Dell                    | 585       | 6.24%   |
| Acer                    | 381       | 4.07%   |
| Hewlett-Packard         | 285       | 3.04%   |
| Apple                   | 266       | 2.84%   |
| AOC                     | 264       | 2.82%   |
| Sharp                   | 218       | 2.33%   |
| Ancor Communications    | 217       | 2.32%   |
| BenQ                    | 213       | 2.27%   |
| Philips                 | 152       | 1.62%   |
| ASUSTek Computer        | 149       | 1.59%   |
| Lenovo                  | 139       | 1.48%   |
| PANDA                   | 135       | 1.44%   |
| ViewSonic               | 86        | 0.92%   |
| Chi Mei Optoelectronics | 82        | 0.87%   |
| Sony                    | 66        | 0.7%    |
| Iiyama                  | 66        | 0.7%    |
| InfoVision              | 55        | 0.59%   |
| MSI                     | 52        | 0.55%   |
| Sceptre Tech            | 47        | 0.5%    |
| Vizio                   | 41        | 0.44%   |
| Panasonic               | 41        | 0.44%   |
| Toshiba                 | 31        | 0.33%   |
| CSO                     | 27        | 0.29%   |
| Unknown                 | 24        | 0.26%   |
| Gigabyte Technology     | 24        | 0.26%   |
| Eizo                    | 20        | 0.21%   |
| Fujitsu Siemens         | 19        | 0.2%    |
| Insignia                | 18        | 0.19%   |
| NEC Computers           | 17        | 0.18%   |
| Hitachi                 | 17        | 0.18%   |
| Vestel Elektronik       | 16        | 0.17%   |
| LG Electronics          | 16        | 0.17%   |
| MStar                   | 15        | 0.16%   |
| TMX                     | 14        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 68        | 0.7%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 61        | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 55        | 0.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 44        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 43        | 0.45%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 41        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 39        | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 38        | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 34        | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 33        | 0.34%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 28        | 0.29%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 27        | 0.28%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 25        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 25        | 0.26%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 25        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 24        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 24        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 24        | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 23        | 0.24%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 23        | 0.24%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                | 23        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 23        | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 22        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 21        | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 21        | 0.22%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                    | 21        | 0.22%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 20        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 20        | 0.21%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 19        | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 19        | 0.2%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                     | 19        | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 19        | 0.2%    |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 18        | 0.19%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 18        | 0.19%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 18        | 0.19%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 18        | 0.19%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 17        | 0.18%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 17        | 0.18%   |
| AOC 24B1W1G5 AOC2401 1920x1080 527x296mm 23.8-inch                    | 17        | 0.18%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 16        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4171      | 47.21%  |
| 1366x768 (WXGA)    | 1394      | 15.78%  |
| 3840x2160 (4K)     | 752       | 8.51%   |
| 2560x1440 (QHD)    | 534       | 6.04%   |
| 1600x900 (HD+)     | 287       | 3.25%   |
| 1920x1200 (WUXGA)  | 197       | 2.23%   |
| 1680x1050 (WSXGA+) | 173       | 1.96%   |
| 1440x900 (WXGA+)   | 172       | 1.95%   |
| 2560x1080          | 164       | 1.86%   |
| 3440x1440          | 158       | 1.79%   |
| 1280x1024 (SXGA)   | 152       | 1.72%   |
| 1280x800 (WXGA)    | 118       | 1.34%   |
| 2560x1600          | 79        | 0.89%   |
| 1360x768           | 58        | 0.66%   |
| 2880x1800          | 55        | 0.62%   |
| 1920x540           | 42        | 0.48%   |
| 3840x1080          | 41        | 0.46%   |
| 3840x2400          | 32        | 0.36%   |
| Unknown            | 30        | 0.34%   |
| 2160x1440          | 29        | 0.33%   |
| 3200x1800 (QHD+)   | 17        | 0.19%   |
| 2736x1824          | 16        | 0.18%   |
| 2256x1504          | 15        | 0.17%   |
| 3840x1600          | 14        | 0.16%   |
| 1024x768 (XGA)     | 14        | 0.16%   |
| 3000x2000          | 13        | 0.15%   |
| 1600x1200          | 13        | 0.15%   |
| 1280x720 (HD)      | 12        | 0.14%   |
| 3456x2160          | 6         | 0.07%   |
| 3200x2000          | 6         | 0.07%   |
| 2048x1152          | 5         | 0.06%   |
| 3840x1200          | 4         | 0.05%   |
| 1920x1280          | 4         | 0.05%   |
| 3840x1100          | 3         | 0.03%   |
| 3072x1920          | 3         | 0.03%   |
| 2560x1700          | 3         | 0.03%   |
| 2288x1287          | 3         | 0.03%   |
| 800x1280           | 2         | 0.02%   |
| 7680x2160          | 2         | 0.02%   |
| 5120x1440          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2368      | 25.3%   |
| 13      | 907       | 9.69%   |
| 27      | 851       | 9.09%   |
| 24      | 722       | 7.72%   |
| 14      | 641       | 6.85%   |
| 23      | 601       | 6.42%   |
| 21      | 478       | 5.11%   |
| 17      | 473       | 5.05%   |
| 31      | 303       | 3.24%   |
| 34      | 274       | 2.93%   |
| 19      | 181       | 1.93%   |
| Unknown | 163       | 1.74%   |
| 18      | 148       | 1.58%   |
| 12      | 141       | 1.51%   |
| 22      | 119       | 1.27%   |
| 20      | 106       | 1.13%   |
| 84      | 94        | 1%      |
| 32      | 82        | 0.88%   |
| 11      | 75        | 0.8%    |
| 72      | 70        | 0.75%   |
| 16      | 65        | 0.69%   |
| 40      | 53        | 0.57%   |
| 54      | 42        | 0.45%   |
| 26      | 39        | 0.42%   |
| 25      | 36        | 0.38%   |
| 48      | 33        | 0.35%   |
| 49      | 25        | 0.27%   |
| 35      | 25        | 0.27%   |
| 28      | 24        | 0.26%   |
| 52      | 22        | 0.24%   |
| 65      | 21        | 0.22%   |
| 46      | 18        | 0.19%   |
| 37      | 16        | 0.17%   |
| 29      | 16        | 0.17%   |
| 47      | 13        | 0.14%   |
| 33      | 13        | 0.14%   |
| 42      | 11        | 0.12%   |
| 43      | 9         | 0.1%    |
| 10      | 8         | 0.09%   |
| 55      | 7         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3499      | 38.2%   |
| 501-600        | 1961      | 21.41%  |
| 401-500        | 927       | 10.12%  |
| 201-300        | 686       | 7.49%   |
| 351-400        | 580       | 6.33%   |
| 601-700        | 459       | 5.01%   |
| 701-800        | 370       | 4.04%   |
| 1001-1500      | 201       | 2.19%   |
| 1501-2000      | 177       | 1.93%   |
| Unknown        | 163       | 1.78%   |
| 801-900        | 108       | 1.18%   |
| 901-1000       | 25        | 0.27%   |
| More than 2000 | 2         | 0.02%   |
| 101-200        | 1         | 0.01%   |
| 1-100          | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 6537      | 79.66%  |
| 16/10   | 889       | 10.83%  |
| 21/9    | 328       | 4%      |
| 5/4     | 150       | 1.83%   |
| Unknown | 96        | 1.17%   |
| 3/2     | 88        | 1.07%   |
| 32/9    | 46        | 0.56%   |
| 4/3     | 45        | 0.55%   |
| 6/5     | 9         | 0.11%   |
| 1.96    | 5         | 0.06%   |
| 3.40    | 3         | 0.04%   |
| 3.20    | 3         | 0.04%   |
| 3.73    | 2         | 0.02%   |
| 0.62    | 2         | 0.02%   |
| 1.00    | 1         | 0.01%   |
| 0.67    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2370      | 25.63%  |
| 201-250        | 1513      | 16.36%  |
| 81-90          | 1212      | 13.11%  |
| 301-350        | 874       | 9.45%   |
| 351-500        | 699       | 7.56%   |
| 151-200        | 429       | 4.64%   |
| 121-130        | 379       | 4.1%    |
| 71-80          | 347       | 3.75%   |
| More than 1000 | 304       | 3.29%   |
| 251-300        | 278       | 3.01%   |
| 141-150        | 188       | 2.03%   |
| 501-1000       | 187       | 2.02%   |
| Unknown        | 163       | 1.76%   |
| 61-70          | 119       | 1.29%   |
| 51-60          | 78        | 0.84%   |
| 111-120        | 51        | 0.55%   |
| 131-140        | 30        | 0.32%   |
| 91-100         | 15        | 0.16%   |
| 41-50          | 8         | 0.09%   |
| 1-40           | 2         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2825      | 31.72%  |
| 121-160       | 2589      | 29.07%  |
| 101-120       | 2237      | 25.12%  |
| 161-240       | 561       | 6.3%    |
| More than 240 | 274       | 3.08%   |
| 1-50          | 257       | 2.89%   |
| Unknown       | 163       | 1.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6299      | 74.62%  |
| 2     | 1532      | 18.15%  |
| 0     | 412       | 4.88%   |
| 3     | 181       | 2.14%   |
| 4     | 15        | 0.18%   |
| 6     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4495      | 35.34%  |
| Intel                             | 4250      | 33.41%  |
| Qualcomm Atheros                  | 1365      | 10.73%  |
| Broadcom                          | 746       | 5.86%   |
| Broadcom Limited                  | 171       | 1.34%   |
| TP-Link                           | 144       | 1.13%   |
| MediaTek                          | 141       | 1.11%   |
| Ralink Technology                 | 140       | 1.1%    |
| Marvell Technology Group          | 125       | 0.98%   |
| Nvidia                            | 111       | 0.87%   |
| Ralink                            | 94        | 0.74%   |
| Samsung Electronics               | 75        | 0.59%   |
| Microsoft                         | 71        | 0.56%   |
| ASIX Electronics                  | 61        | 0.48%   |
| NetGear                           | 47        | 0.37%   |
| Xiaomi                            | 40        | 0.31%   |
| Qualcomm Atheros Communications   | 37        | 0.29%   |
| DisplayLink                       | 36        | 0.28%   |
| InterBiometrics                   | 33        | 0.26%   |
| Google                            | 33        | 0.26%   |
| Aquantia                          | 32        | 0.25%   |
| D-Link                            | 29        | 0.23%   |
| Lenovo                            | 27        | 0.21%   |
| Huawei Technologies               | 27        | 0.21%   |
| Dell                              | 27        | 0.21%   |
| ASUSTek Computer                  | 27        | 0.21%   |
| Sierra Wireless                   | 23        | 0.18%   |
| Qualcomm                          | 21        | 0.17%   |
| Linksys                           | 20        | 0.16%   |
| Ericsson Business Mobile Networks | 20        | 0.16%   |
| JMicron Technology                | 17        | 0.13%   |
| OnePlus Technology (Shenzhen)     | 16        | 0.13%   |
| Motorola PCS                      | 15        | 0.12%   |
| Edimax Technology                 | 15        | 0.12%   |
| Hewlett-Packard                   | 12        | 0.09%   |
| OPPO Electronics                  | 11        | 0.09%   |
| D-Link System                     | 11        | 0.09%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.07%   |
| Belkin Components                 | 9         | 0.07%   |
| Apple                             | 8         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3128      | 20.98%  |
| Intel Wi-Fi 6 AX200                                               | 654       | 4.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 446       | 2.99%   |
| Intel I211 Gigabit Network Connection                             | 380       | 2.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 288       | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 257       | 1.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 250       | 1.68%   |
| Intel Wireless 8265 / 8275                                        | 246       | 1.65%   |
| Realtek RTL8125 2.5GbE Controller                                 | 231       | 1.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 203       | 1.36%   |
| Intel Wi-Fi 6 AX201                                               | 186       | 1.25%   |
| Intel Wireless 7265                                               | 183       | 1.23%   |
| Intel Wireless 7260                                               | 173       | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 171       | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 169       | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 166       | 1.11%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 156       | 1.05%   |
| Intel Wireless 8260                                               | 155       | 1.04%   |
| Intel Wireless-AC 9260                                            | 147       | 0.99%   |
| Intel Ethernet Connection (2) I219-V                              | 146       | 0.98%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 139       | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 138       | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 133       | 0.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 133       | 0.89%   |
| Intel Ethernet Controller I225-V                                  | 125       | 0.84%   |
| Intel Ethernet Connection I217-LM                                 | 113       | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 109       | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 106       | 0.71%   |
| Intel Ethernet Connection (7) I219-V                              | 103       | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 97        | 0.65%   |
| Intel Wireless 3165                                               | 96        | 0.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 84        | 0.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 83        | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 81        | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 81        | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 74        | 0.5%    |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 73        | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 71        | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 68        | 0.46%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 68        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3346      | 47.36%  |
| Qualcomm Atheros                      | 1059      | 14.99%  |
| Realtek Semiconductor                 | 1057      | 14.96%  |
| Broadcom                              | 570       | 8.07%   |
| Ralink Technology                     | 140       | 1.98%   |
| MediaTek                              | 132       | 1.87%   |
| Broadcom Limited                      | 132       | 1.87%   |
| TP-Link                               | 131       | 1.85%   |
| Ralink                                | 94        | 1.33%   |
| Microsoft                             | 66        | 0.93%   |
| NetGear                               | 45        | 0.64%   |
| Qualcomm Atheros Communications       | 37        | 0.52%   |
| Marvell Technology Group              | 34        | 0.48%   |
| D-Link                                | 28        | 0.4%    |
| ASUSTek Computer                      | 25        | 0.35%   |
| Dell                                  | 24        | 0.34%   |
| Sierra Wireless                       | 23        | 0.33%   |
| Linksys                               | 16        | 0.23%   |
| Qualcomm                              | 15        | 0.21%   |
| Edimax Technology                     | 15        | 0.21%   |
| Belkin Components                     | 9         | 0.13%   |
| D-Link System                         | 7         | 0.1%    |
| AVM                                   | 7         | 0.1%    |
| Sitecom Europe                        | 6         | 0.08%   |
| Fibocom                               | 6         | 0.08%   |
| Gemtek                                | 5         | 0.07%   |
| Mercucys                              | 4         | 0.06%   |
| Hewlett-Packard                       | 4         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.06%   |
| IMC Networks                          | 3         | 0.04%   |
| Accton Technology                     | 3         | 0.04%   |
| Wilocity                              | 2         | 0.03%   |
| Samsung Electronics                   | 2         | 0.03%   |
| Ovislink                              | 2         | 0.03%   |
| Micro Star International              | 2         | 0.03%   |
| Ericsson Business Mobile Networks     | 2         | 0.03%   |
| ZyDAS                                 | 1         | 0.01%   |
| Wacom                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Texas Instruments                     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 654       | 9.18%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 257       | 3.61%   |
| Intel Wireless 8265 / 8275                                     | 246       | 3.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 203       | 2.85%   |
| Intel Wi-Fi 6 AX201                                            | 186       | 2.61%   |
| Intel Wireless 7265                                            | 183       | 2.57%   |
| Intel Wireless 7260                                            | 173       | 2.43%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 171       | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 169       | 2.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 166       | 2.33%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 156       | 2.19%   |
| Intel Wireless 8260                                            | 155       | 2.18%   |
| Intel Wireless-AC 9260                                         | 147       | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 139       | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 138       | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 133       | 1.87%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 133       | 1.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 109       | 1.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 106       | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 97        | 1.36%   |
| Intel Wireless 3165                                            | 96        | 1.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 84        | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 83        | 1.17%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 81        | 1.14%   |
| Broadcom BCM43142 802.11b/g/n                                  | 81        | 1.14%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 74        | 1.04%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 73        | 1.03%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 68        | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 66        | 0.93%   |
| Realtek 802.11ac NIC                                           | 65        | 0.91%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 64        | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 62        | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 61        | 0.86%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 61        | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 57        | 0.8%    |
| Intel Wireless 3160                                            | 56        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 55        | 0.77%   |
| Ralink MT7601U Wireless Adapter                                | 52        | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 50        | 0.7%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 49        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 4076      | 54.17%  |
| Intel                            | 2001      | 26.59%  |
| Qualcomm Atheros                 | 416       | 5.53%   |
| Broadcom                         | 306       | 4.07%   |
| Nvidia                           | 111       | 1.48%   |
| Marvell Technology Group         | 91        | 1.21%   |
| Samsung Electronics              | 73        | 0.97%   |
| ASIX Electronics                 | 61        | 0.81%   |
| Broadcom Limited                 | 43        | 0.57%   |
| Xiaomi                           | 40        | 0.53%   |
| DisplayLink                      | 36        | 0.48%   |
| Google                           | 33        | 0.44%   |
| Aquantia                         | 32        | 0.43%   |
| Lenovo                           | 27        | 0.36%   |
| Huawei Technologies              | 24        | 0.32%   |
| JMicron Technology               | 17        | 0.23%   |
| TP-Link                          | 13        | 0.17%   |
| OnePlus Technology (Shenzhen)    | 13        | 0.17%   |
| OPPO Electronics                 | 11        | 0.15%   |
| Motorola PCS                     | 11        | 0.15%   |
| Silicon Integrated Systems [SiS] | 9         | 0.12%   |
| MediaTek                         | 8         | 0.11%   |
| Qualcomm                         | 6         | 0.08%   |
| Apple                            | 6         | 0.08%   |
| VIA Technologies                 | 5         | 0.07%   |
| Microsoft                        | 5         | 0.07%   |
| ICS Advent                       | 5         | 0.07%   |
| Linksys                          | 4         | 0.05%   |
| D-Link System                    | 4         | 0.05%   |
| Mellanox Technologies            | 3         | 0.04%   |
| LG Electronics                   | 3         | 0.04%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.03%   |
| T & A Mobile Phones              | 2         | 0.03%   |
| NetGear                          | 2         | 0.03%   |
| LSI                              | 2         | 0.03%   |
| Hewlett-Packard                  | 2         | 0.03%   |
| ASUSTek Computer                 | 2         | 0.03%   |
| 3Com                             | 2         | 0.03%   |
| Tehuti Networks                  | 1         | 0.01%   |
| Solarflare Communications        | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3128      | 40.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 446       | 5.82%   |
| Intel I211 Gigabit Network Connection                             | 380       | 4.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 288       | 3.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 250       | 3.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 231       | 3.01%   |
| Intel Ethernet Connection (2) I219-V                              | 146       | 1.9%    |
| Intel Ethernet Controller I225-V                                  | 125       | 1.63%   |
| Intel Ethernet Connection I217-LM                                 | 113       | 1.47%   |
| Intel Ethernet Connection (7) I219-V                              | 103       | 1.34%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 71        | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 68        | 0.89%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 66        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 57        | 0.74%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 55        | 0.72%   |
| Intel Ethernet Connection I219-LM                                 | 53        | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 53        | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 52        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 51        | 0.67%   |
| Nvidia MCP79 Ethernet                                             | 51        | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 46        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 46        | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 45        | 0.59%   |
| Intel Ethernet Connection (2) I218-V                              | 45        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 43        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 41        | 0.53%   |
| Nvidia MCP61 Ethernet                                             | 35        | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 35        | 0.46%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 35        | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 35        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 34        | 0.44%   |
| Intel Ethernet Connection (3) I218-LM                             | 34        | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 32        | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.4%    |
| Intel 82577LM Gigabit Network Connection                          | 31        | 0.4%    |
| Intel I210 Gigabit Network Connection                             | 30        | 0.39%   |
| Intel Ethernet Connection (7) I219-LM                             | 30        | 0.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 28        | 0.37%   |
| Google Nexus/Pixel Device (tether)                                | 26        | 0.34%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7022      | 50.86%  |
| WiFi     | 6669      | 48.31%  |
| Modem    | 90        | 0.65%   |
| Unknown  | 25        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 5178      | 59.26%  |
| Ethernet | 3557      | 40.71%  |
| Unknown  | 3         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4604      | 55.63%  |
| 1     | 3333      | 40.27%  |
| 3     | 197       | 2.38%   |
| 0     | 104       | 1.26%   |
| 4     | 29        | 0.35%   |
| 5     | 5         | 0.06%   |
| 10    | 2         | 0.02%   |
| 6     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 6637      | 79.3%   |
| Yes  | 1733      | 20.7%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2906      | 51.79%  |
| Qualcomm Atheros Communications | 443       | 7.9%    |
| Realtek Semiconductor           | 439       | 7.82%   |
| Apple                           | 322       | 5.74%   |
| Cambridge Silicon Radio         | 313       | 5.58%   |
| Broadcom                        | 245       | 4.37%   |
| IMC Networks                    | 222       | 3.96%   |
| Lite-On Technology              | 191       | 3.4%    |
| Foxconn / Hon Hai               | 126       | 2.25%   |
| ASUSTek Computer                | 97        | 1.73%   |
| Dell                            | 62        | 1.1%    |
| Marvell Semiconductor           | 36        | 0.64%   |
| Ralink                          | 30        | 0.53%   |
| Realtek                         | 29        | 0.52%   |
| Hewlett-Packard                 | 29        | 0.52%   |
| Toshiba                         | 28        | 0.5%    |
| MediaTek                        | 12        | 0.21%   |
| Foxconn International           | 11        | 0.2%    |
| TP-Link                         | 7         | 0.12%   |
| Ralink Technology               | 7         | 0.12%   |
| Alps Electric                   | 7         | 0.12%   |
| Dynex                           | 6         | 0.11%   |
| HTC (High Tech Computer)        | 4         | 0.07%   |
| Askey Computer                  | 4         | 0.07%   |
| USI                             | 3         | 0.05%   |
| Unknown                         | 3         | 0.05%   |
| Taiyo Yuden                     | 3         | 0.05%   |
| SIN                             | 3         | 0.05%   |
| Qcom                            | 3         | 0.05%   |
| Opticis                         | 3         | 0.05%   |
| Integrated System Solution      | 3         | 0.05%   |
| Creative Technology             | 3         | 0.05%   |
| Micro Star International        | 2         | 0.04%   |
| Conwise Technology              | 2         | 0.04%   |
| Belkin Components               | 2         | 0.04%   |
| Primax Electronics              | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |
| Actions                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 881       | 15.69%  |
| Intel AX200 Bluetooth                               | 626       | 11.15%  |
| Intel Bluetooth Device                              | 539       | 9.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 412       | 7.34%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 313       | 5.57%   |
| Realtek Bluetooth Radio                             | 271       | 4.83%   |
| Qualcomm Atheros  Bluetooth Device                  | 243       | 4.33%   |
| Apple Bluetooth Host Controller                     | 139       | 2.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 138       | 2.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 131       | 2.33%   |
| Realtek  Bluetooth 4.2 Adapter                      | 115       | 2.05%   |
| Lite-On Bluetooth Device                            | 115       | 2.05%   |
| Apple Bluetooth USB Host Controller                 | 115       | 2.05%   |
| Intel AX210 Bluetooth                               | 79        | 1.41%   |
| IMC Networks Bluetooth Radio                        | 72        | 1.28%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 68        | 1.21%   |
| IMC Networks Wireless_Device                        | 56        | 1%      |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 55        | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                  | 55        | 0.98%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 51        | 0.91%   |
| IMC Networks Bluetooth Device                       | 48        | 0.85%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 45        | 0.8%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 43        | 0.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 40        | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 38        | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 37        | 0.66%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 31        | 0.55%   |
| Ralink RT3290 Bluetooth                             | 30        | 0.53%   |
| Apple Bluetooth HCI                                 | 30        | 0.53%   |
| Realtek Bluetooth Radio                             | 29        | 0.52%   |
| Foxconn / Hon Hai Wireless_Device                   | 29        | 0.52%   |
| Broadcom BCM2045B (BDC-2.1)                         | 28        | 0.5%    |
| Marvell Bluetooth and Wireless LAN Composite        | 24        | 0.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 24        | 0.43%   |
| Dell DW375 Bluetooth Module                         | 22        | 0.39%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 21        | 0.37%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.37%   |
| ASUS Bluetooth Radio                                | 21        | 0.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 19        | 0.34%   |
| Realtek RTL8821A Bluetooth                          | 18        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 5592      | 44.47%  |
| AMD                                             | 2796      | 22.23%  |
| Nvidia                                          | 2654      | 21.1%   |
| C-Media Electronics                             | 223       | 1.77%   |
| Logitech                                        | 125       | 0.99%   |
| JMTek                                           | 68        | 0.54%   |
| Creative Labs                                   | 65        | 0.52%   |
| Kingston Technology                             | 60        | 0.48%   |
| Razer USA                                       | 59        | 0.47%   |
| Texas Instruments                               | 55        | 0.44%   |
| Corsair                                         | 54        | 0.43%   |
| Realtek Semiconductor                           | 50        | 0.4%    |
| SteelSeries ApS                                 | 44        | 0.35%   |
| Focusrite-Novation                              | 41        | 0.33%   |
| ASUSTek Computer                                | 35        | 0.28%   |
| GN Netcom                                       | 33        | 0.26%   |
| Generalplus Technology                          | 30        | 0.24%   |
| Creative Technology                             | 30        | 0.24%   |
| Blue Microphones                                | 28        | 0.22%   |
| Lenovo                                          | 26        | 0.21%   |
| Sony                                            | 23        | 0.18%   |
| Plantronics                                     | 19        | 0.15%   |
| Astro Gaming                                    | 17        | 0.14%   |
| Apple                                           | 17        | 0.14%   |
| Giga-Byte Technology                            | 15        | 0.12%   |
| Tenx Technology                                 | 14        | 0.11%   |
| Samson Technologies                             | 14        | 0.11%   |
| Micro Star International                        | 14        | 0.11%   |
| Hewlett-Packard                                 | 14        | 0.11%   |
| Yamaha                                          | 12        | 0.1%    |
| Turtle Beach                                    | 12        | 0.1%    |
| FiiO Electronics Technology                     | 12        | 0.1%    |
| Sennheiser Communications                       | 11        | 0.09%   |
| SAVITECH                                        | 11        | 0.09%   |
| Thesycon Systemsoftware & Consulting            | 10        | 0.08%   |
| Silicon Integrated Systems [SiS]                | 10        | 0.08%   |
| M-Audio                                         | 10        | 0.08%   |
| Valve Software                                  | 9         | 0.07%   |
| Licensed by Sony Computer Entertainment America | 9         | 0.07%   |
| DSEA A/S                                        | 9         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 857       | 5.73%   |
| AMD Starship/Matisse HD Audio Controller                                   | 647       | 4.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 626       | 4.19%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 542       | 3.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 519       | 3.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 458       | 3.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 399       | 2.67%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 389       | 2.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 312       | 2.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 291       | 1.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 252       | 1.69%   |
| Intel 8 Series HD Audio Controller                                         | 252       | 1.69%   |
| Intel Haswell-ULT HD Audio Controller                                      | 248       | 1.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 244       | 1.63%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 242       | 1.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 241       | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                            | 226       | 1.51%   |
| Nvidia TU106 High Definition Audio Controller                              | 225       | 1.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 207       | 1.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 205       | 1.37%   |
| AMD FCH Azalia Controller                                                  | 205       | 1.37%   |
| Intel Comet Lake PCH cAVS                                                  | 202       | 1.35%   |
| Nvidia GP104 High Definition Audio Controller                              | 196       | 1.31%   |
| Nvidia TU116 High Definition Audio Controller                              | 181       | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 181       | 1.21%   |
| Nvidia GP106 High Definition Audio Controller                              | 179       | 1.2%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 175       | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 172       | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 170       | 1.14%   |
| Intel Broadwell-U Audio Controller                                         | 168       | 1.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 159       | 1.06%   |
| AMD Navi 10 HDMI Audio                                                     | 154       | 1.03%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 143       | 0.96%   |
| Intel CM238 HD Audio Controller                                            | 133       | 0.89%   |
| Nvidia GA104 High Definition Audio Controller                              | 132       | 0.88%   |
| Nvidia TU104 HD Audio Controller                                           | 126       | 0.84%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 126       | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 110       | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                              | 105       | 0.7%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 100       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 513       | 23.08%  |
| SK hynix            | 393       | 17.68%  |
| Micron Technology   | 241       | 10.84%  |
| Kingston            | 240       | 10.8%   |
| Corsair             | 158       | 7.11%   |
| Crucial             | 149       | 6.7%    |
| Unknown             | 110       | 4.95%   |
| G.Skill             | 102       | 4.59%   |
| A-DATA Technology   | 51        | 2.29%   |
| Team                | 30        | 1.35%   |
| Smart               | 29        | 1.3%    |
| Ramaxel Technology  | 27        | 1.21%   |
| Goldkey             | 21        | 0.94%   |
| Elpida              | 21        | 0.94%   |
| Neo Forza           | 18        | 0.81%   |
| Unknown             | 13        | 0.58%   |
| Unknown (ABCD)      | 12        | 0.54%   |
| Patriot             | 11        | 0.49%   |
| Smart Brazil        | 10        | 0.45%   |
| Teikon              | 7         | 0.31%   |
| Nanya Technology    | 7         | 0.31%   |
| Apacer              | 6         | 0.27%   |
| Avant               | 5         | 0.22%   |
| Transcend           | 3         | 0.13%   |
| Silicon Power       | 3         | 0.13%   |
| PNY                 | 3         | 0.13%   |
| High Bridge         | 3         | 0.13%   |
| GOODRAM             | 3         | 0.13%   |
| Timetec             | 2         | 0.09%   |
| Patriot Memory      | 2         | 0.09%   |
| OLOY                | 2         | 0.09%   |
| GSkill              | 2         | 0.09%   |
| Gold Key            | 2         | 0.09%   |
| CSX                 | 2         | 0.09%   |
| ChangXin Memory     | 2         | 0.09%   |
| AMD                 | 2         | 0.09%   |
| Unknown (8A02)      | 1         | 0.04%   |
| Unknown (898F)      | 1         | 0.04%   |
| Unifosa             | 1         | 0.04%   |
| Toshiba             | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 39        | 1.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 30        | 1.28%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 28        | 1.2%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.03%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 20        | 0.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 0.81%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 19        | 0.81%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 18        | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 17        | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 16        | 0.68%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 15        | 0.64%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.6%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 0.6%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.6%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 13        | 0.56%   |
| Unknown                                                          | 13        | 0.56%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.51%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 12        | 0.51%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 12        | 0.51%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 11        | 0.47%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.43%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.43%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 10        | 0.43%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 9         | 0.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.39%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.39%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 9         | 0.39%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 9         | 0.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.39%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 9         | 0.39%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.34%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.34%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1302      | 67.95%  |
| DDR3    | 375       | 19.57%  |
| LPDDR4  | 80        | 4.18%   |
| LPDDR3  | 68        | 3.55%   |
| DDR2    | 23        | 1.2%    |
| DDR5    | 21        | 1.1%    |
| Unknown | 19        | 0.99%   |
| LPDDR5  | 15        | 0.78%   |
| SDRAM   | 11        | 0.57%   |
| DDR     | 2         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1187      | 61.31%  |
| DIMM         | 533       | 27.53%  |
| Row Of Chips | 202       | 10.43%  |
| Chip         | 12        | 0.62%   |
| RIMM         | 1         | 0.05%   |
| Unknown      | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 959       | 46.24%  |
| 4096  | 467       | 22.52%  |
| 16384 | 410       | 19.77%  |
| 2048  | 110       | 5.3%    |
| 32768 | 107       | 5.16%   |
| 1024  | 19        | 0.92%   |
| 512   | 2         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 448       | 21.58%  |
| 3200    | 432       | 20.81%  |
| 1600    | 264       | 12.72%  |
| 2400    | 184       | 8.86%   |
| 2133    | 113       | 5.44%   |
| 3600    | 106       | 5.11%   |
| 1333    | 72        | 3.47%   |
| 4267    | 42        | 2.02%   |
| 1867    | 38        | 1.83%   |
| 3266    | 29        | 1.4%    |
| 1334    | 28        | 1.35%   |
| 3000    | 26        | 1.25%   |
| 3400    | 22        | 1.06%   |
| 4800    | 20        | 0.96%   |
| 8400    | 19        | 0.92%   |
| 800     | 19        | 0.92%   |
| 3733    | 17        | 0.82%   |
| 3466    | 17        | 0.82%   |
| 6400    | 16        | 0.77%   |
| 3866    | 15        | 0.72%   |
| 2933    | 15        | 0.72%   |
| 4266    | 13        | 0.63%   |
| 3800    | 12        | 0.58%   |
| 1866    | 12        | 0.58%   |
| 1067    | 11        | 0.53%   |
| 667     | 11        | 0.53%   |
| 2800    | 9         | 0.43%   |
| 2666    | 8         | 0.39%   |
| Unknown | 8         | 0.39%   |
| 3333    | 5         | 0.24%   |
| 1800    | 4         | 0.19%   |
| 4400    | 3         | 0.14%   |
| 4000    | 3         | 0.14%   |
| 3666    | 3         | 0.14%   |
| 3100    | 3         | 0.14%   |
| 1066    | 3         | 0.14%   |
| 4199    | 2         | 0.1%    |
| 3533    | 2         | 0.1%    |
| 3334    | 2         | 0.1%    |
| 3151    | 2         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 52        | 31.33%  |
| Brother Industries    | 33        | 19.88%  |
| Canon                 | 26        | 15.66%  |
| Seiko Epson           | 18        | 10.84%  |
| Samsung Electronics   | 18        | 10.84%  |
| Dymo-CoStar           | 4         | 2.41%   |
| Fuji Xerox            | 3         | 1.81%   |
| Xerox                 | 2         | 1.2%    |
| QinHeng Electronics   | 2         | 1.2%    |
| STMicroelectronics    | 1         | 0.6%    |
| Prolific Technology   | 1         | 0.6%    |
| Oki Data              | 1         | 0.6%    |
| MIIIW                 | 1         | 0.6%    |
| Lexmark International | 1         | 0.6%    |
| Kyocera               | 1         | 0.6%    |
| ICS Advent            | 1         | 0.6%    |
| Apple                 | 1         | 0.6%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP Deskjet 3050 J610 series                                | 5         | 2.99%   |
| Seiko Epson ET-2700 Series                                 | 3         | 1.8%    |
| Samsung SCX-3400 Series                                    | 3         | 1.8%    |
| Samsung ML-1640 Series Laser Printer                       | 3         | 1.8%    |
| Samsung M2020 Series                                       | 3         | 1.8%    |
| Canon PIXMA MX920 Series                                   | 3         | 1.8%    |
| Brother Printer                                            | 3         | 1.8%    |
| Brother HL-2270DW Laser Printer                            | 3         | 1.8%    |
| Brother HL-2130 series                                     | 3         | 1.8%    |
| Seiko Epson WF-3520 Series                                 | 2         | 1.2%    |
| Seiko Epson L396 Series                                    | 2         | 1.2%    |
| Seiko Epson L355 Series                                    | 2         | 1.2%    |
| Seiko Epson L3110 Series                                   | 2         | 1.2%    |
| Samsung M2070 Series                                       | 2         | 1.2%    |
| QinHeng CH340S                                             | 2         | 1.2%    |
| HP LaserJet Professional P 1102w                           | 2         | 1.2%    |
| HP ENVY Photo 6200 series                                  | 2         | 1.2%    |
| HP ENVY 4520 series                                        | 2         | 1.2%    |
| HP ENVY 4500 series                                        | 2         | 1.2%    |
| HP DeskJet F4100 Printer series                            | 2         | 1.2%    |
| HP Deskjet 2540 series                                     | 2         | 1.2%    |
| HP Deskjet 1000 J110 series                                | 2         | 1.2%    |
| Fuji Xerox DocuPrint CM315/318 z                           | 2         | 1.2%    |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                     | 2         | 1.2%    |
| Canon PIXMA MG2500 Series                                  | 2         | 1.2%    |
| Brother HL-L3230CDW series                                 | 2         | 1.2%    |
| Brother HL-1110 series                                     | 2         | 1.2%    |
| Xerox Phaser 6000B                                         | 1         | 0.6%    |
| Xerox B215                                                 | 1         | 0.6%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 1         | 0.6%    |
| Seiko Epson WF-4830 Series                                 | 1         | 0.6%    |
| Seiko Epson L365 Series                                    | 1         | 0.6%    |
| Seiko Epson L132 Series                                    | 1         | 0.6%    |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 0.6%    |
| Seiko Epson ET-3760 Series                                 | 1         | 0.6%    |
| Seiko Epson ET-3750 Series                                 | 1         | 0.6%    |
| Seiko Epson ET-2800 Series                                 | 1         | 0.6%    |
| Samsung SCX-4200 series                                    | 1         | 0.6%    |
| Samsung ML-2540 Series Laser Printer                       | 1         | 0.6%    |
| Samsung ML-191x/ML-252x Laser Printer                      | 1         | 0.6%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 10        | 62.5%   |
| Seiko Epson     | 3         | 18.75%  |
| Hewlett-Packard | 2         | 12.5%   |
| Mustek Systems  | 1         | 6.25%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson Scanner                    | 2         | 12.5%   |
| Canon CanoScan N1240U/LiDE 30          | 2         | 12.5%   |
| Canon CanoScan LiDE 210                | 2         | 12.5%   |
| Seiko Epson GT-X700 [Perfection 4870]  | 1         | 6.25%   |
| Mustek Systems ScanExpress 1200 UB     | 1         | 6.25%   |
| HP Scanjet 300                         | 1         | 6.25%   |
| HP ScanJet 2400c                       | 1         | 6.25%   |
| Canon CanoScan N650U/N656U             | 1         | 6.25%   |
| Canon CanoScan LiDE 60                 | 1         | 6.25%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40 | 1         | 6.25%   |
| Canon CanoScan LiDE 220                | 1         | 6.25%   |
| Canon CanoScan LiDE 200                | 1         | 6.25%   |
| Canon CanoScan LiDE 110                | 1         | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1043      | 20.94%  |
| IMC Networks                           | 468       | 9.4%    |
| Microdia                               | 464       | 9.32%   |
| Acer                                   | 442       | 8.88%   |
| Realtek Semiconductor                  | 375       | 7.53%   |
| Logitech                               | 337       | 6.77%   |
| Sunplus Innovation Technology          | 256       | 5.14%   |
| Apple                                  | 251       | 5.04%   |
| Quanta                                 | 216       | 4.34%   |
| Cheng Uei Precision Industry (Foxlink) | 157       | 3.15%   |
| Suyin                                  | 124       | 2.49%   |
| Syntek                                 | 117       | 2.35%   |
| Lite-On Technology                     | 92        | 1.85%   |
| Microsoft                              | 62        | 1.24%   |
| Silicon Motion                         | 61        | 1.22%   |
| Luxvisions Innotech Limited            | 59        | 1.18%   |
| Samsung Electronics                    | 38        | 0.76%   |
| Ricoh                                  | 37        | 0.74%   |
| Alcor Micro                            | 31        | 0.62%   |
| Generalplus Technology                 | 22        | 0.44%   |
| Z-Star Microelectronics                | 18        | 0.36%   |
| Sonix Technology                       | 17        | 0.34%   |
| ARC International                      | 15        | 0.3%    |
| SunplusIT                              | 14        | 0.28%   |
| Razer USA                              | 14        | 0.28%   |
| MacroSilicon                           | 14        | 0.28%   |
| ALi                                    | 12        | 0.24%   |
| Unknown                                | 10        | 0.2%    |
| Primax Electronics                     | 10        | 0.2%    |
| KYE Systems (Mouse Systems)            | 10        | 0.2%    |
| Jieli Technology                       | 10        | 0.2%    |
| Intel                                  | 10        | 0.2%    |
| DigiTech                               | 10        | 0.2%    |
| Valve Software                         | 9         | 0.18%   |
| Lenovo                                 | 9         | 0.18%   |
| Importek                               | 9         | 0.18%   |
| AVerMedia Technologies                 | 8         | 0.16%   |
| LG Electronics                         | 7         | 0.14%   |
| Creative Technology                    | 7         | 0.14%   |
| OmniVision Technologies                | 6         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD           | 225       | 4.48%   |
| Chicony Integrated Camera               | 194       | 3.86%   |
| IMC Networks USB2.0 HD UVC WebCam       | 150       | 2.98%   |
| Realtek Integrated_Webcam_HD            | 144       | 2.87%   |
| Chicony HD WebCam                       | 142       | 2.83%   |
| IMC Networks Integrated Camera          | 138       | 2.75%   |
| Chicony USB2.0 Camera                   | 96        | 1.91%   |
| Acer Integrated Camera                  | 96        | 1.91%   |
| Acer BisonCam,NB Pro                    | 90        | 1.79%   |
| Apple Built-in iSight                   | 81        | 1.61%   |
| Syntek Integrated Camera                | 73        | 1.45%   |
| Logitech HD Pro Webcam C920             | 72        | 1.43%   |
| Sunplus Integrated_Webcam_HD            | 70        | 1.39%   |
| Logitech Webcam C270                    | 64        | 1.27%   |
| Apple iPhone 5/5C/5S/6/SE               | 58        | 1.15%   |
| Apple FaceTime HD Camera                | 55        | 1.09%   |
| Acer HD Webcam                          | 53        | 1.05%   |
| Quanta HD User Facing                   | 48        | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 46        | 0.92%   |
| Apple FaceTime HD Camera (Built-in)     | 46        | 0.92%   |
| Acer BisonCam, NB Pro                   | 41        | 0.82%   |
| Samsung Galaxy A5 (MTP)                 | 35        | 0.7%    |
| Lite-On Integrated Camera               | 35        | 0.7%    |
| Chicony USB 2.0 Camera                  | 35        | 0.7%    |
| Quanta HD Webcam                        | 32        | 0.64%   |
| Microdia Integrated Webcam              | 32        | 0.64%   |
| Logitech C922 Pro Stream Webcam         | 32        | 0.64%   |
| Chicony Integrated Camera (1280x720@30) | 32        | 0.64%   |
| Chicony HP Wide Vision HD Camera        | 32        | 0.64%   |
| Sunplus HD WebCam                       | 31        | 0.62%   |
| Microdia Webcam Vitade AF               | 31        | 0.62%   |
| Microdia Laptop_Integrated_Webcam_HD    | 29        | 0.58%   |
| Chicony HP HD Camera                    | 29        | 0.58%   |
| Chicony HD User Facing                  | 29        | 0.58%   |
| Sunplus ASUS Webcam                     | 28        | 0.56%   |
| Chicony USB2.0 HD UVC WebCam            | 28        | 0.56%   |
| Acer SunplusIT Integrated Camera        | 28        | 0.56%   |
| Chicony USB2.0 VGA UVC WebCam           | 26        | 0.52%   |
| Acer Lenovo EasyCamera                  | 26        | 0.52%   |
| Acer EasyCamera                         | 26        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 298       | 32.96%  |
| Validity Sensors                   | 255       | 28.21%  |
| Shenzhen Goodix Technology         | 174       | 19.25%  |
| Elan Microelectronics              | 49        | 5.42%   |
| Upek                               | 44        | 4.87%   |
| LighTuning Technology              | 38        | 4.2%    |
| AuthenTec                          | 27        | 2.99%   |
| STMicroelectronics                 | 7         | 0.77%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.33%   |
| Focal-systems.Corp                 | 3         | 0.33%   |
| Samsung Electronics                | 2         | 0.22%   |
| HOLTEK                             | 2         | 0.22%   |
| DigitalPersona                     | 2         | 0.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 112       | 12.39%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 74        | 8.19%   |
| Shenzhen Goodix  Fingerprint Device                                        | 68        | 7.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 60        | 6.64%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 54        | 5.97%   |
| Shenzhen Goodix FingerPrint                                                | 46        | 5.09%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 44        | 4.87%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 40        | 4.42%   |
| Elan ELAN:Fingerprint                                                      | 35        | 3.87%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 3.65%   |
| Synaptics  WBDI                                                            | 23        | 2.54%   |
| Validity Sensors Synaptics WBDI                                            | 20        | 2.21%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 2.21%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 19        | 2.1%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 19        | 2.1%    |
| Validity Sensors VFS491                                                    | 18        | 1.99%   |
| Synaptics WBDI Device                                                      | 18        | 1.99%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 1.66%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.66%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.55%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 1.55%   |
| Elan ELAN:ARM-M4                                                           | 13        | 1.44%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 12        | 1.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 1%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 0.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 0.88%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 0.88%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 0.77%   |
| AuthenTec AES2810                                                          | 7         | 0.77%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 0.66%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.66%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.44%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.44%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.33%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 0.33%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.33%   |
| AuthenTec AES1600                                                          | 3         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 143       | 44.41%  |
| Alcor Micro               | 87        | 27.02%  |
| Upek                      | 28        | 8.7%    |
| O2 Micro                  | 23        | 7.14%   |
| Lenovo                    | 19        | 5.9%    |
| SCM Microsystems          | 7         | 2.17%   |
| OmniKey                   | 5         | 1.55%   |
| Realtek Semiconductor     | 2         | 0.62%   |
| Aladdin Knowledge Systems | 2         | 0.62%   |
| Advanced Card Systems     | 2         | 0.62%   |
| Giesecke & Devrient       | 1         | 0.31%   |
| Gemalto (was Gemplus)     | 1         | 0.31%   |
| Clay Logic                | 1         | 0.31%   |
| Chicony Electronics       | 1         | 0.31%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 86        | 26.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 44        | 13.66%  |
| Broadcom 5880                                                                | 40        | 12.42%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 37        | 11.49%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 8.7%    |
| Broadcom 58200                                                               | 20        | 6.21%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 5.9%    |
| Lenovo Integrated Smart Card Reader                                          | 19        | 5.9%    |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 5         | 1.55%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.24%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.62%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.62%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.62%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.62%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.31%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.31%   |
| OmniKey CardMan 4321                                                         | 1         | 0.31%   |
| OmniKey CardMan 1021                                                         | 1         | 0.31%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.31%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.31%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.31%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.31%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.31%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.31%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.31%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.31%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5817      | 69.19%  |
| 1     | 2115      | 25.16%  |
| 2     | 406       | 4.83%   |
| 3     | 58        | 0.69%   |
| 4     | 8         | 0.1%    |
| 5     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 885       | 29.15%  |
| Net/wireless             | 537       | 17.69%  |
| Graphics card            | 503       | 16.57%  |
| Multimedia controller    | 350       | 11.53%  |
| Chipcard                 | 311       | 10.24%  |
| Bluetooth                | 84        | 2.77%   |
| Communication controller | 57        | 1.88%   |
| Camera                   | 51        | 1.68%   |
| Sound                    | 47        | 1.55%   |
| Unassigned class         | 45        | 1.48%   |
| Net/ethernet             | 41        | 1.35%   |
| Storage                  | 37        | 1.22%   |
| Network                  | 22        | 0.72%   |
| Card reader              | 20        | 0.66%   |
| Storage/raid             | 12        | 0.4%    |
| Storage/ide              | 11        | 0.36%   |
| Modem                    | 9         | 0.3%    |
| Storage/nvme             | 4         | 0.13%   |
| Firewire controller      | 4         | 0.13%   |
| Flash memory             | 2         | 0.07%   |
| Dvb card                 | 2         | 0.07%   |
| Wireless                 | 1         | 0.03%   |
| Unclassified device      | 1         | 0.03%   |

