Linux - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

Distribution-specific reports: [AlmaLinux](/Dist/AlmaLinux), [Alpine](/Dist/Alpine), [ALT_Linux](/Dist/ALT_Linux), [antiX](/Dist/antiX), [Artix](/Dist/Artix), [Chrome_OS](/Dist/Chrome_OS), [Clear_Linux](/Dist/Clear_Linux), [Deepin](/Dist/Deepin), [Devuan](/Dist/Devuan), [EndeavourOS](/Dist/EndeavourOS), [Garuda_Linux](/Dist/Garuda_Linux), [GNOME_OS](/Dist/GNOME_OS), [Kaisen](/Dist/Kaisen), [Mageia](/Dist/Mageia), [Makulu](/Dist/Makulu), [NixOS](/Dist/NixOS), [Nobara](/Dist/Nobara), [Oracle_Linux](/Dist/Oracle_Linux), [Pardus](/Dist/Pardus), [PureOS](/Dist/PureOS), [Q4OS](/Dist/Q4OS), [Reborn_OS](/Dist/Reborn_OS), [Rocky_Linux](/Dist/Rocky_Linux), [Sparky](/Dist/Sparky), [Void_Linux](/Dist/Void_Linux), [Xero](/Dist/Xero).

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/linuxhw/TestDays_VE)

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

