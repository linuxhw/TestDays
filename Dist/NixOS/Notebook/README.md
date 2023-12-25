NixOS - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for NixOS.

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

Total: 211

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ZBook 17 G5                 | [ad6c489ffc](https://linux-hardware.org/?probe=ad6c489ffc) | Dec 23, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [ef18e09b69](https://linux-hardware.org/?probe=ef18e09b69) | Dec 23, 2023 |
| Lenovo        | Legion Y7000 81FW           | [f67367aa62](https://linux-hardware.org/?probe=f67367aa62) | Dec 23, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [fb187c2fa4](https://linux-hardware.org/?probe=fb187c2fa4) | Dec 20, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [73693b1a91](https://linux-hardware.org/?probe=73693b1a91) | Dec 17, 2023 |
| Lenovo        | Legion Y7000 81FW           | [71c27a1bf6](https://linux-hardware.org/?probe=71c27a1bf6) | Dec 17, 2023 |
| Medion        | M14L-256                    | [6cd85934b3](https://linux-hardware.org/?probe=6cd85934b3) | Dec 15, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [87be870a89](https://linux-hardware.org/?probe=87be870a89) | Dec 09, 2023 |
| MSI           | Prestige 14 A10SC           | [85d6d037cc](https://linux-hardware.org/?probe=85d6d037cc) | Dec 09, 2023 |
| Dell          | G5 5590                     | [6970987854](https://linux-hardware.org/?probe=6970987854) | Dec 08, 2023 |
| HP            | EliteBook 850 G5            | [aae20908c5](https://linux-hardware.org/?probe=aae20908c5) | Dec 05, 2023 |
| Dell          | Latitude 5290 2-in-1        | [525166f0d5](https://linux-hardware.org/?probe=525166f0d5) | Dec 04, 2023 |
| Apple         | MacBookPro9,2               | [1784c4c5b0](https://linux-hardware.org/?probe=1784c4c5b0) | Dec 01, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [9f7f83e1ee](https://linux-hardware.org/?probe=9f7f83e1ee) | Nov 28, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [05c1dddd8d](https://linux-hardware.org/?probe=05c1dddd8d) | Nov 23, 2023 |
| Lenovo        | ThinkPad T450s 20BX001MU... | [80d4678e90](https://linux-hardware.org/?probe=80d4678e90) | Nov 23, 2023 |
| HP            | EliteBook 850 G5            | [602aeb4101](https://linux-hardware.org/?probe=602aeb4101) | Nov 22, 2023 |
| Lenovo        | Legion Y7000P IAH7 82RC     | [4065934176](https://linux-hardware.org/?probe=4065934176) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [fbde674650](https://linux-hardware.org/?probe=fbde674650) | Nov 22, 2023 |
| Apple         | MacBookPro11,4              | [f21a42a965](https://linux-hardware.org/?probe=f21a42a965) | Nov 16, 2023 |
| Apple         | MacBookPro9,2               | [ac7deed0de](https://linux-hardware.org/?probe=ac7deed0de) | Nov 16, 2023 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [455efd5541](https://linux-hardware.org/?probe=455efd5541) | Nov 15, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [ce6a10d6a3](https://linux-hardware.org/?probe=ce6a10d6a3) | Nov 15, 2023 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [789eee99a6](https://linux-hardware.org/?probe=789eee99a6) | Nov 12, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [c55053fa25](https://linux-hardware.org/?probe=c55053fa25) | Nov 12, 2023 |
| HP            | EliteBook 845 14 inch G1... | [dfbaeb29c5](https://linux-hardware.org/?probe=dfbaeb29c5) | Nov 11, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [79e23fd44a](https://linux-hardware.org/?probe=79e23fd44a) | Nov 07, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [2f6078ab72](https://linux-hardware.org/?probe=2f6078ab72) | Nov 07, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [49b3b70e38](https://linux-hardware.org/?probe=49b3b70e38) | Nov 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | [0e5f976d6b](https://linux-hardware.org/?probe=0e5f976d6b) | Nov 02, 2023 |
| Dell          | XPS 9315                    | [6f3e496918](https://linux-hardware.org/?probe=6f3e496918) | Oct 29, 2023 |
| HP            | EliteBook 850 G4            | [68da315076](https://linux-hardware.org/?probe=68da315076) | Oct 28, 2023 |
| Apple         | MacBookPro9,2               | [b075cf8841](https://linux-hardware.org/?probe=b075cf8841) | Oct 28, 2023 |
| HP            | EliteBook Folio 9470m       | [765f6f8003](https://linux-hardware.org/?probe=765f6f8003) | Oct 25, 2023 |
| Lenovo        | Slim 7 16IAH7 82VB          | [a80fcc753e](https://linux-hardware.org/?probe=a80fcc753e) | Oct 25, 2023 |
| MSI           | GE70 2PE                    | [c0bcd133c9](https://linux-hardware.org/?probe=c0bcd133c9) | Oct 22, 2023 |
| HP            | EliteBook Folio 9470m       | [f342373f65](https://linux-hardware.org/?probe=f342373f65) | Oct 20, 2023 |
| Framework     | Laptop                      | [e765d5da63](https://linux-hardware.org/?probe=e765d5da63) | Oct 18, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [feaf25f8e8](https://linux-hardware.org/?probe=feaf25f8e8) | Oct 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ba690b36a3](https://linux-hardware.org/?probe=ba690b36a3) | Oct 12, 2023 |
| MSI           | Prestige 16Studio A13VE     | [0209063983](https://linux-hardware.org/?probe=0209063983) | Oct 12, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [7ff5fe9fdd](https://linux-hardware.org/?probe=7ff5fe9fdd) | Oct 11, 2023 |
| Lenovo        | ThinkPad P50 20EQS4QL11     | [a4d6af03fe](https://linux-hardware.org/?probe=a4d6af03fe) | Oct 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| HP            | EliteBook Folio 9470m       | [9cecfe7ba5](https://linux-hardware.org/?probe=9cecfe7ba5) | Oct 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [801a2a4abf](https://linux-hardware.org/?probe=801a2a4abf) | Oct 09, 2023 |
| Dell          | Latitude E6540              | [fc3ea4bb32](https://linux-hardware.org/?probe=fc3ea4bb32) | Oct 08, 2023 |
| Dell          | Inspiron 3542               | [90f777d9cc](https://linux-hardware.org/?probe=90f777d9cc) | Oct 07, 2023 |
| Dell          | Latitude E6540              | [a4fbd5793d](https://linux-hardware.org/?probe=a4fbd5793d) | Oct 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [c67f66f5e3](https://linux-hardware.org/?probe=c67f66f5e3) | Oct 01, 2023 |
| Dell          | Latitude E6540              | [8fdc000f7e](https://linux-hardware.org/?probe=8fdc000f7e) | Oct 01, 2023 |
| Dell          | Latitude E6540              | [a5de8b78e7](https://linux-hardware.org/?probe=a5de8b78e7) | Oct 01, 2023 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1135ddac8e](https://linux-hardware.org/?probe=1135ddac8e) | Sep 30, 2023 |
| Dell          | Latitude 5430               | [583aa8cf02](https://linux-hardware.org/?probe=583aa8cf02) | Sep 29, 2023 |
| Intel         | SharkBay Platform           | [2406bf1c0d](https://linux-hardware.org/?probe=2406bf1c0d) | Sep 29, 2023 |
| Dell          | Latitude E6540              | [1478e1265d](https://linux-hardware.org/?probe=1478e1265d) | Sep 29, 2023 |
| Dell          | XPS 15 9560                 | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Dell          | Latitude E6540              | [7d9885cd7c](https://linux-hardware.org/?probe=7d9885cd7c) | Sep 27, 2023 |
| HP            | EliteBook Folio 9470m       | [78d31814cf](https://linux-hardware.org/?probe=78d31814cf) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [0d7d5f0613](https://linux-hardware.org/?probe=0d7d5f0613) | Sep 26, 2023 |
| HP            | EliteBook Folio 9470m       | [086b0dc21a](https://linux-hardware.org/?probe=086b0dc21a) | Sep 23, 2023 |
| HP            | EliteBook 8470p             | [220a0f8733](https://linux-hardware.org/?probe=220a0f8733) | Sep 23, 2023 |
| Apple         | MacBookPro9,2               | [bf71bcd90e](https://linux-hardware.org/?probe=bf71bcd90e) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Apple         | MacBookPro9,2               | [4d2c8f9f07](https://linux-hardware.org/?probe=4d2c8f9f07) | Sep 20, 2023 |
| HP            | EliteBook Folio 9470m       | [5e50efa2c4](https://linux-hardware.org/?probe=5e50efa2c4) | Sep 19, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| Dell          | Latitude E6540              | [ff29b23e60](https://linux-hardware.org/?probe=ff29b23e60) | Sep 13, 2023 |
| Acer          | Aspire E5-575G              | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S4RV00    | [8ae7288bf3](https://linux-hardware.org/?probe=8ae7288bf3) | Sep 11, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD00B... | [5778731f85](https://linux-hardware.org/?probe=5778731f85) | Sep 10, 2023 |
| Dell          | Precision 5680              | [fdcb7ce5d4](https://linux-hardware.org/?probe=fdcb7ce5d4) | Sep 05, 2023 |
| Lenovo        | ThinkPad T470 20HES2RC00    | [390104a086](https://linux-hardware.org/?probe=390104a086) | Aug 28, 2023 |
| Dell          | Wyse 5470                   | [6d45205020](https://linux-hardware.org/?probe=6d45205020) | Aug 27, 2023 |
| Lenovo        | G50-70 20351                | [aed7eacff0](https://linux-hardware.org/?probe=aed7eacff0) | Aug 20, 2023 |
| HP            | EliteBook 8470p             | [320138e7f5](https://linux-hardware.org/?probe=320138e7f5) | Aug 11, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [72bb72d2aa](https://linux-hardware.org/?probe=72bb72d2aa) | Aug 08, 2023 |
| ASUSTek       | ProArt StudioBook W730G5... | [c384115725](https://linux-hardware.org/?probe=c384115725) | Aug 05, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [39fbf6393c](https://linux-hardware.org/?probe=39fbf6393c) | Aug 03, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [a6c2e042e4](https://linux-hardware.org/?probe=a6c2e042e4) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| System76      | Pangolin                    | [3b37a9bedb](https://linux-hardware.org/?probe=3b37a9bedb) | Jul 29, 2023 |
| Alienware     | 17                          | [25f67e59b8](https://linux-hardware.org/?probe=25f67e59b8) | Jul 26, 2023 |
| Apple         | MacBookPro11,3              | [8d48a50003](https://linux-hardware.org/?probe=8d48a50003) | Jul 22, 2023 |
| Apple         | MacBookPro11,3              | [c29abaca55](https://linux-hardware.org/?probe=c29abaca55) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | 1005HA                      | [59a0d6a7bb](https://linux-hardware.org/?probe=59a0d6a7bb) | Jul 19, 2023 |
| MSI           | Alpha 15 B5EEK              | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| Lenovo        | Legion R9000P ARX8 82WM     | [95c540792e](https://linux-hardware.org/?probe=95c540792e) | Jul 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4d377fc8b8](https://linux-hardware.org/?probe=4d377fc8b8) | Jul 01, 2023 |
| Dell          | Latitude E5470              | [fd56f44c38](https://linux-hardware.org/?probe=fd56f44c38) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Microtech     | CoreBook Lite               | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [2812cf43d0](https://linux-hardware.org/?probe=2812cf43d0) | Jun 23, 2023 |
| HP            | EliteBook 820 G3            | [925e5f0915](https://linux-hardware.org/?probe=925e5f0915) | Jun 22, 2023 |
| MECHREVO      | WUJIE 14                    | [a55e31b287](https://linux-hardware.org/?probe=a55e31b287) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [46ffcb9672](https://linux-hardware.org/?probe=46ffcb9672) | Jun 18, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| MACHENIKE     | F117-7P                     | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [0d31f94244](https://linux-hardware.org/?probe=0d31f94244) | May 30, 2023 |
| Dell          | Latitude 5290 2-in-1        | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Lenovo        | G50-70 20351                | [19dc1505b5](https://linux-hardware.org/?probe=19dc1505b5) | May 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [e0cbba6897](https://linux-hardware.org/?probe=e0cbba6897) | May 16, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| Apple         | MacBookPro11,5              | [21ecf73d3a](https://linux-hardware.org/?probe=21ecf73d3a) | May 09, 2023 |
| UNOWHY        | Y13G011S4EI                 | [581cd68800](https://linux-hardware.org/?probe=581cd68800) | May 02, 2023 |
| Lenovo        | G50-70 20351                | [5792e8cfa2](https://linux-hardware.org/?probe=5792e8cfa2) | Apr 29, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [2063d4a9fc](https://linux-hardware.org/?probe=2063d4a9fc) | Apr 27, 2023 |
| Apple         | MacBookPro11,3              | [7fd17e2245](https://linux-hardware.org/?probe=7fd17e2245) | Apr 22, 2023 |
| Avell High... | A70 MOB                     | [869b1ae79b](https://linux-hardware.org/?probe=869b1ae79b) | Apr 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0005GE     | [85a4de4e58](https://linux-hardware.org/?probe=85a4de4e58) | Apr 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Dell          | XPS 9320                    | [c78c87474d](https://linux-hardware.org/?probe=c78c87474d) | Apr 05, 2023 |
| GPD           | G1621-02                    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| ASUSTek       | 1005HA                      | [3326423f04](https://linux-hardware.org/?probe=3326423f04) | Mar 06, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Toshiba       | Satellite L50-B             | [8abe852ff0](https://linux-hardware.org/?probe=8abe852ff0) | Mar 03, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [9b044bd920](https://linux-hardware.org/?probe=9b044bd920) | Feb 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J5... | [c8c79f26d8](https://linux-hardware.org/?probe=c8c79f26d8) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| Blackview     | AceBook 1                   | [ea4db42aa8](https://linux-hardware.org/?probe=ea4db42aa8) | Jan 19, 2023 |
| Dell          | Latitude 7420               | [e770b3e784](https://linux-hardware.org/?probe=e770b3e784) | Jan 04, 2023 |
| Dell          | Latitude 7420               | [bab9b86606](https://linux-hardware.org/?probe=bab9b86606) | Jan 04, 2023 |
| Dell          | Precision M4800             | [505f1b47dc](https://linux-hardware.org/?probe=505f1b47dc) | Dec 30, 2022 |
| GPD           | WIN2                        | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| MSI           | Raider GE67HX 12UGS         | [84c6275c04](https://linux-hardware.org/?probe=84c6275c04) | Dec 25, 2022 |
| Dell          | XPS 15 7590                 | [e070540587](https://linux-hardware.org/?probe=e070540587) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | [e4ba0262b4](https://linux-hardware.org/?probe=e4ba0262b4) | Dec 16, 2022 |
| MECHREVO      | Code01 Ver2.0               | [1a9c49eb4f](https://linux-hardware.org/?probe=1a9c49eb4f) | Dec 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [893190593e](https://linux-hardware.org/?probe=893190593e) | Dec 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [d512bff9cc](https://linux-hardware.org/?probe=d512bff9cc) | Dec 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [fef748b3f4](https://linux-hardware.org/?probe=fef748b3f4) | Dec 04, 2022 |
| Acer          | Aspire A315-54K             | [12f19e4fbe](https://linux-hardware.org/?probe=12f19e4fbe) | Nov 23, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [0c889920b5](https://linux-hardware.org/?probe=0c889920b5) | Nov 12, 2022 |
| Dell          | Latitude E5540              | [f2420e40cd](https://linux-hardware.org/?probe=f2420e40cd) | Nov 06, 2022 |
| Dell          | Latitude E5540              | [2456786404](https://linux-hardware.org/?probe=2456786404) | Nov 06, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [b60f8a187c](https://linux-hardware.org/?probe=b60f8a187c) | Nov 04, 2022 |
| Dell          | Inspiron 5570               | [33d3e9ce22](https://linux-hardware.org/?probe=33d3e9ce22) | Nov 03, 2022 |
| Toshiba       | Satellite L50-B             | [c242c45dbe](https://linux-hardware.org/?probe=c242c45dbe) | Nov 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [d58a7c30a9](https://linux-hardware.org/?probe=d58a7c30a9) | Oct 26, 2022 |
| Lenovo        | ThinkPad E470 20H1006JIX    | [8bc8778497](https://linux-hardware.org/?probe=8bc8778497) | Oct 26, 2022 |
| Dell          | Precision 5760              | [4255007db8](https://linux-hardware.org/?probe=4255007db8) | Oct 18, 2022 |
| HP            | ZBook Studio G5             | [0a9b0167c7](https://linux-hardware.org/?probe=0a9b0167c7) | Oct 17, 2022 |
| Dell          | XPS 13 9310                 | [99232ffba3](https://linux-hardware.org/?probe=99232ffba3) | Oct 13, 2022 |
| Dell          | Inspiron 15 7510            | [263276babe](https://linux-hardware.org/?probe=263276babe) | Sep 30, 2022 |
| Dell          | Inspiron 15 7510            | [86e1da35ba](https://linux-hardware.org/?probe=86e1da35ba) | Sep 30, 2022 |
| Dell          | XPS 15 9570                 | [564eb3b439](https://linux-hardware.org/?probe=564eb3b439) | Sep 28, 2022 |
| Dell          | XPS 15 9570                 | [085bd81d5b](https://linux-hardware.org/?probe=085bd81d5b) | Sep 28, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7fc4cdb860](https://linux-hardware.org/?probe=7fc4cdb860) | Sep 22, 2022 |
| Dell          | Precision M4800             | [fae4dbff63](https://linux-hardware.org/?probe=fae4dbff63) | Sep 13, 2022 |
| Apple         | MacBookPro11,5              | [305905e674](https://linux-hardware.org/?probe=305905e674) | Sep 07, 2022 |
| Apple         | MacBookPro11,5              | [19d3fab687](https://linux-hardware.org/?probe=19d3fab687) | Aug 21, 2022 |
| HP            | ProBook 445 G7              | [898a635cdd](https://linux-hardware.org/?probe=898a635cdd) | Aug 20, 2022 |
| HP            | ProBook 445 G7              | [28e67ea5a7](https://linux-hardware.org/?probe=28e67ea5a7) | Aug 20, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [9351f31042](https://linux-hardware.org/?probe=9351f31042) | Aug 13, 2022 |
| Dell          | Latitude 7420               | [219cf18b1e](https://linux-hardware.org/?probe=219cf18b1e) | Jul 06, 2022 |
| Dell          | XPS 13 9310                 | [380770f287](https://linux-hardware.org/?probe=380770f287) | Jun 15, 2022 |
| Dell          | XPS 13 9310                 | [248f252b2a](https://linux-hardware.org/?probe=248f252b2a) | Jun 13, 2022 |
| Lenovo        | ThinkPad X230 23243E9       | [85ffd2561e](https://linux-hardware.org/?probe=85ffd2561e) | Jun 08, 2022 |
| Dell          | XPS 13 9305                 | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude 7420               | [5be44c8aae](https://linux-hardware.org/?probe=5be44c8aae) | Jun 01, 2022 |
| Apple         | MacBookPro11,5              | [5cd59453b1](https://linux-hardware.org/?probe=5cd59453b1) | Apr 15, 2022 |
| Framework     | Laptop                      | [4997cab79b](https://linux-hardware.org/?probe=4997cab79b) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Lenovo        | ThinkPad T490 20N2000LUK    | [a394ce9693](https://linux-hardware.org/?probe=a394ce9693) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [502a8c9d32](https://linux-hardware.org/?probe=502a8c9d32) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5570a879d3](https://linux-hardware.org/?probe=5570a879d3) | Mar 13, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d6cae900dc](https://linux-hardware.org/?probe=d6cae900dc) | Mar 13, 2022 |
| GPD           | MicroPC                     | [a572eb2b39](https://linux-hardware.org/?probe=a572eb2b39) | Mar 11, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [f031fb1a5a](https://linux-hardware.org/?probe=f031fb1a5a) | Mar 11, 2022 |
| Lenovo        | ThinkPad T540p 20BE005YM... | [6d0cd0f4b9](https://linux-hardware.org/?probe=6d0cd0f4b9) | Mar 10, 2022 |
| Lenovo        | ThinkPad X260 20F5S6MF02    | [5e026c07c0](https://linux-hardware.org/?probe=5e026c07c0) | Mar 10, 2022 |
| MSI           | Bravo 15 B5DD               | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| OBSIDIAN-P... | N13_N140ZU                  | [9f2fdbfce5](https://linux-hardware.org/?probe=9f2fdbfce5) | Feb 25, 2022 |
| Dell          | Latitude 7420               | [64178dcbb7](https://linux-hardware.org/?probe=64178dcbb7) | Feb 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [cf3fa03922](https://linux-hardware.org/?probe=cf3fa03922) | Jan 08, 2022 |
| Lenovo        | ThinkPad X390 20Q0CTO1WW    | [d62840031f](https://linux-hardware.org/?probe=d62840031f) | Jan 08, 2022 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | [5fb4f1b6a6](https://linux-hardware.org/?probe=5fb4f1b6a6) | Nov 29, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [dbe8d36249](https://linux-hardware.org/?probe=dbe8d36249) | Nov 04, 2021 |
| Lenovo        | ThinkPad X250 20CLS18S0T    | [0151eadf78](https://linux-hardware.org/?probe=0151eadf78) | Oct 06, 2021 |
| HP            | ProBook 445 G7              | [36c94af49d](https://linux-hardware.org/?probe=36c94af49d) | Aug 09, 2021 |
| HP            | ProBook 445 G7              | [87a418ce6c](https://linux-hardware.org/?probe=87a418ce6c) | Aug 09, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3df83086ef](https://linux-hardware.org/?probe=3df83086ef) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [052ccd7a40](https://linux-hardware.org/?probe=052ccd7a40) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [48fd4d3b89](https://linux-hardware.org/?probe=48fd4d3b89) | Aug 06, 2021 |
| Dell          | Latitude 7420               | [0624aeffd1](https://linux-hardware.org/?probe=0624aeffd1) | Jul 19, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [d14e0ef395](https://linux-hardware.org/?probe=d14e0ef395) | Jun 18, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fc12f446bb](https://linux-hardware.org/?probe=fc12f446bb) | May 23, 2021 |
| HP            | ZBook Studio G5             | [d323a9cfbf](https://linux-hardware.org/?probe=d323a9cfbf) | Apr 23, 2021 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [38ab65a49b](https://linux-hardware.org/?probe=38ab65a49b) | Mar 18, 2021 |
| Lenovo        | ThinkPad T580 20L90024PB    | [8dc60fafaa](https://linux-hardware.org/?probe=8dc60fafaa) | Oct 13, 2020 |
| Dell          | XPS 15 9550                 | [5656cda6a4](https://linux-hardware.org/?probe=5656cda6a4) | Sep 01, 2020 |
| Dell          | XPS 15 9550                 | [550264c421](https://linux-hardware.org/?probe=550264c421) | Aug 22, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [71029187b1](https://linux-hardware.org/?probe=71029187b1) | Jul 03, 2020 |
| Acer          | Aspire E5-576G              | [c126c8b2fd](https://linux-hardware.org/?probe=c126c8b2fd) | Apr 15, 2020 |
| Gigabyte      | Sabre 15                    | [4f92cff461](https://linux-hardware.org/?probe=4f92cff461) | Jul 14, 2019 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| NixOS 23.05                      | 61        | 37.2%   |
| NixOS 23.11                      | 30        | 18.29%  |
| NixOS 22.11                      | 27        | 16.46%  |
| NixOS 22.05                      | 18        | 10.98%  |
| NixOS 21.11                      | 9         | 5.49%   |
| NixOS 24.05                      | 5         | 3.05%   |
| NixOS                            | 2         | 1.22%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.61%   |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.61%   |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.61%   |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.61%   |
| NixOS 21.05.2132.733682c3292     | 1         | 0.61%   |
| NixOS 21.05.20210423.c21475e     | 1         | 0.61%   |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.61%   |
| NixOS 20.09pre-git               | 1         | 0.61%   |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.61%   |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.61%   |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.61%   |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 146       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Notebooks | Percent |
|----------------|-----------|---------|
| 6.1.55         | 5         | 2.87%   |
| 6.3.8          | 4         | 2.3%    |
| 6.1.53         | 4         | 2.3%    |
| 6.1.51         | 4         | 2.3%    |
| 6.6.0          | 3         | 1.72%   |
| 6.5.5          | 3         | 1.72%   |
| 6.3.3          | 3         | 1.72%   |
| 6.1.61         | 3         | 1.72%   |
| 6.1.60         | 3         | 1.72%   |
| 6.1.47         | 3         | 1.72%   |
| 6.1.38         | 3         | 1.72%   |
| 6.1.31         | 3         | 1.72%   |
| 5.15.74        | 3         | 1.72%   |
| 5.15.43        | 3         | 1.72%   |
| 6.5.7-xanmod1  | 2         | 1.15%   |
| 6.5.6          | 2         | 1.15%   |
| 6.5.2          | 2         | 1.15%   |
| 6.5.11-xanmod1 | 2         | 1.15%   |
| 6.4.0          | 2         | 1.15%   |
| 6.3.1          | 2         | 1.15%   |
| 6.1.67         | 2         | 1.15%   |
| 6.1.64         | 2         | 1.15%   |
| 6.1.63         | 2         | 1.15%   |
| 6.1.42         | 2         | 1.15%   |
| 6.1.41         | 2         | 1.15%   |
| 6.1.35         | 2         | 1.15%   |
| 6.1.34         | 2         | 1.15%   |
| 6.1.0          | 2         | 1.15%   |
| 6.0.10         | 2         | 1.15%   |
| 5.16.15        | 2         | 1.15%   |
| 5.15.72        | 2         | 1.15%   |
| 5.15.68        | 2         | 1.15%   |
| 5.15.64        | 2         | 1.15%   |
| 5.15.26        | 2         | 1.15%   |
| 5.13.7         | 2         | 1.15%   |
| 6.6.4-zen1     | 1         | 0.57%   |
| 6.6.4          | 1         | 0.57%   |
| 6.6.3          | 1         | 0.57%   |
| 6.6.2          | 1         | 0.57%   |
| 6.6.1          | 1         | 0.57%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.55  | 5         | 2.87%   |
| 6.3.8   | 4         | 2.3%    |
| 6.1.53  | 4         | 2.3%    |
| 6.1.51  | 4         | 2.3%    |
| 6.6.0   | 3         | 1.72%   |
| 6.5.5   | 3         | 1.72%   |
| 6.3.3   | 3         | 1.72%   |
| 6.1.61  | 3         | 1.72%   |
| 6.1.60  | 3         | 1.72%   |
| 6.1.47  | 3         | 1.72%   |
| 6.1.38  | 3         | 1.72%   |
| 6.1.31  | 3         | 1.72%   |
| 6.0.10  | 3         | 1.72%   |
| 5.15.74 | 3         | 1.72%   |
| 5.15.43 | 3         | 1.72%   |
| 6.6.4   | 2         | 1.15%   |
| 6.5.7   | 2         | 1.15%   |
| 6.5.6   | 2         | 1.15%   |
| 6.5.2   | 2         | 1.15%   |
| 6.5.11  | 2         | 1.15%   |
| 6.4.0   | 2         | 1.15%   |
| 6.3.1   | 2         | 1.15%   |
| 6.2.9   | 2         | 1.15%   |
| 6.1.67  | 2         | 1.15%   |
| 6.1.64  | 2         | 1.15%   |
| 6.1.63  | 2         | 1.15%   |
| 6.1.42  | 2         | 1.15%   |
| 6.1.41  | 2         | 1.15%   |
| 6.1.35  | 2         | 1.15%   |
| 6.1.34  | 2         | 1.15%   |
| 6.1.0   | 2         | 1.15%   |
| 5.16.15 | 2         | 1.15%   |
| 5.15.72 | 2         | 1.15%   |
| 5.15.68 | 2         | 1.15%   |
| 5.15.64 | 2         | 1.15%   |
| 5.15.26 | 2         | 1.15%   |
| 5.13.7  | 2         | 1.15%   |
| 6.6.3   | 1         | 0.57%   |
| 6.6.2   | 1         | 0.57%   |
| 6.6.1   | 1         | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 55        | 33.54%  |
| 5.15    | 31        | 18.9%   |
| 6.3     | 11        | 6.71%   |
| 6.5     | 10        | 6.1%    |
| 6.6     | 8         | 4.88%   |
| 6.4     | 7         | 4.27%   |
| 6.2     | 6         | 3.66%   |
| 6.0     | 6         | 3.66%   |
| 5.16    | 6         | 3.66%   |
| 5.8     | 3         | 1.83%   |
| 5.19    | 3         | 1.83%   |
| 5.13    | 3         | 1.83%   |
| 5.10    | 3         | 1.83%   |
| 5.7     | 2         | 1.22%   |
| 5.4     | 2         | 1.22%   |
| 5.18    | 2         | 1.22%   |
| 5.17    | 2         | 1.22%   |
| 4.19    | 2         | 1.22%   |
| 5.12    | 1         | 0.61%   |
| Unknown | 1         | 0.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 145       | 99.32%  |
| i686   | 1         | 0.68%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 48        | 31.17%  |
| GNOME        | 30        | 19.48%  |
| KDE5         | 22        | 14.29%  |
| sway         | 16        | 10.39%  |
| Hyprland     | 14        | 9.09%   |
| none+i3      | 6         | 3.9%    |
| KDE          | 5         | 3.25%   |
| XFCE         | 3         | 1.95%   |
| Pantheon     | 2         | 1.3%    |
| none+xmonad  | 2         | 1.3%    |
| none+awesome | 2         | 1.3%    |
| Budgie       | 2         | 1.3%    |
| X-Cinnamon   | 1         | 0.65%   |
| none+bspwm   | 1         | 0.65%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 59        | 38.06%  |
| Unknown | 58        | 37.42%  |
| X11     | 32        | 20.65%  |
| Tty     | 6         | 3.87%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 65        | 43.62%  |
| GDM     | 36        | 24.16%  |
| SDDM    | 29        | 19.46%  |
| LightDM | 19        | 12.75%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 88        | 59.06%  |
| Unknown | 33        | 22.15%  |
| en_GB   | 8         | 5.37%   |
| en_DK   | 2         | 1.34%   |
| en_CA   | 2         | 1.34%   |
| en_AU   | 2         | 1.34%   |
| C       | 2         | 1.34%   |
| ru_RU   | 1         | 0.67%   |
| ro_RO   | 1         | 0.67%   |
| pt_PT   | 1         | 0.67%   |
| pt_BR   | 1         | 0.67%   |
| pl_PL   | 1         | 0.67%   |
| lv_LV   | 1         | 0.67%   |
| lt_LT   | 1         | 0.67%   |
| it_IT   | 1         | 0.67%   |
| fr_FR   | 1         | 0.67%   |
| es_MX   | 1         | 0.67%   |
| en_IN   | 1         | 0.67%   |
| de_DE   | 1         | 0.67%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 133       | 91.1%   |
| BIOS | 13        | 8.9%    |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 82        | 54.3%   |
| Btrfs   | 25        | 16.56%  |
| Tmpfs   | 17        | 11.26%  |
| Zfs     | 13        | 8.61%   |
| Xfs     | 9         | 5.96%   |
| Unknown | 3         | 1.99%   |
| F2fs    | 2         | 1.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 138       | 93.24%  |
| MBR     | 5         | 3.38%   |
| Unknown | 5         | 3.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 123       | 82.55%  |
| Yes       | 26        | 17.45%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 112       | 76.71%  |
| Yes       | 34        | 23.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 54        | 36.99%  |
| Dell                   | 23        | 15.75%  |
| ASUSTek Computer       | 18        | 12.33%  |
| Hewlett-Packard        | 14        | 9.59%   |
| Apple                  | 6         | 4.11%   |
| MSI                    | 5         | 3.42%   |
| Framework              | 4         | 2.74%   |
| GPD                    | 3         | 2.05%   |
| Acer                   | 3         | 2.05%   |
| MECHREVO               | 2         | 1.37%   |
| Toshiba                | 1         | 0.68%   |
| Timi                   | 1         | 0.68%   |
| System76               | 1         | 0.68%   |
| Samsung Electronics    | 1         | 0.68%   |
| OBSIDIAN-PC            | 1         | 0.68%   |
| Microtech              | 1         | 0.68%   |
| Medion                 | 1         | 0.68%   |
| MACHENIKE              | 1         | 0.68%   |
| Intel                  | 1         | 0.68%   |
| HUAWEI                 | 1         | 0.68%   |
| Gigabyte Technology    | 1         | 0.68%   |
| Blackview              | 1         | 0.68%   |
| Avell High Performance | 1         | 0.68%   |
| Alienware              | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| HP EliteBook 8470p                          | 2         | 1.37%   |
| Framework Laptop (12th Gen Intel Core)      | 2         | 1.37%   |
| Framework Laptop                            | 2         | 1.37%   |
| Dell Latitude 7420                          | 2         | 1.37%   |
| ASUS Vivobook Go E1404FA_E1404FA            | 2         | 1.37%   |
| Apple MacBookPro11,5                        | 2         | 1.37%   |
| Apple MacBookPro11,3                        | 2         | 1.37%   |
| Toshiba Satellite L50-B                     | 1         | 0.68%   |
| Timi Redmi Book Pro 15 2022                 | 1         | 0.68%   |
| System76 Pangolin                           | 1         | 0.68%   |
| Samsung 530U3BI/530U4BI/530U4BH             | 1         | 0.68%   |
| OBSIDIAN-PC N13_N140ZU                      | 1         | 0.68%   |
| MSI Prestige 16Studio A13VE                 | 1         | 0.68%   |
| MSI Prestige 14 A10SC                       | 1         | 0.68%   |
| MSI GE70 2PE                                | 1         | 0.68%   |
| MSI Bravo 15 B5DD                           | 1         | 0.68%   |
| MSI Alpha 15 B5EEK                          | 1         | 0.68%   |
| Microtech CoreBook Lite                     | 1         | 0.68%   |
| Medion M14L-256                             | 1         | 0.68%   |
| MECHREVO WUJIE 14                           | 1         | 0.68%   |
| MECHREVO Code01 Ver2.0                      | 1         | 0.68%   |
| MACHENIKE F117-7P                           | 1         | 0.68%   |
| Lenovo Yoga Slim 7 Carbon 14ACN6 82L0       | 1         | 0.68%   |
| Lenovo Yoga Slim 7 13ACN5 82CY              | 1         | 0.68%   |
| Lenovo Yoga 14sARE 2020 82A8                | 1         | 0.68%   |
| Lenovo ThinkPad X390 20Q0CTO1WW             | 1         | 0.68%   |
| Lenovo ThinkPad X260 20F5S6MF02             | 1         | 0.68%   |
| Lenovo ThinkPad X260 20F5S4BY00             | 1         | 0.68%   |
| Lenovo ThinkPad X250 20CLS18S0T             | 1         | 0.68%   |
| Lenovo ThinkPad X230 2333AZ2                | 1         | 0.68%   |
| Lenovo ThinkPad X230 23243E9                | 1         | 0.68%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW       | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB007AUK | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon 4th 20FBCT01WW    | 1         | 0.68%   |
| Lenovo ThinkPad T580 20L90024PB             | 1         | 0.68%   |
| Lenovo ThinkPad T540p 20BE005YMH            | 1         | 0.68%   |
| Lenovo ThinkPad T490 20N2000LUK             | 1         | 0.68%   |
| Lenovo ThinkPad T480s 20L7CTO1WW            | 1         | 0.68%   |
| Lenovo ThinkPad T480 20L6S4RV00             | 1         | 0.68%   |
| Lenovo ThinkPad T480 20L5CTO1WW             | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 34        | 23.29%  |
| HP EliteBook       | 8         | 5.48%   |
| Dell XPS           | 8         | 5.48%   |
| Lenovo Legion      | 7         | 4.79%   |
| Dell Latitude      | 7         | 4.79%   |
| ASUS ROG           | 7         | 4.79%   |
| Lenovo IdeaPad     | 5         | 3.42%   |
| ASUS Zenbook       | 5         | 3.42%   |
| Apple MacBookPro11 | 5         | 3.42%   |
| Framework Laptop   | 4         | 2.74%   |
| Lenovo Yoga        | 3         | 2.05%   |
| Lenovo ThinkBook   | 3         | 2.05%   |
| HP ZBook           | 3         | 2.05%   |
| Dell Precision     | 3         | 2.05%   |
| Dell Inspiron      | 3         | 2.05%   |
| ASUS Vivobook      | 3         | 2.05%   |
| Acer Aspire        | 3         | 2.05%   |
| MSI Prestige       | 2         | 1.37%   |
| HP ProBook         | 2         | 1.37%   |
| Toshiba Satellite  | 1         | 0.68%   |
| Timi Redmi         | 1         | 0.68%   |
| System76 Pangolin  | 1         | 0.68%   |
| Samsung 530U3BI    | 1         | 0.68%   |
| OBSIDIAN-PC N13    | 1         | 0.68%   |
| MSI GE70           | 1         | 0.68%   |
| MSI Bravo          | 1         | 0.68%   |
| MSI Alpha          | 1         | 0.68%   |
| Microtech CoreBook | 1         | 0.68%   |
| Medion M14L-256    | 1         | 0.68%   |
| MECHREVO WUJIE     | 1         | 0.68%   |
| MECHREVO Code01    | 1         | 0.68%   |
| MACHENIKE F117-7P  | 1         | 0.68%   |
| Lenovo Slim        | 1         | 0.68%   |
| Lenovo G50-70      | 1         | 0.68%   |
| Intel SharkBay     | 1         | 0.68%   |
| HUAWEI NBLK-WAX9X  | 1         | 0.68%   |
| HP ENVY            | 1         | 0.68%   |
| GPD WIN2           | 1         | 0.68%   |
| GPD MicroPC        | 1         | 0.68%   |
| GPD G1621-02       | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 27        | 18.49%  |
| 2022 | 18        | 12.33%  |
| 2020 | 15        | 10.27%  |
| 2023 | 13        | 8.9%    |
| 2019 | 13        | 8.9%    |
| 2018 | 12        | 8.22%   |
| 2016 | 10        | 6.85%   |
| 2017 | 8         | 5.48%   |
| 2014 | 7         | 4.79%   |
| 2013 | 7         | 4.79%   |
| 2015 | 6         | 4.11%   |
| 2012 | 6         | 4.11%   |
| 2011 | 3         | 2.05%   |
| 2009 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 146       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 142       | 96.6%   |
| Enabled  | 5         | 3.4%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 145       | 99.32%  |
| Yes  | 1         | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 36        | 24.49%  |
| 16.01-24.0  | 35        | 23.81%  |
| 32.01-64.0  | 32        | 21.77%  |
| 4.01-8.0    | 25        | 17.01%  |
| 64.01-256.0 | 8         | 5.44%   |
| 24.01-32.0  | 6         | 4.08%   |
| 3.01-4.0    | 4         | 2.72%   |
| 0.51-1.0    | 1         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 43        | 26.22%  |
| 3.01-4.0   | 32        | 19.51%  |
| 2.01-3.0   | 31        | 18.9%   |
| 8.01-16.0  | 23        | 14.02%  |
| 1.01-2.0   | 15        | 9.15%   |
| 0.51-1.0   | 6         | 3.66%   |
| 24.01-32.0 | 5         | 3.05%   |
| 16.01-24.0 | 5         | 3.05%   |
| 32.01-64.0 | 2         | 1.22%   |
| 0.01-0.5   | 2         | 1.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 77.03%  |
| 2      | 31        | 20.95%  |
| 3      | 3         | 2.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 89.73%  |
| Yes       | 15        | 10.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 67.79%  |
| No        | 48        | 32.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 98.63%  |
| No        | 2         | 1.37%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 93.92%  |
| No        | 9         | 6.08%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 32        | 21.92%  |
| UK          | 9         | 6.16%   |
| Italy       | 9         | 6.16%   |
| Russia      | 8         | 5.48%   |
| Germany     | 7         | 4.79%   |
| France      | 7         | 4.79%   |
| Poland      | 5         | 3.42%   |
| Canada      | 5         | 3.42%   |
| Ukraine     | 4         | 2.74%   |
| Netherlands | 4         | 2.74%   |
| Czechia     | 4         | 2.74%   |
| Switzerland | 3         | 2.05%   |
| Sweden      | 3         | 2.05%   |
| Portugal    | 3         | 2.05%   |
| Norway      | 3         | 2.05%   |
| Japan       | 3         | 2.05%   |
| Austria     | 3         | 2.05%   |
| Spain       | 2         | 1.37%   |
| Qatar       | 2         | 1.37%   |
| Iraq        | 2         | 1.37%   |
| India       | 2         | 1.37%   |
| China       | 2         | 1.37%   |
| Brazil      | 2         | 1.37%   |
| Belgium     | 2         | 1.37%   |
| Australia   | 2         | 1.37%   |
| Vietnam     | 1         | 0.68%   |
| Uzbekistan  | 1         | 0.68%   |
| Uruguay     | 1         | 0.68%   |
| Slovenia    | 1         | 0.68%   |
| Singapore   | 1         | 0.68%   |
| Serbia      | 1         | 0.68%   |
| Romania     | 1         | 0.68%   |
| Peru        | 1         | 0.68%   |
| Mexico      | 1         | 0.68%   |
| Lithuania   | 1         | 0.68%   |
| Latvia      | 1         | 0.68%   |
| Kuwait      | 1         | 0.68%   |
| Iran        | 1         | 0.68%   |
| Hungary     | 1         | 0.68%   |
| Hong Kong   | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Vienna             | 3         | 1.94%   |
| London             | 3         | 1.94%   |
| Craigsville        | 3         | 1.94%   |
| Saratov            | 2         | 1.29%   |
| Prague             | 2         | 1.29%   |
| Pradamano          | 2         | 1.29%   |
| Phoenix            | 2         | 1.29%   |
| Perth              | 2         | 1.29%   |
| Ottawa             | 2         | 1.29%   |
| Oslo               | 2         | 1.29%   |
| Marki              | 2         | 1.29%   |
| Los Angeles        | 2         | 1.29%   |
| Kharkiv            | 2         | 1.29%   |
| Halifax            | 2         | 1.29%   |
| Doha               | 2         | 1.29%   |
| Catania            | 2         | 1.29%   |
| Baghdad            | 2         | 1.29%   |
| Amsterdam          | 2         | 1.29%   |
| Zurich             | 1         | 0.65%   |
| Yangzhou           | 1         | 0.65%   |
| Woodford           | 1         | 0.65%   |
| Woldegk            | 1         | 0.65%   |
| Warsaw             | 1         | 0.65%   |
| Vilnius            | 1         | 0.65%   |
| Villeurbanne       | 1         | 0.65%   |
| Victorville        | 1         | 0.65%   |
| Verneuil-sur-Seine | 1         | 0.65%   |
| Valpacos           | 1         | 0.65%   |
| Trento             | 1         | 0.65%   |
| Tremestieri Etneo  | 1         | 0.65%   |
| Tover              | 1         | 0.65%   |
| Tottenham          | 1         | 0.65%   |
| Tolyatti           | 1         | 0.65%   |
| Tehran             | 1         | 0.65%   |
| Tashkent           | 1         | 0.65%   |
| Szigetszentmiklos  | 1         | 0.65%   |
| Sun Prairie        | 1         | 0.65%   |
| Stockholm          | 1         | 0.65%   |
| Staten Island      | 1         | 0.65%   |
| St Petersburg      | 1         | 0.65%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 48        | 65     | 26.97%  |
| SanDisk                        | 17        | 19     | 9.55%   |
| SK hynix                       | 14        | 17     | 7.87%   |
| Micron Technology              | 10        | 11     | 5.62%   |
| Toshiba                        | 9         | 9      | 5.06%   |
| WDC                            | 8         | 8      | 4.49%   |
| Kingston                       | 7         | 11     | 3.93%   |
| Intel                          | 7         | 8      | 3.93%   |
| Unknown                        | 6         | 6      | 3.37%   |
| Seagate                        | 6         | 7      | 3.37%   |
| Crucial                        | 5         | 6      | 2.81%   |
| Apple                          | 5         | 7      | 2.81%   |
| KIOXIA                         | 4         | 5      | 2.25%   |
| Kingston Technology Company    | 4         | 4      | 2.25%   |
| A-DATA Technology              | 3         | 3      | 1.69%   |
| Yangtze Memory Technologies    | 2         | 2      | 1.12%   |
| Transcend                      | 2         | 2      | 1.12%   |
| Phison Electronics             | 2         | 2      | 1.12%   |
| SPCC                           | 1         | 1      | 0.56%   |
| Solid State Storage Technology | 1         | 1      | 0.56%   |
| S3+                            | 1         | 1      | 0.56%   |
| Realtek                        | 1         | 1      | 0.56%   |
| PNY                            | 1         | 2      | 0.56%   |
| Micron/Crucial Technology      | 1         | 1      | 0.56%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.56%   |
| LITEONIT                       | 1         | 1      | 0.56%   |
| Lite-On Technology             | 1         | 1      | 0.56%   |
| INNOVATION IT                  | 1         | 1      | 0.56%   |
| Hitachi                        | 1         | 2      | 0.56%   |
| HGST                           | 1         | 1      | 0.56%   |
| Dogfish                        | 1         | 1      | 0.56%   |
| Corsair                        | 1         | 1      | 0.56%   |
| China                          | 1         | 1      | 0.56%   |
| Biwin Storage Technology       | 1         | 1      | 0.56%   |
| BIWIN                          | 1         | 1      | 0.56%   |
| ADATA Technology               | 1         | 2      | 0.56%   |
| Unknown                        | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB    | 10        | 5.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB     | 8         | 4.32%   |
| Intel SSDPEKNU512GZ 512GB                              | 4         | 2.16%   |
| Samsung SSD 850 EVO 500GB                              | 3         | 1.62%   |
| Unknown MMC Card  32GB                                 | 2         | 1.08%   |
| SK hynix SKHynix_HFS001TDE9X084N 1TB                   | 2         | 1.08%   |
| SK hynix PC801 NVMe 512GB                              | 2         | 1.08%   |
| SK hynix HFM001TD3JX013N 1TB                           | 2         | 1.08%   |
| Sandisk WD_BLACK SN770 1TB                             | 2         | 1.08%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB       | 2         | 1.08%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 1024GB | 2         | 1.08%   |
| Samsung SSD 870 EVO 500GB                              | 2         | 1.08%   |
| Samsung PM9A1 NVMe 1024GB                              | 2         | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB    | 2         | 1.08%   |
| Micron MTFDKBA512TFH 512GB                             | 2         | 1.08%   |
| Kingston OM8PCP3512F-AI1 512GB                         | 2         | 1.08%   |
| Apple SSD SM0512G 500GB                                | 2         | 1.08%   |
| Yangtze Memory ZHITAI TiPlus7100 2TB                   | 1         | 0.54%   |
| Yangtze Memory YMTC PC300-1TB-B                        | 1         | 0.54%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                       | 1         | 0.54%   |
| WDC WDS200T1X0E-00AFY0 2TB                             | 1         | 0.54%   |
| WDC WD7500BPKX-75HPJT0 752GB                           | 1         | 0.54%   |
| WDC WD10 JPLX-00MBPT0 1TB                              | 1         | 0.54%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                     | 1         | 0.54%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                   | 1         | 0.54%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                     | 1         | 0.54%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                   | 1         | 0.54%   |
| Unknown MMC Card  64GB                                 | 1         | 0.54%   |
| Unknown MMC Card  250GB                                | 1         | 0.54%   |
| Unknown MMC Card  16GB                                 | 1         | 0.54%   |
| Unknown MMC Card  128GB                                | 1         | 0.54%   |
| Transcend TS256GMTS800 256GB SSD                       | 1         | 0.54%   |
| Transcend TS256GMTS430S 256GB SSD                      | 1         | 0.54%   |
| Toshiba XG6 NVMe SSD Controller 512GB                  | 1         | 0.54%   |
| Toshiba XG4 NVMe SSD Controller 512GB                  | 1         | 0.54%   |
| Toshiba THNSFJ256GCSU 256GB SSD                        | 1         | 0.54%   |
| Toshiba MQ01ACF050 500GB                               | 1         | 0.54%   |
| Toshiba MQ01ABD100 1TB                                 | 1         | 0.54%   |
| Toshiba MK2565GSXV 250GB                               | 1         | 0.54%   |
| Toshiba KXG6AZNV512G 512GB                             | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 7      | 42.86%  |
| Toshiba | 3         | 3      | 21.43%  |
| WDC     | 2         | 2      | 14.29%  |
| Hitachi | 1         | 2      | 7.14%   |
| HGST    | 1         | 1      | 7.14%   |
| Apple   | 1         | 1      | 7.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 20     | 32%     |
| SanDisk             | 5         | 5      | 10%     |
| Kingston            | 4         | 7      | 8%      |
| Crucial             | 4         | 5      | 8%      |
| Apple               | 4         | 6      | 8%      |
| Transcend           | 2         | 2      | 4%      |
| Micron Technology   | 2         | 2      | 4%      |
| WDC                 | 1         | 1      | 2%      |
| Toshiba             | 1         | 1      | 2%      |
| SPCC                | 1         | 1      | 2%      |
| SK hynix            | 1         | 1      | 2%      |
| S3+                 | 1         | 1      | 2%      |
| PNY                 | 1         | 2      | 2%      |
| LITEONIT            | 1         | 1      | 2%      |
| INNOVATION IT       | 1         | 1      | 2%      |
| Dogfish             | 1         | 1      | 2%      |
| Corsair             | 1         | 1      | 2%      |
| China               | 1         | 1      | 2%      |
| BIWIN               | 1         | 1      | 2%      |
| Unknown             | 1         | 1      | 2%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 101       | 131    | 60.12%  |
| SSD  | 47        | 61     | 27.98%  |
| HDD  | 14        | 16     | 8.33%   |
| MMC  | 6         | 6      | 3.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 101       | 130    | 62.35%  |
| SATA | 50        | 73     | 30.86%  |
| MMC  | 6         | 6      | 3.7%    |
| SAS  | 5         | 5      | 3.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 39        | 52     | 63.93%  |
| 0.51-1.0   | 19        | 22     | 31.15%  |
| 1.01-2.0   | 2         | 2      | 3.28%   |
| 4.01-10.0  | 1         | 1      | 1.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 43        | 28.29%  |
| Unknown        | 35        | 23.03%  |
| 251-500        | 21        | 13.82%  |
| 101-250        | 17        | 11.18%  |
| 501-1000       | 17        | 11.18%  |
| 1001-2000      | 8         | 5.26%   |
| More than 3000 | 7         | 4.61%   |
| 2001-3000      | 3         | 1.97%   |
| 51-100         | 1         | 0.66%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 51        | 33.12%  |
| Unknown        | 35        | 22.73%  |
| 101-250        | 22        | 14.29%  |
| 21-50          | 16        | 10.39%  |
| 51-100         | 9         | 5.84%   |
| 251-500        | 8         | 5.19%   |
| 501-1000       | 8         | 5.19%   |
| 2001-3000      | 2         | 1.3%    |
| 1001-2000      | 2         | 1.3%    |
| More than 3000 | 1         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10 JPLX-00MBPT0 1TB                      | 1         | 1      | 14.29%  |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 14.29%  |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 14.29%  |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 14.29%  |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 14.29%  |
| Corsair Force GS 240GB SSD                     | 1         | 1      | 14.29%  |
| A-DATA Technology IM2P33F3A NVMe 256GB         | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 2      | 28.57%  |
| WDC               | 1         | 1      | 14.29%  |
| SK hynix          | 1         | 1      | 14.29%  |
| Micron Technology | 1         | 1      | 14.29%  |
| Corsair           | 1         | 1      | 14.29%  |
| A-DATA Technology | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 42.86%  |
| NVMe | 2         | 2      | 28.57%  |
| SSD  | 2         | 2      | 28.57%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZNLN256HCHP-000L7 256GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 140       | 189    | 86.42%  |
| Detected | 14        | 17     | 8.64%   |
| Malfunc  | 7         | 7      | 4.32%   |
| Failed   | 1         | 1      | 0.62%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 74        | 39.57%  |
| Samsung Electronics            | 37        | 19.79%  |
| SanDisk                        | 17        | 9.09%   |
| SK hynix                       | 13        | 6.95%   |
| Micron Technology              | 8         | 4.28%   |
| Kingston Technology Company    | 7         | 3.74%   |
| AMD                            | 7         | 3.74%   |
| Toshiba America Info Systems   | 6         | 3.21%   |
| ADATA Technology               | 4         | 2.14%   |
| KIOXIA                         | 3         | 1.6%    |
| Yangtze Memory Technologies    | 2         | 1.07%   |
| Phison Electronics             | 2         | 1.07%   |
| Micron/Crucial Technology      | 2         | 1.07%   |
| Solid State Storage Technology | 1         | 0.53%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.53%   |
| Marvell Technology Group       | 1         | 0.53%   |
| Lite-On Technology             | 1         | 0.53%   |
| Biwin Storage Technology       | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 17        | 8.95%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 11        | 5.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 4.74%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 9         | 4.74%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 3.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 3.68%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 3.68%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 3.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 3.16%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5         | 2.63%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 2.63%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 4         | 2.11%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 4         | 2.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 2.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 2.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 2.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 1.58%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 1.58%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 3         | 1.58%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 1.58%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 1.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.58%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.05%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 2         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.05%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 1.05%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                            | 2         | 1.05%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 2         | 1.05%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 2         | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2         | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 1.05%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 1.05%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 1.05%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 1.05%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.05%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 1         | 0.53%   |
| Yangtze Memory PC300 NVMe SSD (DRAM-less)                                      | 1         | 0.53%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.53%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 101       | 56.11%  |
| SATA | 64        | 35.56%  |
| RAID | 15        | 8.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 105       | 71.92%  |
| AMD    | 41        | 28.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz              | 4         | 2.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 4         | 2.74%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 4         | 2.74%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics     | 4         | 2.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 4         | 2.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 3         | 2.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 3         | 2.05%   |
| Intel Core i5-8350U CPU @ 1.70GHz              | 3         | 2.05%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 3         | 2.05%   |
| Intel 12th Gen Core i7-1260P                   | 3         | 2.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 3         | 2.05%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 3         | 2.05%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 3         | 2.05%   |
| AMD Ryzen 7 6800H with Radeon Graphics         | 3         | 2.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 2         | 1.37%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 2         | 1.37%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz             | 2         | 1.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 2         | 1.37%   |
| Intel Core i7-6600U CPU @ 2.60GHz              | 2         | 1.37%   |
| Intel Core i7-5600U CPU @ 2.60GHz              | 2         | 1.37%   |
| Intel Core i7-5500U CPU @ 2.40GHz              | 2         | 1.37%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz             | 2         | 1.37%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 2         | 1.37%   |
| Intel Core i5-9300H CPU @ 2.40GHz              | 2         | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 2         | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 2         | 1.37%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 2         | 1.37%   |
| Intel Celeron N4100 CPU @ 1.10GHz              | 2         | 1.37%   |
| Intel 12th Gen Core i5-1240P                   | 2         | 1.37%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 2         | 1.37%   |
| AMD Ryzen 9 5900HS with Radeon Graphics        | 2         | 1.37%   |
| AMD Ryzen 7 PRO 7840HS w/ Radeon 780M Graphics | 2         | 1.37%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics     | 2         | 1.37%   |
| AMD Ryzen 7 5800U with Radeon Graphics         | 2         | 1.37%   |
| AMD Ryzen 7 5800HS with Radeon Graphics        | 2         | 1.37%   |
| AMD Ryzen 5 7520U with Radeon Graphics         | 2         | 1.37%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 2         | 1.37%   |
| Intel Xeon E-2276M CPU @ 2.80GHz               | 1         | 0.68%   |
| Intel Xeon E-2176M CPU @ 2.70GHz               | 1         | 0.68%   |
| Intel Pentium Gold 7505 @ 2.00GHz              | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 42        | 28.77%  |
| Other              | 28        | 19.18%  |
| Intel Core i5      | 22        | 15.07%  |
| AMD Ryzen 7        | 18        | 12.33%  |
| AMD Ryzen 7 PRO    | 10        | 6.85%   |
| AMD Ryzen 9        | 7         | 4.79%   |
| AMD Ryzen 5        | 6         | 4.11%   |
| Intel Celeron      | 4         | 2.74%   |
| Intel Core i3      | 3         | 2.05%   |
| Intel Xeon         | 2         | 1.37%   |
| Intel Pentium Gold | 1         | 0.68%   |
| Intel Core m3      | 1         | 0.68%   |
| Intel Core i9      | 1         | 0.68%   |
| Intel Atom         | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 49        | 33.56%  |
| 8      | 39        | 26.71%  |
| 2      | 33        | 22.6%   |
| 6      | 9         | 6.16%   |
| 12     | 7         | 4.79%   |
| 14     | 4         | 2.74%   |
| 10     | 2         | 1.37%   |
| 24     | 1         | 0.68%   |
| 16     | 1         | 0.68%   |
| 1      | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 146       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 140       | 95.89%  |
| 1      | 6         | 4.11%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 145       | 98.64%  |
| 32-bit         | 1         | 0.68%   |
| Unknown        | 1         | 0.68%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 39        | 26%     |
| 0x0a50000c | 15        | 10%     |
| 0x806ea    | 7         | 4.67%   |
| 0x806c1    | 6         | 4%      |
| 0x08600106 | 6         | 4%      |
| 0x306c3    | 5         | 3.33%   |
| 0x906ea    | 4         | 2.67%   |
| 0x806e9    | 4         | 2.67%   |
| 0x406e3    | 4         | 2.67%   |
| 0x40661    | 4         | 2.67%   |
| 0x40651    | 4         | 2.67%   |
| 0x0a404102 | 4         | 2.67%   |
| 0x906a3    | 3         | 2%      |
| 0x806ec    | 3         | 2%      |
| 0x806eb    | 3         | 2%      |
| 0x306d4    | 3         | 2%      |
| 0x306a9    | 3         | 2%      |
| 0x0a704103 | 3         | 2%      |
| 0x906ed    | 2         | 1.33%   |
| 0x906e9    | 2         | 1.33%   |
| 0x906a4    | 2         | 1.33%   |
| 0x706a8    | 2         | 1.33%   |
| 0x706a1    | 2         | 1.33%   |
| 0x506e3    | 2         | 1.33%   |
| 0x0a404101 | 2         | 1.33%   |
| 0x08a00008 | 2         | 1.33%   |
| 0x08600104 | 2         | 1.33%   |
| 0xb0671    | 1         | 0.67%   |
| 0xa0660    | 1         | 0.67%   |
| 0x806d1    | 1         | 0.67%   |
| 0x706e5    | 1         | 0.67%   |
| 0x106c2    | 1         | 0.67%   |
| 0x0a704104 | 1         | 0.67%   |
| 0x0a601203 | 1         | 0.67%   |
| 0x0a50000d | 1         | 0.67%   |
| 0x0a50000b | 1         | 0.67%   |
| 0x08608103 | 1         | 0.67%   |
| 0x08108109 | 1         | 0.67%   |
| 0x08108102 | 1         | 0.67%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 33        | 22.6%   |
| Zen 3            | 17        | 11.64%  |
| Unknown          | 17        | 11.64%  |
| Haswell          | 14        | 9.59%   |
| Alderlake Hybrid | 13        | 8.9%    |
| TigerLake        | 11        | 7.53%   |
| Skylake          | 11        | 7.53%   |
| Zen 2            | 8         | 5.48%   |
| IvyBridge        | 6         | 4.11%   |
| Goldmont plus    | 4         | 2.74%   |
| Broadwell        | 4         | 2.74%   |
| IceLake          | 3         | 2.05%   |
| Zen+             | 2         | 1.37%   |
| SandyBridge      | 1         | 0.68%   |
| CometLake        | 1         | 0.68%   |
| Bonnell          | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 99        | 50.77%  |
| AMD    | 49        | 25.13%  |
| Nvidia | 47        | 24.1%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 15        | 7.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 10        | 5.03%   |
| Intel UHD Graphics 620                                                                | 9         | 4.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 8         | 4.02%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 8         | 4.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 7         | 3.52%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 7         | 3.52%   |
| AMD Rembrandt [Radeon 680M]                                                           | 6         | 3.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 5         | 2.51%   |
| Intel HD Graphics 620                                                                 | 5         | 2.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 2.51%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 5         | 2.51%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 4         | 2.01%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 4         | 2.01%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 2.01%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 2.01%   |
| Intel HD Graphics 5500                                                                | 4         | 2.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 2.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 2.01%   |
| AMD Phoenix1                                                                          | 4         | 2.01%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.51%   |
| Intel HD Graphics 530                                                                 | 3         | 1.51%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 3         | 1.51%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 1.01%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 1.01%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 2         | 1.01%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 2         | 1.01%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 1.01%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 2         | 1.01%   |
| Intel Raptor Lake-S UHD Graphics                                                      | 2         | 1.01%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 2         | 1.01%   |
| Intel HD Graphics 630                                                                 | 2         | 1.01%   |
| Intel Crystal Well Integrated Graphics Controller                                     | 2         | 1.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 2         | 1.01%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 2         | 1.01%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 2         | 1.01%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 2         | 1.01%   |
| AMD Mendocino                                                                         | 2         | 1.01%   |
| AMD Barcelo                                                                           | 2         | 1.01%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 39.04%  |
| Intel + Nvidia | 33        | 22.6%   |
| 1 x AMD        | 31        | 21.23%  |
| AMD + Nvidia   | 9         | 6.16%   |
| Intel + AMD    | 7         | 4.79%   |
| 1 x Nvidia     | 5         | 3.42%   |
| 2 x Intel      | 2         | 1.37%   |
| 2 x AMD        | 2         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 116       | 78.91%  |
| Proprietary | 29        | 19.73%  |
| Unknown     | 2         | 1.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 91        | 61.07%  |
| 0.01-0.5   | 23        | 15.44%  |
| 1.01-2.0   | 15        | 10.07%  |
| 3.01-4.0   | 9         | 6.04%   |
| 0.51-1.0   | 8         | 5.37%   |
| 7.01-8.0   | 2         | 1.34%   |
| 8.01-16.0  | 1         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 31        | 17.32%  |
| BOE                  | 27        | 15.08%  |
| Chimei Innolux       | 20        | 11.17%  |
| LG Display           | 18        | 10.06%  |
| Samsung Electronics  | 15        | 8.38%   |
| Dell                 | 10        | 5.59%   |
| Sharp                | 8         | 4.47%   |
| PANDA                | 6         | 3.35%   |
| CSO                  | 6         | 3.35%   |
| Apple                | 6         | 3.35%   |
| Goldstar             | 4         | 2.23%   |
| TMX                  | 3         | 1.68%   |
| Hewlett-Packard      | 3         | 1.68%   |
| ASUSTek Computer     | 3         | 1.68%   |
| Philips              | 2         | 1.12%   |
| Panasonic            | 2         | 1.12%   |
| Lenovo               | 2         | 1.12%   |
| InfoVision           | 2         | 1.12%   |
| HannStar             | 2         | 1.12%   |
| Ancor Communications | 2         | 1.12%   |
| Acer                 | 2         | 1.12%   |
| Toshiba              | 1         | 0.56%   |
| KDB                  | 1         | 0.56%   |
| JDI                  | 1         | 0.56%   |
| Eizo                 | 1         | 0.56%   |
| AOC                  | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 4         | 2.23%   |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                 | 2         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 1.12%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 2         | 1.12%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 2         | 1.12%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 1.12%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 1.12%   |
| BOE LCD Monitor BOE0B56 1920x1080 309x174mm 14.0-inch                 | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO6DA8 2560x1600 301x188mm 14.0-inch        | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 1.12%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch        | 2         | 1.12%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 2         | 1.12%   |
| Apple Color LCD APPA02F 2880x1800 331x207mm 15.4-inch                 | 2         | 1.12%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.56%   |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch               | 1         | 0.56%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.56%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.56%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.56%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.56%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 520x290mm 23.4-inch     | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 1         | 0.56%   |
| Samsung Electronics LCD Monitor SAM07C0 1920x1080 480x270mm 21.7-inch | 1         | 0.56%   |
| Samsung Electronics C43J89x SAM0F5B 3840x1200 1050x330mm 43.3-inch    | 1         | 0.56%   |
| Samsung Electronics C32F39M SAM100B 1920x1080 698x393mm 31.5-inch     | 1         | 0.56%   |
| Samsung Electronics C24FG70 SAM0D57 1920x1080 532x304mm 24.1-inch     | 1         | 0.56%   |
| Philips PHL 276E8V PHLC18F 3840x2160 600x340mm 27.2-inch              | 1         | 0.56%   |
| Philips PHL 272P7VU PHL093A 3840x2160 597x336mm 27.0-inch             | 1         | 0.56%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 76        | 44.97%  |
| 3840x2160 (4K)     | 19        | 11.24%  |
| 1366x768 (WXGA)    | 15        | 8.88%   |
| 2880x1800          | 12        | 7.1%    |
| 2560x1440 (QHD)    | 12        | 7.1%    |
| 2560x1600          | 10        | 5.92%   |
| 1920x1200 (WUXGA)  | 6         | 3.55%   |
| 2256x1504          | 4         | 2.37%   |
| 1600x900 (HD+)     | 4         | 2.37%   |
| 3440x1440          | 2         | 1.18%   |
| 3200x2000          | 2         | 1.18%   |
| 3840x2400          | 1         | 0.59%   |
| 3840x1200          | 1         | 0.59%   |
| 1920x1280          | 1         | 0.59%   |
| 1680x1050 (WSXGA+) | 1         | 0.59%   |
| 1280x800 (WXGA)    | 1         | 0.59%   |
| 1280x1024 (SXGA)   | 1         | 0.59%   |
| 1024x600           | 1         | 0.59%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 49        | 28%     |
| 14     | 36        | 20.57%  |
| 13     | 29        | 16.57%  |
| 27     | 13        | 7.43%   |
| 16     | 9         | 5.14%   |
| 24     | 8         | 4.57%   |
| 17     | 8         | 4.57%   |
| 12     | 8         | 4.57%   |
| 23     | 3         | 1.71%   |
| 34     | 2         | 1.14%   |
| 31     | 2         | 1.14%   |
| 21     | 2         | 1.14%   |
| 86     | 1         | 0.57%   |
| 46     | 1         | 0.57%   |
| 43     | 1         | 0.57%   |
| 22     | 1         | 0.57%   |
| 20     | 1         | 0.57%   |
| 10     | 1         | 0.57%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 106       | 60.92%  |
| 201-300     | 25        | 14.37%  |
| 501-600     | 21        | 12.07%  |
| 351-400     | 8         | 4.6%    |
| 601-700     | 5         | 2.87%   |
| 401-500     | 4         | 2.3%    |
| 1001-1500   | 3         | 1.72%   |
| 701-800     | 2         | 1.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 107       | 70.86%  |
| 16/10 | 34        | 22.52%  |
| 3/2   | 5         | 3.31%   |
| 21/9  | 2         | 1.32%   |
| 5/4   | 1         | 0.66%   |
| 3.20  | 1         | 0.66%   |
| 0.56  | 1         | 0.66%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 55        | 31.43%  |
| 101-110        | 49        | 28%     |
| 301-350        | 13        | 7.43%   |
| 201-250        | 11        | 6.29%   |
| 71-80          | 10        | 5.71%   |
| 61-70          | 8         | 4.57%   |
| 121-130        | 8         | 4.57%   |
| 111-120        | 8         | 4.57%   |
| 351-500        | 4         | 2.29%   |
| 251-300        | 2         | 1.14%   |
| 151-200        | 2         | 1.14%   |
| 501-1000       | 2         | 1.14%   |
| More than 1000 | 1         | 0.57%   |
| 41-50          | 1         | 0.57%   |
| 141-150        | 1         | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 71        | 42.51%  |
| 161-240       | 41        | 24.55%  |
| 101-120       | 20        | 11.98%  |
| More than 240 | 17        | 10.18%  |
| 51-100        | 16        | 9.58%   |
| 1-50          | 2         | 1.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 111       | 73.51%  |
| 2     | 28        | 18.54%  |
| 3     | 6         | 3.97%   |
| 0     | 6         | 3.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 104       | 47.71%  |
| Realtek Semiconductor             | 65        | 29.82%  |
| MediaTek                          | 16        | 7.34%   |
| Qualcomm Atheros                  | 11        | 5.05%   |
| Broadcom                          | 7         | 3.21%   |
| Qualcomm                          | 4         | 1.83%   |
| Lenovo                            | 4         | 1.83%   |
| Xiaomi                            | 1         | 0.46%   |
| QinHeng Electronics               | 1         | 0.46%   |
| Microsoft                         | 1         | 0.46%   |
| Fibocom                           | 1         | 0.46%   |
| Ericsson Business Mobile Networks | 1         | 0.46%   |
| Edimax Technology                 | 1         | 0.46%   |
| D-Link                            | 1         | 0.46%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 14.77%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 7.2%    |
| Intel Wi-Fi 6 AX200                                               | 15        | 5.68%   |
| Intel Wireless 8265 / 8275                                        | 10        | 3.79%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 9         | 3.41%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 3.03%   |
| Intel Wireless 8260                                               | 7         | 2.65%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.89%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 5         | 1.89%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.89%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.89%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 4         | 1.52%   |
| Intel Wireless 7265                                               | 4         | 1.52%   |
| Intel Wireless 7260                                               | 4         | 1.52%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.52%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 1.14%   |
| Intel Wireless-AC 9260                                            | 3         | 1.14%   |
| Intel Wireless 3160                                               | 3         | 1.14%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.14%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.14%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.14%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 3         | 1.14%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.76%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 2         | 0.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.76%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                 | 2         | 0.76%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 0.76%   |
| Intel Wireless 3165                                               | 2         | 0.76%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 2         | 0.76%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.76%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.76%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 103       | 68.67%  |
| MediaTek                          | 16        | 10.67%  |
| Qualcomm Atheros                  | 9         | 6%      |
| Realtek Semiconductor             | 7         | 4.67%   |
| Broadcom                          | 7         | 4.67%   |
| Qualcomm                          | 3         | 2%      |
| Microsoft                         | 1         | 0.67%   |
| Fibocom                           | 1         | 0.67%   |
| Ericsson Business Mobile Networks | 1         | 0.67%   |
| Edimax Technology                 | 1         | 0.67%   |
| D-Link                            | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 15        | 10%     |
| Intel Wireless 8265 / 8275                                     | 10        | 6.67%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 9         | 6%      |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 5.33%   |
| Intel Wireless 8260                                            | 7         | 4.67%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 4%      |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 4%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 5         | 3.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 3.33%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 2.67%   |
| Intel Wireless 7265                                            | 4         | 2.67%   |
| Intel Wireless 7260                                            | 4         | 2.67%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 4         | 2.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.67%   |
| Intel Wireless-AC 9260                                         | 3         | 2%      |
| Intel Wireless 3160                                            | 3         | 2%      |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2%      |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 2%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.33%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 2         | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.33%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 2         | 1.33%   |
| Intel Wireless 3165                                            | 2         | 1.33%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 2         | 1.33%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.33%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.67%   |
| Qualcomm QCA6390 Wireless Network Adapter                      | 1         | 0.67%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.67%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.67%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 1         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 1         | 0.67%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 59        | 55.66%  |
| Intel                 | 36        | 33.96%  |
| Lenovo                | 4         | 3.77%   |
| Qualcomm Atheros      | 3         | 2.83%   |
| Broadcom              | 2         | 1.89%   |
| Xiaomi                | 1         | 0.94%   |
| Qualcomm              | 1         | 0.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 39        | 34.51%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 19        | 16.81%  |
| Intel Ethernet Connection I219-LM                                 | 5         | 4.42%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 4.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.65%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3         | 2.65%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.77%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 1.77%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.77%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.77%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.88%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.88%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.88%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.88%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.88%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.88%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.88%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.88%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.88%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.88%   |
| Intel 700 Series Chipset Family Wi-Fi                             | 1         | 0.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.88%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.88%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 144       | 58.3%   |
| Ethernet | 102       | 41.3%   |
| Modem    | 1         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 137       | 85.63%  |
| Ethernet | 23        | 14.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 82        | 56.16%  |
| 1     | 61        | 41.78%  |
| 3     | 3         | 2.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 111       | 75.51%  |
| Yes  | 36        | 24.49%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 68.35%  |
| IMC Networks                    | 7         | 5.04%   |
| Foxconn / Hon Hai               | 7         | 5.04%   |
| Apple                           | 6         | 4.32%   |
| Qualcomm Atheros Communications | 5         | 3.6%    |
| Realtek Semiconductor           | 4         | 2.88%   |
| MediaTek                        | 4         | 2.88%   |
| Broadcom                        | 3         | 2.16%   |
| USI                             | 2         | 1.44%   |
| Lite-On Technology              | 2         | 1.44%   |
| Realtek                         | 1         | 0.72%   |
| Opticis                         | 1         | 0.72%   |
| Integrated System Solution      | 1         | 0.72%   |
| ASUSTek Computer                | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface               | 27        | 19.42%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 15        | 10.79%  |
| Intel AX200 Bluetooth                            | 15        | 10.79%  |
| Intel Bluetooth Device                           | 12        | 8.63%   |
| Intel AX201 Bluetooth                            | 10        | 7.19%   |
| Intel AX210 Bluetooth                            | 9         | 6.47%   |
| IMC Networks Wireless_Device                     | 5         | 3.6%    |
| Apple Bluetooth Host Controller                  | 5         | 3.6%    |
| MediaTek Wireless_Device                         | 4         | 2.88%   |
| Intel Wireless-AC 9260 Bluetooth Adapter         | 3         | 2.16%   |
| Foxconn / Hon Hai Wireless_Device                | 3         | 2.16%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter     | 3         | 2.16%   |
| USI Bluetooth Device                             | 2         | 1.44%   |
| Realtek Bluetooth Radio                          | 2         | 1.44%   |
| Qualcomm Atheros  Bluetooth Device               | 2         | 1.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth       | 2         | 1.44%   |
| Intel Wireless-AC 3168 Bluetooth                 | 2         | 1.44%   |
| Broadcom HP Portable SoftSailing                 | 2         | 1.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter          | 1         | 0.72%   |
| Realtek 802.11ac WLAN Adapter                    | 1         | 0.72%   |
| Realtek 802.11ac WLAN Adapter                    | 1         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0           | 1         | 0.72%   |
| Qualcomm Atheros AR9462 Bluetooth                | 1         | 0.72%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0            | 1         | 0.72%   |
| Opticis Bluetooth Radio                          | 1         | 0.72%   |
| Intel Centrino Bluetooth Wireless Transceiver    | 1         | 0.72%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter | 1         | 0.72%   |
| Integrated System Solution Bluetooth Device      | 1         | 0.72%   |
| IMC Networks Bluetooth Device                    | 1         | 0.72%   |
| IMC Networks BCM20702A0                          | 1         | 0.72%   |
| Foxconn / Hon Hai Bluetooth Adapter              | 1         | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]       | 1         | 0.72%   |
| ASUS Broadcom Bluetooth 2.1                      | 1         | 0.72%   |
| Apple Bluetooth USB Host Controller              | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 106       | 50.96%  |
| AMD                    | 44        | 21.15%  |
| Nvidia                 | 28        | 13.46%  |
| Lenovo                 | 6         | 2.88%   |
| C-Media Electronics    | 4         | 1.92%   |
| Realtek Semiconductor  | 3         | 1.44%   |
| Synaptics              | 2         | 0.96%   |
| Trust                  | 1         | 0.48%   |
| Satechi                | 1         | 0.48%   |
| Razer USA              | 1         | 0.48%   |
| Logitech               | 1         | 0.48%   |
| Kingston Technology    | 1         | 0.48%   |
| JMTek                  | 1         | 0.48%   |
| Hewlett-Packard        | 1         | 0.48%   |
| Goldvish               | 1         | 0.48%   |
| GN Netcom              | 1         | 0.48%   |
| Focusrite-Novation     | 1         | 0.48%   |
| DSEA A/S               | 1         | 0.48%   |
| Creative Technology    | 1         | 0.48%   |
| Corsair                | 1         | 0.48%   |
| AudioQuest             | 1         | 0.48%   |
| (LCS) USB Audio Device | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 41        | 15.53%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 24        | 9.09%   |
| Intel Sunrise Point-LP HD Audio                                         | 22        | 8.33%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 12        | 4.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 11        | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 10        | 3.79%   |
| Intel Cannon Lake PCH cAVS                                              | 9         | 3.41%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 9         | 3.41%   |
| Nvidia Audio device                                                     | 7         | 2.65%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 6         | 2.27%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 5         | 1.89%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 5         | 1.89%   |
| Nvidia GP107GL High Definition Audio Controller                         | 4         | 1.52%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 4         | 1.52%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 1.52%   |
| Intel Haswell-ULT HD Audio Controller                                   | 4         | 1.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 4         | 1.52%   |
| Intel Broadwell-U Audio Controller                                      | 4         | 1.52%   |
| Intel 8 Series HD Audio Controller                                      | 4         | 1.52%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 4         | 1.52%   |
| Realtek Semiconductor USB Audio                                         | 3         | 1.14%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 3         | 1.14%   |
| Nvidia GA106 High Definition Audio Controller                           | 3         | 1.14%   |
| Nvidia GA104 High Definition Audio Controller                           | 3         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                            | 3         | 1.14%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 2         | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                      | 2         | 0.76%   |
| Nvidia GK106 HDMI Audio Controller                                      | 2         | 0.76%   |
| Lenovo ThinkPad Dock Audio                                              | 2         | 0.76%   |
| Intel Raptor Lake-P/U/H cAVS                                            | 2         | 0.76%   |
| Intel Crystal Well HD Audio Controller                                  | 2         | 0.76%   |
| Intel CM238 HD Audio Controller                                         | 2         | 0.76%   |
| Intel 700 Series Chipset Family Precise Touch and Stylus Port #1        | 2         | 0.76%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 2         | 0.76%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 2         | 0.76%   |
| Trust USB microphone                                                    | 1         | 0.38%   |
| Satechi Audio & PD Adapter                                              | 1         | 0.38%   |
| Razer USA Razer Seiren Mini                                             | 1         | 0.38%   |
| Nvidia TU106 High Definition Audio Controller                           | 1         | 0.38%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 49        | 27.84%  |
| SK hynix                     | 37        | 21.02%  |
| Micron Technology            | 34        | 19.32%  |
| Kingston                     | 15        | 8.52%   |
| Crucial                      | 12        | 6.82%   |
| Unknown                      | 4         | 2.27%   |
| Unknown (ABCD)               | 3         | 1.7%    |
| Team                         | 3         | 1.7%    |
| Ramaxel Technology           | 3         | 1.7%    |
| Unknown                      | 3         | 1.7%    |
| Lexar                        | 2         | 1.14%   |
| A-DATA Technology            | 2         | 1.14%   |
| Smart Brazil                 | 1         | 0.57%   |
| Patriot Memory (PDP Systems) | 1         | 0.57%   |
| Patriot                      | 1         | 0.57%   |
| GOODRAM                      | 1         | 0.57%   |
| G.Skill                      | 1         | 0.57%   |
| Corsair                      | 1         | 0.57%   |
| Avant                        | 1         | 0.57%   |
| Apacer                       | 1         | 0.57%   |
| AMD                          | 1         | 0.57%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 2.67%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 1.6%    |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 3         | 1.6%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.6%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 3         | 1.6%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.6%    |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 3         | 1.6%    |
| Unknown                                                          | 3         | 1.6%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 1.07%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 1.07%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.07%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s       | 2         | 1.07%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.07%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.07%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 1.07%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.07%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 2         | 1.07%   |
| Micron RAM MT62F1G32D4DR-031 4GB SODIMM LPDDR5 5500MT/s          | 2         | 1.07%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.07%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.07%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.07%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.07%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s           | 2         | 1.07%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 1         | 0.53%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.53%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.53%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 0.53%   |
| Team RAM TEAMGROUP-SD4-2666 32GB SODIMM DDR4 2667MT/s            | 1         | 0.53%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 1         | 0.53%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.53%   |
| SK hynix RAM Module 32GB SODIMM DDR5 5600MT/s                    | 1         | 0.53%   |
| SK hynix RAM Module 16GB SODIMM DDR5 5600MT/s                    | 1         | 0.53%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 0.53%   |
| SK hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.53%   |
| SK hynix RAM HMT451S6AFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.53%   |
| SK hynix RAM HMCG88AGBSA092N 32GB SODIMM DDR5 5600MT/s           | 1         | 0.53%   |
| SK hynix RAM HMCG78AGBSA092N 16GB SODIMM DDR5 5600MT/s           | 1         | 0.53%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 75        | 52.08%  |
| DDR3   | 25        | 17.36%  |
| LPDDR5 | 17        | 11.81%  |
| LPDDR4 | 14        | 9.72%   |
| DDR5   | 7         | 4.86%   |
| LPDDR3 | 5         | 3.47%   |
| SDRAM  | 1         | 0.69%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 118       | 78.67%  |
| Row Of Chips | 28        | 18.67%  |
| Chip         | 3         | 2%      |
| Unknown      | 1         | 0.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 73        | 44.79%  |
| 16384 | 36        | 22.09%  |
| 4096  | 34        | 20.86%  |
| 32768 | 15        | 9.2%    |
| 2048  | 4         | 2.45%   |
| 1024  | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 35        | 22.44%  |
| 2667    | 30        | 19.23%  |
| 1600    | 24        | 15.38%  |
| 6400    | 14        | 8.97%   |
| 2400    | 12        | 7.69%   |
| 2133    | 12        | 7.69%   |
| 4267    | 7         | 4.49%   |
| 5600    | 4         | 2.56%   |
| 4266    | 4         | 2.56%   |
| 3266    | 4         | 2.56%   |
| 4800    | 3         | 1.92%   |
| 5500    | 2         | 1.28%   |
| 1867    | 2         | 1.28%   |
| 7500    | 1         | 0.64%   |
| 1334    | 1         | 0.64%   |
| Unknown | 1         | 0.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 30        | 23.62%  |
| IMC Networks                           | 18        | 14.17%  |
| Microdia                               | 15        | 11.81%  |
| Bison Electronics                      | 12        | 9.45%   |
| Realtek Semiconductor                  | 10        | 7.87%   |
| Sunplus Innovation Technology          | 7         | 5.51%   |
| Logitech                               | 5         | 3.94%   |
| Syntek                                 | 3         | 2.36%   |
| ShineTech                              | 3         | 2.36%   |
| Quanta                                 | 3         | 2.36%   |
| Lite-On Technology                     | 3         | 2.36%   |
| Acer                                   | 3         | 2.36%   |
| Sonix Technology                       | 2         | 1.57%   |
| Primax Electronics                     | 2         | 1.57%   |
| Luxvisions Innotech Limited            | 2         | 1.57%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.57%   |
| Alcor Micro                            | 2         | 1.57%   |
| Silicon Motion                         | 1         | 0.79%   |
| Samsung Electronics                    | 1         | 0.79%   |
| HDR webcam                             | 1         | 0.79%   |
| globaloptics                           | 1         | 0.79%   |
| Apple                                  | 1         | 0.79%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 18        | 13.95%  |
| IMC Networks Integrated Camera                    | 9         | 6.98%   |
| Microdia Integrated_Webcam_HD                     | 8         | 6.2%    |
| Chicony HP HD Camera                              | 7         | 5.43%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 6         | 4.65%   |
| Bison Integrated Camera                           | 6         | 4.65%   |
| Logitech HD Pro Webcam C920                       | 4         | 3.1%    |
| Syntek Integrated Camera                          | 3         | 2.33%   |
| Sunplus Integrated_Webcam_FHD                     | 3         | 2.33%   |
| Realtek Laptop Camera                             | 3         | 2.33%   |
| Realtek Integrated_Webcam_HD                      | 3         | 2.33%   |
| Sunplus Integrated_Webcam_HD                      | 2         | 1.55%   |
| ShineTech USB2.0 HD UVC WebCam                    | 2         | 1.55%   |
| Primax HP HD Webcam [Fixed]                       | 2         | 1.55%   |
| Microdia Webcam Vitade AF                         | 2         | 1.55%   |
| Microdia Integrated Webcam                        | 2         | 1.55%   |
| Lite-On Integrated Camera                         | 2         | 1.55%   |
| Bison HD Webcam                                   | 2         | 1.55%   |
| Alcor Micro USB 2.0 Camera                        | 2         | 1.55%   |
| Sunplus XiaoMi USB 2.0 Webcam                     | 1         | 0.78%   |
| Sunplus Laptop Integrated Webcam FHD              | 1         | 0.78%   |
| Sonix USB2.0 HD UVC WebCam                        | 1         | 0.78%   |
| Sonix USB2.0 FHD UVC WebCam                       | 1         | 0.78%   |
| Silicon Motion WebCam SC-13HDL11431N              | 1         | 0.78%   |
| Shinetech USB2.0 FHD UVC WebCam                   | 1         | 0.78%   |
| Samsung Galaxy series, misc. (MTP mode)           | 1         | 0.78%   |
| Realtek TV Camera                                 | 1         | 0.78%   |
| Realtek Thronmax Webcam Mic                       | 1         | 0.78%   |
| Realtek Lenovo EasyCamera                         | 1         | 0.78%   |
| Realtek Integrated Webcam                         | 1         | 0.78%   |
| Realtek HD WebCam                                 | 1         | 0.78%   |
| Quanta VGA WebCam                                 | 1         | 0.78%   |
| Quanta USB2.0 HD UVC WebCam                       | 1         | 0.78%   |
| Quanta HD WebCam                                  | 1         | 0.78%   |
| Microdia USB 2.0 Camera                           | 1         | 0.78%   |
| Microdia Laptop_Integrated_Webcam_HD              | 1         | 0.78%   |
| Microdia HP Integrated Webcam                     | 1         | 0.78%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 1         | 0.78%   |
| Luxvisions Innotech Limited Integrated Camera     | 1         | 0.78%   |
| Logitech Webcam C310                              | 1         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 16        | 41.03%  |
| Validity Sensors           | 15        | 38.46%  |
| Shenzhen Goodix Technology | 7         | 17.95%  |
| Focal-systems.Corp         | 1         | 2.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 17.95%  |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 10.26%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 7.69%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 7.69%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 5.13%   |
| Validity Sensors VFS491                                                    | 2         | 5.13%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 5.13%   |
| Synaptics UWP WBDI Device                                                  | 2         | 5.13%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 5.13%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.56%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 2.56%   |
| Synaptics UWP WBDI                                                         | 1         | 2.56%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 18        | 66.67%  |
| Broadcom    | 5         | 18.52%  |
| Yubico.com  | 3         | 11.11%  |
| Upek        | 1         | 3.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 18        | 66.67%  |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 2         | 7.41%   |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 7.41%   |
| Broadcom 5880                                              | 2         | 7.41%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 3.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 3.7%    |
| Broadcom 58200                                             | 1         | 3.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 66        | 43.42%  |
| 1     | 55        | 36.18%  |
| 2     | 28        | 18.42%  |
| 4     | 2         | 1.32%   |
| 3     | 1         | 0.66%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 37        | 31.62%  |
| Multimedia controller    | 23        | 19.66%  |
| Chipcard                 | 22        | 18.8%   |
| Graphics card            | 16        | 13.68%  |
| Net/wireless             | 5         | 4.27%   |
| Camera                   | 4         | 3.42%   |
| Bluetooth                | 3         | 2.56%   |
| Modem                    | 2         | 1.71%   |
| Card reader              | 2         | 1.71%   |
| Network                  | 1         | 0.85%   |
| Firewire controller      | 1         | 0.85%   |
| Communication controller | 1         | 0.85%   |

