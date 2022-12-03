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

Total: 5261

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Notebook                    | Notebook    | [7c22b96a9a](https://linux-hardware.org/?probe=7c22b96a9a) | Dec 01, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [65fa0de0a2](https://linux-hardware.org/?probe=65fa0de0a2) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [ee99c81e47](https://linux-hardware.org/?probe=ee99c81e47) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| HP            | Notebook                    | Notebook    | [afac08b852](https://linux-hardware.org/?probe=afac08b852) | Nov 30, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [c1d2a02024](https://linux-hardware.org/?probe=c1d2a02024) | Nov 30, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [fa36933936](https://linux-hardware.org/?probe=fa36933936) | Nov 29, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Dell          | Latitude 3500               | Notebook    | [de0731ac74](https://linux-hardware.org/?probe=de0731ac74) | Nov 29, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [fab21fa561](https://linux-hardware.org/?probe=fab21fa561) | Nov 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [15909202b8](https://linux-hardware.org/?probe=15909202b8) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [2aba12235d](https://linux-hardware.org/?probe=2aba12235d) | Nov 27, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [26083dd909](https://linux-hardware.org/?probe=26083dd909) | Nov 27, 2022 |
| AVITA         | NS14A6                      | Notebook    | [b9cc8fe757](https://linux-hardware.org/?probe=b9cc8fe757) | Nov 27, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [350202deed](https://linux-hardware.org/?probe=350202deed) | Nov 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [dc561bb107](https://linux-hardware.org/?probe=dc561bb107) | Nov 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [336d829333](https://linux-hardware.org/?probe=336d829333) | Nov 26, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [847b1cb39a](https://linux-hardware.org/?probe=847b1cb39a) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| Dell          | Latitude 5490               | Notebook    | [7aedc1fbd7](https://linux-hardware.org/?probe=7aedc1fbd7) | Nov 26, 2022 |
| ASUSTek       | Zenbook UP5401ZA_UP5401Z... | Convertible | [bb84c0cdc2](https://linux-hardware.org/?probe=bb84c0cdc2) | Nov 26, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00d2cc22aa](https://linux-hardware.org/?probe=00d2cc22aa) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [376fc86892](https://linux-hardware.org/?probe=376fc86892) | Nov 25, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [f46e1bc341](https://linux-hardware.org/?probe=f46e1bc341) | Nov 25, 2022 |
| HP            | 245 G3                      | Notebook    | [c155a2a926](https://linux-hardware.org/?probe=c155a2a926) | Nov 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ce5f08445d](https://linux-hardware.org/?probe=ce5f08445d) | Nov 24, 2022 |
| Dell          | Inspiron 5370               | Notebook    | [469b2c3fd4](https://linux-hardware.org/?probe=469b2c3fd4) | Nov 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d84bc82678](https://linux-hardware.org/?probe=d84bc82678) | Nov 23, 2022 |
| HP            | 15                          | Notebook    | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [1071e10a2c](https://linux-hardware.org/?probe=1071e10a2c) | Nov 23, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [0483728614](https://linux-hardware.org/?probe=0483728614) | Nov 23, 2022 |
| Lenovo        | ThinkPad T480 20L50011US    | Notebook    | [2f32726e0d](https://linux-hardware.org/?probe=2f32726e0d) | Nov 23, 2022 |
| ASUSTek       | H81M-V3                     | Desktop     | [f6be8306c7](https://linux-hardware.org/?probe=f6be8306c7) | Nov 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [2eec6b4f39](https://linux-hardware.org/?probe=2eec6b4f39) | Nov 22, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [88f4469c5d](https://linux-hardware.org/?probe=88f4469c5d) | Nov 21, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [bce41d01ae](https://linux-hardware.org/?probe=bce41d01ae) | Nov 21, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [687044a497](https://linux-hardware.org/?probe=687044a497) | Nov 21, 2022 |
| HP            | 245 G5 Notebook PC          | Notebook    | [deed1dcf4d](https://linux-hardware.org/?probe=deed1dcf4d) | Nov 21, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2da86d4e21](https://linux-hardware.org/?probe=2da86d4e21) | Nov 21, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [634f7d190d](https://linux-hardware.org/?probe=634f7d190d) | Nov 21, 2022 |
| HP            | 1998                        | Desktop     | [7290e58261](https://linux-hardware.org/?probe=7290e58261) | Nov 21, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a5af222fa3](https://linux-hardware.org/?probe=a5af222fa3) | Nov 21, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [88bbdb925b](https://linux-hardware.org/?probe=88bbdb925b) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | Notebook    | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [8b07bd39c9](https://linux-hardware.org/?probe=8b07bd39c9) | Nov 19, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [a90cea62ff](https://linux-hardware.org/?probe=a90cea62ff) | Nov 19, 2022 |
| Sony          | SVE15133CNB                 | Notebook    | [3d78ceb657](https://linux-hardware.org/?probe=3d78ceb657) | Nov 19, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [cb719dbd60](https://linux-hardware.org/?probe=cb719dbd60) | Nov 19, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [ea2f588ed8](https://linux-hardware.org/?probe=ea2f588ed8) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L6S3L400    | Notebook    | [ae98e93989](https://linux-hardware.org/?probe=ae98e93989) | Nov 18, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [785ae6891c](https://linux-hardware.org/?probe=785ae6891c) | Nov 17, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [190c6d9cc7](https://linux-hardware.org/?probe=190c6d9cc7) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [94983688d2](https://linux-hardware.org/?probe=94983688d2) | Nov 16, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [6b14e6a41b](https://linux-hardware.org/?probe=6b14e6a41b) | Nov 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [119f9da4af](https://linux-hardware.org/?probe=119f9da4af) | Nov 16, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [ddc155c281](https://linux-hardware.org/?probe=ddc155c281) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [dea1636b05](https://linux-hardware.org/?probe=dea1636b05) | Nov 15, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [9ed613b632](https://linux-hardware.org/?probe=9ed613b632) | Nov 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [35cb137655](https://linux-hardware.org/?probe=35cb137655) | Nov 15, 2022 |
| Dell          | Precision 7510              | Notebook    | [111903e578](https://linux-hardware.org/?probe=111903e578) | Nov 14, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0e09796a40](https://linux-hardware.org/?probe=0e09796a40) | Nov 14, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [9708710429](https://linux-hardware.org/?probe=9708710429) | Nov 14, 2022 |
| Dell          | Latitude 7480               | Notebook    | [2e485b361c](https://linux-hardware.org/?probe=2e485b361c) | Nov 14, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [e8acccbe3c](https://linux-hardware.org/?probe=e8acccbe3c) | Nov 13, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [5279c2e222](https://linux-hardware.org/?probe=5279c2e222) | Nov 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [e19fef63c9](https://linux-hardware.org/?probe=e19fef63c9) | Nov 12, 2022 |
| Intel         | H61                         | Desktop     | [8b718d964b](https://linux-hardware.org/?probe=8b718d964b) | Nov 12, 2022 |
| Dell          | Inspiron 7373               | Convertible | [fddce72af0](https://linux-hardware.org/?probe=fddce72af0) | Nov 12, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [2cfd92452e](https://linux-hardware.org/?probe=2cfd92452e) | Nov 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c73b422075](https://linux-hardware.org/?probe=c73b422075) | Nov 12, 2022 |
| HP            | Notebook                    | Notebook    | [2419e7d149](https://linux-hardware.org/?probe=2419e7d149) | Nov 12, 2022 |
| HP            | Notebook                    | Notebook    | [97c6c3c412](https://linux-hardware.org/?probe=97c6c3c412) | Nov 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [adf09c8455](https://linux-hardware.org/?probe=adf09c8455) | Nov 11, 2022 |
| Lenovo        | V310-14ISK 80SX             | Notebook    | [0e0de3ee86](https://linux-hardware.org/?probe=0e0de3ee86) | Nov 11, 2022 |
| Dell          | Latitude E6420              | Notebook    | [70ebe12e06](https://linux-hardware.org/?probe=70ebe12e06) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [671714bc5a](https://linux-hardware.org/?probe=671714bc5a) | Nov 11, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [d020fa04fe](https://linux-hardware.org/?probe=d020fa04fe) | Nov 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3bcdc36fff](https://linux-hardware.org/?probe=3bcdc36fff) | Nov 11, 2022 |
| Lenovo        | 314F NO DPK                 | Desktop     | [a069831b82](https://linux-hardware.org/?probe=a069831b82) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [4ff5cb368c](https://linux-hardware.org/?probe=4ff5cb368c) | Nov 10, 2022 |
| HP            | 2000                        | Notebook    | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Dell          | Latitude E6420              | Notebook    | [4be923e459](https://linux-hardware.org/?probe=4be923e459) | Nov 10, 2022 |
| HP            | 8717                        | Desktop     | [57479419c9](https://linux-hardware.org/?probe=57479419c9) | Nov 10, 2022 |
| Samsung       | 950QED                      | Convertible | [c68fd01b4c](https://linux-hardware.org/?probe=c68fd01b4c) | Nov 10, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [4366631db8](https://linux-hardware.org/?probe=4366631db8) | Nov 09, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [0b1b8bf15d](https://linux-hardware.org/?probe=0b1b8bf15d) | Nov 09, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [bc5466e5ac](https://linux-hardware.org/?probe=bc5466e5ac) | Nov 08, 2022 |
| HP            | Pavilion Laptop 14-dv2xx... | Notebook    | [bbc7236402](https://linux-hardware.org/?probe=bbc7236402) | Nov 08, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [cb9f2f3d87](https://linux-hardware.org/?probe=cb9f2f3d87) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [43db111de5](https://linux-hardware.org/?probe=43db111de5) | Nov 07, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0459e9f47e](https://linux-hardware.org/?probe=0459e9f47e) | Nov 06, 2022 |
| Acer          | H81H3-M4                    | Desktop     | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [006e91ea03](https://linux-hardware.org/?probe=006e91ea03) | Nov 06, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [43c1e8b8a8](https://linux-hardware.org/?probe=43c1e8b8a8) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | Notebook    | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [390f51010e](https://linux-hardware.org/?probe=390f51010e) | Nov 06, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | 245 G5 Notebook PC          | Notebook    | [4d52b15940](https://linux-hardware.org/?probe=4d52b15940) | Nov 06, 2022 |
| HP            | Notebook                    | Notebook    | [49e26e62f7](https://linux-hardware.org/?probe=49e26e62f7) | Nov 05, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [625b40327b](https://linux-hardware.org/?probe=625b40327b) | Nov 05, 2022 |
| Dell          | G3 3500                     | Notebook    | [36918f305b](https://linux-hardware.org/?probe=36918f305b) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8f3cf6499e](https://linux-hardware.org/?probe=8f3cf6499e) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [2eb5db395b](https://linux-hardware.org/?probe=2eb5db395b) | Nov 05, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [2c605465bb](https://linux-hardware.org/?probe=2c605465bb) | Nov 04, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [9e6efb3e67](https://linux-hardware.org/?probe=9e6efb3e67) | Nov 04, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [ecea714e26](https://linux-hardware.org/?probe=ecea714e26) | Nov 04, 2022 |
| HP            | 89B5 A                      | Desktop     | [1b04604c98](https://linux-hardware.org/?probe=1b04604c98) | Nov 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f790aefcad](https://linux-hardware.org/?probe=f790aefcad) | Nov 03, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [920c4567d3](https://linux-hardware.org/?probe=920c4567d3) | Nov 03, 2022 |
| HP            | 8717                        | Desktop     | [00cbc9cd2a](https://linux-hardware.org/?probe=00cbc9cd2a) | Nov 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [40a3de202d](https://linux-hardware.org/?probe=40a3de202d) | Nov 03, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [57df10cb95](https://linux-hardware.org/?probe=57df10cb95) | Nov 03, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [5d9743e91d](https://linux-hardware.org/?probe=5d9743e91d) | Nov 02, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [83a1fc191a](https://linux-hardware.org/?probe=83a1fc191a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [95ddb63cb1](https://linux-hardware.org/?probe=95ddb63cb1) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [aa6c06f2bb](https://linux-hardware.org/?probe=aa6c06f2bb) | Nov 02, 2022 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [584db1dcb2](https://linux-hardware.org/?probe=584db1dcb2) | Nov 02, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [115025ee59](https://linux-hardware.org/?probe=115025ee59) | Nov 01, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [74af46599e](https://linux-hardware.org/?probe=74af46599e) | Nov 01, 2022 |
| Acer          | H410H6-M17 P21-A1           | Desktop     | [9333be5120](https://linux-hardware.org/?probe=9333be5120) | Nov 01, 2022 |
| Dell          | Latitude 3420               | Notebook    | [9c2b9ab298](https://linux-hardware.org/?probe=9c2b9ab298) | Nov 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6323d7e1b3](https://linux-hardware.org/?probe=6323d7e1b3) | Nov 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [24203a87c9](https://linux-hardware.org/?probe=24203a87c9) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| Acer          | Unknown                     | Notebook    | [284f534a6a](https://linux-hardware.org/?probe=284f534a6a) | Oct 31, 2022 |
| Acer          | Unknown                     | Notebook    | [27b5267fa3](https://linux-hardware.org/?probe=27b5267fa3) | Oct 31, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [dcccad24af](https://linux-hardware.org/?probe=dcccad24af) | Oct 31, 2022 |
| Lenovo        | Legion Y7000 2019 1050 8... | Notebook    | [3821dabcb9](https://linux-hardware.org/?probe=3821dabcb9) | Oct 31, 2022 |
| HP            | 2000                        | Notebook    | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [26a8adcee2](https://linux-hardware.org/?probe=26a8adcee2) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [dea1724953](https://linux-hardware.org/?probe=dea1724953) | Oct 31, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [02d23cb1b9](https://linux-hardware.org/?probe=02d23cb1b9) | Oct 30, 2022 |
| Sony          | VPCEA45FG                   | Notebook    | [3448172ca3](https://linux-hardware.org/?probe=3448172ca3) | Oct 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [1b29e58b30](https://linux-hardware.org/?probe=1b29e58b30) | Oct 29, 2022 |
| Acer          | Extensa 215-54              | Notebook    | [0fe46d7655](https://linux-hardware.org/?probe=0fe46d7655) | Oct 29, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [74a79dbdb6](https://linux-hardware.org/?probe=74a79dbdb6) | Oct 29, 2022 |
| ASUSTek       | PRIME B365M-C               | Desktop     | [ccf9650f9a](https://linux-hardware.org/?probe=ccf9650f9a) | Oct 29, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [f7155fd671](https://linux-hardware.org/?probe=f7155fd671) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [c6031ce122](https://linux-hardware.org/?probe=c6031ce122) | Oct 28, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [b31400d1d1](https://linux-hardware.org/?probe=b31400d1d1) | Oct 27, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [aa2345213b](https://linux-hardware.org/?probe=aa2345213b) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [9b90ea1d4d](https://linux-hardware.org/?probe=9b90ea1d4d) | Oct 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [91097add4c](https://linux-hardware.org/?probe=91097add4c) | Oct 26, 2022 |
| Dell          | Latitude E7470              | Notebook    | [a9274c9070](https://linux-hardware.org/?probe=a9274c9070) | Oct 26, 2022 |
| Intel         | D945GCNL AAD97184-102       | Desktop     | [a057daae25](https://linux-hardware.org/?probe=a057daae25) | Oct 26, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [91437ee9a7](https://linux-hardware.org/?probe=91437ee9a7) | Oct 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [09d3217ce4](https://linux-hardware.org/?probe=09d3217ce4) | Oct 25, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [75c0c3e97b](https://linux-hardware.org/?probe=75c0c3e97b) | Oct 24, 2022 |
| HP            | Laptop 15s-gy0xxx           | Notebook    | [d1219c1387](https://linux-hardware.org/?probe=d1219c1387) | Oct 23, 2022 |
| Dell          | Vostro 3491                 | Notebook    | [8809be3a93](https://linux-hardware.org/?probe=8809be3a93) | Oct 23, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [0c7ba9c00c](https://linux-hardware.org/?probe=0c7ba9c00c) | Oct 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9a104497e3](https://linux-hardware.org/?probe=9a104497e3) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [bea9c6b47b](https://linux-hardware.org/?probe=bea9c6b47b) | Oct 23, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [8a9c9435e3](https://linux-hardware.org/?probe=8a9c9435e3) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [d37b700ffb](https://linux-hardware.org/?probe=d37b700ffb) | Oct 22, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KY00     | Notebook    | [657b1ee865](https://linux-hardware.org/?probe=657b1ee865) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [d2fa2b9b63](https://linux-hardware.org/?probe=d2fa2b9b63) | Oct 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f07691d6b1](https://linux-hardware.org/?probe=f07691d6b1) | Oct 20, 2022 |
| Acer          | Aspire E5-553G              | Notebook    | [8e75bbadf5](https://linux-hardware.org/?probe=8e75bbadf5) | Oct 20, 2022 |
| HPE           | ML10Gen9                    | Server      | [bbd0be963a](https://linux-hardware.org/?probe=bbd0be963a) | Oct 20, 2022 |
| HP            | 2B1E                        | Desktop     | [1a79dbe66a](https://linux-hardware.org/?probe=1a79dbe66a) | Oct 20, 2022 |
| Dell          | 0K83V0 A00                  | Desktop     | [dde4cfd592](https://linux-hardware.org/?probe=dde4cfd592) | Oct 20, 2022 |
| Lenovo        | ThinkPad T450s 20BWA0DW0... | Notebook    | [117e1e8e03](https://linux-hardware.org/?probe=117e1e8e03) | Oct 20, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2f69a96661](https://linux-hardware.org/?probe=2f69a96661) | Oct 18, 2022 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | Notebook    | [96a36651bf](https://linux-hardware.org/?probe=96a36651bf) | Oct 18, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [36c0e4dd87](https://linux-hardware.org/?probe=36c0e4dd87) | Oct 18, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [e38bd0cb56](https://linux-hardware.org/?probe=e38bd0cb56) | Oct 17, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [cb651a5071](https://linux-hardware.org/?probe=cb651a5071) | Oct 17, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [ca202dddd6](https://linux-hardware.org/?probe=ca202dddd6) | Oct 17, 2022 |
| HP            | InsydeH2O EFI BIOS          | Notebook    | [0c9c2f85b4](https://linux-hardware.org/?probe=0c9c2f85b4) | Oct 17, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [5d3a1ab999](https://linux-hardware.org/?probe=5d3a1ab999) | Oct 17, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [f7b9f3cab2](https://linux-hardware.org/?probe=f7b9f3cab2) | Oct 17, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [ff59edf4e0](https://linux-hardware.org/?probe=ff59edf4e0) | Oct 16, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a45675d222](https://linux-hardware.org/?probe=a45675d222) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [82ab4c516a](https://linux-hardware.org/?probe=82ab4c516a) | Oct 16, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [732979f5a2](https://linux-hardware.org/?probe=732979f5a2) | Oct 16, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [bc42f70bc3](https://linux-hardware.org/?probe=bc42f70bc3) | Oct 16, 2022 |
| Timi          | Mi NoteBook Pro             | Notebook    | [dbdd6179c7](https://linux-hardware.org/?probe=dbdd6179c7) | Oct 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [411a334a74](https://linux-hardware.org/?probe=411a334a74) | Oct 16, 2022 |
| Acer          | H110D4-M1                   | Desktop     | [d4972bc5f9](https://linux-hardware.org/?probe=d4972bc5f9) | Oct 15, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [2b00bd7a92](https://linux-hardware.org/?probe=2b00bd7a92) | Oct 15, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [06cda048c3](https://linux-hardware.org/?probe=06cda048c3) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [2ba7e8c424](https://linux-hardware.org/?probe=2ba7e8c424) | Oct 14, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [5e4c8b36d2](https://linux-hardware.org/?probe=5e4c8b36d2) | Oct 14, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [7ca53492d5](https://linux-hardware.org/?probe=7ca53492d5) | Oct 14, 2022 |
| Lenovo        | 3740 NOK                    | Desktop     | [fbda7a369f](https://linux-hardware.org/?probe=fbda7a369f) | Oct 14, 2022 |
| Dell          | 0VG93V A00                  | Desktop     | [e0c7462fba](https://linux-hardware.org/?probe=e0c7462fba) | Oct 14, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [25556b5183](https://linux-hardware.org/?probe=25556b5183) | Oct 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f4d190e864](https://linux-hardware.org/?probe=f4d190e864) | Oct 13, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [5985f3564a](https://linux-hardware.org/?probe=5985f3564a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [d71c1d033a](https://linux-hardware.org/?probe=d71c1d033a) | Oct 13, 2022 |
| MSI           | Pulse GL66 11UGK            | Notebook    | [07783bd6a7](https://linux-hardware.org/?probe=07783bd6a7) | Oct 13, 2022 |
| Dell          | Vostro 3446                 | Notebook    | [da79693286](https://linux-hardware.org/?probe=da79693286) | Oct 13, 2022 |
| HP            | Laptop 14s-ef1xxx           | Notebook    | [4a38e7efc3](https://linux-hardware.org/?probe=4a38e7efc3) | Oct 13, 2022 |
| Dell          | G3 3500                     | Notebook    | [831b4e147e](https://linux-hardware.org/?probe=831b4e147e) | Oct 12, 2022 |
| AVITA         | NS14A6                      | Notebook    | [0ed9ac0a2b](https://linux-hardware.org/?probe=0ed9ac0a2b) | Oct 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS2K13... | Notebook    | [36abc6f39f](https://linux-hardware.org/?probe=36abc6f39f) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [40adf0a5d8](https://linux-hardware.org/?probe=40adf0a5d8) | Oct 11, 2022 |
| AVITA         | NS14A6                      | Notebook    | [27412eff74](https://linux-hardware.org/?probe=27412eff74) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [0800772df3](https://linux-hardware.org/?probe=0800772df3) | Oct 11, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3e7ef86329](https://linux-hardware.org/?probe=3e7ef86329) | Oct 09, 2022 |
| Sony          | VPCEB46FG                   | Notebook    | [71e2273974](https://linux-hardware.org/?probe=71e2273974) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c0c2e0ca69](https://linux-hardware.org/?probe=c0c2e0ca69) | Oct 08, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | Notebook    | [615578d390](https://linux-hardware.org/?probe=615578d390) | Oct 08, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [f7d3139c23](https://linux-hardware.org/?probe=f7d3139c23) | Oct 08, 2022 |
| HP            | Pavilion dv6                | Notebook    | [0c2329c8d6](https://linux-hardware.org/?probe=0c2329c8d6) | Oct 07, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [6009358723](https://linux-hardware.org/?probe=6009358723) | Oct 07, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [c37715196b](https://linux-hardware.org/?probe=c37715196b) | Oct 07, 2022 |
| Dell          | Vostro 3578                 | Notebook    | [4fa0e607b7](https://linux-hardware.org/?probe=4fa0e607b7) | Oct 07, 2022 |
| HP            | Laptop 14s-dr1xxx           | Notebook    | [00d04b6a56](https://linux-hardware.org/?probe=00d04b6a56) | Oct 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [a431b20f04](https://linux-hardware.org/?probe=a431b20f04) | Oct 07, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [6a9f611fd5](https://linux-hardware.org/?probe=6a9f611fd5) | Oct 07, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [83a49e76b9](https://linux-hardware.org/?probe=83a49e76b9) | Oct 06, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [20ea012e04](https://linux-hardware.org/?probe=20ea012e04) | Oct 06, 2022 |
| HP            | 15                          | Notebook    | [9f0981ed52](https://linux-hardware.org/?probe=9f0981ed52) | Oct 06, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [4fe1810c2c](https://linux-hardware.org/?probe=4fe1810c2c) | Oct 06, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [f6fc1950ac](https://linux-hardware.org/?probe=f6fc1950ac) | Oct 05, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [cb204abf9b](https://linux-hardware.org/?probe=cb204abf9b) | Oct 04, 2022 |
| Lenovo        | ThinkPad T490 20RYS07R00    | Notebook    | [d6be1b9cf9](https://linux-hardware.org/?probe=d6be1b9cf9) | Oct 04, 2022 |
| Dell          | Latitude E7440              | Notebook    | [8dda778da4](https://linux-hardware.org/?probe=8dda778da4) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [62b67bffae](https://linux-hardware.org/?probe=62b67bffae) | Oct 04, 2022 |
| HP            | ProBook 4540s               | Notebook    | [ef3e02b39c](https://linux-hardware.org/?probe=ef3e02b39c) | Oct 03, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [5d6a3f11e7](https://linux-hardware.org/?probe=5d6a3f11e7) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7d1f20cf17](https://linux-hardware.org/?probe=7d1f20cf17) | Oct 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [dfd00dd2d1](https://linux-hardware.org/?probe=dfd00dd2d1) | Oct 03, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [5a77d6df0b](https://linux-hardware.org/?probe=5a77d6df0b) | Oct 02, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [9e5ab25f54](https://linux-hardware.org/?probe=9e5ab25f54) | Oct 02, 2022 |
| MICROMAX      | Canvas Lapbook L1161        | Notebook    | [9efe9e89d6](https://linux-hardware.org/?probe=9efe9e89d6) | Oct 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [88c05ba074](https://linux-hardware.org/?probe=88c05ba074) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [f05f33fa9b](https://linux-hardware.org/?probe=f05f33fa9b) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [82e89b9263](https://linux-hardware.org/?probe=82e89b9263) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [e64a9cf0e2](https://linux-hardware.org/?probe=e64a9cf0e2) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | Notebook    | [1a210b9eb5](https://linux-hardware.org/?probe=1a210b9eb5) | Oct 01, 2022 |
| Lenovo        | ThinkPad L450 20DSS00M01    | Notebook    | [e52e98a7e7](https://linux-hardware.org/?probe=e52e98a7e7) | Oct 01, 2022 |
| Dell          | G3 3500                     | Notebook    | [245ebaabe5](https://linux-hardware.org/?probe=245ebaabe5) | Oct 01, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [c4688badf5](https://linux-hardware.org/?probe=c4688badf5) | Oct 01, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [ee185c669a](https://linux-hardware.org/?probe=ee185c669a) | Oct 01, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [af9b794734](https://linux-hardware.org/?probe=af9b794734) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [68f7384e7a](https://linux-hardware.org/?probe=68f7384e7a) | Sep 30, 2022 |
| Google        | Relm                        | Notebook    | [e440e5c1cc](https://linux-hardware.org/?probe=e440e5c1cc) | Sep 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [a686f595ee](https://linux-hardware.org/?probe=a686f595ee) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [46cba6613f](https://linux-hardware.org/?probe=46cba6613f) | Sep 28, 2022 |
| Dell          | Latitude 3410               | Notebook    | [82fe1556b6](https://linux-hardware.org/?probe=82fe1556b6) | Sep 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [84187f87ed](https://linux-hardware.org/?probe=84187f87ed) | Sep 28, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [265d059992](https://linux-hardware.org/?probe=265d059992) | Sep 27, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3aa314d706](https://linux-hardware.org/?probe=3aa314d706) | Sep 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [9f37c7c4fa](https://linux-hardware.org/?probe=9f37c7c4fa) | Sep 25, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [97c49cffe7](https://linux-hardware.org/?probe=97c49cffe7) | Sep 25, 2022 |
| Acer          | Aspire A515-57G             | Notebook    | [10813c8cb5](https://linux-hardware.org/?probe=10813c8cb5) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0d790a94fa](https://linux-hardware.org/?probe=0d790a94fa) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9c7306d91e](https://linux-hardware.org/?probe=9c7306d91e) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0546e47f90](https://linux-hardware.org/?probe=0546e47f90) | Sep 25, 2022 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [5cd2d8db8c](https://linux-hardware.org/?probe=5cd2d8db8c) | Sep 24, 2022 |
| Lenovo        | ThinkPad E470 20H1004UIG    | Notebook    | [310337a455](https://linux-hardware.org/?probe=310337a455) | Sep 24, 2022 |
| Dell          | Precision 7510              | Notebook    | [11c98b608a](https://linux-hardware.org/?probe=11c98b608a) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [b77f4e7973](https://linux-hardware.org/?probe=b77f4e7973) | Sep 24, 2022 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [45f42656c3](https://linux-hardware.org/?probe=45f42656c3) | Sep 24, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [626c79c116](https://linux-hardware.org/?probe=626c79c116) | Sep 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [214a55ad3e](https://linux-hardware.org/?probe=214a55ad3e) | Sep 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [72caf18b5f](https://linux-hardware.org/?probe=72caf18b5f) | Sep 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [2bb811e308](https://linux-hardware.org/?probe=2bb811e308) | Sep 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5f1b4b1679](https://linux-hardware.org/?probe=5f1b4b1679) | Sep 23, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [71766e04c0](https://linux-hardware.org/?probe=71766e04c0) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ba0d37d696](https://linux-hardware.org/?probe=ba0d37d696) | Sep 23, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [872eafe5f7](https://linux-hardware.org/?probe=872eafe5f7) | Sep 23, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [68338b3080](https://linux-hardware.org/?probe=68338b3080) | Sep 23, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [61f6c99c88](https://linux-hardware.org/?probe=61f6c99c88) | Sep 22, 2022 |
| HP            | 1998                        | Desktop     | [f8399e0d3a](https://linux-hardware.org/?probe=f8399e0d3a) | Sep 22, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3fd067abd9](https://linux-hardware.org/?probe=3fd067abd9) | Sep 21, 2022 |
| Dell          | Latitude 3490               | Notebook    | [de749eeeb8](https://linux-hardware.org/?probe=de749eeeb8) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [c0cc0dc101](https://linux-hardware.org/?probe=c0cc0dc101) | Sep 21, 2022 |
| Acer          | Nitro AN715-51              | Notebook    | [36fb85e6cb](https://linux-hardware.org/?probe=36fb85e6cb) | Sep 21, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [cbbf373937](https://linux-hardware.org/?probe=cbbf373937) | Sep 21, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [1ec0fcefa2](https://linux-hardware.org/?probe=1ec0fcefa2) | Sep 21, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [5175ba7e7c](https://linux-hardware.org/?probe=5175ba7e7c) | Sep 20, 2022 |
| MSI           | H410M-A PRO                 | Desktop     | [76c03610be](https://linux-hardware.org/?probe=76c03610be) | Sep 20, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [43c2f57807](https://linux-hardware.org/?probe=43c2f57807) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [db46d34737](https://linux-hardware.org/?probe=db46d34737) | Sep 19, 2022 |
| ASUSTek       | ROG Flow X16 GV601RE_GV6... | Convertible | [ad99d47a5e](https://linux-hardware.org/?probe=ad99d47a5e) | Sep 19, 2022 |
| Acer          | A75F2-M2 P21-A1             | Desktop     | [2d00ba463b](https://linux-hardware.org/?probe=2d00ba463b) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | Desktop     | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECC... | Notebook    | [e09b077e89](https://linux-hardware.org/?probe=e09b077e89) | Sep 18, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3b06edf9e6](https://linux-hardware.org/?probe=3b06edf9e6) | Sep 18, 2022 |
| MiTAC         | Cedar Trail                 | Desktop     | [75dc595c8f](https://linux-hardware.org/?probe=75dc595c8f) | Sep 17, 2022 |
| MiTAC         | Cedar Trail                 | Desktop     | [c5bd90dad6](https://linux-hardware.org/?probe=c5bd90dad6) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [abca74f17e](https://linux-hardware.org/?probe=abca74f17e) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [a29728a871](https://linux-hardware.org/?probe=a29728a871) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [2bc992ab7e](https://linux-hardware.org/?probe=2bc992ab7e) | Sep 15, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [8dfb715f1e](https://linux-hardware.org/?probe=8dfb715f1e) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c70951aae5](https://linux-hardware.org/?probe=c70951aae5) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [4b19ce2aab](https://linux-hardware.org/?probe=4b19ce2aab) | Sep 15, 2022 |
| HP            | Laptop 14s-dr2xxx           | Notebook    | [39163aba8a](https://linux-hardware.org/?probe=39163aba8a) | Sep 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [578cb93789](https://linux-hardware.org/?probe=578cb93789) | Sep 14, 2022 |
| Dell          | Vostro 14-3468              | Notebook    | [fbe4062b6e](https://linux-hardware.org/?probe=fbe4062b6e) | Sep 14, 2022 |
| HP            | 339A                        | Desktop     | [78e4f67b19](https://linux-hardware.org/?probe=78e4f67b19) | Sep 14, 2022 |
| HP            | 15                          | Notebook    | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [23c756841a](https://linux-hardware.org/?probe=23c756841a) | Sep 14, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [9a3cc70094](https://linux-hardware.org/?probe=9a3cc70094) | Sep 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [423008d102](https://linux-hardware.org/?probe=423008d102) | Sep 13, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [3e5c80e004](https://linux-hardware.org/?probe=3e5c80e004) | Sep 13, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1b8d9a04ae](https://linux-hardware.org/?probe=1b8d9a04ae) | Sep 13, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [644ad9d55f](https://linux-hardware.org/?probe=644ad9d55f) | Sep 12, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d5a0bdc1a9](https://linux-hardware.org/?probe=d5a0bdc1a9) | Sep 12, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [9b10176111](https://linux-hardware.org/?probe=9b10176111) | Sep 12, 2022 |
| Dell          | Precision 5560              | Notebook    | [3120c2b781](https://linux-hardware.org/?probe=3120c2b781) | Sep 12, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [3f9a1f3db0](https://linux-hardware.org/?probe=3f9a1f3db0) | Sep 11, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [49fe1c56a3](https://linux-hardware.org/?probe=49fe1c56a3) | Sep 11, 2022 |
| Samsung       | 750XED                      | Notebook    | [ea68f0910d](https://linux-hardware.org/?probe=ea68f0910d) | Sep 10, 2022 |
| Samsung       | 750XED                      | Notebook    | [475088329e](https://linux-hardware.org/?probe=475088329e) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [5a7c8dfacf](https://linux-hardware.org/?probe=5a7c8dfacf) | Sep 10, 2022 |
| Dell          | Precision 5560              | Notebook    | [f70da50728](https://linux-hardware.org/?probe=f70da50728) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f752846656](https://linux-hardware.org/?probe=f752846656) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3397f75941](https://linux-hardware.org/?probe=3397f75941) | Sep 09, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [5af4c5d3e1](https://linux-hardware.org/?probe=5af4c5d3e1) | Sep 09, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [871de5472c](https://linux-hardware.org/?probe=871de5472c) | Sep 08, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [fad1689295](https://linux-hardware.org/?probe=fad1689295) | Sep 08, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d13ff70895](https://linux-hardware.org/?probe=d13ff70895) | Sep 08, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [1441e1783d](https://linux-hardware.org/?probe=1441e1783d) | Sep 06, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [c3eb52f6ab](https://linux-hardware.org/?probe=c3eb52f6ab) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [1fd4585410](https://linux-hardware.org/?probe=1fd4585410) | Sep 06, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| Dell          | Inspiron 3576               | Notebook    | [8f5998a9e4](https://linux-hardware.org/?probe=8f5998a9e4) | Sep 04, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1c24950db2](https://linux-hardware.org/?probe=1c24950db2) | Sep 04, 2022 |
| Dell          | Vostro 3480                 | Notebook    | [65c846d249](https://linux-hardware.org/?probe=65c846d249) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [2199481d0a](https://linux-hardware.org/?probe=2199481d0a) | Sep 03, 2022 |
| Dell          | Inspiron 5577               | Notebook    | [b06eacf424](https://linux-hardware.org/?probe=b06eacf424) | Sep 02, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [319d526423](https://linux-hardware.org/?probe=319d526423) | Sep 02, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [5b1f25ca62](https://linux-hardware.org/?probe=5b1f25ca62) | Sep 01, 2022 |
| Gigabyte      | H81M-WW                     | Desktop     | [2a56f256a3](https://linux-hardware.org/?probe=2a56f256a3) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [c9841acd77](https://linux-hardware.org/?probe=c9841acd77) | Sep 01, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [e1b27f8003](https://linux-hardware.org/?probe=e1b27f8003) | Aug 31, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [6f3bb6200f](https://linux-hardware.org/?probe=6f3bb6200f) | Aug 31, 2022 |
| HP            | Notebook                    | Notebook    | [2ca7fbbfa9](https://linux-hardware.org/?probe=2ca7fbbfa9) | Aug 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [30457b898c](https://linux-hardware.org/?probe=30457b898c) | Aug 30, 2022 |
| ASUSTek       | ZenBook UX334FAC_UX333FA... | Notebook    | [ae84021e13](https://linux-hardware.org/?probe=ae84021e13) | Aug 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [777f18537c](https://linux-hardware.org/?probe=777f18537c) | Aug 30, 2022 |
| Dell          | Latitude 3440               | Notebook    | [3e3f5ac9ab](https://linux-hardware.org/?probe=3e3f5ac9ab) | Aug 29, 2022 |
| HP            | Notebook                    | Notebook    | [e00cfcb387](https://linux-hardware.org/?probe=e00cfcb387) | Aug 29, 2022 |
| WIPRO         | G31T-M                      | Desktop     | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [1a76248bf8](https://linux-hardware.org/?probe=1a76248bf8) | Aug 28, 2022 |
| Dell          | OptiPlex 3020M              | Desktop     | [84f424cfb7](https://linux-hardware.org/?probe=84f424cfb7) | Aug 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [608a16dc64](https://linux-hardware.org/?probe=608a16dc64) | Aug 27, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1c87349faa](https://linux-hardware.org/?probe=1c87349faa) | Aug 27, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [8ccf243309](https://linux-hardware.org/?probe=8ccf243309) | Aug 27, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [24164369fd](https://linux-hardware.org/?probe=24164369fd) | Aug 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | Notebook    | [cf1b2ff13c](https://linux-hardware.org/?probe=cf1b2ff13c) | Aug 27, 2022 |
| Lenovo        | ThinkPad X260 20F5A050IG    | Notebook    | [33b5154a7a](https://linux-hardware.org/?probe=33b5154a7a) | Aug 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [783495e971](https://linux-hardware.org/?probe=783495e971) | Aug 25, 2022 |
| Lenovo        | ThinkPad L490 20Q5S0LF00    | Notebook    | [3c1287dfd2](https://linux-hardware.org/?probe=3c1287dfd2) | Aug 25, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [f4862a3793](https://linux-hardware.org/?probe=f4862a3793) | Aug 25, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | Notebook    | [5237518074](https://linux-hardware.org/?probe=5237518074) | Aug 25, 2022 |
| HP            | 15                          | Notebook    | [832c6247b2](https://linux-hardware.org/?probe=832c6247b2) | Aug 25, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [d988e1aeb9](https://linux-hardware.org/?probe=d988e1aeb9) | Aug 25, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | Notebook    | [a0c40a81ec](https://linux-hardware.org/?probe=a0c40a81ec) | Aug 24, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [0b1e1d125d](https://linux-hardware.org/?probe=0b1e1d125d) | Aug 23, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cc66ac722b](https://linux-hardware.org/?probe=cc66ac722b) | Aug 23, 2022 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [b177563e19](https://linux-hardware.org/?probe=b177563e19) | Aug 23, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [749e6c3622](https://linux-hardware.org/?probe=749e6c3622) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [62dbb0625f](https://linux-hardware.org/?probe=62dbb0625f) | Aug 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [e5442dd2d4](https://linux-hardware.org/?probe=e5442dd2d4) | Aug 23, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [97772a7cb6](https://linux-hardware.org/?probe=97772a7cb6) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Intel         | H61                         | Desktop     | [f2a42b45ca](https://linux-hardware.org/?probe=f2a42b45ca) | Aug 22, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [b41e95cd1b](https://linux-hardware.org/?probe=b41e95cd1b) | Aug 22, 2022 |
| Acer          | TravelMate P215-52G         | Notebook    | [1d36fcbc9f](https://linux-hardware.org/?probe=1d36fcbc9f) | Aug 21, 2022 |
| HP            | Notebook                    | Notebook    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| Dell          | G3 3500                     | Notebook    | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| eMachines     | D725                        | Notebook    | [34394fab35](https://linux-hardware.org/?probe=34394fab35) | Aug 21, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [9a8166de9b](https://linux-hardware.org/?probe=9a8166de9b) | Aug 20, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [32e59cda1c](https://linux-hardware.org/?probe=32e59cda1c) | Aug 20, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [3f6370f978](https://linux-hardware.org/?probe=3f6370f978) | Aug 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ac28d2918e](https://linux-hardware.org/?probe=ac28d2918e) | Aug 20, 2022 |
| OEM           | Intel H81                   | Desktop     | [5e354c60d1](https://linux-hardware.org/?probe=5e354c60d1) | Aug 20, 2022 |
| HP            | 81C5 MVB                    | Desktop     | [86a0520dc6](https://linux-hardware.org/?probe=86a0520dc6) | Aug 20, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [93c259f492](https://linux-hardware.org/?probe=93c259f492) | Aug 20, 2022 |
| HP            | 15                          | Notebook    | [4d736aca15](https://linux-hardware.org/?probe=4d736aca15) | Aug 20, 2022 |
| ASUSTek       | PRIME B365M-C               | Desktop     | [8ae386a7a0](https://linux-hardware.org/?probe=8ae386a7a0) | Aug 20, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [df6dff3fa3](https://linux-hardware.org/?probe=df6dff3fa3) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b97f13141f](https://linux-hardware.org/?probe=b97f13141f) | Aug 19, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [61f9640136](https://linux-hardware.org/?probe=61f9640136) | Aug 19, 2022 |
| HP            | 15                          | Notebook    | [166efee25e](https://linux-hardware.org/?probe=166efee25e) | Aug 19, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [7a9624c968](https://linux-hardware.org/?probe=7a9624c968) | Aug 19, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0ed8a39444](https://linux-hardware.org/?probe=0ed8a39444) | Aug 19, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [46208653fa](https://linux-hardware.org/?probe=46208653fa) | Aug 18, 2022 |
| Dell          | Latitude 3420               | Notebook    | [49300ca856](https://linux-hardware.org/?probe=49300ca856) | Aug 18, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [4c8af9dc73](https://linux-hardware.org/?probe=4c8af9dc73) | Aug 18, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [dcb33e35ae](https://linux-hardware.org/?probe=dcb33e35ae) | Aug 18, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [ae2d8ade73](https://linux-hardware.org/?probe=ae2d8ade73) | Aug 18, 2022 |
| Acer          | Aspire E1-431               | Notebook    | [d4132b425f](https://linux-hardware.org/?probe=d4132b425f) | Aug 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [944a99ea66](https://linux-hardware.org/?probe=944a99ea66) | Aug 17, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [e6e4efd93a](https://linux-hardware.org/?probe=e6e4efd93a) | Aug 17, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [c62f8ea53b](https://linux-hardware.org/?probe=c62f8ea53b) | Aug 17, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [8236615818](https://linux-hardware.org/?probe=8236615818) | Aug 17, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [32ccd17130](https://linux-hardware.org/?probe=32ccd17130) | Aug 17, 2022 |
| Dell          | Latitude 3420               | Notebook    | [33a254b0e0](https://linux-hardware.org/?probe=33a254b0e0) | Aug 17, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [e5dbfdb922](https://linux-hardware.org/?probe=e5dbfdb922) | Aug 16, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [1d2b1aa4bf](https://linux-hardware.org/?probe=1d2b1aa4bf) | Aug 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [1b12b01004](https://linux-hardware.org/?probe=1b12b01004) | Aug 16, 2022 |
| Dell          | Inspiron 5491 2n1           | Convertible | [6c0375d442](https://linux-hardware.org/?probe=6c0375d442) | Aug 16, 2022 |
| Toshiba       | TECRA R940                  | Notebook    | [f7a6618519](https://linux-hardware.org/?probe=f7a6618519) | Aug 14, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [265b666497](https://linux-hardware.org/?probe=265b666497) | Aug 14, 2022 |
| MSI           | Alpha 15 A3DD               | Notebook    | [fd548daf00](https://linux-hardware.org/?probe=fd548daf00) | Aug 14, 2022 |
| HP            | Presario CQ56               | Notebook    | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| Dell          | Latitude E6420              | Notebook    | [e295e29aa3](https://linux-hardware.org/?probe=e295e29aa3) | Aug 13, 2022 |
| HP            | Pavilion 15                 | Notebook    | [bafa6bfcb8](https://linux-hardware.org/?probe=bafa6bfcb8) | Aug 13, 2022 |
| Lenovo        | IdeaPad 3 15IML05 D1 81W... | Notebook    | [59b3324e73](https://linux-hardware.org/?probe=59b3324e73) | Aug 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f8a6209b06](https://linux-hardware.org/?probe=f8a6209b06) | Aug 12, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [8c6f00600e](https://linux-hardware.org/?probe=8c6f00600e) | Aug 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [1604d7a824](https://linux-hardware.org/?probe=1604d7a824) | Aug 11, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [29f3354492](https://linux-hardware.org/?probe=29f3354492) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [bc7a8afe56](https://linux-hardware.org/?probe=bc7a8afe56) | Aug 11, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [3ba16dc3e1](https://linux-hardware.org/?probe=3ba16dc3e1) | Aug 11, 2022 |
| Dell          | Latitude E7450              | Notebook    | [3992650626](https://linux-hardware.org/?probe=3992650626) | Aug 10, 2022 |
| HP            | 2B2F MVB,A                  | All in one  | [13aef3e1ef](https://linux-hardware.org/?probe=13aef3e1ef) | Aug 10, 2022 |
| HP            | 245 G7 Notebook PC          | Notebook    | [567786673d](https://linux-hardware.org/?probe=567786673d) | Aug 10, 2022 |
| Dell          | Vostro 3480                 | Notebook    | [31b062c315](https://linux-hardware.org/?probe=31b062c315) | Aug 10, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [48722889b6](https://linux-hardware.org/?probe=48722889b6) | Aug 10, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [a24161deaa](https://linux-hardware.org/?probe=a24161deaa) | Aug 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [364f2e0a23](https://linux-hardware.org/?probe=364f2e0a23) | Aug 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [4b6fc67f06](https://linux-hardware.org/?probe=4b6fc67f06) | Aug 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [e4c7906333](https://linux-hardware.org/?probe=e4c7906333) | Aug 09, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [dab9f235f5](https://linux-hardware.org/?probe=dab9f235f5) | Aug 09, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [e11856fcbc](https://linux-hardware.org/?probe=e11856fcbc) | Aug 09, 2022 |
| Timi          | Mi NoteBook Horizon Edit... | Notebook    | [52a0cb298b](https://linux-hardware.org/?probe=52a0cb298b) | Aug 09, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [98c601bb55](https://linux-hardware.org/?probe=98c601bb55) | Aug 08, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [b719fff96d](https://linux-hardware.org/?probe=b719fff96d) | Aug 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c2378f28](https://linux-hardware.org/?probe=49c2378f28) | Aug 08, 2022 |
| Dell          | Latitude 3510               | Notebook    | [5dd81ae3c1](https://linux-hardware.org/?probe=5dd81ae3c1) | Aug 08, 2022 |
| HP            | 15                          | Notebook    | [ef66e0296e](https://linux-hardware.org/?probe=ef66e0296e) | Aug 08, 2022 |
| Apple         | MacBook2,1                  | Notebook    | [d3f41ae4fb](https://linux-hardware.org/?probe=d3f41ae4fb) | Aug 08, 2022 |
| HP            | 2B2F MVB,A                  | All in one  | [f58caefd4f](https://linux-hardware.org/?probe=f58caefd4f) | Aug 08, 2022 |
| ASUSTek       | H110M-CS                    | Desktop     | [01e4feaac6](https://linux-hardware.org/?probe=01e4feaac6) | Aug 07, 2022 |
| HP            | Pavilion g6                 | Notebook    | [aa437aea14](https://linux-hardware.org/?probe=aa437aea14) | Aug 07, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [457fa11671](https://linux-hardware.org/?probe=457fa11671) | Aug 07, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7543f383ad](https://linux-hardware.org/?probe=7543f383ad) | Aug 07, 2022 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [8f7ef1d997](https://linux-hardware.org/?probe=8f7ef1d997) | Aug 07, 2022 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | Notebook    | [ffab2b901d](https://linux-hardware.org/?probe=ffab2b901d) | Aug 07, 2022 |
| HP            | Pavilion g6                 | Notebook    | [955d372528](https://linux-hardware.org/?probe=955d372528) | Aug 06, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7e9b1406b1](https://linux-hardware.org/?probe=7e9b1406b1) | Aug 06, 2022 |
| Sony          | VPCEB16FG                   | Notebook    | [6baf989163](https://linux-hardware.org/?probe=6baf989163) | Aug 06, 2022 |
| HP            | 430                         | Notebook    | [c30f00d442](https://linux-hardware.org/?probe=c30f00d442) | Aug 05, 2022 |
| ASUSTek       | D340MC-C                    | Desktop     | [69ddbb7acd](https://linux-hardware.org/?probe=69ddbb7acd) | Aug 05, 2022 |
| ASUSTek       | D340MC-C                    | Desktop     | [a87fc1ec66](https://linux-hardware.org/?probe=a87fc1ec66) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [e2545a7011](https://linux-hardware.org/?probe=e2545a7011) | Aug 04, 2022 |
| Dell          | Latitude E7470              | Notebook    | [16fd81987c](https://linux-hardware.org/?probe=16fd81987c) | Aug 04, 2022 |
| Gigabyte      | B360M GAMING HD             | Desktop     | [95e1eb0fcb](https://linux-hardware.org/?probe=95e1eb0fcb) | Aug 03, 2022 |
| LORD ELECT... | GM965 Series                | Desktop     | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [00c5ed086b](https://linux-hardware.org/?probe=00c5ed086b) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [4c75e1d374](https://linux-hardware.org/?probe=4c75e1d374) | Aug 03, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [91581d4ecd](https://linux-hardware.org/?probe=91581d4ecd) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [ad8af5c718](https://linux-hardware.org/?probe=ad8af5c718) | Aug 02, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b4e172e88b](https://linux-hardware.org/?probe=b4e172e88b) | Aug 02, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | Notebook    | [6a1b44dfe0](https://linux-hardware.org/?probe=6a1b44dfe0) | Aug 02, 2022 |
| Dell          | G3 3500                     | Notebook    | [440b43e5e5](https://linux-hardware.org/?probe=440b43e5e5) | Aug 02, 2022 |
| Dell          | Latitude 3410               | Notebook    | [b2d717d59e](https://linux-hardware.org/?probe=b2d717d59e) | Aug 02, 2022 |
| HP            | Pavilion g6                 | Notebook    | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| Acer          | Aspire 5560                 | Notebook    | [d5b8ae56fd](https://linux-hardware.org/?probe=d5b8ae56fd) | Aug 01, 2022 |
| HP            | ProBook 440 G2              | Notebook    | [00dd80ba31](https://linux-hardware.org/?probe=00dd80ba31) | Aug 01, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [f275229d83](https://linux-hardware.org/?probe=f275229d83) | Jul 31, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [8707ea39a2](https://linux-hardware.org/?probe=8707ea39a2) | Jul 31, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [9c161b860f](https://linux-hardware.org/?probe=9c161b860f) | Jul 31, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [b846739765](https://linux-hardware.org/?probe=b846739765) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | Notebook    | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [ab643dc6b0](https://linux-hardware.org/?probe=ab643dc6b0) | Jul 30, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [d67c93b534](https://linux-hardware.org/?probe=d67c93b534) | Jul 29, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a42627d17e](https://linux-hardware.org/?probe=a42627d17e) | Jul 29, 2022 |
| Dell          | 05XTT1 A01                  | Mini pc     | [c4ce2965af](https://linux-hardware.org/?probe=c4ce2965af) | Jul 29, 2022 |
| Lenovo        | ThinkPad X230 23253B3       | Notebook    | [fa19ec3adf](https://linux-hardware.org/?probe=fa19ec3adf) | Jul 29, 2022 |
| Intel         | IS80 V117                   | Notebook    | [cf45970313](https://linux-hardware.org/?probe=cf45970313) | Jul 29, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [8d87e3bb3b](https://linux-hardware.org/?probe=8d87e3bb3b) | Jul 28, 2022 |
| HP            | Pavilion 15                 | Notebook    | [512f5ada4a](https://linux-hardware.org/?probe=512f5ada4a) | Jul 28, 2022 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [afaf75a141](https://linux-hardware.org/?probe=afaf75a141) | Jul 28, 2022 |
| HP            | Pavilion 15                 | Notebook    | [b74fec46a0](https://linux-hardware.org/?probe=b74fec46a0) | Jul 28, 2022 |
| HP            | 348 G4                      | Notebook    | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Dell          | Inspiron 5502               | Notebook    | [f84c29c4b6](https://linux-hardware.org/?probe=f84c29c4b6) | Jul 27, 2022 |
| Sony          | VPCEB26FG                   | Notebook    | [49c139799c](https://linux-hardware.org/?probe=49c139799c) | Jul 27, 2022 |
| HP            | 86E9 A                      | Desktop     | [6634eaee32](https://linux-hardware.org/?probe=6634eaee32) | Jul 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [89398a36b1](https://linux-hardware.org/?probe=89398a36b1) | Jul 27, 2022 |
| HP            | 15                          | Notebook    | [9177a1f411](https://linux-hardware.org/?probe=9177a1f411) | Jul 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [f9203ffeed](https://linux-hardware.org/?probe=f9203ffeed) | Jul 26, 2022 |
| Dell          | Latitude 3410               | Notebook    | [20636bf80f](https://linux-hardware.org/?probe=20636bf80f) | Jul 26, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [c9534903a2](https://linux-hardware.org/?probe=c9534903a2) | Jul 26, 2022 |
| Dell          | Latitude 3440               | Notebook    | [a47121441e](https://linux-hardware.org/?probe=a47121441e) | Jul 25, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [da71f235a2](https://linux-hardware.org/?probe=da71f235a2) | Jul 25, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [a1346acc8a](https://linux-hardware.org/?probe=a1346acc8a) | Jul 25, 2022 |
| Dell          | Vostro 3491                 | Notebook    | [6ce65dccb7](https://linux-hardware.org/?probe=6ce65dccb7) | Jul 24, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [df25f468ef](https://linux-hardware.org/?probe=df25f468ef) | Jul 24, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [acc1cd1dcf](https://linux-hardware.org/?probe=acc1cd1dcf) | Jul 24, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [51b984566a](https://linux-hardware.org/?probe=51b984566a) | Jul 24, 2022 |
| Google        | Wolf                        | Notebook    | [f2397aadef](https://linux-hardware.org/?probe=f2397aadef) | Jul 23, 2022 |
| Google        | Wolf                        | Notebook    | [ffa74c4dc0](https://linux-hardware.org/?probe=ffa74c4dc0) | Jul 23, 2022 |
| HP            | Laptop 14q-bu1xx            | Notebook    | [7fa58abd22](https://linux-hardware.org/?probe=7fa58abd22) | Jul 23, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [492b4e1236](https://linux-hardware.org/?probe=492b4e1236) | Jul 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [9002ca2e54](https://linux-hardware.org/?probe=9002ca2e54) | Jul 23, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [e06076002a](https://linux-hardware.org/?probe=e06076002a) | Jul 22, 2022 |
| Lenovo        | ThinkPad T490 20RYS01J00    | Notebook    | [415229917b](https://linux-hardware.org/?probe=415229917b) | Jul 22, 2022 |
| Sony          | SVF15318SNB                 | Notebook    | [176c871bf8](https://linux-hardware.org/?probe=176c871bf8) | Jul 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [b0a8b9eb01](https://linux-hardware.org/?probe=b0a8b9eb01) | Jul 21, 2022 |
| HP            | 3397                        | Desktop     | [017afa048c](https://linux-hardware.org/?probe=017afa048c) | Jul 20, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [ef41a8c220](https://linux-hardware.org/?probe=ef41a8c220) | Jul 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YES... | Notebook    | [48e2fa9544](https://linux-hardware.org/?probe=48e2fa9544) | Jul 19, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [db7cb6f32b](https://linux-hardware.org/?probe=db7cb6f32b) | Jul 18, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [c1c146a0f9](https://linux-hardware.org/?probe=c1c146a0f9) | Jul 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [672bba3723](https://linux-hardware.org/?probe=672bba3723) | Jul 17, 2022 |
| HP            | ProBook 4441s               | Notebook    | [b108eaada9](https://linux-hardware.org/?probe=b108eaada9) | Jul 17, 2022 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [8b5480a55e](https://linux-hardware.org/?probe=8b5480a55e) | Jul 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [79168ebd0b](https://linux-hardware.org/?probe=79168ebd0b) | Jul 16, 2022 |
| Alienware     | 15 R2                       | Notebook    | [8a6bd6054f](https://linux-hardware.org/?probe=8a6bd6054f) | Jul 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [42de47cdc1](https://linux-hardware.org/?probe=42de47cdc1) | Jul 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 Ua 81W... | Notebook    | [513e2ede59](https://linux-hardware.org/?probe=513e2ede59) | Jul 15, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [a55538b651](https://linux-hardware.org/?probe=a55538b651) | Jul 14, 2022 |
| Teclast       | TbooK 10 S                  | Tablet      | [127f1fa76a](https://linux-hardware.org/?probe=127f1fa76a) | Jul 14, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a8d726c8b2](https://linux-hardware.org/?probe=a8d726c8b2) | Jul 14, 2022 |
| HP            | Notebook -15q-bu004tu       | Notebook    | [b15814c3b1](https://linux-hardware.org/?probe=b15814c3b1) | Jul 14, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [b78b735f01](https://linux-hardware.org/?probe=b78b735f01) | Jul 14, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [fc969f7c75](https://linux-hardware.org/?probe=fc969f7c75) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 Ua 81W... | Notebook    | [f0a069d567](https://linux-hardware.org/?probe=f0a069d567) | Jul 13, 2022 |
| HP            | Notebook -15q-bu004tu       | Notebook    | [f45fde1a93](https://linux-hardware.org/?probe=f45fde1a93) | Jul 13, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [c9842baa35](https://linux-hardware.org/?probe=c9842baa35) | Jul 12, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [a002ac843c](https://linux-hardware.org/?probe=a002ac843c) | Jul 12, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [79ecbebabd](https://linux-hardware.org/?probe=79ecbebabd) | Jul 12, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [aba10c973c](https://linux-hardware.org/?probe=aba10c973c) | Jul 11, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [1725714269](https://linux-hardware.org/?probe=1725714269) | Jul 11, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [cc10e6800a](https://linux-hardware.org/?probe=cc10e6800a) | Jul 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [2bfb2ba391](https://linux-hardware.org/?probe=2bfb2ba391) | Jul 11, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [41b46c06f1](https://linux-hardware.org/?probe=41b46c06f1) | Jul 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [1755faf164](https://linux-hardware.org/?probe=1755faf164) | Jul 11, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [46e84f6c32](https://linux-hardware.org/?probe=46e84f6c32) | Jul 10, 2022 |
| Intel         | DH61WW AAG23116-301         | Desktop     | [3b4120b3af](https://linux-hardware.org/?probe=3b4120b3af) | Jul 09, 2022 |
| ASUSTek       | X507UB                      | Notebook    | [53a07e58b8](https://linux-hardware.org/?probe=53a07e58b8) | Jul 09, 2022 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | Notebook    | [95ff55839b](https://linux-hardware.org/?probe=95ff55839b) | Jul 09, 2022 |
| HP            | ProBook 440 G2              | Notebook    | [a2a01affe3](https://linux-hardware.org/?probe=a2a01affe3) | Jul 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [b3cdd2b6f6](https://linux-hardware.org/?probe=b3cdd2b6f6) | Jul 09, 2022 |
| Intel         | H81                         | Desktop     | [e1a730a6e6](https://linux-hardware.org/?probe=e1a730a6e6) | Jul 08, 2022 |
| HP            | 15                          | Notebook    | [a7bfa741b3](https://linux-hardware.org/?probe=a7bfa741b3) | Jul 08, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [ec18f88382](https://linux-hardware.org/?probe=ec18f88382) | Jul 07, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [c9eb8f9a5f](https://linux-hardware.org/?probe=c9eb8f9a5f) | Jul 07, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [f9d01cacbb](https://linux-hardware.org/?probe=f9d01cacbb) | Jul 07, 2022 |
| HP            | 3397                        | Desktop     | [5f251b624d](https://linux-hardware.org/?probe=5f251b624d) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [16c6df7b29](https://linux-hardware.org/?probe=16c6df7b29) | Jul 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [6b25430dc1](https://linux-hardware.org/?probe=6b25430dc1) | Jul 07, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [76de8069a0](https://linux-hardware.org/?probe=76de8069a0) | Jul 07, 2022 |
| HP            | Mini 110-3100               | Notebook    | [5222f63258](https://linux-hardware.org/?probe=5222f63258) | Jul 06, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [342362a5f8](https://linux-hardware.org/?probe=342362a5f8) | Jul 06, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [21f58df6b0](https://linux-hardware.org/?probe=21f58df6b0) | Jul 06, 2022 |
| Dell          | Precision 5530              | Notebook    | [cbe37ac52f](https://linux-hardware.org/?probe=cbe37ac52f) | Jul 05, 2022 |
| Dell          | Latitude 3540               | Notebook    | [a689d5019b](https://linux-hardware.org/?probe=a689d5019b) | Jul 05, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4f82c838cb](https://linux-hardware.org/?probe=4f82c838cb) | Jul 04, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [697729549b](https://linux-hardware.org/?probe=697729549b) | Jul 04, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [31226ebc70](https://linux-hardware.org/?probe=31226ebc70) | Jul 04, 2022 |
| HP            | Notebook                    | Notebook    | [b9eb2e4cdd](https://linux-hardware.org/?probe=b9eb2e4cdd) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [c208a1e955](https://linux-hardware.org/?probe=c208a1e955) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [65debb520a](https://linux-hardware.org/?probe=65debb520a) | Jul 04, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [2a4654f61b](https://linux-hardware.org/?probe=2a4654f61b) | Jul 03, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [ff830000cf](https://linux-hardware.org/?probe=ff830000cf) | Jul 03, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [5f2c58d24a](https://linux-hardware.org/?probe=5f2c58d24a) | Jul 03, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [8a10d711f8](https://linux-hardware.org/?probe=8a10d711f8) | Jul 03, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [ce9585eac5](https://linux-hardware.org/?probe=ce9585eac5) | Jul 03, 2022 |
| MSI           | B365M PRO-VDH               | Desktop     | [8ce7059868](https://linux-hardware.org/?probe=8ce7059868) | Jul 03, 2022 |
| Gigabyte      | H81M-S                      | Desktop     | [4a6acd9191](https://linux-hardware.org/?probe=4a6acd9191) | Jul 02, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fdb841889e](https://linux-hardware.org/?probe=fdb841889e) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX705DD_FX705... | Notebook    | [048a900062](https://linux-hardware.org/?probe=048a900062) | Jul 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [dffcf6cd44](https://linux-hardware.org/?probe=dffcf6cd44) | Jul 02, 2022 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [54a9d6bcb3](https://linux-hardware.org/?probe=54a9d6bcb3) | Jul 02, 2022 |
| Lenovo        | Erazer Y50-70               | Notebook    | [c147e10488](https://linux-hardware.org/?probe=c147e10488) | Jul 02, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [9034bf7260](https://linux-hardware.org/?probe=9034bf7260) | Jul 01, 2022 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [0364230bc7](https://linux-hardware.org/?probe=0364230bc7) | Jul 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | Notebook    | [430c2e6760](https://linux-hardware.org/?probe=430c2e6760) | Jul 01, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [7e809da3ad](https://linux-hardware.org/?probe=7e809da3ad) | Jul 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f54987d748](https://linux-hardware.org/?probe=f54987d748) | Jul 01, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [13e85826c2](https://linux-hardware.org/?probe=13e85826c2) | Jun 30, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [bb4df4398e](https://linux-hardware.org/?probe=bb4df4398e) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [f29c4de6b4](https://linux-hardware.org/?probe=f29c4de6b4) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [7ecd760977](https://linux-hardware.org/?probe=7ecd760977) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | Notebook    | [8428ba0120](https://linux-hardware.org/?probe=8428ba0120) | Jun 30, 2022 |
| Gigabyte      | GB-BSi5-1135G7              | Desktop     | [4701b81ce2](https://linux-hardware.org/?probe=4701b81ce2) | Jun 30, 2022 |
| HP            | 1000                        | Notebook    | [65ae23140e](https://linux-hardware.org/?probe=65ae23140e) | Jun 30, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [1f9d3b4a6c](https://linux-hardware.org/?probe=1f9d3b4a6c) | Jun 29, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [0244eb4fde](https://linux-hardware.org/?probe=0244eb4fde) | Jun 29, 2022 |
| MSI           | A320M PRO-VD/S V2           | Desktop     | [fc5a5d812c](https://linux-hardware.org/?probe=fc5a5d812c) | Jun 29, 2022 |
| Acer          | H81-M1                      | Desktop     | [9ddfb2ec8d](https://linux-hardware.org/?probe=9ddfb2ec8d) | Jun 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [d240efa39f](https://linux-hardware.org/?probe=d240efa39f) | Jun 28, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [dc3e219327](https://linux-hardware.org/?probe=dc3e219327) | Jun 28, 2022 |
| Lenovo        | B41-80 80LG                 | Notebook    | [30f6e726bd](https://linux-hardware.org/?probe=30f6e726bd) | Jun 28, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [404e9daae2](https://linux-hardware.org/?probe=404e9daae2) | Jun 27, 2022 |
| Unknown       | Unknown                     | Desktop     | [bd912e1acc](https://linux-hardware.org/?probe=bd912e1acc) | Jun 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [569faf34f1](https://linux-hardware.org/?probe=569faf34f1) | Jun 27, 2022 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [7e1e1cf659](https://linux-hardware.org/?probe=7e1e1cf659) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3a651b23fb](https://linux-hardware.org/?probe=3a651b23fb) | Jun 26, 2022 |
| HP            | Laptop 15g-br1xx            | Notebook    | [aef95d312f](https://linux-hardware.org/?probe=aef95d312f) | Jun 26, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [db6195eed2](https://linux-hardware.org/?probe=db6195eed2) | Jun 26, 2022 |
| ASUSTek       | X510UNR                     | Notebook    | [d5f3803a24](https://linux-hardware.org/?probe=d5f3803a24) | Jun 26, 2022 |
| HP            | Pavilion 15                 | Notebook    | [929cd4988f](https://linux-hardware.org/?probe=929cd4988f) | Jun 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [d2e82f01d9](https://linux-hardware.org/?probe=d2e82f01d9) | Jun 25, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [5ec853b08c](https://linux-hardware.org/?probe=5ec853b08c) | Jun 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a2f3ee6e42](https://linux-hardware.org/?probe=a2f3ee6e42) | Jun 24, 2022 |
| HP            | 8431                        | All in one  | [e8cbe50e2f](https://linux-hardware.org/?probe=e8cbe50e2f) | Jun 24, 2022 |
| HP            | 8431                        | All in one  | [1a65660840](https://linux-hardware.org/?probe=1a65660840) | Jun 24, 2022 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [1b382e0eb0](https://linux-hardware.org/?probe=1b382e0eb0) | Jun 23, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [d3a3e2cf32](https://linux-hardware.org/?probe=d3a3e2cf32) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d98df1e3c5](https://linux-hardware.org/?probe=d98df1e3c5) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [8adbb8b56a](https://linux-hardware.org/?probe=8adbb8b56a) | Jun 22, 2022 |
| Lenovo        | ThinkPad T420 4177Q5U       | Notebook    | [cf27027c76](https://linux-hardware.org/?probe=cf27027c76) | Jun 22, 2022 |
| Acer          | H110H4-M14 P21-A2E          | Desktop     | [f3c553d3f0](https://linux-hardware.org/?probe=f3c553d3f0) | Jun 22, 2022 |
| Gigabyte      | H61M-S2P                    | Desktop     | [ac99674975](https://linux-hardware.org/?probe=ac99674975) | Jun 22, 2022 |
| Acer          | H110H4-M14 P21-A2E          | Desktop     | [17e46ecec3](https://linux-hardware.org/?probe=17e46ecec3) | Jun 22, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [f25ac785b7](https://linux-hardware.org/?probe=f25ac785b7) | Jun 22, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [93f08af289](https://linux-hardware.org/?probe=93f08af289) | Jun 21, 2022 |
| Gigabyte      | H410M S2 V3                 | Desktop     | [79ac3d3f38](https://linux-hardware.org/?probe=79ac3d3f38) | Jun 21, 2022 |
| Dell          | Vostro 2420                 | Notebook    | [84a4eb23c6](https://linux-hardware.org/?probe=84a4eb23c6) | Jun 21, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [6ce6e1d459](https://linux-hardware.org/?probe=6ce6e1d459) | Jun 20, 2022 |
| Dell          | Vostro 3490                 | Notebook    | [c203985c20](https://linux-hardware.org/?probe=c203985c20) | Jun 20, 2022 |
| Dell          | Vostro 3490                 | Notebook    | [e0968d0d2b](https://linux-hardware.org/?probe=e0968d0d2b) | Jun 20, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d4aa7ef4a3](https://linux-hardware.org/?probe=d4aa7ef4a3) | Jun 20, 2022 |
| Dell          | Vostro 14-3468              | Notebook    | [1f0ee8f5fd](https://linux-hardware.org/?probe=1f0ee8f5fd) | Jun 20, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [90f4bec7db](https://linux-hardware.org/?probe=90f4bec7db) | Jun 19, 2022 |
| HP            | EliteBook 1050 G1           | Notebook    | [731ecfced1](https://linux-hardware.org/?probe=731ecfced1) | Jun 18, 2022 |
| Lenovo        | ThinkPad E490 20N8S01H00    | Notebook    | [7f96502192](https://linux-hardware.org/?probe=7f96502192) | Jun 18, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [31cdb7f2fc](https://linux-hardware.org/?probe=31cdb7f2fc) | Jun 17, 2022 |
| HP            | Unknown                     | Notebook    | [4c4cdf6526](https://linux-hardware.org/?probe=4c4cdf6526) | Jun 17, 2022 |
| Dell          | Latitude 5310               | Notebook    | [d34d939bae](https://linux-hardware.org/?probe=d34d939bae) | Jun 17, 2022 |
| Sony          | SVE15128CNB                 | Notebook    | [029a230c77](https://linux-hardware.org/?probe=029a230c77) | Jun 17, 2022 |
| Unknown       | G41 Series                  | Desktop     | [d257436f52](https://linux-hardware.org/?probe=d257436f52) | Jun 17, 2022 |
| Dell          | Latitude 3450               | Notebook    | [f0bff3d433](https://linux-hardware.org/?probe=f0bff3d433) | Jun 16, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [10304caa6b](https://linux-hardware.org/?probe=10304caa6b) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [b136496151](https://linux-hardware.org/?probe=b136496151) | Jun 16, 2022 |
| ITI LIMITE... | SMAASH XU3i                 | Desktop     | [549a55efdf](https://linux-hardware.org/?probe=549a55efdf) | Jun 16, 2022 |
| ITI LIMITE... | SMAASH XU3i                 | Desktop     | [693d81e1a3](https://linux-hardware.org/?probe=693d81e1a3) | Jun 16, 2022 |
| ASUSTek       | ET2040I                     | Notebook    | [45273f0675](https://linux-hardware.org/?probe=45273f0675) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0ca08532ce](https://linux-hardware.org/?probe=0ca08532ce) | Jun 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | Notebook    | [b10e894950](https://linux-hardware.org/?probe=b10e894950) | Jun 14, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [002c21e90f](https://linux-hardware.org/?probe=002c21e90f) | Jun 14, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [dfa7cc38e7](https://linux-hardware.org/?probe=dfa7cc38e7) | Jun 14, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [0ac0a212e0](https://linux-hardware.org/?probe=0ac0a212e0) | Jun 13, 2022 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [7aaeea9280](https://linux-hardware.org/?probe=7aaeea9280) | Jun 13, 2022 |
| HP            | Laptop 15q-bu0xx            | Notebook    | [859d1ddbb0](https://linux-hardware.org/?probe=859d1ddbb0) | Jun 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0d74445d24](https://linux-hardware.org/?probe=0d74445d24) | Jun 13, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [d6e47a7c18](https://linux-hardware.org/?probe=d6e47a7c18) | Jun 12, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [9840a70112](https://linux-hardware.org/?probe=9840a70112) | Jun 11, 2022 |
| AVITA         | NE14A2                      | Notebook    | [3ac292714a](https://linux-hardware.org/?probe=3ac292714a) | Jun 10, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [d80ec10f91](https://linux-hardware.org/?probe=d80ec10f91) | Jun 09, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [39e10fd449](https://linux-hardware.org/?probe=39e10fd449) | Jun 09, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4102e98034](https://linux-hardware.org/?probe=4102e98034) | Jun 09, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [ef8cc06070](https://linux-hardware.org/?probe=ef8cc06070) | Jun 09, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | Notebook    | [321a2df7db](https://linux-hardware.org/?probe=321a2df7db) | Jun 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [484996e8db](https://linux-hardware.org/?probe=484996e8db) | Jun 08, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [224023dfd2](https://linux-hardware.org/?probe=224023dfd2) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [1f5918622d](https://linux-hardware.org/?probe=1f5918622d) | Jun 08, 2022 |
| Biostar       | H61MLV3                     | Desktop     | [dd47d4aac6](https://linux-hardware.org/?probe=dd47d4aac6) | Jun 08, 2022 |
| Biostar       | H61MLV3                     | Desktop     | [906bb764d6](https://linux-hardware.org/?probe=906bb764d6) | Jun 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [b27a6ef652](https://linux-hardware.org/?probe=b27a6ef652) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | Notebook    | [20a629adc2](https://linux-hardware.org/?probe=20a629adc2) | Jun 08, 2022 |
| Acer          | Swift SF313-53              | Notebook    | [68dff2bc8e](https://linux-hardware.org/?probe=68dff2bc8e) | Jun 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [1a79b3a2ab](https://linux-hardware.org/?probe=1a79b3a2ab) | Jun 07, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [02f5bd70bb](https://linux-hardware.org/?probe=02f5bd70bb) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [27ac9bc8f9](https://linux-hardware.org/?probe=27ac9bc8f9) | Jun 07, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [7fdce576b4](https://linux-hardware.org/?probe=7fdce576b4) | Jun 07, 2022 |
| Flipkart I... | NKi510TL85S                 | Notebook    | [6e1326c27f](https://linux-hardware.org/?probe=6e1326c27f) | Jun 07, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [affa614c99](https://linux-hardware.org/?probe=affa614c99) | Jun 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [b2a364340d](https://linux-hardware.org/?probe=b2a364340d) | Jun 07, 2022 |
| Unknown       | X31_ICH7                    | Desktop     | [f8ab18b666](https://linux-hardware.org/?probe=f8ab18b666) | Jun 07, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [81fad50492](https://linux-hardware.org/?probe=81fad50492) | Jun 06, 2022 |
| Lenovo        | 81WE                        | Notebook    | [31217f3c4a](https://linux-hardware.org/?probe=31217f3c4a) | Jun 06, 2022 |
| Intel         | H61                         | Desktop     | [8178c4da07](https://linux-hardware.org/?probe=8178c4da07) | Jun 06, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [caa9a0cf2f](https://linux-hardware.org/?probe=caa9a0cf2f) | Jun 06, 2022 |
| HP            | 8648                        | Desktop     | [155bf69660](https://linux-hardware.org/?probe=155bf69660) | Jun 05, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [d8a8c3c8b4](https://linux-hardware.org/?probe=d8a8c3c8b4) | Jun 05, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f1becc237d](https://linux-hardware.org/?probe=f1becc237d) | Jun 05, 2022 |
| Dell          | Latitude E6420              | Notebook    | [01eb3f0d4b](https://linux-hardware.org/?probe=01eb3f0d4b) | Jun 05, 2022 |
| Dell          | G3 3500                     | Notebook    | [6734206fa0](https://linux-hardware.org/?probe=6734206fa0) | Jun 05, 2022 |
| HP            | 15                          | Notebook    | [3e96827fe7](https://linux-hardware.org/?probe=3e96827fe7) | Jun 04, 2022 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [41f0428c2b](https://linux-hardware.org/?probe=41f0428c2b) | Jun 04, 2022 |
| Dell          | Inspiron 3584               | Notebook    | [843797dc80](https://linux-hardware.org/?probe=843797dc80) | Jun 04, 2022 |
| HP            | 15                          | Notebook    | [b256b9e839](https://linux-hardware.org/?probe=b256b9e839) | Jun 04, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [66cc7342ec](https://linux-hardware.org/?probe=66cc7342ec) | Jun 04, 2022 |
| Lenovo        | ThinkPad T430 2349LTU       | Notebook    | [2c80cec3c3](https://linux-hardware.org/?probe=2c80cec3c3) | Jun 03, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9533388943](https://linux-hardware.org/?probe=9533388943) | Jun 03, 2022 |
| Lenovo        | IdeaPad V15-ADA             | Notebook    | [94971f4968](https://linux-hardware.org/?probe=94971f4968) | Jun 03, 2022 |
| Dell          | Latitude 7390               | Notebook    | [0c7c9778aa](https://linux-hardware.org/?probe=0c7c9778aa) | Jun 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YFC... | Notebook    | [ac0d3882ca](https://linux-hardware.org/?probe=ac0d3882ca) | Jun 01, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0f84f94a6a](https://linux-hardware.org/?probe=0f84f94a6a) | Jun 01, 2022 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [5b8924befc](https://linux-hardware.org/?probe=5b8924befc) | May 31, 2022 |
| MSI           | B450M GAMING PLUS           | Desktop     | [db537b41f4](https://linux-hardware.org/?probe=db537b41f4) | May 31, 2022 |
| Lenovo        | Erazer Y50-70               | Notebook    | [abb6af451d](https://linux-hardware.org/?probe=abb6af451d) | May 31, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [3fbca187e7](https://linux-hardware.org/?probe=3fbca187e7) | May 31, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2f14b6956f](https://linux-hardware.org/?probe=2f14b6956f) | May 31, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [871738fea2](https://linux-hardware.org/?probe=871738fea2) | May 31, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [f3a24fbc49](https://linux-hardware.org/?probe=f3a24fbc49) | May 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YFC... | Notebook    | [784e1ca4cc](https://linux-hardware.org/?probe=784e1ca4cc) | May 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a82494e1f3](https://linux-hardware.org/?probe=a82494e1f3) | May 29, 2022 |
| Dell          | Vostro 3546                 | Notebook    | [3acd5d4cb0](https://linux-hardware.org/?probe=3acd5d4cb0) | May 28, 2022 |
| Lenovo        | CRESCENTBAY 31900059 STD... | All in one  | [d222b1e86e](https://linux-hardware.org/?probe=d222b1e86e) | May 28, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [4c4689f4b7](https://linux-hardware.org/?probe=4c4689f4b7) | May 28, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [9d9d577f12](https://linux-hardware.org/?probe=9d9d577f12) | May 28, 2022 |
| Dell          | 0NKW6Y A00                  | Desktop     | [778ccadd42](https://linux-hardware.org/?probe=778ccadd42) | May 27, 2022 |
| Dell          | Latitude 5480               | Notebook    | [6056df9c22](https://linux-hardware.org/?probe=6056df9c22) | May 27, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [bf6cb72634](https://linux-hardware.org/?probe=bf6cb72634) | May 26, 2022 |
| Unknown       | G41 Series                  | Desktop     | [e9a273726a](https://linux-hardware.org/?probe=e9a273726a) | May 26, 2022 |
| Acer          | Aspire A515-46              | Notebook    | [e004aa3fd2](https://linux-hardware.org/?probe=e004aa3fd2) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [87460a83e8](https://linux-hardware.org/?probe=87460a83e8) | May 25, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [38ac6de56d](https://linux-hardware.org/?probe=38ac6de56d) | May 25, 2022 |
| Unknown       | G41 Series                  | Desktop     | [f0890bb556](https://linux-hardware.org/?probe=f0890bb556) | May 24, 2022 |
| INP           | i1000BTS                    | Desktop     | [95da2ada33](https://linux-hardware.org/?probe=95da2ada33) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [aeb154944d](https://linux-hardware.org/?probe=aeb154944d) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [bcccd55aab](https://linux-hardware.org/?probe=bcccd55aab) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [8d8d5ff5e1](https://linux-hardware.org/?probe=8d8d5ff5e1) | May 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [bf692d5408](https://linux-hardware.org/?probe=bf692d5408) | May 23, 2022 |
| Dell          | Latitude 3450               | Notebook    | [f788f954ec](https://linux-hardware.org/?probe=f788f954ec) | May 23, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [872649a8b4](https://linux-hardware.org/?probe=872649a8b4) | May 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f2e32c336d](https://linux-hardware.org/?probe=f2e32c336d) | May 23, 2022 |
| Lenovo        | S20-30 20421                | Notebook    | [58d0509bff](https://linux-hardware.org/?probe=58d0509bff) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | Notebook    | [f17079bdce](https://linux-hardware.org/?probe=f17079bdce) | May 22, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [d49880e4c2](https://linux-hardware.org/?probe=d49880e4c2) | May 22, 2022 |
| Acer          | Swift SF514-52T             | Notebook    | [40d5ca6bab](https://linux-hardware.org/?probe=40d5ca6bab) | May 22, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [10d158c79e](https://linux-hardware.org/?probe=10d158c79e) | May 22, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [4e1e3e6863](https://linux-hardware.org/?probe=4e1e3e6863) | May 22, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [afca2e1045](https://linux-hardware.org/?probe=afca2e1045) | May 22, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [914eca828e](https://linux-hardware.org/?probe=914eca828e) | May 22, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3b904a10e3](https://linux-hardware.org/?probe=3b904a10e3) | May 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e165a36a31](https://linux-hardware.org/?probe=e165a36a31) | May 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f729776db3](https://linux-hardware.org/?probe=f729776db3) | May 21, 2022 |
| Acer          | Swift SF514-54T             | Notebook    | [29b06de977](https://linux-hardware.org/?probe=29b06de977) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [01e2d063e8](https://linux-hardware.org/?probe=01e2d063e8) | May 21, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [f3986d7e7d](https://linux-hardware.org/?probe=f3986d7e7d) | May 21, 2022 |
| Gigabyte      | B660M DS3H AX DDR4          | Desktop     | [d5e0667318](https://linux-hardware.org/?probe=d5e0667318) | May 20, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [efd1b236a1](https://linux-hardware.org/?probe=efd1b236a1) | May 20, 2022 |
| Alienware     | x17 R2                      | Notebook    | [019dbb46a4](https://linux-hardware.org/?probe=019dbb46a4) | May 20, 2022 |
| Unknown       | G41 Series                  | Desktop     | [94dcbec5e7](https://linux-hardware.org/?probe=94dcbec5e7) | May 20, 2022 |
| Toshiba       | Satellite U940              | Notebook    | [249374be01](https://linux-hardware.org/?probe=249374be01) | May 19, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [dba5104e21](https://linux-hardware.org/?probe=dba5104e21) | May 18, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [fac15b2640](https://linux-hardware.org/?probe=fac15b2640) | May 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [57610c67ba](https://linux-hardware.org/?probe=57610c67ba) | May 18, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [0a25740096](https://linux-hardware.org/?probe=0a25740096) | May 18, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d831b6cb22](https://linux-hardware.org/?probe=d831b6cb22) | May 17, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [0095bc3389](https://linux-hardware.org/?probe=0095bc3389) | May 16, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [2dac9974af](https://linux-hardware.org/?probe=2dac9974af) | May 16, 2022 |
| Dell          | Precision 3551              | Notebook    | [f134f92d00](https://linux-hardware.org/?probe=f134f92d00) | May 16, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [b4d7d75ad1](https://linux-hardware.org/?probe=b4d7d75ad1) | May 15, 2022 |
| Lenovo        | S20-30 20421                | Notebook    | [7436d81709](https://linux-hardware.org/?probe=7436d81709) | May 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a2fa413622](https://linux-hardware.org/?probe=a2fa413622) | May 15, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [459e7e3586](https://linux-hardware.org/?probe=459e7e3586) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [a442279a0b](https://linux-hardware.org/?probe=a442279a0b) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [88c0d2c252](https://linux-hardware.org/?probe=88c0d2c252) | May 15, 2022 |
| Sony          | VPCEA36FG                   | Notebook    | [0161a27629](https://linux-hardware.org/?probe=0161a27629) | May 13, 2022 |
| HP            | 15                          | Notebook    | [32a7709448](https://linux-hardware.org/?probe=32a7709448) | May 13, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [2a1cf069bc](https://linux-hardware.org/?probe=2a1cf069bc) | May 13, 2022 |
| AVITA         | NS14A8                      | Notebook    | [bc86f7a17e](https://linux-hardware.org/?probe=bc86f7a17e) | May 13, 2022 |
| Dell          | Precision M2800             | Notebook    | [266af2c2b7](https://linux-hardware.org/?probe=266af2c2b7) | May 13, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [3eaf81c13c](https://linux-hardware.org/?probe=3eaf81c13c) | May 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [4d2b2c6a3c](https://linux-hardware.org/?probe=4d2b2c6a3c) | May 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [ed11a30da0](https://linux-hardware.org/?probe=ed11a30da0) | May 12, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | Notebook    | [bbf4ef2a08](https://linux-hardware.org/?probe=bbf4ef2a08) | May 11, 2022 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | Notebook    | [65fce47240](https://linux-hardware.org/?probe=65fce47240) | May 11, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | Notebook    | [61327f1e21](https://linux-hardware.org/?probe=61327f1e21) | May 11, 2022 |
| Dell          | G3 3579                     | Notebook    | [eff2c45d12](https://linux-hardware.org/?probe=eff2c45d12) | May 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [17b75bcced](https://linux-hardware.org/?probe=17b75bcced) | May 10, 2022 |
| HP            | 15                          | Notebook    | [fdef27b310](https://linux-hardware.org/?probe=fdef27b310) | May 10, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | 2000                        | Notebook    | [d0e74bfff6](https://linux-hardware.org/?probe=d0e74bfff6) | May 10, 2022 |
| HP            | Notebook                    | Notebook    | [afe98a811e](https://linux-hardware.org/?probe=afe98a811e) | May 10, 2022 |
| HP            | Pavilion dv6                | Notebook    | [165c15d078](https://linux-hardware.org/?probe=165c15d078) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [911b8e4c5b](https://linux-hardware.org/?probe=911b8e4c5b) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8e43525285](https://linux-hardware.org/?probe=8e43525285) | May 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [3227adfd1a](https://linux-hardware.org/?probe=3227adfd1a) | May 07, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QX01    | Notebook    | [68fbf0cacb](https://linux-hardware.org/?probe=68fbf0cacb) | May 07, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T2S... | Notebook    | [70fe076856](https://linux-hardware.org/?probe=70fe076856) | May 06, 2022 |
| Google        | Lick                        | Notebook    | [60e52e55e1](https://linux-hardware.org/?probe=60e52e55e1) | May 06, 2022 |
| Lenovo        | ThinkPad L13 20R3S10R00     | Notebook    | [b173909e06](https://linux-hardware.org/?probe=b173909e06) | May 06, 2022 |
| HP            | Notebook                    | Notebook    | [05f1b18534](https://linux-hardware.org/?probe=05f1b18534) | May 04, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [db81dd7652](https://linux-hardware.org/?probe=db81dd7652) | May 04, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [156de9d4de](https://linux-hardware.org/?probe=156de9d4de) | May 04, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [aa14a3b075](https://linux-hardware.org/?probe=aa14a3b075) | May 04, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [8bfd6ecc71](https://linux-hardware.org/?probe=8bfd6ecc71) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [bf9f724f45](https://linux-hardware.org/?probe=bf9f724f45) | May 04, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [05585fedf4](https://linux-hardware.org/?probe=05585fedf4) | May 04, 2022 |
| HP            | Pavilion Laptop 15-cs1xx... | Notebook    | [ca91daf662](https://linux-hardware.org/?probe=ca91daf662) | May 04, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [329673fcbf](https://linux-hardware.org/?probe=329673fcbf) | May 03, 2022 |
| ASUSTek       | ROG Strix G713RC_G713RC     | Notebook    | [2ce25fb058](https://linux-hardware.org/?probe=2ce25fb058) | May 03, 2022 |
| Lenovo        | 3724                        | All in one  | [fa47d5fd48](https://linux-hardware.org/?probe=fa47d5fd48) | May 03, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [aa3fb50ed5](https://linux-hardware.org/?probe=aa3fb50ed5) | May 03, 2022 |
| Toshiba       | Satellite U940              | Notebook    | [3d6bd2511e](https://linux-hardware.org/?probe=3d6bd2511e) | May 03, 2022 |
| HP            | Presario CQ42               | Notebook    | [93ac0fd52a](https://linux-hardware.org/?probe=93ac0fd52a) | May 02, 2022 |
| Maxtone       | HIS-G41L V1.1               | Desktop     | [ce61ffd777](https://linux-hardware.org/?probe=ce61ffd777) | May 02, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [dcea7cd8c0](https://linux-hardware.org/?probe=dcea7cd8c0) | May 02, 2022 |
| Maxtone       | HIS-G41L V1.1               | Desktop     | [63fc1199bc](https://linux-hardware.org/?probe=63fc1199bc) | May 01, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [0eb277ff80](https://linux-hardware.org/?probe=0eb277ff80) | May 01, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [549ca9da46](https://linux-hardware.org/?probe=549ca9da46) | May 01, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [ec3ccc4967](https://linux-hardware.org/?probe=ec3ccc4967) | May 01, 2022 |
| Dell          | Latitude 3490               | Notebook    | [ff6e81ce15](https://linux-hardware.org/?probe=ff6e81ce15) | May 01, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [50d37d9cf7](https://linux-hardware.org/?probe=50d37d9cf7) | May 01, 2022 |
| Acer          | Swift SF314-55G             | Notebook    | [1935c949a2](https://linux-hardware.org/?probe=1935c949a2) | May 01, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [37b324ecf9](https://linux-hardware.org/?probe=37b324ecf9) | May 01, 2022 |
| Dell          | G3 3500                     | Notebook    | [df72f36c52](https://linux-hardware.org/?probe=df72f36c52) | Apr 30, 2022 |
| Google        | Lick                        | Notebook    | [33d1e6209a](https://linux-hardware.org/?probe=33d1e6209a) | Apr 30, 2022 |
| Dell          | G3 3500                     | Notebook    | [c9ee387b32](https://linux-hardware.org/?probe=c9ee387b32) | Apr 30, 2022 |
| eMachines     | eME730                      | Notebook    | [ac985950eb](https://linux-hardware.org/?probe=ac985950eb) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [809ea3e76a](https://linux-hardware.org/?probe=809ea3e76a) | Apr 29, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [19f5e16bce](https://linux-hardware.org/?probe=19f5e16bce) | Apr 29, 2022 |
| Lenovo        | ThinkPad T450 20BUS1MN00    | Notebook    | [4e2b073a5c](https://linux-hardware.org/?probe=4e2b073a5c) | Apr 29, 2022 |
| Dell          | G5 5500                     | Notebook    | [c6064853ad](https://linux-hardware.org/?probe=c6064853ad) | Apr 29, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1f6bbce46b](https://linux-hardware.org/?probe=1f6bbce46b) | Apr 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6e00a18a0f](https://linux-hardware.org/?probe=6e00a18a0f) | Apr 28, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [182e82d90e](https://linux-hardware.org/?probe=182e82d90e) | Apr 28, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [59a8e467c6](https://linux-hardware.org/?probe=59a8e467c6) | Apr 28, 2022 |
| Lenovo        | V14 G2 ITL Ua 82KA          | Notebook    | [f191c49754](https://linux-hardware.org/?probe=f191c49754) | Apr 28, 2022 |
| HP            | Notebook                    | Notebook    | [daaa31b65a](https://linux-hardware.org/?probe=daaa31b65a) | Apr 27, 2022 |
| HP            | Notebook                    | Notebook    | [cbac71290e](https://linux-hardware.org/?probe=cbac71290e) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [a696a35961](https://linux-hardware.org/?probe=a696a35961) | Apr 27, 2022 |
| HP            | Notebook                    | Notebook    | [ec93418371](https://linux-hardware.org/?probe=ec93418371) | Apr 26, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [ea3e0b8695](https://linux-hardware.org/?probe=ea3e0b8695) | Apr 26, 2022 |
| Biostar       | J3160NH                     | Desktop     | [8ffd3a1aa4](https://linux-hardware.org/?probe=8ffd3a1aa4) | Apr 26, 2022 |
| MSI           | Z68A-GD80                   | Desktop     | [fedca9082a](https://linux-hardware.org/?probe=fedca9082a) | Apr 25, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [8197ac9c77](https://linux-hardware.org/?probe=8197ac9c77) | Apr 25, 2022 |
| HP            | 348 G4                      | Notebook    | [54db7eb2da](https://linux-hardware.org/?probe=54db7eb2da) | Apr 25, 2022 |
| ASUSTek       | X555LF                      | Notebook    | [0aa3a88c0c](https://linux-hardware.org/?probe=0aa3a88c0c) | Apr 25, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [b4577b2374](https://linux-hardware.org/?probe=b4577b2374) | Apr 25, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [99bd45c11d](https://linux-hardware.org/?probe=99bd45c11d) | Apr 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [45b9330abf](https://linux-hardware.org/?probe=45b9330abf) | Apr 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [36bbd53ec1](https://linux-hardware.org/?probe=36bbd53ec1) | Apr 23, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [4880f7c2d5](https://linux-hardware.org/?probe=4880f7c2d5) | Apr 22, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6d50395aee](https://linux-hardware.org/?probe=6d50395aee) | Apr 22, 2022 |
| Intel         | DH61SA AAG38870-201         | Desktop     | [d8868878ca](https://linux-hardware.org/?probe=d8868878ca) | Apr 22, 2022 |
| Toshiba       | Satellite C850-A786         | Notebook    | [e57aca482e](https://linux-hardware.org/?probe=e57aca482e) | Apr 22, 2022 |
| ECS           | H61H2-MV                    | Desktop     | [939f87564f](https://linux-hardware.org/?probe=939f87564f) | Apr 21, 2022 |
| Unknown       | G41 Series                  | Desktop     | [c6040e6638](https://linux-hardware.org/?probe=c6040e6638) | Apr 21, 2022 |
| HP            | Laptop 15s-du2xxx           | Notebook    | [fe39cbe3d1](https://linux-hardware.org/?probe=fe39cbe3d1) | Apr 20, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [88764ed497](https://linux-hardware.org/?probe=88764ed497) | Apr 20, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [9e2b287533](https://linux-hardware.org/?probe=9e2b287533) | Apr 20, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [6ddb878f3e](https://linux-hardware.org/?probe=6ddb878f3e) | Apr 20, 2022 |
| HP            | Notebook                    | Notebook    | [bec9c06e6e](https://linux-hardware.org/?probe=bec9c06e6e) | Apr 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [53199db8c8](https://linux-hardware.org/?probe=53199db8c8) | Apr 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f3d940677f](https://linux-hardware.org/?probe=f3d940677f) | Apr 19, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [4ec65c693a](https://linux-hardware.org/?probe=4ec65c693a) | Apr 19, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [7d16b45ebd](https://linux-hardware.org/?probe=7d16b45ebd) | Apr 18, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6247b19a2f](https://linux-hardware.org/?probe=6247b19a2f) | Apr 18, 2022 |
| Dell          | Latitude E5520              | Notebook    | [1b428165cf](https://linux-hardware.org/?probe=1b428165cf) | Apr 18, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [b895187681](https://linux-hardware.org/?probe=b895187681) | Apr 17, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [66ef9c9e5f](https://linux-hardware.org/?probe=66ef9c9e5f) | Apr 16, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [ca0b0f6a8a](https://linux-hardware.org/?probe=ca0b0f6a8a) | Apr 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8350598ef6](https://linux-hardware.org/?probe=8350598ef6) | Apr 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [cffdde259f](https://linux-hardware.org/?probe=cffdde259f) | Apr 15, 2022 |
| Timi          | Mi NoteBook 14              | Notebook    | [88abcd9e70](https://linux-hardware.org/?probe=88abcd9e70) | Apr 14, 2022 |
| Gigabyte      | H61MS                       | Desktop     | [84e8094305](https://linux-hardware.org/?probe=84e8094305) | Apr 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [ef76ce862d](https://linux-hardware.org/?probe=ef76ce862d) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [5f85d41ef2](https://linux-hardware.org/?probe=5f85d41ef2) | Apr 14, 2022 |
| ECS           | H81H3-I                     | Desktop     | [1bf6cc284c](https://linux-hardware.org/?probe=1bf6cc284c) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | Notebook    | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [efc9013314](https://linux-hardware.org/?probe=efc9013314) | Apr 13, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [d06a50d75c](https://linux-hardware.org/?probe=d06a50d75c) | Apr 13, 2022 |
| Lenovo        | V14 G2 ITL Ua 82KA          | Notebook    | [b680349236](https://linux-hardware.org/?probe=b680349236) | Apr 12, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [64b8dd4120](https://linux-hardware.org/?probe=64b8dd4120) | Apr 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c7a9564044](https://linux-hardware.org/?probe=c7a9564044) | Apr 12, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [eccb5e26fc](https://linux-hardware.org/?probe=eccb5e26fc) | Apr 12, 2022 |
| Lenovo        | E41-25 81FS                 | Notebook    | [8d0dfa3de3](https://linux-hardware.org/?probe=8d0dfa3de3) | Apr 12, 2022 |
| HP            | Notebook                    | Notebook    | [de9a13770b](https://linux-hardware.org/?probe=de9a13770b) | Apr 11, 2022 |
| Toshiba       | Satellite C50D-A0386        | Notebook    | [31b131cc55](https://linux-hardware.org/?probe=31b131cc55) | Apr 11, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [4e0bcf3318](https://linux-hardware.org/?probe=4e0bcf3318) | Apr 11, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [36e02535fb](https://linux-hardware.org/?probe=36e02535fb) | Apr 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [6feb6018af](https://linux-hardware.org/?probe=6feb6018af) | Apr 10, 2022 |
| HP            | 246                         | Notebook    | [4ef673dd00](https://linux-hardware.org/?probe=4ef673dd00) | Apr 10, 2022 |
| Acer          | One 14 Z2-485               | Notebook    | [57f307fa80](https://linux-hardware.org/?probe=57f307fa80) | Apr 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f76d101440](https://linux-hardware.org/?probe=f76d101440) | Apr 09, 2022 |
| Intel         | DH61SA AAG38870-201         | Desktop     | [516d1a3e43](https://linux-hardware.org/?probe=516d1a3e43) | Apr 08, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [7ec2454548](https://linux-hardware.org/?probe=7ec2454548) | Apr 08, 2022 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a8c92b8a4c](https://linux-hardware.org/?probe=a8c92b8a4c) | Apr 08, 2022 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [21bef916af](https://linux-hardware.org/?probe=21bef916af) | Apr 08, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [94a611644c](https://linux-hardware.org/?probe=94a611644c) | Apr 07, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [e392bf72e9](https://linux-hardware.org/?probe=e392bf72e9) | Apr 07, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [945def6907](https://linux-hardware.org/?probe=945def6907) | Apr 07, 2022 |
| Lenovo        | MAHOBAY                     | All in one  | [787307fc39](https://linux-hardware.org/?probe=787307fc39) | Apr 07, 2022 |
| HP            | Laptop 14q-cy0xxx           | Notebook    | [625bad986e](https://linux-hardware.org/?probe=625bad986e) | Apr 07, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [57c9a10617](https://linux-hardware.org/?probe=57c9a10617) | Apr 07, 2022 |
| ASUSTek       | X542UQR                     | Notebook    | [15c5f13718](https://linux-hardware.org/?probe=15c5f13718) | Apr 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c5c24ea4c2](https://linux-hardware.org/?probe=c5c24ea4c2) | Apr 06, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [5b5118db5d](https://linux-hardware.org/?probe=5b5118db5d) | Apr 06, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [96b467ce52](https://linux-hardware.org/?probe=96b467ce52) | Apr 05, 2022 |
| Dell          | Vostro 3578                 | Notebook    | [8e2637c774](https://linux-hardware.org/?probe=8e2637c774) | Apr 05, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [bc017137e8](https://linux-hardware.org/?probe=bc017137e8) | Apr 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | Notebook    | [1d3cd04256](https://linux-hardware.org/?probe=1d3cd04256) | Apr 04, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [bd5be9b918](https://linux-hardware.org/?probe=bd5be9b918) | Apr 04, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [3e8d03d8d6](https://linux-hardware.org/?probe=3e8d03d8d6) | Apr 03, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [982bcd3a5b](https://linux-hardware.org/?probe=982bcd3a5b) | Apr 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [ba24b37041](https://linux-hardware.org/?probe=ba24b37041) | Apr 03, 2022 |
| Lenovo        | Erazer Y50-70               | Notebook    | [36d3d65801](https://linux-hardware.org/?probe=36d3d65801) | Apr 03, 2022 |
| HP            | Laptop 15s-dr1xxx           | Notebook    | [86ca12c772](https://linux-hardware.org/?probe=86ca12c772) | Apr 03, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [57a0d73ab9](https://linux-hardware.org/?probe=57a0d73ab9) | Apr 02, 2022 |
| HP            | Notebook                    | Notebook    | [f46a05a044](https://linux-hardware.org/?probe=f46a05a044) | Apr 02, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [3bc3694efb](https://linux-hardware.org/?probe=3bc3694efb) | Apr 02, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [d103b2cb25](https://linux-hardware.org/?probe=d103b2cb25) | Apr 02, 2022 |
| Dell          | Inspiron 7386               | Convertible | [0052645485](https://linux-hardware.org/?probe=0052645485) | Apr 02, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [63f818dc19](https://linux-hardware.org/?probe=63f818dc19) | Apr 02, 2022 |
| Intel         | H61                         | Desktop     | [47b28b972b](https://linux-hardware.org/?probe=47b28b972b) | Apr 01, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [a1fc5c114a](https://linux-hardware.org/?probe=a1fc5c114a) | Apr 01, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [d2e5eda16f](https://linux-hardware.org/?probe=d2e5eda16f) | Apr 01, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [3acec795a6](https://linux-hardware.org/?probe=3acec795a6) | Apr 01, 2022 |
| Dell          | G5 5500                     | Notebook    | [56b5d0d490](https://linux-hardware.org/?probe=56b5d0d490) | Apr 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [87dfbaa9e8](https://linux-hardware.org/?probe=87dfbaa9e8) | Apr 01, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [36563f3934](https://linux-hardware.org/?probe=36563f3934) | Apr 01, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a4d2271eaa](https://linux-hardware.org/?probe=a4d2271eaa) | Mar 31, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [946628cb20](https://linux-hardware.org/?probe=946628cb20) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | Notebook    | [85f1411d0e](https://linux-hardware.org/?probe=85f1411d0e) | Mar 30, 2022 |
| Lenovo        | Legion 5 15ITH6 82JK        | Notebook    | [f8edce28d5](https://linux-hardware.org/?probe=f8edce28d5) | Mar 30, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Dell          | 0Y2YM6 A01                  | Desktop     | [4578be5a1e](https://linux-hardware.org/?probe=4578be5a1e) | Mar 30, 2022 |
| Dell          | Latitude E6420              | Notebook    | [411b1a3a51](https://linux-hardware.org/?probe=411b1a3a51) | Mar 30, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [fcbd3df931](https://linux-hardware.org/?probe=fcbd3df931) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| Dell          | Studio 1450                 | Notebook    | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| HP            | Pavilion dv3                | Notebook    | [bd8d09108e](https://linux-hardware.org/?probe=bd8d09108e) | Mar 28, 2022 |
| HP            | 18E7                        | Desktop     | [5dc3eea8b5](https://linux-hardware.org/?probe=5dc3eea8b5) | Mar 28, 2022 |
| Unknown       | G41 Series                  | Desktop     | [4dbde5e06f](https://linux-hardware.org/?probe=4dbde5e06f) | Mar 28, 2022 |
| HP            | Pavilion g4                 | Notebook    | [893eaf3bca](https://linux-hardware.org/?probe=893eaf3bca) | Mar 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d5e927b59e](https://linux-hardware.org/?probe=d5e927b59e) | Mar 26, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | Notebook    | [2465ab5a58](https://linux-hardware.org/?probe=2465ab5a58) | Mar 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e09438b057](https://linux-hardware.org/?probe=e09438b057) | Mar 26, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [11abcc854d](https://linux-hardware.org/?probe=11abcc854d) | Mar 25, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [870e407665](https://linux-hardware.org/?probe=870e407665) | Mar 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4ba4683a05](https://linux-hardware.org/?probe=4ba4683a05) | Mar 24, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [f06216a521](https://linux-hardware.org/?probe=f06216a521) | Mar 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8533e3cf0d](https://linux-hardware.org/?probe=8533e3cf0d) | Mar 23, 2022 |
| Lenovo        | ThinkPad L490 20Q5S0M600    | Notebook    | [1f816ed931](https://linux-hardware.org/?probe=1f816ed931) | Mar 23, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [a6718f483b](https://linux-hardware.org/?probe=a6718f483b) | Mar 22, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [2d8ab46eed](https://linux-hardware.org/?probe=2d8ab46eed) | Mar 21, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [b1bdc8c7d4](https://linux-hardware.org/?probe=b1bdc8c7d4) | Mar 21, 2022 |
| Lenovo        | ThinkPad X230 23251Q0       | Notebook    | [0a705ba05c](https://linux-hardware.org/?probe=0a705ba05c) | Mar 21, 2022 |
| Dell          | Latitude 3400               | Notebook    | [031b95db58](https://linux-hardware.org/?probe=031b95db58) | Mar 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [0e4992c717](https://linux-hardware.org/?probe=0e4992c717) | Mar 20, 2022 |
| HP            | Pavilion 14                 | Notebook    | [537e877606](https://linux-hardware.org/?probe=537e877606) | Mar 20, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [66de21a937](https://linux-hardware.org/?probe=66de21a937) | Mar 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [01bd3bd062](https://linux-hardware.org/?probe=01bd3bd062) | Mar 19, 2022 |
| HP            | Pavilion dv3                | Notebook    | [3dbd970796](https://linux-hardware.org/?probe=3dbd970796) | Mar 19, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [2b30c1219e](https://linux-hardware.org/?probe=2b30c1219e) | Mar 18, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [221de9592b](https://linux-hardware.org/?probe=221de9592b) | Mar 16, 2022 |
| Dell          | Latitude E7450              | Notebook    | [107065a152](https://linux-hardware.org/?probe=107065a152) | Mar 15, 2022 |
| ASUSTek       | VivoBook S14 X430UA         | Notebook    | [9a04e16d4a](https://linux-hardware.org/?probe=9a04e16d4a) | Mar 15, 2022 |
| Lenovo        | Erazer Y50-70               | Notebook    | [ae9a6ee7cb](https://linux-hardware.org/?probe=ae9a6ee7cb) | Mar 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [71dc914b7b](https://linux-hardware.org/?probe=71dc914b7b) | Mar 14, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3af6b6632d](https://linux-hardware.org/?probe=3af6b6632d) | Mar 14, 2022 |
| Dell          | G5 5500                     | Notebook    | [12a4380cad](https://linux-hardware.org/?probe=12a4380cad) | Mar 14, 2022 |
| Intel         | G31                         | Desktop     | [02eaa5ef51](https://linux-hardware.org/?probe=02eaa5ef51) | Mar 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [89d17b56d6](https://linux-hardware.org/?probe=89d17b56d6) | Mar 14, 2022 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [737a2d4c61](https://linux-hardware.org/?probe=737a2d4c61) | Mar 14, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [8f4386fdc5](https://linux-hardware.org/?probe=8f4386fdc5) | Mar 14, 2022 |
| Intel         | DH61WW AAG23116-302         | Desktop     | [20682db2fa](https://linux-hardware.org/?probe=20682db2fa) | Mar 14, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [0a16c273a4](https://linux-hardware.org/?probe=0a16c273a4) | Mar 13, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [218c306874](https://linux-hardware.org/?probe=218c306874) | Mar 13, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [f7fe5893d5](https://linux-hardware.org/?probe=f7fe5893d5) | Mar 13, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [11bd4e97e6](https://linux-hardware.org/?probe=11bd4e97e6) | Mar 13, 2022 |
| Intel         | H61                         | Desktop     | [8efa81cf12](https://linux-hardware.org/?probe=8efa81cf12) | Mar 12, 2022 |
| ASRock        | H61M-S1 PLUS                | Desktop     | [56c15fcbf6](https://linux-hardware.org/?probe=56c15fcbf6) | Mar 12, 2022 |
| Alienware     | 13 R3                       | Notebook    | [a8b07f9c17](https://linux-hardware.org/?probe=a8b07f9c17) | Mar 12, 2022 |
| Dell          | Latitude E5410              | Notebook    | [8015e22264](https://linux-hardware.org/?probe=8015e22264) | Mar 12, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [cb2918a35e](https://linux-hardware.org/?probe=cb2918a35e) | Mar 12, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [508f6f6c0c](https://linux-hardware.org/?probe=508f6f6c0c) | Mar 11, 2022 |
| IBM           | 4367 SVT                    | Server      | [3d7400ea9b](https://linux-hardware.org/?probe=3d7400ea9b) | Mar 11, 2022 |
| Gigabyte      | B660M AORUS PRO AX DDR4     | Desktop     | [59405132c9](https://linux-hardware.org/?probe=59405132c9) | Mar 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/India/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 888       | 22.74%  |
| Ubuntu 18.04                 | 409       | 10.47%  |
| Ubuntu 22.04                 | 153       | 3.92%   |
| Arch                         | 104       | 2.66%   |
| KDE neon 20.04               | 84        | 2.15%   |
| OpenMandriva 4.3             | 73        | 1.87%   |
| Arch Rolling                 | 70        | 1.79%   |
| Pop!_OS 20.04                | 67        | 1.72%   |
| Fedora 36                    | 67        | 1.72%   |
| Zorin 16                     | 63        | 1.61%   |
| Pop!_OS 21.04                | 59        | 1.51%   |
| Ubuntu 20.10                 | 58        | 1.49%   |
| Fedora 34                    | 58        | 1.49%   |
| OpenMandriva 4.2             | 56        | 1.43%   |
| Zorin 15                     | 55        | 1.41%   |
| Ubuntu 21.04                 | 53        | 1.36%   |
| Ubuntu 19.10                 | 51        | 1.31%   |
| ArcoLinux Rolling            | 50        | 1.28%   |
| Pop!_OS 22.04                | 46        | 1.18%   |
| Ubuntu 21.10                 | 45        | 1.15%   |
| Ubuntu 19.04                 | 45        | 1.15%   |
| Pop!_OS 20.10                | 44        | 1.13%   |
| Manjaro                      | 44        | 1.13%   |
| Fedora 35                    | 40        | 1.02%   |
| Fedora 32                    | 39        | 1%      |
| Ubuntu Unity 16.04           | 34        | 0.87%   |
| Linux Mint 20                | 34        | 0.87%   |
| Fedora 33                    | 34        | 0.87%   |
| Ubuntu 16.04                 | 32        | 0.82%   |
| Linux Mint 20.2              | 32        | 0.82%   |
| Linux Mint 20.3              | 31        | 0.79%   |
| Linux Mint 20.1              | 30        | 0.77%   |
| Debian 10                    | 28        | 0.72%   |
| Debian 11                    | 27        | 0.69%   |
| Kubuntu 20.04                | 24        | 0.61%   |
| openSUSE Tumbleweed-XXXXXXXX | 22        | 0.56%   |
| Linux Mint 19.3              | 22        | 0.56%   |
| Elementary 6.1               | 21        | 0.54%   |
| Pop!_OS 21.10                | 20        | 0.51%   |
| Fedora 37                    | 20        | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1713      | 45.4%   |
| Fedora        | 263       | 6.97%   |
| Pop!_OS       | 229       | 6.07%   |
| Arch          | 167       | 4.43%   |
| Linux Mint    | 160       | 4.24%   |
| OpenMandriva  | 143       | 3.79%   |
| Zorin         | 118       | 3.13%   |
| Manjaro       | 109       | 2.89%   |
| KDE neon      | 99        | 2.62%   |
| Debian        | 75        | 1.99%   |
| Kali          | 61        | 1.62%   |
| Ubuntu Unity  | 57        | 1.51%   |
| Kubuntu       | 56        | 1.48%   |
| ArcoLinux     | 56        | 1.48%   |
| Elementary    | 51        | 1.35%   |
| Endless       | 50        | 1.33%   |
| Xubuntu       | 31        | 0.82%   |
| openSUSE      | 27        | 0.72%   |
| CentOS        | 26        | 0.69%   |
| ROSA          | 22        | 0.58%   |
| Clear Linux   | 21        | 0.56%   |
| RHEL          | 20        | 0.53%   |
| Garuda Linux  | 20        | 0.53%   |
| EndeavourOS   | 18        | 0.48%   |
| Ubuntu MATE   | 13        | 0.34%   |
| Ubuntu Budgie | 13        | 0.34%   |
| MX            | 12        | 0.32%   |
| Lubuntu       | 12        | 0.32%   |
| Parrot        | 10        | 0.27%   |
| Xero          | 9         | 0.24%   |
| Void Linux    | 9         | 0.24%   |
| Solus         | 9         | 0.24%   |
| Gentoo        | 9         | 0.24%   |
| Peppermint    | 7         | 0.19%   |
| BlackPanther  | 6         | 0.16%   |
| Artix         | 6         | 0.16%   |
| LMDE          | 5         | 0.13%   |
| Slackware     | 4         | 0.11%   |
| Nobara        | 4         | 0.11%   |
| LinuxFX       | 4         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 152       | 3.63%   |
| 5.16.7-desktop-1omv4003  | 71        | 1.7%    |
| 5.4.0-40-generic         | 61        | 1.46%   |
| 5.10.14-desktop-1omv4002 | 56        | 1.34%   |
| 5.4.0-48-generic         | 47        | 1.12%   |
| 5.4.0-58-generic         | 43        | 1.03%   |
| 5.4.0-52-generic         | 40        | 0.96%   |
| 5.4.0-26-generic         | 40        | 0.96%   |
| 5.4.0-47-generic         | 39        | 0.93%   |
| 5.11.0-27-generic        | 39        | 0.93%   |
| 5.11.0-25-generic        | 35        | 0.84%   |
| 5.11.0-7620-generic      | 34        | 0.81%   |
| 5.4.0-29-generic         | 33        | 0.79%   |
| 5.15.0-46-generic        | 31        | 0.74%   |
| 5.15.0-52-generic        | 30        | 0.72%   |
| 5.8.0-48-generic         | 29        | 0.69%   |
| 5.3.0-28-generic         | 29        | 0.69%   |
| 5.11.0-40-generic        | 29        | 0.69%   |
| 5.8.0-53-generic         | 28        | 0.67%   |
| 5.8.0-55-generic         | 27        | 0.64%   |
| 5.8.0-43-generic         | 27        | 0.64%   |
| 5.4.0-37-generic         | 27        | 0.64%   |
| 5.11.0-43-generic        | 26        | 0.62%   |
| 5.11.0-38-generic        | 26        | 0.62%   |
| 5.11.0-37-generic        | 26        | 0.62%   |
| 5.0.0-37-generic         | 25        | 0.6%    |
| 5.8.0-59-generic         | 24        | 0.57%   |
| 5.8.0-44-generic         | 24        | 0.57%   |
| 5.4.0-74-generic         | 24        | 0.57%   |
| 5.3.0-40-generic         | 24        | 0.57%   |
| 5.13.0-30-generic        | 24        | 0.57%   |
| 4.15.0-45-generic        | 24        | 0.57%   |
| 5.4.0-45-generic         | 23        | 0.55%   |
| 5.3.0-51-generic         | 23        | 0.55%   |
| 5.15.0-48-generic        | 22        | 0.53%   |
| 5.0.0-23-generic         | 22        | 0.53%   |
| 5.8.0-7630-generic       | 21        | 0.5%    |
| 5.8.0-50-generic         | 21        | 0.5%    |
| 5.4.0-39-generic         | 21        | 0.5%    |
| 5.13.0-40-generic        | 21        | 0.5%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 860       | 21.49%  |
| 5.11.0  | 332       | 8.3%    |
| 5.8.0   | 310       | 7.75%   |
| 4.15.0  | 236       | 5.9%    |
| 5.15.0  | 221       | 5.52%   |
| 5.13.0  | 202       | 5.05%   |
| 5.3.0   | 192       | 4.8%    |
| 5.0.0   | 130       | 3.25%   |
| 4.18.0  | 102       | 2.55%   |
| 5.16.7  | 73        | 1.82%   |
| 5.10.0  | 62        | 1.55%   |
| 5.10.14 | 56        | 1.4%    |
| 4.19.0  | 30        | 0.75%   |
| 5.14.0  | 26        | 0.65%   |
| 4.4.0   | 25        | 0.62%   |
| 5.19.0  | 24        | 0.6%    |
| 5.17.5  | 22        | 0.55%   |
| 5.7.0   | 14        | 0.35%   |
| 6.0.8   | 13        | 0.32%   |
| 5.9.0   | 12        | 0.3%    |
| 5.18.0  | 12        | 0.3%    |
| 5.15.11 | 12        | 0.3%    |
| 5.17.9  | 11        | 0.27%   |
| 5.16.11 | 10        | 0.25%   |
| 5.13.12 | 10        | 0.25%   |
| 3.10.0  | 10        | 0.25%   |
| 6.0.9   | 9         | 0.22%   |
| 5.6.6   | 9         | 0.22%   |
| 5.16.0  | 9         | 0.22%   |
| 5.15.8  | 9         | 0.22%   |
| 5.15.5  | 9         | 0.22%   |
| 5.13.9  | 9         | 0.22%   |
| 6.0.6   | 8         | 0.2%    |
| 5.9.16  | 8         | 0.2%    |
| 5.6.0   | 8         | 0.2%    |
| 5.5.0   | 8         | 0.2%    |
| 5.18.6  | 8         | 0.2%    |
| 5.18.5  | 8         | 0.2%    |
| 5.17.4  | 8         | 0.2%    |
| 5.13.19 | 8         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 900       | 22.71%  |
| 5.8     | 370       | 9.34%   |
| 5.11    | 370       | 9.34%   |
| 5.15    | 340       | 8.58%   |
| 5.13    | 256       | 6.46%   |
| 4.15    | 239       | 6.03%   |
| 5.3     | 218       | 5.5%    |
| 5.10    | 189       | 4.77%   |
| 5.16    | 134       | 3.38%   |
| 5.0     | 133       | 3.36%   |
| 4.18    | 108       | 2.73%   |
| 5.17    | 82        | 2.07%   |
| 5.14    | 78        | 1.97%   |
| 5.19    | 76        | 1.92%   |
| 5.18    | 69        | 1.74%   |
| 5.12    | 55        | 1.39%   |
| 5.9     | 51        | 1.29%   |
| 6.0     | 50        | 1.26%   |
| 5.7     | 49        | 1.24%   |
| 4.19    | 42        | 1.06%   |
| 5.6     | 41        | 1.03%   |
| 4.4     | 28        | 0.71%   |
| 5.5     | 26        | 0.66%   |
| 4.9     | 16        | 0.4%    |
| 3.10    | 10        | 0.25%   |
| 5.2     | 8         | 0.2%    |
| 4.13    | 5         | 0.13%   |
| 5.1     | 4         | 0.1%    |
| 4.20    | 3         | 0.08%   |
| 3.16    | 3         | 0.08%   |
| 4.14    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 5       | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.16    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 4.10    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3566      | 97.73%  |
| i686    | 65        | 1.78%   |
| aarch64 | 12        | 0.33%   |
| armv7l  | 6         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 2148      | 56.74%  |
| Unknown           | 465       | 12.28%  |
| KDE5              | 419       | 11.07%  |
| XFCE              | 171       | 4.52%   |
| X-Cinnamon        | 124       | 3.28%   |
| KDE               | 105       | 2.77%   |
| Unity             | 59        | 1.56%   |
| Pantheon          | 49        | 1.29%   |
| MATE              | 44        | 1.16%   |
| Cinnamon          | 34        | 0.9%    |
| GNOME Flashback   | 24        | 0.63%   |
| Budgie            | 21        | 0.55%   |
| i3                | 18        | 0.48%   |
| LXDE              | 15        | 0.4%    |
| Deepin            | 13        | 0.34%   |
| LXQt              | 11        | 0.29%   |
| KDE4              | 10        | 0.26%   |
| awesome           | 9         | 0.24%   |
| GNOME Classic     | 8         | 0.21%   |
| bspwm             | 8         | 0.21%   |
| Sway              | 6         | 0.16%   |
| qtile             | 5         | 0.13%   |
| openbox           | 5         | 0.13%   |
| LeftWM            | 4         | 0.11%   |
| xmonad            | 3         | 0.08%   |
| dwm               | 2         | 0.05%   |
| Yaru:ubuntu:GNOME | 1         | 0.03%   |
| lightdm-xsession  | 1         | 0.03%   |
| i3-with-shmlog    | 1         | 0.03%   |
| i3-gaps           | 1         | 0.03%   |
| Hyprland          | 1         | 0.03%   |
| Enlightenment     | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2848      | 76.07%  |
| Wayland | 568       | 15.17%  |
| Unknown | 282       | 7.53%   |
| Tty     | 46        | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2031      | 53.97%  |
| GDM     | 670       | 17.8%   |
| SDDM    | 392       | 10.42%  |
| GDM3    | 315       | 8.37%   |
| LightDM | 229       | 6.09%   |
| TDM     | 105       | 2.79%   |
| KDM     | 9         | 0.24%   |
| XDM     | 4         | 0.11%   |
| Ly      | 3         | 0.08%   |
| LXDM    | 3         | 0.08%   |
| SLiM    | 2         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_IN   | 2261      | 60.02%  |
| en_US   | 970       | 25.75%  |
| Unknown | 373       | 9.9%    |
| en_GB   | 68        | 1.81%   |
| C       | 65        | 1.73%   |
| en_AG   | 7         | 0.19%   |
| en_CA   | 3         | 0.08%   |
| zh_TW   | 2         | 0.05%   |
| POSIX   | 2         | 0.05%   |
| mr_IN   | 2         | 0.05%   |
| mni_IN  | 2         | 0.05%   |
| en_IE   | 2         | 0.05%   |
| en_AU   | 2         | 0.05%   |
| sa_IN   | 1         | 0.03%   |
| ks_IN   | 1         | 0.03%   |
| es_ES   | 1         | 0.03%   |
| en_SG   | 1         | 0.03%   |
| en_BW   | 1         | 0.03%   |
| de_DE   | 1         | 0.03%   |
| Default | 1         | 0.03%   |
| C.UTF8  | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2131      | 57.47%  |
| BIOS | 1577      | 42.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 3064      | 82.63%  |
| Btrfs   | 301       | 8.12%   |
| Overlay | 165       | 4.45%   |
| Unknown | 78        | 2.1%    |
| Xfs     | 62        | 1.67%   |
| Zfs     | 13        | 0.35%   |
| Ext2    | 12        | 0.32%   |
| Ext3    | 7         | 0.19%   |
| F2fs    | 3         | 0.08%   |
| Tmpfs   | 1         | 0.03%   |
| Jfs     | 1         | 0.03%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2173      | 58.57%  |
| GPT     | 1264      | 34.07%  |
| MBR     | 273       | 7.36%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3222      | 86.94%  |
| Yes       | 484       | 13.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2237      | 60.39%  |
| Yes       | 1467      | 39.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Lenovo                   | 718       | 19.69%  |
| Hewlett-Packard          | 709       | 19.44%  |
| Dell                     | 691       | 18.95%  |
| ASUSTek Computer         | 460       | 12.61%  |
| Acer                     | 233       | 6.39%   |
| Gigabyte Technology      | 223       | 6.11%   |
| Intel                    | 114       | 3.13%   |
| MSI                      | 110       | 3.02%   |
| Unknown                  | 56        | 1.54%   |
| Sony                     | 48        | 1.32%   |
| Toshiba                  | 33        | 0.9%    |
| ASRock                   | 26        | 0.71%   |
| Samsung Electronics      | 24        | 0.66%   |
| Apple                    | 23        | 0.63%   |
| AVITA                    | 19        | 0.52%   |
| OEM                      | 13        | 0.36%   |
| Timi                     | 11        | 0.3%    |
| ECS                      | 11        | 0.3%    |
| Biostar                  | 11        | 0.3%    |
| Raspberry Pi Foundation  | 9         | 0.25%   |
| HCL Infosystems Limited  | 7         | 0.19%   |
| Fujitsu                  | 7         | 0.19%   |
| AMI                      | 7         | 0.19%   |
| HUAWEI                   | 6         | 0.16%   |
| Google                   | 6         | 0.16%   |
| Foxconn                  | 6         | 0.16%   |
| LG Electronics           | 5         | 0.14%   |
| Radxa                    | 4         | 0.11%   |
| eMachines                | 4         | 0.11%   |
| Alienware                | 4         | 0.11%   |
| WIPRO                    | 3         | 0.08%   |
| realme                   | 3         | 0.08%   |
| Pegatron                 | 3         | 0.08%   |
| LORD ELECTRONICS         | 3         | 0.08%   |
| Supermicro               | 2         | 0.05%   |
| Razer                    | 2         | 0.05%   |
| Micromax                 | 2         | 0.05%   |
| Insyde                   | 2         | 0.05%   |
| Gateway                  | 2         | 0.05%   |
| Coconics Private Limited | 2         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 79        | 2.17%   |
| HP Notebook                            | 71        | 1.95%   |
| HP 15                                  | 27        | 0.74%   |
| HP Pavilion 15                         | 26        | 0.71%   |
| Dell Inspiron 3542                     | 25        | 0.69%   |
| HP Pavilion g6                         | 23        | 0.63%   |
| Gigabyte H410M H V3                    | 23        | 0.63%   |
| Dell Inspiron 15-3567                  | 22        | 0.6%    |
| HP Laptop 15-bs0xx                     | 21        | 0.58%   |
| Dell Inspiron 5570                     | 20        | 0.55%   |
| Lenovo IdeaPad 330-15IKB 81DE          | 17        | 0.47%   |
| Lenovo E41-25 81FS                     | 17        | 0.47%   |
| Dell Inspiron 3521                     | 17        | 0.47%   |
| HP Pavilion Notebook                   | 16        | 0.44%   |
| Acer Aspire A715-75G                   | 16        | 0.44%   |
| Dell Vostro 3480                       | 14        | 0.38%   |
| ASUS TUF Gaming FX505DT_FX505DT        | 14        | 0.38%   |
| Lenovo G50-80 80E5                     | 13        | 0.36%   |
| Intel H61                              | 13        | 0.36%   |
| Gigabyte H61MS                         | 13        | 0.36%   |
| Gigabyte H81M-S                        | 12        | 0.33%   |
| Dell Vostro 3578                       | 12        | 0.33%   |
| Dell Vostro 15-3568                    | 12        | 0.33%   |
| ASUS X510UNR                           | 12        | 0.33%   |
| Lenovo G50-45 80E3                     | 11        | 0.3%    |
| HP Laptop 15-da0xxx                    | 11        | 0.3%    |
| HP Laptop 15-bw0xx                     | 11        | 0.3%    |
| Dell Inspiron 5559                     | 11        | 0.3%    |
| Intel HCL Desktop                      | 10        | 0.27%   |
| HP Pavilion x360 Convertible 14-dh1xxx | 10        | 0.27%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 10        | 0.27%   |
| HP Pavilion dv6                        | 10        | 0.27%   |
| Gigabyte H110M-S2                      | 10        | 0.27%   |
| Dell Vostro 3478                       | 10        | 0.27%   |
| ASUS X556UQK                           | 10        | 0.27%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR   | 10        | 0.27%   |
| ASUS All Series                        | 10        | 0.27%   |
| Lenovo ThinkBook 14-IML 20RV           | 9         | 0.25%   |
| Lenovo IdeaPad S540-15IWL D 81NE       | 9         | 0.25%   |
| Lenovo IdeaPad 520-15IKB 81BF          | 9         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 312       | 8.55%   |
| Lenovo IdeaPad     | 236       | 6.47%   |
| Lenovo ThinkPad    | 223       | 6.11%   |
| HP Pavilion        | 196       | 5.37%   |
| HP Laptop          | 138       | 3.78%   |
| Dell Vostro        | 129       | 3.54%   |
| ASUS VivoBook      | 128       | 3.51%   |
| Dell Latitude      | 127       | 3.48%   |
| Acer Aspire        | 121       | 3.32%   |
| Unknown            | 79        | 2.17%   |
| HP Notebook        | 72        | 1.97%   |
| HP EliteBook       | 51        | 1.4%    |
| ASUS TUF           | 48        | 1.32%   |
| HP ProBook         | 42        | 1.15%   |
| Dell OptiPlex      | 42        | 1.15%   |
| ASUS ROG           | 40        | 1.1%    |
| ASUS ASUS          | 34        | 0.93%   |
| ASUS PRIME         | 30        | 0.82%   |
| Acer Nitro         | 29        | 0.8%    |
| Toshiba Satellite  | 28        | 0.77%   |
| HP 15              | 28        | 0.77%   |
| Dell XPS           | 28        | 0.77%   |
| Gigabyte H410M     | 27        | 0.74%   |
| Lenovo Legion      | 26        | 0.71%   |
| Acer Swift         | 24        | 0.66%   |
| Lenovo ThinkBook   | 21        | 0.58%   |
| HP ENVY            | 21        | 0.58%   |
| HP Compaq          | 21        | 0.58%   |
| Dell Precision     | 21        | 0.58%   |
| Lenovo ThinkCentre | 17        | 0.47%   |
| Lenovo E41-25      | 17        | 0.47%   |
| Acer Veriton       | 16        | 0.44%   |
| Lenovo IdeaPadFlex | 15        | 0.41%   |
| Acer Predator      | 15        | 0.41%   |
| HP OMEN            | 14        | 0.38%   |
| Gigabyte H310M     | 14        | 0.38%   |
| Lenovo Yoga        | 13        | 0.36%   |
| Lenovo G50-80      | 13        | 0.36%   |
| Intel H61          | 13        | 0.36%   |
| Gigabyte H61MS     | 13        | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 514       | 14.09%  |
| 2019    | 499       | 13.68%  |
| 2020    | 379       | 10.39%  |
| 2017    | 327       | 8.97%   |
| 2021    | 271       | 7.43%   |
| 2016    | 239       | 6.55%   |
| 2012    | 226       | 6.2%    |
| 2013    | 224       | 6.14%   |
| 2014    | 221       | 6.06%   |
| 2011    | 208       | 5.7%    |
| 2015    | 172       | 4.72%   |
| 2010    | 155       | 4.25%   |
| 2008    | 67        | 1.84%   |
| 2009    | 59        | 1.62%   |
| 2022    | 35        | 0.96%   |
| 2007    | 23        | 0.63%   |
| Unknown | 16        | 0.44%   |
| 2006    | 8         | 0.22%   |
| 2005    | 3         | 0.08%   |
| 2003    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2649      | 72.64%  |
| Desktop        | 821       | 22.51%  |
| Convertible    | 90        | 2.47%   |
| All in one     | 26        | 0.71%   |
| Mini pc        | 25        | 0.69%   |
| System on chip | 17        | 0.47%   |
| Server         | 10        | 0.27%   |
| Tablet         | 9         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3226      | 87.76%  |
| Enabled  | 450       | 12.24%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3637      | 99.73%  |
| Yes  | 10        | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1163      | 31.53%  |
| 3.01-4.0    | 912       | 24.73%  |
| 8.01-16.0   | 692       | 18.76%  |
| 16.01-24.0  | 553       | 14.99%  |
| 1.01-2.0    | 146       | 3.96%   |
| 32.01-64.0  | 122       | 3.31%   |
| 2.01-3.0    | 38        | 1.03%   |
| 64.01-256.0 | 24        | 0.65%   |
| 24.01-32.0  | 20        | 0.54%   |
| 0.51-1.0    | 16        | 0.43%   |
| 0.01-0.5    | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1342      | 33.82%  |
| 2.01-3.0   | 1257      | 31.68%  |
| 3.01-4.0   | 541       | 13.63%  |
| 4.01-8.0   | 535       | 13.48%  |
| 0.51-1.0   | 148       | 3.73%   |
| 8.01-16.0  | 101       | 2.55%   |
| 0.01-0.5   | 31        | 0.78%   |
| 16.01-24.0 | 9         | 0.23%   |
| 32.01-64.0 | 2         | 0.05%   |
| 24.01-32.0 | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2624      | 71.01%  |
| 2      | 873       | 23.63%  |
| 3      | 117       | 3.17%   |
| 0      | 30        | 0.81%   |
| 4      | 29        | 0.78%   |
| 5      | 11        | 0.3%    |
| 6      | 7         | 0.19%   |
| 7      | 2         | 0.05%   |
| 9      | 1         | 0.03%   |
| 8      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2349      | 64.02%  |
| Yes       | 1320      | 35.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3055      | 83.63%  |
| No        | 598       | 16.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3185      | 86.93%  |
| No        | 479       | 13.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2663      | 72.29%  |
| No        | 1021      | 27.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| India   | 3647      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Bengaluru     | 451       | 11.65%  |
| Mumbai        | 265       | 6.85%   |
| Chennai       | 250       | 6.46%   |
| Hyderabad     | 211       | 5.45%   |
| Pune          | 184       | 4.75%   |
| New Delhi     | 175       | 4.52%   |
| Kolkata       | 167       | 4.31%   |
| Delhi         | 146       | 3.77%   |
| Ahmedabad     | 85        | 2.2%    |
| Ernakulam     | 79        | 2.04%   |
| Patna         | 70        | 1.81%   |
| Lucknow       | 70        | 1.81%   |
| Jaipur        | 63        | 1.63%   |
| Gurgaon       | 56        | 1.45%   |
| Bhopal        | 49        | 1.27%   |
| Navi Mumbai   | 47        | 1.21%   |
| Indore        | 47        | 1.21%   |
| Coimbatore    | 45        | 1.16%   |
| Trivandrum    | 40        | 1.03%   |
| Surat         | 39        | 1.01%   |
| Thrissur      | 38        | 0.98%   |
| Malappuram    | 33        | 0.85%   |
| Guwahati      | 32        | 0.83%   |
| Ludhiana      | 29        | 0.75%   |
| Nagpur        | 27        | 0.7%    |
| Bhubaneswar   | 27        | 0.7%    |
| Kochi         | 25        | 0.65%   |
| Noida         | 24        | 0.62%   |
| Gonikoppal    | 22        | 0.57%   |
| Vadodara      | 20        | 0.52%   |
| Vijayawada    | 19        | 0.49%   |
| Thane         | 19        | 0.49%   |
| Kanpur        | 19        | 0.49%   |
| Ghaziabad     | 18        | 0.46%   |
| Visakhapatnam | 17        | 0.44%   |
| Mangalore     | 16        | 0.41%   |
| Mohali        | 15        | 0.39%   |
| Kozhikode     | 15        | 0.39%   |
| Raipur        | 14        | 0.36%   |
| Puducherry    | 14        | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1040      | 1348   | 22.6%   |
| WDC                       | 897       | 1129   | 19.49%  |
| Toshiba                   | 486       | 549    | 10.56%  |
| Samsung Electronics       | 420       | 541    | 9.13%   |
| Kingston                  | 184       | 221    | 4%      |
| SanDisk                   | 180       | 223    | 3.91%   |
| Crucial                   | 165       | 210    | 3.59%   |
| HGST                      | 160       | 185    | 3.48%   |
| SK hynix                  | 151       | 168    | 3.28%   |
| Intel                     | 148       | 197    | 3.22%   |
| Unknown                   | 105       | 132    | 2.28%   |
| Hitachi                   | 102       | 122    | 2.22%   |
| Micron Technology         | 87        | 102    | 1.89%   |
| A-DATA Technology         | 65        | 71     | 1.41%   |
| KIOXIA                    | 52        | 64     | 1.13%   |
| China                     | 25        | 29     | 0.54%   |
| Gigabyte Technology       | 21        | 24     | 0.46%   |
| Unknown                   | 18        | 19     | 0.39%   |
| Phison                    | 16        | 19     | 0.35%   |
| Micron/Crucial Technology | 16        | 18     | 0.35%   |
| Hewlett-Packard           | 16        | 22     | 0.35%   |
| UMIS                      | 15        | 17     | 0.33%   |
| Silicon Motion            | 15        | 17     | 0.33%   |
| LITEON                    | 15        | 17     | 0.33%   |
| Apple                     | 14        | 18     | 0.3%    |
| FORESEE                   | 13        | 14     | 0.28%   |
| Maxtor                    | 10        | 23     | 0.22%   |
| SPCC                      | 9         | 13     | 0.2%    |
| Fujitsu                   | 8         | 8      | 0.17%   |
| TO Exter                  | 7         | 7      | 0.15%   |
| Realtek Semiconductor     | 7         | 8      | 0.15%   |
| XPG                       | 6         | 7      | 0.13%   |
| Transcend                 | 6         | 7      | 0.13%   |
| Union Memory              | 5         | 6      | 0.11%   |
| Lexar                     | 5         | 5      | 0.11%   |
| HS-SSD-C100               | 5         | 7      | 0.11%   |
| Union Memory (Shenzhen)   | 4         | 4      | 0.09%   |
| PNY                       | 4         | 6      | 0.09%   |
| Leven                     | 4         | 4      | 0.09%   |
| Lenovo                    | 4         | 6      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB         | 256       | 5.3%    |
| Toshiba MQ04ABF100 1TB                 | 130       | 2.69%   |
| Toshiba MQ01ABD100 1TB                 | 102       | 2.11%   |
| Seagate ST1000DM010-2EP102 1TB         | 76        | 1.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 60        | 1.24%   |
| Seagate ST500LT012-1DG142 500GB        | 59        | 1.22%   |
| Seagate ST1000LM049-2GH172 1TB         | 57        | 1.18%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 57        | 1.18%   |
| Crucial CT240BX500SSD1 240GB           | 57        | 1.18%   |
| Intel NVMe SSD Drive 512GB             | 52        | 1.08%   |
| Kingston SA400S37240G 240GB SSD        | 49        | 1.01%   |
| Toshiba MQ01ABF050 500GB               | 40        | 0.83%   |
| SanDisk NVMe SSD Drive 256GB           | 38        | 0.79%   |
| Toshiba DT01ACA100 1TB                 | 37        | 0.77%   |
| Samsung NVMe SSD Drive 512GB           | 36        | 0.75%   |
| HGST HTS541010A9E680 1TB               | 35        | 0.72%   |
| Seagate ST500DM002-1BD142 500GB        | 34        | 0.7%    |
| SanDisk NVMe SSD Drive 512GB           | 34        | 0.7%    |
| Seagate ST9500325AS 500GB              | 32        | 0.66%   |
| Intel SSDPEKNW512G8 512GB              | 32        | 0.66%   |
| SK hynix NVMe SSD Drive 512GB          | 30        | 0.62%   |
| WDC WD10SPZX-60Z10T0 1TB               | 29        | 0.6%    |
| HGST HTS721010A9E630 1TB               | 29        | 0.6%    |
| WDC WD10SPZX-24Z10 1TB                 | 28        | 0.58%   |
| Seagate ST2000LM007-1R8174 2TB         | 28        | 0.58%   |
| WDC WD10JPVX-60JC3T1 1TB               | 27        | 0.56%   |
| Seagate ST1000LM048-2E7172 1TB         | 27        | 0.56%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 26        | 0.54%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 25        | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB               | 25        | 0.52%   |
| HGST HTS545050A7E680 500GB             | 23        | 0.48%   |
| A-DATA SU750 256GB SSD                 | 23        | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB               | 22        | 0.46%   |
| Samsung SSD 860 EVO 250GB              | 22        | 0.46%   |
| Seagate ST500LT012-9WS142 500GB        | 20        | 0.41%   |
| Kingston SA400S37480G 480GB SSD        | 20        | 0.41%   |
| HGST HTS545050A7E380 500GB             | 20        | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 19        | 0.39%   |
| Seagate ST3500418AS 500GB              | 19        | 0.39%   |
| WDC WD5000LPVX-75V0TT0 500GB           | 18        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1027      | 1331   | 41.68%  |
| WDC                 | 677       | 819    | 27.48%  |
| Toshiba             | 429       | 473    | 17.41%  |
| HGST                | 160       | 185    | 6.49%   |
| Hitachi             | 102       | 122    | 4.14%   |
| Samsung Electronics | 21        | 24     | 0.85%   |
| Unknown             | 17        | 21     | 0.69%   |
| Fujitsu             | 8         | 8      | 0.32%   |
| Apple               | 6         | 6      | 0.24%   |
| Hewlett-Packard     | 5         | 6      | 0.2%    |
| Maxtor              | 3         | 3      | 0.12%   |
| ASMT                | 2         | 2      | 0.08%   |
| WD MediaMax         | 1         | 1      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| MARSHAL             | 1         | 1      | 0.04%   |
| Lenovo              | 1         | 1      | 0.04%   |
| KESU                | 1         | 2      | 0.04%   |
| IBM                 | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 170       | 217    | 16.97%  |
| WDC                 | 150       | 186    | 14.97%  |
| Crucial             | 149       | 193    | 14.87%  |
| Kingston            | 127       | 158    | 12.67%  |
| A-DATA Technology   | 60        | 66     | 5.99%   |
| SanDisk             | 57        | 75     | 5.69%   |
| SK hynix            | 33        | 35     | 3.29%   |
| China               | 24        | 28     | 2.4%    |
| Micron Technology   | 23        | 30     | 2.3%    |
| Intel               | 18        | 19     | 1.8%    |
| Gigabyte Technology | 16        | 17     | 1.6%    |
| Toshiba             | 13        | 14     | 1.3%    |
| LITEON              | 13        | 15     | 1.3%    |
| FORESEE             | 12        | 13     | 1.2%    |
| Hewlett-Packard     | 10        | 15     | 1%      |
| Unknown             | 9         | 9      | 0.9%    |
| Seagate             | 8         | 8      | 0.8%    |
| TO Exter            | 7         | 7      | 0.7%    |
| SPCC                | 7         | 9      | 0.7%    |
| Maxtor              | 7         | 20     | 0.7%    |
| Apple               | 7         | 11     | 0.7%    |
| Transcend           | 6         | 7      | 0.6%    |
| Unknown             | 5         | 5      | 0.5%    |
| Lexar               | 5         | 5      | 0.5%    |
| PNY                 | 4         | 6      | 0.4%    |
| Leven               | 4         | 4      | 0.4%    |
| StoreJet            | 3         | 3      | 0.3%    |
| Plextor             | 3         | 3      | 0.3%    |
| LITEONIT            | 3         | 4      | 0.3%    |
| KingSpec            | 3         | 3      | 0.3%    |
| HS-SSD-C100         | 3         | 4      | 0.3%    |
| Team                | 2         | 2      | 0.2%    |
| OCZ                 | 2         | 2      | 0.2%    |
| Netac               | 2         | 2      | 0.2%    |
| KLEVV               | 2         | 3      | 0.2%    |
| KIOXIA-EXCERIA      | 2         | 2      | 0.2%    |
| KingDian            | 2         | 2      | 0.2%    |
| BIWIN               | 2         | 2      | 0.2%    |
| Aarvex              | 2         | 2      | 0.2%    |
| YS                  | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2337      | 3008   | 52.9%   |
| NVMe    | 1023      | 1311   | 23.16%  |
| SSD     | 946       | 1235   | 21.41%  |
| MMC     | 82        | 107    | 1.86%   |
| Unknown | 30        | 35     | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2866      | 4147   | 70.38%  |
| NVMe | 1020      | 1304   | 25.05%  |
| SAS  | 104       | 138    | 2.55%   |
| MMC  | 82        | 107    | 2.01%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1712      | 2196   | 51.52%  |
| 0.51-1.0   | 1431      | 1762   | 43.06%  |
| 1.01-2.0   | 125       | 183    | 3.76%   |
| 3.01-4.0   | 30        | 58     | 0.9%    |
| 4.01-10.0  | 14        | 26     | 0.42%   |
| 2.01-3.0   | 9         | 15     | 0.27%   |
| 10.01-20.0 | 2         | 3      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 1007      | 26.45%  |
| 101-250        | 966       | 25.37%  |
| 501-1000       | 653       | 17.15%  |
| 51-100         | 355       | 9.32%   |
| 21-50          | 235       | 6.17%   |
| 1001-2000      | 233       | 6.12%   |
| 1-20           | 197       | 5.17%   |
| More than 3000 | 59        | 1.55%   |
| Unknown        | 58        | 1.52%   |
| 2001-3000      | 44        | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1548      | 39.28%  |
| 21-50          | 812       | 20.6%   |
| 101-250        | 518       | 13.14%  |
| 51-100         | 470       | 11.93%  |
| 251-500        | 286       | 7.26%   |
| 501-1000       | 171       | 4.34%   |
| Unknown        | 58        | 1.47%   |
| 1001-2000      | 48        | 1.22%   |
| More than 3000 | 20        | 0.51%   |
| 2001-3000      | 9         | 0.23%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 21        | 22     | 6.5%    |
| HGST HTS541010A9E680 1TB             | 12        | 12     | 3.72%   |
| Toshiba MQ01ABD100 1TB               | 10        | 10     | 3.1%    |
| Seagate ST500LT012-1DG142 500GB      | 9         | 9      | 2.79%   |
| Seagate ST1000LM049-2GH172 1TB       | 9         | 10     | 2.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 9      | 2.79%   |
| HGST HTS545050A7E680 500GB           | 9         | 11     | 2.79%   |
| Seagate ST500DM002-1BD142 500GB      | 8         | 8      | 2.48%   |
| Seagate ST9500325AS 500GB            | 7         | 7      | 2.17%   |
| Seagate ST500LT012-9WS142 500GB      | 5         | 5      | 1.55%   |
| Seagate ST500LM021-1KJ152 500GB      | 5         | 5      | 1.55%   |
| WDC WD10EZEX-08WN4A0 1TB             | 4         | 4      | 1.24%   |
| Toshiba MQ04ABF100 1TB               | 4         | 5      | 1.24%   |
| Toshiba MQ01ABF050 500GB             | 4         | 4      | 1.24%   |
| Seagate ST3500418AS 500GB            | 4         | 4      | 1.24%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 4      | 1.24%   |
| HGST HTS721010A9E630 1TB             | 4         | 4      | 1.24%   |
| HGST HTS545050A7E380 500GB           | 4         | 4      | 1.24%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 3      | 0.93%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 3      | 0.93%   |
| Seagate ST2000LM007-1R8174 2TB       | 3         | 3      | 0.93%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.93%   |
| Seagate ST1000DM003-1ER162 1TB       | 3         | 3      | 0.93%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 3      | 0.93%   |
| HGST HTS725050A7E630 500GB           | 3         | 3      | 0.93%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 2      | 0.62%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 2      | 0.62%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 2      | 0.62%   |
| WDC WD5000AAKX-001CA0 500GB          | 2         | 5      | 0.62%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 2         | 2      | 0.62%   |
| WDC WD3200AAJS-00L7A0 320GB          | 2         | 2      | 0.62%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 0.62%   |
| Toshiba MQ01ABD050 500GB             | 2         | 2      | 0.62%   |
| Toshiba HDWD110 1TB                  | 2         | 2      | 0.62%   |
| Toshiba DT01ACA100 1TB               | 2         | 2      | 0.62%   |
| Seagate ST9320325AS 320GB            | 2         | 2      | 0.62%   |
| Seagate ST9160314AS 160GB            | 2         | 2      | 0.62%   |
| Seagate ST2000DM001-1CH164 2TB       | 2         | 2      | 0.62%   |
| Seagate ST1000LX015-1U7172-SSHD 1TB  | 2         | 3      | 0.62%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 2      | 0.62%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 125       | 134    | 39.43%  |
| WDC                 | 57        | 66     | 17.98%  |
| HGST                | 35        | 37     | 11.04%  |
| Toshiba             | 32        | 34     | 10.09%  |
| Hitachi             | 24        | 27     | 7.57%   |
| SK hynix            | 10        | 11     | 3.15%   |
| Samsung Electronics | 8         | 10     | 2.52%   |
| SanDisk             | 6         | 6      | 1.89%   |
| Crucial             | 4         | 5      | 1.26%   |
| A-DATA Technology   | 3         | 3      | 0.95%   |
| Apple               | 2         | 2      | 0.63%   |
| YS                  | 1         | 1      | 0.32%   |
| Unknown             | 1         | 1      | 0.32%   |
| Micron Technology   | 1         | 1      | 0.32%   |
| MARSHAL             | 1         | 1      | 0.32%   |
| LITEON              | 1         | 1      | 0.32%   |
| Leven               | 1         | 1      | 0.32%   |
| Lenovo              | 1         | 2      | 0.32%   |
| Intel               | 1         | 1      | 0.32%   |
| Innodisk            | 1         | 1      | 0.32%   |
| IBM                 | 1         | 1      | 0.32%   |
| China               | 1         | 1      | 0.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 125       | 134    | 45.29%  |
| WDC                 | 52        | 61     | 18.84%  |
| HGST                | 35        | 37     | 12.68%  |
| Toshiba             | 32        | 34     | 11.59%  |
| Hitachi             | 24        | 27     | 8.7%    |
| Samsung Electronics | 4         | 5      | 1.45%   |
| Apple               | 2         | 2      | 0.72%   |
| MARSHAL             | 1         | 1      | 0.36%   |
| IBM                 | 1         | 1      | 0.36%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 275       | 302    | 87.03%  |
| SSD  | 26        | 28     | 8.23%   |
| NVMe | 15        | 17     | 4.75%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 16.67%  |
| Seagate ST3320418AS 320GB           | 1         | 1      | 16.67%  |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |
| Samsung Electronics SSD 980 500GB   | 1         | 2      | 16.67%  |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 3      | 50%     |
| WDC                 | 1         | 1      | 16.67%  |
| Samsung Electronics | 1         | 2      | 16.67%  |
| Apple               | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2293      | 3528   | 59.62%  |
| Works    | 1236      | 1814   | 32.14%  |
| Malfunc  | 311       | 347    | 8.09%   |
| Failed   | 6         | 7      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2765      | 63.78%  |
| AMD                              | 570       | 13.15%  |
| Samsung Electronics              | 249       | 5.74%   |
| SanDisk                          | 214       | 4.94%   |
| SK hynix                         | 117       | 2.7%    |
| Micron Technology                | 64        | 1.48%   |
| Kingston Technology Company      | 60        | 1.38%   |
| Toshiba America Info Systems     | 56        | 1.29%   |
| KIOXIA                           | 55        | 1.27%   |
| Micron/Crucial Technology        | 30        | 0.69%   |
| Union Memory (Shenzhen)          | 23        | 0.53%   |
| Phison Electronics               | 19        | 0.44%   |
| Silicon Motion                   | 18        | 0.42%   |
| ASMedia Technology               | 16        | 0.37%   |
| Nvidia                           | 15        | 0.35%   |
| Realtek Semiconductor            | 11        | 0.25%   |
| JMicron Technology               | 8         | 0.18%   |
| ADATA Technology                 | 8         | 0.18%   |
| Marvell Technology Group         | 6         | 0.14%   |
| Solid State Storage Technology   | 4         | 0.09%   |
| Silicon Integrated Systems [SiS] | 4         | 0.09%   |
| Lite-On Technology               | 4         | 0.09%   |
| Yangtze Memory Technologies      | 3         | 0.07%   |
| LSI Logic / Symbios Logic        | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| Broadcom / LSI                   | 3         | 0.07%   |
| VIA Technologies                 | 2         | 0.05%   |
| Shenzhen Longsys Electronics     | 2         | 0.05%   |
| Seagate Technology               | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| Apple                            | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 491       | 10.12%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 420       | 8.66%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 284       | 5.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 176       | 3.63%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 162       | 3.34%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 130       | 2.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 117       | 2.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 116       | 2.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 109       | 2.25%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 109       | 2.25%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 104       | 2.14%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 102       | 2.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 102       | 2.1%    |
| Samsung NVMe SSD Controller 980                                                         | 98        | 2.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 93        | 1.92%   |
| Intel SSD 660P Series                                                                   | 88        | 1.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 87        | 1.79%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 67        | 1.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 66        | 1.36%   |
| Micron Non-Volatile memory controller                                                   | 64        | 1.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 60        | 1.24%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 59        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 55        | 1.13%   |
| KIOXIA NVMe SSD Controller BG4                                                          | 53        | 1.09%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 49        | 1.01%   |
| AMD 400 Series Chipset SATA Controller                                                  | 48        | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 44        | 0.91%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 41        | 0.85%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 40        | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 38        | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 38        | 0.78%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 37        | 0.76%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 37        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 36        | 0.74%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 36        | 0.74%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 34        | 0.7%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 34        | 0.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 33        | 0.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 33        | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 32        | 0.66%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2677      | 59.78%  |
| NVMe | 1029      | 22.98%  |
| RAID | 430       | 9.6%    |
| IDE  | 338       | 7.55%   |
| SAS  | 2         | 0.04%   |
| SCSI | 2         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 2939      | 80.59%  |
| AMD          | 689       | 18.89%  |
| ARM          | 18        | 0.49%   |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 177       | 4.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 108       | 2.96%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 82        | 2.25%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 78        | 2.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 72        | 1.97%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 68        | 1.86%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 47        | 1.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 47        | 1.29%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 45        | 1.23%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 43        | 1.18%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 43        | 1.18%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 42        | 1.15%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 42        | 1.15%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 41        | 1.12%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 37        | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 0.93%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 34        | 0.93%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 33        | 0.9%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 31        | 0.85%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 30        | 0.82%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 30        | 0.82%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 29        | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 0.77%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 27        | 0.74%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 27        | 0.74%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 26        | 0.71%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 26        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 0.69%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 25        | 0.69%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 23        | 0.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 21        | 0.58%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 21        | 0.58%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 21        | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 21        | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 20        | 0.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 20        | 0.55%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 20        | 0.55%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 20        | 0.55%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 19        | 0.52%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 19        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1151      | 31.55%  |
| Intel Core i3           | 636       | 17.43%  |
| Intel Core i7           | 463       | 12.69%  |
| AMD Ryzen 5             | 265       | 7.26%   |
| Other                   | 238       | 6.52%   |
| Intel Pentium           | 123       | 3.37%   |
| Intel Core 2 Duo        | 112       | 3.07%   |
| AMD Ryzen 7             | 102       | 2.8%    |
| Intel Celeron           | 69        | 1.89%   |
| AMD Ryzen 3             | 56        | 1.54%   |
| Intel Pentium Dual-Core | 55        | 1.51%   |
| AMD A6                  | 41        | 1.12%   |
| AMD A8                  | 30        | 0.82%   |
| AMD A4                  | 29        | 0.79%   |
| Intel Atom              | 26        | 0.71%   |
| Intel Xeon              | 21        | 0.58%   |
| AMD FX                  | 21        | 0.58%   |
| AMD Ryzen 9             | 20        | 0.55%   |
| Intel Pentium Dual      | 17        | 0.47%   |
| Intel Core 2            | 17        | 0.47%   |
| AMD A10                 | 16        | 0.44%   |
| Intel Core 2 Quad       | 14        | 0.38%   |
| AMD E1                  | 12        | 0.33%   |
| Intel Pentium Silver    | 9         | 0.25%   |
| Intel Core i9           | 8         | 0.22%   |
| Intel Pentium Gold      | 7         | 0.19%   |
| AMD E2                  | 7         | 0.19%   |
| AMD Athlon II X2        | 7         | 0.19%   |
| AMD Ryzen 5 PRO         | 6         | 0.16%   |
| AMD E                   | 6         | 0.16%   |
| Intel Pentium 4         | 5         | 0.14%   |
| ARM BCM                 | 5         | 0.14%   |
| AMD Ryzen 7 PRO         | 5         | 0.14%   |
| Intel Pentium D         | 4         | 0.11%   |
| AMD Phenom II X4        | 4         | 0.11%   |
| AMD Phenom II X2        | 4         | 0.11%   |
| AMD Athlon              | 4         | 0.11%   |
| Intel Xeon Silver       | 3         | 0.08%   |
| Intel Genuine           | 3         | 0.08%   |
| AMD Sempron             | 3         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1756      | 48.11%  |
| 4      | 1336      | 36.6%   |
| 6      | 318       | 8.71%   |
| 8      | 150       | 4.11%   |
| 1      | 45        | 1.23%   |
| 12     | 16        | 0.44%   |
| 3      | 7         | 0.19%   |
| 14     | 6         | 0.16%   |
| 10     | 6         | 0.16%   |
| 16     | 4         | 0.11%   |
| 32     | 2         | 0.05%   |
| 24     | 2         | 0.05%   |
| 36     | 1         | 0.03%   |
| 20     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3633      | 99.62%  |
| 2      | 14        | 0.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2765      | 75.82%  |
| 1      | 882       | 24.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3593      | 98.44%  |
| Unknown        | 51        | 1.4%    |
| 32-bit         | 5         | 0.14%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 668       | 17.88%  |
| 0x806ea    | 222       | 5.94%   |
| 0x806ec    | 207       | 5.54%   |
| 0x306a9    | 207       | 5.54%   |
| 0x206a7    | 195       | 5.22%   |
| 0x40651    | 141       | 3.77%   |
| 0x806e9    | 139       | 3.72%   |
| 0x906ea    | 138       | 3.69%   |
| 0x406e3    | 131       | 3.51%   |
| 0x806c1    | 127       | 3.4%    |
| 0x1067a    | 115       | 3.08%   |
| 0x306d4    | 101       | 2.7%    |
| 0x306c3    | 100       | 2.68%   |
| 0x706e5    | 67        | 1.79%   |
| 0x08108109 | 66        | 1.77%   |
| 0x20655    | 59        | 1.58%   |
| 0x906e9    | 57        | 1.53%   |
| 0x806eb    | 55        | 1.47%   |
| 0x506e3    | 50        | 1.34%   |
| 0x08108102 | 44        | 1.18%   |
| 0x0a50000c | 43        | 1.15%   |
| 0x06006705 | 35        | 0.94%   |
| 0x6fd      | 34        | 0.91%   |
| 0xa0652    | 32        | 0.86%   |
| 0x07030105 | 31        | 0.83%   |
| 0x08600104 | 28        | 0.75%   |
| 0x20652    | 27        | 0.72%   |
| 0xa0655    | 26        | 0.7%    |
| 0x08600106 | 26        | 0.7%    |
| 0x08701021 | 24        | 0.64%   |
| 0x0810100b | 24        | 0.64%   |
| 0x906ed    | 21        | 0.56%   |
| 0x30678    | 21        | 0.56%   |
| 0x08101007 | 19        | 0.51%   |
| 0x06001119 | 19        | 0.51%   |
| 0x08608103 | 18        | 0.48%   |
| 0x010000c8 | 17        | 0.45%   |
| 0x706a1    | 15        | 0.4%    |
| 0x10676    | 15        | 0.4%    |
| 0xa0653    | 13        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 999       | 27.38%  |
| Haswell          | 292       | 8%      |
| IvyBridge        | 243       | 6.66%   |
| SandyBridge      | 232       | 6.36%   |
| Skylake          | 223       | 6.11%   |
| Zen+             | 153       | 4.19%   |
| Penryn           | 153       | 4.19%   |
| TigerLake        | 148       | 4.06%   |
| Zen 2            | 136       | 3.73%   |
| Broadwell        | 126       | 3.45%   |
| Westmere         | 102       | 2.8%    |
| IceLake          | 94        | 2.58%   |
| CometLake        | 87        | 2.38%   |
| Excavator        | 75        | 2.06%   |
| Zen              | 73        | 2%      |
| Core             | 71        | 1.95%   |
| Unknown          | 65        | 1.78%   |
| Zen 3            | 64        | 1.75%   |
| Silvermont       | 59        | 1.62%   |
| Puma             | 50        | 1.37%   |
| Piledriver       | 41        | 1.12%   |
| Goldmont plus    | 24        | 0.66%   |
| K10              | 20        | 0.55%   |
| Goldmont         | 19        | 0.52%   |
| Alderlake Hybrid | 18        | 0.49%   |
| Nehalem          | 14        | 0.38%   |
| K10 Llano        | 13        | 0.36%   |
| Bonnell          | 11        | 0.3%    |
| Bobcat           | 11        | 0.3%    |
| NetBurst         | 10        | 0.27%   |
| Steamroller      | 5         | 0.14%   |
| Jaguar           | 5         | 0.14%   |
| Bulldozer        | 5         | 0.14%   |
| P6               | 3         | 0.08%   |
| K8 Hammer        | 3         | 0.08%   |
| Tremont          | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2676      | 57.52%  |
| Nvidia                           | 1049      | 22.55%  |
| AMD                              | 916       | 19.69%  |
| Silicon Integrated Systems [SiS] | 4         | 0.09%   |
| Matrox Electronics Systems       | 3         | 0.06%   |
| ASPEED Technology                | 2         | 0.04%   |
| VIA Technologies                 | 1         | 0.02%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 241       | 5.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 202       | 4.25%   |
| Intel HD Graphics 620                                                                 | 170       | 3.58%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 168       | 3.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 163       | 3.43%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 157       | 3.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 142       | 2.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 137       | 2.89%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 134       | 2.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 131       | 2.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 124       | 2.61%   |
| Intel HD Graphics 5500                                                                | 112       | 2.36%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 102       | 2.15%   |
| AMD Renoir                                                                            | 90        | 1.9%    |
| Intel Core Processor Integrated Graphics Controller                                   | 73        | 1.54%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 67        | 1.41%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 66        | 1.39%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 63        | 1.33%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 61        | 1.28%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 57        | 1.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 57        | 1.2%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 56        | 1.18%   |
| Nvidia TU117M                                                                         | 55        | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 53        | 1.12%   |
| Intel HD Graphics 630                                                                 | 52        | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 51        | 1.07%   |
| Nvidia GP108M [GeForce MX250]                                                         | 46        | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 46        | 0.97%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 46        | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 45        | 0.95%   |
| Nvidia GP108M [GeForce MX150]                                                         | 41        | 0.86%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 38        | 0.8%    |
| Intel CometLake-S GT2 [UHD Graphics 630]                                              | 35        | 0.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 35        | 0.74%   |
| Nvidia GM108M [GeForce MX130]                                                         | 34        | 0.72%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 34        | 0.72%   |
| Intel HD Graphics 530                                                                 | 34        | 0.72%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 34        | 0.72%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                | 34        | 0.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 34        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 1776      | 48.47%  |
| Intel + Nvidia     | 623       | 17%     |
| 1 x AMD            | 475       | 12.96%  |
| 1 x Nvidia         | 306       | 8.35%   |
| Intel + AMD        | 264       | 7.21%   |
| AMD + Nvidia       | 115       | 3.14%   |
| 2 x AMD            | 67        | 1.83%   |
| Other              | 24        | 0.66%   |
| 1 x SiS            | 4         | 0.11%   |
| 2 x Nvidia         | 3         | 0.08%   |
| 1 x Matrox         | 3         | 0.08%   |
| 1 x VIA            | 1         | 0.03%   |
| Nvidia + ASPEED    | 1         | 0.03%   |
| Intel + 2 x Nvidia | 1         | 0.03%   |
| 1 x ASPEED         | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3000      | 81.26%  |
| Proprietary | 573       | 15.52%  |
| Unknown     | 119       | 3.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2229      | 59.5%   |
| 1.01-2.0   | 616       | 16.44%  |
| 0.01-0.5   | 326       | 8.7%    |
| 3.01-4.0   | 284       | 7.58%   |
| 0.51-1.0   | 183       | 4.89%   |
| 5.01-6.0   | 55        | 1.47%   |
| 7.01-8.0   | 35        | 0.93%   |
| 8.01-16.0  | 10        | 0.27%   |
| 2.01-3.0   | 4         | 0.11%   |
| 16.01-24.0 | 4         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 605       | 16.15%  |
| AU Optronics            | 590       | 15.75%  |
| Chimei Innolux          | 555       | 14.82%  |
| LG Display              | 463       | 12.36%  |
| Samsung Electronics     | 311       | 8.3%    |
| Dell                    | 216       | 5.77%   |
| Goldstar                | 159       | 4.25%   |
| BenQ                    | 111       | 2.96%   |
| Acer                    | 99        | 2.64%   |
| PANDA                   | 89        | 2.38%   |
| Hewlett-Packard         | 69        | 1.84%   |
| Lenovo                  | 54        | 1.44%   |
| AOC                     | 49        | 1.31%   |
| Sharp                   | 41        | 1.09%   |
| Chi Mei Optoelectronics | 37        | 0.99%   |
| InfoVision              | 30        | 0.8%    |
| ViewSonic               | 23        | 0.61%   |
| Sony                    | 23        | 0.61%   |
| HCL                     | 19        | 0.51%   |
| Apple                   | 17        | 0.45%   |
| Philips                 | 14        | 0.37%   |
| Unknown                 | 13        | 0.35%   |
| LG Electronics          | 11        | 0.29%   |
| TMX                     | 8         | 0.21%   |
| ASUSTek Computer        | 7         | 0.19%   |
| STD                     | 6         | 0.16%   |
| LG Philips              | 6         | 0.16%   |
| InnoLux Display         | 6         | 0.16%   |
| Ancor Communications    | 6         | 0.16%   |
| Toshiba                 | 5         | 0.13%   |
| Panasonic               | 5         | 0.13%   |
| CSO                     | 4         | 0.11%   |
| AOpen                   | 4         | 0.11%   |
| Xiaomi                  | 3         | 0.08%   |
| LGD                     | 3         | 0.08%   |
| HKC                     | 3         | 0.08%   |
| Gigabyte Technology     | 3         | 0.08%   |
| CPT                     | 3         | 0.08%   |
| ___                     | 2         | 0.05%   |
| STA                     | 2         | 0.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 75        | 1.98%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 65        | 1.72%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 38        | 1%      |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 37        | 0.98%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 33        | 0.87%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 32        | 0.85%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 31        | 0.82%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                     | 29        | 0.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 28        | 0.74%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 27        | 0.71%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch       | 27        | 0.71%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 25        | 0.66%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 25        | 0.66%   |
| BenQ GW2283 BNQ78E9 1920x1080 480x270mm 21.7-inch                    | 23        | 0.61%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 22        | 0.58%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 22        | 0.58%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 22        | 0.58%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 20        | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 20        | 0.53%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 20        | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 19        | 0.5%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 19        | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 19        | 0.5%    |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 17        | 0.45%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 16        | 0.42%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 16        | 0.42%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 15        | 0.4%    |
| BOE LCD Monitor BOE07BD 1920x1080 309x174mm 14.0-inch                | 15        | 0.4%    |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                    | 15        | 0.4%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 14        | 0.37%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 14        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 14        | 0.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 14        | 0.37%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 14        | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 13        | 0.34%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 13        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 13        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 13        | 0.34%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 13        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch      | 12        | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1763      | 48.33%  |
| 1366x768 (WXGA)    | 1348      | 36.95%  |
| 1600x900 (HD+)     | 119       | 3.26%   |
| 3840x2160 (4K)     | 80        | 2.19%   |
| 1440x900 (WXGA+)   | 49        | 1.34%   |
| 2560x1440 (QHD)    | 48        | 1.32%   |
| 1280x800 (WXGA)    | 37        | 1.01%   |
| 1920x1200 (WUXGA)  | 26        | 0.71%   |
| 1360x768           | 25        | 0.69%   |
| 1280x1024 (SXGA)   | 24        | 0.66%   |
| 2560x1080          | 19        | 0.52%   |
| 2560x1600          | 15        | 0.41%   |
| Unknown            | 15        | 0.41%   |
| 1680x1050 (WSXGA+) | 11        | 0.3%    |
| 3840x1080          | 9         | 0.25%   |
| 1024x768 (XGA)     | 8         | 0.22%   |
| 1024x600           | 7         | 0.19%   |
| 1280x720 (HD)      | 5         | 0.14%   |
| 3200x2000          | 4         | 0.11%   |
| 2880x1800          | 4         | 0.11%   |
| 4093x4093          | 3         | 0.08%   |
| 2160x1440          | 3         | 0.08%   |
| 3840x2400          | 2         | 0.05%   |
| 3456x2160          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 1280x768           | 2         | 0.05%   |
| 1152x864           | 2         | 0.05%   |
| 8160x4627          | 1         | 0.03%   |
| 6400x2160          | 1         | 0.03%   |
| 5760x2160          | 1         | 0.03%   |
| 4480x1080          | 1         | 0.03%   |
| 3840x1100          | 1         | 0.03%   |
| 3440x1440          | 1         | 0.03%   |
| 3286x1080          | 1         | 0.03%   |
| 3200x900           | 1         | 0.03%   |
| 3072x1920          | 1         | 0.03%   |
| 3000x2000          | 1         | 0.03%   |
| 2736x1824          | 1         | 0.03%   |
| 2732x768           | 1         | 0.03%   |
| 2288x1287          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1650      | 44.06%  |
| 13      | 491       | 13.11%  |
| 14      | 449       | 11.99%  |
| 21      | 225       | 6.01%   |
| 18      | 202       | 5.39%   |
| 24      | 110       | 2.94%   |
| Unknown | 90        | 2.4%    |
| 19      | 87        | 2.32%   |
| 23      | 81        | 2.16%   |
| 27      | 71        | 1.9%    |
| 20      | 50        | 1.34%   |
| 12      | 42        | 1.12%   |
| 17      | 40        | 1.07%   |
| 31      | 23        | 0.61%   |
| 16      | 18        | 0.48%   |
| 34      | 17        | 0.45%   |
| 11      | 16        | 0.43%   |
| 72      | 11        | 0.29%   |
| 10      | 10        | 0.27%   |
| 40      | 8         | 0.21%   |
| 26      | 8         | 0.21%   |
| 22      | 7         | 0.19%   |
| 46      | 6         | 0.16%   |
| 32      | 6         | 0.16%   |
| 84      | 5         | 0.13%   |
| 65      | 4         | 0.11%   |
| 25      | 4         | 0.11%   |
| 54      | 3         | 0.08%   |
| 42      | 3         | 0.08%   |
| 39      | 3         | 0.08%   |
| 52      | 2         | 0.05%   |
| 142     | 1         | 0.03%   |
| 58      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2462      | 65.99%  |
| 401-500        | 562       | 15.06%  |
| 501-600        | 254       | 6.81%   |
| 201-300        | 185       | 4.96%   |
| Unknown        | 90        | 2.41%   |
| 351-400        | 74        | 1.98%   |
| 601-700        | 33        | 0.88%   |
| 701-800        | 23        | 0.62%   |
| 1001-1500      | 17        | 0.46%   |
| 1501-2000      | 16        | 0.43%   |
| 801-900        | 11        | 0.29%   |
| 901-1000       | 3         | 0.08%   |
| More than 2000 | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3205      | 90.95%  |
| 16/10   | 152       | 4.31%   |
| Unknown | 87        | 2.47%   |
| 4/3     | 25        | 0.71%   |
| 5/4     | 19        | 0.54%   |
| 21/9    | 17        | 0.48%   |
| 3/2     | 10        | 0.28%   |
| 6/5     | 6         | 0.17%   |
| 32/9    | 1         | 0.03%   |
| 3.40    | 1         | 0.03%   |
| 1.00    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1634      | 43.65%  |
| 81-90          | 843       | 22.52%  |
| 201-250        | 367       | 9.8%    |
| 141-150        | 209       | 5.58%   |
| 151-200        | 174       | 4.65%   |
| 71-80          | 98        | 2.62%   |
| Unknown        | 90        | 2.4%    |
| 301-350        | 75        | 2%      |
| 351-500        | 46        | 1.23%   |
| 61-70          | 35        | 0.94%   |
| More than 1000 | 27        | 0.72%   |
| 251-300        | 27        | 0.72%   |
| 121-130        | 27        | 0.72%   |
| 501-1000       | 21        | 0.56%   |
| 51-60          | 17        | 0.45%   |
| 111-120        | 17        | 0.45%   |
| 91-100         | 17        | 0.45%   |
| 41-50          | 10        | 0.27%   |
| 131-140        | 9         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1374      | 37.15%  |
| 101-120       | 1295      | 35.01%  |
| 51-100        | 752       | 20.33%  |
| 161-240       | 126       | 3.41%   |
| Unknown       | 90        | 2.43%   |
| 1-50          | 32        | 0.87%   |
| More than 240 | 30        | 0.81%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3294      | 89.22%  |
| 2     | 278       | 7.53%   |
| 0     | 112       | 3.03%   |
| 3     | 8         | 0.22%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2481      | 42.75%  |
| Intel                             | 1458      | 25.12%  |
| Qualcomm Atheros                  | 764       | 13.17%  |
| Broadcom                          | 257       | 4.43%   |
| Ralink Technology                 | 117       | 2.02%   |
| Xiaomi                            | 94        | 1.62%   |
| TP-Link                           | 77        | 1.33%   |
| MediaTek                          | 62        | 1.07%   |
| Ralink                            | 59        | 1.02%   |
| Samsung Electronics               | 45        | 0.78%   |
| Broadcom Limited                  | 45        | 0.78%   |
| OPPO Electronics                  | 43        | 0.74%   |
| Marvell Technology Group          | 31        | 0.53%   |
| D-Link                            | 30        | 0.52%   |
| Qualcomm                          | 29        | 0.5%    |
| Huawei Technologies               | 23        | 0.4%    |
| OnePlus Technology (Shenzhen)     | 21        | 0.36%   |
| Foxconn / Hon Hai                 | 15        | 0.26%   |
| Motorola PCS                      | 14        | 0.24%   |
| ASIX Electronics                  | 13        | 0.22%   |
| Qualcomm Atheros Communications   | 12        | 0.21%   |
| Nvidia                            | 11        | 0.19%   |
| Lenovo                            | 7         | 0.12%   |
| ICS Advent                        | 7         | 0.12%   |
| Google                            | 7         | 0.12%   |
| vivo                              | 6         | 0.1%    |
| NetGear                           | 6         | 0.1%    |
| Edimax Technology                 | 6         | 0.1%    |
| NTmore                            | 5         | 0.09%   |
| JMicron Technology                | 5         | 0.09%   |
| HMD Global                        | 5         | 0.09%   |
| Microchip Technology              | 4         | 0.07%   |
| DisplayLink                       | 4         | 0.07%   |
| D-Link System                     | 4         | 0.07%   |
| ASUSTek Computer                  | 4         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.03%   |
| Spreadtrum Communications         | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.03%   |
| Sierra Wireless                   | 2         | 0.03%   |
| Ericsson Business Mobile Networks | 2         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1630      | 24.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 599       | 8.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 272       | 4.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 131       | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 129       | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 123       | 1.82%   |
| Intel Wireless 8265 / 8275                                        | 121       | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 109       | 1.61%   |
| Intel Wi-Fi 6 AX201                                               | 108       | 1.6%    |
| Ralink MT7601U Wireless Adapter                                   | 104       | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 102       | 1.51%   |
| Broadcom BCM43142 802.11b/g/n                                     | 96        | 1.42%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 93        | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 92        | 1.36%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 89        | 1.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 87        | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 83        | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 78        | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 75        | 1.11%   |
| Intel Wireless 7265                                               | 72        | 1.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 72        | 1.07%   |
| Realtek 802.11n                                                   | 71        | 1.05%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 70        | 1.04%   |
| Intel Wireless 3165                                               | 70        | 1.04%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 66        | 0.98%   |
| Intel Wireless 3160                                               | 57        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 57        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 54        | 0.8%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 44        | 0.65%   |
| OPPO SDM665-IDP _SN:18689828                                      | 43        | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 41        | 0.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 39        | 0.58%   |
| Intel Wireless 8260                                               | 37        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 35        | 0.52%   |
| Intel Wireless 7260                                               | 34        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 34        | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 34        | 0.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 32        | 0.47%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 30        | 0.44%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 29        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1254      | 38.05%  |
| Realtek Semiconductor           | 755       | 22.91%  |
| Qualcomm Atheros                | 679       | 20.6%   |
| Broadcom                        | 215       | 6.52%   |
| Ralink Technology               | 117       | 3.55%   |
| TP-Link                         | 70        | 2.12%   |
| Ralink                          | 58        | 1.76%   |
| MediaTek                        | 46        | 1.4%    |
| Broadcom Limited                | 36        | 1.09%   |
| D-Link                          | 30        | 0.91%   |
| Qualcomm Atheros Communications | 12        | 0.36%   |
| NetGear                         | 6         | 0.18%   |
| Edimax Technology               | 6         | 0.18%   |
| Sierra Wireless                 | 2         | 0.06%   |
| Dell                            | 2         | 0.06%   |
| D-Link System                   | 2         | 0.06%   |
| Wacom                           | 1         | 0.03%   |
| Qualcomm                        | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Marvell Technology Group        | 1         | 0.03%   |
| IMC Networks                    | 1         | 0.03%   |
| ASUSTek Computer                | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 272       | 8.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 131       | 3.96%   |
| Intel Wi-Fi 6 AX200                                                  | 129       | 3.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 123       | 3.71%   |
| Intel Wireless 8265 / 8275                                           | 121       | 3.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 109       | 3.29%   |
| Intel Wi-Fi 6 AX201                                                  | 108       | 3.26%   |
| Ralink MT7601U Wireless Adapter                                      | 104       | 3.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 102       | 3.08%   |
| Broadcom BCM43142 802.11b/g/n                                        | 96        | 2.9%    |
| Realtek RTL8723DE Wireless Network Adapter                           | 93        | 2.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 92        | 2.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 89        | 2.69%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 87        | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 83        | 2.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 78        | 2.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 75        | 2.26%   |
| Intel Wireless 7265                                                  | 72        | 2.17%   |
| Realtek 802.11n                                                      | 71        | 2.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 70        | 2.11%   |
| Intel Wireless 3165                                                  | 70        | 2.11%   |
| Intel Wireless 3160                                                  | 57        | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 57        | 1.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 54        | 1.63%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 44        | 1.33%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 41        | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 39        | 1.18%   |
| Intel Wireless 8260                                                  | 37        | 1.12%   |
| Intel Wireless 7260                                                  | 34        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 34        | 1.03%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 32        | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 30        | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 29        | 0.88%   |
| Intel Wireless-AC 9260                                               | 27        | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 27        | 0.82%   |
| TP-Link 802.11ac WLAN Adapter                                        | 23        | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                           | 23        | 0.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                          | 17        | 0.51%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                         | 17        | 0.51%   |
| D-Link DWA-131 Wireless N Nano Adapter (Rev. E1) [Realtek RTL8192EU] | 17        | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2286      | 68.06%  |
| Intel                            | 478       | 14.23%  |
| Qualcomm Atheros                 | 125       | 3.72%   |
| Xiaomi                           | 94        | 2.8%    |
| Broadcom                         | 60        | 1.79%   |
| Samsung Electronics              | 45        | 1.34%   |
| OPPO Electronics                 | 43        | 1.28%   |
| Marvell Technology Group         | 30        | 0.89%   |
| Qualcomm                         | 28        | 0.83%   |
| Huawei Technologies              | 20        | 0.6%    |
| MediaTek                         | 17        | 0.51%   |
| OnePlus Technology (Shenzhen)    | 16        | 0.48%   |
| ASIX Electronics                 | 13        | 0.39%   |
| Nvidia                           | 10        | 0.3%    |
| Motorola PCS                     | 9         | 0.27%   |
| Broadcom Limited                 | 9         | 0.27%   |
| TP-Link                          | 7         | 0.21%   |
| ICS Advent                       | 7         | 0.21%   |
| Google                           | 7         | 0.21%   |
| vivo                             | 5         | 0.15%   |
| NTmore                           | 5         | 0.15%   |
| JMicron Technology               | 5         | 0.15%   |
| HMD Global                       | 5         | 0.15%   |
| Lenovo                           | 4         | 0.12%   |
| Foxconn / Hon Hai                | 4         | 0.12%   |
| DisplayLink                      | 4         | 0.12%   |
| Microchip Technology             | 3         | 0.09%   |
| ASUSTek Computer                 | 3         | 0.09%   |
| Spreadtrum Communications        | 2         | 0.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| D-Link System                    | 2         | 0.06%   |
| Attansic Technology              | 2         | 0.06%   |
| Aquantia                         | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| Standard Microsystems            | 1         | 0.03%   |
| LG Electronics                   | 1         | 0.03%   |
| Davicom Semiconductor            | 1         | 0.03%   |
| Apple                            | 1         | 0.03%   |
| Android                          | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1630      | 47.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 599       | 17.63%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 72        | 2.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 66        | 1.94%   |
| OPPO SDM665-IDP _SN:18689828                                      | 43        | 1.27%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 35        | 1.03%   |
| Intel Ethernet Connection (4) I219-V                              | 34        | 1%      |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 28        | 0.82%   |
| Intel 82579V Gigabit Network Connection                           | 26        | 0.77%   |
| Intel Ethernet Connection I217-LM                                 | 25        | 0.74%   |
| Qualcomm Redmi Note 8                                             | 24        | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.68%   |
| Intel Ethernet Connection (2) I219-V                              | 23        | 0.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 22        | 0.65%   |
| Intel I211 Gigabit Network Connection                             | 22        | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 21        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 21        | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 20        | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.53%   |
| OnePlus (Shenzhen) AC2003                                         | 16        | 0.47%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 14        | 0.41%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 13        | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.38%   |
| MediaTek N152DL                                                   | 13        | 0.38%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.38%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 12        | 0.35%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.32%   |
| Huawei E353/E3131                                                 | 11        | 0.32%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 10        | 0.29%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10        | 0.29%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.29%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 3185      | 50.72%  |
| Ethernet | 3050      | 48.57%  |
| Unknown  | 30        | 0.48%   |
| Modem    | 14        | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2634      | 72.98%  |
| Ethernet | 968       | 26.82%  |
| Unknown  | 6         | 0.17%   |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2248      | 61.52%  |
| 1     | 1316      | 36.02%  |
| 0     | 57        | 1.56%   |
| 3     | 27        | 0.74%   |
| 4     | 5         | 0.14%   |
| 6     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3116      | 84.47%  |
| Yes  | 573       | 15.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1088      | 40.6%   |
| Realtek Semiconductor           | 437       | 16.31%  |
| Qualcomm Atheros Communications | 415       | 15.49%  |
| Broadcom                        | 146       | 5.45%   |
| IMC Networks                    | 120       | 4.48%   |
| Cambridge Silicon Radio         | 114       | 4.25%   |
| Lite-On Technology              | 109       | 4.07%   |
| Foxconn / Hon Hai               | 81        | 3.02%   |
| Ralink                          | 44        | 1.64%   |
| Dell                            | 30        | 1.12%   |
| Apple                           | 23        | 0.86%   |
| Hewlett-Packard                 | 14        | 0.52%   |
| Foxconn International           | 10        | 0.37%   |
| TP-Link                         | 7         | 0.26%   |
| Toshiba                         | 7         | 0.26%   |
| Ralink Technology               | 7         | 0.26%   |
| Realtek                         | 6         | 0.22%   |
| ASUSTek Computer                | 6         | 0.22%   |
| MediaTek                        | 4         | 0.15%   |
| Integrated System Solution      | 3         | 0.11%   |
| SINO WEALTH                     | 2         | 0.07%   |
| Chicony Electronics             | 2         | 0.07%   |
| USI                             | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Alps Electric                   | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 391       | 14.59%  |
| Realtek Bluetooth Radio                                                             | 268       | 10%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 264       | 9.85%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 243       | 9.07%   |
| Intel AX201 Bluetooth                                                               | 200       | 7.46%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 139       | 5.19%   |
| Intel AX200 Bluetooth                                                               | 126       | 4.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 114       | 4.25%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 53        | 1.98%   |
| IMC Networks Bluetooth Radio                                                        | 49        | 1.83%   |
| Ralink RT3290 Bluetooth                                                             | 44        | 1.64%   |
| IMC Networks Bluetooth Device                                                       | 44        | 1.64%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 42        | 1.57%   |
| Lite-On Bluetooth Device                                                            | 41        | 1.53%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 40        | 1.49%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 35        | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 34        | 1.27%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 34        | 1.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 26        | 0.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 25        | 0.93%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 24        | 0.9%    |
| IMC Networks Wireless_Device                                                        | 24        | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 17        | 0.63%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 15        | 0.56%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 15        | 0.56%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 15        | 0.56%   |
| Realtek RTL8821A Bluetooth                                                          | 14        | 0.52%   |
| Realtek RTL8723B Bluetooth                                                          | 14        | 0.52%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 14        | 0.52%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 13        | 0.49%   |
| Intel Bluetooth Device                                                              | 12        | 0.45%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 12        | 0.45%   |
| Dell Wireless 365 Bluetooth                                                         | 12        | 0.45%   |
| Qualcomm Atheros Bluetooth                                                          | 11        | 0.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.41%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 10        | 0.37%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 10        | 0.37%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 0.37%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 9         | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 8         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2900      | 66.32%  |
| AMD                                          | 743       | 16.99%  |
| Nvidia                                       | 580       | 13.26%  |
| C-Media Electronics                          | 23        | 0.53%   |
| GN Netcom                                    | 14        | 0.32%   |
| Creative Labs                                | 9         | 0.21%   |
| Plantronics                                  | 7         | 0.16%   |
| Generalplus Technology                       | 7         | 0.16%   |
| Texas Instruments                            | 6         | 0.14%   |
| Logitech                                     | 6         | 0.14%   |
| JMTek                                        | 6         | 0.14%   |
| Sennheiser Communications                    | 5         | 0.11%   |
| Realtek Semiconductor                        | 5         | 0.11%   |
| Creative Technology                          | 5         | 0.11%   |
| Tenx Technology                              | 4         | 0.09%   |
| Silicon Integrated Systems [SiS]             | 4         | 0.09%   |
| SteelSeries ApS                              | 3         | 0.07%   |
| OPPO Electronics                             | 2         | 0.05%   |
| M-Audio                                      | 2         | 0.05%   |
| Lenovo                                       | 2         | 0.05%   |
| Giga-Byte Technology                         | 2         | 0.05%   |
| DCMT Technology                              | 2         | 0.05%   |
| Cambridge Silicon Radio                      | 2         | 0.05%   |
| ASUSTek Computer                             | 2         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.02%   |
| ZOOM                                         | 1         | 0.02%   |
| Yamaha                                       | 1         | 0.02%   |
| XMOS                                         | 1         | 0.02%   |
| WL80                                         | 1         | 0.02%   |
| VIA Technologies                             | 1         | 0.02%   |
| Vault                                        | 1         | 0.02%   |
| SZSanJing                                    | 1         | 0.02%   |
| Synaptics                                    | 1         | 0.02%   |
| Sony                                         | 1         | 0.02%   |
| Shenzhen Rapoo Technology                    | 1         | 0.02%   |
| SAVITECH                                     | 1         | 0.02%   |
| Razer USA                                    | 1         | 0.02%   |
| Panasonic (Matsushita)                       | 1         | 0.02%   |
| NEC Computers                                | 1         | 0.02%   |
| Microsoft                                    | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 573       | 10.84%  |
| AMD Family 17h/19h HD Audio Controller                                     | 373       | 7.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 236       | 4.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 234       | 4.43%   |
| Intel Cannon Lake PCH cAVS                                                 | 176       | 3.33%   |
| Intel 8 Series HD Audio Controller                                         | 168       | 3.18%   |
| Intel Haswell-ULT HD Audio Controller                                      | 166       | 3.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 165       | 3.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 163       | 3.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 148       | 2.8%    |
| Intel Comet Lake PCH-LP cAVS                                               | 146       | 2.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 142       | 2.69%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 132       | 2.5%    |
| Intel Broadwell-U Audio Controller                                         | 122       | 2.31%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 121       | 2.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 117       | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 113       | 2.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 113       | 2.14%   |
| AMD FCH Azalia Controller                                                  | 101       | 1.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 100       | 1.89%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 89        | 1.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 78        | 1.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 74        | 1.4%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 73        | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                   | 69        | 1.31%   |
| Nvidia GP107GL High Definition Audio Controller                            | 65        | 1.23%   |
| AMD High Definition Audio Controller                                       | 56        | 1.06%   |
| AMD Starship/Matisse HD Audio Controller                                   | 52        | 0.98%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 51        | 0.96%   |
| Intel 200 Series PCH HD Audio                                              | 50        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                  | 48        | 0.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 45        | 0.85%   |
| Nvidia TU116 High Definition Audio Controller                              | 40        | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 40        | 0.76%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 34        | 0.64%   |
| Intel CM238 HD Audio Controller                                            | 32        | 0.61%   |
| Nvidia GF119 HDMI Audio Controller                                         | 25        | 0.47%   |
| Nvidia GA106 High Definition Audio Controller                              | 25        | 0.47%   |
| Nvidia GF108 High Definition Audio Controller                              | 24        | 0.45%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 24        | 0.45%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 593       | 25.56%  |
| SK hynix                     | 566       | 24.4%   |
| Micron Technology            | 285       | 12.28%  |
| Kingston                     | 199       | 8.58%   |
| Crucial                      | 128       | 5.52%   |
| Unknown                      | 121       | 5.22%   |
| A-DATA Technology            | 93        | 4.01%   |
| Ramaxel Technology           | 87        | 3.75%   |
| Corsair                      | 86        | 3.71%   |
| Transcend                    | 50        | 2.16%   |
| CSX                          | 22        | 0.95%   |
| G.Skill                      | 21        | 0.91%   |
| Nanya Technology             | 17        | 0.73%   |
| Elpida                       | 16        | 0.69%   |
| Unknown (ABCD)               | 4         | 0.17%   |
| Silicon Power                | 4         | 0.17%   |
| OM Nanotech                  | 4         | 0.17%   |
| Avant                        | 3         | 0.13%   |
| ZION                         | 2         | 0.09%   |
| Kllisre                      | 2         | 0.09%   |
| ASint Technology             | 2         | 0.09%   |
| Apacer                       | 2         | 0.09%   |
| Unknown (0xAD44594E45540000) | 1         | 0.04%   |
| Unknown (0x1007)             | 1         | 0.04%   |
| Unknown (09D5)               | 1         | 0.04%   |
| Unknown (07F7)               | 1         | 0.04%   |
| Team                         | 1         | 0.04%   |
| Strontium                    | 1         | 0.04%   |
| SHARETRONIC                  | 1         | 0.04%   |
| Qumo                         | 1         | 0.04%   |
| Qimonda                      | 1         | 0.04%   |
| NETSOL                       | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| Gold Key                     | 1         | 0.04%   |
| Unknown                      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 65        | 2.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 53        | 2.17%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 50        | 2.05%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 38        | 1.56%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 37        | 1.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 37        | 1.52%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 30        | 1.23%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 26        | 1.07%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 26        | 1.07%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 25        | 1.02%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s    | 25        | 1.02%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s    | 25        | 1.02%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 24        | 0.98%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 24        | 0.98%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s       | 24        | 0.98%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 23        | 0.94%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 21        | 0.86%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 20        | 0.82%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 19        | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 17        | 0.7%    |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                    | 17        | 0.7%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s       | 17        | 0.7%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 17        | 0.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 16        | 0.66%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 16        | 0.66%   |
| Crucial RAM CB8GS2400.C8ET 8GB SODIMM DDR4 2667MT/s         | 16        | 0.66%   |
| Corsair RAM CMK16GX4M1D3000C16 16GB DIMM DDR4 3000MT/s      | 15        | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 13        | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s    | 13        | 0.53%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 13        | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 12        | 0.49%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s       | 12        | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 12        | 0.49%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 11        | 0.45%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 11        | 0.45%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 11        | 0.45%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 11        | 0.45%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 10        | 0.41%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 10        | 0.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 10        | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1195      | 62.4%   |
| DDR3    | 527       | 27.52%  |
| LPDDR4  | 61        | 3.19%   |
| SDRAM   | 46        | 2.4%    |
| DDR2    | 35        | 1.83%   |
| LPDDR3  | 24        | 1.25%   |
| Unknown | 17        | 0.89%   |
| DDR     | 5         | 0.26%   |
| DDR5    | 3         | 0.16%   |
| LPDDR5  | 2         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1430      | 75.42%  |
| DIMM         | 356       | 18.78%  |
| Row Of Chips | 105       | 5.54%   |
| Chip         | 2         | 0.11%   |
| Unknown      | 2         | 0.11%   |
| RIMM         | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 920       | 44.1%   |
| 4096  | 709       | 33.99%  |
| 16384 | 218       | 10.45%  |
| 2048  | 189       | 9.06%   |
| 1024  | 30        | 1.44%   |
| 32768 | 16        | 0.77%   |
| 512   | 3         | 0.14%   |
| 1536  | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 559       | 26.72%  |
| 1600    | 394       | 18.83%  |
| 3200    | 365       | 17.45%  |
| 2400    | 213       | 10.18%  |
| 1333    | 90        | 4.3%    |
| 2133    | 80        | 3.82%   |
| 3266    | 65        | 3.11%   |
| 1334    | 53        | 2.53%   |
| Unknown | 32        | 1.53%   |
| 2666    | 28        | 1.34%   |
| 667     | 26        | 1.24%   |
| 3600    | 20        | 0.96%   |
| 4199    | 18        | 0.86%   |
| 1067    | 18        | 0.86%   |
| 3000    | 16        | 0.76%   |
| 4267    | 15        | 0.72%   |
| 800     | 15        | 0.72%   |
| 1867    | 14        | 0.67%   |
| 2800    | 12        | 0.57%   |
| 3400    | 8         | 0.38%   |
| 1866    | 7         | 0.33%   |
| 975     | 6         | 0.29%   |
| 8400    | 4         | 0.19%   |
| 2048    | 4         | 0.19%   |
| 4800    | 3         | 0.14%   |
| 1066    | 3         | 0.14%   |
| 6400    | 2         | 0.1%    |
| 3733    | 2         | 0.1%    |
| 3066    | 2         | 0.1%    |
| 1800    | 2         | 0.1%    |
| 1648    | 2         | 0.1%    |
| 1400    | 2         | 0.1%    |
| 4266    | 1         | 0.05%   |
| 4000    | 1         | 0.05%   |
| 3666    | 1         | 0.05%   |
| 3467    | 1         | 0.05%   |
| 3466    | 1         | 0.05%   |
| 2933    | 1         | 0.05%   |
| 2733    | 1         | 0.05%   |
| 2200    | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 20        | 43.48%  |
| Seiko Epson         | 10        | 21.74%  |
| Canon               | 8         | 17.39%  |
| Brother Industries  | 4         | 8.7%    |
| STMicroelectronics  | 1         | 2.17%   |
| Samsung Electronics | 1         | 2.17%   |
| Ricoh               | 1         | 2.17%   |
| Konica Minolta      | 1         | 2.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                                      | 6         | 13.04%  |
| HP Ink Tank 310 series                                                | 3         | 6.52%   |
| Seiko Epson L380 Series                                               | 2         | 4.35%   |
| HP DeskJet 2130 series                                                | 2         | 4.35%   |
| HP DeskJet 1110 series                                                | 2         | 4.35%   |
| Canon PIXMA MG2500 Series                                             | 2         | 4.35%   |
| Canon LBP2900                                                         | 2         | 4.35%   |
| STMicroelectronics USB Printer P                                      | 1         | 2.17%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                                 | 1         | 2.17%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 2.17%   |
| Seiko Epson M100 Series                                               | 1         | 2.17%   |
| Seiko Epson L405 Series                                               | 1         | 2.17%   |
| Seiko Epson L3200 Series                                              | 1         | 2.17%   |
| Seiko Epson L3150 Series                                              | 1         | 2.17%   |
| Seiko Epson L222 Series                                               | 1         | 2.17%   |
| Seiko Epson L132 Series                                               | 1         | 2.17%   |
| Samsung ML-1640 Series Laser Printer                                  | 1         | 2.17%   |
| Ricoh SP 112SU                                                        | 1         | 2.17%   |
| Konica Minolta 206                                                    | 1         | 2.17%   |
| HP Smart Install                                                      | 1         | 2.17%   |
| HP Printing Support                                                   | 1         | 2.17%   |
| HP LaserJet Professional P1566                                        | 1         | 2.17%   |
| HP LaserJet Pro M202dw                                                | 1         | 2.17%   |
| HP DeskJet 3630 series                                                | 1         | 2.17%   |
| HP DeskJet 2620 All-in-One Printer                                    | 1         | 2.17%   |
| HP Deskjet 1510                                                       | 1         | 2.17%   |
| Canon PIXMA MP280                                                     | 1         | 2.17%   |
| Canon PIXMA MP190                                                     | 1         | 2.17%   |
| Canon MF4800 Series                                                   | 1         | 2.17%   |
| Canon G2000 series                                                    | 1         | 2.17%   |
| Brother Printer                                                       | 1         | 2.17%   |
| Brother HL-L2320D series                                              | 1         | 2.17%   |
| Brother DCP-T510W                                                     | 1         | 2.17%   |
| Brother DCP-T310                                                      | 1         | 2.17%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 75%     |
| Seiko Epson     | 1         | 12.5%   |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 517       | 19.01%  |
| IMC Networks                           | 377       | 13.86%  |
| Realtek Semiconductor                  | 292       | 10.74%  |
| Microdia                               | 272       | 10%     |
| Acer                                   | 170       | 6.25%   |
| Quanta                                 | 166       | 6.1%    |
| Sunplus Innovation Technology          | 155       | 5.7%    |
| Cheng Uei Precision Industry (Foxlink) | 137       | 5.04%   |
| Suyin                                  | 113       | 4.15%   |
| Syntek                                 | 107       | 3.93%   |
| Lite-On Technology                     | 55        | 2.02%   |
| Logitech                               | 52        | 1.91%   |
| Luxvisions Innotech Limited            | 44        | 1.62%   |
| Alcor Micro                            | 28        | 1.03%   |
| Samsung Electronics                    | 21        | 0.77%   |
| Apple                                  | 20        | 0.74%   |
| Silicon Motion                         | 19        | 0.7%    |
| Sonix Technology                       | 18        | 0.66%   |
| DJKANA19IDX53W                         | 17        | 0.63%   |
| Ricoh                                  | 14        | 0.51%   |
| Importek                               | 11        | 0.4%    |
| Z-Star Microelectronics                | 10        | 0.37%   |
| Lenovo                                 | 10        | 0.37%   |
| Primax Electronics                     | 9         | 0.33%   |
| Unknown                                | 8         | 0.29%   |
| OmniVision Technologies                | 8         | 0.29%   |
| Microsoft                              | 6         | 0.22%   |
| GEMBIRD                                | 6         | 0.22%   |
| Arkmicro Technologies                  | 6         | 0.22%   |
| SunplusIT                              | 4         | 0.15%   |
| Intel                                  | 4         | 0.15%   |
| Cubeternet                             | 4         | 0.15%   |
| Pixart Imaging                         | 3         | 0.11%   |
| MSD                                    | 3         | 0.11%   |
| Jieli Technology                       | 3         | 0.11%   |
| Spreadtrum Communications              | 2         | 0.07%   |
| Sony                                   | 2         | 0.07%   |
| MacroSilicon                           | 2         | 0.07%   |
| Holitech                               | 2         | 0.07%   |
| Hewlett-Packard                        | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 142       | 5.2%    |
| IMC Networks USB2.0 HD UVC WebCam                              | 120       | 4.4%    |
| Realtek Integrated_Webcam_HD                                   | 115       | 4.21%   |
| Chicony Integrated Camera                                      | 104       | 3.81%   |
| IMC Networks Integrated Camera                                 | 100       | 3.66%   |
| Sunplus Integrated_Webcam_HD                                   | 86        | 3.15%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 74        | 2.71%   |
| Syntek Integrated Camera                                       | 59        | 2.16%   |
| Realtek Integrated Webcam                                      | 56        | 2.05%   |
| Acer Integrated Camera                                         | 54        | 1.98%   |
| Chicony HP TrueVision HD Camera                                | 51        | 1.87%   |
| Chicony HP Truevision HD                                       | 50        | 1.83%   |
| Chicony HD WebCam                                              | 43        | 1.58%   |
| Chicony EasyCamera                                             | 41        | 1.5%    |
| Suyin HP TrueVision HD                                         | 38        | 1.39%   |
| Quanta HP TrueVision HD Camera                                 | 36        | 1.32%   |
| Quanta HD User Facing                                          | 35        | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 32        | 1.17%   |
| Logitech Webcam C270                                           | 30        | 1.1%    |
| Acer Lenovo EasyCamera                                         | 30        | 1.1%    |
| Syntek EasyCamera                                              | 29        | 1.06%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 28        | 1.03%   |
| Acer EasyCamera                                                | 28        | 1.03%   |
| Chicony HD User Facing                                         | 27        | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 27        | 0.99%   |
| Quanta HD Webcam                                               | 26        | 0.95%   |
| Lite-On Integrated Camera                                      | 25        | 0.92%   |
| Suyin Integrated_Webcam_HD                                     | 23        | 0.84%   |
| Quanta HP Wide Vision HD Camera                                | 22        | 0.81%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 22        | 0.81%   |
| Microdia Integrated Webcam                                     | 22        | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 21        | 0.77%   |
| Chicony HP Wide Vision HD Camera                               | 20        | 0.73%   |
| IMC Networks HP TrueVision HD Camera                           | 19        | 0.7%    |
| Chicony Integrated Camera (1280x720@30)                        | 19        | 0.7%    |
| Realtek Lenovo easy camera                                     | 18        | 0.66%   |
| IMC Networks VGA UVC WebCam                                    | 17        | 0.62%   |
| DJKANA19IDX53W HP Wide Vision HD Camera                        | 17        | 0.62%   |
| Sonix USB2.0 HD UVC WebCam                                     | 16        | 0.59%   |
| Acer SunplusIT Integrated Camera                               | 16        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 162       | 32.21%  |
| Synaptics                          | 115       | 22.86%  |
| Shenzhen Goodix Technology         | 103       | 20.48%  |
| Elan Microelectronics              | 70        | 13.92%  |
| LighTuning Technology              | 21        | 4.17%   |
| Upek                               | 10        | 1.99%   |
| AuthenTec                          | 10        | 1.99%   |
| Focal-systems.Corp                 | 5         | 0.99%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 0.8%    |
| STMicroelectronics                 | 1         | 0.2%    |
| Futronic Technology                | 1         | 0.2%    |
| DigitalPersona                     | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 50        | 9.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 47        | 9.34%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 8.95%   |
| Unknown                                                                    | 41        | 8.15%   |
| Elan ELAN:ARM-M4                                                           | 40        | 7.95%   |
| Elan ELAN:Fingerprint                                                      | 28        | 5.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 24        | 4.77%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 4.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 22        | 4.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 21        | 4.17%   |
| Synaptics  WBDI                                                            | 18        | 3.58%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 2.98%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 12        | 2.39%   |
| Validity Sensors VFS491                                                    | 10        | 1.99%   |
| Validity Sensors VFS Fingerprint sensor                                    | 10        | 1.99%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 1.99%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 1.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.59%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.19%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.19%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 1.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 0.99%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.99%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 5         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.99%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.8%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.8%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 0.8%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.6%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.6%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.4%    |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.4%    |
| AuthenTec AES1600                                                          | 2         | 0.4%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.2%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.2%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.2%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.2%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.2%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.2%    |
| Futronic FS81 Fingerprint Scanner Module                                   | 1         | 0.2%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 48        | 63.16%  |
| Alcor Micro | 15        | 19.74%  |
| Upek        | 6         | 7.89%   |
| O2 Micro    | 3         | 3.95%   |
| Lenovo      | 3         | 3.95%   |
| Clay Logic  | 1         | 1.32%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 23.38%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 19.48%  |
| Broadcom 5880                                                                | 13        | 16.88%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 12.99%  |
| Broadcom 58200                                                               | 8         | 10.39%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 7.79%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.9%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 2.6%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.3%    |
| Clay Logic Nitrokey HSM                                                      | 1         | 1.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2532      | 67.95%  |
| 1     | 1001      | 26.87%  |
| 2     | 150       | 4.03%   |
| 3     | 26        | 0.7%    |
| 4     | 10        | 0.27%   |
| 5     | 5         | 0.13%   |
| 9     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 498       | 35.5%   |
| Graphics card            | 313       | 22.31%  |
| Net/wireless             | 235       | 16.75%  |
| Chipcard                 | 73        | 5.2%    |
| Bluetooth                | 72        | 5.13%   |
| Multimedia controller    | 64        | 4.56%   |
| Communication controller | 47        | 3.35%   |
| Camera                   | 32        | 2.28%   |
| Net/ethernet             | 18        | 1.28%   |
| Sound                    | 17        | 1.21%   |
| Unassigned class         | 9         | 0.64%   |
| Storage                  | 8         | 0.57%   |
| Network                  | 6         | 0.43%   |
| Modem                    | 5         | 0.36%   |
| Card reader              | 3         | 0.21%   |
| Storage/raid             | 1         | 0.07%   |
| Storage/ide              | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

