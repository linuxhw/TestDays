Linux in Poland - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 6611

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B365M DS3H                  | Desktop     | [d515d5d9f7](https://linux-hardware.org/?probe=d515d5d9f7) | Feb 01, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [62f941075c](https://linux-hardware.org/?probe=62f941075c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [4e438c4768](https://linux-hardware.org/?probe=4e438c4768) | Jan 31, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [66459fc07c](https://linux-hardware.org/?probe=66459fc07c) | Jan 31, 2023 |
| ASUSTek       | Maximus VII GENE            | Desktop     | [c936c07925](https://linux-hardware.org/?probe=c936c07925) | Jan 31, 2023 |
| Dell          | Latitude 5410               | Notebook    | [717012530d](https://linux-hardware.org/?probe=717012530d) | Jan 31, 2023 |
| Unknown       | Unknown                     | Notebook    | [e6c824b966](https://linux-hardware.org/?probe=e6c824b966) | Jan 31, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [360dc83e04](https://linux-hardware.org/?probe=360dc83e04) | Jan 31, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [aaaa563786](https://linux-hardware.org/?probe=aaaa563786) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | Notebook    | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [e335e7282d](https://linux-hardware.org/?probe=e335e7282d) | Jan 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [d1e99e3f04](https://linux-hardware.org/?probe=d1e99e3f04) | Jan 30, 2023 |
| Toshiba       | Satellite P750              | Notebook    | [1cc0f342b5](https://linux-hardware.org/?probe=1cc0f342b5) | Jan 30, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [4cb11c2a78](https://linux-hardware.org/?probe=4cb11c2a78) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | Notebook    | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Inspiron 5758               | Notebook    | [de58233dca](https://linux-hardware.org/?probe=de58233dca) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| Dell          | Latitude 5480               | Notebook    | [ee87ac218f](https://linux-hardware.org/?probe=ee87ac218f) | Jan 30, 2023 |
| Dell          | Latitude 5480               | Notebook    | [3cbac640e1](https://linux-hardware.org/?probe=3cbac640e1) | Jan 30, 2023 |
| HP            | 8054                        | Desktop     | [f2367fdcda](https://linux-hardware.org/?probe=f2367fdcda) | Jan 30, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [81717ed3df](https://linux-hardware.org/?probe=81717ed3df) | Jan 30, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a2c721748](https://linux-hardware.org/?probe=5a2c721748) | Jan 30, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [56622f5d6c](https://linux-hardware.org/?probe=56622f5d6c) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [e5af375b93](https://linux-hardware.org/?probe=e5af375b93) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [41d67fcba8](https://linux-hardware.org/?probe=41d67fcba8) | Jan 29, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [1a2fb44fac](https://linux-hardware.org/?probe=1a2fb44fac) | Jan 29, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| ASUSTek       | 1215B                       | Notebook    | [8d26a8d157](https://linux-hardware.org/?probe=8d26a8d157) | Jan 28, 2023 |
| Dell          | 0HY9JP A00                  | Desktop     | [f4aefcd670](https://linux-hardware.org/?probe=f4aefcd670) | Jan 28, 2023 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [cf4086f3e4](https://linux-hardware.org/?probe=cf4086f3e4) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [f6d7ba9d48](https://linux-hardware.org/?probe=f6d7ba9d48) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ff5e2b673e](https://linux-hardware.org/?probe=ff5e2b673e) | Jan 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| ASUSTek       | X540SA                      | Notebook    | [93aed28230](https://linux-hardware.org/?probe=93aed28230) | Jan 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9001ac4e36](https://linux-hardware.org/?probe=9001ac4e36) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| HP            | x2 210 G2                   | Tablet      | [863136882e](https://linux-hardware.org/?probe=863136882e) | Jan 26, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [af3748a4f0](https://linux-hardware.org/?probe=af3748a4f0) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| HP            | 8054                        | Desktop     | [864f5f225e](https://linux-hardware.org/?probe=864f5f225e) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | Notebook    | [e4ddea6092](https://linux-hardware.org/?probe=e4ddea6092) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [4811286faf](https://linux-hardware.org/?probe=4811286faf) | Jan 26, 2023 |
| Dell          | XPS 9320                    | Notebook    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [baae797a05](https://linux-hardware.org/?probe=baae797a05) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [427a7fa0cb](https://linux-hardware.org/?probe=427a7fa0cb) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [7fcc3fb992](https://linux-hardware.org/?probe=7fcc3fb992) | Jan 25, 2023 |
| HP            | 3048h                       | Desktop     | [caabf4189f](https://linux-hardware.org/?probe=caabf4189f) | Jan 25, 2023 |
| Samsung       | R710                        | Notebook    | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | Latitude E6520              | Notebook    | [baf618d1a1](https://linux-hardware.org/?probe=baf618d1a1) | Jan 25, 2023 |
| ASRock        | 775XFire-VSTA               | Desktop     | [e80788f790](https://linux-hardware.org/?probe=e80788f790) | Jan 24, 2023 |
| Dell          | Latitude E6520              | Notebook    | [615879d5e9](https://linux-hardware.org/?probe=615879d5e9) | Jan 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | Notebook    | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [5ddcb9f78b](https://linux-hardware.org/?probe=5ddcb9f78b) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [9fcf89ea7c](https://linux-hardware.org/?probe=9fcf89ea7c) | Jan 23, 2023 |
| Dell          | Latitude E6500              | Notebook    | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a8d203f94b](https://linux-hardware.org/?probe=a8d203f94b) | Jan 23, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [c5da4a997d](https://linux-hardware.org/?probe=c5da4a997d) | Jan 23, 2023 |
| MSI           | B150 PC MATE                | Desktop     | [741901eb8f](https://linux-hardware.org/?probe=741901eb8f) | Jan 23, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [ffe1ffc80e](https://linux-hardware.org/?probe=ffe1ffc80e) | Jan 23, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c2f89a9e58](https://linux-hardware.org/?probe=c2f89a9e58) | Jan 23, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [3a42df71d0](https://linux-hardware.org/?probe=3a42df71d0) | Jan 22, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [076a3479fa](https://linux-hardware.org/?probe=076a3479fa) | Jan 22, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [f3d47cfb62](https://linux-hardware.org/?probe=f3d47cfb62) | Jan 22, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [d251029940](https://linux-hardware.org/?probe=d251029940) | Jan 22, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [d3686f2fc3](https://linux-hardware.org/?probe=d3686f2fc3) | Jan 21, 2023 |
| Dell          | Latitude 9420               | Notebook    | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Dell          | Latitude 5501               | Notebook    | [72581be7e7](https://linux-hardware.org/?probe=72581be7e7) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| HP            | Pavilion dv5                | Notebook    | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [b341182acd](https://linux-hardware.org/?probe=b341182acd) | Jan 20, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [9b4b20b28d](https://linux-hardware.org/?probe=9b4b20b28d) | Jan 20, 2023 |
| Lenovo        | ThinkPad P51 20HJS1EJ1B     | Notebook    | [2ac4b56c2f](https://linux-hardware.org/?probe=2ac4b56c2f) | Jan 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [6c55213012](https://linux-hardware.org/?probe=6c55213012) | Jan 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f935f0c7b](https://linux-hardware.org/?probe=1f935f0c7b) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Dell          | Precision M6600             | Notebook    | [4d697ebfd5](https://linux-hardware.org/?probe=4d697ebfd5) | Jan 19, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [6b5c46a680](https://linux-hardware.org/?probe=6b5c46a680) | Jan 19, 2023 |
| Huanan        | X99-TF V2.0                 | Desktop     | [3fa0103359](https://linux-hardware.org/?probe=3fa0103359) | Jan 19, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [a993e95dde](https://linux-hardware.org/?probe=a993e95dde) | Jan 19, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [1fd7f0acb7](https://linux-hardware.org/?probe=1fd7f0acb7) | Jan 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [16f5041f1d](https://linux-hardware.org/?probe=16f5041f1d) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | Desktop     | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [30698dacda](https://linux-hardware.org/?probe=30698dacda) | Jan 19, 2023 |
| Dell          | Latitude 9420               | Notebook    | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Alienware     | M17xR4                      | Notebook    | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Dell          | 0Y3R3K A00                  | Desktop     | [f2164a9c60](https://linux-hardware.org/?probe=f2164a9c60) | Jan 18, 2023 |
| Dell          | Precision 5750              | Notebook    | [592f9624d3](https://linux-hardware.org/?probe=592f9624d3) | Jan 18, 2023 |
| MSI           | GP65 Leopard 10SFK          | Notebook    | [3c09479564](https://linux-hardware.org/?probe=3c09479564) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [2ad3913a19](https://linux-hardware.org/?probe=2ad3913a19) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [6f463ee96b](https://linux-hardware.org/?probe=6f463ee96b) | Jan 18, 2023 |
| Dell          | Latitude D630               | Notebook    | [0d267a0217](https://linux-hardware.org/?probe=0d267a0217) | Jan 17, 2023 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [03a01ae5f7](https://linux-hardware.org/?probe=03a01ae5f7) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | Notebook    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [aa6ca0d358](https://linux-hardware.org/?probe=aa6ca0d358) | Jan 17, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [267ce15a0c](https://linux-hardware.org/?probe=267ce15a0c) | Jan 17, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [79b74ef79b](https://linux-hardware.org/?probe=79b74ef79b) | Jan 16, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [c159b4d65b](https://linux-hardware.org/?probe=c159b4d65b) | Jan 16, 2023 |
| Dell          | Latitude 3190               | Notebook    | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [94ba7a4ca6](https://linux-hardware.org/?probe=94ba7a4ca6) | Jan 16, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [be77d8e20d](https://linux-hardware.org/?probe=be77d8e20d) | Jan 15, 2023 |
| Lenovo        | ThinkPad T510 4384FF3       | Notebook    | [b62dac21bd](https://linux-hardware.org/?probe=b62dac21bd) | Jan 15, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [a1c627f81a](https://linux-hardware.org/?probe=a1c627f81a) | Jan 15, 2023 |
| Chuwi         | AeroBook Pro                | Notebook    | [13da35b0f7](https://linux-hardware.org/?probe=13da35b0f7) | Jan 15, 2023 |
| ASUSTek       | X510UQR                     | Notebook    | [2fb1d0a04c](https://linux-hardware.org/?probe=2fb1d0a04c) | Jan 14, 2023 |
| Acer          | AO725                       | Notebook    | [739986d5fa](https://linux-hardware.org/?probe=739986d5fa) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [f5499bf32a](https://linux-hardware.org/?probe=f5499bf32a) | Jan 14, 2023 |
| Gigabyte      | Z97M-D3H                    | Desktop     | [305ff29dad](https://linux-hardware.org/?probe=305ff29dad) | Jan 14, 2023 |
| Lenovo        | G585                        | Notebook    | [c7453a5e19](https://linux-hardware.org/?probe=c7453a5e19) | Jan 14, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [5e408d7d3d](https://linux-hardware.org/?probe=5e408d7d3d) | Jan 14, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [5bcda073b3](https://linux-hardware.org/?probe=5bcda073b3) | Jan 13, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3f68ef3681](https://linux-hardware.org/?probe=3f68ef3681) | Jan 13, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [c1e0fd9216](https://linux-hardware.org/?probe=c1e0fd9216) | Jan 13, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [6cc45bde0b](https://linux-hardware.org/?probe=6cc45bde0b) | Jan 13, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [61b7459a43](https://linux-hardware.org/?probe=61b7459a43) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Samsung       | SR700                       | Notebook    | [329a7864c0](https://linux-hardware.org/?probe=329a7864c0) | Jan 13, 2023 |
| HP            | Notebook                    | Notebook    | [3fc38fa55e](https://linux-hardware.org/?probe=3fc38fa55e) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eeeb041ca6](https://linux-hardware.org/?probe=eeeb041ca6) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | Notebook    | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [3dcb242fd6](https://linux-hardware.org/?probe=3dcb242fd6) | Jan 12, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [8dce1e9fdd](https://linux-hardware.org/?probe=8dce1e9fdd) | Jan 12, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ffd5ad6744](https://linux-hardware.org/?probe=ffd5ad6744) | Jan 12, 2023 |
| Lenovo        | Legion Y740S-15IMH 81YX     | Notebook    | [b61eb04be5](https://linux-hardware.org/?probe=b61eb04be5) | Jan 11, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [366e5b92d7](https://linux-hardware.org/?probe=366e5b92d7) | Jan 11, 2023 |
| Sony          | VPCEJ2S1E                   | Notebook    | [f387a3dcf6](https://linux-hardware.org/?probe=f387a3dcf6) | Jan 11, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [e3478b20bd](https://linux-hardware.org/?probe=e3478b20bd) | Jan 11, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [78153a929d](https://linux-hardware.org/?probe=78153a929d) | Jan 11, 2023 |
| ASUSTek       | PRIME B660M-K D4            | Desktop     | [f3fe7611d3](https://linux-hardware.org/?probe=f3fe7611d3) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [140d48870a](https://linux-hardware.org/?probe=140d48870a) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | Notebook    | [f6588e6319](https://linux-hardware.org/?probe=f6588e6319) | Jan 11, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [c6ffd59fb2](https://linux-hardware.org/?probe=c6ffd59fb2) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b828defe64](https://linux-hardware.org/?probe=b828defe64) | Jan 11, 2023 |
| Dell          | Latitude D630               | Notebook    | [64877fdf78](https://linux-hardware.org/?probe=64877fdf78) | Jan 11, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [a4ab96067d](https://linux-hardware.org/?probe=a4ab96067d) | Jan 10, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [2aa757ef35](https://linux-hardware.org/?probe=2aa757ef35) | Jan 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [eefd133e1f](https://linux-hardware.org/?probe=eefd133e1f) | Jan 10, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [33529c6c45](https://linux-hardware.org/?probe=33529c6c45) | Jan 10, 2023 |
| Acer          | Extensa 2540                | Notebook    | [6bddd00c3f](https://linux-hardware.org/?probe=6bddd00c3f) | Jan 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b65fef1f25](https://linux-hardware.org/?probe=b65fef1f25) | Jan 10, 2023 |
| Dell          | Latitude E4310              | Notebook    | [1cd2d3300a](https://linux-hardware.org/?probe=1cd2d3300a) | Jan 09, 2023 |
| Dell          | Latitude E5470              | Notebook    | [41c1a02ca6](https://linux-hardware.org/?probe=41c1a02ca6) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | Notebook    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| Lenovo        | ThinkPad X201 3626D15       | Notebook    | [3d615a1b12](https://linux-hardware.org/?probe=3d615a1b12) | Jan 09, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [045695f1d5](https://linux-hardware.org/?probe=045695f1d5) | Jan 09, 2023 |
| Dell          | 088DT1 A00                  | Desktop     | [f7632cc6ba](https://linux-hardware.org/?probe=f7632cc6ba) | Jan 09, 2023 |
| Dell          | Latitude 3190               | Notebook    | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| Dell          | Latitude 7330               | Convertible | [02cef1bed5](https://linux-hardware.org/?probe=02cef1bed5) | Jan 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [aac6fb4537](https://linux-hardware.org/?probe=aac6fb4537) | Jan 09, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| Samsung       | R780/R778                   | Notebook    | [e26d6dd084](https://linux-hardware.org/?probe=e26d6dd084) | Jan 08, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| Lenovo        | G51-35 80M8                 | Notebook    | [fe19098e1d](https://linux-hardware.org/?probe=fe19098e1d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS0BX0T    | Notebook    | [e05bd2254f](https://linux-hardware.org/?probe=e05bd2254f) | Jan 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [de3c61df29](https://linux-hardware.org/?probe=de3c61df29) | Jan 08, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [9bbe57d371](https://linux-hardware.org/?probe=9bbe57d371) | Jan 08, 2023 |
| HP            | 655                         | Notebook    | [4c7544d7ad](https://linux-hardware.org/?probe=4c7544d7ad) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [c0c15dd0d0](https://linux-hardware.org/?probe=c0c15dd0d0) | Jan 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [459862f611](https://linux-hardware.org/?probe=459862f611) | Jan 08, 2023 |
| ZOTAC         | ZBOX-MI623/MI643 Rev.00     | Mini pc     | [9750302f80](https://linux-hardware.org/?probe=9750302f80) | Jan 07, 2023 |
| HP            | ENVY m6                     | Notebook    | [b5089c7b29](https://linux-hardware.org/?probe=b5089c7b29) | Jan 07, 2023 |
| MSI           | MS-AC7B1 100                | All in one  | [7df138e48a](https://linux-hardware.org/?probe=7df138e48a) | Jan 07, 2023 |
| HP            | ProBook 5330m               | Notebook    | [37416931cd](https://linux-hardware.org/?probe=37416931cd) | Jan 07, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0f51a2d7d5](https://linux-hardware.org/?probe=0f51a2d7d5) | Jan 07, 2023 |
| Gigabyte      | Z97X-UD5H-BK                | Desktop     | [531eaa88b5](https://linux-hardware.org/?probe=531eaa88b5) | Jan 07, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| MSI           | Z590 PRO WIFI               | Desktop     | [98af54429b](https://linux-hardware.org/?probe=98af54429b) | Jan 07, 2023 |
| Lenovo        | S145-15API 81UT             | Notebook    | [fafc9e3fb7](https://linux-hardware.org/?probe=fafc9e3fb7) | Jan 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [fd20c9e982](https://linux-hardware.org/?probe=fd20c9e982) | Jan 07, 2023 |
| Huanan        | X99-F8 NALEX, NALEX         | Desktop     | [e59b16e379](https://linux-hardware.org/?probe=e59b16e379) | Jan 06, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [e8147a271c](https://linux-hardware.org/?probe=e8147a271c) | Jan 06, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e0e6ab58b6](https://linux-hardware.org/?probe=e0e6ab58b6) | Jan 06, 2023 |
| Fujitsu       | D3430-A1 S26361-D3430-A1    | Desktop     | [2df76bde47](https://linux-hardware.org/?probe=2df76bde47) | Jan 06, 2023 |
| Dell          | Latitude E6520              | Notebook    | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [d0299b2518](https://linux-hardware.org/?probe=d0299b2518) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [bb78c165c7](https://linux-hardware.org/?probe=bb78c165c7) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [117e9ffed7](https://linux-hardware.org/?probe=117e9ffed7) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [cacdaaf5c5](https://linux-hardware.org/?probe=cacdaaf5c5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | Notebook    | [bbedda14e5](https://linux-hardware.org/?probe=bbedda14e5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | Notebook    | [d2c2a681a2](https://linux-hardware.org/?probe=d2c2a681a2) | Jan 05, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [e0cf0ea368](https://linux-hardware.org/?probe=e0cf0ea368) | Jan 05, 2023 |
| Dell          | 0Y3R3K A00                  | Desktop     | [8337b0691c](https://linux-hardware.org/?probe=8337b0691c) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | Notebook    | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [307c51149d](https://linux-hardware.org/?probe=307c51149d) | Jan 03, 2023 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [96150fc8a5](https://linux-hardware.org/?probe=96150fc8a5) | Jan 03, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1a3964dd30](https://linux-hardware.org/?probe=1a3964dd30) | Jan 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5f0eeeb9e7](https://linux-hardware.org/?probe=5f0eeeb9e7) | Jan 03, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [bd3d76fa53](https://linux-hardware.org/?probe=bd3d76fa53) | Jan 03, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [b45f76c172](https://linux-hardware.org/?probe=b45f76c172) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | Notebook    | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| HP            | 304Bh                       | Desktop     | [cfe1407faf](https://linux-hardware.org/?probe=cfe1407faf) | Jan 02, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [eb3f1a0f5f](https://linux-hardware.org/?probe=eb3f1a0f5f) | Jan 02, 2023 |
| Dell          | Latitude 3190               | Notebook    | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | Notebook    | [c331237e28](https://linux-hardware.org/?probe=c331237e28) | Jan 02, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [92052e9c47](https://linux-hardware.org/?probe=92052e9c47) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | Notebook    | [1ce680cb4d](https://linux-hardware.org/?probe=1ce680cb4d) | Jan 01, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [24d32a2b05](https://linux-hardware.org/?probe=24d32a2b05) | Jan 01, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [8c4c07c555](https://linux-hardware.org/?probe=8c4c07c555) | Jan 01, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [0a4b320a9e](https://linux-hardware.org/?probe=0a4b320a9e) | Dec 31, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [1347eaedb9](https://linux-hardware.org/?probe=1347eaedb9) | Dec 31, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [4393041949](https://linux-hardware.org/?probe=4393041949) | Dec 30, 2022 |
| ASUSTek       | K72F                        | Notebook    | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9a05e8c413](https://linux-hardware.org/?probe=9a05e8c413) | Dec 30, 2022 |
| HP            | EliteBook 745 G5            | Notebook    | [d819dbd901](https://linux-hardware.org/?probe=d819dbd901) | Dec 30, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [28aede6faf](https://linux-hardware.org/?probe=28aede6faf) | Dec 29, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [ca7468f975](https://linux-hardware.org/?probe=ca7468f975) | Dec 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9b264f00f0](https://linux-hardware.org/?probe=9b264f00f0) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [fdb09844e9](https://linux-hardware.org/?probe=fdb09844e9) | Dec 29, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [9ff3461c31](https://linux-hardware.org/?probe=9ff3461c31) | Dec 29, 2022 |
| Dell          | Latitude E6420              | Notebook    | [9733c425b6](https://linux-hardware.org/?probe=9733c425b6) | Dec 29, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | Notebook    | [e232c2de6d](https://linux-hardware.org/?probe=e232c2de6d) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [95555948a2](https://linux-hardware.org/?probe=95555948a2) | Dec 27, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [06cba3f478](https://linux-hardware.org/?probe=06cba3f478) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | Notebook    | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [031a62faa8](https://linux-hardware.org/?probe=031a62faa8) | Dec 27, 2022 |
| ASRock        | Z390M-ITX/ac                | Desktop     | [23d6589918](https://linux-hardware.org/?probe=23d6589918) | Dec 27, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [02f55ff55b](https://linux-hardware.org/?probe=02f55ff55b) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [e0a09344e0](https://linux-hardware.org/?probe=e0a09344e0) | Dec 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5d2498f405](https://linux-hardware.org/?probe=5d2498f405) | Dec 26, 2022 |
| ASUSTek       | M4A88T-V EVO/USB3           | Desktop     | [05163a2fb9](https://linux-hardware.org/?probe=05163a2fb9) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [d6948e7207](https://linux-hardware.org/?probe=d6948e7207) | Dec 26, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [315cef73cd](https://linux-hardware.org/?probe=315cef73cd) | Dec 25, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [249f50d430](https://linux-hardware.org/?probe=249f50d430) | Dec 25, 2022 |
| Lenovo        | ThinkPad T430 23472Y0       | Notebook    | [4a2d13391c](https://linux-hardware.org/?probe=4a2d13391c) | Dec 25, 2022 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [5ca8ddb512](https://linux-hardware.org/?probe=5ca8ddb512) | Dec 24, 2022 |
| Xiaomi        | Pocophone F1 (Tianma)       | Soc         | [85b5b184bb](https://linux-hardware.org/?probe=85b5b184bb) | Dec 24, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [38ed4755c3](https://linux-hardware.org/?probe=38ed4755c3) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [0836c3b800](https://linux-hardware.org/?probe=0836c3b800) | Dec 23, 2022 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [b721ac26e2](https://linux-hardware.org/?probe=b721ac26e2) | Dec 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c17fe8cbe0](https://linux-hardware.org/?probe=c17fe8cbe0) | Dec 23, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0277928378](https://linux-hardware.org/?probe=0277928378) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [87da3fdf4d](https://linux-hardware.org/?probe=87da3fdf4d) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [bf600b6f1c](https://linux-hardware.org/?probe=bf600b6f1c) | Dec 22, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [0cb3ccf545](https://linux-hardware.org/?probe=0cb3ccf545) | Dec 21, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9ada5592f6](https://linux-hardware.org/?probe=9ada5592f6) | Dec 21, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [06d78a17c1](https://linux-hardware.org/?probe=06d78a17c1) | Dec 21, 2022 |
| Dell          | Precision 3520              | Notebook    | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | Notebook    | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | 8266                        | Desktop     | [321dbc66bf](https://linux-hardware.org/?probe=321dbc66bf) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [b1d6a6a73d](https://linux-hardware.org/?probe=b1d6a6a73d) | Dec 21, 2022 |
| ASUSTek       | PRIME X399-A                | Desktop     | [243fccb6fa](https://linux-hardware.org/?probe=243fccb6fa) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [bbec56fa90](https://linux-hardware.org/?probe=bbec56fa90) | Dec 21, 2022 |
| Dell          | G15 5510                    | Notebook    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming FX505GE          | Notebook    | [094e72dc22](https://linux-hardware.org/?probe=094e72dc22) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [37513092d6](https://linux-hardware.org/?probe=37513092d6) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [70a0e2a296](https://linux-hardware.org/?probe=70a0e2a296) | Dec 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [44a96b54b6](https://linux-hardware.org/?probe=44a96b54b6) | Dec 18, 2022 |
| HP            | ProLiant ML350 G6           | Desktop     | [58113862ee](https://linux-hardware.org/?probe=58113862ee) | Dec 18, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [8c0c2353ab](https://linux-hardware.org/?probe=8c0c2353ab) | Dec 18, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [85d6221160](https://linux-hardware.org/?probe=85d6221160) | Dec 18, 2022 |
| Foxconn       | A76GMV                      | Desktop     | [722a9911f8](https://linux-hardware.org/?probe=722a9911f8) | Dec 18, 2022 |
| Valve         | Jupiter                     | Notebook    | [72f897b9d3](https://linux-hardware.org/?probe=72f897b9d3) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [2e3cc90610](https://linux-hardware.org/?probe=2e3cc90610) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| MSI           | A88XM-E35                   | Desktop     | [f0efaa3c30](https://linux-hardware.org/?probe=f0efaa3c30) | Dec 17, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [0df6f80110](https://linux-hardware.org/?probe=0df6f80110) | Dec 17, 2022 |
| Dell          | Latitude E5570              | Notebook    | [cc58177561](https://linux-hardware.org/?probe=cc58177561) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| POSIFLEX      | KK-3703 D0                  | Desktop     | [8ce9910b00](https://linux-hardware.org/?probe=8ce9910b00) | Dec 16, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1860105d14](https://linux-hardware.org/?probe=1860105d14) | Dec 16, 2022 |
| Dell          | Latitude E6410              | Notebook    | [173f8a8dc8](https://linux-hardware.org/?probe=173f8a8dc8) | Dec 16, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| Dell          | Latitude 7330               | Convertible | [b3956235ae](https://linux-hardware.org/?probe=b3956235ae) | Dec 15, 2022 |
| Dell          | Latitude 5420               | Notebook    | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | Notebook    | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ad1e402db3](https://linux-hardware.org/?probe=ad1e402db3) | Dec 15, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [f0e99676be](https://linux-hardware.org/?probe=f0e99676be) | Dec 14, 2022 |
| Gigabyte      | MMLP3AP-00                  | Notebook    | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| Google        | Ultima                      | Notebook    | [867abc2b8f](https://linux-hardware.org/?probe=867abc2b8f) | Dec 14, 2022 |
| ASUSTek       | M3N                         | Notebook    | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [a607679697](https://linux-hardware.org/?probe=a607679697) | Dec 14, 2022 |
| Inventec      | D CLASS A02                 | Desktop     | [9bd8fecf82](https://linux-hardware.org/?probe=9bd8fecf82) | Dec 14, 2022 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [b7fa78df7a](https://linux-hardware.org/?probe=b7fa78df7a) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX2/CSM             | Desktop     | [cc6e7dae77](https://linux-hardware.org/?probe=cc6e7dae77) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | Notebook    | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| ASUSTek       | M3N                         | Notebook    | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [37284f659a](https://linux-hardware.org/?probe=37284f659a) | Dec 13, 2022 |
| Dell          | Latitude 7330               | Convertible | [95aea2b219](https://linux-hardware.org/?probe=95aea2b219) | Dec 12, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [61685b4f1a](https://linux-hardware.org/?probe=61685b4f1a) | Dec 12, 2022 |
| Dell          | Latitude 5411               | Notebook    | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Dell          | Latitude 5411               | Notebook    | [334ca886a4](https://linux-hardware.org/?probe=334ca886a4) | Dec 12, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Dell          | Latitude 7330               | Convertible | [3bd7f5734d](https://linux-hardware.org/?probe=3bd7f5734d) | Dec 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [177dded9e0](https://linux-hardware.org/?probe=177dded9e0) | Dec 12, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [c94af57999](https://linux-hardware.org/?probe=c94af57999) | Dec 11, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [cea4c76b9d](https://linux-hardware.org/?probe=cea4c76b9d) | Dec 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [6f97813144](https://linux-hardware.org/?probe=6f97813144) | Dec 10, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [ffb030fbbf](https://linux-hardware.org/?probe=ffb030fbbf) | Dec 10, 2022 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [ef403a3962](https://linux-hardware.org/?probe=ef403a3962) | Dec 10, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [50ccab1267](https://linux-hardware.org/?probe=50ccab1267) | Dec 10, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [fe9424a1f0](https://linux-hardware.org/?probe=fe9424a1f0) | Dec 09, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [0dc9bb1cf4](https://linux-hardware.org/?probe=0dc9bb1cf4) | Dec 09, 2022 |
| Dell          | Latitude 7330               | Convertible | [67bbcec9fd](https://linux-hardware.org/?probe=67bbcec9fd) | Dec 09, 2022 |
| Lenovo        | ThinkCentre M70e 0829RB4    | Desktop     | [5a5b271c35](https://linux-hardware.org/?probe=5a5b271c35) | Dec 09, 2022 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [b9e3c45caa](https://linux-hardware.org/?probe=b9e3c45caa) | Dec 09, 2022 |
| Dell          | 0PM2CW A02                  | Server      | [460791d797](https://linux-hardware.org/?probe=460791d797) | Dec 08, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [93075de512](https://linux-hardware.org/?probe=93075de512) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | Notebook    | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| Google        | Glimmer                     | Notebook    | [ad4b3f5575](https://linux-hardware.org/?probe=ad4b3f5575) | Dec 08, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [e15b555b1a](https://linux-hardware.org/?probe=e15b555b1a) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Dell          | Latitude 5480               | Notebook    | [0cd7d6e4c0](https://linux-hardware.org/?probe=0cd7d6e4c0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | Notebook    | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [9a859c9a5d](https://linux-hardware.org/?probe=9a859c9a5d) | Dec 06, 2022 |
| Dell          | Latitude 5310               | Notebook    | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| Dell          | Latitude E7440              | Notebook    | [63b84a9439](https://linux-hardware.org/?probe=63b84a9439) | Dec 06, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e64c5d7bdc](https://linux-hardware.org/?probe=e64c5d7bdc) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [798cf690c5](https://linux-hardware.org/?probe=798cf690c5) | Dec 06, 2022 |
| Dell          | Latitude 5411               | Notebook    | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | Notebook    | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | Notebook    | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [091b8a3a8a](https://linux-hardware.org/?probe=091b8a3a8a) | Dec 05, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [aadffecf5b](https://linux-hardware.org/?probe=aadffecf5b) | Dec 05, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [a4a47ea164](https://linux-hardware.org/?probe=a4a47ea164) | Dec 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [119ec75a5f](https://linux-hardware.org/?probe=119ec75a5f) | Dec 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| HP            | ProLiant ML350e Gen8        | Desktop     | [984fe41e3c](https://linux-hardware.org/?probe=984fe41e3c) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [a849daba2b](https://linux-hardware.org/?probe=a849daba2b) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [6c726b6eb7](https://linux-hardware.org/?probe=6c726b6eb7) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [99b35ee6a3](https://linux-hardware.org/?probe=99b35ee6a3) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [ce36bcdf8b](https://linux-hardware.org/?probe=ce36bcdf8b) | Dec 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7a47529fdc](https://linux-hardware.org/?probe=7a47529fdc) | Dec 04, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | Notebook    | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [afbbf473b9](https://linux-hardware.org/?probe=afbbf473b9) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Gigabyte      | B650E AORUS MASTER se2      | Desktop     | [101ea2715c](https://linux-hardware.org/?probe=101ea2715c) | Dec 04, 2022 |
| pine64,roc... | RockPro64 v2.1              | Soc         | [9973baf711](https://linux-hardware.org/?probe=9973baf711) | Dec 04, 2022 |
| ACTION        | ACTINA GA-G31M-S2L          | Desktop     | [2a2934f919](https://linux-hardware.org/?probe=2a2934f919) | Dec 04, 2022 |
| HP            | Pavilion dv7                | Notebook    | [90c7688386](https://linux-hardware.org/?probe=90c7688386) | Dec 04, 2022 |
| Google        | Lars                        | Notebook    | [efe9cef4b9](https://linux-hardware.org/?probe=efe9cef4b9) | Dec 04, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0455f2c685](https://linux-hardware.org/?probe=0455f2c685) | Dec 04, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [84a50cd483](https://linux-hardware.org/?probe=84a50cd483) | Dec 03, 2022 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [10315500be](https://linux-hardware.org/?probe=10315500be) | Dec 03, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f8dacfeca3](https://linux-hardware.org/?probe=f8dacfeca3) | Dec 03, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [ec5047129a](https://linux-hardware.org/?probe=ec5047129a) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Google        | Lars                        | Notebook    | [ad022bfd93](https://linux-hardware.org/?probe=ad022bfd93) | Dec 03, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [6578471259](https://linux-hardware.org/?probe=6578471259) | Dec 03, 2022 |
| Dell          | G15 5515                    | Notebook    | [218e5c2825](https://linux-hardware.org/?probe=218e5c2825) | Dec 03, 2022 |
| Dell          | Latitude 5480               | Notebook    | [4eba5810d7](https://linux-hardware.org/?probe=4eba5810d7) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [9990900d63](https://linux-hardware.org/?probe=9990900d63) | Dec 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7177c55be0](https://linux-hardware.org/?probe=7177c55be0) | Dec 02, 2022 |
| Dell          | Vostro 5502                 | Notebook    | [86341e8306](https://linux-hardware.org/?probe=86341e8306) | Dec 02, 2022 |
| MSI           | A68HM-E33                   | Desktop     | [4e2313d8b7](https://linux-hardware.org/?probe=4e2313d8b7) | Dec 02, 2022 |
| HP            | 0A98h                       | Desktop     | [e1413607aa](https://linux-hardware.org/?probe=e1413607aa) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4d33c2ab30](https://linux-hardware.org/?probe=4d33c2ab30) | Dec 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [8a25bf4545](https://linux-hardware.org/?probe=8a25bf4545) | Dec 01, 2022 |
| HP            | 0A98h                       | Desktop     | [f2b620c220](https://linux-hardware.org/?probe=f2b620c220) | Dec 01, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| HP            | Pavilion dv7                | Notebook    | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| Fujitsu       | D2917-A1 S26361-D2917-A1    | Desktop     | [dd124e3579](https://linux-hardware.org/?probe=dd124e3579) | Nov 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [a5b34b67f2](https://linux-hardware.org/?probe=a5b34b67f2) | Nov 30, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [3aa3302b92](https://linux-hardware.org/?probe=3aa3302b92) | Nov 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c3d55f501c](https://linux-hardware.org/?probe=c3d55f501c) | Nov 30, 2022 |
| MACHINIST     | X99-D8-MAX V1.0             | Desktop     | [c2430965a1](https://linux-hardware.org/?probe=c2430965a1) | Nov 30, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [f0dfa48048](https://linux-hardware.org/?probe=f0dfa48048) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | Notebook    | [802af80043](https://linux-hardware.org/?probe=802af80043) | Nov 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| Dell          | Latitude E6540              | Notebook    | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| HP            | Pavilion dv7                | Notebook    | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [56ceffe338](https://linux-hardware.org/?probe=56ceffe338) | Nov 28, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| HUAWEI        | MRC-WX0                     | Notebook    | [98f550465b](https://linux-hardware.org/?probe=98f550465b) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [6bf87b9885](https://linux-hardware.org/?probe=6bf87b9885) | Nov 28, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [1a316a1239](https://linux-hardware.org/?probe=1a316a1239) | Nov 27, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [87ef485975](https://linux-hardware.org/?probe=87ef485975) | Nov 27, 2022 |
| Acer          | AO722                       | Notebook    | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| HP            | ProBook 6470b               | Notebook    | [c8da54315e](https://linux-hardware.org/?probe=c8da54315e) | Nov 26, 2022 |
| Dell          | Latitude E6220              | Notebook    | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | Notebook    | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | Notebook    | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | Notebook    | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1bd15590c9](https://linux-hardware.org/?probe=1bd15590c9) | Nov 25, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [a17a108297](https://linux-hardware.org/?probe=a17a108297) | Nov 25, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [2b7bb89689](https://linux-hardware.org/?probe=2b7bb89689) | Nov 25, 2022 |
| HP            | 2215                        | Desktop     | [0134898651](https://linux-hardware.org/?probe=0134898651) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | Notebook    | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| HP            | 213D A01                    | Desktop     | [b0c45fb200](https://linux-hardware.org/?probe=b0c45fb200) | Nov 24, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [b154300490](https://linux-hardware.org/?probe=b154300490) | Nov 24, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Dell          | Latitude 5310               | Notebook    | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| Unknown       | HX90                        | Desktop     | [e1bd045aaa](https://linux-hardware.org/?probe=e1bd045aaa) | Nov 24, 2022 |
| ASUSTek       | K51AC                       | Notebook    | [0b2413e13c](https://linux-hardware.org/?probe=0b2413e13c) | Nov 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ca7045ed57](https://linux-hardware.org/?probe=ca7045ed57) | Nov 24, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [d2d484b35b](https://linux-hardware.org/?probe=d2d484b35b) | Nov 24, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [e7717a62cb](https://linux-hardware.org/?probe=e7717a62cb) | Nov 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [ac72570183](https://linux-hardware.org/?probe=ac72570183) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | Notebook    | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Pavilion dv6                | Notebook    | [e3921e4da9](https://linux-hardware.org/?probe=e3921e4da9) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [51ca9fa048](https://linux-hardware.org/?probe=51ca9fa048) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [0ca1ce1d74](https://linux-hardware.org/?probe=0ca1ce1d74) | Nov 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6d217fbd52](https://linux-hardware.org/?probe=6d217fbd52) | Nov 23, 2022 |
| ASRock        | H410M-HVS R2.0              | Desktop     | [3f381f9fa3](https://linux-hardware.org/?probe=3f381f9fa3) | Nov 23, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [7dd9d3bec3](https://linux-hardware.org/?probe=7dd9d3bec3) | Nov 23, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [17b880ceb9](https://linux-hardware.org/?probe=17b880ceb9) | Nov 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [ad63d86cb9](https://linux-hardware.org/?probe=ad63d86cb9) | Nov 23, 2022 |
| HP            | G5000 (GF783EA#AKD)         | Notebook    | [2437328d23](https://linux-hardware.org/?probe=2437328d23) | Nov 22, 2022 |
| Dell          | Latitude 3420               | Notebook    | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [c345afe01a](https://linux-hardware.org/?probe=c345afe01a) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [e36ab20d8c](https://linux-hardware.org/?probe=e36ab20d8c) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [014cf9f78d](https://linux-hardware.org/?probe=014cf9f78d) | Nov 22, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [a38b2f2f2a](https://linux-hardware.org/?probe=a38b2f2f2a) | Nov 22, 2022 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [24d16fa5df](https://linux-hardware.org/?probe=24d16fa5df) | Nov 22, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a5dcbbbacd](https://linux-hardware.org/?probe=a5dcbbbacd) | Nov 22, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [26ac531682](https://linux-hardware.org/?probe=26ac531682) | Nov 22, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [4743344f41](https://linux-hardware.org/?probe=4743344f41) | Nov 22, 2022 |
| Dell          | 0PU052                      | Desktop     | [b54afc7e1a](https://linux-hardware.org/?probe=b54afc7e1a) | Nov 21, 2022 |
| Dell          | Latitude 5410               | Notebook    | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Dell          | Latitude 5490               | Notebook    | [295073cd07](https://linux-hardware.org/?probe=295073cd07) | Nov 21, 2022 |
| Dell          | Latitude 5310               | Notebook    | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [64cff39a82](https://linux-hardware.org/?probe=64cff39a82) | Nov 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [0a98e4cae4](https://linux-hardware.org/?probe=0a98e4cae4) | Nov 21, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [d74e4882d8](https://linux-hardware.org/?probe=d74e4882d8) | Nov 21, 2022 |
| Dell          | Latitude 3190               | Notebook    | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [740b4f9f03](https://linux-hardware.org/?probe=740b4f9f03) | Nov 20, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [aa4bde7d79](https://linux-hardware.org/?probe=aa4bde7d79) | Nov 20, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [3f18cccea5](https://linux-hardware.org/?probe=3f18cccea5) | Nov 20, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2030d33f00](https://linux-hardware.org/?probe=2030d33f00) | Nov 20, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [75a8f2a500](https://linux-hardware.org/?probe=75a8f2a500) | Nov 20, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [05f54bd8da](https://linux-hardware.org/?probe=05f54bd8da) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d8f53f887a](https://linux-hardware.org/?probe=d8f53f887a) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c967893dd4](https://linux-hardware.org/?probe=c967893dd4) | Nov 20, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [08372f6535](https://linux-hardware.org/?probe=08372f6535) | Nov 20, 2022 |
| Intel         | NUC8i7HVB J68196-502        | Mini pc     | [8c73ebd2b9](https://linux-hardware.org/?probe=8c73ebd2b9) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [1af7bd26fd](https://linux-hardware.org/?probe=1af7bd26fd) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | Notebook    | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ad7abfb8cb](https://linux-hardware.org/?probe=ad7abfb8cb) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [598f8e7c34](https://linux-hardware.org/?probe=598f8e7c34) | Nov 19, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [bc46ec232a](https://linux-hardware.org/?probe=bc46ec232a) | Nov 18, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [c2ad29d3e8](https://linux-hardware.org/?probe=c2ad29d3e8) | Nov 18, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [74a3983b1e](https://linux-hardware.org/?probe=74a3983b1e) | Nov 18, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| ASRock        | X670E Pro RS                | Desktop     | [bfccdbd536](https://linux-hardware.org/?probe=bfccdbd536) | Nov 17, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bb2db87e9a](https://linux-hardware.org/?probe=bb2db87e9a) | Nov 17, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [203df386a1](https://linux-hardware.org/?probe=203df386a1) | Nov 17, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [105a376344](https://linux-hardware.org/?probe=105a376344) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [cdf4d49427](https://linux-hardware.org/?probe=cdf4d49427) | Nov 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | Notebook    | [fe520ea826](https://linux-hardware.org/?probe=fe520ea826) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [b5eb364ac6](https://linux-hardware.org/?probe=b5eb364ac6) | Nov 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [4ab915f825](https://linux-hardware.org/?probe=4ab915f825) | Nov 15, 2022 |
| Dell          | 0PU052                      | Desktop     | [802c39b94f](https://linux-hardware.org/?probe=802c39b94f) | Nov 15, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ea39f5300c](https://linux-hardware.org/?probe=ea39f5300c) | Nov 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d07cacacde](https://linux-hardware.org/?probe=d07cacacde) | Nov 15, 2022 |
| HP            | 22F8                        | Desktop     | [754ebee9c8](https://linux-hardware.org/?probe=754ebee9c8) | Nov 14, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7f21362848](https://linux-hardware.org/?probe=7f21362848) | Nov 14, 2022 |
| HP            | ProBook 6450b               | Notebook    | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [e53d77c404](https://linux-hardware.org/?probe=e53d77c404) | Nov 14, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [27d4e1c496](https://linux-hardware.org/?probe=27d4e1c496) | Nov 13, 2022 |
| Toshiba       | Satellite P300              | Notebook    | [02285947b8](https://linux-hardware.org/?probe=02285947b8) | Nov 13, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Acer          | Aspire E1-531G              | Notebook    | [9f3c8742f7](https://linux-hardware.org/?probe=9f3c8742f7) | Nov 13, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [220c131e59](https://linux-hardware.org/?probe=220c131e59) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [7ca98c421a](https://linux-hardware.org/?probe=7ca98c421a) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [1067cba3cc](https://linux-hardware.org/?probe=1067cba3cc) | Nov 12, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e28c12e783](https://linux-hardware.org/?probe=e28c12e783) | Nov 11, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [e69a98ce67](https://linux-hardware.org/?probe=e69a98ce67) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [59aa7d31d8](https://linux-hardware.org/?probe=59aa7d31d8) | Nov 11, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [2981b232db](https://linux-hardware.org/?probe=2981b232db) | Nov 11, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [e6ad281519](https://linux-hardware.org/?probe=e6ad281519) | Nov 11, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | Notebook    | [3ebec87cd1](https://linux-hardware.org/?probe=3ebec87cd1) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| Dell          | Latitude 7480               | Notebook    | [cd19ef7ab8](https://linux-hardware.org/?probe=cd19ef7ab8) | Nov 10, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [485568beb7](https://linux-hardware.org/?probe=485568beb7) | Nov 10, 2022 |
| Dell          | Latitude 7480               | Notebook    | [100bc3303a](https://linux-hardware.org/?probe=100bc3303a) | Nov 10, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [bf125e16a2](https://linux-hardware.org/?probe=bf125e16a2) | Nov 10, 2022 |
| Dell          | Latitude E6330              | Notebook    | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6531f0596d](https://linux-hardware.org/?probe=6531f0596d) | Nov 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [a3b1e0d746](https://linux-hardware.org/?probe=a3b1e0d746) | Nov 09, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [6642f568d4](https://linux-hardware.org/?probe=6642f568d4) | Nov 09, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [ae6b308816](https://linux-hardware.org/?probe=ae6b308816) | Nov 08, 2022 |
| Dell          | G5 5587                     | Notebook    | [972a2dcaa0](https://linux-hardware.org/?probe=972a2dcaa0) | Nov 08, 2022 |
| Lenovo        | ThinkPad P53 20QQS2CY00     | Notebook    | [98e9599ea3](https://linux-hardware.org/?probe=98e9599ea3) | Nov 08, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [3928df6d1f](https://linux-hardware.org/?probe=3928df6d1f) | Nov 08, 2022 |
| Dell          | 0VD92X A00                  | Desktop     | [a22087073b](https://linux-hardware.org/?probe=a22087073b) | Nov 08, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a8f533624d](https://linux-hardware.org/?probe=a8f533624d) | Nov 08, 2022 |
| Dell          | Latitude E7470              | Notebook    | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [d19fce3e6c](https://linux-hardware.org/?probe=d19fce3e6c) | Nov 08, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [891dbf2492](https://linux-hardware.org/?probe=891dbf2492) | Nov 07, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [fafbf5ba02](https://linux-hardware.org/?probe=fafbf5ba02) | Nov 07, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [97e9d1458f](https://linux-hardware.org/?probe=97e9d1458f) | Nov 07, 2022 |
| Gigabyte      | G41MT-S2                    | Desktop     | [4c91fc2a59](https://linux-hardware.org/?probe=4c91fc2a59) | Nov 07, 2022 |
| HP            | ProBook 5330m               | Notebook    | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Intel         | H55                         | Desktop     | [0481a6ff8e](https://linux-hardware.org/?probe=0481a6ff8e) | Nov 07, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [159ca02eca](https://linux-hardware.org/?probe=159ca02eca) | Nov 07, 2022 |
| HP            | ProBook 6570b               | Notebook    | [1fec197471](https://linux-hardware.org/?probe=1fec197471) | Nov 06, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5deb773641](https://linux-hardware.org/?probe=5deb773641) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| Intel         | D525MW AAE93082-401         | Desktop     | [d37fe5f0b4](https://linux-hardware.org/?probe=d37fe5f0b4) | Nov 06, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e8588245aa](https://linux-hardware.org/?probe=e8588245aa) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3ec96d66bb](https://linux-hardware.org/?probe=3ec96d66bb) | Nov 05, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [55b349ab41](https://linux-hardware.org/?probe=55b349ab41) | Nov 05, 2022 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [16b0128664](https://linux-hardware.org/?probe=16b0128664) | Nov 05, 2022 |
| ASRock        | FM2A88X Extreme4+           | Desktop     | [7596586a99](https://linux-hardware.org/?probe=7596586a99) | Nov 05, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [e8364f4018](https://linux-hardware.org/?probe=e8364f4018) | Nov 04, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | Notebook    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [fa89b7a988](https://linux-hardware.org/?probe=fa89b7a988) | Nov 04, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [24e798d2a5](https://linux-hardware.org/?probe=24e798d2a5) | Nov 04, 2022 |
| MSI           | Z97-G43                     | Desktop     | [85701968ed](https://linux-hardware.org/?probe=85701968ed) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [455bdc6c45](https://linux-hardware.org/?probe=455bdc6c45) | Nov 03, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [c6505744ca](https://linux-hardware.org/?probe=c6505744ca) | Nov 03, 2022 |
| Dell          | Latitude E6540              | Notebook    | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Dell          | Latitude E6430              | Notebook    | [2b6012cc1d](https://linux-hardware.org/?probe=2b6012cc1d) | Nov 02, 2022 |
| Dell          | G15 5515                    | Notebook    | [92f1423303](https://linux-hardware.org/?probe=92f1423303) | Nov 02, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [a2af2980ad](https://linux-hardware.org/?probe=a2af2980ad) | Nov 02, 2022 |
| Dell          | G15 5515                    | Notebook    | [dae7c630d5](https://linux-hardware.org/?probe=dae7c630d5) | Nov 02, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5f81698e9a](https://linux-hardware.org/?probe=5f81698e9a) | Nov 02, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d28b33e126](https://linux-hardware.org/?probe=d28b33e126) | Nov 01, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [245ec71478](https://linux-hardware.org/?probe=245ec71478) | Nov 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| HP            | EliteBook 745 G2            | Notebook    | [0786ded6c8](https://linux-hardware.org/?probe=0786ded6c8) | Oct 31, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ce4bda1df2](https://linux-hardware.org/?probe=ce4bda1df2) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Dell          | Latitude 3190               | Notebook    | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c085788e44](https://linux-hardware.org/?probe=c085788e44) | Oct 31, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [738569f811](https://linux-hardware.org/?probe=738569f811) | Oct 30, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [a8b08a47aa](https://linux-hardware.org/?probe=a8b08a47aa) | Oct 30, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| HP            | ProBook 6540b               | Notebook    | [be9c128b00](https://linux-hardware.org/?probe=be9c128b00) | Oct 30, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [9f43a68f81](https://linux-hardware.org/?probe=9f43a68f81) | Oct 30, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [d0814afd39](https://linux-hardware.org/?probe=d0814afd39) | Oct 29, 2022 |
| Kiano         | SlimNote 1.0                | Notebook    | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Dell          | Latitude 5501               | Notebook    | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0DD0... | Notebook    | [973a3662b9](https://linux-hardware.org/?probe=973a3662b9) | Oct 29, 2022 |
| Kruger&Mat... | KM1406                      | Notebook    | [70b8441ccf](https://linux-hardware.org/?probe=70b8441ccf) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| MSI           | B560M PRO                   | Desktop     | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [59c02d4967](https://linux-hardware.org/?probe=59c02d4967) | Oct 28, 2022 |
| Dell          | Latitude 5531               | Notebook    | [a7ff9a34d2](https://linux-hardware.org/?probe=a7ff9a34d2) | Oct 28, 2022 |
| Dell          | Latitude 5531               | Notebook    | [73ddced77b](https://linux-hardware.org/?probe=73ddced77b) | Oct 28, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [89cc00ef58](https://linux-hardware.org/?probe=89cc00ef58) | Oct 28, 2022 |
| Fujitsu       | LIFEBOOK U728               | Notebook    | [c5867e7dd3](https://linux-hardware.org/?probe=c5867e7dd3) | Oct 28, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d3879c6bb0](https://linux-hardware.org/?probe=d3879c6bb0) | Oct 28, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9914e4d771](https://linux-hardware.org/?probe=9914e4d771) | Oct 28, 2022 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [61e43ba85d](https://linux-hardware.org/?probe=61e43ba85d) | Oct 28, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | Notebook    | [f936993d28](https://linux-hardware.org/?probe=f936993d28) | Oct 28, 2022 |
| Gateway       | P-7805u                     | Notebook    | [7597071801](https://linux-hardware.org/?probe=7597071801) | Oct 28, 2022 |
| Dell          | Latitude E6530              | Notebook    | [71b2df6eff](https://linux-hardware.org/?probe=71b2df6eff) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [4261d8dd66](https://linux-hardware.org/?probe=4261d8dd66) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | Notebook    | [216730dba7](https://linux-hardware.org/?probe=216730dba7) | Oct 27, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Dell          | Latitude E6530              | Notebook    | [c271a351aa](https://linux-hardware.org/?probe=c271a351aa) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [2ff7652d3a](https://linux-hardware.org/?probe=2ff7652d3a) | Oct 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [082e572642](https://linux-hardware.org/?probe=082e572642) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | Notebook    | [6ba1aaf015](https://linux-hardware.org/?probe=6ba1aaf015) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | Notebook    | [062d1d3b82](https://linux-hardware.org/?probe=062d1d3b82) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [2f5cb804c0](https://linux-hardware.org/?probe=2f5cb804c0) | Oct 25, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [18df556ca1](https://linux-hardware.org/?probe=18df556ca1) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [6e98085fc5](https://linux-hardware.org/?probe=6e98085fc5) | Oct 25, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [ecbfb1ca5c](https://linux-hardware.org/?probe=ecbfb1ca5c) | Oct 25, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fbec0d9d0e](https://linux-hardware.org/?probe=fbec0d9d0e) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | Notebook    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [083b2c218e](https://linux-hardware.org/?probe=083b2c218e) | Oct 24, 2022 |
| Dell          | Latitude 3190               | Notebook    | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ce77ed764b](https://linux-hardware.org/?probe=ce77ed764b) | Oct 24, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [d18380bf4c](https://linux-hardware.org/?probe=d18380bf4c) | Oct 24, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| Dell          | Latitude 7390               | Notebook    | [f282e79ccb](https://linux-hardware.org/?probe=f282e79ccb) | Oct 23, 2022 |
| Dell          | Latitude 7390               | Notebook    | [ec27a5efb5](https://linux-hardware.org/?probe=ec27a5efb5) | Oct 23, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b940acb734](https://linux-hardware.org/?probe=b940acb734) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [1f26696990](https://linux-hardware.org/?probe=1f26696990) | Oct 22, 2022 |
| Dell          | 0HX555                      | Desktop     | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [88a93e44f9](https://linux-hardware.org/?probe=88a93e44f9) | Oct 22, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [1056e456bc](https://linux-hardware.org/?probe=1056e456bc) | Oct 22, 2022 |
| ASUSTek       | X550LN                      | Notebook    | [7a6daf6023](https://linux-hardware.org/?probe=7a6daf6023) | Oct 22, 2022 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [624b9f3b57](https://linux-hardware.org/?probe=624b9f3b57) | Oct 22, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [c853f4446a](https://linux-hardware.org/?probe=c853f4446a) | Oct 22, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [f5af95bb9a](https://linux-hardware.org/?probe=f5af95bb9a) | Oct 21, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5def3f5324](https://linux-hardware.org/?probe=5def3f5324) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [7cd6e349f0](https://linux-hardware.org/?probe=7cd6e349f0) | Oct 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [344040aee1](https://linux-hardware.org/?probe=344040aee1) | Oct 19, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7f736b0a22](https://linux-hardware.org/?probe=7f736b0a22) | Oct 19, 2022 |
| HP            | 1825                        | Desktop     | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [5d65b94f2b](https://linux-hardware.org/?probe=5d65b94f2b) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [fc51a7c9dc](https://linux-hardware.org/?probe=fc51a7c9dc) | Oct 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [8bc82af4e5](https://linux-hardware.org/?probe=8bc82af4e5) | Oct 18, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [fcac80ff4a](https://linux-hardware.org/?probe=fcac80ff4a) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| Dell          | Latitude 5421               | Notebook    | [77cbc2b788](https://linux-hardware.org/?probe=77cbc2b788) | Oct 18, 2022 |
| Dell          | Vostro 7580                 | Notebook    | [69cc3a8c62](https://linux-hardware.org/?probe=69cc3a8c62) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b8dbd1daf9](https://linux-hardware.org/?probe=b8dbd1daf9) | Oct 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e8377da07e](https://linux-hardware.org/?probe=e8377da07e) | Oct 17, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [858e5b974b](https://linux-hardware.org/?probe=858e5b974b) | Oct 17, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [4fe1c6d3e8](https://linux-hardware.org/?probe=4fe1c6d3e8) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [2d7d5c19c0](https://linux-hardware.org/?probe=2d7d5c19c0) | Oct 17, 2022 |
| Dell          | Latitude E6430              | Notebook    | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e0400f3015](https://linux-hardware.org/?probe=e0400f3015) | Oct 16, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Acer          | Aspire SW5-012              | Notebook    | [530046bf8a](https://linux-hardware.org/?probe=530046bf8a) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| HP            | ENVY 15                     | Notebook    | [09bfbadebe](https://linux-hardware.org/?probe=09bfbadebe) | Oct 14, 2022 |
| MSI           | MS-N014                     | Notebook    | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [61539bde5e](https://linux-hardware.org/?probe=61539bde5e) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | Notebook    | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| AMI           | Aptio CRB A                 | Mini pc     | [dd887afd02](https://linux-hardware.org/?probe=dd887afd02) | Oct 13, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [973f501233](https://linux-hardware.org/?probe=973f501233) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [a122b26729](https://linux-hardware.org/?probe=a122b26729) | Oct 12, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [7706fb5578](https://linux-hardware.org/?probe=7706fb5578) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| Lenovo        | ThinkPad T530 24297TG       | Notebook    | [d6dec1ab6d](https://linux-hardware.org/?probe=d6dec1ab6d) | Oct 12, 2022 |
| ASUSTek       | X705UDR                     | Notebook    | [5c8601bb4f](https://linux-hardware.org/?probe=5c8601bb4f) | Oct 11, 2022 |
| ASUSTek       | G750JW                      | Notebook    | [251f32c620](https://linux-hardware.org/?probe=251f32c620) | Oct 11, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [a993db557b](https://linux-hardware.org/?probe=a993db557b) | Oct 11, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [2f346a2afb](https://linux-hardware.org/?probe=2f346a2afb) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | Notebook    | [2aea48a0f2](https://linux-hardware.org/?probe=2aea48a0f2) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | Notebook    | [10d90de300](https://linux-hardware.org/?probe=10d90de300) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | Notebook    | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [9e82633709](https://linux-hardware.org/?probe=9e82633709) | Oct 10, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [4c575be5d7](https://linux-hardware.org/?probe=4c575be5d7) | Oct 10, 2022 |
| Acer          | Enduro EUN314-51W           | Notebook    | [14741407aa](https://linux-hardware.org/?probe=14741407aa) | Oct 10, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [b04149c5ea](https://linux-hardware.org/?probe=b04149c5ea) | Oct 10, 2022 |
| Dell          | Latitude 3190               | Notebook    | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [cde031e816](https://linux-hardware.org/?probe=cde031e816) | Oct 10, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [d7bcf0afa3](https://linux-hardware.org/?probe=d7bcf0afa3) | Oct 09, 2022 |
| ASUSTek       | P5Q Premium                 | Desktop     | [8c0a201199](https://linux-hardware.org/?probe=8c0a201199) | Oct 09, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| Dell          | 0GM819                      | Desktop     | [e0266a8468](https://linux-hardware.org/?probe=e0266a8468) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | Notebook    | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [cd707a79ef](https://linux-hardware.org/?probe=cd707a79ef) | Oct 09, 2022 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [be016db304](https://linux-hardware.org/?probe=be016db304) | Oct 08, 2022 |
| Dell          | Precision 7530              | Notebook    | [7f71730e68](https://linux-hardware.org/?probe=7f71730e68) | Oct 07, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [8a89e7f4da](https://linux-hardware.org/?probe=8a89e7f4da) | Oct 06, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d4a282a4b8](https://linux-hardware.org/?probe=d4a282a4b8) | Oct 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [ae8f71dbd3](https://linux-hardware.org/?probe=ae8f71dbd3) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Lenovo        | ThinkPad T480 20L50007PB    | Notebook    | [4c7a6898bf](https://linux-hardware.org/?probe=4c7a6898bf) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| Dell          | Precision 3541              | Notebook    | [bfef2cb8a3](https://linux-hardware.org/?probe=bfef2cb8a3) | Oct 05, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2423d31aeb](https://linux-hardware.org/?probe=2423d31aeb) | Oct 05, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [147483a370](https://linux-hardware.org/?probe=147483a370) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [ac2707d2e6](https://linux-hardware.org/?probe=ac2707d2e6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | Notebook    | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [d389c9fa00](https://linux-hardware.org/?probe=d389c9fa00) | Oct 05, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1348c5b5eb](https://linux-hardware.org/?probe=1348c5b5eb) | Oct 03, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [563ae9b3df](https://linux-hardware.org/?probe=563ae9b3df) | Oct 03, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [339dcddca7](https://linux-hardware.org/?probe=339dcddca7) | Oct 03, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6c821c0c08](https://linux-hardware.org/?probe=6c821c0c08) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | Notebook    | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6437ed8b0e](https://linux-hardware.org/?probe=6437ed8b0e) | Oct 03, 2022 |
| Dynabook      | PORTEGE X40-G               | Notebook    | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| Dell          | Latitude 3190               | Notebook    | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [7fbccd3f20](https://linux-hardware.org/?probe=7fbccd3f20) | Oct 03, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [60bab6fe12](https://linux-hardware.org/?probe=60bab6fe12) | Oct 02, 2022 |
| Acer          | Veriton X6620G v1.0         | Desktop     | [80e98d9053](https://linux-hardware.org/?probe=80e98d9053) | Oct 02, 2022 |
| Acer          | Aspire 5755G                | Notebook    | [c552cb5631](https://linux-hardware.org/?probe=c552cb5631) | Oct 02, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [658873c1d0](https://linux-hardware.org/?probe=658873c1d0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| Acer          | Aspire 4733Z                | Notebook    | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [34006e3b46](https://linux-hardware.org/?probe=34006e3b46) | Oct 01, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [bc6bcfe3f2](https://linux-hardware.org/?probe=bc6bcfe3f2) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [2d1e938e68](https://linux-hardware.org/?probe=2d1e938e68) | Oct 01, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [17abc08754](https://linux-hardware.org/?probe=17abc08754) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [fcf7e031e3](https://linux-hardware.org/?probe=fcf7e031e3) | Sep 30, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [f9582eb0a8](https://linux-hardware.org/?probe=f9582eb0a8) | Sep 29, 2022 |
| Lenovo        | G500s 20245                 | Notebook    | [b9001f7817](https://linux-hardware.org/?probe=b9001f7817) | Sep 29, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [be74c01cca](https://linux-hardware.org/?probe=be74c01cca) | Sep 29, 2022 |
| Dell          | Latitude E6330              | Notebook    | [b075fbcb56](https://linux-hardware.org/?probe=b075fbcb56) | Sep 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [82528435d8](https://linux-hardware.org/?probe=82528435d8) | Sep 29, 2022 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [4b9249b9b0](https://linux-hardware.org/?probe=4b9249b9b0) | Sep 29, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [d23d86be40](https://linux-hardware.org/?probe=d23d86be40) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [1bdf72d415](https://linux-hardware.org/?probe=1bdf72d415) | Sep 27, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | Notebook    | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [f35f96af50](https://linux-hardware.org/?probe=f35f96af50) | Sep 27, 2022 |
| Dell          | Precision 3561              | Notebook    | [77a4030052](https://linux-hardware.org/?probe=77a4030052) | Sep 27, 2022 |
| Dell          | 0DC48C A02                  | Desktop     | [9292e820c5](https://linux-hardware.org/?probe=9292e820c5) | Sep 27, 2022 |
| Toshiba       | Satellite C850-1LK          | Notebook    | [f0240dcb2d](https://linux-hardware.org/?probe=f0240dcb2d) | Sep 27, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | Notebook    | [70860ec433](https://linux-hardware.org/?probe=70860ec433) | Sep 26, 2022 |
| HP            | 805D                        | Desktop     | [b023737f63](https://linux-hardware.org/?probe=b023737f63) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [cb5f6f279b](https://linux-hardware.org/?probe=cb5f6f279b) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | Notebook    | [3f11c520e0](https://linux-hardware.org/?probe=3f11c520e0) | Sep 26, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Dell          | Latitude 3190               | Notebook    | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6d3f575c3d](https://linux-hardware.org/?probe=6d3f575c3d) | Sep 26, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c447921f07](https://linux-hardware.org/?probe=c447921f07) | Sep 25, 2022 |
| Valve         | Jupiter                     | Notebook    | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Acer          | P5WE0                       | Notebook    | [124f7bdd77](https://linux-hardware.org/?probe=124f7bdd77) | Sep 25, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [d9f9db839d](https://linux-hardware.org/?probe=d9f9db839d) | Sep 25, 2022 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8de01689b6](https://linux-hardware.org/?probe=8de01689b6) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Toshiba       | Satellite P205              | Notebook    | [2a1450578e](https://linux-hardware.org/?probe=2a1450578e) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Toshiba       | Satellite P205              | Notebook    | [98e97d946a](https://linux-hardware.org/?probe=98e97d946a) | Sep 23, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| HP            | 3032h                       | Desktop     | [efb6671159](https://linux-hardware.org/?probe=efb6671159) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| MSI           | 760GM-P34                   | Desktop     | [af750add66](https://linux-hardware.org/?probe=af750add66) | Sep 22, 2022 |
| MSI           | H81M-P33                    | Desktop     | [05d5a24774](https://linux-hardware.org/?probe=05d5a24774) | Sep 22, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| Xunlong       | Orange Pi Zero              | Soc         | [0aa622cc13](https://linux-hardware.org/?probe=0aa622cc13) | Sep 21, 2022 |
| Dell          | 0D883F A06                  | Desktop     | [01c50a7a4c](https://linux-hardware.org/?probe=01c50a7a4c) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [d22f082243](https://linux-hardware.org/?probe=d22f082243) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [e4f1a8245a](https://linux-hardware.org/?probe=e4f1a8245a) | Sep 21, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bdb353fd2c](https://linux-hardware.org/?probe=bdb353fd2c) | Sep 20, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [030ce84327](https://linux-hardware.org/?probe=030ce84327) | Sep 20, 2022 |
| Framework     | Laptop                      | Notebook    | [dd163cfa96](https://linux-hardware.org/?probe=dd163cfa96) | Sep 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21c74278f8](https://linux-hardware.org/?probe=21c74278f8) | Sep 20, 2022 |
| Dell          | Latitude E4310              | Notebook    | [c77a454d4e](https://linux-hardware.org/?probe=c77a454d4e) | Sep 20, 2022 |
| Dell          | Latitude E4310              | Notebook    | [4e8bf046d8](https://linux-hardware.org/?probe=4e8bf046d8) | Sep 19, 2022 |
| Apple         | MacBook9,1                  | Notebook    | [e6898c8aa0](https://linux-hardware.org/?probe=e6898c8aa0) | Sep 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [85952e171d](https://linux-hardware.org/?probe=85952e171d) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [eb67db5bff](https://linux-hardware.org/?probe=eb67db5bff) | Sep 19, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | Notebook    | [e6a930e933](https://linux-hardware.org/?probe=e6a930e933) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [793fa18b58](https://linux-hardware.org/?probe=793fa18b58) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | Notebook    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [419bf72e22](https://linux-hardware.org/?probe=419bf72e22) | Sep 19, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [1f2bd2202c](https://linux-hardware.org/?probe=1f2bd2202c) | Sep 19, 2022 |
| Dell          | Latitude 3190               | Notebook    | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [eb1c0556c3](https://linux-hardware.org/?probe=eb1c0556c3) | Sep 19, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5a9ab0de04](https://linux-hardware.org/?probe=5a9ab0de04) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [b3cb8fc82e](https://linux-hardware.org/?probe=b3cb8fc82e) | Sep 18, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e903dccaf1](https://linux-hardware.org/?probe=e903dccaf1) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| HP            | Notebook                    | Notebook    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5023f912e2](https://linux-hardware.org/?probe=5023f912e2) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | Notebook    | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Dell          | Latitude 5511               | Notebook    | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Pine Micro... | Pine64 Rock64               | Soc         | [dbd6ac01d6](https://linux-hardware.org/?probe=dbd6ac01d6) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | Notebook    | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [1c131a1acb](https://linux-hardware.org/?probe=1c131a1acb) | Sep 15, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f12132c99f](https://linux-hardware.org/?probe=f12132c99f) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Dell          | Latitude 5521               | Notebook    | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ea845ec5ea](https://linux-hardware.org/?probe=ea845ec5ea) | Sep 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [efc31007ac](https://linux-hardware.org/?probe=efc31007ac) | Sep 12, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [225bd59ba7](https://linux-hardware.org/?probe=225bd59ba7) | Sep 12, 2022 |
| Dell          | Latitude 3190               | Notebook    | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ed5273b278](https://linux-hardware.org/?probe=ed5273b278) | Sep 11, 2022 |
| Gigabyte      | G41MT-ES2L                  | Desktop     | [74ee0e38a3](https://linux-hardware.org/?probe=74ee0e38a3) | Sep 11, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0c536307da](https://linux-hardware.org/?probe=0c536307da) | Sep 11, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [eff4400b7d](https://linux-hardware.org/?probe=eff4400b7d) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | Notebook    | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| Acer          | Nitro AN517-55              | Notebook    | [16fa00177a](https://linux-hardware.org/?probe=16fa00177a) | Sep 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6248f4732d](https://linux-hardware.org/?probe=6248f4732d) | Sep 10, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | Notebook    | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| Gigabyte      | AORUS 15G XC                | Notebook    | [ea131dfe2c](https://linux-hardware.org/?probe=ea131dfe2c) | Sep 08, 2022 |
| Dell          | Latitude E6540              | Notebook    | [5700f37281](https://linux-hardware.org/?probe=5700f37281) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [6812b52b92](https://linux-hardware.org/?probe=6812b52b92) | Sep 08, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [2cc868e8f0](https://linux-hardware.org/?probe=2cc868e8f0) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [bb2d82813c](https://linux-hardware.org/?probe=bb2d82813c) | Sep 08, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [e757b79169](https://linux-hardware.org/?probe=e757b79169) | Sep 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [6ee5358914](https://linux-hardware.org/?probe=6ee5358914) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | Notebook    | [63524aa492](https://linux-hardware.org/?probe=63524aa492) | Sep 07, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [5cf26fac4d](https://linux-hardware.org/?probe=5cf26fac4d) | Sep 07, 2022 |
| HP            | 1497                        | Desktop     | [3cf8f5d97a](https://linux-hardware.org/?probe=3cf8f5d97a) | Sep 07, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| Dell          | 0DR845                      | Desktop     | [f945fc3f5e](https://linux-hardware.org/?probe=f945fc3f5e) | Sep 07, 2022 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | Desktop     | [a816f4f60b](https://linux-hardware.org/?probe=a816f4f60b) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [4615004e85](https://linux-hardware.org/?probe=4615004e85) | Sep 06, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [5f7f592f25](https://linux-hardware.org/?probe=5f7f592f25) | Sep 05, 2022 |
| MSI           | B85M-E43 DASH               | Desktop     | [f52a53f4a7](https://linux-hardware.org/?probe=f52a53f4a7) | Sep 05, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [e0bb6ae251](https://linux-hardware.org/?probe=e0bb6ae251) | Sep 05, 2022 |
| Dell          | Latitude 3190               | Notebook    | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [1d90e3b685](https://linux-hardware.org/?probe=1d90e3b685) | Sep 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d802875fec](https://linux-hardware.org/?probe=d802875fec) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| Dell          | Latitude E6330              | Notebook    | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [4f45b8e600](https://linux-hardware.org/?probe=4f45b8e600) | Sep 04, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [87a6f9162a](https://linux-hardware.org/?probe=87a6f9162a) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | Notebook    | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [6669ffa68e](https://linux-hardware.org/?probe=6669ffa68e) | Sep 02, 2022 |
| Dell          | Latitude E6220              | Notebook    | [e249853663](https://linux-hardware.org/?probe=e249853663) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| MSI           | B450 GAMING PLUS            | Desktop     | [3561723d92](https://linux-hardware.org/?probe=3561723d92) | Sep 02, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5d85db2c66](https://linux-hardware.org/?probe=5d85db2c66) | Sep 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Dell          | Latitude E6220              | Notebook    | [99c8b865ad](https://linux-hardware.org/?probe=99c8b865ad) | Sep 02, 2022 |
| Dell          | Latitude E6330              | Notebook    | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [12abd434b5](https://linux-hardware.org/?probe=12abd434b5) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Dell          | 042P49 A00                  | Desktop     | [31efc1e75f](https://linux-hardware.org/?probe=31efc1e75f) | Sep 01, 2022 |
| Valve         | Jupiter                     | Notebook    | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| ASUSTek       | P5K/EPU                     | Desktop     | [196d56922a](https://linux-hardware.org/?probe=196d56922a) | Aug 31, 2022 |
| Dell          | Latitude E6330              | Notebook    | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d146908413](https://linux-hardware.org/?probe=d146908413) | Aug 31, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [49c235aa0d](https://linux-hardware.org/?probe=49c235aa0d) | Aug 30, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | Notebook    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [1a8ff186c7](https://linux-hardware.org/?probe=1a8ff186c7) | Aug 29, 2022 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [4a96f9e792](https://linux-hardware.org/?probe=4a96f9e792) | Aug 29, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [e915bb3a8c](https://linux-hardware.org/?probe=e915bb3a8c) | Aug 29, 2022 |
| Dell          | Latitude 3190               | Notebook    | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [72c01f3cf1](https://linux-hardware.org/?probe=72c01f3cf1) | Aug 29, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [3b245a809d](https://linux-hardware.org/?probe=3b245a809d) | Aug 28, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [dcb225651d](https://linux-hardware.org/?probe=dcb225651d) | Aug 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [499889da7e](https://linux-hardware.org/?probe=499889da7e) | Aug 28, 2022 |
| ASUSTek       | F3E                         | Notebook    | [1314dc63b6](https://linux-hardware.org/?probe=1314dc63b6) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [7ed4b144d7](https://linux-hardware.org/?probe=7ed4b144d7) | Aug 28, 2022 |
| ASRock        | X370 Gaming X               | Desktop     | [489691c2e3](https://linux-hardware.org/?probe=489691c2e3) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [afde42fb41](https://linux-hardware.org/?probe=afde42fb41) | Aug 28, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6c1db95864](https://linux-hardware.org/?probe=6c1db95864) | Aug 28, 2022 |
| Dell          | Latitude E6400              | Notebook    | [666ba32534](https://linux-hardware.org/?probe=666ba32534) | Aug 28, 2022 |
| ASUSTek       | G15DK                       | Desktop     | [231c2674a6](https://linux-hardware.org/?probe=231c2674a6) | Aug 28, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [054a02f33e](https://linux-hardware.org/?probe=054a02f33e) | Aug 28, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| HP            | 8054                        | Desktop     | [af4f950786](https://linux-hardware.org/?probe=af4f950786) | Aug 27, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [1813b94682](https://linux-hardware.org/?probe=1813b94682) | Aug 27, 2022 |
| HP            | 15                          | Notebook    | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| ASUSTek       | X705UAP                     | Notebook    | [eacfc15b6c](https://linux-hardware.org/?probe=eacfc15b6c) | Aug 24, 2022 |
| ASUSTek       | P5B                         | Desktop     | [27c91a4b60](https://linux-hardware.org/?probe=27c91a4b60) | Aug 24, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [936ea503c8](https://linux-hardware.org/?probe=936ea503c8) | Aug 24, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d22f756c4c](https://linux-hardware.org/?probe=d22f756c4c) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Dell          | 0T1D10 A01                  | Desktop     | [39e79a7077](https://linux-hardware.org/?probe=39e79a7077) | Aug 23, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [659e36b0ed](https://linux-hardware.org/?probe=659e36b0ed) | Aug 23, 2022 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [0796a8df9d](https://linux-hardware.org/?probe=0796a8df9d) | Aug 23, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [5e11bd516d](https://linux-hardware.org/?probe=5e11bd516d) | Aug 23, 2022 |
| Dell          | Latitude 5521               | Notebook    | [b14afc8c75](https://linux-hardware.org/?probe=b14afc8c75) | Aug 22, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [29d52f610c](https://linux-hardware.org/?probe=29d52f610c) | Aug 22, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [d37dfc0613](https://linux-hardware.org/?probe=d37dfc0613) | Aug 22, 2022 |
| Dell          | Latitude 3190               | Notebook    | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| Lenovo        | ThinkPad T400 6474B84       | Notebook    | [f8a6513790](https://linux-hardware.org/?probe=f8a6513790) | Aug 22, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f38202db0d](https://linux-hardware.org/?probe=f38202db0d) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [33a9a68b5d](https://linux-hardware.org/?probe=33a9a68b5d) | Aug 21, 2022 |
| ASUSTek       | P7P55D-E                    | Desktop     | [7c83845247](https://linux-hardware.org/?probe=7c83845247) | Aug 20, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [2f5ef1300f](https://linux-hardware.org/?probe=2f5ef1300f) | Aug 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| Lenovo        | 3100 SDK0J40700 WIN 3258... | Desktop     | [d39161dc13](https://linux-hardware.org/?probe=d39161dc13) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | Notebook    | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | Notebook    | [f21f1687d5](https://linux-hardware.org/?probe=f21f1687d5) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | Notebook    | [04b38f1dfd](https://linux-hardware.org/?probe=04b38f1dfd) | Aug 19, 2022 |
| ASUSTek       | A88XM-E                     | Desktop     | [04d716a25d](https://linux-hardware.org/?probe=04d716a25d) | Aug 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ac7fb69037](https://linux-hardware.org/?probe=ac7fb69037) | Aug 19, 2022 |
| Dell          | Latitude 7280               | Notebook    | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [fdcb40d147](https://linux-hardware.org/?probe=fdcb40d147) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [cf5500d7b1](https://linux-hardware.org/?probe=cf5500d7b1) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | Notebook    | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [3d5404aaff](https://linux-hardware.org/?probe=3d5404aaff) | Aug 18, 2022 |
| ASRock        | H81M                        | Desktop     | [d59c4705a2](https://linux-hardware.org/?probe=d59c4705a2) | Aug 17, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [abad46b854](https://linux-hardware.org/?probe=abad46b854) | Aug 17, 2022 |
| NEC Comput... | PC-LJ730MG6W                | Notebook    | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1ea309e90c](https://linux-hardware.org/?probe=1ea309e90c) | Aug 17, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [d8e60dcf09](https://linux-hardware.org/?probe=d8e60dcf09) | Aug 17, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Dell          | Latitude 3190               | Notebook    | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [08bf3d620e](https://linux-hardware.org/?probe=08bf3d620e) | Aug 15, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [48637ddb10](https://linux-hardware.org/?probe=48637ddb10) | Aug 14, 2022 |
| HP            | 8054                        | Desktop     | [75e3136f50](https://linux-hardware.org/?probe=75e3136f50) | Aug 14, 2022 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [cc28c5783a](https://linux-hardware.org/?probe=cc28c5783a) | Aug 14, 2022 |
| MSI           | A320M-A PRO M2              | Desktop     | [d0831907e8](https://linux-hardware.org/?probe=d0831907e8) | Aug 14, 2022 |
| Dell          | Latitude E5430 vPro         | Notebook    | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| HP            | EliteBook 2760p             | Notebook    | [bb4c1e4c3a](https://linux-hardware.org/?probe=bb4c1e4c3a) | Aug 13, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Gigabyte      | B460M DS3H V2               | Desktop     | [2522ff1530](https://linux-hardware.org/?probe=2522ff1530) | Aug 13, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [169419cea0](https://linux-hardware.org/?probe=169419cea0) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 577       | 12.41%  |
| OpenMandriva 4.2   | 317       | 6.82%   |
| Ubuntu 18.04       | 280       | 6.02%   |
| OpenMandriva 4.3   | 208       | 4.47%   |
| Ubuntu 22.04       | 153       | 3.29%   |
| Debian 11          | 125       | 2.69%   |
| Arch Rolling       | 102       | 2.19%   |
| ROSA R10           | 98        | 2.11%   |
| ROSA R9            | 70        | 1.51%   |
| ROSA R11           | 69        | 1.48%   |
| Arch               | 68        | 1.46%   |
| Linux Mint 20.3    | 66        | 1.42%   |
| Linux Mint 20.1    | 66        | 1.42%   |
| Manjaro            | 64        | 1.38%   |
| KDE neon 20.04     | 64        | 1.38%   |
| ROSA R11.1         | 60        | 1.29%   |
| Zorin 16           | 59        | 1.27%   |
| Fedora 36          | 59        | 1.27%   |
| Ubuntu 20.10       | 56        | 1.2%    |
| Linux Mint 20.2    | 52        | 1.12%   |
| Ubuntu 21.04       | 50        | 1.08%   |
| Linux Mint 20      | 49        | 1.05%   |
| Ubuntu 19.10       | 48        | 1.03%   |
| Linux Mint 19.3    | 48        | 1.03%   |
| Ubuntu 21.10       | 44        | 0.95%   |
| Fedora 35          | 43        | 0.92%   |
| ROSA R8            | 42        | 0.9%    |
| OpenMandriva 23.01 | 42        | 0.9%    |
| Fedora 33          | 41        | 0.88%   |
| Fedora 34          | 39        | 0.84%   |
| Xubuntu 20.04      | 38        | 0.82%   |
| Fedora 32          | 38        | 0.82%   |
| Debian 10          | 37        | 0.8%    |
| ROSA R8.1          | 36        | 0.77%   |
| Pop!_OS 20.04      | 36        | 0.77%   |
| Fedora 37          | 36        | 0.77%   |
| Zorin 15           | 35        | 0.75%   |
| Linux Mint 21      | 34        | 0.73%   |
| Kubuntu 20.04      | 34        | 0.73%   |
| Ubuntu 19.04       | 33        | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1228      | 28.35%  |
| OpenMandriva  | 610       | 14.08%  |
| Linux Mint    | 343       | 7.92%   |
| ROSA          | 327       | 7.55%   |
| Fedora        | 270       | 6.23%   |
| Debian        | 194       | 4.48%   |
| Manjaro       | 183       | 4.23%   |
| Arch          | 163       | 3.76%   |
| Pop!_OS       | 125       | 2.89%   |
| Zorin         | 98        | 2.26%   |
| Kubuntu       | 84        | 1.94%   |
| KDE neon      | 79        | 1.82%   |
| Xubuntu       | 68        | 1.57%   |
| Gentoo        | 40        | 0.92%   |
| Kali          | 38        | 0.88%   |
| openSUSE      | 36        | 0.83%   |
| Endless       | 35        | 0.81%   |
| Lubuntu       | 33        | 0.76%   |
| Elementary    | 29        | 0.67%   |
| ArcoLinux     | 28        | 0.65%   |
| LMDE          | 22        | 0.51%   |
| EndeavourOS   | 21        | 0.48%   |
| Clear Linux   | 21        | 0.48%   |
| Ubuntu Unity  | 18        | 0.42%   |
| BlackPanther  | 17        | 0.39%   |
| Ubuntu MATE   | 15        | 0.35%   |
| MX            | 13        | 0.3%    |
| CentOS        | 13        | 0.3%    |
| Ubuntu Budgie | 11        | 0.25%   |
| Nobara        | 11        | 0.25%   |
| LinuxFX       | 10        | 0.23%   |
| Garuda Linux  | 10        | 0.23%   |
| SteamOS       | 9         | 0.21%   |
| Raspbian      | 8         | 0.18%   |
| Peppermint    | 8         | 0.18%   |
| NixOS         | 7         | 0.16%   |
| Linux Lite    | 6         | 0.14%   |
| Xero          | 5         | 0.12%   |
| RHEL          | 5         | 0.12%   |
| Parrot        | 5         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 303       | 5.87%   |
| 5.16.7-desktop-1omv4003         | 197       | 3.82%   |
| 5.4.0-42-generic                | 78        | 1.51%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 54        | 1.05%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 53        | 1.03%   |
| 5.15.0-56-generic               | 42        | 0.81%   |
| 6.1.1-desktop-1omv2290          | 41        | 0.79%   |
| 5.4.0-26-generic                | 40        | 0.78%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 39        | 0.76%   |
| 5.4.0-52-generic                | 38        | 0.74%   |
| 5.4.0-48-generic                | 36        | 0.7%    |
| 5.15.0-52-generic               | 36        | 0.7%    |
| 5.15.0-43-generic               | 35        | 0.68%   |
| 5.4.0-58-generic                | 33        | 0.64%   |
| 5.4.0-29-generic                | 30        | 0.58%   |
| 5.3.0-46-generic                | 30        | 0.58%   |
| 5.4.0-54-generic                | 28        | 0.54%   |
| 5.13.0-39-generic               | 27        | 0.52%   |
| 5.11.0-37-generic               | 27        | 0.52%   |
| 5.8.0-43-generic                | 26        | 0.5%    |
| 5.4.0-40-generic                | 26        | 0.5%    |
| 5.4.0-37-generic                | 25        | 0.48%   |
| 5.15.0-48-generic               | 25        | 0.48%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 24        | 0.47%   |
| 5.4.0-33-generic                | 23        | 0.45%   |
| 5.13.0-27-generic               | 23        | 0.45%   |
| 5.4.0-66-generic                | 22        | 0.43%   |
| 5.3.0-42-generic                | 22        | 0.43%   |
| 5.11.0-27-generic               | 22        | 0.43%   |
| 5.0.0-37-generic                | 22        | 0.43%   |
| 5.8.0-48-generic                | 20        | 0.39%   |
| 5.4.0-65-generic                | 20        | 0.39%   |
| 5.4.0-56-generic                | 20        | 0.39%   |
| 5.15.0-58-generic               | 20        | 0.39%   |
| 5.13.0-40-generic               | 20        | 0.39%   |
| 5.4.0-91-generic                | 19        | 0.37%   |
| 5.15.0-53-generic               | 19        | 0.37%   |
| 5.8.0-53-generic                | 18        | 0.35%   |
| 5.4.0-74-generic                | 18        | 0.35%   |
| 5.4.0-53-generic                | 18        | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 746       | 15.35%  |
| 5.10.14 | 305       | 6.28%   |
| 5.15.0  | 294       | 6.05%   |
| 4.15.0  | 282       | 5.8%    |
| 5.11.0  | 222       | 4.57%   |
| 5.8.0   | 220       | 4.53%   |
| 5.16.7  | 200       | 4.12%   |
| 5.13.0  | 190       | 3.91%   |
| 5.3.0   | 166       | 3.42%   |
| 5.10.0  | 131       | 2.7%    |
| 5.0.0   | 101       | 2.08%   |
| 4.18.0  | 89        | 1.83%   |
| 4.9.60  | 66        | 1.36%   |
| 4.9.20  | 62        | 1.28%   |
| 4.19.0  | 51        | 1.05%   |
| 6.1.1   | 42        | 0.86%   |
| 5.19.0  | 39        | 0.8%    |
| 4.1.34  | 32        | 0.66%   |
| 4.1.38  | 28        | 0.58%   |
| 5.14.0  | 27        | 0.56%   |
| 6.0.0   | 20        | 0.41%   |
| 5.17.5  | 20        | 0.41%   |
| 5.9.0   | 18        | 0.37%   |
| 5.11.12 | 18        | 0.37%   |
| 5.4.32  | 17        | 0.35%   |
| 4.9.76  | 16        | 0.33%   |
| 4.9.124 | 16        | 0.33%   |
| 5.17.0  | 15        | 0.31%   |
| 6.0.8   | 14        | 0.29%   |
| 4.9.155 | 14        | 0.29%   |
| 5.6.0   | 13        | 0.27%   |
| 5.4.83  | 13        | 0.27%   |
| 5.15.12 | 13        | 0.27%   |
| 5.16.13 | 12        | 0.25%   |
| 5.12.4  | 12        | 0.25%   |
| 6.0.7   | 11        | 0.23%   |
| 5.9.16  | 11        | 0.23%   |
| 5.15.32 | 11        | 0.23%   |
| 4.18.16 | 11        | 0.23%   |
| 6.0.9   | 10        | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 845       | 17.89%  |
| 5.10    | 546       | 11.56%  |
| 5.15    | 426       | 9.02%   |
| 5.11    | 287       | 6.08%   |
| 5.16    | 283       | 5.99%   |
| 4.15    | 282       | 5.97%   |
| 5.8     | 278       | 5.89%   |
| 5.13    | 220       | 4.66%   |
| 5.3     | 185       | 3.92%   |
| 4.9     | 181       | 3.83%   |
| 6.0     | 112       | 2.37%   |
| 5.0     | 111       | 2.35%   |
| 4.18    | 101       | 2.14%   |
| 5.19    | 95        | 2.01%   |
| 5.14    | 81        | 1.72%   |
| 5.17    | 79        | 1.67%   |
| 5.9     | 74        | 1.57%   |
| 6.1     | 73        | 1.55%   |
| 5.6     | 69        | 1.46%   |
| 5.18    | 69        | 1.46%   |
| 4.19    | 64        | 1.36%   |
| 4.1     | 63        | 1.33%   |
| 5.12    | 60        | 1.27%   |
| 5.5     | 39        | 0.83%   |
| 5.7     | 35        | 0.74%   |
| 4.4     | 17        | 0.36%   |
| 5.1     | 8         | 0.17%   |
| 3.10    | 7         | 0.15%   |
| 5.2     | 4         | 0.08%   |
| 4.20    | 4         | 0.08%   |
| 4.16    | 3         | 0.06%   |
| 4.13    | 3         | 0.06%   |
| 4.8     | 2         | 0.04%   |
| 4.7     | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 4.10    | 2         | 0.04%   |
| 3.18    | 2         | 0.04%   |
| 6.2     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 3989      | 95.45%  |
| i686    | 144       | 3.45%   |
| aarch64 | 24        | 0.57%   |
| armv7l  | 15        | 0.36%   |
| armv8l  | 3         | 0.07%   |
| armv6l  | 2         | 0.05%   |
| ppc64   | 1         | 0.02%   |
| ppc     | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1563      | 35.56%  |
| KDE5            | 1108      | 25.2%   |
| Unknown         | 473       | 10.76%  |
| XFCE            | 304       | 6.92%   |
| X-Cinnamon      | 233       | 5.3%    |
| KDE4            | 175       | 3.98%   |
| KDE             | 126       | 2.87%   |
| MATE            | 98        | 2.23%   |
| Cinnamon        | 64        | 1.46%   |
| LXQt            | 52        | 1.18%   |
| LXDE            | 43        | 0.98%   |
| i3              | 30        | 0.68%   |
| Pantheon        | 27        | 0.61%   |
| Unity           | 21        | 0.48%   |
| Budgie          | 19        | 0.43%   |
| Deepin          | 16        | 0.36%   |
| GNOME Flashback | 9         | 0.2%    |
| GNOME Classic   | 6         | 0.14%   |
| awesome         | 5         | 0.11%   |
| qtile           | 4         | 0.09%   |
| sway            | 3         | 0.07%   |
| Openbox         | 3         | 0.07%   |
| Fluxbox         | 3         | 0.07%   |
| DWM             | 3         | 0.07%   |
| trinity         | 2         | 0.05%   |
| stumpwm         | 1         | 0.02%   |
| qt5ct           | 1         | 0.02%   |
| jwm             | 1         | 0.02%   |
| ICEWM           | 1         | 0.02%   |
| Hyprland        | 1         | 0.02%   |
| GNUstep         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3473      | 80.73%  |
| Wayland | 514       | 11.95%  |
| Unknown | 227       | 5.28%   |
| Tty     | 88        | 2.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1863      | 42.59%  |
| SDDM    | 1055      | 24.12%  |
| GDM     | 480       | 10.97%  |
| LightDM | 327       | 7.48%   |
| GDM3    | 292       | 6.68%   |
| KDM     | 185       | 4.23%   |
| TDM     | 152       | 3.48%   |
| XDM     | 10        | 0.23%   |
| Ly      | 3         | 0.07%   |
| SLiM    | 2         | 0.05%   |
| MDM     | 2         | 0.05%   |
| LXDM    | 2         | 0.05%   |
| SLIMSKI | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| pl_PL      | 2345      | 54.13%  |
| en_US      | 1054      | 24.33%  |
| Unknown    | 644       | 14.87%  |
| en_GB      | 123       | 2.84%   |
| C          | 71        | 1.64%   |
| ru_RU      | 23        | 0.53%   |
| szl_PL     | 12        | 0.28%   |
| en_CA      | 8         | 0.18%   |
| uk_UA      | 6         | 0.14%   |
| de_DE      | 6         | 0.14%   |
| ru_UA      | 5         | 0.12%   |
| fr_FR      | 5         | 0.12%   |
| en_IE      | 5         | 0.12%   |
| en_DK      | 3         | 0.07%   |
| en_AG      | 3         | 0.07%   |
| C.UTF8     | 3         | 0.07%   |
| nl_NL      | 2         | 0.05%   |
| it_IT      | 2         | 0.05%   |
| en_IN      | 2         | 0.05%   |
| sv_SE      | 1         | 0.02%   |
| sk_SK      | 1         | 0.02%   |
| POSIX      | 1         | 0.02%   |
| hu_HU      | 1         | 0.02%   |
| es_ES      | 1         | 0.02%   |
| en_US.UTF8 | 1         | 0.02%   |
| en_AU      | 1         | 0.02%   |
| el_GR      | 1         | 0.02%   |
| af_ZA      | 1         | 0.02%   |
| aa_DJ      | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2386      | 55.9%   |
| EFI  | 1882      | 44.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2947      | 68.26%  |
| Overlay  | 607       | 14.06%  |
| Btrfs    | 339       | 7.85%   |
| Unknown  | 297       | 6.88%   |
| Xfs      | 58        | 1.34%   |
| Zfs      | 26        | 0.6%    |
| F2fs     | 18        | 0.42%   |
| Ext2     | 7         | 0.16%   |
| Tmpfs    | 6         | 0.14%   |
| Ext3     | 6         | 0.14%   |
| XXXXX    | 1         | 0.02%   |
| SquXshfs | 1         | 0.02%   |
| Rootfs   | 1         | 0.02%   |
| Jfs      | 1         | 0.02%   |
| Bcachefs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2088      | 48.5%   |
| GPT     | 1445      | 33.57%  |
| MBR     | 772       | 17.93%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3483      | 81.47%  |
| Yes       | 792       | 18.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2767      | 64.97%  |
| Yes       | 1492      | 35.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 733       | 17.58%  |
| Dell                    | 676       | 16.21%  |
| ASUSTek Computer        | 649       | 15.56%  |
| Hewlett-Packard         | 496       | 11.89%  |
| Gigabyte Technology     | 376       | 9.02%   |
| MSI                     | 321       | 7.7%    |
| Acer                    | 178       | 4.27%   |
| ASRock                  | 145       | 3.48%   |
| Samsung Electronics     | 72        | 1.73%   |
| Toshiba                 | 68        | 1.63%   |
| Fujitsu                 | 45        | 1.08%   |
| Sony                    | 33        | 0.79%   |
| Apple                   | 33        | 0.79%   |
| Fujitsu Siemens         | 31        | 0.74%   |
| HUAWEI                  | 27        | 0.65%   |
| Intel                   | 25        | 0.6%    |
| Raspberry Pi Foundation | 22        | 0.53%   |
| Unknown                 | 17        | 0.41%   |
| Packard Bell            | 12        | 0.29%   |
| Medion                  | 12        | 0.29%   |
| Notebook                | 11        | 0.26%   |
| Google                  | 11        | 0.26%   |
| Foxconn                 | 11        | 0.26%   |
| Valve                   | 9         | 0.22%   |
| eMachines               | 9         | 0.22%   |
| Kiano                   | 7         | 0.17%   |
| AMI                     | 7         | 0.17%   |
| Timi                    | 6         | 0.14%   |
| Inventec                | 6         | 0.14%   |
| ZOTAC                   | 4         | 0.1%    |
| mPTech                  | 4         | 0.1%    |
| Kruger&Matz             | 4         | 0.1%    |
| Huanan                  | 4         | 0.1%    |
| Gateway                 | 4         | 0.1%    |
| ECS                     | 4         | 0.1%    |
| Alienware               | 4         | 0.1%    |
| Supermicro              | 3         | 0.07%   |
| sunxi                   | 3         | 0.07%   |
| Nvidia                  | 3         | 0.07%   |
| Hardkernel              | 3         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 38        | 0.91%   |
| Dell Inspiron 3451                  | 31        | 0.74%   |
| ASUS All Series                     | 28        | 0.67%   |
| ASUS SABERTOOTH Z77                 | 18        | 0.43%   |
| MSI MS-7B86                         | 16        | 0.38%   |
| MSI MS-7817                         | 16        | 0.38%   |
| Gigabyte B450M DS3H                 | 16        | 0.38%   |
| Dell Latitude E6400                 | 15        | 0.36%   |
| Dell Latitude E6540                 | 14        | 0.34%   |
| Dell OptiPlex 780                   | 13        | 0.31%   |
| Lenovo G50-30 80G0                  | 12        | 0.29%   |
| Dell Latitude 5480                  | 12        | 0.29%   |
| MSI MS-7C02                         | 11        | 0.26%   |
| Dell Latitude E6430                 | 11        | 0.26%   |
| Dell Latitude D630                  | 11        | 0.26%   |
| HP Pavilion dv7                     | 10        | 0.24%   |
| Dell Latitude 5490                  | 10        | 0.24%   |
| Valve Jupiter                       | 9         | 0.22%   |
| Gigabyte B450 AORUS ELITE           | 9         | 0.22%   |
| Dell OptiPlex 7010                  | 9         | 0.22%   |
| Dell Latitude E6420                 | 9         | 0.22%   |
| ASUS X555LJ                         | 9         | 0.22%   |
| ASUS TUF Gaming X570-PLUS           | 9         | 0.22%   |
| MSI MS-7C37                         | 8         | 0.19%   |
| MSI MS-7B79                         | 8         | 0.19%   |
| MSI MS-7A38                         | 8         | 0.19%   |
| MSI MS-7721                         | 8         | 0.19%   |
| Lenovo Legion Y530-15ICH 81FV       | 8         | 0.19%   |
| Lenovo G580 20150                   | 8         | 0.19%   |
| Gigabyte B85M-D3H                   | 8         | 0.19%   |
| Dell OptiPlex 755                   | 8         | 0.19%   |
| Dell Latitude E7440                 | 8         | 0.19%   |
| Lenovo Legion Y540-15IRH 81SX       | 7         | 0.17%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 7         | 0.17%   |
| HP EliteBook 6930p                  | 7         | 0.17%   |
| HP 15                               | 7         | 0.17%   |
| Dell Latitude E6330                 | 7         | 0.17%   |
| Dell Latitude E5430 non-vPro        | 7         | 0.17%   |
| ASUS PRIME X470-PRO                 | 7         | 0.17%   |
| ASUS PRIME B450M-A                  | 7         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo ThinkPad         | 303       | 7.27%   |
| Dell Latitude           | 280       | 6.71%   |
| Dell Inspiron           | 148       | 3.55%   |
| Lenovo IdeaPad          | 131       | 3.14%   |
| Acer Aspire             | 104       | 2.49%   |
| Dell OptiPlex           | 90        | 2.16%   |
| HP Pavilion             | 84        | 2.01%   |
| HP EliteBook            | 83        | 1.99%   |
| HP ProBook              | 60        | 1.44%   |
| HP Compaq               | 58        | 1.39%   |
| ASUS PRIME              | 56        | 1.34%   |
| Toshiba Satellite       | 55        | 1.32%   |
| Dell Precision          | 54        | 1.29%   |
| ASUS TUF                | 48        | 1.15%   |
| Lenovo Legion           | 47        | 1.13%   |
| Lenovo ThinkCentre      | 39        | 0.94%   |
| ASUS ROG                | 39        | 0.94%   |
| Unknown                 | 38        | 0.91%   |
| Dell Vostro             | 36        | 0.86%   |
| ASUS VivoBook           | 34        | 0.82%   |
| HP Laptop               | 30        | 0.72%   |
| Dell XPS                | 28        | 0.67%   |
| ASUS All                | 28        | 0.67%   |
| Gigabyte B450M          | 23        | 0.55%   |
| RPi Raspberry           | 22        | 0.53%   |
| ASUS SABERTOOTH         | 20        | 0.48%   |
| HP 250                  | 18        | 0.43%   |
| ASUS ASUS               | 18        | 0.43%   |
| HP EliteDesk            | 17        | 0.41%   |
| Fujitsu LIFEBOOK        | 17        | 0.41%   |
| MSI MS-7B86             | 16        | 0.38%   |
| MSI MS-7817             | 16        | 0.38%   |
| Lenovo Yoga             | 16        | 0.38%   |
| Fujitsu ESPRIMO         | 16        | 0.38%   |
| Acer Extensa            | 15        | 0.36%   |
| HP ZBook                | 14        | 0.34%   |
| Gigabyte X570           | 14        | 0.34%   |
| Gigabyte B450           | 13        | 0.31%   |
| Fujitsu Siemens ESPRIMO | 13        | 0.31%   |
| Acer Nitro              | 13        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 363       | 8.71%   |
| 2018    | 351       | 8.42%   |
| 2013    | 349       | 8.37%   |
| 2019    | 343       | 8.23%   |
| 2011    | 315       | 7.55%   |
| 2020    | 299       | 7.17%   |
| 2014    | 269       | 6.45%   |
| 2017    | 250       | 6%      |
| 2008    | 245       | 5.88%   |
| 2015    | 234       | 5.61%   |
| 2010    | 221       | 5.3%    |
| 2009    | 191       | 4.58%   |
| 2021    | 190       | 4.56%   |
| 2016    | 186       | 4.46%   |
| 2007    | 185       | 4.44%   |
| 2006    | 73        | 1.75%   |
| 2022    | 54        | 1.29%   |
| Unknown | 35        | 0.84%   |
| 2005    | 10        | 0.24%   |
| 2004    | 6         | 0.14%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2466      | 59.14%  |
| Desktop        | 1542      | 36.98%  |
| Convertible    | 44        | 1.06%   |
| System on chip | 37        | 0.89%   |
| Mini pc        | 27        | 0.65%   |
| Server         | 19        | 0.46%   |
| All in one     | 17        | 0.41%   |
| Tablet         | 13        | 0.31%   |
| Phone          | 5         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3957      | 94.42%  |
| Enabled  | 234       | 5.58%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4156      | 99.66%  |
| Yes  | 14        | 0.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 930       | 21.89%  |
| 4.01-8.0        | 867       | 20.41%  |
| 8.01-16.0       | 779       | 18.34%  |
| 16.01-24.0      | 754       | 17.75%  |
| 32.01-64.0      | 426       | 10.03%  |
| 1.01-2.0        | 183       | 4.31%   |
| 2.01-3.0        | 114       | 2.68%   |
| 64.01-256.0     | 87        | 2.05%   |
| 24.01-32.0      | 67        | 1.58%   |
| 0.51-1.0        | 36        | 0.85%   |
| 0.01-0.5        | 4         | 0.09%   |
| More than 256.0 | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 1792      | 37.99%  |
| 2.01-3.0    | 983       | 20.84%  |
| 4.01-8.0    | 598       | 12.68%  |
| 3.01-4.0    | 534       | 11.32%  |
| 0.51-1.0    | 457       | 9.69%   |
| 8.01-16.0   | 200       | 4.24%   |
| 0.01-0.5    | 91        | 1.93%   |
| 16.01-24.0  | 40        | 0.85%   |
| 24.01-32.0  | 12        | 0.25%   |
| 32.01-64.0  | 4         | 0.08%   |
| Unknown     | 4         | 0.08%   |
| 64.01-256.0 | 2         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2557      | 59.11%  |
| 2       | 1077      | 24.9%   |
| 3       | 360       | 8.32%   |
| 4       | 147       | 3.4%    |
| 0       | 67        | 1.55%   |
| 5       | 62        | 1.43%   |
| 6       | 26        | 0.6%    |
| 7       | 14        | 0.32%   |
| 8       | 7         | 0.16%   |
| 9       | 3         | 0.07%   |
| 11      | 2         | 0.05%   |
| 10      | 2         | 0.05%   |
| 13      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2346      | 55.49%  |
| Yes       | 1882      | 44.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3778      | 90.38%  |
| No        | 402       | 9.62%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3139      | 74.63%  |
| No        | 1067      | 25.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2339      | 55.17%  |
| No        | 1901      | 44.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 4170      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 938       | 20.69%  |
| Krakow                 | 339       | 7.48%   |
| Wroclaw                | 266       | 5.87%   |
| Poznan                 | 222       | 4.9%    |
| Lodz                   | 139       | 3.07%   |
| Gdansk                 | 137       | 3.02%   |
| Katowice               | 117       | 2.58%   |
| Lublin                 | 59        | 1.3%    |
| Gdynia                 | 54        | 1.19%   |
| Szczecin               | 48        | 1.06%   |
| Bialystok              | 40        | 0.88%   |
| Częstochowa           | 37        | 0.82%   |
| Rzeszów               | 35        | 0.77%   |
| Gliwice                | 35        | 0.77%   |
| Torun                  | 33        | 0.73%   |
| Ruda Śląska          | 31        | 0.68%   |
| Bydgoszcz              | 30        | 0.66%   |
| Bytom                  | 29        | 0.64%   |
| Sosnowiec              | 23        | 0.51%   |
| Płock                 | 23        | 0.51%   |
| Elblag                 | 22        | 0.49%   |
| Bielsko-Biala          | 21        | 0.46%   |
| Strzyzow               | 20        | 0.44%   |
| Olsztyn                | 20        | 0.44%   |
| Kielce                 | 20        | 0.44%   |
| Chorzów               | 19        | 0.42%   |
| Zabrze                 | 17        | 0.38%   |
| Tarnów                | 17        | 0.38%   |
| Siemianowice Śląskie | 17        | 0.38%   |
| Rybnik                 | 17        | 0.38%   |
| Radom                  | 17        | 0.38%   |
| Tychy                  | 16        | 0.35%   |
| Opole                  | 16        | 0.35%   |
| Cieszyn                | 13        | 0.29%   |
| Blizniew               | 13        | 0.29%   |
| Słupsk                | 12        | 0.26%   |
| Debica                 | 12        | 0.26%   |
| Zielona Góra          | 11        | 0.24%   |
| Pruszków              | 11        | 0.24%   |
| Piaseczno              | 11        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 896       | 1372   | 14.59%  |
| WDC                       | 863       | 1311   | 14.05%  |
| Samsung Electronics       | 841       | 1282   | 13.69%  |
| GOODRAM                   | 403       | 588    | 6.56%   |
| Toshiba                   | 384       | 575    | 6.25%   |
| Kingston                  | 233       | 326    | 3.79%   |
| Crucial                   | 233       | 379    | 3.79%   |
| A-DATA Technology         | 228       | 315    | 3.71%   |
| Unknown                   | 221       | 317    | 3.6%    |
| SanDisk                   | 212       | 292    | 3.45%   |
| Hitachi                   | 208       | 292    | 3.39%   |
| Intel                     | 158       | 207    | 2.57%   |
| SK hynix                  | 130       | 167    | 2.12%   |
| HGST                      | 101       | 130    | 1.64%   |
| Micron Technology         | 80        | 105    | 1.3%    |
| Patriot                   | 74        | 97     | 1.2%    |
| SPCC                      | 66        | 96     | 1.07%   |
| Plextor                   | 57        | 73     | 0.93%   |
| PNY                       | 43        | 47     | 0.7%    |
| KIOXIA                    | 40        | 45     | 0.65%   |
| XPG                       | 39        | 55     | 0.63%   |
| Phison                    | 37        | 51     | 0.6%    |
| Apacer                    | 35        | 56     | 0.57%   |
| Fujitsu                   | 33        | 37     | 0.54%   |
| OCZ                       | 27        | 29     | 0.44%   |
| Corsair                   | 25        | 34     | 0.41%   |
| China                     | 24        | 28     | 0.39%   |
| LITEON                    | 23        | 32     | 0.37%   |
| Maxtor                    | 21        | 21     | 0.34%   |
| Transcend                 | 18        | 19     | 0.29%   |
| KIOXIA-EXCERIA            | 18        | 24     | 0.29%   |
| Silicon Motion            | 17        | 20     | 0.28%   |
| Realtek Semiconductor     | 17        | 27     | 0.28%   |
| Lite-On                   | 17        | 20     | 0.28%   |
| JMicron Technology        | 17        | 18     | 0.28%   |
| ASMT                      | 16        | 17     | 0.26%   |
| Phison Electronics        | 15        | 25     | 0.24%   |
| LITEONIT                  | 15        | 16     | 0.24%   |
| Apple                     | 15        | 19     | 0.24%   |
| Micron/Crucial Technology | 12        | 12     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 59        | 0.88%   |
| Seagate ST1000LM035-1RK172 1TB         | 56        | 0.83%   |
| Crucial CT500MX500SSD1 500GB           | 53        | 0.79%   |
| Toshiba HDWD110 1TB                    | 51        | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 51        | 0.76%   |
| Samsung SSD 850 EVO 250GB              | 49        | 0.73%   |
| GOODRAM SSD 120GB                      | 48        | 0.71%   |
| Crucial CT1000MX500SSD1 1TB            | 40        | 0.59%   |
| Seagate ST500DM002-1BD142 500GB        | 38        | 0.57%   |
| GOODRAM SSDPR-CX400-256-G2 256GB       | 37        | 0.55%   |
| Unknown MMC Card  32GB                 | 34        | 0.51%   |
| Samsung SSD 860 EVO 500GB              | 34        | 0.51%   |
| GOODRAM SSDPR-CX400-512 512GB          | 33        | 0.49%   |
| GOODRAM SSD 240GB                      | 33        | 0.49%   |
| Samsung SSD 860 EVO 250GB              | 32        | 0.48%   |
| Samsung NVMe SSD Drive 500GB           | 32        | 0.48%   |
| Kingston SV300S37A120G 120GB SSD       | 31        | 0.46%   |
| Seagate ST9500325AS 500GB              | 30        | 0.45%   |
| Unknown MMC Card  64GB                 | 29        | 0.43%   |
| Kingston SA400S37240G 240GB SSD        | 29        | 0.43%   |
| Toshiba MQ01ABD100 1TB                 | 28        | 0.42%   |
| Samsung NVMe SSD Drive 512GB           | 28        | 0.42%   |
| A-DATA SU800 256GB SSD                 | 28        | 0.42%   |
| Seagate ST3500418AS 500GB              | 27        | 0.4%    |
| Seagate ST1000DM010-2EP102 1TB         | 27        | 0.4%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 27        | 0.4%    |
| GOODRAM SSDPR-CX400-512-G2 512GB       | 27        | 0.4%    |
| Seagate ST1000DM003-1ER162 1TB         | 26        | 0.39%   |
| Intel NVMe SSD Drive 512GB             | 26        | 0.39%   |
| Patriot Burst 120GB SSD                | 25        | 0.37%   |
| HGST HTS721010A9E630 1TB               | 25        | 0.37%   |
| Crucial CT240BX500SSD1 240GB           | 25        | 0.37%   |
| Samsung HD502HJ 500GB                  | 24        | 0.36%   |
| GOODRAM SSDPR-CX400-256 256GB          | 23        | 0.34%   |
| GOODRAM SSDPR-CX400-128 128GB          | 23        | 0.34%   |
| Seagate Expansion 240GB                | 22        | 0.33%   |
| SanDisk SDSSDA240G 240GB               | 22        | 0.33%   |
| GOODRAM SSDPR-CL100-120-G2 120GB       | 22        | 0.33%   |
| Toshiba DT01ACA100 1TB                 | 21        | 0.31%   |
| Samsung SSD 970 EVO Plus 500GB         | 21        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 893       | 1367   | 35.92%  |
| WDC                 | 721       | 1111   | 29%     |
| Toshiba             | 299       | 469    | 12.03%  |
| Hitachi             | 208       | 292    | 8.37%   |
| Samsung Electronics | 159       | 226    | 6.4%    |
| HGST                | 101       | 130    | 4.06%   |
| Fujitsu             | 33        | 37     | 1.33%   |
| Maxtor              | 19        | 19     | 0.76%   |
| ASMT                | 16        | 17     | 0.64%   |
| Unknown             | 8         | 8      | 0.32%   |
| ASMedia             | 5         | 6      | 0.2%    |
| Apple               | 5         | 5      | 0.2%    |
| USB3.0              | 3         | 3      | 0.12%   |
| PHD 3.0             | 2         | 2      | 0.08%   |
| IBM/Hitachi         | 2         | 2      | 0.08%   |
| Unknown             | 2         | 2      | 0.08%   |
| WD MediaMax         | 1         | 2      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| SAGE                | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 2      | 0.04%   |
| HPE                 | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| GOODRAM             | 396       | 573    | 17.81%  |
| Samsung Electronics | 375       | 524    | 16.86%  |
| Crucial             | 225       | 369    | 10.12%  |
| A-DATA Technology   | 186       | 254    | 8.36%   |
| Kingston            | 170       | 234    | 7.64%   |
| SanDisk             | 148       | 211    | 6.65%   |
| WDC                 | 77        | 89     | 3.46%   |
| Patriot             | 65        | 88     | 2.92%   |
| SPCC                | 59        | 87     | 2.65%   |
| Intel               | 52        | 62     | 2.34%   |
| Plextor             | 48        | 64     | 2.16%   |
| Micron Technology   | 45        | 59     | 2.02%   |
| Toshiba             | 40        | 43     | 1.8%    |
| SK hynix            | 35        | 43     | 1.57%   |
| Apacer              | 32        | 53     | 1.44%   |
| PNY                 | 31        | 35     | 1.39%   |
| OCZ                 | 27        | 29     | 1.21%   |
| LITEON              | 23        | 32     | 1.03%   |
| China               | 23        | 27     | 1.03%   |
| Transcend           | 17        | 18     | 0.76%   |
| LITEONIT            | 15        | 16     | 0.67%   |
| KIOXIA-EXCERIA      | 14        | 19     | 0.63%   |
| JMicron Technology  | 11        | 11     | 0.49%   |
| Corsair             | 10        | 11     | 0.45%   |
| Apple               | 9         | 9      | 0.4%    |
| KingSpec            | 6         | 7      | 0.27%   |
| Intenso             | 6         | 11     | 0.27%   |
| BIWIN               | 5         | 5      | 0.22%   |
| Team                | 4         | 4      | 0.18%   |
| Argon               | 4         | 6      | 0.18%   |
| Lexar               | 3         | 3      | 0.13%   |
| Gigabyte Technology | 3         | 4      | 0.13%   |
| 2-Power             | 3         | 3      | 0.13%   |
| WDC WDS2            | 2         | 2      | 0.09%   |
| Union Memory        | 2         | 3      | 0.09%   |
| Ramaxel Technology  | 2         | 2      | 0.09%   |
| Phison              | 2         | 2      | 0.09%   |
| Netac               | 2         | 3      | 0.09%   |
| Maxtor              | 2         | 2      | 0.09%   |
| HS-SSD-E100         | 2         | 2      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2111      | 3708   | 38.61%  |
| SSD     | 1955      | 3064   | 35.75%  |
| NVMe    | 1134      | 1704   | 20.74%  |
| MMC     | 199       | 283    | 3.64%   |
| Unknown | 69        | 101    | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3282      | 6621   | 68.38%  |
| NVMe | 1133      | 1702   | 23.6%   |
| MMC  | 199       | 283    | 4.15%   |
| SAS  | 186       | 254    | 3.88%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2704      | 4435   | 65.92%  |
| 0.51-1.0   | 1039      | 1668   | 25.33%  |
| 1.01-2.0   | 194       | 320    | 4.73%   |
| 2.01-3.0   | 64        | 141    | 1.56%   |
| 3.01-4.0   | 57        | 113    | 1.39%   |
| 4.01-10.0  | 37        | 77     | 0.9%    |
| 10.01-20.0 | 7         | 18     | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1256      | 27.87%  |
| 251-500        | 856       | 19%     |
| 1-20           | 546       | 12.12%  |
| 501-1000       | 505       | 11.21%  |
| 51-100         | 384       | 8.52%   |
| 1001-2000      | 297       | 6.59%   |
| 21-50          | 233       | 5.17%   |
| Unknown        | 195       | 4.33%   |
| More than 3000 | 136       | 3.02%   |
| 2001-3000      | 98        | 2.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1954      | 42.15%  |
| 21-50          | 685       | 14.78%  |
| 101-250        | 550       | 11.86%  |
| 51-100         | 504       | 10.87%  |
| 251-500        | 289       | 6.23%   |
| 501-1000       | 235       | 5.07%   |
| Unknown        | 195       | 4.21%   |
| 1001-2000      | 132       | 2.85%   |
| More than 3000 | 46        | 0.99%   |
| 2001-3000      | 46        | 0.99%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 13        | 16     | 2.15%   |
| Seagate ST500LT012-9WS142 500GB      | 9         | 28     | 1.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 10     | 1.49%   |
| Seagate ST3500418AS 500GB            | 8         | 11     | 1.32%   |
| Seagate ST500DM002-1BD142 500GB      | 7         | 7      | 1.16%   |
| Seagate ST500LT012-1DG142 500GB      | 6         | 8      | 0.99%   |
| HGST HTS545050A7E680 500GB           | 6         | 6      | 0.99%   |
| Seagate ST1000DM003-9YN162 1TB       | 5         | 5      | 0.83%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 0.83%   |
| GOODRAM SSD 120GB                    | 5         | 5      | 0.83%   |
| ASMT 2135 3TB                        | 5         | 5      | 0.83%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 0.66%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 4      | 0.66%   |
| Toshiba MQ01ABD100 1TB               | 4         | 5      | 0.66%   |
| Seagate ST9500420AS 500GB            | 4         | 4      | 0.66%   |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.66%   |
| Seagate ST92505610AS 250GB           | 4         | 4      | 0.66%   |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.66%   |
| Hitachi HTS541612J9SA00 119GB        | 4         | 5      | 0.66%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.5%    |
| Toshiba MK3265GSX 320GB              | 3         | 3      | 0.5%    |
| Toshiba MK1637GSX 160GB              | 3         | 3      | 0.5%    |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.5%    |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 3      | 0.5%    |
| Seagate ST9250827AS 250GB            | 3         | 3      | 0.5%    |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.5%    |
| Seagate ST9250315AS 250GB            | 3         | 3      | 0.5%    |
| Seagate ST9160821AS 160GB            | 3         | 4      | 0.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB  | 3         | 3      | 0.5%    |
| Seagate ST3500312CS 500GB            | 3         | 3      | 0.5%    |
| Seagate ST3250410AS 250GB            | 3         | 3      | 0.5%    |
| Seagate ST31500341AS 1TB             | 3         | 4      | 0.5%    |
| Seagate ST1000LM014-1EJ164 1TB       | 3         | 4      | 0.5%    |
| Seagate ST1000DX001-1CM162 1TB       | 3         | 6      | 0.5%    |
| Samsung Electronics HD502HJ 500GB    | 3         | 3      | 0.5%    |
| Hitachi HTS543225L9A300 250GB        | 3         | 3      | 0.5%    |
| Hitachi HTS542516K9SA00 160GB        | 3         | 5      | 0.5%    |
| HGST HTS545050A7E380 500GB           | 3         | 3      | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 3      | 0.33%   |
| WDC WD5002ABYS-01B1B0 500GB          | 2         | 14     | 0.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 174       | 236    | 29.95%  |
| WDC                   | 114       | 166    | 19.62%  |
| Hitachi               | 47        | 59     | 8.09%   |
| Toshiba               | 45        | 56     | 7.75%   |
| Samsung Electronics   | 44        | 50     | 7.57%   |
| A-DATA Technology     | 26        | 29     | 4.48%   |
| HGST                  | 17        | 18     | 2.93%   |
| SanDisk               | 15        | 18     | 2.58%   |
| Kingston              | 11        | 11     | 1.89%   |
| SK hynix              | 8         | 8      | 1.38%   |
| GOODRAM               | 8         | 8      | 1.38%   |
| Fujitsu               | 8         | 10     | 1.38%   |
| Intel                 | 7         | 7      | 1.2%    |
| ASMT                  | 6         | 7      | 1.03%   |
| LITEON                | 5         | 5      | 0.86%   |
| Crucial               | 5         | 7      | 0.86%   |
| Micron Technology     | 4         | 4      | 0.69%   |
| Maxtor                | 4         | 4      | 0.69%   |
| LITEONIT              | 4         | 4      | 0.69%   |
| Apacer                | 4         | 7      | 0.69%   |
| SPCC                  | 3         | 3      | 0.52%   |
| OCZ                   | 3         | 3      | 0.52%   |
| Hewlett-Packard       | 3         | 3      | 0.52%   |
| ASMedia               | 3         | 3      | 0.52%   |
| Patriot               | 2         | 4      | 0.34%   |
| XPG                   | 1         | 1      | 0.17%   |
| WDC WDS2              | 1         | 1      | 0.17%   |
| WD MediaMax           | 1         | 2      | 0.17%   |
| SSSTC                 | 1         | 1      | 0.17%   |
| Realtek Semiconductor | 1         | 1      | 0.17%   |
| Plextor               | 1         | 1      | 0.17%   |
| Platinet              | 1         | 1      | 0.17%   |
| Lexar                 | 1         | 1      | 0.17%   |
| Lenovo                | 1         | 1      | 0.17%   |
| Corsair               | 1         | 2      | 0.17%   |
| Unknown               | 1         | 1      | 0.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 174       | 236    | 38.84%  |
| WDC                 | 111       | 162    | 24.78%  |
| Hitachi             | 47        | 59     | 10.49%  |
| Toshiba             | 42        | 53     | 9.38%   |
| Samsung Electronics | 33        | 38     | 7.37%   |
| HGST                | 17        | 18     | 3.79%   |
| Fujitsu             | 8         | 10     | 1.79%   |
| ASMT                | 6         | 7      | 1.34%   |
| Maxtor              | 4         | 4      | 0.89%   |
| ASMedia             | 3         | 3      | 0.67%   |
| WD MediaMax         | 1         | 2      | 0.22%   |
| Hewlett-Packard     | 1         | 1      | 0.22%   |
| Unknown             | 1         | 1      | 0.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 421       | 594    | 76.27%  |
| SSD  | 112       | 128    | 20.29%  |
| NVMe | 19        | 21     | 3.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB         | 1         | 1      | 8.33%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 8.33%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 8.33%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 8.33%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 8.33%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 8.33%   |
| Toshiba DT01ACA100 1TB            | 1         | 2      | 8.33%   |
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 8.33%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 8.33%   |
| Samsung Electronics HD250HJ 250GB | 1         | 1      | 8.33%   |
| OCZ-AGIL ITY3 64GB SSD            | 1         | 1      | 8.33%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 41.67%  |
| Toshiba             | 2         | 3      | 16.67%  |
| Seagate             | 2         | 2      | 16.67%  |
| Samsung Electronics | 1         | 1      | 8.33%   |
| OCZ-AGIL            | 1         | 1      | 8.33%   |
| HGST                | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2164      | 4510   | 47.41%  |
| Works    | 1851      | 3594   | 40.56%  |
| Malfunc  | 537       | 743    | 11.77%  |
| Failed   | 12        | 13     | 0.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2922      | 55.88%  |
| AMD                              | 766       | 14.65%  |
| Samsung Electronics              | 375       | 7.17%   |
| SanDisk                          | 139       | 2.66%   |
| Phison Electronics               | 95        | 1.82%   |
| SK hynix                         | 91        | 1.74%   |
| JMicron Technology               | 91        | 1.74%   |
| ASMedia Technology               | 89        | 1.7%    |
| Nvidia                           | 87        | 1.66%   |
| ADATA Technology                 | 84        | 1.61%   |
| Kingston Technology Company      | 70        | 1.34%   |
| Toshiba America Info Systems     | 47        | 0.9%    |
| KIOXIA                           | 47        | 0.9%    |
| Marvell Technology Group         | 45        | 0.86%   |
| Silicon Motion                   | 37        | 0.71%   |
| Micron Technology                | 36        | 0.69%   |
| Realtek Semiconductor            | 30        | 0.57%   |
| Lite-On Technology               | 26        | 0.5%    |
| VIA Technologies                 | 20        | 0.38%   |
| Micron/Crucial Technology        | 19        | 0.36%   |
| LSI Logic / Symbios Logic        | 15        | 0.29%   |
| Union Memory (Shenzhen)          | 14        | 0.27%   |
| Silicon Integrated Systems [SiS] | 11        | 0.21%   |
| Shenzhen Longsys Electronics     | 11        | 0.21%   |
| Solid State Storage Technology   | 9         | 0.17%   |
| Silicon Image                    | 8         | 0.15%   |
| Broadcom / LSI                   | 8         | 0.15%   |
| Hewlett-Packard                  | 7         | 0.13%   |
| Lenovo                           | 6         | 0.11%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.06%   |
| INNOGRIT                         | 3         | 0.06%   |
| Apple                            | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| ULi Electronics                  | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Tekram Technology                | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| O2 Micro                         | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 495       | 7.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 216       | 3.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 206       | 3.32%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 197       | 3.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 175       | 2.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 153       | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 147       | 2.37%   |
| AMD 400 Series Chipset SATA Controller                                         | 147       | 2.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 126       | 2.03%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 113       | 1.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 106       | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 101       | 1.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 101       | 1.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 99        | 1.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 89        | 1.43%   |
| Samsung NVMe SSD Controller 980                                                | 88        | 1.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 88        | 1.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 87        | 1.4%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 86        | 1.39%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 80        | 1.29%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 77        | 1.24%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 76        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 75        | 1.21%   |
| Intel Volume Management Device NVMe RAID Controller                            | 73        | 1.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 73        | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 73        | 1.18%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 71        | 1.14%   |
| Intel SSD 660P Series                                                          | 67        | 1.08%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 67        | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 65        | 1.05%   |
| JMicron JMB363 SATA/IDE Controller                                             | 62        | 1%      |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 60        | 0.97%   |
| Intel SATA Controller [RAID mode]                                              | 56        | 0.9%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 53        | 0.85%   |
| Phison E12 NVMe Controller                                                     | 48        | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 48        | 0.77%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 44        | 0.71%   |
| AMD 500 Series Chipset SATA Controller                                         | 43        | 0.69%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 39        | 0.63%   |
| Nvidia MCP61 SATA Controller                                                   | 37        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3033      | 56.88%  |
| NVMe | 1150      | 21.57%  |
| IDE  | 799       | 14.98%  |
| RAID | 323       | 6.06%   |
| SAS  | 14        | 0.26%   |
| SCSI | 13        | 0.24%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3149      | 75.52%  |
| AMD          | 974       | 23.36%  |
| ARM          | 40        | 0.96%   |
| Qualcomm     | 3         | 0.07%   |
| PowerMac11,2 | 1         | 0.02%   |
| PowerBook6,7 | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |
| AppliedMicro | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 48        | 1.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 42        | 1%      |
| Intel Core i5-7200U CPU @ 2.50GHz             | 39        | 0.93%   |
| AMD Ryzen 5 3600 6-Core Processor             | 37        | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 34        | 0.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 33        | 0.79%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 32        | 0.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 31        | 0.74%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 0.72%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 29        | 0.69%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 27        | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 26        | 0.62%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.62%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 26        | 0.62%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 24        | 0.57%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 0.55%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 22        | 0.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 22        | 0.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 21        | 0.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 21        | 0.5%    |
| ARM Processor                                 | 21        | 0.5%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 20        | 0.48%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 20        | 0.48%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 20        | 0.48%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 20        | 0.48%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 20        | 0.48%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 20        | 0.48%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 19        | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 19        | 0.45%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 18        | 0.43%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 18        | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 18        | 0.43%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 18        | 0.43%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 17        | 0.41%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 17        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1012      | 24.21%  |
| Intel Core i7           | 639       | 15.29%  |
| Intel Core i3           | 309       | 7.39%   |
| Intel Core 2 Duo        | 289       | 6.91%   |
| AMD Ryzen 5             | 264       | 6.32%   |
| Other                   | 177       | 4.23%   |
| Intel Celeron           | 174       | 4.16%   |
| AMD Ryzen 7             | 169       | 4.04%   |
| Intel Pentium           | 122       | 2.92%   |
| Intel Xeon              | 103       | 2.46%   |
| Intel Atom              | 74        | 1.77%   |
| Intel Pentium Dual-Core | 66        | 1.58%   |
| Intel Core 2 Quad       | 58        | 1.39%   |
| AMD Ryzen 9             | 47        | 1.12%   |
| AMD FX                  | 47        | 1.12%   |
| Intel Core 2            | 40        | 0.96%   |
| AMD Phenom II X4        | 35        | 0.84%   |
| AMD Ryzen 3             | 34        | 0.81%   |
| AMD A6                  | 33        | 0.79%   |
| Intel Pentium Dual      | 32        | 0.77%   |
| AMD Athlon 64 X2        | 31        | 0.74%   |
| AMD A8                  | 30        | 0.72%   |
| AMD A10                 | 27        | 0.65%   |
| AMD Athlon II X2        | 26        | 0.62%   |
| AMD A4                  | 18        | 0.43%   |
| Intel Genuine           | 17        | 0.41%   |
| AMD Athlon II X4        | 17        | 0.41%   |
| Intel Core i9           | 15        | 0.36%   |
| AMD Ryzen 7 PRO         | 15        | 0.36%   |
| AMD E                   | 14        | 0.33%   |
| AMD E1                  | 12        | 0.29%   |
| Intel Celeron M         | 11        | 0.26%   |
| ARM BCM                 | 11        | 0.26%   |
| AMD Ryzen Threadripper  | 10        | 0.24%   |
| AMD GX                  | 9         | 0.22%   |
| AMD Athlon              | 9         | 0.22%   |
| Intel Pentium M         | 8         | 0.19%   |
| Intel Pentium D         | 8         | 0.19%   |
| AMD Turion 64 X2 Mobile | 8         | 0.19%   |
| AMD Ryzen 5 PRO         | 8         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1843      | 43.93%  |
| 4       | 1415      | 33.73%  |
| 6       | 396       | 9.44%   |
| 8       | 247       | 5.89%   |
| 1       | 101       | 2.41%   |
| Unknown | 69        | 1.64%   |
| 12      | 55        | 1.31%   |
| 3       | 23        | 0.55%   |
| 16      | 16        | 0.38%   |
| 10      | 10        | 0.24%   |
| 14      | 9         | 0.21%   |
| 32      | 3         | 0.07%   |
| 24      | 2         | 0.05%   |
| 20      | 2         | 0.05%   |
| 192     | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4129      | 98.95%  |
| 2       | 38        | 0.91%   |
| Unknown | 5         | 0.12%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2498      | 59.58%  |
| 1       | 1625      | 38.76%  |
| Unknown | 69        | 1.65%   |
| 8       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4047      | 96.82%  |
| Unknown        | 81        | 1.94%   |
| 32-bit         | 50        | 1.2%    |
| 64-bit         | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 805       | 18.67%  |
| 0x306a9    | 269       | 6.24%   |
| 0x206a7    | 262       | 6.08%   |
| 0x306c3    | 219       | 5.08%   |
| 0x1067a    | 206       | 4.78%   |
| 0x906ea    | 119       | 2.76%   |
| 0x506e3    | 107       | 2.48%   |
| 0x40651    | 99        | 2.3%    |
| 0x20655    | 88        | 2.04%   |
| 0x906e9    | 87        | 2.02%   |
| 0x6fd      | 84        | 1.95%   |
| 0x30678    | 84        | 1.95%   |
| 0x806ec    | 82        | 1.9%    |
| 0x306d4    | 75        | 1.74%   |
| 0x10676    | 75        | 1.74%   |
| 0x806ea    | 72        | 1.67%   |
| 0x406e3    | 69        | 1.6%    |
| 0x806c1    | 68        | 1.58%   |
| 0x806e9    | 62        | 1.44%   |
| 0x0800820d | 59        | 1.37%   |
| 0x010000c8 | 57        | 1.32%   |
| 0x08701021 | 55        | 1.28%   |
| 0x0a50000c | 48        | 1.11%   |
| 0x6fb      | 43        | 1%      |
| 0x06001119 | 38        | 0.88%   |
| 0x08108109 | 34        | 0.79%   |
| 0x20652    | 33        | 0.77%   |
| 0x6f6      | 31        | 0.72%   |
| 0xa0652    | 28        | 0.65%   |
| 0x08600106 | 28        | 0.65%   |
| 0x08701013 | 27        | 0.63%   |
| 0x806eb    | 25        | 0.58%   |
| 0x08108102 | 25        | 0.58%   |
| 0x906ed    | 24        | 0.56%   |
| 0x406c4    | 23        | 0.53%   |
| 0x06000852 | 22        | 0.51%   |
| 0xa0653    | 21        | 0.49%   |
| 0x406c3    | 21        | 0.49%   |
| 0x106e5    | 21        | 0.49%   |
| 0x08001138 | 21        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 585       | 13.99%  |
| Haswell          | 385       | 9.2%    |
| IvyBridge        | 323       | 7.72%   |
| Penryn           | 321       | 7.67%   |
| SandyBridge      | 310       | 7.41%   |
| Core             | 218       | 5.21%   |
| Skylake          | 217       | 5.19%   |
| Zen 2            | 196       | 4.69%   |
| Zen+             | 153       | 3.66%   |
| Westmere         | 151       | 3.61%   |
| Silvermont       | 147       | 3.51%   |
| K10              | 113       | 2.7%    |
| Unknown          | 106       | 2.53%   |
| Broadwell        | 104       | 2.49%   |
| Zen 3            | 94        | 2.25%   |
| Zen              | 86        | 2.06%   |
| TigerLake        | 79        | 1.89%   |
| Piledriver       | 79        | 1.89%   |
| CometLake        | 72        | 1.72%   |
| K8 Hammer        | 62        | 1.48%   |
| IceLake          | 46        | 1.1%    |
| Bobcat           | 38        | 0.91%   |
| Nehalem          | 36        | 0.86%   |
| Bonnell          | 33        | 0.79%   |
| P6               | 30        | 0.72%   |
| Jaguar           | 25        | 0.6%    |
| Goldmont plus    | 23        | 0.55%   |
| Alderlake Hybrid | 22        | 0.53%   |
| Excavator        | 20        | 0.48%   |
| NetBurst         | 19        | 0.45%   |
| Steamroller      | 18        | 0.43%   |
| K10 Llano        | 16        | 0.38%   |
| Puma             | 15        | 0.36%   |
| K8 & K10 hybrid  | 14        | 0.33%   |
| Goldmont         | 14        | 0.33%   |
| Bulldozer        | 12        | 0.29%   |
| Tremont          | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2337      | 47.04%  |
| Nvidia                           | 1519      | 30.58%  |
| AMD                              | 1086      | 21.86%  |
| Matrox Electronics Systems       | 10        | 0.2%    |
| Silicon Integrated Systems [SiS] | 6         | 0.12%   |
| VIA Technologies                 | 5         | 0.1%    |
| ASPEED Technology                | 4         | 0.08%   |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 248       | 4.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 203       | 3.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 120       | 2.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 100       | 1.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 95        | 1.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 94        | 1.82%   |
| Intel UHD Graphics 620                                                                   | 86        | 1.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 86        | 1.66%   |
| Intel HD Graphics 5500                                                                   | 85        | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 85        | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 85        | 1.64%   |
| AMD Renoir                                                                               | 82        | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 81        | 1.56%   |
| Intel HD Graphics 530                                                                    | 80        | 1.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 76        | 1.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 76        | 1.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 74        | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 73        | 1.41%   |
| Intel HD Graphics 620                                                                    | 72        | 1.39%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 69        | 1.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 69        | 1.33%   |
| Intel HD Graphics 630                                                                    | 69        | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 52        | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 51        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 49        | 0.95%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 47        | 0.91%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 39        | 0.75%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 38        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 38        | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 37        | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 37        | 0.71%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 37        | 0.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 0.71%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 31        | 0.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 31        | 0.6%    |
| Nvidia GT218 [GeForce 210]                                                               | 29        | 0.56%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 29        | 0.56%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 27        | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 26        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1601      | 38.06%  |
| 1 x Nvidia               | 876       | 20.82%  |
| 1 x AMD                  | 803       | 19.09%  |
| Intel + Nvidia           | 558       | 13.26%  |
| Intel + AMD              | 144       | 3.42%   |
| AMD + Nvidia             | 79        | 1.88%   |
| 2 x AMD                  | 61        | 1.45%   |
| Other                    | 46        | 1.09%   |
| 1 x Matrox               | 10        | 0.24%   |
| 1 x SiS                  | 6         | 0.14%   |
| 2 x Nvidia               | 5         | 0.12%   |
| 2 x Intel                | 5         | 0.12%   |
| 1 x VIA                  | 5         | 0.12%   |
| 3 x AMD                  | 2         | 0.05%   |
| Nvidia + ASPEED          | 2         | 0.05%   |
| 1 x ASPEED               | 2         | 0.05%   |
| 1 x S3 Graphics          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3321      | 78.03%  |
| Proprietary | 742       | 17.43%  |
| Unknown     | 193       | 4.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2136      | 49.42%  |
| 1.01-2.0   | 604       | 13.98%  |
| 0.01-0.5   | 571       | 13.21%  |
| 0.51-1.0   | 391       | 9.05%   |
| 3.01-4.0   | 292       | 6.76%   |
| 7.01-8.0   | 165       | 3.82%   |
| 5.01-6.0   | 113       | 2.61%   |
| 8.01-16.0  | 30        | 0.69%   |
| 2.01-3.0   | 16        | 0.37%   |
| 16.01-24.0 | 4         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 660       | 14.27%  |
| AU Optronics            | 537       | 11.61%  |
| LG Display              | 455       | 9.84%   |
| BOE                     | 336       | 7.26%   |
| Chimei Innolux          | 311       | 6.72%   |
| Dell                    | 275       | 5.95%   |
| Goldstar                | 259       | 5.6%    |
| Iiyama                  | 154       | 3.33%   |
| Philips                 | 148       | 3.2%    |
| Lenovo                  | 119       | 2.57%   |
| BenQ                    | 118       | 2.55%   |
| Hewlett-Packard         | 114       | 2.46%   |
| Acer                    | 107       | 2.31%   |
| Chi Mei Optoelectronics | 103       | 2.23%   |
| AOC                     | 95        | 2.05%   |
| NEC Computers           | 74        | 1.6%    |
| Eizo                    | 69        | 1.49%   |
| Ancor Communications    | 60        | 1.3%    |
| Sharp                   | 46        | 0.99%   |
| LG Philips              | 40        | 0.86%   |
| Fujitsu Siemens         | 33        | 0.71%   |
| PANDA                   | 32        | 0.69%   |
| LG Electronics          | 32        | 0.69%   |
| Sony                    | 31        | 0.67%   |
| InfoVision              | 22        | 0.48%   |
| Apple                   | 22        | 0.48%   |
| ASUSTek Computer        | 21        | 0.45%   |
| Unknown                 | 17        | 0.37%   |
| Toshiba                 | 16        | 0.35%   |
| HannStar                | 15        | 0.32%   |
| ViewSonic               | 14        | 0.3%    |
| Panasonic               | 14        | 0.3%    |
| CPT                     | 14        | 0.3%    |
| Idek Iiyama             | 13        | 0.28%   |
| Gateway                 | 13        | 0.28%   |
| MSI                     | 12        | 0.26%   |
| Belinea                 | 12        | 0.26%   |
| LGD                     | 9         | 0.19%   |
| Hitachi                 | 9         | 0.19%   |
| Vestel Elektronik       | 8         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.6%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 28        | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 22        | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 22        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.44%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 19        | 0.39%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 19        | 0.39%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 17        | 0.35%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 17        | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 16        | 0.33%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 15        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 15        | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.31%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 14        | 0.29%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 14        | 0.29%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 13        | 0.27%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.27%   |
| LG Display LCD Monitor LGD0469 1920x1080 380x210mm 17.1-inch             | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 12        | 0.25%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.25%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 11        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 11        | 0.23%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.23%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.23%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 11        | 0.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 11        | 0.23%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 10        | 0.21%   |
| Goldstar 2D FHD TV GSM59C6 1920x1080 509x286mm 23.0-inch                 | 10        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 10        | 0.21%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.21%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch    | 9         | 0.19%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 9         | 0.19%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 9         | 0.19%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 9         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1862      | 42.47%  |
| 1366x768 (WXGA)    | 751       | 17.13%  |
| 1280x1024 (SXGA)   | 207       | 4.72%   |
| 1600x900 (HD+)     | 198       | 4.52%   |
| 3840x2160 (4K)     | 193       | 4.4%    |
| 2560x1440 (QHD)    | 184       | 4.2%    |
| 1280x800 (WXGA)    | 174       | 3.97%   |
| 1680x1050 (WSXGA+) | 166       | 3.79%   |
| 1920x1200 (WUXGA)  | 153       | 3.49%   |
| 1440x900 (WXGA+)   | 127       | 2.9%    |
| Unknown            | 42        | 0.96%   |
| 3440x1440          | 38        | 0.87%   |
| 2560x1080          | 38        | 0.87%   |
| 1024x600           | 26        | 0.59%   |
| 2560x1600          | 22        | 0.5%    |
| 1360x768           | 22        | 0.5%    |
| 1024x768 (XGA)     | 21        | 0.48%   |
| 3840x1080          | 19        | 0.43%   |
| 1600x1200          | 18        | 0.41%   |
| 1920x540           | 10        | 0.23%   |
| 800x1280           | 9         | 0.21%   |
| 2160x1440          | 9         | 0.21%   |
| 3840x2400          | 6         | 0.14%   |
| 3200x1800 (QHD+)   | 6         | 0.14%   |
| 2880x1800          | 6         | 0.14%   |
| 1280x720 (HD)      | 6         | 0.14%   |
| 2048x1152          | 5         | 0.11%   |
| 2288x1287          | 4         | 0.09%   |
| 1680x945           | 4         | 0.09%   |
| 1400x1050          | 4         | 0.09%   |
| 5120x1440          | 3         | 0.07%   |
| 3840x1600          | 3         | 0.07%   |
| 3286x1080          | 3         | 0.07%   |
| 3200x1080          | 3         | 0.07%   |
| 1280x960           | 3         | 0.07%   |
| 1280x768           | 3         | 0.07%   |
| 3840x1200          | 2         | 0.05%   |
| 3600x1080          | 2         | 0.05%   |
| 3456x2160          | 2         | 0.05%   |
| 3000x2000          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1260      | 27.23%  |
| 24      | 362       | 7.82%   |
| 13      | 345       | 7.45%   |
| 14      | 330       | 7.13%   |
| 23      | 312       | 6.74%   |
| 17      | 305       | 6.59%   |
| 21      | 275       | 5.94%   |
| 27      | 271       | 5.86%   |
| Unknown | 247       | 5.34%   |
| 19      | 168       | 3.63%   |
| 22      | 99        | 2.14%   |
| 12      | 90        | 1.94%   |
| 34      | 68        | 1.47%   |
| 18      | 67        | 1.45%   |
| 31      | 55        | 1.19%   |
| 20      | 46        | 0.99%   |
| 11      | 36        | 0.78%   |
| 10      | 29        | 0.63%   |
| 84      | 28        | 0.61%   |
| 25      | 26        | 0.56%   |
| 72      | 24        | 0.52%   |
| 32      | 22        | 0.48%   |
| 16      | 22        | 0.48%   |
| 40      | 20        | 0.43%   |
| 54      | 18        | 0.39%   |
| 48      | 15        | 0.32%   |
| 33      | 10        | 0.22%   |
| 65      | 8         | 0.17%   |
| 42      | 8         | 0.17%   |
| 28      | 8         | 0.17%   |
| 49      | 7         | 0.15%   |
| 46      | 6         | 0.13%   |
| 26      | 6         | 0.13%   |
| 37      | 5         | 0.11%   |
| 43      | 4         | 0.09%   |
| 39      | 4         | 0.09%   |
| 142     | 3         | 0.06%   |
| 55      | 3         | 0.06%   |
| 35      | 3         | 0.06%   |
| 29      | 3         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1828      | 40.25%  |
| 501-600        | 893       | 19.66%  |
| 401-500        | 544       | 11.98%  |
| 351-400        | 377       | 8.3%    |
| 201-300        | 303       | 6.67%   |
| Unknown        | 247       | 5.44%   |
| 701-800        | 100       | 2.2%    |
| 601-700        | 84        | 1.85%   |
| 1001-1500      | 63        | 1.39%   |
| 1501-2000      | 52        | 1.14%   |
| 801-900        | 33        | 0.73%   |
| 901-1000       | 12        | 0.26%   |
| More than 2000 | 3         | 0.07%   |
| 1-100          | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2947      | 70.65%  |
| 16/10   | 620       | 14.86%  |
| Unknown | 212       | 5.08%   |
| 5/4     | 192       | 4.6%    |
| 21/9    | 75        | 1.8%    |
| 4/3     | 49        | 1.17%   |
| 3/2     | 46        | 1.1%    |
| 32/9    | 13        | 0.31%   |
| 0.62    | 7         | 0.17%   |
| 6/5     | 5         | 0.12%   |
| 1.00    | 3         | 0.07%   |
| 0.67    | 2         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1254      | 27.34%  |
| 201-250        | 799       | 17.42%  |
| 81-90          | 543       | 11.84%  |
| 151-200        | 285       | 6.21%   |
| 301-350        | 275       | 6%      |
| Unknown        | 247       | 5.39%   |
| 251-300        | 186       | 4.06%   |
| 121-130        | 174       | 3.79%   |
| 351-500        | 164       | 3.58%   |
| 141-150        | 142       | 3.1%    |
| 71-80          | 123       | 2.68%   |
| More than 1000 | 103       | 2.25%   |
| 61-70          | 88        | 1.92%   |
| 501-1000       | 57        | 1.24%   |
| 131-140        | 42        | 0.92%   |
| 51-60          | 36        | 0.78%   |
| 41-50          | 29        | 0.63%   |
| 91-100         | 19        | 0.41%   |
| 111-120        | 17        | 0.37%   |
| 1-40           | 3         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1574      | 35.41%  |
| 121-160       | 1197      | 26.93%  |
| 101-120       | 1119      | 25.17%  |
| Unknown       | 247       | 5.56%   |
| 161-240       | 160       | 3.6%    |
| 1-50          | 89        | 2%      |
| More than 240 | 59        | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3376      | 78.82%  |
| 2     | 627       | 14.64%  |
| 0     | 171       | 3.99%   |
| 3     | 94        | 2.19%   |
| 4     | 13        | 0.3%    |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2113      | 32.73%  |
| Intel                                  | 2041      | 31.62%  |
| Qualcomm Atheros                       | 797       | 12.35%  |
| Broadcom                               | 376       | 5.82%   |
| Broadcom Limited                       | 113       | 1.75%   |
| TP-Link                                | 93        | 1.44%   |
| Marvell Technology Group               | 87        | 1.35%   |
| Huawei Technologies                    | 85        | 1.32%   |
| Dell                                   | 66        | 1.02%   |
| Ralink                                 | 65        | 1.01%   |
| Ralink Technology                      | 63        | 0.98%   |
| Nvidia                                 | 61        | 0.95%   |
| MediaTek                               | 54        | 0.84%   |
| Qualcomm Atheros Communications        | 42        | 0.65%   |
| Samsung Electronics                    | 36        | 0.56%   |
| Xiaomi                                 | 32        | 0.5%    |
| Microsoft                              | 27        | 0.42%   |
| Ericsson Business Mobile Networks      | 25        | 0.39%   |
| ASUSTek Computer                       | 24        | 0.37%   |
| Hewlett-Packard                        | 21        | 0.33%   |
| Sierra Wireless                        | 16        | 0.25%   |
| JMicron Technology                     | 15        | 0.23%   |
| Lenovo                                 | 13        | 0.2%    |
| Motorola PCS                           | 11        | 0.17%   |
| ASIX Electronics                       | 11        | 0.17%   |
| VIA Technologies                       | 10        | 0.15%   |
| Edimax Technology                      | 10        | 0.15%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.14%   |
| Aquantia                               | 9         | 0.14%   |
| NetGear                                | 8         | 0.12%   |
| Fibocom                                | 8         | 0.12%   |
| DisplayLink                            | 8         | 0.12%   |
| D-Link                                 | 8         | 0.12%   |
| Qualcomm                               | 7         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 5         | 0.08%   |
| Microchip Technology                   | 5         | 0.08%   |
| HTC (High Tech Computer)               | 5         | 0.08%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.06%   |
| Sagem                                  | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1536      | 20.35%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 234       | 3.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 213       | 2.82%   |
| Intel Wi-Fi 6 AX200                                               | 152       | 2.01%   |
| Intel Wireless 8265 / 8275                                        | 114       | 1.51%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 112       | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 109       | 1.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 107       | 1.42%   |
| Intel Wireless 7260                                               | 102       | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 91        | 1.21%   |
| Intel Wireless 8260                                               | 87        | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 82        | 1.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 78        | 1.03%   |
| Intel I211 Gigabit Network Connection                             | 74        | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 73        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 70        | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 70        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 65        | 0.86%   |
| Intel Ethernet Connection I217-LM                                 | 65        | 0.86%   |
| Intel Wireless 7265                                               | 64        | 0.85%   |
| Intel Wi-Fi 6 AX201                                               | 62        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 60        | 0.8%    |
| Intel Wireless 3160                                               | 56        | 0.74%   |
| Intel Wireless 3165                                               | 55        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 53        | 0.7%    |
| Intel 82579V Gigabit Network Connection                           | 51        | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 50        | 0.66%   |
| Intel 82567LM Gigabit Network Connection                          | 49        | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 48        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 47        | 0.62%   |
| Huawei E353/E3131                                                 | 47        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 46        | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 46        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 46        | 0.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 45        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 45        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                    | 44        | 0.58%   |
| Intel Ethernet Connection I218-LM                                 | 42        | 0.56%   |
| Intel WiFi Link 5100                                              | 41        | 0.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 41        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1568      | 46.96%  |
| Qualcomm Atheros                  | 606       | 18.15%  |
| Realtek Semiconductor             | 402       | 12.04%  |
| Broadcom                          | 220       | 6.59%   |
| TP-Link                           | 88        | 2.64%   |
| Ralink                            | 65        | 1.95%   |
| Ralink Technology                 | 63        | 1.89%   |
| Broadcom Limited                  | 55        | 1.65%   |
| MediaTek                          | 51        | 1.53%   |
| Qualcomm Atheros Communications   | 42        | 1.26%   |
| Dell                              | 40        | 1.2%    |
| Microsoft                         | 27        | 0.81%   |
| ASUSTek Computer                  | 24        | 0.72%   |
| Sierra Wireless                   | 16        | 0.48%   |
| Edimax Technology                 | 10        | 0.3%    |
| Fibocom                           | 8         | 0.24%   |
| Ericsson Business Mobile Networks | 8         | 0.24%   |
| D-Link                            | 8         | 0.24%   |
| NetGear                           | 7         | 0.21%   |
| Hewlett-Packard                   | 5         | 0.15%   |
| Sagem                             | 4         | 0.12%   |
| Qualcomm                          | 4         | 0.12%   |
| Belkin Components                 | 3         | 0.09%   |
| ZyXEL Communications              | 2         | 0.06%   |
| ZyDAS                             | 2         | 0.06%   |
| Linksys                           | 2         | 0.06%   |
| D-Link System                     | 2         | 0.06%   |
| Z-Com                             | 1         | 0.03%   |
| Wacom                             | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| Marvell Technology Group          | 1         | 0.03%   |
| IMC Networks                      | 1         | 0.03%   |
| AVM                               | 1         | 0.03%   |
| Accton Technology                 | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 152       | 4.54%   |
| Intel Wireless 8265 / 8275                                              | 114       | 3.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 112       | 3.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 109       | 3.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 107       | 3.2%    |
| Intel Wireless 7260                                                     | 102       | 3.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 91        | 2.72%   |
| Intel Wireless 8260                                                     | 87        | 2.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 82        | 2.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 78        | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 70        | 2.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 70        | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 65        | 1.94%   |
| Intel Wireless 7265                                                     | 64        | 1.91%   |
| Intel Wi-Fi 6 AX201                                                     | 62        | 1.85%   |
| Intel Wireless 3160                                                     | 56        | 1.67%   |
| Intel Wireless 3165                                                     | 55        | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 50        | 1.49%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 48        | 1.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 46        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 46        | 1.37%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 46        | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 45        | 1.34%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 45        | 1.34%   |
| Intel Centrino Ultimate-N 6300                                          | 44        | 1.31%   |
| Intel WiFi Link 5100                                                    | 41        | 1.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 41        | 1.22%   |
| Broadcom BCM43142 802.11b/g/n                                           | 39        | 1.16%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 38        | 1.14%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 35        | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 35        | 1.05%   |
| Intel Wireless-AC 9260                                                  | 34        | 1.02%   |
| Qualcomm Atheros AR9271 802.11n                                         | 32        | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 0.96%   |
| Intel Centrino Advanced-N 6200                                          | 32        | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 29        | 0.87%   |
| Intel Centrino Advanced-N 6235                                          | 29        | 0.87%   |
| Ralink MT7601U Wireless Adapter                                         | 28        | 0.84%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 28        | 0.84%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 27        | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1953      | 48.58%  |
| Intel                                  | 1121      | 27.89%  |
| Qualcomm Atheros                       | 275       | 6.84%   |
| Broadcom                               | 192       | 4.78%   |
| Marvell Technology Group               | 87        | 2.16%   |
| Nvidia                                 | 61        | 1.52%   |
| Broadcom Limited                       | 59        | 1.47%   |
| Huawei Technologies                    | 58        | 1.44%   |
| Samsung Electronics                    | 35        | 0.87%   |
| Xiaomi                                 | 31        | 0.77%   |
| JMicron Technology                     | 15        | 0.37%   |
| Lenovo                                 | 13        | 0.32%   |
| ASIX Electronics                       | 11        | 0.27%   |
| VIA Technologies                       | 10        | 0.25%   |
| Motorola PCS                           | 10        | 0.25%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.22%   |
| Aquantia                               | 9         | 0.22%   |
| DisplayLink                            | 8         | 0.2%    |
| TP-Link                                | 6         | 0.15%   |
| Microchip Technology                   | 5         | 0.12%   |
| HTC (High Tech Computer)               | 5         | 0.12%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.1%    |
| ZTE WCDMA Technologies MSM             | 3         | 0.07%   |
| Qualcomm                               | 3         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.07%   |
| Hewlett-Packard                        | 3         | 0.07%   |
| Attansic Technology                    | 3         | 0.07%   |
| Apple                                  | 3         | 0.07%   |
| Research In Motion                     | 2         | 0.05%   |
| QLogic                                 | 2         | 0.05%   |
| OPPO Electronics                       | 2         | 0.05%   |
| MediaTek                               | 2         | 0.05%   |
| ICS Advent                             | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| 3Com                                   | 2         | 0.05%   |
| QinHeng Electronics                    | 1         | 0.02%   |
| NetXen Incorporated                    | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Mellanox Technologies                  | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1536      | 37.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 234       | 5.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 213       | 5.22%   |
| Intel I211 Gigabit Network Connection                             | 74        | 1.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 73        | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 65        | 1.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 60        | 1.47%   |
| Intel Ethernet Connection (2) I219-V                              | 53        | 1.3%    |
| Intel 82579V Gigabit Network Connection                           | 51        | 1.25%   |
| Intel 82567LM Gigabit Network Connection                          | 49        | 1.2%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 47        | 1.15%   |
| Huawei E353/E3131                                                 | 47        | 1.15%   |
| Intel Ethernet Connection I218-LM                                 | 42        | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 39        | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 37        | 0.91%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 35        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 33        | 0.81%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 32        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 32        | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 32        | 0.78%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 30        | 0.74%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                             | 29        | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 29        | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 27        | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 26        | 0.64%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 24        | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 24        | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 22        | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 22        | 0.54%   |
| Intel Ethernet Controller I225-V                                  | 22        | 0.54%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 22        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21        | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 21        | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 19        | 0.47%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 19        | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 18        | 0.44%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 18        | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 18        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 18        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3771      | 53.7%   |
| WiFi     | 3136      | 44.65%  |
| Modem    | 104       | 1.48%   |
| Unknown  | 12        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2409      | 56.7%   |
| Ethernet | 1839      | 43.28%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2459      | 58.73%  |
| 1     | 1566      | 37.4%   |
| 0     | 88        | 2.1%    |
| 3     | 56        | 1.34%   |
| 4     | 9         | 0.21%   |
| 5     | 3         | 0.07%   |
| 6     | 2         | 0.05%   |
| 17    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3927      | 93.41%  |
| Yes  | 277       | 6.59%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1076      | 45.44%  |
| Qualcomm Atheros Communications | 230       | 9.71%   |
| Broadcom                        | 172       | 7.26%   |
| Realtek Semiconductor           | 150       | 6.33%   |
| Cambridge Silicon Radio         | 145       | 6.12%   |
| IMC Networks                    | 98        | 4.14%   |
| ASUSTek Computer                | 84        | 3.55%   |
| Dell                            | 81        | 3.42%   |
| Foxconn / Hon Hai               | 63        | 2.66%   |
| Hewlett-Packard                 | 59        | 2.49%   |
| Lite-On Technology              | 56        | 2.36%   |
| Apple                           | 30        | 1.27%   |
| Toshiba                         | 24        | 1.01%   |
| Ralink                          | 17        | 0.72%   |
| Foxconn International           | 14        | 0.59%   |
| Realtek                         | 11        | 0.46%   |
| MediaTek                        | 8         | 0.34%   |
| Integrated System Solution      | 7         | 0.3%    |
| Chicony Electronics             | 6         | 0.25%   |
| TP-Link                         | 5         | 0.21%   |
| Taiyo Yuden                     | 5         | 0.21%   |
| Edimax Technology               | 5         | 0.21%   |
| Alps Electric                   | 5         | 0.21%   |
| Ralink Technology               | 3         | 0.13%   |
| Micro Star International        | 2         | 0.08%   |
| Conwise Technology              | 2         | 0.08%   |
| USI                             | 1         | 0.04%   |
| SIN                             | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 472       | 19.92%  |
| Intel Bluetooth Device                              | 156       | 6.59%   |
| Intel AX200 Bluetooth                               | 146       | 6.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 145       | 6.12%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 140       | 5.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 99        | 4.18%   |
| Realtek Bluetooth Radio                             | 95        | 4.01%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 52        | 2.2%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 51        | 2.15%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 48        | 2.03%   |
| Intel Wireless-AC 3168 Bluetooth                    | 45        | 1.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 41        | 1.73%   |
| IMC Networks Bluetooth Radio                        | 38        | 1.6%    |
| Broadcom BCM2045B (BDC-2.1)                         | 37        | 1.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.48%   |
| Realtek  Bluetooth 4.2 Adapter                      | 32        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 30        | 1.27%   |
| Lite-On Bluetooth Device                            | 29        | 1.22%   |
| Dell BCM20702A0 Bluetooth Module                    | 26        | 1.1%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 23        | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 0.97%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 0.93%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.89%   |
| IMC Networks Bluetooth Device                       | 19        | 0.8%    |
| IMC Networks Wireless_Device                        | 18        | 0.76%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 0.72%   |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 0.72%   |
| Realtek RTL8723B Bluetooth                          | 16        | 0.68%   |
| Foxconn / Hon Hai Wireless_Device                   | 15        | 0.63%   |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 0.59%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.55%   |
| Intel AX210 Bluetooth                               | 13        | 0.55%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.55%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.55%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.51%   |
| Apple Bluetooth Host Controller                     | 12        | 0.51%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.46%   |
| Realtek Bluetooth Radio                             | 11        | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3025      | 52.8%   |
| AMD                                  | 1133      | 19.78%  |
| Nvidia                               | 1029      | 17.96%  |
| Creative Labs                        | 77        | 1.34%   |
| C-Media Electronics                  | 77        | 1.34%   |
| Creative Technology                  | 41        | 0.72%   |
| Logitech                             | 22        | 0.38%   |
| Realtek Semiconductor                | 20        | 0.35%   |
| VIA Technologies                     | 19        | 0.33%   |
| Texas Instruments                    | 18        | 0.31%   |
| JMTek                                | 18        | 0.31%   |
| Plantronics                          | 17        | 0.3%    |
| Lenovo                               | 14        | 0.24%   |
| SteelSeries ApS                      | 13        | 0.23%   |
| Kingston Technology                  | 12        | 0.21%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.19%   |
| GYROCOM C&C                          | 11        | 0.19%   |
| Dell                                 | 11        | 0.19%   |
| GN Netcom                            | 9         | 0.16%   |
| Generalplus Technology               | 8         | 0.14%   |
| SAVITECH                             | 7         | 0.12%   |
| Focusrite-Novation                   | 7         | 0.12%   |
| Razer USA                            | 6         | 0.1%    |
| BEHRINGER International              | 6         | 0.1%    |
| ASUSTek Computer                     | 6         | 0.1%    |
| Samson Technologies                  | 5         | 0.09%   |
| Hewlett-Packard                      | 5         | 0.09%   |
| AudioQuest                           | 5         | 0.09%   |
| Valve Software                       | 4         | 0.07%   |
| RODE Microphones                     | 4         | 0.07%   |
| M-Audio                              | 4         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.05%   |
| Sony                                 | 3         | 0.05%   |
| Sennheiser Communications            | 3         | 0.05%   |
| PreSonus Audio Electronics           | 3         | 0.05%   |
| Corsair                              | 3         | 0.05%   |
| Cambridge Audio                      | 3         | 0.05%   |
| AOKEO                                | 3         | 0.05%   |
| XMOS                                 | 2         | 0.03%   |
| ULi Electronics                      | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 342       | 5.07%   |
| AMD Family 17h/19h HD Audio Controller                                     | 281       | 4.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 268       | 3.98%   |
| Intel Sunrise Point-LP HD Audio                                            | 252       | 3.74%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 211       | 3.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 206       | 3.06%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 174       | 2.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 173       | 2.57%   |
| Intel Cannon Lake PCH cAVS                                                 | 167       | 2.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 154       | 2.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 153       | 2.27%   |
| AMD Starship/Matisse HD Audio Controller                                   | 140       | 2.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 139       | 2.06%   |
| AMD FCH Azalia Controller                                                  | 131       | 1.94%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 129       | 1.91%   |
| Intel 8 Series HD Audio Controller                                         | 124       | 1.84%   |
| Intel Haswell-ULT HD Audio Controller                                      | 122       | 1.81%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 115       | 1.71%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 113       | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                            | 102       | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 102       | 1.51%   |
| Intel Broadwell-U Audio Controller                                         | 98        | 1.45%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 96        | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 86        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                              | 84        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 81        | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 79        | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 74        | 1.1%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 69        | 1.02%   |
| Nvidia GP106 High Definition Audio Controller                              | 66        | 0.98%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 59        | 0.88%   |
| Intel 200 Series PCH HD Audio                                              | 59        | 0.88%   |
| Intel CM238 HD Audio Controller                                            | 57        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 56        | 0.83%   |
| Nvidia TU116 High Definition Audio Controller                              | 51        | 0.76%   |
| Nvidia High Definition Audio Controller                                    | 51        | 0.76%   |
| Nvidia GP104 High Definition Audio Controller                              | 51        | 0.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 49        | 0.73%   |
| Nvidia GK107 HDMI Audio Controller                                         | 45        | 0.67%   |
| AMD Kabini HDMI/DP Audio                                                   | 45        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 640       | 20.9%   |
| SK hynix                     | 504       | 16.46%  |
| Kingston                     | 414       | 13.52%  |
| Unknown                      | 376       | 12.28%  |
| Micron Technology            | 243       | 7.94%   |
| GOODRAM                      | 183       | 5.98%   |
| Crucial                      | 139       | 4.54%   |
| G.Skill                      | 87        | 2.84%   |
| Corsair                      | 71        | 2.32%   |
| A-DATA Technology            | 69        | 2.25%   |
| Ramaxel Technology           | 53        | 1.73%   |
| Nanya Technology             | 51        | 1.67%   |
| Patriot                      | 49        | 1.6%    |
| Elpida                       | 42        | 1.37%   |
| Unknown                      | 21        | 0.69%   |
| Wilk                         | 16        | 0.52%   |
| Qimonda                      | 13        | 0.42%   |
| Unknown (ABCD)               | 10        | 0.33%   |
| Apacer                       | 10        | 0.33%   |
| Wilk Elektronik              | 9         | 0.29%   |
| GeIL                         | 9         | 0.29%   |
| ASint Technology             | 9         | 0.29%   |
| Unifosa                      | 4         | 0.13%   |
| 48spaces                     | 4         | 0.13%   |
| Patriot Memory (PDP Systems) | 3         | 0.1%    |
| OCZ                          | 3         | 0.1%    |
| Transcend                    | 2         | 0.07%   |
| Toshiba                      | 2         | 0.07%   |
| Silicon Power                | 2         | 0.07%   |
| SHARETRONIC                  | 2         | 0.07%   |
| AMD                          | 2         | 0.07%   |
| Aeneon                       | 2         | 0.07%   |
| Unknown (8A02)               | 1         | 0.03%   |
| Unknown (768A)               | 1         | 0.03%   |
| Unknown (0x0702)             | 1         | 0.03%   |
| tigo                         | 1         | 0.03%   |
| Team                         | 1         | 0.03%   |
| Swissbit                     | 1         | 0.03%   |
| Smart                        | 1         | 0.03%   |
| PNY                          | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s     | 36        | 1.07%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 28        | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 26        | 0.78%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s | 25        | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 24        | 0.72%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 23        | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 23        | 0.69%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 21        | 0.63%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s   | 21        | 0.63%   |
| Unknown                                                   | 21        | 0.63%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 20        | 0.6%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 20        | 0.6%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 20        | 0.6%    |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s     | 19        | 0.57%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                    | 18        | 0.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 18        | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 18        | 0.54%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s    | 17        | 0.51%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s      | 15        | 0.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 15        | 0.45%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 15        | 0.45%   |
| Patriot RAM 3200 C16 Series 32GB DIMM DDR4 3266MT/s       | 15        | 0.45%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s     | 15        | 0.45%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s   | 15        | 0.45%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 14        | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                   | 13        | 0.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 13        | 0.39%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s     | 13        | 0.39%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 13        | 0.39%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s   | 13        | 0.39%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                   | 12        | 0.36%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 12        | 0.36%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s          | 12        | 0.36%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 12        | 0.36%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s       | 12        | 0.36%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 11        | 0.33%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s     | 11        | 0.33%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 11        | 0.33%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s      | 11        | 0.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s      | 11        | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1022      | 39.4%   |
| DDR3    | 955       | 36.82%  |
| DDR2    | 219       | 8.44%   |
| Unknown | 127       | 4.9%    |
| SDRAM   | 125       | 4.82%   |
| LPDDR4  | 51        | 1.97%   |
| LPDDR3  | 39        | 1.5%    |
| DDR     | 31        | 1.2%    |
| DDR5    | 16        | 0.62%   |
| DRAM    | 6         | 0.23%   |
| LPDDR5  | 3         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1532      | 60.2%   |
| DIMM         | 909       | 35.72%  |
| Row Of Chips | 83        | 3.26%   |
| Chip         | 11        | 0.43%   |
| Unknown      | 7         | 0.28%   |
| RIMM         | 2         | 0.08%   |
| FB-DIMM      | 1         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 860       | 30.16%  |
| 4096    | 796       | 27.92%  |
| 2048    | 514       | 18.03%  |
| 16384   | 381       | 13.36%  |
| 1024    | 186       | 6.52%   |
| 32768   | 79        | 2.77%   |
| 512     | 26        | 0.91%   |
| Unknown | 4         | 0.14%   |
| 1536    | 2         | 0.07%   |
| 256     | 2         | 0.07%   |
| 64      | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 648       | 22.71%  |
| 2667    | 372       | 13.04%  |
| 3200    | 321       | 11.25%  |
| 1333    | 190       | 6.66%   |
| 2400    | 167       | 5.85%   |
| 667     | 122       | 4.28%   |
| 1334    | 121       | 4.24%   |
| 2133    | 115       | 4.03%   |
| 800     | 112       | 3.93%   |
| Unknown | 73        | 2.56%   |
| 3600    | 66        | 2.31%   |
| 1067    | 52        | 1.82%   |
| 4199    | 40        | 1.4%    |
| 1867    | 36        | 1.26%   |
| 533     | 31        | 1.09%   |
| 3266    | 26        | 0.91%   |
| 2048    | 25        | 0.88%   |
| 1066    | 25        | 0.88%   |
| 975     | 25        | 0.88%   |
| 3000    | 23        | 0.81%   |
| 3400    | 19        | 0.67%   |
| 400     | 19        | 0.67%   |
| 1866    | 16        | 0.56%   |
| 4267    | 15        | 0.53%   |
| 3466    | 15        | 0.53%   |
| 2933    | 15        | 0.53%   |
| 4800    | 14        | 0.49%   |
| 3866    | 14        | 0.49%   |
| 3733    | 13        | 0.46%   |
| 1800    | 12        | 0.42%   |
| 2666    | 11        | 0.39%   |
| 8400    | 10        | 0.35%   |
| 333     | 10        | 0.35%   |
| 3800    | 8         | 0.28%   |
| 2866    | 7         | 0.25%   |
| 49926   | 5         | 0.18%   |
| 4266    | 5         | 0.18%   |
| 2800    | 5         | 0.18%   |
| 6400    | 4         | 0.14%   |
| 3333    | 3         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 46        | 46%     |
| Samsung Electronics   | 14        | 14%     |
| Brother Industries    | 11        | 11%     |
| Canon                 | 10        | 10%     |
| Seiko Epson           | 7         | 7%      |
| Prolific Technology   | 5         | 5%      |
| Zebra                 | 2         | 2%      |
| Xerox                 | 2         | 2%      |
| MIIIW                 | 1         | 1%      |
| Lexmark International | 1         | 1%      |
| Datamax-O'Neil        | 1         | 1%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port           | 5         | 4.9%    |
| HP LaserJet 1020                        | 4         | 3.92%   |
| Canon iP7200 series                     | 3         | 2.94%   |
| Seiko Epson AL-M310DN                   | 2         | 1.96%   |
| Samsung SCX-3400 Series                 | 2         | 1.96%   |
| Samsung ML-216x Series Laser Printer    | 2         | 1.96%   |
| Samsung ML-2010P Mono Laser Printer     | 2         | 1.96%   |
| Samsung M2020 Series                    | 2         | 1.96%   |
| HP LaserJet P2015 series                | 2         | 1.96%   |
| HP LaserJet P1102                       | 2         | 1.96%   |
| HP LaserJet M14-M17                     | 2         | 1.96%   |
| HP Deskjet F4500 series                 | 2         | 1.96%   |
| HP DeskJet F4100 Printer series         | 2         | 1.96%   |
| HP Deskjet F2280 series                 | 2         | 1.96%   |
| HP DeskJet 845c                         | 2         | 1.96%   |
| HP DeskJet 840c                         | 2         | 1.96%   |
| HP DeskJet 3700 series                  | 2         | 1.96%   |
| HP DeskJet 2600 series                  | 2         | 1.96%   |
| HP Deskjet 2540 series                  | 2         | 1.96%   |
| HP Deskjet 1050 J410                    | 2         | 1.96%   |
| Canon MG5600 series                     | 2         | 1.96%   |
| Canon LiDE 400                          | 2         | 1.96%   |
| Brother DCP-J105                        | 2         | 1.96%   |
| Brother DCP-1610W                       | 2         | 1.96%   |
| Zebra ZTC GX420t                        | 1         | 0.98%   |
| Zebra LP2844 Printer                    | 1         | 0.98%   |
| Xerox WorkCentre PE16                   | 1         | 0.98%   |
| Xerox Phaser 6000B                      | 1         | 0.98%   |
| Seiko Epson Stylus NX230/SX235W Series  | 1         | 0.98%   |
| Seiko Epson L405 Series                 | 1         | 0.98%   |
| Seiko Epson L396 Series                 | 1         | 0.98%   |
| Seiko Epson L1110 Series                | 1         | 0.98%   |
| Seiko Epson ET-2710 Series              | 1         | 0.98%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 0.98%   |
| Samsung SCX-6545 Series                 | 1         | 0.98%   |
| Samsung SCX-4300 Series                 | 1         | 0.98%   |
| Samsung SCX-4200 series                 | 1         | 0.98%   |
| Samsung ML-3050/ML-3051 Laser Printer   | 1         | 0.98%   |
| Samsung ML-2540 Series Laser Printer    | 1         | 0.98%   |
| MIIIW MW Keyboard Air Mini              | 1         | 0.98%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 11        | 61.11%  |
| Seiko Epson                 | 2         | 11.11%  |
| Plustek                     | 2         | 11.11%  |
| Ultima Electronics          | 1         | 5.56%   |
| Microtek International      | 1         | 5.56%   |
| Acer Peripherals (now BenQ) | 1         | 5.56%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 3         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 11.11%  |
| Canon CanoScan LiDE 120                                  | 2         | 11.11%  |
| Canon CanoScan LiDE 110                                  | 2         | 11.11%  |
| Ultima Artec E+ 48U                                      | 1         | 5.56%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 5.56%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 5.56%   |
| Plustek OpticSlim 1200 Scanner                           | 1         | 5.56%   |
| Plustek OpticPro 1248U Scanner #2                        | 1         | 5.56%   |
| Microtek International USB1200 Scanner                   | 1         | 5.56%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 5.56%   |
| Canon CanoScan LIDE 25                                   | 1         | 5.56%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1         | 5.56%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 527       | 22.2%   |
| Microdia                               | 247       | 10.4%   |
| IMC Networks                           | 234       | 9.86%   |
| Realtek Semiconductor                  | 199       | 8.38%   |
| Acer                                   | 174       | 7.33%   |
| Sunplus Innovation Technology          | 121       | 5.1%    |
| Quanta                                 | 104       | 4.38%   |
| Suyin                                  | 100       | 4.21%   |
| Logitech                               | 90        | 3.79%   |
| Cheng Uei Precision Industry (Foxlink) | 80        | 3.37%   |
| Syntek                                 | 69        | 2.91%   |
| Lite-On Technology                     | 53        | 2.23%   |
| Silicon Motion                         | 50        | 2.11%   |
| Creative Technology                    | 33        | 1.39%   |
| Ricoh                                  | 27        | 1.14%   |
| Apple                                  | 27        | 1.14%   |
| Lenovo                                 | 24        | 1.01%   |
| Alcor Micro                            | 23        | 0.97%   |
| Z-Star Microelectronics                | 22        | 0.93%   |
| Luxvisions Innotech Limited            | 22        | 0.93%   |
| Microsoft                              | 17        | 0.72%   |
| Samsung Electronics                    | 16        | 0.67%   |
| DigiTech                               | 11        | 0.46%   |
| Primax Electronics                     | 9         | 0.38%   |
| Intel                                  | 8         | 0.34%   |
| Generalplus Technology                 | 8         | 0.34%   |
| ALi                                    | 8         | 0.34%   |
| Cubeternet                             | 7         | 0.29%   |
| Hewlett-Packard                        | 6         | 0.25%   |
| Sonix Technology                       | 5         | 0.21%   |
| LG Electronics                         | 4         | 0.17%   |
| Jieli Technology                       | 4         | 0.17%   |
| GEMBIRD                                | 4         | 0.17%   |
| Aveo Technology                        | 4         | 0.17%   |
| Xiongmai                               | 3         | 0.13%   |
| Trust                                  | 3         | 0.13%   |
| Sunplus Technology                     | 3         | 0.13%   |
| MacroSilicon                           | 3         | 0.13%   |
| Importek                               | 3         | 0.13%   |
| Valve Software                         | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 106       | 4.45%   |
| Microdia Integrated_Webcam_HD            | 78        | 3.27%   |
| Realtek Integrated_Webcam_HD             | 64        | 2.69%   |
| IMC Networks Integrated Camera           | 62        | 2.6%    |
| IMC Networks USB2.0 HD UVC WebCam        | 57        | 2.39%   |
| Sunplus Integrated_Webcam_HD             | 52        | 2.18%   |
| Acer Lenovo EasyCamera                   | 50        | 2.1%    |
| Chicony Lenovo EasyCamera                | 40        | 1.68%   |
| Microdia Integrated Webcam               | 37        | 1.55%   |
| Chicony HD Webcam                        | 36        | 1.51%   |
| Suyin Integrated_Webcam_HD               | 35        | 1.47%   |
| Acer Integrated Camera                   | 35        | 1.47%   |
| Syntek Lenovo EasyCamera                 | 29        | 1.22%   |
| Realtek Lenovo EasyCamera                | 25        | 1.05%   |
| Syntek Integrated Camera                 | 23        | 0.97%   |
| Lite-On Integrated Camera                | 23        | 0.97%   |
| Chicony USB2.0 HD UVC WebCam             | 23        | 0.97%   |
| Realtek USB Camera                       | 22        | 0.92%   |
| Logitech Webcam C270                     | 21        | 0.88%   |
| Quanta HP TrueVision HD Camera           | 20        | 0.84%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 20        | 0.84%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 18        | 0.76%   |
| Realtek Integrated Webcam HD             | 17        | 0.71%   |
| Quanta HD User Facing                    | 17        | 0.71%   |
| Creative Live! Cam Sync HD [VF0770]      | 17        | 0.71%   |
| Chicony HP HD Camera                     | 17        | 0.71%   |
| Microdia Laptop_Integrated_Webcam_HD     | 16        | 0.67%   |
| IMC Networks Integrated Webcam           | 16        | 0.67%   |
| Chicony USB 2.0 Camera                   | 16        | 0.67%   |
| Acer SunplusIT Integrated Camera         | 16        | 0.67%   |
| Samsung Galaxy A5 (MTP)                  | 15        | 0.63%   |
| Microdia USB 2.0 Camera                  | 15        | 0.63%   |
| Chicony USB2.0 VGA UVC WebCam            | 15        | 0.63%   |
| Chicony Integrated Camera (1280x720@30)  | 14        | 0.59%   |
| Realtek Integrated Webcam                | 13        | 0.55%   |
| Microdia Sonix USB 2.0 Camera            | 13        | 0.55%   |
| Chicony VGA WebCam                       | 13        | 0.55%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 13        | 0.55%   |
| Lite-On HP HD Camera                     | 12        | 0.5%    |
| Chicony HP HD Webcam [Fixed]             | 12        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 177       | 36.95%  |
| Synaptics                  | 116       | 24.22%  |
| Shenzhen Goodix Technology | 55        | 11.48%  |
| AuthenTec                  | 54        | 11.27%  |
| Upek                       | 34        | 7.1%    |
| LighTuning Technology      | 15        | 3.13%   |
| Elan Microelectronics      | 15        | 3.13%   |
| STMicroelectronics         | 13        | 2.71%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 40        | 8.35%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 7.31%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 6.89%   |
| Shenzhen Goodix  FingerPrint Device                                        | 29        | 6.05%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 24        | 5.01%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 22        | 4.59%   |
| AuthenTec AES2810                                                          | 22        | 4.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 21        | 4.38%   |
| Unknown                                                                    | 20        | 4.18%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 18        | 3.76%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 3.55%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.92%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 13        | 2.71%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 2.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 2.51%   |
| Validity Sensors VFS491                                                    | 12        | 2.51%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.09%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.88%   |
| Synaptics  WBDI                                                            | 9         | 1.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 1.67%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 1.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 1.67%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 1.67%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 1.46%   |
| AuthenTec AES1600                                                          | 7         | 1.46%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.25%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 1.04%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 1.04%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.04%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.04%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.84%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.84%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.84%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.84%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.84%   |
| Synaptics WBDI Device                                                      | 3         | 0.63%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.42%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.21%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 195       | 54.47%  |
| Alcor Micro               | 72        | 20.11%  |
| O2 Micro                  | 39        | 10.89%  |
| Lenovo                    | 20        | 5.59%   |
| Upek                      | 18        | 5.03%   |
| Gemalto (was Gemplus)     | 5         | 1.4%    |
| Advanced Card Systems     | 3         | 0.84%   |
| OmniKey                   | 2         | 0.56%   |
| SCM Microsystems          | 1         | 0.28%   |
| Clay Logic                | 1         | 0.28%   |
| Cherry                    | 1         | 0.28%   |
| Aladdin Knowledge Systems | 1         | 0.28%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 69        | 19.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 64        | 17.88%  |
| Broadcom 5880                                                                | 48        | 13.41%  |
| Broadcom 58200                                                               | 47        | 13.13%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 9.78%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 32        | 8.94%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 5.59%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 18        | 5.03%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.96%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.84%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.56%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.56%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.56%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.28%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.28%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.28%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.28%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.28%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.28%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.28%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2925      | 68.28%  |
| 1     | 1056      | 24.65%  |
| 2     | 256       | 5.98%   |
| 3     | 36        | 0.84%   |
| 4     | 5         | 0.12%   |
| 7     | 3         | 0.07%   |
| 5     | 2         | 0.05%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 473       | 28.58%  |
| Graphics card            | 397       | 23.99%  |
| Chipcard                 | 324       | 19.58%  |
| Net/wireless             | 138       | 8.34%   |
| Multimedia controller    | 53        | 3.2%    |
| Storage                  | 48        | 2.9%    |
| Bluetooth                | 43        | 2.6%    |
| Communication controller | 42        | 2.54%   |
| Camera                   | 33        | 1.99%   |
| Sound                    | 21        | 1.27%   |
| Unassigned class         | 20        | 1.21%   |
| Card reader              | 16        | 0.97%   |
| Modem                    | 8         | 0.48%   |
| Net/ethernet             | 7         | 0.42%   |
| Firewire controller      | 7         | 0.42%   |
| Network                  | 6         | 0.36%   |
| Dvb card                 | 6         | 0.36%   |
| Storage/raid             | 4         | 0.24%   |
| Storage/ide              | 4         | 0.24%   |
| Flash memory             | 3         | 0.18%   |
| Wireless                 | 1         | 0.06%   |
| Tv card                  | 1         | 0.06%   |