Total: 389345

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | X75VBP                      | Notebook    | [45dd9e0bea](https://linux-hardware.org/?probe=45dd9e0bea) | May 09, 2024 |
| ASRock        | H61M-DGS R2.0               | Desktop     | [47be7b76e5](https://linux-hardware.org/?probe=47be7b76e5) | May 09, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [be612ae4a6](https://linux-hardware.org/?probe=be612ae4a6) | May 09, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [f88f22a1b9](https://linux-hardware.org/?probe=f88f22a1b9) | May 09, 2024 |
| Acer          | One S1003                   | Tablet      | [4b36e20081](https://linux-hardware.org/?probe=4b36e20081) | May 09, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L2502CYA... | Notebook    | [03df260579](https://linux-hardware.org/?probe=03df260579) | May 09, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [afd5a26a47](https://linux-hardware.org/?probe=afd5a26a47) | May 09, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [c7b3c10131](https://linux-hardware.org/?probe=c7b3c10131) | May 09, 2024 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [f8574bdf3e](https://linux-hardware.org/?probe=f8574bdf3e) | May 09, 2024 |
| HP            | 805D                        | Desktop     | [208bd3b9dd](https://linux-hardware.org/?probe=208bd3b9dd) | May 09, 2024 |
| HP            | Pavilion dv6500             | Notebook    | [a9906a0a37](https://linux-hardware.org/?probe=a9906a0a37) | May 09, 2024 |
| ASUSTek       | PRIME B250M-C               | Desktop     | [0a6d61d9f6](https://linux-hardware.org/?probe=0a6d61d9f6) | May 09, 2024 |
| Lenovo        | ThinkPad L470 20J5S2RA00    | Notebook    | [9ce0d2cad0](https://linux-hardware.org/?probe=9ce0d2cad0) | May 09, 2024 |
| HP            | 1905                        | Desktop     | [8e94c4bb4e](https://linux-hardware.org/?probe=8e94c4bb4e) | May 09, 2024 |
| Dell          | Inspiron 3481               | Notebook    | [78cf24846f](https://linux-hardware.org/?probe=78cf24846f) | May 09, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c314d61f74](https://linux-hardware.org/?probe=c314d61f74) | May 09, 2024 |
| Unknown       | Unknown                     | Notebook    | [3c4e207a92](https://linux-hardware.org/?probe=3c4e207a92) | May 09, 2024 |
| SDZ           | X133                        | Notebook    | [442d4da2a4](https://linux-hardware.org/?probe=442d4da2a4) | May 09, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [369a002b88](https://linux-hardware.org/?probe=369a002b88) | May 09, 2024 |
| ASUSTek       | K52F                        | Notebook    | [f67d81858e](https://linux-hardware.org/?probe=f67d81858e) | May 09, 2024 |
| LG Electro... | A410-G.BC44P1               | Notebook    | [e687d57757](https://linux-hardware.org/?probe=e687d57757) | May 09, 2024 |
| HP            | 3396                        | Desktop     | [5e68a536f2](https://linux-hardware.org/?probe=5e68a536f2) | May 09, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [4720614db4](https://linux-hardware.org/?probe=4720614db4) | May 09, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [b81a572516](https://linux-hardware.org/?probe=b81a572516) | May 09, 2024 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [161509c62b](https://linux-hardware.org/?probe=161509c62b) | May 09, 2024 |
| HP            | ProBook 650 G3              | Notebook    | [9bfb6a8afd](https://linux-hardware.org/?probe=9bfb6a8afd) | May 09, 2024 |
| Supermicro    | H12SSL-i                    | Server      | [d5cf0eca85](https://linux-hardware.org/?probe=d5cf0eca85) | May 09, 2024 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [236ac0d0ed](https://linux-hardware.org/?probe=236ac0d0ed) | May 09, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [0a6d9b6f29](https://linux-hardware.org/?probe=0a6d9b6f29) | May 09, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [413b207df0](https://linux-hardware.org/?probe=413b207df0) | May 09, 2024 |
| Dell          | Inspiron 7706 2n1           | Convertible | [958dc9b878](https://linux-hardware.org/?probe=958dc9b878) | May 09, 2024 |
| GEEKOM        | MiniAir 11                  | Server      | [20e4a415d6](https://linux-hardware.org/?probe=20e4a415d6) | May 09, 2024 |
| Lenovo        | Bantry CRB NOK              | Desktop     | [c2a11bca8a](https://linux-hardware.org/?probe=c2a11bca8a) | May 09, 2024 |
| Gigabyte      | H410M H V2                  | Desktop     | [fdb662e09b](https://linux-hardware.org/?probe=fdb662e09b) | May 09, 2024 |
| Lenovo        | Yoga Duet IML 2020 82E9     | Tablet      | [469abd69c4](https://linux-hardware.org/?probe=469abd69c4) | May 09, 2024 |
| ASUSTek       | H110M-CS/BR                 | Desktop     | [5c516f0aa0](https://linux-hardware.org/?probe=5c516f0aa0) | May 09, 2024 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [919fba348e](https://linux-hardware.org/?probe=919fba348e) | May 09, 2024 |
| AZW           | MINI S                      | Desktop     | [12557a4240](https://linux-hardware.org/?probe=12557a4240) | May 09, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [6ce58b40cb](https://linux-hardware.org/?probe=6ce58b40cb) | May 09, 2024 |
| Samsung       | 930QED                      | Convertible | [efc32670b1](https://linux-hardware.org/?probe=efc32670b1) | May 09, 2024 |
| HP            | Dev One Notebook PC         | Notebook    | [095bc08ae2](https://linux-hardware.org/?probe=095bc08ae2) | May 09, 2024 |
| Dell          | 0VNP2H A00                  | Desktop     | [28953f7c6a](https://linux-hardware.org/?probe=28953f7c6a) | May 09, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [ee086eec1f](https://linux-hardware.org/?probe=ee086eec1f) | May 09, 2024 |
| Foxconn       | 2AB1                        | Desktop     | [11beb142c3](https://linux-hardware.org/?probe=11beb142c3) | May 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [99879342f6](https://linux-hardware.org/?probe=99879342f6) | May 09, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [dc5b4c6be8](https://linux-hardware.org/?probe=dc5b4c6be8) | May 09, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [291cd1c75f](https://linux-hardware.org/?probe=291cd1c75f) | May 09, 2024 |
| Unknown       | Unknown                     | Notebook    | [64e1e4cc73](https://linux-hardware.org/?probe=64e1e4cc73) | May 09, 2024 |
| HONOR         | BBR-WAX9                    | Notebook    | [be1a16a925](https://linux-hardware.org/?probe=be1a16a925) | May 09, 2024 |
| AZW           | MINI S                      | Desktop     | [7c8e83b2ed](https://linux-hardware.org/?probe=7c8e83b2ed) | May 09, 2024 |
| HONOR         | BBR-WAX9                    | Notebook    | [8c9db99956](https://linux-hardware.org/?probe=8c9db99956) | May 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [d3ffc9eacb](https://linux-hardware.org/?probe=d3ffc9eacb) | May 09, 2024 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [1240b3da0c](https://linux-hardware.org/?probe=1240b3da0c) | May 09, 2024 |
| PCWare        | IPMH61R3                    | Desktop     | [1f3c6428d2](https://linux-hardware.org/?probe=1f3c6428d2) | May 09, 2024 |
| Valve         | Jupiter                     | Notebook    | [18c9c24ecb](https://linux-hardware.org/?probe=18c9c24ecb) | May 09, 2024 |
| Unknown       | Unknown                     | Desktop     | [3027a0b67c](https://linux-hardware.org/?probe=3027a0b67c) | May 09, 2024 |
| MSI           | H310M PRO-VD                | Desktop     | [586c4844be](https://linux-hardware.org/?probe=586c4844be) | May 09, 2024 |
| TianBei       | GEM12                       | Desktop     | [d7b4f33b27](https://linux-hardware.org/?probe=d7b4f33b27) | May 09, 2024 |
| ASRock        | B450M/ac R2.0               | Desktop     | [a20443a9d6](https://linux-hardware.org/?probe=a20443a9d6) | May 09, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [6d6aee3150](https://linux-hardware.org/?probe=6d6aee3150) | May 09, 2024 |
| MSI           | MAG B460M MORTAR WIFI       | Desktop     | [d35204127f](https://linux-hardware.org/?probe=d35204127f) | May 09, 2024 |
| Apple         | MacBookPro9,1               | Notebook    | [2c63121414](https://linux-hardware.org/?probe=2c63121414) | May 09, 2024 |
| Dell          | 051FJ8 A02                  | Desktop     | [1c1caf7a19](https://linux-hardware.org/?probe=1c1caf7a19) | May 09, 2024 |
| Getac         | V110G3                      | Notebook    | [f2bd63cfb8](https://linux-hardware.org/?probe=f2bd63cfb8) | May 09, 2024 |
| Sony          | VPCYB45JB                   | Notebook    | [6f70d22391](https://linux-hardware.org/?probe=6f70d22391) | May 09, 2024 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [2de4ca3c36](https://linux-hardware.org/?probe=2de4ca3c36) | May 09, 2024 |
| MSI           | B450M MORTAR MAX            | Desktop     | [51a4eae4e1](https://linux-hardware.org/?probe=51a4eae4e1) | May 09, 2024 |
| Toshiba       | Satellite C650D             | Notebook    | [9e66892f4b](https://linux-hardware.org/?probe=9e66892f4b) | May 09, 2024 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [fc06be20c3](https://linux-hardware.org/?probe=fc06be20c3) | May 09, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [5782f1959e](https://linux-hardware.org/?probe=5782f1959e) | May 09, 2024 |
| Lenovo        | ThinkBook 13x G4 IMH 21K... | Notebook    | [7cfc568eb2](https://linux-hardware.org/?probe=7cfc568eb2) | May 09, 2024 |
| Panasonic     | FZ55-1                      | Notebook    | [5709bdb252](https://linux-hardware.org/?probe=5709bdb252) | May 09, 2024 |
| ASRock        | X399 Taichi                 | Desktop     | [c82214d90a](https://linux-hardware.org/?probe=c82214d90a) | May 09, 2024 |
| Dell          | Inspiron 13-7359            | Notebook    | [ed773eb204](https://linux-hardware.org/?probe=ed773eb204) | May 09, 2024 |
| Dell          | Vostro 1220                 | Notebook    | [a4ee382052](https://linux-hardware.org/?probe=a4ee382052) | May 09, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [bdcf61edde](https://linux-hardware.org/?probe=bdcf61edde) | May 09, 2024 |
| Dell          | 051FJ8 A02                  | Desktop     | [5a8f86b17c](https://linux-hardware.org/?probe=5a8f86b17c) | May 09, 2024 |
| Gigabyte      | Z87X-UD4H-CF                | Desktop     | [f26982efc3](https://linux-hardware.org/?probe=f26982efc3) | May 09, 2024 |
| Dell          | XPS 15 9520                 | Notebook    | [ef8de4b0d9](https://linux-hardware.org/?probe=ef8de4b0d9) | May 09, 2024 |
| GEEKOM        | MiniAir 11                  | Server      | [9a6f3f3e69](https://linux-hardware.org/?probe=9a6f3f3e69) | May 09, 2024 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [c5f27e5e7b](https://linux-hardware.org/?probe=c5f27e5e7b) | May 09, 2024 |
| Samsung       | 960XGK                      | Notebook    | [4c22b1ca3a](https://linux-hardware.org/?probe=4c22b1ca3a) | May 09, 2024 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [56d2614671](https://linux-hardware.org/?probe=56d2614671) | May 09, 2024 |
| eMachines     | WMCP61M                     | Desktop     | [14e676a6db](https://linux-hardware.org/?probe=14e676a6db) | May 09, 2024 |
| Acer          | Aspire V5-121               | Notebook    | [ee7af6bc3d](https://linux-hardware.org/?probe=ee7af6bc3d) | May 09, 2024 |
| HP            | 8711                        | Mini pc     | [dd252958ea](https://linux-hardware.org/?probe=dd252958ea) | May 09, 2024 |
| Gigabyte      | G5 GE                       | Notebook    | [938a8a3f8e](https://linux-hardware.org/?probe=938a8a3f8e) | May 09, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [4f2761bde5](https://linux-hardware.org/?probe=4f2761bde5) | May 09, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [6bb0aa91af](https://linux-hardware.org/?probe=6bb0aa91af) | May 09, 2024 |
| Ultra         | UB42X                       | Notebook    | [b7f2dbd777](https://linux-hardware.org/?probe=b7f2dbd777) | May 09, 2024 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [5fad364df3](https://linux-hardware.org/?probe=5fad364df3) | May 09, 2024 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | Notebook    | [86d66670cb](https://linux-hardware.org/?probe=86d66670cb) | May 09, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [03e53efb87](https://linux-hardware.org/?probe=03e53efb87) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [821372cdbd](https://linux-hardware.org/?probe=821372cdbd) | May 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K370... | Notebook    | [57bc46051b](https://linux-hardware.org/?probe=57bc46051b) | May 08, 2024 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [813f68dad3](https://linux-hardware.org/?probe=813f68dad3) | May 08, 2024 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [1a1e8edc3b](https://linux-hardware.org/?probe=1a1e8edc3b) | May 08, 2024 |
| ATOPNUC       | MA90                        | Mini pc     | [8098193095](https://linux-hardware.org/?probe=8098193095) | May 08, 2024 |
| Micro Comp... | V3                          | Tablet      | [8a0c0d99f9](https://linux-hardware.org/?probe=8a0c0d99f9) | May 08, 2024 |
| Ultra         | UB42X                       | Notebook    | [4597d0586d](https://linux-hardware.org/?probe=4597d0586d) | May 08, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7cd20b2530](https://linux-hardware.org/?probe=7cd20b2530) | May 08, 2024 |
| Medion        | Cattle24 -1M                | Desktop     | [aa19188799](https://linux-hardware.org/?probe=aa19188799) | May 08, 2024 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [221cf17e59](https://linux-hardware.org/?probe=221cf17e59) | May 08, 2024 |
| Dell          | Vostro 1220                 | Notebook    | [7f6372d340](https://linux-hardware.org/?probe=7f6372d340) | May 08, 2024 |
| MSI           | GE66 Raider 10UG            | Notebook    | [d19e5447f5](https://linux-hardware.org/?probe=d19e5447f5) | May 08, 2024 |
| Packard Be... | EasyNote LM98               | Notebook    | [4826f72192](https://linux-hardware.org/?probe=4826f72192) | May 08, 2024 |
| Toshiba       | PORTEGE Z30-C               | Notebook    | [38ddab3b19](https://linux-hardware.org/?probe=38ddab3b19) | May 08, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [58b9bbc4d6](https://linux-hardware.org/?probe=58b9bbc4d6) | May 08, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [259fba9825](https://linux-hardware.org/?probe=259fba9825) | May 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [fadecff7cd](https://linux-hardware.org/?probe=fadecff7cd) | May 08, 2024 |
| Lenovo        | G50-45 80E3                 | Notebook    | [801eeb31ef](https://linux-hardware.org/?probe=801eeb31ef) | May 08, 2024 |
| Apple         | MacBookPro8,2               | Notebook    | [2410273443](https://linux-hardware.org/?probe=2410273443) | May 08, 2024 |
| Lenovo        | ThinkPad T410 2537MN9       | Notebook    | [7deebe7ca3](https://linux-hardware.org/?probe=7deebe7ca3) | May 08, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [14c3adea64](https://linux-hardware.org/?probe=14c3adea64) | May 08, 2024 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [7a88f50508](https://linux-hardware.org/?probe=7a88f50508) | May 08, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [5283cfbe48](https://linux-hardware.org/?probe=5283cfbe48) | May 08, 2024 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [6143f9e1aa](https://linux-hardware.org/?probe=6143f9e1aa) | May 08, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [2ea426bed2](https://linux-hardware.org/?probe=2ea426bed2) | May 08, 2024 |
| HP            | 18E7                        | Desktop     | [fa637b3b9a](https://linux-hardware.org/?probe=fa637b3b9a) | May 08, 2024 |
| Intel         | X99                         | Desktop     | [a02c0050f2](https://linux-hardware.org/?probe=a02c0050f2) | May 08, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [bc8a5150c3](https://linux-hardware.org/?probe=bc8a5150c3) | May 08, 2024 |
| Lenovo        | ThinkPad X230 2333A91       | Notebook    | [3ad48e3ebe](https://linux-hardware.org/?probe=3ad48e3ebe) | May 08, 2024 |
| Dell          | 0M858N A01                  | Desktop     | [9b34c8bbc2](https://linux-hardware.org/?probe=9b34c8bbc2) | May 08, 2024 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [da62dd4045](https://linux-hardware.org/?probe=da62dd4045) | May 08, 2024 |
| Avell High... | A70 MOB                     | Notebook    | [2be654083e](https://linux-hardware.org/?probe=2be654083e) | May 08, 2024 |
| ASUSTek       | P8H67                       | Desktop     | [ebf3b0112a](https://linux-hardware.org/?probe=ebf3b0112a) | May 08, 2024 |
| Sony          | SVP1321C5E                  | Notebook    | [373fd0a046](https://linux-hardware.org/?probe=373fd0a046) | May 08, 2024 |
| ASUSTek       | H110M-A/DP                  | Desktop     | [b8d75a4ac5](https://linux-hardware.org/?probe=b8d75a4ac5) | May 08, 2024 |
| Unknown       | MT6785V/CC (DT)             | Soc         | [e3e06b8a94](https://linux-hardware.org/?probe=e3e06b8a94) | May 08, 2024 |
| Dell          | Latitude 5530               | Notebook    | [f91e424e6d](https://linux-hardware.org/?probe=f91e424e6d) | May 08, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [762a9e4609](https://linux-hardware.org/?probe=762a9e4609) | May 08, 2024 |
| ASUSTek       | P8H67                       | Desktop     | [7c9d6cd1b4](https://linux-hardware.org/?probe=7c9d6cd1b4) | May 08, 2024 |
| HP            | Stream x360 Convertible ... | Convertible | [0fd35e9fda](https://linux-hardware.org/?probe=0fd35e9fda) | May 08, 2024 |
| Lenovo        | ThinkPad E14 Gen 3 20YFC... | Notebook    | [6a43088440](https://linux-hardware.org/?probe=6a43088440) | May 08, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f3aa52459b](https://linux-hardware.org/?probe=f3aa52459b) | May 08, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [5d23c7ed6f](https://linux-hardware.org/?probe=5d23c7ed6f) | May 08, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [1baa287464](https://linux-hardware.org/?probe=1baa287464) | May 08, 2024 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [6fd6f40abe](https://linux-hardware.org/?probe=6fd6f40abe) | May 08, 2024 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [8256dfc204](https://linux-hardware.org/?probe=8256dfc204) | May 08, 2024 |
| VALE          | Notebook Evolution i5-11... | Notebook    | [55764ee04d](https://linux-hardware.org/?probe=55764ee04d) | May 08, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [11d69e96cb](https://linux-hardware.org/?probe=11d69e96cb) | May 08, 2024 |
| GEEKOM        | Mini Air12                  | Server      | [c02c2be45e](https://linux-hardware.org/?probe=c02c2be45e) | May 08, 2024 |
| ASUSTek       | K54HR                       | Notebook    | [67ddde3a75](https://linux-hardware.org/?probe=67ddde3a75) | May 08, 2024 |
| HP            | ProBook 4740s               | Notebook    | [7f39194517](https://linux-hardware.org/?probe=7f39194517) | May 08, 2024 |
| Lenovo        | ThinkPad T470 20HES18C00    | Notebook    | [a2d8841244](https://linux-hardware.org/?probe=a2d8841244) | May 08, 2024 |
| HUAWEI        | BC11HGSB0 V100R003          | Server      | [ce27371402](https://linux-hardware.org/?probe=ce27371402) | May 08, 2024 |
| Dell          | Latitude E5520              | Notebook    | [1dc92b60a8](https://linux-hardware.org/?probe=1dc92b60a8) | May 08, 2024 |
| MSI           | H310M PRO-M2 PLUS           | Desktop     | [969ea9ed0c](https://linux-hardware.org/?probe=969ea9ed0c) | May 08, 2024 |
| ASRock        | H61M                        | Desktop     | [4db6a46097](https://linux-hardware.org/?probe=4db6a46097) | May 08, 2024 |
| ECT           | ONE GAMING Notebook K56-... | Notebook    | [64028f3e06](https://linux-hardware.org/?probe=64028f3e06) | May 08, 2024 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [31a04e0322](https://linux-hardware.org/?probe=31a04e0322) | May 08, 2024 |
| Sony          | VPCEB1S1E                   | Notebook    | [551a1d2f64](https://linux-hardware.org/?probe=551a1d2f64) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [20ab787216](https://linux-hardware.org/?probe=20ab787216) | May 08, 2024 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [f6e1a31fef](https://linux-hardware.org/?probe=f6e1a31fef) | May 08, 2024 |
| Dell          | XPS 15 7590                 | Notebook    | [a4b733d1fe](https://linux-hardware.org/?probe=a4b733d1fe) | May 08, 2024 |
| MSI           | Z77A-G43                    | Desktop     | [f7e7eb8397](https://linux-hardware.org/?probe=f7e7eb8397) | May 08, 2024 |
| Dell          | Inspiron N5040              | Notebook    | [5fae884a07](https://linux-hardware.org/?probe=5fae884a07) | May 08, 2024 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [ed0902f81c](https://linux-hardware.org/?probe=ed0902f81c) | May 08, 2024 |
| ASUSTek       | LEONITE                     | Desktop     | [a50f5f9e3a](https://linux-hardware.org/?probe=a50f5f9e3a) | May 08, 2024 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [a415a1e824](https://linux-hardware.org/?probe=a415a1e824) | May 08, 2024 |
| ASUSTek       | GL753VE                     | Notebook    | [17bf72a741](https://linux-hardware.org/?probe=17bf72a741) | May 08, 2024 |
| Acer          | Aspire A315-21              | Notebook    | [a838a7101f](https://linux-hardware.org/?probe=a838a7101f) | May 08, 2024 |
| Lenovo        | 110536U ThinkServer TS13... | Desktop     | [d3196733cd](https://linux-hardware.org/?probe=d3196733cd) | May 08, 2024 |
| HP            | EliteBook 735 G5            | Notebook    | [628e01fd2b](https://linux-hardware.org/?probe=628e01fd2b) | May 08, 2024 |
| ASRock        | H61M                        | Desktop     | [cf55ba331e](https://linux-hardware.org/?probe=cf55ba331e) | May 08, 2024 |
| Intel         | STCK1A32WFC H67490-302      | Notebook    | [51c75f3848](https://linux-hardware.org/?probe=51c75f3848) | May 08, 2024 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [c8d8b57bc2](https://linux-hardware.org/?probe=c8d8b57bc2) | May 08, 2024 |
| HP            | ProBook 6460b               | Notebook    | [14aa46f09d](https://linux-hardware.org/?probe=14aa46f09d) | May 08, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [3c353c281f](https://linux-hardware.org/?probe=3c353c281f) | May 08, 2024 |
| Gigabyte      | B650 AORUS ELITE AX V2      | Desktop     | [cb100ba8bc](https://linux-hardware.org/?probe=cb100ba8bc) | May 08, 2024 |
| Infinix       | INBOOK Y1 PLUS NEO          | Notebook    | [253042bbd9](https://linux-hardware.org/?probe=253042bbd9) | May 08, 2024 |
| Acer          | Aspire 5720                 | Notebook    | [0a218dfdfe](https://linux-hardware.org/?probe=0a218dfdfe) | May 08, 2024 |
| TianBei       | GEM12                       | Desktop     | [5e850d92f6](https://linux-hardware.org/?probe=5e850d92f6) | May 08, 2024 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [34cb8ea20b](https://linux-hardware.org/?probe=34cb8ea20b) | May 08, 2024 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [8210b8f2f9](https://linux-hardware.org/?probe=8210b8f2f9) | May 08, 2024 |
| ASUSTek       | N61Vn                       | Notebook    | [07f83fc6c0](https://linux-hardware.org/?probe=07f83fc6c0) | May 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [91ed38bf6d](https://linux-hardware.org/?probe=91ed38bf6d) | May 08, 2024 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [2bf4332abb](https://linux-hardware.org/?probe=2bf4332abb) | May 08, 2024 |
| Biostar       | A320MH                      | Desktop     | [404917c360](https://linux-hardware.org/?probe=404917c360) | May 08, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [0cd34decca](https://linux-hardware.org/?probe=0cd34decca) | May 08, 2024 |
| Micro Elec... | MG-VCP15I-3070              | Notebook    | [11e90f3f8f](https://linux-hardware.org/?probe=11e90f3f8f) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7c01de63e1](https://linux-hardware.org/?probe=7c01de63e1) | May 08, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [ed064c4025](https://linux-hardware.org/?probe=ed064c4025) | May 08, 2024 |
| Dell          | Inspiron 7415 2-in-1        | Convertible | [8f09e9d011](https://linux-hardware.org/?probe=8f09e9d011) | May 08, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [2786d2f8f8](https://linux-hardware.org/?probe=2786d2f8f8) | May 08, 2024 |
| Gigabyte      | B760M DS3H AX DDR4          | Desktop     | [8556d97dea](https://linux-hardware.org/?probe=8556d97dea) | May 08, 2024 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [e896127dc3](https://linux-hardware.org/?probe=e896127dc3) | May 08, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [b981a13960](https://linux-hardware.org/?probe=b981a13960) | May 08, 2024 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [541eebe872](https://linux-hardware.org/?probe=541eebe872) | May 08, 2024 |
| ASUSTek       | X550LD                      | Notebook    | [1c55e1acf7](https://linux-hardware.org/?probe=1c55e1acf7) | May 08, 2024 |
| Samsung       | SR700                       | Notebook    | [97ed5b7fc7](https://linux-hardware.org/?probe=97ed5b7fc7) | May 08, 2024 |
| ASRock        | Z77 Performance             | Desktop     | [500cd7ed60](https://linux-hardware.org/?probe=500cd7ed60) | May 08, 2024 |
| ASUSTek       | X705UVP                     | Notebook    | [b850816596](https://linux-hardware.org/?probe=b850816596) | May 08, 2024 |
| Supermicro    | X9DRW                       | Server      | [fd0af1a212](https://linux-hardware.org/?probe=fd0af1a212) | May 08, 2024 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [b67da2effc](https://linux-hardware.org/?probe=b67da2effc) | May 08, 2024 |
| Dell          | Latitude E6540              | Notebook    | [c6c6acf7d2](https://linux-hardware.org/?probe=c6c6acf7d2) | May 08, 2024 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c5c2b3b9c0](https://linux-hardware.org/?probe=c5c2b3b9c0) | May 08, 2024 |
| Sony          | VGN-NS12M_W                 | Notebook    | [e364d75564](https://linux-hardware.org/?probe=e364d75564) | May 08, 2024 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [291c23ee80](https://linux-hardware.org/?probe=291c23ee80) | May 08, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ab440c0aca](https://linux-hardware.org/?probe=ab440c0aca) | May 08, 2024 |
| Panasonic     | CF-53SAWZYMN                | Notebook    | [15a322275f](https://linux-hardware.org/?probe=15a322275f) | May 08, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [3742af3546](https://linux-hardware.org/?probe=3742af3546) | May 08, 2024 |
| Sony          | VGN-Z51MG_B                 | Notebook    | [6e5ed9d5f6](https://linux-hardware.org/?probe=6e5ed9d5f6) | May 08, 2024 |
| Acer          | Aspire AL14-31P             | Notebook    | [fc4db570af](https://linux-hardware.org/?probe=fc4db570af) | May 08, 2024 |
| MSI           | Z170A GAMING M7             | Desktop     | [e1892a119b](https://linux-hardware.org/?probe=e1892a119b) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ae1ef1680a](https://linux-hardware.org/?probe=ae1ef1680a) | May 08, 2024 |
| MSI           | MS-B120                     | Mini pc     | [29451ebbbb](https://linux-hardware.org/?probe=29451ebbbb) | May 08, 2024 |
| Acer          | Swift SF314-71              | Notebook    | [23d1f2e74a](https://linux-hardware.org/?probe=23d1f2e74a) | May 08, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [38ae310bd0](https://linux-hardware.org/?probe=38ae310bd0) | May 08, 2024 |
| Acer          | P7YE0                       | Notebook    | [21da78891a](https://linux-hardware.org/?probe=21da78891a) | May 08, 2024 |
| MSI           | MS-7255                     | Desktop     | [5e4c3d17d6](https://linux-hardware.org/?probe=5e4c3d17d6) | May 08, 2024 |
| ASRock        | B450M-HDV                   | Desktop     | [098e62d52a](https://linux-hardware.org/?probe=098e62d52a) | May 08, 2024 |
| Linx          | LINX1010B                   | Notebook    | [782fb4ec65](https://linux-hardware.org/?probe=782fb4ec65) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10c139f22b](https://linux-hardware.org/?probe=10c139f22b) | May 08, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [e00e076344](https://linux-hardware.org/?probe=e00e076344) | May 08, 2024 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [d1a276f0c5](https://linux-hardware.org/?probe=d1a276f0c5) | May 08, 2024 |
| Sony          | VGN-CR31S_W                 | Notebook    | [7e7d96c020](https://linux-hardware.org/?probe=7e7d96c020) | May 08, 2024 |
| HP            | 8AC1                        | Desktop     | [34fb750829](https://linux-hardware.org/?probe=34fb750829) | May 08, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [54f40400ed](https://linux-hardware.org/?probe=54f40400ed) | May 08, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [2143043fa4](https://linux-hardware.org/?probe=2143043fa4) | May 08, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [5de84bcb38](https://linux-hardware.org/?probe=5de84bcb38) | May 08, 2024 |
| HP            | ProLiant DL160 G6           | Server      | [1f19c32b7d](https://linux-hardware.org/?probe=1f19c32b7d) | May 08, 2024 |
| HP            | 83E5                        | All in one  | [38a2509046](https://linux-hardware.org/?probe=38a2509046) | May 08, 2024 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [ea4077ed1b](https://linux-hardware.org/?probe=ea4077ed1b) | May 08, 2024 |
| Dell          | Latitude E6540              | Notebook    | [a57f8ef498](https://linux-hardware.org/?probe=a57f8ef498) | May 08, 2024 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | Notebook    | [d77842b741](https://linux-hardware.org/?probe=d77842b741) | May 08, 2024 |
| Dell          | Latitude E5520              | Notebook    | [1c27a2760d](https://linux-hardware.org/?probe=1c27a2760d) | May 08, 2024 |
| MSI           | B650M GAMING PLUS WIFI      | Desktop     | [be715853f7](https://linux-hardware.org/?probe=be715853f7) | May 08, 2024 |
| Fujitsu       | D3403-U1 S26361-D3403-U1    | Desktop     | [75811cd1df](https://linux-hardware.org/?probe=75811cd1df) | May 08, 2024 |
| EVOC          | P7xxTM1                     | Notebook    | [7c15b2991c](https://linux-hardware.org/?probe=7c15b2991c) | May 08, 2024 |
| HP            | 89EB 11                     | Desktop     | [f53a08bd5c](https://linux-hardware.org/?probe=f53a08bd5c) | May 08, 2024 |
| Lenovo        | ThinkPad T440s 20AQ0069G... | Notebook    | [b84ba3c6c7](https://linux-hardware.org/?probe=b84ba3c6c7) | May 08, 2024 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [ac49e3fa07](https://linux-hardware.org/?probe=ac49e3fa07) | May 08, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c9bee8e35a](https://linux-hardware.org/?probe=c9bee8e35a) | May 08, 2024 |
| ASUSTek       | E5402WHA                    | All in one  | [9db61e60e0](https://linux-hardware.org/?probe=9db61e60e0) | May 08, 2024 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [6ac93f82e9](https://linux-hardware.org/?probe=6ac93f82e9) | May 08, 2024 |
| Sony          | VPCF13E1R                   | Notebook    | [593de85e33](https://linux-hardware.org/?probe=593de85e33) | May 08, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [64289cb32c](https://linux-hardware.org/?probe=64289cb32c) | May 08, 2024 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [3514a63f05](https://linux-hardware.org/?probe=3514a63f05) | May 08, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [fcc3b9cc19](https://linux-hardware.org/?probe=fcc3b9cc19) | May 08, 2024 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [e4c7ca80f3](https://linux-hardware.org/?probe=e4c7ca80f3) | May 08, 2024 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [336a5b4e2b](https://linux-hardware.org/?probe=336a5b4e2b) | May 08, 2024 |
| HP            | EliteBook 840 G8            | Notebook    | [6d255e156e](https://linux-hardware.org/?probe=6d255e156e) | May 08, 2024 |
| Hetrix        | Unknown                     | Notebook    | [72a5c6fffe](https://linux-hardware.org/?probe=72a5c6fffe) | May 08, 2024 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [7ad1e2a464](https://linux-hardware.org/?probe=7ad1e2a464) | May 08, 2024 |
| Gigabyte      | H81M-S1                     | Desktop     | [3566b1666c](https://linux-hardware.org/?probe=3566b1666c) | May 08, 2024 |
| ASUSTek       | E520                        | Desktop     | [4e025280e9](https://linux-hardware.org/?probe=4e025280e9) | May 08, 2024 |
| HP            | ZBook 15 G3                 | Notebook    | [8fbd2e21a7](https://linux-hardware.org/?probe=8fbd2e21a7) | May 08, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [eb9d3c539c](https://linux-hardware.org/?probe=eb9d3c539c) | May 08, 2024 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [29552fbf93](https://linux-hardware.org/?probe=29552fbf93) | May 08, 2024 |
| Gigabyte      | B560M H                     | Desktop     | [9d2a9c59a3](https://linux-hardware.org/?probe=9d2a9c59a3) | May 08, 2024 |
| Alienware     | M17x                        | Notebook    | [349d219a3a](https://linux-hardware.org/?probe=349d219a3a) | May 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [b18d2c1ec2](https://linux-hardware.org/?probe=b18d2c1ec2) | May 08, 2024 |
| Dell          | Precision 5560              | Notebook    | [9ad14a0547](https://linux-hardware.org/?probe=9ad14a0547) | May 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [07a1876fd0](https://linux-hardware.org/?probe=07a1876fd0) | May 08, 2024 |
| ECS           | MCP61M-M3                   | Desktop     | [4a66244a0d](https://linux-hardware.org/?probe=4a66244a0d) | May 08, 2024 |
| MSI           | B450M-A PRO MAX II          | Desktop     | [cd66ff303c](https://linux-hardware.org/?probe=cd66ff303c) | May 08, 2024 |
| Toshiba       | Satellite E55-A             | Notebook    | [b77667e33a](https://linux-hardware.org/?probe=b77667e33a) | May 08, 2024 |
| Dell          | Inspiron 5420               | Notebook    | [24c2d41566](https://linux-hardware.org/?probe=24c2d41566) | May 08, 2024 |
| Lenovo        | G580 20150                  | Notebook    | [3a9861e2be](https://linux-hardware.org/?probe=3a9861e2be) | May 08, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6c7c8f37e0](https://linux-hardware.org/?probe=6c7c8f37e0) | May 08, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5c2ce66225](https://linux-hardware.org/?probe=5c2ce66225) | May 08, 2024 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [d9c35695a3](https://linux-hardware.org/?probe=d9c35695a3) | May 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [c0eded1dbf](https://linux-hardware.org/?probe=c0eded1dbf) | May 08, 2024 |
| MSI           | GT60 2OC/2OD                | Notebook    | [aa9d5951b9](https://linux-hardware.org/?probe=aa9d5951b9) | May 08, 2024 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [7cc03eaae9](https://linux-hardware.org/?probe=7cc03eaae9) | May 08, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [43cb45f5c4](https://linux-hardware.org/?probe=43cb45f5c4) | May 08, 2024 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [e49b5301ae](https://linux-hardware.org/?probe=e49b5301ae) | May 08, 2024 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [8acc6c69a3](https://linux-hardware.org/?probe=8acc6c69a3) | May 08, 2024 |
| HP            | 1495                        | Desktop     | [89464c1187](https://linux-hardware.org/?probe=89464c1187) | May 08, 2024 |
| Apple         | MacBookPro11,2              | Notebook    | [0ff911f7ac](https://linux-hardware.org/?probe=0ff911f7ac) | May 08, 2024 |
| ECS           | H61H2-CM                    | Desktop     | [65f99c7e8d](https://linux-hardware.org/?probe=65f99c7e8d) | May 08, 2024 |
| Samsung       | 270E5G/270E5U               | Notebook    | [11c56432a4](https://linux-hardware.org/?probe=11c56432a4) | May 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [dd5fb659cb](https://linux-hardware.org/?probe=dd5fb659cb) | May 08, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [796a659b4e](https://linux-hardware.org/?probe=796a659b4e) | May 08, 2024 |
| MSI           | PRO B650M-P                 | Desktop     | [2490ea1b56](https://linux-hardware.org/?probe=2490ea1b56) | May 08, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [8d2df2d585](https://linux-hardware.org/?probe=8d2df2d585) | May 08, 2024 |
| Lenovo        | ThinkPad Edge 031946U       | Notebook    | [8f8fb39c6e](https://linux-hardware.org/?probe=8f8fb39c6e) | May 08, 2024 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [964b717d95](https://linux-hardware.org/?probe=964b717d95) | May 08, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [199cd47039](https://linux-hardware.org/?probe=199cd47039) | May 08, 2024 |
| HP            | EliteBook 8560p             | Notebook    | [fa48702e03](https://linux-hardware.org/?probe=fa48702e03) | May 08, 2024 |
| Gigabyte      | H81M-S2H                    | Desktop     | [217f6991ee](https://linux-hardware.org/?probe=217f6991ee) | May 08, 2024 |
| MSI           | GF63 Thin 10SC              | Notebook    | [d419afc35f](https://linux-hardware.org/?probe=d419afc35f) | May 08, 2024 |
| HP            | Laptop 15-bs0xx             | Notebook    | [f0bc418296](https://linux-hardware.org/?probe=f0bc418296) | May 08, 2024 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [ade9d916fe](https://linux-hardware.org/?probe=ade9d916fe) | May 08, 2024 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [c4d3aa24cf](https://linux-hardware.org/?probe=c4d3aa24cf) | May 08, 2024 |
| ASUSTek       | B150 PRO GAMING             | Desktop     | [d559ef5203](https://linux-hardware.org/?probe=d559ef5203) | May 08, 2024 |
| Dell          | 0HHV7N A00                  | Desktop     | [63a26dac69](https://linux-hardware.org/?probe=63a26dac69) | May 08, 2024 |
| Acer          | Swift SFX16-61G             | Notebook    | [9cbd40bfc7](https://linux-hardware.org/?probe=9cbd40bfc7) | May 08, 2024 |
| Fujitsu       | FMVNR1PE                    | Notebook    | [95504ca73e](https://linux-hardware.org/?probe=95504ca73e) | May 08, 2024 |
| MSI           | B250M PRO-VDH               | Desktop     | [d11117aeae](https://linux-hardware.org/?probe=d11117aeae) | May 08, 2024 |
| Valve         | Jupiter                     | Notebook    | [cdb467c650](https://linux-hardware.org/?probe=cdb467c650) | May 08, 2024 |
| Gigabyte      | B550M AORUS ELITE AX        | Desktop     | [422cc265d3](https://linux-hardware.org/?probe=422cc265d3) | May 08, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [76e6f087bb](https://linux-hardware.org/?probe=76e6f087bb) | May 08, 2024 |
| NEC Comput... | PC-LS350SSB                 | Notebook    | [530b3713dd](https://linux-hardware.org/?probe=530b3713dd) | May 08, 2024 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [eab2642002](https://linux-hardware.org/?probe=eab2642002) | May 08, 2024 |
| ASUSTek       | X540SA                      | Notebook    | [456909c790](https://linux-hardware.org/?probe=456909c790) | May 08, 2024 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [fea6956058](https://linux-hardware.org/?probe=fea6956058) | May 08, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [511ee9983e](https://linux-hardware.org/?probe=511ee9983e) | May 08, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [acfeddfe20](https://linux-hardware.org/?probe=acfeddfe20) | May 08, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [516e53ae7f](https://linux-hardware.org/?probe=516e53ae7f) | May 08, 2024 |
| Digma         | Pro Magnus M DN16R9-ADXW... | Notebook    | [beee17622d](https://linux-hardware.org/?probe=beee17622d) | May 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [14f9a58589](https://linux-hardware.org/?probe=14f9a58589) | May 08, 2024 |
| Matsushita... | CF-74GCDADBM                | Notebook    | [f353aa5d7c](https://linux-hardware.org/?probe=f353aa5d7c) | May 08, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [f7eef71378](https://linux-hardware.org/?probe=f7eef71378) | May 08, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [13c15b0230](https://linux-hardware.org/?probe=13c15b0230) | May 08, 2024 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [73ee3d2b74](https://linux-hardware.org/?probe=73ee3d2b74) | May 08, 2024 |
| Dell          | 0GN6JF A01                  | Desktop     | [b9877feccd](https://linux-hardware.org/?probe=b9877feccd) | May 08, 2024 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [1be8775956](https://linux-hardware.org/?probe=1be8775956) | May 08, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3292b37df6](https://linux-hardware.org/?probe=3292b37df6) | May 08, 2024 |
| Sony          | SVE1412BCXB                 | Notebook    | [593942e0e3](https://linux-hardware.org/?probe=593942e0e3) | May 08, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [5aee2550ce](https://linux-hardware.org/?probe=5aee2550ce) | May 08, 2024 |
| Schenker      | VISION 16 Pro (L22)         | Notebook    | [c54f918726](https://linux-hardware.org/?probe=c54f918726) | May 08, 2024 |
| ASUSTek       | P5Q SE2                     | Desktop     | [cf126cd087](https://linux-hardware.org/?probe=cf126cd087) | May 08, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [41c99b8030](https://linux-hardware.org/?probe=41c99b8030) | May 08, 2024 |
| ASUSTek       | UX430UQ                     | Notebook    | [7b9134699a](https://linux-hardware.org/?probe=7b9134699a) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [eb38e0f3a5](https://linux-hardware.org/?probe=eb38e0f3a5) | May 08, 2024 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [6021a53b71](https://linux-hardware.org/?probe=6021a53b71) | May 08, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [35d60afe01](https://linux-hardware.org/?probe=35d60afe01) | May 07, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [af6bde9c97](https://linux-hardware.org/?probe=af6bde9c97) | May 07, 2024 |
| Dell          | Vostro 1015                 | Notebook    | [b5f6b13138](https://linux-hardware.org/?probe=b5f6b13138) | May 07, 2024 |
| ASUSTek       | Q550LF                      | Notebook    | [15c9500499](https://linux-hardware.org/?probe=15c9500499) | May 07, 2024 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | Notebook    | [b1a0c45242](https://linux-hardware.org/?probe=b1a0c45242) | May 07, 2024 |
| Dell          | Precision 7540              | Notebook    | [4703617413](https://linux-hardware.org/?probe=4703617413) | May 07, 2024 |
| ASUSTek       | Q550LF                      | Notebook    | [98ddf90ae6](https://linux-hardware.org/?probe=98ddf90ae6) | May 07, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1755d8da2b](https://linux-hardware.org/?probe=1755d8da2b) | May 07, 2024 |
| Lenovo        | ThinkPad T490 20N2003PUS    | Notebook    | [7f484baa22](https://linux-hardware.org/?probe=7f484baa22) | May 07, 2024 |
| Lenovo        | B50-30 80ES                 | Notebook    | [c19f3dfc3a](https://linux-hardware.org/?probe=c19f3dfc3a) | May 07, 2024 |
| Dell          | Precision 7540              | Notebook    | [37638500df](https://linux-hardware.org/?probe=37638500df) | May 07, 2024 |
| Dell          | Inspiron 7558               | Notebook    | [6d19146c49](https://linux-hardware.org/?probe=6d19146c49) | May 07, 2024 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [97598b9cc3](https://linux-hardware.org/?probe=97598b9cc3) | May 07, 2024 |
| Acer          | Swift SF314-52              | Notebook    | [d112cef6d2](https://linux-hardware.org/?probe=d112cef6d2) | May 07, 2024 |
| Samsung       | 530XBB                      | Notebook    | [5c0772cde4](https://linux-hardware.org/?probe=5c0772cde4) | May 07, 2024 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [6aa44077ff](https://linux-hardware.org/?probe=6aa44077ff) | May 07, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [d4d583a573](https://linux-hardware.org/?probe=d4d583a573) | May 07, 2024 |
| HP            | ProBook 430 G6              | Notebook    | [696c3f2a72](https://linux-hardware.org/?probe=696c3f2a72) | May 07, 2024 |
| Dell          | Latitude D830               | Notebook    | [831a2196a3](https://linux-hardware.org/?probe=831a2196a3) | May 07, 2024 |
| Lenovo        | 1046 SDK0T08861 WIN 3305... | Desktop     | [91c857f51e](https://linux-hardware.org/?probe=91c857f51e) | May 07, 2024 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [14bb67e07a](https://linux-hardware.org/?probe=14bb67e07a) | May 07, 2024 |
| Acer          | Aspire A515-54              | Notebook    | [f7d068c059](https://linux-hardware.org/?probe=f7d068c059) | May 07, 2024 |
| ASUSTek       | PRIME B760M-A WIFI D4       | Desktop     | [d83d6a3460](https://linux-hardware.org/?probe=d83d6a3460) | May 07, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [cdcaeb4d46](https://linux-hardware.org/?probe=cdcaeb4d46) | May 07, 2024 |
| Intel         | H55                         | Desktop     | [83c1ac4239](https://linux-hardware.org/?probe=83c1ac4239) | May 07, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [2f571c8d88](https://linux-hardware.org/?probe=2f571c8d88) | May 07, 2024 |
| Acer          | Aspire A515-54              | Notebook    | [f9375ff03c](https://linux-hardware.org/?probe=f9375ff03c) | May 07, 2024 |
| Fujitsu Si... | LIFEBOOK E8410              | Notebook    | [30a913526e](https://linux-hardware.org/?probe=30a913526e) | May 07, 2024 |
| Dell          | 0215PR A02                  | Desktop     | [ff480889b4](https://linux-hardware.org/?probe=ff480889b4) | May 07, 2024 |
| ASUSTek       | H110M-A                     | Desktop     | [e4868e57a3](https://linux-hardware.org/?probe=e4868e57a3) | May 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [3b821d76a7](https://linux-hardware.org/?probe=3b821d76a7) | May 07, 2024 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [8b5ef47376](https://linux-hardware.org/?probe=8b5ef47376) | May 07, 2024 |
| Dell          | 0WR7PY A01                  | Desktop     | [f154c6f22e](https://linux-hardware.org/?probe=f154c6f22e) | May 07, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C70... | Notebook    | [701d936a1c](https://linux-hardware.org/?probe=701d936a1c) | May 07, 2024 |
| MSI           | Z170A-G43 PLUS              | Desktop     | [cbc2d08a03](https://linux-hardware.org/?probe=cbc2d08a03) | May 07, 2024 |
| Valve         | Galileo                     | Notebook    | [9b9caa6850](https://linux-hardware.org/?probe=9b9caa6850) | May 07, 2024 |
| ASRock        | Z390 Pro4                   | Desktop     | [ee53393400](https://linux-hardware.org/?probe=ee53393400) | May 07, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [bc53340b58](https://linux-hardware.org/?probe=bc53340b58) | May 07, 2024 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [6b97d23143](https://linux-hardware.org/?probe=6b97d23143) | May 07, 2024 |
| Dell          | Latitude 5501               | Notebook    | [35d264df4c](https://linux-hardware.org/?probe=35d264df4c) | May 07, 2024 |
| ASUSTek       | X550LN                      | Notebook    | [b139a58ea9](https://linux-hardware.org/?probe=b139a58ea9) | May 07, 2024 |
| HP            | TouchSmart tm2              | Notebook    | [b180e1388d](https://linux-hardware.org/?probe=b180e1388d) | May 07, 2024 |
| OrangePi      | 4 LTS                       | Soc         | [8671fa709f](https://linux-hardware.org/?probe=8671fa709f) | May 07, 2024 |
| PCSMART       | 7.0                         | Desktop     | [66d6082bf4](https://linux-hardware.org/?probe=66d6082bf4) | May 07, 2024 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [4f7e381c6f](https://linux-hardware.org/?probe=4f7e381c6f) | May 07, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [373b9bdb5c](https://linux-hardware.org/?probe=373b9bdb5c) | May 07, 2024 |
| Lenovo        | ThinkPad L15 Gen 3 21C70... | Notebook    | [6d05bc6b3d](https://linux-hardware.org/?probe=6d05bc6b3d) | May 07, 2024 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [9cd7bfcd0f](https://linux-hardware.org/?probe=9cd7bfcd0f) | May 07, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [cdcf7e98eb](https://linux-hardware.org/?probe=cdcf7e98eb) | May 07, 2024 |
| ASUSTek       | P5K3 Deluxe                 | Desktop     | [b03bf61625](https://linux-hardware.org/?probe=b03bf61625) | May 07, 2024 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [32e408088d](https://linux-hardware.org/?probe=32e408088d) | May 07, 2024 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [9b4c39c111](https://linux-hardware.org/?probe=9b4c39c111) | May 07, 2024 |
| ASUSTek       | X555LD                      | Notebook    | [989d24a4b7](https://linux-hardware.org/?probe=989d24a4b7) | May 07, 2024 |
| Dell          | Vostro 15 3510              | Notebook    | [9236e5d92d](https://linux-hardware.org/?probe=9236e5d92d) | May 07, 2024 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7d4c93ea72](https://linux-hardware.org/?probe=7d4c93ea72) | May 07, 2024 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [22eb41201e](https://linux-hardware.org/?probe=22eb41201e) | May 07, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [c7471afead](https://linux-hardware.org/?probe=c7471afead) | May 07, 2024 |
| HP            | Laptop 15-bs1xx             | Notebook    | [f3c9212dca](https://linux-hardware.org/?probe=f3c9212dca) | May 07, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | Desktop     | [e8e1e2e2f8](https://linux-hardware.org/?probe=e8e1e2e2f8) | May 07, 2024 |
| Lenovo        | IdeaPad C340-15IML 81TL     | Convertible | [467c035ce1](https://linux-hardware.org/?probe=467c035ce1) | May 07, 2024 |
| Fujitsu       | LIFEBOOK U7510              | Notebook    | [a52ed98e85](https://linux-hardware.org/?probe=a52ed98e85) | May 07, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [07a4ffe918](https://linux-hardware.org/?probe=07a4ffe918) | May 07, 2024 |
| Dell          | 0XHGV1 A00                  | Desktop     | [b56a1f70d1](https://linux-hardware.org/?probe=b56a1f70d1) | May 07, 2024 |
| MSI           | P67A-G45                    | Desktop     | [f852d50c62](https://linux-hardware.org/?probe=f852d50c62) | May 07, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f696d03152](https://linux-hardware.org/?probe=f696d03152) | May 07, 2024 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [d919c0d099](https://linux-hardware.org/?probe=d919c0d099) | May 07, 2024 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [ebd9696c7b](https://linux-hardware.org/?probe=ebd9696c7b) | May 07, 2024 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b245c99221](https://linux-hardware.org/?probe=b245c99221) | May 07, 2024 |
| Gigabyte      | H410M H V3                  | Desktop     | [486c191884](https://linux-hardware.org/?probe=486c191884) | May 07, 2024 |
| Lenovo        | G710 20252                  | Notebook    | [a7579b63a0](https://linux-hardware.org/?probe=a7579b63a0) | May 07, 2024 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [54b9c594a0](https://linux-hardware.org/?probe=54b9c594a0) | May 07, 2024 |
| Dell          | 0XHGV1 A00                  | Desktop     | [35681eda7f](https://linux-hardware.org/?probe=35681eda7f) | May 07, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [8c2b9bb30a](https://linux-hardware.org/?probe=8c2b9bb30a) | May 07, 2024 |
| AWOW          | AK41                        | Notebook    | [21d739c59c](https://linux-hardware.org/?probe=21d739c59c) | May 07, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [4536e47198](https://linux-hardware.org/?probe=4536e47198) | May 07, 2024 |
| HP            | 250 G3                      | Notebook    | [c34d89360b](https://linux-hardware.org/?probe=c34d89360b) | May 07, 2024 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [df427b5f9f](https://linux-hardware.org/?probe=df427b5f9f) | May 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [857bd41fc3](https://linux-hardware.org/?probe=857bd41fc3) | May 07, 2024 |
| Fujitsu       | D3544-A1 S26361-D3544-A1... | Desktop     | [e04c4654da](https://linux-hardware.org/?probe=e04c4654da) | May 07, 2024 |
| Gigabyte      | A520M S2H                   | Desktop     | [c14a7e4724](https://linux-hardware.org/?probe=c14a7e4724) | May 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e27e19897e](https://linux-hardware.org/?probe=e27e19897e) | May 07, 2024 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [85239f7dc1](https://linux-hardware.org/?probe=85239f7dc1) | May 07, 2024 |
| Supermicro    | X10DDW-i                    | Desktop     | [ff62f6b4d9](https://linux-hardware.org/?probe=ff62f6b4d9) | May 07, 2024 |
| Supermicro    | X10DDW-i                    | Desktop     | [b849fea196](https://linux-hardware.org/?probe=b849fea196) | May 07, 2024 |
| Supermicro    | X10DDW-i                    | Desktop     | [c20ef4d35b](https://linux-hardware.org/?probe=c20ef4d35b) | May 07, 2024 |
| Supermicro    | X10DDW-i                    | Desktop     | [9b21386a04](https://linux-hardware.org/?probe=9b21386a04) | May 07, 2024 |
| Supermicro    | X10DDW-i                    | Desktop     | [99fbeae8c9](https://linux-hardware.org/?probe=99fbeae8c9) | May 07, 2024 |
| Supermicro    | X10DDW-i                    | Desktop     | [48bb233b46](https://linux-hardware.org/?probe=48bb233b46) | May 07, 2024 |
| Supermicro    | X9DRW                       | Server      | [7915255781](https://linux-hardware.org/?probe=7915255781) | May 07, 2024 |
| Supermicro    | X10DRL-i                    | Desktop     | [da5c3ed75f](https://linux-hardware.org/?probe=da5c3ed75f) | May 07, 2024 |
| Sapphire      | PI-AM3RS760G2               | Desktop     | [7a48c1a73b](https://linux-hardware.org/?probe=7a48c1a73b) | May 07, 2024 |
| Acer          | Veriton N4640G              | Desktop     | [44c62400f4](https://linux-hardware.org/?probe=44c62400f4) | May 07, 2024 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [ec3b3b1daa](https://linux-hardware.org/?probe=ec3b3b1daa) | May 07, 2024 |
| Shenzhen M... | F7BSC                       | Desktop     | [9e6a5eb0e2](https://linux-hardware.org/?probe=9e6a5eb0e2) | May 07, 2024 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [db9ea4ffaf](https://linux-hardware.org/?probe=db9ea4ffaf) | May 07, 2024 |
| Lenovo        | 3148 SDK0J40700 WIN 3258... | Desktop     | [b24f7286d2](https://linux-hardware.org/?probe=b24f7286d2) | May 07, 2024 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [a68c1a8752](https://linux-hardware.org/?probe=a68c1a8752) | May 07, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y2... | Notebook    | [064b211de8](https://linux-hardware.org/?probe=064b211de8) | May 07, 2024 |
| Notebook      | NS50_70MU                   | Notebook    | [99983ceae1](https://linux-hardware.org/?probe=99983ceae1) | May 07, 2024 |
| Gigabyte      | Z97-HD3                     | Desktop     | [85dee8d963](https://linux-hardware.org/?probe=85dee8d963) | May 07, 2024 |
| Acer          | Veriton N4640G              | Desktop     | [ebe4fa74ca](https://linux-hardware.org/?probe=ebe4fa74ca) | May 07, 2024 |
| Lenovo        | 7Z74CTO1WW 07               | Server      | [ecd5a5be36](https://linux-hardware.org/?probe=ecd5a5be36) | May 07, 2024 |
| ASUSTek       | A88XM-E                     | Desktop     | [bba7d20511](https://linux-hardware.org/?probe=bba7d20511) | May 07, 2024 |
| HP            | 250 G3                      | Notebook    | [7ebf68ab6e](https://linux-hardware.org/?probe=7ebf68ab6e) | May 07, 2024 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [48be6a2dbb](https://linux-hardware.org/?probe=48be6a2dbb) | May 07, 2024 |
| Lenovo        | ThinkPad T420s 417032U      | Notebook    | [e6839a3d70](https://linux-hardware.org/?probe=e6839a3d70) | May 07, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [bc9db74da3](https://linux-hardware.org/?probe=bc9db74da3) | May 07, 2024 |
| HP            | 84DE                        | All in one  | [b9c011f515](https://linux-hardware.org/?probe=b9c011f515) | May 07, 2024 |
| Intel         | NUC6i3SYB H81132-505        | Mini pc     | [de6a8d14f1](https://linux-hardware.org/?probe=de6a8d14f1) | May 07, 2024 |
| Lenovo        | Unknown                     | Notebook    | [63995e584e](https://linux-hardware.org/?probe=63995e584e) | May 07, 2024 |
| Notebook      | N150CU                      | Notebook    | [348d0cab2d](https://linux-hardware.org/?probe=348d0cab2d) | May 07, 2024 |
| Acer          | Aspire A315-56              | Notebook    | [37f76a3652](https://linux-hardware.org/?probe=37f76a3652) | May 07, 2024 |
| Toshiba       | TECRA R850                  | Notebook    | [a4fae83513](https://linux-hardware.org/?probe=a4fae83513) | May 07, 2024 |
| PELADN        | WI-6                        | Desktop     | [73069ab9f5](https://linux-hardware.org/?probe=73069ab9f5) | May 07, 2024 |
| Dell          | Latitude 3310 2-in-1        | Convertible | [2b066bf51c](https://linux-hardware.org/?probe=2b066bf51c) | May 07, 2024 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [3206e427b1](https://linux-hardware.org/?probe=3206e427b1) | May 07, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [f41f238d9f](https://linux-hardware.org/?probe=f41f238d9f) | May 07, 2024 |
| Dell          | Latitude 3190               | Notebook    | [102011a182](https://linux-hardware.org/?probe=102011a182) | May 07, 2024 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [b941b8d062](https://linux-hardware.org/?probe=b941b8d062) | May 07, 2024 |
| Dell          | Inspiron 3793               | Notebook    | [02e4c23d86](https://linux-hardware.org/?probe=02e4c23d86) | May 07, 2024 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [714735cd6f](https://linux-hardware.org/?probe=714735cd6f) | May 07, 2024 |
| Dell          | Inspiron 3793               | Notebook    | [00234ed0c4](https://linux-hardware.org/?probe=00234ed0c4) | May 07, 2024 |
| Dell          | XPS 15 9520                 | Notebook    | [70022231bd](https://linux-hardware.org/?probe=70022231bd) | May 07, 2024 |
| Gigabyte      | X570S AERO G                | Desktop     | [051c9db94b](https://linux-hardware.org/?probe=051c9db94b) | May 07, 2024 |
| ASUSTek       | ASUSLaptop_Q530VJ           | Notebook    | [97021794a9](https://linux-hardware.org/?probe=97021794a9) | May 07, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [24cf77eb91](https://linux-hardware.org/?probe=24cf77eb91) | May 07, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3514c9adca](https://linux-hardware.org/?probe=3514c9adca) | May 07, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [c9dab30ab0](https://linux-hardware.org/?probe=c9dab30ab0) | May 07, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [072fd0ea79](https://linux-hardware.org/?probe=072fd0ea79) | May 07, 2024 |
| Dell          | Precision 5560              | Notebook    | [c9f03ecb24](https://linux-hardware.org/?probe=c9f03ecb24) | May 07, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [c2a2f067b4](https://linux-hardware.org/?probe=c2a2f067b4) | May 07, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [2ff26254ae](https://linux-hardware.org/?probe=2ff26254ae) | May 07, 2024 |
| Dell          | Latitude 7480               | Notebook    | [2b3aee3902](https://linux-hardware.org/?probe=2b3aee3902) | May 07, 2024 |
| Daten Tecn... | DT02-M4                     | Notebook    | [88093023ed](https://linux-hardware.org/?probe=88093023ed) | May 07, 2024 |
| HP            | 250 G3                      | Notebook    | [5f00c46a92](https://linux-hardware.org/?probe=5f00c46a92) | May 07, 2024 |
| Gigabyte      | B460 HD3                    | Desktop     | [8d8fcf703b](https://linux-hardware.org/?probe=8d8fcf703b) | May 07, 2024 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [94766b9a5d](https://linux-hardware.org/?probe=94766b9a5d) | May 07, 2024 |
| MSI           | B450-A PRO MAX              | Desktop     | [27adbf1266](https://linux-hardware.org/?probe=27adbf1266) | May 07, 2024 |
| Supermicro    | X8DT6                       | Server      | [9a70e94fb0](https://linux-hardware.org/?probe=9a70e94fb0) | May 07, 2024 |
| Dell          | 048DY8 A01                  | Desktop     | [a81f44c8b4](https://linux-hardware.org/?probe=a81f44c8b4) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [9122522638](https://linux-hardware.org/?probe=9122522638) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [3064d4fb1f](https://linux-hardware.org/?probe=3064d4fb1f) | May 07, 2024 |
| Samsung       | RC530/RC730                 | Notebook    | [9e8af32b68](https://linux-hardware.org/?probe=9e8af32b68) | May 07, 2024 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [7d6b757088](https://linux-hardware.org/?probe=7d6b757088) | May 07, 2024 |
| Intel         | SKYBAY                      | Desktop     | [7e692c7e40](https://linux-hardware.org/?probe=7e692c7e40) | May 07, 2024 |
| ASUSTek       | VivoBook S15 X530UF         | Notebook    | [5725e80488](https://linux-hardware.org/?probe=5725e80488) | May 07, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [230c054c87](https://linux-hardware.org/?probe=230c054c87) | May 07, 2024 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [52ca72625a](https://linux-hardware.org/?probe=52ca72625a) | May 07, 2024 |
| HP            | ENVY Notebook 13-ab0XX      | Notebook    | [a9d1c1234c](https://linux-hardware.org/?probe=a9d1c1234c) | May 07, 2024 |
| GEDU          | YourLand                    | Soc         | [e400f0c9b6](https://linux-hardware.org/?probe=e400f0c9b6) | May 07, 2024 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [fb78e4f92a](https://linux-hardware.org/?probe=fb78e4f92a) | May 07, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [c87a91f892](https://linux-hardware.org/?probe=c87a91f892) | May 07, 2024 |
| MSI           | GL62M 7RDX                  | Notebook    | [df43002002](https://linux-hardware.org/?probe=df43002002) | May 07, 2024 |
| MSI           | Thin GF63 12UCX             | Notebook    | [f253ec6e52](https://linux-hardware.org/?probe=f253ec6e52) | May 07, 2024 |
| ASRock        | B450M Pro4-F                | Desktop     | [0c73837ccd](https://linux-hardware.org/?probe=0c73837ccd) | May 07, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [73060b4642](https://linux-hardware.org/?probe=73060b4642) | May 07, 2024 |
| HP            | Pro x360 435 13.3 inch G... | Convertible | [14aed1eae4](https://linux-hardware.org/?probe=14aed1eae4) | May 07, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [b8e70b0693](https://linux-hardware.org/?probe=b8e70b0693) | May 07, 2024 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [961d8a2758](https://linux-hardware.org/?probe=961d8a2758) | May 07, 2024 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [d97bbebd45](https://linux-hardware.org/?probe=d97bbebd45) | May 07, 2024 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [55fdc987e5](https://linux-hardware.org/?probe=55fdc987e5) | May 07, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [504b36774f](https://linux-hardware.org/?probe=504b36774f) | May 07, 2024 |
| MSI           | GF63 Thin 8SC               | Notebook    | [59abbac521](https://linux-hardware.org/?probe=59abbac521) | May 07, 2024 |
| Packard Be... | WMCP78M                     | Desktop     | [4d711194fa](https://linux-hardware.org/?probe=4d711194fa) | May 07, 2024 |
| Supermicro    | X8DT6                       | Server      | [c3428daaf1](https://linux-hardware.org/?probe=c3428daaf1) | May 07, 2024 |
| GEEKOM        | A7                          | Desktop     | [87925a210f](https://linux-hardware.org/?probe=87925a210f) | May 07, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [e061b752c8](https://linux-hardware.org/?probe=e061b752c8) | May 07, 2024 |
| MSI           | X670E GAMING PLUS WIFI      | Desktop     | [72a4d27732](https://linux-hardware.org/?probe=72a4d27732) | May 07, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [b3a37af0d0](https://linux-hardware.org/?probe=b3a37af0d0) | May 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [d7c1c96567](https://linux-hardware.org/?probe=d7c1c96567) | May 07, 2024 |
| SCHNEIDER     | SCL141CTP                   | Notebook    | [ce0a785c29](https://linux-hardware.org/?probe=ce0a785c29) | May 07, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [63e6a64d1b](https://linux-hardware.org/?probe=63e6a64d1b) | May 07, 2024 |
| Lenovo        | ThinkPad T480 20L5A023HK    | Notebook    | [ff78bb7112](https://linux-hardware.org/?probe=ff78bb7112) | May 07, 2024 |
| HP            | G60                         | Notebook    | [c9e5d3832d](https://linux-hardware.org/?probe=c9e5d3832d) | May 07, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [b8dd9a912d](https://linux-hardware.org/?probe=b8dd9a912d) | May 07, 2024 |
| Apple         | Mac-F2268CC8                | All in one  | [b3b751a603](https://linux-hardware.org/?probe=b3b751a603) | May 07, 2024 |
| Dell          | Latitude 9430               | Notebook    | [953be205ca](https://linux-hardware.org/?probe=953be205ca) | May 07, 2024 |
| HP            | 815A                        | Mini pc     | [44b77bda73](https://linux-hardware.org/?probe=44b77bda73) | May 07, 2024 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [60ef8abb02](https://linux-hardware.org/?probe=60ef8abb02) | May 07, 2024 |
| Acer          | TravelMate Spin P414RN-5... | Convertible | [5d3f93b635](https://linux-hardware.org/?probe=5d3f93b635) | May 07, 2024 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [cf6fc980de](https://linux-hardware.org/?probe=cf6fc980de) | May 07, 2024 |
| HP            | EliteBook 840 G8            | Notebook    | [f60faaeec0](https://linux-hardware.org/?probe=f60faaeec0) | May 07, 2024 |
| Apple         | Mac-F2268DAE                | All in one  | [9e279775ed](https://linux-hardware.org/?probe=9e279775ed) | May 07, 2024 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [4fb0650e99](https://linux-hardware.org/?probe=4fb0650e99) | May 07, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [de2ed6e188](https://linux-hardware.org/?probe=de2ed6e188) | May 07, 2024 |
| Dell          | Precision 7720              | Notebook    | [5423da6e5c](https://linux-hardware.org/?probe=5423da6e5c) | May 07, 2024 |
| Lenovo        | ThinkServer TS140           | Desktop     | [be7444624d](https://linux-hardware.org/?probe=be7444624d) | May 07, 2024 |
| ASUSTek       | Zenbook S 13 UX5304VA_UX... | Notebook    | [1c72c07e3d](https://linux-hardware.org/?probe=1c72c07e3d) | May 07, 2024 |
| ECS           | Nettle2                     | Desktop     | [af1b3ee348](https://linux-hardware.org/?probe=af1b3ee348) | May 07, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [0ef70379ee](https://linux-hardware.org/?probe=0ef70379ee) | May 07, 2024 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [d12f9a31f3](https://linux-hardware.org/?probe=d12f9a31f3) | May 07, 2024 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [a415f46a9e](https://linux-hardware.org/?probe=a415f46a9e) | May 07, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA403UI... | Notebook    | [61b3a490a8](https://linux-hardware.org/?probe=61b3a490a8) | May 07, 2024 |
| Sony          | SVF1521E2EW                 | Notebook    | [2e86efc1ba](https://linux-hardware.org/?probe=2e86efc1ba) | May 07, 2024 |
| Lenovo        | ThinkPad T430s 2355CL4      | Notebook    | [b90ab4a6e2](https://linux-hardware.org/?probe=b90ab4a6e2) | May 07, 2024 |
| Huanan        | X58 V1.0                    | Desktop     | [f4d5141ce0](https://linux-hardware.org/?probe=f4d5141ce0) | May 07, 2024 |
| ASRock        | A300M-STX                   | Desktop     | [cdf544ca1d](https://linux-hardware.org/?probe=cdf544ca1d) | May 07, 2024 |
| Dell          | 088DT1 A00                  | Desktop     | [edb955bd5e](https://linux-hardware.org/?probe=edb955bd5e) | May 07, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f605dfd9c2](https://linux-hardware.org/?probe=f605dfd9c2) | May 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [9849982066](https://linux-hardware.org/?probe=9849982066) | May 07, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [38e8b24bd0](https://linux-hardware.org/?probe=38e8b24bd0) | May 07, 2024 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [7cd1070dc0](https://linux-hardware.org/?probe=7cd1070dc0) | May 07, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [1022758f4a](https://linux-hardware.org/?probe=1022758f4a) | May 07, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [36f94dbbd1](https://linux-hardware.org/?probe=36f94dbbd1) | May 07, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [abbe6a092c](https://linux-hardware.org/?probe=abbe6a092c) | May 07, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [dcd5e1e281](https://linux-hardware.org/?probe=dcd5e1e281) | May 07, 2024 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [8f7abd7f23](https://linux-hardware.org/?probe=8f7abd7f23) | May 07, 2024 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [263e934dc2](https://linux-hardware.org/?probe=263e934dc2) | May 07, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [72d8d32749](https://linux-hardware.org/?probe=72d8d32749) | May 07, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [a10be2227c](https://linux-hardware.org/?probe=a10be2227c) | May 07, 2024 |
| Gigabyte      | Z77-D3H                     | Desktop     | [01099601fe](https://linux-hardware.org/?probe=01099601fe) | May 07, 2024 |
| Unknown       | HOTTAB                      | Desktop     | [aadecb497e](https://linux-hardware.org/?probe=aadecb497e) | May 07, 2024 |
| System76      | Gazelle                     | Notebook    | [fbe88df732](https://linux-hardware.org/?probe=fbe88df732) | May 07, 2024 |
| Unknown       | Unknown                     | Notebook    | [09d2748c7a](https://linux-hardware.org/?probe=09d2748c7a) | May 07, 2024 |
| Dell          | 0V8DVD A01                  | All in one  | [2018075583](https://linux-hardware.org/?probe=2018075583) | May 07, 2024 |
| HP            | ProBook 645 G3              | Notebook    | [29cb5b66f8](https://linux-hardware.org/?probe=29cb5b66f8) | May 07, 2024 |
| ASUSTek       | S451LA                      | Notebook    | [f3720aa6f9](https://linux-hardware.org/?probe=f3720aa6f9) | May 07, 2024 |
| Dell          | 02YRK5 A02                  | Desktop     | [fea15ab44c](https://linux-hardware.org/?probe=fea15ab44c) | May 07, 2024 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [be061de1c7](https://linux-hardware.org/?probe=be061de1c7) | May 07, 2024 |
| Lenovo        | 375C No DPK                 | All in one  | [46bbdf2453](https://linux-hardware.org/?probe=46bbdf2453) | May 07, 2024 |
| Dell          | Precision 5520              | Notebook    | [3b0c11a9ff](https://linux-hardware.org/?probe=3b0c11a9ff) | May 07, 2024 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [f683d111b9](https://linux-hardware.org/?probe=f683d111b9) | May 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [643f150579](https://linux-hardware.org/?probe=643f150579) | May 07, 2024 |
| Dell          | Precision 5520              | Notebook    | [bf1f2486cd](https://linux-hardware.org/?probe=bf1f2486cd) | May 07, 2024 |
| Unknown       | Edgepoint Tactical (Ketz... | Soc         | [686788fe19](https://linux-hardware.org/?probe=686788fe19) | May 07, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [e5dc310897](https://linux-hardware.org/?probe=e5dc310897) | May 07, 2024 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [71d1f5cdfb](https://linux-hardware.org/?probe=71d1f5cdfb) | May 07, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [9fd55d6b07](https://linux-hardware.org/?probe=9fd55d6b07) | May 07, 2024 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [1f8035ccf5](https://linux-hardware.org/?probe=1f8035ccf5) | May 07, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [c18909580d](https://linux-hardware.org/?probe=c18909580d) | May 07, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [61aed9772b](https://linux-hardware.org/?probe=61aed9772b) | May 07, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a5b0e5456a](https://linux-hardware.org/?probe=a5b0e5456a) | May 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [773ca4f9c9](https://linux-hardware.org/?probe=773ca4f9c9) | May 06, 2024 |
| HP            | ZBook 15 G6                 | Notebook    | [4a401c8b15](https://linux-hardware.org/?probe=4a401c8b15) | May 06, 2024 |
| Shenzhen M... | F7BAA                       | Desktop     | [69aa3dca70](https://linux-hardware.org/?probe=69aa3dca70) | May 06, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [7eae46245c](https://linux-hardware.org/?probe=7eae46245c) | May 06, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [bf4a7b097c](https://linux-hardware.org/?probe=bf4a7b097c) | May 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [0104fa9a83](https://linux-hardware.org/?probe=0104fa9a83) | May 06, 2024 |
| Alienware     | m15 R7                      | Notebook    | [445b29da20](https://linux-hardware.org/?probe=445b29da20) | May 06, 2024 |
| HP            | ProLiant DL20 Gen9          | Server      | [d270509755](https://linux-hardware.org/?probe=d270509755) | May 06, 2024 |
| Sony          | VPCEB1S1E                   | Notebook    | [db144a8fd9](https://linux-hardware.org/?probe=db144a8fd9) | May 06, 2024 |
| ASUSTek       | X405UQ                      | Notebook    | [aa39bc4676](https://linux-hardware.org/?probe=aa39bc4676) | May 06, 2024 |
| Valve         | Galileo                     | Notebook    | [af20242820](https://linux-hardware.org/?probe=af20242820) | May 06, 2024 |
| Lenovo        | ThinkPad X13 Gen 3 21CM0... | Notebook    | [39fdd434dd](https://linux-hardware.org/?probe=39fdd434dd) | May 06, 2024 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [885618c382](https://linux-hardware.org/?probe=885618c382) | May 06, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [e76f332009](https://linux-hardware.org/?probe=e76f332009) | May 06, 2024 |
| Dell          | 02YYK5 A01                  | Desktop     | [09b75f38cd](https://linux-hardware.org/?probe=09b75f38cd) | May 06, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [e19fea8a49](https://linux-hardware.org/?probe=e19fea8a49) | May 06, 2024 |
| Dell          | 03KWTV A00                  | Desktop     | [68f465c06a](https://linux-hardware.org/?probe=68f465c06a) | May 06, 2024 |
| ASUSTek       | M4A78T-E                    | Desktop     | [2cee8d14ab](https://linux-hardware.org/?probe=2cee8d14ab) | May 06, 2024 |
| MSI           | MAG B660 TOMAHAWK WIFI D... | Desktop     | [5a5f459292](https://linux-hardware.org/?probe=5a5f459292) | May 06, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [bf13a8edca](https://linux-hardware.org/?probe=bf13a8edca) | May 06, 2024 |
| Dell          | 03KWTV A00                  | Desktop     | [1b3f32baf6](https://linux-hardware.org/?probe=1b3f32baf6) | May 06, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [84cc2abe63](https://linux-hardware.org/?probe=84cc2abe63) | May 06, 2024 |
| ASRock        | J3710M                      | Desktop     | [ff2b73c846](https://linux-hardware.org/?probe=ff2b73c846) | May 06, 2024 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [8848310fde](https://linux-hardware.org/?probe=8848310fde) | May 06, 2024 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [fc1633451e](https://linux-hardware.org/?probe=fc1633451e) | May 06, 2024 |
| Dell          | Latitude E6540              | Notebook    | [634735e1da](https://linux-hardware.org/?probe=634735e1da) | May 06, 2024 |
| HP            | 2000                        | Notebook    | [71d3942f81](https://linux-hardware.org/?probe=71d3942f81) | May 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e6dfd023b6](https://linux-hardware.org/?probe=e6dfd023b6) | May 06, 2024 |
| Lenovo        | XiaoXin-15IIL 2020 81YL     | Notebook    | [b95cda619a](https://linux-hardware.org/?probe=b95cda619a) | May 06, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [70346cc510](https://linux-hardware.org/?probe=70346cc510) | May 06, 2024 |
| System76      | Darter Pro                  | Notebook    | [e6da92d97e](https://linux-hardware.org/?probe=e6da92d97e) | May 06, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [4b9e2674de](https://linux-hardware.org/?probe=4b9e2674de) | May 06, 2024 |
| Gigabyte      | H81M-H                      | Desktop     | [5ea3b70747](https://linux-hardware.org/?probe=5ea3b70747) | May 06, 2024 |
| Fujitsu       | D3164-A1 S26361-D3164-A1    | Desktop     | [ae1edad2ab](https://linux-hardware.org/?probe=ae1edad2ab) | May 06, 2024 |
| Acer          | Aspire E1-572               | Notebook    | [3df494e445](https://linux-hardware.org/?probe=3df494e445) | May 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [6ece3912e8](https://linux-hardware.org/?probe=6ece3912e8) | May 06, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [146a7db97f](https://linux-hardware.org/?probe=146a7db97f) | May 06, 2024 |
| Alurin        | ALU-BAR-I511-000-140        | Notebook    | [04578b9c4b](https://linux-hardware.org/?probe=04578b9c4b) | May 06, 2024 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [0e930ac423](https://linux-hardware.org/?probe=0e930ac423) | May 06, 2024 |
| Medion        | E14223                      | Notebook    | [73ae3c5e79](https://linux-hardware.org/?probe=73ae3c5e79) | May 06, 2024 |
| Lenovo        | E31-80 80MX                 | Notebook    | [1c9fd17eff](https://linux-hardware.org/?probe=1c9fd17eff) | May 06, 2024 |
| Lenovo        | ThinkPad Helix 36986CG      | Notebook    | [9b2bd77573](https://linux-hardware.org/?probe=9b2bd77573) | May 06, 2024 |
| Dell          | Latitude E5410              | Notebook    | [0038eadd32](https://linux-hardware.org/?probe=0038eadd32) | May 06, 2024 |
| MSI           | Creator Z16 A12UET          | Notebook    | [edf6b45103](https://linux-hardware.org/?probe=edf6b45103) | May 06, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [44f44fe800](https://linux-hardware.org/?probe=44f44fe800) | May 06, 2024 |
| Unknown       | Unknown                     | Notebook    | [273d6afeb5](https://linux-hardware.org/?probe=273d6afeb5) | May 06, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [ce0082648a](https://linux-hardware.org/?probe=ce0082648a) | May 06, 2024 |
| Lenovo        | IdeaPad Z580                | Notebook    | [2fad877602](https://linux-hardware.org/?probe=2fad877602) | May 06, 2024 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [276faea129](https://linux-hardware.org/?probe=276faea129) | May 06, 2024 |
| Linx          | LINX1010B                   | Notebook    | [5abe12bf84](https://linux-hardware.org/?probe=5abe12bf84) | May 06, 2024 |
| MSI           | Creator Z16 A12UET          | Notebook    | [2aea1cacac](https://linux-hardware.org/?probe=2aea1cacac) | May 06, 2024 |
| Lenovo        | Unknown                     | Notebook    | [dae6c8e749](https://linux-hardware.org/?probe=dae6c8e749) | May 06, 2024 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | Notebook    | [92089af4b7](https://linux-hardware.org/?probe=92089af4b7) | May 06, 2024 |
| MASSCOM VI... | L133                        | Notebook    | [12b6c6b515](https://linux-hardware.org/?probe=12b6c6b515) | May 06, 2024 |
| Dell          | XPS 13 7390                 | Notebook    | [3132f4ff24](https://linux-hardware.org/?probe=3132f4ff24) | May 06, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [9f866b203a](https://linux-hardware.org/?probe=9f866b203a) | May 06, 2024 |
| Dell          | Precision 7710              | Notebook    | [c89fe612a1](https://linux-hardware.org/?probe=c89fe612a1) | May 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [5a788054ec](https://linux-hardware.org/?probe=5a788054ec) | May 06, 2024 |
| MSI           | B650M GAMING PLUS WIFI      | Desktop     | [afbc83ced8](https://linux-hardware.org/?probe=afbc83ced8) | May 06, 2024 |
| Dell          | 0YXT71 A00                  | Desktop     | [b451487b59](https://linux-hardware.org/?probe=b451487b59) | May 06, 2024 |
| Dell          | Precision 7710              | Notebook    | [52c6c4a64a](https://linux-hardware.org/?probe=52c6c4a64a) | May 06, 2024 |
| Star Labs     | StarBook                    | Notebook    | [7e37692a50](https://linux-hardware.org/?probe=7e37692a50) | May 06, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [602683adef](https://linux-hardware.org/?probe=602683adef) | May 06, 2024 |
| Dell          | 0C2KJT A00                  | Desktop     | [a884cd0cf5](https://linux-hardware.org/?probe=a884cd0cf5) | May 06, 2024 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [9a1d11cc26](https://linux-hardware.org/?probe=9a1d11cc26) | May 06, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | Notebook    | [3679c79ac4](https://linux-hardware.org/?probe=3679c79ac4) | May 06, 2024 |
| ASUSTek       | TUF Gaming Z790-PRO WIFI    | Desktop     | [07048840f0](https://linux-hardware.org/?probe=07048840f0) | May 06, 2024 |
| ASUSTek       | P9X79                       | Desktop     | [dd0d50c3bf](https://linux-hardware.org/?probe=dd0d50c3bf) | May 06, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [3236268f3d](https://linux-hardware.org/?probe=3236268f3d) | May 06, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [1d40ae8807](https://linux-hardware.org/?probe=1d40ae8807) | May 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [2487a975e8](https://linux-hardware.org/?probe=2487a975e8) | May 06, 2024 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | Notebook    | [ae77241a92](https://linux-hardware.org/?probe=ae77241a92) | May 06, 2024 |
| Dell          | Latitude 5440               | Notebook    | [f6c9287953](https://linux-hardware.org/?probe=f6c9287953) | May 06, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [326b0babab](https://linux-hardware.org/?probe=326b0babab) | May 06, 2024 |
| PC Special... | NH5x_7xDPx                  | Notebook    | [35a25ffdfd](https://linux-hardware.org/?probe=35a25ffdfd) | May 06, 2024 |
| ASUSTek       | Z240IC-H170                 | All in one  | [978c7be506](https://linux-hardware.org/?probe=978c7be506) | May 06, 2024 |
| Intel         | B75                         | Desktop     | [18e086bc3d](https://linux-hardware.org/?probe=18e086bc3d) | May 06, 2024 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [5bc2e6635d](https://linux-hardware.org/?probe=5bc2e6635d) | May 06, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [38b9f94aeb](https://linux-hardware.org/?probe=38b9f94aeb) | May 06, 2024 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [657a003a54](https://linux-hardware.org/?probe=657a003a54) | May 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [c082a264d6](https://linux-hardware.org/?probe=c082a264d6) | May 06, 2024 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | Desktop     | [867c770e38](https://linux-hardware.org/?probe=867c770e38) | May 06, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [c8f7c82599](https://linux-hardware.org/?probe=c8f7c82599) | May 06, 2024 |
| Dell          | 0478VN A00                  | Desktop     | [305f343c95](https://linux-hardware.org/?probe=305f343c95) | May 06, 2024 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [2af49854e2](https://linux-hardware.org/?probe=2af49854e2) | May 06, 2024 |
| Dell          | Latitude 3420               | Notebook    | [f0412b645c](https://linux-hardware.org/?probe=f0412b645c) | May 06, 2024 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | Desktop     | [a923d8607b](https://linux-hardware.org/?probe=a923d8607b) | May 06, 2024 |
| Dell          | System XPS L702X            | Notebook    | [fec4b7f7ff](https://linux-hardware.org/?probe=fec4b7f7ff) | May 06, 2024 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [b87692bb4f](https://linux-hardware.org/?probe=b87692bb4f) | May 06, 2024 |
| Acer          | Nitro AN515-43              | Notebook    | [c65a5efcdb](https://linux-hardware.org/?probe=c65a5efcdb) | May 06, 2024 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [1181eb41ee](https://linux-hardware.org/?probe=1181eb41ee) | May 06, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [162040356c](https://linux-hardware.org/?probe=162040356c) | May 06, 2024 |
| Intel         | S1200BTL E98681-352         | Server      | [4927e2996f](https://linux-hardware.org/?probe=4927e2996f) | May 06, 2024 |
| Dell          | Vostro 3520                 | Notebook    | [0b420358ac](https://linux-hardware.org/?probe=0b420358ac) | May 06, 2024 |
| eMachines     | WMCP61M                     | Desktop     | [54b1a18c59](https://linux-hardware.org/?probe=54b1a18c59) | May 06, 2024 |
| Acer          | Predator PO3-630            | Desktop     | [7271f27dc0](https://linux-hardware.org/?probe=7271f27dc0) | May 06, 2024 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [1168634a54](https://linux-hardware.org/?probe=1168634a54) | May 06, 2024 |
| Acer          | Aspire 5310                 | Notebook    | [8e28475b52](https://linux-hardware.org/?probe=8e28475b52) | May 06, 2024 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [42a7c6fb23](https://linux-hardware.org/?probe=42a7c6fb23) | May 06, 2024 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [e475e36ab0](https://linux-hardware.org/?probe=e475e36ab0) | May 06, 2024 |
| Dell          | 0HH807                      | Desktop     | [743dea0fc3](https://linux-hardware.org/?probe=743dea0fc3) | May 06, 2024 |
| Dell          | Precision M4700             | Notebook    | [db0b8eb10b](https://linux-hardware.org/?probe=db0b8eb10b) | May 06, 2024 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [92d80bd754](https://linux-hardware.org/?probe=92d80bd754) | May 06, 2024 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [8f78e61ba3](https://linux-hardware.org/?probe=8f78e61ba3) | May 06, 2024 |
| ASUSTek       | TUF B350M-PLUS GAMING       | Desktop     | [e31ea5ab17](https://linux-hardware.org/?probe=e31ea5ab17) | May 06, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d73bdd4b76](https://linux-hardware.org/?probe=d73bdd4b76) | May 06, 2024 |
| Dell          | Vostro 15 3510              | Notebook    | [cd07d15de0](https://linux-hardware.org/?probe=cd07d15de0) | May 06, 2024 |
| Dell          | Inspiron 7737               | Notebook    | [73f61be8b5](https://linux-hardware.org/?probe=73f61be8b5) | May 06, 2024 |
| HP            | 843B                        | Desktop     | [ed0c184996](https://linux-hardware.org/?probe=ed0c184996) | May 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d4cca237f2](https://linux-hardware.org/?probe=d4cca237f2) | May 06, 2024 |
| Lenovo        | IdeaPad Pro 5 14AHP9 83D... | Notebook    | [f8f3623eac](https://linux-hardware.org/?probe=f8f3623eac) | May 06, 2024 |
| Gigabyte      | 8PEMT4                      | Desktop     | [d43ba07bdd](https://linux-hardware.org/?probe=d43ba07bdd) | May 06, 2024 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0bcef3f207](https://linux-hardware.org/?probe=0bcef3f207) | May 06, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [cece4d3b5e](https://linux-hardware.org/?probe=cece4d3b5e) | May 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e5685451f5](https://linux-hardware.org/?probe=e5685451f5) | May 06, 2024 |
| Acer          | Swift SF314-512             | Notebook    | [c1b3018ff5](https://linux-hardware.org/?probe=c1b3018ff5) | May 06, 2024 |
| Packard Be... | EasyNote LM81               | Notebook    | [0ea4d18648](https://linux-hardware.org/?probe=0ea4d18648) | May 06, 2024 |
| ASUSTek       | Z9PR-D12 Series             | Server      | [f922090bb9](https://linux-hardware.org/?probe=f922090bb9) | May 06, 2024 |
| Gigabyte      | H97M-HD3                    | Desktop     | [7548e25e9d](https://linux-hardware.org/?probe=7548e25e9d) | May 06, 2024 |
| Pegatron      | 2AC3                        | Desktop     | [3bc44b080d](https://linux-hardware.org/?probe=3bc44b080d) | May 06, 2024 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [c120bbd998](https://linux-hardware.org/?probe=c120bbd998) | May 06, 2024 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [fba3144c06](https://linux-hardware.org/?probe=fba3144c06) | May 06, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [390ca96513](https://linux-hardware.org/?probe=390ca96513) | May 06, 2024 |
| HP            | 843B                        | Desktop     | [bf812339be](https://linux-hardware.org/?probe=bf812339be) | May 06, 2024 |
| ASRock        | H310CM-HDV                  | Desktop     | [1312cfac28](https://linux-hardware.org/?probe=1312cfac28) | May 06, 2024 |
| Samsung       | 960QFG                      | Convertible | [938356247b](https://linux-hardware.org/?probe=938356247b) | May 06, 2024 |
| Sony          | VPCEB1S1E                   | Notebook    | [aa8d766ae4](https://linux-hardware.org/?probe=aa8d766ae4) | May 06, 2024 |
| HP            | 8053                        | Desktop     | [06b48e5ec6](https://linux-hardware.org/?probe=06b48e5ec6) | May 06, 2024 |
| HP            | Pavilion 15                 | Notebook    | [77f8425176](https://linux-hardware.org/?probe=77f8425176) | May 06, 2024 |
| Dell          | Inspiron 15 3520            | Notebook    | [c9bddc6d00](https://linux-hardware.org/?probe=c9bddc6d00) | May 06, 2024 |
| Dell          | 00CV7F A00                  | Desktop     | [83dce373d6](https://linux-hardware.org/?probe=83dce373d6) | May 06, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [98e922adae](https://linux-hardware.org/?probe=98e922adae) | May 06, 2024 |
| ASUSTek       | GL553VW                     | Notebook    | [c51bf874e5](https://linux-hardware.org/?probe=c51bf874e5) | May 06, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [9007198402](https://linux-hardware.org/?probe=9007198402) | May 06, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [c3072851e8](https://linux-hardware.org/?probe=c3072851e8) | May 06, 2024 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | Notebook    | [9adbb0ba2c](https://linux-hardware.org/?probe=9adbb0ba2c) | May 06, 2024 |
| MSI           | GT60 2OC/2OD                | Notebook    | [d71303b21c](https://linux-hardware.org/?probe=d71303b21c) | May 06, 2024 |
| HP            | EliteBook 820 G2            | Notebook    | [254af47954](https://linux-hardware.org/?probe=254af47954) | May 06, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [bc2508bd91](https://linux-hardware.org/?probe=bc2508bd91) | May 06, 2024 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | Notebook    | [465a5be052](https://linux-hardware.org/?probe=465a5be052) | May 06, 2024 |
| MSI           | GT60 2OC/2OD                | Notebook    | [3330ada128](https://linux-hardware.org/?probe=3330ada128) | May 06, 2024 |
| MSI           | CX61 0NC/CX61 0ND/CX61 0... | Notebook    | [3d1643b2c5](https://linux-hardware.org/?probe=3d1643b2c5) | May 06, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [c741f249e2](https://linux-hardware.org/?probe=c741f249e2) | May 06, 2024 |
| GEDU          | YourLand                    | Soc         | [5bfcf863da](https://linux-hardware.org/?probe=5bfcf863da) | May 06, 2024 |
| Unknown       | Unknown                     | Notebook    | [a857b08dd7](https://linux-hardware.org/?probe=a857b08dd7) | May 06, 2024 |
| MSI           | H110M PRO-VH                | Desktop     | [f0e62a158e](https://linux-hardware.org/?probe=f0e62a158e) | May 06, 2024 |
| Huanan        | X99-QD4 V0.1 693H           | Desktop     | [c23f1deec5](https://linux-hardware.org/?probe=c23f1deec5) | May 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [b6bf02e276](https://linux-hardware.org/?probe=b6bf02e276) | May 06, 2024 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [11bef15f7d](https://linux-hardware.org/?probe=11bef15f7d) | May 06, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [b29aba86be](https://linux-hardware.org/?probe=b29aba86be) | May 06, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [c414f0202a](https://linux-hardware.org/?probe=c414f0202a) | May 06, 2024 |
| MSI           | PRO H610M-E DDR4            | Desktop     | [e4adc14010](https://linux-hardware.org/?probe=e4adc14010) | May 06, 2024 |
| ASRock        | X79 Extreme9                | Desktop     | [a65acf43f1](https://linux-hardware.org/?probe=a65acf43f1) | May 06, 2024 |
| Dell          | Inspiron N7010              | Notebook    | [538f6e2c91](https://linux-hardware.org/?probe=538f6e2c91) | May 06, 2024 |
| Dell          | 0F642F A00                  | Desktop     | [fc2a825e57](https://linux-hardware.org/?probe=fc2a825e57) | May 06, 2024 |
| MSI           | 2AE0                        | Desktop     | [25c9b3836b](https://linux-hardware.org/?probe=25c9b3836b) | May 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [9f8df7b114](https://linux-hardware.org/?probe=9f8df7b114) | May 06, 2024 |
| HP            | ProLiant DL360 Gen9         | Server      | [0544131147](https://linux-hardware.org/?probe=0544131147) | May 06, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [cb063ef0b2](https://linux-hardware.org/?probe=cb063ef0b2) | May 06, 2024 |
| Toshiba       | Satellite C50-B             | Notebook    | [4037de5266](https://linux-hardware.org/?probe=4037de5266) | May 06, 2024 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [76f01093f1](https://linux-hardware.org/?probe=76f01093f1) | May 06, 2024 |
| GEEKOM        | Mini IT12                   | Desktop     | [bf478cb069](https://linux-hardware.org/?probe=bf478cb069) | May 06, 2024 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [bb7e4b6de6](https://linux-hardware.org/?probe=bb7e4b6de6) | May 06, 2024 |
| ASUSTek       | Zenbook UN5401QA_UN5401Q... | Convertible | [6c0c235ec2](https://linux-hardware.org/?probe=6c0c235ec2) | May 06, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [52037a51a0](https://linux-hardware.org/?probe=52037a51a0) | May 06, 2024 |
| HP            | ZBook Studio G3             | Notebook    | [be52b86bc0](https://linux-hardware.org/?probe=be52b86bc0) | May 06, 2024 |
| ASUSTek       | S550CB                      | Notebook    | [943c34e625](https://linux-hardware.org/?probe=943c34e625) | May 06, 2024 |
| Toshiba       | Satellite C660D             | Notebook    | [8c4353e699](https://linux-hardware.org/?probe=8c4353e699) | May 06, 2024 |
| Alienware     | x17 R2                      | Notebook    | [ed5c24948b](https://linux-hardware.org/?probe=ed5c24948b) | May 06, 2024 |
| Fujitsu       | LIFEBOOK E754               | Notebook    | [c201d1f500](https://linux-hardware.org/?probe=c201d1f500) | May 06, 2024 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [ec90e9cff9](https://linux-hardware.org/?probe=ec90e9cff9) | May 06, 2024 |
| Supermicro    | X10DRL-i                    | Desktop     | [80cdad1821](https://linux-hardware.org/?probe=80cdad1821) | May 06, 2024 |
| Acer          | Aspire A715-41G             | Notebook    | [b24efb4449](https://linux-hardware.org/?probe=b24efb4449) | May 06, 2024 |
| Unknown       | Orange Pi 5                 | Soc         | [b81f4223f3](https://linux-hardware.org/?probe=b81f4223f3) | May 06, 2024 |
| Gigabyte      | H81M-S2H                    | Desktop     | [0b1a61e802](https://linux-hardware.org/?probe=0b1a61e802) | May 06, 2024 |
| Samsung       | 550XDA                      | Notebook    | [1ea7dfb8ae](https://linux-hardware.org/?probe=1ea7dfb8ae) | May 06, 2024 |
| ASUSTek       | P2540UA                     | Notebook    | [ea9ddf3f6e](https://linux-hardware.org/?probe=ea9ddf3f6e) | May 06, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ab33f7c9fc](https://linux-hardware.org/?probe=ab33f7c9fc) | May 06, 2024 |
| Apple         | MacBookPro15,2              | Notebook    | [4720f69696](https://linux-hardware.org/?probe=4720f69696) | May 06, 2024 |
| MSI           | K9N6PGM2-V2                 | Desktop     | [a79d33d7cf](https://linux-hardware.org/?probe=a79d33d7cf) | May 06, 2024 |
| ADVAN         | 1701                        | Notebook    | [e0928a1604](https://linux-hardware.org/?probe=e0928a1604) | May 06, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [0f43840d58](https://linux-hardware.org/?probe=0f43840d58) | May 06, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [869ffa1875](https://linux-hardware.org/?probe=869ffa1875) | May 06, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [66c6c3e199](https://linux-hardware.org/?probe=66c6c3e199) | May 06, 2024 |
| Itautec       | Itautec                     | Notebook    | [cb012e89fc](https://linux-hardware.org/?probe=cb012e89fc) | May 06, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [5038e329fc](https://linux-hardware.org/?probe=5038e329fc) | May 06, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [24ef78e496](https://linux-hardware.org/?probe=24ef78e496) | May 06, 2024 |
| Itautec       | Itautec                     | Notebook    | [e1d6b279b9](https://linux-hardware.org/?probe=e1d6b279b9) | May 06, 2024 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [12afc4ec37](https://linux-hardware.org/?probe=12afc4ec37) | May 06, 2024 |
| Unknown       | X570 Phantom Gaming-ITX/... | Notebook    | [a02a58b376](https://linux-hardware.org/?probe=a02a58b376) | May 06, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [4ffd873f67](https://linux-hardware.org/?probe=4ffd873f67) | May 06, 2024 |
| Alienware     | x17 R2                      | Notebook    | [a920973ad3](https://linux-hardware.org/?probe=a920973ad3) | May 06, 2024 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [8d12951a69](https://linux-hardware.org/?probe=8d12951a69) | May 06, 2024 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [8c2af338dc](https://linux-hardware.org/?probe=8c2af338dc) | May 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [9a90343d3e](https://linux-hardware.org/?probe=9a90343d3e) | May 06, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [16dcd59b91](https://linux-hardware.org/?probe=16dcd59b91) | May 06, 2024 |
| ASUSTek       | H97-PLUS                    | Desktop     | [4f4fcced1c](https://linux-hardware.org/?probe=4f4fcced1c) | May 06, 2024 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [91fcd08046](https://linux-hardware.org/?probe=91fcd08046) | May 06, 2024 |
| HP            | 8767 A                      | Desktop     | [c5fd3ea1e4](https://linux-hardware.org/?probe=c5fd3ea1e4) | May 06, 2024 |
| Dell          | Latitude 5400               | Notebook    | [cf78549103](https://linux-hardware.org/?probe=cf78549103) | May 06, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [ef61efd227](https://linux-hardware.org/?probe=ef61efd227) | May 06, 2024 |
| ASUSTek       | CM1831                      | Desktop     | [c228565f48](https://linux-hardware.org/?probe=c228565f48) | May 06, 2024 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [6bb4152903](https://linux-hardware.org/?probe=6bb4152903) | May 06, 2024 |
| HP            | 829A                        | Mini pc     | [c9a6161e36](https://linux-hardware.org/?probe=c9a6161e36) | May 06, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [0b1ac68bc9](https://linux-hardware.org/?probe=0b1ac68bc9) | May 06, 2024 |
| ASUSTek       | CM1831                      | Desktop     | [cc97798ac4](https://linux-hardware.org/?probe=cc97798ac4) | May 06, 2024 |
| Lenovo        | 32E1 SDK0T76463 WIN 3422... | Desktop     | [981ac7ef2b](https://linux-hardware.org/?probe=981ac7ef2b) | May 06, 2024 |
| HP            | 8299                        | Desktop     | [6024274be6](https://linux-hardware.org/?probe=6024274be6) | May 06, 2024 |
| Dell          | Vostro 5471                 | Notebook    | [dae50714b1](https://linux-hardware.org/?probe=dae50714b1) | May 06, 2024 |
| Dell          | Vostro 5471                 | Notebook    | [92897b02b9](https://linux-hardware.org/?probe=92897b02b9) | May 06, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [083cfcc0f3](https://linux-hardware.org/?probe=083cfcc0f3) | May 06, 2024 |
| Alienware     | 17 R4                       | Notebook    | [99e296d142](https://linux-hardware.org/?probe=99e296d142) | May 06, 2024 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [add0ddcfc0](https://linux-hardware.org/?probe=add0ddcfc0) | May 06, 2024 |
| Valve         | Jupiter                     | Notebook    | [829ef0c2ba](https://linux-hardware.org/?probe=829ef0c2ba) | May 06, 2024 |
| Medion        | MS-7366                     | Desktop     | [0c36270a48](https://linux-hardware.org/?probe=0c36270a48) | May 06, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [cb4f1dbbfa](https://linux-hardware.org/?probe=cb4f1dbbfa) | May 06, 2024 |
| Acer          | Aspire ES1-571              | Notebook    | [91a89a447a](https://linux-hardware.org/?probe=91a89a447a) | May 06, 2024 |
| Monster       | ABRA A7 V13.2               | Notebook    | [fef4f4d7d4](https://linux-hardware.org/?probe=fef4f4d7d4) | May 06, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [f22091b0c8](https://linux-hardware.org/?probe=f22091b0c8) | May 06, 2024 |
| Apple         | MacBookPro11,4              | Notebook    | [3c0f7c8c00](https://linux-hardware.org/?probe=3c0f7c8c00) | May 06, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [657538061d](https://linux-hardware.org/?probe=657538061d) | May 06, 2024 |
| Lenovo        | Unknown                     | Notebook    | [5087593233](https://linux-hardware.org/?probe=5087593233) | May 06, 2024 |
| Lenovo        | ThinkPad X200s 74695GU      | Notebook    | [9ea7304023](https://linux-hardware.org/?probe=9ea7304023) | May 06, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [ead92a9fe5](https://linux-hardware.org/?probe=ead92a9fe5) | May 06, 2024 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [4a361a3420](https://linux-hardware.org/?probe=4a361a3420) | May 06, 2024 |
| ASUSTek       | ROG Strix G731GV_G731GV     | Notebook    | [00ceb2ea16](https://linux-hardware.org/?probe=00ceb2ea16) | May 06, 2024 |
| Xiaomi        | Pad 5                       | Notebook    | [2ee74fac7d](https://linux-hardware.org/?probe=2ee74fac7d) | May 05, 2024 |
| Dell          | 004FN1 A01                  | Desktop     | [d0cd268922](https://linux-hardware.org/?probe=d0cd268922) | May 05, 2024 |
| Samsung       | 370E4K                      | Notebook    | [f0c626e7ca](https://linux-hardware.org/?probe=f0c626e7ca) | May 05, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [633754915c](https://linux-hardware.org/?probe=633754915c) | May 05, 2024 |
| Dell          | 0F3KHR A01                  | Desktop     | [583ca0d285](https://linux-hardware.org/?probe=583ca0d285) | May 05, 2024 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [74454fbcde](https://linux-hardware.org/?probe=74454fbcde) | May 05, 2024 |
| HP            | 650                         | Notebook    | [8fa3b11e2c](https://linux-hardware.org/?probe=8fa3b11e2c) | May 05, 2024 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [02dec94612](https://linux-hardware.org/?probe=02dec94612) | May 05, 2024 |
| Unknown       | Unknown                     | Soc         | [938f2c805c](https://linux-hardware.org/?probe=938f2c805c) | May 05, 2024 |
| Lenovo        | Yoga Slim 7-14ARE05 82A2    | Notebook    | [c931a1a446](https://linux-hardware.org/?probe=c931a1a446) | May 05, 2024 |
| Dell          | 0V8WGR A00                  | Desktop     | [826e11d8af](https://linux-hardware.org/?probe=826e11d8af) | May 05, 2024 |
| Apple         | MacBookPro15,2              | Notebook    | [568bb3b863](https://linux-hardware.org/?probe=568bb3b863) | May 05, 2024 |
| Intel         | DG45ID AAE27729-312         | Desktop     | [9610cedb7b](https://linux-hardware.org/?probe=9610cedb7b) | May 05, 2024 |
| MSI           | MEG Z690 UNIFY              | Desktop     | [614bab5cb0](https://linux-hardware.org/?probe=614bab5cb0) | May 05, 2024 |
| Positivo      | J14GL11                     | Notebook    | [71f761fa87](https://linux-hardware.org/?probe=71f761fa87) | May 05, 2024 |
| Foxconn       | PANGU-B 1A32N3500-600-G     | Desktop     | [e2c56e50f1](https://linux-hardware.org/?probe=e2c56e50f1) | May 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [278add8d07](https://linux-hardware.org/?probe=278add8d07) | May 05, 2024 |
| eMachines     | E725                        | Notebook    | [171963d4bd](https://linux-hardware.org/?probe=171963d4bd) | May 05, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [63486fcdd6](https://linux-hardware.org/?probe=63486fcdd6) | May 05, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [29af407035](https://linux-hardware.org/?probe=29af407035) | May 05, 2024 |
| MSI           | Alpha 17 B5EEK              | Notebook    | [38d719b3cc](https://linux-hardware.org/?probe=38d719b3cc) | May 05, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [2cace801f8](https://linux-hardware.org/?probe=2cace801f8) | May 05, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [db900f1cd1](https://linux-hardware.org/?probe=db900f1cd1) | May 05, 2024 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [61af632661](https://linux-hardware.org/?probe=61af632661) | May 05, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1d637d8802](https://linux-hardware.org/?probe=1d637d8802) | May 05, 2024 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [c5f9a761a9](https://linux-hardware.org/?probe=c5f9a761a9) | May 05, 2024 |
| SZMZ          | X99 DUAL Z8                 | Desktop     | [24f362dbe8](https://linux-hardware.org/?probe=24f362dbe8) | May 05, 2024 |
| ASUSTek       | X450CC                      | Notebook    | [1085d5cad5](https://linux-hardware.org/?probe=1085d5cad5) | May 05, 2024 |
| Toshiba       | Satellite A200              | Notebook    | [ba705e9e1b](https://linux-hardware.org/?probe=ba705e9e1b) | May 05, 2024 |
| Gigabyte      | H610M K DDR4                | Desktop     | [da4e59e69d](https://linux-hardware.org/?probe=da4e59e69d) | May 05, 2024 |
| Dell          | 03W3VW A02                  | Desktop     | [ee02b7cd0b](https://linux-hardware.org/?probe=ee02b7cd0b) | May 05, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [e5f565474a](https://linux-hardware.org/?probe=e5f565474a) | May 05, 2024 |
| Dell          | Vostro 3405                 | Notebook    | [85b53deb59](https://linux-hardware.org/?probe=85b53deb59) | May 05, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [8dcee212bd](https://linux-hardware.org/?probe=8dcee212bd) | May 05, 2024 |
| Dell          | Vostro 3405                 | Notebook    | [ae06ac7700](https://linux-hardware.org/?probe=ae06ac7700) | May 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [708780fb6c](https://linux-hardware.org/?probe=708780fb6c) | May 05, 2024 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [81e4b0e4f8](https://linux-hardware.org/?probe=81e4b0e4f8) | May 05, 2024 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [3f095aabb5](https://linux-hardware.org/?probe=3f095aabb5) | May 05, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [802925480b](https://linux-hardware.org/?probe=802925480b) | May 05, 2024 |
| Lenovo        | ThinkPad T420s 41732AU      | Notebook    | [be5eeed803](https://linux-hardware.org/?probe=be5eeed803) | May 05, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [83e37ce2be](https://linux-hardware.org/?probe=83e37ce2be) | May 05, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9da2a84508](https://linux-hardware.org/?probe=9da2a84508) | May 05, 2024 |
| MSI           | PRO B650-VC WIFI            | Desktop     | [5ba462d421](https://linux-hardware.org/?probe=5ba462d421) | May 05, 2024 |
| HP            | 1495                        | Desktop     | [f0e80863a7](https://linux-hardware.org/?probe=f0e80863a7) | May 05, 2024 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [0c960e6942](https://linux-hardware.org/?probe=0c960e6942) | May 05, 2024 |
| MACHINIST     | X99 PR9                     | Desktop     | [0503106449](https://linux-hardware.org/?probe=0503106449) | May 05, 2024 |
| Pegatron      | IPXSB-H61                   | Desktop     | [2a449d83d3](https://linux-hardware.org/?probe=2a449d83d3) | May 05, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [c1e1a31335](https://linux-hardware.org/?probe=c1e1a31335) | May 05, 2024 |
| Gigabyte      | B560M DS3H                  | Desktop     | [3d88207b4d](https://linux-hardware.org/?probe=3d88207b4d) | May 05, 2024 |
| Acer          | Aspire ES1-521              | Notebook    | [65ad890734](https://linux-hardware.org/?probe=65ad890734) | May 05, 2024 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [8c70aa2f23](https://linux-hardware.org/?probe=8c70aa2f23) | May 05, 2024 |
| ASUSTek       | F9E                         | Notebook    | [faf50e0119](https://linux-hardware.org/?probe=faf50e0119) | May 05, 2024 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [0ddd0cd5f9](https://linux-hardware.org/?probe=0ddd0cd5f9) | May 05, 2024 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [2ba8347b04](https://linux-hardware.org/?probe=2ba8347b04) | May 05, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [a17314c287](https://linux-hardware.org/?probe=a17314c287) | May 05, 2024 |
| Dell          | Inspiron 5502               | Notebook    | [43fee6a80f](https://linux-hardware.org/?probe=43fee6a80f) | May 05, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [dd1cdce5af](https://linux-hardware.org/?probe=dd1cdce5af) | May 05, 2024 |
| Dell          | Precision 3561              | Notebook    | [1e92742d1f](https://linux-hardware.org/?probe=1e92742d1f) | May 05, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [47b8006c42](https://linux-hardware.org/?probe=47b8006c42) | May 05, 2024 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [c886338e7a](https://linux-hardware.org/?probe=c886338e7a) | May 05, 2024 |
| Novatech      | NE14I310                    | Notebook    | [edf97226ed](https://linux-hardware.org/?probe=edf97226ed) | May 05, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [3fafaee792](https://linux-hardware.org/?probe=3fafaee792) | May 05, 2024 |
| HP            | 250 G4                      | Notebook    | [6c2d10b0b4](https://linux-hardware.org/?probe=6c2d10b0b4) | May 05, 2024 |
| Timi          | TM1701                      | Notebook    | [305b97ebea](https://linux-hardware.org/?probe=305b97ebea) | May 05, 2024 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [9b9d434149](https://linux-hardware.org/?probe=9b9d434149) | May 05, 2024 |
| Lenovo        | ThinkPad X230 2325BK0       | Notebook    | [0c39b2e745](https://linux-hardware.org/?probe=0c39b2e745) | May 05, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [551c4cd540](https://linux-hardware.org/?probe=551c4cd540) | May 05, 2024 |
| Dell          | Inspiron 11-3162            | Notebook    | [ccf99ca586](https://linux-hardware.org/?probe=ccf99ca586) | May 05, 2024 |
| HP            | ProBook 455 G7              | Notebook    | [470e53d860](https://linux-hardware.org/?probe=470e53d860) | May 05, 2024 |
| Amlogic       | Meson GXL (S905X) P212 D... | Soc         | [1df5ef59da](https://linux-hardware.org/?probe=1df5ef59da) | May 05, 2024 |
| Samsung       | 730QED                      | Convertible | [392bee96b2](https://linux-hardware.org/?probe=392bee96b2) | May 05, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [5af3396f04](https://linux-hardware.org/?probe=5af3396f04) | May 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [8876712f97](https://linux-hardware.org/?probe=8876712f97) | May 05, 2024 |
| ASUSTek       | TUF H310M-PLUS GAMING R2... | Desktop     | [2a47a6393b](https://linux-hardware.org/?probe=2a47a6393b) | May 05, 2024 |
| Lenovo        | ThinkBook 16 G6 ABP 21KK    | Notebook    | [5a7ed888e1](https://linux-hardware.org/?probe=5a7ed888e1) | May 05, 2024 |
| ASUSTek       | F5SL                        | Notebook    | [da423af0cb](https://linux-hardware.org/?probe=da423af0cb) | May 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [7cbaf2743a](https://linux-hardware.org/?probe=7cbaf2743a) | May 05, 2024 |
| Intel         | powered classmate PC        | Tablet      | [42a4f299a3](https://linux-hardware.org/?probe=42a4f299a3) | May 05, 2024 |
| Lenovo        | ThinkPad T470 20HES6VG00    | Notebook    | [f87983a9a9](https://linux-hardware.org/?probe=f87983a9a9) | May 05, 2024 |
| Intel Clie... | LAPAC71H                    | Notebook    | [e599c3f230](https://linux-hardware.org/?probe=e599c3f230) | May 05, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f0e6546433](https://linux-hardware.org/?probe=f0e6546433) | May 05, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [780a67ef79](https://linux-hardware.org/?probe=780a67ef79) | May 05, 2024 |
| ASUSTek       | GL753VD                     | Notebook    | [05c21dbea4](https://linux-hardware.org/?probe=05c21dbea4) | May 05, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [672e653276](https://linux-hardware.org/?probe=672e653276) | May 05, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS WI... | Desktop     | [e4b1fdc5b2](https://linux-hardware.org/?probe=e4b1fdc5b2) | May 05, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [c785a73424](https://linux-hardware.org/?probe=c785a73424) | May 05, 2024 |
| HP            | ZBook 15 G3                 | Notebook    | [486b46ac77](https://linux-hardware.org/?probe=486b46ac77) | May 05, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [14b56b3e78](https://linux-hardware.org/?probe=14b56b3e78) | May 05, 2024 |
| Dell          | 03RT16 A00                  | Desktop     | [e88cedcfb7](https://linux-hardware.org/?probe=e88cedcfb7) | May 05, 2024 |
| Lenovo        | ThinkPad T440p 20AWS0HN0... | Notebook    | [dcdedc549d](https://linux-hardware.org/?probe=dcdedc549d) | May 05, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [63591686d7](https://linux-hardware.org/?probe=63591686d7) | May 05, 2024 |
| Lenovo        | ThinkPad T470s 20HFS1SW0... | Notebook    | [e27c636616](https://linux-hardware.org/?probe=e27c636616) | May 05, 2024 |
| ASUSTek       | CM6870                      | Desktop     | [6d828aab44](https://linux-hardware.org/?probe=6d828aab44) | May 05, 2024 |
| Acer          | Lars                        | Notebook    | [6ec82dab78](https://linux-hardware.org/?probe=6ec82dab78) | May 05, 2024 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [55d15ed397](https://linux-hardware.org/?probe=55d15ed397) | May 05, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [6ee8d65521](https://linux-hardware.org/?probe=6ee8d65521) | May 05, 2024 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [5a6ae63a80](https://linux-hardware.org/?probe=5a6ae63a80) | May 05, 2024 |
| Supermicro    | X7DCL                       | Desktop     | [9644da40a4](https://linux-hardware.org/?probe=9644da40a4) | May 05, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b86bb80db9](https://linux-hardware.org/?probe=b86bb80db9) | May 05, 2024 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [ec489a912b](https://linux-hardware.org/?probe=ec489a912b) | May 05, 2024 |
| Fujitsu       | CELSIUS H730                | Notebook    | [78e1a3550b](https://linux-hardware.org/?probe=78e1a3550b) | May 05, 2024 |
| HP            | 650                         | Notebook    | [6e66ce7389](https://linux-hardware.org/?probe=6e66ce7389) | May 05, 2024 |
| Dell          | Inspiron 16 Plus 7620       | Notebook    | [cd8ef2428b](https://linux-hardware.org/?probe=cd8ef2428b) | May 05, 2024 |
| MSI           | H110M ECO                   | Desktop     | [2c97e6ca20](https://linux-hardware.org/?probe=2c97e6ca20) | May 05, 2024 |
| ASUSTek       | GL753VD                     | Notebook    | [735ff065db](https://linux-hardware.org/?probe=735ff065db) | May 05, 2024 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [826e5c0fc6](https://linux-hardware.org/?probe=826e5c0fc6) | May 05, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [4c7d6f1e6a](https://linux-hardware.org/?probe=4c7d6f1e6a) | May 05, 2024 |
| Dell          | Inspiron 15 3530            | Notebook    | [a71239f845](https://linux-hardware.org/?probe=a71239f845) | May 05, 2024 |
| Fujitsu       | LIFEBOOK T900               | Notebook    | [d396d19b06](https://linux-hardware.org/?probe=d396d19b06) | May 05, 2024 |
| Lenovo        | ThinkPad T470s 20HFS1SW0... | Notebook    | [bd41e79881](https://linux-hardware.org/?probe=bd41e79881) | May 05, 2024 |
| Biostar       | H61MHV3                     | Desktop     | [c57747b094](https://linux-hardware.org/?probe=c57747b094) | May 05, 2024 |
| HP            | ProBook 640 G1              | Notebook    | [012a8fbd0c](https://linux-hardware.org/?probe=012a8fbd0c) | May 05, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [06d6c1d0e2](https://linux-hardware.org/?probe=06d6c1d0e2) | May 05, 2024 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c9843fc5d2](https://linux-hardware.org/?probe=c9843fc5d2) | May 05, 2024 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [528dc99ca7](https://linux-hardware.org/?probe=528dc99ca7) | May 05, 2024 |
| HUAWEI        | MACHR-WX9                   | Notebook    | [9577917e03](https://linux-hardware.org/?probe=9577917e03) | May 05, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b9519853cd](https://linux-hardware.org/?probe=b9519853cd) | May 05, 2024 |
| Valve         | Jupiter                     | Notebook    | [728da6c7b1](https://linux-hardware.org/?probe=728da6c7b1) | May 05, 2024 |
| ASRock        | 970 Extreme3                | Desktop     | [78a7df5736](https://linux-hardware.org/?probe=78a7df5736) | May 05, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [dc7364667b](https://linux-hardware.org/?probe=dc7364667b) | May 05, 2024 |
| ASUSTek       | X510UAR                     | Notebook    | [3317acbe53](https://linux-hardware.org/?probe=3317acbe53) | May 05, 2024 |
| MSI           | PRO X670-P WIFI             | Desktop     | [a411b722e3](https://linux-hardware.org/?probe=a411b722e3) | May 05, 2024 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7988d977fe](https://linux-hardware.org/?probe=7988d977fe) | May 05, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [94542ba081](https://linux-hardware.org/?probe=94542ba081) | May 05, 2024 |
| Apple         | MacBookPro6,2               | Notebook    | [01201fa443](https://linux-hardware.org/?probe=01201fa443) | May 05, 2024 |
| Lenovo        | ThinkPad T440p 20AWS0HN0... | Notebook    | [68020b1c69](https://linux-hardware.org/?probe=68020b1c69) | May 05, 2024 |
| MSI           | X570-A PRO                  | Desktop     | [2fdf2caa36](https://linux-hardware.org/?probe=2fdf2caa36) | May 05, 2024 |
| Dell          | 0J9VVP A00                  | Desktop     | [5971526cf6](https://linux-hardware.org/?probe=5971526cf6) | May 05, 2024 |
| HP            | 1850                        | Desktop     | [5bab4e9f9b](https://linux-hardware.org/?probe=5bab4e9f9b) | May 05, 2024 |
| HP            | 83E1                        | Desktop     | [71a7fa85fb](https://linux-hardware.org/?probe=71a7fa85fb) | May 05, 2024 |
| Dell          | 0YXT71 A02                  | Desktop     | [4da89e5d1d](https://linux-hardware.org/?probe=4da89e5d1d) | May 05, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [7ad59bc402](https://linux-hardware.org/?probe=7ad59bc402) | May 05, 2024 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | Notebook    | [ca15c39fa7](https://linux-hardware.org/?probe=ca15c39fa7) | May 05, 2024 |
| Unknown       | Unknown                     | Desktop     | [d676549abd](https://linux-hardware.org/?probe=d676549abd) | May 05, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [b1caabc9b5](https://linux-hardware.org/?probe=b1caabc9b5) | May 05, 2024 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [0ded21fa2e](https://linux-hardware.org/?probe=0ded21fa2e) | May 05, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [9c6cf56bbb](https://linux-hardware.org/?probe=9c6cf56bbb) | May 05, 2024 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [1820a973e3](https://linux-hardware.org/?probe=1820a973e3) | May 05, 2024 |
| ASUSTek       | N61Vn                       | Notebook    | [5aaf9f4609](https://linux-hardware.org/?probe=5aaf9f4609) | May 05, 2024 |
| Dell          | Latitude 3420               | Notebook    | [a28c6852fe](https://linux-hardware.org/?probe=a28c6852fe) | May 05, 2024 |
| Lenovo        | ThinkPad X220 4291U1A       | Notebook    | [56fe72121d](https://linux-hardware.org/?probe=56fe72121d) | May 05, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [2cc53cfafd](https://linux-hardware.org/?probe=2cc53cfafd) | May 05, 2024 |
| HP            | 806A                        | Desktop     | [d28c449530](https://linux-hardware.org/?probe=d28c449530) | May 05, 2024 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [7380e71093](https://linux-hardware.org/?probe=7380e71093) | May 05, 2024 |
| HP            | 650                         | Notebook    | [aa4f605e5e](https://linux-hardware.org/?probe=aa4f605e5e) | May 05, 2024 |
| Timi          | Mi NoteBook Pro             | Notebook    | [71071a816e](https://linux-hardware.org/?probe=71071a816e) | May 05, 2024 |
| Lenovo        | ThinkPad X240 20ALA08VRT    | Notebook    | [b894f49df3](https://linux-hardware.org/?probe=b894f49df3) | May 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [ce0eb6aa57](https://linux-hardware.org/?probe=ce0eb6aa57) | May 05, 2024 |
| HP            | Compaq 6720s                | Notebook    | [e51bd60d05](https://linux-hardware.org/?probe=e51bd60d05) | May 05, 2024 |
| Lenovo        | ThinkPad L512 2597W1R       | Notebook    | [d7cb3b5ddd](https://linux-hardware.org/?probe=d7cb3b5ddd) | May 05, 2024 |
| MSI           | Modern 14 B11MOL            | Notebook    | [c394eac782](https://linux-hardware.org/?probe=c394eac782) | May 05, 2024 |
| Dell          | 0J9VVP A00                  | Desktop     | [f75406b494](https://linux-hardware.org/?probe=f75406b494) | May 05, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [d0b08c1666](https://linux-hardware.org/?probe=d0b08c1666) | May 05, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [d9c907af86](https://linux-hardware.org/?probe=d9c907af86) | May 05, 2024 |
| Acer          | Aspire A315-23              | Notebook    | [35b8f59849](https://linux-hardware.org/?probe=35b8f59849) | May 05, 2024 |
| Micro Comp... | V3                          | Tablet      | [4d2b3ac262](https://linux-hardware.org/?probe=4d2b3ac262) | May 05, 2024 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [6794452c3b](https://linux-hardware.org/?probe=6794452c3b) | May 05, 2024 |
| Gigabyte      | Z390 UD                     | Desktop     | [af2a20709c](https://linux-hardware.org/?probe=af2a20709c) | May 05, 2024 |
| Intel         | NUC7i5BNB J31144-311        | Mini pc     | [64953efef1](https://linux-hardware.org/?probe=64953efef1) | May 05, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | Notebook    | [db370ffb35](https://linux-hardware.org/?probe=db370ffb35) | May 05, 2024 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [a099133a32](https://linux-hardware.org/?probe=a099133a32) | May 05, 2024 |
| Dell          | 03X6X0 A06                  | Server      | [2e6f46fe60](https://linux-hardware.org/?probe=2e6f46fe60) | May 05, 2024 |
| Lenovo        | Flex 3-1130 80LY            | Notebook    | [3786d9e8e2](https://linux-hardware.org/?probe=3786d9e8e2) | May 05, 2024 |
| ASRock        | 990FX Extreme4              | Desktop     | [4a08259d5e](https://linux-hardware.org/?probe=4a08259d5e) | May 05, 2024 |
| Acer          | Swift SFA16-41              | Notebook    | [df5596b6b2](https://linux-hardware.org/?probe=df5596b6b2) | May 05, 2024 |
| ASUSTek       | PN50                        | Mini pc     | [bab451ff6f](https://linux-hardware.org/?probe=bab451ff6f) | May 05, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [08cb15cda7](https://linux-hardware.org/?probe=08cb15cda7) | May 05, 2024 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [19cb329ead](https://linux-hardware.org/?probe=19cb329ead) | May 05, 2024 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [1ee81eb650](https://linux-hardware.org/?probe=1ee81eb650) | May 05, 2024 |
| Microsoft     | Surface Go 2                | Tablet      | [27703b6ab1](https://linux-hardware.org/?probe=27703b6ab1) | May 05, 2024 |
| Alienware     | 17 R4                       | Notebook    | [4ad46d150c](https://linux-hardware.org/?probe=4ad46d150c) | May 05, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [a88155be11](https://linux-hardware.org/?probe=a88155be11) | May 05, 2024 |
| Acer          | Nitro AN515-46              | Notebook    | [23ae7fd7c6](https://linux-hardware.org/?probe=23ae7fd7c6) | May 05, 2024 |
| Samsung       | R528/R728                   | Notebook    | [2f4a17771e](https://linux-hardware.org/?probe=2f4a17771e) | May 05, 2024 |
| Dell          | Latitude 7480               | Notebook    | [124ec816c7](https://linux-hardware.org/?probe=124ec816c7) | May 05, 2024 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | Notebook    | [bc053b7c75](https://linux-hardware.org/?probe=bc053b7c75) | May 05, 2024 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5510492a9b](https://linux-hardware.org/?probe=5510492a9b) | May 05, 2024 |
| System76      | Oryx Pro                    | Notebook    | [6d05743481](https://linux-hardware.org/?probe=6d05743481) | May 05, 2024 |
| ASUSTek       | A7U                         | Notebook    | [d380bb6272](https://linux-hardware.org/?probe=d380bb6272) | May 05, 2024 |
| MSI           | WS66 11UKT                  | Notebook    | [f9ab812619](https://linux-hardware.org/?probe=f9ab812619) | May 05, 2024 |
| HP            | 240 G8                      | Notebook    | [8b7c23e6cb](https://linux-hardware.org/?probe=8b7c23e6cb) | May 05, 2024 |
| Huanan        | X99-TF                      | Desktop     | [804eb7916a](https://linux-hardware.org/?probe=804eb7916a) | May 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [3602db941f](https://linux-hardware.org/?probe=3602db941f) | May 05, 2024 |
| PCSMART       | 7.0                         | Desktop     | [18ea3d8d19](https://linux-hardware.org/?probe=18ea3d8d19) | May 05, 2024 |
| Supermicro    | H12SSL-NT                   | Server      | [e156a869a2](https://linux-hardware.org/?probe=e156a869a2) | May 05, 2024 |
| ASUSTek       | GR8                         | Notebook    | [6a8003e347](https://linux-hardware.org/?probe=6a8003e347) | May 05, 2024 |
| Dell          | 0NW6H5 A00                  | Desktop     | [ed934b8b61](https://linux-hardware.org/?probe=ed934b8b61) | May 05, 2024 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [4afe74277e](https://linux-hardware.org/?probe=4afe74277e) | May 05, 2024 |
| HP            | Presario CQ42               | Notebook    | [809ae686e3](https://linux-hardware.org/?probe=809ae686e3) | May 05, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [336365df6e](https://linux-hardware.org/?probe=336365df6e) | May 05, 2024 |
| Shenzhen M... | F7BFD                       | Desktop     | [41da20c6a7](https://linux-hardware.org/?probe=41da20c6a7) | May 05, 2024 |
| Novatech      | NE14I310                    | Notebook    | [f2a49ce1fc](https://linux-hardware.org/?probe=f2a49ce1fc) | May 05, 2024 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [80f71c25c1](https://linux-hardware.org/?probe=80f71c25c1) | May 05, 2024 |
| BANGHO        | Suma 1025                   | Tablet      | [e7c37d670f](https://linux-hardware.org/?probe=e7c37d670f) | May 05, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [466c94724a](https://linux-hardware.org/?probe=466c94724a) | May 05, 2024 |
| PC Engines    | apu4                        | Desktop     | [02cb7f9180](https://linux-hardware.org/?probe=02cb7f9180) | May 05, 2024 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [e362e7892b](https://linux-hardware.org/?probe=e362e7892b) | May 05, 2024 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [ab0226a735](https://linux-hardware.org/?probe=ab0226a735) | May 05, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fc52b48b01](https://linux-hardware.org/?probe=fc52b48b01) | May 05, 2024 |
| Gigabyte      | B450 GAMING X               | Desktop     | [632943f952](https://linux-hardware.org/?probe=632943f952) | May 05, 2024 |
| Dell          | Inspiron 7520               | Notebook    | [87c4f1733b](https://linux-hardware.org/?probe=87c4f1733b) | May 05, 2024 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [8d1ee988ad](https://linux-hardware.org/?probe=8d1ee988ad) | May 05, 2024 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [4e837501bb](https://linux-hardware.org/?probe=4e837501bb) | May 05, 2024 |
| Dell          | Precision M4700             | Notebook    | [7b8ccefbed](https://linux-hardware.org/?probe=7b8ccefbed) | May 05, 2024 |
| Panasonic     | FZM1-3                      | Tablet      | [8a7d985c38](https://linux-hardware.org/?probe=8a7d985c38) | May 05, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [eb9fc84dcf](https://linux-hardware.org/?probe=eb9fc84dcf) | May 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [5f2d3291b5](https://linux-hardware.org/?probe=5f2d3291b5) | May 05, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [9cdeec0464](https://linux-hardware.org/?probe=9cdeec0464) | May 05, 2024 |
| Acer          | AOD270                      | Notebook    | [af6b765474](https://linux-hardware.org/?probe=af6b765474) | May 05, 2024 |
| HP            | Notebook                    | Notebook    | [27cafe3bf5](https://linux-hardware.org/?probe=27cafe3bf5) | May 05, 2024 |
| ASRock        | E350M1/USB3                 | Desktop     | [d82d76d3e5](https://linux-hardware.org/?probe=d82d76d3e5) | May 05, 2024 |
| ASRock        | B450M Pro4                  | Desktop     | [af898c03a5](https://linux-hardware.org/?probe=af898c03a5) | May 05, 2024 |
| HP            | ZBook 15 G3                 | Notebook    | [74576596b1](https://linux-hardware.org/?probe=74576596b1) | May 05, 2024 |
| Lenovo        | ThinkPad Edge E530 32597... | Notebook    | [a216f0b6d5](https://linux-hardware.org/?probe=a216f0b6d5) | May 05, 2024 |
| Dell          | Latitude 5410               | Notebook    | [8302f81328](https://linux-hardware.org/?probe=8302f81328) | May 04, 2024 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [c1db6719c8](https://linux-hardware.org/?probe=c1db6719c8) | May 04, 2024 |
| Gigabyte      | X670E AORUS PRO X           | Desktop     | [e1dcda5e45](https://linux-hardware.org/?probe=e1dcda5e45) | May 04, 2024 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [22b510c32b](https://linux-hardware.org/?probe=22b510c32b) | May 04, 2024 |
| Shenzhen B... | XN116B                      | Notebook    | [47dbcecbd7](https://linux-hardware.org/?probe=47dbcecbd7) | May 04, 2024 |
| ASRock        | B560 Pro4                   | Desktop     | [30ae860ce9](https://linux-hardware.org/?probe=30ae860ce9) | May 04, 2024 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [da37bf116d](https://linux-hardware.org/?probe=da37bf116d) | May 04, 2024 |
| Dell          | 06FW8P A01                  | Desktop     | [41be164658](https://linux-hardware.org/?probe=41be164658) | May 04, 2024 |
| Acer          | Switch SW312-31             | Tablet      | [e7fe09d066](https://linux-hardware.org/?probe=e7fe09d066) | May 04, 2024 |
| Dell          | Precision 3510              | Notebook    | [c57923e0ff](https://linux-hardware.org/?probe=c57923e0ff) | May 04, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [afb966db9e](https://linux-hardware.org/?probe=afb966db9e) | May 04, 2024 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 25937     | 9.45%   |
| Ubuntu 22.04      | 16217     | 5.91%   |
| Ubuntu 18.04      | 13209     | 4.81%   |
| Debian 11         | 6982      | 2.54%   |
| Arch Rolling      | 5614      | 2.04%   |
| OpenMandriva 4.2  | 4722      | 1.72%   |
| OpenMandriva 4.3  | 4674      | 1.7%    |
| Pop!_OS 22.04     | 4448      | 1.62%   |
| ROSA R10          | 4390      | 1.6%    |
| ROSA R11          | 4125      | 1.5%    |
| Zorin 16          | 4033      | 1.47%   |
| Debian 12         | 3898      | 1.42%   |
| ROSA R8           | 3637      | 1.32%   |
| ROSA R6           | 3496      | 1.27%   |
| Manjaro           | 3381      | 1.23%   |
| ROSA R7           | 3301      | 1.2%    |
| Linux Mint 20.3   | 3281      | 1.19%   |
| BlackPanther 18.1 | 3119      | 1.14%   |
| Fedora 38         | 3033      | 1.1%    |
| Arch              | 2983      | 1.09%   |
| Fedora 39         | 2970      | 1.08%   |
| KDE neon 20.04    | 2867      | 1.04%   |
| ROSA R8.1         | 2853      | 1.04%   |
| Linux Mint 21.1   | 2817      | 1.03%   |
| ArcoLinux Rolling | 2678      | 0.98%   |
| ROSA R9           | 2552      | 0.93%   |
| Linux Mint 20.2   | 2450      | 0.89%   |
| Linux Mint 21.2   | 2390      | 0.87%   |
| ROSA R11.1        | 2384      | 0.87%   |
| Linux Mint 20.1   | 2280      | 0.83%   |
| Ubuntu 20.10      | 2232      | 0.81%   |
| Linux Mint 19.3   | 2216      | 0.81%   |
| Fedora 36         | 2148      | 0.78%   |
| Pop!_OS 20.04     | 2134      | 0.78%   |
| Ubuntu 21.10      | 2097      | 0.76%   |
| Fedora 37         | 2062      | 0.75%   |
| Ubuntu 19.10      | 2057      | 0.75%   |
| Linux Mint 20     | 2047      | 0.75%   |
| Xubuntu 20.04     | 2034      | 0.74%   |
| ROSA 12.2         | 2021      | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 68681     | 27.01%  |
| ROSA          | 27539     | 10.83%  |
| Linux Mint    | 20630     | 8.11%   |
| OpenMandriva  | 17131     | 6.74%   |
| Fedora        | 16295     | 6.41%   |
| Debian        | 13803     | 5.43%   |
| Pop!_OS       | 10685     | 4.2%    |
| Arch          | 8419      | 3.31%   |
| Manjaro       | 7714      | 3.03%   |
| Zorin         | 6793      | 2.67%   |
| Kubuntu       | 4911      | 1.93%   |
| Xubuntu       | 4580      | 1.8%    |
| KDE neon      | 4499      | 1.77%   |
| Endless       | 3538      | 1.39%   |
| BlackPanther  | 3391      | 1.33%   |
| openSUSE      | 2954      | 1.16%   |
| ArcoLinux     | 2862      | 1.13%   |
| Kali          | 2099      | 0.83%   |
| Elementary    | 1908      | 0.75%   |
| Gentoo        | 1771      | 0.7%    |
| SteamOS       | 1616      | 0.64%   |
| Ubuntu MATE   | 1581      | 0.62%   |
| Lubuntu       | 1539      | 0.61%   |
| EndeavourOS   | 1528      | 0.6%    |
| Ubuntu Unity  | 1216      | 0.48%   |
| LMDE          | 1122      | 0.44%   |
| Nobara        | 1008      | 0.4%    |
| Clear Linux   | 897       | 0.35%   |
| MX            | 864       | 0.34%   |
| CentOS        | 826       | 0.32%   |
| ALT Linux     | 720       | 0.28%   |
| Ubuntu Budgie | 710       | 0.28%   |
| Garuda Linux  | 665       | 0.26%   |
| Parrot        | 591       | 0.23%   |
| Xero          | 454       | 0.18%   |
| Red OS        | 441       | 0.17%   |
| NixOS         | 419       | 0.16%   |
| Raspbian      | 343       | 0.13%   |
| RHEL          | 324       | 0.13%   |
| Peppermint    | 310       | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002           | 4550      | 1.5%    |
| 5.16.7-desktop-1omv4003            | 4365      | 1.44%   |
| 5.4.0-42-generic                   | 3816      | 1.26%   |
| 4.18.16-desktop-1bP                | 2223      | 0.73%   |
| 5.15.0-56-generic                  | 2187      | 0.72%   |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 2020      | 0.67%   |
| 6.2.6-desktop-1omv2390             | 1914      | 0.63%   |
| 6.1.1-desktop-1omv2290             | 1849      | 0.61%   |
| 3.14.44-nrj-desktop-2rosa-x86_64   | 1829      | 0.6%    |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 1827      | 0.6%    |
| 4.15.0-desktop-45.1rosa-x86_64     | 1807      | 0.6%    |
| 5.10.74-generic-2rosa2021.1-x86_64 | 1802      | 0.59%   |
| 5.4.0-58-generic                   | 1735      | 0.57%   |
| 6.4.11-desktop-1omv2390            | 1652      | 0.54%   |
| 4.1.25-nrj-desktop-1rosa-x86_64    | 1592      | 0.52%   |
| 5.4.0-48-generic                   | 1532      | 0.51%   |
| 5.4.0-52-generic                   | 1521      | 0.5%    |
| 5.15.0-58-generic                  | 1514      | 0.5%    |
| 5.15.0-52-generic                  | 1466      | 0.48%   |
| 4.1.15-nrj-desktop-1rosa-x86_64    | 1352      | 0.45%   |
| 5.4.0-26-generic                   | 1345      | 0.44%   |
| 5.15.0-46-generic                  | 1227      | 0.4%    |
| 5.3.0-28-generic                   | 1136      | 0.37%   |
| 5.4.0-29-generic                   | 1125      | 0.37%   |
| 6.6.2-desktop-1omv2390             | 1124      | 0.37%   |
| 6.2.0-26-generic                   | 1124      | 0.37%   |
| 5.4.0-40-generic                   | 1101      | 0.36%   |
| 5.3.0-40-generic                   | 1089      | 0.36%   |
| 5.11.0-27-generic                  | 1080      | 0.36%   |
| 5.15.0-91-generic                  | 1078      | 0.36%   |
| 5.15.0-48-generic                  | 1069      | 0.35%   |
| 6.5.0-14-generic                   | 1054      | 0.35%   |
| 5.10.0-8-amd64                     | 1010      | 0.33%   |
| 5.3.0-46-generic                   | 998       | 0.33%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 979       | 0.32%   |
| 5.19.0-35-generic                  | 965       | 0.32%   |
| 5.4.0-54-generic                   | 950       | 0.31%   |
| 5.4.0-91-generic                   | 947       | 0.31%   |
| 6.2.0-39-generic                   | 943       | 0.31%   |
| 5.6.14-desktop-2bP                 | 940       | 0.31%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 33642     | 11.74%  |
| 5.15.0  | 22518     | 7.86%   |
| 4.15.0  | 14533     | 5.07%   |
| 5.8.0   | 10689     | 3.73%   |
| 5.11.0  | 10342     | 3.61%   |
| 5.13.0  | 9401      | 3.28%   |
| 5.3.0   | 7860      | 2.74%   |
| 5.10.0  | 7698      | 2.69%   |
| 5.19.0  | 7252      | 2.53%   |
| 6.2.0   | 6942      | 2.42%   |
| 6.5.0   | 6684      | 2.33%   |
| 5.0.0   | 5267      | 1.84%   |
| 6.1.0   | 4847      | 1.69%   |
| 5.10.14 | 4601      | 1.61%   |
| 5.16.7  | 4429      | 1.55%   |
| 4.18.0  | 4021      | 1.4%    |
| 6.2.6   | 2905      | 1.01%   |
| 3.14.44 | 2649      | 0.92%   |
| 4.9.20  | 2568      | 0.9%    |
| 4.9.60  | 2556      | 0.89%   |
| 4.18.16 | 2279      | 0.8%    |
| 4.1.25  | 2161      | 0.75%   |
| 6.1.1   | 2113      | 0.74%   |
| 4.19.0  | 1993      | 0.7%    |
| 6.4.11  | 1920      | 0.67%   |
| 5.10.74 | 1866      | 0.65%   |
| 4.1.15  | 1801      | 0.63%   |
| 6.6.2   | 1389      | 0.48%   |
| 4.1.34  | 1355      | 0.47%   |
| 4.1.38  | 1113      | 0.39%   |
| 5.6.14  | 1045      | 0.36%   |
| 5.14.0  | 1022      | 0.36%   |
| 4.9.124 | 1013      | 0.35%   |
| 4.9.9   | 978       | 0.34%   |
| 6.5.6   | 946       | 0.33%   |
| 5.17.5  | 866       | 0.3%    |
| 6.1.20  | 818       | 0.29%   |
| 6.0.12  | 809       | 0.28%   |
| 6.0.0   | 796       | 0.28%   |
| 4.9.155 | 697       | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 37152     | 13.31%  |
| 5.15    | 29210     | 10.47%  |
| 5.10    | 18458     | 6.61%   |
| 4.15    | 14609     | 5.23%   |
| 6.1     | 13029     | 4.67%   |
| 5.8     | 12977     | 4.65%   |
| 6.2     | 12576     | 4.51%   |
| 5.11    | 12285     | 4.4%    |
| 5.13    | 11055     | 3.96%   |
| 6.5     | 10544     | 3.78%   |
| 5.19    | 9422      | 3.38%   |
| 4.9     | 9300      | 3.33%   |
| 5.3     | 8875      | 3.18%   |
| 4.1     | 7591      | 2.72%   |
| 5.16    | 7443      | 2.67%   |
| 4.18    | 6404      | 2.29%   |
| 6.6     | 5942      | 2.13%   |
| 5.0     | 5587      | 2%      |
| 6.4     | 5060      | 1.81%   |
| 6.0     | 4329      | 1.55%   |
| 3.14    | 3504      | 1.26%   |
| 5.14    | 3119      | 1.12%   |
| 5.17    | 2955      | 1.06%   |
| 5.18    | 2944      | 1.05%   |
| 5.6     | 2829      | 1.01%   |
| 6.3     | 2805      | 1%      |
| 4.19    | 2620      | 0.94%   |
| 6.7     | 2597      | 0.93%   |
| 6.8     | 2415      | 0.87%   |
| 5.9     | 2355      | 0.84%   |
| 5.12    | 1896      | 0.68%   |
| 5.7     | 1640      | 0.59%   |
| 5.5     | 985       | 0.35%   |
| 4.4     | 871       | 0.31%   |
| 3.10    | 716       | 0.26%   |
| 4.13    | 406       | 0.15%   |
| 5.2     | 399       | 0.14%   |
| 5.1     | 391       | 0.14%   |
| 4.14    | 240       | 0.09%   |
| 4.12    | 188       | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 231870    | 94.76%  |
| i686        | 10440     | 4.27%   |
| aarch64     | 1741      | 0.71%   |
| armv7l      | 461       | 0.19%   |
| armv6l      | 50        | 0.02%   |
| armv8l      | 40        | 0.02%   |
| riscv64     | 31        | 0.01%   |
| ppc64       | 10        | 0.004%  |
| ppc         | 10        | 0.004%  |
| loongarch64 | 8         | 0.003%  |
| i586        | 7         | 0.003%  |
| e2k         | 7         | 0.003%  |
| Unknown     | 7         | 0.003%  |
| ppc64le     | 5         | 0.002%  |
| mips64      | 4         | 0.002%  |
| mips        | 3         | 0.001%  |
| armv5tel    | 2         | 0.001%  |
| unknow      | 1         | 0.0004% |
| sparc64     | 1         | 0.0004% |
| sh4a        | 1         | 0.0004% |
| s390x       | 1         | 0.0004% |
| i486        | 1         | 0.0004% |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 99875     | 38.84%  |
| KDE5             | 50427     | 19.61%  |
| Unknown          | 26275     | 10.22%  |
| KDE4             | 18398     | 7.15%   |
| XFCE             | 16521     | 6.42%   |
| X-Cinnamon       | 16041     | 6.24%   |
| MATE             | 6565      | 2.55%   |
| KDE              | 4674      | 1.82%   |
| LXQt             | 3347      | 1.3%    |
| Cinnamon         | 2862      | 1.11%   |
| Pantheon         | 1834      | 0.71%   |
| LXDE             | 1293      | 0.5%    |
| i3               | 1280      | 0.5%    |
| Unity            | 1244      | 0.48%   |
| Budgie           | 1180      | 0.46%   |
| KDE6             | 865       | 0.34%   |
| GNOME Flashback  | 599       | 0.23%   |
| Deepin           | 584       | 0.23%   |
| Hyprland         | 391       | 0.15%   |
| GNOME Classic    | 321       | 0.12%   |
| sway             | 315       | 0.12%   |
| Openbox          | 259       | 0.1%    |
| awesome          | 253       | 0.1%    |
| GNUstep          | 172       | 0.07%   |
| bspwm            | 168       | 0.07%   |
| lightdm-xsession | 142       | 0.06%   |
| dwm              | 129       | 0.05%   |
| qtile            | 123       | 0.05%   |
| Trinity          | 96        | 0.04%   |
| Enlightenment    | 96        | 0.04%   |
| icewm            | 94        | 0.04%   |
| xmonad           | 84        | 0.03%   |
| Endless:GNOME    | 53        | 0.02%   |
| LeftWM           | 45        | 0.02%   |
| BunsenLabs       | 38        | 0.01%   |
| i3-with-shmlog   | 30        | 0.01%   |
| fluxbox          | 29        | 0.01%   |
| fly              | 27        | 0.01%   |
| UKUI             | 26        | 0.01%   |
| chadwm           | 25        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 184090    | 72.83%  |
| Wayland     | 48829     | 19.32%  |
| Unknown     | 14345     | 5.68%   |
| Tty         | 5437      | 2.15%   |
| Web         | 37        | 0.01%   |
| Unspecified | 12        | 0.005%  |
| Xcb         | 1         | 0.0004% |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Unknown         | 108008    | 42.2%   |
| SDDM            | 45240     | 17.68%  |
| GDM3            | 28100     | 10.98%  |
| GDM             | 25676     | 10.03%  |
| LightDM         | 23033     | 9%      |
| KDM             | 18521     | 7.24%   |
| TDM             | 6042      | 2.36%   |
| XDM             | 389       | 0.15%   |
| SLiM            | 268       | 0.1%    |
| LXDM            | 205       | 0.08%   |
| Ly              | 109       | 0.04%   |
| MDM             | 89        | 0.03%   |
| GREETD          | 80        | 0.03%   |
| NODM            | 67        | 0.03%   |
| LY-DM           | 44        | 0.02%   |
| SLIMSKI         | 28        | 0.01%   |
| FLY-DM          | 20        | 0.01%   |
| EMPTTY          | 9         | 0.004%  |
| WDM             | 6         | 0.002%  |
| LDM             | 4         | 0.002%  |
| LEMURS          | 3         | 0.001%  |
| SU              | 2         | 0.001%  |
| XINIT           | 1         | 0.0004% |
| LYNDE           | 1         | 0.0004% |
| KODI-STANDALONE | 1         | 0.0004% |
| DARKDM_ON_TTY   | 1         | 0.0004% |
| CDM             | 1         | 0.0004% |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 88777     | 35.36%  |
| Unknown | 43475     | 17.32%  |
| de_DE   | 16423     | 6.54%   |
| ru_RU   | 15912     | 6.34%   |
| en_GB   | 10847     | 4.32%   |
| pt_BR   | 10083     | 4.02%   |
| fr_FR   | 9330      | 3.72%   |
| it_IT   | 6208      | 2.47%   |
| es_ES   | 4818      | 1.92%   |
| C       | 4588      | 1.83%   |
| en_CA   | 3967      | 1.58%   |
| pl_PL   | 3609      | 1.44%   |
| en_IN   | 3257      | 1.3%    |
| en_AU   | 2994      | 1.19%   |
| es_MX   | 1703      | 0.68%   |
| nl_NL   | 1506      | 0.6%    |
| cs_CZ   | 1321      | 0.53%   |
| es_AR   | 1267      | 0.5%    |
| hu_HU   | 1183      | 0.47%   |
| zh_CN   | 1036      | 0.41%   |
| tr_TR   | 903       | 0.36%   |
| pt_PT   | 896       | 0.36%   |
| de_AT   | 884       | 0.35%   |
| en_ZA   | 842       | 0.34%   |
| sv_SE   | 716       | 0.29%   |
| de_CH   | 674       | 0.27%   |
| ja_JP   | 637       | 0.25%   |
| es_CL   | 599       | 0.24%   |
| es_CO   | 592       | 0.24%   |
| fi_FI   | 552       | 0.22%   |
| ru_UA   | 548       | 0.22%   |
| en_NZ   | 546       | 0.22%   |
| en_IE   | 509       | 0.2%    |
| fr_CA   | 492       | 0.2%    |
| fr_BE   | 415       | 0.17%   |
| el_GR   | 400       | 0.16%   |
| ro_RO   | 398       | 0.16%   |
| da_DK   | 371       | 0.15%   |
| nl_BE   | 360       | 0.14%   |
| en_PH   | 335       | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 132758    | 53%     |
| EFI  | 117726    | 47%     |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 170822    | 67.35%  |
| Btrfs               | 25155     | 9.92%   |
| Unknown             | 21433     | 8.45%   |
| Overlay             | 21046     | 8.3%    |
| Tmpfs               | 8420      | 3.32%   |
| Xfs                 | 3312      | 1.31%   |
| Zfs                 | 1722      | 0.68%   |
| Ext2                | 526       | 0.21%   |
| Ext3                | 483       | 0.19%   |
| F2fs                | 373       | 0.15%   |
| Aufs                | 89        | 0.04%   |
| Rootfs              | 60        | 0.02%   |
| Reiserfs            | 57        | 0.02%   |
| Jfs                 | 46        | 0.02%   |
| XXXXXXX             | 28        | 0.01%   |
| Bcachefs            | 12        | 0.005%  |
| XXXXX               | 9         | 0.004%  |
| XXX4                | 7         | 0.003%  |
| SAMSUNG             | 7         | 0.003%  |
| Fuse.fuse-overlayfs | 5         | 0.002%  |
| XXXX                | 4         | 0.002%  |
| XXX                 | 3         | 0.001%  |
| ExX4                | 3         | 0.001%  |
| XXXfs               | 2         | 0.001%  |
| Ubifs               | 2         | 0.001%  |
| Ntfs                | 2         | 0.001%  |
| Xtrfs               | 1         | 0.0004% |
| Ufs                 | 1         | 0.0004% |
| Udf                 | 1         | 0.0004% |
| SquXshfs            | 1         | 0.0004% |
| SquasXfs            | 1         | 0.0004% |
| OveXlay             | 1         | 0.0004% |
| Nilfs2              | 1         | 0.0004% |
| Nfs                 | 1         | 0.0004% |
| Lvm                 | 1         | 0.0004% |
| Fuse.sshfs          | 1         | 0.0004% |
| Fuse.snapfuse       | 1         | 0.0004% |
| Fake                | 1         | 0.0004% |
| Exfat               | 1         | 0.0004% |
| 2G                  | 1         | 0.0004% |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 112780    | 44.61%  |
| GPT     | 97801     | 38.69%  |
| MBR     | 42214     | 16.7%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 213030    | 85.12%  |
| Yes       | 37237     | 14.88%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 178338    | 71.31%  |
| Yes       | 71745     | 28.69%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 42144     | 17.28%  |
| Lenovo                  | 32374     | 13.27%  |
| Hewlett-Packard         | 31421     | 12.88%  |
| Dell                    | 28341     | 11.62%  |
| Gigabyte Technology     | 17191     | 7.05%   |
| Acer                    | 14289     | 5.86%   |
| MSI                     | 13964     | 5.73%   |
| ASRock                  | 8855      | 3.63%   |
| Apple                   | 5987      | 2.45%   |
| Intel                   | 4251      | 1.74%   |
| Toshiba                 | 3701      | 1.52%   |
| Samsung Electronics     | 3351      | 1.37%   |
| Unknown                 | 2595      | 1.06%   |
| Sony                    | 1950      | 0.8%    |
| Fujitsu                 | 1833      | 0.75%   |
| HUAWEI                  | 1510      | 0.62%   |
| Valve                   | 1368      | 0.56%   |
| Raspberry Pi Foundation | 1352      | 0.55%   |
| Google                  | 1104      | 0.45%   |
| Medion                  | 1088      | 0.45%   |
| Pegatron                | 1018      | 0.42%   |
| Supermicro              | 975       | 0.4%    |
| Packard Bell            | 948       | 0.39%   |
| Biostar                 | 929       | 0.38%   |
| Foxconn                 | 923       | 0.38%   |
| ECS                     | 889       | 0.36%   |
| Positivo                | 853       | 0.35%   |
| Microsoft               | 821       | 0.34%   |
| Notebook                | 817       | 0.33%   |
| Alienware               | 636       | 0.26%   |
| Fujitsu Siemens         | 634       | 0.26%   |
| AZW                     | 508       | 0.21%   |
| eMachines               | 493       | 0.2%    |
| Timi                    | 488       | 0.2%    |
| System76                | 455       | 0.19%   |
| TUXEDO                  | 441       | 0.18%   |
| AMI                     | 418       | 0.17%   |
| LG Electronics          | 376       | 0.15%   |
| Chuwi                   | 368       | 0.15%   |
| Clevo                   | 360       | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 3401      | 1.39%   |
| ASUS All Series              | 2277      | 0.93%   |
| Valve Jupiter                | 1290      | 0.53%   |
| HP Notebook                  | 857       | 0.35%   |
| HP Pavilion g6               | 572       | 0.23%   |
| HP Pavilion dv6              | 557       | 0.23%   |
| Dell OptiPlex 7010           | 480       | 0.2%    |
| ASUS TUF Gaming X570-PLUS    | 428       | 0.18%   |
| MSI MS-7C37                  | 418       | 0.17%   |
| RPi Raspberry Pi             | 389       | 0.16%   |
| Apple MacBook5,2             | 386       | 0.16%   |
| HP Pavilion 15               | 368       | 0.15%   |
| MSI MS-7C02                  | 367       | 0.15%   |
| Gigabyte B450M DS3H          | 359       | 0.15%   |
| ASUS PRIME A320M-K           | 355       | 0.15%   |
| HP Pavilion dv7              | 349       | 0.14%   |
| Dell OptiPlex 9020           | 349       | 0.14%   |
| HP Pavilion Notebook         | 346       | 0.14%   |
| MSI MS-7817                  | 320       | 0.13%   |
| Apple MacBookPro9,2          | 309       | 0.13%   |
| MSI MS-7B86                  | 302       | 0.12%   |
| Apple MacBookAir7,2          | 292       | 0.12%   |
| Gigabyte 970A-DS3P           | 285       | 0.12%   |
| Dell Latitude E6420          | 281       | 0.12%   |
| Apple MacBookPro8,1          | 269       | 0.11%   |
| Dell OptiPlex 780            | 268       | 0.11%   |
| MSI MS-7C91                  | 267       | 0.11%   |
| HP 15                        | 263       | 0.11%   |
| Dell OptiPlex 790            | 261       | 0.11%   |
| Dell Latitude E6430          | 259       | 0.11%   |
| ASUS M5A97 R2.0              | 249       | 0.1%    |
| MSI MS-7A38                  | 246       | 0.1%    |
| Dell Latitude E6410          | 245       | 0.1%    |
| ASUS M5A78L-M/USB3           | 245       | 0.1%    |
| MSI MS-7721                  | 243       | 0.1%    |
| MSI MS-7C56                  | 241       | 0.1%    |
| ASUS ROG STRIX B550-F GAMING | 240       | 0.1%    |
| MSI MS-7693                  | 237       | 0.1%    |
| MSI MS-7B79                  | 233       | 0.1%    |
| Dell OptiPlex 3020           | 231       | 0.09%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 13632     | 5.59%   |
| Acer Aspire        | 9441      | 3.87%   |
| Dell Inspiron      | 7392      | 3.03%   |
| Dell Latitude      | 7147      | 2.93%   |
| Lenovo IdeaPad     | 6412      | 2.63%   |
| HP Pavilion        | 5779      | 2.37%   |
| ASUS PRIME         | 4258      | 1.75%   |
| Dell OptiPlex      | 4208      | 1.73%   |
| ASUS ROG           | 3920      | 1.61%   |
| HP EliteBook       | 3761      | 1.54%   |
| Unknown            | 3401      | 1.39%   |
| ASUS VivoBook      | 3209      | 1.32%   |
| HP Compaq          | 3161      | 1.3%    |
| Toshiba Satellite  | 3095      | 1.27%   |
| Dell XPS           | 3041      | 1.25%   |
| HP Laptop          | 2992      | 1.23%   |
| HP ProBook         | 2991      | 1.23%   |
| Dell Precision     | 2568      | 1.05%   |
| ASUS TUF           | 2301      | 0.94%   |
| ASUS All           | 2277      | 0.93%   |
| Lenovo ThinkCentre | 1995      | 0.82%   |
| Dell Vostro        | 1658      | 0.68%   |
| HP ENVY            | 1484      | 0.61%   |
| Lenovo Yoga        | 1361      | 0.56%   |
| RPi Raspberry      | 1350      | 0.55%   |
| Valve Jupiter      | 1290      | 0.53%   |
| Lenovo Legion      | 1203      | 0.49%   |
| Acer Nitro         | 1159      | 0.48%   |
| ASUS Zenbook       | 933       | 0.38%   |
| HP Notebook        | 860       | 0.35%   |
| HP EliteDesk       | 832       | 0.34%   |
| Acer Swift         | 829       | 0.34%   |
| Microsoft Surface  | 821       | 0.34%   |
| Fujitsu LIFEBOOK   | 795       | 0.33%   |
| ASUS ASUS          | 794       | 0.33%   |
| ASUS M5A78L-M      | 775       | 0.32%   |
| HP ZBook           | 757       | 0.31%   |
| Gigabyte X570      | 733       | 0.3%    |
| Lenovo ThinkBook   | 709       | 0.29%   |
| Gigabyte B450M     | 681       | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 20583     | 8.44%   |
| 2012    | 20398     | 8.36%   |
| 2019    | 19441     | 7.97%   |
| 2020    | 19183     | 7.87%   |
| 2011    | 17984     | 7.37%   |
| 2013    | 16892     | 6.93%   |
| 2021    | 15366     | 6.3%    |
| 2017    | 14981     | 6.14%   |
| 2014    | 13585     | 5.57%   |
| 2010    | 13078     | 5.36%   |
| 2015    | 11569     | 4.74%   |
| 2016    | 11367     | 4.66%   |
| 2009    | 10749     | 4.41%   |
| 2008    | 10061     | 4.13%   |
| 2022    | 9850      | 4.04%   |
| 2007    | 7025      | 2.88%   |
| 2023    | 4613      | 1.89%   |
| 2006    | 3074      | 1.26%   |
| Unknown | 2179      | 0.89%   |
| 2005    | 1105      | 0.45%   |
| 2004    | 334       | 0.14%   |
| 2024    | 215       | 0.09%   |
| 2003    | 176       | 0.07%   |
| 2002    | 45        | 0.02%   |
| 2001    | 21        | 0.01%   |
| 2000    | 13        | 0.01%   |
| 1999    | 3         | 0.001%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 131114    | 53.76%  |
| Desktop        | 94227     | 38.64%  |
| Convertible    | 5453      | 2.24%   |
| Mini pc        | 3449      | 1.41%   |
| All in one     | 3183      | 1.31%   |
| Server         | 2246      | 0.92%   |
| Tablet         | 2073      | 0.85%   |
| System on chip | 1973      | 0.81%   |
| Phone          | 137       | 0.06%   |
| Stick pc       | 17        | 0.01%   |
| Other          | 13        | 0.01%   |
| Firewall       | 5         | 0.002%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 228839    | 93.12%  |
| Enabled  | 16902     | 6.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 242349    | 99.36%  |
| Yes  | 1550      | 0.64%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 55331     | 22.13%  |
| 3.01-4.0        | 49126     | 19.65%  |
| 16.01-24.0      | 45425     | 18.17%  |
| 8.01-16.0       | 44203     | 17.68%  |
| 32.01-64.0      | 22748     | 9.1%    |
| 1.01-2.0        | 12395     | 4.96%   |
| 64.01-256.0     | 7255      | 2.9%    |
| 2.01-3.0        | 5777      | 2.31%   |
| 24.01-32.0      | 4401      | 1.76%   |
| 0.51-1.0        | 2152      | 0.86%   |
| More than 256.0 | 507       | 0.2%    |
| Unknown         | 434       | 0.17%   |
| 0.01-0.5        | 249       | 0.1%    |
| 0               | 2         | 0.001%  |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 93394     | 33.89%  |
| 2.01-3.0        | 63138     | 22.91%  |
| 4.01-8.0        | 37725     | 13.69%  |
| 3.01-4.0        | 32965     | 11.96%  |
| 0.51-1.0        | 29372     | 10.66%  |
| 8.01-16.0       | 10544     | 3.83%   |
| 0.01-0.5        | 4830      | 1.75%   |
| 16.01-24.0      | 1667      | 0.6%    |
| Unknown         | 644       | 0.23%   |
| 24.01-32.0      | 600       | 0.22%   |
| 32.01-64.0      | 470       | 0.17%   |
| 64.01-256.0     | 199       | 0.07%   |
| More than 256.0 | 20        | 0.01%   |
| 0               | 14        | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 152509    | 60.1%   |
| 2       | 62218     | 24.52%  |
| 3       | 19430     | 7.66%   |
| 4       | 8746      | 3.45%   |
| 5       | 4108      | 1.62%   |
| 0       | 2329      | 0.92%   |
| 6       | 1940      | 0.76%   |
| 7       | 932       | 0.37%   |
| 8       | 475       | 0.19%   |
| 9       | 287       | 0.11%   |
| 10      | 174       | 0.07%   |
| 11      | 132       | 0.05%   |
| Unknown | 118       | 0.05%   |
| 13      | 70        | 0.03%   |
| 12      | 61        | 0.02%   |
| 14      | 38        | 0.01%   |
| 17      | 21        | 0.01%   |
| 16      | 16        | 0.01%   |
| 18      | 15        | 0.01%   |
| 19      | 14        | 0.01%   |
| 15      | 14        | 0.01%   |
| 21      | 11        | 0.004%  |
| 20      | 11        | 0.004%  |
| 25      | 10        | 0.004%  |
| 27      | 8         | 0.003%  |
| 26      | 7         | 0.003%  |
| 36      | 6         | 0.002%  |
| 28      | 6         | 0.002%  |
| 24      | 6         | 0.002%  |
| 23      | 5         | 0.002%  |
| 22      | 5         | 0.002%  |
| 32      | 3         | 0.001%  |
| 97      | 2         | 0.001%  |
| 93      | 2         | 0.001%  |
| 70      | 2         | 0.001%  |
| 38      | 2         | 0.001%  |
| 37      | 2         | 0.001%  |
| 35      | 2         | 0.001%  |
| 30      | 2         | 0.001%  |
| 29      | 2         | 0.001%  |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 148675    | 60.25%  |
| Yes       | 98084     | 39.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 211431    | 86.42%  |
| No        | 33237     | 13.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 181599    | 73.84%  |
| No        | 64328     | 26.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 140503    | 56.77%  |
| No        | 106974    | 43.23%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 40286     | 16.32%  |
| Russia       | 29076     | 11.78%  |
| Germany      | 23341     | 9.46%   |
| Brazil       | 14621     | 5.92%   |
| France       | 11394     | 4.62%   |
| Italy        | 9154      | 3.71%   |
| UK           | 8966      | 3.63%   |
| Unknown      | 8142      | 3.3%    |
| Canada       | 6849      | 2.77%   |
| Spain        | 6384      | 2.59%   |
| Poland       | 5883      | 2.38%   |
| India        | 5157      | 2.09%   |
| Netherlands  | 4671      | 1.89%   |
| Hungary      | 4380      | 1.77%   |
| Australia    | 3965      | 1.61%   |
| Ukraine      | 3306      | 1.34%   |
| Mexico       | 2912      | 1.18%   |
| Switzerland  | 2562      | 1.04%   |
| Sweden       | 2473      | 1%      |
| Czechia      | 2419      | 0.98%   |
| Austria      | 2217      | 0.9%    |
| Argentina    | 2173      | 0.88%   |
| Turkey       | 2162      | 0.88%   |
| Belgium      | 2097      | 0.85%   |
| Romania      | 2042      | 0.83%   |
| Portugal     | 1811      | 0.73%   |
| China        | 1710      | 0.69%   |
| Finland      | 1703      | 0.69%   |
| Greece       | 1482      | 0.6%    |
| Indonesia    | 1472      | 0.6%    |
| Japan        | 1434      | 0.58%   |
| Norway       | 1246      | 0.5%    |
| South Africa | 1227      | 0.5%    |
| Colombia     | 1193      | 0.48%   |
| Bulgaria     | 1161      | 0.47%   |
| Denmark      | 1117      | 0.45%   |
| Belarus      | 1093      | 0.44%   |
| Chile        | 1089      | 0.44%   |
| Slovakia     | 902       | 0.37%   |
| Serbia       | 854       | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 8194      | 3.09%   |
| Moscow            | 6378      | 2.4%    |
| St Petersburg     | 2558      | 0.96%   |
| Berlin            | 2134      | 0.8%    |
| Sao Paulo         | 1841      | 0.69%   |
| Budapest          | 1756      | 0.66%   |
| Paris             | 1733      | 0.65%   |
| Voronezh          | 1406      | 0.53%   |
| Warsaw            | 1357      | 0.51%   |
| Vienna            | 1285      | 0.48%   |
| Milan             | 1283      | 0.48%   |
| Sydney            | 1110      | 0.42%   |
| Munich            | 1063      | 0.4%    |
| Rome              | 1058      | 0.4%    |
| Madrid            | 1049      | 0.4%    |
| Hamburg           | 983       | 0.37%   |
| Melbourne         | 981       | 0.37%   |
| Prague            | 954       | 0.36%   |
| Amsterdam         | 926       | 0.35%   |
| Rio de Janeiro    | 907       | 0.34%   |
| Novosibirsk       | 896       | 0.34%   |
| Bangor            | 887       | 0.33%   |
| Istanbul          | 826       | 0.31%   |
| Helsinki          | 793       | 0.3%    |
| Kyiv              | 789       | 0.3%    |
| Krasnodar         | 788       | 0.3%    |
| Yekaterinburg     | 787       | 0.3%    |
| Athens            | 782       | 0.29%   |
| Frankfurt am Main | 781       | 0.29%   |
| Pecherskoye       | 753       | 0.28%   |
| Toronto           | 730       | 0.27%   |
| Zurich            | 717       | 0.27%   |
| Barcelona         | 714       | 0.27%   |
| Montreal          | 706       | 0.27%   |
| Bengaluru         | 668       | 0.25%   |
| Bucharest         | 655       | 0.25%   |
| London            | 642       | 0.24%   |
| Los Angeles       | 631       | 0.24%   |
| New York          | 604       | 0.23%   |
| Sofia             | 603       | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 54892     | 88086  | 15.37%  |
| Seagate                     | 53504     | 85426  | 14.98%  |
| Samsung Electronics         | 52055     | 82664  | 14.58%  |
| Toshiba                     | 23243     | 32250  | 6.51%   |
| Kingston                    | 19118     | 26383  | 5.35%   |
| SanDisk                     | 18018     | 24545  | 5.05%   |
| Unknown                     | 14417     | 20081  | 4.04%   |
| Hitachi                     | 12466     | 17172  | 3.49%   |
| Crucial                     | 11728     | 16762  | 3.28%   |
| Intel                       | 8440      | 12268  | 2.36%   |
| SK hynix                    | 8125      | 10382  | 2.28%   |
| HGST                        | 6569      | 9956   | 1.84%   |
| Micron Technology           | 5262      | 6776   | 1.47%   |
| A-DATA Technology           | 5057      | 6784   | 1.42%   |
| China                       | 3443      | 4533   | 0.96%   |
| Apple                       | 2761      | 3710   | 0.77%   |
| KIOXIA                      | 2318      | 2963   | 0.65%   |
| Phison                      | 2281      | 3166   | 0.64%   |
| SPCC                        | 2166      | 2953   | 0.61%   |
| Phison Electronics          | 1915      | 2563   | 0.54%   |
| PNY                         | 1880      | 2585   | 0.53%   |
| Fujitsu                     | 1846      | 2520   | 0.52%   |
| Silicon Motion              | 1788      | 2403   | 0.5%    |
| Micron/Crucial Technology   | 1720      | 2366   | 0.48%   |
| Maxtor                      | 1669      | 2223   | 0.47%   |
| OCZ                         | 1592      | 2087   | 0.45%   |
| Intenso                     | 1544      | 2140   | 0.43%   |
| Unknown                     | 1542      | 1818   | 0.43%   |
| Transcend                   | 1445      | 1858   | 0.4%    |
| Kingston Technology Company | 1423      | 1779   | 0.4%    |
| Patriot                     | 1407      | 1889   | 0.39%   |
| LITEON                      | 1241      | 1536   | 0.35%   |
| Corsair                     | 1115      | 1509   | 0.31%   |
| JMicron Technology          | 1095      | 1329   | 0.31%   |
| GOODRAM                     | 1046      | 1519   | 0.29%   |
| Hewlett-Packard             | 1031      | 1894   | 0.29%   |
| Apacer                      | 940       | 1229   | 0.26%   |
| Team                        | 813       | 1076   | 0.23%   |
| Netac                       | 792       | 1080   | 0.22%   |
| KingSpec                    | 776       | 995    | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 3928      | 0.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 3073      | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2801      | 0.71%   |
| Seagate ST500DM002-1BD142 500GB                    | 2764      | 0.7%    |
| Samsung SSD 860 EVO 500GB                          | 2513      | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2390      | 0.6%    |
| Samsung SSD 850 EVO 250GB                          | 2313      | 0.59%   |
| Unknown MMC Card  32GB                             | 2251      | 0.57%   |
| Kingston SA400S37120G 120GB SSD                    | 2207      | 0.56%   |
| Kingston SA400S37480G 480GB SSD                    | 2147      | 0.54%   |
| Toshiba MQ01ABD100 1TB                             | 2096      | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                     | 2086      | 0.53%   |
| Unknown MMC Card  64GB                             | 1978      | 0.5%    |
| Samsung SSD 850 EVO 500GB                          | 1866      | 0.47%   |
| Toshiba MQ01ABF050 500GB                           | 1815      | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1772      | 0.45%   |
| Seagate ST500LT012-1DG142 500GB                    | 1733      | 0.44%   |
| Toshiba DT01ACA100 1TB                             | 1716      | 0.43%   |
| Kingston SV300S37A120G 120GB SSD                   | 1652      | 0.42%   |
| Crucial CT500MX500SSD1 500GB                       | 1591      | 0.4%    |
| Seagate ST2000DM008-2FR102 2TB                     | 1585      | 0.4%    |
| Samsung SSD 860 EVO 1TB                            | 1561      | 0.39%   |
| Unknown                                            | 1542      | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 1527      | 0.39%   |
| Toshiba MQ04ABF100 1TB                             | 1492      | 0.38%   |
| HGST HTS721010A9E630 1TB                           | 1461      | 0.37%   |
| Samsung SSD 860 EVO 250GB                          | 1412      | 0.36%   |
| Crucial CT240BX500SSD1 240GB                       | 1393      | 0.35%   |
| Crucial CT1000MX500SSD1 1TB                        | 1385      | 0.35%   |
| Seagate ST9500325AS 500GB                          | 1375      | 0.35%   |
| Seagate ST3500418AS 500GB                          | 1299      | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB                     | 1268      | 0.32%   |
| Samsung NVMe SSD Drive 512GB                       | 1250      | 0.32%   |
| Unknown SD/MMC/MS PRO 128GB                        | 1216      | 0.31%   |
| Unknown MMC Card  128GB                            | 1198      | 0.3%    |
| Samsung NVMe SSD Drive 500GB                       | 1157      | 0.29%   |
| Seagate ST1000DM003-1ER162 1TB                     | 1115      | 0.28%   |
| Toshiba DT01ACA050 500GB                           | 1108      | 0.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 1058      | 0.27%   |
| SanDisk NVMe SSD Drive 512GB                       | 1032      | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52541     | 83506  | 34.52%  |
| WDC                 | 45727     | 73441  | 30.04%  |
| Toshiba             | 18578     | 25818  | 12.2%   |
| Hitachi             | 12458     | 17162  | 8.18%   |
| Samsung Electronics | 7380      | 10621  | 4.85%   |
| HGST                | 6555      | 9768   | 4.31%   |
| Fujitsu             | 1824      | 2484   | 1.2%    |
| Maxtor              | 1606      | 2119   | 1.06%   |
| Unknown             | 1328      | 1843   | 0.87%   |
| Apple               | 798       | 950    | 0.52%   |
| JMicron Technology  | 704       | 875    | 0.46%   |
| SABRENT             | 457       | 558    | 0.3%    |
| Hewlett-Packard     | 411       | 969    | 0.27%   |
| TO Exter            | 226       | 281    | 0.15%   |
| ASMT                | 199       | 383    | 0.13%   |
| Intenso             | 157       | 227    | 0.1%    |
| IBM/Hitachi         | 91        | 108    | 0.06%   |
| ASMedia             | 80        | 110    | 0.05%   |
| ExcelStor           | 69        | 83     | 0.05%   |
| HGST HTS            | 64        | 76     | 0.04%   |
| WD MediaMax         | 58        | 90     | 0.04%   |
| LaCie               | 56        | 84     | 0.04%   |
| USB3.0              | 41        | 58     | 0.03%   |
| HPE                 | 41        | 90     | 0.03%   |
| Inateck             | 40        | 52     | 0.03%   |
| Unknown             | 37        | 45     | 0.02%   |
| USB                 | 36        | 45     | 0.02%   |
| KESU                | 28        | 38     | 0.02%   |
| SAGE                | 27        | 34     | 0.02%   |
| QUANTUM             | 26        | 28     | 0.02%   |
| StoreJet            | 25        | 26     | 0.02%   |
| MARVELL             | 23        | 31     | 0.02%   |
| Maxone              | 22        | 31     | 0.01%   |
| External            | 22        | 23     | 0.01%   |
| ASMT109x            | 21        | 31     | 0.01%   |
| Magnetic Data       | 17        | 19     | 0.01%   |
| Initio              | 17        | 18     | 0.01%   |
| MaxDigital          | 16        | 24     | 0.01%   |
| IBM                 | 16        | 22     | 0.01%   |
| MARSHAL             | 15        | 17     | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24234     | 36746  | 21.59%  |
| Kingston            | 15670     | 21497  | 13.96%  |
| Crucial             | 10512     | 15015  | 9.37%   |
| SanDisk             | 9939      | 13553  | 8.86%   |
| WDC                 | 6489      | 8844   | 5.78%   |
| A-DATA Technology   | 4048      | 5441   | 3.61%   |
| China               | 3408      | 4487   | 3.04%   |
| Intel               | 3116      | 4494   | 2.78%   |
| Micron Technology   | 2023      | 2729   | 1.8%    |
| SPCC                | 1931      | 2638   | 1.72%   |
| SK hynix            | 1791      | 2353   | 1.6%    |
| PNY                 | 1740      | 2408   | 1.55%   |
| Toshiba             | 1732      | 2331   | 1.54%   |
| OCZ                 | 1577      | 2046   | 1.41%   |
| Apple               | 1404      | 1652   | 1.25%   |
| Transcend           | 1322      | 1690   | 1.18%   |
| Patriot             | 1306      | 1774   | 1.16%   |
| Intenso             | 1179      | 1609   | 1.05%   |
| LITEON              | 1130      | 1408   | 1.01%   |
| GOODRAM             | 1006      | 1453   | 0.9%    |
| Apacer              | 833       | 1089   | 0.74%   |
| KingSpec            | 754       | 970    | 0.67%   |
| Corsair             | 749       | 1004   | 0.67%   |
| Team                | 708       | 936    | 0.63%   |
| LITEONIT            | 706       | 912    | 0.63%   |
| Plextor             | 662       | 944    | 0.59%   |
| Netac               | 636       | 886    | 0.57%   |
| Lexar               | 473       | 575    | 0.42%   |
| Unknown             | 464       | 547    | 0.41%   |
| Gigabyte Technology | 457       | 639    | 0.41%   |
| Hewlett-Packard     | 447       | 641    | 0.4%    |
| Seagate             | 356       | 504    | 0.32%   |
| ASMT                | 349       | 422    | 0.31%   |
| KingDian            | 320       | 450    | 0.29%   |
| Smartbuy            | 277       | 364    | 0.25%   |
| AMD                 | 268       | 343    | 0.24%   |
| Mushkin             | 238       | 346    | 0.21%   |
| Verbatim            | 227       | 318    | 0.2%    |
| Unknown             | 200       | 239    | 0.18%   |
| FORESEE             | 190       | 234    | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 128279    | 232940 | 40.45%  |
| SSD     | 97579     | 156389 | 30.77%  |
| NVMe    | 73014     | 110269 | 23.03%  |
| MMC     | 12890     | 17366  | 4.07%   |
| Unknown | 5329      | 8017   | 1.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 184288    | 374416 | 64.81%  |
| NVMe | 72898     | 109703 | 25.64%  |
| SAS  | 14293     | 23496  | 5.03%   |
| MMC  | 12890     | 17366  | 4.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 140900    | 232422 | 59.77%  |
| 0.51-1.0        | 64514     | 100017 | 27.37%  |
| 1.01-2.0        | 17187     | 28958  | 7.29%   |
| 3.01-4.0        | 5544      | 10884  | 2.35%   |
| 2.01-3.0        | 3482      | 6493   | 1.48%   |
| 4.01-10.0       | 3196      | 8049   | 1.36%   |
| 10.01-20.0      | 875       | 2450   | 0.37%   |
| More than 100.0 | 16        | 18     | 0.01%   |
| 20.01-50.0      | 12        | 21     | 0.01%   |
| 0               | 12        | 13     | 0.01%   |
| 50.01-100.0     | 1         | 4      | 0.0004% |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 66149     | 25%     |
| 251-500        | 57048     | 21.56%  |
| 501-1000       | 38662     | 14.61%  |
| 1-20           | 21662     | 8.19%   |
| 1001-2000      | 20307     | 7.68%   |
| 51-100         | 18139     | 6.86%   |
| More than 3000 | 12704     | 4.8%    |
| 21-50          | 11654     | 4.4%    |
| Unknown        | 10967     | 4.15%   |
| 2001-3000      | 7287      | 2.75%   |
| 0              | 4         | 0.002%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 109145    | 39.93%  |
| 21-50          | 44609     | 16.32%  |
| 101-250        | 31738     | 11.61%  |
| 51-100         | 28674     | 10.49%  |
| 251-500        | 19418     | 7.1%    |
| 501-1000       | 13811     | 5.05%   |
| Unknown        | 10967     | 4.01%   |
| 1001-2000      | 7738      | 2.83%   |
| More than 3000 | 4322      | 1.58%   |
| 2001-3000      | 2793      | 1.02%   |
| 0              | 102       | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 605       | 780    | 1.76%   |
| Seagate ST9500325AS 500GB           | 511       | 656    | 1.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 384       | 476    | 1.11%   |
| Seagate ST500LT012-9WS142 500GB     | 348       | 445    | 1.01%   |
| Seagate ST3500418AS 500GB           | 348       | 468    | 1.01%   |
| Seagate ST500LT012-1DG142 500GB     | 302       | 363    | 0.88%   |
| HGST HTS545050A7E680 500GB          | 282       | 374    | 0.82%   |
| Seagate ST9320325AS 320GB           | 256       | 322    | 0.74%   |
| Toshiba MQ01ABD100 1TB              | 236       | 287    | 0.68%   |
| Seagate ST1000LM035-1RK172 1TB      | 233       | 256    | 0.68%   |
| Kingston SV300S37A120G 120GB SSD    | 201       | 232    | 0.58%   |
| HGST HTS541010A9E680 1TB            | 198       | 255    | 0.57%   |
| Seagate ST9250315AS 250GB           | 195       | 245    | 0.57%   |
| Seagate ST31000528AS 1TB            | 187       | 234    | 0.54%   |
| HGST HTS721010A9E630 1TB            | 186       | 224    | 0.54%   |
| WDC WD5000AAKX-001CA0 500GB         | 180       | 227    | 0.52%   |
| Toshiba MQ01ABF050 500GB            | 179       | 239    | 0.52%   |
| HGST HTS725050A7E630 500GB          | 169       | 210    | 0.49%   |
| HGST HTS545050A7E380 500GB          | 164       | 227    | 0.48%   |
| Seagate ST3250410AS 250GB           | 159       | 203    | 0.46%   |
| Seagate ST3250310AS 250GB           | 151       | 218    | 0.44%   |
| Hitachi HTS543232A7A384 320GB       | 151       | 178    | 0.44%   |
| Seagate ST31000524AS 1TB            | 144       | 187    | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB      | 144       | 199    | 0.42%   |
| Seagate ST1000DM003-9YN162 1TB      | 135       | 164    | 0.39%   |
| Toshiba MQ01ABD050 500GB            | 131       | 158    | 0.38%   |
| SanDisk SSD U100 256GB              | 129       | 130    | 0.37%   |
| Seagate ST9500420AS 500GB           | 128       | 165    | 0.37%   |
| Hitachi HTS545050A7E380 500GB       | 128       | 157    | 0.37%   |
| Seagate ST320LT020-9YG142 320GB     | 126       | 178    | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 125       | 151    | 0.36%   |
| WDC WD10EARS-00Y5B1 1TB             | 123       | 180    | 0.36%   |
| Toshiba DT01ACA100 1TB              | 123       | 171    | 0.36%   |
| Hitachi HTS545050B9A300 500GB       | 123       | 159    | 0.36%   |
| Hitachi HTS547575A9E384 752GB       | 121       | 152    | 0.35%   |
| Seagate ST3320613AS 320GB           | 116       | 155    | 0.34%   |
| Seagate ST500LM021-1KJ152 500GB     | 115       | 138    | 0.33%   |
| Toshiba DT01ACA050 500GB            | 114       | 143    | 0.33%   |
| Hitachi HTS547550A9E384 500GB       | 114       | 157    | 0.33%   |
| Seagate ST3500413AS 500GB           | 112       | 130    | 0.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9666      | 12993  | 29.11%  |
| WDC                 | 7418      | 10083  | 22.34%  |
| Hitachi             | 3378      | 4307   | 10.17%  |
| Samsung Electronics | 2613      | 3503   | 7.87%   |
| Toshiba             | 2587      | 3235   | 7.79%   |
| HGST                | 1240      | 1617   | 3.73%   |
| Kingston            | 800       | 980    | 2.41%   |
| SanDisk             | 653       | 748    | 1.97%   |
| Maxtor              | 548       | 685    | 1.65%   |
| Intel               | 543       | 779    | 1.64%   |
| Crucial             | 441       | 574    | 1.33%   |
| SK hynix            | 394       | 470    | 1.19%   |
| A-DATA Technology   | 335       | 428    | 1.01%   |
| Fujitsu             | 313       | 385    | 0.94%   |
| Micron Technology   | 210       | 272    | 0.63%   |
| OCZ                 | 178       | 229    | 0.54%   |
| China               | 167       | 194    | 0.5%    |
| SPCC                | 121       | 143    | 0.36%   |
| Corsair             | 106       | 149    | 0.32%   |
| Apple               | 104       | 122    | 0.31%   |
| LITEON              | 84        | 96     | 0.25%   |
| KingSpec            | 61        | 77     | 0.18%   |
| LITEONIT            | 58        | 74     | 0.17%   |
| Hewlett-Packard     | 58        | 70     | 0.17%   |
| Unknown             | 46        | 52     | 0.14%   |
| Netac               | 45        | 49     | 0.14%   |
| IBM/Hitachi         | 44        | 53     | 0.13%   |
| Intenso             | 43        | 54     | 0.13%   |
| Transcend           | 41        | 56     | 0.12%   |
| Plextor             | 39        | 59     | 0.12%   |
| Kingmax             | 39        | 68     | 0.12%   |
| ASMT                | 39        | 55     | 0.12%   |
| Patriot             | 34        | 37     | 0.1%    |
| Apacer              | 32        | 41     | 0.1%    |
| AMD                 | 25        | 30     | 0.08%   |
| SSSTC               | 24        | 28     | 0.07%   |
| Unknown             | 22        | 27     | 0.07%   |
| Mushkin             | 22        | 22     | 0.07%   |
| PNY                 | 20        | 35     | 0.06%   |
| ExcelStor           | 18        | 20     | 0.05%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9664      | 12989  | 35.86%  |
| WDC                 | 7126      | 9726   | 26.44%  |
| Hitachi             | 3378      | 4307   | 12.53%  |
| Toshiba             | 2505      | 3136   | 9.29%   |
| Samsung Electronics | 1858      | 2505   | 6.89%   |
| HGST                | 1240      | 1617   | 4.6%    |
| Maxtor              | 548       | 685    | 2.03%   |
| Fujitsu             | 312       | 384    | 1.16%   |
| Apple               | 71        | 79     | 0.26%   |
| IBM/Hitachi         | 44        | 53     | 0.16%   |
| Hewlett-Packard     | 32        | 40     | 0.12%   |
| ASMT                | 22        | 33     | 0.08%   |
| ExcelStor           | 18        | 20     | 0.07%   |
| WD MediaMax         | 16        | 21     | 0.06%   |
| Unknown             | 13        | 18     | 0.05%   |
| IBM                 | 12        | 14     | 0.04%   |
| JMicron Technology  | 11        | 12     | 0.04%   |
| ASMedia             | 9         | 14     | 0.03%   |
| Unknown             | 8         | 10     | 0.03%   |
| HGST HTS            | 7         | 9      | 0.03%   |
| MARSHAL             | 6         | 7      | 0.02%   |
| QUANTUM             | 5         | 5      | 0.02%   |
| SABRENT             | 4         | 4      | 0.01%   |
| Initio              | 4         | 5      | 0.01%   |
| Inateck             | 4         | 4      | 0.01%   |
| HPE                 | 4         | 6      | 0.01%   |
| SAGE                | 3         | 3      | 0.01%   |
| MDT                 | 3         | 3      | 0.01%   |
| Magnetic Data       | 3         | 3      | 0.01%   |
| TO Exter            | 2         | 2      | 0.01%   |
| MaxDigital          | 2         | 2      | 0.01%   |
| LaCie               | 2         | 2      | 0.01%   |
| Intenso             | 2         | 2      | 0.01%   |
| ICY BOX             | 2         | 3      | 0.01%   |
| CSD                 | 2         | 3      | 0.01%   |
| USB3.0              | 1         | 1      | 0.004%  |
| TPH00100500GB       | 1         | 1      | 0.004%  |
| StoreJet            | 1         | 1      | 0.004%  |
| RSH-339             | 1         | 1      | 0.004%  |
| RSH-319             | 1         | 1      | 0.004%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 24865     | 35740  | 80.06%  |
| SSD     | 5377      | 6897   | 17.31%  |
| NVMe    | 811       | 1020   | 2.61%   |
| Unknown | 6         | 7      | 0.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB          | 21        | 25     | 2.37%   |
| Seagate ST31000528AS 1TB           | 19        | 23     | 2.15%   |
| Samsung Electronics HD502HJ 500GB  | 12        | 17     | 1.36%   |
| Seagate ST500DM002-1BD142 500GB    | 10        | 11     | 1.13%   |
| Samsung Electronics SSD 980 1TB    | 10        | 11     | 1.13%   |
| Hitachi HDS721010DLE630 1TB        | 10        | 23     | 1.13%   |
| Seagate ST9320325AS 320GB          | 9         | 10     | 1.02%   |
| Seagate ST500LT012-1DG142 500GB    | 9         | 11     | 1.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 9         | 9      | 1.02%   |
| Samsung Electronics HM321HI 320GB  | 9         | 11     | 1.02%   |
| Samsung Electronics HD103SJ 1TB    | 9         | 11     | 1.02%   |
| Seagate ST9500325AS 500GB          | 8         | 10     | 0.9%    |
| Seagate ST31000524AS 1TB           | 8         | 10     | 0.9%    |
| Samsung Electronics SSD 980 500GB  | 8         | 9      | 0.9%    |
| HGST HTS721010A9E630 1TB           | 8         | 9      | 0.9%    |
| HGST HTS545050A7E680 500GB         | 8         | 8      | 0.9%    |
| Apple HDD HTS541010A9E662 1TB      | 8         | 8      | 0.9%    |
| Seagate ST3250318AS 250GB          | 7         | 11     | 0.79%   |
| Hitachi HTS545050A7E380 500GB      | 7         | 8      | 0.79%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 6         | 7      | 0.68%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 6         | 7      | 0.68%   |
| Toshiba MQ01ABD050 500GB           | 6         | 6      | 0.68%   |
| Toshiba MK3265GSX 320GB            | 6         | 6      | 0.68%   |
| Toshiba DT01ACA100 1TB             | 6         | 7      | 0.68%   |
| Seagate ST3500412AS 500GB          | 6         | 8      | 0.68%   |
| Seagate ST3500410AS 500GB          | 6         | 8      | 0.68%   |
| Samsung Electronics HD502IJ 500GB  | 6         | 6      | 0.68%   |
| Samsung Electronics HD252HJ 250GB  | 6         | 10     | 0.68%   |
| Hitachi HTS547550A9E384 500GB      | 6         | 7      | 0.68%   |
| HGST HTS545050A7E380 500GB         | 6         | 6      | 0.68%   |
| HGST HTS541010A9E680 1TB           | 6         | 7      | 0.68%   |
| Toshiba MQ01ABD100 1TB             | 5         | 5      | 0.56%   |
| Toshiba MK6465GSX 640GB            | 5         | 7      | 0.56%   |
| Seagate ST3320613AS 320GB          | 5         | 6      | 0.56%   |
| Seagate ST31500341AS 1TB           | 5         | 7      | 0.56%   |
| Samsung Electronics HD322GJ 320GB  | 5         | 6      | 0.56%   |
| Hitachi HDS721010CLA332 1TB        | 5         | 5      | 0.56%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 4         | 10     | 0.45%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 4         | 4      | 0.45%   |
| Toshiba MK5065GSX 500GB            | 4         | 4      | 0.45%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 219       | 266    | 24.89%  |
| WDC                     | 201       | 238    | 22.84%  |
| Samsung Electronics     | 157       | 190    | 17.84%  |
| Toshiba                 | 99        | 111    | 11.25%  |
| Hitachi                 | 71        | 88     | 8.07%   |
| HGST                    | 38        | 42     | 4.32%   |
| Maxtor                  | 13        | 13     | 1.48%   |
| Intel                   | 11        | 14     | 1.25%   |
| Apple                   | 11        | 13     | 1.25%   |
| SK hynix                | 9         | 9      | 1.02%   |
| Crucial                 | 6         | 6      | 0.68%   |
| Kingston                | 4         | 4      | 0.45%   |
| Hewlett-Packard         | 4         | 8      | 0.45%   |
| Fujitsu                 | 4         | 8      | 0.45%   |
| Sandisk                 | 3         | 3      | 0.34%   |
| JMicron Technology      | 3         | 4      | 0.34%   |
| Transcend               | 2         | 2      | 0.23%   |
| Mushkin                 | 2         | 2      | 0.23%   |
| Intenso                 | 2         | 2      | 0.23%   |
| A-DATA Technology       | 2         | 2      | 0.23%   |
| Zheino                  | 1         | 1      | 0.11%   |
| Unknown                 | 1         | 1      | 0.11%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.11%   |
| TPH00800640GB           | 1         | 1      | 0.11%   |
| SPCC                    | 1         | 1      | 0.11%   |
| Phison                  | 1         | 1      | 0.11%   |
| Patriot                 | 1         | 2      | 0.11%   |
| OCZ-AGIL                | 1         | 1      | 0.11%   |
| OCZ                     | 1         | 1      | 0.11%   |
| Micron Technology       | 1         | 1      | 0.11%   |
| LITEON                  | 1         | 2      | 0.11%   |
| KingDian                | 1         | 4      | 0.11%   |
| Inland                  | 1         | 1      | 0.11%   |
| IBM-ESXS                | 1         | 2      | 0.11%   |
| GOODRAM                 | 1         | 1      | 0.11%   |
| External                | 1         | 1      | 0.11%   |
| ExcelStor               | 1         | 1      | 0.11%   |
| Corsair                 | 1         | 1      | 0.11%   |
| Acer                    | 1         | 1      | 0.11%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 132344    | 272815 | 49.07%  |
| Works    | 106272    | 207438 | 39.41%  |
| Malfunc  | 30184     | 43664  | 11.19%  |
| Failed   | 872       | 1050   | 0.32%   |
| Limited  | 9         | 9      | 0.003%  |
| Fixed    | 5         | 5      | 0.002%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 159415    | 52.29%  |
| AMD                              | 47686     | 15.64%  |
| Samsung Electronics              | 25353     | 8.32%   |
| SanDisk                          | 11720     | 3.84%   |
| SK hynix                         | 6163      | 2.02%   |
| Nvidia                           | 5461      | 1.79%   |
| Kingston Technology Company      | 4983      | 1.63%   |
| Phison Electronics               | 4981      | 1.63%   |
| ASMedia Technology               | 4715      | 1.55%   |
| JMicron Technology               | 3799      | 1.25%   |
| Marvell Technology Group         | 3508      | 1.15%   |
| Micron Technology                | 3317      | 1.09%   |
| Toshiba America Info Systems     | 3173      | 1.04%   |
| Micron/Crucial Technology        | 2906      | 0.95%   |
| KIOXIA                           | 2412      | 0.79%   |
| Silicon Motion                   | 2405      | 0.79%   |
| ADATA Technology                 | 1948      | 0.64%   |
| VIA Technologies                 | 1072      | 0.35%   |
| Realtek Semiconductor            | 1019      | 0.33%   |
| LSI Logic / Symbios Logic        | 920       | 0.3%    |
| Broadcom / LSI                   | 787       | 0.26%   |
| MAXIO Technology (Hangzhou)      | 775       | 0.25%   |
| Silicon Integrated Systems [SiS] | 616       | 0.2%    |
| Union Memory (Shenzhen)          | 597       | 0.2%    |
| Solid State Storage Technology   | 572       | 0.19%   |
| Apple                            | 551       | 0.18%   |
| Silicon Image                    | 397       | 0.13%   |
| Shenzhen Longsys Electronics     | 393       | 0.13%   |
| Lite-On Technology               | 368       | 0.12%   |
| Seagate Technology               | 350       | 0.11%   |
| Hewlett-Packard                  | 306       | 0.1%    |
| Adaptec                          | 276       | 0.09%   |
| O2 Micro                         | 214       | 0.07%   |
| Lenovo                           | 210       | 0.07%   |
| INNOGRIT                         | 210       | 0.07%   |
| Yangtze Memory Technologies      | 173       | 0.06%   |
| Integrated Technology Express    | 130       | 0.04%   |
| Solidigm                         | 116       | 0.04%   |
| Biwin Storage Technology         | 110       | 0.04%   |
| Netac Technology                 | 107       | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 29431     | 8.22%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 11975     | 3.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 11279     | 3.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10878     | 3.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10257     | 2.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7820      | 2.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7731      | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 6157      | 1.72%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5966      | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5910      | 1.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5859      | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5445      | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5264      | 1.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5258      | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 5114      | 1.43%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4966      | 1.39%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4933      | 1.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4705      | 1.31%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 4301      | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 4090      | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3993      | 1.12%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3989      | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 3928      | 1.1%    |
| Intel SATA Controller [RAID mode]                                                       | 3913      | 1.09%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3753      | 1.05%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3700      | 1.03%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3540      | 0.99%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3255      | 0.91%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 3094      | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3047      | 0.85%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2942      | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2920      | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2859      | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 2710      | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2661      | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2654      | 0.74%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2583      | 0.72%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2510      | 0.7%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2407      | 0.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2360      | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 173082    | 56.12%  |
| NVMe | 73399     | 23.8%   |
| IDE  | 40385     | 13.09%  |
| RAID | 19883     | 6.45%   |
| SAS  | 1187      | 0.38%   |
| SCSI | 504       | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 180780    | 74.12%  |
| AMD                      | 60671     | 24.87%  |
| ARM                      | 2089      | 0.86%   |
| Unknown                  | 102       | 0.04%   |
| Qualcomm                 | 85        | 0.03%   |
| CentaurHauls             | 78        | 0.03%   |
| Phytium                  | 25        | 0.01%   |
| sifive,u74-mc            | 15        | 0.01%   |
| Loongson                 | 7         | 0.003%  |
| HiSilicon                | 6         | 0.002%  |
| thead,c906               | 5         | 0.002%  |
| Marvell Semiconductor    | 5         | 0.002%  |
| CHRP IBM,8233-E8B        | 5         | 0.002%  |
| sifive,bullet0           | 3         | 0.001%  |
| PowerNV C1P9S01 REV 1.01 | 3         | 0.001%  |
| MIPS                     | 3         | 0.001%  |
| PowerBook5,6             | 2         | 0.001%  |
| Elbrus-MCST              | 2         | 0.001%  |
| CHRP IBM,9131-52A        | 2         | 0.001%  |
| Vortex86 SoC             | 1         | 0.0004% |
| PowerNV FP5466G2         | 1         | 0.0004% |
| PowerNV C829UAG3         | 1         | 0.0004% |
| PowerMac8,1              | 1         | 0.0004% |
| PowerMac7,2              | 1         | 0.0004% |
| PowerMac3,6              | 1         | 0.0004% |
| PowerMac11,2             | 1         | 0.0004% |
| PowerMac10,2             | 1         | 0.0004% |
| PowerBook6,7             | 1         | 0.0004% |
| PowerBook5,5             | 1         | 0.0004% |
| PowerBook5,4             | 1         | 0.0004% |
| PowerBook3,5             | 1         | 0.0004% |
| PowerBook3,4             | 1         | 0.0004% |
| MBE8C-PC                 | 1         | 0.0004% |
| iSH                      | 1         | 0.0004% |
| IBM/S390                 | 1         | 0.0004% |
| HUAWEI                   | 1         | 0.0004% |
| GenuineTMx86             | 1         | 0.0004% |
| FSP-1                    | 1         | 0.0004% |
| EL2S4                    | 1         | 0.0004% |
| E8C/EATX                 | 1         | 0.0004% |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 2303      | 0.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2101      | 0.86%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2038      | 0.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2009      | 0.82%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1939      | 0.79%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1722      | 0.7%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1530      | 0.62%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1523      | 0.62%   |
| ARM Processor                                 | 1505      | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1404      | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1387      | 0.57%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1351      | 0.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1344      | 0.55%   |
| AMD Custom APU 0405                           | 1342      | 0.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1321      | 0.54%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1318      | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1265      | 0.52%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1244      | 0.51%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1237      | 0.5%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1204      | 0.49%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1149      | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1119      | 0.46%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1115      | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1105      | 0.45%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1073      | 0.44%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1070      | 0.44%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1042      | 0.43%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 1024      | 0.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 1022      | 0.42%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 1007      | 0.41%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 937       | 0.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 924       | 0.38%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 921       | 0.38%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 909       | 0.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 890       | 0.36%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 871       | 0.36%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 855       | 0.35%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 849       | 0.35%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 833       | 0.34%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 832       | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 49577     | 20.27%  |
| Intel Core i7           | 39625     | 16.2%   |
| Intel Core i3           | 19161     | 7.83%   |
| Other                   | 18747     | 7.66%   |
| AMD Ryzen 5             | 13557     | 5.54%   |
| Intel Celeron           | 12555     | 5.13%   |
| Intel Core 2 Duo        | 11153     | 4.56%   |
| AMD Ryzen 7             | 10742     | 4.39%   |
| Intel Pentium           | 7082      | 2.9%    |
| Intel Xeon              | 6294      | 2.57%   |
| Intel Atom              | 4891      | 2%      |
| AMD FX                  | 3901      | 1.59%   |
| AMD Ryzen 9             | 3772      | 1.54%   |
| Intel Pentium Dual-Core | 3335      | 1.36%   |
| AMD Ryzen 3             | 2622      | 1.07%   |
| Intel Core 2 Quad       | 2338      | 0.96%   |
| AMD A6                  | 2032      | 0.83%   |
| AMD A8                  | 1984      | 0.81%   |
| AMD A10                 | 1685      | 0.69%   |
| Intel Core 2            | 1647      | 0.67%   |
| AMD A4                  | 1617      | 0.66%   |
| AMD Athlon 64 X2        | 1591      | 0.65%   |
| Intel Pentium Dual      | 1541      | 0.63%   |
| AMD Athlon II X2        | 1436      | 0.59%   |
| Intel Core i9           | 1390      | 0.57%   |
| AMD Phenom II X4        | 1345      | 0.55%   |
| Intel Pentium 4         | 1046      | 0.43%   |
| AMD E                   | 999       | 0.41%   |
| AMD Ryzen 7 PRO         | 971       | 0.4%    |
| Intel Genuine           | 929       | 0.38%   |
| Intel Pentium Silver    | 862       | 0.35%   |
| AMD Athlon              | 845       | 0.35%   |
| AMD E1                  | 838       | 0.34%   |
| AMD Athlon II X4        | 658       | 0.27%   |
| AMD E2                  | 648       | 0.26%   |
| AMD Ryzen 5 PRO         | 634       | 0.26%   |
| AMD Ryzen Threadripper  | 545       | 0.22%   |
| AMD Phenom II X6        | 517       | 0.21%   |
| Intel Pentium D         | 485       | 0.2%    |
| AMD Sempron             | 408       | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 99994     | 40.77%  |
| 4       | 82783     | 33.75%  |
| 6       | 22352     | 9.11%   |
| 8       | 17156     | 7%      |
| 1       | 7196      | 2.93%   |
| 12      | 4237      | 1.73%   |
| Unknown | 2254      | 0.92%   |
| 16      | 2185      | 0.89%   |
| 10      | 2102      | 0.86%   |
| 3       | 1756      | 0.72%   |
| 14      | 1582      | 0.65%   |
| 24      | 633       | 0.26%   |
| 20      | 275       | 0.11%   |
| 32      | 204       | 0.08%   |
| 28      | 131       | 0.05%   |
| 18      | 78        | 0.03%   |
| 64      | 76        | 0.03%   |
| 40      | 61        | 0.02%   |
| 36      | 38        | 0.02%   |
| 5       | 37        | 0.02%   |
| 48      | 35        | 0.01%   |
| 44      | 17        | 0.01%   |
| 128     | 16        | 0.01%   |
| 22      | 11        | 0.004%  |
| 56      | 10        | 0.004%  |
| 96      | 9         | 0.004%  |
| 52      | 5         | 0.002%  |
| 80      | 4         | 0.002%  |
| 192     | 3         | 0.001%  |
| 26      | 3         | 0.001%  |
| 104     | 2         | 0.001%  |
| 7       | 2         | 0.001%  |
| 384     | 1         | 0.0004% |
| 120     | 1         | 0.0004% |
| 115     | 1         | 0.0004% |
| 72      | 1         | 0.0004% |
| 68      | 1         | 0.0004% |
| 15      | 1         | 0.0004% |
| 11      | 1         | 0.0004% |
| 9       | 1         | 0.0004% |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 240694    | 98.64%  |
| 2       | 2670      | 1.09%   |
| Unknown | 520       | 0.21%   |
| 4       | 77        | 0.03%   |
| 3       | 38        | 0.02%   |
| 8       | 4         | 0.002%  |
| 0       | 4         | 0.002%  |
| 16      | 2         | 0.001%  |
| 6       | 2         | 0.001%  |
| 14      | 1         | 0.0004% |
| 11      | 1         | 0.0004% |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 155159    | 63.3%   |
| 1       | 87603     | 35.74%  |
| Unknown | 2253      | 0.92%   |
| 4       | 56        | 0.02%   |
| 8       | 31        | 0.01%   |
| 12      | 6         | 0.002%  |
| 16      | 2         | 0.001%  |
| 6       | 2         | 0.001%  |
| 112     | 1         | 0.0004% |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 236735    | 96.74%  |
| Unknown        | 4973      | 2.03%   |
| 32-bit         | 2554      | 1.04%   |
| 64-bit         | 453       | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 75370     | 29.55%  |
| 0x206a7    | 13545     | 5.31%   |
| 0x306a9    | 12818     | 5.03%   |
| 0x306c3    | 9397      | 3.68%   |
| 0x1067a    | 9304      | 3.65%   |
| 0x906ea    | 5087      | 1.99%   |
| 0x806ea    | 4441      | 1.74%   |
| 0x40651    | 4215      | 1.65%   |
| 0x806ec    | 4207      | 1.65%   |
| 0x506e3    | 4034      | 1.58%   |
| 0x20655    | 3896      | 1.53%   |
| 0x806c1    | 3863      | 1.51%   |
| 0x806e9    | 3816      | 1.5%    |
| 0x406e3    | 3723      | 1.46%   |
| 0x906e9    | 3513      | 1.38%   |
| 0x306d4    | 3296      | 1.29%   |
| 0x6fd      | 3291      | 1.29%   |
| 0x010000c8 | 2646      | 1.04%   |
| 0x08701021 | 2582      | 1.01%   |
| 0x08108109 | 2454      | 0.96%   |
| 0x10676    | 2360      | 0.93%   |
| 0x30678    | 2343      | 0.92%   |
| 0x0a50000c | 2083      | 0.82%   |
| 0x406c4    | 2021      | 0.79%   |
| 0x06001119 | 1945      | 0.76%   |
| 0x0800820d | 1844      | 0.72%   |
| 0x06000852 | 1747      | 0.68%   |
| 0x6fb      | 1632      | 0.64%   |
| 0x20652    | 1622      | 0.64%   |
| 0x08600106 | 1542      | 0.6%    |
| 0x706e5    | 1458      | 0.57%   |
| 0xa0652    | 1368      | 0.54%   |
| 0x706a1    | 1309      | 0.51%   |
| 0x08108102 | 1304      | 0.51%   |
| 0x506c9    | 1231      | 0.48%   |
| 0x106ca    | 1219      | 0.48%   |
| 0x08608103 | 1207      | 0.47%   |
| 0x906ed    | 1197      | 0.47%   |
| 0x106e5    | 1195      | 0.47%   |
| 0x08701013 | 1153      | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 34325     | 14.02%  |
| Haswell           | 19977     | 8.16%   |
| SandyBridge       | 18056     | 7.38%   |
| IvyBridge         | 17603     | 7.19%   |
| Penryn            | 14283     | 5.84%   |
| Unknown           | 12280     | 5.02%   |
| Skylake           | 12007     | 4.91%   |
| Zen 2             | 9396      | 3.84%   |
| Core              | 8491      | 3.47%   |
| Westmere          | 7776      | 3.18%   |
| Zen 3             | 7775      | 3.18%   |
| Zen+              | 7473      | 3.05%   |
| Silvermont        | 7249      | 2.96%   |
| TigerLake         | 6310      | 2.58%   |
| K10               | 6155      | 2.51%   |
| Piledriver        | 5551      | 2.27%   |
| Broadwell         | 5318      | 2.17%   |
| CometLake         | 4836      | 1.98%   |
| Zen               | 4339      | 1.77%   |
| Alderlake Hybrid  | 4320      | 1.76%   |
| IceLake           | 3584      | 1.46%   |
| Goldmont plus     | 3418      | 1.4%    |
| K8 Hammer         | 2968      | 1.21%   |
| Excavator         | 2858      | 1.17%   |
| Bonnell           | 2487      | 1.02%   |
| Nehalem           | 2383      | 0.97%   |
| Bobcat            | 1936      | 0.79%   |
| NetBurst          | 1877      | 0.77%   |
| Goldmont          | 1790      | 0.73%   |
| Puma              | 1536      | 0.63%   |
| P6                | 1154      | 0.47%   |
| Jaguar            | 1093      | 0.45%   |
| Steamroller       | 1067      | 0.44%   |
| K10 Llano         | 1062      | 0.43%   |
| Bulldozer         | 804       | 0.33%   |
| Tremont           | 552       | 0.23%   |
| K8 & K10 hybrid   | 418       | 0.17%   |
| Gracemont         | 158       | 0.06%   |
| K6                | 67        | 0.03%   |
| Meteorlake Hybrid | 34        | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 135576    | 47.55%  |
| Nvidia                                       | 79438     | 27.86%  |
| AMD                                          | 66889     | 23.46%  |
| Matrox Electronics Systems                   | 1341      | 0.47%   |
| ASPEED Technology                            | 952       | 0.33%   |
| Silicon Integrated Systems [SiS]             | 383       | 0.13%   |
| VIA Technologies                             | 269       | 0.09%   |
| ATI Technologies                             | 85        | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 36        | 0.01%   |
| S3 Graphics                                  | 27        | 0.01%   |
| Zhaoxin                                      | 22        | 0.01%   |
| Huawei Technologies                          | 22        | 0.01%   |
| Silicon Motion                               | 15        | 0.01%   |
| Loongson Technology                          | 9         | 0.003%  |
| Red Hat                                      | 6         | 0.002%  |
| Neomagic                                     | 5         | 0.002%  |
| NVidia / SGS Thomson (Joint Venture)         | 4         | 0.001%  |
| Phytium Technology                           | 3         | 0.001%  |
| Trident Microsystems                         | 2         | 0.001%  |
| Jingjia Microelectronics                     | 2         | 0.001%  |
| Conexant Systems                             | 2         | 0.001%  |
| Nanjing Ruixinview Technology                | 1         | 0.0004% |
| Moore Threads Technology                     | 1         | 0.0004% |
| Dome Imaging Systems                         | 1         | 0.0004% |
| Cirrus Logic                                 | 1         | 0.0004% |
| Alliance Semiconductor                       | 1         | 0.0004% |
| 3DLabs                                       | 1         | 0.0004% |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13077     | 4.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9734      | 3.29%   |
| Intel UHD Graphics 620                                                                   | 5759      | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5678      | 1.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5485      | 1.86%   |
| Intel HD Graphics 620                                                                    | 4848      | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4673      | 1.58%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4650      | 1.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4507      | 1.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 4460      | 1.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4252      | 1.44%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4021      | 1.36%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3955      | 1.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3863      | 1.31%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3855      | 1.3%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3775      | 1.28%   |
| Intel HD Graphics 5500                                                                   | 3626      | 1.23%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3410      | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3396      | 1.15%   |
| Intel HD Graphics 530                                                                    | 3384      | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3348      | 1.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3216      | 1.09%   |
| Intel HD Graphics 630                                                                    | 3083      | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2767      | 0.94%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2571      | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2334      | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2289      | 0.77%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2145      | 0.73%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2134      | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2046      | 0.69%   |
| AMD Lucienne                                                                             | 2009      | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1944      | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1940      | 0.66%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1940      | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1919      | 0.65%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 1658      | 0.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1656      | 0.56%   |
| Nvidia GT218 [GeForce 210]                                                               | 1567      | 0.53%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1528      | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1484      | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 97814     | 39.69%  |
| 1 x AMD                  | 52124     | 21.15%  |
| 1 x Nvidia               | 46006     | 18.67%  |
| Intel + Nvidia           | 28487     | 11.56%  |
| Intel + AMD              | 6245      | 2.53%   |
| 2 x AMD                  | 4532      | 1.84%   |
| AMD + Nvidia             | 4031      | 1.64%   |
| Other                    | 2558      | 1.04%   |
| 1 x Matrox               | 1152      | 0.47%   |
| 1 x ASPEED               | 699       | 0.28%   |
| 2 x Intel                | 682       | 0.28%   |
| 2 x Nvidia               | 624       | 0.25%   |
| 1 x SiS                  | 382       | 0.16%   |
| 1 x VIA                  | 266       | 0.11%   |
| Nvidia + ASPEED          | 177       | 0.07%   |
| Nvidia + Matrox          | 136       | 0.06%   |
| AMD + ASPEED             | 59        | 0.02%   |
| Intel + 2 x Nvidia       | 49        | 0.02%   |
| AMD + Matrox             | 49        | 0.02%   |
| 1 x XGI                  | 27        | 0.01%   |
| Intel + AMD + 1 x Nvidia | 27        | 0.01%   |
| 3 x AMD                  | 23        | 0.01%   |
| 1 x S3 Graphics          | 23        | 0.01%   |
| 1 x Zhaoxin              | 21        | 0.01%   |
| 1 x Huawei Technologies  | 21        | 0.01%   |
| Intel + 2 x AMD          | 19        | 0.01%   |
| AMD + 2 x Nvidia         | 19        | 0.01%   |
| 2 x AMD + 1 x Nvidia     | 16        | 0.01%   |
| 3 x Nvidia               | 13        | 0.01%   |
| 2 x Nvidia + 1 x ASPEED  | 13        | 0.01%   |
| 1 x Silicon Motion       | 12        | 0.005%  |
| 2 x Nvidia + 1 x Matrox  | 7         | 0.003%  |
| 1 x Red Hat              | 6         | 0.002%  |
| Nvidia + XGI             | 5         | 0.002%  |
| 1 x Neomagic             | 5         | 0.002%  |
| 1 x Loongson Technology  | 5         | 0.002%  |
| 1 x Intel + 3 x Nvidia   | 5         | 0.002%  |
| Intel + ASPEED           | 5         | 0.002%  |
| AMD + XGI                | 4         | 0.002%  |
| 4 x Nvidia               | 3         | 0.001%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 196196    | 78.71%  |
| Proprietary | 40211     | 16.13%  |
| Unknown     | 12846     | 5.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 137363    | 54.24%  |
| 1.01-2.0       | 32508     | 12.84%  |
| 0.01-0.5       | 31169     | 12.31%  |
| 0.51-1.0       | 19077     | 7.53%   |
| 3.01-4.0       | 14597     | 5.76%   |
| 7.01-8.0       | 8761      | 3.46%   |
| 5.01-6.0       | 4604      | 1.82%   |
| 8.01-16.0      | 3028      | 1.2%    |
| 2.01-3.0       | 1507      | 0.6%    |
| 16.01-24.0     | 526       | 0.21%   |
| 4.01-5.0       | 77        | 0.03%   |
| 32.01-64.0     | 13        | 0.01%   |
| 24.01-32.0     | 10        | 0.004%  |
| 0              | 3         | 0.001%  |
| More than 64.0 | 1         | 0.0004% |
| 6.01-7.0       | 1         | 0.0004% |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 34758     | 13.33%  |
| AU Optronics            | 29167     | 11.19%  |
| LG Display              | 21797     | 8.36%   |
| BOE                     | 20341     | 7.8%    |
| Chimei Innolux          | 19716     | 7.56%   |
| Goldstar                | 14784     | 5.67%   |
| Dell                    | 14402     | 5.52%   |
| Acer                    | 9465      | 3.63%   |
| Hewlett-Packard         | 8595      | 3.3%    |
| AOC                     | 6286      | 2.41%   |
| BenQ                    | 6201      | 2.38%   |
| Philips                 | 5997      | 2.3%    |
| Ancor Communications    | 5376      | 2.06%   |
| Apple                   | 5255      | 2.02%   |
| Lenovo                  | 4709      | 1.81%   |
| Chi Mei Optoelectronics | 4263      | 1.64%   |
| Sharp                   | 4097      | 1.57%   |
| ViewSonic               | 3026      | 1.16%   |
| Iiyama                  | 2397      | 0.92%   |
| PANDA                   | 2206      | 0.85%   |
| ASUSTek Computer        | 2153      | 0.83%   |
| Sony                    | 1941      | 0.74%   |
| InfoVision              | 1800      | 0.69%   |
| LG Philips              | 1541      | 0.59%   |
| Unknown                 | 1492      | 0.57%   |
| LG Electronics          | 1294      | 0.5%    |
| HannStar                | 1184      | 0.45%   |
| NEC Computers           | 1143      | 0.44%   |
| Valve                   | 1077      | 0.41%   |
| Eizo                    | 948       | 0.36%   |
| CSO                     | 857       | 0.33%   |
| Fujitsu Siemens         | 851       | 0.33%   |
| Panasonic               | 842       | 0.32%   |
| MSI                     | 827       | 0.32%   |
| Toshiba                 | 763       | 0.29%   |
| Vizio                   | 720       | 0.28%   |
| CPT                     | 714       | 0.27%   |
| Sceptre Tech            | 621       | 0.24%   |
| Gigabyte Technology     | 458       | 0.18%   |
| Medion                  | 427       | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1132      | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 1088      | 0.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 1040      | 0.39%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 1026      | 0.38%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 966       | 0.36%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 947       | 0.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 924       | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 916       | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 898       | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 751       | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 692       | 0.26%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 690       | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 690       | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 566       | 0.21%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 556       | 0.21%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 548       | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 527       | 0.2%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 515       | 0.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 471       | 0.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 465       | 0.17%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 459       | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 458       | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 453       | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 441       | 0.16%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 417       | 0.15%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 415       | 0.15%   |
| Unknown                                                                  | 413       | 0.15%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 404       | 0.15%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 397       | 0.15%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 393       | 0.15%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 383       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 383       | 0.14%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 381       | 0.14%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 378       | 0.14%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 373       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 368       | 0.14%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 367       | 0.14%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 359       | 0.13%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 356       | 0.13%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 356       | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 102793    | 40.99%  |
| 1366x768 (WXGA)    | 49097     | 19.58%  |
| 3840x2160 (4K)     | 14289     | 5.7%    |
| 1600x900 (HD+)     | 10793     | 4.3%    |
| 2560x1440 (QHD)    | 10444     | 4.16%   |
| 1280x1024 (SXGA)   | 10287     | 4.1%    |
| 1680x1050 (WSXGA+) | 6956      | 2.77%   |
| 1280x800 (WXGA)    | 6748      | 2.69%   |
| 1440x900 (WXGA+)   | 6561      | 2.62%   |
| 1920x1200 (WUXGA)  | 6087      | 2.43%   |
| Unknown            | 2512      | 1%      |
| 3440x1440          | 2324      | 0.93%   |
| 2560x1080          | 2222      | 0.89%   |
| 1360x768           | 2186      | 0.87%   |
| 2560x1600          | 2064      | 0.82%   |
| 1024x600           | 1370      | 0.55%   |
| 1024x768 (XGA)     | 1248      | 0.5%    |
| 2880x1800          | 1205      | 0.48%   |
| 800x1280           | 1184      | 0.47%   |
| 3840x1080          | 1172      | 0.47%   |
| 1920x540           | 828       | 0.33%   |
| 1600x1200          | 684       | 0.27%   |
| 3840x2400          | 661       | 0.26%   |
| 2160x1440          | 621       | 0.25%   |
| 1280x720 (HD)      | 401       | 0.16%   |
| 3200x1800 (QHD+)   | 399       | 0.16%   |
| 2288x1287          | 395       | 0.16%   |
| 2736x1824          | 386       | 0.15%   |
| 2256x1504          | 308       | 0.12%   |
| 1920x1280          | 243       | 0.1%    |
| 3840x1600          | 213       | 0.08%   |
| 3000x2000          | 184       | 0.07%   |
| 1400x1050          | 183       | 0.07%   |
| 3200x2000          | 176       | 0.07%   |
| 3072x1920          | 154       | 0.06%   |
| 3840x1200          | 137       | 0.05%   |
| 2048x1152          | 135       | 0.05%   |
| 4480x1440          | 124       | 0.05%   |
| 3456x2160          | 121       | 0.05%   |
| 1280x960           | 116       | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 65583     | 25.19%  |
| 13      | 22148     | 8.51%   |
| 14      | 18751     | 7.2%    |
| 24      | 17906     | 6.88%   |
| 27      | 17208     | 6.61%   |
| 23      | 15847     | 6.09%   |
| 17      | 15600     | 5.99%   |
| 21      | 15022     | 5.77%   |
| Unknown | 10876     | 4.18%   |
| 19      | 8946      | 3.44%   |
| 18      | 5733      | 2.2%    |
| 31      | 5475      | 2.1%    |
| 20      | 4506      | 1.73%   |
| 22      | 4384      | 1.68%   |
| 12      | 4276      | 1.64%   |
| 34      | 3749      | 1.44%   |
| 11      | 3302      | 1.27%   |
| 16      | 2617      | 1.01%   |
| 84      | 1809      | 0.69%   |
| 10      | 1750      | 0.67%   |
| 72      | 1455      | 0.56%   |
| 40      | 1394      | 0.54%   |
| 32      | 1392      | 0.53%   |
| 54      | 1271      | 0.49%   |
| 7       | 1066      | 0.41%   |
| 25      | 900       | 0.35%   |
| 26      | 790       | 0.3%    |
| 28      | 516       | 0.2%    |
| 48      | 496       | 0.19%   |
| 52      | 465       | 0.18%   |
| 46      | 387       | 0.15%   |
| 37      | 348       | 0.13%   |
| 29      | 346       | 0.13%   |
| 65      | 342       | 0.13%   |
| 42      | 327       | 0.13%   |
| 142     | 303       | 0.12%   |
| 49      | 275       | 0.11%   |
| 33      | 236       | 0.09%   |
| 39      | 215       | 0.08%   |
| 43      | 208       | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 99504     | 38.87%  |
| 501-600        | 47436     | 18.53%  |
| 401-500        | 32874     | 12.84%  |
| 201-300        | 20900     | 8.17%   |
| 351-400        | 18431     | 7.2%    |
| Unknown        | 10876     | 4.25%   |
| 601-700        | 8209      | 3.21%   |
| 701-800        | 5579      | 2.18%   |
| 1001-1500      | 3981      | 1.56%   |
| 1501-2000      | 3566      | 1.39%   |
| 801-900        | 2220      | 0.87%   |
| 1-100          | 1185      | 0.46%   |
| 901-1000       | 685       | 0.27%   |
| More than 2000 | 319       | 0.12%   |
| 101-200        | 204       | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 174502    | 73.59%  |
| 16/10   | 30677     | 12.94%  |
| 5/4     | 9654      | 4.07%   |
| Unknown | 9009      | 3.8%    |
| 21/9    | 4454      | 1.88%   |
| 4/3     | 2968      | 1.25%   |
| 3/2     | 2831      | 1.19%   |
| 0.67    | 949       | 0.4%    |
| 32/9    | 629       | 0.27%   |
| 6/5     | 548       | 0.23%   |
| 1.00    | 328       | 0.14%   |
| 0.62    | 128       | 0.05%   |
| 0.56    | 117       | 0.05%   |
| 1.96    | 75        | 0.03%   |
| 3.40    | 39        | 0.02%   |
| 0.45    | 37        | 0.02%   |
| 3.20    | 31        | 0.01%   |
| 2.00    | 22        | 0.01%   |
| 3.73    | 19        | 0.01%   |
| 2.65    | 19        | 0.01%   |
| 0.89    | 17        | 0.01%   |
| 0.58    | 9         | 0.004%  |
| 2.12    | 8         | 0.003%  |
| 0.80    | 6         | 0.003%  |
| 0.75    | 5         | 0.002%  |
| 11/10   | 4         | 0.002%  |
| 0.63    | 4         | 0.002%  |
| 0.25    | 4         | 0.002%  |
| 3.33    | 3         | 0.001%  |
| 2.01    | 3         | 0.001%  |
| 2.50    | 2         | 0.001%  |
| 1.03    | 2         | 0.001%  |
| 0.65    | 2         | 0.001%  |
| 0.31    | 2         | 0.001%  |
| 3.88    | 1         | 0.0004% |
| 3.76    | 1         | 0.0004% |
| 2.69    | 1         | 0.0004% |
| 2.21    | 1         | 0.0004% |
| 0.79    | 1         | 0.0004% |
| 0.57    | 1         | 0.0004% |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 65077     | 25.22%  |
| 201-250        | 42344     | 16.41%  |
| 81-90          | 31949     | 12.38%  |
| 151-200        | 17786     | 6.89%   |
| 301-350        | 17785     | 6.89%   |
| 351-500        | 11408     | 4.42%   |
| Unknown        | 10877     | 4.22%   |
| 141-150        | 9366      | 3.63%   |
| 121-130        | 9260      | 3.59%   |
| 71-80          | 8950      | 3.47%   |
| 251-300        | 6994      | 2.71%   |
| More than 1000 | 6859      | 2.66%   |
| 501-1000       | 3927      | 1.52%   |
| 61-70          | 3703      | 1.44%   |
| 51-60          | 3394      | 1.32%   |
| 111-120        | 2527      | 0.98%   |
| 131-140        | 1916      | 0.74%   |
| 41-50          | 1708      | 0.66%   |
| 1-40           | 1383      | 0.54%   |
| 91-100         | 806       | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 85746     | 34.18%  |
| 101-120       | 68582     | 27.34%  |
| 121-160       | 59576     | 23.75%  |
| 161-240       | 14535     | 5.79%   |
| Unknown       | 10879     | 4.34%   |
| 1-50          | 6257      | 2.49%   |
| More than 240 | 5278      | 2.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 199328    | 79.58%  |
| 2     | 34281     | 13.69%  |
| 0     | 12685     | 5.06%   |
| 3     | 3793      | 1.51%   |
| 4     | 348       | 0.14%   |
| 5     | 24        | 0.01%   |
| 6     | 12        | 0.005%  |
| 7     | 1         | 0.0004% |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 134223    | 36.5%   |
| Intel                             | 106793    | 29.04%  |
| Qualcomm Atheros                  | 43583     | 11.85%  |
| Broadcom                          | 21465     | 5.84%   |
| MediaTek                          | 5457      | 1.48%   |
| Broadcom Limited                  | 5210      | 1.42%   |
| Marvell Technology Group          | 4795      | 1.3%    |
| Ralink Technology                 | 4703      | 1.28%   |
| Nvidia                            | 4479      | 1.22%   |
| Ralink                            | 3935      | 1.07%   |
| TP-Link                           | 3812      | 1.04%   |
| ASIX Electronics                  | 2027      | 0.55%   |
| Samsung Electronics               | 1801      | 0.49%   |
| Huawei Technologies               | 1511      | 0.41%   |
| Qualcomm Atheros Communications   | 1354      | 0.37%   |
| Xiaomi                            | 1096      | 0.3%    |
| NetGear                           | 986       | 0.27%   |
| D-Link                            | 982       | 0.27%   |
| Dell                              | 908       | 0.25%   |
| Microsoft                         | 885       | 0.24%   |
| ASUSTek Computer                  | 878       | 0.24%   |
| Sierra Wireless                   | 853       | 0.23%   |
| DisplayLink                       | 853       | 0.23%   |
| Qualcomm                          | 828       | 0.23%   |
| D-Link System                     | 818       | 0.22%   |
| JMicron Technology                | 779       | 0.21%   |
| VIA Technologies                  | 730       | 0.2%    |
| Lenovo                            | 728       | 0.2%    |
| Aquantia                          | 700       | 0.19%   |
| Ericsson Business Mobile Networks | 670       | 0.18%   |
| Hewlett-Packard                   | 554       | 0.15%   |
| Silicon Integrated Systems [SiS]  | 495       | 0.13%   |
| Edimax Technology                 | 454       | 0.12%   |
| Linksys                           | 373       | 0.1%    |
| Motorola PCS                      | 358       | 0.1%    |
| Belkin Components                 | 322       | 0.09%   |
| Google                            | 316       | 0.09%   |
| OPPO Electronics                  | 314       | 0.09%   |
| Microchip Technology              | 308       | 0.08%   |
| Attansic Technology               | 284       | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 89483     | 20.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16734     | 3.9%    |
| Intel Wi-Fi 6 AX200                                                    | 9035      | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7921      | 1.85%   |
| Intel Wireless 8265 / 8275                                             | 6192      | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5947      | 1.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5940      | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5792      | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5701      | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5337      | 1.24%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5183      | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 4827      | 1.13%   |
| Intel I211 Gigabit Network Connection                                  | 4785      | 1.12%   |
| Intel Wi-Fi 6 AX201                                                    | 4749      | 1.11%   |
| Intel Wireless 7265                                                    | 4724      | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 4713      | 1.1%    |
| Intel Wireless 7260                                                    | 4312      | 1.01%   |
| Intel Wireless 8260                                                    | 3521      | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3464      | 0.81%   |
| Intel Ethernet Connection (2) I219-V                                   | 3213      | 0.75%   |
| Intel Ethernet Connection I217-LM                                      | 3132      | 0.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3127      | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 3092      | 0.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 3054      | 0.71%   |
| Intel Wireless 3165                                                    | 3009      | 0.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 2772      | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2725      | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 2602      | 0.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 2553      | 0.6%    |
| Intel Ethernet Controller I225-V                                       | 2539      | 0.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 2510      | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2352      | 0.55%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 2332      | 0.54%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2192      | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 2160      | 0.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 2096      | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2079      | 0.48%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 2030      | 0.47%   |
| Intel 82579V Gigabit Network Connection                                | 2020      | 0.47%   |
| Ralink MT7601U Wireless Adapter                                        | 1975      | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 79387     | 41.36%  |
| Qualcomm Atheros                      | 34228     | 17.83%  |
| Realtek Semiconductor                 | 32888     | 17.13%  |
| Broadcom                              | 14323     | 7.46%   |
| MediaTek                              | 5050      | 2.63%   |
| Ralink Technology                     | 4703      | 2.45%   |
| Ralink                                | 3933      | 2.05%   |
| TP-Link                               | 3457      | 1.8%    |
| Broadcom Limited                      | 3202      | 1.67%   |
| Qualcomm Atheros Communications       | 1354      | 0.71%   |
| NetGear                               | 958       | 0.5%    |
| D-Link                                | 919       | 0.48%   |
| Sierra Wireless                       | 853       | 0.44%   |
| ASUSTek Computer                      | 827       | 0.43%   |
| Microsoft                             | 769       | 0.4%    |
| Marvell Technology Group              | 542       | 0.28%   |
| Dell                                  | 541       | 0.28%   |
| Qualcomm                              | 513       | 0.27%   |
| D-Link System                         | 513       | 0.27%   |
| Edimax Technology                     | 454       | 0.24%   |
| Linksys                               | 339       | 0.18%   |
| Belkin Components                     | 312       | 0.16%   |
| FIBOCOM                               | 213       | 0.11%   |
| IMC Networks                          | 178       | 0.09%   |
| AVM                                   | 175       | 0.09%   |
| Hewlett-Packard                       | 124       | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 91        | 0.05%   |
| Sitecom Europe                        | 88        | 0.05%   |
| Mercucys                              | 84        | 0.04%   |
| ZyXEL Communications                  | 76        | 0.04%   |
| ZyDAS                                 | 76        | 0.04%   |
| Gemtek                                | 71        | 0.04%   |
| Micro Star International              | 59        | 0.03%   |
| BUFFALO                               | 57        | 0.03%   |
| Wilocity                              | 45        | 0.02%   |
| Tenda                                 | 40        | 0.02%   |
| Qualcomm Technologies                 | 39        | 0.02%   |
| Wacom                                 | 34        | 0.02%   |
| TRENDnet                              | 32        | 0.02%   |
| Xiaomi                                | 29        | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 9035      | 4.67%   |
| Intel Wireless 8265 / 8275                                              | 6192      | 3.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5947      | 3.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5940      | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5701      | 2.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5337      | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4827      | 2.49%   |
| Intel Wi-Fi 6 AX201                                                     | 4749      | 2.45%   |
| Intel Wireless 7265                                                     | 4724      | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4713      | 2.44%   |
| Intel Wireless 7260                                                     | 4312      | 2.23%   |
| Intel Wireless 8260                                                     | 3521      | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3464      | 1.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3127      | 1.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 3092      | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3054      | 1.58%   |
| Intel Wireless 3165                                                     | 3009      | 1.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2772      | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2725      | 1.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2602      | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2553      | 1.32%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 2510      | 1.3%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2332      | 1.21%   |
| Broadcom BCM43142 802.11b/g/n                                           | 2192      | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2160      | 1.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2096      | 1.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 2030      | 1.05%   |
| Ralink MT7601U Wireless Adapter                                         | 1975      | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1882      | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1729      | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1724      | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1719      | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1668      | 0.86%   |
| Intel Wireless 3160                                                     | 1646      | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1603      | 0.83%   |
| Realtek 802.11ac NIC                                                    | 1508      | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1448      | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1354      | 0.7%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1353      | 0.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1287      | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 120295    | 53.34%  |
| Intel                             | 54905     | 24.34%  |
| Qualcomm Atheros                  | 13781     | 6.11%   |
| Broadcom                          | 9952      | 4.41%   |
| Nvidia                            | 4472      | 1.98%   |
| Marvell Technology Group          | 4256      | 1.89%   |
| Broadcom Limited                  | 2089      | 0.93%   |
| ASIX Electronics                  | 2027      | 0.9%    |
| Samsung Electronics               | 1767      | 0.78%   |
| Xiaomi                            | 1066      | 0.47%   |
| DisplayLink                       | 853       | 0.38%   |
| JMicron Technology                | 779       | 0.35%   |
| Huawei Technologies               | 769       | 0.34%   |
| VIA Technologies                  | 709       | 0.31%   |
| Lenovo                            | 704       | 0.31%   |
| Aquantia                          | 700       | 0.31%   |
| Silicon Integrated Systems [SiS]  | 482       | 0.21%   |
| MediaTek                          | 376       | 0.17%   |
| TP-Link                           | 362       | 0.16%   |
| OPPO Electronics                  | 312       | 0.14%   |
| Google                            | 306       | 0.14%   |
| D-Link System                     | 306       | 0.14%   |
| Qualcomm                          | 303       | 0.13%   |
| Attansic Technology               | 284       | 0.13%   |
| Motorola PCS                      | 252       | 0.11%   |
| ZTE WCDMA Technologies MSM        | 246       | 0.11%   |
| Apple                             | 230       | 0.1%    |
| Microchip Technology              | 226       | 0.1%    |
| Mellanox Technologies             | 206       | 0.09%   |
| ICS Advent                        | 197       | 0.09%   |
| Hewlett-Packard                   | 172       | 0.08%   |
| 3Com                              | 144       | 0.06%   |
| Sundance Technology Inc / IC Plus | 113       | 0.05%   |
| Microsoft                         | 99        | 0.04%   |
| OnePlus Technology (Shenzhen)     | 96        | 0.04%   |
| American Megatrends               | 95        | 0.04%   |
| IBM                               | 91        | 0.04%   |
| HTC (High Tech Computer)          | 90        | 0.04%   |
| T & A Mobile Phones               | 80        | 0.04%   |
| D-Link                            | 65        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 89483     | 38.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16734     | 7.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 7921      | 3.43%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5792      | 2.51%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5183      | 2.25%   |
| Intel I211 Gigabit Network Connection                                  | 4785      | 2.07%   |
| Intel Ethernet Connection (2) I219-V                                   | 3213      | 1.39%   |
| Intel Ethernet Connection I217-LM                                      | 3132      | 1.36%   |
| Intel Ethernet Controller I225-V                                       | 2539      | 1.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2352      | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2079      | 0.9%    |
| Intel 82579V Gigabit Network Connection                                | 2020      | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                  | 1777      | 0.77%   |
| Nvidia MCP61 Ethernet                                                  | 1679      | 0.73%   |
| Intel Ethernet Connection (7) I219-V                                   | 1676      | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                          | 1661      | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1522      | 0.66%   |
| Intel Ethernet Connection I219-LM                                      | 1477      | 0.64%   |
| Intel 82577LM Gigabit Network Connection                               | 1428      | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1300      | 0.56%   |
| Intel Ethernet Connection I218-LM                                      | 1276      | 0.55%   |
| Intel Ethernet Connection I217-V                                       | 1259      | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1255      | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1183      | 0.51%   |
| Intel I210 Gigabit Network Connection                                  | 1173      | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                   | 1140      | 0.49%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 1129      | 0.49%   |
| Nvidia MCP79 Ethernet                                                  | 1110      | 0.48%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1108      | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1099      | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 1084      | 0.47%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 1065      | 0.46%   |
| Intel 82574L Gigabit Network Connection                                | 1060      | 0.46%   |
| Intel 82567LM Gigabit Network Connection                               | 997       | 0.43%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 995       | 0.43%   |
| Intel Ethernet Connection (7) I219-LM                                  | 989       | 0.43%   |
| Intel Ethernet Connection (2) I218-V                                   | 970       | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 968       | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 940       | 0.41%   |
| Intel Ethernet Connection (6) I219-V                                   | 939       | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 211037    | 53.16%  |
| WiFi     | 181412    | 45.7%   |
| Modem    | 3895      | 0.98%   |
| Unknown  | 636       | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 139628    | 55.35%  |
| Ethernet | 112572    | 44.62%  |
| Unknown  | 64        | 0.03%   |
| Modem    | 20        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 131497    | 53.63%  |
| 1     | 101394    | 41.35%  |
| 0     | 5547      | 2.26%   |
| 3     | 4809      | 1.96%   |
| 4     | 1211      | 0.49%   |
| 5     | 261       | 0.11%   |
| 6     | 260       | 0.11%   |
| 8     | 100       | 0.04%   |
| 7     | 47        | 0.02%   |
| 10    | 27        | 0.01%   |
| 12    | 13        | 0.01%   |
| 9     | 11        | 0.004%  |
| 11    | 5         | 0.002%  |
| 13    | 4         | 0.002%  |
| 20    | 3         | 0.001%  |
| 18    | 3         | 0.001%  |
| 17    | 3         | 0.001%  |
| 132   | 2         | 0.001%  |
| 33    | 2         | 0.001%  |
| 16    | 2         | 0.001%  |
| 66    | 1         | 0.0004% |
| 42    | 1         | 0.0004% |
| 32    | 1         | 0.0004% |
| 22    | 1         | 0.0004% |
| 21    | 1         | 0.0004% |
| 14    | 1         | 0.0004% |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 195239    | 77.93%  |
| Yes     | 47231     | 18.85%  |
| Unknown | 8065      | 3.22%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 63285     | 44.43%  |
| Realtek Semiconductor           | 14086     | 9.89%   |
| Qualcomm Atheros Communications | 11606     | 8.15%   |
| Cambridge Silicon Radio         | 8326      | 5.85%   |
| IMC Networks                    | 7660      | 5.38%   |
| Broadcom                        | 7386      | 5.19%   |
| Apple                           | 5526      | 3.88%   |
| Lite-On Technology              | 5187      | 3.64%   |
| Foxconn / Hon Hai               | 4763      | 3.34%   |
| ASUSTek Computer                | 2587      | 1.82%   |
| Dell                            | 1916      | 1.35%   |
| Hewlett-Packard                 | 1586      | 1.11%   |
| MediaTek                        | 1279      | 0.9%    |
| Ralink                          | 1189      | 0.83%   |
| Toshiba                         | 1153      | 0.81%   |
| Realtek                         | 845       | 0.59%   |
| Foxconn International           | 510       | 0.36%   |
| Marvell Semiconductor           | 497       | 0.35%   |
| TP-Link                         | 444       | 0.31%   |
| Alps Electric                   | 385       | 0.27%   |
| Ralink Technology               | 265       | 0.19%   |
| Integrated System Solution      | 219       | 0.15%   |
| USI                             | 184       | 0.13%   |
| Belkin Components               | 136       | 0.1%    |
| Edimax Technology               | 130       | 0.09%   |
| Dynex                           | 127       | 0.09%   |
| Askey Computer                  | 127       | 0.09%   |
| Chicony Electronics             | 103       | 0.07%   |
| Micro Star International        | 99        | 0.07%   |
| Taiyo Yuden                     | 87        | 0.06%   |
| Opticis                         | 78        | 0.05%   |
| Actions                         | 70        | 0.05%   |
| Qcom                            | 68        | 0.05%   |
| HTC (High Tech Computer)        | 65        | 0.05%   |
| Unknown                         | 61        | 0.04%   |
| Smart Modular Technologies      | 53        | 0.04%   |
| Logitech                        | 51        | 0.04%   |
| Conwise Technology              | 41        | 0.03%   |
| Fujitsu                         | 39        | 0.03%   |
| SiW                             | 35        | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 13976     | 9.8%    |
| Intel AX201 Bluetooth                               | 10848     | 7.61%   |
| Intel Bluetooth Device                              | 8790      | 6.16%   |
| Intel AX200 Bluetooth                               | 8616      | 6.04%   |
| Realtek Bluetooth Radio                             | 8578      | 6.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8531      | 5.98%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8325      | 5.84%   |
| Qualcomm Atheros  Bluetooth Device                  | 5182      | 3.63%   |
| IMC Networks Bluetooth Radio                        | 3319      | 2.33%   |
| Intel AX211 Bluetooth                               | 3063      | 2.15%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2568      | 1.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 2526      | 1.77%   |
| Apple Bluetooth Host Controller                     | 2236      | 1.57%   |
| Intel AX210 Bluetooth                               | 2184      | 1.53%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1999      | 1.4%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1903      | 1.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1892      | 1.33%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1727      | 1.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1725      | 1.21%   |
| IMC Networks Bluetooth Device                       | 1518      | 1.06%   |
| IMC Networks Wireless_Device                        | 1510      | 1.06%   |
| Apple Bluetooth USB Host Controller                 | 1505      | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1422      | 1%      |
| Lite-On Bluetooth Device                            | 1316      | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1237      | 0.87%   |
| MediaTek Wireless_Device                            | 1216      | 0.85%   |
| Realtek 802.11ac WLAN Adapter                       | 1202      | 0.84%   |
| Ralink RT3290 Bluetooth                             | 1189      | 0.83%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1159      | 0.81%   |
| Broadcom BCM2045B (BDC-2.1)                         | 972       | 0.68%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 968       | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                    | 944       | 0.66%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 930       | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                    | 849       | 0.6%    |
| Realtek Bluetooth Radio                             | 845       | 0.59%   |
| Foxconn / Hon Hai Wireless_Device                   | 792       | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 728       | 0.51%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 714       | 0.5%    |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 673       | 0.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 662       | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 171472    | 51.47%  |
| AMD                                          | 70826     | 21.26%  |
| Nvidia                                       | 57226     | 17.18%  |
| C-Media Electronics                          | 5375      | 1.61%   |
| Logitech                                     | 2419      | 0.73%   |
| Creative Labs                                | 2185      | 0.66%   |
| Texas Instruments                            | 1178      | 0.35%   |
| JMTek                                        | 1115      | 0.33%   |
| Realtek Semiconductor                        | 1022      | 0.31%   |
| GN Netcom                                    | 995       | 0.3%    |
| Generalplus Technology                       | 910       | 0.27%   |
| ASUSTek Computer                             | 891       | 0.27%   |
| Kingston Technology                          | 871       | 0.26%   |
| Creative Technology                          | 813       | 0.24%   |
| VIA Technologies                             | 786       | 0.24%   |
| Lenovo                                       | 760       | 0.23%   |
| Razer USA                                    | 710       | 0.21%   |
| Plantronics                                  | 675       | 0.2%    |
| Focusrite-Novation                           | 675       | 0.2%    |
| SteelSeries ApS                              | 623       | 0.19%   |
| Silicon Integrated Systems [SiS]             | 605       | 0.18%   |
| Corsair                                      | 583       | 0.17%   |
| Micro Star International                     | 423       | 0.13%   |
| Hewlett-Packard                              | 421       | 0.13%   |
| Apple                                        | 370       | 0.11%   |
| Blue Microphones                             | 345       | 0.1%    |
| Sony                                         | 317       | 0.1%    |
| DSEA A/S                                     | 275       | 0.08%   |
| Tenx Technology                              | 251       | 0.08%   |
| BEHRINGER International                      | 243       | 0.07%   |
| Dell                                         | 234       | 0.07%   |
| Samson Technologies                          | 233       | 0.07%   |
| M-Audio                                      | 201       | 0.06%   |
| Yamaha                                       | 186       | 0.06%   |
| Microsoft                                    | 177       | 0.05%   |
| RODE Microphones                             | 176       | 0.05%   |
| GYROCOM C&C                                  | 176       | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 159       | 0.05%   |
| XMOS                                         | 156       | 0.05%   |
| Thesycon Systemsoftware & Consulting         | 141       | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19659     | 4.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 17275     | 4.37%   |
| Intel Sunrise Point-LP HD Audio                                            | 16872     | 4.27%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16381     | 4.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 11415     | 2.89%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10519     | 2.66%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9326      | 2.36%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 9064      | 2.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 8216      | 2.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8213      | 2.08%   |
| AMD Starship/Matisse HD Audio Controller                                   | 8176      | 2.07%   |
| AMD FCH Azalia Controller                                                  | 7905      | 2%      |
| Intel Cannon Lake PCH cAVS                                                 | 7874      | 1.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7434      | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 6383      | 1.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6301      | 1.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6264      | 1.58%   |
| Intel 8 Series HD Audio Controller                                         | 5770      | 1.46%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5742      | 1.45%   |
| Intel Broadwell-U Audio Controller                                         | 4687      | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4640      | 1.17%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4553      | 1.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4478      | 1.13%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4382      | 1.11%   |
| Intel 200 Series PCH HD Audio                                              | 4345      | 1.1%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4225      | 1.07%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4012      | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                              | 3827      | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3796      | 0.96%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3794      | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3584      | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                   | 3558      | 0.9%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3405      | 0.86%   |
| Nvidia High Definition Audio Controller                                    | 3279      | 0.83%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 3013      | 0.76%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 3004      | 0.76%   |
| Intel Comet Lake PCH cAVS                                                  | 2995      | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2951      | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 2767      | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2741      | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 33753     | 20.37%  |
| SK hynix            | 26956     | 16.27%  |
| Unknown             | 21632     | 13.05%  |
| Kingston            | 19835     | 11.97%  |
| Micron Technology   | 14542     | 8.78%   |
| Crucial             | 9206      | 5.56%   |
| Corsair             | 7884      | 4.76%   |
| G.Skill             | 4967      | 3%      |
| A-DATA Technology   | 3305      | 1.99%   |
| Elpida              | 2813      | 1.7%    |
| Ramaxel Technology  | 2749      | 1.66%   |
| Nanya Technology    | 2276      | 1.37%   |
| Unknown (ABCD)      | 1340      | 0.81%   |
| Unknown             | 1324      | 0.8%    |
| Patriot             | 1237      | 0.75%   |
| Team                | 1132      | 0.68%   |
| Smart               | 878       | 0.53%   |
| Transcend           | 720       | 0.43%   |
| AMD                 | 639       | 0.39%   |
| GOODRAM             | 630       | 0.38%   |
| Apacer              | 446       | 0.27%   |
| ASint Technology    | 365       | 0.22%   |
| Goldkey             | 300       | 0.18%   |
| Silicon Power       | 296       | 0.18%   |
| Kingmax             | 280       | 0.17%   |
| Teikon              | 237       | 0.14%   |
| Qimonda             | 222       | 0.13%   |
| PNY                 | 219       | 0.13%   |
| 48spaces            | 205       | 0.12%   |
| Avant               | 203       | 0.12%   |
| GeIL                | 182       | 0.11%   |
| Unifosa             | 180       | 0.11%   |
| Hewlett-Packard     | 164       | 0.1%    |
| Timetec             | 147       | 0.09%   |
| SHARETRONIC         | 138       | 0.08%   |
| Smart Brazil        | 137       | 0.08%   |
| Kllisre             | 136       | 0.08%   |
| Foxline             | 134       | 0.08%   |
| CSX                 | 121       | 0.07%   |
| Qumo                | 119       | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 1324      | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1182      | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1173      | 0.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1116      | 0.62%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1095      | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 1045      | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1026      | 0.57%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 973       | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 964       | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 937       | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 788       | 0.44%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 770       | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 758       | 0.42%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 727       | 0.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 692       | 0.38%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 688       | 0.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 658       | 0.37%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 656       | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 643       | 0.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 628       | 0.35%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 622       | 0.35%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 602       | 0.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 598       | 0.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 585       | 0.32%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 581       | 0.32%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 580       | 0.32%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 572       | 0.32%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 537       | 0.3%    |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 529       | 0.29%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 528       | 0.29%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 522       | 0.29%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 513       | 0.28%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 512       | 0.28%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 500       | 0.28%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 498       | 0.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 494       | 0.27%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 491       | 0.27%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 490       | 0.27%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 469       | 0.26%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 421       | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 57174     | 39.88%  |
| DDR3            | 50510     | 35.24%  |
| DDR2            | 9744      | 6.8%    |
| Unknown         | 6374      | 4.45%   |
| SDRAM           | 5614      | 3.92%   |
| LPDDR4          | 4724      | 3.3%    |
| LPDDR3          | 2817      | 1.97%   |
| DDR5            | 2743      | 1.91%   |
| DDR             | 1551      | 1.08%   |
| LPDDR5          | 1480      | 1.03%   |
| DRAM            | 589       | 0.41%   |
| RAM             | 10        | 0.01%   |
| EEPROM          | 8         | 0.01%   |
| DDR2 FB-DIMM    | 4         | 0.003%  |
| Logical non-vol | 3         | 0.002%  |
| EPROM           | 2         | 0.001%  |
| SRAM            | 1         | 0.001%  |
| LPDDR2          | 1         | 0.001%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 77599     | 54.66%  |
| DIMM            | 54589     | 38.45%  |
| Row Of Chips    | 8409      | 5.92%   |
| Chip            | 591       | 0.42%   |
| Unknown         | 517       | 0.36%   |
| FB-DIMM         | 135       | 0.1%    |
| RIMM            | 119       | 0.08%   |
| Proprietary Car | 7         | 0.005%  |
| DIP             | 3         | 0.002%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 51529     | 32.45%  |
| 4096    | 44343     | 27.92%  |
| 2048    | 26076     | 16.42%  |
| 16384   | 20404     | 12.85%  |
| 1024    | 9025      | 5.68%   |
| 32768   | 5290      | 3.33%   |
| 512     | 1523      | 0.96%   |
| 256     | 283       | 0.18%   |
| 65536   | 136       | 0.09%   |
| 49152   | 30        | 0.02%   |
| 1536    | 24        | 0.02%   |
| 3072    | 21        | 0.01%   |
| Unknown | 20        | 0.01%   |
| 128     | 19        | 0.01%   |
| 24576   | 8         | 0.01%   |
| 12288   | 8         | 0.01%   |
| 64      | 8         | 0.01%   |
| 16      | 8         | 0.01%   |
| 1       | 8         | 0.01%   |
| 6144    | 7         | 0.004%  |
| 32      | 7         | 0.004%  |
| 131072  | 4         | 0.003%  |
| 129408  | 4         | 0.003%  |
| 8       | 2         | 0.001%  |
| 258496  | 1         | 0.001%  |
| 32767   | 1         | 0.001%  |
| 16315   | 1         | 0.001%  |
| 15616   | 1         | 0.001%  |
| 12536   | 1         | 0.001%  |
| 12333   | 1         | 0.001%  |
| 11825   | 1         | 0.001%  |
| 8072    | 1         | 0.001%  |
| 384     | 1         | 0.001%  |
| 232     | 1         | 0.001%  |
| 13      | 1         | 0.001%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31488     | 20.15%  |
| 3200    | 19871     | 12.71%  |
| 2667    | 18297     | 11.71%  |
| 1333    | 12495     | 7.99%   |
| 2400    | 9993      | 6.39%   |
| 2133    | 6635      | 4.25%   |
| 1334    | 5810      | 3.72%   |
| 800     | 5456      | 3.49%   |
| 667     | 5270      | 3.37%   |
| Unknown | 5038      | 3.22%   |
| 3600    | 3633      | 2.32%   |
| 1867    | 2703      | 1.73%   |
| 1067    | 2052      | 1.31%   |
| 4267    | 1748      | 1.12%   |
| 4800    | 1654      | 1.06%   |
| 1066    | 1578      | 1.01%   |
| 6400    | 1409      | 0.9%    |
| 3266    | 1355      | 0.87%   |
| 1866    | 1174      | 0.75%   |
| 4199    | 1147      | 0.73%   |
| 3733    | 1133      | 0.72%   |
| 533     | 1055      | 0.67%   |
| 2666    | 975       | 0.62%   |
| 1800    | 884       | 0.57%   |
| 400     | 884       | 0.57%   |
| 3000    | 846       | 0.54%   |
| 2933    | 841       | 0.54%   |
| 3400    | 838       | 0.54%   |
| 2048    | 815       | 0.52%   |
| 3800    | 795       | 0.51%   |
| 333     | 518       | 0.33%   |
| 5600    | 505       | 0.32%   |
| 3866    | 502       | 0.32%   |
| 975     | 484       | 0.31%   |
| 4266    | 417       | 0.27%   |
| 3466    | 392       | 0.25%   |
| 8400    | 375       | 0.24%   |
| 6000    | 298       | 0.19%   |
| 2800    | 295       | 0.19%   |
| 3066    | 268       | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 2588      | 34.03%  |
| Canon                           | 1309      | 17.21%  |
| Brother Industries              | 1167      | 15.35%  |
| Samsung Electronics             | 888       | 11.68%  |
| Seiko Epson                     | 699       | 9.19%   |
| Xerox                           | 116       | 1.53%   |
| Prolific Technology             | 96        | 1.26%   |
| Dymo-CoStar                     | 83        | 1.09%   |
| Pantum                          | 81        | 1.07%   |
| Lexmark International           | 81        | 1.07%   |
| Kyocera                         | 78        | 1.03%   |
| QinHeng Electronics             | 66        | 0.87%   |
| Ricoh                           | 55        | 0.72%   |
| Panasonic (Matsushita)          | 49        | 0.64%   |
| STMicroelectronics              | 31        | 0.41%   |
| Zebra                           | 29        | 0.38%   |
| Oki Data                        | 22        | 0.29%   |
| Dell                            | 21        | 0.28%   |
| Fuji Xerox                      | 13        | 0.17%   |
| Apple                           | 11        | 0.14%   |
| Konica Minolta                  | 8         | 0.11%   |
| Xiaomi                          | 7         | 0.09%   |
| TSC Auto ID Technology          | 6         | 0.08%   |
| MIIIW                           | 6         | 0.08%   |
| Custom Engineering SPA          | 6         | 0.08%   |
| Star Micronics                  | 5         | 0.07%   |
| NXP Semiconductors              | 5         | 0.07%   |
| Citizen                         | 5         | 0.07%   |
| SAT                             | 4         | 0.05%   |
| Datamax-O'Neil                  | 4         | 0.05%   |
| Zhuhai Poskey Technology        | 3         | 0.04%   |
| WinChipHead                     | 3         | 0.04%   |
| Sharp                           | 3         | 0.04%   |
| Samsung Info. Systems America   | 3         | 0.04%   |
| Minolta                         | 3         | 0.04%   |
| Magic Control Technology        | 3         | 0.04%   |
| ICS Advent                      | 3         | 0.04%   |
| cab Produkttechnik GmbH & Co KG | 3         | 0.04%   |
| BIXOLON                         | 3         | 0.04%   |
| ATEN International              | 3         | 0.04%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP LaserJet 1020                     | 135       | 1.75%   |
| HP LaserJet 1018                     | 102       | 1.32%   |
| Samsung M2020 Series                 | 96        | 1.25%   |
| Prolific PL2305 Parallel Port        | 96        | 1.25%   |
| HP DeskJet 2600 series               | 86        | 1.12%   |
| Samsung M2070 Series                 | 83        | 1.08%   |
| HP LaserJet P1102                    | 81        | 1.05%   |
| Canon PIXMA MG2500 Series            | 74        | 0.96%   |
| Brother Printer                      | 74        | 0.96%   |
| HP DeskJet 2130 series               | 71        | 0.92%   |
| Samsung SCX-4200 series              | 66        | 0.86%   |
| QinHeng CH340S                       | 66        | 0.86%   |
| Seiko Epson Printer                  | 64        | 0.83%   |
| HP DeskJet 2700 series               | 63        | 0.82%   |
| HP LaserJet P1005                    | 61        | 0.79%   |
| Samsung SCX-3400 Series              | 60        | 0.78%   |
| Canon LBP2900                        | 56        | 0.73%   |
| HP ENVY 4520 series                  | 55        | 0.71%   |
| Brother HL-2030 Laser Printer        | 52        | 0.67%   |
| HP Deskjet 2050 J510                 | 48        | 0.62%   |
| HP LaserJet 1010                     | 47        | 0.61%   |
| HP DeskJet 3630 series               | 47        | 0.61%   |
| Samsung ML-1640 Series Laser Printer | 46        | 0.6%    |
| Canon PIXMA MG3600 Series            | 46        | 0.6%    |
| Seiko Epson ET-2710 Series           | 45        | 0.58%   |
| Canon LiDE 300                       | 44        | 0.57%   |
| Canon PIXMA MX920 Series             | 42        | 0.55%   |
| Canon LiDE 400                       | 42        | 0.55%   |
| Samsung SCX-3200 Series              | 41        | 0.53%   |
| Samsung ML-216x Series Laser Printer | 40        | 0.52%   |
| HP Deskjet 2540 series               | 40        | 0.52%   |
| Brother HL-1110 series               | 39        | 0.51%   |
| HP ENVY 5000 series                  | 37        | 0.48%   |
| HP DeskJet 3700 series               | 35        | 0.45%   |
| HP Deskjet 1050 J410                 | 35        | 0.45%   |
| Canon MF3010                         | 35        | 0.45%   |
| HP LaserJet 1200                     | 34        | 0.44%   |
| Canon MF4410                         | 34        | 0.44%   |
| Canon iP7200 series                  | 34        | 0.44%   |
| HP LaserJet Professional P1102w      | 33        | 0.43%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 866       | 52.17%  |
| Seiko Epson                                    | 364       | 21.93%  |
| Hewlett-Packard                                | 217       | 13.07%  |
| Mustek Systems                                 | 93        | 5.6%    |
| Ultima Electronics                             | 31        | 1.87%   |
| Acer Peripherals (now BenQ)                    | 26        | 1.57%   |
| AGFA-Gevaert NV                                | 18        | 1.08%   |
| Plustek                                        | 11        | 0.66%   |
| KYE Systems (Mouse Systems)                    | 10        | 0.6%    |
| Microtek International                         | 4         | 0.24%   |
| Fujitsu                                        | 4         | 0.24%   |
| UMAX                                           | 3         | 0.18%   |
| Visioneer                                      | 2         | 0.12%   |
| Siemens Information and Communication Products | 2         | 0.12%   |
| Canon Electronics                              | 2         | 0.12%   |
| Avision                                        | 2         | 0.12%   |
| Syscan                                         | 1         | 0.06%   |
| Salix Technology                               | 1         | 0.06%   |
| Papillon Systems                               | 1         | 0.06%   |
| Nikon                                          | 1         | 0.06%   |
| Minolta                                        | 1         | 0.06%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 132       | 7.93%   |
| Canon CanoScan LIDE 25                                                                | 99        | 5.95%   |
| Canon CanoScan LiDE 210                                                               | 97        | 5.83%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 88        | 5.29%   |
| Canon CanoScan LiDE 220                                                               | 80        | 4.8%    |
| Canon CanoScan LiDE 120                                                               | 65        | 3.9%    |
| Canon CanoScan LiDE 100                                                               | 49        | 2.94%   |
| HP ScanJet 2400c                                                                      | 40        | 2.4%    |
| Canon CanoScan N1240U/LiDE 30                                                         | 38        | 2.28%   |
| Canon CanoScan LiDE 60                                                                | 31        | 1.86%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 29        | 1.74%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 29        | 1.74%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 28        | 1.68%   |
| Canon CanoScan LiDE 200                                                               | 27        | 1.62%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 26        | 1.56%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 26        | 1.56%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 25        | 1.5%    |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 24        | 1.44%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 24        | 1.44%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 22        | 1.32%   |
| Mustek Systems SNAPSCAN e22                                                           | 16        | 0.96%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 15        | 0.9%    |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 15        | 0.9%    |
| Canon CanoScan LiDE 90                                                                | 15        | 0.9%    |
| Canon CanoScan LiDE 700F                                                              | 15        | 0.9%    |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 13        | 0.78%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 13        | 0.78%   |
| Canon CanoScan N650U/N656U                                                            | 13        | 0.78%   |
| Canon CanoScan 4400F                                                                  | 13        | 0.78%   |
| Seiko Epson Scanner                                                                   | 12        | 0.72%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 12        | 0.72%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 12        | 0.72%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 12        | 0.72%   |
| HP Scanjet 300                                                                        | 11        | 0.66%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 10        | 0.6%    |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 9         | 0.54%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 9         | 0.54%   |
| HP ScanJet 3800c                                                                      | 9         | 0.54%   |
| HP Scanjet 200                                                                        | 9         | 0.54%   |
| Canon CanoScan LiDE 70                                                                | 9         | 0.54%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 30169     | 21.17%  |
| IMC Networks                           | 12712     | 8.92%   |
| Microdia                               | 11755     | 8.25%   |
| Realtek Semiconductor                  | 10367     | 7.27%   |
| Logitech                               | 8376      | 5.88%   |
| Sunplus Innovation Technology          | 7294      | 5.12%   |
| Bison Electronics                      | 7082      | 4.97%   |
| Quanta                                 | 6620      | 4.64%   |
| Cheng Uei Precision Industry (Foxlink) | 4955      | 3.48%   |
| Suyin                                  | 4749      | 3.33%   |
| Apple                                  | 4414      | 3.1%    |
| Acer                                   | 3433      | 2.41%   |
| Syntek                                 | 3400      | 2.39%   |
| Lite-On Technology                     | 2682      | 1.88%   |
| Silicon Motion                         | 2418      | 1.7%    |
| Luxvisions Innotech Limited            | 2094      | 1.47%   |
| Alcor Micro                            | 1972      | 1.38%   |
| Z-Star Microelectronics                | 1632      | 1.14%   |
| Microsoft                              | 1539      | 1.08%   |
| Samsung Electronics                    | 1362      | 0.96%   |
| Ricoh                                  | 1230      | 0.86%   |
| Sonix Technology                       | 887       | 0.62%   |
| Lenovo                                 | 750       | 0.53%   |
| ALi                                    | 548       | 0.38%   |
| Generalplus Technology                 | 529       | 0.37%   |
| Importek                               | 514       | 0.36%   |
| Primax Electronics                     | 439       | 0.31%   |
| SunplusIT                              | 408       | 0.29%   |
| KYE Systems (Mouse Systems)            | 394       | 0.28%   |
| GEMBIRD                                | 390       | 0.27%   |
| Creative Technology                    | 343       | 0.24%   |
| Cubeternet                             | 322       | 0.23%   |
| ARC International                      | 300       | 0.21%   |
| DigiTech                               | 292       | 0.2%    |
| icSpring                               | 266       | 0.19%   |
| OmniVision Technologies                | 260       | 0.18%   |
| MacroSilicon                           | 239       | 0.17%   |
| Aveo Technology                        | 230       | 0.16%   |
| Arkmicro Technologies                  | 214       | 0.15%   |
| Jieli Technology                       | 213       | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 5543      | 3.86%   |
| Microdia Integrated_Webcam_HD           | 4304      | 3%      |
| Realtek Integrated_Webcam_HD            | 3277      | 2.28%   |
| IMC Networks USB2.0 HD UVC WebCam       | 3132      | 2.18%   |
| IMC Networks Integrated Camera          | 3040      | 2.12%   |
| Chicony HD WebCam                       | 2682      | 1.87%   |
| Bison Integrated Camera                 | 2046      | 1.42%   |
| Logitech Webcam C270                    | 1953      | 1.36%   |
| Sunplus Integrated_Webcam_HD            | 1940      | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 1820      | 1.27%   |
| Syntek Integrated Camera                | 1804      | 1.26%   |
| Samsung Galaxy series, misc. (MTP mode) | 1336      | 0.93%   |
| Realtek USB Camera                      | 1318      | 0.92%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 1264      | 0.88%   |
| Logitech HD Pro Webcam C920             | 1226      | 0.85%   |
| Apple Built-in iSight                   | 1154      | 0.8%    |
| Quanta HD User Facing                   | 1143      | 0.8%    |
| Chicony HP HD Camera                    | 1091      | 0.76%   |
| Apple FaceTime HD Camera (Built-in)     | 991       | 0.69%   |
| Microdia Integrated Webcam              | 977       | 0.68%   |
| Sunplus HD WebCam                       | 971       | 0.68%   |
| Lite-On Integrated Camera               | 933       | 0.65%   |
| Chicony HP TrueVision HD                | 931       | 0.65%   |
| Chicony USB2.0 HD UVC WebCam            | 920       | 0.64%   |
| Acer Integrated Camera                  | 891       | 0.62%   |
| Chicony Lenovo EasyCamera               | 883       | 0.61%   |
| Chicony HD User Facing                  | 875       | 0.61%   |
| Microdia USB 2.0 Camera                 | 852       | 0.59%   |
| Chicony HP TrueVision HD Camera         | 851       | 0.59%   |
| Chicony USB2.0 VGA UVC WebCam           | 845       | 0.59%   |
| Bison HD Webcam                         | 823       | 0.57%   |
| Quanta HP TrueVision HD Camera          | 781       | 0.54%   |
| Chicony EasyCamera                      | 779       | 0.54%   |
| Chicony USB2.0 Camera                   | 752       | 0.52%   |
| Apple FaceTime HD Camera                | 752       | 0.52%   |
| Quanta VGA WebCam                       | 750       | 0.52%   |
| Chicony TOSHIBA Web Camera - HD         | 740       | 0.52%   |
| Chicony USB 2.0 Camera                  | 726       | 0.51%   |
| Chicony VGA WebCam                      | 709       | 0.49%   |
| Chicony Integrated Camera (1280x720@30) | 689       | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 8080      | 33.56%  |
| Synaptics                          | 6471      | 26.88%  |
| Shenzhen Goodix Technology         | 3401      | 14.13%  |
| AuthenTec                          | 1577      | 6.55%   |
| Elan Microelectronics              | 1419      | 5.89%   |
| Upek                               | 1307      | 5.43%   |
| LighTuning Technology              | 966       | 4.01%   |
| STMicroelectronics                 | 387       | 1.61%   |
| Realtek USB2.0 Finger Print Bridge | 139       | 0.58%   |
| Focal-systems.Corp                 | 106       | 0.44%   |
| Samsung Electronics                | 101       | 0.42%   |
| DigitalPersona                     | 28        | 0.12%   |
| HOLTEK                             | 25        | 0.1%    |
| FocalTech                          | 19        | 0.08%   |
| Microsoft                          | 14        | 0.06%   |
| Dell                               | 12        | 0.05%   |
| GDMicroelectronics                 | 8         | 0.03%   |
| Next Biometrics                    | 7         | 0.03%   |
| Futronic Technology                | 4         | 0.02%   |
| Gingytech                          | 3         | 0.01%   |
| Suprema                            | 2         | 0.01%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1917      | 7.96%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1871      | 7.77%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1742      | 7.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1208      | 5.02%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1015      | 4.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 916       | 3.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 914       | 3.8%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 831       | 3.45%   |
| Elan ELAN:Fingerprint                                                      | 781       | 3.24%   |
| Validity Sensors Synaptics WBDI                                            | 695       | 2.89%   |
| Elan ELAN:ARM-M4                                                           | 583       | 2.42%   |
| Validity Sensors VFS491                                                    | 540       | 2.24%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 522       | 2.17%   |
| Validity Sensors Fingerprint scanner                                       | 522       | 2.17%   |
| Shenzhen Goodix FingerPrint                                                | 515       | 2.14%   |
| Synaptics  WBDI                                                            | 495       | 2.06%   |
| AuthenTec AES2810                                                          | 492       | 2.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 464       | 1.93%   |
| Synaptics WBDI                                                             | 455       | 1.89%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 402       | 1.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 401       | 1.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 399       | 1.66%   |
| Synaptics UWP WBDI                                                         | 393       | 1.63%   |
| STMicroelectronics Fingerprint Reader                                      | 385       | 1.6%    |
| Synaptics Fingerprint reader [HP G6]                                       | 384       | 1.59%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 376       | 1.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 352       | 1.46%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 329       | 1.37%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 327       | 1.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 319       | 1.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 281       | 1.17%   |
| AuthenTec AES1600                                                          | 255       | 1.06%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 231       | 0.96%   |
| AuthenTec Fingerprint Sensor                                               | 228       | 0.95%   |
| Synaptics UWP WBDI Device                                                  | 216       | 0.9%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 196       | 0.81%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 161       | 0.67%   |
| LighTuning Fingerprint Reader                                              | 157       | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 141       | 0.59%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 139       | 0.58%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 4567      | 45.1%   |
| Alcor Micro                       | 2737      | 27.03%  |
| O2 Micro                          | 723       | 7.14%   |
| Upek                              | 554       | 5.47%   |
| Lenovo                            | 492       | 4.86%   |
| Gemalto (was Gemplus)             | 157       | 1.55%   |
| SCM Microsystems                  | 131       | 1.29%   |
| Advanced Card Systems             | 103       | 1.02%   |
| OmniKey                           | 90        | 0.89%   |
| Yubico.com                        | 70        | 0.69%   |
| Realtek Semiconductor             | 69        | 0.68%   |
| Aladdin Knowledge Systems         | 58        | 0.57%   |
| CHERRY                            | 39        | 0.39%   |
| Reiner SCT Kartensysteme          | 38        | 0.38%   |
| Chicony Electronics               | 36        | 0.36%   |
| Clay Logic                        | 35        | 0.35%   |
| Aktiv                             | 34        | 0.34%   |
| VASCO Data Security International | 27        | 0.27%   |
| Bit4id                            | 25        | 0.25%   |
| Hewlett-Packard                   | 20        | 0.2%    |
| Giesecke & Devrient               | 17        | 0.17%   |
| Fujitsu Siemens Computers         | 16        | 0.16%   |
| Aladdin R.D.                      | 14        | 0.14%   |
| Athena Smartcard Solutions        | 10        | 0.1%    |
| Watchdata                         | 7         | 0.07%   |
| NXP Semiconductors                | 7         | 0.07%   |
| C3PO                              | 7         | 0.07%   |
| Purism, SPC                       | 6         | 0.06%   |
| Kobil Systems                     | 5         | 0.05%   |
| In Focus Systems                  | 5         | 0.05%   |
| Microchip Technology              | 4         | 0.04%   |
| Feitian Technologies              | 4         | 0.04%   |
| Castles Technology                | 4         | 0.04%   |
| Jing-Mold Enterprise              | 2         | 0.02%   |
| Avtor                             | 2         | 0.02%   |
| ST-Ericsson                       | 1         | 0.01%   |
| SpringCard                        | 1         | 0.01%   |
| Precise Biometrics                | 1         | 0.01%   |
| Mako Technologies                 | 1         | 0.01%   |
| MagTek                            | 1         | 0.01%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2683      | 26.48%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1606      | 15.85%  |
| Broadcom 5880                                                                | 1092      | 10.78%  |
| Broadcom 58200                                                               | 1007      | 9.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 826       | 8.15%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 622       | 6.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 554       | 5.47%   |
| Lenovo Integrated Smart Card Reader                                          | 485       | 4.79%   |
| O2 Micro Oz776 SmartCard Reader                                              | 101       | 1%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 96        | 0.95%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 69        | 0.68%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 60        | 0.59%   |
| Aladdin Knowledge Systems Token JC                                           | 58        | 0.57%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 52        | 0.51%   |
| Alcor Micro Watchdata W 1981                                                 | 51        | 0.5%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 49        | 0.48%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 44        | 0.43%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 41        | 0.4%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 36        | 0.36%   |
| Aktiv Rutoken lite                                                           | 33        | 0.33%   |
| OmniKey CardMan 3021 / 3121                                                  | 30        | 0.3%    |
| CHERRY SmartCard Reader Keyboard KC 1000 SC                                  | 27        | 0.27%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 25        | 0.25%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 25        | 0.25%   |
| Clay Logic Nitrokey Pro                                                      | 25        | 0.25%   |
| Advanced Card Systems ACR122U                                                | 24        | 0.24%   |
| Bit4id miniLector EVO                                                        | 21        | 0.21%   |
| OmniKey CardMan 1021                                                         | 20        | 0.2%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 20        | 0.2%    |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 16        | 0.16%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 14        | 0.14%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 12        | 0.12%   |
| Aladdin R.D. JaCarta                                                         | 12        | 0.12%   |
| Advanced Card Systems ACR39U                                                 | 12        | 0.12%   |
| OmniKey CardMan 4321                                                         | 11        | 0.11%   |
| OmniKey 3x21 Smart Card Reader                                               | 11        | 0.11%   |
| VASCO Data Security International DIGIPASS 870                               | 10        | 0.1%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 10        | 0.1%    |
| Athena Smartcard Solutions ASEDrive CCID                                     | 10        | 0.1%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 9         | 0.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 176190    | 70.11%  |
| 1     | 59979     | 23.87%  |
| 2     | 11940     | 4.75%   |
| 3     | 2083      | 0.83%   |
| 4     | 667       | 0.27%   |
| 5     | 234       | 0.09%   |
| 6     | 115       | 0.05%   |
| 7     | 55        | 0.02%   |
| 8     | 30        | 0.01%   |
| 9     | 14        | 0.01%   |
| 10    | 6         | 0.002%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 23773     | 26.46%  |
| Graphics card            | 22972     | 25.57%  |
| Net/wireless             | 10924     | 12.16%  |
| Chipcard                 | 8733      | 9.72%   |
| Multimedia controller    | 5614      | 6.25%   |
| Communication controller | 3969      | 4.42%   |
| Camera                   | 2535      | 2.82%   |
| Bluetooth                | 2519      | 2.8%    |
| Unassigned class         | 2072      | 2.31%   |
| Sound                    | 1491      | 1.66%   |
| Storage                  | 1291      | 1.44%   |
| Net/ethernet             | 909       | 1.01%   |
| Card reader              | 820       | 0.91%   |
| Network                  | 523       | 0.58%   |
| Modem                    | 458       | 0.51%   |
| Flash memory             | 279       | 0.31%   |
| Storage/raid             | 271       | 0.3%    |
| Dvb card                 | 170       | 0.19%   |
| Storage/ide              | 152       | 0.17%   |
| Firewire controller      | 134       | 0.15%   |
| Storage/nvme             | 58        | 0.06%   |
| Storage/ata              | 57        | 0.06%   |
| Tv card                  | 46        | 0.05%   |
| Wireless                 | 32        | 0.04%   |
| Video                    | 21        | 0.02%   |
| Unclassified device      | 18        | 0.02%   |

