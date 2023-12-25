NixOS - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for NixOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/NixOS/Desktop/README.md) and [notebooks](/Dist/NixOS/Notebook/README.md).

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

Total: 398

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ZBook 17 G5                 | Notebook    | [ad6c489ffc](https://linux-hardware.org/?probe=ad6c489ffc) | Dec 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [ef18e09b69](https://linux-hardware.org/?probe=ef18e09b69) | Dec 23, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [f67367aa62](https://linux-hardware.org/?probe=f67367aa62) | Dec 23, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a953876b2c](https://linux-hardware.org/?probe=a953876b2c) | Dec 23, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [ac1d637679](https://linux-hardware.org/?probe=ac1d637679) | Dec 21, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [1d8538aeef](https://linux-hardware.org/?probe=1d8538aeef) | Dec 20, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [fb187c2fa4](https://linux-hardware.org/?probe=fb187c2fa4) | Dec 20, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [b6aa52f693](https://linux-hardware.org/?probe=b6aa52f693) | Dec 17, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [73693b1a91](https://linux-hardware.org/?probe=73693b1a91) | Dec 17, 2023 |
| Lenovo        | Legion Y7000 81FW           | Notebook    | [71c27a1bf6](https://linux-hardware.org/?probe=71c27a1bf6) | Dec 17, 2023 |
| Medion        | M14L-256                    | Notebook    | [6cd85934b3](https://linux-hardware.org/?probe=6cd85934b3) | Dec 15, 2023 |
| AZW           | EQ                          | Desktop     | [b6aa615ccf](https://linux-hardware.org/?probe=b6aa615ccf) | Dec 14, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [2982c2a2c6](https://linux-hardware.org/?probe=2982c2a2c6) | Dec 14, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [8617acecda](https://linux-hardware.org/?probe=8617acecda) | Dec 11, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [87be870a89](https://linux-hardware.org/?probe=87be870a89) | Dec 09, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [85d6d037cc](https://linux-hardware.org/?probe=85d6d037cc) | Dec 09, 2023 |
| Dell          | G5 5590                     | Notebook    | [6970987854](https://linux-hardware.org/?probe=6970987854) | Dec 08, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [62c4dde3a6](https://linux-hardware.org/?probe=62c4dde3a6) | Dec 07, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [2ba0c7198a](https://linux-hardware.org/?probe=2ba0c7198a) | Dec 05, 2023 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [5b8e1b7878](https://linux-hardware.org/?probe=5b8e1b7878) | Dec 05, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [aae20908c5](https://linux-hardware.org/?probe=aae20908c5) | Dec 05, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [525166f0d5](https://linux-hardware.org/?probe=525166f0d5) | Dec 04, 2023 |
| AZW           | EQ                          | Desktop     | [c2dedbf2f3](https://linux-hardware.org/?probe=c2dedbf2f3) | Dec 04, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [7273cc93a9](https://linux-hardware.org/?probe=7273cc93a9) | Dec 02, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1784c4c5b0](https://linux-hardware.org/?probe=1784c4c5b0) | Dec 01, 2023 |
| Dell          | 0J91V2 A05                  | Server      | [28e8abbbdf](https://linux-hardware.org/?probe=28e8abbbdf) | Dec 01, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [9f7f83e1ee](https://linux-hardware.org/?probe=9f7f83e1ee) | Nov 28, 2023 |
| retsamarre... | 000-F4423-FBA004-2000-N     | Tablet      | [5f97496a76](https://linux-hardware.org/?probe=5f97496a76) | Nov 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [07e6828b2e](https://linux-hardware.org/?probe=07e6828b2e) | Nov 23, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [05c1dddd8d](https://linux-hardware.org/?probe=05c1dddd8d) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450s 20BX001MU... | Notebook    | [80d4678e90](https://linux-hardware.org/?probe=80d4678e90) | Nov 23, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [602aeb4101](https://linux-hardware.org/?probe=602aeb4101) | Nov 22, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | Notebook    | [4065934176](https://linux-hardware.org/?probe=4065934176) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | Notebook    | [fbde674650](https://linux-hardware.org/?probe=fbde674650) | Nov 22, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [34b2b48e8c](https://linux-hardware.org/?probe=34b2b48e8c) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [494b2a6d2f](https://linux-hardware.org/?probe=494b2a6d2f) | Nov 19, 2023 |
| ASUSTek       | ROG Flow X13 GV301RE_GV3... | Convertible | [576d311bde](https://linux-hardware.org/?probe=576d311bde) | Nov 18, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0820ebd908](https://linux-hardware.org/?probe=0820ebd908) | Nov 16, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [f21a42a965](https://linux-hardware.org/?probe=f21a42a965) | Nov 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ac7deed0de](https://linux-hardware.org/?probe=ac7deed0de) | Nov 16, 2023 |
| ASUSTek       | ROG Strix G513QE_G513QE     | Notebook    | [455efd5541](https://linux-hardware.org/?probe=455efd5541) | Nov 15, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [ce6a10d6a3](https://linux-hardware.org/?probe=ce6a10d6a3) | Nov 15, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [a263ed1c12](https://linux-hardware.org/?probe=a263ed1c12) | Nov 13, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [789eee99a6](https://linux-hardware.org/?probe=789eee99a6) | Nov 12, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | Notebook    | [c55053fa25](https://linux-hardware.org/?probe=c55053fa25) | Nov 12, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [67938dee90](https://linux-hardware.org/?probe=67938dee90) | Nov 12, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [503d3690b0](https://linux-hardware.org/?probe=503d3690b0) | Nov 11, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [dfbaeb29c5](https://linux-hardware.org/?probe=dfbaeb29c5) | Nov 11, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [e0883e3bd0](https://linux-hardware.org/?probe=e0883e3bd0) | Nov 11, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [35b2509d27](https://linux-hardware.org/?probe=35b2509d27) | Nov 10, 2023 |
| Nvidia        | snc302eeh                   | Desktop     | [2b0a14caec](https://linux-hardware.org/?probe=2b0a14caec) | Nov 10, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d9cad8ffde](https://linux-hardware.org/?probe=d9cad8ffde) | Nov 09, 2023 |
| Unknown       | Unknown                     | Soc         | [97dadee998](https://linux-hardware.org/?probe=97dadee998) | Nov 08, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [79e23fd44a](https://linux-hardware.org/?probe=79e23fd44a) | Nov 07, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [2f6078ab72](https://linux-hardware.org/?probe=2f6078ab72) | Nov 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [49b3b70e38](https://linux-hardware.org/?probe=49b3b70e38) | Nov 07, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [1786e4735e](https://linux-hardware.org/?probe=1786e4735e) | Nov 07, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [0ecfad9d87](https://linux-hardware.org/?probe=0ecfad9d87) | Nov 07, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [30416c0355](https://linux-hardware.org/?probe=30416c0355) | Nov 04, 2023 |
| HP            | 83E1                        | Desktop     | [c82d34ebac](https://linux-hardware.org/?probe=c82d34ebac) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [0e5f976d6b](https://linux-hardware.org/?probe=0e5f976d6b) | Nov 02, 2023 |
| Dell          | XPS 9315                    | Notebook    | [6f3e496918](https://linux-hardware.org/?probe=6f3e496918) | Oct 29, 2023 |
| HP            | EliteBook 850 G4            | Notebook    | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b075cf8841](https://linux-hardware.org/?probe=b075cf8841) | Oct 28, 2023 |
| LattePanda    | Sigma                       | Desktop     | [d287cf2d8a](https://linux-hardware.org/?probe=d287cf2d8a) | Oct 26, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [387c91f530](https://linux-hardware.org/?probe=387c91f530) | Oct 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| ECS           | A55F-M3                     | Desktop     | [6da483b400](https://linux-hardware.org/?probe=6da483b400) | Oct 25, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | Notebook    | [a80fcc753e](https://linux-hardware.org/?probe=a80fcc753e) | Oct 25, 2023 |
| MSI           | GE70 2PE                    | Notebook    | [c0bcd133c9](https://linux-hardware.org/?probe=c0bcd133c9) | Oct 22, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Framework     | Laptop                      | Notebook    | [e765d5da63](https://linux-hardware.org/?probe=e765d5da63) | Oct 18, 2023 |
| Unknown       | Apple Mac mini (M1, 2020... | Mini pc     | [e6566d9c7c](https://linux-hardware.org/?probe=e6566d9c7c) | Oct 18, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [da6815d760](https://linux-hardware.org/?probe=da6815d760) | Oct 18, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [11155b7b3a](https://linux-hardware.org/?probe=11155b7b3a) | Oct 13, 2023 |
| Unknown       | HX90                        | Desktop     | [f247716ab0](https://linux-hardware.org/?probe=f247716ab0) | Oct 13, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [ba690b36a3](https://linux-hardware.org/?probe=ba690b36a3) | Oct 12, 2023 |
| MSI           | Prestige 16Studio A13VE     | Notebook    | [0209063983](https://linux-hardware.org/?probe=0209063983) | Oct 12, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [7ff5fe9fdd](https://linux-hardware.org/?probe=7ff5fe9fdd) | Oct 11, 2023 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | Notebook    | [a4d6af03fe](https://linux-hardware.org/?probe=a4d6af03fe) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [801a2a4abf](https://linux-hardware.org/?probe=801a2a4abf) | Oct 09, 2023 |
| Dell          | Latitude E6540              | Notebook    | [fc3ea4bb32](https://linux-hardware.org/?probe=fc3ea4bb32) | Oct 08, 2023 |
| ASUSTek       | P7H55                       | Desktop     | [89472bd2f3](https://linux-hardware.org/?probe=89472bd2f3) | Oct 07, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [90f777d9cc](https://linux-hardware.org/?probe=90f777d9cc) | Oct 07, 2023 |
| Dell          | 08DM12 A01                  | Server      | [9faef398d0](https://linux-hardware.org/?probe=9faef398d0) | Oct 07, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [642a2f5a9b](https://linux-hardware.org/?probe=642a2f5a9b) | Oct 04, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a4fbd5793d](https://linux-hardware.org/?probe=a4fbd5793d) | Oct 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [c67f66f5e3](https://linux-hardware.org/?probe=c67f66f5e3) | Oct 01, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [007bb33fbf](https://linux-hardware.org/?probe=007bb33fbf) | Oct 01, 2023 |
| Dell          | Latitude E6540              | Notebook    | [8fdc000f7e](https://linux-hardware.org/?probe=8fdc000f7e) | Oct 01, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a5de8b78e7](https://linux-hardware.org/?probe=a5de8b78e7) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [1135ddac8e](https://linux-hardware.org/?probe=1135ddac8e) | Sep 30, 2023 |
| MSI           | Z68A-GD65                   | Desktop     | [c0f968740b](https://linux-hardware.org/?probe=c0f968740b) | Sep 29, 2023 |
| Dell          | Latitude 5430               | Notebook    | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | Notebook    | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [1478e1265d](https://linux-hardware.org/?probe=1478e1265d) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [0177e96165](https://linux-hardware.org/?probe=0177e96165) | Sep 28, 2023 |
| HP            | 3397                        | Desktop     | [5c1b3bed0b](https://linux-hardware.org/?probe=5c1b3bed0b) | Sep 28, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [24ff983f95](https://linux-hardware.org/?probe=24ff983f95) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Dell          | Latitude E6540              | Notebook    | [7d9885cd7c](https://linux-hardware.org/?probe=7d9885cd7c) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [bf71bcd90e](https://linux-hardware.org/?probe=bf71bcd90e) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4d2c8f9f07](https://linux-hardware.org/?probe=4d2c8f9f07) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| HP            | 1998                        | Desktop     | [4af6b915c2](https://linux-hardware.org/?probe=4af6b915c2) | Sep 17, 2023 |
| Dell          | Latitude E6540              | Notebook    | [ff29b23e60](https://linux-hardware.org/?probe=ff29b23e60) | Sep 13, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S4RV00    | Notebook    | [8ae7288bf3](https://linux-hardware.org/?probe=8ae7288bf3) | Sep 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | Notebook    | [5778731f85](https://linux-hardware.org/?probe=5778731f85) | Sep 10, 2023 |
| HP            | 8767 A                      | Desktop     | [ce91ccf3a9](https://linux-hardware.org/?probe=ce91ccf3a9) | Sep 09, 2023 |
| Dell          | Precision 5680              | Notebook    | [fdcb7ce5d4](https://linux-hardware.org/?probe=fdcb7ce5d4) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 20HES2RC00    | Notebook    | [390104a086](https://linux-hardware.org/?probe=390104a086) | Aug 28, 2023 |
| Dell          | Wyse 5470                   | Notebook    | [6d45205020](https://linux-hardware.org/?probe=6d45205020) | Aug 27, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E GENE    | Desktop     | [a9a56ae120](https://linux-hardware.org/?probe=a9a56ae120) | Aug 22, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [aed7eacff0](https://linux-hardware.org/?probe=aed7eacff0) | Aug 20, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [9e03b48bf3](https://linux-hardware.org/?probe=9e03b48bf3) | Aug 15, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| AZW           | EQ                          | Desktop     | [4a9aad33f3](https://linux-hardware.org/?probe=4a9aad33f3) | Aug 06, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | Notebook    | [c384115725](https://linux-hardware.org/?probe=c384115725) | Aug 05, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [13c8b276bb](https://linux-hardware.org/?probe=13c8b276bb) | Aug 04, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1abcf2ad6f](https://linux-hardware.org/?probe=1abcf2ad6f) | Aug 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| Teclast       | F5                          | Convertible | [76fcc31a43](https://linux-hardware.org/?probe=76fcc31a43) | Aug 01, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [e452f85fb8](https://linux-hardware.org/?probe=e452f85fb8) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| System76      | Pangolin                    | Notebook    | [3b37a9bedb](https://linux-hardware.org/?probe=3b37a9bedb) | Jul 29, 2023 |
| Alienware     | 17                          | Notebook    | [25f67e59b8](https://linux-hardware.org/?probe=25f67e59b8) | Jul 26, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
| HP            | 1998                        | Desktop     | [ef5201611b](https://linux-hardware.org/?probe=ef5201611b) | Jul 24, 2023 |
| HP            | 1998                        | Desktop     | [5a95ac128d](https://linux-hardware.org/?probe=5a95ac128d) | Jul 24, 2023 |
| AZW           | EQ                          | Desktop     | [e065c16f2c](https://linux-hardware.org/?probe=e065c16f2c) | Jul 23, 2023 |
| AZW           | EQ                          | Desktop     | [46a76eeb81](https://linux-hardware.org/?probe=46a76eeb81) | Jul 23, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8d48a50003](https://linux-hardware.org/?probe=8d48a50003) | Jul 22, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [c29abaca55](https://linux-hardware.org/?probe=c29abaca55) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [59a0d6a7bb](https://linux-hardware.org/?probe=59a0d6a7bb) | Jul 19, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [1e8eeb8513](https://linux-hardware.org/?probe=1e8eeb8513) | Jul 16, 2023 |
| ASUSTek       | Z87-EXPERT                  | Desktop     | [8efa3cf99d](https://linux-hardware.org/?probe=8efa3cf99d) | Jul 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [9bb1b8fbca](https://linux-hardware.org/?probe=9bb1b8fbca) | Jul 12, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [d7afc91d12](https://linux-hardware.org/?probe=d7afc91d12) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| Gigabyte      | TRX40 AORUS MASTER          | Desktop     | [f1c343e2c2](https://linux-hardware.org/?probe=f1c343e2c2) | Jul 02, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | Notebook    | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [f15cf1d31b](https://linux-hardware.org/?probe=f15cf1d31b) | Jul 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4d377fc8b8](https://linux-hardware.org/?probe=4d377fc8b8) | Jul 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [fd56f44c38](https://linux-hardware.org/?probe=fd56f44c38) | Jun 29, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [4c4d870bdb](https://linux-hardware.org/?probe=4c4d870bdb) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [cf6a7757d5](https://linux-hardware.org/?probe=cf6a7757d5) | Jun 26, 2023 |
| Microtech     | CoreBook Lite               | Notebook    | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2812cf43d0](https://linux-hardware.org/?probe=2812cf43d0) | Jun 23, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| MECHREVO      | WUJIE 14                    | Notebook    | [a55e31b287](https://linux-hardware.org/?probe=a55e31b287) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | Notebook    | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | Notebook    | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [85902981fd](https://linux-hardware.org/?probe=85902981fd) | Jun 11, 2023 |
| MACHENIKE     | F117-7P                     | Notebook    | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Acer          | Aspire XC600 v1.0           | Desktop     | [754d228b9b](https://linux-hardware.org/?probe=754d228b9b) | Jun 09, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [309d09ae8c](https://linux-hardware.org/?probe=309d09ae8c) | Jun 03, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4396db2f33](https://linux-hardware.org/?probe=4396db2f33) | May 22, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [aefc60eaea](https://linux-hardware.org/?probe=aefc60eaea) | May 11, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [c40c2cb964](https://linux-hardware.org/?probe=c40c2cb964) | May 10, 2023 |
| Acer          | Spin SP514-51N              | Convertible | [6b23655b4b](https://linux-hardware.org/?probe=6b23655b4b) | May 10, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [29b2378b4b](https://linux-hardware.org/?probe=29b2378b4b) | May 08, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [62b28b69dc](https://linux-hardware.org/?probe=62b28b69dc) | May 08, 2023 |
| UNOWHY        | Y13G011S4EI                 | Notebook    | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [6ee65c19d2](https://linux-hardware.org/?probe=6ee65c19d2) | May 02, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [493bc0b894](https://linux-hardware.org/?probe=493bc0b894) | Apr 29, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| Dell          | 0KFKMF A00                  | All in one  | [cbae954ecc](https://linux-hardware.org/?probe=cbae954ecc) | Apr 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | Notebook    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [b8b51b29ef](https://linux-hardware.org/?probe=b8b51b29ef) | Apr 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [7fd17e2245](https://linux-hardware.org/?probe=7fd17e2245) | Apr 22, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | Notebook    | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [6ce8b7fb26](https://linux-hardware.org/?probe=6ce8b7fb26) | Apr 11, 2023 |
| Dell          | XPS 9320                    | Notebook    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| GPD           | G1621-02                    | Notebook    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [f53ad14ea5](https://linux-hardware.org/?probe=f53ad14ea5) | Mar 13, 2023 |
| ASUSTek       | 1005HA                      | Notebook    | [3326423f04](https://linux-hardware.org/?probe=3326423f04) | Mar 06, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [8bf9dd7b83](https://linux-hardware.org/?probe=8bf9dd7b83) | Mar 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [c4f08a9fc3](https://linux-hardware.org/?probe=c4f08a9fc3) | Mar 04, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c4d51ca1b8](https://linux-hardware.org/?probe=c4d51ca1b8) | Mar 04, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [4f3c01941d](https://linux-hardware.org/?probe=4f3c01941d) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | Notebook    | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [616e689b13](https://linux-hardware.org/?probe=616e689b13) | Feb 19, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [5f59be48e1](https://linux-hardware.org/?probe=5f59be48e1) | Feb 16, 2023 |
| Lenovo        | 13w Yoga 82S1               | Convertible | [68effccd60](https://linux-hardware.org/?probe=68effccd60) | Feb 16, 2023 |
| Teclast       | F5                          | Convertible | [e62bdaaa3b](https://linux-hardware.org/?probe=e62bdaaa3b) | Feb 13, 2023 |
| Teclast       | F5                          | Convertible | [30e30a5c3e](https://linux-hardware.org/?probe=30e30a5c3e) | Feb 13, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8ac9c4b4ef](https://linux-hardware.org/?probe=8ac9c4b4ef) | Feb 09, 2023 |
| Acer          | Switch SW713-51GNP          | Tablet      | [46ecb88f1d](https://linux-hardware.org/?probe=46ecb88f1d) | Feb 08, 2023 |
| MSI           | Z77A-G43                    | Desktop     | [eb768bf205](https://linux-hardware.org/?probe=eb768bf205) | Feb 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [75a3416ebc](https://linux-hardware.org/?probe=75a3416ebc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | Notebook    | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| Blackview     | AceBook 1                   | Notebook    | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [b795f7c940](https://linux-hardware.org/?probe=b795f7c940) | Jan 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [0e4ba05b0f](https://linux-hardware.org/?probe=0e4ba05b0f) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [226b8e5ff8](https://linux-hardware.org/?probe=226b8e5ff8) | Jan 15, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b99e4815bc](https://linux-hardware.org/?probe=b99e4815bc) | Jan 10, 2023 |
| Dell          | Latitude 7420               | Notebook    | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | Notebook    | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| Supermicro    | X10SLL-F                    | Server      | [b721a47fa4](https://linux-hardware.org/?probe=b721a47fa4) | Jan 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d5df950832](https://linux-hardware.org/?probe=d5df950832) | Jan 03, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6a53c626dd](https://linux-hardware.org/?probe=6a53c626dd) | Jan 02, 2023 |
| Dell          | Precision M4800             | Notebook    | [505f1b47dc](https://linux-hardware.org/?probe=505f1b47dc) | Dec 30, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [4929f6a6c9](https://linux-hardware.org/?probe=4929f6a6c9) | Dec 28, 2022 |
| Dell          | Inspiron 7586               | Convertible | [d670af270f](https://linux-hardware.org/?probe=d670af270f) | Dec 28, 2022 |
| GPD           | WIN2                        | Notebook    | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| MSI           | Raider GE67HX 12UGS         | Notebook    | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf62b1c520](https://linux-hardware.org/?probe=cf62b1c520) | Dec 20, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [db7b91ac2f](https://linux-hardware.org/?probe=db7b91ac2f) | Dec 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | Notebook    | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ee5f96d645](https://linux-hardware.org/?probe=ee5f96d645) | Dec 09, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3c18fca709](https://linux-hardware.org/?probe=3c18fca709) | Dec 09, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [3dfa1ba4b1](https://linux-hardware.org/?probe=3dfa1ba4b1) | Dec 09, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [110e3eab7f](https://linux-hardware.org/?probe=110e3eab7f) | Dec 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [f698b715e4](https://linux-hardware.org/?probe=f698b715e4) | Nov 30, 2022 |
| Dell          | Inspiron 7586               | Convertible | [91dcb3265a](https://linux-hardware.org/?probe=91dcb3265a) | Nov 24, 2022 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [b79f103dd5](https://linux-hardware.org/?probe=b79f103dd5) | Nov 24, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [44a3785f1f](https://linux-hardware.org/?probe=44a3785f1f) | Nov 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | Notebook    | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | Notebook    | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [fce691523b](https://linux-hardware.org/?probe=fce691523b) | Oct 29, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | Notebook    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [6ffc032b64](https://linux-hardware.org/?probe=6ffc032b64) | Oct 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [d79322ca4a](https://linux-hardware.org/?probe=d79322ca4a) | Oct 19, 2022 |
| Dell          | Precision 5760              | Notebook    | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | Notebook    | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa5ea0c17c](https://linux-hardware.org/?probe=aa5ea0c17c) | Oct 14, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [ae775f1f89](https://linux-hardware.org/?probe=ae775f1f89) | Oct 13, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c203d7c388](https://linux-hardware.org/?probe=c203d7c388) | Oct 07, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3a409e83a0](https://linux-hardware.org/?probe=3a409e83a0) | Oct 07, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [5eb1758869](https://linux-hardware.org/?probe=5eb1758869) | Oct 07, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [8e301a5e4e](https://linux-hardware.org/?probe=8e301a5e4e) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [b21f5fee1a](https://linux-hardware.org/?probe=b21f5fee1a) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3f823868fd](https://linux-hardware.org/?probe=3f823868fd) | Sep 15, 2022 |
| Dell          | Precision M4800             | Notebook    | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [ad69daf392](https://linux-hardware.org/?probe=ad69daf392) | Sep 11, 2022 |
| Dell          | 0F0XJ6 A11                  | Server      | [a02c8258ba](https://linux-hardware.org/?probe=a02c8258ba) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7986ddc1d9](https://linux-hardware.org/?probe=7986ddc1d9) | Sep 11, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [98fd9b974e](https://linux-hardware.org/?probe=98fd9b974e) | Sep 09, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [ce872c873e](https://linux-hardware.org/?probe=ce872c873e) | Aug 24, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| ASUSTek       | H97I-PLUS                   | Desktop     | [982df0dba9](https://linux-hardware.org/?probe=982df0dba9) | Jun 22, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [6d5fdb800a](https://linux-hardware.org/?probe=6d5fdb800a) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [d26f08ea88](https://linux-hardware.org/?probe=d26f08ea88) | Jun 12, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0123caa2f3](https://linux-hardware.org/?probe=0123caa2f3) | Jun 11, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | Notebook    | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | Notebook    | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [ab13de0478](https://linux-hardware.org/?probe=ab13de0478) | May 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [96b24b0640](https://linux-hardware.org/?probe=96b24b0640) | May 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | Notebook    | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | Notebook    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [50d2e86de8](https://linux-hardware.org/?probe=50d2e86de8) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | Notebook    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [46b46c842f](https://linux-hardware.org/?probe=46b46c842f) | Apr 13, 2022 |
| Supermicro    | X8DT6                       | Server      | [0fd3b261c7](https://linux-hardware.org/?probe=0fd3b261c7) | Apr 03, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| ASUSTek       | P8Q77-M                     | Desktop     | [6cd75b6762](https://linux-hardware.org/?probe=6cd75b6762) | Mar 11, 2022 |
| GPD           | MicroPC                     | Notebook    | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [815cb9ab49](https://linux-hardware.org/?probe=815cb9ab49) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [1d6563ada3](https://linux-hardware.org/?probe=1d6563ada3) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | Notebook    | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | Notebook    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [5c984c6d9a](https://linux-hardware.org/?probe=5c984c6d9a) | Mar 09, 2022 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [40d2eced72](https://linux-hardware.org/?probe=40d2eced72) | Mar 09, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [6f9489b2e6](https://linux-hardware.org/?probe=6f9489b2e6) | Mar 09, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [524b675e7e](https://linux-hardware.org/?probe=524b675e7e) | Mar 09, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f38279e396](https://linux-hardware.org/?probe=f38279e396) | Mar 09, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | Notebook    | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| MSI           | X399 SLI PLUS               | Desktop     | [a1d172dbc0](https://linux-hardware.org/?probe=a1d172dbc0) | Feb 16, 2022 |
| Dell          | Latitude 7420               | Notebook    | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | Notebook    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [c84b603f92](https://linux-hardware.org/?probe=c84b603f92) | Jan 04, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | Notebook    | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | Z170-P                      | Desktop     | [d4bac456d1](https://linux-hardware.org/?probe=d4bac456d1) | Dec 16, 2021 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [e5dc04e6a5](https://linux-hardware.org/?probe=e5dc04e6a5) | Dec 16, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [eb5d5f4361](https://linux-hardware.org/?probe=eb5d5f4361) | Dec 12, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [af887c3f7b](https://linux-hardware.org/?probe=af887c3f7b) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Gigabyte      | H97M-D3H                    | Desktop     | [349fbeb586](https://linux-hardware.org/?probe=349fbeb586) | Oct 23, 2021 |
| Teclast       | F5                          | Convertible | [0854310843](https://linux-hardware.org/?probe=0854310843) | Oct 08, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | Notebook    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [66d71367c1](https://linux-hardware.org/?probe=66d71367c1) | Aug 24, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [bd919b4bd6](https://linux-hardware.org/?probe=bd919b4bd6) | Aug 22, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [128ae965a7](https://linux-hardware.org/?probe=128ae965a7) | Aug 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Inspiron 7391 2n1           | Convertible | [f632a64d73](https://linux-hardware.org/?probe=f632a64d73) | Jul 22, 2021 |
| Dell          | Latitude 7420               | Notebook    | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [d93a80d973](https://linux-hardware.org/?probe=d93a80d973) | Jul 14, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [59a699d357](https://linux-hardware.org/?probe=59a699d357) | Jul 14, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | Notebook    | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [60eed45305](https://linux-hardware.org/?probe=60eed45305) | Jun 18, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [0619809b36](https://linux-hardware.org/?probe=0619809b36) | Jun 01, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [6056eac50c](https://linux-hardware.org/?probe=6056eac50c) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [bd9fb4818b](https://linux-hardware.org/?probe=bd9fb4818b) | May 31, 2021 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [12fa3ffea5](https://linux-hardware.org/?probe=12fa3ffea5) | May 31, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | Notebook    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [f03b19461f](https://linux-hardware.org/?probe=f03b19461f) | May 16, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [529e915984](https://linux-hardware.org/?probe=529e915984) | May 16, 2021 |
| HP            | ZBook Studio G5             | Notebook    | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | Notebook    | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| ASUSTek       | Pro WS W480-ACE             | Desktop     | [3825190816](https://linux-hardware.org/?probe=3825190816) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d55d51a3e2](https://linux-hardware.org/?probe=d55d51a3e2) | Feb 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [188755ebc7](https://linux-hardware.org/?probe=188755ebc7) | Oct 25, 2020 |
| Hardkernel    | ODROID-H2                   | Desktop     | [a5d75a24e5](https://linux-hardware.org/?probe=a5d75a24e5) | Oct 13, 2020 |
| Lenovo        | ThinkPad T580 20L90024PB    | Notebook    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b85fb81c59](https://linux-hardware.org/?probe=b85fb81c59) | Sep 28, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | Notebook    | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [5f7f2db973](https://linux-hardware.org/?probe=5f7f2db973) | Aug 21, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [cc8de41afd](https://linux-hardware.org/?probe=cc8de41afd) | Aug 21, 2020 |
| HP            | 8055                        | Desktop     | [1165b457fa](https://linux-hardware.org/?probe=1165b457fa) | Jul 08, 2020 |
| HP            | 8055                        | Desktop     | [a5c65e8d4a](https://linux-hardware.org/?probe=a5c65e8d4a) | Jul 08, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | Notebook    | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| ASRock        | TRX40 Creator               | Desktop     | [2cefd65bfb](https://linux-hardware.org/?probe=2cefd65bfb) | Jun 29, 2020 |
| Acer          | Aspire E5-576G              | Notebook    | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | Notebook    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| NixOS 23.05                      | 104       | 33.44%  |
| NixOS 22.11                      | 54        | 17.36%  |
| NixOS 23.11                      | 53        | 17.04%  |
| NixOS 22.05                      | 37        | 11.9%   |
| NixOS 21.11                      | 18        | 5.79%   |
| NixOS 24.05                      | 10        | 3.22%   |
| NixOS                            | 5         | 1.61%   |
| NixOS 21.05pre-git               | 2         | 0.64%   |
| NixOS 20.09pre-git               | 2         | 0.64%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.32%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.32%   |
| NixOS 21.11.20210528.540dccb     | 1         | 0.32%   |
| NixOS 21.05.git.62d4591722f      | 1         | 0.32%   |
| NixOS 21.05.git.2e369bb2f4e      | 1         | 0.32%   |
| NixOS 21.05.993.93963c27b93      | 1         | 0.32%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.32%   |
| NixOS 21.05.3509.7daf35532d2     | 1         | 0.32%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.32%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.32%   |
| NixOS 21.05.2075.ff1ea3a36c1     | 1         | 0.32%   |
| NixOS 21.05.20210929.ee90403     | 1         | 0.32%   |
| NixOS 21.05.20210430.c8dff32     | 1         | 0.32%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.32%   |
| NixOS 21.05.20210224.f6b5bfd     | 1         | 0.32%   |
| NixOS 21.05.1471.a7512bb64b1     | 1         | 0.32%   |
| NixOS 21.03pre246062.420f89ceb26 | 1         | 0.32%   |
| NixOS 21.03.git.b4349c13a6d      | 1         | 0.32%   |
| NixOS 21.03.20201007.420f89c     | 1         | 0.32%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.32%   |
| NixOS 20.09pre231796.22a81aa5fc1 | 1         | 0.32%   |
| NixOS 20.09.git.4a361b06a93      | 1         | 0.32%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.32%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.32%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.32%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.32%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| NixOS | 280       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version        | Computers | Percent |
|----------------|-----------|---------|
| 6.1.55         | 11        | 3.28%   |
| 6.6.0          | 6         | 1.79%   |
| 6.1.61         | 6         | 1.79%   |
| 6.1.60         | 5         | 1.49%   |
| 6.1.51         | 5         | 1.49%   |
| 6.1.31         | 5         | 1.49%   |
| 5.15.74        | 5         | 1.49%   |
| 6.5.5          | 4         | 1.19%   |
| 6.4.0          | 4         | 1.19%   |
| 6.3.8          | 4         | 1.19%   |
| 6.3.3          | 4         | 1.19%   |
| 6.1.53         | 4         | 1.19%   |
| 6.1.38         | 4         | 1.19%   |
| 5.15.86        | 4         | 1.19%   |
| 5.15.43        | 4         | 1.19%   |
| 6.6.3          | 3         | 0.9%    |
| 6.5.7          | 3         | 0.9%    |
| 6.5.2          | 3         | 0.9%    |
| 6.3.1          | 3         | 0.9%    |
| 6.2.0-rc6      | 3         | 0.9%    |
| 6.1.67         | 3         | 0.9%    |
| 6.1.64         | 3         | 0.9%    |
| 6.1.63         | 3         | 0.9%    |
| 6.1.47         | 3         | 0.9%    |
| 6.1.42         | 3         | 0.9%    |
| 6.1.37         | 3         | 0.9%    |
| 6.1.35         | 3         | 0.9%    |
| 6.1.0          | 3         | 0.9%    |
| 6.0.11         | 3         | 0.9%    |
| 6.0.10         | 3         | 0.9%    |
| 5.15.82        | 3         | 0.9%    |
| 5.15.72        | 3         | 0.9%    |
| 5.15.68        | 3         | 0.9%    |
| 5.15.47        | 3         | 0.9%    |
| 5.15.26        | 3         | 0.9%    |
| 6.6.6          | 2         | 0.6%    |
| 6.6.1          | 2         | 0.6%    |
| 6.5.7-xanmod1  | 2         | 0.6%    |
| 6.5.6          | 2         | 0.6%    |
| 6.5.11-xanmod1 | 2         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.55  | 12        | 3.58%   |
| 6.6.0   | 6         | 1.79%   |
| 6.4.0   | 6         | 1.79%   |
| 6.1.61  | 6         | 1.79%   |
| 6.1.31  | 6         | 1.79%   |
| 6.5.7   | 5         | 1.49%   |
| 6.1.60  | 5         | 1.49%   |
| 6.1.51  | 5         | 1.49%   |
| 5.15.74 | 5         | 1.49%   |
| 6.5.5   | 4         | 1.19%   |
| 6.3.8   | 4         | 1.19%   |
| 6.3.3   | 4         | 1.19%   |
| 6.2.0   | 4         | 1.19%   |
| 6.1.53  | 4         | 1.19%   |
| 6.1.38  | 4         | 1.19%   |
| 6.1.0   | 4         | 1.19%   |
| 6.0.10  | 4         | 1.19%   |
| 5.15.86 | 4         | 1.19%   |
| 5.15.43 | 4         | 1.19%   |
| 6.6.3   | 3         | 0.9%    |
| 6.5.2   | 3         | 0.9%    |
| 6.3.1   | 3         | 0.9%    |
| 6.1.67  | 3         | 0.9%    |
| 6.1.64  | 3         | 0.9%    |
| 6.1.63  | 3         | 0.9%    |
| 6.1.47  | 3         | 0.9%    |
| 6.1.42  | 3         | 0.9%    |
| 6.1.37  | 3         | 0.9%    |
| 6.1.35  | 3         | 0.9%    |
| 6.0.11  | 3         | 0.9%    |
| 5.15.82 | 3         | 0.9%    |
| 5.15.72 | 3         | 0.9%    |
| 5.15.68 | 3         | 0.9%    |
| 5.15.47 | 3         | 0.9%    |
| 5.15.26 | 3         | 0.9%    |
| 6.6.6   | 2         | 0.6%    |
| 6.6.4   | 2         | 0.6%    |
| 6.6.2   | 2         | 0.6%    |
| 6.6.1   | 2         | 0.6%    |
| 6.5.9   | 2         | 0.6%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 92        | 29.3%   |
| 5.15    | 62        | 19.75%  |
| 6.5     | 19        | 6.05%   |
| 6.6     | 18        | 5.73%   |
| 6.4     | 17        | 5.41%   |
| 5.10    | 14        | 4.46%   |
| 6.3     | 13        | 4.14%   |
| 6.2     | 13        | 4.14%   |
| 6.0     | 13        | 4.14%   |
| 5.16    | 8         | 2.55%   |
| 5.4     | 7         | 2.23%   |
| 5.19    | 7         | 2.23%   |
| 5.8     | 6         | 1.91%   |
| 5.18    | 5         | 1.59%   |
| 5.13    | 4         | 1.27%   |
| 5.7     | 3         | 0.96%   |
| 5.17    | 3         | 0.96%   |
| 5.12    | 3         | 0.96%   |
| 5.14    | 2         | 0.64%   |
| 5.11    | 2         | 0.64%   |
| 4.19    | 2         | 0.64%   |
| Unknown | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 272       | 97.14%  |
| aarch64 | 7         | 2.5%    |
| i686    | 1         | 0.36%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Unknown       | 108       | 36.99%  |
| GNOME         | 48        | 16.44%  |
| KDE5          | 39        | 13.36%  |
| sway          | 28        | 9.59%   |
| Hyprland      | 21        | 7.19%   |
| XFCE          | 9         | 3.08%   |
| none+i3       | 9         | 3.08%   |
| KDE           | 9         | 3.08%   |
| none+awesome  | 4         | 1.37%   |
| X-Generic     | 3         | 1.03%   |
| xsession      | 2         | 0.68%   |
| Pantheon      | 2         | 0.68%   |
| none+xmonad   | 2         | 0.68%   |
| MATE          | 2         | 0.68%   |
| Budgie        | 2         | 0.68%   |
| X-Cinnamon    | 1         | 0.34%   |
| plasmawayland | 1         | 0.34%   |
| none+bspwm    | 1         | 0.34%   |
| LXQt          | 1         | 0.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 106       | 36.05%  |
| Wayland | 97        | 32.99%  |
| X11     | 65        | 22.11%  |
| Tty     | 26        | 8.84%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 136       | 47.89%  |
| SDDM    | 55        | 19.37%  |
| GDM     | 55        | 19.37%  |
| LightDM | 38        | 13.38%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 164       | 57.95%  |
| Unknown    | 60        | 21.2%   |
| en_GB      | 16        | 5.65%   |
| en_AU      | 7         | 2.47%   |
| ru_RU      | 5         | 1.77%   |
| de_DE      | 5         | 1.77%   |
| en_DK      | 4         | 1.41%   |
| fr_FR      | 3         | 1.06%   |
| pt_BR      | 2         | 0.71%   |
| it_IT      | 2         | 0.71%   |
| en_CA      | 2         | 0.71%   |
| de_CH      | 2         | 0.71%   |
| C          | 2         | 0.71%   |
| ro_RO      | 1         | 0.35%   |
| pt_PT      | 1         | 0.35%   |
| pl_PL      | 1         | 0.35%   |
| lv_LV      | 1         | 0.35%   |
| lt_LT      | 1         | 0.35%   |
| es_MX      | 1         | 0.35%   |
| en_NZ      | 1         | 0.35%   |
| en_IN      | 1         | 0.35%   |
| en_IE.UTF8 | 1         | 0.35%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 247       | 87.59%  |
| BIOS | 35        | 12.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 153       | 53.68%  |
| Btrfs   | 51        | 17.89%  |
| Zfs     | 27        | 9.47%   |
| Tmpfs   | 27        | 9.47%   |
| Xfs     | 18        | 6.32%   |
| Unknown | 6         | 2.11%   |
| F2fs    | 2         | 0.7%    |
| Ext2    | 1         | 0.35%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 262       | 92.58%  |
| MBR     | 13        | 4.59%   |
| Unknown | 8         | 2.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 225       | 78.67%  |
| Yes       | 61        | 21.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 203       | 71.99%  |
| Yes       | 79        | 28.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 61        | 21.79%  |
| ASUSTek Computer                     | 57        | 20.36%  |
| Dell                                 | 33        | 11.79%  |
| Hewlett-Packard                      | 22        | 7.86%   |
| MSI                                  | 19        | 6.79%   |
| Gigabyte Technology                  | 16        | 5.71%   |
| ASRock                               | 11        | 3.93%   |
| Apple                                | 9         | 3.21%   |
| Acer                                 | 8         | 2.86%   |
| Framework                            | 4         | 1.43%   |
| Pine Microsystems                    | 3         | 1.07%   |
| Intel                                | 3         | 1.07%   |
| GPD                                  | 3         | 1.07%   |
| Unknown                              | 3         | 1.07%   |
| Supermicro                           | 2         | 0.71%   |
| Raspberry Pi Foundation              | 2         | 0.71%   |
| MECHREVO                             | 2         | 0.71%   |
| Toshiba                              | 1         | 0.36%   |
| Timi                                 | 1         | 0.36%   |
| Teclast                              | 1         | 0.36%   |
| System76                             | 1         | 0.36%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.36%   |
| Samsung Electronics                  | 1         | 0.36%   |
| retsamarret                          | 1         | 0.36%   |
| OBSIDIAN-PC                          | 1         | 0.36%   |
| Nvidia                               | 1         | 0.36%   |
| Microtech                            | 1         | 0.36%   |
| Microsoft                            | 1         | 0.36%   |
| Medion                               | 1         | 0.36%   |
| MACHENIKE                            | 1         | 0.36%   |
| LattePanda                           | 1         | 0.36%   |
| HUAWEI                               | 1         | 0.36%   |
| Hardkernel                           | 1         | 0.36%   |
| EVGA                                 | 1         | 0.36%   |
| ECS                                  | 1         | 0.36%   |
| Blackview                            | 1         | 0.36%   |
| AZW                                  | 1         | 0.36%   |
| Avell High Performance               | 1         | 0.36%   |
| Alienware                            | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Pine Microsystems Pine64 PinePhone (1.2)   | 3         | 1.07%   |
| MSI MS-7C37                                | 3         | 1.07%   |
| Lenovo 13w Yoga 82S1                       | 3         | 1.07%   |
| ASUS All Series                            | 3         | 1.07%   |
| Apple iMac17,1                             | 3         | 1.07%   |
| Unknown                                    | 3         | 1.07%   |
| MSI MS-7C56                                | 2         | 0.71%   |
| HP EliteBook 8470p                         | 2         | 0.71%   |
| Gigabyte B550I AORUS PRO AX                | 2         | 0.71%   |
| Gigabyte B450M DS3H                        | 2         | 0.71%   |
| Framework Laptop (12th Gen Intel Core)     | 2         | 0.71%   |
| Framework Laptop                           | 2         | 0.71%   |
| Dell Latitude 7420                         | 2         | 0.71%   |
| Dell Inspiron 7506 2n1                     | 2         | 0.71%   |
| ASUS Zenbook UX3402ZA_UX3402ZA             | 2         | 0.71%   |
| ASUS Zenbook UN5401RA UN5401RA_UN5401RA    | 2         | 0.71%   |
| ASUS Vivobook Go E1404FA_E1404FA           | 2         | 0.71%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.71%   |
| ASRock Z87 Extreme4                        | 2         | 0.71%   |
| Apple MacBookPro11,5                       | 2         | 0.71%   |
| Apple MacBookPro11,3                       | 2         | 0.71%   |
| Toshiba Satellite L50-B                    | 1         | 0.36%   |
| Timi Redmi Book Pro 15 2022                | 1         | 0.36%   |
| Teclast F5                                 | 1         | 0.36%   |
| System76 Pangolin                          | 1         | 0.36%   |
| Supermicro X8DT6                           | 1         | 0.36%   |
| Supermicro X10SLL-F                        | 1         | 0.36%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.36%   |
| Samsung 530U3BI/530U4BI/530U4BH            | 1         | 0.36%   |
| retsamarret 000-F4423-FBA004-2000-N        | 1         | 0.36%   |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 1         | 0.36%   |
| RPi Raspberry Pi 3 Model B+                | 1         | 0.36%   |
| OBSIDIAN-PC N13_N140ZU                     | 1         | 0.36%   |
| Nvidia 680iLT                              | 1         | 0.36%   |
| MSI Prestige 16Studio A13VE                | 1         | 0.36%   |
| MSI Prestige 14 A10SC                      | 1         | 0.36%   |
| MSI MS-7E12                                | 1         | 0.36%   |
| MSI MS-7C95                                | 1         | 0.36%   |
| MSI MS-7C91                                | 1         | 0.36%   |
| MSI MS-7C84                                | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 35        | 12.5%   |
| ASUS ROG                 | 17        | 6.07%   |
| ASUS PRIME               | 10        | 3.57%   |
| Dell XPS                 | 9         | 3.21%   |
| ASUS Zenbook             | 9         | 3.21%   |
| HP EliteBook             | 8         | 2.86%   |
| Dell Inspiron            | 8         | 2.86%   |
| Lenovo Legion            | 7         | 2.5%    |
| Dell Latitude            | 7         | 2.5%    |
| Lenovo IdeaPad           | 5         | 1.79%   |
| Apple MacBookPro11       | 5         | 1.79%   |
| Acer Aspire              | 5         | 1.79%   |
| Lenovo Yoga              | 4         | 1.43%   |
| Gigabyte X570            | 4         | 1.43%   |
| Framework Laptop         | 4         | 1.43%   |
| Dell Precision           | 4         | 1.43%   |
| ASUS Vivobook            | 4         | 1.43%   |
| Pine Microsystems Pine64 | 3         | 1.07%   |
| MSI MS-7C37              | 3         | 1.07%   |
| Lenovo ThinkBook         | 3         | 1.07%   |
| Lenovo 13w               | 3         | 1.07%   |
| HP ZBook                 | 3         | 1.07%   |
| HP EliteDesk             | 3         | 1.07%   |
| Gigabyte B450M           | 3         | 1.07%   |
| Dell PowerEdge           | 3         | 1.07%   |
| ASUS TUF                 | 3         | 1.07%   |
| ASUS All                 | 3         | 1.07%   |
| Apple iMac17             | 3         | 1.07%   |
| Unknown                  | 3         | 1.07%   |
| RPi Raspberry            | 2         | 0.71%   |
| MSI Prestige             | 2         | 0.71%   |
| MSI MS-7C56              | 2         | 0.71%   |
| Lenovo IdeaPadFlex       | 2         | 0.71%   |
| HP Spectre               | 2         | 0.71%   |
| HP ProBook               | 2         | 0.71%   |
| HP ENVY                  | 2         | 0.71%   |
| Gigabyte B550I           | 2         | 0.71%   |
| ASRock Z87               | 2         | 0.71%   |
| Toshiba Satellite        | 1         | 0.36%   |
| Timi Redmi               | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 40        | 14.29%  |
| 2019    | 35        | 12.5%   |
| 2022    | 34        | 12.14%  |
| 2021    | 31        | 11.07%  |
| 2018    | 25        | 8.93%   |
| 2023    | 22        | 7.86%   |
| 2017    | 15        | 5.36%   |
| 2016    | 14        | 5%      |
| 2014    | 13        | 4.64%   |
| 2012    | 12        | 4.29%   |
| 2013    | 11        | 3.93%   |
| 2015    | 10        | 3.57%   |
| Unknown | 7         | 2.5%    |
| 2011    | 6         | 2.14%   |
| 2010    | 2         | 0.71%   |
| 2008    | 2         | 0.71%   |
| 2009    | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 146       | 52.14%  |
| Desktop        | 90        | 32.14%  |
| Convertible    | 23        | 8.21%   |
| Server         | 5         | 1.79%   |
| All in one     | 4         | 1.43%   |
| Phone          | 3         | 1.07%   |
| System on chip | 3         | 1.07%   |
| Tablet         | 3         | 1.07%   |
| Mini pc        | 3         | 1.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 274       | 97.16%  |
| Enabled  | 8         | 2.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 279       | 99.64%  |
| Yes  | 1         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 32.01-64.0      | 66        | 23.32%  |
| 16.01-24.0      | 64        | 22.61%  |
| 8.01-16.0       | 51        | 18.02%  |
| 64.01-256.0     | 36        | 12.72%  |
| 4.01-8.0        | 35        | 12.37%  |
| 24.01-32.0      | 15        | 5.3%    |
| 3.01-4.0        | 12        | 4.24%   |
| 0.51-1.0        | 2         | 0.71%   |
| More than 256.0 | 1         | 0.35%   |
| 1.01-2.0        | 1         | 0.35%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 79        | 25.82%  |
| 2.01-3.0    | 51        | 16.67%  |
| 8.01-16.0   | 47        | 15.36%  |
| 3.01-4.0    | 45        | 14.71%  |
| 1.01-2.0    | 36        | 11.76%  |
| 16.01-24.0  | 15        | 4.9%    |
| 0.51-1.0    | 11        | 3.59%   |
| 32.01-64.0  | 9         | 2.94%   |
| 24.01-32.0  | 7         | 2.29%   |
| 0.01-0.5    | 4         | 1.31%   |
| 64.01-256.0 | 2         | 0.65%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 170       | 58.62%  |
| 2      | 68        | 23.45%  |
| 3      | 26        | 8.97%   |
| 5      | 7         | 2.41%   |
| 4      | 6         | 2.07%   |
| 6      | 4         | 1.38%   |
| 8      | 2         | 0.69%   |
| 7      | 2         | 0.69%   |
| 23     | 1         | 0.34%   |
| 17     | 1         | 0.34%   |
| 11     | 1         | 0.34%   |
| 9      | 1         | 0.34%   |
| 0      | 1         | 0.34%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 248       | 87.94%  |
| Yes       | 34        | 12.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 208       | 73.5%   |
| No        | 75        | 26.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 222       | 78.72%  |
| No        | 60        | 21.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 215       | 75.97%  |
| No        | 68        | 24.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country         | Computers | Percent |
|-----------------|-----------|---------|
| USA             | 66        | 23.57%  |
| Germany         | 27        | 9.64%   |
| UK              | 17        | 6.07%   |
| Russia          | 16        | 5.71%   |
| Italy           | 15        | 5.36%   |
| France          | 13        | 4.64%   |
| Poland          | 9         | 3.21%   |
| Canada          | 9         | 3.21%   |
| Ukraine         | 7         | 2.5%    |
| Austria         | 7         | 2.5%    |
| Australia       | 7         | 2.5%    |
| Netherlands     | 6         | 2.14%   |
| Czechia         | 6         | 2.14%   |
| Switzerland     | 5         | 1.79%   |
| Sweden          | 4         | 1.43%   |
| Portugal        | 4         | 1.43%   |
| Norway          | 4         | 1.43%   |
| Brazil          | 4         | 1.43%   |
| Japan           | 3         | 1.07%   |
| India           | 3         | 1.07%   |
| Denmark         | 3         | 1.07%   |
| Belgium         | 3         | 1.07%   |
| Spain           | 2         | 0.71%   |
| South Africa    | 2         | 0.71%   |
| Slovenia        | 2         | 0.71%   |
| Serbia          | 2         | 0.71%   |
| Qatar           | 2         | 0.71%   |
| New Zealand     | 2         | 0.71%   |
| Mexico          | 2         | 0.71%   |
| Iraq            | 2         | 0.71%   |
| Hungary         | 2         | 0.71%   |
| Finland         | 2         | 0.71%   |
| China           | 2         | 0.71%   |
| Vietnam         | 1         | 0.36%   |
| Uzbekistan      | 1         | 0.36%   |
| Uruguay         | 1         | 0.36%   |
| The Netherlands | 1         | 0.36%   |
| Taiwan          | 1         | 0.36%   |
| Singapore       | 1         | 0.36%   |
| Romania         | 1         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Vienna            | 6         | 2.03%   |
| Perth             | 5         | 1.69%   |
| Milwaukee         | 5         | 1.69%   |
| Kharkiv           | 5         | 1.69%   |
| Marki             | 4         | 1.35%   |
| Frankfurt am Main | 4         | 1.35%   |
| Craigsville       | 4         | 1.35%   |
| Chelyabinsk       | 4         | 1.35%   |
| Amsterdam         | 4         | 1.35%   |
| Prague            | 3         | 1.01%   |
| Plymouth          | 3         | 1.01%   |
| Oslo              | 3         | 1.01%   |
| Lyon              | 3         | 1.01%   |
| Los Angeles       | 3         | 1.01%   |
| London            | 3         | 1.01%   |
| Cerami            | 3         | 1.01%   |
| Southampton       | 2         | 0.68%   |
| South Deerfield   | 2         | 0.68%   |
| Schaafheim        | 2         | 0.68%   |
| Saratov           | 2         | 0.68%   |
| Rochester         | 2         | 0.68%   |
| Richmond          | 2         | 0.68%   |
| Richardson        | 2         | 0.68%   |
| Reno              | 2         | 0.68%   |
| Ramenskoye        | 2         | 0.68%   |
| Pradamano         | 2         | 0.68%   |
| Phoenix           | 2         | 0.68%   |
| Paris             | 2         | 0.68%   |
| Ottawa            | 2         | 0.68%   |
| Moscow            | 2         | 0.68%   |
| Melbourne         | 2         | 0.68%   |
| Las Vegas         | 2         | 0.68%   |
| Krasnodar         | 2         | 0.68%   |
| Hamburg           | 2         | 0.68%   |
| Halifax           | 2         | 0.68%   |
| Gdansk            | 2         | 0.68%   |
| Doha              | 2         | 0.68%   |
| Darmstadt         | 2         | 0.68%   |
| Catania           | 2         | 0.68%   |
| Cape Town         | 2         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 105       | 182    | 25.18%  |
| Sandisk                        | 37        | 46     | 8.87%   |
| Seagate                        | 34        | 81     | 8.15%   |
| WDC                            | 32        | 56     | 7.67%   |
| Toshiba                        | 21        | 37     | 5.04%   |
| SK hynix                       | 17        | 20     | 4.08%   |
| Micron Technology              | 17        | 18     | 4.08%   |
| Intel                          | 16        | 23     | 3.84%   |
| Crucial                        | 16        | 23     | 3.84%   |
| Unknown                        | 14        | 18     | 3.36%   |
| Kingston                       | 14        | 18     | 3.36%   |
| Phison Electronics             | 9         | 12     | 2.16%   |
| Apple                          | 8         | 14     | 1.92%   |
| HGST                           | 7         | 18     | 1.68%   |
| KIOXIA                         | 6         | 8      | 1.44%   |
| Kingston Technology Company    | 5         | 5      | 1.2%    |
| MAXIO Technology (Hangzhou)    | 4         | 6      | 0.96%   |
| A-DATA Technology              | 4         | 4      | 0.96%   |
| Yangtze Memory Technologies    | 3         | 4      | 0.72%   |
| Micron/Crucial Technology      | 3         | 3      | 0.72%   |
| Hitachi                        | 3         | 6      | 0.72%   |
| Corsair                        | 3         | 3      | 0.72%   |
| Transcend                      | 2         | 2      | 0.48%   |
| SPCC                           | 2         | 2      | 0.48%   |
| Realtek Semiconductor          | 2         | 7      | 0.48%   |
| PNY                            | 2         | 3      | 0.48%   |
| Plextor                        | 2         | 2      | 0.48%   |
| OCZ                            | 2         | 2      | 0.48%   |
| Lite-On Technology             | 2         | 2      | 0.48%   |
| China                          | 2         | 2      | 0.48%   |
| ADATA Technology               | 2         | 4      | 0.48%   |
| Unknown                        | 2         | 2      | 0.48%   |
| ZHITAI                         | 1         | 1      | 0.24%   |
| Teclast                        | 1         | 3      | 0.24%   |
| Team                           | 1         | 1      | 0.24%   |
| Solid State Storage Technology | 1         | 1      | 0.24%   |
| Silicon Motion                 | 1         | 1      | 0.24%   |
| S3+                            | 1         | 1      | 0.24%   |
| Realtek                        | 1         | 1      | 0.24%   |
| Phison                         | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 18        | 3.75%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 13        | 2.71%   |
| Samsung SSD 860 EVO 1TB                             | 8         | 1.67%   |
| Unknown MMC Card  32GB                              | 6         | 1.25%   |
| Samsung SSD 860 EVO 500GB                           | 6         | 1.25%   |
| SanDisk SSD PLUS 240GB                              | 4         | 0.83%   |
| Samsung SSD 860 QVO 1TB                             | 4         | 0.83%   |
| Intel SSDPEKNU512GZ 512GB                           | 4         | 0.83%   |
| Unknown MMC Card  128GB                             | 3         | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB                      | 3         | 0.63%   |
| Seagate ST3000DM001-1ER166 3TB                      | 3         | 0.63%   |
| Seagate ST3000DM001-1CH166 3TB                      | 3         | 0.63%   |
| Sandisk WD_BLACK SN770 1TB                          | 3         | 0.63%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 3         | 0.63%   |
| Samsung SSD 980 1TB                                 | 3         | 0.63%   |
| Samsung SSD 970 EVO Plus 2TB                        | 3         | 0.63%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.63%   |
| Samsung SSD 970 EVO 500GB                           | 3         | 0.63%   |
| Samsung SSD 870 EVO 500GB                           | 3         | 0.63%   |
| Samsung SSD 860 EVO 250GB                           | 3         | 0.63%   |
| Samsung SSD 850 EVO 500GB                           | 3         | 0.63%   |
| Phison E16 PCIe4 NVMe Controller 500GB              | 3         | 0.63%   |
| Micron MTFDKCD512TFK 512GB                          | 3         | 0.63%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 1024GB | 3         | 0.63%   |
| Intel SSDPEKNU010TZ 1024GB                          | 3         | 0.63%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 0.63%   |
| WDC WD80EMAZ-00WJTA0 8TB                            | 2         | 0.42%   |
| Unknown MMC Card  16GB                              | 2         | 0.42%   |
| Toshiba BG3 NVMe SSD Controller 128GB               | 2         | 0.42%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                | 2         | 0.42%   |
| SK hynix PC801 NVMe 512GB                           | 2         | 0.42%   |
| SK hynix HFM001TD3JX013N 1TB                        | 2         | 0.42%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 2         | 0.42%   |
| Seagate ST8000VN004-3CP101 8TB                      | 2         | 0.42%   |
| Seagate ST4000VN008-2DR166 4TB                      | 2         | 0.42%   |
| Seagate ST14000NM0018-2H4101 14TB                   | 2         | 0.42%   |
| Seagate ST12000VN0008-2JH101 12TB                   | 2         | 0.42%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2         | 0.42%   |
| Sandisk WD_BLACK SN850X 2000GB                      | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 81     | 39.08%  |
| WDC                 | 25        | 46     | 28.74%  |
| Toshiba             | 13        | 26     | 14.94%  |
| HGST                | 7         | 18     | 8.05%   |
| Hitachi             | 3         | 6      | 3.45%   |
| Apple               | 3         | 3      | 3.45%   |
| Samsung Electronics | 2         | 2      | 2.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 86     | 33.83%  |
| Crucial             | 15        | 22     | 11.28%  |
| SanDisk             | 13        | 18     | 9.77%   |
| Kingston            | 10        | 13     | 7.52%   |
| Apple               | 6         | 8      | 4.51%   |
| Intel               | 5         | 7      | 3.76%   |
| WDC                 | 4         | 5      | 3.01%   |
| Micron Technology   | 3         | 3      | 2.26%   |
| Corsair             | 3         | 3      | 2.26%   |
| Transcend           | 2         | 2      | 1.5%    |
| Toshiba             | 2         | 2      | 1.5%    |
| SPCC                | 2         | 2      | 1.5%    |
| SK hynix            | 2         | 2      | 1.5%    |
| PNY                 | 2         | 3      | 1.5%    |
| OCZ                 | 2         | 2      | 1.5%    |
| China               | 2         | 2      | 1.5%    |
| ZHITAI              | 1         | 1      | 0.75%   |
| Teclast             | 1         | 3      | 0.75%   |
| Team                | 1         | 1      | 0.75%   |
| S3+                 | 1         | 1      | 0.75%   |
| Plextor             | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| LITEON              | 1         | 1      | 0.75%   |
| Intenso             | 1         | 1      | 0.75%   |
| INNOVATION IT       | 1         | 1      | 0.75%   |
| Dogfish             | 1         | 1      | 0.75%   |
| BIWIN               | 1         | 1      | 0.75%   |
| ASMT                | 1         | 1      | 0.75%   |
| ASMedia             | 1         | 1      | 0.75%   |
| A-DATA Technology   | 1         | 1      | 0.75%   |
| Unknown             | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 183       | 255    | 48.67%  |
| SSD     | 116       | 197    | 30.85%  |
| HDD     | 62        | 182    | 16.49%  |
| MMC     | 14        | 19     | 3.72%   |
| Unknown | 1         | 1      | 0.27%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 183       | 254    | 53.82%  |
| SATA | 134       | 369    | 39.41%  |
| MMC  | 14        | 19     | 4.12%   |
| SAS  | 9         | 12     | 2.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 89        | 150    | 44.72%  |
| 0.51-1.0   | 58        | 89     | 29.15%  |
| 1.01-2.0   | 19        | 25     | 9.55%   |
| 4.01-10.0  | 16        | 61     | 8.04%   |
| 2.01-3.0   | 8         | 14     | 4.02%   |
| 3.01-4.0   | 6         | 22     | 3.02%   |
| 10.01-20.0 | 3         | 18     | 1.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 69        | 23.79%  |
| 1-20           | 64        | 22.07%  |
| 251-500        | 39        | 13.45%  |
| 501-1000       | 33        | 11.38%  |
| 101-250        | 29        | 10%     |
| 1001-2000      | 22        | 7.59%   |
| More than 3000 | 21        | 7.24%   |
| 2001-3000      | 10        | 3.45%   |
| 21-50          | 2         | 0.69%   |
| 51-100         | 1         | 0.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 86        | 29.15%  |
| Unknown        | 69        | 23.39%  |
| 101-250        | 37        | 12.54%  |
| 21-50          | 26        | 8.81%   |
| 51-100         | 21        | 7.12%   |
| 501-1000       | 18        | 6.1%    |
| 251-500        | 15        | 5.08%   |
| More than 3000 | 9         | 3.05%   |
| 1001-2000      | 8         | 2.71%   |
| 2001-3000      | 6         | 2.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| SanDisk SSD PLUS 240GB                                          | 2         | 4      | 6.67%   |
| WDC WD30EZRX-00SPEB0 3TB                                        | 1         | 1      | 3.33%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 1         | 1      | 3.33%   |
| WDC WD20EARX-008FB0 2TB                                         | 1         | 1      | 3.33%   |
| WDC WD1600JS-00NCB1 160GB                                       | 1         | 1      | 3.33%   |
| WDC WD10EZEX-60ZF5A0 1TB                                        | 1         | 1      | 3.33%   |
| WDC WD10 JPLX-00MBPT0 1TB                                       | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD100 1TB                                          | 1         | 1      | 3.33%   |
| Toshiba MK2565GSXV 250GB                                        | 1         | 1      | 3.33%   |
| Toshiba HDWQ140 4TB                                             | 1         | 1      | 3.33%   |
| SK hynix PC711 HFS512GDE9X073N 512GB                            | 1         | 1      | 3.33%   |
| Seagate ST8000VN004-2M2101 8TB                                  | 1         | 3      | 3.33%   |
| Seagate ST8000VN0022-2EL112 8TB                                 | 1         | 1      | 3.33%   |
| Seagate ST3500418AS 500GB                                       | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 970 EVO 1TB                             | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 2TB                             | 1         | 1      | 3.33%   |
| Samsung Electronics SSD 870 EVO 1TB                             | 1         | 1      | 3.33%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 250GB | 1         | 1      | 3.33%   |
| Samsung Electronics NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 1         | 1      | 3.33%   |
| Micron Technology C400 RealSSD 2.5 7mm 512GB                    | 1         | 1      | 3.33%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD                  | 1         | 1      | 3.33%   |
| Intel SSDSC2BW240A4 240GB                                       | 1         | 1      | 3.33%   |
| Hitachi HDS722020ALA330 2TB                                     | 1         | 1      | 3.33%   |
| HGST HTS545050A7E680 500GB                                      | 1         | 1      | 3.33%   |
| Crucial CT240M500SSD1 240GB                                     | 1         | 1      | 3.33%   |
| Corsair Neutron XT SSD 240GB                                    | 1         | 1      | 3.33%   |
| Corsair Force GS 240GB SSD                                      | 1         | 1      | 3.33%   |
| ASMT 2115 1TB                                                   | 1         | 1      | 3.33%   |
| A-DATA Technology IM2P33F3A NVMe 256GB                          | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 6      | 20%     |
| Samsung Electronics | 5         | 5      | 16.67%  |
| Toshiba             | 3         | 3      | 10%     |
| Seagate             | 3         | 5      | 10%     |
| SanDisk             | 2         | 4      | 6.67%   |
| Micron Technology   | 2         | 2      | 6.67%   |
| Corsair             | 2         | 2      | 6.67%   |
| SK hynix            | 1         | 1      | 3.33%   |
| Intel               | 1         | 1      | 3.33%   |
| Hitachi             | 1         | 1      | 3.33%   |
| HGST                | 1         | 1      | 3.33%   |
| Crucial             | 1         | 1      | 3.33%   |
| ASMT                | 1         | 1      | 3.33%   |
| A-DATA Technology   | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 6      | 42.86%  |
| Toshiba | 3         | 3      | 21.43%  |
| Seagate | 3         | 5      | 21.43%  |
| Hitachi | 1         | 1      | 7.14%   |
| HGST    | 1         | 1      | 7.14%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 16     | 44.83%  |
| SSD  | 11        | 13     | 37.93%  |
| NVMe | 5         | 5      | 17.24%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MG03ACA300 3TB                           | 1         | 1      | 25%     |
| Toshiba HDWG180 8TB                              | 1         | 4      | 25%     |
| SK hynix BC501 NVMe Solid State Drive 512GB      | 1         | 1      | 25%     |
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 5      | 50%     |
| SK hynix            | 1         | 1      | 25%     |
| Samsung Electronics | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 262       | 562    | 81.88%  |
| Detected | 30        | 51     | 9.38%   |
| Malfunc  | 24        | 34     | 7.5%    |
| Failed   | 4         | 7      | 1.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 134       | 33.17%  |
| Samsung Electronics            | 73        | 18.07%  |
| AMD                            | 60        | 14.85%  |
| SanDisk                        | 29        | 7.18%   |
| SK hynix                       | 15        | 3.71%   |
| Micron Technology              | 14        | 3.47%   |
| ASMedia Technology             | 11        | 2.72%   |
| Phison Electronics             | 10        | 2.48%   |
| Kingston Technology Company    | 9         | 2.23%   |
| Toshiba America Info Systems   | 7         | 1.73%   |
| KIOXIA                         | 6         | 1.49%   |
| ADATA Technology               | 5         | 1.24%   |
| Micron/Crucial Technology      | 4         | 0.99%   |
| MAXIO Technology (Hangzhou)    | 4         | 0.99%   |
| LSI Logic / Symbios Logic      | 4         | 0.99%   |
| Broadcom / LSI                 | 4         | 0.99%   |
| Yangtze Memory Technologies    | 3         | 0.74%   |
| Lite-On Technology             | 3         | 0.74%   |
| Realtek Semiconductor          | 2         | 0.5%    |
| Marvell Technology Group       | 2         | 0.5%    |
| Solid State Storage Technology | 1         | 0.25%   |
| Silicon Motion                 | 1         | 0.25%   |
| Shenzhen Longsys Electronics   | 1         | 0.25%   |
| Nvidia                         | 1         | 0.25%   |
| Biwin Storage Technology       | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 41        | 9.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 37        | 8.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 18        | 4.18%   |
| AMD 500 Series Chipset SATA Controller                                         | 13        | 3.02%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 2.78%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 2.78%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 10        | 2.32%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 2.09%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 1.86%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 8         | 1.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 8         | 1.86%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 7         | 1.62%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 7         | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 1.62%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 1.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 1.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 1.62%   |
| AMD 400 Series Chipset SATA Controller                                         | 7         | 1.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 1.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.16%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 5         | 1.16%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 4         | 0.93%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 0.93%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 4         | 0.93%   |
| Phison E12 NVMe Controller                                                     | 4         | 0.93%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 4         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 0.93%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.7%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3         | 0.7%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 0.7%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 3         | 0.7%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.7%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 3         | 0.7%    |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 0.7%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 3         | 0.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 0.7%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| NVMe | 182       | 47.03%  |
| SATA | 165       | 42.64%  |
| RAID | 25        | 6.46%   |
| IDE  | 8         | 2.07%   |
| SAS  | 7         | 1.81%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 172       | 61.43%  |
| AMD     | 101       | 36.07%  |
| ARM     | 6         | 2.14%   |
| Unknown | 1         | 0.36%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor          | 7         | 2.5%    |
| ARM Processor                              | 6         | 2.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 5         | 1.79%   |
| Intel 12th Gen Core i7-1260P               | 5         | 1.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 5         | 1.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz          | 4         | 1.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 4         | 1.43%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz    | 4         | 1.43%   |
| AMD Ryzen 9 5950X 16-Core Processor        | 4         | 1.43%   |
| AMD Ryzen 9 5900X 12-Core Processor        | 4         | 1.43%   |
| AMD Ryzen 9 5900HX with Radeon Graphics    | 4         | 1.43%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 4         | 1.43%   |
| AMD Ryzen 7 5800H with Radeon Graphics     | 4         | 1.43%   |
| AMD Ryzen 7 3800X 8-Core Processor         | 4         | 1.43%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 4         | 1.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 3         | 1.07%   |
| Intel Core i5-8350U CPU @ 1.70GHz          | 3         | 1.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz          | 3         | 1.07%   |
| Intel Celeron N4100 CPU @ 1.10GHz          | 3         | 1.07%   |
| Intel 12th Gen Core i5-1240P               | 3         | 1.07%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz    | 3         | 1.07%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 3         | 1.07%   |
| AMD Ryzen 7 6800H with Radeon Graphics     | 3         | 1.07%   |
| AMD Ryzen 5 5600G with Radeon Graphics     | 3         | 1.07%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 2         | 0.71%   |
| Intel Core i7-8700 CPU @ 3.20GHz           | 2         | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 2         | 0.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 0.71%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz         | 2         | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 2         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz          | 2         | 0.71%   |
| Intel Core i7-5600U CPU @ 2.60GHz          | 2         | 0.71%   |
| Intel Core i7-5500U CPU @ 2.40GHz          | 2         | 0.71%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz         | 2         | 0.71%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 2         | 0.71%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz         | 2         | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 2         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz         | 2         | 0.71%   |
| Intel Core i5-9300H CPU @ 2.40GHz          | 2         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 2         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Intel Core i7          | 61        | 21.79%  |
| Other                  | 50        | 17.86%  |
| Intel Core i5          | 40        | 14.29%  |
| AMD Ryzen 7            | 34        | 12.14%  |
| AMD Ryzen 5            | 28        | 10%     |
| AMD Ryzen 9            | 21        | 7.5%    |
| AMD Ryzen 7 PRO        | 10        | 3.57%   |
| Intel Xeon             | 8         | 2.86%   |
| Intel Celeron          | 8         | 2.86%   |
| Intel Core i3          | 6         | 2.14%   |
| AMD Ryzen Threadripper | 4         | 1.43%   |
| Intel Core i9          | 2         | 0.71%   |
| AMD FX                 | 2         | 0.71%   |
| Intel Pentium Gold     | 1         | 0.36%   |
| Intel Pentium D        | 1         | 0.36%   |
| Intel Core m3          | 1         | 0.36%   |
| Intel Atom             | 1         | 0.36%   |
| AMD EPYC               | 1         | 0.36%   |
| AMD Athlon II X4       | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 88        | 31.43%  |
| 8       | 59        | 21.07%  |
| 2       | 41        | 14.64%  |
| 6       | 40        | 14.29%  |
| 12      | 19        | 6.79%   |
| 16      | 10        | 3.57%   |
| 10      | 6         | 2.14%   |
| 24      | 5         | 1.79%   |
| 14      | 5         | 1.79%   |
| Unknown | 5         | 1.79%   |
| 32      | 1         | 0.36%   |
| 1       | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 272       | 97.14%  |
| Unknown | 5         | 1.79%   |
| 2       | 3         | 1.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 247       | 88.21%  |
| 1       | 28        | 10%     |
| Unknown | 5         | 1.79%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 278       | 98.93%  |
| 64-bit         | 1         | 0.36%   |
| 32-bit         | 1         | 0.36%   |
| Unknown        | 1         | 0.36%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 23.61%  |
| 0x0a50000c | 17        | 5.9%    |
| 0x306c3    | 13        | 4.51%   |
| 0x906ea    | 9         | 3.13%   |
| 0x806ea    | 9         | 3.13%   |
| 0x806c1    | 9         | 3.13%   |
| 0x306a9    | 9         | 3.13%   |
| 0x08701021 | 9         | 3.13%   |
| 0x0a50000d | 8         | 2.78%   |
| 0x0a404102 | 8         | 2.78%   |
| 0x506e3    | 7         | 2.43%   |
| 0x08600106 | 6         | 2.08%   |
| 0x0a601203 | 5         | 1.74%   |
| 0x08701013 | 5         | 1.74%   |
| 0x906a3    | 4         | 1.39%   |
| 0x806ec    | 4         | 1.39%   |
| 0x806eb    | 4         | 1.39%   |
| 0x806e9    | 4         | 1.39%   |
| 0x406e3    | 4         | 1.39%   |
| 0x40661    | 4         | 1.39%   |
| 0x40651    | 4         | 1.39%   |
| 0x306d4    | 4         | 1.39%   |
| 0x906e9    | 3         | 1.04%   |
| 0x906a4    | 3         | 1.04%   |
| 0x706a8    | 3         | 1.04%   |
| 0x706a1    | 3         | 1.04%   |
| 0x0a704103 | 3         | 1.04%   |
| 0xb0671    | 2         | 0.69%   |
| 0xa0653    | 2         | 0.69%   |
| 0x906ed    | 2         | 0.69%   |
| 0x706e5    | 2         | 0.69%   |
| 0x0a404101 | 2         | 0.69%   |
| 0x0a20120a | 2         | 0.69%   |
| 0x0a201204 | 2         | 0.69%   |
| 0x0a201025 | 2         | 0.69%   |
| 0x0a201016 | 2         | 0.69%   |
| 0x0a201009 | 2         | 0.69%   |
| 0x08a00008 | 2         | 0.69%   |
| 0x08600104 | 2         | 0.69%   |
| 0x08108109 | 2         | 0.69%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 45        | 16.07%  |
| Zen 3            | 38        | 13.57%  |
| Unknown          | 35        | 12.5%   |
| Zen 2            | 26        | 9.29%   |
| Haswell          | 23        | 8.21%   |
| Alderlake Hybrid | 23        | 8.21%   |
| Skylake          | 17        | 6.07%   |
| TigerLake        | 15        | 5.36%   |
| IvyBridge        | 13        | 4.64%   |
| Goldmont plus    | 7         | 2.5%    |
| Broadwell        | 6         | 2.14%   |
| Zen+             | 5         | 1.79%   |
| Zen              | 5         | 1.79%   |
| IceLake          | 5         | 1.79%   |
| CometLake        | 5         | 1.79%   |
| Westmere         | 2         | 0.71%   |
| SandyBridge      | 2         | 0.71%   |
| Piledriver       | 2         | 0.71%   |
| Tremont          | 1         | 0.36%   |
| NetBurst         | 1         | 0.36%   |
| Nehalem          | 1         | 0.36%   |
| K10 Llano        | 1         | 0.36%   |
| Gracemont        | 1         | 0.36%   |
| Bonnell          | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 138       | 41.07%  |
| AMD                        | 107       | 31.85%  |
| Nvidia                     | 86        | 25.6%   |
| Matrox Electronics Systems | 4         | 1.19%   |
| ASPEED Technology          | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 20        | 5.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 13        | 3.78%   |
| Intel UHD Graphics 620                                                                | 10        | 2.91%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 10        | 2.91%   |
| AMD Rembrandt [Radeon 680M]                                                           | 10        | 2.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 10        | 2.91%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 8         | 2.33%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 8         | 2.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 8         | 2.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 2.03%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 7         | 2.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 7         | 2.03%   |
| Intel HD Graphics 620                                                                 | 6         | 1.74%   |
| Intel HD Graphics 530                                                                 | 5         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 1.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 1.45%   |
| AMD Barcelo                                                                           | 5         | 1.45%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 4         | 1.16%   |
| Nvidia GP108M [GeForce MX150]                                                         | 4         | 1.16%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 4         | 1.16%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 1.16%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.16%   |
| Intel HD Graphics 5500                                                                | 4         | 1.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 1.16%   |
| AMD Raphael                                                                           | 4         | 1.16%   |
| AMD Phoenix1                                                                          | 4         | 1.16%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                            | 4         | 1.16%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                         | 4         | 1.16%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                        | 4         | 1.16%   |
| Nvidia TU106 [GeForce RTX 2070]                                                       | 3         | 0.87%   |
| Nvidia GK104 [GeForce GTX 760]                                                        | 3         | 0.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 0.87%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 3         | 0.87%   |
| Intel HD Graphics 630                                                                 | 3         | 0.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 0.87%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 0.87%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                              | 3         | 0.87%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                 | 2         | 0.58%   |
| Nvidia GP108 [GeForce GT 1030]                                                        | 2         | 0.58%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 2         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 30.6%   |
| 1 x AMD        | 78        | 27.76%  |
| Intel + Nvidia | 40        | 14.23%  |
| 1 x Nvidia     | 33        | 11.74%  |
| AMD + Nvidia   | 13        | 4.63%   |
| Intel + AMD    | 9         | 3.2%    |
| Other          | 8         | 2.85%   |
| 2 x AMD        | 6         | 2.14%   |
| 1 x Matrox     | 4         | 1.42%   |
| 2 x Intel      | 2         | 0.71%   |
| 1 x ASPEED     | 1         | 0.36%   |
| AMD + ASPEED   | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 207       | 73.67%  |
| Proprietary | 59        | 21%     |
| Unknown     | 15        | 5.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 171       | 60%     |
| 0.01-0.5   | 34        | 11.93%  |
| 1.01-2.0   | 22        | 7.72%   |
| 7.01-8.0   | 21        | 7.37%   |
| 3.01-4.0   | 13        | 4.56%   |
| 8.01-16.0  | 10        | 3.51%   |
| 0.51-1.0   | 10        | 3.51%   |
| 16.01-24.0 | 3         | 1.05%   |
| 5.01-6.0   | 1         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 37        | 12.01%  |
| Dell                 | 34        | 11.04%  |
| BOE                  | 31        | 10.06%  |
| Samsung Electronics  | 29        | 9.42%   |
| Chimei Innolux       | 23        | 7.47%   |
| LG Display           | 20        | 6.49%   |
| Goldstar             | 20        | 6.49%   |
| Acer                 | 12        | 3.9%    |
| Sharp                | 10        | 3.25%   |
| Apple                | 9         | 2.92%   |
| Ancor Communications | 8         | 2.6%    |
| PANDA                | 7         | 2.27%   |
| Hewlett-Packard      | 7         | 2.27%   |
| Lenovo               | 6         | 1.95%   |
| CSO                  | 6         | 1.95%   |
| Iiyama               | 5         | 1.62%   |
| Philips              | 4         | 1.3%    |
| AOC                  | 4         | 1.3%    |
| ViewSonic            | 3         | 0.97%   |
| TMX                  | 3         | 0.97%   |
| ASUSTek Computer     | 3         | 0.97%   |
| Vizio                | 2         | 0.65%   |
| Panasonic            | 2         | 0.65%   |
| MSI                  | 2         | 0.65%   |
| InfoVision           | 2         | 0.65%   |
| HannStar             | 2         | 0.65%   |
| Gigabyte Technology  | 2         | 0.65%   |
| Eizo                 | 2         | 0.65%   |
| BenQ                 | 2         | 0.65%   |
| WST                  | 1         | 0.32%   |
| Valve                | 1         | 0.32%   |
| Unknown (AAA)        | 1         | 0.32%   |
| Toshiba              | 1         | 0.32%   |
| Sceptre Tech         | 1         | 0.32%   |
| RTK                  | 1         | 0.32%   |
| NEC Computers        | 1         | 0.32%   |
| MPI                  | 1         | 0.32%   |
| KDB                  | 1         | 0.32%   |
| JDI                  | 1         | 0.32%   |
| HVR                  | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 1.27%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 4         | 1.27%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.95%   |
| AU Optronics LCD Monitor AUO019C 1920x1200 286x178mm 13.3-inch        | 3         | 0.95%   |
| Apple iMac APPAE05 3840x2160 597x336mm 27.0-inch                      | 3         | 0.95%   |
| Vizio E480i-C2 VIZ1004 1920x1080 477x268mm 21.5-inch                  | 2         | 0.63%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                 | 2         | 0.63%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 2         | 0.63%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.63%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 2         | 0.63%   |
| Goldstar LG Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch            | 2         | 0.63%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 2         | 0.63%   |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                     | 2         | 0.63%   |
| Dell U2415 DELA0BA 1920x1200 518x324mm 24.1-inch                      | 2         | 0.63%   |
| Dell U2311H DELA060 1920x1080 509x286mm 23.0-inch                     | 2         | 0.63%   |
| Dell S3220DGF DELD0F4 2560x1440 697x392mm 31.5-inch                   | 2         | 0.63%   |
| Dell S2721DGF DEL41D9 2560x1440 597x336mm 27.0-inch                   | 2         | 0.63%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN139D 1920x1080 293x165mm 13.2-inch      | 2         | 0.63%   |
| BOE LCD Monitor BOE0B56 1920x1080 309x174mm 14.0-inch                 | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO6DA8 2560x1600 301x188mm 14.0-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch        | 2         | 0.63%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 2         | 0.63%   |
| Apple Color LCD APPA02F 2880x1800 331x207mm 15.4-inch                 | 2         | 0.63%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 480x270mm 21.7-inch | 2         | 0.63%   |
| Acer CP3271K P ACR0716 3840x2160 597x336mm 27.0-inch                  | 2         | 0.63%   |
| WST KL.1350W.005 WST2C34 2256x1504 285x190mm 13.5-inch                | 1         | 0.32%   |
| ViewSonic VX2758-SERIES VSCA738 2560x1440 598x336mm 27.0-inch         | 1         | 0.32%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch         | 1         | 0.32%   |
| ViewSonic VG2030wm VSCA51E 1680x1050 433x270mm 20.1-inch              | 1         | 0.32%   |
| Valve Index HMD VLV91A8                                               | 1         | 0.32%   |
| Unknown (AAA) Monitor AAA0ABF 1920x1080 480x260mm 21.5-inch           | 1         | 0.32%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.32%   |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch               | 1         | 0.32%   |
| Sharp LQ134N1JW55 SHP1558 1920x1200 288x180mm 13.4-inch               | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 121       | 41.16%  |
| 3840x2160 (4K)     | 41        | 13.95%  |
| 2560x1440 (QHD)    | 29        | 9.86%   |
| 2880x1800          | 16        | 5.44%   |
| 1366x768 (WXGA)    | 16        | 5.44%   |
| 1920x1200 (WUXGA)  | 13        | 4.42%   |
| 2560x1600          | 12        | 4.08%   |
| 1280x1024 (SXGA)   | 8         | 2.72%   |
| 3440x1440          | 7         | 2.38%   |
| 2256x1504          | 5         | 1.7%    |
| 1600x900 (HD+)     | 5         | 1.7%    |
| 2560x1080          | 4         | 1.36%   |
| 1680x1050 (WSXGA+) | 3         | 1.02%   |
| 3840x2400          | 2         | 0.68%   |
| 3200x2000          | 2         | 0.68%   |
| 3840x1200          | 1         | 0.34%   |
| 3000x2000          | 1         | 0.34%   |
| 2736x1824          | 1         | 0.34%   |
| 2160x1200          | 1         | 0.34%   |
| 1920x1280          | 1         | 0.34%   |
| 1440x900 (WXGA+)   | 1         | 0.34%   |
| 1280x800 (WXGA)    | 1         | 0.34%   |
| 1280x720 (HD)      | 1         | 0.34%   |
| 1024x600           | 1         | 0.34%   |
| Unknown            | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 53        | 17.61%  |
| 14      | 46        | 15.28%  |
| 13      | 39        | 12.96%  |
| 27      | 38        | 12.62%  |
| 24      | 25        | 8.31%   |
| 23      | 17        | 5.65%   |
| 17      | 12        | 3.99%   |
| 34      | 11        | 3.65%   |
| 16      | 9         | 2.99%   |
| 12      | 9         | 2.99%   |
| 31      | 7         | 2.33%   |
| 21      | 7         | 2.33%   |
| 19      | 4         | 1.33%   |
| 25      | 3         | 1%      |
| 20      | 3         | 1%      |
| 54      | 2         | 0.66%   |
| 22      | 2         | 0.66%   |
| Unknown | 2         | 0.66%   |
| 86      | 1         | 0.33%   |
| 84      | 1         | 0.33%   |
| 46      | 1         | 0.33%   |
| 43      | 1         | 0.33%   |
| 40      | 1         | 0.33%   |
| 39      | 1         | 0.33%   |
| 38      | 1         | 0.33%   |
| 32      | 1         | 0.33%   |
| 28      | 1         | 0.33%   |
| 26      | 1         | 0.33%   |
| 11      | 1         | 0.33%   |
| 10      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 123       | 41.69%  |
| 501-600     | 75        | 25.42%  |
| 201-300     | 37        | 12.54%  |
| 351-400     | 13        | 4.41%   |
| 701-800     | 12        | 4.07%   |
| 601-700     | 12        | 4.07%   |
| 401-500     | 12        | 4.07%   |
| 1001-1500   | 5         | 1.69%   |
| 801-900     | 3         | 1.02%   |
| Unknown     | 2         | 0.68%   |
| 1501-2000   | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 183       | 68.54%  |
| 16/10   | 53        | 19.85%  |
| 21/9    | 11        | 4.12%   |
| 3/2     | 8         | 3%      |
| 5/4     | 7         | 2.62%   |
| 6/5     | 1         | 0.37%   |
| 3.20    | 1         | 0.37%   |
| 1.00    | 1         | 0.37%   |
| 0.56    | 1         | 0.37%   |
| Unknown | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 81-90          | 67        | 22.26%  |
| 101-110        | 54        | 17.94%  |
| 201-250        | 40        | 13.29%  |
| 301-350        | 39        | 12.96%  |
| 351-500        | 20        | 6.64%   |
| 71-80          | 18        | 5.98%   |
| 251-300        | 11        | 3.65%   |
| 151-200        | 10        | 3.32%   |
| 61-70          | 8         | 2.66%   |
| 121-130        | 8         | 2.66%   |
| 111-120        | 8         | 2.66%   |
| 501-1000       | 5         | 1.66%   |
| More than 1000 | 4         | 1.33%   |
| 141-150        | 4         | 1.33%   |
| Unknown        | 2         | 0.66%   |
| 51-60          | 1         | 0.33%   |
| 41-50          | 1         | 0.33%   |
| 131-140        | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 81        | 28.22%  |
| 51-100        | 66        | 23%     |
| 161-240       | 62        | 21.6%   |
| 101-120       | 47        | 16.38%  |
| More than 240 | 25        | 8.71%   |
| 1-50          | 4         | 1.39%   |
| Unknown       | 2         | 0.7%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 195       | 67.94%  |
| 2     | 51        | 17.77%  |
| 0     | 30        | 10.45%  |
| 3     | 11        | 3.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 179       | 44.86%  |
| Realtek Semiconductor             | 127       | 31.83%  |
| MediaTek                          | 24        | 6.02%   |
| Qualcomm Atheros                  | 16        | 4.01%   |
| Broadcom                          | 15        | 3.76%   |
| Aquantia                          | 5         | 1.25%   |
| Qualcomm                          | 4         | 1%      |
| Lenovo                            | 4         | 1%      |
| TP-Link                           | 3         | 0.75%   |
| Microsoft                         | 3         | 0.75%   |
| Ralink Technology                 | 2         | 0.5%    |
| Xiaomi                            | 1         | 0.25%   |
| Texas Instruments                 | 1         | 0.25%   |
| STMicroelectronics                | 1         | 0.25%   |
| Standard Microsystems             | 1         | 0.25%   |
| Ralink                            | 1         | 0.25%   |
| QinHeng Electronics               | 1         | 0.25%   |
| Pulse-Eight                       | 1         | 0.25%   |
| Oculus VR                         | 1         | 0.25%   |
| Nvidia                            | 1         | 0.25%   |
| ICS Advent                        | 1         | 0.25%   |
| Google                            | 1         | 0.25%   |
| Fibocom                           | 1         | 0.25%   |
| Ericsson Business Mobile Networks | 1         | 0.25%   |
| Edimax Technology                 | 1         | 0.25%   |
| D-Link System                     | 1         | 0.25%   |
| D-Link                            | 1         | 0.25%   |
| ASUSTek Computer                  | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76        | 15.93%  |
| Intel Wi-Fi 6 AX200                                               | 27        | 5.66%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 5.24%   |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 3.35%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 14        | 2.94%   |
| Intel I211 Gigabit Network Connection                             | 14        | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 13        | 2.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 13        | 2.73%   |
| Intel Wireless 8265 / 8275                                        | 10        | 2.1%    |
| Intel Wi-Fi 6 AX201                                               | 10        | 2.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 9         | 1.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 8         | 1.68%   |
| Intel Wireless 8260                                               | 7         | 1.47%   |
| Intel Wireless 7265                                               | 7         | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.47%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 6         | 1.26%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.26%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 6         | 1.26%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 5         | 1.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.05%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.05%   |
| Intel Wireless-AC 9260                                            | 4         | 0.84%   |
| Intel Wireless 7260                                               | 4         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.84%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.63%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.63%   |
| Intel Wireless 3160                                               | 3         | 0.63%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 3         | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 147       | 63.91%  |
| MediaTek                          | 24        | 10.43%  |
| Realtek Semiconductor             | 18        | 7.83%   |
| Qualcomm Atheros                  | 12        | 5.22%   |
| Broadcom                          | 11        | 4.78%   |
| TP-Link                           | 3         | 1.3%    |
| Qualcomm                          | 3         | 1.3%    |
| Microsoft                         | 3         | 1.3%    |
| Ralink Technology                 | 2         | 0.87%   |
| Ralink                            | 1         | 0.43%   |
| Fibocom                           | 1         | 0.43%   |
| Ericsson Business Mobile Networks | 1         | 0.43%   |
| Edimax Technology                 | 1         | 0.43%   |
| D-Link System                     | 1         | 0.43%   |
| D-Link                            | 1         | 0.43%   |
| ASUSTek Computer                  | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 27        | 11.74%  |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 14        | 6.09%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 13        | 5.65%   |
| Intel Wireless 8265 / 8275                                    | 10        | 4.35%   |
| Intel Wi-Fi 6 AX201                                           | 10        | 4.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 9         | 3.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 8         | 3.48%   |
| Intel Wireless 8260                                           | 7         | 3.04%   |
| Intel Wireless 7265                                           | 7         | 3.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 6         | 2.61%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 6         | 2.61%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 6         | 2.61%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 5         | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 5         | 2.17%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 5         | 2.17%   |
| Intel Wireless-AC 9260                                        | 4         | 1.74%   |
| Intel Wireless 7260                                           | 4         | 1.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 4         | 1.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 4         | 1.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 4         | 1.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 4         | 1.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 3         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 1.3%    |
| Intel Wireless 3160                                           | 3         | 1.3%    |
| Intel Raptor Lake PCH CNVi WiFi                               | 3         | 1.3%    |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 3         | 1.3%    |
| Intel Alder Lake-S PCH CNVi WiFi                              | 3         | 1.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 0.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2         | 0.87%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 2         | 0.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 2         | 0.87%   |
| Microsoft Xbox 360 Wireless Adapter                           | 2         | 0.87%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter             | 2         | 0.87%   |
| Intel Wireless 3165                                           | 2         | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 0.87%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter  | 2         | 0.87%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.43%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 0.43%   |
| TP-Link 802.11ac NIC                                          | 1         | 0.43%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 113       | 49.13%  |
| Intel                 | 87        | 37.83%  |
| Broadcom              | 10        | 4.35%   |
| Qualcomm Atheros      | 5         | 2.17%   |
| Aquantia              | 5         | 2.17%   |
| Lenovo                | 4         | 1.74%   |
| Xiaomi                | 1         | 0.43%   |
| Standard Microsystems | 1         | 0.43%   |
| Qualcomm              | 1         | 0.43%   |
| Nvidia                | 1         | 0.43%   |
| ICS Advent            | 1         | 0.43%   |
| Google                | 1         | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76        | 31.54%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 25        | 10.37%  |
| Realtek RTL8125 2.5GbE Controller                                 | 16        | 6.64%   |
| Intel I211 Gigabit Network Connection                             | 14        | 5.81%   |
| Intel Ethernet Controller I225-V                                  | 13        | 5.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.9%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 2.49%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 2.07%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 2.07%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.66%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 1.24%   |
| Intel Ethernet Connection I217-V                                  | 3         | 1.24%   |
| Intel Ethernet Connection (7) I219-LM                             | 3         | 1.24%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.24%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.24%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.24%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 1.24%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.83%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 0.83%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.83%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.83%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.83%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.83%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.83%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.41%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.41%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.41%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.41%   |
| Nvidia MCP55 Ethernet                                             | 1         | 0.41%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.41%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.41%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.41%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.41%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 219       | 50.46%  |
| Ethernet | 209       | 48.16%  |
| Modem    | 5         | 1.15%   |
| Unknown  | 1         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 184       | 63.45%  |
| Ethernet | 106       | 36.55%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 132       | 46.64%  |
| 1     | 130       | 45.94%  |
| 3     | 12        | 4.24%   |
| 0     | 7         | 2.47%   |
| 4     | 2         | 0.71%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 205       | 71.68%  |
| Yes  | 81        | 28.32%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 134       | 61.75%  |
| Realtek Semiconductor           | 13        | 5.99%   |
| Foxconn / Hon Hai               | 10        | 4.61%   |
| Apple                           | 9         | 4.15%   |
| MediaTek                        | 8         | 3.69%   |
| IMC Networks                    | 8         | 3.69%   |
| Cambridge Silicon Radio         | 8         | 3.69%   |
| Broadcom                        | 7         | 3.23%   |
| Qualcomm Atheros Communications | 6         | 2.76%   |
| ASUSTek Computer                | 6         | 2.76%   |
| USI                             | 2         | 0.92%   |
| Lite-On Technology              | 2         | 0.92%   |
| Realtek                         | 1         | 0.46%   |
| Opticis                         | 1         | 0.46%   |
| Integrated System Solution      | 1         | 0.46%   |
| HTC (High Tech Computer)        | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                   | 29        | 13.36%  |
| Intel AX200 Bluetooth                                                | 25        | 11.52%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 20        | 9.22%   |
| Intel AX201 Bluetooth                                                | 20        | 9.22%   |
| Intel Bluetooth Device                                               | 18        | 8.29%   |
| Intel AX210 Bluetooth                                                | 13        | 5.99%   |
| Realtek Bluetooth Radio                                              | 10        | 4.61%   |
| MediaTek Wireless_Device                                             | 8         | 3.69%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 8         | 3.69%   |
| Foxconn / Hon Hai Wireless_Device                                    | 6         | 2.76%   |
| IMC Networks Wireless_Device                                         | 5         | 2.3%    |
| Apple Bluetooth Host Controller                                      | 5         | 2.3%    |
| Intel Wireless-AC 3168 Bluetooth                                     | 4         | 1.84%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 4         | 1.84%   |
| Apple Bluetooth USB Host Controller                                  | 4         | 1.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 3         | 1.38%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                         | 3         | 1.38%   |
| USI Bluetooth Device                                                 | 2         | 0.92%   |
| Qualcomm Atheros  Bluetooth Device                                   | 2         | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 2         | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 2         | 0.92%   |
| Broadcom HP Portable SoftSailing                                     | 2         | 0.92%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 2         | 0.92%   |
| ASUS ASUS USB-BT500                                                  | 2         | 0.92%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                              | 1         | 0.46%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 1         | 0.46%   |
| Realtek 802.11ac WLAN Adapter                                        | 1         | 0.46%   |
| Realtek 802.11ac WLAN Adapter                                        | 1         | 0.46%   |
| Qualcomm Atheros AR9462 Bluetooth                                    | 1         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                | 1         | 0.46%   |
| Opticis Bluetooth Radio                                              | 1         | 0.46%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 1         | 0.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                     | 1         | 0.46%   |
| Integrated System Solution Bluetooth Device                          | 1         | 0.46%   |
| IMC Networks Bluetooth Radio                                         | 1         | 0.46%   |
| IMC Networks Bluetooth Device                                        | 1         | 0.46%   |
| IMC Networks BCM20702A0                                              | 1         | 0.46%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 1         | 0.46%   |
| Foxconn / Hon Hai Bluetooth Adapter                                  | 1         | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                           | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 168       | 38.18%  |
| AMD                                  | 116       | 26.36%  |
| Nvidia                               | 66        | 15%     |
| C-Media Electronics                  | 10        | 2.27%   |
| Lenovo                               | 6         | 1.36%   |
| Razer USA                            | 5         | 1.14%   |
| Focusrite-Novation                   | 5         | 1.14%   |
| Texas Instruments                    | 4         | 0.91%   |
| Kingston Technology                  | 4         | 0.91%   |
| Creative Technology                  | 4         | 0.91%   |
| Realtek Semiconductor                | 3         | 0.68%   |
| AudioQuest                           | 3         | 0.68%   |
| ASUSTek Computer                     | 3         | 0.68%   |
| Synaptics                            | 2         | 0.45%   |
| Schiit Audio                         | 2         | 0.45%   |
| RODE Microphones                     | 2         | 0.45%   |
| Logitech                             | 2         | 0.45%   |
| Hewlett-Packard                      | 2         | 0.45%   |
| DSEA A/S                             | 2         | 0.45%   |
| Corsair                              | 2         | 0.45%   |
| Blue Microphones                     | 2         | 0.45%   |
| Yamaha                               | 1         | 0.23%   |
| Valve Software                       | 1         | 0.23%   |
| Trust                                | 1         | 0.23%   |
| Thomann                              | 1         | 0.23%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.23%   |
| Sony                                 | 1         | 0.23%   |
| Shure                                | 1         | 0.23%   |
| Sennheiser Communications            | 1         | 0.23%   |
| Satechi                              | 1         | 0.23%   |
| Samson Technologies                  | 1         | 0.23%   |
| PreSonus Audio Electronics           | 1         | 0.23%   |
| Mark of the Unicorn                  | 1         | 0.23%   |
| JMTek                                | 1         | 0.23%   |
| Huawei Technologies                  | 1         | 0.23%   |
| GYROCOM C&C                          | 1         | 0.23%   |
| Goldvish                             | 1         | 0.23%   |
| GN Netcom                            | 1         | 0.23%   |
| Giga-Byte Technology                 | 1         | 0.23%   |
| Elgato Systems                       | 1         | 0.23%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 57        | 10.48%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 33        | 6.07%   |
| AMD Starship/Matisse HD Audio Controller                                | 29        | 5.33%   |
| Intel Sunrise Point-LP HD Audio                                         | 24        | 4.41%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 20        | 3.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 15        | 2.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 15        | 2.76%   |
| Intel Cannon Lake PCH cAVS                                              | 14        | 2.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 14        | 2.57%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 12        | 2.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 11        | 2.02%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]              | 10        | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 9         | 1.65%   |
| AMD Navi 10 HDMI Audio                                                  | 9         | 1.65%   |
| Nvidia Audio device                                                     | 7         | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 7         | 1.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 7         | 1.29%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 7         | 1.29%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                     | 7         | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                         | 6         | 1.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 6         | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                           | 5         | 0.92%   |
| Nvidia GA104 High Definition Audio Controller                           | 5         | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 5         | 0.92%   |
| Intel Broadwell-U Audio Controller                                      | 5         | 0.92%   |
| Nvidia TU116 High Definition Audio Controller                           | 4         | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 4         | 0.74%   |
| Nvidia GP104 High Definition Audio Controller                           | 4         | 0.74%   |
| Nvidia GK104 HDMI Audio Controller                                      | 4         | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                           | 4         | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 0.74%   |
| Intel Haswell-ULT HD Audio Controller                                   | 4         | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                            | 4         | 0.74%   |
| Intel Comet Lake PCH cAVS                                               | 4         | 0.74%   |
| Intel 8 Series HD Audio Controller                                      | 4         | 0.74%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1        | 4         | 0.74%   |
| AMD Navi 31 HDMI/DP Audio                                               | 4         | 0.74%   |
| Texas Instruments PCM2902 Audio Codec                                   | 3         | 0.55%   |
| Realtek Semiconductor USB Audio                                         | 3         | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                           | 3         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 64        | 20.32%  |
| SK hynix                     | 52        | 16.51%  |
| Micron Technology            | 41        | 13.02%  |
| Kingston                     | 36        | 11.43%  |
| Corsair                      | 32        | 10.16%  |
| G.Skill                      | 21        | 6.67%   |
| Crucial                      | 20        | 6.35%   |
| Unknown                      | 12        | 3.81%   |
| Team                         | 7         | 2.22%   |
| Unknown (ABCD)               | 5         | 1.59%   |
| A-DATA Technology            | 5         | 1.59%   |
| Ramaxel Technology           | 3         | 0.95%   |
| Unknown                      | 3         | 0.95%   |
| Lexar                        | 2         | 0.63%   |
| GOODRAM                      | 2         | 0.63%   |
| AMD                          | 2         | 0.63%   |
| Unknown (0x59B)              | 1         | 0.32%   |
| Strontium                    | 1         | 0.32%   |
| Smart Brazil                 | 1         | 0.32%   |
| Patriot Memory (PDP Systems) | 1         | 0.32%   |
| Patriot                      | 1         | 0.32%   |
| GLOWAY                       | 1         | 0.32%   |
| Avant                        | 1         | 0.32%   |
| Apacer                       | 1         | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.78%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.19%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 1.19%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.19%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 4         | 1.19%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 3         | 0.89%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 0.89%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.89%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 0.89%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.89%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 3         | 0.89%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s             | 3         | 0.89%   |
| Unknown                                                          | 3         | 0.89%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.59%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1867MT/s                     | 2         | 0.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.59%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 2         | 0.59%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.59%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.59%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 0.59%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.59%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.59%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 2         | 0.59%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 2         | 0.59%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB SODIMM LPDDR5 6400MT/s       | 2         | 0.59%   |
| Micron RAM MT62F1G32D4DR-031 4GB SODIMM LPDDR5 5500MT/s          | 2         | 0.59%   |
| Micron RAM MT62F1G32D4DR-031 2GB Row Of Chips LPDDR5 6400MT/s    | 2         | 0.59%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 0.59%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.59%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.59%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s           | 2         | 0.59%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 2         | 0.59%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 2         | 0.59%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s              | 2         | 0.59%   |
| Kingston RAM KHX2400C15/16G 16GB DIMM DDR4 3334MT/s              | 2         | 0.59%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s           | 2         | 0.59%   |
| Corsair RAM Module 16GB DIMM DDR4 2133MT/s                       | 2         | 0.59%   |
| Corsair RAM CMK64GX4M2D3600C18 32GB DIMM DDR4 3600MT/s           | 2         | 0.59%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 2         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 150       | 55.76%  |
| DDR3    | 48        | 17.84%  |
| LPDDR5  | 24        | 8.92%   |
| LPDDR4  | 20        | 7.43%   |
| DDR5    | 15        | 5.58%   |
| LPDDR3  | 8         | 2.97%   |
| SDRAM   | 1         | 0.37%   |
| DRAM    | 1         | 0.37%   |
| DDR     | 1         | 0.37%   |
| Unknown | 1         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 141       | 51.27%  |
| DIMM         | 87        | 31.64%  |
| Row Of Chips | 42        | 15.27%  |
| Chip         | 3         | 1.09%   |
| RIMM         | 1         | 0.36%   |
| Unknown      | 1         | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 131       | 43.52%  |
| 16384 | 74        | 24.58%  |
| 4096  | 51        | 16.94%  |
| 32768 | 37        | 12.29%  |
| 2048  | 6         | 1.99%   |
| 65536 | 1         | 0.33%   |
| 1024  | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 67        | 22.64%  |
| 1600    | 37        | 12.5%   |
| 2667    | 34        | 11.49%  |
| 2133    | 22        | 7.43%   |
| 6400    | 21        | 7.09%   |
| 2400    | 21        | 7.09%   |
| 3600    | 11        | 3.72%   |
| 4267    | 10        | 3.38%   |
| 3733    | 7         | 2.36%   |
| 1867    | 7         | 2.36%   |
| 4800    | 6         | 2.03%   |
| 1333    | 6         | 2.03%   |
| 6000    | 4         | 1.35%   |
| 5600    | 4         | 1.35%   |
| 4266    | 4         | 1.35%   |
| 3266    | 4         | 1.35%   |
| 3000    | 4         | 1.35%   |
| 5500    | 2         | 0.68%   |
| 5200    | 2         | 0.68%   |
| 3866    | 2         | 0.68%   |
| 3534    | 2         | 0.68%   |
| 3400    | 2         | 0.68%   |
| 3334    | 2         | 0.68%   |
| 2933    | 2         | 0.68%   |
| 7500    | 1         | 0.34%   |
| 4000    | 1         | 0.34%   |
| 3800    | 1         | 0.34%   |
| 3666    | 1         | 0.34%   |
| 2800    | 1         | 0.34%   |
| 2666    | 1         | 0.34%   |
| 2134    | 1         | 0.34%   |
| 2132    | 1         | 0.34%   |
| 1866    | 1         | 0.34%   |
| 1334    | 1         | 0.34%   |
| 1066    | 1         | 0.34%   |
| 800     | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Xerox              | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |
| Brother Industries | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Xerox Phaser 6125N      | 1         | 33.33%  |
| Canon TR8500 series     | 1         | 33.33%  |
| Brother HL-2240D series | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 17.32%  |
| IMC Networks                           | 24        | 13.41%  |
| Logitech                               | 23        | 12.85%  |
| Microdia                               | 17        | 9.5%    |
| Bison Electronics                      | 16        | 8.94%   |
| Realtek Semiconductor                  | 15        | 8.38%   |
| Sunplus Innovation Technology          | 9         | 5.03%   |
| Apple                                  | 5         | 2.79%   |
| Syntek                                 | 4         | 2.23%   |
| Quanta                                 | 4         | 2.23%   |
| ShineTech                              | 3         | 1.68%   |
| MacroSilicon                           | 3         | 1.68%   |
| Lite-On Technology                     | 3         | 1.68%   |
| Acer                                   | 3         | 1.68%   |
| Sonix Technology                       | 2         | 1.12%   |
| Primax Electronics                     | 2         | 1.12%   |
| Luxvisions Innotech Limited            | 2         | 1.12%   |
| HDR webcam                             | 2         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.12%   |
| Alcor Micro                            | 2         | 1.12%   |
| Valve Software                         | 1         | 0.56%   |
| SunplusIT                              | 1         | 0.56%   |
| Silicon Motion                         | 1         | 0.56%   |
| Samsung Electronics                    | 1         | 0.56%   |
| OPPO Electronics                       | 1         | 0.56%   |
| Microsoft                              | 1         | 0.56%   |
| globaloptics                           | 1         | 0.56%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 19        | 10.5%   |
| IMC Networks USB2.0 HD UVC WebCam       | 11        | 6.08%   |
| Bison Integrated Camera                 | 10        | 5.52%   |
| IMC Networks Integrated Camera          | 9         | 4.97%   |
| Microdia Integrated_Webcam_HD           | 8         | 4.42%   |
| Realtek Integrated_Webcam_HD            | 7         | 3.87%   |
| Chicony HP HD Camera                    | 7         | 3.87%   |
| Logitech HD Pro Webcam C920             | 6         | 3.31%   |
| Syntek Integrated Camera                | 4         | 2.21%   |
| Logitech StreamCam                      | 4         | 2.21%   |
| Sunplus Integrated_Webcam_FHD           | 3         | 1.66%   |
| Realtek Laptop Camera                   | 3         | 1.66%   |
| MacroSilicon USB Video                  | 3         | 1.66%   |
| Logitech Webcam C270                    | 3         | 1.66%   |
| Apple FaceTime HD Camera (Built-in)     | 3         | 1.66%   |
| Sunplus Integrated_Webcam_HD            | 2         | 1.1%    |
| ShineTech USB2.0 HD UVC WebCam          | 2         | 1.1%    |
| Primax HP HD Webcam [Fixed]             | 2         | 1.1%    |
| Microdia Webcam Vitade AF               | 2         | 1.1%    |
| Microdia Integrated Webcam              | 2         | 1.1%    |
| Lite-On Integrated Camera               | 2         | 1.1%    |
| HDR webcam HDR webcam                   | 2         | 1.1%    |
| Bison HD Webcam                         | 2         | 1.1%    |
| Alcor Micro USB 2.0 Camera              | 2         | 1.1%    |
| Valve Software 3D Camera                | 1         | 0.55%   |
| SunplusIT HP TrueVision HD Camera       | 1         | 0.55%   |
| Sunplus XiaoMi USB 2.0 Webcam           | 1         | 0.55%   |
| Sunplus Laptop Integrated Webcam FHD    | 1         | 0.55%   |
| Sunplus HD WebCam                       | 1         | 0.55%   |
| Sunplus FHD Camera Microphone           | 1         | 0.55%   |
| Sonix USB2.0 HD UVC WebCam              | 1         | 0.55%   |
| Sonix USB2.0 FHD UVC WebCam             | 1         | 0.55%   |
| Silicon Motion WebCam SC-13HDL11431N    | 1         | 0.55%   |
| Shinetech USB2.0 FHD UVC WebCam         | 1         | 0.55%   |
| Samsung Galaxy series, misc. (MTP mode) | 1         | 0.55%   |
| Realtek TV Camera                       | 1         | 0.55%   |
| Realtek Thronmax Webcam Mic             | 1         | 0.55%   |
| Realtek Lenovo EasyCamera               | 1         | 0.55%   |
| Realtek Integrated Webcam               | 1         | 0.55%   |
| Realtek HD WebCam                       | 1         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 41.3%   |
| Validity Sensors           | 15        | 32.61%  |
| Shenzhen Goodix Technology | 10        | 21.74%  |
| Gingytech                  | 1         | 2.17%   |
| Focal-systems.Corp         | 1         | 2.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 17.39%  |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 15.22%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 6.52%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 6.52%   |
| Synaptics UWP WBDI                                                         | 3         | 6.52%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 6.52%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 6.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 4.35%   |
| Validity Sensors VFS491                                                    | 2         | 4.35%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.35%   |
| Synaptics UWP WBDI Device                                                  | 2         | 4.35%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 4.35%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.17%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.17%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 2.17%   |
| Gingytech Fingerprint sensor                                               | 1         | 2.17%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 18        | 64.29%  |
| Broadcom    | 5         | 17.86%  |
| Yubico.com  | 3         | 10.71%  |
| Upek        | 1         | 3.57%   |
| OmniKey     | 1         | 3.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 18        | 64.29%  |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 2         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 7.14%   |
| Broadcom 5880                                              | 2         | 7.14%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 3.57%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 3.57%   |
| OmniKey CardMan Smart@Link                                 | 1         | 3.57%   |
| Broadcom 58200                                             | 1         | 3.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 167       | 57.39%  |
| 1     | 84        | 28.87%  |
| 2     | 36        | 12.37%  |
| 4     | 2         | 0.69%   |
| 3     | 2         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 27.16%  |
| Multimedia controller    | 34        | 20.99%  |
| Graphics card            | 25        | 15.43%  |
| Chipcard                 | 23        | 14.2%   |
| Net/wireless             | 12        | 7.41%   |
| Camera                   | 6         | 3.7%    |
| Bluetooth                | 5         | 3.09%   |
| Unassigned class         | 3         | 1.85%   |
| Modem                    | 2         | 1.23%   |
| Communication controller | 2         | 1.23%   |
| Card reader              | 2         | 1.23%   |
| Storage/ata              | 1         | 0.62%   |
| Network                  | 1         | 0.62%   |
| Firewire controller      | 1         | 0.62%   |
| Dvb card                 | 1         | 0.62%   |

