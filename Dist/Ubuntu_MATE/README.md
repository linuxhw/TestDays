Ubuntu MATE - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_MATE/Desktop/README.md) and [notebooks](/Dist/Ubuntu_MATE/Notebook/README.md).

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

Total: 2877

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Notebook      | NJx0MU                      | Notebook    | [1a436745ab](https://linux-hardware.org/?probe=1a436745ab) | Jan 06, 2025 |
| Notebook      | NJx0MU                      | Notebook    | [67d6f124c9](https://linux-hardware.org/?probe=67d6f124c9) | Jan 06, 2025 |
| HP            | Pavilion g6                 | Notebook    | [909d7c69b5](https://linux-hardware.org/?probe=909d7c69b5) | Jan 05, 2025 |
| HP            | Pavilion g6                 | Notebook    | [ef9ad1fe50](https://linux-hardware.org/?probe=ef9ad1fe50) | Jan 05, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [adb5d55cf4](https://linux-hardware.org/?probe=adb5d55cf4) | Jan 04, 2025 |
| Supermicro    | X7SPA-HF                    | Desktop     | [6239b93b09](https://linux-hardware.org/?probe=6239b93b09) | Jan 03, 2025 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [88e255ba8a](https://linux-hardware.org/?probe=88e255ba8a) | Jan 03, 2025 |
| Dell          | Inspiron 5567               | Notebook    | [786e67f683](https://linux-hardware.org/?probe=786e67f683) | Jan 02, 2025 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9829e4ea09](https://linux-hardware.org/?probe=9829e4ea09) | Jan 01, 2025 |
| Lenovo        | IdeaPad U510 4941           | Notebook    | [78a774dc27](https://linux-hardware.org/?probe=78a774dc27) | Jan 01, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [90cec85bd7](https://linux-hardware.org/?probe=90cec85bd7) | Dec 30, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [9e7734f37f](https://linux-hardware.org/?probe=9e7734f37f) | Dec 30, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [65d462ae1d](https://linux-hardware.org/?probe=65d462ae1d) | Dec 30, 2024 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [fe49d94f48](https://linux-hardware.org/?probe=fe49d94f48) | Dec 30, 2024 |
| Fujitsu       | D3064-A1 S26361-D3064-A1    | Desktop     | [0f84cbbee8](https://linux-hardware.org/?probe=0f84cbbee8) | Dec 30, 2024 |
| HP            | Pavilion dv4                | Notebook    | [e09129add9](https://linux-hardware.org/?probe=e09129add9) | Dec 30, 2024 |
| Dell          | Inspiron 5567               | Notebook    | [8aea47fff9](https://linux-hardware.org/?probe=8aea47fff9) | Dec 29, 2024 |
| HP            | 8462                        | Desktop     | [d0e8315b62](https://linux-hardware.org/?probe=d0e8315b62) | Dec 28, 2024 |
| Dell          | Latitude 3410               | Notebook    | [d884cebf94](https://linux-hardware.org/?probe=d884cebf94) | Dec 27, 2024 |
| Dell          | 0M858N A01                  | Desktop     | [8378333655](https://linux-hardware.org/?probe=8378333655) | Dec 27, 2024 |
| MSI           | MS-6701                     | Desktop     | [d356deb17b](https://linux-hardware.org/?probe=d356deb17b) | Dec 25, 2024 |
| MSI           | MS-6701                     | Desktop     | [0ab268cc0a](https://linux-hardware.org/?probe=0ab268cc0a) | Dec 25, 2024 |
| MSI           | Stealth GS66 12UHS          | Notebook    | [4634dcf259](https://linux-hardware.org/?probe=4634dcf259) | Dec 25, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [362b9364dd](https://linux-hardware.org/?probe=362b9364dd) | Dec 24, 2024 |
| HP            | 8462                        | Desktop     | [4837f873a4](https://linux-hardware.org/?probe=4837f873a4) | Dec 23, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [0f16f634ba](https://linux-hardware.org/?probe=0f16f634ba) | Dec 22, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [8768679ad7](https://linux-hardware.org/?probe=8768679ad7) | Dec 22, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [2dd67e963d](https://linux-hardware.org/?probe=2dd67e963d) | Dec 19, 2024 |
| Lenovo        | ThinkPad T430 23498F0       | Notebook    | [4b2306ff9f](https://linux-hardware.org/?probe=4b2306ff9f) | Dec 19, 2024 |
| HP            | EliteBook 8440p             | Notebook    | [d711c652eb](https://linux-hardware.org/?probe=d711c652eb) | Dec 19, 2024 |
| Dell          | OptiPlex 5050               | Desktop     | [78724eea62](https://linux-hardware.org/?probe=78724eea62) | Dec 18, 2024 |
| Lenovo        | ThinkPad MFG_IN_GO          | Notebook    | [3c0105bc7f](https://linux-hardware.org/?probe=3c0105bc7f) | Dec 16, 2024 |
| Toshiba       | Satellite C50D-A-133        | Notebook    | [c5dba8548d](https://linux-hardware.org/?probe=c5dba8548d) | Dec 14, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [28c96de064](https://linux-hardware.org/?probe=28c96de064) | Dec 12, 2024 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [88623ffcc4](https://linux-hardware.org/?probe=88623ffcc4) | Dec 10, 2024 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [12f7f54a9f](https://linux-hardware.org/?probe=12f7f54a9f) | Dec 09, 2024 |
| HP            | 8266                        | Desktop     | [ba5135167e](https://linux-hardware.org/?probe=ba5135167e) | Dec 09, 2024 |
| Medion        | MS-7797                     | Desktop     | [5adf732da0](https://linux-hardware.org/?probe=5adf732da0) | Dec 09, 2024 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [0f1748d404](https://linux-hardware.org/?probe=0f1748d404) | Dec 08, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [13635a905e](https://linux-hardware.org/?probe=13635a905e) | Dec 06, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [645f715c2f](https://linux-hardware.org/?probe=645f715c2f) | Dec 06, 2024 |
| Dell          | Latitude E6410              | Notebook    | [9e58a81f87](https://linux-hardware.org/?probe=9e58a81f87) | Dec 02, 2024 |
| HP            | 158A                        | Desktop     | [ba061366cc](https://linux-hardware.org/?probe=ba061366cc) | Dec 02, 2024 |
| Acer          | Aspire 5920G                | Notebook    | [3ac75edf3a](https://linux-hardware.org/?probe=3ac75edf3a) | Nov 30, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [9e1536f755](https://linux-hardware.org/?probe=9e1536f755) | Nov 28, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [4dd4121257](https://linux-hardware.org/?probe=4dd4121257) | Nov 28, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [b17bd0994c](https://linux-hardware.org/?probe=b17bd0994c) | Nov 28, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [3d32552ab3](https://linux-hardware.org/?probe=3d32552ab3) | Nov 28, 2024 |
| Samsung       | R530/R730                   | Notebook    | [8d57e47bb7](https://linux-hardware.org/?probe=8d57e47bb7) | Nov 25, 2024 |
| Samsung       | R530/R730                   | Notebook    | [924a6a8572](https://linux-hardware.org/?probe=924a6a8572) | Nov 25, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [20e57b7eca](https://linux-hardware.org/?probe=20e57b7eca) | Nov 24, 2024 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [8af2b2f494](https://linux-hardware.org/?probe=8af2b2f494) | Nov 24, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [76c5e79d46](https://linux-hardware.org/?probe=76c5e79d46) | Nov 23, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [99d9097a4b](https://linux-hardware.org/?probe=99d9097a4b) | Nov 23, 2024 |
| AZW           | MINI S                      | Desktop     | [0fc266941c](https://linux-hardware.org/?probe=0fc266941c) | Nov 22, 2024 |
| HP            | 8266                        | Desktop     | [59a635aa78](https://linux-hardware.org/?probe=59a635aa78) | Nov 21, 2024 |
| MSI           | MS-B120                     | Mini pc     | [3da903450a](https://linux-hardware.org/?probe=3da903450a) | Nov 20, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M30... | Notebook    | [70f739c61f](https://linux-hardware.org/?probe=70f739c61f) | Nov 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c995846597](https://linux-hardware.org/?probe=c995846597) | Nov 19, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [2f52802556](https://linux-hardware.org/?probe=2f52802556) | Nov 19, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [61d8a1bc22](https://linux-hardware.org/?probe=61d8a1bc22) | Nov 17, 2024 |
| Dell          | 049G3W A02                  | Desktop     | [be710ef5d4](https://linux-hardware.org/?probe=be710ef5d4) | Nov 14, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [eec78bb1ce](https://linux-hardware.org/?probe=eec78bb1ce) | Nov 13, 2024 |
| Dell          | Latitude 7370               | Notebook    | [ea82f5f399](https://linux-hardware.org/?probe=ea82f5f399) | Nov 13, 2024 |
| Acer          | Aspire 5050                 | Notebook    | [eac5cc26a2](https://linux-hardware.org/?probe=eac5cc26a2) | Nov 10, 2024 |
| Dell          | 0C4H12 A00                  | Desktop     | [53891c4e7e](https://linux-hardware.org/?probe=53891c4e7e) | Nov 10, 2024 |
| System76      | Darter Pro                  | Notebook    | [757d9cd509](https://linux-hardware.org/?probe=757d9cd509) | Nov 09, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [9088fca13d](https://linux-hardware.org/?probe=9088fca13d) | Nov 09, 2024 |
| Dell          | 0HMX8D A01                  | Desktop     | [715b506ea4](https://linux-hardware.org/?probe=715b506ea4) | Nov 08, 2024 |
| Lenovo        | ThinkPad L560 20F2S2GW00    | Notebook    | [3c7901a5c1](https://linux-hardware.org/?probe=3c7901a5c1) | Nov 06, 2024 |
| Lenovo        | ThinkPad L560 20F2S2GW00    | Notebook    | [811c3c90ef](https://linux-hardware.org/?probe=811c3c90ef) | Nov 06, 2024 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [90b574e0b2](https://linux-hardware.org/?probe=90b574e0b2) | Nov 04, 2024 |
| Sony          | VPCS13V9E                   | Notebook    | [5f8c9da2ec](https://linux-hardware.org/?probe=5f8c9da2ec) | Nov 03, 2024 |
| Sony          | VPCS13V9E                   | Notebook    | [5f8592eebb](https://linux-hardware.org/?probe=5f8592eebb) | Nov 03, 2024 |
| HP            | ProBook 450 G1              | Notebook    | [1534dbb5c0](https://linux-hardware.org/?probe=1534dbb5c0) | Nov 02, 2024 |
| ASUSTek       | T304UA                      | Tablet      | [da6e013777](https://linux-hardware.org/?probe=da6e013777) | Nov 02, 2024 |
| Dell          | Latitude 7370               | Notebook    | [b5426b24e2](https://linux-hardware.org/?probe=b5426b24e2) | Nov 02, 2024 |
| ASUSTek       | K52F                        | Notebook    | [dd3d46e1f9](https://linux-hardware.org/?probe=dd3d46e1f9) | Oct 31, 2024 |
| ASUSTek       | K52F                        | Notebook    | [74d8af6252](https://linux-hardware.org/?probe=74d8af6252) | Oct 31, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [ad57f56740](https://linux-hardware.org/?probe=ad57f56740) | Oct 31, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [8d959cb7c1](https://linux-hardware.org/?probe=8d959cb7c1) | Oct 30, 2024 |
| Dell          | 0HMX8D A01                  | Desktop     | [f1a37fae52](https://linux-hardware.org/?probe=f1a37fae52) | Oct 30, 2024 |
| Lenovo        | ThinkPad T510 4349BD8       | Notebook    | [2e8c236061](https://linux-hardware.org/?probe=2e8c236061) | Oct 30, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [d05dc21a14](https://linux-hardware.org/?probe=d05dc21a14) | Oct 26, 2024 |
| MSI           | PH67A-C43                   | Desktop     | [d67321fbb9](https://linux-hardware.org/?probe=d67321fbb9) | Oct 25, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [e106b29eab](https://linux-hardware.org/?probe=e106b29eab) | Oct 24, 2024 |
| Gigabyte      | G41MT-S2                    | Desktop     | [7705d36266](https://linux-hardware.org/?probe=7705d36266) | Oct 23, 2024 |
| HP            | Notebook                    | Notebook    | [00a772808d](https://linux-hardware.org/?probe=00a772808d) | Oct 23, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [16c95d4388](https://linux-hardware.org/?probe=16c95d4388) | Oct 22, 2024 |
| ASRock        | A780LM-S                    | Desktop     | [0f911c2c87](https://linux-hardware.org/?probe=0f911c2c87) | Oct 22, 2024 |
| MSI           | MS-B120                     | Mini pc     | [41da7e57a6](https://linux-hardware.org/?probe=41da7e57a6) | Oct 22, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [e3f6b0568c](https://linux-hardware.org/?probe=e3f6b0568c) | Oct 21, 2024 |
| MACHINIST     | E5-D8-MAX V1.1              | Desktop     | [3dff6bbcdb](https://linux-hardware.org/?probe=3dff6bbcdb) | Oct 20, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [637e502045](https://linux-hardware.org/?probe=637e502045) | Oct 20, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [d99d978d2b](https://linux-hardware.org/?probe=d99d978d2b) | Oct 20, 2024 |
| HP            | ProLiant DL360 G7           | Server      | [c639346a52](https://linux-hardware.org/?probe=c639346a52) | Oct 19, 2024 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [957f60f34e](https://linux-hardware.org/?probe=957f60f34e) | Oct 19, 2024 |
| Microsoft     | Surface Go 2                | Tablet      | [bbf8632ea8](https://linux-hardware.org/?probe=bbf8632ea8) | Oct 18, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [b8119f542b](https://linux-hardware.org/?probe=b8119f542b) | Oct 18, 2024 |
| Dell          | XPS 13 9310                 | Notebook    | [92736b8de6](https://linux-hardware.org/?probe=92736b8de6) | Oct 18, 2024 |
| HP            | x2 210 G2                   | Tablet      | [ead38d715f](https://linux-hardware.org/?probe=ead38d715f) | Oct 17, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0bdda39e37](https://linux-hardware.org/?probe=0bdda39e37) | Oct 16, 2024 |
| HP            | 8299                        | Desktop     | [02b17bc8ce](https://linux-hardware.org/?probe=02b17bc8ce) | Oct 16, 2024 |
| ASUSTek       | M4A78-E                     | Desktop     | [2c29f9d339](https://linux-hardware.org/?probe=2c29f9d339) | Oct 15, 2024 |
| HP            | Pavilion dv8                | Notebook    | [21df937346](https://linux-hardware.org/?probe=21df937346) | Oct 14, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [78a5ceba6e](https://linux-hardware.org/?probe=78a5ceba6e) | Oct 12, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [ad611bc852](https://linux-hardware.org/?probe=ad611bc852) | Oct 12, 2024 |
| Lenovo        | ThinkPad T440p 20AWS4N90... | Notebook    | [367e64b3ed](https://linux-hardware.org/?probe=367e64b3ed) | Oct 12, 2024 |
| HP            | 8299                        | Desktop     | [7b4baeb3bb](https://linux-hardware.org/?probe=7b4baeb3bb) | Oct 11, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [4a7041c67c](https://linux-hardware.org/?probe=4a7041c67c) | Oct 11, 2024 |
| HP            | 82F1                        | Desktop     | [cb91c8b3a6](https://linux-hardware.org/?probe=cb91c8b3a6) | Oct 11, 2024 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [0e5cca17fe](https://linux-hardware.org/?probe=0e5cca17fe) | Oct 10, 2024 |
| Lenovo        | B51-80 80LM                 | Notebook    | [aa39bd173c](https://linux-hardware.org/?probe=aa39bd173c) | Oct 09, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [36203d895d](https://linux-hardware.org/?probe=36203d895d) | Oct 08, 2024 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [f039fec17f](https://linux-hardware.org/?probe=f039fec17f) | Oct 08, 2024 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [031f820ae5](https://linux-hardware.org/?probe=031f820ae5) | Oct 07, 2024 |
| Dell          | XPS L322X                   | Notebook    | [ebe83a8923](https://linux-hardware.org/?probe=ebe83a8923) | Oct 07, 2024 |
| Intel         | H61                         | Desktop     | [f7d3219060](https://linux-hardware.org/?probe=f7d3219060) | Oct 07, 2024 |
| Intel         | H61                         | Desktop     | [bac391f6ce](https://linux-hardware.org/?probe=bac391f6ce) | Oct 07, 2024 |
| MSI           | PRO Z790-A MAX WIFI         | Desktop     | [154b1e5c1b](https://linux-hardware.org/?probe=154b1e5c1b) | Oct 07, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [6be09afc6e](https://linux-hardware.org/?probe=6be09afc6e) | Oct 05, 2024 |
| ASUSTek       | X550LN                      | Notebook    | [61239b6939](https://linux-hardware.org/?probe=61239b6939) | Oct 03, 2024 |
| ASUSTek       | X550LN                      | Notebook    | [aa1afeaff4](https://linux-hardware.org/?probe=aa1afeaff4) | Oct 03, 2024 |
| Acer          | EQ45M                       | Desktop     | [0d9b3aab5f](https://linux-hardware.org/?probe=0d9b3aab5f) | Oct 02, 2024 |
| Dell          | Latitude D830               | Notebook    | [f34a4dda6a](https://linux-hardware.org/?probe=f34a4dda6a) | Oct 01, 2024 |
| Dell          | Latitude E7440              | Notebook    | [e214523782](https://linux-hardware.org/?probe=e214523782) | Oct 01, 2024 |
| Intel         | X99                         | Desktop     | [02e8e3a503](https://linux-hardware.org/?probe=02e8e3a503) | Oct 01, 2024 |
| SZMZ          | X99M-G2                     | Desktop     | [382a390721](https://linux-hardware.org/?probe=382a390721) | Oct 01, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [6e019fd901](https://linux-hardware.org/?probe=6e019fd901) | Sep 30, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [ef3968a3cc](https://linux-hardware.org/?probe=ef3968a3cc) | Sep 30, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [e4398bf85e](https://linux-hardware.org/?probe=e4398bf85e) | Sep 30, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [6629e094c4](https://linux-hardware.org/?probe=6629e094c4) | Sep 28, 2024 |
| MSI           | MS-B120                     | Mini pc     | [fa5df37ed3](https://linux-hardware.org/?probe=fa5df37ed3) | Sep 28, 2024 |
| ASUSTek       | UX305FA                     | Notebook    | [cab58b19a5](https://linux-hardware.org/?probe=cab58b19a5) | Sep 27, 2024 |
| HP            | 8266                        | Desktop     | [e604dee3de](https://linux-hardware.org/?probe=e604dee3de) | Sep 26, 2024 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [4422a8ed1b](https://linux-hardware.org/?probe=4422a8ed1b) | Sep 26, 2024 |
| Acer          | Aspire 8735                 | Notebook    | [1e9253098c](https://linux-hardware.org/?probe=1e9253098c) | Sep 24, 2024 |
| MSI           | H410M PRO                   | Desktop     | [6644a178d7](https://linux-hardware.org/?probe=6644a178d7) | Sep 22, 2024 |
| MouseCompu... | W110ER                      | Notebook    | [8ec07c61c5](https://linux-hardware.org/?probe=8ec07c61c5) | Sep 22, 2024 |
| Gigabyte      | H67MA-UD2H-B3               | Desktop     | [21b8f6e55c](https://linux-hardware.org/?probe=21b8f6e55c) | Sep 21, 2024 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [baed1e9059](https://linux-hardware.org/?probe=baed1e9059) | Sep 17, 2024 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4f85171760](https://linux-hardware.org/?probe=4f85171760) | Sep 17, 2024 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | Notebook    | [9146d15a3b](https://linux-hardware.org/?probe=9146d15a3b) | Sep 16, 2024 |
| Gateway       | NV55C                       | Notebook    | [151ce02b0c](https://linux-hardware.org/?probe=151ce02b0c) | Sep 16, 2024 |
| Gateway       | NV55C                       | Notebook    | [f7170c1236](https://linux-hardware.org/?probe=f7170c1236) | Sep 16, 2024 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [0ecccff1eb](https://linux-hardware.org/?probe=0ecccff1eb) | Sep 16, 2024 |
| HP            | 8298                        | Desktop     | [33696766f2](https://linux-hardware.org/?probe=33696766f2) | Sep 15, 2024 |
| HP            | ProBook 4710s               | Notebook    | [e6ca3a8cfc](https://linux-hardware.org/?probe=e6ca3a8cfc) | Sep 13, 2024 |
| Lenovo        | ThinkPad E490 20N8005AAD    | Notebook    | [4e5ac9e97e](https://linux-hardware.org/?probe=4e5ac9e97e) | Sep 13, 2024 |
| Lenovo        | B50-70 20384                | Notebook    | [1f0591024e](https://linux-hardware.org/?probe=1f0591024e) | Sep 12, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [730aa21a44](https://linux-hardware.org/?probe=730aa21a44) | Sep 12, 2024 |
| MSI           | MS-B120                     | Mini pc     | [92b13d7a99](https://linux-hardware.org/?probe=92b13d7a99) | Sep 11, 2024 |
| Fujitsu       | D3502-A1 S26361-D3502-A1    | Desktop     | [8b9b0365cf](https://linux-hardware.org/?probe=8b9b0365cf) | Sep 10, 2024 |
| Gigabyte      | Z87MX-D3H-CF                | Desktop     | [72ced99036](https://linux-hardware.org/?probe=72ced99036) | Sep 10, 2024 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [846c96bd78](https://linux-hardware.org/?probe=846c96bd78) | Sep 10, 2024 |
| Lenovo        | ThinkPad P53 20QQS2Q500     | Notebook    | [f59c986142](https://linux-hardware.org/?probe=f59c986142) | Sep 08, 2024 |
| Lenovo        | ThinkPad P53 20QQS2Q500     | Notebook    | [036064fb7d](https://linux-hardware.org/?probe=036064fb7d) | Sep 08, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [759b1d1403](https://linux-hardware.org/?probe=759b1d1403) | Sep 07, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [7582b12cfa](https://linux-hardware.org/?probe=7582b12cfa) | Sep 07, 2024 |
| MSI           | MS-B120                     | Mini pc     | [7f4be3e611](https://linux-hardware.org/?probe=7f4be3e611) | Sep 07, 2024 |
| ASUSTek       | A88X-PRO                    | Desktop     | [8162d57622](https://linux-hardware.org/?probe=8162d57622) | Sep 06, 2024 |
| ASUSTek       | A88X-PRO                    | Desktop     | [397c9cafae](https://linux-hardware.org/?probe=397c9cafae) | Sep 06, 2024 |
| ASUSTek       | P6T SE                      | Desktop     | [42f319ff6b](https://linux-hardware.org/?probe=42f319ff6b) | Sep 05, 2024 |
| ASUSTek       | X550LN                      | Notebook    | [ce640045ef](https://linux-hardware.org/?probe=ce640045ef) | Sep 03, 2024 |
| HP            | 0A64h                       | Desktop     | [235a192f9e](https://linux-hardware.org/?probe=235a192f9e) | Sep 03, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [873b9f8491](https://linux-hardware.org/?probe=873b9f8491) | Aug 31, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [bb66d6b606](https://linux-hardware.org/?probe=bb66d6b606) | Aug 31, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [4c3b6cd503](https://linux-hardware.org/?probe=4c3b6cd503) | Aug 30, 2024 |
| Dell          | Precision M4800             | Notebook    | [a4be7a565a](https://linux-hardware.org/?probe=a4be7a565a) | Aug 29, 2024 |
| Dell          | Precision M4800             | Notebook    | [825bca67dc](https://linux-hardware.org/?probe=825bca67dc) | Aug 29, 2024 |
| ASRock        | Z77E-ITX                    | Desktop     | [142d4baaa5](https://linux-hardware.org/?probe=142d4baaa5) | Aug 28, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d588f28882](https://linux-hardware.org/?probe=d588f28882) | Aug 28, 2024 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [90fc0ae285](https://linux-hardware.org/?probe=90fc0ae285) | Aug 28, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8c4be8ba0d](https://linux-hardware.org/?probe=8c4be8ba0d) | Aug 27, 2024 |
| ASUSTek       | K52F                        | Notebook    | [7a928c36ce](https://linux-hardware.org/?probe=7a928c36ce) | Aug 26, 2024 |
| Dell          | Latitude 7410               | Notebook    | [a7eb8d9d58](https://linux-hardware.org/?probe=a7eb8d9d58) | Aug 26, 2024 |
| MSI           | MS-B120                     | Mini pc     | [565c06e5c7](https://linux-hardware.org/?probe=565c06e5c7) | Aug 25, 2024 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [5cd382e3a4](https://linux-hardware.org/?probe=5cd382e3a4) | Aug 25, 2024 |
| Dell          | Latitude 3420               | Notebook    | [f13d050d62](https://linux-hardware.org/?probe=f13d050d62) | Aug 21, 2024 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [84c6c853c6](https://linux-hardware.org/?probe=84c6c853c6) | Aug 19, 2024 |
| HP            | 470 17 inch G10 Notebook... | Notebook    | [1b5b2201b3](https://linux-hardware.org/?probe=1b5b2201b3) | Aug 18, 2024 |
| HP            | 470 17 inch G10 Notebook... | Notebook    | [f96763850e](https://linux-hardware.org/?probe=f96763850e) | Aug 18, 2024 |
| Mini PC       | Rev ADLN62                  | Mini pc     | [2f5d9a6f7e](https://linux-hardware.org/?probe=2f5d9a6f7e) | Aug 16, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [4fd40665fe](https://linux-hardware.org/?probe=4fd40665fe) | Aug 15, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [752565b32e](https://linux-hardware.org/?probe=752565b32e) | Aug 15, 2024 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [8fadf1536a](https://linux-hardware.org/?probe=8fadf1536a) | Aug 15, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [72a76100c0](https://linux-hardware.org/?probe=72a76100c0) | Aug 14, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [8c4795ad22](https://linux-hardware.org/?probe=8c4795ad22) | Aug 13, 2024 |
| Intel         | 945GCT-M                    | Desktop     | [105ce7af34](https://linux-hardware.org/?probe=105ce7af34) | Aug 10, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [58929eebee](https://linux-hardware.org/?probe=58929eebee) | Aug 09, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [b69646717f](https://linux-hardware.org/?probe=b69646717f) | Aug 07, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [1130f68b30](https://linux-hardware.org/?probe=1130f68b30) | Aug 04, 2024 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [6aac77b86c](https://linux-hardware.org/?probe=6aac77b86c) | Aug 04, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [3cd7fba406](https://linux-hardware.org/?probe=3cd7fba406) | Aug 02, 2024 |
| HP            | EliteBook 8570p             | Notebook    | [18231f879f](https://linux-hardware.org/?probe=18231f879f) | Jul 31, 2024 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [a54338842b](https://linux-hardware.org/?probe=a54338842b) | Jul 31, 2024 |
| Dell          | XPS L322X                   | Notebook    | [8b14979f7c](https://linux-hardware.org/?probe=8b14979f7c) | Jul 30, 2024 |
| Dell          | XPS L322X                   | Notebook    | [bf4c97865c](https://linux-hardware.org/?probe=bf4c97865c) | Jul 30, 2024 |
| Lenovo        | ThinkPad L512 2597W1R       | Notebook    | [30c12bace2](https://linux-hardware.org/?probe=30c12bace2) | Jul 30, 2024 |
| ASRock        | Z690 Pro RS                 | Desktop     | [e3765bd2ff](https://linux-hardware.org/?probe=e3765bd2ff) | Jul 30, 2024 |
| Gigabyte      | B450M K-CF                  | Desktop     | [f223f80f64](https://linux-hardware.org/?probe=f223f80f64) | Jul 30, 2024 |
| Fujitsu       | LIFEBOOK U748               | Notebook    | [8b17202e4d](https://linux-hardware.org/?probe=8b17202e4d) | Jul 29, 2024 |
| Dell          | Precision M4800             | Notebook    | [50f7d3e735](https://linux-hardware.org/?probe=50f7d3e735) | Jul 28, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [34e2d2c812](https://linux-hardware.org/?probe=34e2d2c812) | Jul 27, 2024 |
| MSI           | MS-B120                     | Mini pc     | [cef31a325c](https://linux-hardware.org/?probe=cef31a325c) | Jul 27, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [ba43243222](https://linux-hardware.org/?probe=ba43243222) | Jul 26, 2024 |
| HP            | 2AF7                        | Desktop     | [09f9029668](https://linux-hardware.org/?probe=09f9029668) | Jul 25, 2024 |
| HP            | 2AF7                        | Desktop     | [2d3a654d52](https://linux-hardware.org/?probe=2d3a654d52) | Jul 25, 2024 |
| Unknown       | Unknown                     | Notebook    | [7bf0973685](https://linux-hardware.org/?probe=7bf0973685) | Jul 24, 2024 |
| HP            | Presario CQ62               | Notebook    | [51d98b56a6](https://linux-hardware.org/?probe=51d98b56a6) | Jul 23, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [b1883fc0b9](https://linux-hardware.org/?probe=b1883fc0b9) | Jul 20, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [938ac7f923](https://linux-hardware.org/?probe=938ac7f923) | Jul 20, 2024 |
| Lenovo        | U310                        | Notebook    | [bc65662bc6](https://linux-hardware.org/?probe=bc65662bc6) | Jul 20, 2024 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [6f1800773c](https://linux-hardware.org/?probe=6f1800773c) | Jul 19, 2024 |
| Dell          | 040DDP A01                  | Desktop     | [bf9438a172](https://linux-hardware.org/?probe=bf9438a172) | Jul 17, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21M50... | Notebook    | [4ede9f000b](https://linux-hardware.org/?probe=4ede9f000b) | Jul 17, 2024 |
| System76      | Pangolin                    | Notebook    | [2f97d7a936](https://linux-hardware.org/?probe=2f97d7a936) | Jul 16, 2024 |
| Dell          | Latitude E6400              | Notebook    | [6902c998ab](https://linux-hardware.org/?probe=6902c998ab) | Jul 16, 2024 |
| Unknown       | Unknown                     | Desktop     | [59c3b16f4d](https://linux-hardware.org/?probe=59c3b16f4d) | Jul 14, 2024 |
| HP            | EliteBook 820 G1            | Notebook    | [fd49810070](https://linux-hardware.org/?probe=fd49810070) | Jul 14, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [ff13f5f94f](https://linux-hardware.org/?probe=ff13f5f94f) | Jul 11, 2024 |
| Gigabyte      | B550M K                     | Desktop     | [c4a4380ddc](https://linux-hardware.org/?probe=c4a4380ddc) | Jul 11, 2024 |
| Medion        | P8610                       | Notebook    | [a39e7058a3](https://linux-hardware.org/?probe=a39e7058a3) | Jul 09, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [8bc58488a8](https://linux-hardware.org/?probe=8bc58488a8) | Jul 09, 2024 |
| Foxconn       | 2ADA                        | Desktop     | [ee229c57c4](https://linux-hardware.org/?probe=ee229c57c4) | Jul 08, 2024 |
| MSI           | MS-B120                     | Mini pc     | [e41e11b1e0](https://linux-hardware.org/?probe=e41e11b1e0) | Jul 07, 2024 |
| Dell          | Inspiron 5566               | Notebook    | [8ccf248b6a](https://linux-hardware.org/?probe=8ccf248b6a) | Jul 07, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [a9ffcc9574](https://linux-hardware.org/?probe=a9ffcc9574) | Jul 07, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [ffbf7e5b14](https://linux-hardware.org/?probe=ffbf7e5b14) | Jul 07, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [d332637cfe](https://linux-hardware.org/?probe=d332637cfe) | Jul 07, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [bca863a045](https://linux-hardware.org/?probe=bca863a045) | Jul 05, 2024 |
| Acer          | AOD270                      | Notebook    | [ed5489a7bb](https://linux-hardware.org/?probe=ed5489a7bb) | Jul 04, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [164247c308](https://linux-hardware.org/?probe=164247c308) | Jul 04, 2024 |
| Gigabyte      | B460 HD3                    | Desktop     | [324898f64e](https://linux-hardware.org/?probe=324898f64e) | Jul 02, 2024 |
| AMI           | Intel                       | Desktop     | [5d8240cda1](https://linux-hardware.org/?probe=5d8240cda1) | Jun 26, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [febacdca60](https://linux-hardware.org/?probe=febacdca60) | Jun 25, 2024 |
| ZOTAC         | ZBOX-EN374070C              | Mini pc     | [71009c6209](https://linux-hardware.org/?probe=71009c6209) | Jun 25, 2024 |
| Dell          | Studio 1558                 | Notebook    | [42102615c5](https://linux-hardware.org/?probe=42102615c5) | Jun 23, 2024 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [db6a8b188d](https://linux-hardware.org/?probe=db6a8b188d) | Jun 23, 2024 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [09ffa0d065](https://linux-hardware.org/?probe=09ffa0d065) | Jun 23, 2024 |
| HP            | Pavilion dv4                | Notebook    | [4d8fa0dcd3](https://linux-hardware.org/?probe=4d8fa0dcd3) | Jun 23, 2024 |
| Dell          | 08NPPY A00                  | Desktop     | [75cff17c2a](https://linux-hardware.org/?probe=75cff17c2a) | Jun 22, 2024 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [d73f02434e](https://linux-hardware.org/?probe=d73f02434e) | Jun 21, 2024 |
| AMI           | Intel                       | Desktop     | [1450c0246f](https://linux-hardware.org/?probe=1450c0246f) | Jun 20, 2024 |
| HP            | Compaq 6715s (GS561AV)      | Notebook    | [858c238b03](https://linux-hardware.org/?probe=858c238b03) | Jun 19, 2024 |
| Dell          | Latitude 5531               | Notebook    | [372b0ebce1](https://linux-hardware.org/?probe=372b0ebce1) | Jun 18, 2024 |
| Dell          | XPS L322X                   | Notebook    | [1af333c86d](https://linux-hardware.org/?probe=1af333c86d) | Jun 18, 2024 |
| Dell          | XPS L322X                   | Notebook    | [34bcf0a790](https://linux-hardware.org/?probe=34bcf0a790) | Jun 18, 2024 |
| Lenovo        | ThinkPad E490 20N80029GE    | Notebook    | [9ef0735764](https://linux-hardware.org/?probe=9ef0735764) | Jun 17, 2024 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [a448de0f44](https://linux-hardware.org/?probe=a448de0f44) | Jun 15, 2024 |
| Dell          | 0MWYPT A02                  | Desktop     | [0188202fa9](https://linux-hardware.org/?probe=0188202fa9) | Jun 14, 2024 |
| Dell          | 0NNNCT A01                  | Desktop     | [9cd3c023df](https://linux-hardware.org/?probe=9cd3c023df) | Jun 13, 2024 |
| HP            | EliteBook 745 G4            | Notebook    | [c317306129](https://linux-hardware.org/?probe=c317306129) | Jun 13, 2024 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [2445a991d8](https://linux-hardware.org/?probe=2445a991d8) | Jun 06, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [75f4137d21](https://linux-hardware.org/?probe=75f4137d21) | Jun 06, 2024 |
| Dell          | 032W55 A03                  | Desktop     | [0bf4dbd092](https://linux-hardware.org/?probe=0bf4dbd092) | Jun 04, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [720d7ca6cb](https://linux-hardware.org/?probe=720d7ca6cb) | May 31, 2024 |
| Gigabyte      | B250M-Gaming 3-CF           | Desktop     | [0429104dcc](https://linux-hardware.org/?probe=0429104dcc) | May 30, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [35684afb98](https://linux-hardware.org/?probe=35684afb98) | May 28, 2024 |
| ASUSTek       | M5A78L LE                   | Desktop     | [5afe282618](https://linux-hardware.org/?probe=5afe282618) | May 27, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [6ec64c0b1c](https://linux-hardware.org/?probe=6ec64c0b1c) | May 27, 2024 |
| HP            | 355 G2                      | Notebook    | [3a458e83e5](https://linux-hardware.org/?probe=3a458e83e5) | May 26, 2024 |
| HP            | 355 G2                      | Notebook    | [8b28adff93](https://linux-hardware.org/?probe=8b28adff93) | May 26, 2024 |
| Dell          | XPS 15 9560                 | Notebook    | [134bad9ba1](https://linux-hardware.org/?probe=134bad9ba1) | May 25, 2024 |
| Acer          | Aspire A515-54              | Notebook    | [fbfb9ee390](https://linux-hardware.org/?probe=fbfb9ee390) | May 24, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [9bc61751b1](https://linux-hardware.org/?probe=9bc61751b1) | May 24, 2024 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [5618803794](https://linux-hardware.org/?probe=5618803794) | May 21, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [36eb3289fa](https://linux-hardware.org/?probe=36eb3289fa) | May 17, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [a667660a0c](https://linux-hardware.org/?probe=a667660a0c) | May 17, 2024 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [146a53575b](https://linux-hardware.org/?probe=146a53575b) | May 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [1d905f7200](https://linux-hardware.org/?probe=1d905f7200) | May 15, 2024 |
| Lenovo        | ThinkStation S30 0606AD5    | Desktop     | [81204f95a0](https://linux-hardware.org/?probe=81204f95a0) | May 15, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [2ddbbe35d9](https://linux-hardware.org/?probe=2ddbbe35d9) | May 14, 2024 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [2c44032705](https://linux-hardware.org/?probe=2c44032705) | May 12, 2024 |
| ASUSTek       | A6Rp                        | Notebook    | [6cf464d3ec](https://linux-hardware.org/?probe=6cf464d3ec) | May 12, 2024 |
| Acer          | Extensa 2540                | Notebook    | [f76fc7e870](https://linux-hardware.org/?probe=f76fc7e870) | May 11, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [2d829398cc](https://linux-hardware.org/?probe=2d829398cc) | May 11, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [ee086eec1f](https://linux-hardware.org/?probe=ee086eec1f) | May 09, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [58b9bbc4d6](https://linux-hardware.org/?probe=58b9bbc4d6) | May 08, 2024 |
| BESSTAR Te... | GB1B                        | Mini pc     | [14c3adea64](https://linux-hardware.org/?probe=14c3adea64) | May 08, 2024 |
| Intel         | STCK1A32WFC H67490-302      | Notebook    | [51c75f3848](https://linux-hardware.org/?probe=51c75f3848) | May 08, 2024 |
| MSI           | MS-B120                     | Mini pc     | [29451ebbbb](https://linux-hardware.org/?probe=29451ebbbb) | May 08, 2024 |
| ASUSTek       | X550LN                      | Notebook    | [b139a58ea9](https://linux-hardware.org/?probe=b139a58ea9) | May 07, 2024 |
| eMachines     | WMCP61M                     | Desktop     | [54b1a18c59](https://linux-hardware.org/?probe=54b1a18c59) | May 06, 2024 |
| Gigabyte      | B75M-D3V                    | Desktop     | [52037a51a0](https://linux-hardware.org/?probe=52037a51a0) | May 06, 2024 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [1820a973e3](https://linux-hardware.org/?probe=1820a973e3) | May 05, 2024 |
| Lenovo        | ThinkPad X240 20ALA08VRT    | Notebook    | [b894f49df3](https://linux-hardware.org/?probe=b894f49df3) | May 05, 2024 |
| Lenovo        | ThinkPad L512 2597W1R       | Notebook    | [d7cb3b5ddd](https://linux-hardware.org/?probe=d7cb3b5ddd) | May 05, 2024 |
| ASUSTek       | E5402WHA                    | All in one  | [899d2f931f](https://linux-hardware.org/?probe=899d2f931f) | May 04, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [151ab0d8e9](https://linux-hardware.org/?probe=151ab0d8e9) | May 01, 2024 |
| HP            | ENVY m7 Notebook            | Notebook    | [4403370d84](https://linux-hardware.org/?probe=4403370d84) | Apr 28, 2024 |
| Dell          | Latitude 5420               | Notebook    | [1fa9f586bb](https://linux-hardware.org/?probe=1fa9f586bb) | Apr 27, 2024 |
| Dell          | Latitude 5420               | Notebook    | [5c878504f5](https://linux-hardware.org/?probe=5c878504f5) | Apr 27, 2024 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [1680c3ad15](https://linux-hardware.org/?probe=1680c3ad15) | Apr 27, 2024 |
| MSI           | MS-B120                     | Mini pc     | [8c52f15119](https://linux-hardware.org/?probe=8c52f15119) | Apr 23, 2024 |
| Morshow       | v1.0                        | Mini pc     | [cc244a6fc6](https://linux-hardware.org/?probe=cc244a6fc6) | Apr 22, 2024 |
| Lenovo        | ThinkPad W520 4284HP9       | Notebook    | [3fa1ba6009](https://linux-hardware.org/?probe=3fa1ba6009) | Apr 22, 2024 |
| Morshow       | v1.0                        | Mini pc     | [e4198c0587](https://linux-hardware.org/?probe=e4198c0587) | Apr 22, 2024 |
| Lenovo        | G70-70 80HW                 | Notebook    | [73f307b60b](https://linux-hardware.org/?probe=73f307b60b) | Apr 20, 2024 |
| ASRock        | B650E Taichi                | Desktop     | [cdd2468f64](https://linux-hardware.org/?probe=cdd2468f64) | Apr 20, 2024 |
| AMI           | Unknown                     | Notebook    | [8330483e6e](https://linux-hardware.org/?probe=8330483e6e) | Apr 20, 2024 |
| Toshiba       | STI 001387                  | Desktop     | [240e193806](https://linux-hardware.org/?probe=240e193806) | Apr 20, 2024 |
| Gigabyte      | H97M-D3H                    | Desktop     | [15a0f07250](https://linux-hardware.org/?probe=15a0f07250) | Apr 20, 2024 |
| HP            | ProBook 470 G1              | Notebook    | [a400b6efad](https://linux-hardware.org/?probe=a400b6efad) | Apr 17, 2024 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [d7337f7684](https://linux-hardware.org/?probe=d7337f7684) | Apr 17, 2024 |
| Dell          | Latitude 5410               | Notebook    | [700b37dcf0](https://linux-hardware.org/?probe=700b37dcf0) | Apr 16, 2024 |
| MSI           | GF75 Thin 10SC              | Notebook    | [7ab70feffe](https://linux-hardware.org/?probe=7ab70feffe) | Apr 16, 2024 |
| HP            | 8643 SMVB                   | Desktop     | [de6f248fc2](https://linux-hardware.org/?probe=de6f248fc2) | Apr 14, 2024 |
| HP            | Pavilion 13 x2 PC           | Notebook    | [684e30a2e3](https://linux-hardware.org/?probe=684e30a2e3) | Apr 13, 2024 |
| HP            | Pavilion 13 x2 PC           | Notebook    | [60d693276a](https://linux-hardware.org/?probe=60d693276a) | Apr 13, 2024 |
| ASRock        | J4105B-ITX                  | Desktop     | [ecb84ecf2a](https://linux-hardware.org/?probe=ecb84ecf2a) | Apr 12, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [b6a43ddde6](https://linux-hardware.org/?probe=b6a43ddde6) | Apr 11, 2024 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [20fe73c7f9](https://linux-hardware.org/?probe=20fe73c7f9) | Apr 11, 2024 |
| ASUSTek       | H97M-E                      | Desktop     | [431b3ef7f6](https://linux-hardware.org/?probe=431b3ef7f6) | Apr 11, 2024 |
| ASUSTek       | M4A78-E                     | Desktop     | [206d758570](https://linux-hardware.org/?probe=206d758570) | Apr 10, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [23e552156c](https://linux-hardware.org/?probe=23e552156c) | Apr 09, 2024 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [313d012a75](https://linux-hardware.org/?probe=313d012a75) | Apr 09, 2024 |
| HP            | EliteBook 2760p             | Notebook    | [37781c3e84](https://linux-hardware.org/?probe=37781c3e84) | Apr 07, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [e8546100eb](https://linux-hardware.org/?probe=e8546100eb) | Apr 07, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a130a64c11](https://linux-hardware.org/?probe=a130a64c11) | Apr 07, 2024 |
| Unknown       | Unknown                     | Desktop     | [ac2a7ce77d](https://linux-hardware.org/?probe=ac2a7ce77d) | Apr 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [1ada20ef48](https://linux-hardware.org/?probe=1ada20ef48) | Apr 06, 2024 |
| AMI           | Unknown                     | Notebook    | [e52668ee27](https://linux-hardware.org/?probe=e52668ee27) | Apr 05, 2024 |
| Acer          | Aspire ES1-311              | Notebook    | [9a68d90ab7](https://linux-hardware.org/?probe=9a68d90ab7) | Apr 05, 2024 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [64c55b79df](https://linux-hardware.org/?probe=64c55b79df) | Apr 04, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [4f2bc03aca](https://linux-hardware.org/?probe=4f2bc03aca) | Apr 04, 2024 |
| ASRock        | B650M-H/M.2+                | Desktop     | [38f4136e38](https://linux-hardware.org/?probe=38f4136e38) | Apr 03, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [a7a78cd117](https://linux-hardware.org/?probe=a7a78cd117) | Apr 02, 2024 |
| Dell          | 032W55 A03                  | Desktop     | [5943c24943](https://linux-hardware.org/?probe=5943c24943) | Apr 01, 2024 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [20959b9997](https://linux-hardware.org/?probe=20959b9997) | Apr 01, 2024 |
| HP            | Pavilion Sleekbook 15       | Notebook    | [42117baa72](https://linux-hardware.org/?probe=42117baa72) | Apr 01, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [cff197ffbf](https://linux-hardware.org/?probe=cff197ffbf) | Mar 30, 2024 |
| Lenovo        | IdeaPad Slim 3 14IAN8 82... | Notebook    | [3709076728](https://linux-hardware.org/?probe=3709076728) | Mar 30, 2024 |
| Dell          | 02YRK5 A02                  | Desktop     | [4c860be642](https://linux-hardware.org/?probe=4c860be642) | Mar 29, 2024 |
| Toshiba       | Satellite C70D-A            | Notebook    | [8489c1e38c](https://linux-hardware.org/?probe=8489c1e38c) | Mar 28, 2024 |
| Dell          | Latitude 3410               | Notebook    | [3aee33bb58](https://linux-hardware.org/?probe=3aee33bb58) | Mar 27, 2024 |
| Monster       | ABRA A5 V17.4               | Notebook    | [153af2c8d9](https://linux-hardware.org/?probe=153af2c8d9) | Mar 23, 2024 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [61d0ee2736](https://linux-hardware.org/?probe=61d0ee2736) | Mar 22, 2024 |
| Gigabyte      | H87-HD3                     | Desktop     | [39e7b8c321](https://linux-hardware.org/?probe=39e7b8c321) | Mar 22, 2024 |
| Lenovo        | ThinkPad T490s 20NX006HM... | Notebook    | [52e2e29f44](https://linux-hardware.org/?probe=52e2e29f44) | Mar 22, 2024 |
| Toshiba       | PORTEGE R500                | Notebook    | [33c598fc6e](https://linux-hardware.org/?probe=33c598fc6e) | Mar 21, 2024 |
| HP            | EliteBook 820 G3            | Notebook    | [5d5d06eab9](https://linux-hardware.org/?probe=5d5d06eab9) | Mar 20, 2024 |
| Acer          | Aspire XC-886 V:2.0         | Desktop     | [624e1874e9](https://linux-hardware.org/?probe=624e1874e9) | Mar 20, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [fc818b5a1b](https://linux-hardware.org/?probe=fc818b5a1b) | Mar 18, 2024 |
| Lenovo        | ThinkStation S30 0606AD5    | Desktop     | [8a703c6f02](https://linux-hardware.org/?probe=8a703c6f02) | Mar 17, 2024 |
| Lenovo        | Z710 20250                  | Notebook    | [60c82a772a](https://linux-hardware.org/?probe=60c82a772a) | Mar 17, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [e2617d5a43](https://linux-hardware.org/?probe=e2617d5a43) | Mar 17, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [5f37f98222](https://linux-hardware.org/?probe=5f37f98222) | Mar 16, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [78ad2387d5](https://linux-hardware.org/?probe=78ad2387d5) | Mar 15, 2024 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [bb52ad6052](https://linux-hardware.org/?probe=bb52ad6052) | Mar 15, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [0fbeb0332d](https://linux-hardware.org/?probe=0fbeb0332d) | Mar 14, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [668f06dbdf](https://linux-hardware.org/?probe=668f06dbdf) | Mar 14, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ad2e487982](https://linux-hardware.org/?probe=ad2e487982) | Mar 12, 2024 |
| Sony          | SVE1712T1EB                 | Notebook    | [a01a793d3b](https://linux-hardware.org/?probe=a01a793d3b) | Mar 12, 2024 |
| Sony          | SVE1712T1EB                 | Notebook    | [2bc7cadf31](https://linux-hardware.org/?probe=2bc7cadf31) | Mar 12, 2024 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [daec1c4210](https://linux-hardware.org/?probe=daec1c4210) | Mar 11, 2024 |
| ASUSTek       | UX31E                       | Notebook    | [94fc346288](https://linux-hardware.org/?probe=94fc346288) | Mar 10, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [c22c7f9510](https://linux-hardware.org/?probe=c22c7f9510) | Mar 10, 2024 |
| MSI           | MS-B120                     | Mini pc     | [8d182b3c8c](https://linux-hardware.org/?probe=8d182b3c8c) | Mar 09, 2024 |
| Dell          | Latitude 3410               | Notebook    | [5ea9fa7a7c](https://linux-hardware.org/?probe=5ea9fa7a7c) | Mar 07, 2024 |
| MSI           | MS-B120                     | Mini pc     | [18c75fd8f9](https://linux-hardware.org/?probe=18c75fd8f9) | Mar 05, 2024 |
| MSI           | Katana GF66 12UC            | Notebook    | [13e9499bcc](https://linux-hardware.org/?probe=13e9499bcc) | Mar 05, 2024 |
| MSI           | Katana GF66 12UC            | Notebook    | [27e54c1325](https://linux-hardware.org/?probe=27e54c1325) | Mar 05, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e053d06a2d](https://linux-hardware.org/?probe=e053d06a2d) | Mar 04, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [6cffe59389](https://linux-hardware.org/?probe=6cffe59389) | Mar 02, 2024 |
| HP            | Notebook                    | Notebook    | [9b7a8a0478](https://linux-hardware.org/?probe=9b7a8a0478) | Feb 29, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [aeee54cee7](https://linux-hardware.org/?probe=aeee54cee7) | Feb 27, 2024 |
| Dell          | Precision 5550              | Notebook    | [59677e206f](https://linux-hardware.org/?probe=59677e206f) | Feb 27, 2024 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [51dde30452](https://linux-hardware.org/?probe=51dde30452) | Feb 25, 2024 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [05c2196fd2](https://linux-hardware.org/?probe=05c2196fd2) | Feb 25, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [69ef5f3bb0](https://linux-hardware.org/?probe=69ef5f3bb0) | Feb 24, 2024 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [f193f8bd36](https://linux-hardware.org/?probe=f193f8bd36) | Feb 23, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d4ac4dafa1](https://linux-hardware.org/?probe=d4ac4dafa1) | Feb 23, 2024 |
| Biostar       | B450MHP                     | Desktop     | [5c5906ef27](https://linux-hardware.org/?probe=5c5906ef27) | Feb 21, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [645bf6be84](https://linux-hardware.org/?probe=645bf6be84) | Feb 20, 2024 |
| Dell          | Latitude 5590               | Notebook    | [e25be34559](https://linux-hardware.org/?probe=e25be34559) | Feb 19, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [3c40fa1a9f](https://linux-hardware.org/?probe=3c40fa1a9f) | Feb 19, 2024 |
| Dell          | Latitude E5550              | Notebook    | [8f96e62eaf](https://linux-hardware.org/?probe=8f96e62eaf) | Feb 18, 2024 |
| Biostar       | B450MHP                     | Desktop     | [81eca30554](https://linux-hardware.org/?probe=81eca30554) | Feb 18, 2024 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [8bb363d9be](https://linux-hardware.org/?probe=8bb363d9be) | Feb 18, 2024 |
| Dell          | OptiPlex 980                | Desktop     | [9554536e5f](https://linux-hardware.org/?probe=9554536e5f) | Feb 18, 2024 |
| Biostar       | B450MHP                     | Desktop     | [1c50343bc4](https://linux-hardware.org/?probe=1c50343bc4) | Feb 17, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [ff0a6068a5](https://linux-hardware.org/?probe=ff0a6068a5) | Feb 17, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [5ad9c09f49](https://linux-hardware.org/?probe=5ad9c09f49) | Feb 16, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1a90ac1ac4](https://linux-hardware.org/?probe=1a90ac1ac4) | Feb 15, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b4a782dfca](https://linux-hardware.org/?probe=b4a782dfca) | Feb 15, 2024 |
| Acer          | Extensa 215-22              | Notebook    | [a7faa9b520](https://linux-hardware.org/?probe=a7faa9b520) | Feb 14, 2024 |
| MSI           | MS-B120                     | Mini pc     | [ea5bf7fa17](https://linux-hardware.org/?probe=ea5bf7fa17) | Feb 11, 2024 |
| Dell          | Inspiron 1520               | Notebook    | [953b2c870f](https://linux-hardware.org/?probe=953b2c870f) | Feb 11, 2024 |
| Toshiba       | Satellite C55-B             | Notebook    | [f9989aa45a](https://linux-hardware.org/?probe=f9989aa45a) | Feb 09, 2024 |
| Dell          | Precision 7520              | Notebook    | [3ba06d2c0d](https://linux-hardware.org/?probe=3ba06d2c0d) | Feb 08, 2024 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | Notebook    | [1d5c5c6bdc](https://linux-hardware.org/?probe=1d5c5c6bdc) | Feb 07, 2024 |
| Lenovo        | ThinkCentre A58 75227MG     | Desktop     | [bf324db579](https://linux-hardware.org/?probe=bf324db579) | Feb 07, 2024 |
| MSI           | PRO H510M-B                 | Desktop     | [1d9804ffcc](https://linux-hardware.org/?probe=1d9804ffcc) | Feb 03, 2024 |
| HP            | Pavilion m6                 | Notebook    | [f12679a936](https://linux-hardware.org/?probe=f12679a936) | Feb 03, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [dbe298a22e](https://linux-hardware.org/?probe=dbe298a22e) | Feb 03, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [6259b53b1c](https://linux-hardware.org/?probe=6259b53b1c) | Feb 02, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [7def8ee544](https://linux-hardware.org/?probe=7def8ee544) | Feb 01, 2024 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [c62ec1a167](https://linux-hardware.org/?probe=c62ec1a167) | Jan 31, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [6f8f587ec5](https://linux-hardware.org/?probe=6f8f587ec5) | Jan 30, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [091fe8d216](https://linux-hardware.org/?probe=091fe8d216) | Jan 29, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1069da15da](https://linux-hardware.org/?probe=1069da15da) | Jan 28, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [7a5a8be027](https://linux-hardware.org/?probe=7a5a8be027) | Jan 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6122c021d6](https://linux-hardware.org/?probe=6122c021d6) | Jan 25, 2024 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [120ebd1d10](https://linux-hardware.org/?probe=120ebd1d10) | Jan 24, 2024 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [434a85ff04](https://linux-hardware.org/?probe=434a85ff04) | Jan 21, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3dff9ac8f3](https://linux-hardware.org/?probe=3dff9ac8f3) | Jan 21, 2024 |
| Apple         | MacBookPro14,1              | Notebook    | [bdf8f178f4](https://linux-hardware.org/?probe=bdf8f178f4) | Jan 18, 2024 |
| Dell          | Latitude E5550              | Notebook    | [2887bb49af](https://linux-hardware.org/?probe=2887bb49af) | Jan 17, 2024 |
| System76      | Lemur Ultra                 | Notebook    | [31f8a83abf](https://linux-hardware.org/?probe=31f8a83abf) | Jan 17, 2024 |
| Dell          | 0GDJXY A00                  | All in one  | [3ea400d76d](https://linux-hardware.org/?probe=3ea400d76d) | Jan 17, 2024 |
| HP            | ProBook 450 G6              | Notebook    | [6d71f55994](https://linux-hardware.org/?probe=6d71f55994) | Jan 17, 2024 |
| Dell          | Latitude E5550              | Notebook    | [0755281d4f](https://linux-hardware.org/?probe=0755281d4f) | Jan 16, 2024 |
| Gigabyte      | Z370N WIFI-CF               | Desktop     | [01eeec96ca](https://linux-hardware.org/?probe=01eeec96ca) | Jan 16, 2024 |
| ASRock        | X570 Steel Legend           | Desktop     | [192feda06a](https://linux-hardware.org/?probe=192feda06a) | Jan 16, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [1279f6d244](https://linux-hardware.org/?probe=1279f6d244) | Jan 13, 2024 |
| Intel         | NUC11PABi7 K90104-305       | Mini pc     | [8a6e291933](https://linux-hardware.org/?probe=8a6e291933) | Jan 11, 2024 |
| Dell          | Vostro 7620                 | Notebook    | [433547fc16](https://linux-hardware.org/?probe=433547fc16) | Jan 11, 2024 |
| Juniper Sy... | Mesa Pro                    | Tablet      | [9c632df9a1](https://linux-hardware.org/?probe=9c632df9a1) | Jan 10, 2024 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [f46fcb5ee9](https://linux-hardware.org/?probe=f46fcb5ee9) | Jan 10, 2024 |
| Dell          | 032W55 A03                  | Desktop     | [97e3c61a8b](https://linux-hardware.org/?probe=97e3c61a8b) | Jan 07, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3f33c9082a](https://linux-hardware.org/?probe=3f33c9082a) | Jan 03, 2024 |
| Lenovo        | ThinkCentre M55e 9645W2C    | Desktop     | [7f8c8e496a](https://linux-hardware.org/?probe=7f8c8e496a) | Jan 02, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [91413e5760](https://linux-hardware.org/?probe=91413e5760) | Jan 02, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [c038b7f7e4](https://linux-hardware.org/?probe=c038b7f7e4) | Jan 02, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [cdb97873fa](https://linux-hardware.org/?probe=cdb97873fa) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [f9d4fa4d55](https://linux-hardware.org/?probe=f9d4fa4d55) | Jan 01, 2024 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [8dab3905db](https://linux-hardware.org/?probe=8dab3905db) | Jan 01, 2024 |
| Gigabyte      | H470M K                     | Desktop     | [90b6ff9ff3](https://linux-hardware.org/?probe=90b6ff9ff3) | Jan 01, 2024 |
| HP            | Laptop 17-cn3xxx            | Notebook    | [3a84122c5a](https://linux-hardware.org/?probe=3a84122c5a) | Dec 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c7f2d68d77](https://linux-hardware.org/?probe=c7f2d68d77) | Dec 30, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [763233abcb](https://linux-hardware.org/?probe=763233abcb) | Dec 30, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [10d9fd3230](https://linux-hardware.org/?probe=10d9fd3230) | Dec 30, 2023 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [5bd82e2331](https://linux-hardware.org/?probe=5bd82e2331) | Dec 28, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f4820a078b](https://linux-hardware.org/?probe=f4820a078b) | Dec 26, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [d25c8e8312](https://linux-hardware.org/?probe=d25c8e8312) | Dec 26, 2023 |
| Medion        | S6445 MD61281               | Notebook    | [b7db1404b6](https://linux-hardware.org/?probe=b7db1404b6) | Dec 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [87cef435db](https://linux-hardware.org/?probe=87cef435db) | Dec 24, 2023 |
| Clevo         | W760/M770CU                 | Notebook    | [c64bdf2349](https://linux-hardware.org/?probe=c64bdf2349) | Dec 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b57fdd9854](https://linux-hardware.org/?probe=b57fdd9854) | Dec 24, 2023 |
| GPU Compan... | GWTN116-3                   | Notebook    | [89366f9a48](https://linux-hardware.org/?probe=89366f9a48) | Dec 23, 2023 |
| GPD           | G1621-02                    | Notebook    | [eaf78f9da1](https://linux-hardware.org/?probe=eaf78f9da1) | Dec 22, 2023 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [73408e34a6](https://linux-hardware.org/?probe=73408e34a6) | Dec 21, 2023 |
| HP            | 350 G1                      | Notebook    | [c219133bce](https://linux-hardware.org/?probe=c219133bce) | Dec 20, 2023 |
| RuggedPC      | RuggedPadY22                | Tablet      | [80f7f9c98a](https://linux-hardware.org/?probe=80f7f9c98a) | Dec 20, 2023 |
| Clevo         | W760/M770CU                 | Notebook    | [fdde778b3c](https://linux-hardware.org/?probe=fdde778b3c) | Dec 19, 2023 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [f3149a6f22](https://linux-hardware.org/?probe=f3149a6f22) | Dec 19, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [bb58136a7c](https://linux-hardware.org/?probe=bb58136a7c) | Dec 18, 2023 |
| RuggedPC      | RuggedPadY22                | Tablet      | [da34d3936d](https://linux-hardware.org/?probe=da34d3936d) | Dec 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1446130ae9](https://linux-hardware.org/?probe=1446130ae9) | Dec 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [80281cb193](https://linux-hardware.org/?probe=80281cb193) | Dec 17, 2023 |
| ASUSTek       | PRIME B760-PLUS             | Desktop     | [b7a7aa8d5d](https://linux-hardware.org/?probe=b7a7aa8d5d) | Dec 17, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | Notebook    | [88312d177f](https://linux-hardware.org/?probe=88312d177f) | Dec 16, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [f58535cbfe](https://linux-hardware.org/?probe=f58535cbfe) | Dec 14, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [4b88dcf6b3](https://linux-hardware.org/?probe=4b88dcf6b3) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [1a63f79d28](https://linux-hardware.org/?probe=1a63f79d28) | Dec 13, 2023 |
| RuggedPC      | RuggedPadY22                | Tablet      | [cb9765df38](https://linux-hardware.org/?probe=cb9765df38) | Dec 12, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [9a0bb65e3f](https://linux-hardware.org/?probe=9a0bb65e3f) | Dec 12, 2023 |
| HP            | 82DC 1100                   | All in one  | [96f4033f37](https://linux-hardware.org/?probe=96f4033f37) | Dec 12, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [991503ccf4](https://linux-hardware.org/?probe=991503ccf4) | Dec 10, 2023 |
| HP            | ProLiant MicroServer        | Desktop     | [5451582602](https://linux-hardware.org/?probe=5451582602) | Dec 08, 2023 |
| MSI           | MS-B120                     | Mini pc     | [51a1cc9143](https://linux-hardware.org/?probe=51a1cc9143) | Dec 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [9c55ae59fe](https://linux-hardware.org/?probe=9c55ae59fe) | Dec 07, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [18a5ca0a40](https://linux-hardware.org/?probe=18a5ca0a40) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [1b3b476186](https://linux-hardware.org/?probe=1b3b476186) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [58547d36b7](https://linux-hardware.org/?probe=58547d36b7) | Dec 06, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [06a0da716b](https://linux-hardware.org/?probe=06a0da716b) | Dec 05, 2023 |
| Microsoft     | Surface Laptop Go 2         | Tablet      | [3c6a041703](https://linux-hardware.org/?probe=3c6a041703) | Dec 05, 2023 |
| MSI           | H81M-P33                    | Desktop     | [3c745928bb](https://linux-hardware.org/?probe=3c745928bb) | Dec 02, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [5f4856fdab](https://linux-hardware.org/?probe=5f4856fdab) | Dec 01, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [bb8295e3fa](https://linux-hardware.org/?probe=bb8295e3fa) | Nov 30, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [0d3ea0a6dc](https://linux-hardware.org/?probe=0d3ea0a6dc) | Nov 30, 2023 |
| Acer          | AOD260                      | Notebook    | [20594f9a03](https://linux-hardware.org/?probe=20594f9a03) | Nov 29, 2023 |
| Acer          | AOD260                      | Notebook    | [de50f2993e](https://linux-hardware.org/?probe=de50f2993e) | Nov 29, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4c55de5adb](https://linux-hardware.org/?probe=4c55de5adb) | Nov 28, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [416fbc3923](https://linux-hardware.org/?probe=416fbc3923) | Nov 28, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [608d264af2](https://linux-hardware.org/?probe=608d264af2) | Nov 27, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [2ecc0c852a](https://linux-hardware.org/?probe=2ecc0c852a) | Nov 27, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [47d33f722e](https://linux-hardware.org/?probe=47d33f722e) | Nov 25, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [5ead75f7bc](https://linux-hardware.org/?probe=5ead75f7bc) | Nov 25, 2023 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [5d2574b6cf](https://linux-hardware.org/?probe=5d2574b6cf) | Nov 24, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [5ae0c22a32](https://linux-hardware.org/?probe=5ae0c22a32) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [59444faae7](https://linux-hardware.org/?probe=59444faae7) | Nov 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [7caae1b1a0](https://linux-hardware.org/?probe=7caae1b1a0) | Nov 24, 2023 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [502e296060](https://linux-hardware.org/?probe=502e296060) | Nov 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [5c0820855b](https://linux-hardware.org/?probe=5c0820855b) | Nov 23, 2023 |
| Lenovo        | IdeaPad Y460                | Notebook    | [265198a4bc](https://linux-hardware.org/?probe=265198a4bc) | Nov 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [a4cda5b12d](https://linux-hardware.org/?probe=a4cda5b12d) | Nov 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [96d6ec7f1f](https://linux-hardware.org/?probe=96d6ec7f1f) | Nov 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c0a0353d6f](https://linux-hardware.org/?probe=c0a0353d6f) | Nov 20, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [acfd3b6493](https://linux-hardware.org/?probe=acfd3b6493) | Nov 19, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [6a9af286f8](https://linux-hardware.org/?probe=6a9af286f8) | Nov 19, 2023 |
| Dell          | Precision 7760              | Notebook    | [daaf99c63e](https://linux-hardware.org/?probe=daaf99c63e) | Nov 17, 2023 |
| Dell          | Precision 7760              | Notebook    | [50404f0f12](https://linux-hardware.org/?probe=50404f0f12) | Nov 17, 2023 |
| ASRock        | X99 Extreme4                | Desktop     | [dfb480c40a](https://linux-hardware.org/?probe=dfb480c40a) | Nov 17, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [9443883eaf](https://linux-hardware.org/?probe=9443883eaf) | Nov 16, 2023 |
| BANGHO        | 1025                        | Notebook    | [d1d51fc17a](https://linux-hardware.org/?probe=d1d51fc17a) | Nov 15, 2023 |
| ASUSTek       | P8P67-M PRO                 | Desktop     | [9d1c329ebb](https://linux-hardware.org/?probe=9d1c329ebb) | Nov 14, 2023 |
| Dell          | Precision M4800             | Notebook    | [9a63057a12](https://linux-hardware.org/?probe=9a63057a12) | Nov 13, 2023 |
| BANGHO        | 1025                        | Notebook    | [97b39ed05d](https://linux-hardware.org/?probe=97b39ed05d) | Nov 13, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [92930dd0d4](https://linux-hardware.org/?probe=92930dd0d4) | Nov 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9dd24e5aaa](https://linux-hardware.org/?probe=9dd24e5aaa) | Nov 12, 2023 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Notebook    | [a206fa30d7](https://linux-hardware.org/?probe=a206fa30d7) | Nov 11, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [cb1e3547f7](https://linux-hardware.org/?probe=cb1e3547f7) | Nov 10, 2023 |
| Dell          | 0TKD84 A02                  | Server      | [accebd9648](https://linux-hardware.org/?probe=accebd9648) | Nov 10, 2023 |
| Dell          | 0VRCY5 A12                  | Server      | [1bf5a3e96c](https://linux-hardware.org/?probe=1bf5a3e96c) | Nov 08, 2023 |
| MSI           | GL62 6QF                    | Notebook    | [ac1f389364](https://linux-hardware.org/?probe=ac1f389364) | Nov 08, 2023 |
| Dell          | 032W55 A03                  | Desktop     | [8d3db7f790](https://linux-hardware.org/?probe=8d3db7f790) | Nov 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [70cdbefd00](https://linux-hardware.org/?probe=70cdbefd00) | Nov 07, 2023 |
| Lenovo        | T530-28ICB                  | Desktop     | [ba883f99a0](https://linux-hardware.org/?probe=ba883f99a0) | Nov 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [24a052bf0c](https://linux-hardware.org/?probe=24a052bf0c) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [254a87d641](https://linux-hardware.org/?probe=254a87d641) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f0b35f0acb](https://linux-hardware.org/?probe=f0b35f0acb) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7060a82ed0](https://linux-hardware.org/?probe=7060a82ed0) | Nov 05, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fc01ceb47b](https://linux-hardware.org/?probe=fc01ceb47b) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [594257aca2](https://linux-hardware.org/?probe=594257aca2) | Nov 03, 2023 |
| Dell          | 09WH54 A01                  | Desktop     | [4eae8e67db](https://linux-hardware.org/?probe=4eae8e67db) | Nov 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [602a2268e2](https://linux-hardware.org/?probe=602a2268e2) | Nov 02, 2023 |
| Lenovo        | ThinkPad P53 20QN000FIX     | Notebook    | [40de43c266](https://linux-hardware.org/?probe=40de43c266) | Nov 02, 2023 |
| Google        | Galtic                      | Notebook    | [8945661ada](https://linux-hardware.org/?probe=8945661ada) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [d2d21dcf50](https://linux-hardware.org/?probe=d2d21dcf50) | Nov 01, 2023 |
| MSI           | Creator 15 A11UE            | Notebook    | [e8b0c2a2b5](https://linux-hardware.org/?probe=e8b0c2a2b5) | Oct 31, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ee7bce3de](https://linux-hardware.org/?probe=6ee7bce3de) | Oct 31, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [b367027f2a](https://linux-hardware.org/?probe=b367027f2a) | Oct 30, 2023 |
| Panasonic     | CF-53SJCZYLM                | Notebook    | [94941374a2](https://linux-hardware.org/?probe=94941374a2) | Oct 30, 2023 |
| Dell          | Precision 7760              | Notebook    | [eaba0c73b0](https://linux-hardware.org/?probe=eaba0c73b0) | Oct 29, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [e3bde6ede0](https://linux-hardware.org/?probe=e3bde6ede0) | Oct 28, 2023 |
| VIT           | P1400                       | Notebook    | [235c6e8c49](https://linux-hardware.org/?probe=235c6e8c49) | Oct 28, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [698c3abcba](https://linux-hardware.org/?probe=698c3abcba) | Oct 27, 2023 |
| Dell          | Latitude 7430               | Notebook    | [e9cfada6a4](https://linux-hardware.org/?probe=e9cfada6a4) | Oct 26, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [9854f25018](https://linux-hardware.org/?probe=9854f25018) | Oct 26, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [2129ab3e24](https://linux-hardware.org/?probe=2129ab3e24) | Oct 26, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b98bc11e71](https://linux-hardware.org/?probe=b98bc11e71) | Oct 25, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [b01d80e583](https://linux-hardware.org/?probe=b01d80e583) | Oct 24, 2023 |
| Gigabyte      | G5 KC                       | Notebook    | [32743a624c](https://linux-hardware.org/?probe=32743a624c) | Oct 24, 2023 |
| Gigabyte      | G5 KC                       | Notebook    | [23d64978d9](https://linux-hardware.org/?probe=23d64978d9) | Oct 24, 2023 |
| Positivo      | C4128G-15                   | Notebook    | [8d9aa2f206](https://linux-hardware.org/?probe=8d9aa2f206) | Oct 23, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [961c369ea4](https://linux-hardware.org/?probe=961c369ea4) | Oct 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f19c18154b](https://linux-hardware.org/?probe=f19c18154b) | Oct 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [2682d3f618](https://linux-hardware.org/?probe=2682d3f618) | Oct 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [8765923ff6](https://linux-hardware.org/?probe=8765923ff6) | Oct 21, 2023 |
| Acer          | Aspire E3-112M              | Notebook    | [11d6580d3e](https://linux-hardware.org/?probe=11d6580d3e) | Oct 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [bc4cc061a2](https://linux-hardware.org/?probe=bc4cc061a2) | Oct 18, 2023 |
| HP            | 3646h                       | Desktop     | [6a679937c4](https://linux-hardware.org/?probe=6a679937c4) | Oct 18, 2023 |
| Hardkernel    | ODROID-C4                   | Soc         | [3a322cbde3](https://linux-hardware.org/?probe=3a322cbde3) | Oct 17, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [f16973062f](https://linux-hardware.org/?probe=f16973062f) | Oct 15, 2023 |
| Packard Be... | EasyNote ENTG81BA           | Notebook    | [f25cb1517e](https://linux-hardware.org/?probe=f25cb1517e) | Oct 12, 2023 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [deb84129fb](https://linux-hardware.org/?probe=deb84129fb) | Oct 10, 2023 |
| ASUSTek       | K50ID                       | Notebook    | [2763bfac4e](https://linux-hardware.org/?probe=2763bfac4e) | Oct 07, 2023 |
| Lenovo        | ThinkPad A275 20KCS09T1G    | Notebook    | [1e797cb20f](https://linux-hardware.org/?probe=1e797cb20f) | Oct 07, 2023 |
| Infinix       | INBOOK X2                   | Notebook    | [5d39adb330](https://linux-hardware.org/?probe=5d39adb330) | Oct 05, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [2a4f34aeb4](https://linux-hardware.org/?probe=2a4f34aeb4) | Oct 05, 2023 |
| Google        | Galtic                      | Notebook    | [e838b462a7](https://linux-hardware.org/?probe=e838b462a7) | Oct 04, 2023 |
| Google        | Galtic                      | Notebook    | [cae091837b](https://linux-hardware.org/?probe=cae091837b) | Oct 03, 2023 |
| ASRock        | J4105-ITX                   | Desktop     | [f4d4b23c31](https://linux-hardware.org/?probe=f4d4b23c31) | Oct 02, 2023 |
| Lenovo        | 3140 SDK0J40700 WIN 3258... | Desktop     | [b9b34bef50](https://linux-hardware.org/?probe=b9b34bef50) | Oct 02, 2023 |
| GPD           | G1621-02                    | Notebook    | [10ca9df59f](https://linux-hardware.org/?probe=10ca9df59f) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f510af1acf](https://linux-hardware.org/?probe=f510af1acf) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7b44ef8cd1](https://linux-hardware.org/?probe=7b44ef8cd1) | Oct 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [8db3bb5b34](https://linux-hardware.org/?probe=8db3bb5b34) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a1f20bb140](https://linux-hardware.org/?probe=a1f20bb140) | Sep 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1449844643](https://linux-hardware.org/?probe=1449844643) | Sep 30, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [8487059659](https://linux-hardware.org/?probe=8487059659) | Sep 30, 2023 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [b952cdd71d](https://linux-hardware.org/?probe=b952cdd71d) | Sep 29, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [390c16a341](https://linux-hardware.org/?probe=390c16a341) | Sep 26, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [64f1cd854d](https://linux-hardware.org/?probe=64f1cd854d) | Sep 26, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [2be1547618](https://linux-hardware.org/?probe=2be1547618) | Sep 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [89d81885ff](https://linux-hardware.org/?probe=89d81885ff) | Sep 26, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1deb55b03b](https://linux-hardware.org/?probe=1deb55b03b) | Sep 25, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [450edd6547](https://linux-hardware.org/?probe=450edd6547) | Sep 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [84bba5e5a7](https://linux-hardware.org/?probe=84bba5e5a7) | Sep 24, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [5fba7d78c6](https://linux-hardware.org/?probe=5fba7d78c6) | Sep 23, 2023 |
| Dell          | Latitude E5470              | Notebook    | [f6e9a7233c](https://linux-hardware.org/?probe=f6e9a7233c) | Sep 23, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d00cc6b535](https://linux-hardware.org/?probe=d00cc6b535) | Sep 21, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [89cce2b6cb](https://linux-hardware.org/?probe=89cce2b6cb) | Sep 21, 2023 |
| Lenovo        | ThinkPad X200 74595FG       | Notebook    | [c5cda29091](https://linux-hardware.org/?probe=c5cda29091) | Sep 21, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [43e04cf99c](https://linux-hardware.org/?probe=43e04cf99c) | Sep 20, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [00ce48a639](https://linux-hardware.org/?probe=00ce48a639) | Sep 19, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [50023a1d3a](https://linux-hardware.org/?probe=50023a1d3a) | Sep 18, 2023 |
| ASUSTek       | N73SM                       | Notebook    | [d4ce8f336d](https://linux-hardware.org/?probe=d4ce8f336d) | Sep 17, 2023 |
| Unknown       | X79M2-Q                     | Desktop     | [670ca9e147](https://linux-hardware.org/?probe=670ca9e147) | Sep 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [adff9fb2a8](https://linux-hardware.org/?probe=adff9fb2a8) | Sep 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [103e7031fe](https://linux-hardware.org/?probe=103e7031fe) | Sep 14, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [21932b1004](https://linux-hardware.org/?probe=21932b1004) | Sep 14, 2023 |
| ASUSTek       | P8P67-M PRO                 | Desktop     | [799a135aca](https://linux-hardware.org/?probe=799a135aca) | Sep 14, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [7cea54ec70](https://linux-hardware.org/?probe=7cea54ec70) | Sep 13, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | Notebook    | [22a0210f8f](https://linux-hardware.org/?probe=22a0210f8f) | Sep 13, 2023 |
| Lenovo        | ThinkPad T490s 20NYS5820... | Notebook    | [4c56913d07](https://linux-hardware.org/?probe=4c56913d07) | Sep 13, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [09c2d451ab](https://linux-hardware.org/?probe=09c2d451ab) | Sep 11, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [820eeccddf](https://linux-hardware.org/?probe=820eeccddf) | Sep 10, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [03b8175690](https://linux-hardware.org/?probe=03b8175690) | Sep 10, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [5bf280924d](https://linux-hardware.org/?probe=5bf280924d) | Sep 09, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [98ba75a25b](https://linux-hardware.org/?probe=98ba75a25b) | Sep 09, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [7e478d179a](https://linux-hardware.org/?probe=7e478d179a) | Sep 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [bd4b5d82ed](https://linux-hardware.org/?probe=bd4b5d82ed) | Sep 09, 2023 |
| ASUSTek       | P8P67-M PRO                 | Desktop     | [6ec67cd2f1](https://linux-hardware.org/?probe=6ec67cd2f1) | Sep 08, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [55b8608662](https://linux-hardware.org/?probe=55b8608662) | Sep 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [4e54155977](https://linux-hardware.org/?probe=4e54155977) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [db4ba96400](https://linux-hardware.org/?probe=db4ba96400) | Sep 07, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [51202f2fd7](https://linux-hardware.org/?probe=51202f2fd7) | Sep 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c02fef3ca2](https://linux-hardware.org/?probe=c02fef3ca2) | Sep 05, 2023 |
| ASUSTek       | P5GC-MX                     | Desktop     | [7d13cd846d](https://linux-hardware.org/?probe=7d13cd846d) | Sep 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1c048ac799](https://linux-hardware.org/?probe=1c048ac799) | Sep 04, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | Notebook    | [2da95fb8e8](https://linux-hardware.org/?probe=2da95fb8e8) | Sep 03, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [858212c01d](https://linux-hardware.org/?probe=858212c01d) | Sep 03, 2023 |
| Hardkernel    | ODROID-M1                   | Soc         | [1901f4aad9](https://linux-hardware.org/?probe=1901f4aad9) | Sep 02, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [0e82099e8f](https://linux-hardware.org/?probe=0e82099e8f) | Sep 01, 2023 |
| MSI           | Z97-G43                     | Desktop     | [74492b4424](https://linux-hardware.org/?probe=74492b4424) | Aug 30, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6f5a767b7e](https://linux-hardware.org/?probe=6f5a767b7e) | Aug 29, 2023 |
| Bluechip C... | TRAVELline TL14W4           | Notebook    | [7959987246](https://linux-hardware.org/?probe=7959987246) | Aug 28, 2023 |
| Dell          | Inspiron 3593               | Notebook    | [1562efcaf2](https://linux-hardware.org/?probe=1562efcaf2) | Aug 27, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [dcb65a221f](https://linux-hardware.org/?probe=dcb65a221f) | Aug 27, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6736188e61](https://linux-hardware.org/?probe=6736188e61) | Aug 26, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [f0a3b05a99](https://linux-hardware.org/?probe=f0a3b05a99) | Aug 25, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [71ba491330](https://linux-hardware.org/?probe=71ba491330) | Aug 24, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [36e12540f3](https://linux-hardware.org/?probe=36e12540f3) | Aug 23, 2023 |
| Dell          | OptiPlex 5050               | Desktop     | [045411a33d](https://linux-hardware.org/?probe=045411a33d) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS WI... | Desktop     | [f280fd203e](https://linux-hardware.org/?probe=f280fd203e) | Aug 21, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [cdbe8c2f04](https://linux-hardware.org/?probe=cdbe8c2f04) | Aug 21, 2023 |
| Dell          | OptiPlex 5050               | Desktop     | [e2c9cecddd](https://linux-hardware.org/?probe=e2c9cecddd) | Aug 18, 2023 |
| Unknown       | Unknown                     | Convertible | [24b989fc80](https://linux-hardware.org/?probe=24b989fc80) | Aug 16, 2023 |
| Unknown       | V00                         | Mini pc     | [cfd52d26cd](https://linux-hardware.org/?probe=cfd52d26cd) | Aug 16, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [810d33b380](https://linux-hardware.org/?probe=810d33b380) | Aug 16, 2023 |
| HP            | 829D                        | Desktop     | [448bb23145](https://linux-hardware.org/?probe=448bb23145) | Aug 15, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [6602bb3d0a](https://linux-hardware.org/?probe=6602bb3d0a) | Aug 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [5a809fe1c3](https://linux-hardware.org/?probe=5a809fe1c3) | Aug 13, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [06316c3471](https://linux-hardware.org/?probe=06316c3471) | Aug 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b97fcb7117](https://linux-hardware.org/?probe=b97fcb7117) | Aug 12, 2023 |
| Dell          | Latitude E7250              | Notebook    | [7418a0dc06](https://linux-hardware.org/?probe=7418a0dc06) | Aug 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [6f230d02c1](https://linux-hardware.org/?probe=6f230d02c1) | Aug 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ea4ae0e0f3](https://linux-hardware.org/?probe=ea4ae0e0f3) | Aug 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2db90ee24e](https://linux-hardware.org/?probe=2db90ee24e) | Aug 11, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [5ccf8e7d00](https://linux-hardware.org/?probe=5ccf8e7d00) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [78f477986b](https://linux-hardware.org/?probe=78f477986b) | Aug 10, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [0c4903c4d2](https://linux-hardware.org/?probe=0c4903c4d2) | Aug 10, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [e76c695348](https://linux-hardware.org/?probe=e76c695348) | Aug 09, 2023 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [8a6ead436f](https://linux-hardware.org/?probe=8a6ead436f) | Aug 08, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [6b6773eeef](https://linux-hardware.org/?probe=6b6773eeef) | Aug 04, 2023 |
| Lenovo        | ThinkPad T420 4236MBG       | Notebook    | [aaaa17358f](https://linux-hardware.org/?probe=aaaa17358f) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8b6b5ff142](https://linux-hardware.org/?probe=8b6b5ff142) | Aug 04, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [f420f3e1e6](https://linux-hardware.org/?probe=f420f3e1e6) | Aug 04, 2023 |
| Acer          | Extensa 5630                | Notebook    | [8b3c2a89a1](https://linux-hardware.org/?probe=8b3c2a89a1) | Aug 04, 2023 |
| Acer          | Extensa 5630                | Notebook    | [ba6669a5e7](https://linux-hardware.org/?probe=ba6669a5e7) | Aug 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [bd88b4e8fa](https://linux-hardware.org/?probe=bd88b4e8fa) | Aug 04, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [a06a335d70](https://linux-hardware.org/?probe=a06a335d70) | Aug 01, 2023 |
| Dell          | Precision 7520              | Notebook    | [b5addbb003](https://linux-hardware.org/?probe=b5addbb003) | Aug 01, 2023 |
| ASUSTek       | P6X58D-E                    | Desktop     | [84a5ec2d0b](https://linux-hardware.org/?probe=84a5ec2d0b) | Aug 01, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cefd14313d](https://linux-hardware.org/?probe=cefd14313d) | Jul 30, 2023 |
| HP            | 829A                        | Mini pc     | [5bd4fdc8d1](https://linux-hardware.org/?probe=5bd4fdc8d1) | Jul 28, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [32e3874db3](https://linux-hardware.org/?probe=32e3874db3) | Jul 28, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [b42a0455f7](https://linux-hardware.org/?probe=b42a0455f7) | Jul 26, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [8e05eceeef](https://linux-hardware.org/?probe=8e05eceeef) | Jul 26, 2023 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [5457b19b2b](https://linux-hardware.org/?probe=5457b19b2b) | Jul 26, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [9e156dd92f](https://linux-hardware.org/?probe=9e156dd92f) | Jul 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f720b1a032](https://linux-hardware.org/?probe=f720b1a032) | Jul 26, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [33c7ff96a8](https://linux-hardware.org/?probe=33c7ff96a8) | Jul 25, 2023 |
| Dell          | Studio 1537                 | Notebook    | [803a98f7e6](https://linux-hardware.org/?probe=803a98f7e6) | Jul 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c675a3feab](https://linux-hardware.org/?probe=c675a3feab) | Jul 25, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [67daf82d15](https://linux-hardware.org/?probe=67daf82d15) | Jul 24, 2023 |
| Dell          | Precision 7520              | Notebook    | [66922483cf](https://linux-hardware.org/?probe=66922483cf) | Jul 24, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [0a3cc7970c](https://linux-hardware.org/?probe=0a3cc7970c) | Jul 23, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [52541ec1ed](https://linux-hardware.org/?probe=52541ec1ed) | Jul 23, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [02903e0210](https://linux-hardware.org/?probe=02903e0210) | Jul 22, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [e82f5072df](https://linux-hardware.org/?probe=e82f5072df) | Jul 20, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [b1a5c8b10d](https://linux-hardware.org/?probe=b1a5c8b10d) | Jul 20, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [a448a20876](https://linux-hardware.org/?probe=a448a20876) | Jul 17, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [9e330138e8](https://linux-hardware.org/?probe=9e330138e8) | Jul 17, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [d625267663](https://linux-hardware.org/?probe=d625267663) | Jul 17, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e707b1595f](https://linux-hardware.org/?probe=e707b1595f) | Jul 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [9e037f08e1](https://linux-hardware.org/?probe=9e037f08e1) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [b592c5b551](https://linux-hardware.org/?probe=b592c5b551) | Jul 15, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [60809c13e6](https://linux-hardware.org/?probe=60809c13e6) | Jul 15, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d5079cefe1](https://linux-hardware.org/?probe=d5079cefe1) | Jul 13, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [cfc5e42de6](https://linux-hardware.org/?probe=cfc5e42de6) | Jul 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [96fea5a002](https://linux-hardware.org/?probe=96fea5a002) | Jul 10, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [43ec3cf70b](https://linux-hardware.org/?probe=43ec3cf70b) | Jul 09, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cc7487e50f](https://linux-hardware.org/?probe=cc7487e50f) | Jul 09, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [1e85aec604](https://linux-hardware.org/?probe=1e85aec604) | Jul 09, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [502c216e98](https://linux-hardware.org/?probe=502c216e98) | Jul 08, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f73623381d](https://linux-hardware.org/?probe=f73623381d) | Jul 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [ef7acb569d](https://linux-hardware.org/?probe=ef7acb569d) | Jul 08, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [d37d74ba93](https://linux-hardware.org/?probe=d37d74ba93) | Jul 07, 2023 |
| Google        | Guado                       | Desktop     | [8bd38f802a](https://linux-hardware.org/?probe=8bd38f802a) | Jul 06, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [b7a676e2fc](https://linux-hardware.org/?probe=b7a676e2fc) | Jul 05, 2023 |
| Dell          | Latitude 7420               | Notebook    | [44c51e8365](https://linux-hardware.org/?probe=44c51e8365) | Jul 05, 2023 |
| Dell          | Latitude 7420               | Notebook    | [9eae2c6ad4](https://linux-hardware.org/?probe=9eae2c6ad4) | Jul 05, 2023 |
| HP            | 339A                        | Desktop     | [8d051ead1c](https://linux-hardware.org/?probe=8d051ead1c) | Jul 05, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [e7c0ca1bfc](https://linux-hardware.org/?probe=e7c0ca1bfc) | Jul 05, 2023 |
| AZW           | Z85                         | Notebook    | [ca44d0b498](https://linux-hardware.org/?probe=ca44d0b498) | Jul 05, 2023 |
| HP            | 350 G1                      | Notebook    | [d965c2785d](https://linux-hardware.org/?probe=d965c2785d) | Jul 04, 2023 |
| HP            | 350 G1                      | Notebook    | [bb742c9ffb](https://linux-hardware.org/?probe=bb742c9ffb) | Jul 04, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [50b65edbc0](https://linux-hardware.org/?probe=50b65edbc0) | Jul 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [23956fd693](https://linux-hardware.org/?probe=23956fd693) | Jul 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [700348835b](https://linux-hardware.org/?probe=700348835b) | Jul 04, 2023 |
| Dell          | G5 5590                     | Notebook    | [c956c1fd2e](https://linux-hardware.org/?probe=c956c1fd2e) | Jul 03, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [066d1a2fa8](https://linux-hardware.org/?probe=066d1a2fa8) | Jul 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [63a0b07325](https://linux-hardware.org/?probe=63a0b07325) | Jul 02, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ce2d3b5375](https://linux-hardware.org/?probe=ce2d3b5375) | Jul 02, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0bb17f7e1b](https://linux-hardware.org/?probe=0bb17f7e1b) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [fb7e164f62](https://linux-hardware.org/?probe=fb7e164f62) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [2774be84e6](https://linux-hardware.org/?probe=2774be84e6) | Jul 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [6896f4aafb](https://linux-hardware.org/?probe=6896f4aafb) | Jul 01, 2023 |
| Toshiba       | Satellite Pro L650          | Notebook    | [d8da913f23](https://linux-hardware.org/?probe=d8da913f23) | Jul 01, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [99b07ae636](https://linux-hardware.org/?probe=99b07ae636) | Jun 30, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [69b69e2a09](https://linux-hardware.org/?probe=69b69e2a09) | Jun 30, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [498eb9b539](https://linux-hardware.org/?probe=498eb9b539) | Jun 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [136060092c](https://linux-hardware.org/?probe=136060092c) | Jun 30, 2023 |
| Dell          | Studio 1558                 | Notebook    | [66e76ea87d](https://linux-hardware.org/?probe=66e76ea87d) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | Notebook    | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Lenovo        | ThinkPad T580 20LAS0DL00    | Notebook    | [5d27a44710](https://linux-hardware.org/?probe=5d27a44710) | Jun 28, 2023 |
| HP            | Pavilion 17                 | Notebook    | [01c3ae7698](https://linux-hardware.org/?probe=01c3ae7698) | Jun 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [cc161cc65b](https://linux-hardware.org/?probe=cc161cc65b) | Jun 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [235e541e2d](https://linux-hardware.org/?probe=235e541e2d) | Jun 28, 2023 |
| Acer          | Extensa 2519                | Notebook    | [1a8a4ee11e](https://linux-hardware.org/?probe=1a8a4ee11e) | Jun 27, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [566e7a4396](https://linux-hardware.org/?probe=566e7a4396) | Jun 26, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [8a0a603eef](https://linux-hardware.org/?probe=8a0a603eef) | Jun 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [47a0ae93f4](https://linux-hardware.org/?probe=47a0ae93f4) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [2eeb463035](https://linux-hardware.org/?probe=2eeb463035) | Jun 25, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [ef129b5a6c](https://linux-hardware.org/?probe=ef129b5a6c) | Jun 25, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [3c8a1b23bb](https://linux-hardware.org/?probe=3c8a1b23bb) | Jun 24, 2023 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [1fe939429c](https://linux-hardware.org/?probe=1fe939429c) | Jun 24, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [ddc5e387cb](https://linux-hardware.org/?probe=ddc5e387cb) | Jun 24, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [e700828afa](https://linux-hardware.org/?probe=e700828afa) | Jun 23, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cd9b9aae75](https://linux-hardware.org/?probe=cd9b9aae75) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [784d676a8d](https://linux-hardware.org/?probe=784d676a8d) | Jun 21, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [6a6cfb05d6](https://linux-hardware.org/?probe=6a6cfb05d6) | Jun 20, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [033c027010](https://linux-hardware.org/?probe=033c027010) | Jun 18, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [ac006b8cb7](https://linux-hardware.org/?probe=ac006b8cb7) | Jun 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [fe0d892e82](https://linux-hardware.org/?probe=fe0d892e82) | Jun 16, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b0361fedbc](https://linux-hardware.org/?probe=b0361fedbc) | Jun 16, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [a0e0ea6aa1](https://linux-hardware.org/?probe=a0e0ea6aa1) | Jun 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e68730cae4](https://linux-hardware.org/?probe=e68730cae4) | Jun 13, 2023 |
| HP            | 625 (WT144EA#ABD)           | Notebook    | [352eaf6ce7](https://linux-hardware.org/?probe=352eaf6ce7) | Jun 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [db301ecd59](https://linux-hardware.org/?probe=db301ecd59) | Jun 11, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [bc315fc56f](https://linux-hardware.org/?probe=bc315fc56f) | Jun 11, 2023 |
| HP            | 625 (WT144EA#ABD)           | Notebook    | [673ab1f0a9](https://linux-hardware.org/?probe=673ab1f0a9) | Jun 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c610b3b9fe](https://linux-hardware.org/?probe=c610b3b9fe) | Jun 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [88d3849db5](https://linux-hardware.org/?probe=88d3849db5) | Jun 10, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [e8ed8e8b1e](https://linux-hardware.org/?probe=e8ed8e8b1e) | Jun 09, 2023 |
| AZW           | EQ                          | Desktop     | [98e574abed](https://linux-hardware.org/?probe=98e574abed) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [befd126f43](https://linux-hardware.org/?probe=befd126f43) | Jun 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [e146923f12](https://linux-hardware.org/?probe=e146923f12) | Jun 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f91c977f0](https://linux-hardware.org/?probe=0f91c977f0) | Jun 06, 2023 |
| HP            | 1998                        | Desktop     | [c6183bd564](https://linux-hardware.org/?probe=c6183bd564) | Jun 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ce1569ee48](https://linux-hardware.org/?probe=ce1569ee48) | Jun 05, 2023 |
| Dell          | Latitude E5540              | Notebook    | [d2bde0e098](https://linux-hardware.org/?probe=d2bde0e098) | Jun 04, 2023 |
| Dell          | Latitude E5540              | Notebook    | [f9483c219e](https://linux-hardware.org/?probe=f9483c219e) | Jun 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [0bd595e07a](https://linux-hardware.org/?probe=0bd595e07a) | Jun 04, 2023 |
| Acer          | Aspire TC-705               | Desktop     | [8aa3bc4947](https://linux-hardware.org/?probe=8aa3bc4947) | Jun 03, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [908f094e9d](https://linux-hardware.org/?probe=908f094e9d) | Jun 02, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [f9c0a669c5](https://linux-hardware.org/?probe=f9c0a669c5) | Jun 02, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [c6ee1e5e32](https://linux-hardware.org/?probe=c6ee1e5e32) | Jun 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [46f5148174](https://linux-hardware.org/?probe=46f5148174) | Jun 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [dab4e98680](https://linux-hardware.org/?probe=dab4e98680) | May 31, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [bb05a8a89b](https://linux-hardware.org/?probe=bb05a8a89b) | May 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c0ec67e3b1](https://linux-hardware.org/?probe=c0ec67e3b1) | May 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f46b9b1b6a](https://linux-hardware.org/?probe=f46b9b1b6a) | May 29, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [32fee60a54](https://linux-hardware.org/?probe=32fee60a54) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ec91d28c95](https://linux-hardware.org/?probe=ec91d28c95) | May 28, 2023 |
| Unknown       | HX90                        | Desktop     | [d38fff55af](https://linux-hardware.org/?probe=d38fff55af) | May 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [f4411b6232](https://linux-hardware.org/?probe=f4411b6232) | May 27, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [aa99fb811d](https://linux-hardware.org/?probe=aa99fb811d) | May 26, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [978ae98d6e](https://linux-hardware.org/?probe=978ae98d6e) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [01e2285654](https://linux-hardware.org/?probe=01e2285654) | May 24, 2023 |
| Avell High... | A72 HYB                     | Notebook    | [c6f131b8b1](https://linux-hardware.org/?probe=c6f131b8b1) | May 24, 2023 |
| Avell High... | A72 HYB                     | Notebook    | [d54fb61d87](https://linux-hardware.org/?probe=d54fb61d87) | May 24, 2023 |
| Dell          | Latitude E6510              | Notebook    | [731befae67](https://linux-hardware.org/?probe=731befae67) | May 23, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1ff1bde0f0](https://linux-hardware.org/?probe=1ff1bde0f0) | May 23, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [df04cb5fb1](https://linux-hardware.org/?probe=df04cb5fb1) | May 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [98473b6b1e](https://linux-hardware.org/?probe=98473b6b1e) | May 22, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [15d9163f08](https://linux-hardware.org/?probe=15d9163f08) | May 20, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [7a2e636353](https://linux-hardware.org/?probe=7a2e636353) | May 18, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [5b51a121e2](https://linux-hardware.org/?probe=5b51a121e2) | May 18, 2023 |
| Unknown       | NF-CK804                    | Desktop     | [754a676bd7](https://linux-hardware.org/?probe=754a676bd7) | May 17, 2023 |
| HP            | Pavilion dv6                | Notebook    | [1b931dc36f](https://linux-hardware.org/?probe=1b931dc36f) | May 17, 2023 |
| Dell          | Latitude E7270              | Notebook    | [c3b39e55f4](https://linux-hardware.org/?probe=c3b39e55f4) | May 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7feff56d1d](https://linux-hardware.org/?probe=7feff56d1d) | May 15, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [aa0e7978c5](https://linux-hardware.org/?probe=aa0e7978c5) | May 14, 2023 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [34efd36999](https://linux-hardware.org/?probe=34efd36999) | May 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [41c5120619](https://linux-hardware.org/?probe=41c5120619) | May 14, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b14b7c3725](https://linux-hardware.org/?probe=b14b7c3725) | May 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9759b380bb](https://linux-hardware.org/?probe=9759b380bb) | May 13, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [67122d7cd6](https://linux-hardware.org/?probe=67122d7cd6) | May 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9c8ffba5f4](https://linux-hardware.org/?probe=9c8ffba5f4) | May 12, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e661dd9daf](https://linux-hardware.org/?probe=e661dd9daf) | May 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [af88b26379](https://linux-hardware.org/?probe=af88b26379) | May 09, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4c3e0a0ac6](https://linux-hardware.org/?probe=4c3e0a0ac6) | May 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e877e8df9](https://linux-hardware.org/?probe=9e877e8df9) | May 08, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [e69f8169fc](https://linux-hardware.org/?probe=e69f8169fc) | May 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [836697d300](https://linux-hardware.org/?probe=836697d300) | May 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a95a3bd3a3](https://linux-hardware.org/?probe=a95a3bd3a3) | May 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [11a41c975d](https://linux-hardware.org/?probe=11a41c975d) | May 07, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [0a096de0e1](https://linux-hardware.org/?probe=0a096de0e1) | May 06, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b6ec076cc6](https://linux-hardware.org/?probe=b6ec076cc6) | May 05, 2023 |
| Acer          | Aspire X1430                | Desktop     | [4bdb74f57e](https://linux-hardware.org/?probe=4bdb74f57e) | May 04, 2023 |
| Acer          | Aspire one                  | Notebook    | [90d59ac61a](https://linux-hardware.org/?probe=90d59ac61a) | May 04, 2023 |
| Acer          | Aspire one                  | Notebook    | [aeabc8c63c](https://linux-hardware.org/?probe=aeabc8c63c) | May 03, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [456582ed94](https://linux-hardware.org/?probe=456582ed94) | May 03, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f9c27ab898](https://linux-hardware.org/?probe=f9c27ab898) | May 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b7ff999133](https://linux-hardware.org/?probe=b7ff999133) | May 02, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c56afa707e](https://linux-hardware.org/?probe=c56afa707e) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [99a39f6696](https://linux-hardware.org/?probe=99a39f6696) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [66a3f8bc3a](https://linux-hardware.org/?probe=66a3f8bc3a) | May 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [193fb3ba91](https://linux-hardware.org/?probe=193fb3ba91) | Apr 30, 2023 |
| MSI           | MS-B120                     | Mini pc     | [8019bfa6d4](https://linux-hardware.org/?probe=8019bfa6d4) | Apr 30, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4f10159e93](https://linux-hardware.org/?probe=4f10159e93) | Apr 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [5fd8f6db6e](https://linux-hardware.org/?probe=5fd8f6db6e) | Apr 30, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [2fe28d7f43](https://linux-hardware.org/?probe=2fe28d7f43) | Apr 29, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [ef3f4d1ac1](https://linux-hardware.org/?probe=ef3f4d1ac1) | Apr 29, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c0c226bf8c](https://linux-hardware.org/?probe=c0c226bf8c) | Apr 28, 2023 |
| ASRock        | H170A-X1                    | Desktop     | [a89448e417](https://linux-hardware.org/?probe=a89448e417) | Apr 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2306f31aa2](https://linux-hardware.org/?probe=2306f31aa2) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a660a768ce](https://linux-hardware.org/?probe=a660a768ce) | Apr 26, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | Notebook    | [554f32b909](https://linux-hardware.org/?probe=554f32b909) | Apr 25, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [88a6d9040e](https://linux-hardware.org/?probe=88a6d9040e) | Apr 23, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [b003b5c775](https://linux-hardware.org/?probe=b003b5c775) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [77b462630d](https://linux-hardware.org/?probe=77b462630d) | Apr 18, 2023 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [83f752ffd8](https://linux-hardware.org/?probe=83f752ffd8) | Apr 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f0353d1327](https://linux-hardware.org/?probe=f0353d1327) | Apr 16, 2023 |
| MSI           | G41M-P26                    | Desktop     | [80c102169c](https://linux-hardware.org/?probe=80c102169c) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [b7a63bbfc7](https://linux-hardware.org/?probe=b7a63bbfc7) | Apr 15, 2023 |
| AMI           | Intel                       | Desktop     | [ec0a5e657e](https://linux-hardware.org/?probe=ec0a5e657e) | Apr 14, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [7041b36ac5](https://linux-hardware.org/?probe=7041b36ac5) | Apr 14, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b821e02641](https://linux-hardware.org/?probe=b821e02641) | Apr 13, 2023 |
| ASUSTek       | ROG STRIX X399-E GAMING     | Desktop     | [ecefe27269](https://linux-hardware.org/?probe=ecefe27269) | Apr 13, 2023 |
| HP            | 1494                        | Desktop     | [9c5dc1a221](https://linux-hardware.org/?probe=9c5dc1a221) | Apr 13, 2023 |
| Google        | Chell                       | Notebook    | [64cecf4575](https://linux-hardware.org/?probe=64cecf4575) | Apr 12, 2023 |
| MSI           | G41M-P26                    | Desktop     | [5b6831f7fc](https://linux-hardware.org/?probe=5b6831f7fc) | Apr 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2bb9767ca7](https://linux-hardware.org/?probe=2bb9767ca7) | Apr 10, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [681be67c93](https://linux-hardware.org/?probe=681be67c93) | Apr 09, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [87be7a6dc0](https://linux-hardware.org/?probe=87be7a6dc0) | Apr 09, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| HUAWEI        | NDZ-WXX9                    | Notebook    | [707d59612f](https://linux-hardware.org/?probe=707d59612f) | Apr 05, 2023 |
| HUAWEI        | NDZ-WXX9                    | Notebook    | [058290755b](https://linux-hardware.org/?probe=058290755b) | Apr 05, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [68322a0698](https://linux-hardware.org/?probe=68322a0698) | Apr 04, 2023 |
| RCA           | W101AS23T2                  | Tablet      | [21e469a8a9](https://linux-hardware.org/?probe=21e469a8a9) | Apr 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [08074927ff](https://linux-hardware.org/?probe=08074927ff) | Apr 03, 2023 |
| ASUSTek       | U6Sg                        | Notebook    | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [77187502c9](https://linux-hardware.org/?probe=77187502c9) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [207edc0a25](https://linux-hardware.org/?probe=207edc0a25) | Apr 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [14751f18b3](https://linux-hardware.org/?probe=14751f18b3) | Apr 01, 2023 |
| Dell          | Latitude E6320              | Notebook    | [a6a0d01947](https://linux-hardware.org/?probe=a6a0d01947) | Mar 31, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [53a11e07e8](https://linux-hardware.org/?probe=53a11e07e8) | Mar 31, 2023 |
| Acer          | Aspire XC-1760              | Desktop     | [68e6aec940](https://linux-hardware.org/?probe=68e6aec940) | Mar 30, 2023 |
| MSI           | MS-AA5E 0A                  | All in one  | [36d66ad0a2](https://linux-hardware.org/?probe=36d66ad0a2) | Mar 29, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [a074e581b0](https://linux-hardware.org/?probe=a074e581b0) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [832b434c38](https://linux-hardware.org/?probe=832b434c38) | Mar 28, 2023 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [7e283bfa25](https://linux-hardware.org/?probe=7e283bfa25) | Mar 28, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d56f48b9d1](https://linux-hardware.org/?probe=d56f48b9d1) | Mar 27, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [bd4eec08fb](https://linux-hardware.org/?probe=bd4eec08fb) | Mar 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [4cc097dbcf](https://linux-hardware.org/?probe=4cc097dbcf) | Mar 26, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [fb3f1be00d](https://linux-hardware.org/?probe=fb3f1be00d) | Mar 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [5a95cd6ad5](https://linux-hardware.org/?probe=5a95cd6ad5) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [890cd39d63](https://linux-hardware.org/?probe=890cd39d63) | Mar 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [50387b06e7](https://linux-hardware.org/?probe=50387b06e7) | Mar 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2a9ae9d859](https://linux-hardware.org/?probe=2a9ae9d859) | Mar 26, 2023 |
| Apple         | MacBookAir4,1               | Notebook    | [6b09e87ee2](https://linux-hardware.org/?probe=6b09e87ee2) | Mar 24, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [182b5af958](https://linux-hardware.org/?probe=182b5af958) | Mar 22, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [e46c856c11](https://linux-hardware.org/?probe=e46c856c11) | Mar 22, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [dcae89c3e5](https://linux-hardware.org/?probe=dcae89c3e5) | Mar 21, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [9ff80f0344](https://linux-hardware.org/?probe=9ff80f0344) | Mar 21, 2023 |
| CCE           | NM70-I                      | Desktop     | [3e99b6e12d](https://linux-hardware.org/?probe=3e99b6e12d) | Mar 21, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [ce6f515364](https://linux-hardware.org/?probe=ce6f515364) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [bbe02b925a](https://linux-hardware.org/?probe=bbe02b925a) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [d376f92f8d](https://linux-hardware.org/?probe=d376f92f8d) | Mar 19, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [605bc3d5b0](https://linux-hardware.org/?probe=605bc3d5b0) | Mar 19, 2023 |
| Acer          | Aspire 5570Z                | Notebook    | [a5ba989714](https://linux-hardware.org/?probe=a5ba989714) | Mar 19, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cd8f53a887](https://linux-hardware.org/?probe=cd8f53a887) | Mar 19, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [0bb94771bc](https://linux-hardware.org/?probe=0bb94771bc) | Mar 18, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [45a412e241](https://linux-hardware.org/?probe=45a412e241) | Mar 18, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [4cee2dc95e](https://linux-hardware.org/?probe=4cee2dc95e) | Mar 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7298c4b04b](https://linux-hardware.org/?probe=7298c4b04b) | Mar 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [794bc239ab](https://linux-hardware.org/?probe=794bc239ab) | Mar 17, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [105acd2203](https://linux-hardware.org/?probe=105acd2203) | Mar 16, 2023 |
| Acer          | Aspire 5570Z                | Notebook    | [74cf43f3e2](https://linux-hardware.org/?probe=74cf43f3e2) | Mar 16, 2023 |
| Acer          | Aspire 5570Z                | Notebook    | [afe4b0baa5](https://linux-hardware.org/?probe=afe4b0baa5) | Mar 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [526e33e980](https://linux-hardware.org/?probe=526e33e980) | Mar 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8d2ca6cedc](https://linux-hardware.org/?probe=8d2ca6cedc) | Mar 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2f69480899](https://linux-hardware.org/?probe=2f69480899) | Mar 14, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [aa66f39ad6](https://linux-hardware.org/?probe=aa66f39ad6) | Mar 13, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ef020a54d0](https://linux-hardware.org/?probe=ef020a54d0) | Mar 12, 2023 |
| HP            | 339A                        | Desktop     | [fa78907d67](https://linux-hardware.org/?probe=fa78907d67) | Mar 12, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [4a54741fec](https://linux-hardware.org/?probe=4a54741fec) | Mar 12, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [f9dfd84f86](https://linux-hardware.org/?probe=f9dfd84f86) | Mar 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [406d19d44f](https://linux-hardware.org/?probe=406d19d44f) | Mar 12, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [d5426d5f1e](https://linux-hardware.org/?probe=d5426d5f1e) | Mar 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [729d9395f0](https://linux-hardware.org/?probe=729d9395f0) | Mar 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ee115bdfb8](https://linux-hardware.org/?probe=ee115bdfb8) | Mar 11, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| HP            | Presario CQ61               | Notebook    | [0eab7ae44e](https://linux-hardware.org/?probe=0eab7ae44e) | Mar 09, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [d2ac8dd020](https://linux-hardware.org/?probe=d2ac8dd020) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [adce83e80e](https://linux-hardware.org/?probe=adce83e80e) | Mar 07, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [61e3840465](https://linux-hardware.org/?probe=61e3840465) | Mar 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [cb7ac03a2a](https://linux-hardware.org/?probe=cb7ac03a2a) | Mar 07, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9178ffc6f9](https://linux-hardware.org/?probe=9178ffc6f9) | Mar 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [48cf9d748f](https://linux-hardware.org/?probe=48cf9d748f) | Mar 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [7d1b3a73f9](https://linux-hardware.org/?probe=7d1b3a73f9) | Mar 05, 2023 |
| AZW           | SER V01                     | Mini pc     | [3a34571e3d](https://linux-hardware.org/?probe=3a34571e3d) | Mar 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9f5aaa2900](https://linux-hardware.org/?probe=9f5aaa2900) | Mar 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [05934ca860](https://linux-hardware.org/?probe=05934ca860) | Mar 04, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [bd1f7da7bc](https://linux-hardware.org/?probe=bd1f7da7bc) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [be909f0882](https://linux-hardware.org/?probe=be909f0882) | Mar 03, 2023 |
| Intel         | NUC12EDBi7 M27908-302       | Mini pc     | [bb51e864a7](https://linux-hardware.org/?probe=bb51e864a7) | Mar 03, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [7e85150e30](https://linux-hardware.org/?probe=7e85150e30) | Mar 03, 2023 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [0cd2798326](https://linux-hardware.org/?probe=0cd2798326) | Mar 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [dbc8fc4b0d](https://linux-hardware.org/?probe=dbc8fc4b0d) | Mar 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [884979d592](https://linux-hardware.org/?probe=884979d592) | Mar 01, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b6128fb3e9](https://linux-hardware.org/?probe=b6128fb3e9) | Feb 28, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fd4d00d935](https://linux-hardware.org/?probe=fd4d00d935) | Feb 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [64cf10c762](https://linux-hardware.org/?probe=64cf10c762) | Feb 26, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [fb3c4afbaa](https://linux-hardware.org/?probe=fb3c4afbaa) | Feb 26, 2023 |
| Sony          | VGN-Z21WRN_B                | Notebook    | [c1b765e164](https://linux-hardware.org/?probe=c1b765e164) | Feb 26, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b1a38edcc2](https://linux-hardware.org/?probe=b1a38edcc2) | Feb 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ec82e38ab0](https://linux-hardware.org/?probe=ec82e38ab0) | Feb 25, 2023 |
| ASUSTek       | X550LN                      | Notebook    | [6ebe283b1c](https://linux-hardware.org/?probe=6ebe283b1c) | Feb 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [24b1205b0c](https://linux-hardware.org/?probe=24b1205b0c) | Feb 24, 2023 |
| HP            | Pavilion dv6000 (GF657EA... | Notebook    | [fe52d35d1a](https://linux-hardware.org/?probe=fe52d35d1a) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [ea8027e95b](https://linux-hardware.org/?probe=ea8027e95b) | Feb 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [2cc3513ca3](https://linux-hardware.org/?probe=2cc3513ca3) | Feb 24, 2023 |
| ASUSTek       | P5K                         | Desktop     | [1769888b2b](https://linux-hardware.org/?probe=1769888b2b) | Feb 23, 2023 |
| ASUSTek       | P5QL-E                      | Desktop     | [52c9ec67bf](https://linux-hardware.org/?probe=52c9ec67bf) | Feb 23, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| HP            | 85A2                        | All in one  | [c9f6d95fb2](https://linux-hardware.org/?probe=c9f6d95fb2) | Feb 21, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [e1a9b1b0fa](https://linux-hardware.org/?probe=e1a9b1b0fa) | Feb 21, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [fa50111733](https://linux-hardware.org/?probe=fa50111733) | Feb 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [76d6c3ad48](https://linux-hardware.org/?probe=76d6c3ad48) | Feb 19, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [e08dcd6c59](https://linux-hardware.org/?probe=e08dcd6c59) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [2b56edae65](https://linux-hardware.org/?probe=2b56edae65) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [dde311dcb2](https://linux-hardware.org/?probe=dde311dcb2) | Feb 19, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [68dcf39492](https://linux-hardware.org/?probe=68dcf39492) | Feb 18, 2023 |
| Dell          | Inspiron 14-3452            | Notebook    | [e2cc024607](https://linux-hardware.org/?probe=e2cc024607) | Feb 18, 2023 |
| Sony          | VPCEB2Z1E                   | Notebook    | [5c172121ab](https://linux-hardware.org/?probe=5c172121ab) | Feb 17, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [1029c7f3bb](https://linux-hardware.org/?probe=1029c7f3bb) | Feb 17, 2023 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [741b7c300c](https://linux-hardware.org/?probe=741b7c300c) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | Notebook    | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [90fb04bc05](https://linux-hardware.org/?probe=90fb04bc05) | Feb 17, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ebca46331e](https://linux-hardware.org/?probe=ebca46331e) | Feb 16, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f3d6e20575](https://linux-hardware.org/?probe=f3d6e20575) | Feb 16, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [d380600b31](https://linux-hardware.org/?probe=d380600b31) | Feb 15, 2023 |
| Lenovo        | ThinkPad SL 2746AHG         | Notebook    | [c141867fa3](https://linux-hardware.org/?probe=c141867fa3) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| Lenovo        | ThinkPad T470 20HES13701    | Notebook    | [9c839fa75b](https://linux-hardware.org/?probe=9c839fa75b) | Feb 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [f41fcff6ff](https://linux-hardware.org/?probe=f41fcff6ff) | Feb 13, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9565a9f43b](https://linux-hardware.org/?probe=9565a9f43b) | Feb 11, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ba06eb3e9c](https://linux-hardware.org/?probe=ba06eb3e9c) | Feb 11, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [8a16d2e4bb](https://linux-hardware.org/?probe=8a16d2e4bb) | Feb 11, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [127e027611](https://linux-hardware.org/?probe=127e027611) | Feb 10, 2023 |
| Lenovo        | 3741 SDK0T76463 WIN 3422... | Desktop     | [14bde69d96](https://linux-hardware.org/?probe=14bde69d96) | Feb 10, 2023 |
| MSI           | MS-B120                     | Mini pc     | [1d365cbddd](https://linux-hardware.org/?probe=1d365cbddd) | Feb 10, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [fb254cca56](https://linux-hardware.org/?probe=fb254cca56) | Feb 10, 2023 |
| Lenovo        | ThinkPad T470 20HES13701    | Notebook    | [fef1f72c3a](https://linux-hardware.org/?probe=fef1f72c3a) | Feb 09, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [647f120e0b](https://linux-hardware.org/?probe=647f120e0b) | Feb 08, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [0f01d55766](https://linux-hardware.org/?probe=0f01d55766) | Feb 08, 2023 |
| HP            | 240 G3                      | Notebook    | [e3a0318824](https://linux-hardware.org/?probe=e3a0318824) | Feb 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [ac340725d3](https://linux-hardware.org/?probe=ac340725d3) | Feb 07, 2023 |
| HP            | Presario CQ56               | Notebook    | [3c6de43677](https://linux-hardware.org/?probe=3c6de43677) | Feb 05, 2023 |
| BESSTAR Te... | CB9                         | Mini pc     | [23fe29b164](https://linux-hardware.org/?probe=23fe29b164) | Feb 05, 2023 |
| Sony          | VPCEH1E1E                   | Notebook    | [76589a7570](https://linux-hardware.org/?probe=76589a7570) | Feb 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a55eba93cc](https://linux-hardware.org/?probe=a55eba93cc) | Feb 04, 2023 |
| Dell          | Precision 7550              | Notebook    | [392db977df](https://linux-hardware.org/?probe=392db977df) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1a189b08ea](https://linux-hardware.org/?probe=1a189b08ea) | Feb 03, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a174385328](https://linux-hardware.org/?probe=a174385328) | Feb 02, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [4644d239d7](https://linux-hardware.org/?probe=4644d239d7) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c402e9c063](https://linux-hardware.org/?probe=c402e9c063) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [eb152c7d4e](https://linux-hardware.org/?probe=eb152c7d4e) | Feb 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [58d5bdaa2d](https://linux-hardware.org/?probe=58d5bdaa2d) | Jan 31, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [6f95748149](https://linux-hardware.org/?probe=6f95748149) | Jan 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [10cdf2558f](https://linux-hardware.org/?probe=10cdf2558f) | Jan 29, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [09bbe80125](https://linux-hardware.org/?probe=09bbe80125) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4333734c92](https://linux-hardware.org/?probe=4333734c92) | Jan 29, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [190a780b8a](https://linux-hardware.org/?probe=190a780b8a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a4ded61661](https://linux-hardware.org/?probe=a4ded61661) | Jan 27, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [609a89ca14](https://linux-hardware.org/?probe=609a89ca14) | Jan 27, 2023 |
| Notebook      | P17SM-A                     | Notebook    | [6ed204eca5](https://linux-hardware.org/?probe=6ed204eca5) | Jan 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [26e692f7de](https://linux-hardware.org/?probe=26e692f7de) | Jan 26, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [a3a0a3a505](https://linux-hardware.org/?probe=a3a0a3a505) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7c19df8c01](https://linux-hardware.org/?probe=7c19df8c01) | Jan 25, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [54d0592fb2](https://linux-hardware.org/?probe=54d0592fb2) | Jan 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [206e04bc7d](https://linux-hardware.org/?probe=206e04bc7d) | Jan 23, 2023 |
| Hardkernel    | ODROID-N2Plus               | Soc         | [eb2e4b24cc](https://linux-hardware.org/?probe=eb2e4b24cc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3a542dd368](https://linux-hardware.org/?probe=3a542dd368) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [9e9dcb9883](https://linux-hardware.org/?probe=9e9dcb9883) | Jan 22, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [fdca7d69cd](https://linux-hardware.org/?probe=fdca7d69cd) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [9536b9eedc](https://linux-hardware.org/?probe=9536b9eedc) | Jan 22, 2023 |
| Google        | Relm                        | Notebook    | [44fb1d9db1](https://linux-hardware.org/?probe=44fb1d9db1) | Jan 21, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.1    | Soc         | [571389ffa0](https://linux-hardware.org/?probe=571389ffa0) | Jan 21, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_MATE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu MATE 20.04 | 665       | 36.44%  |
| Ubuntu MATE 22.04 | 442       | 24.22%  |
| Ubuntu MATE 18.04 | 276       | 15.12%  |
| Ubuntu MATE 24.04 | 94        | 5.15%   |
| Ubuntu MATE 20.10 | 54        | 2.96%   |
| Ubuntu MATE 19.10 | 48        | 2.63%   |
| Ubuntu MATE 21.10 | 45        | 2.47%   |
| Ubuntu MATE 21.04 | 42        | 2.3%    |
| Ubuntu MATE 23.10 | 41        | 2.25%   |
| Ubuntu MATE 22.10 | 39        | 2.14%   |
| Ubuntu MATE 23.04 | 33        | 1.81%   |
| Ubuntu MATE 16.04 | 23        | 1.26%   |
| Ubuntu MATE 24.10 | 11        | 0.6%    |
| Ubuntu MATE       | 4         | 0.22%   |
| Ubuntu MATE 19.04 | 2         | 0.11%   |
| Ubuntu MATE 18.10 | 2         | 0.11%   |
| Ubuntu MATE 17.04 | 2         | 0.11%   |
| Ubuntu MATE 16.10 | 1         | 0.05%   |
| Ubuntu MATE 15.04 | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Ubuntu MATE | 1728      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 5.4.0-42-generic   | 57        | 2.72%   |
| 5.4.0-48-generic   | 44        | 2.1%    |
| 5.4.0-52-generic   | 35        | 1.67%   |
| 5.4.0-47-generic   | 31        | 1.48%   |
| 5.15.0-56-generic  | 31        | 1.48%   |
| 5.4.0-65-generic   | 23        | 1.1%    |
| 5.4.0-58-generic   | 19        | 0.91%   |
| 6.2.0-26-generic   | 18        | 0.86%   |
| 5.4.0-40-generic   | 18        | 0.86%   |
| 5.15.0-47-generic  | 18        | 0.86%   |
| 4.15.0-163-generic | 17        | 0.81%   |
| 5.8.0-48-generic   | 16        | 0.76%   |
| 5.4.0-45-generic   | 16        | 0.76%   |
| 5.3.0-46-generic   | 16        | 0.76%   |
| 5.3.0-40-generic   | 16        | 0.76%   |
| 6.8.0-45-generic   | 15        | 0.72%   |
| 5.15.0-48-generic  | 15        | 0.72%   |
| 5.15.0-46-generic  | 14        | 0.67%   |
| 6.8.0-40-generic   | 13        | 0.62%   |
| 6.5.0-35-generic   | 13        | 0.62%   |
| 5.4.0-94-generic   | 13        | 0.62%   |
| 5.3.0-42-generic   | 13        | 0.62%   |
| 5.15.0-60-generic  | 13        | 0.62%   |
| 5.15.0-58-generic  | 13        | 0.62%   |
| 5.11.0-40-generic  | 13        | 0.62%   |
| 6.2.0-32-generic   | 12        | 0.57%   |
| 5.8.0-50-generic   | 12        | 0.57%   |
| 5.4.0-81-generic   | 12        | 0.57%   |
| 5.4.0-56-generic   | 12        | 0.57%   |
| 5.15.0-67-generic  | 12        | 0.57%   |
| 5.15.0-52-generic  | 12        | 0.57%   |
| 5.15.0-43-generic  | 12        | 0.57%   |
| 6.5.0-14-generic   | 11        | 0.53%   |
| 6.2.0-36-generic   | 11        | 0.53%   |
| 5.4.0-26-generic   | 11        | 0.53%   |
| 5.15.0-40-generic  | 11        | 0.53%   |
| 5.15.0-25-generic  | 11        | 0.53%   |
| 5.13.0-30-generic  | 11        | 0.53%   |
| 6.8.0-51-generic   | 10        | 0.48%   |
| 5.4.0-89-generic   | 10        | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 533       | 28.16%  |
| 5.15.0  | 308       | 16.27%  |
| 5.3.0   | 118       | 6.23%   |
| 5.8.0   | 106       | 5.6%    |
| 4.15.0  | 104       | 5.49%   |
| 6.8.0   | 102       | 5.39%   |
| 5.11.0  | 97        | 5.12%   |
| 6.5.0   | 92        | 4.86%   |
| 5.13.0  | 89        | 4.7%    |
| 6.2.0   | 86        | 4.54%   |
| 5.19.0  | 77        | 4.07%   |
| 5.0.0   | 15        | 0.79%   |
| 6.11.0  | 10        | 0.53%   |
| 4.4.0   | 10        | 0.53%   |
| 5.14.0  | 8         | 0.42%   |
| 6.4.0   | 4         | 0.21%   |
| 5.17.0  | 4         | 0.21%   |
| 5.10.27 | 4         | 0.21%   |
| 4.9.277 | 4         | 0.21%   |
| 4.18.0  | 4         | 0.21%   |
| 6.5.7   | 3         | 0.16%   |
| 6.4.3   | 3         | 0.16%   |
| 6.3.0   | 3         | 0.16%   |
| 6.10.2  | 3         | 0.16%   |
| 5.18.0  | 3         | 0.16%   |
| 4.9.337 | 3         | 0.16%   |
| 4.10.0  | 3         | 0.16%   |
| 6.7.3   | 2         | 0.11%   |
| 6.6.1   | 2         | 0.11%   |
| 6.3.7   | 2         | 0.11%   |
| 6.3.4   | 2         | 0.11%   |
| 6.3.1   | 2         | 0.11%   |
| 6.2.11  | 2         | 0.11%   |
| 6.12.1  | 2         | 0.11%   |
| 6.1.12  | 2         | 0.11%   |
| 6.1.0   | 2         | 0.11%   |
| 5.4.2   | 2         | 0.11%   |
| 5.10.5  | 2         | 0.11%   |
| 5.10.0  | 2         | 0.11%   |
| 4.4.154 | 2         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 537       | 28.59%  |
| 5.15    | 313       | 16.67%  |
| 5.3     | 118       | 6.28%   |
| 5.8     | 108       | 5.75%   |
| 6.8     | 105       | 5.59%   |
| 4.15    | 104       | 5.54%   |
| 5.11    | 97        | 5.17%   |
| 6.5     | 95        | 5.06%   |
| 6.2     | 89        | 4.74%   |
| 5.13    | 89        | 4.74%   |
| 5.19    | 77        | 4.1%    |
| 5.0     | 15        | 0.8%    |
| 4.4     | 13        | 0.69%   |
| 6.11    | 11        | 0.59%   |
| 6.4     | 8         | 0.43%   |
| 5.14    | 8         | 0.43%   |
| 5.10    | 8         | 0.43%   |
| 4.9     | 8         | 0.43%   |
| 6.10    | 7         | 0.37%   |
| 6.6     | 6         | 0.32%   |
| 6.3     | 6         | 0.32%   |
| 6.1     | 6         | 0.32%   |
| 6.7     | 5         | 0.27%   |
| 5.17    | 5         | 0.27%   |
| 6.12    | 4         | 0.21%   |
| 4.18    | 4         | 0.21%   |
| 4.14    | 4         | 0.21%   |
| 6.0     | 3         | 0.16%   |
| 5.9     | 3         | 0.16%   |
| 5.18    | 3         | 0.16%   |
| 4.10    | 3         | 0.16%   |
| 6.9     | 2         | 0.11%   |
| 5.7     | 2         | 0.11%   |
| 5.6     | 2         | 0.11%   |
| 5.5     | 2         | 0.11%   |
| 5.12    | 2         | 0.11%   |
| 5.16    | 1         | 0.05%   |
| 4.8     | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |
| 3.19    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1583      | 91.61%  |
| i686    | 82        | 4.75%   |
| aarch64 | 50        | 2.89%   |
| armv7l  | 12        | 0.69%   |
| ppc     | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 1687      | 97.57%  |
| X-Cinnamon | 10        | 0.58%   |
| GNOME      | 10        | 0.58%   |
| Cinnamon   | 8         | 0.46%   |
| KDE5       | 7         | 0.4%    |
| Trinity    | 2         | 0.12%   |
| Budgie     | 2         | 0.12%   |
| XFCE       | 1         | 0.06%   |
| KDE6       | 1         | 0.06%   |
| i3         | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1673      | 96.65%  |
| Tty     | 36        | 2.08%   |
| Wayland | 22        | 1.27%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 866       | 48.35%  |
| Unknown | 497       | 27.75%  |
| TDM     | 309       | 17.25%  |
| GDM3    | 64        | 3.57%   |
| GDM     | 38        | 2.12%   |
| SDDM    | 7         | 0.39%   |
| LXDM    | 6         | 0.34%   |
| SLiM    | 4         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 601       | 34.5%   |
| de_DE   | 170       | 9.76%   |
| fr_FR   | 162       | 9.3%    |
| pt_BR   | 125       | 7.18%   |
| it_IT   | 83        | 4.76%   |
| en_GB   | 78        | 4.48%   |
| ru_RU   | 57        | 3.27%   |
| es_ES   | 54        | 3.1%    |
| Unknown | 38        | 2.18%   |
| el_GR   | 36        | 2.07%   |
| en_CA   | 35        | 2.01%   |
| C       | 35        | 2.01%   |
| en_AU   | 27        | 1.55%   |
| pl_PL   | 19        | 1.09%   |
| es_AR   | 17        | 0.98%   |
| hu_HU   | 14        | 0.8%    |
| en_IN   | 13        | 0.75%   |
| sv_SE   | 11        | 0.63%   |
| nl_NL   | 11        | 0.63%   |
| fi_FI   | 11        | 0.63%   |
| de_CH   | 9         | 0.52%   |
| es_MX   | 8         | 0.46%   |
| cs_CZ   | 8         | 0.46%   |
| es_PE   | 7         | 0.4%    |
| ru_UA   | 6         | 0.34%   |
| ja_JP   | 6         | 0.34%   |
| es_VE   | 6         | 0.34%   |
| es_CL   | 6         | 0.34%   |
| zh_TW   | 5         | 0.29%   |
| tr_TR   | 5         | 0.29%   |
| en_IL   | 5         | 0.29%   |
| pt_PT   | 4         | 0.23%   |
| nl_BE   | 4         | 0.23%   |
| fr_CA   | 4         | 0.23%   |
| en_PH   | 4         | 0.23%   |
| de_AT   | 4         | 0.23%   |
| da_DK   | 4         | 0.23%   |
| hr_HR   | 3         | 0.17%   |
| et_EE   | 3         | 0.17%   |
| es_GT   | 3         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 955       | 54.17%  |
| EFI  | 808       | 45.83%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1497      | 84.72%  |
| Tmpfs   | 128       | 7.24%   |
| Overlay | 63        | 3.57%   |
| Btrfs   | 30        | 1.7%    |
| Zfs     | 19        | 1.08%   |
| Xfs     | 9         | 0.51%   |
| Unknown | 9         | 0.51%   |
| Ext3    | 4         | 0.23%   |
| Aufs    | 3         | 0.17%   |
| Jfs     | 2         | 0.11%   |
| Ext2    | 2         | 0.11%   |
| ExX4    | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 839       | 47.21%  |
| Unknown | 608       | 34.21%  |
| MBR     | 330       | 18.57%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1495      | 85.28%  |
| Yes       | 258       | 14.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1166      | 66.48%  |
| Yes       | 588       | 33.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 294       | 17.01%  |
| ASUSTek Computer        | 248       | 14.35%  |
| Dell                    | 233       | 13.48%  |
| Lenovo                  | 219       | 12.67%  |
| MSI                     | 92        | 5.32%   |
| Gigabyte Technology     | 92        | 5.32%   |
| Acer                    | 78        | 4.51%   |
| ASRock                  | 51        | 2.95%   |
| Raspberry Pi Foundation | 42        | 2.43%   |
| Intel                   | 42        | 2.43%   |
| Toshiba                 | 30        | 1.74%   |
| Unknown                 | 25        | 1.45%   |
| Apple                   | 24        | 1.39%   |
| Sony                    | 18        | 1.04%   |
| Samsung Electronics     | 15        | 0.87%   |
| Fujitsu                 | 15        | 0.87%   |
| Hardkernel              | 14        | 0.81%   |
| Medion                  | 11        | 0.64%   |
| Notebook                | 8         | 0.46%   |
| Supermicro              | 7         | 0.41%   |
| AZW                     | 7         | 0.41%   |
| Positivo                | 6         | 0.35%   |
| Packard Bell            | 6         | 0.35%   |
| Biostar                 | 6         | 0.35%   |
| AMI                     | 6         | 0.35%   |
| System76                | 5         | 0.29%   |
| Pegatron                | 5         | 0.29%   |
| Google                  | 5         | 0.29%   |
| Clevo                   | 5         | 0.29%   |
| HUAWEI                  | 4         | 0.23%   |
| Fujitsu Siemens         | 4         | 0.23%   |
| Foxconn                 | 4         | 0.23%   |
| ECS                     | 4         | 0.23%   |
| TUXEDO                  | 3         | 0.17%   |
| TrekStor                | 3         | 0.17%   |
| Semp Toshiba            | 3         | 0.17%   |
| Quanta                  | 3         | 0.17%   |
| Microsoft               | 3         | 0.17%   |
| LG Electronics          | 3         | 0.17%   |
| GPD                     | 3         | 0.17%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 37        | 2.14%   |
| ASUS All Series                    | 13        | 0.75%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 12        | 0.69%   |
| HP Compaq Elite 8300 SFF           | 10        | 0.58%   |
| RPi Raspberry Pi                   | 9         | 0.52%   |
| RPi Raspberry Pi 4 Model B Rev 1.2 | 8         | 0.46%   |
| HP ProDesk 600 G1 SFF              | 8         | 0.46%   |
| HP Compaq 6005 Pro SFF PC          | 8         | 0.46%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 7         | 0.41%   |
| HP Pavilion g6                     | 7         | 0.41%   |
| Hardkernel ODROID-N2Plus           | 7         | 0.41%   |
| Dell Latitude E6410                | 7         | 0.41%   |
| HP Notebook                        | 6         | 0.35%   |
| MSI MS-7817                        | 5         | 0.29%   |
| HP Pavilion dv7                    | 5         | 0.29%   |
| Dell Precision M4800               | 5         | 0.29%   |
| Dell OptiPlex 390                  | 5         | 0.29%   |
| Dell OptiPlex 3010                 | 5         | 0.29%   |
| Dell Latitude E6420                | 5         | 0.29%   |
| ASUS M5A97 R2.0                    | 5         | 0.29%   |
| Lenovo IdeaPad 3 15IIL05 81WE      | 4         | 0.23%   |
| HP Compaq 8000 Elite SFF PC        | 4         | 0.23%   |
| HP Compaq 6200 Pro SFF PC          | 4         | 0.23%   |
| Dell OptiPlex GX520                | 4         | 0.23%   |
| Dell OptiPlex 755                  | 4         | 0.23%   |
| Dell OptiPlex 360                  | 4         | 0.23%   |
| ASUS PRIME B450M-A II              | 4         | 0.23%   |
| ASRock B450M Pro4                  | 4         | 0.23%   |
| TrekStor Surfbook A13B             | 3         | 0.17%   |
| RPi Raspberry Pi 3 Model B Rev 1.2 | 3         | 0.17%   |
| MSI MS-7C56                        | 3         | 0.17%   |
| MSI MS-7C51                        | 3         | 0.17%   |
| HP ProLiant MicroServer            | 3         | 0.17%   |
| HP ProBook 640 G8 Notebook PC      | 3         | 0.17%   |
| HP Pavilion dv4                    | 3         | 0.17%   |
| HP Pavilion 17                     | 3         | 0.17%   |
| HP 15                              | 3         | 0.17%   |
| Hardkernel ODROID-C4               | 3         | 0.17%   |
| Hardkernel Odroid XU4              | 3         | 0.17%   |
| Gigabyte B450M DS3H                | 3         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 102       | 5.9%    |
| Dell Latitude            | 65        | 3.76%   |
| Dell OptiPlex            | 61        | 3.53%   |
| Acer Aspire              | 54        | 3.13%   |
| HP Pavilion              | 52        | 3.01%   |
| HP Compaq                | 50        | 2.89%   |
| RPi Raspberry            | 42        | 2.43%   |
| Lenovo IdeaPad           | 41        | 2.37%   |
| Unknown                  | 37        | 2.14%   |
| HP EliteBook             | 35        | 2.03%   |
| Dell Precision           | 34        | 1.97%   |
| ASUS PRIME               | 32        | 1.85%   |
| Dell Inspiron            | 30        | 1.74%   |
| Toshiba Satellite        | 27        | 1.56%   |
| HP ProBook               | 23        | 1.33%   |
| ASUS ROG                 | 20        | 1.16%   |
| Lenovo ThinkCentre       | 19        | 1.1%    |
| Dell XPS                 | 13        | 0.75%   |
| ASUS All                 | 13        | 0.75%   |
| HP Laptop                | 12        | 0.69%   |
| Dell Vostro              | 12        | 0.69%   |
| ASUS VivoBook            | 12        | 0.69%   |
| HP ProDesk               | 11        | 0.64%   |
| Fujitsu LIFEBOOK         | 11        | 0.64%   |
| HP EliteDesk             | 10        | 0.58%   |
| HP ENVY                  | 9         | 0.52%   |
| ASUS TUF                 | 9         | 0.52%   |
| Lenovo ThinkBook         | 8         | 0.46%   |
| HP 250                   | 8         | 0.46%   |
| HP ZBook                 | 7         | 0.41%   |
| HP ProLiant              | 7         | 0.41%   |
| Hardkernel ODROID-N2Plus | 7         | 0.41%   |
| ASUS M5A97               | 7         | 0.41%   |
| ASUS M5A78L-M            | 7         | 0.41%   |
| Lenovo Legion            | 6         | 0.35%   |
| Lenovo IdeaPadFlex       | 6         | 0.35%   |
| HP Notebook              | 6         | 0.35%   |
| Acer TravelMate          | 6         | 0.35%   |
| Packard Bell EasyNote    | 5         | 0.29%   |
| MSI MS-7817              | 5         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 151       | 8.74%   |
| 2011    | 149       | 8.62%   |
| 2012    | 148       | 8.56%   |
| 2018    | 130       | 7.52%   |
| 2013    | 123       | 7.12%   |
| 2019    | 116       | 6.71%   |
| 2021    | 107       | 6.19%   |
| 2014    | 97        | 5.61%   |
| 2010    | 95        | 5.5%    |
| 2017    | 92        | 5.32%   |
| 2009    | 84        | 4.86%   |
| 2008    | 81        | 4.69%   |
| 2015    | 76        | 4.4%    |
| 2016    | 71        | 4.11%   |
| 2022    | 47        | 2.72%   |
| 2007    | 44        | 2.55%   |
| Unknown | 41        | 2.37%   |
| 2023    | 29        | 1.68%   |
| 2006    | 28        | 1.62%   |
| 2005    | 12        | 0.69%   |
| 2024    | 4         | 0.23%   |
| 2004    | 1         | 0.06%   |
| 2003    | 1         | 0.06%   |
| 2002    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 878       | 50.81%  |
| Desktop        | 676       | 39.12%  |
| System on chip | 60        | 3.47%   |
| Mini pc        | 35        | 2.03%   |
| Convertible    | 25        | 1.45%   |
| All in one     | 21        | 1.22%   |
| Server         | 18        | 1.04%   |
| Tablet         | 15        | 0.87%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1616      | 93.03%  |
| Enabled  | 121       | 6.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1721      | 99.59%  |
| Yes  | 7         | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 407       | 23.19%  |
| 4.01-8.0        | 379       | 21.6%   |
| 16.01-24.0      | 285       | 16.24%  |
| 8.01-16.0       | 272       | 15.5%   |
| 32.01-64.0      | 154       | 8.77%   |
| 1.01-2.0        | 85        | 4.84%   |
| 64.01-256.0     | 78        | 4.44%   |
| 2.01-3.0        | 38        | 2.17%   |
| 24.01-32.0      | 31        | 1.77%   |
| 0.51-1.0        | 24        | 1.37%   |
| More than 256.0 | 1         | 0.06%   |
| 0.01-0.5        | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 645       | 34.4%   |
| 2.01-3.0   | 443       | 23.63%  |
| 4.01-8.0   | 247       | 13.17%  |
| 3.01-4.0   | 222       | 11.84%  |
| 0.51-1.0   | 208       | 11.09%  |
| 8.01-16.0  | 63        | 3.36%   |
| 0.01-0.5   | 21        | 1.12%   |
| 24.01-32.0 | 11        | 0.59%   |
| 16.01-24.0 | 9         | 0.48%   |
| 32.01-64.0 | 6         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1071      | 60.41%  |
| 2      | 438       | 24.7%   |
| 3      | 134       | 7.56%   |
| 4      | 64        | 3.61%   |
| 5      | 22        | 1.24%   |
| 6      | 13        | 0.73%   |
| 0      | 12        | 0.68%   |
| 7      | 6         | 0.34%   |
| 10     | 3         | 0.17%   |
| 9      | 3         | 0.17%   |
| 8      | 3         | 0.17%   |
| 11     | 2         | 0.11%   |
| 20     | 1         | 0.06%   |
| 12     | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 959       | 55.08%  |
| Yes       | 782       | 44.92%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1507      | 87.06%  |
| No        | 224       | 12.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1221      | 70.01%  |
| No        | 523       | 29.99%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 928       | 53.06%  |
| No        | 821       | 46.94%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 254       | 14.61%  |
| Germany     | 204       | 11.74%  |
| France      | 171       | 9.84%   |
| Brazil      | 152       | 8.75%   |
| Italy       | 100       | 5.75%   |
| Russia      | 84        | 4.83%   |
| UK          | 76        | 4.37%   |
| Spain       | 71        | 4.09%   |
| Greece      | 45        | 2.59%   |
| Canada      | 38        | 2.19%   |
| Australia   | 29        | 1.67%   |
| Poland      | 28        | 1.61%   |
| Argentina   | 26        | 1.5%    |
| Netherlands | 23        | 1.32%   |
| Hungary     | 22        | 1.27%   |
| Switzerland | 21        | 1.21%   |
| Finland     | 20        | 1.15%   |
| India       | 19        | 1.09%   |
| Belgium     | 19        | 1.09%   |
| Mexico      | 18        | 1.04%   |
| Austria     | 18        | 1.04%   |
| Turkey      | 17        | 0.98%   |
| Ukraine     | 16        | 0.92%   |
| Sweden      | 16        | 0.92%   |
| Czechia     | 14        | 0.81%   |
| Indonesia   | 12        | 0.69%   |
| Portugal    | 11        | 0.63%   |
| Romania     | 10        | 0.58%   |
| Norway      | 10        | 0.58%   |
| Denmark     | 10        | 0.58%   |
| Chile       | 10        | 0.58%   |
| Peru        | 9         | 0.52%   |
| Thailand    | 8         | 0.46%   |
| Japan       | 8         | 0.46%   |
| Estonia     | 8         | 0.46%   |
| Venezuela   | 7         | 0.4%    |
| Taiwan      | 7         | 0.4%    |
| Israel      | 7         | 0.4%    |
| Croatia     | 6         | 0.35%   |
| Bulgaria    | 6         | 0.35%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 79        | 4.28%   |
| Paris             | 33        | 1.79%   |
| Moscow            | 33        | 1.79%   |
| Berlin            | 24        | 1.3%    |
| Thessaloniki      | 19        | 1.03%   |
| Rome              | 17        | 0.92%   |
| Athens            | 17        | 0.92%   |
| St Petersburg     | 10        | 0.54%   |
| Los Angeles       | 10        | 0.54%   |
| Hamburg           | 10        | 0.54%   |
| Vienna            | 9         | 0.49%   |
| Madrid            | 9         | 0.49%   |
| Budapest          | 9         | 0.49%   |
| Manchester        | 8         | 0.43%   |
| Helsinki          | 8         | 0.43%   |
| Warsaw            | 7         | 0.38%   |
| Rio de Janeiro    | 7         | 0.38%   |
| Melbourne         | 7         | 0.38%   |
| Mannheim          | 7         | 0.38%   |
| Frankfurt am Main | 7         | 0.38%   |
| Barcelona         | 7         | 0.38%   |
| Zurich            | 6         | 0.33%   |
| Sundbyberg        | 6         | 0.33%   |
| Rochester         | 6         | 0.33%   |
| Munich            | 6         | 0.33%   |
| Kyiv              | 6         | 0.33%   |
| Brisbane          | 6         | 0.33%   |
| Bengaluru         | 6         | 0.33%   |
| Amsterdam         | 6         | 0.33%   |
| Wittingen         | 5         | 0.27%   |
| Sydney            | 5         | 0.27%   |
| Perth             | 5         | 0.27%   |
| Montpellier       | 5         | 0.27%   |
| Milan             | 5         | 0.27%   |
| Lisbon            | 5         | 0.27%   |
| Cologne           | 5         | 0.27%   |
| Vancouver         | 4         | 0.22%   |
| Toronto           | 4         | 0.22%   |
| Stuttgart         | 4         | 0.22%   |
| Southampton       | 4         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 389       | 616    | 15.56%  |
| WDC                         | 380       | 584    | 15.2%   |
| Samsung Electronics         | 380       | 663    | 15.2%   |
| Toshiba                     | 153       | 237    | 6.12%   |
| Unknown                     | 149       | 199    | 5.96%   |
| Kingston                    | 138       | 180    | 5.52%   |
| SanDisk                     | 112       | 133    | 4.48%   |
| Crucial                     | 100       | 137    | 4%      |
| Hitachi                     | 88        | 105    | 3.52%   |
| SK hynix                    | 56        | 73     | 2.24%   |
| Intel                       | 49        | 65     | 1.96%   |
| A-DATA Technology           | 35        | 38     | 1.4%    |
| China                       | 29        | 35     | 1.16%   |
| HGST                        | 28        | 36     | 1.12%   |
| KIOXIA                      | 19        | 20     | 0.76%   |
| Phison                      | 18        | 19     | 0.72%   |
| Micron Technology           | 18        | 20     | 0.72%   |
| PNY                         | 17        | 18     | 0.68%   |
| Fujitsu                     | 16        | 18     | 0.64%   |
| SPCC                        | 14        | 23     | 0.56%   |
| Intenso                     | 14        | 18     | 0.56%   |
| Silicon Motion              | 12        | 13     | 0.48%   |
| Patriot                     | 12        | 14     | 0.48%   |
| Hewlett-Packard             | 11        | 16     | 0.44%   |
| Transcend                   | 10        | 19     | 0.4%    |
| Unknown                     | 10        | 11     | 0.4%    |
| Corsair                     | 9         | 10     | 0.36%   |
| Netac                       | 8         | 8      | 0.32%   |
| Maxtor                      | 8         | 14     | 0.32%   |
| LITEONIT                    | 8         | 9      | 0.32%   |
| JMicron Technology          | 8         | 11     | 0.32%   |
| Apple                       | 8         | 9      | 0.32%   |
| Phison Electronics          | 7         | 7      | 0.28%   |
| OCZ                         | 7         | 7      | 0.28%   |
| Micron/Crucial Technology   | 7         | 12     | 0.28%   |
| LITEON                      | 7         | 8      | 0.28%   |
| Kingston Technology Company | 7         | 10     | 0.28%   |
| Apacer                      | 7         | 8      | 0.28%   |
| KingSpec                    | 6         | 9      | 0.24%   |
| Team                        | 5         | 5      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                               | 32        | 1.15%   |
| Seagate ST500DM002-1BD142 500GB                      | 30        | 1.08%   |
| Unknown MMC Card  64GB                               | 25        | 0.9%    |
| Kingston SA400S37120G 120GB SSD                      | 24        | 0.87%   |
| Kingston SA400S37240G 240GB SSD                      | 23        | 0.83%   |
| Samsung SSD 860 EVO 500GB                            | 21        | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 17        | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB                       | 15        | 0.54%   |
| Kingston SA400S37480G 480GB SSD                      | 15        | 0.54%   |
| Toshiba MQ01ABF050 500GB                             | 14        | 0.51%   |
| Seagate ST1000DM003-1ER162 1TB                       | 14        | 0.51%   |
| Seagate ST2000DM008-2FR102 2TB                       | 13        | 0.47%   |
| Kingston SV300S37A120G 120GB SSD                     | 13        | 0.47%   |
| Toshiba DT01ACA050 500GB                             | 12        | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB                       | 12        | 0.43%   |
| Samsung SSD 850 EVO 250GB                            | 12        | 0.43%   |
| Crucial CT500MX500SSD1 500GB                         | 12        | 0.43%   |
| Unknown MMC Card  16GB                               | 11        | 0.4%    |
| Unknown MMC Card  128GB                              | 11        | 0.4%    |
| Toshiba DT01ACA100 1TB                               | 11        | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                      | 11        | 0.4%    |
| Seagate ST3500418AS 500GB                            | 11        | 0.4%    |
| Samsung SSD 850 EVO 500GB                            | 11        | 0.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 11        | 0.4%    |
| Toshiba MQ01ABD100 1TB                               | 10        | 0.36%   |
| Seagate ST9500325AS 500GB                            | 10        | 0.36%   |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 10        | 0.36%   |
| Seagate ST1000DM010-2EP102 1TB                       | 10        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB                       | 10        | 0.36%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 10        | 0.36%   |
| Crucial CT1000BX500SSD1 1TB                          | 10        | 0.36%   |
| Unknown                                              | 10        | 0.36%   |
| WDC WD20EZRZ-00Z5HB0 2TB                             | 9         | 0.32%   |
| Samsung SSD 980 1TB                                  | 9         | 0.32%   |
| Crucial CT1000MX500SSD1 1TB                          | 9         | 0.32%   |
| Seagate ST4000DM004-2CV104 4TB                       | 8         | 0.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 8         | 0.29%   |
| Seagate Expansion 1TB                                | 8         | 0.29%   |
| Samsung SSD 980 PRO 1TB                              | 8         | 0.29%   |
| Samsung SSD 970 EVO Plus 1TB                         | 8         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 387       | 611    | 36.72%  |
| WDC                 | 316       | 491    | 29.98%  |
| Toshiba             | 119       | 184    | 11.29%  |
| Hitachi             | 88        | 105    | 8.35%   |
| Samsung Electronics | 50        | 69     | 4.74%   |
| HGST                | 28        | 36     | 2.66%   |
| Fujitsu             | 16        | 18     | 1.52%   |
| Unknown             | 9         | 12     | 0.85%   |
| Maxtor              | 7         | 11     | 0.66%   |
| Hewlett-Packard     | 6         | 10     | 0.57%   |
| SABRENT             | 5         | 5      | 0.47%   |
| JMicron Technology  | 4         | 5      | 0.38%   |
| ASMT                | 3         | 4      | 0.28%   |
| SAGE                | 2         | 2      | 0.19%   |
| IBM/Hitachi         | 2         | 2      | 0.19%   |
| ASMT109x            | 2         | 3      | 0.19%   |
| TO Exter            | 1         | 1      | 0.09%   |
| StoreJet            | 1         | 1      | 0.09%   |
| MaxDigital          | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| KESU                | 1         | 4      | 0.09%   |
| Inateck             | 1         | 1      | 0.09%   |
| DAS                 | 1         | 6      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |
| Apricorn            | 1         | 1      | 0.09%   |
| Apple               | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 201       | 336    | 24.72%  |
| Kingston            | 116       | 149    | 14.27%  |
| Crucial             | 88        | 124    | 10.82%  |
| SanDisk             | 79        | 95     | 9.72%   |
| WDC                 | 44        | 58     | 5.41%   |
| China               | 28        | 34     | 3.44%   |
| A-DATA Technology   | 26        | 28     | 3.2%    |
| Intel               | 24        | 34     | 2.95%   |
| PNY                 | 16        | 17     | 1.97%   |
| Toshiba             | 13        | 17     | 1.6%    |
| SPCC                | 11        | 19     | 1.35%   |
| Intenso             | 11        | 14     | 1.35%   |
| Transcend           | 10        | 19     | 1.23%   |
| SK hynix            | 10        | 15     | 1.23%   |
| Patriot             | 9         | 11     | 1.11%   |
| LITEONIT            | 8         | 9      | 0.98%   |
| OCZ                 | 7         | 7      | 0.86%   |
| Netac               | 7         | 7      | 0.86%   |
| Apacer              | 7         | 8      | 0.86%   |
| Micron Technology   | 6         | 8      | 0.74%   |
| LITEON              | 6         | 7      | 0.74%   |
| KingSpec            | 6         | 9      | 0.74%   |
| Verbatim            | 4         | 20     | 0.49%   |
| Team                | 4         | 4      | 0.49%   |
| FORESEE             | 4         | 4      | 0.49%   |
| Plextor             | 3         | 3      | 0.37%   |
| LDLC                | 3         | 3      | 0.37%   |
| KingFast            | 3         | 3      | 0.37%   |
| Argon               | 3         | 5      | 0.37%   |
| Apple               | 3         | 3      | 0.37%   |
| Vaseky              | 2         | 2      | 0.25%   |
| Seagate             | 2         | 2      | 0.25%   |
| Fanxiang            | 2         | 2      | 0.25%   |
| Corsair             | 2         | 2      | 0.25%   |
| BAITITON            | 2         | 2      | 0.25%   |
| AMD                 | 2         | 2      | 0.25%   |
| AGI                 | 2         | 3      | 0.25%   |
| Unknown             | 2         | 2      | 0.25%   |
| WDC WDS2            | 1         | 1      | 0.12%   |
| USB3.0              | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 894       | 1586   | 39.98%  |
| SSD     | 714       | 1129   | 31.93%  |
| NVMe    | 451       | 663    | 20.17%  |
| MMC     | 133       | 176    | 5.95%   |
| Unknown | 44        | 61     | 1.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1324      | 2611   | 65.45%  |
| NVMe | 451       | 659    | 22.29%  |
| MMC  | 133       | 176    | 6.57%   |
| SAS  | 115       | 169    | 5.68%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 998       | 1562   | 58.53%  |
| 0.51-1.0   | 439       | 675    | 25.75%  |
| 1.01-2.0   | 147       | 237    | 8.62%   |
| 3.01-4.0   | 55        | 78     | 3.23%   |
| 4.01-10.0  | 36        | 109    | 2.11%   |
| 2.01-3.0   | 23        | 40     | 1.35%   |
| 10.01-20.0 | 7         | 14     | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 462       | 25.54%  |
| 251-500        | 427       | 23.6%   |
| 501-1000       | 280       | 15.48%  |
| 1001-2000      | 155       | 8.57%   |
| 51-100         | 130       | 7.19%   |
| More than 3000 | 119       | 6.58%   |
| 21-50          | 73        | 4.04%   |
| 1-20           | 73        | 4.04%   |
| 2001-3000      | 58        | 3.21%   |
| Unknown        | 32        | 1.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 568       | 30.65%  |
| 21-50          | 309       | 16.68%  |
| 101-250        | 271       | 14.62%  |
| 51-100         | 227       | 12.25%  |
| 251-500        | 163       | 8.8%    |
| 501-1000       | 122       | 6.58%   |
| 1001-2000      | 74        | 3.99%   |
| More than 3000 | 53        | 2.86%   |
| 2001-3000      | 34        | 1.83%   |
| Unknown        | 32        | 1.73%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 9         | 9      | 4.25%   |
| Seagate ST3500418AS 500GB             | 5         | 5      | 2.36%   |
| Seagate ST320LT007-9ZV142 320GB       | 5         | 5      | 2.36%   |
| WDC WD5000AAKX-083CA1 500GB           | 4         | 4      | 1.89%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 1.89%   |
| Seagate ST9500325AS 500GB             | 3         | 3      | 1.42%   |
| WDC WD5000AAKX-003CA0 500GB           | 2         | 2      | 0.94%   |
| WDC WD3200BEVT-60ZCT1 320GB           | 2         | 2      | 0.94%   |
| WDC WD2500AAKX-753CA1 250GB           | 2         | 2      | 0.94%   |
| WDC WD10EADS-00L5B1 1TB               | 2         | 4      | 0.94%   |
| Unknown MM0500EANCR 500GB             | 2         | 5      | 0.94%   |
| Toshiba MK7559GSXP 752GB              | 2         | 2      | 0.94%   |
| Seagate ST9500420AS 500GB             | 2         | 2      | 0.94%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 0.94%   |
| Seagate ST9160821AS 160GB             | 2         | 2      | 0.94%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.94%   |
| Seagate ST2000DM001-9YN164 2TB        | 2         | 3      | 0.94%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 0.94%   |
| Seagate ST1000DM003-1CH162 1TB        | 2         | 2      | 0.94%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 0.94%   |
| Samsung Electronics SSD 870 EVO 1TB   | 2         | 2      | 0.94%   |
| Samsung Electronics HD502HJ 500GB     | 2         | 2      | 0.94%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.94%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 2      | 0.94%   |
| Hitachi HTS542516K9SA00 160GB         | 2         | 2      | 0.94%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.47%   |
| WDC WD7500BPVX-60JC3T0 752GB          | 1         | 2      | 0.47%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 1         | 1      | 0.47%   |
| WDC WD7500BPVT-75HXZT1 752GB          | 1         | 1      | 0.47%   |
| WDC WD7500BPVT-22A1YT0 752GB          | 1         | 1      | 0.47%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.47%   |
| WDC WD5003AZEX-00K3CA0 500GB          | 1         | 1      | 0.47%   |
| WDC WD5000LUCT-63RC2Y0 500GB          | 1         | 1      | 0.47%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.47%   |
| WDC WD5000BPKT-75PK4T0 500GB          | 1         | 2      | 0.47%   |
| WDC WD5000AAKX-22ERMA0 500GB          | 1         | 2      | 0.47%   |
| WDC WD5000AAKS-00V1A0 500GB           | 1         | 3      | 0.47%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 0.47%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 0.47%   |
| WDC WD40EFAX-68JH4N0 4TB              | 1         | 2      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 68     | 30.43%  |
| WDC                 | 53        | 68     | 25.6%   |
| Samsung Electronics | 18        | 22     | 8.7%    |
| Hitachi             | 16        | 16     | 7.73%   |
| Toshiba             | 13        | 13     | 6.28%   |
| Kingston            | 5         | 6      | 2.42%   |
| Intel               | 5         | 6      | 2.42%   |
| OCZ                 | 4         | 4      | 1.93%   |
| Crucial             | 3         | 3      | 1.45%   |
| Unknown             | 2         | 5      | 0.97%   |
| SK hynix            | 2         | 5      | 0.97%   |
| SanDisk             | 2         | 2      | 0.97%   |
| Maxtor              | 2         | 2      | 0.97%   |
| HGST                | 2         | 3      | 0.97%   |
| Fujitsu             | 2         | 2      | 0.97%   |
| China               | 2         | 2      | 0.97%   |
| A-DATA Technology   | 2         | 4      | 0.97%   |
| Vaseky              | 1         | 1      | 0.48%   |
| NGFF                | 1         | 1      | 0.48%   |
| Netac               | 1         | 1      | 0.48%   |
| LITEON              | 1         | 1      | 0.48%   |
| LDLC                | 1         | 1      | 0.48%   |
| Intenso             | 1         | 1      | 0.48%   |
| IBM/Hitachi         | 1         | 1      | 0.48%   |
| Eluktro             | 1         | 1      | 0.48%   |
| DAS                 | 1         | 3      | 0.48%   |
| ASMT                | 1         | 2      | 0.48%   |
| Apricorn            | 1         | 1      | 0.48%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 68     | 39.13%  |
| WDC                 | 50        | 65     | 31.06%  |
| Hitachi             | 16        | 16     | 9.94%   |
| Toshiba             | 13        | 13     | 8.07%   |
| Samsung Electronics | 8         | 9      | 4.97%   |
| Unknown             | 2         | 5      | 1.24%   |
| Maxtor              | 2         | 2      | 1.24%   |
| HGST                | 2         | 3      | 1.24%   |
| Fujitsu             | 2         | 2      | 1.24%   |
| IBM/Hitachi         | 1         | 1      | 0.62%   |
| DAS                 | 1         | 3      | 0.62%   |
| Apricorn            | 1         | 1      | 0.62%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 154       | 188    | 77.39%  |
| SSD  | 37        | 41     | 18.59%  |
| NVMe | 8         | 16     | 4.02%   |

Failed Drives
-------------

Failed drive models

Zero info for selected period =(

Failed Drive Vendor
-------------------

Failed drive vendors

Zero info for selected period =(

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 863       | 1834   | 44.95%  |
| Works    | 862       | 1536   | 44.9%   |
| Malfunc  | 195       | 245    | 10.16%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1149      | 56.05%  |
| AMD                              | 308       | 15.02%  |
| Samsung Electronics              | 155       | 7.56%   |
| Sandisk                          | 60        | 2.93%   |
| SK hynix                         | 43        | 2.1%    |
| Phison Electronics               | 38        | 1.85%   |
| Nvidia                           | 32        | 1.56%   |
| ASMedia Technology               | 31        | 1.51%   |
| Kingston Technology Company      | 29        | 1.41%   |
| Toshiba America Info Systems     | 25        | 1.22%   |
| Marvell Technology Group         | 22        | 1.07%   |
| Silicon Motion                   | 20        | 0.98%   |
| KIOXIA                           | 17        | 0.83%   |
| JMicron Technology               | 17        | 0.83%   |
| Micron/Crucial Technology        | 16        | 0.78%   |
| Micron Technology                | 14        | 0.68%   |
| ADATA Technology                 | 13        | 0.63%   |
| Silicon Integrated Systems [SiS] | 9         | 0.44%   |
| VIA Technologies                 | 6         | 0.29%   |
| LSI Logic / Symbios Logic        | 6         | 0.29%   |
| Realtek Semiconductor            | 5         | 0.24%   |
| MAXIO Technology (Hangzhou)      | 5         | 0.24%   |
| Union Memory (Shenzhen)          | 4         | 0.2%    |
| Hewlett-Packard                  | 4         | 0.2%    |
| Solid State Storage Technology   | 3         | 0.15%   |
| Shenzhen Longsys Electronics     | 3         | 0.15%   |
| Solidigm                         | 2         | 0.1%    |
| Broadcom / LSI                   | 2         | 0.1%    |
| TenaFe                           | 1         | 0.05%   |
| Silicon Image                    | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |
| Integrated Technology Express    | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |
| Apacer Technology                | 1         | 0.05%   |
| Adaptec                          | 1         | 0.05%   |
| 3ware                            | 1         | 0.05%   |
| Unknown                          | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 180       | 7.47%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 87        | 3.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 80        | 3.32%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 62        | 2.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 60        | 2.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 58        | 2.41%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 53        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 50        | 2.08%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 47        | 1.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 46        | 1.91%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 44        | 1.83%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 42        | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 42        | 1.74%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 34        | 1.41%   |
| AMD 400 Series Chipset SATA Controller                                                  | 34        | 1.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 32        | 1.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 31        | 1.29%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 31        | 1.29%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 31        | 1.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 31        | 1.29%   |
| Intel SATA Controller [RAID mode]                                                       | 29        | 1.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 29        | 1.2%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 27        | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 26        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 26        | 1.08%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 26        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 25        | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 25        | 1.04%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 25        | 1.04%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 22        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 22        | 0.91%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 21        | 0.87%   |
| AMD 500 Series Chipset SATA Controller                                                  | 21        | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 20        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 20        | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 20        | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 19        | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 18        | 0.75%   |
| Phison E12 NVMe Controller                                                              | 17        | 0.71%   |
| Nvidia MCP61 SATA Controller                                                            | 17        | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1210      | 57.95%  |
| NVMe | 449       | 21.5%   |
| IDE  | 294       | 14.08%  |
| RAID | 125       | 5.99%   |
| SAS  | 7         | 0.34%   |
| SCSI | 3         | 0.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1293      | 74.83%  |
| AMD          | 371       | 21.47%  |
| ARM          | 62        | 3.59%   |
| PowerBook5,6 | 1         | 0.06%   |
| CentaurHauls | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 50        | 2.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 15        | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 13        | 0.75%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 0.58%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.58%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 10        | 0.58%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 0.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 9         | 0.52%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.46%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.46%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 8         | 0.46%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 8         | 0.46%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 8         | 0.46%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8         | 0.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.4%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 7         | 0.4%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 7         | 0.4%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 7         | 0.4%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 7         | 0.4%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.4%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.4%    |
| Intel Core i5-2540M CPU @ 2.60GHz             | 7         | 0.4%    |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 0.4%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 7         | 0.4%    |
| AMD Phenom II X4 B97 Processor                | 7         | 0.4%    |
| AMD FX-6300 Six-Core Processor                | 7         | 0.4%    |
| Intel Pentium CPU N3540 @ 2.16GHz             | 6         | 0.35%   |
| Intel Pentium 4 CPU 3.00GHz                   | 6         | 0.35%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 6         | 0.35%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 6         | 0.35%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 6         | 0.35%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 348       | 20.14%  |
| Intel Core i7           | 264       | 15.28%  |
| Other                   | 161       | 9.32%   |
| Intel Core i3           | 125       | 7.23%   |
| Intel Celeron           | 104       | 6.02%   |
| Intel Core 2 Duo        | 81        | 4.69%   |
| AMD Ryzen 5             | 78        | 4.51%   |
| Intel Pentium           | 56        | 3.24%   |
| Intel Xeon              | 48        | 2.78%   |
| AMD Ryzen 7             | 46        | 2.66%   |
| Intel Atom              | 39        | 2.26%   |
| Intel Pentium Dual-Core | 26        | 1.5%    |
| AMD FX                  | 26        | 1.5%    |
| Intel Core 2 Quad       | 20        | 1.16%   |
| AMD Ryzen 9             | 20        | 1.16%   |
| AMD Ryzen 3             | 18        | 1.04%   |
| AMD Athlon II X2        | 18        | 1.04%   |
| AMD A6                  | 14        | 0.81%   |
| AMD Phenom II X4        | 13        | 0.75%   |
| Intel Genuine           | 12        | 0.69%   |
| AMD A8                  | 12        | 0.69%   |
| Intel Pentium 4         | 11        | 0.64%   |
| AMD A4                  | 11        | 0.64%   |
| Intel Core i9           | 10        | 0.58%   |
| Intel Core 2            | 8         | 0.46%   |
| ARM BCM                 | 8         | 0.46%   |
| AMD Athlon              | 8         | 0.46%   |
| Intel Pentium Silver    | 7         | 0.41%   |
| Intel Pentium Dual      | 7         | 0.41%   |
| Intel Pentium D         | 7         | 0.41%   |
| AMD Turion 64 X2 Mobile | 7         | 0.41%   |
| AMD A10                 | 7         | 0.41%   |
| AMD Ryzen 7 PRO         | 6         | 0.35%   |
| AMD E                   | 6         | 0.35%   |
| AMD Athlon 64 X2        | 6         | 0.35%   |
| AMD Ryzen Threadripper  | 5         | 0.29%   |
| AMD E1                  | 5         | 0.29%   |
| AMD Athlon II X4        | 5         | 0.29%   |
| AMD Ryzen 5 PRO         | 4         | 0.23%   |
| AMD Phenom II X6        | 4         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 717       | 41.37%  |
| 4       | 631       | 36.41%  |
| 6       | 148       | 8.54%   |
| 8       | 91        | 5.25%   |
| 1       | 50        | 2.89%   |
| 12      | 24        | 1.38%   |
| 16      | 17        | 0.98%   |
| 3       | 14        | 0.81%   |
| 10      | 13        | 0.75%   |
| 14      | 10        | 0.58%   |
| 24      | 6         | 0.35%   |
| Unknown | 6         | 0.35%   |
| 32      | 2         | 0.12%   |
| 20      | 2         | 0.12%   |
| 28      | 1         | 0.06%   |
| 5       | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1691      | 97.75%  |
| 2       | 32        | 1.85%   |
| Unknown | 5         | 0.29%   |
| 4       | 2         | 0.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 992       | 57.27%  |
| 1       | 734       | 42.38%  |
| Unknown | 6         | 0.35%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1659      | 95.95%  |
| Unknown        | 39        | 2.26%   |
| 32-bit         | 28        | 1.62%   |
| 64-bit         | 3         | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 610       | 34.04%  |
| 0x306a9    | 93        | 5.19%   |
| 0x206a7    | 91        | 5.08%   |
| 0x306c3    | 78        | 4.35%   |
| 0x1067a    | 62        | 3.46%   |
| 0x806ec    | 32        | 1.79%   |
| 0x806c1    | 30        | 1.67%   |
| 0x6fd      | 29        | 1.62%   |
| 0x40651    | 27        | 1.51%   |
| 0x010000c8 | 26        | 1.45%   |
| 0x906e9    | 25        | 1.4%    |
| 0x506e3    | 25        | 1.4%    |
| 0x906ea    | 24        | 1.34%   |
| 0x806ea    | 24        | 1.34%   |
| 0x406c4    | 21        | 1.17%   |
| 0x20655    | 21        | 1.17%   |
| 0x30678    | 20        | 1.12%   |
| 0x806e9    | 19        | 1.06%   |
| 0x406e3    | 19        | 1.06%   |
| 0x306d4    | 18        | 1%      |
| 0x08108109 | 17        | 0.95%   |
| 0x10676    | 16        | 0.89%   |
| 0x0a50000c | 16        | 0.89%   |
| 0x706e5    | 14        | 0.78%   |
| 0x706a1    | 14        | 0.78%   |
| 0x06000852 | 14        | 0.78%   |
| 0x08701021 | 13        | 0.73%   |
| 0x20652    | 11        | 0.61%   |
| 0x106e5    | 11        | 0.61%   |
| 0x0800820d | 11        | 0.61%   |
| 0xa0671    | 10        | 0.56%   |
| 0x6fb      | 10        | 0.56%   |
| 0x08600106 | 10        | 0.56%   |
| 0x06001119 | 10        | 0.56%   |
| 0x906ed    | 9         | 0.5%    |
| 0x106ca    | 9         | 0.5%    |
| 0x05000119 | 9         | 0.5%    |
| 0x806d1    | 8         | 0.45%   |
| 0x706a8    | 8         | 0.45%   |
| 0x07030105 | 8         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 213       | 12.28%  |
| Haswell          | 150       | 8.65%   |
| SandyBridge      | 140       | 8.07%   |
| IvyBridge        | 126       | 7.27%   |
| Unknown          | 110       | 6.34%   |
| Penryn           | 102       | 5.88%   |
| Skylake          | 71        | 4.09%   |
| Silvermont       | 63        | 3.63%   |
| Core             | 59        | 3.4%    |
| K10              | 56        | 3.23%   |
| Zen 2            | 52        | 3%      |
| Westmere         | 52        | 3%      |
| Zen+             | 44        | 2.54%   |
| Zen 3            | 41        | 2.36%   |
| TigerLake        | 39        | 2.25%   |
| Icelake          | 37        | 2.13%   |
| Piledriver       | 35        | 2.02%   |
| Goldmont plus    | 34        | 1.96%   |
| CometLake        | 34        | 1.96%   |
| Broadwell        | 33        | 1.9%    |
| Zen              | 31        | 1.79%   |
| Alderlake Hybrid | 24        | 1.38%   |
| K8 Hammer        | 23        | 1.33%   |
| Nehalem          | 22        | 1.27%   |
| Excavator        | 22        | 1.27%   |
| Bonnell          | 21        | 1.21%   |
| NetBurst         | 20        | 1.15%   |
| P6               | 14        | 0.81%   |
| Puma             | 11        | 0.63%   |
| Bobcat           | 11        | 0.63%   |
| Jaguar           | 9         | 0.52%   |
| Goldmont         | 9         | 0.52%   |
| Bulldozer        | 6         | 0.35%   |
| Tremont          | 5         | 0.29%   |
| Steamroller      | 5         | 0.29%   |
| K8 & K10 hybrid  | 5         | 0.29%   |
| Gracemont        | 3         | 0.17%   |
| K10 Llano        | 2         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 997       | 51.79%  |
| Nvidia                           | 473       | 24.57%  |
| AMD                              | 431       | 22.39%  |
| Matrox Electronics Systems       | 9         | 0.47%   |
| Silicon Integrated Systems [SiS] | 6         | 0.31%   |
| ASPEED Technology                | 6         | 0.31%   |
| VIA Technologies                 | 3         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 93        | 4.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 3.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 46        | 2.32%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 36        | 1.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 35        | 1.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 34        | 1.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 33        | 1.66%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 30        | 1.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 30        | 1.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 29        | 1.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 1.41%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 1.41%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 27        | 1.36%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 27        | 1.36%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 27        | 1.36%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 26        | 1.31%   |
| Intel UHD Graphics 620                                                                   | 25        | 1.26%   |
| Intel HD Graphics 5500                                                                   | 25        | 1.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 25        | 1.26%   |
| Intel HD Graphics 530                                                                    | 24        | 1.21%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 1.21%   |
| Intel HD Graphics 630                                                                    | 21        | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 21        | 1.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 1.06%   |
| Intel HD Graphics 620                                                                    | 20        | 1.01%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 20        | 1.01%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 0.91%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 18        | 0.91%   |
| Nvidia GT218 [GeForce 210]                                                               | 17        | 0.86%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 17        | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.81%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 15        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 14        | 0.71%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 14        | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 13        | 0.66%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 13        | 0.66%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 12        | 0.61%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 12        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 772       | 44.57%  |
| 1 x AMD                  | 343       | 19.8%   |
| 1 x Nvidia               | 282       | 16.28%  |
| Intel + Nvidia           | 160       | 9.24%   |
| Other                    | 63        | 3.64%   |
| Intel + AMD              | 42        | 2.42%   |
| 2 x AMD                  | 20        | 1.15%   |
| AMD + Nvidia             | 20        | 1.15%   |
| 1 x SiS                  | 6         | 0.35%   |
| 1 x Matrox               | 6         | 0.35%   |
| 2 x Nvidia               | 4         | 0.23%   |
| 1 x VIA                  | 3         | 0.17%   |
| Nvidia + Matrox          | 3         | 0.17%   |
| 1 x ASPEED               | 3         | 0.17%   |
| AMD + ASPEED             | 2         | 0.12%   |
| 2 x Intel                | 1         | 0.06%   |
| Nvidia + ASPEED          | 1         | 0.06%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1317      | 75.39%  |
| Proprietary | 300       | 17.17%  |
| Unknown     | 130       | 7.44%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1044      | 58.95%  |
| 1.01-2.0   | 208       | 11.74%  |
| 0.01-0.5   | 202       | 11.41%  |
| 0.51-1.0   | 131       | 7.4%    |
| 3.01-4.0   | 94        | 5.31%   |
| 7.01-8.0   | 45        | 2.54%   |
| 5.01-6.0   | 25        | 1.41%   |
| 2.01-3.0   | 10        | 0.56%   |
| 8.01-16.0  | 6         | 0.34%   |
| 16.01-24.0 | 5         | 0.28%   |
| 4.01-5.0   | 1         | 0.06%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 265       | 14.47%  |
| AU Optronics            | 193       | 10.53%  |
| LG Display              | 151       | 8.24%   |
| Dell                    | 150       | 8.19%   |
| Chimei Innolux          | 128       | 6.99%   |
| BOE                     | 121       | 6.6%    |
| Goldstar                | 101       | 5.51%   |
| Hewlett-Packard         | 81        | 4.42%   |
| Philips                 | 57        | 3.11%   |
| Acer                    | 56        | 3.06%   |
| BenQ                    | 38        | 2.07%   |
| Ancor Communications    | 34        | 1.86%   |
| AOC                     | 33        | 1.8%    |
| Chi Mei Optoelectronics | 28        | 1.53%   |
| Lenovo                  | 26        | 1.42%   |
| Iiyama                  | 25        | 1.36%   |
| Apple                   | 25        | 1.36%   |
| Sharp                   | 23        | 1.26%   |
| ViewSonic               | 22        | 1.2%    |
| Unknown                 | 16        | 0.87%   |
| PANDA                   | 16        | 0.87%   |
| Sony                    | 15        | 0.82%   |
| LG Philips              | 12        | 0.66%   |
| LG Electronics          | 12        | 0.66%   |
| ASUSTek Computer        | 11        | 0.6%    |
| Vizio                   | 9         | 0.49%   |
| HannStar                | 9         | 0.49%   |
| NEC Computers           | 8         | 0.44%   |
| Fujitsu Siemens         | 8         | 0.44%   |
| Eizo                    | 8         | 0.44%   |
| InfoVision              | 7         | 0.38%   |
| CSO                     | 6         | 0.33%   |
| Panasonic               | 5         | 0.27%   |
| Packard Bell            | 5         | 0.27%   |
| Medion                  | 5         | 0.27%   |
| Belinea                 | 5         | 0.27%   |
| Toshiba                 | 4         | 0.22%   |
| Sceptre Tech            | 4         | 0.22%   |
| RTK                     | 4         | 0.22%   |
| Hitachi                 | 4         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Dell 1708FP DEL4023 1280x1024 338x270mm 17.0-inch                        | 31        | 1.63%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 11        | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.53%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 8         | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.37%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 6         | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 6         | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 6         | 0.32%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 5         | 0.26%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.26%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 5         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.26%   |
| BenQ G610HDA BNQ7819 1366x768 344x194mm 15.5-inch                        | 5         | 0.26%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 5         | 0.26%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                      | 5         | 0.26%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch            | 4         | 0.21%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch        | 4         | 0.21%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch     | 4         | 0.21%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                  | 4         | 0.21%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 4         | 0.21%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 4         | 0.21%   |
| Iiyama PL2773H IVM660A 1920x1080 600x340mm 27.2-inch                     | 4         | 0.21%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 677x290mm 29.0-inch                 | 4         | 0.21%   |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch                | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 4         | 0.21%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.21%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.21%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 4         | 0.21%   |
| Vizio VXW20LHDTV10A VIZ0035 1366x768 440x250mm 19.9-inch                 | 3         | 0.16%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 3         | 0.16%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.16%   |
| Samsung Electronics S23B550 SAM0919 1920x1080 510x287mm 23.0-inch        | 3         | 0.16%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.16%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.16%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 3         | 0.16%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch        | 3         | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 689       | 39.3%   |
| 1366x768 (WXGA)    | 330       | 18.82%  |
| 1280x1024 (SXGA)   | 128       | 7.3%    |
| 3840x2160 (4K)     | 86        | 4.91%   |
| 1600x900 (HD+)     | 83        | 4.73%   |
| 2560x1440 (QHD)    | 68        | 3.88%   |
| 1920x1200 (WUXGA)  | 51        | 2.91%   |
| 1680x1050 (WSXGA+) | 46        | 2.62%   |
| 1280x800 (WXGA)    | 46        | 2.62%   |
| 1440x900 (WXGA+)   | 43        | 2.45%   |
| Unknown            | 26        | 1.48%   |
| 1360x768           | 25        | 1.43%   |
| 3440x1440          | 14        | 0.8%    |
| 1024x600           | 14        | 0.8%    |
| 2560x1600          | 11        | 0.63%   |
| 3840x1080          | 10        | 0.57%   |
| 1600x1200          | 10        | 0.57%   |
| 2560x1080          | 7         | 0.4%    |
| 1024x768 (XGA)     | 6         | 0.34%   |
| 3840x2400          | 5         | 0.29%   |
| 3200x1800 (QHD+)   | 4         | 0.23%   |
| 2880x1800          | 4         | 0.23%   |
| 1920x540           | 4         | 0.23%   |
| 1280x720 (HD)      | 4         | 0.23%   |
| 2288x1287          | 3         | 0.17%   |
| 2160x1440          | 3         | 0.17%   |
| 1920x1280          | 3         | 0.17%   |
| 3840x1200          | 2         | 0.11%   |
| 2880x1620          | 2         | 0.11%   |
| 2736x1824          | 2         | 0.11%   |
| 1680x945           | 2         | 0.11%   |
| 1400x1050          | 2         | 0.11%   |
| 6400x1080          | 1         | 0.06%   |
| 5840x1440          | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 5360x1440          | 1         | 0.06%   |
| 5040x1050          | 1         | 0.06%   |
| 4480x1440          | 1         | 0.06%   |
| 4240x1440          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 396       | 21.72%  |
| 17      | 167       | 9.16%   |
| 14      | 137       | 7.52%   |
| 24      | 127       | 6.97%   |
| 13      | 124       | 6.8%    |
| 27      | 120       | 6.58%   |
| 21      | 108       | 5.92%   |
| 23      | 105       | 5.76%   |
| Unknown | 101       | 5.54%   |
| 19      | 63        | 3.46%   |
| 31      | 49        | 2.69%   |
| 18      | 45        | 2.47%   |
| 12      | 34        | 1.87%   |
| 22      | 32        | 1.76%   |
| 20      | 25        | 1.37%   |
| 11      | 25        | 1.37%   |
| 34      | 21        | 1.15%   |
| 10      | 21        | 1.15%   |
| 16      | 14        | 0.77%   |
| 84      | 12        | 0.66%   |
| 40      | 12        | 0.66%   |
| 32      | 11        | 0.6%    |
| 72      | 10        | 0.55%   |
| 54      | 7         | 0.38%   |
| 46      | 7         | 0.38%   |
| 25      | 7         | 0.38%   |
| 33      | 6         | 0.33%   |
| 52      | 5         | 0.27%   |
| 42      | 5         | 0.27%   |
| 36      | 5         | 0.27%   |
| 26      | 5         | 0.27%   |
| 38      | 3         | 0.16%   |
| 142     | 2         | 0.11%   |
| 85      | 1         | 0.05%   |
| 74      | 1         | 0.05%   |
| 65      | 1         | 0.05%   |
| 63      | 1         | 0.05%   |
| 57      | 1         | 0.05%   |
| 49      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 676       | 37.64%  |
| 501-600        | 326       | 18.15%  |
| 401-500        | 234       | 13.03%  |
| 351-400        | 141       | 7.85%   |
| 201-300        | 138       | 7.68%   |
| Unknown        | 101       | 5.62%   |
| 601-700        | 64        | 3.56%   |
| 701-800        | 43        | 2.39%   |
| 1501-2000      | 24        | 1.34%   |
| 1001-1500      | 24        | 1.34%   |
| 801-900        | 16        | 0.89%   |
| 901-1000       | 6         | 0.33%   |
| More than 2000 | 2         | 0.11%   |
| 101-200        | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1190      | 71.69%  |
| 16/10   | 203       | 12.23%  |
| 5/4     | 115       | 6.93%   |
| Unknown | 82        | 4.94%   |
| 21/9    | 22        | 1.33%   |
| 4/3     | 20        | 1.2%    |
| 3/2     | 19        | 1.14%   |
| 6/5     | 4         | 0.24%   |
| 1.00    | 2         | 0.12%   |
| 32/9    | 1         | 0.06%   |
| 1.96    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 384       | 21.33%  |
| 201-250        | 284       | 15.78%  |
| 81-90          | 209       | 11.61%  |
| 301-350        | 121       | 6.72%   |
| 141-150        | 117       | 6.5%    |
| 151-200        | 115       | 6.39%   |
| Unknown        | 101       | 5.61%   |
| 351-500        | 87        | 4.83%   |
| 121-130        | 71        | 3.94%   |
| 251-300        | 61        | 3.39%   |
| 71-80          | 48        | 2.67%   |
| More than 1000 | 41        | 2.28%   |
| 61-70          | 34        | 1.89%   |
| 501-1000       | 34        | 1.89%   |
| 51-60          | 26        | 1.44%   |
| 41-50          | 20        | 1.11%   |
| 111-120        | 20        | 1.11%   |
| 131-140        | 17        | 0.94%   |
| 91-100         | 9         | 0.5%    |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 660       | 37.63%  |
| 101-120       | 452       | 25.77%  |
| 121-160       | 387       | 22.06%  |
| Unknown       | 101       | 5.76%   |
| 161-240       | 75        | 4.28%   |
| 1-50          | 53        | 3.02%   |
| More than 240 | 26        | 1.48%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1377      | 78.82%  |
| 2     | 258       | 14.77%  |
| 0     | 80        | 4.58%   |
| 3     | 31        | 1.77%   |
| 4     | 1         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 902       | 35.58%  |
| Intel                             | 791       | 31.2%   |
| Qualcomm Atheros                  | 264       | 10.41%  |
| Broadcom                          | 164       | 6.47%   |
| Broadcom Limited                  | 48        | 1.89%   |
| Ralink Technology                 | 32        | 1.26%   |
| TP-Link                           | 30        | 1.18%   |
| Marvell Technology Group          | 30        | 1.18%   |
| Ralink                            | 28        | 1.1%    |
| Nvidia                            | 26        | 1.03%   |
| MediaTek                          | 24        | 0.95%   |
| ASIX Electronics                  | 18        | 0.71%   |
| Sierra Wireless                   | 12        | 0.47%   |
| Qualcomm Atheros Communications   | 11        | 0.43%   |
| Microchip Technology              | 9         | 0.36%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.32%   |
| NetGear                           | 8         | 0.32%   |
| Aquantia                          | 8         | 0.32%   |
| Xiaomi                            | 7         | 0.28%   |
| Samsung Electronics               | 7         | 0.28%   |
| D-Link                            | 7         | 0.28%   |
| ASUSTek Computer                  | 7         | 0.28%   |
| Ericsson Business Mobile Networks | 6         | 0.24%   |
| Attansic Technology               | 6         | 0.24%   |
| JMicron Technology                | 5         | 0.2%    |
| Hewlett-Packard                   | 5         | 0.2%    |
| DisplayLink                       | 5         | 0.2%    |
| Dell                              | 5         | 0.2%    |
| VIA Technologies                  | 4         | 0.16%   |
| Lenovo                            | 4         | 0.16%   |
| Huawei Technologies               | 4         | 0.16%   |
| Edimax Technology                 | 4         | 0.16%   |
| D-Link System                     | 4         | 0.16%   |
| Linksys                           | 3         | 0.12%   |
| ZyDAS                             | 2         | 0.08%   |
| STMicroelectronics                | 2         | 0.08%   |
| QLogic                            | 2         | 0.08%   |
| Microsoft                         | 2         | 0.08%   |
| Fibocom                           | 2         | 0.08%   |
| Belkin Components                 | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 599       | 19.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 116       | 3.87%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 79        | 2.64%   |
| Intel Wi-Fi 6 AX200                                                    | 50        | 1.67%   |
| Intel Wireless 7265                                                    | 43        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 41        | 1.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 40        | 1.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 40        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 37        | 1.23%   |
| Realtek RTL8125 2.5GbE Controller                                      | 35        | 1.17%   |
| Intel Wireless 7260                                                    | 35        | 1.17%   |
| Intel Ethernet Connection I217-LM                                      | 35        | 1.17%   |
| Intel Wireless 8265 / 8275                                             | 34        | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 33        | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 32        | 1.07%   |
| Intel Wi-Fi 6 AX201                                                    | 31        | 1.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 31        | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 27        | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 27        | 0.9%    |
| Intel Ethernet Controller I225-V                                       | 26        | 0.87%   |
| Intel Wireless 3165                                                    | 25        | 0.83%   |
| Intel I211 Gigabit Network Connection                                  | 25        | 0.83%   |
| Intel Wireless 8260                                                    | 24        | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 23        | 0.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 23        | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 20        | 0.67%   |
| Realtek 802.11ac NIC                                                   | 20        | 0.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 19        | 0.63%   |
| Intel Ethernet Connection (2) I219-V                                   | 19        | 0.63%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 18        | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 0.53%   |
| Nvidia MCP61 Ethernet                                                  | 16        | 0.53%   |
| Intel 82574L Gigabit Network Connection                                | 16        | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                          | 16        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 15        | 0.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 15        | 0.5%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 14        | 0.47%   |
| Intel 82579V Gigabit Network Connection                                | 14        | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 13        | 0.43%   |
| Ralink MT7601U Wireless Adapter                                        | 13        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 563       | 43.11%  |
| Realtek Semiconductor           | 237       | 18.15%  |
| Qualcomm Atheros                | 210       | 16.08%  |
| Broadcom                        | 86        | 6.58%   |
| Ralink Technology               | 32        | 2.45%   |
| TP-Link                         | 29        | 2.22%   |
| Ralink                          | 28        | 2.14%   |
| Broadcom Limited                | 28        | 2.14%   |
| MediaTek                        | 19        | 1.45%   |
| Sierra Wireless                 | 12        | 0.92%   |
| Qualcomm Atheros Communications | 11        | 0.84%   |
| NetGear                         | 8         | 0.61%   |
| ASUSTek Computer                | 7         | 0.54%   |
| D-Link                          | 5         | 0.38%   |
| Edimax Technology               | 4         | 0.31%   |
| Dell                            | 4         | 0.31%   |
| Linksys                         | 3         | 0.23%   |
| ZyDAS                           | 2         | 0.15%   |
| Microsoft                       | 2         | 0.15%   |
| Fibocom                         | 2         | 0.15%   |
| Belkin Components               | 2         | 0.15%   |
| Xiaomi                          | 1         | 0.08%   |
| U.S. Robotics                   | 1         | 0.08%   |
| Tenda                           | 1         | 0.08%   |
| Sitecom Europe                  | 1         | 0.08%   |
| Realtek                         | 1         | 0.08%   |
| Qualcomm Technologies           | 1         | 0.08%   |
| Qualcomm                        | 1         | 0.08%   |
| IMC Networks                    | 1         | 0.08%   |
| Hewlett-Packard                 | 1         | 0.08%   |
| Gemtek                          | 1         | 0.08%   |
| D-Link System                   | 1         | 0.08%   |
| AVM                             | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 50        | 3.81%   |
| Intel Wireless 7265                                                     | 43        | 3.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 41        | 3.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 3.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 37        | 2.82%   |
| Intel Wireless 7260                                                     | 35        | 2.67%   |
| Intel Wireless 8265 / 8275                                              | 34        | 2.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 32        | 2.44%   |
| Intel Wi-Fi 6 AX201                                                     | 31        | 2.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 31        | 2.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 27        | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 27        | 2.06%   |
| Intel Wireless 3165                                                     | 25        | 1.91%   |
| Intel Wireless 8260                                                     | 24        | 1.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 23        | 1.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 23        | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.52%   |
| Realtek 802.11ac NIC                                                    | 20        | 1.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 1.45%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 18        | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 15        | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 14        | 1.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 13        | 0.99%   |
| Ralink MT7601U Wireless Adapter                                         | 13        | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 0.99%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 13        | 0.99%   |
| Intel Centrino Advanced-N 6235                                          | 13        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 0.99%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.91%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 12        | 0.91%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 12        | 0.91%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 11        | 0.84%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.84%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.76%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 10        | 0.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 0.76%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 9         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 798       | 50.16%  |
| Intel                            | 443       | 27.84%  |
| Broadcom                         | 90        | 5.66%   |
| Qualcomm Atheros                 | 81        | 5.09%   |
| Marvell Technology Group         | 30        | 1.89%   |
| Nvidia                           | 26        | 1.63%   |
| Broadcom Limited                 | 21        | 1.32%   |
| ASIX Electronics                 | 18        | 1.13%   |
| Microchip Technology             | 9         | 0.57%   |
| Aquantia                         | 8         | 0.5%    |
| Silicon Integrated Systems [SiS] | 7         | 0.44%   |
| Xiaomi                           | 6         | 0.38%   |
| Attansic Technology              | 6         | 0.38%   |
| Samsung Electronics              | 5         | 0.31%   |
| MediaTek                         | 5         | 0.31%   |
| JMicron Technology               | 5         | 0.31%   |
| DisplayLink                      | 5         | 0.31%   |
| VIA Technologies                 | 4         | 0.25%   |
| Lenovo                           | 4         | 0.25%   |
| Huawei Technologies              | 3         | 0.19%   |
| D-Link System                    | 3         | 0.19%   |
| QLogic                           | 2         | 0.13%   |
| D-Link                           | 2         | 0.13%   |
| Apple                            | 2         | 0.13%   |
| TP-Link                          | 1         | 0.06%   |
| NetXen Incorporated              | 1         | 0.06%   |
| Netchip Technology               | 1         | 0.06%   |
| MYRICOM                          | 1         | 0.06%   |
| Motorola PCS                     | 1         | 0.06%   |
| Mellanox Technologies            | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Emulex                           | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 599       | 36.26%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 116       | 7.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 79        | 4.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 40        | 2.42%   |
| Realtek RTL8125 2.5GbE Controller                                      | 35        | 2.12%   |
| Intel Ethernet Connection I217-LM                                      | 35        | 2.12%   |
| Intel Ethernet Controller I225-V                                       | 26        | 1.57%   |
| Intel I211 Gigabit Network Connection                                  | 25        | 1.51%   |
| Intel Ethernet Connection (2) I219-V                                   | 19        | 1.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 0.97%   |
| Nvidia MCP61 Ethernet                                                  | 16        | 0.97%   |
| Intel 82574L Gigabit Network Connection                                | 16        | 0.97%   |
| ASIX AX88179 Gigabit Ethernet                                          | 16        | 0.97%   |
| Intel 82579V Gigabit Network Connection                                | 14        | 0.85%   |
| Intel Ethernet Connection (7) I219-V                                   | 13        | 0.79%   |
| Intel Ethernet Connection (2) I219-LM                                  | 13        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                               | 13        | 0.79%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 13        | 0.79%   |
| Intel Ethernet Connection I217-V                                       | 12        | 0.73%   |
| Intel Ethernet Connection (3) I218-LM                                  | 12        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 12        | 0.73%   |
| Intel Ethernet Connection I219-LM                                      | 11        | 0.67%   |
| Intel Ethernet Connection I218-LM                                      | 11        | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 10        | 0.61%   |
| Intel I210 Gigabit Network Connection                                  | 9         | 0.54%   |
| Intel Ethernet Connection (6) I219-V                                   | 9         | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 8         | 0.48%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                          | 8         | 0.48%   |
| Intel Ethernet Connection I219-V                                       | 8         | 0.48%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 8         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 7         | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 7         | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                                  | 7         | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                                  | 7         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                                  | 7         | 0.42%   |
| Intel Ethernet Connection (4) I219-V                                   | 7         | 0.42%   |
| Intel Ethernet Connection (4) I219-LM                                  | 7         | 0.42%   |
| Intel 82567LM Gigabit Network Connection                               | 7         | 0.42%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 7         | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 6         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1504      | 54.53%  |
| WiFi     | 1223      | 44.34%  |
| Modem    | 29        | 1.05%   |
| Unknown  | 2         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 945       | 53.24%  |
| Ethernet | 830       | 46.76%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 917       | 52.73%  |
| 1     | 690       | 39.68%  |
| 0     | 82        | 4.72%   |
| 3     | 29        | 1.67%   |
| 4     | 12        | 0.69%   |
| 6     | 6         | 0.35%   |
| 5     | 2         | 0.12%   |
| 14    | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 1410      | 80.43%  |
| Yes     | 342       | 19.51%  |
| Unknown | 1         | 0.06%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 455       | 48.25%  |
| Realtek Semiconductor           | 97        | 10.29%  |
| Broadcom                        | 69        | 7.32%   |
| Qualcomm Atheros Communications | 66        | 7%      |
| Cambridge Silicon Radio         | 56        | 5.94%   |
| IMC Networks                    | 32        | 3.39%   |
| Lite-On Technology              | 24        | 2.55%   |
| Foxconn / Hon Hai               | 24        | 2.55%   |
| Dell                            | 22        | 2.33%   |
| Apple                           | 22        | 2.33%   |
| Hewlett-Packard                 | 14        | 1.48%   |
| ASUSTek Computer                | 14        | 1.48%   |
| Ralink                          | 10        | 1.06%   |
| MediaTek                        | 10        | 1.06%   |
| Toshiba                         | 8         | 0.85%   |
| Integrated System Solution      | 3         | 0.32%   |
| Foxconn International           | 3         | 0.32%   |
| Belkin Components               | 3         | 0.32%   |
| TP-Link                         | 2         | 0.21%   |
| Ralink Technology               | 2         | 0.21%   |
| Alps Electric                   | 2         | 0.21%   |
| TRENDnet                        | 1         | 0.11%   |
| Smart Modular Technologies      | 1         | 0.11%   |
| Qcom                            | 1         | 0.11%   |
| Conwise Technology              | 1         | 0.11%   |
| Chicony Electronics             | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 166       | 17.6%   |
| Intel AX201 Bluetooth                               | 88        | 9.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 75        | 7.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 56        | 5.94%   |
| Realtek Bluetooth Radio                             | 53        | 5.62%   |
| Intel AX200 Bluetooth                               | 49        | 5.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 25        | 2.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 22        | 2.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 18        | 1.91%   |
| Intel AX210 Bluetooth                               | 18        | 1.91%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 1.7%    |
| Intel Wireless-AC 3168 Bluetooth                    | 15        | 1.59%   |
| Dell DW375 Bluetooth Module                         | 14        | 1.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 13        | 1.38%   |
| IMC Networks Bluetooth Device                       | 13        | 1.38%   |
| Ralink RT3290 Bluetooth                             | 10        | 1.06%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 1.06%   |
| Intel AX211 Bluetooth                               | 10        | 1.06%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 10        | 1.06%   |
| MediaTek Wireless_Device                            | 9         | 0.95%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 9         | 0.95%   |
| Realtek 802.11ac WLAN Adapter                       | 8         | 0.85%   |
| IMC Networks Bluetooth Radio                        | 8         | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 0.85%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 0.85%   |
| Realtek RTL8723B Bluetooth                          | 7         | 0.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.74%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.74%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 7         | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 0.74%   |
| Apple Bluetooth Host Controller                     | 7         | 0.74%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.64%   |
| Lite-On Bluetooth Device                            | 6         | 0.64%   |
| IMC Networks Wireless_Device                        | 6         | 0.64%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.64%   |
| Broadcom HP Portable SoftSailing                    | 6         | 0.64%   |
| Apple Bluetooth HCI                                 | 6         | 0.64%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 5         | 0.53%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.53%   |
| Apple Bluetooth USB Host Controller                 | 5         | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1234      | 54.15%  |
| AMD                                          | 436       | 19.13%  |
| Nvidia                                       | 382       | 16.76%  |
| C-Media Electronics                          | 42        | 1.84%   |
| Logitech                                     | 16        | 0.7%    |
| Creative Labs                                | 12        | 0.53%   |
| Realtek Semiconductor                        | 11        | 0.48%   |
| Silicon Integrated Systems [SiS]             | 9         | 0.39%   |
| GN Netcom                                    | 9         | 0.39%   |
| ASUSTek Computer                             | 9         | 0.39%   |
| JMTek                                        | 8         | 0.35%   |
| Generalplus Technology                       | 8         | 0.35%   |
| Kingston Technology                          | 6         | 0.26%   |
| Corsair                                      | 6         | 0.26%   |
| VIA Technologies                             | 5         | 0.22%   |
| Plantronics                                  | 5         | 0.22%   |
| Hewlett-Packard                              | 5         | 0.22%   |
| Focusrite-Novation                           | 5         | 0.22%   |
| Lenovo                                       | 4         | 0.18%   |
| Texas Instruments                            | 3         | 0.13%   |
| Tenx Technology                              | 3         | 0.13%   |
| Razer USA                                    | 3         | 0.13%   |
| Ensoniq                                      | 3         | 0.13%   |
| Creative Technology                          | 3         | 0.13%   |
| Cambridge Silicon Radio                      | 3         | 0.13%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.09%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.09%   |
| Sony                                         | 2         | 0.09%   |
| Micro Star International                     | 2         | 0.09%   |
| Meizu                                        | 2         | 0.09%   |
| Jieli Technology                             | 2         | 0.09%   |
| FiiO Electronics Technology                  | 2         | 0.09%   |
| DSEA A/S                                     | 2         | 0.09%   |
| Dell                                         | 2         | 0.09%   |
| D&M Holdings (Denon/Marantz)                 | 2         | 0.09%   |
| Conexant Systems                             | 2         | 0.09%   |
| BEHRINGER International                      | 2         | 0.09%   |
| Alesis                                       | 2         | 0.09%   |
| XMOS                                         | 1         | 0.04%   |
| Walmart                                      | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 126       | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 126       | 4.69%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 122       | 4.54%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 94        | 3.5%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 86        | 3.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 86        | 3.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 78        | 2.9%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 76        | 2.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 60        | 2.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 56        | 2.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 50        | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 47        | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 46        | 1.71%   |
| AMD FCH Azalia Controller                                                                         | 45        | 1.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 39        | 1.45%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 38        | 1.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 37        | 1.38%   |
| Intel 8 Series HD Audio Controller                                                                | 37        | 1.38%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 37        | 1.38%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 36        | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 34        | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 33        | 1.23%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 30        | 1.12%   |
| Intel Broadwell-U Audio Controller                                                                | 30        | 1.12%   |
| Nvidia High Definition Audio Controller                                                           | 29        | 1.08%   |
| Intel 200 Series PCH HD Audio                                                                     | 29        | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 28        | 1.04%   |
| AMD Kabini HDMI/DP Audio                                                                          | 28        | 1.04%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 27        | 1.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 26        | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 25        | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 25        | 0.93%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 24        | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 23        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 23        | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 22        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 22        | 0.82%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 21        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                                         | 20        | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 20        | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 255       | 19.75%  |
| SK hynix                                         | 209       | 16.19%  |
| Kingston                                         | 164       | 12.7%   |
| Unknown                                          | 145       | 11.23%  |
| Micron Technology                                | 115       | 8.91%   |
| Crucial                                          | 91        | 7.05%   |
| Corsair                                          | 69        | 5.34%   |
| G.Skill                                          | 43        | 3.33%   |
| Ramaxel Technology                               | 28        | 2.17%   |
| Nanya Technology                                 | 23        | 1.78%   |
| Unknown (ABCD)                                   | 20        | 1.55%   |
| Elpida                                           | 20        | 1.55%   |
| A-DATA Technology                                | 19        | 1.47%   |
| Smart                                            | 12        | 0.93%   |
| Team                                             | 11        | 0.85%   |
| Unknown                                          | 11        | 0.85%   |
| Patriot                                          | 6         | 0.46%   |
| Teikon                                           | 5         | 0.39%   |
| GOODRAM                                          | 4         | 0.31%   |
| Transcend                                        | 3         | 0.23%   |
| Qimonda                                          | 3         | 0.23%   |
| HBS                                              | 3         | 0.23%   |
| Silicon Power                                    | 2         | 0.15%   |
| Netlist                                          | 2         | 0.15%   |
| Neo Forza                                        | 2         | 0.15%   |
| Hewlett-Packard                                  | 2         | 0.15%   |
| Atermiter                                        | 2         | 0.15%   |
| Unknown (9B0D)                                   | 1         | 0.08%   |
| Unknown (940A)                                   | 1         | 0.08%   |
| Unknown (0x7FFF)                                 | 1         | 0.08%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.08%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.08%   |
| Unknown (0x0E9D)                                 | 1         | 0.08%   |
| Unknown (0x0C26)                                 | 1         | 0.08%   |
| Unknown (0x0B6B)                                 | 1         | 0.08%   |
| Unknown (00FFFFFFFFFFFFFF)                       | 1         | 0.08%   |
| Unifosa                                          | 1         | 0.08%   |
| Toshiba                                          | 1         | 0.08%   |
| Timetec                                          | 1         | 0.08%   |
| Smart Brazil                                     | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 1.02%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 13        | 0.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 12        | 0.87%   |
| Unknown                                                          | 11        | 0.8%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.65%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 8         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.58%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.58%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 7         | 0.51%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.51%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 6         | 0.44%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.44%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.44%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.44%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.44%   |
| Kingston RAM Module 4096MB DIMM DDR3 1333MT/s                    | 6         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.36%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.36%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.36%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.36%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 5         | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.36%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 4         | 0.29%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.29%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s                       | 4         | 0.29%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 4         | 0.29%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 4         | 0.29%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.29%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 4         | 0.29%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 4199MT/s                 | 4         | 0.29%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.29%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.29%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 446       | 39.72%  |
| DDR3    | 414       | 36.87%  |
| DDR2    | 74        | 6.59%   |
| SDRAM   | 43        | 3.83%   |
| LPDDR4  | 40        | 3.56%   |
| Unknown | 33        | 2.94%   |
| DDR5    | 25        | 2.23%   |
| LPDDR3  | 24        | 2.14%   |
| DDR     | 17        | 1.51%   |
| LPDDR5  | 4         | 0.36%   |
| DRAM    | 3         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 620       | 55.71%  |
| DIMM         | 422       | 37.92%  |
| Row Of Chips | 58        | 5.21%   |
| Chip         | 6         | 0.54%   |
| Unknown      | 6         | 0.54%   |
| RIMM         | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 397       | 32.38%  |
| 4096   | 345       | 28.14%  |
| 16384  | 197       | 16.07%  |
| 2048   | 187       | 15.25%  |
| 32768  | 50        | 4.08%   |
| 1024   | 41        | 3.34%   |
| 512    | 4         | 0.33%   |
| 131072 | 1         | 0.08%   |
| 12288  | 1         | 0.08%   |
| 1536   | 1         | 0.08%   |
| 256    | 1         | 0.08%   |
| 32     | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 261       | 21.53%  |
| 3200    | 160       | 13.2%   |
| 2667    | 139       | 11.47%  |
| 1333    | 100       | 8.25%   |
| 2400    | 90        | 7.43%   |
| 2133    | 47        | 3.88%   |
| 1334    | 41        | 3.38%   |
| 800     | 36        | 2.97%   |
| 667     | 36        | 2.97%   |
| Unknown | 32        | 2.64%   |
| 3600    | 24        | 1.98%   |
| 1066    | 19        | 1.57%   |
| 3266    | 15        | 1.24%   |
| 1867    | 15        | 1.24%   |
| 1067    | 14        | 1.16%   |
| 4199    | 12        | 0.99%   |
| 4800    | 11        | 0.91%   |
| 2048    | 10        | 0.83%   |
| 533     | 10        | 0.83%   |
| 4267    | 9         | 0.74%   |
| 6400    | 8         | 0.66%   |
| 3800    | 8         | 0.66%   |
| 3733    | 8         | 0.66%   |
| 2933    | 8         | 0.66%   |
| 1866    | 7         | 0.58%   |
| 3466    | 6         | 0.5%    |
| 3000    | 6         | 0.5%    |
| 1800    | 6         | 0.5%    |
| 5600    | 5         | 0.41%   |
| 2666    | 5         | 0.41%   |
| 975     | 5         | 0.41%   |
| 4000    | 4         | 0.33%   |
| 3400    | 4         | 0.33%   |
| 2800    | 4         | 0.33%   |
| 49926   | 3         | 0.25%   |
| 400     | 3         | 0.25%   |
| 333     | 3         | 0.25%   |
| 266     | 3         | 0.25%   |
| 8400    | 2         | 0.17%   |
| 4266    | 2         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 17        | 27.87%  |
| Brother Industries     | 10        | 16.39%  |
| Seiko Epson            | 7         | 11.48%  |
| Samsung Electronics    | 7         | 11.48%  |
| Canon                  | 7         | 11.48%  |
| Dymo-CoStar            | 4         | 6.56%   |
| QinHeng Electronics    | 2         | 3.28%   |
| Xerox                  | 1         | 1.64%   |
| STMicroelectronics     | 1         | 1.64%   |
| Prolific Technology    | 1         | 1.64%   |
| Panasonic (Matsushita) | 1         | 1.64%   |
| Lexmark International  | 1         | 1.64%   |
| Graphtec America       | 1         | 1.64%   |
| BIXOLON                | 1         | 1.64%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Seiko Epson Printer                                       | 3         | 4.84%   |
| Brother Printer                                           | 3         | 4.84%   |
| Samsung SCX-4200 series                                   | 2         | 3.23%   |
| Samsung M2020 Series                                      | 2         | 3.23%   |
| QinHeng CH340S                                            | 2         | 3.23%   |
| HP LaserJet Professional P1102w                           | 2         | 3.23%   |
| HP LaserJet Professional P 1102w                          | 2         | 3.23%   |
| HP Deskjet F4500 series                                   | 2         | 3.23%   |
| HP DeskJet 2700 series                                    | 2         | 3.23%   |
| Dymo-CoStar LabelWriter 450                               | 2         | 3.23%   |
| Xerox Phaser 3020                                         | 1         | 1.61%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.61%   |
| Seiko Epson XP-4100 Series                                | 1         | 1.61%   |
| Seiko Epson WF-2010 Series                                | 1         | 1.61%   |
| Seiko Epson L382 Series                                   | 1         | 1.61%   |
| Seiko Epson L312 Series                                   | 1         | 1.61%   |
| Samsung M2070 Series                                      | 1         | 1.61%   |
| Samsung CLX-8380 Series                                   | 1         | 1.61%   |
| Samsung CLX-4190 Series                                   | 1         | 1.61%   |
| Prolific PL2305 Parallel Port                             | 1         | 1.61%   |
| Panasonic (Matsushita) KX-MB2130RU                        | 1         | 1.61%   |
| Lexmark International InkJet Color Printer                | 1         | 1.61%   |
| HP Officejet 4500 G510a-f                                 | 1         | 1.61%   |
| HP LaserJet 1022                                          | 1         | 1.61%   |
| HP LaserJet 1020                                          | 1         | 1.61%   |
| HP DeskJet F300 series                                    | 1         | 1.61%   |
| HP DeskJet 845c                                           | 1         | 1.61%   |
| HP Deskjet 3050 J610 series                               | 1         | 1.61%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 1.61%   |
| HP DeskJet 2130 series                                    | 1         | 1.61%   |
| HP color LaserJet 4650                                    | 1         | 1.61%   |
| Graphtec America Graphtec Printer                         | 1         | 1.61%   |
| Dymo-CoStar LabelWriter 310                               | 1         | 1.61%   |
| Dymo-CoStar DYMO LabelWriter 320                          | 1         | 1.61%   |
| Canon PIXMA MG2500 Series                                 | 1         | 1.61%   |
| Canon Pixma iP4500 Printer                                | 1         | 1.61%   |
| Canon MF3010                                              | 1         | 1.61%   |
| Canon MF230 Series UFRII LT                               | 1         | 1.61%   |
| Canon LiDE 400                                            | 1         | 1.61%   |
| Canon LBP7010C/7018C                                      | 1         | 1.61%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 8         | 47.06%  |
| Seiko Epson                                    | 5         | 29.41%  |
| Hewlett-Packard                                | 2         | 11.76%  |
| Siemens Information and Communication Products | 1         | 5.88%   |
| Acer Peripherals (now BenQ)                    | 1         | 5.88%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                           | Computers | Percent |
|---------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                         | 3         | 17.65%  |
| Siemens Information and Communication Products ID-Mouse with Fingerprint Reader | 1         | 5.88%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]                                | 1         | 5.88%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                               | 1         | 5.88%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                              | 1         | 5.88%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                            | 1         | 5.88%   |
| Seiko Epson ES-D400 [GT-S80]                                                    | 1         | 5.88%   |
| HP ScanJet G4010                                                                | 1         | 5.88%   |
| HP ScanJet 4370                                                                 | 1         | 5.88%   |
| Canon CanoScan N1240U/LiDE 30                                                   | 1         | 5.88%   |
| Canon CanoScan LiDE 90                                                          | 1         | 5.88%   |
| Canon CanoScan LIDE 25                                                          | 1         | 5.88%   |
| Canon CanoScan LiDE 210                                                         | 1         | 5.88%   |
| Canon CanoScan LiDE 120                                                         | 1         | 5.88%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                     | 1         | 5.88%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 229       | 24.08%  |
| Microdia                               | 79        | 8.31%   |
| Bison Electronics                      | 69        | 7.26%   |
| IMC Networks                           | 61        | 6.41%   |
| Realtek Semiconductor                  | 58        | 6.1%    |
| Logitech                               | 55        | 5.78%   |
| Sunplus Innovation Technology          | 47        | 4.94%   |
| Cheng Uei Precision Industry (Foxlink) | 45        | 4.73%   |
| Quanta                                 | 36        | 3.79%   |
| Suyin                                  | 29        | 3.05%   |
| Apple                                  | 26        | 2.73%   |
| Syntek                                 | 25        | 2.63%   |
| Ricoh                                  | 18        | 1.89%   |
| Lite-On Technology                     | 17        | 1.79%   |
| Luxvisions Innotech Limited            | 14        | 1.47%   |
| Silicon Motion                         | 13        | 1.37%   |
| Acer                                   | 13        | 1.37%   |
| Alcor Micro                            | 10        | 1.05%   |
| Samsung Electronics                    | 9         | 0.95%   |
| Z-Star Microelectronics                | 7         | 0.74%   |
| Lenovo                                 | 6         | 0.63%   |
| Importek                               | 6         | 0.63%   |
| Generalplus Technology                 | 5         | 0.53%   |
| ARC International                      | 5         | 0.53%   |
| Microsoft                              | 4         | 0.42%   |
| KYE Systems (Mouse Systems)            | 4         | 0.42%   |
| SunplusIT                              | 3         | 0.32%   |
| Sonix Technology                       | 3         | 0.32%   |
| Razer USA                              | 3         | 0.32%   |
| Primax Electronics                     | 3         | 0.32%   |
| DigiTech                               | 3         | 0.32%   |
| Creative Technology                    | 3         | 0.32%   |
| ALi                                    | 3         | 0.32%   |
| Y Media                                | 2         | 0.21%   |
| Unknown                                | 2         | 0.21%   |
| Sunplus Technology                     | 2         | 0.21%   |
| Ruision                                | 2         | 0.21%   |
| LG Electronics                         | 2         | 0.21%   |
| Intel                                  | 2         | 0.21%   |
| icSpring                               | 2         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 38        | 3.97%   |
| Bison Integrated Camera                                 | 22        | 2.3%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 20        | 2.09%   |
| Realtek Integrated_Webcam_HD                            | 19        | 1.99%   |
| Microdia Integrated_Webcam_HD                           | 18        | 1.88%   |
| Syntek Integrated Camera                                | 15        | 1.57%   |
| IMC Networks Integrated Camera                          | 15        | 1.57%   |
| Chicony HP HD Camera                                    | 15        | 1.57%   |
| Sunplus Integrated_Webcam_HD                            | 14        | 1.46%   |
| Logitech Webcam C270                                    | 13        | 1.36%   |
| Chicony HD WebCam                                       | 13        | 1.36%   |
| Logitech HD Pro Webcam C920                             | 12        | 1.26%   |
| Chicony USB2.0 Camera                                   | 11        | 1.15%   |
| Microdia Integrated Webcam                              | 10        | 1.05%   |
| Chicony USB2.0 VGA UVC WebCam                           | 10        | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                      | 10        | 1.05%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 9         | 0.94%   |
| Microdia Webcam Vitade AF                               | 8         | 0.84%   |
| Lite-On Integrated Camera                               | 8         | 0.84%   |
| Chicony USB 2.0 Camera                                  | 8         | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 8         | 0.84%   |
| Bison Lenovo Integrated Webcam                          | 8         | 0.84%   |
| Quanta HD User Facing                                   | 7         | 0.73%   |
| Chicony VGA Webcam                                      | 7         | 0.73%   |
| Chicony HP Wide Vision HD Camera                        | 7         | 0.73%   |
| Bison Lenovo EasyCamera                                 | 7         | 0.73%   |
| Ricoh HD Webcam                                         | 6         | 0.63%   |
| Realtek USB Camera                                      | 6         | 0.63%   |
| Microdia USB 2.0 Camera                                 | 6         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 6         | 0.63%   |
| Chicony TOSHIBA Web Camera - HD                         | 6         | 0.63%   |
| Chicony HP Webcam                                       | 6         | 0.63%   |
| Chicony HP HD Webcam                                    | 6         | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 6         | 0.63%   |
| Apple FaceTime HD Camera (Built-in)                     | 6         | 0.63%   |
| Suyin HP TrueVision HD Integrated Webcam                | 5         | 0.52%   |
| Chicony WebCam                                          | 5         | 0.52%   |
| Chicony Integrated IR Camera                            | 5         | 0.52%   |
| Chicony Integrated Camera (1280x720@30)                 | 5         | 0.52%   |
| Chicony HP TrueVision HD Camera                         | 5         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 69        | 42.59%  |
| Synaptics                  | 36        | 22.22%  |
| Shenzhen Goodix Technology | 19        | 11.73%  |
| Upek                       | 12        | 7.41%   |
| Elan Microelectronics      | 10        | 6.17%   |
| AuthenTec                  | 7         | 4.32%   |
| LighTuning Technology      | 4         | 2.47%   |
| STMicroelectronics         | 3         | 1.85%   |
| Samsung Electronics        | 1         | 0.62%   |
| Focal-systems.Corp         | 1         | 0.62%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 8.02%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 6.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 5.56%   |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 4.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 3.7%    |
| Elan ELAN:ARM-M4                                                           | 6         | 3.7%    |
| Validity Sensors VFS491                                                    | 5         | 3.09%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.09%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 3.09%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 3.09%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 3.09%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 2.47%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.85%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.85%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.85%   |
| Upek TCS5B Fingerprint sensor                                              | 3         | 1.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 1.85%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 1.85%   |
| AuthenTec AES1600                                                          | 3         | 1.85%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.23%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 1.23%   |
| Synaptics WBDI                                                             | 2         | 1.23%   |
| Synaptics UWP WBDI                                                         | 2         | 1.23%   |
| Synaptics  WBDI                                                            | 2         | 1.23%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.23%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.23%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.62%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.62%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.62%   |
| Synaptics WBDI Device                                                      | 1         | 0.62%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.62%   |
| Samsung Fingerprint Device                                                 | 1         | 0.62%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 56        | 52.34%  |
| Alcor Micro           | 26        | 24.3%   |
| O2 Micro              | 6         | 5.61%   |
| Upek                  | 4         | 3.74%   |
| SCM Microsystems      | 3         | 2.8%    |
| Lenovo                | 3         | 2.8%    |
| Advanced Card Systems | 3         | 2.8%    |
| Gemalto (was Gemplus) | 2         | 1.87%   |
| Realtek Semiconductor | 1         | 0.93%   |
| OmniKey               | 1         | 0.93%   |
| Kobil Systems         | 1         | 0.93%   |
| Chicony Electronics   | 1         | 0.93%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 24.3%   |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 18.69%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 14.02%  |
| Broadcom 58200                                                               | 14        | 13.08%  |
| Broadcom 5880                                                                | 7         | 6.54%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 6         | 5.61%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.74%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.8%    |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 1.87%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 1.87%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 0.93%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.93%   |
| SCM Microsystems Identiv SmartOS Reader                                      | 1         | 0.93%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.93%   |
| OmniKey CardMan 1021                                                         | 1         | 0.93%   |
| Kobil Systems Smart Token                                                    | 1         | 0.93%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.93%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.93%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1258      | 71.76%  |
| 1     | 396       | 22.59%  |
| 2     | 79        | 4.51%   |
| 3     | 13        | 0.74%   |
| 4     | 4         | 0.23%   |
| 8     | 2         | 0.11%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 163       | 26.85%  |
| Graphics card            | 155       | 25.54%  |
| Chipcard                 | 97        | 15.98%  |
| Net/wireless             | 51        | 8.4%    |
| Communication controller | 21        | 3.46%   |
| Camera                   | 19        | 3.13%   |
| Bluetooth                | 19        | 3.13%   |
| Multimedia controller    | 15        | 2.47%   |
| Unassigned class         | 12        | 1.98%   |
| Storage                  | 11        | 1.81%   |
| Sound                    | 10        | 1.65%   |
| Modem                    | 7         | 1.15%   |
| Network                  | 6         | 0.99%   |
| Card reader              | 6         | 0.99%   |
| Flash memory             | 5         | 0.82%   |
| Net/ethernet             | 4         | 0.66%   |
| Firewire controller      | 3         | 0.49%   |
| Tv card                  | 1         | 0.16%   |
| Storage/ata              | 1         | 0.16%   |
| Dvb card                 | 1         | 0.16%   |

