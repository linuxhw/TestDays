Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad W530 244743G       | [69a252ccd6](https://linux-hardware.org/?probe=69a252ccd6) | Oct 31, 2021 |
| Dell          | Inspiron 5502               | [e58d33df6b](https://linux-hardware.org/?probe=e58d33df6b) | Oct 31, 2021 |
| Unknown       | MT8117                      | [b579146661](https://linux-hardware.org/?probe=b579146661) | Oct 31, 2021 |
| Dell          | Inspiron 1525               | [38b4ba227c](https://linux-hardware.org/?probe=38b4ba227c) | Oct 30, 2021 |
| Dell          | Inspiron 1525               | [b6302b710d](https://linux-hardware.org/?probe=b6302b710d) | Oct 30, 2021 |
| Dell          | Vostro 3500                 | [60f4ac8cc5](https://linux-hardware.org/?probe=60f4ac8cc5) | Oct 30, 2021 |
| Apple         | MacBookAir7,2               | [5be083edab](https://linux-hardware.org/?probe=5be083edab) | Oct 29, 2021 |
| Dell          | Latitude E7240              | [dbf0fd04c3](https://linux-hardware.org/?probe=dbf0fd04c3) | Oct 28, 2021 |
| Compal        | QAL51                       | [ffffaf4799](https://linux-hardware.org/?probe=ffffaf4799) | Oct 28, 2021 |
| ASUSTek       | Strix 17 GL703GE            | [085ef9e58d](https://linux-hardware.org/?probe=085ef9e58d) | Oct 28, 2021 |
| Acer          | Nitro AN515-54              | [d85a5ada85](https://linux-hardware.org/?probe=d85a5ada85) | Oct 28, 2021 |
| HP            | EliteBook 840 G2            | [a7cc3183f2](https://linux-hardware.org/?probe=a7cc3183f2) | Oct 28, 2021 |
| HP            | Notebook                    | [0ba26ccc72](https://linux-hardware.org/?probe=0ba26ccc72) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| HP            | Laptop 17-by1xxx            | [e6406f34f8](https://linux-hardware.org/?probe=e6406f34f8) | Oct 27, 2021 |
| Dell          | Latitude E6330              | [872cfff7da](https://linux-hardware.org/?probe=872cfff7da) | Oct 26, 2021 |
| Lenovo        | ThinkPad T540p 20BFS05B0... | [5026826dbe](https://linux-hardware.org/?probe=5026826dbe) | Oct 26, 2021 |
| Lenovo        | ThinkPad T540p 20BFS05B0... | [f644310091](https://linux-hardware.org/?probe=f644310091) | Oct 26, 2021 |
| Dell          | Latitude E6330              | [c3e7f97c42](https://linux-hardware.org/?probe=c3e7f97c42) | Oct 25, 2021 |
| Dell          | Latitude E6330              | [0e88df3ae7](https://linux-hardware.org/?probe=0e88df3ae7) | Oct 25, 2021 |
| HP            | Pavilion g6                 | [2c2d7620f9](https://linux-hardware.org/?probe=2c2d7620f9) | Oct 25, 2021 |
| Acer          | AOA150                      | [1380638bb1](https://linux-hardware.org/?probe=1380638bb1) | Oct 25, 2021 |
| Dell          | Latitude E6540              | [df9262f810](https://linux-hardware.org/?probe=df9262f810) | Oct 25, 2021 |
| Acer          | Swift SF314-59              | [1e4856a770](https://linux-hardware.org/?probe=1e4856a770) | Oct 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [be67e01a7d](https://linux-hardware.org/?probe=be67e01a7d) | Oct 24, 2021 |
| Acer          | Aspire A315-23G             | [09f6196e70](https://linux-hardware.org/?probe=09f6196e70) | Oct 23, 2021 |
| Dell          | Latitude E6330              | [e7a19ad923](https://linux-hardware.org/?probe=e7a19ad923) | Oct 23, 2021 |
| HP            | ProBook 430 G5              | [6954277377](https://linux-hardware.org/?probe=6954277377) | Oct 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [7aac95cd60](https://linux-hardware.org/?probe=7aac95cd60) | Oct 23, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [c8f19e95d8](https://linux-hardware.org/?probe=c8f19e95d8) | Oct 23, 2021 |
| Dell          | Inspiron 11 - 3147          | [7354eacfc5](https://linux-hardware.org/?probe=7354eacfc5) | Oct 23, 2021 |
| Jumper        | EZbook                      | [557738cd7d](https://linux-hardware.org/?probe=557738cd7d) | Oct 23, 2021 |
| HP            | EliteBook 840 Aero G8 No... | [713c29aa23](https://linux-hardware.org/?probe=713c29aa23) | Oct 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [bcc008e381](https://linux-hardware.org/?probe=bcc008e381) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [55dcb690c5](https://linux-hardware.org/?probe=55dcb690c5) | Oct 22, 2021 |
| Dell          | Inspiron N4050              | [85a514f622](https://linux-hardware.org/?probe=85a514f622) | Oct 22, 2021 |
| LG Electro... | X120-L.C7L1A9               | [42b7007a7e](https://linux-hardware.org/?probe=42b7007a7e) | Oct 21, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [2815629b34](https://linux-hardware.org/?probe=2815629b34) | Oct 21, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [fe4c73ce24](https://linux-hardware.org/?probe=fe4c73ce24) | Oct 21, 2021 |
| HP            | 250 G1                      | [b34fa14c55](https://linux-hardware.org/?probe=b34fa14c55) | Oct 21, 2021 |
| Dell          | Inspiron 11 - 3147          | [7039c3e31f](https://linux-hardware.org/?probe=7039c3e31f) | Oct 20, 2021 |
| Acer          | Aspire A315-23              | [e8b00fa29b](https://linux-hardware.org/?probe=e8b00fa29b) | Oct 20, 2021 |
| HP            | Laptop 15-db0xxx            | [cd4a22e83b](https://linux-hardware.org/?probe=cd4a22e83b) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2c5f518cc8](https://linux-hardware.org/?probe=2c5f518cc8) | Oct 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [0290c2ca6d](https://linux-hardware.org/?probe=0290c2ca6d) | Oct 19, 2021 |
| Lenovo        | ThinkPad 20J10046US         | [cad3a5eb69](https://linux-hardware.org/?probe=cad3a5eb69) | Oct 18, 2021 |
| Lenovo        | ThinkPad T480 20L5000AMC    | [ea23d24f90](https://linux-hardware.org/?probe=ea23d24f90) | Oct 18, 2021 |
| Aquarius      | NS585                       | [ea22908ff7](https://linux-hardware.org/?probe=ea22908ff7) | Oct 18, 2021 |
| Aquarius      | NS585                       | [daf0f8d357](https://linux-hardware.org/?probe=daf0f8d357) | Oct 18, 2021 |
| MSI           | GF75 Thin 9SC               | [1f4a66b99a](https://linux-hardware.org/?probe=1f4a66b99a) | Oct 18, 2021 |
| Aquarius      | NS585                       | [0f5ea2eb9a](https://linux-hardware.org/?probe=0f5ea2eb9a) | Oct 18, 2021 |
| Aquarius      | NS585                       | [08f117fdcb](https://linux-hardware.org/?probe=08f117fdcb) | Oct 18, 2021 |
| Aquarius      | NS585                       | [3921dda159](https://linux-hardware.org/?probe=3921dda159) | Oct 18, 2021 |
| Aquarius      | NS585                       | [22c808750d](https://linux-hardware.org/?probe=22c808750d) | Oct 18, 2021 |
| Acer          | Aspire A315-23G             | [66d1015de7](https://linux-hardware.org/?probe=66d1015de7) | Oct 17, 2021 |
| Acer          | Aspire A515-51G             | [43bfef3bcd](https://linux-hardware.org/?probe=43bfef3bcd) | Oct 17, 2021 |
| Lenovo        | S10-3                       | [1f4f861804](https://linux-hardware.org/?probe=1f4f861804) | Oct 17, 2021 |
| Dell          | XPS 13 9305                 | [d13426531e](https://linux-hardware.org/?probe=d13426531e) | Oct 17, 2021 |
| HP            | Pavilion x2 Detachable      | [c17c589af5](https://linux-hardware.org/?probe=c17c589af5) | Oct 17, 2021 |
| Toshiba       | Satellite A205              | [68ac15eeda](https://linux-hardware.org/?probe=68ac15eeda) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [69fc64df8b](https://linux-hardware.org/?probe=69fc64df8b) | Oct 16, 2021 |
| Lenovo        | S10-3                       | [acb07e4c72](https://linux-hardware.org/?probe=acb07e4c72) | Oct 16, 2021 |
| Lenovo        | G50-45 80E3                 | [5e79417ff5](https://linux-hardware.org/?probe=5e79417ff5) | Oct 16, 2021 |
| Apple         | MacBook3,1                  | [34fc60e37e](https://linux-hardware.org/?probe=34fc60e37e) | Oct 16, 2021 |
| Acer          | TravelMate P215-53          | [3d398d4b58](https://linux-hardware.org/?probe=3d398d4b58) | Oct 16, 2021 |
| Lenovo        | ThinkPad X60 17068GG        | [2f3b34aac4](https://linux-hardware.org/?probe=2f3b34aac4) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | [dc7e454319](https://linux-hardware.org/?probe=dc7e454319) | Oct 15, 2021 |
| Apple         | MacBookPro14,1              | [bf9482b190](https://linux-hardware.org/?probe=bf9482b190) | Oct 15, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [a7045defdf](https://linux-hardware.org/?probe=a7045defdf) | Oct 15, 2021 |
| Dell          | XPS 15 7590                 | [ff55772306](https://linux-hardware.org/?probe=ff55772306) | Oct 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [9005e4d86d](https://linux-hardware.org/?probe=9005e4d86d) | Oct 15, 2021 |
| Lenovo        | ThinkPad 20J10046US         | [2d46a44cca](https://linux-hardware.org/?probe=2d46a44cca) | Oct 14, 2021 |
| Apple         | MacBookAir7,2               | [f78b91b7de](https://linux-hardware.org/?probe=f78b91b7de) | Oct 14, 2021 |
| Acer          | Aspire A315-23G             | [f8f343d12b](https://linux-hardware.org/?probe=f8f343d12b) | Oct 14, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [c3cdfe0336](https://linux-hardware.org/?probe=c3cdfe0336) | Oct 14, 2021 |
| Aquarius      | NS585                       | [7345eddec4](https://linux-hardware.org/?probe=7345eddec4) | Oct 14, 2021 |
| Apple         | MacBookAir7,1               | [22a831db3d](https://linux-hardware.org/?probe=22a831db3d) | Oct 14, 2021 |
| Aquarius      | NS585                       | [d42e0a77d4](https://linux-hardware.org/?probe=d42e0a77d4) | Oct 14, 2021 |
| Aquarius      | NS585                       | [7b0dd9fe28](https://linux-hardware.org/?probe=7b0dd9fe28) | Oct 14, 2021 |
| Aquarius      | NS585                       | [ea53e809fd](https://linux-hardware.org/?probe=ea53e809fd) | Oct 14, 2021 |
| Acer          | Aspire A515-51G             | [7555392d34](https://linux-hardware.org/?probe=7555392d34) | Oct 14, 2021 |
| Aquarius      | NS585                       | [aaca557699](https://linux-hardware.org/?probe=aaca557699) | Oct 14, 2021 |
| Sony          | SVE14A15FLB                 | [22a4b460cc](https://linux-hardware.org/?probe=22a4b460cc) | Oct 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [2ae81cd94f](https://linux-hardware.org/?probe=2ae81cd94f) | Oct 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | [000ac750e0](https://linux-hardware.org/?probe=000ac750e0) | Oct 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | [69b1046c6e](https://linux-hardware.org/?probe=69b1046c6e) | Oct 13, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [cdb34ca184](https://linux-hardware.org/?probe=cdb34ca184) | Oct 13, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [923479d039](https://linux-hardware.org/?probe=923479d039) | Oct 13, 2021 |
| ASUSTek       | TP201SA                     | [504956d2e9](https://linux-hardware.org/?probe=504956d2e9) | Oct 13, 2021 |
| ASUSTek       | UX303LAB                    | [97b9f51735](https://linux-hardware.org/?probe=97b9f51735) | Oct 13, 2021 |
| MSI           | GF75 Thin 9SC               | [db0ef927e0](https://linux-hardware.org/?probe=db0ef927e0) | Oct 13, 2021 |
| MSI           | GF75 Thin 9SC               | [be82875929](https://linux-hardware.org/?probe=be82875929) | Oct 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [f2690f5ec4](https://linux-hardware.org/?probe=f2690f5ec4) | Oct 13, 2021 |
| HP            | G62                         | [7873481ecb](https://linux-hardware.org/?probe=7873481ecb) | Oct 12, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [b01543c6b8](https://linux-hardware.org/?probe=b01543c6b8) | Oct 12, 2021 |
| Acer          | Aspire ES1-531              | [2a96c0566a](https://linux-hardware.org/?probe=2a96c0566a) | Oct 12, 2021 |
| Dell          | XPS 15 9560                 | [69938c221e](https://linux-hardware.org/?probe=69938c221e) | Oct 12, 2021 |
| Dell          | Vostro 3500                 | [4e86b85a4d](https://linux-hardware.org/?probe=4e86b85a4d) | Oct 12, 2021 |
| Acer          | Aspire A315-23G             | [6476999787](https://linux-hardware.org/?probe=6476999787) | Oct 12, 2021 |
| Lenovo        | ThinkPad T520 4242W9B       | [3947636b4d](https://linux-hardware.org/?probe=3947636b4d) | Oct 12, 2021 |
| Dell          | Inspiron 5567               | [e551d622a8](https://linux-hardware.org/?probe=e551d622a8) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [dce9cc60d3](https://linux-hardware.org/?probe=dce9cc60d3) | Oct 11, 2021 |
| HP            | EliteBook 8460p             | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| Acer          | Aspire A315-23G             | [c97f94ce2f](https://linux-hardware.org/?probe=c97f94ce2f) | Oct 10, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [598d90e6b6](https://linux-hardware.org/?probe=598d90e6b6) | Oct 10, 2021 |
| HP            | TouchSmart tm2              | [4a04d297c6](https://linux-hardware.org/?probe=4a04d297c6) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | [31ae42bc51](https://linux-hardware.org/?probe=31ae42bc51) | Oct 09, 2021 |
| Apple         | MacBookAir7,2               | [5b47e8efcb](https://linux-hardware.org/?probe=5b47e8efcb) | Oct 09, 2021 |
| Dell          | Inspiron 5559               | [3ab285ffb2](https://linux-hardware.org/?probe=3ab285ffb2) | Oct 09, 2021 |
| ASUSTek       | GL553VE                     | [cbbb88337f](https://linux-hardware.org/?probe=cbbb88337f) | Oct 09, 2021 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [00a9d32484](https://linux-hardware.org/?probe=00a9d32484) | Oct 08, 2021 |
| ASUSTek       | N501VW                      | [40231fbffa](https://linux-hardware.org/?probe=40231fbffa) | Oct 08, 2021 |
| Dell          | Latitude 7480               | [e4d0ecb120](https://linux-hardware.org/?probe=e4d0ecb120) | Oct 07, 2021 |
| Lenovo        | ThinkPad T490 20N2000KGE    | [cb7f37874e](https://linux-hardware.org/?probe=cb7f37874e) | Oct 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d76a0d7ff1](https://linux-hardware.org/?probe=d76a0d7ff1) | Oct 07, 2021 |
| Dell          | Latitude E6520              | [18591f972c](https://linux-hardware.org/?probe=18591f972c) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [9ed170f601](https://linux-hardware.org/?probe=9ed170f601) | Oct 07, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [97f69ae3fa](https://linux-hardware.org/?probe=97f69ae3fa) | Oct 07, 2021 |
| Dell          | Vostro A860                 | [02a4dade57](https://linux-hardware.org/?probe=02a4dade57) | Oct 07, 2021 |
| Dell          | Vostro A860                 | [67da5c585b](https://linux-hardware.org/?probe=67da5c585b) | Oct 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [cbb2ea622b](https://linux-hardware.org/?probe=cbb2ea622b) | Oct 07, 2021 |
| MSI           | GF63 8RD                    | [42dfecd0fb](https://linux-hardware.org/?probe=42dfecd0fb) | Oct 06, 2021 |
| ASUSTek       | 1015PE                      | [1a2d7bc306](https://linux-hardware.org/?probe=1a2d7bc306) | Oct 06, 2021 |
| MSI           | GF63 8RD                    | [1c72d1e5d7](https://linux-hardware.org/?probe=1c72d1e5d7) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Dell          | Latitude 7480               | [89d642f54a](https://linux-hardware.org/?probe=89d642f54a) | Oct 06, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [eb4d94004c](https://linux-hardware.org/?probe=eb4d94004c) | Oct 06, 2021 |
| Apple         | MacBook3,1                  | [1e7ca025e2](https://linux-hardware.org/?probe=1e7ca025e2) | Oct 06, 2021 |
| HP            | EliteBook 2170p             | [b5e3aaff19](https://linux-hardware.org/?probe=b5e3aaff19) | Oct 06, 2021 |
| MSI           | Bravo 15 A4DDR              | [3c8835ecc1](https://linux-hardware.org/?probe=3c8835ecc1) | Oct 05, 2021 |
| HP            | 650                         | [bbe8e793b8](https://linux-hardware.org/?probe=bbe8e793b8) | Oct 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | [555befb01f](https://linux-hardware.org/?probe=555befb01f) | Oct 05, 2021 |
| Apple         | MacBookAir7,2               | [9a8833b9c4](https://linux-hardware.org/?probe=9a8833b9c4) | Oct 04, 2021 |
| Dell          | Latitude 7480               | [e8c50a7dbb](https://linux-hardware.org/?probe=e8c50a7dbb) | Oct 04, 2021 |
| Dell          | Latitude E6520              | [b9f0ad8ced](https://linux-hardware.org/?probe=b9f0ad8ced) | Oct 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [572e073021](https://linux-hardware.org/?probe=572e073021) | Oct 04, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [bcdf58bee3](https://linux-hardware.org/?probe=bcdf58bee3) | Oct 04, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| Acer          | Aspire A315-23G             | [9622936906](https://linux-hardware.org/?probe=9622936906) | Oct 04, 2021 |
| HP            | EliteBook 830 G6            | [ccc383c91f](https://linux-hardware.org/?probe=ccc383c91f) | Oct 03, 2021 |
| HP            | EliteBook 830 G6            | [8a9c0fa053](https://linux-hardware.org/?probe=8a9c0fa053) | Oct 03, 2021 |
| Acer          | TMP645-M                    | [c3daab516f](https://linux-hardware.org/?probe=c3daab516f) | Oct 03, 2021 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [52d91383da](https://linux-hardware.org/?probe=52d91383da) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | [153c60004b](https://linux-hardware.org/?probe=153c60004b) | Oct 03, 2021 |
| Acer          | Aspire A114-32              | [0c7f8d9bc1](https://linux-hardware.org/?probe=0c7f8d9bc1) | Oct 03, 2021 |
| HP            | Laptop 15-ra0xx             | [f053eed9e5](https://linux-hardware.org/?probe=f053eed9e5) | Oct 02, 2021 |
| ASUSTek       | 1005HA                      | [5dff50e4bf](https://linux-hardware.org/?probe=5dff50e4bf) | Oct 02, 2021 |
| ASUSTek       | 1005HA                      | [eae46e3544](https://linux-hardware.org/?probe=eae46e3544) | Oct 02, 2021 |
| Dell          | Inspiron 3421               | [8169f29a6a](https://linux-hardware.org/?probe=8169f29a6a) | Oct 02, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [f5565dfb2a](https://linux-hardware.org/?probe=f5565dfb2a) | Oct 01, 2021 |
| HP            | ProBook 430 G6              | [f248667e17](https://linux-hardware.org/?probe=f248667e17) | Oct 01, 2021 |
| HP            | Pavilion g6                 | [ca85ba36e3](https://linux-hardware.org/?probe=ca85ba36e3) | Oct 01, 2021 |
| Lenovo        | B50-30 20382                | [85242c59b6](https://linux-hardware.org/?probe=85242c59b6) | Oct 01, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | [090eee57b7](https://linux-hardware.org/?probe=090eee57b7) | Oct 01, 2021 |
| TrekStor      | Surfbook A13                | [e393d9bc10](https://linux-hardware.org/?probe=e393d9bc10) | Oct 01, 2021 |
| MSI           | GF75 Thin 9SC               | [b62cc852e9](https://linux-hardware.org/?probe=b62cc852e9) | Oct 01, 2021 |
| Apple         | MacBookAir7,2               | [8fa4158350](https://linux-hardware.org/?probe=8fa4158350) | Sep 30, 2021 |
| Dell          | Latitude 7480               | [edecedab9c](https://linux-hardware.org/?probe=edecedab9c) | Sep 30, 2021 |
| Acer          | Aspire A315-23G             | [b8b2183bc1](https://linux-hardware.org/?probe=b8b2183bc1) | Sep 30, 2021 |
| Intel Clie... | LAPBC710                    | [f2535939a1](https://linux-hardware.org/?probe=f2535939a1) | Sep 29, 2021 |
| Timi          | TM1613                      | [f6bb688e77](https://linux-hardware.org/?probe=f6bb688e77) | Sep 29, 2021 |
| Dell          | Precision 3561              | [59bbb944c2](https://linux-hardware.org/?probe=59bbb944c2) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [885bbac853](https://linux-hardware.org/?probe=885bbac853) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8e7519557](https://linux-hardware.org/?probe=b8e7519557) | Sep 29, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [d277db28c5](https://linux-hardware.org/?probe=d277db28c5) | Sep 29, 2021 |
| Acer          | Aspire A315-23G             | [f7a5bd6c04](https://linux-hardware.org/?probe=f7a5bd6c04) | Sep 29, 2021 |
| Dell          | Latitude D630               | [5e7edac95e](https://linux-hardware.org/?probe=5e7edac95e) | Sep 29, 2021 |
| Apple         | MacBookPro14,1              | [01ccd7b321](https://linux-hardware.org/?probe=01ccd7b321) | Sep 28, 2021 |
| Google        | Enguarde                    | [36df7d61be](https://linux-hardware.org/?probe=36df7d61be) | Sep 28, 2021 |
| Google        | Enguarde                    | [4514b06137](https://linux-hardware.org/?probe=4514b06137) | Sep 28, 2021 |
| Google        | Enguarde                    | [ac6c9be38a](https://linux-hardware.org/?probe=ac6c9be38a) | Sep 28, 2021 |
| Google        | Enguarde                    | [36532b595e](https://linux-hardware.org/?probe=36532b595e) | Sep 28, 2021 |
| HP            | Pavilion g6                 | [a349ae4420](https://linux-hardware.org/?probe=a349ae4420) | Sep 28, 2021 |
| Google        | Enguarde                    | [b4273a32be](https://linux-hardware.org/?probe=b4273a32be) | Sep 28, 2021 |
| Google        | Enguarde                    | [0b6cac4bce](https://linux-hardware.org/?probe=0b6cac4bce) | Sep 28, 2021 |
| Google        | Enguarde                    | [3ebd210998](https://linux-hardware.org/?probe=3ebd210998) | Sep 28, 2021 |
| Google        | Enguarde                    | [8ad08b2012](https://linux-hardware.org/?probe=8ad08b2012) | Sep 28, 2021 |
| Apple         | MacBookAir7,1               | [b8706044ce](https://linux-hardware.org/?probe=b8706044ce) | Sep 28, 2021 |
| ASUSTek       | N550JV                      | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | X556UAK                     | [6cd310a2c4](https://linux-hardware.org/?probe=6cd310a2c4) | Sep 27, 2021 |
| Lenovo        | ThinkPad T430 2349N7G       | [d82d96a0ce](https://linux-hardware.org/?probe=d82d96a0ce) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [61fb50bdf0](https://linux-hardware.org/?probe=61fb50bdf0) | Sep 27, 2021 |
| Lenovo        | G50-45 80E3                 | [a01dd88bfb](https://linux-hardware.org/?probe=a01dd88bfb) | Sep 27, 2021 |
| Lenovo        | IdeaPad U510 4941           | [f0f189cfc9](https://linux-hardware.org/?probe=f0f189cfc9) | Sep 27, 2021 |
| HP            | G61                         | [348bab0a1b](https://linux-hardware.org/?probe=348bab0a1b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | [721c266b6b](https://linux-hardware.org/?probe=721c266b6b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | [00d9651c96](https://linux-hardware.org/?probe=00d9651c96) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | [f290c9b80f](https://linux-hardware.org/?probe=f290c9b80f) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | [82bd2ec7eb](https://linux-hardware.org/?probe=82bd2ec7eb) | Sep 27, 2021 |
| MSI           | Bravo 15 A4DDR              | [5236361305](https://linux-hardware.org/?probe=5236361305) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8f8f724934](https://linux-hardware.org/?probe=8f8f724934) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3b68a00361](https://linux-hardware.org/?probe=3b68a00361) | Sep 26, 2021 |
| Packard Be... | EasyNote TS11HR             | [abf2c60d3f](https://linux-hardware.org/?probe=abf2c60d3f) | Sep 26, 2021 |
| Acer          | Aspire F5-573G              | [97a2a90138](https://linux-hardware.org/?probe=97a2a90138) | Sep 26, 2021 |
| Toshiba       | Satellite C655D             | [7742f4cfe0](https://linux-hardware.org/?probe=7742f4cfe0) | Sep 26, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [1f56f02f1d](https://linux-hardware.org/?probe=1f56f02f1d) | Sep 26, 2021 |
| Acer          | TravelMate 2490             | [b09a0d7779](https://linux-hardware.org/?probe=b09a0d7779) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [0c67accead](https://linux-hardware.org/?probe=0c67accead) | Sep 25, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [3b61d0a304](https://linux-hardware.org/?probe=3b61d0a304) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [2762c5237d](https://linux-hardware.org/?probe=2762c5237d) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [7a1202630f](https://linux-hardware.org/?probe=7a1202630f) | Sep 25, 2021 |
| Apple         | MacBookPro12,1              | [4d798633db](https://linux-hardware.org/?probe=4d798633db) | Sep 25, 2021 |
| HP            | Pavilion dv6                | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| Dell          | G3 3590                     | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [11ebd06d5f](https://linux-hardware.org/?probe=11ebd06d5f) | Sep 25, 2021 |
| HP            | ProBook 4530s               | [0fc1845cd7](https://linux-hardware.org/?probe=0fc1845cd7) | Sep 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e9d692e16d](https://linux-hardware.org/?probe=e9d692e16d) | Sep 24, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [c654d6756a](https://linux-hardware.org/?probe=c654d6756a) | Sep 24, 2021 |
| Dell          | Inspiron 5515               | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Dell          | Precision M4800             | [1d4a25cfec](https://linux-hardware.org/?probe=1d4a25cfec) | Sep 24, 2021 |
| Toshiba       | PORTEGE R830                | [fbe6b1147d](https://linux-hardware.org/?probe=fbe6b1147d) | Sep 24, 2021 |
| Acer          | TravelMate P273             | [125707a56f](https://linux-hardware.org/?probe=125707a56f) | Sep 24, 2021 |
| MSI           | GE70 2QE                    | [b1cbbbd78f](https://linux-hardware.org/?probe=b1cbbbd78f) | Sep 23, 2021 |
| ASUSTek       | 1015BXO                     | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| Dell          | Inspiron 5593               | [5ddd391946](https://linux-hardware.org/?probe=5ddd391946) | Sep 23, 2021 |
| HP            | 15                          | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Apple         | MacBookAir7,1               | [e36127ceb6](https://linux-hardware.org/?probe=e36127ceb6) | Sep 22, 2021 |
| HP            | Pavilion dv6                | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | Mixx-700-12ISK 80QL         | [090e25b77c](https://linux-hardware.org/?probe=090e25b77c) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1e8858844a](https://linux-hardware.org/?probe=1e8858844a) | Sep 22, 2021 |
| Dell          | Latitude E7240              | [7048aa6e8b](https://linux-hardware.org/?probe=7048aa6e8b) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [ff5e9a45c3](https://linux-hardware.org/?probe=ff5e9a45c3) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [64b5e6acaf](https://linux-hardware.org/?probe=64b5e6acaf) | Sep 21, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5e6cd3a827](https://linux-hardware.org/?probe=5e6cd3a827) | Sep 21, 2021 |
| Dell          | Vostro 5471                 | [4ce9cddd8f](https://linux-hardware.org/?probe=4ce9cddd8f) | Sep 21, 2021 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [65802f1a29](https://linux-hardware.org/?probe=65802f1a29) | Sep 21, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [14ea1aaa38](https://linux-hardware.org/?probe=14ea1aaa38) | Sep 21, 2021 |
| Lenovo        | ThinkPad T480S 20L7002HC... | [18b74e9f12](https://linux-hardware.org/?probe=18b74e9f12) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | [ab40e7b1de](https://linux-hardware.org/?probe=ab40e7b1de) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | [13687ea608](https://linux-hardware.org/?probe=13687ea608) | Sep 21, 2021 |
| ASUSTek       | K50IN                       | [7cdaef32aa](https://linux-hardware.org/?probe=7cdaef32aa) | Sep 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [203ccd91be](https://linux-hardware.org/?probe=203ccd91be) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | [e8748906aa](https://linux-hardware.org/?probe=e8748906aa) | Sep 20, 2021 |
| MSI           | GE70 2QE                    | [a8b9147ea7](https://linux-hardware.org/?probe=a8b9147ea7) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | [22262e98a5](https://linux-hardware.org/?probe=22262e98a5) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | [c266841471](https://linux-hardware.org/?probe=c266841471) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | [81802596f8](https://linux-hardware.org/?probe=81802596f8) | Sep 20, 2021 |
| HP            | Pavilion g6                 | [d7ce22ebcb](https://linux-hardware.org/?probe=d7ce22ebcb) | Sep 20, 2021 |
| HP            | Pavilion g6                 | [3c060f3910](https://linux-hardware.org/?probe=3c060f3910) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | [bcb44edae6](https://linux-hardware.org/?probe=bcb44edae6) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | [d623d8381b](https://linux-hardware.org/?probe=d623d8381b) | Sep 20, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| Lenovo        | ThinkPad P53 20QQA004CD     | [50b6533131](https://linux-hardware.org/?probe=50b6533131) | Sep 20, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [72c81ecb73](https://linux-hardware.org/?probe=72c81ecb73) | Sep 19, 2021 |
| MSI           | U270 series                 | [6b98f78732](https://linux-hardware.org/?probe=6b98f78732) | Sep 19, 2021 |
| Acer          | AOA110                      | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [61fd64b037](https://linux-hardware.org/?probe=61fd64b037) | Sep 19, 2021 |
| MSI           | U270 series                 | [725e0a6a36](https://linux-hardware.org/?probe=725e0a6a36) | Sep 18, 2021 |
| Acer          | Aspire 5560                 | [f35af81d19](https://linux-hardware.org/?probe=f35af81d19) | Sep 18, 2021 |
| Dell          | Latitude E7450              | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Lenovo        | G70-35 80Q5                 | [6ce6f8e7f7](https://linux-hardware.org/?probe=6ce6f8e7f7) | Sep 17, 2021 |
| Lenovo        | IdeaPad U510 4941           | [f5774645c1](https://linux-hardware.org/?probe=f5774645c1) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | [0f6db66354](https://linux-hardware.org/?probe=0f6db66354) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | [2179e59b37](https://linux-hardware.org/?probe=2179e59b37) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | [84394a400e](https://linux-hardware.org/?probe=84394a400e) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [726f5ed51f](https://linux-hardware.org/?probe=726f5ed51f) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [e0307085f3](https://linux-hardware.org/?probe=e0307085f3) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | [e7b42c85f1](https://linux-hardware.org/?probe=e7b42c85f1) | Sep 17, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [abd7f0d0a1](https://linux-hardware.org/?probe=abd7f0d0a1) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [c8208bc767](https://linux-hardware.org/?probe=c8208bc767) | Sep 17, 2021 |
| MSI           | GF75 Thin 9SC               | [47a6cd4031](https://linux-hardware.org/?probe=47a6cd4031) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | [8d4eff5ca2](https://linux-hardware.org/?probe=8d4eff5ca2) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [f226485da3](https://linux-hardware.org/?probe=f226485da3) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [643fafdceb](https://linux-hardware.org/?probe=643fafdceb) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | [e801613095](https://linux-hardware.org/?probe=e801613095) | Sep 17, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [fb0c3317e3](https://linux-hardware.org/?probe=fb0c3317e3) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [5282f852aa](https://linux-hardware.org/?probe=5282f852aa) | Sep 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dd5496fa35](https://linux-hardware.org/?probe=dd5496fa35) | Sep 17, 2021 |
| Timi          | TM1801                      | [d0919977cb](https://linux-hardware.org/?probe=d0919977cb) | Sep 17, 2021 |
| MSI           | Bravo 15 A4DDR              | [722f184570](https://linux-hardware.org/?probe=722f184570) | Sep 17, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | X751LD                      | [df29a592fb](https://linux-hardware.org/?probe=df29a592fb) | Sep 16, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ee258307b1](https://linux-hardware.org/?probe=ee258307b1) | Sep 15, 2021 |
| PC Special... | Standard                    | [1454a60100](https://linux-hardware.org/?probe=1454a60100) | Sep 15, 2021 |
| Lenovo        | ThinkPad E460 20EUA00AAC    | [c7d8dc11ca](https://linux-hardware.org/?probe=c7d8dc11ca) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | [576b90b734](https://linux-hardware.org/?probe=576b90b734) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | [e9c177240a](https://linux-hardware.org/?probe=e9c177240a) | Sep 15, 2021 |
| Acer          | AO725                       | [68eeff0c2f](https://linux-hardware.org/?probe=68eeff0c2f) | Sep 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [730c0eebf9](https://linux-hardware.org/?probe=730c0eebf9) | Sep 14, 2021 |
| Lenovo        | V330-15IKB 81AX             | [a062985645](https://linux-hardware.org/?probe=a062985645) | Sep 14, 2021 |
| Dell          | Inspiron 15-3567            | [7e486cd179](https://linux-hardware.org/?probe=7e486cd179) | Sep 14, 2021 |
| Aquarius      | NS585                       | [7f88a77812](https://linux-hardware.org/?probe=7f88a77812) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Aquarius      | NS585                       | [f2363c7d5e](https://linux-hardware.org/?probe=f2363c7d5e) | Sep 14, 2021 |
| Acer          | Aspire A315-23              | [01008b3cfd](https://linux-hardware.org/?probe=01008b3cfd) | Sep 13, 2021 |
| Apple         | MacBookAir7,1               | [cd3844f542](https://linux-hardware.org/?probe=cd3844f542) | Sep 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [eb55a1f000](https://linux-hardware.org/?probe=eb55a1f000) | Sep 13, 2021 |
| HP            | Notebook                    | [17f4133e28](https://linux-hardware.org/?probe=17f4133e28) | Sep 13, 2021 |
| Lenovo        | G50-45 80E3                 | [51cf32f87c](https://linux-hardware.org/?probe=51cf32f87c) | Sep 12, 2021 |
| Lenovo        | ThinkPad E14 20RB0028BR     | [8b1b3a98ba](https://linux-hardware.org/?probe=8b1b3a98ba) | Sep 12, 2021 |
| ASUSTek       | M3N                         | [28a5b48a05](https://linux-hardware.org/?probe=28a5b48a05) | Sep 12, 2021 |
| ASUSTek       | M3N                         | [04307947ae](https://linux-hardware.org/?probe=04307947ae) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Apple         | MacBookAir7,1               | [795f6bba58](https://linux-hardware.org/?probe=795f6bba58) | Sep 10, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b95c1b013e](https://linux-hardware.org/?probe=b95c1b013e) | Sep 10, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2377281799](https://linux-hardware.org/?probe=2377281799) | Sep 09, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [13d65a1a4e](https://linux-hardware.org/?probe=13d65a1a4e) | Sep 09, 2021 |
| ASUSTek       | X540NA                      | [f14257cc20](https://linux-hardware.org/?probe=f14257cc20) | Sep 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8433dfbbb9](https://linux-hardware.org/?probe=8433dfbbb9) | Sep 09, 2021 |
| Apple         | MacBookPro10,1              | [1ff67401db](https://linux-hardware.org/?probe=1ff67401db) | Sep 09, 2021 |
| LG Electro... | A410-K.BE43P1               | [7add887914](https://linux-hardware.org/?probe=7add887914) | Sep 08, 2021 |
| Apple         | MacBookAir7,2               | [5c6f3696b2](https://linux-hardware.org/?probe=5c6f3696b2) | Sep 08, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d21daec9ea](https://linux-hardware.org/?probe=d21daec9ea) | Sep 08, 2021 |
| Lenovo        | ThinkPad T430 2349D10       | [11ab5d413d](https://linux-hardware.org/?probe=11ab5d413d) | Sep 08, 2021 |
| Lenovo        | ThinkPad X230 2325B12       | [a55f42da78](https://linux-hardware.org/?probe=a55f42da78) | Sep 08, 2021 |
| ASUSTek       | K52F                        | [b1f04036d8](https://linux-hardware.org/?probe=b1f04036d8) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | [19cfc85441](https://linux-hardware.org/?probe=19cfc85441) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| ASUSTek       | K52F                        | [0d72cf73ac](https://linux-hardware.org/?probe=0d72cf73ac) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | [498dd20152](https://linux-hardware.org/?probe=498dd20152) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6fc35e97d8](https://linux-hardware.org/?probe=6fc35e97d8) | Sep 07, 2021 |
| Dell          | Latitude 7480               | [844ab8df38](https://linux-hardware.org/?probe=844ab8df38) | Sep 06, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9256f3fece](https://linux-hardware.org/?probe=9256f3fece) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | [7f6c0d6337](https://linux-hardware.org/?probe=7f6c0d6337) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | [e6ea97df06](https://linux-hardware.org/?probe=e6ea97df06) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | [3aedb68952](https://linux-hardware.org/?probe=3aedb68952) | Sep 06, 2021 |
| Samsung       | NC10                        | [98ba59d155](https://linux-hardware.org/?probe=98ba59d155) | Sep 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e42726b566](https://linux-hardware.org/?probe=e42726b566) | Sep 06, 2021 |
| Dell          | Vostro 5490                 | [b6e28c84c8](https://linux-hardware.org/?probe=b6e28c84c8) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Toshiba       | Satellite C55-B             | [fe8833475a](https://linux-hardware.org/?probe=fe8833475a) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | [0a1850f760](https://linux-hardware.org/?probe=0a1850f760) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | [4ba7363e9e](https://linux-hardware.org/?probe=4ba7363e9e) | Sep 05, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [18fe596fba](https://linux-hardware.org/?probe=18fe596fba) | Sep 04, 2021 |
| HP            | Presario CQ62               | [4cdec89015](https://linux-hardware.org/?probe=4cdec89015) | Sep 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [9e235c4228](https://linux-hardware.org/?probe=9e235c4228) | Sep 04, 2021 |
| Dell          | Inspiron 1525               | [0e32e6945b](https://linux-hardware.org/?probe=0e32e6945b) | Sep 03, 2021 |
| Apple         | MacBookAir7,2               | [db35296aa1](https://linux-hardware.org/?probe=db35296aa1) | Sep 03, 2021 |
| Acer          | Aspire A315-23              | [fafd031d1f](https://linux-hardware.org/?probe=fafd031d1f) | Sep 03, 2021 |
| Apple         | MacBookAir7,2               | [1449c0a9cd](https://linux-hardware.org/?probe=1449c0a9cd) | Sep 02, 2021 |
| ASUSTek       | UX303LNB                    | [e0756d7ae6](https://linux-hardware.org/?probe=e0756d7ae6) | Sep 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5d183d4587](https://linux-hardware.org/?probe=5d183d4587) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [666c4fef08](https://linux-hardware.org/?probe=666c4fef08) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [d6ee033eb7](https://linux-hardware.org/?probe=d6ee033eb7) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | [28fbb3d82d](https://linux-hardware.org/?probe=28fbb3d82d) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | [27c2ebc917](https://linux-hardware.org/?probe=27c2ebc917) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | [1d9e3a7503](https://linux-hardware.org/?probe=1d9e3a7503) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | [97c9e2dc1f](https://linux-hardware.org/?probe=97c9e2dc1f) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | [f1cad98694](https://linux-hardware.org/?probe=f1cad98694) | Sep 01, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [d542a6b8f9](https://linux-hardware.org/?probe=d542a6b8f9) | Sep 01, 2021 |
| Acer          | Aspire A315-23              | [12a5a0f9c5](https://linux-hardware.org/?probe=12a5a0f9c5) | Sep 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3267eec643](https://linux-hardware.org/?probe=3267eec643) | Sep 01, 2021 |
| Timi          | TM1613                      | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | [bc224fb15f](https://linux-hardware.org/?probe=bc224fb15f) | Aug 31, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [9510c18df6](https://linux-hardware.org/?probe=9510c18df6) | Aug 31, 2021 |
| HP            | Laptop 15s-eq1xxx           | [783955d696](https://linux-hardware.org/?probe=783955d696) | Aug 31, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | [db94fcaf10](https://linux-hardware.org/?probe=db94fcaf10) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | [baf38e8736](https://linux-hardware.org/?probe=baf38e8736) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Fujitsu Si... | LIFEBOOK S6420              | [b26e82328a](https://linux-hardware.org/?probe=b26e82328a) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | [70835c3aa7](https://linux-hardware.org/?probe=70835c3aa7) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | [3e22f55c7b](https://linux-hardware.org/?probe=3e22f55c7b) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | [b73b366bb6](https://linux-hardware.org/?probe=b73b366bb6) | Aug 30, 2021 |
| Toshiba       | Satellite C55-B             | [e1b2dc4810](https://linux-hardware.org/?probe=e1b2dc4810) | Aug 30, 2021 |
| Apple         | MacBookAir7,1               | [e94ab065a3](https://linux-hardware.org/?probe=e94ab065a3) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | [b1425fa900](https://linux-hardware.org/?probe=b1425fa900) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | [b5a84f215b](https://linux-hardware.org/?probe=b5a84f215b) | Aug 30, 2021 |
| Dell          | Latitude E6330              | [95d65375e2](https://linux-hardware.org/?probe=95d65375e2) | Aug 30, 2021 |
| Lenovo        | ThinkPad T61 7661BF3        | [69b6d76471](https://linux-hardware.org/?probe=69b6d76471) | Aug 30, 2021 |
| ASUSTek       | K56CB                       | [1a44fc7e8f](https://linux-hardware.org/?probe=1a44fc7e8f) | Aug 29, 2021 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [6fcfbde79d](https://linux-hardware.org/?probe=6fcfbde79d) | Aug 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [17ae4593ea](https://linux-hardware.org/?probe=17ae4593ea) | Aug 28, 2021 |
| HP            | EliteBook 840 G3            | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| Apple         | MacBookAir7,2               | [d215521170](https://linux-hardware.org/?probe=d215521170) | Aug 27, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [2c85ec0205](https://linux-hardware.org/?probe=2c85ec0205) | Aug 27, 2021 |
| Lenovo        | ThinkPad T440p 20AN006GU... | [bca7704bb0](https://linux-hardware.org/?probe=bca7704bb0) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | [14747d88b3](https://linux-hardware.org/?probe=14747d88b3) | Aug 26, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [87904cbe92](https://linux-hardware.org/?probe=87904cbe92) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [1c2e910793](https://linux-hardware.org/?probe=1c2e910793) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | [4a69118897](https://linux-hardware.org/?probe=4a69118897) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | [474216fba9](https://linux-hardware.org/?probe=474216fba9) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [76d9383f33](https://linux-hardware.org/?probe=76d9383f33) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [213d3f817b](https://linux-hardware.org/?probe=213d3f817b) | Aug 26, 2021 |
| YJKC          | vBOOK Plus RVP7             | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Gigabyte      | AORUS 15G KB                | [6afefe68d7](https://linux-hardware.org/?probe=6afefe68d7) | Aug 26, 2021 |
| HP            | ProBook 4530s               | [2b4cab4d7c](https://linux-hardware.org/?probe=2b4cab4d7c) | Aug 25, 2021 |
| Dell          | Inspiron 3537               | [7bab6dd9db](https://linux-hardware.org/?probe=7bab6dd9db) | Aug 25, 2021 |
| HP            | ProBook 450 G7              | [a2f161dee0](https://linux-hardware.org/?probe=a2f161dee0) | Aug 25, 2021 |
| HUAWEI        | WRT-WX9                     | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [3da8591ac6](https://linux-hardware.org/?probe=3da8591ac6) | Aug 25, 2021 |
| HP            | 630                         | [004d2b364d](https://linux-hardware.org/?probe=004d2b364d) | Aug 25, 2021 |
| Dell          | Latitude 7490               | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Apple         | MacBookAir7,2               | [65d82bc8e7](https://linux-hardware.org/?probe=65d82bc8e7) | Aug 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e1bd0ec7fd](https://linux-hardware.org/?probe=e1bd0ec7fd) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | [8a72f87e7b](https://linux-hardware.org/?probe=8a72f87e7b) | Aug 24, 2021 |
| Apple         | MacBookAir7,1               | [1f257714a9](https://linux-hardware.org/?probe=1f257714a9) | Aug 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [102aea0211](https://linux-hardware.org/?probe=102aea0211) | Aug 24, 2021 |
| HP            | Laptop 15s-fq2xxx           | [f755838fd8](https://linux-hardware.org/?probe=f755838fd8) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | [5cc74103a8](https://linux-hardware.org/?probe=5cc74103a8) | Aug 24, 2021 |
| HP            | 250 G4                      | [5d47aa9804](https://linux-hardware.org/?probe=5d47aa9804) | Aug 24, 2021 |
| ASUSTek       | UX430UAR                    | [77ce457de4](https://linux-hardware.org/?probe=77ce457de4) | Aug 24, 2021 |
| HP            | Laptop 14-cm0xxx            | [df0fa8e968](https://linux-hardware.org/?probe=df0fa8e968) | Aug 24, 2021 |
| Sony          | VPCF115FM                   | [9f9abf79b2](https://linux-hardware.org/?probe=9f9abf79b2) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [8a88eabb1c](https://linux-hardware.org/?probe=8a88eabb1c) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [c4ecd51a21](https://linux-hardware.org/?probe=c4ecd51a21) | Aug 23, 2021 |
| HP            | Laptop 15s-eq1xxx           | [1c9d3bb8b4](https://linux-hardware.org/?probe=1c9d3bb8b4) | Aug 23, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [14af647cc5](https://linux-hardware.org/?probe=14af647cc5) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [5bc9372587](https://linux-hardware.org/?probe=5bc9372587) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [8bcb9e62e1](https://linux-hardware.org/?probe=8bcb9e62e1) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [6c44c4f7e3](https://linux-hardware.org/?probe=6c44c4f7e3) | Aug 23, 2021 |
| Google        | Enguarde                    | [12a2003770](https://linux-hardware.org/?probe=12a2003770) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [7f190e4ed2](https://linux-hardware.org/?probe=7f190e4ed2) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [2db5cafda3](https://linux-hardware.org/?probe=2db5cafda3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [abcab36e0c](https://linux-hardware.org/?probe=abcab36e0c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f3ccb91568](https://linux-hardware.org/?probe=f3ccb91568) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [0d8fa16f47](https://linux-hardware.org/?probe=0d8fa16f47) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [680e8106ec](https://linux-hardware.org/?probe=680e8106ec) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [c18b0215e9](https://linux-hardware.org/?probe=c18b0215e9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [fcc821b941](https://linux-hardware.org/?probe=fcc821b941) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [59f760dbb9](https://linux-hardware.org/?probe=59f760dbb9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [e22a8e2ea4](https://linux-hardware.org/?probe=e22a8e2ea4) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [4fc69342da](https://linux-hardware.org/?probe=4fc69342da) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f2fcae5696](https://linux-hardware.org/?probe=f2fcae5696) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [2f823b2f52](https://linux-hardware.org/?probe=2f823b2f52) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [adf5b71331](https://linux-hardware.org/?probe=adf5b71331) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [618c1c7838](https://linux-hardware.org/?probe=618c1c7838) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [0dff1056d5](https://linux-hardware.org/?probe=0dff1056d5) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [fb0cf0a7a3](https://linux-hardware.org/?probe=fb0cf0a7a3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6b9f550210](https://linux-hardware.org/?probe=6b9f550210) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [4b22440e91](https://linux-hardware.org/?probe=4b22440e91) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6bab7cdc7c](https://linux-hardware.org/?probe=6bab7cdc7c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [d2a08022bd](https://linux-hardware.org/?probe=d2a08022bd) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f39d94cf1b](https://linux-hardware.org/?probe=f39d94cf1b) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [e35bbfda2d](https://linux-hardware.org/?probe=e35bbfda2d) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [60170675ca](https://linux-hardware.org/?probe=60170675ca) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [64a6aa27db](https://linux-hardware.org/?probe=64a6aa27db) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [06b1dab7a0](https://linux-hardware.org/?probe=06b1dab7a0) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [cec5c36945](https://linux-hardware.org/?probe=cec5c36945) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6f38e35f9a](https://linux-hardware.org/?probe=6f38e35f9a) | Aug 23, 2021 |
| HP            | EliteBook 840 G4            | [ebe40b3244](https://linux-hardware.org/?probe=ebe40b3244) | Aug 22, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d98bdb0d1c](https://linux-hardware.org/?probe=d98bdb0d1c) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d688bffa01](https://linux-hardware.org/?probe=d688bffa01) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [3d52884b6e](https://linux-hardware.org/?probe=3d52884b6e) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | [57b847b12c](https://linux-hardware.org/?probe=57b847b12c) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | [db4b9878fa](https://linux-hardware.org/?probe=db4b9878fa) | Aug 22, 2021 |
| Dell          | Inspiron 6000               | [67c6b36361](https://linux-hardware.org/?probe=67c6b36361) | Aug 22, 2021 |
| Dell          | Inspiron 3593               | [dfed5d8b7a](https://linux-hardware.org/?probe=dfed5d8b7a) | Aug 21, 2021 |
| Dell          | Latitude E7470              | [e954672cb2](https://linux-hardware.org/?probe=e954672cb2) | Aug 21, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HP            | 14s-dq2003nw                | [f4dcd70da5](https://linux-hardware.org/?probe=f4dcd70da5) | Aug 21, 2021 |
| Lenovo        | ThinkPad E570 20H500B4GE    | [be964b556b](https://linux-hardware.org/?probe=be964b556b) | Aug 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [5ecdc39ac1](https://linux-hardware.org/?probe=5ecdc39ac1) | Aug 21, 2021 |
| Dell          | Precision 7520              | [372d627a69](https://linux-hardware.org/?probe=372d627a69) | Aug 21, 2021 |
| Apple         | MacBookAir7,1               | [daa01f79aa](https://linux-hardware.org/?probe=daa01f79aa) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [a96a7ada4f](https://linux-hardware.org/?probe=a96a7ada4f) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [c8305c0d4c](https://linux-hardware.org/?probe=c8305c0d4c) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [77359352d0](https://linux-hardware.org/?probe=77359352d0) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | [5312257240](https://linux-hardware.org/?probe=5312257240) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [75e262ddba](https://linux-hardware.org/?probe=75e262ddba) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [bd216572a3](https://linux-hardware.org/?probe=bd216572a3) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [e57aeadfef](https://linux-hardware.org/?probe=e57aeadfef) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [7211565d4a](https://linux-hardware.org/?probe=7211565d4a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [1c490522df](https://linux-hardware.org/?probe=1c490522df) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [16f0b9c14a](https://linux-hardware.org/?probe=16f0b9c14a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [691bb379e5](https://linux-hardware.org/?probe=691bb379e5) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [fe880ac0c8](https://linux-hardware.org/?probe=fe880ac0c8) | Aug 20, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [a5a146e42a](https://linux-hardware.org/?probe=a5a146e42a) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | [c60ef3fa1e](https://linux-hardware.org/?probe=c60ef3fa1e) | Aug 20, 2021 |
| Timi          | TM1612                      | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [2a61705899](https://linux-hardware.org/?probe=2a61705899) | Aug 20, 2021 |
| SLIMBOOK      | TITAN                       | [a2abd981d1](https://linux-hardware.org/?probe=a2abd981d1) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [1ce6738560](https://linux-hardware.org/?probe=1ce6738560) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [e134a1f7c3](https://linux-hardware.org/?probe=e134a1f7c3) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [87fa430aab](https://linux-hardware.org/?probe=87fa430aab) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [c989eac16b](https://linux-hardware.org/?probe=c989eac16b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [3169e477dd](https://linux-hardware.org/?probe=3169e477dd) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [5fcb7fdb26](https://linux-hardware.org/?probe=5fcb7fdb26) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [7afbba35b0](https://linux-hardware.org/?probe=7afbba35b0) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [f1d159bbd1](https://linux-hardware.org/?probe=f1d159bbd1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [38e8211556](https://linux-hardware.org/?probe=38e8211556) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [bd587e5998](https://linux-hardware.org/?probe=bd587e5998) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [3fa54711ec](https://linux-hardware.org/?probe=3fa54711ec) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [4a7f287161](https://linux-hardware.org/?probe=4a7f287161) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [fed5f28778](https://linux-hardware.org/?probe=fed5f28778) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [0ba8599928](https://linux-hardware.org/?probe=0ba8599928) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [e31d43b39d](https://linux-hardware.org/?probe=e31d43b39d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [703cdcf766](https://linux-hardware.org/?probe=703cdcf766) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [9b8ce55c3d](https://linux-hardware.org/?probe=9b8ce55c3d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [2b4af51f46](https://linux-hardware.org/?probe=2b4af51f46) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [b802b4a25b](https://linux-hardware.org/?probe=b802b4a25b) | Aug 18, 2021 |
| Google        | Enguarde                    | [cb421b796b](https://linux-hardware.org/?probe=cb421b796b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [f6c7230675](https://linux-hardware.org/?probe=f6c7230675) | Aug 18, 2021 |
| Google        | Enguarde                    | [7116839a4b](https://linux-hardware.org/?probe=7116839a4b) | Aug 18, 2021 |
| Google        | Enguarde                    | [04817bfb7f](https://linux-hardware.org/?probe=04817bfb7f) | Aug 18, 2021 |
| Google        | Enguarde                    | [92b401a705](https://linux-hardware.org/?probe=92b401a705) | Aug 18, 2021 |
| Google        | Enguarde                    | [f2a438a9be](https://linux-hardware.org/?probe=f2a438a9be) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [c9239b499b](https://linux-hardware.org/?probe=c9239b499b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [b708a97ef1](https://linux-hardware.org/?probe=b708a97ef1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [31dc792a8b](https://linux-hardware.org/?probe=31dc792a8b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [76a48b344d](https://linux-hardware.org/?probe=76a48b344d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [244aba47d4](https://linux-hardware.org/?probe=244aba47d4) | Aug 18, 2021 |
| Google        | Enguarde                    | [b2391216c6](https://linux-hardware.org/?probe=b2391216c6) | Aug 18, 2021 |
| Google        | Enguarde                    | [53b311c24c](https://linux-hardware.org/?probe=53b311c24c) | Aug 18, 2021 |
| Google        | Enguarde                    | [61de56951c](https://linux-hardware.org/?probe=61de56951c) | Aug 18, 2021 |
| Google        | Enguarde                    | [7fd7f1ea77](https://linux-hardware.org/?probe=7fd7f1ea77) | Aug 18, 2021 |
| Google        | Enguarde                    | [2a090f8b2a](https://linux-hardware.org/?probe=2a090f8b2a) | Aug 18, 2021 |
| Google        | Enguarde                    | [62e4ff915a](https://linux-hardware.org/?probe=62e4ff915a) | Aug 18, 2021 |
| Google        | Enguarde                    | [eada085a33](https://linux-hardware.org/?probe=eada085a33) | Aug 18, 2021 |
| Google        | Enguarde                    | [474e20b9f2](https://linux-hardware.org/?probe=474e20b9f2) | Aug 18, 2021 |
| ASUSTek       | UX305CA                     | [6ab6beca67](https://linux-hardware.org/?probe=6ab6beca67) | Aug 18, 2021 |
| HP            | EliteBook 820 G1            | [c7155dfa07](https://linux-hardware.org/?probe=c7155dfa07) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [451fe761a6](https://linux-hardware.org/?probe=451fe761a6) | Aug 18, 2021 |
| Google        | Enguarde                    | [dd0de8b832](https://linux-hardware.org/?probe=dd0de8b832) | Aug 17, 2021 |
| Google        | Enguarde                    | [a6ac2782a6](https://linux-hardware.org/?probe=a6ac2782a6) | Aug 17, 2021 |
| Google        | Enguarde                    | [d32e974941](https://linux-hardware.org/?probe=d32e974941) | Aug 17, 2021 |
| Google        | Enguarde                    | [fe90c1da98](https://linux-hardware.org/?probe=fe90c1da98) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [c3d98780bf](https://linux-hardware.org/?probe=c3d98780bf) | Aug 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4b38b9e598](https://linux-hardware.org/?probe=4b38b9e598) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2c30321150](https://linux-hardware.org/?probe=2c30321150) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2f6317ebc5](https://linux-hardware.org/?probe=2f6317ebc5) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [707606ff5e](https://linux-hardware.org/?probe=707606ff5e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [0c43bb89c0](https://linux-hardware.org/?probe=0c43bb89c0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [fcb540b848](https://linux-hardware.org/?probe=fcb540b848) | Aug 17, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [46240d5ef9](https://linux-hardware.org/?probe=46240d5ef9) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [6e85db6058](https://linux-hardware.org/?probe=6e85db6058) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2e26440865](https://linux-hardware.org/?probe=2e26440865) | Aug 17, 2021 |
| Apple         | MacBook7,1                  | [5ad65197ad](https://linux-hardware.org/?probe=5ad65197ad) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [c185e120f1](https://linux-hardware.org/?probe=c185e120f1) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [ee22c0dcc0](https://linux-hardware.org/?probe=ee22c0dcc0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b3fd5bee39](https://linux-hardware.org/?probe=b3fd5bee39) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [d68e571cd0](https://linux-hardware.org/?probe=d68e571cd0) | Aug 17, 2021 |
| Dell          | Latitude 7480               | [49272ed382](https://linux-hardware.org/?probe=49272ed382) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [28c2f85e9c](https://linux-hardware.org/?probe=28c2f85e9c) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [1f8c3f9487](https://linux-hardware.org/?probe=1f8c3f9487) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [9f6a737d07](https://linux-hardware.org/?probe=9f6a737d07) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [4eb4afec6b](https://linux-hardware.org/?probe=4eb4afec6b) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [5949002919](https://linux-hardware.org/?probe=5949002919) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b0d4ba09f6](https://linux-hardware.org/?probe=b0d4ba09f6) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [12377bdf65](https://linux-hardware.org/?probe=12377bdf65) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [f345284082](https://linux-hardware.org/?probe=f345284082) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [6229638b59](https://linux-hardware.org/?probe=6229638b59) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b95e1787ff](https://linux-hardware.org/?probe=b95e1787ff) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [f1d344625b](https://linux-hardware.org/?probe=f1d344625b) | Aug 17, 2021 |
| Google        | Enguarde                    | [4d7eaa38ba](https://linux-hardware.org/?probe=4d7eaa38ba) | Aug 17, 2021 |
| Google        | Enguarde                    | [8be28c3080](https://linux-hardware.org/?probe=8be28c3080) | Aug 17, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| Google        | Enguarde                    | [cfdf77fbd9](https://linux-hardware.org/?probe=cfdf77fbd9) | Aug 17, 2021 |
| Google        | Enguarde                    | [6e84dfb541](https://linux-hardware.org/?probe=6e84dfb541) | Aug 17, 2021 |
| Google        | Enguarde                    | [2549683d9f](https://linux-hardware.org/?probe=2549683d9f) | Aug 17, 2021 |
| Dell          | Latitude 7410               | [f7f6e5a4d5](https://linux-hardware.org/?probe=f7f6e5a4d5) | Aug 17, 2021 |
| ASUSTek       | 1225B                       | [1dd6877b22](https://linux-hardware.org/?probe=1dd6877b22) | Aug 17, 2021 |
| Google        | Enguarde                    | [0bdebdb178](https://linux-hardware.org/?probe=0bdebdb178) | Aug 16, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [3a489f9498](https://linux-hardware.org/?probe=3a489f9498) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [635d3ab3e5](https://linux-hardware.org/?probe=635d3ab3e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [2e04ae93d1](https://linux-hardware.org/?probe=2e04ae93d1) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [dffcb4d4f6](https://linux-hardware.org/?probe=dffcb4d4f6) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [e3816a3d3a](https://linux-hardware.org/?probe=e3816a3d3a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d76cf98938](https://linux-hardware.org/?probe=d76cf98938) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [fc7b752ce3](https://linux-hardware.org/?probe=fc7b752ce3) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [346d3ca919](https://linux-hardware.org/?probe=346d3ca919) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [eb7cdde4b5](https://linux-hardware.org/?probe=eb7cdde4b5) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ae1b239645](https://linux-hardware.org/?probe=ae1b239645) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d7e9112089](https://linux-hardware.org/?probe=d7e9112089) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [35ab4c3075](https://linux-hardware.org/?probe=35ab4c3075) | Aug 16, 2021 |
| Lenovo        | ThinkPad E490 20N8001EUS    | [40796d62c2](https://linux-hardware.org/?probe=40796d62c2) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [1fa30fb77a](https://linux-hardware.org/?probe=1fa30fb77a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [81f2a65461](https://linux-hardware.org/?probe=81f2a65461) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [a54d2e496c](https://linux-hardware.org/?probe=a54d2e496c) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d0581c16e9](https://linux-hardware.org/?probe=d0581c16e9) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4704dd7dc2](https://linux-hardware.org/?probe=4704dd7dc2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [2d48e28c72](https://linux-hardware.org/?probe=2d48e28c72) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [dcded26792](https://linux-hardware.org/?probe=dcded26792) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [de06f0cb03](https://linux-hardware.org/?probe=de06f0cb03) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [3171a06ab2](https://linux-hardware.org/?probe=3171a06ab2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [154d3f4aac](https://linux-hardware.org/?probe=154d3f4aac) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 20J10046US      | [6943b835e5](https://linux-hardware.org/?probe=6943b835e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [56e2f75dab](https://linux-hardware.org/?probe=56e2f75dab) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7e070c3cee](https://linux-hardware.org/?probe=7e070c3cee) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [be42bbb09a](https://linux-hardware.org/?probe=be42bbb09a) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [42a5d4fb48](https://linux-hardware.org/?probe=42a5d4fb48) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [845219864e](https://linux-hardware.org/?probe=845219864e) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [99531c5564](https://linux-hardware.org/?probe=99531c5564) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [7e2e8d1364](https://linux-hardware.org/?probe=7e2e8d1364) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [c9b0773c42](https://linux-hardware.org/?probe=c9b0773c42) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [947e3524e3](https://linux-hardware.org/?probe=947e3524e3) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [a30c87c3fe](https://linux-hardware.org/?probe=a30c87c3fe) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [edaac7af9f](https://linux-hardware.org/?probe=edaac7af9f) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [94047a5fdc](https://linux-hardware.org/?probe=94047a5fdc) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [ccd9ef4a72](https://linux-hardware.org/?probe=ccd9ef4a72) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [97aab17694](https://linux-hardware.org/?probe=97aab17694) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [3112135337](https://linux-hardware.org/?probe=3112135337) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [8da303b571](https://linux-hardware.org/?probe=8da303b571) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [449ea4adf6](https://linux-hardware.org/?probe=449ea4adf6) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [5bd9662328](https://linux-hardware.org/?probe=5bd9662328) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [079ef9affe](https://linux-hardware.org/?probe=079ef9affe) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [9e81b88eb8](https://linux-hardware.org/?probe=9e81b88eb8) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [7b614dd679](https://linux-hardware.org/?probe=7b614dd679) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| Dell          | G3 3590                     | [05e11ad38d](https://linux-hardware.org/?probe=05e11ad38d) | Aug 16, 2021 |
| HP            | 630                         | [a57ed15001](https://linux-hardware.org/?probe=a57ed15001) | Aug 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [31fcb375f4](https://linux-hardware.org/?probe=31fcb375f4) | Aug 15, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | [e3fd79d228](https://linux-hardware.org/?probe=e3fd79d228) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | [daf1b7a963](https://linux-hardware.org/?probe=daf1b7a963) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [0b7f4b2da5](https://linux-hardware.org/?probe=0b7f4b2da5) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | [f6b6388040](https://linux-hardware.org/?probe=f6b6388040) | Aug 14, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| Dell          | Latitude 7490               | [6ca174eba8](https://linux-hardware.org/?probe=6ca174eba8) | Aug 14, 2021 |
| Dell          | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| Google        | Enguarde                    | [cac72ff077](https://linux-hardware.org/?probe=cac72ff077) | Aug 13, 2021 |
| Google        | Enguarde                    | [8c489e2c59](https://linux-hardware.org/?probe=8c489e2c59) | Aug 13, 2021 |
| Google        | Enguarde                    | [d79905590c](https://linux-hardware.org/?probe=d79905590c) | Aug 13, 2021 |
| Google        | Enguarde                    | [7efce8d06b](https://linux-hardware.org/?probe=7efce8d06b) | Aug 13, 2021 |
| Google        | Enguarde                    | [c53a0803e7](https://linux-hardware.org/?probe=c53a0803e7) | Aug 13, 2021 |
| Google        | Enguarde                    | [410a4b2e26](https://linux-hardware.org/?probe=410a4b2e26) | Aug 13, 2021 |
| Google        | Enguarde                    | [cbc9f75923](https://linux-hardware.org/?probe=cbc9f75923) | Aug 13, 2021 |
| Google        | Enguarde                    | [4ca322af56](https://linux-hardware.org/?probe=4ca322af56) | Aug 13, 2021 |
| Google        | Enguarde                    | [2af4090c36](https://linux-hardware.org/?probe=2af4090c36) | Aug 13, 2021 |
| Google        | Enguarde                    | [43919a91f3](https://linux-hardware.org/?probe=43919a91f3) | Aug 12, 2021 |
| Google        | Enguarde                    | [c93dcd9531](https://linux-hardware.org/?probe=c93dcd9531) | Aug 12, 2021 |
| Google        | Enguarde                    | [8e7147d832](https://linux-hardware.org/?probe=8e7147d832) | Aug 12, 2021 |
| Apple         | MacBookAir7,1               | [65a4eb9f2c](https://linux-hardware.org/?probe=65a4eb9f2c) | Aug 12, 2021 |
| Google        | Enguarde                    | [e9f95dc0ed](https://linux-hardware.org/?probe=e9f95dc0ed) | Aug 12, 2021 |
| Google        | Enguarde                    | [3b5b9d1698](https://linux-hardware.org/?probe=3b5b9d1698) | Aug 12, 2021 |
| Google        | Enguarde                    | [e423d1eee6](https://linux-hardware.org/?probe=e423d1eee6) | Aug 12, 2021 |
| Google        | Enguarde                    | [1f00600e9b](https://linux-hardware.org/?probe=1f00600e9b) | Aug 12, 2021 |
| Google        | Enguarde                    | [88adc88ccd](https://linux-hardware.org/?probe=88adc88ccd) | Aug 12, 2021 |
| Notebook      | NL4x_NL5xLU                 | [82a8b9c657](https://linux-hardware.org/?probe=82a8b9c657) | Aug 12, 2021 |
| Google        | Enguarde                    | [2434eac448](https://linux-hardware.org/?probe=2434eac448) | Aug 12, 2021 |
| Google        | Enguarde                    | [d766910df0](https://linux-hardware.org/?probe=d766910df0) | Aug 12, 2021 |
| Google        | Enguarde                    | [c0516ce965](https://linux-hardware.org/?probe=c0516ce965) | Aug 12, 2021 |
| Google        | Enguarde                    | [728007c621](https://linux-hardware.org/?probe=728007c621) | Aug 12, 2021 |
| Google        | Enguarde                    | [b808ac5856](https://linux-hardware.org/?probe=b808ac5856) | Aug 12, 2021 |
| Google        | Enguarde                    | [326cc3aae3](https://linux-hardware.org/?probe=326cc3aae3) | Aug 12, 2021 |
| Google        | Enguarde                    | [1fddcb2525](https://linux-hardware.org/?probe=1fddcb2525) | Aug 12, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| Dell          | G7 7790                     | [99dd172940](https://linux-hardware.org/?probe=99dd172940) | Aug 12, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | [2bc14051d8](https://linux-hardware.org/?probe=2bc14051d8) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [cbe8c5170f](https://linux-hardware.org/?probe=cbe8c5170f) | Aug 12, 2021 |
| HP            | ProBook 4530s               | [14a78c65a1](https://linux-hardware.org/?probe=14a78c65a1) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| Samsung       | 300E5M/300E5L               | [4139a3a855](https://linux-hardware.org/?probe=4139a3a855) | Aug 11, 2021 |
| Notebook      | N13_N140ZU                  | [cbaecf1d3e](https://linux-hardware.org/?probe=cbaecf1d3e) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | [48573ed425](https://linux-hardware.org/?probe=48573ed425) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [cabe0ebbc8](https://linux-hardware.org/?probe=cabe0ebbc8) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [1dcbf85471](https://linux-hardware.org/?probe=1dcbf85471) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [0c67490330](https://linux-hardware.org/?probe=0c67490330) | Aug 10, 2021 |
| Dell          | Precision 3551              | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| HP            | 250 G4                      | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d650ff0c3e](https://linux-hardware.org/?probe=d650ff0c3e) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| Dell          | Inspiron ME051              | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | B51-35 80LH                 | [5f87168a65](https://linux-hardware.org/?probe=5f87168a65) | Aug 10, 2021 |
| Apple         | MacBookAir7,1               | [6ab68482c0](https://linux-hardware.org/?probe=6ab68482c0) | Aug 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS3R80... | [fbc29e2063](https://linux-hardware.org/?probe=fbc29e2063) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [e4ce236efd](https://linux-hardware.org/?probe=e4ce236efd) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1c26f935e6](https://linux-hardware.org/?probe=1c26f935e6) | Aug 09, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [538a15f3cc](https://linux-hardware.org/?probe=538a15f3cc) | Aug 09, 2021 |
| HP            | 2000                        | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| Lenovo        | ThinkPad T580 20L9001AUS    | [65e201224c](https://linux-hardware.org/?probe=65e201224c) | Aug 09, 2021 |
| MSI           | GP60 2PE                    | [516f3cd4e5](https://linux-hardware.org/?probe=516f3cd4e5) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Lenovo        | ThinkPad T410 2537E49       | [ea10aead92](https://linux-hardware.org/?probe=ea10aead92) | Aug 08, 2021 |
| Dell          | XPS 13 9370                 | [575a84d010](https://linux-hardware.org/?probe=575a84d010) | Aug 08, 2021 |
| Clevo         | W55xEU                      | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| Lenovo        | ThinkPad W500 406152G       | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| Acer          | TravelMate 5720             | [43aae04fa6](https://linux-hardware.org/?probe=43aae04fa6) | Aug 08, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | [1c7914d660](https://linux-hardware.org/?probe=1c7914d660) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c5ef006a35](https://linux-hardware.org/?probe=c5ef006a35) | Aug 08, 2021 |
| Acer          | Swift SF314-51              | [88fa728376](https://linux-hardware.org/?probe=88fa728376) | Aug 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e18202a558](https://linux-hardware.org/?probe=e18202a558) | Aug 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| Clevo         | P170EM                      | [f101b2b318](https://linux-hardware.org/?probe=f101b2b318) | Aug 07, 2021 |
| Acer          | Aspire E5-575               | [3caca4f238](https://linux-hardware.org/?probe=3caca4f238) | Aug 07, 2021 |
| Acer          | Aspire E5-571P              | [1dbaeef7d2](https://linux-hardware.org/?probe=1dbaeef7d2) | Aug 07, 2021 |
| Google        | Parrot                      | [2efb04c61c](https://linux-hardware.org/?probe=2efb04c61c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T61 7661BK7        | [bbabc03a27](https://linux-hardware.org/?probe=bbabc03a27) | Aug 07, 2021 |
| Sony          | VPCF21AFX                   | [40aa5144f7](https://linux-hardware.org/?probe=40aa5144f7) | Aug 07, 2021 |
| Lenovo        | ThinkPad T450 20BUS16700    | [8123256638](https://linux-hardware.org/?probe=8123256638) | Aug 07, 2021 |
| Dell          | XPS 13 9350                 | [e82d4c3561](https://linux-hardware.org/?probe=e82d4c3561) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [412f800d01](https://linux-hardware.org/?probe=412f800d01) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [69696c0e3a](https://linux-hardware.org/?probe=69696c0e3a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| HP            | 630                         | [b2d03b8717](https://linux-hardware.org/?probe=b2d03b8717) | Aug 07, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [368abe4066](https://linux-hardware.org/?probe=368abe4066) | Aug 07, 2021 |
| HP            | 630                         | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Dell          | Latitude E7240              | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | 3085B                       | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [a3914442ca](https://linux-hardware.org/?probe=a3914442ca) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| Google        | Stout                       | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| Dell          | Inspiron 5570               | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | [acff56e8e3](https://linux-hardware.org/?probe=acff56e8e3) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | [704ead0e75](https://linux-hardware.org/?probe=704ead0e75) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| Casper        | C17B                        | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| Apple         | MacBookPro11,4              | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| HP            | Laptop 15s-fq1xxx           | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Intel         | W7645                       | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d7722f9bbf](https://linux-hardware.org/?probe=d7722f9bbf) | Jul 12, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3eceba473e](https://linux-hardware.org/?probe=3eceba473e) | Jul 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [85da1219ad](https://linux-hardware.org/?probe=85da1219ad) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | [bccfe7e145](https://linux-hardware.org/?probe=bccfe7e145) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | [73a418aad6](https://linux-hardware.org/?probe=73a418aad6) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| Acer          | Aspire E5-573               | [d946214a58](https://linux-hardware.org/?probe=d946214a58) | Jul 06, 2021 |
| Dell          | Latitude E6330              | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| HP            | Compaq 6830s                | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| ASUSTek       | K42Jv                       | [88ee690bb2](https://linux-hardware.org/?probe=88ee690bb2) | Jun 30, 2021 |
| Sony          | SVE1512G1RB                 | [41dd93f0c7](https://linux-hardware.org/?probe=41dd93f0c7) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| Acer          | Nitro AN515-51              | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Dell          | Inspiron 3501               | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| MSI           | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| Dell          | Precision 3560              | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| HP            | ProBook 455 G1              | [c334d50b1f](https://linux-hardware.org/?probe=c334d50b1f) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Acer          | Aspire ES1-132              | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| Acer          | Aspire A315-23G             | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Acer          | Aspire V3-331               | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Acer          | Aspire A315-23              | [0de49e4ceb](https://linux-hardware.org/?probe=0de49e4ceb) | Jun 11, 2021 |
| Dell          | Latitude E7470              | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| Clevo         | W250ENQ / W270ENQ           | [95fe5984c2](https://linux-hardware.org/?probe=95fe5984c2) | Jun 09, 2021 |
| Clevo         | W250ENQ / W270ENQ           | [b992eee8b5](https://linux-hardware.org/?probe=b992eee8b5) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d71fba3e59](https://linux-hardware.org/?probe=d71fba3e59) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| Acer          | Aspire A315-23              | [31547cbbcf](https://linux-hardware.org/?probe=31547cbbcf) | May 31, 2021 |
| Acer          | Aspire A315-23              | [4392e54288](https://linux-hardware.org/?probe=4392e54288) | May 31, 2021 |
| Acer          | Aspire A315-23              | [2fda3b392d](https://linux-hardware.org/?probe=2fda3b392d) | May 31, 2021 |
| Acer          | Aspire A315-23              | [41c4d75b72](https://linux-hardware.org/?probe=41c4d75b72) | May 31, 2021 |
| Acer          | Aspire A315-23              | [8b834e3fc0](https://linux-hardware.org/?probe=8b834e3fc0) | May 31, 2021 |
| Acer          | Aspire A315-23              | [8932eef460](https://linux-hardware.org/?probe=8932eef460) | May 31, 2021 |
| Toshiba       | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| MSI           | CX700                       | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Dell          | XPS 13 9310                 | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Lenovo        | Z710 20250                  | [76d72eb45f](https://linux-hardware.org/?probe=76d72eb45f) | May 27, 2021 |
| Aquarius      | NS585                       | [e2035017ff](https://linux-hardware.org/?probe=e2035017ff) | May 26, 2021 |
| Aquarius      | NS585                       | [d2b5b53798](https://linux-hardware.org/?probe=d2b5b53798) | May 26, 2021 |
| Aquarius      | NS585                       | [1c84a98f48](https://linux-hardware.org/?probe=1c84a98f48) | May 26, 2021 |
| Acer          | Aspire A315-23G             | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23              | [834e2e7b7e](https://linux-hardware.org/?probe=834e2e7b7e) | May 24, 2021 |
| Acer          | Aspire A315-23G             | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Acer          | Aspire A315-23              | [71c9c1e86f](https://linux-hardware.org/?probe=71c9c1e86f) | May 21, 2021 |
| HP            | EliteBook 840 G1            | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Acer          | Aspire A315-23G             | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7480               | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Acer          | Aspire A315-23G             | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| HP            | Compaq Presario C700        | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| ASUSTek       | T100TAS                     | [0b8e360f8a](https://linux-hardware.org/?probe=0b8e360f8a) | May 07, 2021 |
| HP            | Split 13 x2 PC              | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| MSI           | Bravo 15 A4DDR              | [372d11517d](https://linux-hardware.org/?probe=372d11517d) | Apr 28, 2021 |
| Lenovo        | G550 20023                  | [69b57eec89](https://linux-hardware.org/?probe=69b57eec89) | Apr 27, 2021 |
| Lenovo        | IdeaPad Z500 20202          | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Acer          | Aspire 5560                 | [853337664f](https://linux-hardware.org/?probe=853337664f) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Dell          | Latitude E6330              | [d2a06d1cde](https://linux-hardware.org/?probe=d2a06d1cde) | Apr 22, 2021 |
| MSI           | Bravo 15 A4DDR              | [60eb0d02a7](https://linux-hardware.org/?probe=60eb0d02a7) | Apr 21, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 3442               | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Dell          | Inspiron 5468               | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [92866f8994](https://linux-hardware.org/?probe=92866f8994) | Apr 17, 2021 |
| HP            | Pavilion g6                 | [7a88de99e8](https://linux-hardware.org/?probe=7a88de99e8) | Apr 16, 2021 |
| HP            | Pavilion g6                 | [8f9f4e211d](https://linux-hardware.org/?probe=8f9f4e211d) | Apr 15, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| HP            | Pavilion g6                 | [d3e2f03de0](https://linux-hardware.org/?probe=d3e2f03de0) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| HP            | Pavilion 17                 | [9bd4ef879a](https://linux-hardware.org/?probe=9bd4ef879a) | Apr 12, 2021 |
| Sony          | VPCEJ3S1R                   | [a57c607409](https://linux-hardware.org/?probe=a57c607409) | Apr 12, 2021 |
| Dell          | Inspiron 5721               | [d90f3a34d1](https://linux-hardware.org/?probe=d90f3a34d1) | Apr 08, 2021 |
| Dell          | Inspiron 5721               | [a0bb6867cd](https://linux-hardware.org/?probe=a0bb6867cd) | Apr 07, 2021 |
| Dell          | Latitude E6330              | [46855c6116](https://linux-hardware.org/?probe=46855c6116) | Apr 07, 2021 |
| Notebook      | N650DU                      | [34efc4fdfe](https://linux-hardware.org/?probe=34efc4fdfe) | Apr 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 20HRC... | [354cd6e94e](https://linux-hardware.org/?probe=354cd6e94e) | Apr 02, 2021 |
| Acer          | TravelMate P259-MG          | [9acbd94cd7](https://linux-hardware.org/?probe=9acbd94cd7) | Apr 01, 2021 |
| Dell          | Inspiron 5721               | [b93f919e23](https://linux-hardware.org/?probe=b93f919e23) | Mar 31, 2021 |
| Dell          | Inspiron 5721               | [2e925f1ee2](https://linux-hardware.org/?probe=2e925f1ee2) | Mar 30, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [8d09fd5fad](https://linux-hardware.org/?probe=8d09fd5fad) | Mar 29, 2021 |
| Dell          | Inspiron 5721               | [d22bc80177](https://linux-hardware.org/?probe=d22bc80177) | Mar 29, 2021 |
| Micro Elec... | MG-VCTR002-2060             | [3724755eea](https://linux-hardware.org/?probe=3724755eea) | Mar 28, 2021 |
| HP            | ProBook 4520s               | [7577a208f6](https://linux-hardware.org/?probe=7577a208f6) | Mar 22, 2021 |
| Lenovo        | B50-30 20382                | [2d50a5e736](https://linux-hardware.org/?probe=2d50a5e736) | Mar 21, 2021 |
| Dell          | Inspiron 5548               | [f20eacbf5c](https://linux-hardware.org/?probe=f20eacbf5c) | Mar 18, 2021 |
| Dell          | Inspiron 5548               | [e3d85d4006](https://linux-hardware.org/?probe=e3d85d4006) | Mar 15, 2021 |
| Dell          | Inspiron 5548               | [3c8f0ff2d4](https://linux-hardware.org/?probe=3c8f0ff2d4) | Mar 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [bcdd60dc85](https://linux-hardware.org/?probe=bcdd60dc85) | Mar 14, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [bd5d97f7e7](https://linux-hardware.org/?probe=bd5d97f7e7) | Mar 07, 2021 |
| Acer          | Aspire E5-521               | [d2ee782761](https://linux-hardware.org/?probe=d2ee782761) | Mar 07, 2021 |
| ASUSTek       | K53E                        | [f84c0f2b1b](https://linux-hardware.org/?probe=f84c0f2b1b) | Mar 05, 2021 |
| Micro Elec... | MG-VCTR002-2060             | [f86910b3b3](https://linux-hardware.org/?probe=f86910b3b3) | Mar 05, 2021 |
| ASUSTek       | K53E                        | [8a98e99c2f](https://linux-hardware.org/?probe=8a98e99c2f) | Mar 05, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [db2b8a39be](https://linux-hardware.org/?probe=db2b8a39be) | Mar 03, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Dell          | XPS 13 9310                 | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| HP            | Pavilion Notebook           | [88c5aee182](https://linux-hardware.org/?probe=88c5aee182) | Mar 02, 2021 |
| Lenovo        | V570 HuronRiver Platform    | [d93b0955fa](https://linux-hardware.org/?probe=d93b0955fa) | Feb 27, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [744852fa69](https://linux-hardware.org/?probe=744852fa69) | Feb 25, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [720734ca06](https://linux-hardware.org/?probe=720734ca06) | Feb 25, 2021 |
| Dell          | Inspiron 5759               | [3710e0320f](https://linux-hardware.org/?probe=3710e0320f) | Feb 24, 2021 |
| HP            | Laptop 15-da0xxx            | [3bb9f3d0f3](https://linux-hardware.org/?probe=3bb9f3d0f3) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [88bab7f6e7](https://linux-hardware.org/?probe=88bab7f6e7) | Feb 22, 2021 |
| HP            | ENVY Notebook               | [e4cc508565](https://linux-hardware.org/?probe=e4cc508565) | Feb 21, 2021 |
| Lenovo        | B50-30 20382                | [6642872403](https://linux-hardware.org/?probe=6642872403) | Feb 19, 2021 |
| LG Electro... | A410-K.BE43P1               | [da5067a065](https://linux-hardware.org/?probe=da5067a065) | Feb 18, 2021 |
| Dell          | Latitude E6440              | [ce086f8df0](https://linux-hardware.org/?probe=ce086f8df0) | Feb 18, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [77da992403](https://linux-hardware.org/?probe=77da992403) | Feb 14, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [2e19efe5b1](https://linux-hardware.org/?probe=2e19efe5b1) | Feb 12, 2021 |
| Dell          | Inspiron 5759               | [e7c528c9be](https://linux-hardware.org/?probe=e7c528c9be) | Feb 11, 2021 |
| Dell          | XPS 13 9310                 | [97e14d7021](https://linux-hardware.org/?probe=97e14d7021) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | [954514a52a](https://linux-hardware.org/?probe=954514a52a) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | [67f2a70d2a](https://linux-hardware.org/?probe=67f2a70d2a) | Feb 09, 2021 |
| Dell          | Inspiron 5759               | [cd72d5cd68](https://linux-hardware.org/?probe=cd72d5cd68) | Feb 09, 2021 |
| Dell          | Latitude 7400               | [32c7787bcb](https://linux-hardware.org/?probe=32c7787bcb) | Feb 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [9b82b49d40](https://linux-hardware.org/?probe=9b82b49d40) | Feb 04, 2021 |
| Unknown       | Unknown                     | [6acba7c545](https://linux-hardware.org/?probe=6acba7c545) | Feb 03, 2021 |
| Unknown       | Unknown                     | [ad10dd6be0](https://linux-hardware.org/?probe=ad10dd6be0) | Feb 03, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [67cfeeb58a](https://linux-hardware.org/?probe=67cfeeb58a) | Jan 31, 2021 |
| Unknown       | Unknown                     | [ea0d120a2b](https://linux-hardware.org/?probe=ea0d120a2b) | Jan 31, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [288a08d946](https://linux-hardware.org/?probe=288a08d946) | Jan 26, 2021 |
| Positivo      | C14CR21                     | [0807ce46f1](https://linux-hardware.org/?probe=0807ce46f1) | Jan 19, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4bdbb16f3d](https://linux-hardware.org/?probe=4bdbb16f3d) | Jan 17, 2021 |
| Acer          | Aspire 5750Z                | [14ca9bb504](https://linux-hardware.org/?probe=14ca9bb504) | Jan 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [286214a4e2](https://linux-hardware.org/?probe=286214a4e2) | Jan 15, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1ec8c1ccd1](https://linux-hardware.org/?probe=1ec8c1ccd1) | Jan 13, 2021 |
| Dell          | Vostro 5490                 | [6afcc11fef](https://linux-hardware.org/?probe=6afcc11fef) | Jan 08, 2021 |
| Dell          | Vostro 5490                 | [1708c28c7b](https://linux-hardware.org/?probe=1708c28c7b) | Jan 08, 2021 |
| Dell          | Latitude E6330              | [1d09a49510](https://linux-hardware.org/?probe=1d09a49510) | Jan 04, 2021 |
| Lenovo        | ThinkPad E480 20KN001NMX    | [4f055c0cf5](https://linux-hardware.org/?probe=4f055c0cf5) | Oct 08, 2019 |
| Dell          | Inspiron 11-3168            | [3831423c95](https://linux-hardware.org/?probe=3831423c95) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | [4343600da2](https://linux-hardware.org/?probe=4343600da2) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | [a1f5874ef6](https://linux-hardware.org/?probe=a1f5874ef6) | Jun 30, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-8-amd64             | 548       | 65.55%  |
| 5.10.0-7-amd64             | 95        | 11.36%  |
| 5.10.0-9-amd64             | 46        | 5.5%    |
| 5.10.0-2-amd64             | 29        | 3.47%   |
| 5.10.0-6-amd64             | 26        | 3.11%   |
| 5.10.0-3-amd64             | 12        | 1.44%   |
| 5.10.0-8-686-pae           | 9         | 1.08%   |
| 5.10.0-5-amd64             | 6         | 0.72%   |
| 5.10.0-4-amd64             | 5         | 0.6%    |
| 5.10.0-1-amd64             | 5         | 0.6%    |
| 5.10.0-8-686               | 4         | 0.48%   |
| 5.12.0-19.3-liquorix-amd64 | 3         | 0.36%   |
| 5.10.0-9-686-pae           | 3         | 0.36%   |
| 5.10.0-9-686               | 2         | 0.24%   |
| 4.19.0-14-amd64            | 2         | 0.24%   |
| 5.14.9-xanmod1-cacule      | 1         | 0.12%   |
| 5.14.6-ndmnet-sid-1        | 1         | 0.12%   |
| 5.14.0-rc3-prygun          | 1         | 0.12%   |
| 5.14.0-2mx-amd64           | 1         | 0.12%   |
| 5.14.0-2-amd64             | 1         | 0.12%   |
| 5.14.0-14.1-liquorix-amd64 | 1         | 0.12%   |
| 5.14.0+                    | 1         | 0.12%   |
| 5.13.8-xanmod1             | 1         | 0.12%   |
| 5.13.8                     | 1         | 0.12%   |
| 5.13.5-xanmod1             | 1         | 0.12%   |
| 5.13.4-e5520               | 1         | 0.12%   |
| 5.13.3                     | 1         | 0.12%   |
| 5.13.15-xanmod1            | 1         | 0.12%   |
| 5.13.0-13.1-liquorix-amd64 | 1         | 0.12%   |
| 5.12.14-amd64-desktop      | 1         | 0.12%   |
| 5.12.10                    | 1         | 0.12%   |
| 5.12.1                     | 1         | 0.12%   |
| 5.12.0-9.2-liquorix-amd64  | 1         | 0.12%   |
| 5.12.0-14.2-liquorix-amd64 | 1         | 0.12%   |
| 5.11.9+                    | 1         | 0.12%   |
| 5.11.22-1-pve              | 1         | 0.12%   |
| 5.11.15-051115-generic     | 1         | 0.12%   |
| 5.11.14                    | 1         | 0.12%   |
| 5.11.0-rc6                 | 1         | 0.12%   |
| 5.11.0-11.1-liquorix-amd64 | 1         | 0.12%   |
| 5.10.40-ismynik            | 1         | 0.12%   |
| 5.10.18-xanmod1            | 1         | 0.12%   |
| 5.10.10-64                 | 1         | 0.12%   |
| 5.10.0-kali3-amd64         | 1         | 0.12%   |
| 5.10.0-io7-amd64           | 1         | 0.12%   |
| 5.10.0-6-rt-amd64          | 1         | 0.12%   |
| 5.10.0-6-686               | 1         | 0.12%   |
| 5.10.0-0.bpo.5-amd64       | 1         | 0.12%   |
| 5.1.12-xanmod8             | 1         | 0.12%   |
| 5.1.0                      | 1         | 0.12%   |
| 4.19.181-z580322           | 1         | 0.12%   |
| 4.19.0-6-amd64             | 1         | 0.12%   |
| 4.19.0-17-686              | 1         | 0.12%   |
| 4.19.0-16-amd64            | 1         | 0.12%   |
| 4.19.0-16-686-pae          | 1         | 0.12%   |
| 3.10.54                    | 1         | 0.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 768       | 95.17%  |
| 5.14.0   | 5         | 0.62%   |
| 4.19.0   | 5         | 0.62%   |
| 5.12.0   | 4         | 0.5%    |
| 5.13.8   | 2         | 0.25%   |
| 5.11.0   | 2         | 0.25%   |
| 5.14.9   | 1         | 0.12%   |
| 5.14.6   | 1         | 0.12%   |
| 5.13.5   | 1         | 0.12%   |
| 5.13.4   | 1         | 0.12%   |
| 5.13.3   | 1         | 0.12%   |
| 5.13.15  | 1         | 0.12%   |
| 5.13.0   | 1         | 0.12%   |
| 5.12.14  | 1         | 0.12%   |
| 5.12.10  | 1         | 0.12%   |
| 5.12.1   | 1         | 0.12%   |
| 5.11.9   | 1         | 0.12%   |
| 5.11.22  | 1         | 0.12%   |
| 5.11.15  | 1         | 0.12%   |
| 5.11.14  | 1         | 0.12%   |
| 5.10.40  | 1         | 0.12%   |
| 5.10.18  | 1         | 0.12%   |
| 5.10.10  | 1         | 0.12%   |
| 5.1.12   | 1         | 0.12%   |
| 5.1.0    | 1         | 0.12%   |
| 4.19.181 | 1         | 0.12%   |
| 3.10.54  | 1         | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 771       | 95.66%  |
| 5.14    | 7         | 0.87%   |
| 5.12    | 7         | 0.87%   |
| 5.13    | 6         | 0.74%   |
| 5.11    | 6         | 0.74%   |
| 4.19    | 6         | 0.74%   |
| 5.1     | 2         | 0.25%   |
| 3.10    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 781       | 97.38%  |
| i686   | 20        | 2.49%   |
| armv7l | 1         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 310       | 38.32%  |
| GNOME            | 198       | 24.47%  |
| KDE5             | 105       | 12.98%  |
| XFCE             | 68        | 8.41%   |
| MATE             | 26        | 3.21%   |
| KDE              | 16        | 1.98%   |
| LXDE             | 15        | 1.85%   |
| i3               | 13        | 1.61%   |
| Cinnamon         | 13        | 1.61%   |
| X-Cinnamon       | 12        | 1.48%   |
| LXQt             | 9         | 1.11%   |
| lightdm-xsession | 6         | 0.74%   |
| GNOME Flashback  | 5         | 0.62%   |
| Openbox          | 3         | 0.37%   |
| GNOME Classic    | 3         | 0.37%   |
| Enlightenment    | 2         | 0.25%   |
| sway             | 1         | 0.12%   |
| ICEWM            | 1         | 0.12%   |
| default          | 1         | 0.12%   |
| Deepin           | 1         | 0.12%   |
| awesome          | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 341       | 41.94%  |
| Unknown | 288       | 35.42%  |
| Wayland | 157       | 19.31%  |
| Tty     | 27        | 3.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 389       | 48.08%  |
| GDM     | 173       | 21.38%  |
| SDDM    | 110       | 13.6%   |
| TDM     | 71        | 8.78%   |
| LightDM | 59        | 7.29%   |
| GDM3    | 4         | 0.49%   |
| XDM     | 2         | 0.25%   |
| KDM     | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 223       | 27.7%   |
| en_US   | 209       | 25.96%  |
| ru_RU   | 87        | 10.81%  |
| en_GB   | 35        | 4.35%   |
| es_ES   | 33        | 4.1%    |
| fr_FR   | 25        | 3.11%   |
| de_DE   | 25        | 3.11%   |
| pt_BR   | 18        | 2.24%   |
| it_IT   | 16        | 1.99%   |
| pl_PL   | 14        | 1.74%   |
| en_IN   | 7         | 0.87%   |
| en_CA   | 7         | 0.87%   |
| zh_CN   | 6         | 0.75%   |
| es_MX   | 6         | 0.75%   |
| tr_TR   | 5         | 0.62%   |
| sv_SE   | 5         | 0.62%   |
| en_AU   | 5         | 0.62%   |
| de_AT   | 5         | 0.62%   |
| C       | 5         | 0.62%   |
| pt_PT   | 4         | 0.5%    |
| ja_JP   | 4         | 0.5%    |
| de_CH   | 4         | 0.5%    |
| cs_CZ   | 4         | 0.5%    |
| uk_UA   | 3         | 0.37%   |
| nn_NO   | 3         | 0.37%   |
| fi_FI   | 3         | 0.37%   |
| es_AR   | 3         | 0.37%   |
| en_ZA   | 3         | 0.37%   |
| en_IE   | 3         | 0.37%   |
| zh_TW   | 2         | 0.25%   |
| ru_UA   | 2         | 0.25%   |
| nl_NL   | 2         | 0.25%   |
| hu_HU   | 2         | 0.25%   |
| es_CO   | 2         | 0.25%   |
| en_SG   | 2         | 0.25%   |
| en_DK   | 2         | 0.25%   |
| bg_BG   | 2         | 0.25%   |
| sk_SK   | 1         | 0.12%   |
| ro_RO   | 1         | 0.12%   |
| nl_BE   | 1         | 0.12%   |
| nb_NO   | 1         | 0.12%   |
| hr_HR   | 1         | 0.12%   |
| gl_ES   | 1         | 0.12%   |
| fr_BE   | 1         | 0.12%   |
| et_EE   | 1         | 0.12%   |
| es_UY   | 1         | 0.12%   |
| es_GT   | 1         | 0.12%   |
| es_EC   | 1         | 0.12%   |
| es_CR   | 1         | 0.12%   |
| es_CL   | 1         | 0.12%   |
| eo      | 1         | 0.12%   |
| en_ZM   | 1         | 0.12%   |
| en_SI   | 1         | 0.12%   |
| en_NZ   | 1         | 0.12%   |
| en_HK   | 1         | 0.12%   |
| ca_ES   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 555       | 68.77%  |
| BIOS | 252       | 31.23%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 459       | 57.16%  |
| Overlay | 304       | 37.86%  |
| Btrfs   | 26        | 3.24%   |
| Xfs     | 7         | 0.87%   |
| Zfs     | 2         | 0.25%   |
| Unknown | 2         | 0.25%   |
| Tmpfs   | 1         | 0.12%   |
| Rootfs  | 1         | 0.12%   |
| Ext3    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 575       | 71.43%  |
| MBR     | 141       | 17.52%  |
| Unknown | 89        | 11.06%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 748       | 92.8%   |
| Yes       | 58        | 7.2%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 609       | 75.56%  |
| Yes       | 197       | 24.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 196       | 24.44%  |
| Apple                | 159       | 19.83%  |
| Hewlett-Packard      | 102       | 12.72%  |
| Dell                 | 90        | 11.22%  |
| ASUSTek Computer     | 56        | 6.98%   |
| Acer                 | 56        | 6.98%   |
| Google               | 49        | 6.11%   |
| MSI                  | 12        | 1.5%    |
| Aquarius             | 12        | 1.5%    |
| Toshiba              | 7         | 0.87%   |
| Samsung Electronics  | 7         | 0.87%   |
| Sony                 | 6         | 0.75%   |
| HUAWEI               | 6         | 0.75%   |
| Timi                 | 4         | 0.5%    |
| Notebook             | 4         | 0.5%    |
| Clevo                | 4         | 0.5%    |
| Gigabyte Technology  | 3         | 0.37%   |
| Fujitsu              | 3         | 0.37%   |
| SLIMBOOK             | 2         | 0.25%   |
| PC Specialist        | 2         | 0.25%   |
| LG Electronics       | 2         | 0.25%   |
| Unknown              | 2         | 0.25%   |
| YJKC                 | 1         | 0.12%   |
| UNOWHY               | 1         | 0.12%   |
| TUXEDO               | 1         | 0.12%   |
| TrekStor             | 1         | 0.12%   |
| Schenker             | 1         | 0.12%   |
| Quanta               | 1         | 0.12%   |
| Positivo             | 1         | 0.12%   |
| Pegatron             | 1         | 0.12%   |
| Panasonic            | 1         | 0.12%   |
| Packard Bell         | 1         | 0.12%   |
| Monster              | 1         | 0.12%   |
| Micro Electronics    | 1         | 0.12%   |
| Jumper               | 1         | 0.12%   |
| Intel Client Systems | 1         | 0.12%   |
| Intel                | 1         | 0.12%   |
| Fujitsu Siemens      | 1         | 0.12%   |
| Compal               | 1         | 0.12%   |
| Casper               | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Apple MacBookAir7,1                     | 75        | 9.35%   |
| Apple MacBookAir7,2                     | 67        | 8.35%   |
| Google Enguarde                         | 47        | 5.86%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US   | 15        | 1.87%   |
| Acer Aspire A315-23                     | 15        | 1.87%   |
| Aquarius NS585                          | 12        | 1.5%    |
| HP EliteBook 8460p                      | 5         | 0.62%   |
| Dell Latitude 7480                      | 5         | 0.62%   |
| Dell XPS 13 9310                        | 4         | 0.5%    |
| Lenovo ThinkPad E475 20H40006US         | 3         | 0.37%   |
| Lenovo IdeaPad L340-15API 81LW          | 3         | 0.37%   |
| HUAWEI NBLK-WAX9X                       | 3         | 0.37%   |
| HP Pavilion Gaming Laptop 15-ec2xxx     | 3         | 0.37%   |
| HP Pavilion g6                          | 3         | 0.37%   |
| Timi TM1613                             | 2         | 0.25%   |
| MSI Bravo 15 A4DDR                      | 2         | 0.25%   |
| Lenovo V510-15IKB 80WQ                  | 2         | 0.25%   |
| Lenovo ThinkPad T490 20N2CTO1WW         | 2         | 0.25%   |
| Lenovo ThinkBook 14 G2 ARE 20VF         | 2         | 0.25%   |
| Lenovo IdeaPad 700-15ISK 80RU           | 2         | 0.25%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 2         | 0.25%   |
| Lenovo IdeaPad 330-15ARR 81D2           | 2         | 0.25%   |
| Lenovo IdeaPad 3 14ADA05 81W0           | 2         | 0.25%   |
| Lenovo G50-80 80E5                      | 2         | 0.25%   |
| Lenovo B50-30 20382                     | 2         | 0.25%   |
| HP ProBook 4530s                        | 2         | 0.25%   |
| HP Pavilion Gaming Laptop 15-ec1xxx     | 2         | 0.25%   |
| HP Notebook                             | 2         | 0.25%   |
| HP Laptop 15s-fq2xxx                    | 2         | 0.25%   |
| HP Laptop 15s-eq1xxx                    | 2         | 0.25%   |
| HP Compaq nx6125 (PZ849UA#ABA)          | 2         | 0.25%   |
| HP Compaq nx6110 (PZ065UA#ABA)          | 2         | 0.25%   |
| Dell XPS 13 9370                        | 2         | 0.25%   |
| Dell XPS 13 7390                        | 2         | 0.25%   |
| Dell Vostro 5490                        | 2         | 0.25%   |
| Dell Vostro 5471                        | 2         | 0.25%   |
| Dell Precision 3540                     | 2         | 0.25%   |
| Dell Latitude E7470                     | 2         | 0.25%   |
| Dell Latitude E7240                     | 2         | 0.25%   |
| Dell Latitude E6330                     | 2         | 0.25%   |
| Dell Inspiron 5570                      | 2         | 0.25%   |
| Dell Inspiron 3793                      | 2         | 0.25%   |
| Dell Inspiron 1525                      | 2         | 0.25%   |
| Dell Inspiron 15 7000 Gaming            | 2         | 0.25%   |
| Dell G3 3590                            | 2         | 0.25%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA | 2         | 0.25%   |
| ASUS TUF GAMING FX504GD_FX80GD          | 2         | 0.25%   |
| ASUS 1005HA                             | 2         | 0.25%   |
| Apple MacBookPro14,1                    | 2         | 0.25%   |
| Apple MacBook7,1                        | 2         | 0.25%   |
| Apple MacBook5,2                        | 2         | 0.25%   |
| Apple MacBook3,1                        | 2         | 0.25%   |
| Acer Aspire A515-51G                    | 2         | 0.25%   |
| Acer Aspire 5560                        | 2         | 0.25%   |
| Acer Aspire 5315                        | 2         | 0.25%   |
| Unknown                                 | 2         | 0.25%   |
| YJKC vBOOK Plus                         | 1         | 0.12%   |
| UNOWHY Y13G002S4EI                      | 1         | 0.12%   |
| TUXEDO Pulse 15 Gen1                    | 1         | 0.12%   |
| TrekStor Surfbook A13                   | 1         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Apple MacBookAir7  | 142       | 17.71%  |
| Lenovo ThinkPad    | 138       | 17.21%  |
| Google Enguarde    | 47        | 5.86%   |
| Acer Aspire        | 40        | 4.99%   |
| Lenovo IdeaPad     | 34        | 4.24%   |
| Dell Inspiron      | 34        | 4.24%   |
| Dell Latitude      | 21        | 2.62%   |
| HP EliteBook       | 19        | 2.37%   |
| HP ProBook         | 17        | 2.12%   |
| HP Pavilion        | 17        | 2.12%   |
| Dell XPS           | 16        | 2%      |
| HP Laptop          | 14        | 1.75%   |
| Aquarius NS585     | 12        | 1.5%    |
| HP Compaq          | 9         | 1.12%   |
| Dell Vostro        | 7         | 0.87%   |
| Dell Precision     | 7         | 0.87%   |
| Toshiba Satellite  | 6         | 0.75%   |
| ASUS ZenBook       | 6         | 0.75%   |
| ASUS ROG           | 6         | 0.75%   |
| ASUS VivoBook      | 5         | 0.62%   |
| Acer TravelMate    | 5         | 0.62%   |
| Lenovo ThinkBook   | 4         | 0.5%    |
| HP 250             | 4         | 0.5%    |
| ASUS TUF           | 4         | 0.5%    |
| Acer Swift         | 4         | 0.5%    |
| HUAWEI NBLK-WAX9X  | 3         | 0.37%   |
| Fujitsu LIFEBOOK   | 3         | 0.37%   |
| Dell G3            | 3         | 0.37%   |
| ASUS ASUS          | 3         | 0.37%   |
| Acer Nitro         | 3         | 0.37%   |
| Timi TM1613        | 2         | 0.25%   |
| MSI Bravo          | 2         | 0.25%   |
| Lenovo V510-15IKB  | 2         | 0.25%   |
| Lenovo G50-80      | 2         | 0.25%   |
| Lenovo B50-30      | 2         | 0.25%   |
| HP ZBook           | 2         | 0.25%   |
| HP Presario        | 2         | 0.25%   |
| HP OMEN            | 2         | 0.25%   |
| HP Notebook        | 2         | 0.25%   |
| HP ENVY            | 2         | 0.25%   |
| Gigabyte AERO      | 2         | 0.25%   |
| ASUS 1005HA        | 2         | 0.25%   |
| Apple MacBookPro14 | 2         | 0.25%   |
| Apple MacBookPro11 | 2         | 0.25%   |
| Apple MacBook7     | 2         | 0.25%   |
| Apple MacBook5     | 2         | 0.25%   |
| Apple MacBook3     | 2         | 0.25%   |
| Unknown            | 2         | 0.25%   |
| YJKC vBOOK         | 1         | 0.12%   |
| UNOWHY Y13G002S4EI | 1         | 0.12%   |
| TUXEDO Pulse       | 1         | 0.12%   |
| TrekStor Surfbook  | 1         | 0.12%   |
| Toshiba PORTEGE    | 1         | 0.12%   |
| Timi TM1801        | 1         | 0.12%   |
| Timi TM1612        | 1         | 0.12%   |
| Sony VPCF21AFX     | 1         | 0.12%   |
| Sony VPCF115FM     | 1         | 0.12%   |
| Sony VPCEJ3S1R     | 1         | 0.12%   |
| Sony VGN-CR21Z     | 1         | 0.12%   |
| Sony SVE1512G1RB   | 1         | 0.12%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 208       | 25.94%  |
| 2021    | 185       | 23.07%  |
| 2019    | 130       | 16.21%  |
| 2018    | 46        | 5.74%   |
| 2012    | 31        | 3.87%   |
| 2013    | 29        | 3.62%   |
| 2011    | 29        | 3.62%   |
| 2008    | 25        | 3.12%   |
| 2016    | 24        | 2.99%   |
| 2014    | 21        | 2.62%   |
| 2015    | 20        | 2.49%   |
| 2017    | 15        | 1.87%   |
| 2009    | 15        | 1.87%   |
| 2010    | 12        | 1.5%    |
| 2007    | 3         | 0.37%   |
| 2006    | 3         | 0.37%   |
| 2005    | 3         | 0.37%   |
| 2004    | 2         | 0.25%   |
| Unknown | 1         | 0.12%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 802       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 741       | 92.16%  |
| Enabled  | 63        | 7.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 753       | 93.89%  |
| Yes  | 49        | 6.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 275       | 34.25%  |
| 3.01-4.0    | 202       | 25.16%  |
| 16.01-24.0  | 131       | 16.31%  |
| 8.01-16.0   | 98        | 12.2%   |
| 32.01-64.0  | 37        | 4.61%   |
| 1.01-2.0    | 28        | 3.49%   |
| 2.01-3.0    | 11        | 1.37%   |
| 0.51-1.0    | 9         | 1.12%   |
| 64.01-256.0 | 6         | 0.75%   |
| 0.01-0.5    | 4         | 0.5%    |
| 24.01-32.0  | 2         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 373       | 45.32%  |
| 2.01-3.0   | 145       | 17.62%  |
| 0.51-1.0   | 96        | 11.66%  |
| 4.01-8.0   | 90        | 10.94%  |
| 3.01-4.0   | 63        | 7.65%   |
| 8.01-16.0  | 29        | 3.52%   |
| 0.01-0.5   | 25        | 3.04%   |
| 32.01-64.0 | 1         | 0.12%   |
| 16.01-24.0 | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 649       | 80.52%  |
| 2      | 141       | 17.49%  |
| 3      | 10        | 1.24%   |
| 4      | 4         | 0.5%    |
| 0      | 2         | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 624       | 77.81%  |
| Yes       | 178       | 22.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 521       | 64.96%  |
| No        | 281       | 35.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 793       | 98.88%  |
| No        | 9         | 1.12%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 686       | 85.32%  |
| No        | 118       | 14.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 303       | 37.69%  |
| Russia       | 84        | 10.45%  |
| Germany      | 40        | 4.98%   |
| Spain        | 39        | 4.85%   |
| France       | 37        | 4.6%    |
| Brazil       | 24        | 2.99%   |
| Poland       | 21        | 2.61%   |
| UK           | 19        | 2.36%   |
| Ukraine      | 17        | 2.11%   |
| Italy        | 13        | 1.62%   |
| Netherlands  | 11        | 1.37%   |
| Canada       | 11        | 1.37%   |
| Sweden       | 10        | 1.24%   |
| China        | 10        | 1.24%   |
| Switzerland  | 9         | 1.12%   |
| Portugal     | 8         | 1%      |
| India        | 8         | 1%      |
| Austria      | 8         | 1%      |
| Turkey       | 7         | 0.87%   |
| Mexico       | 7         | 0.87%   |
| Czechia      | 7         | 0.87%   |
| Argentina    | 6         | 0.75%   |
| Norway       | 5         | 0.62%   |
| Greece       | 5         | 0.62%   |
| Finland      | 5         | 0.62%   |
| Belarus      | 5         | 0.62%   |
| Australia    | 5         | 0.62%   |
| Thailand     | 4         | 0.5%    |
| Romania      | 4         | 0.5%    |
| Kazakhstan   | 4         | 0.5%    |
| Japan        | 4         | 0.5%    |
| Belgium      | 4         | 0.5%    |
| South Africa | 3         | 0.37%   |
| Philippines  | 3         | 0.37%   |
| Ireland      | 3         | 0.37%   |
| Indonesia    | 3         | 0.37%   |
| Ecuador      | 3         | 0.37%   |
| Bulgaria     | 3         | 0.37%   |
| Taiwan       | 2         | 0.25%   |
| Slovenia     | 2         | 0.25%   |
| Latvia       | 2         | 0.25%   |
| Hungary      | 2         | 0.25%   |
| Guatemala    | 2         | 0.25%   |
| Denmark      | 2         | 0.25%   |
| Croatia      | 2         | 0.25%   |
| Colombia     | 2         | 0.25%   |
| Chile        | 2         | 0.25%   |
| Zambia       | 1         | 0.12%   |
| Vietnam      | 1         | 0.12%   |
| Uruguay      | 1         | 0.12%   |
| UAE          | 1         | 0.12%   |
| South Sudan  | 1         | 0.12%   |
| Slovakia     | 1         | 0.12%   |
| Singapore    | 1         | 0.12%   |
| Pakistan     | 1         | 0.12%   |
| New Zealand  | 1         | 0.12%   |
| Morocco      | 1         | 0.12%   |
| Mongolia     | 1         | 0.12%   |
| Moldova      | 1         | 0.12%   |
| Malaysia     | 1         | 0.12%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Portland               | 225       | 27.47%  |
| Voronezh               | 52        | 6.35%   |
| St Petersburg          | 16        | 1.95%   |
| M??laga                | 14        | 1.71%   |
| Paris                  | 10        | 1.22%   |
| Hampden                | 7         | 0.85%   |
| Vienna                 | 5         | 0.61%   |
| London                 | 5         | 0.61%   |
| Berlin                 | 5         | 0.61%   |
| S??o Paulo             | 4         | 0.49%   |
| Moscow                 | 4         | 0.49%   |
| Madrid                 | 4         | 0.49%   |
| Lyon                   | 4         | 0.49%   |
| Helsinki               | 4         | 0.49%   |
| Bengaluru              | 4         | 0.49%   |
| Bangkok                | 4         | 0.49%   |
| Zurich                 | 3         | 0.37%   |
| Warsaw                 | 3         | 0.37%   |
| Toronto                | 3         | 0.37%   |
| Thermopolis            | 3         | 0.37%   |
| Sunnyvale              | 3         | 0.37%   |
| Sevastopol             | 3         | 0.37%   |
| Milan                  | 3         | 0.37%   |
| Mesa                   | 3         | 0.37%   |
| Manchester             | 3         | 0.37%   |
| Kyiv                   | 3         | 0.37%   |
| Iasi                   | 3         | 0.37%   |
| Halstead               | 3         | 0.37%   |
| Frankfort              | 3         | 0.37%   |
| Dublin                 | 3         | 0.37%   |
| Athens                 | 3         | 0.37%   |
| Ankara                 | 3         | 0.37%   |
| Amsterdam              | 3         | 0.37%   |
| Zerkow                 | 2         | 0.24%   |
| Yevpatoriya            | 2         | 0.24%   |
| Wroclaw                | 2         | 0.24%   |
| Valencia               | 2         | 0.24%   |
| Tyreso Strand          | 2         | 0.24%   |
| Ternopil               | 2         | 0.24%   |
| Sydney                 | 2         | 0.24%   |
| Stockholm              | 2         | 0.24%   |
| Sofia                  | 2         | 0.24%   |
| San Miguel de Tucum??n | 2         | 0.24%   |
| Roseville              | 2         | 0.24%   |
| Rio de Janeiro         | 2         | 0.24%   |
| Riga                   | 2         | 0.24%   |
| Prague                 | 2         | 0.24%   |
| Plano                  | 2         | 0.24%   |
| Perm                   | 2         | 0.24%   |
| Offenburg              | 2         | 0.24%   |
| Munich                 | 2         | 0.24%   |
| Molde                  | 2         | 0.24%   |
| Minsk                  | 2         | 0.24%   |
| Loziska                | 2         | 0.24%   |
| Krakow                 | 2         | 0.24%   |
| Katowice               | 2         | 0.24%   |
| Kalamazoo              | 2         | 0.24%   |
| Johannesburg           | 2         | 0.24%   |
| Istanbul               | 2         | 0.24%   |
| Hamburg                | 2         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Apple                     | 148       | 159    | 15.58%  |
| Samsung Electronics       | 139       | 159    | 14.63%  |
| WDC                       | 95        | 118    | 10%     |
| Unknown                   | 76        | 92     | 8%      |
| Seagate                   | 67        | 78     | 7.05%   |
| Kingston                  | 49        | 55     | 5.16%   |
| Toshiba                   | 46        | 47     | 4.84%   |
| Crucial                   | 35        | 40     | 3.68%   |
| SanDisk                   | 33        | 37     | 3.47%   |
| SK Hynix                  | 31        | 34     | 3.26%   |
| Hitachi                   | 27        | 27     | 2.84%   |
| A-DATA Technology         | 26        | 32     | 2.74%   |
| Intel                     | 25        | 25     | 2.63%   |
| Micron Technology         | 21        | 21     | 2.21%   |
| SABRENT                   | 15        | 15     | 1.58%   |
| HGST                      | 15        | 16     | 1.58%   |
| KIOXIA                    | 8         | 9      | 0.84%   |
| Fujitsu                   | 8         | 9      | 0.84%   |
| China                     | 8         | 8      | 0.84%   |
| Transcend                 | 7         | 7      | 0.74%   |
| LITEON                    | 6         | 6      | 0.63%   |
| Union Memory              | 4         | 4      | 0.42%   |
| Silicon Motion            | 4         | 5      | 0.42%   |
| Lenovo                    | 4         | 4      | 0.42%   |
| PNY                       | 3         | 3      | 0.32%   |
| LITEONIT                  | 3         | 3      | 0.32%   |
| Lexar                     | 3         | 4      | 0.32%   |
| JMicron                   | 3         | 3      | 0.32%   |
| Intenso                   | 3         | 3      | 0.32%   |
| ZTC                       | 2         | 4      | 0.21%   |
| XPG                       | 2         | 2      | 0.21%   |
| Team                      | 2         | 2      | 0.21%   |
| SPCC                      | 2         | 2      | 0.21%   |
| Solid State Storage       | 2         | 2      | 0.21%   |
| Phison                    | 2         | 5      | 0.21%   |
| Patriot                   | 2         | 2      | 0.21%   |
| Mass                      | 2         | 2      | 0.21%   |
| Corsair                   | 2         | 2      | 0.21%   |
| Apacer                    | 2         | 2      | 0.21%   |
| USB3.0                    | 1         | 1      | 0.11%   |
| TrekStor                  | 1         | 1      | 0.11%   |
| SILICONMOTION             | 1         | 1      | 0.11%   |
| RDM-II                    | 1         | 1      | 0.11%   |
| PLEXTOR                   | 1         | 1      | 0.11%   |
| Phison Electronics        | 1         | 1      | 0.11%   |
| MyDigitalSSD              | 1         | 1      | 0.11%   |
| Mushkin                   | 1         | 1      | 0.11%   |
| Micron/Crucial Technology | 1         | 1      | 0.11%   |
| MAXTOR                    | 1         | 4      | 0.11%   |
| LDLC                      | 1         | 1      | 0.11%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.11%   |
| KingSpec                  | 1         | 1      | 0.11%   |
| GOODRAM                   | 1         | 1      | 0.11%   |
| FORESEE                   | 1         | 1      | 0.11%   |
| BIWIN                     | 1         | 1      | 0.11%   |
| ASUS-PHISON               | 1         | 1      | 0.11%   |
| AMD                       | 1         | 2      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Apple SSD AP0128H 121GB              | 75        | 7.71%   |
| Apple SSD SM0128G 121GB              | 66        | 6.78%   |
| Unknown AGND3R  16GB                 | 25        | 2.57%   |
| Seagate ST1000LM035-1RK172 1TB       | 22        | 2.26%   |
| Unknown HAG2e  16GB                  | 19        | 1.95%   |
| SABRENT Disk 320GB                   | 15        | 1.54%   |
| A-DATA SU800 512GB SSD               | 12        | 1.23%   |
| Toshiba MQ04ABF100 1TB               | 9         | 0.92%   |
| SanDisk SD8SN8U128G1001 128GB SSD    | 9         | 0.92%   |
| Samsung MZNTY128HDHP-000L1 128GB SSD | 8         | 0.82%   |
| Kingston SA400S37120G 120GB SSD      | 7         | 0.72%   |
| HGST HTS721010A9E630 1TB             | 7         | 0.72%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 6         | 0.62%   |
| Samsung SSD 870 EVO 500GB            | 6         | 0.62%   |
| Samsung SSD 860 EVO 500GB            | 6         | 0.62%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 0.62%   |
| Crucial CT500MX500SSD1 500GB         | 6         | 0.62%   |
| Crucial CT1000MX500SSD1 1TB          | 6         | 0.62%   |
| Toshiba MQ01ABF050 500GB             | 5         | 0.51%   |
| Samsung SSD 970 EVO Plus 500GB       | 5         | 0.51%   |
| Samsung SSD 970 EVO Plus 1TB         | 5         | 0.51%   |
| Samsung SSD 860 EVO 250GB            | 5         | 0.51%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 0.51%   |
| WDC WD10SPZX-24Z10 1TB               | 4         | 0.41%   |
| WDC WD10SPZX-21Z10T0 1TB             | 4         | 0.41%   |
| SanDisk SSD PLUS 240GB               | 4         | 0.41%   |
| Samsung SSD 970 EVO 1TB              | 4         | 0.41%   |
| Samsung SSD 860 EVO 1TB              | 4         | 0.41%   |
| Samsung SSD 850 PRO 1TB              | 4         | 0.41%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.41%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.41%   |
| Intel SSDPEKNW512G8 512GB            | 4         | 0.41%   |
| Hitachi HTS543216L9A300 160GB        | 4         | 0.41%   |
| WDC WD10SPZX-60Z10T0 1TB             | 3         | 0.31%   |
| WDC WD10JPVX-22JC3T0 1TB             | 3         | 0.31%   |
| WDC PC SN530 NVMe 256GB              | 3         | 0.31%   |
| Unknown SDW16G  16GB                 | 3         | 0.31%   |
| Unknown DA4064  64GB                 | 3         | 0.31%   |
| Toshiba MQ04ABD200 2TB               | 3         | 0.31%   |
| SK Hynix HFM001TD3JX013N 1TB         | 3         | 0.31%   |
| Seagate ST9320325AS 320GB            | 3         | 0.31%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.31%   |
| Seagate ST2000LX001-1RG174 2TB       | 3         | 0.31%   |
| Samsung SSD 980 1TB                  | 3         | 0.31%   |
| Samsung SSD 860 EVO M.2 1TB          | 3         | 0.31%   |
| Samsung SSD 850 EVO 250GB            | 3         | 0.31%   |
| Samsung MZALQ256HAJD-000L1 256GB     | 3         | 0.31%   |
| Micron 2300 NVMe 512GB               | 3         | 0.31%   |
| Lexar 512GB SSD                      | 3         | 0.31%   |
| Intel SSDPEKNW512G8H 512GB           | 3         | 0.31%   |
| HGST HTS725050A7E630 500GB           | 3         | 0.31%   |
| Crucial CT250MX500SSD1 250GB         | 3         | 0.31%   |
| Crucial CT1000P1SSD8 1TB             | 3         | 0.31%   |
| ZTC SM201-512G                       | 2         | 0.21%   |
| XPG NVMe SSD Drive 1024GB            | 2         | 0.21%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 2         | 0.21%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 2         | 0.21%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 0.21%   |
| WDC WD50 00LPCX-24VHA 500GB          | 2         | 0.21%   |
| WDC WD10JPVX-60JC3T0 1TB             | 2         | 0.21%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 74     | 29.3%   |
| WDC                 | 53        | 59     | 24.65%  |
| Hitachi             | 27        | 27     | 12.56%  |
| Toshiba             | 26        | 26     | 12.09%  |
| SABRENT             | 15        | 15     | 6.98%   |
| HGST                | 15        | 16     | 6.98%   |
| Fujitsu             | 8         | 9      | 3.72%   |
| Samsung Electronics | 3         | 3      | 1.4%    |
| JMicron             | 2         | 2      | 0.93%   |
| USB3.0              | 1         | 1      | 0.47%   |
| Unknown             | 1         | 1      | 0.47%   |
| SILICONMOTION       | 1         | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 79        | 91     | 22.13%  |
| Apple               | 71        | 75     | 19.89%  |
| Kingston            | 37        | 43     | 10.36%  |
| Crucial             | 28        | 33     | 7.84%   |
| SanDisk             | 26        | 29     | 7.28%   |
| A-DATA Technology   | 18        | 20     | 5.04%   |
| WDC                 | 10        | 16     | 2.8%    |
| Intel               | 10        | 10     | 2.8%    |
| Micron Technology   | 8         | 8      | 2.24%   |
| China               | 8         | 8      | 2.24%   |
| Transcend           | 7         | 7      | 1.96%   |
| SK Hynix            | 7         | 8      | 1.96%   |
| LITEON              | 5         | 5      | 1.4%    |
| Toshiba             | 4         | 4      | 1.12%   |
| PNY                 | 3         | 3      | 0.84%   |
| LITEONIT            | 3         | 3      | 0.84%   |
| Lexar               | 3         | 4      | 0.84%   |
| Intenso             | 3         | 3      | 0.84%   |
| ZTC                 | 2         | 4      | 0.56%   |
| Team                | 2         | 2      | 0.56%   |
| SPCC                | 2         | 2      | 0.56%   |
| Seagate             | 2         | 2      | 0.56%   |
| Patriot             | 2         | 2      | 0.56%   |
| Apacer              | 2         | 2      | 0.56%   |
| Unknown             | 1         | 1      | 0.28%   |
| Union Memory        | 1         | 1      | 0.28%   |
| TrekStor            | 1         | 1      | 0.28%   |
| RDM-II              | 1         | 1      | 0.28%   |
| PLEXTOR             | 1         | 1      | 0.28%   |
| MyDigitalSSD        | 1         | 1      | 0.28%   |
| Mushkin             | 1         | 1      | 0.28%   |
| MAXTOR              | 1         | 4      | 0.28%   |
| LDLC                | 1         | 1      | 0.28%   |
| KingSpec            | 1         | 1      | 0.28%   |
| GOODRAM             | 1         | 1      | 0.28%   |
| FORESEE             | 1         | 1      | 0.28%   |
| Corsair             | 1         | 1      | 0.28%   |
| ASUS-PHISON         | 1         | 1      | 0.28%   |
| AMD                 | 1         | 2      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 341       | 403    | 37.31%  |
| NVMe    | 289       | 336    | 31.62%  |
| HDD     | 203       | 234    | 22.21%  |
| MMC     | 74        | 90     | 8.1%    |
| Unknown | 7         | 7      | 0.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 490       | 603    | 55.18%  |
| NVMe | 289       | 336    | 32.55%  |
| MMC  | 74        | 90     | 8.33%   |
| SAS  | 35        | 41     | 3.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 375       | 451    | 69.57%  |
| 0.51-1.0   | 143       | 162    | 26.53%  |
| 1.01-2.0   | 16        | 19     | 2.97%   |
| 3.01-4.0   | 2         | 2      | 0.37%   |
| 4.01-10.0  | 2         | 2      | 0.37%   |
| 2.01-3.0   | 1         | 1      | 0.19%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 340       | 41.87%  |
| 251-500        | 141       | 17.36%  |
| 1-20           | 79        | 9.73%   |
| 501-1000       | 77        | 9.48%   |
| Unknown        | 68        | 8.37%   |
| 1001-2000      | 44        | 5.42%   |
| 51-100         | 31        | 3.82%   |
| 21-50          | 17        | 2.09%   |
| More than 3000 | 11        | 1.35%   |
| 2001-3000      | 4         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 412       | 50%     |
| 101-250        | 85        | 10.32%  |
| 21-50          | 80        | 9.71%   |
| 51-100         | 78        | 9.47%   |
| Unknown        | 68        | 8.25%   |
| 251-500        | 51        | 6.19%   |
| 501-1000       | 32        | 3.88%   |
| 1001-2000      | 11        | 1.33%   |
| 0              | 4         | 0.49%   |
| More than 3000 | 2         | 0.24%   |
| 2001-3000      | 1         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 2      | 2.9%    |
| Toshiba MQ01ABF050 500GB                       | 2         | 2      | 2.9%    |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 2.9%    |
| Hitachi HTS547575A9E384 752GB                  | 2         | 2      | 2.9%    |
| Hitachi HTS542516K9SA00 160GB                  | 2         | 2      | 2.9%    |
| Crucial CT275MX300SSD1 275GB                   | 2         | 2      | 2.9%    |
| WDC WD7500BPVX-22JC3T0 752GB                   | 1         | 1      | 1.45%   |
| WDC WD7500BPVT-80HXZT3 752GB                   | 1         | 1      | 1.45%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 1.45%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 1.45%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 1.45%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 1.45%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.45%   |
| SK Hynix SH920 mSATA 128GB SSD                 | 1         | 1      | 1.45%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD          | 1         | 1      | 1.45%   |
| SK Hynix HFS256G39MND-2300A 256GB SSD          | 1         | 1      | 1.45%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 1.45%   |
| Seagate ST960822A 64GB                         | 1         | 1      | 1.45%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 1.45%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 1.45%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 1.45%   |
| Seagate ST9160310AS 160GB                      | 1         | 1      | 1.45%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 1.45%   |
| Seagate ST500LM000-SSHD-8GB                    | 1         | 1      | 1.45%   |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 1.45%   |
| Seagate ST1000LX015-1U7172 1TB                 | 1         | 1      | 1.45%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 1.45%   |
| SanDisk SD7SB3Q128G1002 128GB SSD              | 1         | 1      | 1.45%   |
| Samsung Electronics SSD 870 EVO 500GB          | 1         | 1      | 1.45%   |
| Samsung Electronics SSD 850 EVO 1TB            | 1         | 1      | 1.45%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 2      | 1.45%   |
| Samsung Electronics HM321HI 320GB              | 1         | 1      | 1.45%   |
| Micron Technology 2300 NVMe 512GB              | 1         | 1      | 1.45%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.45%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 1.45%   |
| Micron Technology 1100 SATA 256GB SSD          | 1         | 1      | 1.45%   |
| LITEONIT LMT-64M6M-HP 64GB SSD                 | 1         | 1      | 1.45%   |
| LITEON IT SCS-256L9S 256GB SSD                 | 1         | 1      | 1.45%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 1.45%   |
| Kingston SA400S37120G 120GB SSD                | 1         | 1      | 1.45%   |
| Intel SSDSC2KW120H6 120GB                      | 1         | 1      | 1.45%   |
| Intel SSDSC2BF180A4H 180GB                     | 1         | 1      | 1.45%   |
| Intel SSDSA2M160G2HP 160GB                     | 1         | 1      | 1.45%   |
| Intel SSDPEKKF256G7H 256GB                     | 1         | 1      | 1.45%   |
| Hitachi HTS725050A9A364 500GB                  | 1         | 1      | 1.45%   |
| Hitachi HTS547550A9E384 500GB                  | 1         | 1      | 1.45%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 1.45%   |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 1.45%   |
| Hitachi HTS543225L9A300 250GB                  | 1         | 1      | 1.45%   |
| Hitachi HTS543216L9A300 160GB                  | 1         | 1      | 1.45%   |
| Hitachi HTS543212L9A300 120GB                  | 1         | 1      | 1.45%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 1.45%   |
| Hitachi HTS541075A9E680 752GB                  | 1         | 1      | 1.45%   |
| Hitachi HTS541060G9AT00 64GB                   | 1         | 1      | 1.45%   |
| Hitachi HTS541040G9AT00 37GB                   | 1         | 1      | 1.45%   |
| Hitachi HTS541010G9SA00 100GB                  | 1         | 1      | 1.45%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 1.45%   |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 1.45%   |
| HGST HTS545050A7 500GB                         | 1         | 1      | 1.45%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 1.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 16        | 16     | 23.19%  |
| Seagate             | 12        | 12     | 17.39%  |
| WDC                 | 6         | 6      | 8.7%    |
| Toshiba             | 5         | 5      | 7.25%   |
| SK Hynix            | 4         | 4      | 5.8%    |
| Samsung Electronics | 4         | 5      | 5.8%    |
| Micron Technology   | 4         | 4      | 5.8%    |
| Intel               | 4         | 4      | 5.8%    |
| HGST                | 4         | 4      | 5.8%    |
| Crucial             | 3         | 3      | 4.35%   |
| Kingston            | 2         | 2      | 2.9%    |
| SanDisk             | 1         | 1      | 1.45%   |
| LITEONIT            | 1         | 1      | 1.45%   |
| LITEON              | 1         | 1      | 1.45%   |
| Fujitsu             | 1         | 1      | 1.45%   |
| A-DATA Technology   | 1         | 1      | 1.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 16        | 16     | 35.56%  |
| Seagate             | 12        | 12     | 26.67%  |
| WDC                 | 6         | 6      | 13.33%  |
| Toshiba             | 5         | 5      | 11.11%  |
| HGST                | 4         | 4      | 8.89%   |
| Samsung Electronics | 1         | 1      | 2.22%   |
| Fujitsu             | 1         | 1      | 2.22%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 45     | 65.22%  |
| SSD  | 22        | 23     | 31.88%  |
| NVMe | 2         | 2      | 2.9%    |

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
| Works    | 602       | 738    | 70.33%  |
| Detected | 185       | 262    | 21.61%  |
| Malfunc  | 69        | 70     | 8.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 423       | 49.02%  |
| Samsung Electronics            | 130       | 15.06%  |
| AMD                            | 78        | 9.04%   |
| Apple                          | 77        | 8.92%   |
| Sandisk                        | 40        | 4.63%   |
| SK Hynix                       | 23        | 2.67%   |
| Toshiba America Info Systems   | 14        | 1.62%   |
| Micron Technology              | 13        | 1.51%   |
| Kingston Technology Company    | 12        | 1.39%   |
| KIOXIA                         | 11        | 1.27%   |
| ADATA Technology               | 9         | 1.04%   |
| Micron/Crucial Technology      | 8         | 0.93%   |
| Silicon Motion                 | 6         | 0.7%    |
| Nvidia                         | 6         | 0.7%    |
| Phison Electronics             | 4         | 0.46%   |
| Union Memory (Shenzhen)        | 3         | 0.35%   |
| Lenovo                         | 3         | 0.35%   |
| Solid State Storage Technology | 2         | 0.23%   |
| Lite-On Technology             | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Apple S1X NVMe Controller                                                        | 75        | 8.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 70        | 7.73%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 70        | 7.73%   |
| Samsung Electronics SATA controller                                              | 69        | 7.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 56        | 6.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 34        | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 29        | 3.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 24        | 2.65%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 20        | 2.21%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 19        | 2.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 19        | 2.1%    |
| Samsung NVMe SSD Controller 980                                                  | 18        | 1.99%   |
| Intel Volume Management Device NVMe RAID Controller                              | 18        | 1.99%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 15        | 1.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 1.66%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 14        | 1.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 13        | 1.44%   |
| Micron Non-Volatile memory controller                                            | 13        | 1.44%   |
| Intel Comet Lake SATA AHCI Controller                                            | 13        | 1.44%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 12        | 1.33%   |
| KIOXIA Non-Volatile memory controller                                            | 11        | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 11        | 1.22%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 10        | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 10        | 1.1%    |
| Intel SSD 660P Series                                                            | 9         | 0.99%   |
| SK Hynix Gold P31 SSD                                                            | 8         | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 8         | 0.88%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 8         | 0.88%   |
| SK Hynix BC511                                                                   | 7         | 0.77%   |
| Sandisk Non-Volatile memory controller                                           | 7         | 0.77%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 7         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 0.77%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 6         | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 6         | 0.66%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 6         | 0.66%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 6         | 0.66%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 5         | 0.55%   |
| Sandisk PC SN520 NVMe SSD                                                        | 5         | 0.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 0.55%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 5         | 0.55%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 5         | 0.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.55%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 5         | 0.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 0.55%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 4         | 0.44%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 4         | 0.44%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 0.44%   |
| Kingston Company A2000 NVMe SSD                                                  | 4         | 0.44%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 4         | 0.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 4         | 0.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 0.44%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 3         | 0.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.33%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.33%   |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.33%   |
| Lenovo Non-Volatile memory controller                                            | 3         | 0.33%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.33%   |
| Intel SSD 600P Series                                                            | 3         | 0.33%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 509       | 57.58%  |
| NVMe | 289       | 32.69%  |
| IDE  | 45        | 5.09%   |
| RAID | 41        | 4.64%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 693       | 86.41%  |
| AMD    | 108       | 13.47%  |
| ARM    | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz             | 141       | 17.58%  |
| Intel Celeron CPU N2840 @ 2.16GHz             | 48        | 5.99%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 28        | 3.49%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 17        | 2.12%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 2%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 1.87%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 1.62%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 1.62%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 12        | 1.5%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 10        | 1.25%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 10        | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.12%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 8         | 1%      |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 0.87%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.87%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.87%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.87%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 6         | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 0.75%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 6         | 0.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 0.75%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 6         | 0.75%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 0.62%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.62%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.62%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.5%    |
| Intel Core i7-7600U CPU @ 2.80GHz             | 4         | 0.5%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.5%    |
| Intel Core i7-5600U CPU @ 2.60GHz             | 4         | 0.5%    |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 4         | 0.5%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.5%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.5%    |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.5%    |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 0.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.5%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.5%    |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.5%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 4         | 0.5%    |
| Intel Celeron CPU B800 @ 1.50GHz              | 4         | 0.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 0.5%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.5%    |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.37%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 3         | 0.37%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 3         | 0.37%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 0.37%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.37%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.37%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.37%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 3         | 0.37%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 3         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 301       | 37.53%  |
| Intel Core i7           | 140       | 17.46%  |
| Intel Celeron           | 87        | 10.85%  |
| Intel Core i3           | 47        | 5.86%   |
| AMD Ryzen 5             | 45        | 5.61%   |
| Other                   | 41        | 5.11%   |
| Intel Core 2 Duo        | 29        | 3.62%   |
| AMD Ryzen 7             | 17        | 2.12%   |
| Intel Pentium           | 16        | 2%      |
| Intel Atom              | 11        | 1.37%   |
| AMD Ryzen 7 PRO         | 9         | 1.12%   |
| Intel Pentium M         | 5         | 0.62%   |
| AMD Ryzen 9             | 5         | 0.62%   |
| Intel Genuine           | 4         | 0.5%    |
| Intel Celeron M         | 4         | 0.5%    |
| AMD A8                  | 4         | 0.5%    |
| AMD A6                  | 4         | 0.5%    |
| AMD A4                  | 4         | 0.5%    |
| Intel Core 2            | 3         | 0.37%   |
| AMD Ryzen 3             | 3         | 0.37%   |
| Intel Pentium Dual      | 2         | 0.25%   |
| Intel Core m3           | 2         | 0.25%   |
| AMD Turion 64 Mobile    | 2         | 0.25%   |
| AMD E                   | 2         | 0.25%   |
| AMD C-60                | 2         | 0.25%   |
| AMD A12                 | 2         | 0.25%   |
| Intel Xeon              | 1         | 0.12%   |
| Intel Pentium Silver    | 1         | 0.12%   |
| Intel Pentium Gold      | 1         | 0.12%   |
| Intel Pentium Dual-Core | 1         | 0.12%   |
| Intel Core m7           | 1         | 0.12%   |
| ARM ARMv7               | 1         | 0.12%   |
| AMD E1                  | 1         | 0.12%   |
| AMD C-50                | 1         | 0.12%   |
| AMD C-30                | 1         | 0.12%   |
| AMD Athlon 64           | 1         | 0.12%   |
| AMD Athlon              | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 479       | 59.73%  |
| 4      | 225       | 28.05%  |
| 6      | 41        | 5.11%   |
| 8      | 30        | 3.74%   |
| 1      | 27        | 3.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 802       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 596       | 74.31%  |
| 1      | 206       | 25.69%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 783       | 97.63%  |
| 32-bit         | 17        | 2.12%   |
| Unknown        | 2         | 0.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306d4    | 161       | 19.83%  |
| Unknown    | 131       | 16.13%  |
| 0x30678    | 50        | 6.16%   |
| 0x806e9    | 39        | 4.8%    |
| 0x306a9    | 37        | 4.56%   |
| 0x206a7    | 37        | 4.56%   |
| 0x806c1    | 27        | 3.33%   |
| 0x08108109 | 25        | 3.08%   |
| 0x806ec    | 24        | 2.96%   |
| 0x806ea    | 22        | 2.71%   |
| 0x406e3    | 21        | 2.59%   |
| 0x906ea    | 16        | 1.97%   |
| 0x1067a    | 16        | 1.97%   |
| 0x40651    | 14        | 1.72%   |
| 0xa0652    | 13        | 1.6%    |
| 0x906eb    | 12        | 1.48%   |
| 0x706e5    | 11        | 1.35%   |
| 0x306c3    | 11        | 1.35%   |
| 0x08600106 | 10        | 1.23%   |
| 0x806eb    | 7         | 0.86%   |
| 0x6fd      | 7         | 0.86%   |
| 0x20655    | 7         | 0.86%   |
| 0x106c2    | 7         | 0.86%   |
| 0x6d8      | 6         | 0.74%   |
| 0x506c9    | 6         | 0.74%   |
| 0x08600104 | 6         | 0.74%   |
| 0x906e9    | 5         | 0.62%   |
| 0x0a50000c | 5         | 0.62%   |
| 0x08608103 | 5         | 0.62%   |
| 0x08108102 | 5         | 0.62%   |
| 0x0a50000b | 4         | 0.49%   |
| 0x08600103 | 4         | 0.49%   |
| 0x06006705 | 4         | 0.49%   |
| 0x0600611a | 4         | 0.49%   |
| 0x706a8    | 3         | 0.37%   |
| 0x6fb      | 3         | 0.37%   |
| 0x6f6      | 3         | 0.37%   |
| 0x506e3    | 3         | 0.37%   |
| 0x406c4    | 3         | 0.37%   |
| 0x406c3    | 3         | 0.37%   |
| 0x10676    | 3         | 0.37%   |
| 0x906ed    | 2         | 0.25%   |
| 0x806d1    | 2         | 0.25%   |
| 0x6fa      | 2         | 0.25%   |
| 0x6e8      | 2         | 0.25%   |
| 0x695      | 2         | 0.25%   |
| 0x40661    | 2         | 0.25%   |
| 0x106ca    | 2         | 0.25%   |
| 0x0810100b | 2         | 0.25%   |
| 0x07030105 | 2         | 0.25%   |
| 0x03000027 | 2         | 0.25%   |
| 0x706a1    | 1         | 0.12%   |
| 0x20652    | 1         | 0.12%   |
| 0x106e5    | 1         | 0.12%   |
| 0x10661    | 1         | 0.12%   |
| 0x08608102 | 1         | 0.12%   |
| 0x07030106 | 1         | 0.12%   |
| 0x06001119 | 1         | 0.12%   |
| 0x05000119 | 1         | 0.12%   |
| 0x05000101 | 1         | 0.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Broadwell     | 163       | 20.32%  |
| KabyLake      | 156       | 19.45%  |
| Silvermont    | 59        | 7.36%   |
| IvyBridge     | 49        | 6.11%   |
| SandyBridge   | 45        | 5.61%   |
| Haswell       | 38        | 4.74%   |
| TigerLake     | 36        | 4.49%   |
| Zen+          | 34        | 4.24%   |
| Skylake       | 33        | 4.11%   |
| Zen 2         | 26        | 3.24%   |
| Penryn        | 20        | 2.49%   |
| Core          | 19        | 2.37%   |
| IceLake       | 15        | 1.87%   |
| Westmere      | 14        | 1.75%   |
| CometLake     | 14        | 1.75%   |
| Zen 3         | 10        | 1.25%   |
| P6            | 10        | 1.25%   |
| Excavator     | 9         | 1.12%   |
| Bonnell       | 9         | 1.12%   |
| Goldmont      | 8         | 1%      |
| Unknown       | 7         | 0.87%   |
| Bobcat        | 6         | 0.75%   |
| Puma          | 5         | 0.62%   |
| Zen           | 4         | 0.5%    |
| Goldmont plus | 4         | 0.5%    |
| K8 Hammer     | 3         | 0.37%   |
| K10 Llano     | 3         | 0.37%   |
| Piledriver    | 1         | 0.12%   |
| Nehalem       | 1         | 0.12%   |
| Jaguar        | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 662       | 70.13%  |
| Nvidia | 141       | 14.94%  |
| AMD    | 141       | 14.94%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 6000                                                                   | 142       | 14.48%  |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 51        | 5.2%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 46        | 4.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 39        | 3.98%   |
| AMD Picasso                                                                              | 35        | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 33        | 3.36%   |
| Intel UHD Graphics 620                                                                   | 29        | 2.96%   |
| AMD Renoir                                                                               | 26        | 2.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 2.45%   |
| Intel HD Graphics 620                                                                    | 24        | 2.45%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 2.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 2.04%   |
| Intel HD Graphics 5500                                                                   | 20        | 2.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 1.94%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 18        | 1.83%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 16        | 1.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 16        | 1.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.33%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 12        | 1.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.22%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 12        | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 10        | 1.02%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 1.02%   |
| AMD Cezanne                                                                              | 9         | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8         | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 7         | 0.71%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.71%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 7         | 0.71%   |
| Intel HD Graphics 630                                                                    | 7         | 0.71%   |
| Nvidia TU117M                                                                            | 6         | 0.61%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 6         | 0.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 6         | 0.61%   |
| Intel HD Graphics 530                                                                    | 6         | 0.61%   |
| AMD Lucienne                                                                             | 6         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.51%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 0.51%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 5         | 0.51%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 0.51%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 5         | 0.51%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.51%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.51%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5         | 0.51%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.41%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.41%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.41%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.41%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.41%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.31%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.31%   |
| Nvidia GF119M [NVS 4200M]                                                                | 3         | 0.31%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 0.31%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.31%   |
| Intel HD Graphics 515                                                                    | 3         | 0.31%   |
| Intel HD Graphics 500                                                                    | 3         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 532       | 66.17%  |
| Intel + Nvidia | 106       | 13.18%  |
| 1 x AMD        | 96        | 11.94%  |
| Intel + AMD    | 24        | 2.99%   |
| 1 x Nvidia     | 23        | 2.86%   |
| AMD + Nvidia   | 13        | 1.62%   |
| 2 x AMD        | 8         | 1%      |
| Other          | 2         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 692       | 85.86%  |
| Unknown     | 59        | 7.32%   |
| Proprietary | 55        | 6.82%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 675       | 83.44%  |
| 0.01-0.5   | 54        | 6.67%   |
| 1.01-2.0   | 29        | 3.58%   |
| 3.01-4.0   | 25        | 3.09%   |
| 0.51-1.0   | 21        | 2.6%    |
| 7.01-8.0   | 3         | 0.37%   |
| 5.01-6.0   | 2         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 159       | 18.93%  |
| BOE                     | 128       | 15.24%  |
| AU Optronics            | 128       | 15.24%  |
| Chimei Innolux          | 99        | 11.79%  |
| LG Display              | 89        | 10.6%   |
| Samsung Electronics     | 47        | 5.6%    |
| Sharp                   | 23        | 2.74%   |
| Lenovo                  | 18        | 2.14%   |
| Dell                    | 18        | 2.14%   |
| InfoVision              | 15        | 1.79%   |
| PANDA                   | 11        | 1.31%   |
| Goldstar                | 10        | 1.19%   |
| Chi Mei Optoelectronics | 10        | 1.19%   |
| Hewlett-Packard         | 9         | 1.07%   |
| Philips                 | 8         | 0.95%   |
| BenQ                    | 8         | 0.95%   |
| LG Philips              | 6         | 0.71%   |
| Ancor Communications    | 6         | 0.71%   |
| Unknown                 | 5         | 0.6%    |
| HannStar                | 5         | 0.6%    |
| ViewSonic               | 4         | 0.48%   |
| NEC Computers           | 3         | 0.36%   |
| CSO                     | 3         | 0.36%   |
| CPT                     | 3         | 0.36%   |
| AOC                     | 3         | 0.36%   |
| Acer                    | 3         | 0.36%   |
| ___                     | 2         | 0.24%   |
| ASUSTek Computer        | 2         | 0.24%   |
| Vestel Elektronik       | 1         | 0.12%   |
| Sony                    | 1         | 0.12%   |
| Quanta Display          | 1         | 0.12%   |
| Panasonic               | 1         | 0.12%   |
| NCS                     | 1         | 0.12%   |
| MSI                     | 1         | 0.12%   |
| LPL                     | 1         | 0.12%   |
| JXG                     | 1         | 0.12%   |
| JRY                     | 1         | 0.12%   |
| IOD                     | 1         | 0.12%   |
| Iiyama                  | 1         | 0.12%   |
| Eizo                    | 1         | 0.12%   |
| Compaq Computer         | 1         | 0.12%   |
| CMN                     | 1         | 0.12%   |
| BOE Technology Group    | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 40        | 4.72%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 40        | 4.72%   |
| Apple Color LCD APP9CF2 1366x768 260x140mm 11.6-inch                      | 35        | 4.13%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 30        | 3.54%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 23        | 2.71%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 10        | 1.18%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 10        | 1.18%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch            | 10        | 1.18%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch             | 10        | 1.18%   |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch               | 7         | 0.83%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 7         | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 6         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 6         | 0.71%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 6         | 0.71%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 5         | 0.59%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 4         | 0.47%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 4         | 0.47%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 4         | 0.47%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 4         | 0.47%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                     | 4         | 0.47%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch            | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 4         | 0.47%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 4         | 0.47%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 3         | 0.35%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 3         | 0.35%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 3         | 0.35%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 3         | 0.35%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 3         | 0.35%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 3         | 0.35%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch          | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch          | 3         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 3         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 3         | 0.35%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                     | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch             | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch             | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.35%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                   | 2         | 0.24%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                   | 2         | 0.24%   |
| Sharp LCD Monitor SHP1447 1920x1080 290x170mm 13.2-inch                   | 2         | 0.24%   |
| Samsung Electronics SyncMaster SAM011F 1280x1024 376x301mm 19.0-inch      | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch     | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch      | 2         | 0.24%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                   | 2         | 0.24%   |
| NEC Computers EA244WMi NEC68D7 1920x1080 520x320mm 24.0-inch              | 2         | 0.24%   |
| NEC Computers EA244WMi NEC68D5 1920x1200 520x320mm 24.0-inch              | 2         | 0.24%   |
| LG Philips LCD Monitor LPL1151 1024x768 304x228mm 15.0-inch               | 2         | 0.24%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 2         | 0.24%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 0.24%   |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch              | 2         | 0.24%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 2         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 294       | 36.43%  |
| 1366x768 (WXGA)    | 278       | 34.45%  |
| 1440x900 (WXGA+)   | 78        | 9.67%   |
| 1280x800 (WXGA)    | 28        | 3.47%   |
| 1600x900 (HD+)     | 25        | 3.1%    |
| 3840x2160 (4K)     | 20        | 2.48%   |
| 1920x1200 (WUXGA)  | 18        | 2.23%   |
| 2560x1440 (QHD)    | 15        | 1.86%   |
| 1024x600           | 10        | 1.24%   |
| 1280x1024 (SXGA)   | 7         | 0.87%   |
| 2880x1800          | 6         | 0.74%   |
| 1024x768 (XGA)     | 5         | 0.62%   |
| 2288x1287          | 3         | 0.37%   |
| 2160x1440          | 3         | 0.37%   |
| 1680x1050 (WSXGA+) | 3         | 0.37%   |
| 3840x1080          | 2         | 0.25%   |
| 3440x1440          | 2         | 0.25%   |
| 3200x1800 (QHD+)   | 2         | 0.25%   |
| 2560x1600          | 2         | 0.25%   |
| 3840x2400          | 1         | 0.12%   |
| 2880x1920          | 1         | 0.12%   |
| 2256x1504          | 1         | 0.12%   |
| 1792x768           | 1         | 0.12%   |
| 1600x1200          | 1         | 0.12%   |
| Unknown            | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 218       | 26.05%  |
| 13      | 194       | 23.18%  |
| 11      | 136       | 16.25%  |
| 14      | 88        | 10.51%  |
| 12      | 37        | 4.42%   |
| 17      | 34        | 4.06%   |
| 24      | 29        | 3.46%   |
| 23      | 16        | 1.91%   |
| 21      | 16        | 1.91%   |
| 27      | 13        | 1.55%   |
| 10      | 8         | 0.96%   |
| 19      | 6         | 0.72%   |
| 31      | 5         | 0.6%    |
| 25      | 5         | 0.6%    |
| Unknown | 5         | 0.6%    |
| 18      | 4         | 0.48%   |
| 142     | 3         | 0.36%   |
| 84      | 2         | 0.24%   |
| 72      | 2         | 0.24%   |
| 40      | 2         | 0.24%   |
| 34      | 2         | 0.24%   |
| 32      | 2         | 0.24%   |
| 16      | 2         | 0.24%   |
| 8       | 2         | 0.24%   |
| 49      | 1         | 0.12%   |
| 47      | 1         | 0.12%   |
| 46      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 22      | 1         | 0.12%   |
| 20      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 373       | 44.67%  |
| 201-300        | 308       | 36.89%  |
| 501-600        | 56        | 6.71%   |
| 351-400        | 39        | 4.67%   |
| 401-500        | 26        | 3.11%   |
| 601-700        | 9         | 1.08%   |
| 701-800        | 5         | 0.6%    |
| Unknown        | 5         | 0.6%    |
| 1501-2000      | 4         | 0.48%   |
| More than 2000 | 3         | 0.36%   |
| 1001-1500      | 3         | 0.36%   |
| 801-900        | 2         | 0.24%   |
| 101-200        | 2         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 603       | 78.62%  |
| 16/10   | 132       | 17.21%  |
| 5/4     | 7         | 0.91%   |
| 4/3     | 7         | 0.91%   |
| 3/2     | 7         | 0.91%   |
| Unknown | 4         | 0.52%   |
| 21/9    | 3         | 0.39%   |
| 1.00    | 3         | 0.39%   |
| 32/9    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 220       | 26.25%  |
| 81-90          | 194       | 23.15%  |
| 51-60          | 136       | 16.23%  |
| 71-80          | 89        | 10.62%  |
| 201-250        | 49        | 5.85%   |
| 61-70          | 35        | 4.18%   |
| 121-130        | 30        | 3.58%   |
| 251-300        | 14        | 1.67%   |
| 301-350        | 13        | 1.55%   |
| 151-200        | 11        | 1.31%   |
| 351-500        | 10        | 1.19%   |
| 41-50          | 8         | 0.95%   |
| More than 1000 | 7         | 0.84%   |
| 141-150        | 7         | 0.84%   |
| 501-1000       | 5         | 0.6%    |
| Unknown        | 5         | 0.6%    |
| 1-40           | 2         | 0.24%   |
| 91-100         | 2         | 0.24%   |
| 131-140        | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 497       | 60.24%  |
| 101-120       | 156       | 18.91%  |
| 51-100        | 98        | 11.88%  |
| 161-240       | 45        | 5.45%   |
| More than 240 | 14        | 1.7%    |
| 1-50          | 10        | 1.21%   |
| Unknown       | 5         | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 640       | 79.11%  |
| 2     | 96        | 11.87%  |
| 0     | 63        | 7.79%   |
| 3     | 10        | 1.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 402       | 34.21%  |
| Realtek Semiconductor             | 325       | 27.66%  |
| Broadcom Limited                  | 159       | 13.53%  |
| Qualcomm Atheros                  | 140       | 11.91%  |
| Broadcom                          | 55        | 4.68%   |
| Marvell Technology Group          | 13        | 1.11%   |
| Ralink                            | 10        | 0.85%   |
| TP-Link                           | 6         | 0.51%   |
| Sierra Wireless                   | 6         | 0.51%   |
| MEDIATEK                          | 6         | 0.51%   |
| Nvidia                            | 5         | 0.43%   |
| DisplayLink                       | 5         | 0.43%   |
| Dell                              | 5         | 0.43%   |
| JMicron Technology                | 4         | 0.34%   |
| Ericsson Business Mobile Networks | 4         | 0.34%   |
| AMD                               | 3         | 0.26%   |
| Ralink Technology                 | 2         | 0.17%   |
| Qualcomm Atheros Communications   | 2         | 0.17%   |
| Lenovo                            | 2         | 0.17%   |
| Hewlett-Packard                   | 2         | 0.17%   |
| Fibocom                           | 2         | 0.17%   |
| Cypress Semiconductor             | 2         | 0.17%   |
| Attansic Technology               | 2         | 0.17%   |
| ASUSTek Computer                  | 2         | 0.17%   |
| Xiaomi                            | 1         | 0.09%   |
| Samsung Electronics               | 1         | 0.09%   |
| Qualcomm                          | 1         | 0.09%   |
| NetGear                           | 1         | 0.09%   |
| Microchip Technology              | 1         | 0.09%   |
| Huawei Technologies               | 1         | 0.09%   |
| Google                            | 1         | 0.09%   |
| Edimax Technology                 | 1         | 0.09%   |
| D-Link                            | 1         | 0.09%   |
| Belkin Components                 | 1         | 0.09%   |
| ASIX Electronics                  | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 220       | 15.87%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 142       | 10.25%  |
| Intel Wireless 7260                                                     | 62        | 4.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 51        | 3.68%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 46        | 3.32%   |
| Intel Wireless 8265 / 8275                                              | 46        | 3.32%   |
| Intel Wi-Fi 6 AX200                                                     | 37        | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 36        | 2.6%    |
| Intel Ethernet Connection (4) I219-V                                    | 27        | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 25        | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.73%   |
| Intel Wireless 7265                                                     | 23        | 1.66%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 1.59%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 1.3%    |
| Intel Wireless 8260                                                     | 18        | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 16        | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                                   | 12        | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 0.87%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 0.79%   |
| Intel Wireless 3165                                                     | 10        | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 0.72%   |
| Intel Ethernet Connection I218-LM                                       | 9         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                                   | 9         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.58%   |
| Intel Wireless 3160                                                     | 8         | 0.58%   |
| Intel Ethernet Connection I219-LM                                       | 8         | 0.58%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.58%   |
| Intel Centrino Ultimate-N 6300                                          | 8         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                                    | 7         | 0.51%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.43%   |
| Intel Wireless-AC 9260                                                  | 6         | 0.43%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.43%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.43%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 5         | 0.36%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.36%   |
| MEDIATEK Network controller                                             | 5         | 0.36%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.36%   |
| Intel Ethernet Connection (13) I219-V                                   | 5         | 0.36%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 0.36%   |
| Sierra Wireless EM7345 4G LTE                                           | 4         | 0.29%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.29%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 4         | 0.29%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.29%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 4         | 0.29%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.29%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 4         | 0.29%   |
| Intel Ethernet Connection I219-V                                        | 4         | 0.29%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.29%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 0.29%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 388       | 47.14%  |
| Broadcom Limited                | 153       | 18.59%  |
| Qualcomm Atheros                | 127       | 15.43%  |
| Realtek Semiconductor           | 79        | 9.6%    |
| Broadcom                        | 37        | 4.5%    |
| Ralink                          | 10        | 1.22%   |
| Sierra Wireless                 | 6         | 0.73%   |
| MEDIATEK                        | 5         | 0.61%   |
| TP-Link                         | 3         | 0.36%   |
| Dell                            | 3         | 0.36%   |
| Ralink Technology               | 2         | 0.24%   |
| Qualcomm Atheros Communications | 2         | 0.24%   |
| Fibocom                         | 2         | 0.24%   |
| ASUSTek Computer                | 2         | 0.24%   |
| Qualcomm                        | 1         | 0.12%   |
| NetGear                         | 1         | 0.12%   |
| Edimax Technology               | 1         | 0.12%   |
| Belkin Components               | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 142       | 17.17%  |
| Intel Wireless 7260                                                     | 62        | 7.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 51        | 6.17%   |
| Intel Wireless 8265 / 8275                                              | 46        | 5.56%   |
| Intel Wi-Fi 6 AX200                                                     | 37        | 4.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 25        | 3.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 24        | 2.9%    |
| Intel Wireless 7265                                                     | 23        | 2.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 22        | 2.66%   |
| Intel Wi-Fi 6 AX201                                                     | 21        | 2.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 18        | 2.18%   |
| Intel Wireless 8260                                                     | 18        | 2.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 2.06%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 16        | 1.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 1.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.33%   |
| Intel Wireless 3165                                                     | 10        | 1.21%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 10        | 1.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 8         | 0.97%   |
| Intel Wireless 3160                                                     | 8         | 0.97%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.97%   |
| Intel Centrino Ultimate-N 6300                                          | 8         | 0.97%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 0.85%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                           | 7         | 0.85%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 6         | 0.73%   |
| Intel Wireless-AC 9260                                                  | 6         | 0.73%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.6%    |
| MEDIATEK Network controller                                             | 5         | 0.6%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 5         | 0.6%    |
| Sierra Wireless EM7345 4G LTE                                           | 4         | 0.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.48%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.48%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 4         | 0.48%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 3         | 0.36%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 3         | 0.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.36%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 0.36%   |
| Intel Ultimate N WiFi Link 5300                                         | 3         | 0.36%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.36%   |
| Broadcom BCM43227 802.11b/g/n                                           | 3         | 0.36%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 0.36%   |
| Broadcom BCM4321 802.11a/b/g/n                                          | 3         | 0.36%   |
| Sierra Wireless EM7455                                                  | 2         | 0.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.24%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 2         | 0.24%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.24%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.24%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 2         | 0.24%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.24%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 2         | 0.24%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 2         | 0.24%   |
| Intel Centrino Wireless-N 130                                           | 2         | 0.24%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.24%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 292       | 54.38%  |
| Intel                    | 149       | 27.75%  |
| Broadcom                 | 23        | 4.28%   |
| Qualcomm Atheros         | 22        | 4.1%    |
| Marvell Technology Group | 13        | 2.42%   |
| Broadcom Limited         | 7         | 1.3%    |
| Nvidia                   | 5         | 0.93%   |
| DisplayLink              | 5         | 0.93%   |
| JMicron Technology       | 4         | 0.74%   |
| TP-LINK                  | 3         | 0.56%   |
| Lenovo                   | 2         | 0.37%   |
| Cypress Semiconductor    | 2         | 0.37%   |
| Attansic Technology      | 2         | 0.37%   |
| Xiaomi                   | 1         | 0.19%   |
| Samsung Electronics      | 1         | 0.19%   |
| Microchip Technology     | 1         | 0.19%   |
| MediaTek                 | 1         | 0.19%   |
| Huawei Technologies      | 1         | 0.19%   |
| Google                   | 1         | 0.19%   |
| D-Link                   | 1         | 0.19%   |
| ASIX Electronics         | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 220       | 40.52%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 46        | 8.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 36        | 6.63%   |
| Intel Ethernet Connection (4) I219-V                              | 27        | 4.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 2.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 2.21%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 1.66%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 1.47%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 1.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.92%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.92%   |
| Intel Ethernet Connection (13) I219-V                             | 5         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.92%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.74%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.74%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.74%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.55%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.55%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.55%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.55%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.55%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.55%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.55%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.37%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.37%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.37%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 0.37%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.37%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.37%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.37%   |
| Cypress K38231_03                                                 | 2         | 0.37%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                       | 2         | 0.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.37%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 2         | 0.37%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 0.37%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 2         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.18%   |
| TP-LINK USB 10/100 LAN                                            | 1         | 0.18%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.18%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.18%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.18%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.18%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.18%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.18%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.18%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.18%   |
| MediaTek moto g(8) power lite                                     | 1         | 0.18%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.18%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.18%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 793       | 59.67%  |
| Ethernet | 520       | 39.13%  |
| Modem    | 16        | 1.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 703       | 63.56%  |
| Ethernet | 401       | 36.26%  |
| Modem    | 2         | 0.18%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 484       | 60.35%  |
| 1     | 308       | 38.4%   |
| 3     | 7         | 0.87%   |
| 0     | 3         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 705       | 87.25%  |
| Yes  | 103       | 12.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 303       | 44.1%   |
| Apple                           | 156       | 22.71%  |
| Qualcomm Atheros Communications | 52        | 7.57%   |
| Realtek Semiconductor           | 49        | 7.13%   |
| Lite-On Technology              | 33        | 4.8%    |
| Broadcom                        | 26        | 3.78%   |
| IMC Networks                    | 18        | 2.62%   |
| Foxconn / Hon Hai               | 12        | 1.75%   |
| Cambridge Silicon Radio         | 7         | 1.02%   |
| Ralink                          | 6         | 0.87%   |
| Hewlett-Packard                 | 6         | 0.87%   |
| Realtek                         | 5         | 0.73%   |
| Dell                            | 5         | 0.73%   |
| Toshiba                         | 3         | 0.44%   |
| Taiyo Yuden                     | 2         | 0.29%   |
| ASUSTek Computer                | 2         | 0.29%   |
| Qcom                            | 1         | 0.15%   |
| Alps Electric                   | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Apple Bluetooth USB Host Controller                                                 | 142       | 20.61%  |
| Intel Bluetooth wireless interface                                                  | 101       | 14.66%  |
| Intel Bluetooth Device                                                              | 70        | 10.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 45        | 6.53%   |
| Intel AX201 Bluetooth                                                               | 43        | 6.24%   |
| Intel AX200 Bluetooth                                                               | 38        | 5.52%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 35        | 5.08%   |
| Realtek Bluetooth Radio                                                             | 32        | 4.64%   |
| Lite-On Bluetooth Device                                                            | 25        | 3.63%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 11        | 1.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 1.16%   |
| Apple Bluetooth Host Controller                                                     | 8         | 1.16%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 1.02%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 1.02%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 7         | 1.02%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 7         | 1.02%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 0.87%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 0.87%   |
| Realtek Bluetooth Radio                                                             | 5         | 0.73%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.73%   |
| IMC Networks Bluetooth Device                                                       | 4         | 0.58%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.58%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.44%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.44%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.44%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.44%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.44%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.29%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 0.29%   |
| Lite-On BCM43142A0                                                                  | 2         | 0.29%   |
| IMC Networks Bluetooth module                                                       | 2         | 0.29%   |
| IMC Networks Bluetooth                                                              | 2         | 0.29%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.29%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.29%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.29%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.29%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.29%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.29%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                                           | 2         | 0.29%   |
| Apple Bluetooth HCI                                                                 | 2         | 0.29%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)                                             | 1         | 0.15%   |
| Taiyo Yuden Bluetooth Device                                                        | 1         | 0.15%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.15%   |
| Realtek CSR BS8510                                                                  | 1         | 0.15%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.15%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.15%   |
| Lite-On Wireless_Device                                                             | 1         | 0.15%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.15%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.15%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.15%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.15%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.15%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.15%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                                          | 1         | 0.15%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 0.15%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.15%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.15%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.15%   |
| Dell Wireless 360 Bluetooth                                                         | 1         | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 685       | 75.27%  |
| AMD                    | 114       | 12.53%  |
| Nvidia                 | 76        | 8.35%   |
| Generalplus Technology | 7         | 0.77%   |
| C-Media Electronics    | 5         | 0.55%   |
| Creative Technology    | 4         | 0.44%   |
| Plantronics            | 3         | 0.33%   |
| Logitech               | 3         | 0.33%   |
| GN Netcom              | 3         | 0.33%   |
| Texas Instruments      | 2         | 0.22%   |
| Lenovo                 | 2         | 0.22%   |
| SAVITECH               | 1         | 0.11%   |
| Realtek Semiconductor  | 1         | 0.11%   |
| Razer USA              | 1         | 0.11%   |
| Microsoft              | 1         | 0.11%   |
| JMTek                  | 1         | 0.11%   |
| CMX Systems            | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Broadwell-U Audio Controller                                                                | 163       | 13.52%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 162       | 13.43%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 101       | 8.37%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 80        | 6.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 61        | 5.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 50        | 4.15%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 38        | 3.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 36        | 2.99%   |
| Intel Cannon Lake PCH cAVS                                                                        | 35        | 2.9%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 2.74%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 33        | 2.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 1.66%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 1.66%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 1.66%   |
| Intel 8 Series HD Audio Controller                                                                | 20        | 1.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 18        | 1.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 1.24%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 14        | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 12        | 1%      |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 0.91%   |
| AMD FCH Azalia Controller                                                                         | 11        | 0.91%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 0.83%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 8         | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8         | 0.66%   |
| Intel CM238 HD Audio Controller                                                                   | 7         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.58%   |
| Generalplus Technology Usb Audio Device                                                           | 7         | 0.58%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 0.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 0.5%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.41%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.41%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.41%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.41%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.33%   |
| AMD High Definition Audio Controller                                                              | 4         | 0.33%   |
| Nvidia Audio device                                                                               | 3         | 0.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 3         | 0.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.25%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.25%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.25%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.17%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.17%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.17%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.17%   |
| Lenovo ThinkPad Dock Audio                                                                        | 2         | 0.17%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.17%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.17%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.17%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.17%   |
| SAVITECH SA9023 audio controller                                                                  | 1         | 0.08%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.08%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 263       | 32.03%  |
| SK Hynix            | 158       | 19.24%  |
| Micron Technology   | 94        | 11.45%  |
| Crucial             | 63        | 7.67%   |
| Elpida              | 53        | 6.46%   |
| Kingston            | 50        | 6.09%   |
| Unknown             | 43        | 5.24%   |
| Ramaxel Technology  | 19        | 2.31%   |
| A-DATA Technology   | 16        | 1.95%   |
| Corsair             | 13        | 1.58%   |
| Nanya Technology    | 10        | 1.22%   |
| Team                | 5         | 0.61%   |
| Smart               | 5         | 0.61%   |
| GOODRAM             | 4         | 0.49%   |
| Unknown (ABCD)      | 2         | 0.24%   |
| Transcend           | 2         | 0.24%   |
| PNY                 | 2         | 0.24%   |
| Patriot             | 2         | 0.24%   |
| ASint Technology    | 2         | 0.24%   |
| AMD                 | 2         | 0.24%   |
| Wilk                | 1         | 0.12%   |
| Unifosa             | 1         | 0.12%   |
| Teikon              | 1         | 0.12%   |
| SMART Brazil        | 1         | 0.12%   |
| Silicon Power       | 1         | 0.12%   |
| Sesame              | 1         | 0.12%   |
| Novatech            | 1         | 0.12%   |
| Kllisre             | 1         | 0.12%   |
| Infineon            | 1         | 0.12%   |
| Goldkey             | 1         | 0.12%   |
| G.Skill             | 1         | 0.12%   |
| Avant               | 1         | 0.12%   |
| A-TECH              | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                         | 61        | 7.13%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s               | 38        | 4.44%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 30        | 3.51%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 20        | 2.34%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 19        | 2.22%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 19        | 2.22%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s              | 19        | 2.22%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                          | 15        | 1.75%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s             | 12        | 1.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 1.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 10        | 1.17%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s                | 10        | 1.17%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 8         | 0.94%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 8         | 0.94%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 7         | 0.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 0.82%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 6         | 0.7%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 6         | 0.7%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 6         | 0.7%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.7%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 6         | 0.7%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 6         | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 6         | 0.7%    |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 5         | 0.58%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 5         | 0.58%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 5         | 0.58%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 5         | 0.58%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 5         | 0.58%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 5         | 0.58%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 4         | 0.47%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.47%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 4         | 0.47%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s             | 4         | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 3         | 0.35%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                 | 3         | 0.35%   |
| Unknown RAM Module 1GB SODIMM DDR2                                  | 3         | 0.35%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s               | 3         | 0.35%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.35%   |
| SK Hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 3         | 0.35%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 0.35%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 0.35%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s           | 3         | 0.35%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.35%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.35%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.35%   |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                          | 3         | 0.35%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 3         | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.35%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 0.35%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.35%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s           | 3         | 0.35%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 3         | 0.35%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                | 3         | 0.35%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 3         | 0.35%   |
| Micron RAM 4ATF51264HZ-2G3B1 4096MB SODIMM DDR4 2400MT/s            | 3         | 0.35%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s          | 3         | 0.35%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s             | 3         | 0.35%   |
| Unknown SODIMM 1GB SODIMM DDR2 667MT/s                              | 2         | 0.23%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                              | 2         | 0.23%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 358       | 49.52%  |
| DDR4    | 270       | 37.34%  |
| DDR2    | 34        | 4.7%    |
| LPDDR3  | 22        | 3.04%   |
| LPDDR4  | 18        | 2.49%   |
| SDRAM   | 9         | 1.24%   |
| DDR     | 9         | 1.24%   |
| Unknown | 2         | 0.28%   |
| DRAM    | 1         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 678       | 93.52%  |
| Row Of Chips | 41        | 5.66%   |
| Chip         | 5         | 0.69%   |
| Unknown      | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 261       | 33.72%  |
| 8192  | 203       | 26.23%  |
| 2048  | 187       | 24.16%  |
| 16384 | 63        | 8.14%   |
| 1024  | 33        | 4.26%   |
| 32768 | 16        | 2.07%   |
| 512   | 9         | 1.16%   |
| 256   | 2         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 296       | 38.54%  |
| 2667    | 134       | 17.45%  |
| 3200    | 96        | 12.5%   |
| 2400    | 44        | 5.73%   |
| 1333    | 34        | 4.43%   |
| 2133    | 30        | 3.91%   |
| 1334    | 29        | 3.78%   |
| 667     | 17        | 2.21%   |
| Unknown | 15        | 1.95%   |
| 3266    | 10        | 1.3%    |
| 1867    | 10        | 1.3%    |
| 4267    | 9         | 1.17%   |
| 1067    | 9         | 1.17%   |
| 533     | 9         | 1.17%   |
| 975     | 5         | 0.65%   |
| 4199    | 4         | 0.52%   |
| 333     | 4         | 0.52%   |
| 1866    | 3         | 0.39%   |
| 800     | 3         | 0.39%   |
| 400     | 3         | 0.39%   |
| 4266    | 2         | 0.26%   |
| 3000    | 1         | 0.13%   |
| 2048    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |
| Canon               | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-2010P Mono Laser Printer | 1         | 25%     |
| HP DeskJet 2130 series              | 1         | 25%     |
| Canon PIXMA MX920 Series            | 1         | 25%     |
| Brother MFC-L2707DW                 | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 139       | 23.84%  |
| Quanta                                 | 76        | 13.04%  |
| IMC Networks                           | 69        | 11.84%  |
| Acer                                   | 64        | 10.98%  |
| Realtek Semiconductor                  | 45        | 7.72%   |
| Microdia                               | 40        | 6.86%   |
| Suyin                                  | 20        | 3.43%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 3.09%   |
| Sunplus Innovation Technology          | 17        | 2.92%   |
| Lite-On Technology                     | 17        | 2.92%   |
| Syntek                                 | 11        | 1.89%   |
| Apple                                  | 11        | 1.89%   |
| Logitech                               | 9         | 1.54%   |
| Luxvisions Innotech Limited            | 8         | 1.37%   |
| Silicon Motion                         | 6         | 1.03%   |
| Lenovo                                 | 6         | 1.03%   |
| Alcor Micro                            | 4         | 0.69%   |
| Z-Star Microelectronics                | 3         | 0.51%   |
| Primax Electronics                     | 3         | 0.51%   |
| Ricoh                                  | 2         | 0.34%   |
| Intel                                  | 2         | 0.34%   |
| Sunplus Technology                     | 1         | 0.17%   |
| Sonix Technology                       | 1         | 0.17%   |
| Pixart Imaging                         | 1         | 0.17%   |
| OmniVision Technologies                | 1         | 0.17%   |
| Mimaki Engineering                     | 1         | 0.17%   |
| KYE Systems (Mouse Systems)            | 1         | 0.17%   |
| Importek                               | 1         | 0.17%   |
| Holitech                               | 1         | 0.17%   |
| Generalplus Technology                 | 1         | 0.17%   |
| eMPIA Technology                       | 1         | 0.17%   |
| ALi                                    | 1         | 0.17%   |
| A4Tech                                 | 1         | 0.17%   |
| 8SSC20F27114V1SR0C71XEG                | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 54        | 9.23%   |
| Quanta Chromebook HD Camera                                                | 37        | 6.32%   |
| Microdia Integrated_Webcam_HD                                              | 23        | 3.93%   |
| IMC Networks Integrated Camera                                             | 22        | 3.76%   |
| Chicony HD WebCam                                                          | 19        | 3.25%   |
| Realtek Integrated_Webcam_HD                                               | 17        | 2.91%   |
| Quanta VGA WebCam                                                          | 17        | 2.91%   |
| Acer Integrated Camera                                                     | 16        | 2.74%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 15        | 2.56%   |
| Acer BisonCam, NB Pro                                                      | 15        | 2.56%   |
| Chicony Chromebook HD Camera                                               | 10        | 1.71%   |
| Acer SunplusIT Integrated Camera                                           | 10        | 1.71%   |
| Sunplus Integrated_Webcam_HD                                               | 8         | 1.37%   |
| Chicony HP HD Camera                                                       | 8         | 1.37%   |
| Lite-On Integrated Camera                                                  | 7         | 1.2%    |
| Syntek Integrated Camera                                                   | 6         | 1.03%   |
| Chicony Integrated Camera (1280x720@30)                                    | 6         | 1.03%   |
| Acer Lenovo EasyCamera                                                     | 6         | 1.03%   |
| Realtek Integrated Webcam                                                  | 5         | 0.85%   |
| Quanta HP TrueVision HD Camera                                             | 5         | 0.85%   |
| Lite-On HP HD Camera                                                       | 5         | 0.85%   |
| Lenovo Integrated Webcam                                                   | 5         | 0.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 5         | 0.85%   |
| Chicony Lenovo EasyCamera                                                  | 5         | 0.85%   |
| Quanta HD WebCam                                                           | 4         | 0.68%   |
| Quanta HD User Facing                                                      | 4         | 0.68%   |
| Microdia Integrated Webcam                                                 | 4         | 0.68%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 4         | 0.68%   |
| IMC Networks HP TrueVision HD Camera                                       | 4         | 0.68%   |
| Chicony USB2.0 Camera                                                      | 4         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 4         | 0.68%   |
| Acer EasyCamera                                                            | 4         | 0.68%   |
| Suyin Acer CrystalEye Webcam                                               | 3         | 0.51%   |
| Realtek Integrated Webcam HD                                               | 3         | 0.51%   |
| Realtek HD WebCam                                                          | 3         | 0.51%   |
| Quanta HP Webcam                                                           | 3         | 0.51%   |
| Microdia Integrated Webcam HD                                              | 3         | 0.51%   |
| IMC Networks UVC VGA Webcam                                                | 3         | 0.51%   |
| IMC Networks ov9734_azurewave_camera                                       | 3         | 0.51%   |
| Chicony HP TrueVision HD Camera                                            | 3         | 0.51%   |
| Chicony HP Truevision HD                                                   | 3         | 0.51%   |
| Chicony EasyCamera                                                         | 3         | 0.51%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam               | 3         | 0.51%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.51%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 3         | 0.51%   |
| Apple Built-in iSight                                                      | 3         | 0.51%   |
| Acer ThinkPad Integrated Camera                                            | 3         | 0.51%   |
| Acer HD Webcam                                                             | 3         | 0.51%   |
| Syntek Lenovo EasyCamera                                                   | 2         | 0.34%   |
| Suyin Integrated_Webcam_HD                                                 | 2         | 0.34%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 2         | 0.34%   |
| Suyin Asus Integrated Webcam                                               | 2         | 0.34%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 2         | 0.34%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.34%   |
| Sunplus Laptop_Integrated_Webcam_FHD                                       | 2         | 0.34%   |
| Sunplus HP Universal Camera                                                | 2         | 0.34%   |
| Sunplus HD WebCam                                                          | 2         | 0.34%   |
| Silicon Motion HP Webcam-101                                               | 2         | 0.34%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 0.34%   |
| Realtek USB Camera                                                         | 2         | 0.34%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 50        | 38.76%  |
| Synaptics                  | 34        | 26.36%  |
| Shenzhen Goodix Technology | 21        | 16.28%  |
| Upek                       | 7         | 5.43%   |
| AuthenTec                  | 7         | 5.43%   |
| LighTuning Technology      | 4         | 3.1%    |
| Elan Microelectronics      | 4         | 3.1%    |
| STMicroelectronics         | 2         | 1.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 21        | 16.28%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 13.18%  |
| Shenzhen Goodix  Fingerprint Device                                        | 12        | 9.3%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 6.98%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 6.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 5.43%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 4.65%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 3.88%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 3.88%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 3.1%    |
| Elan ELAN:Fingerprint                                                      | 4         | 3.1%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 2.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.55%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.55%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.55%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.78%   |
| Validity Sensors VFS491                                                    | 1         | 0.78%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.78%   |
| Synaptics  WBDI                                                            | 1         | 0.78%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.78%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.78%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 20        | 35.09%  |
| Alcor Micro | 19        | 33.33%  |
| Upek        | 7         | 12.28%  |
| Lenovo      | 7         | 12.28%  |
| O2 Micro    | 2         | 3.51%   |
| OmniKey     | 1         | 1.75%   |
| Cherry      | 1         | 1.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 19        | 33.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 12.28%  |
| Lenovo Integrated Smart Card Reader                                          | 7         | 12.28%  |
| Broadcom 5880                                                                | 7         | 12.28%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 8.77%   |
| Broadcom 58200                                                               | 5         | 8.77%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.51%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 3.51%   |
| OmniKey CardMan 4321                                                         | 1         | 1.75%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.75%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.75%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 388       | 48.02%  |
| 1     | 350       | 43.32%  |
| 2     | 59        | 7.3%    |
| 3     | 10        | 1.24%   |
| 4     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Multimedia controller    | 158       | 32.78%  |
| Fingerprint reader       | 128       | 26.56%  |
| Graphics card            | 91        | 18.88%  |
| Chipcard                 | 48        | 9.96%   |
| Net/wireless             | 24        | 4.98%   |
| Bluetooth                | 11        | 2.28%   |
| Communication controller | 7         | 1.45%   |
| Storage                  | 5         | 1.04%   |
| Card reader              | 3         | 0.62%   |
| Network                  | 2         | 0.41%   |
| Tv card                  | 1         | 0.21%   |
| Net/ethernet             | 1         | 0.21%   |
| Modem                    | 1         | 0.21%   |
| Flash memory             | 1         | 0.21%   |
| Firewire controller      | 1         | 0.21%   |

