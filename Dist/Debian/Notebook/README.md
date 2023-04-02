Debian - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Debian.

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

Total: 6571

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Tactus        | GeoBook 140                 | [0ceb5a3b7c](https://linux-hardware.org/?probe=0ceb5a3b7c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [4787e68a9c](https://linux-hardware.org/?probe=4787e68a9c) | Apr 01, 2023 |
| MSI           | Vector GP66 12UGS           | [12e105f6da](https://linux-hardware.org/?probe=12e105f6da) | Apr 01, 2023 |
| Lenovo        | G50-45 80E3                 | [f75af97954](https://linux-hardware.org/?probe=f75af97954) | Apr 01, 2023 |
| HP            | Pavilion dv7                | [00bbec023a](https://linux-hardware.org/?probe=00bbec023a) | Apr 01, 2023 |
| ASUSTek       | X202E                       | [cdcccb09e7](https://linux-hardware.org/?probe=cdcccb09e7) | Mar 31, 2023 |
| ASUSTek       | X202E                       | [ac12ec53a3](https://linux-hardware.org/?probe=ac12ec53a3) | Mar 31, 2023 |
| Lenovo        | Yoga 3 11 80J8              | [fce7483fa0](https://linux-hardware.org/?probe=fce7483fa0) | Mar 31, 2023 |
| Dell          | Latitude E6330              | [ae7a7254b8](https://linux-hardware.org/?probe=ae7a7254b8) | Mar 31, 2023 |
| Dell          | Latitude E6330              | [2239e12384](https://linux-hardware.org/?probe=2239e12384) | Mar 31, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [3399c2f210](https://linux-hardware.org/?probe=3399c2f210) | Mar 31, 2023 |
| Dell          | Precision M4700             | [7c93bc178e](https://linux-hardware.org/?probe=7c93bc178e) | Mar 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [990f324256](https://linux-hardware.org/?probe=990f324256) | Mar 30, 2023 |
| Dell          | XPS 13 7390                 | [b6226ae481](https://linux-hardware.org/?probe=b6226ae481) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | [bf3d484605](https://linux-hardware.org/?probe=bf3d484605) | Mar 30, 2023 |
| Fujitsu       | LIFEBOOK S752               | [3e4d9fac89](https://linux-hardware.org/?probe=3e4d9fac89) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e85544a3d7](https://linux-hardware.org/?probe=e85544a3d7) | Mar 30, 2023 |
| Dell          | Precision M4800             | [ebd0442adc](https://linux-hardware.org/?probe=ebd0442adc) | Mar 30, 2023 |
| Lenovo        | ThinkPad T60 195143U        | [4de196550b](https://linux-hardware.org/?probe=4de196550b) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [fc06b01f31](https://linux-hardware.org/?probe=fc06b01f31) | Mar 29, 2023 |
| MSI           | Prestige 14Evo A11M         | [5ac693dbd4](https://linux-hardware.org/?probe=5ac693dbd4) | Mar 29, 2023 |
| Acer          | Nitro AN515-43              | [47c758c261](https://linux-hardware.org/?probe=47c758c261) | Mar 29, 2023 |
| Unknown       | Unknown                     | [7d3374d52b](https://linux-hardware.org/?probe=7d3374d52b) | Mar 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [77e01c9b12](https://linux-hardware.org/?probe=77e01c9b12) | Mar 29, 2023 |
| Acer          | Aspire A315-23G             | [5c6734f5e6](https://linux-hardware.org/?probe=5c6734f5e6) | Mar 29, 2023 |
| Medion        | P7641 MD99856               | [7347a28d53](https://linux-hardware.org/?probe=7347a28d53) | Mar 28, 2023 |
| HP            | Pavilion dv5000 (EW771EA... | [db28f35ce0](https://linux-hardware.org/?probe=db28f35ce0) | Mar 28, 2023 |
| Acer          | Aspire V3-571G              | [289bd8c2fd](https://linux-hardware.org/?probe=289bd8c2fd) | Mar 28, 2023 |
| THUNDEROBO... | 911 Plus                    | [6617ad47b7](https://linux-hardware.org/?probe=6617ad47b7) | Mar 28, 2023 |
| Google        | Swanky                      | [0f32e48b38](https://linux-hardware.org/?probe=0f32e48b38) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B9C... | [0744b26f5c](https://linux-hardware.org/?probe=0744b26f5c) | Mar 27, 2023 |
| HP            | EliteBook 840 G3            | [58d5e99cd1](https://linux-hardware.org/?probe=58d5e99cd1) | Mar 27, 2023 |
| GPD           | P3 MAX                      | [b3627909f1](https://linux-hardware.org/?probe=b3627909f1) | Mar 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [17794caffa](https://linux-hardware.org/?probe=17794caffa) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [7cd7234999](https://linux-hardware.org/?probe=7cd7234999) | Mar 27, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [dd84425bc7](https://linux-hardware.org/?probe=dd84425bc7) | Mar 27, 2023 |
| Lenovo        | G50-45 80E3                 | [279d3659a9](https://linux-hardware.org/?probe=279d3659a9) | Mar 26, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [d1f406ffe7](https://linux-hardware.org/?probe=d1f406ffe7) | Mar 26, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | [2d83ebd124](https://linux-hardware.org/?probe=2d83ebd124) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [d2f95decbe](https://linux-hardware.org/?probe=d2f95decbe) | Mar 26, 2023 |
| Dell          | Precision 5570              | [454590a1a8](https://linux-hardware.org/?probe=454590a1a8) | Mar 26, 2023 |
| Acer          | Nitro AN515-52              | [1377a2ea15](https://linux-hardware.org/?probe=1377a2ea15) | Mar 26, 2023 |
| Dell          | Latitude E6330              | [32833b4683](https://linux-hardware.org/?probe=32833b4683) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0C40... | [39b2a59543](https://linux-hardware.org/?probe=39b2a59543) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [9b9a21b7da](https://linux-hardware.org/?probe=9b9a21b7da) | Mar 24, 2023 |
| Packard Be... | H17HV                       | [c4bddccbd8](https://linux-hardware.org/?probe=c4bddccbd8) | Mar 24, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [58f8d5849a](https://linux-hardware.org/?probe=58f8d5849a) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [d6783c57a6](https://linux-hardware.org/?probe=d6783c57a6) | Mar 24, 2023 |
| Lenovo        | Z50-75 80EC                 | [353666c217](https://linux-hardware.org/?probe=353666c217) | Mar 24, 2023 |
| Dell          | Inspiron 7348               | [4011322039](https://linux-hardware.org/?probe=4011322039) | Mar 24, 2023 |
| Toshiba       | Satellite C50-B             | [4b563f19dd](https://linux-hardware.org/?probe=4b563f19dd) | Mar 24, 2023 |
| HP            | EliteBook 850 G5            | [cde421908c](https://linux-hardware.org/?probe=cde421908c) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| ASUSTek       | N56VJ                       | [da2c5d6ff1](https://linux-hardware.org/?probe=da2c5d6ff1) | Mar 24, 2023 |
| Dell          | Inspiron 15 3511            | [7aa41dd248](https://linux-hardware.org/?probe=7aa41dd248) | Mar 23, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [32a4fc1880](https://linux-hardware.org/?probe=32a4fc1880) | Mar 23, 2023 |
| Acer          | Aspire VN7-791              | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [5e97d4fdf3](https://linux-hardware.org/?probe=5e97d4fdf3) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [92208949d5](https://linux-hardware.org/?probe=92208949d5) | Mar 22, 2023 |
| Apple         | MacBookPro11,2              | [aa71c25dba](https://linux-hardware.org/?probe=aa71c25dba) | Mar 22, 2023 |
| Unknown       | Unknown                     | [ef5bf53c45](https://linux-hardware.org/?probe=ef5bf53c45) | Mar 22, 2023 |
| Dell          | G3 3579                     | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Unknown       | Unknown                     | [b96104604a](https://linux-hardware.org/?probe=b96104604a) | Mar 22, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [1f5d2a057c](https://linux-hardware.org/?probe=1f5d2a057c) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Apple         | MacBookPro5,5               | [849f9d23c7](https://linux-hardware.org/?probe=849f9d23c7) | Mar 21, 2023 |
| Lenovo        | ThinkPad X230s 20AHS0070... | [9d86eaf558](https://linux-hardware.org/?probe=9d86eaf558) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Dell          | Inspiron 5570               | [e311e9a53a](https://linux-hardware.org/?probe=e311e9a53a) | Mar 21, 2023 |
| HP            | EliteBook 850 G5            | [5ca3a1b044](https://linux-hardware.org/?probe=5ca3a1b044) | Mar 21, 2023 |
| Lenovo        | G570 20079                  | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| ASUSTek       | S551LB                      | [da9a9373a6](https://linux-hardware.org/?probe=da9a9373a6) | Mar 20, 2023 |
| Toshiba       | Satellite C50-B             | [b9bf22cc53](https://linux-hardware.org/?probe=b9bf22cc53) | Mar 20, 2023 |
| Dell          | Latitude E6420              | [e564f25125](https://linux-hardware.org/?probe=e564f25125) | Mar 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7bc035af43](https://linux-hardware.org/?probe=7bc035af43) | Mar 20, 2023 |
| Fujitsu       | LIFEBOOK E734               | [0c4119f8b3](https://linux-hardware.org/?probe=0c4119f8b3) | Mar 20, 2023 |
| Samsung       | RF511/RF411/RF711           | [bff0b1d8a4](https://linux-hardware.org/?probe=bff0b1d8a4) | Mar 20, 2023 |
| Dell          | Latitude 7480               | [00d8228ec6](https://linux-hardware.org/?probe=00d8228ec6) | Mar 20, 2023 |
| Dell          | G3 3590                     | [cba689e7f5](https://linux-hardware.org/?probe=cba689e7f5) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
| TUXEDO        | N13xWU                      | [e9614af654](https://linux-hardware.org/?probe=e9614af654) | Mar 19, 2023 |
| Dell          | Latitude 7480               | [bbdb75bdce](https://linux-hardware.org/?probe=bbdb75bdce) | Mar 19, 2023 |
| HP            | Pavilion g7                 | [e591ea2173](https://linux-hardware.org/?probe=e591ea2173) | Mar 19, 2023 |
| Lenovo        | ThinkPad T540p 20BE00B8M... | [4cb81db618](https://linux-hardware.org/?probe=4cb81db618) | Mar 19, 2023 |
| Acer          | Aspire V5-552PG             | [d895f0f391](https://linux-hardware.org/?probe=d895f0f391) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | [229dcc2cb0](https://linux-hardware.org/?probe=229dcc2cb0) | Mar 19, 2023 |
| Toshiba       | Satellite C655              | [5037090da8](https://linux-hardware.org/?probe=5037090da8) | Mar 19, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| HP            | Laptop 14-cm0xxx            | [b939c61b5a](https://linux-hardware.org/?probe=b939c61b5a) | Mar 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [f3a832587b](https://linux-hardware.org/?probe=f3a832587b) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| HP            | ProBook 470 G3              | [3cdb0bbdf6](https://linux-hardware.org/?probe=3cdb0bbdf6) | Mar 17, 2023 |
| Aquarius      | NS585                       | [cd1e92458f](https://linux-hardware.org/?probe=cd1e92458f) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [2020cf3584](https://linux-hardware.org/?probe=2020cf3584) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [e7ebc0ec0e](https://linux-hardware.org/?probe=e7ebc0ec0e) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c343e79a84](https://linux-hardware.org/?probe=c343e79a84) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [5391c84cf4](https://linux-hardware.org/?probe=5391c84cf4) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8fcb466fab](https://linux-hardware.org/?probe=8fcb466fab) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [7aa3efb2fd](https://linux-hardware.org/?probe=7aa3efb2fd) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [8319fcb9da](https://linux-hardware.org/?probe=8319fcb9da) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [6bf9694348](https://linux-hardware.org/?probe=6bf9694348) | Mar 17, 2023 |
| Apple         | MacBook5,2                  | [c3c0ef4a31](https://linux-hardware.org/?probe=c3c0ef4a31) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [66f4a76724](https://linux-hardware.org/?probe=66f4a76724) | Mar 17, 2023 |
| HP            | 255 G3                      | [3e5f860704](https://linux-hardware.org/?probe=3e5f860704) | Mar 17, 2023 |
| Samsung       | RF511/RF411/RF711           | [ecb08b3c5e](https://linux-hardware.org/?probe=ecb08b3c5e) | Mar 17, 2023 |
| Dell          | Latitude 7480               | [ee6015f962](https://linux-hardware.org/?probe=ee6015f962) | Mar 17, 2023 |
| MSI           | GF72 8RE                    | [4610dffdcc](https://linux-hardware.org/?probe=4610dffdcc) | Mar 17, 2023 |
| HP            | Notebook                    | [e901631805](https://linux-hardware.org/?probe=e901631805) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [b50b834744](https://linux-hardware.org/?probe=b50b834744) | Mar 16, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f3ee556fb5](https://linux-hardware.org/?probe=f3ee556fb5) | Mar 16, 2023 |
| Dell          | Precision M6800             | [db62a370ed](https://linux-hardware.org/?probe=db62a370ed) | Mar 16, 2023 |
| HP            | EliteBook 8460p             | [e8d00684ac](https://linux-hardware.org/?probe=e8d00684ac) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [57f2de5da4](https://linux-hardware.org/?probe=57f2de5da4) | Mar 16, 2023 |
| HP            | EliteBook 840 G6            | [2a316e6d03](https://linux-hardware.org/?probe=2a316e6d03) | Mar 16, 2023 |
| HP            | EliteBook 830 G5            | [c6aa050dd1](https://linux-hardware.org/?probe=c6aa050dd1) | Mar 16, 2023 |
| Dell          | Latitude 7480               | [72069037ca](https://linux-hardware.org/?probe=72069037ca) | Mar 16, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [ca6ab3c197](https://linux-hardware.org/?probe=ca6ab3c197) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [3f7d27d637](https://linux-hardware.org/?probe=3f7d27d637) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Samsung       | 550XBE/350XBE               | [e670ea3583](https://linux-hardware.org/?probe=e670ea3583) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Acer          | AO756                       | [21ba8b2996](https://linux-hardware.org/?probe=21ba8b2996) | Mar 15, 2023 |
| Apple         | MacBook5,2                  | [c8c6ab5fce](https://linux-hardware.org/?probe=c8c6ab5fce) | Mar 15, 2023 |
| Acer          | Aspire 7720                 | [0f040d8292](https://linux-hardware.org/?probe=0f040d8292) | Mar 15, 2023 |
| HP            | Mini 210-1000               | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| TUXEDO        | Aura 15 Gen2                | [15d4cdae49](https://linux-hardware.org/?probe=15d4cdae49) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [634ae1ae2b](https://linux-hardware.org/?probe=634ae1ae2b) | Mar 14, 2023 |
| ASUSTek       | ZenBook UX534FAC_UX533FA... | [83351958e6](https://linux-hardware.org/?probe=83351958e6) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [a897cf713a](https://linux-hardware.org/?probe=a897cf713a) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [63cbbd1f57](https://linux-hardware.org/?probe=63cbbd1f57) | Mar 14, 2023 |
| TUXEDO        | InfinityBook Pro 14 v4      | [f5cbc232d7](https://linux-hardware.org/?probe=f5cbc232d7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [aeb56fbebc](https://linux-hardware.org/?probe=aeb56fbebc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [ee034131c0](https://linux-hardware.org/?probe=ee034131c0) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [438caf3588](https://linux-hardware.org/?probe=438caf3588) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [57d173995a](https://linux-hardware.org/?probe=57d173995a) | Mar 14, 2023 |
| Acer          | Aspire 7739G                | [aeff2df11c](https://linux-hardware.org/?probe=aeff2df11c) | Mar 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [812104dae3](https://linux-hardware.org/?probe=812104dae3) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [27c3c24dfc](https://linux-hardware.org/?probe=27c3c24dfc) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [714f8e1321](https://linux-hardware.org/?probe=714f8e1321) | Mar 14, 2023 |
| Acer          | Aspire 7720                 | [b80fa5f7ff](https://linux-hardware.org/?probe=b80fa5f7ff) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [500bee4bb7](https://linux-hardware.org/?probe=500bee4bb7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [189b1a8ec7](https://linux-hardware.org/?probe=189b1a8ec7) | Mar 14, 2023 |
| Apple         | MacBook5,2                  | [9be2c9ee2b](https://linux-hardware.org/?probe=9be2c9ee2b) | Mar 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [054bb62a67](https://linux-hardware.org/?probe=054bb62a67) | Mar 14, 2023 |
| Lenovo        | Z710 20250                  | [3a99fb6400](https://linux-hardware.org/?probe=3a99fb6400) | Mar 14, 2023 |
| Acer          | Aspire E5-551G              | [7a992ff109](https://linux-hardware.org/?probe=7a992ff109) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d9d4f5649a](https://linux-hardware.org/?probe=d9d4f5649a) | Mar 14, 2023 |
| Schenker      | VIA 15 Pro                  | [ef02f8156e](https://linux-hardware.org/?probe=ef02f8156e) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [5c4b7a9754](https://linux-hardware.org/?probe=5c4b7a9754) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [481073d13f](https://linux-hardware.org/?probe=481073d13f) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [497a7bdef5](https://linux-hardware.org/?probe=497a7bdef5) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cc878090ee](https://linux-hardware.org/?probe=cc878090ee) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [07ceb1e102](https://linux-hardware.org/?probe=07ceb1e102) | Mar 13, 2023 |
| ASUSTek       | GL753VE                     | [8100c63113](https://linux-hardware.org/?probe=8100c63113) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [79fdcb1951](https://linux-hardware.org/?probe=79fdcb1951) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [73e4261a63](https://linux-hardware.org/?probe=73e4261a63) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [44784531d4](https://linux-hardware.org/?probe=44784531d4) | Mar 13, 2023 |
| Acer          | Aspire E5-511               | [5343f73c67](https://linux-hardware.org/?probe=5343f73c67) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [e58e88f5fd](https://linux-hardware.org/?probe=e58e88f5fd) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [267c6693a0](https://linux-hardware.org/?probe=267c6693a0) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [bdb4c28449](https://linux-hardware.org/?probe=bdb4c28449) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [d9226f0ad6](https://linux-hardware.org/?probe=d9226f0ad6) | Mar 13, 2023 |
| Apple         | MacBook5,2                  | [906f70a5e9](https://linux-hardware.org/?probe=906f70a5e9) | Mar 13, 2023 |
| Lenovo        | Yoga 2 Pro 20266            | [f762c7cc29](https://linux-hardware.org/?probe=f762c7cc29) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| Acer          | Aspire 5738                 | [bd231fbff6](https://linux-hardware.org/?probe=bd231fbff6) | Mar 12, 2023 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [fd6d58db15](https://linux-hardware.org/?probe=fd6d58db15) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| HP            | ZBook 17 G3                 | [f69ef4ff89](https://linux-hardware.org/?probe=f69ef4ff89) | Mar 12, 2023 |
| Lenovo        | ThinkPad X131e 3367AG9      | [0ff86711d1](https://linux-hardware.org/?probe=0ff86711d1) | Mar 12, 2023 |
| Dell          | Latitude 3510               | [13ed29770d](https://linux-hardware.org/?probe=13ed29770d) | Mar 12, 2023 |
| Dell          | Inspiron 5593               | [631b554e46](https://linux-hardware.org/?probe=631b554e46) | Mar 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [55a73e2e07](https://linux-hardware.org/?probe=55a73e2e07) | Mar 12, 2023 |
| HP            | ProBook 4415s               | [8b974a2717](https://linux-hardware.org/?probe=8b974a2717) | Mar 12, 2023 |
| HP            | Pavilion Notebook           | [158d246d65](https://linux-hardware.org/?probe=158d246d65) | Mar 11, 2023 |
| Dell          | Precision 5570              | [470ba58973](https://linux-hardware.org/?probe=470ba58973) | Mar 11, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [f066472937](https://linux-hardware.org/?probe=f066472937) | Mar 11, 2023 |
| Dell          | Latitude E6430              | [080ad6aa2a](https://linux-hardware.org/?probe=080ad6aa2a) | Mar 11, 2023 |
| Acer          | Swift SF314-43              | [dc1a94966b](https://linux-hardware.org/?probe=dc1a94966b) | Mar 11, 2023 |
| Dell          | Latitude 3320               | [2a58a07005](https://linux-hardware.org/?probe=2a58a07005) | Mar 11, 2023 |
| Dell          | Latitude 3320               | [d17364c0ef](https://linux-hardware.org/?probe=d17364c0ef) | Mar 11, 2023 |
| Dell          | XPS 13 9310                 | [c528b16696](https://linux-hardware.org/?probe=c528b16696) | Mar 10, 2023 |
| System76      | Gazelle Professional        | [42f5755b1d](https://linux-hardware.org/?probe=42f5755b1d) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [ffb66872c2](https://linux-hardware.org/?probe=ffb66872c2) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [9736a383d7](https://linux-hardware.org/?probe=9736a383d7) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [f9bd57cf06](https://linux-hardware.org/?probe=f9bd57cf06) | Mar 10, 2023 |
| Apple         | MacBook5,2                  | [a71d5d0d96](https://linux-hardware.org/?probe=a71d5d0d96) | Mar 10, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [87aa621d6a](https://linux-hardware.org/?probe=87aa621d6a) | Mar 10, 2023 |
| Dell          | Latitude 7285               | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [91985ffa00](https://linux-hardware.org/?probe=91985ffa00) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [40499e56d1](https://linux-hardware.org/?probe=40499e56d1) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [3abbf961d5](https://linux-hardware.org/?probe=3abbf961d5) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [734afe2673](https://linux-hardware.org/?probe=734afe2673) | Mar 09, 2023 |
| Apple         | MacBook5,2                  | [364b9159c4](https://linux-hardware.org/?probe=364b9159c4) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [276ce8bd7c](https://linux-hardware.org/?probe=276ce8bd7c) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3daf833362](https://linux-hardware.org/?probe=3daf833362) | Mar 09, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [b00f44cd46](https://linux-hardware.org/?probe=b00f44cd46) | Mar 09, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5bc1f5d6d8](https://linux-hardware.org/?probe=5bc1f5d6d8) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [3b9229e07a](https://linux-hardware.org/?probe=3b9229e07a) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK U7312              | [74bbf2c865](https://linux-hardware.org/?probe=74bbf2c865) | Mar 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Medion        | E122X                       | [dad02f1ac7](https://linux-hardware.org/?probe=dad02f1ac7) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [07f425d57f](https://linux-hardware.org/?probe=07f425d57f) | Mar 08, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f62ef69dcc](https://linux-hardware.org/?probe=f62ef69dcc) | Mar 08, 2023 |
| Dell          | Precision 3560              | [0873d45206](https://linux-hardware.org/?probe=0873d45206) | Mar 08, 2023 |
| HP            | ZBook Studio G3             | [d059dad473](https://linux-hardware.org/?probe=d059dad473) | Mar 08, 2023 |
| Dell          | XPS 15 9570                 | [fc0152a6de](https://linux-hardware.org/?probe=fc0152a6de) | Mar 08, 2023 |
| Acer          | Nitro AN515-43              | [32d1af5dee](https://linux-hardware.org/?probe=32d1af5dee) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [e6cbad4861](https://linux-hardware.org/?probe=e6cbad4861) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [6fa1bc8547](https://linux-hardware.org/?probe=6fa1bc8547) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [ce9ba5580b](https://linux-hardware.org/?probe=ce9ba5580b) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [9a8f396913](https://linux-hardware.org/?probe=9a8f396913) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [07709f5f79](https://linux-hardware.org/?probe=07709f5f79) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [8bbc04cb55](https://linux-hardware.org/?probe=8bbc04cb55) | Mar 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [a3682a5cb6](https://linux-hardware.org/?probe=a3682a5cb6) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [7b1918ab47](https://linux-hardware.org/?probe=7b1918ab47) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [0d996d4041](https://linux-hardware.org/?probe=0d996d4041) | Mar 07, 2023 |
| Apple         | MacBook5,2                  | [eb4c28b498](https://linux-hardware.org/?probe=eb4c28b498) | Mar 07, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [124045e654](https://linux-hardware.org/?probe=124045e654) | Mar 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ac92e5ce13](https://linux-hardware.org/?probe=ac92e5ce13) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [92f8093adb](https://linux-hardware.org/?probe=92f8093adb) | Mar 07, 2023 |
| HP            | ZBook 15 G3                 | [b00f87c99b](https://linux-hardware.org/?probe=b00f87c99b) | Mar 06, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [119a07048d](https://linux-hardware.org/?probe=119a07048d) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [91db409270](https://linux-hardware.org/?probe=91db409270) | Mar 06, 2023 |
| ASUSTek       | X550JX                      | [a9a82b2395](https://linux-hardware.org/?probe=a9a82b2395) | Mar 06, 2023 |
| Fujitsu       | LIFEBOOK U9312              | [19a72f502b](https://linux-hardware.org/?probe=19a72f502b) | Mar 06, 2023 |
| MSI           | Modern 15 A5M               | [7d708fea96](https://linux-hardware.org/?probe=7d708fea96) | Mar 06, 2023 |
| HUAWEI        | BOHB-WAX9                   | [eb5b9b8cb9](https://linux-hardware.org/?probe=eb5b9b8cb9) | Mar 06, 2023 |
| Acer          | Aspire E1-571               | [2194ce4568](https://linux-hardware.org/?probe=2194ce4568) | Mar 06, 2023 |
| MSI           | PS42 8RB                    | [57231416e1](https://linux-hardware.org/?probe=57231416e1) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| Apple         | MacBookPro6,2               | [308b516329](https://linux-hardware.org/?probe=308b516329) | Mar 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [b9677c823b](https://linux-hardware.org/?probe=b9677c823b) | Mar 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Acer          | Aspire A315-54              | [cadbbe841e](https://linux-hardware.org/?probe=cadbbe841e) | Mar 05, 2023 |
| Dell          | G5 5500                     | [7da5494dea](https://linux-hardware.org/?probe=7da5494dea) | Mar 05, 2023 |
| HP            | G42                         | [7dee433139](https://linux-hardware.org/?probe=7dee433139) | Mar 05, 2023 |
| Toshiba       | Satellite A200              | [47f08e4094](https://linux-hardware.org/?probe=47f08e4094) | Mar 04, 2023 |
| HP            | EliteBook 840 G3            | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| Dell          | Latitude E5450              | [2f16482775](https://linux-hardware.org/?probe=2f16482775) | Mar 04, 2023 |
| Intel         | powered classmate PC        | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| SANTECH       | NHx0DB,DE                   | [9ebc94ec48](https://linux-hardware.org/?probe=9ebc94ec48) | Mar 04, 2023 |
| Dell          | Vostro 3700                 | [ea14c47abb](https://linux-hardware.org/?probe=ea14c47abb) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c4def038d9](https://linux-hardware.org/?probe=c4def038d9) | Mar 04, 2023 |
| Dell          | XPS 15 9520                 | [1bef11c91d](https://linux-hardware.org/?probe=1bef11c91d) | Mar 04, 2023 |
| Lenovo        | ThinkPad X220 429035U       | [83266c1006](https://linux-hardware.org/?probe=83266c1006) | Mar 04, 2023 |
| HP            | Laptop 14s-dq1xxx           | [29fa7c0b23](https://linux-hardware.org/?probe=29fa7c0b23) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | [7dc484b236](https://linux-hardware.org/?probe=7dc484b236) | Mar 03, 2023 |
| HP            | 255 G8 Notebook PC          | [b7e4822b00](https://linux-hardware.org/?probe=b7e4822b00) | Mar 03, 2023 |
| Notebook      | NS5x_NS7xPU                 | [55ca2f6ac5](https://linux-hardware.org/?probe=55ca2f6ac5) | Mar 03, 2023 |
| HUAWEI        | BOHB-WAX9                   | [cdaf43afa8](https://linux-hardware.org/?probe=cdaf43afa8) | Mar 03, 2023 |
| Acer          | Aspire E1-522               | [f102669f1f](https://linux-hardware.org/?probe=f102669f1f) | Mar 03, 2023 |
| Unknown       | Unknown                     | [7afe06d070](https://linux-hardware.org/?probe=7afe06d070) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [54a92cd736](https://linux-hardware.org/?probe=54a92cd736) | Mar 03, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [916405bd1c](https://linux-hardware.org/?probe=916405bd1c) | Mar 03, 2023 |
| HP            | 635                         | [108b9443ea](https://linux-hardware.org/?probe=108b9443ea) | Mar 03, 2023 |
| Dell          | Latitude E7440              | [36439d1a64](https://linux-hardware.org/?probe=36439d1a64) | Mar 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [180f5c9379](https://linux-hardware.org/?probe=180f5c9379) | Mar 03, 2023 |
| Dell          | Vostro1710                  | [c24eab7e3d](https://linux-hardware.org/?probe=c24eab7e3d) | Mar 02, 2023 |
| Acer          | Aspire 1640Z                | [915a8900d0](https://linux-hardware.org/?probe=915a8900d0) | Mar 02, 2023 |
| Dell          | Latitude E7440              | [b84f760e8e](https://linux-hardware.org/?probe=b84f760e8e) | Mar 02, 2023 |
| ASUSTek       | X556UR                      | [70c4807d21](https://linux-hardware.org/?probe=70c4807d21) | Mar 02, 2023 |
| MSI           | Creator 15M A9SD            | [b19d8d936c](https://linux-hardware.org/?probe=b19d8d936c) | Mar 02, 2023 |
| HP            | Laptop 17-bs0xx             | [e055e73b69](https://linux-hardware.org/?probe=e055e73b69) | Mar 02, 2023 |
| Dell          | Latitude 3510               | [0bad8d504d](https://linux-hardware.org/?probe=0bad8d504d) | Mar 02, 2023 |
| PC Special... | 14 Fusion IV                | [e465178d82](https://linux-hardware.org/?probe=e465178d82) | Mar 02, 2023 |
| Dell          | XPS 15 9520                 | [2894a5929b](https://linux-hardware.org/?probe=2894a5929b) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| GMKtec        | NucBox5                     | [fc11280fe6](https://linux-hardware.org/?probe=fc11280fe6) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [da2fc6826a](https://linux-hardware.org/?probe=da2fc6826a) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [52ecc1a9fb](https://linux-hardware.org/?probe=52ecc1a9fb) | Mar 01, 2023 |
| HP            | ProBook 4415s               | [4e909ec0ad](https://linux-hardware.org/?probe=4e909ec0ad) | Mar 01, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [1165717061](https://linux-hardware.org/?probe=1165717061) | Feb 28, 2023 |
| TUXEDO        | Aura 15 Gen2                | [26a7db2ed8](https://linux-hardware.org/?probe=26a7db2ed8) | Feb 28, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [e56350a1c1](https://linux-hardware.org/?probe=e56350a1c1) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS10600    | [3fa4d926e0](https://linux-hardware.org/?probe=3fa4d926e0) | Feb 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [b4bfab8974](https://linux-hardware.org/?probe=b4bfab8974) | Feb 28, 2023 |
| HP            | ProBook 6570b               | [3692011e3f](https://linux-hardware.org/?probe=3692011e3f) | Feb 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| ASUSTek       | UX31A                       | [56654a2659](https://linux-hardware.org/?probe=56654a2659) | Feb 27, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [ccac327e17](https://linux-hardware.org/?probe=ccac327e17) | Feb 27, 2023 |
| Dell          | Latitude 5400               | [b788c61c95](https://linux-hardware.org/?probe=b788c61c95) | Feb 27, 2023 |
| Dell          | Latitude 3510               | [de938c4962](https://linux-hardware.org/?probe=de938c4962) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| Dell          | G3 3590                     | [eb9009fad9](https://linux-hardware.org/?probe=eb9009fad9) | Feb 27, 2023 |
| HP            | Pavilion g6                 | [41e4ef16e4](https://linux-hardware.org/?probe=41e4ef16e4) | Feb 26, 2023 |
| Panasonic     | CF-31WEUEEBE                | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430 2349GUU       | [95cc420bd5](https://linux-hardware.org/?probe=95cc420bd5) | Feb 26, 2023 |
| Medion        | BEAST X25                   | [3263e2862a](https://linux-hardware.org/?probe=3263e2862a) | Feb 26, 2023 |
| HP            | 250 G7 Notebook PC          | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [28bb1541b4](https://linux-hardware.org/?probe=28bb1541b4) | Feb 26, 2023 |
| HP            | EliteBook 2530p             | [8906540d72](https://linux-hardware.org/?probe=8906540d72) | Feb 26, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BX... | [633fb08804](https://linux-hardware.org/?probe=633fb08804) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [3b2a19c835](https://linux-hardware.org/?probe=3b2a19c835) | Feb 26, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [7d7953a826](https://linux-hardware.org/?probe=7d7953a826) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | X551CA                      | [c8ead0e580](https://linux-hardware.org/?probe=c8ead0e580) | Feb 25, 2023 |
| Unknown       | T3 MRD                      | [ae88920ea5](https://linux-hardware.org/?probe=ae88920ea5) | Feb 25, 2023 |
| Acer          | Nitro AN517-55              | [76e7c1c236](https://linux-hardware.org/?probe=76e7c1c236) | Feb 25, 2023 |
| HUAWEI        | WRT-WX9                     | [d49316c5e8](https://linux-hardware.org/?probe=d49316c5e8) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [67e31f8e42](https://linux-hardware.org/?probe=67e31f8e42) | Feb 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [2bb4e30118](https://linux-hardware.org/?probe=2bb4e30118) | Feb 25, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [f1db9ad466](https://linux-hardware.org/?probe=f1db9ad466) | Feb 25, 2023 |
| Acer          | Aspire A315-54              | [ff08a846b0](https://linux-hardware.org/?probe=ff08a846b0) | Feb 25, 2023 |
| Unknown       | Unknown                     | [2c5d6ab621](https://linux-hardware.org/?probe=2c5d6ab621) | Feb 25, 2023 |
| HP            | Pavilion g6                 | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [27e2d41750](https://linux-hardware.org/?probe=27e2d41750) | Feb 24, 2023 |
| Acer          | AO756                       | [ca83ee78ec](https://linux-hardware.org/?probe=ca83ee78ec) | Feb 24, 2023 |
| Lenovo        | KaiTian N70z G1d            | [cbc8e4e008](https://linux-hardware.org/?probe=cbc8e4e008) | Feb 24, 2023 |
| ASUSTek       | X551CA                      | [62b46afbb8](https://linux-hardware.org/?probe=62b46afbb8) | Feb 24, 2023 |
| Toshiba       | IS 1412                     | [c2ca1fb2f3](https://linux-hardware.org/?probe=c2ca1fb2f3) | Feb 24, 2023 |
| HP            | Presario CQ57               | [b41de6d094](https://linux-hardware.org/?probe=b41de6d094) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [3f28f459bf](https://linux-hardware.org/?probe=3f28f459bf) | Feb 24, 2023 |
| Lenovo        | G50-80 80E5                 | [8ed4158090](https://linux-hardware.org/?probe=8ed4158090) | Feb 24, 2023 |
| Dell          | Latitude D620               | [fba80b099d](https://linux-hardware.org/?probe=fba80b099d) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [5da2f709bb](https://linux-hardware.org/?probe=5da2f709bb) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [bf32299a30](https://linux-hardware.org/?probe=bf32299a30) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [54279e4e30](https://linux-hardware.org/?probe=54279e4e30) | Feb 24, 2023 |
| HP            | EliteBook Folio 9480m       | [788e0929de](https://linux-hardware.org/?probe=788e0929de) | Feb 24, 2023 |
| Samsung       | N150P                       | [662488621d](https://linux-hardware.org/?probe=662488621d) | Feb 24, 2023 |
| Shanghai Z... | ZXE CRB                     | [478a4b921f](https://linux-hardware.org/?probe=478a4b921f) | Feb 24, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [885478dd47](https://linux-hardware.org/?probe=885478dd47) | Feb 23, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [53eb80a44b](https://linux-hardware.org/?probe=53eb80a44b) | Feb 23, 2023 |
| Lenovo        | ThinkPad T410 2537CS0       | [8d4b399341](https://linux-hardware.org/?probe=8d4b399341) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| LincPlus      | P2                          | [5d4e528621](https://linux-hardware.org/?probe=5d4e528621) | Feb 23, 2023 |
| Lenovo        | ThinkPad E14 20RA0036HV     | [eef601ff61](https://linux-hardware.org/?probe=eef601ff61) | Feb 23, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [09070f52bb](https://linux-hardware.org/?probe=09070f52bb) | Feb 23, 2023 |
| Dell          | Inspiron 5566               | [0233d7525d](https://linux-hardware.org/?probe=0233d7525d) | Feb 22, 2023 |
| Fujitsu       | LIFEBOOK E753               | [8fa3315cca](https://linux-hardware.org/?probe=8fa3315cca) | Feb 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [8227fec538](https://linux-hardware.org/?probe=8227fec538) | Feb 22, 2023 |
| Acer          | Aspire A315-54              | [7cf8754a48](https://linux-hardware.org/?probe=7cf8754a48) | Feb 22, 2023 |
| Acer          | AO756                       | [58f52941c7](https://linux-hardware.org/?probe=58f52941c7) | Feb 22, 2023 |
| Dell          | Latitude 7530               | [4844568edb](https://linux-hardware.org/?probe=4844568edb) | Feb 21, 2023 |
| ASUSTek       | X556UQ                      | [8f645fa6fc](https://linux-hardware.org/?probe=8f645fa6fc) | Feb 21, 2023 |
| Lenovo        | ThinkPad T470 20HDS1DL03    | [25e1a3f801](https://linux-hardware.org/?probe=25e1a3f801) | Feb 21, 2023 |
| Dell          | Inspiron 3468               | [e5977ee094](https://linux-hardware.org/?probe=e5977ee094) | Feb 21, 2023 |
| Dell          | Latitude E6430              | [80c9785ef0](https://linux-hardware.org/?probe=80c9785ef0) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [6ab7953740](https://linux-hardware.org/?probe=6ab7953740) | Feb 20, 2023 |
| Notebook      | PB50_70RF,RD,RC             | [b24f005b1d](https://linux-hardware.org/?probe=b24f005b1d) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [19d29283ed](https://linux-hardware.org/?probe=19d29283ed) | Feb 20, 2023 |
| HP            | EliteBook 735 G5            | [8d1bb46519](https://linux-hardware.org/?probe=8d1bb46519) | Feb 20, 2023 |
| Acer          | Extensa 2520G               | [823c5829a9](https://linux-hardware.org/?probe=823c5829a9) | Feb 20, 2023 |
| HP            | EliteBook 830 G5            | [0cb773d407](https://linux-hardware.org/?probe=0cb773d407) | Feb 20, 2023 |
| Lenovo        | ThinkPad T430 2349PZG       | [7bd3c5a555](https://linux-hardware.org/?probe=7bd3c5a555) | Feb 20, 2023 |
| Acer          | Aspire V5-573G              | [376b35f5b6](https://linux-hardware.org/?probe=376b35f5b6) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [234358d23e](https://linux-hardware.org/?probe=234358d23e) | Feb 20, 2023 |
| Acer          | Aspire E1-572               | [1b75d34b95](https://linux-hardware.org/?probe=1b75d34b95) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Acer          | Nitro AN515-55              | [3158f1e0d5](https://linux-hardware.org/?probe=3158f1e0d5) | Feb 18, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8907f179e9](https://linux-hardware.org/?probe=8907f179e9) | Feb 18, 2023 |
| Lenovo        | ThinkPad E480 20KN001QGE    | [008f40a707](https://linux-hardware.org/?probe=008f40a707) | Feb 18, 2023 |
| Dell          | Latitude E5450              | [56827b29dc](https://linux-hardware.org/?probe=56827b29dc) | Feb 18, 2023 |
| HP            | Laptop 17-bs0xx             | [cc805e31b0](https://linux-hardware.org/?probe=cc805e31b0) | Feb 17, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | [32f5d5e200](https://linux-hardware.org/?probe=32f5d5e200) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [02e6818311](https://linux-hardware.org/?probe=02e6818311) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61p 6457UN2       | [4bf1ccfe74](https://linux-hardware.org/?probe=4bf1ccfe74) | Feb 17, 2023 |
| Apple         | MacBookPro9,1               | [4ab4c99cab](https://linux-hardware.org/?probe=4ab4c99cab) | Feb 17, 2023 |
| Dell          | System XPS L702X            | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d5f9d13ae3](https://linux-hardware.org/?probe=d5f9d13ae3) | Feb 16, 2023 |
| Apple         | MacBookAir6,2               | [46aafc59c4](https://linux-hardware.org/?probe=46aafc59c4) | Feb 16, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [a4fd7cdaa8](https://linux-hardware.org/?probe=a4fd7cdaa8) | Feb 16, 2023 |
| HP            | EliteBook 2530p             | [5398361b68](https://linux-hardware.org/?probe=5398361b68) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Dell          | Precision 5570              | [d0f2fa25c3](https://linux-hardware.org/?probe=d0f2fa25c3) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [13866e78a2](https://linux-hardware.org/?probe=13866e78a2) | Feb 15, 2023 |
| Google        | Grunt                       | [89c633c2c1](https://linux-hardware.org/?probe=89c633c2c1) | Feb 15, 2023 |
| ASUSTek       | K53U                        | [e9a6a69e01](https://linux-hardware.org/?probe=e9a6a69e01) | Feb 15, 2023 |
| Unknown       | T3 MRD                      | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Acer          | Aspire V5-572G              | [7f360258ff](https://linux-hardware.org/?probe=7f360258ff) | Feb 14, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [977650806e](https://linux-hardware.org/?probe=977650806e) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f6bcdb7c6b](https://linux-hardware.org/?probe=f6bcdb7c6b) | Feb 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [345021f7f6](https://linux-hardware.org/?probe=345021f7f6) | Feb 14, 2023 |
| Lenovo        | ThinkPad P51 20HJS0AR16     | [ad0f22fe34](https://linux-hardware.org/?probe=ad0f22fe34) | Feb 14, 2023 |
| ASUSTek       | X505BP                      | [579388a539](https://linux-hardware.org/?probe=579388a539) | Feb 13, 2023 |
| HP            | Laptop 15s-du3xxx           | [4750f3ad3a](https://linux-hardware.org/?probe=4750f3ad3a) | Feb 13, 2023 |
| Dell          | Latitude D630               | [04c083db36](https://linux-hardware.org/?probe=04c083db36) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [6fe738fa6d](https://linux-hardware.org/?probe=6fe738fa6d) | Feb 13, 2023 |
| Dell          | Inspiron 15-3567            | [122eded37e](https://linux-hardware.org/?probe=122eded37e) | Feb 13, 2023 |
| Google        | Droid                       | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [89c31e6f8c](https://linux-hardware.org/?probe=89c31e6f8c) | Feb 12, 2023 |
| Unknown       | Unknown                     | [72ce8d1929](https://linux-hardware.org/?probe=72ce8d1929) | Feb 12, 2023 |
| HP            | EliteBook 850 G1            | [54e092f58f](https://linux-hardware.org/?probe=54e092f58f) | Feb 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [09266b8b06](https://linux-hardware.org/?probe=09266b8b06) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [a541cb52eb](https://linux-hardware.org/?probe=a541cb52eb) | Feb 12, 2023 |
| Medion        | E1239T MD60139              | [35563886e8](https://linux-hardware.org/?probe=35563886e8) | Feb 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [b54b603772](https://linux-hardware.org/?probe=b54b603772) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [4a6ea9bd99](https://linux-hardware.org/?probe=4a6ea9bd99) | Feb 12, 2023 |
| Apple         | MacBookPro10,2              | [063d6eb482](https://linux-hardware.org/?probe=063d6eb482) | Feb 12, 2023 |
| Lenovo        | Z50-70 20354                | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| Notebook      | MAM2120                     | [300a622d96](https://linux-hardware.org/?probe=300a622d96) | Feb 11, 2023 |
| Lenovo        | Z710 20250                  | [94ee6da4d3](https://linux-hardware.org/?probe=94ee6da4d3) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [27323a90bb](https://linux-hardware.org/?probe=27323a90bb) | Feb 11, 2023 |
| Acer          | Predator G9-793             | [8c11736bf0](https://linux-hardware.org/?probe=8c11736bf0) | Feb 11, 2023 |
| Dell          | Latitude E6330              | [1b5cdf846f](https://linux-hardware.org/?probe=1b5cdf846f) | Feb 11, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| HP            | Pavilion g6                 | [35b93693a5](https://linux-hardware.org/?probe=35b93693a5) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| ASUSTek       | N751JX                      | [fd591a3e67](https://linux-hardware.org/?probe=fd591a3e67) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [7ac6f508b2](https://linux-hardware.org/?probe=7ac6f508b2) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | [8f22e1beaa](https://linux-hardware.org/?probe=8f22e1beaa) | Feb 10, 2023 |
| Samsung       | 550XDA                      | [45d947c9f9](https://linux-hardware.org/?probe=45d947c9f9) | Feb 10, 2023 |
| IBM           | ThinkPad T43 18714AG        | [0730c9228d](https://linux-hardware.org/?probe=0730c9228d) | Feb 10, 2023 |
| HP            | Laptop 17-bs0xx             | [84eb5f0ad8](https://linux-hardware.org/?probe=84eb5f0ad8) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [02adcb8587](https://linux-hardware.org/?probe=02adcb8587) | Feb 09, 2023 |
| Acer          | Aspire E1-571               | [fe1dac78bb](https://linux-hardware.org/?probe=fe1dac78bb) | Feb 09, 2023 |
| Dell          | Latitude E7250              | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| AMI           | Cherry Trail CR             | [e7eab93323](https://linux-hardware.org/?probe=e7eab93323) | Feb 09, 2023 |
| Dell          | Latitude E6330              | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| HUAWEI        | CREM-WXX9                   | [965758f3ea](https://linux-hardware.org/?probe=965758f3ea) | Feb 08, 2023 |
| Acer          | Aspire A515-52G             | [e521c55b1a](https://linux-hardware.org/?probe=e521c55b1a) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [cc897fe72d](https://linux-hardware.org/?probe=cc897fe72d) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Dell          | Precision 5570              | [6c257e667d](https://linux-hardware.org/?probe=6c257e667d) | Feb 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d37cc19110](https://linux-hardware.org/?probe=d37cc19110) | Feb 08, 2023 |
| Dell          | Precision 5570              | [e81b3de663](https://linux-hardware.org/?probe=e81b3de663) | Feb 08, 2023 |
| Dell          | Inspiron 5555               | [f5aeb173ba](https://linux-hardware.org/?probe=f5aeb173ba) | Feb 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [def4679f84](https://linux-hardware.org/?probe=def4679f84) | Feb 07, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [eca3a05d41](https://linux-hardware.org/?probe=eca3a05d41) | Feb 07, 2023 |
| Panasonic     | CF-54-1                     | [32a2acc07e](https://linux-hardware.org/?probe=32a2acc07e) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Dell          | Latitude E7250              | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| Dell          | Precision 5570              | [d279e97c00](https://linux-hardware.org/?probe=d279e97c00) | Feb 07, 2023 |
| Toshiba       | Satellite C655              | [a0c2eb7db1](https://linux-hardware.org/?probe=a0c2eb7db1) | Feb 07, 2023 |
| Google        | Terra                       | [edfe00266c](https://linux-hardware.org/?probe=edfe00266c) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | [7d2d46a579](https://linux-hardware.org/?probe=7d2d46a579) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | X71Q                        | [c89b078e8f](https://linux-hardware.org/?probe=c89b078e8f) | Feb 06, 2023 |
| Aquarius      | NS585                       | [e9deef3f9e](https://linux-hardware.org/?probe=e9deef3f9e) | Feb 06, 2023 |
| Lenovo        | ThinkPad X250 20CLS2TQ22    | [112a65a03e](https://linux-hardware.org/?probe=112a65a03e) | Feb 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [413341361a](https://linux-hardware.org/?probe=413341361a) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| Acer          | Aspire A317-53              | [2f56f41681](https://linux-hardware.org/?probe=2f56f41681) | Feb 05, 2023 |
| Google        | Ampton                      | [74d5b6aa4d](https://linux-hardware.org/?probe=74d5b6aa4d) | Feb 05, 2023 |
| Google        | Ampton                      | [2785bde3f9](https://linux-hardware.org/?probe=2785bde3f9) | Feb 05, 2023 |
| HP            | 255 G3                      | [dfa2e96880](https://linux-hardware.org/?probe=dfa2e96880) | Feb 05, 2023 |
| Apple         | MacBookAir7,2               | [29d133e858](https://linux-hardware.org/?probe=29d133e858) | Feb 05, 2023 |
| Acer          | Aspire E1-772               | [147ad71a27](https://linux-hardware.org/?probe=147ad71a27) | Feb 05, 2023 |
| Notebook      | W65_67SJ                    | [870af12011](https://linux-hardware.org/?probe=870af12011) | Feb 05, 2023 |
| Lenovo        | G50-45 80E3                 | [229050fbe5](https://linux-hardware.org/?probe=229050fbe5) | Feb 05, 2023 |
| ASUSTek       | F5SL                        | [1e5bb7661e](https://linux-hardware.org/?probe=1e5bb7661e) | Feb 04, 2023 |
| Lenovo        | G50-45 80E3                 | [885ad2ae95](https://linux-hardware.org/?probe=885ad2ae95) | Feb 04, 2023 |
| Toshiba       | Satellite P775              | [df8aa8c06a](https://linux-hardware.org/?probe=df8aa8c06a) | Feb 04, 2023 |
| HP            | Laptop 17-bs0xx             | [78ca889e8d](https://linux-hardware.org/?probe=78ca889e8d) | Feb 04, 2023 |
| Lenovo        | ThinkPad T440p 20ANS09W0... | [17f9df8f2c](https://linux-hardware.org/?probe=17f9df8f2c) | Feb 03, 2023 |
| Lenovo        | V310-15IKB 80T3             | [a39fb673c7](https://linux-hardware.org/?probe=a39fb673c7) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [4de96841bf](https://linux-hardware.org/?probe=4de96841bf) | Feb 03, 2023 |
| HP            | Pavilion 15                 | [5909dd08e7](https://linux-hardware.org/?probe=5909dd08e7) | Feb 03, 2023 |
| Acer          | Predator PH315-54           | [fe381cbbfe](https://linux-hardware.org/?probe=fe381cbbfe) | Feb 03, 2023 |
| Aquarius      | NS585                       | [7e944d88b3](https://linux-hardware.org/?probe=7e944d88b3) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [ae290fa64e](https://linux-hardware.org/?probe=ae290fa64e) | Feb 03, 2023 |
| HP            | ProBook 450 G7              | [7820377760](https://linux-hardware.org/?probe=7820377760) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [c122070f4f](https://linux-hardware.org/?probe=c122070f4f) | Feb 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [2f2c8adb0c](https://linux-hardware.org/?probe=2f2c8adb0c) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | [6d7a27b213](https://linux-hardware.org/?probe=6d7a27b213) | Feb 02, 2023 |
| Google        | Babymega                    | [2a8b81c6f4](https://linux-hardware.org/?probe=2a8b81c6f4) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| Lenovo        | ThinkPad E495 20NE001GMX    | [29660bbd04](https://linux-hardware.org/?probe=29660bbd04) | Feb 02, 2023 |
| Dell          | Latitude 7480               | [8a7e0b16d5](https://linux-hardware.org/?probe=8a7e0b16d5) | Feb 02, 2023 |
| Dell          | Latitude E6520              | [548b13cd43](https://linux-hardware.org/?probe=548b13cd43) | Feb 02, 2023 |
| Timi          | Mi Laptop Pro 15            | [9deaff7467](https://linux-hardware.org/?probe=9deaff7467) | Feb 02, 2023 |
| Lenovo        | ThinkPad 13 20J10046US      | [85b9d54087](https://linux-hardware.org/?probe=85b9d54087) | Feb 02, 2023 |
| Apple         | MacBook5,2                  | [b8c8ed32e5](https://linux-hardware.org/?probe=b8c8ed32e5) | Feb 01, 2023 |
| Samsung       | 600B4B/600B5B               | [d3cf4446d5](https://linux-hardware.org/?probe=d3cf4446d5) | Feb 01, 2023 |
| Apple         | MacBookAir7,2               | [352c998936](https://linux-hardware.org/?probe=352c998936) | Feb 01, 2023 |
| Toshiba       | Satellite P775              | [c03f7668ac](https://linux-hardware.org/?probe=c03f7668ac) | Feb 01, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [ac78478b3b](https://linux-hardware.org/?probe=ac78478b3b) | Feb 01, 2023 |
| HUAWEI        | HLYL-WXX9                   | [6e8d45f76b](https://linux-hardware.org/?probe=6e8d45f76b) | Jan 31, 2023 |
| HP            | Notebook                    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| HP            | Laptop 17-bs0xx             | [ed57a59e39](https://linux-hardware.org/?probe=ed57a59e39) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| Sony          | PCG-Z1VA(UC)                | [db4f48132e](https://linux-hardware.org/?probe=db4f48132e) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| Dell          | Inspiron 3581               | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| Acer          | Aspire 7750G                | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| Dell          | Latitude E7440              | [9ba078f6ab](https://linux-hardware.org/?probe=9ba078f6ab) | Jan 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| MSI           | Creator 17 B11UE            | [fcf56cfe4d](https://linux-hardware.org/?probe=fcf56cfe4d) | Jan 27, 2023 |
| Dell          | Latitude 5420               | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| Google        | Careena                     | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [a780c8d844](https://linux-hardware.org/?probe=a780c8d844) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [e6a1506275](https://linux-hardware.org/?probe=e6a1506275) | Jan 25, 2023 |
| Apple         | MacBookPro10,1              | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Dell          | Vostro 5470                 | [bfd4198155](https://linux-hardware.org/?probe=bfd4198155) | Jan 25, 2023 |
| Samsung       | R710                        | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| HP            | ZBook 15 G3                 | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [5c7625e3f8](https://linux-hardware.org/?probe=5c7625e3f8) | Jan 23, 2023 |
| Fujitsu       | LIFEBOOK S751               | [ff727a3560](https://linux-hardware.org/?probe=ff727a3560) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | [df0676ac87](https://linux-hardware.org/?probe=df0676ac87) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| Dell          | G3 3579                     | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | [68847eb1e6](https://linux-hardware.org/?probe=68847eb1e6) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [15dde971f3](https://linux-hardware.org/?probe=15dde971f3) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
| Google        | Phaser                      | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Dell          | Latitude 5501               | [d31f972a20](https://linux-hardware.org/?probe=d31f972a20) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3SX0... | [3e08ab25c6](https://linux-hardware.org/?probe=3e08ab25c6) | Jan 20, 2023 |
| Dell          | Latitude E6540              | [34c018d211](https://linux-hardware.org/?probe=34c018d211) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [80cb1c8239](https://linux-hardware.org/?probe=80cb1c8239) | Jan 19, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Insyde        | Braswell                    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [20749dc72f](https://linux-hardware.org/?probe=20749dc72f) | Jan 19, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [368ed9c856](https://linux-hardware.org/?probe=368ed9c856) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| HP            | Compaq 6910p                | [61d820a040](https://linux-hardware.org/?probe=61d820a040) | Jan 18, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Dell          | Latitude 5500               | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [99e10e5d0f](https://linux-hardware.org/?probe=99e10e5d0f) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [624f47d1e3](https://linux-hardware.org/?probe=624f47d1e3) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Positivo      | CHT14B                      | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [a09ace045e](https://linux-hardware.org/?probe=a09ace045e) | Jan 15, 2023 |
| Apple         | MacBookAir5,1               | [f316bddcf2](https://linux-hardware.org/?probe=f316bddcf2) | Jan 15, 2023 |
| Acer          | Swift SF314-510G            | [b929f53536](https://linux-hardware.org/?probe=b929f53536) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [0ec206a07d](https://linux-hardware.org/?probe=0ec206a07d) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | [7e3b019181](https://linux-hardware.org/?probe=7e3b019181) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | [576a509224](https://linux-hardware.org/?probe=576a509224) | Jan 14, 2023 |
| HP            | Laptop 14s-dk0xxx           | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [0899d995dd](https://linux-hardware.org/?probe=0899d995dd) | Jan 14, 2023 |
| Apple         | MacBookPro12,1              | [1402c185c7](https://linux-hardware.org/?probe=1402c185c7) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| HONOR         | HLYL-WXX9                   | [e5b02d94cd](https://linux-hardware.org/?probe=e5b02d94cd) | Jan 14, 2023 |
| Dell          | Inspiron 11 - 3147          | [7193100d05](https://linux-hardware.org/?probe=7193100d05) | Jan 14, 2023 |
| HP            | Pavilion g6                 | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| Panasonic     | CFSZ6-2                     | [7a9f534294](https://linux-hardware.org/?probe=7a9f534294) | Jan 13, 2023 |
| Unknown       | Unknown                     | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| HP            | ProBook 445 G7              | [baf20b6914](https://linux-hardware.org/?probe=baf20b6914) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| Dell          | Latitude 3320               | [f10d2a0741](https://linux-hardware.org/?probe=f10d2a0741) | Jan 13, 2023 |
| Dell          | Latitude 3320               | [613d7d50eb](https://linux-hardware.org/?probe=613d7d50eb) | Jan 13, 2023 |
| HP            | Compaq 6735b                | [01878ee027](https://linux-hardware.org/?probe=01878ee027) | Jan 12, 2023 |
| Dell          | Inspiron 3521               | [694d5be301](https://linux-hardware.org/?probe=694d5be301) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [2316d5dc8b](https://linux-hardware.org/?probe=2316d5dc8b) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [856d91c1ca](https://linux-hardware.org/?probe=856d91c1ca) | Jan 12, 2023 |
| Gateway       | M-6854m                     | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Acer          | Swift SF314-56              | [46aebbe972](https://linux-hardware.org/?probe=46aebbe972) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| HP            | ProBook 430 G5              | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Aquarius      | NS585                       | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| HP            | Mini 110-1000               | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| Aquarius      | NS585                       | [2d37eb6524](https://linux-hardware.org/?probe=2d37eb6524) | Jan 10, 2023 |
| MPMAN         | CONVERTER 102               | [cc1eb56fbc](https://linux-hardware.org/?probe=cc1eb56fbc) | Jan 10, 2023 |
| HP            | 15                          | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | [8d0b4a504d](https://linux-hardware.org/?probe=8d0b4a504d) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e85e91a7f2](https://linux-hardware.org/?probe=e85e91a7f2) | Jan 09, 2023 |
| Acer          | Aspire one 1-131            | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| ASUSTek       | K53U                        | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Digma         | Pro Fortis M DN15P3-8CXN... | [077fd44029](https://linux-hardware.org/?probe=077fd44029) | Jan 08, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX1... | [3c35917c78](https://linux-hardware.org/?probe=3c35917c78) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Acer          | Aspire 7745G                | [9119962d1f](https://linux-hardware.org/?probe=9119962d1f) | Jan 07, 2023 |
| Gigabyte      | G5 GE                       | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| Dell          | Latitude 2110               | [9910f8985b](https://linux-hardware.org/?probe=9910f8985b) | Jan 07, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | [28c9b60939](https://linux-hardware.org/?probe=28c9b60939) | Jan 07, 2023 |
| TUXEDO        | Aura 15 Gen1                | [fa91397209](https://linux-hardware.org/?probe=fa91397209) | Jan 07, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Toshiba       | Satellite C55Dt-A           | [f3cfb5dbb5](https://linux-hardware.org/?probe=f3cfb5dbb5) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [d069cbd46b](https://linux-hardware.org/?probe=d069cbd46b) | Jan 06, 2023 |
| &#er &&       | Aspire 5100                 | [26da9e8ee1](https://linux-hardware.org/?probe=26da9e8ee1) | Jan 06, 2023 |
| Google        | Stout                       | [5ef816b9a6](https://linux-hardware.org/?probe=5ef816b9a6) | Jan 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [4442f2c14a](https://linux-hardware.org/?probe=4442f2c14a) | Jan 05, 2023 |
| Acer          | Extensa 2540                | [ec8b49d7b0](https://linux-hardware.org/?probe=ec8b49d7b0) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | [fdf6545b20](https://linux-hardware.org/?probe=fdf6545b20) | Jan 04, 2023 |
| HP            | 255 G8 Notebook PC          | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| Dell          | Inspiron 5566               | [258412ac0a](https://linux-hardware.org/?probe=258412ac0a) | Jan 03, 2023 |
| ASUSTek       | F5SL                        | [67882c0f69](https://linux-hardware.org/?probe=67882c0f69) | Jan 02, 2023 |
| ASUSTek       | F5SL                        | [42ef1fbf40](https://linux-hardware.org/?probe=42ef1fbf40) | Jan 02, 2023 |
| Acer          | Aspire V3-574G              | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| Acer          | Aspire ES1-711              | [735e062168](https://linux-hardware.org/?probe=735e062168) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [70c50fe035](https://linux-hardware.org/?probe=70c50fe035) | Jan 02, 2023 |
| MSI           | GE75 Raider 8SG             | [b6fa9be350](https://linux-hardware.org/?probe=b6fa9be350) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b54f3aab7b](https://linux-hardware.org/?probe=b54f3aab7b) | Jan 02, 2023 |
| HP            | 250 G8 Notebook PC          | [42e877ed10](https://linux-hardware.org/?probe=42e877ed10) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [8d4934bc09](https://linux-hardware.org/?probe=8d4934bc09) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| ASUSTek       | ZenBook UX333FN_U3300FN     | [750a40a3cc](https://linux-hardware.org/?probe=750a40a3cc) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [2396307897](https://linux-hardware.org/?probe=2396307897) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| Panasonic     | CF-54-2                     | [dfe3d2e06b](https://linux-hardware.org/?probe=dfe3d2e06b) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| Dell          | Inspiron 5566               | [9eadf42d31](https://linux-hardware.org/?probe=9eadf42d31) | Jan 01, 2023 |
| Samsung       | 940XFG                      | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| HP            | 255 G3                      | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Toshiba       | Satellite L775-12V          | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| MACHCREATO... | AB                          | [52a6beb872](https://linux-hardware.org/?probe=52a6beb872) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| HP            | ProBook 6570b               | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| HP            | Pavilion g7                 | [444363b7ec](https://linux-hardware.org/?probe=444363b7ec) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| HP            | ProBook 6470b               | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [321cc72064](https://linux-hardware.org/?probe=321cc72064) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Notebook      | L14xMU                      | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Dell          | Inspiron 1012               | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Exo           | Smart Serie M               | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [29a54c4976](https://linux-hardware.org/?probe=29a54c4976) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Medion        | E122X                       | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [096d4fc8c2](https://linux-hardware.org/?probe=096d4fc8c2) | Dec 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c5f2f2db53](https://linux-hardware.org/?probe=c5f2f2db53) | Dec 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [6ac6e552a8](https://linux-hardware.org/?probe=6ac6e552a8) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| HP            | Laptop 15-dy2xxx            | [df787f1286](https://linux-hardware.org/?probe=df787f1286) | Dec 24, 2022 |
| HP            | Laptop 15-dy2xxx            | [0a2ed74cfd](https://linux-hardware.org/?probe=0a2ed74cfd) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [baae52327d](https://linux-hardware.org/?probe=baae52327d) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [bc5d48b831](https://linux-hardware.org/?probe=bc5d48b831) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [fde483d476](https://linux-hardware.org/?probe=fde483d476) | Dec 23, 2022 |
| Dell          | Latitude E7440              | [a746012ffd](https://linux-hardware.org/?probe=a746012ffd) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [9e5c4705fa](https://linux-hardware.org/?probe=9e5c4705fa) | Dec 23, 2022 |
| Dell          | Latitude D630               | [8175d003ce](https://linux-hardware.org/?probe=8175d003ce) | Dec 23, 2022 |
| Google        | Reks                        | [ecee690e6e](https://linux-hardware.org/?probe=ecee690e6e) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Google        | Reks                        | [58b1b4cac1](https://linux-hardware.org/?probe=58b1b4cac1) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [297651d437](https://linux-hardware.org/?probe=297651d437) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [79b015dcea](https://linux-hardware.org/?probe=79b015dcea) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | [958ee9d145](https://linux-hardware.org/?probe=958ee9d145) | Dec 23, 2022 |
| Dell          | G3 3590                     | [d75d9e6663](https://linux-hardware.org/?probe=d75d9e6663) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Acer          | Aspire 4750                 | [3256c282db](https://linux-hardware.org/?probe=3256c282db) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Dell          | Inspiron 5490               | [1c424b5f55](https://linux-hardware.org/?probe=1c424b5f55) | Dec 23, 2022 |
| Unknown       | Unknown                     | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| Toshiba       | Satellite C55Dt-A           | [67294324c5](https://linux-hardware.org/?probe=67294324c5) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [c6d28912f0](https://linux-hardware.org/?probe=c6d28912f0) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [1a14f26bd3](https://linux-hardware.org/?probe=1a14f26bd3) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [db77bb7a3f](https://linux-hardware.org/?probe=db77bb7a3f) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [d2278ed94d](https://linux-hardware.org/?probe=d2278ed94d) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | [09ba8ccf48](https://linux-hardware.org/?probe=09ba8ccf48) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [f4e79df709](https://linux-hardware.org/?probe=f4e79df709) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | [2c3febf6fa](https://linux-hardware.org/?probe=2c3febf6fa) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [cddffa9123](https://linux-hardware.org/?probe=cddffa9123) | Dec 22, 2022 |
| Dell          | Latitude E7440              | [5f911806c8](https://linux-hardware.org/?probe=5f911806c8) | Dec 22, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Dell          | Latitude D630               | [e1106d8868](https://linux-hardware.org/?probe=e1106d8868) | Dec 22, 2022 |
| Packard Be... | DOT S                       | [c26f1d77e6](https://linux-hardware.org/?probe=c26f1d77e6) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| Dell          | G3 3590                     | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [b4e828bef3](https://linux-hardware.org/?probe=b4e828bef3) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [28013105ef](https://linux-hardware.org/?probe=28013105ef) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [056d76bae8](https://linux-hardware.org/?probe=056d76bae8) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [6b202d6cc2](https://linux-hardware.org/?probe=6b202d6cc2) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Dell          | G3 3590                     | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [cd4fa20e66](https://linux-hardware.org/?probe=cd4fa20e66) | Dec 20, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e676fe186f](https://linux-hardware.org/?probe=e676fe186f) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [658e730bd3](https://linux-hardware.org/?probe=658e730bd3) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| ASUSTek       | T100TA                      | [1dc546e14a](https://linux-hardware.org/?probe=1dc546e14a) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| HP            | 255 G8 Notebook PC          | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| ASUSTek       | 900SD                       | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| Acer          | TravelMate P253             | [97d650e93f](https://linux-hardware.org/?probe=97d650e93f) | Dec 18, 2022 |
| Dell          | Latitude E6530              | [198a9bc936](https://linux-hardware.org/?probe=198a9bc936) | Dec 18, 2022 |
| HP            | Pavilion g7                 | [9829a799a0](https://linux-hardware.org/?probe=9829a799a0) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [f9e4638f19](https://linux-hardware.org/?probe=f9e4638f19) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Dell          | Latitude E4310              | [ace267f47c](https://linux-hardware.org/?probe=ace267f47c) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | [218654b079](https://linux-hardware.org/?probe=218654b079) | Dec 17, 2022 |
| Dell          | Inspiron 14 5425            | [e7d96ccda5](https://linux-hardware.org/?probe=e7d96ccda5) | Dec 17, 2022 |
| HP            | Notebook                    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| Unknown       | Unknown                     | [208016df07](https://linux-hardware.org/?probe=208016df07) | Dec 17, 2022 |
| Acer          | TravelMate P253             | [80188fd5bf](https://linux-hardware.org/?probe=80188fd5bf) | Dec 16, 2022 |
| Dell          | Inspiron 7590               | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Google        | Laser14                     | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| Intel         | powered classmate PC        | [e0401225a2](https://linux-hardware.org/?probe=e0401225a2) | Dec 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Unknown       | T3 MRD                      | [909e1a1604](https://linux-hardware.org/?probe=909e1a1604) | Dec 15, 2022 |
| Google        | Cyan                        | [2b9f20b7da](https://linux-hardware.org/?probe=2b9f20b7da) | Dec 15, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | [f7590c1a07](https://linux-hardware.org/?probe=f7590c1a07) | Dec 15, 2022 |
| Dell          | Latitude 3490               | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Acer          | Aspire 5738                 | [c0c4581310](https://linux-hardware.org/?probe=c0c4581310) | Dec 14, 2022 |
| Apple         | MacBook6,1                  | [f19d464a26](https://linux-hardware.org/?probe=f19d464a26) | Dec 14, 2022 |
| ASUSTek       | M3N                         | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| ASUSTek       | M3N                         | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| Dell          | Latitude 5520               | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| ASUSTek       | G75VW                       | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| Exo           | Smart Serie M               | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Google        | Terra                       | [765deab389](https://linux-hardware.org/?probe=765deab389) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [95dc27194a](https://linux-hardware.org/?probe=95dc27194a) | Dec 12, 2022 |
| MSI           | GP73 Leopard 8RD            | [548de8bdae](https://linux-hardware.org/?probe=548de8bdae) | Dec 12, 2022 |
| Acer          | Aspire A515-56              | [5437de2b1b](https://linux-hardware.org/?probe=5437de2b1b) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Google        | Enguarde                    | [60cce42479](https://linux-hardware.org/?probe=60cce42479) | Dec 12, 2022 |
| Lenovo        | ThinkPad R61e 7650DHU       | [138f60e67c](https://linux-hardware.org/?probe=138f60e67c) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [99c965b83f](https://linux-hardware.org/?probe=99c965b83f) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Acer          | Nitro AN515-51              | [918c340b04](https://linux-hardware.org/?probe=918c340b04) | Dec 12, 2022 |
| Lenovo        | ThinkPad T470 20HES6HC00    | [ca9d609d9d](https://linux-hardware.org/?probe=ca9d609d9d) | Dec 12, 2022 |
| HP            | Laptop 15-db1xxx            | [3dcbd61f9e](https://linux-hardware.org/?probe=3dcbd61f9e) | Dec 12, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Lenovo        | G770 20089                  | [f6f1441538](https://linux-hardware.org/?probe=f6f1441538) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [754e028997](https://linux-hardware.org/?probe=754e028997) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | [fb2f97325d](https://linux-hardware.org/?probe=fb2f97325d) | Dec 11, 2022 |
| Dell          | Latitude 5480               | [01c96ca524](https://linux-hardware.org/?probe=01c96ca524) | Dec 11, 2022 |
| Dell          | Inspiron 13-5368            | [b4ea41e00f](https://linux-hardware.org/?probe=b4ea41e00f) | Dec 11, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [89e7835b90](https://linux-hardware.org/?probe=89e7835b90) | Dec 11, 2022 |
| Notebook      | NJ50_70CU                   | [f77f39af95](https://linux-hardware.org/?probe=f77f39af95) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| HP            | Laptop 15s-du3xxx           | [400a0b555d](https://linux-hardware.org/?probe=400a0b555d) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [e0aca47e1b](https://linux-hardware.org/?probe=e0aca47e1b) | Dec 10, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [5f72ad2758](https://linux-hardware.org/?probe=5f72ad2758) | Dec 10, 2022 |
| Google        | Peppy                       | [59f9af1c52](https://linux-hardware.org/?probe=59f9af1c52) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| SANTECH       | NHx0DB,DE                   | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Lenovo        | ThinkPad 13 20J10046US      | [170accb6cc](https://linux-hardware.org/?probe=170accb6cc) | Dec 09, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| HUAWEI        | KLVL-WXXW                   | [adea8bc8d8](https://linux-hardware.org/?probe=adea8bc8d8) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| ASUSTek       | N750JV                      | [e06c6025f3](https://linux-hardware.org/?probe=e06c6025f3) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [09de0ec660](https://linux-hardware.org/?probe=09de0ec660) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [b0f77fed1f](https://linux-hardware.org/?probe=b0f77fed1f) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [e56fd20ec9](https://linux-hardware.org/?probe=e56fd20ec9) | Dec 08, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Lenovo        | ThinkPad X230 2320CTO       | [b74f2893d0](https://linux-hardware.org/?probe=b74f2893d0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| HP            | EliteBook 2570p             | [fc7d866c16](https://linux-hardware.org/?probe=fc7d866c16) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [03aba4d315](https://linux-hardware.org/?probe=03aba4d315) | Dec 06, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [4dc49eeb10](https://linux-hardware.org/?probe=4dc49eeb10) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0e42e5cbeb](https://linux-hardware.org/?probe=0e42e5cbeb) | Dec 06, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b72cdbdb8](https://linux-hardware.org/?probe=5b72cdbdb8) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [3027fc2c2f](https://linux-hardware.org/?probe=3027fc2c2f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | [a07d55ca40](https://linux-hardware.org/?probe=a07d55ca40) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| ASUSTek       | PU403UA                     | [20007b4296](https://linux-hardware.org/?probe=20007b4296) | Dec 05, 2022 |
| Acer          | Aspire A315-23G             | [41e6f6a3fa](https://linux-hardware.org/?probe=41e6f6a3fa) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f5be4eb37d](https://linux-hardware.org/?probe=f5be4eb37d) | Dec 04, 2022 |
| Toshiba       | dynabook R63/P              | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b475911aaf](https://linux-hardware.org/?probe=b475911aaf) | Dec 03, 2022 |
| Dell          | Inspiron 15-5578            | [61f5950e07](https://linux-hardware.org/?probe=61f5950e07) | Dec 03, 2022 |
| HP            | Laptop 15-da0xxx            | [9053b5cb8a](https://linux-hardware.org/?probe=9053b5cb8a) | Dec 03, 2022 |
| ASUSTek       | S500CA                      | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| Unknown       | Unknown                     | [40917baf56](https://linux-hardware.org/?probe=40917baf56) | Dec 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| Lenovo        | ThinkPad X280 20KE0015BR    | [4c65d4e572](https://linux-hardware.org/?probe=4c65d4e572) | Dec 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [c99bd4ef76](https://linux-hardware.org/?probe=c99bd4ef76) | Dec 03, 2022 |
| Dell          | Inspiron 5566               | [54e06d37fc](https://linux-hardware.org/?probe=54e06d37fc) | Dec 02, 2022 |
| ASUSTek       | N750JV                      | [0fc50d63c4](https://linux-hardware.org/?probe=0fc50d63c4) | Dec 02, 2022 |
| Dell          | Latitude 5591               | [f5735acca7](https://linux-hardware.org/?probe=f5735acca7) | Dec 02, 2022 |
| HP            | Unknown                     | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| Aquarius      | NS585                       | [bbd3bd3ca6](https://linux-hardware.org/?probe=bbd3bd3ca6) | Dec 02, 2022 |
| Aquarius      | NS585                       | [50222418e5](https://linux-hardware.org/?probe=50222418e5) | Dec 02, 2022 |
| Aquarius      | NS585                       | [d55d40681f](https://linux-hardware.org/?probe=d55d40681f) | Dec 02, 2022 |
| Aquarius      | NS585                       | [9013a1cce6](https://linux-hardware.org/?probe=9013a1cce6) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [38ce706249](https://linux-hardware.org/?probe=38ce706249) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [546f2b82c9](https://linux-hardware.org/?probe=546f2b82c9) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [000d536e95](https://linux-hardware.org/?probe=000d536e95) | Dec 02, 2022 |
| HP            | 620                         | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [674157de54](https://linux-hardware.org/?probe=674157de54) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| HP            | Pavilion dv5                | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Notebook      | RIM2520                     | [5f66abbb8b](https://linux-hardware.org/?probe=5f66abbb8b) | Nov 30, 2022 |
| HP            | Elite x2 1011 G1 Tablet     | [1a00258de3](https://linux-hardware.org/?probe=1a00258de3) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| Dell          | Latitude 7490               | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| Dell          | XPS 15 9500                 | [9c87ab493e](https://linux-hardware.org/?probe=9c87ab493e) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [1e52ea39e4](https://linux-hardware.org/?probe=1e52ea39e4) | Nov 28, 2022 |
| Lenovo        | ThinkPad X301 2776LEG       | [ebaea0c805](https://linux-hardware.org/?probe=ebaea0c805) | Nov 28, 2022 |
| Dell          | Precision M6400             | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| HP            | ProBook 450 G5              | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| ASUSTek       | GL752VW                     | [edc0678b85](https://linux-hardware.org/?probe=edc0678b85) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| Tactus        | GeoBook 140                 | [e3f4d734da](https://linux-hardware.org/?probe=e3f4d734da) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [32bfa52fc1](https://linux-hardware.org/?probe=32bfa52fc1) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [3d1b8f282a](https://linux-hardware.org/?probe=3d1b8f282a) | Nov 27, 2022 |
| HP            | Laptop 15s-fq5xxx           | [f1ef96a2e6](https://linux-hardware.org/?probe=f1ef96a2e6) | Nov 26, 2022 |
| MSI           | Creator 15M A9SD            | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| HP            | Laptop 15-da3xxx            | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | 255 G7 Notebook PC          | [8c389cf5d6](https://linux-hardware.org/?probe=8c389cf5d6) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| Lenovo        | ThinkPad T495 20NJS0L100    | [1e9e7f34df](https://linux-hardware.org/?probe=1e9e7f34df) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [bede773ce4](https://linux-hardware.org/?probe=bede773ce4) | Nov 26, 2022 |
| ASUSTek       | A6R                         | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| Dell          | Latitude E7240              | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| HP            | Pavilion TS Sleekbook 14    | [26440cddbb](https://linux-hardware.org/?probe=26440cddbb) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| ASUSTek       | GL752VW                     | [2dfd7f3926](https://linux-hardware.org/?probe=2dfd7f3926) | Nov 25, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [f82ee02c50](https://linux-hardware.org/?probe=f82ee02c50) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| HP            | 255 G7 Notebook PC          | [f5a6bcf0fb](https://linux-hardware.org/?probe=f5a6bcf0fb) | Nov 24, 2022 |
| ASUSTek       | X551CAP                     | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [8b4ad51670](https://linux-hardware.org/?probe=8b4ad51670) | Nov 24, 2022 |
| Dell          | Latitude 5310               | [a5265c8a0e](https://linux-hardware.org/?probe=a5265c8a0e) | Nov 24, 2022 |
| Dell          | Latitude E6500              | [73d607f9e1](https://linux-hardware.org/?probe=73d607f9e1) | Nov 24, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [299634697d](https://linux-hardware.org/?probe=299634697d) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ef378a135b](https://linux-hardware.org/?probe=ef378a135b) | Nov 24, 2022 |
| Aquarius      | NS585                       | [d54530cbcb](https://linux-hardware.org/?probe=d54530cbcb) | Nov 24, 2022 |
| Aquarius      | NS585                       | [64d9bcbcde](https://linux-hardware.org/?probe=64d9bcbcde) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| Lenovo        | ThinkPad T495 20NK000UUS    | [0e8c0e6f07](https://linux-hardware.org/?probe=0e8c0e6f07) | Nov 23, 2022 |
| Lenovo        | ThinkPad T490 20N3S8T211    | [97ea649145](https://linux-hardware.org/?probe=97ea649145) | Nov 23, 2022 |
| HP            | ProBook 450 G7              | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| Dell          | Latitude E6530              | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| MPMAN         | CONVERTER 102               | [cab847edc0](https://linux-hardware.org/?probe=cab847edc0) | Nov 23, 2022 |
| HP            | Compaq 6720s                | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [363e0b0149](https://linux-hardware.org/?probe=363e0b0149) | Nov 22, 2022 |
| Unknown       | Unknown                     | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Dell          | Latitude 3420               | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| Unknown       | Wiren Board rev. 7.3.1 (... | [1f9ccab914](https://linux-hardware.org/?probe=1f9ccab914) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [71c464a407](https://linux-hardware.org/?probe=71c464a407) | Nov 22, 2022 |
| HP            | Pavilion Sleekbook 15       | [add4f71bc0](https://linux-hardware.org/?probe=add4f71bc0) | Nov 22, 2022 |
| HP            | ENVY 6                      | [feb348843e](https://linux-hardware.org/?probe=feb348843e) | Nov 22, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| HP            | 255 G6 Notebook PC          | [149cee1720](https://linux-hardware.org/?probe=149cee1720) | Nov 22, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 3053      | 64.25%  |
| Debian 10                       | 851       | 17.91%  |
| Debian Testing                  | 357       | 7.51%   |
| Debian                          | 151       | 3.18%   |
| Debian 9                        | 146       | 3.07%   |
| Debian Unstable                 | 128       | 2.69%   |
| Debian 11-updates               | 27        | 0.57%   |
| Debian 12                       | 21        | 0.44%   |
| Debian 8                        | 10        | 0.21%   |
| Debian Sid                      | 4         | 0.08%   |
| Debian Testing/unstable         | 2         | 0.04%   |
| Debian Testing-proposed-updates | 1         | 0.02%   |
| Debian 99                       | 1         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Debian | 4615      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 583       | 11.14%  |
| 5.10.0-10-amd64        | 491       | 9.38%   |
| 5.10.0-20-amd64        | 214       | 4.09%   |
| 5.10.0-18-amd64        | 175       | 3.34%   |
| 5.10.0-9-amd64         | 172       | 3.29%   |
| 5.10.0-7-amd64         | 171       | 3.27%   |
| 5.10.0-21-amd64        | 171       | 3.27%   |
| 5.10.0-16-amd64        | 166       | 3.17%   |
| 5.10.0-19-amd64        | 161       | 3.08%   |
| 5.10.0-13-amd64        | 149       | 2.85%   |
| 5.10.0-11-amd64        | 103       | 1.97%   |
| 4.19.0-9-amd64         | 85        | 1.62%   |
| 4.19.0-6-amd64         | 82        | 1.57%   |
| 5.10.0-14-amd64        | 80        | 1.53%   |
| 5.10.0-17-amd64        | 73        | 1.39%   |
| 4.19.0-13-amd64        | 69        | 1.32%   |
| 4.19.0-8-amd64         | 68        | 1.3%    |
| 4.19.0-16-amd64        | 52        | 0.99%   |
| 4.19.0-10-amd64        | 52        | 0.99%   |
| 5.15.0-2-amd64         | 51        | 0.97%   |
| 5.10.0-2-amd64         | 49        | 0.94%   |
| 5.10.0-15-amd64        | 49        | 0.94%   |
| 4.19.0-12-amd64        | 47        | 0.9%    |
| 4.19.0-14-amd64        | 42        | 0.8%    |
| 5.10.0-6-amd64         | 41        | 0.78%   |
| 5.10.0-12-amd64        | 40        | 0.76%   |
| 4.19.0-17-amd64        | 40        | 0.76%   |
| 4.9.0-8-amd64          | 39        | 0.75%   |
| 5.18.0-2-amd64         | 31        | 0.59%   |
| 5.10.0-3-amd64         | 31        | 0.59%   |
| 6.0.0-6-amd64          | 27        | 0.52%   |
| 5.19.0-1-amd64         | 27        | 0.52%   |
| 5.10.0-13-686-pae      | 26        | 0.5%    |
| 5.4.0-4-amd64          | 25        | 0.48%   |
| 5.17.0-1-amd64         | 24        | 0.46%   |
| 5.18.0-4-amd64         | 23        | 0.44%   |
| 6.1.0-5-amd64          | 22        | 0.42%   |
| 6.0.0-2-amd64          | 22        | 0.42%   |
| 5.19.0-2-amd64         | 22        | 0.42%   |
| 5.18.0-0.deb11.4-amd64 | 22        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 2896      | 59.34%  |
| 4.19.0  | 652       | 13.36%  |
| 6.0.0   | 136       | 2.79%   |
| 4.9.0   | 120       | 2.46%   |
| 5.18.0  | 106       | 2.17%   |
| 5.15.0  | 91        | 1.86%   |
| 6.1.0   | 85        | 1.74%   |
| 5.9.0   | 74        | 1.52%   |
| 5.19.0  | 68        | 1.39%   |
| 5.16.0  | 68        | 1.39%   |
| 5.4.0   | 64        | 1.31%   |
| 5.7.0   | 59        | 1.21%   |
| 5.8.0   | 56        | 1.15%   |
| 5.14.0  | 53        | 1.09%   |
| 5.6.0   | 45        | 0.92%   |
| 5.17.0  | 39        | 0.8%    |
| 5.3.0   | 19        | 0.39%   |
| 5.5.0   | 16        | 0.33%   |
| 5.2.0   | 12        | 0.25%   |
| 4.18.0  | 12        | 0.25%   |
| 3.16.0  | 8         | 0.16%   |
| 5.12.0  | 6         | 0.12%   |
| 5.10.10 | 4         | 0.08%   |
| 5.3.5   | 3         | 0.06%   |
| 5.17.5  | 3         | 0.06%   |
| 5.13.19 | 3         | 0.06%   |
| 5.13.0  | 3         | 0.06%   |
| 5.11.0  | 3         | 0.06%   |
| 5.10.60 | 3         | 0.06%   |
| 5.0.0   | 3         | 0.06%   |
| 6.0.2   | 2         | 0.04%   |
| 5.8.2   | 2         | 0.04%   |
| 5.8.16  | 2         | 0.04%   |
| 5.4.21  | 2         | 0.04%   |
| 5.2.5   | 2         | 0.04%   |
| 5.18.15 | 2         | 0.04%   |
| 5.17.11 | 2         | 0.04%   |
| 5.16.12 | 2         | 0.04%   |
| 5.15.5  | 2         | 0.04%   |
| 5.15.35 | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2920      | 59.96%  |
| 4.19    | 656       | 13.47%  |
| 6.0     | 142       | 2.92%   |
| 4.9     | 123       | 2.53%   |
| 5.18    | 111       | 2.28%   |
| 5.15    | 111       | 2.28%   |
| 6.1     | 89        | 1.83%   |
| 5.9     | 80        | 1.64%   |
| 5.4     | 76        | 1.56%   |
| 5.19    | 73        | 1.5%    |
| 5.16    | 72        | 1.48%   |
| 5.7     | 62        | 1.27%   |
| 5.8     | 61        | 1.25%   |
| 5.14    | 58        | 1.19%   |
| 5.6     | 49        | 1.01%   |
| 5.17    | 48        | 0.99%   |
| 5.3     | 24        | 0.49%   |
| 5.5     | 19        | 0.39%   |
| 5.2     | 18        | 0.37%   |
| 5.13    | 12        | 0.25%   |
| 4.18    | 12        | 0.25%   |
| 5.12    | 9         | 0.18%   |
| 5.11    | 9         | 0.18%   |
| 3.16    | 8         | 0.16%   |
| 3.10    | 4         | 0.08%   |
| 6.2     | 3         | 0.06%   |
| 5.1     | 3         | 0.06%   |
| 5.0     | 3         | 0.06%   |
| 4.17    | 2         | 0.04%   |
| 4.15    | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 5.4.104 | 1         | 0.02%   |
| 5.15.6  | 1         | 0.02%   |
| 4.4     | 1         | 0.02%   |
| 4.20    | 1         | 0.02%   |
| 4.13    | 1         | 0.02%   |
| 4.12    | 1         | 0.02%   |
| 4.10    | 1         | 0.02%   |
| 3.8     | 1         | 0.02%   |
| 3.0     | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 4399      | 95.3%   |
| i686    | 204       | 4.42%   |
| armv7l  | 9         | 0.19%   |
| aarch64 | 3         | 0.06%   |
| i586    | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1240      | 26.25%  |
| Unknown           | 1214      | 25.7%   |
| XFCE              | 613       | 12.98%  |
| KDE5              | 580       | 12.28%  |
| MATE              | 198       | 4.19%   |
| X-Cinnamon        | 164       | 3.47%   |
| LXDE              | 146       | 3.09%   |
| Cinnamon          | 142       | 3.01%   |
| KDE               | 111       | 2.35%   |
| i3                | 89        | 1.88%   |
| LXQt              | 68        | 1.44%   |
| GNOME Flashback   | 35        | 0.74%   |
| lightdm-xsession  | 25        | 0.53%   |
| openbox           | 14        | 0.3%    |
| Budgie            | 14        | 0.3%    |
| trinity           | 12        | 0.25%   |
| GNOME Classic     | 10        | 0.21%   |
| sway              | 5         | 0.11%   |
| awesome           | 5         | 0.11%   |
| ICEWM             | 4         | 0.08%   |
| Fluxbox           | 4         | 0.08%   |
| Enlightenment     | 4         | 0.08%   |
| bspwm             | 4         | 0.08%   |
| DWM               | 3         | 0.06%   |
| Cutefish          | 3         | 0.06%   |
| xmonad            | 2         | 0.04%   |
| x-session-manager | 2         | 0.04%   |
| Unity             | 2         | 0.04%   |
| KDE4              | 2         | 0.04%   |
| default           | 2         | 0.04%   |
| wmaker-common     | 1         | 0.02%   |
| matchbox          | 1         | 0.02%   |
| jwm               | 1         | 0.02%   |
| i3-gaps           | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| Deepin            | 1         | 0.02%   |
| BunsenLabs        | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 2638      | 56.03%  |
| Unknown     | 981       | 20.84%  |
| Wayland     | 903       | 19.18%  |
| Tty         | 183       | 3.89%   |
| Unspecified | 2         | 0.04%   |
| Web         | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1878      | 39.7%   |
| GDM     | 928       | 19.62%  |
| LightDM | 763       | 16.13%  |
| SDDM    | 564       | 11.92%  |
| TDM     | 310       | 6.55%   |
| GDM3    | 231       | 4.88%   |
| XDM     | 18        | 0.38%   |
| SLiM    | 13        | 0.27%   |
| NODM    | 10        | 0.21%   |
| KDM     | 8         | 0.17%   |
| LXDM    | 3         | 0.06%   |
| Ly      | 2         | 0.04%   |
| GREETD  | 2         | 0.04%   |
| WDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1395      | 29.74%  |
| Unknown | 987       | 21.04%  |
| ru_RU   | 317       | 6.76%   |
| de_DE   | 297       | 6.33%   |
| fr_FR   | 250       | 5.33%   |
| en_GB   | 198       | 4.22%   |
| pt_BR   | 154       | 3.28%   |
| es_ES   | 136       | 2.9%    |
| it_IT   | 127       | 2.71%   |
| pl_PL   | 93        | 1.98%   |
| en_CA   | 53        | 1.13%   |
| C       | 49        | 1.04%   |
| es_MX   | 45        | 0.96%   |
| en_AU   | 42        | 0.9%    |
| en_IN   | 38        | 0.81%   |
| zh_CN   | 37        | 0.79%   |
| es_AR   | 30        | 0.64%   |
| es_CL   | 28        | 0.6%    |
| en_IE   | 26        | 0.55%   |
| hu_HU   | 24        | 0.51%   |
| de_CH   | 19        | 0.41%   |
| pt_PT   | 18        | 0.38%   |
| fi_FI   | 17        | 0.36%   |
| nl_NL   | 15        | 0.32%   |
| es_VE   | 15        | 0.32%   |
| cs_CZ   | 15        | 0.32%   |
| en_NZ   | 14        | 0.3%    |
| de_AT   | 13        | 0.28%   |
| sv_SE   | 12        | 0.26%   |
| ja_JP   | 12        | 0.26%   |
| es_CO   | 12        | 0.26%   |
| en_ZA   | 11        | 0.23%   |
| tr_TR   | 10        | 0.21%   |
| ko_KR   | 10        | 0.21%   |
| fr_BE   | 10        | 0.21%   |
| en_SG   | 10        | 0.21%   |
| ru_UA   | 8         | 0.17%   |
| ca_ES   | 8         | 0.17%   |
| uk_UA   | 7         | 0.15%   |
| da_DK   | 7         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2880      | 61.75%  |
| BIOS | 1784      | 38.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3266      | 70.4%   |
| Overlay | 1049      | 22.61%  |
| Btrfs   | 146       | 3.15%   |
| Unknown | 78        | 1.68%   |
| Xfs     | 43        | 0.93%   |
| Ext2    | 14        | 0.3%    |
| Zfs     | 13        | 0.28%   |
| Rootfs  | 10        | 0.22%   |
| Tmpfs   | 9         | 0.19%   |
| Ext3    | 6         | 0.13%   |
| Aufs    | 4         | 0.09%   |
| F2fs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 2899      | 61.83%  |
| Unknown | 896       | 19.11%  |
| MBR     | 894       | 19.07%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3826      | 81.94%  |
| Yes       | 843       | 18.06%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3459      | 74.12%  |
| Yes       | 1208      | 25.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1016      | 22.02%  |
| Hewlett-Packard        | 674       | 14.6%   |
| Dell                   | 660       | 14.3%   |
| Apple                  | 643       | 13.93%  |
| ASUSTek Computer       | 426       | 9.23%   |
| Acer                   | 295       | 6.39%   |
| Google                 | 141       | 3.06%   |
| Toshiba                | 76        | 1.65%   |
| MSI                    | 73        | 1.58%   |
| Samsung Electronics    | 71        | 1.54%   |
| Aquarius               | 44        | 0.95%   |
| Sony                   | 40        | 0.87%   |
| HUAWEI                 | 39        | 0.85%   |
| Unknown                | 39        | 0.85%   |
| Notebook               | 28        | 0.61%   |
| Fujitsu                | 23        | 0.5%    |
| Medion                 | 15        | 0.33%   |
| Panasonic              | 14        | 0.3%    |
| TUXEDO                 | 13        | 0.28%   |
| Alienware              | 13        | 0.28%   |
| Intel                  | 12        | 0.26%   |
| IBM                    | 12        | 0.26%   |
| Timi                   | 11        | 0.24%   |
| Positivo               | 11        | 0.24%   |
| Packard Bell           | 10        | 0.22%   |
| Clevo                  | 9         | 0.2%    |
| LG Electronics         | 8         | 0.17%   |
| Fujitsu Siemens        | 8         | 0.17%   |
| Razer                  | 7         | 0.15%   |
| SLIMBOOK               | 6         | 0.13%   |
| PC Specialist          | 6         | 0.13%   |
| GPU Company            | 6         | 0.13%   |
| Gigabyte Technology    | 6         | 0.13%   |
| System76               | 5         | 0.11%   |
| HONOR                  | 5         | 0.11%   |
| Chuwi                  | 5         | 0.11%   |
| Avell High Performance | 5         | 0.11%   |
| Schenker               | 4         | 0.09%   |
| Insyde                 | 4         | 0.09%   |
| Gateway                | 4         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 354       | 7.67%   |
| Apple MacBookAir7,2                   | 77        | 1.67%   |
| Apple MacBookAir7,1                   | 77        | 1.67%   |
| Google Enguarde                       | 74        | 1.6%    |
| Apple MacBook2,1                      | 56        | 1.21%   |
| Unknown                               | 51        | 1.11%   |
| Aquarius NS585                        | 44        | 0.95%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.52%   |
| HP Notebook                           | 23        | 0.5%    |
| Google Terra                          | 23        | 0.5%    |
| Apple MacBook4,1                      | 23        | 0.5%    |
| HP Pavilion g6                        | 17        | 0.37%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.35%   |
| Acer Aspire A315-23                   | 16        | 0.35%   |
| ASUS 1005HA                           | 15        | 0.33%   |
| Dell Latitude E7440                   | 13        | 0.28%   |
| HP EliteBook 8460p                    | 11        | 0.24%   |
| Google Reks                           | 11        | 0.24%   |
| HP Laptop 15-db0xxx                   | 10        | 0.22%   |
| HP EliteBook 840 G3                   | 9         | 0.2%    |
| HP 250 G7 Notebook PC                 | 9         | 0.2%    |
| Dell XPS 13 9310                      | 9         | 0.2%    |
| Dell Latitude E6430                   | 9         | 0.2%    |
| Dell Latitude E6420                   | 9         | 0.2%    |
| Dell Latitude 7480                    | 9         | 0.2%    |
| Samsung 300E4C/300E5C/300E7C          | 8         | 0.17%   |
| HP Pavilion Notebook                  | 8         | 0.17%   |
| Dell Latitude E7450                   | 8         | 0.17%   |
| Dell Latitude E6330                   | 8         | 0.17%   |
| Dell Inspiron 5570                    | 8         | 0.17%   |
| Dell Inspiron 15-3567                 | 8         | 0.17%   |
| Lenovo IdeaPad S145-15API 81V7        | 7         | 0.15%   |
| HP Stream Notebook PC 13              | 7         | 0.15%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 7         | 0.15%   |
| HP Pavilion dv6                       | 7         | 0.15%   |
| HP Laptop 15-db1xxx                   | 7         | 0.15%   |
| HP Laptop 15-bw0xx                    | 7         | 0.15%   |
| HP EliteBook 8470p                    | 7         | 0.15%   |
| HP EliteBook 840 G8 Notebook PC       | 7         | 0.15%   |
| HP 255 G8 Notebook PC                 | 7         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 670       | 14.52%  |
| Apple MacBook5    | 355       | 7.69%   |
| Dell Latitude     | 251       | 5.44%   |
| Dell Inspiron     | 200       | 4.33%   |
| Acer Aspire       | 193       | 4.18%   |
| Lenovo IdeaPad    | 177       | 3.84%   |
| Apple MacBookAir7 | 154       | 3.34%   |
| HP EliteBook      | 139       | 3.01%   |
| HP Pavilion       | 103       | 2.23%   |
| HP ProBook        | 88        | 1.91%   |
| HP Laptop         | 88        | 1.91%   |
| Google Enguarde   | 74        | 1.6%    |
| Dell XPS          | 70        | 1.52%   |
| ASUS VivoBook     | 62        | 1.34%   |
| Toshiba Satellite | 59        | 1.28%   |
| Dell Vostro       | 56        | 1.21%   |
| Apple MacBook2    | 56        | 1.21%   |
| Dell Precision    | 53        | 1.15%   |
| Unknown           | 51        | 1.11%   |
| Aquarius NS585    | 44        | 0.95%   |
| HP Compaq         | 41        | 0.89%   |
| ASUS ZenBook      | 31        | 0.67%   |
| HP ZBook          | 30        | 0.65%   |
| HP 250            | 29        | 0.63%   |
| Lenovo Legion     | 26        | 0.56%   |
| ASUS ASUS         | 24        | 0.52%   |
| Acer Nitro        | 24        | 0.52%   |
| Lenovo ThinkBook  | 23        | 0.5%    |
| HP Notebook       | 23        | 0.5%    |
| Google Terra      | 23        | 0.5%    |
| Apple MacBook4    | 23        | 0.5%    |
| Acer Swift        | 22        | 0.48%   |
| Fujitsu LIFEBOOK  | 20        | 0.43%   |
| HP 255            | 19        | 0.41%   |
| Acer TravelMate   | 19        | 0.41%   |
| ASUS ROG          | 17        | 0.37%   |
| HP OMEN           | 16        | 0.35%   |
| HP ENVY           | 16        | 0.35%   |
| ASUS 1005HA       | 15        | 0.33%   |
| HP Stream         | 14        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 487       | 10.55%  |
| 2019    | 461       | 9.99%   |
| 2020    | 413       | 8.95%   |
| 2021    | 388       | 8.41%   |
| 2018    | 296       | 6.41%   |
| 2016    | 293       | 6.35%   |
| 2012    | 291       | 6.31%   |
| 2011    | 289       | 6.26%   |
| 2017    | 280       | 6.07%   |
| 2015    | 278       | 6.02%   |
| 2013    | 230       | 4.98%   |
| 2014    | 200       | 4.33%   |
| 2022    | 180       | 3.9%    |
| 2010    | 169       | 3.66%   |
| 2008    | 137       | 2.97%   |
| 2007    | 128       | 2.77%   |
| 2006    | 33        | 0.72%   |
| 2005    | 23        | 0.5%    |
| Unknown | 14        | 0.3%    |
| 2004    | 11        | 0.24%   |
| 2003    | 11        | 0.24%   |
| 2002    | 2         | 0.04%   |
| 2023    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 4615      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4267      | 92.02%  |
| Enabled  | 370       | 7.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 4460      | 96.62%  |
| Yes  | 156       | 3.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1200      | 25.76%  |
| 3.01-4.0    | 913       | 19.6%   |
| 16.01-24.0  | 739       | 15.86%  |
| 8.01-16.0   | 705       | 15.13%  |
| 1.01-2.0    | 550       | 11.81%  |
| 32.01-64.0  | 257       | 5.52%   |
| 2.01-3.0    | 98        | 2.1%    |
| 0.51-1.0    | 79        | 1.7%    |
| 64.01-256.0 | 49        | 1.05%   |
| 24.01-32.0  | 46        | 0.99%   |
| 0.01-0.5    | 21        | 0.45%   |
| Unknown     | 2         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1951      | 39.44%  |
| 2.01-3.0   | 1003      | 20.27%  |
| 4.01-8.0   | 644       | 13.02%  |
| 3.01-4.0   | 514       | 10.39%  |
| 0.51-1.0   | 507       | 10.25%  |
| 8.01-16.0  | 171       | 3.46%   |
| 0.01-0.5   | 128       | 2.59%   |
| 16.01-24.0 | 14        | 0.28%   |
| Unknown    | 7         | 0.14%   |
| 32.01-64.0 | 4         | 0.08%   |
| 24.01-32.0 | 3         | 0.06%   |
| 0          | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3664      | 78.31%  |
| 2      | 867       | 18.53%  |
| 3      | 97        | 2.07%   |
| 0      | 29        | 0.62%   |
| 4      | 16        | 0.34%   |
| 5      | 4         | 0.09%   |
| 7      | 2         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2998      | 64.71%  |
| Yes       | 1635      | 35.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3771      | 81.43%  |
| No        | 860       | 18.57%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4527      | 98.01%  |
| No        | 92        | 1.99%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3716      | 79.97%  |
| No        | 931       | 20.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1255      | 27.02%  |
| Germany     | 435       | 9.36%   |
| Russia      | 366       | 7.88%   |
| France      | 317       | 6.82%   |
| Brazil      | 229       | 4.93%   |
| Spain       | 194       | 4.18%   |
| Italy       | 173       | 3.72%   |
| Poland      | 132       | 2.84%   |
| UK          | 102       | 2.2%    |
| Netherlands | 77        | 1.66%   |
| Canada      | 74        | 1.59%   |
| Mexico      | 65        | 1.4%    |
| Switzerland | 64        | 1.38%   |
| India       | 57        | 1.23%   |
| Ukraine     | 53        | 1.14%   |
| China       | 53        | 1.14%   |
| Argentina   | 51        | 1.1%    |
| Australia   | 47        | 1.01%   |
| Sweden      | 42        | 0.9%    |
| Portugal    | 41        | 0.88%   |
| Turkey      | 40        | 0.86%   |
| Hungary     | 40        | 0.86%   |
| Belgium     | 39        | 0.84%   |
| Chile       | 34        | 0.73%   |
| Czechia     | 33        | 0.71%   |
| Austria     | 33        | 0.71%   |
| Finland     | 31        | 0.67%   |
| Greece      | 30        | 0.65%   |
| Norway      | 28        | 0.6%    |
| Romania     | 25        | 0.54%   |
| Indonesia   | 23        | 0.5%    |
| Ireland     | 22        | 0.47%   |
| Colombia    | 22        | 0.47%   |
| Japan       | 21        | 0.45%   |
| Venezuela   | 18        | 0.39%   |
| New Zealand | 18        | 0.39%   |
| Thailand    | 16        | 0.34%   |
| Denmark     | 16        | 0.34%   |
| Bulgaria    | 16        | 0.34%   |
| Croatia     | 14        | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 616       | 12.55%  |
| Dover-Foxcroft    | 229       | 4.66%   |
| Voronezh          | 149       | 3.03%   |
| Paris             | 60        | 1.22%   |
| Moscow            | 53        | 1.08%   |
| St Petersburg     | 52        | 1.06%   |
| Berlin            | 44        | 0.9%    |
| Madrid            | 37        | 0.75%   |
| Seville           | 36        | 0.73%   |
| Sao Paulo         | 35        | 0.71%   |
| Warsaw            | 32        | 0.65%   |
| Munich            | 32        | 0.65%   |
| Vienna            | 25        | 0.51%   |
| Milan             | 24        | 0.49%   |
| Amsterdam         | 24        | 0.49%   |
| Hamburg           | 23        | 0.47%   |
| Barcelona         | 21        | 0.43%   |
| Prague            | 19        | 0.39%   |
| London            | 19        | 0.39%   |
| Frankfurt am Main | 18        | 0.37%   |
| Zurich            | 17        | 0.35%   |
| Mexico City       | 17        | 0.35%   |
| Helsinki          | 17        | 0.35%   |
| Budapest          | 17        | 0.35%   |
| Athens            | 17        | 0.35%   |
| Sydney            | 16        | 0.33%   |
| Istanbul          | 16        | 0.33%   |
| Lisbon            | 14        | 0.29%   |
| Dublin            | 14        | 0.29%   |
| Brasília         | 14        | 0.29%   |
| Singapore         | 13        | 0.26%   |
| Perm              | 13        | 0.26%   |
| Zagreb            | 12        | 0.24%   |
| Toronto           | 11        | 0.22%   |
| Rome              | 11        | 0.22%   |
| New York          | 11        | 0.22%   |
| Leipzig           | 11        | 0.22%   |
| Cologne           | 11        | 0.22%   |
| Buenos Aires      | 11        | 0.22%   |
| Blizniew          | 11        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 813       | 1032   | 14.67%  |
| WDC                       | 618       | 760    | 11.15%  |
| Seagate                   | 520       | 620    | 9.38%   |
| Toshiba                   | 427       | 477    | 7.71%   |
| Unknown                   | 366       | 471    | 6.61%   |
| Kingston                  | 300       | 364    | 5.41%   |
| Fujitsu                   | 289       | 296    | 5.22%   |
| SanDisk                   | 271       | 330    | 4.89%   |
| Crucial                   | 211       | 256    | 3.81%   |
| SK hynix                  | 205       | 251    | 3.7%    |
| Apple                     | 183       | 222    | 3.3%    |
| Hitachi                   | 159       | 183    | 2.87%   |
| Intel                     | 128       | 156    | 2.31%   |
| A-DATA Technology         | 126       | 218    | 2.27%   |
| Micron Technology         | 122       | 132    | 2.2%    |
| HGST                      | 108       | 127    | 1.95%   |
| KIOXIA                    | 50        | 63     | 0.9%    |
| LITEON                    | 34        | 41     | 0.61%   |
| China                     | 31        | 34     | 0.56%   |
| Unknown                   | 29        | 30     | 0.52%   |
| Transcend                 | 27        | 34     | 0.49%   |
| PNY                       | 24        | 28     | 0.43%   |
| Phison                    | 23        | 31     | 0.42%   |
| Intenso                   | 23        | 32     | 0.42%   |
| Silicon Motion            | 22        | 25     | 0.4%    |
| SPCC                      | 21        | 25     | 0.38%   |
| SABRENT                   | 18        | 19     | 0.32%   |
| Patriot                   | 17        | 19     | 0.31%   |
| SSSTC                     | 16        | 16     | 0.29%   |
| LITEONIT                  | 16        | 18     | 0.29%   |
| Team                      | 15        | 17     | 0.27%   |
| JMicron Technology        | 14        | 14     | 0.25%   |
| GOODRAM                   | 13        | 15     | 0.23%   |
| OCZ                       | 12        | 14     | 0.22%   |
| Micron/Crucial Technology | 11        | 11     | 0.2%    |
| LDLC                      | 9         | 9      | 0.16%   |
| ASMT                      | 9         | 15     | 0.16%   |
| Plextor                   | 8         | 8      | 0.14%   |
| Netac                     | 8         | 13     | 0.14%   |
| Lenovo                    | 8         | 10     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB       | 237       | 4.18%   |
| Apple SSD AP0128H 121GB              | 77        | 1.36%   |
| Apple SSD SM0128G 121GB              | 72        | 1.27%   |
| Seagate ST1000LM035-1RK172 1TB       | 67        | 1.18%   |
| Kingston SA400S37240G 240GB SSD      | 61        | 1.08%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 56        | 0.99%   |
| Kingston SA400S37120G 120GB SSD      | 53        | 0.94%   |
| Toshiba MK1655GSXF 160GB             | 52        | 0.92%   |
| A-DATA SU800 512GB SSD               | 46        | 0.81%   |
| Toshiba MQ01ABD100 1TB               | 43        | 0.76%   |
| Toshiba MK1653GSX 160GB              | 43        | 0.76%   |
| HGST HTS721010A9E630 1TB             | 40        | 0.71%   |
| Unknown AGND3R  16GB                 | 39        | 0.69%   |
| Toshiba MQ01ABF050 500GB             | 34        | 0.6%    |
| Toshiba MQ04ABF100 1TB               | 33        | 0.58%   |
| Crucial CT500MX500SSD1 500GB         | 32        | 0.56%   |
| Unknown MMC Card  32GB               | 31        | 0.55%   |
| Unknown HAG2e  16GB                  | 31        | 0.55%   |
| Unknown                              | 29        | 0.51%   |
| Samsung SSD 850 EVO 250GB            | 28        | 0.49%   |
| Samsung SSD 860 EVO 500GB            | 27        | 0.48%   |
| Seagate ST500LT012-1DG142 500GB      | 26        | 0.46%   |
| Seagate ST1000LM048-2E7172 1TB       | 26        | 0.46%   |
| Samsung SSD 970 EVO Plus 1TB         | 26        | 0.46%   |
| Unknown SDW16G  16GB                 | 25        | 0.44%   |
| Kingston SA400S37480G 480GB SSD      | 25        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB          | 24        | 0.42%   |
| Samsung SSD 860 EVO 1TB              | 22        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD     | 22        | 0.39%   |
| Unknown MMC Card  64GB               | 21        | 0.37%   |
| Samsung SSD 860 EVO 250GB            | 21        | 0.37%   |
| Seagate ST9500325AS 500GB            | 20        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 20        | 0.35%   |
| Crucial CT240BX500SSD1 240GB         | 20        | 0.35%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 19        | 0.34%   |
| Samsung MZVLB512HBJQ-000L7 512GB     | 19        | 0.34%   |
| WDC WD10SPZX-24Z10 1TB               | 18        | 0.32%   |
| Seagate ST1000LM049-2GH172 1TB       | 18        | 0.32%   |
| SABRENT Disk 160GB                   | 18        | 0.32%   |
| HGST HTS725050A7E630 500GB           | 18        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 502       | 598    | 27.52%  |
| WDC                 | 358       | 410    | 19.63%  |
| Toshiba             | 316       | 347    | 17.32%  |
| Fujitsu             | 289       | 296    | 15.84%  |
| Hitachi             | 159       | 183    | 8.72%   |
| HGST                | 108       | 127    | 5.92%   |
| Samsung Electronics | 33        | 35     | 1.81%   |
| SABRENT             | 18        | 19     | 0.99%   |
| Unknown             | 13        | 16     | 0.71%   |
| ASMT                | 6         | 11     | 0.33%   |
| IBM/Hitachi         | 5         | 6      | 0.27%   |
| Intenso             | 4         | 5      | 0.22%   |
| SILICONMOTION       | 2         | 2      | 0.11%   |
| Apple               | 2         | 2      | 0.11%   |
| USB3.0              | 1         | 1      | 0.05%   |
| Unknown (CF)        | 1         | 1      | 0.05%   |
| SAGE                | 1         | 1      | 0.05%   |
| QNAP                | 1         | 2      | 0.05%   |
| PHD 3.0             | 1         | 1      | 0.05%   |
| Maxone              | 1         | 1      | 0.05%   |
| IBM                 | 1         | 1      | 0.05%   |
| Hewlett-Packard     | 1         | 1      | 0.05%   |
| ASMT109x            | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 367       | 462    | 20.39%  |
| Kingston            | 237       | 297    | 13.17%  |
| SanDisk             | 198       | 248    | 11%     |
| Crucial             | 189       | 231    | 10.5%   |
| Apple               | 96        | 103    | 5.33%   |
| A-DATA Technology   | 93        | 172    | 5.17%   |
| WDC                 | 70        | 92     | 3.89%   |
| Micron Technology   | 51        | 55     | 2.83%   |
| SK hynix            | 41        | 49     | 2.28%   |
| Intel               | 40        | 44     | 2.22%   |
| China               | 31        | 34     | 1.72%   |
| Toshiba             | 30        | 33     | 1.67%   |
| LITEON              | 28        | 33     | 1.56%   |
| Transcend           | 25        | 32     | 1.39%   |
| PNY                 | 20        | 23     | 1.11%   |
| Intenso             | 17        | 24     | 0.94%   |
| SPCC                | 16        | 19     | 0.89%   |
| Patriot             | 16        | 18     | 0.89%   |
| LITEONIT            | 16        | 18     | 0.89%   |
| Team                | 14        | 16     | 0.78%   |
| OCZ                 | 12        | 14     | 0.67%   |
| GOODRAM             | 10        | 12     | 0.56%   |
| Plextor             | 8         | 8      | 0.44%   |
| Netac               | 8         | 13     | 0.44%   |
| LDLC                | 8         | 8      | 0.44%   |
| JMicron Technology  | 8         | 8      | 0.44%   |
| KingSpec            | 7         | 7      | 0.39%   |
| KingDian            | 6         | 6      | 0.33%   |
| Corsair             | 6         | 6      | 0.33%   |
| Unknown             | 6         | 6      | 0.33%   |
| Seagate             | 5         | 5      | 0.28%   |
| Lexar               | 5         | 6      | 0.28%   |
| Apacer              | 5         | 5      | 0.28%   |
| TO Exter            | 4         | 4      | 0.22%   |
| Hewlett-Packard     | 4         | 6      | 0.22%   |
| Gigabyte Technology | 4         | 4      | 0.22%   |
| Dogfish             | 4         | 7      | 0.22%   |
| BIWIN               | 4         | 4      | 0.22%   |
| ASUS-PHISON         | 4         | 5      | 0.22%   |
| ZTC                 | 3         | 7      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1773      | 2067   | 33.37%  |
| SSD     | 1680      | 2248   | 31.62%  |
| NVMe    | 1417      | 1846   | 26.67%  |
| MMC     | 390       | 497    | 7.34%   |
| Unknown | 53        | 59     | 1%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3117      | 4162   | 61.25%  |
| NVMe | 1416      | 1841   | 27.82%  |
| MMC  | 390       | 497    | 7.66%   |
| SAS  | 166       | 217    | 3.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2441      | 3070   | 71.73%  |
| 0.51-1.0   | 860       | 1116   | 25.27%  |
| 1.01-2.0   | 79        | 99     | 2.32%   |
| 4.01-10.0  | 15        | 19     | 0.44%   |
| 3.01-4.0   | 4         | 6      | 0.12%   |
| 2.01-3.0   | 4         | 5      | 0.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1334      | 27.93%  |
| 251-500        | 970       | 20.31%  |
| Unknown        | 786       | 16.46%  |
| 501-1000       | 611       | 12.79%  |
| 51-100         | 312       | 6.53%   |
| 1001-2000      | 252       | 5.28%   |
| 1-20           | 232       | 4.86%   |
| 21-50          | 176       | 3.69%   |
| 2001-3000      | 56        | 1.17%   |
| More than 3000 | 47        | 0.98%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1718      | 34.85%  |
| Unknown        | 786       | 15.94%  |
| 101-250        | 633       | 12.84%  |
| 21-50          | 622       | 12.62%  |
| 51-100         | 511       | 10.37%  |
| 251-500        | 337       | 6.84%   |
| 501-1000       | 209       | 4.24%   |
| 1001-2000      | 71        | 1.44%   |
| More than 3000 | 18        | 0.37%   |
| 2001-3000      | 14        | 0.28%   |
| 0              | 11        | 0.22%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB        | 25        | 25     | 5.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 11        | 13     | 2.37%   |
| Hitachi HTS543216L9SA02 160GB         | 11        | 11     | 2.37%   |
| Seagate ST9500325AS 500GB             | 10        | 10     | 2.15%   |
| Toshiba MK1653GSX 160GB               | 9         | 9      | 1.94%   |
| Toshiba MQ01ABD100 1TB                | 8         | 8      | 1.72%   |
| Toshiba MK1655GSXF 160GB              | 8         | 8      | 1.72%   |
| Seagate ST9500420AS 500GB             | 7         | 7      | 1.51%   |
| Seagate ST500LM021-1KJ152 500GB       | 6         | 6      | 1.29%   |
| Seagate ST1000LM035-1RK172 1TB        | 6         | 7      | 1.29%   |
| Hitachi HTS545050B9A300 500GB         | 6         | 6      | 1.29%   |
| Seagate ST500LT012-9WS142 500GB       | 5         | 6      | 1.08%   |
| Hitachi HTS542512K9SA00 120GB         | 5         | 6      | 1.08%   |
| HGST HTS725050A7E630 500GB            | 5         | 6      | 1.08%   |
| WDC WD1600BUDT-63DPZY0 160GB          | 4         | 4      | 0.86%   |
| Toshiba MQ01ABF050 500GB              | 4         | 4      | 0.86%   |
| Seagate ST500LM000-SSHD-8GB           | 4         | 4      | 0.86%   |
| Seagate ST320LT007-9ZV142 320GB       | 4         | 6      | 0.86%   |
| Hitachi HTS547575A9E384 752GB         | 4         | 4      | 0.86%   |
| HGST HTS541010A9E680 1TB              | 4         | 4      | 0.86%   |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 0.65%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 3         | 3      | 0.65%   |
| SK hynix HFS256G39MND-2300A 256GB SSD | 3         | 4      | 0.65%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 0.65%   |
| Seagate ST9250315AS 250GB             | 3         | 4      | 0.65%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 0.65%   |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 0.65%   |
| Kingston SA400S37240G 240GB SSD       | 3         | 3      | 0.65%   |
| Kingston SA400S37120G 120GB SSD       | 3         | 4      | 0.65%   |
| Hitachi HTS547550A9E384 500GB         | 3         | 3      | 0.65%   |
| Hitachi HTS542516K9SA00 160GB         | 3         | 3      | 0.65%   |
| HGST HTS721010A9E630 1TB              | 3         | 4      | 0.65%   |
| Crucial CT275MX300SSD1 275GB          | 3         | 3      | 0.65%   |
| WDC WD7500BPVX-22JC3T0 752GB          | 2         | 2      | 0.43%   |
| WDC WD7500BPKT-75PK4T0 752GB          | 2         | 2      | 0.43%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 2         | 2      | 0.43%   |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 4      | 0.43%   |
| WDC WD10JPVX-22JC3T0 1TB              | 2         | 2      | 0.43%   |
| WDC WD10JPCX-24UE4T0 1TB              | 2         | 3      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 99        | 108    | 21.34%  |
| Hitachi             | 72        | 77     | 15.52%  |
| Toshiba             | 55        | 56     | 11.85%  |
| WDC                 | 42        | 45     | 9.05%   |
| Fujitsu             | 39        | 39     | 8.41%   |
| Samsung Electronics | 25        | 27     | 5.39%   |
| HGST                | 23        | 25     | 4.96%   |
| SK hynix            | 17        | 18     | 3.66%   |
| Kingston            | 15        | 16     | 3.23%   |
| SanDisk             | 13        | 15     | 2.8%    |
| Micron Technology   | 12        | 12     | 2.59%   |
| Intel               | 10        | 11     | 2.16%   |
| A-DATA Technology   | 9         | 10     | 1.94%   |
| Crucial             | 8         | 9      | 1.72%   |
| LITEONIT            | 3         | 4      | 0.65%   |
| LITEON              | 3         | 3      | 0.65%   |
| IBM/Hitachi         | 2         | 2      | 0.43%   |
| Corsair             | 2         | 2      | 0.43%   |
| Unknown             | 2         | 2      | 0.43%   |
| Team                | 1         | 1      | 0.22%   |
| SSSTC               | 1         | 1      | 0.22%   |
| ShiJi               | 1         | 1      | 0.22%   |
| Plextor             | 1         | 1      | 0.22%   |
| Lenovo              | 1         | 1      | 0.22%   |
| KingSpec            | 1         | 1      | 0.22%   |
| KingDian            | 1         | 1      | 0.22%   |
| JMicron Technology  | 1         | 1      | 0.22%   |
| IBM                 | 1         | 1      | 0.22%   |
| GOODRAM             | 1         | 1      | 0.22%   |
| DGM                 | 1         | 1      | 0.22%   |
| China               | 1         | 1      | 0.22%   |
| Apple               | 1         | 1      | 0.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 99        | 108    | 28.78%  |
| Hitachi             | 72        | 77     | 20.93%  |
| Toshiba             | 54        | 55     | 15.7%   |
| WDC                 | 41        | 44     | 11.92%  |
| Fujitsu             | 39        | 39     | 11.34%  |
| HGST                | 23        | 25     | 6.69%   |
| Samsung Electronics | 13        | 13     | 3.78%   |
| IBM/Hitachi         | 2         | 2      | 0.58%   |
| IBM                 | 1         | 1      | 0.29%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 341       | 364    | 73.97%  |
| SSD  | 105       | 115    | 22.78%  |
| NVMe | 15        | 15     | 3.25%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 14.29%  |
| Toshiba MK6465GSX 640GB                         | 1         | 1      | 14.29%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 14.29%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 14.29%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 14.29%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 28.57%  |
| Samsung Electronics | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Hitachi             | 1         | 2      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 3159      | 4219   | 63.7%   |
| Detected | 1334      | 1995   | 26.9%   |
| Malfunc  | 458       | 494    | 9.24%   |
| Failed   | 7         | 8      | 0.14%   |
| Limited  | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2791      | 54.54%  |
| Samsung Electronics              | 514       | 10.04%  |
| AMD                              | 436       | 8.52%   |
| Nvidia                           | 376       | 7.35%   |
| SanDisk                          | 249       | 4.87%   |
| SK hynix                         | 153       | 2.99%   |
| Toshiba America Info Systems     | 86        | 1.68%   |
| Apple                            | 84        | 1.64%   |
| Micron Technology                | 71        | 1.39%   |
| Kingston Technology Company      | 63        | 1.23%   |
| KIOXIA                           | 51        | 1%      |
| Phison Electronics               | 40        | 0.78%   |
| ADATA Technology                 | 40        | 0.78%   |
| Silicon Motion                   | 33        | 0.64%   |
| Micron/Crucial Technology        | 33        | 0.64%   |
| Solid State Storage Technology   | 20        | 0.39%   |
| Union Memory (Shenzhen)          | 12        | 0.23%   |
| Silicon Integrated Systems [SiS] | 12        | 0.23%   |
| Lite-On Technology               | 7         | 0.14%   |
| Realtek Semiconductor            | 6         | 0.12%   |
| Shenzhen Longsys Electronics     | 5         | 0.1%    |
| Lenovo                           | 5         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 4         | 0.08%   |
| ULi Electronics                  | 3         | 0.06%   |
| Silicon Image                    | 3         | 0.06%   |
| Seagate Technology               | 3         | 0.06%   |
| Jiangsu Huacun Elec.             | 3         | 0.06%   |
| Biwin Storage Technology         | 3         | 0.06%   |
| VIA Technologies                 | 2         | 0.04%   |
| Marvell Technology Group         | 2         | 0.04%   |
| ASMedia Technology               | 2         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.02%   |
| JMicron Technology               | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 379       | 6.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 364       | 6.64%   |
| Nvidia MCP79 AHCI Controller                                                     | 362       | 6.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 311       | 5.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 219       | 3.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 211       | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 197       | 3.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 141       | 2.57%   |
| Intel Volume Management Device NVMe RAID Controller                              | 131       | 2.39%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 116       | 2.12%   |
| Samsung NVMe SSD Controller 980                                                  | 108       | 1.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 101       | 1.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 98        | 1.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 93        | 1.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 88        | 1.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 85        | 1.55%   |
| Samsung Electronics SATA controller                                              | 83        | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 80        | 1.46%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 80        | 1.46%   |
| Apple S1X NVMe Controller                                                        | 78        | 1.42%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 76        | 1.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 75        | 1.37%   |
| Micron NVMe Storage Controller                                                   | 71        | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                            | 68        | 1.24%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 62        | 1.13%   |
| Intel Tiger Lake-LP SATA Controller                                              | 61        | 1.11%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 58        | 1.06%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 57        | 1.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 56        | 1.02%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 55        | 1%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 54        | 0.99%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 47        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 46        | 0.84%   |
| Intel SSD 660P Series                                                            | 44        | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 44        | 0.8%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 42        | 0.77%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 41        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 38        | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 36        | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 33        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3184      | 59.65%  |
| NVMe | 1424      | 26.68%  |
| IDE  | 380       | 7.12%   |
| RAID | 349       | 6.54%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 3967      | 85.94%  |
| AMD          | 631       | 13.67%  |
| ARM          | 11        | 0.24%   |
| CentaurHauls | 5         | 0.11%   |
| Unknown      | 2         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 356       | 7.7%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 146       | 3.16%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 94        | 2.03%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 81        | 1.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 74        | 1.6%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 73        | 1.58%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 69        | 1.49%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 65        | 1.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 65        | 1.41%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 61        | 1.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 60        | 1.3%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 60        | 1.3%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 58        | 1.26%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 55        | 1.19%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 51        | 1.1%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 48        | 1.04%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 48        | 1.04%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 42        | 0.91%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 40        | 0.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 39        | 0.84%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 35        | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 33        | 0.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 33        | 0.71%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 30        | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 28        | 0.61%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.61%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 27        | 0.58%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 27        | 0.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 26        | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 25        | 0.54%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 25        | 0.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 24        | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 24        | 0.52%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 24        | 0.52%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.52%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1132      | 24.51%  |
| Intel Core i7           | 877       | 18.99%  |
| Intel Core 2 Duo        | 538       | 11.65%  |
| Other                   | 361       | 7.82%   |
| Intel Celeron           | 335       | 7.25%   |
| Intel Core i3           | 308       | 6.67%   |
| AMD Ryzen 5             | 178       | 3.85%   |
| Intel Atom              | 134       | 2.9%    |
| AMD Ryzen 7             | 109       | 2.36%   |
| Intel Pentium           | 84        | 1.82%   |
| Intel Core 2            | 71        | 1.54%   |
| AMD Ryzen 7 PRO         | 46        | 1%      |
| Intel Pentium M         | 33        | 0.71%   |
| AMD A6                  | 31        | 0.67%   |
| Intel Pentium Dual-Core | 26        | 0.56%   |
| AMD A4                  | 26        | 0.56%   |
| Intel Genuine           | 23        | 0.5%    |
| AMD Ryzen 3             | 22        | 0.48%   |
| Intel Pentium Dual      | 20        | 0.43%   |
| AMD A8                  | 20        | 0.43%   |
| AMD Ryzen 5 PRO         | 17        | 0.37%   |
| AMD Ryzen 9             | 16        | 0.35%   |
| AMD E1                  | 16        | 0.35%   |
| AMD A10                 | 15        | 0.32%   |
| Intel Celeron M         | 13        | 0.28%   |
| Intel Pentium Silver    | 11        | 0.24%   |
| AMD E2                  | 11        | 0.24%   |
| AMD E                   | 11        | 0.24%   |
| Intel Core i9           | 10        | 0.22%   |
| Intel Pentium 4         | 9         | 0.19%   |
| Intel Core m3           | 7         | 0.15%   |
| AMD A12                 | 7         | 0.15%   |
| AMD Turion 64 X2 Mobile | 6         | 0.13%   |
| AMD Athlon              | 6         | 0.13%   |
| Intel Xeon              | 5         | 0.11%   |
| Intel Celeron Dual-Core | 5         | 0.11%   |
| ARM ARMv7               | 5         | 0.11%   |
| AMD C-60                | 5         | 0.11%   |
| AMD C-50                | 5         | 0.11%   |
| Intel Mobile Pentium 4  | 4         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2569      | 55.62%  |
| 4      | 1349      | 29.21%  |
| 6      | 244       | 5.28%   |
| 1      | 196       | 4.24%   |
| 8      | 191       | 4.14%   |
| 14     | 26        | 0.56%   |
| 10     | 24        | 0.52%   |
| 12     | 18        | 0.39%   |
| 16     | 1         | 0.02%   |
| 3      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4614      | 99.98%  |
| 2      | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3049      | 66%     |
| 1      | 1570      | 33.98%  |
| 4      | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4426      | 95.86%  |
| 32-bit         | 118       | 2.56%   |
| Unknown        | 71        | 1.54%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 963       | 20.41%  |
| 0x1067a    | 446       | 9.45%   |
| 0x306d4    | 250       | 5.3%    |
| 0x306a9    | 223       | 4.73%   |
| 0x206a7    | 204       | 4.32%   |
| 0x806ec    | 186       | 3.94%   |
| 0x806c1    | 170       | 3.6%    |
| 0x806e9    | 128       | 2.71%   |
| 0x806ea    | 125       | 2.65%   |
| 0x40651    | 122       | 2.59%   |
| 0x30678    | 120       | 2.54%   |
| 0x406e3    | 110       | 2.33%   |
| 0x306c3    | 79        | 1.67%   |
| 0x906ea    | 75        | 1.59%   |
| 0x406c4    | 68        | 1.44%   |
| 0x6f6      | 67        | 1.42%   |
| 0xa0652    | 65        | 1.38%   |
| 0x20655    | 64        | 1.36%   |
| 0x0a50000c | 56        | 1.19%   |
| 0x08600106 | 55        | 1.17%   |
| 0x08108109 | 50        | 1.06%   |
| 0x706e5    | 47        | 1%      |
| 0x10676    | 46        | 0.97%   |
| 0x08608103 | 46        | 0.97%   |
| 0x08108102 | 45        | 0.95%   |
| 0x906eb    | 44        | 0.93%   |
| 0x906a3    | 42        | 0.89%   |
| 0x6fd      | 40        | 0.85%   |
| 0x806eb    | 37        | 0.78%   |
| 0x706a8    | 36        | 0.76%   |
| 0x106ca    | 36        | 0.76%   |
| 0x506e3    | 34        | 0.72%   |
| 0x906e9    | 33        | 0.7%    |
| 0x106c2    | 33        | 0.7%    |
| 0x0600611a | 31        | 0.66%   |
| 0x06006705 | 30        | 0.64%   |
| 0x506c9    | 29        | 0.61%   |
| 0x6d8      | 28        | 0.59%   |
| 0x20652    | 24        | 0.51%   |
| 0x906a4    | 23        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 853       | 18.46%  |
| Penryn           | 527       | 11.4%   |
| IvyBridge        | 298       | 6.45%   |
| Broadwell        | 283       | 6.12%   |
| SandyBridge      | 278       | 6.02%   |
| Haswell          | 271       | 5.86%   |
| Silvermont       | 241       | 5.22%   |
| TigerLake        | 208       | 4.5%    |
| Skylake          | 205       | 4.44%   |
| Core             | 150       | 3.25%   |
| Westmere         | 120       | 2.6%    |
| Zen+             | 119       | 2.58%   |
| Unknown          | 113       | 2.45%   |
| Zen 2            | 107       | 2.32%   |
| CometLake        | 88        | 1.9%    |
| Bonnell          | 86        | 1.86%   |
| Excavator        | 85        | 1.84%   |
| Zen 3            | 75        | 1.62%   |
| Icelake          | 72        | 1.56%   |
| P6               | 67        | 1.45%   |
| Goldmont plus    | 63        | 1.36%   |
| Alderlake Hybrid | 49        | 1.06%   |
| Goldmont         | 39        | 0.84%   |
| Zen              | 35        | 0.76%   |
| Bobcat           | 33        | 0.71%   |
| Puma             | 25        | 0.54%   |
| Jaguar           | 19        | 0.41%   |
| K8 Hammer        | 18        | 0.39%   |
| K10 Llano        | 16        | 0.35%   |
| NetBurst         | 14        | 0.3%    |
| Tremont          | 13        | 0.28%   |
| Piledriver       | 13        | 0.28%   |
| Nehalem          | 13        | 0.28%   |
| K10              | 11        | 0.24%   |
| Steamroller      | 7         | 0.15%   |
| K8 & K10 hybrid  | 7         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3346      | 60.23%  |
| Nvidia                           | 1317      | 23.71%  |
| AMD                              | 876       | 15.77%  |
| Silicon Integrated Systems [SiS] | 7         | 0.13%   |
| Zhaoxin                          | 4         | 0.07%   |
| VIA Technologies                 | 2         | 0.04%   |
| S3 Graphics                      | 2         | 0.04%   |
| Neomagic                         | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 354       | 6.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 275       | 4.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 248       | 4.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 189       | 3.26%   |
| Intel UHD Graphics 620                                                                   | 186       | 3.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 156       | 2.69%   |
| Intel HD Graphics 6000                                                                   | 154       | 2.65%   |
| Intel HD Graphics 620                                                                    | 150       | 2.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 147       | 2.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 143       | 2.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 139       | 2.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 129       | 2.22%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 122       | 2.1%    |
| Intel HD Graphics 5500                                                                   | 116       | 2%      |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 112       | 1.93%   |
| AMD Renoir                                                                               | 106       | 1.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 103       | 1.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 101       | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 95        | 1.64%   |
| Intel Core Processor Integrated Graphics Controller                                      | 92        | 1.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 88        | 1.52%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 78        | 1.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 75        | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 75        | 1.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 69        | 1.19%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 67        | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 57        | 0.98%   |
| AMD Lucienne                                                                             | 55        | 0.95%   |
| Intel HD Graphics 630                                                                    | 46        | 0.79%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 0.76%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 44        | 0.76%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 44        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 44        | 0.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 42        | 0.72%   |
| Intel HD Graphics 530                                                                    | 41        | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 41        | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 38        | 0.66%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 34        | 0.59%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 33        | 0.57%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 33        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 2453      | 53.04%  |
| Intel + Nvidia     | 736       | 15.91%  |
| 1 x AMD            | 614       | 13.28%  |
| 1 x Nvidia         | 516       | 11.16%  |
| Intel + AMD        | 146       | 3.16%   |
| AMD + Nvidia       | 65        | 1.41%   |
| 2 x AMD            | 51        | 1.1%    |
| Other              | 22        | 0.48%   |
| 1 x SiS            | 7         | 0.15%   |
| 1 x Zhaoxin        | 4         | 0.09%   |
| 2 x Intel          | 3         | 0.06%   |
| 1 x VIA            | 2         | 0.04%   |
| 1 x S3 Graphics    | 2         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.04%   |
| 2 x Nvidia         | 1         | 0.02%   |
| 1 x Neomagic       | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4019      | 86.41%  |
| Proprietary | 325       | 6.99%   |
| Unknown     | 307       | 6.6%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 3376      | 72.23%  |
| 0.01-0.5       | 718       | 15.36%  |
| 1.01-2.0       | 251       | 5.37%   |
| 0.51-1.0       | 135       | 2.89%   |
| 3.01-4.0       | 133       | 2.85%   |
| 5.01-6.0       | 29        | 0.62%   |
| 7.01-8.0       | 22        | 0.47%   |
| 2.01-3.0       | 8         | 0.17%   |
| More than 64.0 | 1         | 0.02%   |
| 8.01-16.0      | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 870       | 17.5%   |
| BOE                     | 646       | 12.99%  |
| Apple                   | 641       | 12.89%  |
| LG Display              | 598       | 12.03%  |
| Chimei Innolux          | 550       | 11.06%  |
| Samsung Electronics     | 400       | 8.05%   |
| Dell                    | 132       | 2.65%   |
| Lenovo                  | 115       | 2.31%   |
| Sharp                   | 103       | 2.07%   |
| Goldstar                | 96        | 1.93%   |
| Chi Mei Optoelectronics | 87        | 1.75%   |
| InfoVision              | 67        | 1.35%   |
| Hewlett-Packard         | 59        | 1.19%   |
| PANDA                   | 48        | 0.97%   |
| Philips                 | 46        | 0.93%   |
| BenQ                    | 45        | 0.91%   |
| Iiyama                  | 35        | 0.7%    |
| AOC                     | 35        | 0.7%    |
| HannStar                | 33        | 0.66%   |
| LG Philips              | 31        | 0.62%   |
| Acer                    | 31        | 0.62%   |
| Ancor Communications    | 29        | 0.58%   |
| CSO                     | 27        | 0.54%   |
| Unknown                 | 23        | 0.46%   |
| ViewSonic               | 20        | 0.4%    |
| Sony                    | 18        | 0.36%   |
| CPT                     | 16        | 0.32%   |
| Eizo                    | 14        | 0.28%   |
| Quanta Display          | 10        | 0.2%    |
| ASUSTek Computer        | 9         | 0.18%   |
| Panasonic               | 8         | 0.16%   |
| NEC Computers           | 8         | 0.16%   |
| MSI                     | 6         | 0.12%   |
| LGD                     | 6         | 0.12%   |
| Pixio                   | 5         | 0.1%    |
| InnoLux Display         | 4         | 0.08%   |
| AGO                     | 4         | 0.08%   |
| Toshiba                 | 3         | 0.06%   |
| TMX                     | 3         | 0.06%   |
| SLD                     | 3         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                 | 210       | 4.17%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch               | 189       | 3.76%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                 | 52        | 1.03%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                 | 44        | 0.87%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 43        | 0.85%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 42        | 0.83%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                 | 41        | 0.82%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                 | 37        | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 32        | 0.64%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                 | 29        | 0.58%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 28        | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 27        | 0.54%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 26        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 24        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch      | 24        | 0.48%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 23        | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 22        | 0.44%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                 | 22        | 0.44%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch            | 20        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 20        | 0.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 17        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 17        | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 16        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 16        | 0.32%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 16        | 0.32%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 16        | 0.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 15        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 14        | 0.28%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                 | 14        | 0.28%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch        | 13        | 0.26%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 12        | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 12        | 0.24%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 12        | 0.24%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 12        | 0.24%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 11        | 0.22%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 11        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1762      | 37.52%  |
| 1366x768 (WXGA)    | 1301      | 27.7%   |
| 1280x800 (WXGA)    | 569       | 12.12%  |
| 1600x900 (HD+)     | 194       | 4.13%   |
| 1440x900 (WXGA+)   | 139       | 2.96%   |
| 3840x2160 (4K)     | 134       | 2.85%   |
| 2560x1440 (QHD)    | 99        | 2.11%   |
| 1920x1200 (WUXGA)  | 97        | 2.07%   |
| 1024x600           | 67        | 1.43%   |
| 1280x1024 (SXGA)   | 34        | 0.72%   |
| 2560x1600          | 33        | 0.7%    |
| 1680x1050 (WSXGA+) | 32        | 0.68%   |
| 2560x1080          | 26        | 0.55%   |
| 3840x2400          | 25        | 0.53%   |
| 1360x768           | 21        | 0.45%   |
| 2288x1287          | 20        | 0.43%   |
| 1024x768 (XGA)     | 19        | 0.4%    |
| 2880x1800          | 18        | 0.38%   |
| 3440x1440          | 17        | 0.36%   |
| 3200x1800 (QHD+)   | 11        | 0.23%   |
| 2160x1440          | 9         | 0.19%   |
| 1600x1200          | 7         | 0.15%   |
| Unknown            | 7         | 0.15%   |
| 3840x1080          | 5         | 0.11%   |
| 1400x1050          | 5         | 0.11%   |
| 1280x720 (HD)      | 5         | 0.11%   |
| 3840x1200          | 3         | 0.06%   |
| 3840x1100          | 3         | 0.06%   |
| 2880x1920          | 3         | 0.06%   |
| 2256x1504          | 3         | 0.06%   |
| 2240x1400          | 3         | 0.06%   |
| 1024x576           | 3         | 0.06%   |
| 3072x1920          | 2         | 0.04%   |
| 2304x1440          | 2         | 0.04%   |
| 1920x540           | 2         | 0.04%   |
| 1920x1280          | 2         | 0.04%   |
| 800x1280           | 1         | 0.02%   |
| 7680x2160          | 1         | 0.02%   |
| 640x480            | 1         | 0.02%   |
| 3840x1600          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1505      | 30.23%  |
| 13      | 1158      | 23.26%  |
| 14      | 627       | 12.6%   |
| 11      | 280       | 5.62%   |
| 17      | 276       | 5.54%   |
| 12      | 182       | 3.66%   |
| 24      | 170       | 3.42%   |
| 27      | 127       | 2.55%   |
| 23      | 125       | 2.51%   |
| 21      | 96        | 1.93%   |
| 10      | 68        | 1.37%   |
| Unknown | 43        | 0.86%   |
| 18      | 42        | 0.84%   |
| 34      | 37        | 0.74%   |
| 16      | 31        | 0.62%   |
| 19      | 29        | 0.58%   |
| 31      | 27        | 0.54%   |
| 142     | 20        | 0.4%    |
| 22      | 18        | 0.36%   |
| 25      | 15        | 0.3%    |
| 20      | 12        | 0.24%   |
| 40      | 11        | 0.22%   |
| 32      | 11        | 0.22%   |
| 72      | 10        | 0.2%    |
| 54      | 8         | 0.16%   |
| 8       | 7         | 0.14%   |
| 29      | 6         | 0.12%   |
| 84      | 5         | 0.1%    |
| 46      | 4         | 0.08%   |
| 28      | 4         | 0.08%   |
| 52      | 3         | 0.06%   |
| 49      | 3         | 0.06%   |
| 43      | 3         | 0.06%   |
| 26      | 3         | 0.06%   |
| 48      | 2         | 0.04%   |
| 33      | 2         | 0.04%   |
| 65      | 1         | 0.02%   |
| 58      | 1         | 0.02%   |
| 55      | 1         | 0.02%   |
| 47      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2488      | 50.43%  |
| 201-300        | 1316      | 26.67%  |
| 501-600        | 397       | 8.05%   |
| 351-400        | 321       | 6.51%   |
| 401-500        | 180       | 3.65%   |
| 601-700        | 56        | 1.13%   |
| 701-800        | 49        | 0.99%   |
| Unknown        | 43        | 0.87%   |
| 1001-1500      | 27        | 0.55%   |
| More than 2000 | 20        | 0.41%   |
| 1501-2000      | 15        | 0.3%    |
| 801-900        | 13        | 0.26%   |
| 101-200        | 8         | 0.16%   |
| 901-1000       | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3329      | 74.81%  |
| 16/10   | 921       | 20.7%   |
| 21/9    | 40        | 0.9%    |
| 4/3     | 36        | 0.81%   |
| 5/4     | 34        | 0.76%   |
| 3/2     | 28        | 0.63%   |
| Unknown | 26        | 0.58%   |
| 1.00    | 20        | 0.45%   |
| 32/9    | 4         | 0.09%   |
| 2.65    | 4         | 0.09%   |
| 3.40    | 3         | 0.07%   |
| 3.20    | 3         | 0.07%   |
| 3.73    | 1         | 0.02%   |
| 0.62    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1501      | 30.25%  |
| 81-90          | 1479      | 29.81%  |
| 201-250        | 314       | 6.33%   |
| 71-80          | 299       | 6.03%   |
| 51-60          | 283       | 5.7%    |
| 121-130        | 220       | 4.43%   |
| 61-70          | 176       | 3.55%   |
| 301-350        | 128       | 2.58%   |
| 351-500        | 82        | 1.65%   |
| 251-300        | 80        | 1.61%   |
| 41-50          | 68        | 1.37%   |
| 151-200        | 66        | 1.33%   |
| 141-150        | 59        | 1.19%   |
| More than 1000 | 51        | 1.03%   |
| Unknown        | 43        | 0.87%   |
| 131-140        | 35        | 0.71%   |
| 111-120        | 25        | 0.5%    |
| 501-1000       | 24        | 0.48%   |
| 91-100         | 21        | 0.42%   |
| 1-40           | 8         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2015      | 41.41%  |
| 101-120       | 1650      | 33.91%  |
| 51-100        | 697       | 14.32%  |
| 161-240       | 299       | 6.14%   |
| More than 240 | 102       | 2.1%    |
| 1-50          | 60        | 1.23%   |
| Unknown       | 43        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3660      | 77.61%  |
| 2     | 684       | 14.5%   |
| 0     | 298       | 6.32%   |
| 3     | 72        | 1.53%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2308      | 30.96%  |
| Realtek Semiconductor             | 2004      | 26.88%  |
| Qualcomm Atheros                  | 972       | 13.04%  |
| Broadcom                          | 718       | 9.63%   |
| Nvidia                            | 372       | 4.99%   |
| Broadcom Limited                  | 253       | 3.39%   |
| Marvell Technology Group          | 144       | 1.93%   |
| MediaTek                          | 71        | 0.95%   |
| Ralink                            | 57        | 0.76%   |
| ASIX Electronics                  | 52        | 0.7%    |
| TP-Link                           | 44        | 0.59%   |
| Dell                              | 39        | 0.52%   |
| Samsung Electronics               | 32        | 0.43%   |
| Lenovo                            | 32        | 0.43%   |
| Sierra Wireless                   | 31        | 0.42%   |
| JMicron Technology                | 26        | 0.35%   |
| Ericsson Business Mobile Networks | 25        | 0.34%   |
| Ralink Technology                 | 23        | 0.31%   |
| Qualcomm                          | 21        | 0.28%   |
| Xiaomi                            | 19        | 0.25%   |
| DisplayLink                       | 18        | 0.24%   |
| Huawei Technologies               | 17        | 0.23%   |
| Hewlett-Packard                   | 15        | 0.2%    |
| Fibocom                           | 13        | 0.17%   |
| Silicon Integrated Systems [SiS]  | 11        | 0.15%   |
| Qualcomm Atheros Communications   | 9         | 0.12%   |
| NetGear                           | 8         | 0.11%   |
| Cypress Semiconductor             | 8         | 0.11%   |
| OPPO Electronics                  | 7         | 0.09%   |
| ASUSTek Computer                  | 7         | 0.09%   |
| ICS Advent                        | 6         | 0.08%   |
| Attansic Technology               | 6         | 0.08%   |
| Motorola PCS                      | 5         | 0.07%   |
| Microchip Technology              | 5         | 0.07%   |
| Edimax Technology                 | 5         | 0.07%   |
| D-Link                            | 5         | 0.07%   |
| Apple                             | 5         | 0.07%   |
| AMD                               | 5         | 0.07%   |
| ULi Electronics                   | 3         | 0.04%   |
| U-Blox                            | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 1217      | 13.74%  |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 363       | 4.1%    |
| Nvidia MCP79 Ethernet                                                                 | 362       | 4.09%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 354       | 4%      |
| Intel Wireless 7260                                                                   | 206       | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 199       | 2.25%   |
| Intel Wireless 8265 / 8275                                                            | 186       | 2.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 183       | 2.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 182       | 2.05%   |
| Intel Wi-Fi 6 AX200                                                                   | 172       | 1.94%   |
| Intel Wireless 7265                                                                   | 167       | 1.88%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 160       | 1.81%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 147       | 1.66%   |
| Intel Wi-Fi 6 AX201                                                                   | 146       | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 126       | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 119       | 1.34%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 114       | 1.29%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 114       | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 104       | 1.17%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 103       | 1.16%   |
| Intel Wireless 8260                                                                   | 98        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 96        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 92        | 1.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 80        | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 72        | 0.81%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 70        | 0.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 66        | 0.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 65        | 0.73%   |
| Intel Wireless 3165                                                                   | 61        | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 60        | 0.68%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 59        | 0.67%   |
| Intel Ethernet Connection I218-LM                                                     | 59        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                                  | 59        | 0.67%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 58        | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 53        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                                 | 53        | 0.6%    |
| Intel Ethernet Connection I219-LM                                                     | 52        | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 50        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 48        | 0.54%   |
| Intel Wireless-AC 9260                                                                | 44        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2180      | 46.19%  |
| Qualcomm Atheros                      | 871       | 18.45%  |
| Broadcom                              | 608       | 12.88%  |
| Realtek Semiconductor                 | 546       | 11.57%  |
| Broadcom Limited                      | 215       | 4.56%   |
| MediaTek                              | 66        | 1.4%    |
| Ralink                                | 57        | 1.21%   |
| Sierra Wireless                       | 31        | 0.66%   |
| TP-Link                               | 25        | 0.53%   |
| Dell                                  | 24        | 0.51%   |
| Ralink Technology                     | 23        | 0.49%   |
| FIBOCOM                               | 13        | 0.28%   |
| Qualcomm                              | 10        | 0.21%   |
| Qualcomm Atheros Communications       | 9         | 0.19%   |
| NetGear                               | 8         | 0.17%   |
| ASUSTek Computer                      | 7         | 0.15%   |
| Edimax Technology                     | 5         | 0.11%   |
| Hewlett-Packard                       | 3         | 0.06%   |
| D-Link                                | 3         | 0.06%   |
| Wilocity                              | 2         | 0.04%   |
| Quectel Wireless Solutions            | 2         | 0.04%   |
| D-Link System                         | 2         | 0.04%   |
| Belkin Components                     | 2         | 0.04%   |
| 3Com                                  | 2         | 0.04%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| Winbond Electronics                   | 1         | 0.02%   |
| Microsoft                             | 1         | 0.02%   |
| Cinterion                             | 1         | 0.02%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 363       | 7.65%   |
| Intel Wireless 7260                                                                   | 206       | 4.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 199       | 4.19%   |
| Intel Wireless 8265 / 8275                                                            | 186       | 3.92%   |
| Intel Wi-Fi 6 AX200                                                                   | 172       | 3.63%   |
| Intel Wireless 7265                                                                   | 167       | 3.52%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 160       | 3.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 147       | 3.1%    |
| Intel Wi-Fi 6 AX201                                                                   | 146       | 3.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 126       | 2.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 119       | 2.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 114       | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 114       | 2.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 104       | 2.19%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 103       | 2.17%   |
| Intel Wireless 8260                                                                   | 98        | 2.07%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 96        | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 92        | 1.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 80        | 1.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 72        | 1.52%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 70        | 1.48%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 66        | 1.39%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 65        | 1.37%   |
| Intel Wireless 3165                                                                   | 61        | 1.29%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 59        | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 53        | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 50        | 1.05%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 48        | 1.01%   |
| Intel Wireless-AC 9260                                                                | 44        | 0.93%   |
| Intel Centrino Ultimate-N 6300                                                        | 41        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 41        | 0.86%   |
| Intel Wireless 3160                                                                   | 40        | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 38        | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 37        | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 37        | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 33        | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 32        | 0.67%   |
| Intel Centrino Advanced-N 6200                                                        | 32        | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 31        | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 30        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1801      | 45.61%  |
| Intel                            | 930       | 23.55%  |
| Nvidia                           | 372       | 9.42%   |
| Qualcomm Atheros                 | 213       | 5.39%   |
| Broadcom                         | 145       | 3.67%   |
| Marvell Technology Group         | 144       | 3.65%   |
| ASIX Electronics                 | 52        | 1.32%   |
| Broadcom Limited                 | 41        | 1.04%   |
| Samsung Electronics              | 32        | 0.81%   |
| Lenovo                           | 32        | 0.81%   |
| JMicron Technology               | 26        | 0.66%   |
| Xiaomi                           | 19        | 0.48%   |
| TP-Link                          | 19        | 0.48%   |
| DisplayLink                      | 18        | 0.46%   |
| Silicon Integrated Systems [SiS] | 11        | 0.28%   |
| Huawei Technologies              | 11        | 0.28%   |
| Qualcomm                         | 10        | 0.25%   |
| Cypress Semiconductor            | 8         | 0.2%    |
| OPPO Electronics                 | 7         | 0.18%   |
| ICS Advent                       | 6         | 0.15%   |
| Attansic Technology              | 6         | 0.15%   |
| Microchip Technology             | 5         | 0.13%   |
| MediaTek                         | 5         | 0.13%   |
| Apple                            | 5         | 0.13%   |
| Motorola PCS                     | 4         | 0.1%    |
| Hewlett-Packard                  | 4         | 0.1%    |
| Spreadtrum Communications        | 3         | 0.08%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.05%   |
| National Semiconductor           | 2         | 0.05%   |
| LG Electronics                   | 2         | 0.05%   |
| D-Link                           | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| ULi Electronics                  | 1         | 0.03%   |
| MosChip Semiconductor            | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| HTC (High Tech Computer)         | 1         | 0.03%   |
| Google                           | 1         | 0.03%   |
| Foxconn / Hon Hai                | 1         | 0.03%   |
| Digitech Systems                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1217      | 30.5%   |
| Nvidia MCP79 Ethernet                                             | 362       | 9.07%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 354       | 8.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 183       | 4.59%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 182       | 4.56%   |
| Intel Ethernet Connection (4) I219-LM                             | 60        | 1.5%    |
| Intel Ethernet Connection I218-LM                                 | 59        | 1.48%   |
| Intel Ethernet Connection (4) I219-V                              | 59        | 1.48%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 58        | 1.45%   |
| Intel Ethernet Connection (3) I218-LM                             | 53        | 1.33%   |
| Intel Ethernet Connection I219-LM                                 | 52        | 1.3%    |
| ASIX AX88179 Gigabit Ethernet                                     | 43        | 1.08%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 1.05%   |
| Intel Ethernet Connection (6) I219-V                              | 39        | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 36        | 0.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 35        | 0.88%   |
| Intel 82567LM Gigabit Network Connection                          | 33        | 0.83%   |
| Intel Ethernet Connection I217-LM                                 | 30        | 0.75%   |
| Intel Ethernet Connection I219-V                                  | 29        | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 28        | 0.7%    |
| Intel Ethernet Connection (13) I219-V                             | 27        | 0.68%   |
| Intel Ethernet Connection (10) I219-V                             | 26        | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 25        | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 25        | 0.63%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 22        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 20        | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 20        | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 19        | 0.48%   |
| Intel Ethernet Connection (6) I219-LM                             | 19        | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18        | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.43%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 16        | 0.4%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 16        | 0.4%    |
| Intel Ethernet Connection (7) I219-LM                             | 16        | 0.4%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 15        | 0.38%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 15        | 0.38%   |
| Intel 82566MM Gigabit Network Connection                          | 15        | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14        | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 14        | 0.35%   |
| Intel Ethernet Connection (16) I219-V                             | 14        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4530      | 53.79%  |
| Ethernet | 3766      | 44.72%  |
| Modem    | 119       | 1.41%   |
| Unknown  | 7         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3516      | 72.08%  |
| Ethernet | 1362      | 27.92%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3406      | 73.66%  |
| 1     | 1100      | 23.79%  |
| 0     | 71        | 1.54%   |
| 3     | 45        | 0.97%   |
| 5     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3933      | 84.11%  |
| Yes  | 743       | 15.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1647      | 43.92%  |
| Apple                           | 631       | 16.83%  |
| Qualcomm Atheros Communications | 329       | 8.77%   |
| Realtek Semiconductor           | 314       | 8.37%   |
| Broadcom                        | 179       | 4.77%   |
| Lite-On Technology              | 139       | 3.71%   |
| IMC Networks                    | 136       | 3.63%   |
| Foxconn / Hon Hai               | 94        | 2.51%   |
| Dell                            | 63        | 1.68%   |
| Hewlett-Packard                 | 44        | 1.17%   |
| Cambridge Silicon Radio         | 44        | 1.17%   |
| ASUSTek Computer                | 27        | 0.72%   |
| Realtek                         | 23        | 0.61%   |
| Toshiba                         | 22        | 0.59%   |
| Ralink                          | 19        | 0.51%   |
| Foxconn International           | 9         | 0.24%   |
| Alps Electric                   | 6         | 0.16%   |
| Ralink Technology               | 5         | 0.13%   |
| MediaTek                        | 4         | 0.11%   |
| Taiyo Yuden                     | 3         | 0.08%   |
| Fujitsu                         | 2         | 0.05%   |
| Chicony Electronics             | 2         | 0.05%   |
| USI                             | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |
| Smart Modular Technologies      | 1         | 0.03%   |
| Qcom                            | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Askey Computer                  | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 709       | 18.88%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 351       | 9.35%   |
| Intel AX201 Bluetooth                               | 297       | 7.91%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 267       | 7.11%   |
| Realtek Bluetooth Radio                             | 191       | 5.09%   |
| Qualcomm Atheros  Bluetooth Device                  | 189       | 5.03%   |
| Intel AX200 Bluetooth                               | 164       | 4.37%   |
| Apple Bluetooth USB Host Controller                 | 159       | 4.23%   |
| Realtek  Bluetooth 4.2 Adapter                      | 79        | 2.1%    |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 2.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 49        | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 45        | 1.2%    |
| Intel Bluetooth Device                              | 44        | 1.17%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 44        | 1.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 42        | 1.12%   |
| IMC Networks Bluetooth Radio                        | 40        | 1.07%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 39        | 1.04%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 1.04%   |
| Apple Bluetooth Host Controller                     | 38        | 1.01%   |
| Lite-On Bluetooth Device                            | 36        | 0.96%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 35        | 0.93%   |
| IMC Networks Bluetooth Device                       | 34        | 0.91%   |
| Foxconn / Hon Hai Bluetooth Device                  | 34        | 0.91%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 32        | 0.85%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 32        | 0.85%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 31        | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 30        | 0.8%    |
| Intel AX210 Bluetooth                               | 24        | 0.64%   |
| Realtek Bluetooth Radio                             | 23        | 0.61%   |
| IMC Networks Wireless_Device                        | 23        | 0.61%   |
| Foxconn / Hon Hai Wireless_Device                   | 23        | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 0.56%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.51%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.51%   |
| Dell BCM20702A0 Bluetooth Module                    | 18        | 0.48%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 17        | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 14        | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 3529      | 65.83%  |
| Nvidia                                       | 808       | 15.07%  |
| AMD                                          | 699       | 13.04%  |
| C-Media Electronics                          | 38        | 0.71%   |
| Logitech                                     | 30        | 0.56%   |
| Lenovo                                       | 29        | 0.54%   |
| Realtek Semiconductor                        | 26        | 0.48%   |
| Texas Instruments                            | 18        | 0.34%   |
| Plantronics                                  | 16        | 0.3%    |
| GN Netcom                                    | 16        | 0.3%    |
| Silicon Integrated Systems [SiS]             | 12        | 0.22%   |
| Hewlett-Packard                              | 12        | 0.22%   |
| Generalplus Technology                       | 10        | 0.19%   |
| Creative Technology                          | 7         | 0.13%   |
| ASUSTek Computer                             | 7         | 0.13%   |
| JMTek                                        | 6         | 0.11%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.09%   |
| Focusrite-Novation                           | 5         | 0.09%   |
| Zhaoxin                                      | 4         | 0.07%   |
| RODE Microphones                             | 4         | 0.07%   |
| Kingston Technology                          | 4         | 0.07%   |
| Dell                                         | 4         | 0.07%   |
| ULi Electronics                              | 3         | 0.06%   |
| Sennheiser Communications                    | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| Microsoft                                    | 3         | 0.06%   |
| BEHRINGER International                      | 3         | 0.06%   |
| XMOS                                         | 2         | 0.04%   |
| VIA Technologies                             | 2         | 0.04%   |
| SteelSeries ApS                              | 2         | 0.04%   |
| SAVITECH                                     | 2         | 0.04%   |
| M-Audio                                      | 2         | 0.04%   |
| ESS Technology                               | 2         | 0.04%   |
| Conexant Systems                             | 2         | 0.04%   |
| CMX Systems                                  | 2         | 0.04%   |
| Blue Microphones                             | 2         | 0.04%   |
| Beyerdynamic                                 | 2         | 0.04%   |
| Apple                                        | 2         | 0.04%   |
| Yamaha                                       | 1         | 0.02%   |
| Veho                                         | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 525       | 8.12%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 388       | 6%      |
| Nvidia MCP79 High Definition Audio                                                                | 364       | 5.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 352       | 5.44%   |
| Intel Broadwell-U Audio Controller                                                                | 283       | 4.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 279       | 4.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 223       | 3.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 206       | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 200       | 3.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 172       | 2.66%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 159       | 2.46%   |
| Intel 8 Series HD Audio Controller                                                                | 159       | 2.46%   |
| Intel Cannon Lake PCH cAVS                                                                        | 158       | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 150       | 2.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 148       | 2.29%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 139       | 2.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 132       | 2.04%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 126       | 1.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 116       | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 111       | 1.72%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 97        | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 96        | 1.48%   |
| AMD FCH Azalia Controller                                                                         | 93        | 1.44%   |
| AMD Kabini HDMI/DP Audio                                                                          | 88        | 1.36%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 81        | 1.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 80        | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 80        | 1.24%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 69        | 1.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 63        | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 59        | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 53        | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 52        | 0.8%    |
| Intel CM238 HD Audio Controller                                                                   | 50        | 0.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 46        | 0.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 43        | 0.66%   |
| AMD High Definition Audio Controller                                                              | 41        | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 39        | 0.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 39        | 0.6%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 32        | 0.49%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 31        | 0.48%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 1267      | 28.73%  |
| Samsung Electronics | 1167      | 26.46%  |
| Micron Technology   | 474       | 10.75%  |
| Unknown             | 311       | 7.05%   |
| Kingston            | 305       | 6.92%   |
| Crucial             | 214       | 4.85%   |
| Elpida              | 129       | 2.93%   |
| A-DATA Technology   | 90        | 2.04%   |
| Ramaxel Technology  | 80        | 1.81%   |
| Nanya Technology    | 48        | 1.09%   |
| Corsair             | 40        | 0.91%   |
| Smart               | 35        | 0.79%   |
| Unknown (ABCD)      | 34        | 0.77%   |
| GOODRAM             | 21        | 0.48%   |
| G.Skill             | 19        | 0.43%   |
| Transcend           | 18        | 0.41%   |
| Team                | 16        | 0.36%   |
| Unknown             | 14        | 0.32%   |
| Teikon              | 10        | 0.23%   |
| Apacer              | 8         | 0.18%   |
| 48spaces            | 8         | 0.18%   |
| Silicon Power       | 7         | 0.16%   |
| Patriot             | 7         | 0.16%   |
| ASint Technology    | 7         | 0.16%   |
| Smart Brazil        | 6         | 0.14%   |
| Qimonda             | 4         | 0.09%   |
| PNY                 | 4         | 0.09%   |
| AMD                 | 4         | 0.09%   |
| Wilk                | 3         | 0.07%   |
| Neo Forza           | 3         | 0.07%   |
| Infineon            | 3         | 0.07%   |
| Goldkey             | 3         | 0.07%   |
| Avant               | 3         | 0.07%   |
| Unknown (89F7)      | 2         | 0.05%   |
| Unifosa             | 2         | 0.05%   |
| Timetec             | 2         | 0.05%   |
| TEXTORM             | 2         | 0.05%   |
| Shenzhen WODPOSIT   | 2         | 0.05%   |
| SHARETRONIC         | 2         | 0.05%   |
| PUSKILL             | 2         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 264       | 5.69%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 1.46%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 67        | 1.44%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 1.36%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 44        | 0.95%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.95%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 41        | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 40        | 0.86%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 40        | 0.86%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 39        | 0.84%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 39        | 0.84%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 38        | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 37        | 0.8%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 36        | 0.78%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 35        | 0.75%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 33        | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 33        | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 31        | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 30        | 0.65%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 29        | 0.62%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 28        | 0.6%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 26        | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 25        | 0.54%   |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 25        | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 25        | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 25        | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 0.54%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 24        | 0.52%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 23        | 0.5%    |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 22        | 0.47%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 21        | 0.45%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.43%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 18        | 0.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 18        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1493      | 38.95%  |
| DDR3    | 1299      | 33.89%  |
| DDR2    | 596       | 15.55%  |
| LPDDR4  | 140       | 3.65%   |
| LPDDR3  | 111       | 2.9%    |
| SDRAM   | 83        | 2.17%   |
| DDR     | 41        | 1.07%   |
| Unknown | 23        | 0.6%    |
| DDR5    | 20        | 0.52%   |
| LPDDR5  | 17        | 0.44%   |
| DRAM    | 9         | 0.23%   |
| RAM     | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3503      | 91.27%  |
| Row Of Chips | 256       | 6.67%   |
| Unknown      | 35        | 0.91%   |
| Chip         | 30        | 0.78%   |
| DIMM         | 14        | 0.36%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1270      | 30.63%  |
| 4096  | 1105      | 26.65%  |
| 2048  | 638       | 15.39%  |
| 1024  | 548       | 13.22%  |
| 16384 | 437       | 10.54%  |
| 32768 | 86        | 2.07%   |
| 512   | 43        | 1.04%   |
| 256   | 16        | 0.39%   |
| 128   | 2         | 0.05%   |
| 384   | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 973       | 23.74%  |
| 2667    | 711       | 17.35%  |
| 3200    | 586       | 14.3%   |
| 800     | 385       | 9.39%   |
| 2400    | 251       | 6.12%   |
| 667     | 180       | 4.39%   |
| 2133    | 177       | 4.32%   |
| 1334    | 167       | 4.08%   |
| 1333    | 128       | 3.12%   |
| Unknown | 104       | 2.54%   |
| 1067    | 56        | 1.37%   |
| 4267    | 53        | 1.29%   |
| 1867    | 45        | 1.1%    |
| 3266    | 38        | 0.93%   |
| 4199    | 31        | 0.76%   |
| 4800    | 24        | 0.59%   |
| 1066    | 23        | 0.56%   |
| 533     | 21        | 0.51%   |
| 975     | 19        | 0.46%   |
| 2048    | 18        | 0.44%   |
| 8400    | 16        | 0.39%   |
| 6400    | 16        | 0.39%   |
| 4266    | 13        | 0.32%   |
| 400     | 11        | 0.27%   |
| 333     | 9         | 0.22%   |
| 266     | 8         | 0.2%    |
| 3733    | 7         | 0.17%   |
| 1866    | 7         | 0.17%   |
| 933     | 4         | 0.1%    |
| 2933    | 3         | 0.07%   |
| 2666    | 3         | 0.07%   |
| 1776    | 2         | 0.05%   |
| 1639    | 2         | 0.05%   |
| 3000    | 1         | 0.02%   |
| 2134    | 1         | 0.02%   |
| 1596    | 1         | 0.02%   |
| 200     | 1         | 0.02%   |
| 166     | 1         | 0.02%   |
| 133     | 1         | 0.02%   |
| 100     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 11        | 39.29%  |
| Xerox               | 4         | 14.29%  |
| Canon               | 3         | 10.71%  |
| Brother Industries  | 3         | 10.71%  |
| Samsung Electronics | 2         | 7.14%   |
| Kyocera             | 2         | 7.14%   |
| Xiaomi              | 1         | 3.57%   |
| STMicroelectronics  | 1         | 3.57%   |
| Pantum              | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Xerox B205                                                | 4         | 13.79%  |
| Xiaomi MiMouse 2                                          | 1         | 3.45%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.45%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 3.45%   |
| Samsung CLX-3300 Series                                   | 1         | 3.45%   |
| Pantum P2500W series                                      | 1         | 3.45%   |
| Kyocera FS-1120MFP                                        | 1         | 3.45%   |
| Kyocera ECOSYS P2335d                                     | 1         | 3.45%   |
| HP OfficeJet 3830 series                                  | 1         | 3.45%   |
| HP LaserJet P1102                                         | 1         | 3.45%   |
| HP LaserJet 1200                                          | 1         | 3.45%   |
| HP LaserJet 1160 series                                   | 1         | 3.45%   |
| HP LaserJet 1150                                          | 1         | 3.45%   |
| HP LaserJet 1022                                          | 1         | 3.45%   |
| HP LaserJet 1020                                          | 1         | 3.45%   |
| HP Ink Tank 110 series                                    | 1         | 3.45%   |
| HP EWS UPD                                                | 1         | 3.45%   |
| HP DeskJet 2600 series                                    | 1         | 3.45%   |
| HP Deskjet 2540 series                                    | 1         | 3.45%   |
| HP DeskJet 2130 series                                    | 1         | 3.45%   |
| Canon PIXMA MX920 Series                                  | 1         | 3.45%   |
| Canon LBP3010/LBP3018/LBP3050                             | 1         | 3.45%   |
| Canon G3010 series                                        | 1         | 3.45%   |
| Brother PT-9500PC                                         | 1         | 3.45%   |
| Brother MFC-L2707DW                                       | 1         | 3.45%   |
| Brother HL-L2340D series                                  | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 45.45%  |
| Seiko Epson     | 4         | 36.36%  |
| Mustek Systems  | 1         | 9.09%   |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                           | 2         | 18.18%  |
| Seiko Epson GT-9800F [Perfection 3200]            | 1         | 9.09%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]     | 1         | 9.09%   |
| Seiko Epson GT-7700U [Perfection 1240U]           | 1         | 9.09%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 9.09%   |
| Mustek Systems SNAPSCAN e22                       | 1         | 9.09%   |
| HP Scanjet 200                                    | 1         | 9.09%   |
| Canon CanoScan LIDE 25                            | 1         | 9.09%   |
| Canon CanoScan LiDE 220                           | 1         | 9.09%   |
| Canon CanoScan LiDE 110                           | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 857       | 24.06%  |
| IMC Networks                           | 408       | 11.45%  |
| Microdia                               | 300       | 8.42%   |
| Realtek Semiconductor                  | 297       | 8.34%   |
| Acer                                   | 280       | 7.86%   |
| Quanta                                 | 261       | 7.33%   |
| Sunplus Innovation Technology          | 190       | 5.33%   |
| Suyin                                  | 113       | 3.17%   |
| Cheng Uei Precision Industry (Foxlink) | 105       | 2.95%   |
| Lite-On Technology                     | 85        | 2.39%   |
| Syntek                                 | 78        | 2.19%   |
| Luxvisions Innotech Limited            | 69        | 1.94%   |
| Bison Electronics                      | 65        | 1.82%   |
| Apple                                  | 63        | 1.77%   |
| Silicon Motion                         | 52        | 1.46%   |
| Logitech                               | 51        | 1.43%   |
| Alcor Micro                            | 39        | 1.09%   |
| Lenovo                                 | 31        | 0.87%   |
| Ricoh                                  | 30        | 0.84%   |
| Z-Star Microelectronics                | 19        | 0.53%   |
| Primax Electronics                     | 18        | 0.51%   |
| Sonix Technology                       | 15        | 0.42%   |
| Samsung Electronics                    | 14        | 0.39%   |
| Importek                               | 10        | 0.28%   |
| ALi                                    | 10        | 0.28%   |
| USB Camera                             | 8         | 0.22%   |
| Genesys Logic                          | 8         | 0.22%   |
| SunplusIT                              | 7         | 0.2%    |
| Intel                                  | 5         | 0.14%   |
| Y Media                                | 4         | 0.11%   |
| OmniVision Technologies                | 4         | 0.11%   |
| MacroSilicon                           | 4         | 0.11%   |
| Sunplus Technology                     | 3         | 0.08%   |
| Pixart Imaging                         | 3         | 0.08%   |
| Microsoft                              | 3         | 0.08%   |
| Generalplus Technology                 | 3         | 0.08%   |
| GEMBIRD                                | 3         | 0.08%   |
| ARC International                      | 3         | 0.08%   |
| Tobii Technology AB                    | 2         | 0.06%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 246       | 6.86%   |
| Microdia Integrated_Webcam_HD                       | 143       | 3.99%   |
| IMC Networks Integrated Camera                      | 135       | 3.76%   |
| Realtek Integrated_Webcam_HD                        | 114       | 3.18%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 93        | 2.59%   |
| Chicony HD WebCam                                   | 75        | 2.09%   |
| Sunplus Integrated_Webcam_HD                        | 69        | 1.92%   |
| Quanta Lenovo EasyCamera                            | 69        | 1.92%   |
| Acer BisonCam, NB Pro                               | 57        | 1.59%   |
| Chicony HP HD Camera                                | 48        | 1.34%   |
| Acer Integrated Camera                              | 46        | 1.28%   |
| Bison Integrated Camera                             | 44        | 1.23%   |
| Chicony USB2.0 HD UVC WebCam                        | 42        | 1.17%   |
| Syntek Integrated Camera                            | 41        | 1.14%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 39        | 1.09%   |
| Quanta HP TrueVision HD Camera                      | 35        | 0.98%   |
| Microdia Integrated Webcam                          | 34        | 0.95%   |
| Lite-On Integrated Camera                           | 33        | 0.92%   |
| Quanta HD User Facing                               | 31        | 0.86%   |
| Acer SunplusIT Integrated Camera                    | 31        | 0.86%   |
| Acer Lenovo EasyCamera                              | 30        | 0.84%   |
| Quanta VGA WebCam                                   | 27        | 0.75%   |
| Quanta HP HD Camera                                 | 27        | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 26        | 0.72%   |
| Chicony Integrated Camera (1280x720@30)             | 25        | 0.7%    |
| Sunplus HD WebCam                                   | 24        | 0.67%   |
| Chicony HP TrueVision HD Camera                     | 24        | 0.67%   |
| Realtek USB Camera                                  | 23        | 0.64%   |
| Chicony HD User Facing                              | 23        | 0.64%   |
| Lite-On HP HD Camera                                | 22        | 0.61%   |
| Chicony USB2.0 Camera                               | 22        | 0.61%   |
| Realtek USB2.0 HD UVC WebCam                        | 21        | 0.59%   |
| Chicony EasyCamera                                  | 21        | 0.59%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 21        | 0.59%   |
| Acer Lenovo Integrated Webcam                       | 21        | 0.59%   |
| Realtek Integrated Webcam                           | 20        | 0.56%   |
| Chicony HP TrueVision HD                            | 20        | 0.56%   |
| Chicony Lenovo EasyCamera                           | 19        | 0.53%   |
| Acer HD Webcam                                      | 19        | 0.53%   |
| Acer BisonCam,NB Pro                                | 19        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 248       | 33.07%  |
| Synaptics                          | 233       | 31.07%  |
| Shenzhen Goodix Technology         | 103       | 13.73%  |
| Upek                               | 44        | 5.87%   |
| AuthenTec                          | 44        | 5.87%   |
| Elan Microelectronics              | 36        | 4.8%    |
| LighTuning Technology              | 22        | 2.93%   |
| STMicroelectronics                 | 16        | 2.13%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.27%   |
| Samsung Electronics                | 1         | 0.13%   |
| Microsoft                          | 1         | 0.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 105       | 14%     |
| Shenzhen Goodix  FingerPrint Device                                        | 61        | 8.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 56        | 7.47%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 51        | 6.8%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 45        | 6%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 40        | 5.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 30        | 4%      |
| Shenzhen Goodix Fingerprint Reader                                         | 23        | 3.07%   |
| Elan ELAN:Fingerprint                                                      | 23        | 3.07%   |
| Shenzhen Goodix FingerPrint                                                | 19        | 2.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 18        | 2.4%    |
| AuthenTec AES2810                                                          | 18        | 2.4%    |
| Validity Sensors Synaptics WBDI                                            | 17        | 2.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 2.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 2.27%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 14        | 1.87%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 1.87%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.87%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.87%   |
| Elan ELAN:ARM-M4                                                           | 13        | 1.73%   |
| Validity Sensors VFS491                                                    | 12        | 1.6%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.6%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.33%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 1.33%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 1.2%    |
| Synaptics  WBDI                                                            | 9         | 1.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 1.07%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 0.8%    |
| Synaptics UWP WBDI Device                                                  | 6         | 0.8%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.8%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.67%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 5         | 0.67%   |
| Synaptics WBDI                                                             | 5         | 0.67%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.53%   |
| Synaptics UWP WBDI                                                         | 4         | 0.53%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.53%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.53%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.4%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.27%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 149       | 37.82%  |
| Alcor Micro               | 144       | 36.55%  |
| O2 Micro                  | 28        | 7.11%   |
| Upek                      | 27        | 6.85%   |
| Lenovo                    | 27        | 6.85%   |
| Gemalto (was Gemplus)     | 4         | 1.02%   |
| Yubico.com                | 3         | 0.76%   |
| Clay Logic                | 3         | 0.76%   |
| SCM Microsystems          | 2         | 0.51%   |
| Aladdin Knowledge Systems | 2         | 0.51%   |
| Advanced Card Systems     | 2         | 0.51%   |
| OmniKey                   | 1         | 0.25%   |
| Cherry                    | 1         | 0.25%   |
| C3PO                      | 1         | 0.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 141       | 35.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 48        | 12.18%  |
| Broadcom 5880                                                                | 37        | 9.39%   |
| Broadcom 58200                                                               | 36        | 9.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 27        | 6.85%   |
| Lenovo Integrated Smart Card Reader                                          | 27        | 6.85%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 26        | 6.6%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 6.09%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.02%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.76%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.76%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.51%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.51%   |
| Clay Logic Nitrokey Start                                                    | 2         | 0.51%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.51%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.51%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.25%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.25%   |
| OmniKey CardMan 4321                                                         | 1         | 0.25%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.25%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.25%   |
| C3PO LTC31v2                                                                 | 1         | 0.25%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.25%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2711      | 57.57%  |
| 1     | 1495      | 31.75%  |
| 2     | 391       | 8.3%    |
| 3     | 97        | 2.06%   |
| 4     | 8         | 0.17%   |
| 5     | 6         | 0.13%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 746       | 29.85%  |
| Graphics card            | 651       | 26.05%  |
| Chipcard                 | 361       | 14.45%  |
| Multimedia controller    | 240       | 9.6%    |
| Net/wireless             | 220       | 8.8%    |
| Bluetooth                | 58        | 2.32%   |
| Camera                   | 50        | 2%      |
| Card reader              | 39        | 1.56%   |
| Storage                  | 36        | 1.44%   |
| Communication controller | 34        | 1.36%   |
| Sound                    | 20        | 0.8%    |
| Net/ethernet             | 17        | 0.68%   |
| Network                  | 8         | 0.32%   |
| Modem                    | 7         | 0.28%   |
| Flash memory             | 5         | 0.2%    |
| Unassigned class         | 2         | 0.08%   |
| Firewire controller      | 2         | 0.08%   |
| Wireless                 | 1         | 0.04%   |
| Tv card                  | 1         | 0.04%   |
| Storage/ide              | 1         | 0.04%   |

