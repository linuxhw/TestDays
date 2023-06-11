OpenMandriva - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva/Desktop/README.md) and [notebooks](/Dist/OpenMandriva/Notebook/README.md).

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

Total: 14311

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Nitro AN515-44              | Notebook    | [c74a9048c0](https://linux-hardware.org/?probe=c74a9048c0) | Jun 10, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [98a4edb43d](https://linux-hardware.org/?probe=98a4edb43d) | Jun 10, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [d592b19e9b](https://linux-hardware.org/?probe=d592b19e9b) | Jun 10, 2023 |
| HP            | 339A                        | Desktop     | [348ce53f71](https://linux-hardware.org/?probe=348ce53f71) | Jun 10, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [532d86f9e6](https://linux-hardware.org/?probe=532d86f9e6) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [03660fb140](https://linux-hardware.org/?probe=03660fb140) | Jun 10, 2023 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [2e46385299](https://linux-hardware.org/?probe=2e46385299) | Jun 10, 2023 |
| Gigabyte      | B560M H                     | Desktop     | [fadb7a6aa8](https://linux-hardware.org/?probe=fadb7a6aa8) | Jun 10, 2023 |
| Dell          | 0D883F A06                  | Desktop     | [f0d5120461](https://linux-hardware.org/?probe=f0d5120461) | Jun 10, 2023 |
| HP            | G42                         | Notebook    | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | Notebook    | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| Dell          | Latitude 3580               | Notebook    | [9c02d2c4c4](https://linux-hardware.org/?probe=9c02d2c4c4) | Jun 10, 2023 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [eea1c44d94](https://linux-hardware.org/?probe=eea1c44d94) | Jun 10, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [d7c1b01b69](https://linux-hardware.org/?probe=d7c1b01b69) | Jun 10, 2023 |
| Medion        | Akoya E7226                 | Notebook    | [b46a96183b](https://linux-hardware.org/?probe=b46a96183b) | Jun 10, 2023 |
| Acer          | Predator G3600              | Desktop     | [02a0cf3a71](https://linux-hardware.org/?probe=02a0cf3a71) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [68a77b486e](https://linux-hardware.org/?probe=68a77b486e) | Jun 09, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [a2bd4ab5b9](https://linux-hardware.org/?probe=a2bd4ab5b9) | Jun 09, 2023 |
| MSI           | 970A-G46                    | Desktop     | [e4471b7a38](https://linux-hardware.org/?probe=e4471b7a38) | Jun 09, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [3fb94f0c4b](https://linux-hardware.org/?probe=3fb94f0c4b) | Jun 09, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [8a9223ce9f](https://linux-hardware.org/?probe=8a9223ce9f) | Jun 09, 2023 |
| HP            | 09E0h                       | Desktop     | [b6bb01441c](https://linux-hardware.org/?probe=b6bb01441c) | Jun 09, 2023 |
| Toshiba       | Satellite L635              | Notebook    | [4f124d1525](https://linux-hardware.org/?probe=4f124d1525) | Jun 09, 2023 |
| Toshiba       | PORTEGE R705                | Notebook    | [c7a032c5cf](https://linux-hardware.org/?probe=c7a032c5cf) | Jun 09, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [f0bad84fca](https://linux-hardware.org/?probe=f0bad84fca) | Jun 08, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [dcd4a1ad41](https://linux-hardware.org/?probe=dcd4a1ad41) | Jun 08, 2023 |
| Lenovo        | ThinkPad L430 24655Q7       | Notebook    | [7b45c0777e](https://linux-hardware.org/?probe=7b45c0777e) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [eea4cea0e0](https://linux-hardware.org/?probe=eea4cea0e0) | Jun 08, 2023 |
| HP            | 87A4 10100                  | All in one  | [3c67e34a5e](https://linux-hardware.org/?probe=3c67e34a5e) | Jun 08, 2023 |
| Biostar       | H610MH                      | Desktop     | [2cd4e157d4](https://linux-hardware.org/?probe=2cd4e157d4) | Jun 08, 2023 |
| GuoGuang      | IC2M1028V-J                 | Desktop     | [04527d6ad9](https://linux-hardware.org/?probe=04527d6ad9) | Jun 08, 2023 |
| Lenovo        | ThinkPad L420 7829W1R       | Notebook    | [25d96d98f8](https://linux-hardware.org/?probe=25d96d98f8) | Jun 08, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [fd037bb738](https://linux-hardware.org/?probe=fd037bb738) | Jun 08, 2023 |
| AMI           | Cherry Trail CR             | Desktop     | [5816e6a1cf](https://linux-hardware.org/?probe=5816e6a1cf) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| HP            | 1905                        | Desktop     | [0617f4e698](https://linux-hardware.org/?probe=0617f4e698) | Jun 07, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [369f5d3044](https://linux-hardware.org/?probe=369f5d3044) | Jun 07, 2023 |
| HP            | 8169                        | Desktop     | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| Kraftway      | KWH510                      | Desktop     | [3a5ccb373b](https://linux-hardware.org/?probe=3a5ccb373b) | Jun 07, 2023 |
| HP            | 2B34                        | Desktop     | [d0b5c9767f](https://linux-hardware.org/?probe=d0b5c9767f) | Jun 07, 2023 |
| MSI           | GS63VR 6RF                  | Notebook    | [4bc33968d1](https://linux-hardware.org/?probe=4bc33968d1) | Jun 06, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [8f55e469c8](https://linux-hardware.org/?probe=8f55e469c8) | Jun 06, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [92d0de412b](https://linux-hardware.org/?probe=92d0de412b) | Jun 06, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [bdea2092aa](https://linux-hardware.org/?probe=bdea2092aa) | Jun 06, 2023 |
| HP            | 822A                        | Desktop     | [8cf8694f03](https://linux-hardware.org/?probe=8cf8694f03) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [4c3091f9ff](https://linux-hardware.org/?probe=4c3091f9ff) | Jun 06, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [624a84a2fc](https://linux-hardware.org/?probe=624a84a2fc) | Jun 06, 2023 |
| Intel         | E5 V1.0                     | Desktop     | [077c08c2dc](https://linux-hardware.org/?probe=077c08c2dc) | Jun 06, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [05a473a2be](https://linux-hardware.org/?probe=05a473a2be) | Jun 06, 2023 |
| Acer          | EQ45LM                      | Desktop     | [73f7a3078f](https://linux-hardware.org/?probe=73f7a3078f) | Jun 06, 2023 |
| Acer          | WMCP78M                     | Desktop     | [a7a466de8a](https://linux-hardware.org/?probe=a7a466de8a) | Jun 06, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [85ec51dbf3](https://linux-hardware.org/?probe=85ec51dbf3) | Jun 05, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [a1bcda2245](https://linux-hardware.org/?probe=a1bcda2245) | Jun 05, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| HP            | 8265                        | Desktop     | [7afc259b97](https://linux-hardware.org/?probe=7afc259b97) | Jun 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [44cf28ec0e](https://linux-hardware.org/?probe=44cf28ec0e) | Jun 05, 2023 |
| MSI           | H110M ECO                   | Desktop     | [4215fc5993](https://linux-hardware.org/?probe=4215fc5993) | Jun 05, 2023 |
| HP            | Pavilion g4                 | Notebook    | [af0c33de44](https://linux-hardware.org/?probe=af0c33de44) | Jun 05, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4895fe7746](https://linux-hardware.org/?probe=4895fe7746) | Jun 05, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [a0430d6f0c](https://linux-hardware.org/?probe=a0430d6f0c) | Jun 05, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [933aa24820](https://linux-hardware.org/?probe=933aa24820) | Jun 05, 2023 |
| Dell          | Latitude E4300              | Notebook    | [cfd95b7e5e](https://linux-hardware.org/?probe=cfd95b7e5e) | Jun 05, 2023 |
| ASUSTek       | VX7SX                       | Notebook    | [ddf3010e73](https://linux-hardware.org/?probe=ddf3010e73) | Jun 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [83982c1aa9](https://linux-hardware.org/?probe=83982c1aa9) | Jun 05, 2023 |
| AMD           | A88                         | Desktop     | [a7f64b7e4b](https://linux-hardware.org/?probe=a7f64b7e4b) | Jun 05, 2023 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [72702690e5](https://linux-hardware.org/?probe=72702690e5) | Jun 05, 2023 |
| Intel         | DE3815TYKH H26998-402       | Desktop     | [d2f97c16e9](https://linux-hardware.org/?probe=d2f97c16e9) | Jun 05, 2023 |
| ASUSTek       | K95VJ                       | Notebook    | [9bbcec82c6](https://linux-hardware.org/?probe=9bbcec82c6) | Jun 05, 2023 |
| NEC Comput... | MS-AD611                    | All in one  | [219795e31d](https://linux-hardware.org/?probe=219795e31d) | Jun 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [48d99dbec6](https://linux-hardware.org/?probe=48d99dbec6) | Jun 05, 2023 |
| ASRock        | B150M Pro4                  | Desktop     | [0b59eacbd3](https://linux-hardware.org/?probe=0b59eacbd3) | Jun 05, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [de1d4d9d23](https://linux-hardware.org/?probe=de1d4d9d23) | Jun 05, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [d275c3c00b](https://linux-hardware.org/?probe=d275c3c00b) | Jun 05, 2023 |
| HP            | 1850                        | Desktop     | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [697cc43136](https://linux-hardware.org/?probe=697cc43136) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3af6e03b1c](https://linux-hardware.org/?probe=3af6e03b1c) | Jun 04, 2023 |
| Acer          | AO722                       | Notebook    | [b8f2636f02](https://linux-hardware.org/?probe=b8f2636f02) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [525601c31e](https://linux-hardware.org/?probe=525601c31e) | Jun 04, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [0564fd483d](https://linux-hardware.org/?probe=0564fd483d) | Jun 04, 2023 |
| HP            | 1495                        | Desktop     | [0cbf6bee1f](https://linux-hardware.org/?probe=0cbf6bee1f) | Jun 04, 2023 |
| Acer          | Veriton X4630G V:1.0        | Desktop     | [5106e40f32](https://linux-hardware.org/?probe=5106e40f32) | Jun 04, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8b14da5cf8](https://linux-hardware.org/?probe=8b14da5cf8) | Jun 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [70e5950511](https://linux-hardware.org/?probe=70e5950511) | Jun 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [514b3788ed](https://linux-hardware.org/?probe=514b3788ed) | Jun 04, 2023 |
| MSI           | Boston                      | Desktop     | [95b4d5183d](https://linux-hardware.org/?probe=95b4d5183d) | Jun 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [681baff23c](https://linux-hardware.org/?probe=681baff23c) | Jun 04, 2023 |
| Foxconn       | G41MD                       | Desktop     | [f988a585c9](https://linux-hardware.org/?probe=f988a585c9) | Jun 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [094889a0e2](https://linux-hardware.org/?probe=094889a0e2) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [5d6b08920f](https://linux-hardware.org/?probe=5d6b08920f) | Jun 03, 2023 |
| ECS           | G31T-M                      | Desktop     | [55d38b75c7](https://linux-hardware.org/?probe=55d38b75c7) | Jun 03, 2023 |
| Compaq        | 420                         | Notebook    | [cf7a8f5641](https://linux-hardware.org/?probe=cf7a8f5641) | Jun 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [3aa6cf6780](https://linux-hardware.org/?probe=3aa6cf6780) | Jun 03, 2023 |
| ASUSTek       | PRIME A520M-A               | Desktop     | [7dac003c12](https://linux-hardware.org/?probe=7dac003c12) | Jun 03, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [7f95f275b3](https://linux-hardware.org/?probe=7f95f275b3) | Jun 03, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [79e14478a3](https://linux-hardware.org/?probe=79e14478a3) | Jun 03, 2023 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [1034aea990](https://linux-hardware.org/?probe=1034aea990) | Jun 03, 2023 |
| Positivo      | POS-PIG41BA                 | Desktop     | [f630c0b9cd](https://linux-hardware.org/?probe=f630c0b9cd) | Jun 03, 2023 |
| Lenovo        | ThinkPad L490 20Q5002DMH    | Notebook    | [6d42b7647b](https://linux-hardware.org/?probe=6d42b7647b) | Jun 02, 2023 |
| Dell          | 0GX832 A01                  | Desktop     | [19b718a96c](https://linux-hardware.org/?probe=19b718a96c) | Jun 02, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [647589cbbd](https://linux-hardware.org/?probe=647589cbbd) | Jun 02, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [70a097a219](https://linux-hardware.org/?probe=70a097a219) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1b82c0c3c8](https://linux-hardware.org/?probe=1b82c0c3c8) | Jun 02, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [7b5291c6f8](https://linux-hardware.org/?probe=7b5291c6f8) | Jun 02, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [589bd2e1f8](https://linux-hardware.org/?probe=589bd2e1f8) | Jun 01, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f22933cdb1](https://linux-hardware.org/?probe=f22933cdb1) | Jun 01, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [75c4e47bea](https://linux-hardware.org/?probe=75c4e47bea) | Jun 01, 2023 |
| Teclast       | X4                          | Tablet      | [2392aa748a](https://linux-hardware.org/?probe=2392aa748a) | Jun 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e242ec473b](https://linux-hardware.org/?probe=e242ec473b) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Fujitsu Si... | D2740-A2 S26361-D2740-A2    | Desktop     | [165491db1f](https://linux-hardware.org/?probe=165491db1f) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | Notebook    | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a4854b177f](https://linux-hardware.org/?probe=a4854b177f) | Jun 01, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [1b1a5c05ac](https://linux-hardware.org/?probe=1b1a5c05ac) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | ThinkPad L440 20ASA20VLM    | Notebook    | [1d59682589](https://linux-hardware.org/?probe=1d59682589) | Jun 01, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [b3e3a95a06](https://linux-hardware.org/?probe=b3e3a95a06) | Jun 01, 2023 |
| OEM           | Intel H81                   | Desktop     | [b62ec659fa](https://linux-hardware.org/?probe=b62ec659fa) | Jun 01, 2023 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [d94ba8fb27](https://linux-hardware.org/?probe=d94ba8fb27) | Jun 01, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [00d2d07850](https://linux-hardware.org/?probe=00d2d07850) | May 31, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [417320253a](https://linux-hardware.org/?probe=417320253a) | May 31, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [f9995cb422](https://linux-hardware.org/?probe=f9995cb422) | May 31, 2023 |
| Inventec      | 0PY33N A01                  | Mini pc     | [01452a68b3](https://linux-hardware.org/?probe=01452a68b3) | May 31, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [ca4691fd95](https://linux-hardware.org/?probe=ca4691fd95) | May 31, 2023 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [483bf9a882](https://linux-hardware.org/?probe=483bf9a882) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| Dell          | System Vostro 3450          | Notebook    | [ae337aeb9c](https://linux-hardware.org/?probe=ae337aeb9c) | May 31, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [11bab4bc11](https://linux-hardware.org/?probe=11bab4bc11) | May 30, 2023 |
| TPV-INVENT... | 2AC6 A01                    | Desktop     | [1ac394c97c](https://linux-hardware.org/?probe=1ac394c97c) | May 30, 2023 |
| Timi          | RedmiBook 14 II             | Notebook    | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [9fa8d9d320](https://linux-hardware.org/?probe=9fa8d9d320) | May 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ea55e0ac39](https://linux-hardware.org/?probe=ea55e0ac39) | May 30, 2023 |
| Lenovo        | ThinkPad X61 76738AG        | Notebook    | [7f52d18c2f](https://linux-hardware.org/?probe=7f52d18c2f) | May 30, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [ddab046bd5](https://linux-hardware.org/?probe=ddab046bd5) | May 30, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [f762140894](https://linux-hardware.org/?probe=f762140894) | May 30, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [48359795cc](https://linux-hardware.org/?probe=48359795cc) | May 30, 2023 |
| HP            | 82F2 A01                    | Desktop     | [fb729f1358](https://linux-hardware.org/?probe=fb729f1358) | May 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a46f523ea2](https://linux-hardware.org/?probe=a46f523ea2) | May 29, 2023 |
| MSI           | P67A-GD65                   | Desktop     | [fe5e3bcd7b](https://linux-hardware.org/?probe=fe5e3bcd7b) | May 29, 2023 |
| Samsung       | 600B4B/600B5B               | Notebook    | [feba5017b3](https://linux-hardware.org/?probe=feba5017b3) | May 29, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Notebook    | [e462733019](https://linux-hardware.org/?probe=e462733019) | May 29, 2023 |
| Google        | Auron_Paine                 | Notebook    | [66fd27934f](https://linux-hardware.org/?probe=66fd27934f) | May 29, 2023 |
| Gigabyte      | Z690 UD                     | Desktop     | [feab206ef4](https://linux-hardware.org/?probe=feab206ef4) | May 29, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [7b001db11a](https://linux-hardware.org/?probe=7b001db11a) | May 29, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [fc839b0b6f](https://linux-hardware.org/?probe=fc839b0b6f) | May 29, 2023 |
| Lenovo        | ThinkPad W541 20EF000MUS    | Notebook    | [44c1329399](https://linux-hardware.org/?probe=44c1329399) | May 29, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [528f7440b7](https://linux-hardware.org/?probe=528f7440b7) | May 29, 2023 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [e58b7bfc92](https://linux-hardware.org/?probe=e58b7bfc92) | May 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [42b817db26](https://linux-hardware.org/?probe=42b817db26) | May 29, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [1db96272fe](https://linux-hardware.org/?probe=1db96272fe) | May 29, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [ece00aac41](https://linux-hardware.org/?probe=ece00aac41) | May 29, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1c87272ed8](https://linux-hardware.org/?probe=1c87272ed8) | May 29, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [193fbef9a1](https://linux-hardware.org/?probe=193fbef9a1) | May 28, 2023 |
| HP            | Compaq 6910p (GY174UP#AB... | Notebook    | [43ee52e798](https://linux-hardware.org/?probe=43ee52e798) | May 28, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [af1bb009ca](https://linux-hardware.org/?probe=af1bb009ca) | May 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8436530b0](https://linux-hardware.org/?probe=b8436530b0) | May 28, 2023 |
| Lenovo        | ThinkPad T420 4236N79       | Notebook    | [9908724093](https://linux-hardware.org/?probe=9908724093) | May 28, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [b1213efe40](https://linux-hardware.org/?probe=b1213efe40) | May 28, 2023 |
| Acer          | Aspire 7540                 | Notebook    | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| Toshiba       | Satellite C645D             | Notebook    | [085994472d](https://linux-hardware.org/?probe=085994472d) | May 28, 2023 |
| Gateway       | DT55                        | Desktop     | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [bf3b702d7a](https://linux-hardware.org/?probe=bf3b702d7a) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| HP            | Pavilion dm4                | Notebook    | [51b921c72d](https://linux-hardware.org/?probe=51b921c72d) | May 28, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [f90f831805](https://linux-hardware.org/?probe=f90f831805) | May 28, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [ad8e3ea3ea](https://linux-hardware.org/?probe=ad8e3ea3ea) | May 27, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [3904ffdddf](https://linux-hardware.org/?probe=3904ffdddf) | May 27, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [3e43db6ab5](https://linux-hardware.org/?probe=3e43db6ab5) | May 27, 2023 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [f2181d0270](https://linux-hardware.org/?probe=f2181d0270) | May 27, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [bfc89878ce](https://linux-hardware.org/?probe=bfc89878ce) | May 27, 2023 |
| Dell          | 0TP412                      | Desktop     | [112fa3015f](https://linux-hardware.org/?probe=112fa3015f) | May 27, 2023 |
| Wistron       | ProLiant ML110 G6           | Desktop     | [bc1c76bb8f](https://linux-hardware.org/?probe=bc1c76bb8f) | May 27, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [b0435ce0dc](https://linux-hardware.org/?probe=b0435ce0dc) | May 27, 2023 |
| Intel         | B75                         | Desktop     | [8dba7fa195](https://linux-hardware.org/?probe=8dba7fa195) | May 27, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [3900a03a2c](https://linux-hardware.org/?probe=3900a03a2c) | May 27, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [3e9709dc25](https://linux-hardware.org/?probe=3e9709dc25) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [9dc73257dc](https://linux-hardware.org/?probe=9dc73257dc) | May 27, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [b17003f11e](https://linux-hardware.org/?probe=b17003f11e) | May 27, 2023 |
| MSI           | B250M BAZOOKA               | Desktop     | [2bfe50d945](https://linux-hardware.org/?probe=2bfe50d945) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [5977804b94](https://linux-hardware.org/?probe=5977804b94) | May 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c4af5a7969](https://linux-hardware.org/?probe=c4af5a7969) | May 26, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [31c6913c14](https://linux-hardware.org/?probe=31c6913c14) | May 26, 2023 |
| Dell          | Latitude 5290               | Notebook    | [fb6cbb6a2f](https://linux-hardware.org/?probe=fb6cbb6a2f) | May 26, 2023 |
| Dell          | Latitude E5440              | Notebook    | [4a5501c365](https://linux-hardware.org/?probe=4a5501c365) | May 26, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [5d54a10d85](https://linux-hardware.org/?probe=5d54a10d85) | May 26, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [c897394a34](https://linux-hardware.org/?probe=c897394a34) | May 26, 2023 |
| Fujitsu Si... | D2464-A1 S26361-D2464-A1    | Desktop     | [313c8a3663](https://linux-hardware.org/?probe=313c8a3663) | May 26, 2023 |
| Acer          | EQ45LM                      | Desktop     | [a49c4c8438](https://linux-hardware.org/?probe=a49c4c8438) | May 26, 2023 |
| Acer          | Aspire M3910                | Desktop     | [f4dedc13f9](https://linux-hardware.org/?probe=f4dedc13f9) | May 25, 2023 |
| MSI           | Z590 PLUS                   | Desktop     | [1f531f4e58](https://linux-hardware.org/?probe=1f531f4e58) | May 25, 2023 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [41eac45c5e](https://linux-hardware.org/?probe=41eac45c5e) | May 25, 2023 |
| LG Electro... | 22V280 FAB1                 | All in one  | [0df1994f25](https://linux-hardware.org/?probe=0df1994f25) | May 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0ffdb62c45](https://linux-hardware.org/?probe=0ffdb62c45) | May 25, 2023 |
| Acer          | TravelMate 5720             | Notebook    | [1066a7a5c5](https://linux-hardware.org/?probe=1066a7a5c5) | May 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [6f1a19d503](https://linux-hardware.org/?probe=6f1a19d503) | May 25, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [5311e723a0](https://linux-hardware.org/?probe=5311e723a0) | May 25, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [a8dd30a7bb](https://linux-hardware.org/?probe=a8dd30a7bb) | May 25, 2023 |
| ASUSTek       | P8B75-V                     | Desktop     | [cbcfc55949](https://linux-hardware.org/?probe=cbcfc55949) | May 25, 2023 |
| Dell          | 0XJ8C4 A00                  | Desktop     | [b6b7396e06](https://linux-hardware.org/?probe=b6b7396e06) | May 25, 2023 |
| Timi          | TM1701                      | Notebook    | [c883337466](https://linux-hardware.org/?probe=c883337466) | May 24, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [1247209c34](https://linux-hardware.org/?probe=1247209c34) | May 24, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [701c6c3410](https://linux-hardware.org/?probe=701c6c3410) | May 24, 2023 |
| Lenovo        | 318E SDK0L22692 WIN 3792... | Desktop     | [5fb6f16a6d](https://linux-hardware.org/?probe=5fb6f16a6d) | May 24, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [149a19eeeb](https://linux-hardware.org/?probe=149a19eeeb) | May 24, 2023 |
| Gigabyte      | 8I945GZME-RH                | Desktop     | [3b4c63eddb](https://linux-hardware.org/?probe=3b4c63eddb) | May 24, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [cd798092df](https://linux-hardware.org/?probe=cd798092df) | May 23, 2023 |
| Intel         | H61                         | Desktop     | [794ecc6c43](https://linux-hardware.org/?probe=794ecc6c43) | May 23, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [f0b7bf3520](https://linux-hardware.org/?probe=f0b7bf3520) | May 23, 2023 |
| HP            | 81B3                        | Desktop     | [6b35d06402](https://linux-hardware.org/?probe=6b35d06402) | May 23, 2023 |
| ASUSTek       | PRIME X299-DELUXE           | Desktop     | [c13217076b](https://linux-hardware.org/?probe=c13217076b) | May 23, 2023 |
| Dell          | 0H19HD A06                  | Server      | [25975db1c4](https://linux-hardware.org/?probe=25975db1c4) | May 23, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [e177bb8db5](https://linux-hardware.org/?probe=e177bb8db5) | May 23, 2023 |
| Lenovo        | ThinkPad L520 5017A62       | Notebook    | [a8d01c9adb](https://linux-hardware.org/?probe=a8d01c9adb) | May 23, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [f65eac842b](https://linux-hardware.org/?probe=f65eac842b) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cbda228a9](https://linux-hardware.org/?probe=9cbda228a9) | May 23, 2023 |
| Foxconn       | G41MD                       | Desktop     | [a3a8a67867](https://linux-hardware.org/?probe=a3a8a67867) | May 23, 2023 |
| Dell          | 0X2YVY A00                  | All in one  | [cf15aa9b1a](https://linux-hardware.org/?probe=cf15aa9b1a) | May 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6855a79270](https://linux-hardware.org/?probe=6855a79270) | May 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [76db4a03a1](https://linux-hardware.org/?probe=76db4a03a1) | May 22, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [bc2b7d421d](https://linux-hardware.org/?probe=bc2b7d421d) | May 22, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | Notebook    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| HP            | 2AF3                        | Desktop     | [e70a1c12fb](https://linux-hardware.org/?probe=e70a1c12fb) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| ASRock        | H310M-STX                   | Desktop     | [c5d385dd80](https://linux-hardware.org/?probe=c5d385dd80) | May 22, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [2f1b921a18](https://linux-hardware.org/?probe=2f1b921a18) | May 22, 2023 |
| Lenovo        | ThinkPad T490 20N3S4VV00    | Notebook    | [5c190a4d57](https://linux-hardware.org/?probe=5c190a4d57) | May 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [63a27f785d](https://linux-hardware.org/?probe=63a27f785d) | May 22, 2023 |
| HP            | 1632                        | Desktop     | [ed47689eec](https://linux-hardware.org/?probe=ed47689eec) | May 22, 2023 |
| Dell          | Latitude E6230              | Notebook    | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| ASUSTek       | K84L                        | Notebook    | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [816fffab13](https://linux-hardware.org/?probe=816fffab13) | May 21, 2023 |
| Teclast       | X4                          | Tablet      | [9dc0b8fa7b](https://linux-hardware.org/?probe=9dc0b8fa7b) | May 21, 2023 |
| Dell          | 0PC5F7 A03                  | Desktop     | [0ef682fa85](https://linux-hardware.org/?probe=0ef682fa85) | May 21, 2023 |
| Philco        | 14H                         | Notebook    | [5dbb0cb3b7](https://linux-hardware.org/?probe=5dbb0cb3b7) | May 21, 2023 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | Notebook    | [03afaf2468](https://linux-hardware.org/?probe=03afaf2468) | May 21, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [1c5c9709dd](https://linux-hardware.org/?probe=1c5c9709dd) | May 21, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [906ba8b65c](https://linux-hardware.org/?probe=906ba8b65c) | May 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7ff619a028](https://linux-hardware.org/?probe=7ff619a028) | May 21, 2023 |
| ASUSTek       | N53TK                       | Notebook    | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [2aff70d7c9](https://linux-hardware.org/?probe=2aff70d7c9) | May 21, 2023 |
| Acer          | Aspire 4750                 | Notebook    | [704221c10c](https://linux-hardware.org/?probe=704221c10c) | May 21, 2023 |
| ASRock        | Q1900M                      | Desktop     | [0290a65c70](https://linux-hardware.org/?probe=0290a65c70) | May 21, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [e9b749f2ba](https://linux-hardware.org/?probe=e9b749f2ba) | May 21, 2023 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [0deaff38f5](https://linux-hardware.org/?probe=0deaff38f5) | May 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [c3af6442c9](https://linux-hardware.org/?probe=c3af6442c9) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [e1939cff8f](https://linux-hardware.org/?probe=e1939cff8f) | May 21, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [ed99950768](https://linux-hardware.org/?probe=ed99950768) | May 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [59464cac80](https://linux-hardware.org/?probe=59464cac80) | May 20, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [b68e5e0285](https://linux-hardware.org/?probe=b68e5e0285) | May 20, 2023 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [f39a134aa1](https://linux-hardware.org/?probe=f39a134aa1) | May 20, 2023 |
| Dell          | Inspiron 1501               | Notebook    | [d2fb2ddcce](https://linux-hardware.org/?probe=d2fb2ddcce) | May 20, 2023 |
| ASUSTek       | P8Z77-V                     | Desktop     | [b38a68e146](https://linux-hardware.org/?probe=b38a68e146) | May 20, 2023 |
| Dell          | Latitude 5285               | Notebook    | [0db3cfd34e](https://linux-hardware.org/?probe=0db3cfd34e) | May 20, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b563edd887](https://linux-hardware.org/?probe=b563edd887) | May 20, 2023 |
| Foxconn       | G41MD                       | Desktop     | [1a649b0512](https://linux-hardware.org/?probe=1a649b0512) | May 20, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [f4ed05479f](https://linux-hardware.org/?probe=f4ed05479f) | May 19, 2023 |
| HP            | 250 G2                      | Notebook    | [e3b94752ac](https://linux-hardware.org/?probe=e3b94752ac) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [c1df991f26](https://linux-hardware.org/?probe=c1df991f26) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Lenovo        | ThinkPad W530 24411M9       | Notebook    | [1094884573](https://linux-hardware.org/?probe=1094884573) | May 19, 2023 |
| ASRock        | Z590M Pro4                  | Desktop     | [d039ed90c5](https://linux-hardware.org/?probe=d039ed90c5) | May 19, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [39725fefa4](https://linux-hardware.org/?probe=39725fefa4) | May 19, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [b25115a01a](https://linux-hardware.org/?probe=b25115a01a) | May 19, 2023 |
| ASUSTek       | F7Se                        | Notebook    | [1cd79e84fd](https://linux-hardware.org/?probe=1cd79e84fd) | May 19, 2023 |
| Lenovo        | ThinkPad L560 20F2S1JP03    | Notebook    | [d0dd999b33](https://linux-hardware.org/?probe=d0dd999b33) | May 18, 2023 |
| HP            | 0A54h                       | Desktop     | [76953e42f8](https://linux-hardware.org/?probe=76953e42f8) | May 18, 2023 |
| Acer          | Aspire A114-32              | Notebook    | [d17a909427](https://linux-hardware.org/?probe=d17a909427) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [82dca1cbb8](https://linux-hardware.org/?probe=82dca1cbb8) | May 18, 2023 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2914e5278a](https://linux-hardware.org/?probe=2914e5278a) | May 18, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Toshiba       | Satellite L850-1HQ          | Notebook    | [d16c26b474](https://linux-hardware.org/?probe=d16c26b474) | May 18, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [05379205f4](https://linux-hardware.org/?probe=05379205f4) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b30dee1244](https://linux-hardware.org/?probe=b30dee1244) | May 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [df73f83c15](https://linux-hardware.org/?probe=df73f83c15) | May 18, 2023 |
| Google        | Auron_Paine                 | Notebook    | [a836fcd48f](https://linux-hardware.org/?probe=a836fcd48f) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | Notebook    | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| ASRock        | N68-GS4/USB3 FX             | Desktop     | [80fa152a82](https://linux-hardware.org/?probe=80fa152a82) | May 17, 2023 |
| UMAX          | VisionBook 13Wg Flex        | Convertible | [170db25383](https://linux-hardware.org/?probe=170db25383) | May 17, 2023 |
| Fujitsu       | D3420-U1 S26361-D3420-U1    | Desktop     | [958b2ab1f9](https://linux-hardware.org/?probe=958b2ab1f9) | May 17, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [4bd367b4c7](https://linux-hardware.org/?probe=4bd367b4c7) | May 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| NEC Comput... | SK15 3A3B                   | All in one  | [80a4b43ab9](https://linux-hardware.org/?probe=80a4b43ab9) | May 17, 2023 |
| Fujitsu       | LIFEBOOK P728               | Convertible | [55db12e408](https://linux-hardware.org/?probe=55db12e408) | May 17, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [f50517b1c5](https://linux-hardware.org/?probe=f50517b1c5) | May 17, 2023 |
| Acer          | Spin SP315-51               | Convertible | [e4b64c42b7](https://linux-hardware.org/?probe=e4b64c42b7) | May 16, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [cfe4d9071b](https://linux-hardware.org/?probe=cfe4d9071b) | May 16, 2023 |
| HP            | 18E5                        | Desktop     | [5e25e2156a](https://linux-hardware.org/?probe=5e25e2156a) | May 16, 2023 |
| Maxtang       | FP650 V1.0                  | Desktop     | [8f1eba846a](https://linux-hardware.org/?probe=8f1eba846a) | May 16, 2023 |
| Foxconn       | P35A01                      | Desktop     | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| HP            | Laptop 17z-ca300            | Notebook    | [8daeb02e63](https://linux-hardware.org/?probe=8daeb02e63) | May 16, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [f199f11aa5](https://linux-hardware.org/?probe=f199f11aa5) | May 15, 2023 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [652d9e0fa9](https://linux-hardware.org/?probe=652d9e0fa9) | May 15, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [eee39f2f10](https://linux-hardware.org/?probe=eee39f2f10) | May 15, 2023 |
| Samsung       | R428/P428                   | Notebook    | [1d93335f58](https://linux-hardware.org/?probe=1d93335f58) | May 15, 2023 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [02da78340f](https://linux-hardware.org/?probe=02da78340f) | May 15, 2023 |
| Lenovo        | ThinkPad X390 Yoga 20NN0... | Convertible | [3ca79ab5f8](https://linux-hardware.org/?probe=3ca79ab5f8) | May 15, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [1effa68567](https://linux-hardware.org/?probe=1effa68567) | May 15, 2023 |
| HP            | 8436                        | Desktop     | [ae94b377fd](https://linux-hardware.org/?probe=ae94b377fd) | May 15, 2023 |
| Samsung       | R530/R730                   | Notebook    | [d7674fa203](https://linux-hardware.org/?probe=d7674fa203) | May 15, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [fafdf532fb](https://linux-hardware.org/?probe=fafdf532fb) | May 15, 2023 |
| Lenovo        | ThinkPad X100e 0022CTO      | Notebook    | [842b7a3ee2](https://linux-hardware.org/?probe=842b7a3ee2) | May 14, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [7380a83f05](https://linux-hardware.org/?probe=7380a83f05) | May 14, 2023 |
| HP            | Pavilion dv8                | Notebook    | [422d1fd213](https://linux-hardware.org/?probe=422d1fd213) | May 14, 2023 |
| ASUSTek       | M2A-MX                      | Desktop     | [43c0de16a2](https://linux-hardware.org/?probe=43c0de16a2) | May 14, 2023 |
| Acer          | Aspire A114-32              | Notebook    | [6fdf42b8a9](https://linux-hardware.org/?probe=6fdf42b8a9) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | Notebook    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | Desktop     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Dell          | Precision M4500             | Notebook    | [315cccc082](https://linux-hardware.org/?probe=315cccc082) | May 14, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| ASRock        | G41M-GS3                    | Desktop     | [8859685e86](https://linux-hardware.org/?probe=8859685e86) | May 13, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [cbd408a1a6](https://linux-hardware.org/?probe=cbd408a1a6) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | Notebook    | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [37eeeb2f31](https://linux-hardware.org/?probe=37eeeb2f31) | May 13, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [16954b8f95](https://linux-hardware.org/?probe=16954b8f95) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Intel         | H61                         | Desktop     | [685bd5d439](https://linux-hardware.org/?probe=685bd5d439) | May 12, 2023 |
| Lenovo        | SDK0E50510 WIN 262507960... | Desktop     | [2892c822d5](https://linux-hardware.org/?probe=2892c822d5) | May 12, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [53f535546a](https://linux-hardware.org/?probe=53f535546a) | May 12, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [60defd2bfe](https://linux-hardware.org/?probe=60defd2bfe) | May 12, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [95974d7e97](https://linux-hardware.org/?probe=95974d7e97) | May 12, 2023 |
| ASUSTek       | P5B-VM SE                   | Desktop     | [bd1c748eed](https://linux-hardware.org/?probe=bd1c748eed) | May 12, 2023 |
| HP            | EliteBook 720 G2            | Notebook    | [d6a156003b](https://linux-hardware.org/?probe=d6a156003b) | May 12, 2023 |
| HP            | 0A58h                       | Desktop     | [b48452bdd9](https://linux-hardware.org/?probe=b48452bdd9) | May 12, 2023 |
| Acer          | RS880M05                    | Desktop     | [5952c105f6](https://linux-hardware.org/?probe=5952c105f6) | May 12, 2023 |
| Dell          | 04YP6J A02                  | Desktop     | [aec2bbbb46](https://linux-hardware.org/?probe=aec2bbbb46) | May 11, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [db910d4ee1](https://linux-hardware.org/?probe=db910d4ee1) | May 11, 2023 |
| Toshiba       | Satellite C75-A             | Notebook    | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [989d8eef43](https://linux-hardware.org/?probe=989d8eef43) | May 11, 2023 |
| Acer          | Extensa 5220                | Notebook    | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b63292a4f9](https://linux-hardware.org/?probe=b63292a4f9) | May 11, 2023 |
| Infinix       | INBook X1                   | Notebook    | [c005323a1a](https://linux-hardware.org/?probe=c005323a1a) | May 11, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [7e1600284a](https://linux-hardware.org/?probe=7e1600284a) | May 11, 2023 |
| HP            | Laptop 17-by0xxx            | Notebook    | [10b9d3a925](https://linux-hardware.org/?probe=10b9d3a925) | May 11, 2023 |
| Acer          | Aspire E1-521               | Notebook    | [22d77e0e7d](https://linux-hardware.org/?probe=22d77e0e7d) | May 11, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [040f5917ec](https://linux-hardware.org/?probe=040f5917ec) | May 10, 2023 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [8376015b15](https://linux-hardware.org/?probe=8376015b15) | May 10, 2023 |
| MSI           | B350M PRO-VDH               | Desktop     | [76dbae3614](https://linux-hardware.org/?probe=76dbae3614) | May 10, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [2710a15a04](https://linux-hardware.org/?probe=2710a15a04) | May 10, 2023 |
| Intel         | X58M                        | Desktop     | [666b002908](https://linux-hardware.org/?probe=666b002908) | May 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [68afb54270](https://linux-hardware.org/?probe=68afb54270) | May 10, 2023 |
| Samsung       | X420/X520                   | Notebook    | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [8f7bcc525d](https://linux-hardware.org/?probe=8f7bcc525d) | May 10, 2023 |
| HP            | 83EB                        | All in one  | [0abdbdd77b](https://linux-hardware.org/?probe=0abdbdd77b) | May 10, 2023 |
| ASUSTek       | P8H77-V                     | Desktop     | [f86702afcf](https://linux-hardware.org/?probe=f86702afcf) | May 10, 2023 |
| Thomson       | N14C64WF                    | Notebook    | [4e5a5f6e51](https://linux-hardware.org/?probe=4e5a5f6e51) | May 10, 2023 |
| ASUSTek       | M4A78L-M                    | Desktop     | [1a843c3a7f](https://linux-hardware.org/?probe=1a843c3a7f) | May 10, 2023 |
| Dell          | Precision M3800             | Notebook    | [e7b0097a72](https://linux-hardware.org/?probe=e7b0097a72) | May 09, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f7cb6c9251](https://linux-hardware.org/?probe=f7cb6c9251) | May 09, 2023 |
| HP            | Compaq Mini CQ10-500        | Notebook    | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| HP            | 304Ah                       | Desktop     | [7c6a6b156f](https://linux-hardware.org/?probe=7c6a6b156f) | May 09, 2023 |
| Dell          | Latitude 5420               | Notebook    | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| Fujitsu       | FMVA0500TP                  | Notebook    | [61061bd78d](https://linux-hardware.org/?probe=61061bd78d) | May 09, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [6fe358200a](https://linux-hardware.org/?probe=6fe358200a) | May 09, 2023 |
| Acer          | EG43M                       | Desktop     | [01704e814c](https://linux-hardware.org/?probe=01704e814c) | May 09, 2023 |
| ASUSTek       | M32CD4-K                    | Desktop     | [0bca52bcc5](https://linux-hardware.org/?probe=0bca52bcc5) | May 09, 2023 |
| Acer          | Aspire VN7-592G             | Notebook    | [8ebde36ef2](https://linux-hardware.org/?probe=8ebde36ef2) | May 09, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [57b843a3ca](https://linux-hardware.org/?probe=57b843a3ca) | May 09, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [83f86e5727](https://linux-hardware.org/?probe=83f86e5727) | May 09, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [f173eb5463](https://linux-hardware.org/?probe=f173eb5463) | May 09, 2023 |
| Dell          | Latitude E6440              | Notebook    | [6b8d3c96c5](https://linux-hardware.org/?probe=6b8d3c96c5) | May 09, 2023 |
| HP            | Pavilion dv7                | Notebook    | [1d9699c86f](https://linux-hardware.org/?probe=1d9699c86f) | May 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [531adb6cae](https://linux-hardware.org/?probe=531adb6cae) | May 09, 2023 |
| HP            | ProBook 440 G1              | Notebook    | [aea73943e8](https://linux-hardware.org/?probe=aea73943e8) | May 09, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [53d91dca3c](https://linux-hardware.org/?probe=53d91dca3c) | May 08, 2023 |
| Dell          | 0XCR8D A02                  | Desktop     | [5bc5ccdcad](https://linux-hardware.org/?probe=5bc5ccdcad) | May 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [acf61a6132](https://linux-hardware.org/?probe=acf61a6132) | May 08, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [def28849c6](https://linux-hardware.org/?probe=def28849c6) | May 08, 2023 |
| HP            | 15                          | Notebook    | [fd2af6a225](https://linux-hardware.org/?probe=fd2af6a225) | May 08, 2023 |
| Dell          | 0T656F A01                  | Desktop     | [94294c8cf0](https://linux-hardware.org/?probe=94294c8cf0) | May 08, 2023 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [e7b77f5cf0](https://linux-hardware.org/?probe=e7b77f5cf0) | May 08, 2023 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [22bd54d6d1](https://linux-hardware.org/?probe=22bd54d6d1) | May 08, 2023 |
| Acer          | Aspire ES1-132              | Notebook    | [10a13dcd68](https://linux-hardware.org/?probe=10a13dcd68) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [d615a9b90f](https://linux-hardware.org/?probe=d615a9b90f) | May 08, 2023 |
| Apple         | MacBookAir9,1               | Notebook    | [a0073c6ff3](https://linux-hardware.org/?probe=a0073c6ff3) | May 08, 2023 |
| ASUSTek       | P5QLD PRO                   | Desktop     | [c2a0653c52](https://linux-hardware.org/?probe=c2a0653c52) | May 08, 2023 |
| ASUSTek       | X202E                       | Notebook    | [6039408aaf](https://linux-hardware.org/?probe=6039408aaf) | May 08, 2023 |
| HP            | 15                          | Notebook    | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [47388f4553](https://linux-hardware.org/?probe=47388f4553) | May 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3530619c98](https://linux-hardware.org/?probe=3530619c98) | May 07, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [46a87a6448](https://linux-hardware.org/?probe=46a87a6448) | May 07, 2023 |
| Dell          | 0R230R A00                  | Desktop     | [16611a8ed6](https://linux-hardware.org/?probe=16611a8ed6) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [893f259653](https://linux-hardware.org/?probe=893f259653) | May 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b734a6d6f3](https://linux-hardware.org/?probe=b734a6d6f3) | May 07, 2023 |
| MSI           | H110M PRO-VH                | Desktop     | [d63bc9aeca](https://linux-hardware.org/?probe=d63bc9aeca) | May 07, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [eeb083abcd](https://linux-hardware.org/?probe=eeb083abcd) | May 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [68e1c1b5a4](https://linux-hardware.org/?probe=68e1c1b5a4) | May 07, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [9eef570443](https://linux-hardware.org/?probe=9eef570443) | May 07, 2023 |
| Lenovo        | ThinkPad Yoga 460 20ELS0... | Convertible | [305cc49ac0](https://linux-hardware.org/?probe=305cc49ac0) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [99fbd772e8](https://linux-hardware.org/?probe=99fbd772e8) | May 07, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [895855ed9a](https://linux-hardware.org/?probe=895855ed9a) | May 07, 2023 |
| HP            | Presario CQ57               | Notebook    | [370295ac6d](https://linux-hardware.org/?probe=370295ac6d) | May 07, 2023 |
| Gigabyte      | H470M K                     | Desktop     | [655bbe4068](https://linux-hardware.org/?probe=655bbe4068) | May 07, 2023 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [f86e67c005](https://linux-hardware.org/?probe=f86e67c005) | May 07, 2023 |
| Shuttle       | FZ77                        | Desktop     | [e4a71bcb2d](https://linux-hardware.org/?probe=e4a71bcb2d) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [7a77c66c97](https://linux-hardware.org/?probe=7a77c66c97) | May 06, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | Notebook    | [6c404ee491](https://linux-hardware.org/?probe=6c404ee491) | May 06, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3ea9b926d](https://linux-hardware.org/?probe=f3ea9b926d) | May 06, 2023 |
| Dell          | System XPS L702X            | Notebook    | [210b876fe7](https://linux-hardware.org/?probe=210b876fe7) | May 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b3bf20b454](https://linux-hardware.org/?probe=b3bf20b454) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Alienware     | 0R3FWM A00                  | Desktop     | [c6dbe0270a](https://linux-hardware.org/?probe=c6dbe0270a) | May 06, 2023 |
| Panasonic     | CF-54-1                     | Notebook    | [c964ce47c2](https://linux-hardware.org/?probe=c964ce47c2) | May 06, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [70862b2870](https://linux-hardware.org/?probe=70862b2870) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [094b22cf5a](https://linux-hardware.org/?probe=094b22cf5a) | May 06, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| Intel         | WADE-8076-ST-WMS            | Desktop     | [ae71682181](https://linux-hardware.org/?probe=ae71682181) | May 06, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [d5456946bb](https://linux-hardware.org/?probe=d5456946bb) | May 06, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| ASRock        | G41C-GS                     | Desktop     | [03076cae9a](https://linux-hardware.org/?probe=03076cae9a) | May 06, 2023 |
| Quanta        | JW2                         | Notebook    | [eb9ff2a263](https://linux-hardware.org/?probe=eb9ff2a263) | May 06, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [79c33e919f](https://linux-hardware.org/?probe=79c33e919f) | May 06, 2023 |
| ASRock        | Q270 Pro BTC+               | Desktop     | [4fc3d2c86f](https://linux-hardware.org/?probe=4fc3d2c86f) | May 05, 2023 |
| ASUSTek       | K75DE                       | Notebook    | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| ASUSTek       | X401A1                      | Notebook    | [3fa1a1e9f0](https://linux-hardware.org/?probe=3fa1a1e9f0) | May 05, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [edcdedd65a](https://linux-hardware.org/?probe=edcdedd65a) | May 05, 2023 |
| MSI           | A75A-G55                    | Desktop     | [6ecb91213c](https://linux-hardware.org/?probe=6ecb91213c) | May 05, 2023 |
| Intel         | B75                         | Desktop     | [f70469a019](https://linux-hardware.org/?probe=f70469a019) | May 05, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [09bd22441b](https://linux-hardware.org/?probe=09bd22441b) | May 05, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [ffb03b8bd4](https://linux-hardware.org/?probe=ffb03b8bd4) | May 05, 2023 |
| Acer          | Aspire A315-42              | Notebook    | [d8f78a98f2](https://linux-hardware.org/?probe=d8f78a98f2) | May 05, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [2bb77be32b](https://linux-hardware.org/?probe=2bb77be32b) | May 05, 2023 |
| Gigabyte      | X570S AORUS ELITE           | Desktop     | [6f2b69becc](https://linux-hardware.org/?probe=6f2b69becc) | May 05, 2023 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [ca84298b9d](https://linux-hardware.org/?probe=ca84298b9d) | May 05, 2023 |
| Dell          | 0PU052                      | Desktop     | [03c6b8486e](https://linux-hardware.org/?probe=03c6b8486e) | May 05, 2023 |
| eMachines     | eMG620                      | Notebook    | [224dc7209e](https://linux-hardware.org/?probe=224dc7209e) | May 04, 2023 |
| MSI           | 760GM-P34                   | Desktop     | [cb75fca473](https://linux-hardware.org/?probe=cb75fca473) | May 04, 2023 |
| Dell          | Inspiron 17-7779            | Notebook    | [f5717fc896](https://linux-hardware.org/?probe=f5717fc896) | May 04, 2023 |
| ASRock        | Z590 Steel Legend           | Desktop     | [d36cec198b](https://linux-hardware.org/?probe=d36cec198b) | May 04, 2023 |
| Medion        | E6232                       | Notebook    | [38b433b485](https://linux-hardware.org/?probe=38b433b485) | May 04, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [e60b96481a](https://linux-hardware.org/?probe=e60b96481a) | May 04, 2023 |
| Gateway       | NE46R                       | Notebook    | [05291d9029](https://linux-hardware.org/?probe=05291d9029) | May 04, 2023 |
| HP            | Laptop 17-ak0xx             | Notebook    | [579c16cd5c](https://linux-hardware.org/?probe=579c16cd5c) | May 04, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Fujitsu       | FMVA705ABS                  | Notebook    | [99cb877cba](https://linux-hardware.org/?probe=99cb877cba) | May 04, 2023 |
| Toshiba       | dynabook SS M42 210E/3W     | Notebook    | [ad7f7da4e4](https://linux-hardware.org/?probe=ad7f7da4e4) | May 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [218ba5d6a5](https://linux-hardware.org/?probe=218ba5d6a5) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [6116c0df52](https://linux-hardware.org/?probe=6116c0df52) | May 04, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [a07a7cf773](https://linux-hardware.org/?probe=a07a7cf773) | May 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [92c9651e22](https://linux-hardware.org/?probe=92c9651e22) | May 04, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [2dabac74e0](https://linux-hardware.org/?probe=2dabac74e0) | May 03, 2023 |
| Lenovo        | ThinkPad T430 2347GR2       | Notebook    | [d8ec895bea](https://linux-hardware.org/?probe=d8ec895bea) | May 03, 2023 |
| ASUSTek       | Maximus V GENE              | Desktop     | [1f49086889](https://linux-hardware.org/?probe=1f49086889) | May 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| Acer          | H57M01                      | Desktop     | [affe73e1a5](https://linux-hardware.org/?probe=affe73e1a5) | May 03, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | Notebook    | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| Dell          | Latitude E6540              | Notebook    | [e9f23b9574](https://linux-hardware.org/?probe=e9f23b9574) | May 03, 2023 |
| Positivo      | W2150G                      | All in one  | [38c2a94baa](https://linux-hardware.org/?probe=38c2a94baa) | May 02, 2023 |
| Acer          | Predator PH18-71            | Notebook    | [7c5e0a3de1](https://linux-hardware.org/?probe=7c5e0a3de1) | May 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [530aaeef9d](https://linux-hardware.org/?probe=530aaeef9d) | May 02, 2023 |
| Toshiba       | Satellite C640              | Notebook    | [20d436bfa7](https://linux-hardware.org/?probe=20d436bfa7) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| MSI           | MS-7025                     | Desktop     | [a15dc17cfc](https://linux-hardware.org/?probe=a15dc17cfc) | May 02, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | Notebook    | [cb2a0efe72](https://linux-hardware.org/?probe=cb2a0efe72) | May 02, 2023 |
| Unknown       | 1.0                         | Desktop     | [5f99ebeed7](https://linux-hardware.org/?probe=5f99ebeed7) | May 02, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [fb815bb11c](https://linux-hardware.org/?probe=fb815bb11c) | May 02, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| American M... | IPPBT-RO                    | All in one  | [a2921975cd](https://linux-hardware.org/?probe=a2921975cd) | May 02, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [583642a695](https://linux-hardware.org/?probe=583642a695) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| HP            | 3031h                       | Desktop     | [84140549cd](https://linux-hardware.org/?probe=84140549cd) | May 01, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [00dc63bf78](https://linux-hardware.org/?probe=00dc63bf78) | May 01, 2023 |
| MAXSUN        | MS-A86FX FS M.3             | Desktop     | [3ce20d3b05](https://linux-hardware.org/?probe=3ce20d3b05) | May 01, 2023 |
| Lenovo        | ThinkCentre M71e 5033A1U    | Desktop     | [2e39bbf0cf](https://linux-hardware.org/?probe=2e39bbf0cf) | May 01, 2023 |
| Samsung       | 950QDB                      | Convertible | [ecae18f163](https://linux-hardware.org/?probe=ecae18f163) | May 01, 2023 |
| HP            | 3033h                       | Desktop     | [31a4e00c60](https://linux-hardware.org/?probe=31a4e00c60) | May 01, 2023 |
| HP            | 3648h                       | Desktop     | [38ab69c4e2](https://linux-hardware.org/?probe=38ab69c4e2) | May 01, 2023 |
| HP            | Compaq 8510w                | Notebook    | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [1fb0ca13ff](https://linux-hardware.org/?probe=1fb0ca13ff) | May 01, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [2fd44c38fd](https://linux-hardware.org/?probe=2fd44c38fd) | May 01, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [15c04364fa](https://linux-hardware.org/?probe=15c04364fa) | May 01, 2023 |
| Sony          | VGN-AW11M_H                 | Notebook    | [2c9f98ca31](https://linux-hardware.org/?probe=2c9f98ca31) | May 01, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [d4b7c4a4db](https://linux-hardware.org/?probe=d4b7c4a4db) | May 01, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [4b23b933b5](https://linux-hardware.org/?probe=4b23b933b5) | May 01, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [6da1ddcef5](https://linux-hardware.org/?probe=6da1ddcef5) | May 01, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [41e9bb9584](https://linux-hardware.org/?probe=41e9bb9584) | May 01, 2023 |
| Alienware     | m17 R5 AMD                  | Notebook    | [4e665db2b1](https://linux-hardware.org/?probe=4e665db2b1) | May 01, 2023 |
| HP            | 822A                        | Desktop     | [b373ff6def](https://linux-hardware.org/?probe=b373ff6def) | May 01, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [6c1969f77e](https://linux-hardware.org/?probe=6c1969f77e) | May 01, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [e7905065dd](https://linux-hardware.org/?probe=e7905065dd) | Apr 30, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| DIEBOLD       | NM70-I                      | Desktop     | [c01a40d58c](https://linux-hardware.org/?probe=c01a40d58c) | Apr 30, 2023 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [501d26e477](https://linux-hardware.org/?probe=501d26e477) | Apr 30, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [00fbe71b59](https://linux-hardware.org/?probe=00fbe71b59) | Apr 30, 2023 |
| ASRock        | 760GM-HD                    | Desktop     | [db79e93331](https://linux-hardware.org/?probe=db79e93331) | Apr 30, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [a3d2b3dcd3](https://linux-hardware.org/?probe=a3d2b3dcd3) | Apr 30, 2023 |
| HP            | Notebook                    | Notebook    | [4cece109d5](https://linux-hardware.org/?probe=4cece109d5) | Apr 30, 2023 |
| ASUSTek       | X501A1                      | Notebook    | [66b02cc148](https://linux-hardware.org/?probe=66b02cc148) | Apr 30, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [fdba59c054](https://linux-hardware.org/?probe=fdba59c054) | Apr 30, 2023 |
| Acer          | AO725                       | Notebook    | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [ac7894081f](https://linux-hardware.org/?probe=ac7894081f) | Apr 30, 2023 |
| Medion        | D3F3-EM                     | Desktop     | [6b9e38ad6c](https://linux-hardware.org/?probe=6b9e38ad6c) | Apr 30, 2023 |
| MSI           | A68HM GRENADE               | Desktop     | [938aa1cb46](https://linux-hardware.org/?probe=938aa1cb46) | Apr 30, 2023 |
| HP            | Compaq 6720s                | Notebook    | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [6750e5f83d](https://linux-hardware.org/?probe=6750e5f83d) | Apr 30, 2023 |
| Acer          | E661GXM                     | Desktop     | [d5433b46bd](https://linux-hardware.org/?probe=d5433b46bd) | Apr 30, 2023 |
| Acer          | Aspire X3950                | Desktop     | [406366d5c1](https://linux-hardware.org/?probe=406366d5c1) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [36ccc3c930](https://linux-hardware.org/?probe=36ccc3c930) | Apr 30, 2023 |
| T-bao         | MINI PC V1.0                | Desktop     | [8e77950434](https://linux-hardware.org/?probe=8e77950434) | Apr 30, 2023 |
| Packard Be... | EasyNote ENTF71BM           | Notebook    | [99a89a2055](https://linux-hardware.org/?probe=99a89a2055) | Apr 30, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [fd991056e0](https://linux-hardware.org/?probe=fd991056e0) | Apr 30, 2023 |
| Dell          | Inspiron 15 3525            | Notebook    | [41c212fa2c](https://linux-hardware.org/?probe=41c212fa2c) | Apr 30, 2023 |
| Acer          | TravelMate B311-31          | Notebook    | [de172b8988](https://linux-hardware.org/?probe=de172b8988) | Apr 30, 2023 |
| ASUSTek       | K53E                        | Notebook    | [dcb4502d05](https://linux-hardware.org/?probe=dcb4502d05) | Apr 30, 2023 |
| Intel         | H61                         | Desktop     | [167616bc61](https://linux-hardware.org/?probe=167616bc61) | Apr 30, 2023 |
| Dell          | 0GXM1W A02                  | Desktop     | [7dcb847a6c](https://linux-hardware.org/?probe=7dcb847a6c) | Apr 30, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [8f07407e1a](https://linux-hardware.org/?probe=8f07407e1a) | Apr 29, 2023 |
| Dell          | 0773VG A02                  | Desktop     | [a684ad4938](https://linux-hardware.org/?probe=a684ad4938) | Apr 29, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c8d8595af5](https://linux-hardware.org/?probe=c8d8595af5) | Apr 29, 2023 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [32942be783](https://linux-hardware.org/?probe=32942be783) | Apr 29, 2023 |
| Lenovo        | Unknown                     | Notebook    | [33a55a2347](https://linux-hardware.org/?probe=33a55a2347) | Apr 29, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [3056c07eb6](https://linux-hardware.org/?probe=3056c07eb6) | Apr 29, 2023 |
| ASRock        | 890FX Deluxe4               | Desktop     | [327a1a2b37](https://linux-hardware.org/?probe=327a1a2b37) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| Lenovo        | ThinkPad T530 24294A1       | Notebook    | [8695d820e4](https://linux-hardware.org/?probe=8695d820e4) | Apr 29, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [8ea78b28f1](https://linux-hardware.org/?probe=8ea78b28f1) | Apr 29, 2023 |
| Toshiba       | PORTEGE R830                | Notebook    | [11dc4b3a3e](https://linux-hardware.org/?probe=11dc4b3a3e) | Apr 29, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [0f22698060](https://linux-hardware.org/?probe=0f22698060) | Apr 29, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [59fcc52279](https://linux-hardware.org/?probe=59fcc52279) | Apr 29, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [aa8c0bb2b9](https://linux-hardware.org/?probe=aa8c0bb2b9) | Apr 29, 2023 |
| MSI           | MS-9661 SA                  | Server      | [1888fa6df7](https://linux-hardware.org/?probe=1888fa6df7) | Apr 29, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [168b3cf595](https://linux-hardware.org/?probe=168b3cf595) | Apr 29, 2023 |
| Dell          | Latitude 7390               | Notebook    | [c24cc9ab68](https://linux-hardware.org/?probe=c24cc9ab68) | Apr 29, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [8f1db96b6f](https://linux-hardware.org/?probe=8f1db96b6f) | Apr 29, 2023 |
| Foxconn       | 2AB7                        | Desktop     | [01e7b05d2a](https://linux-hardware.org/?probe=01e7b05d2a) | Apr 29, 2023 |
| Medion        | X6816                       | Notebook    | [2c1807dad7](https://linux-hardware.org/?probe=2c1807dad7) | Apr 29, 2023 |
| HP            | Compaq Presario CQ70        | Notebook    | [b4055572ee](https://linux-hardware.org/?probe=b4055572ee) | Apr 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [7e7da68aa3](https://linux-hardware.org/?probe=7e7da68aa3) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [5fe84b74b0](https://linux-hardware.org/?probe=5fe84b74b0) | Apr 28, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [7719e2a6c9](https://linux-hardware.org/?probe=7719e2a6c9) | Apr 28, 2023 |
| AZW           | MINI S 10                   | Desktop     | [12ba32f977](https://linux-hardware.org/?probe=12ba32f977) | Apr 28, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e2c8068a7d](https://linux-hardware.org/?probe=e2c8068a7d) | Apr 28, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [27a8681404](https://linux-hardware.org/?probe=27a8681404) | Apr 28, 2023 |
| Acer          | Swift SF314-59              | Notebook    | [a84de33c38](https://linux-hardware.org/?probe=a84de33c38) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| Dell          | Latitude D830               | Notebook    | [2ab0772efb](https://linux-hardware.org/?probe=2ab0772efb) | Apr 28, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2beb48be05](https://linux-hardware.org/?probe=2beb48be05) | Apr 27, 2023 |
| Sony          | SVF15212CXW                 | Notebook    | [5d5367dc0e](https://linux-hardware.org/?probe=5d5367dc0e) | Apr 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b21dd8d75a](https://linux-hardware.org/?probe=b21dd8d75a) | Apr 27, 2023 |
| HP            | ProBook 4330s               | Notebook    | [955f91641b](https://linux-hardware.org/?probe=955f91641b) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| Lenovo        | ThinkPad R61 8943DJG        | Notebook    | [afc3fc578e](https://linux-hardware.org/?probe=afc3fc578e) | Apr 27, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [da50afdd1c](https://linux-hardware.org/?probe=da50afdd1c) | Apr 27, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [a63003783d](https://linux-hardware.org/?probe=a63003783d) | Apr 27, 2023 |
| Dell          | 0XKD8M A00                  | All in one  | [1629350aa9](https://linux-hardware.org/?probe=1629350aa9) | Apr 27, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [710070cf4a](https://linux-hardware.org/?probe=710070cf4a) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [f549cb502c](https://linux-hardware.org/?probe=f549cb502c) | Apr 27, 2023 |
| MSI           | H81M-P33                    | Desktop     | [2099cafe74](https://linux-hardware.org/?probe=2099cafe74) | Apr 27, 2023 |
| ASUSTek       | P5GC-VM/SI                  | Desktop     | [abf277ec59](https://linux-hardware.org/?probe=abf277ec59) | Apr 27, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [91930613cb](https://linux-hardware.org/?probe=91930613cb) | Apr 27, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [a23cf53cec](https://linux-hardware.org/?probe=a23cf53cec) | Apr 27, 2023 |
| MSI           | A78M-E35 V2                 | Desktop     | [5eb0f9d104](https://linux-hardware.org/?probe=5eb0f9d104) | Apr 27, 2023 |
| NEC Comput... | PC-LE150C2                  | Notebook    | [a8e48f9686](https://linux-hardware.org/?probe=a8e48f9686) | Apr 27, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [32960eca65](https://linux-hardware.org/?probe=32960eca65) | Apr 27, 2023 |
| Dell          | Latitude E6400              | Notebook    | [2cb1305ae1](https://linux-hardware.org/?probe=2cb1305ae1) | Apr 27, 2023 |
| Samsung       | 950QED                      | Convertible | [0135cc3aa4](https://linux-hardware.org/?probe=0135cc3aa4) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [21577119ad](https://linux-hardware.org/?probe=21577119ad) | Apr 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [6601cb2397](https://linux-hardware.org/?probe=6601cb2397) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [54dea0607f](https://linux-hardware.org/?probe=54dea0607f) | Apr 26, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [ab3c4ea199](https://linux-hardware.org/?probe=ab3c4ea199) | Apr 26, 2023 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [aca5bf366f](https://linux-hardware.org/?probe=aca5bf366f) | Apr 26, 2023 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [238598d9ab](https://linux-hardware.org/?probe=238598d9ab) | Apr 26, 2023 |
| Biostar       | H610MH                      | Desktop     | [935928c60d](https://linux-hardware.org/?probe=935928c60d) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | Notebook    | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| Lenovo        | ThinkPad L512 4444PS9       | Notebook    | [78cf80b13b](https://linux-hardware.org/?probe=78cf80b13b) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [84bc235979](https://linux-hardware.org/?probe=84bc235979) | Apr 26, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [a63293fe36](https://linux-hardware.org/?probe=a63293fe36) | Apr 26, 2023 |
| Fujitsu       | FMVA05004                   | Notebook    | [c494a8453d](https://linux-hardware.org/?probe=c494a8453d) | Apr 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [208f6823ed](https://linux-hardware.org/?probe=208f6823ed) | Apr 26, 2023 |
| Acer          | Aspire TC-605               | Desktop     | [b9dcc7f752](https://linux-hardware.org/?probe=b9dcc7f752) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2349BS7       | Notebook    | [8d832f0261](https://linux-hardware.org/?probe=8d832f0261) | Apr 26, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [b8b58af983](https://linux-hardware.org/?probe=b8b58af983) | Apr 26, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [00bf0576c4](https://linux-hardware.org/?probe=00bf0576c4) | Apr 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4f1e4da37e](https://linux-hardware.org/?probe=4f1e4da37e) | Apr 26, 2023 |
| Toshiba       | dynabook TV/68KBL           | Notebook    | [19c59e3701](https://linux-hardware.org/?probe=19c59e3701) | Apr 26, 2023 |
| Intel         | H81                         | Desktop     | [9a14132581](https://linux-hardware.org/?probe=9a14132581) | Apr 26, 2023 |
| ASUSTek       | X550VQ                      | Notebook    | [3c7d8a0268](https://linux-hardware.org/?probe=3c7d8a0268) | Apr 26, 2023 |
| HP            | 83E2                        | Desktop     | [f10d975821](https://linux-hardware.org/?probe=f10d975821) | Apr 26, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [8a0cd0bb6e](https://linux-hardware.org/?probe=8a0cd0bb6e) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| Dell          | 0RCGCR A04                  | Server      | [8ef63cb2de](https://linux-hardware.org/?probe=8ef63cb2de) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [2e6de51ded](https://linux-hardware.org/?probe=2e6de51ded) | Apr 26, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [5c79032176](https://linux-hardware.org/?probe=5c79032176) | Apr 25, 2023 |
| HP            | 3029h                       | Desktop     | [35be4d25c4](https://linux-hardware.org/?probe=35be4d25c4) | Apr 25, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [e46f340908](https://linux-hardware.org/?probe=e46f340908) | Apr 25, 2023 |
| HP            | Pavilion g4                 | Notebook    | [5e2040a91f](https://linux-hardware.org/?probe=5e2040a91f) | Apr 25, 2023 |
| ASRock        | AB350M-HDV                  | Desktop     | [44ac797451](https://linux-hardware.org/?probe=44ac797451) | Apr 25, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e2f309bb08](https://linux-hardware.org/?probe=e2f309bb08) | Apr 25, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [f132c966f5](https://linux-hardware.org/?probe=f132c966f5) | Apr 25, 2023 |
| Login Info... | LOG-S14BW01-CD              | Notebook    | [5f6e2a61f2](https://linux-hardware.org/?probe=5f6e2a61f2) | Apr 25, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [ae90303c3a](https://linux-hardware.org/?probe=ae90303c3a) | Apr 25, 2023 |
| ASUSTek       | J1800I-C                    | Desktop     | [0a58f3fa51](https://linux-hardware.org/?probe=0a58f3fa51) | Apr 25, 2023 |
| Lenovo        | ThinkCentre A70z 0401G6G    | Desktop     | [b1b8bf3df6](https://linux-hardware.org/?probe=b1b8bf3df6) | Apr 25, 2023 |
| Sony          | VPCS13V9E                   | Notebook    | [3c1551d7be](https://linux-hardware.org/?probe=3c1551d7be) | Apr 25, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [693f0cea98](https://linux-hardware.org/?probe=693f0cea98) | Apr 25, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [a433dd6737](https://linux-hardware.org/?probe=a433dd6737) | Apr 25, 2023 |
| Dell          | 0773VG A01                  | Desktop     | [40cf2f15c2](https://linux-hardware.org/?probe=40cf2f15c2) | Apr 25, 2023 |
| Lenovo        | ThinkPad SL500 2746CTO      | Notebook    | [7283a0f4d9](https://linux-hardware.org/?probe=7283a0f4d9) | Apr 25, 2023 |
| HP            | Compaq 15                   | Notebook    | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| HP            | 18E9                        | Desktop     | [b9bb679cca](https://linux-hardware.org/?probe=b9bb679cca) | Apr 25, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [a437a858a4](https://linux-hardware.org/?probe=a437a858a4) | Apr 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c5adfbd376](https://linux-hardware.org/?probe=c5adfbd376) | Apr 25, 2023 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [405bcbb43c](https://linux-hardware.org/?probe=405bcbb43c) | Apr 25, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [09c7ae9819](https://linux-hardware.org/?probe=09c7ae9819) | Apr 25, 2023 |
| Toshiba       | Satellite L305D             | Notebook    | [1bbf3a5e9c](https://linux-hardware.org/?probe=1bbf3a5e9c) | Apr 25, 2023 |
| ICL           | RAYbook Si1512              | Notebook    | [6aa907fd2e](https://linux-hardware.org/?probe=6aa907fd2e) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [915147a191](https://linux-hardware.org/?probe=915147a191) | Apr 25, 2023 |
| Fujitsu       | LIFEBOOK S935               | Notebook    | [418c2c626e](https://linux-hardware.org/?probe=418c2c626e) | Apr 25, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [92a968e58d](https://linux-hardware.org/?probe=92a968e58d) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | Notebook    | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| HP            | ProBook 5320m               | Notebook    | [7597710994](https://linux-hardware.org/?probe=7597710994) | Apr 24, 2023 |
| Dell          | Latitude XT2                | Notebook    | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [d9ad034d8c](https://linux-hardware.org/?probe=d9ad034d8c) | Apr 24, 2023 |
| Medion        | X681X                       | Notebook    | [d72837ad07](https://linux-hardware.org/?probe=d72837ad07) | Apr 24, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [0e79aaac72](https://linux-hardware.org/?probe=0e79aaac72) | Apr 24, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [fdcfb2bde7](https://linux-hardware.org/?probe=fdcfb2bde7) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b72361ca9e](https://linux-hardware.org/?probe=b72361ca9e) | Apr 24, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T5... | Notebook    | [587e06aeb7](https://linux-hardware.org/?probe=587e06aeb7) | Apr 24, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [b4d8bd0f23](https://linux-hardware.org/?probe=b4d8bd0f23) | Apr 24, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [961a066e6b](https://linux-hardware.org/?probe=961a066e6b) | Apr 24, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [0842334fa2](https://linux-hardware.org/?probe=0842334fa2) | Apr 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [6531aafbfe](https://linux-hardware.org/?probe=6531aafbfe) | Apr 24, 2023 |
| Acer          | Aspire V5-552P              | Notebook    | [28c276f9da](https://linux-hardware.org/?probe=28c276f9da) | Apr 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [6f3f14d26d](https://linux-hardware.org/?probe=6f3f14d26d) | Apr 23, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [538ebf1f96](https://linux-hardware.org/?probe=538ebf1f96) | Apr 23, 2023 |
| Toshiba       | Satellite C855              | Notebook    | [b383279bda](https://linux-hardware.org/?probe=b383279bda) | Apr 23, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [9ba55985fd](https://linux-hardware.org/?probe=9ba55985fd) | Apr 23, 2023 |
| HP            | 0AA8h                       | Desktop     | [b927834a03](https://linux-hardware.org/?probe=b927834a03) | Apr 23, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [22594512d1](https://linux-hardware.org/?probe=22594512d1) | Apr 23, 2023 |
| Shenzhen M... | F6CQW                       | Desktop     | [c2be3dd62b](https://linux-hardware.org/?probe=c2be3dd62b) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e72f221b5b](https://linux-hardware.org/?probe=e72f221b5b) | Apr 23, 2023 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [ec36f4ada2](https://linux-hardware.org/?probe=ec36f4ada2) | Apr 23, 2023 |
| Lenovo        | G550 2958                   | Notebook    | [7a1a8bb421](https://linux-hardware.org/?probe=7a1a8bb421) | Apr 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [cc80f06375](https://linux-hardware.org/?probe=cc80f06375) | Apr 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [3fa24b1a91](https://linux-hardware.org/?probe=3fa24b1a91) | Apr 23, 2023 |
| Toshiba       | dynabook BX/67TG            | Notebook    | [5349d462cd](https://linux-hardware.org/?probe=5349d462cd) | Apr 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [93790f1835](https://linux-hardware.org/?probe=93790f1835) | Apr 23, 2023 |
| Acer          | Spin SP315-51               | Convertible | [42da7880dd](https://linux-hardware.org/?probe=42da7880dd) | Apr 23, 2023 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [bf1dbf49a8](https://linux-hardware.org/?probe=bf1dbf49a8) | Apr 22, 2023 |
| Gigabyte      | EP45-UD3                    | Desktop     | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [6115e5ccd4](https://linux-hardware.org/?probe=6115e5ccd4) | Apr 22, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [e2276c080b](https://linux-hardware.org/?probe=e2276c080b) | Apr 22, 2023 |
| Intel         | NUC12WSBi5 M46425-303       | Mini pc     | [9d1c8d691f](https://linux-hardware.org/?probe=9d1c8d691f) | Apr 22, 2023 |
| Biostar       | A75MG                       | Desktop     | [50cb5c256e](https://linux-hardware.org/?probe=50cb5c256e) | Apr 22, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [36ec2bb4c2](https://linux-hardware.org/?probe=36ec2bb4c2) | Apr 22, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [a7fc39a85b](https://linux-hardware.org/?probe=a7fc39a85b) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [2ff545a3fc](https://linux-hardware.org/?probe=2ff545a3fc) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [63599179ae](https://linux-hardware.org/?probe=63599179ae) | Apr 22, 2023 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [59ad89854c](https://linux-hardware.org/?probe=59ad89854c) | Apr 22, 2023 |
| HP            | ProBook 4330s               | Notebook    | [f6608ffee2](https://linux-hardware.org/?probe=f6608ffee2) | Apr 22, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [485f002152](https://linux-hardware.org/?probe=485f002152) | Apr 22, 2023 |
| Fujitsu       | FJNB037                     | Desktop     | [00e5e30f9b](https://linux-hardware.org/?probe=00e5e30f9b) | Apr 22, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [2d1b73d846](https://linux-hardware.org/?probe=2d1b73d846) | Apr 22, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [8f3546722b](https://linux-hardware.org/?probe=8f3546722b) | Apr 22, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Acer          | Spin SP314-51               | Convertible | [5fd72bcee7](https://linux-hardware.org/?probe=5fd72bcee7) | Apr 22, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [820acdb913](https://linux-hardware.org/?probe=820acdb913) | Apr 22, 2023 |
| MSI           | B360M BAZOOKA               | Desktop     | [46516c6f3a](https://linux-hardware.org/?probe=46516c6f3a) | Apr 22, 2023 |
| Fujitsu Si... | D2156-A1 S26361-D2156-A1    | Desktop     | [617f821f9a](https://linux-hardware.org/?probe=617f821f9a) | Apr 22, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [015e857f63](https://linux-hardware.org/?probe=015e857f63) | Apr 22, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [6a17fe6ead](https://linux-hardware.org/?probe=6a17fe6ead) | Apr 21, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Notebook    | [503c99202e](https://linux-hardware.org/?probe=503c99202e) | Apr 21, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [6f49f4b883](https://linux-hardware.org/?probe=6f49f4b883) | Apr 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b3613186fa](https://linux-hardware.org/?probe=b3613186fa) | Apr 21, 2023 |
| Intel         | DB65AL AAG12530-310         | Desktop     | [c625f3747a](https://linux-hardware.org/?probe=c625f3747a) | Apr 21, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [51ee77485d](https://linux-hardware.org/?probe=51ee77485d) | Apr 21, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [cde822d71c](https://linux-hardware.org/?probe=cde822d71c) | Apr 21, 2023 |
| HP            | 18E5                        | Desktop     | [0437b3deb1](https://linux-hardware.org/?probe=0437b3deb1) | Apr 21, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [78adec215e](https://linux-hardware.org/?probe=78adec215e) | Apr 21, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [422eb87f07](https://linux-hardware.org/?probe=422eb87f07) | Apr 21, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [a315eaa776](https://linux-hardware.org/?probe=a315eaa776) | Apr 21, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [c974888840](https://linux-hardware.org/?probe=c974888840) | Apr 21, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [6720e15331](https://linux-hardware.org/?probe=6720e15331) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [fc70e3e9e0](https://linux-hardware.org/?probe=fc70e3e9e0) | Apr 21, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [fd91075868](https://linux-hardware.org/?probe=fd91075868) | Apr 21, 2023 |
| HP            | Compaq 6720s                | Notebook    | [b980c3c57d](https://linux-hardware.org/?probe=b980c3c57d) | Apr 21, 2023 |
| ASUSTek       | PN62S                       | Mini pc     | [8b7d9ca6fd](https://linux-hardware.org/?probe=8b7d9ca6fd) | Apr 21, 2023 |
| MouseCompu... | Z87-S01                     | Desktop     | [8caff0d2f2](https://linux-hardware.org/?probe=8caff0d2f2) | Apr 21, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | Notebook    | [da51714544](https://linux-hardware.org/?probe=da51714544) | Apr 21, 2023 |
| ASRock        | P43DE                       | Desktop     | [8f2c0ecc69](https://linux-hardware.org/?probe=8f2c0ecc69) | Apr 21, 2023 |
| ASRock        | Z270 Taichi                 | Desktop     | [faf3402431](https://linux-hardware.org/?probe=faf3402431) | Apr 21, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [0a153df418](https://linux-hardware.org/?probe=0a153df418) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [5f1a1c6abd](https://linux-hardware.org/?probe=5f1a1c6abd) | Apr 20, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [11ea81f23c](https://linux-hardware.org/?probe=11ea81f23c) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | Notebook    | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| Acer          | Aspire 5745                 | Notebook    | [19e6d70ce0](https://linux-hardware.org/?probe=19e6d70ce0) | Apr 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [44459cbe3a](https://linux-hardware.org/?probe=44459cbe3a) | Apr 20, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [f2fc6a5da5](https://linux-hardware.org/?probe=f2fc6a5da5) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| Intel         | DG43GT AAE62768-301         | Desktop     | [643ed4ce33](https://linux-hardware.org/?probe=643ed4ce33) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [a09ea158cc](https://linux-hardware.org/?probe=a09ea158cc) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| Dell          | Latitude 5400               | Notebook    | [f0e05c9726](https://linux-hardware.org/?probe=f0e05c9726) | Apr 20, 2023 |
| ASUSTek       | P5K SE                      | Desktop     | [eeff4cd84c](https://linux-hardware.org/?probe=eeff4cd84c) | Apr 20, 2023 |
| HP            | G62                         | Notebook    | [a0096bb254](https://linux-hardware.org/?probe=a0096bb254) | Apr 20, 2023 |
| Gigabyte      | H81N                        | Desktop     | [5729c6c6a9](https://linux-hardware.org/?probe=5729c6c6a9) | Apr 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [561b87c8b4](https://linux-hardware.org/?probe=561b87c8b4) | Apr 20, 2023 |
| MSI           | GE62 6QD                    | Notebook    | [785d4c1655](https://linux-hardware.org/?probe=785d4c1655) | Apr 20, 2023 |
| Toshiba       | dynabook T451/46EW          | Notebook    | [e45702b9aa](https://linux-hardware.org/?probe=e45702b9aa) | Apr 20, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [0c45fc6929](https://linux-hardware.org/?probe=0c45fc6929) | Apr 20, 2023 |
| Intel         | H61S                        | Desktop     | [e29d71587a](https://linux-hardware.org/?probe=e29d71587a) | Apr 20, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [68a7470480](https://linux-hardware.org/?probe=68a7470480) | Apr 19, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [14d03d2dd7](https://linux-hardware.org/?probe=14d03d2dd7) | Apr 19, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| HP            | 18E4                        | Desktop     | [1bd96a017f](https://linux-hardware.org/?probe=1bd96a017f) | Apr 19, 2023 |
| ASUSTek       | N501VW                      | Notebook    | [a31036cae1](https://linux-hardware.org/?probe=a31036cae1) | Apr 19, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [6a0eced5fc](https://linux-hardware.org/?probe=6a0eced5fc) | Apr 19, 2023 |
| ASRock        | B560M-HDV                   | Desktop     | [b835e48fad](https://linux-hardware.org/?probe=b835e48fad) | Apr 19, 2023 |
| Lenovo        | G780 20138                  | Notebook    | [32360109fa](https://linux-hardware.org/?probe=32360109fa) | Apr 19, 2023 |
| ASUSTek       | UX305CA                     | Notebook    | [0ff08e0727](https://linux-hardware.org/?probe=0ff08e0727) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [9c7e865b56](https://linux-hardware.org/?probe=9c7e865b56) | Apr 19, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [53d3a8d066](https://linux-hardware.org/?probe=53d3a8d066) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | Notebook    | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| ECS           | BSW-MINI                    | Desktop     | [5d3161092f](https://linux-hardware.org/?probe=5d3161092f) | Apr 19, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [de205c8c62](https://linux-hardware.org/?probe=de205c8c62) | Apr 19, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [5cbbc95995](https://linux-hardware.org/?probe=5cbbc95995) | Apr 19, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [5fa6c74be4](https://linux-hardware.org/?probe=5fa6c74be4) | Apr 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0W    | Notebook    | [97447a0777](https://linux-hardware.org/?probe=97447a0777) | Apr 19, 2023 |
| MSI           | 0B58h                       | Desktop     | [6473456480](https://linux-hardware.org/?probe=6473456480) | Apr 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [c5639cddcb](https://linux-hardware.org/?probe=c5639cddcb) | Apr 19, 2023 |
| ECS           | H61H2-CM                    | Desktop     | [4396b0b045](https://linux-hardware.org/?probe=4396b0b045) | Apr 19, 2023 |
| Lenovo        | ThinkPad T540p 20BECTO1W... | Notebook    | [ccb7f92798](https://linux-hardware.org/?probe=ccb7f92798) | Apr 19, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [4e95dc284c](https://linux-hardware.org/?probe=4e95dc284c) | Apr 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6fae9a24fb](https://linux-hardware.org/?probe=6fae9a24fb) | Apr 19, 2023 |
| HP            | 8309                        | Desktop     | [d82a6a4488](https://linux-hardware.org/?probe=d82a6a4488) | Apr 19, 2023 |
| HP            | Unknown                     | Notebook    | [5a295b02bc](https://linux-hardware.org/?probe=5a295b02bc) | Apr 19, 2023 |
| MSI           | MS-7235                     | Desktop     | [efaeac524b](https://linux-hardware.org/?probe=efaeac524b) | Apr 18, 2023 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [76aabd80a0](https://linux-hardware.org/?probe=76aabd80a0) | Apr 18, 2023 |
| Acer          | AO722                       | Notebook    | [5fe24a9991](https://linux-hardware.org/?probe=5fe24a9991) | Apr 18, 2023 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | Desktop     | [10693010af](https://linux-hardware.org/?probe=10693010af) | Apr 18, 2023 |
| Biostar       | A960D+V2                    | Desktop     | [34c47b4141](https://linux-hardware.org/?probe=34c47b4141) | Apr 18, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [fb3d31599f](https://linux-hardware.org/?probe=fb3d31599f) | Apr 18, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [9437766194](https://linux-hardware.org/?probe=9437766194) | Apr 18, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [99ea2c7790](https://linux-hardware.org/?probe=99ea2c7790) | Apr 18, 2023 |
| NEC Comput... | MS-7451VM                   | Desktop     | [dc094ceba3](https://linux-hardware.org/?probe=dc094ceba3) | Apr 18, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [4c6abc2653](https://linux-hardware.org/?probe=4c6abc2653) | Apr 18, 2023 |
| Acer          | Swift SF314-52              | Notebook    | [5fc210eaf2](https://linux-hardware.org/?probe=5fc210eaf2) | Apr 18, 2023 |
| ASUSTek       | P5QC                        | Desktop     | [7d47aa511b](https://linux-hardware.org/?probe=7d47aa511b) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [dc707578c9](https://linux-hardware.org/?probe=dc707578c9) | Apr 18, 2023 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [9eb59318e2](https://linux-hardware.org/?probe=9eb59318e2) | Apr 18, 2023 |
| Lenovo        | B50-30 20382                | Notebook    | [d8995dacdc](https://linux-hardware.org/?probe=d8995dacdc) | Apr 18, 2023 |
| Acer          | FQ965M MP                   | Desktop     | [9be9793747](https://linux-hardware.org/?probe=9be9793747) | Apr 18, 2023 |
| Fujitsu       | FMVNA6HE                    | Notebook    | [609572e6f7](https://linux-hardware.org/?probe=609572e6f7) | Apr 18, 2023 |
| Lenovo        | ThinkPad P53 20QN001YUS     | Notebook    | [59549202bd](https://linux-hardware.org/?probe=59549202bd) | Apr 18, 2023 |
| HP            | 18E9                        | Desktop     | [8c36235f13](https://linux-hardware.org/?probe=8c36235f13) | Apr 18, 2023 |
| Gigabyte      | H370 AORUS GAMING 3-CF      | Desktop     | [8b585cf135](https://linux-hardware.org/?probe=8b585cf135) | Apr 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fa475c8ca8](https://linux-hardware.org/?probe=fa475c8ca8) | Apr 17, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [8944559c50](https://linux-hardware.org/?probe=8944559c50) | Apr 17, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [e7d992accf](https://linux-hardware.org/?probe=e7d992accf) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | Notebook    | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Samsung       | 930QED                      | Convertible | [fdfe04c5c9](https://linux-hardware.org/?probe=fdfe04c5c9) | Apr 17, 2023 |
| Medion        | P6634                       | Notebook    | [bb900074b5](https://linux-hardware.org/?probe=bb900074b5) | Apr 17, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8166aa6314](https://linux-hardware.org/?probe=8166aa6314) | Apr 17, 2023 |
| ASUSTek       | UX303LB                     | Notebook    | [48c19abe8c](https://linux-hardware.org/?probe=48c19abe8c) | Apr 17, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| HP            | 1850                        | Desktop     | [fa2fa68792](https://linux-hardware.org/?probe=fa2fa68792) | Apr 17, 2023 |
| HP            | 8062                        | Desktop     | [a2558d47e8](https://linux-hardware.org/?probe=a2558d47e8) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| Lenovo        | G580                        | Notebook    | [e291c2c0aa](https://linux-hardware.org/?probe=e291c2c0aa) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4174faae23](https://linux-hardware.org/?probe=4174faae23) | Apr 17, 2023 |
| Medion        | E16401                      | Notebook    | [e6c20783e7](https://linux-hardware.org/?probe=e6c20783e7) | Apr 17, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| Dell          | Latitude D830               | Notebook    | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [8e99149abe](https://linux-hardware.org/?probe=8e99149abe) | Apr 17, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | Notebook    | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [695446a864](https://linux-hardware.org/?probe=695446a864) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a2b27dd2d6](https://linux-hardware.org/?probe=a2b27dd2d6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [14517ef743](https://linux-hardware.org/?probe=14517ef743) | Apr 17, 2023 |
| ASRock        | X99 Extreme4                | Desktop     | [e375be2ea6](https://linux-hardware.org/?probe=e375be2ea6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [66104cc9cf](https://linux-hardware.org/?probe=66104cc9cf) | Apr 16, 2023 |
| Medion        | MS-7728                     | Desktop     | [1da2d605db](https://linux-hardware.org/?probe=1da2d605db) | Apr 16, 2023 |
| Acer          | Aspire X3950                | Desktop     | [5a9abbd85f](https://linux-hardware.org/?probe=5a9abbd85f) | Apr 16, 2023 |
| eMachines     | E945GCU                     | Desktop     | [4e6aa4be24](https://linux-hardware.org/?probe=4e6aa4be24) | Apr 16, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | Notebook    | [f44bbda528](https://linux-hardware.org/?probe=f44bbda528) | Apr 16, 2023 |
| ASUSTek       | X99-A/USB                   | Desktop     | [d686a4d03c](https://linux-hardware.org/?probe=d686a4d03c) | Apr 16, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [01452c33d1](https://linux-hardware.org/?probe=01452c33d1) | Apr 16, 2023 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [0134b33f82](https://linux-hardware.org/?probe=0134b33f82) | Apr 16, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6ac02f43f2](https://linux-hardware.org/?probe=6ac02f43f2) | Apr 16, 2023 |
| Samsung       | 950QDB                      | Convertible | [29ae07c7f1](https://linux-hardware.org/?probe=29ae07c7f1) | Apr 16, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [3ad1ee8197](https://linux-hardware.org/?probe=3ad1ee8197) | Apr 16, 2023 |
| ASRock        | N68-GS4 FX                  | Desktop     | [19a6cddfe0](https://linux-hardware.org/?probe=19a6cddfe0) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| Dell          | 0RF705                      | Desktop     | [32dbb3206b](https://linux-hardware.org/?probe=32dbb3206b) | Apr 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a2596e8d06](https://linux-hardware.org/?probe=a2596e8d06) | Apr 16, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [71643d03ec](https://linux-hardware.org/?probe=71643d03ec) | Apr 16, 2023 |
| Dell          | Precision 7510              | Notebook    | [abb2d93e32](https://linux-hardware.org/?probe=abb2d93e32) | Apr 16, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [fedecfd9ff](https://linux-hardware.org/?probe=fedecfd9ff) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Foxconn       | ALOE                        | Desktop     | [702f958604](https://linux-hardware.org/?probe=702f958604) | Apr 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [980c6d63d6](https://linux-hardware.org/?probe=980c6d63d6) | Apr 16, 2023 |
| Lenovo        | SHARKBAY SDK0J40700 WIN ... | Desktop     | [00b59d56cd](https://linux-hardware.org/?probe=00b59d56cd) | Apr 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [fad0ef7fef](https://linux-hardware.org/?probe=fad0ef7fef) | Apr 16, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0853728b34](https://linux-hardware.org/?probe=0853728b34) | Apr 16, 2023 |
| MSI           | B150A GAMING PRO            | Desktop     | [26432a7622](https://linux-hardware.org/?probe=26432a7622) | Apr 16, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [360f364ebf](https://linux-hardware.org/?probe=360f364ebf) | Apr 15, 2023 |
| ASUSTek       | K73E                        | Notebook    | [9ab8e37631](https://linux-hardware.org/?probe=9ab8e37631) | Apr 15, 2023 |
| Fujitsu Si... | ESPRIMO Mobile X9515        | Notebook    | [82ffd0e4bd](https://linux-hardware.org/?probe=82ffd0e4bd) | Apr 15, 2023 |
| Dell          | Inspiron MM061              | Notebook    | [b825c609a9](https://linux-hardware.org/?probe=b825c609a9) | Apr 15, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [6c711c5197](https://linux-hardware.org/?probe=6c711c5197) | Apr 15, 2023 |
| Dell          | Precision 7730              | Notebook    | [0e434903ec](https://linux-hardware.org/?probe=0e434903ec) | Apr 15, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [c655afe860](https://linux-hardware.org/?probe=c655afe860) | Apr 15, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [337102cd4c](https://linux-hardware.org/?probe=337102cd4c) | Apr 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [7ac461b735](https://linux-hardware.org/?probe=7ac461b735) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Gigabyte      | F2A85XN-WIFI                | Desktop     | [80a8d69a06](https://linux-hardware.org/?probe=80a8d69a06) | Apr 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS0CW00    | Notebook    | [2d25abe83c](https://linux-hardware.org/?probe=2d25abe83c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [2e860ef402](https://linux-hardware.org/?probe=2e860ef402) | Apr 15, 2023 |
| Foxconn       | 2A8C                        | Desktop     | [8a75d034c7](https://linux-hardware.org/?probe=8a75d034c7) | Apr 15, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [e17175b9ac](https://linux-hardware.org/?probe=e17175b9ac) | Apr 15, 2023 |
| ASUSTek       | M51Vr                       | Notebook    | [27d265c73d](https://linux-hardware.org/?probe=27d265c73d) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [83d43e489d](https://linux-hardware.org/?probe=83d43e489d) | Apr 15, 2023 |
| GPD           | G1619-01                    | Notebook    | [2edac2c38e](https://linux-hardware.org/?probe=2edac2c38e) | Apr 15, 2023 |
| Lenovo        | ThinkCentre M58p 6234CZ6    | Desktop     | [e412c388d8](https://linux-hardware.org/?probe=e412c388d8) | Apr 15, 2023 |
| MSI           | Prestige 15 A12SC           | Notebook    | [51259c6f0a](https://linux-hardware.org/?probe=51259c6f0a) | Apr 15, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [82abb09c06](https://linux-hardware.org/?probe=82abb09c06) | Apr 15, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [dfed605628](https://linux-hardware.org/?probe=dfed605628) | Apr 15, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [a359e8f3ea](https://linux-hardware.org/?probe=a359e8f3ea) | Apr 15, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [f960c27052](https://linux-hardware.org/?probe=f960c27052) | Apr 14, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [f3b7c9c255](https://linux-hardware.org/?probe=f3b7c9c255) | Apr 14, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [44cdfb0917](https://linux-hardware.org/?probe=44cdfb0917) | Apr 14, 2023 |
| ASUSTek       | ROG Strix G532LWS_G532LW... | Notebook    | [a5cb4f9095](https://linux-hardware.org/?probe=a5cb4f9095) | Apr 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [8a5b5b102c](https://linux-hardware.org/?probe=8a5b5b102c) | Apr 14, 2023 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [d5669e92ed](https://linux-hardware.org/?probe=d5669e92ed) | Apr 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [429e68a4ac](https://linux-hardware.org/?probe=429e68a4ac) | Apr 14, 2023 |
| Gigabyte      | P55-UD3R                    | Desktop     | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [3741318176](https://linux-hardware.org/?probe=3741318176) | Apr 14, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [981bad2be2](https://linux-hardware.org/?probe=981bad2be2) | Apr 14, 2023 |
| Acer          | AO756                       | Notebook    | [c17d5276ec](https://linux-hardware.org/?probe=c17d5276ec) | Apr 14, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [dc9e77bd65](https://linux-hardware.org/?probe=dc9e77bd65) | Apr 14, 2023 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [d7d5674aa5](https://linux-hardware.org/?probe=d7d5674aa5) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [e3f3f9fd2b](https://linux-hardware.org/?probe=e3f3f9fd2b) | Apr 14, 2023 |
| HP            | Pavilion dv6                | Notebook    | [3f719938aa](https://linux-hardware.org/?probe=3f719938aa) | Apr 14, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [62bdfa97bd](https://linux-hardware.org/?probe=62bdfa97bd) | Apr 14, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [8fb8771c70](https://linux-hardware.org/?probe=8fb8771c70) | Apr 14, 2023 |
| BANGHO        | MAX G0101                   | Notebook    | [d1ed9e6040](https://linux-hardware.org/?probe=d1ed9e6040) | Apr 14, 2023 |
| HP            | 1791                        | Desktop     | [c87bf6d0e1](https://linux-hardware.org/?probe=c87bf6d0e1) | Apr 13, 2023 |
| Dell          | Latitude E6540              | Notebook    | [61ab891b01](https://linux-hardware.org/?probe=61ab891b01) | Apr 13, 2023 |
| ASUSTek       | K73TA                       | Notebook    | [34319e673a](https://linux-hardware.org/?probe=34319e673a) | Apr 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [1bf207dfca](https://linux-hardware.org/?probe=1bf207dfca) | Apr 13, 2023 |
| Gigabyte      | MQHUDVI                     | All in one  | [1dc2419a21](https://linux-hardware.org/?probe=1dc2419a21) | Apr 13, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| HP            | 1589                        | Desktop     | [b1ca06250e](https://linux-hardware.org/?probe=b1ca06250e) | Apr 13, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [947f70ebf7](https://linux-hardware.org/?probe=947f70ebf7) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [d79266b94f](https://linux-hardware.org/?probe=d79266b94f) | Apr 13, 2023 |
| HP            | 3397                        | Desktop     | [0e4d29ffcd](https://linux-hardware.org/?probe=0e4d29ffcd) | Apr 13, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [0519471935](https://linux-hardware.org/?probe=0519471935) | Apr 13, 2023 |
| Toshiba       | Satellite L75D-A            | Notebook    | [210a475989](https://linux-hardware.org/?probe=210a475989) | Apr 13, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [8c2cc310b2](https://linux-hardware.org/?probe=8c2cc310b2) | Apr 13, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [ffdcd55e2e](https://linux-hardware.org/?probe=ffdcd55e2e) | Apr 13, 2023 |
| System76      | Galago Pro                  | Notebook    | [9239e8d213](https://linux-hardware.org/?probe=9239e8d213) | Apr 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [a841c5fce3](https://linux-hardware.org/?probe=a841c5fce3) | Apr 13, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [ea4bae8ef7](https://linux-hardware.org/?probe=ea4bae8ef7) | Apr 13, 2023 |
| MSI           | MS-7360                     | Desktop     | [48bee654fc](https://linux-hardware.org/?probe=48bee654fc) | Apr 13, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [c53ec6a9c0](https://linux-hardware.org/?probe=c53ec6a9c0) | Apr 13, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f983dadfeb](https://linux-hardware.org/?probe=f983dadfeb) | Apr 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [830a3e27dd](https://linux-hardware.org/?probe=830a3e27dd) | Apr 13, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [76595cf176](https://linux-hardware.org/?probe=76595cf176) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [af4ccb91b1](https://linux-hardware.org/?probe=af4ccb91b1) | Apr 12, 2023 |
| HP            | 1998                        | Desktop     | [8f0fef0b77](https://linux-hardware.org/?probe=8f0fef0b77) | Apr 12, 2023 |
| HP            | 805D                        | Desktop     | [f12230e709](https://linux-hardware.org/?probe=f12230e709) | Apr 12, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [551fabbc17](https://linux-hardware.org/?probe=551fabbc17) | Apr 12, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [d98390c8a7](https://linux-hardware.org/?probe=d98390c8a7) | Apr 12, 2023 |
| Dell          | Latitude E6230              | Notebook    | [a7cce7ebde](https://linux-hardware.org/?probe=a7cce7ebde) | Apr 12, 2023 |
| Acer          | Aspire 5733Z                | Notebook    | [b42b19277c](https://linux-hardware.org/?probe=b42b19277c) | Apr 12, 2023 |
| ASUSTek       | K53U                        | Notebook    | [19ec753136](https://linux-hardware.org/?probe=19ec753136) | Apr 12, 2023 |
| Dell          | 02K9CR A01                  | Desktop     | [45c419b8d6](https://linux-hardware.org/?probe=45c419b8d6) | Apr 12, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [db51c5a1f3](https://linux-hardware.org/?probe=db51c5a1f3) | Apr 12, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6ac890debf](https://linux-hardware.org/?probe=6ac890debf) | Apr 12, 2023 |
| Toshiba       | Satellite L350D             | Notebook    | [df4e0aa857](https://linux-hardware.org/?probe=df4e0aa857) | Apr 12, 2023 |
| ASRock        | M3N78D FX                   | Desktop     | [618073d9e9](https://linux-hardware.org/?probe=618073d9e9) | Apr 12, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [203aeef6a1](https://linux-hardware.org/?probe=203aeef6a1) | Apr 12, 2023 |
| Unknown       | SKYBAY                      | Desktop     | [9cd0292459](https://linux-hardware.org/?probe=9cd0292459) | Apr 12, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [63c52bc5db](https://linux-hardware.org/?probe=63c52bc5db) | Apr 12, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [6a6e2f88f4](https://linux-hardware.org/?probe=6a6e2f88f4) | Apr 12, 2023 |
| HP            | Presario CQ62               | Notebook    | [edee5d8480](https://linux-hardware.org/?probe=edee5d8480) | Apr 12, 2023 |
| Samsung       | R460                        | Notebook    | [9908964d4a](https://linux-hardware.org/?probe=9908964d4a) | Apr 11, 2023 |
| ABIT          | NF-M2S                      | Desktop     | [30e3a2e8c4](https://linux-hardware.org/?probe=30e3a2e8c4) | Apr 11, 2023 |
| ASUSTek       | P5LD2-X/1333                | Desktop     | [e0e655f63c](https://linux-hardware.org/?probe=e0e655f63c) | Apr 11, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [2348aee3d4](https://linux-hardware.org/?probe=2348aee3d4) | Apr 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [c67c78ba10](https://linux-hardware.org/?probe=c67c78ba10) | Apr 11, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [238037e4b8](https://linux-hardware.org/?probe=238037e4b8) | Apr 11, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [c52176294b](https://linux-hardware.org/?probe=c52176294b) | Apr 11, 2023 |
| MSI           | 970A GAMING PRO CARBON      | Desktop     | [b6cae4ec58](https://linux-hardware.org/?probe=b6cae4ec58) | Apr 11, 2023 |
| Lenovo        | ThinkPad L580 20LW000VMX    | Notebook    | [7b2e3794c9](https://linux-hardware.org/?probe=7b2e3794c9) | Apr 11, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [ce8b386e5b](https://linux-hardware.org/?probe=ce8b386e5b) | Apr 11, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [5aad144224](https://linux-hardware.org/?probe=5aad144224) | Apr 11, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fc305814c4](https://linux-hardware.org/?probe=fc305814c4) | Apr 11, 2023 |
| Acer          | TM6495T                     | Notebook    | [435ae018a2](https://linux-hardware.org/?probe=435ae018a2) | Apr 11, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [ad8009e647](https://linux-hardware.org/?probe=ad8009e647) | Apr 11, 2023 |
| Avell High... | A52 HYB                     | Notebook    | [0795bca947](https://linux-hardware.org/?probe=0795bca947) | Apr 11, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [cab4258e1b](https://linux-hardware.org/?probe=cab4258e1b) | Apr 11, 2023 |
| Dell          | 0WR7PY A02                  | Desktop     | [2cec768fe1](https://linux-hardware.org/?probe=2cec768fe1) | Apr 11, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [eb294beef7](https://linux-hardware.org/?probe=eb294beef7) | Apr 11, 2023 |
| HP            | 805B                        | Desktop     | [591658775d](https://linux-hardware.org/?probe=591658775d) | Apr 11, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [52b464bfd3](https://linux-hardware.org/?probe=52b464bfd3) | Apr 10, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [07b7bedac7](https://linux-hardware.org/?probe=07b7bedac7) | Apr 10, 2023 |
| Lenovo        | 3000 V200 07642XU           | Notebook    | [365e3a50d2](https://linux-hardware.org/?probe=365e3a50d2) | Apr 10, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [a5bf121256](https://linux-hardware.org/?probe=a5bf121256) | Apr 10, 2023 |
| ASUSTek       | G751JY                      | Notebook    | [618a195c21](https://linux-hardware.org/?probe=618a195c21) | Apr 10, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e2cffb810b](https://linux-hardware.org/?probe=e2cffb810b) | Apr 10, 2023 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [56f4b51911](https://linux-hardware.org/?probe=56f4b51911) | Apr 10, 2023 |
| Biostar       | H61MHV                      | Desktop     | [13b4632c72](https://linux-hardware.org/?probe=13b4632c72) | Apr 10, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [35f953cfe0](https://linux-hardware.org/?probe=35f953cfe0) | Apr 10, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [979e7ab8f3](https://linux-hardware.org/?probe=979e7ab8f3) | Apr 10, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e043c1c94c](https://linux-hardware.org/?probe=e043c1c94c) | Apr 10, 2023 |
| ASUSTek       | UX303UB                     | Notebook    | [f94b0ee950](https://linux-hardware.org/?probe=f94b0ee950) | Apr 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | Desktop     | [bf18b5af69](https://linux-hardware.org/?probe=bf18b5af69) | Apr 10, 2023 |
| HP            | 3032h                       | Desktop     | [824604840a](https://linux-hardware.org/?probe=824604840a) | Apr 10, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [da4c241466](https://linux-hardware.org/?probe=da4c241466) | Apr 10, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [34f1e1686e](https://linux-hardware.org/?probe=34f1e1686e) | Apr 10, 2023 |
| Lenovo        | ThinkPad X201 3680WFQ       | Notebook    | [f90c2d47c7](https://linux-hardware.org/?probe=f90c2d47c7) | Apr 10, 2023 |
| Lanix         | ChiefRiver                  | Desktop     | [ef23ac88e4](https://linux-hardware.org/?probe=ef23ac88e4) | Apr 10, 2023 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [5964d01442](https://linux-hardware.org/?probe=5964d01442) | Apr 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [502c993dfd](https://linux-hardware.org/?probe=502c993dfd) | Apr 10, 2023 |
| Biostar       | H81MHV3L                    | Desktop     | [8638a242be](https://linux-hardware.org/?probe=8638a242be) | Apr 10, 2023 |
| HP            | Notebook                    | Notebook    | [4a5d785f73](https://linux-hardware.org/?probe=4a5d785f73) | Apr 09, 2023 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [6fd82ceaec](https://linux-hardware.org/?probe=6fd82ceaec) | Apr 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [332f3ed32f](https://linux-hardware.org/?probe=332f3ed32f) | Apr 09, 2023 |
| Biostar       | A320MH                      | Desktop     | [a2aef00c0c](https://linux-hardware.org/?probe=a2aef00c0c) | Apr 09, 2023 |
| Positivo      | A1000BW                     | Notebook    | [02295facdc](https://linux-hardware.org/?probe=02295facdc) | Apr 09, 2023 |
| Sony          | VPCEB1M1E                   | Notebook    | [c182925286](https://linux-hardware.org/?probe=c182925286) | Apr 09, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [feb08fab62](https://linux-hardware.org/?probe=feb08fab62) | Apr 09, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [854ec28c71](https://linux-hardware.org/?probe=854ec28c71) | Apr 09, 2023 |
| lapbook       | S15 PRO                     | Notebook    | [5a039fc6fb](https://linux-hardware.org/?probe=5a039fc6fb) | Apr 09, 2023 |
| Fujitsu Si... | D2312-A3 S26361-D2312-A3    | Desktop     | [54fabc7712](https://linux-hardware.org/?probe=54fabc7712) | Apr 09, 2023 |
| ASUSTek       | ZN240IC                     | All in one  | [557e50987c](https://linux-hardware.org/?probe=557e50987c) | Apr 09, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [d6cbe10f95](https://linux-hardware.org/?probe=d6cbe10f95) | Apr 09, 2023 |
| Lenovo        | B575 1450ABU                | Notebook    | [ef58d2e8e6](https://linux-hardware.org/?probe=ef58d2e8e6) | Apr 09, 2023 |
| Acer          | Aspire 5538                 | Notebook    | [3128c45dbc](https://linux-hardware.org/?probe=3128c45dbc) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | Notebook    | [8def87668b](https://linux-hardware.org/?probe=8def87668b) | Apr 09, 2023 |
| MACHINIST     | X99-k9 V1.0                 | Desktop     | [650acc25ef](https://linux-hardware.org/?probe=650acc25ef) | Apr 09, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [f2040ffb31](https://linux-hardware.org/?probe=f2040ffb31) | Apr 09, 2023 |
| SLIMBOOK      | EXECUTIVE-14                | Notebook    | [e66056ac2d](https://linux-hardware.org/?probe=e66056ac2d) | Apr 09, 2023 |
| Lenovo        | ThinkPad X131e 33722VU      | Notebook    | [5e2ba16114](https://linux-hardware.org/?probe=5e2ba16114) | Apr 09, 2023 |
| ASRock        | Q1900M                      | Desktop     | [6ff7177033](https://linux-hardware.org/?probe=6ff7177033) | Apr 09, 2023 |
| Pegatron      | 2A73h                       | Desktop     | [5de48bf7df](https://linux-hardware.org/?probe=5de48bf7df) | Apr 09, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [a2860baaee](https://linux-hardware.org/?probe=a2860baaee) | Apr 09, 2023 |
| HP            | 1998                        | Desktop     | [3974cfbb0c](https://linux-hardware.org/?probe=3974cfbb0c) | Apr 09, 2023 |
| Samsung       | RV419                       | Notebook    | [88985a3d0d](https://linux-hardware.org/?probe=88985a3d0d) | Apr 09, 2023 |
| Sony          | SVE1713A1EW                 | Notebook    | [402fae93d5](https://linux-hardware.org/?probe=402fae93d5) | Apr 09, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [f36574c96a](https://linux-hardware.org/?probe=f36574c96a) | Apr 09, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [2b039ea053](https://linux-hardware.org/?probe=2b039ea053) | Apr 09, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | Notebook    | [779e8396d6](https://linux-hardware.org/?probe=779e8396d6) | Apr 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d261eb3697](https://linux-hardware.org/?probe=d261eb3697) | Apr 09, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [5244868737](https://linux-hardware.org/?probe=5244868737) | Apr 09, 2023 |
| ASUSTek       | AM1M-A                      | Desktop     | [120f5780bd](https://linux-hardware.org/?probe=120f5780bd) | Apr 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [eab5adc4e6](https://linux-hardware.org/?probe=eab5adc4e6) | Apr 09, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [fe9976de62](https://linux-hardware.org/?probe=fe9976de62) | Apr 09, 2023 |
| Gigabyte      | H370 HD3-CF                 | Desktop     | [b2c9afc61f](https://linux-hardware.org/?probe=b2c9afc61f) | Apr 09, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [03960a3def](https://linux-hardware.org/?probe=03960a3def) | Apr 09, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | Desktop     | [f67448dd99](https://linux-hardware.org/?probe=f67448dd99) | Apr 09, 2023 |
| Google        | Lindar rev3                 | Notebook    | [e6dd3f6805](https://linux-hardware.org/?probe=e6dd3f6805) | Apr 09, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [27df270817](https://linux-hardware.org/?probe=27df270817) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [fa54308baa](https://linux-hardware.org/?probe=fa54308baa) | Apr 09, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [916db99ea5](https://linux-hardware.org/?probe=916db99ea5) | Apr 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [2765290b8c](https://linux-hardware.org/?probe=2765290b8c) | Apr 09, 2023 |
| Dell          | 0Y2MRG A01                  | Desktop     | [d512dee0ba](https://linux-hardware.org/?probe=d512dee0ba) | Apr 09, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [bb9f88795d](https://linux-hardware.org/?probe=bb9f88795d) | Apr 09, 2023 |
| Acer          | Enduro EUN314-51WG          | Notebook    | [7f73117dba](https://linux-hardware.org/?probe=7f73117dba) | Apr 09, 2023 |
| ASUSTek       | P5K                         | Desktop     | [00a17a60bf](https://linux-hardware.org/?probe=00a17a60bf) | Apr 09, 2023 |
| Dell          | Latitude E6420              | Notebook    | [56f5370788](https://linux-hardware.org/?probe=56f5370788) | Apr 09, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [bc18513752](https://linux-hardware.org/?probe=bc18513752) | Apr 09, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [4644a0ea43](https://linux-hardware.org/?probe=4644a0ea43) | Apr 09, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [ea9bd3a740](https://linux-hardware.org/?probe=ea9bd3a740) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7659AB7        | Notebook    | [0b2f9a23ee](https://linux-hardware.org/?probe=0b2f9a23ee) | Apr 09, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [e60f7c9b72](https://linux-hardware.org/?probe=e60f7c9b72) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [c8173d40cd](https://linux-hardware.org/?probe=c8173d40cd) | Apr 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [0f364f6e82](https://linux-hardware.org/?probe=0f364f6e82) | Apr 09, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [436d55c73e](https://linux-hardware.org/?probe=436d55c73e) | Apr 09, 2023 |
| Dell          | Inspiron 7570               | Notebook    | [2bac711aba](https://linux-hardware.org/?probe=2bac711aba) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [2652354b7a](https://linux-hardware.org/?probe=2652354b7a) | Apr 09, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OpenMandriva 4.2    | 4642      | 33.34%  |
| OpenMandriva 4.3    | 4472      | 32.12%  |
| OpenMandriva 23.01  | 1927      | 13.84%  |
| OpenMandriva 23.03  | 1482      | 10.64%  |
| OpenMandriva 4.50   | 867       | 6.23%   |
| OpenMandriva 4.90   | 349       | 2.51%   |
| OpenMandriva 22.12  | 80        | 0.57%   |
| OpenMandriva 23.90  | 40        | 0.29%   |
| OpenMandriva 23.06  | 28        | 0.2%    |
| OpenMandriva 4.1    | 14        | 0.1%    |
| OpenMandriva 22.11  | 8         | 0.06%   |
| OpenMandriva 22.90  | 6         | 0.04%   |
| OpenMandriva 2014.0 | 4         | 0.03%   |
| OpenMandriva 4.0    | 2         | 0.01%   |
| OpenMandriva 3.0    | 2         | 0.01%   |
| OpenMandriva 4.0.1  | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| OpenMandriva | 13289     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002      | 4471      | 31.81%  |
| 5.16.7-desktop-1omv4003       | 4222      | 30.04%  |
| 6.1.1-desktop-1omv2290        | 1760      | 12.52%  |
| 6.2.6-desktop-1omv2390        | 1413      | 10.05%  |
| 5.12.4-desktop-1omv4050       | 372       | 2.65%   |
| 5.18.12-desktop-3omv4090      | 300       | 2.13%   |
| 5.16.13-desktop-1omv4003      | 282       | 2.01%   |
| 5.11.12-desktop-1omv4002      | 210       | 1.49%   |
| 5.19.5-desktop-1omv4090       | 162       | 1.15%   |
| 6.1.4-desktop-1omv2301        | 138       | 0.98%   |
| 5.19.12-desktop-2omv4090      | 123       | 0.88%   |
| 5.14.7-desktop-1omv4050       | 107       | 0.76%   |
| 6.0.10-desktop-2omv22090      | 80        | 0.57%   |
| 6.2.2-desktop-1omv2390        | 43        | 0.31%   |
| 6.3.5-desktop-3omv2390        | 27        | 0.19%   |
| 5.14.14-desktop-1omv4050      | 26        | 0.19%   |
| 5.12.7-desktop-1omv4003       | 22        | 0.16%   |
| 6.2.1-desktop-1omv2390        | 21        | 0.15%   |
| 5.17.1-desktop-2omv4050       | 21        | 0.15%   |
| 5.19.11-desktop-2omv4090      | 17        | 0.12%   |
| 6.0.2-desktop-1omv4090        | 16        | 0.11%   |
| 6.1.2-desktop-1omv2301        | 13        | 0.09%   |
| 5.5.12-desktop-1omv4001       | 12        | 0.09%   |
| 5.11.0-desktop-clang-1omv4002 | 10        | 0.07%   |
| 6.2.0-desktop-0.rc2.1omv2301  | 7         | 0.05%   |
| 6.1.11-desktop-1omv2390       | 7         | 0.05%   |
| 6.0.2-desktop-1omv4050        | 7         | 0.05%   |
| 6.2.8-desktop-1omv2390        | 6         | 0.04%   |
| 5.19.1-desktop-1omv4090       | 6         | 0.04%   |
| 5.18.13-desktop-1omv4090      | 6         | 0.04%   |
| 5.16.3-desktop-2omv4050       | 6         | 0.04%   |
| 6.0.9-desktop-1omv22090       | 5         | 0.04%   |
| 5.10.13-desktop-1omv4002      | 5         | 0.04%   |
| 5.19.0-desktop-1omv4090       | 4         | 0.03%   |
| 5.18.9-desktop-gcc-1omv4090   | 4         | 0.03%   |
| 5.16.5-desktop-2omv4003       | 4         | 0.03%   |
| 6.2.7-desktop-1omv2390        | 3         | 0.02%   |
| 6.1.4-desktop-gcc-1omv2301    | 3         | 0.02%   |
| 5.19.8-desktop-2omv4090       | 3         | 0.02%   |
| 5.16.9-desktop-1omv4003       | 3         | 0.02%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.14 | 4471      | 31.81%  |
| 5.16.7  | 4224      | 30.06%  |
| 6.1.1   | 1760      | 12.52%  |
| 6.2.6   | 1413      | 10.05%  |
| 5.12.4  | 372       | 2.65%   |
| 5.18.12 | 300       | 2.13%   |
| 5.16.13 | 284       | 2.02%   |
| 5.11.12 | 210       | 1.49%   |
| 5.19.5  | 162       | 1.15%   |
| 6.1.4   | 141       | 1%      |
| 5.19.12 | 124       | 0.88%   |
| 5.14.7  | 107       | 0.76%   |
| 6.0.10  | 82        | 0.58%   |
| 6.2.2   | 43        | 0.31%   |
| 6.3.5   | 27        | 0.19%   |
| 5.14.14 | 26        | 0.19%   |
| 5.12.7  | 25        | 0.18%   |
| 6.0.2   | 23        | 0.16%   |
| 5.17.1  | 23        | 0.16%   |
| 6.2.1   | 21        | 0.15%   |
| 5.19.11 | 18        | 0.13%   |
| 6.1.2   | 13        | 0.09%   |
| 5.5.12  | 12        | 0.09%   |
| 5.11.0  | 12        | 0.09%   |
| 6.2.0   | 9         | 0.06%   |
| 6.1.11  | 7         | 0.05%   |
| 6.0.9   | 7         | 0.05%   |
| 6.2.8   | 6         | 0.04%   |
| 5.19.1  | 6         | 0.04%   |
| 5.18.13 | 6         | 0.04%   |
| 5.16.3  | 6         | 0.04%   |
| 6.0.0   | 5         | 0.04%   |
| 5.16.5  | 5         | 0.04%   |
| 5.10.13 | 5         | 0.04%   |
| 6.3.0   | 4         | 0.03%   |
| 5.19.0  | 4         | 0.03%   |
| 5.18.9  | 4         | 0.03%   |
| 5.16.9  | 4         | 0.03%   |
| 5.13.2  | 4         | 0.03%   |
| 6.2.7   | 3         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 4482      | 32.04%  |
| 5.16    | 4465      | 31.92%  |
| 6.1     | 1929      | 13.79%  |
| 6.2     | 1497      | 10.7%   |
| 5.12    | 402       | 2.87%   |
| 5.19    | 320       | 2.29%   |
| 5.18    | 313       | 2.24%   |
| 5.11    | 230       | 1.64%   |
| 5.14    | 134       | 0.96%   |
| 6.0     | 121       | 0.86%   |
| 6.3     | 35        | 0.25%   |
| 5.17    | 25        | 0.18%   |
| 5.5     | 14        | 0.1%    |
| 5.13    | 5         | 0.04%   |
| 4.1     | 4         | 0.03%   |
| 5.15    | 3         | 0.02%   |
| 5.9     | 2         | 0.01%   |
| 5.8     | 2         | 0.01%   |
| 5.1     | 2         | 0.01%   |
| 4.19    | 2         | 0.01%   |
| 5.3     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 13287     | 99.98%  |
| aarch64 | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 12798     | 95.76%  |
| GNOME    | 401       | 3%      |
| LXQt     | 109       | 0.82%   |
| Unknown  | 25        | 0.19%   |
| Cinnamon | 10        | 0.07%   |
| Budgie   | 10        | 0.07%   |
| XFCE     | 8         | 0.06%   |
| KDE4     | 2         | 0.01%   |
| KDE      | 2         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 12879     | 96.56%  |
| Wayland | 456       | 3.42%   |
| Unknown | 2         | 0.01%   |
| Tty     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 12914     | 96.82%  |
| GDM     | 401       | 3.01%   |
| LightDM | 13        | 0.1%    |
| Unknown | 8         | 0.06%   |
| KDM     | 2         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 7237      | 53.46%  |
| de_DE   | 1075      | 7.94%   |
| fr_FR   | 770       | 5.69%   |
| ru_RU   | 754       | 5.57%   |
| pt_BR   | 540       | 3.99%   |
| pl_PL   | 488       | 3.6%    |
| it_IT   | 383       | 2.83%   |
| en_GB   | 336       | 2.48%   |
| es_ES   | 309       | 2.28%   |
| cs_CZ   | 244       | 1.8%    |
| es_MX   | 133       | 0.98%   |
| es_AR   | 100       | 0.74%   |
| de_AT   | 94        | 0.69%   |
| hu_HU   | 90        | 0.66%   |
| en_CA   | 75        | 0.55%   |
| en_AU   | 70        | 0.52%   |
| nl_NL   | 67        | 0.49%   |
| en_IN   | 55        | 0.41%   |
| fr_CA   | 47        | 0.35%   |
| de_CH   | 46        | 0.34%   |
| es_CO   | 44        | 0.33%   |
| pt_PT   | 41        | 0.3%    |
| fr_BE   | 38        | 0.28%   |
| es_CL   | 38        | 0.28%   |
| tr_TR   | 37        | 0.27%   |
| da_DK   | 31        | 0.23%   |
| ru_UA   | 29        | 0.21%   |
| es_VE   | 27        | 0.2%    |
| nl_BE   | 24        | 0.18%   |
| es_PE   | 24        | 0.18%   |
| Unknown | 23        | 0.17%   |
| ro_RO   | 21        | 0.16%   |
| fr_CH   | 19        | 0.14%   |
| es_UY   | 17        | 0.13%   |
| en_NZ   | 14        | 0.1%    |
| nb_NO   | 12        | 0.09%   |
| uk_UA   | 11        | 0.08%   |
| en_ZA   | 11        | 0.08%   |
| en_HK   | 11        | 0.08%   |
| en_AG   | 11        | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 6731      | 50.35%  |
| EFI  | 6638      | 49.65%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 10108     | 73.45%  |
| Ext4     | 3350      | 24.34%  |
| Btrfs    | 187       | 1.36%   |
| F2fs     | 42        | 0.31%   |
| Xfs      | 40        | 0.29%   |
| Ext3     | 10        | 0.07%   |
| Unknown  | 8         | 0.06%   |
| Ext2     | 7         | 0.05%   |
| Jfs      | 6         | 0.04%   |
| Reiserfs | 3         | 0.02%   |
| Tmpfs    | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 8829      | 65.81%  |
| MBR     | 4550      | 33.92%  |
| Unknown | 36        | 0.27%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7455      | 55.13%  |
| No        | 6068      | 44.87%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 7036      | 52.52%  |
| Yes       | 6362      | 47.48%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 2348      | 17.67%  |
| Hewlett-Packard     | 1714      | 12.9%   |
| Lenovo              | 1579      | 11.88%  |
| Dell                | 1557      | 11.72%  |
| Gigabyte Technology | 1121      | 8.44%   |
| Acer                | 891       | 6.7%    |
| MSI                 | 783       | 5.89%   |
| ASRock              | 581       | 4.37%   |
| Toshiba             | 320       | 2.41%   |
| Intel               | 254       | 1.91%   |
| Apple               | 187       | 1.41%   |
| Fujitsu             | 172       | 1.29%   |
| Sony                | 155       | 1.17%   |
| Samsung Electronics | 151       | 1.14%   |
| Medion              | 113       | 0.85%   |
| Unknown             | 79        | 0.59%   |
| Foxconn             | 78        | 0.59%   |
| Pegatron            | 75        | 0.56%   |
| Biostar             | 75        | 0.56%   |
| Positivo            | 73        | 0.55%   |
| Packard Bell        | 64        | 0.48%   |
| ECS                 | 51        | 0.38%   |
| Fujitsu Siemens     | 41        | 0.31%   |
| HUAWEI              | 37        | 0.28%   |
| eMachines           | 33        | 0.25%   |
| AZW                 | 32        | 0.24%   |
| Notebook            | 31        | 0.23%   |
| Microsoft           | 27        | 0.2%    |
| TUXEDO              | 26        | 0.2%    |
| Philco              | 26        | 0.2%    |
| Chuwi               | 25        | 0.19%   |
| BESSTAR Tech        | 25        | 0.19%   |
| Gateway             | 23        | 0.17%   |
| LG Electronics      | 20        | 0.15%   |
| Alienware           | 20        | 0.15%   |
| Supermicro          | 18        | 0.14%   |
| NEC Computers       | 16        | 0.12%   |
| Google              | 16        | 0.12%   |
| Shuttle             | 15        | 0.11%   |
| Compaq              | 13        | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUS All Series                | 131       | 0.99%   |
| ASUS UX31E                     | 122       | 0.92%   |
| Unknown                        | 120       | 0.9%    |
| HP Notebook                    | 66        | 0.5%    |
| Dell Latitude 3120             | 48        | 0.36%   |
| Dell OptiPlex 7010             | 45        | 0.34%   |
| Dell OptiPlex 780              | 37        | 0.28%   |
| Dell Latitude 3190 2-in-1      | 34        | 0.26%   |
| Dell Inspiron 3451             | 32        | 0.24%   |
| ASUS PRIME A320M-K             | 31        | 0.23%   |
| HP Pavilion g6                 | 30        | 0.23%   |
| Dell Latitude 3310             | 29        | 0.22%   |
| Gigabyte H410M H V3            | 27        | 0.2%    |
| Dell OptiPlex 9020             | 26        | 0.2%    |
| Intel H61                      | 25        | 0.19%   |
| HP Pavilion dv6                | 25        | 0.19%   |
| Toshiba dynabook T653/46JR     | 24        | 0.18%   |
| HP EliteDesk 800 G1 SFF        | 24        | 0.18%   |
| Gigabyte 970A-DS3P             | 24        | 0.18%   |
| Dell OptiPlex 3020             | 22        | 0.17%   |
| Sony VGN-FZ31Z                 | 21        | 0.16%   |
| MSI MS-7817                    | 21        | 0.16%   |
| MSI MS-7721                    | 21        | 0.16%   |
| HP Compaq Pro 6300 SFF         | 21        | 0.16%   |
| Dell Latitude E6430            | 21        | 0.16%   |
| ASUS TUF Gaming X570-PLUS      | 21        | 0.16%   |
| MSI MS-7C37                    | 20        | 0.15%   |
| Gigabyte B450M DS3H            | 20        | 0.15%   |
| ASUS SABERTOOTH Z77            | 20        | 0.15%   |
| ASUS PRIME B450M-A             | 20        | 0.15%   |
| MSI MS-7C02                    | 19        | 0.14%   |
| HP Pavilion 15                 | 19        | 0.14%   |
| Gigabyte A320M-S2H             | 19        | 0.14%   |
| Dell OptiPlex 790              | 19        | 0.14%   |
| Dell Inspiron 15-3567          | 19        | 0.14%   |
| ASUS M5A78L-M/USB3             | 18        | 0.14%   |
| HP 15                          | 17        | 0.13%   |
| Dell Latitude E6410            | 17        | 0.13%   |
| Dell Latitude D630             | 17        | 0.13%   |
| Lenovo IdeaPad S145-15AST 81N3 | 16        | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 634       | 4.77%   |
| Dell Latitude         | 537       | 4.04%   |
| Lenovo ThinkPad       | 520       | 3.91%   |
| Lenovo IdeaPad        | 388       | 2.92%   |
| Dell OptiPlex         | 346       | 2.6%    |
| Dell Inspiron         | 343       | 2.58%   |
| HP Pavilion           | 289       | 2.17%   |
| ASUS PRIME            | 287       | 2.16%   |
| HP Compaq             | 279       | 2.1%    |
| Toshiba Satellite     | 244       | 1.84%   |
| HP Laptop             | 166       | 1.25%   |
| Lenovo ThinkCentre    | 161       | 1.21%   |
| ASUS VivoBook         | 139       | 1.05%   |
| HP EliteBook          | 138       | 1.04%   |
| ASUS All              | 131       | 0.99%   |
| ASUS ROG              | 129       | 0.97%   |
| HP ProBook            | 128       | 0.96%   |
| ASUS UX31E            | 122       | 0.92%   |
| Unknown               | 120       | 0.9%    |
| ASUS TUF              | 115       | 0.87%   |
| Dell Precision        | 94        | 0.71%   |
| HP EliteDesk          | 87        | 0.65%   |
| Dell Vostro           | 85        | 0.64%   |
| Fujitsu ESPRIMO       | 73        | 0.55%   |
| HP ProDesk            | 67        | 0.5%    |
| Fujitsu LIFEBOOK      | 67        | 0.5%    |
| HP Notebook           | 66        | 0.5%    |
| Dell XPS              | 66        | 0.5%    |
| ASUS M5A78L-M         | 63        | 0.47%   |
| Lenovo IdeaCentre     | 60        | 0.45%   |
| Lenovo Yoga           | 48        | 0.36%   |
| Gigabyte B450M        | 47        | 0.35%   |
| ASUS P8H61-M          | 43        | 0.32%   |
| Toshiba dynabook      | 42        | 0.32%   |
| Packard Bell EasyNote | 42        | 0.32%   |
| Acer TravelMate       | 41        | 0.31%   |
| Acer Veriton          | 40        | 0.3%    |
| Gigabyte H410M        | 38        | 0.29%   |
| ASUS SABERTOOTH       | 38        | 0.29%   |
| Gigabyte B450         | 36        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 1317      | 9.91%   |
| 2011    | 1270      | 9.56%   |
| 2013    | 1096      | 8.25%   |
| 2018    | 970       | 7.3%    |
| 2019    | 949       | 7.14%   |
| 2020    | 905       | 6.81%   |
| 2014    | 890       | 6.7%    |
| 2010    | 851       | 6.4%    |
| 2021    | 758       | 5.7%    |
| 2017    | 747       | 5.62%   |
| 2015    | 703       | 5.29%   |
| 2008    | 672       | 5.06%   |
| 2009    | 662       | 4.98%   |
| 2016    | 647       | 4.87%   |
| 2007    | 423       | 3.18%   |
| 2022    | 214       | 1.61%   |
| 2006    | 161       | 1.21%   |
| 2005    | 25        | 0.19%   |
| 2023    | 13        | 0.1%    |
| 2004    | 8         | 0.06%   |
| Unknown | 8         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6353      | 47.81%  |
| Desktop        | 6206      | 46.7%   |
| Convertible    | 237       | 1.78%   |
| All in one     | 210       | 1.58%   |
| Mini pc        | 192       | 1.44%   |
| Tablet         | 54        | 0.41%   |
| Server         | 36        | 0.27%   |
| System on chip | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 13289     | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 13257     | 99.76%  |
| Yes  | 32        | 0.24%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 3604      | 26.92%  |
| 4.01-8.0        | 3547      | 26.49%  |
| 8.01-16.0       | 2428      | 18.14%  |
| 16.01-24.0      | 2019      | 15.08%  |
| 32.01-64.0      | 770       | 5.75%   |
| 1.01-2.0        | 480       | 3.59%   |
| 2.01-3.0        | 188       | 1.4%    |
| 24.01-32.0      | 164       | 1.22%   |
| 64.01-256.0     | 157       | 1.17%   |
| 0.51-1.0        | 23        | 0.17%   |
| More than 256.0 | 7         | 0.05%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 10004     | 73.15%  |
| 2.01-3.0   | 1581      | 11.56%  |
| 0.51-1.0   | 1576      | 11.52%  |
| 0.01-0.5   | 226       | 1.65%   |
| 3.01-4.0   | 201       | 1.47%   |
| 4.01-8.0   | 65        | 0.48%   |
| 8.01-16.0  | 19        | 0.14%   |
| 16.01-24.0 | 2         | 0.01%   |
| 32.01-64.0 | 1         | 0.01%   |
| Unknown    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 7907      | 58.71%  |
| 2      | 3280      | 24.36%  |
| 3      | 1111      | 8.25%   |
| 4      | 537       | 3.99%   |
| 0      | 223       | 1.66%   |
| 5      | 221       | 1.64%   |
| 6      | 90        | 0.67%   |
| 7      | 43        | 0.32%   |
| 8      | 31        | 0.23%   |
| 9      | 8         | 0.06%   |
| 12     | 4         | 0.03%   |
| 11     | 3         | 0.02%   |
| 15     | 2         | 0.01%   |
| 13     | 2         | 0.01%   |
| 10     | 2         | 0.01%   |
| 25     | 1         | 0.01%   |
| 18     | 1         | 0.01%   |
| 17     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6983      | 52.33%  |
| No        | 6361      | 47.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 12148     | 91.41%  |
| No        | 1142      | 8.59%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9149      | 68.63%  |
| No        | 4181      | 31.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 6750      | 50.58%  |
| Yes       | 6596      | 49.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 1601      | 12.03%  |
| Germany     | 1525      | 11.46%  |
| Russia      | 960       | 7.21%   |
| France      | 953       | 7.16%   |
| Brazil      | 866       | 6.51%   |
| Poland      | 714       | 5.36%   |
| Italy       | 611       | 4.59%   |
| UK          | 454       | 3.41%   |
| Spain       | 435       | 3.27%   |
| Canada      | 369       | 2.77%   |
| Netherlands | 319       | 2.4%    |
| Czechia     | 290       | 2.18%   |
| Mexico      | 219       | 1.65%   |
| Australia   | 206       | 1.55%   |
| Japan       | 197       | 1.48%   |
| India       | 189       | 1.42%   |
| Hungary     | 149       | 1.12%   |
| Finland     | 142       | 1.07%   |
| Ukraine     | 135       | 1.01%   |
| Argentina   | 134       | 1.01%   |
| Austria     | 133       | 1%      |
| Romania     | 127       | 0.95%   |
| Portugal    | 125       | 0.94%   |
| Belgium     | 118       | 0.89%   |
| Switzerland | 117       | 0.88%   |
| Indonesia   | 115       | 0.86%   |
| Sweden      | 105       | 0.79%   |
| Turkey      | 89        | 0.67%   |
| Slovakia    | 84        | 0.63%   |
| Greece      | 83        | 0.62%   |
| Serbia      | 74        | 0.56%   |
| Colombia    | 73        | 0.55%   |
| Bulgaria    | 69        | 0.52%   |
| Chile       | 67        | 0.5%    |
| China       | 63        | 0.47%   |
| Norway      | 55        | 0.41%   |
| Denmark     | 54        | 0.41%   |
| Peru        | 50        | 0.38%   |
| Venezuela   | 47        | 0.35%   |
| Belarus     | 47        | 0.35%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Moscow           | 184       | 1.34%   |
| Prague           | 145       | 1.06%   |
| Schagen          | 137       | 1%      |
| Warsaw           | 121       | 0.88%   |
| Berlin           | 108       | 0.79%   |
| Paris            | 104       | 0.76%   |
| Sao Paulo        | 89        | 0.65%   |
| Milan            | 85        | 0.62%   |
| St Petersburg    | 79        | 0.58%   |
| Vienna           | 67        | 0.49%   |
| Rio de Janeiro   | 67        | 0.49%   |
| Rome             | 63        | 0.46%   |
| Munich           | 63        | 0.46%   |
| Krakow           | 61        | 0.44%   |
| Mexico City      | 58        | 0.42%   |
| Helsinki         | 55        | 0.4%    |
| Hamburg          | 52        | 0.38%   |
| Madrid           | 51        | 0.37%   |
| Sydney           | 46        | 0.34%   |
| Budapest         | 42        | 0.31%   |
| Melbourne        | 40        | 0.29%   |
| Brisbane         | 37        | 0.27%   |
| Barcelona        | 34        | 0.25%   |
| Jakarta          | 33        | 0.24%   |
| Athens           | 33        | 0.24%   |
| Poznan           | 32        | 0.23%   |
| Montreal         | 32        | 0.23%   |
| Krasnodar        | 32        | 0.23%   |
| Cologne          | 32        | 0.23%   |
| Buenos Aires     | 32        | 0.23%   |
| Yekaterinburg    | 31        | 0.23%   |
| Bucharest        | 31        | 0.23%   |
| Belgrade         | 31        | 0.23%   |
| Stuttgart        | 30        | 0.22%   |
| Nizhniy Novgorod | 30        | 0.22%   |
| Lima             | 30        | 0.22%   |
| Wroclaw          | 29        | 0.21%   |
| Istanbul         | 29        | 0.21%   |
| Bengaluru        | 29        | 0.21%   |
| Porto Alegre     | 27        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3423      | 4363   | 17.67%  |
| Seagate             | 3102      | 3896   | 16.01%  |
| Samsung Electronics | 2315      | 2978   | 11.95%  |
| Toshiba             | 1361      | 1524   | 7.03%   |
| Kingston            | 1197      | 1360   | 6.18%   |
| SanDisk             | 859       | 967    | 4.43%   |
| Crucial             | 858       | 1018   | 4.43%   |
| Hitachi             | 766       | 838    | 3.95%   |
| Unknown             | 516       | 582    | 2.66%   |
| A-DATA Technology   | 397       | 444    | 2.05%   |
| HGST                | 324       | 369    | 1.67%   |
| SK hynix            | 300       | 318    | 1.55%   |
| Intel               | 267       | 309    | 1.38%   |
| China               | 243       | 266    | 1.25%   |
| Micron Technology   | 163       | 176    | 0.84%   |
| PNY                 | 161       | 183    | 0.83%   |
| SPCC                | 156       | 177    | 0.81%   |
| GOODRAM             | 139       | 157    | 0.72%   |
| Intenso             | 131       | 145    | 0.68%   |
| Patriot             | 127       | 137    | 0.66%   |
| Maxtor              | 108       | 123    | 0.56%   |
| JMicron Technology  | 103       | 108    | 0.53%   |
| Transcend           | 102       | 106    | 0.53%   |
| Phison              | 93        | 112    | 0.48%   |
| Apacer              | 90        | 99     | 0.46%   |
| Unknown             | 87        | 91     | 0.45%   |
| Apple               | 83        | 92     | 0.43%   |
| Fujitsu             | 82        | 85     | 0.42%   |
| OCZ                 | 76        | 80     | 0.39%   |
| KIOXIA              | 76        | 79     | 0.39%   |
| LITEON              | 72        | 73     | 0.37%   |
| Gigabyte Technology | 66        | 74     | 0.34%   |
| Corsair             | 64        | 70     | 0.33%   |
| Netac               | 60        | 67     | 0.31%   |
| Silicon Motion      | 57        | 62     | 0.29%   |
| Hewlett-Packard     | 55        | 66     | 0.28%   |
| ASMT                | 55        | 63     | 0.28%   |
| Team                | 54        | 56     | 0.28%   |
| KingSpec            | 50        | 50     | 0.26%   |
| Lexar               | 38        | 39     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 262       | 1.24%   |
| Seagate ST500DM002-1BD142 500GB     | 209       | 0.99%   |
| Seagate ST1000DM010-2EP102 1TB      | 161       | 0.76%   |
| Seagate ST500LT012-1DG142 500GB     | 148       | 0.7%    |
| Kingston SA400S37480G 480GB SSD     | 139       | 0.66%   |
| Kingston SA400S37120G 120GB SSD     | 132       | 0.62%   |
| Samsung SSD 860 EVO 500GB           | 130       | 0.61%   |
| Toshiba DT01ACA100 1TB              | 127       | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 124       | 0.58%   |
| Toshiba MQ01ABF050 500GB            | 123       | 0.58%   |
| SanDisk SSD U100 256GB              | 122       | 0.58%   |
| Toshiba MQ01ABD100 1TB              | 117       | 0.55%   |
| Crucial CT240BX500SSD1 240GB        | 117       | 0.55%   |
| Unknown SD/MMC/MS PRO 64GB          | 115       | 0.54%   |
| Kingston SV300S37A120G 120GB SSD    | 114       | 0.54%   |
| Crucial CT500MX500SSD1 500GB        | 114       | 0.54%   |
| Seagate ST1000LM035-1RK172 1TB      | 113       | 0.53%   |
| Seagate ST2000DM008-2FR102 2TB      | 110       | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB            | 99        | 0.47%   |
| Samsung SSD 850 EVO 250GB           | 98        | 0.46%   |
| Samsung SSD 860 EVO 250GB           | 94        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB         | 90        | 0.42%   |
| Toshiba DT01ACA050 500GB            | 89        | 0.42%   |
| Unknown                             | 87        | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 86        | 0.41%   |
| Seagate ST3500418AS 500GB           | 84        | 0.4%    |
| Samsung SSD 850 EVO 500GB           | 82        | 0.39%   |
| Toshiba MQ04ABF100 1TB              | 79        | 0.37%   |
| Crucial CT480BX500SSD1 480GB        | 78        | 0.37%   |
| Seagate ST9500325AS 500GB           | 76        | 0.36%   |
| Seagate ST1000DM003-1ER162 1TB      | 75        | 0.35%   |
| HGST HTS721010A9E630 1TB            | 70        | 0.33%   |
| Samsung SSD 970 EVO Plus 500GB      | 68        | 0.32%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 63        | 0.3%    |
| Toshiba HDWD110 1TB                 | 62        | 0.29%   |
| HGST HTS545050A7E680 500GB          | 62        | 0.29%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 61        | 0.29%   |
| Samsung SSD 970 EVO Plus 1TB        | 58        | 0.27%   |
| Samsung SSD 860 EVO 1TB             | 58        | 0.27%   |
| JMicron Generic 320GB               | 58        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3056      | 3821   | 33.62%  |
| WDC                 | 2763      | 3458   | 30.4%   |
| Toshiba             | 1194      | 1336   | 13.14%  |
| Hitachi             | 766       | 838    | 8.43%   |
| Samsung Electronics | 487       | 557    | 5.36%   |
| HGST                | 324       | 369    | 3.56%   |
| Unknown             | 119       | 123    | 1.31%   |
| Maxtor              | 104       | 119    | 1.14%   |
| Fujitsu             | 81        | 84     | 0.89%   |
| Apple               | 37        | 37     | 0.41%   |
| External            | 16        | 16     | 0.18%   |
| Hewlett-Packard     | 14        | 19     | 0.15%   |
| USB3.0              | 11        | 11     | 0.12%   |
| ASMedia             | 10        | 10     | 0.11%   |
| WD MediaMax         | 9         | 13     | 0.1%    |
| Intenso             | 9         | 9      | 0.1%    |
| ASMT                | 8         | 15     | 0.09%   |
| SAGE                | 6         | 6      | 0.07%   |
| IBM/Hitachi         | 6         | 7      | 0.07%   |
| ExcelStor           | 6         | 6      | 0.07%   |
| SSK                 | 5         | 6      | 0.06%   |
| Quantum             | 5         | 5      | 0.06%   |
| HPE                 | 5         | 5      | 0.06%   |
| HGST HTS            | 5         | 5      | 0.06%   |
| Inateck             | 4         | 4      | 0.04%   |
| SABRENT             | 3         | 5      | 0.03%   |
| Magnetic Data       | 3         | 3      | 0.03%   |
| JMicron Technology  | 3         | 3      | 0.03%   |
| China               | 3         | 4      | 0.03%   |
| Unknown             | 3         | 3      | 0.03%   |
| USB                 | 2         | 3      | 0.02%   |
| StoreJet            | 2         | 2      | 0.02%   |
| RSH-319             | 2         | 2      | 0.02%   |
| MDT                 | 2         | 2      | 0.02%   |
| LaCie               | 2         | 2      | 0.02%   |
| KESU                | 2         | 3      | 0.02%   |
| USB 3.0             | 1         | 2      | 0.01%   |
| TPH00800640GB       | 1         | 1      | 0.01%   |
| Super Talent        | 1         | 1      | 0.01%   |
| RSH-339             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1230      | 1510   | 16.86%  |
| Kingston            | 993       | 1121   | 13.61%  |
| SanDisk             | 745       | 829    | 10.21%  |
| Crucial             | 727       | 854    | 9.97%   |
| WDC                 | 441       | 491    | 6.05%   |
| A-DATA Technology   | 325       | 356    | 4.46%   |
| China               | 240       | 262    | 3.29%   |
| PNY                 | 140       | 159    | 1.92%   |
| GOODRAM             | 135       | 150    | 1.85%   |
| SPCC                | 127       | 142    | 1.74%   |
| Intel               | 121       | 132    | 1.66%   |
| Toshiba             | 119       | 125    | 1.63%   |
| Patriot             | 115       | 125    | 1.58%   |
| Intenso             | 115       | 127    | 1.58%   |
| Micron Technology   | 99        | 107    | 1.36%   |
| SK hynix            | 96        | 103    | 1.32%   |
| Transcend           | 90        | 93     | 1.23%   |
| Apacer              | 81        | 86     | 1.11%   |
| OCZ                 | 76        | 80     | 1.04%   |
| JMicron Technology  | 68        | 72     | 0.93%   |
| LITEON              | 65        | 66     | 0.89%   |
| Netac               | 51        | 58     | 0.7%    |
| Unknown             | 49        | 51     | 0.67%   |
| KingSpec            | 47        | 47     | 0.64%   |
| Team                | 45        | 46     | 0.62%   |
| ASMT                | 42        | 43     | 0.58%   |
| Gigabyte Technology | 39        | 41     | 0.53%   |
| Apple               | 36        | 36     | 0.49%   |
| Corsair             | 34        | 38     | 0.47%   |
| SABRENT             | 29        | 33     | 0.4%    |
| LITEONIT            | 29        | 31     | 0.4%    |
| Unknown             | 28        | 29     | 0.38%   |
| Lexar               | 28        | 29     | 0.38%   |
| Hewlett-Packard     | 28        | 30     | 0.38%   |
| Plextor             | 24        | 26     | 0.33%   |
| Seagate             | 23        | 27     | 0.32%   |
| KIOXIA-EXCERIA      | 23        | 23     | 0.32%   |
| KingFast            | 21        | 23     | 0.29%   |
| XrayDisk            | 20        | 20     | 0.27%   |
| Verbatim            | 20        | 20     | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 7665      | 10925  | 45.22%  |
| SSD     | 6161      | 8197   | 36.34%  |
| NVMe    | 2522      | 3160   | 14.88%  |
| MMC     | 418       | 466    | 2.47%   |
| Unknown | 186       | 225    | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 11462     | 18261  | 74.96%  |
| NVMe | 2518      | 3136   | 16.47%  |
| SAS  | 893       | 1110   | 5.84%   |
| MMC  | 418       | 466    | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 9065      | 12344  | 63.24%  |
| 0.51-1.0   | 3779      | 4838   | 26.36%  |
| 1.01-2.0   | 907       | 1165   | 6.33%   |
| 3.01-4.0   | 195       | 266    | 1.36%   |
| 2.01-3.0   | 190       | 244    | 1.33%   |
| 4.01-10.0  | 135       | 192    | 0.94%   |
| 10.01-20.0 | 64        | 73     | 0.45%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 6735      | 48.7%   |
| 101-250        | 2126      | 15.37%  |
| 251-500        | 1394      | 10.08%  |
| Unknown        | 1247      | 9.02%   |
| 501-1000       | 749       | 5.42%   |
| 51-100         | 645       | 4.66%   |
| 21-50          | 541       | 3.91%   |
| 1001-2000      | 246       | 1.78%   |
| 2001-3000      | 76        | 0.55%   |
| More than 3000 | 70        | 0.51%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 10939     | 80.16%  |
| Unknown        | 1247      | 9.14%   |
| 21-50          | 415       | 3.04%   |
| 101-250        | 325       | 2.38%   |
| 51-100         | 286       | 2.1%    |
| 251-500        | 204       | 1.49%   |
| 501-1000       | 139       | 1.02%   |
| 1001-2000      | 57        | 0.42%   |
| More than 3000 | 17        | 0.12%   |
| 2001-3000      | 17        | 0.12%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 122       | 122    | 3.02%   |
| Seagate ST500DM002-1BD142 500GB     | 90        | 97     | 2.23%   |
| Seagate ST9500325AS 500GB           | 59        | 63     | 1.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 48        | 52     | 1.19%   |
| Seagate ST500LT012-1DG142 500GB     | 46        | 48     | 1.14%   |
| HGST HTS545050A7E680 500GB          | 41        | 42     | 1.01%   |
| Seagate ST3500418AS 500GB           | 40        | 44     | 0.99%   |
| Seagate ST500LT012-9WS142 500GB     | 37        | 39     | 0.92%   |
| Toshiba MQ01ABD075 752GB            | 33        | 34     | 0.82%   |
| Toshiba MQ01ABF050 500GB            | 31        | 31     | 0.77%   |
| Seagate ST9320325AS 320GB           | 31        | 31     | 0.77%   |
| Kingston SV300S37A120G 120GB SSD    | 30        | 31     | 0.74%   |
| HGST HTS541010A9E680 1TB            | 28        | 30     | 0.69%   |
| Toshiba MQ01ABD100 1TB              | 24        | 24     | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB      | 24        | 25     | 0.59%   |
| HGST HTS721010A9E630 1TB            | 22        | 26     | 0.54%   |
| Seagate ST31000524AS 1TB            | 21        | 21     | 0.52%   |
| WDC WD5000AAKX-001CA0 500GB         | 20        | 23     | 0.49%   |
| Toshiba DT01ACA100 1TB              | 20        | 22     | 0.49%   |
| Seagate ST31000528AS 1TB            | 20        | 21     | 0.49%   |
| WDC WD5000AAKX-75U6AA0 500GB        | 19        | 20     | 0.47%   |
| Seagate ST500LM021-1KJ152 500GB     | 19        | 19     | 0.47%   |
| Hitachi HTS543232A7A384 320GB       | 19        | 20     | 0.47%   |
| HGST HTS545050A7E380 500GB          | 19        | 21     | 0.47%   |
| Crucial CT240M500SSD1 240GB         | 19        | 20     | 0.47%   |
| Toshiba MQ01ABD050 500GB            | 18        | 18     | 0.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 18        | 18     | 0.45%   |
| Seagate ST1000DM010-2EP102 1TB      | 18        | 19     | 0.45%   |
| Hitachi HTS545050A7E380 500GB       | 18        | 19     | 0.45%   |
| Toshiba DT01ACA050 500GB            | 17        | 19     | 0.42%   |
| Seagate ST3500413AS 500GB           | 17        | 18     | 0.42%   |
| HGST HTS725050A7E630 500GB          | 17        | 17     | 0.42%   |
| WDC WD10JPVX-22JC3T0 1TB            | 16        | 16     | 0.4%    |
| Seagate ST3320418AS 320GB           | 16        | 17     | 0.4%    |
| Seagate ST2000DM001-1CH164 2TB      | 16        | 16     | 0.4%    |
| Seagate ST1000DM003-9YN162 1TB      | 16        | 17     | 0.4%    |
| Samsung Electronics HD322HJ 320GB   | 16        | 18     | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 15        | 17     | 0.37%   |
| Hitachi HTS547575A9E384 752GB       | 15        | 15     | 0.37%   |
| Samsung Electronics HD502HJ 500GB   | 14        | 14     | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1076      | 1194   | 27.44%  |
| WDC                 | 881       | 1002   | 22.47%  |
| Hitachi             | 381       | 412    | 9.72%   |
| Toshiba             | 344       | 356    | 8.77%   |
| Samsung Electronics | 289       | 320    | 7.37%   |
| SanDisk             | 185       | 189    | 4.72%   |
| HGST                | 154       | 166    | 3.93%   |
| Kingston            | 102       | 106    | 2.6%    |
| Maxtor              | 68        | 72     | 1.73%   |
| Crucial             | 55        | 58     | 1.4%    |
| Intel               | 43        | 47     | 1.1%    |
| A-DATA Technology   | 37        | 41     | 0.94%   |
| Fujitsu             | 31        | 33     | 0.79%   |
| China               | 31        | 31     | 0.79%   |
| SK hynix            | 25        | 26     | 0.64%   |
| Micron Technology   | 15        | 17     | 0.38%   |
| OCZ                 | 13        | 13     | 0.33%   |
| SPCC                | 10        | 10     | 0.26%   |
| ASMT                | 10        | 11     | 0.26%   |
| Hewlett-Packard     | 9         | 9      | 0.23%   |
| Apple               | 9         | 9      | 0.23%   |
| Netac               | 8         | 8      | 0.2%    |
| LITEON              | 8         | 8      | 0.2%    |
| KingSpec            | 8         | 8      | 0.2%    |
| GOODRAM             | 8         | 8      | 0.2%    |
| Unknown             | 8         | 8      | 0.2%    |
| Corsair             | 7         | 8      | 0.18%   |
| Intenso             | 6         | 6      | 0.15%   |
| Plextor             | 4         | 4      | 0.1%    |
| Patriot             | 4         | 4      | 0.1%    |
| IBM/Hitachi         | 4         | 5      | 0.1%    |
| WD MediaMax         | 3         | 3      | 0.08%   |
| Transcend           | 3         | 3      | 0.08%   |
| Initio              | 3         | 3      | 0.08%   |
| ASMedia             | 3         | 3      | 0.08%   |
| Apacer              | 3         | 4      | 0.08%   |
| XrayDisk            | 2         | 2      | 0.05%   |
| XPG                 | 2         | 2      | 0.05%   |
| USB3.0              | 2         | 2      | 0.05%   |
| Teclast             | 2         | 2      | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1075      | 1193   | 34.02%  |
| WDC                 | 840       | 954    | 26.58%  |
| Hitachi             | 381       | 412    | 12.06%  |
| Toshiba             | 338       | 350    | 10.7%   |
| Samsung Electronics | 234       | 260    | 7.41%   |
| HGST                | 154       | 166    | 4.87%   |
| Maxtor              | 68        | 72     | 2.15%   |
| Fujitsu             | 31        | 33     | 0.98%   |
| Hewlett-Packard     | 6         | 6      | 0.19%   |
| Apple               | 5         | 5      | 0.16%   |
| IBM/Hitachi         | 4         | 5      | 0.13%   |
| WD MediaMax         | 3         | 3      | 0.09%   |
| ASMT                | 3         | 4      | 0.09%   |
| ASMedia             | 3         | 3      | 0.09%   |
| USB3.0              | 2         | 2      | 0.06%   |
| Quantum             | 2         | 2      | 0.06%   |
| HPE                 | 2         | 2      | 0.06%   |
| ExcelStor           | 2         | 2      | 0.06%   |
| SAGE                | 1         | 1      | 0.03%   |
| RSH-339             | 1         | 1      | 0.03%   |
| RSH-319             | 1         | 1      | 0.03%   |
| Magnetic Data       | 1         | 1      | 0.03%   |
| IB                  | 1         | 1      | 0.03%   |
| China               | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2928      | 3481   | 79.44%  |
| SSD     | 708       | 746    | 19.21%  |
| NVMe    | 48        | 50     | 1.3%    |
| Unknown | 2         | 2      | 0.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB     | 4         | 4      | 3.92%   |
| Seagate ST3500418AS 500GB         | 3         | 4      | 2.94%   |
| Seagate ST3250318AS 250GB         | 3         | 3      | 2.94%   |
| Samsung Electronics HD103SJ 1TB   | 3         | 3      | 2.94%   |
| WDC WD800JD-00LSA0 80GB           | 2         | 3      | 1.96%   |
| WDC WD3200BEVT-11ZCT0 320GB       | 2         | 2      | 1.96%   |
| WDC WD2500BEVS-22UST0 250GB       | 2         | 2      | 1.96%   |
| WDC WD20EZRX-00D8PB0 2TB          | 2         | 2      | 1.96%   |
| Toshiba MQ01ABD100 1TB            | 2         | 2      | 1.96%   |
| Seagate ST500DM002-1BD142 500GB   | 2         | 2      | 1.96%   |
| Samsung Electronics HD502HJ 500GB | 2         | 2      | 1.96%   |
| Samsung Electronics HD103UJ 1TB   | 2         | 3      | 1.96%   |
| Hitachi HTS545050A7E380 500GB     | 2         | 2      | 1.96%   |
| Crucial CT500P2SSD8 500GB         | 2         | 2      | 1.96%   |
| WDC WD800JD-75MSA3 80GB           | 1         | 1      | 0.98%   |
| WDC WD7501AALS-00J7B0 752GB       | 1         | 1      | 0.98%   |
| WDC WD7500BPVT-22HXZT3 752GB      | 1         | 1      | 0.98%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB  | 1         | 1      | 0.98%   |
| WDC WD5000LPLX-75ZNTT0 500GB      | 1         | 1      | 0.98%   |
| WDC WD5000BPVT-60HXZT1 500GB      | 1         | 1      | 0.98%   |
| WDC WD5000BEVT-22ZAT0 500GB       | 1         | 1      | 0.98%   |
| WDC WD5000BEVT-22A0RT0 500GB      | 1         | 1      | 0.98%   |
| WDC WD5000AAKS-00C8A0 500GB       | 1         | 1      | 0.98%   |
| WDC WD3200BUCT-63TWBY0 320GB      | 1         | 1      | 0.98%   |
| WDC WD3200BEKT-60KA9T0 320GB      | 1         | 1      | 0.98%   |
| WDC WD3200AAJS-60Z0A0 320GB       | 1         | 1      | 0.98%   |
| WDC WD2500BEVT-60ZCT1 250GB       | 1         | 1      | 0.98%   |
| WDC WD2500BEVT-35A23T0 250GB      | 1         | 1      | 0.98%   |
| WDC WD20EARS-00MVWB0 2TB          | 1         | 1      | 0.98%   |
| WDC WD1600YS-23SHB0 160GB         | 1         | 1      | 0.98%   |
| WDC WD1600BEVT-75A23T0 160GB      | 1         | 1      | 0.98%   |
| WDC WD1600AAJS-00YZCA0 160GB      | 1         | 1      | 0.98%   |
| WDC WD10JPVX-60JC3T0 1TB          | 1         | 1      | 0.98%   |
| WDC WD10JPVT-75A1YT0 1TB          | 1         | 1      | 0.98%   |
| WDC WD10EARX-22N0YB0 1TB          | 1         | 1      | 0.98%   |
| WDC WD10EALX-759BA1 1TB           | 1         | 1      | 0.98%   |
| TPH00800640GB 640GB               | 1         | 1      | 0.98%   |
| Toshiba MQ01ABF050 500GB          | 1         | 1      | 0.98%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 0.98%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 0.98%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 31     | 29.41%  |
| Samsung Electronics | 20        | 21     | 19.61%  |
| Seagate             | 19        | 20     | 18.63%  |
| Toshiba             | 9         | 10     | 8.82%   |
| Hitachi             | 8         | 8      | 7.84%   |
| Apple               | 5         | 5      | 4.9%    |
| HGST                | 2         | 2      | 1.96%   |
| Crucial             | 2         | 2      | 1.96%   |
| TPH00800640GB       | 1         | 1      | 0.98%   |
| SK hynix            | 1         | 1      | 0.98%   |
| Maxtor              | 1         | 1      | 0.98%   |
| Kingston            | 1         | 1      | 0.98%   |
| Intel               | 1         | 1      | 0.98%   |
| GOODRAM             | 1         | 1      | 0.98%   |
| External            | 1         | 1      | 0.98%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 10315     | 16784  | 66.84%  |
| Malfunc  | 3601      | 4279   | 23.33%  |
| Detected | 1416      | 1804   | 9.18%   |
| Failed   | 100       | 106    | 0.65%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 9325      | 58.07%  |
| AMD                              | 3001      | 18.69%  |
| Samsung Electronics              | 789       | 4.91%   |
| SanDisk                          | 437       | 2.72%   |
| Nvidia                           | 286       | 1.78%   |
| ASMedia Technology               | 247       | 1.54%   |
| Phison Electronics               | 230       | 1.43%   |
| Kingston Technology Company      | 230       | 1.43%   |
| JMicron Technology               | 230       | 1.43%   |
| SK hynix                         | 189       | 1.18%   |
| Marvell Technology Group         | 188       | 1.17%   |
| Micron/Crucial Technology        | 139       | 0.87%   |
| Silicon Motion                   | 135       | 0.84%   |
| KIOXIA                           | 81        | 0.5%    |
| Micron Technology                | 73        | 0.45%   |
| ADATA Technology                 | 68        | 0.42%   |
| Toshiba America Info Systems     | 63        | 0.39%   |
| VIA Technologies                 | 61        | 0.38%   |
| Realtek Semiconductor            | 42        | 0.26%   |
| Solid State Storage Technology   | 33        | 0.21%   |
| Union Memory (Shenzhen)          | 26        | 0.16%   |
| MAXIO Technology (Hangzhou)      | 22        | 0.14%   |
| Seagate Technology               | 20        | 0.12%   |
| Silicon Image                    | 18        | 0.11%   |
| Broadcom / LSI                   | 16        | 0.1%    |
| LSI Logic / Symbios Logic        | 14        | 0.09%   |
| Lite-On Technology               | 12        | 0.07%   |
| Silicon Integrated Systems [SiS] | 11        | 0.07%   |
| Shenzhen Longsys Electronics     | 11        | 0.07%   |
| Integrated Technology Express    | 10        | 0.06%   |
| Apple                            | 8         | 0.05%   |
| Adaptec                          | 8         | 0.05%   |
| Biwin Storage Technology         | 6         | 0.04%   |
| Promise Technology               | 5         | 0.03%   |
| Lite-On IT Corp. / Plextor       | 4         | 0.02%   |
| Hewlett-Packard                  | 4         | 0.02%   |
| Lenovo                           | 3         | 0.02%   |
| Yangtze Memory Technologies      | 2         | 0.01%   |
| OCZ Technology Group             | 2         | 0.01%   |
| Netac Technology                 | 2         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1834      | 9.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 684       | 3.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 671       | 3.5%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 586       | 3.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 566       | 2.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 454       | 2.37%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 422       | 2.2%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 387       | 2.02%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 384       | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 379       | 1.98%   |
| AMD 400 Series Chipset SATA Controller                                                  | 377       | 1.97%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 364       | 1.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 358       | 1.87%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 316       | 1.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 311       | 1.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 298       | 1.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 276       | 1.44%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 271       | 1.42%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 265       | 1.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 258       | 1.35%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 257       | 1.34%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 241       | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 226       | 1.18%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 224       | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 223       | 1.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 219       | 1.14%   |
| Samsung NVMe SSD Controller 980                                                         | 213       | 1.11%   |
| AMD 500 Series Chipset SATA Controller                                                  | 207       | 1.08%   |
| Intel SATA Controller [RAID mode]                                                       | 205       | 1.07%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 192       | 1%      |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 191       | 1%      |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 186       | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 184       | 0.96%   |
| AMD FCH SATA Controller D                                                               | 142       | 0.74%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 134       | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 133       | 0.69%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 132       | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 123       | 0.64%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 121       | 0.63%   |
| Nvidia MCP61 SATA Controller                                                            | 120       | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 10487     | 64%     |
| IDE  | 2547      | 15.54%  |
| NVMe | 2510      | 15.32%  |
| RAID | 799       | 4.88%   |
| SAS  | 23        | 0.14%   |
| SCSI | 19        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 9840      | 74.05%  |
| AMD    | 3448      | 25.95%  |
| ARM    | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 122       | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 107       | 0.8%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 103       | 0.77%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 90        | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 89        | 0.67%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 87        | 0.65%   |
| AMD Ryzen 5 3600 6-Core Processor             | 83        | 0.62%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 82        | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 79        | 0.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 76        | 0.57%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 74        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 70        | 0.53%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 70        | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 69        | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 69        | 0.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 68        | 0.51%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 67        | 0.5%    |
| AMD FX-8350 Eight-Core Processor              | 64        | 0.48%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 61        | 0.46%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 60        | 0.45%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 59        | 0.44%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 59        | 0.44%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 59        | 0.44%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 58        | 0.44%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 57        | 0.43%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 56        | 0.42%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 56        | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 56        | 0.42%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 56        | 0.42%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 55        | 0.41%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 54        | 0.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 54        | 0.41%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 53        | 0.4%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 53        | 0.4%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 52        | 0.39%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 52        | 0.39%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 51        | 0.38%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 51        | 0.38%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 51        | 0.38%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 49        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2861      | 21.5%   |
| Intel Core i7           | 1602      | 12.04%  |
| Intel Core i3           | 1452      | 10.91%  |
| Intel Celeron           | 925       | 6.95%   |
| Intel Core 2 Duo        | 845       | 6.35%   |
| AMD Ryzen 5             | 694       | 5.22%   |
| Intel Pentium           | 540       | 4.06%   |
| Other                   | 415       | 3.12%   |
| AMD Ryzen 7             | 415       | 3.12%   |
| AMD FX                  | 265       | 1.99%   |
| Intel Pentium Dual-Core | 254       | 1.91%   |
| AMD Ryzen 3             | 209       | 1.57%   |
| Intel Xeon              | 200       | 1.5%    |
| Intel Core 2 Quad       | 187       | 1.41%   |
| AMD A8                  | 172       | 1.29%   |
| AMD A6                  | 147       | 1.1%    |
| Intel Pentium Silver    | 133       | 1%      |
| AMD A4                  | 128       | 0.96%   |
| AMD A10                 | 122       | 0.92%   |
| AMD Ryzen 9             | 120       | 0.9%    |
| Intel Pentium Dual      | 110       | 0.83%   |
| Intel Core 2            | 101       | 0.76%   |
| AMD Athlon II X2        | 99        | 0.74%   |
| Intel Atom              | 94        | 0.71%   |
| AMD Athlon              | 92        | 0.69%   |
| AMD Phenom II X4        | 90        | 0.68%   |
| AMD E                   | 89        | 0.67%   |
| AMD E1                  | 84        | 0.63%   |
| AMD Athlon 64 X2        | 84        | 0.63%   |
| AMD E2                  | 46        | 0.35%   |
| AMD Athlon II X4        | 41        | 0.31%   |
| Intel Core i9           | 40        | 0.3%    |
| AMD Phenom II X6        | 37        | 0.28%   |
| Intel Pentium Gold      | 36        | 0.27%   |
| AMD Phenom              | 33        | 0.25%   |
| Intel Pentium 4         | 30        | 0.23%   |
| AMD C-60                | 30        | 0.23%   |
| Intel Genuine           | 29        | 0.22%   |
| Intel Pentium D         | 28        | 0.21%   |
| AMD Sempron             | 28        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6933      | 52.08%  |
| 4       | 4116      | 30.92%  |
| 6       | 1001      | 7.52%   |
| 8       | 583       | 4.38%   |
| 1       | 343       | 2.58%   |
| 3       | 109       | 0.82%   |
| 12      | 99        | 0.74%   |
| 16      | 51        | 0.38%   |
| 10      | 30        | 0.23%   |
| 14      | 28        | 0.21%   |
| 24      | 7         | 0.05%   |
| 28      | 3         | 0.02%   |
| 32      | 2         | 0.02%   |
| 20      | 2         | 0.02%   |
| 128     | 1         | 0.01%   |
| 44      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 13244     | 99.65%  |
| 2      | 46        | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7400      | 55.62%  |
| 1       | 5848      | 43.95%  |
| 4       | 32        | 0.24%   |
| 8       | 18        | 0.14%   |
| 12      | 4         | 0.03%   |
| 16      | 1         | 0.01%   |
| 6       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 13284     | 99.95%  |
| Unknown        | 6         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1543      | 11.39%  |
| 0x206a7    | 1126      | 8.31%   |
| 0x306a9    | 1013      | 7.48%   |
| 0x1067a    | 790       | 5.83%   |
| 0x306c3    | 767       | 5.66%   |
| 0x20655    | 325       | 2.4%    |
| 0x506e3    | 283       | 2.09%   |
| 0x40651    | 272       | 2.01%   |
| 0x906ea    | 246       | 1.82%   |
| 0x6fd      | 244       | 1.8%    |
| 0x406e3    | 237       | 1.75%   |
| 0x306d4    | 231       | 1.7%    |
| 0x806e9    | 226       | 1.67%   |
| 0x08108109 | 225       | 1.66%   |
| 0x08701021 | 223       | 1.65%   |
| 0x906e9    | 202       | 1.49%   |
| 0x10676    | 193       | 1.42%   |
| 0x806ea    | 189       | 1.39%   |
| 0x30678    | 181       | 1.34%   |
| 0x06001119 | 161       | 1.19%   |
| 0x806ec    | 144       | 1.06%   |
| 0x010000c8 | 141       | 1.04%   |
| 0x706a1    | 130       | 0.96%   |
| 0x0800820d | 123       | 0.91%   |
| 0x6fb      | 122       | 0.9%    |
| 0x706a8    | 115       | 0.85%   |
| 0x406c4    | 111       | 0.82%   |
| 0x20652    | 111       | 0.82%   |
| 0x0a50000c | 106       | 0.78%   |
| 0x506c9    | 105       | 0.77%   |
| 0x806c1    | 102       | 0.75%   |
| 0x06006705 | 95        | 0.7%    |
| 0x08101016 | 94        | 0.69%   |
| 0x08600106 | 91        | 0.67%   |
| 0xa0653    | 90        | 0.66%   |
| 0x06000822 | 89        | 0.66%   |
| 0x106e5    | 88        | 0.65%   |
| 0x07030105 | 88        | 0.65%   |
| 0x706e5    | 84        | 0.62%   |
| 0x906c0    | 82        | 0.61%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1349      | 10.15%  |
| SandyBridge      | 1249      | 9.39%   |
| Haswell          | 1186      | 8.92%   |
| IvyBridge        | 1140      | 8.57%   |
| Penryn           | 1099      | 8.27%   |
| Skylake          | 628       | 4.72%   |
| Core             | 561       | 4.22%   |
| Westmere         | 499       | 3.75%   |
| Zen+             | 464       | 3.49%   |
| Zen 2            | 425       | 3.2%    |
| K10              | 415       | 3.12%   |
| Silvermont       | 413       | 3.11%   |
| Piledriver       | 409       | 3.08%   |
| Zen 3            | 311       | 2.34%   |
| Zen              | 304       | 2.29%   |
| Broadwell        | 283       | 2.13%   |
| Goldmont plus    | 272       | 2.05%   |
| CometLake        | 249       | 1.87%   |
| Excavator        | 206       | 1.55%   |
| Bobcat           | 185       | 1.39%   |
| IceLake          | 160       | 1.2%    |
| K8 Hammer        | 156       | 1.17%   |
| TigerLake        | 150       | 1.13%   |
| Nehalem          | 139       | 1.05%   |
| Unknown          | 138       | 1.04%   |
| Puma             | 135       | 1.02%   |
| Goldmont         | 121       | 0.91%   |
| Steamroller      | 100       | 0.75%   |
| Alderlake Hybrid | 90        | 0.68%   |
| Tremont          | 88        | 0.66%   |
| Jaguar           | 86        | 0.65%   |
| K10 Llano        | 69        | 0.52%   |
| Bonnell          | 68        | 0.51%   |
| NetBurst         | 65        | 0.49%   |
| Bulldozer        | 56        | 0.42%   |
| K8 & K10 hybrid  | 27        | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 7334      | 49.76%  |
| Nvidia                                       | 3693      | 25.06%  |
| AMD                                          | 3667      | 24.88%  |
| Matrox Electronics Systems                   | 19        | 0.13%   |
| Silicon Integrated Systems [SiS]             | 7         | 0.05%   |
| ASPEED Technology                            | 7         | 0.05%   |
| VIA Technologies                             | 6         | 0.04%   |
| ATI Technologies                             | 3         | 0.02%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.01%   |
| S3 Graphics                                  | 1         | 0.01%   |
| Conexant Systems                             | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 984       | 6.49%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 559       | 3.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 362       | 2.39%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 343       | 2.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 326       | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 324       | 2.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 294       | 1.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 246       | 1.62%   |
| Intel HD Graphics 620                                                                    | 246       | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 243       | 1.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 231       | 1.52%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 224       | 1.48%   |
| Intel HD Graphics 5500                                                                   | 222       | 1.46%   |
| Intel HD Graphics 530                                                                    | 209       | 1.38%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 199       | 1.31%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 192       | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 180       | 1.19%   |
| Intel UHD Graphics 620                                                                   | 177       | 1.17%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 173       | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 165       | 1.09%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 165       | 1.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 152       | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 150       | 0.99%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 145       | 0.96%   |
| AMD Renoir                                                                               | 142       | 0.94%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 136       | 0.9%    |
| Intel HD Graphics 630                                                                    | 134       | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 131       | 0.86%   |
| Nvidia GT218 [GeForce 210]                                                               | 130       | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 117       | 0.77%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 108       | 0.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 107       | 0.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 104       | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 101       | 0.67%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 101       | 0.67%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 98        | 0.65%   |
| Intel HD Graphics 500                                                                    | 93        | 0.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 93        | 0.61%   |
| Intel JasperLake [UHD Graphics]                                                          | 88        | 0.58%   |
| AMD Lucienne                                                                             | 85        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 5847      | 43.78%  |
| 1 x AMD                  | 3108      | 23.27%  |
| 1 x Nvidia               | 2590      | 19.39%  |
| Intel + Nvidia           | 981       | 7.35%   |
| Intel + AMD              | 256       | 1.92%   |
| 2 x AMD                  | 204       | 1.53%   |
| 2 x Intel                | 199       | 1.49%   |
| AMD + Nvidia             | 102       | 0.76%   |
| 2 x Nvidia               | 21        | 0.16%   |
| 1 x Matrox               | 15        | 0.11%   |
| 1 x SiS                  | 7         | 0.05%   |
| 1 x VIA                  | 6         | 0.04%   |
| 1 x ASPEED               | 6         | 0.04%   |
| Nvidia + Matrox          | 2         | 0.01%   |
| Intel + 2 x Nvidia       | 2         | 0.01%   |
| Other                    | 1         | 0.01%   |
| 3 x AMD                  | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.01%   |
| 1 x S3 Graphics          | 1         | 0.01%   |
| Nvidia + XGI             | 1         | 0.01%   |
| Nvidia + ASPEED          | 1         | 0.01%   |
| Intel + Conexant Systems | 1         | 0.01%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.01%   |
| AMD + Matrox             | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 12979     | 97.4%   |
| Unknown     | 271       | 2.03%   |
| Proprietary | 75        | 0.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6372      | 47.69%  |
| 0.01-0.5   | 1994      | 14.93%  |
| 1.01-2.0   | 1877      | 14.05%  |
| 0.51-1.0   | 1520      | 11.38%  |
| 3.01-4.0   | 727       | 5.44%   |
| 7.01-8.0   | 436       | 3.26%   |
| 5.01-6.0   | 253       | 1.89%   |
| 2.01-3.0   | 84        | 0.63%   |
| 8.01-16.0  | 83        | 0.62%   |
| 16.01-24.0 | 10        | 0.07%   |
| 4.01-5.0   | 4         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1927      | 14.4%   |
| AU Optronics            | 1425      | 10.65%  |
| LG Display              | 1147      | 8.57%   |
| BOE                     | 934       | 6.98%   |
| Chimei Innolux          | 933       | 6.97%   |
| Goldstar                | 819       | 6.12%   |
| Dell                    | 637       | 4.76%   |
| Hewlett-Packard         | 629       | 4.7%    |
| Acer                    | 540       | 4.04%   |
| Philips                 | 411       | 3.07%   |
| AOC                     | 388       | 2.9%    |
| BenQ                    | 319       | 2.38%   |
| Lenovo                  | 279       | 2.09%   |
| Ancor Communications    | 266       | 1.99%   |
| Chi Mei Optoelectronics | 239       | 1.79%   |
| ViewSonic               | 169       | 1.26%   |
| Apple                   | 160       | 1.2%    |
| Iiyama                  | 152       | 1.14%   |
| CPT                     | 143       | 1.07%   |
| ASUSTek Computer        | 113       | 0.84%   |
| Sharp                   | 112       | 0.84%   |
| Eizo                    | 112       | 0.84%   |
| LG Philips              | 98        | 0.73%   |
| Sony                    | 97        | 0.72%   |
| PANDA                   | 78        | 0.58%   |
| InfoVision              | 70        | 0.52%   |
| Fujitsu Siemens         | 68        | 0.51%   |
| NEC Computers           | 59        | 0.44%   |
| HannStar                | 56        | 0.42%   |
| Panasonic               | 44        | 0.33%   |
| Toshiba                 | 43        | 0.32%   |
| Unknown                 | 35        | 0.26%   |
| Medion                  | 32        | 0.24%   |
| Vizio                   | 31        | 0.23%   |
| Sceptre Tech            | 30        | 0.22%   |
| Vestel Elektronik       | 29        | 0.22%   |
| MSI                     | 26        | 0.19%   |
| Hitachi                 | 24        | 0.18%   |
| RTK                     | 18        | 0.13%   |
| InnoLux Display         | 18        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 122       | 0.9%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 68        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 65        | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 61        | 0.45%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 56        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 54        | 0.4%    |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 53        | 0.39%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 51        | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 49        | 0.36%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 48        | 0.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 47        | 0.35%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 37        | 0.27%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 35        | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 35        | 0.26%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 35        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 34        | 0.25%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 34        | 0.25%   |
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 33        | 0.24%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 32        | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 31        | 0.23%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch     | 29        | 0.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 28        | 0.21%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 28        | 0.21%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 28        | 0.21%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 28        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 27        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 27        | 0.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 27        | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 26        | 0.19%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 25        | 0.18%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 25        | 0.18%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 24        | 0.18%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 24        | 0.18%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 24        | 0.18%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 23        | 0.17%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 23        | 0.17%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 23        | 0.17%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 23        | 0.17%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 23        | 0.17%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 23        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 5237      | 39.83%  |
| 1366x768 (WXGA)    | 3287      | 25%     |
| 1600x900 (HD+)     | 788       | 5.99%   |
| 3840x2160 (4K)     | 668       | 5.08%   |
| 1280x1024 (SXGA)   | 569       | 4.33%   |
| 1680x1050 (WSXGA+) | 476       | 3.62%   |
| 1440x900 (WXGA+)   | 438       | 3.33%   |
| 2560x1440 (QHD)    | 389       | 2.96%   |
| 1280x800 (WXGA)    | 387       | 2.94%   |
| 1920x1200 (WUXGA)  | 236       | 1.79%   |
| 1360x768           | 135       | 1.03%   |
| 2560x1080          | 69        | 0.52%   |
| 3440x1440          | 68        | 0.52%   |
| 2560x1600          | 56        | 0.43%   |
| 1024x768 (XGA)     | 44        | 0.33%   |
| 1920x540           | 43        | 0.33%   |
| 1600x1200          | 23        | 0.17%   |
| 1024x600           | 21        | 0.16%   |
| 3200x1800 (QHD+)   | 19        | 0.14%   |
| 2880x1800          | 17        | 0.13%   |
| 1280x720 (HD)      | 16        | 0.12%   |
| 2288x1287          | 15        | 0.11%   |
| 2160x1440          | 15        | 0.11%   |
| 2736x1824          | 14        | 0.11%   |
| 1280x960           | 12        | 0.09%   |
| 1680x945           | 11        | 0.08%   |
| 3840x2400          | 9         | 0.07%   |
| 1920x1280          | 9         | 0.07%   |
| 3840x1080          | 8         | 0.06%   |
| 2048x1152          | 7         | 0.05%   |
| Unknown            | 7         | 0.05%   |
| 2256x1504          | 6         | 0.05%   |
| 1400x1050          | 5         | 0.04%   |
| 1280x768           | 5         | 0.04%   |
| 800x1280           | 3         | 0.02%   |
| 3840x1600          | 3         | 0.02%   |
| 3456x2160          | 3         | 0.02%   |
| 2880x1920          | 3         | 0.02%   |
| 2240x1400          | 3         | 0.02%   |
| 1800x1200          | 3         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3220      | 24.03%  |
| 23      | 1083      | 8.08%   |
| 13      | 1080      | 8.06%   |
| 21      | 984       | 7.34%   |
| 17      | 929       | 6.93%   |
| 27      | 883       | 6.59%   |
| 24      | 852       | 6.36%   |
| 14      | 779       | 5.81%   |
| 19      | 568       | 4.24%   |
| 18      | 424       | 3.16%   |
| 31      | 348       | 2.6%    |
| 22      | 326       | 2.43%   |
| 20      | 272       | 2.03%   |
| 11      | 255       | 1.9%    |
| 12      | 252       | 1.88%   |
| Unknown | 127       | 0.95%   |
| 34      | 117       | 0.87%   |
| 84      | 116       | 0.87%   |
| 32      | 76        | 0.57%   |
| 54      | 67        | 0.5%    |
| 40      | 66        | 0.49%   |
| 72      | 63        | 0.47%   |
| 16      | 56        | 0.42%   |
| 26      | 55        | 0.41%   |
| 25      | 51        | 0.38%   |
| 10      | 41        | 0.31%   |
| 52      | 31        | 0.23%   |
| 65      | 27        | 0.2%    |
| 28      | 22        | 0.16%   |
| 48      | 21        | 0.16%   |
| 37      | 17        | 0.13%   |
| 39      | 16        | 0.12%   |
| 46      | 15        | 0.11%   |
| 35      | 14        | 0.1%    |
| 33      | 14        | 0.1%    |
| 29      | 14        | 0.1%    |
| 142     | 13        | 0.1%    |
| 42      | 13        | 0.1%    |
| 74      | 11        | 0.08%   |
| 60      | 10        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 4734      | 35.73%  |
| 501-600        | 2693      | 20.33%  |
| 401-500        | 2273      | 17.16%  |
| 351-400        | 1088      | 8.21%   |
| 201-300        | 1083      | 8.17%   |
| 601-700        | 474       | 3.58%   |
| 701-800        | 218       | 1.65%   |
| 1001-1500      | 212       | 1.6%    |
| 1501-2000      | 193       | 1.46%   |
| Unknown        | 127       | 0.96%   |
| 801-900        | 114       | 0.86%   |
| 901-1000       | 23        | 0.17%   |
| More than 2000 | 13        | 0.1%    |
| 1-100          | 3         | 0.02%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 10078     | 79.04%  |
| 16/10   | 1648      | 12.93%  |
| 5/4     | 558       | 4.38%   |
| 21/9    | 131       | 1.03%   |
| 4/3     | 120       | 0.94%   |
| 3/2     | 114       | 0.89%   |
| Unknown | 45        | 0.35%   |
| 32/9    | 16        | 0.13%   |
| 6/5     | 13        | 0.1%    |
| 1.00    | 13        | 0.1%    |
| 0.67    | 3         | 0.02%   |
| 2.12    | 2         | 0.02%   |
| 1.96    | 2         | 0.02%   |
| 3.40    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 2.01    | 1         | 0.01%   |
| 2.00    | 1         | 0.01%   |
| 0.75    | 1         | 0.01%   |
| 0.63    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3196      | 24%     |
| 201-250        | 2639      | 19.81%  |
| 81-90          | 1393      | 10.46%  |
| 151-200        | 1179      | 8.85%   |
| 301-350        | 922       | 6.92%   |
| 141-150        | 631       | 4.74%   |
| 351-500        | 579       | 4.35%   |
| 121-130        | 528       | 3.96%   |
| 71-80          | 483       | 3.63%   |
| More than 1000 | 384       | 2.88%   |
| 251-300        | 348       | 2.61%   |
| 51-60          | 260       | 1.95%   |
| 61-70          | 224       | 1.68%   |
| 501-1000       | 177       | 1.33%   |
| Unknown        | 127       | 0.95%   |
| 131-140        | 125       | 0.94%   |
| 111-120        | 57        | 0.43%   |
| 41-50          | 37        | 0.28%   |
| 91-100         | 26        | 0.2%    |
| 1-40           | 4         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 5406      | 41.36%  |
| 101-120       | 4173      | 31.92%  |
| 121-160       | 2508      | 19.19%  |
| 161-240       | 432       | 3.3%    |
| 1-50          | 333       | 2.55%   |
| Unknown       | 127       | 0.97%   |
| More than 240 | 93        | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 12157     | 91.15%  |
| 2     | 993       | 7.44%   |
| 0     | 132       | 0.99%   |
| 3     | 45        | 0.34%   |
| 4     | 7         | 0.05%   |
| 6     | 2         | 0.01%   |
| 7     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 7755      | 39.65%  |
| Intel                             | 5259      | 26.89%  |
| Qualcomm Atheros                  | 2792      | 14.28%  |
| Broadcom                          | 981       | 5.02%   |
| Marvell Technology Group          | 269       | 1.38%   |
| Ralink Technology                 | 260       | 1.33%   |
| Ralink                            | 252       | 1.29%   |
| Broadcom Limited                  | 250       | 1.28%   |
| Nvidia                            | 228       | 1.17%   |
| Samsung Electronics               | 169       | 0.86%   |
| TP-Link                           | 140       | 0.72%   |
| MediaTek                          | 128       | 0.65%   |
| Qualcomm Atheros Communications   | 82        | 0.42%   |
| Huawei Technologies               | 82        | 0.42%   |
| JMicron Technology                | 70        | 0.36%   |
| Dell                              | 57        | 0.29%   |
| ASIX Electronics                  | 50        | 0.26%   |
| Ericsson Business Mobile Networks | 46        | 0.24%   |
| D-Link                            | 46        | 0.24%   |
| D-Link System                     | 43        | 0.22%   |
| NetGear                           | 38        | 0.19%   |
| ASUSTek Computer                  | 36        | 0.18%   |
| Sierra Wireless                   | 30        | 0.15%   |
| Xiaomi                            | 29        | 0.15%   |
| Belkin Components                 | 29        | 0.15%   |
| VIA Technologies                  | 27        | 0.14%   |
| Motorola PCS                      | 25        | 0.13%   |
| Microsoft                         | 25        | 0.13%   |
| Aquantia                          | 22        | 0.11%   |
| Linksys                           | 20        | 0.1%    |
| ZTE WCDMA Technologies MSM        | 19        | 0.1%    |
| Edimax Technology                 | 19        | 0.1%    |
| DisplayLink                       | 19        | 0.1%    |
| Hewlett-Packard                   | 18        | 0.09%   |
| IMC Networks                      | 14        | 0.07%   |
| AVM                               | 14        | 0.07%   |
| OPPO Electronics                  | 13        | 0.07%   |
| 3Com                              | 13        | 0.07%   |
| Qualcomm                          | 12        | 0.06%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5537      | 24.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1056      | 4.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 529       | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 442       | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 416       | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 366       | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 360       | 1.6%    |
| Intel Wi-Fi 6 AX200                                               | 315       | 1.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 289       | 1.28%   |
| Intel Wireless 7265                                               | 269       | 1.19%   |
| Intel Ethernet Connection I217-LM                                 | 231       | 1.02%   |
| Intel Wireless 8265 / 8275                                        | 221       | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 213       | 0.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 210       | 0.93%   |
| Intel Wireless 7260                                               | 202       | 0.9%    |
| Intel I211 Gigabit Network Connection                             | 201       | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 195       | 0.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 182       | 0.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 179       | 0.79%   |
| Intel Wireless 3165                                               | 178       | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 169       | 0.75%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 169       | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 168       | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 166       | 0.74%   |
| Intel Wireless 8260                                               | 163       | 0.72%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 158       | 0.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 151       | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 150       | 0.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 144       | 0.64%   |
| Ralink MT7601U Wireless Adapter                                   | 119       | 0.53%   |
| Intel Wireless 3160                                               | 119       | 0.53%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 119       | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 117       | 0.52%   |
| Intel WiFi Link 5100                                              | 108       | 0.48%   |
| Nvidia MCP61 Ethernet                                             | 105       | 0.47%   |
| Intel Wi-Fi 6 AX201                                               | 105       | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 100       | 0.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 98        | 0.43%   |
| Intel Ethernet Controller I225-V                                  | 98        | 0.43%   |
| Intel 82577LM Gigabit Network Connection                          | 96        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 3655      | 38.53%  |
| Qualcomm Atheros                      | 2219      | 23.39%  |
| Realtek Semiconductor                 | 1765      | 18.61%  |
| Broadcom                              | 554       | 5.84%   |
| Ralink Technology                     | 260       | 2.74%   |
| Ralink                                | 252       | 2.66%   |
| MediaTek                              | 106       | 1.12%   |
| Broadcom Limited                      | 106       | 1.12%   |
| TP-Link                               | 102       | 1.08%   |
| Qualcomm Atheros Communications       | 82        | 0.86%   |
| D-Link                                | 42        | 0.44%   |
| ASUSTek Computer                      | 36        | 0.38%   |
| NetGear                               | 31        | 0.33%   |
| Sierra Wireless                       | 30        | 0.32%   |
| Dell                                  | 29        | 0.31%   |
| Belkin Components                     | 28        | 0.3%    |
| Microsoft                             | 23        | 0.24%   |
| D-Link System                         | 22        | 0.23%   |
| Edimax Technology                     | 19        | 0.2%    |
| Linksys                               | 18        | 0.19%   |
| Marvell Technology Group              | 14        | 0.15%   |
| IMC Networks                          | 14        | 0.15%   |
| AVM                                   | 14        | 0.15%   |
| Hewlett-Packard                       | 6         | 0.06%   |
| Mercucys                              | 5         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 5         | 0.05%   |
| ZyDAS                                 | 4         | 0.04%   |
| Wilocity                              | 4         | 0.04%   |
| Sitecom Europe                        | 4         | 0.04%   |
| Qcom                                  | 3         | 0.03%   |
| PLANEX                                | 3         | 0.03%   |
| Guillemot                             | 3         | 0.03%   |
| Fibocom                               | 3         | 0.03%   |
| ZyXEL Communications                  | 2         | 0.02%   |
| Wacom                                 | 2         | 0.02%   |
| Sweex                                 | 2         | 0.02%   |
| Senao                                 | 2         | 0.02%   |
| Philips (or NXP)                      | 2         | 0.02%   |
| Gemtek                                | 2         | 0.02%   |
| Chu Yuen Enterprise                   | 2         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 442       | 4.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 416       | 4.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 366       | 3.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 360       | 3.78%   |
| Intel Wi-Fi 6 AX200                                                     | 315       | 3.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 289       | 3.03%   |
| Intel Wireless 7265                                                     | 269       | 2.82%   |
| Intel Wireless 8265 / 8275                                              | 221       | 2.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 213       | 2.24%   |
| Intel Wireless 7260                                                     | 202       | 2.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 182       | 1.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 179       | 1.88%   |
| Intel Wireless 3165                                                     | 178       | 1.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 169       | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 166       | 1.74%   |
| Intel Wireless 8260                                                     | 163       | 1.71%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 151       | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 144       | 1.51%   |
| Ralink MT7601U Wireless Adapter                                         | 119       | 1.25%   |
| Intel Wireless 3160                                                     | 119       | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 117       | 1.23%   |
| Intel WiFi Link 5100                                                    | 108       | 1.13%   |
| Intel Wi-Fi 6 AX201                                                     | 105       | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 98        | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 95        | 1%      |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 95        | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 95        | 1%      |
| Intel Cannon Lake PCH CNVi WiFi                                         | 95        | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 91        | 0.96%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 86        | 0.9%    |
| Intel Wireless-AC 9260                                                  | 85        | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 84        | 0.88%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 83        | 0.87%   |
| Intel Centrino Advanced-N 6200                                          | 83        | 0.87%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 80        | 0.84%   |
| Intel Centrino Ultimate-N 6300                                          | 79        | 0.83%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 77        | 0.81%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 75        | 0.79%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 73        | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                           | 72        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 7115      | 56.11%  |
| Intel                            | 2816      | 22.21%  |
| Qualcomm Atheros                 | 865       | 6.82%   |
| Broadcom                         | 551       | 4.35%   |
| Marvell Technology Group         | 255       | 2.01%   |
| Nvidia                           | 227       | 1.79%   |
| Samsung Electronics              | 159       | 1.25%   |
| Broadcom Limited                 | 147       | 1.16%   |
| Huawei Technologies              | 73        | 0.58%   |
| JMicron Technology               | 70        | 0.55%   |
| ASIX Electronics                 | 50        | 0.39%   |
| TP-Link                          | 40        | 0.32%   |
| Xiaomi                           | 29        | 0.23%   |
| VIA Technologies                 | 24        | 0.19%   |
| MediaTek                         | 22        | 0.17%   |
| Aquantia                         | 22        | 0.17%   |
| D-Link System                    | 21        | 0.17%   |
| DisplayLink                      | 19        | 0.15%   |
| ZTE WCDMA Technologies MSM       | 18        | 0.14%   |
| Motorola PCS                     | 17        | 0.13%   |
| OPPO Electronics                 | 13        | 0.1%    |
| 3Com                             | 13        | 0.1%    |
| Silicon Integrated Systems [SiS] | 11        | 0.09%   |
| Qualcomm                         | 11        | 0.09%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.06%   |
| NetGear                          | 7         | 0.06%   |
| ICS Advent                       | 7         | 0.06%   |
| T & A Mobile Phones              | 6         | 0.05%   |
| Lenovo                           | 5         | 0.04%   |
| Apple                            | 5         | 0.04%   |
| Spreadtrum Communications        | 4         | 0.03%   |
| HTC (High Tech Computer)         | 4         | 0.03%   |
| Hewlett-Packard                  | 4         | 0.03%   |
| Google                           | 4         | 0.03%   |
| D-Link                           | 4         | 0.03%   |
| vivo                             | 3         | 0.02%   |
| Mellanox Technologies            | 3         | 0.02%   |
| LG Electronics                   | 3         | 0.02%   |
| HMD Global                       | 3         | 0.02%   |
| Attansic Technology              | 3         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 5537      | 42.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1056      | 8.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 529       | 4.1%    |
| Intel Ethernet Connection I217-LM                                 | 231       | 1.79%   |
| Realtek RTL8125 2.5GbE Controller                                 | 210       | 1.63%   |
| Intel I211 Gigabit Network Connection                             | 201       | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 195       | 1.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 169       | 1.31%   |
| Intel Ethernet Connection (2) I219-V                              | 168       | 1.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 158       | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 150       | 1.16%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 119       | 0.92%   |
| Nvidia MCP61 Ethernet                                             | 105       | 0.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 100       | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 98        | 0.76%   |
| Intel 82577LM Gigabit Network Connection                          | 96        | 0.74%   |
| Intel 82567LM Gigabit Network Connection                          | 88        | 0.68%   |
| Intel Ethernet Connection (7) I219-V                              | 84        | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 81        | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 81        | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 77        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 74        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 72        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 70        | 0.54%   |
| Intel Ethernet Connection (3) I218-LM                             | 69        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 69        | 0.54%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 67        | 0.52%   |
| Intel Ethernet Connection I218-LM                                 | 64        | 0.5%    |
| Intel Ethernet Connection I219-LM                                 | 60        | 0.47%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 57        | 0.44%   |
| Huawei E353/E3131                                                 | 52        | 0.4%    |
| Intel Ethernet Connection (4) I219-LM                             | 51        | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 50        | 0.39%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 50        | 0.39%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 49        | 0.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 49        | 0.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 46        | 0.36%   |
| Intel 82574L Gigabit Network Connection                           | 45        | 0.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 44        | 0.34%   |
| Intel Ethernet Connection (2) I218-V                              | 44        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 12144     | 56.63%  |
| WiFi     | 9151      | 42.67%  |
| Modem    | 126       | 0.59%   |
| Unknown  | 25        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7381      | 56.42%  |
| WiFi     | 5701      | 43.58%  |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6981      | 52.45%  |
| 1     | 6007      | 45.13%  |
| 3     | 174       | 1.31%   |
| 0     | 119       | 0.89%   |
| 4     | 22        | 0.17%   |
| 5     | 3         | 0.02%   |
| 6     | 2         | 0.02%   |
| 10    | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 9724      | 72.46%  |
| Yes     | 3695      | 27.53%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2642      | 39.78%  |
| Realtek Semiconductor           | 700       | 10.54%  |
| Qualcomm Atheros Communications | 650       | 9.79%   |
| Cambridge Silicon Radio         | 475       | 7.15%   |
| Broadcom                        | 429       | 6.46%   |
| Lite-On Technology              | 330       | 4.97%   |
| IMC Networks                    | 295       | 4.44%   |
| Foxconn / Hon Hai               | 202       | 3.04%   |
| Apple                           | 178       | 2.68%   |
| Dell                            | 126       | 1.9%    |
| ASUSTek Computer                | 117       | 1.76%   |
| Toshiba                         | 102       | 1.54%   |
| Hewlett-Packard                 | 94        | 1.42%   |
| Ralink                          | 61        | 0.92%   |
| MediaTek                        | 33        | 0.5%    |
| Realtek                         | 28        | 0.42%   |
| Alps Electric                   | 21        | 0.32%   |
| Foxconn International           | 19        | 0.29%   |
| Marvell Semiconductor           | 15        | 0.23%   |
| Ralink Technology               | 14        | 0.21%   |
| Chicony Electronics             | 13        | 0.2%    |
| Belkin Components               | 12        | 0.18%   |
| Askey Computer                  | 12        | 0.18%   |
| TP-Link                         | 11        | 0.17%   |
| Integrated System Solution      | 11        | 0.17%   |
| Fujitsu                         | 7         | 0.11%   |
| Micro Star International        | 6         | 0.09%   |
| Edimax Technology               | 6         | 0.09%   |
| Dynex                           | 6         | 0.09%   |
| Primax Electronics              | 5         | 0.08%   |
| Taiyo Yuden                     | 4         | 0.06%   |
| Qcom                            | 3         | 0.05%   |
| Unknown                         | 3         | 0.05%   |
| SINO WEALTH                     | 2         | 0.03%   |
| ISSC                            | 2         | 0.03%   |
| Accel Semiconductor             | 2         | 0.03%   |
| USI                             | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |
| Smart Modular Technologies      | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 1184      | 17.82%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 475       | 7.15%   |
| Realtek Bluetooth Radio                                                             | 433       | 6.52%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 353       | 5.31%   |
| Intel AX200 Bluetooth                                                               | 302       | 4.54%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 293       | 4.41%   |
| Intel AX201 Bluetooth                                                               | 293       | 4.41%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 180       | 2.71%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 179       | 2.69%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 123       | 1.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 121       | 1.82%   |
| IMC Networks Bluetooth Radio                                                        | 117       | 1.76%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 106       | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 103       | 1.55%   |
| Intel Bluetooth Device                                                              | 88        | 1.32%   |
| IMC Networks Bluetooth Device                                                       | 83        | 1.25%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 81        | 1.22%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 77        | 1.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 75        | 1.13%   |
| Lite-On Bluetooth Device                                                            | 74        | 1.11%   |
| Apple Bluetooth Host Controller                                                     | 72        | 1.08%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 68        | 1.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 67        | 1.01%   |
| Intel AX210 Bluetooth                                                               | 64        | 0.96%   |
| Ralink RT3290 Bluetooth                                                             | 61        | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 60        | 0.9%    |
| Apple Bluetooth USB Host Controller                                                 | 55        | 0.83%   |
| Dell DW375 Bluetooth Module                                                         | 54        | 0.81%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 50        | 0.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 43        | 0.65%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 41        | 0.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 40        | 0.6%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 39        | 0.59%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 38        | 0.57%   |
| Realtek RTL8723B Bluetooth                                                          | 37        | 0.56%   |
| Toshiba Bluetooth Device                                                            | 33        | 0.5%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 32        | 0.48%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 32        | 0.48%   |
| Realtek RTL8821A Bluetooth                                                          | 31        | 0.47%   |
| MediaTek Wireless_Device                                                            | 31        | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 9583      | 54.28%  |
| AMD                                  | 4004      | 22.68%  |
| Nvidia                               | 2890      | 16.37%  |
| C-Media Electronics                  | 247       | 1.4%    |
| Creative Labs                        | 173       | 0.98%   |
| Logitech                             | 80        | 0.45%   |
| Texas Instruments                    | 56        | 0.32%   |
| Generalplus Technology               | 47        | 0.27%   |
| Creative Technology                  | 45        | 0.25%   |
| JMTek                                | 44        | 0.25%   |
| ASUSTek Computer                     | 29        | 0.16%   |
| VIA Technologies                     | 27        | 0.15%   |
| Tenx Technology                      | 19        | 0.11%   |
| Razer USA                            | 18        | 0.1%    |
| GN Netcom                            | 16        | 0.09%   |
| Focusrite-Novation                   | 15        | 0.08%   |
| Realtek Semiconductor                | 13        | 0.07%   |
| Kingston Technology                  | 12        | 0.07%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.06%   |
| Plantronics                          | 10        | 0.06%   |
| Dell                                 | 10        | 0.06%   |
| XMOS                                 | 9         | 0.05%   |
| SteelSeries ApS                      | 9         | 0.05%   |
| KTMicro                              | 9         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 8         | 0.05%   |
| Samson Technologies                  | 8         | 0.05%   |
| PreSonus Audio Electronics           | 8         | 0.05%   |
| Hewlett-Packard                      | 8         | 0.05%   |
| Giga-Byte Technology                 | 8         | 0.05%   |
| Corsair                              | 8         | 0.05%   |
| Yamaha                               | 7         | 0.04%   |
| Micro Star International             | 7         | 0.04%   |
| M-Audio                              | 7         | 0.04%   |
| SAVITECH                             | 6         | 0.03%   |
| Lenovo                               | 6         | 0.03%   |
| Blue Microphones                     | 6         | 0.03%   |
| Apple                                | 6         | 0.03%   |
| Sony                                 | 5         | 0.03%   |
| ROCCAT                               | 5         | 0.03%   |
| GYROCOM C&C                          | 5         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1174      | 5.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1147      | 5.4%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 930       | 4.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 747       | 3.52%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 745       | 3.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 742       | 3.49%   |
| AMD FCH Azalia Controller                                                                         | 655       | 3.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 579       | 2.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 564       | 2.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 563       | 2.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 456       | 2.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 451       | 2.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 390       | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 377       | 1.78%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 368       | 1.73%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 344       | 1.62%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 327       | 1.54%   |
| Intel 8 Series HD Audio Controller                                                                | 298       | 1.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 295       | 1.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 292       | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 279       | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 278       | 1.31%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 269       | 1.27%   |
| Intel Broadwell-U Audio Controller                                                                | 266       | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 262       | 1.23%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 262       | 1.23%   |
| Intel 200 Series PCH HD Audio                                                                     | 255       | 1.2%    |
| Nvidia High Definition Audio Controller                                                           | 248       | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 233       | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 232       | 1.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 202       | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 193       | 0.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 167       | 0.79%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 166       | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 160       | 0.75%   |
| AMD Wrestler HDMI Audio                                                                           | 150       | 0.71%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 149       | 0.7%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 147       | 0.69%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 140       | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 138       | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2941      | 18.62%  |
| SK hynix            | 2376      | 15.04%  |
| Unknown             | 2112      | 13.37%  |
| Kingston            | 2086      | 13.21%  |
| Micron Technology   | 1247      | 7.9%    |
| Crucial             | 838       | 5.31%   |
| Corsair             | 677       | 4.29%   |
| G.Skill             | 483       | 3.06%   |
| Elpida              | 398       | 2.52%   |
| A-DATA Technology   | 353       | 2.24%   |
| Ramaxel Technology  | 290       | 1.84%   |
| Nanya Technology    | 271       | 1.72%   |
| Smart               | 160       | 1.01%   |
| Unknown (ABCD)      | 136       | 0.86%   |
| Unknown             | 136       | 0.86%   |
| Patriot             | 120       | 0.76%   |
| Team                | 119       | 0.75%   |
| GOODRAM             | 83        | 0.53%   |
| Transcend           | 68        | 0.43%   |
| AMD                 | 56        | 0.35%   |
| Apacer              | 53        | 0.34%   |
| Teikon              | 41        | 0.26%   |
| ASint Technology    | 33        | 0.21%   |
| Toshiba             | 30        | 0.19%   |
| Silicon Power       | 30        | 0.19%   |
| Qimonda             | 29        | 0.18%   |
| Kingmax             | 29        | 0.18%   |
| Avant               | 27        | 0.17%   |
| Unifosa             | 23        | 0.15%   |
| GeIL                | 22        | 0.14%   |
| High Bridge         | 21        | 0.13%   |
| PNY                 | 20        | 0.13%   |
| Multilaser          | 19        | 0.12%   |
| CSX                 | 19        | 0.12%   |
| Smart Brazil        | 16        | 0.1%    |
| Timetec             | 15        | 0.09%   |
| Goldkey             | 12        | 0.08%   |
| Neo Forza           | 10        | 0.06%   |
| Kllisre             | 10        | 0.06%   |
| Atermiter           | 10        | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 165       | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 146       | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 142       | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 140       | 0.81%   |
| Unknown                                                          | 136       | 0.79%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 127       | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 123       | 0.72%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 123       | 0.72%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 119       | 0.69%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 115       | 0.67%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 101       | 0.59%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 100       | 0.58%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 97        | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 96        | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 94        | 0.55%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 90        | 0.52%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 88        | 0.51%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 87        | 0.51%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 83        | 0.48%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 68        | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 66        | 0.38%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 65        | 0.38%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 64        | 0.37%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 62        | 0.36%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 60        | 0.35%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 59        | 0.34%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 58        | 0.34%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 57        | 0.33%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 55        | 0.32%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 55        | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 54        | 0.31%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 53        | 0.31%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 53        | 0.31%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 52        | 0.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 50        | 0.29%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 50        | 0.29%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 49        | 0.29%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 48        | 0.28%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 48        | 0.28%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 47        | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 6077      | 45.29%  |
| DDR4    | 4282      | 31.91%  |
| DDR2    | 1114      | 8.3%    |
| SDRAM   | 648       | 4.83%   |
| Unknown | 647       | 4.82%   |
| LPDDR4  | 354       | 2.64%   |
| DDR     | 116       | 0.86%   |
| LPDDR3  | 98        | 0.73%   |
| DDR5    | 38        | 0.28%   |
| DRAM    | 29        | 0.22%   |
| LPDDR5  | 15        | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 6891      | 52.23%  |
| DIMM         | 5866      | 44.46%  |
| Row Of Chips | 368       | 2.79%   |
| Chip         | 30        | 0.23%   |
| Unknown      | 20        | 0.15%   |
| RIMM         | 10        | 0.08%   |
| FB-DIMM      | 8         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 5466      | 36.74%  |
| 8192  | 4307      | 28.95%  |
| 2048  | 3118      | 20.96%  |
| 16384 | 987       | 6.63%   |
| 1024  | 727       | 4.89%   |
| 32768 | 191       | 1.28%   |
| 512   | 74        | 0.5%    |
| 256   | 2         | 0.01%   |
| 65536 | 1         | 0.01%   |
| 3072  | 1         | 0.01%   |
| 64    | 1         | 0.01%   |
| 32    | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 3784      | 25.36%  |
| 1333    | 1621      | 10.86%  |
| 2667    | 1371      | 9.19%   |
| 3200    | 1031      | 6.91%   |
| 2400    | 1013      | 6.79%   |
| 1334    | 706       | 4.73%   |
| 667     | 619       | 4.15%   |
| 800     | 594       | 3.98%   |
| 2133    | 512       | 3.43%   |
| Unknown | 431       | 2.89%   |
| 3600    | 317       | 2.12%   |
| 1067    | 298       | 2%      |
| 1867    | 258       | 1.73%   |
| 1066    | 172       | 1.15%   |
| 3266    | 148       | 0.99%   |
| 1866    | 147       | 0.99%   |
| 4199    | 133       | 0.89%   |
| 2048    | 113       | 0.76%   |
| 2666    | 112       | 0.75%   |
| 533     | 109       | 0.73%   |
| 4267    | 98        | 0.66%   |
| 3400    | 97        | 0.65%   |
| 1800    | 93        | 0.62%   |
| 3000    | 88        | 0.59%   |
| 2933    | 88        | 0.59%   |
| 400     | 84        | 0.56%   |
| 975     | 79        | 0.53%   |
| 3733    | 52        | 0.35%   |
| 3800    | 40        | 0.27%   |
| 3866    | 39        | 0.26%   |
| 2800    | 38        | 0.25%   |
| 3533    | 35        | 0.23%   |
| 3466    | 33        | 0.22%   |
| 333     | 33        | 0.22%   |
| 4266    | 31        | 0.21%   |
| 3666    | 28        | 0.19%   |
| 4800    | 27        | 0.18%   |
| 1639    | 27        | 0.18%   |
| 2000    | 26        | 0.17%   |
| 1648    | 23        | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 188       | 39.5%   |
| Brother Industries    | 95        | 19.96%  |
| Canon                 | 71        | 14.92%  |
| Seiko Epson           | 41        | 8.61%   |
| Samsung Electronics   | 41        | 8.61%   |
| Lexmark International | 10        | 2.1%    |
| Prolific Technology   | 7         | 1.47%   |
| QinHeng Electronics   | 5         | 1.05%   |
| Xerox                 | 4         | 0.84%   |
| Kyocera               | 4         | 0.84%   |
| Dymo-CoStar           | 3         | 0.63%   |
| Ricoh                 | 2         | 0.42%   |
| Zebra                 | 1         | 0.21%   |
| Oki Data              | 1         | 0.21%   |
| NXP Semiconductors    | 1         | 0.21%   |
| MIIIW                 | 1         | 0.21%   |
| Citizen               | 1         | 0.21%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP DeskJet 2700 series               | 8         | 1.66%   |
| HP DeskJet 2600 series               | 8         | 1.66%   |
| Prolific PL2305 Parallel Port        | 7         | 1.45%   |
| HP ENVY 4520 series                  | 7         | 1.45%   |
| HP DeskJet 3630 series               | 7         | 1.45%   |
| Samsung ML-1640 Series Laser Printer | 6         | 1.24%   |
| Samsung M2070 Series                 | 6         | 1.24%   |
| HP DeskJet 2130 series               | 6         | 1.24%   |
| Brother Printer                      | 6         | 1.24%   |
| Brother HL-L2390DW                   | 6         | 1.24%   |
| Samsung M2020 Series                 | 5         | 1.04%   |
| QinHeng CH340S                       | 5         | 1.04%   |
| HP LaserJet 1020                     | 5         | 1.04%   |
| HP LaserJet 1018                     | 5         | 1.04%   |
| Seiko Epson ET-2710 Series           | 4         | 0.83%   |
| HP LaserJet P1006                    | 4         | 0.83%   |
| HP LaserJet P1005                    | 4         | 0.83%   |
| HP Ink Tank Wireless 410 series      | 4         | 0.83%   |
| HP ENVY Photo 6200 series            | 4         | 0.83%   |
| Canon PIXMA MX920 Series             | 4         | 0.83%   |
| Canon PIXMA MG3600 Series            | 4         | 0.83%   |
| Brother DCP-7055W                    | 4         | 0.83%   |
| Seiko Epson L365 Series              | 3         | 0.62%   |
| Seiko Epson L120 Series              | 3         | 0.62%   |
| Samsung SCX-3400 Series              | 3         | 0.62%   |
| Samsung ML-2010P Mono Laser Printer  | 3         | 0.62%   |
| HP OfficeJet Pro 7740 series         | 3         | 0.62%   |
| HP OfficeJet 6950                    | 3         | 0.62%   |
| HP LaserJet Pro M148f-M149f          | 3         | 0.62%   |
| HP LaserJet P1102                    | 3         | 0.62%   |
| HP LaserJet 1200                     | 3         | 0.62%   |
| HP LaserJet 1010                     | 3         | 0.62%   |
| HP ENVY 5000 series                  | 3         | 0.62%   |
| HP Deskjet F4500 series              | 3         | 0.62%   |
| HP Deskjet 2050 J510                 | 3         | 0.62%   |
| HP Deskjet 1050 J410                 | 3         | 0.62%   |
| Canon TS5100 series                  | 3         | 0.62%   |
| Canon TR8500 series                  | 3         | 0.62%   |
| Canon PIXMA MG2500 Series            | 3         | 0.62%   |
| Canon LiDE 300                       | 3         | 0.62%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 49        | 55.06%  |
| Hewlett-Packard             | 13        | 14.61%  |
| Seiko Epson                 | 12        | 13.48%  |
| Mustek Systems              | 7         | 7.87%   |
| AGFA-Gevaert NV             | 3         | 3.37%   |
| KYE Systems (Mouse Systems) | 2         | 2.25%   |
| Plustek                     | 1         | 1.12%   |
| Fujitsu                     | 1         | 1.12%   |
| Acer Peripherals (now BenQ) | 1         | 1.12%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 9         | 10.11%  |
| Canon CanoScan LiDE 210                                  | 7         | 7.87%   |
| Canon CanoScan LiDE 100                                  | 6         | 6.74%   |
| Canon CanoScan LiDE 120                                  | 4         | 4.49%   |
| Mustek Systems ScanExpress 1200 UB                       | 3         | 3.37%   |
| Canon CanoScan N1240U/LiDE 30                            | 3         | 3.37%   |
| Canon CanoScan LIDE 25                                   | 3         | 3.37%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 2         | 2.25%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 2.25%   |
| HP ScanJet 5590                                          | 2         | 2.25%   |
| HP ScanJet 4500C/5550C                                   | 2         | 2.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 2.25%   |
| Canon CanoScan LiDE 70                                   | 2         | 2.25%   |
| Canon CanoScan LiDE 60                                   | 2         | 2.25%   |
| Canon CanoScan LiDE 220                                  | 2         | 2.25%   |
| Canon CanoScan LiDE 200                                  | 2         | 2.25%   |
| AGFA-Gevaert NV SnapScan e20                             | 2         | 2.25%   |
| Seiko Epson Scanner                                      | 1         | 1.12%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1         | 1.12%   |
| Seiko Epson GT-X770 [Perfection V500]                    | 1         | 1.12%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1         | 1.12%   |
| Seiko Epson GT-F700 [Perfection V350]                    | 1         | 1.12%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 1.12%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 1.12%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1         | 1.12%   |
| Plustek 600DPI USB Scanner                               | 1         | 1.12%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 1.12%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 1.12%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1         | 1.12%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1         | 1.12%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 1.12%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE      | 1         | 1.12%   |
| HP ScanJet G4010                                         | 1         | 1.12%   |
| HP ScanJet 4570c                                         | 1         | 1.12%   |
| HP ScanJet 4370                                          | 1         | 1.12%   |
| HP ScanJet 3800c                                         | 1         | 1.12%   |
| HP ScanJet 3670                                          | 1         | 1.12%   |
| HP ScanJet 2400c                                         | 1         | 1.12%   |
| HP ScanJet 2300c                                         | 1         | 1.12%   |
| HP ScanJet 2200c                                         | 1         | 1.12%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1565      | 23.3%   |
| Realtek Semiconductor                  | 583       | 8.68%   |
| Microdia                               | 556       | 8.28%   |
| IMC Networks                           | 484       | 7.2%    |
| Suyin                                  | 356       | 5.3%    |
| Logitech                               | 338       | 5.03%   |
| Sunplus Innovation Technology          | 331       | 4.93%   |
| Bison Electronics                      | 260       | 3.87%   |
| Quanta                                 | 249       | 3.71%   |
| Cheng Uei Precision Industry (Foxlink) | 240       | 3.57%   |
| Syntek                                 | 201       | 2.99%   |
| Acer                                   | 155       | 2.31%   |
| Apple                                  | 145       | 2.16%   |
| Silicon Motion                         | 121       | 1.8%    |
| Alcor Micro                            | 121       | 1.8%    |
| Lite-On Technology                     | 117       | 1.74%   |
| Ricoh                                  | 104       | 1.55%   |
| Microsoft                              | 69        | 1.03%   |
| Z-Star Microelectronics                | 57        | 0.85%   |
| Lenovo                                 | 57        | 0.85%   |
| Luxvisions Innotech Limited            | 53        | 0.79%   |
| Importek                               | 47        | 0.7%    |
| ALi                                    | 38        | 0.57%   |
| Primax Electronics                     | 36        | 0.54%   |
| Samsung Electronics                    | 25        | 0.37%   |
| Generalplus Technology                 | 23        | 0.34%   |
| GEMBIRD                                | 22        | 0.33%   |
| Sonix Technology                       | 20        | 0.3%    |
| OmniVision Technologies                | 19        | 0.28%   |
| DigiTech                               | 19        | 0.28%   |
| Cubeternet                             | 17        | 0.25%   |
| Creative Technology                    | 17        | 0.25%   |
| Aveo Technology                        | 17        | 0.25%   |
| KYE Systems (Mouse Systems)            | 16        | 0.24%   |
| ARC International                      | 15        | 0.22%   |
| Genesys Logic                          | 12        | 0.18%   |
| Jieli Technology                       | 11        | 0.16%   |
| Hewlett-Packard                        | 11        | 0.16%   |
| Sunplus Technology                     | 10        | 0.15%   |
| Huawei Technologies                    | 10        | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 196       | 2.9%    |
| Microdia Integrated_Webcam_HD                           | 171       | 2.53%   |
| Chicony HD WebCam                                       | 161       | 2.38%   |
| Realtek Integrated_Webcam_HD                            | 125       | 1.85%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 106       | 1.57%   |
| Sunplus Integrated_Webcam_HD                            | 103       | 1.52%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 96        | 1.42%   |
| IMC Networks Integrated Camera                          | 86        | 1.27%   |
| Syntek Integrated Camera                                | 84        | 1.24%   |
| Logitech Webcam C270                                    | 84        | 1.24%   |
| Realtek USB Camera                                      | 78        | 1.15%   |
| Microdia Integrated Webcam                              | 74        | 1.09%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 66        | 0.98%   |
| Chicony VGA Webcam                                      | 65        | 0.96%   |
| Chicony USB 2.0 Camera                                  | 61        | 0.9%    |
| Bison Integrated Camera                                 | 61        | 0.9%    |
| Realtek Integrated_Webcam_5M                            | 59        | 0.87%   |
| Chicony TOSHIBA Web Camera - HD                         | 55        | 0.81%   |
| Chicony HP Truevision HD                                | 55        | 0.81%   |
| Sunplus HD WebCam                                       | 53        | 0.78%   |
| Chicony Lenovo EasyCamera                               | 53        | 0.78%   |
| Syntek Lenovo EasyCamera                                | 50        | 0.74%   |
| Apple Built-in iSight                                   | 49        | 0.72%   |
| Chicony USB2.0 HD UVC WebCam                            | 47        | 0.69%   |
| Alcor Micro USB 2.0 Camera                              | 47        | 0.69%   |
| Chicony EasyCamera                                      | 45        | 0.66%   |
| Logitech HD Pro Webcam C920                             | 44        | 0.65%   |
| Lite-On Integrated Camera                               | 43        | 0.64%   |
| Chicony FJ Camera                                       | 43        | 0.64%   |
| Quanta VGA WebCam                                       | 42        | 0.62%   |
| Chicony HP TrueVision HD Camera                         | 42        | 0.62%   |
| Suyin Integrated_Webcam_HD                              | 40        | 0.59%   |
| Chicony USB2.0 VGA UVC WebCam                           | 40        | 0.59%   |
| Chicony HD User Facing                                  | 40        | 0.59%   |
| Chicony HP Webcam                                       | 39        | 0.58%   |
| Quanta HD User Facing                                   | 38        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 38        | 0.56%   |
| Bison Lenovo EasyCamera                                 | 38        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 36        | 0.53%   |
| Quanta HP TrueVision HD Camera                          | 35        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 294       | 37.22%  |
| AuthenTec                  | 123       | 15.57%  |
| Synaptics                  | 88        | 11.14%  |
| Upek                       | 80        | 10.13%  |
| Shenzhen Goodix Technology | 67        | 8.48%   |
| Elan Microelectronics      | 57        | 7.22%   |
| LighTuning Technology      | 39        | 4.94%   |
| STMicroelectronics         | 32        | 4.05%   |
| Samsung Electronics        | 4         | 0.51%   |
| Focal-systems.Corp         | 4         | 0.51%   |
| HOLTEK                     | 1         | 0.13%   |
| DigitalPersona             | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 74        | 9.37%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 54        | 6.84%   |
| AuthenTec AES2810                                                          | 44        | 5.57%   |
| Shenzhen Goodix  FingerPrint Device                                        | 42        | 5.32%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 38        | 4.81%   |
| Elan ELAN:Fingerprint                                                      | 36        | 4.56%   |
| STMicroelectronics Fingerprint Reader                                      | 32        | 4.05%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 32        | 4.05%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 30        | 3.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 28        | 3.54%   |
| Validity Sensors VFS491                                                    | 26        | 3.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 21        | 2.66%   |
| Shenzhen Goodix Fingerprint Reader                                         | 21        | 2.66%   |
| Elan ELAN:ARM-M4                                                           | 21        | 2.66%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 2.53%   |
| AuthenTec AES1600                                                          | 19        | 2.41%   |
| Synaptics  WBDI                                                            | 18        | 2.28%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 17        | 2.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 16        | 2.03%   |
| AuthenTec Fingerprint Sensor                                               | 15        | 1.9%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 1.77%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 1.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.65%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.14%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.01%   |
| Synaptics UWP WBDI                                                         | 7         | 0.89%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.89%   |
| Upek TCS5B Fingerprint sensor                                              | 6         | 0.76%   |
| Synaptics WBDI                                                             | 6         | 0.76%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 0.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 0.76%   |
| LighTuning Fingerprint Reader                                              | 6         | 0.76%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 6         | 0.76%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.63%   |
| Synaptics UWP WBDI Device                                                  | 5         | 0.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 0.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 0.51%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 4         | 0.51%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.51%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 222       | 47.84%  |
| Alcor Micro                       | 78        | 16.81%  |
| O2 Micro                          | 59        | 12.72%  |
| Upek                              | 35        | 7.54%   |
| Lenovo                            | 33        | 7.11%   |
| SCM Microsystems                  | 8         | 1.72%   |
| Gemalto (was Gemplus)             | 6         | 1.29%   |
| Realtek Semiconductor             | 5         | 1.08%   |
| OmniKey                           | 3         | 0.65%   |
| BIT4ID                            | 3         | 0.65%   |
| Advanced Card Systems             | 3         | 0.65%   |
| Reiner SCT Kartensysteme          | 2         | 0.43%   |
| VASCO Data Security International | 1         | 0.22%   |
| Microchip Technology              | 1         | 0.22%   |
| Hewlett-Packard                   | 1         | 0.22%   |
| Fujitsu Siemens Computers         | 1         | 0.22%   |
| Cherry                            | 1         | 0.22%   |
| Castles Technology                | 1         | 0.22%   |
| Aladdin Knowledge Systems         | 1         | 0.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 111       | 23.92%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 75        | 16.16%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 58        | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 55        | 11.85%  |
| Broadcom 5880                                                                | 44        | 9.48%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 35        | 7.54%   |
| Lenovo Integrated Smart Card Reader                                          | 33        | 7.11%   |
| Broadcom 58200                                                               | 11        | 2.37%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 1.08%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 0.65%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.43%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.43%   |
| BIT4ID miniLector EVO                                                        | 2         | 0.43%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.43%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.43%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.22%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 1         | 0.22%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.22%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.22%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.22%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.22%   |
| OmniKey CardMan 4321                                                         | 1         | 0.22%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.22%   |
| OmniKey CardMan 1021                                                         | 1         | 0.22%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.22%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.22%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.22%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.22%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.22%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.22%   |
| Castles Technology EZCCID Smart Card Reader                                  | 1         | 0.22%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.22%   |
| BIT4ID miniLector AIR NFC v3                                                 | 1         | 0.22%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.22%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.22%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 11026     | 82.62%  |
| 1     | 2020      | 15.14%  |
| 2     | 271       | 2.03%   |
| 3     | 24        | 0.18%   |
| 6     | 2         | 0.01%   |
| 4     | 2         | 0.01%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 790       | 30.37%  |
| Graphics card            | 570       | 21.91%  |
| Chipcard                 | 452       | 17.38%  |
| Net/wireless             | 251       | 9.65%   |
| Multimedia controller    | 136       | 5.23%   |
| Bluetooth                | 104       | 4%      |
| Storage                  | 72        | 2.77%   |
| Communication controller | 60        | 2.31%   |
| Camera                   | 58        | 2.23%   |
| Unassigned class         | 50        | 1.92%   |
| Sound                    | 14        | 0.54%   |
| Network                  | 12        | 0.46%   |
| Card reader              | 8         | 0.31%   |
| Flash memory             | 6         | 0.23%   |
| Wireless                 | 4         | 0.15%   |
| Net/ethernet             | 4         | 0.15%   |
| Modem                    | 4         | 0.15%   |
| Storage/raid             | 2         | 0.08%   |
| Storage/ata              | 2         | 0.08%   |
| Unclassified device      | 1         | 0.04%   |
| Dvb card                 | 1         | 0.04%   |

