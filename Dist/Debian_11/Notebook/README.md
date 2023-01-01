Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 3625

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| HP            | 255 G3                      | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| HP            | ProBook 6570b               | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| HP            | ProBook 6470b               | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Notebook      | L14xMU                      | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Dell          | Inspiron 1012               | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Exo           | Smart Serie M               | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| Dell          | Latitude E6520              | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Medion        | E122X                       | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [096d4fc8c2](https://linux-hardware.org/?probe=096d4fc8c2) | Dec 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [c5f2f2db53](https://linux-hardware.org/?probe=c5f2f2db53) | Dec 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | [6ac6e552a8](https://linux-hardware.org/?probe=6ac6e552a8) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
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
| HP            | Stream Notebook PC 13       | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| Dell          | G3 3590                     | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [b4e828bef3](https://linux-hardware.org/?probe=b4e828bef3) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | [056d76bae8](https://linux-hardware.org/?probe=056d76bae8) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | ZBook Power 15.6 inch G8... | [6b202d6cc2](https://linux-hardware.org/?probe=6b202d6cc2) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Dell          | G3 3590                     | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [cd4fa20e66](https://linux-hardware.org/?probe=cd4fa20e66) | Dec 20, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e676fe186f](https://linux-hardware.org/?probe=e676fe186f) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| ASUSTek       | T100TA                      | [1dc546e14a](https://linux-hardware.org/?probe=1dc546e14a) | Dec 20, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| ASUSTek       | 900SD                       | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| Dell          | Latitude E6530              | [198a9bc936](https://linux-hardware.org/?probe=198a9bc936) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470 20HES3JR02    | [f9e4638f19](https://linux-hardware.org/?probe=f9e4638f19) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Dell          | Latitude E4310              | [ace267f47c](https://linux-hardware.org/?probe=ace267f47c) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | [218654b079](https://linux-hardware.org/?probe=218654b079) | Dec 17, 2022 |
| HP            | Notebook                    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| Unknown       | Unknown                     | [208016df07](https://linux-hardware.org/?probe=208016df07) | Dec 17, 2022 |
| Dell          | Inspiron 7590               | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| Intel         | powered classmate PC        | [e0401225a2](https://linux-hardware.org/?probe=e0401225a2) | Dec 15, 2022 |
| Unknown       | T3 MRD                      | [909e1a1604](https://linux-hardware.org/?probe=909e1a1604) | Dec 15, 2022 |
| Google        | Cyan                        | [2b9f20b7da](https://linux-hardware.org/?probe=2b9f20b7da) | Dec 15, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | [f7590c1a07](https://linux-hardware.org/?probe=f7590c1a07) | Dec 15, 2022 |
| Dell          | Latitude 3490               | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Acer          | Aspire 5738                 | [c0c4581310](https://linux-hardware.org/?probe=c0c4581310) | Dec 14, 2022 |
| Apple         | MacBook6,1                  | [f19d464a26](https://linux-hardware.org/?probe=f19d464a26) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| Dell          | Latitude 5520               | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| ASUSTek       | G75VW                       | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| Exo           | Smart Serie M               | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| Google        | Terra                       | [765deab389](https://linux-hardware.org/?probe=765deab389) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [95dc27194a](https://linux-hardware.org/?probe=95dc27194a) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Google        | Enguarde                    | [60cce42479](https://linux-hardware.org/?probe=60cce42479) | Dec 12, 2022 |
| Lenovo        | ThinkPad R61e 7650DHU       | [138f60e67c](https://linux-hardware.org/?probe=138f60e67c) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | [99c965b83f](https://linux-hardware.org/?probe=99c965b83f) | Dec 12, 2022 |
| Dell          | Latitude 5411               | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Acer          | Nitro AN515-51              | [918c340b04](https://linux-hardware.org/?probe=918c340b04) | Dec 12, 2022 |
| Lenovo        | ThinkPad T470 20HES6HC00    | [ca9d609d9d](https://linux-hardware.org/?probe=ca9d609d9d) | Dec 12, 2022 |
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
| SANTECH       | NHx0DB,DE                   | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Lenovo        | ThinkPad 13 20J10046US      | [170accb6cc](https://linux-hardware.org/?probe=170accb6cc) | Dec 09, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| ASUSTek       | N750JV                      | [e06c6025f3](https://linux-hardware.org/?probe=e06c6025f3) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [09de0ec660](https://linux-hardware.org/?probe=09de0ec660) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | [e56fd20ec9](https://linux-hardware.org/?probe=e56fd20ec9) | Dec 08, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Lenovo        | ThinkPad X230 2320CTO       | [b74f2893d0](https://linux-hardware.org/?probe=b74f2893d0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| HP            | EliteBook 2570p             | [fc7d866c16](https://linux-hardware.org/?probe=fc7d866c16) | Dec 06, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | [4dc49eeb10](https://linux-hardware.org/?probe=4dc49eeb10) | Dec 06, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [5b72cdbdb8](https://linux-hardware.org/?probe=5b72cdbdb8) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| Acer          | Aspire A315-23G             | [41e6f6a3fa](https://linux-hardware.org/?probe=41e6f6a3fa) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [f5be4eb37d](https://linux-hardware.org/?probe=f5be4eb37d) | Dec 04, 2022 |
| Toshiba       | dynabook R63/P              | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b475911aaf](https://linux-hardware.org/?probe=b475911aaf) | Dec 03, 2022 |
| Dell          | Inspiron 15-5578            | [61f5950e07](https://linux-hardware.org/?probe=61f5950e07) | Dec 03, 2022 |
| ASUSTek       | S500CA                      | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| Lenovo        | ThinkPad X280 20KE0015BR    | [4c65d4e572](https://linux-hardware.org/?probe=4c65d4e572) | Dec 03, 2022 |
| Dell          | Inspiron 5566               | [54e06d37fc](https://linux-hardware.org/?probe=54e06d37fc) | Dec 02, 2022 |
| ASUSTek       | N750JV                      | [0fc50d63c4](https://linux-hardware.org/?probe=0fc50d63c4) | Dec 02, 2022 |
| Dell          | Latitude 5591               | [f5735acca7](https://linux-hardware.org/?probe=f5735acca7) | Dec 02, 2022 |
| HP            | Unknown                     | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| Aquarius      | NS585                       | [bbd3bd3ca6](https://linux-hardware.org/?probe=bbd3bd3ca6) | Dec 02, 2022 |
| Aquarius      | NS585                       | [50222418e5](https://linux-hardware.org/?probe=50222418e5) | Dec 02, 2022 |
| Aquarius      | NS585                       | [d55d40681f](https://linux-hardware.org/?probe=d55d40681f) | Dec 02, 2022 |
| Aquarius      | NS585                       | [9013a1cce6](https://linux-hardware.org/?probe=9013a1cce6) | Dec 02, 2022 |
| HP            | 620                         | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [674157de54](https://linux-hardware.org/?probe=674157de54) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| HP            | Pavilion dv5                | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| Dell          | Latitude 7490               | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| Dell          | XPS 15 9500                 | [9c87ab493e](https://linux-hardware.org/?probe=9c87ab493e) | Nov 29, 2022 |
| Lenovo        | ThinkPad X301 2776LEG       | [ebaea0c805](https://linux-hardware.org/?probe=ebaea0c805) | Nov 28, 2022 |
| Dell          | Precision M6400             | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| ASUSTek       | GL752VW                     | [edc0678b85](https://linux-hardware.org/?probe=edc0678b85) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [32bfa52fc1](https://linux-hardware.org/?probe=32bfa52fc1) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [3d1b8f282a](https://linux-hardware.org/?probe=3d1b8f282a) | Nov 27, 2022 |
| MSI           | Creator 15M A9SD            | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| HP            | Laptop 15-da3xxx            | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
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
| Aquarius      | NS585                       | [d54530cbcb](https://linux-hardware.org/?probe=d54530cbcb) | Nov 24, 2022 |
| Aquarius      | NS585                       | [64d9bcbcde](https://linux-hardware.org/?probe=64d9bcbcde) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| Lenovo        | ThinkPad T495 20NK000UUS    | [0e8c0e6f07](https://linux-hardware.org/?probe=0e8c0e6f07) | Nov 23, 2022 |
| Lenovo        | ThinkPad T490 20N3S8T211    | [97ea649145](https://linux-hardware.org/?probe=97ea649145) | Nov 23, 2022 |
| Dell          | Latitude E6530              | [71623eedf3](https://linux-hardware.org/?probe=71623eedf3) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| HP            | Compaq 6720s                | [63a0e0161c](https://linux-hardware.org/?probe=63a0e0161c) | Nov 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [363e0b0149](https://linux-hardware.org/?probe=363e0b0149) | Nov 22, 2022 |
| Unknown       | Unknown                     | [1de34b67e2](https://linux-hardware.org/?probe=1de34b67e2) | Nov 22, 2022 |
| Dell          | Latitude 3420               | [30434de3e9](https://linux-hardware.org/?probe=30434de3e9) | Nov 22, 2022 |
| Unknown       | Wiren Board rev. 7.3.1 (... | [1f9ccab914](https://linux-hardware.org/?probe=1f9ccab914) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| HP            | Pavilion Sleekbook 15       | [add4f71bc0](https://linux-hardware.org/?probe=add4f71bc0) | Nov 22, 2022 |
| HP            | ENVY 6                      | [feb348843e](https://linux-hardware.org/?probe=feb348843e) | Nov 22, 2022 |
| Lenovo        | Y520-15IKBA 80WY            | [c1cccb2b2a](https://linux-hardware.org/?probe=c1cccb2b2a) | Nov 22, 2022 |
| ASUSTek       | K53SD                       | [c127a0db71](https://linux-hardware.org/?probe=c127a0db71) | Nov 21, 2022 |
| Lenovo        | ThinkPad E14 20RAS04700     | [63d93d05db](https://linux-hardware.org/?probe=63d93d05db) | Nov 21, 2022 |
| MSI           | Creator 15M A9SD            | [e6d5440b09](https://linux-hardware.org/?probe=e6d5440b09) | Nov 21, 2022 |
| Dell          | Latitude 5310               | [9c19a3de68](https://linux-hardware.org/?probe=9c19a3de68) | Nov 21, 2022 |
| HP            | Laptop 15-db0xxx            | [f634446cde](https://linux-hardware.org/?probe=f634446cde) | Nov 21, 2022 |
| Acer          | Popcorn                     | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| HP            | Laptop 15s-du3xxx           | [a90cea62ff](https://linux-hardware.org/?probe=a90cea62ff) | Nov 19, 2022 |
| Dell          | XPS 13 9380                 | [d42bddbd11](https://linux-hardware.org/?probe=d42bddbd11) | Nov 19, 2022 |
| Aquarius      | NS585                       | [a0bc8d3f44](https://linux-hardware.org/?probe=a0bc8d3f44) | Nov 19, 2022 |
| Acer          | Aspire ES1-533              | [8c080caac2](https://linux-hardware.org/?probe=8c080caac2) | Nov 19, 2022 |
| Fujitsu       | FMVNQL7PM                   | [28ee68da79](https://linux-hardware.org/?probe=28ee68da79) | Nov 19, 2022 |
| Dell          | Latitude 7410               | [ce222880fe](https://linux-hardware.org/?probe=ce222880fe) | Nov 18, 2022 |
| Dynabook      | TECRA A50-J                 | [c0ae8746e0](https://linux-hardware.org/?probe=c0ae8746e0) | Nov 18, 2022 |
| HP            | 650                         | [43998a620b](https://linux-hardware.org/?probe=43998a620b) | Nov 18, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [0278a1f18d](https://linux-hardware.org/?probe=0278a1f18d) | Nov 18, 2022 |
| Apple         | MacBookAir7,2               | [f0fa194e20](https://linux-hardware.org/?probe=f0fa194e20) | Nov 18, 2022 |
| Google        | Terra                       | [9fcc3fb18a](https://linux-hardware.org/?probe=9fcc3fb18a) | Nov 18, 2022 |
| ASUSTek       | T100TA                      | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| Lenovo        | B475 Sabine                 | [5be5a7cd5f](https://linux-hardware.org/?probe=5be5a7cd5f) | Nov 17, 2022 |
| HP            | EliteBook 745 G5            | [9d7fefd253](https://linux-hardware.org/?probe=9d7fefd253) | Nov 17, 2022 |
| MSI           | Creator 15M A9SD            | [f1fdc384f9](https://linux-hardware.org/?probe=f1fdc384f9) | Nov 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [814b5d3d2e](https://linux-hardware.org/?probe=814b5d3d2e) | Nov 17, 2022 |
| HP            | Laptop 15-db0xxx            | [5aa50e7f6c](https://linux-hardware.org/?probe=5aa50e7f6c) | Nov 17, 2022 |
| HP            | OMEN by Laptop 15-dh0xxx    | [523e8a1c6b](https://linux-hardware.org/?probe=523e8a1c6b) | Nov 17, 2022 |
| Dell          | Inspiron 13 5310            | [3c9865d86e](https://linux-hardware.org/?probe=3c9865d86e) | Nov 16, 2022 |
| HP            | Laptop 15-db0xxx            | [f6202bb6fa](https://linux-hardware.org/?probe=f6202bb6fa) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8fe0bcfe69](https://linux-hardware.org/?probe=8fe0bcfe69) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | G470 20078                  | [55f47f2c19](https://linux-hardware.org/?probe=55f47f2c19) | Nov 16, 2022 |
| Unknown       | Unknown                     | [a86465b0f3](https://linux-hardware.org/?probe=a86465b0f3) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [f29e7d7659](https://linux-hardware.org/?probe=f29e7d7659) | Nov 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [867825d906](https://linux-hardware.org/?probe=867825d906) | Nov 15, 2022 |
| Dell          | Inspiron 5558               | [0674cb5916](https://linux-hardware.org/?probe=0674cb5916) | Nov 15, 2022 |
| GPU Compan... | GWTN116-3                   | [f8d8191f69](https://linux-hardware.org/?probe=f8d8191f69) | Nov 15, 2022 |
| ASUSTek       | X550VX                      | [8e55592803](https://linux-hardware.org/?probe=8e55592803) | Nov 15, 2022 |
| Dell          | G7 7700                     | [2440bebe2c](https://linux-hardware.org/?probe=2440bebe2c) | Nov 15, 2022 |
| IBM           | ThinkPad X31 2672JBU        | [ea0c82f4eb](https://linux-hardware.org/?probe=ea0c82f4eb) | Nov 15, 2022 |
| HP            | EliteBook 820 G3            | [fe84036164](https://linux-hardware.org/?probe=fe84036164) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [862e9a2c25](https://linux-hardware.org/?probe=862e9a2c25) | Nov 15, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [a94cf56482](https://linux-hardware.org/?probe=a94cf56482) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| Acer          | Aspire A315-23G             | [16e5672a66](https://linux-hardware.org/?probe=16e5672a66) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [100714ed23](https://linux-hardware.org/?probe=100714ed23) | Nov 14, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [8267ec6686](https://linux-hardware.org/?probe=8267ec6686) | Nov 14, 2022 |
| Toshiba       | Satellite P50-B-10Q         | [f28064cdad](https://linux-hardware.org/?probe=f28064cdad) | Nov 14, 2022 |
| HP            | 530 Notebook PC(KD092AA#... | [b6c682238c](https://linux-hardware.org/?probe=b6c682238c) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [ff0881b6e4](https://linux-hardware.org/?probe=ff0881b6e4) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| HP            | EliteBook 8460p             | [8cb389e68e](https://linux-hardware.org/?probe=8cb389e68e) | Nov 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6677ca6be8](https://linux-hardware.org/?probe=6677ca6be8) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [978facebde](https://linux-hardware.org/?probe=978facebde) | Nov 12, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [904b7c0e89](https://linux-hardware.org/?probe=904b7c0e89) | Nov 12, 2022 |
| HP            | Notebook                    | [2419e7d149](https://linux-hardware.org/?probe=2419e7d149) | Nov 12, 2022 |
| HP            | Notebook                    | [97c6c3c412](https://linux-hardware.org/?probe=97c6c3c412) | Nov 12, 2022 |
| GPU Compan... | GWTC116-2                   | [9e0c2df66d](https://linux-hardware.org/?probe=9e0c2df66d) | Nov 12, 2022 |
| IBM           | ThinkPad X31 2672JBU        | [9f627ba3f8](https://linux-hardware.org/?probe=9f627ba3f8) | Nov 12, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [22ab694d81](https://linux-hardware.org/?probe=22ab694d81) | Nov 11, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [c79bbe36c5](https://linux-hardware.org/?probe=c79bbe36c5) | Nov 11, 2022 |
| NCA Group     | iRU_Notebook                | [6d22b3942e](https://linux-hardware.org/?probe=6d22b3942e) | Nov 11, 2022 |
| HP            | Spectre x2 Detachable       | [0c480bd74d](https://linux-hardware.org/?probe=0c480bd74d) | Nov 11, 2022 |
| ASUSTek       | K50IE                       | [4bd91fccfa](https://linux-hardware.org/?probe=4bd91fccfa) | Nov 11, 2022 |
| Positivo B... | VJFE53F11X-XXXXXX           | [7e81c7cf85](https://linux-hardware.org/?probe=7e81c7cf85) | Nov 10, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [ae40e6e5b3](https://linux-hardware.org/?probe=ae40e6e5b3) | Nov 10, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [8bb3389cc1](https://linux-hardware.org/?probe=8bb3389cc1) | Nov 10, 2022 |
| Lenovo        | G50-30 80G0                 | [1e0c308a85](https://linux-hardware.org/?probe=1e0c308a85) | Nov 10, 2022 |
| ASUSTek       | X550VXK                     | [f752e7959c](https://linux-hardware.org/?probe=f752e7959c) | Nov 10, 2022 |
| ASUSTek       | K50IE                       | [5176f404f1](https://linux-hardware.org/?probe=5176f404f1) | Nov 10, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [9a69ea4724](https://linux-hardware.org/?probe=9a69ea4724) | Nov 10, 2022 |
| Dell          | Latitude E6530              | [f71e1a930c](https://linux-hardware.org/?probe=f71e1a930c) | Nov 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [9d27997bce](https://linux-hardware.org/?probe=9d27997bce) | Nov 09, 2022 |
| Gigabyte      | Sabre 15                    | [1edede0895](https://linux-hardware.org/?probe=1edede0895) | Nov 09, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [098d4ab9ec](https://linux-hardware.org/?probe=098d4ab9ec) | Nov 09, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [6b1f5f2c2a](https://linux-hardware.org/?probe=6b1f5f2c2a) | Nov 08, 2022 |
| Aquarius      | NS585                       | [9b20fcc4b8](https://linux-hardware.org/?probe=9b20fcc4b8) | Nov 08, 2022 |
| Dell          | Latitude E7470              | [3938dbeadd](https://linux-hardware.org/?probe=3938dbeadd) | Nov 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [da41b87b7c](https://linux-hardware.org/?probe=da41b87b7c) | Nov 07, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [f3c625be2d](https://linux-hardware.org/?probe=f3c625be2d) | Nov 07, 2022 |
| Unknown       | Unknown                     | [6af513692f](https://linux-hardware.org/?probe=6af513692f) | Nov 07, 2022 |
| Unknown       | Unknown                     | [b4859caaba](https://linux-hardware.org/?probe=b4859caaba) | Nov 07, 2022 |
| Lenovo        | ThinkPad W700 275236U       | [d3580b26c6](https://linux-hardware.org/?probe=d3580b26c6) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [32b59c7a7d](https://linux-hardware.org/?probe=32b59c7a7d) | Nov 06, 2022 |
| HP            | Laptop 15-db0xxx            | [f0c8aff40f](https://linux-hardware.org/?probe=f0c8aff40f) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [9593951427](https://linux-hardware.org/?probe=9593951427) | Nov 06, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [e872e8551e](https://linux-hardware.org/?probe=e872e8551e) | Nov 06, 2022 |
| Dell          | Latitude E6520              | [53eedbde1f](https://linux-hardware.org/?probe=53eedbde1f) | Nov 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [55d115647e](https://linux-hardware.org/?probe=55d115647e) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [47dda70950](https://linux-hardware.org/?probe=47dda70950) | Nov 06, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5a2028bd2d](https://linux-hardware.org/?probe=5a2028bd2d) | Nov 05, 2022 |
| Acer          | Aspire V3-572G              | [77f939bab4](https://linux-hardware.org/?probe=77f939bab4) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [2d165dd7b0](https://linux-hardware.org/?probe=2d165dd7b0) | Nov 05, 2022 |
| Lenovo        | ThinkPad L380 20M50013MH    | [80ac51627a](https://linux-hardware.org/?probe=80ac51627a) | Nov 05, 2022 |
| ASUSTek       | X756UWK                     | [b89c7882f3](https://linux-hardware.org/?probe=b89c7882f3) | Nov 05, 2022 |
| Dell          | Inspiron 7570               | [158f7b0bcd](https://linux-hardware.org/?probe=158f7b0bcd) | Nov 05, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [605e06c6ad](https://linux-hardware.org/?probe=605e06c6ad) | Nov 04, 2022 |
| Google        | Terra                       | [90518f31df](https://linux-hardware.org/?probe=90518f31df) | Nov 04, 2022 |
| Google        | Terra                       | [46ffa8092b](https://linux-hardware.org/?probe=46ffa8092b) | Nov 04, 2022 |
| Google        | Terra                       | [fc3f4b0ba5](https://linux-hardware.org/?probe=fc3f4b0ba5) | Nov 04, 2022 |
| Google        | Terra                       | [41017e02e4](https://linux-hardware.org/?probe=41017e02e4) | Nov 04, 2022 |
| Google        | Terra                       | [7429a311e4](https://linux-hardware.org/?probe=7429a311e4) | Nov 04, 2022 |
| SK hynix      | HyBook                      | [e758cde5ed](https://linux-hardware.org/?probe=e758cde5ed) | Nov 04, 2022 |
| HP            | ProBook 6450b               | [7e595214cb](https://linux-hardware.org/?probe=7e595214cb) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [391881cdd5](https://linux-hardware.org/?probe=391881cdd5) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [67e9f8d2f4](https://linux-hardware.org/?probe=67e9f8d2f4) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ecf54fa708](https://linux-hardware.org/?probe=ecf54fa708) | Nov 03, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8681693f03](https://linux-hardware.org/?probe=8681693f03) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | [d4d0f735d4](https://linux-hardware.org/?probe=d4d0f735d4) | Nov 03, 2022 |
| HP            | EliteBook 745 G6            | [04e15fb2d7](https://linux-hardware.org/?probe=04e15fb2d7) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [c80c7a9048](https://linux-hardware.org/?probe=c80c7a9048) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [e507b9a974](https://linux-hardware.org/?probe=e507b9a974) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [7a5f1eaf6c](https://linux-hardware.org/?probe=7a5f1eaf6c) | Nov 03, 2022 |
| SAGER         | D900F                       | [7e0d0de36a](https://linux-hardware.org/?probe=7e0d0de36a) | Nov 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [cecc0cca9d](https://linux-hardware.org/?probe=cecc0cca9d) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [464cc2acc3](https://linux-hardware.org/?probe=464cc2acc3) | Nov 03, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d59bd1e8f1](https://linux-hardware.org/?probe=d59bd1e8f1) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [4342ecb0f9](https://linux-hardware.org/?probe=4342ecb0f9) | Nov 02, 2022 |
| Google        | Terra                       | [46299bf228](https://linux-hardware.org/?probe=46299bf228) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [fd32769391](https://linux-hardware.org/?probe=fd32769391) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [d3c1c92563](https://linux-hardware.org/?probe=d3c1c92563) | Nov 02, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [0ffaee423b](https://linux-hardware.org/?probe=0ffaee423b) | Nov 02, 2022 |
| ASUSTek       | 1005HA                      | [1d386943d6](https://linux-hardware.org/?probe=1d386943d6) | Nov 02, 2022 |
| HP            | G42                         | [18c487d99d](https://linux-hardware.org/?probe=18c487d99d) | Nov 02, 2022 |
| Digma         | EVE 11 C422 ES1068EW        | [f5177de131](https://linux-hardware.org/?probe=f5177de131) | Nov 02, 2022 |
| Toshiba       | Satellite L755              | [dc3d60731e](https://linux-hardware.org/?probe=dc3d60731e) | Nov 01, 2022 |
| Acer          | Aspire one                  | [bfb9f97d74](https://linux-hardware.org/?probe=bfb9f97d74) | Oct 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c9e0b81f80](https://linux-hardware.org/?probe=c9e0b81f80) | Oct 31, 2022 |
| HP            | Compaq nc6320 (EV073AV)     | [b73f359ded](https://linux-hardware.org/?probe=b73f359ded) | Oct 31, 2022 |
| ASUSTek       | G75VW                       | [6f1d41a85c](https://linux-hardware.org/?probe=6f1d41a85c) | Oct 31, 2022 |
| Acer          | Aspire one                  | [82b34552f6](https://linux-hardware.org/?probe=82b34552f6) | Oct 31, 2022 |
| Aquarius      | NS585                       | [e4b4e0456d](https://linux-hardware.org/?probe=e4b4e0456d) | Oct 31, 2022 |
| Apple         | MacBookPro5,5               | [00e1f1f754](https://linux-hardware.org/?probe=00e1f1f754) | Oct 31, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [a872c9888a](https://linux-hardware.org/?probe=a872c9888a) | Oct 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [45f670d99f](https://linux-hardware.org/?probe=45f670d99f) | Oct 30, 2022 |
| Acer          | Aspire A515-51G             | [12380f78de](https://linux-hardware.org/?probe=12380f78de) | Oct 30, 2022 |
| ASUSTek       | N751JK                      | [eea92055f3](https://linux-hardware.org/?probe=eea92055f3) | Oct 30, 2022 |
| Dell          | Latitude 5501               | [67f979a26d](https://linux-hardware.org/?probe=67f979a26d) | Oct 29, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | Latitude 5590               | [c7fa986fbd](https://linux-hardware.org/?probe=c7fa986fbd) | Oct 29, 2022 |
| ASUSTek       | X75VC                       | [9c1ab509ec](https://linux-hardware.org/?probe=9c1ab509ec) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [8cc0e0d828](https://linux-hardware.org/?probe=8cc0e0d828) | Oct 29, 2022 |
| Insyde        | Braswell                    | [d98b2d9661](https://linux-hardware.org/?probe=d98b2d9661) | Oct 29, 2022 |
| Samsung       | 300V3A/300V4A/300V5A        | [4acb2d0863](https://linux-hardware.org/?probe=4acb2d0863) | Oct 29, 2022 |
| Dell          | XPS 17 9720                 | [270b988521](https://linux-hardware.org/?probe=270b988521) | Oct 29, 2022 |
| Dell          | Precision 7520              | [30f6ad7a26](https://linux-hardware.org/?probe=30f6ad7a26) | Oct 29, 2022 |
| Dell          | Precision 7520              | [b81923dbd2](https://linux-hardware.org/?probe=b81923dbd2) | Oct 29, 2022 |
| MSI           | Modern 15 A10RBS            | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [60d1db050b](https://linux-hardware.org/?probe=60d1db050b) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [2a9f06c2b4](https://linux-hardware.org/?probe=2a9f06c2b4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [787904d265](https://linux-hardware.org/?probe=787904d265) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [0971db18ed](https://linux-hardware.org/?probe=0971db18ed) | Oct 28, 2022 |
| Toshiba       | Satellite L755              | [0fa70f29d4](https://linux-hardware.org/?probe=0fa70f29d4) | Oct 28, 2022 |
| Lenovo        | ThinkPad T530 239242U       | [dbf70338e9](https://linux-hardware.org/?probe=dbf70338e9) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Dell          | XPS 17 9700                 | [81121b7762](https://linux-hardware.org/?probe=81121b7762) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [0696abd43c](https://linux-hardware.org/?probe=0696abd43c) | Oct 28, 2022 |
| Toshiba       | Satellite C650D             | [d42867d201](https://linux-hardware.org/?probe=d42867d201) | Oct 28, 2022 |
| ASUSTek       | X555QG                      | [bace747804](https://linux-hardware.org/?probe=bace747804) | Oct 28, 2022 |
| Acer          | Aspire A715-75G             | [78b0c55e62](https://linux-hardware.org/?probe=78b0c55e62) | Oct 28, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [02c6d1fe1a](https://linux-hardware.org/?probe=02c6d1fe1a) | Oct 28, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | [768c6c8357](https://linux-hardware.org/?probe=768c6c8357) | Oct 28, 2022 |
| SANTECH       | NHx0DB,DE                   | [db8c0489f4](https://linux-hardware.org/?probe=db8c0489f4) | Oct 28, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [63565608d1](https://linux-hardware.org/?probe=63565608d1) | Oct 28, 2022 |
| Google        | Boten                       | [2ed6baabf0](https://linux-hardware.org/?probe=2ed6baabf0) | Oct 27, 2022 |
| HP            | ZBook 15 G3                 | [2b886c255e](https://linux-hardware.org/?probe=2b886c255e) | Oct 27, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [24da197a3a](https://linux-hardware.org/?probe=24da197a3a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [3ab1fbc8e8](https://linux-hardware.org/?probe=3ab1fbc8e8) | Oct 27, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [faafe16cfb](https://linux-hardware.org/?probe=faafe16cfb) | Oct 27, 2022 |
| THTF          | CR F860-T1                  | [0e20f4f61a](https://linux-hardware.org/?probe=0e20f4f61a) | Oct 27, 2022 |
| ASUSTek       | X541UAK                     | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bfd570bbef](https://linux-hardware.org/?probe=bfd570bbef) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [58820ca517](https://linux-hardware.org/?probe=58820ca517) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [6b9a3ab27e](https://linux-hardware.org/?probe=6b9a3ab27e) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [a5bd8bebc7](https://linux-hardware.org/?probe=a5bd8bebc7) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [bce3a8b1b3](https://linux-hardware.org/?probe=bce3a8b1b3) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [65a1d5242f](https://linux-hardware.org/?probe=65a1d5242f) | Oct 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a09e3f3669](https://linux-hardware.org/?probe=a09e3f3669) | Oct 26, 2022 |
| ASUSTek       | 1005HA                      | [118fed891f](https://linux-hardware.org/?probe=118fed891f) | Oct 26, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [93b8dd8c3e](https://linux-hardware.org/?probe=93b8dd8c3e) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [5e08852d18](https://linux-hardware.org/?probe=5e08852d18) | Oct 25, 2022 |
| Lenovo        | Z50-70 20354                | [08b673e57b](https://linux-hardware.org/?probe=08b673e57b) | Oct 25, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [438afb4185](https://linux-hardware.org/?probe=438afb4185) | Oct 25, 2022 |
| Toshiba       | dynabook MX/33KBL           | [7ee9057da2](https://linux-hardware.org/?probe=7ee9057da2) | Oct 25, 2022 |
| Dell          | Vostro 5490                 | [6b4c7d3c8b](https://linux-hardware.org/?probe=6b4c7d3c8b) | Oct 24, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [eae727e6a0](https://linux-hardware.org/?probe=eae727e6a0) | Oct 24, 2022 |
| Packard Be... | DOT S                       | [f280a6ccbc](https://linux-hardware.org/?probe=f280a6ccbc) | Oct 24, 2022 |
| Lenovo        | ThinkPad T470 20HES4VB00    | [f7b39d371a](https://linux-hardware.org/?probe=f7b39d371a) | Oct 24, 2022 |
| Packard Be... | H17HV                       | [2e94cfdd84](https://linux-hardware.org/?probe=2e94cfdd84) | Oct 24, 2022 |
| Alienware     | M11xR3                      | [62bf8b7b02](https://linux-hardware.org/?probe=62bf8b7b02) | Oct 24, 2022 |
| HP            | Pavilion g4                 | [3b6666b5ba](https://linux-hardware.org/?probe=3b6666b5ba) | Oct 24, 2022 |
| Lenovo        | V310-14IKB 80T2             | [73f18a6fbb](https://linux-hardware.org/?probe=73f18a6fbb) | Oct 24, 2022 |
| Dell          | Precision 7750              | [dd51bb7ccd](https://linux-hardware.org/?probe=dd51bb7ccd) | Oct 23, 2022 |
| HP            | Pavilion g4                 | [487a972bda](https://linux-hardware.org/?probe=487a972bda) | Oct 23, 2022 |
| Panasonic     | CF-LX3J-50M3                | [949acb4c3a](https://linux-hardware.org/?probe=949acb4c3a) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [6437fb22e1](https://linux-hardware.org/?probe=6437fb22e1) | Oct 22, 2022 |
| HP            | Pavilion TS 11              | [a19b5987c6](https://linux-hardware.org/?probe=a19b5987c6) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [88af6c857c](https://linux-hardware.org/?probe=88af6c857c) | Oct 22, 2022 |
| Dell          | Latitude E6520              | [246517ceab](https://linux-hardware.org/?probe=246517ceab) | Oct 22, 2022 |
| ASUSTek       | X756UQK                     | [2570a4e51f](https://linux-hardware.org/?probe=2570a4e51f) | Oct 22, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Apple         | MacBook5,2                  | [165ce75570](https://linux-hardware.org/?probe=165ce75570) | Oct 21, 2022 |
| Acer          | Swift SF314-42              | [2449f6a1b7](https://linux-hardware.org/?probe=2449f6a1b7) | Oct 21, 2022 |
| Aquarius      | NS585                       | [c953c5090c](https://linux-hardware.org/?probe=c953c5090c) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | V310-14IKB 80T2             | [8a0f6b66e6](https://linux-hardware.org/?probe=8a0f6b66e6) | Oct 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7acb5493d7](https://linux-hardware.org/?probe=7acb5493d7) | Oct 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b13dc58884](https://linux-hardware.org/?probe=b13dc58884) | Oct 20, 2022 |
| ASUSTek       | G75VW                       | [194959e65e](https://linux-hardware.org/?probe=194959e65e) | Oct 20, 2022 |
| HP            | EliteBook 745 G3            | [3bfbc8dcac](https://linux-hardware.org/?probe=3bfbc8dcac) | Oct 20, 2022 |
| HP            | Laptop 15-ef2xxx            | [823d998220](https://linux-hardware.org/?probe=823d998220) | Oct 20, 2022 |
| Apple         | MacBook5,2                  | [1e76467975](https://linux-hardware.org/?probe=1e76467975) | Oct 20, 2022 |
| Aquarius      | NS585                       | [a134ed693c](https://linux-hardware.org/?probe=a134ed693c) | Oct 20, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [162e7a20b2](https://linux-hardware.org/?probe=162e7a20b2) | Oct 20, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| HP            | 245 G7                      | [9ec088c343](https://linux-hardware.org/?probe=9ec088c343) | Oct 19, 2022 |
| ASUSTek       | X541NA                      | [5b61fd3a38](https://linux-hardware.org/?probe=5b61fd3a38) | Oct 19, 2022 |
| Dell          | Inspiron 7590               | [43ec5b2df8](https://linux-hardware.org/?probe=43ec5b2df8) | Oct 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [67ebd92594](https://linux-hardware.org/?probe=67ebd92594) | Oct 19, 2022 |
| Acer          | Aspire A315-23G             | [93584b3b67](https://linux-hardware.org/?probe=93584b3b67) | Oct 19, 2022 |
| Fujitsu       | LIFEBOOK E753               | [1fbb05ae6b](https://linux-hardware.org/?probe=1fbb05ae6b) | Oct 18, 2022 |
| HP            | EliteBook 745 G3            | [e800d683ef](https://linux-hardware.org/?probe=e800d683ef) | Oct 18, 2022 |
| ASUSTek       | G75VW                       | [5ee12be257](https://linux-hardware.org/?probe=5ee12be257) | Oct 18, 2022 |
| UNOWHY        | Y13G010S4EI                 | [f7f13866aa](https://linux-hardware.org/?probe=f7f13866aa) | Oct 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IAH7 82S... | [dfa3140411](https://linux-hardware.org/?probe=dfa3140411) | Oct 17, 2022 |
| Dell          | XPS 17 9700                 | [5368bd3ad6](https://linux-hardware.org/?probe=5368bd3ad6) | Oct 17, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e076f9208c](https://linux-hardware.org/?probe=e076f9208c) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [10bcc184e7](https://linux-hardware.org/?probe=10bcc184e7) | Oct 17, 2022 |
| ASUSTek       | G75VW                       | [a88a291921](https://linux-hardware.org/?probe=a88a291921) | Oct 16, 2022 |
| Lenovo        | Legion Y545 81Q6            | [b6162e2c5e](https://linux-hardware.org/?probe=b6162e2c5e) | Oct 16, 2022 |
| Dell          | Inspiron 1545               | [d9928a4ee9](https://linux-hardware.org/?probe=d9928a4ee9) | Oct 16, 2022 |
| Dell          | Latitude 3320               | [e4645890b8](https://linux-hardware.org/?probe=e4645890b8) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [ae7d737ee5](https://linux-hardware.org/?probe=ae7d737ee5) | Oct 16, 2022 |
| Dell          | Inspiron N5110              | [5cbc449f36](https://linux-hardware.org/?probe=5cbc449f36) | Oct 16, 2022 |
| HP            | Laptop 15-ef2xxx            | [fb37bc6617](https://linux-hardware.org/?probe=fb37bc6617) | Oct 15, 2022 |
| HP            | EliteBook Folio 1040 G1     | [81df2d786a](https://linux-hardware.org/?probe=81df2d786a) | Oct 15, 2022 |
| Panasonic     | CF-LX3J-50M3                | [95386977de](https://linux-hardware.org/?probe=95386977de) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [8cf96a6d0b](https://linux-hardware.org/?probe=8cf96a6d0b) | Oct 14, 2022 |
| Dell          | Vostro 15 5510              | [a68e7df338](https://linux-hardware.org/?probe=a68e7df338) | Oct 14, 2022 |
| Dell          | Latitude E6330              | [1b1f5a27f7](https://linux-hardware.org/?probe=1b1f5a27f7) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Dell          | Inspiron 5502               | [41fb5ecf07](https://linux-hardware.org/?probe=41fb5ecf07) | Oct 14, 2022 |
| MSI           | MS-N014                     | [87e6e540be](https://linux-hardware.org/?probe=87e6e540be) | Oct 14, 2022 |
| Google        | Robo                        | [d070697e72](https://linux-hardware.org/?probe=d070697e72) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a1b02901a1](https://linux-hardware.org/?probe=a1b02901a1) | Oct 13, 2022 |
| Acer          | Swift SF314-57              | [a0f4cd454d](https://linux-hardware.org/?probe=a0f4cd454d) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dfc5a5f754](https://linux-hardware.org/?probe=dfc5a5f754) | Oct 13, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [e560a29570](https://linux-hardware.org/?probe=e560a29570) | Oct 12, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [00d174fcf4](https://linux-hardware.org/?probe=00d174fcf4) | Oct 12, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ccee0b66d9](https://linux-hardware.org/?probe=ccee0b66d9) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [22904f1270](https://linux-hardware.org/?probe=22904f1270) | Oct 12, 2022 |
| MSI           | GE72 2QF                    | [ecd8555f97](https://linux-hardware.org/?probe=ecd8555f97) | Oct 12, 2022 |
| Thomson       | N14C4WH64                   | [bfc16b9ded](https://linux-hardware.org/?probe=bfc16b9ded) | Oct 12, 2022 |
| ASUSTek       | N53Jg                       | [0b4302ed6c](https://linux-hardware.org/?probe=0b4302ed6c) | Oct 11, 2022 |
| Apple         | MacBookAir7,2               | [8b4c66e10a](https://linux-hardware.org/?probe=8b4c66e10a) | Oct 11, 2022 |
| Dell          | Precision 7720              | [2252c7bd79](https://linux-hardware.org/?probe=2252c7bd79) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Apple         | MacBook5,2                  | [4687cf8900](https://linux-hardware.org/?probe=4687cf8900) | Oct 10, 2022 |
| Toshiba       | Satellite A100              | [f280857c1c](https://linux-hardware.org/?probe=f280857c1c) | Oct 09, 2022 |
| Dell          | Inspiron 14 5420            | [d9f937a8c4](https://linux-hardware.org/?probe=d9f937a8c4) | Oct 09, 2022 |
| HP            | Pavilion TS 11              | [1a6ea38863](https://linux-hardware.org/?probe=1a6ea38863) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [7785f0ebfb](https://linux-hardware.org/?probe=7785f0ebfb) | Oct 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [487fd1959f](https://linux-hardware.org/?probe=487fd1959f) | Oct 08, 2022 |
| MSI           | Prestige 14Evo A11M         | [68137e0e8d](https://linux-hardware.org/?probe=68137e0e8d) | Oct 07, 2022 |
| HP            | Pavilion dv7                | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [e6eac5c882](https://linux-hardware.org/?probe=e6eac5c882) | Oct 07, 2022 |
| Lenovo        | ThinkPad L512 44444WG       | [b27c3b70a7](https://linux-hardware.org/?probe=b27c3b70a7) | Oct 07, 2022 |
| Shanghai Z... | ZXE CRB                     | [479f3d24f2](https://linux-hardware.org/?probe=479f3d24f2) | Oct 06, 2022 |
| Shanghai Z... | ZXE CRB                     | [5bacb77f8b](https://linux-hardware.org/?probe=5bacb77f8b) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [1b09c0a820](https://linux-hardware.org/?probe=1b09c0a820) | Oct 06, 2022 |
| HP            | EliteBook 8470p             | [0fa7893206](https://linux-hardware.org/?probe=0fa7893206) | Oct 06, 2022 |
| Acer          | Predator PH315-53           | [0f3387ce35](https://linux-hardware.org/?probe=0f3387ce35) | Oct 06, 2022 |
| Toshiba       | Satellite L40               | [0f3e9273a6](https://linux-hardware.org/?probe=0f3e9273a6) | Oct 06, 2022 |
| Google        | Akemi                       | [5a165f46bc](https://linux-hardware.org/?probe=5a165f46bc) | Oct 05, 2022 |
| HP            | EliteBook 8570p             | [3079a45a56](https://linux-hardware.org/?probe=3079a45a56) | Oct 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [96b4cda722](https://linux-hardware.org/?probe=96b4cda722) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [02d4090cce](https://linux-hardware.org/?probe=02d4090cce) | Oct 05, 2022 |
| HP            | EliteBook 8460p             | [4f037d4c3d](https://linux-hardware.org/?probe=4f037d4c3d) | Oct 05, 2022 |
| Toshiba       | NB505                       | [9de39780b5](https://linux-hardware.org/?probe=9de39780b5) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [dea0d04059](https://linux-hardware.org/?probe=dea0d04059) | Oct 05, 2022 |
| Acer          | Aspire A315-23G             | [ab3508b938](https://linux-hardware.org/?probe=ab3508b938) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | EliteBook 8460p             | [8b9d1152e4](https://linux-hardware.org/?probe=8b9d1152e4) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [8631c6f717](https://linux-hardware.org/?probe=8631c6f717) | Oct 04, 2022 |
| MSI           | GF65 Thin 10SDR             | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| HP            | EliteBook 735 G6            | [c3f86b0e1a](https://linux-hardware.org/?probe=c3f86b0e1a) | Oct 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | [33b42f3ed1](https://linux-hardware.org/?probe=33b42f3ed1) | Oct 04, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [5b2fac59ea](https://linux-hardware.org/?probe=5b2fac59ea) | Oct 04, 2022 |
| Shanghai Z... | ZXE CRB                     | [b981993409](https://linux-hardware.org/?probe=b981993409) | Oct 04, 2022 |
| Lenovo        | ThinkPad Twist 20C41A3      | [3da96ac399](https://linux-hardware.org/?probe=3da96ac399) | Oct 04, 2022 |
| Acer          | Aspire A315-56              | [e799907aba](https://linux-hardware.org/?probe=e799907aba) | Oct 04, 2022 |
| Dell          | Precision M4800             | [1099761dca](https://linux-hardware.org/?probe=1099761dca) | Oct 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [31fa8b62ff](https://linux-hardware.org/?probe=31fa8b62ff) | Oct 04, 2022 |
| UNOWHY        | Y13G010S4EI                 | [38f5b56e5d](https://linux-hardware.org/?probe=38f5b56e5d) | Oct 04, 2022 |
| Dell          | Inspiron 5590               | [ed3bf1e99b](https://linux-hardware.org/?probe=ed3bf1e99b) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [81ac41d8b9](https://linux-hardware.org/?probe=81ac41d8b9) | Oct 03, 2022 |
| Dell          | Latitude 2110               | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| ASUSTek       | 1225B                       | [9bb2d54ca7](https://linux-hardware.org/?probe=9bb2d54ca7) | Oct 03, 2022 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [1427143cf0](https://linux-hardware.org/?probe=1427143cf0) | Oct 03, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [64f2393fde](https://linux-hardware.org/?probe=64f2393fde) | Oct 03, 2022 |
| Toshiba       | Satellite L855              | [66e22581f7](https://linux-hardware.org/?probe=66e22581f7) | Oct 03, 2022 |
| Dell          | Precision 3570              | [f4f047eecf](https://linux-hardware.org/?probe=f4f047eecf) | Oct 03, 2022 |
| Apple         | MacBookAir7,2               | [ae39aea3e9](https://linux-hardware.org/?probe=ae39aea3e9) | Oct 02, 2022 |
| Lenovo        | ThinkPad T460s 20F90060G... | [8d17d38142](https://linux-hardware.org/?probe=8d17d38142) | Oct 02, 2022 |
| ASUSTek       | X71Q                        | [830c8ab6d2](https://linux-hardware.org/?probe=830c8ab6d2) | Oct 02, 2022 |
| Toshiba       | Satellite L45               | [79ff097329](https://linux-hardware.org/?probe=79ff097329) | Oct 02, 2022 |
| Acer          | Aspire A715-41G             | [1a473e9809](https://linux-hardware.org/?probe=1a473e9809) | Oct 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9cd72ed352](https://linux-hardware.org/?probe=9cd72ed352) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [5bc67115db](https://linux-hardware.org/?probe=5bc67115db) | Oct 01, 2022 |
| HP            | Pavilion TS 11              | [4758af490a](https://linux-hardware.org/?probe=4758af490a) | Oct 01, 2022 |
| Lenovo        | ThinkPad T440s 20AQCTO1W... | [fbe1e53387](https://linux-hardware.org/?probe=fbe1e53387) | Oct 01, 2022 |
| Lenovo        | ThinkPad L380 20M5SSIN11    | [0cad79b1f7](https://linux-hardware.org/?probe=0cad79b1f7) | Sep 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [786e0c1f5d](https://linux-hardware.org/?probe=786e0c1f5d) | Sep 30, 2022 |
| HP            | Pavilion Notebook           | [ee72cbd627](https://linux-hardware.org/?probe=ee72cbd627) | Sep 29, 2022 |
| HP            | Compaq nx6325 (EY344EA#A... | [8808f98c62](https://linux-hardware.org/?probe=8808f98c62) | Sep 29, 2022 |
| ASUSTek       | N53SV                       | [6652e85ddd](https://linux-hardware.org/?probe=6652e85ddd) | Sep 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS43J0V    | [0453cd781f](https://linux-hardware.org/?probe=0453cd781f) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Dell          | Vostro 15 5510              | [973307d03b](https://linux-hardware.org/?probe=973307d03b) | Sep 28, 2022 |
| Acer          | Aspire A315-23G             | [3eaaf54d1b](https://linux-hardware.org/?probe=3eaaf54d1b) | Sep 28, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [ca9c7bf57b](https://linux-hardware.org/?probe=ca9c7bf57b) | Sep 28, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [2d7ce63bce](https://linux-hardware.org/?probe=2d7ce63bce) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Dell          | Inspiron 15-3567            | [9ae6efbc0f](https://linux-hardware.org/?probe=9ae6efbc0f) | Sep 25, 2022 |
| HUAWEI        | RLEF-XX                     | [7bab2cbc57](https://linux-hardware.org/?probe=7bab2cbc57) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Dell          | Inspiron 14 5425            | [209be443ac](https://linux-hardware.org/?probe=209be443ac) | Sep 24, 2022 |
| ASUSTek       | G501VW                      | [550d6e5438](https://linux-hardware.org/?probe=550d6e5438) | Sep 24, 2022 |
| Lenovo        | ThinkPad T530 23595JU       | [0adb7bc0b1](https://linux-hardware.org/?probe=0adb7bc0b1) | Sep 24, 2022 |
| VIT           | P2402                       | [0242b6bb07](https://linux-hardware.org/?probe=0242b6bb07) | Sep 24, 2022 |
| Samsung       | 550XBE/350XBE               | [dec88709ee](https://linux-hardware.org/?probe=dec88709ee) | Sep 23, 2022 |
| Google        | Robo                        | [4772493ae3](https://linux-hardware.org/?probe=4772493ae3) | Sep 23, 2022 |
| Samsung       | 550XBE/350XBE               | [e17fb419bd](https://linux-hardware.org/?probe=e17fb419bd) | Sep 23, 2022 |
| MECHREVO      | Jiaolong Series GM5ZG0O     | [077c05c78d](https://linux-hardware.org/?probe=077c05c78d) | Sep 23, 2022 |
| Acer          | Aspire ES1-732              | [d6ccc5301b](https://linux-hardware.org/?probe=d6ccc5301b) | Sep 23, 2022 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [f77dda559d](https://linux-hardware.org/?probe=f77dda559d) | Sep 23, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [412296c83f](https://linux-hardware.org/?probe=412296c83f) | Sep 22, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [db6f733994](https://linux-hardware.org/?probe=db6f733994) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [21ba0d8f46](https://linux-hardware.org/?probe=21ba0d8f46) | Sep 22, 2022 |
| Lenovo        | ThinkPad T420 4236WS7       | [0c4627555a](https://linux-hardware.org/?probe=0c4627555a) | Sep 22, 2022 |
| Dell          | Inspiron 5537               | [7e3170527c](https://linux-hardware.org/?probe=7e3170527c) | Sep 22, 2022 |
| HP            | Notebook                    | [18b9221add](https://linux-hardware.org/?probe=18b9221add) | Sep 22, 2022 |
| Toshiba       | Satellite P745              | [963d04c729](https://linux-hardware.org/?probe=963d04c729) | Sep 22, 2022 |
| Dell          | Vostro 15 5510              | [630b3877c4](https://linux-hardware.org/?probe=630b3877c4) | Sep 22, 2022 |
| MSI           | GS60 2PE                    | [1aaaa99706](https://linux-hardware.org/?probe=1aaaa99706) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen2... | [87a3d977b1](https://linux-hardware.org/?probe=87a3d977b1) | Sep 22, 2022 |
| Avell High... | B.ON                        | [95c7e35ef3](https://linux-hardware.org/?probe=95c7e35ef3) | Sep 22, 2022 |
| Lenovo        | G50-45 80E3                 | [41af175db4](https://linux-hardware.org/?probe=41af175db4) | Sep 21, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Avell High... | B.ON                        | [aaebcf57bb](https://linux-hardware.org/?probe=aaebcf57bb) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| Dell          | Precision 7540              | [fb7472fe87](https://linux-hardware.org/?probe=fb7472fe87) | Sep 21, 2022 |
| Dell          | Inspiron MP061              | [8e6955cbf6](https://linux-hardware.org/?probe=8e6955cbf6) | Sep 21, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [0ada4a5b83](https://linux-hardware.org/?probe=0ada4a5b83) | Sep 20, 2022 |
| Lenovo        | ThinkPad T490 20N2001YUS    | [5861c90514](https://linux-hardware.org/?probe=5861c90514) | Sep 20, 2022 |
| HP            | EliteBook 840 14 inch G9... | [450a86c900](https://linux-hardware.org/?probe=450a86c900) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad X260 20F5003EMB    | [302eacc4ff](https://linux-hardware.org/?probe=302eacc4ff) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad SL400 2743AQC      | [beb74c65cc](https://linux-hardware.org/?probe=beb74c65cc) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HP            | 15                          | [50f64276d5](https://linux-hardware.org/?probe=50f64276d5) | Sep 19, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [0f049ae5d6](https://linux-hardware.org/?probe=0f049ae5d6) | Sep 19, 2022 |
| HP            | 15                          | [d74a694eb8](https://linux-hardware.org/?probe=d74a694eb8) | Sep 19, 2022 |
| HP            | G42                         | [3f584eb1af](https://linux-hardware.org/?probe=3f584eb1af) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Panasonic     | CF-53JAWZYDE                | [f8b1ca10d1](https://linux-hardware.org/?probe=f8b1ca10d1) | Sep 19, 2022 |
| Acer          | Aspire A315-23G             | [9e3edc5b61](https://linux-hardware.org/?probe=9e3edc5b61) | Sep 18, 2022 |
| Lenovo        | IdeaPad 720s-13ARR 81BR     | [fa45602fc5](https://linux-hardware.org/?probe=fa45602fc5) | Sep 18, 2022 |
| Lenovo        | ThinkPad P50 20EQS1WW00     | [b94564300a](https://linux-hardware.org/?probe=b94564300a) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [bbb0a5f1a1](https://linux-hardware.org/?probe=bbb0a5f1a1) | Sep 18, 2022 |
| Dell          | Latitude 3310               | [4de8502362](https://linux-hardware.org/?probe=4de8502362) | Sep 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [87c3b99589](https://linux-hardware.org/?probe=87c3b99589) | Sep 18, 2022 |
| Acer          | Aspire A315-23G             | [3de0a6e725](https://linux-hardware.org/?probe=3de0a6e725) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [6c5b0c0659](https://linux-hardware.org/?probe=6c5b0c0659) | Sep 17, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [1fa176a244](https://linux-hardware.org/?probe=1fa176a244) | Sep 17, 2022 |
| Lenovo        | G50-45 80E3                 | [8c355ea88e](https://linux-hardware.org/?probe=8c355ea88e) | Sep 17, 2022 |
| HP            | Notebook                    | [9fcfcab16e](https://linux-hardware.org/?probe=9fcfcab16e) | Sep 17, 2022 |
| HP            | Unknown                     | [e87c925eb0](https://linux-hardware.org/?probe=e87c925eb0) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7e865e8b3f](https://linux-hardware.org/?probe=7e865e8b3f) | Sep 16, 2022 |
| Aquarius      | NS585                       | [84054aaa40](https://linux-hardware.org/?probe=84054aaa40) | Sep 16, 2022 |
| HP            | Stream Laptop 11-y0XX       | [b030fff6bb](https://linux-hardware.org/?probe=b030fff6bb) | Sep 16, 2022 |
| Aquarius      | NS585                       | [c4ad74720a](https://linux-hardware.org/?probe=c4ad74720a) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Aquarius      | NS585                       | [400485718e](https://linux-hardware.org/?probe=400485718e) | Sep 16, 2022 |
| Lenovo        | G50-45 80E3                 | [59c06bcd6f](https://linux-hardware.org/?probe=59c06bcd6f) | Sep 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [382325db11](https://linux-hardware.org/?probe=382325db11) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [a1f16914f7](https://linux-hardware.org/?probe=a1f16914f7) | Sep 16, 2022 |
| Aquarius      | NS585                       | [249e3f9a7c](https://linux-hardware.org/?probe=249e3f9a7c) | Sep 16, 2022 |
| Acer          | Aspire A315-23G             | [283a38bb80](https://linux-hardware.org/?probe=283a38bb80) | Sep 16, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [14cbf91f0c](https://linux-hardware.org/?probe=14cbf91f0c) | Sep 15, 2022 |
| Google        | Stout                       | [82b966b9ad](https://linux-hardware.org/?probe=82b966b9ad) | Sep 15, 2022 |
| Aquarius      | NS585                       | [e86929e9a3](https://linux-hardware.org/?probe=e86929e9a3) | Sep 15, 2022 |
| Aquarius      | NS585                       | [a1568949cd](https://linux-hardware.org/?probe=a1568949cd) | Sep 15, 2022 |
| Aquarius      | NS585                       | [feedc8a0ba](https://linux-hardware.org/?probe=feedc8a0ba) | Sep 15, 2022 |
| Aquarius      | NS585                       | [eb2906fdc5](https://linux-hardware.org/?probe=eb2906fdc5) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [3bf32bc004](https://linux-hardware.org/?probe=3bf32bc004) | Sep 15, 2022 |
| Lenovo        | ThinkPad T430 2347G4U       | [aa5d8a2fc6](https://linux-hardware.org/?probe=aa5d8a2fc6) | Sep 15, 2022 |
| Positivo      | Mobile                      | [f0f7335929](https://linux-hardware.org/?probe=f0f7335929) | Sep 15, 2022 |
| INFINITY      | Unknown                     | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [5bdc2b7041](https://linux-hardware.org/?probe=5bdc2b7041) | Sep 14, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [1e9f44a3da](https://linux-hardware.org/?probe=1e9f44a3da) | Sep 14, 2022 |
| Google        | Terra                       | [9dae30736d](https://linux-hardware.org/?probe=9dae30736d) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8fb883495e](https://linux-hardware.org/?probe=8fb883495e) | Sep 14, 2022 |
| Aquarius      | NS585                       | [2c51e9e9c2](https://linux-hardware.org/?probe=2c51e9e9c2) | Sep 14, 2022 |
| Aquarius      | NS585                       | [54a3f9eec9](https://linux-hardware.org/?probe=54a3f9eec9) | Sep 14, 2022 |
| Aquarius      | NS585                       | [3760a35f01](https://linux-hardware.org/?probe=3760a35f01) | Sep 14, 2022 |
| Dell          | Precision 3571              | [72e1a27ea7](https://linux-hardware.org/?probe=72e1a27ea7) | Sep 14, 2022 |
| Aquarius      | NS585                       | [7927c44ef0](https://linux-hardware.org/?probe=7927c44ef0) | Sep 14, 2022 |
| Aquarius      | NS585                       | [eaa0e46c9f](https://linux-hardware.org/?probe=eaa0e46c9f) | Sep 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8935b3f204](https://linux-hardware.org/?probe=8935b3f204) | Sep 14, 2022 |
| Aquarius      | NS585                       | [a904acc9e9](https://linux-hardware.org/?probe=a904acc9e9) | Sep 14, 2022 |
| Aquarius      | NS585                       | [7f883700cf](https://linux-hardware.org/?probe=7f883700cf) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8ef03a6208](https://linux-hardware.org/?probe=8ef03a6208) | Sep 14, 2022 |
| Aquarius      | NS585                       | [c3f844b853](https://linux-hardware.org/?probe=c3f844b853) | Sep 14, 2022 |
| Aquarius      | NS585                       | [0a77a87395](https://linux-hardware.org/?probe=0a77a87395) | Sep 14, 2022 |
| Aquarius      | NS585                       | [344bf802ef](https://linux-hardware.org/?probe=344bf802ef) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | [6be4965b4d](https://linux-hardware.org/?probe=6be4965b4d) | Sep 14, 2022 |
| Aquarius      | NS585                       | [f627c1d051](https://linux-hardware.org/?probe=f627c1d051) | Sep 14, 2022 |
| Aquarius      | NS585                       | [67eca2e394](https://linux-hardware.org/?probe=67eca2e394) | Sep 14, 2022 |
| Aquarius      | NS585                       | [8c8644f284](https://linux-hardware.org/?probe=8c8644f284) | Sep 14, 2022 |
| Aquarius      | NS585                       | [09ca233ab5](https://linux-hardware.org/?probe=09ca233ab5) | Sep 14, 2022 |
| Dell          | Latitude E7250              | [80a2e50cfc](https://linux-hardware.org/?probe=80a2e50cfc) | Sep 14, 2022 |
| Aquarius      | NS585                       | [df1a5c5ca1](https://linux-hardware.org/?probe=df1a5c5ca1) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [b8665b7aed](https://linux-hardware.org/?probe=b8665b7aed) | Sep 14, 2022 |
| ASUSTek       | K54HR                       | [e65b9d439e](https://linux-hardware.org/?probe=e65b9d439e) | Sep 14, 2022 |
| Acer          | Extensa 215-32              | [22c2adf69b](https://linux-hardware.org/?probe=22c2adf69b) | Sep 14, 2022 |
| Dell          | Inspiron 5585               | [2f391f6793](https://linux-hardware.org/?probe=2f391f6793) | Sep 14, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | [c8994c7912](https://linux-hardware.org/?probe=c8994c7912) | Sep 14, 2022 |
| Dell          | Inspiron 15-7568            | [c3b834caec](https://linux-hardware.org/?probe=c3b834caec) | Sep 14, 2022 |
| Google        | Terra                       | [a7150f06c7](https://linux-hardware.org/?probe=a7150f06c7) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| Aquarius      | NS585                       | [f76497447f](https://linux-hardware.org/?probe=f76497447f) | Sep 13, 2022 |
| Aquarius      | NS585                       | [042a81998b](https://linux-hardware.org/?probe=042a81998b) | Sep 13, 2022 |
| Aquarius      | NS585                       | [e5078cd5f4](https://linux-hardware.org/?probe=e5078cd5f4) | Sep 13, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7acd0e62aa](https://linux-hardware.org/?probe=7acd0e62aa) | Sep 12, 2022 |
| Google        | Terra                       | [6b591d8c39](https://linux-hardware.org/?probe=6b591d8c39) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| ASUSTek       | X455LD                      | [c31dc64978](https://linux-hardware.org/?probe=c31dc64978) | Sep 12, 2022 |
| Google        | Reks                        | [28f0932e1a](https://linux-hardware.org/?probe=28f0932e1a) | Sep 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00ETGE    | [95a3df06c9](https://linux-hardware.org/?probe=95a3df06c9) | Sep 12, 2022 |
| MSI           | Modern 15 A11M              | [bfc50a32ba](https://linux-hardware.org/?probe=bfc50a32ba) | Sep 12, 2022 |
| MSI           | GS60 2PE                    | [0164cbee91](https://linux-hardware.org/?probe=0164cbee91) | Sep 12, 2022 |
| AXDIA Inte... | MYBOOK 14 PRO               | [3a6e62d846](https://linux-hardware.org/?probe=3a6e62d846) | Sep 12, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [c18f89b2bb](https://linux-hardware.org/?probe=c18f89b2bb) | Sep 11, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [e916989486](https://linux-hardware.org/?probe=e916989486) | Sep 11, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [cd49377ddf](https://linux-hardware.org/?probe=cd49377ddf) | Sep 11, 2022 |
| HP            | G42                         | [092b9e2c38](https://linux-hardware.org/?probe=092b9e2c38) | Sep 11, 2022 |
| HP            | 255 G8 Notebook PC          | [cca78f4488](https://linux-hardware.org/?probe=cca78f4488) | Sep 11, 2022 |
| Lenovo        | ThinkPad L460 20FVS1BC0S    | [e668edf31d](https://linux-hardware.org/?probe=e668edf31d) | Sep 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5a7c8dfacf](https://linux-hardware.org/?probe=5a7c8dfacf) | Sep 10, 2022 |
| Google        | Treeya                      | [d7a00caa63](https://linux-hardware.org/?probe=d7a00caa63) | Sep 10, 2022 |
| Lenovo        | G50-45 80E3                 | [2f4b4e4203](https://linux-hardware.org/?probe=2f4b4e4203) | Sep 10, 2022 |
| ASUSTek       | X200CA                      | [70c2613095](https://linux-hardware.org/?probe=70c2613095) | Sep 09, 2022 |
| Acer          | AO532h                      | [3ea8a4ba38](https://linux-hardware.org/?probe=3ea8a4ba38) | Sep 09, 2022 |
| Toshiba       | Satellite L40               | [ef6556670c](https://linux-hardware.org/?probe=ef6556670c) | Sep 09, 2022 |
| Dell          | Latitude E6330              | [9f2183ce75](https://linux-hardware.org/?probe=9f2183ce75) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [92ae6811fa](https://linux-hardware.org/?probe=92ae6811fa) | Sep 09, 2022 |
| HP            | Compaq 8510w                | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| Dell          | Vostro 3500                 | [d37b0f4483](https://linux-hardware.org/?probe=d37b0f4483) | Sep 08, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [c8f2e1da45](https://linux-hardware.org/?probe=c8f2e1da45) | Sep 08, 2022 |
| Google        | Reks                        | [a171b11595](https://linux-hardware.org/?probe=a171b11595) | Sep 08, 2022 |
| ASUSTek       | UX430UAR                    | [478d0564a6](https://linux-hardware.org/?probe=478d0564a6) | Sep 08, 2022 |
| HP            | ProBook 440 G7              | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| ASUSTek       | X441NA                      | [05b7b3b122](https://linux-hardware.org/?probe=05b7b3b122) | Sep 08, 2022 |
| Acer          | Aspire 5738                 | [141712c674](https://linux-hardware.org/?probe=141712c674) | Sep 07, 2022 |
| Lenovo        | B570e 521524G               | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| HP            | Laptop 17-ca0xxx            | [c65eb0b5c8](https://linux-hardware.org/?probe=c65eb0b5c8) | Sep 07, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [c0e98bf9e5](https://linux-hardware.org/?probe=c0e98bf9e5) | Sep 06, 2022 |
| Aquarius      | NS585                       | [74e50c07d8](https://linux-hardware.org/?probe=74e50c07d8) | Sep 06, 2022 |
| HP            | ENVY 17                     | [63411dc061](https://linux-hardware.org/?probe=63411dc061) | Sep 06, 2022 |
| Lenovo        | ThinkPad P51s 20HB000URT    | [8214e1ba30](https://linux-hardware.org/?probe=8214e1ba30) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480 20L50004GE    | [fefa3f4935](https://linux-hardware.org/?probe=fefa3f4935) | Sep 06, 2022 |
| HP            | ProBook 640 G4              | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [4a2fb0c4c2](https://linux-hardware.org/?probe=4a2fb0c4c2) | Sep 06, 2022 |
| Dell          | Latitude 5530               | [a0896a063c](https://linux-hardware.org/?probe=a0896a063c) | Sep 06, 2022 |
| ASUSTek       | X555LAB                     | [b10937286d](https://linux-hardware.org/?probe=b10937286d) | Sep 06, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [6bd37547d3](https://linux-hardware.org/?probe=6bd37547d3) | Sep 05, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [4c68e17f1a](https://linux-hardware.org/?probe=4c68e17f1a) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [e6117fb016](https://linux-hardware.org/?probe=e6117fb016) | Sep 05, 2022 |
| Dell          | Vostro 15 5510              | [beb1aeb4ad](https://linux-hardware.org/?probe=beb1aeb4ad) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| Unknown       | Unknown                     | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| Dell          | Latitude E6330              | [e4dcf51a84](https://linux-hardware.org/?probe=e4dcf51a84) | Sep 04, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [ea93dfd855](https://linux-hardware.org/?probe=ea93dfd855) | Sep 04, 2022 |
| Lenovo        | ThinkPad X230 232438J       | [dca0e2fa77](https://linux-hardware.org/?probe=dca0e2fa77) | Sep 04, 2022 |
| HP            | Compaq 8510w                | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| PC Special... | 14 Fusion IV                | [dd9ed93b55](https://linux-hardware.org/?probe=dd9ed93b55) | Sep 03, 2022 |
| HP            | Compaq 6910p                | [0165c7d3c6](https://linux-hardware.org/?probe=0165c7d3c6) | Sep 03, 2022 |
| Aquarius      | NS585                       | [b11a34556d](https://linux-hardware.org/?probe=b11a34556d) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [626c1e28b1](https://linux-hardware.org/?probe=626c1e28b1) | Sep 03, 2022 |
| Dell          | Latitude E6330              | [6c7adba5b6](https://linux-hardware.org/?probe=6c7adba5b6) | Sep 03, 2022 |
| Acer          | Aspire A315-23G             | [9a2200f8f8](https://linux-hardware.org/?probe=9a2200f8f8) | Sep 03, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | [c8bf09dd8d](https://linux-hardware.org/?probe=c8bf09dd8d) | Sep 02, 2022 |
| Aquarius      | NS585                       | [86de3c4954](https://linux-hardware.org/?probe=86de3c4954) | Sep 02, 2022 |
| Dell          | XPS 13 9350                 | [dc37712dfc](https://linux-hardware.org/?probe=dc37712dfc) | Sep 02, 2022 |
| Google        | Enguarde                    | [50369de0be](https://linux-hardware.org/?probe=50369de0be) | Sep 01, 2022 |
| Dell          | Latitude E6330              | [179123f301](https://linux-hardware.org/?probe=179123f301) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| Google        | Enguarde                    | [b59a9615cd](https://linux-hardware.org/?probe=b59a9615cd) | Sep 01, 2022 |
| Google        | Enguarde                    | [7acc7436b0](https://linux-hardware.org/?probe=7acc7436b0) | Sep 01, 2022 |
| Google        | Enguarde                    | [671a062f6e](https://linux-hardware.org/?probe=671a062f6e) | Sep 01, 2022 |
| Google        | Enguarde                    | [baabafd42b](https://linux-hardware.org/?probe=baabafd42b) | Sep 01, 2022 |
| Google        | Enguarde                    | [4c1595c83e](https://linux-hardware.org/?probe=4c1595c83e) | Sep 01, 2022 |
| Google        | Enguarde                    | [bb6b28b279](https://linux-hardware.org/?probe=bb6b28b279) | Sep 01, 2022 |
| Google        | Terra                       | [b7940ab738](https://linux-hardware.org/?probe=b7940ab738) | Sep 01, 2022 |
| Google        | Enguarde                    | [0cbe57b975](https://linux-hardware.org/?probe=0cbe57b975) | Sep 01, 2022 |
| Google        | Enguarde                    | [9f20842cc5](https://linux-hardware.org/?probe=9f20842cc5) | Sep 01, 2022 |
| Google        | Enguarde                    | [06969489cc](https://linux-hardware.org/?probe=06969489cc) | Sep 01, 2022 |
| Google        | Enguarde                    | [2b4231258e](https://linux-hardware.org/?probe=2b4231258e) | Sep 01, 2022 |
| Google        | Enguarde                    | [1a0596c60d](https://linux-hardware.org/?probe=1a0596c60d) | Sep 01, 2022 |
| Google        | Enguarde                    | [4dfdb5e364](https://linux-hardware.org/?probe=4dfdb5e364) | Sep 01, 2022 |
| Google        | Enguarde                    | [c6db81251c](https://linux-hardware.org/?probe=c6db81251c) | Sep 01, 2022 |
| Google        | Enguarde                    | [05f112ddb7](https://linux-hardware.org/?probe=05f112ddb7) | Sep 01, 2022 |
| Dell          | Vostro 15 5510              | [e14cc69370](https://linux-hardware.org/?probe=e14cc69370) | Sep 01, 2022 |
| ASUSTek       | K50IJ                       | [10dd5d1e15](https://linux-hardware.org/?probe=10dd5d1e15) | Sep 01, 2022 |
| ASUSTek       | X550CC                      | [21f3eb8b1d](https://linux-hardware.org/?probe=21f3eb8b1d) | Sep 01, 2022 |
| ASUSTek       | UX550VD                     | [a43d53b3b7](https://linux-hardware.org/?probe=a43d53b3b7) | Sep 01, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [7277e72eb4](https://linux-hardware.org/?probe=7277e72eb4) | Aug 31, 2022 |
| Dell          | Latitude E6330              | [b5766d41fa](https://linux-hardware.org/?probe=b5766d41fa) | Aug 31, 2022 |
| HP            | 250 G8 Notebook PC          | [c0a39342c3](https://linux-hardware.org/?probe=c0a39342c3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| HP            | Compaq nc6400 (RU626ET#A... | [e94cb8e943](https://linux-hardware.org/?probe=e94cb8e943) | Aug 30, 2022 |
| Google        | Reks                        | [71f6228c3d](https://linux-hardware.org/?probe=71f6228c3d) | Aug 30, 2022 |
| Google        | Reks                        | [48174b01b3](https://linux-hardware.org/?probe=48174b01b3) | Aug 30, 2022 |
| ASUSTek       | X550CC                      | [f9a9be3a35](https://linux-hardware.org/?probe=f9a9be3a35) | Aug 30, 2022 |
| Google        | Terra                       | [25f50ae6d9](https://linux-hardware.org/?probe=25f50ae6d9) | Aug 30, 2022 |
| Google        | Reks                        | [e768a1940e](https://linux-hardware.org/?probe=e768a1940e) | Aug 30, 2022 |
| Lenovo        | ThinkPad L490 20Q5001YPB    | [daae538154](https://linux-hardware.org/?probe=daae538154) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [30b240a3fe](https://linux-hardware.org/?probe=30b240a3fe) | Aug 29, 2022 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [ddc175428b](https://linux-hardware.org/?probe=ddc175428b) | Aug 29, 2022 |
| Dell          | Latitude 5590               | [e06f40dae9](https://linux-hardware.org/?probe=e06f40dae9) | Aug 29, 2022 |
| Acer          | TravelMate P215-53          | [4ba2e9fbba](https://linux-hardware.org/?probe=4ba2e9fbba) | Aug 29, 2022 |
| ASUSTek       | K55VM                       | [ec5806d544](https://linux-hardware.org/?probe=ec5806d544) | Aug 29, 2022 |
| Lenovo        | ThinkPad T61 7661CV7        | [bc62619f59](https://linux-hardware.org/?probe=bc62619f59) | Aug 28, 2022 |
| Dell          | Latitude 5420               | [0d5e8a9703](https://linux-hardware.org/?probe=0d5e8a9703) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Packard Be... | EasyNote_MX37-U-017         | [abc3dbdaec](https://linux-hardware.org/?probe=abc3dbdaec) | Aug 28, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [a10cbdb73b](https://linux-hardware.org/?probe=a10cbdb73b) | Aug 27, 2022 |
| Lenovo        | ThinkPad T420s 4173RT4      | [562d827323](https://linux-hardware.org/?probe=562d827323) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c155c4b324](https://linux-hardware.org/?probe=c155c4b324) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8231da35ed](https://linux-hardware.org/?probe=8231da35ed) | Aug 27, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2KU0... | [6500c142f5](https://linux-hardware.org/?probe=6500c142f5) | Aug 27, 2022 |
| Medion        | Akoya P2213T                | [c8d10c3b3f](https://linux-hardware.org/?probe=c8d10c3b3f) | Aug 27, 2022 |
| Google        | Terra                       | [717b3cc17f](https://linux-hardware.org/?probe=717b3cc17f) | Aug 26, 2022 |
| Google        | Terra                       | [f9856d813e](https://linux-hardware.org/?probe=f9856d813e) | Aug 26, 2022 |
| ASUSTek       | X455LD                      | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| Lenovo        | ThinkPad T590 20N4001NUS    | [479ef1a89c](https://linux-hardware.org/?probe=479ef1a89c) | Aug 26, 2022 |
| ASUSTek       | M70Vn                       | [2e84d460f5](https://linux-hardware.org/?probe=2e84d460f5) | Aug 26, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [73c598ebe7](https://linux-hardware.org/?probe=73c598ebe7) | Aug 26, 2022 |
| Lenovo        | ThinkPad T400 2768BM2       | [f2d91055c9](https://linux-hardware.org/?probe=f2d91055c9) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS17N0... | [a624a45cda](https://linux-hardware.org/?probe=a624a45cda) | Aug 26, 2022 |
| HP            | ProBook 450 G6              | [def45574de](https://linux-hardware.org/?probe=def45574de) | Aug 26, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [843ee79f1b](https://linux-hardware.org/?probe=843ee79f1b) | Aug 25, 2022 |
| Google        | Terra                       | [72965945d5](https://linux-hardware.org/?probe=72965945d5) | Aug 25, 2022 |
| Google        | Terra                       | [78436fd3bf](https://linux-hardware.org/?probe=78436fd3bf) | Aug 25, 2022 |
| Apple         | MacBookAir7,2               | [b2dc63405c](https://linux-hardware.org/?probe=b2dc63405c) | Aug 25, 2022 |
| Dell          | Inspiron 600m               | [6acc515c79](https://linux-hardware.org/?probe=6acc515c79) | Aug 25, 2022 |
| Dell          | Latitude 3570               | [287cfa2ce8](https://linux-hardware.org/?probe=287cfa2ce8) | Aug 25, 2022 |
| Lenovo        | ThinkPad E490 20N8001EUS    | [1620f0e5ff](https://linux-hardware.org/?probe=1620f0e5ff) | Aug 24, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| Dell          | XPS 15 9500                 | [b3a7cd094e](https://linux-hardware.org/?probe=b3a7cd094e) | Aug 24, 2022 |
| HP            | Laptop 14-dq2xxx            | [bc4f5f8811](https://linux-hardware.org/?probe=bc4f5f8811) | Aug 24, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [8b346ab142](https://linux-hardware.org/?probe=8b346ab142) | Aug 24, 2022 |
| Google        | Reks                        | [043b648dc5](https://linux-hardware.org/?probe=043b648dc5) | Aug 23, 2022 |
| Google        | Terra                       | [b720f3ca23](https://linux-hardware.org/?probe=b720f3ca23) | Aug 23, 2022 |
| Google        | Terra                       | [0fd5baced8](https://linux-hardware.org/?probe=0fd5baced8) | Aug 23, 2022 |
| Dell          | Inspiron 3583               | [dfbced302f](https://linux-hardware.org/?probe=dfbced302f) | Aug 23, 2022 |
| Google        | Terra                       | [92efdef775](https://linux-hardware.org/?probe=92efdef775) | Aug 23, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [e5d3453caa](https://linux-hardware.org/?probe=e5d3453caa) | Aug 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | [91f1311a5f](https://linux-hardware.org/?probe=91f1311a5f) | Aug 23, 2022 |
| Lenovo        | ThinkPad E475 20H40006US    | [801a4be04d](https://linux-hardware.org/?probe=801a4be04d) | Aug 23, 2022 |
| Lenovo        | IdeaPad S540-13API 81XC     | [2ac415ca87](https://linux-hardware.org/?probe=2ac415ca87) | Aug 23, 2022 |
| Dell          | Vostro 15 5510              | [3224d8bdcc](https://linux-hardware.org/?probe=3224d8bdcc) | Aug 23, 2022 |
| VANT          | MOOVE3-15                   | [854b7f42d4](https://linux-hardware.org/?probe=854b7f42d4) | Aug 22, 2022 |
| Acer          | Aspire 5742                 | [6692313edb](https://linux-hardware.org/?probe=6692313edb) | Aug 22, 2022 |
| HP            | Laptop 15-dy2xxx            | [2431fa78d1](https://linux-hardware.org/?probe=2431fa78d1) | Aug 21, 2022 |
| HP            | Laptop 15-dy2xxx            | [532e1358b6](https://linux-hardware.org/?probe=532e1358b6) | Aug 21, 2022 |
| Dell          | XPS 15 9550                 | [8ab7fcb6ff](https://linux-hardware.org/?probe=8ab7fcb6ff) | Aug 21, 2022 |
| Dell          | Precision 7720              | [60ad0b7b3d](https://linux-hardware.org/?probe=60ad0b7b3d) | Aug 21, 2022 |
| Positivo      | Mobile                      | [8678ddf7ac](https://linux-hardware.org/?probe=8678ddf7ac) | Aug 20, 2022 |
| Positivo      | Mobile                      | [d1cf6b8c9e](https://linux-hardware.org/?probe=d1cf6b8c9e) | Aug 20, 2022 |
| VANT          | MOOVE3-15                   | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| Dell          | Vostro 15 5510              | [9f5e59e0b9](https://linux-hardware.org/?probe=9f5e59e0b9) | Aug 20, 2022 |
| MSI           | GF75 Thin 10SCSXR           | [095c130069](https://linux-hardware.org/?probe=095c130069) | Aug 20, 2022 |
| HP            | 620                         | [d3b1eb8b4e](https://linux-hardware.org/?probe=d3b1eb8b4e) | Aug 20, 2022 |
| HP            | Laptop 17-cp0xxx            | [6ba8616656](https://linux-hardware.org/?probe=6ba8616656) | Aug 20, 2022 |
| Google        | Reks                        | [e5cde69ff7](https://linux-hardware.org/?probe=e5cde69ff7) | Aug 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [9e72f598eb](https://linux-hardware.org/?probe=9e72f598eb) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [45bfdfa985](https://linux-hardware.org/?probe=45bfdfa985) | Aug 19, 2022 |
| HP            | 620                         | [259635c419](https://linux-hardware.org/?probe=259635c419) | Aug 19, 2022 |
| ICL           | N7x0WU                      | [7b9c4ad6b1](https://linux-hardware.org/?probe=7b9c4ad6b1) | Aug 19, 2022 |
| HP            | Compaq nx7300 (RH678EA#A... | [6fc01cef23](https://linux-hardware.org/?probe=6fc01cef23) | Aug 19, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e6003f393e](https://linux-hardware.org/?probe=e6003f393e) | Aug 19, 2022 |
| Dell          | Latitude 5500               | [1c7c8639aa](https://linux-hardware.org/?probe=1c7c8639aa) | Aug 19, 2022 |
| Google        | Reks                        | [d09d250717](https://linux-hardware.org/?probe=d09d250717) | Aug 18, 2022 |
| Google        | Terra                       | [4eca7693ab](https://linux-hardware.org/?probe=4eca7693ab) | Aug 18, 2022 |
| Google        | Reks                        | [9fc034e8a0](https://linux-hardware.org/?probe=9fc034e8a0) | Aug 18, 2022 |
| Google        | Terra                       | [aabdca917b](https://linux-hardware.org/?probe=aabdca917b) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | [5b1df1054c](https://linux-hardware.org/?probe=5b1df1054c) | Aug 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [e500790878](https://linux-hardware.org/?probe=e500790878) | Aug 18, 2022 |
| Dell          | Vostro 3405                 | [2b5840062a](https://linux-hardware.org/?probe=2b5840062a) | Aug 18, 2022 |
| Acer          | TravelMate 5620             | [cdb6e6d5d6](https://linux-hardware.org/?probe=cdb6e6d5d6) | Aug 17, 2022 |
| ASUSTek       | K70IJ                       | [99bb1459e7](https://linux-hardware.org/?probe=99bb1459e7) | Aug 17, 2022 |
| Shuttle       | DS437                       | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| Dell          | Precision M6600             | [2e1eaedbc4](https://linux-hardware.org/?probe=2e1eaedbc4) | Aug 17, 2022 |
| HP            | Laptop 14-dq2xxx            | [9cefc23bb3](https://linux-hardware.org/?probe=9cefc23bb3) | Aug 17, 2022 |
| HP            | 255 G5 Notebook PC          | [fdeea5b020](https://linux-hardware.org/?probe=fdeea5b020) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [74e8d1be5b](https://linux-hardware.org/?probe=74e8d1be5b) | Aug 16, 2022 |
| Lenovo        | ThinkPad T450s 20BWS21K0... | [d04d18b241](https://linux-hardware.org/?probe=d04d18b241) | Aug 16, 2022 |
| Dell          | Inspiron 5547               | [84a3ba511d](https://linux-hardware.org/?probe=84a3ba511d) | Aug 16, 2022 |
| PCBOX         | Kant                        | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Google        | Terra                       | [8c5b7a9814](https://linux-hardware.org/?probe=8c5b7a9814) | Aug 15, 2022 |
| Google        | Terra                       | [43c28dadff](https://linux-hardware.org/?probe=43c28dadff) | Aug 15, 2022 |
| Google        | Terra                       | [98b7a9a377](https://linux-hardware.org/?probe=98b7a9a377) | Aug 15, 2022 |
| Google        | Terra                       | [3bfcb2b1b4](https://linux-hardware.org/?probe=3bfcb2b1b4) | Aug 15, 2022 |
| Dell          | Latitude 5420               | [0dec3e9676](https://linux-hardware.org/?probe=0dec3e9676) | Aug 15, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [e32eeecfaa](https://linux-hardware.org/?probe=e32eeecfaa) | Aug 15, 2022 |
| Toshiba       | Satellite P50-B-103         | [39da8f51fe](https://linux-hardware.org/?probe=39da8f51fe) | Aug 14, 2022 |
| HP            | Laptop 14-dq2xxx            | [eeed6b3d08](https://linux-hardware.org/?probe=eeed6b3d08) | Aug 14, 2022 |
| Dell          | Latitude E5430 vPro         | [08f713e80b](https://linux-hardware.org/?probe=08f713e80b) | Aug 13, 2022 |
| Acer          | Aspire A315-23G             | [cdba281a27](https://linux-hardware.org/?probe=cdba281a27) | Aug 13, 2022 |
| Apple         | MacBookPro12,1              | [8b417889e1](https://linux-hardware.org/?probe=8b417889e1) | Aug 13, 2022 |
| HP            | Presario CQ56               | [48dfc2da91](https://linux-hardware.org/?probe=48dfc2da91) | Aug 13, 2022 |
| HONOR         | BMH-WCX9                    | [188bfa465d](https://linux-hardware.org/?probe=188bfa465d) | Aug 13, 2022 |
| Dell          | Latitude E6330              | [b48c021700](https://linux-hardware.org/?probe=b48c021700) | Aug 13, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [94eb72e4ac](https://linux-hardware.org/?probe=94eb72e4ac) | Aug 13, 2022 |
| HP            | Pavilion Notebook           | [3dd4d44be4](https://linux-hardware.org/?probe=3dd4d44be4) | Aug 12, 2022 |
| Acer          | Aspire A114-33              | [471a1ec71e](https://linux-hardware.org/?probe=471a1ec71e) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [ed37ad46b6](https://linux-hardware.org/?probe=ed37ad46b6) | Aug 12, 2022 |
| HONOR         | BMH-WCX9                    | [2fab557514](https://linux-hardware.org/?probe=2fab557514) | Aug 12, 2022 |
| Dell          | XPS 13 9350                 | [6f828c5743](https://linux-hardware.org/?probe=6f828c5743) | Aug 12, 2022 |
| Apple         | MacBookAir7,2               | [c38e80ade4](https://linux-hardware.org/?probe=c38e80ade4) | Aug 11, 2022 |
| HP            | ENVY 17 Leap Motion SE N... | [efd4ec3ee7](https://linux-hardware.org/?probe=efd4ec3ee7) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | [4d052b34a7](https://linux-hardware.org/?probe=4d052b34a7) | Aug 11, 2022 |
| ASUSTek       | UX410UAR                    | [9de54b22a8](https://linux-hardware.org/?probe=9de54b22a8) | Aug 11, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [d64d35a05d](https://linux-hardware.org/?probe=d64d35a05d) | Aug 11, 2022 |
| Dell          | Latitude 6430U              | [d21ca8c2e6](https://linux-hardware.org/?probe=d21ca8c2e6) | Aug 11, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | [23b946fc6d](https://linux-hardware.org/?probe=23b946fc6d) | Aug 11, 2022 |
| Toshiba       | Satellite M645              | [9fa1e00c24](https://linux-hardware.org/?probe=9fa1e00c24) | Aug 10, 2022 |
| Toshiba       | TECRA R950                  | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X751LJ                      | [5c3767ccc2](https://linux-hardware.org/?probe=5c3767ccc2) | Aug 10, 2022 |
| Dell          | Latitude E6420              | [7c907987cb](https://linux-hardware.org/?probe=7c907987cb) | Aug 10, 2022 |
| GPU Compan... | GWTC116-2                   | [b92ffbefad](https://linux-hardware.org/?probe=b92ffbefad) | Aug 09, 2022 |
| ASUSTek       | X751LJ                      | [e35689c8f1](https://linux-hardware.org/?probe=e35689c8f1) | Aug 09, 2022 |
| Acer          | Aspire A515-56              | [21fdf57c32](https://linux-hardware.org/?probe=21fdf57c32) | Aug 09, 2022 |
| HP            | EliteBook 725 G3            | [7e36a68724](https://linux-hardware.org/?probe=7e36a68724) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Alienware     | m15 R6                      | [675208eaec](https://linux-hardware.org/?probe=675208eaec) | Aug 09, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| Dell          | Latitude E7450              | [f2d8a030f4](https://linux-hardware.org/?probe=f2d8a030f4) | Aug 08, 2022 |
| HP            | EliteBook 725 G3            | [e48eff307c](https://linux-hardware.org/?probe=e48eff307c) | Aug 08, 2022 |
| Acer          | Aspire A315-23G             | [46b74e61f0](https://linux-hardware.org/?probe=46b74e61f0) | Aug 08, 2022 |
| Dell          | Latitude E6430              | [17d0fce9e5](https://linux-hardware.org/?probe=17d0fce9e5) | Aug 08, 2022 |
| HP            | Laptop 15-ef2xxx            | [b1420b630f](https://linux-hardware.org/?probe=b1420b630f) | Aug 07, 2022 |
| Acer          | Aspire 5738                 | [31d08ab231](https://linux-hardware.org/?probe=31d08ab231) | Aug 07, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [19b3f7fe4b](https://linux-hardware.org/?probe=19b3f7fe4b) | Aug 07, 2022 |
| Dell          | Precision 7720              | [db2f868372](https://linux-hardware.org/?probe=db2f868372) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0564acfb6c](https://linux-hardware.org/?probe=0564acfb6c) | Aug 07, 2022 |
| SANTECH       | NHx0DB,DE                   | [1eba623e90](https://linux-hardware.org/?probe=1eba623e90) | Aug 06, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [53c997fe1f](https://linux-hardware.org/?probe=53c997fe1f) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [d5786b75a3](https://linux-hardware.org/?probe=d5786b75a3) | Aug 05, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [24d8a6228c](https://linux-hardware.org/?probe=24d8a6228c) | Aug 05, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [83c6e58e51](https://linux-hardware.org/?probe=83c6e58e51) | Aug 05, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [d12e654f35](https://linux-hardware.org/?probe=d12e654f35) | Aug 05, 2022 |
| HP            | ProBook 430 G5              | [72a09e7b69](https://linux-hardware.org/?probe=72a09e7b69) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [9d032c38b4](https://linux-hardware.org/?probe=9d032c38b4) | Aug 05, 2022 |
| ASUSTek       | X550CC                      | [433126127b](https://linux-hardware.org/?probe=433126127b) | Aug 05, 2022 |
| Acer          | Aspire 5315                 | [7be46d4930](https://linux-hardware.org/?probe=7be46d4930) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [87d90381e1](https://linux-hardware.org/?probe=87d90381e1) | Aug 04, 2022 |
| HP            | EliteBook 8460p             | [7948505598](https://linux-hardware.org/?probe=7948505598) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e74155922c](https://linux-hardware.org/?probe=e74155922c) | Aug 04, 2022 |
| Acer          | AO532h                      | [9a35f25fba](https://linux-hardware.org/?probe=9a35f25fba) | Aug 04, 2022 |
| Acer          | Aspire A315-23G             | [52e4d5e94f](https://linux-hardware.org/?probe=52e4d5e94f) | Aug 03, 2022 |
| Google        | Droid                       | [15d4518ba0](https://linux-hardware.org/?probe=15d4518ba0) | Aug 03, 2022 |
| ASUSTek       | X756UQK                     | [97b2316a06](https://linux-hardware.org/?probe=97b2316a06) | Aug 03, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [94ccc2e14f](https://linux-hardware.org/?probe=94ccc2e14f) | Aug 03, 2022 |
| Razer         | Blade 14 - RZ09-0370        | [0bf365f767](https://linux-hardware.org/?probe=0bf365f767) | Aug 02, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| HP            | 255 G3                      | [46ad188006](https://linux-hardware.org/?probe=46ad188006) | Aug 02, 2022 |
| HUAWEI        | CREM-WXX9                   | [9e48213e39](https://linux-hardware.org/?probe=9e48213e39) | Aug 02, 2022 |
| HUAWEI        | CREM-WXX9                   | [2efb41280c](https://linux-hardware.org/?probe=2efb41280c) | Aug 02, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [743422e837](https://linux-hardware.org/?probe=743422e837) | Aug 02, 2022 |
| Dell          | Latitude 5490               | [78bde5c7cc](https://linux-hardware.org/?probe=78bde5c7cc) | Aug 02, 2022 |
| Dell          | Inspiron 13-7378            | [c08447d945](https://linux-hardware.org/?probe=c08447d945) | Aug 01, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [ae2fa8b811](https://linux-hardware.org/?probe=ae2fa8b811) | Aug 01, 2022 |
| Dell          | Latitude 7420               | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Toshiba       | TECRA Z40-C                 | [9612659f60](https://linux-hardware.org/?probe=9612659f60) | Aug 01, 2022 |
| Apple         | MacBookPro11,5              | [24ccaddbf8](https://linux-hardware.org/?probe=24ccaddbf8) | Jul 31, 2022 |
| HP            | ProBook 4310s               | [d15b493637](https://linux-hardware.org/?probe=d15b493637) | Jul 31, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [9b362907fc](https://linux-hardware.org/?probe=9b362907fc) | Jul 30, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [61aed5ab55](https://linux-hardware.org/?probe=61aed5ab55) | Jul 30, 2022 |
| Apple         | MacBookPro11,5              | [1b94bd5797](https://linux-hardware.org/?probe=1b94bd5797) | Jul 29, 2022 |
| Acer          | AO756                       | [8203ac54d7](https://linux-hardware.org/?probe=8203ac54d7) | Jul 29, 2022 |
| ASUSTek       | GL553VE                     | [0bbcd152c5](https://linux-hardware.org/?probe=0bbcd152c5) | Jul 29, 2022 |
| Samsung       | R505                        | [4f92cf3c93](https://linux-hardware.org/?probe=4f92cf3c93) | Jul 29, 2022 |
| Lenovo        | ThinkPad L480 20LS002CPB    | [35764371d6](https://linux-hardware.org/?probe=35764371d6) | Jul 29, 2022 |
| Dell          | Latitude E5500              | [ba214335da](https://linux-hardware.org/?probe=ba214335da) | Jul 28, 2022 |
| HP            | Compaq 8510p                | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Lenovo        | S21e-20 80M4                | [bec71c2353](https://linux-hardware.org/?probe=bec71c2353) | Jul 27, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [87f0eb95eb](https://linux-hardware.org/?probe=87f0eb95eb) | Jul 27, 2022 |
| HP            | Stream Notebook PC 11       | [e3c8a52e5b](https://linux-hardware.org/?probe=e3c8a52e5b) | Jul 27, 2022 |
| Acer          | Aspire A515-43              | [d378021961](https://linux-hardware.org/?probe=d378021961) | Jul 26, 2022 |
| ASUSTek       | ZenBook UX325UA             | [587ea51239](https://linux-hardware.org/?probe=587ea51239) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [8aa5207a61](https://linux-hardware.org/?probe=8aa5207a61) | Jul 26, 2022 |
| Notebook      | V15x_V17xPNKPNJPNH          | [fc5bf3cb22](https://linux-hardware.org/?probe=fc5bf3cb22) | Jul 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian_11/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.10.0-8-amd64         | 578       | 19.81%  |
| 5.10.0-10-amd64        | 489       | 16.76%  |
| 5.10.0-7-amd64         | 171       | 5.86%   |
| 5.10.0-9-amd64         | 170       | 5.83%   |
| 5.10.0-18-amd64        | 167       | 5.72%   |
| 5.10.0-16-amd64        | 166       | 5.69%   |
| 5.10.0-19-amd64        | 154       | 5.28%   |
| 5.10.0-13-amd64        | 149       | 5.11%   |
| 5.10.0-11-amd64        | 102       | 3.5%    |
| 5.10.0-14-amd64        | 78        | 2.67%   |
| 5.10.0-17-amd64        | 72        | 2.47%   |
| 5.10.0-20-amd64        | 53        | 1.82%   |
| 5.10.0-15-amd64        | 46        | 1.58%   |
| 5.10.0-12-amd64        | 40        | 1.37%   |
| 5.10.0-6-amd64         | 28        | 0.96%   |
| 5.10.0-2-amd64         | 28        | 0.96%   |
| 5.10.0-13-686-pae      | 26        | 0.89%   |
| 5.18.0-0.deb11.4-amd64 | 19        | 0.65%   |
| 6.0.0-0.deb11.2-amd64  | 17        | 0.58%   |
| 5.14.0-0.bpo.2-amd64   | 17        | 0.58%   |
| 5.15.0-2-amd64         | 14        | 0.48%   |
| 5.10.0-3-amd64         | 13        | 0.45%   |
| 5.16.0-0.bpo.4-amd64   | 12        | 0.41%   |
| 5.10.0-9-686-pae       | 9         | 0.31%   |
| 5.10.0-8-686-pae       | 9         | 0.31%   |
| 5.10.0-13-686          | 9         | 0.31%   |
| 5.19.0-0.deb11.2-amd64 | 8         | 0.27%   |
| 5.18.0-0.bpo.1-amd64   | 8         | 0.27%   |
| 5.15.0-0.bpo.2-amd64   | 8         | 0.27%   |
| 5.19.0-2-amd64         | 7         | 0.24%   |
| 5.10.0-9-686           | 7         | 0.24%   |
| 5.19.0-1-amd64         | 6         | 0.21%   |
| 5.18.0-2-amd64         | 6         | 0.21%   |
| 5.17.0-1-amd64         | 5         | 0.17%   |
| 5.10.0-5-amd64         | 5         | 0.17%   |
| 5.10.0-4-amd64         | 5         | 0.17%   |
| 5.10.0-19-686          | 5         | 0.17%   |
| 5.10.0-18-686-pae      | 5         | 0.17%   |
| 5.10.0-10-686-pae      | 5         | 0.17%   |
| 5.10.0-1-amd64         | 5         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 2445      | 89.86%  |
| 5.18.0   | 39        | 1.43%   |
| 5.15.0   | 36        | 1.32%   |
| 5.16.0   | 31        | 1.14%   |
| 5.19.0   | 26        | 0.96%   |
| 5.14.0   | 24        | 0.88%   |
| 6.0.0    | 19        | 0.7%    |
| 5.17.0   | 13        | 0.48%   |
| 4.19.0   | 7         | 0.26%   |
| 5.13.19  | 3         | 0.11%   |
| 5.12.0   | 3         | 0.11%   |
| 5.10.60  | 3         | 0.11%   |
| 6.0.2    | 2         | 0.07%   |
| 5.17.5   | 2         | 0.07%   |
| 5.17.11  | 2         | 0.07%   |
| 5.15.35  | 2         | 0.07%   |
| 5.13.8   | 2         | 0.07%   |
| 5.11.0   | 2         | 0.07%   |
| 5.10.109 | 2         | 0.07%   |
| 4.9.0    | 2         | 0.07%   |
| 6.1.0    | 1         | 0.04%   |
| 6.0.11   | 1         | 0.04%   |
| 5.4.157  | 1         | 0.04%   |
| 5.19.9   | 1         | 0.04%   |
| 5.19.10  | 1         | 0.04%   |
| 5.19.1   | 1         | 0.04%   |
| 5.18.6   | 1         | 0.04%   |
| 5.18.15  | 1         | 0.04%   |
| 5.17.4   | 1         | 0.04%   |
| 5.17.14  | 1         | 0.04%   |
| 5.16.5   | 1         | 0.04%   |
| 5.15.8   | 1         | 0.04%   |
| 5.15.75  | 1         | 0.04%   |
| 5.15.7   | 1         | 0.04%   |
| 5.15.6.1 | 1         | 0.04%   |
| 5.15.54  | 1         | 0.04%   |
| 5.15.39  | 1         | 0.04%   |
| 5.15.34  | 1         | 0.04%   |
| 5.15.32  | 1         | 0.04%   |
| 5.15.30  | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 2459      | 90.44%  |
| 5.15    | 49        | 1.8%    |
| 5.18    | 41        | 1.51%   |
| 5.16    | 32        | 1.18%   |
| 5.19    | 29        | 1.07%   |
| 5.14    | 29        | 1.07%   |
| 6.0     | 22        | 0.81%   |
| 5.17    | 19        | 0.7%    |
| 5.13    | 9         | 0.33%   |
| 4.19    | 9         | 0.33%   |
| 5.12    | 6         | 0.22%   |
| 5.11    | 6         | 0.22%   |
| 5.1     | 2         | 0.07%   |
| 4.9     | 2         | 0.07%   |
| 6.1     | 1         | 0.04%   |
| 5.4     | 1         | 0.04%   |
| 5.15.6  | 1         | 0.04%   |
| 3.8     | 1         | 0.04%   |
| 3.10    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2560      | 95.88%  |
| i686   | 107       | 4.01%   |
| armv7l | 3         | 0.11%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Unknown           | 942       | 34.75%  |
| GNOME             | 668       | 24.64%  |
| KDE5              | 322       | 11.88%  |
| XFCE              | 294       | 10.84%  |
| MATE              | 90        | 3.32%   |
| LXDE              | 78        | 2.88%   |
| X-Cinnamon        | 74        | 2.73%   |
| Cinnamon          | 64        | 2.36%   |
| i3                | 37        | 1.36%   |
| LXQt              | 33        | 1.22%   |
| KDE               | 28        | 1.03%   |
| GNOME Flashback   | 23        | 0.85%   |
| lightdm-xsession  | 13        | 0.48%   |
| Openbox           | 10        | 0.37%   |
| trinity           | 6         | 0.22%   |
| GNOME Classic     | 5         | 0.18%   |
| Cutefish          | 3         | 0.11%   |
| Budgie            | 3         | 0.11%   |
| sway              | 2         | 0.07%   |
| ICEWM             | 2         | 0.07%   |
| Enlightenment     | 2         | 0.07%   |
| DWM               | 2         | 0.07%   |
| awesome           | 2         | 0.07%   |
| xmonad            | 1         | 0.04%   |
| x-session-manager | 1         | 0.04%   |
| wmaker-common     | 1         | 0.04%   |
| matchbox          | 1         | 0.04%   |
| jwm               | 1         | 0.04%   |
| fluxbox           | 1         | 0.04%   |
| default           | 1         | 0.04%   |
| Deepin            | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 1233      | 45.53%  |
| Unknown     | 872       | 32.2%   |
| Wayland     | 507       | 18.72%  |
| Tty         | 94        | 3.47%   |
| Web         | 1         | 0.04%   |
| Unspecified | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1254      | 46.36%  |
| GDM     | 568       | 21%     |
| LightDM | 458       | 16.93%  |
| SDDM    | 297       | 10.98%  |
| TDM     | 70        | 2.59%   |
| GDM3    | 50        | 1.85%   |
| XDM     | 4         | 0.15%   |
| SLiM    | 3         | 0.11%   |
| KDM     | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 770       | 28.52%  |
| Unknown | 698       | 25.85%  |
| ru_RU   | 221       | 8.19%   |
| de_DE   | 137       | 5.07%   |
| fr_FR   | 129       | 4.78%   |
| en_GB   | 107       | 3.96%   |
| es_ES   | 92        | 3.41%   |
| it_IT   | 70        | 2.59%   |
| pt_BR   | 59        | 2.19%   |
| pl_PL   | 57        | 2.11%   |
| en_CA   | 29        | 1.07%   |
| es_MX   | 24        | 0.89%   |
| en_AU   | 23        | 0.85%   |
| en_IN   | 19        | 0.7%    |
| zh_CN   | 16        | 0.59%   |
| C       | 16        | 0.59%   |
| es_AR   | 15        | 0.56%   |
| hu_HU   | 12        | 0.44%   |
| es_CL   | 11        | 0.41%   |
| en_IE   | 11        | 0.41%   |
| es_VE   | 10        | 0.37%   |
| sv_SE   | 8         | 0.3%    |
| nl_NL   | 8         | 0.3%    |
| ja_JP   | 8         | 0.3%    |
| de_AT   | 8         | 0.3%    |
| tr_TR   | 7         | 0.26%   |
| pt_PT   | 7         | 0.26%   |
| ko_KR   | 7         | 0.26%   |
| fi_FI   | 7         | 0.26%   |
| nb_NO   | 6         | 0.22%   |
| es_CO   | 6         | 0.22%   |
| en_SG   | 6         | 0.22%   |
| de_CH   | 6         | 0.22%   |
| cs_CZ   | 6         | 0.22%   |
| en_ZA   | 5         | 0.19%   |
| en_NZ   | 5         | 0.19%   |
| zh_TW   | 4         | 0.15%   |
| uk_UA   | 4         | 0.15%   |
| es_PE   | 4         | 0.15%   |
| en_DK   | 4         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1837      | 68.34%  |
| BIOS | 851       | 31.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1608      | 60.09%  |
| Overlay | 949       | 35.46%  |
| Btrfs   | 72        | 2.69%   |
| Xfs     | 24        | 0.9%    |
| Zfs     | 10        | 0.37%   |
| Tmpfs   | 6         | 0.22%   |
| Unknown | 3         | 0.11%   |
| Ext2    | 2         | 0.07%   |
| Rootfs  | 1         | 0.04%   |
| Ext3    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1848      | 68.47%  |
| MBR     | 473       | 17.53%  |
| Unknown | 378       | 14.01%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2093      | 77.78%  |
| Yes       | 598       | 22.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2010      | 74.55%  |
| Yes       | 686       | 25.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Apple                          | 564       | 21.13%  |
| Lenovo                         | 539       | 20.19%  |
| Hewlett-Packard                | 364       | 13.64%  |
| Dell                           | 317       | 11.88%  |
| ASUSTek Computer               | 230       | 8.62%   |
| Acer                           | 145       | 5.43%   |
| Google                         | 124       | 4.65%   |
| Aquarius                       | 44        | 1.65%   |
| MSI                            | 40        | 1.5%    |
| Toshiba                        | 36        | 1.35%   |
| Samsung Electronics            | 29        | 1.09%   |
| HUAWEI                         | 24        | 0.9%    |
| Unknown                        | 18        | 0.67%   |
| Sony                           | 17        | 0.64%   |
| Notebook                       | 14        | 0.52%   |
| Fujitsu                        | 11        | 0.41%   |
| Packard Bell                   | 9         | 0.34%   |
| Panasonic                      | 6         | 0.22%   |
| GPU Company                    | 6         | 0.22%   |
| Clevo                          | 6         | 0.22%   |
| Timi                           | 5         | 0.19%   |
| Medion                         | 5         | 0.19%   |
| IBM                            | 5         | 0.19%   |
| TUXEDO                         | 4         | 0.15%   |
| SLIMBOOK                       | 4         | 0.15%   |
| LG Electronics                 | 4         | 0.15%   |
| Intel                          | 4         | 0.15%   |
| HONOR                          | 4         | 0.15%   |
| Gigabyte Technology            | 4         | 0.15%   |
| Fujitsu Siemens                | 4         | 0.15%   |
| Alienware                      | 4         | 0.15%   |
| System76                       | 3         | 0.11%   |
| Positivo                       | 3         | 0.11%   |
| PC Specialist                  | 3         | 0.11%   |
| Avell High Performance         | 3         | 0.11%   |
| Shanghai Zhaoxin Semiconductor | 2         | 0.07%   |
| Razer                          | 2         | 0.07%   |
| Jumper                         | 2         | 0.07%   |
| Insyde                         | 2         | 0.07%   |
| Getac                          | 2         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Apple MacBook5,2                      | 305       | 11.43%  |
| Apple MacBookAir7,1                   | 77        | 2.88%   |
| Google Enguarde                       | 74        | 2.77%   |
| Apple MacBookAir7,2                   | 74        | 2.77%   |
| Apple MacBook2,1                      | 55        | 2.06%   |
| Aquarius NS585                        | 44        | 1.65%   |
| Lenovo ThinkPad E475 20H40006US       | 24        | 0.9%    |
| Google Terra                          | 23        | 0.86%   |
| Unknown                               | 23        | 0.86%   |
| Apple MacBook4,1                      | 21        | 0.79%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US | 16        | 0.6%    |
| Acer Aspire A315-23                   | 15        | 0.56%   |
| ASUS 1005HA                           | 14        | 0.52%   |
| HP Notebook                           | 13        | 0.49%   |
| Google Reks                           | 11        | 0.41%   |
| HP Pavilion g6                        | 10        | 0.37%   |
| HP EliteBook 8460p                    | 9         | 0.34%   |
| HP Laptop 15-db0xxx                   | 8         | 0.3%    |
| Dell Latitude E7440                   | 8         | 0.3%    |
| HP Laptop 15-bw0xx                    | 7         | 0.26%   |
| HP Pavilion Gaming Laptop 15-ec1xxx   | 6         | 0.22%   |
| HP Laptop 15-db1xxx                   | 6         | 0.22%   |
| HP 250 G7 Notebook PC                 | 6         | 0.22%   |
| Dell XPS 13 9310                      | 6         | 0.22%   |
| Dell Latitude E6330                   | 6         | 0.22%   |
| Dell Inspiron 5100                    | 6         | 0.22%   |
| Apple MacBook7,1                      | 6         | 0.22%   |
| Samsung 300E4C/300E5C/300E7C          | 5         | 0.19%   |
| HP Pavilion Gaming Laptop 15-ec2xxx   | 5         | 0.19%   |
| Dell Latitude E6520                   | 5         | 0.19%   |
| Dell Latitude E6420                   | 5         | 0.19%   |
| Dell Latitude 7480                    | 5         | 0.19%   |
| Acer Aspire A515-56                   | 5         | 0.19%   |
| Lenovo ThinkPad T490 20N2CTO1WW       | 4         | 0.15%   |
| Lenovo IdeaPad S145-15API 81V7        | 4         | 0.15%   |
| Lenovo IdeaPad L340-15API 81LW        | 4         | 0.15%   |
| Lenovo IdeaPad 3 15ALC6 82MF          | 4         | 0.15%   |
| Lenovo B50-30 20382                   | 4         | 0.15%   |
| HUAWEI NBLK-WAX9X                     | 4         | 0.15%   |
| HP Stream Notebook PC 13              | 4         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Lenovo ThinkPad   | 372       | 13.94%  |
| Apple MacBook5    | 305       | 11.43%  |
| Apple MacBookAir7 | 151       | 5.66%   |
| Dell Latitude     | 125       | 4.68%   |
| Acer Aspire       | 98        | 3.67%   |
| Dell Inspiron     | 96        | 3.6%    |
| Lenovo IdeaPad    | 83        | 3.11%   |
| Google Enguarde   | 74        | 2.77%   |
| HP EliteBook      | 65        | 2.44%   |
| HP Laptop         | 57        | 2.14%   |
| HP Pavilion       | 56        | 2.1%    |
| Apple MacBook2    | 55        | 2.06%   |
| HP ProBook        | 45        | 1.69%   |
| Aquarius NS585    | 44        | 1.65%   |
| Dell XPS          | 37        | 1.39%   |
| ASUS VivoBook     | 34        | 1.27%   |
| Toshiba Satellite | 29        | 1.09%   |
| Dell Vostro       | 26        | 0.97%   |
| HP Compaq         | 24        | 0.9%    |
| Google Terra      | 23        | 0.86%   |
| Dell Precision    | 23        | 0.86%   |
| Unknown           | 23        | 0.86%   |
| Apple MacBook4    | 21        | 0.79%   |
| ASUS ZenBook      | 20        | 0.75%   |
| HP 250            | 18        | 0.67%   |
| ASUS ASUS         | 18        | 0.67%   |
| HP ZBook          | 17        | 0.64%   |
| ASUS 1005HA       | 14        | 0.52%   |
| HP Notebook       | 13        | 0.49%   |
| Acer TravelMate   | 12        | 0.45%   |
| Lenovo ThinkBook  | 11        | 0.41%   |
| Lenovo Legion     | 11        | 0.41%   |
| HP ENVY           | 11        | 0.41%   |
| Google Reks       | 11        | 0.41%   |
| Acer Swift        | 11        | 0.41%   |
| Acer Nitro        | 11        | 0.41%   |
| HP 255            | 10        | 0.37%   |
| ASUS ROG          | 10        | 0.37%   |
| HP Stream         | 9         | 0.34%   |
| Fujitsu LIFEBOOK  | 9         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2009    | 367       | 13.75%  |
| 2021    | 269       | 10.08%  |
| 2020    | 264       | 9.89%   |
| 2019    | 263       | 9.85%   |
| 2015    | 177       | 6.63%   |
| 2016    | 174       | 6.52%   |
| 2012    | 146       | 5.47%   |
| 2018    | 144       | 5.4%    |
| 2017    | 136       | 5.1%    |
| 2011    | 129       | 4.83%   |
| 2013    | 117       | 4.38%   |
| 2022    | 96        | 3.6%    |
| 2014    | 95        | 3.56%   |
| 2007    | 92        | 3.45%   |
| 2010    | 78        | 2.92%   |
| 2008    | 71        | 2.66%   |
| 2005    | 17        | 0.64%   |
| 2006    | 16        | 0.6%    |
| 2003    | 8         | 0.3%    |
| 2004    | 6         | 0.22%   |
| Unknown | 3         | 0.11%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2669      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2459      | 91.82%  |
| Enabled  | 219       | 8.18%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2542      | 95.21%  |
| Yes  | 128       | 4.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 725       | 27.02%  |
| 3.01-4.0    | 527       | 19.64%  |
| 1.01-2.0    | 437       | 16.29%  |
| 16.01-24.0  | 374       | 13.94%  |
| 8.01-16.0   | 319       | 11.89%  |
| 32.01-64.0  | 131       | 4.88%   |
| 2.01-3.0    | 56        | 2.09%   |
| 0.51-1.0    | 50        | 1.86%   |
| 64.01-256.0 | 28        | 1.04%   |
| 24.01-32.0  | 24        | 0.89%   |
| 0.01-0.5    | 11        | 0.41%   |
| Unknown     | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1273      | 45.63%  |
| 2.01-3.0   | 507       | 18.17%  |
| 0.51-1.0   | 306       | 10.97%  |
| 4.01-8.0   | 290       | 10.39%  |
| 3.01-4.0   | 250       | 8.96%   |
| 0.01-0.5   | 77        | 2.76%   |
| 8.01-16.0  | 76        | 2.72%   |
| 16.01-24.0 | 5         | 0.18%   |
| 32.01-64.0 | 2         | 0.07%   |
| 24.01-32.0 | 2         | 0.07%   |
| Unknown    | 2         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2231      | 82.81%  |
| 2      | 395       | 14.66%  |
| 3      | 38        | 1.41%   |
| 0      | 18        | 0.67%   |
| 4      | 9         | 0.33%   |
| 5      | 2         | 0.07%   |
| 7      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1709      | 63.94%  |
| Yes       | 964       | 36.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2115      | 79.09%  |
| No        | 559       | 20.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2627      | 98.39%  |
| No        | 43        | 1.61%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2223      | 82.98%  |
| No        | 456       | 17.02%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 975       | 36.41%  |
| Russia      | 235       | 8.78%   |
| Germany     | 197       | 7.36%   |
| France      | 155       | 5.79%   |
| Spain       | 115       | 4.29%   |
| Italy       | 81        | 3.02%   |
| Brazil      | 81        | 3.02%   |
| Poland      | 77        | 2.88%   |
| UK          | 56        | 2.09%   |
| Canada      | 42        | 1.57%   |
| Netherlands | 41        | 1.53%   |
| Mexico      | 33        | 1.23%   |
| Sweden      | 26        | 0.97%   |
| China       | 26        | 0.97%   |
| Australia   | 26        | 0.97%   |
| Argentina   | 26        | 0.97%   |
| India       | 24        | 0.9%    |
| Switzerland | 23        | 0.86%   |
| Ukraine     | 21        | 0.78%   |
| Turkey      | 21        | 0.78%   |
| Austria     | 17        | 0.63%   |
| Norway      | 16        | 0.6%    |
| Portugal    | 15        | 0.56%   |
| Hungary     | 15        | 0.56%   |
| Czechia     | 15        | 0.56%   |
| Greece      | 14        | 0.52%   |
| Chile       | 13        | 0.49%   |
| Venezuela   | 12        | 0.45%   |
| Japan       | 12        | 0.45%   |
| Finland     | 12        | 0.45%   |
| Colombia    | 12        | 0.45%   |
| Belgium     | 12        | 0.45%   |
| Romania     | 11        | 0.41%   |
| Ireland     | 11        | 0.41%   |
| Indonesia   | 11        | 0.41%   |
| Bulgaria    | 10        | 0.37%   |
| Croatia     | 9         | 0.34%   |
| New Zealand | 8         | 0.3%    |
| Thailand    | 7         | 0.26%   |
| South Korea | 7         | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Bangor            | 562       | 20.2%   |
| Dover-Foxcroft    | 229       | 8.23%   |
| Voronezh          | 132       | 4.74%   |
| Seville           | 34        | 1.22%   |
| Paris             | 27        | 0.97%   |
| St Petersburg     | 26        | 0.93%   |
| Madrid            | 22        | 0.79%   |
| Berlin            | 22        | 0.79%   |
| Warsaw            | 17        | 0.61%   |
| Moscow            | 17        | 0.61%   |
| Munich            | 15        | 0.54%   |
| Amsterdam         | 15        | 0.54%   |
| Milan             | 13        | 0.47%   |
| Barcelona         | 13        | 0.47%   |
| Vienna            | 12        | 0.43%   |
| London            | 12        | 0.43%   |
| Blizniew          | 11        | 0.4%    |
| Toronto           | 9         | 0.32%   |
| Sao Paulo         | 9         | 0.32%   |
| Perm              | 9         | 0.32%   |
| Athens            | 9         | 0.32%   |
| Zagreb            | 8         | 0.29%   |
| Sydney            | 8         | 0.29%   |
| Mesa              | 8         | 0.29%   |
| Lyon              | 8         | 0.29%   |
| Istanbul          | 8         | 0.29%   |
| Dublin            | 8         | 0.29%   |
| San Jose          | 7         | 0.25%   |
| Prague            | 7         | 0.25%   |
| Natal             | 7         | 0.25%   |
| Hamburg           | 7         | 0.25%   |
| Frankfurt am Main | 7         | 0.25%   |
| Brisbane          | 7         | 0.25%   |
| Seocho-gu         | 6         | 0.22%   |
| Manchester        | 6         | 0.22%   |
| Helsinki          | 6         | 0.22%   |
| Caracas           | 6         | 0.22%   |
| Bengaluru         | 6         | 0.22%   |
| Bangkok           | 6         | 0.22%   |
| Yekaterinburg     | 5         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 406       | 492    | 13.14%  |
| WDC                       | 312       | 368    | 10.1%   |
| Seagate                   | 247       | 290    | 7.99%   |
| Toshiba                   | 246       | 264    | 7.96%   |
| Fujitsu                   | 239       | 243    | 7.73%   |
| Unknown                   | 222       | 275    | 7.18%   |
| Apple                     | 164       | 192    | 5.31%   |
| Kingston                  | 163       | 200    | 5.28%   |
| SanDisk                   | 132       | 161    | 4.27%   |
| Crucial                   | 117       | 136    | 3.79%   |
| SK hynix                  | 114       | 128    | 3.69%   |
| A-DATA Technology         | 87        | 167    | 2.82%   |
| Hitachi                   | 86        | 99     | 2.78%   |
| Intel                     | 69        | 76     | 2.23%   |
| Micron Technology         | 67        | 68     | 2.17%   |
| HGST                      | 48        | 59     | 1.55%   |
| KIOXIA                    | 34        | 38     | 1.1%    |
| China                     | 22        | 22     | 0.71%   |
| LITEON                    | 19        | 22     | 0.61%   |
| SABRENT                   | 16        | 17     | 0.52%   |
| Unknown                   | 16        | 16     | 0.52%   |
| Transcend                 | 15        | 20     | 0.49%   |
| Silicon Motion            | 13        | 14     | 0.42%   |
| Phison                    | 13        | 17     | 0.42%   |
| LITEONIT                  | 12        | 14     | 0.39%   |
| SPCC                      | 11        | 12     | 0.36%   |
| PNY                       | 11        | 11     | 0.36%   |
| Intenso                   | 11        | 13     | 0.36%   |
| GOODRAM                   | 9         | 10     | 0.29%   |
| SSSTC                     | 7         | 7      | 0.23%   |
| Patriot                   | 7         | 7      | 0.23%   |
| Team                      | 6         | 6      | 0.19%   |
| Lenovo                    | 6         | 7      | 0.19%   |
| Netac                     | 5         | 5      | 0.16%   |
| KIOXIA-EXCERIA            | 5         | 6      | 0.16%   |
| JMicron Technology        | 5         | 5      | 0.16%   |
| Apacer                    | 5         | 5      | 0.16%   |
| Union Memory              | 4         | 4      | 0.13%   |
| UMIS                      | 4         | 8      | 0.13%   |
| Micron/Crucial Technology | 4         | 4      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 201       | 6.37%   |
| Apple SSD AP0128H 121GB            | 77        | 2.44%   |
| Apple SSD SM0128G 121GB            | 70        | 2.22%   |
| Toshiba MK1655GSXF 160GB           | 46        | 1.46%   |
| A-DATA SU800 512GB SSD             | 44        | 1.4%    |
| Toshiba MK1653GSX 160GB            | 43        | 1.36%   |
| Unknown AGND3R  16GB               | 39        | 1.24%   |
| Seagate ST1000LM035-1RK172 1TB     | 37        | 1.17%   |
| Kingston SA400S37240G 240GB SSD    | 34        | 1.08%   |
| Kingston SA400S37120G 120GB SSD    | 32        | 1.01%   |
| Unknown HAG2e  16GB                | 30        | 0.95%   |
| Unknown SDW16G  16GB               | 25        | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 25        | 0.79%   |
| Toshiba MQ01ABF050 500GB           | 22        | 0.7%    |
| Toshiba MQ04ABF100 1TB             | 20        | 0.63%   |
| HGST HTS721010A9E630 1TB           | 18        | 0.57%   |
| Crucial CT500MX500SSD1 500GB       | 17        | 0.54%   |
| WDC WD1600BUDT-63DPZY0 160GB       | 16        | 0.51%   |
| Samsung SSD 860 EVO 500GB          | 16        | 0.51%   |
| SABRENT Disk 1TB                   | 16        | 0.51%   |
| Unknown                            | 16        | 0.51%   |
| Unknown MMC Card  32GB             | 15        | 0.48%   |
| Kingston SV300S37A120G 120GB SSD   | 14        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB        | 14        | 0.44%   |
| Seagate ST500LT012-1DG142 500GB    | 13        | 0.41%   |
| SanDisk SD8SBAT128G1122 128GB SSD  | 13        | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB       | 13        | 0.41%   |
| Toshiba MQ01ABD100 1TB             | 12        | 0.38%   |
| Seagate ST980811AS 80GB            | 11        | 0.35%   |
| Samsung SSD 860 EVO 250GB          | 11        | 0.35%   |
| Kingston SA400S37480G 480GB SSD    | 11        | 0.35%   |
| Intel SSDPEKNW512G8 512GB          | 11        | 0.35%   |
| Fujitsu MHY2120BH 120GB            | 11        | 0.35%   |
| WDC WD10SPZX-24Z10 1TB             | 10        | 0.32%   |
| Samsung SSD 850 EVO 500GB          | 10        | 0.32%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 10        | 0.32%   |
| Crucial CT120BX500SSD1 120GB       | 10        | 0.32%   |
| Toshiba MK5065GSXF 500GB           | 9         | 0.29%   |
| SanDisk SD8SN8U128G1001 128GB SSD  | 9         | 0.29%   |
| Samsung SSD 850 EVO 250GB          | 9         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Fujitsu             | 239       | 243    | 23.64%  |
| Seagate             | 238       | 279    | 23.54%  |
| Toshiba             | 199       | 211    | 19.68%  |
| WDC                 | 171       | 188    | 16.91%  |
| Hitachi             | 86        | 99     | 8.51%   |
| HGST                | 48        | 59     | 4.75%   |
| Samsung Electronics | 11        | 12     | 1.09%   |
| Unknown             | 7         | 10     | 0.69%   |
| ASMT                | 4         | 5      | 0.4%    |
| Intenso             | 2         | 2      | 0.2%    |
| USB3.0              | 1         | 1      | 0.1%    |
| Unknown (CF)        | 1         | 1      | 0.1%    |
| SILICONMOTION       | 1         | 1      | 0.1%    |
| Maxone              | 1         | 1      | 0.1%    |
| IBM/Hitachi         | 1         | 1      | 0.1%    |
| ASMT109x            | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 189       | 223    | 19.54%  |
| Kingston            | 129       | 165    | 13.34%  |
| Crucial             | 102       | 119    | 10.55%  |
| SanDisk             | 95        | 120    | 9.82%   |
| Apple               | 82        | 88     | 8.48%   |
| A-DATA Technology   | 64        | 132    | 6.62%   |
| WDC                 | 31        | 44     | 3.21%   |
| Micron Technology   | 27        | 27     | 2.79%   |
| China               | 22        | 22     | 2.28%   |
| SK hynix            | 20        | 25     | 2.07%   |
| Intel               | 18        | 20     | 1.86%   |
| LITEON              | 16        | 18     | 1.65%   |
| Transcend           | 14        | 19     | 1.45%   |
| Toshiba             | 14        | 15     | 1.45%   |
| LITEONIT            | 12        | 14     | 1.24%   |
| PNY                 | 10        | 10     | 1.03%   |
| Intenso             | 9         | 11     | 0.93%   |
| SPCC                | 8         | 9      | 0.83%   |
| Patriot             | 7         | 7      | 0.72%   |
| GOODRAM             | 6         | 7      | 0.62%   |
| Team                | 5         | 5      | 0.52%   |
| Netac               | 5         | 5      | 0.52%   |
| Lexar               | 4         | 5      | 0.41%   |
| JMicron Technology  | 4         | 4      | 0.41%   |
| Apacer              | 4         | 4      | 0.41%   |
| Unknown             | 4         | 4      | 0.41%   |
| ZTC                 | 3         | 4      | 0.31%   |
| Seagate             | 3         | 3      | 0.31%   |
| Plextor             | 3         | 3      | 0.31%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.31%   |
| Dogfish             | 3         | 4      | 0.31%   |
| XrayDisk            | 2         | 2      | 0.21%   |
| Unknown             | 2         | 2      | 0.21%   |
| OCZ                 | 2         | 2      | 0.21%   |
| LDLC                | 2         | 2      | 0.21%   |
| KingDian            | 2         | 2      | 0.21%   |
| Kingchuxing         | 2         | 2      | 0.21%   |
| Fanxiang            | 2         | 2      | 0.21%   |
| Corsair             | 2         | 2      | 0.21%   |
| ASUS-PHISON         | 2         | 2      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 992       | 1114   | 33.22%  |
| SSD     | 915       | 1199   | 30.64%  |
| NVMe    | 822       | 1011   | 27.53%  |
| MMC     | 233       | 283    | 7.8%    |
| Unknown | 24        | 25     | 0.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1762      | 2243   | 60.97%  |
| NVMe | 810       | 993    | 28.03%  |
| MMC  | 233       | 283    | 8.06%   |
| SAS  | 85        | 113    | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1412      | 1692   | 74.91%  |
| 0.51-1.0   | 419       | 553    | 22.23%  |
| 1.01-2.0   | 38        | 46     | 2.02%   |
| 3.01-4.0   | 8         | 12     | 0.42%   |
| 4.01-10.0  | 7         | 9      | 0.37%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 769       | 27.98%  |
| Unknown        | 665       | 24.2%   |
| 251-500        | 461       | 16.78%  |
| 501-1000       | 286       | 10.41%  |
| 1-20           | 178       | 6.48%   |
| 51-100         | 149       | 5.42%   |
| 1001-2000      | 111       | 4.04%   |
| 21-50          | 77        | 2.8%    |
| 2001-3000      | 29        | 1.06%   |
| More than 3000 | 23        | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1040      | 37.13%  |
| Unknown        | 665       | 23.74%  |
| 21-50          | 291       | 10.39%  |
| 101-250        | 257       | 9.18%   |
| 51-100         | 255       | 9.1%    |
| 251-500        | 154       | 5.5%    |
| 501-1000       | 86        | 3.07%   |
| 1001-2000      | 30        | 1.07%   |
| 0              | 10        | 0.36%   |
| More than 3000 | 9         | 0.32%   |
| 2001-3000      | 4         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB                      | 20        | 20     | 7.52%   |
| Toshiba MK1653GSX 160GB                             | 9         | 9      | 3.38%   |
| Toshiba MK1655GSXF 160GB                            | 7         | 7      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 7         | 8      | 2.63%   |
| Seagate ST9500325AS 500GB                           | 6         | 6      | 2.26%   |
| Hitachi HTS543216L9SA02 160GB                       | 6         | 6      | 2.26%   |
| Hitachi HTS542512K9SA00 120GB                       | 5         | 6      | 1.88%   |
| WDC WD1600BUDT-63DPZY0 160GB                        | 4         | 4      | 1.5%    |
| Seagate ST9500420AS 500GB                           | 4         | 4      | 1.5%    |
| Seagate ST500LM021-1KJ152 500GB                     | 4         | 4      | 1.5%    |
| Hitachi HTS545050B9A300 500GB                       | 4         | 4      | 1.5%    |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 3         | 3      | 1.13%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 3      | 1.13%   |
| Seagate ST500LM000-SSHD-8GB                         | 3         | 3      | 1.13%   |
| Hitachi HTS547575A9E384 752GB                       | 3         | 3      | 1.13%   |
| HGST HTS725050A7E630 500GB                          | 3         | 3      | 1.13%   |
| HGST HTS541010A9E680 1TB                            | 3         | 3      | 1.13%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 2         | 2      | 0.75%   |
| WDC WD10SPZX-60Z10T0 1TB                            | 2         | 3      | 0.75%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 2         | 2      | 0.75%   |
| Toshiba MQ04ABF100 1TB                              | 2         | 2      | 0.75%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 2      | 0.75%   |
| SK hynix SH920 mSATA 128GB SSD                      | 2         | 2      | 0.75%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 2         | 2      | 0.75%   |
| SK hynix HFS256G39MND-2300A 256GB SSD               | 2         | 2      | 0.75%   |
| Seagate ST980811AS 80GB                             | 2         | 2      | 0.75%   |
| Seagate ST94811A 40GB                               | 2         | 2      | 0.75%   |
| Seagate ST9320325AS 320GB                           | 2         | 2      | 0.75%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 0.75%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 2      | 0.75%   |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 2         | 2      | 0.75%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 2      | 0.75%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 2      | 0.75%   |
| Hitachi HTS545032B9A300 320GB                       | 2         | 4      | 0.75%   |
| Hitachi HTS542516K9SA00 160GB                       | 2         | 2      | 0.75%   |
| Hitachi HTS541060G9AT00 64GB                        | 2         | 3      | 0.75%   |
| HGST HTS721010A9E630 1TB                            | 2         | 3      | 0.75%   |
| Crucial CT275MX300SSD1 275GB                        | 2         | 2      | 0.75%   |
| WDC WD7500BPVX-22JC3T0 752GB                        | 1         | 1      | 0.38%   |
| WDC WD7500BPVT-80HXZT3 752GB                        | 1         | 1      | 0.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 59     | 20.75%  |
| Hitachi             | 41        | 46     | 15.47%  |
| Toshiba             | 29        | 30     | 10.94%  |
| Fujitsu             | 28        | 28     | 10.57%  |
| WDC                 | 24        | 26     | 9.06%   |
| SK hynix            | 14        | 14     | 5.28%   |
| HGST                | 14        | 15     | 5.28%   |
| Samsung Electronics | 11        | 12     | 4.15%   |
| Micron Technology   | 9         | 9      | 3.4%    |
| Kingston            | 9         | 9      | 3.4%    |
| Intel               | 7         | 8      | 2.64%   |
| Crucial             | 5         | 5      | 1.89%   |
| SanDisk             | 4         | 5      | 1.51%   |
| LITEONIT            | 3         | 4      | 1.13%   |
| LITEON              | 3         | 3      | 1.13%   |
| A-DATA Technology   | 3         | 3      | 1.13%   |
| ShiJi               | 1         | 1      | 0.38%   |
| Lenovo              | 1         | 1      | 0.38%   |
| IBM/Hitachi         | 1         | 1      | 0.38%   |
| GOODRAM             | 1         | 1      | 0.38%   |
| DGM                 | 1         | 1      | 0.38%   |
| Unknown             | 1         | 1      | 0.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 59     | 28.06%  |
| Hitachi             | 41        | 46     | 20.92%  |
| Toshiba             | 29        | 30     | 14.8%   |
| Fujitsu             | 28        | 28     | 14.29%  |
| WDC                 | 24        | 26     | 12.24%  |
| HGST                | 14        | 15     | 7.14%   |
| Samsung Electronics | 4         | 4      | 2.04%   |
| IBM/Hitachi         | 1         | 1      | 0.51%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 196       | 209    | 73.96%  |
| SSD  | 58        | 62     | 21.89%  |
| NVMe | 11        | 11     | 4.15%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                           | Notebooks | Drives | Percent |
|-------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-35A0RT0 500GB                    | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB                 | 1         | 1      | 16.67%  |
| Seagate ST500LM000-1EJ162 500GB                 | 1         | 1      | 16.67%  |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB    | 1         | 1      | 16.67%  |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD | 1         | 1      | 16.67%  |
| Hitachi HTS545050A7E380 500GB                   | 1         | 2      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2         | 2      | 33.33%  |
| Samsung Electronics | 2         | 2      | 33.33%  |
| WDC                 | 1         | 1      | 16.67%  |
| Hitachi             | 1         | 2      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1927      | 2445   | 68.26%  |
| Detected | 626       | 897    | 22.17%  |
| Malfunc  | 263       | 282    | 9.32%   |
| Failed   | 6         | 7      | 0.21%   |
| Limited  | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1450      | 49.79%  |
| Nvidia                           | 318       | 10.92%  |
| Samsung Electronics              | 291       | 9.99%   |
| AMD                              | 259       | 8.89%   |
| SanDisk                          | 138       | 4.74%   |
| SK hynix                         | 91        | 3.13%   |
| Apple                            | 82        | 2.82%   |
| Micron Technology                | 40        | 1.37%   |
| Toshiba America Info Systems     | 38        | 1.3%    |
| Kingston Technology Company      | 34        | 1.17%   |
| KIOXIA                           | 33        | 1.13%   |
| ADATA Technology                 | 25        | 0.86%   |
| Silicon Motion                   | 22        | 0.76%   |
| Phison Electronics               | 21        | 0.72%   |
| Micron/Crucial Technology        | 18        | 0.62%   |
| Solid State Storage Technology   | 12        | 0.41%   |
| Union Memory (Shenzhen)          | 7         | 0.24%   |
| Shenzhen Longsys Electronics     | 4         | 0.14%   |
| Realtek Semiconductor            | 4         | 0.14%   |
| Lenovo                           | 4         | 0.14%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.1%    |
| Lite-On Technology               | 3         | 0.1%    |
| Unknown                          | 3         | 0.1%    |
| ULi Electronics                  | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| Marvell Technology Group         | 2         | 0.07%   |
| ASMedia Technology               | 2         | 0.07%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| Silicon Image                    | 1         | 0.03%   |
| JMicron Technology               | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 AHCI Controller                                                   | 310       | 9.88%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 237       | 7.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 174       | 5.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 157       | 5%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 116       | 3.7%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 106       | 3.38%   |
| Intel Volume Management Device NVMe RAID Controller                            | 89        | 2.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 85        | 2.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 83        | 2.65%   |
| Apple S1X NVMe Controller                                                      | 78        | 2.49%   |
| Samsung Electronics SATA controller                                            | 77        | 2.45%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 68        | 2.17%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 65        | 2.07%   |
| Samsung NVMe SSD Controller 980                                                | 63        | 2.01%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 56        | 1.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 55        | 1.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 51        | 1.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 50        | 1.59%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 45        | 1.43%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 44        | 1.4%    |
| Intel Tiger Lake-LP SATA Controller                                            | 43        | 1.37%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 41        | 1.31%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 41        | 1.31%   |
| Micron Non-Volatile memory controller                                          | 40        | 1.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 39        | 1.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 34        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 32        | 1.02%   |
| Intel SSD 660P Series                                                          | 30        | 0.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 30        | 0.96%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 29        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 29        | 0.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 27        | 0.86%   |
| SanDisk Non-Volatile memory controller                                         | 27        | 0.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 26        | 0.83%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 24        | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 24        | 0.77%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 21        | 0.67%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 19        | 0.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 19        | 0.61%   |
| SK hynix BC511                                                                 | 18        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1826      | 59.61%  |
| NVMe | 811       | 26.48%  |
| IDE  | 227       | 7.41%   |
| RAID | 199       | 6.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2292      | 85.84%  |
| AMD          | 373       | 13.97%  |
| ARM          | 3         | 0.11%   |
| CentaurHauls | 2         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 307       | 11.49%  |
| Intel Core i5-5250U CPU @ 1.60GHz             | 145       | 5.43%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 86        | 3.22%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 58        | 2.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 58        | 2.17%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 51        | 1.91%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 51        | 1.91%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 44        | 1.65%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 40        | 1.5%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 1.24%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 32        | 1.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 30        | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 1.09%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 27        | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 24        | 0.9%    |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 24        | 0.9%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 24        | 0.9%    |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 24        | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 23        | 0.86%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 22        | 0.82%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 22        | 0.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 21        | 0.79%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 21        | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 21        | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 20        | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 20        | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 19        | 0.71%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 18        | 0.67%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 16        | 0.6%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 16        | 0.6%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 16        | 0.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.6%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 15        | 0.56%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 15        | 0.56%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 15        | 0.56%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 14        | 0.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 14        | 0.52%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 0.52%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 14        | 0.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 643       | 24.08%  |
| Intel Core 2 Duo               | 404       | 15.13%  |
| Intel Core i7                  | 395       | 14.79%  |
| Intel Celeron                  | 239       | 8.95%   |
| Other                          | 221       | 8.28%   |
| Intel Core i3                  | 160       | 5.99%   |
| AMD Ryzen 5                    | 124       | 4.64%   |
| Intel Atom                     | 65        | 2.43%   |
| Intel Core 2                   | 61        | 2.28%   |
| AMD Ryzen 7                    | 53        | 1.99%   |
| Intel Pentium                  | 49        | 1.84%   |
| AMD Ryzen 7 PRO                | 27        | 1.01%   |
| AMD A6                         | 22        | 0.82%   |
| Intel Pentium M                | 19        | 0.71%   |
| Intel Genuine                  | 13        | 0.49%   |
| AMD Ryzen 3                    | 13        | 0.49%   |
| AMD A4                         | 12        | 0.45%   |
| AMD Ryzen 9                    | 11        | 0.41%   |
| AMD Ryzen 5 PRO                | 11        | 0.41%   |
| Intel Celeron M                | 10        | 0.37%   |
| Intel Pentium Dual-Core        | 9         | 0.34%   |
| Intel Pentium Dual             | 8         | 0.3%    |
| AMD E1                         | 8         | 0.3%    |
| AMD A8                         | 8         | 0.3%    |
| Intel Pentium 4                | 7         | 0.26%   |
| AMD A10                        | 7         | 0.26%   |
| AMD A12                        | 6         | 0.22%   |
| Intel Core i9                  | 5         | 0.19%   |
| AMD E2                         | 5         | 0.19%   |
| Intel Xeon                     | 4         | 0.15%   |
| Intel Pentium Silver           | 4         | 0.15%   |
| Intel Pentium Gold             | 3         | 0.11%   |
| Intel Mobile Pentium 4         | 3         | 0.11%   |
| Intel Core m3                  | 3         | 0.11%   |
| AMD PRO A10                    | 3         | 0.11%   |
| AMD E                          | 3         | 0.11%   |
| AMD C-60                       | 3         | 0.11%   |
| AMD Athlon                     | 3         | 0.11%   |
| Intel Core 2 Quad              | 2         | 0.07%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1556      | 58.28%  |
| 4      | 726       | 27.19%  |
| 6      | 135       | 5.06%   |
| 1      | 125       | 4.68%   |
| 8      | 110       | 4.12%   |
| 14     | 6         | 0.22%   |
| 12     | 6         | 0.22%   |
| 10     | 6         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2669      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1633      | 61.18%  |
| 1      | 1035      | 38.78%  |
| 4      | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2589      | 97%     |
| 32-bit         | 75        | 2.81%   |
| Unknown        | 5         | 0.19%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 417       | 15.43%  |
| 0x1067a    | 348       | 12.87%  |
| 0x306d4    | 200       | 7.4%    |
| 0x806c1    | 117       | 4.33%   |
| 0x306a9    | 117       | 4.33%   |
| 0x206a7    | 96        | 3.55%   |
| 0x30678    | 95        | 3.51%   |
| 0x806ec    | 83        | 3.07%   |
| 0x806e9    | 75        | 2.77%   |
| 0x6f6      | 61        | 2.26%   |
| 0x40651    | 61        | 2.26%   |
| 0x806ea    | 58        | 2.15%   |
| 0x406e3    | 58        | 2.15%   |
| 0x406c4    | 49        | 1.81%   |
| 0xa0652    | 44        | 1.63%   |
| 0x906eb    | 44        | 1.63%   |
| 0x08108109 | 42        | 1.55%   |
| 0x306c3    | 41        | 1.52%   |
| 0x906ea    | 36        | 1.33%   |
| 0x08600106 | 36        | 1.33%   |
| 0x10676    | 33        | 1.22%   |
| 0x20655    | 32        | 1.18%   |
| 0x08608103 | 32        | 1.18%   |
| 0x0a50000c | 31        | 1.15%   |
| 0x0600611a | 30        | 1.11%   |
| 0x706e5    | 27        | 1%      |
| 0x106c2    | 24        | 0.89%   |
| 0x06006705 | 22        | 0.81%   |
| 0x706a8    | 21        | 0.78%   |
| 0x6fd      | 19        | 0.7%    |
| 0x506c9    | 19        | 0.7%    |
| 0x906e9    | 18        | 0.67%   |
| 0x806eb    | 18        | 0.67%   |
| 0x6d8      | 18        | 0.67%   |
| 0x506e3    | 18        | 0.67%   |
| 0x08108102 | 17        | 0.63%   |
| 0x106ca    | 16        | 0.59%   |
| 0x806d1    | 14        | 0.52%   |
| 0xf29      | 10        | 0.37%   |
| 0x906a3    | 10        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 416       | 15.56%  |
| Penryn           | 392       | 14.67%  |
| Broadwell        | 215       | 8.04%   |
| Silvermont       | 168       | 6.29%   |
| IvyBridge        | 152       | 5.69%   |
| TigerLake        | 149       | 5.57%   |
| Haswell          | 132       | 4.94%   |
| SandyBridge      | 127       | 4.75%   |
| Core             | 103       | 3.85%   |
| Skylake          | 99        | 3.7%    |
| Zen+             | 79        | 2.96%   |
| Zen 2            | 69        | 2.58%   |
| Excavator        | 66        | 2.47%   |
| Unknown          | 59        | 2.21%   |
| Westmere         | 57        | 2.13%   |
| CometLake        | 56        | 2.1%    |
| Bonnell          | 46        | 1.72%   |
| Icelake          | 44        | 1.65%   |
| Zen 3            | 41        | 1.53%   |
| P6               | 39        | 1.46%   |
| Goldmont plus    | 33        | 1.23%   |
| Goldmont         | 23        | 0.86%   |
| Zen              | 17        | 0.64%   |
| Bobcat           | 15        | 0.56%   |
| Puma             | 13        | 0.49%   |
| NetBurst         | 10        | 0.37%   |
| K10 Llano        | 9         | 0.34%   |
| Jaguar           | 8         | 0.3%    |
| Alderlake Hybrid | 8         | 0.3%    |
| Tremont          | 6         | 0.22%   |
| Piledriver       | 6         | 0.22%   |
| K8 Hammer        | 5         | 0.19%   |
| Nehalem          | 4         | 0.15%   |
| K8 & K10 hybrid  | 3         | 0.11%   |
| K10              | 3         | 0.11%   |
| Steamroller      | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1859      | 59.3%   |
| Nvidia                           | 783       | 24.98%  |
| AMD                              | 487       | 15.53%  |
| Zhaoxin                          | 2         | 0.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.06%   |
| VIA Technologies                 | 1         | 0.03%   |
| S3 Graphics                      | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia C79 [GeForce 9400M G]                                                             | 305       | 9.21%   |
| Intel HD Graphics 6000                                                                   | 151       | 4.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 138       | 4.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 135       | 4.08%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 112       | 3.38%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 106       | 3.2%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 93        | 2.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 81        | 2.45%   |
| Intel UHD Graphics 620                                                                   | 80        | 2.42%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 74        | 2.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 70        | 2.11%   |
| Intel HD Graphics 620                                                                    | 69        | 2.08%   |
| AMD Renoir                                                                               | 69        | 2.08%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 68        | 2.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 61        | 1.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 61        | 1.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 60        | 1.81%   |
| Intel HD Graphics 5500                                                                   | 58        | 1.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 50        | 1.51%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 50        | 1.51%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 50        | 1.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 45        | 1.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 45        | 1.36%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 45        | 1.36%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 1.33%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 39        | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 38        | 1.15%   |
| AMD Lucienne                                                                             | 36        | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 34        | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 30        | 0.91%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 27        | 0.82%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 25        | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 24        | 0.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.69%   |
| Intel HD Graphics 630                                                                    | 22        | 0.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 0.63%   |
| Intel HD Graphics 530                                                                    | 21        | 0.63%   |
| Intel HD Graphics 610                                                                    | 20        | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 18        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1433      | 53.61%  |
| 1 x Nvidia      | 378       | 14.14%  |
| Intel + Nvidia  | 360       | 13.47%  |
| 1 x AMD         | 348       | 13.02%  |
| Intel + AMD     | 62        | 2.32%   |
| AMD + Nvidia    | 47        | 1.76%   |
| 2 x AMD         | 30        | 1.12%   |
| Other           | 9         | 0.34%   |
| 1 x Zhaoxin     | 2         | 0.07%   |
| 1 x SiS         | 2         | 0.07%   |
| 1 x VIA         | 1         | 0.04%   |
| 1 x S3 Graphics | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2313      | 86.21%  |
| Unknown     | 215       | 8.01%   |
| Proprietary | 155       | 5.78%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 1916      | 71.15%  |
| 0.01-0.5       | 504       | 18.72%  |
| 1.01-2.0       | 108       | 4.01%   |
| 3.01-4.0       | 69        | 2.56%   |
| 0.51-1.0       | 64        | 2.38%   |
| 5.01-6.0       | 15        | 0.56%   |
| 7.01-8.0       | 9         | 0.33%   |
| 2.01-3.0       | 6         | 0.22%   |
| More than 64.0 | 1         | 0.04%   |
| 8.01-16.0      | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 563       | 20.09%  |
| AU Optronics            | 444       | 15.85%  |
| BOE                     | 367       | 13.1%   |
| LG Display              | 301       | 10.74%  |
| Chimei Innolux          | 295       | 10.53%  |
| Samsung Electronics     | 185       | 6.6%    |
| Lenovo                  | 61        | 2.18%   |
| Dell                    | 55        | 1.96%   |
| Sharp                   | 54        | 1.93%   |
| Goldstar                | 45        | 1.61%   |
| Chi Mei Optoelectronics | 43        | 1.53%   |
| InfoVision              | 36        | 1.28%   |
| BenQ                    | 30        | 1.07%   |
| Hewlett-Packard         | 29        | 1.03%   |
| PANDA                   | 27        | 0.96%   |
| HannStar                | 22        | 0.79%   |
| Unknown                 | 19        | 0.68%   |
| Ancor Communications    | 19        | 0.68%   |
| Philips                 | 17        | 0.61%   |
| LG Philips              | 17        | 0.61%   |
| AOC                     | 16        | 0.57%   |
| ViewSonic               | 15        | 0.54%   |
| Iiyama                  | 15        | 0.54%   |
| CSO                     | 14        | 0.5%    |
| Acer                    | 13        | 0.46%   |
| Eizo                    | 7         | 0.25%   |
| Sony                    | 6         | 0.21%   |
| CPT                     | 6         | 0.21%   |
| NEC Computers           | 5         | 0.18%   |
| Quanta Display          | 4         | 0.14%   |
| Pixio                   | 4         | 0.14%   |
| Panasonic               | 4         | 0.14%   |
| Toshiba                 | 3         | 0.11%   |
| TMX                     | 3         | 0.11%   |
| SLD                     | 3         | 0.11%   |
| MSI                     | 3         | 0.11%   |
| AGO                     | 3         | 0.11%   |
| ___                     | 2         | 0.07%   |
| RTK                     | 2         | 0.07%   |
| Mi                      | 2         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                      | 199       | 7.04%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                    | 150       | 5.3%    |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 52        | 1.84%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 41        | 1.45%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 41        | 1.45%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch             | 39        | 1.38%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                      | 36        | 1.27%   |
| BOE LCD Monitor BOE06B3 1920x1080                                         | 25        | 0.88%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 25        | 0.88%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 22        | 0.78%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch           | 21        | 0.74%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                      | 21        | 0.74%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 19        | 0.67%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                  | 18        | 0.64%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 17        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 17        | 0.6%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 16        | 0.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch             | 14        | 0.5%    |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                      | 13        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 12        | 0.42%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 12        | 0.42%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 11        | 0.39%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 11        | 0.39%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x165mm 13.2-inch               | 9         | 0.32%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 9         | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 9         | 0.32%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 9         | 0.32%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch            | 9         | 0.32%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 9         | 0.32%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 9         | 0.32%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 9         | 0.32%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 9         | 0.32%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 8         | 0.28%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 8         | 0.28%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 8         | 0.28%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch            | 8         | 0.28%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 8         | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 7         | 0.25%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 7         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 7         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 914       | 34.34%  |
| 1366x768 (WXGA)    | 722       | 27.12%  |
| 1280x800 (WXGA)    | 452       | 16.98%  |
| 1440x900 (WXGA+)   | 107       | 4.02%   |
| 1600x900 (HD+)     | 98        | 3.68%   |
| 3840x2160 (4K)     | 66        | 2.48%   |
| 2560x1440 (QHD)    | 52        | 1.95%   |
| 1920x1200 (WUXGA)  | 50        | 1.88%   |
| 1024x600           | 42        | 1.58%   |
| 1280x1024 (SXGA)   | 18        | 0.68%   |
| 2288x1287          | 17        | 0.64%   |
| 2560x1600          | 16        | 0.6%    |
| 1024x768 (XGA)     | 14        | 0.53%   |
| 1360x768           | 12        | 0.45%   |
| 1680x1050 (WSXGA+) | 11        | 0.41%   |
| 3840x2400          | 10        | 0.38%   |
| 2560x1080          | 10        | 0.38%   |
| 2880x1800          | 8         | 0.3%    |
| 3440x1440          | 7         | 0.26%   |
| 2160x1440          | 6         | 0.23%   |
| 1400x1050          | 4         | 0.15%   |
| 3840x1080          | 3         | 0.11%   |
| Unknown            | 3         | 0.11%   |
| 3840x1100          | 2         | 0.08%   |
| 3200x1800 (QHD+)   | 2         | 0.08%   |
| 2256x1504          | 2         | 0.08%   |
| 1920x1280          | 2         | 0.08%   |
| 1600x1200          | 2         | 0.08%   |
| 3840x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |
| 1920x515           | 1         | 0.04%   |
| 1792x768           | 1         | 0.04%   |
| 1024x576           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 13      | 796       | 28.45%  |
| 15      | 764       | 27.31%  |
| 14      | 310       | 11.08%  |
| 11      | 232       | 8.29%   |
| 17      | 130       | 4.65%   |
| 12      | 97        | 3.47%   |
| 24      | 87        | 3.11%   |
| 27      | 64        | 2.29%   |
| 23      | 59        | 2.11%   |
| 21      | 47        | 1.68%   |
| 10      | 40        | 1.43%   |
| 18      | 23        | 0.82%   |
| 19      | 20        | 0.71%   |
| 142     | 17        | 0.61%   |
| 31      | 14        | 0.5%    |
| Unknown | 14        | 0.5%    |
| 16      | 12        | 0.43%   |
| 34      | 11        | 0.39%   |
| 25      | 8         | 0.29%   |
| 32      | 7         | 0.25%   |
| 22      | 7         | 0.25%   |
| 29      | 5         | 0.18%   |
| 20      | 5         | 0.18%   |
| 72      | 4         | 0.14%   |
| 84      | 3         | 0.11%   |
| 40      | 3         | 0.11%   |
| 8       | 3         | 0.11%   |
| 54      | 2         | 0.07%   |
| 52      | 2         | 0.07%   |
| 49      | 2         | 0.07%   |
| 46      | 2         | 0.07%   |
| 28      | 2         | 0.07%   |
| 55      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 43      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 26      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1264      | 45.48%  |
| 201-300        | 967       | 34.8%   |
| 501-600        | 197       | 7.09%   |
| 351-400        | 150       | 5.4%    |
| 401-500        | 94        | 3.38%   |
| 601-700        | 33        | 1.19%   |
| 701-800        | 18        | 0.65%   |
| More than 2000 | 17        | 0.61%   |
| Unknown        | 14        | 0.5%    |
| 1001-1500      | 11        | 0.4%    |
| 1501-2000      | 7         | 0.25%   |
| 801-900        | 4         | 0.14%   |
| 101-200        | 3         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1772      | 69.82%  |
| 16/10   | 663       | 26.12%  |
| 4/3     | 22        | 0.87%   |
| 5/4     | 18        | 0.71%   |
| 3/2     | 17        | 0.67%   |
| 1.00    | 17        | 0.67%   |
| 21/9    | 14        | 0.55%   |
| Unknown | 6         | 0.24%   |
| 2.65    | 4         | 0.16%   |
| 3.40    | 2         | 0.08%   |
| 32/9    | 1         | 0.04%   |
| 3.73    | 1         | 0.04%   |
| 3.20    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 926       | 33.19%  |
| 101-110        | 767       | 27.49%  |
| 51-60          | 234       | 8.39%   |
| 71-80          | 175       | 6.27%   |
| 201-250        | 153       | 5.48%   |
| 121-130        | 103       | 3.69%   |
| 61-70          | 93        | 3.33%   |
| 301-350        | 64        | 2.29%   |
| 251-300        | 45        | 1.61%   |
| 41-50          | 40        | 1.43%   |
| 151-200        | 36        | 1.29%   |
| 351-500        | 35        | 1.25%   |
| 141-150        | 32        | 1.15%   |
| More than 1000 | 30        | 1.08%   |
| 131-140        | 16        | 0.57%   |
| Unknown        | 14        | 0.5%    |
| 91-100         | 10        | 0.36%   |
| 501-1000       | 8         | 0.29%   |
| 111-120        | 6         | 0.22%   |
| 1-40           | 3         | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1190      | 43.34%  |
| 101-120       | 976       | 35.54%  |
| 51-100        | 345       | 12.56%  |
| 161-240       | 141       | 5.13%   |
| More than 240 | 46        | 1.68%   |
| 1-50          | 34        | 1.24%   |
| Unknown       | 14        | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2119      | 78.45%  |
| 2     | 331       | 12.25%  |
| 0     | 212       | 7.85%   |
| 3     | 38        | 1.41%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1246      | 28.99%  |
| Realtek Semiconductor             | 1090      | 25.36%  |
| Qualcomm Atheros                  | 499       | 11.61%  |
| Broadcom                          | 497       | 11.56%  |
| Nvidia                            | 316       | 7.35%   |
| Broadcom Limited                  | 205       | 4.77%   |
| Marvell Technology Group          | 101       | 2.35%   |
| MediaTek                          | 38        | 0.88%   |
| Ralink                            | 29        | 0.67%   |
| TP-Link                           | 25        | 0.58%   |
| ASIX Electronics                  | 25        | 0.58%   |
| Dell                              | 21        | 0.49%   |
| Samsung Electronics               | 18        | 0.42%   |
| Sierra Wireless                   | 17        | 0.4%    |
| Qualcomm                          | 15        | 0.35%   |
| Ralink Technology                 | 13        | 0.3%    |
| DisplayLink                       | 13        | 0.3%    |
| Lenovo                            | 10        | 0.23%   |
| Xiaomi                            | 9         | 0.21%   |
| Hewlett-Packard                   | 9         | 0.21%   |
| Ericsson Business Mobile Networks | 9         | 0.21%   |
| JMicron Technology                | 8         | 0.19%   |
| Huawei Technologies               | 6         | 0.14%   |
| Fibocom                           | 6         | 0.14%   |
| Cypress Semiconductor             | 6         | 0.14%   |
| NetGear                           | 5         | 0.12%   |
| ICS Advent                        | 5         | 0.12%   |
| ASUSTek Computer                  | 5         | 0.12%   |
| AMD                               | 5         | 0.12%   |
| Qualcomm Atheros Communications   | 4         | 0.09%   |
| OPPO Electronics                  | 4         | 0.09%   |
| Attansic Technology               | 4         | 0.09%   |
| Microchip Technology              | 3         | 0.07%   |
| Apple                             | 3         | 0.07%   |
| ULi Electronics                   | 2         | 0.05%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.05%   |
| National Semiconductor            | 2         | 0.05%   |
| Motorola PCS                      | 2         | 0.05%   |
| Dresden Elektronik                | 2         | 0.05%   |
| D-Link                            | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller                     | 682       | 13.56%  |
| Nvidia MCP79 Ethernet                                                                 | 310       | 6.16%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 307       | 6.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                                 | 168       | 3.34%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 155       | 3.08%   |
| Intel Wireless 7260                                                                   | 130       | 2.59%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 120       | 2.39%   |
| Intel Wireless 8265 / 8275                                                            | 105       | 2.09%   |
| Intel Wi-Fi 6 AX201                                                                   | 102       | 2.03%   |
| Intel Wireless 7265                                                                   | 100       | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                                 | 95        | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                              | 92        | 1.83%   |
| Intel Wi-Fi 6 AX200                                                                   | 92        | 1.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 70        | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 69        | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 63        | 1.25%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 59        | 1.17%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 59        | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 57        | 1.13%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                               | 56        | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 55        | 1.09%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 55        | 1.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 51        | 1.01%   |
| Intel Wireless 8260                                                                   | 51        | 1.01%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 45        | 0.89%   |
| Intel Ethernet Connection (4) I219-V                                                  | 40        | 0.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 39        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 34        | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 33        | 0.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 31        | 0.62%   |
| Intel Ethernet Connection I218-LM                                                     | 31        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                                 | 29        | 0.58%   |
| Intel Wireless 3165                                                                   | 27        | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 26        | 0.52%   |
| Intel Ethernet Connection (3) I218-LM                                                 | 26        | 0.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 25        | 0.5%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                                 | 24        | 0.48%   |
| Intel Ethernet Connection I219-LM                                                     | 24        | 0.48%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 24        | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 23        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1183      | 43.38%  |
| Qualcomm Atheros                | 456       | 16.72%  |
| Broadcom                        | 435       | 15.95%  |
| Realtek Semiconductor           | 315       | 11.55%  |
| Broadcom Limited                | 186       | 6.82%   |
| MediaTek                        | 37        | 1.36%   |
| Ralink                          | 29        | 1.06%   |
| Sierra Wireless                 | 17        | 0.62%   |
| Ralink Technology               | 13        | 0.48%   |
| TP-Link                         | 12        | 0.44%   |
| Dell                            | 12        | 0.44%   |
| Qualcomm                        | 6         | 0.22%   |
| Fibocom                         | 6         | 0.22%   |
| NetGear                         | 5         | 0.18%   |
| ASUSTek Computer                | 5         | 0.18%   |
| Qualcomm Atheros Communications | 4         | 0.15%   |
| Z-Com                           | 1         | 0.04%   |
| Wilocity                        | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| 3Com                            | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 307       | 11.22%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 155       | 5.67%   |
| Intel Wireless 7260                                                                   | 130       | 4.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 120       | 4.39%   |
| Intel Wireless 8265 / 8275                                                            | 105       | 3.84%   |
| Intel Wi-Fi 6 AX201                                                                   | 102       | 3.73%   |
| Intel Wireless 7265                                                                   | 100       | 3.65%   |
| Intel Wi-Fi 6 AX200                                                                   | 92        | 3.36%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 70        | 2.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 69        | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 63        | 2.3%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 59        | 2.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 59        | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 57        | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 55        | 2.01%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 55        | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 51        | 1.86%   |
| Intel Wireless 8260                                                                   | 51        | 1.86%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 45        | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 39        | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 34        | 1.24%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 33        | 1.21%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 31        | 1.13%   |
| Intel Wireless 3165                                                                   | 27        | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 26        | 0.95%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 25        | 0.91%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 24        | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                              | 23        | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 23        | 0.84%   |
| Broadcom BCM4321 802.11a/b/g/n                                                        | 23        | 0.84%   |
| Intel Wireless 3160                                                                   | 21        | 0.77%   |
| Intel Centrino Ultimate-N 6300                                                        | 21        | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 20        | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                         | 20        | 0.73%   |
| Intel Centrino Advanced-N 6200                                                        | 20        | 0.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 20        | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 19        | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                                            | 17        | 0.62%   |
| Realtek 802.11n WLAN Adapter                                                          | 17        | 0.62%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 17        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 968       | 43.88%  |
| Intel                            | 475       | 21.53%  |
| Nvidia                           | 316       | 14.32%  |
| Marvell Technology Group         | 101       | 4.58%   |
| Qualcomm Atheros                 | 95        | 4.31%   |
| Broadcom                         | 76        | 3.45%   |
| ASIX Electronics                 | 25        | 1.13%   |
| Broadcom Limited                 | 22        | 1%      |
| Samsung Electronics              | 18        | 0.82%   |
| TP-Link                          | 13        | 0.59%   |
| DisplayLink                      | 13        | 0.59%   |
| Lenovo                           | 10        | 0.45%   |
| Xiaomi                           | 9         | 0.41%   |
| Qualcomm                         | 9         | 0.41%   |
| JMicron Technology               | 8         | 0.36%   |
| Cypress Semiconductor            | 6         | 0.27%   |
| ICS Advent                       | 5         | 0.23%   |
| OPPO Electronics                 | 4         | 0.18%   |
| Huawei Technologies              | 4         | 0.18%   |
| Attansic Technology              | 4         | 0.18%   |
| Microchip Technology             | 3         | 0.14%   |
| Apple                            | 3         | 0.14%   |
| Silicon Integrated Systems [SiS] | 2         | 0.09%   |
| National Semiconductor           | 2         | 0.09%   |
| Motorola PCS                     | 2         | 0.09%   |
| Hewlett-Packard                  | 2         | 0.09%   |
| D-Link                           | 2         | 0.09%   |
| VIA Technologies                 | 1         | 0.05%   |
| Spreadtrum Communications        | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.05%   |
| MosChip Semiconductor            | 1         | 0.05%   |
| MediaTek                         | 1         | 0.05%   |
| Linksys                          | 1         | 0.05%   |
| LG Electronics                   | 1         | 0.05%   |
| Google                           | 1         | 0.05%   |
| Davicom Semiconductor            | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 682       | 30.62%  |
| Nvidia MCP79 Ethernet                                             | 310       | 13.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 168       | 7.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 95        | 4.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 92        | 4.13%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 56        | 2.51%   |
| Intel Ethernet Connection (4) I219-V                              | 40        | 1.8%    |
| Intel Ethernet Connection I218-LM                                 | 31        | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 29        | 1.3%    |
| Intel Ethernet Connection (3) I218-LM                             | 26        | 1.17%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 24        | 1.08%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 1.08%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 22        | 0.99%   |
| Intel 82577LM Gigabit Network Connection                          | 22        | 0.99%   |
| Intel Ethernet Connection (6) I219-V                              | 19        | 0.85%   |
| Intel Ethernet Connection (13) I219-V                             | 19        | 0.85%   |
| ASIX AX88179 Gigabit Ethernet                                     | 19        | 0.85%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 0.76%   |
| Intel Ethernet Connection I219-V                                  | 17        | 0.76%   |
| Intel Ethernet Connection (10) I219-V                             | 15        | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 0.63%   |
| Intel 82567LM Gigabit Network Connection                          | 14        | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 11        | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 11        | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 0.45%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 10        | 0.45%   |
| Intel 82566MM Gigabit Network Connection                          | 10        | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.36%   |
| Intel Ethernet Connection (11) I219-LM                            | 8         | 0.36%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 8         | 0.36%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 7         | 0.31%   |
| Intel Ethernet Connection (7) I219-LM                             | 7         | 0.31%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.31%   |
| Intel Ethernet Connection (13) I219-LM                            | 7         | 0.31%   |
| Broadcom BCM4401 100Base-T                                        | 7         | 0.31%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2629      | 54.68%  |
| Ethernet | 2113      | 43.95%  |
| Modem    | 63        | 1.31%   |
| Unknown  | 3         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2046      | 73.15%  |
| Ethernet | 751       | 26.85%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1918      | 71.81%  |
| 1     | 691       | 25.87%  |
| 0     | 34        | 1.27%   |
| 3     | 27        | 1.01%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2238      | 83.32%  |
| Yes  | 448       | 16.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 904       | 40.39%  |
| Apple                           | 554       | 24.75%  |
| Realtek Semiconductor           | 180       | 8.04%   |
| Qualcomm Atheros Communications | 165       | 7.37%   |
| Broadcom                        | 90        | 4.02%   |
| Lite-On Technology              | 80        | 3.57%   |
| IMC Networks                    | 79        | 3.53%   |
| Foxconn / Hon Hai               | 47        | 2.1%    |
| Dell                            | 31        | 1.39%   |
| Cambridge Silicon Radio         | 25        | 1.12%   |
| Hewlett-Packard                 | 20        | 0.89%   |
| Realtek                         | 13        | 0.58%   |
| Ralink                          | 11        | 0.49%   |
| Toshiba                         | 10        | 0.45%   |
| ASUSTek Computer                | 10        | 0.45%   |
| Ralink Technology               | 4         | 0.18%   |
| Taiyo Yuden                     | 3         | 0.13%   |
| MediaTek                        | 3         | 0.13%   |
| Foxconn International           | 3         | 0.13%   |
| Fujitsu                         | 2         | 0.09%   |
| Alps Electric                   | 2         | 0.09%   |
| Qcom                            | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 408       | 18.23%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 300       | 13.4%   |
| Intel AX201 Bluetooth                               | 182       | 8.13%   |
| Apple Bluetooth USB Host Controller                 | 154       | 6.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 139       | 6.21%   |
| Realtek Bluetooth Radio                             | 120       | 5.36%   |
| Qualcomm Atheros  Bluetooth Device                  | 103       | 4.6%    |
| Intel AX200 Bluetooth                               | 90        | 4.02%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 76        | 3.4%    |
| Realtek  Bluetooth 4.2 Adapter                      | 45        | 2.01%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 33        | 1.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 25        | 1.12%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 24        | 1.07%   |
| IMC Networks Bluetooth Radio                        | 24        | 1.07%   |
| Lite-On Bluetooth Device                            | 21        | 0.94%   |
| Apple Bluetooth Host Controller                     | 21        | 0.94%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 0.89%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 0.85%   |
| Broadcom BCM2045B (BDC-2.1)                         | 19        | 0.85%   |
| Foxconn / Hon Hai Bluetooth Device                  | 18        | 0.8%    |
| IMC Networks Bluetooth Device                       | 16        | 0.71%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 15        | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 0.63%   |
| Intel AX210 Bluetooth                               | 14        | 0.63%   |
| IMC Networks Wireless_Device                        | 14        | 0.63%   |
| Realtek Bluetooth Radio                             | 13        | 0.58%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 0.58%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 0.58%   |
| Ralink RT3290 Bluetooth                             | 11        | 0.49%   |
| Intel Bluetooth Device                              | 11        | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 10        | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 10        | 0.45%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.4%    |
| Lite-On Wireless_Device                             | 8         | 0.36%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.36%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 8         | 0.36%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 7         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1947      | 64.28%  |
| Nvidia                                       | 543       | 17.93%  |
| AMD                                          | 402       | 13.27%  |
| C-Media Electronics                          | 18        | 0.59%   |
| Logitech                                     | 13        | 0.43%   |
| Realtek Semiconductor                        | 11        | 0.36%   |
| Generalplus Technology                       | 9         | 0.3%    |
| Texas Instruments                            | 8         | 0.26%   |
| Lenovo                                       | 8         | 0.26%   |
| Plantronics                                  | 7         | 0.23%   |
| Hewlett-Packard                              | 6         | 0.2%    |
| GN Netcom                                    | 6         | 0.2%    |
| Creative Technology                          | 5         | 0.17%   |
| ASUSTek Computer                             | 3         | 0.1%    |
| Zhaoxin                                      | 2         | 0.07%   |
| ULi Electronics                              | 2         | 0.07%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.07%   |
| Sennheiser Communications                    | 2         | 0.07%   |
| SAVITECH                                     | 2         | 0.07%   |
| RODE Microphones                             | 2         | 0.07%   |
| Microsoft                                    | 2         | 0.07%   |
| Kingston Technology                          | 2         | 0.07%   |
| JMTek                                        | 2         | 0.07%   |
| CMX Systems                                  | 2         | 0.07%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| XMOS                                         | 1         | 0.03%   |
| VIA Technologies                             | 1         | 0.03%   |
| Toshiba                                      | 1         | 0.03%   |
| Thomann                                      | 1         | 0.03%   |
| Tenx Technology                              | 1         | 0.03%   |
| Syntek                                       | 1         | 0.03%   |
| SteelSeries ApS                              | 1         | 0.03%   |
| Samsung Electronics                          | 1         | 0.03%   |
| Razer USA                                    | 1         | 0.03%   |
| Pixart Imaging                               | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)                | 1         | 0.03%   |
| Microdia                                     | 1         | 0.03%   |
| M-Audio                                      | 1         | 0.03%   |
| Focusrite-Novation                           | 1         | 0.03%   |
| ESS Technology                               | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Nvidia MCP79 High Definition Audio                                                                | 312       | 8.4%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 248       | 6.68%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 240       | 6.46%   |
| Intel Broadwell-U Audio Controller                                                                | 215       | 5.79%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 212       | 5.71%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 183       | 4.93%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 148       | 3.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 118       | 3.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 118       | 3.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 97        | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 96        | 2.59%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 95        | 2.56%   |
| Intel Cannon Lake PCH cAVS                                                                        | 93        | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 76        | 2.05%   |
| Intel 8 Series HD Audio Controller                                                                | 76        | 2.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 67        | 1.8%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 65        | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 63        | 1.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 63        | 1.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 60        | 1.62%   |
| AMD Kabini HDMI/DP Audio                                                                          | 60        | 1.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 56        | 1.51%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 54        | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 52        | 1.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 52        | 1.4%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 50        | 1.35%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 44        | 1.19%   |
| AMD FCH Azalia Controller                                                                         | 44        | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 33        | 0.89%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 31        | 0.83%   |
| AMD High Definition Audio Controller                                                              | 27        | 0.73%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 26        | 0.7%    |
| Intel CM238 HD Audio Controller                                                                   | 24        | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 23        | 0.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 22        | 0.59%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 21        | 0.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 0.51%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 18        | 0.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 17        | 0.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| SK hynix                   | 835       | 31.26%  |
| Samsung Electronics        | 699       | 26.17%  |
| Micron Technology          | 255       | 9.55%   |
| Kingston                   | 166       | 6.21%   |
| Unknown                    | 150       | 5.62%   |
| Crucial                    | 146       | 5.47%   |
| Elpida                     | 86        | 3.22%   |
| A-DATA Technology          | 52        | 1.95%   |
| Ramaxel Technology         | 44        | 1.65%   |
| Unknown                    | 32        | 1.2%    |
| Nanya Technology           | 31        | 1.16%   |
| Corsair                    | 28        | 1.05%   |
| Unknown (ABCD)             | 19        | 0.71%   |
| Goodram                    | 19        | 0.71%   |
| Team                       | 12        | 0.45%   |
| Smart                      | 12        | 0.45%   |
| Transcend                  | 11        | 0.41%   |
| G.Skill                    | 8         | 0.3%    |
| Patriot                    | 5         | 0.19%   |
| ASint Technology           | 4         | 0.15%   |
| Apacer                     | 4         | 0.15%   |
| Wilk                       | 3         | 0.11%   |
| Smart Brazil               | 3         | 0.11%   |
| Silicon Power              | 3         | 0.11%   |
| Qimonda                    | 3         | 0.11%   |
| PNY                        | 3         | 0.11%   |
| AMD                        | 3         | 0.11%   |
| Unknown (89F7)             | 2         | 0.07%   |
| Unifosa                    | 2         | 0.07%   |
| Teikon                     | 2         | 0.07%   |
| Shenzhen WODPOSIT          | 2         | 0.07%   |
| Neo Forza                  | 2         | 0.07%   |
| Infineon                   | 2         | 0.07%   |
| Goldkey                    | 2         | 0.07%   |
| Avant                      | 2         | 0.07%   |
| 48spaces                   | 2         | 0.07%   |
| Unknown (D386)             | 1         | 0.04%   |
| Unknown (7F7F7F7F7F7F7F25) | 1         | 0.04%   |
| Unknown (0x0C97)           | 1         | 0.04%   |
| Unknown (08C8)             | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 257       | 9.25%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 2.45%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 62        | 2.23%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 60        | 2.16%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 1.58%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 37        | 1.33%   |
| Unknown                                                          | 32        | 1.15%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 1.04%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 29        | 1.04%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 28        | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 25        | 0.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 0.9%    |
| Crucial RAM CT8G4SFS824A.M8FE 8192MB SODIMM DDR4 2667MT/s        | 25        | 0.9%    |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 24        | 0.86%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 23        | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 23        | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 22        | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 0.79%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 21        | 0.76%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 0.72%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.68%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 19        | 0.68%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 18        | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 0.65%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 0.65%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 16        | 0.58%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 16        | 0.58%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 16        | 0.58%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                       | 15        | 0.54%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 14        | 0.5%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.5%    |
| Samsung RAM M471A5143SB1-CRC 4GB SODIMM DDR4 2400MT/s            | 14        | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 12        | 0.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.43%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 12        | 0.43%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.43%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.43%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 11        | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 856       | 36.41%  |
| DDR3    | 777       | 33.05%  |
| DDR2    | 461       | 19.61%  |
| LPDDR3  | 81        | 3.45%   |
| LPDDR4  | 74        | 3.15%   |
| SDRAM   | 50        | 2.13%   |
| DDR     | 29        | 1.23%   |
| Unknown | 11        | 0.47%   |
| DRAM    | 5         | 0.21%   |
| DDR5    | 4         | 0.17%   |
| LPDDR5  | 3         | 0.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 2166      | 91.74%  |
| Row Of Chips | 124       | 5.25%   |
| Unknown      | 41        | 1.74%   |
| Chip         | 23        | 0.97%   |
| DIMM         | 7         | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 692       | 27.54%  |
| 4096  | 630       | 25.07%  |
| 1024  | 459       | 18.27%  |
| 2048  | 410       | 16.32%  |
| 16384 | 231       | 9.19%   |
| 32768 | 51        | 2.03%   |
| 512   | 29        | 1.15%   |
| 256   | 11        | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 612       | 24.55%  |
| 2667    | 402       | 16.13%  |
| 3200    | 359       | 14.4%   |
| 800     | 313       | 12.56%  |
| 2400    | 133       | 5.33%   |
| 667     | 129       | 5.17%   |
| 1334    | 90        | 3.61%   |
| 2133    | 82        | 3.29%   |
| 1333    | 76        | 3.05%   |
| Unknown | 56        | 2.25%   |
| 1067    | 33        | 1.32%   |
| 1867    | 32        | 1.28%   |
| 4267    | 31        | 1.24%   |
| 3266    | 25        | 1%      |
| 4199    | 17        | 0.68%   |
| 533     | 14        | 0.56%   |
| 2048    | 10        | 0.4%    |
| 1066    | 10        | 0.4%    |
| 8400    | 8         | 0.32%   |
| 975     | 8         | 0.32%   |
| 333     | 8         | 0.32%   |
| 266     | 7         | 0.28%   |
| 4266    | 6         | 0.24%   |
| 4800    | 5         | 0.2%    |
| 400     | 5         | 0.2%    |
| 6400    | 4         | 0.16%   |
| 1866    | 4         | 0.16%   |
| 3733    | 3         | 0.12%   |
| 2933    | 2         | 0.08%   |
| 2666    | 2         | 0.08%   |
| 1639    | 2         | 0.08%   |
| 3000    | 1         | 0.04%   |
| 1596    | 1         | 0.04%   |
| 933     | 1         | 0.04%   |
| 200     | 1         | 0.04%   |
| 133     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 31.25%  |
| Xerox               | 4         | 25%     |
| Canon               | 3         | 18.75%  |
| Brother Industries  | 3         | 18.75%  |
| Samsung Electronics | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Xerox B205                          | 4         | 25%     |
| Samsung ML-2010P Mono Laser Printer | 1         | 6.25%   |
| HP LaserJet 1160 series             | 1         | 6.25%   |
| HP LaserJet 1022                    | 1         | 6.25%   |
| HP Ink Tank 110 series              | 1         | 6.25%   |
| HP DeskJet 2620 All-in-One Printer  | 1         | 6.25%   |
| HP DeskJet 2130 series              | 1         | 6.25%   |
| Canon PIXMA MX920 Series            | 1         | 6.25%   |
| Canon LBP3010/LBP3018/LBP3050       | 1         | 6.25%   |
| Canon G3010 series                  | 1         | 6.25%   |
| Brother PT-9500PC                   | 1         | 6.25%   |
| Brother MFC-L2707DW                 | 1         | 6.25%   |
| Brother HL-L2340D series            | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 4         | 66.67%  |
| Seiko Epson | 2         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 120                       | 2         | 33.33%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 16.67%  |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 16.67%  |
| Canon CanoScan LIDE 25                        | 1         | 16.67%  |
| Canon CanoScan LiDE 220                       | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 454       | 24.01%  |
| IMC Networks                           | 226       | 11.95%  |
| Acer                                   | 198       | 10.47%  |
| Quanta                                 | 191       | 10.1%   |
| Microdia                               | 151       | 7.99%   |
| Realtek Semiconductor                  | 142       | 7.51%   |
| Sunplus Innovation Technology          | 78        | 4.12%   |
| Cheng Uei Precision Industry (Foxlink) | 61        | 3.23%   |
| Suyin                                  | 54        | 2.86%   |
| Lite-On Technology                     | 45        | 2.38%   |
| Syntek                                 | 43        | 2.27%   |
| Luxvisions Innotech Limited            | 37        | 1.96%   |
| Apple                                  | 30        | 1.59%   |
| Logitech                               | 24        | 1.27%   |
| Silicon Motion                         | 18        | 0.95%   |
| Lenovo                                 | 18        | 0.95%   |
| Alcor Micro                            | 17        | 0.9%    |
| Ricoh                                  | 12        | 0.63%   |
| Sonix Technology                       | 9         | 0.48%   |
| Primax Electronics                     | 9         | 0.48%   |
| Z-Star Microelectronics                | 8         | 0.42%   |
| Importek                               | 6         | 0.32%   |
| ALi                                    | 5         | 0.26%   |
| SunplusIT                              | 4         | 0.21%   |
| Samsung Electronics                    | 4         | 0.21%   |
| Intel                                  | 4         | 0.21%   |
| Y Media                                | 3         | 0.16%   |
| USB Camera                             | 3         | 0.16%   |
| Genesys Logic                          | 3         | 0.16%   |
| DJJHFA1BIF5595                         | 3         | 0.16%   |
| Sunplus Technology                     | 2         | 0.11%   |
| Pixart Imaging                         | 2         | 0.11%   |
| OmniVision Technologies                | 2         | 0.11%   |
| Mimaki Engineering                     | 2         | 0.11%   |
| Microsoft                              | 2         | 0.11%   |
| USB Camera CS                          | 1         | 0.05%   |
| Unknown                                | 1         | 0.05%   |
| U0AS01A-0                              | 1         | 0.05%   |
| ShineTech                              | 1         | 0.05%   |
| Nebraska Furniture Mart                | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 144       | 7.57%   |
| Microdia Integrated_Webcam_HD                       | 79        | 4.15%   |
| IMC Networks Integrated Camera                      | 70        | 3.68%   |
| Quanta Chromebook HD Camera                         | 67        | 3.52%   |
| Acer Integrated Camera                              | 60        | 3.15%   |
| Realtek Integrated_Webcam_HD                        | 54        | 2.84%   |
| Acer BisonCam, NB Pro                               | 52        | 2.73%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 49        | 2.58%   |
| Chicony HD WebCam                                   | 41        | 2.16%   |
| Chicony USB2.0 HD UVC WebCam                        | 29        | 1.52%   |
| Sunplus Integrated_Webcam_HD                        | 26        | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 25        | 1.31%   |
| Syntek Integrated Camera                            | 24        | 1.26%   |
| Chicony HP HD Camera                                | 24        | 1.26%   |
| Quanta HP TrueVision HD Camera                      | 22        | 1.16%   |
| Quanta VGA WebCam                                   | 21        | 1.1%    |
| Quanta HD User Facing                               | 19        | 1%      |
| Realtek USB Camera                                  | 18        | 0.95%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 18        | 0.95%   |
| Microdia Integrated Webcam                          | 17        | 0.89%   |
| Lite-On Integrated Camera                           | 17        | 0.89%   |
| Acer SunplusIT Integrated Camera                    | 17        | 0.89%   |
| Chicony Chromebook HD Camera                        | 15        | 0.79%   |
| Quanta HP HD Camera                                 | 14        | 0.74%   |
| Chicony HP TrueVision HD Camera                     | 14        | 0.74%   |
| IMC Networks USB 2.0 Camera                         | 13        | 0.68%   |
| Chicony Integrated Camera (1280x720@30)             | 13        | 0.68%   |
| Chicony HD User Facing                              | 13        | 0.68%   |
| Acer Lenovo EasyCamera                              | 13        | 0.68%   |
| Chicony HP Webcam                                   | 12        | 0.63%   |
| Chicony HP TrueVision HD                            | 12        | 0.63%   |
| Acer Lenovo Integrated Webcam                       | 12        | 0.63%   |
| Suyin HP TrueVision HD                              | 11        | 0.58%   |
| Quanta HD Webcam                                    | 11        | 0.58%   |
| Lite-On HP HD Camera                                | 11        | 0.58%   |
| IMC Networks HD Camera                              | 11        | 0.58%   |
| Apple Built-in iSight                               | 11        | 0.58%   |
| Sunplus HD WebCam                                   | 10        | 0.53%   |
| Lenovo Integrated Webcam                            | 10        | 0.53%   |
| Chicony USB2.0 Camera                               | 10        | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 141       | 35.16%  |
| Synaptics                          | 121       | 30.17%  |
| Shenzhen Goodix Technology         | 59        | 14.71%  |
| AuthenTec                          | 21        | 5.24%   |
| Upek                               | 20        | 4.99%   |
| Elan Microelectronics              | 16        | 3.99%   |
| LighTuning Technology              | 13        | 3.24%   |
| STMicroelectronics                 | 9         | 2.24%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 55        | 13.72%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 38        | 9.48%   |
| Shenzhen Goodix  FingerPrint Device                                        | 32        | 7.98%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 28        | 6.98%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 5.99%   |
| Unknown                                                                    | 22        | 5.49%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 20        | 4.99%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 4.49%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 3.49%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 3.24%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 2.74%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.74%   |
| Elan ELAN:Fingerprint                                                      | 10        | 2.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.24%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.75%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 7         | 1.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.5%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.5%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 1.5%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.5%    |
| Elan ELAN:ARM-M4                                                           | 6         | 1.5%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.25%   |
| Validity Sensors VFS491                                                    | 4         | 1%      |
| AuthenTec AES2810                                                          | 4         | 1%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.75%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.75%   |
| Synaptics  WBDI                                                            | 3         | 0.75%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.5%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.5%    |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.5%    |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.5%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.5%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.5%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.25%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.25%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.25%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 73        | 36.32%  |
| Broadcom                  | 69        | 34.33%  |
| Upek                      | 19        | 9.45%   |
| O2 Micro                  | 15        | 7.46%   |
| Lenovo                    | 13        | 6.47%   |
| Gemalto (was Gemplus)     | 3         | 1.49%   |
| Yubico.com                | 2         | 1%      |
| Aladdin Knowledge Systems | 2         | 1%      |
| SCM Microsystems          | 1         | 0.5%    |
| OmniKey                   | 1         | 0.5%    |
| Clay Logic                | 1         | 0.5%    |
| Cherry                    | 1         | 0.5%    |
| C3PO                      | 1         | 0.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 72        | 35.82%  |
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 10.95%  |
| Broadcom 58200                                                               | 21        | 10.45%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 19        | 9.45%   |
| Broadcom 5880                                                                | 16        | 7.96%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 13        | 6.47%   |
| Lenovo Integrated Smart Card Reader                                          | 13        | 6.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 4.48%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1%      |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1%      |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1%      |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1%      |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.5%    |
| OmniKey CardMan 4321                                                         | 1         | 0.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.5%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.5%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.5%    |
| C3PO LTC31v2                                                                 | 1         | 0.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.5%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1593      | 59.11%  |
| 1     | 851       | 31.58%  |
| 2     | 199       | 7.38%   |
| 3     | 45        | 1.67%   |
| 4     | 4         | 0.15%   |
| 5     | 2         | 0.07%   |
| 6     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 399       | 29.27%  |
| Graphics card            | 354       | 25.97%  |
| Multimedia controller    | 192       | 14.09%  |
| Chipcard                 | 184       | 13.5%   |
| Net/wireless             | 120       | 8.8%    |
| Bluetooth                | 28        | 2.05%   |
| Storage                  | 19        | 1.39%   |
| Communication controller | 18        | 1.32%   |
| Card reader              | 16        | 1.17%   |
| Camera                   | 11        | 0.81%   |
| Sound                    | 5         | 0.37%   |
| Network                  | 4         | 0.29%   |
| Net/ethernet             | 4         | 0.29%   |
| Modem                    | 3         | 0.22%   |
| Unassigned class         | 2         | 0.15%   |
| Flash memory             | 2         | 0.15%   |
| Tv card                  | 1         | 0.07%   |
| Firewire controller      | 1         | 0.07%   |

