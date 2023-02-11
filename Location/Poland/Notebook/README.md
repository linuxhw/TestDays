Linux in Poland - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 3713

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [62f941075c](https://linux-hardware.org/?probe=62f941075c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| Dell          | Latitude 5410               | [717012530d](https://linux-hardware.org/?probe=717012530d) | Jan 31, 2023 |
| Unknown       | Unknown                     | [e6c824b966](https://linux-hardware.org/?probe=e6c824b966) | Jan 31, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [aaaa563786](https://linux-hardware.org/?probe=aaaa563786) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | [d1e99e3f04](https://linux-hardware.org/?probe=d1e99e3f04) | Jan 30, 2023 |
| Toshiba       | Satellite P750              | [1cc0f342b5](https://linux-hardware.org/?probe=1cc0f342b5) | Jan 30, 2023 |
| Apple         | MacBookPro5,2               | [4cb11c2a78](https://linux-hardware.org/?probe=4cb11c2a78) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Inspiron 5758               | [de58233dca](https://linux-hardware.org/?probe=de58233dca) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| Dell          | Latitude 5480               | [ee87ac218f](https://linux-hardware.org/?probe=ee87ac218f) | Jan 30, 2023 |
| Dell          | Latitude 5480               | [3cbac640e1](https://linux-hardware.org/?probe=3cbac640e1) | Jan 30, 2023 |
| Dell          | Latitude 3190               | [a53530646a](https://linux-hardware.org/?probe=a53530646a) | Jan 30, 2023 |
| Dell          | Latitude E6520              | [81717ed3df](https://linux-hardware.org/?probe=81717ed3df) | Jan 30, 2023 |
| Apple         | MacBookPro11,1              | [e5af375b93](https://linux-hardware.org/?probe=e5af375b93) | Jan 29, 2023 |
| Apple         | MacBookPro11,1              | [41d67fcba8](https://linux-hardware.org/?probe=41d67fcba8) | Jan 29, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [e2fa9aa820](https://linux-hardware.org/?probe=e2fa9aa820) | Jan 29, 2023 |
| ASUSTek       | 1215B                       | [8d26a8d157](https://linux-hardware.org/?probe=8d26a8d157) | Jan 28, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [fb7b1bdaf5](https://linux-hardware.org/?probe=fb7b1bdaf5) | Jan 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [f6d7ba9d48](https://linux-hardware.org/?probe=f6d7ba9d48) | Jan 27, 2023 |
| HP            | EliteBook 640 14 inch G9... | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| ASUSTek       | X540SA                      | [93aed28230](https://linux-hardware.org/?probe=93aed28230) | Jan 27, 2023 |
| Kruger&Mat... | KM1406                      | [c944e8058f](https://linux-hardware.org/?probe=c944e8058f) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [bd7e955a3e](https://linux-hardware.org/?probe=bd7e955a3e) | Jan 27, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [1f74ea5c27](https://linux-hardware.org/?probe=1f74ea5c27) | Jan 27, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [af3748a4f0](https://linux-hardware.org/?probe=af3748a4f0) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440p 20AWS24B0... | [e4ddea6092](https://linux-hardware.org/?probe=e4ddea6092) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| HP            | EliteBook Folio 1040 G1     | [4811286faf](https://linux-hardware.org/?probe=4811286faf) | Jan 26, 2023 |
| Dell          | XPS 9320                    | [a1040b4a3f](https://linux-hardware.org/?probe=a1040b4a3f) | Jan 26, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [26f46d5b40](https://linux-hardware.org/?probe=26f46d5b40) | Jan 25, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [f1e6112f8c](https://linux-hardware.org/?probe=f1e6112f8c) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [baae797a05](https://linux-hardware.org/?probe=baae797a05) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [427a7fa0cb](https://linux-hardware.org/?probe=427a7fa0cb) | Jan 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [7fcc3fb992](https://linux-hardware.org/?probe=7fcc3fb992) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | Latitude E6520              | [baf618d1a1](https://linux-hardware.org/?probe=baf618d1a1) | Jan 25, 2023 |
| Dell          | Latitude E6520              | [615879d5e9](https://linux-hardware.org/?probe=615879d5e9) | Jan 24, 2023 |
| Dell          | Latitude 5420               | [cd6dc3695e](https://linux-hardware.org/?probe=cd6dc3695e) | Jan 24, 2023 |
| Lenovo        | ThinkPad T500 2082BPG       | [08a30fd24c](https://linux-hardware.org/?probe=08a30fd24c) | Jan 24, 2023 |
| Dell          | Latitude E5530 non-vPro     | [5ddcb9f78b](https://linux-hardware.org/?probe=5ddcb9f78b) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Dell          | Latitude 3190               | [7d38c480af](https://linux-hardware.org/?probe=7d38c480af) | Jan 23, 2023 |
| Dell          | Latitude E6500              | [ba7c36fe15](https://linux-hardware.org/?probe=ba7c36fe15) | Jan 23, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [ffe1ffc80e](https://linux-hardware.org/?probe=ffe1ffc80e) | Jan 23, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [d3686f2fc3](https://linux-hardware.org/?probe=d3686f2fc3) | Jan 21, 2023 |
| Dell          | Latitude 9420               | [4b847961df](https://linux-hardware.org/?probe=4b847961df) | Jan 21, 2023 |
| Dell          | Latitude 5501               | [72581be7e7](https://linux-hardware.org/?probe=72581be7e7) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| HP            | Pavilion dv5                | [94ba65752b](https://linux-hardware.org/?probe=94ba65752b) | Jan 20, 2023 |
| Acer          | Aspire A114-31              | [b341182acd](https://linux-hardware.org/?probe=b341182acd) | Jan 20, 2023 |
| Lenovo        | ThinkPad P51 20HJS1EJ1B     | [2ac4b56c2f](https://linux-hardware.org/?probe=2ac4b56c2f) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Dell          | Precision M6600             | [4d697ebfd5](https://linux-hardware.org/?probe=4d697ebfd5) | Jan 19, 2023 |
| Dell          | Inspiron 5567               | [a993e95dde](https://linux-hardware.org/?probe=a993e95dde) | Jan 19, 2023 |
| MSI           | Creator Z17 A12UHST         | [1fd7f0acb7](https://linux-hardware.org/?probe=1fd7f0acb7) | Jan 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [16f5041f1d](https://linux-hardware.org/?probe=16f5041f1d) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| Acer          | Aspire A114-31              | [30698dacda](https://linux-hardware.org/?probe=30698dacda) | Jan 19, 2023 |
| Dell          | Latitude 9420               | [3fd325486b](https://linux-hardware.org/?probe=3fd325486b) | Jan 18, 2023 |
| Alienware     | M17xR4                      | [5cce1e5932](https://linux-hardware.org/?probe=5cce1e5932) | Jan 18, 2023 |
| Dell          | Precision 5750              | [592f9624d3](https://linux-hardware.org/?probe=592f9624d3) | Jan 18, 2023 |
| MSI           | GP65 Leopard 10SFK          | [3c09479564](https://linux-hardware.org/?probe=3c09479564) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [2ad3913a19](https://linux-hardware.org/?probe=2ad3913a19) | Jan 18, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [6f463ee96b](https://linux-hardware.org/?probe=6f463ee96b) | Jan 18, 2023 |
| Dell          | Latitude D630               | [0d267a0217](https://linux-hardware.org/?probe=0d267a0217) | Jan 17, 2023 |
| HP            | Pavilion Gaming Notebook    | [03a01ae5f7](https://linux-hardware.org/?probe=03a01ae5f7) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [a49c7ed379](https://linux-hardware.org/?probe=a49c7ed379) | Jan 17, 2023 |
| Lenovo        | ThinkPad E480 20KN0064PB    | [9d20f03ffd](https://linux-hardware.org/?probe=9d20f03ffd) | Jan 17, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [aa6ca0d358](https://linux-hardware.org/?probe=aa6ca0d358) | Jan 17, 2023 |
| ASUSTek       | K53SJ                       | [267ce15a0c](https://linux-hardware.org/?probe=267ce15a0c) | Jan 17, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| Dell          | Inspiron 3583               | [79b74ef79b](https://linux-hardware.org/?probe=79b74ef79b) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [11ca9b863c](https://linux-hardware.org/?probe=11ca9b863c) | Jan 16, 2023 |
| Dell          | Inspiron 11 - 3147          | [af542a44ad](https://linux-hardware.org/?probe=af542a44ad) | Jan 16, 2023 |
| Dell          | Latitude 3190               | [96d1e3a219](https://linux-hardware.org/?probe=96d1e3a219) | Jan 16, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [dd953776aa](https://linux-hardware.org/?probe=dd953776aa) | Jan 16, 2023 |
| Lenovo        | ThinkPad T510 4384FF3       | [b62dac21bd](https://linux-hardware.org/?probe=b62dac21bd) | Jan 15, 2023 |
| Chuwi         | AeroBook Pro                | [13da35b0f7](https://linux-hardware.org/?probe=13da35b0f7) | Jan 15, 2023 |
| ASUSTek       | X510UQR                     | [2fb1d0a04c](https://linux-hardware.org/?probe=2fb1d0a04c) | Jan 14, 2023 |
| Acer          | AO725                       | [739986d5fa](https://linux-hardware.org/?probe=739986d5fa) | Jan 14, 2023 |
| Lenovo        | G585                        | [c7453a5e19](https://linux-hardware.org/?probe=c7453a5e19) | Jan 14, 2023 |
| MSI           | GE70 2QD                    | [5e408d7d3d](https://linux-hardware.org/?probe=5e408d7d3d) | Jan 14, 2023 |
| Dell          | Vostro 3550                 | [3f68ef3681](https://linux-hardware.org/?probe=3f68ef3681) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Samsung       | SR700                       | [329a7864c0](https://linux-hardware.org/?probe=329a7864c0) | Jan 13, 2023 |
| HP            | Notebook                    | [3fc38fa55e](https://linux-hardware.org/?probe=3fc38fa55e) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [05899ebb86](https://linux-hardware.org/?probe=05899ebb86) | Jan 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4236e82f21](https://linux-hardware.org/?probe=4236e82f21) | Jan 13, 2023 |
| HP            | ProBook 450 G6              | [f675188c46](https://linux-hardware.org/?probe=f675188c46) | Jan 12, 2023 |
| MSI           | GE70 2QD                    | [8dce1e9fdd](https://linux-hardware.org/?probe=8dce1e9fdd) | Jan 12, 2023 |
| Lenovo        | Legion Y740S-15IMH 81YX     | [b61eb04be5](https://linux-hardware.org/?probe=b61eb04be5) | Jan 11, 2023 |
| Sony          | VPCEJ2S1E                   | [f387a3dcf6](https://linux-hardware.org/?probe=f387a3dcf6) | Jan 11, 2023 |
| MSI           | GL75 9SE                    | [e3478b20bd](https://linux-hardware.org/?probe=e3478b20bd) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | [140d48870a](https://linux-hardware.org/?probe=140d48870a) | Jan 11, 2023 |
| ASUSTek       | 1215N                       | [f6588e6319](https://linux-hardware.org/?probe=f6588e6319) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b828defe64](https://linux-hardware.org/?probe=b828defe64) | Jan 11, 2023 |
| Dell          | Latitude D630               | [64877fdf78](https://linux-hardware.org/?probe=64877fdf78) | Jan 11, 2023 |
| ASUSTek       | X550CC                      | [2aa757ef35](https://linux-hardware.org/?probe=2aa757ef35) | Jan 10, 2023 |
| Samsung       | 550P5C/550P7C               | [33529c6c45](https://linux-hardware.org/?probe=33529c6c45) | Jan 10, 2023 |
| Acer          | Extensa 2540                | [6bddd00c3f](https://linux-hardware.org/?probe=6bddd00c3f) | Jan 10, 2023 |
| Dell          | Latitude E4310              | [1cd2d3300a](https://linux-hardware.org/?probe=1cd2d3300a) | Jan 09, 2023 |
| Dell          | Latitude E5470              | [41c1a02ca6](https://linux-hardware.org/?probe=41c1a02ca6) | Jan 09, 2023 |
| Chuwi         | GemiBook                    | [918dc5f283](https://linux-hardware.org/?probe=918dc5f283) | Jan 09, 2023 |
| Lenovo        | ThinkPad X201 3626D15       | [3d615a1b12](https://linux-hardware.org/?probe=3d615a1b12) | Jan 09, 2023 |
| Dell          | Latitude 3190               | [055e045e52](https://linux-hardware.org/?probe=055e045e52) | Jan 09, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| Samsung       | R780/R778                   | [e26d6dd084](https://linux-hardware.org/?probe=e26d6dd084) | Jan 08, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| Lenovo        | G51-35 80M8                 | [fe19098e1d](https://linux-hardware.org/?probe=fe19098e1d) | Jan 08, 2023 |
| Acer          | Aspire A315-41              | [b4ed141fd3](https://linux-hardware.org/?probe=b4ed141fd3) | Jan 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS0BX0T    | [e05bd2254f](https://linux-hardware.org/?probe=e05bd2254f) | Jan 08, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [de3c61df29](https://linux-hardware.org/?probe=de3c61df29) | Jan 08, 2023 |
| HP            | 655                         | [4c7544d7ad](https://linux-hardware.org/?probe=4c7544d7ad) | Jan 08, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [1ad8a2f766](https://linux-hardware.org/?probe=1ad8a2f766) | Jan 08, 2023 |
| HP            | ENVY m6                     | [b5089c7b29](https://linux-hardware.org/?probe=b5089c7b29) | Jan 07, 2023 |
| HP            | ProBook 5330m               | [37416931cd](https://linux-hardware.org/?probe=37416931cd) | Jan 07, 2023 |
| Lenovo        | S145-15API 81UT             | [fafc9e3fb7](https://linux-hardware.org/?probe=fafc9e3fb7) | Jan 07, 2023 |
| Apple         | MacBookPro9,2               | [e0e6ab58b6](https://linux-hardware.org/?probe=e0e6ab58b6) | Jan 06, 2023 |
| Dell          | Latitude E6520              | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| MSI           | Creator Z17 A12UHST         | [d0299b2518](https://linux-hardware.org/?probe=d0299b2518) | Jan 06, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c84d3b6b03](https://linux-hardware.org/?probe=c84d3b6b03) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | [117e9ffed7](https://linux-hardware.org/?probe=117e9ffed7) | Jan 06, 2023 |
| MSI           | GP76 Leopard 10UE           | [cacdaaf5c5](https://linux-hardware.org/?probe=cacdaaf5c5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | [bbedda14e5](https://linux-hardware.org/?probe=bbedda14e5) | Jan 05, 2023 |
| Acer          | NG-A715-72G-70F7            | [d2c2a681a2](https://linux-hardware.org/?probe=d2c2a681a2) | Jan 05, 2023 |
| Acer          | Aspire A715-74G             | [e0cf0ea368](https://linux-hardware.org/?probe=e0cf0ea368) | Jan 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [4853686d6c](https://linux-hardware.org/?probe=4853686d6c) | Jan 05, 2023 |
| ASUSTek       | K55VM                       | [d4d53ed49f](https://linux-hardware.org/?probe=d4d53ed49f) | Jan 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [307c51149d](https://linux-hardware.org/?probe=307c51149d) | Jan 03, 2023 |
| Acer          | Nitro AN515-55              | [c5bc3a8eae](https://linux-hardware.org/?probe=c5bc3a8eae) | Jan 03, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [1a3964dd30](https://linux-hardware.org/?probe=1a3964dd30) | Jan 03, 2023 |
| Dell          | XPS 13 7390                 | [b45f76c172](https://linux-hardware.org/?probe=b45f76c172) | Jan 03, 2023 |
| Lenovo        | ThinkPad T460s 20FAS5QW0... | [373efc41b0](https://linux-hardware.org/?probe=373efc41b0) | Jan 03, 2023 |
| Fujitsu       | LIFEBOOK S751               | [5fbed33610](https://linux-hardware.org/?probe=5fbed33610) | Jan 03, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [99ba91623a](https://linux-hardware.org/?probe=99ba91623a) | Jan 02, 2023 |
| Acer          | Aspire E1-571               | [eb3f1a0f5f](https://linux-hardware.org/?probe=eb3f1a0f5f) | Jan 02, 2023 |
| Dell          | Latitude 3190               | [19f42109a3](https://linux-hardware.org/?probe=19f42109a3) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | [c331237e28](https://linux-hardware.org/?probe=c331237e28) | Jan 02, 2023 |
| MSI           | PE60 6QE                    | [1ce680cb4d](https://linux-hardware.org/?probe=1ce680cb4d) | Jan 01, 2023 |
| Gigabyte      | RC14UD                      | [24d32a2b05](https://linux-hardware.org/?probe=24d32a2b05) | Jan 01, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [48c688033a](https://linux-hardware.org/?probe=48c688033a) | Dec 30, 2022 |
| ASUSTek       | K72F                        | [f761bf9bd6](https://linux-hardware.org/?probe=f761bf9bd6) | Dec 30, 2022 |
| Lenovo        | ThinkPad R61 8918DEG        | [82cbc15539](https://linux-hardware.org/?probe=82cbc15539) | Dec 30, 2022 |
| HP            | EliteBook 745 G5            | [d819dbd901](https://linux-hardware.org/?probe=d819dbd901) | Dec 30, 2022 |
| HP            | ProBook 450 G7              | [ca7468f975](https://linux-hardware.org/?probe=ca7468f975) | Dec 29, 2022 |
| Dell          | Latitude E6420              | [9733c425b6](https://linux-hardware.org/?probe=9733c425b6) | Dec 29, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [e232c2de6d](https://linux-hardware.org/?probe=e232c2de6d) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [03cca95360](https://linux-hardware.org/?probe=03cca95360) | Dec 27, 2022 |
| HP            | EliteBook 820 G3            | [95555948a2](https://linux-hardware.org/?probe=95555948a2) | Dec 27, 2022 |
| Acer          | Nitro AN515-44              | [58b02cceb0](https://linux-hardware.org/?probe=58b02cceb0) | Dec 27, 2022 |
| Dell          | Latitude 3190               | [f395b56cec](https://linux-hardware.org/?probe=f395b56cec) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [e0a09344e0](https://linux-hardware.org/?probe=e0a09344e0) | Dec 26, 2022 |
| ASUSTek       | X550LD                      | [d6948e7207](https://linux-hardware.org/?probe=d6948e7207) | Dec 26, 2022 |
| Acer          | Nitro AN515-31              | [249f50d430](https://linux-hardware.org/?probe=249f50d430) | Dec 25, 2022 |
| Lenovo        | ThinkPad T430 23472Y0       | [4a2d13391c](https://linux-hardware.org/?probe=4a2d13391c) | Dec 25, 2022 |
| GPU Compan... | GWTN141-10                  | [38ed4755c3](https://linux-hardware.org/?probe=38ed4755c3) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | [f3dc3c0121](https://linux-hardware.org/?probe=f3dc3c0121) | Dec 22, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [bf600b6f1c](https://linux-hardware.org/?probe=bf600b6f1c) | Dec 22, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [06d78a17c1](https://linux-hardware.org/?probe=06d78a17c1) | Dec 21, 2022 |
| Dell          | Precision 3520              | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [b1d6a6a73d](https://linux-hardware.org/?probe=b1d6a6a73d) | Dec 21, 2022 |
| ASUSTek       | N55SF                       | [bbec56fa90](https://linux-hardware.org/?probe=bbec56fa90) | Dec 21, 2022 |
| Dell          | G15 5510                    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| ASUSTek       | TUF Gaming FX505GE          | [094e72dc22](https://linux-hardware.org/?probe=094e72dc22) | Dec 20, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [0d59e38c20](https://linux-hardware.org/?probe=0d59e38c20) | Dec 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [37513092d6](https://linux-hardware.org/?probe=37513092d6) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Dell          | Vostro 15 3510              | [f2467d713d](https://linux-hardware.org/?probe=f2467d713d) | Dec 19, 2022 |
| Dell          | Latitude 3190               | [9227c8dbfb](https://linux-hardware.org/?probe=9227c8dbfb) | Dec 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [44a96b54b6](https://linux-hardware.org/?probe=44a96b54b6) | Dec 18, 2022 |
| Apple         | MacBookPro14,1              | [8c0c2353ab](https://linux-hardware.org/?probe=8c0c2353ab) | Dec 18, 2022 |
| Valve         | Jupiter                     | [72f897b9d3](https://linux-hardware.org/?probe=72f897b9d3) | Dec 17, 2022 |
| Toshiba       | Satellite L650              | [7ea253aa11](https://linux-hardware.org/?probe=7ea253aa11) | Dec 17, 2022 |
| Apple         | MacBookPro11,1              | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Dell          | Latitude E6330              | [ca6551bf8e](https://linux-hardware.org/?probe=ca6551bf8e) | Dec 17, 2022 |
| Dell          | Latitude E5570              | [cc58177561](https://linux-hardware.org/?probe=cc58177561) | Dec 17, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [0d7a54bc21](https://linux-hardware.org/?probe=0d7a54bc21) | Dec 16, 2022 |
| Dell          | Latitude E6410              | [173f8a8dc8](https://linux-hardware.org/?probe=173f8a8dc8) | Dec 16, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [4f63e7b8d1](https://linux-hardware.org/?probe=4f63e7b8d1) | Dec 15, 2022 |
| Dell          | Latitude 5420               | [5fa4cbba73](https://linux-hardware.org/?probe=5fa4cbba73) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Gigabyte      | MMLP3AP-00                  | [6b53aab624](https://linux-hardware.org/?probe=6b53aab624) | Dec 14, 2022 |
| Google        | Ultima                      | [867abc2b8f](https://linux-hardware.org/?probe=867abc2b8f) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| Dell          | Inspiron 3451               | [de7f9d5e33](https://linux-hardware.org/?probe=de7f9d5e33) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [f540185d6c](https://linux-hardware.org/?probe=f540185d6c) | Dec 14, 2022 |
| Dell          | XPS L501X                   | [32e195f4c6](https://linux-hardware.org/?probe=32e195f4c6) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [37284f659a](https://linux-hardware.org/?probe=37284f659a) | Dec 13, 2022 |
| MSI           | Creator Z17 A12UHST         | [61685b4f1a](https://linux-hardware.org/?probe=61685b4f1a) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [334ca886a4](https://linux-hardware.org/?probe=334ca886a4) | Dec 12, 2022 |
| HP            | Pavilion dv7                | [1e10e0306f](https://linux-hardware.org/?probe=1e10e0306f) | Dec 12, 2022 |
| Dell          | Latitude 3190               | [c2c5f3feb3](https://linux-hardware.org/?probe=c2c5f3feb3) | Dec 12, 2022 |
| Apple         | MacBookPro11,1              | [492b382af1](https://linux-hardware.org/?probe=492b382af1) | Dec 11, 2022 |
| HP            | EliteBook 830 G6            | [cea4c76b9d](https://linux-hardware.org/?probe=cea4c76b9d) | Dec 11, 2022 |
| Samsung       | 270E5G/270E5U               | [93075de512](https://linux-hardware.org/?probe=93075de512) | Dec 08, 2022 |
| MSI           | Vector GP76 12UGS           | [d6c55a874f](https://linux-hardware.org/?probe=d6c55a874f) | Dec 08, 2022 |
| Google        | Glimmer                     | [ad4b3f5575](https://linux-hardware.org/?probe=ad4b3f5575) | Dec 08, 2022 |
| Apple         | MacBookPro12,1              | [e15b555b1a](https://linux-hardware.org/?probe=e15b555b1a) | Dec 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Dell          | Latitude 5480               | [0cd7d6e4c0](https://linux-hardware.org/?probe=0cd7d6e4c0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude E7440              | [9a859c9a5d](https://linux-hardware.org/?probe=9a859c9a5d) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| Dell          | Latitude E7440              | [63b84a9439](https://linux-hardware.org/?probe=63b84a9439) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [119ec75a5f](https://linux-hardware.org/?probe=119ec75a5f) | Dec 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [36985fd47e](https://linux-hardware.org/?probe=36985fd47e) | Dec 05, 2022 |
| Apple         | MacBookPro11,1              | [5b0565920f](https://linux-hardware.org/?probe=5b0565920f) | Dec 05, 2022 |
| ASUSTek       | X555LJ                      | [a849daba2b](https://linux-hardware.org/?probe=a849daba2b) | Dec 05, 2022 |
| Dell          | Latitude 3190               | [12975376ba](https://linux-hardware.org/?probe=12975376ba) | Dec 05, 2022 |
| MSI           | GF63 Thin 9RCX              | [1bf4364f61](https://linux-hardware.org/?probe=1bf4364f61) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| Lenovo        | G770 20089                  | [d35d60f972](https://linux-hardware.org/?probe=d35d60f972) | Dec 04, 2022 |
| MSI           | Creator Z17 A12UHST         | [afbbf473b9](https://linux-hardware.org/?probe=afbbf473b9) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| HP            | Pavilion dv7                | [90c7688386](https://linux-hardware.org/?probe=90c7688386) | Dec 04, 2022 |
| Google        | Lars                        | [efe9cef4b9](https://linux-hardware.org/?probe=efe9cef4b9) | Dec 04, 2022 |
| Dell          | XPS 15 9570                 | [ec5047129a](https://linux-hardware.org/?probe=ec5047129a) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Google        | Lars                        | [ad022bfd93](https://linux-hardware.org/?probe=ad022bfd93) | Dec 03, 2022 |
| Dell          | G15 5515                    | [218e5c2825](https://linux-hardware.org/?probe=218e5c2825) | Dec 03, 2022 |
| Dell          | Latitude 5480               | [4eba5810d7](https://linux-hardware.org/?probe=4eba5810d7) | Dec 03, 2022 |
| Dell          | Vostro 5502                 | [86341e8306](https://linux-hardware.org/?probe=86341e8306) | Dec 02, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4d33c2ab30](https://linux-hardware.org/?probe=4d33c2ab30) | Dec 02, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [929550dc41](https://linux-hardware.org/?probe=929550dc41) | Dec 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [615b292682](https://linux-hardware.org/?probe=615b292682) | Dec 01, 2022 |
| HP            | Pavilion dv7                | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [3aa3302b92](https://linux-hardware.org/?probe=3aa3302b92) | Nov 30, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [c3d55f501c](https://linux-hardware.org/?probe=c3d55f501c) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f4de100586](https://linux-hardware.org/?probe=f4de100586) | Nov 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [802af80043](https://linux-hardware.org/?probe=802af80043) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| HP            | ProBook 640 G2              | [56ceffe338](https://linux-hardware.org/?probe=56ceffe338) | Nov 28, 2022 |
| Dell          | Latitude 3190               | [3c4756b965](https://linux-hardware.org/?probe=3c4756b965) | Nov 28, 2022 |
| HUAWEI        | MRC-WX0                     | [98f550465b](https://linux-hardware.org/?probe=98f550465b) | Nov 28, 2022 |
| Valve         | Jupiter                     | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| ASUSTek       | G75VX                       | [87ef485975](https://linux-hardware.org/?probe=87ef485975) | Nov 27, 2022 |
| Acer          | AO722                       | [fb75768c70](https://linux-hardware.org/?probe=fb75768c70) | Nov 26, 2022 |
| HP            | ProBook 6470b               | [c8da54315e](https://linux-hardware.org/?probe=c8da54315e) | Nov 26, 2022 |
| Dell          | Latitude E6220              | [aa8d2d2fc7](https://linux-hardware.org/?probe=aa8d2d2fc7) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [848b6ab7b3](https://linux-hardware.org/?probe=848b6ab7b3) | Nov 26, 2022 |
| Lenovo        | B51-80 80LM                 | [c34893c661](https://linux-hardware.org/?probe=c34893c661) | Nov 26, 2022 |
| Valve         | Jupiter                     | [7412d8b03b](https://linux-hardware.org/?probe=7412d8b03b) | Nov 26, 2022 |
| Valve         | Jupiter                     | [24d078fe91](https://linux-hardware.org/?probe=24d078fe91) | Nov 26, 2022 |
| Dell          | Latitude E6420              | [c3e8903f19](https://linux-hardware.org/?probe=c3e8903f19) | Nov 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [4261949a3e](https://linux-hardware.org/?probe=4261949a3e) | Nov 25, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [8acafcf4ab](https://linux-hardware.org/?probe=8acafcf4ab) | Nov 25, 2022 |
| Dell          | Inspiron 14 Plus 7420       | [a35ca4bbbe](https://linux-hardware.org/?probe=a35ca4bbbe) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| HP            | EliteBook 8560p             | [e7bf51183d](https://linux-hardware.org/?probe=e7bf51183d) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| HP            | 250 G6 Notebook PC          | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| ASUSTek       | K51AC                       | [0b2413e13c](https://linux-hardware.org/?probe=0b2413e13c) | Nov 24, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [e7717a62cb](https://linux-hardware.org/?probe=e7717a62cb) | Nov 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [ac72570183](https://linux-hardware.org/?probe=ac72570183) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | [d639be7513](https://linux-hardware.org/?probe=d639be7513) | Nov 23, 2022 |
| Kruger&Mat... | KM1406                      | [a7e0207e4b](https://linux-hardware.org/?probe=a7e0207e4b) | Nov 23, 2022 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [57dfd88985](https://linux-hardware.org/?probe=57dfd88985) | Nov 23, 2022 |
| HP            | Pavilion dv6                | [e3921e4da9](https://linux-hardware.org/?probe=e3921e4da9) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [51ca9fa048](https://linux-hardware.org/?probe=51ca9fa048) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [0ca1ce1d74](https://linux-hardware.org/?probe=0ca1ce1d74) | Nov 23, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [6d217fbd52](https://linux-hardware.org/?probe=6d217fbd52) | Nov 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [ad63d86cb9](https://linux-hardware.org/?probe=ad63d86cb9) | Nov 23, 2022 |
| HP            | G5000 (GF783EA#AKD)         | [2437328d23](https://linux-hardware.org/?probe=2437328d23) | Nov 22, 2022 |
| Dell          | Latitude 3420               | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [c345afe01a](https://linux-hardware.org/?probe=c345afe01a) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | [e36ab20d8c](https://linux-hardware.org/?probe=e36ab20d8c) | Nov 22, 2022 |
| MSI           | Creator Z17 A12UHST         | [014cf9f78d](https://linux-hardware.org/?probe=014cf9f78d) | Nov 22, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [a5dcbbbacd](https://linux-hardware.org/?probe=a5dcbbbacd) | Nov 22, 2022 |
| HP            | EliteBook Folio 1040 G1     | [26ac531682](https://linux-hardware.org/?probe=26ac531682) | Nov 22, 2022 |
| Dell          | Latitude 5410               | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Dell          | Latitude 5490               | [295073cd07](https://linux-hardware.org/?probe=295073cd07) | Nov 21, 2022 |
| Dell          | Latitude 5310               | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [0a98e4cae4](https://linux-hardware.org/?probe=0a98e4cae4) | Nov 21, 2022 |
| Dell          | Latitude 3190               | [1cfe937b0e](https://linux-hardware.org/?probe=1cfe937b0e) | Nov 21, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [740b4f9f03](https://linux-hardware.org/?probe=740b4f9f03) | Nov 20, 2022 |
| HP            | Compaq Presario CQ60        | [3f18cccea5](https://linux-hardware.org/?probe=3f18cccea5) | Nov 20, 2022 |
| HUAWEI        | HVY-WXX9                    | [2030d33f00](https://linux-hardware.org/?probe=2030d33f00) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d8f53f887a](https://linux-hardware.org/?probe=d8f53f887a) | Nov 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c967893dd4](https://linux-hardware.org/?probe=c967893dd4) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1af7bd26fd](https://linux-hardware.org/?probe=1af7bd26fd) | Nov 19, 2022 |
| Lenovo        | S145-15API 81UT             | [fd832d05e2](https://linux-hardware.org/?probe=fd832d05e2) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ad7abfb8cb](https://linux-hardware.org/?probe=ad7abfb8cb) | Nov 19, 2022 |
| Acer          | Aspire V3-772G              | [bc46ec232a](https://linux-hardware.org/?probe=bc46ec232a) | Nov 18, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [4d8be4bb54](https://linux-hardware.org/?probe=4d8be4bb54) | Nov 18, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [dd25be7aef](https://linux-hardware.org/?probe=dd25be7aef) | Nov 17, 2022 |
| Dell          | Inspiron 13-5368            | [203df386a1](https://linux-hardware.org/?probe=203df386a1) | Nov 17, 2022 |
| Dell          | Inspiron 3451               | [105a376344](https://linux-hardware.org/?probe=105a376344) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [5fd36e3d66](https://linux-hardware.org/?probe=5fd36e3d66) | Nov 17, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [62b2a72fa9](https://linux-hardware.org/?probe=62b2a72fa9) | Nov 16, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | [fe520ea826](https://linux-hardware.org/?probe=fe520ea826) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [b5eb364ac6](https://linux-hardware.org/?probe=b5eb364ac6) | Nov 16, 2022 |
| Valve         | Jupiter                     | [4ab915f825](https://linux-hardware.org/?probe=4ab915f825) | Nov 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d07cacacde](https://linux-hardware.org/?probe=d07cacacde) | Nov 15, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| Toshiba       | Satellite P300              | [02285947b8](https://linux-hardware.org/?probe=02285947b8) | Nov 13, 2022 |
| Dell          | Inspiron 3583               | [6fcf5c9bd6](https://linux-hardware.org/?probe=6fcf5c9bd6) | Nov 13, 2022 |
| Acer          | Aspire E1-531G              | [9f3c8742f7](https://linux-hardware.org/?probe=9f3c8742f7) | Nov 13, 2022 |
| Lenovo        | G580 20150                  | [7a628290f2](https://linux-hardware.org/?probe=7a628290f2) | Nov 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1067cba3cc](https://linux-hardware.org/?probe=1067cba3cc) | Nov 12, 2022 |
| Dell          | Latitude E6540              | [e28c12e783](https://linux-hardware.org/?probe=e28c12e783) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [59aa7d31d8](https://linux-hardware.org/?probe=59aa7d31d8) | Nov 11, 2022 |
| Apple         | MacBookPro14,1              | [2981b232db](https://linux-hardware.org/?probe=2981b232db) | Nov 11, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [3ebec87cd1](https://linux-hardware.org/?probe=3ebec87cd1) | Nov 11, 2022 |
| Lenovo        | G580 20150                  | [11344e1661](https://linux-hardware.org/?probe=11344e1661) | Nov 11, 2022 |
| Dell          | Latitude 7480               | [cd19ef7ab8](https://linux-hardware.org/?probe=cd19ef7ab8) | Nov 10, 2022 |
| Dell          | Latitude 7480               | [100bc3303a](https://linux-hardware.org/?probe=100bc3303a) | Nov 10, 2022 |
| MSI           | Stealth GS77 12UGS          | [bf125e16a2](https://linux-hardware.org/?probe=bf125e16a2) | Nov 10, 2022 |
| Dell          | Latitude E6330              | [04113ad3de](https://linux-hardware.org/?probe=04113ad3de) | Nov 10, 2022 |
| Dell          | Inspiron N7010              | [8d43f2e3fc](https://linux-hardware.org/?probe=8d43f2e3fc) | Nov 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| MSI           | Creator Z17 A12UHST         | [a3b1e0d746](https://linux-hardware.org/?probe=a3b1e0d746) | Nov 09, 2022 |
| Dell          | XPS 15 9550                 | [6642f568d4](https://linux-hardware.org/?probe=6642f568d4) | Nov 09, 2022 |
| MSI           | Stealth GS77 12UGS          | [ae6b308816](https://linux-hardware.org/?probe=ae6b308816) | Nov 08, 2022 |
| Dell          | G5 5587                     | [972a2dcaa0](https://linux-hardware.org/?probe=972a2dcaa0) | Nov 08, 2022 |
| Lenovo        | ThinkPad P53 20QQS2CY00     | [98e9599ea3](https://linux-hardware.org/?probe=98e9599ea3) | Nov 08, 2022 |
| Dell          | Latitude E7470              | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [d19fce3e6c](https://linux-hardware.org/?probe=d19fce3e6c) | Nov 08, 2022 |
| MSI           | Creator Z17 A12UHST         | [891dbf2492](https://linux-hardware.org/?probe=891dbf2492) | Nov 07, 2022 |
| Acer          | Aspire E5-573G              | [fafbf5ba02](https://linux-hardware.org/?probe=fafbf5ba02) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| HP            | ProBook 6570b               | [1fec197471](https://linux-hardware.org/?probe=1fec197471) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3ec96d66bb](https://linux-hardware.org/?probe=3ec96d66bb) | Nov 05, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | [010fd86c32](https://linux-hardware.org/?probe=010fd86c32) | Nov 04, 2022 |
| Acer          | Aspire A715-74G             | [fa89b7a988](https://linux-hardware.org/?probe=fa89b7a988) | Nov 04, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [24e798d2a5](https://linux-hardware.org/?probe=24e798d2a5) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [455bdc6c45](https://linux-hardware.org/?probe=455bdc6c45) | Nov 03, 2022 |
| HP            | EliteBook 745 G2            | [c6505744ca](https://linux-hardware.org/?probe=c6505744ca) | Nov 03, 2022 |
| Dell          | Latitude E6540              | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Dell          | Latitude E6430              | [2b6012cc1d](https://linux-hardware.org/?probe=2b6012cc1d) | Nov 02, 2022 |
| Dell          | G15 5515                    | [92f1423303](https://linux-hardware.org/?probe=92f1423303) | Nov 02, 2022 |
| Dell          | G15 5515                    | [dae7c630d5](https://linux-hardware.org/?probe=dae7c630d5) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [310895b721](https://linux-hardware.org/?probe=310895b721) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| HP            | Unknown                     | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| HP            | EliteBook 745 G2            | [0786ded6c8](https://linux-hardware.org/?probe=0786ded6c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Latitude 3190               | [fe0d1261a6](https://linux-hardware.org/?probe=fe0d1261a6) | Oct 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [24d91cf27b](https://linux-hardware.org/?probe=24d91cf27b) | Oct 30, 2022 |
| HP            | ProBook 6540b               | [be9c128b00](https://linux-hardware.org/?probe=be9c128b00) | Oct 30, 2022 |
| Kiano         | SlimNote 1.0                | [db1ae618d8](https://linux-hardware.org/?probe=db1ae618d8) | Oct 29, 2022 |
| Dell          | Latitude 5501               | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| Lenovo        | ThinkPad T450s 20BWS0DD0... | [973a3662b9](https://linux-hardware.org/?probe=973a3662b9) | Oct 29, 2022 |
| Kruger&Mat... | KM1406                      | [70b8441ccf](https://linux-hardware.org/?probe=70b8441ccf) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| HP            | 250 G8 Notebook PC          | [59c02d4967](https://linux-hardware.org/?probe=59c02d4967) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [a7ff9a34d2](https://linux-hardware.org/?probe=a7ff9a34d2) | Oct 28, 2022 |
| Dell          | Latitude 5531               | [73ddced77b](https://linux-hardware.org/?probe=73ddced77b) | Oct 28, 2022 |
| HP            | EliteBook 840 G6            | [89cc00ef58](https://linux-hardware.org/?probe=89cc00ef58) | Oct 28, 2022 |
| Fujitsu       | LIFEBOOK U728               | [c5867e7dd3](https://linux-hardware.org/?probe=c5867e7dd3) | Oct 28, 2022 |
| Dell          | XPS 15 9510                 | [d3879c6bb0](https://linux-hardware.org/?probe=d3879c6bb0) | Oct 28, 2022 |
| Lenovo        | ThinkPad T430 23498M7       | [f936993d28](https://linux-hardware.org/?probe=f936993d28) | Oct 28, 2022 |
| Gateway       | P-7805u                     | [7597071801](https://linux-hardware.org/?probe=7597071801) | Oct 28, 2022 |
| Dell          | Latitude E6530              | [71b2df6eff](https://linux-hardware.org/?probe=71b2df6eff) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | [4261d8dd66](https://linux-hardware.org/?probe=4261d8dd66) | Oct 27, 2022 |
| Acer          | Aspire A114-32              | [216730dba7](https://linux-hardware.org/?probe=216730dba7) | Oct 27, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [00e77b8815](https://linux-hardware.org/?probe=00e77b8815) | Oct 26, 2022 |
| Dell          | Latitude E6530              | [c271a351aa](https://linux-hardware.org/?probe=c271a351aa) | Oct 26, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [94d1c333ac](https://linux-hardware.org/?probe=94d1c333ac) | Oct 26, 2022 |
| HUAWEI        | HKD-WXX                     | [2ff7652d3a](https://linux-hardware.org/?probe=2ff7652d3a) | Oct 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [082e572642](https://linux-hardware.org/?probe=082e572642) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | [6ba1aaf015](https://linux-hardware.org/?probe=6ba1aaf015) | Oct 26, 2022 |
| Lenovo        | ThinkPad T490s 20NX002QU... | [062d1d3b82](https://linux-hardware.org/?probe=062d1d3b82) | Oct 26, 2022 |
| Lenovo        | ThinkPad R500 2716W2K       | [c9a59d0ee9](https://linux-hardware.org/?probe=c9a59d0ee9) | Oct 26, 2022 |
| MSI           | Creator Z17 A12UHST         | [18df556ca1](https://linux-hardware.org/?probe=18df556ca1) | Oct 25, 2022 |
| ASUSTek       | X540SA                      | [a515dd93cd](https://linux-hardware.org/?probe=a515dd93cd) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [c1a4fde481](https://linux-hardware.org/?probe=c1a4fde481) | Oct 24, 2022 |
| Lenovo        | ThinkPad T490 20N3S9DJ00    | [80bf151a4d](https://linux-hardware.org/?probe=80bf151a4d) | Oct 24, 2022 |
| Dell          | Latitude 3190               | [b116ac92f3](https://linux-hardware.org/?probe=b116ac92f3) | Oct 24, 2022 |
| HP            | ZBook 17 G6                 | [d28d720a26](https://linux-hardware.org/?probe=d28d720a26) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [f282e79ccb](https://linux-hardware.org/?probe=f282e79ccb) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [ec27a5efb5](https://linux-hardware.org/?probe=ec27a5efb5) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [1f26696990](https://linux-hardware.org/?probe=1f26696990) | Oct 22, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [88a93e44f9](https://linux-hardware.org/?probe=88a93e44f9) | Oct 22, 2022 |
| ASUSTek       | X550LN                      | [7a6daf6023](https://linux-hardware.org/?probe=7a6daf6023) | Oct 22, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [f5af95bb9a](https://linux-hardware.org/?probe=f5af95bb9a) | Oct 21, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [5def3f5324](https://linux-hardware.org/?probe=5def3f5324) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7cd6e349f0](https://linux-hardware.org/?probe=7cd6e349f0) | Oct 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [344040aee1](https://linux-hardware.org/?probe=344040aee1) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| MSI           | Creator Z17 A12UHST         | [5d65b94f2b](https://linux-hardware.org/?probe=5d65b94f2b) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8bc82af4e5](https://linux-hardware.org/?probe=8bc82af4e5) | Oct 18, 2022 |
| Lenovo        | G580 20150                  | [7639ea3b73](https://linux-hardware.org/?probe=7639ea3b73) | Oct 18, 2022 |
| Dell          | Latitude 5421               | [77cbc2b788](https://linux-hardware.org/?probe=77cbc2b788) | Oct 18, 2022 |
| Dell          | Vostro 7580                 | [69cc3a8c62](https://linux-hardware.org/?probe=69cc3a8c62) | Oct 18, 2022 |
| HP            | ZBook 17 G6                 | [2f27f08ce8](https://linux-hardware.org/?probe=2f27f08ce8) | Oct 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b8dbd1daf9](https://linux-hardware.org/?probe=b8dbd1daf9) | Oct 17, 2022 |
| Dell          | Inspiron 3541               | [858e5b974b](https://linux-hardware.org/?probe=858e5b974b) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| Dell          | Latitude E6430              | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| Acer          | Aspire SW5-012              | [530046bf8a](https://linux-hardware.org/?probe=530046bf8a) | Oct 15, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [bf6d77aefd](https://linux-hardware.org/?probe=bf6d77aefd) | Oct 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | ENVY 15                     | [09bfbadebe](https://linux-hardware.org/?probe=09bfbadebe) | Oct 14, 2022 |
| MSI           | MS-N014                     | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Lenovo        | G500s 20245                 | [61539bde5e](https://linux-hardware.org/?probe=61539bde5e) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [973f501233](https://linux-hardware.org/?probe=973f501233) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Lenovo        | G580 20150                  | [8e564b93cb](https://linux-hardware.org/?probe=8e564b93cb) | Oct 13, 2022 |
| Acer          | Aspire A315-21              | [a122b26729](https://linux-hardware.org/?probe=a122b26729) | Oct 12, 2022 |
| Dell          | XPS 13 9310                 | [8437ac2ffc](https://linux-hardware.org/?probe=8437ac2ffc) | Oct 12, 2022 |
| Lenovo        | ThinkPad T530 24297TG       | [d6dec1ab6d](https://linux-hardware.org/?probe=d6dec1ab6d) | Oct 12, 2022 |
| ASUSTek       | X705UDR                     | [5c8601bb4f](https://linux-hardware.org/?probe=5c8601bb4f) | Oct 11, 2022 |
| ASUSTek       | G750JW                      | [251f32c620](https://linux-hardware.org/?probe=251f32c620) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | [2aea48a0f2](https://linux-hardware.org/?probe=2aea48a0f2) | Oct 11, 2022 |
| Lenovo        | ThinkPad X200s 7470A98      | [10d90de300](https://linux-hardware.org/?probe=10d90de300) | Oct 11, 2022 |
| Lenovo        | ThinkPad P50 20EQS5MP00     | [83858a99c3](https://linux-hardware.org/?probe=83858a99c3) | Oct 10, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [4c575be5d7](https://linux-hardware.org/?probe=4c575be5d7) | Oct 10, 2022 |
| Acer          | Enduro EUN314-51W           | [14741407aa](https://linux-hardware.org/?probe=14741407aa) | Oct 10, 2022 |
| Dell          | Latitude 3190               | [bee132f486](https://linux-hardware.org/?probe=bee132f486) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| Dell          | Precision 7530              | [7f71730e68](https://linux-hardware.org/?probe=7f71730e68) | Oct 07, 2022 |
| Dell          | Inspiron 3451               | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ae8f71dbd3](https://linux-hardware.org/?probe=ae8f71dbd3) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Lenovo        | ThinkPad T480 20L50007PB    | [4c7a6898bf](https://linux-hardware.org/?probe=4c7a6898bf) | Oct 06, 2022 |
| Dell          | Vostro 15-3568              | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| Dell          | Precision 3541              | [bfef2cb8a3](https://linux-hardware.org/?probe=bfef2cb8a3) | Oct 05, 2022 |
| ASUSTek       | X550CC                      | [147483a370](https://linux-hardware.org/?probe=147483a370) | Oct 05, 2022 |
| Valve         | Jupiter                     | [ac2707d2e6](https://linux-hardware.org/?probe=ac2707d2e6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW002CP... | [b7cd76d0b6](https://linux-hardware.org/?probe=b7cd76d0b6) | Oct 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d389c9fa00](https://linux-hardware.org/?probe=d389c9fa00) | Oct 05, 2022 |
| Lenovo        | Z51-70 80K6                 | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6c821c0c08](https://linux-hardware.org/?probe=6c821c0c08) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [a9c2a1eca0](https://linux-hardware.org/?probe=a9c2a1eca0) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| Dynabook      | PORTEGE X40-G               | [fc68a9cdbf](https://linux-hardware.org/?probe=fc68a9cdbf) | Oct 03, 2022 |
| Dell          | Latitude 3190               | [29b38a4a94](https://linux-hardware.org/?probe=29b38a4a94) | Oct 03, 2022 |
| Acer          | Aspire 5755G                | [c552cb5631](https://linux-hardware.org/?probe=c552cb5631) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| Acer          | Aspire 4733Z                | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [34006e3b46](https://linux-hardware.org/?probe=34006e3b46) | Oct 01, 2022 |
| Dell          | Inspiron 3451               | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| Acer          | Aspire A715-74G             | [17abc08754](https://linux-hardware.org/?probe=17abc08754) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| Lenovo        | G500s 20245                 | [b9001f7817](https://linux-hardware.org/?probe=b9001f7817) | Sep 29, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [be74c01cca](https://linux-hardware.org/?probe=be74c01cca) | Sep 29, 2022 |
| Dell          | Latitude E6330              | [b075fbcb56](https://linux-hardware.org/?probe=b075fbcb56) | Sep 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [82528435d8](https://linux-hardware.org/?probe=82528435d8) | Sep 29, 2022 |
| MSI           | Creator Z17 A12UHST         | [4b9249b9b0](https://linux-hardware.org/?probe=4b9249b9b0) | Sep 29, 2022 |
| Dell          | Inspiron 5558               | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Valve         | Jupiter                     | [bdc84f1b9b](https://linux-hardware.org/?probe=bdc84f1b9b) | Sep 28, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| Dell          | Precision 3561              | [77a4030052](https://linux-hardware.org/?probe=77a4030052) | Sep 27, 2022 |
| Toshiba       | Satellite C850-1LK          | [f0240dcb2d](https://linux-hardware.org/?probe=f0240dcb2d) | Sep 27, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [70860ec433](https://linux-hardware.org/?probe=70860ec433) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [cb5f6f279b](https://linux-hardware.org/?probe=cb5f6f279b) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [3f11c520e0](https://linux-hardware.org/?probe=3f11c520e0) | Sep 26, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Dell          | Latitude 3190               | [27ac75e10c](https://linux-hardware.org/?probe=27ac75e10c) | Sep 26, 2022 |
| Valve         | Jupiter                     | [ebf3e70cf7](https://linux-hardware.org/?probe=ebf3e70cf7) | Sep 25, 2022 |
| Acer          | P5WE0                       | [124f7bdd77](https://linux-hardware.org/?probe=124f7bdd77) | Sep 25, 2022 |
| HP            | Laptop 17-cp0xxx            | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [89a1a3179d](https://linux-hardware.org/?probe=89a1a3179d) | Sep 24, 2022 |
| Toshiba       | Satellite P205              | [2a1450578e](https://linux-hardware.org/?probe=2a1450578e) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK S760               | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Toshiba       | Satellite P205              | [98e97d946a](https://linux-hardware.org/?probe=98e97d946a) | Sep 23, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [36c369745a](https://linux-hardware.org/?probe=36c369745a) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [de7c138e21](https://linux-hardware.org/?probe=de7c138e21) | Sep 22, 2022 |
| Lenovo        | G505s 20255                 | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [967110ef60](https://linux-hardware.org/?probe=967110ef60) | Sep 21, 2022 |
| HP            | EliteBook 840 G2            | [030ce84327](https://linux-hardware.org/?probe=030ce84327) | Sep 20, 2022 |
| Framework     | Laptop                      | [dd163cfa96](https://linux-hardware.org/?probe=dd163cfa96) | Sep 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21c74278f8](https://linux-hardware.org/?probe=21c74278f8) | Sep 20, 2022 |
| Dell          | Latitude E4310              | [c77a454d4e](https://linux-hardware.org/?probe=c77a454d4e) | Sep 20, 2022 |
| Dell          | Latitude E4310              | [4e8bf046d8](https://linux-hardware.org/?probe=4e8bf046d8) | Sep 19, 2022 |
| Apple         | MacBook9,1                  | [e6898c8aa0](https://linux-hardware.org/?probe=e6898c8aa0) | Sep 19, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [85952e171d](https://linux-hardware.org/?probe=85952e171d) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [eb67db5bff](https://linux-hardware.org/?probe=eb67db5bff) | Sep 19, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | [e6a930e933](https://linux-hardware.org/?probe=e6a930e933) | Sep 19, 2022 |
| HP            | ProBook 470 G5              | [793fa18b58](https://linux-hardware.org/?probe=793fa18b58) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| Toshiba       | PORTEGE Z30-A               | [419bf72e22](https://linux-hardware.org/?probe=419bf72e22) | Sep 19, 2022 |
| Dell          | Latitude 3190               | [f96d782326](https://linux-hardware.org/?probe=f96d782326) | Sep 19, 2022 |
| Valve         | Jupiter                     | [52352bab7a](https://linux-hardware.org/?probe=52352bab7a) | Sep 19, 2022 |
| HP            | Notebook                    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [9c23c7bb58](https://linux-hardware.org/?probe=9c23c7bb58) | Sep 17, 2022 |
| Lenovo        | G50-80 80E5                 | [5023f912e2](https://linux-hardware.org/?probe=5023f912e2) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Dell          | Latitude 5511               | [9a2faa8d22](https://linux-hardware.org/?probe=9a2faa8d22) | Sep 16, 2022 |
| HP            | ProBook 470 G5              | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [099e5d3523](https://linux-hardware.org/?probe=099e5d3523) | Sep 16, 2022 |
| Dell          | Inspiron 3451               | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| Dell          | Inspiron 5584               | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Dell          | Latitude 5521               | [c342e3ab13](https://linux-hardware.org/?probe=c342e3ab13) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| Dell          | Inspiron 3451               | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [efc31007ac](https://linux-hardware.org/?probe=efc31007ac) | Sep 12, 2022 |
| Dell          | Latitude 3190               | [3c0abb17a9](https://linux-hardware.org/?probe=3c0abb17a9) | Sep 12, 2022 |
| HUAWEI        | KPL-W0X                     | [eff4400b7d](https://linux-hardware.org/?probe=eff4400b7d) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| Acer          | Nitro AN517-55              | [16fa00177a](https://linux-hardware.org/?probe=16fa00177a) | Sep 10, 2022 |
| Toshiba       | Satellite L40               | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| Gigabyte      | AORUS 15G XC                | [ea131dfe2c](https://linux-hardware.org/?probe=ea131dfe2c) | Sep 08, 2022 |
| Dell          | Latitude E6540              | [5700f37281](https://linux-hardware.org/?probe=5700f37281) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6812b52b92](https://linux-hardware.org/?probe=6812b52b92) | Sep 08, 2022 |
| Dell          | Inspiron 3541               | [2cc868e8f0](https://linux-hardware.org/?probe=2cc868e8f0) | Sep 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [6ee5358914](https://linux-hardware.org/?probe=6ee5358914) | Sep 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [63524aa492](https://linux-hardware.org/?probe=63524aa492) | Sep 07, 2022 |
| HP            | EliteBook 8440p             | [5cf26fac4d](https://linux-hardware.org/?probe=5cf26fac4d) | Sep 07, 2022 |
| Samsung       | RC420/RC520/RC720           | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4615004e85](https://linux-hardware.org/?probe=4615004e85) | Sep 06, 2022 |
| Lenovo        | G580 20150                  | [e0bb6ae251](https://linux-hardware.org/?probe=e0bb6ae251) | Sep 05, 2022 |
| Dell          | Latitude 3190               | [25c70ea2f3](https://linux-hardware.org/?probe=25c70ea2f3) | Sep 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d802875fec](https://linux-hardware.org/?probe=d802875fec) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| Dell          | Latitude E6330              | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| HP            | 620                         | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6669ffa68e](https://linux-hardware.org/?probe=6669ffa68e) | Sep 02, 2022 |
| Dell          | Latitude E6220              | [e249853663](https://linux-hardware.org/?probe=e249853663) | Sep 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8320ded55c](https://linux-hardware.org/?probe=8320ded55c) | Sep 02, 2022 |
| Valve         | Jupiter                     | [ad3ce497e7](https://linux-hardware.org/?probe=ad3ce497e7) | Sep 02, 2022 |
| Dell          | Latitude E6220              | [99c8b865ad](https://linux-hardware.org/?probe=99c8b865ad) | Sep 02, 2022 |
| Dell          | Latitude E6330              | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [12abd434b5](https://linux-hardware.org/?probe=12abd434b5) | Sep 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [e16313490d](https://linux-hardware.org/?probe=e16313490d) | Sep 01, 2022 |
| Valve         | Jupiter                     | [60db4bfa03](https://linux-hardware.org/?probe=60db4bfa03) | Aug 31, 2022 |
| Dell          | Latitude E6330              | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| Dell          | Latitude 3190               | [0998f7a5d1](https://linux-hardware.org/?probe=0998f7a5d1) | Aug 29, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| ASUSTek       | F3E                         | [1314dc63b6](https://linux-hardware.org/?probe=1314dc63b6) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [7ed4b144d7](https://linux-hardware.org/?probe=7ed4b144d7) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| Dell          | Latitude E6400              | [666ba32534](https://linux-hardware.org/?probe=666ba32534) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| Lenovo        | G580 20150                  | [1813b94682](https://linux-hardware.org/?probe=1813b94682) | Aug 27, 2022 |
| HP            | 15                          | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| ASUSTek       | X705UAP                     | [eacfc15b6c](https://linux-hardware.org/?probe=eacfc15b6c) | Aug 24, 2022 |
| Dell          | Inspiron 5402               | [936ea503c8](https://linux-hardware.org/?probe=936ea503c8) | Aug 24, 2022 |
| Acer          | Aspire E5-571               | [659e36b0ed](https://linux-hardware.org/?probe=659e36b0ed) | Aug 23, 2022 |
| Dell          | Latitude 5521               | [b14afc8c75](https://linux-hardware.org/?probe=b14afc8c75) | Aug 22, 2022 |
| Dell          | XPS 15 9560                 | [29d52f610c](https://linux-hardware.org/?probe=29d52f610c) | Aug 22, 2022 |
| Dell          | Latitude 3190               | [74fd1046be](https://linux-hardware.org/?probe=74fd1046be) | Aug 22, 2022 |
| Lenovo        | ThinkPad T400 6474B84       | [f8a6513790](https://linux-hardware.org/?probe=f8a6513790) | Aug 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Valve         | Jupiter                     | [eb63fecd35](https://linux-hardware.org/?probe=eb63fecd35) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | [f21f1687d5](https://linux-hardware.org/?probe=f21f1687d5) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | [04b38f1dfd](https://linux-hardware.org/?probe=04b38f1dfd) | Aug 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | [ac7fb69037](https://linux-hardware.org/?probe=ac7fb69037) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [fdcb40d147](https://linux-hardware.org/?probe=fdcb40d147) | Aug 18, 2022 |
| HP            | ZBook 17 G6                 | [cf5500d7b1](https://linux-hardware.org/?probe=cf5500d7b1) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| NEC Comput... | PC-LJ730MG6W                | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| MSI           | GT72S 6QE                   | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Dell          | Latitude 3190               | [5564506d3c](https://linux-hardware.org/?probe=5564506d3c) | Aug 15, 2022 |
| Dell          | Latitude E5430 vPro         | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| HP            | EliteBook 2760p             | [bb4c1e4c3a](https://linux-hardware.org/?probe=bb4c1e4c3a) | Aug 13, 2022 |
| Acer          | Aspire A515-51G             | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| ASUSTek       | UX303LAB                    | [169419cea0](https://linux-hardware.org/?probe=169419cea0) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| HP            | EliteBook 2760p             | [0ce6a49a7f](https://linux-hardware.org/?probe=0ce6a49a7f) | Aug 12, 2022 |
| Lenovo        | Z710 20250                  | [8c7b1d0773](https://linux-hardware.org/?probe=8c7b1d0773) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [6a07e79eb7](https://linux-hardware.org/?probe=6a07e79eb7) | Aug 11, 2022 |
| Lenovo        | G580 20150                  | [7e83b07cca](https://linux-hardware.org/?probe=7e83b07cca) | Aug 11, 2022 |
| HP            | 255 G4                      | [3ed3978b93](https://linux-hardware.org/?probe=3ed3978b93) | Aug 11, 2022 |
| Alienware     | M17xR4                      | [a9d3769b5b](https://linux-hardware.org/?probe=a9d3769b5b) | Aug 10, 2022 |
| Dell          | Latitude 5521               | [25f117c439](https://linux-hardware.org/?probe=25f117c439) | Aug 10, 2022 |
| HP            | Pavilion HDX9200            | [079cb2197b](https://linux-hardware.org/?probe=079cb2197b) | Aug 10, 2022 |
| HP            | 255 G4                      | [44b5858d14](https://linux-hardware.org/?probe=44b5858d14) | Aug 10, 2022 |
| HP            | Compaq Presario CQ60        | [20f30b16e5](https://linux-hardware.org/?probe=20f30b16e5) | Aug 09, 2022 |
| Toshiba       | Satellite A300              | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMC    | [47d4f751e1](https://linux-hardware.org/?probe=47d4f751e1) | Aug 09, 2022 |
| Dell          | Latitude 3190               | [5818ff09cb](https://linux-hardware.org/?probe=5818ff09cb) | Aug 08, 2022 |
| Dell          | Vostro 3500                 | [71390cb3ec](https://linux-hardware.org/?probe=71390cb3ec) | Aug 07, 2022 |
| PC Special... | Recoil II                   | [1e05c3546f](https://linux-hardware.org/?probe=1e05c3546f) | Aug 07, 2022 |
| ASUSTek       | K52JT                       | [013f296b81](https://linux-hardware.org/?probe=013f296b81) | Aug 07, 2022 |
| MSI           | Creator Z17 A12UHST         | [ccbb6bb183](https://linux-hardware.org/?probe=ccbb6bb183) | Aug 05, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [0a34d32db6](https://linux-hardware.org/?probe=0a34d32db6) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440s 20AR003SM... | [e835f1eca5](https://linux-hardware.org/?probe=e835f1eca5) | Aug 04, 2022 |
| Acer          | Aspire E5-571               | [a249c68580](https://linux-hardware.org/?probe=a249c68580) | Aug 04, 2022 |
| Fujitsu Si... | AMILO Li1705                | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| Dell          | Inspiron 3583               | [7f2e8ddf72](https://linux-hardware.org/?probe=7f2e8ddf72) | Aug 04, 2022 |
| ASUSTek       | G550JK                      | [e73f25c149](https://linux-hardware.org/?probe=e73f25c149) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| Lenovo        | Yoga 900-13ISK 80MK         | [1d0650ff70](https://linux-hardware.org/?probe=1d0650ff70) | Aug 03, 2022 |
| MSI           | Creator Z17 A12UHST         | [87533b4847](https://linux-hardware.org/?probe=87533b4847) | Aug 03, 2022 |
| ASUSTek       | G550JK                      | [76414b53ee](https://linux-hardware.org/?probe=76414b53ee) | Aug 03, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| Dell          | Latitude 3190               | [1f86e5fa57](https://linux-hardware.org/?probe=1f86e5fa57) | Aug 01, 2022 |
| Acer          | Aspire 5730                 | [1541bd94e2](https://linux-hardware.org/?probe=1541bd94e2) | Jul 31, 2022 |
| Acer          | Aspire V5-591G              | [80396b28bf](https://linux-hardware.org/?probe=80396b28bf) | Jul 31, 2022 |
| HP            | 550                         | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Dell          | XPS M1330                   | [2abad8da86](https://linux-hardware.org/?probe=2abad8da86) | Jul 30, 2022 |
| Acer          | Aspire 5730                 | [8ac8b8a87a](https://linux-hardware.org/?probe=8ac8b8a87a) | Jul 30, 2022 |
| Dell          | Precision 5550              | [e11d4be493](https://linux-hardware.org/?probe=e11d4be493) | Jul 30, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| Dell          | Latitude E7470              | [9f4d55071c](https://linux-hardware.org/?probe=9f4d55071c) | Jul 28, 2022 |
| Dell          | Latitude 5421               | [ec91a9ea85](https://linux-hardware.org/?probe=ec91a9ea85) | Jul 27, 2022 |
| Lenovo        | G50-70 20351                | [4ddfbb6ad8](https://linux-hardware.org/?probe=4ddfbb6ad8) | Jul 26, 2022 |
| Toshiba       | Satellite L750D             | [c8e9ea3fdd](https://linux-hardware.org/?probe=c8e9ea3fdd) | Jul 26, 2022 |
| HP            | Laptop 15s-eq0xxx           | [aabcc30a17](https://linux-hardware.org/?probe=aabcc30a17) | Jul 25, 2022 |
| Dell          | Latitude 3190               | [2ec6ff1812](https://linux-hardware.org/?probe=2ec6ff1812) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [123fc55893](https://linux-hardware.org/?probe=123fc55893) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | [597fb27e56](https://linux-hardware.org/?probe=597fb27e56) | Jul 23, 2022 |
| Lenovo        | G50-30 80G0                 | [8b1930ddbd](https://linux-hardware.org/?probe=8b1930ddbd) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [4e47525879](https://linux-hardware.org/?probe=4e47525879) | Jul 22, 2022 |
| Packard Be... | EasyNote TE11BZ             | [e1099c5342](https://linux-hardware.org/?probe=e1099c5342) | Jul 22, 2022 |
| Dell          | Inspiron MM061              | [8e0cd55a28](https://linux-hardware.org/?probe=8e0cd55a28) | Jul 22, 2022 |
| ASUSTek       | X550CL                      | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Dell          | Latitude E6540              | [4688c6f312](https://linux-hardware.org/?probe=4688c6f312) | Jul 21, 2022 |
| HP            | EliteBook 840 G5            | [03afe0a303](https://linux-hardware.org/?probe=03afe0a303) | Jul 20, 2022 |
| HP            | 250 G6 Notebook PC          | [83d1355e61](https://linux-hardware.org/?probe=83d1355e61) | Jul 19, 2022 |
| Dell          | Latitude 3190               | [4fa9fe26c1](https://linux-hardware.org/?probe=4fa9fe26c1) | Jul 18, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| MSI           | Creator Z17 A12UHST         | [ef0c958c66](https://linux-hardware.org/?probe=ef0c958c66) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Lenovo        | G580 20150                  | [d6b737940e](https://linux-hardware.org/?probe=d6b737940e) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | [4d653cf4e6](https://linux-hardware.org/?probe=4d653cf4e6) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Hyperbook     | Z15 Zen                     | [41129ecc5e](https://linux-hardware.org/?probe=41129ecc5e) | Jul 14, 2022 |
| Dell          | Inspiron 3451               | [c95dd7e491](https://linux-hardware.org/?probe=c95dd7e491) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| HP            | EliteBook 8570w             | [495c5afa4b](https://linux-hardware.org/?probe=495c5afa4b) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [2566bb66dd](https://linux-hardware.org/?probe=2566bb66dd) | Jul 12, 2022 |
| Dell          | Latitude E6420              | [d3bbc4a899](https://linux-hardware.org/?probe=d3bbc4a899) | Jul 12, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [24dc866c51](https://linux-hardware.org/?probe=24dc866c51) | Jul 11, 2022 |
| Dell          | Latitude 3190               | [b3c7283cdb](https://linux-hardware.org/?probe=b3c7283cdb) | Jul 11, 2022 |
| HP            | ProBook 4740s               | [18ff2d02bd](https://linux-hardware.org/?probe=18ff2d02bd) | Jul 10, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [6ed9abc24e](https://linux-hardware.org/?probe=6ed9abc24e) | Jul 10, 2022 |
| Lenovo        | ThinkPad R61 8932FJG        | [d783a022b3](https://linux-hardware.org/?probe=d783a022b3) | Jul 08, 2022 |
| Dell          | Latitude D420               | [2e3ded5234](https://linux-hardware.org/?probe=2e3ded5234) | Jul 08, 2022 |
| Acer          | Aspire A715-75G             | [4a6cc98dd6](https://linux-hardware.org/?probe=4a6cc98dd6) | Jul 08, 2022 |
| MSI           | GF63 Thin 8RCS              | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [5cf26aa015](https://linux-hardware.org/?probe=5cf26aa015) | Jul 08, 2022 |
| Lenovo        | ThinkPad T410 2537W2L       | [a2e55ad8ac](https://linux-hardware.org/?probe=a2e55ad8ac) | Jul 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [b4732a4bda](https://linux-hardware.org/?probe=b4732a4bda) | Jul 05, 2022 |
| Lenovo        | ThinkPad P53 20QNS00Y00     | [64dc631691](https://linux-hardware.org/?probe=64dc631691) | Jul 05, 2022 |
| HP            | ProBook 6475b               | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Dell          | Latitude 7280               | [5333012df2](https://linux-hardware.org/?probe=5333012df2) | Jul 04, 2022 |
| Dell          | Latitude 3190               | [f5c0f0798a](https://linux-hardware.org/?probe=f5c0f0798a) | Jul 04, 2022 |
| Dell          | Inspiron 5567               | [740ba48457](https://linux-hardware.org/?probe=740ba48457) | Jul 03, 2022 |
| Dell          | Latitude E6420              | [e1b517f8af](https://linux-hardware.org/?probe=e1b517f8af) | Jul 03, 2022 |
| Dell          | Inspiron 3451               | [a57cf9cc46](https://linux-hardware.org/?probe=a57cf9cc46) | Jul 03, 2022 |
| ASUSTek       | X55U                        | [ed55b4ef39](https://linux-hardware.org/?probe=ed55b4ef39) | Jul 03, 2022 |
| Lenovo        | ThinkPad E470 20H1007MPB    | [7a20748cc1](https://linux-hardware.org/?probe=7a20748cc1) | Jul 03, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [8b717c6bdf](https://linux-hardware.org/?probe=8b717c6bdf) | Jul 02, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [10ff366630](https://linux-hardware.org/?probe=10ff366630) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| Lenovo        | ThinkPad T450s 20BX002NM... | [3bb2e1821b](https://linux-hardware.org/?probe=3bb2e1821b) | Jul 01, 2022 |
| Dell          | Latitude 3420               | [651ab17da0](https://linux-hardware.org/?probe=651ab17da0) | Jun 30, 2022 |
| Framework     | Laptop                      | [61a6480a38](https://linux-hardware.org/?probe=61a6480a38) | Jun 30, 2022 |
| Dell          | Inspiron 3451               | [6cf63ca19e](https://linux-hardware.org/?probe=6cf63ca19e) | Jun 30, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [0e09c926c1](https://linux-hardware.org/?probe=0e09c926c1) | Jun 30, 2022 |
| Dell          | Inspiron M5040              | [64c8f1ad3f](https://linux-hardware.org/?probe=64c8f1ad3f) | Jun 29, 2022 |
| Lenovo        | G580 20150                  | [dbe5fe496a](https://linux-hardware.org/?probe=dbe5fe496a) | Jun 29, 2022 |
| Getac         | B300-X                      | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| Lenovo        | ThinkPad T420 4180MY7       | [a57e4e84f8](https://linux-hardware.org/?probe=a57e4e84f8) | Jun 29, 2022 |
| Dell          | Inspiron M5040              | [a9522b8288](https://linux-hardware.org/?probe=a9522b8288) | Jun 28, 2022 |
| Dell          | Latitude D420               | [c531c131ec](https://linux-hardware.org/?probe=c531c131ec) | Jun 28, 2022 |
| Dell          | Latitude 5511               | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| Lenovo        | ThinkPad T470 20HES07J00    | [4be29eb5f1](https://linux-hardware.org/?probe=4be29eb5f1) | Jun 27, 2022 |
| Dell          | Latitude 3190               | [3bf5b47ea1](https://linux-hardware.org/?probe=3bf5b47ea1) | Jun 27, 2022 |
| ASUSTek       | X751LK                      | [d7f4b1678b](https://linux-hardware.org/?probe=d7f4b1678b) | Jun 24, 2022 |
| ASUSTek       | X751LK                      | [09dfab066c](https://linux-hardware.org/?probe=09dfab066c) | Jun 24, 2022 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [0c96d2bc24](https://linux-hardware.org/?probe=0c96d2bc24) | Jun 24, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| Acer          | Aspire E1-570               | [906b1f465e](https://linux-hardware.org/?probe=906b1f465e) | Jun 23, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [212cd0ac63](https://linux-hardware.org/?probe=212cd0ac63) | Jun 22, 2022 |
| Lenovo        | G50-30 80G0                 | [f82628e802](https://linux-hardware.org/?probe=f82628e802) | Jun 21, 2022 |
| Lenovo        | G50-30 80G0                 | [402aec2b04](https://linux-hardware.org/?probe=402aec2b04) | Jun 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [d6c4bb6995](https://linux-hardware.org/?probe=d6c4bb6995) | Jun 21, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [23f396c697](https://linux-hardware.org/?probe=23f396c697) | Jun 21, 2022 |
| HP            | Pavilion Notebook           | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [52aa806063](https://linux-hardware.org/?probe=52aa806063) | Jun 20, 2022 |
| Dell          | Latitude 3190               | [bb05f51a63](https://linux-hardware.org/?probe=bb05f51a63) | Jun 20, 2022 |
| Dell          | Inspiron 3451               | [d9ac6a3f41](https://linux-hardware.org/?probe=d9ac6a3f41) | Jun 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c8a4e8226](https://linux-hardware.org/?probe=3c8a4e8226) | Jun 18, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [ee2f7822c9](https://linux-hardware.org/?probe=ee2f7822c9) | Jun 18, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [f944290604](https://linux-hardware.org/?probe=f944290604) | Jun 17, 2022 |
| Dell          | Latitude E5450              | [42f5a53e24](https://linux-hardware.org/?probe=42f5a53e24) | Jun 16, 2022 |
| Acer          | Aspire E1-570G              | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| mPTech        | ARC 11.6 128GB HD           | [b9469e3ae8](https://linux-hardware.org/?probe=b9469e3ae8) | Jun 15, 2022 |
| Dell          | Latitude E6430s             | [a1043bd5bf](https://linux-hardware.org/?probe=a1043bd5bf) | Jun 14, 2022 |
| ASUSTek       | 1005P                       | [4bd178fe29](https://linux-hardware.org/?probe=4bd178fe29) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [35cbb5ff8b](https://linux-hardware.org/?probe=35cbb5ff8b) | Jun 14, 2022 |
| Dell          | Inspiron 3451               | [7ca7f789d8](https://linux-hardware.org/?probe=7ca7f789d8) | Jun 14, 2022 |
| Dell          | Latitude E5470              | [a4533cfbc7](https://linux-hardware.org/?probe=a4533cfbc7) | Jun 14, 2022 |
| Acer          | Aspire 7738                 | [39646d89f1](https://linux-hardware.org/?probe=39646d89f1) | Jun 14, 2022 |
| Acer          | TravelMate 5760             | [90e189c067](https://linux-hardware.org/?probe=90e189c067) | Jun 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e33ea31f97](https://linux-hardware.org/?probe=e33ea31f97) | Jun 13, 2022 |
| HP            | EliteBook 850 G2            | [10b796ad9c](https://linux-hardware.org/?probe=10b796ad9c) | Jun 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [0a985a9f53](https://linux-hardware.org/?probe=0a985a9f53) | Jun 13, 2022 |
| MSI           | Bravo 17 A4DDR              | [fc31a9ec53](https://linux-hardware.org/?probe=fc31a9ec53) | Jun 13, 2022 |
| MSI           | Bravo 17 A4DDR              | [916ce4be3b](https://linux-hardware.org/?probe=916ce4be3b) | Jun 13, 2022 |
| Dell          | Latitude 3190               | [fb55b815b6](https://linux-hardware.org/?probe=fb55b815b6) | Jun 13, 2022 |
| HP            | ZBook Studio G3             | [0dda22b68b](https://linux-hardware.org/?probe=0dda22b68b) | Jun 12, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| Lenovo        | M490s 20214                 | [961e8807e9](https://linux-hardware.org/?probe=961e8807e9) | Jun 12, 2022 |
| ASUSTek       | K53BR                       | [b64b9e0f4a](https://linux-hardware.org/?probe=b64b9e0f4a) | Jun 12, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Acer          | Aspire A515-51G             | [785b725767](https://linux-hardware.org/?probe=785b725767) | Jun 10, 2022 |
| Dell          | Latitude 5310               | [fe0ffed6e4](https://linux-hardware.org/?probe=fe0ffed6e4) | Jun 10, 2022 |
| HP            | EliteBook 850 G3            | [e086b31446](https://linux-hardware.org/?probe=e086b31446) | Jun 10, 2022 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | [c97b8918a0](https://linux-hardware.org/?probe=c97b8918a0) | Jun 10, 2022 |
| Dell          | Latitude E6420              | [a92cd16ef7](https://linux-hardware.org/?probe=a92cd16ef7) | Jun 10, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [58d62f94d4](https://linux-hardware.org/?probe=58d62f94d4) | Jun 09, 2022 |
| Lenovo        | ThinkPad T500 2241A87       | [96b00f450d](https://linux-hardware.org/?probe=96b00f450d) | Jun 09, 2022 |
| Acer          | Nitro AN515-54              | [d14ead3bf7](https://linux-hardware.org/?probe=d14ead3bf7) | Jun 09, 2022 |
| HP            | ProBook 450 G5              | [cec4cb4af4](https://linux-hardware.org/?probe=cec4cb4af4) | Jun 09, 2022 |
| Lenovo        | ThinkPad T530 2429B68       | [86e92f8a19](https://linux-hardware.org/?probe=86e92f8a19) | Jun 09, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [ebc62a50b4](https://linux-hardware.org/?probe=ebc62a50b4) | Jun 08, 2022 |
| Acer          | Swift SF314-42              | [5af5c89f5e](https://linux-hardware.org/?probe=5af5c89f5e) | Jun 08, 2022 |
| Dell          | Latitude 5421               | [24665e8e4b](https://linux-hardware.org/?probe=24665e8e4b) | Jun 08, 2022 |
| Dell          | Precision 5550              | [a4bf41771c](https://linux-hardware.org/?probe=a4bf41771c) | Jun 07, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [4655b6a8ed](https://linux-hardware.org/?probe=4655b6a8ed) | Jun 07, 2022 |
| Dell          | Inspiron 3451               | [a6feb9dcd2](https://linux-hardware.org/?probe=a6feb9dcd2) | Jun 07, 2022 |
| HP            | Pavilion dv6700             | [a688137dd3](https://linux-hardware.org/?probe=a688137dd3) | Jun 07, 2022 |
| Unknown       | Unknown                     | [c0625a957b](https://linux-hardware.org/?probe=c0625a957b) | Jun 06, 2022 |
| Dell          | Latitude 3190               | [190816b333](https://linux-hardware.org/?probe=190816b333) | Jun 06, 2022 |
| Dell          | Latitude E6430              | [95b7617708](https://linux-hardware.org/?probe=95b7617708) | Jun 05, 2022 |
| MSI           | PR601/VR603                 | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Fujitsu       | FMVA0800C                   | [bacd4a55bb](https://linux-hardware.org/?probe=bacd4a55bb) | Jun 05, 2022 |
| Acer          | Swift SF314-42              | [fbfcffd093](https://linux-hardware.org/?probe=fbfcffd093) | Jun 03, 2022 |
| Lenovo        | G580 20150                  | [ca44145e04](https://linux-hardware.org/?probe=ca44145e04) | Jun 03, 2022 |
| Dell          | Inspiron 3451               | [ba5e3a5d77](https://linux-hardware.org/?probe=ba5e3a5d77) | Jun 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [2db8072ec9](https://linux-hardware.org/?probe=2db8072ec9) | Jun 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [5b88aad243](https://linux-hardware.org/?probe=5b88aad243) | Jun 02, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [491a4105d8](https://linux-hardware.org/?probe=491a4105d8) | Jun 01, 2022 |
| Dell          | Inspiron 5749               | [408e42beb8](https://linux-hardware.org/?probe=408e42beb8) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [d12c2f9f7c](https://linux-hardware.org/?probe=d12c2f9f7c) | Jun 01, 2022 |
| Dell          | Inspiron 3451               | [04e9ce0ba0](https://linux-hardware.org/?probe=04e9ce0ba0) | Jun 01, 2022 |
| Dell          | Inspiron 5521               | [4fdf9880d4](https://linux-hardware.org/?probe=4fdf9880d4) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [1e6ab0f183](https://linux-hardware.org/?probe=1e6ab0f183) | May 31, 2022 |
| HP            | EliteBook 8440p             | [4df2d3c129](https://linux-hardware.org/?probe=4df2d3c129) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [9b53c4df9d](https://linux-hardware.org/?probe=9b53c4df9d) | May 31, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [a08d3e5d4b](https://linux-hardware.org/?probe=a08d3e5d4b) | May 31, 2022 |
| Dell          | Latitude 5511               | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| Dell          | Latitude 3190               | [e43c62a67a](https://linux-hardware.org/?probe=e43c62a67a) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c71a8e9817](https://linux-hardware.org/?probe=c71a8e9817) | May 29, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| MSI           | GP76 Leopard 10UE           | [9e74d767a6](https://linux-hardware.org/?probe=9e74d767a6) | May 29, 2022 |
| Dell          | Inspiron 3451               | [8ad9f9f5d9](https://linux-hardware.org/?probe=8ad9f9f5d9) | May 29, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [8e577a4a1a](https://linux-hardware.org/?probe=8e577a4a1a) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [b8c8e8baef](https://linux-hardware.org/?probe=b8c8e8baef) | May 27, 2022 |
| Dell          | Inspiron 3451               | [798f65546b](https://linux-hardware.org/?probe=798f65546b) | May 27, 2022 |
| Sony          | VPCEE3S1E                   | [f3c7988996](https://linux-hardware.org/?probe=f3c7988996) | May 27, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [cff9e3245c](https://linux-hardware.org/?probe=cff9e3245c) | May 25, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [29b8def5b3](https://linux-hardware.org/?probe=29b8def5b3) | May 25, 2022 |
| Dell          | Latitude 5310               | [2117fbfccb](https://linux-hardware.org/?probe=2117fbfccb) | May 25, 2022 |
| HP            | 250 G8 Notebook PC          | [ce09b72069](https://linux-hardware.org/?probe=ce09b72069) | May 25, 2022 |
| HP            | 250 G8 Notebook PC          | [cee3591bcd](https://linux-hardware.org/?probe=cee3591bcd) | May 25, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [0517751353](https://linux-hardware.org/?probe=0517751353) | May 24, 2022 |
| Dell          | Latitude 5310               | [cb40714b3f](https://linux-hardware.org/?probe=cb40714b3f) | May 24, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [ed4df544d6](https://linux-hardware.org/?probe=ed4df544d6) | May 24, 2022 |
| HP            | Pavilion 15                 | [4140810d35](https://linux-hardware.org/?probe=4140810d35) | May 24, 2022 |
| HP            | 250 G8 Notebook PC          | [2f4c72e2a9](https://linux-hardware.org/?probe=2f4c72e2a9) | May 24, 2022 |
| HP            | ProBook 6475b               | [5202cf8c75](https://linux-hardware.org/?probe=5202cf8c75) | May 23, 2022 |
| HP            | Pavilion 15                 | [ca77af8ab9](https://linux-hardware.org/?probe=ca77af8ab9) | May 23, 2022 |
| Lenovo        | ThinkPad T61 7661BM5        | [9a6d69d512](https://linux-hardware.org/?probe=9a6d69d512) | May 22, 2022 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [d728114b9b](https://linux-hardware.org/?probe=d728114b9b) | May 22, 2022 |
| Acer          | Aspire E5-571G              | [8f47f3a71c](https://linux-hardware.org/?probe=8f47f3a71c) | May 22, 2022 |
| Acer          | Nitro AN515-54              | [04a8f20f28](https://linux-hardware.org/?probe=04a8f20f28) | May 21, 2022 |
| Dell          | Inspiron 3451               | [38c450f343](https://linux-hardware.org/?probe=38c450f343) | May 21, 2022 |
| Lenovo        | G50-70 20351                | [b6f469418c](https://linux-hardware.org/?probe=b6f469418c) | May 21, 2022 |
| Dell          | Latitude 5490               | [450756ee49](https://linux-hardware.org/?probe=450756ee49) | May 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| Dell          | Inspiron 3451               | [d14ff2c62e](https://linux-hardware.org/?probe=d14ff2c62e) | May 20, 2022 |
| HP            | EliteBook 8570w             | [3f21c66d5c](https://linux-hardware.org/?probe=3f21c66d5c) | May 20, 2022 |
| HP            | EliteBook 850 G6            | [1b672f1faa](https://linux-hardware.org/?probe=1b672f1faa) | May 20, 2022 |
| HP            | EliteBook 850 G6            | [d2232927a7](https://linux-hardware.org/?probe=d2232927a7) | May 20, 2022 |
| HP            | 250 G4 Notebook PC          | [1472f65ca0](https://linux-hardware.org/?probe=1472f65ca0) | May 19, 2022 |
| Sony          | VGN-NR32L_S                 | [2709583292](https://linux-hardware.org/?probe=2709583292) | May 18, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [5e0b60c547](https://linux-hardware.org/?probe=5e0b60c547) | May 17, 2022 |
| Dell          | Latitude E6230              | [1afeba4362](https://linux-hardware.org/?probe=1afeba4362) | May 17, 2022 |
| Dell          | Inspiron 5735               | [b678e46de2](https://linux-hardware.org/?probe=b678e46de2) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| Toshiba       | Satellite L750D             | [6a84eb18c8](https://linux-hardware.org/?probe=6a84eb18c8) | May 16, 2022 |
| Dell          | Latitude 3190               | [e80556f7d6](https://linux-hardware.org/?probe=e80556f7d6) | May 16, 2022 |
| Dell          | Latitude 5580               | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| Dell          | Inspiron 3583               | [3589bb82ad](https://linux-hardware.org/?probe=3589bb82ad) | May 15, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [59c5dbcb22](https://linux-hardware.org/?probe=59c5dbcb22) | May 15, 2022 |
| Lenovo        | ThinkPad T500 2241W2B       | [2bd7b2d9a4](https://linux-hardware.org/?probe=2bd7b2d9a4) | May 14, 2022 |
| Packard Be... | EasyNote ENTF71BM           | [e8808a770a](https://linux-hardware.org/?probe=e8808a770a) | May 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [5fad688f56](https://linux-hardware.org/?probe=5fad688f56) | May 14, 2022 |
| Dell          | MXG061                      | [36b09ae01e](https://linux-hardware.org/?probe=36b09ae01e) | May 14, 2022 |
| HP            | 250 G4 Notebook PC          | [996bc01199](https://linux-hardware.org/?probe=996bc01199) | May 13, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [761f1a1cbd](https://linux-hardware.org/?probe=761f1a1cbd) | May 13, 2022 |
| Dell          | Inspiron 3541               | [7873185850](https://linux-hardware.org/?probe=7873185850) | May 12, 2022 |
| HP            | EliteBook 820 G1            | [dd51bb3592](https://linux-hardware.org/?probe=dd51bb3592) | May 12, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [c64195c6bb](https://linux-hardware.org/?probe=c64195c6bb) | May 12, 2022 |
| HP            | EliteBook 840 G1            | [a57e3f28c2](https://linux-hardware.org/?probe=a57e3f28c2) | May 12, 2022 |
| Lenovo        | ThinkPad X200 7458WAY       | [1d845e69bd](https://linux-hardware.org/?probe=1d845e69bd) | May 11, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7d03983e37](https://linux-hardware.org/?probe=7d03983e37) | May 11, 2022 |
| Dell          | Precision 7530              | [d97721b6cf](https://linux-hardware.org/?probe=d97721b6cf) | May 11, 2022 |
| Dell          | Inspiron 3583               | [5b2b56f445](https://linux-hardware.org/?probe=5b2b56f445) | May 11, 2022 |
| Lenovo        | V15-IIL 82C5                | [b02040672d](https://linux-hardware.org/?probe=b02040672d) | May 11, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [af186fe9e3](https://linux-hardware.org/?probe=af186fe9e3) | May 10, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [b6fed1d4fe](https://linux-hardware.org/?probe=b6fed1d4fe) | May 10, 2022 |
| HP            | EliteBook 820 G3            | [015ede2e58](https://linux-hardware.org/?probe=015ede2e58) | May 09, 2022 |
| HP            | EliteBook 8570w             | [840087bbed](https://linux-hardware.org/?probe=840087bbed) | May 09, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [9e81b04453](https://linux-hardware.org/?probe=9e81b04453) | May 09, 2022 |
| HP            | EliteBook 8570w             | [d9779b1c50](https://linux-hardware.org/?probe=d9779b1c50) | May 09, 2022 |
| Dell          | MXG061                      | [119f6dd774](https://linux-hardware.org/?probe=119f6dd774) | May 09, 2022 |
| Google        | Relm                        | [37a9101768](https://linux-hardware.org/?probe=37a9101768) | May 09, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [c302d389bc](https://linux-hardware.org/?probe=c302d389bc) | May 08, 2022 |
| Dell          | Latitude E6220              | [f5ba7cbb31](https://linux-hardware.org/?probe=f5ba7cbb31) | May 08, 2022 |
| Dell          | Vostro 1440                 | [a44eb19e96](https://linux-hardware.org/?probe=a44eb19e96) | May 08, 2022 |
| Dell          | Vostro 1440                 | [356b0ae168](https://linux-hardware.org/?probe=356b0ae168) | May 08, 2022 |
| Lenovo        | G510 20238                  | [8a5f88eca1](https://linux-hardware.org/?probe=8a5f88eca1) | May 08, 2022 |
| ASUSTek       | N76VZ                       | [f1e06f5c2f](https://linux-hardware.org/?probe=f1e06f5c2f) | May 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [9a1a0ce2f1](https://linux-hardware.org/?probe=9a1a0ce2f1) | May 08, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [880b5d5853](https://linux-hardware.org/?probe=880b5d5853) | May 07, 2022 |
| HP            | ProBook 4530s               | [76fc5ea6ce](https://linux-hardware.org/?probe=76fc5ea6ce) | May 06, 2022 |
| Apple         | MacBookPro8,2               | [87e8930fcf](https://linux-hardware.org/?probe=87e8930fcf) | May 06, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fb4cf43d54](https://linux-hardware.org/?probe=fb4cf43d54) | May 05, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [503e18f6cb](https://linux-hardware.org/?probe=503e18f6cb) | May 05, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [76d61df983](https://linux-hardware.org/?probe=76d61df983) | May 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [a9f5b77476](https://linux-hardware.org/?probe=a9f5b77476) | May 04, 2022 |
| Acer          | Nitro AN515-54              | [1d9a559405](https://linux-hardware.org/?probe=1d9a559405) | May 04, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ee3b3dc380](https://linux-hardware.org/?probe=ee3b3dc380) | May 04, 2022 |
| ASUSTek       | N76VZ                       | [b9c2a28ba0](https://linux-hardware.org/?probe=b9c2a28ba0) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2349AK5       | [78f64f92f3](https://linux-hardware.org/?probe=78f64f92f3) | May 03, 2022 |
| ASUSTek       | X550CL                      | [b224821361](https://linux-hardware.org/?probe=b224821361) | May 03, 2022 |
| Toshiba       | Satellite C55t-C            | [7c1211e221](https://linux-hardware.org/?probe=7c1211e221) | May 02, 2022 |
| ASUSTek       | X705UAP                     | [5703c517d1](https://linux-hardware.org/?probe=5703c517d1) | May 02, 2022 |
| Acer          | Aspire E5-571G              | [8df6782398](https://linux-hardware.org/?probe=8df6782398) | May 02, 2022 |
| ASUSTek       | X550CL                      | [5340c940c2](https://linux-hardware.org/?probe=5340c940c2) | May 02, 2022 |
| ASUSTek       | X580VD                      | [920fb8f8d8](https://linux-hardware.org/?probe=920fb8f8d8) | May 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [112d0557c3](https://linux-hardware.org/?probe=112d0557c3) | May 01, 2022 |
| Fujitsu       | LIFEBOOK S751               | [6150343dc0](https://linux-hardware.org/?probe=6150343dc0) | May 01, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [317736e849](https://linux-hardware.org/?probe=317736e849) | May 01, 2022 |
| Toshiba       | Satellite C55t-C            | [dd21a03b63](https://linux-hardware.org/?probe=dd21a03b63) | May 01, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ea3bd2e330](https://linux-hardware.org/?probe=ea3bd2e330) | May 01, 2022 |
| Apple         | MacBookPro7,1               | [ac3f2c5c61](https://linux-hardware.org/?probe=ac3f2c5c61) | May 01, 2022 |
| Acer          | Extensa 5220                | [ebbd01171d](https://linux-hardware.org/?probe=ebbd01171d) | May 01, 2022 |
| Lenovo        | G510 20238                  | [07e8a61019](https://linux-hardware.org/?probe=07e8a61019) | Apr 30, 2022 |
| ASUSTek       | UX303LAB                    | [4d47234d72](https://linux-hardware.org/?probe=4d47234d72) | Apr 30, 2022 |
| Acer          | Aspire E5-571               | [35b5fa2276](https://linux-hardware.org/?probe=35b5fa2276) | Apr 30, 2022 |
| ASUSTek       | X71Vn                       | [b31a7dce8b](https://linux-hardware.org/?probe=b31a7dce8b) | Apr 29, 2022 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [2c8a1c2444](https://linux-hardware.org/?probe=2c8a1c2444) | Apr 29, 2022 |
| Apple         | MacBook3,1                  | [5c90931c74](https://linux-hardware.org/?probe=5c90931c74) | Apr 28, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [00474d7e97](https://linux-hardware.org/?probe=00474d7e97) | Apr 28, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [3c9c9f209d](https://linux-hardware.org/?probe=3c9c9f209d) | Apr 28, 2022 |
| Dell          | Latitude 5420               | [26abde11eb](https://linux-hardware.org/?probe=26abde11eb) | Apr 28, 2022 |
| Apple         | MacBook3,1                  | [c7da3d4c4f](https://linux-hardware.org/?probe=c7da3d4c4f) | Apr 27, 2022 |
| Acer          | Nitro AN515-43              | [99527fd065](https://linux-hardware.org/?probe=99527fd065) | Apr 26, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [482bb47b36](https://linux-hardware.org/?probe=482bb47b36) | Apr 26, 2022 |
| HP            | EliteBook 8770w             | [4fa8e91f6d](https://linux-hardware.org/?probe=4fa8e91f6d) | Apr 26, 2022 |
| Dell          | Latitude 7520               | [674f3ca531](https://linux-hardware.org/?probe=674f3ca531) | Apr 26, 2022 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [489a3a5798](https://linux-hardware.org/?probe=489a3a5798) | Apr 26, 2022 |
| Dell          | Precision 7510              | [484a851b85](https://linux-hardware.org/?probe=484a851b85) | Apr 25, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [06a00cfce7](https://linux-hardware.org/?probe=06a00cfce7) | Apr 25, 2022 |
| HP            | Pavilion 17                 | [8a86695a31](https://linux-hardware.org/?probe=8a86695a31) | Apr 25, 2022 |
| MSI           | PE60 2QE                    | [703b37d444](https://linux-hardware.org/?probe=703b37d444) | Apr 24, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | [ac10947315](https://linux-hardware.org/?probe=ac10947315) | Apr 24, 2022 |
| HUAWEI        | HVY-WXX9                    | [43098a1f34](https://linux-hardware.org/?probe=43098a1f34) | Apr 23, 2022 |
| HP            | EliteBook 8440p             | [487f1a4924](https://linux-hardware.org/?probe=487f1a4924) | Apr 23, 2022 |
| Acer          | Aspire E1-531               | [c1cd0a61e1](https://linux-hardware.org/?probe=c1cd0a61e1) | Apr 23, 2022 |
| HP            | Pavilion 17                 | [851d01ca2e](https://linux-hardware.org/?probe=851d01ca2e) | Apr 23, 2022 |
| Dell          | Inspiron 3542               | [0c301210d8](https://linux-hardware.org/?probe=0c301210d8) | Apr 22, 2022 |
| ASUSTek       | X541UJ                      | [4043c70a42](https://linux-hardware.org/?probe=4043c70a42) | Apr 22, 2022 |
| HUAWEI        | HVY-WXX9                    | [3320719d25](https://linux-hardware.org/?probe=3320719d25) | Apr 22, 2022 |
| MSI           | GE60 2PC                    | [0614a4172b](https://linux-hardware.org/?probe=0614a4172b) | Apr 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [b6a457c33a](https://linux-hardware.org/?probe=b6a457c33a) | Apr 21, 2022 |
| Dell          | Latitude E6420              | [83b008961c](https://linux-hardware.org/?probe=83b008961c) | Apr 21, 2022 |
| Samsung       | RC410/RC510/RC710           | [9adfada605](https://linux-hardware.org/?probe=9adfada605) | Apr 20, 2022 |
| Dell          | Latitude E6420              | [85d321a02b](https://linux-hardware.org/?probe=85d321a02b) | Apr 20, 2022 |
| Dell          | Inspiron 15-3567            | [b87e7c08ab](https://linux-hardware.org/?probe=b87e7c08ab) | Apr 19, 2022 |
| HP            | ProBook 6440b               | [54a85fc99d](https://linux-hardware.org/?probe=54a85fc99d) | Apr 18, 2022 |
| Lenovo        | ThinkPad Edge E430 3254C... | [df0e3664e4](https://linux-hardware.org/?probe=df0e3664e4) | Apr 17, 2022 |
| MSI           | GF75 Thin 10UEK             | [866aa88f0f](https://linux-hardware.org/?probe=866aa88f0f) | Apr 17, 2022 |
| ASUSTek       | S551LB                      | [bb1d6d3623](https://linux-hardware.org/?probe=bb1d6d3623) | Apr 17, 2022 |
| HP            | Pavilion g6                 | [a7f800ed49](https://linux-hardware.org/?probe=a7f800ed49) | Apr 16, 2022 |
| Dell          | Inspiron 5570               | [066d125002](https://linux-hardware.org/?probe=066d125002) | Apr 15, 2022 |
| Acer          | Nitro AN515-42              | [f203fe95e5](https://linux-hardware.org/?probe=f203fe95e5) | Apr 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [77cf6f482e](https://linux-hardware.org/?probe=77cf6f482e) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [13bfd82a49](https://linux-hardware.org/?probe=13bfd82a49) | Apr 14, 2022 |
| ASUSTek       | N61Jv                       | [959c5f2238](https://linux-hardware.org/?probe=959c5f2238) | Apr 14, 2022 |
| Sony          | VGN-FZ11M                   | [23731be3a1](https://linux-hardware.org/?probe=23731be3a1) | Apr 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [154eb4b040](https://linux-hardware.org/?probe=154eb4b040) | Apr 14, 2022 |
| Lenovo        | G500 20236                  | [2decdc1731](https://linux-hardware.org/?probe=2decdc1731) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E430 3254C... | [155a0f970f](https://linux-hardware.org/?probe=155a0f970f) | Apr 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7e6cb72711](https://linux-hardware.org/?probe=7e6cb72711) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [729b19eda3](https://linux-hardware.org/?probe=729b19eda3) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f2588a9d63](https://linux-hardware.org/?probe=f2588a9d63) | Apr 13, 2022 |
| Toshiba       | Satellite A300              | [1773d841d4](https://linux-hardware.org/?probe=1773d841d4) | Apr 13, 2022 |
| Dell          | Latitude E6420              | [7491167b48](https://linux-hardware.org/?probe=7491167b48) | Apr 13, 2022 |
| Dell          | Latitude E6420              | [3a6e6c7a62](https://linux-hardware.org/?probe=3a6e6c7a62) | Apr 13, 2022 |
| Dell          | Inspiron 17 7000 Series ... | [c8abf66820](https://linux-hardware.org/?probe=c8abf66820) | Apr 12, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [c3d7c67155](https://linux-hardware.org/?probe=c3d7c67155) | Apr 12, 2022 |
| Dell          | Latitude 5480               | [f733f24fdc](https://linux-hardware.org/?probe=f733f24fdc) | Apr 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [47cecc43f6](https://linux-hardware.org/?probe=47cecc43f6) | Apr 11, 2022 |
| Lenovo        | 3000 V200 076472G           | [11a06d9b03](https://linux-hardware.org/?probe=11a06d9b03) | Apr 10, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7f5ccf9e6d](https://linux-hardware.org/?probe=7f5ccf9e6d) | Apr 10, 2022 |
| ASUSTek       | X553MA                      | [68e49479b4](https://linux-hardware.org/?probe=68e49479b4) | Apr 09, 2022 |
| Lenovo        | Z51-70 80K6                 | [dc1db2125f](https://linux-hardware.org/?probe=dc1db2125f) | Apr 08, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [414464db43](https://linux-hardware.org/?probe=414464db43) | Apr 08, 2022 |
| Dell          | Latitude 5480               | [6891954221](https://linux-hardware.org/?probe=6891954221) | Apr 08, 2022 |
| Dell          | Inspiron 5515               | [de3e7023c4](https://linux-hardware.org/?probe=de3e7023c4) | Apr 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [556d9d27ef](https://linux-hardware.org/?probe=556d9d27ef) | Apr 07, 2022 |
| Dell          | Latitude E4310              | [e89d84e0dd](https://linux-hardware.org/?probe=e89d84e0dd) | Apr 07, 2022 |
| HP            | EliteBook 840 G2            | [691c061ef4](https://linux-hardware.org/?probe=691c061ef4) | Apr 07, 2022 |
| Dell          | Latitude 5521               | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Dell          | Latitude 5480               | [4e82478bdf](https://linux-hardware.org/?probe=4e82478bdf) | Apr 07, 2022 |
| Dell          | MXG061                      | [3ff1cc3367](https://linux-hardware.org/?probe=3ff1cc3367) | Apr 07, 2022 |
| Dell          | MXG061                      | [9c91bd9487](https://linux-hardware.org/?probe=9c91bd9487) | Apr 06, 2022 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [9536873aca](https://linux-hardware.org/?probe=9536873aca) | Apr 06, 2022 |
| Acer          | Aspire E5-774G              | [2e61b0b4d5](https://linux-hardware.org/?probe=2e61b0b4d5) | Apr 05, 2022 |
| Apple         | MacBookAir4,2               | [0c1f8b4efe](https://linux-hardware.org/?probe=0c1f8b4efe) | Apr 05, 2022 |
| Lenovo        | G580 20150                  | [d85f7abf8c](https://linux-hardware.org/?probe=d85f7abf8c) | Apr 05, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [81165aa277](https://linux-hardware.org/?probe=81165aa277) | Apr 05, 2022 |
| Acer          | TravelMate P215-41-G2       | [4e35add210](https://linux-hardware.org/?probe=4e35add210) | Apr 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [37b0484558](https://linux-hardware.org/?probe=37b0484558) | Apr 04, 2022 |
| Dell          | Latitude 5421               | [78ac6f00cd](https://linux-hardware.org/?probe=78ac6f00cd) | Apr 04, 2022 |
| Apple         | MacBookPro12,1              | [44a524bb2f](https://linux-hardware.org/?probe=44a524bb2f) | Apr 03, 2022 |
| Acer          | Nitro AN515-43              | [e6e1af5316](https://linux-hardware.org/?probe=e6e1af5316) | Apr 03, 2022 |
| HP            | Unknown                     | [e33741c278](https://linux-hardware.org/?probe=e33741c278) | Apr 03, 2022 |
| HP            | Pavilion g6                 | [6f774cb7a9](https://linux-hardware.org/?probe=6f774cb7a9) | Apr 03, 2022 |
| Acer          | Nitro AN515-52              | [51980559c7](https://linux-hardware.org/?probe=51980559c7) | Apr 03, 2022 |
| HP            | ProBook 650 G1              | [f13dbb1e06](https://linux-hardware.org/?probe=f13dbb1e06) | Apr 02, 2022 |
| HP            | 255 G7 Notebook PC          | [a7d794c2d8](https://linux-hardware.org/?probe=a7d794c2d8) | Apr 02, 2022 |
| HP            | Unknown                     | [761f0c08b2](https://linux-hardware.org/?probe=761f0c08b2) | Apr 02, 2022 |
| Dell          | Inspiron MM061              | [ca95a8324a](https://linux-hardware.org/?probe=ca95a8324a) | Apr 02, 2022 |
| Dell          | Inspiron MM061              | [a6f8e740aa](https://linux-hardware.org/?probe=a6f8e740aa) | Apr 02, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [f1ceaa5222](https://linux-hardware.org/?probe=f1ceaa5222) | Apr 02, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [ce4341b7b1](https://linux-hardware.org/?probe=ce4341b7b1) | Apr 01, 2022 |
| HP            | EliteBook 820 G2            | [5308b25e76](https://linux-hardware.org/?probe=5308b25e76) | Mar 31, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [eeb03a5d88](https://linux-hardware.org/?probe=eeb03a5d88) | Mar 31, 2022 |
| Valve         | Jupiter                     | [d8625616de](https://linux-hardware.org/?probe=d8625616de) | Mar 30, 2022 |
| Acer          | Nitro AN515-43              | [d1c02dfaee](https://linux-hardware.org/?probe=d1c02dfaee) | Mar 29, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [fc7ebbef4e](https://linux-hardware.org/?probe=fc7ebbef4e) | Mar 29, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [ab2bed88a7](https://linux-hardware.org/?probe=ab2bed88a7) | Mar 29, 2022 |
| Dell          | XPS 15 7590                 | [426b141f91](https://linux-hardware.org/?probe=426b141f91) | Mar 29, 2022 |
| ASUSTek       | UX310UA                     | [b052cccfb8](https://linux-hardware.org/?probe=b052cccfb8) | Mar 27, 2022 |
| Dell          | MXG071                      | [ac0158dcb9](https://linux-hardware.org/?probe=ac0158dcb9) | Mar 27, 2022 |
| Dell          | Inspiron 5758               | [ddd5e24256](https://linux-hardware.org/?probe=ddd5e24256) | Mar 26, 2022 |
| MAXDATA       | ECO4510IW                   | [d731c99bf8](https://linux-hardware.org/?probe=d731c99bf8) | Mar 26, 2022 |
| Dell          | Latitude E7450              | [db931ebb1f](https://linux-hardware.org/?probe=db931ebb1f) | Mar 25, 2022 |
| Dell          | Latitude 5420               | [fed42f2345](https://linux-hardware.org/?probe=fed42f2345) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| HP            | ProBook 6570b               | [41548696b7](https://linux-hardware.org/?probe=41548696b7) | Mar 23, 2022 |
| HP            | Pavilion ZV6100 (EE984EA... | [282dfe7eb0](https://linux-hardware.org/?probe=282dfe7eb0) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f7f7b2d459](https://linux-hardware.org/?probe=f7f7b2d459) | Mar 22, 2022 |
| Packard Be... | EasyNote TK85               | [7b2ab61a6e](https://linux-hardware.org/?probe=7b2ab61a6e) | Mar 21, 2022 |
| Dell          | System Inspiron N7110       | [d3b1757cf5](https://linux-hardware.org/?probe=d3b1757cf5) | Mar 21, 2022 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [ceb4f22239](https://linux-hardware.org/?probe=ceb4f22239) | Mar 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 339       | 12.5%   |
| OpenMandriva 4.2             | 187       | 6.9%    |
| Ubuntu 18.04                 | 166       | 6.12%   |
| Ubuntu 22.04                 | 104       | 3.84%   |
| OpenMandriva 4.3             | 100       | 3.69%   |
| Debian 11                    | 80        | 2.95%   |
| ROSA R10                     | 50        | 1.84%   |
| Arch Rolling                 | 47        | 1.73%   |
| Linux Mint 20.3              | 42        | 1.55%   |
| Linux Mint 20.1              | 42        | 1.55%   |
| Arch                         | 42        | 1.55%   |
| KDE neon 20.04               | 40        | 1.48%   |
| ROSA R9                      | 39        | 1.44%   |
| Fedora 36                    | 36        | 1.33%   |
| Manjaro                      | 34        | 1.25%   |
| ROSA R11.1                   | 33        | 1.22%   |
| Linux Mint 20.2              | 33        | 1.22%   |
| Ubuntu 21.04                 | 32        | 1.18%   |
| Ubuntu 20.10                 | 32        | 1.18%   |
| Linux Mint 19.3              | 31        | 1.14%   |
| Zorin 16                     | 30        | 1.11%   |
| ROSA R11                     | 29        | 1.07%   |
| Zorin 15                     | 27        | 1%      |
| Ubuntu 19.10                 | 27        | 1%      |
| OpenMandriva 23.01           | 27        | 1%      |
| Linux Mint 20                | 27        | 1%      |
| Ubuntu 21.10                 | 26        | 0.96%   |
| Xubuntu 20.04                | 25        | 0.92%   |
| ROSA R8                      | 25        | 0.92%   |
| Fedora 33                    | 25        | 0.92%   |
| Fedora 32                    | 24        | 0.89%   |
| Fedora 35                    | 23        | 0.85%   |
| Linux Mint 21                | 22        | 0.81%   |
| Debian 10                    | 21        | 0.77%   |
| Fedora 37                    | 20        | 0.74%   |
| Fedora 34                    | 20        | 0.74%   |
| Pop!_OS 20.04                | 19        | 0.7%    |
| openSUSE Tumbleweed-XXXXXXXX | 19        | 0.7%    |
| Ubuntu 22.10                 | 18        | 0.66%   |
| Kubuntu 20.04                | 18        | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 743       | 29.07%  |
| OpenMandriva  | 333       | 13.03%  |
| Linux Mint    | 213       | 8.33%   |
| ROSA          | 179       | 7%      |
| Fedora        | 166       | 6.49%   |
| Debian        | 121       | 4.73%   |
| Manjaro       | 105       | 4.11%   |
| Arch          | 85        | 3.33%   |
| Pop!_OS       | 66        | 2.58%   |
| Zorin         | 60        | 2.35%   |
| KDE neon      | 51        | 2%      |
| Kubuntu       | 47        | 1.84%   |
| Xubuntu       | 42        | 1.64%   |
| Kali          | 34        | 1.33%   |
| Lubuntu       | 25        | 0.98%   |
| Endless       | 22        | 0.86%   |
| openSUSE      | 21        | 0.82%   |
| Elementary    | 20        | 0.78%   |
| Gentoo        | 19        | 0.74%   |
| ArcoLinux     | 18        | 0.7%    |
| LMDE          | 15        | 0.59%   |
| Clear Linux   | 13        | 0.51%   |
| EndeavourOS   | 11        | 0.43%   |
| Nobara        | 10        | 0.39%   |
| Ubuntu Unity  | 9         | 0.35%   |
| Garuda Linux  | 9         | 0.35%   |
| Ubuntu MATE   | 8         | 0.31%   |
| SteamOS       | 8         | 0.31%   |
| LinuxFX       | 8         | 0.31%   |
| Ubuntu Budgie | 7         | 0.27%   |
| Peppermint    | 7         | 0.27%   |
| MX            | 6         | 0.23%   |
| BlackPanther  | 6         | 0.23%   |
| CentOS        | 5         | 0.2%    |
| Parrot        | 4         | 0.16%   |
| Linux Lite    | 4         | 0.16%   |
| Xero          | 3         | 0.12%   |
| Sparky        | 3         | 0.12%   |
| Solus         | 3         | 0.12%   |
| NixOS         | 3         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 5.99%   |
| 5.16.7-desktop-1omv4003         | 99        | 3.35%   |
| 5.4.0-42-generic                | 44        | 1.49%   |
| 5.15.0-56-generic               | 29        | 0.98%   |
| 6.1.1-desktop-1omv2290          | 27        | 0.91%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 26        | 0.88%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 24        | 0.81%   |
| 5.4.0-52-generic                | 22        | 0.74%   |
| 5.4.0-48-generic                | 22        | 0.74%   |
| 5.15.0-52-generic               | 21        | 0.71%   |
| 5.15.0-43-generic               | 21        | 0.71%   |
| 5.4.0-29-generic                | 20        | 0.68%   |
| 5.4.0-58-generic                | 19        | 0.64%   |
| 5.4.0-26-generic                | 19        | 0.64%   |
| 5.3.0-46-generic                | 18        | 0.61%   |
| 5.15.0-53-generic               | 18        | 0.61%   |
| 5.4.0-33-generic                | 17        | 0.58%   |
| 5.11.0-37-generic               | 17        | 0.58%   |
| 5.0.0-37-generic                | 17        | 0.58%   |
| 5.4.0-54-generic                | 16        | 0.54%   |
| 5.15.0-48-generic               | 16        | 0.54%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 16        | 0.54%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 16        | 0.54%   |
| 5.8.0-43-generic                | 15        | 0.51%   |
| 5.4.0-40-generic                | 14        | 0.47%   |
| 5.4.0-37-generic                | 14        | 0.47%   |
| 5.3.0-40-generic                | 14        | 0.47%   |
| 5.15.0-58-generic               | 14        | 0.47%   |
| 5.3.0-42-generic                | 13        | 0.44%   |
| 5.13.0-39-generic               | 13        | 0.44%   |
| 5.13.0-27-generic               | 13        | 0.44%   |
| 5.11.0-43-generic               | 13        | 0.44%   |
| 5.11.0-27-generic               | 13        | 0.44%   |
| 5.11.0-25-generic               | 13        | 0.44%   |
| 4.15.0-43-generic               | 13        | 0.44%   |
| 5.4.0-91-generic                | 12        | 0.41%   |
| 5.4.0-74-generic                | 12        | 0.41%   |
| 5.15.0-47-generic               | 12        | 0.41%   |
| 5.13.0-28-generic               | 12        | 0.41%   |
| 5.11.0-34-generic               | 12        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 438       | 15.61%  |
| 5.15.0  | 196       | 6.99%   |
| 5.10.14 | 178       | 6.35%   |
| 4.15.0  | 147       | 5.24%   |
| 5.11.0  | 143       | 5.1%    |
| 5.8.0   | 127       | 4.53%   |
| 5.13.0  | 113       | 4.03%   |
| 5.3.0   | 103       | 3.67%   |
| 5.16.7  | 100       | 3.57%   |
| 5.10.0  | 92        | 3.28%   |
| 5.0.0   | 61        | 2.17%   |
| 4.18.0  | 58        | 2.07%   |
| 4.9.20  | 35        | 1.25%   |
| 4.9.60  | 32        | 1.14%   |
| 4.19.0  | 30        | 1.07%   |
| 6.1.1   | 28        | 1%      |
| 5.19.0  | 23        | 0.82%   |
| 5.14.0  | 22        | 0.78%   |
| 4.1.34  | 22        | 0.78%   |
| 6.0.0   | 15        | 0.53%   |
| 4.1.38  | 14        | 0.5%    |
| 5.11.12 | 13        | 0.46%   |
| 5.17.0  | 12        | 0.43%   |
| 5.9.0   | 11        | 0.39%   |
| 5.17.5  | 11        | 0.39%   |
| 5.4.32  | 10        | 0.36%   |
| 6.0.7   | 9         | 0.32%   |
| 5.5.0   | 8         | 0.29%   |
| 5.4.83  | 8         | 0.29%   |
| 5.16.0  | 8         | 0.29%   |
| 4.9.76  | 8         | 0.29%   |
| 5.19.14 | 7         | 0.25%   |
| 5.18.12 | 7         | 0.25%   |
| 5.18.0  | 7         | 0.25%   |
| 5.16.11 | 7         | 0.25%   |
| 5.15.12 | 7         | 0.25%   |
| 6.0.9   | 6         | 0.21%   |
| 6.0.2   | 6         | 0.21%   |
| 5.7.0   | 6         | 0.21%   |
| 5.6.0   | 6         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 496       | 18.06%  |
| 5.10    | 320       | 11.65%  |
| 5.15    | 257       | 9.36%   |
| 5.11    | 180       | 6.55%   |
| 5.8     | 158       | 5.75%   |
| 5.16    | 151       | 5.5%    |
| 4.15    | 147       | 5.35%   |
| 5.13    | 130       | 4.73%   |
| 5.3     | 115       | 4.19%   |
| 4.9     | 99        | 3.6%    |
| 6.0     | 67        | 2.44%   |
| 5.0     | 67        | 2.44%   |
| 4.18    | 61        | 2.22%   |
| 5.19    | 59        | 2.15%   |
| 5.14    | 53        | 1.93%   |
| 5.17    | 49        | 1.78%   |
| 6.1     | 45        | 1.64%   |
| 5.9     | 42        | 1.53%   |
| 5.6     | 41        | 1.49%   |
| 5.18    | 39        | 1.42%   |
| 4.19    | 36        | 1.31%   |
| 4.1     | 35        | 1.27%   |
| 5.12    | 25        | 0.91%   |
| 5.5     | 23        | 0.84%   |
| 5.7     | 20        | 0.73%   |
| 4.4     | 8         | 0.29%   |
| 5.1     | 6         | 0.22%   |
| 3.10    | 4         | 0.15%   |
| 5.2     | 3         | 0.11%   |
| 4.20    | 2         | 0.07%   |
| 4.13    | 2         | 0.07%   |
| 4.10    | 2         | 0.07%   |
| 6.2     | 1         | 0.04%   |
| 4.17    | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |
| 4.12    | 1         | 0.04%   |
| 4.11    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2365      | 95.75%  |
| i686    | 104       | 4.21%   |
| aarch64 | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 961       | 37.19%  |
| KDE5            | 614       | 23.76%  |
| Unknown         | 253       | 9.79%   |
| XFCE            | 180       | 6.97%   |
| X-Cinnamon      | 150       | 5.8%    |
| KDE4            | 97        | 3.75%   |
| KDE             | 71        | 2.75%   |
| MATE            | 53        | 2.05%   |
| Cinnamon        | 41        | 1.59%   |
| LXQt            | 37        | 1.43%   |
| LXDE            | 34        | 1.32%   |
| Pantheon        | 18        | 0.7%    |
| i3              | 15        | 0.58%   |
| Budgie          | 14        | 0.54%   |
| Unity           | 11        | 0.43%   |
| Deepin          | 9         | 0.35%   |
| GNOME Flashback | 5         | 0.19%   |
| sway            | 3         | 0.12%   |
| GNOME Classic   | 3         | 0.12%   |
| awesome         | 3         | 0.12%   |
| Trinity         | 2         | 0.08%   |
| qtile           | 2         | 0.08%   |
| Fluxbox         | 2         | 0.08%   |
| DWM             | 2         | 0.08%   |
| stumpwm         | 1         | 0.04%   |
| qt5ct           | 1         | 0.04%   |
| openbox         | 1         | 0.04%   |
| GNUstep         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2033      | 80.13%  |
| Wayland | 349       | 13.76%  |
| Unknown | 128       | 5.05%   |
| Tty     | 27        | 1.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1068      | 41.38%  |
| SDDM    | 600       | 23.25%  |
| GDM     | 327       | 12.67%  |
| LightDM | 194       | 7.52%   |
| GDM3    | 188       | 7.28%   |
| KDM     | 99        | 3.84%   |
| TDM     | 95        | 3.68%   |
| XDM     | 5         | 0.19%   |
| Ly      | 2         | 0.08%   |
| SLiM    | 1         | 0.04%   |
| MDM     | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| pl_PL   | 1354      | 53.18%  |
| en_US   | 656       | 25.77%  |
| Unknown | 370       | 14.53%  |
| en_GB   | 69        | 2.71%   |
| C       | 39        | 1.53%   |
| ru_RU   | 15        | 0.59%   |
| szl_PL  | 9         | 0.35%   |
| de_DE   | 5         | 0.2%    |
| uk_UA   | 3         | 0.12%   |
| fr_FR   | 3         | 0.12%   |
| en_IE   | 3         | 0.12%   |
| ru_UA   | 2         | 0.08%   |
| nl_NL   | 2         | 0.08%   |
| it_IT   | 2         | 0.08%   |
| en_DK   | 2         | 0.08%   |
| C.UTF8  | 2         | 0.08%   |
| sk_SK   | 1         | 0.04%   |
| POSIX   | 1         | 0.04%   |
| hu_HU   | 1         | 0.04%   |
| es_ES   | 1         | 0.04%   |
| en_IN   | 1         | 0.04%   |
| en_CA   | 1         | 0.04%   |
| en_AU   | 1         | 0.04%   |
| en_AG   | 1         | 0.04%   |
| af_ZA   | 1         | 0.04%   |
| aa_DJ   | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1312      | 52.19%  |
| EFI  | 1202      | 47.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 1774      | 69.9%   |
| Overlay  | 323       | 12.73%  |
| Btrfs    | 195       | 7.68%   |
| Unknown  | 173       | 6.82%   |
| Xfs      | 35        | 1.38%   |
| Zfs      | 18        | 0.71%   |
| F2fs     | 9         | 0.35%   |
| Ext3     | 3         | 0.12%   |
| Ext2     | 3         | 0.12%   |
| Tmpfs    | 2         | 0.08%   |
| XXXXX    | 1         | 0.04%   |
| Rootfs   | 1         | 0.04%   |
| Bcachefs | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1213      | 48.04%  |
| GPT     | 890       | 35.25%  |
| MBR     | 422       | 16.71%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2137      | 84.94%  |
| Yes       | 379       | 15.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1690      | 67.49%  |
| Yes       | 814       | 32.51%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 645       | 26.16%  |
| Dell                | 535       | 21.7%   |
| Hewlett-Packard     | 373       | 15.13%  |
| ASUSTek Computer    | 298       | 12.08%  |
| Acer                | 161       | 6.53%   |
| Samsung Electronics | 71        | 2.88%   |
| Toshiba             | 68        | 2.76%   |
| MSI                 | 58        | 2.35%   |
| Sony                | 33        | 1.34%   |
| HUAWEI              | 27        | 1.09%   |
| Fujitsu Siemens     | 20        | 0.81%   |
| Fujitsu             | 19        | 0.77%   |
| Apple               | 18        | 0.73%   |
| Packard Bell        | 12        | 0.49%   |
| Notebook            | 11        | 0.45%   |
| Google              | 11        | 0.45%   |
| Valve               | 9         | 0.36%   |
| eMachines           | 9         | 0.36%   |
| Medion              | 7         | 0.28%   |
| Timi                | 6         | 0.24%   |
| Kiano               | 6         | 0.24%   |
| Kruger&Matz         | 4         | 0.16%   |
| Alienware           | 4         | 0.16%   |
| Unknown             | 4         | 0.16%   |
| mPTech              | 3         | 0.12%   |
| Gigabyte Technology | 3         | 0.12%   |
| Clevo               | 3         | 0.12%   |
| Chuwi               | 3         | 0.12%   |
| Teclast             | 2         | 0.08%   |
| System76            | 2         | 0.08%   |
| Star Labs           | 2         | 0.08%   |
| Panasonic           | 2         | 0.08%   |
| MODECOM             | 2         | 0.08%   |
| MAXDATA             | 2         | 0.08%   |
| Maibenben           | 2         | 0.08%   |
| Intel               | 2         | 0.08%   |
| IBM                 | 2         | 0.08%   |
| Getac               | 2         | 0.08%   |
| Gateway             | 2         | 0.08%   |
| Framework           | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Dell Inspiron 3451                  | 31        | 1.26%   |
| Unknown                             | 23        | 0.93%   |
| Dell Latitude E6400                 | 15        | 0.61%   |
| Dell Latitude E6540                 | 14        | 0.57%   |
| Lenovo G50-30 80G0                  | 12        | 0.49%   |
| Dell Latitude 5480                  | 12        | 0.49%   |
| Dell Latitude E6430                 | 11        | 0.45%   |
| Dell Latitude D630                  | 11        | 0.45%   |
| HP Pavilion dv7                     | 10        | 0.41%   |
| Dell Latitude 5490                  | 10        | 0.41%   |
| Valve Jupiter                       | 9         | 0.36%   |
| Dell Latitude E6420                 | 9         | 0.36%   |
| ASUS X555LJ                         | 9         | 0.36%   |
| Lenovo Legion Y530-15ICH 81FV       | 8         | 0.32%   |
| Lenovo G580 20150                   | 8         | 0.32%   |
| Dell Latitude E7440                 | 8         | 0.32%   |
| Lenovo Legion Y540-15IRH 81SX       | 7         | 0.28%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 7         | 0.28%   |
| HP EliteBook 6930p                  | 7         | 0.28%   |
| HP 15                               | 7         | 0.28%   |
| Dell Latitude E6330                 | 7         | 0.28%   |
| Dell Latitude E5430 non-vPro        | 7         | 0.28%   |
| Toshiba Satellite A300              | 6         | 0.24%   |
| Samsung 550P5C/550P7C               | 6         | 0.24%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 6         | 0.24%   |
| Lenovo Z51-70 80K6                  | 6         | 0.24%   |
| Lenovo Legion 5 15ARH05 82B5        | 6         | 0.24%   |
| Lenovo IdeaPad Y510P 20217          | 6         | 0.24%   |
| Lenovo IdeaPad 100-15IBY 80MJ       | 6         | 0.24%   |
| Lenovo IdeaPad 100-15IBD 80QQ       | 6         | 0.24%   |
| Lenovo G500 20236                   | 6         | 0.24%   |
| HUAWEI HVY-WXX9                     | 6         | 0.24%   |
| HP Pavilion g6                      | 6         | 0.24%   |
| HP Pavilion dv6                     | 6         | 0.24%   |
| HP Notebook                         | 6         | 0.24%   |
| HP Laptop 15-db1xxx                 | 6         | 0.24%   |
| HP 250 G6 Notebook PC               | 6         | 0.24%   |
| Dell Latitude E7450                 | 6         | 0.24%   |
| Dell Latitude E5470                 | 6         | 0.24%   |
| Dell Latitude 5420                  | 6         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 293       | 11.88%  |
| Dell Latitude         | 279       | 11.31%  |
| Dell Inspiron         | 142       | 5.76%   |
| Lenovo IdeaPad        | 131       | 5.31%   |
| Acer Aspire           | 99        | 4.01%   |
| HP Pavilion           | 81        | 3.28%   |
| HP EliteBook          | 80        | 3.24%   |
| HP ProBook            | 58        | 2.35%   |
| Toshiba Satellite     | 55        | 2.23%   |
| Lenovo Legion         | 46        | 1.87%   |
| ASUS VivoBook         | 34        | 1.38%   |
| Dell Precision        | 33        | 1.34%   |
| HP Laptop             | 30        | 1.22%   |
| Dell XPS              | 28        | 1.14%   |
| Dell Vostro           | 27        | 1.09%   |
| Unknown               | 23        | 0.93%   |
| HP Compaq             | 20        | 0.81%   |
| HP 250                | 18        | 0.73%   |
| Fujitsu LIFEBOOK      | 17        | 0.69%   |
| ASUS ASUS             | 17        | 0.69%   |
| ASUS TUF              | 16        | 0.65%   |
| ASUS ROG              | 15        | 0.61%   |
| Acer Extensa          | 15        | 0.61%   |
| HP ZBook              | 14        | 0.57%   |
| Packard Bell EasyNote | 12        | 0.49%   |
| Lenovo G50-30         | 12        | 0.49%   |
| Lenovo ThinkBook      | 11        | 0.45%   |
| Acer TravelMate       | 11        | 0.45%   |
| Acer Nitro            | 11        | 0.45%   |
| Lenovo Yoga           | 10        | 0.41%   |
| HP OMEN               | 10        | 0.41%   |
| Valve Jupiter         | 9         | 0.36%   |
| Lenovo G580           | 9         | 0.36%   |
| ASUS X555LJ           | 9         | 0.36%   |
| Acer Swift            | 9         | 0.36%   |
| Fujitsu Siemens AMILO | 8         | 0.32%   |
| Dell G3               | 8         | 0.32%   |
| ASUS Zenbook          | 8         | 0.32%   |
| Samsung 350V5C        | 7         | 0.28%   |
| HP 255                | 7         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 213       | 8.64%   |
| 2012    | 212       | 8.6%    |
| 2013    | 207       | 8.39%   |
| 2011    | 204       | 8.27%   |
| 2020    | 198       | 8.03%   |
| 2008    | 170       | 6.89%   |
| 2018    | 166       | 6.73%   |
| 2014    | 163       | 6.61%   |
| 2015    | 159       | 6.45%   |
| 2010    | 134       | 5.43%   |
| 2017    | 133       | 5.39%   |
| 2021    | 132       | 5.35%   |
| 2016    | 113       | 4.58%   |
| 2007    | 98        | 3.97%   |
| 2009    | 87        | 3.53%   |
| 2022    | 38        | 1.54%   |
| 2006    | 33        | 1.34%   |
| 2005    | 3         | 0.12%   |
| 2004    | 2         | 0.08%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2466      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2281      | 91.94%  |
| Enabled  | 200       | 8.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2453      | 99.47%  |
| Yes  | 13        | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 638       | 25.55%  |
| 4.01-8.0    | 592       | 23.71%  |
| 8.01-16.0   | 409       | 16.38%  |
| 16.01-24.0  | 390       | 15.62%  |
| 32.01-64.0  | 204       | 8.17%   |
| 1.01-2.0    | 115       | 4.61%   |
| 2.01-3.0    | 84        | 3.36%   |
| 24.01-32.0  | 26        | 1.04%   |
| 64.01-256.0 | 20        | 0.8%    |
| 0.51-1.0    | 19        | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1042      | 37.93%  |
| 2.01-3.0   | 612       | 22.28%  |
| 4.01-8.0   | 344       | 12.52%  |
| 3.01-4.0   | 340       | 12.38%  |
| 0.51-1.0   | 240       | 8.74%   |
| 8.01-16.0  | 119       | 4.33%   |
| 0.01-0.5   | 30        | 1.09%   |
| 16.01-24.0 | 14        | 0.51%   |
| 24.01-32.0 | 6         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1849      | 73.31%  |
| 2      | 559       | 22.16%  |
| 3      | 67        | 2.66%   |
| 0      | 36        | 1.43%   |
| 4      | 9         | 0.36%   |
| 5      | 2         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1436      | 57.65%  |
| Yes       | 1055      | 42.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2163      | 87.36%  |
| No        | 313       | 12.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2431      | 98.46%  |
| No        | 38        | 1.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1881      | 74.97%  |
| No        | 628       | 25.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 2466      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 580       | 21.83%  |
| Krakow                 | 216       | 8.13%   |
| Wroclaw                | 154       | 5.8%    |
| Poznan                 | 144       | 5.42%   |
| Lodz                   | 92        | 3.46%   |
| Gdansk                 | 84        | 3.16%   |
| Katowice               | 69        | 2.6%    |
| Lublin                 | 35        | 1.32%   |
| Szczecin               | 30        | 1.13%   |
| Gdynia                 | 30        | 1.13%   |
| Rzeszów               | 22        | 0.83%   |
| Ruda Śląska          | 22        | 0.83%   |
| Bialystok              | 21        | 0.79%   |
| Torun                  | 20        | 0.75%   |
| Częstochowa           | 20        | 0.75%   |
| Bydgoszcz              | 20        | 0.75%   |
| Gliwice                | 16        | 0.6%    |
| Elblag                 | 16        | 0.6%    |
| Bytom                  | 15        | 0.56%   |
| Olsztyn                | 14        | 0.53%   |
| Sosnowiec              | 13        | 0.49%   |
| Chorzów               | 13        | 0.49%   |
| Opole                  | 12        | 0.45%   |
| Kielce                 | 12        | 0.45%   |
| Tarnów                | 11        | 0.41%   |
| Płock                 | 11        | 0.41%   |
| Blizniew               | 11        | 0.41%   |
| Siemianowice Śląskie | 10        | 0.38%   |
| Pruszków              | 10        | 0.38%   |
| Zabrze                 | 9         | 0.34%   |
| Tychy                  | 9         | 0.34%   |
| Bielsko-Biala          | 8         | 0.3%    |
| Rybnik                 | 7         | 0.26%   |
| Gorzów Wielkopolski   | 7         | 0.26%   |
| Chojnice               | 7         | 0.26%   |
| Zielona Góra          | 6         | 0.23%   |
| Wejherowo              | 6         | 0.23%   |
| Stalowa Wola           | 6         | 0.23%   |
| Skierniewice           | 6         | 0.23%   |
| Skawina                | 6         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 432       | 566    | 14.18%  |
| Seagate             | 370       | 457    | 12.15%  |
| WDC                 | 346       | 424    | 11.36%  |
| Toshiba             | 203       | 255    | 6.66%   |
| GOODRAM             | 191       | 246    | 6.27%   |
| Unknown             | 143       | 182    | 4.69%   |
| SanDisk             | 129       | 162    | 4.24%   |
| Hitachi             | 118       | 141    | 3.87%   |
| Kingston            | 115       | 151    | 3.78%   |
| Intel               | 114       | 141    | 3.74%   |
| SK hynix            | 112       | 138    | 3.68%   |
| A-DATA Technology   | 107       | 126    | 3.51%   |
| Crucial             | 106       | 151    | 3.48%   |
| HGST                | 70        | 87     | 2.3%    |
| Micron Technology   | 61        | 78     | 2%      |
| KIOXIA              | 31        | 35     | 1.02%   |
| SPCC                | 29        | 35     | 0.95%   |
| Patriot             | 26        | 34     | 0.85%   |
| Plextor             | 25        | 36     | 0.82%   |
| PNY                 | 21        | 22     | 0.69%   |
| Fujitsu             | 19        | 20     | 0.62%   |
| LITEON              | 16        | 20     | 0.53%   |
| Phison              | 13        | 18     | 0.43%   |
| LITEONIT            | 13        | 14     | 0.43%   |
| KIOXIA-EXCERIA      | 12        | 13     | 0.39%   |
| Apacer              | 12        | 17     | 0.39%   |
| Transcend           | 11        | 12     | 0.36%   |
| China               | 11        | 14     | 0.36%   |
| Phison Electronics  | 9         | 9      | 0.3%    |
| Silicon Motion      | 8         | 10     | 0.26%   |
| JMicron Technology  | 8         | 8      | 0.26%   |
| OCZ                 | 7         | 7      | 0.23%   |
| Apple               | 7         | 9      | 0.23%   |
| Union Memory        | 6         | 9      | 0.2%    |
| Lenovo              | 6         | 8      | 0.2%    |
| HUAWEI              | 6         | 8      | 0.2%    |
| Lite-On             | 5         | 6      | 0.16%   |
| Unknown             | 5         | 6      | 0.16%   |
| XPG                 | 4         | 5      | 0.13%   |
| Solid State Storage | 4         | 4      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB        | 53        | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB         | 46        | 1.46%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 38        | 1.2%    |
| Intel NVMe SSD Drive 512GB             | 25        | 0.79%   |
| Seagate ST9500325AS 500GB              | 22        | 0.7%    |
| GOODRAM SSDPR-CX400-256-G2 256GB       | 22        | 0.7%    |
| GOODRAM SSD 120GB                      | 22        | 0.7%    |
| Crucial CT500MX500SSD1 500GB           | 22        | 0.7%    |
| Unknown MMC Card  32GB                 | 21        | 0.67%   |
| Toshiba MQ01ABD100 1TB                 | 21        | 0.67%   |
| Samsung NVMe SSD Drive 512GB           | 21        | 0.67%   |
| HGST HTS721010A9E630 1TB               | 19        | 0.6%    |
| Kingston SA400S37240G 240GB SSD        | 18        | 0.57%   |
| Unknown MMC Card  64GB                 | 17        | 0.54%   |
| SanDisk NVMe SSD Drive 512GB           | 17        | 0.54%   |
| Samsung SSD 850 EVO 250GB              | 17        | 0.54%   |
| Intel SSDPEKNW512G8H 512GB             | 17        | 0.54%   |
| Crucial CT1000MX500SSD1 1TB            | 17        | 0.54%   |
| Toshiba MQ01ABF050 500GB               | 15        | 0.48%   |
| Samsung SSD 860 EVO 500GB              | 15        | 0.48%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 15        | 0.48%   |
| GOODRAM SSD 240GB                      | 15        | 0.48%   |
| WDC WD10JPCX-24UE4T0 1TB               | 14        | 0.44%   |
| GOODRAM SSDPR-CX400-512 512GB          | 14        | 0.44%   |
| Seagate Expansion 240GB                | 13        | 0.41%   |
| HGST HTS725050A7E630 500GB             | 13        | 0.41%   |
| Crucial CT240BX500SSD1 240GB           | 13        | 0.41%   |
| SK hynix NVMe SSD Drive 512GB          | 12        | 0.38%   |
| HGST HTS545050A7E680 500GB             | 12        | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB               | 11        | 0.35%   |
| Toshiba NVMe SSD Drive 512GB           | 11        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 11        | 0.35%   |
| Seagate ST1000LM014-SSHD-8GB           | 11        | 0.35%   |
| Samsung SSD 860 EVO 250GB              | 11        | 0.35%   |
| Patriot Burst 120GB SSD                | 11        | 0.35%   |
| GOODRAM SSDPR-CX400-512-G2 512GB       | 11        | 0.35%   |
| GOODRAM SSDPR-CX400-256 256GB          | 11        | 0.35%   |
| SPCC Solid State Disk 512GB            | 10        | 0.32%   |
| Seagate ST9250315AS 250GB              | 10        | 0.32%   |
| SanDisk SDSSDA240G 240GB               | 10        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 368       | 453    | 36.95%  |
| WDC                 | 234       | 281    | 23.49%  |
| Toshiba             | 137       | 171    | 13.76%  |
| Hitachi             | 118       | 141    | 11.85%  |
| HGST                | 70        | 87     | 7.03%   |
| Samsung Electronics | 32        | 33     | 3.21%   |
| Fujitsu             | 19        | 20     | 1.91%   |
| Unknown             | 4         | 4      | 0.4%    |
| USB3.0              | 3         | 3      | 0.3%    |
| ASMT                | 3         | 3      | 0.3%    |
| ASMedia             | 3         | 3      | 0.3%    |
| StoreJet            | 1         | 1      | 0.1%    |
| SAGE                | 1         | 1      | 0.1%    |
| PHD 3.0             | 1         | 1      | 0.1%    |
| LaCie               | 1         | 2      | 0.1%    |
| IBM/Hitachi         | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 205       | 266    | 17.69%  |
| GOODRAM             | 189       | 244    | 16.31%  |
| Crucial             | 102       | 146    | 8.8%    |
| A-DATA Technology   | 89        | 106    | 7.68%   |
| Kingston            | 88        | 115    | 7.59%   |
| SanDisk             | 82        | 104    | 7.08%   |
| WDC                 | 49        | 54     | 4.23%   |
| Intel               | 34        | 39     | 2.93%   |
| SK hynix            | 32        | 40     | 2.76%   |
| Micron Technology   | 30        | 38     | 2.59%   |
| Toshiba             | 28        | 30     | 2.42%   |
| SPCC                | 27        | 33     | 2.33%   |
| Patriot             | 24        | 32     | 2.07%   |
| Plextor             | 22        | 33     | 1.9%    |
| LITEON              | 16        | 20     | 1.38%   |
| PNY                 | 15        | 16     | 1.29%   |
| LITEONIT            | 13        | 14     | 1.12%   |
| KIOXIA-EXCERIA      | 11        | 12     | 0.95%   |
| China               | 11        | 14     | 0.95%   |
| Transcend           | 10        | 11     | 0.86%   |
| Apacer              | 10        | 15     | 0.86%   |
| OCZ                 | 7         | 7      | 0.6%    |
| JMicron Technology  | 7         | 7      | 0.6%    |
| Apple               | 4         | 4      | 0.35%   |
| KingSpec            | 3         | 4      | 0.26%   |
| 2-Power             | 3         | 3      | 0.26%   |
| Union Memory        | 2         | 3      | 0.17%   |
| Team                | 2         | 2      | 0.17%   |
| Ramaxel Technology  | 2         | 2      | 0.17%   |
| Netac               | 2         | 3      | 0.17%   |
| Intenso             | 2         | 2      | 0.17%   |
| HS-SSD-C100         | 2         | 2      | 0.17%   |
| Gigabyte Technology | 2         | 3      | 0.17%   |
| Corsair             | 2         | 2      | 0.17%   |
| BIWIN               | 2         | 2      | 0.17%   |
| Unknown             | 2         | 2      | 0.17%   |
| Wolf                | 1         | 2      | 0.09%   |
| WDC WDS2            | 1         | 1      | 0.09%   |
| W800SH              | 1         | 1      | 0.09%   |
| Verbatim            | 1         | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1065      | 1459   | 36.94%  |
| HDD     | 960       | 1205   | 33.3%   |
| NVMe    | 697       | 940    | 24.18%  |
| MMC     | 130       | 165    | 4.51%   |
| Unknown | 31        | 39     | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1809      | 2590   | 66.31%  |
| NVMe | 697       | 939    | 25.55%  |
| MMC  | 130       | 165    | 4.77%   |
| SAS  | 92        | 114    | 3.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1484      | 2004   | 74.69%  |
| 0.51-1.0   | 467       | 617    | 23.5%   |
| 1.01-2.0   | 29        | 36     | 1.46%   |
| 4.01-10.0  | 4         | 4      | 0.2%    |
| 3.01-4.0   | 2         | 2      | 0.1%    |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 798       | 30.39%  |
| 251-500        | 590       | 22.47%  |
| 1-20           | 331       | 12.6%   |
| 501-1000       | 283       | 10.78%  |
| 51-100         | 232       | 8.83%   |
| 21-50          | 125       | 4.76%   |
| 1001-2000      | 117       | 4.46%   |
| Unknown        | 96        | 3.66%   |
| 2001-3000      | 30        | 1.14%   |
| More than 3000 | 24        | 0.91%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1185      | 43.73%  |
| 21-50          | 446       | 16.46%  |
| 101-250        | 354       | 13.06%  |
| 51-100         | 338       | 12.47%  |
| 251-500        | 147       | 5.42%   |
| 501-1000       | 96        | 3.54%   |
| Unknown        | 96        | 3.54%   |
| 1001-2000      | 37        | 1.37%   |
| 2001-3000      | 7         | 0.26%   |
| More than 3000 | 4         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 8         | 8      | 2.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 8         | 9      | 2.9%    |
| Seagate ST500LT012-9WS142 500GB                | 7         | 26     | 2.54%   |
| Seagate ST500LT012-1DG142 500GB                | 5         | 7      | 1.81%   |
| HGST HTS545050A7E680 500GB                     | 5         | 5      | 1.81%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 4         | 4      | 1.45%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 4         | 4      | 1.45%   |
| Hitachi HTS541612J9SA00 119GB                  | 4         | 5      | 1.45%   |
| WDC WD3200BPVT-80ZEST0 320GB                   | 3         | 3      | 1.09%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 1.09%   |
| Toshiba MK1246GSX 120GB                        | 3         | 3      | 1.09%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 3         | 3      | 1.09%   |
| Seagate ST9500420AS 500GB                      | 3         | 3      | 1.09%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 1.09%   |
| Seagate ST9250827AS 250GB                      | 3         | 3      | 1.09%   |
| Seagate ST9250410AS 250GB                      | 3         | 3      | 1.09%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 3         | 4      | 1.09%   |
| WDC WD1600BEVT-75A23T0 160GB                   | 2         | 2      | 0.72%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 2         | 2      | 0.72%   |
| Toshiba MK3265GSX 320GB                        | 2         | 2      | 0.72%   |
| Toshiba MK1637GSX 160GB                        | 2         | 2      | 0.72%   |
| Seagate ST980811AS 80GB                        | 2         | 2      | 0.72%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.72%   |
| Seagate ST9160821AS 160GB                      | 2         | 3      | 0.72%   |
| Seagate ST320LT020-9YG142 320GB                | 2         | 2      | 0.72%   |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 2      | 0.72%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD            | 2         | 2      | 0.72%   |
| Samsung Electronics HM250HI 250GB              | 2         | 2      | 0.72%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 2         | 2      | 0.72%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD          | 2         | 2      | 0.72%   |
| Kingston SV300S37A120G 120GB SSD               | 2         | 2      | 0.72%   |
| Hitachi HTS543232A7A384 320GB                  | 2         | 3      | 0.72%   |
| Hitachi HTS543225L9SA00 250GB                  | 2         | 2      | 0.72%   |
| Hitachi HTS543225L9A300 250GB                  | 2         | 2      | 0.72%   |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 0.72%   |
| Hitachi HTS542512K9SA00 120GB                  | 2         | 2      | 0.72%   |
| HGST HTS725050A7E630 500GB                     | 2         | 3      | 0.72%   |
| HGST HTS725032A7E630 320GB                     | 2         | 2      | 0.72%   |
| HGST HTS545050A7E380 500GB                     | 2         | 2      | 0.72%   |
| HGST HTS541010A9E680 1TB                       | 2         | 2      | 0.72%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 99     | 26.18%  |
| WDC                 | 37        | 38     | 13.45%  |
| Toshiba             | 34        | 44     | 12.36%  |
| Hitachi             | 30        | 34     | 10.91%  |
| Samsung Electronics | 16        | 17     | 5.82%   |
| A-DATA Technology   | 16        | 18     | 5.82%   |
| HGST                | 15        | 16     | 5.45%   |
| SK hynix            | 8         | 8      | 2.91%   |
| SanDisk             | 6         | 7      | 2.18%   |
| Intel               | 6         | 6      | 2.18%   |
| Micron Technology   | 4         | 4      | 1.45%   |
| Kingston            | 4         | 4      | 1.45%   |
| Fujitsu             | 4         | 4      | 1.45%   |
| Crucial             | 4         | 6      | 1.45%   |
| LITEONIT            | 3         | 3      | 1.09%   |
| LITEON              | 3         | 3      | 1.09%   |
| ASMedia             | 3         | 3      | 1.09%   |
| Patriot             | 2         | 4      | 0.73%   |
| OCZ                 | 2         | 2      | 0.73%   |
| SPCC                | 1         | 1      | 0.36%   |
| Plextor             | 1         | 1      | 0.36%   |
| Platinet            | 1         | 1      | 0.36%   |
| Lexar               | 1         | 1      | 0.36%   |
| Lenovo              | 1         | 1      | 0.36%   |
| Apacer              | 1         | 1      | 0.36%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 72        | 99     | 36.18%  |
| WDC                 | 35        | 36     | 17.59%  |
| Toshiba             | 31        | 41     | 15.58%  |
| Hitachi             | 30        | 34     | 15.08%  |
| HGST                | 15        | 16     | 7.54%   |
| Samsung Electronics | 9         | 9      | 4.52%   |
| Fujitsu             | 4         | 4      | 2.01%   |
| ASMedia             | 3         | 3      | 1.51%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 197       | 242    | 72.69%  |
| SSD  | 61        | 69     | 22.51%  |
| NVMe | 13        | 15     | 4.8%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB       | 1         | 1      | 20%     |
| WDC WD3200BEKT-75PVMT1 320GB    | 1         | 1      | 20%     |
| WDC WD2500BEVS-22UST0 250GB     | 1         | 1      | 20%     |
| Toshiba MK3265GSXN 320GB        | 1         | 1      | 20%     |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1250      | 1932   | 47.8%   |
| Works    | 1095      | 1545   | 41.87%  |
| Malfunc  | 265       | 326    | 10.13%  |
| Failed   | 5         | 5      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1922      | 67.2%   |
| AMD                              | 230       | 8.04%   |
| Samsung Electronics              | 210       | 7.34%   |
| SanDisk                          | 109       | 3.81%   |
| SK hynix                         | 80        | 2.8%    |
| Toshiba America Info Systems     | 42        | 1.47%   |
| Phison Electronics               | 35        | 1.22%   |
| KIOXIA                           | 33        | 1.15%   |
| Micron Technology                | 31        | 1.08%   |
| Kingston Technology Company      | 29        | 1.01%   |
| ADATA Technology                 | 22        | 0.77%   |
| Nvidia                           | 18        | 0.63%   |
| Silicon Motion                   | 15        | 0.52%   |
| Union Memory (Shenzhen)          | 12        | 0.42%   |
| Silicon Integrated Systems [SiS] | 11        | 0.38%   |
| Lite-On Technology               | 9         | 0.31%   |
| Realtek Semiconductor            | 8         | 0.28%   |
| Solid State Storage Technology   | 7         | 0.24%   |
| Micron/Crucial Technology        | 7         | 0.24%   |
| Lenovo                           | 6         | 0.21%   |
| VIA Technologies                 | 5         | 0.17%   |
| JMicron Technology               | 4         | 0.14%   |
| Shenzhen Longsys Electronics     | 3         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 3         | 0.1%    |
| Yangtze Memory Technologies      | 2         | 0.07%   |
| Apple                            | 2         | 0.07%   |
| Silicon Image                    | 1         | 0.03%   |
| O2 Micro                         | 1         | 0.03%   |
| Marvell Technology Group         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 211       | 6.68%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 188       | 5.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 166       | 5.26%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 149       | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 144       | 4.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 126       | 3.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 109       | 3.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 105       | 3.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 98        | 3.1%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 88        | 2.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 85        | 2.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 77        | 2.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 72        | 2.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 70        | 2.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 68        | 2.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 66        | 2.09%   |
| Samsung NVMe SSD Controller 980                                                | 65        | 2.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 60        | 1.9%    |
| Intel SSD 660P Series                                                          | 55        | 1.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 52        | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 36        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 36        | 1.14%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 34        | 1.08%   |
| Micron Non-Volatile memory controller                                          | 31        | 0.98%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 31        | 0.98%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 31        | 0.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 27        | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 25        | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 24        | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 23        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                          | 23        | 0.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 22        | 0.7%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 22        | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 21        | 0.67%   |
| SK hynix BC511                                                                 | 19        | 0.6%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 19        | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 18        | 0.57%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 18        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 18        | 0.57%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 18        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1774      | 59.07%  |
| NVMe | 706       | 23.51%  |
| IDE  | 293       | 9.76%   |
| RAID | 230       | 7.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2101      | 85.2%   |
| AMD          | 363       | 14.72%  |
| QUALCOMM     | 1         | 0.04%   |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 48        | 1.94%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 42        | 1.7%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 1.34%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 32        | 1.3%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 1.26%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 1.22%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 30        | 1.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 1.22%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1.18%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 1.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 26        | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 1.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 25        | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 25        | 1.01%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.97%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 24        | 0.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 22        | 0.89%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 21        | 0.85%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 21        | 0.85%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 20        | 0.81%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 20        | 0.81%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 20        | 0.81%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 20        | 0.81%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 20        | 0.81%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 19        | 0.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 19        | 0.77%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 18        | 0.73%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 18        | 0.73%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 17        | 0.69%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 17        | 0.69%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 17        | 0.69%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 17        | 0.69%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.65%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 16        | 0.65%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 16        | 0.65%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 15        | 0.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 0.61%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 15        | 0.61%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 14        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 692       | 28.05%  |
| Intel Core i7                  | 476       | 19.29%  |
| Intel Core 2 Duo               | 210       | 8.51%   |
| Intel Core i3                  | 208       | 8.43%   |
| Intel Celeron                  | 130       | 5.27%   |
| Other                          | 123       | 4.99%   |
| AMD Ryzen 5                    | 110       | 4.46%   |
| Intel Pentium                  | 79        | 3.2%    |
| AMD Ryzen 7                    | 79        | 3.2%    |
| Intel Atom                     | 51        | 2.07%   |
| Intel Pentium Dual-Core        | 36        | 1.46%   |
| AMD A6                         | 22        | 0.89%   |
| Intel Core 2                   | 20        | 0.81%   |
| Intel Pentium Dual             | 17        | 0.69%   |
| Intel Genuine                  | 15        | 0.61%   |
| AMD Ryzen 7 PRO                | 14        | 0.57%   |
| AMD A8                         | 14        | 0.57%   |
| Intel Celeron M                | 11        | 0.45%   |
| AMD E1                         | 11        | 0.45%   |
| AMD E                          | 11        | 0.45%   |
| AMD A4                         | 11        | 0.45%   |
| Intel Xeon                     | 9         | 0.36%   |
| AMD A10                        | 9         | 0.36%   |
| Intel Pentium M                | 8         | 0.32%   |
| AMD E2                         | 8         | 0.32%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.28%   |
| AMD Ryzen 9                    | 7         | 0.28%   |
| AMD Athlon X2                  | 7         | 0.28%   |
| Intel Core Duo                 | 5         | 0.2%    |
| AMD Ryzen 3                    | 5         | 0.2%    |
| AMD C-60                       | 5         | 0.2%    |
| Intel Core i9                  | 4         | 0.16%   |
| Intel Celeron Dual-Core        | 4         | 0.16%   |
| AMD Turion X2 Dual-Core Mobile | 4         | 0.16%   |
| AMD Phenom II                  | 4         | 0.16%   |
| AMD Athlon II                  | 4         | 0.16%   |
| AMD Ryzen 5 PRO                | 3         | 0.12%   |
| Intel Pentium Silver           | 2         | 0.08%   |
| Intel Core m5                  | 2         | 0.08%   |
| Intel Core m3                  | 2         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1396      | 56.56%  |
| 4       | 702       | 28.44%  |
| 6       | 156       | 6.32%   |
| 8       | 110       | 4.46%   |
| 1       | 64        | 2.59%   |
| Unknown | 21        | 0.85%   |
| 14      | 9         | 0.36%   |
| 12      | 4         | 0.16%   |
| 10      | 2         | 0.08%   |
| 3       | 2         | 0.08%   |
| 192     | 1         | 0.04%   |
| 5       | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2463      | 99.88%  |
| Unknown | 2         | 0.08%   |
| 2       | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1715      | 69.38%  |
| 1       | 735       | 29.73%  |
| Unknown | 21        | 0.85%   |
| 8       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2387      | 96.6%   |
| 32-bit         | 44        | 1.78%   |
| Unknown        | 39        | 1.58%   |
| 64-bit         | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 427       | 16.85%  |
| 0x206a7    | 183       | 7.22%   |
| 0x306a9    | 171       | 6.75%   |
| 0x1067a    | 104       | 4.1%    |
| 0x40651    | 94        | 3.71%   |
| 0x20655    | 84        | 3.31%   |
| 0x906ea    | 80        | 3.16%   |
| 0x306c3    | 76        | 3%      |
| 0x30678    | 76        | 3%      |
| 0x806ec    | 75        | 2.96%   |
| 0x306d4    | 73        | 2.88%   |
| 0x806c1    | 68        | 2.68%   |
| 0x806ea    | 67        | 2.64%   |
| 0x6fd      | 67        | 2.64%   |
| 0x406e3    | 67        | 2.64%   |
| 0x806e9    | 56        | 2.21%   |
| 0x10676    | 50        | 1.97%   |
| 0x506e3    | 48        | 1.89%   |
| 0x906e9    | 43        | 1.7%    |
| 0x0a50000c | 37        | 1.46%   |
| 0x20652    | 31        | 1.22%   |
| 0xa0652    | 28        | 1.1%    |
| 0x08600106 | 26        | 1.03%   |
| 0x806eb    | 23        | 0.91%   |
| 0x08108109 | 23        | 0.91%   |
| 0x08108102 | 23        | 0.91%   |
| 0x706e5    | 19        | 0.75%   |
| 0x6fb      | 18        | 0.71%   |
| 0x6f6      | 17        | 0.67%   |
| 0x906ed    | 16        | 0.63%   |
| 0x806d1    | 16        | 0.63%   |
| 0x106ca    | 16        | 0.63%   |
| 0x08600104 | 16        | 0.63%   |
| 0x08600103 | 16        | 0.63%   |
| 0x406c3    | 15        | 0.59%   |
| 0x06001119 | 15        | 0.59%   |
| 0x106c2    | 13        | 0.51%   |
| 0x05000119 | 13        | 0.51%   |
| 0x6e8      | 12        | 0.47%   |
| 0x406c4    | 12        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 429       | 17.38%  |
| Haswell          | 211       | 8.55%   |
| SandyBridge      | 208       | 8.43%   |
| IvyBridge        | 208       | 8.43%   |
| Penryn           | 172       | 6.97%   |
| Core             | 138       | 5.59%   |
| Skylake          | 137       | 5.55%   |
| Westmere         | 124       | 5.02%   |
| Silvermont       | 114       | 4.62%   |
| Broadwell        | 95        | 3.85%   |
| Zen 2            | 82        | 3.32%   |
| TigerLake        | 78        | 3.16%   |
| Zen+             | 58        | 2.35%   |
| Zen 3            | 45        | 1.82%   |
| IceLake          | 38        | 1.54%   |
| CometLake        | 36        | 1.46%   |
| Unknown          | 36        | 1.46%   |
| Bonnell          | 32        | 1.3%    |
| P6               | 29        | 1.18%   |
| Bobcat           | 29        | 1.18%   |
| Zen              | 19        | 0.77%   |
| Piledriver       | 19        | 0.77%   |
| Goldmont plus    | 16        | 0.65%   |
| K8 & K10 hybrid  | 14        | 0.57%   |
| Excavator        | 13        | 0.53%   |
| Puma             | 12        | 0.49%   |
| K8 Hammer        | 12        | 0.49%   |
| Jaguar           | 12        | 0.49%   |
| Alderlake Hybrid | 12        | 0.49%   |
| K10              | 11        | 0.45%   |
| Goldmont         | 10        | 0.41%   |
| K10 Llano        | 9         | 0.36%   |
| Nehalem          | 6         | 0.24%   |
| Steamroller      | 3         | 0.12%   |
| Tremont          | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1862      | 58.28%  |
| Nvidia                           | 770       | 24.1%   |
| AMD                              | 552       | 17.28%  |
| Silicon Integrated Systems [SiS] | 6         | 0.19%   |
| VIA Technologies                 | 5         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 200       | 5.98%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 192       | 5.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 115       | 3.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 100       | 2.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 94        | 2.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 85        | 2.54%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 85        | 2.54%   |
| Intel HD Graphics 5500                                                                   | 84        | 2.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 83        | 2.48%   |
| Intel UHD Graphics 620                                                                   | 80        | 2.39%   |
| AMD Renoir                                                                               | 77        | 2.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 74        | 2.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 73        | 2.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 69        | 2.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 69        | 2.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 68        | 2.03%   |
| Intel HD Graphics 620                                                                    | 64        | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 59        | 1.77%   |
| Intel HD Graphics 630                                                                    | 49        | 1.47%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 47        | 1.41%   |
| Intel HD Graphics 530                                                                    | 47        | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 41        | 1.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 1.17%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 37        | 1.11%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 1.11%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 31        | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 31        | 0.93%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 31        | 0.93%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 27        | 0.81%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 26        | 0.78%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 26        | 0.78%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 25        | 0.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 23        | 0.69%   |
| Nvidia GM108M [GeForce 840M]                                                             | 21        | 0.63%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 21        | 0.63%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 21        | 0.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 20        | 0.6%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 20        | 0.6%    |
| Nvidia TU117M                                                                            | 18        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1196      | 48.42%  |
| Intel + Nvidia           | 532       | 21.54%  |
| 1 x AMD                  | 317       | 12.83%  |
| 1 x Nvidia               | 174       | 7.04%   |
| Intel + AMD              | 131       | 5.3%    |
| AMD + Nvidia             | 63        | 2.55%   |
| 2 x AMD                  | 39        | 1.58%   |
| 1 x SiS                  | 6         | 0.24%   |
| 1 x VIA                  | 5         | 0.2%    |
| 2 x Intel                | 3         | 0.12%   |
| Other                    | 2         | 0.08%   |
| 2 x Nvidia               | 1         | 0.04%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2082      | 83.38%  |
| Proprietary | 348       | 13.94%  |
| Unknown     | 67        | 2.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1472      | 58.2%   |
| 1.01-2.0   | 352       | 13.92%  |
| 0.01-0.5   | 329       | 13.01%  |
| 3.01-4.0   | 156       | 6.17%   |
| 0.51-1.0   | 155       | 6.13%   |
| 5.01-6.0   | 44        | 1.74%   |
| 7.01-8.0   | 15        | 0.59%   |
| 2.01-3.0   | 4         | 0.16%   |
| 8.01-16.0  | 2         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 523       | 18.37%  |
| LG Display              | 451       | 15.84%  |
| Samsung Electronics     | 358       | 12.57%  |
| BOE                     | 325       | 11.42%  |
| Chimei Innolux          | 304       | 10.68%  |
| Dell                    | 104       | 3.65%   |
| Chi Mei Optoelectronics | 101       | 3.55%   |
| Lenovo                  | 90        | 3.16%   |
| Goldstar                | 55        | 1.93%   |
| Iiyama                  | 52        | 1.83%   |
| Sharp                   | 41        | 1.44%   |
| LG Philips              | 40        | 1.4%    |
| PANDA                   | 30        | 1.05%   |
| Philips                 | 27        | 0.95%   |
| BenQ                    | 25        | 0.88%   |
| AOC                     | 22        | 0.77%   |
| Acer                    | 21        | 0.74%   |
| NEC Computers           | 20        | 0.7%    |
| Hewlett-Packard         | 20        | 0.7%    |
| InfoVision              | 19        | 0.67%   |
| Ancor Communications    | 16        | 0.56%   |
| HannStar                | 15        | 0.53%   |
| CPT                     | 14        | 0.49%   |
| Apple                   | 14        | 0.49%   |
| Eizo                    | 11        | 0.39%   |
| LGD                     | 9         | 0.32%   |
| Toshiba                 | 8         | 0.28%   |
| CSO                     | 8         | 0.28%   |
| ASUSTek Computer        | 8         | 0.28%   |
| Seiko/Epson             | 7         | 0.25%   |
| Panasonic               | 6         | 0.21%   |
| Mi                      | 6         | 0.21%   |
| Fujitsu Siemens         | 6         | 0.21%   |
| Sony                    | 5         | 0.18%   |
| MSI                     | 5         | 0.18%   |
| InnoLux Display         | 5         | 0.18%   |
| Vestel Elektronik       | 4         | 0.14%   |
| TMX                     | 4         | 0.14%   |
| LPL                     | 4         | 0.14%   |
| IBM                     | 4         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 1.07%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 29        | 1%      |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 28        | 0.96%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 22        | 0.76%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 21        | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 20        | 0.69%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 19        | 0.65%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 19        | 0.65%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 15        | 0.52%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 15        | 0.52%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 15        | 0.52%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 15        | 0.52%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 13        | 0.45%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.45%   |
| LG Display LCD Monitor LGD0469 1920x1080 380x210mm 17.1-inch             | 12        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 12        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.41%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 12        | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 12        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 11        | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.38%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 11        | 0.38%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 11        | 0.38%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 11        | 0.38%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 10        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 10        | 0.34%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 10        | 0.34%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.34%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 9         | 0.31%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 9         | 0.31%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 340x190mm 15.3-inch    | 9         | 0.31%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 9         | 0.31%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 9         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 9         | 0.31%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 8         | 0.28%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 8         | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1073      | 40.57%  |
| 1366x768 (WXGA)    | 713       | 26.96%  |
| 1600x900 (HD+)     | 187       | 7.07%   |
| 1280x800 (WXGA)    | 171       | 6.47%   |
| 3840x2160 (4K)     | 81        | 3.06%   |
| 2560x1440 (QHD)    | 75        | 2.84%   |
| 1920x1200 (WUXGA)  | 63        | 2.38%   |
| 1440x900 (WXGA+)   | 61        | 2.31%   |
| 1680x1050 (WSXGA+) | 48        | 1.81%   |
| 1024x600           | 26        | 0.98%   |
| 1280x1024 (SXGA)   | 20        | 0.76%   |
| 2560x1600          | 17        | 0.64%   |
| 3440x1440          | 15        | 0.57%   |
| 2560x1080          | 11        | 0.42%   |
| 800x1280           | 9         | 0.34%   |
| 2160x1440          | 8         | 0.3%    |
| 1024x768 (XGA)     | 7         | 0.26%   |
| Unknown            | 7         | 0.26%   |
| 3840x2400          | 6         | 0.23%   |
| 2880x1800          | 5         | 0.19%   |
| 3200x1800 (QHD+)   | 4         | 0.15%   |
| 1680x945           | 4         | 0.15%   |
| 3840x1080          | 3         | 0.11%   |
| 3286x1080          | 3         | 0.11%   |
| 1400x1050          | 3         | 0.11%   |
| 3840x1600          | 2         | 0.08%   |
| 3456x2160          | 2         | 0.08%   |
| 3000x2000          | 2         | 0.08%   |
| 2288x1287          | 2         | 0.08%   |
| 2256x1504          | 2         | 0.08%   |
| 1280x768           | 2         | 0.08%   |
| 1280x720 (HD)      | 2         | 0.08%   |
| 6400x1600          | 1         | 0.04%   |
| 3300x2200          | 1         | 0.04%   |
| 3200x2000          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2240x1400          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |
| 1920x540           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1236      | 43.26%  |
| 13      | 323       | 11.31%  |
| 14      | 316       | 11.06%  |
| 17      | 221       | 7.74%   |
| 24      | 119       | 4.17%   |
| 23      | 96        | 3.36%   |
| 12      | 88        | 3.08%   |
| 27      | 82        | 2.87%   |
| Unknown | 61        | 2.14%   |
| 21      | 56        | 1.96%   |
| 11      | 33        | 1.16%   |
| 34      | 27        | 0.95%   |
| 10      | 27        | 0.95%   |
| 19      | 23        | 0.81%   |
| 22      | 22        | 0.77%   |
| 16      | 21        | 0.74%   |
| 31      | 17        | 0.6%    |
| 18      | 17        | 0.6%    |
| 48      | 10        | 0.35%   |
| 25      | 9         | 0.32%   |
| 20      | 9         | 0.32%   |
| 84      | 8         | 0.28%   |
| 40      | 5         | 0.18%   |
| 72      | 4         | 0.14%   |
| 32      | 4         | 0.14%   |
| 43      | 3         | 0.11%   |
| 37      | 3         | 0.11%   |
| 54      | 2         | 0.07%   |
| 28      | 2         | 0.07%   |
| 26      | 2         | 0.07%   |
| 7       | 2         | 0.07%   |
| 142     | 1         | 0.04%   |
| 65      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 49      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 35      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 29      | 1         | 0.04%   |
| 3       | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1707      | 60.7%   |
| 351-400        | 278       | 9.89%   |
| 501-600        | 275       | 9.78%   |
| 201-300        | 275       | 9.78%   |
| 401-500        | 114       | 4.05%   |
| Unknown        | 61        | 2.17%   |
| 701-800        | 32        | 1.14%   |
| 601-700        | 26        | 0.92%   |
| 1001-1500      | 16        | 0.57%   |
| 1501-2000      | 12        | 0.43%   |
| 801-900        | 9         | 0.32%   |
| 901-1000       | 3         | 0.11%   |
| 1-100          | 3         | 0.11%   |
| More than 2000 | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1995      | 79.64%  |
| 16/10   | 357       | 14.25%  |
| Unknown | 44        | 1.76%   |
| 21/9    | 30        | 1.2%    |
| 3/2     | 29        | 1.16%   |
| 5/4     | 21        | 0.84%   |
| 4/3     | 15        | 0.6%    |
| 0.62    | 7         | 0.28%   |
| 32/9    | 3         | 0.12%   |
| 0.67    | 2         | 0.08%   |
| 6/5     | 1         | 0.04%   |
| 1.00    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1234      | 43.45%  |
| 81-90          | 528       | 18.59%  |
| 201-250        | 219       | 7.71%   |
| 121-130        | 174       | 6.13%   |
| 71-80          | 104       | 3.66%   |
| 61-70          | 87        | 3.06%   |
| 301-350        | 84        | 2.96%   |
| 251-300        | 62        | 2.18%   |
| Unknown        | 61        | 2.15%   |
| 351-500        | 50        | 1.76%   |
| 131-140        | 42        | 1.48%   |
| 151-200        | 39        | 1.37%   |
| 51-60          | 33        | 1.16%   |
| 41-50          | 27        | 0.95%   |
| More than 1000 | 26        | 0.92%   |
| 141-150        | 25        | 0.88%   |
| 91-100         | 16        | 0.56%   |
| 501-1000       | 14        | 0.49%   |
| 111-120        | 12        | 0.42%   |
| 1-40           | 3         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1140      | 40.92%  |
| 101-120       | 816       | 29.29%  |
| 51-100        | 578       | 20.75%  |
| 161-240       | 115       | 4.13%   |
| Unknown       | 61        | 2.19%   |
| More than 240 | 55        | 1.97%   |
| 1-50          | 21        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2004      | 79.02%  |
| 2     | 408       | 16.09%  |
| 3     | 61        | 2.41%   |
| 0     | 54        | 2.13%   |
| 4     | 7         | 0.28%   |
| 6     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1445      | 35.46%  |
| Realtek Semiconductor             | 1139      | 27.95%  |
| Qualcomm Atheros                  | 620       | 15.21%  |
| Broadcom                          | 280       | 6.87%   |
| Broadcom Limited                  | 84        | 2.06%   |
| Dell                              | 66        | 1.62%   |
| Marvell Technology Group          | 61        | 1.5%    |
| Huawei Technologies               | 58        | 1.42%   |
| MediaTek                          | 36        | 0.88%   |
| Ralink                            | 32        | 0.79%   |
| Ericsson Business Mobile Networks | 25        | 0.61%   |
| TP-Link                           | 22        | 0.54%   |
| Hewlett-Packard                   | 21        | 0.52%   |
| Samsung Electronics               | 20        | 0.49%   |
| Xiaomi                            | 15        | 0.37%   |
| Sierra Wireless                   | 15        | 0.37%   |
| JMicron Technology                | 15        | 0.37%   |
| Lenovo                            | 12        | 0.29%   |
| Ralink Technology                 | 10        | 0.25%   |
| Nvidia                            | 10        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 9         | 0.22%   |
| Qualcomm Atheros Communications   | 8         | 0.2%    |
| Fibocom                           | 8         | 0.2%    |
| DisplayLink                       | 8         | 0.2%    |
| ASIX Electronics                  | 8         | 0.2%    |
| Qualcomm                          | 6         | 0.15%   |
| Motorola PCS                      | 5         | 0.12%   |
| ASUSTek Computer                  | 5         | 0.12%   |
| VIA Technologies                  | 4         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 3         | 0.07%   |
| Attansic Technology               | 3         | 0.07%   |
| NetGear                           | 2         | 0.05%   |
| Microsoft                         | 2         | 0.05%   |
| HTC (High Tech Computer)          | 2         | 0.05%   |
| Toshiba                           | 1         | 0.02%   |
| Tenda                             | 1         | 0.02%   |
| Sigma Designs                     | 1         | 0.02%   |
| Shenzhen Goodix Technology        | 1         | 0.02%   |
| Sagem                             | 1         | 0.02%   |
| QinHeng Electronics               | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 748       | 15.14%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 214       | 4.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 146       | 2.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 107       | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 106       | 2.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 105       | 2.13%   |
| Intel Wireless 8265 / 8275                                              | 102       | 2.07%   |
| Intel Wi-Fi 6 AX200                                                     | 97        | 1.96%   |
| Intel Wireless 7260                                                     | 92        | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 78        | 1.58%   |
| Intel Wireless 8260                                                     | 77        | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 74        | 1.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 70        | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 70        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 69        | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 62        | 1.26%   |
| Intel Wi-Fi 6 AX201                                                     | 61        | 1.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 60        | 1.21%   |
| Intel Wireless 7265                                                     | 59        | 1.19%   |
| Intel Wireless 3160                                                     | 54        | 1.09%   |
| Intel 82567LM Gigabit Network Connection                                | 49        | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 45        | 0.91%   |
| Intel Wireless 3165                                                     | 45        | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 45        | 0.91%   |
| Intel Centrino Ultimate-N 6300                                          | 44        | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 43        | 0.87%   |
| Intel Ethernet Connection I218-LM                                       | 42        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 0.83%   |
| Intel WiFi Link 5100                                                    | 41        | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 39        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                                | 39        | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                           | 39        | 0.79%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 37        | 0.75%   |
| Huawei E353/E3131                                                       | 37        | 0.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 36        | 0.73%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 0.65%   |
| Intel Ethernet Connection I217-LM                                       | 32        | 0.65%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 32        | 0.65%   |
| Intel Centrino Advanced-N 6200                                          | 32        | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 30        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1372      | 53.08%  |
| Qualcomm Atheros                  | 517       | 20%     |
| Realtek Semiconductor             | 263       | 10.17%  |
| Broadcom                          | 190       | 7.35%   |
| Broadcom Limited                  | 47        | 1.82%   |
| Dell                              | 40        | 1.55%   |
| MediaTek                          | 34        | 1.32%   |
| Ralink                            | 32        | 1.24%   |
| TP-Link                           | 18        | 0.7%    |
| Sierra Wireless                   | 15        | 0.58%   |
| Ralink Technology                 | 10        | 0.39%   |
| Qualcomm Atheros Communications   | 8         | 0.31%   |
| Fibocom                           | 8         | 0.31%   |
| Ericsson Business Mobile Networks | 8         | 0.31%   |
| Hewlett-Packard                   | 5         | 0.19%   |
| ASUSTek Computer                  | 5         | 0.19%   |
| Qualcomm                          | 4         | 0.15%   |
| NetGear                           | 2         | 0.08%   |
| Microsoft                         | 2         | 0.08%   |
| Tenda                             | 1         | 0.04%   |
| Sagem                             | 1         | 0.04%   |
| Linksys                           | 1         | 0.04%   |
| Edimax Technology                 | 1         | 0.04%   |
| Belkin Components                 | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 107       | 4.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 106       | 4.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 105       | 4.06%   |
| Intel Wireless 8265 / 8275                                              | 102       | 3.94%   |
| Intel Wi-Fi 6 AX200                                                     | 97        | 3.75%   |
| Intel Wireless 7260                                                     | 92        | 3.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 78        | 3.01%   |
| Intel Wireless 8260                                                     | 77        | 2.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 74        | 2.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 70        | 2.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 70        | 2.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 69        | 2.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 62        | 2.4%    |
| Intel Wi-Fi 6 AX201                                                     | 61        | 2.36%   |
| Intel Wireless 7265                                                     | 59        | 2.28%   |
| Intel Wireless 3160                                                     | 54        | 2.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 45        | 1.74%   |
| Intel Wireless 3165                                                     | 45        | 1.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 45        | 1.74%   |
| Intel Centrino Ultimate-N 6300                                          | 44        | 1.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 43        | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 1.58%   |
| Intel WiFi Link 5100                                                    | 41        | 1.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 39        | 1.51%   |
| Broadcom BCM43142 802.11b/g/n                                           | 39        | 1.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 37        | 1.43%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 36        | 1.39%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 32        | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 32        | 1.24%   |
| Intel Centrino Advanced-N 6200                                          | 32        | 1.24%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 29        | 1.12%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 28        | 1.08%   |
| Intel Centrino Advanced-N 6235                                          | 28        | 1.08%   |
| Intel Centrino Wireless-N 2230                                          | 26        | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 25        | 0.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 24        | 0.93%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 19        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 18        | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 17        | 0.66%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 17        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1043      | 46.36%  |
| Intel                            | 635       | 28.22%  |
| Qualcomm Atheros                 | 182       | 8.09%   |
| Broadcom                         | 122       | 5.42%   |
| Marvell Technology Group         | 61        | 2.71%   |
| Huawei Technologies              | 42        | 1.87%   |
| Broadcom Limited                 | 38        | 1.69%   |
| Samsung Electronics              | 19        | 0.84%   |
| JMicron Technology               | 15        | 0.67%   |
| Xiaomi                           | 14        | 0.62%   |
| Lenovo                           | 12        | 0.53%   |
| Nvidia                           | 10        | 0.44%   |
| Silicon Integrated Systems [SiS] | 9         | 0.4%    |
| DisplayLink                      | 8         | 0.36%   |
| ASIX Electronics                 | 8         | 0.36%   |
| Motorola PCS                     | 5         | 0.22%   |
| VIA Technologies                 | 4         | 0.18%   |
| TP-Link                          | 4         | 0.18%   |
| Hewlett-Packard                  | 3         | 0.13%   |
| Attansic Technology              | 3         | 0.13%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.09%   |
| Qualcomm                         | 2         | 0.09%   |
| HTC (High Tech Computer)         | 2         | 0.09%   |
| QinHeng Electronics              | 1         | 0.04%   |
| OPPO Electronics                 | 1         | 0.04%   |
| MediaTek                         | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 748       | 33.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 214       | 9.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 146       | 6.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 60        | 2.65%   |
| Intel 82567LM Gigabit Network Connection                          | 49        | 2.17%   |
| Intel Ethernet Connection I218-LM                                 | 42        | 1.86%   |
| Intel 82577LM Gigabit Network Connection                          | 39        | 1.72%   |
| Huawei E353/E3131                                                 | 37        | 1.64%   |
| Intel Ethernet Connection I217-LM                                 | 32        | 1.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 30        | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 29        | 1.28%   |
| Intel Ethernet Connection (6) I219-V                              | 28        | 1.24%   |
| Intel Ethernet Connection (3) I218-LM                             | 27        | 1.19%   |
| Intel Ethernet Connection I219-LM                                 | 25        | 1.11%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 1.06%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 21        | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 21        | 0.93%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 21        | 0.93%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.75%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 16        | 0.71%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 16        | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 16        | 0.71%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 15        | 0.66%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.62%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 14        | 0.62%   |
| Intel Ethernet Connection (5) I219-LM                             | 14        | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 13        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 13        | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 13        | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 13        | 0.57%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.53%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 12        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 11        | 0.49%   |
| Intel 82566MM Gigabit Network Connection                          | 11        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 10        | 0.44%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.44%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 10        | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2431      | 51.94%  |
| Ethernet | 2160      | 46.15%  |
| Modem    | 84        | 1.79%   |
| Unknown  | 5         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1997      | 77.73%  |
| Ethernet | 572       | 22.27%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2025      | 82.02%  |
| 1     | 409       | 16.57%  |
| 0     | 27        | 1.09%   |
| 3     | 8         | 0.32%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2318      | 93.17%  |
| Yes  | 170       | 6.83%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 888       | 46.84%  |
| Qualcomm Atheros Communications | 214       | 11.29%  |
| Broadcom                        | 155       | 8.18%   |
| Realtek Semiconductor           | 129       | 6.8%    |
| IMC Networks                    | 95        | 5.01%   |
| Dell                            | 81        | 4.27%   |
| Hewlett-Packard                 | 59        | 3.11%   |
| Foxconn / Hon Hai               | 59        | 3.11%   |
| Lite-On Technology              | 54        | 2.85%   |
| ASUSTek Computer                | 25        | 1.32%   |
| Toshiba                         | 24        | 1.27%   |
| Cambridge Silicon Radio         | 23        | 1.21%   |
| Ralink                          | 17        | 0.9%    |
| Foxconn International           | 14        | 0.74%   |
| Apple                           | 14        | 0.74%   |
| Realtek                         | 10        | 0.53%   |
| Chicony Electronics             | 6         | 0.32%   |
| Taiyo Yuden                     | 5         | 0.26%   |
| Alps Electric                   | 5         | 0.26%   |
| Ralink Technology               | 3         | 0.16%   |
| MediaTek                        | 3         | 0.16%   |
| Integrated System Solution      | 3         | 0.16%   |
| Micro Star International        | 2         | 0.11%   |
| USI                             | 1         | 0.05%   |
| TP-Link                         | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 420       | 22.15%  |
| Intel Bluetooth Device                              | 142       | 7.49%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 122       | 6.43%   |
| Qualcomm Atheros  Bluetooth Device                  | 95        | 5.01%   |
| Intel AX200 Bluetooth                               | 91        | 4.8%    |
| Realtek Bluetooth Radio                             | 79        | 4.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 51        | 2.69%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 51        | 2.69%   |
| IMC Networks Bluetooth Radio                        | 37        | 1.95%   |
| Broadcom BCM2045B (BDC-2.1)                         | 37        | 1.95%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 34        | 1.79%   |
| Realtek  Bluetooth 4.2 Adapter                      | 29        | 1.53%   |
| Lite-On Bluetooth Device                            | 28        | 1.48%   |
| Dell BCM20702A0 Bluetooth Module                    | 26        | 1.37%   |
| Intel Wireless-AC 3168 Bluetooth                    | 25        | 1.32%   |
| HP Broadcom 2070 Bluetooth Combo                    | 23        | 1.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23        | 1.21%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 22        | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 22        | 1.16%   |
| Dell DW375 Bluetooth Module                         | 21        | 1.11%   |
| IMC Networks Bluetooth Device                       | 19        | 1%      |
| Ralink RT3290 Bluetooth                             | 17        | 0.9%    |
| Broadcom BCM2070 Bluetooth Device                   | 17        | 0.9%    |
| Realtek RTL8723B Bluetooth                          | 16        | 0.84%   |
| IMC Networks Wireless_Device                        | 16        | 0.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 14        | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.74%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.69%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.63%   |
| Broadcom HP Portable SoftSailing                    | 12        | 0.63%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.58%   |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 0.58%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 0.58%   |
| Dell Wireless 370 Bluetooth Mini-card               | 11        | 0.58%   |
| Dell Wireless 360 Bluetooth                         | 11        | 0.58%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 11        | 0.58%   |
| Realtek Bluetooth Radio                             | 10        | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 0.53%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2058      | 68.24%  |
| AMD                                          | 416       | 13.79%  |
| Nvidia                                       | 376       | 12.47%  |
| C-Media Electronics                          | 16        | 0.53%   |
| Creative Technology                          | 15        | 0.5%    |
| Realtek Semiconductor                        | 13        | 0.43%   |
| Lenovo                                       | 13        | 0.43%   |
| Silicon Integrated Systems [SiS]             | 11        | 0.36%   |
| Plantronics                                  | 11        | 0.36%   |
| Logitech                                     | 10        | 0.33%   |
| GN Netcom                                    | 8         | 0.27%   |
| SteelSeries ApS                              | 6         | 0.2%    |
| VIA Technologies                             | 5         | 0.17%   |
| Texas Instruments                            | 5         | 0.17%   |
| Dell                                         | 5         | 0.17%   |
| Hewlett-Packard                              | 4         | 0.13%   |
| Focusrite-Novation                           | 4         | 0.13%   |
| Samson Technologies                          | 3         | 0.1%    |
| JMTek                                        | 3         | 0.1%    |
| Sennheiser Communications                    | 2         | 0.07%   |
| Kingston Technology                          | 2         | 0.07%   |
| Generalplus Technology                       | 2         | 0.07%   |
| DSEA A/S                                     | 2         | 0.07%   |
| BEHRINGER International                      | 2         | 0.07%   |
| AudioQuest                                   | 2         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Yamaha                                       | 1         | 0.03%   |
| TTGK Technology                              | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Silicon Motion                               | 1         | 0.03%   |
| SAVITECH                                     | 1         | 0.03%   |
| Razer USA                                    | 1         | 0.03%   |
| Native Instruments                           | 1         | 0.03%   |
| MCS                                          | 1         | 0.03%   |
| Mark of the Unicorn                          | 1         | 0.03%   |
| M-Audio                                      | 1         | 0.03%   |
| KTMicro                                      | 1         | 0.03%   |
| Jieli Technology                             | 1         | 0.03%   |
| GYROCOM C&C                                  | 1         | 0.03%   |
| FiiO Electronics Technology                  | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 247       | 6.87%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 233       | 6.48%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 213       | 5.92%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 168       | 4.67%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 162       | 4.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 130       | 3.61%   |
| Intel 8 Series HD Audio Controller                                                                | 119       | 3.31%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 117       | 3.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 115       | 3.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 106       | 2.95%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 96        | 2.67%   |
| Intel Broadwell-U Audio Controller                                                                | 95        | 2.64%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 94        | 2.61%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 93        | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 83        | 2.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 78        | 2.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 74        | 2.06%   |
| AMD FCH Azalia Controller                                                                         | 70        | 1.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 69        | 1.92%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 69        | 1.92%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 66        | 1.83%   |
| Intel CM238 HD Audio Controller                                                                   | 55        | 1.53%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 53        | 1.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 52        | 1.45%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 47        | 1.31%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 43        | 1.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 40        | 1.11%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 39        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 34        | 0.95%   |
| AMD Wrestler HDMI Audio                                                                           | 27        | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 27        | 0.75%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 23        | 0.64%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 23        | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 23        | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 22        | 0.61%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 20        | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 20        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 19        | 0.53%   |
| AMD Trinity HDMI Audio Controller                                                                 | 19        | 0.53%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 18        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 540       | 28.1%   |
| SK hynix                     | 404       | 21.02%  |
| Micron Technology            | 205       | 10.67%  |
| Kingston                     | 205       | 10.67%  |
| Unknown                      | 146       | 7.6%    |
| GOODRAM                      | 90        | 4.68%   |
| Crucial                      | 76        | 3.95%   |
| Ramaxel Technology           | 47        | 2.45%   |
| A-DATA Technology            | 45        | 2.34%   |
| Nanya Technology             | 36        | 1.87%   |
| Elpida                       | 31        | 1.61%   |
| Patriot                      | 15        | 0.78%   |
| Unknown                      | 12        | 0.62%   |
| Qimonda                      | 10        | 0.52%   |
| Wilk                         | 9         | 0.47%   |
| Unknown (ABCD)               | 7         | 0.36%   |
| Corsair                      | 7         | 0.36%   |
| ASint Technology             | 7         | 0.36%   |
| G.Skill                      | 5         | 0.26%   |
| Unifosa                      | 3         | 0.16%   |
| Apacer                       | 3         | 0.16%   |
| 48spaces                     | 3         | 0.16%   |
| Toshiba                      | 2         | 0.1%    |
| SHARETRONIC                  | 2         | 0.1%    |
| Unknown (8A02)               | 1         | 0.05%   |
| Unknown (768A)               | 1         | 0.05%   |
| Transcend                    | 1         | 0.05%   |
| Swissbit                     | 1         | 0.05%   |
| Smart                        | 1         | 0.05%   |
| PNY                          | 1         | 0.05%   |
| Patriot Memory (PDP Systems) | 1         | 0.05%   |
| Goldkey                      | 1         | 0.05%   |
| fef5                         | 1         | 0.05%   |
| ChangXin Memory              | 1         | 0.05%   |
| 430112204340C940             | 1         | 0.05%   |
| 430112174392063E             | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s      | 36        | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                 | 26        | 1.26%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s      | 25        | 1.22%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s  | 24        | 1.17%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s  | 22        | 1.07%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 21        | 1.02%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s    | 21        | 1.02%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 20        | 0.97%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 20        | 0.97%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s      | 20        | 0.97%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 20        | 0.97%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 18        | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 17        | 0.83%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s     | 17        | 0.83%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 16        | 0.78%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s       | 15        | 0.73%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s      | 15        | 0.73%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s      | 15        | 0.73%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s    | 15        | 0.73%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 14        | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 14        | 0.68%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s     | 13        | 0.63%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 13        | 0.63%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s      | 13        | 0.63%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 12        | 0.58%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM 1067MT/s           | 12        | 0.58%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 12        | 0.58%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s    | 12        | 0.58%   |
| Unknown                                                    | 12        | 0.58%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 11        | 0.54%   |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s      | 11        | 0.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 11        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 11        | 0.54%   |
| Crucial RAM CT102464BF160B.C16 8192MB SODIMM DDR3 1600MT/s | 11        | 0.54%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s  | 10        | 0.49%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s      | 10        | 0.49%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM SDRAM 2048MT/s    | 10        | 0.49%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s    | 10        | 0.49%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                 | 9         | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s     | 9         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 621       | 39.4%   |
| DDR4    | 614       | 38.96%  |
| DDR2    | 150       | 9.52%   |
| SDRAM   | 71        | 4.51%   |
| LPDDR4  | 47        | 2.98%   |
| LPDDR3  | 35        | 2.22%   |
| Unknown | 11        | 0.7%    |
| DDR     | 10        | 0.63%   |
| DDR5    | 9         | 0.57%   |
| DRAM    | 5         | 0.32%   |
| LPDDR5  | 3         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1446      | 93.47%  |
| Row Of Chips | 76        | 4.91%   |
| Chip         | 11        | 0.71%   |
| DIMM         | 7         | 0.45%   |
| Unknown      | 7         | 0.45%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 531       | 30.76%  |
| 8192    | 517       | 29.95%  |
| 2048    | 287       | 16.63%  |
| 16384   | 249       | 14.43%  |
| 1024    | 100       | 5.79%   |
| 32768   | 27        | 1.56%   |
| 512     | 9         | 0.52%   |
| Unknown | 4         | 0.23%   |
| 1536    | 1         | 0.06%   |
| 256     | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 445       | 25.72%  |
| 2667    | 314       | 18.15%  |
| 3200    | 225       | 13.01%  |
| 1334    | 113       | 6.53%   |
| 2400    | 97        | 5.61%   |
| 2133    | 77        | 4.45%   |
| 667     | 76        | 4.39%   |
| 1333    | 65        | 3.76%   |
| Unknown | 50        | 2.89%   |
| 4199    | 40        | 2.31%   |
| 1067    | 36        | 2.08%   |
| 800     | 29        | 1.68%   |
| 975     | 25        | 1.45%   |
| 2048    | 24        | 1.39%   |
| 533     | 22        | 1.27%   |
| 4267    | 14        | 0.81%   |
| 1867    | 14        | 0.81%   |
| 3266    | 11        | 0.64%   |
| 8400    | 10        | 0.58%   |
| 4800    | 10        | 0.58%   |
| 1066    | 8         | 0.46%   |
| 4266    | 5         | 0.29%   |
| 3733    | 4         | 0.23%   |
| 400     | 4         | 0.23%   |
| 333     | 4         | 0.23%   |
| 6400    | 3         | 0.17%   |
| 2933    | 1         | 0.06%   |
| 2134    | 1         | 0.06%   |
| 1776    | 1         | 0.06%   |
| 1639    | 1         | 0.06%   |
| 933     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 10        | 45.45%  |
| Samsung Electronics | 4         | 18.18%  |
| Canon               | 3         | 13.64%  |
| Seiko Epson         | 2         | 9.09%   |
| Zebra               | 1         | 4.55%   |
| Xerox               | 1         | 4.55%   |
| Brother Industries  | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Deskjet F2280 series                 | 2         | 9.09%   |
| Zebra ZTC GX420t                        | 1         | 4.55%   |
| Xerox Phaser 6000B                      | 1         | 4.55%   |
| Seiko Epson L396 Series                 | 1         | 4.55%   |
| Seiko Epson AL-M310DN                   | 1         | 4.55%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4.55%   |
| Samsung SCX-6545 Series                 | 1         | 4.55%   |
| Samsung SCX-3400 Series                 | 1         | 4.55%   |
| Samsung M2020 Series                    | 1         | 4.55%   |
| HP LaserJet P1102                       | 1         | 4.55%   |
| HP LaserJet P1005                       | 1         | 4.55%   |
| HP LaserJet 1020                        | 1         | 4.55%   |
| HP LaserJet 1018                        | 1         | 4.55%   |
| HP Ink Tank Wireless 410 series         | 1         | 4.55%   |
| HP Deskjet Ink Advant K209a-z           | 1         | 4.55%   |
| HP Deskjet D1500 series                 | 1         | 4.55%   |
| HP Deskjet 2540 series                  | 1         | 4.55%   |
| Canon PIXMA MG3000 series               | 1         | 4.55%   |
| Canon MG5600 series                     | 1         | 4.55%   |
| Canon LiDE 400                          | 1         | 4.55%   |
| Brother DCP-1610W                       | 1         | 4.55%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon                  | 2         | 50%     |
| Plustek                | 1         | 25%     |
| Microtek International | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner         | 1         | 25%     |
| Microtek International USB1200 Scanner | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20     | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30          | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 509       | 24.12%  |
| IMC Networks                           | 229       | 10.85%  |
| Microdia                               | 224       | 10.62%  |
| Realtek Semiconductor                  | 192       | 9.1%    |
| Acer                                   | 169       | 8.01%   |
| Sunplus Innovation Technology          | 120       | 5.69%   |
| Suyin                                  | 100       | 4.74%   |
| Quanta                                 | 99        | 4.69%   |
| Cheng Uei Precision Industry (Foxlink) | 75        | 3.55%   |
| Syntek                                 | 67        | 3.18%   |
| Silicon Motion                         | 50        | 2.37%   |
| Lite-On Technology                     | 47        | 2.23%   |
| Ricoh                                  | 27        | 1.28%   |
| Lenovo                                 | 23        | 1.09%   |
| Luxvisions Innotech Limited            | 21        | 1%      |
| Logitech                               | 21        | 1%      |
| Alcor Micro                            | 20        | 0.95%   |
| Apple                                  | 15        | 0.71%   |
| Z-Star Microelectronics                | 14        | 0.66%   |
| DigiTech                               | 11        | 0.52%   |
| Creative Technology                    | 10        | 0.47%   |
| Primax Electronics                     | 9         | 0.43%   |
| Intel                                  | 8         | 0.38%   |
| ALi                                    | 8         | 0.38%   |
| Sonix Technology                       | 5         | 0.24%   |
| Samsung Electronics                    | 5         | 0.24%   |
| Generalplus Technology                 | 5         | 0.24%   |
| Microsoft                              | 4         | 0.19%   |
| Importek                               | 3         | 0.14%   |
| Sunplus Technology                     | 2         | 0.09%   |
| OmniVision Technologies                | 2         | 0.09%   |
| MacroSilicon                           | 2         | 0.09%   |
| Foxconn / Hon Hai                      | 2         | 0.09%   |
| Cubeternet                             | 2         | 0.09%   |
| Trust                                  | 1         | 0.05%   |
| Nokia Mobile Phones                    | 1         | 0.05%   |
| Nebraska Furniture Mart                | 1         | 0.05%   |
| Mustek Systems                         | 1         | 0.05%   |
| LG Electronics                         | 1         | 0.05%   |
| kingcome                               | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 102       | 4.82%   |
| Microdia Integrated_Webcam_HD            | 77        | 3.64%   |
| Realtek Integrated_Webcam_HD             | 63        | 2.98%   |
| IMC Networks Integrated Camera           | 60        | 2.84%   |
| IMC Networks USB2.0 HD UVC WebCam        | 56        | 2.65%   |
| Sunplus Integrated_Webcam_HD             | 52        | 2.46%   |
| Acer Lenovo EasyCamera                   | 50        | 2.36%   |
| Chicony Lenovo EasyCamera                | 40        | 1.89%   |
| Microdia Integrated Webcam               | 37        | 1.75%   |
| Chicony HD Webcam                        | 36        | 1.7%    |
| Suyin Integrated_Webcam_HD               | 35        | 1.65%   |
| Acer Integrated Camera                   | 32        | 1.51%   |
| Syntek Lenovo EasyCamera                 | 29        | 1.37%   |
| Realtek Lenovo EasyCamera                | 25        | 1.18%   |
| Syntek Integrated Camera                 | 21        | 0.99%   |
| Lite-On Integrated Camera                | 21        | 0.99%   |
| Chicony USB2.0 HD UVC WebCam             | 21        | 0.99%   |
| Realtek USB Camera                       | 20        | 0.95%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 20        | 0.95%   |
| Quanta HP TrueVision HD Camera           | 19        | 0.9%    |
| Suyin Acer/HP Integrated Webcam [CN0314] | 18        | 0.85%   |
| Realtek Integrated Webcam HD             | 17        | 0.8%    |
| Quanta HD User Facing                    | 17        | 0.8%    |
| Chicony HP HD Camera                     | 17        | 0.8%    |
| Microdia Laptop_Integrated_Webcam_HD     | 16        | 0.76%   |
| IMC Networks Integrated Webcam           | 16        | 0.76%   |
| Chicony USB 2.0 Camera                   | 16        | 0.76%   |
| Acer SunplusIT Integrated Camera         | 16        | 0.76%   |
| Chicony USB2.0 VGA UVC WebCam            | 15        | 0.71%   |
| Realtek Integrated Webcam                | 13        | 0.61%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 13        | 0.61%   |
| Chicony Integrated Camera (1280x720@30)  | 13        | 0.61%   |
| Lite-On HP HD Camera                     | 12        | 0.57%   |
| Chicony VGA WebCam                       | 12        | 0.57%   |
| Chicony HP HD Webcam [Fixed]             | 12        | 0.57%   |
| Acer EasyCamera                          | 12        | 0.57%   |
| Sunplus Laptop_Integrated_Webcam_FHD     | 11        | 0.52%   |
| Sunplus HD WebCam                        | 11        | 0.52%   |
| Silicon Motion WebCam SC-13HDL11939N     | 11        | 0.52%   |
| Quanta HP Webcam                         | 11        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 172       | 38.22%  |
| Synaptics                  | 99        | 22%     |
| AuthenTec                  | 53        | 11.78%  |
| Shenzhen Goodix Technology | 52        | 11.56%  |
| Upek                       | 34        | 7.56%   |
| LighTuning Technology      | 15        | 3.33%   |
| Elan Microelectronics      | 13        | 2.89%   |
| STMicroelectronics         | 12        | 2.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 8.44%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 7.78%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 33        | 7.33%   |
| Shenzhen Goodix  FingerPrint Device                                        | 29        | 6.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 24        | 5.33%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 22        | 4.89%   |
| AuthenTec AES2810                                                          | 22        | 4.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 18        | 4%      |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 3.78%   |
| Unknown                                                                    | 15        | 3.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 3.11%   |
| Validity Sensors VFS491                                                    | 12        | 2.67%   |
| STMicroelectronics Fingerprint Reader                                      | 12        | 2.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2.44%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 11        | 2.44%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 2%      |
| Elan ELAN:Fingerprint                                                      | 9         | 2%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 8         | 1.78%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 1.78%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.33%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.33%   |
| AuthenTec AES1600                                                          | 6         | 1.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 1.11%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.11%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.11%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.11%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.89%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.89%   |
| Synaptics  WBDI                                                            | 4         | 0.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.89%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.89%   |
| Elan ELAN:ARM-M4                                                           | 4         | 0.89%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.89%   |
| Synaptics WBDI Device                                                      | 3         | 0.67%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.67%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.44%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.22%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 194       | 56.23%  |
| Alcor Micro               | 69        | 20%     |
| O2 Micro                  | 39        | 11.3%   |
| Lenovo                    | 20        | 5.8%    |
| Upek                      | 18        | 5.22%   |
| Gemalto (was Gemplus)     | 4         | 1.16%   |
| Aladdin Knowledge Systems | 1         | 0.29%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 67        | 19.42%  |
| Broadcom BCM5880 Secure Applications Processor                               | 64        | 18.55%  |
| Broadcom 5880                                                                | 48        | 13.91%  |
| Broadcom 58200                                                               | 46        | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 35        | 10.14%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 32        | 9.28%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 5.8%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 18        | 5.22%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 2.03%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.87%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.29%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.29%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.29%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.29%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1455      | 57.51%  |
| 1     | 812       | 32.09%  |
| 2     | 226       | 8.93%   |
| 3     | 29        | 1.15%   |
| 4     | 3         | 0.12%   |
| 7     | 2         | 0.08%   |
| 5     | 2         | 0.08%   |
| 6     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 444       | 33.16%  |
| Chipcard                 | 316       | 23.6%   |
| Graphics card            | 281       | 20.99%  |
| Net/wireless             | 81        | 6.05%   |
| Storage                  | 46        | 3.44%   |
| Multimedia controller    | 38        | 2.84%   |
| Bluetooth                | 36        | 2.69%   |
| Camera                   | 24        | 1.79%   |
| Communication controller | 22        | 1.64%   |
| Card reader              | 15        | 1.12%   |
| Sound                    | 10        | 0.75%   |
| Modem                    | 7         | 0.52%   |
| Firewire controller      | 5         | 0.37%   |
| Net/ethernet             | 4         | 0.3%    |
| Flash memory             | 3         | 0.22%   |
| Dvb card                 | 3         | 0.22%   |
| Wireless                 | 1         | 0.07%   |
| Tv card                  | 1         | 0.07%   |
| Storage/raid             | 1         | 0.07%   |
| Network                  | 1         | 0.07%   |

