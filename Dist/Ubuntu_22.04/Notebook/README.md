Ubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 2554

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | GF65 Thin 9SEXR             | [537828a21f](https://linux-hardware.org/?probe=537828a21f) | Oct 01, 2022 |
| Acer          | Aspire 5920G                | [9bd67cf4f9](https://linux-hardware.org/?probe=9bd67cf4f9) | Oct 01, 2022 |
| Sony          | VPCCA15FX                   | [5063ea411b](https://linux-hardware.org/?probe=5063ea411b) | Oct 01, 2022 |
| Sony          | VPCCA15FX                   | [96eb3d8cf7](https://linux-hardware.org/?probe=96eb3d8cf7) | Oct 01, 2022 |
| Lenovo        | V130-15IKB 81HN             | [44a4ed90e1](https://linux-hardware.org/?probe=44a4ed90e1) | Oct 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [6525098252](https://linux-hardware.org/?probe=6525098252) | Oct 01, 2022 |
| Lenovo        | G400s VILG1                 | [e666344187](https://linux-hardware.org/?probe=e666344187) | Oct 01, 2022 |
| Acer          | Enduro EN314-51W            | [46782cf8f5](https://linux-hardware.org/?probe=46782cf8f5) | Oct 01, 2022 |
| Dell          | Latitude E5250              | [aeb221e727](https://linux-hardware.org/?probe=aeb221e727) | Oct 01, 2022 |
| Dell          | Latitude E5250              | [43f7cf1b59](https://linux-hardware.org/?probe=43f7cf1b59) | Oct 01, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [34006e3b46](https://linux-hardware.org/?probe=34006e3b46) | Oct 01, 2022 |
| HP            | ProBook 430 G7              | [bf25686a1f](https://linux-hardware.org/?probe=bf25686a1f) | Oct 01, 2022 |
| Dell          | Latitude 5480               | [ec9593f051](https://linux-hardware.org/?probe=ec9593f051) | Oct 01, 2022 |
| Notebook      | W330SU2                     | [a5d5500584](https://linux-hardware.org/?probe=a5d5500584) | Oct 01, 2022 |
| HP            | Pavilion 17                 | [fa2e48904a](https://linux-hardware.org/?probe=fa2e48904a) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | [571271ed93](https://linux-hardware.org/?probe=571271ed93) | Sep 30, 2022 |
| MSI           | Modern 14 A10M              | [9da1f3fe66](https://linux-hardware.org/?probe=9da1f3fe66) | Sep 30, 2022 |
| Dell          | Latitude 5530               | [43874dad6d](https://linux-hardware.org/?probe=43874dad6d) | Sep 30, 2022 |
| SANTECH       | NHx0EH_EJ_EK                | [01366bbeb7](https://linux-hardware.org/?probe=01366bbeb7) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [87c9436154](https://linux-hardware.org/?probe=87c9436154) | Sep 30, 2022 |
| HP            | Notebook                    | [a30c1af9a5](https://linux-hardware.org/?probe=a30c1af9a5) | Sep 30, 2022 |
| Acer          | Aspire E1-531               | [fbe026b995](https://linux-hardware.org/?probe=fbe026b995) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| SIEMENS       | SIMATIC ITP1000             | [adbd7dbca6](https://linux-hardware.org/?probe=adbd7dbca6) | Sep 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6bcbc9e08c](https://linux-hardware.org/?probe=6bcbc9e08c) | Sep 30, 2022 |
| NEC Comput... | PC-VRL21FB6S3R7             | [2001e2e28e](https://linux-hardware.org/?probe=2001e2e28e) | Sep 30, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CBA    | [4cad2a770c](https://linux-hardware.org/?probe=4cad2a770c) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480s 20L7001YU... | [929514123f](https://linux-hardware.org/?probe=929514123f) | Sep 30, 2022 |
| Acer          | Aspire E5-521               | [a55d68e93c](https://linux-hardware.org/?probe=a55d68e93c) | Sep 30, 2022 |
| Google        | Relm                        | [e440e5c1cc](https://linux-hardware.org/?probe=e440e5c1cc) | Sep 30, 2022 |
| Apple         | MacBookPro16,1              | [03f56ec19b](https://linux-hardware.org/?probe=03f56ec19b) | Sep 30, 2022 |
| Samsung       | R430/P430/R480              | [09795617ab](https://linux-hardware.org/?probe=09795617ab) | Sep 30, 2022 |
| Lenovo        | G500s 20245                 | [b9001f7817](https://linux-hardware.org/?probe=b9001f7817) | Sep 29, 2022 |
| Toshiba       | TECRA M10                   | [64ad67c8e9](https://linux-hardware.org/?probe=64ad67c8e9) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [36ad3c69ee](https://linux-hardware.org/?probe=36ad3c69ee) | Sep 29, 2022 |
| Acer          | Aspire ES1-311              | [0f40a045a9](https://linux-hardware.org/?probe=0f40a045a9) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [bd2dea6653](https://linux-hardware.org/?probe=bd2dea6653) | Sep 29, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [be74c01cca](https://linux-hardware.org/?probe=be74c01cca) | Sep 29, 2022 |
| Acer          | Aspire A715-72G             | [8b7e129d4a](https://linux-hardware.org/?probe=8b7e129d4a) | Sep 29, 2022 |
| Lenovo        | ThinkPad P53 MWS 15.6 (Q... | [8990060646](https://linux-hardware.org/?probe=8990060646) | Sep 29, 2022 |
| Apple         | MacBookPro3,1               | [00f2a6e705](https://linux-hardware.org/?probe=00f2a6e705) | Sep 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [54bc787611](https://linux-hardware.org/?probe=54bc787611) | Sep 29, 2022 |
| Dell          | XPS 13 9370                 | [4e0be93d26](https://linux-hardware.org/?probe=4e0be93d26) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Dell          | Latitude E7250              | [bed2e025b0](https://linux-hardware.org/?probe=bed2e025b0) | Sep 29, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [82528435d8](https://linux-hardware.org/?probe=82528435d8) | Sep 29, 2022 |
| MSI           | Creator Z17 A12UHST         | [4b9249b9b0](https://linux-hardware.org/?probe=4b9249b9b0) | Sep 29, 2022 |
| HP            | ProBook 6560b               | [902ef8ef79](https://linux-hardware.org/?probe=902ef8ef79) | Sep 29, 2022 |
| Razer         | Blade                       | [63a4e5f829](https://linux-hardware.org/?probe=63a4e5f829) | Sep 29, 2022 |
| HUAWEI        | HVY-WXX9                    | [4f2655de78](https://linux-hardware.org/?probe=4f2655de78) | Sep 29, 2022 |
| Sony          | VPCEH12FX                   | [037cda52fd](https://linux-hardware.org/?probe=037cda52fd) | Sep 29, 2022 |
| MSI           | Modern 14 A10M              | [5c5666fa97](https://linux-hardware.org/?probe=5c5666fa97) | Sep 29, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [65f56cc48b](https://linux-hardware.org/?probe=65f56cc48b) | Sep 29, 2022 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [0cbacebb95](https://linux-hardware.org/?probe=0cbacebb95) | Sep 29, 2022 |
| Dell          | XPS 15 9570                 | [eb3798c367](https://linux-hardware.org/?probe=eb3798c367) | Sep 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [cd08dccca4](https://linux-hardware.org/?probe=cd08dccca4) | Sep 28, 2022 |
| Notebook      | PB50_70RF,RD,RC             | [d56e485c88](https://linux-hardware.org/?probe=d56e485c88) | Sep 28, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [a3fc8eb1bc](https://linux-hardware.org/?probe=a3fc8eb1bc) | Sep 28, 2022 |
| Lenovo        | Legion S7 15IMH5 82BC       | [4ecc5d01c1](https://linux-hardware.org/?probe=4ecc5d01c1) | Sep 28, 2022 |
| Dell          | Latitude E7250              | [4bf6378dde](https://linux-hardware.org/?probe=4bf6378dde) | Sep 28, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [d5a4d2ae41](https://linux-hardware.org/?probe=d5a4d2ae41) | Sep 28, 2022 |
| Dell          | Latitude E5430 non-vPro     | [12e886f006](https://linux-hardware.org/?probe=12e886f006) | Sep 28, 2022 |
| Dell          | Vostro 15 3515              | [7e4413a053](https://linux-hardware.org/?probe=7e4413a053) | Sep 28, 2022 |
| Dell          | XPS 13 9350                 | [23142407b0](https://linux-hardware.org/?probe=23142407b0) | Sep 28, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [bbd715eb5a](https://linux-hardware.org/?probe=bbd715eb5a) | Sep 28, 2022 |
| Medion        | E6234                       | [19f1d7841e](https://linux-hardware.org/?probe=19f1d7841e) | Sep 28, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [a64f339e70](https://linux-hardware.org/?probe=a64f339e70) | Sep 28, 2022 |
| Dell          | Latitude 3410               | [82fe1556b6](https://linux-hardware.org/?probe=82fe1556b6) | Sep 28, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [78badcba3c](https://linux-hardware.org/?probe=78badcba3c) | Sep 28, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9271d6a014](https://linux-hardware.org/?probe=9271d6a014) | Sep 28, 2022 |
| Apple         | MacBookPro9,2               | [6ea648bc51](https://linux-hardware.org/?probe=6ea648bc51) | Sep 28, 2022 |
| Acer          | Aspire E5-573               | [f7e628a5a1](https://linux-hardware.org/?probe=f7e628a5a1) | Sep 28, 2022 |
| Positivo      | S14CT01                     | [66e0c53646](https://linux-hardware.org/?probe=66e0c53646) | Sep 28, 2022 |
| Unknown       | Unknown                     | [3e450900da](https://linux-hardware.org/?probe=3e450900da) | Sep 28, 2022 |
| Apple         | MacBookPro15,2              | [2e6164b675](https://linux-hardware.org/?probe=2e6164b675) | Sep 28, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | [6eab6db53b](https://linux-hardware.org/?probe=6eab6db53b) | Sep 27, 2022 |
| Acer          | Aspire 5750G                | [f73c1084d0](https://linux-hardware.org/?probe=f73c1084d0) | Sep 27, 2022 |
| HP            | ProBook 450 G2              | [a9c7d575cd](https://linux-hardware.org/?probe=a9c7d575cd) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [47acb38827](https://linux-hardware.org/?probe=47acb38827) | Sep 27, 2022 |
| Dell          | Precision 3561              | [77a4030052](https://linux-hardware.org/?probe=77a4030052) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | [e5405dd3d8](https://linux-hardware.org/?probe=e5405dd3d8) | Sep 27, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [d0f8e8a0f6](https://linux-hardware.org/?probe=d0f8e8a0f6) | Sep 27, 2022 |
| Dell          | Latitude E7470              | [5bdc528b5a](https://linux-hardware.org/?probe=5bdc528b5a) | Sep 27, 2022 |
| Philco        | PNB14.1AC14S128W10          | [ee4bc98535](https://linux-hardware.org/?probe=ee4bc98535) | Sep 27, 2022 |
| HP            | Pavilion 10 TS              | [28003748e6](https://linux-hardware.org/?probe=28003748e6) | Sep 27, 2022 |
| HP            | ENVY m7 Notebook            | [c2739df54b](https://linux-hardware.org/?probe=c2739df54b) | Sep 27, 2022 |
| HP            | 635                         | [0509987782](https://linux-hardware.org/?probe=0509987782) | Sep 27, 2022 |
| Lenovo        | ThinkPad T410 2537AT9       | [553490bb4c](https://linux-hardware.org/?probe=553490bb4c) | Sep 27, 2022 |
| HP            | ProBook 450 G2              | [2935c5bedd](https://linux-hardware.org/?probe=2935c5bedd) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [ae7c83bb37](https://linux-hardware.org/?probe=ae7c83bb37) | Sep 27, 2022 |
| Dell          | Inspiron 5570               | [3735a32f9e](https://linux-hardware.org/?probe=3735a32f9e) | Sep 27, 2022 |
| Samsung       | R425/R525                   | [a5b0ee0a18](https://linux-hardware.org/?probe=a5b0ee0a18) | Sep 27, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3aa314d706](https://linux-hardware.org/?probe=3aa314d706) | Sep 27, 2022 |
| HP            | Laptop 17-cp0xxx            | [895fae1f2e](https://linux-hardware.org/?probe=895fae1f2e) | Sep 27, 2022 |
| ASUSTek       | G73Jh                       | [ac96a56edf](https://linux-hardware.org/?probe=ac96a56edf) | Sep 27, 2022 |
| Lenovo        | ThinkPad T480s 20L8S6WP0... | [d0149ee0e2](https://linux-hardware.org/?probe=d0149ee0e2) | Sep 27, 2022 |
| Dell          | XPS 15 9500                 | [d9d87f101a](https://linux-hardware.org/?probe=d9d87f101a) | Sep 27, 2022 |
| Dell          | XPS 13 9310                 | [6f9bc0cdba](https://linux-hardware.org/?probe=6f9bc0cdba) | Sep 26, 2022 |
| Dell          | XPS 13 9310                 | [d65cd8309b](https://linux-hardware.org/?probe=d65cd8309b) | Sep 26, 2022 |
| Dell          | Latitude 5420               | [bd81c07917](https://linux-hardware.org/?probe=bd81c07917) | Sep 26, 2022 |
| Dell          | Inspiron 1525               | [42ea8221af](https://linux-hardware.org/?probe=42ea8221af) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [3acb168799](https://linux-hardware.org/?probe=3acb168799) | Sep 26, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [9a1514cc61](https://linux-hardware.org/?probe=9a1514cc61) | Sep 26, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [fd7e096a4b](https://linux-hardware.org/?probe=fd7e096a4b) | Sep 26, 2022 |
| HP            | Unknown                     | [e8906c977c](https://linux-hardware.org/?probe=e8906c977c) | Sep 26, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [70860ec433](https://linux-hardware.org/?probe=70860ec433) | Sep 26, 2022 |
| ASUSTek       | X580VD                      | [378e1d3133](https://linux-hardware.org/?probe=378e1d3133) | Sep 26, 2022 |
| HP            | ProBook 650 G1              | [bdcb5090f0](https://linux-hardware.org/?probe=bdcb5090f0) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| GIADA         | ChiefRiver Platform         | [d0f71cdc7f](https://linux-hardware.org/?probe=d0f71cdc7f) | Sep 26, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7c8030e423](https://linux-hardware.org/?probe=7c8030e423) | Sep 26, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | [31235a45b5](https://linux-hardware.org/?probe=31235a45b5) | Sep 26, 2022 |
| Lenovo        | ThinkPad T480 20L6SCWK00    | [60933ed48b](https://linux-hardware.org/?probe=60933ed48b) | Sep 26, 2022 |
| Acer          | Aspire A514-54              | [bab009e0b7](https://linux-hardware.org/?probe=bab009e0b7) | Sep 26, 2022 |
| Insyde        | WindTab89                   | [0073af9597](https://linux-hardware.org/?probe=0073af9597) | Sep 26, 2022 |
| Insyde        | WindTab89                   | [6935ebecaa](https://linux-hardware.org/?probe=6935ebecaa) | Sep 26, 2022 |
| Dell          | Latitude 7420               | [0834411088](https://linux-hardware.org/?probe=0834411088) | Sep 26, 2022 |
| Dell          | Latitude E7470              | [1dba765507](https://linux-hardware.org/?probe=1dba765507) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [cb5f6f279b](https://linux-hardware.org/?probe=cb5f6f279b) | Sep 26, 2022 |
| Lenovo        | ThinkPad Edge E430 3254A... | [3f11c520e0](https://linux-hardware.org/?probe=3f11c520e0) | Sep 26, 2022 |
| ASUSTek       | K55VJ                       | [8e87d041c3](https://linux-hardware.org/?probe=8e87d041c3) | Sep 26, 2022 |
| HP            | Spectre Pro x360 G2         | [d9248f7b2e](https://linux-hardware.org/?probe=d9248f7b2e) | Sep 26, 2022 |
| Acer          | Aspire A515-55              | [a9ac678198](https://linux-hardware.org/?probe=a9ac678198) | Sep 26, 2022 |
| Acer          | Aspire A515-55              | [8e66a480f3](https://linux-hardware.org/?probe=8e66a480f3) | Sep 26, 2022 |
| Dell          | Inspiron 11-3168            | [6b1d418929](https://linux-hardware.org/?probe=6b1d418929) | Sep 26, 2022 |
| Samsung       | 670Z5E                      | [6bce247e38](https://linux-hardware.org/?probe=6bce247e38) | Sep 26, 2022 |
| AZW           | SEi                         | [ca815a2e20](https://linux-hardware.org/?probe=ca815a2e20) | Sep 26, 2022 |
| HP            | ProBook 6560b               | [96637a94a6](https://linux-hardware.org/?probe=96637a94a6) | Sep 25, 2022 |
| Jumper        | EZbook                      | [1af58cd7e7](https://linux-hardware.org/?probe=1af58cd7e7) | Sep 25, 2022 |
| ASUSTek       | G750JX                      | [4ce2831fac](https://linux-hardware.org/?probe=4ce2831fac) | Sep 25, 2022 |
| NSX           | Celeron 14                  | [b8fdb14beb](https://linux-hardware.org/?probe=b8fdb14beb) | Sep 25, 2022 |
| Positivo      | S14SL01                     | [a6b3c260f4](https://linux-hardware.org/?probe=a6b3c260f4) | Sep 25, 2022 |
| NSX           | Celeron 14                  | [1d358a2828](https://linux-hardware.org/?probe=1d358a2828) | Sep 25, 2022 |
| Acer          | Aspire 3810T                | [de19c5a7e9](https://linux-hardware.org/?probe=de19c5a7e9) | Sep 25, 2022 |
| HP            | EliteBook 840 G3            | [2ad6238f03](https://linux-hardware.org/?probe=2ad6238f03) | Sep 25, 2022 |
| Acer          | P5WE0                       | [124f7bdd77](https://linux-hardware.org/?probe=124f7bdd77) | Sep 25, 2022 |
| Unknown       | A116C1_1                    | [470cd9917c](https://linux-hardware.org/?probe=470cd9917c) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| Lenovo        | IdeaPad3-15ADA05 81W1       | [d2192ee6f0](https://linux-hardware.org/?probe=d2192ee6f0) | Sep 25, 2022 |
| Acer          | Swift SF314-71              | [3414420bc7](https://linux-hardware.org/?probe=3414420bc7) | Sep 25, 2022 |
| Positivo      | S14SL01                     | [e09fcd6e38](https://linux-hardware.org/?probe=e09fcd6e38) | Sep 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3e5af3e86c](https://linux-hardware.org/?probe=3e5af3e86c) | Sep 25, 2022 |
| AMI           | Intel                       | [56de8f8b8a](https://linux-hardware.org/?probe=56de8f8b8a) | Sep 25, 2022 |
| Dell          | Latitude 13                 | [28d623103e](https://linux-hardware.org/?probe=28d623103e) | Sep 25, 2022 |
| AMI           | Intel                       | [330585dcd8](https://linux-hardware.org/?probe=330585dcd8) | Sep 25, 2022 |
| Dell          | Inspiron 5570               | [6516021810](https://linux-hardware.org/?probe=6516021810) | Sep 25, 2022 |
| Dell          | XPS 15 9500                 | [1095e2f7f0](https://linux-hardware.org/?probe=1095e2f7f0) | Sep 25, 2022 |
| HP            | ProBook 450 G5              | [262ff53f6a](https://linux-hardware.org/?probe=262ff53f6a) | Sep 25, 2022 |
| Avell High... | A70 MOB                     | [b867406b76](https://linux-hardware.org/?probe=b867406b76) | Sep 25, 2022 |
| Dell          | Inspiron 15 5510            | [cfda1aa63a](https://linux-hardware.org/?probe=cfda1aa63a) | Sep 25, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | [fee2b2d57e](https://linux-hardware.org/?probe=fee2b2d57e) | Sep 24, 2022 |
| Acer          | Aspire E5-551               | [693dca23b3](https://linux-hardware.org/?probe=693dca23b3) | Sep 24, 2022 |
| HP            | Stream 11 Pro               | [01a4c35ec9](https://linux-hardware.org/?probe=01a4c35ec9) | Sep 24, 2022 |
| HP            | Stream 11 Pro               | [46b9ac9732](https://linux-hardware.org/?probe=46b9ac9732) | Sep 24, 2022 |
| HP            | Stream 11 Pro               | [e562c8160a](https://linux-hardware.org/?probe=e562c8160a) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [118cf21173](https://linux-hardware.org/?probe=118cf21173) | Sep 24, 2022 |
| Dell          | Latitude 3410               | [ba10ea9fc5](https://linux-hardware.org/?probe=ba10ea9fc5) | Sep 24, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [84d47822bf](https://linux-hardware.org/?probe=84d47822bf) | Sep 24, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [3afd2e892b](https://linux-hardware.org/?probe=3afd2e892b) | Sep 24, 2022 |
| Lenovo        | ThinkPad E470 20H1004UIG    | [310337a455](https://linux-hardware.org/?probe=310337a455) | Sep 24, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2322475867](https://linux-hardware.org/?probe=2322475867) | Sep 24, 2022 |
| Gigabyte      | AORUS 5 SE                  | [c188e2c5b5](https://linux-hardware.org/?probe=c188e2c5b5) | Sep 24, 2022 |
| ASUSTek       | X200MA                      | [753d8c4211](https://linux-hardware.org/?probe=753d8c4211) | Sep 24, 2022 |
| Dell          | G15 5515                    | [ae769dae75](https://linux-hardware.org/?probe=ae769dae75) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [8f29c3dc10](https://linux-hardware.org/?probe=8f29c3dc10) | Sep 24, 2022 |
| Dell          | Vostro V131                 | [809655978a](https://linux-hardware.org/?probe=809655978a) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [d1ed6b20cf](https://linux-hardware.org/?probe=d1ed6b20cf) | Sep 24, 2022 |
| Toshiba       | Satellite A305              | [9e04fb330b](https://linux-hardware.org/?probe=9e04fb330b) | Sep 24, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [b01a9ac97f](https://linux-hardware.org/?probe=b01a9ac97f) | Sep 24, 2022 |
| Acer          | Swift SF315-52              | [b9e88a43d8](https://linux-hardware.org/?probe=b9e88a43d8) | Sep 24, 2022 |
| HP            | Laptop 15-da0xxx            | [da14d41e78](https://linux-hardware.org/?probe=da14d41e78) | Sep 24, 2022 |
| Dell          | G15 5515                    | [893c248dec](https://linux-hardware.org/?probe=893c248dec) | Sep 24, 2022 |
| Dell          | Latitude 5420               | [170a3248f6](https://linux-hardware.org/?probe=170a3248f6) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [9fbedd972e](https://linux-hardware.org/?probe=9fbedd972e) | Sep 24, 2022 |
| Dell          | Latitude E6500              | [491ad19866](https://linux-hardware.org/?probe=491ad19866) | Sep 24, 2022 |
| MSI           | GF65 Thin 9SEXR             | [b6f7e58295](https://linux-hardware.org/?probe=b6f7e58295) | Sep 24, 2022 |
| HP            | ProBook 4530s               | [7c6fe43c69](https://linux-hardware.org/?probe=7c6fe43c69) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [0d4570c1d6](https://linux-hardware.org/?probe=0d4570c1d6) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [02787c733c](https://linux-hardware.org/?probe=02787c733c) | Sep 23, 2022 |
| Lenovo        | Legion R9000K2021H 82N6     | [d739547049](https://linux-hardware.org/?probe=d739547049) | Sep 23, 2022 |
| Acer          | Aspire E5-771G              | [39dc43058e](https://linux-hardware.org/?probe=39dc43058e) | Sep 23, 2022 |
| ASUSTek       | N750JV                      | [f69fe7dacf](https://linux-hardware.org/?probe=f69fe7dacf) | Sep 23, 2022 |
| Toshiba       | Satellite P205              | [2a1450578e](https://linux-hardware.org/?probe=2a1450578e) | Sep 23, 2022 |
| Dell          | Inspiron 15 5510            | [fe7ae61ecd](https://linux-hardware.org/?probe=fe7ae61ecd) | Sep 23, 2022 |
| HP            | ProBook 4530s               | [a533c17d9f](https://linux-hardware.org/?probe=a533c17d9f) | Sep 23, 2022 |
| Dell          | Inspiron 5566               | [4ed9eae431](https://linux-hardware.org/?probe=4ed9eae431) | Sep 23, 2022 |
| Toshiba       | Satellite P205              | [98e97d946a](https://linux-hardware.org/?probe=98e97d946a) | Sep 23, 2022 |
| NEC Comput... | PC-VK25LCZDM                | [97ab1f723e](https://linux-hardware.org/?probe=97ab1f723e) | Sep 23, 2022 |
| Dell          | Latitude E6330              | [5f1a272734](https://linux-hardware.org/?probe=5f1a272734) | Sep 23, 2022 |
| Toshiba       | Satellite C850-F21B         | [6d336c1e89](https://linux-hardware.org/?probe=6d336c1e89) | Sep 23, 2022 |
| Toshiba       | Satellite C850-F21B         | [dc1e853bbf](https://linux-hardware.org/?probe=dc1e853bbf) | Sep 23, 2022 |
| HP            | EliteBook 2760p             | [7d71278ac4](https://linux-hardware.org/?probe=7d71278ac4) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [67ec6c656b](https://linux-hardware.org/?probe=67ec6c656b) | Sep 23, 2022 |
| HP            | EliteBook 840 G5            | [872eafe5f7](https://linux-hardware.org/?probe=872eafe5f7) | Sep 23, 2022 |
| HP            | EliteBook 840 G5            | [68338b3080](https://linux-hardware.org/?probe=68338b3080) | Sep 23, 2022 |
| Acer          | TMP645-M                    | [83b27c389c](https://linux-hardware.org/?probe=83b27c389c) | Sep 23, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [b2768e9e6d](https://linux-hardware.org/?probe=b2768e9e6d) | Sep 23, 2022 |
| Lenovo        | G500 20236                  | [0707ef3cf0](https://linux-hardware.org/?probe=0707ef3cf0) | Sep 23, 2022 |
| HP            | Pavilion 10 TS              | [1186e5b5d8](https://linux-hardware.org/?probe=1186e5b5d8) | Sep 23, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [3f9e2bb677](https://linux-hardware.org/?probe=3f9e2bb677) | Sep 23, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [10103bf87f](https://linux-hardware.org/?probe=10103bf87f) | Sep 23, 2022 |
| HP            | ENVY Notebook               | [7335c99e6a](https://linux-hardware.org/?probe=7335c99e6a) | Sep 23, 2022 |
| HP            | 15 TS                       | [6577aa9bb8](https://linux-hardware.org/?probe=6577aa9bb8) | Sep 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [845256127e](https://linux-hardware.org/?probe=845256127e) | Sep 23, 2022 |
| HP            | Laptop 17-by2xxx            | [3e71e40ba0](https://linux-hardware.org/?probe=3e71e40ba0) | Sep 22, 2022 |
| HP            | Laptop 17-by2xxx            | [4af5f4bacc](https://linux-hardware.org/?probe=4af5f4bacc) | Sep 22, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Acer          | Aspire A515-55              | [fb1cce613c](https://linux-hardware.org/?probe=fb1cce613c) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| HP            | 255 G4 Notebook PC          | [655e2f4cb5](https://linux-hardware.org/?probe=655e2f4cb5) | Sep 22, 2022 |
| MSI           | GL63 9SDK                   | [83a78aa62b](https://linux-hardware.org/?probe=83a78aa62b) | Sep 22, 2022 |
| MSI           | GL63 9SDK                   | [a0ba440640](https://linux-hardware.org/?probe=a0ba440640) | Sep 22, 2022 |
| Dell          | XPS 9320                    | [6866f3105c](https://linux-hardware.org/?probe=6866f3105c) | Sep 22, 2022 |
| HP            | ProBook 6475b               | [fd9242f579](https://linux-hardware.org/?probe=fd9242f579) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | [58b83fee74](https://linux-hardware.org/?probe=58b83fee74) | Sep 22, 2022 |
| Dell          | Latitude 5501               | [f40716377a](https://linux-hardware.org/?probe=f40716377a) | Sep 22, 2022 |
| AXIOO         | SlimBook 11                 | [c658e4f48c](https://linux-hardware.org/?probe=c658e4f48c) | Sep 22, 2022 |
| MSI           | Creator Z17 A12UHST         | [06c854fd7b](https://linux-hardware.org/?probe=06c854fd7b) | Sep 22, 2022 |
| Lenovo        | ThinkPad E595 20NFA000AU    | [a01352810a](https://linux-hardware.org/?probe=a01352810a) | Sep 22, 2022 |
| Acer          | Aspire E5-571               | [dc6bf82565](https://linux-hardware.org/?probe=dc6bf82565) | Sep 22, 2022 |
| HP            | EliteBook 8560p             | [c018c3287e](https://linux-hardware.org/?probe=c018c3287e) | Sep 22, 2022 |
| ASUSTek       | G73Jh                       | [e40a8996c4](https://linux-hardware.org/?probe=e40a8996c4) | Sep 22, 2022 |
| HP            | 15 Notebook PC              | [0643e29e9d](https://linux-hardware.org/?probe=0643e29e9d) | Sep 22, 2022 |
| HP            | Laptop 15-da0xxx            | [d889f0c2ee](https://linux-hardware.org/?probe=d889f0c2ee) | Sep 22, 2022 |
| HONOR         | HLYL-WXX9                   | [1da06fd0ba](https://linux-hardware.org/?probe=1da06fd0ba) | Sep 21, 2022 |
| Dell          | Inspiron 5566               | [183f486a54](https://linux-hardware.org/?probe=183f486a54) | Sep 21, 2022 |
| Acer          | Aspire E5-575G              | [cbbf373937](https://linux-hardware.org/?probe=cbbf373937) | Sep 21, 2022 |
| Acer          | Aspire E5-575G              | [4482b2913a](https://linux-hardware.org/?probe=4482b2913a) | Sep 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [74d69dbd69](https://linux-hardware.org/?probe=74d69dbd69) | Sep 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [7dc3fbcf76](https://linux-hardware.org/?probe=7dc3fbcf76) | Sep 21, 2022 |
| HP            | Laptop 15-da0xxx            | [e234a2b52a](https://linux-hardware.org/?probe=e234a2b52a) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | [17945ad430](https://linux-hardware.org/?probe=17945ad430) | Sep 21, 2022 |
| Dell          | Precision 7550              | [347372a20a](https://linux-hardware.org/?probe=347372a20a) | Sep 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [982931b71f](https://linux-hardware.org/?probe=982931b71f) | Sep 21, 2022 |
| HP            | 250 G8 Notebook PC          | [49c7f8f204](https://linux-hardware.org/?probe=49c7f8f204) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | [dddf15cbf5](https://linux-hardware.org/?probe=dddf15cbf5) | Sep 21, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [98d21fb774](https://linux-hardware.org/?probe=98d21fb774) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | [21404b14d1](https://linux-hardware.org/?probe=21404b14d1) | Sep 21, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [56bff32d34](https://linux-hardware.org/?probe=56bff32d34) | Sep 21, 2022 |
| Lenovo        | ThinkPad W500 4061BC8       | [f2280ae816](https://linux-hardware.org/?probe=f2280ae816) | Sep 21, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [c859bf5e24](https://linux-hardware.org/?probe=c859bf5e24) | Sep 21, 2022 |
| Medion        | E6220                       | [59b39f54d8](https://linux-hardware.org/?probe=59b39f54d8) | Sep 21, 2022 |
| HP            | Pavilion g7                 | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| HP            | Laptop 15-da0xxx            | [a454bf3aa7](https://linux-hardware.org/?probe=a454bf3aa7) | Sep 20, 2022 |
| HP            | EliteBook 840 G2            | [030ce84327](https://linux-hardware.org/?probe=030ce84327) | Sep 20, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [824c786d4b](https://linux-hardware.org/?probe=824c786d4b) | Sep 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [849246d9f3](https://linux-hardware.org/?probe=849246d9f3) | Sep 20, 2022 |
| HP            | ProBook 6560b               | [743f401352](https://linux-hardware.org/?probe=743f401352) | Sep 20, 2022 |
| HP            | EliteBook 840 G3            | [233ba928b8](https://linux-hardware.org/?probe=233ba928b8) | Sep 20, 2022 |
| HP            | EliteBook 830 G5            | [5d6c1cd007](https://linux-hardware.org/?probe=5d6c1cd007) | Sep 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [21c74278f8](https://linux-hardware.org/?probe=21c74278f8) | Sep 20, 2022 |
| HP            | EliteBook 8760w             | [858fd4f09e](https://linux-hardware.org/?probe=858fd4f09e) | Sep 20, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3e80cdec5b](https://linux-hardware.org/?probe=3e80cdec5b) | Sep 20, 2022 |
| Dell          | Latitude E4310              | [c77a454d4e](https://linux-hardware.org/?probe=c77a454d4e) | Sep 20, 2022 |
| Lenovo        | E50-80 80J2                 | [a399d96de2](https://linux-hardware.org/?probe=a399d96de2) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [9d85bdedd3](https://linux-hardware.org/?probe=9d85bdedd3) | Sep 20, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [e91328a3c2](https://linux-hardware.org/?probe=e91328a3c2) | Sep 20, 2022 |
| Sony          | VPCEH12FX                   | [1728d15dbf](https://linux-hardware.org/?probe=1728d15dbf) | Sep 20, 2022 |
| Dell          | Latitude E4310              | [4e8bf046d8](https://linux-hardware.org/?probe=4e8bf046d8) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [329f95e326](https://linux-hardware.org/?probe=329f95e326) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [5891712135](https://linux-hardware.org/?probe=5891712135) | Sep 19, 2022 |
| HP            | EliteBook 850 G3            | [7cfeb3607a](https://linux-hardware.org/?probe=7cfeb3607a) | Sep 19, 2022 |
| Samsung       | 300E5K/300E5Q               | [aaedf90f31](https://linux-hardware.org/?probe=aaedf90f31) | Sep 19, 2022 |
| Dell          | Latitude E6320              | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| Dell          | Latitude E6540              | [d13fb4e622](https://linux-hardware.org/?probe=d13fb4e622) | Sep 19, 2022 |
| ASUSTek       | UX490UA                     | [e953c29d50](https://linux-hardware.org/?probe=e953c29d50) | Sep 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [6b6ad790c5](https://linux-hardware.org/?probe=6b6ad790c5) | Sep 19, 2022 |
| Lenovo        | Yoga 3 14 80JH              | [7b17bd93c0](https://linux-hardware.org/?probe=7b17bd93c0) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | [5db637f345](https://linux-hardware.org/?probe=5db637f345) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | [f0bbe89fe8](https://linux-hardware.org/?probe=f0bbe89fe8) | Sep 19, 2022 |
| HONOR         | HLYL-WXX9                   | [1f91c596f5](https://linux-hardware.org/?probe=1f91c596f5) | Sep 19, 2022 |
| HP            | 470 G7 Notebook PC          | [a9f6ad0c32](https://linux-hardware.org/?probe=a9f6ad0c32) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | [8bf0000c61](https://linux-hardware.org/?probe=8bf0000c61) | Sep 19, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [44afa82c4a](https://linux-hardware.org/?probe=44afa82c4a) | Sep 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [61cbfb879a](https://linux-hardware.org/?probe=61cbfb879a) | Sep 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d2e3e6c9bb](https://linux-hardware.org/?probe=d2e3e6c9bb) | Sep 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [e404df9b2f](https://linux-hardware.org/?probe=e404df9b2f) | Sep 19, 2022 |
| Dell          | Inspiron 7577               | [fe5d00b2c8](https://linux-hardware.org/?probe=fe5d00b2c8) | Sep 19, 2022 |
| Lenovo        | ThinkPad E480 20KNA040CD    | [8cd233ffbb](https://linux-hardware.org/?probe=8cd233ffbb) | Sep 19, 2022 |
| Acer          | Aspire A515-55              | [c932451f8e](https://linux-hardware.org/?probe=c932451f8e) | Sep 19, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [514dde2498](https://linux-hardware.org/?probe=514dde2498) | Sep 19, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [40629d6fbc](https://linux-hardware.org/?probe=40629d6fbc) | Sep 19, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [23f17e2f91](https://linux-hardware.org/?probe=23f17e2f91) | Sep 19, 2022 |
| Dell          | Precision 5530              | [37520b086e](https://linux-hardware.org/?probe=37520b086e) | Sep 18, 2022 |
| Lenovo        | E50-80 80J2                 | [1a538a3132](https://linux-hardware.org/?probe=1a538a3132) | Sep 18, 2022 |
| Unknown       | Unknown                     | [fab82ec455](https://linux-hardware.org/?probe=fab82ec455) | Sep 18, 2022 |
| MSI           | Prestige 14Evo A11MO        | [9af5848173](https://linux-hardware.org/?probe=9af5848173) | Sep 18, 2022 |
| Chuwi         | GemiBook                    | [c6ec4f6320](https://linux-hardware.org/?probe=c6ec4f6320) | Sep 18, 2022 |
| Dell          | Studio 1737                 | [7218731367](https://linux-hardware.org/?probe=7218731367) | Sep 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [465ce269fd](https://linux-hardware.org/?probe=465ce269fd) | Sep 18, 2022 |
| ASUSTek       | X553MA                      | [28839dfd9e](https://linux-hardware.org/?probe=28839dfd9e) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4aef09c37a](https://linux-hardware.org/?probe=4aef09c37a) | Sep 18, 2022 |
| Acer          | Aspire A315-56              | [644bb082f4](https://linux-hardware.org/?probe=644bb082f4) | Sep 18, 2022 |
| Samsung       | 670Z5E                      | [50758a53dd](https://linux-hardware.org/?probe=50758a53dd) | Sep 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [daa76ef1c9](https://linux-hardware.org/?probe=daa76ef1c9) | Sep 18, 2022 |
| Acer          | Aspire V3-571               | [3f20a5e69d](https://linux-hardware.org/?probe=3f20a5e69d) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b0a2728114](https://linux-hardware.org/?probe=b0a2728114) | Sep 17, 2022 |
| Lenovo        | ThinkPad E490 20N8005AEQ    | [1de60a584a](https://linux-hardware.org/?probe=1de60a584a) | Sep 17, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [8e5e19a8bd](https://linux-hardware.org/?probe=8e5e19a8bd) | Sep 17, 2022 |
| HP            | 250 G8 Notebook PC          | [6dd18a5a96](https://linux-hardware.org/?probe=6dd18a5a96) | Sep 17, 2022 |
| Dell          | Latitude 5520               | [3e023f86c9](https://linux-hardware.org/?probe=3e023f86c9) | Sep 17, 2022 |
| HP            | EliteBook 850 G3            | [2eee433657](https://linux-hardware.org/?probe=2eee433657) | Sep 17, 2022 |
| ASUSTek       | UX32VD                      | [324cafa8d2](https://linux-hardware.org/?probe=324cafa8d2) | Sep 17, 2022 |
| HUAWEI        | BOM-WXX9                    | [0c3d62f1c9](https://linux-hardware.org/?probe=0c3d62f1c9) | Sep 17, 2022 |
| Acer          | Swift SF314-71              | [0c383a03ad](https://linux-hardware.org/?probe=0c383a03ad) | Sep 17, 2022 |
| Acer          | Aspire 5820TG               | [df263f4d0b](https://linux-hardware.org/?probe=df263f4d0b) | Sep 17, 2022 |
| HP            | Laptop 15-db0xxx            | [c4a7f1814f](https://linux-hardware.org/?probe=c4a7f1814f) | Sep 16, 2022 |
| Dell          | Vostro 15 3510              | [d70dc7ab47](https://linux-hardware.org/?probe=d70dc7ab47) | Sep 16, 2022 |
| Dell          | Vostro 15 3510              | [0bcb975501](https://linux-hardware.org/?probe=0bcb975501) | Sep 16, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [5b94d00557](https://linux-hardware.org/?probe=5b94d00557) | Sep 16, 2022 |
| Dell          | XPS 17 9720                 | [88a30be903](https://linux-hardware.org/?probe=88a30be903) | Sep 16, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [e31f54dfa3](https://linux-hardware.org/?probe=e31f54dfa3) | Sep 16, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [cf4e574788](https://linux-hardware.org/?probe=cf4e574788) | Sep 16, 2022 |
| HP            | ZBook Firefly 14 inch G9... | [f543e0852f](https://linux-hardware.org/?probe=f543e0852f) | Sep 16, 2022 |
| Lenovo        | ThinkPad T440s 20ARS0CN1... | [2f9eaf5711](https://linux-hardware.org/?probe=2f9eaf5711) | Sep 16, 2022 |
| Acer          | Aspire A515-51              | [59811273b4](https://linux-hardware.org/?probe=59811273b4) | Sep 16, 2022 |
| Sony          | VPCF23EFX                   | [a1b5a72e1c](https://linux-hardware.org/?probe=a1b5a72e1c) | Sep 16, 2022 |
| System76      | Galago Pro                  | [8d6c6b18fd](https://linux-hardware.org/?probe=8d6c6b18fd) | Sep 16, 2022 |
| HP            | ProBook 4340s               | [acca12f9d4](https://linux-hardware.org/?probe=acca12f9d4) | Sep 16, 2022 |
| Unknown       | Unknown                     | [d391ace7f8](https://linux-hardware.org/?probe=d391ace7f8) | Sep 16, 2022 |
| HP            | ENVY Laptop 13-ba0xxx       | [016a874005](https://linux-hardware.org/?probe=016a874005) | Sep 16, 2022 |
| Dell          | Latitude E6520              | [df5bdafb78](https://linux-hardware.org/?probe=df5bdafb78) | Sep 15, 2022 |
| Getac         | S410G2                      | [01ef66363e](https://linux-hardware.org/?probe=01ef66363e) | Sep 15, 2022 |
| Acer          | Aspire A515-51G             | [bc275a0476](https://linux-hardware.org/?probe=bc275a0476) | Sep 15, 2022 |
| Getac         | S410G2                      | [14c74d0b7e](https://linux-hardware.org/?probe=14c74d0b7e) | Sep 15, 2022 |
| HP            | Laptop 15s-fq1xxx           | [be467d8dfe](https://linux-hardware.org/?probe=be467d8dfe) | Sep 15, 2022 |
| HP            | Pavilion dv6                | [9c9c531c6b](https://linux-hardware.org/?probe=9c9c531c6b) | Sep 15, 2022 |
| ASUSTek       | 1005PE                      | [683c42315f](https://linux-hardware.org/?probe=683c42315f) | Sep 15, 2022 |
| ASUSTek       | VivoBook E14 E402WAS        | [84dee7df6c](https://linux-hardware.org/?probe=84dee7df6c) | Sep 15, 2022 |
| Chuwi         | CoreBook X                  | [e59a625390](https://linux-hardware.org/?probe=e59a625390) | Sep 15, 2022 |
| Dell          | Latitude 7480               | [a9432965f4](https://linux-hardware.org/?probe=a9432965f4) | Sep 15, 2022 |
| Acer          | Nitro AN517-55              | [a05e721ec9](https://linux-hardware.org/?probe=a05e721ec9) | Sep 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [a49e02ebe7](https://linux-hardware.org/?probe=a49e02ebe7) | Sep 15, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [8574413795](https://linux-hardware.org/?probe=8574413795) | Sep 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [000eb38ea7](https://linux-hardware.org/?probe=000eb38ea7) | Sep 15, 2022 |
| HP            | OMEN by Laptop              | [282afe0352](https://linux-hardware.org/?probe=282afe0352) | Sep 15, 2022 |
| Medion        | E6234                       | [2ea41cb7ed](https://linux-hardware.org/?probe=2ea41cb7ed) | Sep 15, 2022 |
| HP            | Laptop 14s-dr2xxx           | [39163aba8a](https://linux-hardware.org/?probe=39163aba8a) | Sep 15, 2022 |
| HP            | EliteBook 850 G3            | [f1e4aef2f2](https://linux-hardware.org/?probe=f1e4aef2f2) | Sep 15, 2022 |
| HP            | EliteBook 1040 G4           | [9b4136a781](https://linux-hardware.org/?probe=9b4136a781) | Sep 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0737d49df2](https://linux-hardware.org/?probe=0737d49df2) | Sep 15, 2022 |
| Toshiba       | Satellite P50-B-11L         | [eba4212008](https://linux-hardware.org/?probe=eba4212008) | Sep 15, 2022 |
| HP            | Pavilion Notebook           | [578cb93789](https://linux-hardware.org/?probe=578cb93789) | Sep 14, 2022 |
| Apple         | MacBook9,1                  | [ee115a214b](https://linux-hardware.org/?probe=ee115a214b) | Sep 14, 2022 |
| ASUSTek       | X200CA                      | [6e71dffc7b](https://linux-hardware.org/?probe=6e71dffc7b) | Sep 14, 2022 |
| Dell          | Vostro 14-3468              | [fbe4062b6e](https://linux-hardware.org/?probe=fbe4062b6e) | Sep 14, 2022 |
| Exo           | Smart XL4                   | [96f159b86f](https://linux-hardware.org/?probe=96f159b86f) | Sep 14, 2022 |
| Google        | Snappy                      | [e428dec368](https://linux-hardware.org/?probe=e428dec368) | Sep 14, 2022 |
| Dell          | Inspiron 15 3520            | [1d74f86789](https://linux-hardware.org/?probe=1d74f86789) | Sep 14, 2022 |
| Dell          | Inspiron N5050              | [db02122f3d](https://linux-hardware.org/?probe=db02122f3d) | Sep 14, 2022 |
| HP            | EliteBook 840 G2            | [ca96e9bf9b](https://linux-hardware.org/?probe=ca96e9bf9b) | Sep 14, 2022 |
| Dell          | Latitude E6400              | [0c6b0c35e6](https://linux-hardware.org/?probe=0c6b0c35e6) | Sep 14, 2022 |
| Dell          | Latitude E6400              | [b4c9fcf4c3](https://linux-hardware.org/?probe=b4c9fcf4c3) | Sep 14, 2022 |
| BESSTAR Te... | T3 MRD                      | [0b03396c93](https://linux-hardware.org/?probe=0b03396c93) | Sep 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [81d620ed2f](https://linux-hardware.org/?probe=81d620ed2f) | Sep 14, 2022 |
| HP            | Laptop 15-db0xxx            | [3e082463a9](https://linux-hardware.org/?probe=3e082463a9) | Sep 14, 2022 |
| Dell          | Latitude 7300               | [9802315270](https://linux-hardware.org/?probe=9802315270) | Sep 14, 2022 |
| Lanix         | AL V9                       | [03e7c7ece5](https://linux-hardware.org/?probe=03e7c7ece5) | Sep 14, 2022 |
| Apple         | MacBook9,1                  | [4748d72784](https://linux-hardware.org/?probe=4748d72784) | Sep 14, 2022 |
| Dell          | Latitude 7300               | [5d82c4da95](https://linux-hardware.org/?probe=5d82c4da95) | Sep 14, 2022 |
| Dell          | Inspiron 5593               | [f7b7c249be](https://linux-hardware.org/?probe=f7b7c249be) | Sep 14, 2022 |
| Chuwi         | GemiBook Pro                | [5b62dddb37](https://linux-hardware.org/?probe=5b62dddb37) | Sep 13, 2022 |
| HP            | Pavilion 17                 | [5d9be9b086](https://linux-hardware.org/?probe=5d9be9b086) | Sep 13, 2022 |
| Dell          | Latitude E5550              | [90674e3069](https://linux-hardware.org/?probe=90674e3069) | Sep 13, 2022 |
| ASUSTek       | X750JB                      | [dd6137189b](https://linux-hardware.org/?probe=dd6137189b) | Sep 13, 2022 |
| Dell          | Precision 5550              | [82eebd67fd](https://linux-hardware.org/?probe=82eebd67fd) | Sep 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [423008d102](https://linux-hardware.org/?probe=423008d102) | Sep 13, 2022 |
| Dell          | Inspiron N5050              | [c0f9d7bf4a](https://linux-hardware.org/?probe=c0f9d7bf4a) | Sep 13, 2022 |
| Sony          | SVE15127CAW                 | [3f21f2c6af](https://linux-hardware.org/?probe=3f21f2c6af) | Sep 13, 2022 |
| Dell          | Latitude 7420               | [84f0ebcfea](https://linux-hardware.org/?probe=84f0ebcfea) | Sep 13, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [c07c5b31f6](https://linux-hardware.org/?probe=c07c5b31f6) | Sep 13, 2022 |
| HUAWEI        | HVY-WXX9                    | [999cbe4e8f](https://linux-hardware.org/?probe=999cbe4e8f) | Sep 13, 2022 |
| HP            | Laptop 15-db0xxx            | [5240fca99f](https://linux-hardware.org/?probe=5240fca99f) | Sep 13, 2022 |
| MSI           | Prestige 14 A11SCX          | [0c0264943f](https://linux-hardware.org/?probe=0c0264943f) | Sep 13, 2022 |
| Dell          | XPS 15 9510                 | [44be9b9134](https://linux-hardware.org/?probe=44be9b9134) | Sep 13, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b6b3f2dce1](https://linux-hardware.org/?probe=b6b3f2dce1) | Sep 13, 2022 |
| ASUSTek       | X200LA                      | [e0947fe5c7](https://linux-hardware.org/?probe=e0947fe5c7) | Sep 13, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [3e5c80e004](https://linux-hardware.org/?probe=3e5c80e004) | Sep 13, 2022 |
| Acer          | Aspire ES1-311              | [ee2f9a766c](https://linux-hardware.org/?probe=ee2f9a766c) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [0e6413e94b](https://linux-hardware.org/?probe=0e6413e94b) | Sep 13, 2022 |
| Toshiba       | Satellite A500              | [0d96df6375](https://linux-hardware.org/?probe=0d96df6375) | Sep 13, 2022 |
| Acer          | Aspire 7741                 | [a1375d3bb4](https://linux-hardware.org/?probe=a1375d3bb4) | Sep 13, 2022 |
| Dell          | Latitude 7420               | [211c7ab44c](https://linux-hardware.org/?probe=211c7ab44c) | Sep 12, 2022 |
| Alienware     | M14xR1                      | [a4064c0342](https://linux-hardware.org/?probe=a4064c0342) | Sep 12, 2022 |
| Alienware     | M14xR1                      | [b8a40ec999](https://linux-hardware.org/?probe=b8a40ec999) | Sep 12, 2022 |
| Dell          | Inspiron 15-3567            | [f062dd3ff8](https://linux-hardware.org/?probe=f062dd3ff8) | Sep 12, 2022 |
| Dell          | Vostro 7620                 | [dc7d444958](https://linux-hardware.org/?probe=dc7d444958) | Sep 12, 2022 |
| Dell          | XPS 9315                    | [77ecec9e58](https://linux-hardware.org/?probe=77ecec9e58) | Sep 12, 2022 |
| HP            | 470 G7 Notebook PC          | [f1c4e72e54](https://linux-hardware.org/?probe=f1c4e72e54) | Sep 12, 2022 |
| Dell          | XPS 9315                    | [cfaae58ffa](https://linux-hardware.org/?probe=cfaae58ffa) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | [3162a68bf5](https://linux-hardware.org/?probe=3162a68bf5) | Sep 12, 2022 |
| HP            | Laptop 15-bw0xx             | [644ad9d55f](https://linux-hardware.org/?probe=644ad9d55f) | Sep 12, 2022 |
| System76      | Darter Pro                  | [d93179bdb4](https://linux-hardware.org/?probe=d93179bdb4) | Sep 12, 2022 |
| HP            | Compaq Presario CQ40        | [d764e72d74](https://linux-hardware.org/?probe=d764e72d74) | Sep 12, 2022 |
| ASUSTek       | UX32VD                      | [6a6e7e4207](https://linux-hardware.org/?probe=6a6e7e4207) | Sep 12, 2022 |
| Acer          | Aspire E5-575G              | [d5a0bdc1a9](https://linux-hardware.org/?probe=d5a0bdc1a9) | Sep 12, 2022 |
| Chuwi         | HeroBook Air                | [f944581a0f](https://linux-hardware.org/?probe=f944581a0f) | Sep 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [efc31007ac](https://linux-hardware.org/?probe=efc31007ac) | Sep 12, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [326ab7b00a](https://linux-hardware.org/?probe=326ab7b00a) | Sep 12, 2022 |
| Dell          | XPS 17 9710                 | [4b728bc447](https://linux-hardware.org/?probe=4b728bc447) | Sep 12, 2022 |
| Avell High... | B.ON                        | [f30bca74ab](https://linux-hardware.org/?probe=f30bca74ab) | Sep 12, 2022 |
| Acer          | Aspire A515-55              | [5a114e6867](https://linux-hardware.org/?probe=5a114e6867) | Sep 12, 2022 |
| Apple         | MacBook5,1                  | [be66df4eb9](https://linux-hardware.org/?probe=be66df4eb9) | Sep 12, 2022 |
| ASUSTek       | X553MA                      | [32c5b56788](https://linux-hardware.org/?probe=32c5b56788) | Sep 11, 2022 |
| HP            | ProBook 645 G3              | [0bd9070bee](https://linux-hardware.org/?probe=0bd9070bee) | Sep 11, 2022 |
| Chuwi         | CoreBook X                  | [4f29128588](https://linux-hardware.org/?probe=4f29128588) | Sep 11, 2022 |
| HP            | Presario CQ56               | [ccc7d97678](https://linux-hardware.org/?probe=ccc7d97678) | Sep 11, 2022 |
| Acer          | Aspire V3-771               | [044ee57b31](https://linux-hardware.org/?probe=044ee57b31) | Sep 11, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [d85e0f5222](https://linux-hardware.org/?probe=d85e0f5222) | Sep 11, 2022 |
| HP            | 245 G6                      | [9abb7c255d](https://linux-hardware.org/?probe=9abb7c255d) | Sep 11, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [f8be9f1680](https://linux-hardware.org/?probe=f8be9f1680) | Sep 11, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | [2933ca56f3](https://linux-hardware.org/?probe=2933ca56f3) | Sep 11, 2022 |
| HP            | Laptop 17-bs0xx             | [512a6bd927](https://linux-hardware.org/?probe=512a6bd927) | Sep 11, 2022 |
| Dell          | Latitude E6500              | [b80cc8553b](https://linux-hardware.org/?probe=b80cc8553b) | Sep 11, 2022 |
| Toshiba       | IS 1413G                    | [fab48b6c15](https://linux-hardware.org/?probe=fab48b6c15) | Sep 10, 2022 |
| Acer          | Aspire ES1-411              | [6bbebcbcb1](https://linux-hardware.org/?probe=6bbebcbcb1) | Sep 10, 2022 |
| Chuwi         | UBook XPro                  | [b695b65d86](https://linux-hardware.org/?probe=b695b65d86) | Sep 10, 2022 |
| Dell          | Latitude E7240              | [2976e9106e](https://linux-hardware.org/?probe=2976e9106e) | Sep 10, 2022 |
| Lenovo        | ThinkPad L380 20M6S48000    | [74102b95cb](https://linux-hardware.org/?probe=74102b95cb) | Sep 10, 2022 |
| Acer          | Nitro AN517-55              | [5cd8a55e0f](https://linux-hardware.org/?probe=5cd8a55e0f) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | [e72b842ab6](https://linux-hardware.org/?probe=e72b842ab6) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ab939db2c0](https://linux-hardware.org/?probe=ab939db2c0) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | [f9604390e8](https://linux-hardware.org/?probe=f9604390e8) | Sep 10, 2022 |
| HP            | Unknown                     | [5cf262a728](https://linux-hardware.org/?probe=5cf262a728) | Sep 10, 2022 |
| Packard Be... | EasyNote MH36               | [32025f0e69](https://linux-hardware.org/?probe=32025f0e69) | Sep 10, 2022 |
| Acer          | Nitro AN517-55              | [16fa00177a](https://linux-hardware.org/?probe=16fa00177a) | Sep 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [c8ffb4c23b](https://linux-hardware.org/?probe=c8ffb4c23b) | Sep 10, 2022 |
| Alienware     | M14xR1                      | [ea2adf914b](https://linux-hardware.org/?probe=ea2adf914b) | Sep 10, 2022 |
| Dell          | Latitude 5520               | [909fc06073](https://linux-hardware.org/?probe=909fc06073) | Sep 10, 2022 |
| Dell          | Inspiron 5515               | [e0a7bbacb9](https://linux-hardware.org/?probe=e0a7bbacb9) | Sep 10, 2022 |
| Acer          | Aspire A314-22G             | [b6f9c0a0e7](https://linux-hardware.org/?probe=b6f9c0a0e7) | Sep 10, 2022 |
| Acer          | Aspire V3-472P              | [632117c524](https://linux-hardware.org/?probe=632117c524) | Sep 10, 2022 |
| Toshiba       | Satellite C55-C             | [c9b78bb640](https://linux-hardware.org/?probe=c9b78bb640) | Sep 10, 2022 |
| Toshiba       | Satellite C70D-A            | [41e71a8271](https://linux-hardware.org/?probe=41e71a8271) | Sep 09, 2022 |
| HP            | ProBook 640 G1              | [e6c0d3de61](https://linux-hardware.org/?probe=e6c0d3de61) | Sep 09, 2022 |
| Gateway       | NE56R                       | [c928861fb0](https://linux-hardware.org/?probe=c928861fb0) | Sep 09, 2022 |
| Dell          | Latitude 5531               | [66eac260ef](https://linux-hardware.org/?probe=66eac260ef) | Sep 09, 2022 |
| Avell High... | A70 MOB                     | [1cc84e9a0d](https://linux-hardware.org/?probe=1cc84e9a0d) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [498a2244e4](https://linux-hardware.org/?probe=498a2244e4) | Sep 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d946b5e886](https://linux-hardware.org/?probe=d946b5e886) | Sep 09, 2022 |
| Dell          | Latitude 7490               | [189b1d9ab2](https://linux-hardware.org/?probe=189b1d9ab2) | Sep 09, 2022 |
| Fujitsu       | LIFEBOOK S760               | [d805aa67b2](https://linux-hardware.org/?probe=d805aa67b2) | Sep 09, 2022 |
| Dell          | Latitude E6230              | [30d4c452fe](https://linux-hardware.org/?probe=30d4c452fe) | Sep 09, 2022 |
| HP            | ProBook 450 G6              | [be18103b06](https://linux-hardware.org/?probe=be18103b06) | Sep 09, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [e42f779622](https://linux-hardware.org/?probe=e42f779622) | Sep 09, 2022 |
| Acer          | Aspire 5715Z                | [614ae0addd](https://linux-hardware.org/?probe=614ae0addd) | Sep 09, 2022 |
| Lenovo        | ThinkPad T470 20HES3370A    | [5beda28487](https://linux-hardware.org/?probe=5beda28487) | Sep 09, 2022 |
| Acer          | Aspire A315-58              | [5af4c5d3e1](https://linux-hardware.org/?probe=5af4c5d3e1) | Sep 09, 2022 |
| HP            | ProBook 445 G7              | [0bff612c28](https://linux-hardware.org/?probe=0bff612c28) | Sep 09, 2022 |
| Gateway       | NE56R                       | [3167a59b9b](https://linux-hardware.org/?probe=3167a59b9b) | Sep 09, 2022 |
| ASUSTek       | X555LAB                     | [7d108d27ee](https://linux-hardware.org/?probe=7d108d27ee) | Sep 09, 2022 |
| HP            | ProBook 4540s               | [9769570360](https://linux-hardware.org/?probe=9769570360) | Sep 08, 2022 |
| HP            | ProBook 4540s               | [b99a74ee67](https://linux-hardware.org/?probe=b99a74ee67) | Sep 08, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [10829f6091](https://linux-hardware.org/?probe=10829f6091) | Sep 08, 2022 |
| Dell          | XPS 15 7590                 | [57cbaefc6e](https://linux-hardware.org/?probe=57cbaefc6e) | Sep 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [4562797ebc](https://linux-hardware.org/?probe=4562797ebc) | Sep 08, 2022 |
| Acer          | Aspire 5736Z                | [820b817bff](https://linux-hardware.org/?probe=820b817bff) | Sep 08, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | [c803fe67f3](https://linux-hardware.org/?probe=c803fe67f3) | Sep 08, 2022 |
| HP            | ZBook 15                    | [89a1ed226b](https://linux-hardware.org/?probe=89a1ed226b) | Sep 08, 2022 |
| Acer          | Aspire 5920G                | [7dd567a644](https://linux-hardware.org/?probe=7dd567a644) | Sep 08, 2022 |
| SKIKK         | Standard                    | [3d7a0b8762](https://linux-hardware.org/?probe=3d7a0b8762) | Sep 08, 2022 |
| Notebook      | N350DW                      | [673f2961a0](https://linux-hardware.org/?probe=673f2961a0) | Sep 08, 2022 |
| Dell          | Inspiron 5537               | [871de5472c](https://linux-hardware.org/?probe=871de5472c) | Sep 08, 2022 |
| Dell          | Inspiron 5537               | [fad1689295](https://linux-hardware.org/?probe=fad1689295) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6812b52b92](https://linux-hardware.org/?probe=6812b52b92) | Sep 08, 2022 |
| ASUSTek       | X553MA                      | [32edc5cfad](https://linux-hardware.org/?probe=32edc5cfad) | Sep 08, 2022 |
| Dell          | Inspiron 3541               | [2cc868e8f0](https://linux-hardware.org/?probe=2cc868e8f0) | Sep 08, 2022 |
| HP            | 255 G7 Notebook PC          | [f826db042c](https://linux-hardware.org/?probe=f826db042c) | Sep 08, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [7cf6479781](https://linux-hardware.org/?probe=7cf6479781) | Sep 08, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [6ee5358914](https://linux-hardware.org/?probe=6ee5358914) | Sep 08, 2022 |
| MSI           | GS65 Stealth 9SF            | [b7c0e9f507](https://linux-hardware.org/?probe=b7c0e9f507) | Sep 07, 2022 |
| MSI           | GS65 Stealth 9SF            | [d86e74ff07](https://linux-hardware.org/?probe=d86e74ff07) | Sep 07, 2022 |
| HP            | 15 Notebook PC              | [c67ce341c3](https://linux-hardware.org/?probe=c67ce341c3) | Sep 07, 2022 |
| HP            | 15 Notebook PC              | [bf046aa33d](https://linux-hardware.org/?probe=bf046aa33d) | Sep 07, 2022 |
| Acer          | Aspire 5920G                | [713102f9c1](https://linux-hardware.org/?probe=713102f9c1) | Sep 07, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | [4d677cc03a](https://linux-hardware.org/?probe=4d677cc03a) | Sep 07, 2022 |
| Dell          | Vostro 7620                 | [9f745ee182](https://linux-hardware.org/?probe=9f745ee182) | Sep 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HR... | [63524aa492](https://linux-hardware.org/?probe=63524aa492) | Sep 07, 2022 |
| HP            | Laptop 15-dw0xxx            | [90908282f2](https://linux-hardware.org/?probe=90908282f2) | Sep 07, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [72ba31c33a](https://linux-hardware.org/?probe=72ba31c33a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [308047a7cb](https://linux-hardware.org/?probe=308047a7cb) | Sep 07, 2022 |
| HP            | ProBook 430 G6              | [99de13d37c](https://linux-hardware.org/?probe=99de13d37c) | Sep 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c98348c9a3](https://linux-hardware.org/?probe=c98348c9a3) | Sep 07, 2022 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [65d158746d](https://linux-hardware.org/?probe=65d158746d) | Sep 07, 2022 |
| HP            | 255 G7 Notebook PC          | [818e44087d](https://linux-hardware.org/?probe=818e44087d) | Sep 07, 2022 |
| Toshiba       | Satellite L635              | [6d0bbfb576](https://linux-hardware.org/?probe=6d0bbfb576) | Sep 07, 2022 |
| Positivo      | Smash                       | [0051f458c6](https://linux-hardware.org/?probe=0051f458c6) | Sep 07, 2022 |
| Toshiba       | Satellite NB10t-A-101       | [b824e1e3d5](https://linux-hardware.org/?probe=b824e1e3d5) | Sep 06, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [7479eb6186](https://linux-hardware.org/?probe=7479eb6186) | Sep 06, 2022 |
| HP            | Laptop 15-dy1xxx            | [b5aa9dbddc](https://linux-hardware.org/?probe=b5aa9dbddc) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | [b12a6d2146](https://linux-hardware.org/?probe=b12a6d2146) | Sep 06, 2022 |
| Dell          | Latitude 3340               | [ec720c63b1](https://linux-hardware.org/?probe=ec720c63b1) | Sep 06, 2022 |
| Lenovo        | V145-15AST 81MT             | [90d59bf651](https://linux-hardware.org/?probe=90d59bf651) | Sep 06, 2022 |
| Dell          | Inspiron N5010              | [48a1236943](https://linux-hardware.org/?probe=48a1236943) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4615004e85](https://linux-hardware.org/?probe=4615004e85) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [d20b550fd6](https://linux-hardware.org/?probe=d20b550fd6) | Sep 06, 2022 |
| HP            | EliteBook 840 G1            | [1796a51c0c](https://linux-hardware.org/?probe=1796a51c0c) | Sep 06, 2022 |
| Dell          | Inspiron 3543               | [60a94af2ef](https://linux-hardware.org/?probe=60a94af2ef) | Sep 06, 2022 |
| Dell          | XPS 15 9500                 | [0d66bc1b42](https://linux-hardware.org/?probe=0d66bc1b42) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [b8200b36d4](https://linux-hardware.org/?probe=b8200b36d4) | Sep 06, 2022 |
| Toshiba       | Satellite L875D             | [3967661ea3](https://linux-hardware.org/?probe=3967661ea3) | Sep 06, 2022 |
| Acer          | Nitro AN517-55              | [a9da4ec109](https://linux-hardware.org/?probe=a9da4ec109) | Sep 06, 2022 |
| Dell          | Precision M4700             | [1762d6d7b8](https://linux-hardware.org/?probe=1762d6d7b8) | Sep 05, 2022 |
| HP            | Pavilion g6                 | [770b1a8154](https://linux-hardware.org/?probe=770b1a8154) | Sep 05, 2022 |
| Dell          | Latitude E6540              | [cdc8e8c4b1](https://linux-hardware.org/?probe=cdc8e8c4b1) | Sep 05, 2022 |
| Acer          | Swift SF314-43              | [57235f1260](https://linux-hardware.org/?probe=57235f1260) | Sep 05, 2022 |
| Acer          | Swift SF314-43              | [7d505ec2d3](https://linux-hardware.org/?probe=7d505ec2d3) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [3c578ac6c8](https://linux-hardware.org/?probe=3c578ac6c8) | Sep 05, 2022 |
| Lenovo        | ThinkPad X201 Tablet 298... | [cfaa6480e5](https://linux-hardware.org/?probe=cfaa6480e5) | Sep 05, 2022 |
| Toshiba       | Satellite C50-B             | [00e103f0a0](https://linux-hardware.org/?probe=00e103f0a0) | Sep 05, 2022 |
| Dell          | Latitude 5531               | [dff44a5e24](https://linux-hardware.org/?probe=dff44a5e24) | Sep 05, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [c34e343671](https://linux-hardware.org/?probe=c34e343671) | Sep 05, 2022 |
| Alienware     | m15 R7                      | [c9d5bcb40f](https://linux-hardware.org/?probe=c9d5bcb40f) | Sep 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | [92b56566ae](https://linux-hardware.org/?probe=92b56566ae) | Sep 05, 2022 |
| HP            | Laptop 15s-eq2xxx           | [11eddd9f6d](https://linux-hardware.org/?probe=11eddd9f6d) | Sep 05, 2022 |
| TrekStor      | Notebook Slim S130          | [abd3c1ccf8](https://linux-hardware.org/?probe=abd3c1ccf8) | Sep 05, 2022 |
| HUAWEI        | KLVL-WXXW                   | [093ecc4108](https://linux-hardware.org/?probe=093ecc4108) | Sep 05, 2022 |
| Dell          | Inspiron N4050              | [343b6df180](https://linux-hardware.org/?probe=343b6df180) | Sep 05, 2022 |
| Toshiba       | Satellite Pro L450          | [8cc36d7338](https://linux-hardware.org/?probe=8cc36d7338) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | [99be9d8928](https://linux-hardware.org/?probe=99be9d8928) | Sep 05, 2022 |
| Lenovo        | ThinkPad T470 20HES3370A    | [3a466cef0a](https://linux-hardware.org/?probe=3a466cef0a) | Sep 05, 2022 |
| HP            | Pavilion dv6500             | [c37bace401](https://linux-hardware.org/?probe=c37bace401) | Sep 05, 2022 |
| Toshiba       | Satellite C50-B             | [a7708366c2](https://linux-hardware.org/?probe=a7708366c2) | Sep 05, 2022 |
| Dell          | Inspiron 15 3525            | [0ec2aca595](https://linux-hardware.org/?probe=0ec2aca595) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [ce623f1d8d](https://linux-hardware.org/?probe=ce623f1d8d) | Sep 04, 2022 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d802875fec](https://linux-hardware.org/?probe=d802875fec) | Sep 04, 2022 |
| HP            | EliteBook 8440p             | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| Dell          | Inspiron 15-3573            | [47b54fb058](https://linux-hardware.org/?probe=47b54fb058) | Sep 04, 2022 |
| ASUSTek       | X302LA                      | [bc5ccb7df4](https://linux-hardware.org/?probe=bc5ccb7df4) | Sep 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [68b6da5fe1](https://linux-hardware.org/?probe=68b6da5fe1) | Sep 04, 2022 |
| HP            | ProBook 455 G5              | [c8e73af546](https://linux-hardware.org/?probe=c8e73af546) | Sep 04, 2022 |
| HP            | Pavilion 15                 | [ed8a48954e](https://linux-hardware.org/?probe=ed8a48954e) | Sep 04, 2022 |
| Packard Be... | EasyNote LJ65               | [cd0ee92e1c](https://linux-hardware.org/?probe=cd0ee92e1c) | Sep 04, 2022 |
| Dell          | Latitude E7250              | [2af321a880](https://linux-hardware.org/?probe=2af321a880) | Sep 04, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [ecaa040ba1](https://linux-hardware.org/?probe=ecaa040ba1) | Sep 04, 2022 |
| Acer          | TravelMate P253             | [828da93c00](https://linux-hardware.org/?probe=828da93c00) | Sep 04, 2022 |
| Lenovo        | IdeaPad 730S-13IWL 81JB     | [6503b9f3ba](https://linux-hardware.org/?probe=6503b9f3ba) | Sep 04, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [920bfdae34](https://linux-hardware.org/?probe=920bfdae34) | Sep 04, 2022 |
| Timi          | TM1701                      | [e766bf8915](https://linux-hardware.org/?probe=e766bf8915) | Sep 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TAC... | [6bfcf13e01](https://linux-hardware.org/?probe=6bfcf13e01) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Aspire V3-571G              | [3f17eeffec](https://linux-hardware.org/?probe=3f17eeffec) | Sep 03, 2022 |
| Dell          | Latitude 7300               | [30994e1857](https://linux-hardware.org/?probe=30994e1857) | Sep 03, 2022 |
| Dell          | Inspiron 5558               | [5b344b7d80](https://linux-hardware.org/?probe=5b344b7d80) | Sep 03, 2022 |
| Timi          | TM1701                      | [740d59830a](https://linux-hardware.org/?probe=740d59830a) | Sep 03, 2022 |
| Acer          | Swift SF314-52              | [dfcde87ea3](https://linux-hardware.org/?probe=dfcde87ea3) | Sep 03, 2022 |
| Acer          | Aspire E5-553               | [de2cfb43d7](https://linux-hardware.org/?probe=de2cfb43d7) | Sep 03, 2022 |
| Toshiba       | Satellite C70D-A            | [32fa823faa](https://linux-hardware.org/?probe=32fa823faa) | Sep 03, 2022 |
| Apple         | MacBookPro9,2               | [c78ad07fa6](https://linux-hardware.org/?probe=c78ad07fa6) | Sep 03, 2022 |
| HP            | ProBook 455 G5              | [bb8be69e14](https://linux-hardware.org/?probe=bb8be69e14) | Sep 03, 2022 |
| Schenker      | XMG NEO (CZN/E21)           | [0b6cccf796](https://linux-hardware.org/?probe=0b6cccf796) | Sep 03, 2022 |
| BESSTAR Te... | X400                        | [8eb69c0ad6](https://linux-hardware.org/?probe=8eb69c0ad6) | Sep 03, 2022 |
| Acer          | Aspire 5750G                | [a881cc280a](https://linux-hardware.org/?probe=a881cc280a) | Sep 03, 2022 |
| Dell          | XPS 13 9350                 | [eb732461f4](https://linux-hardware.org/?probe=eb732461f4) | Sep 03, 2022 |
| Dell          | Precision M6800             | [67d98f2139](https://linux-hardware.org/?probe=67d98f2139) | Sep 03, 2022 |
| Dell          | XPS 13 9350                 | [72ae2ba843](https://linux-hardware.org/?probe=72ae2ba843) | Sep 03, 2022 |
| HP            | Laptop 15s-eq0xxx           | [85e96b2d25](https://linux-hardware.org/?probe=85e96b2d25) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [6a91fe77a0](https://linux-hardware.org/?probe=6a91fe77a0) | Sep 03, 2022 |
| HP            | ProBook 6460b               | [6dead72b3a](https://linux-hardware.org/?probe=6dead72b3a) | Sep 03, 2022 |
| Dell          | Latitude E6420              | [98a628a92a](https://linux-hardware.org/?probe=98a628a92a) | Sep 03, 2022 |
| Dell          | Latitude E6420              | [e9c43bd2ab](https://linux-hardware.org/?probe=e9c43bd2ab) | Sep 03, 2022 |
| Dell          | G15 5510                    | [fbcdd4d274](https://linux-hardware.org/?probe=fbcdd4d274) | Sep 03, 2022 |
| Dell          | Latitude E7450              | [de66677d3d](https://linux-hardware.org/?probe=de66677d3d) | Sep 03, 2022 |
| Dell          | Inspiron 5558               | [2d4eeaf028](https://linux-hardware.org/?probe=2d4eeaf028) | Sep 03, 2022 |
| Acer          | Aspire E1-531               | [601c1eea92](https://linux-hardware.org/?probe=601c1eea92) | Sep 03, 2022 |
| Dell          | Latitude E6540              | [76dd708578](https://linux-hardware.org/?probe=76dd708578) | Sep 03, 2022 |
| Lenovo        | ThinkPad P52 20MAS07F04     | [fe662b0bd6](https://linux-hardware.org/?probe=fe662b0bd6) | Sep 03, 2022 |
| Dell          | Latitude E6540              | [223af58b88](https://linux-hardware.org/?probe=223af58b88) | Sep 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4c07e27fb2](https://linux-hardware.org/?probe=4c07e27fb2) | Sep 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6669ffa68e](https://linux-hardware.org/?probe=6669ffa68e) | Sep 02, 2022 |
| Dell          | Latitude E6220              | [e249853663](https://linux-hardware.org/?probe=e249853663) | Sep 02, 2022 |
| HP            | Laptop 15s-eq0xxx           | [da3adfc2ce](https://linux-hardware.org/?probe=da3adfc2ce) | Sep 02, 2022 |
| Unknown       | Unknown                     | [44c4961820](https://linux-hardware.org/?probe=44c4961820) | Sep 02, 2022 |
| Acer          | Aspire V3-772               | [bc1bcb3b13](https://linux-hardware.org/?probe=bc1bcb3b13) | Sep 02, 2022 |
| Lenovo        | ThinkPad T410 2518F5U       | [9b61c2fbcc](https://linux-hardware.org/?probe=9b61c2fbcc) | Sep 02, 2022 |
| Dell          | Inspiron 5559               | [7da5af06fb](https://linux-hardware.org/?probe=7da5af06fb) | Sep 02, 2022 |
| Lenovo        | ThinkPad T470 20HES3370A    | [ae1d14117b](https://linux-hardware.org/?probe=ae1d14117b) | Sep 02, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [319d526423](https://linux-hardware.org/?probe=319d526423) | Sep 02, 2022 |
| MSI           | Creator Z17 A12UHST         | [3071865e76](https://linux-hardware.org/?probe=3071865e76) | Sep 02, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [60b4add0a0](https://linux-hardware.org/?probe=60b4add0a0) | Sep 02, 2022 |
| Lenovo        | ThinkPad P53 MWS 15.6 (Q... | [dad5b2c8b8](https://linux-hardware.org/?probe=dad5b2c8b8) | Sep 02, 2022 |
| Dell          | Latitude E6220              | [99c8b865ad](https://linux-hardware.org/?probe=99c8b865ad) | Sep 02, 2022 |
| Lenovo        | ThinkPad T410 2518F5U       | [95e8dcce67](https://linux-hardware.org/?probe=95e8dcce67) | Sep 02, 2022 |
| HP            | Compaq Presario CQ60        | [a2c489f43b](https://linux-hardware.org/?probe=a2c489f43b) | Sep 02, 2022 |
| Lenovo        | ThinkPad P53 MWS 15.6 (Q... | [6946f868d5](https://linux-hardware.org/?probe=6946f868d5) | Sep 02, 2022 |
| BESSTAR Te... | X400                        | [2a6969af70](https://linux-hardware.org/?probe=2a6969af70) | Sep 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [12abd434b5](https://linux-hardware.org/?probe=12abd434b5) | Sep 01, 2022 |
| Dell          | Latitude 5521               | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [02ec70b604](https://linux-hardware.org/?probe=02ec70b604) | Sep 01, 2022 |
| Lenovo        | ThinkPad T400 6474W7T       | [f9a9b12b37](https://linux-hardware.org/?probe=f9a9b12b37) | Sep 01, 2022 |
| HP            | Laptop 15-db0xxx            | [de848d928c](https://linux-hardware.org/?probe=de848d928c) | Sep 01, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STC... | [0a5a3fa67e](https://linux-hardware.org/?probe=0a5a3fa67e) | Sep 01, 2022 |
| Casper        | NIRVANA NOTEBOOK            | [7a5978071e](https://linux-hardware.org/?probe=7a5978071e) | Sep 01, 2022 |
| Avell High... | C62 MOB                     | [ab93c1f314](https://linux-hardware.org/?probe=ab93c1f314) | Sep 01, 2022 |
| Notebook      | NL40_50CU                   | [af0da080ec](https://linux-hardware.org/?probe=af0da080ec) | Sep 01, 2022 |
| Dell          | Latitude 3340               | [d64525742a](https://linux-hardware.org/?probe=d64525742a) | Sep 01, 2022 |
| Dell          | Latitude 3340               | [b9d472b965](https://linux-hardware.org/?probe=b9d472b965) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cc30fbdce2](https://linux-hardware.org/?probe=cc30fbdce2) | Sep 01, 2022 |
| LG Electro... | 14Z990-V.AP72B              | [8c67c188a1](https://linux-hardware.org/?probe=8c67c188a1) | Sep 01, 2022 |
| Lenovo        | ThinkPad T400 6474W7T       | [b52974ac00](https://linux-hardware.org/?probe=b52974ac00) | Sep 01, 2022 |
| Dell          | Latitude 5591               | [b860997149](https://linux-hardware.org/?probe=b860997149) | Sep 01, 2022 |
| HP            | ProBook 6460b               | [a0e3db2eed](https://linux-hardware.org/?probe=a0e3db2eed) | Sep 01, 2022 |
| Samsung       | 950XEE                      | [454b67dd88](https://linux-hardware.org/?probe=454b67dd88) | Sep 01, 2022 |
| Acer          | Aspire E5-571               | [7759e41b1d](https://linux-hardware.org/?probe=7759e41b1d) | Sep 01, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [85d4f11486](https://linux-hardware.org/?probe=85d4f11486) | Sep 01, 2022 |
| HP            | EliteBook 840 G2            | [4da3485e34](https://linux-hardware.org/?probe=4da3485e34) | Sep 01, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | [5a4e2225a8](https://linux-hardware.org/?probe=5a4e2225a8) | Sep 01, 2022 |
| HP            | G42                         | [a79b07fcd0](https://linux-hardware.org/?probe=a79b07fcd0) | Sep 01, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [93ff04a07b](https://linux-hardware.org/?probe=93ff04a07b) | Sep 01, 2022 |
| Dell          | Latitude 7390               | [571b195a12](https://linux-hardware.org/?probe=571b195a12) | Aug 31, 2022 |
| Dell          | Latitude 7390               | [3c3f6114f6](https://linux-hardware.org/?probe=3c3f6114f6) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | [42879ce5cf](https://linux-hardware.org/?probe=42879ce5cf) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | [3c7e97b769](https://linux-hardware.org/?probe=3c7e97b769) | Aug 31, 2022 |
| Acer          | Aspire V3-571G              | [8f4a2b603a](https://linux-hardware.org/?probe=8f4a2b603a) | Aug 31, 2022 |
| Toshiba       | Satellite Pro L500          | [7f523718cf](https://linux-hardware.org/?probe=7f523718cf) | Aug 31, 2022 |
| Dell          | Latitude 7280               | [e71e9350b4](https://linux-hardware.org/?probe=e71e9350b4) | Aug 31, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [4808984401](https://linux-hardware.org/?probe=4808984401) | Aug 31, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [eb79e6b28e](https://linux-hardware.org/?probe=eb79e6b28e) | Aug 31, 2022 |
| HUAWEI        | HVY-WXX9                    | [193310218d](https://linux-hardware.org/?probe=193310218d) | Aug 31, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [d36b7bb077](https://linux-hardware.org/?probe=d36b7bb077) | Aug 31, 2022 |
| HUAWEI        | CREF-XX                     | [4ea2674cd8](https://linux-hardware.org/?probe=4ea2674cd8) | Aug 31, 2022 |
| Lenovo        | ThinkPad P43s 20RJS0D100    | [afbf0f6021](https://linux-hardware.org/?probe=afbf0f6021) | Aug 31, 2022 |
| HP            | Presario F500 (GM639LA#A... | [7323caa631](https://linux-hardware.org/?probe=7323caa631) | Aug 31, 2022 |
| Dell          | Vostro 3550                 | [c26bf23cdd](https://linux-hardware.org/?probe=c26bf23cdd) | Aug 31, 2022 |
| Dell          | Inspiron 5502               | [1bb776feab](https://linux-hardware.org/?probe=1bb776feab) | Aug 31, 2022 |
| Lenovo        | V15-IIL 82C5                | [2a9e478284](https://linux-hardware.org/?probe=2a9e478284) | Aug 30, 2022 |
| Lenovo        | ThinkPad Edge E530 62724... | [87cad1c0b0](https://linux-hardware.org/?probe=87cad1c0b0) | Aug 30, 2022 |
| Avell High... | B.ON                        | [dbc18dad43](https://linux-hardware.org/?probe=dbc18dad43) | Aug 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20da9d42a4](https://linux-hardware.org/?probe=20da9d42a4) | Aug 30, 2022 |
| Lenovo        | ThinkPad L512 259756M       | [3990fcfeed](https://linux-hardware.org/?probe=3990fcfeed) | Aug 30, 2022 |
| Dell          | XPS 15 9570                 | [6c35aeda10](https://linux-hardware.org/?probe=6c35aeda10) | Aug 30, 2022 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | [273e5229a4](https://linux-hardware.org/?probe=273e5229a4) | Aug 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [11efd3dbe0](https://linux-hardware.org/?probe=11efd3dbe0) | Aug 30, 2022 |
| HP            | EliteBook 840 G2            | [5ba91d8167](https://linux-hardware.org/?probe=5ba91d8167) | Aug 30, 2022 |
| HP            | EliteBook 840 G1            | [23d73aa95c](https://linux-hardware.org/?probe=23d73aa95c) | Aug 30, 2022 |
| ASUSTek       | GL552JX                     | [d477c2cd47](https://linux-hardware.org/?probe=d477c2cd47) | Aug 30, 2022 |
| HP            | EliteBook 840 G2            | [bed3be5142](https://linux-hardware.org/?probe=bed3be5142) | Aug 30, 2022 |
| HP            | EliteBook 840 G2            | [b588415d06](https://linux-hardware.org/?probe=b588415d06) | Aug 30, 2022 |
| Lenovo        | ThinkPad T470 20HES3370A    | [3b1630e4bc](https://linux-hardware.org/?probe=3b1630e4bc) | Aug 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [6393abc859](https://linux-hardware.org/?probe=6393abc859) | Aug 30, 2022 |
| Dell          | Latitude 5520               | [26434099b3](https://linux-hardware.org/?probe=26434099b3) | Aug 30, 2022 |
| HP            | EliteBook 830 G6            | [897046248f](https://linux-hardware.org/?probe=897046248f) | Aug 30, 2022 |
| Dell          | Inspiron 5502               | [28a1dd084e](https://linux-hardware.org/?probe=28a1dd084e) | Aug 30, 2022 |
| Dell          | Inspiron 5502               | [df0098010e](https://linux-hardware.org/?probe=df0098010e) | Aug 30, 2022 |
| Chuwi         | GemiBook                    | [abca00f582](https://linux-hardware.org/?probe=abca00f582) | Aug 30, 2022 |
| ASUSTek       | K501LX                      | [993e5d9848](https://linux-hardware.org/?probe=993e5d9848) | Aug 29, 2022 |
| Apple         | MacBookPro7,1               | [a879fb8249](https://linux-hardware.org/?probe=a879fb8249) | Aug 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [636a7f710c](https://linux-hardware.org/?probe=636a7f710c) | Aug 29, 2022 |
| Dell          | Latitude E5450              | [9dad9e784f](https://linux-hardware.org/?probe=9dad9e784f) | Aug 29, 2022 |
| Monster       | Huma H5 V3.2                | [ea050f24db](https://linux-hardware.org/?probe=ea050f24db) | Aug 29, 2022 |
| Fujitsu       | LIFEBOOK E746               | [5b0eba15c2](https://linux-hardware.org/?probe=5b0eba15c2) | Aug 29, 2022 |
| Apple         | MacBookPro11,4              | [dc1f806296](https://linux-hardware.org/?probe=dc1f806296) | Aug 29, 2022 |
| HP            | ProBook 440 14 inch G9 N... | [0a08f13779](https://linux-hardware.org/?probe=0a08f13779) | Aug 29, 2022 |
| System76      | Galago Pro                  | [df2c4ae77c](https://linux-hardware.org/?probe=df2c4ae77c) | Aug 29, 2022 |
| ASUSTek       | X553MA                      | [108e0c7803](https://linux-hardware.org/?probe=108e0c7803) | Aug 29, 2022 |
| HP            | ZBook 15u G4                | [39f4830019](https://linux-hardware.org/?probe=39f4830019) | Aug 28, 2022 |
| Lenovo        | G50-45 80E3                 | [239e5612ee](https://linux-hardware.org/?probe=239e5612ee) | Aug 28, 2022 |
| Panasonic     | CF-30KTPAZAE                | [61a8f4a768](https://linux-hardware.org/?probe=61a8f4a768) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [8fac02d016](https://linux-hardware.org/?probe=8fac02d016) | Aug 28, 2022 |
| HP            | ZBook 15u G4                | [2115d02bfd](https://linux-hardware.org/?probe=2115d02bfd) | Aug 28, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | [d281087322](https://linux-hardware.org/?probe=d281087322) | Aug 28, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [c8c04ce5db](https://linux-hardware.org/?probe=c8c04ce5db) | Aug 28, 2022 |
| Dell          | Latitude E7470              | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Dell          | Inspiron 3543               | [68d1385b7e](https://linux-hardware.org/?probe=68d1385b7e) | Aug 28, 2022 |
| Microtech     | CoreBook                    | [7507a104b7](https://linux-hardware.org/?probe=7507a104b7) | Aug 28, 2022 |
| Dell          | Inspiron N5010              | [1a76248bf8](https://linux-hardware.org/?probe=1a76248bf8) | Aug 28, 2022 |
| Alienware     | 15                          | [f85646920a](https://linux-hardware.org/?probe=f85646920a) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [98bb5817f6](https://linux-hardware.org/?probe=98bb5817f6) | Aug 27, 2022 |
| HP            | Pavilion Notebook           | [0e4eab04c0](https://linux-hardware.org/?probe=0e4eab04c0) | Aug 27, 2022 |
| HP            | Pavilion Notebook           | [65e832cb2f](https://linux-hardware.org/?probe=65e832cb2f) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [65f638768e](https://linux-hardware.org/?probe=65f638768e) | Aug 27, 2022 |
| Alienware     | M14xR1                      | [498d5f5254](https://linux-hardware.org/?probe=498d5f5254) | Aug 27, 2022 |
| Acer          | Nitro AN515-57              | [decd7daef2](https://linux-hardware.org/?probe=decd7daef2) | Aug 27, 2022 |
| BESSTAR Te... | X400                        | [ab70086ae7](https://linux-hardware.org/?probe=ab70086ae7) | Aug 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f4d9682f50](https://linux-hardware.org/?probe=f4d9682f50) | Aug 27, 2022 |
| BESSTAR Te... | X400                        | [f8d3611cf0](https://linux-hardware.org/?probe=f8d3611cf0) | Aug 27, 2022 |
| Acer          | Nitro AN515-54              | [975f6a801d](https://linux-hardware.org/?probe=975f6a801d) | Aug 27, 2022 |
| HP            | Unknown                     | [9b22ce41e3](https://linux-hardware.org/?probe=9b22ce41e3) | Aug 27, 2022 |
| Lenovo        | YangTian V340-15-IIL 81X... | [f26ee3814c](https://linux-hardware.org/?probe=f26ee3814c) | Aug 27, 2022 |
| Fujitsu       | LIFEBOOK A530               | [5534f20f99](https://linux-hardware.org/?probe=5534f20f99) | Aug 27, 2022 |
| Fujitsu       | LIFEBOOK A530               | [df9aa3eab2](https://linux-hardware.org/?probe=df9aa3eab2) | Aug 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | [cf1b2ff13c](https://linux-hardware.org/?probe=cf1b2ff13c) | Aug 27, 2022 |
| Positivo      | C14CR01                     | [bb9a4c427a](https://linux-hardware.org/?probe=bb9a4c427a) | Aug 27, 2022 |
| speedmaste... | E131x series                | [69d287c029](https://linux-hardware.org/?probe=69d287c029) | Aug 26, 2022 |
| Dell          | Latitude E6510              | [846791d8b9](https://linux-hardware.org/?probe=846791d8b9) | Aug 26, 2022 |
| Dell          | Vostro 1520                 | [b51f7dfba6](https://linux-hardware.org/?probe=b51f7dfba6) | Aug 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [62ce95ce9c](https://linux-hardware.org/?probe=62ce95ce9c) | Aug 26, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [b24bbedfc1](https://linux-hardware.org/?probe=b24bbedfc1) | Aug 26, 2022 |
| Apple         | MacBookPro9,2               | [49b01e516c](https://linux-hardware.org/?probe=49b01e516c) | Aug 26, 2022 |
| ASUSTek       | S551LB                      | [efd20dadd0](https://linux-hardware.org/?probe=efd20dadd0) | Aug 26, 2022 |
| Acer          | Aspire A315-34              | [d71a1ce240](https://linux-hardware.org/?probe=d71a1ce240) | Aug 26, 2022 |
| Timi          | Redmi Book Pro 14 2022      | [3f61df6540](https://linux-hardware.org/?probe=3f61df6540) | Aug 26, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [83377b24dc](https://linux-hardware.org/?probe=83377b24dc) | Aug 25, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cbae91bec7](https://linux-hardware.org/?probe=cbae91bec7) | Aug 25, 2022 |
| Gateway       | NV53A                       | [618b8506e2](https://linux-hardware.org/?probe=618b8506e2) | Aug 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d2e2d5484c](https://linux-hardware.org/?probe=d2e2d5484c) | Aug 25, 2022 |
| HUAWEI        | BOM-WXX9                    | [06ba6b75b4](https://linux-hardware.org/?probe=06ba6b75b4) | Aug 25, 2022 |
| Lenovo        | ThinkPad L490 20Q5S0LF00    | [3c1287dfd2](https://linux-hardware.org/?probe=3c1287dfd2) | Aug 25, 2022 |
| Dell          | Inspiron N5010              | [f4862a3793](https://linux-hardware.org/?probe=f4862a3793) | Aug 25, 2022 |
| Dell          | Inspiron 5459               | [398f6d4b78](https://linux-hardware.org/?probe=398f6d4b78) | Aug 25, 2022 |
| HP            | ProBook 430 G5              | [6a7db587c7](https://linux-hardware.org/?probe=6a7db587c7) | Aug 25, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [ba23396754](https://linux-hardware.org/?probe=ba23396754) | Aug 25, 2022 |
| Dell          | XPS 15 9560                 | [28323e5398](https://linux-hardware.org/?probe=28323e5398) | Aug 25, 2022 |
| ASUSTek       | P81IJ                       | [7ab324abea](https://linux-hardware.org/?probe=7ab324abea) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HP            | ZBook 15u G4                | [dcdc803214](https://linux-hardware.org/?probe=dcdc803214) | Aug 24, 2022 |
| ASUSTek       | ProArt StudioBook W700G3... | [72f873111c](https://linux-hardware.org/?probe=72f873111c) | Aug 24, 2022 |
| HP            | Pavilion Notebook           | [70ca4aae12](https://linux-hardware.org/?probe=70ca4aae12) | Aug 24, 2022 |
| Linx          | LINX1010B                   | [07194b77d4](https://linux-hardware.org/?probe=07194b77d4) | Aug 24, 2022 |
| Lenovo        | IdeaPad S540-15IML D 81N... | [a0c40a81ec](https://linux-hardware.org/?probe=a0c40a81ec) | Aug 24, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| HP            | 255 G6 Notebook PC          | [a476ba5a83](https://linux-hardware.org/?probe=a476ba5a83) | Aug 24, 2022 |
| Dell          | Inspiron 3543               | [000b034e01](https://linux-hardware.org/?probe=000b034e01) | Aug 24, 2022 |
| Packard Be... | EasyNote LJ65               | [dcd6540e36](https://linux-hardware.org/?probe=dcd6540e36) | Aug 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [421ab76c43](https://linux-hardware.org/?probe=421ab76c43) | Aug 24, 2022 |
| Dell          | Inspiron 5402               | [936ea503c8](https://linux-hardware.org/?probe=936ea503c8) | Aug 24, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c7d603acb8](https://linux-hardware.org/?probe=c7d603acb8) | Aug 24, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [17260bd4fb](https://linux-hardware.org/?probe=17260bd4fb) | Aug 24, 2022 |
| Toshiba       | Satellite C55-B             | [eaabc96ff1](https://linux-hardware.org/?probe=eaabc96ff1) | Aug 24, 2022 |
| Lenovo        | V330-15IKB 81AX             | [c3ddddae2c](https://linux-hardware.org/?probe=c3ddddae2c) | Aug 24, 2022 |
| Apple         | MacBookPro16,2              | [3c6266b13d](https://linux-hardware.org/?probe=3c6266b13d) | Aug 23, 2022 |
| Packard Be... | EasyNote LJ65               | [6493743ace](https://linux-hardware.org/?probe=6493743ace) | Aug 23, 2022 |
| Dell          | Precision M4800             | [dbe7bfeb57](https://linux-hardware.org/?probe=dbe7bfeb57) | Aug 23, 2022 |
| Dell          | Precision M4800             | [b8edb4a562](https://linux-hardware.org/?probe=b8edb4a562) | Aug 23, 2022 |
| HP            | Stream 11 Pro               | [de889aa178](https://linux-hardware.org/?probe=de889aa178) | Aug 23, 2022 |
| HP            | Pavilion g6                 | [ae65121050](https://linux-hardware.org/?probe=ae65121050) | Aug 23, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [3866b50e6e](https://linux-hardware.org/?probe=3866b50e6e) | Aug 23, 2022 |
| HP            | Laptop 15s-eq0xxx           | [29db41fc1b](https://linux-hardware.org/?probe=29db41fc1b) | Aug 23, 2022 |
| Dell          | Vostro 5481                 | [749e6c3622](https://linux-hardware.org/?probe=749e6c3622) | Aug 23, 2022 |
| TEKNOSERVI... | PORTATIL TTL 15             | [054d000bb1](https://linux-hardware.org/?probe=054d000bb1) | Aug 23, 2022 |
| ASUSTek       | X556UF                      | [23316377ee](https://linux-hardware.org/?probe=23316377ee) | Aug 23, 2022 |
| HP            | EliteBook 8470p             | [0b017b90c9](https://linux-hardware.org/?probe=0b017b90c9) | Aug 23, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [62db26b1b4](https://linux-hardware.org/?probe=62db26b1b4) | Aug 23, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [284d2fd5c1](https://linux-hardware.org/?probe=284d2fd5c1) | Aug 23, 2022 |
| Acer          | Aspire E5-571               | [659e36b0ed](https://linux-hardware.org/?probe=659e36b0ed) | Aug 23, 2022 |
| Dell          | Latitude D630               | [be9c4025cb](https://linux-hardware.org/?probe=be9c4025cb) | Aug 23, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [b008c35b2b](https://linux-hardware.org/?probe=b008c35b2b) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3c41ecc4e0](https://linux-hardware.org/?probe=3c41ecc4e0) | Aug 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | [323faca611](https://linux-hardware.org/?probe=323faca611) | Aug 22, 2022 |
| HP            | Compaq nc6400 (EH522AV)     | [1c583ce5d2](https://linux-hardware.org/?probe=1c583ce5d2) | Aug 22, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ee5962ca1e](https://linux-hardware.org/?probe=ee5962ca1e) | Aug 22, 2022 |
| Lenovo        | ThinkPad X230 23252UG       | [149419b2df](https://linux-hardware.org/?probe=149419b2df) | Aug 22, 2022 |
| Lenovo        | B570e 476022G               | [ad4a4c25d5](https://linux-hardware.org/?probe=ad4a4c25d5) | Aug 22, 2022 |
| Lenovo        | ThinkPad X230 23252UG       | [09505ab893](https://linux-hardware.org/?probe=09505ab893) | Aug 22, 2022 |
| HUAWEI        | NBD-WXX9                    | [4391428197](https://linux-hardware.org/?probe=4391428197) | Aug 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [2aa681b773](https://linux-hardware.org/?probe=2aa681b773) | Aug 22, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a51a82210b](https://linux-hardware.org/?probe=a51a82210b) | Aug 22, 2022 |
| Acer          | Aspire 5741G                | [dfa9c7ced0](https://linux-hardware.org/?probe=dfa9c7ced0) | Aug 22, 2022 |
| Dell          | Latitude E7240              | [4adf6ab444](https://linux-hardware.org/?probe=4adf6ab444) | Aug 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [6fcc3e058d](https://linux-hardware.org/?probe=6fcc3e058d) | Aug 22, 2022 |
| HP            | EliteBook 8440p             | [f85ff90a58](https://linux-hardware.org/?probe=f85ff90a58) | Aug 22, 2022 |
| HP            | EliteBook 8440p             | [3842f0e711](https://linux-hardware.org/?probe=3842f0e711) | Aug 22, 2022 |
| Lenovo        | ThinkPad E580 20KS0009AD    | [ba4d785a29](https://linux-hardware.org/?probe=ba4d785a29) | Aug 22, 2022 |
| Toshiba       | Satellite L875D             | [45ed0eb61a](https://linux-hardware.org/?probe=45ed0eb61a) | Aug 22, 2022 |
| Acer          | Aspire E1-410               | [e7d78093ba](https://linux-hardware.org/?probe=e7d78093ba) | Aug 22, 2022 |
| Acer          | Aspire E1-410               | [d2ba4edba4](https://linux-hardware.org/?probe=d2ba4edba4) | Aug 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [f1fa32b507](https://linux-hardware.org/?probe=f1fa32b507) | Aug 22, 2022 |
| ASUSTek       | X540NA                      | [1fa4b8b58a](https://linux-hardware.org/?probe=1fa4b8b58a) | Aug 21, 2022 |
| Dell          | Latitude 5490               | [a37eabe03f](https://linux-hardware.org/?probe=a37eabe03f) | Aug 21, 2022 |
| ASUSTek       | X540NA                      | [e9bcb08163](https://linux-hardware.org/?probe=e9bcb08163) | Aug 21, 2022 |
| Dell          | Inspiron 3583               | [d9ab8accea](https://linux-hardware.org/?probe=d9ab8accea) | Aug 21, 2022 |
| Dell          | Inspiron 3583               | [6ff066abac](https://linux-hardware.org/?probe=6ff066abac) | Aug 21, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [838dcef1f9](https://linux-hardware.org/?probe=838dcef1f9) | Aug 21, 2022 |
| HP            | Laptop 17-bs0xx             | [3dda19880c](https://linux-hardware.org/?probe=3dda19880c) | Aug 21, 2022 |
| Dell          | XPS 13 9370                 | [79d380d4af](https://linux-hardware.org/?probe=79d380d4af) | Aug 21, 2022 |
| Dell          | XPS 13 9350                 | [e663637449](https://linux-hardware.org/?probe=e663637449) | Aug 21, 2022 |
| ASUSTek       | X556UF                      | [9630e2d4f5](https://linux-hardware.org/?probe=9630e2d4f5) | Aug 21, 2022 |
| Samsung       | R519/R719                   | [c0720d7924](https://linux-hardware.org/?probe=c0720d7924) | Aug 21, 2022 |
| Dell          | G5 5587                     | [327f035c11](https://linux-hardware.org/?probe=327f035c11) | Aug 21, 2022 |
| ASUSTek       | Zenbook UM5401QA_UM5401Q... | [1380621999](https://linux-hardware.org/?probe=1380621999) | Aug 21, 2022 |
| ASUSTek       | K53SD                       | [1b2c4f25a7](https://linux-hardware.org/?probe=1b2c4f25a7) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | [75f94f8fa5](https://linux-hardware.org/?probe=75f94f8fa5) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | [aa44fba5de](https://linux-hardware.org/?probe=aa44fba5de) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2e77015116](https://linux-hardware.org/?probe=2e77015116) | Aug 21, 2022 |
| Dell          | Inspiron 1520               | [052b6ab02c](https://linux-hardware.org/?probe=052b6ab02c) | Aug 21, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [d4a7a111a7](https://linux-hardware.org/?probe=d4a7a111a7) | Aug 21, 2022 |
| Samsung       | 550P5C/550P7C               | [c369daf6b0](https://linux-hardware.org/?probe=c369daf6b0) | Aug 21, 2022 |
| Timi          | TM1701                      | [4591dee526](https://linux-hardware.org/?probe=4591dee526) | Aug 21, 2022 |
| Dell          | Latitude 5420               | [e8ccf9922e](https://linux-hardware.org/?probe=e8ccf9922e) | Aug 21, 2022 |
| Dell          | Latitude 5420               | [f44e5a1241](https://linux-hardware.org/?probe=f44e5a1241) | Aug 21, 2022 |
| Dell          | Inspiron 5447               | [21d9982f20](https://linux-hardware.org/?probe=21d9982f20) | Aug 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [342bd47a5a](https://linux-hardware.org/?probe=342bd47a5a) | Aug 20, 2022 |
| ASUSTek       | N56VZ                       | [e9e40a7df5](https://linux-hardware.org/?probe=e9e40a7df5) | Aug 20, 2022 |
| HP            | Pavilion dv6                | [5d8ca491cf](https://linux-hardware.org/?probe=5d8ca491cf) | Aug 20, 2022 |
| HP            | 15                          | [4d736aca15](https://linux-hardware.org/?probe=4d736aca15) | Aug 20, 2022 |
| MSI           | GS65 Stealth Thin 8RE       | [90aed4d5d1](https://linux-hardware.org/?probe=90aed4d5d1) | Aug 20, 2022 |
| Toshiba       | PORTEGE M780                | [8b7e72c5d9](https://linux-hardware.org/?probe=8b7e72c5d9) | Aug 20, 2022 |
| Dell          | Latitude E6430              | [30a702dcec](https://linux-hardware.org/?probe=30a702dcec) | Aug 20, 2022 |
| HP            | Compaq 6730b (KE718AV)      | [2bb0221a17](https://linux-hardware.org/?probe=2bb0221a17) | Aug 19, 2022 |
| Unknown       | Unknown                     | [937afb80d6](https://linux-hardware.org/?probe=937afb80d6) | Aug 19, 2022 |
| HUAWEI        | NBD-WXX9                    | [b7c760ecee](https://linux-hardware.org/?probe=b7c760ecee) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [87fcf5d702](https://linux-hardware.org/?probe=87fcf5d702) | Aug 19, 2022 |
| Lenovo        | V110-15IAP 80TG             | [65bb270b4e](https://linux-hardware.org/?probe=65bb270b4e) | Aug 19, 2022 |
| HP            | Laptop 14s-fq1xxx           | [61f9640136](https://linux-hardware.org/?probe=61f9640136) | Aug 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [bdb88a532f](https://linux-hardware.org/?probe=bdb88a532f) | Aug 19, 2022 |
| HP            | ElitePad 1000 G2            | [ed06ba603c](https://linux-hardware.org/?probe=ed06ba603c) | Aug 19, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [8834646a81](https://linux-hardware.org/?probe=8834646a81) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | [f21f1687d5](https://linux-hardware.org/?probe=f21f1687d5) | Aug 19, 2022 |
| Acer          | Aspire E5-475               | [04b38f1dfd](https://linux-hardware.org/?probe=04b38f1dfd) | Aug 19, 2022 |
| HP            | Laptop 15-da0xxx            | [7a9624c968](https://linux-hardware.org/?probe=7a9624c968) | Aug 19, 2022 |
| Acer          | Aspire E5-571               | [12371a2f0b](https://linux-hardware.org/?probe=12371a2f0b) | Aug 19, 2022 |
| Dell          | Inspiron 5535               | [b62b002b47](https://linux-hardware.org/?probe=b62b002b47) | Aug 19, 2022 |
| Dell          | Latitude E6410              | [3304a70394](https://linux-hardware.org/?probe=3304a70394) | Aug 19, 2022 |
| Compaq        | Presario 21 VerX            | [97aa39b2ca](https://linux-hardware.org/?probe=97aa39b2ca) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f9ec8eaac3](https://linux-hardware.org/?probe=f9ec8eaac3) | Aug 18, 2022 |
| Sony          | VPCEB1S1E                   | [45dbb67d02](https://linux-hardware.org/?probe=45dbb67d02) | Aug 18, 2022 |
| Dell          | Inspiron 7570               | [7d353117aa](https://linux-hardware.org/?probe=7d353117aa) | Aug 18, 2022 |
| Dell          | Inspiron 7570               | [10609a18a8](https://linux-hardware.org/?probe=10609a18a8) | Aug 18, 2022 |
| Apple         | MacBookAir6,2               | [f27c089486](https://linux-hardware.org/?probe=f27c089486) | Aug 18, 2022 |
| HP            | Stream 11 Pro               | [76b11a4ddb](https://linux-hardware.org/?probe=76b11a4ddb) | Aug 18, 2022 |
| MSI           | Katana GF66 11UG            | [74da710e26](https://linux-hardware.org/?probe=74da710e26) | Aug 18, 2022 |
| HP            | ProBook 640 G4              | [d4da530f4b](https://linux-hardware.org/?probe=d4da530f4b) | Aug 18, 2022 |
| ASUSTek       | ZenBook UX434FAC_UX433FA... | [a3da16034e](https://linux-hardware.org/?probe=a3da16034e) | Aug 18, 2022 |
| Lenovo        | G50-80 80E5                 | [1a392021c7](https://linux-hardware.org/?probe=1a392021c7) | Aug 18, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [2bf774fae7](https://linux-hardware.org/?probe=2bf774fae7) | Aug 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c32d69a956](https://linux-hardware.org/?probe=c32d69a956) | Aug 18, 2022 |
| Dynabook      | Satellite Pro C50-G-10M     | [92acf22491](https://linux-hardware.org/?probe=92acf22491) | Aug 18, 2022 |
| Dynabook      | Satellite Pro C50-G-10M     | [f1c882f6f9](https://linux-hardware.org/?probe=f1c882f6f9) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [658569ca5e](https://linux-hardware.org/?probe=658569ca5e) | Aug 18, 2022 |
| Acer          | Aspire E5-471G              | [3179053060](https://linux-hardware.org/?probe=3179053060) | Aug 18, 2022 |
| Acer          | TMP255-M                    | [ec78f44540](https://linux-hardware.org/?probe=ec78f44540) | Aug 18, 2022 |
| Acer          | TMP255-M                    | [b0bf845535](https://linux-hardware.org/?probe=b0bf845535) | Aug 18, 2022 |
| Packard Be... | EasyNote TJ65               | [df3b457c00](https://linux-hardware.org/?probe=df3b457c00) | Aug 18, 2022 |
| Lenovo        | G580 20150                  | [3c18536e95](https://linux-hardware.org/?probe=3c18536e95) | Aug 18, 2022 |
| Apple         | MacBookPro8,2               | [5200949f98](https://linux-hardware.org/?probe=5200949f98) | Aug 18, 2022 |
| HP            | EliteBook 8470p             | [8f5ed294e7](https://linux-hardware.org/?probe=8f5ed294e7) | Aug 17, 2022 |
| HP            | Laptop 14-cm0xxx            | [e6b2ec9760](https://linux-hardware.org/?probe=e6b2ec9760) | Aug 17, 2022 |
| Acer          | Aspire E1-431               | [d4132b425f](https://linux-hardware.org/?probe=d4132b425f) | Aug 17, 2022 |
| Dell          | Inspiron 7520               | [96349ba82a](https://linux-hardware.org/?probe=96349ba82a) | Aug 17, 2022 |
| ASUSTek       | X556UQ                      | [cc792932e6](https://linux-hardware.org/?probe=cc792932e6) | Aug 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e9d1b72a88](https://linux-hardware.org/?probe=e9d1b72a88) | Aug 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [f3731f8754](https://linux-hardware.org/?probe=f3731f8754) | Aug 17, 2022 |
| HP            | Laptop 15-dw3xxx            | [f0d245ec0f](https://linux-hardware.org/?probe=f0d245ec0f) | Aug 17, 2022 |
| Dell          | XPS 15 9560                 | [d971bbde47](https://linux-hardware.org/?probe=d971bbde47) | Aug 17, 2022 |
| Dell          | XPS 15 9520                 | [7e75c31235](https://linux-hardware.org/?probe=7e75c31235) | Aug 17, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9003287b49](https://linux-hardware.org/?probe=9003287b49) | Aug 17, 2022 |
| Packard Be... | EasyNote TS11HR             | [9d82dca288](https://linux-hardware.org/?probe=9d82dca288) | Aug 17, 2022 |
| Toshiba       | Satellite C870-1F3          | [6738afe025](https://linux-hardware.org/?probe=6738afe025) | Aug 17, 2022 |
| Dell          | G15 5515                    | [3a7c8ea452](https://linux-hardware.org/?probe=3a7c8ea452) | Aug 17, 2022 |
| Toshiba       | Satellite C55-A             | [b5108145be](https://linux-hardware.org/?probe=b5108145be) | Aug 17, 2022 |
| Toshiba       | Satellite C55-A             | [0db7961f5a](https://linux-hardware.org/?probe=0db7961f5a) | Aug 17, 2022 |
| Dell          | Latitude 7400               | [7f870ac8c2](https://linux-hardware.org/?probe=7f870ac8c2) | Aug 17, 2022 |
| HP            | ProBook 4440s               | [5f3b887159](https://linux-hardware.org/?probe=5f3b887159) | Aug 17, 2022 |
| ASUSTek       | K72Jr                       | [604b0356b1](https://linux-hardware.org/?probe=604b0356b1) | Aug 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [dcfef0a5d7](https://linux-hardware.org/?probe=dcfef0a5d7) | Aug 17, 2022 |
| HP            | Compaq 6720s                | [bf767707b2](https://linux-hardware.org/?probe=bf767707b2) | Aug 17, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [96c0510005](https://linux-hardware.org/?probe=96c0510005) | Aug 16, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [364ebb944a](https://linux-hardware.org/?probe=364ebb944a) | Aug 16, 2022 |
| Notebook      | NS5x_NS7xPU                 | [9c61455acb](https://linux-hardware.org/?probe=9c61455acb) | Aug 16, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2b746c613f](https://linux-hardware.org/?probe=2b746c613f) | Aug 16, 2022 |
| Samsung       | SP55S                       | [da13a56b12](https://linux-hardware.org/?probe=da13a56b12) | Aug 16, 2022 |
| Lenovo        | G50-80 80E5                 | [112c52fe0c](https://linux-hardware.org/?probe=112c52fe0c) | Aug 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b9e32d8f94](https://linux-hardware.org/?probe=b9e32d8f94) | Aug 16, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [a6b5ac708a](https://linux-hardware.org/?probe=a6b5ac708a) | Aug 16, 2022 |
| Notebook      | NS5x_NS7xPU                 | [9f6a6e3775](https://linux-hardware.org/?probe=9f6a6e3775) | Aug 16, 2022 |
| Apple         | MacBookPro9,2               | [565bb62364](https://linux-hardware.org/?probe=565bb62364) | Aug 16, 2022 |
| HP            | Pavilion g6                 | [ddc9a7396e](https://linux-hardware.org/?probe=ddc9a7396e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | [ef1cbed5a4](https://linux-hardware.org/?probe=ef1cbed5a4) | Aug 16, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [c62eb0135b](https://linux-hardware.org/?probe=c62eb0135b) | Aug 15, 2022 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [4d5eb5e332](https://linux-hardware.org/?probe=4d5eb5e332) | Aug 15, 2022 |
| VALE          | Notebook Classic C170       | [e1563aa775](https://linux-hardware.org/?probe=e1563aa775) | Aug 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [88fc37216d](https://linux-hardware.org/?probe=88fc37216d) | Aug 15, 2022 |
| ASUSTek       | X501A1                      | [d021969767](https://linux-hardware.org/?probe=d021969767) | Aug 15, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [6c757dee54](https://linux-hardware.org/?probe=6c757dee54) | Aug 15, 2022 |
| Dell          | Precision 3571              | [ba2a6f6d10](https://linux-hardware.org/?probe=ba2a6f6d10) | Aug 15, 2022 |
| Dell          | Latitude 3510               | [97e3f5102d](https://linux-hardware.org/?probe=97e3f5102d) | Aug 15, 2022 |
| HP            | ProBook 450 G3              | [b359d6e711](https://linux-hardware.org/?probe=b359d6e711) | Aug 15, 2022 |
| ASUSTek       | GL552VW                     | [ae85f68d58](https://linux-hardware.org/?probe=ae85f68d58) | Aug 15, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [ffe1757df5](https://linux-hardware.org/?probe=ffe1757df5) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [caf6393a95](https://linux-hardware.org/?probe=caf6393a95) | Aug 15, 2022 |
| Dell          | Latitude 5531               | [4697382760](https://linux-hardware.org/?probe=4697382760) | Aug 15, 2022 |
| Dell          | Precision 3571              | [0aefc564d4](https://linux-hardware.org/?probe=0aefc564d4) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | [ce03a2383e](https://linux-hardware.org/?probe=ce03a2383e) | Aug 15, 2022 |
| Notebook      | NS5x_NS7xPU                 | [b85f9a8cfd](https://linux-hardware.org/?probe=b85f9a8cfd) | Aug 15, 2022 |
| Apple         | MacBook4,1                  | [1c9628e804](https://linux-hardware.org/?probe=1c9628e804) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | [cb10c34587](https://linux-hardware.org/?probe=cb10c34587) | Aug 15, 2022 |
| HP            | Laptop 15-da1xxx            | [dd375c139f](https://linux-hardware.org/?probe=dd375c139f) | Aug 14, 2022 |
| Packard Be... | EasyNote TS11HR             | [837159c07a](https://linux-hardware.org/?probe=837159c07a) | Aug 14, 2022 |
| Lenovo        | G50-80 80E5                 | [29724f5a3f](https://linux-hardware.org/?probe=29724f5a3f) | Aug 14, 2022 |
| Timi          | TM1701                      | [f54a2ca3bc](https://linux-hardware.org/?probe=f54a2ca3bc) | Aug 14, 2022 |
| MSI           | Alpha 15 A3DD               | [fd548daf00](https://linux-hardware.org/?probe=fd548daf00) | Aug 14, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | [da2935226c](https://linux-hardware.org/?probe=da2935226c) | Aug 14, 2022 |
| HP            | EliteBook 840 G3            | [81b8b0400d](https://linux-hardware.org/?probe=81b8b0400d) | Aug 14, 2022 |
| Lenovo        | G50-80 80E5                 | [132a476896](https://linux-hardware.org/?probe=132a476896) | Aug 14, 2022 |
| Lenovo        | ThinkPad E550 20DF0040CA    | [0f657d4798](https://linux-hardware.org/?probe=0f657d4798) | Aug 14, 2022 |
| Notebook      | NL40_50CU                   | [dc6838dde5](https://linux-hardware.org/?probe=dc6838dde5) | Aug 14, 2022 |
| Acer          | Aspire V5-471PG             | [c91dcf26c8](https://linux-hardware.org/?probe=c91dcf26c8) | Aug 14, 2022 |
| Dell          | Latitude 5531               | [aaac45c3dd](https://linux-hardware.org/?probe=aaac45c3dd) | Aug 14, 2022 |
| Lenovo        | V130-15IKB 81HN             | [b479c93d90](https://linux-hardware.org/?probe=b479c93d90) | Aug 14, 2022 |
| Timi          | TM1701                      | [dc4d12ca83](https://linux-hardware.org/?probe=dc4d12ca83) | Aug 14, 2022 |
| Acer          | Nitro AN515-42              | [f4626d5fde](https://linux-hardware.org/?probe=f4626d5fde) | Aug 14, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [66a759db9c](https://linux-hardware.org/?probe=66a759db9c) | Aug 14, 2022 |
| Lenovo        | IdeaPad S540-13IML 81XA     | [9ee2e85959](https://linux-hardware.org/?probe=9ee2e85959) | Aug 14, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [fa12e95e32](https://linux-hardware.org/?probe=fa12e95e32) | Aug 14, 2022 |
| A-DATA Tec... | XENIA 14                    | [51cc14cc1f](https://linux-hardware.org/?probe=51cc14cc1f) | Aug 14, 2022 |
| ASUSTek       | N53SN                       | [6cb4ac4247](https://linux-hardware.org/?probe=6cb4ac4247) | Aug 14, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [e7783dda18](https://linux-hardware.org/?probe=e7783dda18) | Aug 13, 2022 |
| HP            | ProBook 640 G1              | [7f8289a8f3](https://linux-hardware.org/?probe=7f8289a8f3) | Aug 13, 2022 |
| HP            | 470 G7 Notebook PC          | [adae536639](https://linux-hardware.org/?probe=adae536639) | Aug 13, 2022 |
| HP            | 470 G7 Notebook PC          | [5a319a7a29](https://linux-hardware.org/?probe=5a319a7a29) | Aug 13, 2022 |
| BESSTAR Te... | X400                        | [b6dcf79292](https://linux-hardware.org/?probe=b6dcf79292) | Aug 13, 2022 |
| HP            | Pavilion 15                 | [a5ef05aaff](https://linux-hardware.org/?probe=a5ef05aaff) | Aug 13, 2022 |
| Apple         | MacBookPro16,1              | [720b74b4f8](https://linux-hardware.org/?probe=720b74b4f8) | Aug 13, 2022 |
| Acer          | Nitro AN515-42              | [ca0a82cb87](https://linux-hardware.org/?probe=ca0a82cb87) | Aug 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [298cf4b527](https://linux-hardware.org/?probe=298cf4b527) | Aug 13, 2022 |
| Samsung       | 300E5M/300E5L               | [e39c1b59a6](https://linux-hardware.org/?probe=e39c1b59a6) | Aug 13, 2022 |
| Acer          | Aspire V5-471PG             | [5c2d9bf35f](https://linux-hardware.org/?probe=5c2d9bf35f) | Aug 13, 2022 |
| Dell          | Inspiron 1545               | [039ac79042](https://linux-hardware.org/?probe=039ac79042) | Aug 13, 2022 |
| Acer          | Aspire E5-575               | [60580d80c4](https://linux-hardware.org/?probe=60580d80c4) | Aug 13, 2022 |
| Toshiba       | PORTEGE M780                | [b7304a84fd](https://linux-hardware.org/?probe=b7304a84fd) | Aug 13, 2022 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [0f367345a0](https://linux-hardware.org/?probe=0f367345a0) | Aug 12, 2022 |
| HUAWEI        | HVY-WXX9                    | [1caa3886f8](https://linux-hardware.org/?probe=1caa3886f8) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | [3e63b30226](https://linux-hardware.org/?probe=3e63b30226) | Aug 12, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [73a3d7c1cf](https://linux-hardware.org/?probe=73a3d7c1cf) | Aug 12, 2022 |
| HP            | 15                          | [30a35c4e04](https://linux-hardware.org/?probe=30a35c4e04) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [f8a6209b06](https://linux-hardware.org/?probe=f8a6209b06) | Aug 12, 2022 |
| Lenovo        | ThinkPad T490s 20NYS79X0... | [5fe4fba501](https://linux-hardware.org/?probe=5fe4fba501) | Aug 12, 2022 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [db6af6dbfc](https://linux-hardware.org/?probe=db6af6dbfc) | Aug 12, 2022 |
| BESSTAR Te... | X400                        | [e8424e153d](https://linux-hardware.org/?probe=e8424e153d) | Aug 12, 2022 |
| HP            | 255 G6 Notebook PC          | [d53db96c14](https://linux-hardware.org/?probe=d53db96c14) | Aug 12, 2022 |
| HP            | 255 G6 Notebook PC          | [1eaceda85f](https://linux-hardware.org/?probe=1eaceda85f) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX534FAC            | [419660b78b](https://linux-hardware.org/?probe=419660b78b) | Aug 12, 2022 |
| HP            | ProBook 6570b               | [335eb52112](https://linux-hardware.org/?probe=335eb52112) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0c3e294d06](https://linux-hardware.org/?probe=0c3e294d06) | Aug 12, 2022 |
| Notebook      | NS5x_NS7xPU                 | [ee9c6679ca](https://linux-hardware.org/?probe=ee9c6679ca) | Aug 12, 2022 |
| HUAWEI        | CREM-WXX9                   | [dbdcafa667](https://linux-hardware.org/?probe=dbdcafa667) | Aug 11, 2022 |
| Apple         | MacBookPro11,3              | [1091d27582](https://linux-hardware.org/?probe=1091d27582) | Aug 11, 2022 |
| HP            | ProBook 450 G5              | [846e1d6c9f](https://linux-hardware.org/?probe=846e1d6c9f) | Aug 11, 2022 |
| Dell          | XPS 9320                    | [2c76534231](https://linux-hardware.org/?probe=2c76534231) | Aug 11, 2022 |
| Avell High... | B.ON                        | [b057c64850](https://linux-hardware.org/?probe=b057c64850) | Aug 11, 2022 |
| Dell          | Inspiron 3584               | [3ba16dc3e1](https://linux-hardware.org/?probe=3ba16dc3e1) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [4360427600](https://linux-hardware.org/?probe=4360427600) | Aug 11, 2022 |
| HP            | Stream Notebook PC 13       | [09b81bbcc4](https://linux-hardware.org/?probe=09b81bbcc4) | Aug 11, 2022 |
| MSI           | Modern 14 A10RB             | [9979c66e3e](https://linux-hardware.org/?probe=9979c66e3e) | Aug 11, 2022 |
| Lenovo        | ThinkPad Edge E530 62724... | [53ad80ce0d](https://linux-hardware.org/?probe=53ad80ce0d) | Aug 11, 2022 |
| ASUSTek       | X510UR                      | [3faeed2cc1](https://linux-hardware.org/?probe=3faeed2cc1) | Aug 11, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [4a34f7697a](https://linux-hardware.org/?probe=4a34f7697a) | Aug 11, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8b0ede5e40](https://linux-hardware.org/?probe=8b0ede5e40) | Aug 10, 2022 |
| Dell          | Precision 5530              | [08137fb7ea](https://linux-hardware.org/?probe=08137fb7ea) | Aug 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [bd5bfb000b](https://linux-hardware.org/?probe=bd5bfb000b) | Aug 10, 2022 |
| Sony          | VPCYB20AL                   | [f886e2ff98](https://linux-hardware.org/?probe=f886e2ff98) | Aug 10, 2022 |
| Dell          | Latitude E7450              | [3992650626](https://linux-hardware.org/?probe=3992650626) | Aug 10, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [3151f7847e](https://linux-hardware.org/?probe=3151f7847e) | Aug 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [0f33fa05f5](https://linux-hardware.org/?probe=0f33fa05f5) | Aug 10, 2022 |
| Dell          | XPS 9320                    | [f1ce1578ed](https://linux-hardware.org/?probe=f1ce1578ed) | Aug 10, 2022 |
| Dell          | Inspiron 5523               | [6a6928a8a5](https://linux-hardware.org/?probe=6a6928a8a5) | Aug 10, 2022 |
| HP            | 2000                        | [f933964387](https://linux-hardware.org/?probe=f933964387) | Aug 10, 2022 |
| HUAWEI        | MACHR-WX9                   | [19f2f18728](https://linux-hardware.org/?probe=19f2f18728) | Aug 10, 2022 |
| MSI           | Creator 15 A11UE            | [9685c95f42](https://linux-hardware.org/?probe=9685c95f42) | Aug 09, 2022 |
| Lenovo        | V330-15IKB 81AX             | [39922e64f8](https://linux-hardware.org/?probe=39922e64f8) | Aug 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [364f2e0a23](https://linux-hardware.org/?probe=364f2e0a23) | Aug 09, 2022 |
| Lenovo        | ThinkPad T460p 20FWCTO1W... | [2ac0968200](https://linux-hardware.org/?probe=2ac0968200) | Aug 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [63a6df97b9](https://linux-hardware.org/?probe=63a6df97b9) | Aug 09, 2022 |
| HUAWEI        | KLVC-WXX9                   | [fa0e4ba168](https://linux-hardware.org/?probe=fa0e4ba168) | Aug 09, 2022 |
| HP            | Pavilion g6                 | [4b6fc67f06](https://linux-hardware.org/?probe=4b6fc67f06) | Aug 09, 2022 |
| Dell          | Inspiron 5593               | [1b59fcaefb](https://linux-hardware.org/?probe=1b59fcaefb) | Aug 09, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [8a7ce6e755](https://linux-hardware.org/?probe=8a7ce6e755) | Aug 09, 2022 |
| HP            | Laptop 15-dy1xxx            | [38d16fe95a](https://linux-hardware.org/?probe=38d16fe95a) | Aug 09, 2022 |
| Dell          | Latitude 5531               | [64998a7d5a](https://linux-hardware.org/?probe=64998a7d5a) | Aug 09, 2022 |
| Acer          | Nitro AN515-54              | [bb2e5a2390](https://linux-hardware.org/?probe=bb2e5a2390) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [e4be834b9b](https://linux-hardware.org/?probe=e4be834b9b) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [032e3470a6](https://linux-hardware.org/?probe=032e3470a6) | Aug 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9a06c0c10c](https://linux-hardware.org/?probe=9a06c0c10c) | Aug 09, 2022 |
| Dell          | Inspiron 7370               | [17d8e571fa](https://linux-hardware.org/?probe=17d8e571fa) | Aug 08, 2022 |
| MSI           | Creator 15 A11UE            | [45702835fc](https://linux-hardware.org/?probe=45702835fc) | Aug 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [114ada270e](https://linux-hardware.org/?probe=114ada270e) | Aug 08, 2022 |
| Dell          | XPS 15 9520                 | [50420ea12f](https://linux-hardware.org/?probe=50420ea12f) | Aug 08, 2022 |
| ASUSTek       | X540NA                      | [c37ee0a700](https://linux-hardware.org/?probe=c37ee0a700) | Aug 08, 2022 |
| Fujitsu       | LIFEBOOK E5412              | [daa7780efb](https://linux-hardware.org/?probe=daa7780efb) | Aug 08, 2022 |
| Acer          | Aspire A315-56              | [742452483f](https://linux-hardware.org/?probe=742452483f) | Aug 08, 2022 |
| Dell          | Inspiron 5447               | [65b4e485ad](https://linux-hardware.org/?probe=65b4e485ad) | Aug 08, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [21e646de39](https://linux-hardware.org/?probe=21e646de39) | Aug 08, 2022 |
| Apple         | MacBookPro14,1              | [7115af1c63](https://linux-hardware.org/?probe=7115af1c63) | Aug 08, 2022 |
| Framework     | Laptop                      | [c52019fe10](https://linux-hardware.org/?probe=c52019fe10) | Aug 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [dff2dcd497](https://linux-hardware.org/?probe=dff2dcd497) | Aug 07, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [023d68a796](https://linux-hardware.org/?probe=023d68a796) | Aug 07, 2022 |
| Timi          | RedmiBook 16                | [d1e515a491](https://linux-hardware.org/?probe=d1e515a491) | Aug 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [977159d1d8](https://linux-hardware.org/?probe=977159d1d8) | Aug 07, 2022 |
| HP            | Pavilion g6                 | [aa437aea14](https://linux-hardware.org/?probe=aa437aea14) | Aug 07, 2022 |
| ASUSTek       | N56VZ                       | [3ee621b609](https://linux-hardware.org/?probe=3ee621b609) | Aug 07, 2022 |
| MSI           | Vector GP66 12UH            | [561191fa0e](https://linux-hardware.org/?probe=561191fa0e) | Aug 07, 2022 |
| Acer          | Aspire A315-41              | [6a9c811ea3](https://linux-hardware.org/?probe=6a9c811ea3) | Aug 07, 2022 |
| HP            | Pavilion g6                 | [7543f383ad](https://linux-hardware.org/?probe=7543f383ad) | Aug 07, 2022 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [8f7ef1d997](https://linux-hardware.org/?probe=8f7ef1d997) | Aug 07, 2022 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [ffab2b901d](https://linux-hardware.org/?probe=ffab2b901d) | Aug 07, 2022 |
| HUAWEI        | KLVD-WXX9                   | [ba034abead](https://linux-hardware.org/?probe=ba034abead) | Aug 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [8e2366679b](https://linux-hardware.org/?probe=8e2366679b) | Aug 07, 2022 |
| Lenovo        | ThinkPad Twist 33477RG      | [9b826e7361](https://linux-hardware.org/?probe=9b826e7361) | Aug 07, 2022 |
| AZW           | GT-R                        | [5d6effabbd](https://linux-hardware.org/?probe=5d6effabbd) | Aug 06, 2022 |
| AZW           | GT-R                        | [c121b194be](https://linux-hardware.org/?probe=c121b194be) | Aug 06, 2022 |
| Dell          | XPS 13 9310                 | [7e9a6b9e85](https://linux-hardware.org/?probe=7e9a6b9e85) | Aug 06, 2022 |
| HP            | 255 G6 Notebook PC          | [de1dd136e8](https://linux-hardware.org/?probe=de1dd136e8) | Aug 06, 2022 |
| Apple         | MacBookPro11,5              | [968cdd1444](https://linux-hardware.org/?probe=968cdd1444) | Aug 06, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.15.0-47-generic        | 249       | 12.27%  |
| 5.15.0-46-generic        | 226       | 11.13%  |
| 5.15.0-27-generic        | 174       | 8.57%   |
| 5.15.0-41-generic        | 162       | 7.98%   |
| 5.15.0-25-generic        | 160       | 7.88%   |
| 5.15.0-43-generic        | 159       | 7.83%   |
| 5.15.0-40-generic        | 156       | 7.68%   |
| 5.15.0-48-generic        | 153       | 7.54%   |
| 5.15.0-33-generic        | 107       | 5.27%   |
| 5.15.0-30-generic        | 86        | 4.24%   |
| 5.15.0-39-generic        | 72        | 3.55%   |
| 5.15.0-37-generic        | 57        | 2.81%   |
| 5.15.0-35-generic        | 46        | 2.27%   |
| 5.15.0-23-generic        | 21        | 1.03%   |
| 5.15.0-18-generic        | 13        | 0.64%   |
| 5.15.0-50-generic        | 10        | 0.49%   |
| 5.15.0-28-generic        | 7         | 0.34%   |
| 5.15.0-17-generic        | 7         | 0.34%   |
| 5.19.0-051900-generic    | 6         | 0.3%    |
| 5.17.0-051700-generic    | 5         | 0.25%   |
| 5.15.0-22-generic        | 5         | 0.25%   |
| 5.13.0-19-generic        | 5         | 0.25%   |
| 5.19.5-051905-generic    | 4         | 0.2%    |
| 5.18.0-051800-generic    | 4         | 0.2%    |
| 5.17.1-051701-generic    | 4         | 0.2%    |
| 5.17.0-1012-oem          | 4         | 0.2%    |
| 5.15.0-32-generic        | 4         | 0.2%    |
| 5.17.9-051709-generic    | 3         | 0.15%   |
| 5.17.2-051702-generic    | 3         | 0.15%   |
| 5.17.0-1016-oem          | 3         | 0.15%   |
| 5.15.0-36-generic        | 3         | 0.15%   |
| 6.0.0-060000rc3-generic  | 2         | 0.1%    |
| 5.19.3-051903-generic    | 2         | 0.1%    |
| 5.19.11-051911-generic   | 2         | 0.1%    |
| 5.18.8-t2                | 2         | 0.1%    |
| 5.18.15-051815-generic   | 2         | 0.1%    |
| 5.18.0-051800rc1-generic | 2         | 0.1%    |
| 5.17.8-051708-generic    | 2         | 0.1%    |
| 5.17.6-051706-generic    | 2         | 0.1%    |
| 5.17.5-051705-generic    | 2         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 1795      | 92.86%  |
| 5.17.0  | 29        | 1.5%    |
| 5.14.0  | 10        | 0.52%   |
| 5.13.0  | 10        | 0.52%   |
| 5.19.0  | 8         | 0.41%   |
| 5.18.0  | 8         | 0.41%   |
| 6.0.0   | 4         | 0.21%   |
| 5.19.5  | 4         | 0.21%   |
| 5.17.1  | 4         | 0.21%   |
| 5.18.8  | 3         | 0.16%   |
| 5.17.9  | 3         | 0.16%   |
| 5.17.8  | 3         | 0.16%   |
| 5.17.5  | 3         | 0.16%   |
| 5.17.2  | 3         | 0.16%   |
| 5.16.0  | 3         | 0.16%   |
| 5.19.3  | 2         | 0.1%    |
| 5.19.11 | 2         | 0.1%    |
| 5.18.6  | 2         | 0.1%    |
| 5.18.15 | 2         | 0.1%    |
| 5.17.6  | 2         | 0.1%    |
| 5.17.4  | 2         | 0.1%    |
| 5.17.11 | 2         | 0.1%    |
| 5.13.19 | 2         | 0.1%    |
| 5.4.0   | 1         | 0.05%   |
| 5.19.2  | 1         | 0.05%   |
| 5.19.1  | 1         | 0.05%   |
| 5.18.4  | 1         | 0.05%   |
| 5.18.3  | 1         | 0.05%   |
| 5.18.2  | 1         | 0.05%   |
| 5.18.16 | 1         | 0.05%   |
| 5.18.12 | 1         | 0.05%   |
| 5.18.11 | 1         | 0.05%   |
| 5.18.1  | 1         | 0.05%   |
| 5.17.15 | 1         | 0.05%   |
| 5.16.2  | 1         | 0.05%   |
| 5.16.11 | 1         | 0.05%   |
| 5.15.70 | 1         | 0.05%   |
| 5.15.67 | 1         | 0.05%   |
| 5.15.6  | 1         | 0.05%   |
| 5.15.55 | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 1805      | 93.52%  |
| 5.17    | 52        | 2.69%   |
| 5.18    | 21        | 1.09%   |
| 5.19    | 18        | 0.93%   |
| 5.13    | 12        | 0.62%   |
| 5.14    | 10        | 0.52%   |
| 5.16    | 5         | 0.26%   |
| 6.0     | 4         | 0.21%   |
| 5.4     | 1         | 0.05%   |
| 5.11    | 1         | 0.05%   |
| 5.10    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1922      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 1853      | 96.16%  |
| Unknown           | 47        | 2.44%   |
| GNOME Flashback   | 9         | 0.47%   |
| X-Cinnamon        | 6         | 0.31%   |
| i3                | 4         | 0.21%   |
| Cinnamon          | 3         | 0.16%   |
| Yaru:ubuntu:GNOME | 1         | 0.05%   |
| GNUstep           | 1         | 0.05%   |
| GNOME Classic     | 1         | 0.05%   |
| dwm               | 1         | 0.05%   |
| awesome           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 1330      | 68.38%  |
| X11     | 572       | 29.41%  |
| Unknown | 24        | 1.23%   |
| Tty     | 19        | 0.98%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 1760      | 91.24%  |
| Unknown | 124       | 6.43%   |
| LightDM | 27        | 1.4%    |
| GDM     | 9         | 0.47%   |
| SDDM    | 8         | 0.41%   |
| XDM     | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 910       | 47.27%  |
| de_DE   | 128       | 6.65%   |
| pt_BR   | 101       | 5.25%   |
| fr_FR   | 90        | 4.68%   |
| en_GB   | 88        | 4.57%   |
| en_IN   | 76        | 3.95%   |
| es_ES   | 52        | 2.7%    |
| it_IT   | 47        | 2.44%   |
| ru_RU   | 39        | 2.03%   |
| pl_PL   | 37        | 1.92%   |
| en_CA   | 29        | 1.51%   |
| en_AU   | 29        | 1.51%   |
| zh_CN   | 20        | 1.04%   |
| C       | 15        | 0.78%   |
| pt_PT   | 14        | 0.73%   |
| nl_NL   | 14        | 0.73%   |
| hu_HU   | 13        | 0.68%   |
| es_AR   | 13        | 0.68%   |
| en_ZA   | 13        | 0.68%   |
| es_MX   | 12        | 0.62%   |
| tr_TR   | 11        | 0.57%   |
| da_DK   | 11        | 0.57%   |
| cs_CZ   | 11        | 0.57%   |
| Unknown | 10        | 0.52%   |
| sv_SE   | 8         | 0.42%   |
| fr_BE   | 8         | 0.42%   |
| de_AT   | 8         | 0.42%   |
| fi_FI   | 7         | 0.36%   |
| ro_RO   | 6         | 0.31%   |
| es_CO   | 6         | 0.31%   |
| es_CL   | 6         | 0.31%   |
| en_IL   | 6         | 0.31%   |
| de_CH   | 6         | 0.31%   |
| nb_NO   | 5         | 0.26%   |
| ja_JP   | 5         | 0.26%   |
| en_PH   | 5         | 0.26%   |
| en_NZ   | 5         | 0.26%   |
| en_HK   | 5         | 0.26%   |
| en_SG   | 4         | 0.21%   |
| en_IE   | 4         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1073      | 55.6%   |
| EFI  | 857       | 44.4%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1795      | 93.15%  |
| Overlay | 53        | 2.75%   |
| Zfs     | 49        | 2.54%   |
| Btrfs   | 17        | 0.88%   |
| Xfs     | 5         | 0.26%   |
| Ext3    | 5         | 0.26%   |
| Ext2    | 3         | 0.16%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1107      | 57.51%  |
| GPT     | 774       | 40.21%  |
| MBR     | 44        | 2.29%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1781      | 92.23%  |
| Yes       | 150       | 7.77%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1231      | 63.78%  |
| Yes       | 699       | 36.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 396       | 20.6%   |
| Hewlett-Packard        | 357       | 18.57%  |
| Dell                   | 334       | 17.38%  |
| ASUSTek Computer       | 205       | 10.67%  |
| Acer                   | 150       | 7.8%    |
| Toshiba                | 49        | 2.55%   |
| MSI                    | 49        | 2.55%   |
| HUAWEI                 | 47        | 2.45%   |
| Apple                  | 47        | 2.45%   |
| Samsung Electronics    | 30        | 1.56%   |
| Sony                   | 17        | 0.88%   |
| Timi                   | 15        | 0.78%   |
| Google                 | 13        | 0.68%   |
| Alienware              | 13        | 0.68%   |
| Positivo               | 12        | 0.62%   |
| Unknown                | 12        | 0.62%   |
| Chuwi                  | 11        | 0.57%   |
| Medion                 | 10        | 0.52%   |
| Notebook               | 9         | 0.47%   |
| Fujitsu                | 8         | 0.42%   |
| LG Electronics         | 7         | 0.36%   |
| Avell High Performance | 7         | 0.36%   |
| Razer                  | 6         | 0.31%   |
| Packard Bell           | 6         | 0.31%   |
| System76               | 5         | 0.26%   |
| Gateway                | 5         | 0.26%   |
| Teclast                | 4         | 0.21%   |
| Jumper                 | 4         | 0.21%   |
| GPU Company            | 4         | 0.21%   |
| Gigabyte Technology    | 4         | 0.21%   |
| Framework              | 4         | 0.21%   |
| AMI                    | 4         | 0.21%   |
| Panasonic              | 3         | 0.16%   |
| NEC Computers          | 3         | 0.16%   |
| Monster                | 3         | 0.16%   |
| HONOR                  | 3         | 0.16%   |
| AZW                    | 3         | 0.16%   |
| TUXEDO                 | 2         | 0.1%    |
| TrekStor               | 2         | 0.1%    |
| Schenker               | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 16        | 0.83%   |
| HP Notebook                     | 9         | 0.47%   |
| HUAWEI HVY-WXX9                 | 8         | 0.42%   |
| HP Pavilion g6                  | 8         | 0.42%   |
| Dell Latitude 5420              | 8         | 0.42%   |
| HP Pavilion 15                  | 7         | 0.36%   |
| HP Pavilion Notebook            | 6         | 0.31%   |
| HP EliteBook 840 G8 Notebook PC | 6         | 0.31%   |
| HP EliteBook 840 G1             | 6         | 0.31%   |
| Dell XPS 15 9520                | 6         | 0.31%   |
| Alienware x17 R2                | 6         | 0.31%   |
| Acer Aspire E5-571              | 6         | 0.31%   |
| Timi TM1701                     | 5         | 0.26%   |
| Lenovo IdeaPad 5 14ITL05 82FE   | 5         | 0.26%   |
| HUAWEI BOM-WXX9                 | 5         | 0.26%   |
| HP ProBook 440 G8 Notebook PC   | 5         | 0.26%   |
| HP EliteBook 840 G3             | 5         | 0.26%   |
| HP 15                           | 5         | 0.26%   |
| Dell XPS 15 9500                | 5         | 0.26%   |
| Dell XPS 15 7590                | 5         | 0.26%   |
| Dell XPS 13 9380                | 5         | 0.26%   |
| Dell Latitude E7470             | 5         | 0.26%   |
| Dell Latitude E6510             | 5         | 0.26%   |
| Dell Latitude 5520              | 5         | 0.26%   |
| Acer Swift SF314-43             | 5         | 0.26%   |
| Acer Swift SF314-42             | 5         | 0.26%   |
| Lenovo ThinkBook 15 G3 ACL 21A4 | 4         | 0.21%   |
| Lenovo IdeaPad 5 14ALC05 82LM   | 4         | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81DE   | 4         | 0.21%   |
| HUAWEI NBLB-WAX9N               | 4         | 0.21%   |
| HUAWEI BOHK-WAX9X               | 4         | 0.21%   |
| HUAWEI BOHB-WAX9                | 4         | 0.21%   |
| HP ProBook 650 G1               | 4         | 0.21%   |
| HP Pavilion g7                  | 4         | 0.21%   |
| HP Laptop 15s-eq2xxx            | 4         | 0.21%   |
| HP Laptop 15-db0xxx             | 4         | 0.21%   |
| HP Laptop 15-da0xxx             | 4         | 0.21%   |
| Framework Laptop                | 4         | 0.21%   |
| Dell XPS 15 9570                | 4         | 0.21%   |
| Dell XPS 15 9560                | 4         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 178       | 9.26%   |
| Dell Latitude         | 111       | 5.78%   |
| Lenovo IdeaPad        | 105       | 5.46%   |
| Acer Aspire           | 99        | 5.15%   |
| Dell Inspiron         | 98        | 5.1%    |
| HP Pavilion           | 68        | 3.54%   |
| HP ProBook            | 62        | 3.23%   |
| HP EliteBook          | 62        | 3.23%   |
| HP Laptop             | 57        | 2.97%   |
| Dell XPS              | 54        | 2.81%   |
| ASUS VivoBook         | 48        | 2.5%    |
| Toshiba Satellite     | 38        | 1.98%   |
| Dell Precision        | 28        | 1.46%   |
| ASUS ROG              | 26        | 1.35%   |
| Lenovo ThinkBook      | 25        | 1.3%    |
| Dell Vostro           | 25        | 1.3%    |
| Lenovo Legion         | 22        | 1.14%   |
| Acer Swift            | 21        | 1.09%   |
| HP ZBook              | 20        | 1.04%   |
| ASUS Zenbook          | 20        | 1.04%   |
| HP ENVY               | 16        | 0.83%   |
| Unknown               | 16        | 0.83%   |
| ASUS ASUS             | 15        | 0.78%   |
| Acer Nitro            | 13        | 0.68%   |
| HP Notebook           | 10        | 0.52%   |
| HUAWEI HVY-WXX9       | 8         | 0.42%   |
| HP OMEN               | 8         | 0.42%   |
| HP 255                | 8         | 0.42%   |
| HP 15                 | 8         | 0.42%   |
| Fujitsu LIFEBOOK      | 8         | 0.42%   |
| Dell G15              | 8         | 0.42%   |
| Lenovo Yoga           | 7         | 0.36%   |
| Apple MacBookPro11    | 7         | 0.36%   |
| Toshiba PORTEGE       | 6         | 0.31%   |
| Razer Blade           | 6         | 0.31%   |
| Packard Bell EasyNote | 6         | 0.31%   |
| MSI Stealth           | 6         | 0.31%   |
| MSI Prestige          | 6         | 0.31%   |
| HP Stream             | 6         | 0.31%   |
| HP 250                | 6         | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 338       | 17.59%  |
| 2020    | 264       | 13.74%  |
| 2019    | 176       | 9.16%   |
| 2018    | 152       | 7.91%   |
| 2013    | 122       | 6.35%   |
| 2017    | 121       | 6.3%    |
| 2022    | 112       | 5.83%   |
| 2014    | 107       | 5.57%   |
| 2012    | 105       | 5.46%   |
| 2011    | 99        | 5.15%   |
| 2015    | 85        | 4.42%   |
| 2010    | 77        | 4.01%   |
| 2016    | 76        | 3.95%   |
| 2008    | 37        | 1.93%   |
| 2009    | 30        | 1.56%   |
| 2007    | 15        | 0.78%   |
| 2006    | 3         | 0.16%   |
| Unknown | 3         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1922      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1659      | 86%     |
| Enabled  | 270       | 14%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1907      | 99.22%  |
| Yes  | 15        | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 589       | 30.61%  |
| 16.01-24.0  | 417       | 21.67%  |
| 3.01-4.0    | 322       | 16.74%  |
| 8.01-16.0   | 317       | 16.48%  |
| 32.01-64.0  | 156       | 8.11%   |
| 1.01-2.0    | 48        | 2.49%   |
| 64.01-256.0 | 38        | 1.98%   |
| 24.01-32.0  | 26        | 1.35%   |
| 2.01-3.0    | 11        | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 629       | 31.7%   |
| 1.01-2.0   | 563       | 28.38%  |
| 4.01-8.0   | 348       | 17.54%  |
| 3.01-4.0   | 331       | 16.68%  |
| 8.01-16.0  | 82        | 4.13%   |
| 0.51-1.0   | 15        | 0.76%   |
| 16.01-24.0 | 7         | 0.35%   |
| 24.01-32.0 | 4         | 0.2%    |
| 0.01-0.5   | 3         | 0.15%   |
| 32.01-64.0 | 2         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1478      | 76.54%  |
| 2      | 402       | 20.82%  |
| 3      | 32        | 1.66%   |
| 0      | 14        | 0.73%   |
| 4      | 3         | 0.16%   |
| 7      | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1390      | 72.25%  |
| Yes       | 534       | 27.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1428      | 74.18%  |
| No        | 497       | 25.82%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1895      | 98.6%   |
| No        | 27        | 1.4%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1598      | 82.58%  |
| No        | 337       | 17.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 324       | 16.83%  |
| Germany      | 171       | 8.88%   |
| Brazil       | 121       | 6.29%   |
| France       | 107       | 5.56%   |
| India        | 88        | 4.57%   |
| Italy        | 84        | 4.36%   |
| UK           | 71        | 3.69%   |
| Russia       | 70        | 3.64%   |
| Poland       | 54        | 2.81%   |
| Spain        | 49        | 2.55%   |
| Netherlands  | 42        | 2.18%   |
| Canada       | 37        | 1.92%   |
| Turkey       | 32        | 1.66%   |
| Argentina    | 28        | 1.45%   |
| Mexico       | 27        | 1.4%    |
| Sweden       | 26        | 1.35%   |
| Hungary      | 26        | 1.35%   |
| Australia    | 26        | 1.35%   |
| Portugal     | 22        | 1.14%   |
| China        | 21        | 1.09%   |
| Romania      | 20        | 1.04%   |
| Czechia      | 18        | 0.94%   |
| Belgium      | 18        | 0.94%   |
| Austria      | 18        | 0.94%   |
| Finland      | 17        | 0.88%   |
| Indonesia    | 16        | 0.83%   |
| Denmark      | 15        | 0.78%   |
| Taiwan       | 14        | 0.73%   |
| Switzerland  | 14        | 0.73%   |
| South Africa | 13        | 0.68%   |
| Pakistan     | 13        | 0.68%   |
| Iran         | 13        | 0.68%   |
| Egypt        | 13        | 0.68%   |
| Chile        | 13        | 0.68%   |
| Bulgaria     | 13        | 0.68%   |
| Ukraine      | 11        | 0.57%   |
| Greece       | 11        | 0.57%   |
| Colombia     | 11        | 0.57%   |
| Norway       | 10        | 0.52%   |
| Singapore    | 9         | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Moscow         | 22        | 1.12%   |
| Warsaw         | 17        | 0.87%   |
| Milan          | 17        | 0.87%   |
| Paris          | 15        | 0.77%   |
| Budapest       | 15        | 0.77%   |
| Berlin         | 15        | 0.77%   |
| Istanbul       | 13        | 0.66%   |
| Vienna         | 12        | 0.61%   |
| Sao Paulo      | 12        | 0.61%   |
| Madrid         | 12        | 0.61%   |
| Helsinki       | 12        | 0.61%   |
| Sydney         | 10        | 0.51%   |
| St Petersburg  | 10        | 0.51%   |
| Yangon         | 9         | 0.46%   |
| Rome           | 9         | 0.46%   |
| Taipei         | 8         | 0.41%   |
| Singapore      | 8         | 0.41%   |
| Rio de Janeiro | 8         | 0.41%   |
| Tehran         | 7         | 0.36%   |
| Santiago       | 7         | 0.36%   |
| Mumbai         | 7         | 0.36%   |
| Mexico City    | 7         | 0.36%   |
| Jakarta        | 7         | 0.36%   |
| Fortaleza      | 7         | 0.36%   |
| Bucharest      | 7         | 0.36%   |
| Bengaluru      | 7         | 0.36%   |
| Ankara         | 7         | 0.36%   |
| Zagreb         | 6         | 0.31%   |
| Stockholm      | 6         | 0.31%   |
| Sofia          | 6         | 0.31%   |
| Prague         | 6         | 0.31%   |
| Munich         | 6         | 0.31%   |
| London         | 6         | 0.31%   |
| Lisbon         | 6         | 0.31%   |
| Leipzig        | 6         | 0.31%   |
| Curitiba       | 6         | 0.31%   |
| Cairo          | 6         | 0.31%   |
| Buenos Aires   | 6         | 0.31%   |
| Barcelona      | 6         | 0.31%   |
| Athens         | 6         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 411       | 482    | 17.99%  |
| WDC                            | 242       | 270    | 10.59%  |
| Seagate                        | 192       | 215    | 8.4%    |
| Toshiba                        | 148       | 159    | 6.48%   |
| SK hynix                       | 135       | 141    | 5.91%   |
| SanDisk                        | 135       | 147    | 5.91%   |
| Kingston                       | 127       | 137    | 5.56%   |
| Unknown                        | 98        | 106    | 4.29%   |
| Micron Technology              | 82        | 87     | 3.59%   |
| Intel                          | 78        | 101    | 3.41%   |
| HGST                           | 60        | 63     | 2.63%   |
| Crucial                        | 60        | 63     | 2.63%   |
| Hitachi                        | 52        | 58     | 2.28%   |
| KIOXIA                         | 50        | 52     | 2.19%   |
| Phison                         | 37        | 43     | 1.62%   |
| A-DATA Technology              | 33        | 40     | 1.44%   |
| Unknown                        | 30        | 30     | 1.31%   |
| Apple                          | 28        | 34     | 1.23%   |
| Silicon Motion                 | 15        | 18     | 0.66%   |
| Intenso                        | 13        | 15     | 0.57%   |
| China                          | 13        | 14     | 0.57%   |
| SPCC                           | 12        | 12     | 0.53%   |
| Netac                          | 12        | 13     | 0.53%   |
| LITEON                         | 12        | 13     | 0.53%   |
| PNY                            | 11        | 13     | 0.48%   |
| Hewlett-Packard                | 9         | 11     | 0.39%   |
| Transcend                      | 8         | 9      | 0.35%   |
| GOODRAM                        | 8         | 8      | 0.35%   |
| UMIS                           | 6         | 6      | 0.26%   |
| YMTC                           | 5         | 5      | 0.22%   |
| Union Memory (Shenzhen)        | 5         | 5      | 0.22%   |
| Solid State Storage Technology | 5         | 5      | 0.22%   |
| Plextor                        | 5         | 5      | 0.22%   |
| Gigabyte Technology            | 5         | 6      | 0.22%   |
| BIWIN                          | 5         | 5      | 0.22%   |
| Apacer                         | 5         | 5      | 0.22%   |
| ADATA Technology               | 5         | 8      | 0.22%   |
| Teclast                        | 4         | 5      | 0.18%   |
| Patriot                        | 4         | 4      | 0.18%   |
| OCZ                            | 4         | 4      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB       | 38        | 1.6%    |
| Seagate ST1000LM035-1RK172 1TB     | 31        | 1.31%   |
| Unknown                            | 30        | 1.27%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 25        | 1.06%   |
| Toshiba MQ01ABD100 1TB             | 24        | 1.01%   |
| Toshiba MQ04ABF100 1TB             | 23        | 0.97%   |
| Samsung NVMe SSD Drive 256GB       | 22        | 0.93%   |
| SanDisk NVMe SSD Drive 512GB       | 21        | 0.89%   |
| Samsung NVMe SSD Drive 1024GB      | 20        | 0.84%   |
| Kingston SA400S37240G 240GB SSD    | 18        | 0.76%   |
| Seagate ST9500325AS 500GB          | 17        | 0.72%   |
| SanDisk NVMe SSD Drive 256GB       | 17        | 0.72%   |
| SK hynix NVMe SSD Drive 512GB      | 14        | 0.59%   |
| Seagate ST500LT012-1DG142 500GB    | 14        | 0.59%   |
| Micron NVMe SSD Drive 512GB        | 14        | 0.59%   |
| HGST HTS545050A7E680 500GB         | 14        | 0.59%   |
| WDC WD10SPZX-21Z10T0 1TB           | 13        | 0.55%   |
| Samsung SSD 860 EVO 500GB          | 13        | 0.55%   |
| Phison 311CD0512GB                 | 12        | 0.51%   |
| Intel NVMe SSD Drive 512GB         | 12        | 0.51%   |
| Toshiba MQ01ABF050 500GB           | 11        | 0.46%   |
| SK hynix NVMe SSD Drive 256GB      | 11        | 0.46%   |
| Samsung MZALQ512HALU-000L2 512GB   | 11        | 0.46%   |
| Kingston SA400S37480G 480GB SSD    | 11        | 0.46%   |
| Kingston SA400S37120G 120GB SSD    | 11        | 0.46%   |
| HGST HTS721010A9E630 1TB           | 11        | 0.46%   |
| KIOXIA NVMe SSD Drive 256GB        | 10        | 0.42%   |
| Intel SSDPEKNW512G8 512GB          | 10        | 0.42%   |
| HGST HTS541010A9E680 1TB           | 10        | 0.42%   |
| Crucial CT500MX500SSD1 500GB       | 10        | 0.42%   |
| Unknown SD/MMC/MS PRO 2GB          | 9         | 0.38%   |
| SanDisk NVMe SSD Drive 1TB         | 9         | 0.38%   |
| Samsung SSD 980 1TB                | 9         | 0.38%   |
| Samsung SSD 970 EVO Plus 1TB       | 9         | 0.38%   |
| Kingston NVMe SSD Drive 512GB      | 9         | 0.38%   |
| Crucial CT480BX500SSD1 480GB       | 9         | 0.38%   |
| Crucial CT1000MX500SSD1 1TB        | 9         | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 8         | 0.34%   |
| Toshiba NVMe SSD Drive 256GB       | 8         | 0.34%   |
| Toshiba MQ01ABD050 500GB           | 8         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 183       | 204    | 32.33%  |
| WDC                 | 136       | 148    | 24.03%  |
| Toshiba             | 105       | 109    | 18.55%  |
| HGST                | 60        | 63     | 10.6%   |
| Hitachi             | 51        | 57     | 9.01%   |
| Samsung Electronics | 12        | 13     | 2.12%   |
| Unknown             | 9         | 10     | 1.59%   |
| Fujitsu             | 4         | 4      | 0.71%   |
| Apple               | 3         | 3      | 0.53%   |
| USB                 | 1         | 1      | 0.18%   |
| StoreJet            | 1         | 1      | 0.18%   |
| SAGE                | 1         | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 116       | 129    | 18.74%  |
| Kingston            | 78        | 87     | 12.6%   |
| SanDisk             | 60        | 68     | 9.69%   |
| Crucial             | 50        | 53     | 8.08%   |
| WDC                 | 41        | 45     | 6.62%   |
| Micron Technology   | 22        | 23     | 3.55%   |
| SK hynix            | 21        | 24     | 3.39%   |
| A-DATA Technology   | 18        | 20     | 2.91%   |
| Apple               | 13        | 14     | 2.1%    |
| SPCC                | 12        | 12     | 1.94%   |
| Netac               | 12        | 13     | 1.94%   |
| LITEON              | 12        | 13     | 1.94%   |
| China               | 12        | 13     | 1.94%   |
| PNY                 | 10        | 12     | 1.62%   |
| Intenso             | 10        | 12     | 1.62%   |
| Intel               | 10        | 10     | 1.62%   |
| Unknown             | 10        | 10     | 1.62%   |
| Toshiba             | 8         | 8      | 1.29%   |
| GOODRAM             | 8         | 8      | 1.29%   |
| Transcend           | 6         | 7      | 0.97%   |
| Hewlett-Packard     | 6         | 8      | 0.97%   |
| BIWIN               | 5         | 5      | 0.81%   |
| Teclast             | 4         | 5      | 0.65%   |
| Patriot             | 4         | 4      | 0.65%   |
| OCZ                 | 4         | 4      | 0.65%   |
| Lexar               | 4         | 4      | 0.65%   |
| Apacer              | 4         | 4      | 0.65%   |
| Plextor             | 3         | 3      | 0.48%   |
| LITEONIT            | 3         | 3      | 0.48%   |
| Gigabyte Technology | 3         | 3      | 0.48%   |
| FORESEE             | 3         | 3      | 0.48%   |
| Corsair             | 3         | 3      | 0.48%   |
| BHT                 | 3         | 3      | 0.48%   |
| Verbatim            | 2         | 2      | 0.32%   |
| ShiJi               | 2         | 2      | 0.32%   |
| Seagate             | 2         | 2      | 0.32%   |
| Phison              | 2         | 2      | 0.32%   |
| KingSpec            | 2         | 2      | 0.32%   |
| WDC WDB             | 1         | 1      | 0.16%   |
| VISIPRO             | 1         | 1      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 915       | 1090   | 41.76%  |
| SSD     | 581       | 678    | 26.52%  |
| HDD     | 551       | 614    | 25.15%  |
| MMC     | 112       | 122    | 5.11%   |
| Unknown | 32        | 33     | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1038      | 1258   | 48.82%  |
| NVMe | 911       | 1083   | 42.85%  |
| MMC  | 112       | 122    | 5.27%   |
| SAS  | 65        | 74     | 3.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 737       | 863    | 65.39%  |
| 0.51-1.0   | 359       | 394    | 31.85%  |
| 1.01-2.0   | 21        | 23     | 1.86%   |
| 4.01-10.0  | 7         | 9      | 0.62%   |
| 3.01-4.0   | 2         | 2      | 0.18%   |
| 2.01-3.0   | 1         | 1      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 619       | 31.71%  |
| 251-500        | 572       | 29.3%   |
| 501-1000       | 316       | 16.19%  |
| 51-100         | 109       | 5.58%   |
| 1-20           | 100       | 5.12%   |
| 1001-2000      | 96        | 4.92%   |
| 21-50          | 86        | 4.41%   |
| More than 3000 | 22        | 1.13%   |
| 2001-3000      | 17        | 0.87%   |
| Unknown        | 15        | 0.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 797       | 40.31%  |
| 21-50          | 414       | 20.94%  |
| 51-100         | 291       | 14.72%  |
| 101-250        | 235       | 11.89%  |
| 251-500        | 120       | 6.07%   |
| 501-1000       | 69        | 3.49%   |
| 1001-2000      | 24        | 1.21%   |
| Unknown        | 15        | 0.76%   |
| More than 3000 | 8         | 0.4%    |
| 2001-3000      | 4         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 5         | 6      | 5.49%   |
| Seagate ST9500325AS 500GB                | 4         | 4      | 4.4%    |
| Toshiba MQ01ABD100 1TB                   | 3         | 3      | 3.3%    |
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3      | 3.3%    |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 3.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 2         | 2      | 2.2%    |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 2.2%    |
| Seagate ST500LT012-9WS142 500GB          | 2         | 2      | 2.2%    |
| Seagate ST1000LM014-SSHD-8GB             | 2         | 2      | 2.2%    |
| Seagate ST1000LM014-1EJ164 1TB           | 2         | 2      | 2.2%    |
| HGST HTS541075A9E680 752GB               | 2         | 2      | 2.2%    |
| HGST HTS541010A9E680 1TB                 | 2         | 2      | 2.2%    |
| WDC WDS480G2G0A-00JH30 480GB SSD         | 1         | 1      | 1.1%    |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 1         | 1      | 1.1%    |
| WDC WD7500BPKT-22PK4T0 752GB             | 1         | 1      | 1.1%    |
| WDC WD5000LPVX-22V0TT0 500GB             | 1         | 1      | 1.1%    |
| WDC WD5000LPCX-60VHAT0 500GB             | 1         | 1      | 1.1%    |
| WDC WD5000BEVT-00A0RT0 500GB             | 1         | 1      | 1.1%    |
| WDC WD3200BPVT-16JJ5T0 320GB             | 1         | 1      | 1.1%    |
| WDC WD3200BEKT-60V5T1 320GB              | 1         | 1      | 1.1%    |
| WDC WD2500BEKT-75A25T0 250GB             | 1         | 2      | 1.1%    |
| WDC WD10SPZX-24Z10 1TB                   | 1         | 1      | 1.1%    |
| WDC WD10SPZX-21Z10T0 1TB                 | 1         | 2      | 1.1%    |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 1.1%    |
| WDC WD10JPVX-60JC3T0 1TB                 | 1         | 1      | 1.1%    |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.1%    |
| WDC WD10JPVX-00JC3T0 1TB                 | 1         | 1      | 1.1%    |
| WDC WD10JPCX-24UE4T0 1TB                 | 1         | 1      | 1.1%    |
| WDC PC SA530 SDATN8Y-256G-1006 256GB SSD | 1         | 1      | 1.1%    |
| VISIPRO SSD 256GB                        | 1         | 1      | 1.1%    |
| Toshiba MQ01ABF032 320GB                 | 1         | 1      | 1.1%    |
| Toshiba MQ01ABD050 500GB                 | 1         | 1      | 1.1%    |
| Toshiba MK6465GSX 640GB                  | 1         | 1      | 1.1%    |
| Toshiba MK5065GSXN 500GB                 | 1         | 1      | 1.1%    |
| Toshiba MK5065GSX 500GB                  | 1         | 1      | 1.1%    |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 1.1%    |
| SK hynix SC210 2.5 7MM 128GB SSD         | 1         | 1      | 1.1%    |
| SK hynix HFS256GD9TNG-62A0A 256GB        | 1         | 1      | 1.1%    |
| SK hynix HFS128G3AMNM-1010A 128GB SSD    | 1         | 1      | 1.1%    |
| SK hynix HFS128G32MND-2200A 128GB SSD    | 1         | 1      | 1.1%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 24     | 25.27%  |
| WDC                 | 19        | 21     | 20.88%  |
| HGST                | 11        | 11     | 12.09%  |
| Toshiba             | 9         | 9      | 9.89%   |
| SK hynix            | 7         | 7      | 7.69%   |
| Hitachi             | 6         | 6      | 6.59%   |
| Micron Technology   | 4         | 4      | 4.4%    |
| A-DATA Technology   | 3         | 3      | 3.3%    |
| Samsung Electronics | 2         | 2      | 2.2%    |
| Intel               | 2         | 2      | 2.2%    |
| VISIPRO             | 1         | 1      | 1.1%    |
| SanDisk             | 1         | 1      | 1.1%    |
| LITEON              | 1         | 1      | 1.1%    |
| Kingston            | 1         | 2      | 1.1%    |
| Intenso             | 1         | 1      | 1.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 24     | 35.94%  |
| WDC                 | 14        | 16     | 21.88%  |
| HGST                | 11        | 11     | 17.19%  |
| Toshiba             | 8         | 8      | 12.5%   |
| Hitachi             | 6         | 6      | 9.38%   |
| Samsung Electronics | 2         | 2      | 3.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 64        | 67     | 70.33%  |
| SSD  | 20        | 21     | 21.98%  |
| NVMe | 7         | 7      | 7.69%   |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1144      | 1530   | 57.49%  |
| Works    | 756       | 912    | 37.99%  |
| Malfunc  | 90        | 95     | 4.52%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1239      | 52.08%  |
| Samsung Electronics            | 306       | 12.86%  |
| AMD                            | 224       | 9.42%   |
| SanDisk                        | 133       | 5.59%   |
| SK hynix                       | 108       | 4.54%   |
| Micron Technology              | 59        | 2.48%   |
| Kingston Technology Company    | 52        | 2.19%   |
| Toshiba America Info Systems   | 44        | 1.85%   |
| KIOXIA                         | 42        | 1.77%   |
| Phison Electronics             | 39        | 1.64%   |
| Silicon Motion                 | 22        | 0.92%   |
| ADATA Technology               | 19        | 0.8%    |
| Micron/Crucial Technology      | 14        | 0.59%   |
| Union Memory (Shenzhen)        | 11        | 0.46%   |
| Solid State Storage Technology | 11        | 0.46%   |
| Apple                          | 11        | 0.46%   |
| Nvidia                         | 9         | 0.38%   |
| Yangtze Memory Technologies    | 6         | 0.25%   |
| Marvell Technology Group       | 6         | 0.25%   |
| Seagate Technology             | 4         | 0.17%   |
| Realtek Semiconductor          | 4         | 0.17%   |
| MAXIO Technology (Hangzhou)    | 3         | 0.13%   |
| Lite-On Technology             | 3         | 0.13%   |
| Lenovo                         | 3         | 0.13%   |
| Shenzhen Longsys Electronics   | 2         | 0.08%   |
| ASMedia Technology             | 2         | 0.08%   |
| Zhaoxin                        | 1         | 0.04%   |
| Unknown                        | 1         | 0.04%   |
| Transcend                      | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 203       | 8.1%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 155       | 6.19%   |
| Intel Volume Management Device NVMe RAID Controller                            | 141       | 5.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 116       | 4.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 112       | 4.47%   |
| Samsung NVMe SSD Controller 980                                                | 106       | 4.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 103       | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 71        | 2.83%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 66        | 2.63%   |
| Micron Non-Volatile memory controller                                          | 59        | 2.35%   |
| SK hynix Gold P31 SSD                                                          | 57        | 2.27%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 55        | 2.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 55        | 2.19%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 47        | 1.88%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 44        | 1.76%   |
| Intel Tiger Lake-LP SATA Controller                                            | 39        | 1.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 39        | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 38        | 1.52%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 35        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 35        | 1.4%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 34        | 1.36%   |
| Intel Comet Lake SATA AHCI Controller                                          | 31        | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 29        | 1.16%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 28        | 1.12%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 27        | 1.08%   |
| SanDisk Non-Volatile memory controller                                         | 27        | 1.08%   |
| Intel Non-Volatile memory controller                                           | 27        | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 27        | 1.08%   |
| Phison PS5013 E13 NVMe Controller                                              | 25        | 1%      |
| Intel SSD 660P Series                                                          | 25        | 1%      |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 25        | 1%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 21        | 0.84%   |
| Kingston Company Company Non-Volatile memory controller                        | 20        | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 20        | 0.8%    |
| SK hynix Non-Volatile memory controller                                        | 19        | 0.76%   |
| SK hynix BC511                                                                 | 19        | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 19        | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 18        | 0.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 17        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1209      | 49.71%  |
| NVMe | 908       | 37.34%  |
| RAID | 256       | 10.53%  |
| IDE  | 59        | 2.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1542      | 80.23%  |
| AMD          | 379       | 19.72%  |
| CentaurHauls | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 54        | 2.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 53        | 2.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 37        | 1.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 1.72%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 28        | 1.46%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 28        | 1.46%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 28        | 1.46%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 27        | 1.4%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 1.35%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 25        | 1.3%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 23        | 1.2%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 23        | 1.2%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 22        | 1.14%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 1.14%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 22        | 1.14%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 21        | 1.09%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 20        | 1.04%   |
| Intel 12th Gen Core i7-12700H                 | 20        | 1.04%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 19        | 0.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 19        | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 0.94%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 18        | 0.94%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 18        | 0.94%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 17        | 0.88%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 16        | 0.83%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 16        | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 0.73%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 14        | 0.73%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 13        | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 13        | 0.68%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 13        | 0.68%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 12        | 0.62%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 12        | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.57%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 11        | 0.57%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz       | 11        | 0.57%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 11        | 0.57%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 11        | 0.57%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 10        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 467       | 24.3%   |
| Intel Core i7                  | 380       | 19.77%  |
| Other                          | 297       | 15.45%  |
| Intel Core i3                  | 140       | 7.28%   |
| Intel Celeron                  | 116       | 6.04%   |
| AMD Ryzen 5                    | 111       | 5.78%   |
| AMD Ryzen 7                    | 97        | 5.05%   |
| Intel Core 2 Duo               | 48        | 2.5%    |
| Intel Pentium                  | 42        | 2.19%   |
| AMD A6                         | 20        | 1.04%   |
| AMD Ryzen 9                    | 18        | 0.94%   |
| Intel Atom                     | 16        | 0.83%   |
| AMD Ryzen 3                    | 16        | 0.83%   |
| AMD A4                         | 15        | 0.78%   |
| AMD A10                        | 14        | 0.73%   |
| AMD Ryzen 7 PRO                | 13        | 0.68%   |
| AMD A8                         | 13        | 0.68%   |
| Intel Pentium Dual-Core        | 9         | 0.47%   |
| Intel Core i9                  | 9         | 0.47%   |
| AMD E2                         | 9         | 0.47%   |
| Intel Pentium Dual             | 8         | 0.42%   |
| AMD Athlon                     | 7         | 0.36%   |
| AMD Ryzen 5 PRO                | 5         | 0.26%   |
| Intel Xeon                     | 4         | 0.21%   |
| Intel Pentium Silver           | 4         | 0.21%   |
| Intel Genuine                  | 4         | 0.21%   |
| AMD E                          | 4         | 0.21%   |
| Intel Core m3                  | 3         | 0.16%   |
| Intel Core 2                   | 3         | 0.16%   |
| AMD Athlon II                  | 3         | 0.16%   |
| Intel Pentium Gold             | 2         | 0.1%    |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.1%    |
| AMD Phenom II                  | 2         | 0.1%    |
| AMD FX                         | 2         | 0.1%    |
| AMD E1                         | 2         | 0.1%    |
| AMD Athlon 64 X2               | 2         | 0.1%    |
| AMD A12                        | 2         | 0.1%    |
| Intel Core m5                  | 1         | 0.05%   |
| Intel Core M                   | 1         | 0.05%   |
| Intel Core 2 Solo              | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 831       | 43.21%  |
| 4      | 671       | 34.89%  |
| 8      | 173       | 9%      |
| 6      | 163       | 8.48%   |
| 14     | 43        | 2.24%   |
| 12     | 14        | 0.73%   |
| 1      | 14        | 0.73%   |
| 10     | 11        | 0.57%   |
| 16     | 1         | 0.05%   |
| 5      | 1         | 0.05%   |
| 3      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1922      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1539      | 80.03%  |
| 1      | 384       | 19.97%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1921      | 99.95%  |
| Unknown        | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 998       | 51.28%  |
| 0x806c1    | 114       | 5.86%   |
| 0x806ec    | 61        | 3.13%   |
| 0x806ea    | 60        | 3.08%   |
| 0x306a9    | 51        | 2.62%   |
| 0x0a50000c | 49        | 2.52%   |
| 0x906a3    | 44        | 2.26%   |
| 0x906ea    | 33        | 1.7%    |
| 0x40651    | 31        | 1.59%   |
| 0x206a7    | 30        | 1.54%   |
| 0x806d1    | 29        | 1.49%   |
| 0x406e3    | 28        | 1.44%   |
| 0x08608103 | 27        | 1.39%   |
| 0xa0652    | 26        | 1.34%   |
| 0x306d4    | 26        | 1.34%   |
| 0x806e9    | 25        | 1.28%   |
| 0x706e5    | 25        | 1.28%   |
| 0x08108109 | 22        | 1.13%   |
| 0x706a8    | 20        | 1.03%   |
| 0x306c3    | 19        | 0.98%   |
| 0x08600106 | 17        | 0.87%   |
| 0x08600104 | 14        | 0.72%   |
| 0x20655    | 12        | 0.62%   |
| 0x806eb    | 10        | 0.51%   |
| 0x06006705 | 10        | 0.51%   |
| 0x906e9    | 9         | 0.46%   |
| 0x906ed    | 8         | 0.41%   |
| 0x906a4    | 8         | 0.41%   |
| 0x706a1    | 8         | 0.41%   |
| 0x506c9    | 8         | 0.41%   |
| 0x1067a    | 8         | 0.41%   |
| 0x08108102 | 8         | 0.41%   |
| 0x06001119 | 8         | 0.41%   |
| 0x6fd      | 7         | 0.36%   |
| 0x20652    | 6         | 0.31%   |
| 0x506e3    | 5         | 0.26%   |
| 0x506ca    | 5         | 0.26%   |
| 0x30678    | 5         | 0.26%   |
| 0x0a50000b | 5         | 0.26%   |
| 0x0a404101 | 5         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 375       | 19.5%   |
| TigerLake        | 170       | 8.84%   |
| Haswell          | 131       | 6.81%   |
| IvyBridge        | 114       | 5.93%   |
| SandyBridge      | 105       | 5.46%   |
| Unknown          | 104       | 5.41%   |
| Skylake          | 90        | 4.68%   |
| Icelake          | 82        | 4.26%   |
| Zen 3            | 79        | 4.11%   |
| Broadwell        | 69        | 3.59%   |
| Zen+             | 60        | 3.12%   |
| Westmere         | 60        | 3.12%   |
| Zen 2            | 57        | 2.96%   |
| Silvermont       | 56        | 2.91%   |
| Alderlake Hybrid | 52        | 2.7%    |
| Penryn           | 50        | 2.6%    |
| CometLake        | 47        | 2.44%   |
| Goldmont plus    | 44        | 2.29%   |
| Excavator        | 39        | 2.03%   |
| Goldmont         | 27        | 1.4%    |
| Core             | 25        | 1.3%    |
| Puma             | 14        | 0.73%   |
| Piledriver       | 14        | 0.73%   |
| Zen              | 9         | 0.47%   |
| K10              | 9         | 0.47%   |
| Bobcat           | 9         | 0.47%   |
| K10 Llano        | 7         | 0.36%   |
| Steamroller      | 5         | 0.26%   |
| Nehalem          | 5         | 0.26%   |
| K8 Hammer        | 4         | 0.21%   |
| K8 & K10 hybrid  | 4         | 0.21%   |
| Jaguar           | 4         | 0.21%   |
| Tremont          | 2         | 0.1%    |
| Bonnell          | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1442      | 58.59%  |
| Nvidia  | 544       | 22.1%   |
| AMD     | 474       | 19.26%  |
| Zhaoxin | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 159       | 6.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 108       | 4.31%   |
| Intel UHD Graphics 620                                                                   | 98        | 3.92%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 96        | 3.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 73        | 2.92%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 64        | 2.56%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 63        | 2.52%   |
| AMD Cezanne                                                                              | 63        | 2.52%   |
| Intel HD Graphics 5500                                                                   | 60        | 2.4%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 58        | 2.32%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 58        | 2.32%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 57        | 2.28%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 57        | 2.28%   |
| Intel HD Graphics 620                                                                    | 55        | 2.2%    |
| AMD Lucienne                                                                             | 55        | 2.2%    |
| AMD Renoir                                                                               | 53        | 2.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 47        | 1.88%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 45        | 1.8%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 42        | 1.68%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 40        | 1.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 39        | 1.56%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 38        | 1.52%   |
| Intel Core Processor Integrated Graphics Controller                                      | 36        | 1.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 31        | 1.24%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 31        | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 29        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 1.08%   |
| Intel HD Graphics 500                                                                    | 24        | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 23        | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 0.8%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 20        | 0.8%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 20        | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 0.72%   |
| Nvidia GP108M [GeForce MX150]                                                            | 18        | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 0.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 0.6%    |
| Intel HD Graphics 630                                                                    | 15        | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 14        | 0.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 14        | 0.56%   |
| Nvidia TU117M                                                                            | 13        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 946       | 49.22%  |
| Intel + Nvidia | 411       | 21.38%  |
| 1 x AMD        | 324       | 16.86%  |
| 1 x Nvidia     | 83        | 4.32%   |
| Intel + AMD    | 77        | 4.01%   |
| AMD + Nvidia   | 49        | 2.55%   |
| 2 x AMD        | 24        | 1.25%   |
| Other          | 6         | 0.31%   |
| 2 x Nvidia     | 1         | 0.05%   |
| 1 x Zhaoxin    | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1577      | 81.71%  |
| Proprietary | 321       | 16.63%  |
| Unknown     | 32        | 1.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1575      | 81.48%  |
| 1.01-2.0   | 121       | 6.26%   |
| 0.01-0.5   | 110       | 5.69%   |
| 0.51-1.0   | 54        | 2.79%   |
| 3.01-4.0   | 42        | 2.17%   |
| 5.01-6.0   | 16        | 0.83%   |
| 7.01-8.0   | 10        | 0.52%   |
| 2.01-3.0   | 3         | 0.16%   |
| 8.01-16.0  | 2         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 434       | 19.2%   |
| BOE                     | 385       | 17.04%  |
| Chimei Innolux          | 289       | 12.79%  |
| LG Display              | 286       | 12.65%  |
| Samsung Electronics     | 219       | 9.69%   |
| Sharp                   | 76        | 3.36%   |
| Dell                    | 60        | 2.65%   |
| Goldstar                | 58        | 2.57%   |
| Apple                   | 47        | 2.08%   |
| PANDA                   | 43        | 1.9%    |
| Lenovo                  | 38        | 1.68%   |
| Chi Mei Optoelectronics | 31        | 1.37%   |
| Hewlett-Packard         | 28        | 1.24%   |
| Philips                 | 23        | 1.02%   |
| Acer                    | 23        | 1.02%   |
| CSO                     | 20        | 0.88%   |
| BenQ                    | 19        | 0.84%   |
| InfoVision              | 17        | 0.75%   |
| AOC                     | 14        | 0.62%   |
| Sony                    | 11        | 0.49%   |
| Ancor Communications    | 10        | 0.44%   |
| LG Philips              | 8         | 0.35%   |
| Iiyama                  | 8         | 0.35%   |
| ASUSTek Computer        | 8         | 0.35%   |
| CPT                     | 7         | 0.31%   |
| ViewSonic               | 6         | 0.27%   |
| HannStar                | 6         | 0.27%   |
| TMX                     | 5         | 0.22%   |
| Toshiba                 | 4         | 0.18%   |
| STA                     | 3         | 0.13%   |
| SLD                     | 3         | 0.13%   |
| SGT                     | 3         | 0.13%   |
| Pixio                   | 3         | 0.13%   |
| JDI                     | 3         | 0.13%   |
| Fujitsu Siemens         | 3         | 0.13%   |
| Vizio                   | 2         | 0.09%   |
| Unknown (XXX)           | 2         | 0.09%   |
| Sceptre Tech            | 2         | 0.09%   |
| Panasonic               | 2         | 0.09%   |
| OEM                     | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.88%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 19        | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 15        | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 14        | 0.61%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 14        | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 12        | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.53%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 10        | 0.44%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.44%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 10        | 0.44%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 9         | 0.39%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 9         | 0.39%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 8         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 8         | 0.35%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 8         | 0.35%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 8         | 0.35%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 8         | 0.35%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 7         | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 7         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 7         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 7         | 0.31%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 7         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 7         | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 7         | 0.31%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 7         | 0.31%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 7         | 0.31%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 7         | 0.31%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch           | 7         | 0.31%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 7         | 0.31%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 6         | 0.26%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 6         | 0.26%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 6         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.26%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 6         | 0.26%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 6         | 0.26%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.26%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 6         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 973       | 46.11%  |
| 1366x768 (WXGA)    | 556       | 26.35%  |
| 3840x2160 (4K)     | 99        | 4.69%   |
| 1600x900 (HD+)     | 93        | 4.41%   |
| 2560x1440 (QHD)    | 66        | 3.13%   |
| 1280x800 (WXGA)    | 45        | 2.13%   |
| 1920x1200 (WUXGA)  | 42        | 1.99%   |
| 2560x1600          | 37        | 1.75%   |
| 1440x900 (WXGA+)   | 29        | 1.37%   |
| 2880x1800          | 27        | 1.28%   |
| 3840x2400          | 19        | 0.9%    |
| 2560x1080          | 17        | 0.81%   |
| 2160x1440          | 14        | 0.66%   |
| 1680x1050 (WSXGA+) | 14        | 0.66%   |
| 3440x1440          | 12        | 0.57%   |
| 1280x1024 (SXGA)   | 10        | 0.47%   |
| 1360x768           | 6         | 0.28%   |
| 3200x1800 (QHD+)   | 5         | 0.24%   |
| 3072x1920          | 5         | 0.24%   |
| 2256x1504          | 5         | 0.24%   |
| 3840x1080          | 4         | 0.19%   |
| 3456x2160          | 4         | 0.19%   |
| 3200x2000          | 3         | 0.14%   |
| 3000x2000          | 3         | 0.14%   |
| 2520x1680          | 3         | 0.14%   |
| 1920x540           | 3         | 0.14%   |
| Unknown            | 2         | 0.09%   |
| 6400x2160          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 2944x1080          | 1         | 0.05%   |
| 2304x1440          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 2240x1400          | 1         | 0.05%   |
| 2048x1152          | 1         | 0.05%   |
| 1920x515           | 1         | 0.05%   |
| 1920x1280          | 1         | 0.05%   |
| 1600x1200          | 1         | 0.05%   |
| 1400x1050          | 1         | 0.05%   |
| 1280x720 (HD)      | 1         | 0.05%   |
| 1024x768 (XGA)     | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 951       | 42.08%  |
| 13      | 316       | 13.98%  |
| 14      | 297       | 13.14%  |
| 17      | 151       | 6.68%   |
| 27      | 75        | 3.32%   |
| 24      | 71        | 3.14%   |
| 21      | 58        | 2.57%   |
| 23      | 53        | 2.35%   |
| 16      | 47        | 2.08%   |
| 12      | 39        | 1.73%   |
| 11      | 37        | 1.64%   |
| 34      | 27        | 1.19%   |
| 31      | 20        | 0.88%   |
| 18      | 15        | 0.66%   |
| Unknown | 15        | 0.66%   |
| 22      | 11        | 0.49%   |
| 19      | 10        | 0.44%   |
| 84      | 8         | 0.35%   |
| 54      | 7         | 0.31%   |
| 26      | 6         | 0.27%   |
| 20      | 6         | 0.27%   |
| 10      | 6         | 0.27%   |
| 72      | 5         | 0.22%   |
| 65      | 3         | 0.13%   |
| 43      | 3         | 0.13%   |
| 32      | 3         | 0.13%   |
| 49      | 2         | 0.09%   |
| 47      | 2         | 0.09%   |
| 46      | 2         | 0.09%   |
| 29      | 2         | 0.09%   |
| 28      | 2         | 0.09%   |
| 74      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 40      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |
| 35      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 25      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1415      | 62.97%  |
| 201-300     | 239       | 10.64%  |
| 351-400     | 188       | 8.37%   |
| 501-600     | 187       | 8.32%   |
| 401-500     | 99        | 4.41%   |
| 601-700     | 33        | 1.47%   |
| 701-800     | 31        | 1.38%   |
| 1001-1500   | 19        | 0.85%   |
| Unknown     | 15        | 0.67%   |
| 1501-2000   | 14        | 0.62%   |
| 801-900     | 3         | 0.13%   |
| 901-1000    | 3         | 0.13%   |
| 101-200     | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1659      | 84.04%  |
| 16/10   | 231       | 11.7%   |
| 21/9    | 30        | 1.52%   |
| 3/2     | 29        | 1.47%   |
| 4/3     | 7         | 0.35%   |
| 5/4     | 5         | 0.25%   |
| Unknown | 5         | 0.25%   |
| 32/9    | 3         | 0.15%   |
| 6/5     | 2         | 0.1%    |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 954       | 42.34%  |
| 81-90          | 493       | 21.88%  |
| 201-250        | 151       | 6.7%    |
| 121-130        | 133       | 5.9%    |
| 71-80          | 121       | 5.37%   |
| 301-350        | 82        | 3.64%   |
| 351-500        | 51        | 2.26%   |
| 111-120        | 38        | 1.69%   |
| 51-60          | 37        | 1.64%   |
| 61-70          | 36        | 1.6%    |
| 151-200        | 36        | 1.6%    |
| More than 1000 | 25        | 1.11%   |
| 251-300        | 22        | 0.98%   |
| 141-150        | 16        | 0.71%   |
| 131-140        | 15        | 0.67%   |
| Unknown        | 15        | 0.67%   |
| 501-1000       | 14        | 0.62%   |
| 91-100         | 7         | 0.31%   |
| 41-50          | 6         | 0.27%   |
| 1-40           | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 952       | 42.96%  |
| 101-120       | 618       | 27.89%  |
| 51-100        | 318       | 14.35%  |
| 161-240       | 196       | 8.84%   |
| More than 240 | 94        | 4.24%   |
| 1-50          | 23        | 1.04%   |
| Unknown       | 15        | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1518      | 78.13%  |
| 2     | 339       | 17.45%  |
| 3     | 42        | 2.16%   |
| 0     | 41        | 2.11%   |
| 4     | 3         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1056      | 35.39%  |
| Intel                                  | 1047      | 35.09%  |
| Qualcomm Atheros                       | 360       | 12.06%  |
| Broadcom                               | 147       | 4.93%   |
| MediaTek                               | 65        | 2.18%   |
| Broadcom Limited                       | 44        | 1.47%   |
| Ralink                                 | 23        | 0.77%   |
| ASIX Electronics                       | 22        | 0.74%   |
| TP-Link                                | 21        | 0.7%    |
| Marvell Technology Group               | 17        | 0.57%   |
| DisplayLink                            | 16        | 0.54%   |
| Lenovo                                 | 13        | 0.44%   |
| Samsung Electronics                    | 12        | 0.4%    |
| Ralink Technology                      | 12        | 0.4%    |
| Dell                                   | 12        | 0.4%    |
| Xiaomi                                 | 9         | 0.3%    |
| NetGear                                | 9         | 0.3%    |
| Qualcomm                               | 8         | 0.27%   |
| Sierra Wireless                        | 7         | 0.23%   |
| ICS Advent                             | 7         | 0.23%   |
| Hewlett-Packard                        | 7         | 0.23%   |
| OPPO Electronics                       | 6         | 0.2%    |
| JMicron Technology                     | 6         | 0.2%    |
| Motorola PCS                           | 5         | 0.17%   |
| Google                                 | 5         | 0.17%   |
| Apple                                  | 5         | 0.17%   |
| Qualcomm Atheros Communications        | 4         | 0.13%   |
| Nvidia                                 | 4         | 0.13%   |
| Huawei Technologies                    | 4         | 0.13%   |
| U-Blox                                 | 3         | 0.1%    |
| Toshiba                                | 3         | 0.1%    |
| Ericsson Business Mobile Networks      | 3         | 0.1%    |
| Edimax Technology                      | 3         | 0.1%    |
| D-Link                                 | 2         | 0.07%   |
| Arduino SA                             | 2         | 0.07%   |
| U.S. Robotics                          | 1         | 0.03%   |
| TRENDnet                               | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Sigma Designs                          | 1         | 0.03%   |
| SEGGER                                 | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 580       | 16.41%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 157       | 4.44%   |
| Intel Wi-Fi 6 AX201                                               | 133       | 3.76%   |
| Intel Wi-Fi 6 AX200                                               | 106       | 3%      |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 85        | 2.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 84        | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 77        | 2.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 73        | 2.07%   |
| Intel Wireless 8265 / 8275                                        | 71        | 2.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 69        | 1.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 64        | 1.81%   |
| Intel Wireless 7265                                               | 57        | 1.61%   |
| Intel Wireless 7260                                               | 51        | 1.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 50        | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 48        | 1.36%   |
| Intel Wireless 8260                                               | 47        | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 46        | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 42        | 1.19%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 42        | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 41        | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 40        | 1.13%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 33        | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 33        | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 32        | 0.91%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 28        | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 28        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 28        | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 26        | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24        | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 24        | 0.68%   |
| Intel Wireless 3160                                               | 23        | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 0.65%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 23        | 0.65%   |
| Intel Centrino Wireless-N 2230                                    | 22        | 0.62%   |
| Intel Wireless 3165                                               | 21        | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 21        | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 20        | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 20        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1000      | 50.66%  |
| Realtek Semiconductor             | 359       | 18.19%  |
| Qualcomm Atheros                  | 311       | 15.75%  |
| Broadcom                          | 115       | 5.83%   |
| MediaTek                          | 58        | 2.94%   |
| Broadcom Limited                  | 31        | 1.57%   |
| Ralink                            | 23        | 1.17%   |
| TP-Link                           | 18        | 0.91%   |
| Ralink Technology                 | 12        | 0.61%   |
| NetGear                           | 8         | 0.41%   |
| Dell                              | 8         | 0.41%   |
| Sierra Wireless                   | 7         | 0.35%   |
| Qualcomm                          | 5         | 0.25%   |
| Qualcomm Atheros Communications   | 4         | 0.2%    |
| Hewlett-Packard                   | 4         | 0.2%    |
| Edimax Technology                 | 3         | 0.15%   |
| D-Link                            | 2         | 0.1%    |
| U.S. Robotics                     | 1         | 0.05%   |
| TRENDnet                          | 1         | 0.05%   |
| Quectel Wireless Solutions        | 1         | 0.05%   |
| IMC Networks                      | 1         | 0.05%   |
| FIBOCOM                           | 1         | 0.05%   |
| Ericsson Business Mobile Networks | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 133       | 6.69%   |
| Intel Wi-Fi 6 AX200                                            | 106       | 5.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 85        | 4.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 77        | 3.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 73        | 3.67%   |
| Intel Wireless 8265 / 8275                                     | 71        | 3.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 69        | 3.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 64        | 3.22%   |
| Intel Wireless 7265                                            | 57        | 2.87%   |
| Intel Wireless 7260                                            | 51        | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 50        | 2.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 48        | 2.41%   |
| Intel Wireless 8260                                            | 47        | 2.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 46        | 2.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 42        | 2.11%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 41        | 2.06%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 40        | 2.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 33        | 1.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 33        | 1.66%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 32        | 1.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 28        | 1.41%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 28        | 1.41%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 28        | 1.41%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 26        | 1.31%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 24        | 1.21%   |
| Intel Wireless 3160                                            | 23        | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 23        | 1.16%   |
| Intel Centrino Wireless-N 2230                                 | 22        | 1.11%   |
| Intel Wireless 3165                                            | 21        | 1.06%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 20        | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 20        | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 17        | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 17        | 0.85%   |
| Intel Wireless-AC 9260                                         | 17        | 0.85%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 15        | 0.75%   |
| Realtek Realtek Network controller                             | 15        | 0.75%   |
| Realtek 802.11n WLAN Adapter                                   | 15        | 0.75%   |
| Broadcom BCM43142 802.11b/g/n                                  | 14        | 0.7%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 871       | 58.03%  |
| Intel                                  | 327       | 21.79%  |
| Qualcomm Atheros                       | 83        | 5.53%   |
| Broadcom                               | 60        | 4%      |
| ASIX Electronics                       | 22        | 1.47%   |
| Marvell Technology Group               | 17        | 1.13%   |
| DisplayLink                            | 16        | 1.07%   |
| Broadcom Limited                       | 14        | 0.93%   |
| Lenovo                                 | 13        | 0.87%   |
| Samsung Electronics                    | 12        | 0.8%    |
| Xiaomi                                 | 9         | 0.6%    |
| MediaTek                               | 7         | 0.47%   |
| ICS Advent                             | 7         | 0.47%   |
| OPPO Electronics                       | 6         | 0.4%    |
| JMicron Technology                     | 6         | 0.4%    |
| Google                                 | 5         | 0.33%   |
| Apple                                  | 5         | 0.33%   |
| Nvidia                                 | 4         | 0.27%   |
| TP-Link                                | 3         | 0.2%    |
| Qualcomm                               | 3         | 0.2%    |
| Motorola PCS                           | 3         | 0.2%    |
| Huawei Technologies                    | 3         | 0.2%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.07%   |
| NetGear                                | 1         | 0.07%   |
| HMD Global                             | 1         | 0.07%   |
| Hewlett-Packard                        | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 580       | 38.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 157       | 10.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 84        | 5.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 42        | 2.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 2.43%   |
| Realtek RTL8125 2.5GbE Controller                                 | 24        | 1.58%   |
| Intel Ethernet Connection I219-LM                                 | 23        | 1.51%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 1.38%   |
| Intel 82577LM Gigabit Network Connection                          | 21        | 1.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 19        | 1.25%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 18        | 1.18%   |
| Realtek Killer E3000 2.5GbE Controller                            | 16        | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 1.05%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 13        | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                             | 13        | 0.86%   |
| Intel Ethernet Connection (13) I219-LM                            | 13        | 0.86%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.79%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 11        | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 11        | 0.72%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 10        | 0.66%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.66%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.59%   |
| Intel 82567LM Gigabit Network Connection                          | 9         | 0.59%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 9         | 0.59%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 8         | 0.53%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.53%   |
| Intel Ethernet Connection (6) I219-LM                             | 8         | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.53%   |
| DisplayLink Dell Universal Dock D6000                             | 8         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 7         | 0.46%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 7         | 0.46%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.39%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.39%   |
| OPPO RMX2117                                                      | 6         | 0.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1896      | 56.72%  |
| Ethernet | 1423      | 42.57%  |
| Modem    | 21        | 0.63%   |
| Unknown  | 3         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1594      | 78.75%  |
| Ethernet | 430       | 21.25%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1259      | 65.5%   |
| 1     | 617       | 32.1%   |
| 0     | 35        | 1.82%   |
| 3     | 11        | 0.57%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1386      | 71.63%  |
| Yes  | 549       | 28.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 864       | 53.76%  |
| Realtek Semiconductor           | 203       | 12.63%  |
| Qualcomm Atheros Communications | 124       | 7.72%   |
| IMC Networks                    | 87        | 5.41%   |
| Lite-On Technology              | 68        | 4.23%   |
| Foxconn / Hon Hai               | 57        | 3.55%   |
| Broadcom                        | 47        | 2.92%   |
| Apple                           | 33        | 2.05%   |
| Realtek                         | 23        | 1.43%   |
| Dell                            | 23        | 1.43%   |
| Cambridge Silicon Radio         | 18        | 1.12%   |
| Ralink                          | 17        | 1.06%   |
| Toshiba                         | 15        | 0.93%   |
| Hewlett-Packard                 | 11        | 0.68%   |
| Ralink Technology               | 4         | 0.25%   |
| Foxconn International           | 3         | 0.19%   |
| ASUSTek Computer                | 2         | 0.12%   |
| Askey Computer                  | 2         | 0.12%   |
| Alps Electric                   | 2         | 0.12%   |
| USI                             | 1         | 0.06%   |
| Opticis                         | 1         | 0.06%   |
| Mobile Action Technology        | 1         | 0.06%   |
| Integrated System Solution      | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 276       | 17.16%  |
| Intel AX201 Bluetooth                               | 225       | 13.99%  |
| Realtek Bluetooth Radio                             | 150       | 9.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 117       | 7.28%   |
| Intel AX200 Bluetooth                               | 105       | 6.53%   |
| Qualcomm Atheros  Bluetooth Device                  | 60        | 3.73%   |
| Intel Bluetooth Device                              | 54        | 3.36%   |
| Realtek  Bluetooth 4.2 Adapter                      | 42        | 2.61%   |
| Intel AX210 Bluetooth                               | 31        | 1.93%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 29        | 1.8%    |
| IMC Networks Bluetooth Radio                        | 29        | 1.8%    |
| IMC Networks Wireless_Device                        | 28        | 1.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 27        | 1.68%   |
| Realtek Bluetooth Radio                             | 23        | 1.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 22        | 1.37%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 1.31%   |
| Foxconn / Hon Hai Bluetooth Device                  | 19        | 1.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 1.12%   |
| Apple Bluetooth Host Controller                     | 18        | 1.12%   |
| Ralink RT3290 Bluetooth                             | 17        | 1.06%   |
| IMC Networks Bluetooth Device                       | 17        | 1.06%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 13        | 0.81%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 13        | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 0.75%   |
| Lite-On Bluetooth Device                            | 12        | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 12        | 0.75%   |
| Dell DW375 Bluetooth Module                         | 8         | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 7         | 0.44%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.44%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 0.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.44%   |
| HP Broadcom 2070 Bluetooth Combo                    | 7         | 0.44%   |
| Toshiba Bluetooth Device                            | 6         | 0.37%   |
| Lite-On Wireless_Device                             | 6         | 0.37%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.37%   |
| Dell Wireless 365 Bluetooth                         | 6         | 0.37%   |
| Dell BCM20702A0 Bluetooth Module                    | 6         | 0.37%   |
| Broadcom HP Portable SoftSailing                    | 6         | 0.37%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 6         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1518      | 64.4%   |
| AMD                                  | 407       | 17.27%  |
| Nvidia                               | 289       | 12.26%  |
| Lenovo                               | 13        | 0.55%   |
| GN Netcom                            | 12        | 0.51%   |
| Plantronics                          | 11        | 0.47%   |
| Hewlett-Packard                      | 10        | 0.42%   |
| C-Media Electronics                  | 8         | 0.34%   |
| Realtek Semiconductor                | 7         | 0.3%    |
| Corsair                              | 7         | 0.3%    |
| Apple                                | 7         | 0.3%    |
| Logitech                             | 6         | 0.25%   |
| Texas Instruments                    | 4         | 0.17%   |
| Razer USA                            | 4         | 0.17%   |
| Kingston Technology                  | 4         | 0.17%   |
| JMTek                                | 4         | 0.17%   |
| Creative Technology                  | 3         | 0.13%   |
| BEHRINGER International              | 3         | 0.13%   |
| XMOS                                 | 2         | 0.08%   |
| RODE Microphones                     | 2         | 0.08%   |
| JBL                                  | 2         | 0.08%   |
| Google                               | 2         | 0.08%   |
| DSEA A/S                             | 2         | 0.08%   |
| DCMT Technology                      | 2         | 0.08%   |
| ASUSTek Computer                     | 2         | 0.08%   |
| Zhaoxin                              | 1         | 0.04%   |
| X-TENSIONS                           | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| SteelSeries ApS                      | 1         | 0.04%   |
| Sony                                 | 1         | 0.04%   |
| Sennheiser Communications            | 1         | 0.04%   |
| SAVITECH                             | 1         | 0.04%   |
| Samsung Electronics                  | 1         | 0.04%   |
| OPPO Electronics                     | 1         | 0.04%   |
| No brand                             | 1         | 0.04%   |
| Medeli Electronics                   | 1         | 0.04%   |
| M-Audio                              | 1         | 0.04%   |
| Lautsprecher Teufel                  | 1         | 0.04%   |
| JOUNIVO                              | 1         | 0.04%   |
| Huawei Technologies                  | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 251       | 8.72%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 236       | 8.19%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 170       | 5.9%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 167       | 5.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 136       | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 83        | 2.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 76        | 2.64%   |
| Intel 8 Series HD Audio Controller                                                                | 76        | 2.64%   |
| Intel Broadwell-U Audio Controller                                                                | 69        | 2.4%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 68        | 2.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 67        | 2.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 65        | 2.26%   |
| Intel Cannon Lake PCH cAVS                                                                        | 64        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 64        | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 64        | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 62        | 2.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 56        | 1.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 52        | 1.81%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 48        | 1.67%   |
| AMD FCH Azalia Controller                                                                         | 48        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 46        | 1.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 46        | 1.6%    |
| Intel Comet Lake PCH cAVS                                                                         | 44        | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 44        | 1.53%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 39        | 1.35%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 38        | 1.32%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 36        | 1.25%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 35        | 1.22%   |
| AMD High Definition Audio Controller                                                              | 31        | 1.08%   |
| Nvidia Audio device                                                                               | 27        | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 26        | 0.9%    |
| AMD Kabini HDMI/DP Audio                                                                          | 26        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 22        | 0.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 21        | 0.73%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 20        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 20        | 0.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 0.63%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 0.63%   |
| Intel CM238 HD Audio Controller                                                                   | 17        | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 383       | 30.71%  |
| SK hynix                                | 306       | 24.54%  |
| Micron Technology                       | 179       | 14.35%  |
| Kingston                                | 89        | 7.14%   |
| Crucial                                 | 57        | 4.57%   |
| Unknown                                 | 38        | 3.05%   |
| Unknown (ABCD)                          | 30        | 2.41%   |
| A-DATA Technology                       | 30        | 2.41%   |
| Ramaxel Technology                      | 25        | 2%      |
| Nanya Technology                        | 12        | 0.96%   |
| Smart                                   | 11        | 0.88%   |
| Elpida                                  | 11        | 0.88%   |
| Unknown                                 | 9         | 0.72%   |
| Team                                    | 8         | 0.64%   |
| G.Skill                                 | 8         | 0.64%   |
| Corsair                                 | 7         | 0.56%   |
| Patriot                                 | 6         | 0.48%   |
| Goodram                                 | 3         | 0.24%   |
| Smart Brazil                            | 2         | 0.16%   |
| PNY                                     | 2         | 0.16%   |
| Kllisre                                 | 2         | 0.16%   |
| Goldkey                                 | 2         | 0.16%   |
| fef5                                    | 2         | 0.16%   |
| CSX                                     | 2         | 0.16%   |
| Avant                                   | 2         | 0.16%   |
| ASint Technology                        | 2         | 0.16%   |
| AMD                                     | 2         | 0.16%   |
| Wilk                                    | 1         | 0.08%   |
| Unknown (768A)                          | 1         | 0.08%   |
| Toshiba                                 | 1         | 0.08%   |
| Timetec                                 | 1         | 0.08%   |
| Super Talent                            | 1         | 0.08%   |
| Silicon Power Computer & Communications | 1         | 0.08%   |
| Silicon Power                           | 1         | 0.08%   |
| Shenzhen WODPOSIT                       | 1         | 0.08%   |
| SanMax                                  | 1         | 0.08%   |
| Qimonda                                 | 1         | 0.08%   |
| OM Nanotech                             | 1         | 0.08%   |
| Multilaser                              | 1         | 0.08%   |
| Memox                                   | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 2.71%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 29        | 2.24%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 1.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 1.24%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 16        | 1.24%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 14        | 1.08%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 14        | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 13        | 1.01%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.93%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 12        | 0.93%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.85%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 10        | 0.77%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.77%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 0.77%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 9         | 0.7%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 9         | 0.7%    |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 9         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.7%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.7%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.7%    |
| Unknown                                                          | 9         | 0.7%    |
| SK hynix RAM HMCG78MEBSA095N 16GB SODIMM DDR5 4800MT/s           | 8         | 0.62%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.62%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 8         | 0.62%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.62%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.54%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 7         | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 7         | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.54%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 7         | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 0.54%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 6         | 0.46%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 6         | 0.46%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 603       | 57.1%   |
| DDR3    | 235       | 22.25%  |
| LPDDR4  | 100       | 9.47%   |
| LPDDR3  | 42        | 3.98%   |
| DDR5    | 27        | 2.56%   |
| DDR2    | 16        | 1.52%   |
| Unknown | 16        | 1.52%   |
| LPDDR5  | 9         | 0.85%   |
| SDRAM   | 7         | 0.66%   |
| DDR     | 1         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 893       | 83.93%  |
| Row Of Chips | 155       | 14.57%  |
| Unknown      | 8         | 0.75%   |
| Chip         | 5         | 0.47%   |
| DIMM         | 3         | 0.28%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 458       | 39.86%  |
| 4096  | 352       | 30.64%  |
| 16384 | 194       | 16.88%  |
| 2048  | 78        | 6.79%   |
| 32768 | 52        | 4.53%   |
| 1024  | 13        | 1.13%   |
| 6144  | 2         | 0.17%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 316       | 27.89%  |
| 2667    | 237       | 20.92%  |
| 1600    | 185       | 16.33%  |
| 2400    | 104       | 9.18%   |
| 2133    | 55        | 4.85%   |
| 4267    | 37        | 3.27%   |
| 4800    | 35        | 3.09%   |
| 1334    | 30        | 2.65%   |
| 1333    | 21        | 1.85%   |
| 3266    | 16        | 1.41%   |
| 6400    | 13        | 1.15%   |
| 4266    | 13        | 1.15%   |
| 1867    | 13        | 1.15%   |
| 667     | 12        | 1.06%   |
| 1067    | 9         | 0.79%   |
| Unknown | 8         | 0.71%   |
| 4199    | 7         | 0.62%   |
| 1066    | 5         | 0.44%   |
| 8400    | 4         | 0.35%   |
| 2933    | 3         | 0.26%   |
| 1866    | 3         | 0.26%   |
| 800     | 2         | 0.18%   |
| 533     | 2         | 0.18%   |
| 3733    | 1         | 0.09%   |
| 2666    | 1         | 0.09%   |
| 975     | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 8         | 42.11%  |
| Canon               | 4         | 21.05%  |
| Brother Industries  | 4         | 21.05%  |
| STMicroelectronics  | 1         | 5.26%   |
| Seiko Epson         | 1         | 5.26%   |
| Samsung Electronics | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Brother DCP-1510                   | 2         | 10.53%  |
| STMicroelectronics USB Printer P   | 1         | 5.26%   |
| Seiko Epson L3110 Series           | 1         | 5.26%   |
| Samsung C43x Series                | 1         | 5.26%   |
| HP Officejet 4630 series           | 1         | 5.26%   |
| HP LaserJet M14-M17                | 1         | 5.26%   |
| HP LaserJet 1300                   | 1         | 5.26%   |
| HP LaserJet 1020                   | 1         | 5.26%   |
| HP LaserJet 1018                   | 1         | 5.26%   |
| HP DeskJet 2700 series             | 1         | 5.26%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 5.26%   |
| HP DeskJet 2300 series             | 1         | 5.26%   |
| Canon PIXMA MX330                  | 1         | 5.26%   |
| Canon PIXMA MG2900 Series          | 1         | 5.26%   |
| Canon MF3110                       | 1         | 5.26%   |
| Canon LBP6030w/6018w               | 1         | 5.26%   |
| Brother MFC-L2710DN series         | 1         | 5.26%   |
| Brother MFC-L2700DW                | 1         | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| HP OfficeJet 6110      | 1         | 33.33%  |
| Canon CanoScan LIDE 25 | 1         | 33.33%  |
| Canon CanoScan 4200F   | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 356       | 20.19%  |
| IMC Networks                           | 210       | 11.91%  |
| Microdia                               | 189       | 10.72%  |
| Realtek Semiconductor                  | 139       | 7.88%   |
| Acer                                   | 138       | 7.83%   |
| Quanta                                 | 123       | 6.98%   |
| Sunplus Innovation Technology          | 117       | 6.64%   |
| Cheng Uei Precision Industry (Foxlink) | 73        | 4.14%   |
| Luxvisions Innotech Limited            | 56        | 3.18%   |
| Suyin                                  | 51        | 2.89%   |
| Syntek                                 | 47        | 2.67%   |
| Lite-On Technology                     | 37        | 2.1%    |
| Apple                                  | 31        | 1.76%   |
| Silicon Motion                         | 23        | 1.3%    |
| Logitech                               | 23        | 1.3%    |
| Alcor Micro                            | 23        | 1.3%    |
| Samsung Electronics                    | 17        | 0.96%   |
| Sonix Technology                       | 11        | 0.62%   |
| Ricoh                                  | 10        | 0.57%   |
| Importek                               | 9         | 0.51%   |
| ALi                                    | 9         | 0.51%   |
| icSpring                               | 8         | 0.45%   |
| Lenovo                                 | 7         | 0.4%    |
| SunplusIT                              | 6         | 0.34%   |
| Y Media                                | 5         | 0.28%   |
| Primax Electronics                     | 5         | 0.28%   |
| Z-Star Microelectronics                | 4         | 0.23%   |
| Intel                                  | 4         | 0.23%   |
| OmniVision Technologies                | 3         | 0.17%   |
| Microsoft                              | 3         | 0.17%   |
| Sunplus Technology                     | 2         | 0.11%   |
| Jieli Technology                       | 2         | 0.11%   |
| Guillemot                              | 2         | 0.11%   |
| Xiaomi                                 | 1         | 0.06%   |
| WCM_USB                                | 1         | 0.06%   |
| USB Camera CS                          | 1         | 0.06%   |
| Unknown                                | 1         | 0.06%   |
| The Imaging Source Europe              | 1         | 0.06%   |
| ShineTech                              | 1         | 0.06%   |
| OYT TECH                               | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                        | 114       | 6.43%   |
| Chicony Integrated Camera                            | 89        | 5.02%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 52        | 2.93%   |
| IMC Networks Integrated Camera                       | 51        | 2.87%   |
| Acer Integrated Camera                               | 45        | 2.54%   |
| Realtek Integrated_Webcam_HD                         | 42        | 2.37%   |
| Chicony HD WebCam                                    | 40        | 2.25%   |
| Sunplus Integrated_Webcam_HD                         | 36        | 2.03%   |
| Chicony HP HD Camera                                 | 26        | 1.47%   |
| Syntek Integrated Camera                             | 24        | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 23        | 1.3%    |
| Quanta HD User Facing                                | 22        | 1.24%   |
| Quanta HP HD Camera                                  | 21        | 1.18%   |
| IMC Networks HD Camera                               | 21        | 1.18%   |
| Samsung Galaxy A5 (MTP)                              | 17        | 0.96%   |
| Quanta HP TrueVision HD Camera                       | 17        | 0.96%   |
| Chicony TOSHIBA Web Camera - HD                      | 17        | 0.96%   |
| Sunplus HD WebCam                                    | 15        | 0.85%   |
| Luxvisions Innotech Limited Integrated Camera        | 15        | 0.85%   |
| Realtek USB Camera                                   | 14        | 0.79%   |
| Realtek Integrated Webcam                            | 14        | 0.79%   |
| Cheng Uei Precision Industry (Foxlink) Webcam        | 14        | 0.79%   |
| Quanta HD WebCam                                     | 13        | 0.73%   |
| Luxvisions Innotech Limited HP HD Camera             | 13        | 0.73%   |
| Lite-On HP HD Webcam                                 | 13        | 0.73%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 12        | 0.68%   |
| Chicony HD User Facing                               | 12        | 0.68%   |
| Acer Lenovo EasyCamera                               | 12        | 0.68%   |
| Suyin HP Truevision HD                               | 11        | 0.62%   |
| Microdia Integrated Webcam                           | 11        | 0.62%   |
| Lite-On Integrated Camera                            | 11        | 0.62%   |
| IMC Networks HP TrueVision HD Camera                 | 11        | 0.62%   |
| Alcor Micro SHUNCCM2MP                               | 11        | 0.62%   |
| Syntek Lenovo EasyCamera                             | 10        | 0.56%   |
| Sonix USB2.0 HD UVC WebCam                           | 10        | 0.56%   |
| Realtek HD WebCam                                    | 10        | 0.56%   |
| Quanta HP Wide Vision HD Camera                      | 10        | 0.56%   |
| Quanta HD Camera                                     | 10        | 0.56%   |
| Microdia Webcam Vitade AF                            | 10        | 0.56%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 10        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 119       | 30.2%   |
| Synaptics                  | 102       | 25.89%  |
| Shenzhen Goodix Technology | 97        | 24.62%  |
| Elan Microelectronics      | 31        | 7.87%   |
| LighTuning Technology      | 15        | 3.81%   |
| AuthenTec                  | 14        | 3.55%   |
| Upek                       | 12        | 3.05%   |
| STMicroelectronics         | 1         | 0.25%   |
| HOLTEK                     | 1         | 0.25%   |
| Focal-systems.Corp         | 1         | 0.25%   |
| DigitalPersona             | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 69        | 17.51%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 9.64%   |
| Unknown                                                                    | 33        | 8.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 6.6%    |
| Elan ELAN:ARM-M4                                                           | 19        | 4.82%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 15        | 3.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 15        | 3.81%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 3.3%    |
| Elan ELAN:Fingerprint                                                      | 12        | 3.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 2.79%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 2.54%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 2.54%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 10        | 2.54%   |
| Validity Sensors VFS491                                                    | 9         | 2.28%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.28%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.28%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 2.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 8         | 2.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 1.78%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.78%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.52%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.52%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.52%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.27%   |
| AuthenTec AES1600                                                          | 4         | 1.02%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 0.76%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.51%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.51%   |
| Synaptics  WBDI                                                            | 2         | 0.51%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.51%   |
| AuthenTec AES2810                                                          | 2         | 0.51%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 0.51%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.25%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.25%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.25%   |
| Synaptics WBDI Device                                                      | 1         | 0.25%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.25%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 83        | 61.94%  |
| Alcor Micro               | 33        | 24.63%  |
| Upek                      | 4         | 2.99%   |
| O2 Micro                  | 4         | 2.99%   |
| Gemalto (was Gemplus)     | 4         | 2.99%   |
| Watchdata                 | 1         | 0.75%   |
| SCM Microsystems          | 1         | 0.75%   |
| OmniKey                   | 1         | 0.75%   |
| NXP Semiconductors        | 1         | 0.75%   |
| Lenovo                    | 1         | 0.75%   |
| Aladdin Knowledge Systems | 1         | 0.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 33        | 24.63%  |
| Broadcom 58200                                                               | 30        | 22.39%  |
| Broadcom BCM5880 Secure Applications Processor                               | 24        | 17.91%  |
| Broadcom 5880                                                                | 19        | 14.18%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 7.46%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.99%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 2.99%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.49%   |
| Watchdata USB Key                                                            | 1         | 0.75%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.75%   |
| OmniKey CardMan 4321                                                         | 1         | 0.75%   |
| NXP Semiconductors PR533                                                     | 1         | 0.75%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 0.75%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.75%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.75%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.75%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1149      | 59.29%  |
| 1     | 637       | 32.87%  |
| 2     | 140       | 7.22%   |
| 3     | 9         | 0.46%   |
| 5     | 2         | 0.1%    |
| 7     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 387       | 41.35%  |
| Graphics card            | 184       | 19.66%  |
| Chipcard                 | 126       | 13.46%  |
| Net/wireless             | 76        | 8.12%   |
| Camera                   | 59        | 6.3%    |
| Multimedia controller    | 32        | 3.42%   |
| Bluetooth                | 29        | 3.1%    |
| Sound                    | 14        | 1.5%    |
| Storage                  | 11        | 1.18%   |
| Card reader              | 9         | 0.96%   |
| Communication controller | 5         | 0.53%   |
| Network                  | 2         | 0.21%   |
| Net/ethernet             | 2         | 0.21%   |

