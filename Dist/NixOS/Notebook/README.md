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

Total: 252

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Gaming Laptop 1... | [fe7dfd8247](https://linux-hardware.org/?probe=fe7dfd8247) | Feb 02, 2024 |
| Apple         | MacBookPro11,5              | [55197489b0](https://linux-hardware.org/?probe=55197489b0) | Feb 02, 2024 |
| Corsair       | Voyager a1600               | [86aec463cc](https://linux-hardware.org/?probe=86aec463cc) | Jan 30, 2024 |
| Corsair       | Voyager a1600               | [00605bf92c](https://linux-hardware.org/?probe=00605bf92c) | Jan 28, 2024 |
| Sony          | VGN-CS11S_Q                 | [df687ca726](https://linux-hardware.org/?probe=df687ca726) | Jan 26, 2024 |
| Apple         | MacBookPro11,5              | [d7308911e4](https://linux-hardware.org/?probe=d7308911e4) | Jan 26, 2024 |
| Framework     | Laptop                      | [64d0e147fe](https://linux-hardware.org/?probe=64d0e147fe) | Jan 25, 2024 |
| Sony          | VGN-CS11S_Q                 | [4c9e427a30](https://linux-hardware.org/?probe=4c9e427a30) | Jan 25, 2024 |
| Lenovo        | Legion Y530-15ICH 81FV      | [4a41cdcc67](https://linux-hardware.org/?probe=4a41cdcc67) | Jan 25, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c2be9790ea](https://linux-hardware.org/?probe=c2be9790ea) | Jan 25, 2024 |
| Lenovo        | ThinkPad T495 20NJ0016MX    | [31aa08c915](https://linux-hardware.org/?probe=31aa08c915) | Jan 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [553986db8b](https://linux-hardware.org/?probe=553986db8b) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f73bc25ab5](https://linux-hardware.org/?probe=f73bc25ab5) | Jan 17, 2024 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [ca16a763c8](https://linux-hardware.org/?probe=ca16a763c8) | Jan 17, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | [6cfbe412a8](https://linux-hardware.org/?probe=6cfbe412a8) | Jan 16, 2024 |
| System76      | Oryx Pro                    | [db771e1a08](https://linux-hardware.org/?probe=db771e1a08) | Jan 16, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8578d3d843](https://linux-hardware.org/?probe=8578d3d843) | Jan 15, 2024 |
| Apple         | MacBookPro3,1               | [87d8854210](https://linux-hardware.org/?probe=87d8854210) | Jan 12, 2024 |
| Apple         | MacBookPro11,3              | [9297ef72df](https://linux-hardware.org/?probe=9297ef72df) | Jan 12, 2024 |
| Apple         | MacBookPro11,3              | [17fa0ca044](https://linux-hardware.org/?probe=17fa0ca044) | Jan 12, 2024 |
| Timi          | Xiaomi Book Pro 16 2022     | [ee3988fb25](https://linux-hardware.org/?probe=ee3988fb25) | Jan 09, 2024 |
| Dell          | XPS 15 9530                 | [40a1d7ca08](https://linux-hardware.org/?probe=40a1d7ca08) | Jan 08, 2024 |
| HUAWEI        | WRT-WX9                     | [5b9a494436](https://linux-hardware.org/?probe=5b9a494436) | Jan 08, 2024 |
| Dell          | XPS 9315                    | [af18bb67fd](https://linux-hardware.org/?probe=af18bb67fd) | Jan 08, 2024 |
| Framework     | Laptop (12th Gen Intel C... | [00c7d53339](https://linux-hardware.org/?probe=00c7d53339) | Jan 08, 2024 |
| Fujitsu       | LIFEBOOK U7412              | [e7b60f15e8](https://linux-hardware.org/?probe=e7b60f15e8) | Jan 08, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | [739eae84a2](https://linux-hardware.org/?probe=739eae84a2) | Jan 07, 2024 |
| Dell          | Inspiron 5767               | [460e0f5fa4](https://linux-hardware.org/?probe=460e0f5fa4) | Jan 05, 2024 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [8d22dafe25](https://linux-hardware.org/?probe=8d22dafe25) | Jan 03, 2024 |
| Dynabook      | PORTEGE X30L-K              | [9c965e61f4](https://linux-hardware.org/?probe=9c965e61f4) | Jan 02, 2024 |
| Lenovo        | Yoga 7 16IRL8 82YN          | [5ea7f924df](https://linux-hardware.org/?probe=5ea7f924df) | Jan 02, 2024 |
| Lenovo        | ThinkPad Twist 33476LU      | [bb88a71510](https://linux-hardware.org/?probe=bb88a71510) | Jan 01, 2024 |
| System76      | Serval WS                   | [3dd4d45859](https://linux-hardware.org/?probe=3dd4d45859) | Dec 30, 2023 |
| Acer          | Aspire A515-54G             | [35e2f8c10c](https://linux-hardware.org/?probe=35e2f8c10c) | Dec 29, 2023 |
| HP            | ZBook Firefly 14 inch G1... | [97e425d424](https://linux-hardware.org/?probe=97e425d424) | Dec 26, 2023 |
| Dell          | XPS 13 9380                 | [541f2d959f](https://linux-hardware.org/?probe=541f2d959f) | Dec 26, 2023 |
| Fujitsu       | LIFEBOOK U7412              | [a2797ec36b](https://linux-hardware.org/?probe=a2797ec36b) | Dec 26, 2023 |
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
| Gigabyte      | B550I AORUS PRO AX          | [07e6828b2e](https://linux-hardware.org/?probe=07e6828b2e) | Nov 23, 2023 |
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
| Gigabyte      | B550I AORUS PRO AX          | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
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
| Gigabyte      | B550I AORUS PRO AX          | [959f3b36df](https://linux-hardware.org/?probe=959f3b36df) | Jul 26, 2023 |
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
| Gigabyte      | B550I AORUS PRO AX          | [bbbc9206b4](https://linux-hardware.org/?probe=bbbc9206b4) | Apr 17, 2023 |
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
| NixOS 23.05                      | 63        | 31.66%  |
| NixOS 23.11                      | 48        | 24.12%  |
| NixOS 22.11                      | 27        | 13.57%  |
| NixOS 24.05                      | 20        | 10.05%  |
| NixOS 22.05                      | 18        | 9.05%   |
| NixOS 21.11                      | 9         | 4.52%   |
| NixOS                            | 2         | 1.01%   |
| NixOS 21.11pre302265.c6c4a3d45ab | 1         | 0.5%    |
| NixOS 21.11.20210606.fbfb794     | 1         | 0.5%    |
| NixOS 21.05.4384.4f37689c8a2     | 1         | 0.5%    |
| NixOS 21.05.3443.ee90403e147     | 1         | 0.5%    |
| NixOS 21.05.2132.733682c3292     | 1         | 0.5%    |
| NixOS 21.05.20210423.c21475e     | 1         | 0.5%    |
| NixOS 21.03.20200927.84d74ae     | 1         | 0.5%    |
| NixOS 20.09pre-git               | 1         | 0.5%    |
| NixOS 20.03.2351.f8248ab6d9e     | 1         | 0.5%    |
| NixOS 19.09.2522.75f4ba05c63     | 1         | 0.5%    |
| NixOS 19.09.2220.92231f4f32f     | 1         | 0.5%    |
| NixOS 19.03.173054.754763ff4ba   | 1         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| NixOS | 175       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version        | Notebooks | Percent |
|----------------|-----------|---------|
| 6.1.69         | 8         | 3.79%   |
| 6.6.8          | 5         | 2.37%   |
| 6.1.55         | 5         | 2.37%   |
| 6.3.8          | 4         | 1.9%    |
| 6.1.68         | 4         | 1.9%    |
| 6.1.53         | 4         | 1.9%    |
| 6.1.51         | 4         | 1.9%    |
| 6.6.0          | 3         | 1.42%   |
| 6.5.5          | 3         | 1.42%   |
| 6.3.3          | 3         | 1.42%   |
| 6.1.64         | 3         | 1.42%   |
| 6.1.61         | 3         | 1.42%   |
| 6.1.60         | 3         | 1.42%   |
| 6.1.47         | 3         | 1.42%   |
| 6.1.38         | 3         | 1.42%   |
| 6.1.31         | 3         | 1.42%   |
| 5.15.74        | 3         | 1.42%   |
| 5.15.43        | 3         | 1.42%   |
| 6.6.3          | 2         | 0.95%   |
| 6.5.7-xanmod1  | 2         | 0.95%   |
| 6.5.6          | 2         | 0.95%   |
| 6.5.2          | 2         | 0.95%   |
| 6.5.11-xanmod1 | 2         | 0.95%   |
| 6.4.0          | 2         | 0.95%   |
| 6.3.1          | 2         | 0.95%   |
| 6.1.67         | 2         | 0.95%   |
| 6.1.63         | 2         | 0.95%   |
| 6.1.42         | 2         | 0.95%   |
| 6.1.41         | 2         | 0.95%   |
| 6.1.35         | 2         | 0.95%   |
| 6.1.34         | 2         | 0.95%   |
| 6.1.0          | 2         | 0.95%   |
| 6.0.10         | 2         | 0.95%   |
| 5.16.15        | 2         | 0.95%   |
| 5.15.72        | 2         | 0.95%   |
| 5.15.68        | 2         | 0.95%   |
| 5.15.64        | 2         | 0.95%   |
| 5.15.26        | 2         | 0.95%   |
| 5.13.7         | 2         | 0.95%   |
| 6.7.2          | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1.69  | 8         | 3.79%   |
| 6.6.8   | 6         | 2.84%   |
| 6.1.55  | 5         | 2.37%   |
| 6.3.8   | 4         | 1.9%    |
| 6.1.68  | 4         | 1.9%    |
| 6.1.53  | 4         | 1.9%    |
| 6.1.51  | 4         | 1.9%    |
| 6.7.0   | 3         | 1.42%   |
| 6.6.0   | 3         | 1.42%   |
| 6.5.5   | 3         | 1.42%   |
| 6.5.11  | 3         | 1.42%   |
| 6.3.3   | 3         | 1.42%   |
| 6.1.64  | 3         | 1.42%   |
| 6.1.61  | 3         | 1.42%   |
| 6.1.60  | 3         | 1.42%   |
| 6.1.47  | 3         | 1.42%   |
| 6.1.38  | 3         | 1.42%   |
| 6.1.31  | 3         | 1.42%   |
| 6.0.10  | 3         | 1.42%   |
| 5.15.74 | 3         | 1.42%   |
| 5.15.43 | 3         | 1.42%   |
| 6.6.4   | 2         | 0.95%   |
| 6.6.3   | 2         | 0.95%   |
| 6.6.2   | 2         | 0.95%   |
| 6.5.7   | 2         | 0.95%   |
| 6.5.6   | 2         | 0.95%   |
| 6.5.2   | 2         | 0.95%   |
| 6.4.0   | 2         | 0.95%   |
| 6.3.1   | 2         | 0.95%   |
| 6.2.9   | 2         | 0.95%   |
| 6.1.67  | 2         | 0.95%   |
| 6.1.63  | 2         | 0.95%   |
| 6.1.42  | 2         | 0.95%   |
| 6.1.41  | 2         | 0.95%   |
| 6.1.35  | 2         | 0.95%   |
| 6.1.34  | 2         | 0.95%   |
| 6.1.0   | 2         | 0.95%   |
| 5.16.15 | 2         | 0.95%   |
| 5.15.72 | 2         | 0.95%   |
| 5.15.68 | 2         | 0.95%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 71        | 35.86%  |
| 5.15    | 31        | 15.66%  |
| 6.6     | 18        | 9.09%   |
| 6.5     | 11        | 5.56%   |
| 6.3     | 11        | 5.56%   |
| 6.4     | 8         | 4.04%   |
| 6.2     | 7         | 3.54%   |
| 6.0     | 6         | 3.03%   |
| 5.16    | 6         | 3.03%   |
| 6.7     | 5         | 2.53%   |
| 5.8     | 3         | 1.52%   |
| 5.19    | 3         | 1.52%   |
| 5.13    | 3         | 1.52%   |
| 5.10    | 3         | 1.52%   |
| 5.7     | 2         | 1.01%   |
| 5.4     | 2         | 1.01%   |
| 5.18    | 2         | 1.01%   |
| 5.17    | 2         | 1.01%   |
| 4.19    | 2         | 1.01%   |
| 5.12    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 174       | 99.43%  |
| i686   | 1         | 0.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Unknown      | 49        | 26.63%  |
| GNOME        | 39        | 21.2%   |
| KDE5         | 25        | 13.59%  |
| sway         | 20        | 10.87%  |
| Hyprland     | 19        | 10.33%  |
| KDE          | 11        | 5.98%   |
| none+i3      | 8         | 4.35%   |
| XFCE         | 3         | 1.63%   |
| Pantheon     | 2         | 1.09%   |
| none+xmonad  | 2         | 1.09%   |
| none+awesome | 2         | 1.09%   |
| Budgie       | 2         | 1.09%   |
| X-Cinnamon   | 1         | 0.54%   |
| none+bspwm   | 1         | 0.54%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 77        | 41.4%   |
| Unknown | 68        | 36.56%  |
| X11     | 35        | 18.82%  |
| Tty     | 6         | 3.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 39.66%  |
| GDM     | 47        | 26.26%  |
| SDDM    | 39        | 21.79%  |
| LightDM | 22        | 12.29%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 109       | 60.89%  |
| Unknown    | 34        | 18.99%  |
| en_GB      | 9         | 5.03%   |
| pt_PT      | 3         | 1.68%   |
| en_AU      | 3         | 1.68%   |
| pt_BR      | 2         | 1.12%   |
| fr_FR      | 2         | 1.12%   |
| en_DK      | 2         | 1.12%   |
| en_CA      | 2         | 1.12%   |
| de_DE      | 2         | 1.12%   |
| C          | 2         | 1.12%   |
| ru_RU      | 1         | 0.56%   |
| ro_RO      | 1         | 0.56%   |
| pl_PL      | 1         | 0.56%   |
| lv_LV      | 1         | 0.56%   |
| lt_LT      | 1         | 0.56%   |
| it_IT      | 1         | 0.56%   |
| es_MX      | 1         | 0.56%   |
| en_IN      | 1         | 0.56%   |
| en_IE.UTF8 | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 161       | 92%     |
| BIOS | 14        | 8%      |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 100       | 55.56%  |
| Btrfs   | 31        | 17.22%  |
| Tmpfs   | 19        | 10.56%  |
| Zfs     | 16        | 8.89%   |
| Xfs     | 9         | 5%      |
| Unknown | 3         | 1.67%   |
| F2fs    | 2         | 1.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 166       | 93.79%  |
| MBR     | 6         | 3.39%   |
| Unknown | 5         | 2.82%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 150       | 84.27%  |
| Yes       | 28        | 15.73%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 77.27%  |
| Yes       | 40        | 22.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 61        | 34.86%  |
| Dell                   | 26        | 14.86%  |
| ASUSTek Computer       | 19        | 10.86%  |
| Hewlett-Packard        | 16        | 9.14%   |
| Apple                  | 10        | 5.71%   |
| Framework              | 6         | 3.43%   |
| MSI                    | 5         | 2.86%   |
| Acer                   | 4         | 2.29%   |
| System76               | 3         | 1.71%   |
| GPD                    | 3         | 1.71%   |
| Timi                   | 2         | 1.14%   |
| MECHREVO               | 2         | 1.14%   |
| HUAWEI                 | 2         | 1.14%   |
| Gigabyte Technology    | 2         | 1.14%   |
| Toshiba                | 1         | 0.57%   |
| Sony                   | 1         | 0.57%   |
| Samsung Electronics    | 1         | 0.57%   |
| OBSIDIAN-PC            | 1         | 0.57%   |
| Microtech              | 1         | 0.57%   |
| Medion                 | 1         | 0.57%   |
| MACHENIKE              | 1         | 0.57%   |
| Intel                  | 1         | 0.57%   |
| Fujitsu                | 1         | 0.57%   |
| Dynabook               | 1         | 0.57%   |
| Corsair                | 1         | 0.57%   |
| Blackview              | 1         | 0.57%   |
| Avell High Performance | 1         | 0.57%   |
| Alienware              | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                 | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Apple MacBookPro11,5                                 | 4         | 2.29%   |
| Framework Laptop (12th Gen Intel Core)               | 3         | 1.71%   |
| Framework Laptop                                     | 3         | 1.71%   |
| Apple MacBookPro11,3                                 | 3         | 1.71%   |
| HP ZBook Firefly 14 inch G10 A Mobile Workstation PC | 2         | 1.14%   |
| HP EliteBook 8470p                                   | 2         | 1.14%   |
| Dell Latitude 7420                                   | 2         | 1.14%   |
| ASUS Vivobook Go E1404FA_E1404FA                     | 2         | 1.14%   |
| Toshiba Satellite L50-B                              | 1         | 0.57%   |
| Timi Xiaomi Book Pro 16 2022                         | 1         | 0.57%   |
| Timi Redmi Book Pro 15 2022                          | 1         | 0.57%   |
| System76 Serval WS                                   | 1         | 0.57%   |
| System76 Pangolin                                    | 1         | 0.57%   |
| System76 Oryx Pro                                    | 1         | 0.57%   |
| Sony VGN-CS11S_Q                                     | 1         | 0.57%   |
| Samsung 530U3BI/530U4BI/530U4BH                      | 1         | 0.57%   |
| OBSIDIAN-PC N13_N140ZU                               | 1         | 0.57%   |
| MSI Prestige 16Studio A13VE                          | 1         | 0.57%   |
| MSI Prestige 14 A10SC                                | 1         | 0.57%   |
| MSI GE70 2PE                                         | 1         | 0.57%   |
| MSI Bravo 15 B5DD                                    | 1         | 0.57%   |
| MSI Alpha 15 B5EEK                                   | 1         | 0.57%   |
| Microtech CoreBook Lite                              | 1         | 0.57%   |
| Medion M14L-256                                      | 1         | 0.57%   |
| MECHREVO WUJIE 14                                    | 1         | 0.57%   |
| MECHREVO Code01 Ver2.0                               | 1         | 0.57%   |
| MACHENIKE F117-7P                                    | 1         | 0.57%   |
| Lenovo Yoga Slim 7 Carbon 14ACN6 82L0                | 1         | 0.57%   |
| Lenovo Yoga Slim 7 13ACN5 82CY                       | 1         | 0.57%   |
| Lenovo Yoga 7 16IRL8 82YN                            | 1         | 0.57%   |
| Lenovo Yoga 14sARE 2020 82A8                         | 1         | 0.57%   |
| Lenovo ThinkPad X390 20Q0CTO1WW                      | 1         | 0.57%   |
| Lenovo ThinkPad X260 20F5S6MF02                      | 1         | 0.57%   |
| Lenovo ThinkPad X260 20F5S4BY00                      | 1         | 0.57%   |
| Lenovo ThinkPad X250 20CLS18S0T                      | 1         | 0.57%   |
| Lenovo ThinkPad X230 2333AZ2                         | 1         | 0.57%   |
| Lenovo ThinkPad X230 23243E9                         | 1         | 0.57%   |
| Lenovo ThinkPad X1 Extreme 20MFCTO1WW                | 1         | 0.57%   |
| Lenovo ThinkPad X1 Carbon Gen 11 21HNA09QCD          | 1         | 0.57%   |
| Lenovo ThinkPad X1 Carbon Gen 10 21CB007AUK          | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 38        | 21.71%  |
| Dell XPS           | 10        | 5.71%   |
| Lenovo Legion      | 8         | 4.57%   |
| HP EliteBook       | 8         | 4.57%   |
| Apple MacBookPro11 | 8         | 4.57%   |
| Dell Latitude      | 7         | 4%      |
| ASUS ROG           | 7         | 4%      |
| Lenovo IdeaPad     | 6         | 3.43%   |
| Framework Laptop   | 6         | 3.43%   |
| ASUS Zenbook       | 5         | 2.86%   |
| Lenovo Yoga        | 4         | 2.29%   |
| HP ZBook           | 4         | 2.29%   |
| Dell Inspiron      | 4         | 2.29%   |
| ASUS Vivobook      | 4         | 2.29%   |
| Acer Aspire        | 4         | 2.29%   |
| Lenovo ThinkBook   | 3         | 1.71%   |
| Dell Precision     | 3         | 1.71%   |
| MSI Prestige       | 2         | 1.14%   |
| HP ProBook         | 2         | 1.14%   |
| Toshiba Satellite  | 1         | 0.57%   |
| Timi Xiaomi        | 1         | 0.57%   |
| Timi Redmi         | 1         | 0.57%   |
| System76 Serval    | 1         | 0.57%   |
| System76 Pangolin  | 1         | 0.57%   |
| System76 Oryx      | 1         | 0.57%   |
| Sony VGN-CS11S     | 1         | 0.57%   |
| Samsung 530U3BI    | 1         | 0.57%   |
| OBSIDIAN-PC N13    | 1         | 0.57%   |
| MSI GE70           | 1         | 0.57%   |
| MSI Bravo          | 1         | 0.57%   |
| MSI Alpha          | 1         | 0.57%   |
| Microtech CoreBook | 1         | 0.57%   |
| Medion M14L-256    | 1         | 0.57%   |
| MECHREVO WUJIE     | 1         | 0.57%   |
| MECHREVO Code01    | 1         | 0.57%   |
| MACHENIKE F117-7P  | 1         | 0.57%   |
| Lenovo Slim        | 1         | 0.57%   |
| Lenovo G50-70      | 1         | 0.57%   |
| Intel SharkBay     | 1         | 0.57%   |
| HUAWEI WRT-WX9     | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 29        | 16.57%  |
| 2022 | 23        | 13.14%  |
| 2023 | 20        | 11.43%  |
| 2020 | 17        | 9.71%   |
| 2019 | 15        | 8.57%   |
| 2018 | 15        | 8.57%   |
| 2016 | 13        | 7.43%   |
| 2017 | 8         | 4.57%   |
| 2014 | 8         | 4.57%   |
| 2013 | 8         | 4.57%   |
| 2015 | 6         | 3.43%   |
| 2012 | 5         | 2.86%   |
| 2011 | 3         | 1.71%   |
| 2008 | 3         | 1.71%   |
| 2009 | 1         | 0.57%   |
| 2007 | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 175       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 170       | 95.51%  |
| Enabled  | 8         | 4.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 172       | 98.29%  |
| Yes  | 3         | 1.71%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 44        | 25%     |
| 8.01-16.0   | 42        | 23.86%  |
| 32.01-64.0  | 37        | 21.02%  |
| 4.01-8.0    | 28        | 15.91%  |
| 64.01-256.0 | 12        | 6.82%   |
| 24.01-32.0  | 7         | 3.98%   |
| 3.01-4.0    | 5         | 2.84%   |
| 0.51-1.0    | 1         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 57        | 28.64%  |
| 2.01-3.0   | 40        | 20.1%   |
| 3.01-4.0   | 38        | 19.1%   |
| 8.01-16.0  | 26        | 13.07%  |
| 1.01-2.0   | 17        | 8.54%   |
| 16.01-24.0 | 6         | 3.02%   |
| 0.51-1.0   | 6         | 3.02%   |
| 24.01-32.0 | 5         | 2.51%   |
| 32.01-64.0 | 2         | 1.01%   |
| 0.01-0.5   | 2         | 1.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 135       | 75.84%  |
| 2      | 39        | 21.91%  |
| 3      | 4         | 2.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 159       | 90.86%  |
| Yes       | 16        | 9.14%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 116       | 65.17%  |
| No        | 62        | 34.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 174       | 99.43%  |
| No        | 1         | 0.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 94.35%  |
| No        | 10        | 5.65%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 41        | 23.43%  |
| UK          | 10        | 5.71%   |
| Italy       | 10        | 5.71%   |
| Germany     | 10        | 5.71%   |
| Russia      | 9         | 5.14%   |
| France      | 8         | 4.57%   |
| Portugal    | 5         | 2.86%   |
| Poland      | 5         | 2.86%   |
| Netherlands | 5         | 2.86%   |
| Canada      | 5         | 2.86%   |
| Brazil      | 5         | 2.86%   |
| Ukraine     | 4         | 2.29%   |
| Sweden      | 4         | 2.29%   |
| Czechia     | 4         | 2.29%   |
| Switzerland | 3         | 1.71%   |
| Norway      | 3         | 1.71%   |
| Japan       | 3         | 1.71%   |
| Austria     | 3         | 1.71%   |
| Spain       | 2         | 1.14%   |
| Singapore   | 2         | 1.14%   |
| Qatar       | 2         | 1.14%   |
| Iraq        | 2         | 1.14%   |
| India       | 2         | 1.14%   |
| China       | 2         | 1.14%   |
| Belgium     | 2         | 1.14%   |
| Australia   | 2         | 1.14%   |
| Vietnam     | 1         | 0.57%   |
| Uzbekistan  | 1         | 0.57%   |
| Uruguay     | 1         | 0.57%   |
| Thailand    | 1         | 0.57%   |
| Slovenia    | 1         | 0.57%   |
| Serbia      | 1         | 0.57%   |
| Romania     | 1         | 0.57%   |
| Peru        | 1         | 0.57%   |
| Mexico      | 1         | 0.57%   |
| Malaysia    | 1         | 0.57%   |
| Lithuania   | 1         | 0.57%   |
| Latvia      | 1         | 0.57%   |
| Kuwait      | 1         | 0.57%   |
| Iran        | 1         | 0.57%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Vienna             | 3         | 1.62%   |
| London             | 3         | 1.62%   |
| Craigsville        | 3         | 1.62%   |
| Amsterdam          | 3         | 1.62%   |
| Singapore          | 2         | 1.08%   |
| Saratov            | 2         | 1.08%   |
| San Diego          | 2         | 1.08%   |
| Rochester          | 2         | 1.08%   |
| Richmond           | 2         | 1.08%   |
| Prague             | 2         | 1.08%   |
| Pradamano          | 2         | 1.08%   |
| Porto              | 2         | 1.08%   |
| Phoenix            | 2         | 1.08%   |
| Perth              | 2         | 1.08%   |
| Ottawa             | 2         | 1.08%   |
| Oslo               | 2         | 1.08%   |
| Montpellier        | 2         | 1.08%   |
| Marki              | 2         | 1.08%   |
| Los Angeles        | 2         | 1.08%   |
| Kharkiv            | 2         | 1.08%   |
| Halifax            | 2         | 1.08%   |
| Doha               | 2         | 1.08%   |
| Chapayevsk         | 2         | 1.08%   |
| Catania            | 2         | 1.08%   |
| Baghdad            | 2         | 1.08%   |
| Zurich             | 1         | 0.54%   |
| Yangzhou           | 1         | 0.54%   |
| Woodford           | 1         | 0.54%   |
| Woldegk            | 1         | 0.54%   |
| Warsaw             | 1         | 0.54%   |
| Vilnius            | 1         | 0.54%   |
| Villeurbanne       | 1         | 0.54%   |
| Victorville        | 1         | 0.54%   |
| Verneuil-sur-Seine | 1         | 0.54%   |
| Valpacos           | 1         | 0.54%   |
| Trento             | 1         | 0.54%   |
| Tremestieri Etneo  | 1         | 0.54%   |
| Tover              | 1         | 0.54%   |
| Tottenham          | 1         | 0.54%   |
| Tolyatti           | 1         | 0.54%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 57        | 76     | 26.64%  |
| Sandisk                        | 24        | 27     | 11.21%  |
| SK hynix                       | 15        | 18     | 7.01%   |
| Micron Technology              | 11        | 12     | 5.14%   |
| Toshiba                        | 10        | 10     | 4.67%   |
| WDC                            | 9         | 9      | 4.21%   |
| Unknown                        | 9         | 10     | 4.21%   |
| Seagate                        | 8         | 9      | 3.74%   |
| Kingston                       | 8         | 12     | 3.74%   |
| Intel                          | 7         | 8      | 3.27%   |
| Apple                          | 7         | 9      | 3.27%   |
| Crucial                        | 6         | 7      | 2.8%    |
| KIOXIA                         | 5         | 6      | 2.34%   |
| Kingston Technology Company    | 4         | 4      | 1.87%   |
| A-DATA Technology              | 4         | 4      | 1.87%   |
| Yangtze Memory Technologies    | 2         | 2      | 0.93%   |
| Union Memory (Shenzhen)        | 2         | 2      | 0.93%   |
| Transcend                      | 2         | 2      | 0.93%   |
| Phison Electronics             | 2         | 3      | 0.93%   |
| Micron/Crucial Technology      | 2         | 2      | 0.93%   |
| MAXIO Technology (Hangzhou)    | 2         | 2      | 0.93%   |
| SPCC                           | 1         | 1      | 0.47%   |
| Solid State Storage Technology | 1         | 1      | 0.47%   |
| S3+                            | 1         | 1      | 0.47%   |
| Realtek Semiconductor          | 1         | 8      | 0.47%   |
| Realtek                        | 1         | 1      | 0.47%   |
| PNY                            | 1         | 2      | 0.47%   |
| LITEONIT                       | 1         | 1      | 0.47%   |
| Lite-On Technology             | 1         | 1      | 0.47%   |
| INNOVATION IT                  | 1         | 1      | 0.47%   |
| Hitachi                        | 1         | 2      | 0.47%   |
| HGST                           | 1         | 1      | 0.47%   |
| Dogfish                        | 1         | 1      | 0.47%   |
| Corsair                        | 1         | 1      | 0.47%   |
| China                          | 1         | 1      | 0.47%   |
| Biwin Storage Technology       | 1         | 1      | 0.47%   |
| BIWIN                          | 1         | 1      | 0.47%   |
| ADATA Technology               | 1         | 2      | 0.47%   |
| Unknown                        | 1         | 1      | 0.47%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 11        | 4.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 10        | 4.52%   |
| Intel SSDPEKNU512GZ 512GB                           | 4         | 1.81%   |
| Unknown MMC Card  32GB                              | 3         | 1.36%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 3         | 1.36%   |
| Samsung SSD 850 EVO 500GB                           | 3         | 1.36%   |
| Apple SSD SM0512G 500GB                             | 3         | 1.36%   |
| Unknown MMC Card  64GB                              | 2         | 0.9%    |
| Toshiba XG6 NVMe SSD Controller 256GB               | 2         | 0.9%    |
| SK hynix SKHynix_HFS001TDE9X084N 1024GB             | 2         | 0.9%    |
| SK hynix PC801 NVMe 512GB                           | 2         | 0.9%    |
| SK hynix HFM001TD3JX013N 1024GB                     | 2         | 0.9%    |
| Seagate ST2000LM007-1R8174 2TB                      | 2         | 0.9%    |
| Sandisk WD_BLACK SN770 1TB                          | 2         | 0.9%    |
| Sandisk WD Blue SN570 1TB                           | 2         | 0.9%    |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 2         | 0.9%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD 1TB | 2         | 0.9%    |
| Samsung SSD 870 EVO 500GB                           | 2         | 0.9%    |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.9%    |
| Samsung PM9A1 NVMe 1024GB                           | 2         | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.9%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 2         | 0.9%    |
| Micron MTFDKBA512TFH 512GB                          | 2         | 0.9%    |
| KIOXIA KBG50ZNV512G 512GB                           | 2         | 0.9%    |
| Kingston OM8PCP3512F-AI1 512GB                      | 2         | 0.9%    |
| Yangtze Memory ZHITAI TiPlus7100 2TB                | 1         | 0.45%   |
| Yangtze Memory YMTC PC300-1TB-B 1024GB              | 1         | 0.45%   |
| WDC WDS480G2G0B-00EPW0 480GB SSD                    | 1         | 0.45%   |
| WDC WDS200T1X0E-00AFY0 2TB                          | 1         | 0.45%   |
| WDC WD7500BPKX-75HPJT0 752GB                        | 1         | 0.45%   |
| WDC WD10SPZX-60Z10T1 1TB                            | 1         | 0.45%   |
| WDC WD10 JPLX-00MBPT0 1TB                           | 1         | 0.45%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                  | 1         | 0.45%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB                | 1         | 0.45%   |
| WDC PC SN530 SDBPTPZ-1T00-1002 1TB                  | 1         | 0.45%   |
| WDC PC SN530 SDBPNPZ-256G-1002 256GB                | 1         | 0.45%   |
| Unknown MMC Card  537GB                             | 1         | 0.45%   |
| Unknown MMC Card  250GB                             | 1         | 0.45%   |
| Unknown MMC Card  16GB                              | 1         | 0.45%   |
| Unknown MMC Card  128GB                             | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 9      | 47.06%  |
| WDC     | 3         | 3      | 17.65%  |
| Toshiba | 3         | 3      | 17.65%  |
| Hitachi | 1         | 2      | 5.88%   |
| HGST    | 1         | 1      | 5.88%   |
| Apple   | 1         | 1      | 5.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 18        | 22     | 31.58%  |
| SanDisk             | 6         | 6      | 10.53%  |
| Apple               | 6         | 8      | 10.53%  |
| Crucial             | 5         | 6      | 8.77%   |
| Kingston            | 4         | 7      | 7.02%   |
| Transcend           | 2         | 2      | 3.51%   |
| Micron Technology   | 2         | 2      | 3.51%   |
| WDC                 | 1         | 1      | 1.75%   |
| Toshiba             | 1         | 1      | 1.75%   |
| SPCC                | 1         | 1      | 1.75%   |
| SK hynix            | 1         | 1      | 1.75%   |
| S3+                 | 1         | 1      | 1.75%   |
| PNY                 | 1         | 2      | 1.75%   |
| LITEONIT            | 1         | 1      | 1.75%   |
| INNOVATION IT       | 1         | 1      | 1.75%   |
| Dogfish             | 1         | 1      | 1.75%   |
| Corsair             | 1         | 1      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| BIWIN               | 1         | 1      | 1.75%   |
| A-DATA Technology   | 1         | 1      | 1.75%   |
| Unknown             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 124       | 165    | 60.78%  |
| SSD  | 54        | 68     | 26.47%  |
| HDD  | 17        | 19     | 8.33%   |
| MMC  | 9         | 10     | 4.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 124       | 164    | 62.94%  |
| SATA | 58        | 82     | 29.44%  |
| MMC  | 9         | 10     | 4.57%   |
| SAS  | 6         | 6      | 3.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 47        | 60     | 66.2%   |
| 0.51-1.0   | 20        | 23     | 28.17%  |
| 1.01-2.0   | 3         | 3      | 4.23%   |
| 3.01-4.0   | 1         | 1      | 1.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 52        | 28.73%  |
| Unknown        | 35        | 19.34%  |
| 251-500        | 29        | 16.02%  |
| 101-250        | 20        | 11.05%  |
| 501-1000       | 19        | 10.5%   |
| 1001-2000      | 12        | 6.63%   |
| More than 3000 | 8         | 4.42%   |
| 2001-3000      | 5         | 2.76%   |
| 51-100         | 1         | 0.55%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 64        | 34.59%  |
| Unknown        | 35        | 18.92%  |
| 101-250        | 25        | 13.51%  |
| 21-50          | 20        | 10.81%  |
| 251-500        | 13        | 7.03%   |
| 51-100         | 12        | 6.49%   |
| 501-1000       | 8         | 4.32%   |
| 1001-2000      | 4         | 2.16%   |
| 2001-3000      | 3         | 1.62%   |
| More than 3000 | 1         | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10 JPLX-00MBPT0 1TB                      | 1         | 1      | 12.5%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 12.5%   |
| Toshiba MK2565GSXV 250GB                       | 1         | 1      | 12.5%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 12.5%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 12.5%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 12.5%   |
| Corsair Force GS 240GB SSD                     | 1         | 1      | 12.5%   |
| A-DATA Technology IM2P33F3A NVMe 256GB         | 1         | 1      | 12.5%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 2      | 25%     |
| WDC               | 1         | 1      | 12.5%   |
| SK hynix          | 1         | 1      | 12.5%   |
| Seagate           | 1         | 1      | 12.5%   |
| Micron Technology | 1         | 1      | 12.5%   |
| Corsair           | 1         | 1      | 12.5%   |
| A-DATA Technology | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 50%     |
| WDC     | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 50%     |
| NVMe | 2         | 2      | 25%     |
| SSD  | 2         | 2      | 25%     |

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
| Works    | 168       | 231    | 86.15%  |
| Detected | 18        | 22     | 9.23%   |
| Malfunc  | 8         | 8      | 4.1%    |
| Failed   | 1         | 1      | 0.51%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 81        | 36.65%  |
| Samsung Electronics                     | 46        | 20.81%  |
| Sandisk                                 | 23        | 10.41%  |
| SK hynix                                | 14        | 6.33%   |
| Micron Technology                       | 9         | 4.07%   |
| AMD                                     | 9         | 4.07%   |
| Kingston Technology Company             | 8         | 3.62%   |
| Toshiba America Info Systems            | 7         | 3.17%   |
| KIOXIA                                  | 4         | 1.81%   |
| ADATA Technology                        | 4         | 1.81%   |
| Micron/Crucial Technology               | 3         | 1.36%   |
| Yangtze Memory Technologies             | 2         | 0.9%    |
| Phison Electronics                      | 2         | 0.9%    |
| MAXIO Technology (Hangzhou)             | 2         | 0.9%    |
| Union Memory (Shenzhen)                 | 1         | 0.45%   |
| Solid State Storage Technology          | 1         | 0.45%   |
| Shenzhen Unionmemory Information System | 1         | 0.45%   |
| Realtek Semiconductor                   | 1         | 0.45%   |
| Marvell Technology Group                | 1         | 0.45%   |
| Lite-On Technology                      | 1         | 0.45%   |
| Biwin Storage Technology                | 1         | 0.45%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 18        | 8%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 5.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 4.89%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 9         | 4%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 3.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 3.56%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 8         | 3.56%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 3.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 3.11%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 3.11%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 5         | 2.22%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 5         | 2.22%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 4         | 1.78%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 4         | 1.78%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 1.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 1.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.78%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 3         | 1.33%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 3         | 1.33%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 3         | 1.33%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 3         | 1.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 1.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.33%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.89%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 2         | 0.89%   |
| SanDisk Ultra 3D / WD Blue SN570 NVMe SSD (DRAM-less)                          | 2         | 0.89%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 2         | 0.89%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 2         | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.89%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.89%   |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 2         | 0.89%   |
| Phison PS5019-E19 PCIe4 NVMe Controller (DRAM-less)                            | 2         | 0.89%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 2         | 0.89%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 2         | 0.89%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 2         | 0.89%   |
| Kingston Company NV2 NVMe SSD SM2267XT (DRAM-less)                             | 2         | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2         | 0.89%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.89%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 2         | 0.89%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 124       | 57.67%  |
| SATA | 74        | 34.42%  |
| RAID | 16        | 7.44%   |
| IDE  | 1         | 0.47%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 128       | 73.14%  |
| AMD    | 47        | 26.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel 12th Gen Core i7-1260P                   | 5         | 2.86%   |
| Intel Core i7-8750H CPU @ 2.20GHz              | 4         | 2.29%   |
| Intel Core i7-8565U CPU @ 1.80GHz              | 4         | 2.29%   |
| Intel Core i7-8550U CPU @ 1.80GHz              | 4         | 2.29%   |
| Intel Core i5-6300U CPU @ 2.40GHz              | 4         | 2.29%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz        | 4         | 2.29%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics     | 4         | 2.29%   |
| AMD Ryzen 7 5800H with Radeon Graphics         | 4         | 2.29%   |
| Intel Core i7-7500U CPU @ 2.70GHz              | 3         | 1.71%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz             | 3         | 1.71%   |
| Intel Core i5-8350U CPU @ 1.70GHz              | 3         | 1.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz              | 3         | 1.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz              | 3         | 1.71%   |
| Intel 12th Gen Core i5-1240P                   | 3         | 1.71%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz        | 3         | 1.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 3         | 1.71%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 3         | 1.71%   |
| AMD Ryzen 9 5900HX with Radeon Graphics        | 3         | 1.71%   |
| AMD Ryzen 7 PRO 7840HS w/ Radeon 780M Graphics | 3         | 1.71%   |
| AMD Ryzen 7 6800H with Radeon Graphics         | 3         | 1.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz             | 2         | 1.14%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz             | 2         | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 2         | 1.14%   |
| Intel Core i7-6600U CPU @ 2.60GHz              | 2         | 1.14%   |
| Intel Core i7-5600U CPU @ 2.60GHz              | 2         | 1.14%   |
| Intel Core i7-5500U CPU @ 2.40GHz              | 2         | 1.14%   |
| Intel Core i7-4980HQ CPU @ 2.80GHz             | 2         | 1.14%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz             | 2         | 1.14%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz             | 2         | 1.14%   |
| Intel Core i7-10510U CPU @ 1.80GHz             | 2         | 1.14%   |
| Intel Core i5-9300H CPU @ 2.40GHz              | 2         | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz              | 2         | 1.14%   |
| Intel Core i5-4210U CPU @ 1.70GHz              | 2         | 1.14%   |
| Intel Celeron N4100 CPU @ 1.10GHz              | 2         | 1.14%   |
| Intel 13th Gen Core i9-13900HX                 | 2         | 1.14%   |
| Intel 13th Gen Core i7-13700H                  | 2         | 1.14%   |
| Intel 12th Gen Core i7-1270P                   | 2         | 1.14%   |
| AMD Ryzen 9 5900HS with Radeon Graphics        | 2         | 1.14%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics     | 2         | 1.14%   |
| AMD Ryzen 7 5800U with Radeon Graphics         | 2         | 1.14%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 51        | 29.14%  |
| Other              | 39        | 22.29%  |
| Intel Core i5      | 23        | 13.14%  |
| AMD Ryzen 7        | 19        | 10.86%  |
| AMD Ryzen 7 PRO    | 12        | 6.86%   |
| AMD Ryzen 9        | 9         | 5.14%   |
| AMD Ryzen 5        | 6         | 3.43%   |
| Intel Celeron      | 4         | 2.29%   |
| Intel Core i3      | 3         | 1.71%   |
| Intel Xeon         | 2         | 1.14%   |
| Intel Core 2 Duo   | 2         | 1.14%   |
| Intel Pentium Gold | 1         | 0.57%   |
| Intel Core m3      | 1         | 0.57%   |
| Intel Core i9      | 1         | 0.57%   |
| Intel Atom         | 1         | 0.57%   |
| AMD Ryzen 5 PRO    | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 57        | 32.57%  |
| 8      | 43        | 24.57%  |
| 2      | 37        | 21.14%  |
| 12     | 12        | 6.86%   |
| 6      | 11        | 6.29%   |
| 14     | 6         | 3.43%   |
| 10     | 5         | 2.86%   |
| 24     | 2         | 1.14%   |
| 16     | 1         | 0.57%   |
| 1      | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 175       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 167       | 95.43%  |
| 1      | 8         | 4.57%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 174       | 98.86%  |
| 32-bit         | 1         | 0.57%   |
| Unknown        | 1         | 0.57%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 51        | 28.18%  |
| 0x0a50000c | 16        | 8.84%   |
| 0x806ea    | 7         | 3.87%   |
| 0x806c1    | 6         | 3.31%   |
| 0x40661    | 6         | 3.31%   |
| 0x08600106 | 6         | 3.31%   |
| 0x906ea    | 5         | 2.76%   |
| 0x906a3    | 5         | 2.76%   |
| 0x806e9    | 5         | 2.76%   |
| 0x306c3    | 5         | 2.76%   |
| 0x806ec    | 4         | 2.21%   |
| 0x806eb    | 4         | 2.21%   |
| 0x406e3    | 4         | 2.21%   |
| 0x40651    | 4         | 2.21%   |
| 0x306a9    | 4         | 2.21%   |
| 0x0a704103 | 4         | 2.21%   |
| 0x0a404102 | 4         | 2.21%   |
| 0x306d4    | 3         | 1.66%   |
| 0xb06a3    | 2         | 1.1%    |
| 0xb0671    | 2         | 1.1%    |
| 0x906ed    | 2         | 1.1%    |
| 0x906e9    | 2         | 1.1%    |
| 0x906a4    | 2         | 1.1%    |
| 0x706a8    | 2         | 1.1%    |
| 0x706a1    | 2         | 1.1%    |
| 0x506e3    | 2         | 1.1%    |
| 0x0a404101 | 2         | 1.1%    |
| 0x08a00008 | 2         | 1.1%    |
| 0x08600104 | 2         | 1.1%    |
| 0x08108109 | 2         | 1.1%    |
| 0xb06a2    | 1         | 0.55%   |
| 0xa0660    | 1         | 0.55%   |
| 0xa0652    | 1         | 0.55%   |
| 0x806d1    | 1         | 0.55%   |
| 0x706e5    | 1         | 0.55%   |
| 0x106c2    | 1         | 0.55%   |
| 0x10676    | 1         | 0.55%   |
| 0x0a704104 | 1         | 0.55%   |
| 0x0a601203 | 1         | 0.55%   |
| 0x0a50000d | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 38        | 21.71%  |
| Alderlake Hybrid | 22        | 12.57%  |
| Unknown          | 21        | 12%     |
| Zen 3            | 19        | 10.86%  |
| Haswell          | 17        | 9.71%   |
| TigerLake        | 12        | 6.86%   |
| Skylake          | 11        | 6.29%   |
| Zen 2            | 8         | 4.57%   |
| IvyBridge        | 7         | 4%      |
| Goldmont plus    | 4         | 2.29%   |
| Broadwell        | 4         | 2.29%   |
| Zen+             | 3         | 1.71%   |
| IceLake          | 3         | 1.71%   |
| CometLake        | 2         | 1.14%   |
| SandyBridge      | 1         | 0.57%   |
| Penryn           | 1         | 0.57%   |
| Core             | 1         | 0.57%   |
| Bonnell          | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 117       | 50.43%  |
| AMD    | 58        | 25%     |
| Nvidia | 57        | 24.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 15        | 6.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 11        | 4.64%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 11        | 4.64%   |
| Intel UHD Graphics 620                                                                | 9         | 3.8%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 3.8%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 8         | 3.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 7         | 2.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 7         | 2.95%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 7         | 2.95%   |
| AMD Rembrandt [Radeon 680M]                                                           | 7         | 2.95%   |
| Intel HD Graphics 620                                                                 | 6         | 2.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 6         | 2.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 5         | 2.11%   |
| AMD Phoenix1                                                                          | 5         | 2.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 4         | 1.69%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 4         | 1.69%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 1.69%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 1.69%   |
| Intel HD Graphics 5500                                                                | 4         | 1.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 1.69%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 1.69%   |
| AMD Venus XT [Radeon HD 8870M / R9 M270X/M370X]                                       | 4         | 1.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 1.69%   |
| Nvidia GP108M [GeForce MX250]                                                         | 3         | 1.27%   |
| Nvidia GK107M [GeForce GT 750M Mac Edition]                                           | 3         | 1.27%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 3         | 1.27%   |
| Intel Raptor Lake-S UHD Graphics                                                      | 3         | 1.27%   |
| Intel HD Graphics 530                                                                 | 3         | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 3         | 1.27%   |
| AMD Barcelo                                                                           | 3         | 1.27%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 2         | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                                         | 2         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 0.84%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 2         | 0.84%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 2         | 0.84%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 2         | 0.84%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                       | 2         | 0.84%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                       | 2         | 0.84%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                       | 2         | 0.84%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 67        | 38.29%  |
| Intel + Nvidia | 40        | 22.86%  |
| 1 x AMD        | 38        | 21.71%  |
| AMD + Nvidia   | 9         | 5.14%   |
| 1 x Nvidia     | 8         | 4.57%   |
| Intel + AMD    | 8         | 4.57%   |
| 2 x AMD        | 3         | 1.71%   |
| 2 x Intel      | 2         | 1.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 138       | 78.41%  |
| Proprietary | 36        | 20.45%  |
| Unknown     | 2         | 1.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 108       | 60.67%  |
| 0.01-0.5   | 27        | 15.17%  |
| 1.01-2.0   | 19        | 10.67%  |
| 3.01-4.0   | 10        | 5.62%   |
| 0.51-1.0   | 9         | 5.06%   |
| 8.01-16.0  | 3         | 1.69%   |
| 7.01-8.0   | 2         | 1.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| AU Optronics         | 36        | 16.9%   |
| BOE                  | 33        | 15.49%  |
| LG Display           | 24        | 11.27%  |
| Chimei Innolux       | 24        | 11.27%  |
| Samsung Electronics  | 17        | 7.98%   |
| Dell                 | 11        | 5.16%   |
| Apple                | 10        | 4.69%   |
| Sharp                | 9         | 4.23%   |
| PANDA                | 6         | 2.82%   |
| CSO                  | 6         | 2.82%   |
| Hewlett-Packard      | 5         | 2.35%   |
| Goldstar             | 5         | 2.35%   |
| TMX                  | 3         | 1.41%   |
| ASUSTek Computer     | 3         | 1.41%   |
| Ancor Communications | 3         | 1.41%   |
| Philips              | 2         | 0.94%   |
| Panasonic            | 2         | 0.94%   |
| Lenovo               | 2         | 0.94%   |
| InfoVision           | 2         | 0.94%   |
| HannStar             | 2         | 0.94%   |
| Acer                 | 2         | 0.94%   |
| Toshiba              | 1         | 0.47%   |
| KDB                  | 1         | 0.47%   |
| JDI                  | 1         | 0.47%   |
| Eizo                 | 1         | 0.47%   |
| BenQ                 | 1         | 0.47%   |
| AOC                  | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 6         | 2.82%   |
| Apple Color LCD APPA02F 2880x1800 331x207mm 15.4-inch                 | 3         | 1.41%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch | 2         | 0.94%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch          | 2         | 0.94%   |
| Dell P2418D DELD0C1 2560x1440 526x296mm 23.8-inch                     | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN152A 2560x1440 344x193mm 15.5-inch      | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 2         | 0.94%   |
| BOE LCD Monitor BOE0B56 1920x1080 309x174mm 14.0-inch                 | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO6DA8 2560x1600 301x188mm 14.0-inch        | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO4A90 1920x1080 309x174mm 14.0-inch        | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO103D 1920x1080 309x173mm 13.9-inch        | 2         | 0.94%   |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch          | 2         | 0.94%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                 | 2         | 0.94%   |
| Apple Color LCD APPA022 2880x1800 331x207mm 15.4-inch                 | 2         | 0.94%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.47%   |
| TMX TL140ADXP24-0 TMX2004 2880x1800 300x190mm 14.0-inch               | 1         | 0.47%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP1548 1920x1200 288x180mm 13.4-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 1         | 0.47%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch     | 1         | 0.47%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch     | 1         | 0.47%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 520x290mm 23.4-inch     | 1         | 0.47%   |
| Samsung Electronics LU28R55 SAM1015 3840x2160 632x360mm 28.6-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4193 2880x1800 302x189mm 14.0-inch | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 89        | 44.06%  |
| 3840x2160 (4K)     | 21        | 10.4%   |
| 1366x768 (WXGA)    | 16        | 7.92%   |
| 2880x1800          | 15        | 7.43%   |
| 2560x1440 (QHD)    | 14        | 6.93%   |
| 1920x1200 (WUXGA)  | 12        | 5.94%   |
| 2560x1600          | 11        | 5.45%   |
| 2256x1504          | 6         | 2.97%   |
| 1600x900 (HD+)     | 4         | 1.98%   |
| 3840x2400          | 2         | 0.99%   |
| 3440x1440          | 2         | 0.99%   |
| 3200x2000          | 2         | 0.99%   |
| 3840x1200          | 1         | 0.5%    |
| 2240x1400          | 1         | 0.5%    |
| 2160x1440          | 1         | 0.5%    |
| 1920x1280          | 1         | 0.5%    |
| 1680x1050 (WSXGA+) | 1         | 0.5%    |
| 1280x800 (WXGA)    | 1         | 0.5%    |
| 1280x1024 (SXGA)   | 1         | 0.5%    |
| 1024x600           | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 58        | 27.75%  |
| 14     | 39        | 18.66%  |
| 13     | 37        | 17.7%   |
| 27     | 15        | 7.18%   |
| 16     | 13        | 6.22%   |
| 17     | 10        | 4.78%   |
| 12     | 9         | 4.31%   |
| 24     | 8         | 3.83%   |
| 31     | 3         | 1.44%   |
| 23     | 3         | 1.44%   |
| 21     | 3         | 1.44%   |
| 34     | 2         | 0.96%   |
| 25     | 2         | 0.96%   |
| 86     | 1         | 0.48%   |
| 46     | 1         | 0.48%   |
| 43     | 1         | 0.48%   |
| 28     | 1         | 0.48%   |
| 22     | 1         | 0.48%   |
| 20     | 1         | 0.48%   |
| 10     | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 124       | 59.62%  |
| 201-300     | 32        | 15.38%  |
| 501-600     | 24        | 11.54%  |
| 351-400     | 10        | 4.81%   |
| 601-700     | 8         | 3.85%   |
| 401-500     | 5         | 2.4%    |
| 1001-1500   | 3         | 1.44%   |
| 701-800     | 2         | 0.96%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 123       | 67.58%  |
| 16/10 | 46        | 25.27%  |
| 3/2   | 8         | 4.4%    |
| 21/9  | 2         | 1.1%    |
| 5/4   | 1         | 0.55%   |
| 3.20  | 1         | 0.55%   |
| 0.56  | 1         | 0.55%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 63        | 30.14%  |
| 101-110        | 58        | 27.75%  |
| 301-350        | 15        | 7.18%   |
| 71-80          | 13        | 6.22%   |
| 111-120        | 12        | 5.74%   |
| 201-250        | 11        | 5.26%   |
| 61-70          | 9         | 4.31%   |
| 121-130        | 9         | 4.31%   |
| 351-500        | 6         | 2.87%   |
| 251-300        | 4         | 1.91%   |
| 151-200        | 3         | 1.44%   |
| 501-1000       | 2         | 0.96%   |
| More than 1000 | 1         | 0.48%   |
| 41-50          | 1         | 0.48%   |
| 141-150        | 1         | 0.48%   |
| 131-140        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 87        | 43.72%  |
| 161-240       | 51        | 25.63%  |
| 101-120       | 23        | 11.56%  |
| More than 240 | 18        | 9.05%   |
| 51-100        | 18        | 9.05%   |
| 1-50          | 2         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 135       | 74.18%  |
| 2     | 34        | 18.68%  |
| 0     | 7         | 3.85%   |
| 3     | 6         | 3.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 120       | 45.45%  |
| Realtek Semiconductor             | 77        | 29.17%  |
| MediaTek                          | 19        | 7.2%    |
| Qualcomm Atheros                  | 15        | 5.68%   |
| Broadcom                          | 10        | 3.79%   |
| Qualcomm                          | 5         | 1.89%   |
| Lenovo                            | 4         | 1.52%   |
| Marvell Technology Group          | 2         | 0.76%   |
| Xiaomi                            | 1         | 0.38%   |
| TP-Link                           | 1         | 0.38%   |
| STMicroelectronics                | 1         | 0.38%   |
| Qualcomm Atheros Communications   | 1         | 0.38%   |
| QinHeng Electronics               | 1         | 0.38%   |
| Microsoft                         | 1         | 0.38%   |
| ICS Advent                        | 1         | 0.38%   |
| Fibocom                           | 1         | 0.38%   |
| Ericsson Business Mobile Networks | 1         | 0.38%   |
| Edimax Technology                 | 1         | 0.38%   |
| D-Link                            | 1         | 0.38%   |
| Broadcom Limited                  | 1         | 0.38%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 45        | 14.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 7.01%   |
| Intel Wi-Fi 6 AX200                                                    | 16        | 5.1%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 11        | 3.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 11        | 3.5%    |
| Intel Wireless 8265 / 8275                                             | 10        | 3.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 7         | 2.23%   |
| Intel Wireless 8260                                                    | 7         | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 7         | 2.23%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 1.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 6         | 1.91%   |
| Intel Wi-Fi 6 AX201                                                    | 6         | 1.91%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 6         | 1.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 1.59%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.59%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 1.59%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 5         | 1.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 4         | 1.27%   |
| Intel Wireless 7265                                                    | 4         | 1.27%   |
| Intel Wireless 7260                                                    | 4         | 1.27%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 4         | 1.27%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 4         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 1.27%   |
| Qualcomm QCNFA765 Wireless Network Adapter                             | 3         | 0.96%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 3         | 0.96%   |
| Intel Wireless 3165                                                    | 3         | 0.96%   |
| Intel Wireless 3160                                                    | 3         | 0.96%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 3         | 0.96%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 3         | 0.96%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter           | 3         | 0.96%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 2         | 0.64%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 2         | 0.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 2         | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 120       | 65.93%  |
| MediaTek                          | 19        | 10.44%  |
| Qualcomm Atheros                  | 13        | 7.14%   |
| Broadcom                          | 10        | 5.49%   |
| Realtek Semiconductor             | 8         | 4.4%    |
| Qualcomm                          | 4         | 2.2%    |
| TP-Link                           | 1         | 0.55%   |
| Qualcomm Atheros Communications   | 1         | 0.55%   |
| Microsoft                         | 1         | 0.55%   |
| Fibocom                           | 1         | 0.55%   |
| Ericsson Business Mobile Networks | 1         | 0.55%   |
| Edimax Technology                 | 1         | 0.55%   |
| D-Link                            | 1         | 0.55%   |
| Broadcom Limited                  | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                                   | 16        | 8.79%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                             | 11        | 6.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 11        | 6.04%   |
| Intel Wireless 8265 / 8275                                                            | 10        | 5.49%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                         | 7         | 3.85%   |
| Intel Wireless 8260                                                                   | 7         | 3.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 7         | 3.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 6         | 3.3%    |
| Intel Wi-Fi 6 AX201                                                                   | 6         | 3.3%    |
| Intel Raptor Lake PCH CNVi WiFi                                                       | 6         | 3.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 5         | 2.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 5         | 2.75%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                           | 5         | 2.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                               | 4         | 2.2%    |
| Intel Wireless 7265                                                                   | 4         | 2.2%    |
| Intel Wireless 7260                                                                   | 4         | 2.2%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                               | 4         | 2.2%    |
| Intel Tiger Lake PCH CNVi WiFi                                                        | 4         | 2.2%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 4         | 2.2%    |
| Qualcomm QCNFA765 Wireless Network Adapter                                            | 3         | 1.65%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                                     | 3         | 1.65%   |
| Intel Wireless 3165                                                                   | 3         | 1.65%   |
| Intel Wireless 3160                                                                   | 3         | 1.65%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                                     | 3         | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 3         | 1.65%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                          | 3         | 1.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                           | 2         | 1.1%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 2         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 2         | 1.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 2         | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 2         | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 2         | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 2         | 1.1%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                           | 1         | 0.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 1         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                   | 1         | 0.55%   |
| Qualcomm QCA6390 Wireless Network Adapter                                             | 1         | 0.55%   |
| Qualcomm Atheros AR9271 802.11n                                                       | 1         | 0.55%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 1         | 0.55%   |
| Microsoft Xbox 360 Wireless Adapter                                                   | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 70        | 57.85%  |
| Intel                    | 37        | 30.58%  |
| Lenovo                   | 4         | 3.31%   |
| Qualcomm Atheros         | 3         | 2.48%   |
| Marvell Technology Group | 2         | 1.65%   |
| Broadcom                 | 2         | 1.65%   |
| Xiaomi                   | 1         | 0.83%   |
| Qualcomm                 | 1         | 0.83%   |
| ICS Advent               | 1         | 0.83%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 45        | 34.62%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 22        | 16.92%  |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 4.62%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 3.85%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 3.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 3.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 3.08%   |
| Intel Ethernet Connection I217-LM                                      | 3         | 2.31%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 2.31%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 2         | 1.54%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                       | 2         | 1.54%   |
| Intel Ethernet Connection (7) I219-LM                                  | 2         | 1.54%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 1.54%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 1.54%   |
| Intel Ethernet Connection (2) I219-LM                                  | 2         | 1.54%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 1.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.77%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.77%   |
| Qualcomm Redmi 9T                                                      | 1         | 0.77%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.77%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 1         | 0.77%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.77%   |
| Lenovo USB-C Dock Ethernet                                             | 1         | 0.77%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 1         | 0.77%   |
| Intel I210 Gigabit Network Connection                                  | 1         | 0.77%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.77%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.77%   |
| Intel Ethernet Connection (2) I219-V                                   | 1         | 0.77%   |
| Intel Ethernet Connection (16) I219-V                                  | 1         | 0.77%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.77%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 0.77%   |
| ICS Advent USB 10/100 LAN                                              | 1         | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1         | 0.77%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                      | 1         | 0.77%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 174       | 59.39%  |
| Ethernet | 117       | 39.93%  |
| Modem    | 2         | 0.68%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 164       | 85.42%  |
| Ethernet | 28        | 14.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 95        | 54.29%  |
| 1     | 76        | 43.43%  |
| 3     | 4         | 2.29%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 131       | 74.01%  |
| Yes  | 46        | 25.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 110       | 65.87%  |
| Foxconn / Hon Hai               | 11        | 6.59%   |
| Apple                           | 10        | 5.99%   |
| IMC Networks                    | 8         | 4.79%   |
| Realtek Semiconductor           | 5         | 2.99%   |
| Qualcomm Atheros Communications | 5         | 2.99%   |
| MediaTek                        | 4         | 2.4%    |
| Broadcom                        | 4         | 2.4%    |
| Lite-On Technology              | 3         | 1.8%    |
| USI                             | 2         | 1.2%    |
| Realtek                         | 1         | 0.6%    |
| Opticis                         | 1         | 0.6%    |
| Integrated System Solution      | 1         | 0.6%    |
| ASUSTek Computer                | 1         | 0.6%    |
| Alps Electric                   | 1         | 0.6%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface             | 28        | 16.77%  |
| Intel Bluetooth Device                         | 20        | 11.98%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 17        | 10.18%  |
| Intel AX200 Bluetooth                          | 16        | 9.58%   |
| Intel AX210 Bluetooth                          | 11        | 6.59%   |
| Intel AX201 Bluetooth                          | 11        | 6.59%   |
| Foxconn / Hon Hai Wireless_Device              | 9         | 5.39%   |
| Apple Bluetooth Host Controller                | 8         | 4.79%   |
| IMC Networks Wireless_Device                   | 6         | 3.59%   |
| Realtek Bluetooth Radio                        | 4         | 2.4%    |
| MediaTek Wireless_Device                       | 4         | 2.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter       | 4         | 2.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth     | 3         | 1.8%    |
| USI Bluetooth Device                           | 2         | 1.2%    |
| Qualcomm Atheros  Bluetooth Device             | 2         | 1.2%    |
| Intel Wireless-AC 3168 Bluetooth               | 2         | 1.2%    |
| Foxconn / Hon Hai Bluetooth Device             | 2         | 1.2%    |
| Broadcom HP Portable SoftSailing               | 2         | 1.2%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter        | 1         | 0.6%    |
| Realtek Bluetooth Radio                        | 1         | 0.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0         | 1         | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth              | 1         | 0.6%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0          | 1         | 0.6%    |
| Opticis Bluetooth Radio                        | 1         | 0.6%    |
| Intel Centrino Bluetooth Wireless Transceiver  | 1         | 0.6%    |
| Integrated System Solution Bluetooth Device    | 1         | 0.6%    |
| IMC Networks Bluetooth Device                  | 1         | 0.6%    |
| IMC Networks BCM20702A0                        | 1         | 0.6%    |
| Broadcom BCM20702A0                            | 1         | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 0.6%    |
| ASUS Broadcom Bluetooth 2.1                    | 1         | 0.6%    |
| Apple Bluetooth USB Host Controller            | 1         | 0.6%    |
| Apple Bluetooth HCI                            | 1         | 0.6%    |
| Alps Electric BCM2046 Bluetooth Device         | 1         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 129       | 52.44%  |
| AMD                       | 52        | 21.14%  |
| Nvidia                    | 33        | 13.41%  |
| Lenovo                    | 6         | 2.44%   |
| C-Media Electronics       | 4         | 1.63%   |
| Realtek Semiconductor     | 3         | 1.22%   |
| Synaptics                 | 2         | 0.81%   |
| Focusrite-Novation        | 2         | 0.81%   |
| Trust                     | 1         | 0.41%   |
| Sony                      | 1         | 0.41%   |
| Sennheiser Communications | 1         | 0.41%   |
| Satechi                   | 1         | 0.41%   |
| Razer USA                 | 1         | 0.41%   |
| Logitech                  | 1         | 0.41%   |
| Kingston Technology       | 1         | 0.41%   |
| JMTek                     | 1         | 0.41%   |
| Hewlett-Packard           | 1         | 0.41%   |
| Goldvish                  | 1         | 0.41%   |
| GN Netcom                 | 1         | 0.41%   |
| Creative Technology       | 1         | 0.41%   |
| Corsair                   | 1         | 0.41%   |
| AudioQuest                | 1         | 0.41%   |
| (LCS) USB Audio Device    | 1         | 0.41%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                  | 46        | 14.89%  |
| AMD Renoir Radeon High Definition Audio Controller                      | 26        | 8.41%   |
| Intel Sunrise Point-LP HD Audio                                         | 23        | 7.44%   |
| AMD Rembrandt Radeon High Definition Audio Controller                   | 14        | 4.53%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                 | 13        | 4.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller     | 13        | 4.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller             | 12        | 3.88%   |
| Intel Cannon Lake PCH cAVS                                              | 10        | 3.24%   |
| Nvidia Audio device                                                     | 9         | 2.91%   |
| Intel Raptor Lake-P/U/H cAVS                                            | 7         | 2.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                  | 7         | 2.27%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller     | 7         | 2.27%   |
| Nvidia GP107GL High Definition Audio Controller                         | 5         | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller        | 5         | 1.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                 | 4         | 1.29%   |
| Intel Tiger Lake-H HD Audio Controller                                  | 4         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                   | 4         | 1.29%   |
| Intel Comet Lake PCH-LP cAVS                                            | 4         | 1.29%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio            | 4         | 1.29%   |
| Intel Broadwell-U Audio Controller                                      | 4         | 1.29%   |
| Intel 8 Series HD Audio Controller                                      | 4         | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller         | 4         | 1.29%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series] | 4         | 1.29%   |
| Realtek Semiconductor USB Audio                                         | 3         | 0.97%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]           | 3         | 0.97%   |
| Nvidia GK107 HDMI Audio Controller                                      | 3         | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                           | 3         | 0.97%   |
| Nvidia GA104 High Definition Audio Controller                           | 3         | 0.97%   |
| Intel Raptor Lake High Definition Audio Controller                      | 3         | 0.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                     | 3         | 0.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                 | 3         | 0.97%   |
| Synaptics CX31993 384Khz HIFI AUDIO                                     | 2         | 0.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller          | 2         | 0.65%   |
| Nvidia GK106 HDMI Audio Controller                                      | 2         | 0.65%   |
| Lenovo ThinkPad Dock Audio                                              | 2         | 0.65%   |
| Intel Crystal Well HD Audio Controller                                  | 2         | 0.65%   |
| Intel CM238 HD Audio Controller                                         | 2         | 0.65%   |
| Trust USB microphone                                                    | 1         | 0.32%   |
| Sony DualSense wireless controller (PS5)                                | 1         | 0.32%   |
| Sennheiser Communications Headset [PC 8]                                | 1         | 0.32%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 54        | 25.84%  |
| SK hynix                     | 45        | 21.53%  |
| Micron Technology            | 39        | 18.66%  |
| Kingston                     | 16        | 7.66%   |
| Crucial                      | 16        | 7.66%   |
| Unknown                      | 7         | 3.35%   |
| Unknown                      | 7         | 3.35%   |
| Team                         | 4         | 1.91%   |
| Ramaxel Technology           | 4         | 1.91%   |
| Unknown (ABCD)               | 3         | 1.44%   |
| Lexar                        | 2         | 0.96%   |
| Avant                        | 2         | 0.96%   |
| A-DATA Technology            | 2         | 0.96%   |
| Smart Brazil                 | 1         | 0.48%   |
| Patriot Memory (PDP Systems) | 1         | 0.48%   |
| Patriot                      | 1         | 0.48%   |
| GOODRAM                      | 1         | 0.48%   |
| G.Skill                      | 1         | 0.48%   |
| Corsair                      | 1         | 0.48%   |
| Apacer                       | 1         | 0.48%   |
| AMD                          | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 7         | 3.18%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                        | 6         | 2.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 2.27%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 4         | 1.82%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 1.36%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.36%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 3         | 1.36%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 1.36%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s             | 3         | 1.36%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s                | 2         | 0.91%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 2         | 0.91%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.91%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s          | 2         | 0.91%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s    | 2         | 0.91%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.91%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s              | 2         | 0.91%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 2         | 0.91%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 2         | 0.91%   |
| Samsung RAM K3LKCKC@BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s        | 2         | 0.91%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s           | 2         | 0.91%   |
| Micron RAM MT62F1G32D4DR-031 4GB SODIMM LPDDR5 5500MT/s             | 2         | 0.91%   |
| Micron RAM Module 8GB SODIMM DDR3 1600MT/s                          | 2         | 0.91%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.91%   |
| Micron RAM 53E2G32D4NQ-046 4096MB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.91%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 2         | 0.91%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.91%   |
| Micron RAM 16KTF2G64HZ-1G6A1 16GB SODIMM DDR3 1600MT/s              | 2         | 0.91%   |
| Crucial RAM CT32G4SFD832A.M16FF 32GB SODIMM DDR4 3200MT/s           | 2         | 0.91%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                         | 1         | 0.45%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 1         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR2                                  | 1         | 0.45%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.45%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 1         | 0.45%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                 | 1         | 0.45%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 1         | 0.45%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s               | 1         | 0.45%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 1         | 0.45%   |
| SK hynix RAM Module 8GB SODIMM DDR5 5600MT/s                        | 1         | 0.45%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 1         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 87        | 50.29%  |
| DDR3   | 29        | 16.76%  |
| LPDDR5 | 21        | 12.14%  |
| LPDDR4 | 14        | 8.09%   |
| DDR5   | 12        | 6.94%   |
| LPDDR3 | 7         | 4.05%   |
| DDR2   | 2         | 1.16%   |
| SDRAM  | 1         | 0.58%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 139       | 77.65%  |
| Row Of Chips | 35        | 19.55%  |
| Chip         | 3         | 1.68%   |
| DIMM         | 1         | 0.56%   |
| Unknown      | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 85        | 44.04%  |
| 16384 | 42        | 21.76%  |
| 4096  | 39        | 20.21%  |
| 32768 | 20        | 10.36%  |
| 2048  | 6         | 3.11%   |
| 1024  | 1         | 0.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 44        | 23.66%  |
| 2667    | 34        | 18.28%  |
| 1600    | 27        | 14.52%  |
| 6400    | 17        | 9.14%   |
| 2133    | 14        | 7.53%   |
| 2400    | 12        | 6.45%   |
| 4267    | 7         | 3.76%   |
| 4800    | 6         | 3.23%   |
| 5600    | 5         | 2.69%   |
| 4266    | 4         | 2.15%   |
| 3266    | 4         | 2.15%   |
| 5500    | 2         | 1.08%   |
| 1867    | 2         | 1.08%   |
| Unknown | 2         | 1.08%   |
| 7500    | 1         | 0.54%   |
| 7467    | 1         | 0.54%   |
| 5200    | 1         | 0.54%   |
| 1334    | 1         | 0.54%   |
| 1333    | 1         | 0.54%   |
| 667     | 1         | 0.54%   |

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
| Chicony Electronics                    | 38        | 24.68%  |
| IMC Networks                           | 20        | 12.99%  |
| Microdia                               | 18        | 11.69%  |
| Bison Electronics                      | 15        | 9.74%   |
| Realtek Semiconductor                  | 11        | 7.14%   |
| Sunplus Innovation Technology          | 8         | 5.19%   |
| Logitech                               | 6         | 3.9%    |
| Acer                                   | 5         | 3.25%   |
| Syntek                                 | 4         | 2.6%    |
| ShineTech                              | 4         | 2.6%    |
| Quanta                                 | 3         | 1.95%   |
| Luxvisions Innotech Limited            | 3         | 1.95%   |
| Lite-On Technology                     | 3         | 1.95%   |
| Sonix Technology                       | 2         | 1.3%    |
| Primax Electronics                     | 2         | 1.3%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.3%    |
| Apple                                  | 2         | 1.3%    |
| Alcor Micro                            | 2         | 1.3%    |
| Z-Star Microelectronics                | 1         | 0.65%   |
| webcamvendor                           | 1         | 0.65%   |
| Silicon Motion                         | 1         | 0.65%   |
| Samsung Electronics                    | 1         | 0.65%   |
| Ricoh                                  | 1         | 0.65%   |
| globaloptics                           | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                | 20        | 12.9%   |
| Microdia Integrated_Webcam_HD                            | 11        | 7.1%    |
| IMC Networks Integrated Camera                           | 10        | 6.45%   |
| Chicony HP HD Camera                                     | 7         | 4.52%   |
| IMC Networks USB2.0 HD UVC WebCam                        | 6         | 3.87%   |
| Bison Integrated Camera                                  | 6         | 3.87%   |
| Syntek Integrated Camera                                 | 4         | 2.58%   |
| Realtek Laptop Camera                                    | 4         | 2.58%   |
| Logitech HD Pro Webcam C920                              | 4         | 2.58%   |
| Sunplus Integrated_Webcam_FHD                            | 3         | 1.94%   |
| ShineTech USB2.0 HD UVC WebCam                           | 3         | 1.94%   |
| Realtek Integrated_Webcam_HD                             | 3         | 1.94%   |
| Sunplus Integrated_Webcam_HD                             | 2         | 1.29%   |
| Primax HP HD Webcam [Fixed]                              | 2         | 1.29%   |
| Microdia Webcam Vitade AF                                | 2         | 1.29%   |
| Microdia Integrated Webcam                               | 2         | 1.29%   |
| Luxvisions Innotech Limited Integrated Camera            | 2         | 1.29%   |
| Lite-On Integrated Camera                                | 2         | 1.29%   |
| Chicony HP 5MP Camera                                    | 2         | 1.29%   |
| Bison HD Webcam                                          | 2         | 1.29%   |
| Bison BisonCam,NB Pro                                    | 2         | 1.29%   |
| Alcor Micro USB 2.0 Camera                               | 2         | 1.29%   |
| Acer Integrated Camera                                   | 2         | 1.29%   |
| Z-Star Venus USB2.0 Camera                               | 1         | 0.65%   |
| webcamvendor webcamproduct                               | 1         | 0.65%   |
| Sunplus XiaoMi WebCam                                    | 1         | 0.65%   |
| Sunplus XiaoMi USB 2.0 Webcam                            | 1         | 0.65%   |
| Sunplus Laptop Integrated Webcam FHD                     | 1         | 0.65%   |
| Sonix USB2.0 HD UVC WebCam                               | 1         | 0.65%   |
| Sonix USB2.0 FHD UVC WebCam                              | 1         | 0.65%   |
| Silicon Motion WebCam SC-13HDL11431N                     | 1         | 0.65%   |
| Shinetech USB2.0 FHD UVC WebCam                          | 1         | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)                  | 1         | 0.65%   |
| Ricoh Sony Visual Communication Camera Integrated Webcam | 1         | 0.65%   |
| Realtek TV Camera                                        | 1         | 0.65%   |
| Realtek Thronmax Webcam Mic                              | 1         | 0.65%   |
| Realtek Lenovo EasyCamera                                | 1         | 0.65%   |
| Realtek Integrated Webcam                                | 1         | 0.65%   |
| Realtek HD WebCam                                        | 1         | 0.65%   |
| Quanta VGA WebCam                                        | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 19        | 44.19%  |
| Validity Sensors           | 15        | 34.88%  |
| Shenzhen Goodix Technology | 8         | 18.6%   |
| Focal-systems.Corp         | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 18.6%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 11.63%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 6.98%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 6.98%   |
| Synaptics UWP WBDI Device                                                  | 3         | 6.98%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 6.98%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 6.98%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 6.98%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 2         | 4.65%   |
| Validity Sensors VFS491                                                    | 2         | 4.65%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 2.33%   |
| Synaptics UWP WBDI                                                         | 1         | 2.33%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 21        | 70%     |
| Broadcom    | 5         | 16.67%  |
| Yubico.com  | 3         | 10%     |
| Upek        | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 21        | 70%     |
| Yubico.com Yubikey 4/5 U2F+CCID                            | 2         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 6.67%   |
| Broadcom 5880                                              | 2         | 6.67%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                        | 1         | 3.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 3.33%   |
| Broadcom 58200                                             | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 87        | 47.8%   |
| 1     | 62        | 34.07%  |
| 2     | 29        | 15.93%  |
| 4     | 2         | 1.1%    |
| 3     | 2         | 1.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 31.78%  |
| Multimedia controller    | 26        | 20.16%  |
| Chipcard                 | 25        | 19.38%  |
| Graphics card            | 17        | 13.18%  |
| Net/wireless             | 6         | 4.65%   |
| Camera                   | 4         | 3.1%    |
| Bluetooth                | 3         | 2.33%   |
| Modem                    | 2         | 1.55%   |
| Card reader              | 2         | 1.55%   |
| Network                  | 1         | 0.78%   |
| Firewire controller      | 1         | 0.78%   |
| Communication controller | 1         | 0.78%   |

