Linux in India - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in India.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/India/Desktop/README.md) and [notebooks](/Location/India/Notebook/README.md).

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

Total: 6745

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ENVY x360 Convertible 13... | Convertible | [ea37beb412](https://linux-hardware.org/?probe=ea37beb412) | Nov 05, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c17ad7033c](https://linux-hardware.org/?probe=c17ad7033c) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [399dda92eb](https://linux-hardware.org/?probe=399dda92eb) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [49c91b6782](https://linux-hardware.org/?probe=49c91b6782) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [c39cd7480d](https://linux-hardware.org/?probe=c39cd7480d) | Nov 04, 2023 |
| HP            | 15                          | Notebook    | [5d5fb36764](https://linux-hardware.org/?probe=5d5fb36764) | Nov 04, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [ede0c05f18](https://linux-hardware.org/?probe=ede0c05f18) | Nov 04, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [07e66cf3c5](https://linux-hardware.org/?probe=07e66cf3c5) | Nov 04, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [3521a1f918](https://linux-hardware.org/?probe=3521a1f918) | Nov 04, 2023 |
| AVITA         | NS14A2                      | Notebook    | [738e0008ce](https://linux-hardware.org/?probe=738e0008ce) | Nov 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [dff06d88c5](https://linux-hardware.org/?probe=dff06d88c5) | Nov 03, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [c4aa915297](https://linux-hardware.org/?probe=c4aa915297) | Nov 03, 2023 |
| Dell          | 0CN7X8 A05                  | Server      | [afe0c7dfbe](https://linux-hardware.org/?probe=afe0c7dfbe) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [bb1da2575d](https://linux-hardware.org/?probe=bb1da2575d) | Nov 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS13J00     | Notebook    | [ebfdc934b7](https://linux-hardware.org/?probe=ebfdc934b7) | Nov 02, 2023 |
| Acer          | Swift SF314-55G             | Notebook    | [fee0e3c809](https://linux-hardware.org/?probe=fee0e3c809) | Nov 02, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [137dba2261](https://linux-hardware.org/?probe=137dba2261) | Nov 02, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [e4b4501211](https://linux-hardware.org/?probe=e4b4501211) | Nov 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [54516fba78](https://linux-hardware.org/?probe=54516fba78) | Nov 01, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [59e202bef7](https://linux-hardware.org/?probe=59e202bef7) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3c04d0213b](https://linux-hardware.org/?probe=3c04d0213b) | Nov 01, 2023 |
| Gigabyte      | A520M K V2                  | Desktop     | [10670f1068](https://linux-hardware.org/?probe=10670f1068) | Nov 01, 2023 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [9031850aa0](https://linux-hardware.org/?probe=9031850aa0) | Nov 01, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [70e4b3b007](https://linux-hardware.org/?probe=70e4b3b007) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [352bf34e3b](https://linux-hardware.org/?probe=352bf34e3b) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [2e35f866e3](https://linux-hardware.org/?probe=2e35f866e3) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 20RAS13J00     | Notebook    | [91a0aacae9](https://linux-hardware.org/?probe=91a0aacae9) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [ebec8d6fd1](https://linux-hardware.org/?probe=ebec8d6fd1) | Oct 31, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d9da25aaae](https://linux-hardware.org/?probe=d9da25aaae) | Oct 31, 2023 |
| Acer          | One 14 Z8-415               | Notebook    | [e3b7fce5f3](https://linux-hardware.org/?probe=e3b7fce5f3) | Oct 31, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [069872b404](https://linux-hardware.org/?probe=069872b404) | Oct 31, 2023 |
| Chuwi         | CoreBook                    | Notebook    | [71b0d03991](https://linux-hardware.org/?probe=71b0d03991) | Oct 30, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [7ffe987b92](https://linux-hardware.org/?probe=7ffe987b92) | Oct 30, 2023 |
| Intel         | H81                         | Desktop     | [2e37259d45](https://linux-hardware.org/?probe=2e37259d45) | Oct 29, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [4e093f6544](https://linux-hardware.org/?probe=4e093f6544) | Oct 29, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [1b0a34d774](https://linux-hardware.org/?probe=1b0a34d774) | Oct 29, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [be3a00001c](https://linux-hardware.org/?probe=be3a00001c) | Oct 29, 2023 |
| HP            | 15                          | Notebook    | [cda635d432](https://linux-hardware.org/?probe=cda635d432) | Oct 28, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ecc6e8d906](https://linux-hardware.org/?probe=ecc6e8d906) | Oct 28, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [ce321700bc](https://linux-hardware.org/?probe=ce321700bc) | Oct 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c25324c2a2](https://linux-hardware.org/?probe=c25324c2a2) | Oct 28, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [8157e9bd12](https://linux-hardware.org/?probe=8157e9bd12) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [49982fda5c](https://linux-hardware.org/?probe=49982fda5c) | Oct 28, 2023 |
| HCL Infosy... | HCL ME Laptop               | Notebook    | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [44b772393d](https://linux-hardware.org/?probe=44b772393d) | Oct 27, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [66cfbcd057](https://linux-hardware.org/?probe=66cfbcd057) | Oct 26, 2023 |
| ECS           | H81H3-M3S                   | Desktop     | [6f4c530a93](https://linux-hardware.org/?probe=6f4c530a93) | Oct 26, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [f3407cd11d](https://linux-hardware.org/?probe=f3407cd11d) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | Notebook    | [0ed2bd399f](https://linux-hardware.org/?probe=0ed2bd399f) | Oct 25, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [03333fbe23](https://linux-hardware.org/?probe=03333fbe23) | Oct 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [358936d398](https://linux-hardware.org/?probe=358936d398) | Oct 25, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [71a22f4706](https://linux-hardware.org/?probe=71a22f4706) | Oct 25, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9246bb9a28](https://linux-hardware.org/?probe=9246bb9a28) | Oct 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Google        | Teemo                       | Desktop     | [ae5140ac26](https://linux-hardware.org/?probe=ae5140ac26) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | Notebook    | [0f08eb340b](https://linux-hardware.org/?probe=0f08eb340b) | Oct 24, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [332b714861](https://linux-hardware.org/?probe=332b714861) | Oct 24, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [673f62810a](https://linux-hardware.org/?probe=673f62810a) | Oct 23, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [5a23f97862](https://linux-hardware.org/?probe=5a23f97862) | Oct 23, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cf347b4567](https://linux-hardware.org/?probe=cf347b4567) | Oct 23, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [470eb40837](https://linux-hardware.org/?probe=470eb40837) | Oct 23, 2023 |
| HP            | Laptop 14s-dy5xxx           | Notebook    | [e873e5d24c](https://linux-hardware.org/?probe=e873e5d24c) | Oct 23, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | Notebook    | [399c501d43](https://linux-hardware.org/?probe=399c501d43) | Oct 23, 2023 |
| ASUSTek       | GL553VE                     | Notebook    | [9cb6cb4f5b](https://linux-hardware.org/?probe=9cb6cb4f5b) | Oct 22, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [f6831bde3b](https://linux-hardware.org/?probe=f6831bde3b) | Oct 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 Ua 82F... | Notebook    | [735bb309a1](https://linux-hardware.org/?probe=735bb309a1) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [f204c7469c](https://linux-hardware.org/?probe=f204c7469c) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [5f376e3415](https://linux-hardware.org/?probe=5f376e3415) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [422e70640a](https://linux-hardware.org/?probe=422e70640a) | Oct 21, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [76632b6a09](https://linux-hardware.org/?probe=76632b6a09) | Oct 21, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [b762dc0df0](https://linux-hardware.org/?probe=b762dc0df0) | Oct 20, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [cc2f4a6fce](https://linux-hardware.org/?probe=cc2f4a6fce) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [ee44c25ed9](https://linux-hardware.org/?probe=ee44c25ed9) | Oct 20, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [4e0af93a94](https://linux-hardware.org/?probe=4e0af93a94) | Oct 20, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [137f87e169](https://linux-hardware.org/?probe=137f87e169) | Oct 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a7dbe29bbe](https://linux-hardware.org/?probe=a7dbe29bbe) | Oct 19, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [0c6accd4fc](https://linux-hardware.org/?probe=0c6accd4fc) | Oct 19, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [c05a67e739](https://linux-hardware.org/?probe=c05a67e739) | Oct 19, 2023 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [9ad763d3a1](https://linux-hardware.org/?probe=9ad763d3a1) | Oct 18, 2023 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [5064906065](https://linux-hardware.org/?probe=5064906065) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [e7787b05fe](https://linux-hardware.org/?probe=e7787b05fe) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [57dbbcb9f3](https://linux-hardware.org/?probe=57dbbcb9f3) | Oct 18, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [8fb05c37a8](https://linux-hardware.org/?probe=8fb05c37a8) | Oct 18, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8543bed1b3](https://linux-hardware.org/?probe=8543bed1b3) | Oct 17, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [91d1297632](https://linux-hardware.org/?probe=91d1297632) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [c3bd837d33](https://linux-hardware.org/?probe=c3bd837d33) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | Notebook    | [72e348d9bb](https://linux-hardware.org/?probe=72e348d9bb) | Oct 17, 2023 |
| Intel         | DH77KC AAG39641-401         | Desktop     | [abfbdc1640](https://linux-hardware.org/?probe=abfbdc1640) | Oct 17, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [03670e3e53](https://linux-hardware.org/?probe=03670e3e53) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [73e2838408](https://linux-hardware.org/?probe=73e2838408) | Oct 16, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [83cb446c19](https://linux-hardware.org/?probe=83cb446c19) | Oct 16, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d308e7bb0](https://linux-hardware.org/?probe=3d308e7bb0) | Oct 16, 2023 |
| Gigabyte      | GA-78LMT-S2 R2              | Desktop     | [038f59eb24](https://linux-hardware.org/?probe=038f59eb24) | Oct 15, 2023 |
| Dell          | Latitude 5591               | Notebook    | [ef0287bbad](https://linux-hardware.org/?probe=ef0287bbad) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [73f73df16b](https://linux-hardware.org/?probe=73f73df16b) | Oct 14, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [b63b919a75](https://linux-hardware.org/?probe=b63b919a75) | Oct 14, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [4ddde9e92e](https://linux-hardware.org/?probe=4ddde9e92e) | Oct 13, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [17d1931208](https://linux-hardware.org/?probe=17d1931208) | Oct 13, 2023 |
| ASUSTek       | UX430UAR                    | Notebook    | [e66e176aac](https://linux-hardware.org/?probe=e66e176aac) | Oct 13, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [92726caa44](https://linux-hardware.org/?probe=92726caa44) | Oct 12, 2023 |
| Infinix       | ZERO BOOK 13                | Notebook    | [c20c04a240](https://linux-hardware.org/?probe=c20c04a240) | Oct 12, 2023 |
| Acer          | Swift SF315-41              | Notebook    | [804f28fe5b](https://linux-hardware.org/?probe=804f28fe5b) | Oct 12, 2023 |
| Fujitsu       | D2991-A1 S26361-D2991-A1    | Desktop     | [9ca6bc0b08](https://linux-hardware.org/?probe=9ca6bc0b08) | Oct 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [941644a3ed](https://linux-hardware.org/?probe=941644a3ed) | Oct 11, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [605fcbffe8](https://linux-hardware.org/?probe=605fcbffe8) | Oct 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [7aeb935c28](https://linux-hardware.org/?probe=7aeb935c28) | Oct 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [427ca84f59](https://linux-hardware.org/?probe=427ca84f59) | Oct 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a0e076c7f3](https://linux-hardware.org/?probe=a0e076c7f3) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [767f2c26e0](https://linux-hardware.org/?probe=767f2c26e0) | Oct 10, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [50682769d9](https://linux-hardware.org/?probe=50682769d9) | Oct 10, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [2bc390851d](https://linux-hardware.org/?probe=2bc390851d) | Oct 10, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [9799f9f959](https://linux-hardware.org/?probe=9799f9f959) | Oct 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [640744cc70](https://linux-hardware.org/?probe=640744cc70) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [601fd070ec](https://linux-hardware.org/?probe=601fd070ec) | Oct 10, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [265a8e5346](https://linux-hardware.org/?probe=265a8e5346) | Oct 09, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [dd44b0dc9e](https://linux-hardware.org/?probe=dd44b0dc9e) | Oct 08, 2023 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [d8cf994cfe](https://linux-hardware.org/?probe=d8cf994cfe) | Oct 08, 2023 |
| Dell          | Vostro 1450                 | Notebook    | [55334a897d](https://linux-hardware.org/?probe=55334a897d) | Oct 08, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [5f69a24978](https://linux-hardware.org/?probe=5f69a24978) | Oct 08, 2023 |
| Lenovo        | Yoga 7 16ARP8 83BS          | Notebook    | [36d48fe6f7](https://linux-hardware.org/?probe=36d48fe6f7) | Oct 07, 2023 |
| Intel         | H61                         | Desktop     | [a37805d0d3](https://linux-hardware.org/?probe=a37805d0d3) | Oct 07, 2023 |
| HP            | Laptop 15s-fr2xxx           | Notebook    | [2dc2d438ea](https://linux-hardware.org/?probe=2dc2d438ea) | Oct 07, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [9be367f445](https://linux-hardware.org/?probe=9be367f445) | Oct 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [8619f7e43e](https://linux-hardware.org/?probe=8619f7e43e) | Oct 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [0a18c0ff5d](https://linux-hardware.org/?probe=0a18c0ff5d) | Oct 06, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [425aa2b0f7](https://linux-hardware.org/?probe=425aa2b0f7) | Oct 05, 2023 |
| HP            | 198E                        | Desktop     | [a586865b3d](https://linux-hardware.org/?probe=a586865b3d) | Oct 05, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [ddadccf492](https://linux-hardware.org/?probe=ddadccf492) | Oct 05, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [1729f3bfbe](https://linux-hardware.org/?probe=1729f3bfbe) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [ee95e8f5fd](https://linux-hardware.org/?probe=ee95e8f5fd) | Oct 05, 2023 |
| Lenovo        | G40-45 80E1                 | Notebook    | [0cf58ae6b1](https://linux-hardware.org/?probe=0cf58ae6b1) | Oct 05, 2023 |
| Sony          | VPCEB16FG                   | Notebook    | [9e655187a5](https://linux-hardware.org/?probe=9e655187a5) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [bdf9fff544](https://linux-hardware.org/?probe=bdf9fff544) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS06E00     | Notebook    | [549cad8b4f](https://linux-hardware.org/?probe=549cad8b4f) | Oct 05, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ccd7cf5f34](https://linux-hardware.org/?probe=ccd7cf5f34) | Oct 05, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [3639fedec4](https://linux-hardware.org/?probe=3639fedec4) | Oct 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [eebbbc30b8](https://linux-hardware.org/?probe=eebbbc30b8) | Oct 03, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [f332024d38](https://linux-hardware.org/?probe=f332024d38) | Oct 03, 2023 |
| Dell          | Latitude 7400               | Notebook    | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| Acer          | Aspire A314-36M             | Notebook    | [5276b99f12](https://linux-hardware.org/?probe=5276b99f12) | Oct 03, 2023 |
| MSI           | B450M GAMING PLUS           | Desktop     | [8a780dd81c](https://linux-hardware.org/?probe=8a780dd81c) | Oct 02, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [160d49a81f](https://linux-hardware.org/?probe=160d49a81f) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [445e604c2e](https://linux-hardware.org/?probe=445e604c2e) | Oct 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4e0bb2d740](https://linux-hardware.org/?probe=4e0bb2d740) | Oct 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [840bfbb2cb](https://linux-hardware.org/?probe=840bfbb2cb) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [81027151d1](https://linux-hardware.org/?probe=81027151d1) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f9a210173c](https://linux-hardware.org/?probe=f9a210173c) | Oct 01, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [1df2dc7261](https://linux-hardware.org/?probe=1df2dc7261) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| Pegatron      | Eureka3                     | Desktop     | [e5c7ff0c70](https://linux-hardware.org/?probe=e5c7ff0c70) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1c4b1aa68d](https://linux-hardware.org/?probe=1c4b1aa68d) | Sep 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4074a9c221](https://linux-hardware.org/?probe=4074a9c221) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [988f015a89](https://linux-hardware.org/?probe=988f015a89) | Sep 30, 2023 |
| Acer          | Aspire SW3-016              | Notebook    | [62c3855aa7](https://linux-hardware.org/?probe=62c3855aa7) | Sep 30, 2023 |
| Lenovo        | H410                        | Desktop     | [f49a6ce32f](https://linux-hardware.org/?probe=f49a6ce32f) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0c9b2c687a](https://linux-hardware.org/?probe=0c9b2c687a) | Sep 28, 2023 |
| HP            | Notebook                    | Notebook    | [7d55fd8520](https://linux-hardware.org/?probe=7d55fd8520) | Sep 28, 2023 |
| HP            | Notebook                    | Notebook    | [49192b29a6](https://linux-hardware.org/?probe=49192b29a6) | Sep 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d53c8ae481](https://linux-hardware.org/?probe=d53c8ae481) | Sep 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [001d5aa716](https://linux-hardware.org/?probe=001d5aa716) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c5c6c5233a](https://linux-hardware.org/?probe=c5c6c5233a) | Sep 27, 2023 |
| Dell          | Latitude 3410               | Notebook    | [7b326dd690](https://linux-hardware.org/?probe=7b326dd690) | Sep 27, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [afdb68ccfe](https://linux-hardware.org/?probe=afdb68ccfe) | Sep 26, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [d6982725f2](https://linux-hardware.org/?probe=d6982725f2) | Sep 26, 2023 |
| Infinix       | INBOOK Y1 PLUS NEO          | Notebook    | [30998449af](https://linux-hardware.org/?probe=30998449af) | Sep 26, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [cc34f92566](https://linux-hardware.org/?probe=cc34f92566) | Sep 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [17bb721483](https://linux-hardware.org/?probe=17bb721483) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [14766bbd15](https://linux-hardware.org/?probe=14766bbd15) | Sep 26, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [ccdfae441b](https://linux-hardware.org/?probe=ccdfae441b) | Sep 26, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [94ce4b6306](https://linux-hardware.org/?probe=94ce4b6306) | Sep 25, 2023 |
| Lenovo        | B480 20140                  | Notebook    | [960fe0be2b](https://linux-hardware.org/?probe=960fe0be2b) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [9de1c7395f](https://linux-hardware.org/?probe=9de1c7395f) | Sep 25, 2023 |
| Infinix       | INBOOK X1 SLIM              | Notebook    | [bd6f358c7f](https://linux-hardware.org/?probe=bd6f358c7f) | Sep 25, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [7ff4162cbb](https://linux-hardware.org/?probe=7ff4162cbb) | Sep 25, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [55f54a0aeb](https://linux-hardware.org/?probe=55f54a0aeb) | Sep 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b69f53c8fe](https://linux-hardware.org/?probe=b69f53c8fe) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a7eb798aed](https://linux-hardware.org/?probe=a7eb798aed) | Sep 25, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [ac45698051](https://linux-hardware.org/?probe=ac45698051) | Sep 25, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [b42e3e4395](https://linux-hardware.org/?probe=b42e3e4395) | Sep 24, 2023 |
| ASRock        | B150M Pro4/Hyper            | Desktop     | [6bd5055b96](https://linux-hardware.org/?probe=6bd5055b96) | Sep 24, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [fe5f9ad018](https://linux-hardware.org/?probe=fe5f9ad018) | Sep 23, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [4e91084325](https://linux-hardware.org/?probe=4e91084325) | Sep 23, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [f6369d0be5](https://linux-hardware.org/?probe=f6369d0be5) | Sep 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [e2c17f3a64](https://linux-hardware.org/?probe=e2c17f3a64) | Sep 23, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [58b289a69d](https://linux-hardware.org/?probe=58b289a69d) | Sep 23, 2023 |
| Samsung       | 935XDB                      | Notebook    | [a0672b9726](https://linux-hardware.org/?probe=a0672b9726) | Sep 23, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [674c086aa5](https://linux-hardware.org/?probe=674c086aa5) | Sep 22, 2023 |
| HP            | 834F                        | Desktop     | [b69b667f2c](https://linux-hardware.org/?probe=b69b667f2c) | Sep 22, 2023 |
| Getac         | T800G2                      | Tablet      | [fe815f3c1f](https://linux-hardware.org/?probe=fe815f3c1f) | Sep 22, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [67ac6fc0d9](https://linux-hardware.org/?probe=67ac6fc0d9) | Sep 22, 2023 |
| HP            | ProBook 430 G3              | Notebook    | [519a567ecb](https://linux-hardware.org/?probe=519a567ecb) | Sep 22, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [fc49b16c1c](https://linux-hardware.org/?probe=fc49b16c1c) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c00e994c2c](https://linux-hardware.org/?probe=c00e994c2c) | Sep 21, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [874c33c481](https://linux-hardware.org/?probe=874c33c481) | Sep 21, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [af7ac2b917](https://linux-hardware.org/?probe=af7ac2b917) | Sep 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [a085f48523](https://linux-hardware.org/?probe=a085f48523) | Sep 20, 2023 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [0c99fa225e](https://linux-hardware.org/?probe=0c99fa225e) | Sep 20, 2023 |
| Lenovo        | H320 10044                  | Desktop     | [bf4ffce3e9](https://linux-hardware.org/?probe=bf4ffce3e9) | Sep 20, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [f01ce05b1f](https://linux-hardware.org/?probe=f01ce05b1f) | Sep 20, 2023 |
| Lenovo        | G580 20157                  | Notebook    | [9b576274e4](https://linux-hardware.org/?probe=9b576274e4) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [1850488dd1](https://linux-hardware.org/?probe=1850488dd1) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [c122be4331](https://linux-hardware.org/?probe=c122be4331) | Sep 20, 2023 |
| Intel         | DZ68PL AAG42750-301         | Desktop     | [c16c7202a1](https://linux-hardware.org/?probe=c16c7202a1) | Sep 20, 2023 |
| Intel         | H61                         | Desktop     | [82a94f86d2](https://linux-hardware.org/?probe=82a94f86d2) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [00c6b8cced](https://linux-hardware.org/?probe=00c6b8cced) | Sep 20, 2023 |
| Gigabyte      | Z790 AERO G                 | Desktop     | [6ded2501bf](https://linux-hardware.org/?probe=6ded2501bf) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [052438c7dd](https://linux-hardware.org/?probe=052438c7dd) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [a87ec029ab](https://linux-hardware.org/?probe=a87ec029ab) | Sep 19, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6784f50f9d](https://linux-hardware.org/?probe=6784f50f9d) | Sep 19, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [6233a0f825](https://linux-hardware.org/?probe=6233a0f825) | Sep 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [aeffbe0fe5](https://linux-hardware.org/?probe=aeffbe0fe5) | Sep 19, 2023 |
| HP            | Notebook                    | Notebook    | [3c10ef5d72](https://linux-hardware.org/?probe=3c10ef5d72) | Sep 19, 2023 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [da930461ec](https://linux-hardware.org/?probe=da930461ec) | Sep 18, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [a64dc1766a](https://linux-hardware.org/?probe=a64dc1766a) | Sep 18, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [39a50dc7e8](https://linux-hardware.org/?probe=39a50dc7e8) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [cad09f007e](https://linux-hardware.org/?probe=cad09f007e) | Sep 18, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [f6a841ea3d](https://linux-hardware.org/?probe=f6a841ea3d) | Sep 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [5b5eb2a0a5](https://linux-hardware.org/?probe=5b5eb2a0a5) | Sep 18, 2023 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [0460fafb99](https://linux-hardware.org/?probe=0460fafb99) | Sep 17, 2023 |
| Dell          | XPS L501X                   | Notebook    | [13d0075027](https://linux-hardware.org/?probe=13d0075027) | Sep 16, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [06e2986bbc](https://linux-hardware.org/?probe=06e2986bbc) | Sep 16, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [506d025e1e](https://linux-hardware.org/?probe=506d025e1e) | Sep 15, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1c5a009557](https://linux-hardware.org/?probe=1c5a009557) | Sep 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8df91a5efc](https://linux-hardware.org/?probe=8df91a5efc) | Sep 15, 2023 |
| HP            | ENVY 15                     | Notebook    | [c5c9db023b](https://linux-hardware.org/?probe=c5c9db023b) | Sep 15, 2023 |
| HP            | ENVY 15                     | Notebook    | [9741cff4ca](https://linux-hardware.org/?probe=9741cff4ca) | Sep 15, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [71a6a04c4c](https://linux-hardware.org/?probe=71a6a04c4c) | Sep 15, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [bb4b6fe52f](https://linux-hardware.org/?probe=bb4b6fe52f) | Sep 15, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [37e1d06001](https://linux-hardware.org/?probe=37e1d06001) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [b30ec0e0a8](https://linux-hardware.org/?probe=b30ec0e0a8) | Sep 14, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [e1a54edbdc](https://linux-hardware.org/?probe=e1a54edbdc) | Sep 14, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [160685ce41](https://linux-hardware.org/?probe=160685ce41) | Sep 14, 2023 |
| MSI           | Thin GF63 12HW              | Notebook    | [79e6e5fc48](https://linux-hardware.org/?probe=79e6e5fc48) | Sep 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [1703cfdd5e](https://linux-hardware.org/?probe=1703cfdd5e) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e8b1e251a3](https://linux-hardware.org/?probe=e8b1e251a3) | Sep 13, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [deb3ba5bf7](https://linux-hardware.org/?probe=deb3ba5bf7) | Sep 13, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [23ded25239](https://linux-hardware.org/?probe=23ded25239) | Sep 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c2b009d544](https://linux-hardware.org/?probe=c2b009d544) | Sep 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ecc13f9294](https://linux-hardware.org/?probe=ecc13f9294) | Sep 12, 2023 |
| Lenovo        | IDEA 315-15 81WE            | Notebook    | [f148c9218a](https://linux-hardware.org/?probe=f148c9218a) | Sep 12, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [005f0b4e53](https://linux-hardware.org/?probe=005f0b4e53) | Sep 11, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [aabd401f54](https://linux-hardware.org/?probe=aabd401f54) | Sep 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [eb75d89868](https://linux-hardware.org/?probe=eb75d89868) | Sep 11, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [bffb256730](https://linux-hardware.org/?probe=bffb256730) | Sep 11, 2023 |
| Acer          | Predator PH315-54           | Notebook    | [2088909e8a](https://linux-hardware.org/?probe=2088909e8a) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [16b6bd1d3d](https://linux-hardware.org/?probe=16b6bd1d3d) | Sep 09, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [25649c8a92](https://linux-hardware.org/?probe=25649c8a92) | Sep 09, 2023 |
| Dell          | Latitude E6430              | Notebook    | [0ace4858e1](https://linux-hardware.org/?probe=0ace4858e1) | Sep 09, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [bdd270eddd](https://linux-hardware.org/?probe=bdd270eddd) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [f08f8e5ce8](https://linux-hardware.org/?probe=f08f8e5ce8) | Sep 09, 2023 |
| HP            | Laptop 15s-fr1xxx           | Notebook    | [a6e3c47b2d](https://linux-hardware.org/?probe=a6e3c47b2d) | Sep 08, 2023 |
| Intel         | H81                         | Desktop     | [52fa5b7a15](https://linux-hardware.org/?probe=52fa5b7a15) | Sep 08, 2023 |
| Gateway       | NE56R                       | Notebook    | [ec2415b16d](https://linux-hardware.org/?probe=ec2415b16d) | Sep 08, 2023 |
| Gateway       | NE56R                       | Notebook    | [4871fca687](https://linux-hardware.org/?probe=4871fca687) | Sep 08, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [8ebe24476b](https://linux-hardware.org/?probe=8ebe24476b) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [fd7e472e9b](https://linux-hardware.org/?probe=fd7e472e9b) | Sep 07, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [a2fab791b4](https://linux-hardware.org/?probe=a2fab791b4) | Sep 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [003d136012](https://linux-hardware.org/?probe=003d136012) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [24eca3030c](https://linux-hardware.org/?probe=24eca3030c) | Sep 07, 2023 |
| Dell          | Latitude 3520               | Notebook    | [0fa236983e](https://linux-hardware.org/?probe=0fa236983e) | Sep 06, 2023 |
| Dell          | 0KP561                      | Desktop     | [90055b146d](https://linux-hardware.org/?probe=90055b146d) | Sep 06, 2023 |
| Intel         | H81                         | Desktop     | [5a16cea30a](https://linux-hardware.org/?probe=5a16cea30a) | Sep 06, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| Gateway       | NE56R                       | Notebook    | [ade8432ca6](https://linux-hardware.org/?probe=ade8432ca6) | Sep 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b1f7a8316d](https://linux-hardware.org/?probe=b1f7a8316d) | Sep 06, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [586f1d2fa7](https://linux-hardware.org/?probe=586f1d2fa7) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4ed976d4ba](https://linux-hardware.org/?probe=4ed976d4ba) | Sep 06, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [79328b47d8](https://linux-hardware.org/?probe=79328b47d8) | Sep 05, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [bb7f6aed1a](https://linux-hardware.org/?probe=bb7f6aed1a) | Sep 05, 2023 |
| Gateway       | NE56R                       | Notebook    | [be83386f4d](https://linux-hardware.org/?probe=be83386f4d) | Sep 05, 2023 |
| Intel         | H61                         | Desktop     | [d749d1595f](https://linux-hardware.org/?probe=d749d1595f) | Sep 05, 2023 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [613e4acc75](https://linux-hardware.org/?probe=613e4acc75) | Sep 05, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [7c5a59da7b](https://linux-hardware.org/?probe=7c5a59da7b) | Sep 05, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [b595dd4436](https://linux-hardware.org/?probe=b595dd4436) | Sep 05, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [381e87228c](https://linux-hardware.org/?probe=381e87228c) | Sep 04, 2023 |
| Gateway       | NE56R                       | Notebook    | [99b1c83e93](https://linux-hardware.org/?probe=99b1c83e93) | Sep 04, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [f7a6b9d479](https://linux-hardware.org/?probe=f7a6b9d479) | Sep 04, 2023 |
| HP            | 247 G8 Notebook PC          | Notebook    | [74a7d9e304](https://linux-hardware.org/?probe=74a7d9e304) | Sep 04, 2023 |
| Toshiba       | Satellite C850              | Notebook    | [188a672b4d](https://linux-hardware.org/?probe=188a672b4d) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [7b776b30bd](https://linux-hardware.org/?probe=7b776b30bd) | Sep 03, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [733f5cb987](https://linux-hardware.org/?probe=733f5cb987) | Sep 03, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [e0b3a3a55b](https://linux-hardware.org/?probe=e0b3a3a55b) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [69b91f1c46](https://linux-hardware.org/?probe=69b91f1c46) | Sep 03, 2023 |
| HP            | Pavilion dv4                | Notebook    | [8d183fb271](https://linux-hardware.org/?probe=8d183fb271) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [9845368fc2](https://linux-hardware.org/?probe=9845368fc2) | Sep 03, 2023 |
| ASUSTek       | F1A55-M LX PLUS             | Desktop     | [a2aebc52bd](https://linux-hardware.org/?probe=a2aebc52bd) | Sep 03, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | Notebook    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| HP            | ProLiant DL380p Gen8        | Server      | [05c90f0109](https://linux-hardware.org/?probe=05c90f0109) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [2c9f663c14](https://linux-hardware.org/?probe=2c9f663c14) | Sep 01, 2023 |
| HP            | Pavilion g6                 | Notebook    | [0f0960322d](https://linux-hardware.org/?probe=0f0960322d) | Sep 01, 2023 |
| Timi          | Mi NoteBook Pro             | Notebook    | [7d3823ff94](https://linux-hardware.org/?probe=7d3823ff94) | Sep 01, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [ec5d9509f6](https://linux-hardware.org/?probe=ec5d9509f6) | Sep 01, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [929ae155ea](https://linux-hardware.org/?probe=929ae155ea) | Sep 01, 2023 |
| Dell          | Latitude 5400               | Notebook    | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| Unknown       | H110M2                      | Desktop     | [bff031410a](https://linux-hardware.org/?probe=bff031410a) | Aug 31, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [3411b788bc](https://linux-hardware.org/?probe=3411b788bc) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [c3d8f5daca](https://linux-hardware.org/?probe=c3d8f5daca) | Aug 31, 2023 |
| HP            | 339A                        | Desktop     | [6c323fe4d4](https://linux-hardware.org/?probe=6c323fe4d4) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [f94ed7f5d1](https://linux-hardware.org/?probe=f94ed7f5d1) | Aug 31, 2023 |
| HP            | 15                          | Notebook    | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| MSI           | Thin GF63 12VE              | Notebook    | [0615d252af](https://linux-hardware.org/?probe=0615d252af) | Aug 31, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [8adf70b56e](https://linux-hardware.org/?probe=8adf70b56e) | Aug 31, 2023 |
| Intel         | DB85FL AAG89861-201         | Desktop     | [035f2909a1](https://linux-hardware.org/?probe=035f2909a1) | Aug 30, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [f69425a68d](https://linux-hardware.org/?probe=f69425a68d) | Aug 30, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [4bedf20d35](https://linux-hardware.org/?probe=4bedf20d35) | Aug 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [78e163bc13](https://linux-hardware.org/?probe=78e163bc13) | Aug 30, 2023 |
| OEM           | Intel H81                   | Desktop     | [7d179cb8e9](https://linux-hardware.org/?probe=7d179cb8e9) | Aug 30, 2023 |
| Acer          | One Z1402                   | Notebook    | [2e917719ec](https://linux-hardware.org/?probe=2e917719ec) | Aug 29, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [6e4b12a41e](https://linux-hardware.org/?probe=6e4b12a41e) | Aug 29, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [93fd8245ab](https://linux-hardware.org/?probe=93fd8245ab) | Aug 29, 2023 |
| Infinix       | INBOOK X2 SLIM              | Notebook    | [fafc374d46](https://linux-hardware.org/?probe=fafc374d46) | Aug 29, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [9d092039d3](https://linux-hardware.org/?probe=9d092039d3) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | Notebook    | [8a7f22304b](https://linux-hardware.org/?probe=8a7f22304b) | Aug 29, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [65f52f1180](https://linux-hardware.org/?probe=65f52f1180) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | Notebook    | [598458b278](https://linux-hardware.org/?probe=598458b278) | Aug 28, 2023 |
| Intel         | H61                         | Desktop     | [9e5ed4db62](https://linux-hardware.org/?probe=9e5ed4db62) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | Notebook    | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [15b81ebfc0](https://linux-hardware.org/?probe=15b81ebfc0) | Aug 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [a762e96941](https://linux-hardware.org/?probe=a762e96941) | Aug 28, 2023 |
| Dell          | Inspiron 5542               | Notebook    | [70fbf53140](https://linux-hardware.org/?probe=70fbf53140) | Aug 27, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | Notebook    | [79c52635ec](https://linux-hardware.org/?probe=79c52635ec) | Aug 27, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [08f577f854](https://linux-hardware.org/?probe=08f577f854) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [fe02fb8d64](https://linux-hardware.org/?probe=fe02fb8d64) | Aug 27, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [3b5476180b](https://linux-hardware.org/?probe=3b5476180b) | Aug 26, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [1a1924897a](https://linux-hardware.org/?probe=1a1924897a) | Aug 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [04426b4b83](https://linux-hardware.org/?probe=04426b4b83) | Aug 25, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [25c5011587](https://linux-hardware.org/?probe=25c5011587) | Aug 25, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [1fde0105bf](https://linux-hardware.org/?probe=1fde0105bf) | Aug 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f37fa5636](https://linux-hardware.org/?probe=3f37fa5636) | Aug 25, 2023 |
| Dell          | Inspiron N5050              | Notebook    | [4d282e98b2](https://linux-hardware.org/?probe=4d282e98b2) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [c63d6cfab0](https://linux-hardware.org/?probe=c63d6cfab0) | Aug 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5bddf6d37d](https://linux-hardware.org/?probe=5bddf6d37d) | Aug 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [38573350a3](https://linux-hardware.org/?probe=38573350a3) | Aug 23, 2023 |
| Dell          | Vostro 3558                 | Notebook    | [61cb58f13b](https://linux-hardware.org/?probe=61cb58f13b) | Aug 23, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [6c4e1108c1](https://linux-hardware.org/?probe=6c4e1108c1) | Aug 23, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [c8cc960675](https://linux-hardware.org/?probe=c8cc960675) | Aug 21, 2023 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [c16bd959dc](https://linux-hardware.org/?probe=c16bd959dc) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [0b0926bb45](https://linux-hardware.org/?probe=0b0926bb45) | Aug 21, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [b5b7a6d8f8](https://linux-hardware.org/?probe=b5b7a6d8f8) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| ASUSTek       | ROG Strix G712LU            | Notebook    | [7fd51c6d4d](https://linux-hardware.org/?probe=7fd51c6d4d) | Aug 20, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b50e7eb542](https://linux-hardware.org/?probe=b50e7eb542) | Aug 20, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [6d8baa3226](https://linux-hardware.org/?probe=6d8baa3226) | Aug 20, 2023 |
| ASRockRack    | EP2C612D16C-4L              | Desktop     | [61802adf5b](https://linux-hardware.org/?probe=61802adf5b) | Aug 19, 2023 |
| ASRockRack    | EP2C612D16C-4L              | Desktop     | [52d818cdbd](https://linux-hardware.org/?probe=52d818cdbd) | Aug 19, 2023 |
| Lenovo        | ThinkPad E470 20H2S0XB00    | Notebook    | [517d8c57d2](https://linux-hardware.org/?probe=517d8c57d2) | Aug 19, 2023 |
| Dell          | Vostro 3401                 | Notebook    | [792ea03809](https://linux-hardware.org/?probe=792ea03809) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [80b304814d](https://linux-hardware.org/?probe=80b304814d) | Aug 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [dee14abe77](https://linux-hardware.org/?probe=dee14abe77) | Aug 18, 2023 |
| Lenovo        | ThinkPad X230 23253B3       | Notebook    | [8da8bfe394](https://linux-hardware.org/?probe=8da8bfe394) | Aug 18, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [c95ab5ea6e](https://linux-hardware.org/?probe=c95ab5ea6e) | Aug 18, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [5369c283ad](https://linux-hardware.org/?probe=5369c283ad) | Aug 18, 2023 |
| Infinix       | INBOOK X1 NEO               | Notebook    | [bb08f7158b](https://linux-hardware.org/?probe=bb08f7158b) | Aug 18, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a5a12b8086](https://linux-hardware.org/?probe=a5a12b8086) | Aug 17, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [18c9f279a1](https://linux-hardware.org/?probe=18c9f279a1) | Aug 17, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [6c31be997f](https://linux-hardware.org/?probe=6c31be997f) | Aug 17, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [78d5f440ff](https://linux-hardware.org/?probe=78d5f440ff) | Aug 17, 2023 |
| Dell          | Latitude E6520              | Notebook    | [15420bd102](https://linux-hardware.org/?probe=15420bd102) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [145e7ceb96](https://linux-hardware.org/?probe=145e7ceb96) | Aug 16, 2023 |
| Acer          | Swift SF314-510G            | Notebook    | [11a4bc0bac](https://linux-hardware.org/?probe=11a4bc0bac) | Aug 16, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [12f64c8222](https://linux-hardware.org/?probe=12f64c8222) | Aug 16, 2023 |
| Dell          | Latitude 3520               | Notebook    | [33d3220fa3](https://linux-hardware.org/?probe=33d3220fa3) | Aug 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [8298417da7](https://linux-hardware.org/?probe=8298417da7) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [ff958dc821](https://linux-hardware.org/?probe=ff958dc821) | Aug 16, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [859e36f237](https://linux-hardware.org/?probe=859e36f237) | Aug 16, 2023 |
| Dell          | Latitude 5300               | Notebook    | [506c05d30c](https://linux-hardware.org/?probe=506c05d30c) | Aug 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [ea9845e55b](https://linux-hardware.org/?probe=ea9845e55b) | Aug 15, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [31beedbfba](https://linux-hardware.org/?probe=31beedbfba) | Aug 15, 2023 |
| Lenovo        | Legion Y740-15IRH 81UF      | Notebook    | [2b0ec42ffb](https://linux-hardware.org/?probe=2b0ec42ffb) | Aug 15, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [5a2c741f84](https://linux-hardware.org/?probe=5a2c741f84) | Aug 14, 2023 |
| Lenovo        | ThinkCentre M58p 7220AR1    | Desktop     | [2bc1532fb7](https://linux-hardware.org/?probe=2bc1532fb7) | Aug 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [28be66d0b1](https://linux-hardware.org/?probe=28be66d0b1) | Aug 14, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [cfc638b4b2](https://linux-hardware.org/?probe=cfc638b4b2) | Aug 14, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [dea6e2f8b8](https://linux-hardware.org/?probe=dea6e2f8b8) | Aug 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1c643cc90f](https://linux-hardware.org/?probe=1c643cc90f) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [5286543cae](https://linux-hardware.org/?probe=5286543cae) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [464dc037bd](https://linux-hardware.org/?probe=464dc037bd) | Aug 13, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [f98e22f722](https://linux-hardware.org/?probe=f98e22f722) | Aug 13, 2023 |
| Dell          | 0100P6 A01                  | Desktop     | [2cf993001c](https://linux-hardware.org/?probe=2cf993001c) | Aug 13, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [1034423357](https://linux-hardware.org/?probe=1034423357) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e0e0c962d5](https://linux-hardware.org/?probe=e0e0c962d5) | Aug 12, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [c336f9aa8c](https://linux-hardware.org/?probe=c336f9aa8c) | Aug 11, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [7d31344218](https://linux-hardware.org/?probe=7d31344218) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [980f6773f8](https://linux-hardware.org/?probe=980f6773f8) | Aug 10, 2023 |
| Dell          | 0YF8P5 A00                  | Desktop     | [93f35a6d26](https://linux-hardware.org/?probe=93f35a6d26) | Aug 10, 2023 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [479f066821](https://linux-hardware.org/?probe=479f066821) | Aug 10, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [646d098c58](https://linux-hardware.org/?probe=646d098c58) | Aug 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e703bb179f](https://linux-hardware.org/?probe=e703bb179f) | Aug 10, 2023 |
| Valve         | Jupiter                     | Notebook    | [eee501d93c](https://linux-hardware.org/?probe=eee501d93c) | Aug 09, 2023 |
| Dell          | 06CJMN A00                  | Desktop     | [cead9bd601](https://linux-hardware.org/?probe=cead9bd601) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [eec04bec1d](https://linux-hardware.org/?probe=eec04bec1d) | Aug 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c9c978701a](https://linux-hardware.org/?probe=c9c978701a) | Aug 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [f69459e15a](https://linux-hardware.org/?probe=f69459e15a) | Aug 08, 2023 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | Desktop     | [6ffda81a5e](https://linux-hardware.org/?probe=6ffda81a5e) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [58446ba97c](https://linux-hardware.org/?probe=58446ba97c) | Aug 08, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [2335e10b59](https://linux-hardware.org/?probe=2335e10b59) | Aug 08, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [d91d6193e6](https://linux-hardware.org/?probe=d91d6193e6) | Aug 07, 2023 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [608c3967b2](https://linux-hardware.org/?probe=608c3967b2) | Aug 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | Notebook    | [ebcf58253e](https://linux-hardware.org/?probe=ebcf58253e) | Aug 07, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [8dae611904](https://linux-hardware.org/?probe=8dae611904) | Aug 06, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [91376cc583](https://linux-hardware.org/?probe=91376cc583) | Aug 06, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [bc55c09547](https://linux-hardware.org/?probe=bc55c09547) | Aug 06, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [44d851d327](https://linux-hardware.org/?probe=44d851d327) | Aug 06, 2023 |
| Dell          | Inspiron 7572               | Notebook    | [2509709a1e](https://linux-hardware.org/?probe=2509709a1e) | Aug 06, 2023 |
| Dell          | Precision 3571              | Notebook    | [fdbbd33ee6](https://linux-hardware.org/?probe=fdbbd33ee6) | Aug 06, 2023 |
| Dell          | Precision 3571              | Notebook    | [76de48bd02](https://linux-hardware.org/?probe=76de48bd02) | Aug 06, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6af70944d8](https://linux-hardware.org/?probe=6af70944d8) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [1790fa9d72](https://linux-hardware.org/?probe=1790fa9d72) | Aug 05, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [1e157ae535](https://linux-hardware.org/?probe=1e157ae535) | Aug 05, 2023 |
| HP            | 15                          | Notebook    | [77ae1d8e7e](https://linux-hardware.org/?probe=77ae1d8e7e) | Aug 05, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [771a45e46f](https://linux-hardware.org/?probe=771a45e46f) | Aug 05, 2023 |
| Fujitsu       | LIFEBOOK LH532              | Notebook    | [ba3a2e1773](https://linux-hardware.org/?probe=ba3a2e1773) | Aug 04, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [c5ea71f927](https://linux-hardware.org/?probe=c5ea71f927) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [082f92da07](https://linux-hardware.org/?probe=082f92da07) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [1078db460a](https://linux-hardware.org/?probe=1078db460a) | Aug 04, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f27f9b2a7f](https://linux-hardware.org/?probe=f27f9b2a7f) | Aug 03, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [8193f810ab](https://linux-hardware.org/?probe=8193f810ab) | Aug 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [0cf8e99478](https://linux-hardware.org/?probe=0cf8e99478) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [38f33f3878](https://linux-hardware.org/?probe=38f33f3878) | Aug 03, 2023 |
| OEM           | Intel H81                   | Desktop     | [82606b5050](https://linux-hardware.org/?probe=82606b5050) | Aug 03, 2023 |
| Alienware     | 14                          | Notebook    | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | Notebook                    | Notebook    | [258f6a82ad](https://linux-hardware.org/?probe=258f6a82ad) | Aug 02, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [97d2508df2](https://linux-hardware.org/?probe=97d2508df2) | Aug 02, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [2019699cac](https://linux-hardware.org/?probe=2019699cac) | Aug 02, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [5523e61097](https://linux-hardware.org/?probe=5523e61097) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [32d205bbdf](https://linux-hardware.org/?probe=32d205bbdf) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a0270160ad](https://linux-hardware.org/?probe=a0270160ad) | Aug 02, 2023 |
| Lenovo        | Bantry CRB SDK0E50510 WI... | Desktop     | [69cd0aae71](https://linux-hardware.org/?probe=69cd0aae71) | Aug 02, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [6fe0b53a1b](https://linux-hardware.org/?probe=6fe0b53a1b) | Aug 02, 2023 |
| Dell          | Latitude E7470              | Notebook    | [d377538364](https://linux-hardware.org/?probe=d377538364) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [5650f66cd4](https://linux-hardware.org/?probe=5650f66cd4) | Jul 31, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [ff6816b285](https://linux-hardware.org/?probe=ff6816b285) | Jul 31, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [f641b9c622](https://linux-hardware.org/?probe=f641b9c622) | Jul 30, 2023 |
| Dell          | Latitude E5270              | Notebook    | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [d9d3f5bce4](https://linux-hardware.org/?probe=d9d3f5bce4) | Jul 30, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [20d5d0a3ad](https://linux-hardware.org/?probe=20d5d0a3ad) | Jul 30, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [eff9350e7f](https://linux-hardware.org/?probe=eff9350e7f) | Jul 29, 2023 |
| Lenovo        | 3132 NOK                    | Desktop     | [6ab9975946](https://linux-hardware.org/?probe=6ab9975946) | Jul 29, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [6a6420b23e](https://linux-hardware.org/?probe=6a6420b23e) | Jul 29, 2023 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [bc92202f16](https://linux-hardware.org/?probe=bc92202f16) | Jul 29, 2023 |
| Dell          | Precision 3550              | Notebook    | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | Notebook    | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [2f6969a3c9](https://linux-hardware.org/?probe=2f6969a3c9) | Jul 27, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [d6a4c29101](https://linux-hardware.org/?probe=d6a4c29101) | Jul 27, 2023 |
| Dell          | 0W7JN5 A01                  | Server      | [8f86e6220c](https://linux-hardware.org/?probe=8f86e6220c) | Jul 27, 2023 |
| Dell          | 0W7JN5 A01                  | Server      | [568da91aee](https://linux-hardware.org/?probe=568da91aee) | Jul 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CJC... | Notebook    | [d7fa33e7b1](https://linux-hardware.org/?probe=d7fa33e7b1) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [1bac11c715](https://linux-hardware.org/?probe=1bac11c715) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [1409af2a38](https://linux-hardware.org/?probe=1409af2a38) | Jul 26, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [2c7364f005](https://linux-hardware.org/?probe=2c7364f005) | Jul 26, 2023 |
| HP            | 87A4 10100                  | All in one  | [99d5e60209](https://linux-hardware.org/?probe=99d5e60209) | Jul 26, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [866a4197cd](https://linux-hardware.org/?probe=866a4197cd) | Jul 26, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [a6abe36eef](https://linux-hardware.org/?probe=a6abe36eef) | Jul 26, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [8a297cb644](https://linux-hardware.org/?probe=8a297cb644) | Jul 26, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [aa34907e3a](https://linux-hardware.org/?probe=aa34907e3a) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | Notebook    | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ENVY Notebook               | Notebook    | [9ab8362949](https://linux-hardware.org/?probe=9ab8362949) | Jul 25, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [e1fea727ff](https://linux-hardware.org/?probe=e1fea727ff) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [61646d77f1](https://linux-hardware.org/?probe=61646d77f1) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [8377b87a66](https://linux-hardware.org/?probe=8377b87a66) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [8ecb2eb1fc](https://linux-hardware.org/?probe=8ecb2eb1fc) | Jul 24, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [d9f18f8f28](https://linux-hardware.org/?probe=d9f18f8f28) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [e822964466](https://linux-hardware.org/?probe=e822964466) | Jul 24, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [313f3aa210](https://linux-hardware.org/?probe=313f3aa210) | Jul 23, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [d47fdd358d](https://linux-hardware.org/?probe=d47fdd358d) | Jul 23, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [545d840e2f](https://linux-hardware.org/?probe=545d840e2f) | Jul 23, 2023 |
| Dell          | Latitude 3490               | Notebook    | [8988026686](https://linux-hardware.org/?probe=8988026686) | Jul 23, 2023 |
| Dell          | Latitude 3490               | Notebook    | [b7f8f886f8](https://linux-hardware.org/?probe=b7f8f886f8) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [6c0c0671df](https://linux-hardware.org/?probe=6c0c0671df) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cc08425e5b](https://linux-hardware.org/?probe=cc08425e5b) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Timi          | Mi NoteBook Horizon Edit... | Notebook    | [72a5dfb7cd](https://linux-hardware.org/?probe=72a5dfb7cd) | Jul 21, 2023 |
| Dell          | 0NKW6Y A00                  | Desktop     | [a331a92532](https://linux-hardware.org/?probe=a331a92532) | Jul 21, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [33150ea27b](https://linux-hardware.org/?probe=33150ea27b) | Jul 21, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [6bb2b5bfb6](https://linux-hardware.org/?probe=6bb2b5bfb6) | Jul 20, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [061efe2135](https://linux-hardware.org/?probe=061efe2135) | Jul 20, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [18a6e9f055](https://linux-hardware.org/?probe=18a6e9f055) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| AVITA         | NS14A6                      | Notebook    | [594afbeb74](https://linux-hardware.org/?probe=594afbeb74) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [77468bcff7](https://linux-hardware.org/?probe=77468bcff7) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [eb7b37c1d2](https://linux-hardware.org/?probe=eb7b37c1d2) | Jul 19, 2023 |
| HP            | Notebook                    | Notebook    | [2ccf016245](https://linux-hardware.org/?probe=2ccf016245) | Jul 19, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [06e511f834](https://linux-hardware.org/?probe=06e511f834) | Jul 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [38c5f4d547](https://linux-hardware.org/?probe=38c5f4d547) | Jul 19, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [0c537839b2](https://linux-hardware.org/?probe=0c537839b2) | Jul 19, 2023 |
| Unknown       | G41 Series                  | Desktop     | [5890a777c5](https://linux-hardware.org/?probe=5890a777c5) | Jul 19, 2023 |
| Dell          | Precision 3581              | Notebook    | [68d58784d5](https://linux-hardware.org/?probe=68d58784d5) | Jul 18, 2023 |
| Dell          | Latitude 5480               | Notebook    | [30aaaf3ba8](https://linux-hardware.org/?probe=30aaaf3ba8) | Jul 18, 2023 |
| Dell          | Latitude 3590               | Notebook    | [6386a869e5](https://linux-hardware.org/?probe=6386a869e5) | Jul 18, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [3d0b2577a1](https://linux-hardware.org/?probe=3d0b2577a1) | Jul 18, 2023 |
| Dell          | Latitude 7480               | Notebook    | [83caa544f7](https://linux-hardware.org/?probe=83caa544f7) | Jul 18, 2023 |
| Dell          | Latitude 7480               | Notebook    | [526e020c94](https://linux-hardware.org/?probe=526e020c94) | Jul 18, 2023 |
| Dell          | 0XFWHV A00                  | Desktop     | [0c229a1245](https://linux-hardware.org/?probe=0c229a1245) | Jul 18, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [5b68d7d6e2](https://linux-hardware.org/?probe=5b68d7d6e2) | Jul 16, 2023 |
| Intel         | DH61BF AAG81311-102         | Desktop     | [bc2e347565](https://linux-hardware.org/?probe=bc2e347565) | Jul 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| HP            | 15                          | Notebook    | [73b0c0312f](https://linux-hardware.org/?probe=73b0c0312f) | Jul 15, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [94f963ff8c](https://linux-hardware.org/?probe=94f963ff8c) | Jul 15, 2023 |
| POWERX        | G41                         | Desktop     | [70a6d4e6bf](https://linux-hardware.org/?probe=70a6d4e6bf) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [b8481d7a4c](https://linux-hardware.org/?probe=b8481d7a4c) | Jul 14, 2023 |
| Dell          | Latitude 5480               | Notebook    | [c74dc748f5](https://linux-hardware.org/?probe=c74dc748f5) | Jul 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1e2b959156](https://linux-hardware.org/?probe=1e2b959156) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [e042e7c94e](https://linux-hardware.org/?probe=e042e7c94e) | Jul 14, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b8b0b27baf](https://linux-hardware.org/?probe=b8b0b27baf) | Jul 14, 2023 |
| HP            | 86F3 00100                  | All in one  | [3ab66add04](https://linux-hardware.org/?probe=3ab66add04) | Jul 14, 2023 |
| HP            | 86F3 00100                  | All in one  | [95577f518a](https://linux-hardware.org/?probe=95577f518a) | Jul 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [76513f6a7d](https://linux-hardware.org/?probe=76513f6a7d) | Jul 14, 2023 |
| Gigabyte      | B550 GAMING X               | Desktop     | [67b2bb6155](https://linux-hardware.org/?probe=67b2bb6155) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [934947072a](https://linux-hardware.org/?probe=934947072a) | Jul 13, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [d5079cefe1](https://linux-hardware.org/?probe=d5079cefe1) | Jul 13, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [d22ab22240](https://linux-hardware.org/?probe=d22ab22240) | Jul 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [b31130eea6](https://linux-hardware.org/?probe=b31130eea6) | Jul 13, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [04c4e233af](https://linux-hardware.org/?probe=04c4e233af) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [949ca22bb2](https://linux-hardware.org/?probe=949ca22bb2) | Jul 12, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3532802c06](https://linux-hardware.org/?probe=3532802c06) | Jul 12, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [f3c9995017](https://linux-hardware.org/?probe=f3c9995017) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [aea754f076](https://linux-hardware.org/?probe=aea754f076) | Jul 11, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [995e13dee9](https://linux-hardware.org/?probe=995e13dee9) | Jul 11, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [05f889dc1a](https://linux-hardware.org/?probe=05f889dc1a) | Jul 11, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [ad7b13940b](https://linux-hardware.org/?probe=ad7b13940b) | Jul 11, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7a8f3c985f](https://linux-hardware.org/?probe=7a8f3c985f) | Jul 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [76d89b3b3b](https://linux-hardware.org/?probe=76d89b3b3b) | Jul 11, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [50ed801045](https://linux-hardware.org/?probe=50ed801045) | Jul 11, 2023 |
| HP            | Pavilion - 14-CE2068ST      | Notebook    | [bdf8b67813](https://linux-hardware.org/?probe=bdf8b67813) | Jul 10, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [806e14ad19](https://linux-hardware.org/?probe=806e14ad19) | Jul 10, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [784f886357](https://linux-hardware.org/?probe=784f886357) | Jul 10, 2023 |
| Gigabyte      | B365M DS3H WIFI             | Desktop     | [150b2a2675](https://linux-hardware.org/?probe=150b2a2675) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | Desktop     | [a887a01dd7](https://linux-hardware.org/?probe=a887a01dd7) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [3a1baa8f6c](https://linux-hardware.org/?probe=3a1baa8f6c) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [a1c37a6a4b](https://linux-hardware.org/?probe=a1c37a6a4b) | Jul 09, 2023 |
| Intel         | H61                         | Desktop     | [11e024727c](https://linux-hardware.org/?probe=11e024727c) | Jul 09, 2023 |
| MSI           | Z97 GUARD-PRO               | Desktop     | [298da90a40](https://linux-hardware.org/?probe=298da90a40) | Jul 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| Dell          | Latitude E5440              | Notebook    | [9b4a70fe2b](https://linux-hardware.org/?probe=9b4a70fe2b) | Jul 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [629f165835](https://linux-hardware.org/?probe=629f165835) | Jul 07, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [b7459d1653](https://linux-hardware.org/?probe=b7459d1653) | Jul 07, 2023 |
| HP            | ProBook 4525s               | Notebook    | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| HP            | Laptop                      | Notebook    | [30a1d8ec1c](https://linux-hardware.org/?probe=30a1d8ec1c) | Jul 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [e555b073b5](https://linux-hardware.org/?probe=e555b073b5) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [b11fe33b8c](https://linux-hardware.org/?probe=b11fe33b8c) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [f5f96d51ed](https://linux-hardware.org/?probe=f5f96d51ed) | Jul 05, 2023 |
| HP            | 339A                        | Desktop     | [e746807776](https://linux-hardware.org/?probe=e746807776) | Jul 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [ca637a5884](https://linux-hardware.org/?probe=ca637a5884) | Jul 05, 2023 |
| HP            | Laptop 14s-ef1xxx           | Notebook    | [14e321559e](https://linux-hardware.org/?probe=14e321559e) | Jul 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [a889efa719](https://linux-hardware.org/?probe=a889efa719) | Jul 04, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [86c82575ec](https://linux-hardware.org/?probe=86c82575ec) | Jul 04, 2023 |
| Dell          | Precision 3581              | Notebook    | [1d4db3cec3](https://linux-hardware.org/?probe=1d4db3cec3) | Jul 03, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5634ff05d5](https://linux-hardware.org/?probe=5634ff05d5) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [dfd66d3d07](https://linux-hardware.org/?probe=dfd66d3d07) | Jul 03, 2023 |
| ASUSTek       | X541UAK                     | Notebook    | [c4dcbea71d](https://linux-hardware.org/?probe=c4dcbea71d) | Jul 03, 2023 |
| HP            | 861A                        | Desktop     | [0531675f82](https://linux-hardware.org/?probe=0531675f82) | Jul 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [da24c07da6](https://linux-hardware.org/?probe=da24c07da6) | Jul 02, 2023 |
| Gigabyte      | GA-H61M-S                   | Desktop     | [351a27ff5e](https://linux-hardware.org/?probe=351a27ff5e) | Jul 02, 2023 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [71aa2fd160](https://linux-hardware.org/?probe=71aa2fd160) | Jul 02, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [09c7b86b2c](https://linux-hardware.org/?probe=09c7b86b2c) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [835f3a390f](https://linux-hardware.org/?probe=835f3a390f) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | Notebook    | [3271b3b559](https://linux-hardware.org/?probe=3271b3b559) | Jul 02, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [a8caf9af8e](https://linux-hardware.org/?probe=a8caf9af8e) | Jul 02, 2023 |
| ASRock        | B150M Pro4/Hyper            | Desktop     | [84eee16dd5](https://linux-hardware.org/?probe=84eee16dd5) | Jul 01, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [0c4c59cf86](https://linux-hardware.org/?probe=0c4c59cf86) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [d0fc2ea58e](https://linux-hardware.org/?probe=d0fc2ea58e) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [8b5dc3456b](https://linux-hardware.org/?probe=8b5dc3456b) | Jul 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [0aed51f639](https://linux-hardware.org/?probe=0aed51f639) | Jul 01, 2023 |
| Infinix       | INBOOK X2 PLUS              | Notebook    | [9a74f19725](https://linux-hardware.org/?probe=9a74f19725) | Jul 01, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [f127804b4a](https://linux-hardware.org/?probe=f127804b4a) | Jun 30, 2023 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [5ac29ea67f](https://linux-hardware.org/?probe=5ac29ea67f) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [10467d9f3e](https://linux-hardware.org/?probe=10467d9f3e) | Jun 30, 2023 |
| HP            | 15                          | Notebook    | [2d80407689](https://linux-hardware.org/?probe=2d80407689) | Jun 30, 2023 |
| HP            | 15                          | Notebook    | [398d659d8c](https://linux-hardware.org/?probe=398d659d8c) | Jun 30, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [602d134940](https://linux-hardware.org/?probe=602d134940) | Jun 30, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [eab5331f66](https://linux-hardware.org/?probe=eab5331f66) | Jun 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [0ad496c06d](https://linux-hardware.org/?probe=0ad496c06d) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0f0defbd9c](https://linux-hardware.org/?probe=0f0defbd9c) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [0086cae258](https://linux-hardware.org/?probe=0086cae258) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [5d30ae9d05](https://linux-hardware.org/?probe=5d30ae9d05) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6a29eda577](https://linux-hardware.org/?probe=6a29eda577) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [bf4abd6e9e](https://linux-hardware.org/?probe=bf4abd6e9e) | Jun 28, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [4baea798b1](https://linux-hardware.org/?probe=4baea798b1) | Jun 27, 2023 |
| Acer          | Swift SFG14-71              | Notebook    | [f66ac636e6](https://linux-hardware.org/?probe=f66ac636e6) | Jun 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [fc7f2b378b](https://linux-hardware.org/?probe=fc7f2b378b) | Jun 27, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [d6b3d5cb90](https://linux-hardware.org/?probe=d6b3d5cb90) | Jun 27, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [13c7f88d66](https://linux-hardware.org/?probe=13c7f88d66) | Jun 26, 2023 |
| ASUSTek       | H61M-CS                     | Desktop     | [2878c06857](https://linux-hardware.org/?probe=2878c06857) | Jun 26, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [08ba4bf92b](https://linux-hardware.org/?probe=08ba4bf92b) | Jun 26, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [3dc15705c8](https://linux-hardware.org/?probe=3dc15705c8) | Jun 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA    | Notebook    | [8a764f6629](https://linux-hardware.org/?probe=8a764f6629) | Jun 26, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [aeb1c6b8d2](https://linux-hardware.org/?probe=aeb1c6b8d2) | Jun 26, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1a21c582de](https://linux-hardware.org/?probe=1a21c582de) | Jun 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [23499b1838](https://linux-hardware.org/?probe=23499b1838) | Jun 25, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1fc0c8e328](https://linux-hardware.org/?probe=1fc0c8e328) | Jun 25, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [2f5357533f](https://linux-hardware.org/?probe=2f5357533f) | Jun 25, 2023 |
| Lenovo        | E41-55 82FJ                 | Notebook    | [f725e1bd1a](https://linux-hardware.org/?probe=f725e1bd1a) | Jun 25, 2023 |
| Dell          | Precision M6400             | Notebook    | [b68c09e274](https://linux-hardware.org/?probe=b68c09e274) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Precision 5540              | Notebook    | [7d6c1fe39d](https://linux-hardware.org/?probe=7d6c1fe39d) | Jun 25, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [7f8217bce2](https://linux-hardware.org/?probe=7f8217bce2) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5679200535](https://linux-hardware.org/?probe=5679200535) | Jun 24, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [9279842ec3](https://linux-hardware.org/?probe=9279842ec3) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [628fca0448](https://linux-hardware.org/?probe=628fca0448) | Jun 24, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [77473ea84c](https://linux-hardware.org/?probe=77473ea84c) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [de0580cf77](https://linux-hardware.org/?probe=de0580cf77) | Jun 24, 2023 |
| HP            | Pavilion g6                 | Notebook    | [b8d79ce295](https://linux-hardware.org/?probe=b8d79ce295) | Jun 24, 2023 |
| Dell          | G5 5505                     | Notebook    | [dbe52869d7](https://linux-hardware.org/?probe=dbe52869d7) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [515f5a5392](https://linux-hardware.org/?probe=515f5a5392) | Jun 23, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [15fd4078ea](https://linux-hardware.org/?probe=15fd4078ea) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [4d9c9f9bd0](https://linux-hardware.org/?probe=4d9c9f9bd0) | Jun 23, 2023 |
| Dell          | G5 5505                     | Notebook    | [f435440e91](https://linux-hardware.org/?probe=f435440e91) | Jun 23, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [5c76172491](https://linux-hardware.org/?probe=5c76172491) | Jun 22, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | Notebook    | [110c366456](https://linux-hardware.org/?probe=110c366456) | Jun 22, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7cc301b3f7](https://linux-hardware.org/?probe=7cc301b3f7) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [ab7c961e2b](https://linux-hardware.org/?probe=ab7c961e2b) | Jun 21, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [1ba2e18bc1](https://linux-hardware.org/?probe=1ba2e18bc1) | Jun 21, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [c80413d259](https://linux-hardware.org/?probe=c80413d259) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Dell          | Precision 5560              | Notebook    | [ee53248c8c](https://linux-hardware.org/?probe=ee53248c8c) | Jun 20, 2023 |
| Intel         | H61                         | Desktop     | [d8de2bb1a7](https://linux-hardware.org/?probe=d8de2bb1a7) | Jun 20, 2023 |
| POWERX        | G41                         | Desktop     | [5d1b37ec3a](https://linux-hardware.org/?probe=5d1b37ec3a) | Jun 20, 2023 |
| Lenovo        | ThinkPad T460s 20F9005BU... | Notebook    | [59a527c934](https://linux-hardware.org/?probe=59a527c934) | Jun 20, 2023 |
| Timi          | RedmiBook 15                | Notebook    | [f975205ebd](https://linux-hardware.org/?probe=f975205ebd) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [6dea148dd7](https://linux-hardware.org/?probe=6dea148dd7) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [63381e724a](https://linux-hardware.org/?probe=63381e724a) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [4b20fef62f](https://linux-hardware.org/?probe=4b20fef62f) | Jun 19, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [e195f838c3](https://linux-hardware.org/?probe=e195f838c3) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [94999d2965](https://linux-hardware.org/?probe=94999d2965) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [acaa27666b](https://linux-hardware.org/?probe=acaa27666b) | Jun 17, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [a585caa218](https://linux-hardware.org/?probe=a585caa218) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [4907b6927a](https://linux-hardware.org/?probe=4907b6927a) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [edd82d072b](https://linux-hardware.org/?probe=edd82d072b) | Jun 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [ccb49000fa](https://linux-hardware.org/?probe=ccb49000fa) | Jun 16, 2023 |
| Unknown       | G41 Series                  | Desktop     | [07122155fa](https://linux-hardware.org/?probe=07122155fa) | Jun 15, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [20ddd7a28b](https://linux-hardware.org/?probe=20ddd7a28b) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [69048c54c9](https://linux-hardware.org/?probe=69048c54c9) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [fe39c9b2ce](https://linux-hardware.org/?probe=fe39c9b2ce) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [2b4d088695](https://linux-hardware.org/?probe=2b4d088695) | Jun 14, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [a5143e68f8](https://linux-hardware.org/?probe=a5143e68f8) | Jun 14, 2023 |
| Dell          | 0VNM11 A01                  | Desktop     | [138e3687ac](https://linux-hardware.org/?probe=138e3687ac) | Jun 14, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [fffb0a25f1](https://linux-hardware.org/?probe=fffb0a25f1) | Jun 13, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [1ede32fb28](https://linux-hardware.org/?probe=1ede32fb28) | Jun 13, 2023 |
| Dell          | XPS 17 9710                 | Notebook    | [9ab7a065c4](https://linux-hardware.org/?probe=9ab7a065c4) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [5e636c4693](https://linux-hardware.org/?probe=5e636c4693) | Jun 13, 2023 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [c0e73c1ff8](https://linux-hardware.org/?probe=c0e73c1ff8) | Jun 12, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [e6713db4c3](https://linux-hardware.org/?probe=e6713db4c3) | Jun 12, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [f31365f369](https://linux-hardware.org/?probe=f31365f369) | Jun 12, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [ffd9da63dd](https://linux-hardware.org/?probe=ffd9da63dd) | Jun 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [0d80451f80](https://linux-hardware.org/?probe=0d80451f80) | Jun 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [b25c3a4ecb](https://linux-hardware.org/?probe=b25c3a4ecb) | Jun 11, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [a192769f1b](https://linux-hardware.org/?probe=a192769f1b) | Jun 11, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [66aa96212a](https://linux-hardware.org/?probe=66aa96212a) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [864729436a](https://linux-hardware.org/?probe=864729436a) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [7ab0866235](https://linux-hardware.org/?probe=7ab0866235) | Jun 10, 2023 |
| Intel         | DH55TC AAE70932-302         | Desktop     | [6090a53f8a](https://linux-hardware.org/?probe=6090a53f8a) | Jun 10, 2023 |
| HP            | 339A                        | Desktop     | [348ce53f71](https://linux-hardware.org/?probe=348ce53f71) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [1eeb12a5ca](https://linux-hardware.org/?probe=1eeb12a5ca) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [e46f2fe66e](https://linux-hardware.org/?probe=e46f2fe66e) | Jun 10, 2023 |
| HP            | G42                         | Notebook    | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [5dd8c1fed8](https://linux-hardware.org/?probe=5dd8c1fed8) | Jun 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [b23bc1dc48](https://linux-hardware.org/?probe=b23bc1dc48) | Jun 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | Notebook    | [fb6aca39d9](https://linux-hardware.org/?probe=fb6aca39d9) | Jun 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [e103817b2d](https://linux-hardware.org/?probe=e103817b2d) | Jun 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [6062ee64a9](https://linux-hardware.org/?probe=6062ee64a9) | Jun 07, 2023 |
| Dell          | G15 5511                    | Notebook    | [ddee46cbfa](https://linux-hardware.org/?probe=ddee46cbfa) | Jun 07, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [14016f0f6f](https://linux-hardware.org/?probe=14016f0f6f) | Jun 07, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | Notebook    | [721ff5908a](https://linux-hardware.org/?probe=721ff5908a) | Jun 06, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Dell          | Latitude E6430              | Notebook    | [bfa5da5406](https://linux-hardware.org/?probe=bfa5da5406) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [1e5a50fa47](https://linux-hardware.org/?probe=1e5a50fa47) | Jun 06, 2023 |
| Acer          | Aspire A314-36M             | Notebook    | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| HP            | 3397                        | Desktop     | [f85e642ee3](https://linux-hardware.org/?probe=f85e642ee3) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [503bc1f4cc](https://linux-hardware.org/?probe=503bc1f4cc) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [31a814cd0e](https://linux-hardware.org/?probe=31a814cd0e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [2a612dc748](https://linux-hardware.org/?probe=2a612dc748) | Jun 06, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [5159be9e2b](https://linux-hardware.org/?probe=5159be9e2b) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Sony          | VPCEH25EN                   | Notebook    | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [ea59ba572e](https://linux-hardware.org/?probe=ea59ba572e) | Jun 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [6528b4bffe](https://linux-hardware.org/?probe=6528b4bffe) | Jun 05, 2023 |
| Dell          | Latitude 3460               | Notebook    | [1a92cd0779](https://linux-hardware.org/?probe=1a92cd0779) | Jun 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [dbc9b8df0b](https://linux-hardware.org/?probe=dbc9b8df0b) | Jun 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [ceab55a00c](https://linux-hardware.org/?probe=ceab55a00c) | Jun 05, 2023 |
| HP            | 3397                        | Desktop     | [e9dd850e23](https://linux-hardware.org/?probe=e9dd850e23) | Jun 05, 2023 |
| BY OEM        | ZRD1103                     | Desktop     | [316792c3ac](https://linux-hardware.org/?probe=316792c3ac) | Jun 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | Notebook    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| AVITA         | NS14A8                      | Notebook    | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87b33e1181](https://linux-hardware.org/?probe=87b33e1181) | Jun 04, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [1e4ffa48ce](https://linux-hardware.org/?probe=1e4ffa48ce) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [e86a159ec5](https://linux-hardware.org/?probe=e86a159ec5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [01cd20c83d](https://linux-hardware.org/?probe=01cd20c83d) | Jun 03, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [a0cc355293](https://linux-hardware.org/?probe=a0cc355293) | Jun 03, 2023 |
| Acer          | Aspire ES1-523              | Notebook    | [a080a07f52](https://linux-hardware.org/?probe=a080a07f52) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b8c8f96b56](https://linux-hardware.org/?probe=b8c8f96b56) | Jun 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [13adb1e221](https://linux-hardware.org/?probe=13adb1e221) | Jun 02, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [af2f742bc5](https://linux-hardware.org/?probe=af2f742bc5) | Jun 01, 2023 |
| OEM           | Intel H81                   | Desktop     | [b62ec659fa](https://linux-hardware.org/?probe=b62ec659fa) | Jun 01, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [b7032438d2](https://linux-hardware.org/?probe=b7032438d2) | May 31, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [2c315764a9](https://linux-hardware.org/?probe=2c315764a9) | May 31, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [6c814f5bb5](https://linux-hardware.org/?probe=6c814f5bb5) | May 31, 2023 |
| Toshiba       | Satellite L850              | Notebook    | [cee0a13d3f](https://linux-hardware.org/?probe=cee0a13d3f) | May 31, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [dc6256036e](https://linux-hardware.org/?probe=dc6256036e) | May 30, 2023 |
| Intel         | DH61BF AAG81311-102         | Desktop     | [22123492ab](https://linux-hardware.org/?probe=22123492ab) | May 30, 2023 |
| Lenovo        | 3740 NOK                    | Desktop     | [c15d9d37c7](https://linux-hardware.org/?probe=c15d9d37c7) | May 30, 2023 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [7653baa0f8](https://linux-hardware.org/?probe=7653baa0f8) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [89bb5ff663](https://linux-hardware.org/?probe=89bb5ff663) | May 29, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [087565aed3](https://linux-hardware.org/?probe=087565aed3) | May 29, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [c5b13d6ea2](https://linux-hardware.org/?probe=c5b13d6ea2) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | Notebook    | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [423fe90cad](https://linux-hardware.org/?probe=423fe90cad) | May 28, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [a1aa06298d](https://linux-hardware.org/?probe=a1aa06298d) | May 28, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [4d8767d94b](https://linux-hardware.org/?probe=4d8767d94b) | May 28, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [902b837f1a](https://linux-hardware.org/?probe=902b837f1a) | May 27, 2023 |
| Dell          | Latitude 7480               | Notebook    | [2c74ec8198](https://linux-hardware.org/?probe=2c74ec8198) | May 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [5cf35078b0](https://linux-hardware.org/?probe=5cf35078b0) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c9c4e5ddb5](https://linux-hardware.org/?probe=c9c4e5ddb5) | May 26, 2023 |
| Dell          | 0H6C3V A00                  | All in one  | [16ce047abb](https://linux-hardware.org/?probe=16ce047abb) | May 26, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [4a59deb075](https://linux-hardware.org/?probe=4a59deb075) | May 25, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [0316f8d274](https://linux-hardware.org/?probe=0316f8d274) | May 25, 2023 |
| Dell          | 0H6C3V A00                  | All in one  | [a6b57b9588](https://linux-hardware.org/?probe=a6b57b9588) | May 25, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [270540781d](https://linux-hardware.org/?probe=270540781d) | May 25, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [53cbfa6255](https://linux-hardware.org/?probe=53cbfa6255) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [490c47960a](https://linux-hardware.org/?probe=490c47960a) | May 25, 2023 |
| MSI           | GF63 Thin 9RC               | Notebook    | [aef2c48b64](https://linux-hardware.org/?probe=aef2c48b64) | May 24, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [ae4f8dba2c](https://linux-hardware.org/?probe=ae4f8dba2c) | May 24, 2023 |
| Dell          | Vostro 2420                 | Notebook    | [ebff669275](https://linux-hardware.org/?probe=ebff669275) | May 24, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [bcb5af2775](https://linux-hardware.org/?probe=bcb5af2775) | May 24, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [e8bc14fc34](https://linux-hardware.org/?probe=e8bc14fc34) | May 23, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [c5615351bb](https://linux-hardware.org/?probe=c5615351bb) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [691b17e221](https://linux-hardware.org/?probe=691b17e221) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d704fd9efd](https://linux-hardware.org/?probe=d704fd9efd) | May 23, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [7d93944943](https://linux-hardware.org/?probe=7d93944943) | May 23, 2023 |
| Unknown       | Unknown                     | Desktop     | [aec9e5a959](https://linux-hardware.org/?probe=aec9e5a959) | May 22, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [5838a30c8b](https://linux-hardware.org/?probe=5838a30c8b) | May 22, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [33773ecf4d](https://linux-hardware.org/?probe=33773ecf4d) | May 22, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | Notebook    | [7d81e00b27](https://linux-hardware.org/?probe=7d81e00b27) | May 22, 2023 |
| HP            | 8599                        | Desktop     | [2e9caaf13a](https://linux-hardware.org/?probe=2e9caaf13a) | May 22, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [59464cac80](https://linux-hardware.org/?probe=59464cac80) | May 20, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [ff730fcbf6](https://linux-hardware.org/?probe=ff730fcbf6) | May 20, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [7aef6229db](https://linux-hardware.org/?probe=7aef6229db) | May 20, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| HP            | Laptop 15s-dr3xxx           | Notebook    | [4c44db2d32](https://linux-hardware.org/?probe=4c44db2d32) | May 19, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [61f60c8a7d](https://linux-hardware.org/?probe=61f60c8a7d) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b0ed659e7d](https://linux-hardware.org/?probe=b0ed659e7d) | May 19, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [7b98244b73](https://linux-hardware.org/?probe=7b98244b73) | May 19, 2023 |
| Fujitsu       | JIB75Y3                     | Desktop     | [1926915856](https://linux-hardware.org/?probe=1926915856) | May 19, 2023 |
| Gigabyte      | H310M S2                    | Desktop     | [b8a04e73b8](https://linux-hardware.org/?probe=b8a04e73b8) | May 18, 2023 |
| Dell          | Inspiron 14 5408            | Notebook    | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| HP            | Laptop 15s-du0xxx           | Notebook    | [ddc3152cbc](https://linux-hardware.org/?probe=ddc3152cbc) | May 17, 2023 |
| MSI           | GF63 Thin 9RC               | Notebook    | [b8f2e92853](https://linux-hardware.org/?probe=b8f2e92853) | May 16, 2023 |
| HP            | 339A                        | Desktop     | [72433c7d24](https://linux-hardware.org/?probe=72433c7d24) | May 16, 2023 |
| Lenovo        | 3168 NOK                    | Desktop     | [d541bf827b](https://linux-hardware.org/?probe=d541bf827b) | May 15, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [3e34d3a71c](https://linux-hardware.org/?probe=3e34d3a71c) | May 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [000f3c2444](https://linux-hardware.org/?probe=000f3c2444) | May 15, 2023 |
| Fujitsu       | JIB75Y3                     | Desktop     | [31146fe86e](https://linux-hardware.org/?probe=31146fe86e) | May 15, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [b938ce8d64](https://linux-hardware.org/?probe=b938ce8d64) | May 15, 2023 |
| HP            | 3397                        | Desktop     | [17d9dcc121](https://linux-hardware.org/?probe=17d9dcc121) | May 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | Notebook    | [fb4bda01b7](https://linux-hardware.org/?probe=fb4bda01b7) | May 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0060b3cb1c](https://linux-hardware.org/?probe=0060b3cb1c) | May 14, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [b9e5026a6a](https://linux-hardware.org/?probe=b9e5026a6a) | May 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [4a322b398b](https://linux-hardware.org/?probe=4a322b398b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [d251ccd249](https://linux-hardware.org/?probe=d251ccd249) | May 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [bc0dacd119](https://linux-hardware.org/?probe=bc0dacd119) | May 13, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [d06731c12e](https://linux-hardware.org/?probe=d06731c12e) | May 13, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [677e681a2d](https://linux-hardware.org/?probe=677e681a2d) | May 13, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [a8c81eafb0](https://linux-hardware.org/?probe=a8c81eafb0) | May 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [388408dc4b](https://linux-hardware.org/?probe=388408dc4b) | May 13, 2023 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [e0c2e78cad](https://linux-hardware.org/?probe=e0c2e78cad) | May 13, 2023 |
| AVITA         | NS14A6                      | Notebook    | [253f084ba1](https://linux-hardware.org/?probe=253f084ba1) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c9597b5b24](https://linux-hardware.org/?probe=c9597b5b24) | May 11, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [6cd766b17e](https://linux-hardware.org/?probe=6cd766b17e) | May 11, 2023 |
| Dell          | Latitude E5470              | Notebook    | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| AVITA         | NS14A6                      | Notebook    | [d2cdbff22c](https://linux-hardware.org/?probe=d2cdbff22c) | May 11, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [328d899b1c](https://linux-hardware.org/?probe=328d899b1c) | May 11, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [040f5917ec](https://linux-hardware.org/?probe=040f5917ec) | May 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [601a09abf6](https://linux-hardware.org/?probe=601a09abf6) | May 10, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [02c4a35621](https://linux-hardware.org/?probe=02c4a35621) | May 10, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | Notebook    | [0308c5d0c5](https://linux-hardware.org/?probe=0308c5d0c5) | May 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d2d1037c9d](https://linux-hardware.org/?probe=d2d1037c9d) | May 09, 2023 |
| Dell          | Latitude 3490               | Notebook    | [f9ed2aa5ab](https://linux-hardware.org/?probe=f9ed2aa5ab) | May 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [745096932c](https://linux-hardware.org/?probe=745096932c) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [dfe5f362e2](https://linux-hardware.org/?probe=dfe5f362e2) | May 09, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [cbc45e8ffa](https://linux-hardware.org/?probe=cbc45e8ffa) | May 09, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [c4a2b98dc5](https://linux-hardware.org/?probe=c4a2b98dc5) | May 09, 2023 |
| MSI           | MPG Z790 CARBON WIFI        | Desktop     | [bcccbb24de](https://linux-hardware.org/?probe=bcccbb24de) | May 09, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [e1313af3e6](https://linux-hardware.org/?probe=e1313af3e6) | May 08, 2023 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [410350c836](https://linux-hardware.org/?probe=410350c836) | May 08, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [c74bb83ac9](https://linux-hardware.org/?probe=c74bb83ac9) | May 08, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [f5acf4a186](https://linux-hardware.org/?probe=f5acf4a186) | May 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7e003cf7a9](https://linux-hardware.org/?probe=7e003cf7a9) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [99fbd772e8](https://linux-hardware.org/?probe=99fbd772e8) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b1b0fa7485](https://linux-hardware.org/?probe=b1b0fa7485) | May 07, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [741b9f90e1](https://linux-hardware.org/?probe=741b9f90e1) | May 07, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [1dbc92c072](https://linux-hardware.org/?probe=1dbc92c072) | May 07, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [845c2112be](https://linux-hardware.org/?probe=845c2112be) | May 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [3569e8fb31](https://linux-hardware.org/?probe=3569e8fb31) | May 06, 2023 |
| Dell          | Inspiron 3537               | Notebook    | [5b49eec8c6](https://linux-hardware.org/?probe=5b49eec8c6) | May 06, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [20461b100d](https://linux-hardware.org/?probe=20461b100d) | May 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [834d2304aa](https://linux-hardware.org/?probe=834d2304aa) | May 06, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| Acer          | Aspire E5-576               | Notebook    | [a73b11b28f](https://linux-hardware.org/?probe=a73b11b28f) | May 05, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [36de4a9de4](https://linux-hardware.org/?probe=36de4a9de4) | May 05, 2023 |
| HP            | ProBook 440 G5              | Notebook    | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS0SE00     | Notebook    | [c5d4b5a3a7](https://linux-hardware.org/?probe=c5d4b5a3a7) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [b7a4021d1f](https://linux-hardware.org/?probe=b7a4021d1f) | May 05, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [4cc44f819d](https://linux-hardware.org/?probe=4cc44f819d) | May 05, 2023 |
| Sony          | SVE15117FNW                 | Notebook    | [7ec421e4a1](https://linux-hardware.org/?probe=7ec421e4a1) | May 04, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [e60b96481a](https://linux-hardware.org/?probe=e60b96481a) | May 04, 2023 |
| Gateway       | NE46R                       | Notebook    | [05291d9029](https://linux-hardware.org/?probe=05291d9029) | May 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [5b46ed614a](https://linux-hardware.org/?probe=5b46ed614a) | May 04, 2023 |
| Dell          | Latitude 5490               | Notebook    | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [ac499d5a17](https://linux-hardware.org/?probe=ac499d5a17) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [6116c0df52](https://linux-hardware.org/?probe=6116c0df52) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [f115dd1851](https://linux-hardware.org/?probe=f115dd1851) | May 03, 2023 |
| Dell          | Latitude 5480               | Notebook    | [a8b85d06d8](https://linux-hardware.org/?probe=a8b85d06d8) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [530aaeef9d](https://linux-hardware.org/?probe=530aaeef9d) | May 02, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [eae11b1ac4](https://linux-hardware.org/?probe=eae11b1ac4) | May 02, 2023 |
| HP            | 86FC MVB                    | Desktop     | [de40052f4c](https://linux-hardware.org/?probe=de40052f4c) | May 02, 2023 |
| Intel         | NUC5CPYB H61145-404         | Mini pc     | [0873c73291](https://linux-hardware.org/?probe=0873c73291) | May 02, 2023 |
| Dell          | Inspiron 1564               | Notebook    | [e94ef67ab2](https://linux-hardware.org/?probe=e94ef67ab2) | May 01, 2023 |
| Dell          | Inspiron 14 5420            | Notebook    | [cc65b3de6f](https://linux-hardware.org/?probe=cc65b3de6f) | May 01, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [842333a8da](https://linux-hardware.org/?probe=842333a8da) | May 01, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [4f72daaab8](https://linux-hardware.org/?probe=4f72daaab8) | May 01, 2023 |
| Dell          | Latitude E5420              | Notebook    | [df8c9e7f40](https://linux-hardware.org/?probe=df8c9e7f40) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ccb46c2a2b](https://linux-hardware.org/?probe=ccb46c2a2b) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [446a548122](https://linux-hardware.org/?probe=446a548122) | Apr 30, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b0542737c](https://linux-hardware.org/?probe=4b0542737c) | Apr 29, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [2c335c5bfb](https://linux-hardware.org/?probe=2c335c5bfb) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | Notebook    | [0ea5e1926e](https://linux-hardware.org/?probe=0ea5e1926e) | Apr 29, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c6c943679f](https://linux-hardware.org/?probe=c6c943679f) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [216a4b9b67](https://linux-hardware.org/?probe=216a4b9b67) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [6736f3d911](https://linux-hardware.org/?probe=6736f3d911) | Apr 28, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [2ba1bab0fe](https://linux-hardware.org/?probe=2ba1bab0fe) | Apr 28, 2023 |
| Dell          | 0DNMV1 A01                  | Desktop     | [ab17992052](https://linux-hardware.org/?probe=ab17992052) | Apr 28, 2023 |
| Dell          | 0DNMV1 A01                  | Desktop     | [04bfccce7b](https://linux-hardware.org/?probe=04bfccce7b) | Apr 28, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | Notebook    | [65f390b956](https://linux-hardware.org/?probe=65f390b956) | Apr 28, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [eb327f9dc8](https://linux-hardware.org/?probe=eb327f9dc8) | Apr 28, 2023 |
| Unknown       | G41                         | Desktop     | [2a6a185bec](https://linux-hardware.org/?probe=2a6a185bec) | Apr 28, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [000022b2dd](https://linux-hardware.org/?probe=000022b2dd) | Apr 28, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [ca9179cae4](https://linux-hardware.org/?probe=ca9179cae4) | Apr 28, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [2499c633a5](https://linux-hardware.org/?probe=2499c633a5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | Notebook    | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [a23cf53cec](https://linux-hardware.org/?probe=a23cf53cec) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3e8fe7fed4](https://linux-hardware.org/?probe=3e8fe7fed4) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [4bdb6b2a7f](https://linux-hardware.org/?probe=4bdb6b2a7f) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | Notebook    | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [7ab7e066cf](https://linux-hardware.org/?probe=7ab7e066cf) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | Notebook    | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [e0d69966e9](https://linux-hardware.org/?probe=e0d69966e9) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [b6b7cdfe22](https://linux-hardware.org/?probe=b6b7cdfe22) | Apr 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a2c2f1f536](https://linux-hardware.org/?probe=a2c2f1f536) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 20RAS1DB00     | Notebook    | [8e09a153f5](https://linux-hardware.org/?probe=8e09a153f5) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [45199e8296](https://linux-hardware.org/?probe=45199e8296) | Apr 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [2787d97e6e](https://linux-hardware.org/?probe=2787d97e6e) | Apr 24, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | Notebook    | [8bfea5add2](https://linux-hardware.org/?probe=8bfea5add2) | Apr 24, 2023 |
| HP            | G42                         | Notebook    | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [cb9c1bfb3c](https://linux-hardware.org/?probe=cb9c1bfb3c) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [8578f44f47](https://linux-hardware.org/?probe=8578f44f47) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [91999697ba](https://linux-hardware.org/?probe=91999697ba) | Apr 20, 2023 |
| Acer          | Aspire 5745                 | Notebook    | [19e6d70ce0](https://linux-hardware.org/?probe=19e6d70ce0) | Apr 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | Notebook    | [59d7ef5ddd](https://linux-hardware.org/?probe=59d7ef5ddd) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [46ade409df](https://linux-hardware.org/?probe=46ade409df) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [954388c5e0](https://linux-hardware.org/?probe=954388c5e0) | Apr 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0W    | Notebook    | [97447a0777](https://linux-hardware.org/?probe=97447a0777) | Apr 19, 2023 |
| MSI           | 0B58h                       | Desktop     | [6473456480](https://linux-hardware.org/?probe=6473456480) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3a855386b4](https://linux-hardware.org/?probe=3a855386b4) | Apr 18, 2023 |
| MSI           | GP65 Leopard 10SEK          | Notebook    | [3b852bad57](https://linux-hardware.org/?probe=3b852bad57) | Apr 18, 2023 |
| Lenovo        | E41-25 81FS                 | Notebook    | [10bfabc1b8](https://linux-hardware.org/?probe=10bfabc1b8) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [6041b126fa](https://linux-hardware.org/?probe=6041b126fa) | Apr 18, 2023 |
| HP            | 630                         | Notebook    | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [9be6e0f395](https://linux-hardware.org/?probe=9be6e0f395) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d1d3cf9928](https://linux-hardware.org/?probe=d1d3cf9928) | Apr 17, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [786daebed0](https://linux-hardware.org/?probe=786daebed0) | Apr 17, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [dbd2cfbd81](https://linux-hardware.org/?probe=dbd2cfbd81) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| ASUSTek       | EX-B560M-V5                 | Desktop     | [243b7b3722](https://linux-hardware.org/?probe=243b7b3722) | Apr 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7f5feb82ab](https://linux-hardware.org/?probe=7f5feb82ab) | Apr 17, 2023 |
| Gigabyte      | H81M-S                      | Desktop     | [db6516c973](https://linux-hardware.org/?probe=db6516c973) | Apr 16, 2023 |
| Dell          | Vostro 3580                 | Notebook    | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [0dfc78d12a](https://linux-hardware.org/?probe=0dfc78d12a) | Apr 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [bfaea1065e](https://linux-hardware.org/?probe=bfaea1065e) | Apr 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [3738d57a9c](https://linux-hardware.org/?probe=3738d57a9c) | Apr 15, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [bc7d49c64c](https://linux-hardware.org/?probe=bc7d49c64c) | Apr 15, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7d9278e08a](https://linux-hardware.org/?probe=7d9278e08a) | Apr 15, 2023 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [c99626b458](https://linux-hardware.org/?probe=c99626b458) | Apr 14, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [a2b5435974](https://linux-hardware.org/?probe=a2b5435974) | Apr 14, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [50a9e6f749](https://linux-hardware.org/?probe=50a9e6f749) | Apr 14, 2023 |
| Acer          | AO756                       | Notebook    | [c17d5276ec](https://linux-hardware.org/?probe=c17d5276ec) | Apr 14, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [6106a2c31f](https://linux-hardware.org/?probe=6106a2c31f) | Apr 13, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [42e4889a44](https://linux-hardware.org/?probe=42e4889a44) | Apr 13, 2023 |
| MSI           | X370 GAMING PLUS            | Desktop     | [f63c87bf19](https://linux-hardware.org/?probe=f63c87bf19) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [0d0ff5240b](https://linux-hardware.org/?probe=0d0ff5240b) | Apr 12, 2023 |
| ASUSTek       | K53U                        | Notebook    | [19ec753136](https://linux-hardware.org/?probe=19ec753136) | Apr 12, 2023 |
| Dell          | Precision 5520              | Notebook    | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [8b0573684a](https://linux-hardware.org/?probe=8b0573684a) | Apr 12, 2023 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [3225aa17d2](https://linux-hardware.org/?probe=3225aa17d2) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [40c7ac46e2](https://linux-hardware.org/?probe=40c7ac46e2) | Apr 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b9d22dfaea](https://linux-hardware.org/?probe=b9d22dfaea) | Apr 10, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [bc18513752](https://linux-hardware.org/?probe=bc18513752) | Apr 09, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [0bbe9702ca](https://linux-hardware.org/?probe=0bbe9702ca) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [c82c56c81e](https://linux-hardware.org/?probe=c82c56c81e) | Apr 09, 2023 |
| Dell          | Latitude 7275               | Notebook    | [d1a55f8f55](https://linux-hardware.org/?probe=d1a55f8f55) | Apr 09, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [51c8f59aeb](https://linux-hardware.org/?probe=51c8f59aeb) | Apr 08, 2023 |
| Dell          | Latitude 3410               | Notebook    | [9fd7d9d439](https://linux-hardware.org/?probe=9fd7d9d439) | Apr 08, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [10c9b38ed6](https://linux-hardware.org/?probe=10c9b38ed6) | Apr 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [133568abf2](https://linux-hardware.org/?probe=133568abf2) | Apr 07, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4f37849c94](https://linux-hardware.org/?probe=4f37849c94) | Apr 07, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [122c9d0ae2](https://linux-hardware.org/?probe=122c9d0ae2) | Apr 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f29d8154a2](https://linux-hardware.org/?probe=f29d8154a2) | Apr 06, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [c26cae6392](https://linux-hardware.org/?probe=c26cae6392) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [62bdbae29c](https://linux-hardware.org/?probe=62bdbae29c) | Apr 05, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [fef3cbc941](https://linux-hardware.org/?probe=fef3cbc941) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [8425bb5da3](https://linux-hardware.org/?probe=8425bb5da3) | Apr 04, 2023 |
| HP            | 1495                        | Desktop     | [c0665ecb23](https://linux-hardware.org/?probe=c0665ecb23) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [b35bf27d28](https://linux-hardware.org/?probe=b35bf27d28) | Apr 04, 2023 |
| HP            | 1000                        | Notebook    | [111c9bd980](https://linux-hardware.org/?probe=111c9bd980) | Apr 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [7325272558](https://linux-hardware.org/?probe=7325272558) | Apr 04, 2023 |
| Lenovo        | Unknown                     | Notebook    | [4216d2969c](https://linux-hardware.org/?probe=4216d2969c) | Apr 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [d3a27ee996](https://linux-hardware.org/?probe=d3a27ee996) | Apr 03, 2023 |
| Lenovo        | 3724                        | All in one  | [690f25d1ab](https://linux-hardware.org/?probe=690f25d1ab) | Apr 03, 2023 |
| Gateway       | NE56R                       | Notebook    | [ffa6b1d3f3](https://linux-hardware.org/?probe=ffa6b1d3f3) | Apr 03, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [4145a32920](https://linux-hardware.org/?probe=4145a32920) | Apr 03, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [6ace928ea5](https://linux-hardware.org/?probe=6ace928ea5) | Apr 03, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [cc341f3faf](https://linux-hardware.org/?probe=cc341f3faf) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS0D800     | Notebook    | [ea2f5b484f](https://linux-hardware.org/?probe=ea2f5b484f) | Apr 02, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [1561095eff](https://linux-hardware.org/?probe=1561095eff) | Apr 02, 2023 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [5380352186](https://linux-hardware.org/?probe=5380352186) | Apr 02, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [d018871b72](https://linux-hardware.org/?probe=d018871b72) | Apr 02, 2023 |
| HP            | Laptop 15q-ds0xxx           | Notebook    | [42bd53a04e](https://linux-hardware.org/?probe=42bd53a04e) | Apr 02, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [cd6dee4651](https://linux-hardware.org/?probe=cd6dee4651) | Apr 01, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [d93b1d27e1](https://linux-hardware.org/?probe=d93b1d27e1) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [0992e2d8d8](https://linux-hardware.org/?probe=0992e2d8d8) | Mar 31, 2023 |
| HP            | 250 G3                      | Notebook    | [519b0e31a8](https://linux-hardware.org/?probe=519b0e31a8) | Mar 30, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [f24b481b5b](https://linux-hardware.org/?probe=f24b481b5b) | Mar 30, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [c68415cbb6](https://linux-hardware.org/?probe=c68415cbb6) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| Acer          | Extensa 215-23              | Notebook    | [bf5730d468](https://linux-hardware.org/?probe=bf5730d468) | Mar 29, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [a2ba637448](https://linux-hardware.org/?probe=a2ba637448) | Mar 29, 2023 |
| Dell          | 0T2HR0 A02                  | Desktop     | [bf959f65d2](https://linux-hardware.org/?probe=bf959f65d2) | Mar 29, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/India/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 944       | 18.8%   |
| Ubuntu 18.04                 | 414       | 8.25%   |
| Ubuntu 22.04                 | 377       | 7.51%   |
| Arch Rolling                 | 125       | 2.49%   |
| Arch                         | 104       | 2.07%   |
| Zorin 16                     | 99        | 1.97%   |
| Pop!_OS 22.04                | 97        | 1.93%   |
| Fedora 38                    | 85        | 1.69%   |
| KDE neon 20.04               | 84        | 1.67%   |
| ArcoLinux Rolling            | 83        | 1.65%   |
| OpenMandriva 4.3             | 77        | 1.53%   |
| Fedora 36                    | 69        | 1.37%   |
| Pop!_OS 20.04                | 67        | 1.33%   |
| Fedora 37                    | 62        | 1.24%   |
| Pop!_OS 21.04                | 60        | 1.2%    |
| Ubuntu 20.10                 | 58        | 1.16%   |
| Fedora 34                    | 58        | 1.16%   |
| OpenMandriva 4.2             | 57        | 1.14%   |
| Zorin 15                     | 56        | 1.12%   |
| Ubuntu 21.04                 | 54        | 1.08%   |
| Manjaro                      | 53        | 1.06%   |
| Ubuntu 19.10                 | 51        | 1.02%   |
| Ubuntu 21.10                 | 45        | 0.9%    |
| Ubuntu 19.04                 | 45        | 0.9%    |
| Debian 11                    | 45        | 0.9%    |
| Pop!_OS 20.10                | 44        | 0.88%   |
| Linux Mint 21.1              | 41        | 0.82%   |
| Fedora 35                    | 40        | 0.8%    |
| Ubuntu 23.04                 | 39        | 0.78%   |
| Fedora 32                    | 39        | 0.78%   |
| Ubuntu Unity 16.04           | 34        | 0.68%   |
| Linux Mint 20                | 34        | 0.68%   |
| Fedora 33                    | 34        | 0.68%   |
| OpenMandriva 23.03           | 33        | 0.66%   |
| Ubuntu 16.04                 | 32        | 0.64%   |
| Linux Mint 20.2              | 32        | 0.64%   |
| Linux Mint 20.3              | 31        | 0.62%   |
| Linux Mint 20.1              | 30        | 0.6%    |
| EndeavourOS Rolling          | 30        | 0.6%    |
| openSUSE Tumbleweed-XXXXXXXX | 28        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2053      | 42.47%  |
| Fedora        | 390       | 8.07%   |
| Pop!_OS       | 281       | 5.81%   |
| Linux Mint    | 222       | 4.59%   |
| OpenMandriva  | 221       | 4.57%   |
| Arch          | 220       | 4.55%   |
| Zorin         | 155       | 3.21%   |
| Manjaro       | 132       | 2.73%   |
| KDE neon      | 121       | 2.5%    |
| Debian        | 121       | 2.5%    |
| Kali          | 89        | 1.84%   |
| ArcoLinux     | 89        | 1.84%   |
| Kubuntu       | 79        | 1.63%   |
| Ubuntu Unity  | 61        | 1.26%   |
| Elementary    | 58        | 1.2%    |
| Endless       | 52        | 1.08%   |
| Xubuntu       | 37        | 0.77%   |
| openSUSE      | 36        | 0.74%   |
| EndeavourOS   | 34        | 0.7%    |
| Garuda Linux  | 29        | 0.6%    |
| CentOS        | 28        | 0.58%   |
| RHEL          | 25        | 0.52%   |
| ROSA          | 23        | 0.48%   |
| Xero          | 22        | 0.46%   |
| Clear Linux   | 22        | 0.46%   |
| MX            | 20        | 0.41%   |
| Parrot        | 18        | 0.37%   |
| Ubuntu Budgie | 16        | 0.33%   |
| Lubuntu       | 15        | 0.31%   |
| Ubuntu MATE   | 14        | 0.29%   |
| Void Linux    | 10        | 0.21%   |
| Solus         | 9         | 0.19%   |
| Nobara        | 9         | 0.19%   |
| Gentoo        | 9         | 0.19%   |
| Artix         | 8         | 0.17%   |
| Peppermint    | 7         | 0.14%   |
| BlackPanther  | 7         | 0.14%   |
| Slackware     | 6         | 0.12%   |
| LMDE          | 6         | 0.12%   |
| Archcraft     | 6         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 153       | 2.84%   |
| 5.16.7-desktop-1omv4003  | 73        | 1.35%   |
| 5.4.0-40-generic         | 61        | 1.13%   |
| 5.10.14-desktop-1omv4002 | 57        | 1.06%   |
| 5.15.0-56-generic        | 54        | 1%      |
| 5.4.0-48-generic         | 47        | 0.87%   |
| 5.4.0-58-generic         | 43        | 0.8%    |
| 5.11.0-27-generic        | 41        | 0.76%   |
| 5.4.0-52-generic         | 40        | 0.74%   |
| 5.4.0-26-generic         | 40        | 0.74%   |
| 5.4.0-47-generic         | 39        | 0.72%   |
| 5.11.0-25-generic        | 35        | 0.65%   |
| 5.11.0-7620-generic      | 34        | 0.63%   |
| 6.2.0-26-generic         | 33        | 0.61%   |
| 5.4.0-29-generic         | 33        | 0.61%   |
| 6.2.6-desktop-1omv2390   | 32        | 0.59%   |
| 5.15.0-52-generic        | 32        | 0.59%   |
| 5.15.0-46-generic        | 31        | 0.57%   |
| 5.15.0-58-generic        | 30        | 0.56%   |
| 5.8.0-48-generic         | 29        | 0.54%   |
| 5.3.0-28-generic         | 29        | 0.54%   |
| 5.11.0-40-generic        | 29        | 0.54%   |
| 5.8.0-53-generic         | 28        | 0.52%   |
| 5.8.0-55-generic         | 27        | 0.5%    |
| 5.8.0-43-generic         | 27        | 0.5%    |
| 5.4.0-37-generic         | 27        | 0.5%    |
| 5.11.0-43-generic        | 26        | 0.48%   |
| 5.11.0-38-generic        | 26        | 0.48%   |
| 5.11.0-37-generic        | 26        | 0.48%   |
| 5.19.0-41-generic        | 25        | 0.46%   |
| 5.0.0-37-generic         | 25        | 0.46%   |
| 5.8.0-59-generic         | 24        | 0.44%   |
| 5.8.0-44-generic         | 24        | 0.44%   |
| 5.4.0-74-generic         | 24        | 0.44%   |
| 5.3.0-40-generic         | 24        | 0.44%   |
| 5.19.0-38-generic        | 24        | 0.44%   |
| 5.15.0-43-generic        | 24        | 0.44%   |
| 5.13.0-30-generic        | 24        | 0.44%   |
| 4.15.0-45-generic        | 24        | 0.44%   |
| 5.4.0-45-generic         | 23        | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 870       | 16.86%  |
| 5.15.0  | 437       | 8.47%   |
| 5.11.0  | 337       | 6.53%   |
| 5.8.0   | 310       | 6.01%   |
| 4.15.0  | 237       | 4.59%   |
| 5.13.0  | 206       | 3.99%   |
| 5.3.0   | 192       | 3.72%   |
| 5.19.0  | 187       | 3.62%   |
| 5.0.0   | 130       | 2.52%   |
| 6.2.0   | 120       | 2.33%   |
| 4.18.0  | 104       | 2.02%   |
| 5.10.0  | 76        | 1.47%   |
| 5.16.7  | 75        | 1.45%   |
| 5.10.14 | 57        | 1.1%    |
| 6.1.0   | 54        | 1.05%   |
| 6.2.6   | 51        | 0.99%   |
| 5.14.0  | 35        | 0.68%   |
| 4.19.0  | 30        | 0.58%   |
| 4.4.0   | 25        | 0.48%   |
| 6.1.1   | 22        | 0.43%   |
| 5.17.5  | 22        | 0.43%   |
| 6.0.12  | 19        | 0.37%   |
| 6.0.0   | 18        | 0.35%   |
| 6.4.11  | 16        | 0.31%   |
| 6.2.9   | 16        | 0.31%   |
| 5.7.0   | 14        | 0.27%   |
| 6.5.5   | 13        | 0.25%   |
| 6.5.0   | 13        | 0.25%   |
| 6.0.8   | 13        | 0.25%   |
| 6.0.6   | 13        | 0.25%   |
| 5.18.0  | 13        | 0.25%   |
| 5.15.11 | 13        | 0.25%   |
| 6.3.8   | 12        | 0.23%   |
| 6.0.9   | 12        | 0.23%   |
| 5.9.0   | 12        | 0.23%   |
| 3.10.0  | 12        | 0.23%   |
| 6.4.8   | 11        | 0.21%   |
| 6.4.12  | 11        | 0.21%   |
| 5.17.9  | 11        | 0.21%   |
| 6.3.5   | 10        | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 910       | 17.83%  |
| 5.15    | 571       | 11.19%  |
| 5.11    | 376       | 7.37%   |
| 5.8     | 370       | 7.25%   |
| 5.13    | 260       | 5.09%   |
| 6.2     | 243       | 4.76%   |
| 5.19    | 243       | 4.76%   |
| 4.15    | 240       | 4.7%    |
| 5.3     | 218       | 4.27%   |
| 5.10    | 205       | 4.02%   |
| 6.1     | 155       | 3.04%   |
| 5.16    | 140       | 2.74%   |
| 5.0     | 135       | 2.64%   |
| 6.0     | 112       | 2.19%   |
| 4.18    | 111       | 2.17%   |
| 5.14    | 89        | 1.74%   |
| 6.4     | 86        | 1.68%   |
| 5.17    | 83        | 1.63%   |
| 5.18    | 71        | 1.39%   |
| 6.5     | 69        | 1.35%   |
| 6.3     | 61        | 1.19%   |
| 5.12    | 56        | 1.1%    |
| 5.9     | 51        | 1%      |
| 5.7     | 49        | 0.96%   |
| 4.19    | 42        | 0.82%   |
| 5.6     | 41        | 0.8%    |
| 4.4     | 28        | 0.55%   |
| 5.5     | 26        | 0.51%   |
| 4.9     | 16        | 0.31%   |
| 3.10    | 12        | 0.24%   |
| 5.2     | 8         | 0.16%   |
| 4.13    | 5         | 0.1%    |
| 5.1     | 4         | 0.08%   |
| 6.6     | 3         | 0.06%   |
| 4.20    | 3         | 0.06%   |
| 3.16    | 3         | 0.06%   |
| 4.14    | 2         | 0.04%   |
| 4.1     | 2         | 0.04%   |
| 5       | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4559      | 98.06%  |
| i686    | 69        | 1.48%   |
| aarch64 | 15        | 0.32%   |
| armv7l  | 6         | 0.13%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 2737      | 56.57%  |
| KDE5              | 652       | 13.48%  |
| Unknown           | 483       | 9.98%   |
| XFCE              | 231       | 4.77%   |
| X-Cinnamon        | 190       | 3.93%   |
| KDE               | 106       | 2.19%   |
| Unity             | 63        | 1.3%    |
| Pantheon          | 56        | 1.16%   |
| MATE              | 55        | 1.14%   |
| Cinnamon          | 35        | 0.72%   |
| i3                | 30        | 0.62%   |
| GNOME Flashback   | 25        | 0.52%   |
| Budgie            | 24        | 0.5%    |
| LXDE              | 20        | 0.41%   |
| LXQt              | 19        | 0.39%   |
| Deepin            | 15        | 0.31%   |
| GNOME Classic     | 12        | 0.25%   |
| KDE4              | 11        | 0.23%   |
| awesome           | 11        | 0.23%   |
| bspwm             | 10        | 0.21%   |
| qtile             | 9         | 0.19%   |
| sway              | 7         | 0.14%   |
| dwm               | 7         | 0.14%   |
| Openbox           | 6         | 0.12%   |
| Hyprland          | 6         | 0.12%   |
| LeftWM            | 5         | 0.1%    |
| xmonad            | 4         | 0.08%   |
| lightdm-xsession  | 2         | 0.04%   |
| Enlightenment     | 2         | 0.04%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| icewm             | 1         | 0.02%   |
| i3-with-shmlog    | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| chadwm            | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3460      | 72.25%  |
| Wayland | 965       | 20.15%  |
| Unknown | 300       | 6.26%   |
| Tty     | 64        | 1.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2304      | 47.75%  |
| GDM     | 793       | 16.44%  |
| GDM3    | 652       | 13.51%  |
| SDDM    | 596       | 12.35%  |
| LightDM | 346       | 7.17%   |
| TDM     | 105       | 2.18%   |
| XDM     | 9         | 0.19%   |
| KDM     | 9         | 0.19%   |
| LXDM    | 4         | 0.08%   |
| SLiM    | 3         | 0.06%   |
| Ly      | 3         | 0.06%   |
| GREETD  | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang             | Computers | Percent |
|------------------|-----------|---------|
| en_IN            | 2887      | 60.06%  |
| en_US            | 1325      | 27.56%  |
| Unknown          | 382       | 7.95%   |
| en_GB            | 91        | 1.89%   |
| C                | 83        | 1.73%   |
| en_AG            | 8         | 0.17%   |
| en_CA            | 5         | 0.1%    |
| zh_TW            | 2         | 0.04%   |
| POSIX            | 2         | 0.04%   |
| mr_IN            | 2         | 0.04%   |
| mni_IN           | 2         | 0.04%   |
| en_IE            | 2         | 0.04%   |
| en_AU            | 2         | 0.04%   |
| ta_LK            | 1         | 0.02%   |
| sa_IN            | 1         | 0.02%   |
| pl_PL            | 1         | 0.02%   |
| ks_IN            | 1         | 0.02%   |
| es_ES            | 1         | 0.02%   |
| en_US.ISO-8859-1 | 1         | 0.02%   |
| en_SG            | 1         | 0.02%   |
| en_NG            | 1         | 0.02%   |
| en_DK            | 1         | 0.02%   |
| en_BW            | 1         | 0.02%   |
| de_DE            | 1         | 0.02%   |
| Default          | 1         | 0.02%   |
| C.UTF8           | 1         | 0.02%   |
| aa_DJ            | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2788      | 58.87%  |
| BIOS | 1948      | 41.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3739      | 78.3%   |
| Btrfs   | 487       | 10.2%   |
| Overlay | 222       | 4.65%   |
| Tmpfs   | 106       | 2.22%   |
| Xfs     | 81        | 1.7%    |
| Unknown | 79        | 1.65%   |
| Zfs     | 23        | 0.48%   |
| F2fs    | 13        | 0.27%   |
| Ext2    | 13        | 0.27%   |
| Ext3    | 9         | 0.19%   |
| XXXXX   | 1         | 0.02%   |
| Jfs     | 1         | 0.02%   |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2424      | 51.05%  |
| GPT     | 1958      | 41.24%  |
| MBR     | 366       | 7.71%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4099      | 86.71%  |
| Yes       | 628       | 13.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2854      | 60.36%  |
| Yes       | 1874      | 39.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 912       | 19.63%  |
| Hewlett-Packard         | 892       | 19.2%   |
| Dell                    | 848       | 18.25%  |
| ASUSTek Computer        | 593       | 12.76%  |
| Acer                    | 305       | 6.56%   |
| Gigabyte Technology     | 277       | 5.96%   |
| MSI                     | 152       | 3.27%   |
| Intel                   | 143       | 3.08%   |
| Unknown                 | 68        | 1.46%   |
| Sony                    | 50        | 1.08%   |
| ASRock                  | 39        | 0.84%   |
| Apple                   | 38        | 0.82%   |
| Toshiba                 | 36        | 0.77%   |
| Timi                    | 34        | 0.73%   |
| Samsung Electronics     | 27        | 0.58%   |
| AVITA                   | 23        | 0.49%   |
| OEM                     | 16        | 0.34%   |
| Raspberry Pi Foundation | 12        | 0.26%   |
| ECS                     | 12        | 0.26%   |
| Biostar                 | 11        | 0.24%   |
| Fujitsu                 | 10        | 0.22%   |
| HONOR                   | 9         | 0.19%   |
| HCL Infosystems Limited | 9         | 0.19%   |
| Foxconn                 | 9         | 0.19%   |
| AMI                     | 9         | 0.19%   |
| Infinix                 | 8         | 0.17%   |
| HUAWEI                  | 8         | 0.17%   |
| Google                  | 7         | 0.15%   |
| LG Electronics          | 5         | 0.11%   |
| Gateway                 | 5         | 0.11%   |
| Alienware               | 5         | 0.11%   |
| Radxa                   | 4         | 0.09%   |
| Pegatron                | 4         | 0.09%   |
| ITI LIMITED             | 4         | 0.09%   |
| eMachines               | 4         | 0.09%   |
| WIPRO                   | 3         | 0.06%   |
| Valve                   | 3         | 0.06%   |
| realme                  | 3         | 0.06%   |
| LORD ELECTRONICS        | 3         | 0.06%   |
| ZOTAC                   | 2         | 0.04%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 93        | 2%      |
| HP Notebook                            | 78        | 1.68%   |
| HP 15                                  | 34        | 0.73%   |
| HP Pavilion 15                         | 30        | 0.65%   |
| HP Pavilion g6                         | 28        | 0.6%    |
| Dell Inspiron 3542                     | 27        | 0.58%   |
| Gigabyte H410M H V3                    | 23        | 0.49%   |
| Lenovo E41-25 81FS                     | 22        | 0.47%   |
| Intel H61                              | 22        | 0.47%   |
| Dell Inspiron 15-3567                  | 22        | 0.47%   |
| HP Laptop 15-bs0xx                     | 21        | 0.45%   |
| Dell Inspiron 5570                     | 20        | 0.43%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 19        | 0.41%   |
| HP Pavilion Notebook                   | 18        | 0.39%   |
| Dell Inspiron 3521                     | 18        | 0.39%   |
| ASUS TUF Gaming FX505DT_FX505DT        | 18        | 0.39%   |
| Acer Aspire A715-75G                   | 17        | 0.37%   |
| Lenovo G50-80 80E5                     | 16        | 0.34%   |
| Dell Vostro 15-3568                    | 16        | 0.34%   |
| Gigabyte H81M-S                        | 15        | 0.32%   |
| Gigabyte H61MS                         | 15        | 0.32%   |
| Dell Vostro 3480                       | 15        | 0.32%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 14        | 0.3%    |
| Lenovo IdeaPad 320-15ISK 80XH          | 13        | 0.28%   |
| HP Laptop 15-da0xxx                    | 13        | 0.28%   |
| Dell Vostro 3578                       | 13        | 0.28%   |
| Dell Inspiron 1545                     | 13        | 0.28%   |
| Timi Mi NoteBook Ultra                 | 12        | 0.26%   |
| HP Pavilion x360 Convertible 14-dh1xxx | 12        | 0.26%   |
| HP Pavilion Laptop 14-dv0xxx           | 12        | 0.26%   |
| Gigabyte H310M S2 2.0                  | 12        | 0.26%   |
| Dell Inspiron 5559                     | 12        | 0.26%   |
| ASUS X510UNR                           | 12        | 0.26%   |
| Lenovo G50-45 80E3                     | 11        | 0.24%   |
| HP Laptop 15-bw0xx                     | 11        | 0.24%   |
| Gigabyte H110M-S2                      | 11        | 0.24%   |
| Dell Inspiron N5010                    | 11        | 0.24%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR   | 11        | 0.24%   |
| ASUS TUF Gaming FX505DY_FX505DY        | 11        | 0.24%   |
| Lenovo IdeaPad S540-15IWL D 81NE       | 10        | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 374       | 8.05%   |
| Lenovo IdeaPad     | 287       | 6.18%   |
| Lenovo ThinkPad    | 286       | 6.15%   |
| HP Pavilion        | 254       | 5.47%   |
| ASUS VivoBook      | 176       | 3.79%   |
| HP Laptop          | 168       | 3.62%   |
| Dell Latitude      | 164       | 3.53%   |
| Acer Aspire        | 161       | 3.46%   |
| Dell Vostro        | 154       | 3.31%   |
| Unknown            | 93        | 2%      |
| HP Notebook        | 79        | 1.7%    |
| HP EliteBook       | 61        | 1.31%   |
| ASUS TUF           | 60        | 1.29%   |
| ASUS ROG           | 59        | 1.27%   |
| ASUS ASUS          | 53        | 1.14%   |
| HP ProBook         | 52        | 1.12%   |
| Dell OptiPlex      | 47        | 1.01%   |
| Acer Nitro         | 41        | 0.88%   |
| ASUS PRIME         | 40        | 0.86%   |
| Lenovo Legion      | 36        | 0.77%   |
| HP ENVY            | 36        | 0.77%   |
| Dell XPS           | 36        | 0.77%   |
| HP 15              | 35        | 0.75%   |
| Acer Swift         | 32        | 0.69%   |
| Toshiba Satellite  | 31        | 0.67%   |
| Lenovo ThinkBook   | 31        | 0.67%   |
| Dell Precision     | 31        | 0.67%   |
| Gigabyte H410M     | 29        | 0.62%   |
| HP Compaq          | 28        | 0.6%    |
| Lenovo ThinkCentre | 25        | 0.54%   |
| Timi Mi            | 24        | 0.52%   |
| Gigabyte H310M     | 23        | 0.49%   |
| Lenovo E41-25      | 22        | 0.47%   |
| Intel H61          | 22        | 0.47%   |
| Lenovo Yoga        | 20        | 0.43%   |
| Acer Predator      | 20        | 0.43%   |
| Lenovo IdeaPadFlex | 19        | 0.41%   |
| ASUS ZenBook       | 17        | 0.37%   |
| Acer Veriton       | 17        | 0.37%   |
| Lenovo G50-80      | 16        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 598       | 12.87%  |
| 2018    | 596       | 12.83%  |
| 2020    | 473       | 10.18%  |
| 2021    | 456       | 9.81%   |
| 2017    | 396       | 8.52%   |
| 2012    | 284       | 6.11%   |
| 2016    | 282       | 6.07%   |
| 2014    | 267       | 5.75%   |
| 2013    | 262       | 5.64%   |
| 2011    | 234       | 5.04%   |
| 2015    | 197       | 4.24%   |
| 2022    | 186       | 4%      |
| 2010    | 172       | 3.7%    |
| 2008    | 83        | 1.79%   |
| 2009    | 73        | 1.57%   |
| 2023    | 31        | 0.67%   |
| 2007    | 26        | 0.56%   |
| Unknown | 19        | 0.41%   |
| 2006    | 8         | 0.17%   |
| 2005    | 3         | 0.06%   |
| 2003    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 3392      | 72.99%  |
| Desktop        | 1024      | 22.04%  |
| Convertible    | 121       | 2.6%    |
| Mini pc        | 33        | 0.71%   |
| All in one     | 32        | 0.69%   |
| System on chip | 20        | 0.43%   |
| Server         | 13        | 0.28%   |
| Tablet         | 12        | 0.26%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4111      | 87.69%  |
| Enabled  | 577       | 12.31%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4633      | 99.7%   |
| Yes  | 14        | 0.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1505      | 31.94%  |
| 3.01-4.0        | 1036      | 21.99%  |
| 8.01-16.0       | 909       | 19.29%  |
| 16.01-24.0      | 789       | 16.74%  |
| 32.01-64.0      | 174       | 3.69%   |
| 1.01-2.0        | 159       | 3.37%   |
| 2.01-3.0        | 43        | 0.91%   |
| 64.01-256.0     | 43        | 0.91%   |
| 24.01-32.0      | 34        | 0.72%   |
| 0.51-1.0        | 17        | 0.36%   |
| 0.01-0.5        | 2         | 0.04%   |
| More than 256.0 | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 1579      | 31.05%  |
| 1.01-2.0    | 1565      | 30.77%  |
| 4.01-8.0    | 784       | 15.41%  |
| 3.01-4.0    | 768       | 15.1%   |
| 0.51-1.0    | 184       | 3.62%   |
| 8.01-16.0   | 156       | 3.07%   |
| 0.01-0.5    | 33        | 0.65%   |
| 16.01-24.0  | 11        | 0.22%   |
| 32.01-64.0  | 2         | 0.04%   |
| 24.01-32.0  | 2         | 0.04%   |
| 64.01-256.0 | 1         | 0.02%   |
| Unknown     | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 3292      | 69.8%   |
| 2      | 1151      | 24.41%  |
| 3      | 164       | 3.48%   |
| 4      | 43        | 0.91%   |
| 0      | 32        | 0.68%   |
| 5      | 19        | 0.4%    |
| 6      | 9         | 0.19%   |
| 7      | 3         | 0.06%   |
| 19     | 1         | 0.02%   |
| 9      | 1         | 0.02%   |
| 8      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 3195      | 68.31%  |
| Yes       | 1482      | 31.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3829      | 82.26%  |
| No        | 826       | 17.74%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4081      | 87.48%  |
| No        | 584       | 12.52%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3477      | 74.04%  |
| No        | 1219      | 25.96%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| India   | 4647      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Bengaluru     | 593       | 11.96%  |
| Mumbai        | 320       | 6.46%   |
| Chennai       | 318       | 6.42%   |
| Hyderabad     | 295       | 5.95%   |
| Delhi         | 273       | 5.51%   |
| Pune          | 246       | 4.96%   |
| Kolkata       | 205       | 4.14%   |
| New Delhi     | 192       | 3.87%   |
| Ahmedabad     | 111       | 2.24%   |
| Lucknow       | 91        | 1.84%   |
| Patna         | 85        | 1.71%   |
| Jaipur        | 80        | 1.61%   |
| Ernakulam     | 79        | 1.59%   |
| Gurgaon       | 69        | 1.39%   |
| Indore        | 64        | 1.29%   |
| Kochi         | 60        | 1.21%   |
| Coimbatore    | 60        | 1.21%   |
| Bhopal        | 58        | 1.17%   |
| Navi Mumbai   | 53        | 1.07%   |
| Trivandrum    | 50        | 1.01%   |
| Surat         | 50        | 1.01%   |
| Thrissur      | 46        | 0.93%   |
| Guwahati      | 40        | 0.81%   |
| Bhubaneswar   | 38        | 0.77%   |
| Nagpur        | 37        | 0.75%   |
| Malappuram    | 37        | 0.75%   |
| Ludhiana      | 34        | 0.69%   |
| Noida         | 30        | 0.61%   |
| Chandigarh    | 27        | 0.54%   |
| Mangalore     | 25        | 0.5%    |
| Ghaziabad     | 25        | 0.5%    |
| Visakhapatnam | 23        | 0.46%   |
| Vadodara      | 23        | 0.46%   |
| Thane         | 23        | 0.46%   |
| Kanpur        | 23        | 0.46%   |
| Vijayawada    | 22        | 0.44%   |
| Gonikoppal    | 22        | 0.44%   |
| Kozhikode     | 19        | 0.38%   |
| Dehradun      | 19        | 0.38%   |
| Tiruchi       | 18        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1246      | 1626   | 20.8%   |
| WDC                         | 1082      | 1405   | 18.07%  |
| Samsung Electronics         | 585       | 747    | 9.77%   |
| Toshiba                     | 566       | 649    | 9.45%   |
| SanDisk                     | 264       | 327    | 4.41%   |
| Crucial                     | 241       | 318    | 4.02%   |
| Kingston                    | 228       | 273    | 3.81%   |
| SK hynix                    | 201       | 229    | 3.36%   |
| Intel                       | 200       | 269    | 3.34%   |
| HGST                        | 178       | 217    | 2.97%   |
| Micron Technology           | 174       | 196    | 2.91%   |
| Unknown                     | 133       | 164    | 2.22%   |
| Hitachi                     | 113       | 136    | 1.89%   |
| KIOXIA                      | 86        | 99     | 1.44%   |
| A-DATA Technology           | 75        | 82     | 1.25%   |
| China                       | 53        | 64     | 0.88%   |
| Unknown                     | 33        | 40     | 0.55%   |
| Micron/Crucial Technology   | 31        | 35     | 0.52%   |
| Gigabyte Technology         | 28        | 33     | 0.47%   |
| FORESEE                     | 26        | 29     | 0.43%   |
| Silicon Motion              | 24        | 27     | 0.4%    |
| Apple                       | 23        | 31     | 0.38%   |
| UMIS                        | 21        | 24     | 0.35%   |
| Phison                      | 19        | 22     | 0.32%   |
| Hewlett-Packard             | 19        | 25     | 0.32%   |
| LITEON                      | 16        | 20     | 0.27%   |
| Kingston Technology Company | 14        | 17     | 0.23%   |
| Lexar                       | 12        | 12     | 0.2%    |
| Acer                        | 12        | 13     | 0.2%    |
| XPG                         | 11        | 14     | 0.18%   |
| SPCC                        | 11        | 18     | 0.18%   |
| Realtek Semiconductor       | 11        | 17     | 0.18%   |
| Transcend                   | 10        | 11     | 0.17%   |
| Maxtor                      | 10        | 26     | 0.17%   |
| ADATA Technology            | 10        | 13     | 0.17%   |
| Fujitsu                     | 9         | 9      | 0.15%   |
| Union Memory (Shenzhen)     | 8         | 10     | 0.13%   |
| EVM                         | 8         | 10     | 0.13%   |
| TO Exter                    | 7         | 7      | 0.12%   |
| PNY                         | 7         | 9      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 295       | 4.68%   |
| Toshiba MQ04ABF100 1TB                            | 155       | 2.46%   |
| Toshiba MQ01ABD100 1TB                            | 111       | 1.76%   |
| Seagate ST1000DM010-2EP102 1TB                    | 91        | 1.44%   |
| Crucial CT240BX500SSD1 240GB                      | 81        | 1.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 74        | 1.17%   |
| Seagate ST1000LM049-2GH172 1TB                    | 69        | 1.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 68        | 1.08%   |
| Seagate ST500LT012-1DG142 500GB                   | 64        | 1.02%   |
| Kingston SA400S37240G 240GB SSD                   | 58        | 0.92%   |
| Intel NVMe SSD Drive 512GB                        | 52        | 0.82%   |
| Toshiba MQ01ABF050 500GB                          | 46        | 0.73%   |
| Toshiba DT01ACA100 1TB                            | 42        | 0.67%   |
| Seagate ST500DM002-1BD142 500GB                   | 42        | 0.67%   |
| SanDisk NVMe SSD Drive 512GB                      | 42        | 0.67%   |
| Intel SSDPEKNW512G8 512GB                         | 41        | 0.65%   |
| HGST HTS541010A9E680 1TB                          | 41        | 0.65%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 38        | 0.6%    |
| Seagate ST9500325AS 500GB                         | 38        | 0.6%    |
| SanDisk NVMe SSD Drive 256GB                      | 38        | 0.6%    |
| WDC WD10SPZX-24Z10 1TB                            | 36        | 0.57%   |
| Seagate ST2000LM007-1R8174 2TB                    | 36        | 0.57%   |
| Samsung NVMe SSD Drive 512GB                      | 36        | 0.57%   |
| Seagate ST1000LM048-2E7172 1TB                    | 35        | 0.56%   |
| Micron 2450_MTFDKBA512TFK 512GB                   | 33        | 0.52%   |
| HGST HTS721010A9E630 1TB                          | 33        | 0.52%   |
| Unknown                                           | 33        | 0.52%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 30        | 0.48%   |
| SK hynix NVMe SSD Drive 512GB                     | 30        | 0.48%   |
| Crucial CT480BX500SSD1 480GB                      | 29        | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 27        | 0.43%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 27        | 0.43%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 27        | 0.43%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 27        | 0.43%   |
| HGST HTS545050A7E680 500GB                        | 27        | 0.43%   |
| Samsung SSD 860 EVO 250GB                         | 26        | 0.41%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 26        | 0.41%   |
| Kingston SA400S37120G 120GB SSD                   | 26        | 0.41%   |
| Seagate ST3500312CS 500GB                         | 24        | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 23        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1229      | 1605   | 42.13%  |
| WDC                 | 808       | 1009   | 27.7%   |
| Toshiba             | 503       | 566    | 17.24%  |
| HGST                | 178       | 217    | 6.1%    |
| Hitachi             | 113       | 136    | 3.87%   |
| Samsung Electronics | 24        | 29     | 0.82%   |
| Unknown             | 22        | 26     | 0.75%   |
| Fujitsu             | 9         | 9      | 0.31%   |
| Apple               | 9         | 9      | 0.31%   |
| Hewlett-Packard     | 6         | 7      | 0.21%   |
| External            | 5         | 9      | 0.17%   |
| Maxtor              | 3         | 3      | 0.1%    |
| WD MediaMax         | 1         | 1      | 0.03%   |
| Synology            | 1         | 1      | 0.03%   |
| StoreJet            | 1         | 1      | 0.03%   |
| MARSHAL             | 1         | 1      | 0.03%   |
| Lenovo              | 1         | 1      | 0.03%   |
| KESU                | 1         | 2      | 0.03%   |
| IBM                 | 1         | 1      | 0.03%   |
| Unknown             | 1         | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 211       | 282    | 15.81%  |
| Samsung Electronics | 206       | 260    | 15.43%  |
| WDC                 | 198       | 244    | 14.83%  |
| Kingston            | 156       | 194    | 11.69%  |
| SanDisk             | 68        | 88     | 5.09%   |
| A-DATA Technology   | 66        | 73     | 4.94%   |
| China               | 52        | 63     | 3.9%    |
| SK hynix            | 37        | 39     | 2.77%   |
| Micron Technology   | 26        | 34     | 1.95%   |
| Intel               | 25        | 26     | 1.87%   |
| Gigabyte Technology | 23        | 26     | 1.72%   |
| FORESEE             | 18        | 21     | 1.35%   |
| Unknown             | 16        | 17     | 1.2%    |
| Toshiba             | 14        | 15     | 1.05%   |
| LITEON              | 14        | 18     | 1.05%   |
| Lexar               | 12        | 12     | 0.9%    |
| Apple               | 12        | 16     | 0.9%    |
| Hewlett-Packard     | 11        | 16     | 0.82%   |
| Seagate             | 10        | 10     | 0.75%   |
| Acer                | 10        | 11     | 0.75%   |
| SPCC                | 8         | 12     | 0.6%    |
| Transcend           | 7         | 8      | 0.52%   |
| TO Exter            | 7         | 7      | 0.52%   |
| PNY                 | 7         | 9      | 0.52%   |
| Maxtor              | 7         | 23     | 0.52%   |
| EVM                 | 6         | 8      | 0.45%   |
| Unknown             | 5         | 5      | 0.37%   |
| POWER               | 5         | 5      | 0.37%   |
| Zebronics           | 4         | 4      | 0.3%    |
| Netac               | 4         | 4      | 0.3%    |
| LITEONIT            | 4         | 7      | 0.3%    |
| Leven               | 4         | 4      | 0.3%    |
| KingSpec            | 4         | 4      | 0.3%    |
| HS-SSD-C100         | 4         | 5      | 0.3%    |
| StoreJet            | 3         | 3      | 0.22%   |
| Plextor             | 3         | 3      | 0.22%   |
| KLEVV               | 3         | 4      | 0.22%   |
| geonix              | 3         | 3      | 0.22%   |
| CONSISTENT          | 3         | 4      | 0.22%   |
| Aarvex              | 3         | 4      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2759      | 3634   | 48.21%  |
| NVMe    | 1553      | 2010   | 27.14%  |
| SSD     | 1255      | 1652   | 21.93%  |
| MMC     | 104       | 135    | 1.82%   |
| Unknown | 52        | 63     | 0.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3454      | 5184   | 65.88%  |
| NVMe | 1550      | 2001   | 29.56%  |
| SAS  | 135       | 174    | 2.57%   |
| MMC  | 104       | 135    | 1.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2084      | 2772   | 51.79%  |
| 0.51-1.0   | 1705      | 2142   | 42.37%  |
| 1.01-2.0   | 166       | 245    | 4.13%   |
| 3.01-4.0   | 40        | 71     | 0.99%   |
| 4.01-10.0  | 15        | 31     | 0.37%   |
| 2.01-3.0   | 11        | 17     | 0.27%   |
| 10.01-20.0 | 3         | 8      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1313      | 26.77%  |
| 101-250        | 1257      | 25.63%  |
| 501-1000       | 842       | 17.17%  |
| 51-100         | 440       | 8.97%   |
| 1001-2000      | 305       | 6.22%   |
| 21-50          | 279       | 5.69%   |
| 1-20           | 254       | 5.18%   |
| More than 3000 | 78        | 1.59%   |
| Unknown        | 69        | 1.41%   |
| 2001-3000      | 67        | 1.37%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1906      | 37.62%  |
| 21-50          | 1061      | 20.94%  |
| 101-250        | 699       | 13.8%   |
| 51-100         | 625       | 12.34%  |
| 251-500        | 385       | 7.6%    |
| 501-1000       | 212       | 4.18%   |
| 1001-2000      | 74        | 1.46%   |
| Unknown        | 69        | 1.36%   |
| More than 3000 | 21        | 0.41%   |
| 2001-3000      | 13        | 0.26%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 27        | 29     | 6.26%   |
| HGST HTS541010A9E680 1TB             | 14        | 14     | 3.25%   |
| HGST HTS545050A7E680 500GB           | 12        | 16     | 2.78%   |
| Toshiba MQ01ABD100 1TB               | 11        | 11     | 2.55%   |
| Seagate ST500DM002-1BD142 500GB      | 11        | 11     | 2.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 11        | 11     | 2.55%   |
| Seagate ST9500325AS 500GB            | 10        | 10     | 2.32%   |
| Seagate ST500LT012-1DG142 500GB      | 10        | 10     | 2.32%   |
| Seagate ST1000LM049-2GH172 1TB       | 10        | 12     | 2.32%   |
| Toshiba MQ04ABF100 1TB               | 6         | 7      | 1.39%   |
| Toshiba MQ01ABF050 500GB             | 6         | 6      | 1.39%   |
| Seagate ST500LT012-9WS142 500GB      | 6         | 7      | 1.39%   |
| Seagate ST500LM021-1KJ152 500GB      | 6         | 6      | 1.39%   |
| Seagate ST3500418AS 500GB            | 5         | 5      | 1.16%   |
| HGST HTS721010A9E630 1TB             | 5         | 5      | 1.16%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 4      | 0.93%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 4      | 0.93%   |
| Seagate ST2000LM007-1R8174 2TB       | 4         | 4      | 0.93%   |
| Seagate ST1000DM003-1ER162 1TB       | 4         | 4      | 0.93%   |
| HGST HTS545050A7E380 500GB           | 4         | 4      | 0.93%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 3      | 0.7%    |
| Toshiba DT01ACA100 1TB               | 3         | 5      | 0.7%    |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 4      | 0.7%    |
| Seagate ST9320325AS 320GB            | 3         | 3      | 0.7%    |
| Seagate ST9160314AS 160GB            | 3         | 4      | 0.7%    |
| Seagate ST3500312CS 500GB            | 3         | 3      | 0.7%    |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.7%    |
| Seagate ST1000DM010-2EP102 1TB       | 3         | 3      | 0.7%    |
| Seagate ST1000DM003-1CH162 1TB       | 3         | 3      | 0.7%    |
| Hitachi HTS547575A9E384 752GB        | 3         | 3      | 0.7%    |
| Hitachi HTS545032B9A300 320GB        | 3         | 5      | 0.7%    |
| Hitachi HTS543232A7A384 320GB        | 3         | 3      | 0.7%    |
| HGST HTS725050A7E630 500GB           | 3         | 3      | 0.7%    |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 2      | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 2      | 0.46%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 2      | 0.46%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 2      | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 2         | 2      | 0.46%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 6      | 0.46%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 2      | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 166       | 180    | 39.15%  |
| WDC                         | 76        | 89     | 17.92%  |
| Toshiba                     | 44        | 48     | 10.38%  |
| HGST                        | 42        | 46     | 9.91%   |
| Hitachi                     | 31        | 35     | 7.31%   |
| SK hynix                    | 13        | 15     | 3.07%   |
| Samsung Electronics         | 11        | 14     | 2.59%   |
| SanDisk                     | 7         | 7      | 1.65%   |
| Intel                       | 4         | 4      | 0.94%   |
| Crucial                     | 4         | 5      | 0.94%   |
| Apple                       | 3         | 3      | 0.71%   |
| A-DATA Technology           | 3         | 4      | 0.71%   |
| Micron Technology           | 2         | 2      | 0.47%   |
| Unknown                     | 2         | 2      | 0.47%   |
| YS                          | 1         | 1      | 0.24%   |
| Wibtek                      | 1         | 1      | 0.24%   |
| Unknown                     | 1         | 1      | 0.24%   |
| SPCC                        | 1         | 1      | 0.24%   |
| Secure                      | 1         | 1      | 0.24%   |
| POWER                       | 1         | 1      | 0.24%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.24%   |
| MARSHAL                     | 1         | 1      | 0.24%   |
| LITEONIT                    | 1         | 1      | 0.24%   |
| LITEON                      | 1         | 1      | 0.24%   |
| Leven                       | 1         | 1      | 0.24%   |
| Lenovo                      | 1         | 2      | 0.24%   |
| Innodisk                    | 1         | 1      | 0.24%   |
| IBM                         | 1         | 1      | 0.24%   |
| Gamers                      | 1         | 1      | 0.24%   |
| China                       | 1         | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 166       | 180    | 45.98%  |
| WDC                 | 69        | 81     | 19.11%  |
| Toshiba             | 43        | 47     | 11.91%  |
| HGST                | 42        | 46     | 11.63%  |
| Hitachi             | 31        | 35     | 8.59%   |
| Samsung Electronics | 5         | 7      | 1.39%   |
| Apple               | 3         | 3      | 0.83%   |
| MARSHAL             | 1         | 1      | 0.28%   |
| IBM                 | 1         | 1      | 0.28%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 357       | 401    | 85%     |
| SSD  | 42        | 46     | 10%     |
| NVMe | 21        | 24     | 5%      |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-001CA0 500GB         | 1         | 1      | 11.11%  |
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 1      | 11.11%  |
| Toshiba HDWD110 1TB                 | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 11.11%  |
| Seagate ST3320418AS 320GB           | 1         | 1      | 11.11%  |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1      | 11.11%  |
| Samsung Electronics SSD 980 500GB   | 1         | 2      | 11.11%  |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 11.11%  |
| Acer SSD FA100 256GB                | 1         | 1      | 11.11%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 33.33%  |
| WDC                 | 2         | 2      | 22.22%  |
| Toshiba             | 1         | 1      | 11.11%  |
| Samsung Electronics | 1         | 2      | 11.11%  |
| Apple               | 1         | 1      | 11.11%  |
| Acer                | 1         | 1      | 11.11%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2746      | 4328   | 55.42%  |
| Works    | 1787      | 2685   | 36.06%  |
| Malfunc  | 413       | 471    | 8.34%   |
| Failed   | 9         | 10     | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3441      | 60.37%  |
| AMD                                     | 716       | 12.56%  |
| Samsung Electronics                     | 375       | 6.58%   |
| SanDisk                                 | 308       | 5.4%    |
| SK hynix                                | 164       | 2.88%   |
| Micron Technology                       | 148       | 2.6%    |
| KIOXIA                                  | 90        | 1.58%   |
| Kingston Technology Company             | 86        | 1.51%   |
| Toshiba America Info Systems            | 60        | 1.05%   |
| Micron/Crucial Technology               | 59        | 1.04%   |
| Union Memory (Shenzhen)                 | 31        | 0.54%   |
| Silicon Motion                          | 29        | 0.51%   |
| Phison Electronics                      | 26        | 0.46%   |
| ADATA Technology                        | 26        | 0.46%   |
| ASMedia Technology                      | 25        | 0.44%   |
| Nvidia                                  | 17        | 0.3%    |
| Realtek Semiconductor                   | 16        | 0.28%   |
| Shenzhen Longsys Electronics            | 11        | 0.19%   |
| Yangtze Memory Technologies             | 10        | 0.18%   |
| Solid State Storage Technology          | 8         | 0.14%   |
| JMicron Technology                      | 8         | 0.14%   |
| Marvell Technology Group                | 7         | 0.12%   |
| Silicon Integrated Systems [SiS]        | 4         | 0.07%   |
| LSI Logic / Symbios Logic               | 4         | 0.07%   |
| Lite-On Technology                      | 4         | 0.07%   |
| Broadcom / LSI                          | 4         | 0.07%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.05%   |
| Lenovo                                  | 3         | 0.05%   |
| Apple                                   | 3         | 0.05%   |
| VIA Technologies                        | 2         | 0.04%   |
| Shenzhen Unionmemory Information System | 2         | 0.04%   |
| INNOGRIT                                | 2         | 0.04%   |
| Transcend                               | 1         | 0.02%   |
| Solidigm                                | 1         | 0.02%   |
| Seagate Technology                      | 1         | 0.02%   |
| Netac Technology                        | 1         | 0.02%   |
| Integrated Technology Express           | 1         | 0.02%   |
| Hosin Global Electronics                | 1         | 0.02%   |
| Hewlett-Packard                         | 1         | 0.02%   |
| Biwin Storage Technology                | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 609       | 9.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 501       | 7.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 349       | 5.48%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 209       | 3.28%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 207       | 3.25%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 187       | 2.94%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 156       | 2.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 150       | 2.36%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 146       | 2.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 131       | 2.06%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 128       | 2.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 128       | 2.01%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 121       | 1.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 118       | 1.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 114       | 1.79%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 111       | 1.74%   |
| Intel SSD 660P Series                                                                   | 110       | 1.73%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 97        | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 87        | 1.37%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 82        | 1.29%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 76        | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 75        | 1.18%   |
| AMD 400 Series Chipset SATA Controller                                                  | 64        | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 61        | 0.96%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                                   | 57        | 0.89%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 57        | 0.89%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 55        | 0.86%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 53        | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 52        | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 51        | 0.8%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 47        | 0.74%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 47        | 0.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 46        | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 45        | 0.71%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                             | 45        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 44        | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 43        | 0.68%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 41        | 0.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 40        | 0.63%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 40        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3326      | 56.5%   |
| NVMe | 1559      | 26.48%  |
| RAID | 609       | 10.34%  |
| IDE  | 388       | 6.59%   |
| SAS  | 3         | 0.05%   |
| SCSI | 2         | 0.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3694      | 79.49%  |
| AMD          | 931       | 20.03%  |
| ARM          | 21        | 0.45%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 199       | 4.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 125       | 2.69%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 106       | 2.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 94        | 2.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 83        | 1.78%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 80        | 1.72%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 59        | 1.27%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 54        | 1.16%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 53        | 1.14%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 51        | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 50        | 1.08%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 50        | 1.08%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 49        | 1.05%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 47        | 1.01%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 45        | 0.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 44        | 0.95%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 41        | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 40        | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 40        | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 39        | 0.84%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 38        | 0.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 37        | 0.8%    |
| Intel Core i3-10110U CPU @ 2.10GHz            | 36        | 0.77%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 35        | 0.75%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 34        | 0.73%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 33        | 0.71%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 33        | 0.71%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 32        | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 31        | 0.67%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 30        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 0.62%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 29        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 0.6%    |
| Intel Core i5-10400 CPU @ 2.90GHz             | 28        | 0.6%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 26        | 0.56%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 25        | 0.54%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 0.52%   |
| Intel 12th Gen Core i5-1240P                  | 24        | 0.52%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 24        | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1374      | 29.55%  |
| Intel Core i3           | 759       | 16.33%  |
| Intel Core i7           | 574       | 12.35%  |
| Other                   | 459       | 9.87%   |
| AMD Ryzen 5             | 373       | 8.02%   |
| AMD Ryzen 7             | 163       | 3.51%   |
| Intel Pentium           | 145       | 3.12%   |
| Intel Core 2 Duo        | 135       | 2.9%    |
| Intel Celeron           | 82        | 1.76%   |
| AMD Ryzen 3             | 75        | 1.61%   |
| Intel Pentium Dual-Core | 60        | 1.29%   |
| AMD A6                  | 47        | 1.01%   |
| AMD Ryzen 9             | 33        | 0.71%   |
| AMD A8                  | 33        | 0.71%   |
| AMD A4                  | 31        | 0.67%   |
| Intel Atom              | 29        | 0.62%   |
| Intel Xeon              | 27        | 0.58%   |
| AMD FX                  | 24        | 0.52%   |
| Intel Pentium Dual      | 21        | 0.45%   |
| Intel Core 2            | 18        | 0.39%   |
| Intel Core 2 Quad       | 17        | 0.37%   |
| AMD A10                 | 17        | 0.37%   |
| AMD E1                  | 15        | 0.32%   |
| Intel Pentium Silver    | 12        | 0.26%   |
| Intel Core i9           | 9         | 0.19%   |
| AMD Ryzen 7 PRO         | 9         | 0.19%   |
| AMD E2                  | 8         | 0.17%   |
| Intel Pentium Gold      | 7         | 0.15%   |
| Intel Pentium 4         | 7         | 0.15%   |
| AMD Athlon II X2        | 7         | 0.15%   |
| AMD Ryzen 5 PRO         | 6         | 0.13%   |
| AMD E                   | 6         | 0.13%   |
| ARM BCM                 | 5         | 0.11%   |
| AMD Sempron             | 5         | 0.11%   |
| AMD Athlon              | 5         | 0.11%   |
| Intel Pentium D         | 4         | 0.09%   |
| AMD Ryzen Threadripper  | 4         | 0.09%   |
| AMD Phenom II X4        | 4         | 0.09%   |
| AMD Phenom II X2        | 4         | 0.09%   |
| Intel Xeon Silver       | 3         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2083      | 44.8%   |
| 4      | 1674      | 36%     |
| 6      | 436       | 9.38%   |
| 8      | 255       | 5.48%   |
| 12     | 66        | 1.42%   |
| 1      | 58        | 1.25%   |
| 10     | 26        | 0.56%   |
| 14     | 21        | 0.45%   |
| 16     | 12        | 0.26%   |
| 3      | 8         | 0.17%   |
| 24     | 7         | 0.15%   |
| 32     | 2         | 0.04%   |
| 36     | 1         | 0.02%   |
| 20     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4630      | 99.63%  |
| 2      | 17        | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 3574      | 76.89%  |
| 1      | 1071      | 23.04%  |
| 4      | 2         | 0.04%   |
| 12     | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4592      | 98.75%  |
| Unknown        | 51        | 1.1%    |
| 32-bit         | 6         | 0.13%   |
| 64-bit         | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1168      | 24.34%  |
| 0x806ea    | 233       | 4.86%   |
| 0x306a9    | 232       | 4.83%   |
| 0x806ec    | 229       | 4.77%   |
| 0x206a7    | 215       | 4.48%   |
| 0x806c1    | 166       | 3.46%   |
| 0x906ea    | 158       | 3.29%   |
| 0x40651    | 154       | 3.21%   |
| 0x406e3    | 153       | 3.19%   |
| 0x806e9    | 148       | 3.08%   |
| 0x1067a    | 124       | 2.58%   |
| 0x306c3    | 114       | 2.38%   |
| 0x306d4    | 112       | 2.33%   |
| 0x08108109 | 90        | 1.88%   |
| 0x706e5    | 82        | 1.71%   |
| 0x0a50000c | 71        | 1.48%   |
| 0x20655    | 64        | 1.33%   |
| 0x906e9    | 63        | 1.31%   |
| 0x806eb    | 62        | 1.29%   |
| 0x506e3    | 57        | 1.19%   |
| 0x08108102 | 50        | 1.04%   |
| 0xa0652    | 44        | 0.92%   |
| 0x06006705 | 44        | 0.92%   |
| 0x6fd      | 38        | 0.79%   |
| 0x08600106 | 37        | 0.77%   |
| 0x906a3    | 34        | 0.71%   |
| 0x08608103 | 34        | 0.71%   |
| 0x07030105 | 32        | 0.67%   |
| 0x20652    | 31        | 0.65%   |
| 0x08600104 | 30        | 0.63%   |
| 0xa0655    | 28        | 0.58%   |
| 0x0a50000d | 28        | 0.58%   |
| 0x08701021 | 28        | 0.58%   |
| 0x0810100b | 28        | 0.58%   |
| 0x906ed    | 24        | 0.5%    |
| 0x30678    | 23        | 0.48%   |
| 0x08101007 | 22        | 0.46%   |
| 0x06001119 | 22        | 0.46%   |
| 0x010000c8 | 21        | 0.44%   |
| 0x706a1    | 16        | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1172      | 25.2%   |
| Haswell          | 347       | 7.46%   |
| IvyBridge        | 296       | 6.36%   |
| Skylake          | 280       | 6.02%   |
| SandyBridge      | 275       | 5.91%   |
| TigerLake        | 236       | 5.07%   |
| Zen+             | 194       | 4.17%   |
| Penryn           | 178       | 3.83%   |
| Zen 2            | 166       | 3.57%   |
| Broadwell        | 149       | 3.2%    |
| Unknown          | 147       | 3.16%   |
| IceLake          | 134       | 2.88%   |
| Zen 3            | 133       | 2.86%   |
| CometLake        | 120       | 2.58%   |
| Westmere         | 119       | 2.56%   |
| Alderlake Hybrid | 108       | 2.32%   |
| Zen              | 88        | 1.89%   |
| Excavator        | 85        | 1.83%   |
| Core             | 82        | 1.76%   |
| Silvermont       | 68        | 1.46%   |
| Puma             | 53        | 1.14%   |
| Piledriver       | 47        | 1.01%   |
| Goldmont plus    | 29        | 0.62%   |
| K10              | 25        | 0.54%   |
| Goldmont         | 23        | 0.49%   |
| Nehalem          | 15        | 0.32%   |
| K10 Llano        | 13        | 0.28%   |
| Bobcat           | 13        | 0.28%   |
| NetBurst         | 12        | 0.26%   |
| Bonnell          | 11        | 0.24%   |
| Jaguar           | 7         | 0.15%   |
| Tremont          | 6         | 0.13%   |
| Steamroller      | 6         | 0.13%   |
| Bulldozer        | 6         | 0.13%   |
| K8 Hammer        | 4         | 0.09%   |
| P6               | 3         | 0.06%   |
| Gracemont        | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3368      | 56.7%   |
| Nvidia                           | 1379      | 23.22%  |
| AMD                              | 1178      | 19.83%  |
| Matrox Electronics Systems       | 6         | 0.1%    |
| Silicon Integrated Systems [SiS] | 4         | 0.07%   |
| ASPEED Technology                | 3         | 0.05%   |
| VIA Technologies                 | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 271       | 4.47%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 241       | 3.97%   |
| Intel HD Graphics 620                                                                 | 197       | 3.25%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 194       | 3.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 193       | 3.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 189       | 3.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 186       | 3.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 185       | 3.05%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 172       | 2.84%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 170       | 2.8%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 168       | 2.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 155       | 2.56%   |
| Intel HD Graphics 5500                                                                | 130       | 2.14%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 114       | 1.88%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 110       | 1.81%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 101       | 1.67%   |
| Intel Core Processor Integrated Graphics Controller                                   | 88        | 1.45%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 83        | 1.37%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 75        | 1.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 72        | 1.19%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 71        | 1.17%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 67        | 1.1%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 66        | 1.09%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 62        | 1.02%   |
| Intel HD Graphics 630                                                                 | 61        | 1.01%   |
| AMD Lucienne                                                                          | 61        | 1.01%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 60        | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 58        | 0.96%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 56        | 0.92%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 56        | 0.92%   |
| Nvidia GP108M [GeForce MX250]                                                         | 53        | 0.87%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 49        | 0.81%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 46        | 0.76%   |
| Nvidia GP108M [GeForce MX150]                                                         | 45        | 0.74%   |
| Nvidia GM108M [GeForce MX130]                                                         | 43        | 0.71%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 43        | 0.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 43        | 0.71%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 42        | 0.69%   |
| Intel HD Graphics 530                                                                 | 42        | 0.69%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 41        | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2224      | 47.6%   |
| Intel + Nvidia     | 815       | 17.44%  |
| 1 x AMD            | 628       | 13.44%  |
| 1 x Nvidia         | 389       | 8.33%   |
| Intel + AMD        | 297       | 6.36%   |
| AMD + Nvidia       | 171       | 3.66%   |
| 2 x AMD            | 87        | 1.86%   |
| Other              | 27        | 0.58%   |
| 2 x Intel          | 15        | 0.32%   |
| 1 x Matrox         | 6         | 0.13%   |
| 2 x Nvidia         | 4         | 0.09%   |
| 1 x SiS            | 4         | 0.09%   |
| 1 x ASPEED         | 2         | 0.04%   |
| 1 x VIA            | 1         | 0.02%   |
| Nvidia + ASPEED    | 1         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3811      | 80.9%   |
| Proprietary | 754       | 16.01%  |
| Unknown     | 146       | 3.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2947      | 61.64%  |
| 1.01-2.0   | 713       | 14.91%  |
| 0.01-0.5   | 420       | 8.78%   |
| 3.01-4.0   | 342       | 7.15%   |
| 0.51-1.0   | 216       | 4.52%   |
| 5.01-6.0   | 69        | 1.44%   |
| 7.01-8.0   | 43        | 0.9%    |
| 8.01-16.0  | 18        | 0.38%   |
| 16.01-24.0 | 8         | 0.17%   |
| 2.01-3.0   | 5         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 786       | 16.5%   |
| Chimei Innolux          | 737       | 15.47%  |
| AU Optronics            | 718       | 15.07%  |
| LG Display              | 557       | 11.69%  |
| Samsung Electronics     | 388       | 8.14%   |
| Dell                    | 266       | 5.58%   |
| Goldstar                | 207       | 4.34%   |
| BenQ                    | 133       | 2.79%   |
| Acer                    | 125       | 2.62%   |
| PANDA                   | 115       | 2.41%   |
| Hewlett-Packard         | 91        | 1.91%   |
| Lenovo                  | 77        | 1.62%   |
| AOC                     | 54        | 1.13%   |
| Sharp                   | 51        | 1.07%   |
| Chi Mei Optoelectronics | 41        | 0.86%   |
| InfoVision              | 38        | 0.8%    |
| Apple                   | 32        | 0.67%   |
| ViewSonic               | 28        | 0.59%   |
| Sony                    | 28        | 0.59%   |
| HCL                     | 20        | 0.42%   |
| TMX                     | 18        | 0.38%   |
| Philips                 | 17        | 0.36%   |
| Unknown                 | 15        | 0.31%   |
| LG Electronics          | 13        | 0.27%   |
| LG Philips              | 9         | 0.19%   |
| CSO                     | 9         | 0.19%   |
| ASUSTek Computer        | 9         | 0.19%   |
| STD                     | 8         | 0.17%   |
| Panasonic               | 8         | 0.17%   |
| InnoLux Display         | 8         | 0.17%   |
| HKC                     | 7         | 0.15%   |
| Toshiba                 | 6         | 0.13%   |
| MSI                     | 6         | 0.13%   |
| Gigabyte Technology     | 6         | 0.13%   |
| Ancor Communications    | 6         | 0.13%   |
| Xiaomi                  | 5         | 0.1%    |
| SGT                     | 5         | 0.1%    |
| RTK                     | 4         | 0.08%   |
| AOpen                   | 4         | 0.08%   |
| Unknown                 | 4         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 91        | 1.89%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 72        | 1.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 47        | 0.98%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 40        | 0.83%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 37        | 0.77%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 37        | 0.77%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 36        | 0.75%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 36        | 0.75%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 36        | 0.75%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                     | 33        | 0.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 30        | 0.62%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 29        | 0.6%    |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 28        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 27        | 0.56%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 26        | 0.54%   |
| BenQ GW2283 BNQ78E9 1920x1080 476x268mm 21.5-inch                    | 26        | 0.54%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 25        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 25        | 0.52%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 24        | 0.5%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 24        | 0.5%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 23        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 23        | 0.48%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 23        | 0.48%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 21        | 0.44%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 20        | 0.42%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 20        | 0.42%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 20        | 0.42%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 20        | 0.42%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 17        | 0.35%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 17        | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 16        | 0.33%   |
| Dell E1916HV DELF06C 1366x768 409x230mm 18.5-inch                    | 16        | 0.33%   |
| BOE LCD Monitor BOE07BD 1920x1080 309x174mm 14.0-inch                | 16        | 0.33%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 16        | 0.33%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 16        | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 15        | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 15        | 0.31%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 15        | 0.31%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 15        | 0.31%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 15        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2293      | 49.54%  |
| 1366x768 (WXGA)    | 1572      | 33.96%  |
| 1600x900 (HD+)     | 140       | 3.02%   |
| 3840x2160 (4K)     | 113       | 2.44%   |
| 2560x1440 (QHD)    | 88        | 1.9%    |
| 1440x900 (WXGA+)   | 64        | 1.38%   |
| 1920x1200 (WUXGA)  | 49        | 1.06%   |
| 1280x800 (WXGA)    | 49        | 1.06%   |
| 2560x1600          | 34        | 0.73%   |
| 1360x768           | 27        | 0.58%   |
| 1280x1024 (SXGA)   | 26        | 0.56%   |
| 2560x1080          | 25        | 0.54%   |
| 2880x1800          | 22        | 0.48%   |
| 1680x1050 (WSXGA+) | 19        | 0.41%   |
| Unknown            | 15        | 0.32%   |
| 3200x2000          | 12        | 0.26%   |
| 3840x1080          | 9         | 0.19%   |
| 1024x768 (XGA)     | 8         | 0.17%   |
| 1024x600           | 7         | 0.15%   |
| 1280x720 (HD)      | 6         | 0.13%   |
| 3840x2400          | 4         | 0.09%   |
| 3440x1440          | 4         | 0.09%   |
| 800x1280           | 3         | 0.06%   |
| 4093x4093          | 3         | 0.06%   |
| 3456x2160          | 3         | 0.06%   |
| 2288x1287          | 3         | 0.06%   |
| 2240x1400          | 3         | 0.06%   |
| 2160x1440          | 3         | 0.06%   |
| 3072x1920          | 2         | 0.04%   |
| 2736x1824          | 2         | 0.04%   |
| 2256x1504          | 2         | 0.04%   |
| 1280x768           | 2         | 0.04%   |
| 1152x864           | 2         | 0.04%   |
| 8160x4627          | 1         | 0.02%   |
| 6400x2160          | 1         | 0.02%   |
| 5760x2160          | 1         | 0.02%   |
| 4480x1080          | 1         | 0.02%   |
| 3840x1100          | 1         | 0.02%   |
| 3286x1080          | 1         | 0.02%   |
| 3200x900           | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2041      | 42.84%  |
| 13      | 621       | 13.04%  |
| 14      | 600       | 12.59%  |
| 21      | 279       | 5.86%   |
| 18      | 237       | 4.97%   |
| 24      | 143       | 3%      |
| 23      | 112       | 2.35%   |
| 19      | 112       | 2.35%   |
| Unknown | 102       | 2.14%   |
| 27      | 99        | 2.08%   |
| 20      | 59        | 1.24%   |
| 17      | 57        | 1.2%    |
| 12      | 54        | 1.13%   |
| 31      | 43        | 0.9%    |
| 16      | 39        | 0.82%   |
| 34      | 23        | 0.48%   |
| 11      | 20        | 0.42%   |
| 72      | 13        | 0.27%   |
| 26      | 13        | 0.27%   |
| 40      | 11        | 0.23%   |
| 32      | 11        | 0.23%   |
| 22      | 11        | 0.23%   |
| 10      | 10        | 0.21%   |
| 84      | 8         | 0.17%   |
| 46      | 7         | 0.15%   |
| 65      | 6         | 0.13%   |
| 25      | 5         | 0.1%    |
| 52      | 4         | 0.08%   |
| 54      | 3         | 0.06%   |
| 42      | 3         | 0.06%   |
| 39      | 3         | 0.06%   |
| 7       | 3         | 0.06%   |
| 142     | 2         | 0.04%   |
| 86      | 2         | 0.04%   |
| 36      | 2         | 0.04%   |
| 63      | 1         | 0.02%   |
| 61      | 1         | 0.02%   |
| 58      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 43      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3107      | 65.52%  |
| 401-500        | 686       | 14.47%  |
| 501-600        | 343       | 7.23%   |
| 201-300        | 239       | 5.04%   |
| 351-400        | 102       | 2.15%   |
| Unknown        | 102       | 2.15%   |
| 601-700        | 56        | 1.18%   |
| 701-800        | 36        | 0.76%   |
| 1001-1500      | 26        | 0.55%   |
| 1501-2000      | 21        | 0.44%   |
| 801-900        | 15        | 0.32%   |
| 901-1000       | 4         | 0.08%   |
| 1-100          | 3         | 0.06%   |
| More than 2000 | 2         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 4010      | 89.81%  |
| 16/10   | 253       | 5.67%   |
| Unknown | 97        | 2.17%   |
| 4/3     | 25        | 0.56%   |
| 21/9    | 25        | 0.56%   |
| 5/4     | 24        | 0.54%   |
| 3/2     | 11        | 0.25%   |
| 6/5     | 6         | 0.13%   |
| 2.00    | 5         | 0.11%   |
| 0.67    | 3         | 0.07%   |
| 1.00    | 2         | 0.04%   |
| 0.56    | 2         | 0.04%   |
| 32/9    | 1         | 0.02%   |
| 3.40    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2027      | 42.6%   |
| 81-90          | 1101      | 23.14%  |
| 201-250        | 463       | 9.73%   |
| 141-150        | 248       | 5.21%   |
| 151-200        | 231       | 4.85%   |
| 71-80          | 124       | 2.61%   |
| 301-350        | 102       | 2.14%   |
| Unknown        | 102       | 2.14%   |
| 351-500        | 78        | 1.64%   |
| 61-70          | 44        | 0.92%   |
| More than 1000 | 41        | 0.86%   |
| 121-130        | 40        | 0.84%   |
| 111-120        | 35        | 0.74%   |
| 251-300        | 33        | 0.69%   |
| 501-1000       | 28        | 0.59%   |
| 51-60          | 21        | 0.44%   |
| 91-100         | 17        | 0.36%   |
| 41-50          | 10        | 0.21%   |
| 131-140        | 10        | 0.21%   |
| 1-40           | 3         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1803      | 38.29%  |
| 101-120       | 1547      | 32.85%  |
| 51-100        | 944       | 20.05%  |
| 161-240       | 203       | 4.31%   |
| Unknown       | 102       | 2.17%   |
| More than 240 | 62        | 1.32%   |
| 1-50          | 48        | 1.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 4170      | 88.59%  |
| 2     | 380       | 8.07%   |
| 0     | 148       | 3.14%   |
| 3     | 9         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3124      | 42.38%  |
| Intel                             | 1932      | 26.21%  |
| Qualcomm Atheros                  | 885       | 12.01%  |
| Broadcom                          | 305       | 4.14%   |
| Ralink Technology                 | 133       | 1.8%    |
| MediaTek                          | 126       | 1.71%   |
| Xiaomi                            | 111       | 1.51%   |
| TP-Link                           | 105       | 1.42%   |
| Ralink                            | 71        | 0.96%   |
| Samsung Electronics               | 68        | 0.92%   |
| OPPO Electronics                  | 67        | 0.91%   |
| Broadcom Limited                  | 61        | 0.83%   |
| Qualcomm                          | 46        | 0.62%   |
| D-Link                            | 35        | 0.47%   |
| Marvell Technology Group          | 33        | 0.45%   |
| ASIX Electronics                  | 30        | 0.41%   |
| OnePlus Technology (Shenzhen)     | 25        | 0.34%   |
| Huawei Technologies               | 24        | 0.33%   |
| Motorola PCS                      | 21        | 0.28%   |
| Qualcomm Atheros Communications   | 15        | 0.2%    |
| Foxconn / Hon Hai                 | 15        | 0.2%    |
| Nvidia                            | 13        | 0.18%   |
| ICS Advent                        | 10        | 0.14%   |
| Google                            | 9         | 0.12%   |
| vivo                              | 8         | 0.11%   |
| NetGear                           | 8         | 0.11%   |
| Lenovo                            | 7         | 0.09%   |
| JMicron Technology                | 7         | 0.09%   |
| Edimax Technology                 | 6         | 0.08%   |
| DisplayLink                       | 6         | 0.08%   |
| NTmore                            | 5         | 0.07%   |
| HMD Global                        | 5         | 0.07%   |
| Dell                              | 5         | 0.07%   |
| ASUSTek Computer                  | 5         | 0.07%   |
| Microchip Technology              | 4         | 0.05%   |
| D-Link System                     | 4         | 0.05%   |
| Ericsson Business Mobile Networks | 3         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.03%   |
| Spreadtrum Communications         | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2053      | 23.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 700       | 8.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 315       | 3.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 175       | 2.04%   |
| Intel Wi-Fi 6 AX201                                               | 174       | 2.03%   |
| Intel Wi-Fi 6 AX200                                               | 160       | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 155       | 1.81%   |
| Intel Wireless 8265 / 8275                                        | 152       | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 130       | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 118       | 1.38%   |
| Ralink MT7601U Wireless Adapter                                   | 116       | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 113       | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 110       | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                     | 109       | 1.27%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 105       | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 104       | 1.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 94        | 1.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 93        | 1.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 88        | 1.03%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 86        | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 86        | 1%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 86        | 1%      |
| Intel Wireless 7265                                               | 84        | 0.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 80        | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 79        | 0.92%   |
| Intel Wireless 3165                                               | 79        | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 74        | 0.86%   |
| Intel Wireless 3160                                               | 69        | 0.81%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 66        | 0.77%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 61        | 0.71%   |
| OPPO RMX2027                                                      | 59        | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 57        | 0.67%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 55        | 0.64%   |
| Intel Wireless 8260                                               | 54        | 0.63%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 51        | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 45        | 0.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 44        | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 44        | 0.51%   |
| Intel Wireless 7260                                               | 42        | 0.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 38        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1679      | 39.66%  |
| Realtek Semiconductor             | 968       | 22.86%  |
| Qualcomm Atheros                  | 788       | 18.61%  |
| Broadcom                          | 255       | 6.02%   |
| Ralink Technology                 | 133       | 3.14%   |
| MediaTek                          | 108       | 2.55%   |
| TP-Link                           | 96        | 2.27%   |
| Ralink                            | 70        | 1.65%   |
| Broadcom Limited                  | 47        | 1.11%   |
| D-Link                            | 35        | 0.83%   |
| Qualcomm Atheros Communications   | 15        | 0.35%   |
| Qualcomm                          | 9         | 0.21%   |
| NetGear                           | 8         | 0.19%   |
| Edimax Technology                 | 6         | 0.14%   |
| Dell                              | 4         | 0.09%   |
| Sierra Wireless                   | 2         | 0.05%   |
| D-Link System                     | 2         | 0.05%   |
| ASUSTek Computer                  | 2         | 0.05%   |
| Wacom                             | 1         | 0.02%   |
| Philips (or NXP)                  | 1         | 0.02%   |
| Micro Star International          | 1         | 0.02%   |
| Marvell Technology Group          | 1         | 0.02%   |
| IMC Networks                      | 1         | 0.02%   |
| Ericsson Business Mobile Networks | 1         | 0.02%   |
| Belkin Components                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 315       | 7.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 175       | 4.11%   |
| Intel Wi-Fi 6 AX201                                            | 174       | 4.09%   |
| Intel Wi-Fi 6 AX200                                            | 160       | 3.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 155       | 3.64%   |
| Intel Wireless 8265 / 8275                                     | 152       | 3.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 130       | 3.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 118       | 2.77%   |
| Ralink MT7601U Wireless Adapter                                | 116       | 2.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 113       | 2.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 110       | 2.59%   |
| Broadcom BCM43142 802.11b/g/n                                  | 109       | 2.56%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 105       | 2.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 104       | 2.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 94        | 2.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 93        | 2.19%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 86        | 2.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 86        | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 86        | 2.02%   |
| Intel Wireless 7265                                            | 84        | 1.98%   |
| Intel Wireless 3165                                            | 79        | 1.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 78        | 1.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 74        | 1.74%   |
| Intel Wireless 3160                                            | 69        | 1.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 66        | 1.55%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 61        | 1.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 57        | 1.34%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 55        | 1.29%   |
| Intel Wireless 8260                                            | 54        | 1.27%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 45        | 1.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 44        | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 44        | 1.03%   |
| Intel Wireless 7260                                            | 42        | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 37        | 0.87%   |
| Intel Wireless-AC 9260                                         | 34        | 0.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 34        | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 26        | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 26        | 0.61%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 24        | 0.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 21        | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2855      | 67.7%   |
| Intel                            | 609       | 14.44%  |
| Qualcomm Atheros                 | 142       | 3.37%   |
| Xiaomi                           | 111       | 2.63%   |
| Broadcom                         | 75        | 1.78%   |
| Samsung Electronics              | 68        | 1.61%   |
| OPPO Electronics                 | 67        | 1.59%   |
| Qualcomm                         | 37        | 0.88%   |
| Marvell Technology Group         | 32        | 0.76%   |
| ASIX Electronics                 | 30        | 0.71%   |
| MediaTek                         | 20        | 0.47%   |
| Huawei Technologies              | 20        | 0.47%   |
| OnePlus Technology (Shenzhen)    | 19        | 0.45%   |
| Broadcom Limited                 | 14        | 0.33%   |
| Motorola PCS                     | 13        | 0.31%   |
| Nvidia                           | 12        | 0.28%   |
| ICS Advent                       | 10        | 0.24%   |
| TP-Link                          | 9         | 0.21%   |
| Google                           | 9         | 0.21%   |
| JMicron Technology               | 7         | 0.17%   |
| vivo                             | 6         | 0.14%   |
| Lenovo                           | 6         | 0.14%   |
| DisplayLink                      | 6         | 0.14%   |
| NTmore                           | 5         | 0.12%   |
| HMD Global                       | 5         | 0.12%   |
| Foxconn / Hon Hai                | 4         | 0.09%   |
| Microchip Technology             | 3         | 0.07%   |
| ASUSTek Computer                 | 3         | 0.07%   |
| Spreadtrum Communications        | 2         | 0.05%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| D-Link System                    | 2         | 0.05%   |
| Attansic Technology              | 2         | 0.05%   |
| Aquantia                         | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.02%   |
| VIA Technologies                 | 1         | 0.02%   |
| Standard Microsystems            | 1         | 0.02%   |
| LG Electronics                   | 1         | 0.02%   |
| LeEco                            | 1         | 0.02%   |
| HTC (High Tech Computer)         | 1         | 0.02%   |
| Emulex                           | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2053      | 48.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 700       | 16.42%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 88        | 2.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 79        | 1.85%   |
| OPPO RMX2027                                                      | 59        | 1.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 51        | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 38        | 0.89%   |
| Intel Ethernet Connection I219-LM                                 | 36        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 35        | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 0.8%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 32        | 0.75%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 31        | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 31        | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 0.7%    |
| Intel 82579V Gigabit Network Connection                           | 29        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 28        | 0.66%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 27        | 0.63%   |
| Intel I211 Gigabit Network Connection                             | 27        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 27        | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 24        | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 23        | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 20        | 0.47%   |
| Intel Ethernet Connection (3) I218-LM                             | 20        | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 19        | 0.45%   |
| OnePlus (Shenzhen) OnePlus                                        | 19        | 0.45%   |
| Intel Ethernet Connection (10) I219-V                             | 17        | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.38%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.38%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.35%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.35%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.35%   |
| Intel Ethernet Connection (6) I219-LM                             | 15        | 0.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.35%   |
| MediaTek Wiko U316AT                                              | 14        | 0.33%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.3%    |
| Motorola PCS motorola one macro                                   | 13        | 0.3%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4081      | 51.3%   |
| Ethernet | 3824      | 48.07%  |
| Unknown  | 33        | 0.41%   |
| Modem    | 17        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3378      | 73.05%  |
| Ethernet | 1241      | 26.84%  |
| Unknown  | 4         | 0.09%   |
| Modem    | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2813      | 60.39%  |
| 1     | 1734      | 37.23%  |
| 0     | 67        | 1.44%   |
| 3     | 33        | 0.71%   |
| 4     | 8         | 0.17%   |
| 6     | 2         | 0.04%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3753      | 79.36%  |
| Yes  | 976       | 20.64%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1475      | 42.13%  |
| Realtek Semiconductor           | 556       | 15.88%  |
| Qualcomm Atheros Communications | 480       | 13.71%  |
| IMC Networks                    | 178       | 5.08%   |
| Broadcom                        | 173       | 4.94%   |
| Cambridge Silicon Radio         | 146       | 4.17%   |
| Lite-On Technology              | 136       | 3.88%   |
| Foxconn / Hon Hai               | 110       | 3.14%   |
| Ralink                          | 55        | 1.57%   |
| Dell                            | 38        | 1.09%   |
| Apple                           | 36        | 1.03%   |
| TP-Link                         | 21        | 0.6%    |
| Hewlett-Packard                 | 18        | 0.51%   |
| MediaTek                        | 14        | 0.4%    |
| Toshiba                         | 10        | 0.29%   |
| Foxconn International           | 10        | 0.29%   |
| ASUSTek Computer                | 9         | 0.26%   |
| Realtek                         | 8         | 0.23%   |
| Ralink Technology               | 7         | 0.2%    |
| Opticis                         | 5         | 0.14%   |
| Integrated System Solution      | 4         | 0.11%   |
| USI                             | 2         | 0.06%   |
| SINO WEALTH                     | 2         | 0.06%   |
| Chicony Electronics             | 2         | 0.06%   |
| Unknown                         | 2         | 0.06%   |
| Micro Star International        | 1         | 0.03%   |
| Belkin Components               | 1         | 0.03%   |
| Alps Electric                   | 1         | 0.03%   |
| Accel Semiconductor             | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 472       | 13.48%  |
| Realtek Bluetooth Radio                                                             | 350       | 9.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 333       | 9.51%   |
| Intel AX201 Bluetooth                                                               | 322       | 9.19%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 287       | 8.2%    |
| Intel AX200 Bluetooth                                                               | 157       | 4.48%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 154       | 4.4%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 146       | 4.17%   |
| Intel Bluetooth Device                                                              | 85        | 2.43%   |
| IMC Networks Bluetooth Radio                                                        | 67        | 1.91%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 58        | 1.66%   |
| IMC Networks Bluetooth Device                                                       | 56        | 1.6%    |
| Ralink RT3290 Bluetooth                                                             | 55        | 1.57%   |
| IMC Networks Wireless_Device                                                        | 52        | 1.48%   |
| Lite-On Bluetooth Device                                                            | 49        | 1.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 48        | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 44        | 1.26%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 42        | 1.2%    |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 42        | 1.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 39        | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 32        | 0.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 29        | 0.83%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 26        | 0.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 24        | 0.69%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 24        | 0.69%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 23        | 0.66%   |
| TP-Link UB500 Adapter                                                               | 21        | 0.6%    |
| Apple Bluetooth USB Host Controller                                                 | 19        | 0.54%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 17        | 0.49%   |
| Realtek RTL8821A Bluetooth                                                          | 17        | 0.49%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 17        | 0.49%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 17        | 0.49%   |
| Realtek RTL8723B Bluetooth                                                          | 16        | 0.46%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 16        | 0.46%   |
| Lite-On Wireless_Device                                                             | 14        | 0.4%    |
| Dell Wireless 365 Bluetooth                                                         | 13        | 0.37%   |
| Intel AX210 Bluetooth                                                               | 12        | 0.34%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.34%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 12        | 0.34%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 12        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3646      | 64.73%  |
| AMD                                          | 991       | 17.59%  |
| Nvidia                                       | 776       | 13.78%  |
| C-Media Electronics                          | 37        | 0.66%   |
| GN Netcom                                    | 20        | 0.36%   |
| Creative Labs                                | 12        | 0.21%   |
| Texas Instruments                            | 10        | 0.18%   |
| Plantronics                                  | 9         | 0.16%   |
| Generalplus Technology                       | 9         | 0.16%   |
| ASUSTek Computer                             | 9         | 0.16%   |
| Realtek Semiconductor                        | 8         | 0.14%   |
| JMTek                                        | 8         | 0.14%   |
| Logitech                                     | 7         | 0.12%   |
| Creative Technology                          | 6         | 0.11%   |
| Tenx Technology                              | 5         | 0.09%   |
| SteelSeries ApS                              | 4         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.07%   |
| Sennheiser Communications                    | 4         | 0.07%   |
| OPPO Electronics                             | 4         | 0.07%   |
| Micro Star International                     | 3         | 0.05%   |
| Lenovo                                       | 3         | 0.05%   |
| Jieli Technology                             | 3         | 0.05%   |
| Hewlett-Packard                              | 3         | 0.05%   |
| M-Audio                                      | 2         | 0.04%   |
| Kingston Technology                          | 2         | 0.04%   |
| GYROCOM C&C                                  | 2         | 0.04%   |
| Giga-Byte Technology                         | 2         | 0.04%   |
| Focusrite-Novation                           | 2         | 0.04%   |
| DCMT Technology                              | 2         | 0.04%   |
| Corsair                                      | 2         | 0.04%   |
| Cambridge Silicon Radio                      | 2         | 0.04%   |
| Apple                                        | 2         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| ZOOM                                         | 1         | 0.02%   |
| YSTEK Technology                             | 1         | 0.02%   |
| Yamaha                                       | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| VIA Technologies                             | 1         | 0.02%   |
| Vault                                        | 1         | 0.02%   |
| SZSanJing                                    | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 673       | 9.87%   |
| AMD Family 17h/19h HD Audio Controller                                     | 554       | 8.12%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 285       | 4.18%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 280       | 4.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 236       | 3.46%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 233       | 3.42%   |
| Intel Cannon Lake PCH cAVS                                                 | 212       | 3.11%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 202       | 2.96%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 195       | 2.86%   |
| Intel 8 Series HD Audio Controller                                         | 194       | 2.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 192       | 2.82%   |
| Intel Comet Lake PCH-LP cAVS                                               | 172       | 2.52%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 165       | 2.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 159       | 2.33%   |
| Intel Broadwell-U Audio Controller                                         | 144       | 2.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 143       | 2.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 140       | 2.05%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 131       | 1.92%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 121       | 1.77%   |
| AMD FCH Azalia Controller                                                  | 112       | 1.64%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 108       | 1.58%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 105       | 1.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 96        | 1.41%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 90        | 1.32%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 83        | 1.22%   |
| AMD Kabini HDMI/DP Audio                                                   | 74        | 1.09%   |
| Intel Comet Lake PCH cAVS                                                  | 73        | 1.07%   |
| Nvidia GP107GL High Definition Audio Controller                            | 70        | 1.03%   |
| AMD Starship/Matisse HD Audio Controller                                   | 66        | 0.97%   |
| AMD High Definition Audio Controller                                       | 66        | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 65        | 0.95%   |
| Intel 200 Series PCH HD Audio                                              | 65        | 0.95%   |
| Nvidia TU116 High Definition Audio Controller                              | 55        | 0.81%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 54        | 0.79%   |
| Nvidia Audio device                                                        | 48        | 0.7%    |
| Nvidia High Definition Audio Controller                                    | 45        | 0.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 43        | 0.63%   |
| Nvidia GA106 High Definition Audio Controller                              | 37        | 0.54%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 37        | 0.54%   |
| Intel CM238 HD Audio Controller                                            | 37        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 823       | 26.28%  |
| SK hynix                     | 736       | 23.5%   |
| Micron Technology            | 409       | 13.06%  |
| Kingston                     | 266       | 8.49%   |
| Crucial                      | 179       | 5.72%   |
| Unknown                      | 149       | 4.76%   |
| A-DATA Technology            | 121       | 3.86%   |
| Corsair                      | 109       | 3.48%   |
| Ramaxel Technology           | 106       | 3.38%   |
| Transcend                    | 61        | 1.95%   |
| G.Skill                      | 35        | 1.12%   |
| CSX                          | 31        | 0.99%   |
| Nanya Technology             | 23        | 0.73%   |
| Elpida                       | 21        | 0.67%   |
| Unknown                      | 12        | 0.38%   |
| Unknown (ABCD)               | 7         | 0.22%   |
| OM Nanotech                  | 6         | 0.19%   |
| Silicon Power                | 5         | 0.16%   |
| ZION                         | 3         | 0.1%    |
| Avant                        | 3         | 0.1%    |
| Unknown (0x0CDC)             | 2         | 0.06%   |
| Team                         | 2         | 0.06%   |
| Kllisre                      | 2         | 0.06%   |
| ASint Technology             | 2         | 0.06%   |
| Apacer                       | 2         | 0.06%   |
| Unknown (0xAD44594E45540000) | 1         | 0.03%   |
| Unknown (0x1007)             | 1         | 0.03%   |
| Unknown (0x0CAB)             | 1         | 0.03%   |
| Unknown (0x0080)             | 1         | 0.03%   |
| Unknown (09D5)               | 1         | 0.03%   |
| Unknown (07F7)               | 1         | 0.03%   |
| Strontium                    | 1         | 0.03%   |
| SHARETRONIC                  | 1         | 0.03%   |
| Ramos Technology             | 1         | 0.03%   |
| Qumo                         | 1         | 0.03%   |
| Qimonda                      | 1         | 0.03%   |
| Patriot Memory (PDP Systems) | 1         | 0.03%   |
| NETSOL                       | 1         | 0.03%   |
| Lexar Co Limited             | 1         | 0.03%   |
| Goldkey                      | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 71        | 2.15%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 61        | 1.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 55        | 1.67%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 43        | 1.3%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 42        | 1.27%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 41        | 1.24%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 37        | 1.12%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 37        | 1.12%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 35        | 1.06%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 34        | 1.03%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 33        | 1%      |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 32        | 0.97%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 32        | 0.97%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 32        | 0.97%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 29        | 0.88%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 28        | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 28        | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 27        | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 27        | 0.82%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s        | 26        | 0.79%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 25        | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 25        | 0.76%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 23        | 0.7%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 23        | 0.7%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 22        | 0.67%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 21        | 0.64%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 21        | 0.64%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 21        | 0.64%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                    | 17        | 0.52%   |
| Crucial RAM CB8GS2400.C8ET 8GB SODIMM DDR4 2667MT/s         | 17        | 0.52%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s      | 17        | 0.52%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 15        | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 15        | 0.45%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s        | 15        | 0.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 14        | 0.42%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 14        | 0.42%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 14        | 0.42%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 14        | 0.42%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 14        | 0.42%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s       | 14        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1619      | 62.58%  |
| DDR3    | 649       | 25.09%  |
| LPDDR4  | 93        | 3.59%   |
| SDRAM   | 63        | 2.44%   |
| DDR2    | 49        | 1.89%   |
| LPDDR3  | 31        | 1.2%    |
| DDR5    | 30        | 1.16%   |
| LPDDR5  | 24        | 0.93%   |
| Unknown | 23        | 0.89%   |
| DDR     | 6         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1901      | 74.03%  |
| DIMM         | 474       | 18.46%  |
| Row Of Chips | 185       | 7.2%    |
| Chip         | 4         | 0.16%   |
| RIMM         | 2         | 0.08%   |
| Unknown      | 2         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1326      | 46.64%  |
| 4096  | 838       | 29.48%  |
| 16384 | 345       | 12.14%  |
| 2048  | 245       | 8.62%   |
| 32768 | 47        | 1.65%   |
| 1024  | 37        | 1.3%    |
| 512   | 4         | 0.14%   |
| 1536  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 687       | 24.46%  |
| 3200    | 630       | 22.43%  |
| 1600    | 490       | 17.44%  |
| 2400    | 238       | 8.47%   |
| 1333    | 118       | 4.2%    |
| 2133    | 96        | 3.42%   |
| 3266    | 71        | 2.53%   |
| 1334    | 65        | 2.31%   |
| Unknown | 41        | 1.46%   |
| 3600    | 40        | 1.42%   |
| 2666    | 31        | 1.1%    |
| 667     | 31        | 1.1%    |
| 4267    | 28        | 1%      |
| 6400    | 26        | 0.93%   |
| 4800    | 24        | 0.85%   |
| 1067    | 23        | 0.82%   |
| 4199    | 20        | 0.71%   |
| 3000    | 18        | 0.64%   |
| 2800    | 18        | 0.64%   |
| 800     | 17        | 0.61%   |
| 1867    | 16        | 0.57%   |
| 975     | 14        | 0.5%    |
| 1866    | 8         | 0.28%   |
| 3733    | 7         | 0.25%   |
| 2048    | 5         | 0.18%   |
| 8400    | 4         | 0.14%   |
| 1800    | 4         | 0.14%   |
| 4266    | 3         | 0.11%   |
| 3400    | 3         | 0.11%   |
| 1648    | 3         | 0.11%   |
| 6000    | 2         | 0.07%   |
| 5200    | 2         | 0.07%   |
| 3866    | 2         | 0.07%   |
| 3466    | 2         | 0.07%   |
| 3066    | 2         | 0.07%   |
| 2933    | 2         | 0.07%   |
| 1066    | 2         | 0.07%   |
| 533     | 2         | 0.07%   |
| 49926   | 1         | 0.04%   |
| 25834   | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 22        | 42.31%  |
| Seiko Epson         | 12        | 23.08%  |
| Canon               | 9         | 17.31%  |
| Brother Industries  | 5         | 9.62%   |
| STMicroelectronics  | 1         | 1.92%   |
| Samsung Electronics | 1         | 1.92%   |
| Ricoh               | 1         | 1.92%   |
| Konica Minolta      | 1         | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                                      | 6         | 11.54%  |
| HP Ink Tank 310 series                                                | 4         | 7.69%   |
| Canon PIXMA MG2500 Series                                             | 3         | 5.77%   |
| Seiko Epson L380 Series                                               | 2         | 3.85%   |
| HP DeskJet 2130 series                                                | 2         | 3.85%   |
| HP DeskJet 1110 series                                                | 2         | 3.85%   |
| Canon LBP2900                                                         | 2         | 3.85%   |
| STMicroelectronics USB Printing Support                               | 1         | 1.92%   |
| Seiko Epson USB2.0 Printer                                            | 1         | 1.92%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 1.92%   |
| Seiko Epson M100 Series                                               | 1         | 1.92%   |
| Seiko Epson L6160 Series                                              | 1         | 1.92%   |
| Seiko Epson L405 Series                                               | 1         | 1.92%   |
| Seiko Epson L360 Series                                               | 1         | 1.92%   |
| Seiko Epson L3200 Series                                              | 1         | 1.92%   |
| Seiko Epson L3110 Series                                              | 1         | 1.92%   |
| Seiko Epson L132 Series                                               | 1         | 1.92%   |
| Seiko Epson ET-2710 Series                                            | 1         | 1.92%   |
| Samsung ML-1640 Series Laser Printer                                  | 1         | 1.92%   |
| Ricoh SP 112SU                                                        | 1         | 1.92%   |
| Konica Minolta 206                                                    | 1         | 1.92%   |
| HP Smart Install                                                      | 1         | 1.92%   |
| HP Printing Support                                                   | 1         | 1.92%   |
| HP LaserJet Professional P1566                                        | 1         | 1.92%   |
| HP LaserJet Pro M201dw                                                | 1         | 1.92%   |
| HP LaserJet P1102                                                     | 1         | 1.92%   |
| HP DeskJet 3630 series                                                | 1         | 1.92%   |
| HP DeskJet 2600 series                                                | 1         | 1.92%   |
| HP Deskjet 1510                                                       | 1         | 1.92%   |
| Canon PIXMA MP280                                                     | 1         | 1.92%   |
| Canon PIXMA MP190                                                     | 1         | 1.92%   |
| Canon MF4800 Series                                                   | 1         | 1.92%   |
| Canon G2000 series                                                    | 1         | 1.92%   |
| Brother Printer                                                       | 1         | 1.92%   |
| Brother HL-L2320D series                                              | 1         | 1.92%   |
| Brother DCP-T510W                                                     | 1         | 1.92%   |
| Brother DCP-T310                                                      | 1         | 1.92%   |
| Brother DCP-L2520D                                                    | 1         | 1.92%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 75%     |
| Seiko Epson     | 1         | 12.5%   |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 5         | 62.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| HP ScanJet 2200c                            | 1         | 12.5%   |
| Canon CanoScan LiDE 120                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 634       | 18.23%  |
| IMC Networks                           | 505       | 14.52%  |
| Realtek Semiconductor                  | 346       | 9.95%   |
| Microdia                               | 343       | 9.86%   |
| Quanta                                 | 244       | 7.02%   |
| Sunplus Innovation Technology          | 200       | 5.75%   |
| Bison Electronics                      | 174       | 5%      |
| Cheng Uei Precision Industry (Foxlink) | 170       | 4.89%   |
| Syntek                                 | 136       | 3.91%   |
| Suyin                                  | 126       | 3.62%   |
| Luxvisions Innotech Limited            | 83        | 2.39%   |
| Logitech                               | 67        | 1.93%   |
| Lite-On Technology                     | 65        | 1.87%   |
| Acer                                   | 56        | 1.61%   |
| Sonix Technology                       | 36        | 1.04%   |
| Alcor Micro                            | 35        | 1.01%   |
| Apple                                  | 28        | 0.81%   |
| Samsung Electronics                    | 25        | 0.72%   |
| Silicon Motion                         | 21        | 0.6%    |
| Ricoh                                  | 14        | 0.4%    |
| Lenovo                                 | 14        | 0.4%    |
| Importek                               | 13        | 0.37%   |
| Z-Star Microelectronics                | 10        | 0.29%   |
| Primax Electronics                     | 10        | 0.29%   |
| Unknown                                | 9         | 0.26%   |
| OmniVision Technologies                | 9         | 0.26%   |
| OPPO Electronics                       | 7         | 0.2%    |
| SunplusIT                              | 6         | 0.17%   |
| Microsoft                              | 6         | 0.17%   |
| GEMBIRD                                | 6         | 0.17%   |
| Arkmicro Technologies                  | 6         | 0.17%   |
| 8SSC20F27114V1SR0BK1X4S                | 6         | 0.17%   |
| Intel                                  | 5         | 0.14%   |
| Pixart Imaging                         | 4         | 0.12%   |
| MSD                                    | 4         | 0.12%   |
| MacroSilicon                           | 4         | 0.12%   |
| Hewlett-Packard                        | 4         | 0.12%   |
| Cubeternet                             | 4         | 0.12%   |
| vivo                                   | 3         | 0.09%   |
| Jieli Technology                       | 3         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 176       | 5.05%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 174       | 4.99%   |
| Realtek Integrated_Webcam_HD                                   | 142       | 4.07%   |
| IMC Networks Integrated Camera                                 | 139       | 3.99%   |
| Chicony Integrated Camera                                      | 133       | 3.82%   |
| Sunplus Integrated_Webcam_HD                                   | 96        | 2.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 87        | 2.5%    |
| Syntek Integrated Camera                                       | 78        | 2.24%   |
| Chicony HP Truevision HD camera                                | 67        | 1.92%   |
| Realtek Integrated Webcam                                      | 61        | 1.75%   |
| Chicony HP Truevision HD                                       | 58        | 1.66%   |
| Quanta HP TrueVision HD Camera                                 | 51        | 1.46%   |
| Chicony EasyCamera                                             | 49        | 1.41%   |
| Quanta HD User Facing                                          | 46        | 1.32%   |
| Suyin HP Truevision HD                                         | 43        | 1.23%   |
| Bison Integrated Camera                                        | 42        | 1.21%   |
| Logitech Webcam C270                                           | 39        | 1.12%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 38        | 1.09%   |
| Quanta HP Wide Vision HD Camera                                | 36        | 1.03%   |
| Acer Integrated Camera                                         | 35        | 1%      |
| Syntek EasyCamera                                              | 34        | 0.98%   |
| Chicony HP Wide Vision HD Camera                               | 34        | 0.98%   |
| Chicony HD WebCam                                              | 34        | 0.98%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 34        | 0.98%   |
| Chicony HD User Facing                                         | 33        | 0.95%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 32        | 0.92%   |
| Lite-On Integrated Camera                                      | 28        | 0.8%    |
| Bison EasyCamera                                               | 28        | 0.8%    |
| Sonix USB2.0 HD UVC WebCam                                     | 27        | 0.77%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 27        | 0.77%   |
| IMC Networks HP TrueVision HD Camera                           | 27        | 0.77%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 25        | 0.72%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 25        | 0.72%   |
| Microdia Integrated Webcam                                     | 24        | 0.69%   |
| Bison Lenovo EasyCamera                                        | 24        | 0.69%   |
| Suyin Integrated_Webcam_HD                                     | 23        | 0.66%   |
| Bison HD Webcam                                                | 23        | 0.66%   |
| Realtek EasyCamera                                             | 22        | 0.63%   |
| Quanta VGA WebCam                                              | 21        | 0.6%    |
| Quanta ACER HD User Facing                                     | 21        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 192       | 29.63%  |
| Synaptics                          | 152       | 23.46%  |
| Shenzhen Goodix Technology         | 135       | 20.83%  |
| Elan Microelectronics              | 96        | 14.81%  |
| LighTuning Technology              | 23        | 3.55%   |
| Realtek USB2.0 Finger Print Bridge | 18        | 2.78%   |
| AuthenTec                          | 12        | 1.85%   |
| Upek                               | 11        | 1.7%    |
| Focal-systems.Corp                 | 6         | 0.93%   |
| STMicroelectronics                 | 1         | 0.15%   |
| Futronic Technology                | 1         | 0.15%   |
| DigitalPersona                     | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 74        | 11.42%  |
| Elan ELAN:ARM-M4                                                           | 62        | 9.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 55        | 8.49%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 54        | 8.33%   |
| Elan ELAN:Fingerprint                                                      | 31        | 4.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 25        | 3.86%   |
| Synaptics WBDI                                                             | 25        | 3.86%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 3.86%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 24        | 3.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 3.55%   |
| Synaptics UWP WBDI                                                         | 20        | 3.09%   |
| Synaptics  WBDI                                                            | 19        | 2.93%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 18        | 2.78%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 18        | 2.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 15        | 2.31%   |
| Synaptics Fingerprint scanner                                              | 14        | 2.16%   |
| Validity Sensors VFS Fingerprint sensor                                    | 12        | 1.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 1.85%   |
| Validity Sensors VFS491                                                    | 11        | 1.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 1.54%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 1.39%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.08%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 0.93%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 0.93%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 0.93%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 0.93%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 6         | 0.93%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.77%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 0.77%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.77%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.62%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 0.46%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 3         | 0.46%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.31%   |
| Synaptics TouchPad                                                         | 2         | 0.31%   |
| AuthenTec AES2810                                                          | 2         | 0.31%   |
| AuthenTec AES1600                                                          | 2         | 0.31%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 69        | 65.71%  |
| Alcor Micro           | 19        | 18.1%   |
| Upek                  | 8         | 7.62%   |
| O2 Micro              | 3         | 2.86%   |
| Lenovo                | 3         | 2.86%   |
| Yubico.com            | 1         | 0.95%   |
| Gemalto (was Gemplus) | 1         | 0.95%   |
| Clay Logic            | 1         | 0.95%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 23        | 21.7%   |
| Broadcom 5880                                                                | 19        | 17.92%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 17.92%  |
| Broadcom 58200                                                               | 15        | 14.15%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 12.26%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 7.55%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.83%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.89%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.94%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.94%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.94%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 0.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3174      | 66.68%  |
| 1     | 1318      | 27.69%  |
| 2     | 217       | 4.56%   |
| 3     | 28        | 0.59%   |
| 4     | 13        | 0.27%   |
| 5     | 6         | 0.13%   |
| 9     | 2         | 0.04%   |
| 6     | 2         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 643       | 34.51%  |
| Graphics card            | 434       | 23.3%   |
| Net/wireless             | 285       | 15.3%   |
| Chipcard                 | 99        | 5.31%   |
| Multimedia controller    | 91        | 4.88%   |
| Bluetooth                | 90        | 4.83%   |
| Camera                   | 62        | 3.33%   |
| Communication controller | 61        | 3.27%   |
| Net/ethernet             | 25        | 1.34%   |
| Sound                    | 23        | 1.23%   |
| Storage                  | 13        | 0.7%    |
| Unassigned class         | 11        | 0.59%   |
| Network                  | 10        | 0.54%   |
| Modem                    | 7         | 0.38%   |
| Card reader              | 5         | 0.27%   |
| Storage/raid             | 1         | 0.05%   |
| Storage/nvme             | 1         | 0.05%   |
| Storage/ide              | 1         | 0.05%   |
| Firewire controller      | 1         | 0.05%   |

