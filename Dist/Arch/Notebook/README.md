Arch - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Arch.

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

Total: 4024

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | X570S AORUS PRO AX          | [253135f8dc](https://linux-hardware.org/?probe=253135f8dc) | Dec 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d57de89542](https://linux-hardware.org/?probe=d57de89542) | Dec 01, 2022 |
| Lenovo        | B40-70 20392                | [a527c5b6e6](https://linux-hardware.org/?probe=a527c5b6e6) | Dec 01, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [cccb2da575](https://linux-hardware.org/?probe=cccb2da575) | Dec 01, 2022 |
| ASUSTek       | E403SA                      | [d3a1f181d5](https://linux-hardware.org/?probe=d3a1f181d5) | Nov 30, 2022 |
| Positivo B... | S14SL03                     | [a42ebacec4](https://linux-hardware.org/?probe=a42ebacec4) | Nov 29, 2022 |
| MSI           | GF75 Thin 9SC               | [50a779c35d](https://linux-hardware.org/?probe=50a779c35d) | Nov 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [9f473cbdeb](https://linux-hardware.org/?probe=9f473cbdeb) | Nov 29, 2022 |
| Dell          | Inspiron 15-3567            | [b06377f324](https://linux-hardware.org/?probe=b06377f324) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [d258962c35](https://linux-hardware.org/?probe=d258962c35) | Nov 28, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [a3c2004787](https://linux-hardware.org/?probe=a3c2004787) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ceb78dbe4e](https://linux-hardware.org/?probe=ceb78dbe4e) | Nov 28, 2022 |
| Timi          | TM1613                      | [37036a425d](https://linux-hardware.org/?probe=37036a425d) | Nov 28, 2022 |
| Dell          | G15 5520                    | [251078d1b4](https://linux-hardware.org/?probe=251078d1b4) | Nov 28, 2022 |
| HP            | Pavilion Laptop 14-ce3xx... | [ccc431ef2e](https://linux-hardware.org/?probe=ccc431ef2e) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0d99651537](https://linux-hardware.org/?probe=0d99651537) | Nov 28, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [3f660318ea](https://linux-hardware.org/?probe=3f660318ea) | Nov 28, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [f18a4c8031](https://linux-hardware.org/?probe=f18a4c8031) | Nov 28, 2022 |
| Acer          | Predator PH315-54           | [15909202b8](https://linux-hardware.org/?probe=15909202b8) | Nov 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [d8bb1b1d38](https://linux-hardware.org/?probe=d8bb1b1d38) | Nov 27, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [4825bcbe78](https://linux-hardware.org/?probe=4825bcbe78) | Nov 27, 2022 |
| Dell          | Latitude E7440              | [3709af0366](https://linux-hardware.org/?probe=3709af0366) | Nov 27, 2022 |
| Sony          | VPCEA45FG                   | [847b1cb39a](https://linux-hardware.org/?probe=847b1cb39a) | Nov 26, 2022 |
| HP            | Laptop 14s-dq1xxx           | [9b3a058fda](https://linux-hardware.org/?probe=9b3a058fda) | Nov 26, 2022 |
| ASUSTek       | K70AB                       | [8b7e3c4b9e](https://linux-hardware.org/?probe=8b7e3c4b9e) | Nov 26, 2022 |
| Dell          | Latitude 5490               | [7aedc1fbd7](https://linux-hardware.org/?probe=7aedc1fbd7) | Nov 26, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [0e3f081937](https://linux-hardware.org/?probe=0e3f081937) | Nov 26, 2022 |
| MSI           | Alpha 17 B5EEK              | [0cd6df782e](https://linux-hardware.org/?probe=0cd6df782e) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cd9478ab62](https://linux-hardware.org/?probe=cd9478ab62) | Nov 26, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [1f2bd09174](https://linux-hardware.org/?probe=1f2bd09174) | Nov 25, 2022 |
| MSI           | Modern 14 B10MW             | [9768df6ae0](https://linux-hardware.org/?probe=9768df6ae0) | Nov 25, 2022 |
| MSI           | Modern 14 B10MW             | [1564025817](https://linux-hardware.org/?probe=1564025817) | Nov 25, 2022 |
| Acer          | Nitro AN515-52              | [c639db74cb](https://linux-hardware.org/?probe=c639db74cb) | Nov 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [2d1c8c7ea5](https://linux-hardware.org/?probe=2d1c8c7ea5) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ce5f08445d](https://linux-hardware.org/?probe=ce5f08445d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [4efc557c1b](https://linux-hardware.org/?probe=4efc557c1b) | Nov 24, 2022 |
| MECER         | YA13Q20-DP_PRO              | [c51a900a73](https://linux-hardware.org/?probe=c51a900a73) | Nov 23, 2022 |
| HP            | Laptop 15-dw3xxx            | [4f6911ae2c](https://linux-hardware.org/?probe=4f6911ae2c) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [51ca9fa048](https://linux-hardware.org/?probe=51ca9fa048) | Nov 23, 2022 |
| MSI           | Modern 15 A5M               | [0ca1ce1d74](https://linux-hardware.org/?probe=0ca1ce1d74) | Nov 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [47d808147c](https://linux-hardware.org/?probe=47d808147c) | Nov 23, 2022 |
| Lenovo        | ThinkPad T480 20L50011US    | [2f32726e0d](https://linux-hardware.org/?probe=2f32726e0d) | Nov 23, 2022 |
| Lenovo        | ThinkPad T440p 20AWS3RJ0... | [43f6a19d9a](https://linux-hardware.org/?probe=43f6a19d9a) | Nov 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [65a3383e83](https://linux-hardware.org/?probe=65a3383e83) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| HP            | ProBook 6570b               | [b7bd63db1c](https://linux-hardware.org/?probe=b7bd63db1c) | Nov 22, 2022 |
| HP            | EliteBook 8460w             | [cdb72eea80](https://linux-hardware.org/?probe=cdb72eea80) | Nov 22, 2022 |
| Dell          | XPS 13 9300                 | [3f9c0d5b63](https://linux-hardware.org/?probe=3f9c0d5b63) | Nov 22, 2022 |
| ASUSTek       | GL503VS                     | [18fa411a6d](https://linux-hardware.org/?probe=18fa411a6d) | Nov 22, 2022 |
| Acer          | Nitro AN515-52              | [57b2e84560](https://linux-hardware.org/?probe=57b2e84560) | Nov 22, 2022 |
| ASUSTek       | X455YA                      | [70267d756a](https://linux-hardware.org/?probe=70267d756a) | Nov 21, 2022 |
| Acer          | Nitro AN515-52              | [308968646b](https://linux-hardware.org/?probe=308968646b) | Nov 21, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [cd2b457ffb](https://linux-hardware.org/?probe=cd2b457ffb) | Nov 20, 2022 |
| HP            | Notebook                    | [1278403b39](https://linux-hardware.org/?probe=1278403b39) | Nov 20, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [2db5ac853d](https://linux-hardware.org/?probe=2db5ac853d) | Nov 20, 2022 |
| Dell          | XPS 9320                    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [7ac338ce0d](https://linux-hardware.org/?probe=7ac338ce0d) | Nov 19, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [50bd30f30d](https://linux-hardware.org/?probe=50bd30f30d) | Nov 19, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [85e0869ac9](https://linux-hardware.org/?probe=85e0869ac9) | Nov 19, 2022 |
| Dell          | Latitude E5440              | [f423bbe9b0](https://linux-hardware.org/?probe=f423bbe9b0) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [865fa07274](https://linux-hardware.org/?probe=865fa07274) | Nov 19, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [68d651f36b](https://linux-hardware.org/?probe=68d651f36b) | Nov 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [87219ba8e3](https://linux-hardware.org/?probe=87219ba8e3) | Nov 19, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [6a39161e50](https://linux-hardware.org/?probe=6a39161e50) | Nov 19, 2022 |
| Dell          | Latitude E5440              | [0f98fe6066](https://linux-hardware.org/?probe=0f98fe6066) | Nov 18, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [0cdd3b10fc](https://linux-hardware.org/?probe=0cdd3b10fc) | Nov 18, 2022 |
| Alienware     | m17                         | [e3e14a271a](https://linux-hardware.org/?probe=e3e14a271a) | Nov 17, 2022 |
| Dell          | XPS 15 9570                 | [d62ee2298d](https://linux-hardware.org/?probe=d62ee2298d) | Nov 16, 2022 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [69f54ed610](https://linux-hardware.org/?probe=69f54ed610) | Nov 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3eaa12ef7a](https://linux-hardware.org/?probe=3eaa12ef7a) | Nov 16, 2022 |
| Apple         | MacBookPro11,4              | [91268b9919](https://linux-hardware.org/?probe=91268b9919) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [e2982c0c35](https://linux-hardware.org/?probe=e2982c0c35) | Nov 16, 2022 |
| ASUSTek       | X550VX                      | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | [96db8793b2](https://linux-hardware.org/?probe=96db8793b2) | Nov 15, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | [c576805c81](https://linux-hardware.org/?probe=c576805c81) | Nov 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [35cb137655](https://linux-hardware.org/?probe=35cb137655) | Nov 15, 2022 |
| Alienware     | m17                         | [4140c68e95](https://linux-hardware.org/?probe=4140c68e95) | Nov 15, 2022 |
| Acer          | Aspire A715-42G             | [403bc1b6b5](https://linux-hardware.org/?probe=403bc1b6b5) | Nov 14, 2022 |
| Acer          | Aspire A715-42G             | [6209796b42](https://linux-hardware.org/?probe=6209796b42) | Nov 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [d28a778811](https://linux-hardware.org/?probe=d28a778811) | Nov 14, 2022 |
| Dell          | XPS 13 9380                 | [1501d641b4](https://linux-hardware.org/?probe=1501d641b4) | Nov 14, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [d584008808](https://linux-hardware.org/?probe=d584008808) | Nov 14, 2022 |
| Fujitsu       | LIFEBOOK U7511              | [66656bedcf](https://linux-hardware.org/?probe=66656bedcf) | Nov 14, 2022 |
| Lenovo        | XiaoXinPro 14ACH 2021 82... | [d74b37eebb](https://linux-hardware.org/?probe=d74b37eebb) | Nov 13, 2022 |
| HP            | Laptop 14-dq2xxx            | [dcb6d439d4](https://linux-hardware.org/?probe=dcb6d439d4) | Nov 13, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [7290725ced](https://linux-hardware.org/?probe=7290725ced) | Nov 13, 2022 |
| HONOR         | BOD-WXX9                    | [ca8b207b30](https://linux-hardware.org/?probe=ca8b207b30) | Nov 12, 2022 |
| Packard Be... | EasyNote LJ65               | [1de1737600](https://linux-hardware.org/?probe=1de1737600) | Nov 12, 2022 |
| Gigabyte      | G5 KE                       | [aefbee04fd](https://linux-hardware.org/?probe=aefbee04fd) | Nov 12, 2022 |
| Acer          | AO722                       | [5c51412f98](https://linux-hardware.org/?probe=5c51412f98) | Nov 12, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [7fded9a538](https://linux-hardware.org/?probe=7fded9a538) | Nov 12, 2022 |
| Dell          | Inspiron 15 3511            | [361f37b08d](https://linux-hardware.org/?probe=361f37b08d) | Nov 11, 2022 |
| Google        | Blooglet                    | [bd55466988](https://linux-hardware.org/?probe=bd55466988) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| ASUSTek       | K54C                        | [e347d4a0f5](https://linux-hardware.org/?probe=e347d4a0f5) | Nov 10, 2022 |
| MSI           | GV62 8RC                    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d6fd1a5ecd](https://linux-hardware.org/?probe=d6fd1a5ecd) | Nov 10, 2022 |
| Panasonic     | CF-R9KWCTDR                 | [2a414f5dc5](https://linux-hardware.org/?probe=2a414f5dc5) | Nov 10, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [abbb784ea9](https://linux-hardware.org/?probe=abbb784ea9) | Nov 09, 2022 |
| MSI           | GL63 8RD                    | [e10069a2f8](https://linux-hardware.org/?probe=e10069a2f8) | Nov 09, 2022 |
| HP            | Elite x2 1012 G1            | [0847b8a5d7](https://linux-hardware.org/?probe=0847b8a5d7) | Nov 09, 2022 |
| HP            | Elite x2 1012 G1            | [a5446ab998](https://linux-hardware.org/?probe=a5446ab998) | Nov 09, 2022 |
| Dell          | XPS 15 9550                 | [6642f568d4](https://linux-hardware.org/?probe=6642f568d4) | Nov 09, 2022 |
| HP            | ProBook 430 G3              | [e69d9794fd](https://linux-hardware.org/?probe=e69d9794fd) | Nov 09, 2022 |
| DERE          | V14                         | [0431077216](https://linux-hardware.org/?probe=0431077216) | Nov 08, 2022 |
| HP            | ProBook 430 G3              | [d8bae2c402](https://linux-hardware.org/?probe=d8bae2c402) | Nov 08, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [b4d22497e8](https://linux-hardware.org/?probe=b4d22497e8) | Nov 08, 2022 |
| Dell          | XPS 13 9310                 | [5f358af327](https://linux-hardware.org/?probe=5f358af327) | Nov 08, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [d19fce3e6c](https://linux-hardware.org/?probe=d19fce3e6c) | Nov 08, 2022 |
| Dell          | XPS 13 9360                 | [a35aee6ec2](https://linux-hardware.org/?probe=a35aee6ec2) | Nov 08, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [95b5d8b8ca](https://linux-hardware.org/?probe=95b5d8b8ca) | Nov 07, 2022 |
| MSI           | Modern 14 B5M               | [c2e7afc800](https://linux-hardware.org/?probe=c2e7afc800) | Nov 07, 2022 |
| Packard Be... | EasyNote LJ65               | [c75f470cf8](https://linux-hardware.org/?probe=c75f470cf8) | Nov 06, 2022 |
| Teclast       | F6 Pro                      | [bfba140f45](https://linux-hardware.org/?probe=bfba140f45) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [0d7567fb3f](https://linux-hardware.org/?probe=0d7567fb3f) | Nov 06, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [c3a3d8d222](https://linux-hardware.org/?probe=c3a3d8d222) | Nov 06, 2022 |
| HP            | ProBook 6570b               | [1fec197471](https://linux-hardware.org/?probe=1fec197471) | Nov 06, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [006e91ea03](https://linux-hardware.org/?probe=006e91ea03) | Nov 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3A... | [d53e6cef83](https://linux-hardware.org/?probe=d53e6cef83) | Nov 06, 2022 |
| Clevo         | Modified by dsanke          | [b0c6c10d48](https://linux-hardware.org/?probe=b0c6c10d48) | Nov 05, 2022 |
| COLORFUL      | X15 XS 22                   | [38bc70c9b2](https://linux-hardware.org/?probe=38bc70c9b2) | Nov 04, 2022 |
| COLORFUL      | X15 XS 22                   | [342a90f101](https://linux-hardware.org/?probe=342a90f101) | Nov 04, 2022 |
| Lenovo        | ThinkPad E14 20RA004VPH     | [fbe5c4578c](https://linux-hardware.org/?probe=fbe5c4578c) | Nov 04, 2022 |
| MSI           | Bravo 15 A4DDR              | [8598cf3c36](https://linux-hardware.org/?probe=8598cf3c36) | Nov 04, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [72b1a49ec9](https://linux-hardware.org/?probe=72b1a49ec9) | Nov 04, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [eeda582315](https://linux-hardware.org/?probe=eeda582315) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | [b46456d0c2](https://linux-hardware.org/?probe=b46456d0c2) | Nov 04, 2022 |
| ASUSTek       | X555LJ                      | [e57ec28998](https://linux-hardware.org/?probe=e57ec28998) | Nov 03, 2022 |
| ASUSTek       | X550LD                      | [0847d7c7e6](https://linux-hardware.org/?probe=0847d7c7e6) | Nov 03, 2022 |
| Avell High... | B.ON                        | [f0ea745f7d](https://linux-hardware.org/?probe=f0ea745f7d) | Nov 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e2f82d9c90](https://linux-hardware.org/?probe=e2f82d9c90) | Nov 03, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [ec7425c123](https://linux-hardware.org/?probe=ec7425c123) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [608c7f56e6](https://linux-hardware.org/?probe=608c7f56e6) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [209e99f964](https://linux-hardware.org/?probe=209e99f964) | Nov 02, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [f12fc289fa](https://linux-hardware.org/?probe=f12fc289fa) | Nov 02, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [de1cd69b53](https://linux-hardware.org/?probe=de1cd69b53) | Nov 02, 2022 |
| GPD           | P3 MAX                      | [8b198da775](https://linux-hardware.org/?probe=8b198da775) | Nov 02, 2022 |
| GPD           | P3 MAX                      | [aea8f8bb50](https://linux-hardware.org/?probe=aea8f8bb50) | Nov 02, 2022 |
| Notebook      | P65xHP                      | [68d40fd2c7](https://linux-hardware.org/?probe=68d40fd2c7) | Nov 02, 2022 |
| ASUSTek       | N53Jg                       | [8e4782c668](https://linux-hardware.org/?probe=8e4782c668) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | [4c80b212c6](https://linux-hardware.org/?probe=4c80b212c6) | Nov 01, 2022 |
| Acer          | Swift SF314-512             | [4e92800709](https://linux-hardware.org/?probe=4e92800709) | Nov 01, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7603f28400](https://linux-hardware.org/?probe=7603f28400) | Nov 01, 2022 |
| ASUSTek       | K54C                        | [dd4f63b1e4](https://linux-hardware.org/?probe=dd4f63b1e4) | Nov 01, 2022 |
| Avell High... | B.ON                        | [1eb1bf21ed](https://linux-hardware.org/?probe=1eb1bf21ed) | Oct 31, 2022 |
| Lenovo        | Legion Y7000 2019 1050 8... | [3821dabcb9](https://linux-hardware.org/?probe=3821dabcb9) | Oct 31, 2022 |
| HP            | ProBook 450 G6              | [224f9c8141](https://linux-hardware.org/?probe=224f9c8141) | Oct 30, 2022 |
| HP            | EliteBook 840 G5            | [f8c58b7061](https://linux-hardware.org/?probe=f8c58b7061) | Oct 30, 2022 |
| Dell          | Latitude E5430 non-vPro     | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| HP            | ProBook 640 G4              | [0a7776630f](https://linux-hardware.org/?probe=0a7776630f) | Oct 30, 2022 |
| Apple         | MacBookPro11,2              | [c5955c7440](https://linux-hardware.org/?probe=c5955c7440) | Oct 29, 2022 |
| MSI           | Prestige 14 A10SC           | [1504398ef8](https://linux-hardware.org/?probe=1504398ef8) | Oct 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [1753d78397](https://linux-hardware.org/?probe=1753d78397) | Oct 29, 2022 |
| HP            | OMEN by Laptop              | [610be75cca](https://linux-hardware.org/?probe=610be75cca) | Oct 29, 2022 |
| HP            | Pavilion dv5                | [8bd42e12c3](https://linux-hardware.org/?probe=8bd42e12c3) | Oct 29, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [be41a03a4d](https://linux-hardware.org/?probe=be41a03a4d) | Oct 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [893d006e2f](https://linux-hardware.org/?probe=893d006e2f) | Oct 29, 2022 |
| HP            | 250 G8 Notebook PC          | [59c02d4967](https://linux-hardware.org/?probe=59c02d4967) | Oct 28, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [0dde1fbb38](https://linux-hardware.org/?probe=0dde1fbb38) | Oct 28, 2022 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [8cf64e81cd](https://linux-hardware.org/?probe=8cf64e81cd) | Oct 28, 2022 |
| Avell High... | B.ON                        | [194a1eddc3](https://linux-hardware.org/?probe=194a1eddc3) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [2ad60a938a](https://linux-hardware.org/?probe=2ad60a938a) | Oct 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7d99f01f0e](https://linux-hardware.org/?probe=7d99f01f0e) | Oct 28, 2022 |
| Lenovo        | ThinkPad W540 20BHS0730D    | [f24dc12e06](https://linux-hardware.org/?probe=f24dc12e06) | Oct 28, 2022 |
| Unknown       | Unknown                     | [a03935aadd](https://linux-hardware.org/?probe=a03935aadd) | Oct 27, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [639503102e](https://linux-hardware.org/?probe=639503102e) | Oct 27, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [84acb8d19b](https://linux-hardware.org/?probe=84acb8d19b) | Oct 27, 2022 |
| Unknown       | Unknown                     | [069ce9d405](https://linux-hardware.org/?probe=069ce9d405) | Oct 27, 2022 |
| Apple         | MacBookAir7,2               | [abadd71c90](https://linux-hardware.org/?probe=abadd71c90) | Oct 27, 2022 |
| Lenovo        | ThinkPad T480s 20L8S5YM0... | [c348de09bf](https://linux-hardware.org/?probe=c348de09bf) | Oct 26, 2022 |
| Lenovo        | ThinkPad T480 20L50000IX    | [bcb1b11c50](https://linux-hardware.org/?probe=bcb1b11c50) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| HP            | 250 G8 Notebook PC          | [d4ebaa71a2](https://linux-hardware.org/?probe=d4ebaa71a2) | Oct 26, 2022 |
| Dell          | Precision 5570              | [67d7b55dab](https://linux-hardware.org/?probe=67d7b55dab) | Oct 26, 2022 |
| Timi          | A7S                         | [004df6b9a1](https://linux-hardware.org/?probe=004df6b9a1) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [307356784a](https://linux-hardware.org/?probe=307356784a) | Oct 26, 2022 |
| Dell          | Latitude E5570              | [2d59f069b4](https://linux-hardware.org/?probe=2d59f069b4) | Oct 26, 2022 |
| HUAWEI        | HN-WX9X                     | [042ffc026d](https://linux-hardware.org/?probe=042ffc026d) | Oct 26, 2022 |
| Timi          | A7S                         | [77a87009dd](https://linux-hardware.org/?probe=77a87009dd) | Oct 26, 2022 |
| Apple         | MacBookPro10,1              | [212ce8900d](https://linux-hardware.org/?probe=212ce8900d) | Oct 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [53e6b23ebf](https://linux-hardware.org/?probe=53e6b23ebf) | Oct 26, 2022 |
| Dell          | Latitude E6430              | [f196a9762f](https://linux-hardware.org/?probe=f196a9762f) | Oct 25, 2022 |
| Dell          | Latitude E6430              | [8062ec17fd](https://linux-hardware.org/?probe=8062ec17fd) | Oct 25, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [2d7fa062e3](https://linux-hardware.org/?probe=2d7fa062e3) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [cca91f3fe8](https://linux-hardware.org/?probe=cca91f3fe8) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [8f34a9c24c](https://linux-hardware.org/?probe=8f34a9c24c) | Oct 25, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [1f939e0414](https://linux-hardware.org/?probe=1f939e0414) | Oct 25, 2022 |
| Acer          | Aspire A715-42G             | [72b73a6552](https://linux-hardware.org/?probe=72b73a6552) | Oct 25, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [26415e4b74](https://linux-hardware.org/?probe=26415e4b74) | Oct 25, 2022 |
| Dell          | Inspiron 7559               | [2a1b8eb060](https://linux-hardware.org/?probe=2a1b8eb060) | Oct 25, 2022 |
| HP            | 255 G8 Notebook PC          | [30c305f07c](https://linux-hardware.org/?probe=30c305f07c) | Oct 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3146a3d644](https://linux-hardware.org/?probe=3146a3d644) | Oct 25, 2022 |
| ASUSTek       | GL553VD                     | [20278229cd](https://linux-hardware.org/?probe=20278229cd) | Oct 25, 2022 |
| Acer          | Aspire A515-45              | [4584821ae6](https://linux-hardware.org/?probe=4584821ae6) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [169601c723](https://linux-hardware.org/?probe=169601c723) | Oct 25, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [efb9c3d448](https://linux-hardware.org/?probe=efb9c3d448) | Oct 25, 2022 |
| Lenovo        | B51-80 80LM                 | [aaed1997fd](https://linux-hardware.org/?probe=aaed1997fd) | Oct 25, 2022 |
| Fujitsu       | LIFEBOOK A532               | [e176b2ac7c](https://linux-hardware.org/?probe=e176b2ac7c) | Oct 25, 2022 |
| Dell          | Inspiron 13-7359            | [5a6d4ce6e7](https://linux-hardware.org/?probe=5a6d4ce6e7) | Oct 25, 2022 |
| Acer          | Aspire A515-52G             | [f569841512](https://linux-hardware.org/?probe=f569841512) | Oct 24, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [4948eb3b16](https://linux-hardware.org/?probe=4948eb3b16) | Oct 24, 2022 |
| Lenovo        | ThinkPad T480 20L5000AIX    | [43650773c9](https://linux-hardware.org/?probe=43650773c9) | Oct 24, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [d663683611](https://linux-hardware.org/?probe=d663683611) | Oct 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [417beae8e5](https://linux-hardware.org/?probe=417beae8e5) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [7733e4f8d5](https://linux-hardware.org/?probe=7733e4f8d5) | Oct 24, 2022 |
| Acer          | Aspire A315-42              | [20dcade848](https://linux-hardware.org/?probe=20dcade848) | Oct 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [d4c62f39e3](https://linux-hardware.org/?probe=d4c62f39e3) | Oct 24, 2022 |
| Acer          | Aspire A515-45              | [b39d63f4f2](https://linux-hardware.org/?probe=b39d63f4f2) | Oct 24, 2022 |
| ASUSTek       | K54C                        | [acf64b4ced](https://linux-hardware.org/?probe=acf64b4ced) | Oct 24, 2022 |
| Apple         | MacBookAir7,2               | [d7e99b5869](https://linux-hardware.org/?probe=d7e99b5869) | Oct 24, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c24c3f0836](https://linux-hardware.org/?probe=c24c3f0836) | Oct 23, 2022 |
| Dell          | Vostro 3491                 | [8809be3a93](https://linux-hardware.org/?probe=8809be3a93) | Oct 23, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6EH0... | [794fa1859f](https://linux-hardware.org/?probe=794fa1859f) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [514642847b](https://linux-hardware.org/?probe=514642847b) | Oct 22, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [a22e54462c](https://linux-hardware.org/?probe=a22e54462c) | Oct 21, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [07acd27a70](https://linux-hardware.org/?probe=07acd27a70) | Oct 21, 2022 |
| HP            | EliteBook 840 G1            | [837845f259](https://linux-hardware.org/?probe=837845f259) | Oct 20, 2022 |
| Dell          | Latitude E6500              | [d64ffd6f2e](https://linux-hardware.org/?probe=d64ffd6f2e) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [4c0b27f18e](https://linux-hardware.org/?probe=4c0b27f18e) | Oct 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7cd6e349f0](https://linux-hardware.org/?probe=7cd6e349f0) | Oct 20, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d042d922e5](https://linux-hardware.org/?probe=d042d922e5) | Oct 20, 2022 |
| HP            | 250 G8 Notebook PC          | [e8dc04cc0e](https://linux-hardware.org/?probe=e8dc04cc0e) | Oct 20, 2022 |
| Dell          | Inspiron 5584               | [79ec522ef8](https://linux-hardware.org/?probe=79ec522ef8) | Oct 20, 2022 |
| HP            | Pavilion dm4                | [d96f382cc2](https://linux-hardware.org/?probe=d96f382cc2) | Oct 19, 2022 |
| HP            | Pavilion dm4                | [171745a6e8](https://linux-hardware.org/?probe=171745a6e8) | Oct 19, 2022 |
| Dell          | Inspiron 5584               | [4dac48ea7f](https://linux-hardware.org/?probe=4dac48ea7f) | Oct 19, 2022 |
| MOTILE        | M141                        | [a6da22306f](https://linux-hardware.org/?probe=a6da22306f) | Oct 19, 2022 |
| Acer          | Aspire A515-51              | [0022d7c5ef](https://linux-hardware.org/?probe=0022d7c5ef) | Oct 19, 2022 |
| HP            | 255 G8 Notebook PC          | [2f69a96661](https://linux-hardware.org/?probe=2f69a96661) | Oct 18, 2022 |
| Samsung       | 270E5J/2570EJ               | [f2750b0a70](https://linux-hardware.org/?probe=f2750b0a70) | Oct 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8bc82af4e5](https://linux-hardware.org/?probe=8bc82af4e5) | Oct 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [437cb780cb](https://linux-hardware.org/?probe=437cb780cb) | Oct 18, 2022 |
| Avell High... | B.ON                        | [fc8b4d7534](https://linux-hardware.org/?probe=fc8b4d7534) | Oct 18, 2022 |
| Dell          | Vostro 7580                 | [69cc3a8c62](https://linux-hardware.org/?probe=69cc3a8c62) | Oct 18, 2022 |
| HP            | 255 G8 Notebook PC          | [cb651a5071](https://linux-hardware.org/?probe=cb651a5071) | Oct 17, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [e3eba59f05](https://linux-hardware.org/?probe=e3eba59f05) | Oct 17, 2022 |
| MECHREVO      | Code01 Ver2.0               | [5fbae9cfcf](https://linux-hardware.org/?probe=5fbae9cfcf) | Oct 17, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [e39622cea9](https://linux-hardware.org/?probe=e39622cea9) | Oct 17, 2022 |
| Dell          | Inspiron 3521               | [f7b9f3cab2](https://linux-hardware.org/?probe=f7b9f3cab2) | Oct 17, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [e38add57d6](https://linux-hardware.org/?probe=e38add57d6) | Oct 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS6DV00     | [472b64041d](https://linux-hardware.org/?probe=472b64041d) | Oct 16, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [babb66e9c9](https://linux-hardware.org/?probe=babb66e9c9) | Oct 16, 2022 |
| Alienware     | m15 R6                      | [3cb0cb3e9d](https://linux-hardware.org/?probe=3cb0cb3e9d) | Oct 15, 2022 |
| Acer          | Aspire A515-45              | [7a8b3b953d](https://linux-hardware.org/?probe=7a8b3b953d) | Oct 15, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [d56a8a035a](https://linux-hardware.org/?probe=d56a8a035a) | Oct 15, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [6adb156840](https://linux-hardware.org/?probe=6adb156840) | Oct 15, 2022 |
| Dell          | Precision M4500             | [36048a8407](https://linux-hardware.org/?probe=36048a8407) | Oct 15, 2022 |
| Lenovo        | ThinkPad L420 78545EG       | [d2c975644c](https://linux-hardware.org/?probe=d2c975644c) | Oct 15, 2022 |
| ASUSTek       | X553MA                      | [ade1f0f879](https://linux-hardware.org/?probe=ade1f0f879) | Oct 14, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [fbb018d1ef](https://linux-hardware.org/?probe=fbb018d1ef) | Oct 14, 2022 |
| Dell          | Precision M4800             | [aa9a1680fd](https://linux-hardware.org/?probe=aa9a1680fd) | Oct 14, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [973f501233](https://linux-hardware.org/?probe=973f501233) | Oct 13, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | [f80eb01da1](https://linux-hardware.org/?probe=f80eb01da1) | Oct 13, 2022 |
| HP            | ProBook 640 G4              | [3d832d1780](https://linux-hardware.org/?probe=3d832d1780) | Oct 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [d3ade506f7](https://linux-hardware.org/?probe=d3ade506f7) | Oct 12, 2022 |
| Acer          | Nitro AN515-52              | [212c135857](https://linux-hardware.org/?probe=212c135857) | Oct 12, 2022 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [8b554dcfe0](https://linux-hardware.org/?probe=8b554dcfe0) | Oct 12, 2022 |
| Dell          | Latitude E6420              | [0083bd14b8](https://linux-hardware.org/?probe=0083bd14b8) | Oct 12, 2022 |
| Unknown       | Unknown                     | [ac743b08fa](https://linux-hardware.org/?probe=ac743b08fa) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Lenovo        | ThinkPad X201 3680FAG       | [f44ca565c1](https://linux-hardware.org/?probe=f44ca565c1) | Oct 11, 2022 |
| AMI           | Cherry Trail CR             | [7d3c652547](https://linux-hardware.org/?probe=7d3c652547) | Oct 11, 2022 |
| Lenovo        | ThinkPad T410 2522E38       | [7d923eff3f](https://linux-hardware.org/?probe=7d923eff3f) | Oct 11, 2022 |
| Acer          | Nitro AN515-52              | [8e1e663189](https://linux-hardware.org/?probe=8e1e663189) | Oct 10, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [d6e11d36a8](https://linux-hardware.org/?probe=d6e11d36a8) | Oct 10, 2022 |
| Framework     | Laptop                      | [b5fe425089](https://linux-hardware.org/?probe=b5fe425089) | Oct 10, 2022 |
| HP            | EliteBook 8730w             | [e7545a94b2](https://linux-hardware.org/?probe=e7545a94b2) | Oct 09, 2022 |
| HP            | EliteBook 8730w             | [b938a96086](https://linux-hardware.org/?probe=b938a96086) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [62e134c294](https://linux-hardware.org/?probe=62e134c294) | Oct 09, 2022 |
| Dell          | XPS 13 9370                 | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Timi          | Mi Laptop Pro 15            | [f756c2bb92](https://linux-hardware.org/?probe=f756c2bb92) | Oct 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [a431b20f04](https://linux-hardware.org/?probe=a431b20f04) | Oct 07, 2022 |
| Acer          | Aspire A515-57G             | [f8d3a419e6](https://linux-hardware.org/?probe=f8d3a419e6) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [5ace2d0c1f](https://linux-hardware.org/?probe=5ace2d0c1f) | Oct 06, 2022 |
| MSI           | Modern 15 A5M               | [035a9bb7fa](https://linux-hardware.org/?probe=035a9bb7fa) | Oct 05, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [3338607f1a](https://linux-hardware.org/?probe=3338607f1a) | Oct 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [74130061ff](https://linux-hardware.org/?probe=74130061ff) | Oct 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [72a5f6b03c](https://linux-hardware.org/?probe=72a5f6b03c) | Oct 05, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a51c98849b](https://linux-hardware.org/?probe=a51c98849b) | Oct 05, 2022 |
| Dell          | XPS 15 9570                 | [0edf82b5be](https://linux-hardware.org/?probe=0edf82b5be) | Oct 05, 2022 |
| Avell High... | B.ON                        | [2b629889c7](https://linux-hardware.org/?probe=2b629889c7) | Oct 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a4b830a39b](https://linux-hardware.org/?probe=a4b830a39b) | Oct 04, 2022 |
| Acer          | Aspire ES1-572              | [1bd18c9a15](https://linux-hardware.org/?probe=1bd18c9a15) | Oct 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [62b67bffae](https://linux-hardware.org/?probe=62b67bffae) | Oct 04, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [e07e70b822](https://linux-hardware.org/?probe=e07e70b822) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [790114327c](https://linux-hardware.org/?probe=790114327c) | Oct 04, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [85bcec60e7](https://linux-hardware.org/?probe=85bcec60e7) | Oct 04, 2022 |
| Dell          | XPS 13 9300                 | [00ecde42a1](https://linux-hardware.org/?probe=00ecde42a1) | Oct 02, 2022 |
| UNOWHY        | Y13G012S4EI                 | [5c4c517651](https://linux-hardware.org/?probe=5c4c517651) | Oct 02, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [9a2de7b77f](https://linux-hardware.org/?probe=9a2de7b77f) | Oct 02, 2022 |
| UNOWHY        | Y13G012S4EI                 | [014d8c23f8](https://linux-hardware.org/?probe=014d8c23f8) | Oct 01, 2022 |
| Google        | Blooglet                    | [0081fa7064](https://linux-hardware.org/?probe=0081fa7064) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [0a022a22c6](https://linux-hardware.org/?probe=0a022a22c6) | Oct 01, 2022 |
| HP            | 655                         | [6b10f9eda8](https://linux-hardware.org/?probe=6b10f9eda8) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | [82e89b9263](https://linux-hardware.org/?probe=82e89b9263) | Oct 01, 2022 |
| Dell          | Inspiron 5567               | [e64a9cf0e2](https://linux-hardware.org/?probe=e64a9cf0e2) | Oct 01, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [1aa913c010](https://linux-hardware.org/?probe=1aa913c010) | Oct 01, 2022 |
| Acer          | Swift SF314-43              | [cfd0c22e29](https://linux-hardware.org/?probe=cfd0c22e29) | Sep 30, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [71ef5c4f0e](https://linux-hardware.org/?probe=71ef5c4f0e) | Sep 30, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | [16f1ddb076](https://linux-hardware.org/?probe=16f1ddb076) | Sep 30, 2022 |
| Dell          | XPS 13 7390                 | [c4ccdf9992](https://linux-hardware.org/?probe=c4ccdf9992) | Sep 30, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMB    | [0c8a6ce686](https://linux-hardware.org/?probe=0c8a6ce686) | Sep 29, 2022 |
| TUXEDO        | Book_XA1510                 | [f39b64916d](https://linux-hardware.org/?probe=f39b64916d) | Sep 29, 2022 |
| Lenovo        | ThinkPad T430 23501K0       | [124afba97e](https://linux-hardware.org/?probe=124afba97e) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [fbc4f29134](https://linux-hardware.org/?probe=fbc4f29134) | Sep 28, 2022 |
| Lenovo        | Legion R70002021 82JW       | [b12e5d06a3](https://linux-hardware.org/?probe=b12e5d06a3) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d4797ada2a](https://linux-hardware.org/?probe=d4797ada2a) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | [4073c084df](https://linux-hardware.org/?probe=4073c084df) | Sep 28, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [04fbd64661](https://linux-hardware.org/?probe=04fbd64661) | Sep 27, 2022 |
| HP            | Laptop 15-dw3xxx            | [d7dcd834e2](https://linux-hardware.org/?probe=d7dcd834e2) | Sep 27, 2022 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [56131c4db0](https://linux-hardware.org/?probe=56131c4db0) | Sep 27, 2022 |
| Timi          | TM1604                      | [2ee795db1a](https://linux-hardware.org/?probe=2ee795db1a) | Sep 27, 2022 |
| Lenovo        | V15-ADA 82C7                | [e53b87c0fd](https://linux-hardware.org/?probe=e53b87c0fd) | Sep 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [95c0fd6047](https://linux-hardware.org/?probe=95c0fd6047) | Sep 26, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [d9187e470e](https://linux-hardware.org/?probe=d9187e470e) | Sep 26, 2022 |
| Dell          | G15 5511                    | [f960f38940](https://linux-hardware.org/?probe=f960f38940) | Sep 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [109d0ef34c](https://linux-hardware.org/?probe=109d0ef34c) | Sep 26, 2022 |
| MSI           | GS65 Stealth 9SE            | [0c8e0eb1f5](https://linux-hardware.org/?probe=0c8e0eb1f5) | Sep 26, 2022 |
| Dell          | Inspiron 5570               | [6af4756d35](https://linux-hardware.org/?probe=6af4756d35) | Sep 25, 2022 |
| MECHREVO      | Code01 Ver2.0               | [18246c5a9e](https://linux-hardware.org/?probe=18246c5a9e) | Sep 25, 2022 |
| Dell          | XPS 15 9510                 | [1ccf6c5c41](https://linux-hardware.org/?probe=1ccf6c5c41) | Sep 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [bdc8453efc](https://linux-hardware.org/?probe=bdc8453efc) | Sep 24, 2022 |
| Acer          | Aspire A314-22              | [31b11c4544](https://linux-hardware.org/?probe=31b11c4544) | Sep 24, 2022 |
| Dell          | Precision 7560              | [8124a7a3eb](https://linux-hardware.org/?probe=8124a7a3eb) | Sep 24, 2022 |
| Lenovo        | ThinkPad P52s 20LCS03L38    | [5d9c8cd268](https://linux-hardware.org/?probe=5d9c8cd268) | Sep 23, 2022 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [0121aac33a](https://linux-hardware.org/?probe=0121aac33a) | Sep 22, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [672d6f2fc8](https://linux-hardware.org/?probe=672d6f2fc8) | Sep 22, 2022 |
| HP            | Laptop 15-bs1xx             | [5657597c18](https://linux-hardware.org/?probe=5657597c18) | Sep 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [52bb32a60c](https://linux-hardware.org/?probe=52bb32a60c) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [628fd0d32d](https://linux-hardware.org/?probe=628fd0d32d) | Sep 21, 2022 |
| ASUSTek       | K46CB                       | [88cbbeaee6](https://linux-hardware.org/?probe=88cbbeaee6) | Sep 20, 2022 |
| Valve         | Jupiter                     | [3aeb184ce4](https://linux-hardware.org/?probe=3aeb184ce4) | Sep 20, 2022 |
| HP            | EliteBook 850 G3            | [7bbcf621e1](https://linux-hardware.org/?probe=7bbcf621e1) | Sep 20, 2022 |
| Dell          | Inspiron 5570               | [16d661b4e5](https://linux-hardware.org/?probe=16d661b4e5) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | [b84e8d2682](https://linux-hardware.org/?probe=b84e8d2682) | Sep 20, 2022 |
| Lenovo        | Legion R70002021 82JW       | [4779dfc2b0](https://linux-hardware.org/?probe=4779dfc2b0) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [b07937de6a](https://linux-hardware.org/?probe=b07937de6a) | Sep 20, 2022 |
| HP            | Dev One Notebook PC         | [97426638ff](https://linux-hardware.org/?probe=97426638ff) | Sep 20, 2022 |
| HP            | Dev One Notebook PC         | [5367a8e71f](https://linux-hardware.org/?probe=5367a8e71f) | Sep 20, 2022 |
| Dell          | Latitude 7390               | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [e149495b74](https://linux-hardware.org/?probe=e149495b74) | Sep 19, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f454a8f6a5](https://linux-hardware.org/?probe=f454a8f6a5) | Sep 19, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [3862ccf53f](https://linux-hardware.org/?probe=3862ccf53f) | Sep 19, 2022 |
| Acer          | Swift SF314-42              | [f52b35d82d](https://linux-hardware.org/?probe=f52b35d82d) | Sep 19, 2022 |
| Dell          | XPS 13 9305                 | [9d61a37458](https://linux-hardware.org/?probe=9d61a37458) | Sep 19, 2022 |
| Dell          | Inspiron 5566               | [58d84150d6](https://linux-hardware.org/?probe=58d84150d6) | Sep 18, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [cd1441d5a4](https://linux-hardware.org/?probe=cd1441d5a4) | Sep 18, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [dce5b5917c](https://linux-hardware.org/?probe=dce5b5917c) | Sep 18, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [aa3908e5fc](https://linux-hardware.org/?probe=aa3908e5fc) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | [eb488dae73](https://linux-hardware.org/?probe=eb488dae73) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [abca74f17e](https://linux-hardware.org/?probe=abca74f17e) | Sep 17, 2022 |
| HP            | EliteBook 840 G5            | [eb406c0e81](https://linux-hardware.org/?probe=eb406c0e81) | Sep 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a26e1ad502](https://linux-hardware.org/?probe=a26e1ad502) | Sep 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6ff152e455](https://linux-hardware.org/?probe=6ff152e455) | Sep 15, 2022 |
| HUAWEI        | KLVD-WXX9                   | [9e0c10b8e3](https://linux-hardware.org/?probe=9e0c10b8e3) | Sep 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d0d43b3cc5](https://linux-hardware.org/?probe=d0d43b3cc5) | Sep 14, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [b7ed5c7f4a](https://linux-hardware.org/?probe=b7ed5c7f4a) | Sep 14, 2022 |
| HP            | EliteBook 840 G5            | [6b6e4efdfc](https://linux-hardware.org/?probe=6b6e4efdfc) | Sep 13, 2022 |
| Samsung       | 950XED                      | [f8a15210f0](https://linux-hardware.org/?probe=f8a15210f0) | Sep 13, 2022 |
| ASUSTek       | X555LJ                      | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| Toshiba       | Satellite U845W             | [030a371841](https://linux-hardware.org/?probe=030a371841) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [410b905321](https://linux-hardware.org/?probe=410b905321) | Sep 11, 2022 |
| MECHREVO      | Code01 Ver2.0               | [c55fd8d477](https://linux-hardware.org/?probe=c55fd8d477) | Sep 11, 2022 |
| MSI           | Alpha 15 B5EEK              | [c59ebfd9e8](https://linux-hardware.org/?probe=c59ebfd9e8) | Sep 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [46c51b7097](https://linux-hardware.org/?probe=46c51b7097) | Sep 11, 2022 |
| Dell          | Latitude 7424 Rugged Ext... | [0e5e98a9e2](https://linux-hardware.org/?probe=0e5e98a9e2) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | [d2c057ed6e](https://linux-hardware.org/?probe=d2c057ed6e) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 23444ZG       | [d83eee9752](https://linux-hardware.org/?probe=d83eee9752) | Sep 11, 2022 |
| Samsung       | 750XED                      | [ea68f0910d](https://linux-hardware.org/?probe=ea68f0910d) | Sep 10, 2022 |
| Samsung       | 750XED                      | [475088329e](https://linux-hardware.org/?probe=475088329e) | Sep 10, 2022 |
| Framework     | Laptop                      | [b0b7801b11](https://linux-hardware.org/?probe=b0b7801b11) | Sep 10, 2022 |
| Lenovo        | ThinkPad X230 23252QG       | [4146ff55f9](https://linux-hardware.org/?probe=4146ff55f9) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [3c214d75b2](https://linux-hardware.org/?probe=3c214d75b2) | Sep 10, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [4911a898bd](https://linux-hardware.org/?probe=4911a898bd) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f5c538e2c7](https://linux-hardware.org/?probe=f5c538e2c7) | Sep 09, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| Medion        | S4216                       | [1f1e6b24bf](https://linux-hardware.org/?probe=1f1e6b24bf) | Sep 08, 2022 |
| Dell          | Latitude 7350               | [4a30d9431e](https://linux-hardware.org/?probe=4a30d9431e) | Sep 08, 2022 |
| Google        | Rabbid                      | [636b8205ae](https://linux-hardware.org/?probe=636b8205ae) | Sep 08, 2022 |
| Google        | Rabbid                      | [f33074ee09](https://linux-hardware.org/?probe=f33074ee09) | Sep 08, 2022 |
| LG Electro... | 17Z90P-G.AA86D              | [1f304e9792](https://linux-hardware.org/?probe=1f304e9792) | Sep 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [a5fdc97073](https://linux-hardware.org/?probe=a5fdc97073) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e88363a341](https://linux-hardware.org/?probe=e88363a341) | Sep 07, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [ec22409311](https://linux-hardware.org/?probe=ec22409311) | Sep 07, 2022 |
| Acer          | Aspire A315-34              | [893afb133c](https://linux-hardware.org/?probe=893afb133c) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [a4f8e52425](https://linux-hardware.org/?probe=a4f8e52425) | Sep 06, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [3ce6c0f44c](https://linux-hardware.org/?probe=3ce6c0f44c) | Sep 06, 2022 |
| Acer          | Aspire A515-44G             | [0daca2662d](https://linux-hardware.org/?probe=0daca2662d) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d55d359a3e](https://linux-hardware.org/?probe=d55d359a3e) | Sep 05, 2022 |
| Dell          | Latitude E6520              | [e37ba07a92](https://linux-hardware.org/?probe=e37ba07a92) | Sep 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [92d04feeca](https://linux-hardware.org/?probe=92d04feeca) | Sep 05, 2022 |
| Dell          | Precision 3571              | [d9939fbfd4](https://linux-hardware.org/?probe=d9939fbfd4) | Sep 05, 2022 |
| Google        | Coral                       | [af898f9be4](https://linux-hardware.org/?probe=af898f9be4) | Sep 05, 2022 |
| Acer          | Swift SF314-41              | [aa90cb0d30](https://linux-hardware.org/?probe=aa90cb0d30) | Sep 04, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [c9d51bfae8](https://linux-hardware.org/?probe=c9d51bfae8) | Sep 04, 2022 |
| Acer          | Swift SF314-41              | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e30f86bc30](https://linux-hardware.org/?probe=e30f86bc30) | Sep 03, 2022 |
| Dell          | Latitude 7350               | [f52406cbf2](https://linux-hardware.org/?probe=f52406cbf2) | Sep 03, 2022 |
| Dell          | XPS 15 9570                 | [b313706909](https://linux-hardware.org/?probe=b313706909) | Sep 03, 2022 |
| TUXEDO        | Book_XA1510                 | [e379f966da](https://linux-hardware.org/?probe=e379f966da) | Sep 03, 2022 |
| Apple         | MacBook5,1                  | [0f5aab705f](https://linux-hardware.org/?probe=0f5aab705f) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6b62abaaaf](https://linux-hardware.org/?probe=6b62abaaaf) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ec466abbf7](https://linux-hardware.org/?probe=ec466abbf7) | Sep 03, 2022 |
| HP            | 15                          | [48493c0282](https://linux-hardware.org/?probe=48493c0282) | Sep 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [c073d9fb9f](https://linux-hardware.org/?probe=c073d9fb9f) | Sep 03, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2199481d0a](https://linux-hardware.org/?probe=2199481d0a) | Sep 03, 2022 |
| Lenovo        | ThinkPad L390 20NSS11E00    | [d5dbbd658f](https://linux-hardware.org/?probe=d5dbbd658f) | Sep 03, 2022 |
| ASUSTek       | N501VW                      | [e7e5ddf474](https://linux-hardware.org/?probe=e7e5ddf474) | Sep 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [7c04c344cb](https://linux-hardware.org/?probe=7c04c344cb) | Sep 02, 2022 |
| Dell          | Inspiron 5577               | [b06eacf424](https://linux-hardware.org/?probe=b06eacf424) | Sep 02, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cd935b0146](https://linux-hardware.org/?probe=cd935b0146) | Sep 02, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | XPS 15 9520                 | [f1cfdb5e32](https://linux-hardware.org/?probe=f1cfdb5e32) | Sep 02, 2022 |
| Acer          | Aspire 5742                 | [fadbc676b4](https://linux-hardware.org/?probe=fadbc676b4) | Sep 02, 2022 |
| Toshiba       | Satellite C55D-B            | [4f9267de27](https://linux-hardware.org/?probe=4f9267de27) | Sep 02, 2022 |
| MECHREVO      | Code01 Ver2.0               | [6456a1b04f](https://linux-hardware.org/?probe=6456a1b04f) | Sep 02, 2022 |
| Acer          | Aspire 4349                 | [1918459ea4](https://linux-hardware.org/?probe=1918459ea4) | Sep 02, 2022 |
| MECHREVO      | Code01 Ver2.0               | [f88772c4dc](https://linux-hardware.org/?probe=f88772c4dc) | Sep 01, 2022 |
| Purism        | Librem 14                   | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c9841acd77](https://linux-hardware.org/?probe=c9841acd77) | Sep 01, 2022 |
| HUAWEI        | HKD-WXX                     | [7ff88a93c2](https://linux-hardware.org/?probe=7ff88a93c2) | Sep 01, 2022 |
| MECHREVO      | Code01 Ver2.0               | [bbe5fe0eac](https://linux-hardware.org/?probe=bbe5fe0eac) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Notebook      | NH5xAx                      | [e8487cd15f](https://linux-hardware.org/?probe=e8487cd15f) | Aug 31, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [ef34b3c3aa](https://linux-hardware.org/?probe=ef34b3c3aa) | Aug 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [3d7c0ee13d](https://linux-hardware.org/?probe=3d7c0ee13d) | Aug 30, 2022 |
| ASUSTek       | E202SA                      | [393cb25da2](https://linux-hardware.org/?probe=393cb25da2) | Aug 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| HP            | EliteBook 820 G3            | [4ea311ca8e](https://linux-hardware.org/?probe=4ea311ca8e) | Aug 30, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c44a50e117](https://linux-hardware.org/?probe=c44a50e117) | Aug 29, 2022 |
| MSI           | Modern 14 B10MW             | [c107217cf8](https://linux-hardware.org/?probe=c107217cf8) | Aug 28, 2022 |
| Framework     | Laptop                      | [71c896cd39](https://linux-hardware.org/?probe=71c896cd39) | Aug 28, 2022 |
| Dell          | Inspiron 5577               | [b40621d5f6](https://linux-hardware.org/?probe=b40621d5f6) | Aug 28, 2022 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [1d29556c76](https://linux-hardware.org/?probe=1d29556c76) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [d056fbc982](https://linux-hardware.org/?probe=d056fbc982) | Aug 28, 2022 |
| BBEN          | G16                         | [6b0b170e1c](https://linux-hardware.org/?probe=6b0b170e1c) | Aug 28, 2022 |
| BBEN          | G16                         | [66fc9bd46b](https://linux-hardware.org/?probe=66fc9bd46b) | Aug 28, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa84c700c6](https://linux-hardware.org/?probe=aa84c700c6) | Aug 28, 2022 |
| Dell          | Latitude 3150               | [09f1514148](https://linux-hardware.org/?probe=09f1514148) | Aug 27, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8841ba5f53](https://linux-hardware.org/?probe=8841ba5f53) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| Dell          | Latitude 7350               | [c784fd2743](https://linux-hardware.org/?probe=c784fd2743) | Aug 26, 2022 |
| Acer          | Aspire A515-45              | [c0b89ea222](https://linux-hardware.org/?probe=c0b89ea222) | Aug 26, 2022 |
| Lenovo        | ThinkPad T430 2344BMU       | [c164d20c15](https://linux-hardware.org/?probe=c164d20c15) | Aug 26, 2022 |
| Dell          | Latitude 7424 Rugged Ext... | [9770e301cd](https://linux-hardware.org/?probe=9770e301cd) | Aug 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [fcfd89bb32](https://linux-hardware.org/?probe=fcfd89bb32) | Aug 25, 2022 |
| ASUSTek       | X580VD                      | [c579b49e4c](https://linux-hardware.org/?probe=c579b49e4c) | Aug 25, 2022 |
| HP            | ZBook 15 G6                 | [e51675ce88](https://linux-hardware.org/?probe=e51675ce88) | Aug 24, 2022 |
| ASUSTek       | X751LD                      | [7ce95dab0a](https://linux-hardware.org/?probe=7ce95dab0a) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Dell          | XPS L421X                   | [227df9dc9e](https://linux-hardware.org/?probe=227df9dc9e) | Aug 24, 2022 |
| Acer          | Nitro AN515-45              | [98c26372c2](https://linux-hardware.org/?probe=98c26372c2) | Aug 23, 2022 |
| LG Electro... | S430-G.BC33P1               | [d0b4cf47fe](https://linux-hardware.org/?probe=d0b4cf47fe) | Aug 23, 2022 |
| Acer          | Swift SF114-33              | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| MSI           | GS73VR 6RF                  | [870534e620](https://linux-hardware.org/?probe=870534e620) | Aug 23, 2022 |
| MSI           | GL75 Leopard 10SDK          | [7004b23b33](https://linux-hardware.org/?probe=7004b23b33) | Aug 23, 2022 |
| Dell          | XPS 15 9570                 | [6cc47c9a0d](https://linux-hardware.org/?probe=6cc47c9a0d) | Aug 23, 2022 |
| Dell          | Latitude 7390               | [0d626db6e1](https://linux-hardware.org/?probe=0d626db6e1) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [d08e00053f](https://linux-hardware.org/?probe=d08e00053f) | Aug 22, 2022 |
| Toshiba       | Satellite P55t-C            | [70560700a6](https://linux-hardware.org/?probe=70560700a6) | Aug 22, 2022 |
| ASUSTek       | X555UB                      | [a1db92c63c](https://linux-hardware.org/?probe=a1db92c63c) | Aug 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ada7663387](https://linux-hardware.org/?probe=ada7663387) | Aug 21, 2022 |
| SLIMBOOK      | PROX14-AMD                  | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| HP            | Laptop 14-dk1xxx            | [4875c1533b](https://linux-hardware.org/?probe=4875c1533b) | Aug 21, 2022 |
| BBEN          | G16                         | [f9768aedb9](https://linux-hardware.org/?probe=f9768aedb9) | Aug 21, 2022 |
| BBEN          | G16                         | [d491f08ce0](https://linux-hardware.org/?probe=d491f08ce0) | Aug 21, 2022 |
| HP            | Pavilion g4                 | [f8c2fc628e](https://linux-hardware.org/?probe=f8c2fc628e) | Aug 21, 2022 |
| Acer          | Aspire E5-575               | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Acer          | Aspire A315-23G             | [e31fb3f3cf](https://linux-hardware.org/?probe=e31fb3f3cf) | Aug 21, 2022 |
| HP            | ENVY 15                     | [5d984dedf6](https://linux-hardware.org/?probe=5d984dedf6) | Aug 20, 2022 |
| MSI           | Modern 14 B5M               | [9a8166de9b](https://linux-hardware.org/?probe=9a8166de9b) | Aug 20, 2022 |
| realme        | RMNBXXXX                    | [d98be8821f](https://linux-hardware.org/?probe=d98be8821f) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [4f711bf806](https://linux-hardware.org/?probe=4f711bf806) | Aug 20, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c6bb19402d](https://linux-hardware.org/?probe=c6bb19402d) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Dell          | Inspiron 5558               | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Framework     | Laptop                      | [a8988f1665](https://linux-hardware.org/?probe=a8988f1665) | Aug 18, 2022 |
| Dell          | Latitude 7390               | [d726450b55](https://linux-hardware.org/?probe=d726450b55) | Aug 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [0dbc32a26d](https://linux-hardware.org/?probe=0dbc32a26d) | Aug 17, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [ff64bb7593](https://linux-hardware.org/?probe=ff64bb7593) | Aug 17, 2022 |
| TPVAOC        | AA183M                      | [089472ea13](https://linux-hardware.org/?probe=089472ea13) | Aug 16, 2022 |
| Dell          | Vostro 2420                 | [1d2b1aa4bf](https://linux-hardware.org/?probe=1d2b1aa4bf) | Aug 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [eb37729065](https://linux-hardware.org/?probe=eb37729065) | Aug 16, 2022 |
| HP            | ENVY m7                     | [9142b4fff0](https://linux-hardware.org/?probe=9142b4fff0) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| Lenovo        | IdeaPad 5-15ARE05 81YQ      | [0a48289c39](https://linux-hardware.org/?probe=0a48289c39) | Aug 16, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [35cd057234](https://linux-hardware.org/?probe=35cd057234) | Aug 16, 2022 |
| Acer          | Celadon-RN                  | [043b0c9fd7](https://linux-hardware.org/?probe=043b0c9fd7) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | [94309eee94](https://linux-hardware.org/?probe=94309eee94) | Aug 15, 2022 |
| HP            | EliteBook 845 14 inch G9... | [4e05ac232c](https://linux-hardware.org/?probe=4e05ac232c) | Aug 15, 2022 |
| Dell          | Vostro 7500                 | [3e084bba8b](https://linux-hardware.org/?probe=3e084bba8b) | Aug 15, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [1db8ed0da4](https://linux-hardware.org/?probe=1db8ed0da4) | Aug 14, 2022 |
| HP            | ENVY Laptop 13-aq0xxx       | [105367d5d6](https://linux-hardware.org/?probe=105367d5d6) | Aug 14, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [7817924a07](https://linux-hardware.org/?probe=7817924a07) | Aug 14, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97f75c2be0](https://linux-hardware.org/?probe=97f75c2be0) | Aug 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1C00... | [dbbae31450](https://linux-hardware.org/?probe=dbbae31450) | Aug 13, 2022 |
| HP            | 250 G6 Notebook PC          | [ee2f627cb6](https://linux-hardware.org/?probe=ee2f627cb6) | Aug 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c131aca1](https://linux-hardware.org/?probe=26c131aca1) | Aug 13, 2022 |
| ASUSTek       | GL552VX                     | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [0045f412a9](https://linux-hardware.org/?probe=0045f412a9) | Aug 12, 2022 |
| Dell          | XPS 13 9360                 | [a78c885366](https://linux-hardware.org/?probe=a78c885366) | Aug 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [e3be6b79c1](https://linux-hardware.org/?probe=e3be6b79c1) | Aug 12, 2022 |
| Acer          | Predator PH315-52           | [fad6aace6a](https://linux-hardware.org/?probe=fad6aace6a) | Aug 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [69843536ef](https://linux-hardware.org/?probe=69843536ef) | Aug 11, 2022 |
| HP            | ProBook 640 G5              | [321cb5faf4](https://linux-hardware.org/?probe=321cb5faf4) | Aug 11, 2022 |
| HP            | ProBook 640 G5              | [b71c89e139](https://linux-hardware.org/?probe=b71c89e139) | Aug 11, 2022 |
| HP            | Pavilion Gaming Notebook    | [673ef8a276](https://linux-hardware.org/?probe=673ef8a276) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [d61320f9c5](https://linux-hardware.org/?probe=d61320f9c5) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [bc7a8afe56](https://linux-hardware.org/?probe=bc7a8afe56) | Aug 11, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [27b3fb870a](https://linux-hardware.org/?probe=27b3fb870a) | Aug 11, 2022 |
| HP            | Laptop 17-cn0xxx            | [94a67b764b](https://linux-hardware.org/?probe=94a67b764b) | Aug 11, 2022 |
| Dell          | XPS 13 9380                 | [534c1142c2](https://linux-hardware.org/?probe=534c1142c2) | Aug 10, 2022 |
| Dell          | XPS 13 9380                 | [0724d34f68](https://linux-hardware.org/?probe=0724d34f68) | Aug 10, 2022 |
| HP            | EliteBook 845 14 inch G9... | [644f2ccaaf](https://linux-hardware.org/?probe=644f2ccaaf) | Aug 10, 2022 |
| Lenovo        | IdeaPad Y410P 20216         | [df3068aea1](https://linux-hardware.org/?probe=df3068aea1) | Aug 10, 2022 |
| MSI           | GP66 Leopard 11UH           | [a85b442a71](https://linux-hardware.org/?probe=a85b442a71) | Aug 09, 2022 |
| HP            | Laptop 14-fq0xxx            | [598febc046](https://linux-hardware.org/?probe=598febc046) | Aug 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [fc8542afef](https://linux-hardware.org/?probe=fc8542afef) | Aug 09, 2022 |
| Alienware     | x15 R1                      | [59b6412e2f](https://linux-hardware.org/?probe=59b6412e2f) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [1636ef38d5](https://linux-hardware.org/?probe=1636ef38d5) | Aug 09, 2022 |
| HP            | EliteBook 840 G5            | [16b59e0aae](https://linux-hardware.org/?probe=16b59e0aae) | Aug 08, 2022 |
| HP            | ZBook 15 G6                 | [f833eca9da](https://linux-hardware.org/?probe=f833eca9da) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330s-15ARR 81FB     | [4546912e7b](https://linux-hardware.org/?probe=4546912e7b) | Aug 08, 2022 |
| Lenovo        | Legion R70002021 82JW       | [949598482f](https://linux-hardware.org/?probe=949598482f) | Aug 07, 2022 |
| HUAWEI        | CREM-WXX9                   | [409cc97b53](https://linux-hardware.org/?probe=409cc97b53) | Aug 07, 2022 |
| HP            | Laptop 15s-gr0xxx           | [457fa11671](https://linux-hardware.org/?probe=457fa11671) | Aug 07, 2022 |
| Lenovo        | ThinkPad E14 20RA004WUS     | [b140ac0aea](https://linux-hardware.org/?probe=b140ac0aea) | Aug 07, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [3f71cac385](https://linux-hardware.org/?probe=3f71cac385) | Aug 06, 2022 |
| Acer          | Predator G3-571             | [e5e720b21b](https://linux-hardware.org/?probe=e5e720b21b) | Aug 06, 2022 |
| MECHREVO      | Code 01 Series PF5NU1G      | [3c42214ad0](https://linux-hardware.org/?probe=3c42214ad0) | Aug 06, 2022 |
| Lenovo        | ThinkPad T61 6457VE6        | [a6a1de13e4](https://linux-hardware.org/?probe=a6a1de13e4) | Aug 05, 2022 |
| HP            | ZBook 15 G6                 | [034cd98301](https://linux-hardware.org/?probe=034cd98301) | Aug 05, 2022 |
| Dell          | Latitude E5440              | [7d828eb093](https://linux-hardware.org/?probe=7d828eb093) | Aug 05, 2022 |
| Lenovo        | Legion R70002021 82JW       | [7a3c7a2886](https://linux-hardware.org/?probe=7a3c7a2886) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [900f1d3f01](https://linux-hardware.org/?probe=900f1d3f01) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [4c75e1d374](https://linux-hardware.org/?probe=4c75e1d374) | Aug 03, 2022 |
| ASUSTek       | G550JK                      | [76414b53ee](https://linux-hardware.org/?probe=76414b53ee) | Aug 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [66c117c18e](https://linux-hardware.org/?probe=66c117c18e) | Aug 03, 2022 |
| HP            | EliteBook 840 G5            | [62a6f6b85a](https://linux-hardware.org/?probe=62a6f6b85a) | Aug 02, 2022 |
| HP            | EliteBook 840 G5            | [f93096f2ff](https://linux-hardware.org/?probe=f93096f2ff) | Aug 02, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | [9beb1b8221](https://linux-hardware.org/?probe=9beb1b8221) | Aug 02, 2022 |
| Lenovo        | ThinkPad Edge E431 62771... | [563bd9cecd](https://linux-hardware.org/?probe=563bd9cecd) | Aug 02, 2022 |
| TUXEDO        | Pulse 15 Gen2               | [e650b177cc](https://linux-hardware.org/?probe=e650b177cc) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | [a008ad925d](https://linux-hardware.org/?probe=a008ad925d) | Aug 01, 2022 |
| Acidanther... | MacBookPro13,1              | [5c8158f059](https://linux-hardware.org/?probe=5c8158f059) | Aug 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [d77ac14ae9](https://linux-hardware.org/?probe=d77ac14ae9) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [65d5b19d40](https://linux-hardware.org/?probe=65d5b19d40) | Aug 01, 2022 |
| Lenovo        | ThinkPad T420 4180LN1       | [35304c2321](https://linux-hardware.org/?probe=35304c2321) | Aug 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [b2385a694b](https://linux-hardware.org/?probe=b2385a694b) | Jul 31, 2022 |
| Toshiba       | dynabook Satellite B35/R    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [d3b270c068](https://linux-hardware.org/?probe=d3b270c068) | Jul 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [97f6892c6c](https://linux-hardware.org/?probe=97f6892c6c) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | [3b08b42260](https://linux-hardware.org/?probe=3b08b42260) | Jul 30, 2022 |
| Dell          | Inspiron N4010              | [7589775fb4](https://linux-hardware.org/?probe=7589775fb4) | Jul 30, 2022 |
| Lenovo        | ThinkPad E480 20KN001QRT    | [e0e0792a71](https://linux-hardware.org/?probe=e0e0792a71) | Jul 30, 2022 |
| Clevo         | W150HNM/W170HN              | [31c83153b5](https://linux-hardware.org/?probe=31c83153b5) | Jul 29, 2022 |
| MSI           | GF75 Thin 9SC               | [a6113f2e35](https://linux-hardware.org/?probe=a6113f2e35) | Jul 29, 2022 |
| Toshiba       | Satellite L70-B             | [bee2cdca79](https://linux-hardware.org/?probe=bee2cdca79) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ef7aa9cb2e](https://linux-hardware.org/?probe=ef7aa9cb2e) | Jul 29, 2022 |
| Dell          | Latitude 5480               | [2e2d540cb0](https://linux-hardware.org/?probe=2e2d540cb0) | Jul 29, 2022 |
| Framework     | Laptop                      | [626e3266c7](https://linux-hardware.org/?probe=626e3266c7) | Jul 29, 2022 |
| HP            | ZBook 15v G5                | [b08d670a98](https://linux-hardware.org/?probe=b08d670a98) | Jul 28, 2022 |
| HP            | 255 G7 Notebook PC          | [bc1a82a647](https://linux-hardware.org/?probe=bc1a82a647) | Jul 28, 2022 |
| Dell          | XPS 15 9500                 | [e5d7cc54e7](https://linux-hardware.org/?probe=e5d7cc54e7) | Jul 28, 2022 |
| Timi          | TM1703                      | [b3c578658f](https://linux-hardware.org/?probe=b3c578658f) | Jul 28, 2022 |
| Acer          | Aspire A715-42G             | [8d87e3bb3b](https://linux-hardware.org/?probe=8d87e3bb3b) | Jul 28, 2022 |
| Lenovo        | ThinkPad X230 2325TXV       | [2c5c6ba837](https://linux-hardware.org/?probe=2c5c6ba837) | Jul 28, 2022 |
| Apple         | MacBookAir7,2               | [b547e23eb1](https://linux-hardware.org/?probe=b547e23eb1) | Jul 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [7d9d58c2da](https://linux-hardware.org/?probe=7d9d58c2da) | Jul 27, 2022 |
| Dell          | G5 5590                     | [ae478a8f82](https://linux-hardware.org/?probe=ae478a8f82) | Jul 27, 2022 |
| Samsung       | 935XDB                      | [d6149a337b](https://linux-hardware.org/?probe=d6149a337b) | Jul 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [75c2236b06](https://linux-hardware.org/?probe=75c2236b06) | Jul 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [6577d30f3e](https://linux-hardware.org/?probe=6577d30f3e) | Jul 26, 2022 |
| Alienware     | m15 R4                      | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| Dell          | Precision 7560              | [2fdcece648](https://linux-hardware.org/?probe=2fdcece648) | Jul 25, 2022 |
| Dell          | Precision 7560              | [02fb353f1e](https://linux-hardware.org/?probe=02fb353f1e) | Jul 25, 2022 |
| Dell          | Vostro 3491                 | [6ce65dccb7](https://linux-hardware.org/?probe=6ce65dccb7) | Jul 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ce2ecc0fd8](https://linux-hardware.org/?probe=ce2ecc0fd8) | Jul 24, 2022 |
| Timi          | RedmiBook 14 II             | [cd8d5a1ee6](https://linux-hardware.org/?probe=cd8d5a1ee6) | Jul 24, 2022 |
| Lenovo        | ThinkPad X280 20KES2SN00    | [202423ba73](https://linux-hardware.org/?probe=202423ba73) | Jul 24, 2022 |
| Google        | Wolf                        | [f2397aadef](https://linux-hardware.org/?probe=f2397aadef) | Jul 23, 2022 |
| Google        | Wolf                        | [ffa74c4dc0](https://linux-hardware.org/?probe=ffa74c4dc0) | Jul 23, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [492b4e1236](https://linux-hardware.org/?probe=492b4e1236) | Jul 23, 2022 |
| ASUSTek       | X555LD                      | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | [51d002e1b7](https://linux-hardware.org/?probe=51d002e1b7) | Jul 23, 2022 |
| Apple         | MacBookAir7,1               | [41d0e95039](https://linux-hardware.org/?probe=41d0e95039) | Jul 23, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [3428364c49](https://linux-hardware.org/?probe=3428364c49) | Jul 22, 2022 |
| Acer          | Nitro AN515-55              | [85f2ffe45a](https://linux-hardware.org/?probe=85f2ffe45a) | Jul 22, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [b8ce5a0377](https://linux-hardware.org/?probe=b8ce5a0377) | Jul 22, 2022 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [02dd3c2357](https://linux-hardware.org/?probe=02dd3c2357) | Jul 21, 2022 |
| Samsung       | 935XDB                      | [e01b518899](https://linux-hardware.org/?probe=e01b518899) | Jul 21, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [8505a7d575](https://linux-hardware.org/?probe=8505a7d575) | Jul 21, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | [d101f95ac2](https://linux-hardware.org/?probe=d101f95ac2) | Jul 20, 2022 |
| Lenovo        | V570 HuronRiver Platform    | [7e317412e0](https://linux-hardware.org/?probe=7e317412e0) | Jul 20, 2022 |
| HP            | ProBook 640 G5              | [36a725c595](https://linux-hardware.org/?probe=36a725c595) | Jul 19, 2022 |
| MSI           | Stealth GS77 12UGS          | [8d6d581aac](https://linux-hardware.org/?probe=8d6d581aac) | Jul 19, 2022 |
| Acer          | Aspire A515-45              | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| HP            | ZHAN 99 Mobile Workstati... | [cafc6119f3](https://linux-hardware.org/?probe=cafc6119f3) | Jul 18, 2022 |
| MSI           | GS75 Stealth 9SF            | [24e8aca8d1](https://linux-hardware.org/?probe=24e8aca8d1) | Jul 17, 2022 |
| System76      | Lemur Pro                   | [a4adde6cf9](https://linux-hardware.org/?probe=a4adde6cf9) | Jul 17, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [321c1a6e7a](https://linux-hardware.org/?probe=321c1a6e7a) | Jul 17, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [ebcca43b7f](https://linux-hardware.org/?probe=ebcca43b7f) | Jul 17, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | [e94cde9ec6](https://linux-hardware.org/?probe=e94cde9ec6) | Jul 17, 2022 |
| Dell          | Latitude E6540              | [595eeced49](https://linux-hardware.org/?probe=595eeced49) | Jul 16, 2022 |
| Dell          | Latitude E6540              | [804dad339b](https://linux-hardware.org/?probe=804dad339b) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a6e936c29d](https://linux-hardware.org/?probe=a6e936c29d) | Jul 16, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d465259da1](https://linux-hardware.org/?probe=d465259da1) | Jul 16, 2022 |
| HP            | ProBook 640 G5              | [93e838afb1](https://linux-hardware.org/?probe=93e838afb1) | Jul 16, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [1dc42453a1](https://linux-hardware.org/?probe=1dc42453a1) | Jul 15, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [164d1ff988](https://linux-hardware.org/?probe=164d1ff988) | Jul 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e4530dd7b4](https://linux-hardware.org/?probe=e4530dd7b4) | Jul 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [c475c84f19](https://linux-hardware.org/?probe=c475c84f19) | Jul 15, 2022 |
| HP            | EliteBook 8570w             | [c21885de7f](https://linux-hardware.org/?probe=c21885de7f) | Jul 15, 2022 |
| MSI           | Stealth GS77 12UGS          | [b5f57e7b95](https://linux-hardware.org/?probe=b5f57e7b95) | Jul 14, 2022 |
| Hyperbook     | Z15 Zen                     | [41129ecc5e](https://linux-hardware.org/?probe=41129ecc5e) | Jul 14, 2022 |
| Dell          | Inspiron 7570               | [872ca81b40](https://linux-hardware.org/?probe=872ca81b40) | Jul 13, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [896226e566](https://linux-hardware.org/?probe=896226e566) | Jul 13, 2022 |
| Lenovo        | ThinkPad T430 2349CV8       | [fac90d81d0](https://linux-hardware.org/?probe=fac90d81d0) | Jul 13, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | [6021e75347](https://linux-hardware.org/?probe=6021e75347) | Jul 13, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [eb05f4aed9](https://linux-hardware.org/?probe=eb05f4aed9) | Jul 13, 2022 |
| Toshiba       | Satellite M645              | [0149367a4e](https://linux-hardware.org/?probe=0149367a4e) | Jul 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [eac5600627](https://linux-hardware.org/?probe=eac5600627) | Jul 12, 2022 |
| Notebook      | NL5xRU                      | [a4bc7e790c](https://linux-hardware.org/?probe=a4bc7e790c) | Jul 11, 2022 |
| HP            | ProBook 440 G6              | [6a065093ba](https://linux-hardware.org/?probe=6a065093ba) | Jul 10, 2022 |
| Acer          | Nitro AN515-44              | [1478a70c4b](https://linux-hardware.org/?probe=1478a70c4b) | Jul 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [de4d640168](https://linux-hardware.org/?probe=de4d640168) | Jul 10, 2022 |
| Acer          | Nitro AN515-45              | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | U36SG                       | [878e0283d9](https://linux-hardware.org/?probe=878e0283d9) | Jul 08, 2022 |
| ASUSTek       | GL702VSK                    | [4fe32d25e5](https://linux-hardware.org/?probe=4fe32d25e5) | Jul 08, 2022 |
| Apple         | MacBookPro12,1              | [62fb099dfd](https://linux-hardware.org/?probe=62fb099dfd) | Jul 07, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [92b59598e5](https://linux-hardware.org/?probe=92b59598e5) | Jul 06, 2022 |
| MSI           | GP66 Leopard 10UH           | [dcbe6f403d](https://linux-hardware.org/?probe=dcbe6f403d) | Jul 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [9ad51a3a2c](https://linux-hardware.org/?probe=9ad51a3a2c) | Jul 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [341858c479](https://linux-hardware.org/?probe=341858c479) | Jul 05, 2022 |
| MSI           | GP66 Leopard 11UG           | [bc37067029](https://linux-hardware.org/?probe=bc37067029) | Jul 05, 2022 |
| Acer          | Aspire E5-522               | [9693c1d4ff](https://linux-hardware.org/?probe=9693c1d4ff) | Jul 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [4829f98af6](https://linux-hardware.org/?probe=4829f98af6) | Jul 04, 2022 |
| HP            | 250 G6 Notebook PC          | [fed0993c92](https://linux-hardware.org/?probe=fed0993c92) | Jul 03, 2022 |
| Dell          | Vostro 2420                 | [ce9585eac5](https://linux-hardware.org/?probe=ce9585eac5) | Jul 03, 2022 |
| Intel         | HuronRiver Platform         | [c0d79569d8](https://linux-hardware.org/?probe=c0d79569d8) | Jul 03, 2022 |
| Acer          | Aspire VX5-591G             | [5393a13046](https://linux-hardware.org/?probe=5393a13046) | Jul 02, 2022 |
| Infinix       | INBOOK X2                   | [eedac976d8](https://linux-hardware.org/?probe=eedac976d8) | Jul 02, 2022 |
| Acer          | Swift SF314-42              | [bd4792ebd8](https://linux-hardware.org/?probe=bd4792ebd8) | Jul 02, 2022 |
| Apple         | MacBookPro14,1              | [aad648ac8d](https://linux-hardware.org/?probe=aad648ac8d) | Jul 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [5950f35d56](https://linux-hardware.org/?probe=5950f35d56) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [6904140540](https://linux-hardware.org/?probe=6904140540) | Jul 02, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [7e809da3ad](https://linux-hardware.org/?probe=7e809da3ad) | Jul 01, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [27cd378ed6](https://linux-hardware.org/?probe=27cd378ed6) | Jul 01, 2022 |
| HP            | Pavilion g4                 | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| Dell          | XPS M1330                   | [b891e49fac](https://linux-hardware.org/?probe=b891e49fac) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [96b07cbbd5](https://linux-hardware.org/?probe=96b07cbbd5) | Jun 30, 2022 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [abebd5c659](https://linux-hardware.org/?probe=abebd5c659) | Jun 30, 2022 |
| Dell          | Vostro 5625                 | [0a047126ba](https://linux-hardware.org/?probe=0a047126ba) | Jun 30, 2022 |
| HUAWEI        | HVY-WXX9                    | [e7f3ea5cf5](https://linux-hardware.org/?probe=e7f3ea5cf5) | Jun 30, 2022 |
| Infinix       | INBOOK X2                   | [1c87102f96](https://linux-hardware.org/?probe=1c87102f96) | Jun 29, 2022 |
| Lenovo        | ThinkPad P50 20EQS5M100     | [d0b6aa0a1a](https://linux-hardware.org/?probe=d0b6aa0a1a) | Jun 29, 2022 |
| Dell          | XPS 13 9310                 | [6a2b56796c](https://linux-hardware.org/?probe=6a2b56796c) | Jun 28, 2022 |
| Acer          | Aspire M5-582PT             | [e159de9f3e](https://linux-hardware.org/?probe=e159de9f3e) | Jun 28, 2022 |
| HP            | EliteBook 840 G2            | [79a978476b](https://linux-hardware.org/?probe=79a978476b) | Jun 28, 2022 |
| Dell          | Latitude 7350               | [427cc37d76](https://linux-hardware.org/?probe=427cc37d76) | Jun 28, 2022 |
| Dell          | Latitude 7350               | [65d1c5c6f5](https://linux-hardware.org/?probe=65d1c5c6f5) | Jun 28, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [20054c6da2](https://linux-hardware.org/?probe=20054c6da2) | Jun 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS6XC00    | [a4b9098138](https://linux-hardware.org/?probe=a4b9098138) | Jun 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0beecf61e4](https://linux-hardware.org/?probe=0beecf61e4) | Jun 26, 2022 |
| Dell          | Inspiron 3442               | [72286bac00](https://linux-hardware.org/?probe=72286bac00) | Jun 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [68e2e0bbdb](https://linux-hardware.org/?probe=68e2e0bbdb) | Jun 25, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [27343a622f](https://linux-hardware.org/?probe=27343a622f) | Jun 25, 2022 |
| Dell          | Latitude 5420               | [2149a24612](https://linux-hardware.org/?probe=2149a24612) | Jun 25, 2022 |
| Dell          | Latitude 5490               | [4c3d48724c](https://linux-hardware.org/?probe=4c3d48724c) | Jun 25, 2022 |
| Dell          | Latitude 5490               | [3bb8a81dbf](https://linux-hardware.org/?probe=3bb8a81dbf) | Jun 25, 2022 |
| ASUSTek       | G551JM                      | [2d8e7ffcb2](https://linux-hardware.org/?probe=2d8e7ffcb2) | Jun 24, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [5bd3ad4d01](https://linux-hardware.org/?probe=5bd3ad4d01) | Jun 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [fac01563a9](https://linux-hardware.org/?probe=fac01563a9) | Jun 24, 2022 |
| Acer          | Nitro AN715-51              | [a8df58056b](https://linux-hardware.org/?probe=a8df58056b) | Jun 24, 2022 |
| Lenovo        | ThinkPad T580 20LAS6XC00    | [55e631d9b6](https://linux-hardware.org/?probe=55e631d9b6) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1780abcf08](https://linux-hardware.org/?probe=1780abcf08) | Jun 24, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [e0da282c48](https://linux-hardware.org/?probe=e0da282c48) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [a1a0b3b43b](https://linux-hardware.org/?probe=a1a0b3b43b) | Jun 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f2b61e1e02](https://linux-hardware.org/?probe=f2b61e1e02) | Jun 23, 2022 |
| Acer          | Aspire E1-570               | [906b1f465e](https://linux-hardware.org/?probe=906b1f465e) | Jun 23, 2022 |
| Razer         | Blade                       | [6c8b201cd9](https://linux-hardware.org/?probe=6c8b201cd9) | Jun 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [51ec938467](https://linux-hardware.org/?probe=51ec938467) | Jun 22, 2022 |
| LG Electro... | 15Z95N-G.AAC6U1             | [c5b4596c19](https://linux-hardware.org/?probe=c5b4596c19) | Jun 22, 2022 |
| Acer          | Nitro AN515-55              | [bc159b637c](https://linux-hardware.org/?probe=bc159b637c) | Jun 22, 2022 |
| Dell          | Vostro 2420                 | [84a4eb23c6](https://linux-hardware.org/?probe=84a4eb23c6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a8d78740e8](https://linux-hardware.org/?probe=a8d78740e8) | Jun 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [4539c26ede](https://linux-hardware.org/?probe=4539c26ede) | Jun 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | [cf80e45435](https://linux-hardware.org/?probe=cf80e45435) | Jun 21, 2022 |
| Apple         | MacBookPro16,1              | [35f551b127](https://linux-hardware.org/?probe=35f551b127) | Jun 21, 2022 |
| HP            | EliteBook 8570w             | [2530e2e400](https://linux-hardware.org/?probe=2530e2e400) | Jun 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [9a9dd8fa0c](https://linux-hardware.org/?probe=9a9dd8fa0c) | Jun 21, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [ff5ed1835c](https://linux-hardware.org/?probe=ff5ed1835c) | Jun 20, 2022 |
| Philco        | OEM                         | [bee7961704](https://linux-hardware.org/?probe=bee7961704) | Jun 20, 2022 |
| HONOR         | HYM-WXX                     | [9eb7129a46](https://linux-hardware.org/?probe=9eb7129a46) | Jun 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| HP            | ENVY dv7                    | [22dec86487](https://linux-hardware.org/?probe=22dec86487) | Jun 20, 2022 |
| ASUSTek       | GL502VMK                    | [d872e88532](https://linux-hardware.org/?probe=d872e88532) | Jun 20, 2022 |
| ASUSTek       | X550JX                      | [999d6e4735](https://linux-hardware.org/?probe=999d6e4735) | Jun 20, 2022 |
| Framework     | Laptop                      | [f5ece7ce85](https://linux-hardware.org/?probe=f5ece7ce85) | Jun 19, 2022 |
| Toshiba       | Satellite Click 10 LX5W-... | [b8f87c8ede](https://linux-hardware.org/?probe=b8f87c8ede) | Jun 19, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcbbdaf844](https://linux-hardware.org/?probe=fcbbdaf844) | Jun 18, 2022 |
| HUAWEI        | KPR-WX9                     | [4c08060155](https://linux-hardware.org/?probe=4c08060155) | Jun 18, 2022 |
| HP            | EliteBook 8460p             | [e19c095325](https://linux-hardware.org/?probe=e19c095325) | Jun 18, 2022 |
| Acer          | Nitro AN515-44              | [9ed8b5c759](https://linux-hardware.org/?probe=9ed8b5c759) | Jun 17, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [2e98922741](https://linux-hardware.org/?probe=2e98922741) | Jun 17, 2022 |
| Dell          | Latitude E5450              | [42f5a53e24](https://linux-hardware.org/?probe=42f5a53e24) | Jun 16, 2022 |
| HP            | Laptop 15-dw2xxx            | [7eee6145a1](https://linux-hardware.org/?probe=7eee6145a1) | Jun 16, 2022 |
| ASUSTek       | X411UA                      | [da7deca26c](https://linux-hardware.org/?probe=da7deca26c) | Jun 16, 2022 |
| ASUSTek       | T100HAN                     | [20105d0e64](https://linux-hardware.org/?probe=20105d0e64) | Jun 16, 2022 |
| Acer          | Swift SF314-511             | [c414ab98c5](https://linux-hardware.org/?probe=c414ab98c5) | Jun 16, 2022 |
| MSI           | GP66 Leopard 11UG           | [ffcca1ccac](https://linux-hardware.org/?probe=ffcca1ccac) | Jun 16, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [27d9d9e55e](https://linux-hardware.org/?probe=27d9d9e55e) | Jun 16, 2022 |
| Lenovo        | ThinkPad P50 20EQS31G00     | [51042aca4a](https://linux-hardware.org/?probe=51042aca4a) | Jun 15, 2022 |
| Acer          | Nitro AN515-55              | [bb631825e3](https://linux-hardware.org/?probe=bb631825e3) | Jun 15, 2022 |
| Lenovo        | ThinkPad E490 20N8002APB    | [3a17ac0192](https://linux-hardware.org/?probe=3a17ac0192) | Jun 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| GPU Compan... | GWTN141-10                  | [c856f6d54f](https://linux-hardware.org/?probe=c856f6d54f) | Jun 14, 2022 |
| Timi          | TM1701                      | [e57d1ac956](https://linux-hardware.org/?probe=e57d1ac956) | Jun 14, 2022 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [ee0b4c4389](https://linux-hardware.org/?probe=ee0b4c4389) | Jun 14, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [c87c87881e](https://linux-hardware.org/?probe=c87c87881e) | Jun 14, 2022 |
| Google        | Quawks                      | [c513bb8294](https://linux-hardware.org/?probe=c513bb8294) | Jun 14, 2022 |
| ASUSTek       | U36SG                       | [d5c67322d4](https://linux-hardware.org/?probe=d5c67322d4) | Jun 14, 2022 |
| HONOR         | HYM-WXX                     | [0f745d7bc7](https://linux-hardware.org/?probe=0f745d7bc7) | Jun 13, 2022 |
| HP            | Laptop 15-dw2xxx            | [cdc0b49b72](https://linux-hardware.org/?probe=cdc0b49b72) | Jun 13, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e33ea31f97](https://linux-hardware.org/?probe=e33ea31f97) | Jun 13, 2022 |
| HP            | Laptop 15q-bu0xx            | [859d1ddbb0](https://linux-hardware.org/?probe=859d1ddbb0) | Jun 13, 2022 |
| Samsung       | 670Z5E                      | [049e305b33](https://linux-hardware.org/?probe=049e305b33) | Jun 13, 2022 |
| Dell          | Inspiron 1545               | [ac1f1fe24f](https://linux-hardware.org/?probe=ac1f1fe24f) | Jun 12, 2022 |
| ASUSTek       | T100HAN                     | [9a5b9400a1](https://linux-hardware.org/?probe=9a5b9400a1) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | [52efea465c](https://linux-hardware.org/?probe=52efea465c) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | [731e6f4aa8](https://linux-hardware.org/?probe=731e6f4aa8) | Jun 12, 2022 |
| Dell          | Precision 7520              | [002f7ce017](https://linux-hardware.org/?probe=002f7ce017) | Jun 12, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e414ea3e15](https://linux-hardware.org/?probe=e414ea3e15) | Jun 11, 2022 |
| Alienware     | m15 R4                      | [5299db8f70](https://linux-hardware.org/?probe=5299db8f70) | Jun 11, 2022 |
| ASUSTek       | X555LD                      | [d5d6eeb639](https://linux-hardware.org/?probe=d5d6eeb639) | Jun 11, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [c8f8c1a8e3](https://linux-hardware.org/?probe=c8f8c1a8e3) | Jun 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [91580d9a20](https://linux-hardware.org/?probe=91580d9a20) | Jun 10, 2022 |
| Fujitsu       | LIFEBOOK E556               | [1dd2b6a645](https://linux-hardware.org/?probe=1dd2b6a645) | Jun 10, 2022 |
| Lenovo        | ThinkPad X230 2325TXV       | [67f152d520](https://linux-hardware.org/?probe=67f152d520) | Jun 10, 2022 |
| ASUSTek       | ROG Strix G513QR_G513QR     | [e33e73a70f](https://linux-hardware.org/?probe=e33e73a70f) | Jun 10, 2022 |
| Lenovo        | ThinkPad X220 4291IR6       | [958f8bb25b](https://linux-hardware.org/?probe=958f8bb25b) | Jun 09, 2022 |
| Lenovo        | Unknown                     | [2921bcaa1c](https://linux-hardware.org/?probe=2921bcaa1c) | Jun 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [dcfb1c33aa](https://linux-hardware.org/?probe=dcfb1c33aa) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [737a4183c8](https://linux-hardware.org/?probe=737a4183c8) | Jun 07, 2022 |
| Avell High... | A62 LIV                     | [5a7be822e3](https://linux-hardware.org/?probe=5a7be822e3) | Jun 07, 2022 |
| Dell          | Precision 5550              | [a4bf41771c](https://linux-hardware.org/?probe=a4bf41771c) | Jun 07, 2022 |
| Lenovo        | ThinkPad T495 20NJ0007US    | [2b3ee11cad](https://linux-hardware.org/?probe=2b3ee11cad) | Jun 07, 2022 |
| HP            | EliteBook 840 G5            | [73ba6fe3c0](https://linux-hardware.org/?probe=73ba6fe3c0) | Jun 06, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [228fe8f3f1](https://linux-hardware.org/?probe=228fe8f3f1) | Jun 06, 2022 |
| Dell          | Latitude 5511               | [5d9a12a88d](https://linux-hardware.org/?probe=5d9a12a88d) | Jun 06, 2022 |
| Acer          | Nitro AN515-55              | [4ab9f94abe](https://linux-hardware.org/?probe=4ab9f94abe) | Jun 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [6d46a6107c](https://linux-hardware.org/?probe=6d46a6107c) | Jun 06, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [f4dcc8e7a1](https://linux-hardware.org/?probe=f4dcc8e7a1) | Jun 06, 2022 |
| Samsung       | 550XBE/350XBE               | [4746fe546b](https://linux-hardware.org/?probe=4746fe546b) | Jun 05, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [f9bd82bcd7](https://linux-hardware.org/?probe=f9bd82bcd7) | Jun 05, 2022 |
| Dell          | G3 3500                     | [6734206fa0](https://linux-hardware.org/?probe=6734206fa0) | Jun 05, 2022 |
| Fujitsu       | LIFEBOOK U937               | [44d3d1edad](https://linux-hardware.org/?probe=44d3d1edad) | Jun 04, 2022 |
| TUXEDO        | Book_XA1510                 | [6738253853](https://linux-hardware.org/?probe=6738253853) | Jun 04, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [66cc7342ec](https://linux-hardware.org/?probe=66cc7342ec) | Jun 04, 2022 |
| Acer          | Swift SF314-511             | [883f386564](https://linux-hardware.org/?probe=883f386564) | Jun 03, 2022 |
| Acer          | Swift SF314-511             | [ecd590c347](https://linux-hardware.org/?probe=ecd590c347) | Jun 03, 2022 |
| HP            | Pavilion Notebook           | [0fe589689b](https://linux-hardware.org/?probe=0fe589689b) | Jun 02, 2022 |
| Dell          | Latitude 9420               | [28ba6de10d](https://linux-hardware.org/?probe=28ba6de10d) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | [fd7f5dd506](https://linux-hardware.org/?probe=fd7f5dd506) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [84efabac8f](https://linux-hardware.org/?probe=84efabac8f) | Jun 01, 2022 |
| MSI           | Bravo 15 B5DD               | [4ae400000f](https://linux-hardware.org/?probe=4ae400000f) | Jun 01, 2022 |
| MSI           | Bravo 15 B5DD               | [d561d8dbdb](https://linux-hardware.org/?probe=d561d8dbdb) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [460e11ebe2](https://linux-hardware.org/?probe=460e11ebe2) | May 31, 2022 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [3195728920](https://linux-hardware.org/?probe=3195728920) | May 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [799a25df83](https://linux-hardware.org/?probe=799a25df83) | May 31, 2022 |
| Dell          | Latitude 5511               | [ef262c4020](https://linux-hardware.org/?probe=ef262c4020) | May 31, 2022 |
| Dell          | Inspiron 5567               | [2f14b6956f](https://linux-hardware.org/?probe=2f14b6956f) | May 31, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [49c400d1f7](https://linux-hardware.org/?probe=49c400d1f7) | May 31, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [deaac8464e](https://linux-hardware.org/?probe=deaac8464e) | May 31, 2022 |
| HP            | EliteBook 8470p             | [6b22d31e8e](https://linux-hardware.org/?probe=6b22d31e8e) | May 31, 2022 |
| Lenovo        | ThinkPad T460p 20FW0005A... | [df0f623625](https://linux-hardware.org/?probe=df0f623625) | May 30, 2022 |
| Dell          | Latitude 5511               | [33b796acff](https://linux-hardware.org/?probe=33b796acff) | May 30, 2022 |
| ASUSTek       | X555UQ                      | [c266f3d070](https://linux-hardware.org/?probe=c266f3d070) | May 30, 2022 |
| Dell          | Inspiron 15-3567            | [3299abfc78](https://linux-hardware.org/?probe=3299abfc78) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c71a8e9817](https://linux-hardware.org/?probe=c71a8e9817) | May 29, 2022 |
| Timi          | TM1604                      | [cd9b839800](https://linux-hardware.org/?probe=cd9b839800) | May 29, 2022 |
| Lenovo        | Legion Y7000P2020H 82AX     | [220325c031](https://linux-hardware.org/?probe=220325c031) | May 29, 2022 |
| HP            | Laptop 15-dy2xxx            | [1c71dac18b](https://linux-hardware.org/?probe=1c71dac18b) | May 29, 2022 |
| ASUSTek       | GL502VSK                    | [44fb5da9d6](https://linux-hardware.org/?probe=44fb5da9d6) | May 29, 2022 |
| eMachines     | eM350                       | [2573854a09](https://linux-hardware.org/?probe=2573854a09) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | [1029a819d7](https://linux-hardware.org/?probe=1029a819d7) | May 29, 2022 |
| SLIMBOOK      | TITAN                       | [c4e27f4d19](https://linux-hardware.org/?probe=c4e27f4d19) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [09aa4c998d](https://linux-hardware.org/?probe=09aa4c998d) | May 28, 2022 |
| ASUSTek       | G750JX                      | [dfb08cef0b](https://linux-hardware.org/?probe=dfb08cef0b) | May 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [b8c8e8baef](https://linux-hardware.org/?probe=b8c8e8baef) | May 27, 2022 |
| System76      | Lemur Pro                   | [dcfd3abdd6](https://linux-hardware.org/?probe=dcfd3abdd6) | May 26, 2022 |
| Lenovo        | IdeaPad Z580                | [4b1c87e746](https://linux-hardware.org/?probe=4b1c87e746) | May 26, 2022 |
| Dell          | G15 5515                    | [4f47780467](https://linux-hardware.org/?probe=4f47780467) | May 26, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1eecb7a012](https://linux-hardware.org/?probe=1eecb7a012) | May 26, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [2eb4f98b37](https://linux-hardware.org/?probe=2eb4f98b37) | May 26, 2022 |
| Acer          | Aspire A515-46              | [e004aa3fd2](https://linux-hardware.org/?probe=e004aa3fd2) | May 25, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [4b23940919](https://linux-hardware.org/?probe=4b23940919) | May 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c8051b3bfc](https://linux-hardware.org/?probe=c8051b3bfc) | May 24, 2022 |
| HP            | Pavilion 15                 | [4140810d35](https://linux-hardware.org/?probe=4140810d35) | May 24, 2022 |
| System76      | Oryx Pro                    | [f95bed2419](https://linux-hardware.org/?probe=f95bed2419) | May 24, 2022 |
| System76      | Oryx Pro                    | [10502c5379](https://linux-hardware.org/?probe=10502c5379) | May 24, 2022 |
| Dell          | Inspiron N4010              | [872649a8b4](https://linux-hardware.org/?probe=872649a8b4) | May 23, 2022 |
| Acer          | Nitro AN515-45              | [293712cc51](https://linux-hardware.org/?probe=293712cc51) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5c74b9f6e4](https://linux-hardware.org/?probe=5c74b9f6e4) | May 23, 2022 |
| HP            | Pavilion 15                 | [ca77af8ab9](https://linux-hardware.org/?probe=ca77af8ab9) | May 23, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5ab3662d65](https://linux-hardware.org/?probe=5ab3662d65) | May 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [fe1d187774](https://linux-hardware.org/?probe=fe1d187774) | May 22, 2022 |
| Dell          | Inspiron 3558               | [47b2310054](https://linux-hardware.org/?probe=47b2310054) | May 22, 2022 |
| Google        | Quawks                      | [cb763161cf](https://linux-hardware.org/?probe=cb763161cf) | May 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [f2c0dedc02](https://linux-hardware.org/?probe=f2c0dedc02) | May 20, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [99283be07b](https://linux-hardware.org/?probe=99283be07b) | May 20, 2022 |
| Dell          | XPS 15 9510                 | [ee62ecda2e](https://linux-hardware.org/?probe=ee62ecda2e) | May 19, 2022 |
| Apple         | MacBookPro8,1               | [e9a6f0bd85](https://linux-hardware.org/?probe=e9a6f0bd85) | May 19, 2022 |
| Google        | Caroline                    | [2b665e84d3](https://linux-hardware.org/?probe=2b665e84d3) | May 19, 2022 |
| Samsung       | 730QCJ/730QCR               | [08452b3686](https://linux-hardware.org/?probe=08452b3686) | May 19, 2022 |
| Lenovo        | IdeaPad U430p 20269         | [bcf848458f](https://linux-hardware.org/?probe=bcf848458f) | May 18, 2022 |
| HP            | ProBook 445 G7 Notebook ... | [e85e2e6559](https://linux-hardware.org/?probe=e85e2e6559) | May 18, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [2ee4916960](https://linux-hardware.org/?probe=2ee4916960) | May 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [153dab147a](https://linux-hardware.org/?probe=153dab147a) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [843a31b222](https://linux-hardware.org/?probe=843a31b222) | May 17, 2022 |
| Acer          | Aspire A515-56              | [a32b5ba574](https://linux-hardware.org/?probe=a32b5ba574) | May 17, 2022 |
| Acer          | Aspire A515-56              | [27366d5566](https://linux-hardware.org/?probe=27366d5566) | May 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a10241fd00](https://linux-hardware.org/?probe=a10241fd00) | May 17, 2022 |
| Dell          | Vostro 3405                 | [fcec5f1cdd](https://linux-hardware.org/?probe=fcec5f1cdd) | May 17, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [d52e9e2938](https://linux-hardware.org/?probe=d52e9e2938) | May 17, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [21f3f7368f](https://linux-hardware.org/?probe=21f3f7368f) | May 17, 2022 |
| Dell          | Precision 5540              | [02576569ce](https://linux-hardware.org/?probe=02576569ce) | May 16, 2022 |
| Dell          | Inspiron 3458               | [5c4fca4c42](https://linux-hardware.org/?probe=5c4fca4c42) | May 16, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [00acddbf24](https://linux-hardware.org/?probe=00acddbf24) | May 16, 2022 |
| HP            | Pavilion Laptop 13-an0xx... | [b4d7d75ad1](https://linux-hardware.org/?probe=b4d7d75ad1) | May 15, 2022 |
| Dell          | XPS 17 9710                 | [449c90c9dd](https://linux-hardware.org/?probe=449c90c9dd) | May 15, 2022 |
| MSI           | Stealth 15M A11SDK          | [0067badf7c](https://linux-hardware.org/?probe=0067badf7c) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [0793a5608a](https://linux-hardware.org/?probe=0793a5608a) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [84ae0966e6](https://linux-hardware.org/?probe=84ae0966e6) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d8361f7895](https://linux-hardware.org/?probe=d8361f7895) | May 14, 2022 |
| Dell          | Latitude E6400              | [2831bacde3](https://linux-hardware.org/?probe=2831bacde3) | May 13, 2022 |
| ASUSTek       | ROG Strix G513QE_G513QE     | [0a28329f7a](https://linux-hardware.org/?probe=0a28329f7a) | May 12, 2022 |
| MSI           | Alpha 15 B5EEK              | [ea8ce36bef](https://linux-hardware.org/?probe=ea8ce36bef) | May 12, 2022 |
| Dell          | Vostro 3405                 | [3c8e334d43](https://linux-hardware.org/?probe=3c8e334d43) | May 12, 2022 |
| Lenovo        | Unknown                     | [3cced8a4fa](https://linux-hardware.org/?probe=3cced8a4fa) | May 12, 2022 |
| MSI           | Modern 14 B5M               | [b207ce7566](https://linux-hardware.org/?probe=b207ce7566) | May 12, 2022 |
| Dell          | XPS 17 9710                 | [ff27218d11](https://linux-hardware.org/?probe=ff27218d11) | May 12, 2022 |
| Dell          | XPS 15 9510                 | [299f811f98](https://linux-hardware.org/?probe=299f811f98) | May 12, 2022 |
| Lenovo        | ThinkPad X230 23257Y1       | [0c4e13a23d](https://linux-hardware.org/?probe=0c4e13a23d) | May 11, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [0e3079b5a1](https://linux-hardware.org/?probe=0e3079b5a1) | May 11, 2022 |
| MSI           | GF75 Thin 9SC               | [6e8c40ad7c](https://linux-hardware.org/?probe=6e8c40ad7c) | May 10, 2022 |
| Dell          | Inspiron 5567               | [f09183023d](https://linux-hardware.org/?probe=f09183023d) | May 10, 2022 |
| Toshiba       | Satellite C55-A-1N0         | [c64d31da4e](https://linux-hardware.org/?probe=c64d31da4e) | May 10, 2022 |
| Notebook      | P65xHP                      | [b1205b8ca1](https://linux-hardware.org/?probe=b1205b8ca1) | May 10, 2022 |
| Dell          | Latitude E6430              | [a188e200b3](https://linux-hardware.org/?probe=a188e200b3) | May 10, 2022 |
| Acer          | Aspire A315-22              | [b3c9da4989](https://linux-hardware.org/?probe=b3c9da4989) | May 09, 2022 |
| Dell          | Inspiron 13-7378            | [768b19f0ff](https://linux-hardware.org/?probe=768b19f0ff) | May 09, 2022 |
| Dell          | Latitude E6430              | [a6b570e125](https://linux-hardware.org/?probe=a6b570e125) | May 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [b0b389263a](https://linux-hardware.org/?probe=b0b389263a) | May 08, 2022 |
| Dell          | Latitude 3330               | [4f05d8475c](https://linux-hardware.org/?probe=4f05d8475c) | May 08, 2022 |
| Acer          | Aspire R7-371T              | [207110a3d4](https://linux-hardware.org/?probe=207110a3d4) | May 07, 2022 |
| Timi          | TM1604                      | [bc97206a3a](https://linux-hardware.org/?probe=bc97206a3a) | May 07, 2022 |
| HP            | ProBook 4530s               | [76fc5ea6ce](https://linux-hardware.org/?probe=76fc5ea6ce) | May 06, 2022 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [795365ba55](https://linux-hardware.org/?probe=795365ba55) | May 06, 2022 |
| Lenovo        | B590 37613LG                | [b0226c712c](https://linux-hardware.org/?probe=b0226c712c) | May 06, 2022 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [ac270166aa](https://linux-hardware.org/?probe=ac270166aa) | May 06, 2022 |
| Framework     | Laptop                      | [67c58248dd](https://linux-hardware.org/?probe=67c58248dd) | May 06, 2022 |
| Compal        | QAQXX                       | [d3211e6bc6](https://linux-hardware.org/?probe=d3211e6bc6) | May 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fb4cf43d54](https://linux-hardware.org/?probe=fb4cf43d54) | May 05, 2022 |
| Apple         | MacBookAir7,2               | [8a9eed8fe0](https://linux-hardware.org/?probe=8a9eed8fe0) | May 05, 2022 |
| Apple         | MacBookAir7,2               | [0f36c83b15](https://linux-hardware.org/?probe=0f36c83b15) | May 05, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [0bbc6c64c2](https://linux-hardware.org/?probe=0bbc6c64c2) | May 05, 2022 |
| Dell          | Latitude 3340               | [b724073bff](https://linux-hardware.org/?probe=b724073bff) | May 05, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [3c081a7012](https://linux-hardware.org/?probe=3c081a7012) | May 04, 2022 |
| HP            | EliteBook 8470p             | [db81dd7652](https://linux-hardware.org/?probe=db81dd7652) | May 04, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ee3b3dc380](https://linux-hardware.org/?probe=ee3b3dc380) | May 04, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [79491af642](https://linux-hardware.org/?probe=79491af642) | May 03, 2022 |
| Acer          | Aspire A517-51G             | [1dc71986aa](https://linux-hardware.org/?probe=1dc71986aa) | May 03, 2022 |
| Acer          | Aspire A517-51G             | [d0ad1ff2fe](https://linux-hardware.org/?probe=d0ad1ff2fe) | May 03, 2022 |
| Acer          | Nitro AN517-54              | [de2960b350](https://linux-hardware.org/?probe=de2960b350) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [f937431614](https://linux-hardware.org/?probe=f937431614) | May 01, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [59e65b422b](https://linux-hardware.org/?probe=59e65b422b) | May 01, 2022 |
| MSI           | Modern 14 B5M               | [04dee023e6](https://linux-hardware.org/?probe=04dee023e6) | May 01, 2022 |
| Acer          | Aspire E5-571               | [35b5fa2276](https://linux-hardware.org/?probe=35b5fa2276) | Apr 30, 2022 |
| Dell          | Precision 7540              | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Dell          | Precision M6600             | [bb40a22dd3](https://linux-hardware.org/?probe=bb40a22dd3) | Apr 29, 2022 |
| Acer          | Aspire A715-71G             | [ec6c90818c](https://linux-hardware.org/?probe=ec6c90818c) | Apr 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [96fc510369](https://linux-hardware.org/?probe=96fc510369) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| HP            | ZBook 17 G2                 | [81409450dc](https://linux-hardware.org/?probe=81409450dc) | Apr 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ab11d6ac2f](https://linux-hardware.org/?probe=ab11d6ac2f) | Apr 28, 2022 |
| Acer          | Aspire ES1-572              | [25f9b83c30](https://linux-hardware.org/?probe=25f9b83c30) | Apr 28, 2022 |
| HP            | Notebook                    | [daaa31b65a](https://linux-hardware.org/?probe=daaa31b65a) | Apr 27, 2022 |
| ASUSTek       | E402SA                      | [4c5cbe705d](https://linux-hardware.org/?probe=4c5cbe705d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [ea3e0b8695](https://linux-hardware.org/?probe=ea3e0b8695) | Apr 26, 2022 |
| MouseCompu... | NH55Dx                      | [0a397dd5e7](https://linux-hardware.org/?probe=0a397dd5e7) | Apr 25, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [37a92322aa](https://linux-hardware.org/?probe=37a92322aa) | Apr 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [190d52b2d6](https://linux-hardware.org/?probe=190d52b2d6) | Apr 25, 2022 |
| Acer          | TravelMate P259-MG          | [debe4697b9](https://linux-hardware.org/?probe=debe4697b9) | Apr 23, 2022 |
| Dell          | Latitude 3340               | [e6aa31da26](https://linux-hardware.org/?probe=e6aa31da26) | Apr 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c90694a42c](https://linux-hardware.org/?probe=c90694a42c) | Apr 23, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [e97ab3fc6c](https://linux-hardware.org/?probe=e97ab3fc6c) | Apr 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2c17462cda](https://linux-hardware.org/?probe=2c17462cda) | Apr 22, 2022 |
| Dell          | Latitude E5500              | [500b4b5ee2](https://linux-hardware.org/?probe=500b4b5ee2) | Apr 22, 2022 |
| Dell          | Inspiron 7577               | [ea4f513eb9](https://linux-hardware.org/?probe=ea4f513eb9) | Apr 22, 2022 |
| HP            | EliteBook 8470p             | [c1623a9f89](https://linux-hardware.org/?probe=c1623a9f89) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ce3b387afa](https://linux-hardware.org/?probe=ce3b387afa) | Apr 21, 2022 |
| Dell          | XPS 13 7390                 | [b2cc2161d3](https://linux-hardware.org/?probe=b2cc2161d3) | Apr 21, 2022 |
| Apple         | MacBookAir5,1               | [3dd8282149](https://linux-hardware.org/?probe=3dd8282149) | Apr 20, 2022 |
| Toshiba       | TECRA R940                  | [e7dc07a41c](https://linux-hardware.org/?probe=e7dc07a41c) | Apr 20, 2022 |
| Intel         | W7650                       | [cdf0885f07](https://linux-hardware.org/?probe=cdf0885f07) | Apr 20, 2022 |
| Dell          | XPS 13 9310                 | [e6f96a585c](https://linux-hardware.org/?probe=e6f96a585c) | Apr 18, 2022 |
| Alienware     | M11x                        | [df72ecbe58](https://linux-hardware.org/?probe=df72ecbe58) | Apr 18, 2022 |
| Avell High... | B.ON                        | [6f37e0aabc](https://linux-hardware.org/?probe=6f37e0aabc) | Apr 18, 2022 |
| Apple         | MacBookPro12,1              | [3c5f232016](https://linux-hardware.org/?probe=3c5f232016) | Apr 17, 2022 |
| TUXEDO        | Book_XA1510                 | [b109942662](https://linux-hardware.org/?probe=b109942662) | Apr 17, 2022 |
| HP            | ZBook 17 G2                 | [d7b7a81cbb](https://linux-hardware.org/?probe=d7b7a81cbb) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | [9529ed78e9](https://linux-hardware.org/?probe=9529ed78e9) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | [1ef9e4e85d](https://linux-hardware.org/?probe=1ef9e4e85d) | Apr 16, 2022 |
| Dell          | XPS 15 9560                 | [abee14fa00](https://linux-hardware.org/?probe=abee14fa00) | Apr 16, 2022 |
| Fujitsu       | LIFEBOOK P771               | [f9d5ba9c1c](https://linux-hardware.org/?probe=f9d5ba9c1c) | Apr 16, 2022 |
| Fujitsu       | LIFEBOOK P771               | [a6580631d1](https://linux-hardware.org/?probe=a6580631d1) | Apr 16, 2022 |
| LG Electro... | 15Z95P-G.AA78B              | [f5ef9987a4](https://linux-hardware.org/?probe=f5ef9987a4) | Apr 15, 2022 |
| MSI           | Creator 15 A10SFS           | [42b2140343](https://linux-hardware.org/?probe=42b2140343) | Apr 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [539ce7e59a](https://linux-hardware.org/?probe=539ce7e59a) | Apr 15, 2022 |
| Alienware     | x17 R1                      | [86a2d88704](https://linux-hardware.org/?probe=86a2d88704) | Apr 15, 2022 |
| Sony          | VPCF115FM                   | [b174df5915](https://linux-hardware.org/?probe=b174df5915) | Apr 15, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [078a3464bf](https://linux-hardware.org/?probe=078a3464bf) | Apr 15, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [cffdde259f](https://linux-hardware.org/?probe=cffdde259f) | Apr 15, 2022 |
| Dell          | Inspiron 7559               | [5302420f94](https://linux-hardware.org/?probe=5302420f94) | Apr 15, 2022 |
| Dell          | Latitude E7450              | [9af0006104](https://linux-hardware.org/?probe=9af0006104) | Apr 15, 2022 |
| Framework     | Laptop                      | [e4c994f47a](https://linux-hardware.org/?probe=e4c994f47a) | Apr 14, 2022 |
| HP            | Laptop 14-cf0xxx            | [3fcf4f7e02](https://linux-hardware.org/?probe=3fcf4f7e02) | Apr 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [68d7627d20](https://linux-hardware.org/?probe=68d7627d20) | Apr 14, 2022 |
| Sony          | VPCF115FM                   | [03f96804b2](https://linux-hardware.org/?probe=03f96804b2) | Apr 14, 2022 |
| Lenovo        | E31-80 80MX                 | [ea96e85c49](https://linux-hardware.org/?probe=ea96e85c49) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c49c891a78](https://linux-hardware.org/?probe=c49c891a78) | Apr 14, 2022 |
| Lenovo        | ThinkPad T480 20L6S93F00    | [b8c57e6b8a](https://linux-hardware.org/?probe=b8c57e6b8a) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [9e6fc630f4](https://linux-hardware.org/?probe=9e6fc630f4) | Apr 14, 2022 |
| Framework     | Laptop                      | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [c9e8c79a2e](https://linux-hardware.org/?probe=c9e8c79a2e) | Apr 14, 2022 |
| Lenovo        | XiaoXin Chao7000-14IKBR ... | [2394088db1](https://linux-hardware.org/?probe=2394088db1) | Apr 14, 2022 |
| Framework     | Laptop                      | [b8850e9dc8](https://linux-hardware.org/?probe=b8850e9dc8) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [5f85d41ef2](https://linux-hardware.org/?probe=5f85d41ef2) | Apr 14, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [f3d294f808](https://linux-hardware.org/?probe=f3d294f808) | Apr 14, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [a7f25c6027](https://linux-hardware.org/?probe=a7f25c6027) | Apr 14, 2022 |
| Dell          | G5 5505                     | [7c8b949b95](https://linux-hardware.org/?probe=7c8b949b95) | Apr 14, 2022 |
| HP            | ENVY Notebook               | [2b982a201c](https://linux-hardware.org/?probe=2b982a201c) | Apr 14, 2022 |
| Lenovo        | ThinkPad T550 20CKCTO1WW    | [81d6a811d5](https://linux-hardware.org/?probe=81d6a811d5) | Apr 14, 2022 |
| Lenovo        | ThinkPad T410 2537E82       | [84026a1dd3](https://linux-hardware.org/?probe=84026a1dd3) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c68c62f98c](https://linux-hardware.org/?probe=c68c62f98c) | Apr 14, 2022 |
| Framework     | Laptop                      | [16d27bad7a](https://linux-hardware.org/?probe=16d27bad7a) | Apr 14, 2022 |
| Lenovo        | IdeaPad S540-13ARE 82DL     | [17363a1a13](https://linux-hardware.org/?probe=17363a1a13) | Apr 14, 2022 |
| HP            | ZBook Firefly 15 G7 Mobi... | [0e9e99acae](https://linux-hardware.org/?probe=0e9e99acae) | Apr 13, 2022 |
| Monster       | ABRA A5 V15.8               | [28f1e82585](https://linux-hardware.org/?probe=28f1e82585) | Apr 13, 2022 |
| Lenovo        | ThinkPad X220 4291QT1       | [58ef1f3594](https://linux-hardware.org/?probe=58ef1f3594) | Apr 13, 2022 |
| Apple         | MacBookPro10,2              | [cf7c54ff19](https://linux-hardware.org/?probe=cf7c54ff19) | Apr 13, 2022 |
| Lenovo        | ThinkPad T440p 20AN006GU... | [8c26cf3ce0](https://linux-hardware.org/?probe=8c26cf3ce0) | Apr 13, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [6dc0087ab4](https://linux-hardware.org/?probe=6dc0087ab4) | Apr 13, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b076cac85d](https://linux-hardware.org/?probe=b076cac85d) | Apr 13, 2022 |
| Samsung       | 270E5J/2570EJ               | [4aeb8de6f6](https://linux-hardware.org/?probe=4aeb8de6f6) | Apr 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [90505ddcfa](https://linux-hardware.org/?probe=90505ddcfa) | Apr 13, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [eff12a28fd](https://linux-hardware.org/?probe=eff12a28fd) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NY000JM... | [e93e7d9ad1](https://linux-hardware.org/?probe=e93e7d9ad1) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [2edcc0aefa](https://linux-hardware.org/?probe=2edcc0aefa) | Apr 13, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [32371c52a6](https://linux-hardware.org/?probe=32371c52a6) | Apr 13, 2022 |
| Apple         | MacBookPro8,1               | [fad4436356](https://linux-hardware.org/?probe=fad4436356) | Apr 13, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [75f2876f06](https://linux-hardware.org/?probe=75f2876f06) | Apr 12, 2022 |
| Lenovo        | V130-15IGM 81HL             | [c74caa4194](https://linux-hardware.org/?probe=c74caa4194) | Apr 12, 2022 |
| Dell          | Vostro 14-5459              | [89d65f0a36](https://linux-hardware.org/?probe=89d65f0a36) | Apr 12, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [7c4eb57bca](https://linux-hardware.org/?probe=7c4eb57bca) | Apr 12, 2022 |
| Razer         | Blade                       | [13c7eb09fa](https://linux-hardware.org/?probe=13c7eb09fa) | Apr 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [7007f9e0fc](https://linux-hardware.org/?probe=7007f9e0fc) | Apr 12, 2022 |
| Framework     | Laptop                      | [02b837b78a](https://linux-hardware.org/?probe=02b837b78a) | Apr 12, 2022 |
| Dell          | Latitude 5480               | [f733f24fdc](https://linux-hardware.org/?probe=f733f24fdc) | Apr 12, 2022 |
| ASUSTek       | S551LN                      | [8795a49142](https://linux-hardware.org/?probe=8795a49142) | Apr 12, 2022 |
| ASUSTek       | S551LN                      | [4999fb1eff](https://linux-hardware.org/?probe=4999fb1eff) | Apr 12, 2022 |
| HUAWEI        | KLVL-WXX9                   | [47cecc43f6](https://linux-hardware.org/?probe=47cecc43f6) | Apr 11, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [a86b688768](https://linux-hardware.org/?probe=a86b688768) | Apr 11, 2022 |
| Dell          | Precision M6800             | [571eab63d2](https://linux-hardware.org/?probe=571eab63d2) | Apr 10, 2022 |
| Dell          | Precision M6800             | [236217f64d](https://linux-hardware.org/?probe=236217f64d) | Apr 10, 2022 |
| Acer          | One 14 Z2-485               | [57f307fa80](https://linux-hardware.org/?probe=57f307fa80) | Apr 09, 2022 |
| Lenovo        | XiaoXin Air 13IML 81WV      | [c5ae7c810d](https://linux-hardware.org/?probe=c5ae7c810d) | Apr 09, 2022 |
| HP            | Pavilion Notebook           | [f76d101440](https://linux-hardware.org/?probe=f76d101440) | Apr 09, 2022 |
| Acer          | Nitro AN515-45              | [ce9698e187](https://linux-hardware.org/?probe=ce9698e187) | Apr 09, 2022 |
| Lenovo        | Yoga Slim 7 Carbon 14ACN... | [5328fde624](https://linux-hardware.org/?probe=5328fde624) | Apr 08, 2022 |
| LG Electro... | S430-G.BC33P1               | [95f8d514d6](https://linux-hardware.org/?probe=95f8d514d6) | Apr 08, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Arch/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Arch          | 1744      | 59.83%  |
| Arch Rolling  | 1161      | 39.83%  |
| Arch V20.5.7  | 2         | 0.07%   |
| Arch V19.04.4 | 2         | 0.07%   |
| Arch V6.9.2   | 1         | 0.03%   |
| Arch V20.3.4  | 1         | 0.03%   |
| Arch V19.07.9 | 1         | 0.03%   |
| Arch V19.06.1 | 1         | 0.03%   |
| Arch V19.01.4 | 1         | 0.03%   |
| Arch 2.7      | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Arch | 2824      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version         | Notebooks | Percent |
|-----------------|-----------|---------|
| 5.17.1-arch1-1  | 52        | 1.56%   |
| 6.0.2-arch1-1   | 51        | 1.53%   |
| 5.9.14-arch1-1  | 31        | 0.93%   |
| 5.9.1-arch1-1   | 31        | 0.93%   |
| 5.8.5-arch1-1   | 28        | 0.84%   |
| 5.17.5-arch1-1  | 28        | 0.84%   |
| 5.8.10-arch1-1  | 26        | 0.78%   |
| 5.17.9-arch1-1  | 24        | 0.72%   |
| 5.11.16-arch1-1 | 24        | 0.72%   |
| 5.8.14-arch1-1  | 23        | 0.69%   |
| 5.8.1-arch1-1   | 23        | 0.69%   |
| 5.7.12-arch1-1  | 23        | 0.69%   |
| 6.0.9-arch1-1   | 22        | 0.66%   |
| 5.18.1-arch1-1  | 22        | 0.66%   |
| 5.13.13-arch1-1 | 22        | 0.66%   |
| 5.13.12-arch1-1 | 22        | 0.66%   |
| 5.18.16-arch1-1 | 21        | 0.63%   |
| 5.9.10-arch1-1  | 20        | 0.6%    |
| 5.8.12-arch1-1  | 20        | 0.6%    |
| 6.0.7-arch1-1   | 19        | 0.57%   |
| 5.8.3-arch1-1   | 19        | 0.57%   |
| 5.16.16-arch1-1 | 19        | 0.57%   |
| 5.11.11-arch1-1 | 19        | 0.57%   |
| 5.9.11-arch2-1  | 18        | 0.54%   |
| 5.19.13-arch1-1 | 18        | 0.54%   |
| 5.16.2-arch1-1  | 18        | 0.54%   |
| 5.12.15-arch1-1 | 18        | 0.54%   |
| 5.11.2-arch1-1  | 18        | 0.54%   |
| 5.7.6-arch1-1   | 17        | 0.51%   |
| 5.6.13-arch1-1  | 17        | 0.51%   |
| 5.18.14-arch1-1 | 17        | 0.51%   |
| 5.15.2-arch1-1  | 17        | 0.51%   |
| 5.14.14-arch1-1 | 17        | 0.51%   |
| 5.10.16-arch1-1 | 17        | 0.51%   |
| 5.6.15-arch1-1  | 16        | 0.48%   |
| 5.15.7-arch1-1  | 16        | 0.48%   |
| 5.14.8-arch1-1  | 16        | 0.48%   |
| 6.0.8-arch1-1   | 15        | 0.45%   |
| 5.6.11-arch1-1  | 15        | 0.45%   |
| 5.18.12-arch1-1 | 15        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.1  | 65        | 1.95%   |
| 6.0.2   | 60        | 1.8%    |
| 5.9.1   | 40        | 1.2%    |
| 5.9.14  | 38        | 1.14%   |
| 5.8.5   | 38        | 1.14%   |
| 5.17.5  | 38        | 1.14%   |
| 5.13.13 | 31        | 0.93%   |
| 5.8.14  | 30        | 0.9%    |
| 5.8.10  | 29        | 0.87%   |
| 5.17.9  | 29        | 0.87%   |
| 6.0.9   | 28        | 0.84%   |
| 5.18.16 | 27        | 0.81%   |
| 5.8.12  | 26        | 0.78%   |
| 5.8.1   | 26        | 0.78%   |
| 5.18.1  | 26        | 0.78%   |
| 5.16.2  | 26        | 0.78%   |
| 5.13.12 | 26        | 0.78%   |
| 5.11.16 | 26        | 0.78%   |
| 5.7.12  | 25        | 0.75%   |
| 5.16.16 | 24        | 0.72%   |
| 5.14.8  | 24        | 0.72%   |
| 5.11.2  | 24        | 0.72%   |
| 5.10.16 | 24        | 0.72%   |
| 6.0.8   | 23        | 0.69%   |
| 5.19.13 | 23        | 0.69%   |
| 5.18.3  | 23        | 0.69%   |
| 5.12.15 | 23        | 0.69%   |
| 5.14.14 | 22        | 0.66%   |
| 6.0.7   | 21        | 0.63%   |
| 5.9.11  | 21        | 0.63%   |
| 5.9.10  | 21        | 0.63%   |
| 5.8.3   | 21        | 0.63%   |
| 5.19.2  | 21        | 0.63%   |
| 5.15.10 | 21        | 0.63%   |
| 5.11.11 | 21        | 0.63%   |
| 5.7.6   | 20        | 0.6%    |
| 5.5.13  | 20        | 0.6%    |
| 5.18.14 | 20        | 0.6%    |
| 5.13.4  | 20        | 0.6%    |
| 5.6.13  | 19        | 0.57%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 239       | 7.46%   |
| 5.8     | 232       | 7.25%   |
| 5.18    | 218       | 6.81%   |
| 5.9     | 208       | 6.5%    |
| 5.17    | 197       | 6.15%   |
| 5.4     | 193       | 6.03%   |
| 5.16    | 188       | 5.87%   |
| 5.10    | 182       | 5.68%   |
| 6.0     | 181       | 5.65%   |
| 5.19    | 173       | 5.4%    |
| 5.11    | 168       | 5.25%   |
| 5.12    | 153       | 4.78%   |
| 5.13    | 142       | 4.43%   |
| 5.7     | 138       | 4.31%   |
| 5.6     | 135       | 4.22%   |
| 5.14    | 128       | 4%      |
| 5.5     | 93        | 2.9%    |
| 5.3     | 64        | 2%      |
| 5.2     | 33        | 1.03%   |
| 4.19    | 26        | 0.81%   |
| 5.0     | 19        | 0.59%   |
| 5.1     | 16        | 0.5%    |
| 4.18    | 16        | 0.5%    |
| 4.17    | 12        | 0.37%   |
| 4.20    | 9         | 0.28%   |
| 4.14    | 9         | 0.28%   |
| 4.15    | 5         | 0.16%   |
| 4.9     | 4         | 0.12%   |
| 4.7     | 4         | 0.12%   |
| 4.16    | 4         | 0.12%   |
| 4.6     | 3         | 0.09%   |
| 4.4     | 3         | 0.09%   |
| 4.8     | 2         | 0.06%   |
| 4.13    | 2         | 0.06%   |
| 4.11    | 2         | 0.06%   |
| Unknown | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2821      | 99.89%  |
| i686   | 3         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| GNOME                    | 985       | 33.48%  |
| KDE5                     | 660       | 22.43%  |
| Unknown                  | 405       | 13.77%  |
| XFCE                     | 228       | 7.75%   |
| i3                       | 167       | 5.68%   |
| KDE                      | 139       | 4.72%   |
| sway                     | 41        | 1.39%   |
| MATE                     | 39        | 1.33%   |
| Budgie                   | 39        | 1.33%   |
| Cinnamon                 | 37        | 1.26%   |
| X-Cinnamon               | 34        | 1.16%   |
| LXQt                     | 28        | 0.95%   |
| awesome                  | 22        | 0.75%   |
| Deepin                   | 21        | 0.71%   |
| LXDE                     | 15        | 0.51%   |
| bspwm                    | 14        | 0.48%   |
| GNOME Flashback          | 9         | 0.31%   |
| qtile                    | 8         | 0.27%   |
| xmonad                   | 7         | 0.24%   |
| Unity                    | 7         | 0.24%   |
| Hyprland                 | 6         | 0.2%    |
| DWM                      | 6         | 0.2%    |
| openbox                  | 5         | 0.17%   |
| GNOME Classic            | 4         | 0.14%   |
| Enlightenment            | 4         | 0.14%   |
| i3-with-shmlog           | 3         | 0.1%    |
| X-Generic                | 1         | 0.03%   |
| river                    | 1         | 0.03%   |
| Pantheon                 | 1         | 0.03%   |
| jwm                      | 1         | 0.03%   |
| instantwm                | 1         | 0.03%   |
| ICEWM                    | 1         | 0.03%   |
| dusk                     | 1         | 0.03%   |
| default                  | 1         | 0.03%   |
| /usr/bin/openbox-session | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1732      | 59.46%  |
| Wayland | 720       | 24.72%  |
| Tty     | 260       | 8.93%   |
| Unknown | 201       | 6.9%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1225      | 41.89%  |
| SDDM    | 655       | 22.4%   |
| GDM     | 436       | 14.91%  |
| LightDM | 313       | 10.7%   |
| TDM     | 188       | 6.43%   |
| Ly      | 31        | 1.06%   |
| XDM     | 28        | 0.96%   |
| LXDM    | 23        | 0.79%   |
| SLiM    | 10        | 0.34%   |
| GREETD  | 8         | 0.27%   |
| NODM    | 3         | 0.1%    |
| EMPTTY  | 3         | 0.1%    |
| MDM     | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 1387      | 48.09%  |
| Unknown | 342       | 11.86%  |
| en_GB   | 160       | 5.55%   |
| C       | 134       | 4.65%   |
| it_IT   | 94        | 3.26%   |
| de_DE   | 94        | 3.26%   |
| pt_BR   | 80        | 2.77%   |
| ru_RU   | 72        | 2.5%    |
| fr_FR   | 65        | 2.25%   |
| en_IN   | 41        | 1.42%   |
| pl_PL   | 38        | 1.32%   |
| zh_CN   | 33        | 1.14%   |
| es_ES   | 32        | 1.11%   |
| en_CA   | 29        | 1.01%   |
| en_AU   | 23        | 0.8%    |
| es_MX   | 14        | 0.49%   |
| es_AR   | 11        | 0.38%   |
| en_IE   | 11        | 0.38%   |
| de_AT   | 10        | 0.35%   |
| tr_TR   | 9         | 0.31%   |
| ja_JP   | 9         | 0.31%   |
| en_DK   | 9         | 0.31%   |
| hu_HU   | 8         | 0.28%   |
| es_CL   | 8         | 0.28%   |
| ru_UA   | 7         | 0.24%   |
| es_CO   | 7         | 0.24%   |
| en_SG   | 7         | 0.24%   |
| en_NZ   | 7         | 0.24%   |
| pt_PT   | 6         | 0.21%   |
| nl_NL   | 6         | 0.21%   |
| en_ZA   | 6         | 0.21%   |
| zh_TW   | 5         | 0.17%   |
| fr_CA   | 5         | 0.17%   |
| es_PE   | 5         | 0.17%   |
| cs_CZ   | 5         | 0.17%   |
| ca_ES   | 5         | 0.17%   |
| ko_KR   | 4         | 0.14%   |
| fr_CH   | 4         | 0.14%   |
| fr_BE   | 4         | 0.14%   |
| en-US   | 4         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1805      | 62.41%  |
| BIOS | 1087      | 37.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2099      | 73.49%  |
| Btrfs   | 507       | 17.75%  |
| Unknown | 108       | 3.78%   |
| Xfs     | 66        | 2.31%   |
| F2fs    | 37        | 1.3%    |
| Zfs     | 16        | 0.56%   |
| Overlay | 15        | 0.53%   |
| Ext2    | 3         | 0.11%   |
| XXXXX   | 2         | 0.07%   |
| XXX4    | 1         | 0.04%   |
| Jfs     | 1         | 0.04%   |
| Aufs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1771      | 61.77%  |
| Unknown | 836       | 29.16%  |
| MBR     | 260       | 9.07%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2564      | 89.9%   |
| Yes       | 288       | 10.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2097      | 73.27%  |
| Yes       | 765       | 26.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 829       | 29.36%  |
| Dell                   | 463       | 16.4%   |
| Hewlett-Packard        | 385       | 13.63%  |
| ASUSTek Computer       | 333       | 11.79%  |
| Acer                   | 223       | 7.9%    |
| MSI                    | 82        | 2.9%    |
| Apple                  | 57        | 2.02%   |
| Samsung Electronics    | 47        | 1.66%   |
| HUAWEI                 | 45        | 1.59%   |
| Toshiba                | 36        | 1.27%   |
| Notebook               | 27        | 0.96%   |
| Timi                   | 20        | 0.71%   |
| Google                 | 19        | 0.67%   |
| Sony                   | 18        | 0.64%   |
| Framework              | 17        | 0.6%    |
| TUXEDO                 | 14        | 0.5%    |
| Alienware              | 14        | 0.5%    |
| Razer                  | 13        | 0.46%   |
| Unknown                | 12        | 0.42%   |
| Fujitsu                | 11        | 0.39%   |
| LG Electronics         | 9         | 0.32%   |
| Avell High Performance | 9         | 0.32%   |
| System76               | 8         | 0.28%   |
| Schenker               | 7         | 0.25%   |
| Packard Bell           | 7         | 0.25%   |
| Intel                  | 7         | 0.25%   |
| MECHREVO               | 6         | 0.21%   |
| Gigabyte Technology    | 6         | 0.21%   |
| Positivo               | 5         | 0.18%   |
| Chuwi                  | 5         | 0.18%   |
| Teclast                | 4         | 0.14%   |
| SLIMBOOK               | 4         | 0.14%   |
| Medion                 | 4         | 0.14%   |
| Koompi                 | 4         | 0.14%   |
| GPD                    | 4         | 0.14%   |
| PC Specialist          | 3         | 0.11%   |
| Intel Client Systems   | 3         | 0.11%   |
| HONOR                  | 3         | 0.11%   |
| Fujitsu Siemens        | 3         | 0.11%   |
| Eluktronics            | 3         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 29        | 1.03%   |
| Framework Laptop                    | 16        | 0.57%   |
| HP Notebook                         | 14        | 0.5%    |
| Dell XPS 15 9570                    | 14        | 0.5%    |
| Dell XPS 15 9500                    | 12        | 0.42%   |
| Dell XPS 13 9360                    | 11        | 0.39%   |
| Dell XPS 13 9380                    | 10        | 0.35%   |
| Dell Inspiron 15 7000 Gaming        | 10        | 0.35%   |
| HUAWEI NBLK-WAX9X                   | 9         | 0.32%   |
| HP EliteBook 840 G6                 | 9         | 0.32%   |
| Dell XPS 15 7590                    | 9         | 0.32%   |
| Dell XPS 13 9370                    | 9         | 0.32%   |
| Lenovo IdeaPad 5 14ARE05 81YM       | 8         | 0.28%   |
| Dell XPS 13 9350                    | 8         | 0.28%   |
| Dell Latitude E6430                 | 8         | 0.28%   |
| ASUS ROG Strix G513QY_G513QY        | 8         | 0.28%   |
| Lenovo ThinkBook 15 G2 ITL 20VE     | 7         | 0.25%   |
| HP 250 G6 Notebook PC               | 7         | 0.25%   |
| Dell XPS 13 9310                    | 7         | 0.25%   |
| Dell Precision 7540                 | 7         | 0.25%   |
| Dell Latitude E7450                 | 7         | 0.25%   |
| Dell Inspiron 5570                  | 7         | 0.25%   |
| ASUS TUF Gaming FX505DT_FX505DT     | 7         | 0.25%   |
| Acer Nitro AN515-52                 | 7         | 0.25%   |
| Lenovo Y520-15IKBN 80WK             | 6         | 0.21%   |
| Lenovo Legion 5 15ARH05 82B5        | 6         | 0.21%   |
| HP Pavilion Notebook                | 6         | 0.21%   |
| HP Pavilion Gaming Laptop 15-cx0xxx | 6         | 0.21%   |
| HP Pavilion g6                      | 6         | 0.21%   |
| HP EliteBook 840 G5                 | 6         | 0.21%   |
| Dell XPS 13 7390                    | 6         | 0.21%   |
| Dell Latitude 5480                  | 6         | 0.21%   |
| ASUS X580VD                         | 6         | 0.21%   |
| Apple MacBookAir7,2                 | 6         | 0.21%   |
| Acer Aspire E5-571                  | 6         | 0.21%   |
| Timi TM1701                         | 5         | 0.18%   |
| Razer Blade                         | 5         | 0.18%   |
| Lenovo ThinkPad T480 20L5CTO1WW     | 5         | 0.18%   |
| Lenovo Legion Y530-15ICH 81FV       | 5         | 0.18%   |
| Lenovo IdeaPad L340-15API 81LW      | 5         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 499       | 17.67%  |
| Lenovo IdeaPad    | 153       | 5.42%   |
| Acer Aspire       | 130       | 4.6%    |
| Dell Inspiron     | 129       | 4.57%   |
| Dell XPS          | 118       | 4.18%   |
| Dell Latitude     | 118       | 4.18%   |
| HP Pavilion       | 82        | 2.9%    |
| HP EliteBook      | 82        | 2.9%    |
| Lenovo Legion     | 52        | 1.84%   |
| HP Laptop         | 50        | 1.77%   |
| HP ProBook        | 49        | 1.74%   |
| ASUS VivoBook     | 48        | 1.7%    |
| ASUS ROG          | 44        | 1.56%   |
| Dell Precision    | 41        | 1.45%   |
| Acer Nitro        | 35        | 1.24%   |
| Unknown           | 29        | 1.03%   |
| Toshiba Satellite | 28        | 0.99%   |
| Dell Vostro       | 26        | 0.92%   |
| Lenovo ThinkBook  | 25        | 0.89%   |
| ASUS TUF          | 25        | 0.89%   |
| Acer Swift        | 25        | 0.89%   |
| ASUS ZenBook      | 23        | 0.81%   |
| HP ENVY           | 21        | 0.74%   |
| ASUS ASUS         | 21        | 0.74%   |
| Framework Laptop  | 17        | 0.6%    |
| HP OMEN           | 15        | 0.53%   |
| HP 250            | 15        | 0.53%   |
| Lenovo Yoga       | 14        | 0.5%    |
| HP Notebook       | 14        | 0.5%    |
| Razer Blade       | 13        | 0.46%   |
| MSI Modern        | 11        | 0.39%   |
| Fujitsu LIFEBOOK  | 11        | 0.39%   |
| Dell G3           | 11        | 0.39%   |
| Acer Predator     | 10        | 0.35%   |
| HUAWEI NBLK-WAX9X | 9         | 0.32%   |
| HP ZBook          | 9         | 0.32%   |
| HP 255            | 9         | 0.32%   |
| ASUS Strix        | 8         | 0.28%   |
| Dell G5           | 7         | 0.25%   |
| Apple MacBookAir7 | 7         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 400       | 14.16%  |
| 2020    | 375       | 13.28%  |
| 2018    | 344       | 12.18%  |
| 2021    | 292       | 10.34%  |
| 2017    | 229       | 8.11%   |
| 2015    | 179       | 6.34%   |
| 2016    | 176       | 6.23%   |
| 2012    | 155       | 5.49%   |
| 2013    | 150       | 5.31%   |
| 2011    | 138       | 4.89%   |
| 2014    | 130       | 4.6%    |
| 2010    | 89        | 3.15%   |
| 2022    | 61        | 2.16%   |
| 2008    | 53        | 1.88%   |
| 2009    | 39        | 1.38%   |
| 2007    | 9         | 0.32%   |
| 2006    | 4         | 0.14%   |
| Unknown | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2824      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2798      | 98.83%  |
| Enabled  | 33        | 1.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2791      | 98.83%  |
| Yes  | 33        | 1.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 748       | 26.16%  |
| 16.01-24.0  | 686       | 23.99%  |
| 8.01-16.0   | 646       | 22.6%   |
| 3.01-4.0    | 337       | 11.79%  |
| 32.01-64.0  | 275       | 9.62%   |
| 24.01-32.0  | 50        | 1.75%   |
| 1.01-2.0    | 47        | 1.64%   |
| 64.01-256.0 | 45        | 1.57%   |
| 2.01-3.0    | 20        | 0.7%    |
| 0.51-1.0    | 5         | 0.17%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 801       | 25.69%  |
| 2.01-3.0   | 800       | 25.66%  |
| 4.01-8.0   | 613       | 19.66%  |
| 3.01-4.0   | 534       | 17.13%  |
| 8.01-16.0  | 183       | 5.87%   |
| 0.51-1.0   | 131       | 4.2%    |
| 0.01-0.5   | 27        | 0.87%   |
| 16.01-24.0 | 18        | 0.58%   |
| 24.01-32.0 | 10        | 0.32%   |
| 32.01-64.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1948      | 67.85%  |
| 2      | 789       | 27.48%  |
| 3      | 105       | 3.66%   |
| 0      | 14        | 0.49%   |
| 4      | 11        | 0.38%   |
| 5      | 3         | 0.1%    |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2231      | 78.64%  |
| Yes       | 606       | 21.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2207      | 77.79%  |
| No        | 630       | 22.21%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2802      | 99.15%  |
| No        | 24        | 0.85%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2417      | 84.75%  |
| No        | 435       | 15.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 492       | 17.31%  |
| Germany      | 241       | 8.48%   |
| Russia       | 169       | 5.94%   |
| Italy        | 155       | 5.45%   |
| Brazil       | 155       | 5.45%   |
| France       | 131       | 4.61%   |
| India        | 125       | 4.4%    |
| UK           | 95        | 3.34%   |
| Poland       | 84        | 2.95%   |
| Canada       | 73        | 2.57%   |
| Spain        | 61        | 2.15%   |
| Netherlands  | 57        | 2%      |
| China        | 56        | 1.97%   |
| Turkey       | 41        | 1.44%   |
| Australia    | 40        | 1.41%   |
| Ukraine      | 39        | 1.37%   |
| Austria      | 38        | 1.34%   |
| Sweden       | 35        | 1.23%   |
| Indonesia    | 32        | 1.13%   |
| Belgium      | 30        | 1.06%   |
| Czechia      | 29        | 1.02%   |
| Mexico       | 28        | 0.98%   |
| Romania      | 26        | 0.91%   |
| Portugal     | 23        | 0.81%   |
| Argentina    | 23        | 0.81%   |
| Switzerland  | 22        | 0.77%   |
| Vietnam      | 21        | 0.74%   |
| Iran         | 21        | 0.74%   |
| Japan        | 20        | 0.7%    |
| Hungary      | 19        | 0.67%   |
| New Zealand  | 18        | 0.63%   |
| Greece       | 18        | 0.63%   |
| Finland      | 18        | 0.63%   |
| Colombia     | 18        | 0.63%   |
| Denmark      | 17        | 0.6%    |
| Chile        | 16        | 0.56%   |
| Norway       | 15        | 0.53%   |
| Belarus      | 15        | 0.53%   |
| South Africa | 12        | 0.42%   |
| Peru         | 12        | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 47        | 1.57%   |
| Milan             | 28        | 0.93%   |
| Paris             | 27        | 0.9%    |
| St Petersburg     | 26        | 0.87%   |
| Sao Paulo         | 26        | 0.87%   |
| Berlin            | 25        | 0.83%   |
| Warsaw            | 24        | 0.8%    |
| Munich            | 20        | 0.67%   |
| Los Angeles       | 20        | 0.67%   |
| Vienna            | 19        | 0.63%   |
| Amsterdam         | 17        | 0.57%   |
| Valencia          | 16        | 0.53%   |
| Bengaluru         | 16        | 0.53%   |
| Prague            | 15        | 0.5%    |
| Kyiv              | 15        | 0.5%    |
| Istanbul          | 15        | 0.5%    |
| Sydney            | 14        | 0.47%   |
| Phoenix           | 13        | 0.43%   |
| Frankfurt am Main | 13        | 0.43%   |
| Tehran            | 12        | 0.4%    |
| Montreal          | 12        | 0.4%    |
| Melbourne         | 11        | 0.37%   |
| Jakarta           | 11        | 0.37%   |
| Hamburg           | 11        | 0.37%   |
| Buenos Aires      | 11        | 0.37%   |
| Mexico City       | 10        | 0.33%   |
| Helsinki          | 10        | 0.33%   |
| Cologne           | 10        | 0.33%   |
| Budapest          | 10        | 0.33%   |
| Bogotá           | 10        | 0.33%   |
| Athens            | 10        | 0.33%   |
| Turin             | 9         | 0.3%    |
| Seattle           | 9         | 0.3%    |
| Rome              | 9         | 0.3%    |
| New York          | 9         | 0.3%    |
| London            | 9         | 0.3%    |
| Lima              | 9         | 0.3%    |
| Curitiba          | 9         | 0.3%    |
| Chennai           | 9         | 0.3%    |
| Beijing           | 9         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 791       | 1049   | 21.21%  |
| WDC                         | 412       | 509    | 11.05%  |
| Seagate                     | 343       | 417    | 9.2%    |
| SanDisk                     | 300       | 348    | 8.04%   |
| Toshiba                     | 265       | 308    | 7.1%    |
| SK hynix                    | 206       | 245    | 5.52%   |
| Kingston                    | 181       | 224    | 4.85%   |
| Unknown                     | 150       | 181    | 4.02%   |
| Intel                       | 134       | 170    | 3.59%   |
| Crucial                     | 110       | 150    | 2.95%   |
| HGST                        | 107       | 115    | 2.87%   |
| Micron Technology           | 106       | 125    | 2.84%   |
| Hitachi                     | 59        | 60     | 1.58%   |
| A-DATA Technology           | 47        | 65     | 1.26%   |
| Apple                       | 35        | 42     | 0.94%   |
| Phison                      | 27        | 32     | 0.72%   |
| LITEON                      | 27        | 28     | 0.72%   |
| KIOXIA                      | 24        | 27     | 0.64%   |
| Transcend                   | 21        | 22     | 0.56%   |
| SPCC                        | 17        | 18     | 0.46%   |
| Lenovo                      | 16        | 18     | 0.43%   |
| China                       | 16        | 21     | 0.43%   |
| Silicon Motion              | 15        | 15     | 0.4%    |
| Phison Electronics          | 13        | 13     | 0.35%   |
| JMicron Technology          | 13        | 12     | 0.35%   |
| PNY                         | 12        | 15     | 0.32%   |
| LITEONIT                    | 11        | 11     | 0.29%   |
| ADATA Technology            | 11        | 12     | 0.29%   |
| Micron/Crucial Technology   | 10        | 11     | 0.27%   |
| KingSpec                    | 10        | 11     | 0.27%   |
| GOODRAM                     | 10        | 10     | 0.27%   |
| Patriot                     | 9         | 9      | 0.24%   |
| OCZ                         | 8         | 8      | 0.21%   |
| Lite-On                     | 8         | 10     | 0.21%   |
| Kingston Technology Company | 8         | 8      | 0.21%   |
| Plextor                     | 7         | 7      | 0.19%   |
| FORESEE                     | 7         | 9      | 0.19%   |
| Corsair                     | 7         | 8      | 0.19%   |
| Union Memory (Shenzhen)     | 6         | 6      | 0.16%   |
| UMIS                        | 6         | 7      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                       | 78        | 1.99%   |
| Samsung NVMe SSD Drive 512GB                         | 63        | 1.61%   |
| SanDisk NVMe SSD Drive 512GB                         | 45        | 1.15%   |
| HGST HTS721010A9E630 1TB                             | 43        | 1.1%    |
| SK hynix NVMe SSD Drive 512GB                        | 39        | 0.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 39        | 0.99%   |
| Toshiba MQ01ABD100 1TB                               | 36        | 0.92%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 35        | 0.89%   |
| Samsung SSD 860 EVO 500GB                            | 34        | 0.87%   |
| Toshiba MQ04ABF100 1TB                               | 33        | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 31        | 0.79%   |
| Kingston SA400S37240G 240GB SSD                      | 28        | 0.71%   |
| Samsung SSD 850 EVO 500GB                            | 27        | 0.69%   |
| SanDisk NVMe SSD Drive 256GB                         | 24        | 0.61%   |
| Seagate ST1000LM048-2E7172 1TB                       | 23        | 0.59%   |
| Seagate ST2000LM007-1R8174 2TB                       | 22        | 0.56%   |
| Crucial CT500MX500SSD1 500GB                         | 22        | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB                         | 21        | 0.54%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 20        | 0.51%   |
| Toshiba NVMe SSD Drive 512GB                         | 20        | 0.51%   |
| SanDisk NVMe SSD Drive 1TB                           | 20        | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB                       | 20        | 0.51%   |
| Samsung NVMe SSD Drive 1TB                           | 20        | 0.51%   |
| HGST HTS541010A9E680 1TB                             | 20        | 0.51%   |
| Unknown MMC Card  64GB                               | 19        | 0.48%   |
| Unknown MMC Card  32GB                               | 18        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB                      | 18        | 0.46%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB    | 18        | 0.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 18        | 0.46%   |
| Kingston SA400S37480G 480GB SSD                      | 18        | 0.46%   |
| Seagate ST1000LX015-1U7172 1TB                       | 17        | 0.43%   |
| Samsung SSD 860 EVO 1TB                              | 17        | 0.43%   |
| Samsung NVMe SSD Drive 500GB                         | 17        | 0.43%   |
| Toshiba MQ01ABF050 500GB                             | 16        | 0.41%   |
| Kingston SA400S37120G 120GB SSD                      | 16        | 0.41%   |
| Crucial CT1000MX500SSD1 1TB                          | 16        | 0.41%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 15        | 0.38%   |
| SK hynix NVMe SSD Drive 256GB                        | 15        | 0.38%   |
| Samsung SSD 850 EVO 250GB                            | 15        | 0.38%   |
| Intel SSDPEKNW512G8 512GB                            | 15        | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 336       | 408    | 37.17%  |
| WDC                 | 222       | 257    | 24.56%  |
| Toshiba             | 146       | 163    | 16.15%  |
| HGST                | 107       | 115    | 11.84%  |
| Hitachi             | 59        | 60     | 6.53%   |
| Unknown             | 9         | 11     | 1%      |
| Samsung Electronics | 8         | 8      | 0.88%   |
| Fujitsu             | 4         | 4      | 0.44%   |
| ASMT                | 3         | 4      | 0.33%   |
| Apple               | 3         | 3      | 0.33%   |
| HGST HTS            | 2         | 2      | 0.22%   |
| SAGE                | 1         | 1      | 0.11%   |
| PHD 3.0             | 1         | 1      | 0.11%   |
| NeoTech             | 1         | 1      | 0.11%   |
| Maxone              | 1         | 1      | 0.11%   |
| ACASIS              | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 305       | 375    | 26.43%  |
| SanDisk             | 133       | 149    | 11.53%  |
| Kingston            | 124       | 151    | 10.75%  |
| Crucial             | 97        | 127    | 8.41%   |
| WDC                 | 76        | 98     | 6.59%   |
| Toshiba             | 31        | 39     | 2.69%   |
| SK hynix            | 31        | 37     | 2.69%   |
| Micron Technology   | 31        | 38     | 2.69%   |
| Intel               | 29        | 33     | 2.51%   |
| A-DATA Technology   | 29        | 43     | 2.51%   |
| LITEON              | 24        | 25     | 2.08%   |
| Apple               | 22        | 23     | 1.91%   |
| Transcend           | 21        | 22     | 1.82%   |
| China               | 16        | 21     | 1.39%   |
| SPCC                | 13        | 13     | 1.13%   |
| PNY                 | 11        | 14     | 0.95%   |
| LITEONIT            | 11        | 11     | 0.95%   |
| KingSpec            | 10        | 11     | 0.87%   |
| Patriot             | 9         | 9      | 0.78%   |
| GOODRAM             | 9         | 9      | 0.78%   |
| OCZ                 | 8         | 8      | 0.69%   |
| JMicron Technology  | 8         | 8      | 0.69%   |
| Plextor             | 7         | 7      | 0.61%   |
| Intenso             | 6         | 7      | 0.52%   |
| FORESEE             | 6         | 8      | 0.52%   |
| Lexar               | 5         | 8      | 0.43%   |
| Gigabyte Technology | 4         | 4      | 0.35%   |
| Unknown             | 3         | 3      | 0.26%   |
| Mushkin             | 3         | 3      | 0.26%   |
| BHT                 | 3         | 5      | 0.26%   |
| ZHITAI              | 2         | 3      | 0.17%   |
| Verbatim            | 2         | 2      | 0.17%   |
| TO Exter            | 2         | 3      | 0.17%   |
| Teclast             | 2         | 2      | 0.17%   |
| Seagate             | 2         | 2      | 0.17%   |
| Netac               | 2         | 2      | 0.17%   |
| Lenovo              | 2         | 2      | 0.17%   |
| HS-SSD-E100         | 2         | 2      | 0.17%   |
| HS-SSD-C100         | 2         | 2      | 0.17%   |
| Hewlett-Packard     | 2         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1393      | 1917   | 39.78%  |
| SSD     | 1059      | 1386   | 30.24%  |
| HDD     | 876       | 1040   | 25.01%  |
| MMC     | 140       | 168    | 4%      |
| Unknown | 34        | 36     | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1641      | 2329   | 49.91%  |
| NVMe | 1389      | 1904   | 42.24%  |
| MMC  | 140       | 168    | 4.26%   |
| SAS  | 118       | 146    | 3.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1148      | 1496   | 59.92%  |
| 0.51-1.0   | 683       | 824    | 35.65%  |
| 1.01-2.0   | 75        | 95     | 3.91%   |
| 4.01-10.0  | 5         | 5      | 0.26%   |
| 3.01-4.0   | 4         | 5      | 0.21%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 795       | 27.08%  |
| 251-500        | 794       | 27.04%  |
| 501-1000       | 563       | 19.18%  |
| 1001-2000      | 317       | 10.8%   |
| 51-100         | 132       | 4.5%    |
| More than 3000 | 90        | 3.07%   |
| 2001-3000      | 76        | 2.59%   |
| Unknown        | 73        | 2.49%   |
| 21-50          | 51        | 1.74%   |
| 1-20           | 45        | 1.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 669       | 21.86%  |
| 101-250        | 594       | 19.41%  |
| 21-50          | 510       | 16.67%  |
| 51-100         | 448       | 14.64%  |
| 251-500        | 401       | 13.1%   |
| 501-1000       | 241       | 7.88%   |
| 1001-2000      | 78        | 2.55%   |
| Unknown        | 73        | 2.39%   |
| 2001-3000      | 25        | 0.82%   |
| More than 3000 | 21        | 0.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                | 9         | 9      | 4.64%   |
| Seagate ST1000LM035-1RK172 1TB          | 8         | 8      | 4.12%   |
| HGST HTS541010A9E680 1TB                | 6         | 6      | 3.09%   |
| HGST HTS545050A7E680 500GB              | 5         | 6      | 2.58%   |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 4         | 4      | 2.06%   |
| HGST HTS725050A7E630 500GB              | 4         | 4      | 2.06%   |
| Seagate ST9500325AS 500GB               | 3         | 3      | 1.55%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 3      | 1.55%   |
| Seagate ST2000LM007-1R8174 2TB          | 3         | 3      | 1.55%   |
| Seagate ST1000LX015-1U7172 1TB          | 3         | 4      | 1.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 3      | 1.55%   |
| Seagate ST1000LM014-SSHD-8GB            | 3         | 3      | 1.55%   |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 2      | 1.03%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 2      | 1.03%   |
| Toshiba MK3276GSX 320GB                 | 2         | 2      | 1.03%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 2      | 1.03%   |
| Seagate ST9250315AS 250GB               | 2         | 2      | 1.03%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 2      | 1.03%   |
| Seagate ST500LM021-1KJ152 500GB         | 2         | 2      | 1.03%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 2      | 1.03%   |
| Seagate ST500LM000-SSHD-8GB             | 2         | 2      | 1.03%   |
| Seagate ST2000LX001-1RG174 2TB          | 2         | 2      | 1.03%   |
| Seagate ST1000LM048-2E7172 1TB          | 2         | 2      | 1.03%   |
| SanDisk SD7SB3Q256G1002 256GB SSD       | 2         | 2      | 1.03%   |
| Samsung Electronics SSD 970 EVO 2TB     | 2         | 2      | 1.03%   |
| LITEON CV8-8E128-HP 128GB SSD           | 2         | 2      | 1.03%   |
| Intel SSDSC2BF240A4L 240GB              | 2         | 2      | 1.03%   |
| Hitachi HTS723232A7A364 320GB           | 2         | 2      | 1.03%   |
| Hitachi HTS545050A7E380 500GB           | 2         | 3      | 1.03%   |
| Hitachi HTS545025B9A300 250GB           | 2         | 2      | 1.03%   |
| Hitachi HTS541680J9SA00 80GB            | 2         | 2      | 1.03%   |
| Hitachi HTS541616J9SA00 160GB           | 2         | 2      | 1.03%   |
| HGST HTS545050A7E380 500GB              | 2         | 2      | 1.03%   |
| WDC WDS100T2B0B-00YS70 1TB SSD          | 1         | 1      | 0.52%   |
| WDC WD7500BPKT-00PK4T0 752GB            | 1         | 1      | 0.52%   |
| WDC WD5000LPVX-80V0TT0 500GB            | 1         | 1      | 0.52%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 1      | 0.52%   |
| WDC WD5000LPCX-00VHAT0 500GB            | 1         | 1      | 0.52%   |
| WDC WD5000BPVT-16HXZT1 500GB            | 1         | 1      | 0.52%   |
| WDC WD5000BEVT-22ZAT0 500GB             | 1         | 1      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 54        | 56     | 27.84%  |
| HGST                | 28        | 29     | 14.43%  |
| WDC                 | 20        | 22     | 10.31%  |
| Toshiba             | 19        | 21     | 9.79%   |
| Hitachi             | 17        | 18     | 8.76%   |
| Samsung Electronics | 11        | 14     | 5.67%   |
| SK hynix            | 9         | 10     | 4.64%   |
| Intel               | 7         | 8      | 3.61%   |
| SanDisk             | 6         | 7      | 3.09%   |
| Kingston            | 5         | 5      | 2.58%   |
| Crucial             | 5         | 5      | 2.58%   |
| Micron Technology   | 3         | 4      | 1.55%   |
| LITEON              | 3         | 3      | 1.55%   |
| ASMT                | 2         | 2      | 1.03%   |
| OCZ                 | 1         | 1      | 0.52%   |
| KingSpec            | 1         | 1      | 0.52%   |
| China               | 1         | 1      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |
| A-DATA Technology   | 1         | 1      | 0.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 54        | 56     | 40.3%   |
| HGST    | 28        | 29     | 20.9%   |
| WDC     | 19        | 21     | 14.18%  |
| Hitachi | 17        | 18     | 12.69%  |
| Toshiba | 14        | 16     | 10.45%  |
| ASMT    | 1         | 1      | 0.75%   |
| Apple   | 1         | 1      | 0.75%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 133       | 142    | 68.91%  |
| SSD  | 47        | 50     | 24.35%  |
| NVMe | 13        | 17     | 6.74%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZVLW128HEGR-000L2 128GB     | 1         | 2      | 25%     |
| Samsung Electronics MZNLN128HAHQ-000H1 128GB SSD | 1         | 1      | 25%     |
| Phison ESO128GTLC9-E8C-2 128GB                   | 1         | 1      | 25%     |
| Kingston SV300S37A120G 120GB SSD                 | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 50%     |
| Phison              | 1         | 1      | 25%     |
| Kingston            | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1460      | 2179   | 47.5%   |
| Works    | 1420      | 2154   | 46.19%  |
| Malfunc  | 190       | 209    | 6.18%   |
| Failed   | 4         | 5      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1779      | 50.16%  |
| Samsung Electronics              | 511       | 14.41%  |
| AMD                              | 355       | 10.01%  |
| SanDisk                          | 262       | 7.39%   |
| SK hynix                         | 172       | 4.85%   |
| Toshiba America Info Systems     | 88        | 2.48%   |
| Micron Technology                | 76        | 2.14%   |
| Kingston Technology Company      | 64        | 1.8%    |
| Phison Electronics               | 50        | 1.41%   |
| KIOXIA                           | 25        | 0.7%    |
| ADATA Technology                 | 25        | 0.7%    |
| Micron/Crucial Technology        | 24        | 0.68%   |
| Silicon Motion                   | 22        | 0.62%   |
| Union Memory (Shenzhen)          | 16        | 0.45%   |
| Lenovo                           | 14        | 0.39%   |
| Realtek Semiconductor            | 11        | 0.31%   |
| Lite-On Technology               | 10        | 0.28%   |
| Apple                            | 10        | 0.28%   |
| Solid State Storage Technology   | 7         | 0.2%    |
| Yangtze Memory Technologies      | 5         | 0.14%   |
| Nvidia                           | 5         | 0.14%   |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.08%   |
| Biwin Storage Technology         | 3         | 0.08%   |
| Marvell Technology Group         | 2         | 0.06%   |
| ASMedia Technology               | 2         | 0.06%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Netac Technology                 | 1         | 0.03%   |
| INNOGRIT                         | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 336       | 9.16%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 304       | 8.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 266       | 7.25%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 169       | 4.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 159       | 4.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 143       | 3.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 114       | 3.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 112       | 3.05%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 99        | 2.7%    |
| Samsung NVMe SSD Controller 980                                                | 98        | 2.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 95        | 2.59%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 84        | 2.29%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 83        | 2.26%   |
| Micron Non-Volatile memory controller                                          | 76        | 2.07%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 68        | 1.85%   |
| Intel SSD 660P Series                                                          | 59        | 1.61%   |
| Intel Volume Management Device NVMe RAID Controller                            | 57        | 1.55%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 55        | 1.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 54        | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 51        | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 47        | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 44        | 1.2%    |
| SanDisk Non-Volatile memory controller                                         | 38        | 1.04%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 38        | 1.04%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 36        | 0.98%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 36        | 0.98%   |
| SK hynix Non-Volatile memory controller                                        | 34        | 0.93%   |
| Phison E12 NVMe Controller                                                     | 33        | 0.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 30        | 0.82%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 30        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 27        | 0.74%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 27        | 0.74%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 25        | 0.68%   |
| Intel Tiger Lake-LP SATA Controller                                            | 23        | 0.63%   |
| Intel Comet Lake SATA AHCI Controller                                          | 23        | 0.63%   |
| SK hynix BC511                                                                 | 22        | 0.6%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 22        | 0.6%    |
| Kingston Company Company Non-Volatile memory controller                        | 21        | 0.57%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 19        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1865      | 52.89%  |
| NVMe | 1393      | 39.51%  |
| RAID | 221       | 6.27%   |
| IDE  | 47        | 1.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2220      | 78.61%  |
| AMD    | 604       | 21.39%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 72        | 2.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 69        | 2.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 68        | 2.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 63        | 2.23%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 62        | 2.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 60        | 2.12%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 60        | 2.12%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 53        | 1.88%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 45        | 1.59%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 45        | 1.59%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 43        | 1.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 42        | 1.49%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 42        | 1.49%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 38        | 1.34%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 36        | 1.27%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 35        | 1.24%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 35        | 1.24%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 33        | 1.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 31        | 1.1%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 1.1%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 30        | 1.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 28        | 0.99%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 27        | 0.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 26        | 0.92%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 26        | 0.92%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 25        | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 25        | 0.88%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 23        | 0.81%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 22        | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 0.78%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 22        | 0.78%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 21        | 0.74%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 21        | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 21        | 0.74%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 20        | 0.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 19        | 0.67%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 19        | 0.67%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 18        | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 17        | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 17        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 833       | 29.48%  |
| Intel Core i5           | 729       | 25.8%   |
| Other                   | 198       | 7.01%   |
| AMD Ryzen 5             | 193       | 6.83%   |
| AMD Ryzen 7             | 187       | 6.62%   |
| Intel Core i3           | 164       | 5.8%    |
| Intel Celeron           | 77        | 2.72%   |
| Intel Core 2 Duo        | 73        | 2.58%   |
| AMD Ryzen 7 PRO         | 55        | 1.95%   |
| Intel Pentium           | 46        | 1.63%   |
| AMD Ryzen 9             | 38        | 1.34%   |
| Intel Atom              | 30        | 1.06%   |
| Intel Core i9           | 26        | 0.92%   |
| AMD Ryzen 3             | 26        | 0.92%   |
| AMD Ryzen 5 PRO         | 16        | 0.57%   |
| AMD A6                  | 14        | 0.5%    |
| Intel Xeon              | 12        | 0.42%   |
| Intel Pentium Silver    | 11        | 0.39%   |
| AMD A4                  | 11        | 0.39%   |
| AMD A10                 | 11        | 0.39%   |
| AMD A8                  | 8         | 0.28%   |
| AMD E2                  | 7         | 0.25%   |
| Intel Pentium Dual-Core | 6         | 0.21%   |
| Intel Genuine           | 5         | 0.18%   |
| Intel Core m3           | 5         | 0.18%   |
| AMD E                   | 5         | 0.18%   |
| Intel Core 2            | 4         | 0.14%   |
| AMD E1                  | 4         | 0.14%   |
| AMD Athlon              | 3         | 0.11%   |
| AMD A12                 | 3         | 0.11%   |
| Intel Pentium Dual      | 2         | 0.07%   |
| Intel Core m7           | 2         | 0.07%   |
| Intel Core m5           | 2         | 0.07%   |
| Intel Core M            | 2         | 0.07%   |
| Intel Celeron Dual-Core | 2         | 0.07%   |
| AMD Turion Neo X2       | 2         | 0.07%   |
| AMD Phenom II           | 2         | 0.07%   |
| AMD Athlon X2           | 2         | 0.07%   |
| Intel Core 2 Solo       | 1         | 0.04%   |
| Intel Celeron M         | 1         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 1102      | 39%     |
| 2      | 1075      | 38.04%  |
| 8      | 308       | 10.9%   |
| 6      | 301       | 10.65%  |
| 1      | 17        | 0.6%    |
| 12     | 10        | 0.35%   |
| 14     | 9         | 0.32%   |
| 10     | 2         | 0.07%   |
| 5      | 1         | 0.04%   |
| 3      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2824      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2407      | 85.11%  |
| 1      | 421       | 14.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2763      | 97.77%  |
| Unknown        | 60        | 2.12%   |
| 32-bit         | 3         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 840       | 28.66%  |
| 0x906ea    | 133       | 4.54%   |
| 0x806ea    | 127       | 4.33%   |
| 0x306a9    | 115       | 3.92%   |
| 0x806ec    | 107       | 3.65%   |
| 0x206a7    | 99        | 3.38%   |
| 0x406e3    | 98        | 3.34%   |
| 0x806c1    | 92        | 3.14%   |
| 0x306d4    | 87        | 2.97%   |
| 0x40651    | 82        | 2.8%    |
| 0x906e9    | 80        | 2.73%   |
| 0x806e9    | 72        | 2.46%   |
| 0x08108102 | 69        | 2.35%   |
| 0x306c3    | 64        | 2.18%   |
| 0x0a50000c | 64        | 2.18%   |
| 0x08600106 | 60        | 2.05%   |
| 0xa0652    | 54        | 1.84%   |
| 0x20655    | 46        | 1.57%   |
| 0x506e3    | 43        | 1.47%   |
| 0x08108109 | 42        | 1.43%   |
| 0x08600104 | 39        | 1.33%   |
| 0x806eb    | 38        | 1.3%    |
| 0x08600103 | 38        | 1.3%    |
| 0x1067a    | 32        | 1.09%   |
| 0x08608103 | 24        | 0.82%   |
| 0x0810100b | 24        | 0.82%   |
| 0x706e5    | 22        | 0.75%   |
| 0x406c4    | 20        | 0.68%   |
| 0x806d1    | 19        | 0.65%   |
| 0x10676    | 19        | 0.65%   |
| 0x906ed    | 17        | 0.58%   |
| 0x706a1    | 16        | 0.55%   |
| 0x30678    | 16        | 0.55%   |
| 0x08608102 | 16        | 0.55%   |
| 0x506c9    | 14        | 0.48%   |
| 0x20652    | 12        | 0.41%   |
| 0x06006705 | 11        | 0.38%   |
| 0x906a3    | 9         | 0.31%   |
| 0x406c3    | 9         | 0.31%   |
| 0x106ca    | 9         | 0.31%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 794       | 28.11%  |
| Haswell          | 201       | 7.12%   |
| Skylake          | 198       | 7.01%   |
| Zen 2            | 170       | 6.02%   |
| IvyBridge        | 169       | 5.98%   |
| TigerLake        | 138       | 4.88%   |
| SandyBridge      | 138       | 4.88%   |
| Zen+             | 134       | 4.74%   |
| Broadwell        | 114       | 4.04%   |
| Unknown          | 104       | 3.68%   |
| Zen 3            | 95        | 3.36%   |
| CometLake        | 88        | 3.12%   |
| Penryn           | 75        | 2.65%   |
| Westmere         | 68        | 2.41%   |
| Silvermont       | 61        | 2.16%   |
| IceLake          | 48        | 1.7%    |
| Zen              | 46        | 1.63%   |
| Goldmont plus    | 30        | 1.06%   |
| Excavator        | 29        | 1.03%   |
| Core             | 19        | 0.67%   |
| Goldmont         | 17        | 0.6%    |
| Bonnell          | 13        | 0.46%   |
| Bobcat           | 11        | 0.39%   |
| Puma             | 9         | 0.32%   |
| Alderlake Hybrid | 9         | 0.32%   |
| Nehalem          | 8         | 0.28%   |
| K10 Llano        | 7         | 0.25%   |
| Piledriver       | 6         | 0.21%   |
| K10              | 6         | 0.21%   |
| Jaguar           | 6         | 0.21%   |
| Tremont          | 4         | 0.14%   |
| Steamroller      | 3         | 0.11%   |
| K8 Hammer        | 3         | 0.11%   |
| P6               | 2         | 0.07%   |
| K8 & K10 hybrid  | 2         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2069      | 54.05%  |
| Nvidia                           | 996       | 26.02%  |
| AMD                              | 759       | 19.83%  |
| Silicon Integrated Systems [SiS] | 3         | 0.08%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 184       | 4.73%   |
| Intel UHD Graphics 620                                                                   | 176       | 4.52%   |
| AMD Renoir                                                                               | 162       | 4.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 161       | 4.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 136       | 3.5%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 133       | 3.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 126       | 3.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 123       | 3.16%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 113       | 2.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 108       | 2.78%   |
| Intel HD Graphics 620                                                                    | 100       | 2.57%   |
| Intel HD Graphics 5500                                                                   | 95        | 2.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 90        | 2.31%   |
| Intel HD Graphics 630                                                                    | 87        | 2.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 85        | 2.19%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 76        | 1.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 67        | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 66        | 1.7%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 61        | 1.57%   |
| AMD Lucienne                                                                             | 56        | 1.44%   |
| Intel HD Graphics 530                                                                    | 52        | 1.34%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 50        | 1.29%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 47        | 1.21%   |
| Intel Core Processor Integrated Graphics Controller                                      | 47        | 1.21%   |
| Nvidia GP108M [GeForce MX150]                                                            | 41        | 1.05%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 40        | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 38        | 0.98%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 34        | 0.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 34        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 34        | 0.87%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 33        | 0.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 29        | 0.75%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 27        | 0.69%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 27        | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 0.69%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 26        | 0.67%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 26        | 0.67%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 24        | 0.62%   |
| Nvidia TU117M                                                                            | 23        | 0.59%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 22        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1184      | 41.78%  |
| Intel + Nvidia           | 759       | 26.78%  |
| 1 x AMD                  | 474       | 16.73%  |
| 1 x Nvidia               | 121       | 4.27%   |
| Intel + AMD              | 119       | 4.2%    |
| AMD + Nvidia             | 115       | 4.06%   |
| 2 x AMD                  | 50        | 1.76%   |
| Other                    | 3         | 0.11%   |
| 1 x SiS                  | 3         | 0.11%   |
| Intel + 2 x Nvidia       | 2         | 0.07%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.07%   |
| 2 x Nvidia               | 1         | 0.04%   |
| 2 x Intel                | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2236      | 78.54%  |
| Proprietary | 603       | 21.18%  |
| Unknown     | 8         | 0.28%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1944      | 67.03%  |
| 0.01-0.5   | 289       | 9.97%   |
| 1.01-2.0   | 266       | 9.17%   |
| 3.01-4.0   | 154       | 5.31%   |
| 0.51-1.0   | 117       | 4.03%   |
| 7.01-8.0   | 56        | 1.93%   |
| 5.01-6.0   | 56        | 1.93%   |
| 2.01-3.0   | 11        | 0.38%   |
| 8.01-16.0  | 7         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 683       | 19.73%  |
| BOE                     | 488       | 14.1%   |
| LG Display              | 456       | 13.17%  |
| Chimei Innolux          | 452       | 13.06%  |
| Samsung Electronics     | 291       | 8.41%   |
| Sharp                   | 151       | 4.36%   |
| Dell                    | 124       | 3.58%   |
| PANDA                   | 86        | 2.48%   |
| Goldstar                | 83        | 2.4%    |
| Lenovo                  | 75        | 2.17%   |
| Apple                   | 59        | 1.7%    |
| Hewlett-Packard         | 51        | 1.47%   |
| Acer                    | 40        | 1.16%   |
| BenQ                    | 35        | 1.01%   |
| InfoVision              | 34        | 0.98%   |
| AOC                     | 34        | 0.98%   |
| Philips                 | 31        | 0.9%    |
| CSO                     | 27        | 0.78%   |
| Ancor Communications    | 27        | 0.78%   |
| Chi Mei Optoelectronics | 26        | 0.75%   |
| Iiyama                  | 21        | 0.61%   |
| Sony                    | 13        | 0.38%   |
| ViewSonic               | 11        | 0.32%   |
| ASUSTek Computer        | 11        | 0.32%   |
| CPT                     | 8         | 0.23%   |
| TMX                     | 7         | 0.2%    |
| NEC Computers           | 7         | 0.2%    |
| JDI                     | 7         | 0.2%    |
| Toshiba                 | 6         | 0.17%   |
| Panasonic               | 6         | 0.17%   |
| MSI                     | 6         | 0.17%   |
| Pixio                   | 5         | 0.14%   |
| LG Philips              | 5         | 0.14%   |
| InnoLux Display         | 5         | 0.14%   |
| Eizo                    | 5         | 0.14%   |
| LGD                     | 4         | 0.12%   |
| HannStar                | 4         | 0.12%   |
| Fujitsu Siemens         | 4         | 0.12%   |
| Vizio                   | 3         | 0.09%   |
| ITE                     | 3         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 40        | 1.14%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 36        | 1.03%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 28        | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 28        | 0.8%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 23        | 0.66%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 22        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 22        | 0.63%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 17        | 0.49%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 17        | 0.49%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 15        | 0.43%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 14        | 0.4%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 14        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 14        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 14        | 0.4%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 14        | 0.4%    |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 13        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 13        | 0.37%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 13        | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 12        | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 12        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 12        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 12        | 0.34%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 11        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 11        | 0.31%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 11        | 0.31%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 11        | 0.31%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch         | 11        | 0.31%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 11        | 0.31%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 10        | 0.29%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 10        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch       | 10        | 0.29%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 10        | 0.29%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 10        | 0.29%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch         | 10        | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 9         | 0.26%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 9         | 0.26%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 9         | 0.26%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch          | 9         | 0.26%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 9         | 0.26%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 9         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1675      | 52.28%  |
| 1366x768 (WXGA)    | 641       | 20.01%  |
| 3840x2160 (4K)     | 170       | 5.31%   |
| 2560x1440 (QHD)    | 130       | 4.06%   |
| 1600x900 (HD+)     | 122       | 3.81%   |
| 1920x1200 (WUXGA)  | 62        | 1.94%   |
| 1280x800 (WXGA)    | 51        | 1.59%   |
| 2560x1600          | 37        | 1.15%   |
| 1440x900 (WXGA+)   | 37        | 1.15%   |
| 1680x1050 (WSXGA+) | 31        | 0.97%   |
| 2880x1800          | 29        | 0.91%   |
| 3440x1440          | 24        | 0.75%   |
| 3840x2400          | 21        | 0.66%   |
| 2560x1080          | 20        | 0.62%   |
| 3200x1800 (QHD+)   | 18        | 0.56%   |
| 2256x1504          | 17        | 0.53%   |
| 1280x1024 (SXGA)   | 16        | 0.5%    |
| 2160x1440          | 12        | 0.37%   |
| 1360x768           | 12        | 0.37%   |
| 3072x1920          | 7         | 0.22%   |
| 3000x2000          | 7         | 0.22%   |
| 3840x1600          | 6         | 0.19%   |
| 1024x600           | 6         | 0.19%   |
| Unknown            | 6         | 0.19%   |
| 2240x1400          | 5         | 0.16%   |
| 1280x720 (HD)      | 5         | 0.16%   |
| 3840x1080          | 3         | 0.09%   |
| 2520x1680          | 3         | 0.09%   |
| 1920x540           | 3         | 0.09%   |
| 1680x945           | 3         | 0.09%   |
| 3456x2160          | 2         | 0.06%   |
| 3200x2000          | 2         | 0.06%   |
| 1920x1280          | 2         | 0.06%   |
| 1600x1200          | 2         | 0.06%   |
| 800x1280           | 1         | 0.03%   |
| 7680x1440          | 1         | 0.03%   |
| 5520x1080          | 1         | 0.03%   |
| 4480x1440          | 1         | 0.03%   |
| 3840x1100          | 1         | 0.03%   |
| 3286x1080          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1346      | 38.9%   |
| 13      | 554       | 16.01%  |
| 14      | 477       | 13.79%  |
| 17      | 170       | 4.91%   |
| 27      | 167       | 4.83%   |
| 24      | 144       | 4.16%   |
| 23      | 110       | 3.18%   |
| 12      | 92        | 2.66%   |
| 21      | 65        | 1.88%   |
| 34      | 41        | 1.18%   |
| Unknown | 41        | 1.18%   |
| 11      | 39        | 1.13%   |
| 16      | 38        | 1.1%    |
| 18      | 27        | 0.78%   |
| 31      | 24        | 0.69%   |
| 19      | 20        | 0.58%   |
| 20      | 14        | 0.4%    |
| 22      | 13        | 0.38%   |
| 10      | 11        | 0.32%   |
| 84      | 8         | 0.23%   |
| 72      | 8         | 0.23%   |
| 54      | 5         | 0.14%   |
| 37      | 5         | 0.14%   |
| 29      | 5         | 0.14%   |
| 28      | 5         | 0.14%   |
| 25      | 5         | 0.14%   |
| 48      | 4         | 0.12%   |
| 40      | 3         | 0.09%   |
| 26      | 3         | 0.09%   |
| 42      | 2         | 0.06%   |
| 32      | 2         | 0.06%   |
| 74      | 1         | 0.03%   |
| 65      | 1         | 0.03%   |
| 55      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 50      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 46      | 1         | 0.03%   |
| 43      | 1         | 0.03%   |
| 38      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 2089      | 61.1%   |
| 201-300     | 422       | 12.34%  |
| 501-600     | 384       | 11.23%  |
| 351-400     | 213       | 6.23%   |
| 401-500     | 127       | 3.71%   |
| 601-700     | 53        | 1.55%   |
| 701-800     | 43        | 1.26%   |
| Unknown     | 41        | 1.2%    |
| 1501-2000   | 17        | 0.5%    |
| 1001-1500   | 15        | 0.44%   |
| 801-900     | 10        | 0.29%   |
| 901-1000    | 3         | 0.09%   |
| 101-200     | 2         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2530      | 84.87%  |
| 16/10   | 284       | 9.53%   |
| 3/2     | 51        | 1.71%   |
| 21/9    | 49        | 1.64%   |
| Unknown | 27        | 0.91%   |
| 5/4     | 19        | 0.64%   |
| 4/3     | 9         | 0.3%    |
| 32/9    | 5         | 0.17%   |
| 2.65    | 4         | 0.13%   |
| 3.40    | 1         | 0.03%   |
| 1.03    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1349      | 39.16%  |
| 81-90          | 801       | 23.25%  |
| 201-250        | 277       | 8.04%   |
| 71-80          | 223       | 6.47%   |
| 301-350        | 169       | 4.91%   |
| 121-130        | 145       | 4.21%   |
| 61-70          | 89        | 2.58%   |
| 351-500        | 69        | 2%      |
| 251-300        | 51        | 1.48%   |
| 151-200        | 44        | 1.28%   |
| Unknown        | 41        | 1.19%   |
| 51-60          | 40        | 1.16%   |
| 141-150        | 30        | 0.87%   |
| More than 1000 | 27        | 0.78%   |
| 111-120        | 27        | 0.78%   |
| 501-1000       | 18        | 0.52%   |
| 131-140        | 16        | 0.46%   |
| 91-100         | 16        | 0.46%   |
| 41-50          | 12        | 0.35%   |
| 1-40           | 1         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1602      | 47.4%   |
| 101-120       | 728       | 21.54%  |
| 51-100        | 492       | 14.56%  |
| 161-240       | 329       | 9.73%   |
| More than 240 | 157       | 4.64%   |
| Unknown       | 41        | 1.21%   |
| 1-50          | 31        | 0.92%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2243      | 77.67%  |
| 2     | 561       | 19.43%  |
| 3     | 69        | 2.39%   |
| 0     | 10        | 0.35%   |
| 4     | 5         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1739      | 38.97%  |
| Realtek Semiconductor             | 1486      | 33.3%   |
| Qualcomm Atheros                  | 574       | 12.86%  |
| Broadcom                          | 178       | 3.99%   |
| MediaTek                          | 78        | 1.75%   |
| Broadcom Limited                  | 44        | 0.99%   |
| Lenovo                            | 34        | 0.76%   |
| TP-Link                           | 27        | 0.61%   |
| Ericsson Business Mobile Networks | 25        | 0.56%   |
| ASIX Electronics                  | 25        | 0.56%   |
| Sierra Wireless                   | 23        | 0.52%   |
| Qualcomm                          | 21        | 0.47%   |
| Marvell Technology Group          | 21        | 0.47%   |
| Ralink                            | 17        | 0.38%   |
| Ralink Technology                 | 16        | 0.36%   |
| DisplayLink                       | 15        | 0.34%   |
| Hewlett-Packard                   | 14        | 0.31%   |
| Dell                              | 13        | 0.29%   |
| Samsung Electronics               | 11        | 0.25%   |
| Apple                             | 11        | 0.25%   |
| Xiaomi                            | 10        | 0.22%   |
| Huawei Technologies               | 8         | 0.18%   |
| D-Link                            | 7         | 0.16%   |
| Cypress Semiconductor             | 7         | 0.16%   |
| NetGear                           | 6         | 0.13%   |
| Google                            | 6         | 0.13%   |
| Linksys                           | 5         | 0.11%   |
| JMicron Technology                | 5         | 0.11%   |
| Nvidia                            | 4         | 0.09%   |
| Fibocom                           | 4         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.07%   |
| Qualcomm Atheros Communications   | 3         | 0.07%   |
| Motorola PCS                      | 3         | 0.07%   |
| Microsoft                         | 3         | 0.07%   |
| Arduino SA                        | 3         | 0.07%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.04%   |
| ASUSTek Computer                  | 2         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.02%   |
| U-Blox                            | 1         | 0.02%   |
| SEGGER                            | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1006      | 18.84%  |
| Intel Wi-Fi 6 AX200                                               | 264       | 4.94%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 187       | 3.5%    |
| Intel Wireless 8265 / 8275                                        | 175       | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 125       | 2.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 124       | 2.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 115       | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 113       | 2.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 108       | 2.02%   |
| Intel Wireless 7265                                               | 100       | 1.87%   |
| Intel Wi-Fi 6 AX201                                               | 96        | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 91        | 1.7%    |
| Intel Wireless 8260                                               | 88        | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 81        | 1.52%   |
| Intel Wireless 7260                                               | 81        | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 78        | 1.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 73        | 1.37%   |
| Intel Wireless 3165                                               | 71        | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 71        | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 64        | 1.2%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 64        | 1.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 61        | 1.14%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 58        | 1.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 56        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 52        | 0.97%   |
| Intel Wireless-AC 9260                                            | 45        | 0.84%   |
| Intel Ethernet Connection (4) I219-V                              | 45        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                             | 44        | 0.82%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 43        | 0.81%   |
| Intel Wireless 3160                                               | 38        | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 38        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 37        | 0.69%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 35        | 0.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 34        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 33        | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 32        | 0.6%    |
| Intel Ethernet Connection I219-LM                                 | 29        | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 0.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 27        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1674      | 57.27%  |
| Qualcomm Atheros                | 482       | 16.49%  |
| Realtek Semiconductor           | 368       | 12.59%  |
| Broadcom                        | 152       | 5.2%    |
| MediaTek                        | 75        | 2.57%   |
| Broadcom Limited                | 34        | 1.16%   |
| Sierra Wireless                 | 23        | 0.79%   |
| TP-Link                         | 20        | 0.68%   |
| Qualcomm                        | 18        | 0.62%   |
| Ralink                          | 17        | 0.58%   |
| Ralink Technology               | 16        | 0.55%   |
| Hewlett-Packard                 | 8         | 0.27%   |
| Dell                            | 6         | 0.21%   |
| NetGear                         | 5         | 0.17%   |
| Linksys                         | 5         | 0.17%   |
| D-Link                          | 5         | 0.17%   |
| Fibocom                         | 4         | 0.14%   |
| Qualcomm Atheros Communications | 3         | 0.1%    |
| Xiaomi                          | 2         | 0.07%   |
| ASUSTek Computer                | 2         | 0.07%   |
| Quectel Wireless Solutions      | 1         | 0.03%   |
| Microsoft                       | 1         | 0.03%   |
| Marvell Technology Group        | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 264       | 9%      |
| Intel Wireless 8265 / 8275                                     | 175       | 5.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 125       | 4.26%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 115       | 3.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 108       | 3.68%   |
| Intel Wireless 7265                                            | 100       | 3.41%   |
| Intel Wi-Fi 6 AX201                                            | 96        | 3.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 91        | 3.1%    |
| Intel Wireless 8260                                            | 88        | 3%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 81        | 2.76%   |
| Intel Wireless 7260                                            | 81        | 2.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 78        | 2.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 73        | 2.49%   |
| Intel Wireless 3165                                            | 71        | 2.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 71        | 2.42%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 64        | 2.18%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 64        | 2.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 61        | 2.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 58        | 1.98%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 56        | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 52        | 1.77%   |
| Intel Wireless-AC 9260                                         | 45        | 1.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 43        | 1.47%   |
| Intel Wireless 3160                                            | 38        | 1.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 37        | 1.26%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 35        | 1.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 34        | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 32        | 1.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 27        | 0.92%   |
| Intel Centrino Ultimate-N 6300                                 | 24        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 23        | 0.78%   |
| Intel Centrino Advanced-N 6235                                 | 22        | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                  | 22        | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 19        | 0.65%   |
| Intel Centrino Advanced-N 6200                                 | 19        | 0.65%   |
| Intel Centrino Wireless-N 2230                                 | 17        | 0.58%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 17        | 0.58%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 16        | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 15        | 0.51%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 15        | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1338      | 57.65%  |
| Intel                            | 606       | 26.11%  |
| Qualcomm Atheros                 | 139       | 5.99%   |
| Broadcom                         | 47        | 2.02%   |
| Lenovo                           | 34        | 1.46%   |
| ASIX Electronics                 | 25        | 1.08%   |
| Marvell Technology Group         | 20        | 0.86%   |
| DisplayLink                      | 15        | 0.65%   |
| Samsung Electronics              | 11        | 0.47%   |
| Apple                            | 11        | 0.47%   |
| Broadcom Limited                 | 10        | 0.43%   |
| Xiaomi                           | 8         | 0.34%   |
| TP-Link                          | 7         | 0.3%    |
| Cypress Semiconductor            | 7         | 0.3%    |
| Google                           | 6         | 0.26%   |
| JMicron Technology               | 5         | 0.22%   |
| Nvidia                           | 4         | 0.17%   |
| Huawei Technologies              | 4         | 0.17%   |
| Silicon Integrated Systems [SiS] | 3         | 0.13%   |
| Qualcomm                         | 3         | 0.13%   |
| Motorola PCS                     | 3         | 0.13%   |
| MediaTek                         | 3         | 0.13%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.09%   |
| Microsoft                        | 2         | 0.09%   |
| D-Link                           | 2         | 0.09%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.04%   |
| QNAP System                      | 1         | 0.04%   |
| NetGear                          | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1006      | 42.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 187       | 7.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 124       | 5.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 113       | 4.79%   |
| Intel Ethernet Connection (4) I219-V                              | 45        | 1.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 44        | 1.87%   |
| Intel Ethernet Connection (6) I219-V                              | 38        | 1.61%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 1.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 33        | 1.4%    |
| Intel Ethernet Connection I219-LM                                 | 29        | 1.23%   |
| Intel Ethernet Connection I218-LM                                 | 29        | 1.23%   |
| Intel 82577LM Gigabit Network Connection                          | 27        | 1.14%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 1.02%   |
| Intel 82567LM Gigabit Network Connection                          | 24        | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 22        | 0.93%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 21        | 0.89%   |
| Intel Ethernet Connection (6) I219-LM                             | 21        | 0.89%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 20        | 0.85%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 0.76%   |
| Intel Ethernet Connection (10) I219-V                             | 16        | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.64%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 0.42%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.38%   |
| Lenovo USB-C Dock Ethernet                                        | 9         | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.34%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.34%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 8         | 0.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 0.34%   |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.34%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 8         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2803      | 55.45%  |
| Ethernet | 2203      | 43.58%  |
| Modem    | 46        | 0.91%   |
| Unknown  | 3         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2379      | 78.98%  |
| Ethernet | 632       | 20.98%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2013      | 71.18%  |
| 1     | 754       | 26.66%  |
| 3     | 35        | 1.24%   |
| 0     | 25        | 0.88%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2434      | 85.08%  |
| Yes  | 427       | 14.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1381      | 56.67%  |
| Realtek Semiconductor           | 223       | 9.15%   |
| Qualcomm Atheros Communications | 207       | 8.49%   |
| IMC Networks                    | 114       | 4.68%   |
| Broadcom                        | 114       | 4.68%   |
| Lite-On Technology              | 109       | 4.47%   |
| Foxconn / Hon Hai               | 82        | 3.36%   |
| Apple                           | 44        | 1.81%   |
| Realtek                         | 31        | 1.27%   |
| Dell                            | 31        | 1.27%   |
| Cambridge Silicon Radio         | 23        | 0.94%   |
| Hewlett-Packard                 | 15        | 0.62%   |
| Toshiba                         | 9         | 0.37%   |
| Ralink                          | 9         | 0.37%   |
| MediaTek                        | 9         | 0.37%   |
| Foxconn International           | 6         | 0.25%   |
| USI                             | 5         | 0.21%   |
| ASUSTek Computer                | 5         | 0.21%   |
| Chicony Electronics             | 3         | 0.12%   |
| Askey Computer                  | 3         | 0.12%   |
| TP-Link                         | 2         | 0.08%   |
| Ralink Technology               | 2         | 0.08%   |
| Alps Electric                   | 2         | 0.08%   |
| Unknown                         | 1         | 0.04%   |
| Syntek                          | 1         | 0.04%   |
| Opticis                         | 1         | 0.04%   |
| Micro Star International        | 1         | 0.04%   |
| Marvell Semiconductor           | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Dynex                           | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 529       | 21.66%  |
| Intel AX200 Bluetooth                               | 247       | 10.11%  |
| Intel AX201 Bluetooth                               | 207       | 8.48%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 205       | 8.39%   |
| Realtek Bluetooth Radio                             | 145       | 5.94%   |
| Qualcomm Atheros  Bluetooth Device                  | 111       | 4.55%   |
| Intel AX210 Bluetooth                               | 64        | 2.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 54        | 2.21%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 41        | 1.68%   |
| Lite-On Bluetooth Device                            | 39        | 1.6%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 39        | 1.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 39        | 1.6%    |
| Foxconn / Hon Hai Bluetooth Device                  | 38        | 1.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 37        | 1.52%   |
| IMC Networks Bluetooth Radio                        | 37        | 1.52%   |
| Intel Wireless-AC 3168 Bluetooth                    | 33        | 1.35%   |
| Realtek Bluetooth Radio                             | 31        | 1.27%   |
| IMC Networks Wireless_Device                        | 30        | 1.23%   |
| IMC Networks Bluetooth Device                       | 30        | 1.23%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 29        | 1.19%   |
| Apple Bluetooth Host Controller                     | 25        | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 23        | 0.94%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 23        | 0.94%   |
| Foxconn / Hon Hai Wireless_Device                   | 22        | 0.9%    |
| Broadcom BCM2045B (BDC-2.1)                         | 22        | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 17        | 0.7%    |
| Intel Bluetooth Device                              | 14        | 0.57%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.53%   |
| Apple Bluetooth USB Host Controller                 | 13        | 0.53%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.49%   |
| Lite-On Wireless_Device                             | 12        | 0.49%   |
| Dell DW375 Bluetooth Module                         | 12        | 0.49%   |
| Realtek RTL8821A Bluetooth                          | 10        | 0.41%   |
| Dell BCM20702A0 Bluetooth Module                    | 10        | 0.41%   |
| Broadcom HP Portable SoftSailing                    | 10        | 0.41%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.37%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.37%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 8         | 0.33%   |
| MediaTek Wireless_Device                            | 8         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2185      | 59.2%   |
| AMD                                          | 659       | 17.85%  |
| Nvidia                                       | 530       | 14.36%  |
| C-Media Electronics                          | 37        | 1%      |
| Lenovo                                       | 32        | 0.87%   |
| Realtek Semiconductor                        | 27        | 0.73%   |
| Texas Instruments                            | 17        | 0.46%   |
| Logitech                                     | 17        | 0.46%   |
| JMTek                                        | 17        | 0.46%   |
| Focusrite-Novation                           | 15        | 0.41%   |
| Apple                                        | 14        | 0.38%   |
| Kingston Technology                          | 11        | 0.3%    |
| GN Netcom                                    | 10        | 0.27%   |
| Razer USA                                    | 9         | 0.24%   |
| SteelSeries ApS                              | 8         | 0.22%   |
| Plantronics                                  | 6         | 0.16%   |
| Creative Technology                          | 6         | 0.16%   |
| Sennheiser Communications                    | 4         | 0.11%   |
| Samson Technologies                          | 4         | 0.11%   |
| Hewlett-Packard                              | 4         | 0.11%   |
| Generalplus Technology                       | 4         | 0.11%   |
| Silicon Integrated Systems [SiS]             | 3         | 0.08%   |
| XMOS                                         | 2         | 0.05%   |
| Valve Software                               | 2         | 0.05%   |
| Schiit Audio                                 | 2         | 0.05%   |
| SAVITECH                                     | 2         | 0.05%   |
| No brand                                     | 2         | 0.05%   |
| Native Instruments                           | 2         | 0.05%   |
| Mackie Designs                               | 2         | 0.05%   |
| GYROCOM C&C                                  | 2         | 0.05%   |
| Corsair                                      | 2         | 0.05%   |
| Barco Display Systems                        | 2         | 0.05%   |
| Audio-Technica                               | 2         | 0.05%   |
| ASUSTek Computer                             | 2         | 0.05%   |
| A4Tech                                       | 2         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| ZOOM                                         | 1         | 0.03%   |
| Yamaha                                       | 1         | 0.03%   |
| WL80                                         | 1         | 0.03%   |
| USB MICROPHONE                               | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 506       | 11.17%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 414       | 9.14%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 254       | 5.6%    |
| Intel Cannon Lake PCH cAVS                                                                        | 197       | 4.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 187       | 4.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 163       | 3.6%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 139       | 3.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 138       | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 119       | 2.63%   |
| Intel Broadwell-U Audio Controller                                                                | 113       | 2.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 109       | 2.41%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 109       | 2.41%   |
| Intel 8 Series HD Audio Controller                                                                | 109       | 2.41%   |
| Intel CM238 HD Audio Controller                                                                   | 102       | 2.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 95        | 2.1%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 83        | 1.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 81        | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 81        | 1.79%   |
| Intel Comet Lake PCH cAVS                                                                         | 81        | 1.79%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 76        | 1.68%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 68        | 1.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 68        | 1.5%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 66        | 1.46%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 56        | 1.24%   |
| AMD FCH Azalia Controller                                                                         | 35        | 0.77%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 34        | 0.75%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 34        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 31        | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 31        | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 30        | 0.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 30        | 0.66%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 29        | 0.64%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 28        | 0.62%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 26        | 0.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 25        | 0.55%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 24        | 0.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 22        | 0.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 22        | 0.49%   |
| Realtek Semiconductor USB Audio                                                                   | 21        | 0.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 20        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 741       | 29.92%  |
| SK hynix            | 562       | 22.69%  |
| Micron Technology   | 320       | 12.92%  |
| Kingston            | 244       | 9.85%   |
| Crucial             | 151       | 6.1%    |
| Unknown             | 90        | 3.63%   |
| Ramaxel Technology  | 68        | 2.75%   |
| A-DATA Technology   | 50        | 2.02%   |
| Corsair             | 44        | 1.78%   |
| Elpida              | 37        | 1.49%   |
| G.Skill             | 17        | 0.69%   |
| Nanya Technology    | 14        | 0.57%   |
| Transcend           | 12        | 0.48%   |
| Team                | 12        | 0.48%   |
| Smart               | 12        | 0.48%   |
| Patriot             | 12        | 0.48%   |
| Unknown (ABCD)      | 10        | 0.4%    |
| Goodram             | 9         | 0.36%   |
| Teikon              | 5         | 0.2%    |
| Smart Brazil        | 5         | 0.2%    |
| PNY                 | 5         | 0.2%    |
| Goldkey             | 5         | 0.2%    |
| AMD                 | 5         | 0.2%    |
| Unknown             | 5         | 0.2%    |
| Apacer              | 4         | 0.16%   |
| V-GeN               | 3         | 0.12%   |
| Avant               | 3         | 0.12%   |
| 48spaces            | 3         | 0.12%   |
| Silicon Power       | 2         | 0.08%   |
| PKI/Kingston        | 2         | 0.08%   |
| Neo Forza           | 2         | 0.08%   |
| High Bridge         | 2         | 0.08%   |
| V-Color             | 1         | 0.04%   |
| Unknown (C509)      | 1         | 0.04%   |
| Unknown (0x0C26)    | 1         | 0.04%   |
| Unknown (07F7)      | 1         | 0.04%   |
| Timetec             | 1         | 0.04%   |
| Spectek             | 1         | 0.04%   |
| SHARETRONIC         | 1         | 0.04%   |
| Sesame              | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 54        | 2.06%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 49        | 1.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 48        | 1.83%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 36        | 1.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 32        | 1.22%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 25        | 0.95%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 23        | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.8%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 0.76%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 20        | 0.76%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 20        | 0.76%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.76%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 19        | 0.72%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 19        | 0.72%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.69%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 18        | 0.69%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.69%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.65%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.65%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.65%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 16        | 0.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.57%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 15        | 0.57%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 15        | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 15        | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 14        | 0.53%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 14        | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.46%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 12        | 0.46%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 12        | 0.46%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 12        | 0.46%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 12        | 0.46%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 12        | 0.46%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16384MB SODIMM DDR4 2667MT/s       | 11        | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1214      | 59.57%  |
| DDR3    | 557       | 27.33%  |
| LPDDR4  | 92        | 4.51%   |
| LPDDR3  | 84        | 4.12%   |
| DDR2    | 33        | 1.62%   |
| SDRAM   | 26        | 1.28%   |
| LPDDR5  | 18        | 0.88%   |
| DDR5    | 9         | 0.44%   |
| Unknown | 3         | 0.15%   |
| DRAM    | 1         | 0.05%   |
| DDR     | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1786      | 87.59%  |
| Row Of Chips | 214       | 10.5%   |
| Chip         | 25        | 1.23%   |
| DIMM         | 7         | 0.34%   |
| Unknown      | 7         | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 977       | 43.87%  |
| 4096  | 598       | 26.85%  |
| 16384 | 382       | 17.15%  |
| 2048  | 171       | 7.68%   |
| 32768 | 71        | 3.19%   |
| 1024  | 28        | 1.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 585       | 26.15%  |
| 3200    | 431       | 19.27%  |
| 1600    | 406       | 18.15%  |
| 2400    | 224       | 10.01%  |
| 2133    | 141       | 6.3%    |
| 1334    | 79        | 3.53%   |
| 1333    | 49        | 2.19%   |
| 4267    | 48        | 2.15%   |
| 3266    | 48        | 2.15%   |
| 1867    | 38        | 1.7%    |
| 1067    | 24        | 1.07%   |
| 667     | 24        | 1.07%   |
| 6400    | 17        | 0.76%   |
| 8400    | 15        | 0.67%   |
| 4199    | 15        | 0.67%   |
| 4266    | 13        | 0.58%   |
| 1066    | 13        | 0.58%   |
| Unknown | 13        | 0.58%   |
| 4800    | 10        | 0.45%   |
| 2048    | 9         | 0.4%    |
| 2933    | 7         | 0.31%   |
| 975     | 7         | 0.31%   |
| 800     | 7         | 0.31%   |
| 1866    | 2         | 0.09%   |
| 533     | 2         | 0.09%   |
| 400     | 2         | 0.09%   |
| 3733    | 1         | 0.04%   |
| 3400    | 1         | 0.04%   |
| 3000    | 1         | 0.04%   |
| 2666    | 1         | 0.04%   |
| 1776    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 1200    | 1         | 0.04%   |
| 200     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 50%     |
| Samsung Electronics | 2         | 12.5%   |
| Prolific Technology | 2         | 12.5%   |
| Seiko Epson         | 1         | 6.25%   |
| Dymo-CoStar         | 1         | 6.25%   |
| Canon               | 1         | 6.25%   |
| Brother Industries  | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port      | 2         | 12.5%   |
| HP DeskJet 2130 series             | 2         | 12.5%   |
| Seiko Epson WF-2530 Series         | 1         | 6.25%   |
| Samsung SCX-3200 Series            | 1         | 6.25%   |
| Samsung M2020 Series               | 1         | 6.25%   |
| HP OfficeJet 5600 (USBHUB)         | 1         | 6.25%   |
| HP LaserJet 1320                   | 1         | 6.25%   |
| HP ENVY 5000 series                | 1         | 6.25%   |
| HP DeskJet 840c                    | 1         | 6.25%   |
| HP DeskJet 4100 series             | 1         | 6.25%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 6.25%   |
| Dymo-CoStar LabelWriter 400        | 1         | 6.25%   |
| Canon PIXMA MG2500 Series          | 1         | 6.25%   |
| Brother HL-1110 series             | 1         | 6.25%   |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 623       | 24.01%  |
| IMC Networks                           | 327       | 12.6%   |
| Acer                                   | 262       | 10.1%   |
| Microdia                               | 239       | 9.21%   |
| Realtek Semiconductor                  | 200       | 7.71%   |
| Quanta                                 | 154       | 5.93%   |
| Sunplus Innovation Technology          | 133       | 5.13%   |
| Cheng Uei Precision Industry (Foxlink) | 95        | 3.66%   |
| Syntek                                 | 78        | 3.01%   |
| Lite-On Technology                     | 77        | 2.97%   |
| Suyin                                  | 48        | 1.85%   |
| Apple                                  | 48        | 1.85%   |
| Logitech                               | 47        | 1.81%   |
| Silicon Motion                         | 37        | 1.43%   |
| Luxvisions Innotech Limited            | 37        | 1.43%   |
| Alcor Micro                            | 29        | 1.12%   |
| Lenovo                                 | 20        | 0.77%   |
| Samsung Electronics                    | 15        | 0.58%   |
| Ricoh                                  | 10        | 0.39%   |
| ALi                                    | 10        | 0.39%   |
| Importek                               | 9         | 0.35%   |
| Primax Electronics                     | 7         | 0.27%   |
| Sonix Technology                       | 6         | 0.23%   |
| Microsoft                              | 6         | 0.23%   |
| Z-Star Microelectronics                | 5         | 0.19%   |
| Unknown                                | 5         | 0.19%   |
| SunplusIT                              | 5         | 0.19%   |
| DJKANA19IDX53W                         | 5         | 0.19%   |
| Google                                 | 4         | 0.15%   |
| ARC International                      | 4         | 0.15%   |
| OmniVision Technologies                | 3         | 0.12%   |
| MacroSilicon                           | 3         | 0.12%   |
| YGTek                                  | 2         | 0.08%   |
| Valve Software                         | 2         | 0.08%   |
| USB Camera                             | 2         | 0.08%   |
| Razer USA                              | 2         | 0.08%   |
| LG Electronics                         | 2         | 0.08%   |
| Intel                                  | 2         | 0.08%   |
| Holitech                               | 2         | 0.08%   |
| DigiTech                               | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 179       | 6.83%   |
| Microdia Integrated_Webcam_HD                                              | 132       | 5.04%   |
| IMC Networks Integrated Camera                                             | 112       | 4.27%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 96        | 3.66%   |
| Acer Integrated Camera                                                     | 84        | 3.2%    |
| Chicony HD Webcam                                                          | 77        | 2.94%   |
| Realtek Integrated_Webcam_HD                                               | 72        | 2.75%   |
| Sunplus Integrated_Webcam_HD                                               | 58        | 2.21%   |
| Syntek Integrated Camera                                                   | 44        | 1.68%   |
| Quanta HD User Facing                                                      | 41        | 1.56%   |
| Lite-On Integrated Camera                                                  | 39        | 1.49%   |
| Acer SunplusIT Integrated Camera                                           | 34        | 1.3%    |
| Acer HD Webcam                                                             | 34        | 1.3%    |
| Chicony Integrated Camera (1280x720@30)                                    | 28        | 1.07%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 27        | 1.03%   |
| Chicony USB2.0 Camera                                                      | 27        | 1.03%   |
| Microdia Integrated Webcam                                                 | 24        | 0.92%   |
| Realtek USB Camera                                                         | 22        | 0.84%   |
| Chicony HP HD Camera                                                       | 22        | 0.84%   |
| Chicony HD User Facing                                                     | 22        | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 22        | 0.84%   |
| Acer Lenovo EasyCamera                                                     | 22        | 0.84%   |
| Chicony HP Wide Vision HD Camera                                           | 20        | 0.76%   |
| Realtek Integrated Webcam                                                  | 19        | 0.72%   |
| IMC Networks ov9734_azurewave_camera                                       | 19        | 0.72%   |
| Chicony EasyCamera                                                         | 19        | 0.72%   |
| Syntek Lenovo EasyCamera                                                   | 18        | 0.69%   |
| Sunplus HD WebCam                                                          | 17        | 0.65%   |
| Quanta VGA WebCam                                                          | 17        | 0.65%   |
| Quanta HD Webcam                                                           | 17        | 0.65%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 17        | 0.65%   |
| Lite-On HP HD Camera                                                       | 17        | 0.65%   |
| Chicony ThinkPad T490 Webcam                                               | 17        | 0.65%   |
| Quanta HP TrueVision HD Camera                                             | 16        | 0.61%   |
| Microdia Integrated Webcam HD                                              | 16        | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                                               | 16        | 0.61%   |
| Chicony HP TrueVision HD                                                   | 16        | 0.61%   |
| Acer BisonCam, NB Pro                                                      | 16        | 0.61%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 15        | 0.57%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 15        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 210       | 34.48%  |
| Validity Sensors                   | 167       | 27.42%  |
| Shenzhen Goodix Technology         | 112       | 18.39%  |
| Elan Microelectronics              | 36        | 5.91%   |
| Upek                               | 26        | 4.27%   |
| LighTuning Technology              | 25        | 4.11%   |
| AuthenTec                          | 20        | 3.28%   |
| STMicroelectronics                 | 8         | 1.31%   |
| Samsung Electronics                | 2         | 0.33%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.33%   |
| Focal-systems.Corp                 | 1         | 0.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 98        | 16.09%  |
| Shenzhen Goodix  FingerPrint Device                                        | 64        | 10.51%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 42        | 6.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 33        | 5.42%   |
| Elan ELAN:Fingerprint                                                      | 26        | 4.27%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 4.11%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 24        | 3.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 24        | 3.94%   |
| Shenzhen Goodix FingerPrint                                                | 24        | 3.94%   |
| Unknown                                                                    | 23        | 3.78%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 22        | 3.61%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 16        | 2.63%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 16        | 2.63%   |
| Validity Sensors Synaptics WBDI                                            | 15        | 2.46%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 15        | 2.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 2.3%    |
| Validity Sensors VFS491                                                    | 13        | 2.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 12        | 1.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 1.81%   |
| AuthenTec AES2810                                                          | 11        | 1.81%   |
| Elan ELAN:ARM-M4                                                           | 10        | 1.64%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.48%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 1.31%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 1.15%   |
| Synaptics  WBDI                                                            | 5         | 0.82%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 0.66%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.66%   |
| Synaptics WBDI Device                                                      | 4         | 0.66%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.49%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.49%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.33%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.33%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.33%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.33%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.33%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.16%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.16%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 108       | 43.37%  |
| Broadcom                  | 99        | 39.76%  |
| Upek                      | 16        | 6.43%   |
| Lenovo                    | 10        | 4.02%   |
| O2 Micro                  | 5         | 2.01%   |
| SCM Microsystems          | 3         | 1.2%    |
| Yubico.com                | 2         | 0.8%    |
| Clay Logic                | 2         | 0.8%    |
| Hewlett-Packard           | 1         | 0.4%    |
| Gemalto (was Gemplus)     | 1         | 0.4%    |
| Chicony Electronics       | 1         | 0.4%    |
| Aladdin Knowledge Systems | 1         | 0.4%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 108       | 43.37%  |
| Broadcom 5880                                                                | 28        | 11.24%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 27        | 10.84%  |
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 8.84%   |
| Broadcom 58200                                                               | 20        | 8.03%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 16        | 6.43%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 4.02%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 1.61%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 0.8%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.8%    |
| Clay Logic CanoKey Pigeon                                                    | 2         | 0.8%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.8%    |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 0.4%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.4%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.4%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.4%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.4%    |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.4%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1735      | 60.1%   |
| 1     | 892       | 30.9%   |
| 2     | 202       | 7%      |
| 3     | 50        | 1.73%   |
| 4     | 7         | 0.24%   |
| 7     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 598       | 41.41%  |
| Graphics card            | 250       | 17.31%  |
| Chipcard                 | 224       | 15.51%  |
| Multimedia controller    | 96        | 6.65%   |
| Net/wireless             | 84        | 5.82%   |
| Camera                   | 79        | 5.47%   |
| Bluetooth                | 27        | 1.87%   |
| Net/ethernet             | 17        | 1.18%   |
| Storage                  | 16        | 1.11%   |
| Sound                    | 14        | 0.97%   |
| Communication controller | 13        | 0.9%    |
| Card reader              | 9         | 0.62%   |
| Network                  | 6         | 0.42%   |
| Wireless                 | 2         | 0.14%   |
| Modem                    | 2         | 0.14%   |
| Dvb card                 | 2         | 0.14%   |
| Unassigned class         | 1         | 0.07%   |
| Storage/nvme             | 1         | 0.07%   |
| Storage/ata              | 1         | 0.07%   |
| Flash memory             | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

