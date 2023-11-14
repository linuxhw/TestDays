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

Total: 1769

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [b153378dab](https://linux-hardware.org/?probe=b153378dab) | Nov 06, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [985ed440bf](https://linux-hardware.org/?probe=985ed440bf) | Nov 06, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [1cf99ffe12](https://linux-hardware.org/?probe=1cf99ffe12) | Nov 05, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [cf8911c5e0](https://linux-hardware.org/?probe=cf8911c5e0) | Nov 05, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [451abee058](https://linux-hardware.org/?probe=451abee058) | Nov 05, 2023 |
| ASUSTek       | UX370UAR                    | Convertible | [754b927267](https://linux-hardware.org/?probe=754b927267) | Nov 05, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [9f19a2ba3a](https://linux-hardware.org/?probe=9f19a2ba3a) | Nov 04, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [d3a8398c99](https://linux-hardware.org/?probe=d3a8398c99) | Nov 04, 2023 |
| Acer          | Aspire R5-571TG             | Convertible | [f0e8c6a66f](https://linux-hardware.org/?probe=f0e8c6a66f) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d95fab9dc1](https://linux-hardware.org/?probe=d95fab9dc1) | Nov 04, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [b213aefe09](https://linux-hardware.org/?probe=b213aefe09) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [db71fb65bf](https://linux-hardware.org/?probe=db71fb65bf) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b592d36d74](https://linux-hardware.org/?probe=b592d36d74) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [da695062ba](https://linux-hardware.org/?probe=da695062ba) | Nov 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a08b1cfa29](https://linux-hardware.org/?probe=a08b1cfa29) | Nov 03, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [de293a4621](https://linux-hardware.org/?probe=de293a4621) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b0c996ac38](https://linux-hardware.org/?probe=b0c996ac38) | Nov 02, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [47abbeb9c1](https://linux-hardware.org/?probe=47abbeb9c1) | Nov 01, 2023 |
| MSI           | GV62 8RD                    | Notebook    | [d85cb220a0](https://linux-hardware.org/?probe=d85cb220a0) | Nov 01, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [5116fa401d](https://linux-hardware.org/?probe=5116fa401d) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [865e6764f2](https://linux-hardware.org/?probe=865e6764f2) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [bf87ba6b55](https://linux-hardware.org/?probe=bf87ba6b55) | Nov 01, 2023 |
| ASRock        | B450 Pro4 R2.0              | Desktop     | [c950f24711](https://linux-hardware.org/?probe=c950f24711) | Nov 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6af2aaed4e](https://linux-hardware.org/?probe=6af2aaed4e) | Nov 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [0dc16901b7](https://linux-hardware.org/?probe=0dc16901b7) | Nov 01, 2023 |
| Microsoft     | Surface Laptop Go 3         | Tablet      | [efa4316df1](https://linux-hardware.org/?probe=efa4316df1) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | Notebook    | [0b21a4419d](https://linux-hardware.org/?probe=0b21a4419d) | Nov 01, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0FS0... | Notebook    | [757199e3cf](https://linux-hardware.org/?probe=757199e3cf) | Nov 01, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6c1c4ea069](https://linux-hardware.org/?probe=6c1c4ea069) | Oct 31, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20SUA... | Notebook    | [701a08bdb6](https://linux-hardware.org/?probe=701a08bdb6) | Oct 31, 2023 |
| MSI           | Z270-A PRO                  | Desktop     | [b4e85014cc](https://linux-hardware.org/?probe=b4e85014cc) | Oct 31, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [62adc05f6a](https://linux-hardware.org/?probe=62adc05f6a) | Oct 31, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [55f41faf27](https://linux-hardware.org/?probe=55f41faf27) | Oct 31, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [64292785b9](https://linux-hardware.org/?probe=64292785b9) | Oct 31, 2023 |
| MSI           | PRO B550M-P GEN3            | Desktop     | [413254deb3](https://linux-hardware.org/?probe=413254deb3) | Oct 30, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [0b62ec2df6](https://linux-hardware.org/?probe=0b62ec2df6) | Oct 30, 2023 |
| MSI           | Modern 15 A11M              | Notebook    | [43161bd5f4](https://linux-hardware.org/?probe=43161bd5f4) | Oct 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [508c244637](https://linux-hardware.org/?probe=508c244637) | Oct 30, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f19f70993f](https://linux-hardware.org/?probe=f19f70993f) | Oct 30, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [3f0259e17b](https://linux-hardware.org/?probe=3f0259e17b) | Oct 30, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | Notebook    | [448c3ca446](https://linux-hardware.org/?probe=448c3ca446) | Oct 30, 2023 |
| Acer          | Aspire R5-571TG             | Convertible | [024085ccb0](https://linux-hardware.org/?probe=024085ccb0) | Oct 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [c1d00eb91f](https://linux-hardware.org/?probe=c1d00eb91f) | Oct 29, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [c9a6bd4217](https://linux-hardware.org/?probe=c9a6bd4217) | Oct 29, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [aaf303e411](https://linux-hardware.org/?probe=aaf303e411) | Oct 28, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [0e1711e674](https://linux-hardware.org/?probe=0e1711e674) | Oct 28, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | Notebook    | [e0dc47cf61](https://linux-hardware.org/?probe=e0dc47cf61) | Oct 28, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [96710ad70e](https://linux-hardware.org/?probe=96710ad70e) | Oct 28, 2023 |
| Gigabyte      | Z590 Gaming X               | Desktop     | [86bb741092](https://linux-hardware.org/?probe=86bb741092) | Oct 27, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [1f5d6e4141](https://linux-hardware.org/?probe=1f5d6e4141) | Oct 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [db2952a9d8](https://linux-hardware.org/?probe=db2952a9d8) | Oct 27, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [21bcc65553](https://linux-hardware.org/?probe=21bcc65553) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [5aef96bd0e](https://linux-hardware.org/?probe=5aef96bd0e) | Oct 25, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [6cd6569138](https://linux-hardware.org/?probe=6cd6569138) | Oct 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [95b5ac0a0e](https://linux-hardware.org/?probe=95b5ac0a0e) | Oct 24, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [9c37fcb5c9](https://linux-hardware.org/?probe=9c37fcb5c9) | Oct 24, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [8a67a1a41a](https://linux-hardware.org/?probe=8a67a1a41a) | Oct 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [e2e4b18ec2](https://linux-hardware.org/?probe=e2e4b18ec2) | Oct 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [9649ffc088](https://linux-hardware.org/?probe=9649ffc088) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [79ef1e4f2b](https://linux-hardware.org/?probe=79ef1e4f2b) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a5c33d9a5a](https://linux-hardware.org/?probe=a5c33d9a5a) | Oct 22, 2023 |
| ASRock        | B450M/ac R2.0               | Desktop     | [c1313fc22e](https://linux-hardware.org/?probe=c1313fc22e) | Oct 22, 2023 |
| HP            | Snappy                      | Notebook    | [2d0c13b032](https://linux-hardware.org/?probe=2d0c13b032) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [f103762ce5](https://linux-hardware.org/?probe=f103762ce5) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [147d6ad175](https://linux-hardware.org/?probe=147d6ad175) | Oct 21, 2023 |
| Gigabyte      | B760 GAMING X AX DDR4       | Desktop     | [eb5de485aa](https://linux-hardware.org/?probe=eb5de485aa) | Oct 21, 2023 |
| HP            | Snappy                      | Notebook    | [b8dc14dc5d](https://linux-hardware.org/?probe=b8dc14dc5d) | Oct 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [cd302f735e](https://linux-hardware.org/?probe=cd302f735e) | Oct 21, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [e5362858a0](https://linux-hardware.org/?probe=e5362858a0) | Oct 20, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [01544384cc](https://linux-hardware.org/?probe=01544384cc) | Oct 20, 2023 |
| Acer          | Aspire R5-571TG             | Convertible | [7e85436ec2](https://linux-hardware.org/?probe=7e85436ec2) | Oct 20, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [7deca235e3](https://linux-hardware.org/?probe=7deca235e3) | Oct 20, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [c01a27db62](https://linux-hardware.org/?probe=c01a27db62) | Oct 20, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [8fbbe4eec8](https://linux-hardware.org/?probe=8fbbe4eec8) | Oct 20, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [12b93b3f48](https://linux-hardware.org/?probe=12b93b3f48) | Oct 20, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [240879310d](https://linux-hardware.org/?probe=240879310d) | Oct 19, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [41666281fc](https://linux-hardware.org/?probe=41666281fc) | Oct 19, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ec015a6c9e](https://linux-hardware.org/?probe=ec015a6c9e) | Oct 19, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [e350eec913](https://linux-hardware.org/?probe=e350eec913) | Oct 19, 2023 |
| LTD Delovo... | EVE 1494E ES1280EW          | Tablet      | [97c02ed2e9](https://linux-hardware.org/?probe=97c02ed2e9) | Oct 17, 2023 |
| Positivo      | POS-PIG43BC SIM             | Desktop     | [ded7e15a49](https://linux-hardware.org/?probe=ded7e15a49) | Oct 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [172cfdcd26](https://linux-hardware.org/?probe=172cfdcd26) | Oct 16, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [5ee2d06317](https://linux-hardware.org/?probe=5ee2d06317) | Oct 15, 2023 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | Notebook    | [0d80ec0e27](https://linux-hardware.org/?probe=0d80ec0e27) | Oct 15, 2023 |
| Toshiba       | Satellite C855-1KF          | Notebook    | [1dbc7c0de3](https://linux-hardware.org/?probe=1dbc7c0de3) | Oct 15, 2023 |
| ASRock        | X470 Gaming K4              | Desktop     | [740122e9fa](https://linux-hardware.org/?probe=740122e9fa) | Oct 15, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [bc47dea2fe](https://linux-hardware.org/?probe=bc47dea2fe) | Oct 14, 2023 |
| Dell          | Inspiron 16 7630 2-in-1     | Convertible | [1156f51af6](https://linux-hardware.org/?probe=1156f51af6) | Oct 12, 2023 |
| MSI           | GS63 Stealth 8RE            | Notebook    | [a83fe5a954](https://linux-hardware.org/?probe=a83fe5a954) | Oct 11, 2023 |
| MSI           | GS63 Stealth 8RE            | Notebook    | [5f9d5460fb](https://linux-hardware.org/?probe=5f9d5460fb) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [d44d655589](https://linux-hardware.org/?probe=d44d655589) | Oct 11, 2023 |
| Gigabyte      | Z390 DESIGNARE-CF           | Desktop     | [3df74e5b96](https://linux-hardware.org/?probe=3df74e5b96) | Oct 11, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [04fbcfc11b](https://linux-hardware.org/?probe=04fbcfc11b) | Oct 10, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4071bd53ce](https://linux-hardware.org/?probe=4071bd53ce) | Oct 10, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [e1dc170ad7](https://linux-hardware.org/?probe=e1dc170ad7) | Oct 09, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5089a21326](https://linux-hardware.org/?probe=5089a21326) | Oct 07, 2023 |
| System76      | Gazelle                     | Notebook    | [1a40053c3e](https://linux-hardware.org/?probe=1a40053c3e) | Oct 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2d73d7e286](https://linux-hardware.org/?probe=2d73d7e286) | Oct 06, 2023 |
| Acer          | Aspire 7730G                | Notebook    | [d48f861a2e](https://linux-hardware.org/?probe=d48f861a2e) | Oct 05, 2023 |
| HP            | ZBook 14u G4                | Notebook    | [1d14da7190](https://linux-hardware.org/?probe=1d14da7190) | Oct 05, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | Notebook    | [cc02a5e08e](https://linux-hardware.org/?probe=cc02a5e08e) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8e0792976d](https://linux-hardware.org/?probe=8e0792976d) | Oct 03, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ca5985274a](https://linux-hardware.org/?probe=ca5985274a) | Oct 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [b992cbe7ae](https://linux-hardware.org/?probe=b992cbe7ae) | Oct 02, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [b5fcc0da7b](https://linux-hardware.org/?probe=b5fcc0da7b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b8068a8e68](https://linux-hardware.org/?probe=b8068a8e68) | Oct 02, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cacc534be7](https://linux-hardware.org/?probe=cacc534be7) | Oct 02, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [4e1788f184](https://linux-hardware.org/?probe=4e1788f184) | Oct 02, 2023 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [35830807d4](https://linux-hardware.org/?probe=35830807d4) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1c4b1aa68d](https://linux-hardware.org/?probe=1c4b1aa68d) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [988f015a89](https://linux-hardware.org/?probe=988f015a89) | Sep 30, 2023 |
| Lenovo        | ThinkPad E495 20NES07V00    | Notebook    | [935dc10f6b](https://linux-hardware.org/?probe=935dc10f6b) | Sep 30, 2023 |
| Dell          | Latitude 5410               | Notebook    | [d13c5769a3](https://linux-hardware.org/?probe=d13c5769a3) | Sep 30, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [0e67f3a0f3](https://linux-hardware.org/?probe=0e67f3a0f3) | Sep 29, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [670f7351b5](https://linux-hardware.org/?probe=670f7351b5) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1543bac588](https://linux-hardware.org/?probe=1543bac588) | Sep 27, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ed68f904fe](https://linux-hardware.org/?probe=ed68f904fe) | Sep 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e24beff974](https://linux-hardware.org/?probe=e24beff974) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [b8b2b3ff7e](https://linux-hardware.org/?probe=b8b2b3ff7e) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6677b81417](https://linux-hardware.org/?probe=6677b81417) | Sep 26, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [0dca41ca4e](https://linux-hardware.org/?probe=0dca41ca4e) | Sep 25, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [94ce4b6306](https://linux-hardware.org/?probe=94ce4b6306) | Sep 25, 2023 |
| MSI           | GS63VR 6RF                  | Notebook    | [03a9aed3c9](https://linux-hardware.org/?probe=03a9aed3c9) | Sep 25, 2023 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [7ea3152d65](https://linux-hardware.org/?probe=7ea3152d65) | Sep 25, 2023 |
| Dell          | G5 5505                     | Notebook    | [e9c461d44d](https://linux-hardware.org/?probe=e9c461d44d) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [cada97becf](https://linux-hardware.org/?probe=cada97becf) | Sep 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2b371179db](https://linux-hardware.org/?probe=2b371179db) | Sep 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2bb252778b](https://linux-hardware.org/?probe=2bb252778b) | Sep 25, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [f6369d0be5](https://linux-hardware.org/?probe=f6369d0be5) | Sep 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2d1e14cb66](https://linux-hardware.org/?probe=2d1e14cb66) | Sep 23, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [0f276cde5a](https://linux-hardware.org/?probe=0f276cde5a) | Sep 23, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [c6211ac3aa](https://linux-hardware.org/?probe=c6211ac3aa) | Sep 22, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [3a965cb7e3](https://linux-hardware.org/?probe=3a965cb7e3) | Sep 22, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [90c9ffe2e0](https://linux-hardware.org/?probe=90c9ffe2e0) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [45f00aaf92](https://linux-hardware.org/?probe=45f00aaf92) | Sep 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [7f327aca42](https://linux-hardware.org/?probe=7f327aca42) | Sep 21, 2023 |
| HP            | 212B                        | Desktop     | [f961d48c51](https://linux-hardware.org/?probe=f961d48c51) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [9fdc142c76](https://linux-hardware.org/?probe=9fdc142c76) | Sep 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [d940deb0df](https://linux-hardware.org/?probe=d940deb0df) | Sep 19, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2b913a2e83](https://linux-hardware.org/?probe=2b913a2e83) | Sep 19, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [5cab8957eb](https://linux-hardware.org/?probe=5cab8957eb) | Sep 18, 2023 |
| HP            | Dragonfly Pro               | Notebook    | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [a93d60a237](https://linux-hardware.org/?probe=a93d60a237) | Sep 17, 2023 |
| ASUSTek       | PRIME H770-PLUS             | Desktop     | [c58fea9225](https://linux-hardware.org/?probe=c58fea9225) | Sep 16, 2023 |
| Dell          | Latitude E5470              | Notebook    | [0602c2deb2](https://linux-hardware.org/?probe=0602c2deb2) | Sep 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aea37f693f](https://linux-hardware.org/?probe=aea37f693f) | Sep 15, 2023 |
| ASRock        | B450M/ac R2.0               | Desktop     | [804b890928](https://linux-hardware.org/?probe=804b890928) | Sep 15, 2023 |
| MSI           | MEG Z790 GODLIKE            | Desktop     | [ef63882e50](https://linux-hardware.org/?probe=ef63882e50) | Sep 15, 2023 |
| MSI           | MEG Z790 GODLIKE            | Desktop     | [688462f949](https://linux-hardware.org/?probe=688462f949) | Sep 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [c954042e8b](https://linux-hardware.org/?probe=c954042e8b) | Sep 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [452d16c55c](https://linux-hardware.org/?probe=452d16c55c) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2260bcd7af](https://linux-hardware.org/?probe=2260bcd7af) | Sep 12, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2284d8a2dd](https://linux-hardware.org/?probe=2284d8a2dd) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [dca28b0d09](https://linux-hardware.org/?probe=dca28b0d09) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [6c6c4a19ec](https://linux-hardware.org/?probe=6c6c4a19ec) | Sep 12, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [e72c31a6fc](https://linux-hardware.org/?probe=e72c31a6fc) | Sep 11, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [4628c4e630](https://linux-hardware.org/?probe=4628c4e630) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d8ac2101a](https://linux-hardware.org/?probe=6d8ac2101a) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [16b6bd1d3d](https://linux-hardware.org/?probe=16b6bd1d3d) | Sep 09, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [bdd270eddd](https://linux-hardware.org/?probe=bdd270eddd) | Sep 09, 2023 |
| ASUSTek       | ROG Maximus XI EXTREME      | Desktop     | [37efc0526e](https://linux-hardware.org/?probe=37efc0526e) | Sep 09, 2023 |
| ASUSTek       | ROG Maximus XI EXTREME      | Desktop     | [035446631a](https://linux-hardware.org/?probe=035446631a) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [5b0ce3438c](https://linux-hardware.org/?probe=5b0ce3438c) | Sep 08, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [178d6df21a](https://linux-hardware.org/?probe=178d6df21a) | Sep 08, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [6870581b7c](https://linux-hardware.org/?probe=6870581b7c) | Sep 08, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [872f12f24c](https://linux-hardware.org/?probe=872f12f24c) | Sep 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d5430e9279](https://linux-hardware.org/?probe=d5430e9279) | Sep 08, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [5b22cd283b](https://linux-hardware.org/?probe=5b22cd283b) | Sep 08, 2023 |
| ASRock        | B450M/ac R2.0               | Desktop     | [82266958be](https://linux-hardware.org/?probe=82266958be) | Sep 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [003d136012](https://linux-hardware.org/?probe=003d136012) | Sep 07, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [79ddc77f63](https://linux-hardware.org/?probe=79ddc77f63) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [a5506bdc30](https://linux-hardware.org/?probe=a5506bdc30) | Sep 07, 2023 |
| Acer          | Aspire GX-785               | Desktop     | [e33b7b35bf](https://linux-hardware.org/?probe=e33b7b35bf) | Sep 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fafd1b4cf2](https://linux-hardware.org/?probe=fafd1b4cf2) | Sep 06, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f7c65dc902](https://linux-hardware.org/?probe=f7c65dc902) | Sep 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [38aad324f2](https://linux-hardware.org/?probe=38aad324f2) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [cd1be324d4](https://linux-hardware.org/?probe=cd1be324d4) | Sep 05, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [82fd19c99e](https://linux-hardware.org/?probe=82fd19c99e) | Sep 05, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [08dd85e58d](https://linux-hardware.org/?probe=08dd85e58d) | Sep 05, 2023 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [fc603fc196](https://linux-hardware.org/?probe=fc603fc196) | Sep 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [13b7789482](https://linux-hardware.org/?probe=13b7789482) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [8a4af58adc](https://linux-hardware.org/?probe=8a4af58adc) | Sep 04, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3ee4e0f848](https://linux-hardware.org/?probe=3ee4e0f848) | Sep 02, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [f23cf01c1c](https://linux-hardware.org/?probe=f23cf01c1c) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [db2e607ae6](https://linux-hardware.org/?probe=db2e607ae6) | Sep 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [d8e4c2da1e](https://linux-hardware.org/?probe=d8e4c2da1e) | Sep 01, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [b652970974](https://linux-hardware.org/?probe=b652970974) | Sep 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [4725c2be8e](https://linux-hardware.org/?probe=4725c2be8e) | Sep 01, 2023 |
| HP            | Pavilion Aero Laptop 13z... | Notebook    | [afa88a8a6a](https://linux-hardware.org/?probe=afa88a8a6a) | Sep 01, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [ce1e538f59](https://linux-hardware.org/?probe=ce1e538f59) | Sep 01, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [a6619c179c](https://linux-hardware.org/?probe=a6619c179c) | Aug 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [578f5e581e](https://linux-hardware.org/?probe=578f5e581e) | Aug 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [0bf7d37cc9](https://linux-hardware.org/?probe=0bf7d37cc9) | Aug 30, 2023 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [7cf4986142](https://linux-hardware.org/?probe=7cf4986142) | Aug 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [320e8d218f](https://linux-hardware.org/?probe=320e8d218f) | Aug 28, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [d238cd036a](https://linux-hardware.org/?probe=d238cd036a) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [01a0f80107](https://linux-hardware.org/?probe=01a0f80107) | Aug 27, 2023 |
| ASUSTek       | X550VXK                     | Notebook    | [897e4f89ec](https://linux-hardware.org/?probe=897e4f89ec) | Aug 27, 2023 |
| Samsung       | 930QCG                      | Convertible | [3fb44943e6](https://linux-hardware.org/?probe=3fb44943e6) | Aug 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [95d23ba555](https://linux-hardware.org/?probe=95d23ba555) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [657c08f61f](https://linux-hardware.org/?probe=657c08f61f) | Aug 27, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ab8f75bb84](https://linux-hardware.org/?probe=ab8f75bb84) | Aug 27, 2023 |
| Unknown       | V00                         | Mini pc     | [81085cf18b](https://linux-hardware.org/?probe=81085cf18b) | Aug 26, 2023 |
| Google        | Madoo                       | Notebook    | [6644bab363](https://linux-hardware.org/?probe=6644bab363) | Aug 26, 2023 |
| Unknown       | Unknown                     | Desktop     | [2bbc495ee5](https://linux-hardware.org/?probe=2bbc495ee5) | Aug 25, 2023 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [d02a7851a6](https://linux-hardware.org/?probe=d02a7851a6) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [3eea0be3b4](https://linux-hardware.org/?probe=3eea0be3b4) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [53ba2f91cd](https://linux-hardware.org/?probe=53ba2f91cd) | Aug 24, 2023 |
| HP            | 1589                        | Desktop     | [982f4f1442](https://linux-hardware.org/?probe=982f4f1442) | Aug 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [637ccef7bd](https://linux-hardware.org/?probe=637ccef7bd) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [34a96cbdc8](https://linux-hardware.org/?probe=34a96cbdc8) | Aug 24, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [816f3ce721](https://linux-hardware.org/?probe=816f3ce721) | Aug 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [ef3454780b](https://linux-hardware.org/?probe=ef3454780b) | Aug 23, 2023 |
| HP            | 250 G4                      | Notebook    | [1eb6dc4c12](https://linux-hardware.org/?probe=1eb6dc4c12) | Aug 23, 2023 |
| HP            | 18E4                        | Desktop     | [0235c76e04](https://linux-hardware.org/?probe=0235c76e04) | Aug 23, 2023 |
| Lenovo        | ThinkPad E495 20NES0KM00    | Notebook    | [783db5b84d](https://linux-hardware.org/?probe=783db5b84d) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [c6a3274c8f](https://linux-hardware.org/?probe=c6a3274c8f) | Aug 21, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [165cab2421](https://linux-hardware.org/?probe=165cab2421) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [6112b46746](https://linux-hardware.org/?probe=6112b46746) | Aug 21, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6cee16ebd6](https://linux-hardware.org/?probe=6cee16ebd6) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [b883100fd3](https://linux-hardware.org/?probe=b883100fd3) | Aug 21, 2023 |
| MSI           | Katana 15 B13VGK            | Notebook    | [c21afd5e9f](https://linux-hardware.org/?probe=c21afd5e9f) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b6aa75cb80](https://linux-hardware.org/?probe=b6aa75cb80) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [71853f1c36](https://linux-hardware.org/?probe=71853f1c36) | Aug 20, 2023 |
| Packard Be... | EasyNote TJ66               | Notebook    | [7e5e1655a6](https://linux-hardware.org/?probe=7e5e1655a6) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [d6df464cc7](https://linux-hardware.org/?probe=d6df464cc7) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [471f5f6132](https://linux-hardware.org/?probe=471f5f6132) | Aug 20, 2023 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [60385dd9f0](https://linux-hardware.org/?probe=60385dd9f0) | Aug 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e797880ede](https://linux-hardware.org/?probe=e797880ede) | Aug 19, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8bb2d02e4d](https://linux-hardware.org/?probe=8bb2d02e4d) | Aug 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [867105e269](https://linux-hardware.org/?probe=867105e269) | Aug 18, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [f99d3dca93](https://linux-hardware.org/?probe=f99d3dca93) | Aug 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [5ed6b3612a](https://linux-hardware.org/?probe=5ed6b3612a) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [6e6a7171bf](https://linux-hardware.org/?probe=6e6a7171bf) | Aug 16, 2023 |
| HP            | 18E4                        | Desktop     | [4fd89c22ae](https://linux-hardware.org/?probe=4fd89c22ae) | Aug 14, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [1632c89b98](https://linux-hardware.org/?probe=1632c89b98) | Aug 13, 2023 |
| HP            | 8055                        | Desktop     | [a4c4208546](https://linux-hardware.org/?probe=a4c4208546) | Aug 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [246c60a344](https://linux-hardware.org/?probe=246c60a344) | Aug 13, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [6cbef2a38d](https://linux-hardware.org/?probe=6cbef2a38d) | Aug 13, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d760e3f4c4](https://linux-hardware.org/?probe=d760e3f4c4) | Aug 13, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [083e25221d](https://linux-hardware.org/?probe=083e25221d) | Aug 10, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f6040edeb0](https://linux-hardware.org/?probe=f6040edeb0) | Aug 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3b02fcaeb7](https://linux-hardware.org/?probe=3b02fcaeb7) | Aug 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [bdc11616d7](https://linux-hardware.org/?probe=bdc11616d7) | Aug 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601VI_GV6... | Convertible | [99ffb28c11](https://linux-hardware.org/?probe=99ffb28c11) | Aug 08, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [bc55c09547](https://linux-hardware.org/?probe=bc55c09547) | Aug 06, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [0e79a19ed6](https://linux-hardware.org/?probe=0e79a19ed6) | Aug 06, 2023 |
| Dell          | Latitude E5570              | Notebook    | [cbcea81a37](https://linux-hardware.org/?probe=cbcea81a37) | Aug 06, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [34e27f60e0](https://linux-hardware.org/?probe=34e27f60e0) | Aug 05, 2023 |
| Toshiba       | PORTEGE R700                | Notebook    | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [5f63621af2](https://linux-hardware.org/?probe=5f63621af2) | Aug 04, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4c677637c2](https://linux-hardware.org/?probe=4c677637c2) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [7372322587](https://linux-hardware.org/?probe=7372322587) | Aug 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a08886d394](https://linux-hardware.org/?probe=a08886d394) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| Sony          | VPCSB1V9R                   | Notebook    | [8d809c3877](https://linux-hardware.org/?probe=8d809c3877) | Aug 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [fd9503645f](https://linux-hardware.org/?probe=fd9503645f) | Aug 01, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [9e892c6bc7](https://linux-hardware.org/?probe=9e892c6bc7) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [13a4427208](https://linux-hardware.org/?probe=13a4427208) | Jul 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [5d12cf34ca](https://linux-hardware.org/?probe=5d12cf34ca) | Jul 31, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [ae14da63f3](https://linux-hardware.org/?probe=ae14da63f3) | Jul 30, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4f94bdf300](https://linux-hardware.org/?probe=4f94bdf300) | Jul 30, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f1db906c7c](https://linux-hardware.org/?probe=f1db906c7c) | Jul 30, 2023 |
| Samsung       | 960QFG                      | Convertible | [c14544a7ff](https://linux-hardware.org/?probe=c14544a7ff) | Jul 30, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [963eb3c0a8](https://linux-hardware.org/?probe=963eb3c0a8) | Jul 29, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [cb13e61bae](https://linux-hardware.org/?probe=cb13e61bae) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Google        | Fleex                       | Notebook    | [977fa266d3](https://linux-hardware.org/?probe=977fa266d3) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [2cd6047230](https://linux-hardware.org/?probe=2cd6047230) | Jul 25, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [0b4b6b015b](https://linux-hardware.org/?probe=0b4b6b015b) | Jul 24, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [351ebe5f4f](https://linux-hardware.org/?probe=351ebe5f4f) | Jul 24, 2023 |
| HP            | 250 G3                      | Notebook    | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a179c222ea](https://linux-hardware.org/?probe=a179c222ea) | Jul 23, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [7f3a5aa8cd](https://linux-hardware.org/?probe=7f3a5aa8cd) | Jul 22, 2023 |
| HP            | 86F3 00100                  | All in one  | [26504c2968](https://linux-hardware.org/?probe=26504c2968) | Jul 22, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [7387b87abf](https://linux-hardware.org/?probe=7387b87abf) | Jul 21, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [2a3971e2fc](https://linux-hardware.org/?probe=2a3971e2fc) | Jul 21, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [788fc0bfc9](https://linux-hardware.org/?probe=788fc0bfc9) | Jul 21, 2023 |
| ASUSTek       | G551JK                      | Notebook    | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [9a705d5047](https://linux-hardware.org/?probe=9a705d5047) | Jul 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [cc73a658d1](https://linux-hardware.org/?probe=cc73a658d1) | Jul 19, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [7733ed8a40](https://linux-hardware.org/?probe=7733ed8a40) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [4bba49b11c](https://linux-hardware.org/?probe=4bba49b11c) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [91f1d1f94f](https://linux-hardware.org/?probe=91f1d1f94f) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [32fbe34ce0](https://linux-hardware.org/?probe=32fbe34ce0) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [25aef4eda4](https://linux-hardware.org/?probe=25aef4eda4) | Jul 18, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [ef2395800e](https://linux-hardware.org/?probe=ef2395800e) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d589d40102](https://linux-hardware.org/?probe=d589d40102) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7e0ff09c1f](https://linux-hardware.org/?probe=7e0ff09c1f) | Jul 15, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [44a9f08c5e](https://linux-hardware.org/?probe=44a9f08c5e) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | Notebook    | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [2d03b5f0b6](https://linux-hardware.org/?probe=2d03b5f0b6) | Jul 14, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [13961b824f](https://linux-hardware.org/?probe=13961b824f) | Jul 14, 2023 |
| MSI           | B150M ECO                   | Desktop     | [84601cd9dc](https://linux-hardware.org/?probe=84601cd9dc) | Jul 14, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | Notebook    | [2213337296](https://linux-hardware.org/?probe=2213337296) | Jul 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [093938a09b](https://linux-hardware.org/?probe=093938a09b) | Jul 13, 2023 |
| OriginPC      | EVO16-S                     | Notebook    | [f3b1c85a1a](https://linux-hardware.org/?probe=f3b1c85a1a) | Jul 11, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [fddf95e5c8](https://linux-hardware.org/?probe=fddf95e5c8) | Jul 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4347661295](https://linux-hardware.org/?probe=4347661295) | Jul 11, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [a497806f86](https://linux-hardware.org/?probe=a497806f86) | Jul 10, 2023 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [93fcbdf5d5](https://linux-hardware.org/?probe=93fcbdf5d5) | Jul 10, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [160af9ddfb](https://linux-hardware.org/?probe=160af9ddfb) | Jul 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS08C0K    | Notebook    | [9857dab3ab](https://linux-hardware.org/?probe=9857dab3ab) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [09ada263c3](https://linux-hardware.org/?probe=09ada263c3) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [33e4bac631](https://linux-hardware.org/?probe=33e4bac631) | Jul 05, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [60c1acd1fc](https://linux-hardware.org/?probe=60c1acd1fc) | Jul 04, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16IAH7 8... | Notebook    | [ad57a8dd50](https://linux-hardware.org/?probe=ad57a8dd50) | Jul 04, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0064c1c269](https://linux-hardware.org/?probe=0064c1c269) | Jul 03, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f9e366002e](https://linux-hardware.org/?probe=f9e366002e) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [c1a241c0a5](https://linux-hardware.org/?probe=c1a241c0a5) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [6df7cc5145](https://linux-hardware.org/?probe=6df7cc5145) | Jul 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [0a50455c18](https://linux-hardware.org/?probe=0a50455c18) | Jul 02, 2023 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [efb7d0f42a](https://linux-hardware.org/?probe=efb7d0f42a) | Jul 02, 2023 |
| Dell          | XPS L521X                   | Notebook    | [b80baf340c](https://linux-hardware.org/?probe=b80baf340c) | Jul 02, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [83dd07d2a7](https://linux-hardware.org/?probe=83dd07d2a7) | Jul 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [1ab74730be](https://linux-hardware.org/?probe=1ab74730be) | Jul 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b5f1dc88df](https://linux-hardware.org/?probe=b5f1dc88df) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [916b60f6f7](https://linux-hardware.org/?probe=916b60f6f7) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f3cb4dc749](https://linux-hardware.org/?probe=f3cb4dc749) | Jun 29, 2023 |
| eMachines     | eME728                      | Notebook    | [37dc0ef617](https://linux-hardware.org/?probe=37dc0ef617) | Jun 29, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [89f1647ea1](https://linux-hardware.org/?probe=89f1647ea1) | Jun 29, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [1a84c61bd4](https://linux-hardware.org/?probe=1a84c61bd4) | Jun 27, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [c147d5716d](https://linux-hardware.org/?probe=c147d5716d) | Jun 27, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d0d602b518](https://linux-hardware.org/?probe=d0d602b518) | Jun 27, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [f664b455eb](https://linux-hardware.org/?probe=f664b455eb) | Jun 26, 2023 |
| Google        | Sasuke                      | Notebook    | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e0f5116d38](https://linux-hardware.org/?probe=e0f5116d38) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7ac67acfed](https://linux-hardware.org/?probe=7ac67acfed) | Jun 21, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [481ef14837](https://linux-hardware.org/?probe=481ef14837) | Jun 21, 2023 |
| MSI           | B450M PRO-VDH               | Desktop     | [ed8ee7af2c](https://linux-hardware.org/?probe=ed8ee7af2c) | Jun 19, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [78207fbf49](https://linux-hardware.org/?probe=78207fbf49) | Jun 19, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [90720c3820](https://linux-hardware.org/?probe=90720c3820) | Jun 18, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4b184d1037](https://linux-hardware.org/?probe=4b184d1037) | Jun 18, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [2bcd63ec1e](https://linux-hardware.org/?probe=2bcd63ec1e) | Jun 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| ZOTAC         | ZBOX-EN760                  | Mini pc     | [e36c953da7](https://linux-hardware.org/?probe=e36c953da7) | Jun 14, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| Dell          | Latitude E5570              | Notebook    | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e8ed28dba0](https://linux-hardware.org/?probe=e8ed28dba0) | Jun 14, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [507d8cc765](https://linux-hardware.org/?probe=507d8cc765) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21a8144a2e](https://linux-hardware.org/?probe=21a8144a2e) | Jun 13, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [51a3b444dd](https://linux-hardware.org/?probe=51a3b444dd) | Jun 13, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c433d533f0](https://linux-hardware.org/?probe=c433d533f0) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| ASUSTek       | CM6850                      | Desktop     | [33579719ed](https://linux-hardware.org/?probe=33579719ed) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| Dell          | Latitude E6510              | Notebook    | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| Dell          | 0DWPVW A00                  | Desktop     | [ffad802816](https://linux-hardware.org/?probe=ffad802816) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| VIT           | P2402                       | Notebook    | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [52df878410](https://linux-hardware.org/?probe=52df878410) | Jun 08, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [0f41ab04b6](https://linux-hardware.org/?probe=0f41ab04b6) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [33fb312b6d](https://linux-hardware.org/?probe=33fb312b6d) | Jun 05, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [92fe930ecf](https://linux-hardware.org/?probe=92fe930ecf) | Jun 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [04830d213f](https://linux-hardware.org/?probe=04830d213f) | Jun 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [4ccfddd671](https://linux-hardware.org/?probe=4ccfddd671) | Jun 02, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [becb85a201](https://linux-hardware.org/?probe=becb85a201) | Jun 02, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [c4cd05b00f](https://linux-hardware.org/?probe=c4cd05b00f) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [7d35807036](https://linux-hardware.org/?probe=7d35807036) | Jun 01, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [8bc281486e](https://linux-hardware.org/?probe=8bc281486e) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | Notebook    | [0b04d3bf20](https://linux-hardware.org/?probe=0b04d3bf20) | May 28, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [af33101302](https://linux-hardware.org/?probe=af33101302) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| HP            | 86EE                        | All in one  | [ba49672c5b](https://linux-hardware.org/?probe=ba49672c5b) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [4c22ef876f](https://linux-hardware.org/?probe=4c22ef876f) | May 26, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [46cb91a74d](https://linux-hardware.org/?probe=46cb91a74d) | May 25, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48bd340a09](https://linux-hardware.org/?probe=48bd340a09) | May 24, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a605d12e2d](https://linux-hardware.org/?probe=a605d12e2d) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a1770c45b0](https://linux-hardware.org/?probe=a1770c45b0) | May 23, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [0cba90ce8e](https://linux-hardware.org/?probe=0cba90ce8e) | May 23, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [a48977a871](https://linux-hardware.org/?probe=a48977a871) | May 22, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| HP            | 18E4                        | Desktop     | [5601900c8b](https://linux-hardware.org/?probe=5601900c8b) | May 22, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [da9ebc680a](https://linux-hardware.org/?probe=da9ebc680a) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [7560196205](https://linux-hardware.org/?probe=7560196205) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [4dc91feab7](https://linux-hardware.org/?probe=4dc91feab7) | May 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [59a9ba6e16](https://linux-hardware.org/?probe=59a9ba6e16) | May 13, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [4fd655c0aa](https://linux-hardware.org/?probe=4fd655c0aa) | May 13, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [e4bfe14f2d](https://linux-hardware.org/?probe=e4bfe14f2d) | May 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [bc0dacd119](https://linux-hardware.org/?probe=bc0dacd119) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [35d056f8bd](https://linux-hardware.org/?probe=35d056f8bd) | May 11, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | 18E4                        | Desktop     | [2a528dc758](https://linux-hardware.org/?probe=2a528dc758) | May 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [3346a6a326](https://linux-hardware.org/?probe=3346a6a326) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [2a7a243899](https://linux-hardware.org/?probe=2a7a243899) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [c7a298018f](https://linux-hardware.org/?probe=c7a298018f) | May 08, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [a916fc6080](https://linux-hardware.org/?probe=a916fc6080) | May 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7a1ffd8bd2](https://linux-hardware.org/?probe=7a1ffd8bd2) | May 07, 2023 |
| Timi          | TM1701                      | Notebook    | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [7ab24c2d1a](https://linux-hardware.org/?probe=7ab24c2d1a) | May 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [df58b07032](https://linux-hardware.org/?probe=df58b07032) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [91c6b0d769](https://linux-hardware.org/?probe=91c6b0d769) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| HP            | 1589                        | Desktop     | [dd3e55b423](https://linux-hardware.org/?probe=dd3e55b423) | May 05, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8ff62a5045](https://linux-hardware.org/?probe=8ff62a5045) | May 05, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Lenovo        | ThinkPad W530 24473F2       | Notebook    | [937dddbff0](https://linux-hardware.org/?probe=937dddbff0) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e49682836a](https://linux-hardware.org/?probe=e49682836a) | May 04, 2023 |
| HP            | 18E4                        | Desktop     | [d1344e36dd](https://linux-hardware.org/?probe=d1344e36dd) | May 03, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [9984dd7707](https://linux-hardware.org/?probe=9984dd7707) | May 03, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [16ac84221b](https://linux-hardware.org/?probe=16ac84221b) | May 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [96402fa64a](https://linux-hardware.org/?probe=96402fa64a) | May 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [07324ae678](https://linux-hardware.org/?probe=07324ae678) | May 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [24363c23cf](https://linux-hardware.org/?probe=24363c23cf) | May 01, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Dell          | Latitude 5580               | Notebook    | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| HP            | 18E4                        | Desktop     | [da858ea464](https://linux-hardware.org/?probe=da858ea464) | Apr 30, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [8c4352985e](https://linux-hardware.org/?probe=8c4352985e) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| HP            | 8715                        | Mini pc     | [8d210cce39](https://linux-hardware.org/?probe=8d210cce39) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f1d5d361d5](https://linux-hardware.org/?probe=f1d5d361d5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | Notebook    | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [17ae2e245a](https://linux-hardware.org/?probe=17ae2e245a) | Apr 22, 2023 |
| Notebook      | W65_W67RB                   | Notebook    | [f34e442b8b](https://linux-hardware.org/?probe=f34e442b8b) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | Notebook    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [00f7379c8f](https://linux-hardware.org/?probe=00f7379c8f) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [c27abc2880](https://linux-hardware.org/?probe=c27abc2880) | Apr 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | Notebook    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f6a652b68d](https://linux-hardware.org/?probe=f6a652b68d) | Apr 14, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [8eaac4a62d](https://linux-hardware.org/?probe=8eaac4a62d) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [47f2ba894b](https://linux-hardware.org/?probe=47f2ba894b) | Apr 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [07353da9f6](https://linux-hardware.org/?probe=07353da9f6) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [0e074bebcf](https://linux-hardware.org/?probe=0e074bebcf) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59db7a4f11](https://linux-hardware.org/?probe=59db7a4f11) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01cae1e152](https://linux-hardware.org/?probe=01cae1e152) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| HP            | 18E4                        | Desktop     | [54c681affc](https://linux-hardware.org/?probe=54c681affc) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [15d7d40bed](https://linux-hardware.org/?probe=15d7d40bed) | Apr 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | Notebook    | [aee22ee8b3](https://linux-hardware.org/?probe=aee22ee8b3) | Apr 08, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d1167f66b8](https://linux-hardware.org/?probe=d1167f66b8) | Apr 08, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [a6c5efe560](https://linux-hardware.org/?probe=a6c5efe560) | Apr 07, 2023 |
| HP            | 250 G4                      | Notebook    | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| HP            | Unknown                     | Notebook    | [0af30fd642](https://linux-hardware.org/?probe=0af30fd642) | Apr 06, 2023 |
| Gigabyte      | H87M-D3H                    | Desktop     | [b9c169025d](https://linux-hardware.org/?probe=b9c169025d) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5012c822d7](https://linux-hardware.org/?probe=5012c822d7) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [33eb81c75e](https://linux-hardware.org/?probe=33eb81c75e) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | Notebook    | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [546e8e3742](https://linux-hardware.org/?probe=546e8e3742) | Apr 04, 2023 |
| Samsung       | 950QDB                      | Convertible | [967646c481](https://linux-hardware.org/?probe=967646c481) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [d3a27ee996](https://linux-hardware.org/?probe=d3a27ee996) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [d64af320d7](https://linux-hardware.org/?probe=d64af320d7) | Apr 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [3400bd9412](https://linux-hardware.org/?probe=3400bd9412) | Apr 02, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | Notebook    | [edb6e927bd](https://linux-hardware.org/?probe=edb6e927bd) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | Notebook    | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| HP            | 8715                        | Mini pc     | [bcd377dcb7](https://linux-hardware.org/?probe=bcd377dcb7) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| GPD           | G1621-02                    | Notebook    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| HP            | 8715                        | Mini pc     | [222fde0a83](https://linux-hardware.org/?probe=222fde0a83) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [008eb6ad60](https://linux-hardware.org/?probe=008eb6ad60) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4dd142ab8f](https://linux-hardware.org/?probe=4dd142ab8f) | Mar 31, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| AWOW          | AL34                        | Notebook    | [19f60f27c8](https://linux-hardware.org/?probe=19f60f27c8) | Mar 29, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [65671e15cb](https://linux-hardware.org/?probe=65671e15cb) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [b165f54c80](https://linux-hardware.org/?probe=b165f54c80) | Mar 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [d80388d7ef](https://linux-hardware.org/?probe=d80388d7ef) | Mar 27, 2023 |
| HP            | 18E4                        | Desktop     | [5d10e73e1d](https://linux-hardware.org/?probe=5d10e73e1d) | Mar 26, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a8d31fc431](https://linux-hardware.org/?probe=a8d31fc431) | Mar 26, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [4253088a92](https://linux-hardware.org/?probe=4253088a92) | Mar 25, 2023 |
| Samsung       | 550XDA                      | Notebook    | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [18cd806803](https://linux-hardware.org/?probe=18cd806803) | Mar 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | Notebook    | [3042a430c0](https://linux-hardware.org/?probe=3042a430c0) | Mar 24, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e923cf7edb](https://linux-hardware.org/?probe=e923cf7edb) | Mar 24, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [5bd922e142](https://linux-hardware.org/?probe=5bd922e142) | Mar 23, 2023 |
| AZW           | GK35                        | Desktop     | [bd935978b7](https://linux-hardware.org/?probe=bd935978b7) | Mar 22, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| GPD           | G1619-04                    | Notebook    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [f6042580d0](https://linux-hardware.org/?probe=f6042580d0) | Mar 20, 2023 |
| Notebook      | N150ZU                      | Notebook    | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| ASUSTek       | UX301LAA                    | Notebook    | [882d4d095b](https://linux-hardware.org/?probe=882d4d095b) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [1c2c765978](https://linux-hardware.org/?probe=1c2c765978) | Mar 18, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [a3e8bcd9dd](https://linux-hardware.org/?probe=a3e8bcd9dd) | Mar 18, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [ae4d8ba68c](https://linux-hardware.org/?probe=ae4d8ba68c) | Mar 18, 2023 |
| AZW           | U59                         | Desktop     | [ce6bd37711](https://linux-hardware.org/?probe=ce6bd37711) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [cd9310c350](https://linux-hardware.org/?probe=cd9310c350) | Mar 17, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [b43ea7bb6e](https://linux-hardware.org/?probe=b43ea7bb6e) | Mar 17, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [c6ef926aa6](https://linux-hardware.org/?probe=c6ef926aa6) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [066f0cd17b](https://linux-hardware.org/?probe=066f0cd17b) | Mar 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | Notebook    | [b588252431](https://linux-hardware.org/?probe=b588252431) | Mar 14, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [0f3b7bd317](https://linux-hardware.org/?probe=0f3b7bd317) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Notebook    | [7f58d0d0a0](https://linux-hardware.org/?probe=7f58d0d0a0) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Notebook    | [0c58b8ebad](https://linux-hardware.org/?probe=0c58b8ebad) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Unknown       | HX90                        | Desktop     | [51aca581e4](https://linux-hardware.org/?probe=51aca581e4) | Mar 11, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [bf6081f2af](https://linux-hardware.org/?probe=bf6081f2af) | Mar 09, 2023 |
| Dell          | Precision 7720              | Notebook    | [6132f690aa](https://linux-hardware.org/?probe=6132f690aa) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [8a33917a89](https://linux-hardware.org/?probe=8a33917a89) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [f4d71dcbd0](https://linux-hardware.org/?probe=f4d71dcbd0) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0fdb67b9d2](https://linux-hardware.org/?probe=0fdb67b9d2) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e48f233a0](https://linux-hardware.org/?probe=2e48f233a0) | Mar 09, 2023 |
| Dell          | Precision 7720              | Notebook    | [e4a1149bcb](https://linux-hardware.org/?probe=e4a1149bcb) | Mar 08, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [af171db9dc](https://linux-hardware.org/?probe=af171db9dc) | Mar 08, 2023 |
| Timi          | TM1701                      | Notebook    | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [f363dca8ca](https://linux-hardware.org/?probe=f363dca8ca) | Mar 07, 2023 |
| HP            | 8860 A                      | Desktop     | [78c9aa9174](https://linux-hardware.org/?probe=78c9aa9174) | Mar 07, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| Dell          | Latitude 5289               | Notebook    | [dcac5b8ebc](https://linux-hardware.org/?probe=dcac5b8ebc) | Mar 06, 2023 |
| Google        | Rammus                      | Notebook    | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HP            | 18E4                        | Desktop     | [a277b636c1](https://linux-hardware.org/?probe=a277b636c1) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | 18E4                        | Desktop     | [8e76736e7e](https://linux-hardware.org/?probe=8e76736e7e) | Mar 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [80dca547fc](https://linux-hardware.org/?probe=80dca547fc) | Mar 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [89fb184b09](https://linux-hardware.org/?probe=89fb184b09) | Mar 01, 2023 |
| HP            | 18E4                        | Desktop     | [cab6d807e9](https://linux-hardware.org/?probe=cab6d807e9) | Feb 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1412fd5885](https://linux-hardware.org/?probe=1412fd5885) | Feb 26, 2023 |
| HP            | 18E4                        | Desktop     | [5c7c3413c9](https://linux-hardware.org/?probe=5c7c3413c9) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [ccff1403b0](https://linux-hardware.org/?probe=ccff1403b0) | Feb 24, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [32f4f192fa](https://linux-hardware.org/?probe=32f4f192fa) | Feb 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [576a0fc8f5](https://linux-hardware.org/?probe=576a0fc8f5) | Feb 23, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [2915d1c409](https://linux-hardware.org/?probe=2915d1c409) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d5f5531b82](https://linux-hardware.org/?probe=d5f5531b82) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| Google        | Helios                      | Notebook    | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [b0693958a6](https://linux-hardware.org/?probe=b0693958a6) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [c84212b39c](https://linux-hardware.org/?probe=c84212b39c) | Feb 15, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [6c540405e8](https://linux-hardware.org/?probe=6c540405e8) | Feb 15, 2023 |
| GPD           | G1621-02                    | Notebook    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4b0331863e](https://linux-hardware.org/?probe=4b0331863e) | Feb 14, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [d8ed5d5e88](https://linux-hardware.org/?probe=d8ed5d5e88) | Feb 14, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [820aa2bf49](https://linux-hardware.org/?probe=820aa2bf49) | Feb 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM    | Notebook    | [9e0e0bef82](https://linux-hardware.org/?probe=9e0e0bef82) | Feb 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [debdb17904](https://linux-hardware.org/?probe=debdb17904) | Feb 12, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8133fc11b8](https://linux-hardware.org/?probe=8133fc11b8) | Feb 12, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [05d11c4fe3](https://linux-hardware.org/?probe=05d11c4fe3) | Feb 12, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| HP            | Compaq 6820s                | Notebook    | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [0c6da36f9d](https://linux-hardware.org/?probe=0c6da36f9d) | Feb 11, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [059d515c3c](https://linux-hardware.org/?probe=059d515c3c) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Dell          | 0Y5FXV A00                  | Desktop     | [692b7eab6b](https://linux-hardware.org/?probe=692b7eab6b) | Feb 08, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2LN0... | Notebook    | [4fdb5d662c](https://linux-hardware.org/?probe=4fdb5d662c) | Feb 08, 2023 |
| HP            | ENVY Notebook PC            | Convertible | [a8165997b7](https://linux-hardware.org/?probe=a8165997b7) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [43c3e4d160](https://linux-hardware.org/?probe=43c3e4d160) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| HP            | Setzer                      | Notebook    | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [96847498e3](https://linux-hardware.org/?probe=96847498e3) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [de7f0840d1](https://linux-hardware.org/?probe=de7f0840d1) | Feb 01, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [455825998f](https://linux-hardware.org/?probe=455825998f) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4251ab2f9a](https://linux-hardware.org/?probe=4251ab2f9a) | Feb 01, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [bcaa2e6b1a](https://linux-hardware.org/?probe=bcaa2e6b1a) | Jan 30, 2023 |
| Dell          | Latitude 5400               | Notebook    | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [b15899ef80](https://linux-hardware.org/?probe=b15899ef80) | Jan 27, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [357a0cd22d](https://linux-hardware.org/?probe=357a0cd22d) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Dell          | Latitude E5410              | Notebook    | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| Google        | Magpie                      | Notebook    | [34506f260e](https://linux-hardware.org/?probe=34506f260e) | Jan 26, 2023 |
| HP            | 86EE                        | All in one  | [2632541785](https://linux-hardware.org/?probe=2632541785) | Jan 25, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [55b2bf8aea](https://linux-hardware.org/?probe=55b2bf8aea) | Jan 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [56a9b7ad32](https://linux-hardware.org/?probe=56a9b7ad32) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [f371c1c8b6](https://linux-hardware.org/?probe=f371c1c8b6) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Notebook    | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [1153793fd9](https://linux-hardware.org/?probe=1153793fd9) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f1d22db1d7](https://linux-hardware.org/?probe=f1d22db1d7) | Jan 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [2c44f8275e](https://linux-hardware.org/?probe=2c44f8275e) | Jan 17, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e40c15660](https://linux-hardware.org/?probe=2e40c15660) | Jan 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [8b1ccef51d](https://linux-hardware.org/?probe=8b1ccef51d) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [154dafff1e](https://linux-hardware.org/?probe=154dafff1e) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [ce588e0413](https://linux-hardware.org/?probe=ce588e0413) | Jan 14, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [1681bdc38e](https://linux-hardware.org/?probe=1681bdc38e) | Jan 14, 2023 |
| Dell          | Precision M4800             | Notebook    | [c5deb205c7](https://linux-hardware.org/?probe=c5deb205c7) | Jan 14, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [4fc1f3aff0](https://linux-hardware.org/?probe=4fc1f3aff0) | Jan 11, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [878c92decc](https://linux-hardware.org/?probe=878c92decc) | Jan 11, 2023 |
| HP            | 18E4                        | Desktop     | [600d82b264](https://linux-hardware.org/?probe=600d82b264) | Jan 11, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| HP            | 18E4                        | Desktop     | [3386d53667](https://linux-hardware.org/?probe=3386d53667) | Jan 10, 2023 |
| HP            | 2179                        | Desktop     | [ad75cc2104](https://linux-hardware.org/?probe=ad75cc2104) | Jan 10, 2023 |
| Dell          | 0NRKPK A01                  | Desktop     | [f5bdf45b4a](https://linux-hardware.org/?probe=f5bdf45b4a) | Jan 08, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Dell          | XPS 9320                    | Notebook    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c84118baf](https://linux-hardware.org/?probe=0c84118baf) | Jan 03, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [be6730b67b](https://linux-hardware.org/?probe=be6730b67b) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [2d0530b779](https://linux-hardware.org/?probe=2d0530b779) | Jan 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [bc57a904f7](https://linux-hardware.org/?probe=bc57a904f7) | Jan 03, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [b613cd1179](https://linux-hardware.org/?probe=b613cd1179) | Jan 02, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| Toshiba       | EQUIUM A100                 | Notebook    | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| HP            | 18E4                        | Desktop     | [c83c8341e3](https://linux-hardware.org/?probe=c83c8341e3) | Jan 01, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [20eb2d93e2](https://linux-hardware.org/?probe=20eb2d93e2) | Jan 01, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| HP            | 18E4                        | Desktop     | [1b1eccbbe1](https://linux-hardware.org/?probe=1b1eccbbe1) | Dec 31, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [9aba0ac647](https://linux-hardware.org/?probe=9aba0ac647) | Dec 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [30e1303337](https://linux-hardware.org/?probe=30e1303337) | Dec 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4d915292f4](https://linux-hardware.org/?probe=4d915292f4) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [b38e3cc51e](https://linux-hardware.org/?probe=b38e3cc51e) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [adb13e2649](https://linux-hardware.org/?probe=adb13e2649) | Dec 29, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [e422b934d0](https://linux-hardware.org/?probe=e422b934d0) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b8099c7a94](https://linux-hardware.org/?probe=b8099c7a94) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [475b76e98a](https://linux-hardware.org/?probe=475b76e98a) | Dec 28, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [cd90f1782c](https://linux-hardware.org/?probe=cd90f1782c) | Dec 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [78418bfaa6](https://linux-hardware.org/?probe=78418bfaa6) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | Notebook    | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [416b0bb4e1](https://linux-hardware.org/?probe=416b0bb4e1) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [244ad65a78](https://linux-hardware.org/?probe=244ad65a78) | Dec 24, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [348c431775](https://linux-hardware.org/?probe=348c431775) | Dec 23, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [262a879a99](https://linux-hardware.org/?probe=262a879a99) | Dec 19, 2022 |
| Sony          | VGN-FW11E                   | Notebook    | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HP            | 15                          | Notebook    | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [54e81a596c](https://linux-hardware.org/?probe=54e81a596c) | Dec 18, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0a486ca67b](https://linux-hardware.org/?probe=0a486ca67b) | Dec 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [c5adff1ad5](https://linux-hardware.org/?probe=c5adff1ad5) | Dec 17, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [8c87fc340b](https://linux-hardware.org/?probe=8c87fc340b) | Dec 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e69127d249](https://linux-hardware.org/?probe=e69127d249) | Dec 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8968e6816e](https://linux-hardware.org/?probe=8968e6816e) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [26757adc9d](https://linux-hardware.org/?probe=26757adc9d) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [ba6bef79d5](https://linux-hardware.org/?probe=ba6bef79d5) | Dec 15, 2022 |
| Lenovo        | Yoga 510-15IKB 80VC         | Convertible | [cb1e09289e](https://linux-hardware.org/?probe=cb1e09289e) | Dec 15, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [de70f43070](https://linux-hardware.org/?probe=de70f43070) | Dec 14, 2022 |
| HP            | 18E4                        | Desktop     | [00f1e4a14a](https://linux-hardware.org/?probe=00f1e4a14a) | Dec 14, 2022 |
| PC Special... | Elimina Iv 17               | Notebook    | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [502792fe8a](https://linux-hardware.org/?probe=502792fe8a) | Dec 12, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [2a1d9a153b](https://linux-hardware.org/?probe=2a1d9a153b) | Dec 11, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48ccfd51b4](https://linux-hardware.org/?probe=48ccfd51b4) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [5f3e259429](https://linux-hardware.org/?probe=5f3e259429) | Dec 10, 2022 |
| HP            | 18E4                        | Desktop     | [418a689ae5](https://linux-hardware.org/?probe=418a689ae5) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [963477cf57](https://linux-hardware.org/?probe=963477cf57) | Dec 07, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [46a6e9e722](https://linux-hardware.org/?probe=46a6e9e722) | Dec 07, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [e897549786](https://linux-hardware.org/?probe=e897549786) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [b12969b62f](https://linux-hardware.org/?probe=b12969b62f) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [dcd57e5862](https://linux-hardware.org/?probe=dcd57e5862) | Dec 04, 2022 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [8741c9175e](https://linux-hardware.org/?probe=8741c9175e) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [c3b6dada9d](https://linux-hardware.org/?probe=c3b6dada9d) | Dec 02, 2022 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 1041      | 87.11%  |
| EndeavourOS         | 154       | 12.89%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| EndeavourOS | 1184      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 6.5.9-arch2-1    | 25        | 1.79%   |
| 6.4.12-arch1-1   | 23        | 1.65%   |
| 6.2.8-arch1-1    | 20        | 1.44%   |
| 5.15.12-arch1-1  | 20        | 1.44%   |
| 6.1.1-arch1-1    | 16        | 1.15%   |
| 6.3.9-arch1-1    | 15        | 1.08%   |
| 6.5.7-arch1-1    | 13        | 0.93%   |
| 6.3.1-arch1-1    | 13        | 0.93%   |
| 6.1.12-arch1-1   | 13        | 0.93%   |
| 6.5.3-arch1-1    | 12        | 0.86%   |
| 6.3.4-arch1-1    | 12        | 0.86%   |
| 6.2.2-arch1-1    | 11        | 0.79%   |
| 6.2.13-arch1-1   | 11        | 0.79%   |
| 6.2.10-arch1-1   | 11        | 0.79%   |
| 6.0.9-arch1-1    | 11        | 0.79%   |
| 6.0.2-arch1-1    | 11        | 0.79%   |
| 5.17.1-arch1-1   | 11        | 0.79%   |
| 6.4.11-arch2-1   | 10        | 0.72%   |
| 5.19.7-arch1-1   | 10        | 0.72%   |
| 5.17.5-arch1-1   | 10        | 0.72%   |
| 6.5.8-arch1-1    | 9         | 0.65%   |
| 6.5.5-arch1-1    | 9         | 0.65%   |
| 6.0.2-zen1-1-zen | 9         | 0.65%   |
| 6.0.12-arch1-1   | 9         | 0.65%   |
| 5.15.10-arch1-1  | 9         | 0.65%   |
| 6.4.7-arch1-1    | 8         | 0.57%   |
| 6.2.9-arch1-1    | 8         | 0.57%   |
| 5.17.9-arch1-1   | 8         | 0.57%   |
| 5.15.7-arch1-1   | 8         | 0.57%   |
| 5.14.9-arch2-1   | 8         | 0.57%   |
| 5.13.13-arch1-1  | 8         | 0.57%   |
| 5.11.11-arch1-1  | 8         | 0.57%   |
| 6.5.4-arch2-1    | 7         | 0.5%    |
| 6.1.11-arch1-1   | 7         | 0.5%    |
| 5.9.14-arch1-1   | 7         | 0.5%    |
| 5.19.12-arch1-1  | 7         | 0.5%    |
| 5.18.16-arch1-1  | 7         | 0.5%    |
| 5.18.12-arch1-1  | 7         | 0.5%    |
| 5.16.10-arch1-1  | 7         | 0.5%    |
| 6.4.8-arch1-1    | 6         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.12  | 29        | 2.08%   |
| 6.5.9   | 28        | 2.01%   |
| 5.15.12 | 28        | 2.01%   |
| 6.3.1   | 23        | 1.65%   |
| 6.1.1   | 23        | 1.65%   |
| 6.2.8   | 22        | 1.58%   |
| 6.0.2   | 22        | 1.58%   |
| 6.5.3   | 16        | 1.15%   |
| 6.4.11  | 16        | 1.15%   |
| 6.3.9   | 16        | 1.15%   |
| 6.3.4   | 16        | 1.15%   |
| 6.5.8   | 15        | 1.08%   |
| 6.4.7   | 15        | 1.08%   |
| 6.4.3   | 15        | 1.08%   |
| 6.1.12  | 15        | 1.08%   |
| 6.0.9   | 15        | 1.08%   |
| 5.17.1  | 15        | 1.08%   |
| 6.5.7   | 14        | 1.01%   |
| 6.2.2   | 14        | 1.01%   |
| 6.2.13  | 14        | 1.01%   |
| 5.17.5  | 14        | 1.01%   |
| 6.2.10  | 13        | 0.93%   |
| 6.5.5   | 12        | 0.86%   |
| 6.0.6   | 12        | 0.86%   |
| 6.0.12  | 12        | 0.86%   |
| 5.19.7  | 12        | 0.86%   |
| 5.13.13 | 12        | 0.86%   |
| 6.2.9   | 11        | 0.79%   |
| 5.18.12 | 11        | 0.79%   |
| 5.17.9  | 11        | 0.79%   |
| 6.5.4   | 10        | 0.72%   |
| 6.4.1   | 10        | 0.72%   |
| 6.3.5   | 10        | 0.72%   |
| 5.19.9  | 10        | 0.72%   |
| 5.14.9  | 10        | 0.72%   |
| 6.4.10  | 9         | 0.65%   |
| 6.1.9   | 9         | 0.65%   |
| 5.19.13 | 9         | 0.65%   |
| 5.18.16 | 9         | 0.65%   |
| 5.15.7  | 9         | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 140       | 10.42%  |
| 5.15    | 139       | 10.35%  |
| 6.4     | 116       | 8.64%   |
| 6.5     | 105       | 7.82%   |
| 6.2     | 105       | 7.82%   |
| 6.3     | 86        | 6.4%    |
| 6.0     | 83        | 6.18%   |
| 5.19    | 79        | 5.88%   |
| 5.16    | 66        | 4.91%   |
| 5.17    | 64        | 4.77%   |
| 5.18    | 60        | 4.47%   |
| 5.14    | 52        | 3.87%   |
| 5.12    | 38        | 2.83%   |
| 5.10    | 38        | 2.83%   |
| 5.11    | 37        | 2.76%   |
| 5.9     | 35        | 2.61%   |
| 5.13    | 35        | 2.61%   |
| 5.8     | 24        | 1.79%   |
| 5.7     | 21        | 1.56%   |
| 5.4     | 7         | 0.52%   |
| 5.6     | 5         | 0.37%   |
| 5.5     | 2         | 0.15%   |
| 4.19    | 2         | 0.15%   |
| 6.6     | 1         | 0.07%   |
| 5.2     | 1         | 0.07%   |
| 5.17.1  | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1183      | 99.92%  |
| aarch64 | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 475       | 38.56%  |
| GNOME           | 258       | 20.94%  |
| XFCE            | 226       | 18.34%  |
| i3              | 50        | 4.06%   |
| X-Cinnamon      | 45        | 3.65%   |
| Budgie          | 29        | 2.35%   |
| KDE             | 27        | 2.19%   |
| Unknown         | 24        | 1.95%   |
| Cinnamon        | 18        | 1.46%   |
| sway            | 15        | 1.22%   |
| MATE            | 12        | 0.97%   |
| Hyprland        | 12        | 0.97%   |
| LXQt            | 9         | 0.73%   |
| Deepin          | 5         | 0.41%   |
| bspwm           | 5         | 0.41%   |
| openbox         | 4         | 0.32%   |
| GNOME Flashback | 4         | 0.32%   |
| awesome         | 4         | 0.32%   |
| LXDE            | 3         | 0.24%   |
| qtile           | 2         | 0.16%   |
| xmonad          | 1         | 0.08%   |
| LeftWM          | 1         | 0.08%   |
| jwm             | 1         | 0.08%   |
| herbstluftwm    | 1         | 0.08%   |
| GNOME Classic   | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 882       | 72.41%  |
| Wayland | 271       | 22.25%  |
| Tty     | 45        | 3.69%   |
| Unknown | 19        | 1.56%   |
| Web     | 1         | 0.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 393       | 32.11%  |
| SDDM    | 314       | 25.65%  |
| Unknown | 314       | 25.65%  |
| GDM     | 149       | 12.17%  |
| TDM     | 48        | 3.92%   |
| LY-DM   | 3         | 0.25%   |
| GREETD  | 2         | 0.16%   |
| LEMURS  | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 601       | 50.34%  |
| en_GB   | 87        | 7.29%   |
| it_IT   | 80        | 6.7%    |
| de_DE   | 67        | 5.61%   |
| en_CA   | 47        | 3.94%   |
| ru_RU   | 31        | 2.6%    |
| fr_FR   | 27        | 2.26%   |
| en_IN   | 27        | 2.26%   |
| es_ES   | 19        | 1.59%   |
| en_AU   | 19        | 1.59%   |
| pl_PL   | 15        | 1.26%   |
| pt_BR   | 14        | 1.17%   |
| Unknown | 14        | 1.17%   |
| nl_NL   | 10        | 0.84%   |
| es_MX   | 10        | 0.84%   |
| de_AT   | 10        | 0.84%   |
| fi_FI   | 9         | 0.75%   |
| tr_TR   | 8         | 0.67%   |
| es_AR   | 8         | 0.67%   |
| en_DK   | 7         | 0.59%   |
| sv_SE   | 6         | 0.5%    |
| en_NZ   | 6         | 0.5%    |
| en_AG   | 6         | 0.5%    |
| pt_PT   | 5         | 0.42%   |
| nl_BE   | 5         | 0.42%   |
| en_PH   | 5         | 0.42%   |
| en_HK   | 4         | 0.34%   |
| de_CH   | 4         | 0.34%   |
| zh_CN   | 3         | 0.25%   |
| en_SG   | 3         | 0.25%   |
| cs_CZ   | 3         | 0.25%   |
| ru_UA   | 2         | 0.17%   |
| hu_HU   | 2         | 0.17%   |
| es_CO   | 2         | 0.17%   |
| en_ZA   | 2         | 0.17%   |
| en_IL   | 2         | 0.17%   |
| C       | 2         | 0.17%   |
| sr_RS   | 1         | 0.08%   |
| sl_SI   | 1         | 0.08%   |
| sk_SK   | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 775       | 64.48%  |
| BIOS | 427       | 35.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 822       | 68.79%  |
| Btrfs   | 312       | 26.11%  |
| Overlay | 28        | 2.34%   |
| Xfs     | 12        | 1%      |
| Tmpfs   | 12        | 1%      |
| F2fs    | 3         | 0.25%   |
| Unknown | 3         | 0.25%   |
| Zfs     | 1         | 0.08%   |
| XXX4    | 1         | 0.08%   |
| Ext2    | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 805       | 67.08%  |
| Unknown | 314       | 26.17%  |
| MBR     | 81        | 6.75%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1022      | 85.38%  |
| Yes       | 175       | 14.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 814       | 67.33%  |
| Yes       | 395       | 32.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 232       | 19.59%  |
| Lenovo              | 230       | 19.43%  |
| Hewlett-Packard     | 150       | 12.67%  |
| MSI                 | 112       | 9.46%   |
| Dell                | 103       | 8.7%    |
| Gigabyte Technology | 79        | 6.67%   |
| Acer                | 53        | 4.48%   |
| ASRock              | 36        | 3.04%   |
| Apple               | 30        | 2.53%   |
| HUAWEI              | 14        | 1.18%   |
| Microsoft           | 12        | 1.01%   |
| Google              | 12        | 1.01%   |
| Timi                | 11        | 0.93%   |
| Samsung Electronics | 11        | 0.93%   |
| Toshiba             | 9         | 0.76%   |
| Unknown             | 9         | 0.76%   |
| Notebook            | 7         | 0.59%   |
| Sony                | 5         | 0.42%   |
| Positivo            | 4         | 0.34%   |
| Intel               | 4         | 0.34%   |
| Fujitsu             | 4         | 0.34%   |
| ZOTAC               | 3         | 0.25%   |
| TUXEDO              | 3         | 0.25%   |
| Schenker            | 3         | 0.25%   |
| Packard Bell        | 3         | 0.25%   |
| AZW                 | 3         | 0.25%   |
| TrekStor            | 2         | 0.17%   |
| Razer               | 2         | 0.17%   |
| Huanan              | 2         | 0.17%   |
| GPD                 | 2         | 0.17%   |
| Chuwi               | 2         | 0.17%   |
| Biostar             | 2         | 0.17%   |
| BESSTAR Tech        | 2         | 0.17%   |
| AMI                 | 2         | 0.17%   |
| Alienware           | 2         | 0.17%   |
| VIT                 | 1         | 0.08%   |
| UMAX                | 1         | 0.08%   |
| Teclast             | 1         | 0.08%   |
| System76            | 1         | 0.08%   |
| Shinelon Computer   | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 12        | 1.01%   |
| Unknown                               | 10        | 0.84%   |
| ASUS All Series                       | 9         | 0.76%   |
| ASUS TUF Gaming X570-PLUS             | 8         | 0.68%   |
| Apple MacBookAir7,2                   | 7         | 0.59%   |
| MSI MS-7C02                           | 5         | 0.42%   |
| MSI MS-7A38                           | 5         | 0.42%   |
| Microsoft Surface Laptop Go           | 5         | 0.42%   |
| Gigabyte B550 AORUS ELITE V2          | 5         | 0.42%   |
| ASUS ROG STRIX X570-E GAMING          | 5         | 0.42%   |
| MSI MS-7C91                           | 4         | 0.34%   |
| MSI MS-7C56                           | 4         | 0.34%   |
| Gigabyte B450 AORUS ELITE             | 4         | 0.34%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.34%   |
| ASRock B450M Pro4                     | 4         | 0.34%   |
| ASRock B450 Pro4                      | 4         | 0.34%   |
| MSI MS-7C52                           | 3         | 0.25%   |
| MSI MS-7B86                           | 3         | 0.25%   |
| MSI Modern 14 B5M                     | 3         | 0.25%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.25%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.25%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.25%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 3         | 0.25%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 3         | 0.25%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.25%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.25%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.25%   |
| HP Laptop 15-db0xxx                   | 3         | 0.25%   |
| Gigabyte B550M AORUS PRO              | 3         | 0.25%   |
| Gigabyte B450M DS3H                   | 3         | 0.25%   |
| Dell Inspiron 3542                    | 3         | 0.25%   |
| ASUS TUF Gaming B550-PLUS             | 3         | 0.25%   |
| ASUS ROG STRIX B550-F GAMING          | 3         | 0.25%   |
| ASUS PRIME X570-P                     | 3         | 0.25%   |
| ASUS PRIME A320M-K                    | 3         | 0.25%   |
| Apple MacBookPro16,2                  | 3         | 0.25%   |
| Acer Aspire E5-575G                   | 3         | 0.25%   |
| Timi TM1701                           | 2         | 0.17%   |
| Timi A35S                             | 2         | 0.17%   |
| Samsung 950QDB                        | 2         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 103       | 8.7%    |
| ASUS ROG           | 57        | 4.81%   |
| Lenovo IdeaPad     | 53        | 4.48%   |
| Acer Aspire        | 33        | 2.79%   |
| ASUS TUF           | 30        | 2.53%   |
| HP Pavilion        | 29        | 2.45%   |
| Dell Latitude      | 27        | 2.28%   |
| ASUS PRIME         | 27        | 2.28%   |
| Dell Inspiron      | 26        | 2.2%    |
| HP EliteBook       | 21        | 1.77%   |
| Lenovo Yoga        | 19        | 1.6%    |
| ASUS VivoBook      | 19        | 1.6%    |
| HP Laptop          | 17        | 1.44%   |
| Lenovo Legion      | 16        | 1.35%   |
| HP ENVY            | 13        | 1.1%    |
| Dell OptiPlex      | 13        | 1.1%    |
| MSI MS-7C37        | 12        | 1.01%   |
| Microsoft Surface  | 12        | 1.01%   |
| Dell XPS           | 12        | 1.01%   |
| Lenovo ThinkBook   | 11        | 0.93%   |
| ASUS Zenbook       | 11        | 0.93%   |
| Dell Precision     | 10        | 0.84%   |
| ASUS ASUS          | 10        | 0.84%   |
| Unknown            | 10        | 0.84%   |
| MSI Modern         | 9         | 0.76%   |
| Gigabyte B550      | 9         | 0.76%   |
| ASUS All           | 9         | 0.76%   |
| Toshiba Satellite  | 7         | 0.59%   |
| HP 255             | 7         | 0.59%   |
| Gigabyte X570      | 7         | 0.59%   |
| Gigabyte B450      | 7         | 0.59%   |
| ASRock B450        | 7         | 0.59%   |
| Apple MacBookAir7  | 7         | 0.59%   |
| Acer Swift         | 7         | 0.59%   |
| Lenovo IdeaPadFlex | 6         | 0.51%   |
| HP ZBook           | 6         | 0.51%   |
| HP ProBook         | 6         | 0.51%   |
| MSI MS-7C02        | 5         | 0.42%   |
| MSI MS-7A38        | 5         | 0.42%   |
| Lenovo ThinkCentre | 5         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 172       | 14.53%  |
| 2021    | 159       | 13.43%  |
| 2019    | 147       | 12.42%  |
| 2018    | 135       | 11.4%   |
| 2022    | 99        | 8.36%   |
| 2017    | 82        | 6.93%   |
| 2016    | 62        | 5.24%   |
| 2013    | 60        | 5.07%   |
| 2015    | 57        | 4.81%   |
| 2012    | 53        | 4.48%   |
| 2014    | 46        | 3.89%   |
| 2023    | 28        | 2.36%   |
| 2011    | 27        | 2.28%   |
| 2010    | 20        | 1.69%   |
| 2008    | 15        | 1.27%   |
| 2009    | 14        | 1.18%   |
| 2007    | 7         | 0.59%   |
| Unknown | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 691       | 58.36%  |
| Desktop     | 388       | 32.77%  |
| Convertible | 57        | 4.81%   |
| Tablet      | 17        | 1.44%   |
| All in one  | 17        | 1.44%   |
| Mini pc     | 13        | 1.1%    |
| Server      | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1178      | 99.41%  |
| Enabled  | 7         | 0.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1169      | 98.73%  |
| Yes  | 15        | 1.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 300       | 25.06%  |
| 8.01-16.0   | 269       | 22.47%  |
| 4.01-8.0    | 238       | 19.88%  |
| 32.01-64.0  | 203       | 16.96%  |
| 3.01-4.0    | 92        | 7.69%   |
| 24.01-32.0  | 45        | 3.76%   |
| 64.01-256.0 | 39        | 3.26%   |
| 1.01-2.0    | 7         | 0.58%   |
| 2.01-3.0    | 3         | 0.25%   |
| Unknown     | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 331       | 25.46%  |
| 2.01-3.0   | 313       | 24.08%  |
| 1.01-2.0   | 258       | 19.85%  |
| 3.01-4.0   | 244       | 18.77%  |
| 8.01-16.0  | 102       | 7.85%   |
| 0.51-1.0   | 32        | 2.46%   |
| 16.01-24.0 | 13        | 1%      |
| 24.01-32.0 | 4         | 0.31%   |
| 0.01-0.5   | 2         | 0.15%   |
| Unknown    | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 640       | 52.37%  |
| 2      | 324       | 26.51%  |
| 3      | 117       | 9.57%   |
| 4      | 74        | 6.06%   |
| 5      | 33        | 2.7%    |
| 6      | 20        | 1.64%   |
| 0      | 5         | 0.41%   |
| 7      | 4         | 0.33%   |
| 9      | 3         | 0.25%   |
| 8      | 2         | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 975       | 82%     |
| Yes       | 214       | 18%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 948       | 79.73%  |
| No        | 241       | 20.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1004      | 84.37%  |
| No        | 186       | 15.63%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 951       | 79.58%  |
| No        | 244       | 20.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 270       | 22.54%  |
| Italy       | 114       | 9.52%   |
| Germany     | 111       | 9.27%   |
| Canada      | 51        | 4.26%   |
| France      | 44        | 3.67%   |
| Russia      | 38        | 3.17%   |
| Poland      | 34        | 2.84%   |
| India       | 34        | 2.84%   |
| UK          | 33        | 2.75%   |
| Netherlands | 33        | 2.75%   |
| Brazil      | 28        | 2.34%   |
| Spain       | 27        | 2.25%   |
| Turkey      | 26        | 2.17%   |
| Finland     | 22        | 1.84%   |
| Austria     | 21        | 1.75%   |
| Australia   | 21        | 1.75%   |
| Sweden      | 19        | 1.59%   |
| Mexico      | 17        | 1.42%   |
| Belgium     | 16        | 1.34%   |
| Switzerland | 12        | 1%      |
| Indonesia   | 11        | 0.92%   |
| Argentina   | 10        | 0.83%   |
| Romania     | 9         | 0.75%   |
| Hungary     | 9         | 0.75%   |
| Vietnam     | 7         | 0.58%   |
| Portugal    | 7         | 0.58%   |
| New Zealand | 7         | 0.58%   |
| Hong Kong   | 7         | 0.58%   |
| Denmark     | 7         | 0.58%   |
| Czechia     | 7         | 0.58%   |
| Ukraine     | 6         | 0.5%    |
| Norway      | 6         | 0.5%    |
| Malaysia    | 6         | 0.5%    |
| Greece      | 6         | 0.5%    |
| Bangladesh  | 6         | 0.5%    |
| Slovenia    | 5         | 0.42%   |
| Serbia      | 5         | 0.42%   |
| Philippines | 5         | 0.42%   |
| Croatia     | 5         | 0.42%   |
| Colombia    | 5         | 0.42%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Montreal              | 15        | 1.18%   |
| Milan                 | 15        | 1.18%   |
| Berlin                | 13        | 1.03%   |
| Helsinki              | 12        | 0.95%   |
| St Petersburg         | 11        | 0.87%   |
| Istanbul              | 11        | 0.87%   |
| Amsterdam             | 11        | 0.87%   |
| Rome                  | 9         | 0.71%   |
| Hamburg               | 9         | 0.71%   |
| Frankfurt am Main     | 9         | 0.71%   |
| Warsaw                | 8         | 0.63%   |
| Sydney                | 8         | 0.63%   |
| Paris                 | 8         | 0.63%   |
| Vienna                | 7         | 0.55%   |
| Turin                 | 7         | 0.55%   |
| Toms River            | 7         | 0.55%   |
| Moscow                | 7         | 0.55%   |
| Melbourne             | 7         | 0.55%   |
| Toronto               | 6         | 0.47%   |
| Madrid                | 6         | 0.47%   |
| Wroclaw               | 5         | 0.39%   |
| Seattle               | 5         | 0.39%   |
| Portland              | 5         | 0.39%   |
| Naples                | 5         | 0.39%   |
| Jacksonville          | 5         | 0.39%   |
| Houston               | 5         | 0.39%   |
| Florence              | 5         | 0.39%   |
| Belgrade              | 5         | 0.39%   |
| Barberton             | 5         | 0.39%   |
| Zurich                | 4         | 0.32%   |
| Victoria              | 4         | 0.32%   |
| Singapore             | 4         | 0.32%   |
| San Luis Potosí City | 4         | 0.32%   |
| Rotterdam             | 4         | 0.32%   |
| Ottawa                | 4         | 0.32%   |
| Miami                 | 4         | 0.32%   |
| Mexico City           | 4         | 0.32%   |
| Mesa                  | 4         | 0.32%   |
| Malmo                 | 4         | 0.32%   |
| Los Angeles           | 4         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 395       | 607    | 20.29%  |
| Seagate                     | 217       | 306    | 11.15%  |
| WDC                         | 208       | 324    | 10.68%  |
| Sandisk                     | 140       | 174    | 7.19%   |
| Kingston                    | 126       | 179    | 6.47%   |
| Crucial                     | 81        | 120    | 4.16%   |
| SK hynix                    | 77        | 95     | 3.95%   |
| Toshiba                     | 76        | 91     | 3.9%    |
| Intel                       | 52        | 66     | 2.67%   |
| Micron Technology           | 51        | 57     | 2.62%   |
| Unknown                     | 47        | 62     | 2.41%   |
| HGST                        | 31        | 40     | 1.59%   |
| KIOXIA                      | 30        | 31     | 1.54%   |
| Hitachi                     | 28        | 30     | 1.44%   |
| A-DATA Technology           | 25        | 36     | 1.28%   |
| Apple                       | 24        | 32     | 1.23%   |
| Phison Electronics          | 22        | 24     | 1.13%   |
| Phison                      | 20        | 21     | 1.03%   |
| Micron/Crucial Technology   | 17        | 26     | 0.87%   |
| Kingston Technology Company | 17        | 19     | 0.87%   |
| China                       | 16        | 16     | 0.82%   |
| Corsair                     | 11        | 11     | 0.56%   |
| SPCC                        | 9         | 10     | 0.46%   |
| Patriot                     | 9         | 12     | 0.46%   |
| PNY                         | 8         | 9      | 0.41%   |
| LITEONIT                    | 8         | 9      | 0.41%   |
| ADATA Technology            | 8         | 8      | 0.41%   |
| Silicon Motion              | 7         | 7      | 0.36%   |
| Gigabyte Technology         | 7         | 9      | 0.36%   |
| Transcend                   | 6         | 7      | 0.31%   |
| OCZ                         | 6         | 6      | 0.31%   |
| JMicron Technology          | 6         | 6      | 0.31%   |
| Intenso                     | 6         | 8      | 0.31%   |
| XPG                         | 5         | 5      | 0.26%   |
| Union Memory (Shenzhen)     | 5         | 5      | 0.26%   |
| Realtek                     | 5         | 9      | 0.26%   |
| Mushkin                     | 5         | 5      | 0.26%   |
| LITEON                      | 5         | 7      | 0.26%   |
| SABRENT                     | 4         | 6      | 0.21%   |
| Realtek Semiconductor       | 4         | 4      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 67        | 3.09%   |
| Seagate ST2000DM008-2FR102 2TB                        | 28        | 1.29%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 28        | 1.29%   |
| Kingston SA400S37240G 240GB SSD                       | 27        | 1.25%   |
| Samsung SSD 860 EVO 1TB                               | 23        | 1.06%   |
| Seagate ST1000LM035-1RK172 1TB                        | 20        | 0.92%   |
| Crucial CT500MX500SSD1 500GB                          | 20        | 0.92%   |
| Samsung SSD 860 EVO 500GB                             | 18        | 0.83%   |
| Samsung SSD 850 EVO 250GB                             | 18        | 0.83%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 17        | 0.78%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 16        | 0.74%   |
| Samsung SSD 870 QVO 1TB                               | 16        | 0.74%   |
| Samsung SSD 850 EVO 500GB                             | 15        | 0.69%   |
| Kingston SA400S37120G 120GB SSD                       | 15        | 0.69%   |
| Kingston SA400S37480G 480GB SSD                       | 14        | 0.65%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 12        | 0.55%   |
| HGST HTS721010A9E630 1TB                              | 12        | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB                        | 11        | 0.51%   |
| Seagate ST1000DM010-2EP102 1TB                        | 11        | 0.51%   |
| Samsung SSD 980 1TB                                   | 11        | 0.51%   |
| Samsung SSD 860 EVO 250GB                             | 11        | 0.51%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 10        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                           | 10        | 0.46%   |
| Toshiba MQ01ABD100 1TB                                | 9         | 0.42%   |
| Seagate ST500LT012-1DG142 500GB                       | 9         | 0.42%   |
| Samsung SSD 970 EVO 500GB                             | 9         | 0.42%   |
| Phison E16 PCIe4 NVMe Controller 500GB                | 9         | 0.42%   |
| Crucial CT240BX500SSD1 240GB                          | 9         | 0.42%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 8         | 0.37%   |
| Unknown SD/MMC/MS PRO 16GB                            | 8         | 0.37%   |
| Unknown MMC Card  64GB                                | 8         | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB                        | 8         | 0.37%   |
| Samsung SSD 980 500GB                                 | 8         | 0.37%   |
| Intel SSD 660P Series 1024GB                          | 8         | 0.37%   |
| Unknown MMC Card  16GB                                | 7         | 0.32%   |
| Unknown MMC Card  128GB                               | 7         | 0.32%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 7         | 0.32%   |
| Seagate ST1000LM049-2GH172 1TB                        | 7         | 0.32%   |
| Seagate Expansion Desk 3TB                            | 7         | 0.32%   |
| Samsung SSD 870 EVO 1TB                               | 7         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 207       | 292    | 41.24%  |
| WDC                 | 146       | 221    | 29.08%  |
| Toshiba             | 46        | 52     | 9.16%   |
| HGST                | 31        | 40     | 6.18%   |
| Hitachi             | 28        | 30     | 5.58%   |
| Samsung Electronics | 12        | 33     | 2.39%   |
| Unknown             | 8         | 8      | 1.59%   |
| Maxtor              | 3         | 3      | 0.6%    |
| Maxone              | 3         | 3      | 0.6%    |
| Fujitsu             | 3         | 3      | 0.6%    |
| Apple               | 3         | 3      | 0.6%    |
| ASMT                | 2         | 4      | 0.4%    |
| USB3.0              | 1         | 1      | 0.2%    |
| StoreJet            | 1         | 1      | 0.2%    |
| RSH-319             | 1         | 2      | 0.2%    |
| PI-041              | 1         | 1      | 0.2%    |
| MaxDigital          | 1         | 2      | 0.2%    |
| JMicron Technology  | 1         | 1      | 0.2%    |
| HPE                 | 1         | 1      | 0.2%    |
| Generic-            | 1         | 1      | 0.2%    |
| Fantom              | 1         | 2      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 194       | 272    | 28.16%  |
| Kingston            | 86        | 124    | 12.48%  |
| Crucial             | 73        | 103    | 10.6%   |
| SanDisk             | 50        | 57     | 7.26%   |
| WDC                 | 48        | 62     | 6.97%   |
| A-DATA Technology   | 18        | 22     | 2.61%   |
| SK hynix            | 17        | 22     | 2.47%   |
| China               | 16        | 16     | 2.32%   |
| Micron Technology   | 13        | 17     | 1.89%   |
| Apple               | 13        | 16     | 1.89%   |
| Intel               | 12        | 16     | 1.74%   |
| Toshiba             | 11        | 13     | 1.6%    |
| Patriot             | 9         | 12     | 1.31%   |
| LITEONIT            | 8         | 9      | 1.16%   |
| SPCC                | 7         | 8      | 1.02%   |
| Corsair             | 7         | 7      | 1.02%   |
| OCZ                 | 6         | 6      | 0.87%   |
| Intenso             | 6         | 8      | 0.87%   |
| Gigabyte Technology | 6         | 7      | 0.87%   |
| Transcend           | 5         | 5      | 0.73%   |
| Seagate             | 5         | 7      | 0.73%   |
| PNY                 | 5         | 6      | 0.73%   |
| SABRENT             | 4         | 6      | 0.58%   |
| Mushkin             | 4         | 4      | 0.58%   |
| LITEON              | 4         | 5      | 0.58%   |
| GOODRAM             | 4         | 4      | 0.58%   |
| Netac               | 3         | 4      | 0.44%   |
| Hewlett-Packard     | 3         | 3      | 0.44%   |
| Emtec               | 3         | 3      | 0.44%   |
| WDC WDS             | 2         | 2      | 0.29%   |
| Teclast             | 2         | 4      | 0.29%   |
| Plextor             | 2         | 3      | 0.29%   |
| Phison              | 2         | 2      | 0.29%   |
| Leven               | 2         | 3      | 0.29%   |
| KingSpec            | 2         | 2      | 0.29%   |
| KingFast            | 2         | 2      | 0.29%   |
| Apacer              | 2         | 2      | 0.29%   |
| Zheino              | 1         | 1      | 0.15%   |
| WALTON              | 1         | 2      | 0.15%   |
| V-GeN               | 1         | 1      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 674       | 959    | 39.95%  |
| SSD     | 541       | 916    | 32.07%  |
| HDD     | 413       | 705    | 24.48%  |
| MMC     | 37        | 47     | 2.19%   |
| Unknown | 22        | 29     | 1.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 709       | 1519   | 46.8%   |
| NVMe | 671       | 945    | 44.29%  |
| SAS  | 98        | 145    | 6.47%   |
| MMC  | 37        | 47     | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 504       | 869    | 48.7%   |
| 0.51-1.0   | 330       | 466    | 31.88%  |
| 1.01-2.0   | 112       | 169    | 10.82%  |
| 3.01-4.0   | 37        | 55     | 3.57%   |
| 2.01-3.0   | 27        | 30     | 2.61%   |
| 4.01-10.0  | 19        | 26     | 1.84%   |
| 10.01-20.0 | 6         | 6      | 0.58%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 250       | 20.15%  |
| 251-500        | 213       | 17.16%  |
| 1001-2000      | 196       | 15.79%  |
| 501-1000       | 189       | 15.23%  |
| More than 3000 | 119       | 9.59%   |
| Unknown        | 75        | 6.04%   |
| 2001-3000      | 67        | 5.4%    |
| 1-20           | 64        | 5.16%   |
| 51-100         | 46        | 3.71%   |
| 21-50          | 22        | 1.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 283       | 21.85%  |
| 101-250        | 194       | 14.98%  |
| 21-50          | 190       | 14.67%  |
| 51-100         | 166       | 12.82%  |
| 251-500        | 129       | 9.96%   |
| 501-1000       | 106       | 8.19%   |
| 1001-2000      | 91        | 7.03%   |
| Unknown        | 75        | 5.79%   |
| More than 3000 | 36        | 2.78%   |
| 2001-3000      | 21        | 1.62%   |
| 0              | 4         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB               | 6         | 11     | 5.13%   |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.42%   |
| Seagate ST500LT012-1DG142 500GB          | 3         | 3      | 2.56%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 3      | 2.56%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 2         | 2      | 1.71%   |
| WDC WD20EARX-00PASB0 2TB                 | 2         | 2      | 1.71%   |
| Toshiba MQ01ABD100 1TB                   | 2         | 2      | 1.71%   |
| Seagate ST9320325AS 320GB                | 2         | 5      | 1.71%   |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 8      | 1.71%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 1.71%   |
| Corsair Force LS SSD 120GB               | 2         | 2      | 1.71%   |
| XPG GAMMIX S11 240GB                     | 1         | 1      | 0.85%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.85%   |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 0.85%   |
| WDC WD5000BPVT-60HXZT3 500GB             | 1         | 1      | 0.85%   |
| WDC WD5000AZRX-00A8LB0 500GB             | 1         | 1      | 0.85%   |
| WDC WD5000AVDS-63U7B1 500GB              | 1         | 1      | 0.85%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1         | 2      | 0.85%   |
| WDC WD2003FZEX-00Z4SA0 2TB               | 1         | 1      | 0.85%   |
| WDC WD2002FYPS-01U1B0 2TB                | 1         | 1      | 0.85%   |
| WDC WD2000FYYZ-01UL1B2 2TB               | 1         | 1      | 0.85%   |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10EZRX-00D8PB0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1         | 1      | 0.85%   |
| WDC WD10EACS-00D6B1 1TB                  | 1         | 1      | 0.85%   |
| WDC WD1003FBYZ-010FB0 1TB                | 1         | 2      | 0.85%   |
| WDC WD1002FBYS-02A6B0 1TB                | 1         | 1      | 0.85%   |
| WDC WD Blue SA510 2.5 1TB                | 1         | 2      | 0.85%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB     | 1         | 1      | 0.85%   |
| Transcend TS240GMTS420S 240GB SSD        | 1         | 1      | 0.85%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.85%   |
| Toshiba THNSNK128GCS8 SATA 128GB SSD     | 1         | 1      | 0.85%   |
| Toshiba MQ01ABD050 500GB                 | 1         | 2      | 0.85%   |
| Toshiba MK5055GSXF 500GB                 | 1         | 1      | 0.85%   |
| Toshiba MK2533GSG 250GB                  | 1         | 1      | 0.85%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 0.85%   |
| Toshiba DT01ACA300 3TB                   | 1         | 2      | 0.85%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 0.85%   |
| Toshiba DT01ACA050 500GB                 | 1         | 1      | 0.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 35     | 20%     |
| WDC                 | 21        | 25     | 18.26%  |
| Toshiba             | 11        | 13     | 9.57%   |
| HGST                | 11        | 16     | 9.57%   |
| Samsung Electronics | 8         | 13     | 6.96%   |
| SK hynix            | 6         | 6      | 5.22%   |
| Hitachi             | 5         | 5      | 4.35%   |
| SanDisk             | 4         | 5      | 3.48%   |
| Crucial             | 4         | 14     | 3.48%   |
| Intel               | 3         | 3      | 2.61%   |
| Kingston            | 2         | 2      | 1.74%   |
| Corsair             | 2         | 2      | 1.74%   |
| Apple               | 2         | 2      | 1.74%   |
| XPG                 | 1         | 1      | 0.87%   |
| Transcend           | 1         | 1      | 0.87%   |
| SSSTC               | 1         | 1      | 0.87%   |
| Patriot             | 1         | 1      | 0.87%   |
| OCZ                 | 1         | 1      | 0.87%   |
| Micron Technology   | 1         | 1      | 0.87%   |
| LITEONIT            | 1         | 1      | 0.87%   |
| Fujitsu             | 1         | 1      | 0.87%   |
| Drevo               | 1         | 1      | 0.87%   |
| China               | 1         | 1      | 0.87%   |
| ASMT                | 1         | 2      | 0.87%   |
| Actseno             | 1         | 1      | 0.87%   |
| A-DATA Technology   | 1         | 1      | 0.87%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 35     | 34.33%  |
| WDC                 | 17        | 19     | 25.37%  |
| HGST                | 11        | 16     | 16.42%  |
| Toshiba             | 8         | 10     | 11.94%  |
| Hitachi             | 5         | 5      | 7.46%   |
| Samsung Electronics | 1         | 1      | 1.49%   |
| Fujitsu             | 1         | 1      | 1.49%   |
| ASMT                | 1         | 2      | 1.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 64        | 89     | 58.18%  |
| SSD  | 38        | 53     | 34.55%  |
| NVMe | 8         | 13     | 7.27%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HD252HJ 250GB | 1         | 1      | 33.33%  |
| LITEON CA3-8D512 512GB            | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| LITEON              | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 813       | 1633   | 61.22%  |
| Detected | 406       | 864    | 30.57%  |
| Malfunc  | 106       | 155    | 7.98%   |
| Failed   | 3         | 4      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 615       | 36.07%  |
| AMD                            | 304       | 17.83%  |
| Samsung Electronics            | 241       | 14.13%  |
| SanDisk                        | 125       | 7.33%   |
| SK hynix                       | 59        | 3.46%   |
| Kingston Technology Company    | 59        | 3.46%   |
| Phison Electronics             | 48        | 2.82%   |
| Micron Technology              | 39        | 2.29%   |
| ASMedia Technology             | 37        | 2.17%   |
| KIOXIA                         | 32        | 1.88%   |
| Micron/Crucial Technology      | 25        | 1.47%   |
| Toshiba America Info Systems   | 19        | 1.11%   |
| ADATA Technology               | 15        | 0.88%   |
| Silicon Motion                 | 10        | 0.59%   |
| Solid State Storage Technology | 8         | 0.47%   |
| Realtek Semiconductor          | 8         | 0.47%   |
| Apple                          | 8         | 0.47%   |
| Union Memory (Shenzhen)        | 7         | 0.41%   |
| Marvell Technology Group       | 7         | 0.41%   |
| JMicron Technology             | 7         | 0.41%   |
| Seagate Technology             | 5         | 0.29%   |
| Nvidia                         | 5         | 0.29%   |
| MAXIO Technology (Hangzhou)    | 5         | 0.29%   |
| Shenzhen Longsys Electronics   | 3         | 0.18%   |
| Lenovo                         | 3         | 0.18%   |
| Yangtze Memory Technologies    | 2         | 0.12%   |
| Transcend                      | 2         | 0.12%   |
| Lite-On Technology             | 2         | 0.12%   |
| VIA Technologies               | 1         | 0.06%   |
| LSI Logic / Symbios Logic      | 1         | 0.06%   |
| INNOGRIT                       | 1         | 0.06%   |
| Broadcom / LSI                 | 1         | 0.06%   |
| Biwin Storage Technology       | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 229       | 12.33%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 116       | 6.24%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 68        | 3.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 62        | 3.34%   |
| AMD 400 Series Chipset SATA Controller                                         | 61        | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 47        | 2.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 38        | 2.05%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 37        | 1.99%   |
| AMD 500 Series Chipset SATA Controller                                         | 37        | 1.99%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 36        | 1.94%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 35        | 1.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 34        | 1.83%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 30        | 1.61%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 28        | 1.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 28        | 1.51%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 27        | 1.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 27        | 1.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 22        | 1.18%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 21        | 1.13%   |
| Intel Comet Lake SATA AHCI Controller                                          | 20        | 1.08%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 20        | 1.08%   |
| Phison E12 NVMe Controller                                                     | 19        | 1.02%   |
| Intel Tiger Lake-LP SATA Controller                                            | 18        | 0.97%   |
| Intel SSD 660P Series                                                          | 18        | 0.97%   |
| Phison E16 PCIe4 NVMe Controller                                               | 17        | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 17        | 0.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 16        | 0.86%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 16        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15        | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 0.81%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 14        | 0.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 14        | 0.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 13        | 0.7%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 12        | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.65%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 12        | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 12        | 0.65%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 11        | 0.59%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 11        | 0.59%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 10        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 819       | 50.34%  |
| NVMe | 670       | 41.18%  |
| RAID | 96        | 5.9%    |
| IDE  | 37        | 2.27%   |
| SAS  | 5         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 746       | 62.95%  |
| AMD     | 437       | 36.88%  |
| ARM     | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 20        | 1.69%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 20        | 1.69%   |
| AMD Ryzen 5 3600 6-Core Processor             | 20        | 1.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 1.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 18        | 1.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 1.43%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 15        | 1.27%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 1.18%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.18%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 1.1%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 1.01%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 1.01%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 11        | 0.93%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 0.93%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 11        | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.84%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.84%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 10        | 0.84%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.84%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 10        | 0.84%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.76%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 9         | 0.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.68%   |
| Intel 12th Gen Core i7-12700H                 | 8         | 0.68%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.59%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 7         | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.59%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 7         | 0.59%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 0.59%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.59%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 7         | 0.59%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.59%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 7         | 0.59%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 7         | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 251       | 21.18%  |
| Intel Core i7           | 218       | 18.4%   |
| AMD Ryzen 5             | 153       | 12.91%  |
| AMD Ryzen 7             | 145       | 12.24%  |
| Other                   | 128       | 10.8%   |
| AMD Ryzen 9             | 50        | 4.22%   |
| Intel Core i3           | 48        | 4.05%   |
| Intel Celeron           | 38        | 3.21%   |
| Intel Core 2 Duo        | 20        | 1.69%   |
| Intel Xeon              | 19        | 1.6%    |
| AMD Ryzen 3             | 19        | 1.6%    |
| AMD Ryzen 7 PRO         | 18        | 1.52%   |
| Intel Pentium           | 11        | 0.93%   |
| AMD A4                  | 8         | 0.68%   |
| Intel Core i9           | 6         | 0.51%   |
| AMD FX                  | 6         | 0.51%   |
| AMD Athlon              | 5         | 0.42%   |
| Intel Core m3           | 4         | 0.34%   |
| AMD Ryzen 5 PRO         | 4         | 0.34%   |
| AMD A8                  | 4         | 0.34%   |
| Intel Core 2 Quad       | 3         | 0.25%   |
| AMD Ryzen Threadripper  | 3         | 0.25%   |
| AMD A10                 | 3         | 0.25%   |
| Intel Pentium Gold      | 2         | 0.17%   |
| Intel Pentium Dual-Core | 2         | 0.17%   |
| Intel Core 2            | 2         | 0.17%   |
| Intel Atom              | 2         | 0.17%   |
| AMD E1                  | 2         | 0.17%   |
| Intel Pentium Dual      | 1         | 0.08%   |
| Intel Core m5           | 1         | 0.08%   |
| Intel Core 2 Extreme    | 1         | 0.08%   |
| AMD Phenom II X6        | 1         | 0.08%   |
| AMD Phenom II X4        | 1         | 0.08%   |
| AMD E2                  | 1         | 0.08%   |
| AMD E                   | 1         | 0.08%   |
| AMD Athlon X4           | 1         | 0.08%   |
| AMD Athlon II X4        | 1         | 0.08%   |
| AMD Athlon II           | 1         | 0.08%   |
| AMD A6                  | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 402       | 33.9%   |
| 2       | 291       | 24.54%  |
| 8       | 212       | 17.88%  |
| 6       | 186       | 15.68%  |
| 12      | 37        | 3.12%   |
| 14      | 22        | 1.85%   |
| 10      | 14        | 1.18%   |
| 16      | 13        | 1.1%    |
| 3       | 3         | 0.25%   |
| 24      | 2         | 0.17%   |
| 32      | 1         | 0.08%   |
| 5       | 1         | 0.08%   |
| 1       | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1179      | 99.41%  |
| 2       | 6         | 0.51%   |
| Unknown | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 970       | 81.79%  |
| 1       | 215       | 18.13%  |
| Unknown | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1181      | 99.66%  |
| Unknown        | 3         | 0.25%   |
| 64-bit         | 1         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 528       | 43.31%  |
| 0x0a50000c | 41        | 3.36%   |
| 0x08701021 | 33        | 2.71%   |
| 0x306c3    | 31        | 2.54%   |
| 0x306a9    | 25        | 2.05%   |
| 0x806ea    | 24        | 1.97%   |
| 0x08108109 | 24        | 1.97%   |
| 0x406e3    | 22        | 1.8%    |
| 0x906ea    | 20        | 1.64%   |
| 0x806e9    | 20        | 1.64%   |
| 0x08600106 | 20        | 1.64%   |
| 0x806ec    | 18        | 1.48%   |
| 0x806c1    | 18        | 1.48%   |
| 0x506e3    | 18        | 1.48%   |
| 0x08608103 | 18        | 1.48%   |
| 0x40651    | 17        | 1.39%   |
| 0x08600104 | 16        | 1.31%   |
| 0x906e9    | 15        | 1.23%   |
| 0x0a404102 | 14        | 1.15%   |
| 0x0a50000d | 13        | 1.07%   |
| 0x706e5    | 12        | 0.98%   |
| 0x0a201009 | 12        | 0.98%   |
| 0x08108102 | 12        | 0.98%   |
| 0x206a7    | 11        | 0.9%    |
| 0x08701013 | 11        | 0.9%    |
| 0x906a3    | 10        | 0.82%   |
| 0x706a1    | 9         | 0.74%   |
| 0x306d4    | 9         | 0.74%   |
| 0x1067a    | 9         | 0.74%   |
| 0x0a20120a | 9         | 0.74%   |
| 0x0a201016 | 8         | 0.66%   |
| 0xa0652    | 7         | 0.57%   |
| 0x406c4    | 7         | 0.57%   |
| 0x0800820d | 7         | 0.57%   |
| 0x08001138 | 7         | 0.57%   |
| 0x806d1    | 6         | 0.49%   |
| 0x06006705 | 6         | 0.49%   |
| 0xa0655    | 5         | 0.41%   |
| 0x20655    | 5         | 0.41%   |
| 0x0a601203 | 5         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 213       | 17.96%  |
| Zen 3            | 123       | 10.37%  |
| Zen 2            | 122       | 10.29%  |
| Haswell          | 94        | 7.93%   |
| Unknown          | 90        | 7.59%   |
| Skylake          | 72        | 6.07%   |
| Zen+             | 60        | 5.06%   |
| IvyBridge        | 48        | 4.05%   |
| TigerLake        | 47        | 3.96%   |
| Alderlake Hybrid | 42        | 3.54%   |
| CometLake        | 34        | 2.87%   |
| IceLake          | 33        | 2.78%   |
| SandyBridge      | 31        | 2.61%   |
| Zen              | 26        | 2.19%   |
| Broadwell        | 24        | 2.02%   |
| Penryn           | 21        | 1.77%   |
| Excavator        | 17        | 1.43%   |
| Goldmont plus    | 16        | 1.35%   |
| Westmere         | 14        | 1.18%   |
| Silvermont       | 14        | 1.18%   |
| Core             | 10        | 0.84%   |
| Piledriver       | 7         | 0.59%   |
| Jaguar           | 6         | 0.51%   |
| Nehalem          | 5         | 0.42%   |
| Goldmont         | 4         | 0.34%   |
| Tremont          | 3         | 0.25%   |
| K10              | 3         | 0.25%   |
| Puma             | 2         | 0.17%   |
| Bulldozer        | 2         | 0.17%   |
| Steamroller      | 1         | 0.08%   |
| K10 Llano        | 1         | 0.08%   |
| Bobcat           | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 586       | 40.14%  |
| Nvidia | 451       | 30.89%  |
| AMD    | 423       | 28.97%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]               | 54        | 3.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 50        | 3.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 47        | 3.12%   |
| Intel UHD Graphics 620                                                      | 45        | 2.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 40        | 2.65%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 36        | 2.39%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 31        | 2.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 28        | 1.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 28        | 1.86%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 28        | 1.86%   |
| Intel HD Graphics 620                                                       | 27        | 1.79%   |
| AMD Rembrandt [Radeon 680M]                                                 | 27        | 1.79%   |
| AMD Lucienne                                                                | 26        | 1.72%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 23        | 1.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 21        | 1.39%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                   | 21        | 1.39%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 20        | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 19        | 1.26%   |
| Intel HD Graphics 530                                                       | 19        | 1.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 19        | 1.26%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 18        | 1.19%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 18        | 1.19%   |
| Intel HD Graphics 630                                                       | 18        | 1.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 18        | 1.19%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 17        | 1.13%   |
| Intel HD Graphics 5500                                                      | 16        | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 16        | 1.06%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 15        | 0.99%   |
| AMD Barcelo                                                                 | 15        | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 14        | 0.93%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 14        | 0.93%   |
| Nvidia GP108M [GeForce MX150]                                               | 13        | 0.86%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 13        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 12        | 0.8%    |
| Nvidia GP104 [GeForce GTX 1070]                                             | 12        | 0.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 12        | 0.8%    |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 11        | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11        | 0.73%   |
| Intel Core Processor Integrated Graphics Controller                         | 11        | 0.73%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 10        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 362       | 30.39%  |
| 1 x AMD                  | 305       | 25.61%  |
| 1 x Nvidia               | 209       | 17.55%  |
| Intel + Nvidia           | 183       | 15.37%  |
| AMD + Nvidia             | 54        | 4.53%   |
| 2 x AMD                  | 41        | 3.44%   |
| Intel + AMD              | 26        | 2.18%   |
| 2 x Intel                | 5         | 0.42%   |
| 2 x Nvidia               | 3         | 0.25%   |
| Other                    | 2         | 0.17%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 844       | 70.86%  |
| Proprietary | 345       | 28.97%  |
| Unknown     | 2         | 0.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 666       | 55.18%  |
| 0.01-0.5   | 126       | 10.44%  |
| 1.01-2.0   | 103       | 8.53%   |
| 7.01-8.0   | 92        | 7.62%   |
| 3.01-4.0   | 75        | 6.21%   |
| 8.01-16.0  | 50        | 4.14%   |
| 5.01-6.0   | 46        | 3.81%   |
| 0.51-1.0   | 35        | 2.9%    |
| 2.01-3.0   | 8         | 0.66%   |
| 16.01-24.0 | 6         | 0.5%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 163       | 11.21%  |
| Samsung Electronics     | 155       | 10.66%  |
| BOE                     | 144       | 9.9%    |
| Chimei Innolux          | 137       | 9.42%   |
| LG Display              | 114       | 7.84%   |
| Goldstar                | 77        | 5.3%    |
| Dell                    | 66        | 4.54%   |
| Acer                    | 56        | 3.85%   |
| AOC                     | 48        | 3.3%    |
| Ancor Communications    | 41        | 2.82%   |
| Lenovo                  | 36        | 2.48%   |
| Hewlett-Packard         | 36        | 2.48%   |
| BenQ                    | 36        | 2.48%   |
| Apple                   | 29        | 1.99%   |
| ASUSTek Computer        | 27        | 1.86%   |
| PANDA                   | 26        | 1.79%   |
| Sharp                   | 24        | 1.65%   |
| Philips                 | 18        | 1.24%   |
| ViewSonic               | 17        | 1.17%   |
| Iiyama                  | 15        | 1.03%   |
| InfoVision              | 13        | 0.89%   |
| Gigabyte Technology     | 13        | 0.89%   |
| CSO                     | 11        | 0.76%   |
| TMX                     | 10        | 0.69%   |
| Vizio                   | 9         | 0.62%   |
| LG Electronics          | 7         | 0.48%   |
| MSI                     | 6         | 0.41%   |
| Chi Mei Optoelectronics | 6         | 0.41%   |
| Unknown                 | 5         | 0.34%   |
| Sony                    | 5         | 0.34%   |
| Fujitsu Siemens         | 5         | 0.34%   |
| Pixio                   | 4         | 0.28%   |
| ___                     | 3         | 0.21%   |
| Valve                   | 3         | 0.21%   |
| Toshiba                 | 3         | 0.21%   |
| Sceptre Tech            | 3         | 0.21%   |
| RTK                     | 3         | 0.21%   |
| Panasonic               | 3         | 0.21%   |
| Mi                      | 3         | 0.21%   |
| LG Philips              | 3         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 9         | 0.6%    |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 8         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.53%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 7         | 0.47%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 7         | 0.47%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 0.47%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 7         | 0.47%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 598x336mm 27.0-inch         | 6         | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.4%    |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 6         | 0.4%    |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 5         | 0.33%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5         | 0.33%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 5         | 0.33%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 5         | 0.33%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.33%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 5         | 0.33%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 5         | 0.33%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 5         | 0.33%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.33%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 530x300mm 24.0-inch     | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 4         | 0.27%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.27%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 0.27%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 0.27%   |
| Goldstar ULTRAGEAR GSM5BB4 2560x1440 597x336mm 27.0-inch              | 4         | 0.27%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 4         | 0.27%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch        | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.27%   |
| AOC 24B2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 4         | 0.27%   |
| ___ LCDTV16 ___3393 1920x1080                                         | 3         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 671       | 49.05%  |
| 1366x768 (WXGA)    | 157       | 11.48%  |
| 2560x1440 (QHD)    | 123       | 8.99%   |
| 3840x2160 (4K)     | 103       | 7.53%   |
| 2560x1600          | 39        | 2.85%   |
| 1920x1200 (WUXGA)  | 35        | 2.56%   |
| 1440x900 (WXGA+)   | 26        | 1.9%    |
| 2560x1080          | 22        | 1.61%   |
| 1600x900 (HD+)     | 20        | 1.46%   |
| 1280x1024 (SXGA)   | 19        | 1.39%   |
| 3440x1440          | 17        | 1.24%   |
| 2880x1800          | 17        | 1.24%   |
| 1680x1050 (WSXGA+) | 16        | 1.17%   |
| Unknown            | 15        | 1.1%    |
| 1280x800 (WXGA)    | 9         | 0.66%   |
| 2736x1824          | 8         | 0.58%   |
| 3840x1080          | 7         | 0.51%   |
| 2160x1440          | 7         | 0.51%   |
| 3840x2400          | 6         | 0.44%   |
| 3200x2000          | 5         | 0.37%   |
| 1360x768           | 5         | 0.37%   |
| 3456x2160          | 3         | 0.22%   |
| 3200x1800 (QHD+)   | 3         | 0.22%   |
| 3072x1920          | 3         | 0.22%   |
| 3000x2000          | 3         | 0.22%   |
| 1920x540           | 3         | 0.22%   |
| 3840x1600          | 2         | 0.15%   |
| 2240x1400          | 2         | 0.15%   |
| 1920x1280          | 2         | 0.15%   |
| 1800x1200          | 2         | 0.15%   |
| 1024x768 (XGA)     | 2         | 0.15%   |
| 9840x3840          | 1         | 0.07%   |
| 5760x1080          | 1         | 0.07%   |
| 4480x1440          | 1         | 0.07%   |
| 3840x2560          | 1         | 0.07%   |
| 3840x1440          | 1         | 0.07%   |
| 3840x1200          | 1         | 0.07%   |
| 3840x1100          | 1         | 0.07%   |
| 3520x1080          | 1         | 0.07%   |
| 3240x2160          | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 329       | 22.5%   |
| 13      | 154       | 10.53%  |
| 27      | 151       | 10.33%  |
| 24      | 139       | 9.51%   |
| 14      | 133       | 9.1%    |
| 23      | 71        | 4.86%   |
| 21      | 67        | 4.58%   |
| 17      | 52        | 3.56%   |
| 31      | 48        | 3.28%   |
| 16      | 42        | 2.87%   |
| Unknown | 41        | 2.8%    |
| 34      | 36        | 2.46%   |
| 12      | 25        | 1.71%   |
| 19      | 20        | 1.37%   |
| 18      | 16        | 1.09%   |
| 11      | 14        | 0.96%   |
| 22      | 13        | 0.89%   |
| 54      | 12        | 0.82%   |
| 20      | 12        | 0.82%   |
| 40      | 8         | 0.55%   |
| 32      | 8         | 0.55%   |
| 84      | 7         | 0.48%   |
| 72      | 6         | 0.41%   |
| 28      | 5         | 0.34%   |
| 10      | 5         | 0.34%   |
| 46      | 4         | 0.27%   |
| 42      | 4         | 0.27%   |
| 29      | 4         | 0.27%   |
| 52      | 3         | 0.21%   |
| 49      | 3         | 0.21%   |
| 37      | 3         | 0.21%   |
| 26      | 3         | 0.21%   |
| 25      | 3         | 0.21%   |
| 74      | 2         | 0.14%   |
| 69      | 2         | 0.14%   |
| 65      | 2         | 0.14%   |
| 58      | 2         | 0.14%   |
| 48      | 2         | 0.14%   |
| 36      | 2         | 0.14%   |
| 35      | 2         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 571       | 40.61%  |
| 501-600     | 312       | 22.19%  |
| 201-300     | 124       | 8.82%   |
| 401-500     | 114       | 8.11%   |
| 351-400     | 67        | 4.77%   |
| 601-700     | 64        | 4.55%   |
| 701-800     | 47        | 3.34%   |
| Unknown     | 41        | 2.92%   |
| 1001-1500   | 30        | 2.13%   |
| 1501-2000   | 17        | 1.21%   |
| 801-900     | 14        | 1%      |
| 901-1000    | 4         | 0.28%   |
| 101-200     | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 958       | 76.64%  |
| 16/10   | 158       | 12.64%  |
| 21/9    | 40        | 3.2%    |
| Unknown | 32        | 2.56%   |
| 3/2     | 28        | 2.24%   |
| 5/4     | 14        | 1.12%   |
| 4/3     | 6         | 0.48%   |
| 6/5     | 4         | 0.32%   |
| 32/9    | 4         | 0.32%   |
| 2.65    | 3         | 0.24%   |
| 3.40    | 1         | 0.08%   |
| 0.62    | 1         | 0.08%   |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 331       | 22.99%  |
| 81-90          | 223       | 15.49%  |
| 201-250        | 219       | 15.21%  |
| 301-350        | 155       | 10.76%  |
| 351-500        | 95        | 6.6%    |
| 71-80          | 70        | 4.86%   |
| 151-200        | 48        | 3.33%   |
| 251-300        | 46        | 3.19%   |
| 121-130        | 41        | 2.85%   |
| Unknown        | 41        | 2.85%   |
| More than 1000 | 40        | 2.78%   |
| 111-120        | 37        | 2.57%   |
| 501-1000       | 26        | 1.81%   |
| 141-150        | 21        | 1.46%   |
| 61-70          | 15        | 1.04%   |
| 51-60          | 15        | 1.04%   |
| 131-140        | 8         | 0.56%   |
| 41-50          | 5         | 0.35%   |
| 91-100         | 3         | 0.21%   |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 454       | 33.21%  |
| 51-100        | 379       | 27.72%  |
| 101-120       | 271       | 19.82%  |
| 161-240       | 137       | 10.02%  |
| More than 240 | 51        | 3.73%   |
| Unknown       | 41        | 3%      |
| 1-50          | 34        | 2.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 916       | 75.52%  |
| 2     | 256       | 21.1%   |
| 3     | 35        | 2.89%   |
| 4     | 3         | 0.25%   |
| 0     | 3         | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 696       | 38.65%  |
| Intel                             | 655       | 36.37%  |
| Qualcomm Atheros                  | 135       | 7.5%    |
| MediaTek                          | 70        | 3.89%   |
| Broadcom                          | 55        | 3.05%   |
| ASIX Electronics                  | 21        | 1.17%   |
| TP-Link                           | 17        | 0.94%   |
| Microsoft                         | 13        | 0.72%   |
| Broadcom Limited                  | 13        | 0.72%   |
| D-Link                            | 11        | 0.61%   |
| Sierra Wireless                   | 8         | 0.44%   |
| Ralink                            | 7         | 0.39%   |
| Lenovo                            | 7         | 0.39%   |
| DisplayLink                       | 7         | 0.39%   |
| Aquantia                          | 7         | 0.39%   |
| Ralink Technology                 | 5         | 0.28%   |
| Qualcomm                          | 5         | 0.28%   |
| Marvell Technology Group          | 5         | 0.28%   |
| Samsung Electronics               | 4         | 0.22%   |
| Qualcomm Atheros Communications   | 4         | 0.22%   |
| Huawei Technologies               | 4         | 0.22%   |
| Hewlett-Packard                   | 4         | 0.22%   |
| Google                            | 4         | 0.22%   |
| Cypress Semiconductor             | 4         | 0.22%   |
| Apple                             | 4         | 0.22%   |
| OPPO Electronics                  | 3         | 0.17%   |
| Nvidia                            | 3         | 0.17%   |
| Xiaomi                            | 2         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.11%   |
| Oculus VR                         | 2         | 0.11%   |
| NetGear                           | 2         | 0.11%   |
| Microchip Technology              | 2         | 0.11%   |
| Linksys                           | 2         | 0.11%   |
| ICS Advent                        | 2         | 0.11%   |
| Ericsson Business Mobile Networks | 2         | 0.11%   |
| Wilocity                          | 1         | 0.06%   |
| Quectel Wireless Solutions        | 1         | 0.06%   |
| Qualcomm Technologies             | 1         | 0.06%   |
| Motorola PCS                      | 1         | 0.06%   |
| Mellanox Technologies             | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 469       | 21.92%  |
| Intel Wi-Fi 6 AX200                                               | 103       | 4.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 69        | 3.22%   |
| Intel Wireless 8265 / 8275                                        | 43        | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 42        | 1.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 1.87%   |
| Intel I211 Gigabit Network Connection                             | 40        | 1.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 39        | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 39        | 1.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 37        | 1.73%   |
| Intel Wi-Fi 6 AX201                                               | 33        | 1.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 32        | 1.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 32        | 1.5%    |
| Intel Wireless 7265                                               | 31        | 1.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 28        | 1.31%   |
| Intel Wireless 8260                                               | 24        | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 1.12%   |
| Intel Wireless 7260                                               | 23        | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 1.07%   |
| Intel Wireless-AC 9260                                            | 22        | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 21        | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 20        | 0.93%   |
| Intel Ethernet Controller I225-V                                  | 20        | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 0.93%   |
| Intel Wireless 3165                                               | 19        | 0.89%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 18        | 0.84%   |
| Intel Ethernet Connection (2) I219-V                              | 18        | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 17        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 16        | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 15        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 13        | 0.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.61%   |
| Realtek 802.11ac NIC                                              | 13        | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 13        | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.56%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 11        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 564       | 53.01%  |
| Realtek Semiconductor                 | 184       | 17.29%  |
| Qualcomm Atheros                      | 108       | 10.15%  |
| MediaTek                              | 69        | 6.48%   |
| Broadcom                              | 42        | 3.95%   |
| TP-Link                               | 15        | 1.41%   |
| Microsoft                             | 12        | 1.13%   |
| Broadcom Limited                      | 12        | 1.13%   |
| D-Link                                | 11        | 1.03%   |
| Sierra Wireless                       | 8         | 0.75%   |
| Ralink                                | 7         | 0.66%   |
| Ralink Technology                     | 5         | 0.47%   |
| Qualcomm                              | 5         | 0.47%   |
| Qualcomm Atheros Communications       | 4         | 0.38%   |
| Marvell Technology Group              | 4         | 0.38%   |
| Linksys                               | 2         | 0.19%   |
| Wilocity                              | 1         | 0.09%   |
| Quectel Wireless Solutions            | 1         | 0.09%   |
| Qualcomm Technologies                 | 1         | 0.09%   |
| NetGear                               | 1         | 0.09%   |
| Fibocom                               | 1         | 0.09%   |
| Ericsson Business Mobile Networks     | 1         | 0.09%   |
| Edimax Technology                     | 1         | 0.09%   |
| Dell                                  | 1         | 0.09%   |
| D-Link System                         | 1         | 0.09%   |
| Belkin Components                     | 1         | 0.09%   |
| AVM                                   | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 103       | 9.57%   |
| Intel Wireless 8265 / 8275                                           | 43        | 4%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 39        | 3.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 39        | 3.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 37        | 3.44%   |
| Intel Wi-Fi 6 AX201                                                  | 33        | 3.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 32        | 2.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 32        | 2.97%   |
| Intel Wireless 7265                                                  | 31        | 2.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 27        | 2.51%   |
| Intel Wireless 8260                                                  | 24        | 2.23%   |
| Intel Wireless 7260                                                  | 23        | 2.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 23        | 2.14%   |
| Intel Wireless-AC 9260                                               | 22        | 2.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 21        | 1.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 20        | 1.86%   |
| Intel Wireless 3165                                                  | 19        | 1.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 18        | 1.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 17        | 1.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 16        | 1.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 15        | 1.39%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 15        | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 14        | 1.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 13        | 1.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 13        | 1.21%   |
| Realtek 802.11ac NIC                                                 | 13        | 1.21%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 13        | 1.21%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 11        | 1.02%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 11        | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 11        | 1.02%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 9         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                     | 9         | 0.84%   |
| Intel Wireless 3160                                                  | 9         | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 9         | 0.84%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 9         | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 9         | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 9         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                        | 9         | 0.84%   |
| D-Link 802.11ac NIC                                                  | 8         | 0.74%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                           | 7         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 620       | 60.55%  |
| Intel                         | 263       | 25.68%  |
| Qualcomm Atheros              | 40        | 3.91%   |
| Broadcom                      | 21        | 2.05%   |
| ASIX Electronics              | 21        | 2.05%   |
| DisplayLink                   | 7         | 0.68%   |
| Aquantia                      | 7         | 0.68%   |
| Lenovo                        | 6         | 0.59%   |
| Google                        | 4         | 0.39%   |
| Cypress Semiconductor         | 4         | 0.39%   |
| Apple                         | 4         | 0.39%   |
| Samsung Electronics           | 3         | 0.29%   |
| OPPO Electronics              | 3         | 0.29%   |
| Nvidia                        | 3         | 0.29%   |
| Xiaomi                        | 2         | 0.2%    |
| TP-Link                       | 2         | 0.2%    |
| ICS Advent                    | 2         | 0.2%    |
| D-Link                        | 2         | 0.2%    |
| OnePlus Technology (Shenzhen) | 1         | 0.1%    |
| NetGear                       | 1         | 0.1%    |
| Motorola PCS                  | 1         | 0.1%    |
| Microsoft                     | 1         | 0.1%    |
| Mellanox Technologies         | 1         | 0.1%    |
| MediaTek                      | 1         | 0.1%    |
| Marvell Technology Group      | 1         | 0.1%    |
| Huawei Technologies           | 1         | 0.1%    |
| Hewlett-Packard               | 1         | 0.1%    |
| Broadcom Limited              | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 469       | 44.79%  |
| Realtek RTL8125 2.5GbE Controller                                 | 69        | 6.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 42        | 4.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 40        | 3.82%   |
| Intel I211 Gigabit Network Connection                             | 40        | 3.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 2.29%   |
| Intel Ethernet Controller I225-V                                  | 20        | 1.91%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 1.91%   |
| Intel Ethernet Connection (2) I219-V                              | 18        | 1.72%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 1.72%   |
| Intel Ethernet Connection (7) I219-V                              | 14        | 1.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.96%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.96%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.96%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.57%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 5         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.48%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 0.48%   |
| Intel Ethernet Connection I217-V                                  | 5         | 0.48%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 0.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.38%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.38%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.38%   |
| Cypress K38231_03                                                 | 4         | 0.38%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.38%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.38%   |
| Apple iBridge                                                     | 4         | 0.38%   |
| Realtek PCIe GbE Family Controller                                | 3         | 0.29%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.29%   |
| OPPO RMX2027                                                      | 3         | 0.29%   |
| Intel Ethernet Controller I226-V                                  | 3         | 0.29%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.29%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1001      | 51.05%  |
| Ethernet | 943       | 48.09%  |
| Modem    | 15        | 0.76%   |
| Unknown  | 2         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 811       | 64.26%  |
| Ethernet | 451       | 35.74%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 638       | 53.57%  |
| 1     | 506       | 42.49%  |
| 3     | 36        | 3.02%   |
| 0     | 7         | 0.59%   |
| 4     | 4         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 917       | 75.97%  |
| Yes  | 290       | 24.03%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 510       | 51.88%  |
| Realtek Semiconductor           | 119       | 12.11%  |
| Cambridge Silicon Radio         | 52        | 5.29%   |
| Qualcomm Atheros Communications | 49        | 4.98%   |
| IMC Networks                    | 45        | 4.58%   |
| Foxconn / Hon Hai               | 37        | 3.76%   |
| Broadcom                        | 31        | 3.15%   |
| Lite-On Technology              | 30        | 3.05%   |
| Apple                           | 22        | 2.24%   |
| MediaTek                        | 19        | 1.93%   |
| ASUSTek Computer                | 18        | 1.83%   |
| Realtek                         | 9         | 0.92%   |
| TP-Link                         | 7         | 0.71%   |
| Toshiba                         | 6         | 0.61%   |
| USI                             | 5         | 0.51%   |
| Ralink                          | 4         | 0.41%   |
| Dell                            | 4         | 0.41%   |
| Marvell Semiconductor           | 3         | 0.31%   |
| HTC (High Tech Computer)        | 3         | 0.31%   |
| Hewlett-Packard                 | 3         | 0.31%   |
| Opticis                         | 2         | 0.2%    |
| Foxconn International           | 1         | 0.1%    |
| Edimax Technology               | 1         | 0.1%    |
| Dynex                           | 1         | 0.1%    |
| Alps Electric                   | 1         | 0.1%    |
| Actions                         | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 160       | 16.23%  |
| Intel AX200 Bluetooth                               | 100       | 10.14%  |
| Intel AX201 Bluetooth                               | 88        | 8.92%   |
| Realtek Bluetooth Radio                             | 85        | 8.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 54        | 5.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 52        | 5.27%   |
| Intel Bluetooth Device                              | 36        | 3.65%   |
| Intel AX210 Bluetooth                               | 36        | 3.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 32        | 3.25%   |
| Foxconn / Hon Hai Wireless_Device                   | 25        | 2.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 20        | 2.03%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 20        | 2.03%   |
| MediaTek Wireless_Device                            | 18        | 1.83%   |
| IMC Networks Wireless_Device                        | 18        | 1.83%   |
| IMC Networks Bluetooth Radio                        | 17        | 1.72%   |
| Intel Wireless-AC 3168 Bluetooth                    | 14        | 1.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 1.32%   |
| Apple Bluetooth USB Host Controller                 | 11        | 1.12%   |
| Realtek Bluetooth Radio                             | 9         | 0.91%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 0.81%   |
| TP-Link UB500 Adapter                               | 7         | 0.71%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 7         | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.61%   |
| Lite-On Bluetooth Device                            | 6         | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.61%   |
| Apple Bluetooth Host Controller                     | 6         | 0.61%   |
| USI Bluetooth Device                                | 5         | 0.51%   |
| Realtek RTL8821A Bluetooth                          | 5         | 0.51%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.51%   |
| IMC Networks Bluetooth Device                       | 5         | 0.51%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.51%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.41%   |
| Lite-On Wireless_Device                             | 4         | 0.41%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.3%    |
| Marvell Bluetooth and Wireless LAN Composite        | 3         | 0.3%    |
| Lite-On Bluetooth Radio                             | 3         | 0.3%    |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 733       | 38.54%  |
| AMD                                             | 483       | 25.39%  |
| Nvidia                                          | 335       | 17.61%  |
| C-Media Electronics                             | 39        | 2.05%   |
| Logitech                                        | 28        | 1.47%   |
| SteelSeries ApS                                 | 21        | 1.1%    |
| Texas Instruments                               | 19        | 1%      |
| Kingston Technology                             | 18        | 0.95%   |
| Creative Labs                                   | 13        | 0.68%   |
| Creative Technology                             | 12        | 0.63%   |
| JMTek                                           | 11        | 0.58%   |
| Focusrite-Novation                              | 10        | 0.53%   |
| Corsair                                         | 9         | 0.47%   |
| Sony                                            | 8         | 0.42%   |
| Razer USA                                       | 8         | 0.42%   |
| Blue Microphones                                | 8         | 0.42%   |
| Realtek Semiconductor                           | 7         | 0.37%   |
| Lenovo                                          | 7         | 0.37%   |
| RODE Microphones                                | 6         | 0.32%   |
| Micro Star International                        | 6         | 0.32%   |
| KORG                                            | 6         | 0.32%   |
| Generalplus Technology                          | 6         | 0.32%   |
| XMOS                                            | 5         | 0.26%   |
| Samson Technologies                             | 5         | 0.26%   |
| NAD Electronics                                 | 5         | 0.26%   |
| Apple                                           | 5         | 0.26%   |
| AKAI                                            | 5         | 0.26%   |
| Valve Software                                  | 4         | 0.21%   |
| KTMicro                                         | 3         | 0.16%   |
| Hewlett-Packard                                 | 3         | 0.16%   |
| GYROCOM C&C                                     | 3         | 0.16%   |
| FiiO Electronics Technology                     | 3         | 0.16%   |
| ASUSTek Computer                                | 3         | 0.16%   |
| AKAI Professional M.I.                          | 3         | 0.16%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.11%   |
| Tenx Technology                                 | 2         | 0.11%   |
| Sennheiser Communications                       | 2         | 0.11%   |
| Mark of the Unicorn                             | 2         | 0.11%   |
| M-Audio                                         | 2         | 0.11%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 246       | 10.42%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 137       | 5.81%   |
| Intel Sunrise Point-LP HD Audio                                            | 116       | 4.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 111       | 4.7%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 56        | 2.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 53        | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 50        | 2.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 47        | 1.99%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 47        | 1.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 46        | 1.95%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 41        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 40        | 1.69%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 37        | 1.57%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 35        | 1.48%   |
| Nvidia GA104 High Definition Audio Controller                              | 31        | 1.31%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 31        | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 30        | 1.27%   |
| Nvidia TU106 High Definition Audio Controller                              | 29        | 1.23%   |
| Intel Haswell-ULT HD Audio Controller                                      | 29        | 1.23%   |
| Nvidia GP107GL High Definition Audio Controller                            | 28        | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 25        | 1.06%   |
| Nvidia GA106 High Definition Audio Controller                              | 25        | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 1.06%   |
| AMD Navi 10 HDMI Audio                                                     | 25        | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                               | 24        | 1.02%   |
| Intel Broadwell-U Audio Controller                                         | 24        | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 23        | 0.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 23        | 0.97%   |
| Intel Comet Lake PCH cAVS                                                  | 22        | 0.93%   |
| Intel 200 Series PCH HD Audio                                              | 22        | 0.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 20        | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 19        | 0.81%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 19        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 17        | 0.72%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 17        | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 16        | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 16        | 0.68%   |
| Nvidia Audio device                                                        | 15        | 0.64%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 15        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 275       | 26.39%  |
| SK hynix            | 181       | 17.37%  |
| Micron Technology   | 117       | 11.23%  |
| Kingston            | 90        | 8.64%   |
| Corsair             | 74        | 7.1%    |
| G.Skill             | 72        | 6.91%   |
| Crucial             | 67        | 6.43%   |
| Unknown             | 39        | 3.74%   |
| Ramaxel Technology  | 16        | 1.54%   |
| A-DATA Technology   | 15        | 1.44%   |
| Team                | 13        | 1.25%   |
| Patriot             | 13        | 1.25%   |
| Unknown (ABCD)      | 8         | 0.77%   |
| Elpida              | 8         | 0.77%   |
| Unknown             | 8         | 0.77%   |
| Nanya Technology    | 4         | 0.38%   |
| Kllisre             | 3         | 0.29%   |
| GOODRAM             | 3         | 0.29%   |
| Transcend           | 2         | 0.19%   |
| Teikon              | 2         | 0.19%   |
| Shenzhen Mic        | 2         | 0.19%   |
| Neo Forza           | 2         | 0.19%   |
| Hikvision           | 2         | 0.19%   |
| Golden Empire       | 2         | 0.19%   |
| Apacer              | 2         | 0.19%   |
| Wilk                | 1         | 0.1%    |
| V-GeN               | 1         | 0.1%    |
| Unknown (0x5846)    | 1         | 0.1%    |
| Toshiba             | 1         | 0.1%    |
| Strontium           | 1         | 0.1%    |
| Smart Brazil        | 1         | 0.1%    |
| Smart               | 1         | 0.1%    |
| Silicon Power       | 1         | 0.1%    |
| Sesame              | 1         | 0.1%    |
| Qimonda             | 1         | 0.1%    |
| PNY                 | 1         | 0.1%    |
| MAXSUN              | 1         | 0.1%    |
| Magnum Tech         | 1         | 0.1%    |
| KLEVV               | 1         | 0.1%    |
| Kingmax             | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 20        | 1.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 1.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 14        | 1.25%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.16%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 11        | 0.98%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.89%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 0.89%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.89%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 9         | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 9         | 0.8%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.8%    |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 8         | 0.71%   |
| Unknown                                                          | 8         | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.62%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.62%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.62%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 0.53%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.53%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.53%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 6         | 0.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.45%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 5         | 0.45%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 5         | 0.45%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.45%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 5         | 0.45%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.36%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.36%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.36%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.36%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 555       | 61.67%  |
| DDR3    | 174       | 19.33%  |
| LPDDR4  | 50        | 5.56%   |
| DDR5    | 35        | 3.89%   |
| LPDDR3  | 31        | 3.44%   |
| LPDDR5  | 23        | 2.56%   |
| DDR2    | 15        | 1.67%   |
| SDRAM   | 9         | 1%      |
| Unknown | 7         | 0.78%   |
| DDR     | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 518       | 57.56%  |
| DIMM         | 260       | 28.89%  |
| Row Of Chips | 109       | 12.11%  |
| Chip         | 7         | 0.78%   |
| Unknown      | 4         | 0.44%   |
| RIMM         | 1         | 0.11%   |
| FB-DIMM      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 478       | 48.98%  |
| 4096  | 210       | 21.52%  |
| 16384 | 177       | 18.14%  |
| 2048  | 55        | 5.64%   |
| 32768 | 48        | 4.92%   |
| 1024  | 7         | 0.72%   |
| 49152 | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 246       | 25.2%   |
| 2667    | 151       | 15.47%  |
| 1600    | 135       | 13.83%  |
| 2400    | 56        | 5.74%   |
| 3600    | 49        | 5.02%   |
| 2133    | 45        | 4.61%   |
| 4800    | 25        | 2.56%   |
| 3266    | 25        | 2.56%   |
| 6400    | 24        | 2.46%   |
| 1333    | 24        | 2.46%   |
| 1867    | 22        | 2.25%   |
| 4267    | 20        | 2.05%   |
| 3733    | 16        | 1.64%   |
| 1334    | 11        | 1.13%   |
| 3533    | 9         | 0.92%   |
| 3400    | 8         | 0.82%   |
| 3800    | 7         | 0.72%   |
| 800     | 7         | 0.72%   |
| 667     | 7         | 0.72%   |
| 3866    | 6         | 0.61%   |
| Unknown | 6         | 0.61%   |
| 3000    | 5         | 0.51%   |
| 1800    | 5         | 0.51%   |
| 5600    | 4         | 0.41%   |
| 4266    | 4         | 0.41%   |
| 2933    | 4         | 0.41%   |
| 2666    | 4         | 0.41%   |
| 1067    | 4         | 0.41%   |
| 6000    | 3         | 0.31%   |
| 3500    | 3         | 0.31%   |
| 2800    | 3         | 0.31%   |
| 2048    | 3         | 0.31%   |
| 1066    | 3         | 0.31%   |
| 4000    | 2         | 0.2%    |
| 3666    | 2         | 0.2%    |
| 3534    | 2         | 0.2%    |
| 3466    | 2         | 0.2%    |
| 2733    | 2         | 0.2%    |
| 1648    | 2         | 0.2%    |
| 65535   | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 6         | 30%     |
| Hewlett-Packard     | 5         | 25%     |
| Xerox               | 2         | 10%     |
| Prolific Technology | 2         | 10%     |
| Canon               | 2         | 10%     |
| Seiko Epson         | 1         | 5%      |
| Samsung Electronics | 1         | 5%      |
| Pantum              | 1         | 5%      |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Xerox B210                    | 2         | 10%     |
| Prolific PL2305 Parallel Port | 2         | 10%     |
| Seiko Epson WF-2010 Series    | 1         | 5%      |
| Samsung M2020 Series          | 1         | 5%      |
| Pantum P2500W series          | 1         | 5%      |
| HP OfficeJet Pro 8020 series  | 1         | 5%      |
| HP ENVY 5540 series           | 1         | 5%      |
| HP ENVY 5000 series           | 1         | 5%      |
| HP DeskJet 2130 series        | 1         | 5%      |
| HP ColorLaserJet M253-M254    | 1         | 5%      |
| Canon PIXMA MG2500 Series     | 1         | 5%      |
| Canon MF260 II Series         | 1         | 5%      |
| Brother Printer               | 1         | 5%      |
| Brother MFC-L2710DW series    | 1         | 5%      |
| Brother MFC-J4535DW           | 1         | 5%      |
| Brother HL-2130 series        | 1         | 5%      |
| Brother DCP-9020CDW           | 1         | 5%      |
| Brother DCP-9015CDW           | 1         | 5%      |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 151       | 17.89%  |
| IMC Networks                           | 114       | 13.51%  |
| Logitech                               | 68        | 8.06%   |
| Bison Electronics                      | 59        | 6.99%   |
| Microdia                               | 57        | 6.75%   |
| Quanta                                 | 44        | 5.21%   |
| Realtek Semiconductor                  | 37        | 4.38%   |
| Sunplus Innovation Technology          | 35        | 4.15%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 4.15%   |
| Apple                                  | 30        | 3.55%   |
| Syntek                                 | 28        | 3.32%   |
| Lite-On Technology                     | 26        | 3.08%   |
| Luxvisions Innotech Limited            | 22        | 2.61%   |
| Acer                                   | 15        | 1.78%   |
| Sonix Technology                       | 13        | 1.54%   |
| Microsoft                              | 12        | 1.42%   |
| Suyin                                  | 8         | 0.95%   |
| Samsung Electronics                    | 6         | 0.71%   |
| MacroSilicon                           | 5         | 0.59%   |
| Hewlett-Packard                        | 5         | 0.59%   |
| Valve Software                         | 4         | 0.47%   |
| Silicon Motion                         | 4         | 0.47%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.47%   |
| Lenovo                                 | 4         | 0.47%   |
| Google                                 | 4         | 0.47%   |
| Alcor Micro                            | 4         | 0.47%   |
| Primax Electronics                     | 3         | 0.36%   |
| GEMBIRD                                | 3         | 0.36%   |
| Trust                                  | 2         | 0.24%   |
| Shinetech                              | 2         | 0.24%   |
| Ricoh                                  | 2         | 0.24%   |
| LG Electronics                         | 2         | 0.24%   |
| KYE Systems (Mouse Systems)            | 2         | 0.24%   |
| Intel                                  | 2         | 0.24%   |
| Huawei Technologies                    | 2         | 0.24%   |
| Generalplus Technology                 | 2         | 0.24%   |
| DLTDC0A9II090N                         | 2         | 0.24%   |
| Creative Technology                    | 2         | 0.24%   |
| Y Media                                | 1         | 0.12%   |
| Xiaomi                                 | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 49        | 5.76%   |
| IMC Networks Integrated Camera                       | 45        | 5.29%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 40        | 4.71%   |
| Microdia Integrated_Webcam_HD                        | 21        | 2.47%   |
| Chicony HD WebCam                                    | 20        | 2.35%   |
| Syntek Integrated Camera                             | 18        | 2.12%   |
| Logitech HD Pro Webcam C920                          | 17        | 2%      |
| Bison Integrated Camera                              | 16        | 1.88%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 15        | 1.76%   |
| Realtek Integrated_Webcam_HD                         | 14        | 1.65%   |
| Bison HD Webcam                                      | 13        | 1.53%   |
| Logitech Webcam C270                                 | 11        | 1.29%   |
| Acer Integrated Camera                               | 11        | 1.29%   |
| Apple FaceTime HD Camera (Built-in)                  | 10        | 1.18%   |
| Sonix USB2.0 HD UVC WebCam                           | 9         | 1.06%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 9         | 1.06%   |
| Sunplus Integrated_Webcam_HD                         | 8         | 0.94%   |
| Quanta USB2.0 HD UVC WebCam                          | 8         | 0.94%   |
| Microdia Webcam Vitade AF                            | 8         | 0.94%   |
| Sunplus HD WebCam                                    | 7         | 0.82%   |
| Quanta HP TrueVision HD Camera                       | 7         | 0.82%   |
| Logitech C922 Pro Stream Webcam                      | 7         | 0.82%   |
| Lite-On Integrated Camera                            | 7         | 0.82%   |
| Chicony HP Wide Vision HD Camera                     | 7         | 0.82%   |
| Samsung Galaxy series, misc. (MTP mode)              | 6         | 0.71%   |
| Quanta HP HD Camera                                  | 6         | 0.71%   |
| Quanta HD Camera                                     | 6         | 0.71%   |
| Microdia USB 2.0 Camera                              | 6         | 0.71%   |
| Microdia Integrated Webcam                           | 6         | 0.71%   |
| Chicony USB2.0 HD UVC WebCam                         | 6         | 0.71%   |
| Chicony HD User Facing                               | 6         | 0.71%   |
| Bison EasyCamera                                     | 6         | 0.71%   |
| Bison BisonCam,NB Pro                                | 6         | 0.71%   |
| Syntek EasyCamera                                    | 5         | 0.59%   |
| Microsoft LifeCam HD-3000                            | 5         | 0.59%   |
| MacroSilicon USB Video                               | 5         | 0.59%   |
| Luxvisions Innotech Limited Integrated Camera        | 5         | 0.59%   |
| Logitech C920 PRO HD Webcam                          | 5         | 0.59%   |
| Lite-On HP Webcam                                    | 5         | 0.59%   |
| Lite-On HP HD Camera                                 | 5         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 57        | 36.77%  |
| Validity Sensors                   | 37        | 23.87%  |
| Shenzhen Goodix Technology         | 26        | 16.77%  |
| Elan Microelectronics              | 19        | 12.26%  |
| LighTuning Technology              | 6         | 3.87%   |
| Upek                               | 3         | 1.94%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.94%   |
| Samsung Electronics                | 2         | 1.29%   |
| AuthenTec                          | 2         | 1.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 9.68%   |
| Shenzhen Goodix  FingerPrint Device                                        | 14        | 9.03%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 7.74%   |
| Elan ELAN:Fingerprint                                                      | 11        | 7.1%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 5.81%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 5.16%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 5.16%   |
| Synaptics  WBDI                                                            | 8         | 5.16%   |
| Elan ELAN:ARM-M4                                                           | 8         | 5.16%   |
| Synaptics WBDI                                                             | 6         | 3.87%   |
| Synaptics UWP WBDI                                                         | 5         | 3.23%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.23%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.58%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 2.58%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.94%   |
| Validity Sensors VFS491                                                    | 3         | 1.94%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.94%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 1.94%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 1.94%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.94%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.94%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.29%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.29%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 1.29%   |
| Unknown                                                                    | 2         | 1.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.65%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.65%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.65%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.65%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.65%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.65%   |
| AuthenTec AES2810                                                          | 1         | 0.65%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.65%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 24        | 50%     |
| Alcor Micro | 16        | 33.33%  |
| Lenovo      | 3         | 6.25%   |
| Upek        | 2         | 4.17%   |
| O2 Micro    | 2         | 4.17%   |
| HID Global  | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 30.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 20.41%  |
| Broadcom 5880                                                                | 6         | 12.24%  |
| Broadcom 58200                                                               | 6         | 12.24%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.12%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.12%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.08%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.08%   |
| HID Global USB Reader V3                                                     | 1         | 2.04%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.04%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 828       | 68.15%  |
| 1     | 325       | 26.75%  |
| 2     | 57        | 4.69%   |
| 3     | 3         | 0.25%   |
| 8     | 1         | 0.08%   |
| 4     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 155       | 35.47%  |
| Multimedia controller    | 51        | 11.67%  |
| Net/ethernet             | 50        | 11.44%  |
| Chipcard                 | 46        | 10.53%  |
| Graphics card            | 41        | 9.38%   |
| Net/wireless             | 34        | 7.78%   |
| Camera                   | 18        | 4.12%   |
| Bluetooth                | 13        | 2.97%   |
| Network                  | 7         | 1.6%    |
| Unassigned class         | 4         | 0.92%   |
| Storage                  | 3         | 0.69%   |
| Sound                    | 3         | 0.69%   |
| Dvb card                 | 3         | 0.69%   |
| Storage/nvme             | 2         | 0.46%   |
| Communication controller | 2         | 0.46%   |
| Card reader              | 2         | 0.46%   |
| Storage/raid             | 1         | 0.23%   |
| Storage/ata              | 1         | 0.23%   |
| Modem                    | 1         | 0.23%   |

