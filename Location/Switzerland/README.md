Linux in Switzerland - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Switzerland/Desktop/README.md) and [notebooks](/Location/Switzerland/Notebook/README.md).

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

Total: 3527

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [c71241f73d](https://linux-hardware.org/?probe=c71241f73d) | Oct 01, 2023 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [b1af5494c8](https://linux-hardware.org/?probe=b1af5494c8) | Oct 01, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [34e5bf82de](https://linux-hardware.org/?probe=34e5bf82de) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [d8c97108ad](https://linux-hardware.org/?probe=d8c97108ad) | Sep 30, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [bcbf0e5bfd](https://linux-hardware.org/?probe=bcbf0e5bfd) | Sep 30, 2023 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [caa5ce0b99](https://linux-hardware.org/?probe=caa5ce0b99) | Sep 29, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [725f1e5b25](https://linux-hardware.org/?probe=725f1e5b25) | Sep 29, 2023 |
| TUXEDO        | Stellaris Intel Gen5        | Notebook    | [6d981e4890](https://linux-hardware.org/?probe=6d981e4890) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [47a0a8627c](https://linux-hardware.org/?probe=47a0a8627c) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [3fcfddc8e9](https://linux-hardware.org/?probe=3fcfddc8e9) | Sep 27, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [af863ee3d6](https://linux-hardware.org/?probe=af863ee3d6) | Sep 27, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [e8397f6d0a](https://linux-hardware.org/?probe=e8397f6d0a) | Sep 26, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [5351027f5e](https://linux-hardware.org/?probe=5351027f5e) | Sep 25, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [a34763914d](https://linux-hardware.org/?probe=a34763914d) | Sep 23, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f2bb4ee9f0](https://linux-hardware.org/?probe=f2bb4ee9f0) | Sep 23, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [f1721712f2](https://linux-hardware.org/?probe=f1721712f2) | Sep 22, 2023 |
| Gigabyte      | P55-UD4                     | Desktop     | [16f768ab94](https://linux-hardware.org/?probe=16f768ab94) | Sep 21, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [34d899f825](https://linux-hardware.org/?probe=34d899f825) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [8b39e51416](https://linux-hardware.org/?probe=8b39e51416) | Sep 21, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [b1fd4a61ae](https://linux-hardware.org/?probe=b1fd4a61ae) | Sep 21, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [389282109e](https://linux-hardware.org/?probe=389282109e) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [ae7455bac3](https://linux-hardware.org/?probe=ae7455bac3) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [6337af2f4c](https://linux-hardware.org/?probe=6337af2f4c) | Sep 20, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e04968b0ab](https://linux-hardware.org/?probe=e04968b0ab) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [16c09be7f2](https://linux-hardware.org/?probe=16c09be7f2) | Sep 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [16f80f70a8](https://linux-hardware.org/?probe=16f80f70a8) | Sep 19, 2023 |
| Lenovo        | ThinkPad X61s 7666Y2X       | Notebook    | [177e40808d](https://linux-hardware.org/?probe=177e40808d) | Sep 19, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [49963f0f8a](https://linux-hardware.org/?probe=49963f0f8a) | Sep 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [06d67bab4a](https://linux-hardware.org/?probe=06d67bab4a) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [0c21583146](https://linux-hardware.org/?probe=0c21583146) | Sep 17, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2b66c2969e](https://linux-hardware.org/?probe=2b66c2969e) | Sep 17, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [5a9f4e8791](https://linux-hardware.org/?probe=5a9f4e8791) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | Notebook    | [93d01648a0](https://linux-hardware.org/?probe=93d01648a0) | Sep 17, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1f152eb6fa](https://linux-hardware.org/?probe=1f152eb6fa) | Sep 17, 2023 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [38a985d781](https://linux-hardware.org/?probe=38a985d781) | Sep 16, 2023 |
| JINGSHA       | X99-D8I                     | Desktop     | [2865a9b1e6](https://linux-hardware.org/?probe=2865a9b1e6) | Sep 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [1b8a46fc57](https://linux-hardware.org/?probe=1b8a46fc57) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [1400ef978f](https://linux-hardware.org/?probe=1400ef978f) | Sep 12, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [6b9804a536](https://linux-hardware.org/?probe=6b9804a536) | Sep 10, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [86f844f512](https://linux-hardware.org/?probe=86f844f512) | Sep 10, 2023 |
| ASUSTek       | ROG STRIX TRX40-E GAMING    | Desktop     | [0562141e37](https://linux-hardware.org/?probe=0562141e37) | Sep 10, 2023 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [d824341957](https://linux-hardware.org/?probe=d824341957) | Sep 10, 2023 |
| Olivetti      | OLIBOOK PX5-XXXAES          | Notebook    | [70225c18e1](https://linux-hardware.org/?probe=70225c18e1) | Sep 10, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [bb0f6ff00d](https://linux-hardware.org/?probe=bb0f6ff00d) | Sep 09, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [4a63a68d47](https://linux-hardware.org/?probe=4a63a68d47) | Sep 09, 2023 |
| Microsoft     | Surface Laptop 2            | Tablet      | [e74f5bd967](https://linux-hardware.org/?probe=e74f5bd967) | Sep 09, 2023 |
| HP            | 2B36                        | Desktop     | [20552523c6](https://linux-hardware.org/?probe=20552523c6) | Sep 08, 2023 |
| HP            | 2B36                        | Desktop     | [7697b6ff27](https://linux-hardware.org/?probe=7697b6ff27) | Sep 08, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [86ea72cfeb](https://linux-hardware.org/?probe=86ea72cfeb) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [0de4c341fa](https://linux-hardware.org/?probe=0de4c341fa) | Sep 07, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [d3996a81e2](https://linux-hardware.org/?probe=d3996a81e2) | Sep 07, 2023 |
| HP            | 2B3C                        | Desktop     | [471f0f283b](https://linux-hardware.org/?probe=471f0f283b) | Sep 06, 2023 |
| Lenovo        | Yoga Slim 7 14APU8 83AA     | Notebook    | [b884752710](https://linux-hardware.org/?probe=b884752710) | Sep 06, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [1056a6ebb4](https://linux-hardware.org/?probe=1056a6ebb4) | Sep 06, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [051fefc7ca](https://linux-hardware.org/?probe=051fefc7ca) | Sep 05, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [a28608cf93](https://linux-hardware.org/?probe=a28608cf93) | Sep 04, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [ce450a1a6e](https://linux-hardware.org/?probe=ce450a1a6e) | Sep 03, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Convertible | [e446721809](https://linux-hardware.org/?probe=e446721809) | Sep 02, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [aab4c37d85](https://linux-hardware.org/?probe=aab4c37d85) | Sep 02, 2023 |
| HP            | Compaq 15                   | Notebook    | [2d0b51ccd5](https://linux-hardware.org/?probe=2d0b51ccd5) | Sep 01, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [25b3fed672](https://linux-hardware.org/?probe=25b3fed672) | Aug 31, 2023 |
| Lenovo        | ThinkPad X200 7458AL7       | Notebook    | [763d0f46f4](https://linux-hardware.org/?probe=763d0f46f4) | Aug 31, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [1c5a7bba51](https://linux-hardware.org/?probe=1c5a7bba51) | Aug 31, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [48fe841736](https://linux-hardware.org/?probe=48fe841736) | Aug 30, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3f2dec6262](https://linux-hardware.org/?probe=3f2dec6262) | Aug 30, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [ca4ddb2663](https://linux-hardware.org/?probe=ca4ddb2663) | Aug 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [176ad353fa](https://linux-hardware.org/?probe=176ad353fa) | Aug 29, 2023 |
| HP            | 8953                        | Desktop     | [7f0a271e35](https://linux-hardware.org/?probe=7f0a271e35) | Aug 29, 2023 |
| HP            | 82A2                        | Desktop     | [44e0a72dad](https://linux-hardware.org/?probe=44e0a72dad) | Aug 28, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [fe9f235c26](https://linux-hardware.org/?probe=fe9f235c26) | Aug 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [efc8be8369](https://linux-hardware.org/?probe=efc8be8369) | Aug 28, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [d238cd036a](https://linux-hardware.org/?probe=d238cd036a) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [492a021411](https://linux-hardware.org/?probe=492a021411) | Aug 27, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [0f05e92358](https://linux-hardware.org/?probe=0f05e92358) | Aug 27, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [248f2a9745](https://linux-hardware.org/?probe=248f2a9745) | Aug 27, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d76b06bfd3](https://linux-hardware.org/?probe=d76b06bfd3) | Aug 27, 2023 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [c1bea53459](https://linux-hardware.org/?probe=c1bea53459) | Aug 27, 2023 |
| ASUSTek       | M3N WS                      | Desktop     | [da41c8a755](https://linux-hardware.org/?probe=da41c8a755) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [14805d08fd](https://linux-hardware.org/?probe=14805d08fd) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [f4af40c36f](https://linux-hardware.org/?probe=f4af40c36f) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [08efa3dcf3](https://linux-hardware.org/?probe=08efa3dcf3) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [131e36d487](https://linux-hardware.org/?probe=131e36d487) | Aug 22, 2023 |
| Gigabyte      | MZA2-CE0-00 02010201        | Server      | [853b026197](https://linux-hardware.org/?probe=853b026197) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [f280fd203e](https://linux-hardware.org/?probe=f280fd203e) | Aug 21, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7a5bd0f1a6](https://linux-hardware.org/?probe=7a5bd0f1a6) | Aug 19, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a75b18f36c](https://linux-hardware.org/?probe=a75b18f36c) | Aug 19, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [d3aac86eac](https://linux-hardware.org/?probe=d3aac86eac) | Aug 16, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [7032d8da96](https://linux-hardware.org/?probe=7032d8da96) | Aug 16, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [013756c475](https://linux-hardware.org/?probe=013756c475) | Aug 16, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [9f04bd8095](https://linux-hardware.org/?probe=9f04bd8095) | Aug 16, 2023 |
| HP            | EliteBook x360 830 G8 No... | Convertible | [8e409a97d7](https://linux-hardware.org/?probe=8e409a97d7) | Aug 15, 2023 |
| ASRock        | EP2C602                     | Desktop     | [26c37b5dfa](https://linux-hardware.org/?probe=26c37b5dfa) | Aug 15, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9825a49641](https://linux-hardware.org/?probe=9825a49641) | Aug 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [25aaeea069](https://linux-hardware.org/?probe=25aaeea069) | Aug 15, 2023 |
| Alienware     | 0XJKKD A01                  | Desktop     | [1b0f880002](https://linux-hardware.org/?probe=1b0f880002) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [37086c4564](https://linux-hardware.org/?probe=37086c4564) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [ed6e0727b2](https://linux-hardware.org/?probe=ed6e0727b2) | Aug 14, 2023 |
| ASRock        | EP2C602                     | Desktop     | [c152c5a2f9](https://linux-hardware.org/?probe=c152c5a2f9) | Aug 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [fe5f1d5c1b](https://linux-hardware.org/?probe=fe5f1d5c1b) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [1d5206dc94](https://linux-hardware.org/?probe=1d5206dc94) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bcda0258e5](https://linux-hardware.org/?probe=bcda0258e5) | Aug 12, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| Intel         | D915GEV AAC63667-501        | Desktop     | [4d65f6d8fa](https://linux-hardware.org/?probe=4d65f6d8fa) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [92fda27219](https://linux-hardware.org/?probe=92fda27219) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [3bd085d1a5](https://linux-hardware.org/?probe=3bd085d1a5) | Aug 10, 2023 |
| HP            | 8433 11                     | Desktop     | [eac08c7b54](https://linux-hardware.org/?probe=eac08c7b54) | Aug 09, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [b97d54f6d8](https://linux-hardware.org/?probe=b97d54f6d8) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [11cf6b0c98](https://linux-hardware.org/?probe=11cf6b0c98) | Aug 09, 2023 |
| GPD           | P2 MAX                      | Notebook    | [064bc78973](https://linux-hardware.org/?probe=064bc78973) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [1e3f49e3a0](https://linux-hardware.org/?probe=1e3f49e3a0) | Aug 09, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [2f32ca43ee](https://linux-hardware.org/?probe=2f32ca43ee) | Aug 09, 2023 |
| HP            | 894D                        | Desktop     | [e1c397df93](https://linux-hardware.org/?probe=e1c397df93) | Aug 09, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [62889fd683](https://linux-hardware.org/?probe=62889fd683) | Aug 08, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [cb5a99b4fb](https://linux-hardware.org/?probe=cb5a99b4fb) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [6c24c9f7a9](https://linux-hardware.org/?probe=6c24c9f7a9) | Aug 05, 2023 |
| HP            | 87A4 10100                  | All in one  | [ac3d0deece](https://linux-hardware.org/?probe=ac3d0deece) | Aug 05, 2023 |
| HP            | 87A4 10100                  | All in one  | [1dac28eee7](https://linux-hardware.org/?probe=1dac28eee7) | Aug 05, 2023 |
| AZW           | GTR V02                     | Desktop     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| HP            | 2AF7                        | Desktop     | [655c896815](https://linux-hardware.org/?probe=655c896815) | Aug 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [e7810a04a9](https://linux-hardware.org/?probe=e7810a04a9) | Aug 04, 2023 |
| Dell          | XPS 9320                    | Notebook    | [140f8f8b2e](https://linux-hardware.org/?probe=140f8f8b2e) | Aug 04, 2023 |
| HP            | 87A4 10100                  | All in one  | [a62908af95](https://linux-hardware.org/?probe=a62908af95) | Aug 04, 2023 |
| HP            | 87A4 10100                  | All in one  | [eb7ae8bbb2](https://linux-hardware.org/?probe=eb7ae8bbb2) | Aug 04, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [0839bbc721](https://linux-hardware.org/?probe=0839bbc721) | Aug 03, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| HP            | 843E                        | Desktop     | [dbbfb83ae4](https://linux-hardware.org/?probe=dbbfb83ae4) | Aug 03, 2023 |
| HP            | 843E                        | Desktop     | [952db006c3](https://linux-hardware.org/?probe=952db006c3) | Aug 03, 2023 |
| Dell          | Latitude E6330              | Notebook    | [75d54a8988](https://linux-hardware.org/?probe=75d54a8988) | Aug 03, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [5bbbd1f3d4](https://linux-hardware.org/?probe=5bbbd1f3d4) | Aug 02, 2023 |
| Schenker      | XMG FOCUS (Mid 2021)        | Notebook    | [d7fa14789f](https://linux-hardware.org/?probe=d7fa14789f) | Aug 01, 2023 |
| ASUSTek       | Vivobook ASUSLaptop TP34... | Convertible | [3efa8549a5](https://linux-hardware.org/?probe=3efa8549a5) | Aug 01, 2023 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [b298625640](https://linux-hardware.org/?probe=b298625640) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [25dd387c2c](https://linux-hardware.org/?probe=25dd387c2c) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [7f5c70c059](https://linux-hardware.org/?probe=7f5c70c059) | Aug 01, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [49a431c092](https://linux-hardware.org/?probe=49a431c092) | Jul 31, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [add6831dcd](https://linux-hardware.org/?probe=add6831dcd) | Jul 31, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [7cb3479a69](https://linux-hardware.org/?probe=7cb3479a69) | Jul 31, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [beea8be008](https://linux-hardware.org/?probe=beea8be008) | Jul 30, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [80b81f5eff](https://linux-hardware.org/?probe=80b81f5eff) | Jul 30, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [5518dab193](https://linux-hardware.org/?probe=5518dab193) | Jul 29, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [aef96d4eb8](https://linux-hardware.org/?probe=aef96d4eb8) | Jul 29, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [1006fe2c7b](https://linux-hardware.org/?probe=1006fe2c7b) | Jul 29, 2023 |
| HP            | Elite Dragonfly             | Convertible | [a44424e066](https://linux-hardware.org/?probe=a44424e066) | Jul 28, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [86d9ab8b73](https://linux-hardware.org/?probe=86d9ab8b73) | Jul 28, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [6ea424234a](https://linux-hardware.org/?probe=6ea424234a) | Jul 28, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [9c8b9571d9](https://linux-hardware.org/?probe=9c8b9571d9) | Jul 27, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | Notebook    | [03152e1c57](https://linux-hardware.org/?probe=03152e1c57) | Jul 26, 2023 |
| Acer          | Elena                       | Desktop     | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [45e8471971](https://linux-hardware.org/?probe=45e8471971) | Jul 26, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [5693ac5e4c](https://linux-hardware.org/?probe=5693ac5e4c) | Jul 25, 2023 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [9fbb932f79](https://linux-hardware.org/?probe=9fbb932f79) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [a326770d26](https://linux-hardware.org/?probe=a326770d26) | Jul 25, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [47fec524e4](https://linux-hardware.org/?probe=47fec524e4) | Jul 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [dc537ae22a](https://linux-hardware.org/?probe=dc537ae22a) | Jul 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [cff40caac1](https://linux-hardware.org/?probe=cff40caac1) | Jul 24, 2023 |
| Dell          | Latitude 7480               | Notebook    | [acad753aa8](https://linux-hardware.org/?probe=acad753aa8) | Jul 23, 2023 |
| ASUSTek       | PRIME B650M-A WIFI II       | Desktop     | [f2e2436cf1](https://linux-hardware.org/?probe=f2e2436cf1) | Jul 23, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [d387ed9d0c](https://linux-hardware.org/?probe=d387ed9d0c) | Jul 22, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [ff6179199d](https://linux-hardware.org/?probe=ff6179199d) | Jul 22, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [988a5f870c](https://linux-hardware.org/?probe=988a5f870c) | Jul 21, 2023 |
| ASUSTek       | G551JK                      | Notebook    | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a8f79a71f7](https://linux-hardware.org/?probe=a8f79a71f7) | Jul 20, 2023 |
| Acer          | Predator PH317-56           | Notebook    | [248af0e35c](https://linux-hardware.org/?probe=248af0e35c) | Jul 18, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [b3d68108a2](https://linux-hardware.org/?probe=b3d68108a2) | Jul 18, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [fbb58d4f7c](https://linux-hardware.org/?probe=fbb58d4f7c) | Jul 18, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [f62d1b0d14](https://linux-hardware.org/?probe=f62d1b0d14) | Jul 17, 2023 |
| HP            | Pavilion dm1                | Notebook    | [135bb20fbd](https://linux-hardware.org/?probe=135bb20fbd) | Jul 17, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [798ddca1c4](https://linux-hardware.org/?probe=798ddca1c4) | Jul 16, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [236c9f5565](https://linux-hardware.org/?probe=236c9f5565) | Jul 14, 2023 |
| HP            | Pavilion dm1                | Notebook    | [3b05c5dc5c](https://linux-hardware.org/?probe=3b05c5dc5c) | Jul 14, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [d017610254](https://linux-hardware.org/?probe=d017610254) | Jul 14, 2023 |
| Dell          | 0WC7KF A00                  | All in one  | [71309341ec](https://linux-hardware.org/?probe=71309341ec) | Jul 13, 2023 |
| HP            | 83DD                        | Mini pc     | [38e991673e](https://linux-hardware.org/?probe=38e991673e) | Jul 12, 2023 |
| Dell          | XPS 12 9Q23                 | Notebook    | [5fb9db838e](https://linux-hardware.org/?probe=5fb9db838e) | Jul 12, 2023 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [fdde43af89](https://linux-hardware.org/?probe=fdde43af89) | Jul 11, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [6d76fdbcd6](https://linux-hardware.org/?probe=6d76fdbcd6) | Jul 10, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [9fd763e236](https://linux-hardware.org/?probe=9fd763e236) | Jul 09, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [b44c0d94f4](https://linux-hardware.org/?probe=b44c0d94f4) | Jul 09, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [61da77f999](https://linux-hardware.org/?probe=61da77f999) | Jul 09, 2023 |
| Medion        | MS-7667                     | Desktop     | [52ff08b634](https://linux-hardware.org/?probe=52ff08b634) | Jul 09, 2023 |
| Lenovo        | ThinkPad T470p 20J6003DG... | Notebook    | [a7632f8c4b](https://linux-hardware.org/?probe=a7632f8c4b) | Jul 09, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [9b8d05afca](https://linux-hardware.org/?probe=9b8d05afca) | Jul 08, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e0e1896cc3](https://linux-hardware.org/?probe=e0e1896cc3) | Jul 07, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [3908772779](https://linux-hardware.org/?probe=3908772779) | Jul 07, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [8da6cc6879](https://linux-hardware.org/?probe=8da6cc6879) | Jul 07, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Notebook    | [4ff583eb14](https://linux-hardware.org/?probe=4ff583eb14) | Jul 05, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [80ed1496a1](https://linux-hardware.org/?probe=80ed1496a1) | Jul 05, 2023 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [530d25db12](https://linux-hardware.org/?probe=530d25db12) | Jul 03, 2023 |
| TUXEDO        | InfinityBook 14 v2          | Notebook    | [9447ac0693](https://linux-hardware.org/?probe=9447ac0693) | Jul 02, 2023 |
| HP            | 8918                        | Desktop     | [da7b695c7b](https://linux-hardware.org/?probe=da7b695c7b) | Jul 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [277a9bb8e4](https://linux-hardware.org/?probe=277a9bb8e4) | Jul 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d772da19a0](https://linux-hardware.org/?probe=d772da19a0) | Jun 30, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [566b883024](https://linux-hardware.org/?probe=566b883024) | Jun 30, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [921821fda8](https://linux-hardware.org/?probe=921821fda8) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3c1007547d](https://linux-hardware.org/?probe=3c1007547d) | Jun 30, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [1e33cadd37](https://linux-hardware.org/?probe=1e33cadd37) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ad91997e3e](https://linux-hardware.org/?probe=ad91997e3e) | Jun 28, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [7f5dfae0db](https://linux-hardware.org/?probe=7f5dfae0db) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [8619447305](https://linux-hardware.org/?probe=8619447305) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [bddefdfb2c](https://linux-hardware.org/?probe=bddefdfb2c) | Jun 27, 2023 |
| Unknown       | Unknown                     | Soc         | [baebeebbdb](https://linux-hardware.org/?probe=baebeebbdb) | Jun 27, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [731b4a6479](https://linux-hardware.org/?probe=731b4a6479) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Star Labs     | LabTop                      | Notebook    | [a413031ef8](https://linux-hardware.org/?probe=a413031ef8) | Jun 25, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [66f2fbfdf4](https://linux-hardware.org/?probe=66f2fbfdf4) | Jun 25, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [32ab15a1eb](https://linux-hardware.org/?probe=32ab15a1eb) | Jun 25, 2023 |
| Acer          | Aspire F5-571G              | Notebook    | [fb61026d60](https://linux-hardware.org/?probe=fb61026d60) | Jun 25, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | Notebook    | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [cb554fb8f8](https://linux-hardware.org/?probe=cb554fb8f8) | Jun 24, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [f8dee044e2](https://linux-hardware.org/?probe=f8dee044e2) | Jun 24, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [24db241d7a](https://linux-hardware.org/?probe=24db241d7a) | Jun 22, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [23ea485e5e](https://linux-hardware.org/?probe=23ea485e5e) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [d607d3c598](https://linux-hardware.org/?probe=d607d3c598) | Jun 22, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [8518224d34](https://linux-hardware.org/?probe=8518224d34) | Jun 21, 2023 |
| Lenovo        | ThinkPad L380 20M50011MZ    | Notebook    | [223c8d15d4](https://linux-hardware.org/?probe=223c8d15d4) | Jun 21, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [186a21a6f7](https://linux-hardware.org/?probe=186a21a6f7) | Jun 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f008d4c0db](https://linux-hardware.org/?probe=f008d4c0db) | Jun 19, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [953a81c579](https://linux-hardware.org/?probe=953a81c579) | Jun 19, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e9865c622f](https://linux-hardware.org/?probe=e9865c622f) | Jun 19, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [90720c3820](https://linux-hardware.org/?probe=90720c3820) | Jun 18, 2023 |
| Lenovo        | ThinkPad E580 20KS001JMZ    | Notebook    | [780d549a32](https://linux-hardware.org/?probe=780d549a32) | Jun 18, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4b184d1037](https://linux-hardware.org/?probe=4b184d1037) | Jun 18, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [c45597704a](https://linux-hardware.org/?probe=c45597704a) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a312151081](https://linux-hardware.org/?probe=a312151081) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [7d329c0bee](https://linux-hardware.org/?probe=7d329c0bee) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [acf5c5a440](https://linux-hardware.org/?probe=acf5c5a440) | Jun 14, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [467be092e4](https://linux-hardware.org/?probe=467be092e4) | Jun 14, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [8ea9d60a21](https://linux-hardware.org/?probe=8ea9d60a21) | Jun 12, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [794030a707](https://linux-hardware.org/?probe=794030a707) | Jun 12, 2023 |
| Lenovo        | ThinkPad T420s 4175A16      | Notebook    | [3d23465019](https://linux-hardware.org/?probe=3d23465019) | Jun 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [ec6af41f13](https://linux-hardware.org/?probe=ec6af41f13) | Jun 11, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | Notebook    | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [6adee93e47](https://linux-hardware.org/?probe=6adee93e47) | Jun 10, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [08a506ad4e](https://linux-hardware.org/?probe=08a506ad4e) | Jun 09, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [15185698e7](https://linux-hardware.org/?probe=15185698e7) | Jun 09, 2023 |
| ASUSTek       | P8P67 LE                    | Desktop     | [212ff65852](https://linux-hardware.org/?probe=212ff65852) | Jun 09, 2023 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [7346eaf346](https://linux-hardware.org/?probe=7346eaf346) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [45ee697eed](https://linux-hardware.org/?probe=45ee697eed) | Jun 07, 2023 |
| HP            | 2B36                        | Desktop     | [0f36ecaa7e](https://linux-hardware.org/?probe=0f36ecaa7e) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [f70195a177](https://linux-hardware.org/?probe=f70195a177) | Jun 07, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | Notebook    | [7d33fb0564](https://linux-hardware.org/?probe=7d33fb0564) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [82aba8957b](https://linux-hardware.org/?probe=82aba8957b) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ae164f9998](https://linux-hardware.org/?probe=ae164f9998) | Jun 06, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [6ae325ff9d](https://linux-hardware.org/?probe=6ae325ff9d) | Jun 06, 2023 |
| HP            | 8918                        | Desktop     | [6f94c9caa9](https://linux-hardware.org/?probe=6f94c9caa9) | Jun 06, 2023 |
| Lenovo        | ThinkPad 21CKCT01WW         | Notebook    | [92c9ec75c4](https://linux-hardware.org/?probe=92c9ec75c4) | Jun 05, 2023 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [1bd1a651bb](https://linux-hardware.org/?probe=1bd1a651bb) | Jun 05, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [d9dba3ffdf](https://linux-hardware.org/?probe=d9dba3ffdf) | Jun 04, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [5b7a78b32e](https://linux-hardware.org/?probe=5b7a78b32e) | Jun 04, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [14f68da7a7](https://linux-hardware.org/?probe=14f68da7a7) | Jun 04, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [f077d744cb](https://linux-hardware.org/?probe=f077d744cb) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [e69fbf77e4](https://linux-hardware.org/?probe=e69fbf77e4) | Jun 04, 2023 |
| HP            | 843C                        | Desktop     | [21751c1221](https://linux-hardware.org/?probe=21751c1221) | Jun 04, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [4d24b9b7d5](https://linux-hardware.org/?probe=4d24b9b7d5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [f95d5c3046](https://linux-hardware.org/?probe=f95d5c3046) | Jun 03, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d8f3391b68](https://linux-hardware.org/?probe=d8f3391b68) | Jun 02, 2023 |
| HP            | 8918                        | Desktop     | [b03f8a6eb3](https://linux-hardware.org/?probe=b03f8a6eb3) | Jun 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | Notebook    | [e920b77fbb](https://linux-hardware.org/?probe=e920b77fbb) | Jun 02, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [16d662673f](https://linux-hardware.org/?probe=16d662673f) | Jun 02, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | Notebook    | [0a6e1e6be8](https://linux-hardware.org/?probe=0a6e1e6be8) | Jun 02, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | Desktop     | [e98b2555d7](https://linux-hardware.org/?probe=e98b2555d7) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3cb9ad156f](https://linux-hardware.org/?probe=3cb9ad156f) | Jun 01, 2023 |
| Dell          | Latitude 7490               | Notebook    | [31eb124dfb](https://linux-hardware.org/?probe=31eb124dfb) | Jun 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [29ec12f64d](https://linux-hardware.org/?probe=29ec12f64d) | May 30, 2023 |
| HP            | 2B36                        | Desktop     | [8e4fc0d41f](https://linux-hardware.org/?probe=8e4fc0d41f) | May 29, 2023 |
| GPD           | P2 MAX                      | Notebook    | [3c083ee96d](https://linux-hardware.org/?probe=3c083ee96d) | May 29, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [1d8b78cbdc](https://linux-hardware.org/?probe=1d8b78cbdc) | May 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Lenovo        | 3716 SDK0T76461 WIN 3422... | Desktop     | [2f3952dcfe](https://linux-hardware.org/?probe=2f3952dcfe) | May 27, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [246b95d20f](https://linux-hardware.org/?probe=246b95d20f) | May 24, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [2ef3c0b337](https://linux-hardware.org/?probe=2ef3c0b337) | May 24, 2023 |
| Samsung       | 930QED                      | Convertible | [14f0193b6a](https://linux-hardware.org/?probe=14f0193b6a) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [2cdf1c9e61](https://linux-hardware.org/?probe=2cdf1c9e61) | May 23, 2023 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [cca41e18cb](https://linux-hardware.org/?probe=cca41e18cb) | May 23, 2023 |
| Intel         | S2600STB J17012-601         | Server      | [2fa80c021a](https://linux-hardware.org/?probe=2fa80c021a) | May 23, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [a5a990a94c](https://linux-hardware.org/?probe=a5a990a94c) | May 23, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [aa0bf32546](https://linux-hardware.org/?probe=aa0bf32546) | May 23, 2023 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [c956e9cbab](https://linux-hardware.org/?probe=c956e9cbab) | May 22, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [ae4f01f58e](https://linux-hardware.org/?probe=ae4f01f58e) | May 22, 2023 |
| Dell          | Latitude E6530              | Notebook    | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| Lenovo        | 316E NOK                    | Mini pc     | [019a851aeb](https://linux-hardware.org/?probe=019a851aeb) | May 21, 2023 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [4a68db15c2](https://linux-hardware.org/?probe=4a68db15c2) | May 21, 2023 |
| ASUSTek       | ROG Flow X13 GV302XI_GV3... | Convertible | [5d4070956a](https://linux-hardware.org/?probe=5d4070956a) | May 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [f59c4fec2f](https://linux-hardware.org/?probe=f59c4fec2f) | May 20, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [0f9a26db5f](https://linux-hardware.org/?probe=0f9a26db5f) | May 16, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [bdaec355df](https://linux-hardware.org/?probe=bdaec355df) | May 16, 2023 |
| Lenovo        | ThinkPad X230 23257AG       | Notebook    | [56056f7c9a](https://linux-hardware.org/?probe=56056f7c9a) | May 15, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [b595a4a849](https://linux-hardware.org/?probe=b595a4a849) | May 15, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [ec0250b092](https://linux-hardware.org/?probe=ec0250b092) | May 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [9f4a8a37c0](https://linux-hardware.org/?probe=9f4a8a37c0) | May 15, 2023 |
| ASUSTek       | H97-PLUS                    | Desktop     | [e67567bd2a](https://linux-hardware.org/?probe=e67567bd2a) | May 15, 2023 |
| Dell          | Latitude 5520               | Notebook    | [721000195d](https://linux-hardware.org/?probe=721000195d) | May 15, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [c82f72f0e2](https://linux-hardware.org/?probe=c82f72f0e2) | May 15, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [64b813a7dc](https://linux-hardware.org/?probe=64b813a7dc) | May 14, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [6142fe7fbd](https://linux-hardware.org/?probe=6142fe7fbd) | May 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [26beee94a9](https://linux-hardware.org/?probe=26beee94a9) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [d71435c79a](https://linux-hardware.org/?probe=d71435c79a) | May 12, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [62e7f77fdc](https://linux-hardware.org/?probe=62e7f77fdc) | May 12, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f6c8b6c33e](https://linux-hardware.org/?probe=f6c8b6c33e) | May 12, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [41d9417c57](https://linux-hardware.org/?probe=41d9417c57) | May 11, 2023 |
| Acer          | Aspire 5332                 | Notebook    | [e74870bf17](https://linux-hardware.org/?probe=e74870bf17) | May 10, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [c39e7fa08d](https://linux-hardware.org/?probe=c39e7fa08d) | May 09, 2023 |
| HP            | Compaq 6910p                | Notebook    | [c17dc1abcf](https://linux-hardware.org/?probe=c17dc1abcf) | May 08, 2023 |
| Dell          | 0KRC95 A00                  | Desktop     | [f0f22d5d3f](https://linux-hardware.org/?probe=f0f22d5d3f) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c95999b5ad](https://linux-hardware.org/?probe=c95999b5ad) | May 08, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [670e910889](https://linux-hardware.org/?probe=670e910889) | May 08, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [7502ce9679](https://linux-hardware.org/?probe=7502ce9679) | May 08, 2023 |
| Medion        | MS-7797                     | Desktop     | [590e39bef4](https://linux-hardware.org/?probe=590e39bef4) | May 07, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [6089dfdeab](https://linux-hardware.org/?probe=6089dfdeab) | May 07, 2023 |
| ASRock        | 4X4-4000 Series             | Desktop     | [df056ec6f1](https://linux-hardware.org/?probe=df056ec6f1) | May 07, 2023 |
| Medion        | MS-7797                     | Desktop     | [d7eb2caa26](https://linux-hardware.org/?probe=d7eb2caa26) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6a4a95e86f](https://linux-hardware.org/?probe=6a4a95e86f) | May 06, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [2a4b061b07](https://linux-hardware.org/?probe=2a4b061b07) | May 05, 2023 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [54417e14cf](https://linux-hardware.org/?probe=54417e14cf) | May 05, 2023 |
| HP            | 212B                        | Desktop     | [d71b834a1c](https://linux-hardware.org/?probe=d71b834a1c) | May 05, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [4b705b9dca](https://linux-hardware.org/?probe=4b705b9dca) | May 03, 2023 |
| Lenovo        | 3730 SDK0T76463 WIN 3422... | Desktop     | [61873cde49](https://linux-hardware.org/?probe=61873cde49) | May 03, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [bbd9496296](https://linux-hardware.org/?probe=bbd9496296) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [71ec2fc5ea](https://linux-hardware.org/?probe=71ec2fc5ea) | May 03, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Notebook    | [6936dcf305](https://linux-hardware.org/?probe=6936dcf305) | May 03, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [7a44b651f4](https://linux-hardware.org/?probe=7a44b651f4) | May 03, 2023 |
| Acer          | Predator PH18-71            | Notebook    | [7c5e0a3de1](https://linux-hardware.org/?probe=7c5e0a3de1) | May 02, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [a720d9d42e](https://linux-hardware.org/?probe=a720d9d42e) | May 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0f77b52547](https://linux-hardware.org/?probe=0f77b52547) | May 01, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [c8c9c1e591](https://linux-hardware.org/?probe=c8c9c1e591) | Apr 30, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [5d77d7d922](https://linux-hardware.org/?probe=5d77d7d922) | Apr 30, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [910d4a6ad8](https://linux-hardware.org/?probe=910d4a6ad8) | Apr 29, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [e1e3261c15](https://linux-hardware.org/?probe=e1e3261c15) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [00d8186404](https://linux-hardware.org/?probe=00d8186404) | Apr 28, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [50e1b8e197](https://linux-hardware.org/?probe=50e1b8e197) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| Dell          | Latitude 5520               | Notebook    | [3071d4a9d8](https://linux-hardware.org/?probe=3071d4a9d8) | Apr 26, 2023 |
| Dell          | Latitude 5520               | Notebook    | [23fe32affd](https://linux-hardware.org/?probe=23fe32affd) | Apr 26, 2023 |
| MSI           | Creator 15 A10SGS           | Notebook    | [1b364e385a](https://linux-hardware.org/?probe=1b364e385a) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a48c247194](https://linux-hardware.org/?probe=a48c247194) | Apr 26, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [11844fed4d](https://linux-hardware.org/?probe=11844fed4d) | Apr 25, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [7afd2012e8](https://linux-hardware.org/?probe=7afd2012e8) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [c7fdbbb95b](https://linux-hardware.org/?probe=c7fdbbb95b) | Apr 25, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [363bb28966](https://linux-hardware.org/?probe=363bb28966) | Apr 25, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d73e1b6350](https://linux-hardware.org/?probe=d73e1b6350) | Apr 24, 2023 |
| Dell          | Latitude 7530               | Notebook    | [17140d3871](https://linux-hardware.org/?probe=17140d3871) | Apr 24, 2023 |
| HP            | 8433 11                     | Desktop     | [e885f0469c](https://linux-hardware.org/?probe=e885f0469c) | Apr 22, 2023 |
| AZW           | GTR V02                     | Desktop     | [104badc0d7](https://linux-hardware.org/?probe=104badc0d7) | Apr 22, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [d7ad0ed423](https://linux-hardware.org/?probe=d7ad0ed423) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [570077aa64](https://linux-hardware.org/?probe=570077aa64) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | Desktop     | [65c9942c32](https://linux-hardware.org/?probe=65c9942c32) | Apr 21, 2023 |
| Lenovo        | 3753 SDK0T76461 WIN 3422... | Desktop     | [607dbbf4d8](https://linux-hardware.org/?probe=607dbbf4d8) | Apr 21, 2023 |
| Gigabyte      | P55A-UD7                    | Desktop     | [59f8c4d262](https://linux-hardware.org/?probe=59f8c4d262) | Apr 20, 2023 |
| Intel         | S2600WTTR G92187-366        | Server      | [9bb50174ef](https://linux-hardware.org/?probe=9bb50174ef) | Apr 20, 2023 |
| Dell          | 0DPRKF A01                  | Server      | [51412400ba](https://linux-hardware.org/?probe=51412400ba) | Apr 20, 2023 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | Desktop     | [f20338e169](https://linux-hardware.org/?probe=f20338e169) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2c6da4e91f](https://linux-hardware.org/?probe=2c6da4e91f) | Apr 20, 2023 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [472922fafd](https://linux-hardware.org/?probe=472922fafd) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [a1b9ea4fd9](https://linux-hardware.org/?probe=a1b9ea4fd9) | Apr 20, 2023 |
| Intel         | DX58SO2 AAG10925-207        | Desktop     | [4e31c5af6b](https://linux-hardware.org/?probe=4e31c5af6b) | Apr 20, 2023 |
| Intel         | DP67BA AAG10219-303         | Desktop     | [27a629fd15](https://linux-hardware.org/?probe=27a629fd15) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [f3a680d9bc](https://linux-hardware.org/?probe=f3a680d9bc) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [96d5a26185](https://linux-hardware.org/?probe=96d5a26185) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [b6306c2e97](https://linux-hardware.org/?probe=b6306c2e97) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [fbedbcb213](https://linux-hardware.org/?probe=fbedbcb213) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [6e77ac0ec9](https://linux-hardware.org/?probe=6e77ac0ec9) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [c1b2a75484](https://linux-hardware.org/?probe=c1b2a75484) | Apr 20, 2023 |
| Fujitsu       | D3617-A1 S26361-D3617-A1    | Desktop     | [756eccb961](https://linux-hardware.org/?probe=756eccb961) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [ef04208d0f](https://linux-hardware.org/?probe=ef04208d0f) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [c419c9200f](https://linux-hardware.org/?probe=c419c9200f) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [1be8dc273c](https://linux-hardware.org/?probe=1be8dc273c) | Apr 20, 2023 |
| Intel         | S2600WTTR G92187-366        | Server      | [d765a92052](https://linux-hardware.org/?probe=d765a92052) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [244222ae5c](https://linux-hardware.org/?probe=244222ae5c) | Apr 20, 2023 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [f77fe53c69](https://linux-hardware.org/?probe=f77fe53c69) | Apr 20, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7d49aa5207](https://linux-hardware.org/?probe=7d49aa5207) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [d53ce13aa3](https://linux-hardware.org/?probe=d53ce13aa3) | Apr 20, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [ec13e17577](https://linux-hardware.org/?probe=ec13e17577) | Apr 20, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [9fde2b21fc](https://linux-hardware.org/?probe=9fde2b21fc) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | Desktop     | [ddc7ba8ccb](https://linux-hardware.org/?probe=ddc7ba8ccb) | Apr 20, 2023 |
| Fujitsu       | D3348-A2 S26361-D3348-A2    | Desktop     | [3dbd4f731c](https://linux-hardware.org/?probe=3dbd4f731c) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [d46e9b11d5](https://linux-hardware.org/?probe=d46e9b11d5) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [afbf28c15a](https://linux-hardware.org/?probe=afbf28c15a) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [f185782be2](https://linux-hardware.org/?probe=f185782be2) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [731671f1b8](https://linux-hardware.org/?probe=731671f1b8) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [463c62da83](https://linux-hardware.org/?probe=463c62da83) | Apr 20, 2023 |
| Fujitsu       | D3517-A1 S26361-D3517-A1    | Desktop     | [0356125777](https://linux-hardware.org/?probe=0356125777) | Apr 20, 2023 |
| ASUSTek       | PRIME Z490M-PLUS            | Desktop     | [0a45e9e9af](https://linux-hardware.org/?probe=0a45e9e9af) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ccf2e2bbc3](https://linux-hardware.org/?probe=ccf2e2bbc3) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [3171099090](https://linux-hardware.org/?probe=3171099090) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [032f3a72c6](https://linux-hardware.org/?probe=032f3a72c6) | Apr 20, 2023 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [df7041b726](https://linux-hardware.org/?probe=df7041b726) | Apr 20, 2023 |
| ASUSTek       | P9X79 WS                    | Desktop     | [04e9cd2455](https://linux-hardware.org/?probe=04e9cd2455) | Apr 20, 2023 |
| Intel         | DP55WB AAE64798-207         | Desktop     | [0dd9e12f5a](https://linux-hardware.org/?probe=0dd9e12f5a) | Apr 20, 2023 |
| HP            | 870B                        | Desktop     | [ad6a3cc4d0](https://linux-hardware.org/?probe=ad6a3cc4d0) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [9e668ff813](https://linux-hardware.org/?probe=9e668ff813) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [5dc0cb1f28](https://linux-hardware.org/?probe=5dc0cb1f28) | Apr 20, 2023 |
| Medion        | GA-Z170X-Gaming 7           | Desktop     | [706cfb4c50](https://linux-hardware.org/?probe=706cfb4c50) | Apr 20, 2023 |
| Gigabyte      | H97-HD3                     | Desktop     | [b3b27e0fcf](https://linux-hardware.org/?probe=b3b27e0fcf) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [bdbd8d06e2](https://linux-hardware.org/?probe=bdbd8d06e2) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [ff10999142](https://linux-hardware.org/?probe=ff10999142) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [11da8c5d96](https://linux-hardware.org/?probe=11da8c5d96) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [128d16cf7f](https://linux-hardware.org/?probe=128d16cf7f) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c2de2809a0](https://linux-hardware.org/?probe=c2de2809a0) | Apr 20, 2023 |
| Intel         | S2600WFT H48104-860         | Server      | [f5848d1ba2](https://linux-hardware.org/?probe=f5848d1ba2) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c3a3c03c3f](https://linux-hardware.org/?probe=c3a3c03c3f) | Apr 20, 2023 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [1ae9258a0d](https://linux-hardware.org/?probe=1ae9258a0d) | Apr 20, 2023 |
| Intel         | SVRBD-ROW_T G30981-503      | Server      | [5fba63c085](https://linux-hardware.org/?probe=5fba63c085) | Apr 20, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [ab89260502](https://linux-hardware.org/?probe=ab89260502) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3f99aeec69](https://linux-hardware.org/?probe=3f99aeec69) | Apr 20, 2023 |
| HP            | 870B                        | Desktop     | [50f654b2a0](https://linux-hardware.org/?probe=50f654b2a0) | Apr 20, 2023 |
| Fujitsu       | D3348-A1 S26361-D3348-A1    | Desktop     | [9949a0748f](https://linux-hardware.org/?probe=9949a0748f) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [e3cfbf7435](https://linux-hardware.org/?probe=e3cfbf7435) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9817f90648](https://linux-hardware.org/?probe=9817f90648) | Apr 20, 2023 |
| ASUSTek       | G35CG                       | Desktop     | [cf4854d704](https://linux-hardware.org/?probe=cf4854d704) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [296676f929](https://linux-hardware.org/?probe=296676f929) | Apr 20, 2023 |
| ASUSTek       | PRIME Z370-A II             | Desktop     | [2eeebec1ec](https://linux-hardware.org/?probe=2eeebec1ec) | Apr 20, 2023 |
| Fujitsu       | D3417-A2 S26361-D3417-A2    | Desktop     | [68ac671aab](https://linux-hardware.org/?probe=68ac671aab) | Apr 20, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [a069d32b86](https://linux-hardware.org/?probe=a069d32b86) | Apr 20, 2023 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [1b1a3da7b2](https://linux-hardware.org/?probe=1b1a3da7b2) | Apr 20, 2023 |
| Gigabyte      | MZ12-HD3-00 01010101        | Server      | [def4067c8e](https://linux-hardware.org/?probe=def4067c8e) | Apr 20, 2023 |
| ASUSTek       | X99-S                       | Desktop     | [2a1fcefe29](https://linux-hardware.org/?probe=2a1fcefe29) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5c54edc96d](https://linux-hardware.org/?probe=5c54edc96d) | Apr 20, 2023 |
| ASRock        | B760M Steel Legend WiFi     | Desktop     | [563e45a22a](https://linux-hardware.org/?probe=563e45a22a) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0000720fb6](https://linux-hardware.org/?probe=0000720fb6) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [fdda3d6276](https://linux-hardware.org/?probe=fdda3d6276) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ee95d83f31](https://linux-hardware.org/?probe=ee95d83f31) | Apr 20, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [1e49dc0f67](https://linux-hardware.org/?probe=1e49dc0f67) | Apr 20, 2023 |
| Gigabyte      | MZ92-FS0-00 01010101        | Server      | [3e6b182473](https://linux-hardware.org/?probe=3e6b182473) | Apr 20, 2023 |
| HP            | ProLiant ML150 G6           | Desktop     | [76dc3db16a](https://linux-hardware.org/?probe=76dc3db16a) | Apr 20, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [c4c1d8086c](https://linux-hardware.org/?probe=c4c1d8086c) | Apr 20, 2023 |
| ASRock        | B560M-HDV                   | Desktop     | [b835e48fad](https://linux-hardware.org/?probe=b835e48fad) | Apr 19, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [882d6f625d](https://linux-hardware.org/?probe=882d6f625d) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8f16bcad94](https://linux-hardware.org/?probe=8f16bcad94) | Apr 19, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [848607e7f1](https://linux-hardware.org/?probe=848607e7f1) | Apr 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [b076a9a807](https://linux-hardware.org/?probe=b076a9a807) | Apr 18, 2023 |
| Dell          | 0D4VY1 A00                  | All in one  | [ddbd926522](https://linux-hardware.org/?probe=ddbd926522) | Apr 18, 2023 |
| Dell          | 0R4CNN A02                  | Server      | [237a3cd682](https://linux-hardware.org/?probe=237a3cd682) | Apr 18, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [79225bdfaf](https://linux-hardware.org/?probe=79225bdfaf) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [4d802fb610](https://linux-hardware.org/?probe=4d802fb610) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [2b749e898e](https://linux-hardware.org/?probe=2b749e898e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [702377976d](https://linux-hardware.org/?probe=702377976d) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [32f7392dce](https://linux-hardware.org/?probe=32f7392dce) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b7f40b0d8e](https://linux-hardware.org/?probe=b7f40b0d8e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [9602690aa2](https://linux-hardware.org/?probe=9602690aa2) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [bbf0a5108a](https://linux-hardware.org/?probe=bbf0a5108a) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [000ec3362e](https://linux-hardware.org/?probe=000ec3362e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [7d67899067](https://linux-hardware.org/?probe=7d67899067) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [256a2110b0](https://linux-hardware.org/?probe=256a2110b0) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [9f69cc7127](https://linux-hardware.org/?probe=9f69cc7127) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [997c25143e](https://linux-hardware.org/?probe=997c25143e) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [71822fdac9](https://linux-hardware.org/?probe=71822fdac9) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [b3f9111b79](https://linux-hardware.org/?probe=b3f9111b79) | Apr 17, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [df314b2a9c](https://linux-hardware.org/?probe=df314b2a9c) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [dc155ce308](https://linux-hardware.org/?probe=dc155ce308) | Apr 17, 2023 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [aaff05d28f](https://linux-hardware.org/?probe=aaff05d28f) | Apr 17, 2023 |
| Lenovo        | ThinkPad T420 4180MG1       | Notebook    | [132e6ba829](https://linux-hardware.org/?probe=132e6ba829) | Apr 17, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [fc6c4adaa4](https://linux-hardware.org/?probe=fc6c4adaa4) | Apr 17, 2023 |
| Apple         | Mac-65CE76090165799A iMa... | All in one  | [8dd4721bd1](https://linux-hardware.org/?probe=8dd4721bd1) | Apr 16, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [a0f5ba360c](https://linux-hardware.org/?probe=a0f5ba360c) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [9c885fa5cf](https://linux-hardware.org/?probe=9c885fa5cf) | Apr 16, 2023 |
| Lenovo        | 3704 SDK0R32862 WIN 3258... | Desktop     | [4d3cbcc4d9](https://linux-hardware.org/?probe=4d3cbcc4d9) | Apr 16, 2023 |
| Dell          | Latitude 7530               | Notebook    | [133059c3d6](https://linux-hardware.org/?probe=133059c3d6) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [8fb4ed64eb](https://linux-hardware.org/?probe=8fb4ed64eb) | Apr 16, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5943787304](https://linux-hardware.org/?probe=5943787304) | Apr 16, 2023 |
| ASUSTek       | X756UJ                      | Notebook    | [a374f8dd26](https://linux-hardware.org/?probe=a374f8dd26) | Apr 15, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [c4f2e4e7d8](https://linux-hardware.org/?probe=c4f2e4e7d8) | Apr 14, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [a0247e45a6](https://linux-hardware.org/?probe=a0247e45a6) | Apr 13, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [f205e700dc](https://linux-hardware.org/?probe=f205e700dc) | Apr 13, 2023 |
| Lenovo        | Yoga 6 13ABR8 83B2          | Convertible | [817e4bb939](https://linux-hardware.org/?probe=817e4bb939) | Apr 13, 2023 |
| HP            | 8433 11                     | Desktop     | [61c92812be](https://linux-hardware.org/?probe=61c92812be) | Apr 12, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [d5e608b74e](https://linux-hardware.org/?probe=d5e608b74e) | Apr 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [e9ba143773](https://linux-hardware.org/?probe=e9ba143773) | Apr 11, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [ec028424ea](https://linux-hardware.org/?probe=ec028424ea) | Apr 09, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [cc25df15df](https://linux-hardware.org/?probe=cc25df15df) | Apr 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9ccdf29023](https://linux-hardware.org/?probe=9ccdf29023) | Apr 08, 2023 |
| ASUSTek       | P8P67                       | Desktop     | [a62766f42e](https://linux-hardware.org/?probe=a62766f42e) | Apr 08, 2023 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [6a8c52faa7](https://linux-hardware.org/?probe=6a8c52faa7) | Apr 06, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [d741226152](https://linux-hardware.org/?probe=d741226152) | Apr 06, 2023 |
| HP            | ProBook 4540s               | Notebook    | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | Notebook    | [32f5d43e96](https://linux-hardware.org/?probe=32f5d43e96) | Apr 04, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [423c5d2481](https://linux-hardware.org/?probe=423c5d2481) | Apr 03, 2023 |
| Sony          | VPCF22C5E                   | Notebook    | [9d122b8bdd](https://linux-hardware.org/?probe=9d122b8bdd) | Apr 03, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [8566b9511a](https://linux-hardware.org/?probe=8566b9511a) | Apr 02, 2023 |
| ASUSTek       | Maximus IV Extreme-Z        | Desktop     | [36d245f86b](https://linux-hardware.org/?probe=36d245f86b) | Apr 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3a8d512ae4](https://linux-hardware.org/?probe=3a8d512ae4) | Apr 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [6f3e488e2b](https://linux-hardware.org/?probe=6f3e488e2b) | Apr 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b0beffe006](https://linux-hardware.org/?probe=b0beffe006) | Apr 01, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [17fb0ed43a](https://linux-hardware.org/?probe=17fb0ed43a) | Mar 31, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [1d5f866283](https://linux-hardware.org/?probe=1d5f866283) | Mar 31, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [570836875c](https://linux-hardware.org/?probe=570836875c) | Mar 31, 2023 |
| HP            | Unknown                     | Notebook    | [fb784430a5](https://linux-hardware.org/?probe=fb784430a5) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [3494b0fdd9](https://linux-hardware.org/?probe=3494b0fdd9) | Mar 30, 2023 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [c885b5da6c](https://linux-hardware.org/?probe=c885b5da6c) | Mar 30, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [452a3fa4a8](https://linux-hardware.org/?probe=452a3fa4a8) | Mar 29, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [e1d01990f4](https://linux-hardware.org/?probe=e1d01990f4) | Mar 27, 2023 |
| HP            | 844C                        | Desktop     | [8270d682a8](https://linux-hardware.org/?probe=8270d682a8) | Mar 27, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [405ce5a9c8](https://linux-hardware.org/?probe=405ce5a9c8) | Mar 27, 2023 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [35e0a73e8f](https://linux-hardware.org/?probe=35e0a73e8f) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [03df3679d3](https://linux-hardware.org/?probe=03df3679d3) | Mar 26, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [f7d3c52f58](https://linux-hardware.org/?probe=f7d3c52f58) | Mar 26, 2023 |
| Acer          | Predator G9-791             | Notebook    | [1f820516a3](https://linux-hardware.org/?probe=1f820516a3) | Mar 26, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [426c7d7939](https://linux-hardware.org/?probe=426c7d7939) | Mar 25, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [6c64b62e05](https://linux-hardware.org/?probe=6c64b62e05) | Mar 25, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | Notebook    | [0096d3d3b1](https://linux-hardware.org/?probe=0096d3d3b1) | Mar 25, 2023 |
| HP            | 8433 11                     | Desktop     | [5ab010ffd4](https://linux-hardware.org/?probe=5ab010ffd4) | Mar 25, 2023 |
| Purism        | Librem 13 v2                | Notebook    | [ef5cf3e08f](https://linux-hardware.org/?probe=ef5cf3e08f) | Mar 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [728f83932f](https://linux-hardware.org/?probe=728f83932f) | Mar 24, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [5a94081c24](https://linux-hardware.org/?probe=5a94081c24) | Mar 24, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [704fb36197](https://linux-hardware.org/?probe=704fb36197) | Mar 23, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e8ad290196](https://linux-hardware.org/?probe=e8ad290196) | Mar 23, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [1159055040](https://linux-hardware.org/?probe=1159055040) | Mar 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [74be0519cc](https://linux-hardware.org/?probe=74be0519cc) | Mar 22, 2023 |
| ASRock        | H270 Pro4                   | Desktop     | [01eb4c8ba5](https://linux-hardware.org/?probe=01eb4c8ba5) | Mar 22, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [ea5065ef8f](https://linux-hardware.org/?probe=ea5065ef8f) | Mar 21, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [5074a23172](https://linux-hardware.org/?probe=5074a23172) | Mar 20, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [9ba3333988](https://linux-hardware.org/?probe=9ba3333988) | Mar 20, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [0fb09c29cb](https://linux-hardware.org/?probe=0fb09c29cb) | Mar 20, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [6c83c2a089](https://linux-hardware.org/?probe=6c83c2a089) | Mar 19, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [3c00ca015f](https://linux-hardware.org/?probe=3c00ca015f) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [d7acdc8bf3](https://linux-hardware.org/?probe=d7acdc8bf3) | Mar 18, 2023 |
| Google        | Lillipup                    | Notebook    | [3eca64113c](https://linux-hardware.org/?probe=3eca64113c) | Mar 18, 2023 |
| Medion        | S1219T MD99922              | Tablet      | [4e6f4d1197](https://linux-hardware.org/?probe=4e6f4d1197) | Mar 17, 2023 |
| HP            | 2B36                        | Desktop     | [85c11ec746](https://linux-hardware.org/?probe=85c11ec746) | Mar 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [10ec4f48dd](https://linux-hardware.org/?probe=10ec4f48dd) | Mar 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [bfdb73f825](https://linux-hardware.org/?probe=bfdb73f825) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [be76f3a0a3](https://linux-hardware.org/?probe=be76f3a0a3) | Mar 15, 2023 |
| Medion        | B360H4-EM V1.0              | Desktop     | [839899a14d](https://linux-hardware.org/?probe=839899a14d) | Mar 15, 2023 |
| ASUSTek       | UX32A                       | Notebook    | [05121bc6af](https://linux-hardware.org/?probe=05121bc6af) | Mar 15, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f4926b859a](https://linux-hardware.org/?probe=f4926b859a) | Mar 15, 2023 |
| Dell          | Latitude E6440              | Notebook    | [76a537c18e](https://linux-hardware.org/?probe=76a537c18e) | Mar 14, 2023 |
| Notebook      | NS50MU                      | Notebook    | [f5e64711f3](https://linux-hardware.org/?probe=f5e64711f3) | Mar 14, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f424a1dc42](https://linux-hardware.org/?probe=f424a1dc42) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [31ac227c9f](https://linux-hardware.org/?probe=31ac227c9f) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [36bcd11bd3](https://linux-hardware.org/?probe=36bcd11bd3) | Mar 14, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [aca12aa4c5](https://linux-hardware.org/?probe=aca12aa4c5) | Mar 13, 2023 |
| Lenovo        | ThinkPad T490s 20NX002SG... | Notebook    | [aa5eb19101](https://linux-hardware.org/?probe=aa5eb19101) | Mar 13, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [433c3d165a](https://linux-hardware.org/?probe=433c3d165a) | Mar 13, 2023 |
| HP            | 212B                        | Desktop     | [8d5ef71d93](https://linux-hardware.org/?probe=8d5ef71d93) | Mar 13, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [43c96b4e3e](https://linux-hardware.org/?probe=43c96b4e3e) | Mar 13, 2023 |
| Apple         | Mac-4B682C642B45593E iMa... | All in one  | [a6af61dfb4](https://linux-hardware.org/?probe=a6af61dfb4) | Mar 13, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [c2174a1837](https://linux-hardware.org/?probe=c2174a1837) | Mar 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [99095e84f5](https://linux-hardware.org/?probe=99095e84f5) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [55fe24706a](https://linux-hardware.org/?probe=55fe24706a) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [6c90dd73e7](https://linux-hardware.org/?probe=6c90dd73e7) | Mar 11, 2023 |
| Dell          | 09KPNV A00                  | Desktop     | [c792b83b69](https://linux-hardware.org/?probe=c792b83b69) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | Notebook    | [ade1e690bb](https://linux-hardware.org/?probe=ade1e690bb) | Mar 11, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d7535fd29e](https://linux-hardware.org/?probe=d7535fd29e) | Mar 10, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [0e1279e96d](https://linux-hardware.org/?probe=0e1279e96d) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5b8db1d628](https://linux-hardware.org/?probe=5b8db1d628) | Mar 10, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [b9e49da1f7](https://linux-hardware.org/?probe=b9e49da1f7) | Mar 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [9946c1c6dc](https://linux-hardware.org/?probe=9946c1c6dc) | Mar 09, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [3c5ca39c55](https://linux-hardware.org/?probe=3c5ca39c55) | Mar 08, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | Notebook    | [e280beba92](https://linux-hardware.org/?probe=e280beba92) | Mar 08, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [d52a175b61](https://linux-hardware.org/?probe=d52a175b61) | Mar 07, 2023 |
| AZW           | GTR V02                     | Desktop     | [030dde937b](https://linux-hardware.org/?probe=030dde937b) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [971feb34e4](https://linux-hardware.org/?probe=971feb34e4) | Mar 07, 2023 |
| Fujitsu       | CELSIUS H780                | Notebook    | [7080d07525](https://linux-hardware.org/?probe=7080d07525) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [3b02985778](https://linux-hardware.org/?probe=3b02985778) | Mar 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | Notebook    | [e6e0d7226d](https://linux-hardware.org/?probe=e6e0d7226d) | Mar 07, 2023 |
| Acer          | Nitro AN517-52              | Notebook    | [fd6cb5c68a](https://linux-hardware.org/?probe=fd6cb5c68a) | Mar 07, 2023 |
| Acer          | Predator PH517-61           | Notebook    | [359903fe58](https://linux-hardware.org/?probe=359903fe58) | Mar 07, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [5656c3015d](https://linux-hardware.org/?probe=5656c3015d) | Mar 06, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [676eaa7960](https://linux-hardware.org/?probe=676eaa7960) | Mar 06, 2023 |
| Lenovo        | ThinkPad E590 20NB000YMZ    | Notebook    | [fb05511be8](https://linux-hardware.org/?probe=fb05511be8) | Mar 05, 2023 |
| HP            | Compaq 15                   | Notebook    | [5c8a185273](https://linux-hardware.org/?probe=5c8a185273) | Mar 05, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [e57a377381](https://linux-hardware.org/?probe=e57a377381) | Mar 05, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [e45794963a](https://linux-hardware.org/?probe=e45794963a) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [a987f40464](https://linux-hardware.org/?probe=a987f40464) | Mar 04, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [6cd1e0a746](https://linux-hardware.org/?probe=6cd1e0a746) | Mar 04, 2023 |
| Timi          | TM1701                      | Notebook    | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [02df2ea534](https://linux-hardware.org/?probe=02df2ea534) | Mar 03, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [1bcec582e3](https://linux-hardware.org/?probe=1bcec582e3) | Mar 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [cacb713046](https://linux-hardware.org/?probe=cacb713046) | Mar 02, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [86ec7ef027](https://linux-hardware.org/?probe=86ec7ef027) | Mar 02, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [117d283b7a](https://linux-hardware.org/?probe=117d283b7a) | Mar 02, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [0f19d5c037](https://linux-hardware.org/?probe=0f19d5c037) | Mar 01, 2023 |
| Lenovo        | ThinkPad Edge E531 6885D... | Notebook    | [0780656106](https://linux-hardware.org/?probe=0780656106) | Mar 01, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [ed251c6cfe](https://linux-hardware.org/?probe=ed251c6cfe) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [8fc8fee94a](https://linux-hardware.org/?probe=8fc8fee94a) | Feb 27, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [3f0d63ab15](https://linux-hardware.org/?probe=3f0d63ab15) | Feb 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1412fd5885](https://linux-hardware.org/?probe=1412fd5885) | Feb 26, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [0855d319b4](https://linux-hardware.org/?probe=0855d319b4) | Feb 26, 2023 |
| Medion        | BEAST X25                   | Notebook    | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| Dell          | Latitude 5580               | Notebook    | [cd4a13ce32](https://linux-hardware.org/?probe=cd4a13ce32) | Feb 25, 2023 |
| Dell          | Latitude 5580               | Notebook    | [79da5a8efd](https://linux-hardware.org/?probe=79da5a8efd) | Feb 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [9755df8e75](https://linux-hardware.org/?probe=9755df8e75) | Feb 25, 2023 |
| Lenovo        | ThinkPad P50s 20FKS0A300    | Notebook    | [2b9ed74f9d](https://linux-hardware.org/?probe=2b9ed74f9d) | Feb 25, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [af87e6ea4c](https://linux-hardware.org/?probe=af87e6ea4c) | Feb 25, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [9c0775a106](https://linux-hardware.org/?probe=9c0775a106) | Feb 25, 2023 |
| Lenovo        | ThinkPad X61s 7667CG7       | Notebook    | [f090aa4d60](https://linux-hardware.org/?probe=f090aa4d60) | Feb 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [bea010d25e](https://linux-hardware.org/?probe=bea010d25e) | Feb 24, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [0608ea56d7](https://linux-hardware.org/?probe=0608ea56d7) | Feb 24, 2023 |
| Intel         | NUC7i3DNB J57625-510        | Mini pc     | [aedbb176f7](https://linux-hardware.org/?probe=aedbb176f7) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [701608fad1](https://linux-hardware.org/?probe=701608fad1) | Feb 22, 2023 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4794c72566](https://linux-hardware.org/?probe=4794c72566) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX B560-A GAMING ... | Desktop     | [119e106d80](https://linux-hardware.org/?probe=119e106d80) | Feb 20, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [576314ab03](https://linux-hardware.org/?probe=576314ab03) | Feb 20, 2023 |
| ASUSTek       | GL702VM                     | Notebook    | [daa3e0f7df](https://linux-hardware.org/?probe=daa3e0f7df) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [033908dc21](https://linux-hardware.org/?probe=033908dc21) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | Notebook    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| Gigabyte      | X99-Ultra Gaming-CF         | Desktop     | [031c13ea35](https://linux-hardware.org/?probe=031c13ea35) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | Notebook    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [f8dfa838b7](https://linux-hardware.org/?probe=f8dfa838b7) | Feb 18, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | Notebook    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | Notebook    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | Notebook    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [d773500fcb](https://linux-hardware.org/?probe=d773500fcb) | Feb 18, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [c8bc9e01fd](https://linux-hardware.org/?probe=c8bc9e01fd) | Feb 17, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | Desktop     | [8338ee5a0d](https://linux-hardware.org/?probe=8338ee5a0d) | Feb 17, 2023 |
| Acer          | Aspire 5741G                | Notebook    | [b39c940cfd](https://linux-hardware.org/?probe=b39c940cfd) | Feb 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [92a61cd4ee](https://linux-hardware.org/?probe=92a61cd4ee) | Feb 16, 2023 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | Notebook    | [ccd78843fc](https://linux-hardware.org/?probe=ccd78843fc) | Feb 16, 2023 |
| Philco        | DTC-A55                     | Desktop     | [e957b8f1cf](https://linux-hardware.org/?probe=e957b8f1cf) | Feb 16, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [ef74f90ec1](https://linux-hardware.org/?probe=ef74f90ec1) | Feb 16, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [e927a19203](https://linux-hardware.org/?probe=e927a19203) | Feb 16, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [826959e69e](https://linux-hardware.org/?probe=826959e69e) | Feb 13, 2023 |
| Samsung       | 930QED                      | Convertible | [9e03711ee7](https://linux-hardware.org/?probe=9e03711ee7) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [91657d5c1d](https://linux-hardware.org/?probe=91657d5c1d) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | Notebook    | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| HP            | ZBook 14u G5                | Notebook    | [db7a713397](https://linux-hardware.org/?probe=db7a713397) | Feb 12, 2023 |
| Lenovo        | ThinkPad P73 20QR002PMZ     | Notebook    | [458447fa93](https://linux-hardware.org/?probe=458447fa93) | Feb 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2d2e867259](https://linux-hardware.org/?probe=2d2e867259) | Feb 10, 2023 |
| HP            | 8653 A                      | Desktop     | [5854a10eb0](https://linux-hardware.org/?probe=5854a10eb0) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [40c7c2e40b](https://linux-hardware.org/?probe=40c7c2e40b) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ddd47ed4b7](https://linux-hardware.org/?probe=ddd47ed4b7) | Feb 10, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [f163a3dd38](https://linux-hardware.org/?probe=f163a3dd38) | Feb 09, 2023 |
| HP            | Pavilion dv6                | Notebook    | [6d9840bb7c](https://linux-hardware.org/?probe=6d9840bb7c) | Feb 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a73dfae3f](https://linux-hardware.org/?probe=9a73dfae3f) | Feb 08, 2023 |
| HP            | ProBook 4720s               | Notebook    | [96ec8d979e](https://linux-hardware.org/?probe=96ec8d979e) | Feb 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [e7fd395c49](https://linux-hardware.org/?probe=e7fd395c49) | Feb 05, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [49a4e66cd0](https://linux-hardware.org/?probe=49a4e66cd0) | Feb 05, 2023 |
| Fujitsu       | D3413-A1 S26361-D3413-A1    | Desktop     | [384a4f7da2](https://linux-hardware.org/?probe=384a4f7da2) | Feb 05, 2023 |
| HP            | 2B36                        | Desktop     | [dde1352d90](https://linux-hardware.org/?probe=dde1352d90) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [9e7d0b79cf](https://linux-hardware.org/?probe=9e7d0b79cf) | Feb 05, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [90c48082e0](https://linux-hardware.org/?probe=90c48082e0) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | Notebook    | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [5dbc22fda8](https://linux-hardware.org/?probe=5dbc22fda8) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e7b6c27948](https://linux-hardware.org/?probe=e7b6c27948) | Feb 04, 2023 |
| Gigabyte      | H81M-H                      | Desktop     | [4626133ef2](https://linux-hardware.org/?probe=4626133ef2) | Feb 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [b08ab3c55c](https://linux-hardware.org/?probe=b08ab3c55c) | Feb 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | Notebook    | [9968b839f2](https://linux-hardware.org/?probe=9968b839f2) | Feb 03, 2023 |
| HP            | ProBook 6560b               | Notebook    | [a66e882be4](https://linux-hardware.org/?probe=a66e882be4) | Feb 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [0ca0b99aa3](https://linux-hardware.org/?probe=0ca0b99aa3) | Feb 03, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [60cf9e4948](https://linux-hardware.org/?probe=60cf9e4948) | Jan 31, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [ff0dfe765e](https://linux-hardware.org/?probe=ff0dfe765e) | Jan 31, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [59a0c6f08f](https://linux-hardware.org/?probe=59a0c6f08f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [fddcdb0f47](https://linux-hardware.org/?probe=fddcdb0f47) | Jan 29, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [11b07d4e11](https://linux-hardware.org/?probe=11b07d4e11) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [1d79d6f224](https://linux-hardware.org/?probe=1d79d6f224) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [14b3eb9a58](https://linux-hardware.org/?probe=14b3eb9a58) | Jan 25, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b83c8fb5a1](https://linux-hardware.org/?probe=b83c8fb5a1) | Jan 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b6afa43240](https://linux-hardware.org/?probe=b6afa43240) | Jan 24, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [141c9ffa73](https://linux-hardware.org/?probe=141c9ffa73) | Jan 24, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [e04cbf47d6](https://linux-hardware.org/?probe=e04cbf47d6) | Jan 24, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [213b4b45e5](https://linux-hardware.org/?probe=213b4b45e5) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [163afb997a](https://linux-hardware.org/?probe=163afb997a) | Jan 23, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [f45af20da6](https://linux-hardware.org/?probe=f45af20da6) | Jan 23, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | Notebook    | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [93d0aaac10](https://linux-hardware.org/?probe=93d0aaac10) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [eb9cef403c](https://linux-hardware.org/?probe=eb9cef403c) | Jan 21, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [0192877edc](https://linux-hardware.org/?probe=0192877edc) | Jan 20, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [69f4adcf81](https://linux-hardware.org/?probe=69f4adcf81) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [873a521bf5](https://linux-hardware.org/?probe=873a521bf5) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bf7bab9d7c](https://linux-hardware.org/?probe=bf7bab9d7c) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [e05b7e7729](https://linux-hardware.org/?probe=e05b7e7729) | Jan 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | Notebook    | [37fd07b937](https://linux-hardware.org/?probe=37fd07b937) | Jan 18, 2023 |
| Medion        | MS-7728                     | Desktop     | [b5e3ddf859](https://linux-hardware.org/?probe=b5e3ddf859) | Jan 18, 2023 |
| Acer          | Veriton M2110G              | Desktop     | [7097a3cf90](https://linux-hardware.org/?probe=7097a3cf90) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [b4e1da9857](https://linux-hardware.org/?probe=b4e1da9857) | Jan 17, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [80f8925010](https://linux-hardware.org/?probe=80f8925010) | Jan 17, 2023 |
| Acer          | Aspire M5910                | Desktop     | [d2d4e86b49](https://linux-hardware.org/?probe=d2d4e86b49) | Jan 17, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| HP            | 212B                        | Desktop     | [00822b2263](https://linux-hardware.org/?probe=00822b2263) | Jan 16, 2023 |
| Medion        | MS-7728                     | Desktop     | [5168c2f916](https://linux-hardware.org/?probe=5168c2f916) | Jan 16, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [340bddf38d](https://linux-hardware.org/?probe=340bddf38d) | Jan 16, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ca74e79834](https://linux-hardware.org/?probe=ca74e79834) | Jan 15, 2023 |
| AZW           | GTR V02                     | Desktop     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [1f30a57359](https://linux-hardware.org/?probe=1f30a57359) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ebb69311f7](https://linux-hardware.org/?probe=ebb69311f7) | Jan 14, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [03e4d52b2d](https://linux-hardware.org/?probe=03e4d52b2d) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [182eb9ffa1](https://linux-hardware.org/?probe=182eb9ffa1) | Jan 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f84f79fce7](https://linux-hardware.org/?probe=f84f79fce7) | Jan 11, 2023 |
| ELSKY         | QM10u                       | Desktop     | [c9bde314b5](https://linux-hardware.org/?probe=c9bde314b5) | Jan 11, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [d014e736fc](https://linux-hardware.org/?probe=d014e736fc) | Jan 11, 2023 |
| Dell          | Latitude 9420               | Convertible | [1446885eb7](https://linux-hardware.org/?probe=1446885eb7) | Jan 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a7b0b9f2e](https://linux-hardware.org/?probe=9a7b0b9f2e) | Jan 10, 2023 |
| Medion        | MS-7728                     | Desktop     | [8310cf0974](https://linux-hardware.org/?probe=8310cf0974) | Jan 10, 2023 |
| HP            | 3048h                       | Desktop     | [e13a2bdf6e](https://linux-hardware.org/?probe=e13a2bdf6e) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [d665a7f0ff](https://linux-hardware.org/?probe=d665a7f0ff) | Jan 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | Notebook    | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [bd0adf87e3](https://linux-hardware.org/?probe=bd0adf87e3) | Jan 08, 2023 |
| ASUSTek       | K53U                        | Notebook    | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Alienware     | 17 R3                       | Notebook    | [f94b2fc95f](https://linux-hardware.org/?probe=f94b2fc95f) | Jan 08, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [97335b8723](https://linux-hardware.org/?probe=97335b8723) | Jan 07, 2023 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [ac69fa3d31](https://linux-hardware.org/?probe=ac69fa3d31) | Jan 07, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [03524fa074](https://linux-hardware.org/?probe=03524fa074) | Jan 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [7281c172f4](https://linux-hardware.org/?probe=7281c172f4) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [8e49c8c0b1](https://linux-hardware.org/?probe=8e49c8c0b1) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [ca8adec17c](https://linux-hardware.org/?probe=ca8adec17c) | Jan 06, 2023 |
| Medion        | MS-7728                     | Desktop     | [4b3e96394b](https://linux-hardware.org/?probe=4b3e96394b) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0016M... | Notebook    | [b48981da6d](https://linux-hardware.org/?probe=b48981da6d) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b329d8f40f](https://linux-hardware.org/?probe=b329d8f40f) | Jan 06, 2023 |
| Acer          | Predator G9-591             | Notebook    | [160b31ea8f](https://linux-hardware.org/?probe=160b31ea8f) | Jan 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0b9972387e](https://linux-hardware.org/?probe=0b9972387e) | Jan 05, 2023 |
| Medion        | MS-7728                     | Desktop     | [0ffef4911e](https://linux-hardware.org/?probe=0ffef4911e) | Jan 05, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8f519746c2](https://linux-hardware.org/?probe=8f519746c2) | Jan 04, 2023 |
| Medion        | MS-7728                     | Desktop     | [9c2439adf6](https://linux-hardware.org/?probe=9c2439adf6) | Jan 04, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [518b2272d4](https://linux-hardware.org/?probe=518b2272d4) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [b341980e6c](https://linux-hardware.org/?probe=b341980e6c) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d50cf83414](https://linux-hardware.org/?probe=d50cf83414) | Jan 04, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | Notebook    | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8c9e803e01](https://linux-hardware.org/?probe=8c9e803e01) | Jan 01, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [cc24dc6f72](https://linux-hardware.org/?probe=cc24dc6f72) | Dec 31, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [bf3922e95d](https://linux-hardware.org/?probe=bf3922e95d) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [82b86d954a](https://linux-hardware.org/?probe=82b86d954a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | Notebook    | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | Notebook    | [bcb9b7a061](https://linux-hardware.org/?probe=bcb9b7a061) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [a73fe5e678](https://linux-hardware.org/?probe=a73fe5e678) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [77ee14ad98](https://linux-hardware.org/?probe=77ee14ad98) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [1c022f7ff8](https://linux-hardware.org/?probe=1c022f7ff8) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [803a4e58e0](https://linux-hardware.org/?probe=803a4e58e0) | Dec 25, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b445490856](https://linux-hardware.org/?probe=b445490856) | Dec 25, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2d50f93c7f](https://linux-hardware.org/?probe=2d50f93c7f) | Dec 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [dac438be55](https://linux-hardware.org/?probe=dac438be55) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [e160bf6ea0](https://linux-hardware.org/?probe=e160bf6ea0) | Dec 22, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [e7bf0c0a09](https://linux-hardware.org/?probe=e7bf0c0a09) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [907ca44afe](https://linux-hardware.org/?probe=907ca44afe) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [9fca55febc](https://linux-hardware.org/?probe=9fca55febc) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [47397487a7](https://linux-hardware.org/?probe=47397487a7) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e954c9ca37](https://linux-hardware.org/?probe=e954c9ca37) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [57605a26eb](https://linux-hardware.org/?probe=57605a26eb) | Dec 19, 2022 |
| ASUSTek       | PN64                        | Mini pc     | [a5fdbdb0c8](https://linux-hardware.org/?probe=a5fdbdb0c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3a6e0b953f](https://linux-hardware.org/?probe=3a6e0b953f) | Dec 19, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [7a528ca531](https://linux-hardware.org/?probe=7a528ca531) | Dec 17, 2022 |
| Acer          | Aspire E5-773               | Notebook    | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [1129626fee](https://linux-hardware.org/?probe=1129626fee) | Dec 13, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [9f0f4a8510](https://linux-hardware.org/?probe=9f0f4a8510) | Dec 12, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [f7577f248a](https://linux-hardware.org/?probe=f7577f248a) | Dec 12, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [787ba0950d](https://linux-hardware.org/?probe=787ba0950d) | Dec 11, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [9ed715edc4](https://linux-hardware.org/?probe=9ed715edc4) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3282a529f0](https://linux-hardware.org/?probe=3282a529f0) | Dec 11, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [6c26c9ff8c](https://linux-hardware.org/?probe=6c26c9ff8c) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [c3c6c2f4fc](https://linux-hardware.org/?probe=c3c6c2f4fc) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [62986b3426](https://linux-hardware.org/?probe=62986b3426) | Dec 08, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [637056cc12](https://linux-hardware.org/?probe=637056cc12) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [15ca126de2](https://linux-hardware.org/?probe=15ca126de2) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [eef6c9c624](https://linux-hardware.org/?probe=eef6c9c624) | Dec 08, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [439e89b31f](https://linux-hardware.org/?probe=439e89b31f) | Dec 07, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [f2ba8a7d55](https://linux-hardware.org/?probe=f2ba8a7d55) | Dec 06, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [927991f54f](https://linux-hardware.org/?probe=927991f54f) | Dec 06, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [ee9c9e919b](https://linux-hardware.org/?probe=ee9c9e919b) | Dec 05, 2022 |
| HP            | ENVY dv7                    | Notebook    | [8e8b9ecfb6](https://linux-hardware.org/?probe=8e8b9ecfb6) | Dec 04, 2022 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [9a0718a60f](https://linux-hardware.org/?probe=9a0718a60f) | Dec 04, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | Notebook    | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Acer          | Predator PH317-56           | Notebook    | [ea1d794b18](https://linux-hardware.org/?probe=ea1d794b18) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [19395b5e21](https://linux-hardware.org/?probe=19395b5e21) | Dec 02, 2022 |
| HP            | ProBook 6560b               | Notebook    | [c62ff16666](https://linux-hardware.org/?probe=c62ff16666) | Dec 02, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [13b2f864f8](https://linux-hardware.org/?probe=13b2f864f8) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8e0ea55ccc](https://linux-hardware.org/?probe=8e0ea55ccc) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [7817399ec6](https://linux-hardware.org/?probe=7817399ec6) | Dec 02, 2022 |
| HP            | ENVY dv7                    | Notebook    | [60e3263ce2](https://linux-hardware.org/?probe=60e3263ce2) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| HP            | ENVY dv7                    | Notebook    | [1cef09f19a](https://linux-hardware.org/?probe=1cef09f19a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [8d98938198](https://linux-hardware.org/?probe=8d98938198) | Nov 30, 2022 |
| Dell          | 0Y2G81 A01                  | Server      | [7ce42afb90](https://linux-hardware.org/?probe=7ce42afb90) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d233ee2114](https://linux-hardware.org/?probe=d233ee2114) | Nov 30, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [8d37e3e327](https://linux-hardware.org/?probe=8d37e3e327) | Nov 29, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [e41751f26a](https://linux-hardware.org/?probe=e41751f26a) | Nov 29, 2022 |
| Notebook      | L140PU                      | Notebook    | [8893420e06](https://linux-hardware.org/?probe=8893420e06) | Nov 28, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [d353a1624b](https://linux-hardware.org/?probe=d353a1624b) | Nov 28, 2022 |
| Pegatron      | VIOLET                      | Desktop     | [f0f25e6854](https://linux-hardware.org/?probe=f0f25e6854) | Nov 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [15ee6e2e20](https://linux-hardware.org/?probe=15ee6e2e20) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8e266a1137](https://linux-hardware.org/?probe=8e266a1137) | Nov 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [3ba26453f1](https://linux-hardware.org/?probe=3ba26453f1) | Nov 24, 2022 |
| Nvidia        | Tegra                       | Soc         | [b565b4082e](https://linux-hardware.org/?probe=b565b4082e) | Nov 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [90f931841d](https://linux-hardware.org/?probe=90f931841d) | Nov 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [111f6a1fc2](https://linux-hardware.org/?probe=111f6a1fc2) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | Notebook    | [080bbeb75a](https://linux-hardware.org/?probe=080bbeb75a) | Nov 22, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [b5ed1b189a](https://linux-hardware.org/?probe=b5ed1b189a) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [54f10b9d0b](https://linux-hardware.org/?probe=54f10b9d0b) | Nov 21, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [576ca67a28](https://linux-hardware.org/?probe=576ca67a28) | Nov 21, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [65c874adbd](https://linux-hardware.org/?probe=65c874adbd) | Nov 20, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b25dd25478](https://linux-hardware.org/?probe=b25dd25478) | Nov 20, 2022 |
| Dell          | XPS 9320                    | Notebook    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| HP            | 212B                        | Desktop     | [574a94ad86](https://linux-hardware.org/?probe=574a94ad86) | Nov 18, 2022 |
| HP            | 212B                        | Desktop     | [3995268826](https://linux-hardware.org/?probe=3995268826) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | Notebook    | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b3e809f3d2](https://linux-hardware.org/?probe=b3e809f3d2) | Nov 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | Notebook    | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| HP            | Compaq 15                   | Notebook    | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| GPD           | G1619-04                    | Notebook    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [71a871168d](https://linux-hardware.org/?probe=71a871168d) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c6c7120833](https://linux-hardware.org/?probe=c6c7120833) | Nov 15, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [5682e576ad](https://linux-hardware.org/?probe=5682e576ad) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [2053688baa](https://linux-hardware.org/?probe=2053688baa) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [15f6c6a1aa](https://linux-hardware.org/?probe=15f6c6a1aa) | Nov 14, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [3726e23d23](https://linux-hardware.org/?probe=3726e23d23) | Nov 14, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [f320cc2659](https://linux-hardware.org/?probe=f320cc2659) | Nov 11, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [d2e25c9c4e](https://linux-hardware.org/?probe=d2e25c9c4e) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [33a4a1ea9a](https://linux-hardware.org/?probe=33a4a1ea9a) | Nov 09, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [ff7014b9b8](https://linux-hardware.org/?probe=ff7014b9b8) | Nov 06, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [69c1a004e6](https://linux-hardware.org/?probe=69c1a004e6) | Nov 03, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [9224a599b3](https://linux-hardware.org/?probe=9224a599b3) | Nov 03, 2022 |
| HP            | 8458                        | Mini pc     | [4da864256d](https://linux-hardware.org/?probe=4da864256d) | Nov 03, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | Desktop     | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fd4d484f61](https://linux-hardware.org/?probe=fd4d484f61) | Nov 02, 2022 |
| Dell          | Precision 5520              | Notebook    | [e1a819ec3e](https://linux-hardware.org/?probe=e1a819ec3e) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| GPD           | G1619-04                    | Notebook    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1e1f105579](https://linux-hardware.org/?probe=1e1f105579) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [19cddcf899](https://linux-hardware.org/?probe=19cddcf899) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2W30... | Notebook    | [8e0c00531b](https://linux-hardware.org/?probe=8e0c00531b) | Oct 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6047d5d94a](https://linux-hardware.org/?probe=6047d5d94a) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |
| Dell          | Latitude E4310              | Notebook    | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b5d48f6adb](https://linux-hardware.org/?probe=b5d48f6adb) | Oct 29, 2022 |
| Lenovo        | ThinkPad T420 4236NUG       | Notebook    | [d0e3fa9699](https://linux-hardware.org/?probe=d0e3fa9699) | Oct 28, 2022 |
| HP            | 3396                        | Desktop     | [d42479acb8](https://linux-hardware.org/?probe=d42479acb8) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [9a540d96f5](https://linux-hardware.org/?probe=9a540d96f5) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c55b37c393](https://linux-hardware.org/?probe=c55b37c393) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c3bbb31b04](https://linux-hardware.org/?probe=c3bbb31b04) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [849800f3f3](https://linux-hardware.org/?probe=849800f3f3) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Acer          | WG43M                       | Desktop     | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b81dd63334](https://linux-hardware.org/?probe=b81dd63334) | Oct 21, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [55a46537f8](https://linux-hardware.org/?probe=55a46537f8) | Oct 21, 2022 |
| Medion        | S15449                      | Notebook    | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a83d0f0ade](https://linux-hardware.org/?probe=a83d0f0ade) | Oct 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [f5073cd7a2](https://linux-hardware.org/?probe=f5073cd7a2) | Oct 20, 2022 |
| HP            | 829A                        | Mini pc     | [3470bd9a76](https://linux-hardware.org/?probe=3470bd9a76) | Oct 17, 2022 |
| HP            | 829A                        | Mini pc     | [3ab01040ef](https://linux-hardware.org/?probe=3ab01040ef) | Oct 17, 2022 |
| MSI           | H170I PRO AC                | Desktop     | [ea4ecf6238](https://linux-hardware.org/?probe=ea4ecf6238) | Oct 17, 2022 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | Notebook    | [3e8ca06ac6](https://linux-hardware.org/?probe=3e8ca06ac6) | Oct 17, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [5d60b980ca](https://linux-hardware.org/?probe=5d60b980ca) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| Google        | Lars                        | Notebook    | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| HP            | ENVY 15                     | Notebook    | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [9d2cf83f81](https://linux-hardware.org/?probe=9d2cf83f81) | Oct 12, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [feb997ebfc](https://linux-hardware.org/?probe=feb997ebfc) | Oct 12, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [67532c45cb](https://linux-hardware.org/?probe=67532c45cb) | Oct 12, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [5112d236ce](https://linux-hardware.org/?probe=5112d236ce) | Oct 12, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [10e153f71e](https://linux-hardware.org/?probe=10e153f71e) | Oct 10, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [ee62bfc634](https://linux-hardware.org/?probe=ee62bfc634) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [a3a056691b](https://linux-hardware.org/?probe=a3a056691b) | Oct 07, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [7f03ff4490](https://linux-hardware.org/?probe=7f03ff4490) | Oct 07, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [e48bdade3d](https://linux-hardware.org/?probe=e48bdade3d) | Oct 06, 2022 |
| Dell          | Latitude E6410              | Notebook    | [f7baa71813](https://linux-hardware.org/?probe=f7baa71813) | Oct 05, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [24da875cf7](https://linux-hardware.org/?probe=24da875cf7) | Oct 04, 2022 |
| HP            | 213D A01                    | Desktop     | [e81fd5fea5](https://linux-hardware.org/?probe=e81fd5fea5) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [e4cc03e802](https://linux-hardware.org/?probe=e4cc03e802) | Oct 03, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6a5067b548](https://linux-hardware.org/?probe=6a5067b548) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2044c11c98](https://linux-hardware.org/?probe=2044c11c98) | Oct 02, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [e405dee0bd](https://linux-hardware.org/?probe=e405dee0bd) | Oct 02, 2022 |
| MSI           | 2A9C                        | Desktop     | [a933ad6bca](https://linux-hardware.org/?probe=a933ad6bca) | Oct 01, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [5e38213b3b](https://linux-hardware.org/?probe=5e38213b3b) | Sep 30, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [744143bdd6](https://linux-hardware.org/?probe=744143bdd6) | Sep 30, 2022 |
| Acer          | Spin SP111-32N              | Convertible | [6c3ab0f793](https://linux-hardware.org/?probe=6c3ab0f793) | Sep 27, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [9a1514cc61](https://linux-hardware.org/?probe=9a1514cc61) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3c87156766](https://linux-hardware.org/?probe=3c87156766) | Sep 25, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [fee2b2d57e](https://linux-hardware.org/?probe=fee2b2d57e) | Sep 24, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6f492f55c3](https://linux-hardware.org/?probe=6f492f55c3) | Sep 24, 2022 |
| Acer          | Spin SP111-32N              | Convertible | [75ed13ea90](https://linux-hardware.org/?probe=75ed13ea90) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [f9c071cdd8](https://linux-hardware.org/?probe=f9c071cdd8) | Sep 23, 2022 |
| System76      | Darter Pro                  | Notebook    | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| HP            | 8053                        | Desktop     | [d46ac6d7db](https://linux-hardware.org/?probe=d46ac6d7db) | Sep 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [074a9f8433](https://linux-hardware.org/?probe=074a9f8433) | Sep 22, 2022 |
| System76      | Darter Pro                  | Notebook    | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [dc6bf82565](https://linux-hardware.org/?probe=dc6bf82565) | Sep 22, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [dddf15cbf5](https://linux-hardware.org/?probe=dddf15cbf5) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [21404b14d1](https://linux-hardware.org/?probe=21404b14d1) | Sep 21, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [3c274fc7f3](https://linux-hardware.org/?probe=3c274fc7f3) | Sep 19, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3aa36dda04](https://linux-hardware.org/?probe=3aa36dda04) | Sep 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [43bc9e36cd](https://linux-hardware.org/?probe=43bc9e36cd) | Sep 17, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [ec15390099](https://linux-hardware.org/?probe=ec15390099) | Sep 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [81d620ed2f](https://linux-hardware.org/?probe=81d620ed2f) | Sep 14, 2022 |
| HP            | Notebook                    | Notebook    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c54a63e1a3](https://linux-hardware.org/?probe=c54a63e1a3) | Sep 13, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [4aa1954c0c](https://linux-hardware.org/?probe=4aa1954c0c) | Sep 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e2d13711aa](https://linux-hardware.org/?probe=e2d13711aa) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | Notebook    | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [e72b842ab6](https://linux-hardware.org/?probe=e72b842ab6) | Sep 10, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [ce9d09e18a](https://linux-hardware.org/?probe=ce9d09e18a) | Sep 10, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [6a4fa8ebe7](https://linux-hardware.org/?probe=6a4fa8ebe7) | Sep 09, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [965f8fe14d](https://linux-hardware.org/?probe=965f8fe14d) | Sep 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [6c5483e3f5](https://linux-hardware.org/?probe=6c5483e3f5) | Sep 07, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| Dell          | 0GN6JF A01                  | Desktop     | [390fbaaca7](https://linux-hardware.org/?probe=390fbaaca7) | Sep 05, 2022 |
| HP            | 8076                        | Desktop     | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| Acer          | Aspire S5-371               | Notebook    | [ed31a97b57](https://linux-hardware.org/?probe=ed31a97b57) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [08cfa37b81](https://linux-hardware.org/?probe=08cfa37b81) | Sep 03, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 304       | 12.16%  |
| Ubuntu 18.04                 | 271       | 10.84%  |
| Ubuntu 22.04                 | 229       | 9.16%   |
| Debian 11                    | 95        | 3.8%    |
| Linux Mint 20.3              | 56        | 2.24%   |
| OpenMandriva 4.3             | 43        | 1.72%   |
| Debian 10                    | 41        | 1.64%   |
| Ubuntu 21.10                 | 38        | 1.52%   |
| Arch Rolling                 | 37        | 1.48%   |
| openSUSE Tumbleweed-XXXXXXXX | 36        | 1.44%   |
| Linux Mint 20.2              | 36        | 1.44%   |
| Linux Mint 20.1              | 36        | 1.44%   |
| KDE neon 20.04               | 36        | 1.44%   |
| Zorin 16                     | 32        | 1.28%   |
| OpenMandriva 4.2             | 31        | 1.24%   |
| Linux Mint 21.1              | 30        | 1.2%    |
| Pop!_OS 22.04                | 28        | 1.12%   |
| Arch                         | 28        | 1.12%   |
| Manjaro                      | 27        | 1.08%   |
| Ubuntu 20.10                 | 25        | 1%      |
| Fedora 38                    | 25        | 1%      |
| OpenMandriva 23.01           | 24        | 0.96%   |
| Fedora 32                    | 24        | 0.96%   |
| Ubuntu 22.10                 | 23        | 0.92%   |
| Fedora 37                    | 23        | 0.92%   |
| Ubuntu 21.04                 | 22        | 0.88%   |
| Fedora 34                    | 22        | 0.88%   |
| Ubuntu 19.10                 | 21        | 0.84%   |
| Pop!_OS 21.04                | 21        | 0.84%   |
| Pop!_OS 20.10                | 21        | 0.84%   |
| Pop!_OS 20.04                | 21        | 0.84%   |
| Fedora 33                    | 21        | 0.84%   |
| ArcoLinux Rolling            | 21        | 0.84%   |
| Ubuntu 19.04                 | 20        | 0.8%    |
| Fedora 35                    | 20        | 0.8%    |
| Linux Mint 19.3              | 19        | 0.76%   |
| Ubuntu 23.04                 | 18        | 0.72%   |
| OpenMandriva 23.03           | 16        | 0.64%   |
| Linux Mint 21                | 16        | 0.64%   |
| Fedora 36                    | 16        | 0.64%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 885       | 38.63%  |
| Linux Mint    | 204       | 8.9%    |
| Debian        | 176       | 7.68%   |
| Fedora        | 154       | 6.72%   |
| OpenMandriva  | 131       | 5.72%   |
| Pop!_OS       | 90        | 3.93%   |
| Manjaro       | 72        | 3.14%   |
| Arch          | 64        | 2.79%   |
| Kubuntu       | 51        | 2.23%   |
| openSUSE      | 48        | 2.1%    |
| Zorin         | 47        | 2.05%   |
| KDE neon      | 43        | 1.88%   |
| ROSA          | 26        | 1.13%   |
| Xubuntu       | 25        | 1.09%   |
| ArcoLinux     | 24        | 1.05%   |
| Ubuntu MATE   | 18        | 0.79%   |
| Kali          | 18        | 0.79%   |
| Gentoo        | 18        | 0.79%   |
| Elementary    | 16        | 0.7%    |
| Lubuntu       | 15        | 0.65%   |
| CentOS        | 12        | 0.52%   |
| EndeavourOS   | 11        | 0.48%   |
| Ubuntu Budgie | 10        | 0.44%   |
| Feren OS      | 10        | 0.44%   |
| Clear Linux   | 9         | 0.39%   |
| Ubuntu Unity  | 7         | 0.31%   |
| MX            | 7         | 0.31%   |
| LMDE          | 7         | 0.31%   |
| Endless       | 7         | 0.31%   |
| BlackPanther  | 7         | 0.31%   |
| SteamOS       | 5         | 0.22%   |
| RHEL          | 5         | 0.22%   |
| Artix         | 5         | 0.22%   |
| Void Linux    | 4         | 0.17%   |
| TUXEDO OS     | 4         | 0.17%   |
| Parrot        | 4         | 0.17%   |
| NixOS         | 4         | 0.17%   |
| Garuda Linux  | 4         | 0.17%   |
| Xero          | 3         | 0.13%   |
| Virtuozzo     | 3         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.15.0-88-generic        | 44        | 1.57%   |
| 5.16.7-desktop-1omv4003  | 38        | 1.36%   |
| 5.15.0-67-generic        | 35        | 1.25%   |
| 5.15.0-58-generic        | 33        | 1.18%   |
| 5.4.0-42-generic         | 32        | 1.14%   |
| 5.15.0-56-generic        | 31        | 1.11%   |
| 5.15.0-69-generic        | 30        | 1.07%   |
| 5.10.14-desktop-1omv4002 | 30        | 1.07%   |
| 4.15.0-91-generic        | 27        | 0.97%   |
| 5.15.0-46-generic        | 25        | 0.89%   |
| 5.4.0-52-generic         | 22        | 0.79%   |
| 5.4.0-48-generic         | 22        | 0.79%   |
| 5.19.0-35-generic        | 22        | 0.79%   |
| 4.15.0-96-generic        | 22        | 0.79%   |
| 5.4.0-58-generic         | 21        | 0.75%   |
| 6.1.1-desktop-1omv2290   | 20        | 0.72%   |
| 5.10.0-8-arm64           | 17        | 0.61%   |
| 6.2.6-desktop-1omv2390   | 16        | 0.57%   |
| 5.8.0-43-generic         | 15        | 0.54%   |
| 5.4.0-91-generic         | 15        | 0.54%   |
| 5.15.0-60-generic        | 15        | 0.54%   |
| 5.10.0-21-amd64          | 15        | 0.54%   |
| 5.13.0-35-generic        | 14        | 0.5%    |
| 5.4.0-80-generic         | 13        | 0.46%   |
| 5.4.0-26-generic         | 13        | 0.46%   |
| 5.15.0-52-generic        | 13        | 0.46%   |
| 5.11.0-43-generic        | 13        | 0.46%   |
| 5.11.0-27-generic        | 13        | 0.46%   |
| 5.4.0-81-generic         | 12        | 0.43%   |
| 5.4.0-47-generic         | 12        | 0.43%   |
| 5.15.0-48-generic        | 12        | 0.43%   |
| 5.15.0-43-generic        | 12        | 0.43%   |
| 5.13.0-39-generic        | 12        | 0.43%   |
| 5.13.0-30-generic        | 12        | 0.43%   |
| 5.10.0-8-amd64           | 12        | 0.43%   |
| 5.0.0-37-generic         | 12        | 0.43%   |
| 5.8.0-55-generic         | 11        | 0.39%   |
| 5.8.0-53-generic         | 11        | 0.39%   |
| 5.8.0-48-generic         | 11        | 0.39%   |
| 5.8.0-44-generic         | 11        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 378       | 14.49%  |
| 5.15.0  | 310       | 11.89%  |
| 4.15.0  | 206       | 7.9%    |
| 5.8.0   | 128       | 4.91%   |
| 5.11.0  | 117       | 4.49%   |
| 5.13.0  | 107       | 4.1%    |
| 5.10.0  | 97        | 3.72%   |
| 5.19.0  | 84        | 3.22%   |
| 5.3.0   | 72        | 2.76%   |
| 5.0.0   | 50        | 1.92%   |
| 6.2.0   | 42        | 1.61%   |
| 4.18.0  | 42        | 1.61%   |
| 5.16.7  | 39        | 1.5%    |
| 4.19.0  | 38        | 1.46%   |
| 5.10.14 | 31        | 1.19%   |
| 6.1.0   | 28        | 1.07%   |
| 6.1.1   | 24        | 0.92%   |
| 6.2.6   | 22        | 0.84%   |
| 5.14.0  | 15        | 0.58%   |
| 5.17.5  | 13        | 0.5%    |
| 6.0.0   | 12        | 0.46%   |
| 5.6.0   | 11        | 0.42%   |
| 5.7.0   | 9         | 0.35%   |
| 5.18.0  | 9         | 0.35%   |
| 5.16.13 | 8         | 0.31%   |
| 3.10.0  | 8         | 0.31%   |
| 6.4.11  | 7         | 0.27%   |
| 6.0.12  | 7         | 0.27%   |
| 5.10.7  | 7         | 0.27%   |
| 4.9.60  | 7         | 0.27%   |
| 6.3.5   | 6         | 0.23%   |
| 6.0.7   | 6         | 0.23%   |
| 6.0.15  | 6         | 0.23%   |
| 5.6.14  | 6         | 0.23%   |
| 5.3.18  | 6         | 0.23%   |
| 5.16.0  | 6         | 0.23%   |
| 4.18.16 | 6         | 0.23%   |
| 6.2.9   | 5         | 0.19%   |
| 5.9.16  | 5         | 0.19%   |
| 5.9.11  | 5         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 397       | 15.48%  |
| 5.15    | 364       | 14.2%   |
| 4.15    | 207       | 8.07%   |
| 5.10    | 168       | 6.55%   |
| 5.8     | 161       | 6.28%   |
| 5.11    | 146       | 5.69%   |
| 5.13    | 124       | 4.84%   |
| 5.19    | 97        | 3.78%   |
| 6.2     | 89        | 3.47%   |
| 5.3     | 85        | 3.32%   |
| 6.1     | 82        | 3.2%    |
| 5.16    | 75        | 2.93%   |
| 5.0     | 55        | 2.15%   |
| 6.0     | 50        | 1.95%   |
| 4.18    | 50        | 1.95%   |
| 4.19    | 45        | 1.76%   |
| 5.6     | 41        | 1.6%    |
| 5.17    | 38        | 1.48%   |
| 5.14    | 38        | 1.48%   |
| 5.9     | 29        | 1.13%   |
| 5.7     | 29        | 1.13%   |
| 6.4     | 28        | 1.09%   |
| 5.18    | 28        | 1.09%   |
| 6.3     | 26        | 1.01%   |
| 5.12    | 25        | 0.98%   |
| 4.9     | 23        | 0.9%    |
| 5.5     | 11        | 0.43%   |
| 6.5     | 9         | 0.35%   |
| 3.10    | 8         | 0.31%   |
| 4.4     | 5         | 0.2%    |
| 4.14    | 4         | 0.16%   |
| 5.2     | 3         | 0.12%   |
| 4.20    | 3         | 0.12%   |
| 4.13    | 3         | 0.12%   |
| 4.1     | 3         | 0.12%   |
| 2.6     | 3         | 0.12%   |
| 4.10    | 2         | 0.08%   |
| 3.16    | 2         | 0.08%   |
| 5.1     | 1         | 0.04%   |
| 5       | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2136      | 96.61%  |
| aarch64 | 40        | 1.81%   |
| i686    | 33        | 1.49%   |
| armv8l  | 1         | 0.05%   |
| armv7l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 928       | 40.16%  |
| KDE5            | 351       | 15.19%  |
| Unknown         | 316       | 13.67%  |
| X-Cinnamon      | 163       | 7.05%   |
| GNUstep         | 153       | 6.62%   |
| XFCE            | 115       | 4.98%   |
| MATE            | 59        | 2.55%   |
| KDE             | 43        | 1.86%   |
| Cinnamon        | 35        | 1.51%   |
| LXQt            | 23        | 1%      |
| Pantheon        | 17        | 0.74%   |
| KDE4            | 17        | 0.74%   |
| i3              | 17        | 0.74%   |
| LXDE            | 16        | 0.69%   |
| Budgie          | 15        | 0.65%   |
| GNOME Flashback | 13        | 0.56%   |
| Unity           | 6         | 0.26%   |
| bspwm           | 5         | 0.22%   |
| qtile           | 4         | 0.17%   |
| Trinity         | 2         | 0.09%   |
| sway            | 2         | 0.09%   |
| GNOME Classic   | 2         | 0.09%   |
| DWM             | 2         | 0.09%   |
| xmonad          | 1         | 0.04%   |
| openbox         | 1         | 0.04%   |
| none+awesome    | 1         | 0.04%   |
| ICEWM           | 1         | 0.04%   |
| herbstluftwm    | 1         | 0.04%   |
| fluxbox         | 1         | 0.04%   |
| awesome         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1578      | 67.35%  |
| Wayland | 421       | 17.97%  |
| Unknown | 178       | 7.6%    |
| Tty     | 163       | 6.96%   |
| Web     | 3         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 954       | 41.01%  |
| LightDM | 409       | 17.58%  |
| SDDM    | 308       | 13.24%  |
| GDM     | 284       | 12.21%  |
| GDM3    | 266       | 11.44%  |
| TDM     | 80        | 3.44%   |
| KDM     | 15        | 0.64%   |
| XDM     | 4         | 0.17%   |
| SLiM    | 3         | 0.13%   |
| NODM    | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 820       | 35.28%  |
| de_CH      | 527       | 22.68%  |
| Unknown    | 354       | 15.23%  |
| fr_CH      | 159       | 6.84%   |
| de_DE      | 150       | 6.45%   |
| en_GB      | 99        | 4.26%   |
| C          | 47        | 2.02%   |
| fr_FR      | 45        | 1.94%   |
| it_IT      | 19        | 0.82%   |
| it_CH      | 19        | 0.82%   |
| pt_PT      | 17        | 0.73%   |
| pl_PL      | 9         | 0.39%   |
| es_ES      | 9         | 0.39%   |
| ru_RU      | 7         | 0.3%    |
| en_CH      | 7         | 0.3%    |
| en_AU      | 5         | 0.22%   |
| de_AT      | 4         | 0.17%   |
| POSIX      | 3         | 0.13%   |
| en_IE      | 3         | 0.13%   |
| en_CA      | 2         | 0.09%   |
| en_AG      | 2         | 0.09%   |
| de_IT      | 2         | 0.09%   |
| tr_TR      | 1         | 0.04%   |
| sk_SK      | 1         | 0.04%   |
| ru_UA      | 1         | 0.04%   |
| pt_BR      | 1         | 0.04%   |
| nl_BE      | 1         | 0.04%   |
| hu_HU      | 1         | 0.04%   |
| hsb_DE     | 1         | 0.04%   |
| gsw_CH     | 1         | 0.04%   |
| fr_CA      | 1         | 0.04%   |
| fi_FI      | 1         | 0.04%   |
| de_LI      | 1         | 0.04%   |
| de_CH.UTF8 | 1         | 0.04%   |
| cs_CZ      | 1         | 0.04%   |
| ca_ES      | 1         | 0.04%   |
| C.UTF8     | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1269      | 56.08%  |
| BIOS | 994       | 43.92%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1756      | 77.22%  |
| Btrfs   | 204       | 8.97%   |
| Overlay | 142       | 6.24%   |
| Unknown | 65        | 2.86%   |
| Xfs     | 41        | 1.8%    |
| Tmpfs   | 35        | 1.54%   |
| Zfs     | 13        | 0.57%   |
| Ext2    | 6         | 0.26%   |
| Ext3    | 5         | 0.22%   |
| F2fs    | 4         | 0.18%   |
| Jfs     | 1         | 0.04%   |
| ExX4    | 1         | 0.04%   |
| Aufs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1068      | 47.07%  |
| Unknown | 958       | 42.22%  |
| MBR     | 243       | 10.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1920      | 84.84%  |
| Yes       | 343       | 15.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1692      | 75.13%  |
| Yes       | 560       | 24.87%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 421       | 19.06%  |
| Hewlett-Packard         | 367       | 16.61%  |
| Lenovo                  | 359       | 16.25%  |
| Dell                    | 178       | 8.06%   |
| Acer                    | 124       | 5.61%   |
| Gigabyte Technology     | 96        | 4.35%   |
| Apple                   | 88        | 3.98%   |
| MSI                     | 73        | 3.3%    |
| Intel                   | 68        | 3.08%   |
| ASRock                  | 66        | 2.99%   |
| Fujitsu                 | 41        | 1.86%   |
| Raspberry Pi Foundation | 34        | 1.54%   |
| Medion                  | 30        | 1.36%   |
| Supermicro              | 19        | 0.86%   |
| Toshiba                 | 17        | 0.77%   |
| Microsoft               | 17        | 0.77%   |
| Sony                    | 15        | 0.68%   |
| TUXEDO                  | 14        | 0.63%   |
| Samsung Electronics     | 12        | 0.54%   |
| Notebook                | 12        | 0.54%   |
| Unknown                 | 11        | 0.5%    |
| Shuttle                 | 9         | 0.41%   |
| HUAWEI                  | 9         | 0.41%   |
| ZOTAC                   | 8         | 0.36%   |
| TrekStor                | 7         | 0.32%   |
| Pegatron                | 7         | 0.32%   |
| PC Engines              | 7         | 0.32%   |
| Razer                   | 6         | 0.27%   |
| DALCO AG Switzerland    | 6         | 0.27%   |
| Alienware               | 6         | 0.27%   |
| Schenker                | 5         | 0.23%   |
| Packard Bell            | 5         | 0.23%   |
| Valve                   | 4         | 0.18%   |
| Timi                    | 3         | 0.14%   |
| PC Specialist           | 3         | 0.14%   |
| GPD                     | 3         | 0.14%   |
| Fujitsu Siemens         | 3         | 0.14%   |
| Clevo                   | 3         | 0.14%   |
| Biostar                 | 3         | 0.14%   |
| AMI                     | 3         | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 34        | 1.54%   |
| Unknown                                    | 18        | 0.81%   |
| ASUS PRIME Z590-P                          | 17        | 0.77%   |
| Fujitsu CELSIUS_W550                       | 12        | 0.54%   |
| ASUS PRIME X570-PRO                        | 12        | 0.54%   |
| ASUS ROG STRIX X570-E GAMING               | 11        | 0.5%    |
| RPi Raspberry Pi 4 Model B Rev 1.2         | 10        | 0.45%   |
| ASUS PRIME B550M-A                         | 10        | 0.45%   |
| RPi Raspberry Pi 4 Model B Rev 1.1         | 9         | 0.41%   |
| RPi Raspberry Pi 3 Model B Rev 1.2         | 8         | 0.36%   |
| HP Pavilion dv7                            | 8         | 0.36%   |
| ASUS STRIX Z270F GAMING                    | 8         | 0.36%   |
| MSI MS-7C02                                | 7         | 0.32%   |
| Dell Latitude 7490                         | 7         | 0.32%   |
| ASUS P9X79 WS                              | 7         | 0.32%   |
| ASUS P8Z77-V LX                            | 7         | 0.32%   |
| Microsoft Surface Pro 4                    | 6         | 0.27%   |
| DALCO AG Switzerland +41 44 908 38 38      | 6         | 0.27%   |
| Apple iMac12,2                             | 6         | 0.27%   |
| PC Engines APU2                            | 5         | 0.23%   |
| Intel S4600LH                              | 5         | 0.23%   |
| Intel DP67BA AAG10219-303                  | 5         | 0.23%   |
| HP Pavilion dv6                            | 5         | 0.23%   |
| HP Notebook                                | 5         | 0.23%   |
| HP ENVY 15                                 | 5         | 0.23%   |
| HP EliteDesk 800 G1 SFF                    | 5         | 0.23%   |
| Fujitsu CELSIUS W570                       | 5         | 0.23%   |
| Dell XPS 15 9570                           | 5         | 0.23%   |
| Dell OptiPlex 9020                         | 5         | 0.23%   |
| Dell OptiPlex 7010                         | 5         | 0.23%   |
| Dell Latitude E7240                        | 5         | 0.23%   |
| ASUS ROG STRIX Z370-F GAMING               | 5         | 0.23%   |
| Apple MacBookPro9,2                        | 5         | 0.23%   |
| Apple MacBookPro8,1                        | 5         | 0.23%   |
| Apple iMac8,1                              | 5         | 0.23%   |
| Apple iMac13,1                             | 5         | 0.23%   |
| Valve Jupiter                              | 4         | 0.18%   |
| Supermicro X8DTN+-F                        | 4         | 0.18%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW | 4         | 0.18%   |
| Lenovo MIIX 310-10ICR 80SG                 | 4         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 225       | 10.19%  |
| ASUS ROG           | 78        | 3.53%   |
| ASUS PRIME         | 77        | 3.49%   |
| Acer Aspire        | 73        | 3.3%    |
| HP EliteBook       | 68        | 3.08%   |
| HP Pavilion        | 57        | 2.58%   |
| Dell XPS           | 53        | 2.4%    |
| Dell Latitude      | 52        | 2.35%   |
| HP ProBook         | 39        | 1.77%   |
| Lenovo Yoga        | 36        | 1.63%   |
| RPi Raspberry      | 34        | 1.54%   |
| HP ENVY            | 34        | 1.54%   |
| ASUS All           | 34        | 1.54%   |
| Dell OptiPlex      | 32        | 1.45%   |
| Fujitsu CELSIUS    | 28        | 1.27%   |
| HP Compaq          | 25        | 1.13%   |
| HP EliteDesk       | 23        | 1.04%   |
| Lenovo IdeaPad     | 21        | 0.95%   |
| ASUS TUF           | 20        | 0.91%   |
| ASUS VivoBook      | 19        | 0.86%   |
| HP Laptop          | 18        | 0.81%   |
| Unknown            | 18        | 0.81%   |
| Microsoft Surface  | 17        | 0.77%   |
| HP ZBook           | 15        | 0.68%   |
| Dell Inspiron      | 15        | 0.68%   |
| Acer Swift         | 14        | 0.63%   |
| Dell Precision     | 13        | 0.59%   |
| Toshiba Satellite  | 11        | 0.5%    |
| Lenovo ThinkCentre | 11        | 0.5%    |
| Lenovo IdeaPadFlex | 11        | 0.5%    |
| ASUS ZenBook       | 11        | 0.5%    |
| ASUS STRIX         | 10        | 0.45%   |
| Lenovo Legion      | 9         | 0.41%   |
| HP Spectre         | 9         | 0.41%   |
| HP ProLiant        | 9         | 0.41%   |
| HP ProDesk         | 9         | 0.41%   |
| Gigabyte X570      | 9         | 0.41%   |
| ASUS P9X79         | 9         | 0.41%   |
| Apple iMac12       | 9         | 0.41%   |
| Acer Predator      | 9         | 0.41%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 225       | 10.19%  |
| 2019    | 221       | 10%     |
| 2020    | 208       | 9.42%   |
| 2017    | 174       | 7.88%   |
| 2012    | 162       | 7.33%   |
| 2021    | 150       | 6.79%   |
| 2011    | 143       | 6.47%   |
| 2014    | 131       | 5.93%   |
| 2013    | 131       | 5.93%   |
| 2015    | 127       | 5.75%   |
| 2016    | 111       | 5.02%   |
| 2010    | 98        | 4.44%   |
| 2022    | 91        | 4.12%   |
| 2008    | 64        | 2.9%    |
| 2009    | 58        | 2.63%   |
| 2007    | 36        | 1.63%   |
| Unknown | 29        | 1.31%   |
| 2023    | 24        | 1.09%   |
| 2006    | 16        | 0.72%   |
| 2005    | 6         | 0.27%   |
| 2004    | 3         | 0.14%   |
| 2003    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1004      | 45.45%  |
| Desktop        | 846       | 38.3%   |
| Convertible    | 121       | 5.48%   |
| Mini pc        | 54        | 2.44%   |
| All in one     | 53        | 2.4%    |
| Server         | 51        | 2.31%   |
| System on chip | 39        | 1.77%   |
| Tablet         | 38        | 1.72%   |
| Phone          | 3         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2027      | 90.98%  |
| Enabled  | 201       | 9.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2194      | 99.32%  |
| Yes  | 15        | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 557       | 24.7%   |
| 32.01-64.0      | 370       | 16.41%  |
| 4.01-8.0        | 366       | 16.23%  |
| 8.01-16.0       | 356       | 15.79%  |
| 3.01-4.0        | 271       | 12.02%  |
| 64.01-256.0     | 158       | 7.01%   |
| 1.01-2.0        | 56        | 2.48%   |
| 24.01-32.0      | 55        | 2.44%   |
| More than 256.0 | 27        | 1.2%    |
| 0.51-1.0        | 22        | 0.98%   |
| 2.01-3.0        | 16        | 0.71%   |
| 0.01-0.5        | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 776       | 30.85%  |
| 2.01-3.0        | 564       | 22.43%  |
| 4.01-8.0        | 421       | 16.74%  |
| 3.01-4.0        | 302       | 12.01%  |
| 0.51-1.0        | 179       | 7.12%   |
| 8.01-16.0       | 163       | 6.48%   |
| 0.01-0.5        | 45        | 1.79%   |
| 16.01-24.0      | 30        | 1.19%   |
| 24.01-32.0      | 11        | 0.44%   |
| 32.01-64.0      | 10        | 0.4%    |
| 64.01-256.0     | 8         | 0.32%   |
| Unknown         | 4         | 0.16%   |
| More than 256.0 | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1366      | 59.57%  |
| 2       | 545       | 23.77%  |
| 3       | 196       | 8.55%   |
| 4       | 73        | 3.18%   |
| 5       | 47        | 2.05%   |
| 6       | 22        | 0.96%   |
| 0       | 21        | 0.92%   |
| 7       | 17        | 0.74%   |
| 14      | 2         | 0.09%   |
| 11      | 1         | 0.04%   |
| 9       | 1         | 0.04%   |
| 8       | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1461      | 65.4%   |
| Yes       | 773       | 34.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1895      | 85.13%  |
| No        | 331       | 14.87%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1586      | 71.41%  |
| No        | 635       | 28.59%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1333      | 59.56%  |
| No        | 905       | 40.44%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 2209      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Zurich                             | 634       | 26.31%  |
| Bern                               | 112       | 4.65%   |
| Geneva                             | 86        | 3.57%   |
| Lucerne                            | 64        | 2.66%   |
| Lausanne                           | 40        | 1.66%   |
| Basel                              | 40        | 1.66%   |
| Winterthur                         | 36        | 1.49%   |
| Wiesendangen / Wiesendangen (Dorf) | 33        | 1.37%   |
| Neuchatel                          | 28        | 1.16%   |
| Thun                               | 26        | 1.08%   |
| Lugano                             | 21        | 0.87%   |
| Dietikon                           | 20        | 0.83%   |
| Lyss                               | 19        | 0.79%   |
| Wil                                | 17        | 0.71%   |
| St. Gallen                         | 17        | 0.71%   |
| Herrliberg                         | 14        | 0.58%   |
| Aarau                              | 13        | 0.54%   |
| Wettingen                          | 12        | 0.5%    |
| Sion                               | 12        | 0.5%    |
| Munchenstein                       | 12        | 0.5%    |
| Ittigen                            | 11        | 0.46%   |
| Dubendorf                          | 11        | 0.46%   |
| Biel/Bienne                        | 11        | 0.46%   |
| Willisau                           | 9         | 0.37%   |
| Uster                              | 9         | 0.37%   |
| Solothurn                          | 9         | 0.37%   |
| Schaffhausen                       | 9         | 0.37%   |
| Onex                               | 9         | 0.37%   |
| Oberwil-Lieli                      | 9         | 0.37%   |
| Kloten                             | 9         | 0.37%   |
| Glattbrugg                         | 9         | 0.37%   |
| Baden                              | 9         | 0.37%   |
| Zollikofen                         | 8         | 0.33%   |
| Widnau                             | 8         | 0.33%   |
| Wetzikon                           | 8         | 0.33%   |
| Wallisellen                        | 8         | 0.33%   |
| St. Moritz                         | 8         | 0.33%   |
| Prilly                             | 8         | 0.33%   |
| Morges                             | 8         | 0.33%   |
| Burgdorf                           | 8         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 831       | 1494   | 26.31%  |
| WDC                         | 435       | 707    | 13.77%  |
| Seagate                     | 366       | 532    | 11.59%  |
| SanDisk                     | 170       | 212    | 5.38%   |
| Toshiba                     | 154       | 213    | 4.87%   |
| Unknown                     | 146       | 221    | 4.62%   |
| Intel                       | 141       | 204    | 4.46%   |
| Hitachi                     | 101       | 139    | 3.2%    |
| SK hynix                    | 99        | 121    | 3.13%   |
| Kingston                    | 92        | 135    | 2.91%   |
| Crucial                     | 91        | 129    | 2.88%   |
| Micron Technology           | 57        | 72     | 1.8%    |
| Apple                       | 45        | 50     | 1.42%   |
| HGST                        | 36        | 46     | 1.14%   |
| Corsair                     | 27        | 32     | 0.85%   |
| OCZ                         | 25        | 30     | 0.79%   |
| A-DATA Technology           | 24        | 36     | 0.76%   |
| Intenso                     | 21        | 22     | 0.66%   |
| Phison                      | 19        | 30     | 0.6%    |
| LITEON                      | 19        | 25     | 0.6%    |
| LITEONIT                    | 14        | 16     | 0.44%   |
| KIOXIA                      | 14        | 21     | 0.44%   |
| Transcend                   | 13        | 23     | 0.41%   |
| Phison Electronics          | 13        | 24     | 0.41%   |
| China                       | 13        | 15     | 0.41%   |
| ASMT                        | 10        | 15     | 0.32%   |
| Hewlett-Packard             | 9         | 11     | 0.28%   |
| Silicon Motion              | 8         | 9      | 0.25%   |
| KingSpec                    | 8         | 13     | 0.25%   |
| Unknown                     | 8         | 8      | 0.25%   |
| SPCC                        | 7         | 8      | 0.22%   |
| Plextor                     | 7         | 8      | 0.22%   |
| JMicron Technology          | 7         | 7      | 0.22%   |
| Fujitsu                     | 7         | 10     | 0.22%   |
| Micron/Crucial Technology   | 6         | 9      | 0.19%   |
| LaCie                       | 6         | 6      | 0.19%   |
| Patriot                     | 5         | 6      | 0.16%   |
| Kingston Technology Company | 5         | 5      | 0.16%   |
| HPE                         | 5         | 12     | 0.16%   |
| Realtek Semiconductor       | 4         | 5      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB                           | 43        | 1.21%   |
| Samsung SSD 850 EVO 250GB                           | 37        | 1.04%   |
| Samsung SSD 860 EVO 1TB                             | 35        | 0.99%   |
| Samsung NVMe SSD Drive 1TB                          | 34        | 0.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 34        | 0.96%   |
| Samsung SSD 860 EVO 500GB                           | 29        | 0.82%   |
| Samsung SSD 980 PRO 1TB                             | 27        | 0.76%   |
| Samsung SSD 860 EVO 250GB                           | 27        | 0.76%   |
| Samsung SSD 970 EVO Plus 1TB                        | 26        | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 25        | 0.7%    |
| Seagate ST2000DM008-2FR102 2TB                      | 24        | 0.68%   |
| Samsung NVMe SSD Drive 512GB                        | 24        | 0.68%   |
| Unknown MMC Card  32GB                              | 21        | 0.59%   |
| Samsung SSD 840 EVO 250GB                           | 21        | 0.59%   |
| Seagate ST2000DM006-2DM164 2TB                      | 19        | 0.54%   |
| Samsung NVMe SSD Drive 500GB                        | 18        | 0.51%   |
| Unknown MMC Card  64GB                              | 17        | 0.48%   |
| Unknown MMC Card  128GB                             | 17        | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB                      | 16        | 0.45%   |
| Samsung SSD 850 EVO 1TB                             | 16        | 0.45%   |
| Seagate Expansion 1TB                               | 15        | 0.42%   |
| Samsung SSD 860 QVO 1TB                             | 15        | 0.42%   |
| HGST HTS721010A9E630 1TB                            | 15        | 0.42%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.39%   |
| SanDisk NVMe SSD Drive 1TB                          | 14        | 0.39%   |
| Samsung NVMe SSD Drive 1024GB                       | 14        | 0.39%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 13        | 0.37%   |
| SK hynix NVMe SSD Drive 512GB                       | 13        | 0.37%   |
| Seagate ST4000DM004-2CV104 4TB                      | 13        | 0.37%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13        | 0.37%   |
| Samsung SSD 850 PRO 256GB                           | 13        | 0.37%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 13        | 0.37%   |
| Crucial CT1000MX500SSD1 1TB                         | 13        | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 12        | 0.34%   |
| Samsung SSD 970 EVO 1TB                             | 12        | 0.34%   |
| Samsung SSD 870 EVO 500GB                           | 12        | 0.34%   |
| Unknown SD/MMC/MS PRO 128GB                         | 11        | 0.31%   |
| Samsung SSD 970 EVO Plus 2TB                        | 11        | 0.31%   |
| Samsung SSD 850 PRO 512GB                           | 11        | 0.31%   |
| Samsung SSD 840 PRO Series 256GB                    | 11        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 355       | 510    | 35.5%   |
| WDC                 | 327       | 546    | 32.7%   |
| Hitachi             | 101       | 139    | 10.1%   |
| Toshiba             | 81        | 105    | 8.1%    |
| Samsung Electronics | 40        | 61     | 4%      |
| HGST                | 36        | 46     | 3.6%    |
| Unknown             | 12        | 13     | 1.2%    |
| Apple               | 12        | 12     | 1.2%    |
| Fujitsu             | 7         | 10     | 0.7%    |
| Maxtor              | 4         | 6      | 0.4%    |
| Intenso             | 4         | 4      | 0.4%    |
| ASMT                | 3         | 4      | 0.3%    |
| Initio              | 2         | 2      | 0.2%    |
| Hewlett-Packard     | 2         | 4      | 0.2%    |
| External            | 2         | 2      | 0.2%    |
| USB3.0              | 1         | 2      | 0.1%    |
| USB                 | 1         | 2      | 0.1%    |
| Unknown (CF)        | 1         | 1      | 0.1%    |
| SABRENT             | 1         | 1      | 0.1%    |
| MARVELL             | 1         | 1      | 0.1%    |
| IET                 | 1         | 1      | 0.1%    |
| ICY BOX             | 1         | 1      | 0.1%    |
| HPE                 | 1         | 6      | 0.1%    |
| HGST HTS            | 1         | 1      | 0.1%    |
| ExcelStor           | 1         | 2      | 0.1%    |
| ASMT109x            | 1         | 1      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 448       | 773    | 39.54%  |
| SanDisk             | 97        | 121    | 8.56%   |
| Crucial             | 82        | 119    | 7.24%   |
| Intel               | 67        | 86     | 5.91%   |
| Kingston            | 66        | 102    | 5.83%   |
| WDC                 | 63        | 83     | 5.56%   |
| Micron Technology   | 30        | 41     | 2.65%   |
| Toshiba             | 26        | 39     | 2.29%   |
| Apple               | 26        | 28     | 2.29%   |
| OCZ                 | 25        | 30     | 2.21%   |
| SK hynix            | 19        | 23     | 1.68%   |
| LITEON              | 18        | 24     | 1.59%   |
| Intenso             | 15        | 16     | 1.32%   |
| A-DATA Technology   | 15        | 24     | 1.32%   |
| LITEONIT            | 14        | 16     | 1.24%   |
| Corsair             | 13        | 14     | 1.15%   |
| China               | 13        | 15     | 1.15%   |
| Transcend           | 12        | 22     | 1.06%   |
| KingSpec            | 8         | 13     | 0.71%   |
| Plextor             | 7         | 8      | 0.62%   |
| SPCC                | 6         | 7      | 0.53%   |
| ASMT                | 6         | 10     | 0.53%   |
| Patriot             | 5         | 6      | 0.44%   |
| JMicron Technology  | 5         | 5      | 0.44%   |
| KIOXIA-EXCERIA      | 4         | 5      | 0.35%   |
| Seagate             | 3         | 3      | 0.26%   |
| HPE                 | 3         | 4      | 0.26%   |
| Hewlett-Packard     | 3         | 4      | 0.26%   |
| PNY                 | 2         | 3      | 0.18%   |
| Mushkin             | 2         | 2      | 0.18%   |
| Dogfish             | 2         | 3      | 0.18%   |
| Adaptec             | 2         | 2      | 0.18%   |
| XSTAR               | 1         | 1      | 0.09%   |
| WDC WDS             | 1         | 1      | 0.09%   |
| WALRAM              | 1         | 1      | 0.09%   |
| VERICO              | 1         | 1      | 0.09%   |
| Unknown             | 1         | 1      | 0.09%   |
| TO Exter            | 1         | 1      | 0.09%   |
| S3+                 | 1         | 1      | 0.09%   |
| Phison              | 1         | 3      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 990       | 1683   | 34.19%  |
| NVMe    | 879       | 1363   | 30.35%  |
| HDD     | 850       | 1484   | 29.35%  |
| MMC     | 142       | 211    | 4.9%    |
| Unknown | 35        | 53     | 1.21%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1454      | 3044   | 55.77%  |
| NVMe | 879       | 1362   | 33.72%  |
| MMC  | 142       | 211    | 5.45%   |
| SAS  | 132       | 177    | 5.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 989       | 1598   | 50.23%  |
| 0.51-1.0   | 557       | 898    | 28.29%  |
| 1.01-2.0   | 228       | 376    | 11.58%  |
| 3.01-4.0   | 81        | 133    | 4.11%   |
| 2.01-3.0   | 52        | 77     | 2.64%   |
| 4.01-10.0  | 44        | 58     | 2.23%   |
| 10.01-20.0 | 18        | 27     | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 541       | 22.69%  |
| 251-500        | 444       | 18.62%  |
| 501-1000       | 373       | 15.65%  |
| 1001-2000      | 257       | 10.78%  |
| More than 3000 | 174       | 7.3%    |
| 1-20           | 170       | 7.13%   |
| Unknown        | 116       | 4.87%   |
| 51-100         | 115       | 4.82%   |
| 2001-3000      | 113       | 4.74%   |
| 21-50          | 81        | 3.4%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 837       | 33.8%   |
| 21-50          | 318       | 12.84%  |
| 101-250        | 318       | 12.84%  |
| 51-100         | 267       | 10.78%  |
| 251-500        | 229       | 9.25%   |
| 501-1000       | 181       | 7.31%   |
| Unknown        | 116       | 4.68%   |
| 1001-2000      | 107       | 4.32%   |
| More than 3000 | 73        | 2.95%   |
| 2001-3000      | 30        | 1.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WD3000HLHX-01JJPV0 304GB         | 2         | 2      | 1.33%   |
| WDC WD20EARS-00J99B0 2TB             | 2         | 2      | 1.33%   |
| WDC WD10EARS-00Y5B1 1TB              | 2         | 2      | 1.33%   |
| WDC WD10EADS-00L5B1 1TB              | 2         | 2      | 1.33%   |
| Seagate ST9320325AS 320GB            | 2         | 2      | 1.33%   |
| Seagate ST3250310AS 250GB            | 2         | 2      | 1.33%   |
| Seagate ST31500341AS 1TB             | 2         | 5      | 1.33%   |
| Samsung Electronics SSD 850 EVO 1TB  | 2         | 2      | 1.33%   |
| Initio 3639S 1TB                     | 2         | 2      | 1.33%   |
| Hitachi HUA722020ALA330 2TB          | 2         | 2      | 1.33%   |
| Hitachi HTS545050B9SA00 500GB        | 2         | 2      | 1.33%   |
| Hitachi HTS545050B9A300 500GB        | 2         | 2      | 1.33%   |
| XSTAR SSD 128GB                      | 1         | 1      | 0.67%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 0.67%   |
| WDC WD5000AAKS-65A7B0 500GB          | 1         | 1      | 0.67%   |
| WDC WD5000AAKS-00TMA0 500GB          | 1         | 1      | 0.67%   |
| WDC WD5000AAKS-00E4A0 500GB          | 1         | 1      | 0.67%   |
| WDC WD40PURX-64GVNY0 4TB             | 1         | 1      | 0.67%   |
| WDC WD40EZRZ-00WN9B0 4TB             | 1         | 1      | 0.67%   |
| WDC WD40EFRX-68N32N0 4TB             | 1         | 2      | 0.67%   |
| WDC WD4003FZEX-00Z4SA0 4TB           | 1         | 2      | 0.67%   |
| WDC WD3200AAKS-00B3A0 320GB          | 1         | 1      | 0.67%   |
| WDC WD3200AAJS-40VWA1 320GB          | 1         | 1      | 0.67%   |
| WDC WD30EZRX-00D8PB0 3TB             | 1         | 1      | 0.67%   |
| WDC WD2502ABYS-01B7A0 256GB          | 1         | 1      | 0.67%   |
| WDC WD20EZRZ-00Z5HB0 2TB             | 1         | 1      | 0.67%   |
| WDC WD20EZRX-00D8PB0 2TB             | 1         | 2      | 0.67%   |
| WDC WD20EFRX-68AX9N0 2TB             | 1         | 1      | 0.67%   |
| WDC WD20EARS-00J2GB0 2TB             | 1         | 1      | 0.67%   |
| WDC WD1600BEKT-60A25T1 160GB         | 1         | 1      | 0.67%   |
| WDC WD10EZEX-08M2NA0 1TB             | 1         | 1      | 0.67%   |
| WDC WD10EADS-22M2B0 1TB              | 1         | 1      | 0.67%   |
| WDC WD10EADS-11M2B3 1TB              | 1         | 1      | 0.67%   |
| WDC WD1002FAEX-00Z3A0 1TB            | 1         | 1      | 0.67%   |
| WDC WD1001FALS-403AA0 1TB            | 1         | 1      | 0.67%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 1         | 1      | 0.67%   |
| Toshiba THNSN5256GPUK 256GB          | 1         | 1      | 0.67%   |
| Toshiba MQ01ACF050 500GB             | 1         | 1      | 0.67%   |
| Toshiba MQ01ABF050 500GB             | 1         | 2      | 0.67%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1      | 0.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 30        | 34     | 20.27%  |
| Seagate             | 22        | 33     | 14.86%  |
| Samsung Electronics | 18        | 21     | 12.16%  |
| Hitachi             | 14        | 15     | 9.46%   |
| Toshiba             | 10        | 13     | 6.76%   |
| SK hynix            | 9         | 10     | 6.08%   |
| Intel               | 8         | 9      | 5.41%   |
| SanDisk             | 5         | 6      | 3.38%   |
| Micron Technology   | 5         | 6      | 3.38%   |
| Kingston            | 5         | 6      | 3.38%   |
| HGST                | 4         | 4      | 2.7%    |
| OCZ                 | 3         | 4      | 2.03%   |
| A-DATA Technology   | 3         | 5      | 2.03%   |
| Initio              | 2         | 2      | 1.35%   |
| Crucial             | 2         | 2      | 1.35%   |
| XSTAR               | 1         | 1      | 0.68%   |
| Patriot             | 1         | 2      | 0.68%   |
| LITEONIT            | 1         | 1      | 0.68%   |
| Intenso             | 1         | 1      | 0.68%   |
| Fujitsu             | 1         | 1      | 0.68%   |
| China               | 1         | 1      | 0.68%   |
| ASMedia             | 1         | 1      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 28        | 32     | 32.18%  |
| Seagate             | 22        | 33     | 25.29%  |
| Hitachi             | 14        | 15     | 16.09%  |
| Toshiba             | 9         | 12     | 10.34%  |
| Samsung Electronics | 5         | 6      | 5.75%   |
| HGST                | 4         | 4      | 4.6%    |
| Initio              | 2         | 2      | 2.3%    |
| Fujitsu             | 1         | 1      | 1.15%   |
| ASMedia             | 1         | 1      | 1.15%   |
| Apple               | 1         | 1      | 1.15%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 80        | 107    | 56.74%  |
| SSD  | 50        | 60     | 35.46%  |
| NVMe | 11        | 12     | 7.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3750528AS 752GB | 1         | 1      | 100%    |

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
| Detected | 1235      | 2556   | 51.03%  |
| Works    | 1051      | 2058   | 43.43%  |
| Malfunc  | 133       | 179    | 5.5%    |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1442      | 49.67%  |
| Samsung Electronics            | 443       | 15.26%  |
| AMD                            | 336       | 11.57%  |
| SanDisk                        | 121       | 4.17%   |
| SK hynix                       | 72        | 2.48%   |
| ASMedia Technology             | 64        | 2.2%    |
| Marvell Technology Group       | 57        | 1.96%   |
| Toshiba America Info Systems   | 52        | 1.79%   |
| Phison Electronics             | 45        | 1.55%   |
| JMicron Technology             | 35        | 1.21%   |
| Kingston Technology Company    | 33        | 1.14%   |
| Nvidia                         | 30        | 1.03%   |
| Micron Technology              | 28        | 0.96%   |
| LSI Logic / Symbios Logic      | 16        | 0.55%   |
| Silicon Motion                 | 13        | 0.45%   |
| Micron/Crucial Technology      | 13        | 0.45%   |
| KIOXIA                         | 13        | 0.45%   |
| Areca Technology               | 13        | 0.45%   |
| Seagate Technology             | 11        | 0.38%   |
| ADATA Technology               | 11        | 0.38%   |
| Hewlett-Packard                | 8         | 0.28%   |
| Broadcom / LSI                 | 8         | 0.28%   |
| Solid State Storage Technology | 6         | 0.21%   |
| Apple                          | 5         | 0.17%   |
| Union Memory (Shenzhen)        | 4         | 0.14%   |
| Realtek Semiconductor          | 4         | 0.14%   |
| Lite-On Technology             | 4         | 0.14%   |
| Lenovo                         | 4         | 0.14%   |
| Adaptec                        | 4         | 0.14%   |
| VIA Technologies               | 3         | 0.1%    |
| Silicon Image                  | 2         | 0.07%   |
| Transcend                      | 1         | 0.03%   |
| Tekram Technology              | 1         | 0.03%   |
| Biwin Storage Technology       | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 228       | 6.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 226       | 6.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 110       | 3.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 92        | 2.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 90        | 2.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 90        | 2.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 70        | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 63        | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 60        | 1.83%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 60        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 58        | 1.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 56        | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                            | 55        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 51        | 1.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 50        | 1.52%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 48        | 1.46%   |
| Intel SATA Controller [RAID mode]                                              | 43        | 1.31%   |
| AMD 400 Series Chipset SATA Controller                                         | 43        | 1.31%   |
| AMD 500 Series Chipset SATA Controller                                         | 39        | 1.19%   |
| Samsung NVMe SSD Controller 980                                                | 38        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 38        | 1.16%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 35        | 1.06%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 34        | 1.03%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 34        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 34        | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 32        | 0.97%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 31        | 0.94%   |
| Intel SSD 660P Series                                                          | 31        | 0.94%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 28        | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 27        | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 27        | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 25        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 24        | 0.73%   |
| Phison E12 NVMe Controller                                                     | 23        | 0.7%    |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 23        | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 23        | 0.7%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 22        | 0.67%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 22        | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 22        | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 21        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1524      | 53.18%  |
| NVMe | 884       | 30.84%  |
| RAID | 217       | 7.57%   |
| IDE  | 213       | 7.43%   |
| SAS  | 27        | 0.94%   |
| SCSI | 1         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1728      | 78.23%  |
| AMD          | 436       | 19.74%  |
| ARM          | 39        | 1.77%   |
| QUALCOMM     | 2         | 0.09%   |
| CentaurHauls | 2         | 0.09%   |
| Unknown      | 2         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 48        | 2.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 45        | 2.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 42        | 1.9%    |
| ARM Processor                              | 38        | 1.72%   |
| Intel Core i7-6700 CPU @ 3.40GHz           | 23        | 1.04%   |
| AMD Ryzen 7 5800X 8-Core Processor         | 23        | 1.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 21        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 21        | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 21        | 0.95%   |
| Intel Core i7-2600 CPU @ 3.40GHz           | 20        | 0.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz         | 20        | 0.9%    |
| Intel Core i7-4790 CPU @ 3.60GHz           | 18        | 0.81%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 18        | 0.81%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 17        | 0.77%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 17        | 0.77%   |
| AMD Ryzen 5 3600 6-Core Processor          | 17        | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 16        | 0.72%   |
| Intel 11th Gen Core i9-11900F @ 2.50GHz    | 16        | 0.72%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 15        | 0.68%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 15        | 0.68%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 15        | 0.68%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 14        | 0.63%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 14        | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 14        | 0.63%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 13        | 0.59%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 13        | 0.59%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 13        | 0.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 13        | 0.59%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 12        | 0.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 12        | 0.54%   |
| Intel 12th Gen Core i7-1260P               | 12        | 0.54%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 11        | 0.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz          | 11        | 0.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 11        | 0.5%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 11        | 0.5%    |
| Intel Core i7-8700 CPU @ 3.20GHz           | 10        | 0.45%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 10        | 0.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 10        | 0.45%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 10        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 695       | 31.45%  |
| Intel Core i5           | 428       | 19.37%  |
| Other                   | 221       | 10%     |
| AMD Ryzen 7             | 119       | 5.38%   |
| Intel Xeon              | 90        | 4.07%   |
| AMD Ryzen 5             | 87        | 3.94%   |
| Intel Core 2 Duo        | 72        | 3.26%   |
| Intel Core i3           | 58        | 2.62%   |
| AMD Ryzen 9             | 58        | 2.62%   |
| Intel Celeron           | 53        | 2.4%    |
| Intel Atom              | 33        | 1.49%   |
| Intel Pentium           | 29        | 1.31%   |
| Intel Core i9           | 21        | 0.95%   |
| AMD Ryzen 7 PRO         | 21        | 0.95%   |
| AMD FX                  | 20        | 0.9%    |
| AMD Ryzen Threadripper  | 15        | 0.68%   |
| Intel Pentium Dual-Core | 14        | 0.63%   |
| Intel Core 2            | 14        | 0.63%   |
| Intel Core 2 Quad       | 13        | 0.59%   |
| AMD Ryzen 3             | 10        | 0.45%   |
| AMD A8                  | 9         | 0.41%   |
| AMD Quad-Core Opteron   | 8         | 0.36%   |
| AMD GX                  | 8         | 0.36%   |
| AMD EPYC                | 8         | 0.36%   |
| Intel Xeon Gold         | 7         | 0.32%   |
| AMD E                   | 6         | 0.27%   |
| Intel Pentium 4         | 5         | 0.23%   |
| AMD Phenom II X4        | 5         | 0.23%   |
| AMD Opteron             | 5         | 0.23%   |
| AMD Athlon              | 5         | 0.23%   |
| Intel Pentium Silver    | 4         | 0.18%   |
| Intel Genuine           | 4         | 0.18%   |
| AMD Phenom II X6        | 4         | 0.18%   |
| AMD A10                 | 4         | 0.18%   |
| Intel Pentium M         | 3         | 0.14%   |
| Intel Core M            | 3         | 0.14%   |
| AMD Ryzen 5 PRO         | 3         | 0.14%   |
| AMD Phenom              | 3         | 0.14%   |
| AMD E2                  | 3         | 0.14%   |
| AMD E1                  | 3         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 917       | 41.46%  |
| 2       | 602       | 27.22%  |
| 8       | 252       | 11.39%  |
| 6       | 227       | 10.26%  |
| 12      | 64        | 2.89%   |
| 16      | 38        | 1.72%   |
| 1       | 21        | 0.95%   |
| 10      | 19        | 0.86%   |
| 14      | 18        | 0.81%   |
| 24      | 13        | 0.59%   |
| 32      | 10        | 0.45%   |
| 3       | 8         | 0.36%   |
| Unknown | 6         | 0.27%   |
| 40      | 5         | 0.23%   |
| 128     | 3         | 0.14%   |
| 48      | 3         | 0.14%   |
| 64      | 2         | 0.09%   |
| 18      | 2         | 0.09%   |
| 22      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2145      | 97.06%  |
| 2       | 49        | 2.22%   |
| 4       | 11        | 0.5%    |
| Unknown | 4         | 0.18%   |
| 3       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1635      | 73.72%  |
| 1       | 577       | 26.01%  |
| Unknown | 6         | 0.27%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2171      | 97.97%  |
| Unknown        | 32        | 1.44%   |
| 32-bit         | 12        | 0.54%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 572       | 24.91%  |
| 0x306a9    | 127       | 5.53%   |
| 0x206a7    | 107       | 4.66%   |
| 0x306c3    | 97        | 4.22%   |
| 0x806ea    | 80        | 3.48%   |
| 0x506e3    | 65        | 2.83%   |
| 0x906ea    | 62        | 2.7%    |
| 0x806ec    | 56        | 2.44%   |
| 0x40651    | 55        | 2.4%    |
| 0x806c1    | 54        | 2.35%   |
| 0x1067a    | 54        | 2.35%   |
| 0x806e9    | 53        | 2.31%   |
| 0x906e9    | 38        | 1.66%   |
| 0x306d4    | 32        | 1.39%   |
| 0x08701021 | 32        | 1.39%   |
| 0x406e3    | 28        | 1.22%   |
| 0x20655    | 25        | 1.09%   |
| 0x30678    | 22        | 0.96%   |
| 0xa0671    | 20        | 0.87%   |
| 0xa0655    | 19        | 0.83%   |
| 0x706e5    | 19        | 0.83%   |
| 0x0a50000c | 19        | 0.83%   |
| 0x0800820d | 19        | 0.83%   |
| 0x10676    | 18        | 0.78%   |
| 0x806eb    | 17        | 0.74%   |
| 0x406c4    | 15        | 0.65%   |
| 0x306f2    | 15        | 0.65%   |
| 0x206d7    | 15        | 0.65%   |
| 0x106e5    | 15        | 0.65%   |
| 0xa0652    | 14        | 0.61%   |
| 0x906ed    | 14        | 0.61%   |
| 0x906a3    | 14        | 0.61%   |
| 0x50654    | 14        | 0.61%   |
| 0x306e4    | 14        | 0.61%   |
| 0x20652    | 14        | 0.61%   |
| 0x0a404102 | 14        | 0.61%   |
| 0x0a201016 | 14        | 0.61%   |
| 0x08701013 | 13        | 0.57%   |
| 0x206c2    | 12        | 0.52%   |
| 0x706a1    | 11        | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 428       | 19.33%  |
| Haswell          | 212       | 9.58%   |
| IvyBridge        | 167       | 7.54%   |
| SandyBridge      | 154       | 6.96%   |
| Skylake          | 146       | 6.59%   |
| Unknown          | 137       | 6.19%   |
| Zen 2            | 110       | 4.97%   |
| Penryn           | 85        | 3.84%   |
| Zen 3            | 84        | 3.79%   |
| TigerLake        | 72        | 3.25%   |
| Westmere         | 60        | 2.71%   |
| CometLake        | 53        | 2.39%   |
| Silvermont       | 52        | 2.35%   |
| Broadwell        | 51        | 2.3%    |
| Icelake          | 48        | 2.17%   |
| Zen+             | 45        | 2.03%   |
| Alderlake Hybrid | 43        | 1.94%   |
| Nehalem          | 37        | 1.67%   |
| Core             | 37        | 1.67%   |
| Zen              | 36        | 1.63%   |
| K10              | 30        | 1.36%   |
| Piledriver       | 23        | 1.04%   |
| Goldmont plus    | 20        | 0.9%    |
| Bobcat           | 13        | 0.59%   |
| Goldmont         | 12        | 0.54%   |
| Puma             | 10        | 0.45%   |
| K8 Hammer        | 9         | 0.41%   |
| Jaguar           | 8         | 0.36%   |
| P6               | 6         | 0.27%   |
| NetBurst         | 5         | 0.23%   |
| Excavator        | 5         | 0.23%   |
| Bulldozer        | 5         | 0.23%   |
| Bonnell          | 5         | 0.23%   |
| K10 Llano        | 4         | 0.18%   |
| Steamroller      | 2         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1205      | 47.59%  |
| Nvidia                                       | 792       | 31.28%  |
| AMD                                          | 473       | 18.68%  |
| Matrox Electronics Systems                   | 35        | 1.38%   |
| ASPEED Technology                            | 16        | 0.63%   |
| XGI Technology (eXtreme Graphics Innovation) | 9         | 0.36%   |
| VIA Technologies                             | 2         | 0.08%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 91        | 3.53%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 89        | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 86        | 3.33%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 68        | 2.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 66        | 2.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 62        | 2.4%    |
| Intel HD Graphics 620                                                                    | 56        | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 47        | 1.82%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 42        | 1.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 42        | 1.63%   |
| Intel HD Graphics 530                                                                    | 41        | 1.59%   |
| AMD Renoir                                                                               | 38        | 1.47%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 1.32%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 33        | 1.28%   |
| Intel HD Graphics 5500                                                                   | 31        | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 1.12%   |
| Intel HD Graphics 630                                                                    | 27        | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 1.05%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 27        | 1.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 26        | 1.01%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 26        | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 0.89%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 21        | 0.81%   |
| Nvidia GP107GL [Quadro P400]                                                             | 20        | 0.78%   |
| Nvidia GA104 [GeForce RTX 3070 Lite Hash Rate]                                           | 19        | 0.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 0.74%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 0.7%    |
| AMD Rembrandt [Radeon 680M]                                                              | 18        | 0.7%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.66%   |
| AMD Lucienne                                                                             | 17        | 0.66%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.62%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.62%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 16        | 0.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 0.58%   |
| Nvidia GK107GL [Quadro K420]                                                             | 15        | 0.58%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 15        | 0.58%   |
| Intel Iris Plus Graphics G7                                                              | 15        | 0.58%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 13        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 878       | 39.44%  |
| 1 x Nvidia               | 500       | 22.46%  |
| 1 x AMD                  | 390       | 17.52%  |
| Intel + Nvidia           | 252       | 11.32%  |
| Other                    | 52        | 2.34%   |
| Intel + AMD              | 42        | 1.89%   |
| 1 x Matrox               | 32        | 1.44%   |
| AMD + Nvidia             | 28        | 1.26%   |
| 2 x AMD                  | 13        | 0.58%   |
| 1 x ASPEED               | 10        | 0.45%   |
| 1 x XGI                  | 9         | 0.4%    |
| 2 x Nvidia               | 5         | 0.22%   |
| Nvidia + ASPEED          | 5         | 0.22%   |
| 2 x Intel                | 3         | 0.13%   |
| 1 x VIA                  | 2         | 0.09%   |
| Nvidia + Matrox          | 2         | 0.09%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |
| AMD + Matrox             | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1633      | 73.1%   |
| Proprietary | 476       | 21.31%  |
| Unknown     | 125       | 5.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1215      | 53.57%  |
| 1.01-2.0   | 276       | 12.17%  |
| 0.01-0.5   | 206       | 9.08%   |
| 3.01-4.0   | 156       | 6.88%   |
| 0.51-1.0   | 147       | 6.48%   |
| 7.01-8.0   | 123       | 5.42%   |
| 8.01-16.0  | 73        | 3.22%   |
| 5.01-6.0   | 42        | 1.85%   |
| 2.01-3.0   | 15        | 0.66%   |
| 16.01-24.0 | 13        | 0.57%   |
| 4.01-5.0   | 2         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 326       | 13.63%  |
| AU Optronics            | 269       | 11.25%  |
| LG Display              | 219       | 9.16%   |
| Dell                    | 170       | 7.11%   |
| Chimei Innolux          | 138       | 5.77%   |
| BOE                     | 123       | 5.14%   |
| Hewlett-Packard         | 113       | 4.73%   |
| Acer                    | 103       | 4.31%   |
| Philips                 | 97        | 4.06%   |
| Apple                   | 90        | 3.76%   |
| BenQ                    | 76        | 3.18%   |
| Ancor Communications    | 65        | 2.72%   |
| Sharp                   | 63        | 2.63%   |
| Lenovo                  | 58        | 2.43%   |
| AOC                     | 53        | 2.22%   |
| Goldstar                | 52        | 2.17%   |
| Eizo                    | 41        | 1.71%   |
| ASUSTek Computer        | 27        | 1.13%   |
| Unknown                 | 25        | 1.05%   |
| InfoVision              | 23        | 0.96%   |
| Chi Mei Optoelectronics | 23        | 0.96%   |
| Sony                    | 21        | 0.88%   |
| CSO                     | 18        | 0.75%   |
| NEC Computers           | 15        | 0.63%   |
| Iiyama                  | 15        | 0.63%   |
| Panasonic               | 12        | 0.5%    |
| PANDA                   | 10        | 0.42%   |
| Toshiba                 | 8         | 0.33%   |
| Vestel Elektronik       | 7         | 0.29%   |
| Medion                  | 7         | 0.29%   |
| Fujitsu Siemens         | 6         | 0.25%   |
| ViewSonic               | 5         | 0.21%   |
| MSI                     | 5         | 0.21%   |
| LG Philips              | 5         | 0.21%   |
| LG Electronics          | 5         | 0.21%   |
| Gigabyte Technology     | 5         | 0.21%   |
| AUS                     | 5         | 0.21%   |
| Valve                   | 4         | 0.17%   |
| LGD                     | 4         | 0.17%   |
| JDI                     | 4         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor LF24T450F 1920x1080                   | 15        | 0.6%    |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                  | 11        | 0.44%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 11        | 0.44%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 10        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 9         | 0.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.36%   |
| AOC Q3279WG5B AOC3279 2560x1440 730x430mm 33.4-inch                   | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch      | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 8         | 0.32%   |
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 7         | 0.28%   |
| Philips LCD Monitor PHL 272S4L 2560x1440                              | 7         | 0.28%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 7         | 0.28%   |
| Dell LCD Monitor P2719H 3840x1080                                     | 7         | 0.28%   |
| Dell LCD Monitor P2719H                                               | 7         | 0.28%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                      | 7         | 0.28%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 7         | 0.28%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 6         | 0.24%   |
| Samsung Electronics SyncMaster SAM0587 1920x1200 520x320mm 24.0-inch  | 6         | 0.24%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 6         | 0.24%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch      | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 6         | 0.24%   |
| Apple iMac APPA012 1920x1080 475x267mm 21.5-inch                      | 6         | 0.24%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch     | 5         | 0.2%    |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 5         | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.2%    |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                    | 5         | 0.2%    |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 5         | 0.2%    |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.2%    |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 5         | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 5         | 0.2%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 0.2%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.2%    |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 5         | 0.2%    |
| Hewlett-Packard E243i HPN3463 1920x1200 518x324mm 24.1-inch           | 5         | 0.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 5         | 0.2%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 5         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 962       | 41.41%  |
| 3840x2160 (4K)     | 213       | 9.17%   |
| 2560x1440 (QHD)    | 170       | 7.32%   |
| 1366x768 (WXGA)    | 166       | 7.15%   |
| 1920x1200 (WUXGA)  | 122       | 5.25%   |
| 1600x900 (HD+)     | 88        | 3.79%   |
| 1680x1050 (WSXGA+) | 81        | 3.49%   |
| 1280x1024 (SXGA)   | 67        | 2.88%   |
| Unknown            | 66        | 2.84%   |
| 3440x1440          | 45        | 1.94%   |
| 2560x1600          | 37        | 1.59%   |
| 1280x800 (WXGA)    | 37        | 1.59%   |
| 1440x900 (WXGA+)   | 34        | 1.46%   |
| 3840x1080          | 31        | 1.33%   |
| 1600x1200          | 26        | 1.12%   |
| 2880x1800          | 14        | 0.6%    |
| 3840x2400          | 12        | 0.52%   |
| 3200x1800 (QHD+)   | 12        | 0.52%   |
| 2560x1080          | 12        | 0.52%   |
| 2736x1824          | 11        | 0.47%   |
| 3840x1200          | 10        | 0.43%   |
| 3840x1600          | 7         | 0.3%    |
| 1360x768           | 7         | 0.3%    |
| 1024x768 (XGA)     | 7         | 0.3%    |
| 4480x1440          | 6         | 0.26%   |
| 3000x2000          | 6         | 0.26%   |
| 1920x540           | 6         | 0.26%   |
| 1024x600           | 5         | 0.22%   |
| 800x1280           | 4         | 0.17%   |
| 3520x1200          | 4         | 0.17%   |
| 3456x2160          | 4         | 0.17%   |
| 2160x1440          | 4         | 0.17%   |
| 7680x2160          | 3         | 0.13%   |
| 5120x1440          | 3         | 0.13%   |
| 3360x1050          | 3         | 0.13%   |
| 2048x1152          | 3         | 0.13%   |
| 6400x1440          | 2         | 0.09%   |
| 3840x1100          | 2         | 0.09%   |
| 3200x1080          | 2         | 0.09%   |
| 3072x1920          | 2         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 420       | 17.71%  |
| 27      | 245       | 10.33%  |
| 13      | 218       | 9.19%   |
| Unknown | 214       | 9.03%   |
| 14      | 198       | 8.35%   |
| 24      | 193       | 8.14%   |
| 17      | 145       | 6.12%   |
| 23      | 120       | 5.06%   |
| 21      | 97        | 4.09%   |
| 31      | 62        | 2.61%   |
| 12      | 60        | 2.53%   |
| 34      | 44        | 1.86%   |
| 20      | 40        | 1.69%   |
| 22      | 39        | 1.64%   |
| 19      | 39        | 1.64%   |
| 16      | 25        | 1.05%   |
| 84      | 18        | 0.76%   |
| 32      | 17        | 0.72%   |
| 11      | 15        | 0.63%   |
| 72      | 14        | 0.59%   |
| 40      | 14        | 0.59%   |
| 25      | 14        | 0.59%   |
| 33      | 11        | 0.46%   |
| 46      | 10        | 0.42%   |
| 37      | 10        | 0.42%   |
| 18      | 10        | 0.42%   |
| 29      | 9         | 0.38%   |
| 48      | 8         | 0.34%   |
| 54      | 7         | 0.3%    |
| 28      | 7         | 0.3%    |
| 10      | 7         | 0.3%    |
| 49      | 6         | 0.25%   |
| 35      | 4         | 0.17%   |
| 26      | 4         | 0.17%   |
| 7       | 4         | 0.17%   |
| 65      | 3         | 0.13%   |
| 55      | 3         | 0.13%   |
| 142     | 2         | 0.08%   |
| 60      | 2         | 0.08%   |
| 43      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 722       | 30.93%  |
| 501-600        | 513       | 21.98%  |
| 201-300        | 225       | 9.64%   |
| Unknown        | 214       | 9.17%   |
| 401-500        | 187       | 8.01%   |
| 351-400        | 176       | 7.54%   |
| 601-700        | 108       | 4.63%   |
| 701-800        | 72        | 3.08%   |
| 1001-1500      | 44        | 1.89%   |
| 1501-2000      | 33        | 1.41%   |
| 801-900        | 30        | 1.29%   |
| 1-100          | 4         | 0.17%   |
| 901-1000       | 3         | 0.13%   |
| More than 2000 | 2         | 0.09%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1416      | 65.92%  |
| 16/10   | 326       | 15.18%  |
| Unknown | 200       | 9.31%   |
| 5/4     | 59        | 2.75%   |
| 21/9    | 57        | 2.65%   |
| 3/2     | 32        | 1.49%   |
| 4/3     | 29        | 1.35%   |
| 32/9    | 12        | 0.56%   |
| 6/5     | 4         | 0.19%   |
| 0.67    | 4         | 0.19%   |
| 1.00    | 3         | 0.14%   |
| 3.40    | 2         | 0.09%   |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 2.50    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 417       | 17.74%  |
| 201-250        | 324       | 13.78%  |
| 81-90          | 286       | 12.17%  |
| 301-350        | 248       | 10.55%  |
| Unknown        | 214       | 9.1%    |
| 351-500        | 152       | 6.47%   |
| 71-80          | 127       | 5.4%    |
| 121-130        | 110       | 4.68%   |
| 251-300        | 107       | 4.55%   |
| 151-200        | 106       | 4.51%   |
| More than 1000 | 57        | 2.42%   |
| 61-70          | 56        | 2.38%   |
| 501-1000       | 48        | 2.04%   |
| 111-120        | 25        | 1.06%   |
| 141-150        | 23        | 0.98%   |
| 51-60          | 18        | 0.77%   |
| 131-140        | 16        | 0.68%   |
| 41-50          | 6         | 0.26%   |
| 91-100         | 6         | 0.26%   |
| 1-40           | 5         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 658       | 28.91%  |
| 121-160       | 611       | 26.85%  |
| 101-120       | 435       | 19.11%  |
| Unknown       | 214       | 9.4%    |
| 161-240       | 196       | 8.61%   |
| More than 240 | 108       | 4.75%   |
| 1-50          | 54        | 2.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1655      | 72.21%  |
| 2     | 412       | 17.98%  |
| 0     | 164       | 7.16%   |
| 3     | 57        | 2.49%   |
| 4     | 4         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1341      | 41.34%  |
| Realtek Semiconductor             | 904       | 27.87%  |
| Qualcomm Atheros                  | 237       | 7.31%   |
| Broadcom                          | 188       | 5.8%    |
| MediaTek                          | 46        | 1.42%   |
| Broadcom Limited                  | 46        | 1.42%   |
| Marvell Technology Group          | 43        | 1.33%   |
| Ralink                            | 32        | 0.99%   |
| Aquantia                          | 32        | 0.99%   |
| ASIX Electronics                  | 28        | 0.86%   |
| Lenovo                            | 24        | 0.74%   |
| Nvidia                            | 23        | 0.71%   |
| TP-Link                           | 20        | 0.62%   |
| Sierra Wireless                   | 20        | 0.62%   |
| Ralink Technology                 | 20        | 0.62%   |
| DisplayLink                       | 16        | 0.49%   |
| Hewlett-Packard                   | 15        | 0.46%   |
| Dell                              | 15        | 0.46%   |
| Huawei Technologies               | 14        | 0.43%   |
| Ericsson Business Mobile Networks | 13        | 0.4%    |
| Edimax Technology                 | 13        | 0.4%    |
| Samsung Electronics               | 12        | 0.37%   |
| NetGear                           | 12        | 0.37%   |
| Qualcomm                          | 11        | 0.34%   |
| Microchip Technology              | 10        | 0.31%   |
| ASUSTek Computer                  | 10        | 0.31%   |
| D-Link                            | 9         | 0.28%   |
| Xiaomi                            | 8         | 0.25%   |
| Microsoft                         | 8         | 0.25%   |
| IMC Networks                      | 5         | 0.15%   |
| Fibocom                           | 5         | 0.15%   |
| AVM                               | 5         | 0.15%   |
| NetXen Incorporated               | 4         | 0.12%   |
| Linksys                           | 4         | 0.12%   |
| ICS Advent                        | 4         | 0.12%   |
| D-Link System                     | 4         | 0.12%   |
| Wilocity                          | 3         | 0.09%   |
| Mellanox Technologies             | 3         | 0.09%   |
| Arduino SA                        | 3         | 0.09%   |
| Qualcomm Atheros Communications   | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 620       | 15.99%  |
| Intel Wi-Fi 6 AX200                                               | 132       | 3.4%    |
| Intel Wireless 8265 / 8275                                        | 107       | 2.76%   |
| Intel I211 Gigabit Network Connection                             | 95        | 2.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 92        | 2.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 86        | 2.22%   |
| Realtek RTL8125 2.5GbE Controller                                 | 72        | 1.86%   |
| Intel Ethernet Connection (2) I219-V                              | 59        | 1.52%   |
| Intel Wi-Fi 6 AX201                                               | 58        | 1.5%    |
| Intel Wireless 7260                                               | 53        | 1.37%   |
| Intel Wireless 7265                                               | 47        | 1.21%   |
| Intel Ethernet Connection I217-LM                                 | 46        | 1.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 1.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 40        | 1.03%   |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 1.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 40        | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 39        | 1.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 39        | 1.01%   |
| Intel Wireless 8260                                               | 38        | 0.98%   |
| Intel 82579V Gigabit Network Connection                           | 36        | 0.93%   |
| Intel 82574L Gigabit Network Connection                           | 33        | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 32        | 0.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 30        | 0.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 29        | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 28        | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27        | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 25        | 0.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 25        | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 25        | 0.64%   |
| Intel Wireless 3165                                               | 25        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 25        | 0.64%   |
| Intel Wireless-AC 9260                                            | 24        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 0.62%   |
| Intel Centrino Ultimate-N 6300                                    | 24        | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 0.59%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 922       | 55.01%  |
| Qualcomm Atheros                      | 195       | 11.63%  |
| Realtek Semiconductor                 | 174       | 10.38%  |
| Broadcom                              | 106       | 6.32%   |
| MediaTek                              | 43        | 2.57%   |
| Ralink                                | 32        | 1.91%   |
| Broadcom Limited                      | 31        | 1.85%   |
| Sierra Wireless                       | 20        | 1.19%   |
| Ralink Technology                     | 20        | 1.19%   |
| TP-Link                               | 15        | 0.89%   |
| Edimax Technology                     | 13        | 0.78%   |
| NetGear                               | 11        | 0.66%   |
| Marvell Technology Group              | 11        | 0.66%   |
| ASUSTek Computer                      | 10        | 0.6%    |
| Qualcomm                              | 9         | 0.54%   |
| Dell                                  | 8         | 0.48%   |
| D-Link                                | 8         | 0.48%   |
| Hewlett-Packard                       | 7         | 0.42%   |
| Microsoft                             | 5         | 0.3%    |
| IMC Networks                          | 5         | 0.3%    |
| Fibocom                               | 5         | 0.3%    |
| AVM                                   | 5         | 0.3%    |
| Wilocity                              | 3         | 0.18%   |
| D-Link System                         | 3         | 0.18%   |
| Qualcomm Atheros Communications       | 2         | 0.12%   |
| Micro Star International              | 2         | 0.12%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.12%   |
| ZyXEL Communications                  | 1         | 0.06%   |
| Quectel Wireless Solutions            | 1         | 0.06%   |
| Philips (or NXP)                      | 1         | 0.06%   |
| Netopia                               | 1         | 0.06%   |
| Linksys                               | 1         | 0.06%   |
| Gemtek                                | 1         | 0.06%   |
| CyberTAN Technology                   | 1         | 0.06%   |
| Belkin Components                     | 1         | 0.06%   |
| Arduino SA                            | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 132       | 7.83%   |
| Intel Wireless 8265 / 8275                                     | 107       | 6.35%   |
| Intel Wi-Fi 6 AX201                                            | 58        | 3.44%   |
| Intel Wireless 7260                                            | 53        | 3.14%   |
| Intel Wireless 7265                                            | 47        | 2.79%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 40        | 2.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 40        | 2.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 39        | 2.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 39        | 2.31%   |
| Intel Wireless 8260                                            | 38        | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 32        | 1.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 30        | 1.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 29        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 25        | 1.48%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 25        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 25        | 1.48%   |
| Intel Wireless 3165                                            | 25        | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 25        | 1.48%   |
| Intel Wireless-AC 9260                                         | 24        | 1.42%   |
| Intel Centrino Ultimate-N 6300                                 | 24        | 1.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 22        | 1.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 1.19%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 20        | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 19        | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 18        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 17        | 1.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 17        | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 16        | 0.95%   |
| Intel Centrino Advanced-N 6235                                 | 16        | 0.95%   |
| Intel Wireless 3160                                            | 15        | 0.89%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 14        | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 13        | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 12        | 0.71%   |
| Sierra Wireless EM7455                                         | 11        | 0.65%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 11        | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 11        | 0.65%   |
| Intel Centrino Advanced-N 6200                                 | 11        | 0.65%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 11        | 0.65%   |
| Broadcom Limited BCM4331 802.11a/b/g/n                         | 11        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 828       | 40.12%  |
| Intel                         | 814       | 39.44%  |
| Broadcom                      | 108       | 5.23%   |
| Qualcomm Atheros              | 69        | 3.34%   |
| Marvell Technology Group      | 32        | 1.55%   |
| Aquantia                      | 32        | 1.55%   |
| ASIX Electronics              | 28        | 1.36%   |
| Nvidia                        | 23        | 1.11%   |
| Lenovo                        | 23        | 1.11%   |
| DisplayLink                   | 16        | 0.78%   |
| Broadcom Limited              | 15        | 0.73%   |
| Samsung Electronics           | 12        | 0.58%   |
| Xiaomi                        | 8         | 0.39%   |
| Microchip Technology          | 8         | 0.39%   |
| Huawei Technologies           | 8         | 0.39%   |
| TP-Link                       | 5         | 0.24%   |
| NetXen Incorporated           | 4         | 0.19%   |
| ICS Advent                    | 4         | 0.19%   |
| MediaTek                      | 3         | 0.15%   |
| Linksys                       | 3         | 0.15%   |
| Qualcomm                      | 2         | 0.1%    |
| Microsoft                     | 2         | 0.1%    |
| Mellanox Technologies         | 2         | 0.1%    |
| Standard Microsystems         | 1         | 0.05%   |
| QNAP System                   | 1         | 0.05%   |
| OnePlus Technology (Shenzhen) | 1         | 0.05%   |
| NetGear                       | 1         | 0.05%   |
| Netchip Technology            | 1         | 0.05%   |
| MosChip Semiconductor         | 1         | 0.05%   |
| JMicron Technology            | 1         | 0.05%   |
| HMD Global                    | 1         | 0.05%   |
| Hewlett-Packard               | 1         | 0.05%   |
| Google                        | 1         | 0.05%   |
| D-Link System                 | 1         | 0.05%   |
| D-Link                        | 1         | 0.05%   |
| Cypress Semiconductor         | 1         | 0.05%   |
| Apple                         | 1         | 0.05%   |
| ADMtek                        | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 620       | 29.01%  |
| Intel I211 Gigabit Network Connection                             | 95        | 4.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 92        | 4.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 86        | 4.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 72        | 3.37%   |
| Intel Ethernet Connection (2) I219-V                              | 59        | 2.76%   |
| Intel Ethernet Connection I217-LM                                 | 46        | 2.15%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 42        | 1.97%   |
| Intel Ethernet Connection (2) I219-LM                             | 40        | 1.87%   |
| Intel 82579V Gigabit Network Connection                           | 36        | 1.68%   |
| Intel 82574L Gigabit Network Connection                           | 33        | 1.54%   |
| Intel Ethernet Controller I225-V                                  | 28        | 1.31%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 1.08%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 1.08%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 1.08%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 1.08%   |
| ASIX AX88179 Gigabit Ethernet                                     | 23        | 1.08%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 23        | 1.08%   |
| Intel I350 Gigabit Network Connection                             | 20        | 0.94%   |
| Intel I210 Gigabit Network Connection                             | 20        | 0.94%   |
| Intel Ethernet Connection (7) I219-V                              | 19        | 0.89%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 19        | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 18        | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 18        | 0.84%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 16        | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12        | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.51%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.42%   |
| Nvidia MCP79 Ethernet                                             | 9         | 0.42%   |
| Intel Ethernet Connection (13) I219-V                             | 9         | 0.42%   |
| Intel 82576 Gigabit Network Connection                            | 9         | 0.42%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 8         | 0.37%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 8         | 0.37%   |
| Lenovo ThinkPad Lan                                               | 8         | 0.37%   |
| Intel Ethernet Connection (11) I219-LM                            | 8         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1887      | 53.58%  |
| WiFi     | 1582      | 44.92%  |
| Modem    | 49        | 1.39%   |
| Unknown  | 4         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1130      | 50.56%  |
| Ethernet | 1105      | 49.44%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1127      | 50.72%  |
| 1     | 884       | 39.78%  |
| 3     | 98        | 4.41%   |
| 0     | 70        | 3.15%   |
| 4     | 27        | 1.22%   |
| 6     | 8         | 0.36%   |
| 5     | 4         | 0.18%   |
| 8     | 2         | 0.09%   |
| 10    | 1         | 0.05%   |
| 7     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1785      | 78.6%   |
| Yes  | 486       | 21.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 743       | 55.28%  |
| Realtek Semiconductor           | 87        | 6.47%   |
| Apple                           | 81        | 6.03%   |
| Broadcom                        | 71        | 5.28%   |
| Cambridge Silicon Radio         | 60        | 4.46%   |
| Qualcomm Atheros Communications | 57        | 4.24%   |
| Foxconn / Hon Hai               | 50        | 3.72%   |
| IMC Networks                    | 43        | 3.2%    |
| Lite-On Technology              | 34        | 2.53%   |
| ASUSTek Computer                | 31        | 2.31%   |
| Hewlett-Packard                 | 16        | 1.19%   |
| Dell                            | 14        | 1.04%   |
| Ralink                          | 9         | 0.67%   |
| MediaTek                        | 9         | 0.67%   |
| Marvell Semiconductor           | 9         | 0.67%   |
| USI                             | 5         | 0.37%   |
| Alps Electric                   | 4         | 0.3%    |
| Toshiba                         | 3         | 0.22%   |
| Realtek                         | 3         | 0.22%   |
| Micro Star International        | 3         | 0.22%   |
| Ralink Technology               | 2         | 0.15%   |
| Chicony Electronics             | 2         | 0.15%   |
| TP-Link                         | 1         | 0.07%   |
| Taiyo Yuden                     | 1         | 0.07%   |
| Logitech                        | 1         | 0.07%   |
| Integrated System Solution      | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Foxconn International           | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 279       | 20.73%  |
| Intel AX201 Bluetooth                               | 133       | 9.88%   |
| Intel AX200 Bluetooth                               | 125       | 9.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 79        | 5.87%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 60        | 4.46%   |
| Realtek Bluetooth Radio                             | 59        | 4.38%   |
| Intel Bluetooth Device                              | 43        | 3.19%   |
| Apple Bluetooth USB Host Controller                 | 25        | 1.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 24        | 1.78%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 1.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 24        | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 22        | 1.63%   |
| Apple Bluetooth Host Controller                     | 22        | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 21        | 1.56%   |
| Realtek  Bluetooth 4.2 Adapter                      | 20        | 1.49%   |
| IMC Networks Bluetooth Radio                        | 20        | 1.49%   |
| Intel AX210 Bluetooth                               | 16        | 1.19%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 14        | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 1.04%   |
| IMC Networks Wireless_Device                        | 12        | 0.89%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.89%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 10        | 0.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.74%   |
| Foxconn / Hon Hai Wireless_Device                   | 10        | 0.74%   |
| Apple Bluetooth HCI                                 | 10        | 0.74%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.67%   |
| MediaTek Wireless_Device                            | 9         | 0.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 0.59%   |
| ASUS ASUS USB-BT500                                 | 8         | 0.59%   |
| Marvell Bluetooth and Wireless LAN Composite        | 7         | 0.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 7         | 0.52%   |
| Lite-On Bluetooth Device                            | 6         | 0.45%   |
| IMC Networks Bluetooth Device                       | 6         | 0.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.45%   |
| Foxconn / Hon Hai BCM20702A0                        | 6         | 0.45%   |
| USI Bluetooth Device                                | 5         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 1635      | 52.72%  |
| Nvidia                    | 611       | 19.7%   |
| AMD                       | 514       | 16.58%  |
| GN Netcom                 | 38        | 1.23%   |
| Logitech                  | 37        | 1.19%   |
| C-Media Electronics       | 33        | 1.06%   |
| ASUSTek Computer          | 19        | 0.61%   |
| Lenovo                    | 18        | 0.58%   |
| Plantronics               | 14        | 0.45%   |
| Realtek Semiconductor     | 11        | 0.35%   |
| Hewlett-Packard           | 11        | 0.35%   |
| Creative Labs             | 10        | 0.32%   |
| SteelSeries ApS           | 9         | 0.29%   |
| RODE Microphones          | 9         | 0.29%   |
| Kingston Technology       | 9         | 0.29%   |
| Generalplus Technology    | 6         | 0.19%   |
| BEHRINGER International   | 6         | 0.19%   |
| Apple                     | 6         | 0.19%   |
| Texas Instruments         | 5         | 0.16%   |
| Tenx Technology           | 5         | 0.16%   |
| Razer USA                 | 5         | 0.16%   |
| Samson Technologies       | 4         | 0.13%   |
| Corsair                   | 4         | 0.13%   |
| Conexant Systems          | 4         | 0.13%   |
| Sony                      | 3         | 0.1%    |
| Sennheiser Communications | 3         | 0.1%    |
| ROCCAT                    | 3         | 0.1%    |
| JMTek                     | 3         | 0.1%    |
| Focusrite-Novation        | 3         | 0.1%    |
| Creative Technology       | 3         | 0.1%    |
| Yamaha                    | 2         | 0.06%   |
| XMOS                      | 2         | 0.06%   |
| VIA Technologies          | 2         | 0.06%   |
| TerraTec Electronic       | 2         | 0.06%   |
| Roland                    | 2         | 0.06%   |
| Other World Computing     | 2         | 0.06%   |
| Micro Star International  | 2         | 0.06%   |
| Magic Control Technology  | 2         | 0.06%   |
| HiFiBerry                 | 2         | 0.06%   |
| GYROCOM C&C               | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 210       | 5.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 158       | 4.42%   |
| AMD Family 17h/19h HD Audio Controller                                     | 142       | 3.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 123       | 3.44%   |
| AMD Starship/Matisse HD Audio Controller                                   | 113       | 3.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 101       | 2.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 87        | 2.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 82        | 2.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 81        | 2.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 74        | 2.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 74        | 2.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 72        | 2.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 65        | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                      | 63        | 1.76%   |
| Intel 8 Series HD Audio Controller                                         | 63        | 1.76%   |
| Intel 200 Series PCH HD Audio                                              | 60        | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 54        | 1.51%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50        | 1.4%    |
| Nvidia GK107 HDMI Audio Controller                                         | 48        | 1.34%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 47        | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 43        | 1.2%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 42        | 1.17%   |
| Nvidia GA104 High Definition Audio Controller                              | 41        | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 41        | 1.15%   |
| Intel Comet Lake PCH-LP cAVS                                               | 41        | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 41        | 1.15%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 35        | 0.98%   |
| Intel Comet Lake PCH cAVS                                                  | 35        | 0.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 33        | 0.92%   |
| Nvidia GF108 High Definition Audio Controller                              | 32        | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 32        | 0.89%   |
| Nvidia GP102 HDMI Audio Controller                                         | 30        | 0.84%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 30        | 0.84%   |
| Nvidia GP104 High Definition Audio Controller                              | 29        | 0.81%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 29        | 0.81%   |
| Nvidia GK104 HDMI Audio Controller                                         | 28        | 0.78%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 28        | 0.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 28        | 0.78%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 27        | 0.75%   |
| AMD FCH Azalia Controller                                                  | 26        | 0.73%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 360       | 23.84%  |
| SK hynix            | 284       | 18.81%  |
| Kingston            | 253       | 16.75%  |
| Micron Technology   | 168       | 11.13%  |
| Corsair             | 152       | 10.07%  |
| Unknown             | 98        | 6.49%   |
| Crucial             | 53        | 3.51%   |
| G.Skill             | 42        | 2.78%   |
| Elpida              | 21        | 1.39%   |
| Ramaxel Technology  | 13        | 0.86%   |
| A-DATA Technology   | 13        | 0.86%   |
| Nanya Technology    | 9         | 0.6%    |
| Unknown             | 6         | 0.4%    |
| Patriot             | 5         | 0.33%   |
| Unknown (ABCD)      | 3         | 0.2%    |
| Hewlett-Packard     | 3         | 0.2%    |
| Avant               | 3         | 0.2%    |
| Unknown (0x9801)    | 2         | 0.13%   |
| ASint Technology    | 2         | 0.13%   |
| Apacer              | 2         | 0.13%   |
| Unknown (0x198)     | 1         | 0.07%   |
| Unknown (08AE)      | 1         | 0.07%   |
| Unifosa             | 1         | 0.07%   |
| Team                | 1         | 0.07%   |
| Smart               | 1         | 0.07%   |
| Princeton           | 1         | 0.07%   |
| Patriot Memory      | 1         | 0.07%   |
| OnBoard             | 1         | 0.07%   |
| OCZ                 | 1         | 0.07%   |
| Melco               | 1         | 0.07%   |
| Kingmax             | 1         | 0.07%   |
| KANMEIQi            | 1         | 0.07%   |
| HPE                 | 1         | 0.07%   |
| GOODRAM             | 1         | 0.07%   |
| G-Alantic           | 1         | 0.07%   |
| Advantech           | 1         | 0.07%   |
| A-DA                | 1         | 0.07%   |
| 48spaces            | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 16        | 0.98%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 16        | 0.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 14        | 0.86%   |
| Kingston RAM 9905734-415.A00G 16GB DIMM DDR4 3200MT/s            | 13        | 0.8%    |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 13        | 0.8%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 12        | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.61%   |
| Kingston RAM 9905734-016.A00G 16GB DIMM DDR4 3200MT/s            | 9         | 0.55%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.49%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 8         | 0.49%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.49%   |
| Corsair RAM CM4X16GC3000C16K4D 16GB DIMM DDR4 3000MT/s           | 8         | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.43%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 7         | 0.43%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 7         | 0.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.43%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.43%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 7         | 0.43%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s           | 7         | 0.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.37%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.37%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 6         | 0.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.37%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 6         | 0.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.37%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.37%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 6         | 0.37%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.37%   |
| Corsair RAM CMK64GX4M2E3200C16 32GB DIMM DDR4 3200MT/s           | 6         | 0.37%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 6         | 0.37%   |
| Unknown                                                          | 6         | 0.37%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 5         | 0.31%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.31%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.31%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 5         | 0.31%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 688       | 50.33%  |
| DDR3    | 440       | 32.19%  |
| LPDDR3  | 61        | 4.46%   |
| LPDDR4  | 48        | 3.51%   |
| DDR2    | 41        | 3%      |
| DDR5    | 31        | 2.27%   |
| Unknown | 22        | 1.61%   |
| SDRAM   | 18        | 1.32%   |
| LPDDR5  | 13        | 0.95%   |
| DDR     | 5         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 675       | 49.56%  |
| DIMM         | 554       | 40.68%  |
| Row Of Chips | 114       | 8.37%   |
| Chip         | 9         | 0.66%   |
| RIMM         | 6         | 0.44%   |
| Unknown      | 3         | 0.22%   |
| FB-DIMM      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 590       | 40.41%  |
| 16384 | 330       | 22.6%   |
| 4096  | 296       | 20.27%  |
| 2048  | 128       | 8.77%   |
| 32768 | 78        | 5.34%   |
| 1024  | 31        | 2.12%   |
| 65536 | 5         | 0.34%   |
| 49152 | 1         | 0.07%   |
| 512   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 270       | 18.51%  |
| 3200    | 231       | 15.83%  |
| 2667    | 196       | 13.43%  |
| 2133    | 108       | 7.4%    |
| 1333    | 99        | 6.79%   |
| 2400    | 95        | 6.51%   |
| 1334    | 51        | 3.5%    |
| 3600    | 30        | 2.06%   |
| 1867    | 28        | 1.92%   |
| 3000    | 27        | 1.85%   |
| 800     | 26        | 1.78%   |
| 4267    | 25        | 1.71%   |
| 4800    | 24        | 1.64%   |
| 2666    | 23        | 1.58%   |
| 3400    | 19        | 1.3%    |
| 667     | 19        | 1.3%    |
| 1067    | 16        | 1.1%    |
| 6400    | 14        | 0.96%   |
| 3266    | 13        | 0.89%   |
| Unknown | 12        | 0.82%   |
| 1066    | 10        | 0.69%   |
| 3733    | 9         | 0.62%   |
| 2933    | 8         | 0.55%   |
| 3800    | 7         | 0.48%   |
| 8400    | 6         | 0.41%   |
| 1800    | 6         | 0.41%   |
| 5808    | 5         | 0.34%   |
| 4266    | 5         | 0.34%   |
| 3533    | 5         | 0.34%   |
| 3100    | 5         | 0.34%   |
| 2000    | 5         | 0.34%   |
| 1866    | 5         | 0.34%   |
| 4199    | 4         | 0.27%   |
| 3933    | 4         | 0.27%   |
| 3666    | 4         | 0.27%   |
| 2465    | 4         | 0.27%   |
| 2048    | 4         | 0.27%   |
| 3500    | 3         | 0.21%   |
| 333     | 3         | 0.21%   |
| 6000    | 2         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 26        | 41.94%  |
| Brother Industries       | 16        | 25.81%  |
| Samsung Electronics      | 5         | 8.06%   |
| Canon                    | 4         | 6.45%   |
| STMicroelectronics       | 3         | 4.84%   |
| Seiko Epson              | 2         | 3.23%   |
| Oki Data                 | 2         | 3.23%   |
| Zhuhai Poskey Technology | 1         | 1.61%   |
| Prolific Technology      | 1         | 1.61%   |
| Konica Minolta           | 1         | 1.61%   |
| Dymo-CoStar              | 1         | 1.61%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44  | 3         | 4.84%   |
| Samsung M337x 387x 407x Series                             | 2         | 3.23%   |
| Oki Data USB Device                                        | 2         | 3.23%   |
| HP OfficeJet Pro 7730 series                               | 2         | 3.23%   |
| HP OfficeJet 6950                                          | 2         | 3.23%   |
| HP LaserJet Pro M148f-M149f                                | 2         | 3.23%   |
| HP ENVY 5540 series                                        | 2         | 3.23%   |
| HP Deskjet 2540 series                                     | 2         | 3.23%   |
| Brother Printer                                            | 2         | 3.23%   |
| Brother MFC Composite Device                               | 2         | 3.23%   |
| Zhuhai Poskey Printer                                      | 1         | 1.61%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.61%   |
| Seiko Epson ET-2820 Series                                 | 1         | 1.61%   |
| Samsung M332x 382x 402x Series                             | 1         | 1.61%   |
| Samsung C48x Series                                        | 1         | 1.61%   |
| Samsung C1860 Series                                       | 1         | 1.61%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.61%   |
| Konica Minolta Printer                                     | 1         | 1.61%   |
| HP Smart Tank Plus 550 series                              | 1         | 1.61%   |
| HP Smart Tank 7000 series                                  | 1         | 1.61%   |
| HP Officejet 4630 series                                   | 1         | 1.61%   |
| HP LaserJet P3010 Series                                   | 1         | 1.61%   |
| HP LaserJet P2055 series                                   | 1         | 1.61%   |
| HP Laserjet P1505                                          | 1         | 1.61%   |
| HP LaserJet P1102                                          | 1         | 1.61%   |
| HP LaserJet 3050                                           | 1         | 1.61%   |
| HP LaserJet 3020                                           | 1         | 1.61%   |
| HP LaserJet 1320                                           | 1         | 1.61%   |
| HP LaserJet 1020                                           | 1         | 1.61%   |
| HP Laser 107a                                              | 1         | 1.61%   |
| HP ENVY Photo 6200 series                                  | 1         | 1.61%   |
| HP ENVY 6400 series                                        | 1         | 1.61%   |
| HP ENVY 4520 series                                        | 1         | 1.61%   |
| HP DeskJet F2100 Printer series                            | 1         | 1.61%   |
| Dymo-CoStar LabelWriter 450                                | 1         | 1.61%   |
| Canon TS3300 series                                        | 1         | 1.61%   |
| Canon PIXMA TS6250                                         | 1         | 1.61%   |
| Canon PIXMA MX450 Series                                   | 1         | 1.61%   |
| Canon iP7200 series                                        | 1         | 1.61%   |
| Brother MFC-9320CW                                         | 1         | 1.61%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Canon             | 7         | 46.67%  |
| Seiko Epson       | 4         | 26.67%  |
| Hewlett-Packard   | 2         | 13.33%  |
| Fujitsu           | 1         | 6.67%   |
| Canon Electronics | 1         | 6.67%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                       | 2         | 13.33%  |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                   | 1         | 6.67%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1         | 6.67%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]       | 1         | 6.67%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 6.67%   |
| HP ScanJet 4070 PhotoSmart                                    | 1         | 6.67%   |
| HP ScanJet 2400c                                              | 1         | 6.67%   |
| Fujitsu ScanSnap SV600                                        | 1         | 6.67%   |
| Canon P-150 Scanner                                           | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20                            | 1         | 6.67%   |
| Canon CanoScan N650U/N656U                                    | 1         | 6.67%   |
| Canon CanoScan LIDE 25                                        | 1         | 6.67%   |
| Canon CanoScan LiDE 200                                       | 1         | 6.67%   |
| Canon CanoScan LiDE 100                                       | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 338       | 27.08%  |
| IMC Networks                           | 98        | 7.85%   |
| Logitech                               | 92        | 7.37%   |
| Apple                                  | 80        | 6.41%   |
| Microdia                               | 77        | 6.17%   |
| Bison Electronics                      | 63        | 5.05%   |
| Realtek Semiconductor                  | 62        | 4.97%   |
| Quanta                                 | 59        | 4.73%   |
| Sunplus Innovation Technology          | 51        | 4.09%   |
| Cheng Uei Precision Industry (Foxlink) | 48        | 3.85%   |
| Lite-On Technology                     | 35        | 2.8%    |
| Suyin                                  | 31        | 2.48%   |
| Acer                                   | 28        | 2.24%   |
| Syntek                                 | 21        | 1.68%   |
| Luxvisions Innotech Limited            | 17        | 1.36%   |
| Lenovo                                 | 17        | 1.36%   |
| Ricoh                                  | 14        | 1.12%   |
| Alcor Micro                            | 14        | 1.12%   |
| Microsoft                              | 13        | 1.04%   |
| Samsung Electronics                    | 12        | 0.96%   |
| Sonix Technology                       | 8         | 0.64%   |
| Silicon Motion                         | 7         | 0.56%   |
| Z-Star Microelectronics                | 5         | 0.4%    |
| Generalplus Technology                 | 5         | 0.4%    |
| ALi                                    | 5         | 0.4%    |
| Primax Electronics                     | 4         | 0.32%   |
| Xiaomi                                 | 2         | 0.16%   |
| Tripath Technology                     | 2         | 0.16%   |
| OmniVision Technologies                | 2         | 0.16%   |
| MacroSilicon                           | 2         | 0.16%   |
| Intel                                  | 2         | 0.16%   |
| Genesys Logic                          | 2         | 0.16%   |
| DigiTech                               | 2         | 0.16%   |
| Creative Technology                    | 2         | 0.16%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.16%   |
| YGTek                                  | 1         | 0.08%   |
| WCM_USB                                | 1         | 0.08%   |
| Tobii Technology AB                    | 1         | 0.08%   |
| ShineTech                              | 1         | 0.08%   |
| Pixart Imaging                         | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 89        | 7.02%   |
| IMC Networks Integrated Camera          | 45        | 3.55%   |
| Microdia Integrated_Webcam_HD           | 39        | 3.08%   |
| Chicony HD WebCam                       | 32        | 2.52%   |
| Chicony HP HD Camera                    | 26        | 2.05%   |
| Apple FaceTime HD Camera (Built-in)     | 26        | 2.05%   |
| IMC Networks USB2.0 HD UVC WebCam       | 23        | 1.81%   |
| Apple Built-in iSight                   | 23        | 1.81%   |
| Realtek Integrated_Webcam_HD            | 21        | 1.66%   |
| Bison Integrated Camera                 | 20        | 1.58%   |
| Logitech HD Pro Webcam C920             | 16        | 1.26%   |
| Lite-On Integrated Camera               | 16        | 1.26%   |
| Quanta HP HD Camera                     | 15        | 1.18%   |
| Logitech Webcam C270                    | 15        | 1.18%   |
| Chicony USB2.0 Camera                   | 15        | 1.18%   |
| Chicony HP Wide Vision HD Camera        | 14        | 1.1%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR      | 13        | 1.03%   |
| Syntek Integrated Camera                | 12        | 0.95%   |
| Sunplus Integrated_Webcam_HD            | 12        | 0.95%   |
| Sunplus HD WebCam                       | 12        | 0.95%   |
| Samsung Galaxy series, misc. (MTP mode) | 12        | 0.95%   |
| Microdia Integrated Webcam              | 11        | 0.87%   |
| Chicony Integrated Camera (1280x720@30) | 11        | 0.87%   |
| Chicony HP Truevision HD                | 11        | 0.87%   |
| Lite-On HP HD Camera                    | 10        | 0.79%   |
| Apple FaceTime HD Camera                | 10        | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 9         | 0.71%   |
| Chicony HD User Facing                  | 9         | 0.71%   |
| Chicony Integrated IR Camera            | 8         | 0.63%   |
| Suyin HP Truevision HD                  | 7         | 0.55%   |
| Realtek USB2.0 HD UVC WebCam            | 7         | 0.55%   |
| Quanta HD Webcam                        | 7         | 0.55%   |
| Quanta HD User Facing                   | 7         | 0.55%   |
| Logitech StreamCam                      | 7         | 0.55%   |
| Logitech HD Webcam C615                 | 7         | 0.55%   |
| Lenovo Integrated Webcam                | 7         | 0.55%   |
| Chicony VGA WebCam                      | 7         | 0.55%   |
| Chicony HP HD Webcam                    | 7         | 0.55%   |
| Bison SunplusIT Integrated Camera       | 7         | 0.55%   |
| Acer BisonCam,NB Pro                    | 7         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 138       | 36.9%   |
| Synaptics                          | 137       | 36.63%  |
| Shenzhen Goodix Technology         | 31        | 8.29%   |
| Upek                               | 20        | 5.35%   |
| Elan Microelectronics              | 19        | 5.08%   |
| AuthenTec                          | 14        | 3.74%   |
| LighTuning Technology              | 11        | 2.94%   |
| STMicroelectronics                 | 3         | 0.8%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 47        | 12.57%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 31        | 8.29%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 5.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 4.28%   |
| Validity Sensors Synaptics WBDI                                            | 16        | 4.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 4.01%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 14        | 3.74%   |
| Synaptics  WBDI                                                            | 13        | 3.48%   |
| Elan ELAN:ARM-M4                                                           | 13        | 3.48%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 3.21%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 2.94%   |
| Shenzhen Goodix  FingerPrint Device                                        | 11        | 2.94%   |
| Synaptics UWP WBDI                                                         | 10        | 2.67%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 2.41%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 2.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.41%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.41%   |
| Validity Sensors VFS491                                                    | 8         | 2.14%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 2.14%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 7         | 1.87%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 1.87%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 1.87%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.6%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.34%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.34%   |
| AuthenTec AES2810                                                          | 5         | 1.34%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.34%   |
| Synaptics WBDI                                                             | 4         | 1.07%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.07%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.07%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 3         | 0.8%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.8%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.8%    |
| Synaptics UWP WBDI Device                                                  | 3         | 0.8%    |
| STMicroelectronics Fingerprint Reader                                      | 3         | 0.8%    |
| Unknown                                                                    | 3         | 0.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 0.53%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.53%   |
| Synaptics Fingerprint scanner                                              | 2         | 0.53%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.53%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 54        | 42.86%  |
| Broadcom                  | 40        | 31.75%  |
| Upek                      | 12        | 9.52%   |
| Yubico.com                | 5         | 3.97%   |
| O2 Micro                  | 5         | 3.97%   |
| Lenovo                    | 3         | 2.38%   |
| Clay Logic                | 2         | 1.59%   |
| OmniKey                   | 1         | 0.79%   |
| Gemalto (was Gemplus)     | 1         | 0.79%   |
| Bit4id                    | 1         | 0.79%   |
| Aladdin Knowledge Systems | 1         | 0.79%   |
| Advanced Card Systems     | 1         | 0.79%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 54        | 42.86%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 10.32%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 12        | 9.52%   |
| Broadcom 5880                                                                | 11        | 8.73%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 8         | 6.35%   |
| Broadcom 58200                                                               | 8         | 6.35%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 3.97%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 2.38%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.38%   |
| Yubico.com Yubikey NEO(-N) U2F+CCID                                          | 1         | 0.79%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.79%   |
| OmniKey CardMan 4321                                                         | 1         | 0.79%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.79%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.79%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.79%   |
| Bit4id miniLector-s                                                          | 1         | 0.79%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.79%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.79%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1473      | 64.63%  |
| 1     | 619       | 27.16%  |
| 2     | 144       | 6.32%   |
| 3     | 26        | 1.14%   |
| 4     | 11        | 0.48%   |
| 7     | 2         | 0.09%   |
| 6     | 2         | 0.09%   |
| 5     | 2         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 369       | 36.46%  |
| Graphics card            | 171       | 16.9%   |
| Chipcard                 | 106       | 10.47%  |
| Net/wireless             | 101       | 9.98%   |
| Multimedia controller    | 56        | 5.53%   |
| Communication controller | 51        | 5.04%   |
| Unassigned class         | 39        | 3.85%   |
| Camera                   | 27        | 2.67%   |
| Bluetooth                | 22        | 2.17%   |
| Sound                    | 14        | 1.38%   |
| Card reader              | 12        | 1.19%   |
| Net/ethernet             | 11        | 1.09%   |
| Storage                  | 8         | 0.79%   |
| Network                  | 6         | 0.59%   |
| Storage/raid             | 5         | 0.49%   |
| Modem                    | 5         | 0.49%   |
| Dvb card                 | 3         | 0.3%    |
| Storage/nvme             | 2         | 0.2%    |
| Wireless                 | 1         | 0.1%    |
| Storage/ata              | 1         | 0.1%    |
| Flash memory             | 1         | 0.1%    |
| Firewire controller      | 1         | 0.1%    |

