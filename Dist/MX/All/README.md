MX - Tested Hardware & Statistics
---------------------------------

A project to collect tested hardware configurations for MX.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX/Desktop/README.md) and [notebooks](/Dist/MX/Notebook/README.md).

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

Total: 1923

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ProBook 655 G1              | Notebook    | [428ad9e1da](https://linux-hardware.org/?probe=428ad9e1da) | Jan 02, 2026 |
| HP            | ProBook 655 G1              | Notebook    | [9d4441d7ff](https://linux-hardware.org/?probe=9d4441d7ff) | Jan 02, 2026 |
| Apple         | MacBookPro5,5               | Notebook    | [bf4dff23a5](https://linux-hardware.org/?probe=bf4dff23a5) | Jan 02, 2026 |
| Dell          | Latitude 5520               | Notebook    | [3da3572f73](https://linux-hardware.org/?probe=3da3572f73) | Jan 02, 2026 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [587c4317fa](https://linux-hardware.org/?probe=587c4317fa) | Jan 01, 2026 |
| Toshiba       | Satellite C850D-119         | Notebook    | [94c9e1ceba](https://linux-hardware.org/?probe=94c9e1ceba) | Jan 01, 2026 |
| ASUSTek       | Zenbook Flip UP3404VA_UP... | Convertible | [5f0da72d4a](https://linux-hardware.org/?probe=5f0da72d4a) | Dec 30, 2025 |
| Lenovo        | ThinkCentre M57 6071ADU     | Desktop     | [08990918a9](https://linux-hardware.org/?probe=08990918a9) | Dec 29, 2025 |
| Dell          | Vostro 15-3568              | Notebook    | [9bf916ef12](https://linux-hardware.org/?probe=9bf916ef12) | Dec 28, 2025 |
| Sony          | VPCEH2J1E                   | Notebook    | [de9cb788dd](https://linux-hardware.org/?probe=de9cb788dd) | Dec 25, 2025 |
| Lenovo        | G50-30 80G0                 | Notebook    | [eaca56d6a6](https://linux-hardware.org/?probe=eaca56d6a6) | Dec 25, 2025 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [c2c4520d0c](https://linux-hardware.org/?probe=c2c4520d0c) | Dec 24, 2025 |
| Lenovo        | ThinkPad T480 20L6S9UJ0Y    | Notebook    | [57cfc501d6](https://linux-hardware.org/?probe=57cfc501d6) | Dec 23, 2025 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [ccc3e59b14](https://linux-hardware.org/?probe=ccc3e59b14) | Dec 22, 2025 |
| Toshiba       | NB520                       | Notebook    | [9ed62aa4b7](https://linux-hardware.org/?probe=9ed62aa4b7) | Dec 21, 2025 |
| Acer          | Aspire A114-33              | Notebook    | [1773222e3d](https://linux-hardware.org/?probe=1773222e3d) | Dec 21, 2025 |
| Lenovo        | ThinkPad L580 20LW000VMX    | Notebook    | [c6cfe81aa5](https://linux-hardware.org/?probe=c6cfe81aa5) | Dec 20, 2025 |
| ASUSTek       | 1000HE                      | Notebook    | [aea8a66e54](https://linux-hardware.org/?probe=aea8a66e54) | Dec 20, 2025 |
| NEC Comput... | G1BVR2 A                    | All in one  | [6a2210fb28](https://linux-hardware.org/?probe=6a2210fb28) | Dec 18, 2025 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [0c9c335722](https://linux-hardware.org/?probe=0c9c335722) | Dec 16, 2025 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [89c1b0ace9](https://linux-hardware.org/?probe=89c1b0ace9) | Dec 16, 2025 |
| GMKtec        | NucBox K8 Plus              | Desktop     | [baff7be179](https://linux-hardware.org/?probe=baff7be179) | Dec 15, 2025 |
| Dell          | Latitude 5410               | Notebook    | [5dd93b27b0](https://linux-hardware.org/?probe=5dd93b27b0) | Dec 13, 2025 |
| Dell          | 0GDG8Y A00                  | Desktop     | [74489bc996](https://linux-hardware.org/?probe=74489bc996) | Dec 12, 2025 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [445e38a0af](https://linux-hardware.org/?probe=445e38a0af) | Dec 12, 2025 |
| AZW           | EQ                          | Desktop     | [9449d2ff9f](https://linux-hardware.org/?probe=9449d2ff9f) | Dec 12, 2025 |
| Dell          | Inspiron 7506 2n1           | Convertible | [262b2dbcb2](https://linux-hardware.org/?probe=262b2dbcb2) | Dec 11, 2025 |
| Dell          | Inspiron 7506 2n1           | Convertible | [644fa5b73d](https://linux-hardware.org/?probe=644fa5b73d) | Dec 11, 2025 |
| Apple         | MacBookPro14,1              | Notebook    | [1ca15aa6cd](https://linux-hardware.org/?probe=1ca15aa6cd) | Dec 10, 2025 |
| Medion        | NPxxRNA                     | Notebook    | [e9344c9092](https://linux-hardware.org/?probe=e9344c9092) | Dec 09, 2025 |
| Gigabyte      | A520M H                     | Desktop     | [0d1f8ef856](https://linux-hardware.org/?probe=0d1f8ef856) | Dec 09, 2025 |
| Gigabyte      | B460 HD3                    | Desktop     | [88e9427b13](https://linux-hardware.org/?probe=88e9427b13) | Dec 07, 2025 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [7a7e3c991a](https://linux-hardware.org/?probe=7a7e3c991a) | Dec 06, 2025 |
| Lenovo        | ThinkPad T590 20N5S3FR00    | Notebook    | [cc805f3509](https://linux-hardware.org/?probe=cc805f3509) | Dec 06, 2025 |
| Dell          | Latitude 5500               | Notebook    | [b5f9c9ebe4](https://linux-hardware.org/?probe=b5f9c9ebe4) | Dec 06, 2025 |
| Google        | Terra                       | Notebook    | [cede36936e](https://linux-hardware.org/?probe=cede36936e) | Dec 06, 2025 |
| LattePanda    | 3 Delta LP-BS-7-S70JR200... | Desktop     | [068350c8f9](https://linux-hardware.org/?probe=068350c8f9) | Dec 05, 2025 |
| ASRock        | X570 PG Velocita            | Desktop     | [d76200a58a](https://linux-hardware.org/?probe=d76200a58a) | Dec 05, 2025 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e713098184](https://linux-hardware.org/?probe=e713098184) | Dec 05, 2025 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [32b9f41c9d](https://linux-hardware.org/?probe=32b9f41c9d) | Dec 04, 2025 |
| Star Labs     | StarLite                    | Tablet      | [5cd612e6a3](https://linux-hardware.org/?probe=5cd612e6a3) | Dec 03, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [6e1acbb114](https://linux-hardware.org/?probe=6e1acbb114) | Dec 03, 2025 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [212a29eda9](https://linux-hardware.org/?probe=212a29eda9) | Dec 01, 2025 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [527ff37ff4](https://linux-hardware.org/?probe=527ff37ff4) | Nov 30, 2025 |
| Acer          | AO532h                      | Notebook    | [93ae5ca608](https://linux-hardware.org/?probe=93ae5ca608) | Nov 30, 2025 |
| ASUSTek       | K52Jc                       | Notebook    | [56b3a4c466](https://linux-hardware.org/?probe=56b3a4c466) | Nov 30, 2025 |
| ASUSTek       | K52Jc                       | Notebook    | [c098c92aab](https://linux-hardware.org/?probe=c098c92aab) | Nov 29, 2025 |
| HP            | 82DD 0001                   | All in one  | [a2b175f206](https://linux-hardware.org/?probe=a2b175f206) | Nov 29, 2025 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [635b3601d7](https://linux-hardware.org/?probe=635b3601d7) | Nov 27, 2025 |
| Fujitsu       | FMVNA7SE                    | Notebook    | [3e9482ed4c](https://linux-hardware.org/?probe=3e9482ed4c) | Nov 27, 2025 |
| Notebook      | NL5xRU                      | Notebook    | [a651458834](https://linux-hardware.org/?probe=a651458834) | Nov 27, 2025 |
| Dell          | 0WMJ54 A01                  | Desktop     | [9265b6709d](https://linux-hardware.org/?probe=9265b6709d) | Nov 25, 2025 |
| Foxconn       | 2A8C                        | Desktop     | [29b884f7a8](https://linux-hardware.org/?probe=29b884f7a8) | Nov 24, 2025 |
| Dell          | Vostro 3500                 | Notebook    | [d2ba738f11](https://linux-hardware.org/?probe=d2ba738f11) | Nov 23, 2025 |
| AZW           | EQ                          | Desktop     | [2bb38ce723](https://linux-hardware.org/?probe=2bb38ce723) | Nov 23, 2025 |
| Dell          | Latitude 5500               | Notebook    | [da824eeb52](https://linux-hardware.org/?probe=da824eeb52) | Nov 22, 2025 |
| ASRock        | B360M Pro4                  | Desktop     | [59e06dfbdc](https://linux-hardware.org/?probe=59e06dfbdc) | Nov 22, 2025 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [d36f00065b](https://linux-hardware.org/?probe=d36f00065b) | Nov 22, 2025 |
| Gigabyte      | B650M GAMING PLUS WIFI      | Desktop     | [3d1d1a9b31](https://linux-hardware.org/?probe=3d1d1a9b31) | Nov 22, 2025 |
| AZW           | EQ                          | Desktop     | [8ca2607f1e](https://linux-hardware.org/?probe=8ca2607f1e) | Nov 21, 2025 |
| Daten Tecn... | DVRN-4                      | Notebook    | [2146dd4395](https://linux-hardware.org/?probe=2146dd4395) | Nov 21, 2025 |
| Lenovo        | G50-45 80E3                 | Notebook    | [b10db4854c](https://linux-hardware.org/?probe=b10db4854c) | Nov 19, 2025 |
| Dell          | 03KWTV A00                  | Desktop     | [c16567816d](https://linux-hardware.org/?probe=c16567816d) | Nov 17, 2025 |
| Apple         | MacBookAir7,2               | Notebook    | [fadd3c1658](https://linux-hardware.org/?probe=fadd3c1658) | Nov 16, 2025 |
| ASRock        | A785GM-LE                   | Desktop     | [42290de27f](https://linux-hardware.org/?probe=42290de27f) | Nov 14, 2025 |
| Dell          | 0478VN A00                  | Desktop     | [d0416e02e4](https://linux-hardware.org/?probe=d0416e02e4) | Nov 14, 2025 |
| HP            | 2000                        | Notebook    | [a87e9d5e79](https://linux-hardware.org/?probe=a87e9d5e79) | Nov 14, 2025 |
| HP            | ENVY Laptop 17-cg1xxx       | Notebook    | [8da244ccdd](https://linux-hardware.org/?probe=8da244ccdd) | Nov 14, 2025 |
| Dell          | 088DT1 A01                  | Desktop     | [b48e66c63c](https://linux-hardware.org/?probe=b48e66c63c) | Nov 14, 2025 |
| Dell          | 0GDG8Y A00                  | Desktop     | [9bbb18a6ce](https://linux-hardware.org/?probe=9bbb18a6ce) | Nov 13, 2025 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [b2d8511070](https://linux-hardware.org/?probe=b2d8511070) | Nov 13, 2025 |
| Toshiba       | Satellite C70-B             | Notebook    | [6c24d32c03](https://linux-hardware.org/?probe=6c24d32c03) | Nov 13, 2025 |
| Sony          | VPCEB4M1E                   | Notebook    | [85d85991d2](https://linux-hardware.org/?probe=85d85991d2) | Nov 12, 2025 |
| Sony          | VPCEB4M1E                   | Notebook    | [e4afefa75f](https://linux-hardware.org/?probe=e4afefa75f) | Nov 12, 2025 |
| Toshiba       | Satellite L510              | Notebook    | [9c228175c9](https://linux-hardware.org/?probe=9c228175c9) | Nov 12, 2025 |
| Dell          | Vostro 3400                 | Notebook    | [5803878a17](https://linux-hardware.org/?probe=5803878a17) | Nov 09, 2025 |
| Lenovo        | MIIX 3-1030 80HV            | Tablet      | [e7956c7a25](https://linux-hardware.org/?probe=e7956c7a25) | Nov 06, 2025 |
| Dell          | Inspiron 16 5645            | Notebook    | [7f29a20d7d](https://linux-hardware.org/?probe=7f29a20d7d) | Nov 05, 2025 |
| AMI           | Cherry Trail CR             | Mini pc     | [a3486f9c70](https://linux-hardware.org/?probe=a3486f9c70) | Nov 04, 2025 |
| HP            | 2000                        | Notebook    | [df6a6894b0](https://linux-hardware.org/?probe=df6a6894b0) | Nov 04, 2025 |
| ASUSTek       | UX303UA                     | Notebook    | [5e97e42d1f](https://linux-hardware.org/?probe=5e97e42d1f) | Nov 02, 2025 |
| ASUSTek       | UX430UNR                    | Notebook    | [99d51c0dba](https://linux-hardware.org/?probe=99d51c0dba) | Nov 01, 2025 |
| Medion        | Crawler E30e                | Notebook    | [cad65708be](https://linux-hardware.org/?probe=cad65708be) | Nov 01, 2025 |
| HP            | 1998                        | Desktop     | [9d0728359d](https://linux-hardware.org/?probe=9d0728359d) | Oct 30, 2025 |
| Fujitsu       | FARV04001Z                  | Tablet      | [b9f7f0433a](https://linux-hardware.org/?probe=b9f7f0433a) | Oct 29, 2025 |
| Lenovo        | ThinkPad X200 74553XG       | Notebook    | [f26926f29c](https://linux-hardware.org/?probe=f26926f29c) | Oct 29, 2025 |
| Fujitsu Si... | AMILO Pi 2540               | Notebook    | [33db8bddec](https://linux-hardware.org/?probe=33db8bddec) | Oct 23, 2025 |
| HP            | Stream Notebook PC 11       | Notebook    | [d4d64a6d08](https://linux-hardware.org/?probe=d4d64a6d08) | Oct 23, 2025 |
| Unknown       | Unknown                     | Mini pc     | [a802e1cd41](https://linux-hardware.org/?probe=a802e1cd41) | Oct 23, 2025 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [dd70fdf93b](https://linux-hardware.org/?probe=dd70fdf93b) | Oct 21, 2025 |
| Dell          | Inspiron 5567               | Notebook    | [2f13ec3188](https://linux-hardware.org/?probe=2f13ec3188) | Oct 21, 2025 |
| Dell          | Inspiron 5567               | Notebook    | [e9f9adf8ef](https://linux-hardware.org/?probe=e9f9adf8ef) | Oct 21, 2025 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [e5e1c3eb94](https://linux-hardware.org/?probe=e5e1c3eb94) | Oct 20, 2025 |
| Toshiba       | Satellite L510              | Notebook    | [3f681fe057](https://linux-hardware.org/?probe=3f681fe057) | Oct 20, 2025 |
| Dell          | Latitude E5540              | Notebook    | [4c8afbabca](https://linux-hardware.org/?probe=4c8afbabca) | Oct 19, 2025 |
| Acer          | Aspire AG15-51P             | Notebook    | [1b96a53761](https://linux-hardware.org/?probe=1b96a53761) | Oct 16, 2025 |
| Unknown       | Unknown                     | Desktop     | [8dfb06ae56](https://linux-hardware.org/?probe=8dfb06ae56) | Oct 15, 2025 |
| ASUSTek       | Maximus VIII GENE           | Desktop     | [67bb684b06](https://linux-hardware.org/?probe=67bb684b06) | Oct 15, 2025 |
| Dell          | 0XCR8D A01                  | Desktop     | [5c64a80eb3](https://linux-hardware.org/?probe=5c64a80eb3) | Oct 14, 2025 |
| Dell          | 0XCR8D A01                  | Desktop     | [61a4c8e8b9](https://linux-hardware.org/?probe=61a4c8e8b9) | Oct 14, 2025 |
| Dell          | Inspiron N4020              | Notebook    | [45dd2629b5](https://linux-hardware.org/?probe=45dd2629b5) | Oct 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [6e27bedba7](https://linux-hardware.org/?probe=6e27bedba7) | Oct 07, 2025 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [75993f5957](https://linux-hardware.org/?probe=75993f5957) | Oct 07, 2025 |
| Wortmann      | 1220663_1470189             | Notebook    | [8be31b3cbc](https://linux-hardware.org/?probe=8be31b3cbc) | Oct 06, 2025 |
| ASUSTek       | UX410UQK                    | Notebook    | [ebb2f63d3b](https://linux-hardware.org/?probe=ebb2f63d3b) | Oct 06, 2025 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [81d1a3e7a8](https://linux-hardware.org/?probe=81d1a3e7a8) | Oct 06, 2025 |
| Google        | Treeya                      | Notebook    | [4d63a8557b](https://linux-hardware.org/?probe=4d63a8557b) | Oct 06, 2025 |
| Lenovo        | G50-70 20351                | Notebook    | [408a86830b](https://linux-hardware.org/?probe=408a86830b) | Oct 05, 2025 |
| Lenovo        | G50-70 20351                | Notebook    | [74fdf4158c](https://linux-hardware.org/?probe=74fdf4158c) | Oct 05, 2025 |
| American M... | K7S41GX                     | Desktop     | [53edf0f2d4](https://linux-hardware.org/?probe=53edf0f2d4) | Oct 05, 2025 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [3f99eb19f4](https://linux-hardware.org/?probe=3f99eb19f4) | Oct 05, 2025 |
| HP            | Pavilion Laptop 15z-eh00... | Notebook    | [2518904235](https://linux-hardware.org/?probe=2518904235) | Oct 05, 2025 |
| ZOTAC         | ZBOX-MI/CI625/645/665NAN... | Mini pc     | [180dca4c87](https://linux-hardware.org/?probe=180dca4c87) | Oct 04, 2025 |
| ZOTAC         | ZBOX-MI/CI625/645/665NAN... | Mini pc     | [003412db2b](https://linux-hardware.org/?probe=003412db2b) | Oct 04, 2025 |
| GMKtec        | NucBox K10                  | Mini pc     | [81cb41ece6](https://linux-hardware.org/?probe=81cb41ece6) | Oct 02, 2025 |
| Dell          | 0HD5W2 A00                  | Desktop     | [4a76959f28](https://linux-hardware.org/?probe=4a76959f28) | Oct 01, 2025 |
| Dell          | 0HD5W2 A00                  | Desktop     | [b1ce088521](https://linux-hardware.org/?probe=b1ce088521) | Oct 01, 2025 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [eb13d054d5](https://linux-hardware.org/?probe=eb13d054d5) | Sep 29, 2025 |
| Unknown       | 1.0                         | Desktop     | [16637d807e](https://linux-hardware.org/?probe=16637d807e) | Sep 28, 2025 |
| Apple         | MacBookAir7,1               | Notebook    | [688a16bfec](https://linux-hardware.org/?probe=688a16bfec) | Sep 28, 2025 |
| HP            | EliteBook 645 14 inch G1... | Notebook    | [da0ebf373b](https://linux-hardware.org/?probe=da0ebf373b) | Sep 27, 2025 |
| Unknown       | K7VT6-C                     | Desktop     | [1ebf11a51e](https://linux-hardware.org/?probe=1ebf11a51e) | Sep 27, 2025 |
| Unknown       | K7VT6-C                     | Desktop     | [5acc199b06](https://linux-hardware.org/?probe=5acc199b06) | Sep 27, 2025 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [c8a02404e8](https://linux-hardware.org/?probe=c8a02404e8) | Sep 26, 2025 |
| Gigabyte      | Z690 GAMING X DDR4 V2       | Desktop     | [8e8f810fcf](https://linux-hardware.org/?probe=8e8f810fcf) | Sep 26, 2025 |
| HP            | Pavilion Laptop 15z-eh00... | Notebook    | [25f8f8f056](https://linux-hardware.org/?probe=25f8f8f056) | Sep 24, 2025 |
| ONERugged     | P10J                        | Tablet      | [6c7d053405](https://linux-hardware.org/?probe=6c7d053405) | Sep 22, 2025 |
| Dell          | 0NW6H5 A00                  | Desktop     | [bb3382d1b8](https://linux-hardware.org/?probe=bb3382d1b8) | Sep 21, 2025 |
| Dell          | Inspiron N7010              | Notebook    | [75c303ee55](https://linux-hardware.org/?probe=75c303ee55) | Sep 21, 2025 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [fde585ff82](https://linux-hardware.org/?probe=fde585ff82) | Sep 20, 2025 |
| HP            | ProBook 440 G7              | Notebook    | [792c15eeb7](https://linux-hardware.org/?probe=792c15eeb7) | Sep 20, 2025 |
| Acer          | AO722                       | Notebook    | [f1a6eab88d](https://linux-hardware.org/?probe=f1a6eab88d) | Sep 19, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [e36fc51285](https://linux-hardware.org/?probe=e36fc51285) | Sep 15, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [d38939253e](https://linux-hardware.org/?probe=d38939253e) | Sep 15, 2025 |
| Dell          | Inspiron 16 5645            | Notebook    | [4a93f8b0d1](https://linux-hardware.org/?probe=4a93f8b0d1) | Sep 15, 2025 |
| Medion        | E15223                      | Notebook    | [c062b348d1](https://linux-hardware.org/?probe=c062b348d1) | Sep 15, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [3618f3c44d](https://linux-hardware.org/?probe=3618f3c44d) | Sep 14, 2025 |
| ASRock        | A300M-STX                   | Desktop     | [505139ae3b](https://linux-hardware.org/?probe=505139ae3b) | Sep 14, 2025 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [c8da642ab9](https://linux-hardware.org/?probe=c8da642ab9) | Sep 13, 2025 |
| Dell          | Inspiron 16 5645            | Notebook    | [abcdd54c4d](https://linux-hardware.org/?probe=abcdd54c4d) | Sep 12, 2025 |
| Lenovo        | 3148 SDK0J40700 WIN 3258... | Desktop     | [ced811cdc0](https://linux-hardware.org/?probe=ced811cdc0) | Sep 10, 2025 |
| Lenovo        | 3148 SDK0J40700 WIN 3258... | Desktop     | [34d7d5986b](https://linux-hardware.org/?probe=34d7d5986b) | Sep 10, 2025 |
| PCBOX         | PCB-GLW2                    | Notebook    | [0d2fd19d0e](https://linux-hardware.org/?probe=0d2fd19d0e) | Sep 10, 2025 |
| Dell          | 0VG93V A00                  | Desktop     | [f938f4ce6a](https://linux-hardware.org/?probe=f938f4ce6a) | Sep 09, 2025 |
| Apple         | MacBookAir6,2               | Notebook    | [8fed6df5bb](https://linux-hardware.org/?probe=8fed6df5bb) | Sep 07, 2025 |
| HP            | ProBook 470 G3              | Notebook    | [097eca27df](https://linux-hardware.org/?probe=097eca27df) | Sep 06, 2025 |
| Acer          | TravelMate B311-31          | Notebook    | [20e8fc805c](https://linux-hardware.org/?probe=20e8fc805c) | Sep 03, 2025 |
| HP            | Pavilion 15                 | Notebook    | [ab1864300c](https://linux-hardware.org/?probe=ab1864300c) | Sep 02, 2025 |
| Unknown       | Unknown                     | Desktop     | [86804b57a4](https://linux-hardware.org/?probe=86804b57a4) | Aug 31, 2025 |
| Unknown       | AX16PRO                     | Notebook    | [3a42432fe5](https://linux-hardware.org/?probe=3a42432fe5) | Aug 28, 2025 |
| GMKtec        | NucBox K10                  | Mini pc     | [2a9421a6fb](https://linux-hardware.org/?probe=2a9421a6fb) | Aug 26, 2025 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [ce15c49d7f](https://linux-hardware.org/?probe=ce15c49d7f) | Aug 26, 2025 |
| HP            | ProBook 470 G3              | Notebook    | [07e76d8dd5](https://linux-hardware.org/?probe=07e76d8dd5) | Aug 23, 2025 |
| Lenovo        | 3148 SDK0J40700 WIN 3258... | Desktop     | [96eace97f0](https://linux-hardware.org/?probe=96eace97f0) | Aug 23, 2025 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [a80e84712a](https://linux-hardware.org/?probe=a80e84712a) | Aug 23, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [defcf8d9c2](https://linux-hardware.org/?probe=defcf8d9c2) | Aug 22, 2025 |
| GMKtec        | NucBox K10                  | Mini pc     | [d67ab48115](https://linux-hardware.org/?probe=d67ab48115) | Aug 20, 2025 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [307b882e42](https://linux-hardware.org/?probe=307b882e42) | Aug 20, 2025 |
| Dell          | 0CRWCR A01                  | All in one  | [b5c49ac337](https://linux-hardware.org/?probe=b5c49ac337) | Aug 18, 2025 |
| MSI           | GE62 2QF                    | Notebook    | [d7f7fecb75](https://linux-hardware.org/?probe=d7f7fecb75) | Aug 17, 2025 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [8a410a9c2c](https://linux-hardware.org/?probe=8a410a9c2c) | Aug 16, 2025 |
| Biostar       | G41D3+                      | Desktop     | [0fa7f0d0df](https://linux-hardware.org/?probe=0fa7f0d0df) | Aug 15, 2025 |
| Gigabyte      | B850 AORUS ELITE WIFI7 I... | Desktop     | [66b3deb7ce](https://linux-hardware.org/?probe=66b3deb7ce) | Aug 13, 2025 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [3a07ec8362](https://linux-hardware.org/?probe=3a07ec8362) | Aug 13, 2025 |
| ASUSTek       | Q170M-C                     | Desktop     | [a13c14f3d4](https://linux-hardware.org/?probe=a13c14f3d4) | Aug 12, 2025 |
| HP            | 0B4Ch D                     | Desktop     | [19684fb424](https://linux-hardware.org/?probe=19684fb424) | Aug 12, 2025 |
| MSI           | Z170M MORTAR                | Desktop     | [15ef7008ac](https://linux-hardware.org/?probe=15ef7008ac) | Aug 11, 2025 |
| MSI           | Z170M MORTAR                | Desktop     | [5a8d247921](https://linux-hardware.org/?probe=5a8d247921) | Aug 11, 2025 |
| HP            | Pavilion 15                 | Notebook    | [8bc227fe80](https://linux-hardware.org/?probe=8bc227fe80) | Aug 10, 2025 |
| Google        | Treeya                      | Notebook    | [57c5dfda3f](https://linux-hardware.org/?probe=57c5dfda3f) | Aug 09, 2025 |
| ASUSTek       | X202E                       | Notebook    | [224f9800a0](https://linux-hardware.org/?probe=224f9800a0) | Aug 09, 2025 |
| ASUSTek       | X202E                       | Notebook    | [54719df93e](https://linux-hardware.org/?probe=54719df93e) | Aug 09, 2025 |
| TianBei       | GOD88                       | Desktop     | [78f58ee6e2](https://linux-hardware.org/?probe=78f58ee6e2) | Aug 08, 2025 |
| Dell          | Studio XPS 1640             | Notebook    | [af14bd2dea](https://linux-hardware.org/?probe=af14bd2dea) | Aug 07, 2025 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [59b5c22a28](https://linux-hardware.org/?probe=59b5c22a28) | Aug 05, 2025 |
| Dell          | Latitude 9510               | Notebook    | [f898a3708e](https://linux-hardware.org/?probe=f898a3708e) | Aug 05, 2025 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [52f9d3da90](https://linux-hardware.org/?probe=52f9d3da90) | Aug 03, 2025 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [d765b11397](https://linux-hardware.org/?probe=d765b11397) | Aug 03, 2025 |
| MSI           | Modern 14 A10M              | Notebook    | [b3323d296c](https://linux-hardware.org/?probe=b3323d296c) | Aug 01, 2025 |
| Acer          | TravelMate P215-53          | Notebook    | [6f2159a6ff](https://linux-hardware.org/?probe=6f2159a6ff) | Jul 31, 2025 |
| Acer          | Aspire one 1-431            | Notebook    | [8c04b9267a](https://linux-hardware.org/?probe=8c04b9267a) | Jul 31, 2025 |
| Unknown       | Unknown                     | Notebook    | [458d6debf1](https://linux-hardware.org/?probe=458d6debf1) | Jul 30, 2025 |
| Dell          | Latitude 5400               | Notebook    | [5be654e778](https://linux-hardware.org/?probe=5be654e778) | Jul 30, 2025 |
| Dell          | Vostro 3500                 | Notebook    | [c2d479c2e8](https://linux-hardware.org/?probe=c2d479c2e8) | Jul 30, 2025 |
| Apple         | MacBookPro9,2               | Notebook    | [e3b80533b2](https://linux-hardware.org/?probe=e3b80533b2) | Jul 28, 2025 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [75d8a5514e](https://linux-hardware.org/?probe=75d8a5514e) | Jul 27, 2025 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [e754f28930](https://linux-hardware.org/?probe=e754f28930) | Jul 25, 2025 |
| HP            | Pavilion dv6500             | Notebook    | [3d658232b3](https://linux-hardware.org/?probe=3d658232b3) | Jul 25, 2025 |
| Apple         | MacBookAir2,1               | Notebook    | [20f1fb531e](https://linux-hardware.org/?probe=20f1fb531e) | Jul 23, 2025 |
| ASUSTek       | PRIME H470-PLUS             | Desktop     | [08f05cc5df](https://linux-hardware.org/?probe=08f05cc5df) | Jul 23, 2025 |
| Apple         | MacBookAir1,1               | Notebook    | [633472e541](https://linux-hardware.org/?probe=633472e541) | Jul 22, 2025 |
| ECS           | P43G                        | Desktop     | [399e8e60fa](https://linux-hardware.org/?probe=399e8e60fa) | Jul 22, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [78bf64aa11](https://linux-hardware.org/?probe=78bf64aa11) | Jul 22, 2025 |
| HP            | Laptop                      | Notebook    | [6e1a0ff0fa](https://linux-hardware.org/?probe=6e1a0ff0fa) | Jul 21, 2025 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dd28fb514f](https://linux-hardware.org/?probe=dd28fb514f) | Jul 18, 2025 |
| Acer          | Aspire 5750G                | Notebook    | [3c42e357d1](https://linux-hardware.org/?probe=3c42e357d1) | Jul 16, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [647e63d412](https://linux-hardware.org/?probe=647e63d412) | Jul 15, 2025 |
| Acer          | Predator PH18-72            | Notebook    | [795524aef0](https://linux-hardware.org/?probe=795524aef0) | Jul 14, 2025 |
| AMI           | Aptio CRB                   | Mini pc     | [d35d5d19fe](https://linux-hardware.org/?probe=d35d5d19fe) | Jul 13, 2025 |
| HP            | Pavilion dv6500             | Notebook    | [da1f1188d0](https://linux-hardware.org/?probe=da1f1188d0) | Jul 10, 2025 |
| Alienware     | 17 R4                       | Notebook    | [91ebf4cf72](https://linux-hardware.org/?probe=91ebf4cf72) | Jul 10, 2025 |
| Toshiba       | STI 012887                  | Desktop     | [d9df19d48a](https://linux-hardware.org/?probe=d9df19d48a) | Jul 09, 2025 |
| Alienware     | 17 R4                       | Notebook    | [1557d34a34](https://linux-hardware.org/?probe=1557d34a34) | Jul 08, 2025 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [82fb91ab48](https://linux-hardware.org/?probe=82fb91ab48) | Jul 05, 2025 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [7b1303b585](https://linux-hardware.org/?probe=7b1303b585) | Jul 05, 2025 |
| Unknown       | G41 Series                  | Desktop     | [d1ececac79](https://linux-hardware.org/?probe=d1ececac79) | Jul 04, 2025 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [a208fc1359](https://linux-hardware.org/?probe=a208fc1359) | Jul 02, 2025 |
| Toshiba       | Satellite C70D-B            | Notebook    | [35f24ff6b4](https://linux-hardware.org/?probe=35f24ff6b4) | Jul 01, 2025 |
| Infinix       | GL613                       | Notebook    | [0a7f9146e1](https://linux-hardware.org/?probe=0a7f9146e1) | Jun 30, 2025 |
| Wortmann      | TERRA_PC                    | Desktop     | [41b1554dad](https://linux-hardware.org/?probe=41b1554dad) | Jun 28, 2025 |
| Wortmann      | TERRA_PC                    | Desktop     | [66faf9c677](https://linux-hardware.org/?probe=66faf9c677) | Jun 28, 2025 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7f33350270](https://linux-hardware.org/?probe=7f33350270) | Jun 27, 2025 |
| ATARI         | VCS 800 Onyx                | Notebook    | [6d9422b126](https://linux-hardware.org/?probe=6d9422b126) | Jun 27, 2025 |
| ASUSTek       | F3Sg                        | Notebook    | [acc043daec](https://linux-hardware.org/?probe=acc043daec) | Jun 26, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [1d719b744d](https://linux-hardware.org/?probe=1d719b744d) | Jun 24, 2025 |
| Intel         | powered classmate PC        | Notebook    | [e41e762d92](https://linux-hardware.org/?probe=e41e762d92) | Jun 23, 2025 |
| Acer          | Aspire A315-41G             | Notebook    | [89e44ec862](https://linux-hardware.org/?probe=89e44ec862) | Jun 21, 2025 |
| Acer          | One S1003P                  | Tablet      | [2f17341bdc](https://linux-hardware.org/?probe=2f17341bdc) | Jun 20, 2025 |
| Acer          | One S1003P                  | Tablet      | [2991add303](https://linux-hardware.org/?probe=2991add303) | Jun 20, 2025 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [90bf1ec264](https://linux-hardware.org/?probe=90bf1ec264) | Jun 19, 2025 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [ffc8b739e3](https://linux-hardware.org/?probe=ffc8b739e3) | Jun 19, 2025 |
| Acer          | H610MHP-E                   | Desktop     | [ca0ccf0dc6](https://linux-hardware.org/?probe=ca0ccf0dc6) | Jun 19, 2025 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [f35c3f0d97](https://linux-hardware.org/?probe=f35c3f0d97) | Jun 18, 2025 |
| MSI           | Z170A PC MATE               | Desktop     | [9f9f242399](https://linux-hardware.org/?probe=9f9f242399) | Jun 17, 2025 |
| Intel         | powered classmate PC        | Notebook    | [73e28609cc](https://linux-hardware.org/?probe=73e28609cc) | Jun 16, 2025 |
| Intel         | powered classmate PC        | Notebook    | [ba84a1c954](https://linux-hardware.org/?probe=ba84a1c954) | Jun 16, 2025 |
| Intel         | powered classmate PC        | Notebook    | [de05adf4be](https://linux-hardware.org/?probe=de05adf4be) | Jun 16, 2025 |
| Pegatron      | 2A73h                       | Desktop     | [0fda070d5b](https://linux-hardware.org/?probe=0fda070d5b) | Jun 15, 2025 |
| Acer          | Aspire E1-432               | Notebook    | [5549edc6d3](https://linux-hardware.org/?probe=5549edc6d3) | Jun 15, 2025 |
| HP            | Presario CQ57               | Notebook    | [abfed818bb](https://linux-hardware.org/?probe=abfed818bb) | Jun 15, 2025 |
| Intel         | powered classmate PC        | Notebook    | [cb98fcf7b0](https://linux-hardware.org/?probe=cb98fcf7b0) | Jun 13, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4e48864c36](https://linux-hardware.org/?probe=4e48864c36) | Jun 13, 2025 |
| MSI           | Z170A PC MATE               | Desktop     | [29cb3a4f3a](https://linux-hardware.org/?probe=29cb3a4f3a) | Jun 13, 2025 |
| Intel         | powered classmate PC        | Notebook    | [5ed3743c9f](https://linux-hardware.org/?probe=5ed3743c9f) | Jun 11, 2025 |
| Intel         | powered classmate PC        | Notebook    | [1ef141a39b](https://linux-hardware.org/?probe=1ef141a39b) | Jun 11, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [f246b5c8ee](https://linux-hardware.org/?probe=f246b5c8ee) | Jun 11, 2025 |
| Intel         | powered classmate PC        | Notebook    | [cdcfcc2077](https://linux-hardware.org/?probe=cdcfcc2077) | Jun 10, 2025 |
| HP            | Notebook                    | Notebook    | [d1fbc3acd3](https://linux-hardware.org/?probe=d1fbc3acd3) | Jun 08, 2025 |
| HP            | Notebook                    | Notebook    | [8e678c782d](https://linux-hardware.org/?probe=8e678c782d) | Jun 08, 2025 |
| MSI           | B360M BAZOOKA               | Desktop     | [076c8b5a2f](https://linux-hardware.org/?probe=076c8b5a2f) | Jun 05, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [55ba6e9314](https://linux-hardware.org/?probe=55ba6e9314) | Jun 05, 2025 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [c4951d5137](https://linux-hardware.org/?probe=c4951d5137) | Jun 05, 2025 |
| Dell          | 0D441T A01                  | Desktop     | [0929612cd7](https://linux-hardware.org/?probe=0929612cd7) | Jun 04, 2025 |
| Daten Tecn... | DVRN-4                      | Notebook    | [4369bd8486](https://linux-hardware.org/?probe=4369bd8486) | Jun 02, 2025 |
| HP            | 8062                        | Desktop     | [14a0fffacf](https://linux-hardware.org/?probe=14a0fffacf) | Jun 01, 2025 |
| Dell          | System Inspiron N411Z       | Notebook    | [333a275c1e](https://linux-hardware.org/?probe=333a275c1e) | Jun 01, 2025 |
| Microsoft     | Surface Pro 3               | Tablet      | [bf30400518](https://linux-hardware.org/?probe=bf30400518) | May 27, 2025 |
| HP            | Pavilion Notebook           | Notebook    | [372f4efe68](https://linux-hardware.org/?probe=372f4efe68) | May 24, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [da660b8818](https://linux-hardware.org/?probe=da660b8818) | May 24, 2025 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [4689020ecc](https://linux-hardware.org/?probe=4689020ecc) | May 24, 2025 |
| Apple         | Mac-F2218EA9                | All in one  | [88be8c5ee8](https://linux-hardware.org/?probe=88be8c5ee8) | May 24, 2025 |
| Microsoft     | Surface Pro 3               | Tablet      | [508ccbd8bd](https://linux-hardware.org/?probe=508ccbd8bd) | May 23, 2025 |
| Apple         | MacBookAir1,1               | Notebook    | [ad5dcf0a77](https://linux-hardware.org/?probe=ad5dcf0a77) | May 22, 2025 |
| MSI           | Z170M MORTAR                | Desktop     | [2b4da03498](https://linux-hardware.org/?probe=2b4da03498) | May 22, 2025 |
| Acer          | Aspire AV16-51P             | Notebook    | [6e14a97260](https://linux-hardware.org/?probe=6e14a97260) | May 21, 2025 |
| HP            | 212B                        | Desktop     | [ae68308b57](https://linux-hardware.org/?probe=ae68308b57) | May 19, 2025 |
| Unknown       | Unknown                     | Notebook    | [db9efb83b5](https://linux-hardware.org/?probe=db9efb83b5) | May 19, 2025 |
| HP            | Laptop 14-em0xxx            | Notebook    | [35532415da](https://linux-hardware.org/?probe=35532415da) | May 17, 2025 |
| HP            | Laptop 14-em0xxx            | Notebook    | [cc3799f7b4](https://linux-hardware.org/?probe=cc3799f7b4) | May 17, 2025 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [c971e9e2e1](https://linux-hardware.org/?probe=c971e9e2e1) | May 17, 2025 |
| HP            | Pavilion dv7                | Notebook    | [90c8da4c22](https://linux-hardware.org/?probe=90c8da4c22) | May 17, 2025 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c7332c10e4](https://linux-hardware.org/?probe=c7332c10e4) | May 15, 2025 |
| Acer          | Aspire A315-41              | Notebook    | [839b8194be](https://linux-hardware.org/?probe=839b8194be) | May 14, 2025 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [d68381eaa0](https://linux-hardware.org/?probe=d68381eaa0) | May 14, 2025 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [bb45bbd399](https://linux-hardware.org/?probe=bb45bbd399) | May 12, 2025 |
| HP            | Pavilion x2 Detachable P... | Notebook    | [4810457ca4](https://linux-hardware.org/?probe=4810457ca4) | May 11, 2025 |
| Pegatron      | 2A73h                       | Desktop     | [8b12a95d66](https://linux-hardware.org/?probe=8b12a95d66) | May 11, 2025 |
| Alienware     | 17 R4                       | Notebook    | [68d5433cb2](https://linux-hardware.org/?probe=68d5433cb2) | May 11, 2025 |
| ASUSTek       | AM1M-A                      | Desktop     | [f2914ba8d5](https://linux-hardware.org/?probe=f2914ba8d5) | May 10, 2025 |
| GEEKOM        | Mini IT13                   | Desktop     | [4ec9643d63](https://linux-hardware.org/?probe=4ec9643d63) | May 07, 2025 |
| Dell          | Inspiron 14-3467            | Notebook    | [bf2355ffc1](https://linux-hardware.org/?probe=bf2355ffc1) | May 05, 2025 |
| Toshiba       | Satellite A300              | Notebook    | [fbc016a6c1](https://linux-hardware.org/?probe=fbc016a6c1) | May 04, 2025 |
| HP            | ENVY 15 x360 PC             | Notebook    | [bbf9f60a98](https://linux-hardware.org/?probe=bbf9f60a98) | May 04, 2025 |
| Toshiba       | Satellite A300              | Notebook    | [9b925ffdf3](https://linux-hardware.org/?probe=9b925ffdf3) | May 04, 2025 |
| Unknown       | AB07C                       | Desktop     | [a99ad523fa](https://linux-hardware.org/?probe=a99ad523fa) | May 03, 2025 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5219e561b2](https://linux-hardware.org/?probe=5219e561b2) | May 03, 2025 |
| ECS           | JSLM-Q3D                    | Desktop     | [54d83cdee4](https://linux-hardware.org/?probe=54d83cdee4) | May 03, 2025 |
| Apple         | MacBookPro7,1               | Notebook    | [891baab7c7](https://linux-hardware.org/?probe=891baab7c7) | May 02, 2025 |
| Dell          | Inspiron 14-3467            | Notebook    | [070c57d0ef](https://linux-hardware.org/?probe=070c57d0ef) | Apr 30, 2025 |
| Intel         | B75                         | Desktop     | [ea4c550813](https://linux-hardware.org/?probe=ea4c550813) | Apr 30, 2025 |
| Dell          | Precision 3530              | Notebook    | [73f7113ffb](https://linux-hardware.org/?probe=73f7113ffb) | Apr 29, 2025 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [6e493e3bd8](https://linux-hardware.org/?probe=6e493e3bd8) | Apr 28, 2025 |
| Dell          | Latitude E6400              | Notebook    | [56e60c04c9](https://linux-hardware.org/?probe=56e60c04c9) | Apr 27, 2025 |
| Dell          | Latitude E6400              | Notebook    | [f9d2b3e6d9](https://linux-hardware.org/?probe=f9d2b3e6d9) | Apr 27, 2025 |
| Acer          | Aspire 7750                 | Notebook    | [7290031e9e](https://linux-hardware.org/?probe=7290031e9e) | Apr 26, 2025 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [6928ed0afd](https://linux-hardware.org/?probe=6928ed0afd) | Apr 26, 2025 |
| Lenovo        | G50-45 80E3                 | Notebook    | [b888f58f60](https://linux-hardware.org/?probe=b888f58f60) | Apr 26, 2025 |
| ASUSTek       | P552LA                      | Notebook    | [8c9c5975a0](https://linux-hardware.org/?probe=8c9c5975a0) | Apr 25, 2025 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [f3e8946a13](https://linux-hardware.org/?probe=f3e8946a13) | Apr 24, 2025 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b36b9677ac](https://linux-hardware.org/?probe=b36b9677ac) | Apr 24, 2025 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [703bd9063a](https://linux-hardware.org/?probe=703bd9063a) | Apr 24, 2025 |
| Samsung       | N150/N210/N220              | Notebook    | [60a16df78d](https://linux-hardware.org/?probe=60a16df78d) | Apr 21, 2025 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [6947eaa50a](https://linux-hardware.org/?probe=6947eaa50a) | Apr 19, 2025 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [0fb34fd396](https://linux-hardware.org/?probe=0fb34fd396) | Apr 18, 2025 |
| MSI           | 760GM-P21                   | Desktop     | [a4a0a6cb5b](https://linux-hardware.org/?probe=a4a0a6cb5b) | Apr 17, 2025 |
| MSI           | 760GM-P21                   | Desktop     | [88d1d194e5](https://linux-hardware.org/?probe=88d1d194e5) | Apr 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [261cca5e2a](https://linux-hardware.org/?probe=261cca5e2a) | Apr 17, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [e045bb43a0](https://linux-hardware.org/?probe=e045bb43a0) | Apr 17, 2025 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b11cb00993](https://linux-hardware.org/?probe=b11cb00993) | Apr 17, 2025 |
| HP            | Pavilion dv7                | Notebook    | [bc8ee714aa](https://linux-hardware.org/?probe=bc8ee714aa) | Apr 13, 2025 |
| Dell          | Latitude E5500              | Notebook    | [8c5aad5e48](https://linux-hardware.org/?probe=8c5aad5e48) | Apr 12, 2025 |
| Lenovo        | 3148 SDK0J40700 WIN 3258... | Desktop     | [9b91cc31e7](https://linux-hardware.org/?probe=9b91cc31e7) | Apr 10, 2025 |
| MSI           | B75MA-E33                   | Desktop     | [79f17e1162](https://linux-hardware.org/?probe=79f17e1162) | Apr 10, 2025 |
| Dell          | 0HD5W2 A01                  | Desktop     | [149fec45ec](https://linux-hardware.org/?probe=149fec45ec) | Apr 10, 2025 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [53242d1ed3](https://linux-hardware.org/?probe=53242d1ed3) | Apr 10, 2025 |
| Apple         | MacBookPro8,2               | Notebook    | [cd7b47ea0a](https://linux-hardware.org/?probe=cd7b47ea0a) | Apr 10, 2025 |
| Dell          | G15 5515                    | Notebook    | [6ef6273956](https://linux-hardware.org/?probe=6ef6273956) | Apr 09, 2025 |
| HP            | ENVY 15 x360 PC             | Notebook    | [9ba27ba280](https://linux-hardware.org/?probe=9ba27ba280) | Apr 08, 2025 |
| HP            | OMEN Gaming Laptop 17-db... | Notebook    | [cf02aa8670](https://linux-hardware.org/?probe=cf02aa8670) | Apr 07, 2025 |
| HP            | Pavilion x2 Detachable      | Tablet      | [4388068dd5](https://linux-hardware.org/?probe=4388068dd5) | Apr 05, 2025 |
| Dell          | Latitude E6410              | Notebook    | [fd3fac39ae](https://linux-hardware.org/?probe=fd3fac39ae) | Apr 04, 2025 |
| MSI           | U90/U100                    | Notebook    | [5006e02c05](https://linux-hardware.org/?probe=5006e02c05) | Apr 03, 2025 |
| Medion        | S17405                      | Notebook    | [38a1f6ced0](https://linux-hardware.org/?probe=38a1f6ced0) | Apr 03, 2025 |
| HP            | ProBook 455 G3              | Notebook    | [1b2d9a76f8](https://linux-hardware.org/?probe=1b2d9a76f8) | Apr 02, 2025 |
| ASUSTek       | 1000HE                      | Notebook    | [e857ea0047](https://linux-hardware.org/?probe=e857ea0047) | Mar 30, 2025 |
| ASUSTek       | M2NPV-MX                    | Desktop     | [90f5be2e93](https://linux-hardware.org/?probe=90f5be2e93) | Mar 30, 2025 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [3bfa147a0f](https://linux-hardware.org/?probe=3bfa147a0f) | Mar 27, 2025 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [5ccf766297](https://linux-hardware.org/?probe=5ccf766297) | Mar 26, 2025 |
| Acer          | AO725                       | Notebook    | [8fa858fde1](https://linux-hardware.org/?probe=8fa858fde1) | Mar 25, 2025 |
| MSI           | B450 GAMING PLUS            | Desktop     | [c4dab6146d](https://linux-hardware.org/?probe=c4dab6146d) | Mar 24, 2025 |
| MSI           | B450 GAMING PLUS            | Desktop     | [1f74e0c8ba](https://linux-hardware.org/?probe=1f74e0c8ba) | Mar 24, 2025 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [f2f455142e](https://linux-hardware.org/?probe=f2f455142e) | Mar 22, 2025 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | Desktop     | [cc9f5754a1](https://linux-hardware.org/?probe=cc9f5754a1) | Mar 20, 2025 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [1cd4bf968d](https://linux-hardware.org/?probe=1cd4bf968d) | Mar 19, 2025 |
| Fujitsu       | D2990-A1 S26361-D2990-A1    | Desktop     | [103d102f1e](https://linux-hardware.org/?probe=103d102f1e) | Mar 18, 2025 |
| Lenovo        | ThinkPad L512 44444XG       | Notebook    | [c3086a05f4](https://linux-hardware.org/?probe=c3086a05f4) | Mar 18, 2025 |
| Medion        | MS-7646                     | Desktop     | [0761a423f4](https://linux-hardware.org/?probe=0761a423f4) | Mar 16, 2025 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [ee280b693e](https://linux-hardware.org/?probe=ee280b693e) | Mar 16, 2025 |
| Foxconn       | 2AB1                        | Desktop     | [702838a49f](https://linux-hardware.org/?probe=702838a49f) | Mar 15, 2025 |
| Medion        | MS-7646                     | Desktop     | [18ab07fe68](https://linux-hardware.org/?probe=18ab07fe68) | Mar 15, 2025 |
| Foxconn       | 2AB1                        | Desktop     | [76336c64bc](https://linux-hardware.org/?probe=76336c64bc) | Mar 14, 2025 |
| Dell          | Latitude E6540              | Notebook    | [8486d9062e](https://linux-hardware.org/?probe=8486d9062e) | Mar 14, 2025 |
| Dell          | Latitude E6440              | Notebook    | [59f2291974](https://linux-hardware.org/?probe=59f2291974) | Mar 13, 2025 |
| ASUSTek       | 1000H                       | Notebook    | [6921f09d8b](https://linux-hardware.org/?probe=6921f09d8b) | Mar 13, 2025 |
| AOpen         | D1001 C26361-D1001          | Desktop     | [d503542f14](https://linux-hardware.org/?probe=d503542f14) | Mar 11, 2025 |
| HP            | 18E5                        | Desktop     | [80a5f4f889](https://linux-hardware.org/?probe=80a5f4f889) | Mar 10, 2025 |
| HP            | ZBook 17 G3                 | Notebook    | [cb8bd65307](https://linux-hardware.org/?probe=cb8bd65307) | Mar 07, 2025 |
| ASUSTek       | 901                         | Notebook    | [fdafcbf1ec](https://linux-hardware.org/?probe=fdafcbf1ec) | Mar 05, 2025 |
| Acer          | TravelMate 7730G            | Notebook    | [664a0068ce](https://linux-hardware.org/?probe=664a0068ce) | Mar 04, 2025 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0c5131b0cc](https://linux-hardware.org/?probe=0c5131b0cc) | Mar 02, 2025 |
| Toshiba       | Satellite C55D-B            | Notebook    | [23dc9bb800](https://linux-hardware.org/?probe=23dc9bb800) | Feb 28, 2025 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [cfcb0472cc](https://linux-hardware.org/?probe=cfcb0472cc) | Feb 28, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [70e7510bd3](https://linux-hardware.org/?probe=70e7510bd3) | Feb 28, 2025 |
| MSI           | H270-A PRO                  | Desktop     | [71d5c84d53](https://linux-hardware.org/?probe=71d5c84d53) | Feb 27, 2025 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [962b747fcb](https://linux-hardware.org/?probe=962b747fcb) | Feb 26, 2025 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [6762a384d2](https://linux-hardware.org/?probe=6762a384d2) | Feb 24, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [b476447887](https://linux-hardware.org/?probe=b476447887) | Feb 23, 2025 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [1846658f0c](https://linux-hardware.org/?probe=1846658f0c) | Feb 22, 2025 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [00d1da3042](https://linux-hardware.org/?probe=00d1da3042) | Feb 22, 2025 |
| Foxconn       | 2AB1                        | Desktop     | [9374b1af24](https://linux-hardware.org/?probe=9374b1af24) | Feb 22, 2025 |
| Pegatron      | E66                         | Desktop     | [638ddb76ea](https://linux-hardware.org/?probe=638ddb76ea) | Feb 21, 2025 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [933a486ebf](https://linux-hardware.org/?probe=933a486ebf) | Feb 21, 2025 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [9226357bd6](https://linux-hardware.org/?probe=9226357bd6) | Feb 21, 2025 |
| Intel         | DX58SO AAE29331-504         | Desktop     | [82a0e2a19f](https://linux-hardware.org/?probe=82a0e2a19f) | Feb 21, 2025 |
| Lenovo        | ThinkPad T420 4180A32       | Notebook    | [3fe648af90](https://linux-hardware.org/?probe=3fe648af90) | Feb 19, 2025 |
| Dell          | Inspiron 5558               | Notebook    | [ac45242025](https://linux-hardware.org/?probe=ac45242025) | Feb 17, 2025 |
| Panasonic     | CFSV1-2                     | Notebook    | [962d1504f0](https://linux-hardware.org/?probe=962d1504f0) | Feb 16, 2025 |
| Shenzhen D... | MP100                       | Desktop     | [cfa8b4b798](https://linux-hardware.org/?probe=cfa8b4b798) | Feb 15, 2025 |
| Shenzhen D... | MP100                       | Desktop     | [d725129d0f](https://linux-hardware.org/?probe=d725129d0f) | Feb 15, 2025 |
| Acer          | Aspire E1-731               | Notebook    | [d84936954c](https://linux-hardware.org/?probe=d84936954c) | Feb 14, 2025 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [48a13d7830](https://linux-hardware.org/?probe=48a13d7830) | Feb 14, 2025 |
| Dell          | Latitude D630               | Notebook    | [8a27773bce](https://linux-hardware.org/?probe=8a27773bce) | Feb 13, 2025 |
| Dell          | Latitude E6400              | Notebook    | [857964a35f](https://linux-hardware.org/?probe=857964a35f) | Feb 10, 2025 |
| Google        | Phaser360                   | Notebook    | [b261235d72](https://linux-hardware.org/?probe=b261235d72) | Feb 09, 2025 |
| Dell          | Latitude 5420               | Notebook    | [6a6ade61a2](https://linux-hardware.org/?probe=6a6ade61a2) | Feb 08, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [3db8c7f29d](https://linux-hardware.org/?probe=3db8c7f29d) | Feb 07, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [58b815cbda](https://linux-hardware.org/?probe=58b815cbda) | Feb 05, 2025 |
| Dell          | Inspiron MP061              | Notebook    | [b995685a87](https://linux-hardware.org/?probe=b995685a87) | Feb 03, 2025 |
| Dell          | Inspiron MP061              | Notebook    | [ff7bdb9ff5](https://linux-hardware.org/?probe=ff7bdb9ff5) | Feb 03, 2025 |
| MSI           | Katana 15 B13VFK            | Notebook    | [f63c2b237e](https://linux-hardware.org/?probe=f63c2b237e) | Feb 03, 2025 |
| Toshiba       | Satellite P500              | Notebook    | [b0a9517f32](https://linux-hardware.org/?probe=b0a9517f32) | Feb 03, 2025 |
| MSI           | V563610921-P5A-36964646-... | Desktop     | [0be5f69a3f](https://linux-hardware.org/?probe=0be5f69a3f) | Feb 02, 2025 |
| ASUSTek       | G16CHR                      | Desktop     | [951c844f51](https://linux-hardware.org/?probe=951c844f51) | Jan 31, 2025 |
| ASUSTek       | G16CHR                      | Desktop     | [d17f1249f5](https://linux-hardware.org/?probe=d17f1249f5) | Jan 31, 2025 |
| ASRock        | Z77 Pro3                    | Desktop     | [7ded8f457b](https://linux-hardware.org/?probe=7ded8f457b) | Jan 29, 2025 |
| Dell          | Latitude E6540              | Notebook    | [b0066afe40](https://linux-hardware.org/?probe=b0066afe40) | Jan 28, 2025 |
| Dell          | Latitude E6540              | Notebook    | [24e4f652f2](https://linux-hardware.org/?probe=24e4f652f2) | Jan 28, 2025 |
| Dell          | Latitude E6540              | Notebook    | [6abfa647ce](https://linux-hardware.org/?probe=6abfa647ce) | Jan 28, 2025 |
| Dell          | Precision 5540              | Notebook    | [51f95532d7](https://linux-hardware.org/?probe=51f95532d7) | Jan 26, 2025 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [e48900314b](https://linux-hardware.org/?probe=e48900314b) | Jan 26, 2025 |
| HP            | Stream x360 Convertible ... | Convertible | [e6dfeb5659](https://linux-hardware.org/?probe=e6dfeb5659) | Jan 26, 2025 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [8d0c94654d](https://linux-hardware.org/?probe=8d0c94654d) | Jan 26, 2025 |
| Biostar       | H81MHV3                     | Desktop     | [7b83c9e94b](https://linux-hardware.org/?probe=7b83c9e94b) | Jan 25, 2025 |
| Lenovo        | ThinkBook 16 G7 IML 21MS    | Notebook    | [05534db00b](https://linux-hardware.org/?probe=05534db00b) | Jan 24, 2025 |
| Lenovo        | ThinkBook 16 G7 IML 21MS    | Notebook    | [5d9ad551c5](https://linux-hardware.org/?probe=5d9ad551c5) | Jan 24, 2025 |
| HP            | 18E5                        | Desktop     | [ad19b3112b](https://linux-hardware.org/?probe=ad19b3112b) | Jan 23, 2025 |
| HP            | 255 G8 Notebook PC          | Notebook    | [fb7ea03b75](https://linux-hardware.org/?probe=fb7ea03b75) | Jan 23, 2025 |
| HP            | Compaq nc6320 (RU397EA#A... | Notebook    | [d55491d0da](https://linux-hardware.org/?probe=d55491d0da) | Jan 21, 2025 |
| Dell          | Studio 1555                 | Notebook    | [07d75f559e](https://linux-hardware.org/?probe=07d75f559e) | Jan 21, 2025 |
| Dell          | Studio 1555                 | Notebook    | [e54000b052](https://linux-hardware.org/?probe=e54000b052) | Jan 20, 2025 |
| Dell          | Latitude 5520               | Notebook    | [0a05270d35](https://linux-hardware.org/?probe=0a05270d35) | Jan 19, 2025 |
| HP            | 339A                        | Desktop     | [415c6f86df](https://linux-hardware.org/?probe=415c6f86df) | Jan 18, 2025 |
| MSI           | PRO X670-P WIFI             | Desktop     | [89a9d7da3e](https://linux-hardware.org/?probe=89a9d7da3e) | Jan 17, 2025 |
| Medion        | Akoya S2218 MD99590         | Notebook    | [d880b99a80](https://linux-hardware.org/?probe=d880b99a80) | Jan 16, 2025 |
| GRT           | H90                         | Mini pc     | [71c5d07ace](https://linux-hardware.org/?probe=71c5d07ace) | Jan 16, 2025 |
| Medion        | E15223                      | Notebook    | [664bb6cdac](https://linux-hardware.org/?probe=664bb6cdac) | Jan 15, 2025 |
| Unknown       | Unknown                     | Desktop     | [8d647549f4](https://linux-hardware.org/?probe=8d647549f4) | Jan 15, 2025 |
| Unknown       | Unknown                     | Desktop     | [c3d2f04421](https://linux-hardware.org/?probe=c3d2f04421) | Jan 15, 2025 |
| Lenovo        | ThinkPad X131e 3374A14      | Notebook    | [6d9233d064](https://linux-hardware.org/?probe=6d9233d064) | Jan 13, 2025 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [ebb71a3732](https://linux-hardware.org/?probe=ebb71a3732) | Jan 13, 2025 |
| AZW           | GTi14 V1.0                  | Mini pc     | [63d7c0e280](https://linux-hardware.org/?probe=63d7c0e280) | Jan 10, 2025 |
| Dell          | Inspiron 7537               | Notebook    | [c26bacf658](https://linux-hardware.org/?probe=c26bacf658) | Jan 09, 2025 |
| Dell          | Inspiron 7537               | Notebook    | [02a7b74d49](https://linux-hardware.org/?probe=02a7b74d49) | Jan 09, 2025 |
| HP            | HDX18                       | Notebook    | [5036eb4ddb](https://linux-hardware.org/?probe=5036eb4ddb) | Jan 09, 2025 |
| Acer          | One S1003                   | Tablet      | [f69caecc6f](https://linux-hardware.org/?probe=f69caecc6f) | Jan 09, 2025 |
| Dell          | Inspiron 7586               | Convertible | [3576ce0827](https://linux-hardware.org/?probe=3576ce0827) | Jan 08, 2025 |
| Unknown       | V00                         | Mini pc     | [0e6b34abd0](https://linux-hardware.org/?probe=0e6b34abd0) | Jan 08, 2025 |
| Unknown       | V00                         | Mini pc     | [6aff6f04b7](https://linux-hardware.org/?probe=6aff6f04b7) | Jan 07, 2025 |
| Dell          | XPS 15 9570                 | Notebook    | [66adacf460](https://linux-hardware.org/?probe=66adacf460) | Jan 07, 2025 |
| Dell          | XPS 15 9570                 | Notebook    | [1faaaf8a62](https://linux-hardware.org/?probe=1faaaf8a62) | Jan 06, 2025 |
| Biostar       | H81MHV3                     | Desktop     | [d03cc0092f](https://linux-hardware.org/?probe=d03cc0092f) | Jan 05, 2025 |
| MSI           | B250M BAZOOKA               | Desktop     | [30ef92bbfc](https://linux-hardware.org/?probe=30ef92bbfc) | Jan 05, 2025 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [a322d502b8](https://linux-hardware.org/?probe=a322d502b8) | Jan 05, 2025 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [315981955a](https://linux-hardware.org/?probe=315981955a) | Jan 03, 2025 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [118b96c4df](https://linux-hardware.org/?probe=118b96c4df) | Jan 03, 2025 |
| Dell          | Latitude 5590               | Notebook    | [ac8442c3af](https://linux-hardware.org/?probe=ac8442c3af) | Jan 01, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [cb43939fff](https://linux-hardware.org/?probe=cb43939fff) | Jan 01, 2025 |
| Sony          | VGN-FZ11M                   | Notebook    | [25ec238dec](https://linux-hardware.org/?probe=25ec238dec) | Dec 31, 2024 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [9494acd014](https://linux-hardware.org/?probe=9494acd014) | Dec 31, 2024 |
| Shenzhen D... | MP100                       | Desktop     | [ed4c3517e1](https://linux-hardware.org/?probe=ed4c3517e1) | Dec 31, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b71ec4b1e6](https://linux-hardware.org/?probe=b71ec4b1e6) | Dec 31, 2024 |
| Lenovo        | ThinkPad E570 20H5S0CF00    | Notebook    | [1b1018c49e](https://linux-hardware.org/?probe=1b1018c49e) | Dec 30, 2024 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [4825814497](https://linux-hardware.org/?probe=4825814497) | Dec 28, 2024 |
| Dell          | Latitude E7450              | Notebook    | [6677188d5d](https://linux-hardware.org/?probe=6677188d5d) | Dec 27, 2024 |
| Toshiba       | Satellite P870              | Notebook    | [a0e62c769c](https://linux-hardware.org/?probe=a0e62c769c) | Dec 24, 2024 |
| Toshiba       | Satellite P870              | Notebook    | [17c3c89a60](https://linux-hardware.org/?probe=17c3c89a60) | Dec 23, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [2bb943950c](https://linux-hardware.org/?probe=2bb943950c) | Dec 23, 2024 |
| Dell          | Latitude E6440              | Notebook    | [8ef2131731](https://linux-hardware.org/?probe=8ef2131731) | Dec 23, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | Notebook    | [117beaf6ca](https://linux-hardware.org/?probe=117beaf6ca) | Dec 22, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [80af2d46c0](https://linux-hardware.org/?probe=80af2d46c0) | Dec 21, 2024 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e052122061](https://linux-hardware.org/?probe=e052122061) | Dec 20, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [fb6b122d69](https://linux-hardware.org/?probe=fb6b122d69) | Dec 19, 2024 |
| Dell          | 0P4T42 A01                  | All in one  | [aad8987195](https://linux-hardware.org/?probe=aad8987195) | Dec 19, 2024 |
| MSI           | H61M-P20                    | Desktop     | [f15424c030](https://linux-hardware.org/?probe=f15424c030) | Dec 19, 2024 |
| Dell          | Latitude E5570              | Notebook    | [54e9a1a0b3](https://linux-hardware.org/?probe=54e9a1a0b3) | Dec 17, 2024 |
| Dell          | Inspiron 7786               | Convertible | [5fac427a17](https://linux-hardware.org/?probe=5fac427a17) | Dec 16, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [57042541c4](https://linux-hardware.org/?probe=57042541c4) | Dec 15, 2024 |
| HP            | EliteBook 840 G3            | Notebook    | [dc74fc85f6](https://linux-hardware.org/?probe=dc74fc85f6) | Dec 14, 2024 |
| AZW           | GTi14 V1.0                  | Mini pc     | [28e079a0db](https://linux-hardware.org/?probe=28e079a0db) | Dec 12, 2024 |
| youyeetoo     | X1 SBC                      | Notebook    | [1abafad3a5](https://linux-hardware.org/?probe=1abafad3a5) | Dec 12, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [1a8a388009](https://linux-hardware.org/?probe=1a8a388009) | Dec 11, 2024 |
| GRT           | H90                         | Mini pc     | [6f862e4d32](https://linux-hardware.org/?probe=6f862e4d32) | Dec 11, 2024 |
| AZW           | GTi14 V1.0                  | Mini pc     | [62bb9a9c3b](https://linux-hardware.org/?probe=62bb9a9c3b) | Dec 10, 2024 |
| ASUSTek       | F5V                         | Notebook    | [fc57564f87](https://linux-hardware.org/?probe=fc57564f87) | Dec 09, 2024 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [00c881af99](https://linux-hardware.org/?probe=00c881af99) | Dec 09, 2024 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a669b03a47](https://linux-hardware.org/?probe=a669b03a47) | Dec 08, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b5d4c3caa9](https://linux-hardware.org/?probe=b5d4c3caa9) | Dec 02, 2024 |
| Dell          | 0G17RR A00                  | All in one  | [384d13d228](https://linux-hardware.org/?probe=384d13d228) | Dec 01, 2024 |
| Dell          | 0G17RR A00                  | All in one  | [01ec6d486a](https://linux-hardware.org/?probe=01ec6d486a) | Dec 01, 2024 |
| ASRock        | Z390 Phantom Gaming 9       | Desktop     | [6573a24594](https://linux-hardware.org/?probe=6573a24594) | Dec 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [32ae181590](https://linux-hardware.org/?probe=32ae181590) | Dec 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MMS... | Notebook    | [cf0dcbdaff](https://linux-hardware.org/?probe=cf0dcbdaff) | Nov 30, 2024 |
| HP            | 255 G1                      | Notebook    | [0dd46cadda](https://linux-hardware.org/?probe=0dd46cadda) | Nov 29, 2024 |
| Dell          | 0DR845                      | Desktop     | [1b6afa334f](https://linux-hardware.org/?probe=1b6afa334f) | Nov 29, 2024 |
| GRT           | H90                         | Mini pc     | [074a205d8a](https://linux-hardware.org/?probe=074a205d8a) | Nov 29, 2024 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [b671dd7405](https://linux-hardware.org/?probe=b671dd7405) | Nov 26, 2024 |
| Acer          | Swift SF314-57              | Notebook    | [fc0d1a098a](https://linux-hardware.org/?probe=fc0d1a098a) | Nov 25, 2024 |
| Lenovo        | ThinkPad T440p 20AWA0N5R... | Notebook    | [af6d253f42](https://linux-hardware.org/?probe=af6d253f42) | Nov 25, 2024 |
| Lenovo        | 3148 SDK0J40700 WIN 3258... | Desktop     | [10abdf7972](https://linux-hardware.org/?probe=10abdf7972) | Nov 24, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b2bdca3443](https://linux-hardware.org/?probe=b2bdca3443) | Nov 20, 2024 |
| Lenovo        | ThinkPad Z61m 94529JG       | Notebook    | [2b158c1a28](https://linux-hardware.org/?probe=2b158c1a28) | Nov 19, 2024 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [4b5de9a37a](https://linux-hardware.org/?probe=4b5de9a37a) | Nov 19, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [065b59e739](https://linux-hardware.org/?probe=065b59e739) | Nov 18, 2024 |
| Toshiba       | Satellite C55D-B            | Notebook    | [7c3fb96c09](https://linux-hardware.org/?probe=7c3fb96c09) | Nov 18, 2024 |
| Lenovo        | 3000 N200 0769BLG           | Notebook    | [d58726bb7b](https://linux-hardware.org/?probe=d58726bb7b) | Nov 18, 2024 |
| Insyde        | M1106BAP                    | Notebook    | [cad9f73269](https://linux-hardware.org/?probe=cad9f73269) | Nov 18, 2024 |
| Acer          | Aspire A515-54G             | Notebook    | [3b287d26d3](https://linux-hardware.org/?probe=3b287d26d3) | Nov 17, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [190740e091](https://linux-hardware.org/?probe=190740e091) | Nov 16, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [8cf19c813b](https://linux-hardware.org/?probe=8cf19c813b) | Nov 16, 2024 |
| Lenovo        | 3000 N200 0769BLG           | Notebook    | [60ef264f93](https://linux-hardware.org/?probe=60ef264f93) | Nov 16, 2024 |
| Dell          | 073MMW A03                  | Desktop     | [f7d046b276](https://linux-hardware.org/?probe=f7d046b276) | Nov 15, 2024 |
| ASRock        | A75M-HVS                    | Desktop     | [71e383d168](https://linux-hardware.org/?probe=71e383d168) | Nov 14, 2024 |
| SYS           | H310CH5-TI2                 | Desktop     | [8d26063a45](https://linux-hardware.org/?probe=8d26063a45) | Nov 13, 2024 |
| HP            | ENVY m7 Notebook            | Notebook    | [d38f15b4c6](https://linux-hardware.org/?probe=d38f15b4c6) | Nov 13, 2024 |
| HP            | 829D                        | Desktop     | [bbd6f07955](https://linux-hardware.org/?probe=bbd6f07955) | Nov 08, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0f2501a96e](https://linux-hardware.org/?probe=0f2501a96e) | Nov 07, 2024 |
| HP            | 829D                        | Desktop     | [ce428beb45](https://linux-hardware.org/?probe=ce428beb45) | Nov 07, 2024 |
| HP            | 8265                        | Desktop     | [91d18e37fc](https://linux-hardware.org/?probe=91d18e37fc) | Nov 07, 2024 |
| Samsung       | 935QDC                      | Convertible | [d6a39bed87](https://linux-hardware.org/?probe=d6a39bed87) | Nov 05, 2024 |
| Acer          | Aspire 5750G                | Notebook    | [554b0591cd](https://linux-hardware.org/?probe=554b0591cd) | Nov 05, 2024 |
| Lenovo        | ThinkCentre M71e 3129B2G    | Desktop     | [0f3c377fbc](https://linux-hardware.org/?probe=0f3c377fbc) | Nov 03, 2024 |
| Dell          | Latitude E6440              | Notebook    | [04241680ab](https://linux-hardware.org/?probe=04241680ab) | Nov 03, 2024 |
| Dell          | Latitude E6440              | Notebook    | [651d5b49ad](https://linux-hardware.org/?probe=651d5b49ad) | Nov 03, 2024 |
| HP            | ProBook 645 G2              | Notebook    | [07452965ae](https://linux-hardware.org/?probe=07452965ae) | Nov 01, 2024 |
| Gateway       | ZX4351                      | All in one  | [c98e028454](https://linux-hardware.org/?probe=c98e028454) | Nov 01, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2aaad8cdd1](https://linux-hardware.org/?probe=2aaad8cdd1) | Nov 01, 2024 |
| HP            | ProBook 645 G2              | Notebook    | [9f82b3c340](https://linux-hardware.org/?probe=9f82b3c340) | Oct 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [b73f669319](https://linux-hardware.org/?probe=b73f669319) | Oct 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [aabc0b8d5c](https://linux-hardware.org/?probe=aabc0b8d5c) | Oct 31, 2024 |
| Acer          | Aspire Lite AL15-52         | Notebook    | [fe9498f7a0](https://linux-hardware.org/?probe=fe9498f7a0) | Oct 29, 2024 |
| HP            | Casablanca H710             | Notebook    | [f80673dbdc](https://linux-hardware.org/?probe=f80673dbdc) | Oct 28, 2024 |
| Apple         | MacBookAir1,1               | Notebook    | [3cf79323fc](https://linux-hardware.org/?probe=3cf79323fc) | Oct 28, 2024 |
| Acer          | Aspire XC-605               | Desktop     | [5b81ea0b2c](https://linux-hardware.org/?probe=5b81ea0b2c) | Oct 27, 2024 |
| Samsung       | DeskTop System              | Desktop     | [ca4fa68a45](https://linux-hardware.org/?probe=ca4fa68a45) | Oct 27, 2024 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [8171ac365f](https://linux-hardware.org/?probe=8171ac365f) | Oct 27, 2024 |
| Intel         | H61                         | Desktop     | [8460791859](https://linux-hardware.org/?probe=8460791859) | Oct 27, 2024 |
| Lenovo        | ThinkPad E470 20H1002FLM    | Notebook    | [7f9f628051](https://linux-hardware.org/?probe=7f9f628051) | Oct 25, 2024 |
| HP            | Pavilion g6                 | Notebook    | [b9c9cc3f65](https://linux-hardware.org/?probe=b9c9cc3f65) | Oct 25, 2024 |
| HP            | Pavilion g6                 | Notebook    | [76ff4ae74d](https://linux-hardware.org/?probe=76ff4ae74d) | Oct 25, 2024 |
| Gigabyte      | P35-S3G                     | Desktop     | [c38dd7e7f6](https://linux-hardware.org/?probe=c38dd7e7f6) | Oct 24, 2024 |
| Gigabyte      | P35-S3G                     | Desktop     | [fc78d0d762](https://linux-hardware.org/?probe=fc78d0d762) | Oct 24, 2024 |
| HP            | Laptop 15-dy5xxx            | Notebook    | [c030729a0e](https://linux-hardware.org/?probe=c030729a0e) | Oct 24, 2024 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [4232854445](https://linux-hardware.org/?probe=4232854445) | Oct 23, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [26585357e5](https://linux-hardware.org/?probe=26585357e5) | Oct 21, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [7ae8bf79b4](https://linux-hardware.org/?probe=7ae8bf79b4) | Oct 21, 2024 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | Desktop     | [9644c911da](https://linux-hardware.org/?probe=9644c911da) | Oct 18, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [082fa9dd81](https://linux-hardware.org/?probe=082fa9dd81) | Oct 17, 2024 |
| ASRock        | Z370 Pro4                   | Desktop     | [768bfdaf9a](https://linux-hardware.org/?probe=768bfdaf9a) | Oct 17, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [f977e8a7ce](https://linux-hardware.org/?probe=f977e8a7ce) | Oct 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [423cf5f3bd](https://linux-hardware.org/?probe=423cf5f3bd) | Oct 16, 2024 |
| MSI           | H110M PRO-VD                | Desktop     | [cc09ec8aa4](https://linux-hardware.org/?probe=cc09ec8aa4) | Oct 16, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bc9f2b478b](https://linux-hardware.org/?probe=bc9f2b478b) | Oct 14, 2024 |
| HP            | 655                         | Notebook    | [44bcea3de2](https://linux-hardware.org/?probe=44bcea3de2) | Oct 14, 2024 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [e0bf2cc58a](https://linux-hardware.org/?probe=e0bf2cc58a) | Oct 13, 2024 |
| Dell          | Latitude E6430              | Notebook    | [bdebcd33a6](https://linux-hardware.org/?probe=bdebcd33a6) | Oct 12, 2024 |
| Framework     | Laptop                      | Notebook    | [ba5a1a5bfc](https://linux-hardware.org/?probe=ba5a1a5bfc) | Oct 11, 2024 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4747b9f85b](https://linux-hardware.org/?probe=4747b9f85b) | Oct 10, 2024 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [8c8eabd7b6](https://linux-hardware.org/?probe=8c8eabd7b6) | Oct 10, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [292332c812](https://linux-hardware.org/?probe=292332c812) | Oct 08, 2024 |
| Acer          | Aspire 5738                 | Notebook    | [946c78abb8](https://linux-hardware.org/?probe=946c78abb8) | Oct 07, 2024 |
| HP            | 86EE                        | All in one  | [b60cb3ba3d](https://linux-hardware.org/?probe=b60cb3ba3d) | Oct 07, 2024 |
| HP            | ProLiant DL360 G7           | Server      | [7926b0dc7f](https://linux-hardware.org/?probe=7926b0dc7f) | Oct 05, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [b373b972bf](https://linux-hardware.org/?probe=b373b972bf) | Oct 03, 2024 |
| HP            | ProBook 645 G2              | Notebook    | [07e2717694](https://linux-hardware.org/?probe=07e2717694) | Oct 02, 2024 |
| Medion        | E2215T MD60285              | Notebook    | [a3f12e9645](https://linux-hardware.org/?probe=a3f12e9645) | Oct 01, 2024 |
| MSI           | Prestige 16 AI Evo B1MG     | Notebook    | [e44bc0da2c](https://linux-hardware.org/?probe=e44bc0da2c) | Oct 01, 2024 |
| Lenovo        | ThinkPad T410 2522E34       | Notebook    | [22aef19581](https://linux-hardware.org/?probe=22aef19581) | Sep 30, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [6526213a5a](https://linux-hardware.org/?probe=6526213a5a) | Sep 30, 2024 |
| Dell          | 0P096C A00                  | Desktop     | [e67dbd9311](https://linux-hardware.org/?probe=e67dbd9311) | Sep 29, 2024 |
| HP            | 0A5Ch                       | Desktop     | [c1d6e5486d](https://linux-hardware.org/?probe=c1d6e5486d) | Sep 29, 2024 |
| Intel         | H110D4-P1                   | Desktop     | [626cc0fd13](https://linux-hardware.org/?probe=626cc0fd13) | Sep 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [1c28596af0](https://linux-hardware.org/?probe=1c28596af0) | Sep 28, 2024 |
| TECNO Mobi... | MEGABOOK T14TA              | Notebook    | [f42a3c6797](https://linux-hardware.org/?probe=f42a3c6797) | Sep 28, 2024 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [2b9c6f05fe](https://linux-hardware.org/?probe=2b9c6f05fe) | Sep 28, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [2591c32e72](https://linux-hardware.org/?probe=2591c32e72) | Sep 27, 2024 |
| Unknown       | Unknown                     | Mini pc     | [10786fdad1](https://linux-hardware.org/?probe=10786fdad1) | Sep 27, 2024 |
| Dell          | Latitude 7490               | Notebook    | [4fc1fc2d86](https://linux-hardware.org/?probe=4fc1fc2d86) | Sep 27, 2024 |
| Samsung       | 730U3E/740U3E               | Notebook    | [82cb5ef24c](https://linux-hardware.org/?probe=82cb5ef24c) | Sep 25, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [a8db3428c3](https://linux-hardware.org/?probe=a8db3428c3) | Sep 25, 2024 |
| HP            | Pavilion g6                 | Notebook    | [e4085b23eb](https://linux-hardware.org/?probe=e4085b23eb) | Sep 24, 2024 |
| Intel         | B75                         | Desktop     | [17dd91b6f2](https://linux-hardware.org/?probe=17dd91b6f2) | Sep 24, 2024 |
| HP            | Pavilion 17                 | Notebook    | [6d532316c9](https://linux-hardware.org/?probe=6d532316c9) | Sep 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [ae73de44a9](https://linux-hardware.org/?probe=ae73de44a9) | Sep 22, 2024 |
| Dell          | System XPS L702X            | Notebook    | [d2662fe6a6](https://linux-hardware.org/?probe=d2662fe6a6) | Sep 20, 2024 |
| Gigabyte      | B450M H                     | Desktop     | [be59e2f196](https://linux-hardware.org/?probe=be59e2f196) | Sep 20, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [2d03646368](https://linux-hardware.org/?probe=2d03646368) | Sep 17, 2024 |
| MSI           | A78-G41 PC Mate             | Desktop     | [941b873461](https://linux-hardware.org/?probe=941b873461) | Sep 16, 2024 |
| MSI           | A78-G41 PC Mate             | Desktop     | [5cb76e009d](https://linux-hardware.org/?probe=5cb76e009d) | Sep 16, 2024 |
| Acer          | Aspire A515-47              | Notebook    | [bf14576006](https://linux-hardware.org/?probe=bf14576006) | Sep 16, 2024 |
| Lenovo        | ThinkPad T410 2522G18       | Notebook    | [1165597d26](https://linux-hardware.org/?probe=1165597d26) | Sep 16, 2024 |
| System76      | Serval WS                   | Notebook    | [0da8d49168](https://linux-hardware.org/?probe=0da8d49168) | Sep 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b105d16e70](https://linux-hardware.org/?probe=b105d16e70) | Sep 13, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [f8dd4f91b9](https://linux-hardware.org/?probe=f8dd4f91b9) | Sep 12, 2024 |
| ASRock        | Z490 Steel Legend           | Desktop     | [ea538bf56c](https://linux-hardware.org/?probe=ea538bf56c) | Sep 12, 2024 |
| Inter Sale... | NID-11125DE                 | Notebook    | [5f0390c58c](https://linux-hardware.org/?probe=5f0390c58c) | Sep 12, 2024 |
| Dell          | 0JYH5J A00                  | All in one  | [b1a24dcb7c](https://linux-hardware.org/?probe=b1a24dcb7c) | Sep 11, 2024 |
| HP            | Pavilion dv7                | Notebook    | [871aaa0215](https://linux-hardware.org/?probe=871aaa0215) | Sep 11, 2024 |
| HP            | Pavilion dv7                | Notebook    | [af8ba6a16b](https://linux-hardware.org/?probe=af8ba6a16b) | Sep 11, 2024 |
| Dell          | Latitude 7300               | Notebook    | [e7bf6cf5d8](https://linux-hardware.org/?probe=e7bf6cf5d8) | Sep 06, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [fbffd2655c](https://linux-hardware.org/?probe=fbffd2655c) | Sep 05, 2024 |
| Acer          | RS880M05                    | Desktop     | [4998887624](https://linux-hardware.org/?probe=4998887624) | Sep 03, 2024 |
| Acer          | RS880M05                    | Desktop     | [e421cfccdf](https://linux-hardware.org/?probe=e421cfccdf) | Sep 03, 2024 |
| HP            | Notebook                    | Notebook    | [4074a83837](https://linux-hardware.org/?probe=4074a83837) | Sep 01, 2024 |
| Gigabyte      | GB-BSi5-1135G7              | Desktop     | [24c103a266](https://linux-hardware.org/?probe=24c103a266) | Aug 31, 2024 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [ce81460fc8](https://linux-hardware.org/?probe=ce81460fc8) | Aug 31, 2024 |
| Dell          | 0RF703                      | Desktop     | [e82a1ff8e3](https://linux-hardware.org/?probe=e82a1ff8e3) | Aug 29, 2024 |
| Dell          | System XPS 15Z              | Notebook    | [64925b60e9](https://linux-hardware.org/?probe=64925b60e9) | Aug 29, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [23e6c52258](https://linux-hardware.org/?probe=23e6c52258) | Aug 29, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [02c479ee0f](https://linux-hardware.org/?probe=02c479ee0f) | Aug 27, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [d4b46af5cb](https://linux-hardware.org/?probe=d4b46af5cb) | Aug 27, 2024 |
| Unknown       | AX16Pro                     | Notebook    | [091e76b6ed](https://linux-hardware.org/?probe=091e76b6ed) | Aug 27, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [c539073766](https://linux-hardware.org/?probe=c539073766) | Aug 25, 2024 |
| Lenovo        | B550 20053                  | Notebook    | [d7a362e8ae](https://linux-hardware.org/?probe=d7a362e8ae) | Aug 25, 2024 |
| HP            | 82F1                        | Desktop     | [5bd98b8749](https://linux-hardware.org/?probe=5bd98b8749) | Aug 25, 2024 |
| HP            | 82F1                        | Desktop     | [1dcd4be378](https://linux-hardware.org/?probe=1dcd4be378) | Aug 25, 2024 |
| HP            | Notebook                    | Notebook    | [51aefbbe02](https://linux-hardware.org/?probe=51aefbbe02) | Aug 24, 2024 |
| Dell          | Inspiron 15 3511            | Notebook    | [e9389eeab0](https://linux-hardware.org/?probe=e9389eeab0) | Aug 24, 2024 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [fe852bd498](https://linux-hardware.org/?probe=fe852bd498) | Aug 22, 2024 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [5dd0130b6b](https://linux-hardware.org/?probe=5dd0130b6b) | Aug 21, 2024 |
| AZW           | EQ13                        | Mini pc     | [1f081f6ae3](https://linux-hardware.org/?probe=1f081f6ae3) | Aug 20, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [561ce191e0](https://linux-hardware.org/?probe=561ce191e0) | Aug 19, 2024 |
| Dell          | XPS 15 9570                 | Notebook    | [6011f4954b](https://linux-hardware.org/?probe=6011f4954b) | Aug 19, 2024 |
| MSI           | Vector 16 HX A14VHG         | Notebook    | [00d080c251](https://linux-hardware.org/?probe=00d080c251) | Aug 17, 2024 |
| Dell          | Latitude D430               | Notebook    | [4346500f96](https://linux-hardware.org/?probe=4346500f96) | Aug 16, 2024 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [9153a53950](https://linux-hardware.org/?probe=9153a53950) | Aug 16, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a34d40daeb](https://linux-hardware.org/?probe=a34d40daeb) | Aug 16, 2024 |
| Lenovo        | V17 G3 IAP 82U1             | Notebook    | [1b19bfdd9a](https://linux-hardware.org/?probe=1b19bfdd9a) | Aug 15, 2024 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [fe6038ad0d](https://linux-hardware.org/?probe=fe6038ad0d) | Aug 14, 2024 |
| Dell          | XPS 16 9640                 | Notebook    | [4c6475c28e](https://linux-hardware.org/?probe=4c6475c28e) | Aug 12, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f17d30bee1](https://linux-hardware.org/?probe=f17d30bee1) | Aug 10, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [49d572df1d](https://linux-hardware.org/?probe=49d572df1d) | Aug 10, 2024 |
| Acer          | TP-SW5-012P-18FQ            | Notebook    | [95f5359eb5](https://linux-hardware.org/?probe=95f5359eb5) | Aug 10, 2024 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [dc966fdca4](https://linux-hardware.org/?probe=dc966fdca4) | Aug 09, 2024 |
| HP            | 0A04h                       | Desktop     | [f476265afe](https://linux-hardware.org/?probe=f476265afe) | Aug 08, 2024 |
| Unknown       | E142                        | Notebook    | [9944efec2a](https://linux-hardware.org/?probe=9944efec2a) | Aug 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [a4f8eaf4bc](https://linux-hardware.org/?probe=a4f8eaf4bc) | Aug 07, 2024 |
| ASUSTek       | T100TA                      | Notebook    | [087ac815ec](https://linux-hardware.org/?probe=087ac815ec) | Aug 06, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [1771fdc95b](https://linux-hardware.org/?probe=1771fdc95b) | Aug 06, 2024 |
| ASUSTek       | P5Q-EM                      | Desktop     | [a4984bb698](https://linux-hardware.org/?probe=a4984bb698) | Aug 05, 2024 |
| ASUSTek       | ROG Flow X13 GV302XU_GV3... | Convertible | [3d75c97eb7](https://linux-hardware.org/?probe=3d75c97eb7) | Aug 04, 2024 |
| Microsoft     | Surface Pro 9               | Tablet      | [ddc89e68c4](https://linux-hardware.org/?probe=ddc89e68c4) | Aug 02, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6903ed9a06](https://linux-hardware.org/?probe=6903ed9a06) | Aug 02, 2024 |
| Lenovo        | ThinkPad 10 20C3S0HJ00      | Tablet      | [fbdcd41333](https://linux-hardware.org/?probe=fbdcd41333) | Jul 30, 2024 |
| Acer          | Aspire A515-47              | Notebook    | [7e28f24801](https://linux-hardware.org/?probe=7e28f24801) | Jul 30, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [49a9d6c2e4](https://linux-hardware.org/?probe=49a9d6c2e4) | Jul 30, 2024 |
| GEEKOM        | Mini IT13                   | Desktop     | [23c5c50556](https://linux-hardware.org/?probe=23c5c50556) | Jul 27, 2024 |
| Lenovo        | 334A NOK                    | Mini pc     | [9e68c66366](https://linux-hardware.org/?probe=9e68c66366) | Jul 26, 2024 |
| Acer          | TP-SW5-012P-18FQ            | Notebook    | [0cd53c394b](https://linux-hardware.org/?probe=0cd53c394b) | Jul 26, 2024 |
| HP            | Compaq 6730s                | Notebook    | [2c89ca2d0d](https://linux-hardware.org/?probe=2c89ca2d0d) | Jul 25, 2024 |
| HP            | Compaq 6730s                | Notebook    | [5724e952f7](https://linux-hardware.org/?probe=5724e952f7) | Jul 25, 2024 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [01b1c8c6cc](https://linux-hardware.org/?probe=01b1c8c6cc) | Jul 24, 2024 |
| ASUSTek       | PU301LA                     | Notebook    | [4f9c3ff09f](https://linux-hardware.org/?probe=4f9c3ff09f) | Jul 23, 2024 |
| HP            | ProBook 455 G2              | Notebook    | [6e9b0d9256](https://linux-hardware.org/?probe=6e9b0d9256) | Jul 22, 2024 |
| Acer          | H610MHP-E                   | Desktop     | [54e0a6ed60](https://linux-hardware.org/?probe=54e0a6ed60) | Jul 22, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [0662223517](https://linux-hardware.org/?probe=0662223517) | Jul 22, 2024 |
| HP            | ENVY m7 Notebook            | Notebook    | [b9f143068f](https://linux-hardware.org/?probe=b9f143068f) | Jul 21, 2024 |
| Lenovo        | ThinkPad L480 20LS001AGE    | Notebook    | [797eae789c](https://linux-hardware.org/?probe=797eae789c) | Jul 21, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [345fc32f50](https://linux-hardware.org/?probe=345fc32f50) | Jul 21, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [768145912a](https://linux-hardware.org/?probe=768145912a) | Jul 20, 2024 |
| Lenovo        | ThinkCentre A58 75227SG     | Desktop     | [e8606d105c](https://linux-hardware.org/?probe=e8606d105c) | Jul 18, 2024 |
| Apple         | MacBookPro5,4               | Notebook    | [44267b835a](https://linux-hardware.org/?probe=44267b835a) | Jul 16, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [f0cc03e825](https://linux-hardware.org/?probe=f0cc03e825) | Jul 15, 2024 |
| HP            | 8266                        | Desktop     | [be8a065a36](https://linux-hardware.org/?probe=be8a065a36) | Jul 14, 2024 |
| Medion        | MS-7748                     | Desktop     | [3e7c4e1d43](https://linux-hardware.org/?probe=3e7c4e1d43) | Jul 14, 2024 |
| Lenovo        | ThinkPad T500 20552CU       | Notebook    | [587f2d66e0](https://linux-hardware.org/?probe=587f2d66e0) | Jul 12, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [dd1cfc0693](https://linux-hardware.org/?probe=dd1cfc0693) | Jul 11, 2024 |
| Acer          | Aspire 5538                 | Notebook    | [209e123c1e](https://linux-hardware.org/?probe=209e123c1e) | Jul 08, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [6a90ef0cd0](https://linux-hardware.org/?probe=6a90ef0cd0) | Jul 06, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [7dcaf9e889](https://linux-hardware.org/?probe=7dcaf9e889) | Jul 06, 2024 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [75ce86bf8e](https://linux-hardware.org/?probe=75ce86bf8e) | Jul 05, 2024 |
| Dell          | 0T656F A01                  | Desktop     | [ecdd487673](https://linux-hardware.org/?probe=ecdd487673) | Jul 05, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1f3c85da43](https://linux-hardware.org/?probe=1f3c85da43) | Jul 02, 2024 |
| Dell          | Latitude E5420              | Notebook    | [a140673eb6](https://linux-hardware.org/?probe=a140673eb6) | Jul 01, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [c54b7538dc](https://linux-hardware.org/?probe=c54b7538dc) | Jul 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [17c5c8cb74](https://linux-hardware.org/?probe=17c5c8cb74) | Jun 28, 2024 |
| Dell          | 0YY62T A00                  | Mini pc     | [e46328f6d3](https://linux-hardware.org/?probe=e46328f6d3) | Jun 27, 2024 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | Notebook    | [64ca53d3d0](https://linux-hardware.org/?probe=64ca53d3d0) | Jun 27, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a86fc2b197](https://linux-hardware.org/?probe=a86fc2b197) | Jun 27, 2024 |
| Samsung       | 960QGK                      | Convertible | [d7e98771ef](https://linux-hardware.org/?probe=d7e98771ef) | Jun 26, 2024 |
| ASUSTek       | NODUSM3                     | Desktop     | [4b8b2d0cb0](https://linux-hardware.org/?probe=4b8b2d0cb0) | Jun 25, 2024 |
| Razer         | Blade 18 - RZ09-0509        | Notebook    | [d0e4380367](https://linux-hardware.org/?probe=d0e4380367) | Jun 23, 2024 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | Desktop     | [3ba33c7694](https://linux-hardware.org/?probe=3ba33c7694) | Jun 23, 2024 |
| Fujitsu       | D3067-A1 S26361-D3067-A1    | Desktop     | [d88a3ae668](https://linux-hardware.org/?probe=d88a3ae668) | Jun 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c6bee0ad67](https://linux-hardware.org/?probe=c6bee0ad67) | Jun 23, 2024 |
| Lenovo        | ThinkPad T580 20LAS4KG0Q    | Notebook    | [9e222818ab](https://linux-hardware.org/?probe=9e222818ab) | Jun 22, 2024 |
| Lenovo        | ThinkPad T580 20LAS4KG0Q    | Notebook    | [d20044a0fc](https://linux-hardware.org/?probe=d20044a0fc) | Jun 22, 2024 |
| Acer          | Aspire ES1-572              | Notebook    | [3ed5118890](https://linux-hardware.org/?probe=3ed5118890) | Jun 21, 2024 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [8acebd9a23](https://linux-hardware.org/?probe=8acebd9a23) | Jun 20, 2024 |
| Lenovo        | Remore CRB Win8 STD MM D... | Desktop     | [26694fdf4c](https://linux-hardware.org/?probe=26694fdf4c) | Jun 15, 2024 |
| Dell          | XPS 14 9440                 | Notebook    | [b32c71b845](https://linux-hardware.org/?probe=b32c71b845) | Jun 14, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [386adc3726](https://linux-hardware.org/?probe=386adc3726) | Jun 13, 2024 |
| Dell          | Inspiron 7500 2n1 Black     | Convertible | [18eb7baa73](https://linux-hardware.org/?probe=18eb7baa73) | Jun 11, 2024 |
| Gigabyte      | A520M H                     | Desktop     | [4850d46dda](https://linux-hardware.org/?probe=4850d46dda) | Jun 11, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [8c44fcfe24](https://linux-hardware.org/?probe=8c44fcfe24) | Jun 08, 2024 |
| Dell          | Latitude 3190               | Notebook    | [931a3406c1](https://linux-hardware.org/?probe=931a3406c1) | Jun 06, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | Notebook    | [c823161b4d](https://linux-hardware.org/?probe=c823161b4d) | Jun 05, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | Notebook    | [bd5daadc8e](https://linux-hardware.org/?probe=bd5daadc8e) | Jun 05, 2024 |
| ASUSTek       | X205TA                      | Notebook    | [e39012d26d](https://linux-hardware.org/?probe=e39012d26d) | Jun 02, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [8e15f36c9e](https://linux-hardware.org/?probe=8e15f36c9e) | Jun 02, 2024 |
| Gigabyte      | A520M H                     | Desktop     | [199f375169](https://linux-hardware.org/?probe=199f375169) | Jun 01, 2024 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [56f7d22d21](https://linux-hardware.org/?probe=56f7d22d21) | May 31, 2024 |
| Dell          | Inspiron 5584               | Notebook    | [0d061a3e07](https://linux-hardware.org/?probe=0d061a3e07) | May 31, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a22a7ed64a](https://linux-hardware.org/?probe=a22a7ed64a) | May 30, 2024 |
| HP            | 620                         | Notebook    | [fc744613bf](https://linux-hardware.org/?probe=fc744613bf) | May 30, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [b1b2d6a841](https://linux-hardware.org/?probe=b1b2d6a841) | May 30, 2024 |
| ASUSTek       | A88XM-A                     | Desktop     | [4b9f7e6b3c](https://linux-hardware.org/?probe=4b9f7e6b3c) | May 29, 2024 |
| Acer          | Aspire ES1-533              | Notebook    | [f308e9468f](https://linux-hardware.org/?probe=f308e9468f) | May 29, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [5d9d51e2c4](https://linux-hardware.org/?probe=5d9d51e2c4) | May 28, 2024 |
| Medion        | Z370H4-EM                   | Desktop     | [144540334c](https://linux-hardware.org/?probe=144540334c) | May 28, 2024 |
| HP            | ENVY Notebook               | Notebook    | [525b25d9db](https://linux-hardware.org/?probe=525b25d9db) | May 28, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d5c083c4c6](https://linux-hardware.org/?probe=d5c083c4c6) | May 27, 2024 |
| Acer          | Aspire 8730                 | Notebook    | [9633277543](https://linux-hardware.org/?probe=9633277543) | May 27, 2024 |
| Dell          | Studio XPS 1645             | Notebook    | [e9eb7685bd](https://linux-hardware.org/?probe=e9eb7685bd) | May 27, 2024 |
| Medion        | Z370H4-EM                   | Desktop     | [e833e99cd2](https://linux-hardware.org/?probe=e833e99cd2) | May 26, 2024 |
| Dell          | Studio XPS 1645             | Notebook    | [d4926c0589](https://linux-hardware.org/?probe=d4926c0589) | May 26, 2024 |
| Acer          | Nitro N50-620               | Desktop     | [35d81006b0](https://linux-hardware.org/?probe=35d81006b0) | May 25, 2024 |
| Dell          | 042P49 A01                  | Desktop     | [9ef1b2b561](https://linux-hardware.org/?probe=9ef1b2b561) | May 25, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [29ebda2c17](https://linux-hardware.org/?probe=29ebda2c17) | May 23, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [599aca7ecd](https://linux-hardware.org/?probe=599aca7ecd) | May 23, 2024 |
| Fujitsu Si... | AMILO Li 2727               | Notebook    | [730034178b](https://linux-hardware.org/?probe=730034178b) | May 22, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [74c8e530ad](https://linux-hardware.org/?probe=74c8e530ad) | May 22, 2024 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [de96d1e8d8](https://linux-hardware.org/?probe=de96d1e8d8) | May 22, 2024 |
| ASUSTek       | ROG Flow X13 GV302XU_GV3... | Convertible | [356cb5a3e4](https://linux-hardware.org/?probe=356cb5a3e4) | May 21, 2024 |
| Dell          | Latitude 3190               | Notebook    | [744cbd30d7](https://linux-hardware.org/?probe=744cbd30d7) | May 21, 2024 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [f7b6c908b5](https://linux-hardware.org/?probe=f7b6c908b5) | May 20, 2024 |
| HP            | 650                         | Notebook    | [4e91cb9494](https://linux-hardware.org/?probe=4e91cb9494) | May 19, 2024 |
| Lenovo        | B590 37613FG                | Notebook    | [34097ce34b](https://linux-hardware.org/?probe=34097ce34b) | May 16, 2024 |
| Lenovo        | ThinkPad T410s 2912BY8      | Notebook    | [6d19133fbd](https://linux-hardware.org/?probe=6d19133fbd) | May 16, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [bbcfd5d01e](https://linux-hardware.org/?probe=bbcfd5d01e) | May 16, 2024 |
| Dell          | 0MGK50 A02                  | Desktop     | [09ba1d9fb0](https://linux-hardware.org/?probe=09ba1d9fb0) | May 16, 2024 |
| Pegatron      | EVE                         | Desktop     | [ee182c046b](https://linux-hardware.org/?probe=ee182c046b) | May 15, 2024 |
| Apple         | MacBook1,1                  | Notebook    | [d2c4471cc0](https://linux-hardware.org/?probe=d2c4471cc0) | May 15, 2024 |
| Microsoft     | Surface Laptop Go           | Tablet      | [fc99aed1f8](https://linux-hardware.org/?probe=fc99aed1f8) | May 15, 2024 |
| Dell          | Vostro 15 3515              | Notebook    | [a936d845d9](https://linux-hardware.org/?probe=a936d845d9) | May 14, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5a380a95a7](https://linux-hardware.org/?probe=5a380a95a7) | May 13, 2024 |
| Lenovo        | ThinkPad T410s 2912BY8      | Notebook    | [ef78e9b672](https://linux-hardware.org/?probe=ef78e9b672) | May 13, 2024 |
| GFAST         | N-140                       | Notebook    | [5f9ab6d37e](https://linux-hardware.org/?probe=5f9ab6d37e) | May 13, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [ccf9b15f46](https://linux-hardware.org/?probe=ccf9b15f46) | May 13, 2024 |
| Toshiba       | Satellite C55D-B            | Notebook    | [916a3269bb](https://linux-hardware.org/?probe=916a3269bb) | May 11, 2024 |
| HP            | 250 G1                      | Notebook    | [d2f30faf8c](https://linux-hardware.org/?probe=d2f30faf8c) | May 11, 2024 |
| Apple         | MacBook1,1                  | Notebook    | [b474cba5c4](https://linux-hardware.org/?probe=b474cba5c4) | May 10, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [67c81e68d4](https://linux-hardware.org/?probe=67c81e68d4) | May 09, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [413b207df0](https://linux-hardware.org/?probe=413b207df0) | May 09, 2024 |
| Dell          | Latitude 3190               | Notebook    | [102011a182](https://linux-hardware.org/?probe=102011a182) | May 07, 2024 |
| Toshiba       | Satellite C50-B             | Notebook    | [4037de5266](https://linux-hardware.org/?probe=4037de5266) | May 06, 2024 |
| Lenovo        | Yoga Slim 7-14ARE05 82A2    | Notebook    | [c931a1a446](https://linux-hardware.org/?probe=c931a1a446) | May 05, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b9519853cd](https://linux-hardware.org/?probe=b9519853cd) | May 05, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [08cb15cda7](https://linux-hardware.org/?probe=08cb15cda7) | May 05, 2024 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [41e3014295](https://linux-hardware.org/?probe=41e3014295) | May 04, 2024 |
| Dell          | Vostro 3400                 | Notebook    | [cd1ed35419](https://linux-hardware.org/?probe=cd1ed35419) | May 02, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [cbd3101c16](https://linux-hardware.org/?probe=cbd3101c16) | May 01, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [6aca55ce35](https://linux-hardware.org/?probe=6aca55ce35) | May 01, 2024 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [bac49afb7f](https://linux-hardware.org/?probe=bac49afb7f) | Apr 30, 2024 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [d40738eda7](https://linux-hardware.org/?probe=d40738eda7) | Apr 28, 2024 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [9ed5c55a61](https://linux-hardware.org/?probe=9ed5c55a61) | Apr 28, 2024 |
| Intel         | AB2L .A001                  | Mini pc     | [c83deebaf0](https://linux-hardware.org/?probe=c83deebaf0) | Apr 28, 2024 |
| Lenovo        | ThinkPad E560 20EV0011GE    | Notebook    | [38ab585e58](https://linux-hardware.org/?probe=38ab585e58) | Apr 27, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [d1fbf194df](https://linux-hardware.org/?probe=d1fbf194df) | Apr 25, 2024 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [dc7cef1fe5](https://linux-hardware.org/?probe=dc7cef1fe5) | Apr 25, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [62621a436b](https://linux-hardware.org/?probe=62621a436b) | Apr 25, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c44f97261d](https://linux-hardware.org/?probe=c44f97261d) | Apr 24, 2024 |
| Dell          | 0K095G A02                  | Desktop     | [a5f4dd8567](https://linux-hardware.org/?probe=a5f4dd8567) | Apr 24, 2024 |
| Dell          | 0K095G A02                  | Desktop     | [0d7d9ad04d](https://linux-hardware.org/?probe=0d7d9ad04d) | Apr 24, 2024 |
| Lenovo        | G505s 20255                 | Notebook    | [b7d2ec7d4d](https://linux-hardware.org/?probe=b7d2ec7d4d) | Apr 24, 2024 |
| Acer          | Aspire A515-47              | Notebook    | [dc0e4e49bb](https://linux-hardware.org/?probe=dc0e4e49bb) | Apr 24, 2024 |
| Acer          | Aspire A515-47              | Notebook    | [feba2802f3](https://linux-hardware.org/?probe=feba2802f3) | Apr 22, 2024 |
| Samsung       | N150/N210/N220              | Notebook    | [73f5edc5e5](https://linux-hardware.org/?probe=73f5edc5e5) | Apr 22, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [0aeb871159](https://linux-hardware.org/?probe=0aeb871159) | Apr 22, 2024 |
| AMI           | Intel                       | Desktop     | [212fd4a0d8](https://linux-hardware.org/?probe=212fd4a0d8) | Apr 22, 2024 |
| AMI           | Intel                       | Desktop     | [2044003b5c](https://linux-hardware.org/?probe=2044003b5c) | Apr 22, 2024 |
| SGIN          | M15                         | Notebook    | [68c2d94db7](https://linux-hardware.org/?probe=68c2d94db7) | Apr 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [9e43e9df38](https://linux-hardware.org/?probe=9e43e9df38) | Apr 19, 2024 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [59b4f4a7fe](https://linux-hardware.org/?probe=59b4f4a7fe) | Apr 19, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b3e2fd82b1](https://linux-hardware.org/?probe=b3e2fd82b1) | Apr 18, 2024 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [980252a20c](https://linux-hardware.org/?probe=980252a20c) | Apr 18, 2024 |
| GPU Compan... | GWTN116-3                   | Notebook    | [30fba12411](https://linux-hardware.org/?probe=30fba12411) | Apr 18, 2024 |
| GPU Compan... | GWTN116-3                   | Notebook    | [a11ace542b](https://linux-hardware.org/?probe=a11ace542b) | Apr 18, 2024 |
| Toshiba       | Satellite C55D-B            | Notebook    | [0d2ecb9207](https://linux-hardware.org/?probe=0d2ecb9207) | Apr 17, 2024 |
| HP            | 255 G1                      | Notebook    | [edea4d298e](https://linux-hardware.org/?probe=edea4d298e) | Apr 15, 2024 |
| Acer          | Aspire E1-572               | Notebook    | [a91f9fc37a](https://linux-hardware.org/?probe=a91f9fc37a) | Apr 15, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [70446389fb](https://linux-hardware.org/?probe=70446389fb) | Apr 13, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [e717cc9856](https://linux-hardware.org/?probe=e717cc9856) | Apr 13, 2024 |
| Google        | Cyan                        | Notebook    | [46c86ddfe0](https://linux-hardware.org/?probe=46c86ddfe0) | Apr 12, 2024 |
| Google        | Cyan                        | Notebook    | [e2c458d3a7](https://linux-hardware.org/?probe=e2c458d3a7) | Apr 11, 2024 |
| Acer          | AO756                       | Notebook    | [79847ca0b1](https://linux-hardware.org/?probe=79847ca0b1) | Apr 11, 2024 |
| Apple         | MacBook4,1                  | Notebook    | [d6304d794d](https://linux-hardware.org/?probe=d6304d794d) | Apr 11, 2024 |
| Dell          | Latitude 3190               | Notebook    | [4f2b2351b3](https://linux-hardware.org/?probe=4f2b2351b3) | Apr 09, 2024 |
| HP            | Notebook                    | Notebook    | [414230182b](https://linux-hardware.org/?probe=414230182b) | Apr 06, 2024 |
| ASUSTek       | Z170-A                      | Desktop     | [30127a97b5](https://linux-hardware.org/?probe=30127a97b5) | Apr 06, 2024 |
| Google        | Magolor                     | Notebook    | [36145fc673](https://linux-hardware.org/?probe=36145fc673) | Apr 06, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [0852701d67](https://linux-hardware.org/?probe=0852701d67) | Apr 05, 2024 |
| ASRock        | H77 Pro4-M                  | Desktop     | [4202019d78](https://linux-hardware.org/?probe=4202019d78) | Apr 03, 2024 |
| Dell          | Latitude 3190               | Notebook    | [c15e7df670](https://linux-hardware.org/?probe=c15e7df670) | Apr 02, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a31a3d60b1](https://linux-hardware.org/?probe=a31a3d60b1) | Apr 01, 2024 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [ce4f787af2](https://linux-hardware.org/?probe=ce4f787af2) | Apr 01, 2024 |
| Lenovo        | ThinkPad L470 20J5S1FL00    | Notebook    | [bde51e7b2c](https://linux-hardware.org/?probe=bde51e7b2c) | Apr 01, 2024 |
| Dell          | Inspiron 3185               | Notebook    | [80090c69a3](https://linux-hardware.org/?probe=80090c69a3) | Mar 31, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [115bac67be](https://linux-hardware.org/?probe=115bac67be) | Mar 30, 2024 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [7f8a245399](https://linux-hardware.org/?probe=7f8a245399) | Mar 29, 2024 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [7b17376565](https://linux-hardware.org/?probe=7b17376565) | Mar 29, 2024 |
| Fujitsu       | LIFEBOOK T938               | Convertible | [791a897f07](https://linux-hardware.org/?probe=791a897f07) | Mar 28, 2024 |
| Gigabyte      | H81M-D2V                    | Desktop     | [6bc3e596e6](https://linux-hardware.org/?probe=6bc3e596e6) | Mar 28, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e8233f1a8a](https://linux-hardware.org/?probe=e8233f1a8a) | Mar 26, 2024 |
| Acer          | Aspire E5-421G              | Notebook    | [f16af02ed4](https://linux-hardware.org/?probe=f16af02ed4) | Mar 26, 2024 |
| Lenovo        | ThinkPad X280 20KES6M100    | Notebook    | [07c23b72ec](https://linux-hardware.org/?probe=07c23b72ec) | Mar 25, 2024 |
| HP            | 250 G1                      | Notebook    | [1061b55594](https://linux-hardware.org/?probe=1061b55594) | Mar 25, 2024 |
| Dell          | 0HMX8D A01                  | Desktop     | [8cd1470fc0](https://linux-hardware.org/?probe=8cd1470fc0) | Mar 25, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [bbfdefb7ef](https://linux-hardware.org/?probe=bbfdefb7ef) | Mar 25, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [904ac30154](https://linux-hardware.org/?probe=904ac30154) | Mar 23, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [2eb785461f](https://linux-hardware.org/?probe=2eb785461f) | Mar 23, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8099dc4885](https://linux-hardware.org/?probe=8099dc4885) | Mar 22, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [cc230156f7](https://linux-hardware.org/?probe=cc230156f7) | Mar 19, 2024 |
| Gateway       | H57M01                      | Desktop     | [4254102990](https://linux-hardware.org/?probe=4254102990) | Mar 19, 2024 |
| Gateway       | H57M01                      | Desktop     | [162b2ed3b3](https://linux-hardware.org/?probe=162b2ed3b3) | Mar 17, 2024 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | Notebook    | [16070af93d](https://linux-hardware.org/?probe=16070af93d) | Mar 17, 2024 |
| HP            | 255 G1                      | Notebook    | [097c812445](https://linux-hardware.org/?probe=097c812445) | Mar 16, 2024 |
| Toshiba       | dynabook T552/36GB          | Notebook    | [9da00148f4](https://linux-hardware.org/?probe=9da00148f4) | Mar 14, 2024 |
| Medion        | Defender P30                | Notebook    | [34a9a3fde8](https://linux-hardware.org/?probe=34a9a3fde8) | Mar 13, 2024 |
| Medion        | Defender P30                | Notebook    | [459ac8cc46](https://linux-hardware.org/?probe=459ac8cc46) | Mar 13, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [91114bc213](https://linux-hardware.org/?probe=91114bc213) | Mar 13, 2024 |
| HP            | 620                         | Notebook    | [b5df7d8db3](https://linux-hardware.org/?probe=b5df7d8db3) | Mar 12, 2024 |
| Apple         | Mac-F2268CC8                | All in one  | [fccb125880](https://linux-hardware.org/?probe=fccb125880) | Mar 12, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [771c9373e9](https://linux-hardware.org/?probe=771c9373e9) | Mar 11, 2024 |
| HP            | 650                         | Notebook    | [96c8acc1a4](https://linux-hardware.org/?probe=96c8acc1a4) | Mar 11, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [df839d09a2](https://linux-hardware.org/?probe=df839d09a2) | Mar 11, 2024 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [5dc203d476](https://linux-hardware.org/?probe=5dc203d476) | Mar 10, 2024 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [4ed069d496](https://linux-hardware.org/?probe=4ed069d496) | Mar 09, 2024 |
| HP            | 2B5A 011                    | Desktop     | [8eb2546f52](https://linux-hardware.org/?probe=8eb2546f52) | Mar 09, 2024 |
| Toshiba       | Satellite P875              | Notebook    | [e1b998e44b](https://linux-hardware.org/?probe=e1b998e44b) | Mar 09, 2024 |
| HP            | 8950                        | Desktop     | [ee925d29a1](https://linux-hardware.org/?probe=ee925d29a1) | Mar 08, 2024 |
| HP            | 8950                        | Desktop     | [f2b8f96540](https://linux-hardware.org/?probe=f2b8f96540) | Mar 08, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [be5e190ea5](https://linux-hardware.org/?probe=be5e190ea5) | Mar 08, 2024 |
| ASUSTek       | T100TA                      | Notebook    | [d723bb2900](https://linux-hardware.org/?probe=d723bb2900) | Mar 07, 2024 |
| ASRock        | A300M-STX                   | Desktop     | [a92e2761aa](https://linux-hardware.org/?probe=a92e2761aa) | Mar 06, 2024 |
| HP            | Compaq nc6320 (RU397EA#A... | Notebook    | [edd727d30d](https://linux-hardware.org/?probe=edd727d30d) | Mar 05, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [e61abe174c](https://linux-hardware.org/?probe=e61abe174c) | Mar 04, 2024 |
| Google        | Magolor                     | Notebook    | [bf456da608](https://linux-hardware.org/?probe=bf456da608) | Mar 04, 2024 |
| HP            | Pavilion g6                 | Notebook    | [fd797ba3af](https://linux-hardware.org/?probe=fd797ba3af) | Mar 04, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [e4944abc1f](https://linux-hardware.org/?probe=e4944abc1f) | Mar 03, 2024 |
| Alienware     | 18                          | Notebook    | [b7402f0c82](https://linux-hardware.org/?probe=b7402f0c82) | Mar 03, 2024 |
| HP            | Pavilion g6                 | Notebook    | [7e4412a097](https://linux-hardware.org/?probe=7e4412a097) | Mar 03, 2024 |
| Lenovo        | ThinkPad T480 20L6003PFR    | Notebook    | [d6ded6d32a](https://linux-hardware.org/?probe=d6ded6d32a) | Mar 03, 2024 |
| Dell          | System Inspiron N7110       | Notebook    | [6c1eb8d628](https://linux-hardware.org/?probe=6c1eb8d628) | Mar 02, 2024 |
| HP            | Pavilion dv6                | Notebook    | [14e50b9c6c](https://linux-hardware.org/?probe=14e50b9c6c) | Mar 01, 2024 |
| PC Special... | Lafite Pro III 17           | Notebook    | [41f1e90fb9](https://linux-hardware.org/?probe=41f1e90fb9) | Feb 29, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [c6209a30c6](https://linux-hardware.org/?probe=c6209a30c6) | Feb 28, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [3d502260aa](https://linux-hardware.org/?probe=3d502260aa) | Feb 28, 2024 |
| Dell          | 0M863N A01                  | Desktop     | [1db77a3f14](https://linux-hardware.org/?probe=1db77a3f14) | Feb 27, 2024 |
| Toshiba       | IS 1413G                    | Notebook    | [0f39b4b446](https://linux-hardware.org/?probe=0f39b4b446) | Feb 27, 2024 |
| Toshiba       | Satellite C55-A             | Notebook    | [9d0cd280a9](https://linux-hardware.org/?probe=9d0cd280a9) | Feb 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [527feb458b](https://linux-hardware.org/?probe=527feb458b) | Feb 26, 2024 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [ce358b38bc](https://linux-hardware.org/?probe=ce358b38bc) | Feb 26, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [f31eac8a5d](https://linux-hardware.org/?probe=f31eac8a5d) | Feb 24, 2024 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [1dab02eb79](https://linux-hardware.org/?probe=1dab02eb79) | Feb 24, 2024 |
| Apple         | MacBookPro5,2               | Notebook    | [f34e05e096](https://linux-hardware.org/?probe=f34e05e096) | Feb 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [bb563ea8ac](https://linux-hardware.org/?probe=bb563ea8ac) | Feb 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2c9ffa4b20](https://linux-hardware.org/?probe=2c9ffa4b20) | Feb 23, 2024 |
| Toshiba       | IS 1413G                    | Notebook    | [c88a0acd8e](https://linux-hardware.org/?probe=c88a0acd8e) | Feb 22, 2024 |
| Dell          | Vostro 1014                 | Notebook    | [5fcabcc564](https://linux-hardware.org/?probe=5fcabcc564) | Feb 22, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [9b25d17d18](https://linux-hardware.org/?probe=9b25d17d18) | Feb 21, 2024 |
| Dell          | Latitude 3190               | Notebook    | [1396b535bf](https://linux-hardware.org/?probe=1396b535bf) | Feb 20, 2024 |
| I-life        | ZEDNOTE                     | Notebook    | [172d63ec33](https://linux-hardware.org/?probe=172d63ec33) | Feb 19, 2024 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [3cf24bd897](https://linux-hardware.org/?probe=3cf24bd897) | Feb 18, 2024 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fab0b459e0](https://linux-hardware.org/?probe=fab0b459e0) | Feb 18, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [75d09cfc27](https://linux-hardware.org/?probe=75d09cfc27) | Feb 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [96859b01b7](https://linux-hardware.org/?probe=96859b01b7) | Feb 17, 2024 |
| Dell          | Latitude E5540              | Notebook    | [9103e34326](https://linux-hardware.org/?probe=9103e34326) | Feb 17, 2024 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [9e494a90c5](https://linux-hardware.org/?probe=9e494a90c5) | Feb 17, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [39da02c65d](https://linux-hardware.org/?probe=39da02c65d) | Feb 16, 2024 |
| Dell          | Inspiron 7566               | Notebook    | [9d3c279e4c](https://linux-hardware.org/?probe=9d3c279e4c) | Feb 16, 2024 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [bb7608ac6f](https://linux-hardware.org/?probe=bb7608ac6f) | Feb 15, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [70a8707a5c](https://linux-hardware.org/?probe=70a8707a5c) | Feb 15, 2024 |
| Lenovo        | 3741 SDK0T76461 WIN 3422... | Desktop     | [144333e02b](https://linux-hardware.org/?probe=144333e02b) | Feb 15, 2024 |
| ASRock        | B450M Pro4-F                | Desktop     | [a98775e16e](https://linux-hardware.org/?probe=a98775e16e) | Feb 13, 2024 |
| Dell          | Latitude 3190               | Notebook    | [2f96d064fd](https://linux-hardware.org/?probe=2f96d064fd) | Feb 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a7f40a3ffe](https://linux-hardware.org/?probe=a7f40a3ffe) | Feb 11, 2024 |
| Fujitsu Si... | AMILO Li 1818               | Notebook    | [1703fc6a96](https://linux-hardware.org/?probe=1703fc6a96) | Feb 11, 2024 |
| ASUSTek       | T100TAM                     | Notebook    | [2b6b08ce6c](https://linux-hardware.org/?probe=2b6b08ce6c) | Feb 10, 2024 |
| LG Electro... | 17Z90N-V.BJ51P1             | Notebook    | [df1bbe4be6](https://linux-hardware.org/?probe=df1bbe4be6) | Feb 10, 2024 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [de7b828cc8](https://linux-hardware.org/?probe=de7b828cc8) | Feb 10, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [9c0a07bf2b](https://linux-hardware.org/?probe=9c0a07bf2b) | Feb 08, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [24d22f38e9](https://linux-hardware.org/?probe=24d22f38e9) | Feb 08, 2024 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [7350797e64](https://linux-hardware.org/?probe=7350797e64) | Feb 07, 2024 |
| ASRock        | 970 Extreme4                | Desktop     | [973c66c65d](https://linux-hardware.org/?probe=973c66c65d) | Feb 07, 2024 |
| Dell          | Latitude 3190               | Notebook    | [f597a4ca06](https://linux-hardware.org/?probe=f597a4ca06) | Feb 06, 2024 |
| MSI           | GE63 Raider RGB 9SE         | Notebook    | [044863dd64](https://linux-hardware.org/?probe=044863dd64) | Feb 05, 2024 |
| Dell          | Latitude 120L               | Notebook    | [e5707dd6cb](https://linux-hardware.org/?probe=e5707dd6cb) | Feb 04, 2024 |
| Samsung       | 750XDA                      | Notebook    | [a7dd0472ed](https://linux-hardware.org/?probe=a7dd0472ed) | Feb 03, 2024 |
| Acidanther... | Mac-F221DCC8                | All in one  | [973ce60ef5](https://linux-hardware.org/?probe=973ce60ef5) | Feb 03, 2024 |
| Dell          | Latitude D630               | Notebook    | [4ab9c9ef70](https://linux-hardware.org/?probe=4ab9c9ef70) | Feb 03, 2024 |
| Acidanther... | Mac-F221DCC8                | All in one  | [f610379068](https://linux-hardware.org/?probe=f610379068) | Feb 03, 2024 |
| VIT           | P3400                       | Notebook    | [036ee57838](https://linux-hardware.org/?probe=036ee57838) | Feb 02, 2024 |
| HP            | 09E8h                       | Desktop     | [413788d555](https://linux-hardware.org/?probe=413788d555) | Feb 02, 2024 |
| VIT           | P3400                       | Notebook    | [6b03e6574f](https://linux-hardware.org/?probe=6b03e6574f) | Feb 01, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [653f9c5fa5](https://linux-hardware.org/?probe=653f9c5fa5) | Feb 01, 2024 |
| Dell          | 00VTMF A01                  | Desktop     | [3298485dd9](https://linux-hardware.org/?probe=3298485dd9) | Jan 31, 2024 |
| Dell          | Latitude 3190               | Notebook    | [16f86af47d](https://linux-hardware.org/?probe=16f86af47d) | Jan 30, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [35aa462f74](https://linux-hardware.org/?probe=35aa462f74) | Jan 30, 2024 |
| Dell          | Latitude 7380               | Notebook    | [d11324e996](https://linux-hardware.org/?probe=d11324e996) | Jan 28, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [3f817efef4](https://linux-hardware.org/?probe=3f817efef4) | Jan 26, 2024 |
| HP            | 304Ah                       | Desktop     | [5e40a8acee](https://linux-hardware.org/?probe=5e40a8acee) | Jan 24, 2024 |
| Dell          | Latitude E6410              | Notebook    | [1b7b83010f](https://linux-hardware.org/?probe=1b7b83010f) | Jan 24, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [6eb8876e79](https://linux-hardware.org/?probe=6eb8876e79) | Jan 24, 2024 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [6ae01879d8](https://linux-hardware.org/?probe=6ae01879d8) | Jan 23, 2024 |
| HP            | 0A5Ch                       | Desktop     | [f886596563](https://linux-hardware.org/?probe=f886596563) | Jan 23, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [e03dc88f3e](https://linux-hardware.org/?probe=e03dc88f3e) | Jan 20, 2024 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [0da14a9376](https://linux-hardware.org/?probe=0da14a9376) | Jan 18, 2024 |
| HP            | Notebook                    | Notebook    | [0f5f8dd38d](https://linux-hardware.org/?probe=0f5f8dd38d) | Jan 17, 2024 |
| Google        | Barla                       | Notebook    | [f053c5164a](https://linux-hardware.org/?probe=f053c5164a) | Jan 16, 2024 |
| HP            | 8750                        | Desktop     | [6dd29a1c24](https://linux-hardware.org/?probe=6dd29a1c24) | Jan 16, 2024 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [33216d3bf8](https://linux-hardware.org/?probe=33216d3bf8) | Jan 16, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [d0af07b360](https://linux-hardware.org/?probe=d0af07b360) | Jan 15, 2024 |
| Apple         | MacBookPro14,3              | Notebook    | [3b0c274172](https://linux-hardware.org/?probe=3b0c274172) | Jan 12, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [f782b74751](https://linux-hardware.org/?probe=f782b74751) | Jan 12, 2024 |
| Unknown       | GB01                        | Desktop     | [33016aa27b](https://linux-hardware.org/?probe=33016aa27b) | Jan 11, 2024 |
| Unknown       | GB01                        | Desktop     | [551b27fa9b](https://linux-hardware.org/?probe=551b27fa9b) | Jan 11, 2024 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [f40c009358](https://linux-hardware.org/?probe=f40c009358) | Jan 11, 2024 |
| Dell          | 0KV62T A00                  | Desktop     | [17aa442f24](https://linux-hardware.org/?probe=17aa442f24) | Jan 10, 2024 |
| Dell          | Latitude 3190               | Notebook    | [afdd5a1dbe](https://linux-hardware.org/?probe=afdd5a1dbe) | Jan 09, 2024 |
| HP            | Pavilion dv2700             | Notebook    | [957ec4cc30](https://linux-hardware.org/?probe=957ec4cc30) | Jan 09, 2024 |
| KEIAN         | KI8-BK                      | Tablet      | [aaf299df58](https://linux-hardware.org/?probe=aaf299df58) | Jan 08, 2024 |
| Sony          | SVF1521H1EW                 | Notebook    | [1939183179](https://linux-hardware.org/?probe=1939183179) | Jan 07, 2024 |
| ASUSTek       | PN52                        | Mini pc     | [5c770765da](https://linux-hardware.org/?probe=5c770765da) | Jan 05, 2024 |
| HP            | 8265                        | Desktop     | [da63a4f9c1](https://linux-hardware.org/?probe=da63a4f9c1) | Jan 05, 2024 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [029706288d](https://linux-hardware.org/?probe=029706288d) | Jan 04, 2024 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9dfa4f4d36](https://linux-hardware.org/?probe=9dfa4f4d36) | Jan 03, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [71d03730b7](https://linux-hardware.org/?probe=71d03730b7) | Jan 03, 2024 |
| Dell          | Latitude 5400               | Notebook    | [9e318e9b78](https://linux-hardware.org/?probe=9e318e9b78) | Jan 03, 2024 |
| Dell          | Latitude 5400               | Notebook    | [59a90bd726](https://linux-hardware.org/?probe=59a90bd726) | Jan 03, 2024 |
| Acer          | Aspire A515-43              | Notebook    | [68a2707c3f](https://linux-hardware.org/?probe=68a2707c3f) | Dec 31, 2023 |
| MSI           | MS-ACB31 100                | All in one  | [ffe63dc278](https://linux-hardware.org/?probe=ffe63dc278) | Dec 30, 2023 |
| Google        | Barla                       | Notebook    | [585887bc42](https://linux-hardware.org/?probe=585887bc42) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8f3ab867ea](https://linux-hardware.org/?probe=8f3ab867ea) | Dec 30, 2023 |
| HP            | 8265                        | Desktop     | [94344dbe98](https://linux-hardware.org/?probe=94344dbe98) | Dec 28, 2023 |
| HP            | Pavilion dv6                | Notebook    | [39515c70db](https://linux-hardware.org/?probe=39515c70db) | Dec 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c29956a752](https://linux-hardware.org/?probe=c29956a752) | Dec 27, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [5647df79c0](https://linux-hardware.org/?probe=5647df79c0) | Dec 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [e0da711bcb](https://linux-hardware.org/?probe=e0da711bcb) | Dec 26, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [977367b99e](https://linux-hardware.org/?probe=977367b99e) | Dec 26, 2023 |
| Lenovo        | ThinkPad T460 20FMS0W32L    | Notebook    | [55200b6aa5](https://linux-hardware.org/?probe=55200b6aa5) | Dec 26, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [eade6242b7](https://linux-hardware.org/?probe=eade6242b7) | Dec 25, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [ab0b99f2f2](https://linux-hardware.org/?probe=ab0b99f2f2) | Dec 25, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [0da41c3e3b](https://linux-hardware.org/?probe=0da41c3e3b) | Dec 25, 2023 |
| Google        | Bobba                       | Notebook    | [c0e8038184](https://linux-hardware.org/?probe=c0e8038184) | Dec 22, 2023 |
| Google        | Bobba                       | Notebook    | [c03b219f2e](https://linux-hardware.org/?probe=c03b219f2e) | Dec 22, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [456c5b7613](https://linux-hardware.org/?probe=456c5b7613) | Dec 21, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [88cad415fb](https://linux-hardware.org/?probe=88cad415fb) | Dec 21, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [bc7fc2be74](https://linux-hardware.org/?probe=bc7fc2be74) | Dec 20, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [11f3b9c9d6](https://linux-hardware.org/?probe=11f3b9c9d6) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f912bcd96a](https://linux-hardware.org/?probe=f912bcd96a) | Dec 20, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a7e488632e](https://linux-hardware.org/?probe=a7e488632e) | Dec 19, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [97e3b8d570](https://linux-hardware.org/?probe=97e3b8d570) | Dec 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a6d28b0e6a](https://linux-hardware.org/?probe=a6d28b0e6a) | Dec 18, 2023 |
| Acer          | Aspire 4820TG               | Notebook    | [a9bc29a915](https://linux-hardware.org/?probe=a9bc29a915) | Dec 17, 2023 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [df3eb3c253](https://linux-hardware.org/?probe=df3eb3c253) | Dec 17, 2023 |
| HP            | 8265                        | Desktop     | [cc0b59e7f7](https://linux-hardware.org/?probe=cc0b59e7f7) | Dec 13, 2023 |
| HP            | Notebook                    | Notebook    | [d25691af9b](https://linux-hardware.org/?probe=d25691af9b) | Dec 13, 2023 |
| Gigabyte      | MRHM7AP                     | Desktop     | [ba4400c919](https://linux-hardware.org/?probe=ba4400c919) | Dec 13, 2023 |
| Dell          | Latitude 3190               | Notebook    | [faf8105e3c](https://linux-hardware.org/?probe=faf8105e3c) | Dec 12, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [10e35dbb2a](https://linux-hardware.org/?probe=10e35dbb2a) | Dec 12, 2023 |
| Dell          | Vostro 1320                 | Notebook    | [cf44765cd0](https://linux-hardware.org/?probe=cf44765cd0) | Dec 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [8fc19fa86c](https://linux-hardware.org/?probe=8fc19fa86c) | Dec 11, 2023 |
| Lenovo        | ThinkPad X201 3626GWG       | Notebook    | [023f7dd390](https://linux-hardware.org/?probe=023f7dd390) | Dec 11, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [3bbc394b2e](https://linux-hardware.org/?probe=3bbc394b2e) | Dec 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [6c558ca3cf](https://linux-hardware.org/?probe=6c558ca3cf) | Dec 06, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [442d7a2388](https://linux-hardware.org/?probe=442d7a2388) | Dec 03, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [d536392d03](https://linux-hardware.org/?probe=d536392d03) | Nov 30, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [bfe263dfe0](https://linux-hardware.org/?probe=bfe263dfe0) | Nov 30, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [9a5c924695](https://linux-hardware.org/?probe=9a5c924695) | Nov 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [339e20f716](https://linux-hardware.org/?probe=339e20f716) | Nov 24, 2023 |
| MSI           | A68HM-P33 V2                | Desktop     | [bee7ef1689](https://linux-hardware.org/?probe=bee7ef1689) | Nov 22, 2023 |
| Mediacom      | FlexBook edge11 - M-FBE1... | Notebook    | [9b0835e62d](https://linux-hardware.org/?probe=9b0835e62d) | Nov 21, 2023 |
| Dell          | Latitude 3190               | Notebook    | [3c5b8541c7](https://linux-hardware.org/?probe=3c5b8541c7) | Nov 21, 2023 |
| Lenovo        | ThinkPad T500 20552CU       | Notebook    | [7389e9e37c](https://linux-hardware.org/?probe=7389e9e37c) | Nov 21, 2023 |
| HP            | 8265                        | Desktop     | [d798ead6f7](https://linux-hardware.org/?probe=d798ead6f7) | Nov 20, 2023 |
| Dell          | 0MNPJ9 A01                  | Desktop     | [80ded618fb](https://linux-hardware.org/?probe=80ded618fb) | Nov 19, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [e1a2307332](https://linux-hardware.org/?probe=e1a2307332) | Nov 18, 2023 |
| Dell          | Precision 5570              | Notebook    | [7cb435d2dc](https://linux-hardware.org/?probe=7cb435d2dc) | Nov 16, 2023 |
| HP            | ProLiant DL380 G5           | Server      | [55414de640](https://linux-hardware.org/?probe=55414de640) | Nov 14, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [23196bda4d](https://linux-hardware.org/?probe=23196bda4d) | Nov 14, 2023 |
| HP            | ProLiant DL360 G5           | Server      | [90ce2b0711](https://linux-hardware.org/?probe=90ce2b0711) | Nov 13, 2023 |
| Gateway       | NV57H                       | Notebook    | [e5f084f72c](https://linux-hardware.org/?probe=e5f084f72c) | Nov 11, 2023 |
| HP            | 3397                        | Desktop     | [67e178009d](https://linux-hardware.org/?probe=67e178009d) | Nov 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [751f4b0d96](https://linux-hardware.org/?probe=751f4b0d96) | Nov 08, 2023 |
| Intel         | NUC7JYB J67967-406          | Mini pc     | [600002b4a9](https://linux-hardware.org/?probe=600002b4a9) | Nov 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [25ab11fca1](https://linux-hardware.org/?probe=25ab11fca1) | Nov 08, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [0d65b73ae2](https://linux-hardware.org/?probe=0d65b73ae2) | Nov 07, 2023 |
| Dell          | Latitude 3190               | Notebook    | [309f968d10](https://linux-hardware.org/?probe=309f968d10) | Nov 07, 2023 |
| HP            | 2B34                        | Desktop     | [52737869e2](https://linux-hardware.org/?probe=52737869e2) | Nov 06, 2023 |
| HP            | ProBook 6470b               | Notebook    | [50c1d43281](https://linux-hardware.org/?probe=50c1d43281) | Nov 05, 2023 |
| AMI           | Unknown                     | Notebook    | [2512404fd7](https://linux-hardware.org/?probe=2512404fd7) | Nov 05, 2023 |
| ASRock        | A320M Pro4-F                | Desktop     | [7dab52cd8c](https://linux-hardware.org/?probe=7dab52cd8c) | Nov 05, 2023 |
| HP            | Compaq 6730s                | Notebook    | [073756d958](https://linux-hardware.org/?probe=073756d958) | Nov 03, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [e95902544f](https://linux-hardware.org/?probe=e95902544f) | Nov 03, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [2de4949247](https://linux-hardware.org/?probe=2de4949247) | Nov 01, 2023 |
| Lenovo        | V17 G2 ITL 82NX             | Notebook    | [d267711f7e](https://linux-hardware.org/?probe=d267711f7e) | Nov 01, 2023 |
| Dell          | Latitude 5490               | Notebook    | [fcee866d9a](https://linux-hardware.org/?probe=fcee866d9a) | Oct 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [dc68dc55c9](https://linux-hardware.org/?probe=dc68dc55c9) | Oct 31, 2023 |
| HONOR         | BMH-WDX9                    | Notebook    | [a1962fef8a](https://linux-hardware.org/?probe=a1962fef8a) | Oct 31, 2023 |
| AMI           | Intel                       | Notebook    | [42ebe1755f](https://linux-hardware.org/?probe=42ebe1755f) | Oct 30, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0a5b6171b7](https://linux-hardware.org/?probe=0a5b6171b7) | Oct 30, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [52786d6efa](https://linux-hardware.org/?probe=52786d6efa) | Oct 30, 2023 |
| Intel         | H81                         | Desktop     | [2e37259d45](https://linux-hardware.org/?probe=2e37259d45) | Oct 29, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2cb1fb1ec9](https://linux-hardware.org/?probe=2cb1fb1ec9) | Oct 27, 2023 |
| HP            | 339A                        | Desktop     | [d0deadc097](https://linux-hardware.org/?probe=d0deadc097) | Oct 27, 2023 |
| Lenovo        | 376D SDK0T76465 WIN 3422... | Desktop     | [2a97bb6c00](https://linux-hardware.org/?probe=2a97bb6c00) | Oct 27, 2023 |
| Dell          | 0K9T56 A00                  | All in one  | [e02693091f](https://linux-hardware.org/?probe=e02693091f) | Oct 25, 2023 |
| Dell          | 0K9T56 A00                  | All in one  | [cc8dcd6a8d](https://linux-hardware.org/?probe=cc8dcd6a8d) | Oct 24, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a26f69cb33](https://linux-hardware.org/?probe=a26f69cb33) | Oct 24, 2023 |
| AZW           | SER V1                      | Desktop     | [8c734a7dfc](https://linux-hardware.org/?probe=8c734a7dfc) | Oct 21, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [f6a5fcd391](https://linux-hardware.org/?probe=f6a5fcd391) | Oct 21, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [36eb2472ca](https://linux-hardware.org/?probe=36eb2472ca) | Oct 20, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [6c7d912754](https://linux-hardware.org/?probe=6c7d912754) | Oct 20, 2023 |
| Acer          | Extensa 2519                | Notebook    | [4d8970a1f5](https://linux-hardware.org/?probe=4d8970a1f5) | Oct 19, 2023 |
| Acer          | Aspire TC-1760              | Desktop     | [9e4ac23c4b](https://linux-hardware.org/?probe=9e4ac23c4b) | Oct 19, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [dada2b85e8](https://linux-hardware.org/?probe=dada2b85e8) | Oct 17, 2023 |
| Dell          | Inspiron 5448               | Notebook    | [5901b49079](https://linux-hardware.org/?probe=5901b49079) | Oct 17, 2023 |
| Dell          | Latitude 3190               | Notebook    | [6524dff50f](https://linux-hardware.org/?probe=6524dff50f) | Oct 17, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [20c026b8a7](https://linux-hardware.org/?probe=20c026b8a7) | Oct 16, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [da0024090d](https://linux-hardware.org/?probe=da0024090d) | Oct 16, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [60e2d65ac4](https://linux-hardware.org/?probe=60e2d65ac4) | Oct 16, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [df7395bd63](https://linux-hardware.org/?probe=df7395bd63) | Oct 16, 2023 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [273e4a294a](https://linux-hardware.org/?probe=273e4a294a) | Oct 15, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [665eba904c](https://linux-hardware.org/?probe=665eba904c) | Oct 14, 2023 |
| Google        | Celes                       | Notebook    | [914ad131fd](https://linux-hardware.org/?probe=914ad131fd) | Oct 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [00fc33d73e](https://linux-hardware.org/?probe=00fc33d73e) | Oct 13, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [6f4fb2dff4](https://linux-hardware.org/?probe=6f4fb2dff4) | Oct 10, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [e4f9055fce](https://linux-hardware.org/?probe=e4f9055fce) | Oct 09, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [62c8d86cfa](https://linux-hardware.org/?probe=62c8d86cfa) | Oct 06, 2023 |
| Dell          | Latitude E6410              | Notebook    | [d6db17e35f](https://linux-hardware.org/?probe=d6db17e35f) | Oct 06, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [e583e35b95](https://linux-hardware.org/?probe=e583e35b95) | Oct 03, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [538889d79f](https://linux-hardware.org/?probe=538889d79f) | Oct 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [21aac15234](https://linux-hardware.org/?probe=21aac15234) | Oct 03, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [4b46fb8e6a](https://linux-hardware.org/?probe=4b46fb8e6a) | Oct 02, 2023 |
| Notebook      | NL5xNU                      | Notebook    | [d5e4f28683](https://linux-hardware.org/?probe=d5e4f28683) | Oct 02, 2023 |
| Fujitsu Si... | AMILO A1650G                | Notebook    | [ec61a60044](https://linux-hardware.org/?probe=ec61a60044) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4a6090c2f4](https://linux-hardware.org/?probe=4a6090c2f4) | Sep 29, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [ee6e1996b9](https://linux-hardware.org/?probe=ee6e1996b9) | Sep 29, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [3c87964524](https://linux-hardware.org/?probe=3c87964524) | Sep 28, 2023 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | Notebook    | [2b7f074e47](https://linux-hardware.org/?probe=2b7f074e47) | Sep 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [8ebd8669f2](https://linux-hardware.org/?probe=8ebd8669f2) | Sep 26, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/MX/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| MX 23          | 687       | 47.94%  |
| MX 21          | 433       | 30.22%  |
| MX 19          | 150       | 10.47%  |
| MX 20          | 74        | 5.16%   |
| MX 25          | 50        | 3.49%   |
| MX 18          | 27        | 1.88%   |
| MX 24          | 4         | 0.28%   |
| MX 17          | 4         | 0.28%   |
| MX 22          | 1         | 0.07%   |
| MX 2           | 1         | 0.07%   |
| MX 16-migrated | 1         | 0.07%   |
| MX 16          | 1         | 0.07%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| MX   | 1402      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Computers | Percent |
|---------------------------|-----------|---------|
| 4.19.0-6-amd64            | 59        | 3.86%   |
| 6.0.0-6mx-amd64           | 44        | 2.88%   |
| 6.1.0-37-amd64            | 41        | 2.68%   |
| 5.10.0-21-amd64           | 41        | 2.68%   |
| 6.1.0-17-amd64            | 40        | 2.61%   |
| 6.1.0-21-amd64            | 36        | 2.35%   |
| 6.1.0-13-amd64            | 35        | 2.29%   |
| 6.1.0-25-amd64            | 32        | 2.09%   |
| 6.1.0-10-amd64            | 32        | 2.09%   |
| 5.10.0-23-amd64           | 26        | 1.7%    |
| 6.1.0-26-amd64            | 25        | 1.63%   |
| 6.5.0-1mx-ahs-amd64       | 24        | 1.57%   |
| 6.1.0-23-amd64            | 24        | 1.57%   |
| 5.10.0-20-amd64           | 24        | 1.57%   |
| 5.10.0-5mx-amd64          | 23        | 1.5%    |
| 6.4.0-1mx-ahs-amd64       | 21        | 1.37%   |
| 6.1.0-33-amd64            | 21        | 1.37%   |
| 5.10.0-18-amd64           | 21        | 1.37%   |
| 5.10.0-13-amd64           | 20        | 1.31%   |
| 5.14.0-4mx-amd64          | 19        | 1.24%   |
| 6.12.57+deb13-amd64       | 18        | 1.18%   |
| 6.1.0-40-amd64            | 18        | 1.18%   |
| 6.1.0-32-amd64            | 18        | 1.18%   |
| 6.1.0-31-amd64            | 18        | 1.18%   |
| 5.10.0-9-amd64            | 18        | 1.18%   |
| 5.10.0-19-amd64           | 18        | 1.18%   |
| 6.12.48+deb13-amd64       | 17        | 1.11%   |
| 6.1.0-18-amd64            | 17        | 1.11%   |
| 5.6.0-2-amd64             | 17        | 1.11%   |
| 5.8.0-3-amd64             | 16        | 1.05%   |
| 5.16.0-5mx-amd64          | 15        | 0.98%   |
| 6.1.0-29-amd64            | 14        | 0.92%   |
| 6.1.0-28-amd64            | 14        | 0.92%   |
| 6.1.0-34-amd64            | 13        | 0.85%   |
| 5.10.0-16-amd64           | 13        | 0.85%   |
| 6.0.0-10.1-liquorix-amd64 | 12        | 0.78%   |
| 5.18.0-4mx-amd64          | 12        | 0.78%   |
| 6.6.12-1-liquorix-amd64   | 10        | 0.65%   |
| 6.16.12-1-liquorix-amd64  | 10        | 0.65%   |
| 6.1.0-35-amd64            | 10        | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 513       | 34.95%  |
| 5.10.0  | 290       | 19.75%  |
| 4.19.0  | 135       | 9.2%    |
| 6.0.0   | 67        | 4.56%   |
| 6.4.0   | 29        | 1.98%   |
| 6.5.0   | 27        | 1.84%   |
| 5.16.0  | 24        | 1.63%   |
| 5.14.0  | 22        | 1.5%    |
| 5.6.0   | 19        | 1.29%   |
| 6.12.57 | 18        | 1.23%   |
| 6.12.48 | 17        | 1.16%   |
| 5.8.0   | 16        | 1.09%   |
| 5.18.0  | 14        | 0.95%   |
| 5.19.0  | 12        | 0.82%   |
| 6.6.12  | 10        | 0.68%   |
| 6.16.12 | 10        | 0.68%   |
| 6.8.9   | 9         | 0.61%   |
| 5.4.0   | 9         | 0.61%   |
| 6.15.11 | 7         | 0.48%   |
| 6.11.10 | 7         | 0.48%   |
| 5.17.0  | 7         | 0.48%   |
| 6.7.12  | 6         | 0.41%   |
| 6.6.11  | 6         | 0.41%   |
| 6.14.10 | 6         | 0.41%   |
| 5.5.0   | 6         | 0.41%   |
| 4.15.0  | 6         | 0.41%   |
| 6.12.6  | 5         | 0.34%   |
| 6.10.10 | 5         | 0.34%   |
| 5.15.0  | 5         | 0.34%   |
| 6.9.7   | 4         | 0.27%   |
| 6.14.2  | 4         | 0.27%   |
| 6.13.7  | 4         | 0.27%   |
| 6.10.11 | 4         | 0.27%   |
| 5.8.16  | 4         | 0.27%   |
| 5.3.0   | 4         | 0.27%   |
| 5.2.21  | 4         | 0.27%   |
| 6.9.12  | 3         | 0.2%    |
| 6.6.9   | 3         | 0.2%    |
| 6.3.9   | 3         | 0.2%    |
| 6.3.0   | 3         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 517       | 35.31%  |
| 5.10    | 298       | 20.36%  |
| 4.19    | 136       | 9.29%   |
| 6.0     | 68        | 4.64%   |
| 6.12    | 58        | 3.96%   |
| 6.4     | 35        | 2.39%   |
| 6.5     | 32        | 2.19%   |
| 6.6     | 28        | 1.91%   |
| 5.16    | 24        | 1.64%   |
| 5.6     | 22        | 1.5%    |
| 5.14    | 22        | 1.5%    |
| 5.8     | 20        | 1.37%   |
| 6.14    | 16        | 1.09%   |
| 6.11    | 16        | 1.09%   |
| 5.18    | 14        | 0.96%   |
| 6.8     | 12        | 0.82%   |
| 5.4     | 12        | 0.82%   |
| 5.19    | 12        | 0.82%   |
| 6.7     | 11        | 0.75%   |
| 6.10    | 11        | 0.75%   |
| 6.9     | 10        | 0.68%   |
| 6.16    | 10        | 0.68%   |
| 6.13    | 8         | 0.55%   |
| 6.15    | 7         | 0.48%   |
| 5.2     | 7         | 0.48%   |
| 5.17    | 7         | 0.48%   |
| 6.3     | 6         | 0.41%   |
| 5.5     | 6         | 0.41%   |
| 4.15    | 6         | 0.41%   |
| 5.3     | 5         | 0.34%   |
| 5.15    | 5         | 0.34%   |
| 4.9     | 5         | 0.34%   |
| 6.2     | 4         | 0.27%   |
| 6.17    | 2         | 0.14%   |
| 5.13    | 2         | 0.14%   |
| 5.11    | 2         | 0.14%   |
| 4.18    | 2         | 0.14%   |
| 5.9     | 1         | 0.07%   |
| 5.7     | 1         | 0.07%   |
| 5.1     | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1332      | 94.94%  |
| i686    | 67        | 4.78%   |
| aarch64 | 4         | 0.29%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 1027      | 72.22%  |
| KDE5             | 279       | 19.62%  |
| fluxbox          | 20        | 1.41%   |
| Unknown          | 15        | 1.05%   |
| lightdm-xsession | 12        | 0.84%   |
| i3               | 9         | 0.63%   |
| Budgie           | 9         | 0.63%   |
| KDE6             | 8         | 0.56%   |
| X-Cinnamon       | 7         | 0.49%   |
| MATE             | 7         | 0.49%   |
| LXQt             | 7         | 0.49%   |
| GNOME            | 7         | 0.49%   |
| Trinity          | 3         | 0.21%   |
| KDE              | 3         | 0.21%   |
| GNOME Flashback  | 2         | 0.14%   |
| Cinnamon         | 2         | 0.14%   |
| spectrwm         | 1         | 0.07%   |
| LXDE             | 1         | 0.07%   |
| KDE4             | 1         | 0.07%   |
| ICEWM            | 1         | 0.07%   |
| GNOME Classic    | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1356      | 96.51%  |
| Wayland | 36        | 2.56%   |
| Tty     | 12        | 0.85%   |
| Web     | 1         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 1108      | 78.53%  |
| SDDM    | 269       | 19.06%  |
| TDM     | 14        | 0.99%   |
| SLiM    | 14        | 0.99%   |
| Unknown | 3         | 0.21%   |
| GDM3    | 2         | 0.14%   |
| GDM     | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 595       | 41.9%   |
| de_DE   | 169       | 11.9%   |
| Unknown | 105       | 7.39%   |
| en_GB   | 81        | 5.7%    |
| it_IT   | 72        | 5.07%   |
| fr_FR   | 43        | 3.03%   |
| ru_RU   | 37        | 2.61%   |
| pl_PL   | 30        | 2.11%   |
| es_ES   | 30        | 2.11%   |
| en_AU   | 30        | 2.11%   |
| pt_BR   | 23        | 1.62%   |
| sk_SK   | 17        | 1.2%    |
| es_AR   | 14        | 0.99%   |
| en_CA   | 12        | 0.85%   |
| tr_TR   | 11        | 0.77%   |
| hu_HU   | 10        | 0.7%    |
| es_MX   | 10        | 0.7%    |
| nl_NL   | 9         | 0.63%   |
| en_NZ   | 9         | 0.63%   |
| es_VE   | 8         | 0.56%   |
| en_IE   | 8         | 0.56%   |
| de_CH   | 8         | 0.56%   |
| de_AT   | 8         | 0.56%   |
| fi_FI   | 7         | 0.49%   |
| es_BO   | 6         | 0.42%   |
| nl_BE   | 5         | 0.35%   |
| sv_SE   | 4         | 0.28%   |
| hr_HR   | 4         | 0.28%   |
| es_CO   | 4         | 0.28%   |
| el_GR   | 4         | 0.28%   |
| C       | 4         | 0.28%   |
| uk_UA   | 3         | 0.21%   |
| ja_JP   | 3         | 0.21%   |
| fr_CH   | 3         | 0.21%   |
| fr_CA   | 3         | 0.21%   |
| fr_BE   | 3         | 0.21%   |
| es_PE   | 3         | 0.21%   |
| bg_BG   | 3         | 0.21%   |
| zh_TW   | 2         | 0.14%   |
| zh_CN   | 2         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 887       | 63.18%  |
| BIOS | 517       | 36.82%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1249      | 88.52%  |
| Overlay  | 109       | 7.73%   |
| Btrfs    | 39        | 2.76%   |
| Tmpfs    | 5         | 0.35%   |
| Xfs      | 3         | 0.21%   |
| Ext3     | 2         | 0.14%   |
| Unknown  | 2         | 0.14%   |
| Reiserfs | 1         | 0.07%   |
| F2fs     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 1003      | 71.24%  |
| MBR     | 398       | 28.27%  |
| Unknown | 7         | 0.5%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1117      | 78.44%  |
| Yes       | 307       | 21.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 856       | 60.62%  |
| Yes       | 556       | 39.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 208       | 14.84%  |
| Lenovo                               | 195       | 13.91%  |
| ASUSTek Computer                     | 191       | 13.62%  |
| Dell                                 | 182       | 12.98%  |
| Acer                                 | 82        | 5.85%   |
| Gigabyte Technology                  | 64        | 4.56%   |
| Apple                                | 63        | 4.49%   |
| MSI                                  | 58        | 4.14%   |
| ASRock                               | 39        | 2.78%   |
| Toshiba                              | 27        | 1.93%   |
| Intel                                | 27        | 1.93%   |
| Unknown                              | 23        | 1.64%   |
| Medion                               | 19        | 1.36%   |
| Sony                                 | 17        | 1.21%   |
| Samsung Electronics                  | 16        | 1.14%   |
| Google                               | 12        | 0.86%   |
| Fujitsu Siemens                      | 11        | 0.78%   |
| Fujitsu                              | 10        | 0.71%   |
| Foxconn                              | 7         | 0.5%    |
| AZW                                  | 7         | 0.5%    |
| AMI                                  | 7         | 0.5%    |
| ZOTAC                                | 6         | 0.43%   |
| Microsoft                            | 6         | 0.43%   |
| Alienware                            | 6         | 0.43%   |
| Pegatron                             | 5         | 0.36%   |
| Gateway                              | 5         | 0.36%   |
| Raspberry Pi Foundation              | 4         | 0.29%   |
| Notebook                             | 4         | 0.29%   |
| ECS                                  | 4         | 0.29%   |
| Biostar                              | 4         | 0.29%   |
| Shenzhen Meigao Electronic Equipment | 3         | 0.21%   |
| Packard Bell                         | 3         | 0.21%   |
| Wortmann AG                          | 2         | 0.14%   |
| TUXEDO                               | 2         | 0.14%   |
| Semp Toshiba                         | 2         | 0.14%   |
| Razer                                | 2         | 0.14%   |
| Panasonic                            | 2         | 0.14%   |
| HONOR                                | 2         | 0.14%   |
| GPU Company                          | 2         | 0.14%   |
| GEEKOM                               | 2         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 28        | 2%      |
| ASUS All Series                                   | 12        | 0.86%   |
| HP Notebook                                       | 7         | 0.5%    |
| Apple MacBookPro7,1                               | 7         | 0.5%    |
| Intel powered classmate PC                        | 6         | 0.43%   |
| MSI MS-7C91                                       | 4         | 0.29%   |
| Dell Latitude E6540                               | 4         | 0.29%   |
| AZW SER                                           | 4         | 0.29%   |
| Samsung 305E4A/305E5A/305E7A                      | 3         | 0.21%   |
| Microsoft Surface Pro 3                           | 3         | 0.21%   |
| Lenovo ThinkBook 15 G3 ACL 21A4                   | 3         | 0.21%   |
| HP Pavilion Laptop 15-eh1xxx                      | 3         | 0.21%   |
| HP Pavilion g6                                    | 3         | 0.21%   |
| HP Pavilion dv7                                   | 3         | 0.21%   |
| HP Pavilion 15                                    | 3         | 0.21%   |
| HP EliteDesk 800 G1 USDT                          | 3         | 0.21%   |
| HP 255 15.6 inch G9 Notebook PC                   | 3         | 0.21%   |
| HP 250 15.6 inch G9 Notebook PC                   | 3         | 0.21%   |
| Foxconn Pro3500 Series                            | 3         | 0.21%   |
| Dell Vostro 3500                                  | 3         | 0.21%   |
| Dell OptiPlex 9020                                | 3         | 0.21%   |
| Dell OptiPlex 9010                                | 3         | 0.21%   |
| Dell OptiPlex 755                                 | 3         | 0.21%   |
| ASUS PRIME B450M-A                                | 3         | 0.21%   |
| ASUS M5A97 R2.0                                   | 3         | 0.21%   |
| Apple MacBookAir7,2                               | 3         | 0.21%   |
| Apple MacBookAir6,2                               | 3         | 0.21%   |
| Apple MacBookAir1,1                               | 3         | 0.21%   |
| Toshiba Satellite P875                            | 2         | 0.14%   |
| Toshiba Satellite C70-B                           | 2         | 0.14%   |
| Toshiba Satellite A300                            | 2         | 0.14%   |
| Toshiba PORTEGE Z30-C                             | 2         | 0.14%   |
| Shenzhen Meigao Electronic Equipment Venus series | 2         | 0.14%   |
| Samsung N150/N210/N220                            | 2         | 0.14%   |
| RPi Raspberry Pi 5 Model B Rev 1.0                | 2         | 0.14%   |
| MSI MS-7B86                                       | 2         | 0.14%   |
| MSI MS-7A34                                       | 2         | 0.14%   |
| MSI MS-7641                                       | 2         | 0.14%   |
| Lenovo V17 G3 IAP 82U1                            | 2         | 0.14%   |
| Lenovo ThinkPad T500 20552CU                      | 2         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 95        | 6.78%   |
| Dell Latitude         | 60        | 4.28%   |
| Acer Aspire           | 52        | 3.71%   |
| Dell Inspiron         | 39        | 2.78%   |
| Dell OptiPlex         | 33        | 2.35%   |
| ASUS Vivobook         | 31        | 2.21%   |
| HP Pavilion           | 30        | 2.14%   |
| Lenovo IdeaPad        | 28        | 2%      |
| Unknown               | 28        | 2%      |
| ASUS PRIME            | 24        | 1.71%   |
| HP ProBook            | 23        | 1.64%   |
| Toshiba Satellite     | 20        | 1.43%   |
| HP Laptop             | 20        | 1.43%   |
| HP Compaq             | 18        | 1.28%   |
| HP EliteBook          | 17        | 1.21%   |
| Lenovo ThinkCentre    | 13        | 0.93%   |
| ASUS ROG              | 13        | 0.93%   |
| Dell Vostro           | 12        | 0.86%   |
| ASUS TUF              | 12        | 0.86%   |
| ASUS All              | 12        | 0.86%   |
| Dell Precision        | 10        | 0.71%   |
| Dell XPS              | 9         | 0.64%   |
| HP ENVY               | 8         | 0.57%   |
| HP 255                | 8         | 0.57%   |
| HP 250                | 8         | 0.57%   |
| Fujitsu Siemens AMILO | 8         | 0.57%   |
| HP ZBook              | 7         | 0.5%    |
| HP Notebook           | 7         | 0.5%    |
| Apple MacBookPro7     | 7         | 0.5%    |
| Microsoft Surface     | 6         | 0.43%   |
| Lenovo Yoga           | 6         | 0.43%   |
| Lenovo ThinkBook      | 6         | 0.43%   |
| Lenovo IdeaCentre     | 6         | 0.43%   |
| Intel powered         | 6         | 0.43%   |
| HP Spectre            | 6         | 0.43%   |
| HP EliteDesk          | 6         | 0.43%   |
| Dell System           | 6         | 0.43%   |
| Dell Studio           | 6         | 0.43%   |
| Toshiba PORTEGE       | 5         | 0.36%   |
| Lenovo MIIX           | 5         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 112       | 7.99%   |
| 2013    | 108       | 7.7%    |
| 2018    | 102       | 7.28%   |
| 2012    | 96        | 6.85%   |
| 2020    | 94        | 6.7%    |
| 2011    | 92        | 6.56%   |
| 2019    | 85        | 6.06%   |
| 2022    | 77        | 5.49%   |
| 2016    | 76        | 5.42%   |
| 2010    | 74        | 5.28%   |
| 2015    | 64        | 4.56%   |
| 2014    | 62        | 4.42%   |
| 2017    | 60        | 4.28%   |
| 2009    | 60        | 4.28%   |
| 2023    | 59        | 4.21%   |
| 2008    | 59        | 4.21%   |
| 2007    | 37        | 2.64%   |
| 2024    | 36        | 2.57%   |
| 2006    | 24        | 1.71%   |
| 2025    | 10        | 0.71%   |
| 2005    | 9         | 0.64%   |
| Unknown | 4         | 0.29%   |
| 2004    | 2         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 832       | 59.34%  |
| Desktop        | 431       | 30.74%  |
| Mini pc        | 43        | 3.07%   |
| Convertible    | 34        | 2.43%   |
| All in one     | 27        | 1.93%   |
| Tablet         | 24        | 1.71%   |
| Server         | 7         | 0.5%    |
| System on chip | 4         | 0.29%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1383      | 98.57%  |
| Enabled  | 20        | 1.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1386      | 98.86%  |
| Yes  | 16        | 1.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 333       | 23.63%  |
| 8.01-16.0   | 257       | 18.24%  |
| 16.01-24.0  | 247       | 17.53%  |
| 3.01-4.0    | 234       | 16.61%  |
| 32.01-64.0  | 149       | 10.57%  |
| 1.01-2.0    | 90        | 6.39%   |
| 2.01-3.0    | 36        | 2.56%   |
| 24.01-32.0  | 26        | 1.85%   |
| 64.01-256.0 | 24        | 1.7%    |
| 0.51-1.0    | 13        | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 506       | 34.31%  |
| 2.01-3.0   | 446       | 30.24%  |
| 3.01-4.0   | 203       | 13.76%  |
| 4.01-8.0   | 177       | 12%     |
| 0.51-1.0   | 92        | 6.24%   |
| 8.01-16.0  | 37        | 2.51%   |
| 0.01-0.5   | 8         | 0.54%   |
| 16.01-24.0 | 4         | 0.27%   |
| 24.01-32.0 | 2         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 898       | 63.06%  |
| 2      | 337       | 23.67%  |
| 3      | 111       | 7.79%   |
| 4      | 38        | 2.67%   |
| 5      | 19        | 1.33%   |
| 0      | 10        | 0.7%    |
| 8      | 4         | 0.28%   |
| 7      | 3         | 0.21%   |
| 6      | 3         | 0.21%   |
| 9      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 910       | 64.68%  |
| Yes       | 497       | 35.32%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1199      | 85.52%  |
| No        | 203       | 14.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1134      | 80.65%  |
| No        | 272       | 19.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 887       | 63.04%  |
| No        | 520       | 36.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 298       | 21.13%  |
| Germany      | 181       | 12.84%  |
| Italy        | 81        | 5.74%   |
| UK           | 60        | 4.26%   |
| Canada       | 52        | 3.69%   |
| France       | 50        | 3.55%   |
| Russia       | 46        | 3.26%   |
| Spain        | 40        | 2.84%   |
| Australia    | 40        | 2.84%   |
| Brazil       | 38        | 2.7%    |
| Poland       | 37        | 2.62%   |
| India        | 36        | 2.55%   |
| Greece       | 27        | 1.91%   |
| Netherlands  | 24        | 1.7%    |
| Slovakia     | 22        | 1.56%   |
| Indonesia    | 18        | 1.28%   |
| Austria      | 18        | 1.28%   |
| Finland      | 17        | 1.21%   |
| Serbia       | 16        | 1.13%   |
| Sweden       | 15        | 1.06%   |
| Mexico       | 15        | 1.06%   |
| Belgium      | 15        | 1.06%   |
| Argentina    | 15        | 1.06%   |
| Hungary      | 14        | 0.99%   |
| Turkey       | 13        | 0.92%   |
| Switzerland  | 12        | 0.85%   |
| Romania      | 12        | 0.85%   |
| New Zealand  | 11        | 0.78%   |
| Ukraine      | 10        | 0.71%   |
| Venezuela    | 9         | 0.64%   |
| Norway       | 8         | 0.57%   |
| Ireland      | 8         | 0.57%   |
| South Africa | 7         | 0.5%    |
| Colombia     | 7         | 0.5%    |
| Chile        | 7         | 0.5%    |
| Bolivia      | 7         | 0.5%    |
| Portugal     | 6         | 0.43%   |
| Egypt        | 6         | 0.43%   |
| Thailand     | 5         | 0.35%   |
| Singapore    | 5         | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Berlin         | 21        | 1.44%   |
| Bratislava     | 18        | 1.23%   |
| Athens         | 17        | 1.17%   |
| Moscow         | 16        | 1.1%    |
| Vienna         | 15        | 1.03%   |
| Sydney         | 14        | 0.96%   |
| Munich         | 12        | 0.82%   |
| Milan          | 12        | 0.82%   |
| Melbourne      | 12        | 0.82%   |
| Paris          | 11        | 0.75%   |
| Warsaw         | 10        | 0.69%   |
| St Petersburg  | 10        | 0.69%   |
| Seattle        | 9         | 0.62%   |
| Budapest       | 9         | 0.62%   |
| Hamburg        | 8         | 0.55%   |
| Bengaluru      | 8         | 0.55%   |
| Belgrade       | 8         | 0.55%   |
| Rome           | 7         | 0.48%   |
| Los Angeles    | 7         | 0.48%   |
| La Paz         | 7         | 0.48%   |
| Montreal       | 6         | 0.41%   |
| Krakow         | 6         | 0.41%   |
| Florence       | 6         | 0.41%   |
| Dublin         | 6         | 0.41%   |
| Amsterdam      | 6         | 0.41%   |
| Stockholm      | 5         | 0.34%   |
| Singapore      | 5         | 0.34%   |
| Rio de Janeiro | 5         | 0.34%   |
| Madrid         | 5         | 0.34%   |
| Helsinki       | 5         | 0.34%   |
| Cranston       | 5         | 0.34%   |
| Calgary        | 5         | 0.34%   |
| Bogotá        | 5         | 0.34%   |
| Toronto        | 4         | 0.27%   |
| Stuttgart      | 4         | 0.27%   |
| San Diego      | 4         | 0.27%   |
| Portland       | 4         | 0.27%   |
| Patna          | 4         | 0.27%   |
| Otwock         | 4         | 0.27%   |
| Kyiv           | 4         | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 282       | 374    | 14.02%  |
| WDC                 | 261       | 315    | 12.97%  |
| Seagate             | 220       | 299    | 10.93%  |
| Kingston            | 116       | 127    | 5.77%   |
| SanDisk             | 112       | 123    | 5.57%   |
| Crucial             | 104       | 154    | 5.17%   |
| Unknown             | 97        | 116    | 4.82%   |
| Toshiba             | 93        | 106    | 4.62%   |
| SK hynix            | 68        | 70     | 3.38%   |
| Hitachi             | 55        | 68     | 2.73%   |
| Intel               | 47        | 62     | 2.34%   |
| Micron Technology   | 32        | 38     | 1.59%   |
| China               | 32        | 40     | 1.59%   |
| Unknown             | 31        | 31     | 1.54%   |
| A-DATA Technology   | 28        | 34     | 1.39%   |
| HGST                | 26        | 35     | 1.29%   |
| SPCC                | 24        | 24     | 1.19%   |
| Apple               | 23        | 28     | 1.14%   |
| KIOXIA              | 21        | 26     | 1.04%   |
| Intenso             | 20        | 20     | 0.99%   |
| PNY                 | 18        | 20     | 0.89%   |
| Lexar               | 12        | 14     | 0.6%    |
| Transcend           | 10        | 10     | 0.5%    |
| Team                | 10        | 12     | 0.5%    |
| Silicon Motion      | 10        | 11     | 0.5%    |
| Patriot             | 10        | 13     | 0.5%    |
| Netac               | 9         | 10     | 0.45%   |
| Fujitsu             | 9         | 9      | 0.45%   |
| Phison              | 8         | 10     | 0.4%    |
| LITEON              | 8         | 8      | 0.4%    |
| GOODRAM             | 8         | 9      | 0.4%    |
| Corsair             | 8         | 8      | 0.4%    |
| Apacer              | 8         | 8      | 0.4%    |
| Maxtor              | 7         | 8      | 0.35%   |
| FORESEE             | 7         | 7      | 0.35%   |
| Phison Electronics  | 6         | 7      | 0.3%    |
| LITEONIT            | 6         | 6      | 0.3%    |
| OCZ                 | 5         | 5      | 0.25%   |
| Mushkin             | 5         | 5      | 0.25%   |
| KingSpec            | 5         | 6      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 31        | 1.43%   |
| Kingston SA400S37240G 240GB SSD    | 20        | 0.92%   |
| Samsung SSD 860 EVO 500GB          | 18        | 0.83%   |
| Kingston SA400S37480G 480GB SSD    | 16        | 0.74%   |
| SanDisk NVMe SSD Drive 1TB         | 15        | 0.69%   |
| Samsung SSD 850 EVO 250GB          | 14        | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB     | 13        | 0.6%    |
| Kingston SV300S37A120G 120GB SSD   | 13        | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB       | 12        | 0.55%   |
| Kingston SA400S37120G 120GB SSD    | 12        | 0.55%   |
| Seagate ST500DM002-1BD142 500GB    | 11        | 0.51%   |
| Unknown SD/MMC/MS PRO 2GB          | 10        | 0.46%   |
| Samsung SSD 850 EVO 500GB          | 10        | 0.46%   |
| Crucial CT500MX500SSD1 500GB       | 10        | 0.46%   |
| Crucial CT240BX500SSD1 240GB       | 10        | 0.46%   |
| Toshiba MQ01ABF050 500GB           | 9         | 0.42%   |
| Seagate ST4000DM004-2CV104 4TB     | 9         | 0.42%   |
| Seagate ST2000DM008-2FR102 2TB     | 9         | 0.42%   |
| SanDisk NVMe SSD Drive 512GB       | 9         | 0.42%   |
| Samsung SSD 870 EVO 500GB          | 9         | 0.42%   |
| HGST HTS721010A9E630 1TB           | 9         | 0.42%   |
| Crucial CT1000MX500SSD1 1TB        | 9         | 0.42%   |
| Toshiba MQ01ABD100 1TB             | 8         | 0.37%   |
| SK hynix HBG4e  32GB               | 8         | 0.37%   |
| Samsung SSD 860 EVO 250GB          | 8         | 0.37%   |
| Intel SSDPEKNU512GZ 512GB          | 8         | 0.37%   |
| Toshiba DT01ACA100 1TB             | 7         | 0.32%   |
| Seagate ST9500325AS 500GB          | 7         | 0.32%   |
| Seagate ST500LM021-1KJ152 500GB    | 7         | 0.32%   |
| Seagate ST1000DM010-2EP102 1TB     | 7         | 0.32%   |
| Seagate Expansion 2TB              | 7         | 0.32%   |
| Samsung SSD 980 PRO 1TB            | 7         | 0.32%   |
| Samsung SSD 870 EVO 1TB            | 7         | 0.32%   |
| Crucial CT120BX500SSD1 120GB       | 7         | 0.32%   |
| WDC WD10EZEX-00BN5A0 1TB           | 6         | 0.28%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.28%   |
| Seagate ST1000DM003-1SB102 1TB     | 6         | 0.28%   |
| SanDisk SSD PLUS 1000GB            | 6         | 0.28%   |
| Samsung SSD 980 500GB              | 6         | 0.28%   |
| Samsung SSD 970 EVO Plus 500GB     | 6         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 218       | 293    | 34.22%  |
| WDC                 | 195       | 238    | 30.61%  |
| Toshiba             | 73        | 83     | 11.46%  |
| Hitachi             | 55        | 68     | 8.63%   |
| Samsung Electronics | 26        | 33     | 4.08%   |
| HGST                | 26        | 35     | 4.08%   |
| Unknown             | 11        | 11     | 1.73%   |
| Fujitsu             | 9         | 9      | 1.41%   |
| Maxtor              | 7         | 8      | 1.1%    |
| Apple               | 5         | 5      | 0.78%   |
| Hewlett-Packard     | 3         | 8      | 0.47%   |
| External            | 3         | 4      | 0.47%   |
| Intenso             | 2         | 2      | 0.31%   |
| Space ke            | 1         | 2      | 0.16%   |
| IBM/Hitachi         | 1         | 1      | 0.16%   |
| ASMT                | 1         | 1      | 0.16%   |
| Unknown             | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 143       | 182    | 19.07%  |
| Kingston            | 88        | 97     | 11.73%  |
| Crucial             | 80        | 120    | 10.67%  |
| SanDisk             | 62        | 66     | 8.27%   |
| WDC                 | 36        | 38     | 4.8%    |
| China               | 30        | 38     | 4%      |
| A-DATA Technology   | 21        | 26     | 2.8%    |
| SPCC                | 19        | 19     | 2.53%   |
| Intenso             | 17        | 17     | 2.27%   |
| Intel               | 16        | 22     | 2.13%   |
| PNY                 | 15        | 16     | 2%      |
| Apple               | 15        | 18     | 2%      |
| Micron Technology   | 14        | 20     | 1.87%   |
| SK hynix            | 12        | 12     | 1.6%    |
| Transcend           | 10        | 10     | 1.33%   |
| GOODRAM             | 8         | 9      | 1.07%   |
| Patriot             | 7         | 9      | 0.93%   |
| LITEON              | 7         | 7      | 0.93%   |
| Toshiba             | 6         | 6      | 0.8%    |
| Team                | 6         | 6      | 0.8%    |
| Netac               | 6         | 6      | 0.8%    |
| LITEONIT            | 6         | 6      | 0.8%    |
| OCZ                 | 5         | 5      | 0.67%   |
| KingSpec            | 5         | 6      | 0.67%   |
| Apacer              | 5         | 5      | 0.67%   |
| Unknown             | 5         | 5      | 0.67%   |
| Verbatim            | 4         | 4      | 0.53%   |
| Lexar               | 4         | 4      | 0.53%   |
| KingFast            | 4         | 5      | 0.53%   |
| T-FORCE             | 3         | 3      | 0.4%    |
| SABRENT             | 3         | 6      | 0.4%    |
| Mushkin             | 3         | 3      | 0.4%    |
| HS-SSD-C100         | 3         | 4      | 0.4%    |
| Gigabyte Technology | 3         | 3      | 0.4%    |
| FORESEE             | 3         | 3      | 0.4%    |
| Fanxiang            | 3         | 3      | 0.4%    |
| Dogfish             | 3         | 3      | 0.4%    |
| Corsair             | 3         | 3      | 0.4%    |
| BIWIN               | 3         | 4      | 0.4%    |
| WALRAM              | 2         | 2      | 0.27%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 658       | 892    | 36.51%  |
| HDD     | 547       | 802    | 30.36%  |
| NVMe    | 467       | 595    | 25.92%  |
| MMC     | 114       | 140    | 6.33%   |
| Unknown | 16        | 22     | 0.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 973       | 1610   | 59.47%  |
| NVMe | 466       | 588    | 28.48%  |
| MMC  | 114       | 140    | 6.97%   |
| SAS  | 83        | 113    | 5.07%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 765       | 1049   | 62.14%  |
| 0.51-1.0   | 312       | 426    | 25.35%  |
| 1.01-2.0   | 93        | 123    | 7.55%   |
| 3.01-4.0   | 33        | 40     | 2.68%   |
| 2.01-3.0   | 14        | 18     | 1.14%   |
| 4.01-10.0  | 12        | 34     | 0.97%   |
| 10.01-20.0 | 2         | 4      | 0.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 399       | 27.54%  |
| 251-500        | 298       | 20.57%  |
| 501-1000       | 202       | 13.94%  |
| 51-100         | 135       | 9.32%   |
| 21-50          | 110       | 7.59%   |
| 1-20           | 109       | 7.52%   |
| 1001-2000      | 84        | 5.8%    |
| More than 3000 | 66        | 4.55%   |
| 2001-3000      | 41        | 2.83%   |
| Unknown        | 5         | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 623       | 42.47%  |
| 21-50          | 243       | 16.56%  |
| 101-250        | 177       | 12.07%  |
| 51-100         | 158       | 10.77%  |
| 251-500        | 98        | 6.68%   |
| 501-1000       | 71        | 4.84%   |
| 1001-2000      | 49        | 3.34%   |
| More than 3000 | 29        | 1.98%   |
| 2001-3000      | 14        | 0.95%   |
| Unknown        | 5         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 6         | 6      | 2.2%    |
| Toshiba MQ01ABD100 1TB               | 4         | 4      | 1.47%   |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 4      | 1.47%   |
| HGST HTS545050A7E680 500GB           | 4         | 5      | 1.47%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 3         | 3      | 1.1%    |
| WDC WD10EZEX-75M2NA0 1TB             | 3         | 4      | 1.1%    |
| Toshiba MQ01ABF050 500GB             | 3         | 3      | 1.1%    |
| SK hynix BC711 HFM512GD3JX013N 512GB | 3         | 4      | 1.1%    |
| Seagate ST500LT012-9WS142 500GB      | 3         | 3      | 1.1%    |
| Seagate ST500LM000-1EJ162 500GB      | 3         | 3      | 1.1%    |
| Seagate ST500DM002-1BD142 500GB      | 3         | 3      | 1.1%    |
| Hitachi HTS545050A7E380 500GB        | 3         | 3      | 1.1%    |
| WDC WD40EZRX-00SPEB0 4TB             | 2         | 2      | 0.73%   |
| WDC WD Green 2.5 240GB               | 2         | 2      | 0.73%   |
| Toshiba MK7575GSX 752GB              | 2         | 3      | 0.73%   |
| Toshiba MK5059GSXP 500GB             | 2         | 2      | 0.73%   |
| Seagate ST500LM021-1KJ152 500GB      | 2         | 2      | 0.73%   |
| Seagate ST31000524AS 1TB             | 2         | 2      | 0.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 2         | 2      | 0.73%   |
| Seagate ST1000DM003-9YN162 1TB       | 2         | 2      | 0.73%   |
| SanDisk SSD PLUS 480GB               | 2         | 2      | 0.73%   |
| SanDisk SSD PLUS 1000GB              | 2         | 2      | 0.73%   |
| Samsung Electronics HM250HI 250GB    | 2         | 3      | 0.73%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 2      | 0.73%   |
| Indilinx IND-S325S120G 120GB SSD     | 2         | 4      | 0.73%   |
| Hitachi HUA722020ALA331 2TB          | 2         | 2      | 0.73%   |
| Hitachi HTS543225L9A300 250GB        | 2         | 2      | 0.73%   |
| HGST HTS721010A9E630 1TB             | 2         | 2      | 0.73%   |
| HGST HTS545050A7E380 500GB           | 2         | 5      | 0.73%   |
| China SSD 512GB                      | 2         | 2      | 0.73%   |
| A-DATA Technology SU650 240GB SSD    | 2         | 2      | 0.73%   |
| YANSEN YSZF18-128 128GB SSD          | 1         | 1      | 0.37%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 1      | 0.37%   |
| WDC WDS100T2B0A-00SM50 1TB SSD       | 1         | 1      | 0.37%   |
| WDC WD6400AACS-00G8B1 640GB          | 1         | 1      | 0.37%   |
| WDC WD5003ABYX-01WERA1 500GB         | 1         | 1      | 0.37%   |
| WDC WD5000LPCX-00VHAT0 500GB         | 1         | 1      | 0.37%   |
| WDC WD5000LPCX-0 500GB               | 1         | 1      | 0.37%   |
| WDC WD5000BPVT-60HXZT3 500GB         | 1         | 1      | 0.37%   |
| WDC WD5000AAKS-40V6A0 500GB          | 1         | 1      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 64        | 74     | 23.97%  |
| WDC                 | 52        | 59     | 19.48%  |
| Hitachi             | 26        | 29     | 9.74%   |
| Samsung Electronics | 22        | 29     | 8.24%   |
| Toshiba             | 21        | 23     | 7.87%   |
| HGST                | 12        | 16     | 4.49%   |
| SK hynix            | 7         | 8      | 2.62%   |
| Intel               | 7         | 10     | 2.62%   |
| SanDisk             | 6         | 6      | 2.25%   |
| Crucial             | 6         | 28     | 2.25%   |
| Fujitsu             | 5         | 5      | 1.87%   |
| Maxtor              | 4         | 4      | 1.5%    |
| Kingston            | 4         | 4      | 1.5%    |
| China               | 4         | 4      | 1.5%    |
| A-DATA Technology   | 3         | 4      | 1.12%   |
| Netac               | 2         | 2      | 0.75%   |
| Micron Technology   | 2         | 2      | 0.75%   |
| Intenso             | 2         | 2      | 0.75%   |
| Indilinx            | 2         | 4      | 0.75%   |
| Apple               | 2         | 2      | 0.75%   |
| YANSEN              | 1         | 1      | 0.37%   |
| V-GeN               | 1         | 1      | 0.37%   |
| SPCC                | 1         | 1      | 0.37%   |
| RENICE              | 1         | 1      | 0.37%   |
| Phison              | 1         | 1      | 0.37%   |
| OCZ                 | 1         | 1      | 0.37%   |
| LITEONIT            | 1         | 1      | 0.37%   |
| Lexar               | 1         | 1      | 0.37%   |
| Lenovo              | 1         | 1      | 0.37%   |
| KingSpec            | 1         | 1      | 0.37%   |
| IBM/Hitachi         | 1         | 1      | 0.37%   |
| GOODRAM             | 1         | 1      | 0.37%   |
| ADATA Technology    | 1         | 1      | 0.37%   |
| Unknown             | 1         | 1      | 0.37%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 64        | 74     | 33.51%  |
| WDC                 | 47        | 54     | 24.61%  |
| Hitachi             | 26        | 29     | 13.61%  |
| Toshiba             | 20        | 22     | 10.47%  |
| HGST                | 12        | 16     | 6.28%   |
| Samsung Electronics | 11        | 14     | 5.76%   |
| Fujitsu             | 5         | 5      | 2.62%   |
| Maxtor              | 4         | 4      | 2.09%   |
| IBM/Hitachi         | 1         | 1      | 0.52%   |
| Unknown             | 1         | 1      | 0.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 182       | 220    | 70.82%  |
| SSD  | 63        | 90     | 24.51%  |
| NVMe | 12        | 19     | 4.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Toshiba MK5065GSX 500GB             | 2         | 2      | 40%     |
| WDC WD3200AAJS-00B4A0 320GB         | 1         | 1      | 20%     |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 20%     |
| Seagate ST3500418AS 500GB           | 1         | 2      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 40%     |
| Seagate | 2         | 3      | 40%     |
| WDC     | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1134      | 1799   | 69.7%   |
| Malfunc  | 251       | 329    | 15.43%  |
| Detected | 236       | 316    | 14.51%  |
| Failed   | 5         | 6      | 0.31%   |
| Fixed    | 1         | 1      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 886       | 51.6%   |
| AMD                                     | 241       | 14.04%  |
| Samsung Electronics                     | 132       | 7.69%   |
| SanDisk                                 | 76        | 4.43%   |
| SK hynix                                | 44        | 2.56%   |
| Nvidia                                  | 35        | 2.04%   |
| Kingston Technology Company             | 32        | 1.86%   |
| Phison Electronics                      | 28        | 1.63%   |
| Micron Technology                       | 25        | 1.46%   |
| KIOXIA                                  | 24        | 1.4%    |
| ASMedia Technology                      | 24        | 1.4%    |
| Silicon Motion                          | 21        | 1.22%   |
| Micron/Crucial Technology               | 20        | 1.16%   |
| Marvell Technology Group                | 16        | 0.93%   |
| JMicron Technology                      | 15        | 0.87%   |
| Toshiba America Info Systems            | 12        | 0.7%    |
| Shenzhen Longsys Electronics            | 11        | 0.64%   |
| ADATA Technology                        | 11        | 0.64%   |
| Realtek Semiconductor                   | 9         | 0.52%   |
| MAXIO Technology (Hangzhou)             | 9         | 0.52%   |
| VIA Technologies                        | 5         | 0.29%   |
| Silicon Image                           | 4         | 0.23%   |
| LSI Logic / Symbios Logic               | 4         | 0.23%   |
| Hewlett-Packard                         | 4         | 0.23%   |
| Union Memory (Shenzhen)                 | 3         | 0.17%   |
| Unknown                                 | 3         | 0.17%   |
| ULi Electronics                         | 2         | 0.12%   |
| Solid State Storage Technology          | 2         | 0.12%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.12%   |
| Lite-On Technology                      | 2         | 0.12%   |
| Lenovo                                  | 2         | 0.12%   |
| Broadcom / LSI                          | 2         | 0.12%   |
| Apple                                   | 2         | 0.12%   |
| TenaFe                                  | 1         | 0.06%   |
| Solidigm                                | 1         | 0.06%   |
| Shenzhen Unionmemory Information System | 1         | 0.06%   |
| O2 Micro                                | 1         | 0.06%   |
| Nextorage                               | 1         | 0.06%   |
| Netac Technology                        | 1         | 0.06%   |
| Integrated Technology Express           | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 147       | 7.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 70        | 3.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 55        | 2.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 52        | 2.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 50        | 2.57%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 48        | 2.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 42        | 2.16%   |
| Intel Volume Management Device NVMe RAID Controller                            | 38        | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 34        | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 28        | 1.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 28        | 1.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 27        | 1.39%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 26        | 1.34%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 26        | 1.34%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 26        | 1.34%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 25        | 1.29%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 25        | 1.29%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 24        | 1.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 23        | 1.18%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 22        | 1.13%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 21        | 1.08%   |
| AMD 500 Series Chipset SATA Controller                                         | 21        | 1.08%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 20        | 1.03%   |
| Intel Tiger Lake-LP SATA Controller                                            | 20        | 1.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 20        | 1.03%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 19        | 0.98%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 19        | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 19        | 0.98%   |
| AMD 400 Series Chipset SATA Controller                                         | 18        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 17        | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 17        | 0.87%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 17        | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 16        | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 16        | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 15        | 0.77%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 15        | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 15        | 0.77%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 15        | 0.77%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 14        | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 979       | 55.88%  |
| NVMe | 459       | 26.2%   |
| IDE  | 190       | 10.84%  |
| RAID | 121       | 6.91%   |
| SCSI | 2         | 0.11%   |
| SAS  | 1         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1065      | 75.96%  |
| AMD          | 332       | 23.68%  |
| ARM          | 4         | 0.29%   |
| CentaurHauls | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 19        | 1.36%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 18        | 1.28%   |
| Intel Atom CPU Z3735F @ 1.33GHz         | 17        | 1.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 17        | 1.21%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 13        | 0.93%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 12        | 0.86%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 11        | 0.78%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 10        | 0.71%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 0.71%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz       | 10        | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 9         | 0.64%   |
| Intel Core i7-3770 CPU @ 3.40GHz        | 9         | 0.64%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 9         | 0.64%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 8         | 0.57%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 8         | 0.57%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 8         | 0.57%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 8         | 0.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 8         | 0.57%   |
| Intel 12th Gen Core i5-1235U            | 8         | 0.57%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 7         | 0.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 0.5%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 7         | 0.5%    |
| Intel Celeron N4020 CPU @ 1.10GHz       | 7         | 0.5%    |
| Intel Celeron CPU N3350 @ 1.10GHz       | 7         | 0.5%    |
| Intel Celeron CPU 847 @ 1.10GHz         | 7         | 0.5%    |
| AMD Ryzen 5 5600H with Radeon Graphics  | 7         | 0.5%    |
| Intel Core Ultra 7 155H                 | 6         | 0.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 0.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 6         | 0.43%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 6         | 0.43%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 6         | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 6         | 0.43%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 6         | 0.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz       | 6         | 0.43%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz    | 6         | 0.43%   |
| Intel 12th Gen Core i5-12450H           | 6         | 0.43%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 6         | 0.43%   |
| AMD Ryzen 5 5625U with Radeon Graphics  | 6         | 0.43%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 6         | 0.43%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 5         | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 285       | 20.33%  |
| Intel Core i7           | 193       | 13.77%  |
| Other                   | 134       | 9.56%   |
| Intel Celeron           | 91        | 6.49%   |
| Intel Core 2 Duo        | 89        | 6.35%   |
| Intel Core i3           | 87        | 6.21%   |
| AMD Ryzen 5             | 86        | 6.13%   |
| AMD Ryzen 7             | 69        | 4.92%   |
| Intel Atom              | 57        | 4.07%   |
| Intel Pentium           | 27        | 1.93%   |
| AMD Ryzen 3             | 21        | 1.5%    |
| Intel Xeon              | 20        | 1.43%   |
| AMD Ryzen 9             | 19        | 1.36%   |
| AMD A8                  | 15        | 1.07%   |
| Intel Pentium Dual-Core | 12        | 0.86%   |
| Intel Core 2            | 11        | 0.78%   |
| AMD A4                  | 11        | 0.78%   |
| AMD FX                  | 10        | 0.71%   |
| Intel Core              | 9         | 0.64%   |
| Intel Genuine           | 8         | 0.57%   |
| AMD A6                  | 8         | 0.57%   |
| Intel Pentium Silver    | 7         | 0.5%    |
| Intel Core i9           | 7         | 0.5%    |
| Intel Core 2 Quad       | 7         | 0.5%    |
| AMD Phenom II X4        | 7         | 0.5%    |
| AMD E1                  | 7         | 0.5%    |
| Intel Pentium Dual      | 6         | 0.43%   |
| AMD Athlon              | 6         | 0.43%   |
| AMD A10                 | 6         | 0.43%   |
| Intel Pentium 4         | 5         | 0.36%   |
| AMD E                   | 5         | 0.36%   |
| AMD Athlon II X4        | 5         | 0.36%   |
| AMD Athlon II X2        | 5         | 0.36%   |
| Intel Pentium Gold      | 4         | 0.29%   |
| Intel Celeron M         | 4         | 0.29%   |
| AMD Turion 64 X2 Mobile | 4         | 0.29%   |
| AMD Sempron             | 4         | 0.29%   |
| AMD Phenom II X6        | 4         | 0.29%   |
| AMD E2                  | 4         | 0.29%   |
| AMD Athlon 64 X2        | 4         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 575       | 41.01%  |
| 4       | 452       | 32.24%  |
| 6       | 140       | 9.99%   |
| 8       | 108       | 7.7%    |
| 1       | 45        | 3.21%   |
| 12      | 21        | 1.5%    |
| 10      | 21        | 1.5%    |
| 16      | 13        | 0.93%   |
| 14      | 11        | 0.78%   |
| 24      | 4         | 0.29%   |
| 3       | 4         | 0.29%   |
| Unknown | 4         | 0.29%   |
| 20      | 2         | 0.14%   |
| 5       | 2         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1389      | 99.07%  |
| 2       | 9         | 0.64%   |
| Unknown | 4         | 0.29%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 861       | 61.37%  |
| 1       | 538       | 38.35%  |
| Unknown | 4         | 0.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1374      | 97.93%  |
| 32-bit         | 29        | 2.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 330       | 23.13%  |
| 0x206a7    | 82        | 5.75%   |
| 0x306a9    | 71        | 4.98%   |
| 0x1067a    | 55        | 3.85%   |
| 0x306c3    | 54        | 3.78%   |
| 0x506e3    | 31        | 2.17%   |
| 0x30678    | 31        | 2.17%   |
| 0x806c1    | 30        | 2.1%    |
| 0x406e3    | 28        | 1.96%   |
| 0x20655    | 28        | 1.96%   |
| 0x40651    | 27        | 1.89%   |
| 0x906ea    | 22        | 1.54%   |
| 0x806ec    | 22        | 1.54%   |
| 0x406c4    | 20        | 1.4%    |
| 0x806ea    | 19        | 1.33%   |
| 0x806e9    | 19        | 1.33%   |
| 0x6fd      | 19        | 1.33%   |
| 0x306d4    | 19        | 1.33%   |
| 0x0a50000c | 19        | 1.33%   |
| 0x08608103 | 18        | 1.26%   |
| 0x906e9    | 16        | 1.12%   |
| 0x706a8    | 14        | 0.98%   |
| 0x706a1    | 13        | 0.91%   |
| 0x906a4    | 12        | 0.84%   |
| 0x906a3    | 12        | 0.84%   |
| 0x506c9    | 12        | 0.84%   |
| 0x10676    | 12        | 0.84%   |
| 0x6fb      | 11        | 0.77%   |
| 0xa0653    | 10        | 0.7%    |
| 0x20652    | 10        | 0.7%    |
| 0x08701021 | 10        | 0.7%    |
| 0x08108109 | 10        | 0.7%    |
| 0x0800820d | 10        | 0.7%    |
| 0x906ed    | 9         | 0.63%   |
| 0x106e5    | 9         | 0.63%   |
| 0x010000c8 | 9         | 0.63%   |
| 0x106c2    | 8         | 0.56%   |
| 0x0600611a | 8         | 0.56%   |
| 0x03000027 | 8         | 0.56%   |
| 0xa0671    | 7         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 154       | 10.97%  |
| Haswell           | 101       | 7.19%   |
| SandyBridge       | 98        | 6.98%   |
| Unknown           | 92        | 6.55%   |
| IvyBridge         | 85        | 6.05%   |
| Penryn            | 84        | 5.98%   |
| Skylake           | 69        | 4.91%   |
| Silvermont        | 65        | 4.63%   |
| Zen 3             | 55        | 3.92%   |
| Alderlake Hybrid  | 53        | 3.77%   |
| TigerLake         | 51        | 3.63%   |
| Core              | 51        | 3.63%   |
| Westmere          | 45        | 3.21%   |
| Zen+              | 35        | 2.49%   |
| Zen 2             | 31        | 2.21%   |
| Goldmont plus     | 29        | 2.07%   |
| K10               | 26        | 1.85%   |
| CometLake         | 26        | 1.85%   |
| IceLake           | 22        | 1.57%   |
| Broadwell         | 22        | 1.57%   |
| Excavator         | 21        | 1.5%    |
| Bonnell           | 19        | 1.35%   |
| Zen               | 16        | 1.14%   |
| Nehalem           | 15        | 1.07%   |
| K8 Hammer         | 15        | 1.07%   |
| Goldmont          | 15        | 1.07%   |
| Piledriver        | 14        | 1%      |
| P6                | 14        | 1%      |
| Puma              | 12        | 0.85%   |
| Bobcat            | 12        | 0.85%   |
| Tremont           | 10        | 0.71%   |
| K10 Llano         | 9         | 0.64%   |
| NetBurst          | 8         | 0.57%   |
| Meteorlake Hybrid | 8         | 0.57%   |
| Jaguar            | 6         | 0.43%   |
| Gracemont         | 5         | 0.36%   |
| Steamroller       | 4         | 0.28%   |
| Bulldozer         | 4         | 0.28%   |
| K6                | 2         | 0.14%   |
| K8 & K10 hybrid   | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 846       | 52.88%  |
| AMD                        | 379       | 23.69%  |
| Nvidia                     | 372       | 23.25%  |
| VIA Technologies           | 2         | 0.13%   |
| Matrox Electronics Systems | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 78        | 4.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 56        | 3.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 44        | 2.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 36        | 2.16%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 32        | 1.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29        | 1.74%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 1.68%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 28        | 1.68%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 27        | 1.62%   |
| AMD Lucienne                                                                             | 27        | 1.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 25        | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 24        | 1.44%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 1.44%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 23        | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 22        | 1.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 18        | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 1.02%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 1.02%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 17        | 1.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 0.84%   |
| AMD Raphael                                                                              | 14        | 0.84%   |
| AMD Barcelo                                                                              | 14        | 0.84%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 13        | 0.78%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 13        | 0.78%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 13        | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 12        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 0.72%   |
| Intel Apollo Lake GT1 [HD Graphics 500]                                                  | 12        | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 12        | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 11        | 0.66%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 11        | 0.66%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 11        | 0.66%   |
| Intel JasperLake [UHD Graphics]                                                          | 11        | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 0.6%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 10        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 634       | 44.87%  |
| 1 x AMD            | 294       | 20.81%  |
| 1 x Nvidia         | 224       | 15.85%  |
| Intel + Nvidia     | 119       | 8.42%   |
| 2 x Intel          | 44        | 3.11%   |
| Intel + AMD        | 37        | 2.62%   |
| AMD + Nvidia       | 26        | 1.84%   |
| 2 x AMD            | 24        | 1.7%    |
| Other              | 4         | 0.28%   |
| 2 x Nvidia         | 2         | 0.14%   |
| 1 x VIA            | 2         | 0.14%   |
| 3 x AMD            | 1         | 0.07%   |
| 1 x Matrox         | 1         | 0.07%   |
| Intel + 2 x Nvidia | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1208      | 85.31%  |
| Proprietary | 142       | 10.03%  |
| Unknown     | 66        | 4.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 868       | 61.21%  |
| 0.01-0.5   | 221       | 15.59%  |
| 1.01-2.0   | 110       | 7.76%   |
| 0.51-1.0   | 88        | 6.21%   |
| 3.01-4.0   | 51        | 3.6%    |
| 7.01-8.0   | 43        | 3.03%   |
| 5.01-6.0   | 15        | 1.06%   |
| 8.01-16.0  | 12        | 0.85%   |
| 2.01-3.0   | 8         | 0.56%   |
| 4.01-5.0   | 1         | 0.07%   |
| 16.01-24.0 | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 188       | 12.63%  |
| Samsung Electronics     | 179       | 12.02%  |
| Chimei Innolux          | 128       | 8.6%    |
| BOE                     | 126       | 8.46%   |
| LG Display              | 109       | 7.32%   |
| Goldstar                | 73        | 4.9%    |
| Dell                    | 69        | 4.63%   |
| Apple                   | 52        | 3.49%   |
| Acer                    | 51        | 3.43%   |
| Hewlett-Packard         | 50        | 3.36%   |
| BenQ                    | 37        | 2.48%   |
| Lenovo                  | 36        | 2.42%   |
| AOC                     | 33        | 2.22%   |
| Chi Mei Optoelectronics | 30        | 2.01%   |
| Ancor Communications    | 25        | 1.68%   |
| Philips                 | 23        | 1.54%   |
| Sony                    | 20        | 1.34%   |
| InfoVision              | 19        | 1.28%   |
| Sharp                   | 15        | 1.01%   |
| ViewSonic               | 14        | 0.94%   |
| PANDA                   | 13        | 0.87%   |
| ASUSTek Computer        | 13        | 0.87%   |
| HannStar                | 12        | 0.81%   |
| LG Philips              | 11        | 0.74%   |
| Iiyama                  | 8         | 0.54%   |
| Eizo                    | 8         | 0.54%   |
| MSI                     | 7         | 0.47%   |
| Vizio                   | 6         | 0.4%    |
| Sceptre Tech            | 6         | 0.4%    |
| Fujitsu Siemens         | 6         | 0.4%    |
| NEC Computers           | 5         | 0.34%   |
| HKC                     | 5         | 0.34%   |
| CPT                     | 5         | 0.34%   |
| Vestel Elektronik       | 4         | 0.27%   |
| Quanta Display          | 4         | 0.27%   |
| Medion                  | 4         | 0.27%   |
| InnoLux Display         | 4         | 0.27%   |
| Hitachi                 | 4         | 0.27%   |
| RTK                     | 3         | 0.2%    |
| Plain Tree Systems      | 3         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 10        | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 9         | 0.6%    |
| Samsung Electronics SyncMaster SAM0091 1600x1200 432x324mm 21.3-inch     | 8         | 0.53%   |
| InfoVision LCD Monitor IVO03FA 1366x768 223x125mm 10.1-inch              | 7         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch    | 6         | 0.4%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.4%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 5         | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 5         | 0.33%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                         | 5         | 0.33%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                       | 5         | 0.33%   |
| Vestel Elektronik 40UHD_LCD_TV VES3700 3840x2160 880x500mm 39.8-inch     | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 4         | 0.27%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 4         | 0.27%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.27%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 4         | 0.27%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch          | 4         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 4         | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 0.27%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                    | 4         | 0.27%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 4         | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 4         | 0.27%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 4         | 0.27%   |
| Vizio E500i-B1 VIZ1004 1920x1080 1095x616mm 49.5-inch                    | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch    | 3         | 0.2%    |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 3         | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 3         | 0.2%    |
| Plain Tree Systems LCD Monitor PTS06A5 1280x1024 340x270mm 17.1-inch     | 3         | 0.2%    |
| Philips 221P3LPY PHL08A3 1920x1080 477x268mm 21.5-inch                   | 3         | 0.2%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 3         | 0.2%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.2%    |
| LG Display LCD Monitor LGD027A 1600x900 382x215mm 17.3-inch              | 3         | 0.2%    |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 3         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 611       | 42.34%  |
| 1366x768 (WXGA)    | 290       | 20.1%   |
| 3840x2160 (4K)     | 91        | 6.31%   |
| 2560x1440 (QHD)    | 63        | 4.37%   |
| 1280x800 (WXGA)    | 59        | 4.09%   |
| 1600x900 (HD+)     | 56        | 3.88%   |
| 1280x1024 (SXGA)   | 41        | 2.84%   |
| 1920x1200 (WUXGA)  | 40        | 2.77%   |
| 1680x1050 (WSXGA+) | 40        | 2.77%   |
| 1440x900 (WXGA+)   | 36        | 2.49%   |
| 1024x600           | 14        | 0.97%   |
| 2560x1600          | 12        | 0.83%   |
| 1600x1200          | 12        | 0.83%   |
| 1360x768           | 10        | 0.69%   |
| 2880x1800          | 9         | 0.62%   |
| 2560x1080          | 8         | 0.55%   |
| 3440x1440          | 7         | 0.49%   |
| 1024x768 (XGA)     | 7         | 0.49%   |
| 2160x1440          | 6         | 0.42%   |
| 3840x1080          | 4         | 0.28%   |
| Unknown            | 4         | 0.28%   |
| 3840x2400          | 3         | 0.21%   |
| 2880x1920          | 3         | 0.21%   |
| 2256x1504          | 3         | 0.21%   |
| 3200x1800 (QHD+)   | 2         | 0.14%   |
| 1400x1050          | 2         | 0.14%   |
| 1280x720 (HD)      | 2         | 0.14%   |
| 3840x2560          | 1         | 0.07%   |
| 3200x2000          | 1         | 0.07%   |
| 3072x1920          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2048x1536          | 1         | 0.07%   |
| 1920x1440          | 1         | 0.07%   |
| 1920x1280          | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 379       | 25.52%  |
| 13      | 138       | 9.29%   |
| 24      | 109       | 7.34%   |
| 14      | 107       | 7.21%   |
| 27      | 94        | 6.33%   |
| 23      | 90        | 6.06%   |
| 17      | 84        | 5.66%   |
| 21      | 79        | 5.32%   |
| 11      | 44        | 2.96%   |
| 31      | 41        | 2.76%   |
| 18      | 38        | 2.56%   |
| 19      | 36        | 2.42%   |
| 16      | 32        | 2.15%   |
| 10      | 24        | 1.62%   |
| 22      | 23        | 1.55%   |
| 20      | 23        | 1.55%   |
| 12      | 22        | 1.48%   |
| Unknown | 18        | 1.21%   |
| 84      | 16        | 1.08%   |
| 34      | 13        | 0.88%   |
| 54      | 12        | 0.81%   |
| 32      | 7         | 0.47%   |
| 72      | 6         | 0.4%    |
| 65      | 5         | 0.34%   |
| 26      | 5         | 0.34%   |
| 25      | 5         | 0.34%   |
| 63      | 4         | 0.27%   |
| 40      | 4         | 0.27%   |
| 57      | 3         | 0.2%    |
| 39      | 3         | 0.2%    |
| 36      | 3         | 0.2%    |
| 49      | 2         | 0.13%   |
| 46      | 2         | 0.13%   |
| 43      | 2         | 0.13%   |
| 42      | 2         | 0.13%   |
| 28      | 2         | 0.13%   |
| 85      | 1         | 0.07%   |
| 75      | 1         | 0.07%   |
| 74      | 1         | 0.07%   |
| 64      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 574       | 39.13%  |
| 501-600     | 281       | 19.15%  |
| 401-500     | 173       | 11.79%  |
| 201-300     | 167       | 11.38%  |
| 351-400     | 112       | 7.63%   |
| 601-700     | 50        | 3.41%   |
| 1001-1500   | 30        | 2.04%   |
| 701-800     | 25        | 1.7%    |
| 1501-2000   | 25        | 1.7%    |
| Unknown     | 18        | 1.23%   |
| 801-900     | 8         | 0.55%   |
| 901-1000    | 4         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1050      | 76.7%   |
| 16/10   | 209       | 15.27%  |
| 5/4     | 39        | 2.85%   |
| 4/3     | 24        | 1.75%   |
| 3/2     | 19        | 1.39%   |
| 21/9    | 13        | 0.95%   |
| Unknown | 10        | 0.73%   |
| 32/9    | 2         | 0.15%   |
| 0.56    | 2         | 0.15%   |
| 6/5     | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 377       | 25.56%  |
| 201-250        | 236       | 16%     |
| 81-90          | 193       | 13.08%  |
| 301-350        | 97        | 6.58%   |
| 151-200        | 88        | 5.97%   |
| 121-130        | 66        | 4.47%   |
| 351-500        | 63        | 4.27%   |
| More than 1000 | 52        | 3.53%   |
| 71-80          | 50        | 3.39%   |
| 141-150        | 48        | 3.25%   |
| 51-60          | 44        | 2.98%   |
| 251-300        | 42        | 2.85%   |
| 111-120        | 25        | 1.69%   |
| 41-50          | 24        | 1.63%   |
| 61-70          | 21        | 1.42%   |
| 501-1000       | 19        | 1.29%   |
| Unknown        | 18        | 1.22%   |
| 91-100         | 7         | 0.47%   |
| 131-140        | 5         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 496       | 34.54%  |
| 121-160       | 402       | 27.99%  |
| 101-120       | 379       | 26.39%  |
| 161-240       | 82        | 5.71%   |
| 1-50          | 34        | 2.37%   |
| More than 240 | 25        | 1.74%   |
| Unknown       | 18        | 1.25%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1191      | 84.05%  |
| 2     | 180       | 12.7%   |
| 0     | 35        | 2.47%   |
| 3     | 11        | 0.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 753       | 34.43%  |
| Intel                                  | 618       | 28.26%  |
| Qualcomm Atheros                       | 207       | 9.47%   |
| Broadcom                               | 157       | 7.18%   |
| MediaTek                               | 64        | 2.93%   |
| TP-Link                                | 46        | 2.1%    |
| Broadcom Limited                       | 45        | 2.06%   |
| Marvell Technology Group               | 27        | 1.23%   |
| Ralink                                 | 26        | 1.19%   |
| Nvidia                                 | 23        | 1.05%   |
| Ralink Technology                      | 22        | 1.01%   |
| Samsung Electronics                    | 16        | 0.73%   |
| ASIX Electronics                       | 16        | 0.73%   |
| OPPO Electronics                       | 12        | 0.55%   |
| Xiaomi                                 | 9         | 0.41%   |
| Sierra Wireless                        | 9         | 0.41%   |
| Qualcomm Atheros Communications        | 9         | 0.41%   |
| Motorola PCS                           | 9         | 0.41%   |
| Microsoft                              | 7         | 0.32%   |
| Huawei Technologies                    | 6         | 0.27%   |
| Google                                 | 6         | 0.27%   |
| Edimax Technology                      | 6         | 0.27%   |
| ASUSTek Computer                       | 6         | 0.27%   |
| NetGear                                | 5         | 0.23%   |
| Dell                                   | 5         | 0.23%   |
| D-Link                                 | 5         | 0.23%   |
| VIA Technologies                       | 4         | 0.18%   |
| Linksys                                | 4         | 0.18%   |
| Belkin Components                      | 4         | 0.18%   |
| Qualcomm                               | 3         | 0.14%   |
| Lenovo                                 | 3         | 0.14%   |
| JMicron Technology                     | 3         | 0.14%   |
| IMC Networks                           | 3         | 0.14%   |
| Fibocom                                | 3         | 0.14%   |
| Ericsson Business Mobile Networks      | 3         | 0.14%   |
| D-Link System                          | 3         | 0.14%   |
| AVM                                    | 3         | 0.14%   |
| Attansic Technology                    | 3         | 0.14%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.09%   |
| Shenzhen Goodix Technology             | 2         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 466       | 17.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 91        | 3.51%   |
| Intel Wi-Fi 6 AX200                                                    | 40        | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 39        | 1.5%    |
| Intel Wireless 8265 / 8275                                             | 39        | 1.5%    |
| Intel Wi-Fi 6 AX201                                                    | 36        | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                      | 35        | 1.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 33        | 1.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 33        | 1.27%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 32        | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 32        | 1.23%   |
| Intel Wireless 8260                                                    | 31        | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 26        | 1%      |
| Intel Wireless 7260                                                    | 26        | 1%      |
| Intel Ethernet Connection I217-LM                                      | 26        | 1%      |
| Intel Wireless 7265                                                    | 25        | 0.96%   |
| Intel Wireless 3165                                                    | 25        | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 23        | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 23        | 0.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 22        | 0.85%   |
| Intel Ethernet Controller I225-V                                       | 22        | 0.85%   |
| Realtek 802.11ac NIC                                                   | 21        | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 20        | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 20        | 0.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 20        | 0.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 19        | 0.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 17        | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                          | 17        | 0.66%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 16        | 0.62%   |
| Intel 82577LM Gigabit Network Connection                               | 16        | 0.62%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]   | 15        | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 14        | 0.54%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 14        | 0.54%   |
| Intel Ethernet Connection (2) I219-V                                   | 14        | 0.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 14        | 0.54%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 14        | 0.54%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 14        | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 13        | 0.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 13        | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 13        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 470       | 38.06%  |
| Realtek Semiconductor             | 248       | 20.08%  |
| Qualcomm Atheros                  | 158       | 12.79%  |
| Broadcom                          | 109       | 8.83%   |
| MediaTek                          | 55        | 4.45%   |
| TP-Link                           | 43        | 3.48%   |
| Broadcom Limited                  | 29        | 2.35%   |
| Ralink                            | 26        | 2.11%   |
| Ralink Technology                 | 22        | 1.78%   |
| Sierra Wireless                   | 9         | 0.73%   |
| Qualcomm Atheros Communications   | 9         | 0.73%   |
| Edimax Technology                 | 6         | 0.49%   |
| ASUSTek Computer                  | 6         | 0.49%   |
| NetGear                           | 5         | 0.4%    |
| D-Link                            | 5         | 0.4%    |
| Linksys                           | 4         | 0.32%   |
| Belkin Components                 | 4         | 0.32%   |
| Microsoft                         | 3         | 0.24%   |
| IMC Networks                      | 3         | 0.24%   |
| Fibocom                           | 3         | 0.24%   |
| AVM                               | 3         | 0.24%   |
| Marvell Technology Group          | 2         | 0.16%   |
| Dell                              | 2         | 0.16%   |
| ZyDAS                             | 1         | 0.08%   |
| Tenda                             | 1         | 0.08%   |
| Sweex                             | 1         | 0.08%   |
| Realtek                           | 1         | 0.08%   |
| Qualcomm Technologies             | 1         | 0.08%   |
| Qualcomm                          | 1         | 0.08%   |
| Mercucys                          | 1         | 0.08%   |
| Hewlett-Packard                   | 1         | 0.08%   |
| Fujitsu Siemens Computers         | 1         | 0.08%   |
| Ericsson Business Mobile Networks | 1         | 0.08%   |
| D-Link System                     | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 40        | 3.21%   |
| Intel Wireless 8265 / 8275                                              | 39        | 3.13%   |
| Intel Wi-Fi 6 AX201                                                     | 36        | 2.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 33        | 2.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 33        | 2.65%   |
| Intel Wireless 8260                                                     | 31        | 2.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 26        | 2.09%   |
| Intel Wireless 7260                                                     | 26        | 2.09%   |
| Intel Wireless 7265                                                     | 25        | 2.01%   |
| Intel Wireless 3165                                                     | 25        | 2.01%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 23        | 1.85%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 23        | 1.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 23        | 1.85%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 22        | 1.77%   |
| Realtek 802.11ac NIC                                                    | 21        | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 20        | 1.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 20        | 1.61%   |
| Broadcom BCM43142 802.11b/g/n                                           | 17        | 1.36%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 16        | 1.28%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 15        | 1.2%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 1.12%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 14        | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 14        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.12%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 14        | 1.12%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 13        | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 13        | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 13        | 1.04%   |
| Ralink MT7601U Wireless Adapter                                         | 12        | 0.96%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 12        | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 12        | 0.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 12        | 0.96%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 11        | 0.88%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 11        | 0.88%   |
| Intel Centrino Advanced-N 6200                                          | 11        | 0.88%   |
| Realtek 802.11n WLAN Adapter                                            | 10        | 0.8%    |
| Intel Raptor Lake PCH CNVi WiFi                                         | 10        | 0.8%    |
| Intel Centrino Advanced-N 6235                                          | 10        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 646       | 50.04%  |
| Intel                                  | 316       | 24.48%  |
| Broadcom                               | 73        | 5.65%   |
| Qualcomm Atheros                       | 71        | 5.5%    |
| Marvell Technology Group               | 25        | 1.94%   |
| Nvidia                                 | 23        | 1.78%   |
| Broadcom Limited                       | 17        | 1.32%   |
| Samsung Electronics                    | 16        | 1.24%   |
| ASIX Electronics                       | 16        | 1.24%   |
| OPPO Electronics                       | 12        | 0.93%   |
| Xiaomi                                 | 9         | 0.7%    |
| Motorola PCS                           | 9         | 0.7%    |
| MediaTek                               | 9         | 0.7%    |
| Google                                 | 5         | 0.39%   |
| VIA Technologies                       | 4         | 0.31%   |
| TP-Link                                | 4         | 0.31%   |
| Microsoft                              | 4         | 0.31%   |
| Huawei Technologies                    | 4         | 0.31%   |
| Lenovo                                 | 3         | 0.23%   |
| JMicron Technology                     | 3         | 0.23%   |
| Attansic Technology                    | 3         | 0.23%   |
| Suzhou Motorcomm Electronic Technology | 2         | 0.15%   |
| Raspberry Pi                           | 2         | 0.15%   |
| Qualcomm                               | 2         | 0.15%   |
| D-Link System                          | 2         | 0.15%   |
| T & A Mobile Phones                    | 1         | 0.08%   |
| Spreadtrum Communications              | 1         | 0.08%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.08%   |
| QinHeng Electronics                    | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.08%   |
| ICS Advent                             | 1         | 0.08%   |
| Hewlett-Packard                        | 1         | 0.08%   |
| Foxconn / Hon Hai                      | 1         | 0.08%   |
| DisplayLink                            | 1         | 0.08%   |
| Aquantia                               | 1         | 0.08%   |
| Apple                                  | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 466       | 35.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 91        | 6.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 39        | 2.94%   |
| Realtek RTL8125 2.5GbE Controller                                      | 35        | 2.64%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 32        | 2.42%   |
| Intel Ethernet Connection I217-LM                                      | 26        | 1.96%   |
| Intel Ethernet Controller I225-V                                       | 22        | 1.66%   |
| Intel 82577LM Gigabit Network Connection                               | 16        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                                   | 14        | 1.06%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 14        | 1.06%   |
| Intel Ethernet Connection (7) I219-V                                   | 12        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 0.91%   |
| ASIX AX88179 Gigabit Ethernet                                          | 12        | 0.91%   |
| OPPO Ace 3V                                                            | 11        | 0.83%   |
| Intel I211 Gigabit Network Connection                                  | 11        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                  | 11        | 0.83%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 10        | 0.75%   |
| Nvidia MCP79 Ethernet                                                  | 10        | 0.75%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 0.75%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 0.75%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 9         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 9         | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 9         | 0.68%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 9         | 0.68%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 9         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 8         | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 8         | 0.6%    |
| Intel Ethernet Connection I218-LM                                      | 8         | 0.6%    |
| Motorola PCS motorola one 5G ace                                       | 7         | 0.53%   |
| Intel Ethernet Connection I219-V                                       | 7         | 0.53%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 7         | 0.53%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 7         | 0.53%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 6         | 0.45%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 6         | 0.45%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 6         | 0.45%   |
| Intel Ethernet Connection I217-V                                       | 6         | 0.45%   |
| Intel Ethernet Connection (6) I219-LM                                  | 6         | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1197      | 50.89%  |
| WiFi     | 1134      | 48.21%  |
| Modem    | 17        | 0.72%   |
| Unknown  | 4         | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 825       | 57.73%  |
| Ethernet | 603       | 42.2%   |
| Unknown  | 1         | 0.07%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 788       | 56.09%  |
| 1     | 535       | 38.08%  |
| 0     | 52        | 3.7%    |
| 3     | 26        | 1.85%   |
| 4     | 2         | 0.14%   |
| 12    | 1         | 0.07%   |
| 8     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1023      | 72.35%  |
| Yes  | 391       | 27.65%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 375       | 40.94%  |
| Realtek Semiconductor           | 113       | 12.34%  |
| Qualcomm Atheros Communications | 58        | 6.33%   |
| Apple                           | 57        | 6.22%   |
| Broadcom                        | 51        | 5.57%   |
| Cambridge Silicon Radio         | 47        | 5.13%   |
| IMC Networks                    | 45        | 4.91%   |
| Foxconn / Hon Hai               | 34        | 3.71%   |
| Lite-On Technology              | 28        | 3.06%   |
| Dell                            | 17        | 1.86%   |
| MediaTek                        | 16        | 1.75%   |
| Hewlett-Packard                 | 14        | 1.53%   |
| Ralink                          | 13        | 1.42%   |
| ASUSTek Computer                | 11        | 1.2%    |
| Toshiba                         | 10        | 1.09%   |
| TP-Link                         | 8         | 0.87%   |
| Alps Electric                   | 4         | 0.44%   |
| Realtek                         | 3         | 0.33%   |
| Foxconn International           | 3         | 0.33%   |
| Marvell Semiconductor           | 2         | 0.22%   |
| Ralink Technology               | 1         | 0.11%   |
| Plugable                        | 1         | 0.11%   |
| Micro Star International        | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| Creative Technology             | 1         | 0.11%   |
| Actions                         | 1         | 0.11%   |
| Unknown                         | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 144       | 15.7%   |
| Realtek Bluetooth Radio                                                             | 91        | 9.92%   |
| Intel AX201 Bluetooth                                                               | 70        | 7.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 47        | 5.13%   |
| Intel AX200 Bluetooth                                                               | 40        | 4.36%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 38        | 4.14%   |
| Intel Bluetooth Device                                                              | 32        | 3.49%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 26        | 2.84%   |
| IMC Networks Wireless_Device                                                        | 25        | 2.73%   |
| Apple Bluetooth Host Controller                                                     | 24        | 2.62%   |
| Apple Bluetooth USB Host Controller                                                 | 18        | 1.96%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 15        | 1.64%   |
| MediaTek Wireless_Device                                                            | 15        | 1.64%   |
| Ralink RT3290 Bluetooth                                                             | 13        | 1.42%   |
| IMC Networks Bluetooth Radio                                                        | 13        | 1.42%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 12        | 1.31%   |
| Intel AX210 Bluetooth                                                               | 12        | 1.31%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 10        | 1.09%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 10        | 1.09%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 10        | 1.09%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 9         | 0.98%   |
| TP-Link TP-T@- UB500 Adapter                                                        | 8         | 0.87%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 8         | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 8         | 0.87%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 8         | 0.87%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 8         | 0.87%   |
| Apple Bluetooth HCI                                                                 | 8         | 0.87%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 7         | 0.76%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 0.76%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 7         | 0.76%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 6         | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 0.65%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 5         | 0.55%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 5         | 0.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 5         | 0.55%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 5         | 0.55%   |
| Toshiba BCM43142A0                                                                  | 4         | 0.44%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 983       | 53.77%  |
| AMD                                          | 380       | 20.79%  |
| Nvidia                                       | 293       | 16.03%  |
| C-Media Electronics                          | 27        | 1.48%   |
| Creative Labs                                | 15        | 0.82%   |
| Logitech                                     | 10        | 0.55%   |
| Texas Instruments                            | 8         | 0.44%   |
| JMTek                                        | 8         | 0.44%   |
| Realtek Semiconductor                        | 7         | 0.38%   |
| VIA Technologies                             | 5         | 0.27%   |
| GN Netcom                                    | 5         | 0.27%   |
| Focusrite-Novation                           | 5         | 0.27%   |
| Nordic Semiconductor ASA                     | 3         | 0.16%   |
| Microsoft                                    | 3         | 0.16%   |
| Lenovo                                       | 3         | 0.16%   |
| Jieli Technology                             | 3         | 0.16%   |
| Generalplus Technology                       | 3         | 0.16%   |
| BEHRINGER International                      | 3         | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.11%   |
| Tenx Technology                              | 2         | 0.11%   |
| SteelSeries ApS                              | 2         | 0.11%   |
| Sony                                         | 2         | 0.11%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.11%   |
| ROCCAT                                       | 2         | 0.11%   |
| Philips (or NXP)                             | 2         | 0.11%   |
| Linux Foundation                             | 2         | 0.11%   |
| Kingston Technology                          | 2         | 0.11%   |
| Hewlett-Packard                              | 2         | 0.11%   |
| GYROCOM C&C                                  | 2         | 0.11%   |
| Giga-Byte Technology                         | 2         | 0.11%   |
| Fortemedia                                   | 2         | 0.11%   |
| Dell                                         | 2         | 0.11%   |
| Apple                                        | 2         | 0.11%   |
| Walmart                                      | 1         | 0.05%   |
| ULi Electronics                              | 1         | 0.05%   |
| TerraTec Electronic                          | 1         | 0.05%   |
| Shenzhen Riitek Technology                   | 1         | 0.05%   |
| Setek Elektronik                             | 1         | 0.05%   |
| Schiit Audio                                 | 1         | 0.05%   |
| RODE Microphones                             | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 159       | 7.29%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 98        | 4.49%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 90        | 4.12%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 84        | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 80        | 3.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 58        | 2.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 50        | 2.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 49        | 2.25%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 48        | 2.2%    |
| AMD FCH Azalia Controller                                                                         | 46        | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 41        | 1.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 41        | 1.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 41        | 1.88%   |
| AMD Radeon High Definition Audio Controller                                                       | 39        | 1.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 36        | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 36        | 1.65%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 32        | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 31        | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 31        | 1.42%   |
| Intel 8 Series HD Audio Controller                                                                | 31        | 1.42%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 29        | 1.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 29        | 1.33%   |
| AMD Kabini HDMI/DP Audio                                                                          | 26        | 1.19%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 24        | 1.1%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 21        | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 0.96%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 0.96%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 20        | 0.92%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 20        | 0.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 0.82%   |
| Intel 200 Series PCH HD Audio                                                                     | 18        | 0.82%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 18        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 0.78%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 17        | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 0.73%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 16        | 0.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 15        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 15        | 0.69%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 14        | 0.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 320       | 19.7%   |
| SK hynix                                | 295       | 18.17%  |
| Unknown                                 | 192       | 11.82%  |
| Micron Technology                       | 147       | 9.05%   |
| Kingston                                | 146       | 8.99%   |
| Crucial                                 | 109       | 6.71%   |
| Corsair                                 | 72        | 4.43%   |
| G.Skill                                 | 46        | 2.83%   |
| A-DATA Technology                       | 42        | 2.59%   |
| Unknown                                 | 34        | 2.09%   |
| Ramaxel Technology                      | 31        | 1.91%   |
| Elpida                                  | 29        | 1.79%   |
| Unknown (ABCD)                          | 25        | 1.54%   |
| Nanya Technology                        | 23        | 1.42%   |
| Team                                    | 16        | 0.99%   |
| Smart                                   | 9         | 0.55%   |
| Patriot                                 | 9         | 0.55%   |
| Transcend                               | 8         | 0.49%   |
| Apacer                                  | 7         | 0.43%   |
| CSX                                     | 4         | 0.25%   |
| Unifosa                                 | 3         | 0.18%   |
| Timetec                                 | 3         | 0.18%   |
| Lexar Co Limited                        | 3         | 0.18%   |
| Lexar                                   | 3         | 0.18%   |
| 48spaces                                | 3         | 0.18%   |
| Unknown (0x0B45)                        | 2         | 0.12%   |
| Teikon                                  | 2         | 0.12%   |
| Silicon Power Computer & Communications | 2         | 0.12%   |
| Qimonda                                 | 2         | 0.12%   |
| PNY                                     | 2         | 0.12%   |
| Avant                                   | 2         | 0.12%   |
| ASint Technology                        | 2         | 0.12%   |
| 4ea5                                    | 2         | 0.12%   |
| Wilk                                    | 1         | 0.06%   |
| V-GeN                                   | 1         | 0.06%   |
| Unknown (F301)                          | 1         | 0.06%   |
| Unknown (AB)                            | 1         | 0.06%   |
| Unknown (8A02)                          | 1         | 0.06%   |
| Unknown (0x0E9D)                        | 1         | 0.06%   |
| Unknown (0x0CAB)                        | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 34        | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 18        | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 18        | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.86%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 13        | 0.75%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.69%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 11        | 0.63%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.63%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 11        | 0.63%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 10        | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 0.52%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 9         | 0.52%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 8         | 0.46%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.46%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 7         | 0.4%    |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 7         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 7         | 0.4%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 7         | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.4%    |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 7         | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.4%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 7         | 0.4%    |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 6         | 0.35%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.35%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.35%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 6         | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.35%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 6         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 5         | 0.29%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 5         | 0.29%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.29%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.29%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.29%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.29%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 5         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 530       | 37.35%  |
| DDR3    | 524       | 36.93%  |
| DDR2    | 97        | 6.84%   |
| SDRAM   | 59        | 4.16%   |
| LPDDR4  | 54        | 3.81%   |
| DDR5    | 51        | 3.59%   |
| Unknown | 32        | 2.26%   |
| LPDDR5  | 26        | 1.83%   |
| LPDDR3  | 22        | 1.55%   |
| DDR     | 20        | 1.41%   |
| DRAM    | 4         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 912       | 64.96%  |
| DIMM         | 394       | 28.06%  |
| Row Of Chips | 75        | 5.34%   |
| Unknown      | 11        | 0.78%   |
| Chip         | 9         | 0.64%   |
| FB-DIMM      | 3         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 497       | 32.74%  |
| 4096  | 432       | 28.46%  |
| 2048  | 247       | 16.27%  |
| 16384 | 201       | 13.24%  |
| 1024  | 79        | 5.2%    |
| 32768 | 51        | 3.36%   |
| 512   | 8         | 0.53%   |
| 65536 | 1         | 0.07%   |
| 49152 | 1         | 0.07%   |
| 256   | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 318       | 20.66%  |
| 3200    | 239       | 15.53%  |
| 2667    | 148       | 9.62%   |
| 1333    | 122       | 7.93%   |
| 2400    | 100       | 6.5%    |
| 667     | 56        | 3.64%   |
| Unknown | 50        | 3.25%   |
| 2133    | 45        | 2.92%   |
| 1334    | 44        | 2.86%   |
| 1067    | 43        | 2.79%   |
| 800     | 43        | 2.79%   |
| 3600    | 33        | 2.14%   |
| 5600    | 21        | 1.36%   |
| 1867    | 18        | 1.17%   |
| 6400    | 16        | 1.04%   |
| 4800    | 14        | 0.91%   |
| 4267    | 14        | 0.91%   |
| 2048    | 14        | 0.91%   |
| 8400    | 12        | 0.78%   |
| 533     | 12        | 0.78%   |
| 6000    | 11        | 0.71%   |
| 4199    | 11        | 0.71%   |
| 3266    | 11        | 0.71%   |
| 1800    | 11        | 0.71%   |
| 3733    | 10        | 0.65%   |
| 3000    | 9         | 0.58%   |
| 2933    | 8         | 0.52%   |
| 1866    | 8         | 0.52%   |
| 1066    | 8         | 0.52%   |
| 975     | 8         | 0.52%   |
| 2666    | 6         | 0.39%   |
| 1639    | 6         | 0.39%   |
| 400     | 6         | 0.39%   |
| 4000    | 4         | 0.26%   |
| 3800    | 4         | 0.26%   |
| 3466    | 4         | 0.26%   |
| 333     | 4         | 0.26%   |
| 7500    | 3         | 0.19%   |
| 7467    | 3         | 0.19%   |
| 5500    | 3         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Brother Industries    | 11        | 29.73%  |
| Hewlett-Packard       | 9         | 24.32%  |
| Canon                 | 8         | 21.62%  |
| Seiko Epson           | 4         | 10.81%  |
| Dymo-CoStar           | 2         | 5.41%   |
| Samsung Electronics   | 1         | 2.7%    |
| Lexmark International | 1         | 2.7%    |
| Konica Minolta        | 1         | 2.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450        | 2         | 5.26%   |
| Canon MF641C                       | 2         | 5.26%   |
| Brother MFC-7340                   | 2         | 5.26%   |
| Brother DCP-L2540DW                | 2         | 5.26%   |
| Seiko Epson L380 Series            | 1         | 2.63%   |
| Seiko Epson ET-4850 Series         | 1         | 2.63%   |
| Seiko Epson ET-2720 Series         | 1         | 2.63%   |
| Seiko Epson EPSON L220 Series      | 1         | 2.63%   |
| Samsung ML-1610 Mono Laser Printer | 1         | 2.63%   |
| Lexmark International CS417dn      | 1         | 2.63%   |
| Konica Minolta KONICA MINOLTA 206  | 1         | 2.63%   |
| HP Smart Tank 710-720 series       | 1         | 2.63%   |
| HP LaserJet Pro M148-M149          | 1         | 2.63%   |
| HP LaserJet P2055 series           | 1         | 2.63%   |
| HP LaserJet P1006                  | 1         | 2.63%   |
| HP LaserJet 1022                   | 1         | 2.63%   |
| HP HP LaserJet M101-M106           | 1         | 2.63%   |
| HP ENVY 4500 series                | 1         | 2.63%   |
| HP Deskjet 3510 series             | 1         | 2.63%   |
| HP Deskjet 1510                    | 1         | 2.63%   |
| Canon PIXMA MG5600 Series          | 1         | 2.63%   |
| Canon PIXMA MG3600 Series          | 1         | 2.63%   |
| Canon PIXMA MG2500 Series          | 1         | 2.63%   |
| Canon PIXMA iP4000                 | 1         | 2.63%   |
| Canon MG5700 series                | 1         | 2.63%   |
| Canon LiDE 400                     | 1         | 2.63%   |
| Brother Printer                    | 1         | 2.63%   |
| Brother MFC-7360N                  | 1         | 2.63%   |
| Brother HL-L2400DWE                | 1         | 2.63%   |
| Brother HL-L2380DW                 | 1         | 2.63%   |
| Brother HL-L2350DW series          | 1         | 2.63%   |
| Brother HL-52x0 series             | 1         | 2.63%   |
| Brother HL-2150N series            | 1         | 2.63%   |
| Brother DCP-L2500D                 | 1         | 2.63%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 9         | 81.82%  |
| Seiko Epson    | 1         | 9.09%   |
| Mustek Systems | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20    | 2         | 18.18%  |
| Canon CanoScan LiDE 700F              | 2         | 18.18%  |
| Canon CanoScan LiDE 210               | 2         | 18.18%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 9.09%   |
| Mustek Systems BearPaw 1200 CU Plus   | 1         | 9.09%   |
| Canon CanoScan N1240U/LiDE 30         | 1         | 9.09%   |
| Canon CanoScan LIDE 25                | 1         | 9.09%   |
| Canon CanoScan 8800F                  | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 173       | 19.93%  |
| Microdia                               | 71        | 8.18%   |
| Bison Electronics                      | 69        | 7.95%   |
| Realtek Semiconductor                  | 63        | 7.26%   |
| IMC Networks                           | 61        | 7.03%   |
| Quanta                                 | 47        | 5.41%   |
| Sunplus Innovation Technology          | 43        | 4.95%   |
| Apple                                  | 42        | 4.84%   |
| Cheng Uei Precision Industry (Foxlink) | 38        | 4.38%   |
| Logitech                               | 37        | 4.26%   |
| Suyin                                  | 26        | 3%      |
| Luxvisions Innotech Limited            | 23        | 2.65%   |
| Lite-On Technology                     | 23        | 2.65%   |
| Alcor Micro                            | 15        | 1.73%   |
| Microsoft                              | 14        | 1.61%   |
| Lenovo                                 | 14        | 1.61%   |
| Syntek                                 | 12        | 1.38%   |
| Sonix Technology                       | 10        | 1.15%   |
| Silicon Motion                         | 9         | 1.04%   |
| Ricoh                                  | 9         | 1.04%   |
| Z-Star Microelectronics                | 6         | 0.69%   |
| Importek                               | 6         | 0.69%   |
| icSpring                               | 4         | 0.46%   |
| Generalplus Technology                 | 4         | 0.46%   |
| Samsung Electronics                    | 3         | 0.35%   |
| GEMBIRD                                | 3         | 0.35%   |
| Cubeternet                             | 3         | 0.35%   |
| ShineTech                              | 2         | 0.23%   |
| MacroSilicon                           | 2         | 0.23%   |
| kingcome                               | 2         | 0.23%   |
| Intel                                  | 2         | 0.23%   |
| Hewlett-Packard                        | 2         | 0.23%   |
| ARC International                      | 2         | 0.23%   |
| ALi                                    | 2         | 0.23%   |
| Acer                                   | 2         | 0.23%   |
| YGTek                                  | 1         | 0.12%   |
| Y Media                                | 1         | 0.12%   |
| Xiongmai                               | 1         | 0.12%   |
| WaveRider Communications               | 1         | 0.12%   |
| USB Cam Manufacturer                   | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 36        | 4.13%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 27        | 3.1%    |
| Apple Built-in iSight                               | 24        | 2.75%   |
| Realtek Integrated_Webcam_HD                        | 23        | 2.64%   |
| Microdia Integrated_Webcam_HD                       | 22        | 2.52%   |
| Sunplus Integrated_Webcam_HD                        | 12        | 1.38%   |
| Chicony HD WebCam                                   | 12        | 1.38%   |
| IMC Networks Integrated Camera                      | 11        | 1.26%   |
| Bison Integrated Camera                             | 11        | 1.26%   |
| Lite-On Integrated Camera                           | 10        | 1.15%   |
| Logitech Webcam C270                                | 9         | 1.03%   |
| Chicony TOSHIBA Web Camera - HD                     | 9         | 1.03%   |
| Apple FaceTime HD Camera (Built-in)                 | 9         | 1.03%   |
| Quanta HD User Facing                               | 8         | 0.92%   |
| Chicony HP Truevision HD camera                     | 8         | 0.92%   |
| Bison USB HD Webcam                                 | 8         | 0.92%   |
| Lenovo Integrated Webcam [R5U877]                   | 7         | 0.8%    |
| Bison Lenovo EasyCamera                             | 7         | 0.8%    |
| Realtek USB2.0 HD UVC WebCam                        | 6         | 0.69%   |
| Quanta HP TrueVision HD Camera                      | 6         | 0.69%   |
| Microsoft LifeCam HD-3000                           | 6         | 0.69%   |
| Microdia Integrated Webcam                          | 6         | 0.69%   |
| Luxvisions Innotech Limited Integrated Camera       | 6         | 0.69%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 6         | 0.69%   |
| Importek TOSHIBA Web Camera - HD                    | 6         | 0.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 6         | 0.69%   |
| Chicony USB 2.0 Camera                              | 6         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 6         | 0.69%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 6         | 0.69%   |
| Bison HD Webcam                                     | 6         | 0.69%   |
| Syntek Integrated Camera                            | 5         | 0.57%   |
| Suyin HP TrueVision HD Integrated Webcam            | 5         | 0.57%   |
| Sunplus HD WebCam                                   | 5         | 0.57%   |
| Realtek USB Camera                                  | 5         | 0.57%   |
| Quanta HP HD Camera                                 | 5         | 0.57%   |
| Microdia USB 2.0 Camera                             | 5         | 0.57%   |
| Microdia Laptop_Integrated_Webcam_2M                | 5         | 0.57%   |
| Logitech Webcam C930e                               | 5         | 0.57%   |
| Lite-On HP HD Camera                                | 5         | 0.57%   |
| Lenovo Integrated Webcam                            | 5         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 50        | 34.25%  |
| Synaptics                          | 29        | 19.86%  |
| Shenzhen Goodix Technology         | 16        | 10.96%  |
| Elan Microelectronics              | 14        | 9.59%   |
| AuthenTec                          | 14        | 9.59%   |
| Upek                               | 13        | 8.9%    |
| LighTuning Technology              | 4         | 2.74%   |
| STMicroelectronics                 | 3         | 2.05%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.68%   |
| Microsoft                          | 1         | 0.68%   |
| Focal-systems.Corp                 | 1         | 0.68%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 12        | 8.22%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 10        | 6.85%   |
| Shenzhen Goodix  Fingerprint Device                             | 10        | 6.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 8         | 5.48%   |
| Elan ELAN:Fingerprint                                           | 8         | 5.48%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 6         | 4.11%   |
| Validity Sensors Synaptics WBDI                                 | 6         | 4.11%   |
| Elan ELAN:ARM-M4                                                | 6         | 4.11%   |
| AuthenTec AES2810                                               | 6         | 4.11%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 6         | 4.11%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 5         | 3.42%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 5         | 3.42%   |
| Shenzhen Goodix Fingerprint Reader                              | 5         | 3.42%   |
| Validity Sensors VFS Fingerprint sensor                         | 4         | 2.74%   |
| Validity Sensors Fingerprint scanner                            | 4         | 2.74%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 2.05%   |
| Upek TCS5B Fingerprint sensor                                   | 3         | 2.05%   |
| Synaptics UWP WBDI Device                                       | 3         | 2.05%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 3         | 2.05%   |
| STMicroelectronics Fingerprint Reader                           | 3         | 2.05%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 1.37%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 1.37%   |
| Validity Sensors VFS300 Fingerprint Reader                      | 2         | 1.37%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 2         | 1.37%   |
| Synaptics WBDI Fingerprint Reader USB 102                       | 2         | 1.37%   |
| Synaptics  WBDI                                                 | 2         | 1.37%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 2         | 1.37%   |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 1.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 1.37%   |
| Validity Sensors VFS491                                         | 1         | 0.68%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 0.68%   |
| Synaptics UWP WBDI                                              | 1         | 0.68%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 0.68%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 0.68%   |
| Microsoft Fingerprint Reader                                    | 1         | 0.68%   |
| LighTuning Fingerprint Sensor                                   | 1         | 0.68%   |
| LighTuning Fingerprint Reader                                   | 1         | 0.68%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 0.68%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 0.68%   |
| AuthenTec AES1600                                               | 1         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 28        | 44.44%  |
| Alcor Micro           | 19        | 30.16%  |
| O2 Micro              | 8         | 12.7%   |
| Lenovo                | 4         | 6.35%   |
| Chicony Electronics   | 2         | 3.17%   |
| Advanced Card Systems | 2         | 3.17%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 30.16%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 7         | 11.11%  |
| Broadcom 5880                                                                | 7         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 9.52%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 7.94%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.35%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 6.35%   |
| Broadcom 58200                                                               | 4         | 6.35%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 4.76%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 3.17%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 1.59%   |
| Advanced Card Systems ACR122U                                                | 1         | 1.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 944       | 66.53%  |
| 1     | 374       | 26.36%  |
| 2     | 84        | 5.92%   |
| 3     | 16        | 1.13%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 197       | 34.81%  |
| Fingerprint reader       | 145       | 25.62%  |
| Net/wireless             | 70        | 12.37%  |
| Chipcard                 | 57        | 10.07%  |
| Multimedia controller    | 24        | 4.24%   |
| Camera                   | 15        | 2.65%   |
| Bluetooth                | 15        | 2.65%   |
| Communication controller | 12        | 2.12%   |
| Storage                  | 6         | 1.06%   |
| Unassigned class         | 5         | 0.88%   |
| Card reader              | 5         | 0.88%   |
| Network                  | 3         | 0.53%   |
| Net/ethernet             | 3         | 0.53%   |
| Flash memory             | 3         | 0.53%   |
| Sound                    | 2         | 0.35%   |
| Wireless                 | 1         | 0.18%   |
| Storage/raid             | 1         | 0.18%   |
| Storage/ata              | 1         | 0.18%   |
| Dvb card                 | 1         | 0.18%   |

