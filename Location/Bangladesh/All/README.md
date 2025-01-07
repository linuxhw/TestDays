Linux in Bangladesh - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Bangladesh.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bangladesh/Desktop/README.md) and [notebooks](/Location/Bangladesh/Notebook/README.md).

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

Total: 600

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [81230d7d43](https://linux-hardware.org/?probe=81230d7d43) | Dec 21, 2024 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [b19f32d4f6](https://linux-hardware.org/?probe=b19f32d4f6) | Dec 17, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [9fd4e2660e](https://linux-hardware.org/?probe=9fd4e2660e) | Dec 17, 2024 |
| HUAWEI        | RLEF-XX                     | Notebook    | [21f24f2e24](https://linux-hardware.org/?probe=21f24f2e24) | Dec 13, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [8d359551f2](https://linux-hardware.org/?probe=8d359551f2) | Dec 06, 2024 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [143735c29c](https://linux-hardware.org/?probe=143735c29c) | Dec 03, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [76d2be874d](https://linux-hardware.org/?probe=76d2be874d) | Dec 03, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [84fd04ed74](https://linux-hardware.org/?probe=84fd04ed74) | Dec 03, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c751e5836a](https://linux-hardware.org/?probe=c751e5836a) | Dec 01, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [1335a900cb](https://linux-hardware.org/?probe=1335a900cb) | Nov 28, 2024 |
| Lenovo        | ThinkPad T480 20L6S3JG00    | Notebook    | [2936f6558e](https://linux-hardware.org/?probe=2936f6558e) | Nov 22, 2024 |
| Lenovo        | ThinkPad T480 20L6S3JG00    | Notebook    | [3d39119429](https://linux-hardware.org/?probe=3d39119429) | Nov 21, 2024 |
| ASUSTek       | K40IE                       | Notebook    | [1aa4497926](https://linux-hardware.org/?probe=1aa4497926) | Nov 18, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5067d1ba52](https://linux-hardware.org/?probe=5067d1ba52) | Nov 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [aeea617a28](https://linux-hardware.org/?probe=aeea617a28) | Nov 15, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [b7086817a8](https://linux-hardware.org/?probe=b7086817a8) | Nov 12, 2024 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [9739937f81](https://linux-hardware.org/?probe=9739937f81) | Nov 12, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [b20fbc39f9](https://linux-hardware.org/?probe=b20fbc39f9) | Nov 10, 2024 |
| Acer          | Predator PHN16-71           | Notebook    | [f3b608f54f](https://linux-hardware.org/?probe=f3b608f54f) | Nov 10, 2024 |
| Dell          | Inspiron 5505               | Notebook    | [e44d7f2f25](https://linux-hardware.org/?probe=e44d7f2f25) | Nov 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [ac4d04734d](https://linux-hardware.org/?probe=ac4d04734d) | Nov 05, 2024 |
| HP            | 8526 MVB, A                 | Desktop     | [0cf908694a](https://linux-hardware.org/?probe=0cf908694a) | Nov 04, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [9e438cb0e1](https://linux-hardware.org/?probe=9e438cb0e1) | Oct 30, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [dd9ac664ef](https://linux-hardware.org/?probe=dd9ac664ef) | Oct 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [0ba3e2a6cf](https://linux-hardware.org/?probe=0ba3e2a6cf) | Oct 28, 2024 |
| Lenovo        | ThinkPad T480 20L6SA5Q1E    | Notebook    | [b36104396e](https://linux-hardware.org/?probe=b36104396e) | Oct 26, 2024 |
| Intel         | BOX-J4105A V3.0             | Desktop     | [cfb97329fd](https://linux-hardware.org/?probe=cfb97329fd) | Oct 22, 2024 |
| Intel         | BOX-J4105A V3.0             | Desktop     | [ac1ccf2eba](https://linux-hardware.org/?probe=ac1ccf2eba) | Oct 22, 2024 |
| MSI           | Modern 14 B10MW             | Notebook    | [7f701f4c7e](https://linux-hardware.org/?probe=7f701f4c7e) | Oct 21, 2024 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [8f4ed9b69e](https://linux-hardware.org/?probe=8f4ed9b69e) | Oct 20, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a10a4ae8fa](https://linux-hardware.org/?probe=a10a4ae8fa) | Oct 17, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [fdd792f39b](https://linux-hardware.org/?probe=fdd792f39b) | Oct 15, 2024 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [b1fa5db79a](https://linux-hardware.org/?probe=b1fa5db79a) | Oct 14, 2024 |
| Valve         | Jupiter                     | Notebook    | [dd814ebab8](https://linux-hardware.org/?probe=dd814ebab8) | Oct 11, 2024 |
| MSI           | PRO B650-S WIFI             | Desktop     | [4df073db36](https://linux-hardware.org/?probe=4df073db36) | Sep 28, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [bd364d0579](https://linux-hardware.org/?probe=bd364d0579) | Sep 25, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [ac56f45474](https://linux-hardware.org/?probe=ac56f45474) | Sep 25, 2024 |
| Lenovo        | ThinkPad L490 20Q6S31700    | Notebook    | [b63e05de61](https://linux-hardware.org/?probe=b63e05de61) | Sep 21, 2024 |
| ASUSTek       | X550VX                      | Notebook    | [e3c621dc77](https://linux-hardware.org/?probe=e3c621dc77) | Sep 21, 2024 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [554ba54af3](https://linux-hardware.org/?probe=554ba54af3) | Sep 18, 2024 |
| Biostar       | B550MX/E PRO                | Desktop     | [812dab488d](https://linux-hardware.org/?probe=812dab488d) | Sep 18, 2024 |
| MSI           | Modern 14 B4MW              | Notebook    | [1e32af6401](https://linux-hardware.org/?probe=1e32af6401) | Sep 15, 2024 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [8238a64ba2](https://linux-hardware.org/?probe=8238a64ba2) | Sep 10, 2024 |
| HP            | 242 G1                      | Notebook    | [b3dea9f0da](https://linux-hardware.org/?probe=b3dea9f0da) | Sep 08, 2024 |
| Lenovo        | IdeaPad Slim 3 14ABR8 82... | Notebook    | [5ac6514b08](https://linux-hardware.org/?probe=5ac6514b08) | Sep 01, 2024 |
| Lenovo        | IdeaPad Slim 3 14ABR8 82... | Notebook    | [04cd9930c8](https://linux-hardware.org/?probe=04cd9930c8) | Sep 01, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [76050eee07](https://linux-hardware.org/?probe=76050eee07) | Aug 31, 2024 |
| MSI           | MAG B760 TOMAHAWK WIFI      | Desktop     | [c2aa0b4bee](https://linux-hardware.org/?probe=c2aa0b4bee) | Aug 30, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7de01582ba](https://linux-hardware.org/?probe=7de01582ba) | Aug 16, 2024 |
| Gigabyte      | H81M-S1                     | Desktop     | [1681bb92b5](https://linux-hardware.org/?probe=1681bb92b5) | Aug 14, 2024 |
| HUAWEI        | RLEF-XX                     | Notebook    | [01008e9053](https://linux-hardware.org/?probe=01008e9053) | Aug 13, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ed0cfaf91b](https://linux-hardware.org/?probe=ed0cfaf91b) | Aug 12, 2024 |
| OEM           | Intel H81                   | Desktop     | [94a2e82a82](https://linux-hardware.org/?probe=94a2e82a82) | Aug 10, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [e6011d2739](https://linux-hardware.org/?probe=e6011d2739) | Aug 10, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [4bbef13098](https://linux-hardware.org/?probe=4bbef13098) | Aug 08, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [a83a2bfc4c](https://linux-hardware.org/?probe=a83a2bfc4c) | Aug 02, 2024 |
| HUAWEI        | RLEF-XX                     | Notebook    | [a24b85d085](https://linux-hardware.org/?probe=a24b85d085) | Jul 29, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [31a5f645ab](https://linux-hardware.org/?probe=31a5f645ab) | Jul 27, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [196be66fdf](https://linux-hardware.org/?probe=196be66fdf) | Jul 14, 2024 |
| Gigabyte      | B150M-D3V-CF                | Desktop     | [a9981333cd](https://linux-hardware.org/?probe=a9981333cd) | Jul 12, 2024 |
| Dell          | Inspiron 15 3520            | Notebook    | [c2bd74626f](https://linux-hardware.org/?probe=c2bd74626f) | Jul 08, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [913d40ec76](https://linux-hardware.org/?probe=913d40ec76) | Jul 03, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [bd5f3c6e26](https://linux-hardware.org/?probe=bd5f3c6e26) | Jul 03, 2024 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [3bf15e63ac](https://linux-hardware.org/?probe=3bf15e63ac) | Jun 21, 2024 |
| HP            | EliteBook 745 G2            | Notebook    | [ba647a0782](https://linux-hardware.org/?probe=ba647a0782) | Jun 19, 2024 |
| MSI           | PRO B650M-P                 | Desktop     | [742072552d](https://linux-hardware.org/?probe=742072552d) | Jun 15, 2024 |
| Dell          | Inspiron 5505               | Notebook    | [5496cf5716](https://linux-hardware.org/?probe=5496cf5716) | Jun 14, 2024 |
| Qbits Tech... | S15-4D8G                    | Notebook    | [3287fbf77c](https://linux-hardware.org/?probe=3287fbf77c) | Jun 12, 2024 |
| Qbits Tech... | S15-4D8G                    | Notebook    | [ad44765555](https://linux-hardware.org/?probe=ad44765555) | Jun 12, 2024 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [9e356b09e3](https://linux-hardware.org/?probe=9e356b09e3) | Jun 10, 2024 |
| HP            | EliteBook 745 G2            | Notebook    | [dcb4b870bc](https://linux-hardware.org/?probe=dcb4b870bc) | Jun 04, 2024 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [0260200963](https://linux-hardware.org/?probe=0260200963) | Jun 02, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6358a86657](https://linux-hardware.org/?probe=6358a86657) | May 30, 2024 |
| Dell          | Inspiron 15-7568            | Notebook    | [81a6415168](https://linux-hardware.org/?probe=81a6415168) | May 28, 2024 |
| Dell          | Inspiron 5468               | Notebook    | [266dc7095b](https://linux-hardware.org/?probe=266dc7095b) | May 19, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [5b4b1f382b](https://linux-hardware.org/?probe=5b4b1f382b) | May 11, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [32fc232869](https://linux-hardware.org/?probe=32fc232869) | May 01, 2024 |
| ASRock        | B550 Steel Legend           | Desktop     | [45c1449bf6](https://linux-hardware.org/?probe=45c1449bf6) | Apr 27, 2024 |
| HP            | EliteBook 850 G4            | Notebook    | [1e562ccb80](https://linux-hardware.org/?probe=1e562ccb80) | Apr 27, 2024 |
| Gigabyte      | H310M S2P                   | Desktop     | [80fc55e632](https://linux-hardware.org/?probe=80fc55e632) | Apr 22, 2024 |
| MSI           | Modern 15 A5M               | Notebook    | [df536172a9](https://linux-hardware.org/?probe=df536172a9) | Apr 10, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [7624144c62](https://linux-hardware.org/?probe=7624144c62) | Apr 08, 2024 |
| Dell          | Latitude 3410               | Notebook    | [0922287873](https://linux-hardware.org/?probe=0922287873) | Apr 08, 2024 |
| Gigabyte      | B250M-Gaming5-CF            | Desktop     | [47d0634e2a](https://linux-hardware.org/?probe=47d0634e2a) | Mar 31, 2024 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [7f4da7e9bd](https://linux-hardware.org/?probe=7f4da7e9bd) | Mar 30, 2024 |
| HP            | ProBook 450 G2              | Notebook    | [86529bcb5e](https://linux-hardware.org/?probe=86529bcb5e) | Mar 22, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [899cb71147](https://linux-hardware.org/?probe=899cb71147) | Mar 22, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [eb26cf21f5](https://linux-hardware.org/?probe=eb26cf21f5) | Mar 16, 2024 |
| MSI           | G41M-P33 Combo              | Desktop     | [20fee7f4de](https://linux-hardware.org/?probe=20fee7f4de) | Mar 07, 2024 |
| MSI           | G41M-P33 Combo              | Desktop     | [f2cca8436d](https://linux-hardware.org/?probe=f2cca8436d) | Mar 07, 2024 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [2e1dca9bf1](https://linux-hardware.org/?probe=2e1dca9bf1) | Mar 06, 2024 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7105302b8d](https://linux-hardware.org/?probe=7105302b8d) | Mar 04, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [20d430b7b1](https://linux-hardware.org/?probe=20d430b7b1) | Mar 03, 2024 |
| HUAWEI        | RLEF-XX                     | Notebook    | [17ed092beb](https://linux-hardware.org/?probe=17ed092beb) | Feb 27, 2024 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [a58943c0ce](https://linux-hardware.org/?probe=a58943c0ce) | Feb 23, 2024 |
| Acer          | Aspire A315-57G             | Notebook    | [060f07dd4c](https://linux-hardware.org/?probe=060f07dd4c) | Feb 20, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [5398646f81](https://linux-hardware.org/?probe=5398646f81) | Feb 11, 2024 |
| HP            | Laptop 15-da1xxx            | Notebook    | [f82dcf7a8c](https://linux-hardware.org/?probe=f82dcf7a8c) | Feb 08, 2024 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | Notebook    | [8b109272ff](https://linux-hardware.org/?probe=8b109272ff) | Feb 07, 2024 |
| Dell          | XPS 13 7390                 | Notebook    | [d68f1566cc](https://linux-hardware.org/?probe=d68f1566cc) | Feb 07, 2024 |
| MSI           | PRO B650-S WIFI             | Desktop     | [08d3d9b75e](https://linux-hardware.org/?probe=08d3d9b75e) | Jan 26, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [25b00c66d6](https://linux-hardware.org/?probe=25b00c66d6) | Jan 26, 2024 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [73f56ca35a](https://linux-hardware.org/?probe=73f56ca35a) | Jan 26, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [38b1e0aa62](https://linux-hardware.org/?probe=38b1e0aa62) | Jan 23, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [d6aeeb6ece](https://linux-hardware.org/?probe=d6aeeb6ece) | Jan 21, 2024 |
| Acer          | Nitro AN515-51              | Notebook    | [4ce3126197](https://linux-hardware.org/?probe=4ce3126197) | Jan 14, 2024 |
| Acer          | Nitro AN515-51              | Notebook    | [44f67c403a](https://linux-hardware.org/?probe=44f67c403a) | Jan 14, 2024 |
| MSI           | B450M-A PRO MAX             | Desktop     | [09ec307e39](https://linux-hardware.org/?probe=09ec307e39) | Jan 10, 2024 |
| Dell          | Latitude 5400               | Notebook    | [9e318e9b78](https://linux-hardware.org/?probe=9e318e9b78) | Jan 03, 2024 |
| Dell          | Latitude 5400               | Notebook    | [59a90bd726](https://linux-hardware.org/?probe=59a90bd726) | Jan 03, 2024 |
| MSI           | Modern 14 B4MW              | Notebook    | [f1f1b527ce](https://linux-hardware.org/?probe=f1f1b527ce) | Jan 02, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [082442f033](https://linux-hardware.org/?probe=082442f033) | Jan 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c56c8e1bcf](https://linux-hardware.org/?probe=c56c8e1bcf) | Dec 27, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [f9d9539e00](https://linux-hardware.org/?probe=f9d9539e00) | Dec 21, 2023 |
| Google        | Pantheon                    | Notebook    | [f4640ed7c1](https://linux-hardware.org/?probe=f4640ed7c1) | Dec 19, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [82be8c9bb4](https://linux-hardware.org/?probe=82be8c9bb4) | Dec 18, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [8ad076eb34](https://linux-hardware.org/?probe=8ad076eb34) | Dec 18, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [7f648e3b6e](https://linux-hardware.org/?probe=7f648e3b6e) | Dec 15, 2023 |
| Timi          | TM1709                      | Notebook    | [f566951fd0](https://linux-hardware.org/?probe=f566951fd0) | Dec 14, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [aac962ade2](https://linux-hardware.org/?probe=aac962ade2) | Dec 14, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [85cb328b2d](https://linux-hardware.org/?probe=85cb328b2d) | Dec 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [f8b53d98cc](https://linux-hardware.org/?probe=f8b53d98cc) | Dec 10, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [65530f33de](https://linux-hardware.org/?probe=65530f33de) | Dec 06, 2023 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [997c41ef61](https://linux-hardware.org/?probe=997c41ef61) | Dec 01, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [945c324d2b](https://linux-hardware.org/?probe=945c324d2b) | Nov 30, 2023 |
| Fujitsu       | FMVC06001                   | Notebook    | [122e4a9608](https://linux-hardware.org/?probe=122e4a9608) | Nov 20, 2023 |
| HP            | Laptop 15s-du1xxx           | Notebook    | [a49d6872fd](https://linux-hardware.org/?probe=a49d6872fd) | Nov 20, 2023 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [fc34295ec7](https://linux-hardware.org/?probe=fc34295ec7) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [be7a52191a](https://linux-hardware.org/?probe=be7a52191a) | Nov 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [6ec54b38a2](https://linux-hardware.org/?probe=6ec54b38a2) | Nov 07, 2023 |
| HP            | Pavilion g7                 | Notebook    | [b3dc228560](https://linux-hardware.org/?probe=b3dc228560) | Nov 02, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [cb27a04bd5](https://linux-hardware.org/?probe=cb27a04bd5) | Oct 26, 2023 |
| ECS           | CHICAGO2                    | Desktop     | [e33ec52f5a](https://linux-hardware.org/?probe=e33ec52f5a) | Oct 21, 2023 |
| ASUSTek       | X442UAR                     | Notebook    | [454f454638](https://linux-hardware.org/?probe=454f454638) | Oct 21, 2023 |
| ASUSTek       | M11BB                       | Desktop     | [acf7108592](https://linux-hardware.org/?probe=acf7108592) | Oct 20, 2023 |
| ASUSTek       | M11BB                       | Desktop     | [38436a17ef](https://linux-hardware.org/?probe=38436a17ef) | Oct 20, 2023 |
| ASUSTek       | X450LCP                     | Notebook    | [ae3fec47c6](https://linux-hardware.org/?probe=ae3fec47c6) | Oct 19, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [cb3ee2550b](https://linux-hardware.org/?probe=cb3ee2550b) | Oct 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [e57363450f](https://linux-hardware.org/?probe=e57363450f) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [71256e953b](https://linux-hardware.org/?probe=71256e953b) | Oct 16, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [53c0055ced](https://linux-hardware.org/?probe=53c0055ced) | Oct 13, 2023 |
| HP            | 2B5E                        | Desktop     | [9dff375d05](https://linux-hardware.org/?probe=9dff375d05) | Oct 12, 2023 |
| Gigabyte      | B150M-D3V-CF                | Desktop     | [75b228c5fb](https://linux-hardware.org/?probe=75b228c5fb) | Sep 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [128658b9f0](https://linux-hardware.org/?probe=128658b9f0) | Sep 26, 2023 |
| MSI           | PRO H410M-B                 | Desktop     | [dd6815e149](https://linux-hardware.org/?probe=dd6815e149) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c63ae3378d](https://linux-hardware.org/?probe=c63ae3378d) | Sep 22, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0f189d3c2a](https://linux-hardware.org/?probe=0f189d3c2a) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f7280def0d](https://linux-hardware.org/?probe=f7280def0d) | Sep 20, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [1e8bb82a4a](https://linux-hardware.org/?probe=1e8bb82a4a) | Sep 16, 2023 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [8bc40fd9f1](https://linux-hardware.org/?probe=8bc40fd9f1) | Sep 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [699fb7e97e](https://linux-hardware.org/?probe=699fb7e97e) | Sep 07, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [989134a7c5](https://linux-hardware.org/?probe=989134a7c5) | Sep 06, 2023 |
| Gigabyte      | Z690 AORUS ELITE DDR4       | Desktop     | [7e7d27d9f2](https://linux-hardware.org/?probe=7e7d27d9f2) | Sep 03, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [9675488adc](https://linux-hardware.org/?probe=9675488adc) | Aug 28, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [29e062fb36](https://linux-hardware.org/?probe=29e062fb36) | Aug 27, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9c34344e6d](https://linux-hardware.org/?probe=9c34344e6d) | Aug 26, 2023 |
| Biostar       | H410MH                      | Desktop     | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [2ec62f31c9](https://linux-hardware.org/?probe=2ec62f31c9) | Aug 12, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [72eb04ca17](https://linux-hardware.org/?probe=72eb04ca17) | Aug 08, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [a4a6f81455](https://linux-hardware.org/?probe=a4a6f81455) | Aug 05, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [ef010c9d51](https://linux-hardware.org/?probe=ef010c9d51) | Aug 05, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [8aad3290a7](https://linux-hardware.org/?probe=8aad3290a7) | Aug 03, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [3f15239dd2](https://linux-hardware.org/?probe=3f15239dd2) | Jul 16, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [8974860f56](https://linux-hardware.org/?probe=8974860f56) | Jul 12, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [cc4f862316](https://linux-hardware.org/?probe=cc4f862316) | Jul 11, 2023 |
| HP            | Notebook                    | Notebook    | [9487146a2f](https://linux-hardware.org/?probe=9487146a2f) | Jun 09, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [c64ff76dba](https://linux-hardware.org/?probe=c64ff76dba) | Jun 09, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a34c3550be](https://linux-hardware.org/?probe=a34c3550be) | Jun 06, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4808ee44b5](https://linux-hardware.org/?probe=4808ee44b5) | Jun 04, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [abf4b3f5d2](https://linux-hardware.org/?probe=abf4b3f5d2) | Jun 02, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [4092d4fe1b](https://linux-hardware.org/?probe=4092d4fe1b) | Jun 02, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [f73c3032af](https://linux-hardware.org/?probe=f73c3032af) | May 30, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [12fe930fb2](https://linux-hardware.org/?probe=12fe930fb2) | May 30, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [f8ec1083ad](https://linux-hardware.org/?probe=f8ec1083ad) | May 26, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [eb636c0b30](https://linux-hardware.org/?probe=eb636c0b30) | May 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [2a2712560e](https://linux-hardware.org/?probe=2a2712560e) | May 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [38482c1a10](https://linux-hardware.org/?probe=38482c1a10) | May 15, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [cc4f992884](https://linux-hardware.org/?probe=cc4f992884) | May 12, 2023 |
| ASRock        | H470M-HDV                   | Desktop     | [36257aa0a2](https://linux-hardware.org/?probe=36257aa0a2) | May 11, 2023 |
| ASUSTek       | X556UQK                     | Notebook    | [12d23bdebb](https://linux-hardware.org/?probe=12d23bdebb) | May 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [6fc095ce39](https://linux-hardware.org/?probe=6fc095ce39) | May 04, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b97932d8f1](https://linux-hardware.org/?probe=b97932d8f1) | May 03, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [c4841e9b59](https://linux-hardware.org/?probe=c4841e9b59) | May 02, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [a1c1008bf1](https://linux-hardware.org/?probe=a1c1008bf1) | Apr 29, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [ce4700304c](https://linux-hardware.org/?probe=ce4700304c) | Apr 26, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [b9846b05e7](https://linux-hardware.org/?probe=b9846b05e7) | Apr 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [c27abc2880](https://linux-hardware.org/?probe=c27abc2880) | Apr 17, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [802d7b7c3f](https://linux-hardware.org/?probe=802d7b7c3f) | Apr 07, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [874157891b](https://linux-hardware.org/?probe=874157891b) | Apr 06, 2023 |
| Lenovo        | ThinkPad X220 4290CTO       | Notebook    | [5dd9277838](https://linux-hardware.org/?probe=5dd9277838) | Apr 04, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6af08c4bfe](https://linux-hardware.org/?probe=6af08c4bfe) | Mar 30, 2023 |
| Lenovo        | ThinkPad T470s 20HGS23V0... | Notebook    | [6f0d3fd82b](https://linux-hardware.org/?probe=6f0d3fd82b) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b860e76ead](https://linux-hardware.org/?probe=b860e76ead) | Mar 26, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [2940ea3b40](https://linux-hardware.org/?probe=2940ea3b40) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [ec2390af74](https://linux-hardware.org/?probe=ec2390af74) | Mar 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e3e0efa236](https://linux-hardware.org/?probe=e3e0efa236) | Mar 20, 2023 |
| Lenovo        | LEGION5PRO-16ACH6H 82JQ     | Notebook    | [4f3cbedf85](https://linux-hardware.org/?probe=4f3cbedf85) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [a0cf486df2](https://linux-hardware.org/?probe=a0cf486df2) | Mar 19, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [7d708fea96](https://linux-hardware.org/?probe=7d708fea96) | Mar 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [418b5dd7ff](https://linux-hardware.org/?probe=418b5dd7ff) | Feb 27, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [47db699ed6](https://linux-hardware.org/?probe=47db699ed6) | Feb 18, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c1e5226b6e](https://linux-hardware.org/?probe=c1e5226b6e) | Feb 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [6cda8724a4](https://linux-hardware.org/?probe=6cda8724a4) | Feb 14, 2023 |
| Toshiba       | Satellite Pro L510          | Notebook    | [c8dc3a76e5](https://linux-hardware.org/?probe=c8dc3a76e5) | Feb 06, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [a2ab102eeb](https://linux-hardware.org/?probe=a2ab102eeb) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [ddb7f53b34](https://linux-hardware.org/?probe=ddb7f53b34) | Feb 03, 2023 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [2793159580](https://linux-hardware.org/?probe=2793159580) | Feb 03, 2023 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [63143e2bf5](https://linux-hardware.org/?probe=63143e2bf5) | Feb 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f8630776ca](https://linux-hardware.org/?probe=f8630776ca) | Jan 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [af63cfc79a](https://linux-hardware.org/?probe=af63cfc79a) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f0d73c960e](https://linux-hardware.org/?probe=f0d73c960e) | Jan 25, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [cf6bdca9c4](https://linux-hardware.org/?probe=cf6bdca9c4) | Jan 23, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | Notebook    | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [c3f150a8f4](https://linux-hardware.org/?probe=c3f150a8f4) | Jan 18, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [d2ac110bfb](https://linux-hardware.org/?probe=d2ac110bfb) | Jan 18, 2023 |
| MSI           | Modern 14 B10MW             | Notebook    | [ad5c9e7f6a](https://linux-hardware.org/?probe=ad5c9e7f6a) | Jan 18, 2023 |
| HP            | Notebook                    | Notebook    | [fbdf174a63](https://linux-hardware.org/?probe=fbdf174a63) | Jan 16, 2023 |
| Dell          | Latitude 5300               | Notebook    | [8149377926](https://linux-hardware.org/?probe=8149377926) | Jan 15, 2023 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [bddd00febc](https://linux-hardware.org/?probe=bddd00febc) | Jan 15, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [e5773ce5f8](https://linux-hardware.org/?probe=e5773ce5f8) | Jan 11, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [53043b7d75](https://linux-hardware.org/?probe=53043b7d75) | Jan 10, 2023 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [3566221932](https://linux-hardware.org/?probe=3566221932) | Jan 06, 2023 |
| ASUSTek       | P453UA                      | Notebook    | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3a505870ba](https://linux-hardware.org/?probe=3a505870ba) | Dec 22, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [7c8e3bbb6a](https://linux-hardware.org/?probe=7c8e3bbb6a) | Dec 21, 2022 |
| HP            | 15                          | Notebook    | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [4b44d6e506](https://linux-hardware.org/?probe=4b44d6e506) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | Desktop     | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| Acer          | Aspire E5-471               | Notebook    | [3e9c2f0201](https://linux-hardware.org/?probe=3e9c2f0201) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | Notebook    | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [da83c13da3](https://linux-hardware.org/?probe=da83c13da3) | Nov 30, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [459c2ba743](https://linux-hardware.org/?probe=459c2ba743) | Nov 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9836f71cb7](https://linux-hardware.org/?probe=9836f71cb7) | Nov 24, 2022 |
| Lenovo        | G40-70 20369                | Notebook    | [aafdfb20ff](https://linux-hardware.org/?probe=aafdfb20ff) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9b9a13f34f](https://linux-hardware.org/?probe=9b9a13f34f) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [4efc557c1b](https://linux-hardware.org/?probe=4efc557c1b) | Nov 24, 2022 |
| HP            | 15                          | Notebook    | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| Dell          | G7 7700                     | Notebook    | [2440bebe2c](https://linux-hardware.org/?probe=2440bebe2c) | Nov 15, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [2c342fa72f](https://linux-hardware.org/?probe=2c342fa72f) | Nov 14, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b5080a1102](https://linux-hardware.org/?probe=b5080a1102) | Nov 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2548bcefe0](https://linux-hardware.org/?probe=2548bcefe0) | Nov 04, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [fbe835b8ef](https://linux-hardware.org/?probe=fbe835b8ef) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [e1a32857ba](https://linux-hardware.org/?probe=e1a32857ba) | Oct 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [9357d641ef](https://linux-hardware.org/?probe=9357d641ef) | Oct 18, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [068a780cce](https://linux-hardware.org/?probe=068a780cce) | Oct 17, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [d4c5e9f853](https://linux-hardware.org/?probe=d4c5e9f853) | Oct 16, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [5dd9f2cda4](https://linux-hardware.org/?probe=5dd9f2cda4) | Oct 09, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [ee4c1a5f66](https://linux-hardware.org/?probe=ee4c1a5f66) | Oct 03, 2022 |
| Biostar       | G41D3C                      | Desktop     | [97ee103719](https://linux-hardware.org/?probe=97ee103719) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8f28254d53](https://linux-hardware.org/?probe=8f28254d53) | Sep 20, 2022 |
| Dell          | Inspiron 14-3467            | Notebook    | [e92b56817a](https://linux-hardware.org/?probe=e92b56817a) | Sep 14, 2022 |
| Biostar       | G41D3C                      | Desktop     | [280212d494](https://linux-hardware.org/?probe=280212d494) | Sep 13, 2022 |
| Biostar       | G41D3C                      | Desktop     | [6d15a54350](https://linux-hardware.org/?probe=6d15a54350) | Sep 13, 2022 |
| Biostar       | G41D3C                      | Desktop     | [09d42cd406](https://linux-hardware.org/?probe=09d42cd406) | Sep 13, 2022 |
| Biostar       | G41D3C                      | Desktop     | [c45809d681](https://linux-hardware.org/?probe=c45809d681) | Sep 13, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [4fbc7a765f](https://linux-hardware.org/?probe=4fbc7a765f) | Sep 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [aa1cd85ea9](https://linux-hardware.org/?probe=aa1cd85ea9) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4e798ff22](https://linux-hardware.org/?probe=d4e798ff22) | Sep 07, 2022 |
| Toshiba       | Satellite L645              | Notebook    | [642a6f7602](https://linux-hardware.org/?probe=642a6f7602) | Sep 03, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1d04855f84](https://linux-hardware.org/?probe=1d04855f84) | Aug 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7439a7400d](https://linux-hardware.org/?probe=7439a7400d) | Aug 27, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [262ff7d08a](https://linux-hardware.org/?probe=262ff7d08a) | Aug 27, 2022 |
| HP            | Pavilion x360 m3 Convert... | Convertible | [bde621edc4](https://linux-hardware.org/?probe=bde621edc4) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [e04617befa](https://linux-hardware.org/?probe=e04617befa) | Aug 17, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [db7b7b3126](https://linux-hardware.org/?probe=db7b7b3126) | Aug 15, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [ae85f68d58](https://linux-hardware.org/?probe=ae85f68d58) | Aug 15, 2022 |
| Acer          | Aspire M5-581T              | Notebook    | [7efdb0e467](https://linux-hardware.org/?probe=7efdb0e467) | Aug 14, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [97f75c2be0](https://linux-hardware.org/?probe=97f75c2be0) | Aug 13, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [534c1142c2](https://linux-hardware.org/?probe=534c1142c2) | Aug 10, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0724d34f68](https://linux-hardware.org/?probe=0724d34f68) | Aug 10, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [41f0d0b264](https://linux-hardware.org/?probe=41f0d0b264) | Aug 02, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [c6643cb779](https://linux-hardware.org/?probe=c6643cb779) | Jul 28, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [2dc0ffa0d1](https://linux-hardware.org/?probe=2dc0ffa0d1) | Jul 26, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| HP            | 14                          | Notebook    | [816a62dde0](https://linux-hardware.org/?probe=816a62dde0) | Jul 07, 2022 |
| Timi          | Mi NoteBook Pro             | Notebook    | [046a18dc14](https://linux-hardware.org/?probe=046a18dc14) | Jul 03, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [9a35c1249b](https://linux-hardware.org/?probe=9a35c1249b) | Jun 30, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c8f0217b26](https://linux-hardware.org/?probe=c8f0217b26) | Jun 29, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [d3af5b938a](https://linux-hardware.org/?probe=d3af5b938a) | Jun 29, 2022 |
| Gigabyte      | B360M HD3                   | Desktop     | [b35e9f3e5c](https://linux-hardware.org/?probe=b35e9f3e5c) | Jun 28, 2022 |
| ASUSTek       | X507UB                      | Notebook    | [0ba0fc4089](https://linux-hardware.org/?probe=0ba0fc4089) | Jun 28, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [4b202c1285](https://linux-hardware.org/?probe=4b202c1285) | Jun 22, 2022 |
| MSI           | H61M-P31/W8                 | Desktop     | [7b8cc6556b](https://linux-hardware.org/?probe=7b8cc6556b) | Jun 12, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [758bdaefe9](https://linux-hardware.org/?probe=758bdaefe9) | May 21, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [99283be07b](https://linux-hardware.org/?probe=99283be07b) | May 20, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b85af00b16](https://linux-hardware.org/?probe=b85af00b16) | May 18, 2022 |
| Dell          | Latitude 5580               | Notebook    | [18cefe0718](https://linux-hardware.org/?probe=18cefe0718) | May 17, 2022 |
| Dell          | Inspiron 5505               | Notebook    | [c1353ba170](https://linux-hardware.org/?probe=c1353ba170) | May 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [f09183023d](https://linux-hardware.org/?probe=f09183023d) | May 10, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [71e0ef1fc9](https://linux-hardware.org/?probe=71e0ef1fc9) | May 07, 2022 |
| HP            | 240 G3                      | Notebook    | [7062083e69](https://linux-hardware.org/?probe=7062083e69) | May 06, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3055b0e95f](https://linux-hardware.org/?probe=3055b0e95f) | May 05, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [88f6586c4b](https://linux-hardware.org/?probe=88f6586c4b) | May 02, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ab11d6ac2f](https://linux-hardware.org/?probe=ab11d6ac2f) | Apr 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6e993bc145](https://linux-hardware.org/?probe=6e993bc145) | Apr 10, 2022 |
| Unknown       | Unknown                     | Desktop     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [19623aa8b6](https://linux-hardware.org/?probe=19623aa8b6) | Apr 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [287aa3ba8e](https://linux-hardware.org/?probe=287aa3ba8e) | Apr 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| HP            | ZHAN 66 Pro A 14 G4 Note... | Notebook    | [8199781e64](https://linux-hardware.org/?probe=8199781e64) | Mar 28, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [33d1544ea1](https://linux-hardware.org/?probe=33d1544ea1) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [52ce856be5](https://linux-hardware.org/?probe=52ce856be5) | Mar 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [1dd07eeee0](https://linux-hardware.org/?probe=1dd07eeee0) | Mar 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [321d0c1b4a](https://linux-hardware.org/?probe=321d0c1b4a) | Mar 23, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [5db5bac582](https://linux-hardware.org/?probe=5db5bac582) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [cb949f34eb](https://linux-hardware.org/?probe=cb949f34eb) | Mar 20, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [da23c76a90](https://linux-hardware.org/?probe=da23c76a90) | Mar 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [fd9e66788c](https://linux-hardware.org/?probe=fd9e66788c) | Mar 17, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e141c99bf2](https://linux-hardware.org/?probe=e141c99bf2) | Mar 09, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [87d97b3c00](https://linux-hardware.org/?probe=87d97b3c00) | Mar 05, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [d7a873bf3d](https://linux-hardware.org/?probe=d7a873bf3d) | Feb 27, 2022 |
| Acer          | TravelMate P214-53          | Notebook    | [87f30f494f](https://linux-hardware.org/?probe=87f30f494f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [62c028a881](https://linux-hardware.org/?probe=62c028a881) | Feb 16, 2022 |
| Biostar       | H55 HD                      | Desktop     | [b0d5843b6e](https://linux-hardware.org/?probe=b0d5843b6e) | Feb 13, 2022 |
| HP            | Compaq 8000 Elite CMT PC    | Desktop     | [42647bc4b3](https://linux-hardware.org/?probe=42647bc4b3) | Feb 12, 2022 |
| HP            | 339A                        | Desktop     | [6f8e63bfb0](https://linux-hardware.org/?probe=6f8e63bfb0) | Feb 11, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [0c13bfa27b](https://linux-hardware.org/?probe=0c13bfa27b) | Feb 10, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [8e73dc39ab](https://linux-hardware.org/?probe=8e73dc39ab) | Feb 09, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [42e37d6172](https://linux-hardware.org/?probe=42e37d6172) | Feb 07, 2022 |
| Biostar       | H55 HD                      | Desktop     | [e08da3e685](https://linux-hardware.org/?probe=e08da3e685) | Feb 03, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [47c47a0121](https://linux-hardware.org/?probe=47c47a0121) | Feb 02, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [d7431ab69e](https://linux-hardware.org/?probe=d7431ab69e) | Jan 31, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [76d17811e3](https://linux-hardware.org/?probe=76d17811e3) | Jan 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [caca9680a9](https://linux-hardware.org/?probe=caca9680a9) | Jan 25, 2022 |
| Lenovo        | ThinkPad X230 2324A82       | Notebook    | [be92c29259](https://linux-hardware.org/?probe=be92c29259) | Jan 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1e89749691](https://linux-hardware.org/?probe=1e89749691) | Jan 22, 2022 |
| MSI           | FM2-A55M-E33                | Desktop     | [ac35b74090](https://linux-hardware.org/?probe=ac35b74090) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [88f62c8333](https://linux-hardware.org/?probe=88f62c8333) | Jan 15, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [38a7870ece](https://linux-hardware.org/?probe=38a7870ece) | Jan 13, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [2fb0411785](https://linux-hardware.org/?probe=2fb0411785) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [0d69dca8f3](https://linux-hardware.org/?probe=0d69dca8f3) | Jan 04, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [692274162f](https://linux-hardware.org/?probe=692274162f) | Jan 04, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e6a4a21d5c](https://linux-hardware.org/?probe=e6a4a21d5c) | Jan 02, 2022 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [8e8da56e93](https://linux-hardware.org/?probe=8e8da56e93) | Jan 01, 2022 |
| OEM           | Unknown                     | Desktop     | [6adc4b5659](https://linux-hardware.org/?probe=6adc4b5659) | Jan 01, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [b674024789](https://linux-hardware.org/?probe=b674024789) | Dec 30, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [209e15690e](https://linux-hardware.org/?probe=209e15690e) | Dec 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [00696e3398](https://linux-hardware.org/?probe=00696e3398) | Dec 28, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [7280895518](https://linux-hardware.org/?probe=7280895518) | Dec 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [56d5bb8659](https://linux-hardware.org/?probe=56d5bb8659) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [6ab6a89db8](https://linux-hardware.org/?probe=6ab6a89db8) | Dec 12, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [3cd505591d](https://linux-hardware.org/?probe=3cd505591d) | Dec 11, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Dell          | Latitude 7480               | Notebook    | [480ad981d9](https://linux-hardware.org/?probe=480ad981d9) | Dec 07, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [42edbb20ce](https://linux-hardware.org/?probe=42edbb20ce) | Dec 04, 2021 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [e155882ffa](https://linux-hardware.org/?probe=e155882ffa) | Dec 02, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [07bcad31f5](https://linux-hardware.org/?probe=07bcad31f5) | Dec 02, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [cf0cd5c862](https://linux-hardware.org/?probe=cf0cd5c862) | Dec 01, 2021 |
| ASUSTek       | UX430UQ                     | Notebook    | [5cd208a361](https://linux-hardware.org/?probe=5cd208a361) | Dec 01, 2021 |
| ASUSTek       | P453UJ                      | Notebook    | [056cba6efd](https://linux-hardware.org/?probe=056cba6efd) | Nov 28, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [aa0a0e67b3](https://linux-hardware.org/?probe=aa0a0e67b3) | Nov 26, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [9bffff74e0](https://linux-hardware.org/?probe=9bffff74e0) | Nov 26, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [09b0e5058d](https://linux-hardware.org/?probe=09b0e5058d) | Nov 23, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [623b2b0ba9](https://linux-hardware.org/?probe=623b2b0ba9) | Nov 19, 2021 |
| HP            | Elite x2 1012 G2            | Tablet      | [47d816d00f](https://linux-hardware.org/?probe=47d816d00f) | Nov 12, 2021 |
| MSI           | 990FXA-GD65                 | Desktop     | [6d2cade66c](https://linux-hardware.org/?probe=6d2cade66c) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [efd1c194ac](https://linux-hardware.org/?probe=efd1c194ac) | Nov 11, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [0802656d19](https://linux-hardware.org/?probe=0802656d19) | Nov 11, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [312e04d7f9](https://linux-hardware.org/?probe=312e04d7f9) | Nov 09, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f1f7ca30e5](https://linux-hardware.org/?probe=f1f7ca30e5) | Nov 05, 2021 |
| ASUSTek       | X442UAR                     | Notebook    | [0db140fa3d](https://linux-hardware.org/?probe=0db140fa3d) | Nov 03, 2021 |
| OEM           | Intel H81                   | Desktop     | [a4e298caf1](https://linux-hardware.org/?probe=a4e298caf1) | Nov 02, 2021 |
| OEM           | Intel H81                   | Desktop     | [50758cfaf3](https://linux-hardware.org/?probe=50758cfaf3) | Oct 26, 2021 |
| OEM           | Intel H81                   | Desktop     | [e997f638bc](https://linux-hardware.org/?probe=e997f638bc) | Oct 26, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [356632b328](https://linux-hardware.org/?probe=356632b328) | Oct 19, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [d377aa2b23](https://linux-hardware.org/?probe=d377aa2b23) | Oct 17, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [7447071c00](https://linux-hardware.org/?probe=7447071c00) | Oct 16, 2021 |
| MSI           | Boston                      | Desktop     | [77d385bc09](https://linux-hardware.org/?probe=77d385bc09) | Oct 13, 2021 |
| MSI           | Boston                      | Desktop     | [14528f628a](https://linux-hardware.org/?probe=14528f628a) | Oct 13, 2021 |
| HP            | ProBook 450 G5              | Notebook    | [0bf0387391](https://linux-hardware.org/?probe=0bf0387391) | Oct 07, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [6a5bc4355e](https://linux-hardware.org/?probe=6a5bc4355e) | Oct 05, 2021 |
| Acer          | Aspire V5-471               | Notebook    | [4b9f0ceb64](https://linux-hardware.org/?probe=4b9f0ceb64) | Oct 05, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [883e0dec71](https://linux-hardware.org/?probe=883e0dec71) | Sep 19, 2021 |
| Dell          | Latitude E7250              | Notebook    | [275b9204f5](https://linux-hardware.org/?probe=275b9204f5) | Sep 13, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [8109d84e42](https://linux-hardware.org/?probe=8109d84e42) | Sep 12, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [6a9842e166](https://linux-hardware.org/?probe=6a9842e166) | Sep 06, 2021 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [752964e357](https://linux-hardware.org/?probe=752964e357) | Sep 05, 2021 |
| ASUSTek       | X456UQ                      | Notebook    | [6ce8e44ad3](https://linux-hardware.org/?probe=6ce8e44ad3) | Sep 02, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [7a654e5473](https://linux-hardware.org/?probe=7a654e5473) | Aug 28, 2021 |
| Acer          | Aspire 4349                 | Notebook    | [527e511232](https://linux-hardware.org/?probe=527e511232) | Aug 27, 2021 |
| Gigabyte      | B250M-Gaming5-CF            | Desktop     | [c34514576a](https://linux-hardware.org/?probe=c34514576a) | Aug 17, 2021 |
| Intel         | DG31PR AAD97573-302         | Desktop     | [460fc8dfd4](https://linux-hardware.org/?probe=460fc8dfd4) | Aug 08, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [48853e253b](https://linux-hardware.org/?probe=48853e253b) | Aug 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [c672738a0e](https://linux-hardware.org/?probe=c672738a0e) | Aug 04, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | Notebook    | [c22e4ce5b4](https://linux-hardware.org/?probe=c22e4ce5b4) | Jul 29, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [1f6b072c8e](https://linux-hardware.org/?probe=1f6b072c8e) | Jul 24, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [dd58ecd9c7](https://linux-hardware.org/?probe=dd58ecd9c7) | Jul 23, 2021 |
| ASUSTek       | X550JK                      | Notebook    | [ebd01f2605](https://linux-hardware.org/?probe=ebd01f2605) | Jul 22, 2021 |
| Unknown       | Unknown                     | Desktop     | [c6dea4c88d](https://linux-hardware.org/?probe=c6dea4c88d) | Jul 19, 2021 |
| Biostar       | TZ68K+                      | Desktop     | [52ef8197ad](https://linux-hardware.org/?probe=52ef8197ad) | Jul 13, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [3b153ae2f9](https://linux-hardware.org/?probe=3b153ae2f9) | Jun 24, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [988fc9a599](https://linux-hardware.org/?probe=988fc9a599) | Jun 24, 2021 |
| HP            | 15                          | Notebook    | [4f6c5d8c89](https://linux-hardware.org/?probe=4f6c5d8c89) | Jun 22, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [406cb898f1](https://linux-hardware.org/?probe=406cb898f1) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [1927d0abfe](https://linux-hardware.org/?probe=1927d0abfe) | Jun 13, 2021 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [23e735bb8f](https://linux-hardware.org/?probe=23e735bb8f) | Jun 08, 2021 |
| Dell          | 0VHWTR A02                  | Desktop     | [ec7174828a](https://linux-hardware.org/?probe=ec7174828a) | Jun 04, 2021 |
| ASUSTek       | UX310UAK                    | Notebook    | [4a79148721](https://linux-hardware.org/?probe=4a79148721) | Jun 03, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [f52091e51e](https://linux-hardware.org/?probe=f52091e51e) | May 31, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [0226c84811](https://linux-hardware.org/?probe=0226c84811) | May 25, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [b2c4e6f3a5](https://linux-hardware.org/?probe=b2c4e6f3a5) | May 25, 2021 |
| HP            | 15 Notebook PC              | Notebook    | [b34d6d63d9](https://linux-hardware.org/?probe=b34d6d63d9) | May 22, 2021 |
| MSI           | B85M GAMING                 | Desktop     | [4d2529b647](https://linux-hardware.org/?probe=4d2529b647) | May 22, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [8f1510061b](https://linux-hardware.org/?probe=8f1510061b) | May 18, 2021 |
| Lenovo        | ThinkPad T430s 2356GPU      | Notebook    | [e78b76fcf3](https://linux-hardware.org/?probe=e78b76fcf3) | May 18, 2021 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [aba051d387](https://linux-hardware.org/?probe=aba051d387) | May 15, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [fa9f8b7f7e](https://linux-hardware.org/?probe=fa9f8b7f7e) | May 10, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [db1a234412](https://linux-hardware.org/?probe=db1a234412) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [1254eab2b7](https://linux-hardware.org/?probe=1254eab2b7) | May 04, 2021 |
| HP            | 15                          | Notebook    | [fd4d562cd2](https://linux-hardware.org/?probe=fd4d562cd2) | May 04, 2021 |
| MSI           | Summit B14 A11MOT           | Notebook    | [9bdd91f198](https://linux-hardware.org/?probe=9bdd91f198) | May 02, 2021 |
| HP            | ProBook 440 G7              | Notebook    | [dbcbb68258](https://linux-hardware.org/?probe=dbcbb68258) | Apr 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [b2600d2372](https://linux-hardware.org/?probe=b2600d2372) | Apr 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [367455807e](https://linux-hardware.org/?probe=367455807e) | Mar 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1de185d0da](https://linux-hardware.org/?probe=1de185d0da) | Mar 22, 2021 |
| Dell          | Latitude E4300              | Notebook    | [2ccfcf6a1b](https://linux-hardware.org/?probe=2ccfcf6a1b) | Mar 22, 2021 |
| HP            | 15                          | Notebook    | [860412bddc](https://linux-hardware.org/?probe=860412bddc) | Mar 20, 2021 |
| HP            | 15                          | Notebook    | [62447250f9](https://linux-hardware.org/?probe=62447250f9) | Mar 17, 2021 |
| ASUSTek       | H110M-CS                    | Desktop     | [ac52c3630c](https://linux-hardware.org/?probe=ac52c3630c) | Mar 12, 2021 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [4ee1271923](https://linux-hardware.org/?probe=4ee1271923) | Mar 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [6343267ab7](https://linux-hardware.org/?probe=6343267ab7) | Mar 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [47123299d4](https://linux-hardware.org/?probe=47123299d4) | Mar 09, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [a8091a8c28](https://linux-hardware.org/?probe=a8091a8c28) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8f8fe2c911](https://linux-hardware.org/?probe=8f8fe2c911) | Mar 06, 2021 |
| ASUSTek       | X411UNV                     | Notebook    | [009f3bb5e5](https://linux-hardware.org/?probe=009f3bb5e5) | Feb 27, 2021 |
| HP            | 15                          | Notebook    | [e74fa488e9](https://linux-hardware.org/?probe=e74fa488e9) | Feb 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| ASUSTek       | ZenBook UX461FA_UX461FA     | Convertible | [8efc8caada](https://linux-hardware.org/?probe=8efc8caada) | Feb 27, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [b414109f66](https://linux-hardware.org/?probe=b414109f66) | Feb 07, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [08a1160725](https://linux-hardware.org/?probe=08a1160725) | Feb 07, 2021 |
| HP            | Notebook                    | Notebook    | [df39c8aaf8](https://linux-hardware.org/?probe=df39c8aaf8) | Feb 02, 2021 |
| ASUSTek       | X45C                        | Notebook    | [349beec2d5](https://linux-hardware.org/?probe=349beec2d5) | Jan 27, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [474d61d1a7](https://linux-hardware.org/?probe=474d61d1a7) | Jan 27, 2021 |
| HP            | ProBook 450 G2              | Notebook    | [c9e8f99464](https://linux-hardware.org/?probe=c9e8f99464) | Jan 21, 2021 |
| Lenovo        | ThinkPad T450 20BUS2021M    | Notebook    | [60929bb3d1](https://linux-hardware.org/?probe=60929bb3d1) | Jan 21, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [32878b3dae](https://linux-hardware.org/?probe=32878b3dae) | Jan 20, 2021 |
| Gigabyte      | B365M HD3                   | Desktop     | [03b73f8223](https://linux-hardware.org/?probe=03b73f8223) | Jan 20, 2021 |
| HP            | Notebook                    | Notebook    | [d14d8fe5db](https://linux-hardware.org/?probe=d14d8fe5db) | Jan 19, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [0bfbe639fc](https://linux-hardware.org/?probe=0bfbe639fc) | Jan 18, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [e053ef39b6](https://linux-hardware.org/?probe=e053ef39b6) | Jan 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [5ee0809420](https://linux-hardware.org/?probe=5ee0809420) | Jan 16, 2021 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [4c2ddc3c14](https://linux-hardware.org/?probe=4c2ddc3c14) | Jan 10, 2021 |
| HP            | 15                          | Notebook    | [1b3597829c](https://linux-hardware.org/?probe=1b3597829c) | Jan 05, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [150aed5937](https://linux-hardware.org/?probe=150aed5937) | Dec 28, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [f3aaccf16d](https://linux-hardware.org/?probe=f3aaccf16d) | Dec 19, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [eff007611b](https://linux-hardware.org/?probe=eff007611b) | Dec 16, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [1eec63b277](https://linux-hardware.org/?probe=1eec63b277) | Dec 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [da59a1c5a8](https://linux-hardware.org/?probe=da59a1c5a8) | Dec 07, 2020 |
| MSI           | GS63 7RD                    | Notebook    | [51929f5d16](https://linux-hardware.org/?probe=51929f5d16) | Dec 05, 2020 |
| Gigabyte      | B85M-HD3                    | Desktop     | [983f59c8ba](https://linux-hardware.org/?probe=983f59c8ba) | Nov 17, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [4d0297d500](https://linux-hardware.org/?probe=4d0297d500) | Nov 15, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [2898db77af](https://linux-hardware.org/?probe=2898db77af) | Nov 14, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [399693b152](https://linux-hardware.org/?probe=399693b152) | Nov 04, 2020 |
| HP            | 15                          | Notebook    | [751dbba280](https://linux-hardware.org/?probe=751dbba280) | Nov 04, 2020 |
| Unknown       | Unknown                     | Desktop     | [49351fb74d](https://linux-hardware.org/?probe=49351fb74d) | Nov 03, 2020 |
| Unknown       | Unknown                     | Desktop     | [a5450c668e](https://linux-hardware.org/?probe=a5450c668e) | Oct 30, 2020 |
| ASRock        | AB350 Pro4                  | Desktop     | [7e48c5dac7](https://linux-hardware.org/?probe=7e48c5dac7) | Oct 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [20da8831d7](https://linux-hardware.org/?probe=20da8831d7) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [6abbe0be7c](https://linux-hardware.org/?probe=6abbe0be7c) | Oct 29, 2020 |
| Notebook      | DCL C483                    | Notebook    | [ed2bb10c86](https://linux-hardware.org/?probe=ed2bb10c86) | Oct 29, 2020 |
| ASUSTek       | H110M-CS                    | Desktop     | [4bc7a25c4b](https://linux-hardware.org/?probe=4bc7a25c4b) | Oct 29, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [7a6ee90819](https://linux-hardware.org/?probe=7a6ee90819) | Oct 29, 2020 |
| HP            | ENVY Sleekbook 4            | Notebook    | [b2377a6388](https://linux-hardware.org/?probe=b2377a6388) | Oct 29, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [c85f72911e](https://linux-hardware.org/?probe=c85f72911e) | Oct 29, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [1f7d96b34a](https://linux-hardware.org/?probe=1f7d96b34a) | Oct 27, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [76e61701fa](https://linux-hardware.org/?probe=76e61701fa) | Oct 24, 2020 |
| ASUSTek       | P453UA                      | Notebook    | [a376addbeb](https://linux-hardware.org/?probe=a376addbeb) | Oct 21, 2020 |
| Acer          | Aspire E5-575               | Notebook    | [218b3ce742](https://linux-hardware.org/?probe=218b3ce742) | Oct 12, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [da1765fe36](https://linux-hardware.org/?probe=da1765fe36) | Oct 11, 2020 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [a9c53146fc](https://linux-hardware.org/?probe=a9c53146fc) | Oct 10, 2020 |
| Acer          | Aspire A515-51G             | Notebook    | [be8091856c](https://linux-hardware.org/?probe=be8091856c) | Oct 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [a6f1865423](https://linux-hardware.org/?probe=a6f1865423) | Oct 07, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [75933321b6](https://linux-hardware.org/?probe=75933321b6) | Oct 02, 2020 |
| Acer          | Aspire 4752                 | Notebook    | [ae7fe5907d](https://linux-hardware.org/?probe=ae7fe5907d) | Sep 27, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [ed0ef70a05](https://linux-hardware.org/?probe=ed0ef70a05) | Sep 19, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [871d27c2e8](https://linux-hardware.org/?probe=871d27c2e8) | Sep 18, 2020 |
| Gigabyte      | GA-E350N                    | Desktop     | [3f442c236c](https://linux-hardware.org/?probe=3f442c236c) | Sep 18, 2020 |
| HP            | ProBook 440 G5              | Notebook    | [d7b1ce1a01](https://linux-hardware.org/?probe=d7b1ce1a01) | Sep 15, 2020 |
| Notebook      | N2x0LU                      | Notebook    | [86354a1c26](https://linux-hardware.org/?probe=86354a1c26) | Sep 14, 2020 |
| ASUSTek       | X510UQ                      | Notebook    | [e289d19d20](https://linux-hardware.org/?probe=e289d19d20) | Sep 14, 2020 |
| ASRock        | Z77 Pro3                    | Desktop     | [8d6db6e2d3](https://linux-hardware.org/?probe=8d6db6e2d3) | Sep 09, 2020 |
| ASUSTek       | X555LF                      | Notebook    | [22629ba9b2](https://linux-hardware.org/?probe=22629ba9b2) | Sep 07, 2020 |
| Lenovo        | ThinkPad E490 20N9S1XE00    | Notebook    | [43ddcf3c95](https://linux-hardware.org/?probe=43ddcf3c95) | Sep 06, 2020 |
| Unknown       | Unknown                     | Phone       | [d4a5776865](https://linux-hardware.org/?probe=d4a5776865) | Sep 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [38548d7877](https://linux-hardware.org/?probe=38548d7877) | Sep 01, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [3edf866f94](https://linux-hardware.org/?probe=3edf866f94) | Aug 22, 2020 |
| Acer          | Aspire E5-576               | Notebook    | [3a9beeb9f4](https://linux-hardware.org/?probe=3a9beeb9f4) | Aug 16, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [3c3b21f81b](https://linux-hardware.org/?probe=3c3b21f81b) | Aug 15, 2020 |
| HP            | 14                          | Notebook    | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| SYS           | H310CH5-TI2                 | Desktop     | [fb33742784](https://linux-hardware.org/?probe=fb33742784) | Aug 06, 2020 |
| HP            | EliteBook 850 G2            | Notebook    | [1c81c3c24d](https://linux-hardware.org/?probe=1c81c3c24d) | Jul 30, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [27a9cd08a6](https://linux-hardware.org/?probe=27a9cd08a6) | Jul 26, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [f1ef1518c4](https://linux-hardware.org/?probe=f1ef1518c4) | Jul 25, 2020 |
| Gigabyte      | B250M-HD3-CF                | Desktop     | [bf80f266b6](https://linux-hardware.org/?probe=bf80f266b6) | Jul 25, 2020 |
| Acer          | Aspire E5-473               | Notebook    | [9c3656a710](https://linux-hardware.org/?probe=9c3656a710) | Jul 24, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [3c50b289eb](https://linux-hardware.org/?probe=3c50b289eb) | Jul 21, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [e800855127](https://linux-hardware.org/?probe=e800855127) | Jul 21, 2020 |
| Dell          | Latitude E7470              | Notebook    | [74e59971a2](https://linux-hardware.org/?probe=74e59971a2) | Jul 09, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [eb79a1863c](https://linux-hardware.org/?probe=eb79a1863c) | Jul 08, 2020 |
| ASUSTek       | X200CA                      | Notebook    | [374493e07f](https://linux-hardware.org/?probe=374493e07f) | Jul 08, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [04f260c99a](https://linux-hardware.org/?probe=04f260c99a) | Jul 06, 2020 |
| HP            | EliteBook 2570p             | Notebook    | [aa5a987949](https://linux-hardware.org/?probe=aa5a987949) | Jul 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [e8be3d4a45](https://linux-hardware.org/?probe=e8be3d4a45) | Jul 02, 2020 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [d59cf3e39f](https://linux-hardware.org/?probe=d59cf3e39f) | Jun 21, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | Notebook    | [bedb334316](https://linux-hardware.org/?probe=bedb334316) | Jun 11, 2020 |
| Gigabyte      | B75MS                       | Desktop     | [116d7e4473](https://linux-hardware.org/?probe=116d7e4473) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [0690307575](https://linux-hardware.org/?probe=0690307575) | Jun 06, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [2d68573dcb](https://linux-hardware.org/?probe=2d68573dcb) | Jun 04, 2020 |
| ASRock        | B450 Gaming K4              | Desktop     | [24ebee7f8d](https://linux-hardware.org/?probe=24ebee7f8d) | Jun 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e10a133997](https://linux-hardware.org/?probe=e10a133997) | Jun 02, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [7b57cf3668](https://linux-hardware.org/?probe=7b57cf3668) | May 30, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [821df8e348](https://linux-hardware.org/?probe=821df8e348) | May 25, 2020 |
| ASUSTek       | H61M-A                      | Desktop     | [6118e39327](https://linux-hardware.org/?probe=6118e39327) | May 25, 2020 |
| HP            | Notebook                    | Notebook    | [024a28eb0b](https://linux-hardware.org/?probe=024a28eb0b) | May 23, 2020 |
| Dell          | Latitude E7450              | Notebook    | [f3e9ca7a40](https://linux-hardware.org/?probe=f3e9ca7a40) | May 21, 2020 |
| Lenovo        | ThinkPad E470 20H1A029SG    | Notebook    | [6afaed7f7f](https://linux-hardware.org/?probe=6afaed7f7f) | May 21, 2020 |
| Dell          | Latitude E7450              | Notebook    | [e6818ffd7d](https://linux-hardware.org/?probe=e6818ffd7d) | May 21, 2020 |
| Notebook      | W9x0LU                      | Notebook    | [c7455fcb18](https://linux-hardware.org/?probe=c7455fcb18) | May 17, 2020 |
| Lenovo        | V330-14IKB 81B0             | Notebook    | [5d81beb457](https://linux-hardware.org/?probe=5d81beb457) | May 17, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [7b1a18ebf9](https://linux-hardware.org/?probe=7b1a18ebf9) | May 09, 2020 |
| ASUSTek       | X556URK                     | Notebook    | [63c6b5a357](https://linux-hardware.org/?probe=63c6b5a357) | May 08, 2020 |
| Foxconn       | 17A0                        | Desktop     | [167cb26122](https://linux-hardware.org/?probe=167cb26122) | May 03, 2020 |
| Notebook      | N750BU                      | Notebook    | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [de6fa960ad](https://linux-hardware.org/?probe=de6fa960ad) | Apr 23, 2020 |
| I-Life Dig... | ZED_AIR_PLUS                | Convertible | [b1a911e13e](https://linux-hardware.org/?probe=b1a911e13e) | Mar 27, 2020 |
| MSI           | H61M-P31/W8                 | Desktop     | [26d8323c91](https://linux-hardware.org/?probe=26d8323c91) | Mar 25, 2020 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [baa90e0762](https://linux-hardware.org/?probe=baa90e0762) | Mar 22, 2020 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | Desktop     | [34ced022e3](https://linux-hardware.org/?probe=34ced022e3) | Feb 29, 2020 |
| HP            | Mini 210-4000               | Notebook    | [61c0ab33d8](https://linux-hardware.org/?probe=61c0ab33d8) | Feb 28, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [729f8e494d](https://linux-hardware.org/?probe=729f8e494d) | Feb 14, 2020 |
| Dell          | Inspiron 13-5378            | Notebook    | [357823f120](https://linux-hardware.org/?probe=357823f120) | Feb 03, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [e9a4da7f1c](https://linux-hardware.org/?probe=e9a4da7f1c) | Jan 31, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [4fad937155](https://linux-hardware.org/?probe=4fad937155) | Jan 10, 2020 |
| Lenovo        | ThinkPad L380 20M6S22500    | Notebook    | [15c43def70](https://linux-hardware.org/?probe=15c43def70) | Jan 09, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [9d4e0d1911](https://linux-hardware.org/?probe=9d4e0d1911) | Jan 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [2d0bca85ea](https://linux-hardware.org/?probe=2d0bca85ea) | Dec 29, 2019 |
| Gigabyte      | B85M-D3H                    | Desktop     | [753205d5df](https://linux-hardware.org/?probe=753205d5df) | Dec 27, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [d85b25cd22](https://linux-hardware.org/?probe=d85b25cd22) | Dec 24, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [30c00cb837](https://linux-hardware.org/?probe=30c00cb837) | Dec 14, 2019 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [e004d9f500](https://linux-hardware.org/?probe=e004d9f500) | Dec 14, 2019 |
| ASUSTek       | E202SA                      | Notebook    | [e052cf247b](https://linux-hardware.org/?probe=e052cf247b) | Nov 23, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [44d09b2105](https://linux-hardware.org/?probe=44d09b2105) | Nov 19, 2019 |
| HP            | ProBook 450 G4              | Notebook    | [3fc910f23c](https://linux-hardware.org/?probe=3fc910f23c) | Nov 19, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [afc9fdb4b3](https://linux-hardware.org/?probe=afc9fdb4b3) | Nov 14, 2019 |
| Acer          | Aspire E5-571G              | Notebook    | [7914862967](https://linux-hardware.org/?probe=7914862967) | Nov 14, 2019 |
| MSI           | PH67A-C43                   | Desktop     | [b472118c5a](https://linux-hardware.org/?probe=b472118c5a) | Oct 29, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [73a0de63c0](https://linux-hardware.org/?probe=73a0de63c0) | Sep 27, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [4299e1c036](https://linux-hardware.org/?probe=4299e1c036) | Sep 27, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [671ea53b31](https://linux-hardware.org/?probe=671ea53b31) | Sep 22, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [53b4bf1914](https://linux-hardware.org/?probe=53b4bf1914) | Sep 22, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [6022620aee](https://linux-hardware.org/?probe=6022620aee) | Sep 17, 2019 |
| ASUSTek       | X441UA                      | Notebook    | [d0632368ab](https://linux-hardware.org/?probe=d0632368ab) | Sep 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [ede7f2c199](https://linux-hardware.org/?probe=ede7f2c199) | Aug 30, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [e3c13fc2d8](https://linux-hardware.org/?probe=e3c13fc2d8) | Aug 20, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d0d6cd20b1](https://linux-hardware.org/?probe=d0d6cd20b1) | Jul 26, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [f9b65f1415](https://linux-hardware.org/?probe=f9b65f1415) | Jul 14, 2019 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a6f5bc1b0f](https://linux-hardware.org/?probe=a6f5bc1b0f) | Jul 13, 2019 |
| HP            | Notebook                    | Notebook    | [2ce0b2ff35](https://linux-hardware.org/?probe=2ce0b2ff35) | Jul 04, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [298e510c05](https://linux-hardware.org/?probe=298e510c05) | Jun 22, 2019 |
| Lenovo        | ThinkPad X230 2324F51       | Notebook    | [9291e8f5f3](https://linux-hardware.org/?probe=9291e8f5f3) | Jun 22, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [70fecd4e42](https://linux-hardware.org/?probe=70fecd4e42) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [ee5c9fcc02](https://linux-hardware.org/?probe=ee5c9fcc02) | Jun 04, 2019 |
| Acer          | Aspire A515-51              | Notebook    | [424ee39d57](https://linux-hardware.org/?probe=424ee39d57) | Jun 04, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [37a334e523](https://linux-hardware.org/?probe=37a334e523) | Jun 02, 2019 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [cb301afe49](https://linux-hardware.org/?probe=cb301afe49) | Jun 02, 2019 |
| Lenovo        | S10-3                       | Notebook    | [09f132c2fa](https://linux-hardware.org/?probe=09f132c2fa) | May 27, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [24c1251a9a](https://linux-hardware.org/?probe=24c1251a9a) | May 09, 2019 |
| ASUSTek       | H110M-K                     | Desktop     | [0f42a3ea73](https://linux-hardware.org/?probe=0f42a3ea73) | May 09, 2019 |
| Daffodil C... | DCL S4                      | Notebook    | [291cd2445c](https://linux-hardware.org/?probe=291cd2445c) | May 08, 2019 |
| HP            | ProBook 4540s               | Notebook    | [a8b0fbe3a8](https://linux-hardware.org/?probe=a8b0fbe3a8) | Apr 22, 2019 |
| Foxconn       | G31MV/G31MV-K FAB           | Desktop     | [83303ad448](https://linux-hardware.org/?probe=83303ad448) | Apr 07, 2019 |
| Intel         | Unknown                     | Desktop     | [6abdeb3169](https://linux-hardware.org/?probe=6abdeb3169) | Mar 10, 2019 |
| Intel         | Unknown                     | Desktop     | [d27842b77f](https://linux-hardware.org/?probe=d27842b77f) | Mar 10, 2019 |
| Intel         | Unknown                     | Desktop     | [1c484063a6](https://linux-hardware.org/?probe=1c484063a6) | Mar 09, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | Notebook    | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| MSI           | P55A-G55                    | Desktop     | [8bc6ce2174](https://linux-hardware.org/?probe=8bc6ce2174) | Dec 08, 2018 |
| MSI           | P55A-G55                    | Desktop     | [24654f4990](https://linux-hardware.org/?probe=24654f4990) | Dec 07, 2018 |
| Gigabyte      | P55-USB3                    | Desktop     | [3cf949c024](https://linux-hardware.org/?probe=3cf949c024) | Jul 21, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Bangladesh/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 47        | 10.73%  |
| Ubuntu 22.04                 | 23        | 5.25%   |
| Arch Rolling                 | 21        | 4.79%   |
| ArcoLinux Rolling            | 15        | 3.42%   |
| Arch                         | 12        | 2.74%   |
| Ubuntu 24.04                 | 11        | 2.51%   |
| Ubuntu 18.04                 | 11        | 2.51%   |
| Pop!_OS 22.04                | 11        | 2.51%   |
| Manjaro                      | 11        | 2.51%   |
| Zorin 16                     | 10        | 2.28%   |
| Debian 12                    | 9         | 2.05%   |
| Ubuntu 19.10                 | 8         | 1.83%   |
| KDE neon 20.04               | 8         | 1.83%   |
| Debian 11                    | 8         | 1.83%   |
| Fedora 40                    | 7         | 1.6%    |
| EndeavourOS Rolling          | 7         | 1.6%    |
| Fedora 38                    | 6         | 1.37%   |
| OpenMandriva 4.2             | 5         | 1.14%   |
| Fedora 33                    | 5         | 1.14%   |
| Zorin 15                     | 4         | 0.91%   |
| Ubuntu 22.10                 | 4         | 0.91%   |
| OpenMandriva 4.3             | 4         | 0.91%   |
| Manjaro 20.0.1               | 4         | 0.91%   |
| Linux Mint 20.2              | 4         | 0.91%   |
| KDE neon 22.04               | 4         | 0.91%   |
| Fedora 37                    | 4         | 0.91%   |
| Zorin 17                     | 3         | 0.68%   |
| Ubuntu 23.04                 | 3         | 0.68%   |
| Ubuntu 19.04                 | 3         | 0.68%   |
| Pop!_OS 21.10                | 3         | 0.68%   |
| Pop!_OS 21.04                | 3         | 0.68%   |
| openSUSE Tumbleweed-XXXXXXXX | 3         | 0.68%   |
| Manjaro 20.1.2               | 3         | 0.68%   |
| Linux Mint 22                | 3         | 0.68%   |
| Linux Mint 21                | 3         | 0.68%   |
| Linux Mint 20.1              | 3         | 0.68%   |
| Linux Mint 20                | 3         | 0.68%   |
| Kubuntu 23.10                | 3         | 0.68%   |
| Kubuntu 22.04                | 3         | 0.68%   |
| Kubuntu 20.04                | 3         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 116       | 28.22%  |
| Manjaro      | 33        | 8.03%   |
| Arch         | 32        | 7.79%   |
| Fedora       | 30        | 7.3%    |
| Linux Mint   | 22        | 5.35%   |
| Debian       | 20        | 4.87%   |
| Pop!_OS      | 18        | 4.38%   |
| Zorin        | 17        | 4.14%   |
| Kubuntu      | 17        | 4.14%   |
| ArcoLinux    | 15        | 3.65%   |
| OpenMandriva | 12        | 2.92%   |
| KDE neon     | 12        | 2.92%   |
| Kali         | 9         | 2.19%   |
| EndeavourOS  | 8         | 1.95%   |
| Endless      | 6         | 1.46%   |
| Parrot       | 5         | 1.22%   |
| openSUSE     | 3         | 0.73%   |
| MX           | 3         | 0.73%   |
| Garuda Linux | 3         | 0.73%   |
| Shopno       | 2         | 0.49%   |
| LMDE         | 2         | 0.49%   |
| Deepin       | 2         | 0.49%   |
| CentOS       | 2         | 0.49%   |
| BlackPanther | 2         | 0.49%   |
| Artix        | 2         | 0.49%   |
| AlmaLinux    | 2         | 0.49%   |
| Void Linux   | 1         | 0.24%   |
| Ubuntu Unity | 1         | 0.24%   |
| Ubuntu MATE  | 1         | 0.24%   |
| SteamOS      | 1         | 0.24%   |
| ROSA         | 1         | 0.24%   |
| Rocky Linux  | 1         | 0.24%   |
| Pragma       | 1         | 0.24%   |
| NixOS        | 1         | 0.24%   |
| Nitrux       | 1         | 0.24%   |
| Mabox        | 1         | 0.24%   |
| Lubuntu      | 1         | 0.24%   |
| Gentoo       | 1         | 0.24%   |
| Elementary   | 1         | 0.24%   |
| Devuan       | 1         | 0.24%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 8         | 1.66%   |
| 5.4.0-52-generic         | 6         | 1.24%   |
| 6.8.0-45-generic         | 5         | 1.04%   |
| 5.10.14-desktop-1omv4002 | 5         | 1.04%   |
| 5.13.0-28-generic        | 4         | 0.83%   |
| 6.9.3-76060903-generic   | 3         | 0.62%   |
| 6.5.0-14-generic         | 3         | 0.62%   |
| 6.2.0-34-generic         | 3         | 0.62%   |
| 6.2.0-32-generic         | 3         | 0.62%   |
| 6.2.0-26-generic         | 3         | 0.62%   |
| 5.9.16-1-MANJARO         | 3         | 0.62%   |
| 5.8.0-55-generic         | 3         | 0.62%   |
| 5.8.0-41-generic         | 3         | 0.62%   |
| 5.6.11-1-MANJARO         | 3         | 0.62%   |
| 5.4.0-53-generic         | 3         | 0.62%   |
| 5.4.0-40-generic         | 3         | 0.62%   |
| 5.4.0-29-generic         | 3         | 0.62%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.62%   |
| 5.15.0-57-generic        | 3         | 0.62%   |
| 5.15.0-56-generic        | 3         | 0.62%   |
| 5.15.0-48-generic        | 3         | 0.62%   |
| 5.11.0-37-generic        | 3         | 0.62%   |
| 5.11.0-16-generic        | 3         | 0.62%   |
| 5.10.0-33-amd64          | 3         | 0.62%   |
| 6.8.0-50-generic         | 2         | 0.41%   |
| 6.8.0-49-generic         | 2         | 0.41%   |
| 6.8.0-41-generic         | 2         | 0.41%   |
| 6.8.0-40-generic         | 2         | 0.41%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.41%   |
| 6.5.0-21-generic         | 2         | 0.41%   |
| 6.2.9-300.fc38.x86_64    | 2         | 0.41%   |
| 6.2.0-37-generic         | 2         | 0.41%   |
| 6.2.0-33-generic         | 2         | 0.41%   |
| 6.1.12-arch1-1           | 2         | 0.41%   |
| 6.1.0-17-amd64           | 2         | 0.41%   |
| 6.0.9-zen1-1-zen         | 2         | 0.41%   |
| 6.0.0-kali6-amd64        | 2         | 0.41%   |
| 5.8.16-2-MANJARO         | 2         | 0.41%   |
| 5.8.0-50-generic         | 2         | 0.41%   |
| 5.8.0-44-generic         | 2         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 40        | 8.66%   |
| 5.15.0  | 33        | 7.14%   |
| 5.11.0  | 19        | 4.11%   |
| 5.8.0   | 18        | 3.9%    |
| 6.8.0   | 17        | 3.68%   |
| 5.13.0  | 17        | 3.68%   |
| 5.19.0  | 15        | 3.25%   |
| 6.5.0   | 14        | 3.03%   |
| 6.2.0   | 14        | 3.03%   |
| 5.10.0  | 14        | 3.03%   |
| 5.3.0   | 13        | 2.81%   |
| 6.1.0   | 9         | 1.95%   |
| 5.0.0   | 7         | 1.52%   |
| 4.18.0  | 7         | 1.52%   |
| 4.15.0  | 7         | 1.52%   |
| 6.0.0   | 6         | 1.3%    |
| 6.9.3   | 5         | 1.08%   |
| 5.10.14 | 5         | 1.08%   |
| 5.9.16  | 4         | 0.87%   |
| 5.8.16  | 4         | 0.87%   |
| 5.14.0  | 4         | 0.87%   |
| 4.19.0  | 4         | 0.87%   |
| 6.6.2   | 3         | 0.65%   |
| 6.6.10  | 3         | 0.65%   |
| 6.1.8   | 3         | 0.65%   |
| 6.0.12  | 3         | 0.65%   |
| 5.6.11  | 3         | 0.65%   |
| 5.18.12 | 3         | 0.65%   |
| 5.16.7  | 3         | 0.65%   |
| 6.8.5   | 2         | 0.43%   |
| 6.7.4   | 2         | 0.43%   |
| 6.6.8   | 2         | 0.43%   |
| 6.6.1   | 2         | 0.43%   |
| 6.4.0   | 2         | 0.43%   |
| 6.2.9   | 2         | 0.43%   |
| 6.2.7   | 2         | 0.43%   |
| 6.1.12  | 2         | 0.43%   |
| 6.0.9   | 2         | 0.43%   |
| 5.7.19  | 2         | 0.43%   |
| 5.4.8   | 2         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 49        | 10.89%  |
| 5.4     | 47        | 10.44%  |
| 5.10    | 27        | 6%      |
| 6.8     | 25        | 5.56%   |
| 5.8     | 25        | 5.56%   |
| 5.11    | 24        | 5.33%   |
| 6.2     | 22        | 4.89%   |
| 5.13    | 19        | 4.22%   |
| 6.1     | 18        | 4%      |
| 6.5     | 17        | 3.78%   |
| 5.19    | 17        | 3.78%   |
| 6.6     | 16        | 3.56%   |
| 5.16    | 14        | 3.11%   |
| 6.0     | 13        | 2.89%   |
| 5.3     | 13        | 2.89%   |
| 6.9     | 10        | 2.22%   |
| 4.18    | 8         | 1.78%   |
| 5.18    | 7         | 1.56%   |
| 5.0     | 7         | 1.56%   |
| 4.15    | 7         | 1.56%   |
| 6.7     | 6         | 1.33%   |
| 5.14    | 6         | 1.33%   |
| 6.4     | 5         | 1.11%   |
| 6.10    | 5         | 1.11%   |
| 5.9     | 5         | 1.11%   |
| 5.7     | 5         | 1.11%   |
| 5.6     | 5         | 1.11%   |
| 5.17    | 5         | 1.11%   |
| 4.19    | 5         | 1.11%   |
| 6.11    | 4         | 0.89%   |
| 6.3     | 3         | 0.67%   |
| 6.12    | 3         | 0.67%   |
| 5.12    | 2         | 0.44%   |
| 5.1     | 2         | 0.44%   |
| 4.9     | 1         | 0.22%   |
| 4.4     | 1         | 0.22%   |
| 4.13    | 1         | 0.22%   |
| 3.18    | 1         | 0.22%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 384       | 97.96%  |
| i686    | 4         | 1.02%   |
| aarch64 | 4         | 1.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 194       | 47.09%  |
| KDE5            | 90        | 21.84%  |
| XFCE            | 32        | 7.77%   |
| Unknown         | 32        | 7.77%   |
| X-Cinnamon      | 22        | 5.34%   |
| KDE6            | 9         | 2.18%   |
| MATE            | 7         | 1.7%    |
| awesome         | 5         | 1.21%   |
| KDE             | 4         | 0.97%   |
| i3-with-shmlog  | 2         | 0.49%   |
| Deepin          | 2         | 0.49%   |
| bspwm           | 2         | 0.49%   |
| Unity           | 1         | 0.24%   |
| qtile           | 1         | 0.24%   |
| Pantheon        | 1         | 0.24%   |
| openbox         | 1         | 0.24%   |
| none+awesome    | 1         | 0.24%   |
| LXQt            | 1         | 0.24%   |
| LXDE            | 1         | 0.24%   |
| i3              | 1         | 0.24%   |
| GNOME Flashback | 1         | 0.24%   |
| DWM             | 1         | 0.24%   |
| Cinnamon        | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 295       | 71.26%  |
| Wayland | 94        | 22.71%  |
| Unknown | 20        | 4.83%   |
| Tty     | 5         | 1.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 184       | 44.55%  |
| SDDM    | 71        | 17.19%  |
| GDM3    | 55        | 13.32%  |
| GDM     | 48        | 11.62%  |
| LightDM | 43        | 10.41%  |
| TDM     | 9         | 2.18%   |
| Ly      | 2         | 0.48%   |
| LY-DM   | 1         | 0.24%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 334       | 83.92%  |
| Unknown | 31        | 7.79%   |
| C       | 13        | 3.27%   |
| en_GB   | 12        | 3.02%   |
| en_IN   | 2         | 0.5%    |
| ru_RU   | 1         | 0.25%   |
| en_IE   | 1         | 0.25%   |
| en_EN   | 1         | 0.25%   |
| en_CA   | 1         | 0.25%   |
| en_AG   | 1         | 0.25%   |
| Default | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 208       | 51.11%  |
| BIOS | 199       | 48.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 296       | 72.91%  |
| Btrfs   | 48        | 11.82%  |
| Overlay | 31        | 7.64%   |
| Tmpfs   | 20        | 4.93%   |
| Xfs     | 5         | 1.23%   |
| Unknown | 5         | 1.23%   |
| Zfs     | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 192       | 47.06%  |
| GPT     | 183       | 44.85%  |
| MBR     | 33        | 8.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 340       | 84.58%  |
| Yes       | 62        | 15.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 238       | 59.2%   |
| Yes       | 164       | 40.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUSTek Computer            | 78        | 19.9%   |
| Hewlett-Packard             | 68        | 17.35%  |
| MSI                         | 45        | 11.48%  |
| Lenovo                      | 43        | 10.97%  |
| Gigabyte Technology         | 36        | 9.18%   |
| Dell                        | 34        | 8.67%   |
| Acer                        | 24        | 6.12%   |
| ASRock                      | 9         | 2.3%    |
| Unknown                     | 9         | 2.3%    |
| Intel                       | 6         | 1.53%   |
| Biostar                     | 5         | 1.28%   |
| OEM                         | 4         | 1.02%   |
| Notebook                    | 4         | 1.02%   |
| Toshiba                     | 3         | 0.77%   |
| Foxconn                     | 3         | 0.77%   |
| Apple                       | 3         | 0.77%   |
| Timi                        | 2         | 0.51%   |
| Raspberry Pi Foundation     | 2         | 0.51%   |
| HUAWEI                      | 2         | 0.51%   |
| Fujitsu                     | 2         | 0.51%   |
| win element                 | 1         | 0.26%   |
| Valve                       | 1         | 0.26%   |
| SYS                         | 1         | 0.26%   |
| Samsung Electronics         | 1         | 0.26%   |
| Qbits Technologies          | 1         | 0.26%   |
| I-Life Digital Technologies | 1         | 0.26%   |
| Google                      | 1         | 0.26%   |
| FriendlyElec                | 1         | 0.26%   |
| ECS                         | 1         | 0.26%   |
| Daffodil Computers          | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 11        | 2.81%   |
| MSI MS-7C52                              | 7         | 1.79%   |
| HP ProBook 450 G4                        | 5         | 1.28%   |
| MSI Modern 15 A5M                        | 4         | 1.02%   |
| HP Notebook                              | 4         | 1.02%   |
| ASUS All Series                          | 4         | 1.02%   |
| OEM Intel H81                            | 3         | 0.77%   |
| MSI Modern 14 B10MW                      | 3         | 0.77%   |
| HP ProBook 450 G2                        | 3         | 0.77%   |
| Gigabyte B250M-HD3                       | 3         | 0.77%   |
| ASUS VivoBook_ASUSLaptop X530FN_S530FN   | 3         | 0.77%   |
| MSI MS-7E26                              | 2         | 0.51%   |
| MSI MS-7D96                              | 2         | 0.51%   |
| MSI MS-7B89                              | 2         | 0.51%   |
| MSI MS-7A15                              | 2         | 0.51%   |
| MSI MS-7788                              | 2         | 0.51%   |
| MSI MS-7668                              | 2         | 0.51%   |
| MSI Modern 14 B4MW                       | 2         | 0.51%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS0JT00 | 2         | 0.51%   |
| Lenovo IdeaPad 320-15IKB 80XL            | 2         | 0.51%   |
| Intel DG41RQ AAE54511-203                | 2         | 0.51%   |
| HP ProBook 4540s                         | 2         | 0.51%   |
| HP ProBook 440 G8 Notebook PC            | 2         | 0.51%   |
| HP EliteBook 840 G3                      | 2         | 0.51%   |
| HP 15                                    | 2         | 0.51%   |
| HP 14                                    | 2         | 0.51%   |
| Gigabyte H61M-S2PV                       | 2         | 0.51%   |
| Dell Inspiron 3442                       | 2         | 0.51%   |
| Dell Inspiron 15-3567                    | 2         | 0.51%   |
| ASUS X556UQK                             | 2         | 0.51%   |
| ASUS X510UQ                              | 2         | 0.51%   |
| ASUS VivoBook_ASUSLaptop X531FL_S531FL   | 2         | 0.51%   |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA   | 2         | 0.51%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA   | 2         | 0.51%   |
| ASUS VivoBook_ASUSLaptop X509DA          | 2         | 0.51%   |
| ASUS VivoBook 14_ASUS Laptop X407UA      | 2         | 0.51%   |
| ASUS P453UA                              | 2         | 0.51%   |
| ASRock B450 Gaming K4                    | 2         | 0.51%   |
| Acer Nitro AN515-43                      | 2         | 0.51%   |
| win element MoreFine S500+               | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS VivoBook      | 29        | 7.4%    |
| HP ProBook         | 22        | 5.61%   |
| Lenovo IdeaPad     | 18        | 4.59%   |
| Lenovo ThinkPad    | 17        | 4.34%   |
| Acer Aspire        | 17        | 4.34%   |
| Dell Inspiron      | 16        | 4.08%   |
| HP EliteBook       | 11        | 2.81%   |
| Unknown            | 11        | 2.81%   |
| Dell Latitude      | 10        | 2.55%   |
| MSI Modern         | 9         | 2.3%    |
| MSI MS-7C52        | 7         | 1.79%   |
| HP Laptop          | 6         | 1.53%   |
| ASUS TUF           | 6         | 1.53%   |
| HP Pavilion        | 4         | 1.02%   |
| HP Notebook        | 4         | 1.02%   |
| ASUS All           | 4         | 1.02%   |
| Acer Nitro         | 4         | 1.02%   |
| Toshiba Satellite  | 3         | 0.77%   |
| OEM Intel          | 3         | 0.77%   |
| HP ENVY            | 3         | 0.77%   |
| HP 15              | 3         | 0.77%   |
| Gigabyte B550M     | 3         | 0.77%   |
| Gigabyte B450M     | 3         | 0.77%   |
| Gigabyte B250M-HD3 | 3         | 0.77%   |
| Dell XPS           | 3         | 0.77%   |
| RPi Raspberry      | 2         | 0.51%   |
| MSI MS-7E26        | 2         | 0.51%   |
| MSI MS-7D96        | 2         | 0.51%   |
| MSI MS-7B89        | 2         | 0.51%   |
| MSI MS-7A15        | 2         | 0.51%   |
| MSI MS-7788        | 2         | 0.51%   |
| MSI MS-7668        | 2         | 0.51%   |
| Lenovo Legion      | 2         | 0.51%   |
| Intel DG41RQ       | 2         | 0.51%   |
| HP Victus          | 2         | 0.51%   |
| HP Compaq          | 2         | 0.51%   |
| HP 250             | 2         | 0.51%   |
| HP 14              | 2         | 0.51%   |
| Gigabyte H61M-S2PV | 2         | 0.51%   |
| Dell Vostro        | 2         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 46        | 11.73%  |
| 2019    | 44        | 11.22%  |
| 2016    | 44        | 11.22%  |
| 2021    | 35        | 8.93%   |
| 2020    | 31        | 7.91%   |
| 2017    | 31        | 7.91%   |
| 2015    | 24        | 6.12%   |
| 2013    | 22        | 5.61%   |
| 2014    | 21        | 5.36%   |
| 2012    | 21        | 5.36%   |
| 2022    | 15        | 3.83%   |
| 2011    | 15        | 3.83%   |
| 2010    | 13        | 3.32%   |
| 2023    | 12        | 3.06%   |
| 2009    | 8         | 2.04%   |
| 2008    | 5         | 1.28%   |
| Unknown | 4         | 1.02%   |
| 2024    | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 252       | 64.29%  |
| Desktop        | 129       | 32.91%  |
| Convertible    | 5         | 1.28%   |
| System on chip | 3         | 0.77%   |
| Phone          | 1         | 0.26%   |
| Tablet         | 1         | 0.26%   |
| Mini pc        | 1         | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 368       | 92.46%  |
| Enabled  | 30        | 7.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 391       | 99.74%  |
| Yes  | 1         | 0.26%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 144       | 36.09%  |
| 8.01-16.0   | 85        | 21.3%   |
| 3.01-4.0    | 80        | 20.05%  |
| 16.01-24.0  | 53        | 13.28%  |
| 32.01-64.0  | 14        | 3.51%   |
| 1.01-2.0    | 14        | 3.51%   |
| 24.01-32.0  | 3         | 0.75%   |
| 2.01-3.0    | 3         | 0.75%   |
| 64.01-256.0 | 2         | 0.5%    |
| 0.51-1.0    | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 134       | 30.32%  |
| 2.01-3.0   | 129       | 29.19%  |
| 3.01-4.0   | 76        | 17.19%  |
| 4.01-8.0   | 74        | 16.74%  |
| 0.51-1.0   | 14        | 3.17%   |
| 8.01-16.0  | 9         | 2.04%   |
| 0.01-0.5   | 5         | 1.13%   |
| 16.01-24.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 249       | 62.41%  |
| 2      | 127       | 31.83%  |
| 3      | 18        | 4.51%   |
| 5      | 2         | 0.5%    |
| 4      | 2         | 0.5%    |
| 0      | 1         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 292       | 74.11%  |
| Yes       | 102       | 25.89%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 321       | 81.27%  |
| No        | 74        | 18.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 305       | 76.25%  |
| No        | 95        | 23.75%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 254       | 63.66%  |
| No        | 145       | 36.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Bangladesh | 392       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Dhaka             | 243       | 58.55%  |
| Chittagong        | 25        | 6.02%   |
| Tongi             | 12        | 2.89%   |
| Rajshahi          | 11        | 2.65%   |
| Jessore           | 8         | 1.93%   |
| Mirpur            | 7         | 1.69%   |
| Khulna            | 7         | 1.69%   |
| Narayanganj       | 6         | 1.45%   |
| Sylhet            | 5         | 1.2%    |
| Maulavi Bāzār   | 5         | 1.2%    |
| Comilla           | 5         | 1.2%    |
| Wari              | 4         | 0.96%   |
| Pabna             | 4         | 0.96%   |
| Azimpur           | 4         | 0.96%   |
| Sherpur           | 3         | 0.72%   |
| Savar Upazila     | 3         | 0.72%   |
| Paltan            | 3         | 0.72%   |
| Mymensingh        | 3         | 0.72%   |
| Dinajpur          | 3         | 0.72%   |
| Bogra             | 3         | 0.72%   |
| Senbag            | 2         | 0.48%   |
| Rangpur City      | 2         | 0.48%   |
| Pirganj           | 2         | 0.48%   |
| Nilphamari        | 2         | 0.48%   |
| Narail            | 2         | 0.48%   |
| Lalpur            | 2         | 0.48%   |
| Jamalpur          | 2         | 0.48%   |
| Feni              | 2         | 0.48%   |
| Chuadanga         | 2         | 0.48%   |
| Uttara            | 1         | 0.24%   |
| Ukhiya            | 1         | 0.24%   |
| Tejgaon           | 1         | 0.24%   |
| Srimangal         | 1         | 0.24%   |
| Sirajganj         | 1         | 0.24%   |
| Patrun            | 1         | 0.24%   |
| Patnitala         | 1         | 0.24%   |
| Pabna Sadar       | 1         | 0.24%   |
| NДЃrДЃyanganj | 1         | 0.24%   |
| Natore            | 1         | 0.24%   |
| Narsingdi         | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 88        | 120    | 16.21%  |
| Seagate                     | 80        | 101    | 14.73%  |
| Toshiba                     | 72        | 93     | 13.26%  |
| Samsung Electronics         | 52        | 73     | 9.58%   |
| Transcend                   | 31        | 33     | 5.71%   |
| SanDisk                     | 18        | 19     | 3.31%   |
| Hitachi                     | 16        | 23     | 2.95%   |
| HGST                        | 14        | 14     | 2.58%   |
| Intel                       | 13        | 16     | 2.39%   |
| Micron Technology           | 11        | 11     | 2.03%   |
| A-DATA Technology           | 11        | 12     | 2.03%   |
| Kingston                    | 10        | 13     | 1.84%   |
| Unknown                     | 9         | 10     | 1.66%   |
| Silicon Motion              | 9         | 24     | 1.66%   |
| Teutons                     | 8         | 12     | 1.47%   |
| Phison Electronics          | 8         | 10     | 1.47%   |
| Hewlett-Packard             | 7         | 7      | 1.29%   |
| Team                        | 6         | 6      | 1.1%    |
| SK hynix                    | 5         | 7      | 0.92%   |
| Corsair                     | 5         | 7      | 0.92%   |
| MAXIO Technology (Hangzhou) | 4         | 4      | 0.74%   |
| Unknown                     | 4         | 4      | 0.74%   |
| TwinMOS                     | 3         | 3      | 0.55%   |
| Ramsta                      | 3         | 3      | 0.55%   |
| PNY                         | 3         | 3      | 0.55%   |
| Phison                      | 3         | 3      | 0.55%   |
| KIOXIA                      | 3         | 3      | 0.55%   |
| KingSpec                    | 3         | 3      | 0.55%   |
| KingFast                    | 3         | 3      | 0.55%   |
| Gigabyte Technology         | 3         | 4      | 0.55%   |
| China                       | 3         | 3      | 0.55%   |
| Apacer                      | 3         | 4      | 0.55%   |
| Realtek Semiconductor       | 2         | 2      | 0.37%   |
| Netac                       | 2         | 3      | 0.37%   |
| Kingston Technology Company | 2         | 2      | 0.37%   |
| HS-SSD-E100                 | 2         | 3      | 0.37%   |
| Crucial                     | 2         | 3      | 0.37%   |
| WDC WDS4                    | 1         | 1      | 0.18%   |
| WALTON                      | 1         | 2      | 0.18%   |
| SUNEAST                     | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                        | 23        | 4.04%   |
| Toshiba MQ04ABF100 1TB                                | 17        | 2.98%   |
| Toshiba DT01ACA100 1TB                                | 16        | 2.81%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                      | 9         | 1.58%   |
| Seagate ST1000DM010-2EP102 1TB                        | 9         | 1.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 7         | 1.23%   |
| Toshiba HDWD110 1TB                                   | 7         | 1.23%   |
| Seagate ST500DM002-1BD142 500GB                       | 7         | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 7         | 1.23%   |
| WDC WD10SPZX-60Z10T0 1TB                              | 6         | 1.05%   |
| HGST HTS541010A9E680 1TB                              | 6         | 1.05%   |
| WDC WD10JPVX-60JC3T0 1TB                              | 5         | 0.88%   |
| Toshiba MQ01ABD100 1TB                                | 5         | 0.88%   |
| Seagate ST500LT012-1DG142 500GB                       | 5         | 0.88%   |
| SanDisk NVMe SSD Drive 512GB                          | 5         | 0.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB   | 5         | 0.88%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB  | 5         | 0.88%   |
| Phison PS5013 E13 NVMe Controller 512GB               | 5         | 0.88%   |
| A-DATA SU650 240GB SSD                                | 5         | 0.88%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 4         | 0.7%    |
| WDC WD SSD 120GB                                      | 4         | 0.7%    |
| Transcend TS256GSSD230S 256GB                         | 4         | 0.7%    |
| Toshiba DT01ACA200 2TB                                | 4         | 0.7%    |
| Teutons PLATINUM SSD 128GB                            | 4         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 4         | 0.7%    |
| Seagate ST1000LM049-2GH172 1TB                        | 4         | 0.7%    |
| Kingston OM8PCP3512F-AI1 512GB                        | 4         | 0.7%    |
| Intel NVMe SSD Drive 512GB                            | 4         | 0.7%    |
| Unknown                                               | 4         | 0.7%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD                      | 3         | 0.53%   |
| WDC WD5000AAKX-001CA0 500GB                           | 3         | 0.53%   |
| WDC WD20EZRZ-00Z5HB0 2TB                              | 3         | 0.53%   |
| WDC WD10JPVX-60JC3T1 1TB                              | 3         | 0.53%   |
| WDC WD10EZEX-60WN4A0 1TB                              | 3         | 0.53%   |
| WDC WD10EZEX-22MFCA0 1TB                              | 3         | 0.53%   |
| Transcend TS240GSSD220S 240GB                         | 3         | 0.53%   |
| Transcend TS240GMTS820S 240GB SSD                     | 3         | 0.53%   |
| Transcend TS128GSSD370S 128GB                         | 3         | 0.53%   |
| Transcend TS128GMTE110S 128GB                         | 3         | 0.53%   |
| Transcend TS120GSSD220S 120GB                         | 3         | 0.53%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 80        | 100    | 32.39%  |
| Toshiba             | 65        | 85     | 26.32%  |
| WDC                 | 58        | 76     | 23.48%  |
| Hitachi             | 16        | 23     | 6.48%   |
| HGST                | 14        | 14     | 5.67%   |
| Samsung Electronics | 13        | 21     | 5.26%   |
| ASMT                | 1         | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 26        | 32     | 17.22%  |
| Transcend           | 26        | 28     | 17.22%  |
| Samsung Electronics | 11        | 14     | 7.28%   |
| A-DATA Technology   | 11        | 12     | 7.28%   |
| Teutons             | 8         | 12     | 5.3%    |
| SanDisk             | 6         | 6      | 3.97%   |
| Micron Technology   | 6         | 6      | 3.97%   |
| Team                | 5         | 5      | 3.31%   |
| Hewlett-Packard     | 5         | 5      | 3.31%   |
| TwinMOS             | 3         | 3      | 1.99%   |
| Toshiba             | 3         | 4      | 1.99%   |
| Ramsta              | 3         | 3      | 1.99%   |
| PNY                 | 3         | 3      | 1.99%   |
| KingSpec            | 3         | 3      | 1.99%   |
| Gigabyte Technology | 3         | 4      | 1.99%   |
| China               | 3         | 3      | 1.99%   |
| Apacer              | 3         | 4      | 1.99%   |
| Netac               | 2         | 3      | 1.32%   |
| HS-SSD-E100         | 2         | 2      | 1.32%   |
| Crucial             | 2         | 3      | 1.32%   |
| Corsair             | 2         | 3      | 1.32%   |
| WDC WDS4            | 1         | 1      | 0.66%   |
| WALTON              | 1         | 2      | 0.66%   |
| SUNEAST             | 1         | 1      | 0.66%   |
| SK hynix            | 1         | 1      | 0.66%   |
| Plextor             | 1         | 1      | 0.66%   |
| Patriot             | 1         | 1      | 0.66%   |
| OCZ                 | 1         | 1      | 0.66%   |
| Kingston            | 1         | 1      | 0.66%   |
| KingFast            | 1         | 1      | 0.66%   |
| Intel               | 1         | 1      | 0.66%   |
| GeIL                | 1         | 1      | 0.66%   |
| GAMER               | 1         | 1      | 0.66%   |
| Apple               | 1         | 1      | 0.66%   |
| addlink             | 1         | 1      | 0.66%   |
| Unknown             | 1         | 1      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 236       | 320    | 44.95%  |
| SSD     | 148       | 174    | 28.19%  |
| NVMe    | 122       | 175    | 23.24%  |
| Unknown | 12        | 12     | 2.29%   |
| MMC     | 7         | 8      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 303       | 502    | 69.34%  |
| NVMe | 122       | 174    | 27.92%  |
| MMC  | 7         | 8      | 1.6%    |
| SAS  | 5         | 5      | 1.14%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 196       | 266    | 53.12%  |
| 0.51-1.0   | 148       | 193    | 40.11%  |
| 1.01-2.0   | 19        | 25     | 5.15%   |
| 3.01-4.0   | 3         | 4      | 0.81%   |
| 4.01-10.0  | 2         | 2      | 0.54%   |
| 2.01-3.0   | 1         | 4      | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 124       | 29.31%  |
| 251-500        | 91        | 21.51%  |
| 501-1000       | 74        | 17.49%  |
| 1001-2000      | 35        | 8.27%   |
| 51-100         | 34        | 8.04%   |
| 21-50          | 29        | 6.86%   |
| 1-20           | 17        | 4.02%   |
| More than 3000 | 8         | 1.89%   |
| Unknown        | 7         | 1.65%   |
| 2001-3000      | 4         | 0.95%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 141       | 32.49%  |
| 21-50          | 94        | 21.66%  |
| 51-100         | 67        | 15.44%  |
| 101-250        | 66        | 15.21%  |
| 251-500        | 28        | 6.45%   |
| 501-1000       | 21        | 4.84%   |
| 1001-2000      | 7         | 1.61%   |
| Unknown        | 7         | 1.61%   |
| More than 3000 | 2         | 0.46%   |
| 2001-3000      | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                             | Computers | Drives | Percent |
|---------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                            | 4         | 6      | 7.84%   |
| Toshiba DT01ACA100 1TB                            | 3         | 4      | 5.88%   |
| Toshiba MQ01ABD050 500GB                          | 2         | 2      | 3.92%   |
| Toshiba DT01ACA200 2TB                            | 2         | 3      | 3.92%   |
| Seagate ST500DM002-1BD142 500GB                   | 2         | 2      | 3.92%   |
| HGST HTS545050A7E680 500GB                        | 2         | 2      | 3.92%   |
| HGST HTS541010A9E680 1TB                          | 2         | 2      | 3.92%   |
| WDC WD5000LPCX-22VHAT0 500GB                      | 1         | 1      | 1.96%   |
| WDC WD5000BPVT-22HXZT3 500GB                      | 1         | 1      | 1.96%   |
| WDC WD5000AAKX-001CA0 500GB                       | 1         | 1      | 1.96%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 1         | 1      | 1.96%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 1         | 2      | 1.96%   |
| WDC WD10JPVT-00MS8T0 1TB                          | 1         | 1      | 1.96%   |
| WDC WD10EZEX-60WN4A0 1TB                          | 1         | 1      | 1.96%   |
| WDC WD10EZEX-22MFCA0 1TB                          | 1         | 1      | 1.96%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 1         | 1      | 1.96%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 1         | 1      | 1.96%   |
| WDC WD10EALX-009BA0 1TB                           | 1         | 1      | 1.96%   |
| Toshiba HDWD110 1TB                               | 1         | 1      | 1.96%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD             | 1         | 1      | 1.96%   |
| Silicon Motion SM2262/SM2262EN SSD Controller 2TB | 1         | 1      | 1.96%   |
| Seagate ST9500325AS 500GB                         | 1         | 1      | 1.96%   |
| Seagate ST500LT012-9WS142 500GB                   | 1         | 1      | 1.96%   |
| Seagate ST500LT012-1DG142 500GB                   | 1         | 1      | 1.96%   |
| Seagate ST3500418AS 500GB                         | 1         | 1      | 1.96%   |
| Seagate ST320LT012-9WS14C 320GB                   | 1         | 1      | 1.96%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 1         | 1      | 1.96%   |
| Seagate ST1000LM049-2GH172 1TB                    | 1         | 1      | 1.96%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1      | 1.96%   |
| Seagate ST1000DM003-1CH162 1TB                    | 1         | 1      | 1.96%   |
| Samsung Electronics HM160HI 160GB                 | 1         | 1      | 1.96%   |
| Samsung Electronics HD161HJ 160GB                 | 1         | 2      | 1.96%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD    | 1         | 1      | 1.96%   |
| Intel SSDSCKKW240H6 240GB                         | 1         | 1      | 1.96%   |
| HS-SSD-E100 SSD 128G                              | 1         | 1      | 1.96%   |
| Hitachi HTS545025B9A300 250GB                     | 1         | 1      | 1.96%   |
| Hitachi HDT725050VLA380 500GB                     | 1         | 1      | 1.96%   |
| Hitachi HDT721032SLA360 320GB                     | 1         | 2      | 1.96%   |
| HGST HTS545050A7E380 500GB                        | 1         | 1      | 1.96%   |
| Hewlett-Packard SSD S600 240GB                    | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 12        | 16     | 24%     |
| Seagate             | 11        | 11     | 22%     |
| WDC                 | 10        | 12     | 20%     |
| HGST                | 5         | 5      | 10%     |
| Hitachi             | 3         | 4      | 6%      |
| Samsung Electronics | 2         | 3      | 4%      |
| SK hynix            | 1         | 1      | 2%      |
| Silicon Motion      | 1         | 1      | 2%      |
| Micron Technology   | 1         | 1      | 2%      |
| Intel               | 1         | 1      | 2%      |
| HS-SSD-E100         | 1         | 1      | 2%      |
| Hewlett-Packard     | 1         | 1      | 2%      |
| A-DATA Technology   | 1         | 2      | 2%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 12        | 16     | 27.91%  |
| Seagate             | 11        | 11     | 25.58%  |
| WDC                 | 10        | 12     | 23.26%  |
| HGST                | 5         | 5      | 11.63%  |
| Hitachi             | 3         | 4      | 6.98%   |
| Samsung Electronics | 2         | 3      | 4.65%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 42        | 51     | 85.71%  |
| SSD  | 6         | 7      | 12.24%  |
| NVMe | 1         | 1      | 2.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                  | Computers | Drives | Percent |
|------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB | 1         | 1      | 50%     |
| Toshiba DT01ACA100 1TB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 229       | 381    | 53.13%  |
| Works    | 151       | 247    | 35.03%  |
| Malfunc  | 49        | 59     | 11.37%  |
| Failed   | 2         | 2      | 0.46%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 289       | 60.84%  |
| AMD                            | 59        | 12.42%  |
| Samsung Electronics            | 30        | 6.32%   |
| SanDisk                        | 19        | 4%      |
| Phison Electronics             | 13        | 2.74%   |
| Silicon Motion                 | 10        | 2.11%   |
| Kingston Technology Company    | 10        | 2.11%   |
| Transcend                      | 5         | 1.05%   |
| Micron Technology              | 5         | 1.05%   |
| KIOXIA                         | 5         | 1.05%   |
| SK hynix                       | 4         | 0.84%   |
| MAXIO Technology (Hangzhou)    | 4         | 0.84%   |
| Shenzhen Longsys Electronics   | 3         | 0.63%   |
| Marvell Technology Group       | 3         | 0.63%   |
| ASMedia Technology             | 3         | 0.63%   |
| Toshiba America Info Systems   | 2         | 0.42%   |
| Realtek Semiconductor          | 2         | 0.42%   |
| Nvidia                         | 2         | 0.42%   |
| Biwin Storage Technology       | 2         | 0.42%   |
| VIA Technologies               | 1         | 0.21%   |
| Solidigm                       | 1         | 0.21%   |
| Solid State Storage Technology | 1         | 0.21%   |
| Lenovo                         | 1         | 0.21%   |
| Hosin Global Electronics       | 1         | 0.21%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 65        | 11.9%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 39        | 7.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 21        | 3.85%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 18        | 3.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 15        | 2.75%   |
| AMD 400 Series Chipset SATA Controller                                                  | 15        | 2.75%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 13        | 2.38%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 13        | 2.38%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 13        | 2.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 12        | 2.2%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 2.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 11        | 2.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 9         | 1.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 1.65%   |
| AMD 500 Series Chipset SATA Controller                                                  | 9         | 1.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 8         | 1.47%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 8         | 1.47%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                     | 8         | 1.47%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 8         | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7         | 1.28%   |
| Intel SSD 660P Series                                                                   | 7         | 1.28%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 6         | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 1.1%    |
| Phison E12 NVMe Controller                                                              | 5         | 0.92%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 5         | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 5         | 0.92%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5         | 0.92%   |
| Transcend NVMe PCIe SSD 110S/112S/120S/MTE300S/MTE400S/MTE652T2 (DRAM-less)             | 4         | 0.73%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                   | 4         | 0.73%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 4         | 0.73%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                           | 4         | 0.73%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 4         | 0.73%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 4         | 0.73%   |
| Intel SATA Controller [RAID Mode]                                                       | 4         | 0.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 4         | 0.73%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 4         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 282       | 58.02%  |
| NVMe | 123       | 25.31%  |
| RAID | 45        | 9.26%   |
| IDE  | 36        | 7.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 315       | 80.36%  |
| AMD    | 73        | 18.62%  |
| ARM    | 4         | 1.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz           | 15        | 3.82%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 13        | 3.31%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 12        | 3.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 9         | 2.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 9         | 2.29%   |
| Intel Core i3-7100U CPU @ 2.40GHz           | 8         | 2.04%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 6         | 1.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 1.27%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 5         | 1.27%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 1.27%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 1.27%   |
| Intel Core i3-8130U CPU @ 2.20GHz           | 5         | 1.27%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 5         | 1.27%   |
| AMD Ryzen 5 3600 6-Core Processor           | 5         | 1.27%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 4         | 1.02%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 1.02%   |
| Intel Core i5-5300U CPU @ 2.30GHz           | 4         | 1.02%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 4         | 1.02%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.02%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4         | 1.02%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.02%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 4         | 1.02%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 1.02%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 4         | 1.02%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz          | 4         | 1.02%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4         | 1.02%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 4         | 1.02%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 3         | 0.76%   |
| Intel Pentium CPU G630 @ 2.70GHz            | 3         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.76%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 3         | 0.76%   |
| Intel Core i5-7500 CPU @ 3.40GHz            | 3         | 0.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz          | 3         | 0.76%   |
| Intel Core i3-7130U CPU @ 2.70GHz           | 3         | 0.76%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 3         | 0.76%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 3         | 0.76%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 3         | 0.76%   |
| Intel Core i3-4160 CPU @ 3.60GHz            | 3         | 0.76%   |
| Intel Core 2 Duo CPU T6570 @ 2.10GHz        | 3         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 127       | 32.4%   |
| Intel Core i3           | 72        | 18.37%  |
| Other                   | 39        | 9.95%   |
| AMD Ryzen 5             | 35        | 8.93%   |
| Intel Core i7           | 29        | 7.4%    |
| Intel Pentium           | 14        | 3.57%   |
| AMD Ryzen 7             | 13        | 3.32%   |
| Intel Core 2 Duo        | 11        | 2.81%   |
| Intel Celeron           | 9         | 2.3%    |
| AMD Ryzen 3             | 8         | 2.04%   |
| Intel Pentium Dual-Core | 6         | 1.53%   |
| Intel Xeon              | 4         | 1.02%   |
| Intel Pentium Gold      | 3         | 0.77%   |
| AMD Ryzen 9             | 3         | 0.77%   |
| Intel Core 2 Quad       | 2         | 0.51%   |
| Intel Atom              | 2         | 0.51%   |
| AMD A8                  | 2         | 0.51%   |
| AMD A6                  | 2         | 0.51%   |
| AMD A10                 | 2         | 0.51%   |
| Intel Celeron Dual-Core | 1         | 0.26%   |
| ARM AArch64             | 1         | 0.26%   |
| AMD Ryzen 7 PRO         | 1         | 0.26%   |
| AMD Ryzen 5 PRO         | 1         | 0.26%   |
| AMD FX                  | 1         | 0.26%   |
| AMD E2                  | 1         | 0.26%   |
| AMD E                   | 1         | 0.26%   |
| AMD Athlon              | 1         | 0.26%   |
| AMD A4                  | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 192       | 48.85%  |
| 4       | 125       | 31.81%  |
| 6       | 39        | 9.92%   |
| 8       | 18        | 4.58%   |
| 10      | 7         | 1.78%   |
| 12      | 5         | 1.27%   |
| 24      | 2         | 0.51%   |
| 16      | 2         | 0.51%   |
| 1       | 2         | 0.51%   |
| Unknown | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 391       | 99.74%  |
| Unknown | 1         | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 297       | 75.57%  |
| 1       | 95        | 24.17%  |
| Unknown | 1         | 0.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 391       | 99.74%  |
| Unknown        | 1         | 0.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 175       | 42.17%  |
| 0x806e9    | 25        | 6.02%   |
| 0x806ea    | 16        | 3.86%   |
| 0x306a9    | 15        | 3.61%   |
| 0x206a7    | 13        | 3.13%   |
| 0x406e3    | 12        | 2.89%   |
| 0x806ec    | 10        | 2.41%   |
| 0x40651    | 10        | 2.41%   |
| 0x306d4    | 10        | 2.41%   |
| 0x1067a    | 10        | 2.41%   |
| 0x806c1    | 9         | 2.17%   |
| 0x306c3    | 9         | 2.17%   |
| 0x08108109 | 9         | 2.17%   |
| 0x806eb    | 7         | 1.69%   |
| 0x906e9    | 6         | 1.45%   |
| 0x08701021 | 6         | 1.45%   |
| 0x706e5    | 5         | 1.2%    |
| 0x906ea    | 4         | 0.96%   |
| 0x406c4    | 4         | 0.96%   |
| 0x506e3    | 3         | 0.72%   |
| 0x20655    | 3         | 0.72%   |
| 0x106e5    | 3         | 0.72%   |
| 0x10676    | 3         | 0.72%   |
| 0x0a50000c | 3         | 0.72%   |
| 0x08108102 | 3         | 0.72%   |
| 0xa0652    | 2         | 0.48%   |
| 0x906eb    | 2         | 0.48%   |
| 0x90672    | 2         | 0.48%   |
| 0x6fb      | 2         | 0.48%   |
| 0x20652    | 2         | 0.48%   |
| 0x0a601206 | 2         | 0.48%   |
| 0x08608103 | 2         | 0.48%   |
| 0x08600104 | 2         | 0.48%   |
| 0x0810100b | 2         | 0.48%   |
| 0xb06f2    | 1         | 0.24%   |
| 0xa0653    | 1         | 0.24%   |
| 0x906a4    | 1         | 0.24%   |
| 0x906a3    | 1         | 0.24%   |
| 0x806d1    | 1         | 0.24%   |
| 0x706a8    | 1         | 0.24%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 111       | 28.17%  |
| Haswell          | 30        | 7.61%   |
| Skylake          | 28        | 7.11%   |
| Unknown          | 28        | 7.11%   |
| IvyBridge        | 22        | 5.58%   |
| SandyBridge      | 19        | 4.82%   |
| Penryn           | 17        | 4.31%   |
| Zen 3            | 16        | 4.06%   |
| TigerLake        | 16        | 4.06%   |
| Zen+             | 15        | 3.81%   |
| Broadwell        | 15        | 3.81%   |
| Zen 2            | 14        | 3.55%   |
| Alderlake Hybrid | 10        | 2.54%   |
| IceLake          | 8         | 2.03%   |
| CometLake        | 8         | 2.03%   |
| Silvermont       | 7         | 1.78%   |
| Westmere         | 5         | 1.27%   |
| Core             | 5         | 1.27%   |
| Zen              | 3         | 0.76%   |
| Piledriver       | 3         | 0.76%   |
| Nehalem          | 3         | 0.76%   |
| Excavator        | 3         | 0.76%   |
| Bonnell          | 2         | 0.51%   |
| Steamroller      | 1         | 0.25%   |
| Puma             | 1         | 0.25%   |
| K10 Llano        | 1         | 0.25%   |
| Goldmont plus    | 1         | 0.25%   |
| Goldmont         | 1         | 0.25%   |
| Bobcat           | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 291       | 62.72%  |
| Nvidia | 93        | 20.04%  |
| AMD    | 80        | 17.24%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 620                                                                    | 36        | 7.64%   |
| Intel UHD Graphics 620                                                                   | 23        | 4.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 4.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 19        | 4.03%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 3.61%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 2.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.97%   |
| Intel HD Graphics 5500                                                                   | 13        | 2.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 2.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 2.55%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 2.34%   |
| Intel HD Graphics 630                                                                    | 10        | 2.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 2.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 9         | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.7%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 8         | 1.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1.49%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 7         | 1.49%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 1.27%   |
| AMD Lucienne                                                                             | 6         | 1.27%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 1.06%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.06%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 5         | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 1.06%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 5         | 1.06%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 5         | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.85%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.85%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 0.85%   |
| Intel HD Graphics 530                                                                    | 4         | 0.85%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 4         | 0.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.85%   |
| AMD Raphael                                                                              | 4         | 0.85%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 3         | 0.64%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.64%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.64%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.64%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.64%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 227       | 57.47%  |
| 1 x AMD        | 57        | 14.43%  |
| Intel + Nvidia | 52        | 13.16%  |
| 1 x Nvidia     | 32        | 8.1%    |
| AMD + Nvidia   | 9         | 2.28%   |
| Intel + AMD    | 8         | 2.03%   |
| 2 x AMD        | 6         | 1.52%   |
| Other          | 4         | 1.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 325       | 80.05%  |
| Proprietary | 57        | 14.04%  |
| Unknown     | 24        | 5.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 300       | 74.81%  |
| 1.01-2.0   | 40        | 9.98%   |
| 3.01-4.0   | 23        | 5.74%   |
| 0.01-0.5   | 19        | 4.74%   |
| 0.51-1.0   | 9         | 2.24%   |
| 7.01-8.0   | 7         | 1.75%   |
| 5.01-6.0   | 3         | 0.75%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 71        | 17.79%  |
| AU Optronics            | 60        | 15.04%  |
| Chimei Innolux          | 51        | 12.78%  |
| LG Display              | 39        | 9.77%   |
| Samsung Electronics     | 34        | 8.52%   |
| Hewlett-Packard         | 28        | 7.02%   |
| Dell                    | 24        | 6.02%   |
| Goldstar                | 22        | 5.51%   |
| PANDA                   | 6         | 1.5%    |
| MSI                     | 6         | 1.5%    |
| ASUSTek Computer        | 6         | 1.5%    |
| ViewSonic               | 5         | 1.25%   |
| Chi Mei Optoelectronics | 4         | 1%      |
| Philips                 | 3         | 0.75%   |
| Lenovo                  | 3         | 0.75%   |
| Apple                   | 3         | 0.75%   |
| Ancor Communications    | 3         | 0.75%   |
| Sony                    | 2         | 0.5%    |
| LG Electronics          | 2         | 0.5%    |
| ___                     | 1         | 0.25%   |
| Westinghouse            | 1         | 0.25%   |
| Valve                   | 1         | 0.25%   |
| UTV                     | 1         | 0.25%   |
| Unknown                 | 1         | 0.25%   |
| Sharp                   | 1         | 0.25%   |
| SAC                     | 1         | 0.25%   |
| QXS                     | 1         | 0.25%   |
| Mi                      | 1         | 0.25%   |
| LLL                     | 1         | 0.25%   |
| JXC                     | 1         | 0.25%   |
| InfoVision              | 1         | 0.25%   |
| IDS                     | 1         | 0.25%   |
| HYU                     | 1         | 0.25%   |
| HUYINIUDA               | 1         | 0.25%   |
| HUAWEI                  | 1         | 0.25%   |
| HKC                     | 1         | 0.25%   |
| Gigabyte Technology     | 1         | 0.25%   |
| FSR                     | 1         | 0.25%   |
| DHI                     | 1         | 0.25%   |
| Denver                  | 1         | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch              | 12        | 2.94%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch    | 12        | 2.94%   |
| Hewlett-Packard 22fw HPN3541 1920x1080 476x268mm 21.5-inch          | 7         | 1.72%   |
| Hewlett-Packard V194 HWP3346 1366x768 410x230mm 18.5-inch           | 6         | 1.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch      | 6         | 1.47%   |
| Samsung Electronics S19F350 SAM0D46 1366x768 410x230mm 18.5-inch    | 5         | 1.23%   |
| Dell SE2219H DELF10F 1920x1080 476x268mm 21.5-inch                  | 4         | 0.98%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                   | 4         | 0.98%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch               | 4         | 0.98%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                | 4         | 0.98%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch      | 4         | 0.98%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch        | 3         | 0.74%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch         | 3         | 0.74%   |
| Dell S2240L DELD054 1920x1080 476x267mm 21.5-inch                   | 3         | 0.74%   |
| Dell S2218H DELD0B8 1920x1080 476x268mm 21.5-inch                   | 3         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch     | 3         | 0.74%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch               | 3         | 0.74%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                | 3         | 0.74%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                | 3         | 0.74%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                | 3         | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch      | 3         | 0.74%   |
| Samsung Electronics SyncMaster SAM0472 1440x900 367x229mm 17.0-inch | 2         | 0.49%   |
| Samsung Electronics S22R35x SAM103A 1920x1080 476x268mm 21.5-inch   | 2         | 0.49%   |
| Samsung Electronics LCD Monitor S19F350 1366x768                    | 2         | 0.49%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch        | 2         | 0.49%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch        | 2         | 0.49%   |
| LG Display LCD Monitor LGD0504 1366x768 340x190mm 15.3-inch         | 2         | 0.49%   |
| LG Display LCD Monitor LGD04C0 1366x768 309x174mm 14.0-inch         | 2         | 0.49%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch        | 2         | 0.49%   |
| LG Display LCD Monitor LGD0466 1366x768 309x174mm 14.0-inch         | 2         | 0.49%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch         | 2         | 0.49%   |
| Lenovo R27fc-30 LEN67B6 1920x1080 598x336mm 27.0-inch               | 2         | 0.49%   |
| Hewlett-Packard v185w HWP2820 1366x768 410x230mm 18.5-inch          | 2         | 0.49%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch           | 2         | 0.49%   |
| Hewlett-Packard 22f HPN3542 1920x1080 476x267mm 21.5-inch           | 2         | 0.49%   |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch             | 2         | 0.49%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch           | 2         | 0.49%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                    | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch    | 2         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch     | 2         | 0.49%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 179       | 46.37%  |
| 1366x768 (WXGA)   | 143       | 37.05%  |
| 3840x2160 (4K)    | 18        | 4.66%   |
| 1440x900 (WXGA+)  | 8         | 2.07%   |
| 1600x900 (HD+)    | 7         | 1.81%   |
| 1920x1200 (WUXGA) | 5         | 1.3%    |
| 2560x1600         | 4         | 1.04%   |
| 1280x1024 (SXGA)  | 4         | 1.04%   |
| 1280x800 (WXGA)   | 3         | 0.78%   |
| 2560x1440 (QHD)   | 2         | 0.52%   |
| 1024x600          | 2         | 0.52%   |
| Unknown           | 2         | 0.52%   |
| 800x1280          | 1         | 0.26%   |
| 3840x2400         | 1         | 0.26%   |
| 3440x1440         | 1         | 0.26%   |
| 3360x1080         | 1         | 0.26%   |
| 2736x1824         | 1         | 0.26%   |
| 2726x768          | 1         | 0.26%   |
| 2240x1400         | 1         | 0.26%   |
| 1360x768          | 1         | 0.26%   |
| 1024x768 (XGA)    | 1         | 0.26%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 124       | 30.92%  |
| 13      | 58        | 14.46%  |
| 14      | 48        | 11.97%  |
| 21      | 42        | 10.47%  |
| 18      | 31        | 7.73%   |
| 23      | 16        | 3.99%   |
| 31      | 12        | 2.99%   |
| 16      | 9         | 2.24%   |
| Unknown | 9         | 2.24%   |
| 27      | 8         | 2%      |
| 19      | 8         | 2%      |
| 24      | 7         | 1.75%   |
| 12      | 7         | 1.75%   |
| 17      | 6         | 1.5%    |
| 11      | 3         | 0.75%   |
| 72      | 2         | 0.5%    |
| 32      | 2         | 0.5%    |
| 10      | 2         | 0.5%    |
| 84      | 1         | 0.25%   |
| 49      | 1         | 0.25%   |
| 39      | 1         | 0.25%   |
| 34      | 1         | 0.25%   |
| 26      | 1         | 0.25%   |
| 20      | 1         | 0.25%   |
| 7       | 1         | 0.25%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 220       | 55.56%  |
| 401-500     | 85        | 21.46%  |
| 201-300     | 28        | 7.07%   |
| 501-600     | 24        | 6.06%   |
| 601-700     | 12        | 3.03%   |
| 351-400     | 9         | 2.27%   |
| Unknown     | 9         | 2.27%   |
| 701-800     | 3         | 0.76%   |
| 1501-2000   | 3         | 0.76%   |
| 801-900     | 1         | 0.25%   |
| 1001-1500   | 1         | 0.25%   |
| 1-100       | 1         | 0.25%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 327       | 89.34%  |
| 16/10   | 21        | 5.74%   |
| Unknown | 8         | 2.19%   |
| 4/3     | 4         | 1.09%   |
| 5/4     | 2         | 0.55%   |
| 32/9    | 1         | 0.27%   |
| 3/2     | 1         | 0.27%   |
| 21/9    | 1         | 0.27%   |
| 0.67    | 1         | 0.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 124       | 31%     |
| 81-90          | 93        | 23.25%  |
| 201-250        | 45        | 11.25%  |
| 141-150        | 32        | 8%      |
| 151-200        | 25        | 6.25%   |
| 351-500        | 15        | 3.75%   |
| 71-80          | 11        | 2.75%   |
| Unknown        | 9         | 2.25%   |
| 301-350        | 8         | 2%      |
| 111-120        | 8         | 2%      |
| 61-70          | 7         | 1.75%   |
| 131-140        | 5         | 1.25%   |
| 251-300        | 4         | 1%      |
| More than 1000 | 3         | 0.75%   |
| 51-60          | 3         | 0.75%   |
| 41-50          | 2         | 0.5%    |
| 501-1000       | 2         | 0.5%    |
| 91-100         | 2         | 0.5%    |
| 1-40           | 1         | 0.25%   |
| 121-130        | 1         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 150       | 37.97%  |
| 121-160       | 122       | 30.89%  |
| 51-100        | 94        | 23.8%   |
| 161-240       | 14        | 3.54%   |
| Unknown       | 9         | 2.28%   |
| More than 240 | 4         | 1.01%   |
| 1-50          | 2         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 339       | 84.75%  |
| 2     | 40        | 10%     |
| 0     | 19        | 4.75%   |
| 3     | 2         | 0.5%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 279       | 48.52%  |
| Intel                             | 138       | 24%     |
| Qualcomm Atheros                  | 66        | 11.48%  |
| MediaTek                          | 19        | 3.3%    |
| Ralink Technology                 | 17        | 2.96%   |
| Xiaomi                            | 10        | 1.74%   |
| TP-Link                           | 9         | 1.57%   |
| Broadcom                          | 9         | 1.57%   |
| Ralink                            | 5         | 0.87%   |
| Samsung Electronics               | 4         | 0.7%    |
| OPPO Electronics                  | 3         | 0.52%   |
| D-Link                            | 3         | 0.52%   |
| Qualcomm                          | 2         | 0.35%   |
| HMD Global                        | 2         | 0.35%   |
| ASIX Electronics                  | 2         | 0.35%   |
| Sundance Technology Inc / IC Plus | 1         | 0.17%   |
| NetGear                           | 1         | 0.17%   |
| ICS Advent                        | 1         | 0.17%   |
| Huawei Technologies               | 1         | 0.17%   |
| Dell                              | 1         | 0.17%   |
| Arduino SA                        | 1         | 0.17%   |
| AboCom Systems                    | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 190       | 28.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 46        | 6.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 27        | 4.09%   |
| Intel Wireless 8265 / 8275                                             | 22        | 3.33%   |
| Ralink MT7601U Wireless Adapter                                        | 15        | 2.27%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 14        | 2.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 14        | 2.12%   |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 13        | 1.97%   |
| Intel Wi-Fi 6 AX201                                                    | 13        | 1.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 10        | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 10        | 1.52%   |
| Intel Wireless 3165                                                    | 10        | 1.52%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 9         | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 8         | 1.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 7         | 1.06%   |
| Intel Wireless 8260                                                    | 7         | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                                  | 7         | 1.06%   |
| Intel Wi-Fi 6 AX200                                                    | 6         | 0.91%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 0.76%   |
| Intel Wireless 7265                                                    | 5         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 5         | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 0.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4         | 0.61%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 4         | 0.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 0.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 4         | 0.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                | 4         | 0.61%   |
| Intel Wireless 7260                                                    | 4         | 0.61%   |
| Intel Wireless 3160                                                    | 4         | 0.61%   |
| Intel Raptor Lake-S PCH CNVi WiFi                                      | 4         | 0.61%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 0.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 4         | 0.61%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                                      | 3         | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 125       | 39.68%  |
| Realtek Semiconductor | 67        | 21.27%  |
| Qualcomm Atheros      | 62        | 19.68%  |
| Ralink Technology     | 17        | 5.4%    |
| MediaTek              | 16        | 5.08%   |
| TP-Link               | 8         | 2.54%   |
| Broadcom              | 6         | 1.9%    |
| Ralink                | 5         | 1.59%   |
| Xiaomi                | 3         | 0.95%   |
| D-Link                | 3         | 0.95%   |
| NetGear               | 1         | 0.32%   |
| Dell                  | 1         | 0.32%   |
| AboCom Systems        | 1         | 0.32%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 27        | 8.57%   |
| Intel Wireless 8265 / 8275                                     | 22        | 6.98%   |
| Ralink MT7601U Wireless Adapter                                | 15        | 4.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 14        | 4.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 14        | 4.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 4.13%   |
| Intel Wi-Fi 6 AX201                                            | 13        | 4.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 3.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 3.17%   |
| Intel Wireless 3165                                            | 10        | 3.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 9         | 2.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 8         | 2.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 7         | 2.22%   |
| Intel Wireless 8260                                            | 7         | 2.22%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 1.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.59%   |
| Intel Wireless 7265                                            | 5         | 1.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 5         | 1.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 1.59%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 4         | 1.27%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 4         | 1.27%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 1.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.27%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 1.27%   |
| Intel Wireless 7260                                            | 4         | 1.27%   |
| Intel Wireless 3160                                            | 4         | 1.27%   |
| Intel Raptor Lake-S PCH CNVi WiFi                              | 4         | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 1.27%   |
| Xiaomi MediaTek MT7601U [MI WiFi]                              | 3         | 0.95%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 0.95%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 3         | 0.95%   |
| Realtek RTL8188GU 802.11n WLAN Adapter (After Modeswitch)      | 3         | 0.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 3         | 0.95%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 0.95%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.63%   |
| Realtek 802.11ac NIC                                           | 2         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 257       | 76.04%  |
| Intel                             | 44        | 13.02%  |
| Qualcomm Atheros                  | 8         | 2.37%   |
| Xiaomi                            | 7         | 2.07%   |
| Broadcom                          | 4         | 1.18%   |
| OPPO Electronics                  | 3         | 0.89%   |
| MediaTek                          | 3         | 0.89%   |
| Samsung Electronics               | 2         | 0.59%   |
| Qualcomm                          | 2         | 0.59%   |
| HMD Global                        | 2         | 0.59%   |
| ASIX Electronics                  | 2         | 0.59%   |
| TP-Link                           | 1         | 0.3%    |
| Sundance Technology Inc / IC Plus | 1         | 0.3%    |
| ICS Advent                        | 1         | 0.3%    |
| Huawei Technologies               | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 190       | 55.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 46        | 13.45%  |
| Realtek RTL8125 2.5GbE Controller                                      | 13        | 3.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 8         | 2.34%   |
| Intel Ethernet Connection (4) I219-LM                                  | 7         | 2.05%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 1.46%   |
| Intel Ethernet Connection (2) I219-V                                   | 5         | 1.46%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 4         | 1.17%   |
| Intel Ethernet Connection I219-LM                                      | 4         | 1.17%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 1.17%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.88%   |
| MediaTek Infinix SMART 5                                               | 3         | 0.88%   |
| Intel Ethernet Controller I225-V                                       | 3         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                                   | 3         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 2         | 0.58%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.58%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.58%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 2         | 0.58%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.58%   |
| Qualcomm Airtel 4G                                                     | 2         | 0.58%   |
| OPPO OnePlus Nord 4                                                    | 2         | 0.58%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.58%   |
| HMD Global Nokia6.2                                                    | 2         | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.58%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.29%   |
| Sundance Inc / IC Plus IP1000 Family Gigabit Ethernet                  | 1         | 0.29%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.29%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 0.29%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 1         | 0.29%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.29%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.29%   |
| OPPO CPH2477                                                           | 1         | 0.29%   |
| Intel Ethernet Connection I217-LM                                      | 1         | 0.29%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.29%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.29%   |
| Intel Ethernet Connection (6) I219-LM                                  | 1         | 0.29%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.29%   |
| Intel Ethernet Connection (10) I219-V                                  | 1         | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 320       | 51.04%  |
| WiFi     | 304       | 48.48%  |
| Modem    | 3         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 243       | 61.52%  |
| Ethernet | 152       | 38.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 196       | 50%     |
| 2     | 189       | 48.21%  |
| 0     | 5         | 1.28%   |
| 3     | 2         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 384       | 97.96%  |
| Yes  | 8         | 2.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 106       | 41.25%  |
| IMC Networks                    | 37        | 14.4%   |
| Realtek Semiconductor           | 29        | 11.28%  |
| Cambridge Silicon Radio         | 20        | 7.78%   |
| Qualcomm Atheros Communications | 18        | 7%      |
| Lite-On Technology              | 14        | 5.45%   |
| Broadcom                        | 7         | 2.72%   |
| MediaTek                        | 6         | 2.33%   |
| Foxconn / Hon Hai               | 6         | 2.33%   |
| Ralink                          | 4         | 1.56%   |
| Realtek                         | 2         | 0.78%   |
| Apple                           | 2         | 0.78%   |
| Toshiba                         | 1         | 0.39%   |
| SINO WEALTH                     | 1         | 0.39%   |
| Hewlett-Packard                 | 1         | 0.39%   |
| Foxconn International           | 1         | 0.39%   |
| Dell                            | 1         | 0.39%   |
| Unknown                         | 1         | 0.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 51        | 19.84%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 7.78%   |
| Realtek Bluetooth Radio                             | 19        | 7.39%   |
| Intel AX201 Bluetooth                               | 17        | 6.61%   |
| IMC Networks Bluetooth Device                       | 15        | 5.84%   |
| IMC Networks Bluetooth Radio                        | 14        | 5.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 5.06%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 4.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 4.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 3.11%   |
| IMC Networks Wireless_Device                        | 7         | 2.72%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2.33%   |
| MediaTek Wireless_Device                            | 6         | 2.33%   |
| Intel AX200 Bluetooth                               | 6         | 2.33%   |
| Lite-On Bluetooth Device                            | 5         | 1.95%   |
| Intel AX211 Bluetooth                               | 5         | 1.95%   |
| Ralink RT3290 Bluetooth                             | 4         | 1.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 2         | 0.78%   |
| Realtek Bluetooth Radio                             | 2         | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.78%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.78%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.78%   |
| Apple Bluetooth Host Controller                     | 2         | 0.78%   |
| Toshiba Bluetooth Radio                             | 1         | 0.39%   |
| SINO WEALTH Bluetooth Keyboard                      | 1         | 0.39%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.39%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.39%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.39%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.39%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.39%   |
| Intel AX210 Bluetooth                               | 1         | 0.39%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.39%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.39%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 312       | 67.1%   |
| AMD                    | 82        | 17.63%  |
| Nvidia                 | 51        | 10.97%  |
| Generalplus Technology | 7         | 1.51%   |
| C-Media Electronics    | 3         | 0.65%   |
| Logitech               | 2         | 0.43%   |
| JMTek                  | 2         | 0.43%   |
| Razer USA              | 1         | 0.22%   |
| KTMicro                | 1         | 0.22%   |
| iCreate Technologies   | 1         | 0.22%   |
| Google                 | 1         | 0.22%   |
| Creative Labs          | 1         | 0.22%   |
| ASUSTek Computer       | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 79        | 13.96%  |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 47        | 8.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 22        | 3.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 21        | 3.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 3.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 3.36%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 2.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 2.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 2.65%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 2.65%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 15        | 2.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 2.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.3%    |
| Intel 8 Series HD Audio Controller                                                                | 13        | 2.3%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 12        | 2.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 11        | 1.94%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 1.77%   |
| Intel 200 Series PCH HD Audio                                                                     | 10        | 1.77%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.41%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 1.41%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.24%   |
| Generalplus Technology USB Audio Device                                                           | 7         | 1.24%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 7         | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 1.06%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.06%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.88%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 0.88%   |
| AMD FCH Azalia Controller                                                                         | 5         | 0.88%   |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.71%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.71%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 4         | 0.71%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 4         | 0.71%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 3         | 0.53%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.53%   |
| Intel USB PnP Sound Device                                                                        | 3         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 59        | 23.05%  |
| SK hynix            | 46        | 17.97%  |
| Micron Technology   | 30        | 11.72%  |
| G.Skill             | 19        | 7.42%   |
| A-DATA Technology   | 13        | 5.08%   |
| Unknown             | 12        | 4.69%   |
| Kingston            | 12        | 4.69%   |
| Corsair             | 12        | 4.69%   |
| Transcend           | 9         | 3.52%   |
| Team                | 7         | 2.73%   |
| Ramaxel Technology  | 6         | 2.34%   |
| Crucial             | 4         | 1.56%   |
| Unknown             | 4         | 1.56%   |
| Nanya Technology    | 3         | 1.17%   |
| SemsoTai            | 2         | 0.78%   |
| Elpida              | 2         | 0.78%   |
| Unknown (C509)      | 1         | 0.39%   |
| Unknown (ABCD)      | 1         | 0.39%   |
| Unknown (768A)      | 1         | 0.39%   |
| Unknown (6B86)      | 1         | 0.39%   |
| TwinMOS             | 1         | 0.39%   |
| Toshiba             | 1         | 0.39%   |
| Silicon Power       | 1         | 0.39%   |
| Ramos Technology    | 1         | 0.39%   |
| Qumo                | 1         | 0.39%   |
| PNY                 | 1         | 0.39%   |
| Patriot             | 1         | 0.39%   |
| Lexar               | 1         | 0.39%   |
| Hewlett-Packard     | 1         | 0.39%   |
| GeIL                | 1         | 0.39%   |
| ASint Technology    | 1         | 0.39%   |
| Apacer              | 1         | 0.39%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Corsair RAM CMK8GX4M1E3200C16 8GB DIMM DDR4 3200MT/s      | 7         | 2.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s    | 6         | 2.26%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 5         | 1.88%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s     | 5         | 1.88%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 4         | 1.5%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s    | 4         | 1.5%    |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s  | 4         | 1.5%    |
| Unknown                                                   | 4         | 1.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 3         | 1.13%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 1.13%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 3         | 1.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.13%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 3         | 1.13%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s     | 3         | 1.13%   |
| Transcend RAM JM3200HSG-8G 8GB SODIMM DDR4 3200MT/s       | 2         | 0.75%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s        | 2         | 0.75%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s     | 2         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 2         | 0.75%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 0.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 2         | 0.75%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s    | 2         | 0.75%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s     | 2         | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s     | 2         | 0.75%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s     | 2         | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 0.75%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s      | 2         | 0.75%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s      | 2         | 0.75%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 2         | 0.75%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s     | 2         | 0.75%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 2         | 0.75%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s     | 2         | 0.75%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s    | 2         | 0.75%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s    | 2         | 0.75%   |
| Kingston RAM KHX2400C15D4/4G 4GB DIMM DDR4 3151MT/s       | 2         | 0.75%   |
| G.Skill RAM F4-3600C18-16GTZN 16GB DIMM DDR4 3666MT/s     | 2         | 0.75%   |
| G.Skill RAM F4-2133C15-4GRS 4GB SODIMM DDR4 2134MT/s      | 2         | 0.75%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 3066MT/s      | 2         | 0.75%   |
| A-DATA RAM Module 8GB SODIMM DDR4 2400MT/s                | 2         | 0.75%   |
| Unknown RAM Module 8GB DIMM DDR4 3200MT/s                 | 1         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 130       | 65.66%  |
| DDR3    | 44        | 22.22%  |
| LPDDR4  | 6         | 3.03%   |
| DDR5    | 6         | 3.03%   |
| LPDDR3  | 5         | 2.53%   |
| SDRAM   | 2         | 1.01%   |
| DDR2    | 2         | 1.01%   |
| Unknown | 2         | 1.01%   |
| LPDDR5  | 1         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 133       | 67.86%  |
| DIMM         | 52        | 26.53%  |
| Row Of Chips | 10        | 5.1%    |
| RIMM         | 1         | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 93        | 41.7%   |
| 4096  | 71        | 31.84%  |
| 16384 | 35        | 15.7%   |
| 2048  | 15        | 6.73%   |
| 32768 | 8         | 3.59%   |
| 1024  | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 55        | 25%     |
| 2667  | 47        | 21.36%  |
| 1600  | 30        | 13.64%  |
| 2400  | 19        | 8.64%   |
| 2133  | 16        | 7.27%   |
| 1333  | 8         | 3.64%   |
| 1067  | 5         | 2.27%   |
| 3600  | 4         | 1.82%   |
| 1867  | 4         | 1.82%   |
| 1334  | 3         | 1.36%   |
| 1066  | 3         | 1.36%   |
| 6400  | 2         | 0.91%   |
| 5600  | 2         | 0.91%   |
| 4800  | 2         | 0.91%   |
| 3800  | 2         | 0.91%   |
| 3666  | 2         | 0.91%   |
| 3266  | 2         | 0.91%   |
| 3151  | 2         | 0.91%   |
| 3066  | 2         | 0.91%   |
| 2134  | 2         | 0.91%   |
| 8400  | 1         | 0.45%   |
| 6000  | 1         | 0.45%   |
| 4267  | 1         | 0.45%   |
| 4199  | 1         | 0.45%   |
| 2800  | 1         | 0.45%   |
| 2666  | 1         | 0.45%   |
| 2000  | 1         | 0.45%   |
| 800   | 1         | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 66.67%  |
| Pantum      | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson EPSON L132 Series | 2         | 66.67%  |
| Pantum PMF22 series           | 1         | 33.33%  |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 54        | 21.86%  |
| IMC Networks                           | 43        | 17.41%  |
| Cheng Uei Precision Industry (Foxlink) | 21        | 8.5%    |
| Quanta                                 | 16        | 6.48%   |
| Bison Electronics                      | 16        | 6.48%   |
| Realtek Semiconductor                  | 15        | 6.07%   |
| Sunplus Innovation Technology          | 13        | 5.26%   |
| Microdia                               | 13        | 5.26%   |
| Luxvisions Innotech Limited            | 11        | 4.45%   |
| Lite-On Technology                     | 8         | 3.24%   |
| Suyin                                  | 5         | 2.02%   |
| Syntek                                 | 4         | 1.62%   |
| Sonix Technology                       | 3         | 1.21%   |
| Logitech                               | 3         | 1.21%   |
| Alcor Micro                            | 3         | 1.21%   |
| Acer                                   | 3         | 1.21%   |
| Z-Star Microelectronics                | 2         | 0.81%   |
| Silicon Motion                         | 2         | 0.81%   |
| Primax Electronics                     | 2         | 0.81%   |
| Apple                                  | 2         | 0.81%   |
| ANYKA                                  | 2         | 0.81%   |
| WCM_USB                                | 1         | 0.4%    |
| SiGma Micro                            | 1         | 0.4%    |
| ShineTech                              | 1         | 0.4%    |
| Jieli Technology                       | 1         | 0.4%    |
| Importek                               | 1         | 0.4%    |
| Unknown                                | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 15        | 6.05%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 12        | 4.84%   |
| Chicony USB2.0 VGA UVC WebCam                           | 12        | 4.84%   |
| IMC Networks Integrated Camera                          | 7         | 2.82%   |
| Microdia Integrated_Webcam_HD                           | 6         | 2.42%   |
| Chicony HD WebCam                                       | 6         | 2.42%   |
| IMC Networks VGA UVC WebCam                             | 5         | 2.02%   |
| Bison HD Webcam                                         | 5         | 2.02%   |
| Sunplus Integrated_Webcam_HD                            | 4         | 1.61%   |
| Realtek Integrated_Webcam_HD                            | 4         | 1.61%   |
| Luxvisions Innotech Limited HP HD Camera                | 4         | 1.61%   |
| Lite-On HP HD Camera                                    | 4         | 1.61%   |
| Chicony Integrated Camera                               | 4         | 1.61%   |
| Chicony HP HD Camera                                    | 4         | 1.61%   |
| Chicony EasyCamera                                      | 4         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera     | 4         | 1.61%   |
| Bison Integrated Camera                                 | 4         | 1.61%   |
| Syntek Integrated Camera                                | 3         | 1.21%   |
| Suyin Integrated_Webcam_HD                              | 3         | 1.21%   |
| Quanta HP TrueVision HD Camera                          | 3         | 1.21%   |
| Quanta HP HD Camera                                     | 3         | 1.21%   |
| Quanta HD Webcam                                        | 3         | 1.21%   |
| Luxvisions Innotech Limited Integrated Camera           | 3         | 1.21%   |
| IMC Networks USB2.0 HD IR UVC WebCam                    | 3         | 1.21%   |
| Chicony HP HD Webcam                                    | 3         | 1.21%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 3         | 1.21%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.21%   |
| Bison Lenovo EasyCamera                                 | 3         | 1.21%   |
| Z-Star A4 TECH USB2.0 PC Camera J                       | 2         | 0.81%   |
| Suyin HP Truevision HD                                  | 2         | 0.81%   |
| Sunplus Laptop Integrated Webcam HD                     | 2         | 0.81%   |
| Sonix USB2.0 HD UVC WebCam                              | 2         | 0.81%   |
| Realtek USB2.0 VGA UVC WebCam                           | 2         | 0.81%   |
| Realtek USB2.0 HD UVC WebCam                            | 2         | 0.81%   |
| Quanta HD User Facing                                   | 2         | 0.81%   |
| Primax HP HD Webcam [Fixed]                             | 2         | 0.81%   |
| Microdia HP Integrated Webcam                           | 2         | 0.81%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 0.81%   |
| Logitech Webcam C270                                    | 2         | 0.81%   |
| Lite-On Integrated Camera                               | 2         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 33        | 67.35%  |
| Synaptics                  | 9         | 18.37%  |
| Shenzhen Goodix Technology | 3         | 6.12%   |
| Elan Microelectronics      | 3         | 6.12%   |
| Upek                       | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 36.73%  |
| Validity Sensors VFS491                                                    | 4         | 8.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 8.16%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 6.12%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 4.08%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 4.08%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 4.08%   |
| Elan ELAN:Fingerprint                                                      | 2         | 4.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 2.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.04%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 2.04%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 2.04%   |
| Synaptics WBDI                                                             | 1         | 2.04%   |
| Synaptics  WBDI                                                            | 1         | 2.04%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 2.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 2.04%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Broadcom | 7         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 28.57%  |
| Broadcom 5880                                                                | 2         | 28.57%  |
| Broadcom 58200                                                               | 2         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 289       | 70.83%  |
| 1     | 100       | 24.51%  |
| 2     | 13        | 3.19%   |
| 3     | 3         | 0.74%   |
| 5     | 2         | 0.49%   |
| 4     | 1         | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 47        | 33.57%  |
| Graphics card            | 37        | 26.43%  |
| Net/wireless             | 20        | 14.29%  |
| Communication controller | 7         | 5%      |
| Chipcard                 | 7         | 5%      |
| Camera                   | 6         | 4.29%   |
| Bluetooth                | 6         | 4.29%   |
| Multimedia controller    | 5         | 3.57%   |
| Sound                    | 3         | 2.14%   |
| Unassigned class         | 1         | 0.71%   |
| Card reader              | 1         | 0.71%   |

