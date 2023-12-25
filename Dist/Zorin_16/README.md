Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 5920

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E6430              | Notebook    | [d949738171](https://linux-hardware.org/?probe=d949738171) | Dec 24, 2023 |
| Dell          | Latitude E6430              | Notebook    | [c821d379ec](https://linux-hardware.org/?probe=c821d379ec) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [a69b3fa1ca](https://linux-hardware.org/?probe=a69b3fa1ca) | Dec 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [9ac48a1719](https://linux-hardware.org/?probe=9ac48a1719) | Dec 24, 2023 |
| HP            | Notebook                    | Notebook    | [69bef099c0](https://linux-hardware.org/?probe=69bef099c0) | Dec 24, 2023 |
| ASUSTek       | M2V                         | Desktop     | [67c7bc43ed](https://linux-hardware.org/?probe=67c7bc43ed) | Dec 23, 2023 |
| ASUSTek       | M2V                         | Desktop     | [1d6970f290](https://linux-hardware.org/?probe=1d6970f290) | Dec 23, 2023 |
| HP            | 1998                        | Desktop     | [8eb25518c4](https://linux-hardware.org/?probe=8eb25518c4) | Dec 23, 2023 |
| HP            | Victus by 15.6 inch Gami... | Notebook    | [b74170ede4](https://linux-hardware.org/?probe=b74170ede4) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [b4d280ac6a](https://linux-hardware.org/?probe=b4d280ac6a) | Dec 23, 2023 |
| Toshiba       | Satellite Pro R50-C         | Notebook    | [421d62894b](https://linux-hardware.org/?probe=421d62894b) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [9c0210d1ed](https://linux-hardware.org/?probe=9c0210d1ed) | Dec 22, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [49cdf35ca4](https://linux-hardware.org/?probe=49cdf35ca4) | Dec 22, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [084e48827c](https://linux-hardware.org/?probe=084e48827c) | Dec 21, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [83183dbb01](https://linux-hardware.org/?probe=83183dbb01) | Dec 21, 2023 |
| Lenovo        | ThinkPad X131e 33691K7      | Notebook    | [360dc0f244](https://linux-hardware.org/?probe=360dc0f244) | Dec 21, 2023 |
| Dell          | Latitude E7270              | Notebook    | [4574a46c78](https://linux-hardware.org/?probe=4574a46c78) | Dec 21, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [f9d9539e00](https://linux-hardware.org/?probe=f9d9539e00) | Dec 21, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [ee5e05ce6d](https://linux-hardware.org/?probe=ee5e05ce6d) | Dec 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6311def15e](https://linux-hardware.org/?probe=6311def15e) | Dec 21, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [8b094a74c9](https://linux-hardware.org/?probe=8b094a74c9) | Dec 21, 2023 |
| HP            | 1000                        | Notebook    | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5266cee35b](https://linux-hardware.org/?probe=5266cee35b) | Dec 21, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c0c637bbba](https://linux-hardware.org/?probe=c0c637bbba) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [50a3c349a0](https://linux-hardware.org/?probe=50a3c349a0) | Dec 21, 2023 |
| HP            | ProBook 430 G7              | Notebook    | [f79ed192ac](https://linux-hardware.org/?probe=f79ed192ac) | Dec 21, 2023 |
| Dell          | 0FM586                      | Desktop     | [eadcdb629b](https://linux-hardware.org/?probe=eadcdb629b) | Dec 20, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [caa584d966](https://linux-hardware.org/?probe=caa584d966) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [af51ef8978](https://linux-hardware.org/?probe=af51ef8978) | Dec 20, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [7cda066ff6](https://linux-hardware.org/?probe=7cda066ff6) | Dec 20, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [6a601de5d5](https://linux-hardware.org/?probe=6a601de5d5) | Dec 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [f7cd6db92f](https://linux-hardware.org/?probe=f7cd6db92f) | Dec 20, 2023 |
| HP            | 1998                        | Desktop     | [bc41363911](https://linux-hardware.org/?probe=bc41363911) | Dec 20, 2023 |
| Framework     | Laptop                      | Notebook    | [2aab7ea892](https://linux-hardware.org/?probe=2aab7ea892) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bcae8d434f](https://linux-hardware.org/?probe=bcae8d434f) | Dec 19, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [95ab984d32](https://linux-hardware.org/?probe=95ab984d32) | Dec 19, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [582c2df7b1](https://linux-hardware.org/?probe=582c2df7b1) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [91b5e05490](https://linux-hardware.org/?probe=91b5e05490) | Dec 19, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [fde7aeea9c](https://linux-hardware.org/?probe=fde7aeea9c) | Dec 19, 2023 |
| Google        | Phaser360                   | Notebook    | [c739678794](https://linux-hardware.org/?probe=c739678794) | Dec 18, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [780a4cf454](https://linux-hardware.org/?probe=780a4cf454) | Dec 18, 2023 |
| Lenovo        | ThinkPad X240 20AMS0VU00    | Notebook    | [ecca798714](https://linux-hardware.org/?probe=ecca798714) | Dec 18, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [c2b96a9e0f](https://linux-hardware.org/?probe=c2b96a9e0f) | Dec 18, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [74cdfd92c0](https://linux-hardware.org/?probe=74cdfd92c0) | Dec 18, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [125dbde28d](https://linux-hardware.org/?probe=125dbde28d) | Dec 17, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [2b9510004d](https://linux-hardware.org/?probe=2b9510004d) | Dec 17, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [a411802ac6](https://linux-hardware.org/?probe=a411802ac6) | Dec 17, 2023 |
| Sony          | VGN-FW455J                  | Notebook    | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [7962dd075b](https://linux-hardware.org/?probe=7962dd075b) | Dec 17, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [304fbf1e83](https://linux-hardware.org/?probe=304fbf1e83) | Dec 17, 2023 |
| Lenovo        | Yoga 7 16IRL8 82YN          | Convertible | [4e3b49ab8e](https://linux-hardware.org/?probe=4e3b49ab8e) | Dec 17, 2023 |
| Irbis         | NB12                        | Notebook    | [f6eb11e455](https://linux-hardware.org/?probe=f6eb11e455) | Dec 17, 2023 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [ad9eaf3ae6](https://linux-hardware.org/?probe=ad9eaf3ae6) | Dec 16, 2023 |
| Google        | Phaser360                   | Notebook    | [784ed40440](https://linux-hardware.org/?probe=784ed40440) | Dec 16, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [56e1b0ed26](https://linux-hardware.org/?probe=56e1b0ed26) | Dec 16, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [30f8fe050c](https://linux-hardware.org/?probe=30f8fe050c) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [4973d42380](https://linux-hardware.org/?probe=4973d42380) | Dec 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [faf62fd1be](https://linux-hardware.org/?probe=faf62fd1be) | Dec 16, 2023 |
| HP            | Notebook                    | Notebook    | [a960b17c37](https://linux-hardware.org/?probe=a960b17c37) | Dec 16, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [1bd6eab773](https://linux-hardware.org/?probe=1bd6eab773) | Dec 15, 2023 |
| Dell          | 0FM586                      | Desktop     | [c895a8d51f](https://linux-hardware.org/?probe=c895a8d51f) | Dec 15, 2023 |
| Medion        | P7624                       | Notebook    | [4828985ec0](https://linux-hardware.org/?probe=4828985ec0) | Dec 15, 2023 |
| Medion        | P7624                       | Notebook    | [050fbbd613](https://linux-hardware.org/?probe=050fbbd613) | Dec 15, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [de4b8201ef](https://linux-hardware.org/?probe=de4b8201ef) | Dec 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [646c709529](https://linux-hardware.org/?probe=646c709529) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [b5fefd59fe](https://linux-hardware.org/?probe=b5fefd59fe) | Dec 15, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [7d20d738b1](https://linux-hardware.org/?probe=7d20d738b1) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [734375c1cc](https://linux-hardware.org/?probe=734375c1cc) | Dec 14, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | Notebook    | [5ae09c04d4](https://linux-hardware.org/?probe=5ae09c04d4) | Dec 14, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3eb792873c](https://linux-hardware.org/?probe=3eb792873c) | Dec 14, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [048f7ace00](https://linux-hardware.org/?probe=048f7ace00) | Dec 14, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [85f532c1c5](https://linux-hardware.org/?probe=85f532c1c5) | Dec 13, 2023 |
| Positivo      | POS-PIQ57BQ POSITIVO        | Desktop     | [1a2fe7c9ef](https://linux-hardware.org/?probe=1a2fe7c9ef) | Dec 13, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [f9933769ef](https://linux-hardware.org/?probe=f9933769ef) | Dec 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [27b99be924](https://linux-hardware.org/?probe=27b99be924) | Dec 12, 2023 |
| HP            | Notebook                    | Notebook    | [972e86b7cf](https://linux-hardware.org/?probe=972e86b7cf) | Dec 12, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [bdfc16eb98](https://linux-hardware.org/?probe=bdfc16eb98) | Dec 11, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [f779186ae7](https://linux-hardware.org/?probe=f779186ae7) | Dec 11, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [311c3a6954](https://linux-hardware.org/?probe=311c3a6954) | Dec 11, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | Notebook    | [a644fcc63e](https://linux-hardware.org/?probe=a644fcc63e) | Dec 11, 2023 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [332492b0c4](https://linux-hardware.org/?probe=332492b0c4) | Dec 11, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [d0ff744f50](https://linux-hardware.org/?probe=d0ff744f50) | Dec 10, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [e7dbed1e89](https://linux-hardware.org/?probe=e7dbed1e89) | Dec 10, 2023 |
| Dell          | 0FM586                      | Desktop     | [2bf8665376](https://linux-hardware.org/?probe=2bf8665376) | Dec 10, 2023 |
| MSI           | 2AE0                        | Desktop     | [29c5d75dcf](https://linux-hardware.org/?probe=29c5d75dcf) | Dec 10, 2023 |
| MSI           | 2AE0                        | Desktop     | [63543021ec](https://linux-hardware.org/?probe=63543021ec) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [5522722e53](https://linux-hardware.org/?probe=5522722e53) | Dec 10, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [52e1cb6958](https://linux-hardware.org/?probe=52e1cb6958) | Dec 10, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [949de6a6a9](https://linux-hardware.org/?probe=949de6a6a9) | Dec 10, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [3f4af9bbdd](https://linux-hardware.org/?probe=3f4af9bbdd) | Dec 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [514899b0b9](https://linux-hardware.org/?probe=514899b0b9) | Dec 10, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bc892e5d3b](https://linux-hardware.org/?probe=bc892e5d3b) | Dec 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| Acer          | AOD257                      | Notebook    | [79c121ca0e](https://linux-hardware.org/?probe=79c121ca0e) | Dec 09, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [d2abe7128b](https://linux-hardware.org/?probe=d2abe7128b) | Dec 09, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [955f530c70](https://linux-hardware.org/?probe=955f530c70) | Dec 08, 2023 |
| Acer          | AOD257                      | Notebook    | [c817dc5cca](https://linux-hardware.org/?probe=c817dc5cca) | Dec 08, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [045ab5efca](https://linux-hardware.org/?probe=045ab5efca) | Dec 08, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [88c39cda86](https://linux-hardware.org/?probe=88c39cda86) | Dec 08, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [fc2efc3edb](https://linux-hardware.org/?probe=fc2efc3edb) | Dec 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [767b4efa54](https://linux-hardware.org/?probe=767b4efa54) | Dec 06, 2023 |
| MSI           | MS-7309                     | Desktop     | [bfc6167f25](https://linux-hardware.org/?probe=bfc6167f25) | Dec 06, 2023 |
| MSI           | MS-7309                     | Desktop     | [556b1ebd9a](https://linux-hardware.org/?probe=556b1ebd9a) | Dec 06, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [bfd0ab0fc0](https://linux-hardware.org/?probe=bfd0ab0fc0) | Dec 06, 2023 |
| Dell          | Latitude 7490               | Notebook    | [364b5c38d4](https://linux-hardware.org/?probe=364b5c38d4) | Dec 06, 2023 |
| Gateway       | SX2851                      | Desktop     | [2ec497373d](https://linux-hardware.org/?probe=2ec497373d) | Dec 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1748ab2263](https://linux-hardware.org/?probe=1748ab2263) | Dec 05, 2023 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [3792e939db](https://linux-hardware.org/?probe=3792e939db) | Dec 05, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [549c56d2f8](https://linux-hardware.org/?probe=549c56d2f8) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [9714fadd61](https://linux-hardware.org/?probe=9714fadd61) | Dec 04, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [ee58e73f03](https://linux-hardware.org/?probe=ee58e73f03) | Dec 04, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [23937a8b80](https://linux-hardware.org/?probe=23937a8b80) | Dec 04, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0d13c9a0b6](https://linux-hardware.org/?probe=0d13c9a0b6) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcb521e9aa](https://linux-hardware.org/?probe=dcb521e9aa) | Dec 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [4800fa6c99](https://linux-hardware.org/?probe=4800fa6c99) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [6bc5e84b91](https://linux-hardware.org/?probe=6bc5e84b91) | Dec 04, 2023 |
| Dell          | 042P49 A00                  | Desktop     | [813edffc94](https://linux-hardware.org/?probe=813edffc94) | Dec 04, 2023 |
| HP            | 3031h                       | Desktop     | [06a9e0c346](https://linux-hardware.org/?probe=06a9e0c346) | Dec 04, 2023 |
| SONIQ Digi... | Soniq 11.6inch Convertib... | Convertible | [4e67d597e1](https://linux-hardware.org/?probe=4e67d597e1) | Dec 04, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [45d1723559](https://linux-hardware.org/?probe=45d1723559) | Dec 03, 2023 |
| Dell          | Latitude 6430U              | Notebook    | [1e4dda911f](https://linux-hardware.org/?probe=1e4dda911f) | Dec 03, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [e4f6d008cc](https://linux-hardware.org/?probe=e4f6d008cc) | Dec 03, 2023 |
| MSI           | 870A-G54                    | Desktop     | [46f9552be9](https://linux-hardware.org/?probe=46f9552be9) | Dec 03, 2023 |
| HP            | Pavilion dv7                | Notebook    | [42ddf2c00c](https://linux-hardware.org/?probe=42ddf2c00c) | Dec 03, 2023 |
| Unknown       | Unknown                     | Desktop     | [dca543f661](https://linux-hardware.org/?probe=dca543f661) | Dec 03, 2023 |
| HP            | Pavilion dv5                | Notebook    | [40e03f76cf](https://linux-hardware.org/?probe=40e03f76cf) | Dec 03, 2023 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [7a932c5570](https://linux-hardware.org/?probe=7a932c5570) | Dec 02, 2023 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [9b46bc6583](https://linux-hardware.org/?probe=9b46bc6583) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [f2a9f68180](https://linux-hardware.org/?probe=f2a9f68180) | Dec 02, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [e6d3755007](https://linux-hardware.org/?probe=e6d3755007) | Dec 02, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [5d98fa1470](https://linux-hardware.org/?probe=5d98fa1470) | Dec 02, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [9dea837056](https://linux-hardware.org/?probe=9dea837056) | Dec 02, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [f1e82db736](https://linux-hardware.org/?probe=f1e82db736) | Dec 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [aab717794b](https://linux-hardware.org/?probe=aab717794b) | Dec 01, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [ca692e6dcb](https://linux-hardware.org/?probe=ca692e6dcb) | Dec 01, 2023 |
| MSI           | MPG Z590M GAMING EDGE WI... | Desktop     | [a8495b2209](https://linux-hardware.org/?probe=a8495b2209) | Dec 01, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [72702ceb3f](https://linux-hardware.org/?probe=72702ceb3f) | Dec 01, 2023 |
| HP            | 15                          | Notebook    | [7bd98a81f6](https://linux-hardware.org/?probe=7bd98a81f6) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [02f2ca658e](https://linux-hardware.org/?probe=02f2ca658e) | Dec 01, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e812beed5d](https://linux-hardware.org/?probe=e812beed5d) | Dec 01, 2023 |
| Acer          | Extensa M2610 V:1.0         | Desktop     | [e4c1bd6f51](https://linux-hardware.org/?probe=e4c1bd6f51) | Nov 30, 2023 |
| Acer          | Aspire A517-52G             | Notebook    | [33126bb441](https://linux-hardware.org/?probe=33126bb441) | Nov 30, 2023 |
| Toshiba       | Satellite L850D-131         | Notebook    | [483c7cfdf6](https://linux-hardware.org/?probe=483c7cfdf6) | Nov 30, 2023 |
| AMI           | AMD                         | Notebook    | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B5602CBA... | Notebook    | [0c08316018](https://linux-hardware.org/?probe=0c08316018) | Nov 29, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [062cd64553](https://linux-hardware.org/?probe=062cd64553) | Nov 29, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [423e8001ab](https://linux-hardware.org/?probe=423e8001ab) | Nov 29, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [c934dcacd6](https://linux-hardware.org/?probe=c934dcacd6) | Nov 29, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9af25bdb99](https://linux-hardware.org/?probe=9af25bdb99) | Nov 28, 2023 |
| Medion        | Erazer P7643 MD60133        | Notebook    | [65f090fe28](https://linux-hardware.org/?probe=65f090fe28) | Nov 28, 2023 |
| HP            | 15                          | Notebook    | [c1ca96368f](https://linux-hardware.org/?probe=c1ca96368f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | Notebook    | [f99e3c8556](https://linux-hardware.org/?probe=f99e3c8556) | Nov 28, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [f85fb01be1](https://linux-hardware.org/?probe=f85fb01be1) | Nov 28, 2023 |
| HP            | 15                          | Notebook    | [aba1e87e5c](https://linux-hardware.org/?probe=aba1e87e5c) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [7d6885561f](https://linux-hardware.org/?probe=7d6885561f) | Nov 28, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [e106315577](https://linux-hardware.org/?probe=e106315577) | Nov 28, 2023 |
| Dell          | XPS 15 9550                 | Notebook    | [6d2e371a5f](https://linux-hardware.org/?probe=6d2e371a5f) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [bfd90230bc](https://linux-hardware.org/?probe=bfd90230bc) | Nov 27, 2023 |
| Lenovo        | Yoga 730-13IWL 81JR         | Convertible | [38dd158d3e](https://linux-hardware.org/?probe=38dd158d3e) | Nov 27, 2023 |
| Acer          | Aspire TC-280               | Desktop     | [4b2fec8699](https://linux-hardware.org/?probe=4b2fec8699) | Nov 27, 2023 |
| Dell          | Latitude D830               | Notebook    | [2e017edf81](https://linux-hardware.org/?probe=2e017edf81) | Nov 27, 2023 |
| HP            | ENVY m6                     | Notebook    | [41cff88708](https://linux-hardware.org/?probe=41cff88708) | Nov 26, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [fb45c81af9](https://linux-hardware.org/?probe=fb45c81af9) | Nov 26, 2023 |
| AZW           | Green G3                    | Desktop     | [c08be7a4cf](https://linux-hardware.org/?probe=c08be7a4cf) | Nov 26, 2023 |
| Toshiba       | TECRA W50-A                 | Notebook    | [91a2348496](https://linux-hardware.org/?probe=91a2348496) | Nov 25, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [e4062fc1e4](https://linux-hardware.org/?probe=e4062fc1e4) | Nov 25, 2023 |
| HP            | 82F1                        | Desktop     | [09c7b87413](https://linux-hardware.org/?probe=09c7b87413) | Nov 24, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [c9522c065e](https://linux-hardware.org/?probe=c9522c065e) | Nov 24, 2023 |
| HP            | 82F1                        | Desktop     | [9ed00910d4](https://linux-hardware.org/?probe=9ed00910d4) | Nov 24, 2023 |
| Lenovo        | ThinkPad T570 20HAS0K501    | Notebook    | [4fe6d8f889](https://linux-hardware.org/?probe=4fe6d8f889) | Nov 24, 2023 |
| Lenovo        | MAHOBAY Win8 STD EM DPK ... | All in one  | [a86dba284f](https://linux-hardware.org/?probe=a86dba284f) | Nov 24, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [6930db743c](https://linux-hardware.org/?probe=6930db743c) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [eb779ea004](https://linux-hardware.org/?probe=eb779ea004) | Nov 24, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0d60447eea](https://linux-hardware.org/?probe=0d60447eea) | Nov 24, 2023 |
| HP            | G5000 (GF767EA#B1A)         | Notebook    | [5239511cca](https://linux-hardware.org/?probe=5239511cca) | Nov 24, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [9d5752b2d8](https://linux-hardware.org/?probe=9d5752b2d8) | Nov 24, 2023 |
| Unknown       | M17                         | Notebook    | [d3d7d176b4](https://linux-hardware.org/?probe=d3d7d176b4) | Nov 23, 2023 |
| Medion        | E5214                       | Notebook    | [f3ab89b2d3](https://linux-hardware.org/?probe=f3ab89b2d3) | Nov 23, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [87ccf00042](https://linux-hardware.org/?probe=87ccf00042) | Nov 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c883420b97](https://linux-hardware.org/?probe=c883420b97) | Nov 23, 2023 |
| Gigabyte      | GA-MA74GMT-S2               | Desktop     | [440e7b6c7c](https://linux-hardware.org/?probe=440e7b6c7c) | Nov 23, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | Notebook    | [3b995f6b47](https://linux-hardware.org/?probe=3b995f6b47) | Nov 23, 2023 |
| Toshiba       | Satellite L850D-131         | Notebook    | [8810505a5a](https://linux-hardware.org/?probe=8810505a5a) | Nov 23, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | Notebook    | [37a1e3b979](https://linux-hardware.org/?probe=37a1e3b979) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [c5a84018e9](https://linux-hardware.org/?probe=c5a84018e9) | Nov 23, 2023 |
| HP            | 3029h                       | Desktop     | [2dd2ec759b](https://linux-hardware.org/?probe=2dd2ec759b) | Nov 23, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [fca11dfd70](https://linux-hardware.org/?probe=fca11dfd70) | Nov 23, 2023 |
| Acer          | Aspire ES1-731              | Notebook    | [649e8a4e24](https://linux-hardware.org/?probe=649e8a4e24) | Nov 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [8d492b21b0](https://linux-hardware.org/?probe=8d492b21b0) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [343ba69496](https://linux-hardware.org/?probe=343ba69496) | Nov 22, 2023 |
| HP            | 3561                        | All in one  | [aef249e21a](https://linux-hardware.org/?probe=aef249e21a) | Nov 22, 2023 |
| HUAWEI        | BoDE-WXX9                   | Notebook    | [b365872b3f](https://linux-hardware.org/?probe=b365872b3f) | Nov 22, 2023 |
| MSI           | Z390-A PRO                  | Desktop     | [1f07a66db1](https://linux-hardware.org/?probe=1f07a66db1) | Nov 22, 2023 |
| Samsung       | 530XBB                      | Notebook    | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [11f7e8f675](https://linux-hardware.org/?probe=11f7e8f675) | Nov 22, 2023 |
| HP            | EliteBook Folio 1020 G1     | Notebook    | [022f885fe9](https://linux-hardware.org/?probe=022f885fe9) | Nov 22, 2023 |
| Notebook      | NL40_50CU                   | Notebook    | [94885b9878](https://linux-hardware.org/?probe=94885b9878) | Nov 21, 2023 |
| AZW           | MINI S 10                   | Desktop     | [47bd270ae8](https://linux-hardware.org/?probe=47bd270ae8) | Nov 21, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [c363e01e5f](https://linux-hardware.org/?probe=c363e01e5f) | Nov 21, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [f9136272f9](https://linux-hardware.org/?probe=f9136272f9) | Nov 21, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [6e0d000498](https://linux-hardware.org/?probe=6e0d000498) | Nov 20, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [3664fc3164](https://linux-hardware.org/?probe=3664fc3164) | Nov 20, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6c2755ced9](https://linux-hardware.org/?probe=6c2755ced9) | Nov 20, 2023 |
| Lenovo        | ThinkPad Edge E530 32599... | Notebook    | [f472f3fd2e](https://linux-hardware.org/?probe=f472f3fd2e) | Nov 20, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8fbd1e56eb](https://linux-hardware.org/?probe=8fbd1e56eb) | Nov 20, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [84df1d0476](https://linux-hardware.org/?probe=84df1d0476) | Nov 20, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [97b8871652](https://linux-hardware.org/?probe=97b8871652) | Nov 20, 2023 |
| Medion        | E5214                       | Notebook    | [8e3148e284](https://linux-hardware.org/?probe=8e3148e284) | Nov 20, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [e0a3622122](https://linux-hardware.org/?probe=e0a3622122) | Nov 20, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [8047aac511](https://linux-hardware.org/?probe=8047aac511) | Nov 20, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [9137a70965](https://linux-hardware.org/?probe=9137a70965) | Nov 20, 2023 |
| AZW           | MINI S 10                   | Desktop     | [a1358be402](https://linux-hardware.org/?probe=a1358be402) | Nov 20, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [468cc043b8](https://linux-hardware.org/?probe=468cc043b8) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [be15ab8952](https://linux-hardware.org/?probe=be15ab8952) | Nov 19, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [626d8d9409](https://linux-hardware.org/?probe=626d8d9409) | Nov 19, 2023 |
| Intel         | H61                         | Desktop     | [bdab1dc80a](https://linux-hardware.org/?probe=bdab1dc80a) | Nov 19, 2023 |
| HUAWEI        | CREFG-XX                    | Notebook    | [747979b60f](https://linux-hardware.org/?probe=747979b60f) | Nov 19, 2023 |
| Intel         | H61                         | Desktop     | [4b5806ba4c](https://linux-hardware.org/?probe=4b5806ba4c) | Nov 19, 2023 |
| Acer          | Spin SP513-52N              | Convertible | [339c8003a9](https://linux-hardware.org/?probe=339c8003a9) | Nov 19, 2023 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [6876ff8fc6](https://linux-hardware.org/?probe=6876ff8fc6) | Nov 19, 2023 |
| Acer          | Extensa M2610 V:1.0         | Desktop     | [7b70ac1965](https://linux-hardware.org/?probe=7b70ac1965) | Nov 19, 2023 |
| Medion        | E5214                       | Notebook    | [4513f3394d](https://linux-hardware.org/?probe=4513f3394d) | Nov 18, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [b62a8b07f4](https://linux-hardware.org/?probe=b62a8b07f4) | Nov 18, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS AC    | Desktop     | [cb10d99771](https://linux-hardware.org/?probe=cb10d99771) | Nov 18, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [ec19f0fa52](https://linux-hardware.org/?probe=ec19f0fa52) | Nov 18, 2023 |
| Lenovo        | ThinkCentre M90p 5536Y1K    | Desktop     | [6bdc4cb524](https://linux-hardware.org/?probe=6bdc4cb524) | Nov 18, 2023 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [75cd18198b](https://linux-hardware.org/?probe=75cd18198b) | Nov 18, 2023 |
| Dell          | Latitude 5490               | Notebook    | [b3da1a92d0](https://linux-hardware.org/?probe=b3da1a92d0) | Nov 17, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [54bad5da51](https://linux-hardware.org/?probe=54bad5da51) | Nov 17, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [d087235304](https://linux-hardware.org/?probe=d087235304) | Nov 17, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [9974b99f5a](https://linux-hardware.org/?probe=9974b99f5a) | Nov 16, 2023 |
| HP            | Pavilion g7                 | Notebook    | [9f8b6f3432](https://linux-hardware.org/?probe=9f8b6f3432) | Nov 16, 2023 |
| HP            | Pavilion g7                 | Notebook    | [0c4816a4f2](https://linux-hardware.org/?probe=0c4816a4f2) | Nov 16, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [df572cd989](https://linux-hardware.org/?probe=df572cd989) | Nov 15, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [7edaa0f1be](https://linux-hardware.org/?probe=7edaa0f1be) | Nov 15, 2023 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [559ef6212b](https://linux-hardware.org/?probe=559ef6212b) | Nov 15, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [d79f8e5ed5](https://linux-hardware.org/?probe=d79f8e5ed5) | Nov 14, 2023 |
| HP            | ZBook 14u G6                | Notebook    | [c6471dbbfd](https://linux-hardware.org/?probe=c6471dbbfd) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [8c4d2fca5a](https://linux-hardware.org/?probe=8c4d2fca5a) | Nov 14, 2023 |
| Adreamer      | PN1308P                     | Notebook    | [5efc66eebc](https://linux-hardware.org/?probe=5efc66eebc) | Nov 14, 2023 |
| HP            | Compaq 6910p                | Notebook    | [019a154d30](https://linux-hardware.org/?probe=019a154d30) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [513485cc8f](https://linux-hardware.org/?probe=513485cc8f) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | Notebook    | [077bbdc325](https://linux-hardware.org/?probe=077bbdc325) | Nov 14, 2023 |
| Tactus        | GeoBook 110                 | Notebook    | [5e50f31cbb](https://linux-hardware.org/?probe=5e50f31cbb) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d00bbdf844](https://linux-hardware.org/?probe=d00bbdf844) | Nov 14, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [493702778b](https://linux-hardware.org/?probe=493702778b) | Nov 14, 2023 |
| Fujitsu       | D2619 S26361-D2619-N15 W... | Server      | [d9f5b1502c](https://linux-hardware.org/?probe=d9f5b1502c) | Nov 14, 2023 |
| Fujitsu       | D2619 S26361-D2619-N15 W... | Server      | [56925134d7](https://linux-hardware.org/?probe=56925134d7) | Nov 14, 2023 |
| JHZD          | BQM5                        | Desktop     | [cab813ae6e](https://linux-hardware.org/?probe=cab813ae6e) | Nov 14, 2023 |
| Gigabyte      | Z390 UD                     | Desktop     | [f961fee784](https://linux-hardware.org/?probe=f961fee784) | Nov 14, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [3c336ad6e1](https://linux-hardware.org/?probe=3c336ad6e1) | Nov 14, 2023 |
| Lenovo        | ThinkPad E550 20DF00CNGE    | Notebook    | [35e0f85cf3](https://linux-hardware.org/?probe=35e0f85cf3) | Nov 13, 2023 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [73a53ca5a4](https://linux-hardware.org/?probe=73a53ca5a4) | Nov 13, 2023 |
| Dell          | 0RW199                      | Desktop     | [e3b364ccd6](https://linux-hardware.org/?probe=e3b364ccd6) | Nov 13, 2023 |
| Intel         | H61                         | Desktop     | [cbefae3544](https://linux-hardware.org/?probe=cbefae3544) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a0105ee2c8](https://linux-hardware.org/?probe=a0105ee2c8) | Nov 13, 2023 |
| HP            | 15                          | Notebook    | [20b22b2eeb](https://linux-hardware.org/?probe=20b22b2eeb) | Nov 13, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [83d6eddd15](https://linux-hardware.org/?probe=83d6eddd15) | Nov 12, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [8bcc86ef17](https://linux-hardware.org/?probe=8bcc86ef17) | Nov 12, 2023 |
| HP            | ProLiant ML350e Gen8 v2     | Desktop     | [f5de128dd1](https://linux-hardware.org/?probe=f5de128dd1) | Nov 12, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [d46548a5e6](https://linux-hardware.org/?probe=d46548a5e6) | Nov 12, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [cd4230cf5b](https://linux-hardware.org/?probe=cd4230cf5b) | Nov 12, 2023 |
| HUAWEI        | RLEFG-XX                    | Notebook    | [5f413be4fc](https://linux-hardware.org/?probe=5f413be4fc) | Nov 12, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [1d2a92df29](https://linux-hardware.org/?probe=1d2a92df29) | Nov 12, 2023 |
| Lenovo        | ThinkPad E580 20KS001RGE    | Notebook    | [55b706c3ec](https://linux-hardware.org/?probe=55b706c3ec) | Nov 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS22Q00    | Notebook    | [4c40c1d213](https://linux-hardware.org/?probe=4c40c1d213) | Nov 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [16acb0dabc](https://linux-hardware.org/?probe=16acb0dabc) | Nov 11, 2023 |
| Toshiba       | Satellite L655              | Notebook    | [b3c59942a1](https://linux-hardware.org/?probe=b3c59942a1) | Nov 11, 2023 |
| Intel         | H61                         | Desktop     | [c65f2e03f6](https://linux-hardware.org/?probe=c65f2e03f6) | Nov 11, 2023 |
| HP            | Presario CQ62               | Notebook    | [584d709751](https://linux-hardware.org/?probe=584d709751) | Nov 11, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [1b3661590f](https://linux-hardware.org/?probe=1b3661590f) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [13798a5389](https://linux-hardware.org/?probe=13798a5389) | Nov 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b962155541](https://linux-hardware.org/?probe=b962155541) | Nov 11, 2023 |
| Dell          | Precision M6800             | Notebook    | [4ad69afe3a](https://linux-hardware.org/?probe=4ad69afe3a) | Nov 11, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e4fd0fa1f0](https://linux-hardware.org/?probe=e4fd0fa1f0) | Nov 10, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [fda2670cc5](https://linux-hardware.org/?probe=fda2670cc5) | Nov 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [08c8ac6e4d](https://linux-hardware.org/?probe=08c8ac6e4d) | Nov 09, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [c0e0567705](https://linux-hardware.org/?probe=c0e0567705) | Nov 09, 2023 |
| Lenovo        | Z40-70 20366                | Notebook    | [f1968605c1](https://linux-hardware.org/?probe=f1968605c1) | Nov 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [97e4b3093b](https://linux-hardware.org/?probe=97e4b3093b) | Nov 09, 2023 |
| Dell          | 0RW199                      | Desktop     | [11e414d343](https://linux-hardware.org/?probe=11e414d343) | Nov 08, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [6a30b05dcb](https://linux-hardware.org/?probe=6a30b05dcb) | Nov 08, 2023 |
| PEAQ          | PNB C1014-I1B1 MD99447      | Notebook    | [33d5a0aa8c](https://linux-hardware.org/?probe=33d5a0aa8c) | Nov 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b48cc5df9c](https://linux-hardware.org/?probe=b48cc5df9c) | Nov 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [cc75144dea](https://linux-hardware.org/?probe=cc75144dea) | Nov 08, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [38b21b9f64](https://linux-hardware.org/?probe=38b21b9f64) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| HP            | Compaq 6830s                | Notebook    | [069a45be37](https://linux-hardware.org/?probe=069a45be37) | Nov 08, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [abb549b943](https://linux-hardware.org/?probe=abb549b943) | Nov 07, 2023 |
| Lenovo        | ThinkPad T440p 20AWS08S0... | Notebook    | [b7e993f677](https://linux-hardware.org/?probe=b7e993f677) | Nov 07, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [864f50cabf](https://linux-hardware.org/?probe=864f50cabf) | Nov 07, 2023 |
| Fujitsu Si... | AMILO Li 1818               | Notebook    | [ab74cc1cc6](https://linux-hardware.org/?probe=ab74cc1cc6) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [c2434cadfc](https://linux-hardware.org/?probe=c2434cadfc) | Nov 07, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [a5628b0f9d](https://linux-hardware.org/?probe=a5628b0f9d) | Nov 07, 2023 |
| Lenovo        | Gardenia CRB SDK0J40709 ... | All in one  | [ef772812b1](https://linux-hardware.org/?probe=ef772812b1) | Nov 07, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [eea33256f6](https://linux-hardware.org/?probe=eea33256f6) | Nov 07, 2023 |
| Lenovo        | IdeaPad S400u 20213         | Notebook    | [5ddd610c2d](https://linux-hardware.org/?probe=5ddd610c2d) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| Dell          | Latitude E7450              | Notebook    | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| HP            | 1497                        | Desktop     | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | Desktop     | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Toshiba       | STI 001359                  | Desktop     | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [1173519349](https://linux-hardware.org/?probe=1173519349) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Timi          | A35                         | Notebook    | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [4372a2d9eb](https://linux-hardware.org/?probe=4372a2d9eb) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [fb7f16d298](https://linux-hardware.org/?probe=fb7f16d298) | Nov 02, 2023 |
| ASUSTek       | U36SD                       | Notebook    | [e2045d61a5](https://linux-hardware.org/?probe=e2045d61a5) | Nov 02, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [ef9bc3cc1e](https://linux-hardware.org/?probe=ef9bc3cc1e) | Nov 02, 2023 |
| ONDA          | Tablet                      | Tablet      | [1f8b5d6c72](https://linux-hardware.org/?probe=1f8b5d6c72) | Nov 01, 2023 |
| Dell          | 0XCR8D A01                  | Desktop     | [bc8414b164](https://linux-hardware.org/?probe=bc8414b164) | Nov 01, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [6db0212093](https://linux-hardware.org/?probe=6db0212093) | Nov 01, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [9fff8956bb](https://linux-hardware.org/?probe=9fff8956bb) | Nov 01, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [73a395f017](https://linux-hardware.org/?probe=73a395f017) | Nov 01, 2023 |
| Lenovo        | MAHOBAY                     | Desktop     | [319e545ba5](https://linux-hardware.org/?probe=319e545ba5) | Oct 31, 2023 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [3b667e2123](https://linux-hardware.org/?probe=3b667e2123) | Oct 31, 2023 |
| Pegatron      | EVANS                       | Desktop     | [3ea2a80843](https://linux-hardware.org/?probe=3ea2a80843) | Oct 31, 2023 |
| Pegatron      | EVANS                       | Desktop     | [52c3eeea68](https://linux-hardware.org/?probe=52c3eeea68) | Oct 31, 2023 |
| RCA           | W122SC24T2                  | Tablet      | [1313389b98](https://linux-hardware.org/?probe=1313389b98) | Oct 31, 2023 |
| RCA           | W122SC24T2                  | Tablet      | [f46f159a0c](https://linux-hardware.org/?probe=f46f159a0c) | Oct 31, 2023 |
| Sony          | SVS15116GAB                 | Notebook    | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [185b65ebc1](https://linux-hardware.org/?probe=185b65ebc1) | Oct 30, 2023 |
| HP            | 21F5 0A                     | Desktop     | [097ce56daf](https://linux-hardware.org/?probe=097ce56daf) | Oct 30, 2023 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [c447277c0b](https://linux-hardware.org/?probe=c447277c0b) | Oct 30, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [627ed781b5](https://linux-hardware.org/?probe=627ed781b5) | Oct 30, 2023 |
| HP            | 15                          | Notebook    | [1480b12f56](https://linux-hardware.org/?probe=1480b12f56) | Oct 30, 2023 |
| HP            | Notebook                    | Notebook    | [5538a0e3b2](https://linux-hardware.org/?probe=5538a0e3b2) | Oct 30, 2023 |
| HP            | Pavilion dv4                | Notebook    | [854806c6f4](https://linux-hardware.org/?probe=854806c6f4) | Oct 29, 2023 |
| HP            | 1998                        | Desktop     | [2182b05a45](https://linux-hardware.org/?probe=2182b05a45) | Oct 29, 2023 |
| HP            | ENVY 17                     | Notebook    | [8852bab8c1](https://linux-hardware.org/?probe=8852bab8c1) | Oct 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [28f261fb9a](https://linux-hardware.org/?probe=28f261fb9a) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | Notebook    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| Notebook      | PA70Hx                      | Notebook    | [e13de47400](https://linux-hardware.org/?probe=e13de47400) | Oct 29, 2023 |
| Lenovo        | ThinkPad E420 1141BTU       | Notebook    | [867e950bca](https://linux-hardware.org/?probe=867e950bca) | Oct 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [a123ac023f](https://linux-hardware.org/?probe=a123ac023f) | Oct 29, 2023 |
| MSI           | Z370M MORTAR                | Desktop     | [0af3708cd3](https://linux-hardware.org/?probe=0af3708cd3) | Oct 29, 2023 |
| HP            | 18E4                        | Desktop     | [b192ce4f35](https://linux-hardware.org/?probe=b192ce4f35) | Oct 28, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [97eabba1a8](https://linux-hardware.org/?probe=97eabba1a8) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [d48a91cce4](https://linux-hardware.org/?probe=d48a91cce4) | Oct 28, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [b9830b7f02](https://linux-hardware.org/?probe=b9830b7f02) | Oct 28, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [98c2ece6fd](https://linux-hardware.org/?probe=98c2ece6fd) | Oct 28, 2023 |
| HP            | ENVY 17                     | Notebook    | [aaa99aaa53](https://linux-hardware.org/?probe=aaa99aaa53) | Oct 27, 2023 |
| Acer          | TravelMate Spin P614RN-5    | Convertible | [e337a1e208](https://linux-hardware.org/?probe=e337a1e208) | Oct 27, 2023 |
| HCL Infosy... | HCL ME Laptop               | Notebook    | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| MSI           | Boston                      | Desktop     | [66f7505c8b](https://linux-hardware.org/?probe=66f7505c8b) | Oct 27, 2023 |
| Thomson       | WWNEO14C-4BK32F             | Notebook    | [516a5ee33b](https://linux-hardware.org/?probe=516a5ee33b) | Oct 27, 2023 |
| HP            | 2215                        | Desktop     | [01fd79c4fe](https://linux-hardware.org/?probe=01fd79c4fe) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [463b5f73b5](https://linux-hardware.org/?probe=463b5f73b5) | Oct 26, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [763e54c87b](https://linux-hardware.org/?probe=763e54c87b) | Oct 26, 2023 |
| HP            | G61                         | Notebook    | [d184a33522](https://linux-hardware.org/?probe=d184a33522) | Oct 26, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [67021475e9](https://linux-hardware.org/?probe=67021475e9) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [ec0dcdaa76](https://linux-hardware.org/?probe=ec0dcdaa76) | Oct 26, 2023 |
| ASUSTek       | PRIME X370-A                | Desktop     | [4f4d354524](https://linux-hardware.org/?probe=4f4d354524) | Oct 26, 2023 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [ca4ce5575c](https://linux-hardware.org/?probe=ca4ce5575c) | Oct 26, 2023 |
| HP            | Pavilion g7                 | Notebook    | [4699d107df](https://linux-hardware.org/?probe=4699d107df) | Oct 26, 2023 |
| LORD ELECT... | Guso G4x + ICH7 Series M... | Desktop     | [c6f81cf996](https://linux-hardware.org/?probe=c6f81cf996) | Oct 25, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [3c8f87fe9e](https://linux-hardware.org/?probe=3c8f87fe9e) | Oct 25, 2023 |
| Lenovo        | 0x36C4 SDK0M26027 WIN 32... | All in one  | [e0534a1c2a](https://linux-hardware.org/?probe=e0534a1c2a) | Oct 25, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6f9c14dc54](https://linux-hardware.org/?probe=6f9c14dc54) | Oct 24, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [039878b1b2](https://linux-hardware.org/?probe=039878b1b2) | Oct 24, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [706967e8e6](https://linux-hardware.org/?probe=706967e8e6) | Oct 24, 2023 |
| Gigabyte      | B85M-D3V Plus               | Desktop     | [845b1f10ef](https://linux-hardware.org/?probe=845b1f10ef) | Oct 24, 2023 |
| Dell          | 0RCPW3 A03                  | Desktop     | [a461b9f3e7](https://linux-hardware.org/?probe=a461b9f3e7) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [905555c7d5](https://linux-hardware.org/?probe=905555c7d5) | Oct 23, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [5f6d67d67e](https://linux-hardware.org/?probe=5f6d67d67e) | Oct 23, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [cd4e6f4d07](https://linux-hardware.org/?probe=cd4e6f4d07) | Oct 23, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [961b658ac5](https://linux-hardware.org/?probe=961b658ac5) | Oct 23, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | Notebook    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6f89b3f8ad](https://linux-hardware.org/?probe=6f89b3f8ad) | Oct 22, 2023 |
| ONDA          | Tablet                      | Tablet      | [2ef7c07bdf](https://linux-hardware.org/?probe=2ef7c07bdf) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ff9e1d6c16](https://linux-hardware.org/?probe=ff9e1d6c16) | Oct 22, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [9999b4b89a](https://linux-hardware.org/?probe=9999b4b89a) | Oct 22, 2023 |
| Dell          | Precision 7530              | Notebook    | [92f2a2c99e](https://linux-hardware.org/?probe=92f2a2c99e) | Oct 22, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [ef8715c7a7](https://linux-hardware.org/?probe=ef8715c7a7) | Oct 21, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [081a658255](https://linux-hardware.org/?probe=081a658255) | Oct 21, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [001d67067b](https://linux-hardware.org/?probe=001d67067b) | Oct 21, 2023 |
| ONDA          | Tablet                      | Tablet      | [835a5e9d6d](https://linux-hardware.org/?probe=835a5e9d6d) | Oct 21, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [5536078e9f](https://linux-hardware.org/?probe=5536078e9f) | Oct 21, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [ef8c0bb04c](https://linux-hardware.org/?probe=ef8c0bb04c) | Oct 21, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [330cbe85c6](https://linux-hardware.org/?probe=330cbe85c6) | Oct 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [a7ee33da8f](https://linux-hardware.org/?probe=a7ee33da8f) | Oct 21, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [6b9df8da7d](https://linux-hardware.org/?probe=6b9df8da7d) | Oct 21, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [11d8517f7e](https://linux-hardware.org/?probe=11d8517f7e) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [d8b8f7bafe](https://linux-hardware.org/?probe=d8b8f7bafe) | Oct 20, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [cb8d8311e7](https://linux-hardware.org/?probe=cb8d8311e7) | Oct 20, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [3dd8426b8f](https://linux-hardware.org/?probe=3dd8426b8f) | Oct 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [af96c09a64](https://linux-hardware.org/?probe=af96c09a64) | Oct 19, 2023 |
| MSI           | MAG Z590 TOMAHAWK WIFI      | Desktop     | [77079711d3](https://linux-hardware.org/?probe=77079711d3) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7fed113f9b](https://linux-hardware.org/?probe=7fed113f9b) | Oct 19, 2023 |
| ALLDOCUBE     | KnoteGo                     | Tablet      | [17833d30dc](https://linux-hardware.org/?probe=17833d30dc) | Oct 19, 2023 |
| HP            | 829A                        | Mini pc     | [8a3f72e9ef](https://linux-hardware.org/?probe=8a3f72e9ef) | Oct 19, 2023 |
| Dell          | Latitude 5490               | Notebook    | [cdf021cc62](https://linux-hardware.org/?probe=cdf021cc62) | Oct 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [060a642de4](https://linux-hardware.org/?probe=060a642de4) | Oct 19, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [051cd3c21e](https://linux-hardware.org/?probe=051cd3c21e) | Oct 19, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d37e5bc4f2](https://linux-hardware.org/?probe=d37e5bc4f2) | Oct 19, 2023 |
| ASUSTek       | X751SA                      | Notebook    | [21a2a5b900](https://linux-hardware.org/?probe=21a2a5b900) | Oct 18, 2023 |
| ONDA          | Tablet                      | Tablet      | [6a43a8d57d](https://linux-hardware.org/?probe=6a43a8d57d) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [bdc9d825d8](https://linux-hardware.org/?probe=bdc9d825d8) | Oct 18, 2023 |
| EPSON DIRE... | AT992E                      | Desktop     | [ec5284109e](https://linux-hardware.org/?probe=ec5284109e) | Oct 18, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [c1ea75561b](https://linux-hardware.org/?probe=c1ea75561b) | Oct 18, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [9a6fd46a7d](https://linux-hardware.org/?probe=9a6fd46a7d) | Oct 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [03cf657f5a](https://linux-hardware.org/?probe=03cf657f5a) | Oct 17, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | Notebook    | [f1e77b51bc](https://linux-hardware.org/?probe=f1e77b51bc) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| Acer          | Aspire SW5-012              | Notebook    | [848b8d7c20](https://linux-hardware.org/?probe=848b8d7c20) | Oct 17, 2023 |
| Lenovo        | ThinkPad T440 20B7S1D200    | Notebook    | [43185c1e5b](https://linux-hardware.org/?probe=43185c1e5b) | Oct 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [fd91b9ece9](https://linux-hardware.org/?probe=fd91b9ece9) | Oct 16, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [76e5cf1323](https://linux-hardware.org/?probe=76e5cf1323) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a0f3ae3d1a](https://linux-hardware.org/?probe=a0f3ae3d1a) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [cfc61d2f3c](https://linux-hardware.org/?probe=cfc61d2f3c) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [d22b6fa2e4](https://linux-hardware.org/?probe=d22b6fa2e4) | Oct 15, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [16a117accb](https://linux-hardware.org/?probe=16a117accb) | Oct 15, 2023 |
| HP            | Pavilion g7                 | Notebook    | [309ca4d5c7](https://linux-hardware.org/?probe=309ca4d5c7) | Oct 15, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [d43a466e59](https://linux-hardware.org/?probe=d43a466e59) | Oct 14, 2023 |
| Lenovo        | Yoga 7 16IAH7 82UF          | Convertible | [39e9986b39](https://linux-hardware.org/?probe=39e9986b39) | Oct 14, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [c6321b8063](https://linux-hardware.org/?probe=c6321b8063) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [35a5d0ac7c](https://linux-hardware.org/?probe=35a5d0ac7c) | Oct 14, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [081856b4e9](https://linux-hardware.org/?probe=081856b4e9) | Oct 14, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [0db9d6a5cf](https://linux-hardware.org/?probe=0db9d6a5cf) | Oct 14, 2023 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | Desktop     | [f4e7334b7e](https://linux-hardware.org/?probe=f4e7334b7e) | Oct 14, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [c2cbb1c407](https://linux-hardware.org/?probe=c2cbb1c407) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| MSI           | B85M-E45                    | Desktop     | [6ad9d3ff3c](https://linux-hardware.org/?probe=6ad9d3ff3c) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [ffd832c09d](https://linux-hardware.org/?probe=ffd832c09d) | Oct 13, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [c70591ee60](https://linux-hardware.org/?probe=c70591ee60) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| Lenovo        | V110-15IAP 80TG             | Notebook    | [314d81343b](https://linux-hardware.org/?probe=314d81343b) | Oct 12, 2023 |
| Schenker      | XMG CORE (REN/M20)          | Notebook    | [48ee28954d](https://linux-hardware.org/?probe=48ee28954d) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | Pavilion g7                 | Notebook    | [e276347e0a](https://linux-hardware.org/?probe=e276347e0a) | Oct 12, 2023 |
| Acer          | Aspire A317-55P             | Notebook    | [a4e8b9c99a](https://linux-hardware.org/?probe=a4e8b9c99a) | Oct 12, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [02414ff1af](https://linux-hardware.org/?probe=02414ff1af) | Oct 11, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| Acer          | Aspire A317-55P             | Notebook    | [3805200b55](https://linux-hardware.org/?probe=3805200b55) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [cc50dc0894](https://linux-hardware.org/?probe=cc50dc0894) | Oct 11, 2023 |
| MSI           | Z97-G55 SLI                 | Desktop     | [754748eac6](https://linux-hardware.org/?probe=754748eac6) | Oct 11, 2023 |
| Dell          | 0XHGV1 A00                  | Desktop     | [adda7a23c2](https://linux-hardware.org/?probe=adda7a23c2) | Oct 11, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [44a7bac1b9](https://linux-hardware.org/?probe=44a7bac1b9) | Oct 10, 2023 |
| AMI           | Intel                       | Desktop     | [1615dc16ba](https://linux-hardware.org/?probe=1615dc16ba) | Oct 10, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [df54ad11e5](https://linux-hardware.org/?probe=df54ad11e5) | Oct 10, 2023 |
| ASUSTek       | K42F                        | Notebook    | [0d099eb4f7](https://linux-hardware.org/?probe=0d099eb4f7) | Oct 10, 2023 |
| Lenovo        | Tiger Hill                  | Desktop     | [cdd9f65bf5](https://linux-hardware.org/?probe=cdd9f65bf5) | Oct 10, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [c4ae24b408](https://linux-hardware.org/?probe=c4ae24b408) | Oct 10, 2023 |
| Toshiba       | Satellite Pro R50-B         | Notebook    | [9b41869902](https://linux-hardware.org/?probe=9b41869902) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [53e4e70567](https://linux-hardware.org/?probe=53e4e70567) | Oct 09, 2023 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [332ce6061d](https://linux-hardware.org/?probe=332ce6061d) | Oct 09, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [8984311ce7](https://linux-hardware.org/?probe=8984311ce7) | Oct 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| HP            | Pavilion 15                 | Notebook    | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [067260a51f](https://linux-hardware.org/?probe=067260a51f) | Oct 08, 2023 |
| Shuttle       | FS110                       | Desktop     | [cd7c40ed57](https://linux-hardware.org/?probe=cd7c40ed57) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Lenovo        | ThinkPad T460s 20FAS08W0... | Notebook    | [24dee8bc07](https://linux-hardware.org/?probe=24dee8bc07) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [f347154767](https://linux-hardware.org/?probe=f347154767) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| Pegatron      | EVANS                       | Desktop     | [f798f24c90](https://linux-hardware.org/?probe=f798f24c90) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Alienware     | M14xR2                      | Notebook    | [3b7dd3717c](https://linux-hardware.org/?probe=3b7dd3717c) | Oct 07, 2023 |
| Dynabook      | PORTEGE X30W-J              | Convertible | [aa212009a2](https://linux-hardware.org/?probe=aa212009a2) | Oct 06, 2023 |
| Dell          | Precision 5530              | Notebook    | [38fdcea75f](https://linux-hardware.org/?probe=38fdcea75f) | Oct 06, 2023 |
| Thomson       | GEN360-4C128BK              | Notebook    | [ec04ddb0ba](https://linux-hardware.org/?probe=ec04ddb0ba) | Oct 06, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [d68de2a20e](https://linux-hardware.org/?probe=d68de2a20e) | Oct 06, 2023 |
| Intel         | X99                         | Desktop     | [9bc14ff597](https://linux-hardware.org/?probe=9bc14ff597) | Oct 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7add8932c3](https://linux-hardware.org/?probe=7add8932c3) | Oct 06, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [ff815f228b](https://linux-hardware.org/?probe=ff815f228b) | Oct 05, 2023 |
| Medion        | E4251 MD61435               | Notebook    | [b8f2dc6919](https://linux-hardware.org/?probe=b8f2dc6919) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [8313e4fb72](https://linux-hardware.org/?probe=8313e4fb72) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [7eec2f8e4e](https://linux-hardware.org/?probe=7eec2f8e4e) | Oct 05, 2023 |
| Dell          | Latitude 7480               | Notebook    | [a80bc8f591](https://linux-hardware.org/?probe=a80bc8f591) | Oct 05, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a6668a2378](https://linux-hardware.org/?probe=a6668a2378) | Oct 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [de22cbed3e](https://linux-hardware.org/?probe=de22cbed3e) | Oct 04, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [c3e7936a83](https://linux-hardware.org/?probe=c3e7936a83) | Oct 04, 2023 |
| Dell          | 0RW199                      | Desktop     | [f829184aa0](https://linux-hardware.org/?probe=f829184aa0) | Oct 04, 2023 |
| Dell          | G3 3579                     | Notebook    | [7730315a91](https://linux-hardware.org/?probe=7730315a91) | Oct 04, 2023 |
| Lenovo        | Tiger Hill                  | Desktop     | [4a3ef3e12f](https://linux-hardware.org/?probe=4a3ef3e12f) | Oct 03, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [1e6ec4d559](https://linux-hardware.org/?probe=1e6ec4d559) | Oct 03, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [0ebc5c48b5](https://linux-hardware.org/?probe=0ebc5c48b5) | Oct 03, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [00afde76db](https://linux-hardware.org/?probe=00afde76db) | Oct 03, 2023 |
| Pegatron      | EVANS                       | Desktop     | [3f2a4fe53e](https://linux-hardware.org/?probe=3f2a4fe53e) | Oct 03, 2023 |
| Gigabyte      | Z270-HD3-CF                 | Desktop     | [c23994e74a](https://linux-hardware.org/?probe=c23994e74a) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b210c95b8e](https://linux-hardware.org/?probe=b210c95b8e) | Oct 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [2519f8a695](https://linux-hardware.org/?probe=2519f8a695) | Oct 02, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [320836ef04](https://linux-hardware.org/?probe=320836ef04) | Oct 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [aa2d376e85](https://linux-hardware.org/?probe=aa2d376e85) | Oct 02, 2023 |
| MSI           | B85M-E45                    | Desktop     | [12fa4b4da3](https://linux-hardware.org/?probe=12fa4b4da3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | Desktop     | [2c6f35e1d3](https://linux-hardware.org/?probe=2c6f35e1d3) | Oct 02, 2023 |
| Acer          | Aspire M3450                | Desktop     | [ded620f59b](https://linux-hardware.org/?probe=ded620f59b) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [5698c85faa](https://linux-hardware.org/?probe=5698c85faa) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [056bfb8474](https://linux-hardware.org/?probe=056bfb8474) | Oct 01, 2023 |
| HP            | 470 17 inch G9              | Notebook    | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [dfa1322112](https://linux-hardware.org/?probe=dfa1322112) | Oct 01, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [8d558a64e8](https://linux-hardware.org/?probe=8d558a64e8) | Oct 01, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [127980fc54](https://linux-hardware.org/?probe=127980fc54) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [e0cdb74f25](https://linux-hardware.org/?probe=e0cdb74f25) | Oct 01, 2023 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [d9750c9040](https://linux-hardware.org/?probe=d9750c9040) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0669d0020d](https://linux-hardware.org/?probe=0669d0020d) | Sep 30, 2023 |
| Acer          | Predator G3610              | Desktop     | [cddfa514ba](https://linux-hardware.org/?probe=cddfa514ba) | Sep 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [c93af00811](https://linux-hardware.org/?probe=c93af00811) | Sep 30, 2023 |
| MP            | MS-7848                     | Desktop     | [63d5662351](https://linux-hardware.org/?probe=63d5662351) | Sep 30, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [237492c356](https://linux-hardware.org/?probe=237492c356) | Sep 30, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [d249d5e114](https://linux-hardware.org/?probe=d249d5e114) | Sep 30, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [186991da49](https://linux-hardware.org/?probe=186991da49) | Sep 29, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [145f7eccd3](https://linux-hardware.org/?probe=145f7eccd3) | Sep 29, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a318f83948](https://linux-hardware.org/?probe=a318f83948) | Sep 29, 2023 |
| Lenovo        | IdeaPad Slim 3 15IRU8 82... | Notebook    | [e9dd0291e0](https://linux-hardware.org/?probe=e9dd0291e0) | Sep 29, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [8ba160ee59](https://linux-hardware.org/?probe=8ba160ee59) | Sep 29, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [4aa521a31f](https://linux-hardware.org/?probe=4aa521a31f) | Sep 29, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [4f74530d68](https://linux-hardware.org/?probe=4f74530d68) | Sep 28, 2023 |
| Lenovo        | ThinkPad R60 9461DXG        | Notebook    | [5fb1e549ea](https://linux-hardware.org/?probe=5fb1e549ea) | Sep 28, 2023 |
| HP            | 2B35                        | Desktop     | [2f63f14724](https://linux-hardware.org/?probe=2f63f14724) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [cfd174dbe0](https://linux-hardware.org/?probe=cfd174dbe0) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [c717c1ab13](https://linux-hardware.org/?probe=c717c1ab13) | Sep 28, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f6c6bfc3fe](https://linux-hardware.org/?probe=f6c6bfc3fe) | Sep 27, 2023 |
| Lenovo        | ThinkPad E14 20RA0050US     | Notebook    | [097539dde8](https://linux-hardware.org/?probe=097539dde8) | Sep 27, 2023 |
| Medion        | E6431 MD60112               | Notebook    | [f1fee9da62](https://linux-hardware.org/?probe=f1fee9da62) | Sep 27, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [3d001a09ab](https://linux-hardware.org/?probe=3d001a09ab) | Sep 27, 2023 |
| HP            | Notebook                    | Notebook    | [4690fda15e](https://linux-hardware.org/?probe=4690fda15e) | Sep 27, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [e7e87a1269](https://linux-hardware.org/?probe=e7e87a1269) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [0c8a57738d](https://linux-hardware.org/?probe=0c8a57738d) | Sep 25, 2023 |
| AZW           | SER                         | Mini pc     | [8e73904b3c](https://linux-hardware.org/?probe=8e73904b3c) | Sep 25, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a778013e21](https://linux-hardware.org/?probe=a778013e21) | Sep 25, 2023 |
| Intel         | W7645                       | Notebook    | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| Dell          | 0Y5DDC A00                  | Desktop     | [29feb62e32](https://linux-hardware.org/?probe=29feb62e32) | Sep 25, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [863dfa9b96](https://linux-hardware.org/?probe=863dfa9b96) | Sep 25, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [1bee981c70](https://linux-hardware.org/?probe=1bee981c70) | Sep 25, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [7c901ae7fd](https://linux-hardware.org/?probe=7c901ae7fd) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | Notebook    | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| Alienware     | M17x                        | Notebook    | [5c6b700486](https://linux-hardware.org/?probe=5c6b700486) | Sep 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [6d75f2f29b](https://linux-hardware.org/?probe=6d75f2f29b) | Sep 24, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [f2a543d0dd](https://linux-hardware.org/?probe=f2a543d0dd) | Sep 24, 2023 |
| Sary          | Tab2                        | Tablet      | [7078e2b899](https://linux-hardware.org/?probe=7078e2b899) | Sep 23, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [fdfd7f2e50](https://linux-hardware.org/?probe=fdfd7f2e50) | Sep 23, 2023 |
| Sary          | Tab2                        | Tablet      | [913ec00764](https://linux-hardware.org/?probe=913ec00764) | Sep 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [6897fc6f5a](https://linux-hardware.org/?probe=6897fc6f5a) | Sep 23, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [02a39de387](https://linux-hardware.org/?probe=02a39de387) | Sep 23, 2023 |
| Dell          | 0HN7XN A01                  | Desktop     | [fd3ce44501](https://linux-hardware.org/?probe=fd3ce44501) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| Lenovo        | ThinkPad E575 20H8000HUS    | Notebook    | [8b5a2354c5](https://linux-hardware.org/?probe=8b5a2354c5) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [e513362f71](https://linux-hardware.org/?probe=e513362f71) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | Notebook    | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [81bf9d5194](https://linux-hardware.org/?probe=81bf9d5194) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [7ecfb9c56f](https://linux-hardware.org/?probe=7ecfb9c56f) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | Notebook    | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| AZW           | MINI S 10                   | Desktop     | [e393d95960](https://linux-hardware.org/?probe=e393d95960) | Sep 21, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [cc25c24fa5](https://linux-hardware.org/?probe=cc25c24fa5) | Sep 21, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d92a4fb2af](https://linux-hardware.org/?probe=d92a4fb2af) | Sep 21, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [a76faead17](https://linux-hardware.org/?probe=a76faead17) | Sep 21, 2023 |
| Acer          | TravelMate P246-MG          | Notebook    | [197b2c18c7](https://linux-hardware.org/?probe=197b2c18c7) | Sep 21, 2023 |
| Acer          | Aspire VN7-572G             | Notebook    | [8936ef0637](https://linux-hardware.org/?probe=8936ef0637) | Sep 21, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e57a830f9c](https://linux-hardware.org/?probe=e57a830f9c) | Sep 21, 2023 |
| Lenovo        | ThinkPad T570 20HAS1PC00    | Notebook    | [218325e9e3](https://linux-hardware.org/?probe=218325e9e3) | Sep 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [85a0203a02](https://linux-hardware.org/?probe=85a0203a02) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [dd7f2cf2b2](https://linux-hardware.org/?probe=dd7f2cf2b2) | Sep 20, 2023 |
| Lenovo        | ThinkPad T560 20FJS2BX00    | Notebook    | [c96d3bf498](https://linux-hardware.org/?probe=c96d3bf498) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | Desktop     | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [776633dd59](https://linux-hardware.org/?probe=776633dd59) | Sep 20, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [fcdaf47870](https://linux-hardware.org/?probe=fcdaf47870) | Sep 20, 2023 |
| Unknown       | Unknown                     | Desktop     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Dell          | 0RW199                      | Desktop     | [2857c6ada1](https://linux-hardware.org/?probe=2857c6ada1) | Sep 20, 2023 |
| Gigabyte      | Z790 UD AC                  | Desktop     | [83af285806](https://linux-hardware.org/?probe=83af285806) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [162a680d7d](https://linux-hardware.org/?probe=162a680d7d) | Sep 19, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [3d4f35cc26](https://linux-hardware.org/?probe=3d4f35cc26) | Sep 19, 2023 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [fcd8ef31df](https://linux-hardware.org/?probe=fcd8ef31df) | Sep 19, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [9fb8b99e70](https://linux-hardware.org/?probe=9fb8b99e70) | Sep 19, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [ca70cb035f](https://linux-hardware.org/?probe=ca70cb035f) | Sep 19, 2023 |
| Biostar       | H61MLC                      | Desktop     | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [f45c7732e3](https://linux-hardware.org/?probe=f45c7732e3) | Sep 19, 2023 |
| AZW           | GTR V21                     | Desktop     | [5066e153f8](https://linux-hardware.org/?probe=5066e153f8) | Sep 19, 2023 |
| HP            | Pavilion dv7                | Notebook    | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [5ec304bdb6](https://linux-hardware.org/?probe=5ec304bdb6) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [d03b8c1860](https://linux-hardware.org/?probe=d03b8c1860) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [202375fbb7](https://linux-hardware.org/?probe=202375fbb7) | Sep 18, 2023 |
| HP            | 3047h                       | Desktop     | [a955e9b6c6](https://linux-hardware.org/?probe=a955e9b6c6) | Sep 17, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [9e7069cdc3](https://linux-hardware.org/?probe=9e7069cdc3) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [065988c338](https://linux-hardware.org/?probe=065988c338) | Sep 17, 2023 |
| Hometech      | Ultra Tab 8W                | Notebook    | [1a9e79b92e](https://linux-hardware.org/?probe=1a9e79b92e) | Sep 17, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [08ed0347db](https://linux-hardware.org/?probe=08ed0347db) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [e639402c30](https://linux-hardware.org/?probe=e639402c30) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [b42ad40603](https://linux-hardware.org/?probe=b42ad40603) | Sep 17, 2023 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [3a230dc10f](https://linux-hardware.org/?probe=3a230dc10f) | Sep 16, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3774dfea8e](https://linux-hardware.org/?probe=3774dfea8e) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [87f26cde55](https://linux-hardware.org/?probe=87f26cde55) | Sep 16, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [8913a6c47f](https://linux-hardware.org/?probe=8913a6c47f) | Sep 16, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [72503b214c](https://linux-hardware.org/?probe=72503b214c) | Sep 16, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [16c14700d3](https://linux-hardware.org/?probe=16c14700d3) | Sep 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [00fd2287c0](https://linux-hardware.org/?probe=00fd2287c0) | Sep 16, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [f6be487f38](https://linux-hardware.org/?probe=f6be487f38) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| ASUSTek       | K54C                        | Notebook    | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [5cd83bcad9](https://linux-hardware.org/?probe=5cd83bcad9) | Sep 15, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [2c412a10ca](https://linux-hardware.org/?probe=2c412a10ca) | Sep 15, 2023 |
| Intel         | NUC6CAYB J23203-408         | Mini pc     | [def911de73](https://linux-hardware.org/?probe=def911de73) | Sep 14, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [83cb90361c](https://linux-hardware.org/?probe=83cb90361c) | Sep 14, 2023 |
| Itautec       | Infoway                     | Notebook    | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| Acer          | Aspire 5735                 | Notebook    | [9d3ceb6624](https://linux-hardware.org/?probe=9d3ceb6624) | Sep 14, 2023 |
| HP            | Notebook                    | Notebook    | [29f1834722](https://linux-hardware.org/?probe=29f1834722) | Sep 14, 2023 |
| MSI           | Bravo 15 A4DDR              | Notebook    | [bba9e61120](https://linux-hardware.org/?probe=bba9e61120) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [40aee3739e](https://linux-hardware.org/?probe=40aee3739e) | Sep 13, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [9bbec30b2f](https://linux-hardware.org/?probe=9bbec30b2f) | Sep 13, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | Desktop     | [3cba209625](https://linux-hardware.org/?probe=3cba209625) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [4dcd4e8234](https://linux-hardware.org/?probe=4dcd4e8234) | Sep 13, 2023 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [cbfa4c2641](https://linux-hardware.org/?probe=cbfa4c2641) | Sep 13, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [b94c2a0420](https://linux-hardware.org/?probe=b94c2a0420) | Sep 13, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [c9ce4cde54](https://linux-hardware.org/?probe=c9ce4cde54) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Sony          | VPCEB1E1E                   | Notebook    | [cbd095ee01](https://linux-hardware.org/?probe=cbd095ee01) | Sep 12, 2023 |
| Acer          | Aspire 5750ZG               | Notebook    | [9029730ffb](https://linux-hardware.org/?probe=9029730ffb) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [5358fa25ef](https://linux-hardware.org/?probe=5358fa25ef) | Sep 12, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [e4f73d159c](https://linux-hardware.org/?probe=e4f73d159c) | Sep 12, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [8ddbf6665f](https://linux-hardware.org/?probe=8ddbf6665f) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [9fc04871b0](https://linux-hardware.org/?probe=9fc04871b0) | Sep 12, 2023 |
| Gigabyte      | GA-890FXA-UD5               | Desktop     | [a80cffbabe](https://linux-hardware.org/?probe=a80cffbabe) | Sep 11, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [5907e59551](https://linux-hardware.org/?probe=5907e59551) | Sep 11, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [21baf66690](https://linux-hardware.org/?probe=21baf66690) | Sep 11, 2023 |
| Colorful T... | C.A68HM-K PLUS YV18         | Desktop     | [c57a3a012d](https://linux-hardware.org/?probe=c57a3a012d) | Sep 11, 2023 |
| HP            | Pavilion dv7                | Notebook    | [e7c7395c7b](https://linux-hardware.org/?probe=e7c7395c7b) | Sep 11, 2023 |
| ASUSTek       | PRIME H370-A                | Desktop     | [c757d0e2c3](https://linux-hardware.org/?probe=c757d0e2c3) | Sep 11, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Mini pc     | [39a15ba0ca](https://linux-hardware.org/?probe=39a15ba0ca) | Sep 10, 2023 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | Notebook    | [26fc33cb75](https://linux-hardware.org/?probe=26fc33cb75) | Sep 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [b211a425b2](https://linux-hardware.org/?probe=b211a425b2) | Sep 10, 2023 |
| ASUSTek       | X541UA                      | Notebook    | [a8184365b8](https://linux-hardware.org/?probe=a8184365b8) | Sep 10, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [a8db1b43ce](https://linux-hardware.org/?probe=a8db1b43ce) | Sep 09, 2023 |
| ASUSTek       | CG8270                      | Desktop     | [26b9818094](https://linux-hardware.org/?probe=26b9818094) | Sep 09, 2023 |
| Lenovo        | V110-14IAP 80TF             | Notebook    | [3ee6c9a460](https://linux-hardware.org/?probe=3ee6c9a460) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [6f66e35ec3](https://linux-hardware.org/?probe=6f66e35ec3) | Sep 09, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [9306917366](https://linux-hardware.org/?probe=9306917366) | Sep 09, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [382cd978ab](https://linux-hardware.org/?probe=382cd978ab) | Sep 08, 2023 |
| HP            | 8523 A01                    | Mini pc     | [b050702ce4](https://linux-hardware.org/?probe=b050702ce4) | Sep 08, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [c936953cf7](https://linux-hardware.org/?probe=c936953cf7) | Sep 08, 2023 |
| Lenovo        | ThinkPad T430 2349H2G       | Notebook    | [1d9d7c7f78](https://linux-hardware.org/?probe=1d9d7c7f78) | Sep 08, 2023 |
| HP            | 8299                        | Desktop     | [df4048bcc4](https://linux-hardware.org/?probe=df4048bcc4) | Sep 08, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [97d9faccab](https://linux-hardware.org/?probe=97d9faccab) | Sep 07, 2023 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [3112302ff6](https://linux-hardware.org/?probe=3112302ff6) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [d136074365](https://linux-hardware.org/?probe=d136074365) | Sep 07, 2023 |
| Acer          | Aspire X1470                | Desktop     | [a965ab170a](https://linux-hardware.org/?probe=a965ab170a) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [125a7f7c0d](https://linux-hardware.org/?probe=125a7f7c0d) | Sep 07, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fe02bb3d71](https://linux-hardware.org/?probe=fe02bb3d71) | Sep 07, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [6bb77310bf](https://linux-hardware.org/?probe=6bb77310bf) | Sep 06, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [0428af4d14](https://linux-hardware.org/?probe=0428af4d14) | Sep 06, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [415ba1cfc1](https://linux-hardware.org/?probe=415ba1cfc1) | Sep 06, 2023 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [a7e1067ce7](https://linux-hardware.org/?probe=a7e1067ce7) | Sep 06, 2023 |
| HP            | ProBook 650 G5              | Notebook    | [5e6e5cd047](https://linux-hardware.org/?probe=5e6e5cd047) | Sep 06, 2023 |
| Dell          | 0F3KHR A00                  | Desktop     | [53bfbec77e](https://linux-hardware.org/?probe=53bfbec77e) | Sep 06, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [3227a8a6bc](https://linux-hardware.org/?probe=3227a8a6bc) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Toshiba       | Satellite A210              | Notebook    | [54f5fb9c03](https://linux-hardware.org/?probe=54f5fb9c03) | Sep 06, 2023 |
| Alienware     | 0446JC A01                  | Desktop     | [d0c3088707](https://linux-hardware.org/?probe=d0c3088707) | Sep 06, 2023 |
| Framework     | Laptop                      | Notebook    | [bd2852cd9e](https://linux-hardware.org/?probe=bd2852cd9e) | Sep 05, 2023 |
| HP            | 0B54h D                     | Desktop     | [6fc93ef4ee](https://linux-hardware.org/?probe=6fc93ef4ee) | Sep 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [f8ec276ea3](https://linux-hardware.org/?probe=f8ec276ea3) | Sep 05, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [788841792b](https://linux-hardware.org/?probe=788841792b) | Sep 04, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [7f0254a775](https://linux-hardware.org/?probe=7f0254a775) | Sep 04, 2023 |
| Toshiba       | Satellite C70D-A            | Notebook    | [36070747fd](https://linux-hardware.org/?probe=36070747fd) | Sep 04, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [371c148953](https://linux-hardware.org/?probe=371c148953) | Sep 04, 2023 |
| Dell          | Latitude E6530              | Notebook    | [e1aa22b8b9](https://linux-hardware.org/?probe=e1aa22b8b9) | Sep 04, 2023 |
| Pegatron      | IPXSB-H61                   | Desktop     | [78a354984d](https://linux-hardware.org/?probe=78a354984d) | Sep 04, 2023 |
| Dell          | 0D28YY A01                  | Desktop     | [ae79e6a689](https://linux-hardware.org/?probe=ae79e6a689) | Sep 04, 2023 |
| Dell          | G15 5511                    | Notebook    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [2c9b64c445](https://linux-hardware.org/?probe=2c9b64c445) | Sep 03, 2023 |
| Lenovo        | Legion S7 16IAH7 82TF       | Notebook    | [f4c15b0551](https://linux-hardware.org/?probe=f4c15b0551) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | Notebook    | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [9ab1a9731d](https://linux-hardware.org/?probe=9ab1a9731d) | Sep 03, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [eee58fd067](https://linux-hardware.org/?probe=eee58fd067) | Sep 03, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [78d7ccad98](https://linux-hardware.org/?probe=78d7ccad98) | Sep 02, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [6215db2c5a](https://linux-hardware.org/?probe=6215db2c5a) | Sep 02, 2023 |
| AMI           | Intel                       | Convertible | [dd24abacfc](https://linux-hardware.org/?probe=dd24abacfc) | Sep 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [b2b0d3e018](https://linux-hardware.org/?probe=b2b0d3e018) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [f05f130786](https://linux-hardware.org/?probe=f05f130786) | Sep 02, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [7f9db7db99](https://linux-hardware.org/?probe=7f9db7db99) | Sep 01, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [027ceec09f](https://linux-hardware.org/?probe=027ceec09f) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | Notebook    | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [24743bf01d](https://linux-hardware.org/?probe=24743bf01d) | Sep 01, 2023 |
| Dell          | Latitude 5400               | Notebook    | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | Notebook    | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| HP            | ProBook 4740s               | Notebook    | [0ab7fe639e](https://linux-hardware.org/?probe=0ab7fe639e) | Sep 01, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [436e4af3ce](https://linux-hardware.org/?probe=436e4af3ce) | Aug 31, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [be8b002a45](https://linux-hardware.org/?probe=be8b002a45) | Aug 31, 2023 |
| HP            | 15                          | Notebook    | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Sony          | VPCEE23FX                   | Notebook    | [65714e4d48](https://linux-hardware.org/?probe=65714e4d48) | Aug 30, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [d963970016](https://linux-hardware.org/?probe=d963970016) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| HP            | 8054                        | Desktop     | [f73271d96e](https://linux-hardware.org/?probe=f73271d96e) | Aug 30, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3fb03adafb](https://linux-hardware.org/?probe=3fb03adafb) | Aug 29, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [01701d7ab0](https://linux-hardware.org/?probe=01701d7ab0) | Aug 29, 2023 |
| ASUSTek       | K93SV                       | Notebook    | [6da5e2d119](https://linux-hardware.org/?probe=6da5e2d119) | Aug 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [9b92626f63](https://linux-hardware.org/?probe=9b92626f63) | Aug 29, 2023 |
| Intel         | S2600CP G50768-512          | Server      | [eba7f74017](https://linux-hardware.org/?probe=eba7f74017) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [fffbca3973](https://linux-hardware.org/?probe=fffbca3973) | Aug 28, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [8e13da67ed](https://linux-hardware.org/?probe=8e13da67ed) | Aug 28, 2023 |
| Intel         | H61                         | Desktop     | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| Lenovo        | Yoga 3 14 80JH              | Notebook    | [5268d75df2](https://linux-hardware.org/?probe=5268d75df2) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [bdd515fe27](https://linux-hardware.org/?probe=bdd515fe27) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | Notebook    | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [cb2419d3df](https://linux-hardware.org/?probe=cb2419d3df) | Aug 27, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4357727561](https://linux-hardware.org/?probe=4357727561) | Aug 27, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [2031fd343b](https://linux-hardware.org/?probe=2031fd343b) | Aug 27, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [929efec703](https://linux-hardware.org/?probe=929efec703) | Aug 27, 2023 |
| eMachines     | EL1352                      | Desktop     | [5f9258beb2](https://linux-hardware.org/?probe=5f9258beb2) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [06f19f4198](https://linux-hardware.org/?probe=06f19f4198) | Aug 26, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6fbf874054](https://linux-hardware.org/?probe=6fbf874054) | Aug 26, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [e212f5bc28](https://linux-hardware.org/?probe=e212f5bc28) | Aug 25, 2023 |
| Google        | Rammus                      | Notebook    | [28554e7ce5](https://linux-hardware.org/?probe=28554e7ce5) | Aug 25, 2023 |
| GuoGuang      | IC2M1028N                   | Desktop     | [ffcd5b9fa5](https://linux-hardware.org/?probe=ffcd5b9fa5) | Aug 25, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [270cd028cf](https://linux-hardware.org/?probe=270cd028cf) | Aug 25, 2023 |
| HP            | ProBook 640 G4              | Notebook    | [3b75cf22fb](https://linux-hardware.org/?probe=3b75cf22fb) | Aug 25, 2023 |
| Samsung       | 960QFG                      | Convertible | [400b83d634](https://linux-hardware.org/?probe=400b83d634) | Aug 24, 2023 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [42d3a714ac](https://linux-hardware.org/?probe=42d3a714ac) | Aug 24, 2023 |
| TERRA         | TERRAPC                     | Notebook    | [b33c6ce6e8](https://linux-hardware.org/?probe=b33c6ce6e8) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | ProBook 4740s               | Notebook    | [f9e2a275da](https://linux-hardware.org/?probe=f9e2a275da) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [7712e558c5](https://linux-hardware.org/?probe=7712e558c5) | Aug 24, 2023 |
| AZW           | MINI S                      | Desktop     | [6296a4f71d](https://linux-hardware.org/?probe=6296a4f71d) | Aug 24, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [64859dd75d](https://linux-hardware.org/?probe=64859dd75d) | Aug 24, 2023 |
| HP            | 8299                        | Desktop     | [aa27bed4f1](https://linux-hardware.org/?probe=aa27bed4f1) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| ASUSTek       | X756UQ                      | Notebook    | [0ff5520460](https://linux-hardware.org/?probe=0ff5520460) | Aug 22, 2023 |
| Lenovo        | ThinkPad P51 20HJS3MY00     | Notebook    | [010dac0caa](https://linux-hardware.org/?probe=010dac0caa) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [9b52370ec1](https://linux-hardware.org/?probe=9b52370ec1) | Aug 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [51e91dd03e](https://linux-hardware.org/?probe=51e91dd03e) | Aug 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [2a05992a61](https://linux-hardware.org/?probe=2a05992a61) | Aug 21, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | Notebook    | [a440d57d28](https://linux-hardware.org/?probe=a440d57d28) | Aug 21, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [409855b61b](https://linux-hardware.org/?probe=409855b61b) | Aug 21, 2023 |
| Dell          | Precision M4700             | Notebook    | [9ec95d5a4d](https://linux-hardware.org/?probe=9ec95d5a4d) | Aug 21, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [7a206bdd57](https://linux-hardware.org/?probe=7a206bdd57) | Aug 21, 2023 |
| HP            | Notebook                    | Notebook    | [5b7ff7f278](https://linux-hardware.org/?probe=5b7ff7f278) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Dell          | Latitude 3350               | Notebook    | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | Unknown                     | Notebook    | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | Notebook    | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Alienware     | 17                          | Notebook    | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [2ac06099d8](https://linux-hardware.org/?probe=2ac06099d8) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [f97c8a25c5](https://linux-hardware.org/?probe=f97c8a25c5) | Aug 19, 2023 |
| ASUSTek       | P5L-MX                      | Desktop     | [f06dbc1b8c](https://linux-hardware.org/?probe=f06dbc1b8c) | Aug 19, 2023 |
| HP            | 3047h                       | Desktop     | [91d9eaa1de](https://linux-hardware.org/?probe=91d9eaa1de) | Aug 19, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [2c20d038ca](https://linux-hardware.org/?probe=2c20d038ca) | Aug 19, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [d109b04177](https://linux-hardware.org/?probe=d109b04177) | Aug 19, 2023 |
| Acer          | Swift SF514-52T             | Notebook    | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| ASUSTek       | X550ZA                      | Notebook    | [7f23195701](https://linux-hardware.org/?probe=7f23195701) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| HP            | 3047h                       | Desktop     | [a4aa888c24](https://linux-hardware.org/?probe=a4aa888c24) | Aug 18, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [720c3bfa88](https://linux-hardware.org/?probe=720c3bfa88) | Aug 18, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [d14c477dc9](https://linux-hardware.org/?probe=d14c477dc9) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [7092a32ce5](https://linux-hardware.org/?probe=7092a32ce5) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [58866ca1fb](https://linux-hardware.org/?probe=58866ca1fb) | Aug 17, 2023 |
| HP            | 3032h                       | Desktop     | [34a300f540](https://linux-hardware.org/?probe=34a300f540) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [d7402c2c8d](https://linux-hardware.org/?probe=d7402c2c8d) | Aug 17, 2023 |
| TAGTech       | TAGITOP-UNI C               | Notebook    | [1cccdef7f4](https://linux-hardware.org/?probe=1cccdef7f4) | Aug 17, 2023 |
| Intel         | X79M-S                      | Desktop     | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| Google        | Coral                       | Notebook    | [f8ed9b3bda](https://linux-hardware.org/?probe=f8ed9b3bda) | Aug 17, 2023 |
| Lenovo        | ThinkPad T480 20L5S04F00    | Notebook    | [7eb670d219](https://linux-hardware.org/?probe=7eb670d219) | Aug 17, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [de9a1cb848](https://linux-hardware.org/?probe=de9a1cb848) | Aug 17, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [7c1a42d442](https://linux-hardware.org/?probe=7c1a42d442) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [50731e7c54](https://linux-hardware.org/?probe=50731e7c54) | Aug 16, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [50b5957370](https://linux-hardware.org/?probe=50b5957370) | Aug 16, 2023 |
| Lenovo        | G40-30 80FY                 | Notebook    | [6574b3e96d](https://linux-hardware.org/?probe=6574b3e96d) | Aug 16, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [86c85e57c2](https://linux-hardware.org/?probe=86c85e57c2) | Aug 16, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [b31bf50c6e](https://linux-hardware.org/?probe=b31bf50c6e) | Aug 16, 2023 |
| Dell          | Latitude D630               | Notebook    | [878b00d959](https://linux-hardware.org/?probe=878b00d959) | Aug 15, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [3da24e6a41](https://linux-hardware.org/?probe=3da24e6a41) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [645730bff3](https://linux-hardware.org/?probe=645730bff3) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [08fc74cb7b](https://linux-hardware.org/?probe=08fc74cb7b) | Aug 15, 2023 |
| Sony          | VGN-SR19VN                  | Notebook    | [7adc151adb](https://linux-hardware.org/?probe=7adc151adb) | Aug 15, 2023 |
| Biostar       | H410MH                      | Desktop     | [abe98ae584](https://linux-hardware.org/?probe=abe98ae584) | Aug 15, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [bb4bf558dd](https://linux-hardware.org/?probe=bb4bf558dd) | Aug 15, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [e79cdd0ba3](https://linux-hardware.org/?probe=e79cdd0ba3) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | Notebook    | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Medion        | E15301                      | Notebook    | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [102a6b136f](https://linux-hardware.org/?probe=102a6b136f) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f09f15784f](https://linux-hardware.org/?probe=f09f15784f) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | 30D9 SDK0J40697 WIN 3305... | Desktop     | [7e47b7128b](https://linux-hardware.org/?probe=7e47b7128b) | Aug 13, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | Notebook    | [777c4f7fb8](https://linux-hardware.org/?probe=777c4f7fb8) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | Notebook    | [c692882ce4](https://linux-hardware.org/?probe=c692882ce4) | Aug 13, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [ff8bec8b75](https://linux-hardware.org/?probe=ff8bec8b75) | Aug 12, 2023 |
| AMI           | Unknown                     | Notebook    | [326999bd6b](https://linux-hardware.org/?probe=326999bd6b) | Aug 12, 2023 |
| AMI           | Unknown                     | Notebook    | [614b443c5c](https://linux-hardware.org/?probe=614b443c5c) | Aug 12, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [17179d26d5](https://linux-hardware.org/?probe=17179d26d5) | Aug 12, 2023 |
| HP            | 350 G2                      | Notebook    | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| MSI           | 2AE0                        | Desktop     | [b8a2a0eb5c](https://linux-hardware.org/?probe=b8a2a0eb5c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [71f554fd2c](https://linux-hardware.org/?probe=71f554fd2c) | Aug 12, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [edd42a9a6d](https://linux-hardware.org/?probe=edd42a9a6d) | Aug 12, 2023 |
| Lenovo        | IdeaPad Duet 3 11IAN8 82... | Tablet      | [b61e23d1ec](https://linux-hardware.org/?probe=b61e23d1ec) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | Notebook    | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [d35bac0620](https://linux-hardware.org/?probe=d35bac0620) | Aug 12, 2023 |
| Biostar       | A770 A2+                    | Desktop     | [fb7d0009fd](https://linux-hardware.org/?probe=fb7d0009fd) | Aug 12, 2023 |
| Dell          | 0XKD8M A00                  | All in one  | [6cbd6d691c](https://linux-hardware.org/?probe=6cbd6d691c) | Aug 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| HP            | 3032h                       | Desktop     | [1727f042cd](https://linux-hardware.org/?probe=1727f042cd) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | Notebook    | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Dell          | XPS 13 9365                 | Convertible | [a2756bd55e](https://linux-hardware.org/?probe=a2756bd55e) | Aug 10, 2023 |
| Intel         | DZ68BC AAG30742-401         | Desktop     | [9bf37df045](https://linux-hardware.org/?probe=9bf37df045) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | Notebook    | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [6e9ca3c833](https://linux-hardware.org/?probe=6e9ca3c833) | Aug 09, 2023 |
| HP            | 3032h                       | Desktop     | [03a8cc31ea](https://linux-hardware.org/?probe=03a8cc31ea) | Aug 09, 2023 |
| HP            | Presario CQ56               | Notebook    | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [6047747c8f](https://linux-hardware.org/?probe=6047747c8f) | Aug 09, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [8a11b56d79](https://linux-hardware.org/?probe=8a11b56d79) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Acidanther... | Mac-AA95B1DDAB278B95 iMa... | All in one  | [9c789edd52](https://linux-hardware.org/?probe=9c789edd52) | Aug 08, 2023 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [2e30c62b25](https://linux-hardware.org/?probe=2e30c62b25) | Aug 08, 2023 |
| Intel         | X79M-S                      | Desktop     | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [965220ce86](https://linux-hardware.org/?probe=965220ce86) | Aug 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | Notebook    | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c95daf7007](https://linux-hardware.org/?probe=c95daf7007) | Aug 06, 2023 |
| Pegatron      | IPMMB-MQ1                   | Desktop     | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [6b22ae1f36](https://linux-hardware.org/?probe=6b22ae1f36) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [1af709c14e](https://linux-hardware.org/?probe=1af709c14e) | Aug 05, 2023 |
| Gigabyte      | Z97X-UD5H                   | Desktop     | [3bc330734d](https://linux-hardware.org/?probe=3bc330734d) | Aug 05, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [3b5e9f52a2](https://linux-hardware.org/?probe=3b5e9f52a2) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [5d998a099e](https://linux-hardware.org/?probe=5d998a099e) | Aug 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [e57d71e056](https://linux-hardware.org/?probe=e57d71e056) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | Notebook    | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [8ee9cccace](https://linux-hardware.org/?probe=8ee9cccace) | Aug 05, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [7ffb6822e6](https://linux-hardware.org/?probe=7ffb6822e6) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | Notebook    | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [3793d876eb](https://linux-hardware.org/?probe=3793d876eb) | Aug 04, 2023 |
| GPD           | G1621-02                    | Notebook    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [9f27152a86](https://linux-hardware.org/?probe=9f27152a86) | Aug 04, 2023 |
| Dell          | Latitude 7490               | Notebook    | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | Notebook    | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [35cf0fd859](https://linux-hardware.org/?probe=35cf0fd859) | Aug 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| HP            | 89B5 A                      | Desktop     | [cb6f36f32c](https://linux-hardware.org/?probe=cb6f36f32c) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | Notebook    | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | Notebook    | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | Notebook    | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [cfce53f1a3](https://linux-hardware.org/?probe=cfce53f1a3) | Aug 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [731a8b0e31](https://linux-hardware.org/?probe=731a8b0e31) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| AZW           | GTR V01                     | Mini pc     | [f3f9a4366b](https://linux-hardware.org/?probe=f3f9a4366b) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [287740b630](https://linux-hardware.org/?probe=287740b630) | Aug 01, 2023 |
| HP            | 1496                        | Desktop     | [24863488f0](https://linux-hardware.org/?probe=24863488f0) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [90dce7a9cf](https://linux-hardware.org/?probe=90dce7a9cf) | Jul 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [0ce1be51b9](https://linux-hardware.org/?probe=0ce1be51b9) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | Notebook    | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| Gigabyte      | M68MT-S2                    | Desktop     | [b1125cd76c](https://linux-hardware.org/?probe=b1125cd76c) | Jul 29, 2023 |
| HP            | Pavilion dv4                | Notebook    | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [1771e4ca4b](https://linux-hardware.org/?probe=1771e4ca4b) | Jul 29, 2023 |
| ASUSTek       | H97-PRO GAMER               | Desktop     | [e668b29cf4](https://linux-hardware.org/?probe=e668b29cf4) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Lenovo        | 30D0 SDK0J40705 WIN 3425... | Desktop     | [8c930cc5e4](https://linux-hardware.org/?probe=8c930cc5e4) | Jul 29, 2023 |
| HP            | Pavilion g7                 | Notebook    | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [310207e0fd](https://linux-hardware.org/?probe=310207e0fd) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [7583695051](https://linux-hardware.org/?probe=7583695051) | Jul 28, 2023 |
| Microsoft     | Surface 3                   | Tablet      | [fe7c4fd681](https://linux-hardware.org/?probe=fe7c4fd681) | Jul 28, 2023 |
| Google        | Edgar                       | Notebook    | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | Notebook    | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| Pegatron      | BOWIE                       | Desktop     | [4d413cb864](https://linux-hardware.org/?probe=4d413cb864) | Jul 28, 2023 |
| HP            | 3397                        | Desktop     | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [e7fdf45ff0](https://linux-hardware.org/?probe=e7fdf45ff0) | Jul 27, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [2f12124bed](https://linux-hardware.org/?probe=2f12124bed) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| MP            | MS-7848                     | Desktop     | [3dd9f22548](https://linux-hardware.org/?probe=3dd9f22548) | Jul 26, 2023 |
| Intel         | NUC13ANBi7 M89645-203       | Mini pc     | [238c98ee81](https://linux-hardware.org/?probe=238c98ee81) | Jul 26, 2023 |
| Lenovo        | No DPK                      | All in one  | [1b1fa8ccec](https://linux-hardware.org/?probe=1b1fa8ccec) | Jul 26, 2023 |
| Acer          | Elena                       | Desktop     | [78eff851f2](https://linux-hardware.org/?probe=78eff851f2) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [1b062f3c31](https://linux-hardware.org/?probe=1b062f3c31) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| ASRock        | Z97M Pro4                   | Desktop     | [bca4424b5d](https://linux-hardware.org/?probe=bca4424b5d) | Jul 26, 2023 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0236b3ce26](https://linux-hardware.org/?probe=0236b3ce26) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [1355a4f2f4](https://linux-hardware.org/?probe=1355a4f2f4) | Jul 25, 2023 |
| Acer          | TravelMate B113             | Notebook    | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [47fec524e4](https://linux-hardware.org/?probe=47fec524e4) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | Notebook    | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [431abc64d1](https://linux-hardware.org/?probe=431abc64d1) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | Notebook    | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | Notebook    | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | Notebook    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| HP            | 8350                        | Desktop     | [f17382c501](https://linux-hardware.org/?probe=f17382c501) | Jul 23, 2023 |
| Dell          | Latitude E6400              | Notebook    | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [13bb65f561](https://linux-hardware.org/?probe=13bb65f561) | Jul 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 235       | 5.29%   |
| 5.11.0-38-generic | 180       | 4.05%   |
| 5.11.0-27-generic | 156       | 3.51%   |
| 5.15.0-58-generic | 152       | 3.42%   |
| 5.15.0-46-generic | 152       | 3.42%   |
| 5.15.0-52-generic | 151       | 3.4%    |
| 5.15.0-67-generic | 143       | 3.22%   |
| 5.15.0-69-generic | 136       | 3.06%   |
| 5.13.0-30-generic | 126       | 2.84%   |
| 5.15.0-78-generic | 124       | 2.79%   |
| 5.11.0-40-generic | 124       | 2.79%   |
| 5.13.0-39-generic | 122       | 2.75%   |
| 5.15.0-60-generic | 109       | 2.45%   |
| 5.11.0-41-generic | 108       | 2.43%   |
| 5.11.0-37-generic | 107       | 2.41%   |
| 5.15.0-76-generic | 106       | 2.39%   |
| 5.15.0-71-generic | 104       | 2.34%   |
| 5.11.0-43-generic | 101       | 2.27%   |
| 5.15.0-48-generic | 95        | 2.14%   |
| 5.11.0-34-generic | 94        | 2.12%   |
| 5.15.0-88-generic | 93        | 2.09%   |
| 5.13.0-40-generic | 90        | 2.03%   |
| 5.15.0-53-generic | 81        | 1.82%   |
| 5.15.0-84-generic | 80        | 1.8%    |
| 5.15.0-41-generic | 77        | 1.73%   |
| 5.13.0-44-generic | 76        | 1.71%   |
| 5.13.0-35-generic | 74        | 1.67%   |
| 5.13.0-28-generic | 73        | 1.64%   |
| 5.15.0-73-generic | 68        | 1.53%   |
| 5.15.0-89-generic | 66        | 1.49%   |
| 5.15.0-86-generic | 66        | 1.49%   |
| 5.15.0-83-generic | 59        | 1.33%   |
| 5.15.0-72-generic | 59        | 1.33%   |
| 5.13.0-52-generic | 59        | 1.33%   |
| 5.13.0-27-generic | 59        | 1.33%   |
| 5.15.0-91-generic | 58        | 1.31%   |
| 5.15.0-79-generic | 55        | 1.24%   |
| 5.13.0-41-generic | 54        | 1.22%   |
| 5.15.0-87-generic | 44        | 0.99%   |
| 5.13.0-51-generic | 42        | 0.95%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 2145      | 53.77%  |
| 5.11.0  | 951       | 23.84%  |
| 5.13.0  | 769       | 19.28%  |
| 5.8.0   | 53        | 1.33%   |
| 5.14.0  | 10        | 0.25%   |
| 6.3.13  | 5         | 0.13%   |
| 6.5.7   | 4         | 0.1%    |
| 5.4.0   | 4         | 0.1%    |
| 6.2.16  | 3         | 0.08%   |
| 6.3.2   | 2         | 0.05%   |
| 5.19.12 | 2         | 0.05%   |
| 5.19.0  | 2         | 0.05%   |
| 5.18.15 | 2         | 0.05%   |
| 5.17.5  | 2         | 0.05%   |
| 5.17.1  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.10.0  | 2         | 0.05%   |
| 6.6.7   | 1         | 0.03%   |
| 6.6.1   | 1         | 0.03%   |
| 6.3.1   | 1         | 0.03%   |
| 6.3.0   | 1         | 0.03%   |
| 6.2.7   | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.1.8   | 1         | 0.03%   |
| 6.1.7   | 1         | 0.03%   |
| 6.1.22  | 1         | 0.03%   |
| 6.0.9   | 1         | 0.03%   |
| 6.0.8   | 1         | 0.03%   |
| 6.0.19  | 1         | 0.03%   |
| 6.0.0   | 1         | 0.03%   |
| 5.4.180 | 1         | 0.03%   |
| 5.19.9  | 1         | 0.03%   |
| 5.19.6  | 1         | 0.03%   |
| 5.19.2  | 1         | 0.03%   |
| 5.19.14 | 1         | 0.03%   |
| 5.19.1  | 1         | 0.03%   |
| 5.18.6  | 1         | 0.03%   |
| 5.18.19 | 1         | 0.03%   |
| 5.17.9  | 1         | 0.03%   |
| 5.16.5  | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 2148      | 53.86%  |
| 5.11    | 951       | 23.85%  |
| 5.13    | 770       | 19.31%  |
| 5.8     | 53        | 1.33%   |
| 5.14    | 10        | 0.25%   |
| 6.3     | 9         | 0.23%   |
| 5.19    | 9         | 0.23%   |
| 6.2     | 5         | 0.13%   |
| 5.4     | 5         | 0.13%   |
| 5.17    | 5         | 0.13%   |
| 5.16    | 5         | 0.13%   |
| 6.5     | 4         | 0.1%    |
| 6.0     | 4         | 0.1%    |
| 5.18    | 4         | 0.1%    |
| 6.6     | 2         | 0.05%   |
| 6.1     | 2         | 0.05%   |
| 5.10    | 2         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3829      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3278      | 84.92%  |
| XFCE       | 534       | 13.83%  |
| Unknown    | 23        | 0.6%    |
| KDE5       | 7         | 0.18%   |
| X-Cinnamon | 4         | 0.1%    |
| Cinnamon   | 3         | 0.08%   |
| Budgie     | 3         | 0.08%   |
| Unity      | 2         | 0.05%   |
| i3         | 2         | 0.05%   |
| MATE       | 1         | 0.03%   |
| LXQt       | 1         | 0.03%   |
| LXDE       | 1         | 0.03%   |
| KDE        | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3771      | 97.87%  |
| Wayland | 72        | 1.87%   |
| Unknown | 8         | 0.21%   |
| Tty     | 2         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2981      | 76.79%  |
| GDM     | 413       | 10.64%  |
| GDM3    | 347       | 8.94%   |
| LightDM | 137       | 3.53%   |
| SDDM    | 2         | 0.05%   |
| TDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 1507      | 39.15%  |
| de_DE | 380       | 9.87%   |
| en_GB | 258       | 6.7%    |
| pt_BR | 215       | 5.59%   |
| fr_FR | 143       | 3.72%   |
| it_IT | 120       | 3.12%   |
| es_ES | 120       | 3.12%   |
| en_CA | 106       | 2.75%   |
| en_IN | 98        | 2.55%   |
| pl_PL | 93        | 2.42%   |
| en_AU | 72        | 1.87%   |
| nl_NL | 66        | 1.71%   |
| es_MX | 53        | 1.38%   |
| ru_RU | 48        | 1.25%   |
| en_ZA | 37        | 0.96%   |
| pt_PT | 32        | 0.83%   |
| cs_CZ | 32        | 0.83%   |
| es_AR | 30        | 0.78%   |
| hu_HU | 27        | 0.7%    |
| sv_SE | 25        | 0.65%   |
| tr_TR | 23        | 0.6%    |
| en_NZ | 23        | 0.6%    |
| nl_BE | 20        | 0.52%   |
| es_CL | 19        | 0.49%   |
| de_CH | 19        | 0.49%   |
| fr_BE | 17        | 0.44%   |
| fr_CA | 14        | 0.36%   |
| de_AT | 14        | 0.36%   |
| es_CO | 13        | 0.34%   |
| ja_JP | 12        | 0.31%   |
| fi_FI | 12        | 0.31%   |
| el_GR | 11        | 0.29%   |
| nb_NO | 10        | 0.26%   |
| en_PH | 10        | 0.26%   |
| da_DK | 10        | 0.26%   |
| sk_SK | 9         | 0.23%   |
| es_VE | 9         | 0.23%   |
| en_IE | 8         | 0.21%   |
| bg_BG | 8         | 0.21%   |
| ar_EG | 8         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2256      | 58.16%  |
| BIOS | 1623      | 41.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3549      | 91.99%  |
| Tmpfs    | 106       | 2.75%   |
| Zfs      | 72        | 1.87%   |
| Overlay  | 64        | 1.66%   |
| Btrfs    | 41        | 1.06%   |
| Xfs      | 9         | 0.23%   |
| Ext2     | 9         | 0.23%   |
| Ext3     | 6         | 0.16%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3158      | 81.41%  |
| GPT     | 562       | 14.49%  |
| MBR     | 159       | 4.1%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3730      | 97.16%  |
| Yes       | 109       | 2.84%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3463      | 90.16%  |
| Yes       | 378       | 9.84%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 638       | 16.66%  |
| ASUSTek Computer    | 549       | 14.34%  |
| Dell                | 503       | 13.14%  |
| Lenovo              | 499       | 13.03%  |
| Gigabyte Technology | 219       | 5.72%   |
| Acer                | 198       | 5.17%   |
| MSI                 | 184       | 4.81%   |
| Apple               | 140       | 3.66%   |
| ASRock              | 91        | 2.38%   |
| Toshiba             | 87        | 2.27%   |
| Intel               | 64        | 1.67%   |
| Unknown             | 45        | 1.18%   |
| Samsung Electronics | 41        | 1.07%   |
| Sony                | 33        | 0.86%   |
| Google              | 33        | 0.86%   |
| Fujitsu             | 30        | 0.78%   |
| Microsoft           | 26        | 0.68%   |
| HUAWEI              | 25        | 0.65%   |
| Biostar             | 20        | 0.52%   |
| Pegatron            | 19        | 0.5%    |
| Packard Bell        | 19        | 0.5%    |
| Positivo            | 18        | 0.47%   |
| AZW                 | 17        | 0.44%   |
| Medion              | 16        | 0.42%   |
| Foxconn             | 15        | 0.39%   |
| Alienware           | 15        | 0.39%   |
| Chuwi               | 11        | 0.29%   |
| AMI                 | 11        | 0.29%   |
| Notebook            | 9         | 0.24%   |
| Fujitsu Siemens     | 8         | 0.21%   |
| Multilaser          | 7         | 0.18%   |
| GPU Company         | 7         | 0.18%   |
| Gateway             | 6         | 0.16%   |
| BESSTAR Tech        | 6         | 0.16%   |
| Thomson             | 5         | 0.13%   |
| LG Electronics      | 5         | 0.13%   |
| ECS                 | 5         | 0.13%   |
| TrekStor            | 4         | 0.1%    |
| Semp Toshiba        | 4         | 0.1%    |
| RCA                 | 4         | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Unknown                    | 57        | 1.49%   |
| ASUS All Series            | 32        | 0.84%   |
| HP Notebook                | 25        | 0.65%   |
| HP Pavilion Notebook       | 14        | 0.37%   |
| HP 15                      | 13        | 0.34%   |
| Dell OptiPlex 7010         | 13        | 0.34%   |
| MSI MS-7817                | 9         | 0.24%   |
| HP Pavilion dv7            | 9         | 0.24%   |
| HP Pavilion dv6            | 9         | 0.24%   |
| HP Pavilion 15             | 9         | 0.24%   |
| Dell OptiPlex 790          | 8         | 0.21%   |
| Apple MacBookPro8,1        | 8         | 0.21%   |
| Apple iMac12,2             | 8         | 0.21%   |
| Apple iMac12,1             | 8         | 0.21%   |
| Microsoft Surface Pro      | 7         | 0.18%   |
| Lenovo MIIX 320-10ICR 80XF | 7         | 0.18%   |
| Intel H61                  | 7         | 0.18%   |
| Dell OptiPlex 780          | 7         | 0.18%   |
| Dell OptiPlex 380          | 7         | 0.18%   |
| ASUS TUF Gaming X570-PLUS  | 7         | 0.18%   |
| ASUS M5A78L-M/USB3         | 7         | 0.18%   |
| Apple MacBookPro12,1       | 7         | 0.18%   |
| Apple iMac10,1             | 7         | 0.18%   |
| MSI MS-7C02                | 6         | 0.16%   |
| Microsoft Surface Pro 4    | 6         | 0.16%   |
| HP Pavilion g7             | 6         | 0.16%   |
| Gigabyte B450 AORUS M      | 6         | 0.16%   |
| Gigabyte A320M-S2H         | 6         | 0.16%   |
| Dell OptiPlex 3010         | 6         | 0.16%   |
| Dell Latitude E6540        | 6         | 0.16%   |
| Dell Latitude E6520        | 6         | 0.16%   |
| Dell Inspiron 15-3567      | 6         | 0.16%   |
| ASUS M5A97 R2.0            | 6         | 0.16%   |
| MSI MS-7C37                | 5         | 0.13%   |
| HP ProBook 640 G1          | 5         | 0.13%   |
| HP Pavilion g6             | 5         | 0.13%   |
| HP EliteDesk 800 G1 SFF    | 5         | 0.13%   |
| HP EliteBook 2570p         | 5         | 0.13%   |
| HP Compaq Pro 6300 SFF     | 5         | 0.13%   |
| GPU Company GWTC116-2      | 5         | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 162       | 4.23%   |
| Acer Aspire           | 133       | 3.47%   |
| Dell Latitude         | 132       | 3.45%   |
| Dell Inspiron         | 131       | 3.42%   |
| HP Pavilion           | 126       | 3.29%   |
| Lenovo IdeaPad        | 122       | 3.19%   |
| Dell OptiPlex         | 96        | 2.51%   |
| Toshiba Satellite     | 70        | 1.83%   |
| HP EliteBook          | 67        | 1.75%   |
| HP Compaq             | 58        | 1.51%   |
| ASUS ROG              | 57        | 1.49%   |
| Unknown               | 57        | 1.49%   |
| HP ProBook            | 53        | 1.38%   |
| ASUS PRIME            | 49        | 1.28%   |
| HP Laptop             | 47        | 1.23%   |
| Lenovo ThinkCentre    | 44        | 1.15%   |
| ASUS TUF              | 41        | 1.07%   |
| Dell Precision        | 38        | 0.99%   |
| ASUS VivoBook         | 38        | 0.99%   |
| Lenovo Yoga           | 33        | 0.86%   |
| Dell XPS              | 33        | 0.86%   |
| ASUS All              | 32        | 0.84%   |
| HP ENVY               | 30        | 0.78%   |
| Dell Vostro           | 30        | 0.78%   |
| Microsoft Surface     | 26        | 0.68%   |
| HP Notebook           | 25        | 0.65%   |
| HP EliteDesk          | 23        | 0.6%    |
| HP Stream             | 19        | 0.5%    |
| ASUS ZenBook          | 16        | 0.42%   |
| Apple iMac12          | 16        | 0.42%   |
| Packard Bell EasyNote | 15        | 0.39%   |
| HP 15                 | 15        | 0.39%   |
| ASUS ASUS             | 15        | 0.39%   |
| Lenovo Legion         | 14        | 0.37%   |
| HP OMEN               | 14        | 0.37%   |
| HP ProDesk            | 13        | 0.34%   |
| Gigabyte B450         | 13        | 0.34%   |
| Fujitsu ESPRIMO       | 13        | 0.34%   |
| Lenovo MIIX           | 11        | 0.29%   |
| Lenovo IdeaCentre     | 11        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 320       | 8.36%   |
| 2021    | 319       | 8.33%   |
| 2013    | 315       | 8.23%   |
| 2011    | 314       | 8.2%    |
| 2018    | 297       | 7.76%   |
| 2020    | 285       | 7.44%   |
| 2019    | 269       | 7.03%   |
| 2014    | 260       | 6.79%   |
| 2017    | 248       | 6.48%   |
| 2010    | 212       | 5.54%   |
| 2016    | 205       | 5.35%   |
| 2015    | 193       | 5.04%   |
| 2008    | 156       | 4.07%   |
| 2009    | 138       | 3.6%    |
| 2022    | 116       | 3.03%   |
| 2007    | 92        | 2.4%    |
| 2023    | 55        | 1.44%   |
| 2006    | 25        | 0.65%   |
| 2005    | 6         | 0.16%   |
| Unknown | 4         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2107      | 55.03%  |
| Desktop     | 1389      | 36.28%  |
| Convertible | 101       | 2.64%   |
| All in one  | 92        | 2.4%    |
| Tablet      | 67        | 1.75%   |
| Mini pc     | 63        | 1.65%   |
| Server      | 10        | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3380      | 87.45%  |
| Enabled  | 485       | 12.55%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3792      | 99.03%  |
| Yes  | 37        | 0.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1064      | 27.51%  |
| 3.01-4.0        | 823       | 21.28%  |
| 16.01-24.0      | 672       | 17.37%  |
| 8.01-16.0       | 641       | 16.57%  |
| 32.01-64.0      | 303       | 7.83%   |
| 1.01-2.0        | 173       | 4.47%   |
| 64.01-256.0     | 77        | 1.99%   |
| 24.01-32.0      | 53        | 1.37%   |
| 2.01-3.0        | 53        | 1.37%   |
| 0.51-1.0        | 8         | 0.21%   |
| More than 256.0 | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1535      | 36.67%  |
| 2.01-3.0   | 1383      | 33.04%  |
| 3.01-4.0   | 590       | 14.09%  |
| 4.01-8.0   | 499       | 11.92%  |
| 8.01-16.0  | 83        | 1.98%   |
| 0.51-1.0   | 77        | 1.84%   |
| 16.01-24.0 | 11        | 0.26%   |
| 24.01-32.0 | 5         | 0.12%   |
| 32.01-64.0 | 2         | 0.05%   |
| 0.01-0.5   | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2492      | 63.64%  |
| 2      | 950       | 24.26%  |
| 3      | 229       | 5.85%   |
| 4      | 117       | 2.99%   |
| 5      | 55        | 1.4%    |
| 6      | 33        | 0.84%   |
| 0      | 15        | 0.38%   |
| 7      | 12        | 0.31%   |
| 8      | 9         | 0.23%   |
| 51     | 1         | 0.03%   |
| 30     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |
| 9      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2216      | 57.53%  |
| Yes       | 1636      | 42.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3190      | 83.12%  |
| No        | 648       | 16.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3059      | 79.54%  |
| No        | 787       | 20.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2297      | 59.42%  |
| No        | 1569      | 40.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 889       | 23.13%  |
| Germany      | 411       | 10.69%  |
| Brazil       | 241       | 6.27%   |
| UK           | 235       | 6.12%   |
| Canada       | 134       | 3.49%   |
| Italy        | 133       | 3.46%   |
| France       | 131       | 3.41%   |
| Spain        | 128       | 3.33%   |
| Netherlands  | 110       | 2.86%   |
| India        | 102       | 2.65%   |
| Poland       | 90        | 2.34%   |
| Australia    | 74        | 1.93%   |
| Mexico       | 71        | 1.85%   |
| Belgium      | 52        | 1.35%   |
| Russia       | 47        | 1.22%   |
| Sweden       | 45        | 1.17%   |
| South Africa | 41        | 1.07%   |
| Portugal     | 40        | 1.04%   |
| Switzerland  | 39        | 1.01%   |
| Austria      | 39        | 1.01%   |
| Argentina    | 39        | 1.01%   |
| Czechia      | 36        | 0.94%   |
| Turkey       | 35        | 0.91%   |
| Hungary      | 33        | 0.86%   |
| Greece       | 30        | 0.78%   |
| Romania      | 29        | 0.75%   |
| Norway       | 29        | 0.75%   |
| New Zealand  | 25        | 0.65%   |
| Japan        | 23        | 0.6%    |
| Chile        | 23        | 0.6%    |
| Finland      | 22        | 0.57%   |
| Denmark      | 22        | 0.57%   |
| Egypt        | 21        | 0.55%   |
| Colombia     | 21        | 0.55%   |
| Indonesia    | 19        | 0.49%   |
| Serbia       | 17        | 0.44%   |
| Bulgaria     | 16        | 0.42%   |
| Ireland      | 14        | 0.36%   |
| Slovakia     | 13        | 0.34%   |
| Malaysia     | 13        | 0.34%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 36        | 0.9%    |
| Munich            | 26        | 0.65%   |
| Madrid            | 22        | 0.55%   |
| Rome              | 21        | 0.52%   |
| Athens            | 21        | 0.52%   |
| Vienna            | 20        | 0.5%    |
| Sydney            | 20        | 0.5%    |
| Rio de Janeiro    | 20        | 0.5%    |
| New York          | 20        | 0.5%    |
| Hamburg           | 19        | 0.47%   |
| Sao Paulo         | 18        | 0.45%   |
| Milan             | 17        | 0.42%   |
| Amsterdam         | 16        | 0.4%    |
| Montreal          | 15        | 0.37%   |
| Denver            | 15        | 0.37%   |
| Dallas            | 15        | 0.37%   |
| Paris             | 14        | 0.35%   |
| Melbourne         | 13        | 0.32%   |
| London            | 13        | 0.32%   |
| Cape Town         | 13        | 0.32%   |
| Johannesburg      | 12        | 0.3%    |
| Delhi             | 12        | 0.3%    |
| Toronto           | 11        | 0.27%   |
| Stockholm         | 11        | 0.27%   |
| Salt Lake City    | 11        | 0.27%   |
| Phoenix           | 11        | 0.27%   |
| Mexico City       | 11        | 0.27%   |
| Istanbul          | 11        | 0.27%   |
| Houston           | 11        | 0.27%   |
| Frankfurt am Main | 11        | 0.27%   |
| Bogotá           | 11        | 0.27%   |
| Bengaluru         | 11        | 0.27%   |
| Auckland          | 11        | 0.27%   |
| Valencia          | 10        | 0.25%   |
| Seattle           | 10        | 0.25%   |
| Perth             | 10        | 0.25%   |
| Moscow            | 10        | 0.25%   |
| Jakarta           | 10        | 0.25%   |
| Helsinki          | 10        | 0.25%   |
| Calgary           | 10        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 789       | 1133   | 14.53%  |
| Samsung Electronics         | 719       | 1034   | 13.24%  |
| WDC                         | 695       | 960    | 12.8%   |
| Toshiba                     | 373       | 476    | 6.87%   |
| Sandisk                     | 335       | 422    | 6.17%   |
| Unknown                     | 325       | 449    | 5.98%   |
| Kingston                    | 290       | 409    | 5.34%   |
| Crucial                     | 195       | 237    | 3.59%   |
| Hitachi                     | 166       | 218    | 3.06%   |
| SK hynix                    | 116       | 134    | 2.14%   |
| Intel                       | 111       | 143    | 2.04%   |
| HGST                        | 90        | 112    | 1.66%   |
| Micron Technology           | 79        | 94     | 1.45%   |
| China                       | 79        | 95     | 1.45%   |
| A-DATA Technology           | 71        | 90     | 1.31%   |
| Apple                       | 66        | 76     | 1.22%   |
| Intenso                     | 46        | 49     | 0.85%   |
| Silicon Motion              | 40        | 52     | 0.74%   |
| KIOXIA                      | 37        | 42     | 0.68%   |
| PNY                         | 36        | 47     | 0.66%   |
| Phison                      | 36        | 42     | 0.66%   |
| Unknown                     | 36        | 40     | 0.66%   |
| SPCC                        | 32        | 46     | 0.59%   |
| Patriot                     | 28        | 37     | 0.52%   |
| Netac                       | 28        | 32     | 0.52%   |
| Micron/Crucial Technology   | 24        | 29     | 0.44%   |
| GOODRAM                     | 24        | 28     | 0.44%   |
| JMicron Technology          | 23        | 28     | 0.42%   |
| Phison Electronics          | 21        | 24     | 0.39%   |
| OCZ                         | 18        | 21     | 0.33%   |
| LITEON                      | 18        | 20     | 0.33%   |
| Lexar                       | 17        | 17     | 0.31%   |
| Team                        | 16        | 19     | 0.29%   |
| Kingston Technology Company | 16        | 20     | 0.29%   |
| KingSpec                    | 16        | 19     | 0.29%   |
| LITEONIT                    | 15        | 17     | 0.28%   |
| Hewlett-Packard             | 15        | 21     | 0.28%   |
| Transcend                   | 14        | 31     | 0.26%   |
| Realtek Semiconductor       | 14        | 15     | 0.26%   |
| MAXIO Technology (Hangzhou) | 14        | 14     | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  64GB                              | 98        | 1.65%   |
| Unknown MMC Card  32GB                              | 93        | 1.56%   |
| Kingston SA400S37240G 240GB SSD                     | 71        | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 51        | 0.86%   |
| Seagate ST500DM002-1BD142 500GB                     | 48        | 0.81%   |
| Seagate ST1000LM035-1RK172 1TB                      | 48        | 0.81%   |
| Toshiba MQ01ABD100 1TB                              | 42        | 0.71%   |
| Unknown MMC Card  128GB                             | 40        | 0.67%   |
| Kingston SA400S37480G 480GB SSD                     | 40        | 0.67%   |
| Crucial CT240BX500SSD1 240GB                        | 40        | 0.67%   |
| Samsung SSD 860 EVO 500GB                           | 38        | 0.64%   |
| Kingston SA400S37120G 120GB SSD                     | 38        | 0.64%   |
| Unknown                                             | 36        | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 33        | 0.55%   |
| Unknown SD/MMC/MS PRO 128GB                         | 31        | 0.52%   |
| Toshiba MQ01ABF050 500GB                            | 31        | 0.52%   |
| Seagate ST500LT012-1DG142 500GB                     | 30        | 0.5%    |
| Seagate ST1000DM010-2EP102 1TB                      | 30        | 0.5%    |
| Samsung SSD 850 EVO 250GB                           | 29        | 0.49%   |
| Toshiba MQ04ABF100 1TB                              | 28        | 0.47%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 26        | 0.44%   |
| Crucial CT500MX500SSD1 500GB                        | 26        | 0.44%   |
| Samsung SSD 850 EVO 500GB                           | 25        | 0.42%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.42%   |
| Samsung NVMe SSD Drive 1TB                          | 25        | 0.42%   |
| Seagate ST9500325AS 500GB                           | 24        | 0.4%    |
| Seagate ST1000DM003-1CH162 1TB                      | 23        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 22        | 0.37%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 22        | 0.37%   |
| Seagate Expansion 1TB                               | 21        | 0.35%   |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.35%   |
| Samsung SSD 870 EVO 1TB                             | 21        | 0.35%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.35%   |
| Crucial CT1000MX500SSD1 1TB                         | 21        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD                    | 20        | 0.34%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 19        | 0.32%   |
| HGST HTS721010A9E630 1TB                            | 19        | 0.32%   |
| Unknown MMC Card  16GB                              | 18        | 0.3%    |
| Toshiba HDWD110 1TB                                 | 18        | 0.3%    |
| SanDisk NVMe SSD Drive 1TB                          | 18        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 778       | 1105   | 36.72%  |
| WDC                 | 596       | 812    | 28.13%  |
| Toshiba             | 289       | 375    | 13.64%  |
| Hitachi             | 166       | 218    | 7.83%   |
| HGST                | 90        | 112    | 4.25%   |
| Samsung Electronics | 87        | 107    | 4.11%   |
| Unknown             | 32        | 39     | 1.51%   |
| Apple               | 29        | 33     | 1.37%   |
| Maxtor              | 13        | 17     | 0.61%   |
| Fujitsu             | 13        | 15     | 0.61%   |
| USB3.0              | 4         | 5      | 0.19%   |
| Hewlett-Packard     | 4         | 7      | 0.19%   |
| Intenso             | 3         | 3      | 0.14%   |
| SSK                 | 2         | 2      | 0.09%   |
| JMicron Technology  | 2         | 2      | 0.09%   |
| XrayDisk            | 1         | 1      | 0.05%   |
| WD MediaMax         | 1         | 1      | 0.05%   |
| TO Exter            | 1         | 1      | 0.05%   |
| TDAS                | 1         | 3      | 0.05%   |
| SABRENT             | 1         | 1      | 0.05%   |
| QUANTUM             | 1         | 1      | 0.05%   |
| LaCie               | 1         | 1      | 0.05%   |
| KESU                | 1         | 1      | 0.05%   |
| HGST HTS            | 1         | 1      | 0.05%   |
| External            | 1         | 1      | 0.05%   |
| ACASIS              | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 359       | 506    | 19.14%  |
| Kingston            | 244       | 330    | 13.01%  |
| Crucial             | 186       | 226    | 9.91%   |
| SanDisk             | 180       | 227    | 9.59%   |
| WDC                 | 80        | 105    | 4.26%   |
| China               | 78        | 94     | 4.16%   |
| A-DATA Technology   | 62        | 81     | 3.3%    |
| Intel               | 42        | 49     | 2.24%   |
| Toshiba             | 39        | 46     | 2.08%   |
| PNY                 | 36        | 47     | 1.92%   |
| Micron Technology   | 33        | 38     | 1.76%   |
| SK hynix            | 32        | 32     | 1.71%   |
| SPCC                | 31        | 45     | 1.65%   |
| Intenso             | 31        | 33     | 1.65%   |
| Apple               | 31        | 35     | 1.65%   |
| Netac               | 28        | 31     | 1.49%   |
| Patriot             | 27        | 36     | 1.44%   |
| GOODRAM             | 22        | 26     | 1.17%   |
| LITEON              | 18        | 20     | 0.96%   |
| OCZ                 | 17        | 20     | 0.91%   |
| Team                | 16        | 19     | 0.85%   |
| Lexar               | 16        | 16     | 0.85%   |
| LITEONIT            | 15        | 17     | 0.8%    |
| KingSpec            | 15        | 18     | 0.8%    |
| Transcend           | 14        | 31     | 0.75%   |
| JMicron Technology  | 13        | 15     | 0.69%   |
| Unknown             | 12        | 15     | 0.64%   |
| Apacer              | 11        | 14     | 0.59%   |
| Hewlett-Packard     | 10        | 13     | 0.53%   |
| Gigabyte Technology | 9         | 10     | 0.48%   |
| Fanxiang            | 7         | 8      | 0.37%   |
| Leven               | 6         | 7      | 0.32%   |
| ASMT                | 6         | 6      | 0.32%   |
| Verbatim            | 5         | 5      | 0.27%   |
| Teclast             | 5         | 5      | 0.27%   |
| Plextor             | 5         | 6      | 0.27%   |
| Phison              | 5         | 7      | 0.27%   |
| Mushkin             | 5         | 5      | 0.27%   |
| FORESEE             | 5         | 6      | 0.27%   |
| Super Talent        | 4         | 5      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1820      | 2865   | 37.02%  |
| SSD     | 1676      | 2411   | 34.09%  |
| NVMe    | 1003      | 1384   | 20.4%   |
| MMC     | 304       | 411    | 6.18%   |
| Unknown | 113       | 141    | 2.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2960      | 5106   | 66.04%  |
| NVMe | 997       | 1368   | 22.24%  |
| MMC  | 304       | 411    | 6.78%   |
| SAS  | 221       | 327    | 4.93%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2190      | 3219   | 60.8%   |
| 0.51-1.0   | 1006      | 1410   | 27.93%  |
| 1.01-2.0   | 247       | 350    | 6.86%   |
| 3.01-4.0   | 65        | 134    | 1.8%    |
| 4.01-10.0  | 51        | 75     | 1.42%   |
| 2.01-3.0   | 35        | 60     | 0.97%   |
| 10.01-20.0 | 7         | 27     | 0.19%   |
| 20.01-50.0 | 1         | 1      | 0.03%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1285      | 32.38%  |
| 251-500        | 971       | 24.46%  |
| 501-1000       | 598       | 15.07%  |
| 51-100         | 328       | 8.26%   |
| 1001-2000      | 235       | 5.92%   |
| 21-50          | 190       | 4.79%   |
| More than 3000 | 141       | 3.55%   |
| 1-20           | 95        | 2.39%   |
| 2001-3000      | 76        | 1.91%   |
| Unknown        | 50        | 1.26%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1526      | 36.73%  |
| 21-50          | 1184      | 28.5%   |
| 51-100         | 509       | 12.25%  |
| 101-250        | 404       | 9.72%   |
| 251-500        | 215       | 5.17%   |
| 501-1000       | 128       | 3.08%   |
| More than 3000 | 66        | 1.59%   |
| 1001-2000      | 53        | 1.28%   |
| Unknown        | 50        | 1.2%    |
| 2001-3000      | 20        | 0.48%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD100 1TB                   | 4         | 4      | 3.48%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.61%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.61%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 2         | 2      | 1.74%   |
| Toshiba MQ02ABD100H 1TB                  | 2         | 2      | 1.74%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.74%   |
| Seagate ST9500420AS 500GB                | 2         | 2      | 1.74%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 1.74%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.74%   |
| Seagate ST500DM002-1BD142 500GB          | 2         | 2      | 1.74%   |
| Seagate ST1000LM048-2E7172 1TB           | 2         | 2      | 1.74%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 1.74%   |
| Kingston SUV400S37240G 240GB SSD         | 2         | 2      | 1.74%   |
| HGST HTS545050A7E380 500GB               | 2         | 3      | 1.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD         | 1         | 1      | 0.87%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.87%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.87%   |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 0.87%   |
| WDC WD5000BEVT-24A0RT0 500GB             | 1         | 1      | 0.87%   |
| WDC WD3200AAKS-22B3A0 320GB              | 1         | 1      | 0.87%   |
| WDC WD3200AAJS-00L7A0 320GB              | 1         | 1      | 0.87%   |
| WDC WD2500AAJS-00B4A0 250GB              | 1         | 1      | 0.87%   |
| WDC WD20EZRX-22D8PB0 2TB                 | 1         | 1      | 0.87%   |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 1      | 0.87%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.87%   |
| WDC WD10SPZX-75Z10T2 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10JPVT-55A1YT0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD10EZEX-21M2NA0 1TB                 | 1         | 2      | 0.87%   |
| WDC WD10EURX-63FH1Y0 1TB                 | 1         | 1      | 0.87%   |
| WDC WD Green 2.5 1000GB                  | 1         | 1      | 0.87%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.87%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.87%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.87%   |
| Toshiba MQ01ABF050 500GB                 | 1         | 1      | 0.87%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 1      | 0.87%   |
| Toshiba MK8046GSX 80GB                   | 1         | 1      | 0.87%   |
| Toshiba MK3265GSX 320GB                  | 1         | 1      | 0.87%   |
| Toshiba MG03ACA200 2TB                   | 1         | 1      | 0.87%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 0.87%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 39     | 33.33%  |
| WDC                 | 19        | 20     | 16.67%  |
| Toshiba             | 15        | 15     | 13.16%  |
| HGST                | 11        | 12     | 9.65%   |
| Kingston            | 6         | 6      | 5.26%   |
| Samsung Electronics | 5         | 5      | 4.39%   |
| Hitachi             | 3         | 3      | 2.63%   |
| SK hynix            | 2         | 2      | 1.75%   |
| Intel               | 2         | 2      | 1.75%   |
| A-DATA Technology   | 2         | 2      | 1.75%   |
| Teclast             | 1         | 1      | 0.88%   |
| Silicon Motion      | 1         | 1      | 0.88%   |
| POLION              | 1         | 1      | 0.88%   |
| OCZ                 | 1         | 1      | 0.88%   |
| Netac               | 1         | 1      | 0.88%   |
| Maxtor              | 1         | 1      | 0.88%   |
| LITEONIT            | 1         | 1      | 0.88%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |
| Drevo               | 1         | 1      | 0.88%   |
| China               | 1         | 1      | 0.88%   |
| Unknown             | 1         | 1      | 0.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 39     | 44.71%  |
| WDC                 | 17        | 18     | 20%     |
| Toshiba             | 12        | 12     | 14.12%  |
| HGST                | 11        | 12     | 12.94%  |
| Samsung Electronics | 3         | 3      | 3.53%   |
| Hitachi             | 3         | 3      | 3.53%   |
| Maxtor              | 1         | 1      | 1.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 81        | 88     | 73.64%  |
| SSD  | 25        | 25     | 22.73%  |
| NVMe | 4         | 4      | 3.64%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3391      | 6362   | 85.59%  |
| Works    | 460       | 730    | 11.61%  |
| Malfunc  | 108       | 117    | 2.73%   |
| Failed   | 2         | 2      | 0.05%   |
| Fixed    | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2599      | 56.71%  |
| AMD                              | 714       | 15.58%  |
| Samsung Electronics              | 342       | 7.46%   |
| SanDisk                          | 175       | 3.82%   |
| SK hynix                         | 79        | 1.72%   |
| Kingston Technology Company      | 69        | 1.51%   |
| Nvidia                           | 66        | 1.44%   |
| ASMedia Technology               | 60        | 1.31%   |
| Phison Electronics               | 58        | 1.27%   |
| Micron Technology                | 47        | 1.03%   |
| Toshiba America Info Systems     | 45        | 0.98%   |
| Silicon Motion                   | 45        | 0.98%   |
| KIOXIA                           | 39        | 0.85%   |
| JMicron Technology               | 39        | 0.85%   |
| Marvell Technology Group         | 34        | 0.74%   |
| Micron/Crucial Technology        | 33        | 0.72%   |
| ADATA Technology                 | 22        | 0.48%   |
| MAXIO Technology (Hangzhou)      | 16        | 0.35%   |
| Realtek Semiconductor            | 15        | 0.33%   |
| VIA Technologies                 | 11        | 0.24%   |
| Seagate Technology               | 9         | 0.2%    |
| Silicon Image                    | 8         | 0.17%   |
| Union Memory (Shenzhen)          | 6         | 0.13%   |
| Solid State Storage Technology   | 6         | 0.13%   |
| Lite-On Technology               | 6         | 0.13%   |
| Apple                            | 5         | 0.11%   |
| Shenzhen Longsys Electronics     | 4         | 0.09%   |
| LSI Logic / Symbios Logic        | 4         | 0.09%   |
| INNOGRIT                         | 4         | 0.09%   |
| Broadcom / LSI                   | 4         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| OCZ Technology Group             | 2         | 0.04%   |
| Netac Technology                 | 2         | 0.04%   |
| Lenovo                           | 2         | 0.04%   |
| TenaFe                           | 1         | 0.02%   |
| Nextorage                        | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 481       | 9.11%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 194       | 3.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 191       | 3.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 187       | 3.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 142       | 2.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 134       | 2.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 131       | 2.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 107       | 2.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 98        | 1.86%   |
| Intel Volume Management Device NVMe RAID Controller                            | 88        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 87        | 1.65%   |
| AMD 400 Series Chipset SATA Controller                                         | 87        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 85        | 1.61%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 81        | 1.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 79        | 1.5%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 75        | 1.42%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 73        | 1.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 72        | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 71        | 1.34%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 70        | 1.33%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 70        | 1.33%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 69        | 1.31%   |
| Intel SATA Controller [RAID mode]                                              | 65        | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 61        | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 56        | 1.06%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 54        | 1.02%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 54        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 52        | 0.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 51        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 48        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 48        | 0.91%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 45        | 0.85%   |
| AMD 500 Series Chipset SATA Controller                                         | 45        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 42        | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 42        | 0.8%    |
| Intel Tiger Lake-LP SATA Controller                                            | 40        | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 38        | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 35        | 0.66%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 35        | 0.66%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 35        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2837      | 60.3%   |
| NVMe | 997       | 21.19%  |
| IDE  | 518       | 11.01%  |
| RAID | 342       | 7.27%   |
| SAS  | 8         | 0.17%   |
| SCSI | 3         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2993      | 78.17%  |
| AMD    | 836       | 21.83%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 52        | 1.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 41        | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 40        | 1.04%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 0.89%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 34        | 0.89%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 28        | 0.73%   |
| AMD Ryzen 5 3600 6-Core Processor             | 28        | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 27        | 0.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz              | 27        | 0.7%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 25        | 0.65%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 25        | 0.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 24        | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 24        | 0.63%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 23        | 0.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 22        | 0.57%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 21        | 0.55%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 0.55%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.55%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 21        | 0.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.52%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 20        | 0.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 0.5%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 18        | 0.47%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 17        | 0.44%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 17        | 0.44%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 17        | 0.44%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 16        | 0.42%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.39%   |
| Intel Core i7-6700 CPU @ 3.40GHz              | 15        | 0.39%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 15        | 0.39%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 15        | 0.39%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 15        | 0.39%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 15        | 0.39%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 15        | 0.39%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 15        | 0.39%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 15        | 0.39%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 15        | 0.39%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 14        | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 887       | 23.15%  |
| Intel Core i7           | 548       | 14.3%   |
| Intel Core i3           | 355       | 9.26%   |
| Intel Celeron           | 265       | 6.92%   |
| Other                   | 232       | 6.05%   |
| AMD Ryzen 5             | 200       | 5.22%   |
| Intel Core 2 Duo        | 186       | 4.85%   |
| Intel Atom              | 124       | 3.24%   |
| AMD Ryzen 7             | 123       | 3.21%   |
| Intel Pentium           | 111       | 2.9%    |
| Intel Xeon              | 81        | 2.11%   |
| AMD Ryzen 9             | 58        | 1.51%   |
| AMD FX                  | 56        | 1.46%   |
| Intel Pentium Dual-Core | 53        | 1.38%   |
| AMD A6                  | 47        | 1.23%   |
| AMD Ryzen 3             | 37        | 0.97%   |
| AMD A10                 | 35        | 0.91%   |
| Intel Core 2 Quad       | 34        | 0.89%   |
| AMD A8                  | 34        | 0.89%   |
| AMD A4                  | 33        | 0.86%   |
| Intel Pentium Dual      | 32        | 0.84%   |
| AMD Athlon II X2        | 25        | 0.65%   |
| Intel Core 2            | 21        | 0.55%   |
| AMD Phenom II X4        | 18        | 0.47%   |
| AMD E1                  | 17        | 0.44%   |
| Intel Pentium Silver    | 16        | 0.42%   |
| Intel Core i9           | 15        | 0.39%   |
| AMD Athlon 64 X2        | 13        | 0.34%   |
| Intel Core M            | 12        | 0.31%   |
| Intel Pentium Gold      | 11        | 0.29%   |
| AMD Phenom II X6        | 11        | 0.29%   |
| AMD E                   | 11        | 0.29%   |
| AMD Athlon              | 11        | 0.29%   |
| AMD Turion 64 X2 Mobile | 8         | 0.21%   |
| Intel Pentium 4         | 7         | 0.18%   |
| AMD E2                  | 7         | 0.18%   |
| AMD Athlon II X4        | 7         | 0.18%   |
| AMD Athlon II           | 6         | 0.16%   |
| Intel Core m5           | 5         | 0.13%   |
| AMD Ryzen 7 PRO         | 5         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1773      | 46.26%  |
| 4      | 1379      | 35.98%  |
| 6      | 291       | 7.59%   |
| 8      | 202       | 5.27%   |
| 1      | 52        | 1.36%   |
| 12     | 47        | 1.23%   |
| 10     | 25        | 0.65%   |
| 16     | 24        | 0.63%   |
| 3      | 22        | 0.57%   |
| 14     | 12        | 0.31%   |
| 24     | 3         | 0.08%   |
| 28     | 2         | 0.05%   |
| 40     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3813      | 99.58%  |
| 2      | 16        | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2310      | 60.31%  |
| 1      | 1520      | 39.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3829      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 290       | 7.46%   |
| 0x306a9    | 283       | 7.28%   |
| Unknown    | 278       | 7.15%   |
| 0x306c3    | 225       | 5.79%   |
| 0x1067a    | 182       | 4.68%   |
| 0x40651    | 111       | 2.85%   |
| 0x806c1    | 104       | 2.67%   |
| 0x406e3    | 99        | 2.55%   |
| 0x806e9    | 95        | 2.44%   |
| 0x20655    | 94        | 2.42%   |
| 0x306d4    | 89        | 2.29%   |
| 0x506e3    | 83        | 2.13%   |
| 0x30678    | 83        | 2.13%   |
| 0x406c4    | 81        | 2.08%   |
| 0x906ea    | 71        | 1.83%   |
| 0x806ec    | 71        | 1.83%   |
| 0x806ea    | 71        | 1.83%   |
| 0x906e9    | 63        | 1.62%   |
| 0x706a8    | 62        | 1.59%   |
| 0x6fd      | 56        | 1.44%   |
| 0x08701021 | 51        | 1.31%   |
| 0x08108109 | 48        | 1.23%   |
| 0x506c9    | 45        | 1.16%   |
| 0x706e5    | 44        | 1.13%   |
| 0x10676    | 40        | 1.03%   |
| 0x20652    | 39        | 1%      |
| 0x010000c8 | 39        | 1%      |
| 0x06000852 | 37        | 0.95%   |
| 0x406c3    | 33        | 0.85%   |
| 0x6fb      | 31        | 0.8%    |
| 0x0a50000c | 31        | 0.8%    |
| 0x06001119 | 28        | 0.72%   |
| 0x0800820d | 27        | 0.69%   |
| 0x07030105 | 26        | 0.67%   |
| 0x06006705 | 26        | 0.67%   |
| 0x08600106 | 25        | 0.64%   |
| 0xa0655    | 24        | 0.62%   |
| 0xa0653    | 24        | 0.62%   |
| 0x0a50000d | 23        | 0.59%   |
| 0x706a1    | 22        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 455       | 11.88%  |
| Haswell          | 369       | 9.63%   |
| SandyBridge      | 314       | 8.2%    |
| IvyBridge        | 305       | 7.96%   |
| Penryn           | 229       | 5.98%   |
| Silvermont       | 213       | 5.56%   |
| Skylake          | 191       | 4.99%   |
| Westmere         | 145       | 3.78%   |
| Core             | 126       | 3.29%   |
| Zen 2            | 122       | 3.18%   |
| TigerLake        | 118       | 3.08%   |
| Zen 3            | 110       | 2.87%   |
| Zen+             | 100       | 2.61%   |
| Unknown          | 96        | 2.51%   |
| Broadwell        | 95        | 2.48%   |
| Goldmont plus    | 87        | 2.27%   |
| K10              | 86        | 2.24%   |
| CometLake        | 76        | 1.98%   |
| Piledriver       | 72        | 1.88%   |
| IceLake          | 72        | 1.88%   |
| Excavator        | 66        | 1.72%   |
| Zen              | 53        | 1.38%   |
| Goldmont         | 48        | 1.25%   |
| Puma             | 41        | 1.07%   |
| Alderlake Hybrid | 38        | 0.99%   |
| Nehalem          | 34        | 0.89%   |
| K8 Hammer        | 28        | 0.73%   |
| Jaguar           | 26        | 0.68%   |
| Bobcat           | 21        | 0.55%   |
| K10 Llano        | 18        | 0.47%   |
| Steamroller      | 16        | 0.42%   |
| Bonnell          | 16        | 0.42%   |
| Tremont          | 15        | 0.39%   |
| Bulldozer        | 15        | 0.39%   |
| NetBurst         | 10        | 0.26%   |
| K8 & K10 hybrid  | 5         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2341      | 53.25%  |
| Nvidia                           | 1042      | 23.7%   |
| AMD                              | 997       | 22.68%  |
| Matrox Electronics Systems       | 6         | 0.14%   |
| VIA Technologies                 | 4         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.07%   |
| ASPEED Technology                | 2         | 0.05%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 239       | 5.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 178       | 3.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 116       | 2.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 112       | 2.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 95        | 2.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 95        | 2.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 95        | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 90        | 1.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 87        | 1.93%   |
| Intel HD Graphics 620                                                                    | 80        | 1.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 76        | 1.68%   |
| Intel UHD Graphics 620                                                                   | 71        | 1.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 70        | 1.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 69        | 1.53%   |
| Intel HD Graphics 5500                                                                   | 56        | 1.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 53        | 1.17%   |
| Intel HD Graphics 630                                                                    | 51        | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 1.11%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 48        | 1.06%   |
| Intel HD Graphics 530                                                                    | 48        | 1.06%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 47        | 1.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 43        | 0.95%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 0.95%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 41        | 0.91%   |
| Intel HD Graphics 500                                                                    | 41        | 0.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 40        | 0.89%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 37        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 35        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 35        | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 35        | 0.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 34        | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 32        | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 32        | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 32        | 0.71%   |
| AMD Lucienne                                                                             | 31        | 0.69%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 27        | 0.6%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 26        | 0.58%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 24        | 0.53%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 23        | 0.51%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 1850      | 48.08%  |
| 1 x AMD              | 800       | 20.79%  |
| 1 x Nvidia           | 633       | 16.45%  |
| Intel + Nvidia       | 337       | 8.76%   |
| Intel + AMD          | 94        | 2.44%   |
| 2 x AMD              | 52        | 1.35%   |
| AMD + Nvidia         | 52        | 1.35%   |
| 2 x Nvidia           | 7         | 0.18%   |
| Other                | 6         | 0.16%   |
| 1 x VIA              | 4         | 0.1%    |
| 1 x Matrox           | 4         | 0.1%    |
| 1 x SiS              | 3         | 0.08%   |
| 1 x ASPEED           | 2         | 0.05%   |
| 2 x Intel            | 1         | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| Nvidia + Matrox      | 1         | 0.03%   |
| AMD + Matrox         | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3104      | 80.54%  |
| Proprietary | 614       | 15.93%  |
| Unknown     | 136       | 3.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2323      | 59.63%  |
| 0.01-0.5   | 462       | 11.86%  |
| 1.01-2.0   | 360       | 9.24%   |
| 0.51-1.0   | 313       | 8.03%   |
| 3.01-4.0   | 179       | 4.59%   |
| 7.01-8.0   | 124       | 3.18%   |
| 5.01-6.0   | 55        | 1.41%   |
| 8.01-16.0  | 43        | 1.1%    |
| 2.01-3.0   | 33        | 0.85%   |
| 16.01-24.0 | 4         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 494       | 12.7%   |
| AU Optronics            | 458       | 11.77%  |
| BOE                     | 349       | 8.97%   |
| Chimei Innolux          | 341       | 8.76%   |
| LG Display              | 331       | 8.51%   |
| Dell                    | 186       | 4.78%   |
| Goldstar                | 174       | 4.47%   |
| Hewlett-Packard         | 140       | 3.6%    |
| Apple                   | 121       | 3.11%   |
| Acer                    | 111       | 2.85%   |
| AOC                     | 89        | 2.29%   |
| Philips                 | 87        | 2.24%   |
| Lenovo                  | 71        | 1.82%   |
| Ancor Communications    | 66        | 1.7%    |
| Chi Mei Optoelectronics | 65        | 1.67%   |
| BenQ                    | 62        | 1.59%   |
| Sharp                   | 54        | 1.39%   |
| Sony                    | 32        | 0.82%   |
| LG Philips              | 32        | 0.82%   |
| LG Electronics          | 31        | 0.8%    |
| PANDA                   | 29        | 0.75%   |
| InfoVision              | 29        | 0.75%   |
| Unknown                 | 28        | 0.72%   |
| ViewSonic               | 27        | 0.69%   |
| Unknown                 | 25        | 0.64%   |
| Vizio                   | 23        | 0.59%   |
| ASUSTek Computer        | 22        | 0.57%   |
| Iiyama                  | 21        | 0.54%   |
| Fujitsu Siemens         | 16        | 0.41%   |
| Sceptre Tech            | 13        | 0.33%   |
| Panasonic               | 13        | 0.33%   |
| Eizo                    | 13        | 0.33%   |
| Toshiba                 | 12        | 0.31%   |
| NEC Computers           | 12        | 0.31%   |
| CPT                     | 12        | 0.31%   |
| MSI                     | 11        | 0.28%   |
| HPN                     | 10        | 0.26%   |
| HannStar                | 9         | 0.23%   |
| FUS                     | 7         | 0.18%   |
| Microstep               | 6         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 28        | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 21        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 19        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.45%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 17        | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 16        | 0.4%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 15        | 0.37%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.37%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 14        | 0.35%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 14        | 0.35%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 13        | 0.32%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 0.3%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 12        | 0.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.3%    |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch             | 11        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.27%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 10        | 0.25%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 10        | 0.25%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 9         | 0.22%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.22%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 9         | 0.22%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 9         | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 8         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 8         | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 8         | 0.2%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 8         | 0.2%    |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                         | 8         | 0.2%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 7         | 0.17%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 7         | 0.17%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 7         | 0.17%   |
| Apple iMac APPA007 2560x1440 597x336mm 27.0-inch                         | 7         | 0.17%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.15%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch    | 6         | 0.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1447      | 38.19%  |
| 1366x768 (WXGA)    | 934       | 24.65%  |
| 1600x900 (HD+)     | 198       | 5.23%   |
| 3840x2160 (4K)     | 197       | 5.2%    |
| 2560x1440 (QHD)    | 112       | 2.96%   |
| 1280x800 (WXGA)    | 107       | 2.82%   |
| 1680x1050 (WSXGA+) | 105       | 2.77%   |
| 1440x900 (WXGA+)   | 103       | 2.72%   |
| 1280x1024 (SXGA)   | 93        | 2.45%   |
| Unknown            | 68        | 1.79%   |
| 1920x1200 (WUXGA)  | 58        | 1.53%   |
| 1360x768           | 41        | 1.08%   |
| 3440x1440          | 37        | 0.98%   |
| 3840x1080          | 34        | 0.9%    |
| 2560x1600          | 30        | 0.79%   |
| 2560x1080          | 30        | 0.79%   |
| 2736x1824          | 18        | 0.48%   |
| 1920x540           | 17        | 0.45%   |
| 2880x1800          | 12        | 0.32%   |
| 2160x1440          | 12        | 0.32%   |
| 3200x1800 (QHD+)   | 10        | 0.26%   |
| 2256x1504          | 10        | 0.26%   |
| 1024x768 (XGA)     | 9         | 0.24%   |
| 1600x1200          | 8         | 0.21%   |
| 3840x2400          | 7         | 0.18%   |
| 1280x720 (HD)      | 7         | 0.18%   |
| 1024x600           | 5         | 0.13%   |
| 5760x1080          | 4         | 0.11%   |
| 3840x1600          | 4         | 0.11%   |
| 1920x1280          | 4         | 0.11%   |
| 4480x1440          | 3         | 0.08%   |
| 3600x1080          | 3         | 0.08%   |
| 2880x1920          | 3         | 0.08%   |
| 1920x515           | 3         | 0.08%   |
| 7680x2160          | 2         | 0.05%   |
| 5760x2160          | 2         | 0.05%   |
| 5120x1440          | 2         | 0.05%   |
| 4480x1600          | 2         | 0.05%   |
| 4480x1080          | 2         | 0.05%   |
| 3360x1080          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 984       | 25.53%  |
| 13      | 376       | 9.75%   |
| Unknown | 303       | 7.86%   |
| 14      | 290       | 7.52%   |
| 17      | 224       | 5.81%   |
| 27      | 215       | 5.58%   |
| 24      | 190       | 4.93%   |
| 21      | 180       | 4.67%   |
| 23      | 169       | 4.38%   |
| 19      | 102       | 2.65%   |
| 11      | 95        | 2.46%   |
| 31      | 89        | 2.31%   |
| 12      | 86        | 2.23%   |
| 20      | 82        | 2.13%   |
| 18      | 79        | 2.05%   |
| 22      | 67        | 1.74%   |
| 34      | 50        | 1.3%    |
| 16      | 30        | 0.78%   |
| 40      | 28        | 0.73%   |
| 54      | 23        | 0.6%    |
| 84      | 22        | 0.57%   |
| 72      | 18        | 0.47%   |
| 32      | 16        | 0.42%   |
| 26      | 15        | 0.39%   |
| 10      | 15        | 0.39%   |
| 25      | 12        | 0.31%   |
| 52      | 8         | 0.21%   |
| 49      | 8         | 0.21%   |
| 48      | 7         | 0.18%   |
| 36      | 7         | 0.18%   |
| 65      | 6         | 0.16%   |
| 28      | 5         | 0.13%   |
| 46      | 4         | 0.1%    |
| 37      | 4         | 0.1%    |
| 29      | 4         | 0.1%    |
| 74      | 3         | 0.08%   |
| 64      | 3         | 0.08%   |
| 58      | 3         | 0.08%   |
| 42      | 3         | 0.08%   |
| 39      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1499      | 39.44%  |
| 501-600        | 542       | 14.26%  |
| 401-500        | 454       | 11.94%  |
| 201-300        | 378       | 9.94%   |
| Unknown        | 303       | 7.97%   |
| 351-400        | 263       | 6.92%   |
| 601-700        | 121       | 3.18%   |
| 701-800        | 76        | 2%      |
| 1001-1500      | 72        | 1.89%   |
| 1501-2000      | 46        | 1.21%   |
| 801-900        | 38        | 1%      |
| 901-1000       | 6         | 0.16%   |
| 101-200        | 2         | 0.05%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2638      | 73.91%  |
| 16/10   | 417       | 11.68%  |
| Unknown | 270       | 7.57%   |
| 5/4     | 84        | 2.35%   |
| 21/9    | 58        | 1.63%   |
| 3/2     | 54        | 1.51%   |
| 4/3     | 26        | 0.73%   |
| 32/9    | 11        | 0.31%   |
| 6/5     | 4         | 0.11%   |
| 3.73    | 3         | 0.08%   |
| 0.62    | 2         | 0.06%   |
| 1.00    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 978       | 25.53%  |
| 81-90          | 536       | 13.99%  |
| 201-250        | 488       | 12.74%  |
| Unknown        | 303       | 7.91%   |
| 151-200        | 250       | 6.53%   |
| 301-350        | 223       | 5.82%   |
| 351-500        | 165       | 4.31%   |
| 121-130        | 156       | 4.07%   |
| 71-80          | 142       | 3.71%   |
| 141-150        | 108       | 2.82%   |
| More than 1000 | 107       | 2.79%   |
| 51-60          | 97        | 2.53%   |
| 61-70          | 72        | 1.88%   |
| 251-300        | 69        | 1.8%    |
| 501-1000       | 61        | 1.59%   |
| 111-120        | 26        | 0.68%   |
| 131-140        | 25        | 0.65%   |
| 41-50          | 13        | 0.34%   |
| 91-100         | 10        | 0.26%   |
| 1-40           | 2         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1120      | 29.92%  |
| 51-100        | 1090      | 29.12%  |
| 121-160       | 860       | 22.98%  |
| Unknown       | 303       | 8.1%    |
| 161-240       | 199       | 5.32%   |
| 1-50          | 108       | 2.89%   |
| More than 240 | 63        | 1.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3252      | 83.49%  |
| 2     | 465       | 11.94%  |
| 0     | 138       | 3.54%   |
| 3     | 35        | 0.9%    |
| 4     | 4         | 0.1%    |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2055      | 35.27%  |
| Intel                             | 1674      | 28.73%  |
| Qualcomm Atheros                  | 698       | 11.98%  |
| Broadcom                          | 413       | 7.09%   |
| Broadcom Limited                  | 117       | 2.01%   |
| Ralink Technology                 | 87        | 1.49%   |
| TP-Link                           | 85        | 1.46%   |
| Marvell Technology Group          | 78        | 1.34%   |
| MediaTek                          | 70        | 1.2%    |
| Ralink                            | 67        | 1.15%   |
| Nvidia                            | 58        | 1%      |
| Samsung Electronics               | 40        | 0.69%   |
| ASIX Electronics                  | 31        | 0.53%   |
| Dell                              | 25        | 0.43%   |
| NetGear                           | 24        | 0.41%   |
| DisplayLink                       | 20        | 0.34%   |
| Xiaomi                            | 19        | 0.33%   |
| Qualcomm Atheros Communications   | 16        | 0.27%   |
| Huawei Technologies               | 16        | 0.27%   |
| Sierra Wireless                   | 15        | 0.26%   |
| Microsoft                         | 15        | 0.26%   |
| JMicron Technology                | 13        | 0.22%   |
| D-Link System                     | 13        | 0.22%   |
| D-Link                            | 13        | 0.22%   |
| Hewlett-Packard                   | 11        | 0.19%   |
| OPPO Electronics                  | 10        | 0.17%   |
| Edimax Technology                 | 10        | 0.17%   |
| ASUSTek Computer                  | 9         | 0.15%   |
| Motorola PCS                      | 8         | 0.14%   |
| Qualcomm                          | 7         | 0.12%   |
| Linksys                           | 7         | 0.12%   |
| Ericsson Business Mobile Networks | 7         | 0.12%   |
| Aquantia                          | 6         | 0.1%    |
| T & A Mobile Phones               | 5         | 0.09%   |
| Google                            | 5         | 0.09%   |
| Belkin Components                 | 5         | 0.09%   |
| VIA Technologies                  | 4         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.07%   |
| ZyDAS                             | 3         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1295      | 19.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 303       | 4.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 169       | 2.49%   |
| Intel Wi-Fi 6 AX200                                               | 118       | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 112       | 1.65%   |
| Intel Wireless 7265                                               | 110       | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 98        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 95        | 1.4%    |
| Intel Wireless 8265 / 8275                                        | 91        | 1.34%   |
| Intel Wireless 7260                                               | 90        | 1.33%   |
| Intel Wi-Fi 6 AX201                                               | 82        | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                 | 81        | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 81        | 1.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 80        | 1.18%   |
| Intel Ethernet Connection I217-LM                                 | 79        | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 0.94%   |
| Intel Wireless 3165                                               | 63        | 0.93%   |
| Intel Wireless 8260                                               | 61        | 0.9%    |
| Broadcom BCM43142 802.11b/g/n                                     | 61        | 0.9%    |
| Intel I211 Gigabit Network Connection                             | 59        | 0.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 57        | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 55        | 0.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 53        | 0.78%   |
| Realtek 802.11ac NIC                                              | 48        | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 47        | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 46        | 0.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 46        | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 43        | 0.63%   |
| Intel Ethernet Connection (2) I219-V                              | 43        | 0.63%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 40        | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 40        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 0.57%   |
| Ralink MT7601U Wireless Adapter                                   | 38        | 0.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 38        | 0.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 37        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 36        | 0.53%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 36        | 0.53%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 35        | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 32        | 0.47%   |
| Intel WiFi Link 5100                                              | 30        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1278      | 38.92%  |
| Realtek Semiconductor                 | 617       | 18.79%  |
| Qualcomm Atheros                      | 552       | 16.81%  |
| Broadcom                              | 289       | 8.8%    |
| Ralink Technology                     | 87        | 2.65%   |
| Broadcom Limited                      | 76        | 2.31%   |
| TP-Link                               | 74        | 2.25%   |
| Ralink                                | 67        | 2.04%   |
| MediaTek                              | 60        | 1.83%   |
| NetGear                               | 24        | 0.73%   |
| Marvell Technology Group              | 22        | 0.67%   |
| Dell                                  | 19        | 0.58%   |
| Qualcomm Atheros Communications       | 16        | 0.49%   |
| Sierra Wireless                       | 15        | 0.46%   |
| D-Link                                | 13        | 0.4%    |
| Microsoft                             | 12        | 0.37%   |
| D-Link System                         | 11        | 0.33%   |
| Edimax Technology                     | 10        | 0.3%    |
| ASUSTek Computer                      | 8         | 0.24%   |
| Linksys                               | 6         | 0.18%   |
| Belkin Components                     | 5         | 0.15%   |
| ZyDAS                                 | 3         | 0.09%   |
| TRENDnet                              | 2         | 0.06%   |
| Gemtek                                | 2         | 0.06%   |
| Fibocom                               | 2         | 0.06%   |
| AVM                                   | 2         | 0.06%   |
| ZyXEL Communications                  | 1         | 0.03%   |
| Xiaomi                                | 1         | 0.03%   |
| Tenda                                 | 1         | 0.03%   |
| Qualcomm                              | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |
| Mercucys                              | 1         | 0.03%   |
| Hewlett-Packard                       | 1         | 0.03%   |
| Ericsson Business Mobile Networks     | 1         | 0.03%   |
| Askey Computer                        | 1         | 0.03%   |
| ADMtek                                | 1         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 118       | 3.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 112       | 3.38%   |
| Intel Wireless 7265                                            | 110       | 3.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 98        | 2.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 95        | 2.86%   |
| Intel Wireless 8265 / 8275                                     | 91        | 2.74%   |
| Intel Wireless 7260                                            | 90        | 2.71%   |
| Intel Wi-Fi 6 AX201                                            | 82        | 2.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 81        | 2.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 80        | 2.41%   |
| Intel Wireless 3165                                            | 63        | 1.9%    |
| Intel Wireless 8260                                            | 61        | 1.84%   |
| Broadcom BCM43142 802.11b/g/n                                  | 61        | 1.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 57        | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 55        | 1.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 53        | 1.6%    |
| Realtek 802.11ac NIC                                           | 48        | 1.45%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 47        | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 46        | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 46        | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 40        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 40        | 1.21%   |
| Ralink MT7601U Wireless Adapter                                | 38        | 1.15%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 38        | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 37        | 1.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 36        | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 35        | 1.06%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 32        | 0.97%   |
| Intel WiFi Link 5100                                           | 30        | 0.9%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 28        | 0.84%   |
| Intel Wireless-AC 9260                                         | 27        | 0.81%   |
| Intel Centrino Ultimate-N 6300                                 | 27        | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 26        | 0.78%   |
| Intel Wireless 3160                                            | 25        | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 24        | 0.72%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 24        | 0.72%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 23        | 0.69%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 22        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 22        | 0.66%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 22        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1783      | 53.18%  |
| Intel                             | 822       | 24.52%  |
| Qualcomm Atheros                  | 198       | 5.91%   |
| Broadcom                          | 181       | 5.4%    |
| Nvidia                            | 58        | 1.73%   |
| Marvell Technology Group          | 56        | 1.67%   |
| Broadcom Limited                  | 43        | 1.28%   |
| ASIX Electronics                  | 31        | 0.92%   |
| Samsung Electronics               | 27        | 0.81%   |
| DisplayLink                       | 20        | 0.6%    |
| Xiaomi                            | 18        | 0.54%   |
| JMicron Technology                | 13        | 0.39%   |
| Huawei Technologies               | 13        | 0.39%   |
| TP-Link                           | 11        | 0.33%   |
| OPPO Electronics                  | 10        | 0.3%    |
| MediaTek                          | 9         | 0.27%   |
| Qualcomm                          | 6         | 0.18%   |
| Aquantia                          | 6         | 0.18%   |
| Motorola PCS                      | 5         | 0.15%   |
| Google                            | 5         | 0.15%   |
| VIA Technologies                  | 4         | 0.12%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.09%   |
| Hewlett-Packard                   | 3         | 0.09%   |
| Sundance Technology Inc / IC Plus | 2         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.06%   |
| Microsoft                         | 2         | 0.06%   |
| Lenovo                            | 2         | 0.06%   |
| ICS Advent                        | 2         | 0.06%   |
| HMD Global                        | 2         | 0.06%   |
| D-Link System                     | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| T & A Mobile Phones               | 1         | 0.03%   |
| Sun Microsystems                  | 1         | 0.03%   |
| Research In Motion                | 1         | 0.03%   |
| Novatel Wireless                  | 1         | 0.03%   |
| Motorola BCS                      | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| LG Electronics                    | 1         | 0.03%   |
| HTC (High Tech Computer)          | 1         | 0.03%   |
| GoPro                             | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1295      | 38.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 303       | 8.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 169       | 4.97%   |
| Realtek RTL8125 2.5GbE Controller                                 | 81        | 2.38%   |
| Intel Ethernet Connection I217-LM                                 | 79        | 2.33%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 1.88%   |
| Intel I211 Gigabit Network Connection                             | 59        | 1.74%   |
| Intel Ethernet Controller I225-V                                  | 43        | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 43        | 1.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 1.15%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 36        | 1.06%   |
| Intel Ethernet Connection I217-V                                  | 28        | 0.82%   |
| Intel Ethernet Connection I219-LM                                 | 27        | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 26        | 0.77%   |
| Intel Ethernet Connection I218-LM                                 | 26        | 0.77%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 25        | 0.74%   |
| Nvidia MCP79 Ethernet                                             | 24        | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 22        | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.65%   |
| Intel 82577LM Gigabit Network Connection                          | 22        | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.62%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 21        | 0.62%   |
| Nvidia MCP61 Ethernet                                             | 19        | 0.56%   |
| Intel 82579V Gigabit Network Connection                           | 18        | 0.53%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.53%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 17        | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 17        | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 17        | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 16        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 16        | 0.47%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 16        | 0.47%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 15        | 0.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 15        | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 14        | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 14        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3181      | 50.39%  |
| WiFi     | 3062      | 48.5%   |
| Modem    | 57        | 0.9%    |
| Unknown  | 13        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2394      | 60.21%  |
| Ethernet | 1576      | 39.64%  |
| Modem    | 3         | 0.08%   |
| Unknown  | 3         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2066      | 53.76%  |
| 1     | 1574      | 40.96%  |
| 0     | 129       | 3.36%   |
| 3     | 68        | 1.77%   |
| 5     | 3         | 0.08%   |
| 4     | 2         | 0.05%   |
| 7     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2651      | 68.15%  |
| Yes  | 1239      | 31.85%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 988       | 42.42%  |
| Realtek Semiconductor           | 282       | 12.11%  |
| Qualcomm Atheros Communications | 202       | 8.67%   |
| Broadcom                        | 130       | 5.58%   |
| Apple                           | 129       | 5.54%   |
| Cambridge Silicon Radio         | 121       | 5.2%    |
| IMC Networks                    | 100       | 4.29%   |
| Foxconn / Hon Hai               | 62        | 2.66%   |
| Lite-On Technology              | 57        | 2.45%   |
| Dell                            | 40        | 1.72%   |
| ASUSTek Computer                | 33        | 1.42%   |
| Hewlett-Packard                 | 32        | 1.37%   |
| Toshiba                         | 28        | 1.2%    |
| Marvell Semiconductor           | 21        | 0.9%    |
| Ralink                          | 18        | 0.77%   |
| MediaTek                        | 16        | 0.69%   |
| Realtek                         | 12        | 0.52%   |
| TP-Link                         | 8         | 0.34%   |
| Foxconn International           | 7         | 0.3%    |
| Integrated System Solution      | 6         | 0.26%   |
| Alps Electric                   | 6         | 0.26%   |
| Dynex                           | 5         | 0.21%   |
| Unknown                         | 5         | 0.21%   |
| Belkin Components               | 4         | 0.17%   |
| Askey Computer                  | 3         | 0.13%   |
| Actions                         | 3         | 0.13%   |
| Ralink Technology               | 2         | 0.09%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| National Semiconductor          | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Conwise Technology              | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 418       | 17.92%  |
| Realtek Bluetooth Radio                             | 181       | 7.76%   |
| Intel AX201 Bluetooth                               | 151       | 6.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 124       | 5.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 121       | 5.19%   |
| Intel AX200 Bluetooth                               | 103       | 4.42%   |
| Qualcomm Atheros  Bluetooth Device                  | 86        | 3.69%   |
| Apple Bluetooth Host Controller                     | 59        | 2.53%   |
| Realtek  Bluetooth 4.2 Adapter                      | 57        | 2.44%   |
| Intel AX210 Bluetooth                               | 51        | 2.19%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 38        | 1.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 36        | 1.54%   |
| IMC Networks Bluetooth Device                       | 35        | 1.5%    |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 33        | 1.42%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 30        | 1.29%   |
| IMC Networks Bluetooth Radio                        | 29        | 1.24%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 28        | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.16%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 26        | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 23        | 0.99%   |
| Apple Bluetooth USB Host Controller                 | 23        | 0.99%   |
| Intel Bluetooth Device                              | 21        | 0.9%    |
| Realtek 802.11ac WLAN Adapter                       | 20        | 0.86%   |
| Marvell Bluetooth and Wireless LAN Composite        | 20        | 0.86%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 20        | 0.86%   |
| IMC Networks Wireless_Device                        | 20        | 0.86%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 19        | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 19        | 0.81%   |
| Ralink RT3290 Bluetooth                             | 18        | 0.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 18        | 0.77%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.73%   |
| Foxconn / Hon Hai Bluetooth Device                  | 17        | 0.73%   |
| MediaTek Wireless_Device                            | 15        | 0.64%   |
| Dell DW375 Bluetooth Module                         | 14        | 0.6%    |
| Apple Bluetooth HCI                                 | 14        | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.56%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.56%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 13        | 0.56%   |
| Lite-On Bluetooth Device                            | 11        | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2825      | 55.15%  |
| AMD                                          | 1060      | 20.7%   |
| Nvidia                                       | 822       | 16.05%  |
| C-Media Electronics                          | 60        | 1.17%   |
| Creative Labs                                | 25        | 0.49%   |
| Logitech                                     | 21        | 0.41%   |
| JMTek                                        | 19        | 0.37%   |
| Generalplus Technology                       | 18        | 0.35%   |
| Texas Instruments                            | 17        | 0.33%   |
| Kingston Technology                          | 17        | 0.33%   |
| ASUSTek Computer                             | 16        | 0.31%   |
| Realtek Semiconductor                        | 12        | 0.23%   |
| Plantronics                                  | 11        | 0.21%   |
| VIA Technologies                             | 10        | 0.2%    |
| Razer USA                                    | 10        | 0.2%    |
| GN Netcom                                    | 10        | 0.2%    |
| Creative Technology                          | 10        | 0.2%    |
| SteelSeries ApS                              | 7         | 0.14%   |
| Tenx Technology                              | 6         | 0.12%   |
| Micro Star International                     | 6         | 0.12%   |
| Lenovo                                       | 6         | 0.12%   |
| Focusrite-Novation                           | 6         | 0.12%   |
| DCMT Technology                              | 5         | 0.1%    |
| Corsair                                      | 5         | 0.1%    |
| Zoran Co. Personal Media Division (Nogatech) | 4         | 0.08%   |
| PreSonus Audio Electronics                   | 4         | 0.08%   |
| KTMicro                                      | 4         | 0.08%   |
| DSEA A/S                                     | 4         | 0.08%   |
| BR25                                         | 4         | 0.08%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.06%   |
| RODE Microphones                             | 3         | 0.06%   |
| BEHRINGER International                      | 3         | 0.06%   |
| Astro Gaming                                 | 3         | 0.06%   |
| Asahi Kasei Microsystems                     | 3         | 0.06%   |
| Apple                                        | 3         | 0.06%   |
| AKAI Professional M.I.                       | 3         | 0.06%   |
| Yamaha                                       | 2         | 0.04%   |
| XMOS                                         | 2         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 2         | 0.04%   |
| Sony                                         | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 302       | 4.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 296       | 4.86%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 282       | 4.63%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 260       | 4.27%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 221       | 3.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 156       | 2.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 152       | 2.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 145       | 2.38%   |
| AMD FCH Azalia Controller                                                                         | 144       | 2.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 125       | 2.05%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 122       | 2%      |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 118       | 1.94%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 116       | 1.9%    |
| Intel 8 Series HD Audio Controller                                                                | 114       | 1.87%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 110       | 1.81%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 108       | 1.77%   |
| Intel Cannon Lake PCH cAVS                                                                        | 93        | 1.53%   |
| Intel Broadwell-U Audio Controller                                                                | 91        | 1.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 89        | 1.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 87        | 1.43%   |
| AMD Kabini HDMI/DP Audio                                                                          | 86        | 1.41%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 85        | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 83        | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 71        | 1.17%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 67        | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 64        | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 63        | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 63        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 61        | 1%      |
| Intel 200 Series PCH HD Audio                                                                     | 55        | 0.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 55        | 0.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 52        | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 48        | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 46        | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 46        | 0.76%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 46        | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 44        | 0.72%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 43        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 42        | 0.69%   |
| Nvidia High Definition Audio Controller                                                           | 41        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 208       | 24.05%  |
| SK hynix               | 160       | 18.5%   |
| Micron Technology      | 94        | 10.87%  |
| Unknown                | 78        | 9.02%   |
| Kingston               | 69        | 7.98%   |
| Crucial                | 45        | 5.2%    |
| Unknown (ABCD)         | 26        | 3.01%   |
| Corsair                | 26        | 3.01%   |
| G.Skill                | 24        | 2.77%   |
| A-DATA Technology      | 17        | 1.97%   |
| Team                   | 14        | 1.62%   |
| Elpida                 | 13        | 1.5%    |
| Ramaxel Technology     | 12        | 1.39%   |
| Unknown                | 9         | 1.04%   |
| Nanya Technology       | 8         | 0.92%   |
| Smart                  | 7         | 0.81%   |
| Patriot                | 5         | 0.58%   |
| Timetec                | 4         | 0.46%   |
| Avant                  | 3         | 0.35%   |
| Wilk                   | 2         | 0.23%   |
| Unifosa                | 2         | 0.23%   |
| Transcend              | 2         | 0.23%   |
| Teikon                 | 2         | 0.23%   |
| Qimonda                | 2         | 0.23%   |
| ff                     | 2         | 0.23%   |
| fef5                   | 2         | 0.23%   |
| Apacer                 | 2         | 0.23%   |
| 4ea5                   | 2         | 0.23%   |
| Unknown (08B5)         | 1         | 0.12%   |
| Unknown (07F7)         | 1         | 0.12%   |
| Unknown (000080B30080) | 1         | 0.12%   |
| SUPER KINGSTEK         | 1         | 0.12%   |
| Strontium              | 1         | 0.12%   |
| Smart Brazil           | 1         | 0.12%   |
| Silicon Power          | 1         | 0.12%   |
| SHARETRONIC            | 1         | 0.12%   |
| PUSKILL                | 1         | 0.12%   |
| ProMos/Mosel Vitelic   | 1         | 0.12%   |
| pqi                    | 1         | 0.12%   |
| PNY                    | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s  | 22        | 2.4%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s            | 11        | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s             | 10        | 1.09%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 9         | 0.98%   |
| Unknown                                                           | 9         | 0.98%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s             | 8         | 0.87%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s            | 7         | 0.77%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s             | 7         | 0.77%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s             | 7         | 0.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s             | 7         | 0.77%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s             | 7         | 0.77%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                      | 6         | 0.66%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s             | 6         | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s             | 6         | 0.66%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s             | 6         | 0.66%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 5         | 0.55%   |
| SK hynix RAM HMT425S6AFR6A-PB 2048MB SODIMM DDR3 3200MT/s         | 5         | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s            | 5         | 0.55%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s            | 5         | 0.55%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s             | 5         | 0.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s             | 5         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s        | 5         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3                             | 4         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                    | 4         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 1536MB DIMM LPDDR4 2400MT/s | 4         | 0.44%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s            | 4         | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s            | 4         | 0.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s            | 4         | 0.44%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s        | 4         | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s             | 4         | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s       | 4         | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s       | 4         | 0.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s             | 4         | 0.44%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s             | 4         | 0.44%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s          | 4         | 0.44%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.44%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s              | 4         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3                                | 3         | 0.33%   |
| Unknown RAM Module 2048MB SODIMM DDR3                             | 3         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 316       | 42.53%  |
| DDR3    | 263       | 35.4%   |
| LPDDR4  | 56        | 7.54%   |
| LPDDR3  | 30        | 4.04%   |
| DDR2    | 28        | 3.77%   |
| SDRAM   | 18        | 2.42%   |
| Unknown | 17        | 2.29%   |
| DDR5    | 7         | 0.94%   |
| LPDDR5  | 4         | 0.54%   |
| DDR     | 4         | 0.54%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 461       | 62.21%  |
| DIMM         | 190       | 25.64%  |
| Row Of Chips | 73        | 9.85%   |
| Chip         | 8         | 1.08%   |
| Unknown      | 8         | 1.08%   |
| FB-DIMM      | 1         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 315       | 38.18%  |
| 4096  | 249       | 30.18%  |
| 2048  | 119       | 14.42%  |
| 16384 | 91        | 11.03%  |
| 32768 | 26        | 3.15%   |
| 1024  | 23        | 2.79%   |
| 512   | 2         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 167       | 20.75%  |
| 3200    | 132       | 16.4%   |
| 2667    | 106       | 13.17%  |
| 2400    | 71        | 8.82%   |
| 1333    | 52        | 6.46%   |
| 2133    | 31        | 3.85%   |
| 1334    | 26        | 3.23%   |
| 1867    | 19        | 2.36%   |
| 4267    | 17        | 2.11%   |
| 3600    | 16        | 1.99%   |
| 667     | 14        | 1.74%   |
| Unknown | 14        | 1.74%   |
| 800     | 13        | 1.61%   |
| 1066    | 12        | 1.49%   |
| 3266    | 10        | 1.24%   |
| 4800    | 7         | 0.87%   |
| 3733    | 7         | 0.87%   |
| 3000    | 7         | 0.87%   |
| 2048    | 7         | 0.87%   |
| 1866    | 7         | 0.87%   |
| 1800    | 6         | 0.75%   |
| 6400    | 5         | 0.62%   |
| 1067    | 5         | 0.62%   |
| 8400    | 4         | 0.5%    |
| 2933    | 4         | 0.5%    |
| 975     | 4         | 0.5%    |
| 4266    | 3         | 0.37%   |
| 4199    | 3         | 0.37%   |
| 3800    | 3         | 0.37%   |
| 2666    | 3         | 0.37%   |
| 3866    | 2         | 0.25%   |
| 3666    | 2         | 0.25%   |
| 3500    | 2         | 0.25%   |
| 3466    | 2         | 0.25%   |
| 3400    | 2         | 0.25%   |
| 400     | 2         | 0.25%   |
| 6000    | 1         | 0.12%   |
| 5600    | 1         | 0.12%   |
| 5354    | 1         | 0.12%   |
| 5200    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 31        | 31.63%  |
| Canon                 | 19        | 19.39%  |
| Brother Industries    | 16        | 16.33%  |
| Seiko Epson           | 14        | 14.29%  |
| Samsung Electronics   | 10        | 10.2%   |
| Lexmark International | 3         | 3.06%   |
| Zebra                 | 1         | 1.02%   |
| Ricoh                 | 1         | 1.02%   |
| QinHeng Electronics   | 1         | 1.02%   |
| Konica Minolta        | 1         | 1.02%   |
| GG IMAGE              | 1         | 1.02%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                     | 3         | 3.06%   |
| HP DeskJet 2700 series                       | 3         | 3.06%   |
| Samsung C460 Series                          | 2         | 2.04%   |
| HP OfficeJet 6950                            | 2         | 2.04%   |
| HP LaserJet Professional P1102w              | 2         | 2.04%   |
| HP ENVY Photo 6200 series                    | 2         | 2.04%   |
| HP DeskJet 2130 series                       | 2         | 2.04%   |
| Canon TS3100 series                          | 2         | 2.04%   |
| Canon PIXMA MG3600 Series                    | 2         | 2.04%   |
| Canon LiDE 400                               | 2         | 2.04%   |
| Brother HL-2140 series                       | 2         | 2.04%   |
| Zebra ZP 450 Printer                         | 1         | 1.02%   |
| Seiko Epson XP-7100 Series                   | 1         | 1.02%   |
| Seiko Epson XP-235 Series                    | 1         | 1.02%   |
| Seiko Epson XP-200 Series                    | 1         | 1.02%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 1.02%   |
| Seiko Epson L805 Series                      | 1         | 1.02%   |
| Seiko Epson L6270 Series                     | 1         | 1.02%   |
| Seiko Epson L355 Series                      | 1         | 1.02%   |
| Seiko Epson L3150 Series                     | 1         | 1.02%   |
| Seiko Epson ET-2820 Series                   | 1         | 1.02%   |
| Seiko Epson ET-2810 Series                   | 1         | 1.02%   |
| Seiko Epson AcuLaser C1700                   | 1         | 1.02%   |
| Samsung SCX-483x 5x3x Series                 | 1         | 1.02%   |
| Samsung SCX-4623 Series                      | 1         | 1.02%   |
| Samsung SCX-4200 series                      | 1         | 1.02%   |
| Samsung SCX-3400 Series                      | 1         | 1.02%   |
| Samsung ML-2950 Series                       | 1         | 1.02%   |
| Samsung ML-216x Series Laser Printer         | 1         | 1.02%   |
| Samsung M2070 Series                         | 1         | 1.02%   |
| Samsung M2020 Series                         | 1         | 1.02%   |
| Ricoh SP 112SU                               | 1         | 1.02%   |
| QinHeng CH340S                               | 1         | 1.02%   |
| Lexmark International MX317dn                | 1         | 1.02%   |
| Lexmark International Laser Printer E232     | 1         | 1.02%   |
| Lexmark International 2400 series            | 1         | 1.02%   |
| Konica Minolta PagePro 1380MF                | 1         | 1.02%   |
| HP Smart Tank 510 series                     | 1         | 1.02%   |
| HP PSC 1100 series                           | 1         | 1.02%   |
| HP OfficeJet Pro 9010 series                 | 1         | 1.02%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 61.11%  |
| Seiko Epson     | 4         | 22.22%  |
| Hewlett-Packard | 3         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 3         | 15.79%  |
| Canon CanoScan LiDE 90                      | 2         | 10.53%  |
| Canon CanoScan LiDE 220                     | 2         | 10.53%  |
| Seiko Epson Scanner                         | 1         | 5.26%   |
| HP ScanJet 2400c                            | 1         | 5.26%   |
| HP Scanjet 200                              | 1         | 5.26%   |
| HP PSC 1200                                 | 1         | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 5.26%   |
| Canon CanoScan LiDE 60                      | 1         | 5.26%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1         | 5.26%   |
| Canon CanoScan LIDE 25                      | 1         | 5.26%   |
| Canon CanoScan LiDE 110                     | 1         | 5.26%   |
| Canon CanoScan LiDE 100                     | 1         | 5.26%   |
| Canon CanoScan D660U                        | 1         | 5.26%   |
| Canon CanoScan 8800F                        | 1         | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 465       | 20.71%  |
| Microdia                               | 199       | 8.86%   |
| Realtek Semiconductor                  | 185       | 8.24%   |
| IMC Networks                           | 165       | 7.35%   |
| Sunplus Innovation Technology          | 126       | 5.61%   |
| Bison Electronics                      | 118       | 5.26%   |
| Apple                                  | 113       | 5.03%   |
| Cheng Uei Precision Industry (Foxlink) | 97        | 4.32%   |
| Quanta                                 | 95        | 4.23%   |
| Logitech                               | 86        | 3.83%   |
| Suyin                                  | 76        | 3.39%   |
| Syntek                                 | 62        | 2.76%   |
| Lite-On Technology                     | 43        | 1.92%   |
| Alcor Micro                            | 37        | 1.65%   |
| Silicon Motion                         | 35        | 1.56%   |
| Acer                                   | 30        | 1.34%   |
| Luxvisions Innotech Limited            | 25        | 1.11%   |
| Microsoft                              | 22        | 0.98%   |
| Samsung Electronics                    | 21        | 0.94%   |
| Ricoh                                  | 20        | 0.89%   |
| Sonix Technology                       | 17        | 0.76%   |
| icSpring                               | 14        | 0.62%   |
| Z-Star Microelectronics                | 13        | 0.58%   |
| Primax Electronics                     | 12        | 0.53%   |
| Generalplus Technology                 | 12        | 0.53%   |
| ARC International                      | 10        | 0.45%   |
| SunplusIT                              | 9         | 0.4%    |
| Lenovo                                 | 9         | 0.4%    |
| GEMBIRD                                | 9         | 0.4%    |
| ALi                                    | 8         | 0.36%   |
| Importek                               | 6         | 0.27%   |
| Y Media                                | 5         | 0.22%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.22%   |
| Jieli Technology                       | 5         | 0.22%   |
| Sunplus Technology                     | 4         | 0.18%   |
| Razer USA                              | 4         | 0.18%   |
| Intel                                  | 4         | 0.18%   |
| Genesys Logic                          | 4         | 0.18%   |
| Creative Technology                    | 4         | 0.18%   |
| Tobii Technology AB                    | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 80        | 3.54%   |
| Microdia Integrated_Webcam_HD                       | 46        | 2.04%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 42        | 1.86%   |
| Apple FaceTime HD Camera (Built-in)                 | 41        | 1.81%   |
| Syntek Integrated Camera                            | 40        | 1.77%   |
| Bison Integrated Camera                             | 40        | 1.77%   |
| Realtek Integrated_Webcam_HD                        | 38        | 1.68%   |
| Chicony HD WebCam                                   | 37        | 1.64%   |
| IMC Networks Integrated Camera                      | 32        | 1.42%   |
| Realtek USB Camera                                  | 29        | 1.28%   |
| Apple Built-in iSight                               | 29        | 1.28%   |
| Chicony HP Truevision HD                            | 28        | 1.24%   |
| Microdia Integrated Webcam                          | 26        | 1.15%   |
| Chicony TOSHIBA Web Camera - HD                     | 24        | 1.06%   |
| Sunplus Integrated_Webcam_HD                        | 23        | 1.02%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 23        | 1.02%   |
| Samsung Galaxy series, misc. (MTP mode)             | 21        | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 21        | 0.93%   |
| Bison Lenovo EasyCamera                             | 21        | 0.93%   |
| Logitech Webcam C270                                | 19        | 0.84%   |
| Lite-On HP HD Camera                                | 18        | 0.8%    |
| Alcor Micro USB 2.0 Camera                          | 18        | 0.8%    |
| Microdia Webcam Vitade AF                           | 17        | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 17        | 0.75%   |
| Sunplus HD WebCam                                   | 16        | 0.71%   |
| Chicony EasyCamera                                  | 16        | 0.71%   |
| Realtek Integrated Webcam                           | 15        | 0.66%   |
| Realtek HP Truevision HD                            | 15        | 0.66%   |
| Chicony USB2.0 VGA UVC WebCam                       | 15        | 0.66%   |
| Chicony HP TrueVision HD Camera                     | 15        | 0.66%   |
| Apple FaceTime HD Camera                            | 15        | 0.66%   |
| Quanta HP Wide Vision HD Camera                     | 14        | 0.62%   |
| Quanta HD User Facing                               | 14        | 0.62%   |
| icSpring camera                                     | 14        | 0.62%   |
| Chicony VGA WebCam                                  | 14        | 0.62%   |
| Chicony Lenovo EasyCamera                           | 14        | 0.62%   |
| Chicony HP HD Camera                                | 14        | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 13        | 0.58%   |
| Logitech HD Pro Webcam C920                         | 13        | 0.58%   |
| Chicony HP Wide Vision HD Camera                    | 13        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 148       | 40.44%  |
| Synaptics                          | 60        | 16.39%  |
| Shenzhen Goodix Technology         | 50        | 13.66%  |
| AuthenTec                          | 34        | 9.29%   |
| Upek                               | 24        | 6.56%   |
| Elan Microelectronics              | 22        | 6.01%   |
| LighTuning Technology              | 12        | 3.28%   |
| STMicroelectronics                 | 7         | 1.91%   |
| Samsung Electronics                | 3         | 0.82%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 0.82%   |
| Next Biometrics                    | 1         | 0.27%   |
| HOLTEK                             | 1         | 0.27%   |
| Focal-systems.Corp                 | 1         | 0.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 8.2%    |
| Shenzhen Goodix  Fingerprint Device                                        | 29        | 7.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 6.01%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 4.92%   |
| Validity Sensors VFS491                                                    | 15        | 4.1%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 4.1%    |
| Elan ELAN:ARM-M4                                                           | 15        | 4.1%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 3.55%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 3.01%   |
| AuthenTec AES2810                                                          | 11        | 3.01%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 3.01%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.73%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 2.73%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.46%   |
| Synaptics UWP WBDI                                                         | 9         | 2.46%   |
| Synaptics  WBDI                                                            | 9         | 2.46%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 2.46%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 2.19%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.91%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.91%   |
| Synaptics WBDI                                                             | 7         | 1.91%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.91%   |
| Elan ELAN:Fingerprint                                                      | 7         | 1.91%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.64%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 1.64%   |
| LighTuning Fingerprint Sensor                                              | 5         | 1.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.37%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.37%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 1.09%   |
| AuthenTec AES1600                                                          | 4         | 1.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.82%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.82%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.82%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 0.82%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.55%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.55%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 80        | 52.63%  |
| Alcor Micro                       | 25        | 16.45%  |
| O2 Micro                          | 16        | 10.53%  |
| Upek                              | 6         | 3.95%   |
| Lenovo                            | 6         | 3.95%   |
| VASCO Data Security International | 3         | 1.97%   |
| Realtek Semiconductor             | 3         | 1.97%   |
| Yubico.com                        | 2         | 1.32%   |
| SCM Microsystems                  | 2         | 1.32%   |
| Fujitsu Siemens Computers         | 2         | 1.32%   |
| Advanced Card Systems             | 2         | 1.32%   |
| Reiner SCT Kartensysteme          | 1         | 0.66%   |
| OmniKey                           | 1         | 0.66%   |
| Jing-Mold Enterprise              | 1         | 0.66%   |
| Gemalto (was Gemplus)             | 1         | 0.66%   |
| Chicony Electronics               | 1         | 0.66%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 30        | 19.74%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 25        | 16.45%  |
| Broadcom 5880                                                                | 22        | 14.47%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 13.16%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 9.87%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 3.95%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.95%   |
| Broadcom 58200                                                               | 6         | 3.95%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.97%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.32%   |
| VASCO Data Security International DIGIPASS 870                               | 2         | 1.32%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 2         | 1.32%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.32%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.66%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.66%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.66%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.66%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.66%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.66%   |
| Jing-Mold Enterprise HP USB Business Slim Smartcard CCID Keyboard            | 1         | 0.66%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.66%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.66%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.66%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.66%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2745      | 70.4%   |
| 1     | 928       | 23.8%   |
| 2     | 199       | 5.1%    |
| 3     | 24        | 0.62%   |
| 4     | 2         | 0.05%   |
| 8     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 360       | 26.51%  |
| Graphics card            | 297       | 21.87%  |
| Net/wireless             | 239       | 17.6%   |
| Multimedia controller    | 159       | 11.71%  |
| Chipcard                 | 141       | 10.38%  |
| Communication controller | 29        | 2.14%   |
| Bluetooth                | 28        | 2.06%   |
| Storage                  | 26        | 1.91%   |
| Sound                    | 13        | 0.96%   |
| Unassigned class         | 10        | 0.74%   |
| Camera                   | 10        | 0.74%   |
| Net/ethernet             | 8         | 0.59%   |
| Modem                    | 7         | 0.52%   |
| Storage/raid             | 6         | 0.44%   |
| Network                  | 6         | 0.44%   |
| Dvb card                 | 5         | 0.37%   |
| Card reader              | 5         | 0.37%   |
| Storage/ide              | 4         | 0.29%   |
| Storage/nvme             | 2         | 0.15%   |
| Flash memory             | 2         | 0.15%   |
| Unclassified device      | 1         | 0.07%   |

