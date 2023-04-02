Zorin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 3974

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Vostro 1520                 | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [22d22e0742](https://linux-hardware.org/?probe=22d22e0742) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [2994622700](https://linux-hardware.org/?probe=2994622700) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Positivo      | S14SL01                     | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| HP            | kip                         | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Positivo      | Q232A                       | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| Dell          | Precision M4500             | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| WEIPAI        | S15                         | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | Latitude E5510              | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| HP            | 255 G5                      | [99e2d83974](https://linux-hardware.org/?probe=99e2d83974) | Mar 24, 2023 |
| Dell          | Inspiron 3721               | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion dv6                | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Dell          | Latitude E7240              | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| Dell          | Inspiron 5405               | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Acer          | TravelMate 2490             | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| Dell          | Inspiron 5423               | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Google        | Kip                         | [84b79bf446](https://linux-hardware.org/?probe=84b79bf446) | Mar 19, 2023 |
| Google        | Kip                         | [4e63ea7ac8](https://linux-hardware.org/?probe=4e63ea7ac8) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Dell          | Inspiron 3721               | [c7b5ea67bb](https://linux-hardware.org/?probe=c7b5ea67bb) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| ASUSTek       | G53SX                       | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| HP            | Pavilion dm1                | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Alienware     | 15 R3                       | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| Google        | Babymega                    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| Acer          | Aspire 5736Z                | [d9e1bb3da7](https://linux-hardware.org/?probe=d9e1bb3da7) | Mar 16, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [f6a3a68640](https://linux-hardware.org/?probe=f6a3a68640) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| Google        | Celes                       | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| HP            | Pavilion dv6                | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| HP            | Pavilion 15                 | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| Toshiba       | PORTEGE X30-D               | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Dell          | Latitude E5470              | [86adaddcae](https://linux-hardware.org/?probe=86adaddcae) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| HP            | Pavilion dv6                | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Dell          | Latitude E5470              | [e7e23885b7](https://linux-hardware.org/?probe=e7e23885b7) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Medion        | Akoya E1318T                | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | [6648af3696](https://linux-hardware.org/?probe=6648af3696) | Mar 10, 2023 |
| Lenovo        | G50-45 80E3                 | [807d1626b4](https://linux-hardware.org/?probe=807d1626b4) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [3b0a7cfbf0](https://linux-hardware.org/?probe=3b0a7cfbf0) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [08bfa4188e](https://linux-hardware.org/?probe=08bfa4188e) | Mar 10, 2023 |
| HP            | ProBook 4530s               | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Precision M6700             | [7a02d78344](https://linux-hardware.org/?probe=7a02d78344) | Mar 10, 2023 |
| HP            | ZBook 17 G2                 | [565c8963d4](https://linux-hardware.org/?probe=565c8963d4) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| Acer          | Aspire M3-581G              | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | Latitude 3180               | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| Multilaser    | PC130                       | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| ASUSTek       | K50IJ                       | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| Dell          | Latitude E4310              | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| Google        | Candy                       | [e74102ff2c](https://linux-hardware.org/?probe=e74102ff2c) | Mar 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [3f1ebc8271](https://linux-hardware.org/?probe=3f1ebc8271) | Mar 07, 2023 |
| Google        | Lillipup                    | [33350c987b](https://linux-hardware.org/?probe=33350c987b) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Google        | Lillipup                    | [214481f959](https://linux-hardware.org/?probe=214481f959) | Mar 06, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Timi          | TM1701                      | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1237954f03](https://linux-hardware.org/?probe=1237954f03) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [a3b6a280c1](https://linux-hardware.org/?probe=a3b6a280c1) | Mar 02, 2023 |
| HP            | Notebook                    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [7b17e49d0f](https://linux-hardware.org/?probe=7b17e49d0f) | Mar 02, 2023 |
| ASUSTek       | X200MA                      | [95b0a4d944](https://linux-hardware.org/?probe=95b0a4d944) | Mar 02, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| Toshiba       | Satellite S55t-B            | [69734289ba](https://linux-hardware.org/?probe=69734289ba) | Mar 01, 2023 |
| MSI           | Raider GE66 12UHS           | [3fcfdd9fba](https://linux-hardware.org/?probe=3fcfdd9fba) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| Dell          | Inspiron N5010              | [480ff87a20](https://linux-hardware.org/?probe=480ff87a20) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| HP            | ENVY 17                     | [61d1252ef3](https://linux-hardware.org/?probe=61d1252ef3) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
| Dell          | Inspiron 3793               | [d7b51f6048](https://linux-hardware.org/?probe=d7b51f6048) | Feb 27, 2023 |
| HP            | Pavilion dv7                | [d5da5f62b8](https://linux-hardware.org/?probe=d5da5f62b8) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [42acb38635](https://linux-hardware.org/?probe=42acb38635) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e8c76a33fe](https://linux-hardware.org/?probe=e8c76a33fe) | Feb 27, 2023 |
| Dell          | Vostro 1540                 | [8f09ea4351](https://linux-hardware.org/?probe=8f09ea4351) | Feb 27, 2023 |
| HP            | ENVY m7 Notebook            | [14374fbcc8](https://linux-hardware.org/?probe=14374fbcc8) | Feb 27, 2023 |
| Lenovo        | V570 1066EDG                | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| HP            | 620                         | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Dell          | Latitude E6440              | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| HP            | Laptop 15-dy2xxx            | [7f88a11698](https://linux-hardware.org/?probe=7f88a11698) | Feb 25, 2023 |
| Digibras      | NH4CU03                     | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| HP            | Laptop 14-ck0xxx            | [bafb67390c](https://linux-hardware.org/?probe=bafb67390c) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Apple         | MacBookPro12,1              | [3b27d3609f](https://linux-hardware.org/?probe=3b27d3609f) | Feb 24, 2023 |
| HP            | ProBook 4545s               | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| ASUSTek       | T100TAF                     | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| Dell          | Latitude 7480               | [fd80b301db](https://linux-hardware.org/?probe=fd80b301db) | Feb 23, 2023 |
| Lenovo        | G500 20236                  | [294c5c45e6](https://linux-hardware.org/?probe=294c5c45e6) | Feb 23, 2023 |
| DERE          | V14                         | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| HP            | ENVY 17                     | [ea0b2e63ef](https://linux-hardware.org/?probe=ea0b2e63ef) | Feb 21, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [5d32bc7f7c](https://linux-hardware.org/?probe=5d32bc7f7c) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [a00e724475](https://linux-hardware.org/?probe=a00e724475) | Feb 21, 2023 |
| Dell          | System XPS L502X            | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| HP            | 620                         | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Toshiba       | PORTEGE Z30-A               | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Dell          | Latitude E5440              | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Toshiba       | Satellite L50-B             | [3c53a60245](https://linux-hardware.org/?probe=3c53a60245) | Feb 19, 2023 |
| Toshiba       | Satellite L50D-B            | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [752cdf5b2b](https://linux-hardware.org/?probe=752cdf5b2b) | Feb 19, 2023 |
| Multilaser    | PC130                       | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| HP            | Unknown                     | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| HP            | ENVY 17                     | [de8af1b249](https://linux-hardware.org/?probe=de8af1b249) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Medion        | E7220                       | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| ASUSTek       | K50IJ                       | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [a7aa67f64e](https://linux-hardware.org/?probe=a7aa67f64e) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [eda645cefe](https://linux-hardware.org/?probe=eda645cefe) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [66c15f037d](https://linux-hardware.org/?probe=66c15f037d) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [9e154ea3a4](https://linux-hardware.org/?probe=9e154ea3a4) | Feb 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [d1edc30dac](https://linux-hardware.org/?probe=d1edc30dac) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | [baa5f72e80](https://linux-hardware.org/?probe=baa5f72e80) | Feb 12, 2023 |
| HP            | Notebook                    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6f7c0f381e](https://linux-hardware.org/?probe=6f7c0f381e) | Feb 12, 2023 |
| HP            | Laptop 15-dy2xxx            | [131d5052d1](https://linux-hardware.org/?probe=131d5052d1) | Feb 11, 2023 |
| Dell          | Inspiron 16 5625            | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [518f413d2f](https://linux-hardware.org/?probe=518f413d2f) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [a24d7423c4](https://linux-hardware.org/?probe=a24d7423c4) | Feb 11, 2023 |
| Dell          | Latitude E6400              | [8c489c529a](https://linux-hardware.org/?probe=8c489c529a) | Feb 11, 2023 |
| Acer          | TravelMate P253             | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| HONOR         | HLYL-WXX9                   | [9d916e8e03](https://linux-hardware.org/?probe=9d916e8e03) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| Acer          | Predator G3-571             | [50fe192ea1](https://linux-hardware.org/?probe=50fe192ea1) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [8513e7eb92](https://linux-hardware.org/?probe=8513e7eb92) | Feb 09, 2023 |
| Positivo      | Smash2                      | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [5c9ca6cd47](https://linux-hardware.org/?probe=5c9ca6cd47) | Feb 09, 2023 |
| HP            | Pavilion dv7                | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Acer          | Aspire 5755G                | [0d0c6fe86c](https://linux-hardware.org/?probe=0d0c6fe86c) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [ae78404854](https://linux-hardware.org/?probe=ae78404854) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [b2c3e0fa85](https://linux-hardware.org/?probe=b2c3e0fa85) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Lenovo        | V570 1066EDG                | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| Acer          | Okinawa                     | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Sony          | VGN-Z31XN_B                 | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| TWC           | Unknown                     | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| MSI           | GF63 Thin 11UC              | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Intel         | Unknown                     | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Sony          | VPCEG36FX                   | [d760d9e79b](https://linux-hardware.org/?probe=d760d9e79b) | Feb 06, 2023 |
| Acer          | TravelMate P253             | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Acer          | One S1002                   | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Insyde        | CherryTrail                 | [b3ad379bdc](https://linux-hardware.org/?probe=b3ad379bdc) | Feb 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| Dell          | Latitude D630               | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| Dell          | Inspiron 5537               | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| Intel         | Unknown                     | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| MSI           | GF63 Thin 11UC              | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| MSI           | Raider GE66 12UHS           | [75e83dae8b](https://linux-hardware.org/?probe=75e83dae8b) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | [d221bc6b8d](https://linux-hardware.org/?probe=d221bc6b8d) | Feb 01, 2023 |
| Dell          | Latitude E6540              | [156a047a82](https://linux-hardware.org/?probe=156a047a82) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [a663152b7c](https://linux-hardware.org/?probe=a663152b7c) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [ae3838cc5d](https://linux-hardware.org/?probe=ae3838cc5d) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | Pavilion Notebook           | [912213d849](https://linux-hardware.org/?probe=912213d849) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [456415a23e](https://linux-hardware.org/?probe=456415a23e) | Jan 30, 2023 |
| Dell          | Latitude E6520              | [f042c5966b](https://linux-hardware.org/?probe=f042c5966b) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1F20... | [39b709296b](https://linux-hardware.org/?probe=39b709296b) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| Dell          | Precision 5530              | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [62b104b3d2](https://linux-hardware.org/?probe=62b104b3d2) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [b7cf9bee5c](https://linux-hardware.org/?probe=b7cf9bee5c) | Jan 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Dell          | Precision 5530              | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| Dell          | Vostro 1520                 | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| Dell          | Latitude E7470              | [4245585e75](https://linux-hardware.org/?probe=4245585e75) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| HP            | Notebook                    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [de7bee1cd6](https://linux-hardware.org/?probe=de7bee1cd6) | Jan 26, 2023 |
| Alienware     | M11xR3                      | [634b7f8eb0](https://linux-hardware.org/?probe=634b7f8eb0) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| HP            | 625                         | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Google        | Blorb                       | [adae28c837](https://linux-hardware.org/?probe=adae28c837) | Jan 25, 2023 |
| HP            | EliteBook Folio 9470m       | [5dfd026f77](https://linux-hardware.org/?probe=5dfd026f77) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [61d7aa3ef9](https://linux-hardware.org/?probe=61d7aa3ef9) | Jan 25, 2023 |
| Google        | Kip                         | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| HP            | Laptop 15-dy2xxx            | [af9518a90a](https://linux-hardware.org/?probe=af9518a90a) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| AXDIA Inte... | WINPAD V10                  | [dc93e9d9f0](https://linux-hardware.org/?probe=dc93e9d9f0) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [6fd520f670](https://linux-hardware.org/?probe=6fd520f670) | Jan 23, 2023 |
| Acer          | Aspire SW5-012              | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ProBook 440 G5              | [788d350490](https://linux-hardware.org/?probe=788d350490) | Jan 23, 2023 |
| Dell          | Latitude E7470              | [525bcdd915](https://linux-hardware.org/?probe=525bcdd915) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Acer          | Aspire A315-59              | [20b73bd156](https://linux-hardware.org/?probe=20b73bd156) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6d5ca0b2e3](https://linux-hardware.org/?probe=6d5ca0b2e3) | Jan 22, 2023 |
| Packard Be... | EasyNote TE69KB             | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| Dell          | Precision M6800             | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| HP            | 625                         | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| Lenovo        | V110-15IAP 80TG             | [1707a21fed](https://linux-hardware.org/?probe=1707a21fed) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| HP            | 625                         | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Dell          | Inspiron 1525               | [548d331968](https://linux-hardware.org/?probe=548d331968) | Jan 21, 2023 |
| ASUSTek       | X453MA                      | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| ASUSTek       | G74Sx                       | [f3af245bf8](https://linux-hardware.org/?probe=f3af245bf8) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| ASUSTek       | A6U                         | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| HP            | ProBook 4740s               | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Acer          | Aspire E5-774G              | [f3ab78c392](https://linux-hardware.org/?probe=f3ab78c392) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [4908236396](https://linux-hardware.org/?probe=4908236396) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [9e17ffeecc](https://linux-hardware.org/?probe=9e17ffeecc) | Jan 19, 2023 |
| Lenovo        | V110-15IAP 80TG             | [cfe9a9d924](https://linux-hardware.org/?probe=cfe9a9d924) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | 15                          | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| Google        | Kip                         | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | Pavilion dv7                | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [473ae331ec](https://linux-hardware.org/?probe=473ae331ec) | Jan 16, 2023 |
| Wortmann      | Mobile 1524                 | [17fc7e2f75](https://linux-hardware.org/?probe=17fc7e2f75) | Jan 16, 2023 |
| HP            | Pavilion 17                 | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Lenovo        | G560 0679                   | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Sony          | VGN-SR16GN_B                | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [19531b68b1](https://linux-hardware.org/?probe=19531b68b1) | Jan 14, 2023 |
| HP            | EliteBook 745 G5            | [941c62872e](https://linux-hardware.org/?probe=941c62872e) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [ddf679df3a](https://linux-hardware.org/?probe=ddf679df3a) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| ASUSTek       | K93SV                       | [250b4a09a0](https://linux-hardware.org/?probe=250b4a09a0) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| HP            | Laptop 14-bw0xx             | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| Acer          | Aspire 2920                 | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Samsung       | R520/R522/R620              | [78eb96d148](https://linux-hardware.org/?probe=78eb96d148) | Jan 11, 2023 |
| Samsung       | R520/R522/R620              | [9dfcb68d9a](https://linux-hardware.org/?probe=9dfcb68d9a) | Jan 11, 2023 |
| HP            | Notebook                    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| Dell          | Inspiron 3583               | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Dell          | Inspiron 15-3567            | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| HP            | Pavilion dv6                | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| Dell          | Latitude E6510              | [28cceb82e3](https://linux-hardware.org/?probe=28cceb82e3) | Jan 09, 2023 |
| Acer          | Aspire A315-53              | [a8f14a8a8e](https://linux-hardware.org/?probe=a8f14a8a8e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5bd32eb6f6](https://linux-hardware.org/?probe=5bd32eb6f6) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [88ba7d805e](https://linux-hardware.org/?probe=88ba7d805e) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [b5b4c3f6ef](https://linux-hardware.org/?probe=b5b4c3f6ef) | Jan 08, 2023 |
| MSI           | CR62 6M                     | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| Dell          | Inspiron 5559               | [4c680e9948](https://linux-hardware.org/?probe=4c680e9948) | Jan 07, 2023 |
| HP            | Laptop 17-cp1xxx            | [d699356fd1](https://linux-hardware.org/?probe=d699356fd1) | Jan 07, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [76f452827f](https://linux-hardware.org/?probe=76f452827f) | Jan 06, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Multilaser    | PC024                       | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Dell          | Precision M90               | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | ProBook 4540s               | [6e2638a12e](https://linux-hardware.org/?probe=6e2638a12e) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Acer          | Aspire V3-772G              | [4ec59dca55](https://linux-hardware.org/?probe=4ec59dca55) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| HP            | EliteBook Folio 9470m       | [309e449325](https://linux-hardware.org/?probe=309e449325) | Jan 03, 2023 |
| HP            | Pavilion dv7                | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Apple         | MacBookPro12,1              | [ce3dc1998f](https://linux-hardware.org/?probe=ce3dc1998f) | Jan 02, 2023 |
| HP            | EliteBook 2570p             | [fcf5d132a5](https://linux-hardware.org/?probe=fcf5d132a5) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| Dell          | Latitude E5440              | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| HP            | Pavilion dv6                | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0360bb01d0](https://linux-hardware.org/?probe=0360bb01d0) | Jan 01, 2023 |
| Dell          | Latitude E5500              | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| HP            | Pavilion dv6                | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Dell          | Latitude E6540              | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | Latitude 7490               | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Unknown       | Unknown                     | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| HP            | Pavilion dv7                | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| HP            | Pavilion g7                 | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Lenovo        | G500 20236                  | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| Sony          | VJZ13A                      | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| MSI           | MS-1035                     | [6a8a6b7de4](https://linux-hardware.org/?probe=6a8a6b7de4) | Dec 19, 2022 |
| GPD           | G1619-04                    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Dell          | Studio XPS 1645             | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| Dell          | Inspiron 7537               | [7064963568](https://linux-hardware.org/?probe=7064963568) | Dec 18, 2022 |
| ASUSTek       | S500CA                      | [55cf134a8b](https://linux-hardware.org/?probe=55cf134a8b) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| GPU Compan... | GWTC116-2                   | [e64e0ee27a](https://linux-hardware.org/?probe=e64e0ee27a) | Dec 17, 2022 |
| Fusion5       | C60Bv2-128GB                | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| HP            | Compaq 6910p (RM231UT#AB... | [4653b4877b](https://linux-hardware.org/?probe=4653b4877b) | Dec 17, 2022 |
| HP            | 250 G1                      | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| Jumper        | EZbook                      | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Jumper        | EZbook                      | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Toshiba       | Satellite P500              | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| Google        | Blorb                       | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Machcreato... | 14                          | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| HP            | Pavilion dv7                | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| HP            | Laptop 17-bs0xx             | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | [09b233d518](https://linux-hardware.org/?probe=09b233d518) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Apple         | MacBook4,1                  | [45ad14cbc2](https://linux-hardware.org/?probe=45ad14cbc2) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Alienware     | 18                          | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Sony          | VGN-NR32M_S                 | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X751SA                      | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [097b783ae5](https://linux-hardware.org/?probe=097b783ae5) | Dec 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [0f4312c32e](https://linux-hardware.org/?probe=0f4312c32e) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| HP            | Laptop 14-bw0xx             | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| Toshiba       | Satellite L500              | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Dell          | Latitude 7490               | [6021de66f0](https://linux-hardware.org/?probe=6021de66f0) | Dec 07, 2022 |
| HP            | ProBook 640 G1              | [1c99985945](https://linux-hardware.org/?probe=1c99985945) | Dec 07, 2022 |
| Dell          | Studio 1558                 | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| Dell          | Latitude 7490               | [2b29482df2](https://linux-hardware.org/?probe=2b29482df2) | Dec 06, 2022 |
| Dell          | Inspiron 5558               | [f8e7b50548](https://linux-hardware.org/?probe=f8e7b50548) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Toshiba       | Satellite L855              | [a28616ab1b](https://linux-hardware.org/?probe=a28616ab1b) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [9775fe7147](https://linux-hardware.org/?probe=9775fe7147) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| HP            | Pavilion dv7                | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [e74106a982](https://linux-hardware.org/?probe=e74106a982) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [26e6a987d0](https://linux-hardware.org/?probe=26e6a987d0) | Dec 03, 2022 |
| HP            | Pavilion g4                 | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Acer          | Aspire V5-121               | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | Latitude E5520              | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Dell          | System XPS L502X            | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Dell          | Latitude E6540              | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| ASUSTek       | X202E                       | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Samsung       | 600B4B/600B5B               | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Toshiba       | Satellite S55t-B            | [4b01021314](https://linux-hardware.org/?probe=4b01021314) | Nov 24, 2022 |
| HP            | Notebook                    | [d65b0a06fe](https://linux-hardware.org/?probe=d65b0a06fe) | Nov 24, 2022 |
| HP            | Notebook                    | [54b351457e](https://linux-hardware.org/?probe=54b351457e) | Nov 24, 2022 |
| HP            | 15                          | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| Apple         | MacBookPro5,4               | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Framework     | Laptop                      | [6cc495c0d9](https://linux-hardware.org/?probe=6cc495c0d9) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7c034bd91](https://linux-hardware.org/?probe=a7c034bd91) | Nov 19, 2022 |
| Dell          | Latitude E6540              | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | 14                          | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| HP            | 14                          | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ef7af01d47](https://linux-hardware.org/?probe=ef7af01d47) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ceca708c95](https://linux-hardware.org/?probe=ceca708c95) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [23f8c23e8b](https://linux-hardware.org/?probe=23f8c23e8b) | Nov 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| Gateway       | NV59C                       | [b3be978b72](https://linux-hardware.org/?probe=b3be978b72) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [b240ae5338](https://linux-hardware.org/?probe=b240ae5338) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [d1049db1fb](https://linux-hardware.org/?probe=d1049db1fb) | Nov 15, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [73bc7e7428](https://linux-hardware.org/?probe=73bc7e7428) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [9d798077df](https://linux-hardware.org/?probe=9d798077df) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Microtech     | ebookLite                   | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| Acer          | Extensa 2530                | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| Hampoo        | Cherry Trail CR             | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| HP            | 250 G4                      | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| Microtech     | ebookLite                   | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [2e79d44f43](https://linux-hardware.org/?probe=2e79d44f43) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [1f9e0a7e16](https://linux-hardware.org/?probe=1f9e0a7e16) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [d3a6ca47df](https://linux-hardware.org/?probe=d3a6ca47df) | Nov 11, 2022 |
| HP            | 2000                        | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Microtech     | ebookLite                   | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| ASUSTek       | G50VT                       | [57f7e69b18](https://linux-hardware.org/?probe=57f7e69b18) | Nov 10, 2022 |
| HP            | Pavilion Notebook           | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| GPU Compan... | GWTN156-2BK                 | [cf64038190](https://linux-hardware.org/?probe=cf64038190) | Nov 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c17772f8e7](https://linux-hardware.org/?probe=c17772f8e7) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| HP            | ProBook 430 G4              | [5d6f34affd](https://linux-hardware.org/?probe=5d6f34affd) | Nov 08, 2022 |
| Gateway       | ML6732                      | [7889349228](https://linux-hardware.org/?probe=7889349228) | Nov 08, 2022 |
| Dell          | Latitude E5420              | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Linx          | LINX1010B                   | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| ASUSTek       | U36SD                       | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| ASUSTek       | F5V                         | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| HP            | 240 G8                      | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Quanta        | TW8/SW8/DW8                 | [31caaec976](https://linux-hardware.org/?probe=31caaec976) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| Lenovo        | G40-30 80FY                 | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| BANGHO        | W240HU/W250HUQ              | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [30cd9b0d29](https://linux-hardware.org/?probe=30cd9b0d29) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| Microtech     | CoreBook                    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| Dell          | Latitude E6540              | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [7c6ddf22b5](https://linux-hardware.org/?probe=7c6ddf22b5) | Nov 02, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7fb2c2163](https://linux-hardware.org/?probe=a7fb2c2163) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| HP            | Pavilion 15                 | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| GPU Compan... | GWTN156-2BK                 | [99ab599fbc](https://linux-hardware.org/?probe=99ab599fbc) | Nov 01, 2022 |
| Dell          | Latitude E6500              | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| Dell          | Latitude E6500              | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| HP            | 2000                        | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Packard Be... | EasyNote TE69KB             | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [d8f6faad10](https://linux-hardware.org/?probe=d8f6faad10) | Oct 30, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [75dcd27c77](https://linux-hardware.org/?probe=75dcd27c77) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6c3a410233](https://linux-hardware.org/?probe=6c3a410233) | Oct 30, 2022 |
| Dell          | Inspiron 5537               | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| Dell          | Inspiron N5050              | [f844544154](https://linux-hardware.org/?probe=f844544154) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| Dell          | Latitude E6530              | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| HP            | Presario V6000 (RV053UA#... | [ca121e3727](https://linux-hardware.org/?probe=ca121e3727) | Oct 28, 2022 |
| HP            | OMEN Notebook PC 15         | [fea0167027](https://linux-hardware.org/?probe=fea0167027) | Oct 28, 2022 |
| Packard Be... | EasyNote MH45               | [b9aa4cc6d5](https://linux-hardware.org/?probe=b9aa4cc6d5) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| Acer          | Aspire 5720Z                | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [58e18764cb](https://linux-hardware.org/?probe=58e18764cb) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [06274bdff6](https://linux-hardware.org/?probe=06274bdff6) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Dell          | Inspiron 1525               | [742bf13a9f](https://linux-hardware.org/?probe=742bf13a9f) | Oct 25, 2022 |
| MSI           | GT70 2PE                    | [26d9f8ba04](https://linux-hardware.org/?probe=26d9f8ba04) | Oct 25, 2022 |
| Toshiba       | K201                        | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| MSI           | GE62 7RE                    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| Lenovo        | ThinkPad T520 4243PN7       | [fdca71510b](https://linux-hardware.org/?probe=fdca71510b) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| Apple         | MacBookPro8,2               | [200f2ac48e](https://linux-hardware.org/?probe=200f2ac48e) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Alienware     | 18                          | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| Chuwi         | HeroBook Air                | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| AMI           | Unknown                     | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| ASUSTek       | X510UQ                      | [6d976f6f96](https://linux-hardware.org/?probe=6d976f6f96) | Oct 23, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [a8a9cdfabc](https://linux-hardware.org/?probe=a8a9cdfabc) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [d82378ea41](https://linux-hardware.org/?probe=d82378ea41) | Oct 22, 2022 |
| Acer          | Aspire E5-411               | [f4fa3fce70](https://linux-hardware.org/?probe=f4fa3fce70) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| Dell          | Studio 1558                 | [ac449d0411](https://linux-hardware.org/?probe=ac449d0411) | Oct 21, 2022 |
| HP            | Stream Notebook             | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Acer          | Predator PH517-61           | [e30217884a](https://linux-hardware.org/?probe=e30217884a) | Oct 21, 2022 |
| Dell          | Vostro V13                  | [c7cd7a2ddf](https://linux-hardware.org/?probe=c7cd7a2ddf) | Oct 21, 2022 |
| Dell          | Vostro V13                  | [43eb559763](https://linux-hardware.org/?probe=43eb559763) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire A315-33              | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| HP            | G62                         | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| Dell          | Studio 1458                 | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| Dell          | Vostro 3500                 | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| HP            | Notebook                    | [01692e8f30](https://linux-hardware.org/?probe=01692e8f30) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| Acer          | Aspire E5-411               | [01979e17ce](https://linux-hardware.org/?probe=01979e17ce) | Oct 17, 2022 |
| HP            | Laptop 15-db0xxx            | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [f188526e04](https://linux-hardware.org/?probe=f188526e04) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Toshiba       | Satellite C55-A             | [f93fb31ad5](https://linux-hardware.org/?probe=f93fb31ad5) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| Google        | Lars                        | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HUAWEI        | KLVD-WXX9                   | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [772645390a](https://linux-hardware.org/?probe=772645390a) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [7e770fd62b](https://linux-hardware.org/?probe=7e770fd62b) | Oct 14, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Chuwi         | HeroBook Pro                | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| Dell          | Latitude E6330              | [815d48ffba](https://linux-hardware.org/?probe=815d48ffba) | Oct 12, 2022 |
| Dell          | Latitude E6410              | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| TERRA         | TERRAPC                     | [048f3ad5ef](https://linux-hardware.org/?probe=048f3ad5ef) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| Acer          | Aspire A315-33              | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Lenovo        | G500 20236                  | [897321f579](https://linux-hardware.org/?probe=897321f579) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Dell          | Inspiron 3521               | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Dell          | Latitude E6410              | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| AXDIA Inte... | WINBOOK 13                  | [35638411ee](https://linux-hardware.org/?probe=35638411ee) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| Dell          | Inspiron 1200               | [45c46e1b91](https://linux-hardware.org/?probe=45c46e1b91) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | [29c7a43356](https://linux-hardware.org/?probe=29c7a43356) | Oct 06, 2022 |
| Dell          | Vostro 2520                 | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| Dell          | Latitude E6500              | [84fa5b35ed](https://linux-hardware.org/?probe=84fa5b35ed) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| HP            | EliteBook 840 G6            | [397e5be75c](https://linux-hardware.org/?probe=397e5be75c) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| HP            | ENVY m6                     | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| Google        | Careena                     | [7ac4802a10](https://linux-hardware.org/?probe=7ac4802a10) | Oct 04, 2022 |
| Acer          | Extensa 2530                | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d3bcd51be1](https://linux-hardware.org/?probe=d3bcd51be1) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| Lenovo        | V570 1066EDG                | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |
| Acer          | Aspire 4733Z                | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Apple         | MacBookPro8,1               | [f42501fcc3](https://linux-hardware.org/?probe=f42501fcc3) | Oct 01, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Notebook      | NJ50GU                      | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Irbis         | NB61 WS001                  | [3fda78e356](https://linux-hardware.org/?probe=3fda78e356) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| Dell          | Inspiron 1200               | [32dd972d77](https://linux-hardware.org/?probe=32dd972d77) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | [01ebd7e70b](https://linux-hardware.org/?probe=01ebd7e70b) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | [d2c06711d7](https://linux-hardware.org/?probe=d2c06711d7) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Dell          | Inspiron 3582               | [8cd21b783a](https://linux-hardware.org/?probe=8cd21b783a) | Sep 28, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| Dell          | Inspiron 5559               | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Dell          | Latitude E6520              | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Toshiba       | Satellite L855              | [19e5b180eb](https://linux-hardware.org/?probe=19e5b180eb) | Sep 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f501591d1b](https://linux-hardware.org/?probe=f501591d1b) | Sep 27, 2022 |
| Dell          | System Inspiron N7110       | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [c45069d56d](https://linux-hardware.org/?probe=c45069d56d) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [3441e0cac3](https://linux-hardware.org/?probe=3441e0cac3) | Sep 26, 2022 |
| ASUSTek       | X201EP                      | [4e6c202d5d](https://linux-hardware.org/?probe=4e6c202d5d) | Sep 26, 2022 |
| Unknown       | NB-7000                     | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [28e086b848](https://linux-hardware.org/?probe=28e086b848) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [6a8d9c1d7a](https://linux-hardware.org/?probe=6a8d9c1d7a) | Sep 25, 2022 |
| Dell          | Inspiron 14-3452            | [bb90844ff6](https://linux-hardware.org/?probe=bb90844ff6) | Sep 25, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [d8a451b3e6](https://linux-hardware.org/?probe=d8a451b3e6) | Sep 25, 2022 |
| Dell          | Inspiron 3185               | [561c02f958](https://linux-hardware.org/?probe=561c02f958) | Sep 25, 2022 |
| Acer          | Aspire SW5-012              | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| Acer          | Extensa 5635ZG              | [ade183eadc](https://linux-hardware.org/?probe=ade183eadc) | Sep 24, 2022 |
| HP            | 250 G8 Notebook PC          | [fab0eac5a6](https://linux-hardware.org/?probe=fab0eac5a6) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| HP            | EliteBook 840 G6            | [9ccc1b86a7](https://linux-hardware.org/?probe=9ccc1b86a7) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | [00e679e86c](https://linux-hardware.org/?probe=00e679e86c) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | [318436c7ab](https://linux-hardware.org/?probe=318436c7ab) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| Toshiba       | Satellite L855              | [4421e54d32](https://linux-hardware.org/?probe=4421e54d32) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| Alienware     | 18                          | [91d0153265](https://linux-hardware.org/?probe=91d0153265) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Dell          | G15 5515                    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| HP            | Pavilion g7                 | [d51d3d282a](https://linux-hardware.org/?probe=d51d3d282a) | Sep 20, 2022 |
| Dell          | Latitude D610               | [47e0f0fa27](https://linux-hardware.org/?probe=47e0f0fa27) | Sep 19, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| Lenovo        | ThinkPad 11e 20DAS09U00     | [81bd748796](https://linux-hardware.org/?probe=81bd748796) | Sep 19, 2022 |
| Dell          | Latitude E6540              | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| Alienware     | 18                          | [fda9eabd7e](https://linux-hardware.org/?probe=fda9eabd7e) | Sep 18, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [bceb6698c2](https://linux-hardware.org/?probe=bceb6698c2) | Sep 18, 2022 |
| Microtech     | CoreBook                    | [6b1a53d2c2](https://linux-hardware.org/?probe=6b1a53d2c2) | Sep 18, 2022 |
| Ematic        | EWT118                      | [41670ebd30](https://linux-hardware.org/?probe=41670ebd30) | Sep 18, 2022 |
| Dell          | Latitude D610               | [df13ed7396](https://linux-hardware.org/?probe=df13ed7396) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude E6510              | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [e7bb3017fb](https://linux-hardware.org/?probe=e7bb3017fb) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c81727b775](https://linux-hardware.org/?probe=c81727b775) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [5620510083](https://linux-hardware.org/?probe=5620510083) | Sep 16, 2022 |
| Dell          | Latitude E4300              | [b3c04d8a81](https://linux-hardware.org/?probe=b3c04d8a81) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [258c624b3b](https://linux-hardware.org/?probe=258c624b3b) | Sep 15, 2022 |
| Dell          | Latitude D630               | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| Toshiba       | Satellite C855              | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| HP            | EliteBook 820 G2            | [199f191441](https://linux-hardware.org/?probe=199f191441) | Sep 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| HP            | EliteBook 840 G6            | [3c13816886](https://linux-hardware.org/?probe=3c13816886) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | 600B4B/600B5B               | [25c2b764a6](https://linux-hardware.org/?probe=25c2b764a6) | Sep 12, 2022 |
| Dell          | Latitude E7240              | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Gigabyte      | P64V7                       | [b9d2c998be](https://linux-hardware.org/?probe=b9d2c998be) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| HP            | Pavilion dv6000 (RP986EA... | [f20de20683](https://linux-hardware.org/?probe=f20de20683) | Sep 11, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| HP            | Pavilion dv6700             | [4e96c157b7](https://linux-hardware.org/?probe=4e96c157b7) | Sep 10, 2022 |
| AZW           | Z83-V                       | [70e8dba2ef](https://linux-hardware.org/?probe=70e8dba2ef) | Sep 10, 2022 |
| AZW           | Z83-V                       | [622725ab19](https://linux-hardware.org/?probe=622725ab19) | Sep 10, 2022 |
| Acer          | Aspire 7745G                | [a41158c2cc](https://linux-hardware.org/?probe=a41158c2cc) | Sep 10, 2022 |
| Toshiba       | Satellite P200              | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [e11963681c](https://linux-hardware.org/?probe=e11963681c) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| HP            | Laptop 17-bs0xx             | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| Dell          | Latitude E5420              | [b80d26540d](https://linux-hardware.org/?probe=b80d26540d) | Sep 08, 2022 |
| ASUSTek       | UX331UA                     | [e1e0acfdf3](https://linux-hardware.org/?probe=e1e0acfdf3) | Sep 08, 2022 |
| Dell          | Latitude E4300              | [5d3a9edf5d](https://linux-hardware.org/?probe=5d3a9edf5d) | Sep 07, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [70b198055e](https://linux-hardware.org/?probe=70b198055e) | Sep 07, 2022 |
| HP            | 15                          | [c02361a2ff](https://linux-hardware.org/?probe=c02361a2ff) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| HP            | Pavilion g7                 | [5ed29a7629](https://linux-hardware.org/?probe=5ed29a7629) | Sep 05, 2022 |
| Apple         | MacBook5,1                  | [88c4e0664a](https://linux-hardware.org/?probe=88c4e0664a) | Sep 05, 2022 |
| HP            | G62                         | [a3f84f3bf8](https://linux-hardware.org/?probe=a3f84f3bf8) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | [eec792ef79](https://linux-hardware.org/?probe=eec792ef79) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | [0751d35153](https://linux-hardware.org/?probe=0751d35153) | Sep 04, 2022 |
| Apple         | MacBookAir7,2               | [079d33f9b2](https://linux-hardware.org/?probe=079d33f9b2) | Sep 03, 2022 |
| HP            | 620                         | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| Itautec       | Infoway                     | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| Apple         | MacBookPro8,2               | [c74752a0d2](https://linux-hardware.org/?probe=c74752a0d2) | Sep 02, 2022 |
| Positivo      | C14CR01                     | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Dell          | Inspiron 15-3552            | [2eb780855d](https://linux-hardware.org/?probe=2eb780855d) | Sep 01, 2022 |
| Intel         | powered classmate PC        | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| Dell          | Inspiron 15-3552            | [8e2cd928f3](https://linux-hardware.org/?probe=8e2cd928f3) | Aug 31, 2022 |
| HP            | Laptop 15-dy1xxx            | [836644c18b](https://linux-hardware.org/?probe=836644c18b) | Aug 31, 2022 |
| HP            | ProBook 6470b               | [2cbe458c94](https://linux-hardware.org/?probe=2cbe458c94) | Aug 30, 2022 |
| Apple         | MacBookAir7,2               | [a96a893eac](https://linux-hardware.org/?probe=a96a893eac) | Aug 30, 2022 |
| Acer          | Aspire SW5-271              | [3446f93f1d](https://linux-hardware.org/?probe=3446f93f1d) | Aug 29, 2022 |
| Samsung       | 300E5M/300E5L               | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Dell          | XPS 15 9510                 | [45bba02b35](https://linux-hardware.org/?probe=45bba02b35) | Aug 29, 2022 |
| Dell          | Latitude E5440              | [b0d92d186f](https://linux-hardware.org/?probe=b0d92d186f) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [be59676867](https://linux-hardware.org/?probe=be59676867) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [04aec7a28a](https://linux-hardware.org/?probe=04aec7a28a) | Aug 28, 2022 |
| Google        | Butterfly                   | [df8fafaf3b](https://linux-hardware.org/?probe=df8fafaf3b) | Aug 28, 2022 |
| HUAWEI        | KLVD-WXX9                   | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [5b80fb349f](https://linux-hardware.org/?probe=5b80fb349f) | Aug 26, 2022 |
| Apple         | MacBook5,1                  | [7c9f388153](https://linux-hardware.org/?probe=7c9f388153) | Aug 26, 2022 |
| Dell          | XPS 15 9570                 | [c6fc39489e](https://linux-hardware.org/?probe=c6fc39489e) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Framework     | Laptop                      | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| HP            | Pavilion Notebook           | [5d03f69f35](https://linux-hardware.org/?probe=5d03f69f35) | Aug 25, 2022 |
| Dell          | Latitude E7240              | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Framework     | Laptop                      | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| Toshiba       | Satellite L855              | [73de62c6c7](https://linux-hardware.org/?probe=73de62c6c7) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [01416789ab](https://linux-hardware.org/?probe=01416789ab) | Aug 21, 2022 |
| Alienware     | 15 R3                       | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| HP            | 250 G7 Notebook PC          | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| Positivo      | C14CU51                     | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| ASUSTek       | X542BA                      | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| Apple         | MacBookPro5,5               | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| GPU Compan... | GWTN156-11                  | [c22aa4377d](https://linux-hardware.org/?probe=c22aa4377d) | Aug 19, 2022 |
| Dell          | Inspiron N5010              | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| HP            | 14                          | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| ASUSTek       | X756UQ                      | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| Dell          | Latitude E6420              | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| ASUSTek       | K54C                        | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| HP            | Pavilion dv9700             | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| Lenovo        | G505s 20255                 | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Packard Be... | EasyNote TE69KB             | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| Lenovo        | IdeaPad Z580                | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2257302110](https://linux-hardware.org/?probe=2257302110) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| HP            | EliteBook 6930p             | [7267931d03](https://linux-hardware.org/?probe=7267931d03) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Zorin 16 | 1544      | 58.13%  |
| Zorin 15 | 998       | 37.58%  |
| Zorin 12 | 114       | 4.29%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Zorin | 2646      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 117       | 3.91%   |
| 5.11.0-38-generic | 100       | 3.34%   |
| 5.11.0-27-generic | 92        | 3.07%   |
| 5.15.0-52-generic | 89        | 2.97%   |
| 5.15.0-58-generic | 88        | 2.94%   |
| 5.15.0-46-generic | 88        | 2.94%   |
| 5.13.0-30-generic | 74        | 2.47%   |
| 5.3.0-40-generic  | 67        | 2.24%   |
| 5.11.0-37-generic | 67        | 2.24%   |
| 5.11.0-40-generic | 65        | 2.17%   |
| 5.11.0-41-generic | 62        | 2.07%   |
| 5.4.0-42-generic  | 61        | 2.04%   |
| 5.13.0-39-generic | 60        | 2%      |
| 5.11.0-34-generic | 57        | 1.9%    |
| 5.15.0-67-generic | 56        | 1.87%   |
| 5.11.0-43-generic | 56        | 1.87%   |
| 5.15.0-60-generic | 54        | 1.8%    |
| 5.3.0-46-generic  | 53        | 1.77%   |
| 5.15.0-48-generic | 51        | 1.7%    |
| 5.13.0-44-generic | 48        | 1.6%    |
| 5.3.0-51-generic  | 47        | 1.57%   |
| 5.0.0-37-generic  | 47        | 1.57%   |
| 5.13.0-40-generic | 45        | 1.5%    |
| 5.15.0-53-generic | 42        | 1.4%    |
| 5.13.0-35-generic | 40        | 1.34%   |
| 5.4.0-47-generic  | 38        | 1.27%   |
| 5.3.0-53-generic  | 37        | 1.24%   |
| 5.13.0-28-generic | 37        | 1.24%   |
| 5.3.0-42-generic  | 36        | 1.2%    |
| 5.4.0-45-generic  | 34        | 1.14%   |
| 5.15.0-41-generic | 34        | 1.14%   |
| 5.4.0-58-generic  | 31        | 1.04%   |
| 5.4.0-48-generic  | 31        | 1.04%   |
| 5.13.0-52-generic | 31        | 1.04%   |
| 5.4.0-65-generic  | 28        | 0.94%   |
| 5.13.0-27-generic | 28        | 0.94%   |
| 5.4.0-80-generic  | 26        | 0.87%   |
| 5.11.0-46-generic | 26        | 0.87%   |
| 5.13.0-41-generic | 25        | 0.84%   |
| 5.4.0-72-generic  | 23        | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 616       | 22.29%  |
| 5.4.0   | 575       | 20.81%  |
| 5.11.0  | 547       | 19.8%   |
| 5.13.0  | 406       | 14.69%  |
| 5.3.0   | 312       | 11.29%  |
| 4.15.0  | 110       | 3.98%   |
| 5.0.0   | 89        | 3.22%   |
| 4.18.0  | 45        | 1.63%   |
| 5.8.0   | 23        | 0.83%   |
| 5.14.0  | 8         | 0.29%   |
| 4.4.0   | 4         | 0.14%   |
| 5.6.0   | 2         | 0.07%   |
| 5.18.15 | 2         | 0.07%   |
| 5.16.0  | 2         | 0.07%   |
| 5.10.0  | 2         | 0.07%   |
| 6.0.19  | 1         | 0.04%   |
| 6.0.0   | 1         | 0.04%   |
| 5.9.12  | 1         | 0.04%   |
| 5.9.0   | 1         | 0.04%   |
| 5.7.1   | 1         | 0.04%   |
| 5.4.180 | 1         | 0.04%   |
| 5.4.1   | 1         | 0.04%   |
| 5.19.9  | 1         | 0.04%   |
| 5.19.14 | 1         | 0.04%   |
| 5.19.12 | 1         | 0.04%   |
| 5.19.1  | 1         | 0.04%   |
| 5.19.0  | 1         | 0.04%   |
| 5.18.6  | 1         | 0.04%   |
| 5.16.12 | 1         | 0.04%   |
| 5.15.49 | 1         | 0.04%   |
| 5.15.24 | 1         | 0.04%   |
| 5.13.18 | 1         | 0.04%   |
| 5.10.35 | 1         | 0.04%   |
| 5.10.16 | 1         | 0.04%   |
| 4.13.0  | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 618       | 22.37%  |
| 5.4     | 577       | 20.88%  |
| 5.11    | 547       | 19.8%   |
| 5.13    | 407       | 14.73%  |
| 5.3     | 312       | 11.29%  |
| 4.15    | 110       | 3.98%   |
| 5.0     | 89        | 3.22%   |
| 4.18    | 45        | 1.63%   |
| 5.8     | 23        | 0.83%   |
| 5.14    | 8         | 0.29%   |
| 5.19    | 5         | 0.18%   |
| 5.10    | 4         | 0.14%   |
| 4.4     | 4         | 0.14%   |
| 5.18    | 3         | 0.11%   |
| 5.16    | 3         | 0.11%   |
| 6.0     | 2         | 0.07%   |
| 5.9     | 2         | 0.07%   |
| 5.6     | 2         | 0.07%   |
| 5.7     | 1         | 0.04%   |
| 4.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2376      | 89.69%  |
| i686   | 273       | 10.31%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 1857      | 69.45%  |
| XFCE       | 629       | 23.52%  |
| Unknown    | 169       | 6.32%   |
| X-Cinnamon | 7         | 0.26%   |
| KDE        | 3         | 0.11%   |
| Unity      | 2         | 0.07%   |
| KDE5       | 2         | 0.07%   |
| Budgie     | 2         | 0.07%   |
| LXDE       | 1         | 0.04%   |
| i3         | 1         | 0.04%   |
| Cinnamon   | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2518      | 94.34%  |
| Unknown | 106       | 3.97%   |
| Wayland | 45        | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2132      | 79.46%  |
| GDM3    | 198       | 7.38%   |
| GDM     | 189       | 7.04%   |
| LightDM | 155       | 5.78%   |
| TDM     | 6         | 0.22%   |
| SDDM    | 2         | 0.07%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 923       | 34.58%  |
| de_DE   | 195       | 7.31%   |
| pt_BR   | 173       | 6.48%   |
| en_GB   | 156       | 5.84%   |
| Unknown | 126       | 4.72%   |
| it_IT   | 104       | 3.9%    |
| en_IN   | 87        | 3.26%   |
| fr_FR   | 81        | 3.03%   |
| es_ES   | 80        | 3%      |
| en_CA   | 80        | 3%      |
| pl_PL   | 63        | 2.36%   |
| en_AU   | 42        | 1.57%   |
| pt_PT   | 40        | 1.5%    |
| es_MX   | 36        | 1.35%   |
| ru_RU   | 34        | 1.27%   |
| nl_NL   | 34        | 1.27%   |
| cs_CZ   | 31        | 1.16%   |
| en_ZA   | 26        | 0.97%   |
| es_AR   | 25        | 0.94%   |
| tr_TR   | 23        | 0.86%   |
| C       | 20        | 0.75%   |
| sv_SE   | 18        | 0.67%   |
| es_CL   | 18        | 0.67%   |
| en_NZ   | 17        | 0.64%   |
| de_AT   | 17        | 0.64%   |
| ja_JP   | 13        | 0.49%   |
| hu_HU   | 13        | 0.49%   |
| de_CH   | 13        | 0.49%   |
| fr_BE   | 12        | 0.45%   |
| fr_CA   | 11        | 0.41%   |
| el_GR   | 11        | 0.41%   |
| nl_BE   | 10        | 0.37%   |
| es_CO   | 9         | 0.34%   |
| en_PH   | 8         | 0.3%    |
| da_DK   | 8         | 0.3%    |
| ru_UA   | 7         | 0.26%   |
| ro_RO   | 7         | 0.26%   |
| es_PE   | 7         | 0.26%   |
| bg_BG   | 6         | 0.22%   |
| hr_HR   | 5         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1417      | 52.93%  |
| EFI  | 1260      | 47.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2503      | 94.27%  |
| Overlay | 58        | 2.18%   |
| Zfs     | 28        | 1.05%   |
| Btrfs   | 22        | 0.83%   |
| Ext2    | 21        | 0.79%   |
| Unknown | 17        | 0.64%   |
| Xfs     | 3         | 0.11%   |
| Ext3    | 3         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2350      | 87.92%  |
| GPT     | 244       | 9.13%   |
| MBR     | 79        | 2.96%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2526      | 94.86%  |
| Yes       | 137       | 5.14%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2226      | 83.62%  |
| Yes       | 436       | 16.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 602       | 22.75%  |
| Dell                | 406       | 15.34%  |
| Lenovo              | 403       | 15.23%  |
| ASUSTek Computer    | 270       | 10.2%   |
| Acer                | 213       | 8.05%   |
| Toshiba             | 149       | 5.63%   |
| Apple               | 62        | 2.34%   |
| Samsung Electronics | 54        | 2.04%   |
| Sony                | 47        | 1.78%   |
| MSI                 | 41        | 1.55%   |
| Packard Bell        | 28        | 1.06%   |
| Unknown             | 26        | 0.98%   |
| Google              | 23        | 0.87%   |
| Positivo            | 19        | 0.72%   |
| HUAWEI              | 18        | 0.68%   |
| Fujitsu Siemens     | 17        | 0.64%   |
| Fujitsu             | 17        | 0.64%   |
| Medion              | 13        | 0.49%   |
| Notebook            | 11        | 0.42%   |
| Alienware           | 10        | 0.38%   |
| Panasonic           | 9         | 0.34%   |
| Gateway             | 8         | 0.3%    |
| Chuwi               | 8         | 0.3%    |
| Multilaser          | 7         | 0.26%   |
| AMI                 | 7         | 0.26%   |
| Insyde              | 6         | 0.23%   |
| eMachines           | 6         | 0.23%   |
| NEC Computers       | 5         | 0.19%   |
| LG Electronics      | 5         | 0.19%   |
| Itautec             | 5         | 0.19%   |
| GPU Company         | 5         | 0.19%   |
| Ematic              | 5         | 0.19%   |
| Digibras            | 5         | 0.19%   |
| Clevo               | 5         | 0.19%   |
| Thomson             | 4         | 0.15%   |
| Semp Toshiba        | 4         | 0.15%   |
| Razer               | 4         | 0.15%   |
| Quanta              | 4         | 0.15%   |
| Jumper              | 4         | 0.15%   |
| Intel               | 4         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Unknown                 | 53        | 2%      |
| HP Notebook             | 28        | 1.06%   |
| HP Pavilion Notebook    | 16        | 0.6%    |
| HP Pavilion dv6         | 15        | 0.57%   |
| HP 15                   | 12        | 0.45%   |
| HP Pavilion 15          | 11        | 0.42%   |
| Toshiba Satellite C660  | 10        | 0.38%   |
| HP Pavilion dv7         | 10        | 0.38%   |
| Dell Latitude D630      | 9         | 0.34%   |
| Dell Inspiron 1545      | 9         | 0.34%   |
| HP Pavilion g6          | 8         | 0.3%    |
| HP Laptop 15-bw0xx      | 8         | 0.3%    |
| Dell Latitude E6540     | 8         | 0.3%    |
| Dell Latitude E6400     | 8         | 0.3%    |
| Dell Inspiron 15-3567   | 8         | 0.3%    |
| Apple MacBookPro8,1     | 8         | 0.3%    |
| HP EliteBook 840 G1     | 7         | 0.26%   |
| Dell Latitude E6410     | 7         | 0.26%   |
| Dell Inspiron 3521      | 7         | 0.26%   |
| Dell Inspiron 1525      | 7         | 0.26%   |
| Toshiba Satellite A100  | 6         | 0.23%   |
| HP ProBook 640 G1       | 6         | 0.23%   |
| HP Pavilion g7          | 6         | 0.23%   |
| HP Pavilion dv6700      | 6         | 0.23%   |
| HP Pavilion 17          | 6         | 0.23%   |
| Dell Inspiron 7520      | 6         | 0.23%   |
| HP ProBook 4540s        | 5         | 0.19%   |
| HP ProBook 4530s        | 5         | 0.19%   |
| HP Pavilion dv5         | 5         | 0.19%   |
| HP Laptop 15-db0xxx     | 5         | 0.19%   |
| HP EliteBook 8460p      | 5         | 0.19%   |
| HP Compaq Presario CQ60 | 5         | 0.19%   |
| HP Compaq 6730s         | 5         | 0.19%   |
| HP 14                   | 5         | 0.19%   |
| Dell Latitude E6430     | 5         | 0.19%   |
| Dell Latitude E6420     | 5         | 0.19%   |
| Dell Latitude E5500     | 5         | 0.19%   |
| Dell Latitude E5440     | 5         | 0.19%   |
| Dell Inspiron N5010     | 5         | 0.19%   |
| Dell Inspiron 3542      | 5         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 164       | 6.2%    |
| Dell Inspiron         | 158       | 5.97%   |
| HP Pavilion           | 156       | 5.9%    |
| Dell Latitude         | 150       | 5.67%   |
| Acer Aspire           | 147       | 5.56%   |
| Lenovo IdeaPad        | 128       | 4.84%   |
| Toshiba Satellite     | 126       | 4.76%   |
| HP EliteBook          | 72        | 2.72%   |
| HP ProBook            | 66        | 2.49%   |
| HP Laptop             | 53        | 2%      |
| Unknown               | 53        | 2%      |
| HP Compaq             | 49        | 1.85%   |
| ASUS VivoBook         | 36        | 1.36%   |
| Dell Vostro           | 29        | 1.1%    |
| HP Notebook           | 28        | 1.06%   |
| Packard Bell EasyNote | 26        | 0.98%   |
| HP ENVY               | 22        | 0.83%   |
| Dell XPS              | 19        | 0.72%   |
| HP Stream             | 18        | 0.68%   |
| Dell Precision        | 16        | 0.6%    |
| ASUS ZenBook          | 15        | 0.57%   |
| HP Presario           | 14        | 0.53%   |
| HP 15                 | 14        | 0.53%   |
| ASUS ROG              | 14        | 0.53%   |
| HP 255                | 13        | 0.49%   |
| Dell Studio           | 12        | 0.45%   |
| Lenovo Yoga           | 11        | 0.42%   |
| HP OMEN               | 11        | 0.42%   |
| Fujitsu LIFEBOOK      | 11        | 0.42%   |
| Apple MacBookPro8     | 11        | 0.42%   |
| Acer TravelMate       | 11        | 0.42%   |
| HP ZBook              | 10        | 0.38%   |
| Dell System           | 10        | 0.38%   |
| Toshiba PORTEGE       | 9         | 0.34%   |
| Fujitsu Siemens AMILO | 9         | 0.34%   |
| ASUS ASUS             | 9         | 0.34%   |
| HP Mini               | 8         | 0.3%    |
| Apple MacBookPro11    | 8         | 0.3%    |
| Acer Swift            | 8         | 0.3%    |
| ASUS TUF              | 7         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 250       | 9.45%   |
| 2012    | 228       | 8.62%   |
| 2013    | 223       | 8.43%   |
| 2010    | 197       | 7.45%   |
| 2008    | 181       | 6.84%   |
| 2014    | 165       | 6.24%   |
| 2018    | 161       | 6.08%   |
| 2019    | 159       | 6.01%   |
| 2017    | 146       | 5.52%   |
| 2015    | 142       | 5.37%   |
| 2021    | 141       | 5.33%   |
| 2007    | 138       | 5.22%   |
| 2009    | 131       | 4.95%   |
| 2016    | 130       | 4.91%   |
| 2020    | 124       | 4.69%   |
| 2006    | 53        | 2%      |
| 2005    | 35        | 1.32%   |
| 2022    | 32        | 1.21%   |
| Unknown | 4         | 0.15%   |
| 2023    | 3         | 0.11%   |
| 2003    | 2         | 0.08%   |
| 2004    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2646      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2348      | 88.17%  |
| Enabled  | 315       | 11.83%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2618      | 98.94%  |
| Yes  | 28        | 1.06%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 801       | 30.08%  |
| 4.01-8.0    | 744       | 27.94%  |
| 8.01-16.0   | 325       | 12.2%   |
| 1.01-2.0    | 304       | 11.42%  |
| 16.01-24.0  | 228       | 8.56%   |
| 2.01-3.0    | 105       | 3.94%   |
| 32.01-64.0  | 70        | 2.63%   |
| 0.51-1.0    | 67        | 2.52%   |
| 64.01-256.0 | 10        | 0.38%   |
| 24.01-32.0  | 9         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1252      | 43.82%  |
| 2.01-3.0   | 775       | 27.13%  |
| 3.01-4.0   | 313       | 10.96%  |
| 0.51-1.0   | 261       | 9.14%   |
| 4.01-8.0   | 202       | 7.07%   |
| 8.01-16.0  | 26        | 0.91%   |
| 0.01-0.5   | 25        | 0.88%   |
| 24.01-32.0 | 2         | 0.07%   |
| 16.01-24.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2059      | 76.6%   |
| 2      | 552       | 20.54%  |
| 3      | 54        | 2.01%   |
| 0      | 11        | 0.41%   |
| 4      | 8         | 0.3%    |
| 5      | 2         | 0.07%   |
| 8      | 1         | 0.04%   |
| 6      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1331      | 50.06%  |
| No        | 1328      | 49.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2189      | 82.54%  |
| No        | 463       | 17.46%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2559      | 96.64%  |
| No        | 89        | 3.36%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1708      | 63.9%   |
| No        | 965       | 36.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 542       | 20.4%   |
| Germany      | 229       | 8.62%   |
| Brazil       | 200       | 7.53%   |
| UK           | 154       | 5.8%    |
| Italy        | 110       | 4.14%   |
| Canada       | 103       | 3.88%   |
| India        | 94        | 3.54%   |
| Spain        | 87        | 3.27%   |
| France       | 79        | 2.97%   |
| Poland       | 63        | 2.37%   |
| Netherlands  | 61        | 2.3%    |
| Mexico       | 57        | 2.15%   |
| Australia    | 48        | 1.81%   |
| Portugal     | 46        | 1.73%   |
| Czechia      | 36        | 1.35%   |
| Russia       | 34        | 1.28%   |
| Argentina    | 34        | 1.28%   |
| Sweden       | 33        | 1.24%   |
| South Africa | 33        | 1.24%   |
| Belgium      | 33        | 1.24%   |
| Austria      | 31        | 1.17%   |
| Turkey       | 28        | 1.05%   |
| Romania      | 28        | 1.05%   |
| Switzerland  | 27        | 1.02%   |
| Indonesia    | 25        | 0.94%   |
| Greece       | 23        | 0.87%   |
| New Zealand  | 20        | 0.75%   |
| Japan        | 18        | 0.68%   |
| Chile        | 18        | 0.68%   |
| Norway       | 16        | 0.6%    |
| Hungary      | 16        | 0.6%    |
| Serbia       | 15        | 0.56%   |
| Egypt        | 15        | 0.56%   |
| Colombia     | 15        | 0.56%   |
| Bulgaria     | 14        | 0.53%   |
| Ukraine      | 12        | 0.45%   |
| Philippines  | 11        | 0.41%   |
| Kenya        | 10        | 0.38%   |
| Denmark      | 10        | 0.38%   |
| Israel       | 9         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 21        | 0.76%   |
| Sydney         | 19        | 0.69%   |
| Berlin         | 19        | 0.69%   |
| Vienna         | 17        | 0.61%   |
| Madrid         | 16        | 0.58%   |
| Rome           | 14        | 0.51%   |
| Munich         | 14        | 0.51%   |
| Athens         | 14        | 0.51%   |
| Montreal       | 13        | 0.47%   |
| Rio de Janeiro | 12        | 0.43%   |
| Milan          | 12        | 0.43%   |
| Johannesburg   | 12        | 0.43%   |
| Istanbul       | 12        | 0.43%   |
| Hamburg        | 12        | 0.43%   |
| Auckland       | 12        | 0.43%   |
| Prague         | 11        | 0.4%    |
| New York       | 11        | 0.4%    |
| Cairo          | 11        | 0.4%    |
| Paris          | 10        | 0.36%   |
| Mexico City    | 10        | 0.36%   |
| Jakarta        | 10        | 0.36%   |
| Bengaluru      | 10        | 0.36%   |
| Toronto        | 9         | 0.33%   |
| Stockholm      | 9         | 0.33%   |
| Seattle        | 9         | 0.33%   |
| Nairobi        | 9         | 0.33%   |
| Moscow         | 9         | 0.33%   |
| Kolkata        | 9         | 0.33%   |
| Dallas         | 9         | 0.33%   |
| Belgrade       | 9         | 0.33%   |
| Amsterdam      | 9         | 0.33%   |
| Warsaw         | 8         | 0.29%   |
| Krakow         | 8         | 0.29%   |
| Glasgow        | 8         | 0.29%   |
| Buenos Aires   | 8         | 0.29%   |
| Barcelona      | 8         | 0.29%   |
| Tel Aviv       | 7         | 0.25%   |
| Stuttgart      | 7         | 0.25%   |
| Perth          | 7         | 0.25%   |
| Melbourne      | 7         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 416       | 502    | 13.52%  |
| WDC                       | 386       | 460    | 12.55%  |
| Samsung Electronics       | 338       | 461    | 10.99%  |
| Toshiba                   | 328       | 373    | 10.66%  |
| Unknown                   | 263       | 363    | 8.55%   |
| SanDisk                   | 170       | 197    | 5.53%   |
| Hitachi                   | 160       | 187    | 5.2%    |
| Kingston                  | 136       | 161    | 4.42%   |
| Crucial                   | 107       | 127    | 3.48%   |
| HGST                      | 90        | 108    | 2.93%   |
| Intel                     | 76        | 95     | 2.47%   |
| SK hynix                  | 58        | 69     | 1.89%   |
| Micron Technology         | 46        | 56     | 1.5%    |
| Fujitsu                   | 40        | 42     | 1.3%    |
| A-DATA Technology         | 39        | 42     | 1.27%   |
| China                     | 31        | 37     | 1.01%   |
| Intenso                   | 22        | 23     | 0.72%   |
| Apple                     | 22        | 23     | 0.72%   |
| PNY                       | 21        | 24     | 0.68%   |
| KIOXIA                    | 18        | 20     | 0.59%   |
| SPCC                      | 16        | 18     | 0.52%   |
| LITEONIT                  | 15        | 18     | 0.49%   |
| LITEON                    | 15        | 19     | 0.49%   |
| Transcend                 | 14        | 19     | 0.46%   |
| Patriot                   | 13        | 16     | 0.42%   |
| Netac                     | 13        | 13     | 0.42%   |
| Unknown                   | 13        | 15     | 0.42%   |
| Phison                    | 12        | 14     | 0.39%   |
| GOODRAM                   | 12        | 13     | 0.39%   |
| Team                      | 10        | 11     | 0.33%   |
| JMicron Technology        | 10        | 11     | 0.33%   |
| OCZ                       | 9         | 10     | 0.29%   |
| SABRENT                   | 8         | 9      | 0.26%   |
| ASMT                      | 6         | 6      | 0.2%    |
| Silicon Motion            | 5         | 5      | 0.16%   |
| Lite-On                   | 5         | 7      | 0.16%   |
| Hewlett-Packard           | 5         | 5      | 0.16%   |
| Plextor                   | 4         | 4      | 0.13%   |
| Phison Electronics        | 4         | 4      | 0.13%   |
| Micron/Crucial Technology | 4         | 4      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 98        | 3.06%   |
| Unknown MMC Card  64GB                 | 65        | 2.03%   |
| Toshiba MQ01ABF050 500GB               | 47        | 1.47%   |
| Seagate ST1000LM035-1RK172 1TB         | 43        | 1.34%   |
| Toshiba MQ01ABD100 1TB                 | 34        | 1.06%   |
| Seagate ST500LT012-1DG142 500GB        | 34        | 1.06%   |
| Kingston SA400S37240G 240GB SSD        | 32        | 1%      |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 31        | 0.97%   |
| Toshiba MQ04ABF100 1TB                 | 30        | 0.94%   |
| Unknown MMC Card  16GB                 | 26        | 0.81%   |
| Unknown MMC Card  128GB                | 26        | 0.81%   |
| Seagate ST9500325AS 500GB              | 24        | 0.75%   |
| Samsung NVMe SSD Drive 512GB           | 24        | 0.75%   |
| Kingston SA400S37480G 480GB SSD        | 23        | 0.72%   |
| Crucial CT240BX500SSD1 240GB           | 21        | 0.66%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 20        | 0.63%   |
| SanDisk NVMe SSD Drive 256GB           | 20        | 0.63%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 19        | 0.59%   |
| Kingston SA400S37120G 120GB SSD        | 19        | 0.59%   |
| Intel NVMe SSD Drive 512GB             | 17        | 0.53%   |
| HGST HTS725050A7E630 500GB             | 17        | 0.53%   |
| HGST HTS541010A9E680 1TB               | 17        | 0.53%   |
| Crucial CT500MX500SSD1 500GB           | 17        | 0.53%   |
| Seagate Expansion+ 2TB                 | 16        | 0.5%    |
| Hitachi HTS545032B9A300 320GB          | 16        | 0.5%    |
| HGST HTS721010A9E630 1TB               | 16        | 0.5%    |
| Samsung SSD 850 EVO 500GB              | 15        | 0.47%   |
| SanDisk NVMe SSD Drive 512GB           | 14        | 0.44%   |
| Samsung SSD 860 EVO 500GB              | 13        | 0.41%   |
| Samsung SSD 860 EVO 250GB              | 13        | 0.41%   |
| Unknown                                | 13        | 0.41%   |
| HGST HTS545050A7E680 500GB             | 12        | 0.38%   |
| Unknown SD/MMC/MS PRO 64GB             | 11        | 0.34%   |
| Kingston SV300S37A120G 120GB SSD       | 11        | 0.34%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 10        | 0.31%   |
| WDC WD10JPVX-22JC3T0 1TB               | 10        | 0.31%   |
| Toshiba MQ01ABD075 752GB               | 10        | 0.31%   |
| Seagate ST9320325AS 320GB              | 10        | 0.31%   |
| Seagate ST500LT012-9WS142 500GB        | 10        | 0.31%   |
| Seagate ST500LM021-1KJ152 500GB        | 10        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 413       | 495    | 29.58%  |
| WDC                 | 332       | 387    | 23.78%  |
| Toshiba             | 282       | 317    | 20.2%   |
| Hitachi             | 160       | 187    | 11.46%  |
| HGST                | 90        | 108    | 6.45%   |
| Samsung Electronics | 40        | 45     | 2.87%   |
| Fujitsu             | 40        | 42     | 2.87%   |
| Unknown             | 11        | 17     | 0.79%   |
| SABRENT             | 8         | 9      | 0.57%   |
| ASMT                | 6         | 6      | 0.43%   |
| IBM/Hitachi         | 4         | 5      | 0.29%   |
| Apple               | 3         | 3      | 0.21%   |
| JMicron Technology  | 2         | 2      | 0.14%   |
| USB3.0              | 1         | 1      | 0.07%   |
| T-CREATE            | 1         | 1      | 0.07%   |
| Pioneer             | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 192       | 261    | 19.49%  |
| Kingston            | 118       | 142    | 11.98%  |
| Crucial             | 105       | 123    | 10.66%  |
| SanDisk             | 100       | 118    | 10.15%  |
| WDC                 | 44        | 55     | 4.47%   |
| A-DATA Technology   | 35        | 38     | 3.55%   |
| Intel               | 34        | 39     | 3.45%   |
| China               | 30        | 36     | 3.05%   |
| Toshiba             | 29        | 33     | 2.94%   |
| SK hynix            | 23        | 27     | 2.34%   |
| Micron Technology   | 22        | 26     | 2.23%   |
| PNY                 | 21        | 24     | 2.13%   |
| Apple               | 17        | 17     | 1.73%   |
| SPCC                | 15        | 17     | 1.52%   |
| LITEONIT            | 15        | 18     | 1.52%   |
| LITEON              | 15        | 19     | 1.52%   |
| Intenso             | 15        | 15     | 1.52%   |
| Transcend           | 14        | 19     | 1.42%   |
| Patriot             | 13        | 16     | 1.32%   |
| Netac               | 13        | 13     | 1.32%   |
| GOODRAM             | 12        | 13     | 1.22%   |
| Team                | 10        | 11     | 1.02%   |
| OCZ                 | 9         | 10     | 0.91%   |
| JMicron Technology  | 6         | 7      | 0.61%   |
| Unknown             | 5         | 7      | 0.51%   |
| Plextor             | 4         | 4      | 0.41%   |
| Hewlett-Packard     | 4         | 4      | 0.41%   |
| Lexar               | 3         | 3      | 0.3%    |
| KingSpec            | 3         | 3      | 0.3%    |
| BHT                 | 3         | 4      | 0.3%    |
| Apacer              | 3         | 3      | 0.3%    |
| Verbatim            | 2         | 2      | 0.2%    |
| Vaseky              | 2         | 3      | 0.2%    |
| TO Exter            | 2         | 3      | 0.2%    |
| Teclast             | 2         | 2      | 0.2%    |
| TCSUNBOW            | 2         | 2      | 0.2%    |
| Mushkin             | 2         | 2      | 0.2%    |
| Leven               | 2         | 2      | 0.2%    |
| KingDian            | 2         | 2      | 0.2%    |
| HS-SSD-E100         | 2         | 2      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1361      | 1628   | 45.55%  |
| SSD     | 940       | 1183   | 31.46%  |
| NVMe    | 378       | 494    | 12.65%  |
| MMC     | 264       | 361    | 8.84%   |
| Unknown | 45        | 49     | 1.51%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2156      | 2735   | 74.76%  |
| NVMe | 378       | 493    | 13.11%  |
| MMC  | 264       | 361    | 9.15%   |
| SAS  | 86        | 126    | 2.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Notebooks | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 1711      | 2105   | 75.14%  |
| 0.51-1.0        | 499       | 614    | 21.91%  |
| 1.01-2.0        | 55        | 74     | 2.42%   |
| 4.01-10.0       | 7         | 10     | 0.31%   |
| 3.01-4.0        | 3         | 6      | 0.13%   |
| More than 100.0 | 1         | 1      | 0.04%   |
| 2.01-3.0        | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 952       | 35.03%  |
| 251-500        | 711       | 26.16%  |
| 501-1000       | 323       | 11.88%  |
| 51-100         | 308       | 11.33%  |
| 21-50          | 187       | 6.88%   |
| 1-20           | 84        | 3.09%   |
| 1001-2000      | 83        | 3.05%   |
| Unknown        | 26        | 0.96%   |
| More than 3000 | 25        | 0.92%   |
| 2001-3000      | 19        | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1447      | 51.4%   |
| 21-50          | 649       | 23.06%  |
| 51-100         | 277       | 9.84%   |
| 101-250        | 235       | 8.35%   |
| 251-500        | 111       | 3.94%   |
| 501-1000       | 43        | 1.53%   |
| Unknown        | 26        | 0.92%   |
| 1001-2000      | 13        | 0.46%   |
| More than 3000 | 11        | 0.39%   |
| 2001-3000      | 3         | 0.11%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 3         | 3      | 5.45%   |
| Toshiba MQ02ABD100H 1TB                             | 2         | 2      | 3.64%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 3.64%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 3.64%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 1      | 1.82%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 1.82%   |
| WDC WD5000BEVT-24A0RT0 500GB                        | 1         | 1      | 1.82%   |
| WDC WD3200BPVT-55ZEST0 320GB                        | 1         | 1      | 1.82%   |
| WDC WD10SPZX-75Z10T2 1TB                            | 1         | 1      | 1.82%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 1.82%   |
| WDC WD10JPVT-55A1YT0 1TB                            | 1         | 1      | 1.82%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 1.82%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 1.82%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 1.82%   |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 1.82%   |
| Toshiba MK2046GSX 200GB                             | 1         | 1      | 1.82%   |
| Teclast 128GB NS550-2242 SSD                        | 1         | 1      | 1.82%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 1.82%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 1.82%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 1.82%   |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 1.82%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 1.82%   |
| Seagate ST9200420ASG 200GB                          | 1         | 1      | 1.82%   |
| Seagate ST9160411ASG 160GB                          | 1         | 1      | 1.82%   |
| Seagate ST9160314AS 160GB                           | 1         | 1      | 1.82%   |
| Seagate ST9120822AS 120GB                           | 1         | 1      | 1.82%   |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 1.82%   |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 1      | 1.82%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 1.82%   |
| Seagate ST1000LM048-2E7172 1TB                      | 1         | 1      | 1.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 1.82%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD    | 1         | 1      | 1.82%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD       | 1         | 1      | 1.82%   |
| Samsung Electronics HM160JI 160GB                   | 1         | 1      | 1.82%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 1.82%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD               | 1         | 1      | 1.82%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 1.82%   |
| Kingston SA400S37120G 120GB SSD                     | 1         | 1      | 1.82%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 1.82%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 1.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 32.73%  |
| Toshiba             | 9         | 9      | 16.36%  |
| WDC                 | 7         | 7      | 12.73%  |
| Hitachi             | 5         | 5      | 9.09%   |
| HGST                | 5         | 5      | 9.09%   |
| Samsung Electronics | 3         | 3      | 5.45%   |
| Kingston            | 3         | 3      | 5.45%   |
| Teclast             | 1         | 1      | 1.82%   |
| SK hynix            | 1         | 1      | 1.82%   |
| Micron Technology   | 1         | 1      | 1.82%   |
| LITEONIT            | 1         | 1      | 1.82%   |
| Hewlett-Packard     | 1         | 1      | 1.82%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 18        | 18     | 40.91%  |
| Toshiba             | 8         | 8      | 18.18%  |
| WDC                 | 7         | 7      | 15.91%  |
| Hitachi             | 5         | 5      | 11.36%  |
| HGST                | 5         | 5      | 11.36%  |
| Samsung Electronics | 1         | 1      | 2.27%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 44        | 44     | 80%     |
| SSD  | 10        | 10     | 18.18%  |
| NVMe | 1         | 1      | 1.82%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2418      | 3406   | 90.12%  |
| Works    | 209       | 252    | 7.79%   |
| Malfunc  | 54        | 55     | 2.01%   |
| Failed   | 2         | 2      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1954      | 70.52%  |
| AMD                              | 346       | 12.49%  |
| Samsung Electronics              | 129       | 4.66%   |
| SanDisk                          | 72        | 2.6%    |
| Nvidia                           | 44        | 1.59%   |
| SK hynix                         | 33        | 1.19%   |
| Silicon Integrated Systems [SiS] | 28        | 1.01%   |
| Micron Technology                | 25        | 0.9%    |
| Kingston Technology Company      | 20        | 0.72%   |
| Toshiba America Info Systems     | 19        | 0.69%   |
| KIOXIA                           | 18        | 0.65%   |
| Phison Electronics               | 15        | 0.54%   |
| VIA Technologies                 | 11        | 0.4%    |
| Micron/Crucial Technology        | 7         | 0.25%   |
| ADATA Technology                 | 7         | 0.25%   |
| Silicon Motion                   | 6         | 0.22%   |
| Marvell Technology Group         | 5         | 0.18%   |
| Lite-On Technology               | 5         | 0.18%   |
| JMicron Technology               | 5         | 0.18%   |
| Union Memory (Shenzhen)          | 4         | 0.14%   |
| Realtek Semiconductor            | 4         | 0.14%   |
| ASMedia Technology               | 4         | 0.14%   |
| Yangtze Memory Technologies      | 2         | 0.07%   |
| Silicon Image                    | 2         | 0.07%   |
| Apple                            | 2         | 0.07%   |
| Solid State Storage Technology   | 1         | 0.04%   |
| Seagate Technology               | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 263       | 8.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 222       | 7.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 184       | 5.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 183       | 5.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 149       | 4.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 143       | 4.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 112       | 3.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 109       | 3.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 93        | 2.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 92        | 2.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 67        | 2.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 65        | 2.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 56        | 1.8%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 52        | 1.67%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 50        | 1.6%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 49        | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 47        | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                              | 43        | 1.38%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 42        | 1.35%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 39        | 1.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 38        | 1.22%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 35        | 1.12%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 35        | 1.12%   |
| Samsung NVMe SSD Controller 980                                                  | 34        | 1.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 29        | 0.93%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 28        | 0.9%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 27        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 27        | 0.87%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 26        | 0.83%   |
| Micron NVMe Storage Controller                                                   | 24        | 0.77%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 22        | 0.71%   |
| Intel Tiger Lake-LP SATA Controller                                              | 21        | 0.67%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 20        | 0.64%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 19        | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 18        | 0.58%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 18        | 0.58%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 17        | 0.55%   |
| Intel Comet Lake SATA AHCI Controller                                            | 17        | 0.55%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 17        | 0.55%   |
| Intel SSD 660P Series                                                            | 16        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1940      | 65.85%  |
| IDE  | 424       | 14.39%  |
| NVMe | 381       | 12.93%  |
| RAID | 201       | 6.82%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2221      | 83.94%  |
| AMD          | 424       | 16.02%  |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 37        | 1.4%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 33        | 1.25%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 1.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 29        | 1.1%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 28        | 1.06%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 0.94%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 25        | 0.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 24        | 0.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 23        | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 23        | 0.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 22        | 0.83%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 22        | 0.83%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 0.79%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 20        | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 20        | 0.76%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 20        | 0.76%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 20        | 0.76%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.72%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 18        | 0.68%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 18        | 0.68%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 18        | 0.68%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 18        | 0.68%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 18        | 0.68%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 18        | 0.68%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 17        | 0.64%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 17        | 0.64%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 17        | 0.64%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 17        | 0.64%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 17        | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 0.6%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 16        | 0.6%    |
| Intel Celeron CPU N3050 @ 1.60GHz             | 16        | 0.6%    |
| Intel Core i5-3230M CPU @ 2.60GHz             | 15        | 0.57%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 15        | 0.57%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 15        | 0.57%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 15        | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 14        | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 552       | 20.85%  |
| Intel Core i7           | 391       | 14.77%  |
| Intel Core i3           | 275       | 10.39%  |
| Intel Core 2 Duo        | 228       | 8.61%   |
| Intel Celeron           | 226       | 8.53%   |
| Intel Atom              | 151       | 5.7%    |
| Other                   | 92        | 3.47%   |
| Intel Pentium           | 89        | 3.36%   |
| AMD Ryzen 5             | 60        | 2.27%   |
| AMD A6                  | 48        | 1.81%   |
| Intel Genuine           | 42        | 1.59%   |
| AMD Ryzen 7             | 42        | 1.59%   |
| AMD A4                  | 37        | 1.4%    |
| Intel Pentium Dual-Core | 35        | 1.32%   |
| Intel Pentium Dual      | 29        | 1.1%    |
| Intel Pentium M         | 25        | 0.94%   |
| Intel Core 2            | 25        | 0.94%   |
| Intel Celeron M         | 24        | 0.91%   |
| AMD A8                  | 23        | 0.87%   |
| AMD A10                 | 23        | 0.87%   |
| AMD E1                  | 21        | 0.79%   |
| AMD Ryzen 3             | 20        | 0.76%   |
| AMD E                   | 17        | 0.64%   |
| AMD Turion 64 X2 Mobile | 16        | 0.6%    |
| Intel Celeron Dual-Core | 9         | 0.34%   |
| AMD Turion 64 Mobile    | 9         | 0.34%   |
| Intel Pentium Silver    | 8         | 0.3%    |
| Intel Core M            | 8         | 0.3%    |
| AMD E2                  | 8         | 0.3%    |
| AMD Athlon II           | 8         | 0.3%    |
| Intel Core Duo          | 7         | 0.26%   |
| AMD Ryzen 9             | 7         | 0.26%   |
| AMD Athlon 64 X2        | 7         | 0.26%   |
| AMD Mobile Sempron      | 6         | 0.23%   |
| AMD C-50                | 6         | 0.23%   |
| AMD Athlon X2           | 6         | 0.23%   |
| AMD Athlon              | 6         | 0.23%   |
| AMD Sempron             | 5         | 0.19%   |
| AMD C-60                | 5         | 0.19%   |
| Intel Pentium 4         | 4         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1702      | 64.27%  |
| 4      | 630       | 23.79%  |
| 1      | 177       | 6.68%   |
| 6      | 72        | 2.72%   |
| 8      | 56        | 2.11%   |
| 14     | 4         | 0.15%   |
| 10     | 4         | 0.15%   |
| 3      | 2         | 0.08%   |
| 16     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2646      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1539      | 58.16%  |
| 1      | 1107      | 41.84%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2529      | 95.54%  |
| 32-bit         | 116       | 4.38%   |
| Unknown        | 2         | 0.08%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 245       | 9.13%   |
| Unknown    | 230       | 8.57%   |
| 0x306a9    | 195       | 7.27%   |
| 0x1067a    | 143       | 5.33%   |
| 0x40651    | 122       | 4.55%   |
| 0x20655    | 99        | 3.69%   |
| 0x6fd      | 83        | 3.09%   |
| 0x406e3    | 83        | 3.09%   |
| 0x306d4    | 79        | 2.94%   |
| 0x30678    | 78        | 2.91%   |
| 0x306c3    | 75        | 2.8%    |
| 0x806e9    | 64        | 2.39%   |
| 0x806ea    | 63        | 2.35%   |
| 0x806c1    | 53        | 1.98%   |
| 0x406c4    | 52        | 1.94%   |
| 0x10676    | 46        | 1.71%   |
| 0x806ec    | 42        | 1.57%   |
| 0x506c9    | 38        | 1.42%   |
| 0x406c3    | 38        | 1.42%   |
| 0x906ea    | 37        | 1.38%   |
| 0x20652    | 36        | 1.34%   |
| 0x106ca    | 33        | 1.23%   |
| 0x706a8    | 31        | 1.16%   |
| 0x06006705 | 31        | 1.16%   |
| 0x6e8      | 30        | 1.12%   |
| 0x906e9    | 29        | 1.08%   |
| 0x706e5    | 29        | 1.08%   |
| 0x6d8      | 29        | 1.08%   |
| 0x106c2    | 24        | 0.89%   |
| 0x08108109 | 24        | 0.89%   |
| 0x08108102 | 24        | 0.89%   |
| 0x07030105 | 24        | 0.89%   |
| 0x0700010f | 23        | 0.86%   |
| 0x05000119 | 23        | 0.86%   |
| 0x6f6      | 22        | 0.82%   |
| 0x6fb      | 21        | 0.78%   |
| 0x06001119 | 21        | 0.78%   |
| 0xa0652    | 17        | 0.63%   |
| 0x706a1    | 17        | 0.63%   |
| 0x10661    | 17        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 276       | 10.43%  |
| SandyBridge      | 251       | 9.49%   |
| Haswell          | 213       | 8.05%   |
| IvyBridge        | 206       | 7.79%   |
| Penryn           | 200       | 7.56%   |
| Silvermont       | 194       | 7.33%   |
| Core             | 170       | 6.42%   |
| Westmere         | 142       | 5.37%   |
| Skylake          | 100       | 3.78%   |
| P6               | 82        | 3.1%    |
| Broadwell        | 79        | 2.99%   |
| Bonnell          | 67        | 2.53%   |
| TigerLake        | 62        | 2.34%   |
| Excavator        | 57        | 2.15%   |
| Zen+             | 51        | 1.93%   |
| Goldmont plus    | 49        | 1.85%   |
| K8 Hammer        | 43        | 1.63%   |
| IceLake          | 40        | 1.51%   |
| Goldmont         | 40        | 1.51%   |
| Puma             | 39        | 1.47%   |
| Bobcat           | 35        | 1.32%   |
| Zen 2            | 32        | 1.21%   |
| Jaguar           | 29        | 1.1%    |
| Piledriver       | 25        | 0.94%   |
| Unknown          | 24        | 0.91%   |
| Zen 3            | 23        | 0.87%   |
| CometLake        | 22        | 0.83%   |
| K10              | 19        | 0.72%   |
| K10 Llano        | 17        | 0.64%   |
| K8 & K10 hybrid  | 15        | 0.57%   |
| Zen              | 14        | 0.53%   |
| Nehalem          | 10        | 0.38%   |
| Alderlake Hybrid | 6         | 0.23%   |
| Tremont          | 5         | 0.19%   |
| Steamroller      | 5         | 0.19%   |
| NetBurst         | 4         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1933      | 62.17%  |
| AMD                              | 598       | 19.23%  |
| Nvidia                           | 543       | 17.47%  |
| Silicon Integrated Systems [SiS] | 25        | 0.8%    |
| VIA Technologies                 | 10        | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 224       | 6.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 195       | 5.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 126       | 3.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 124       | 3.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 107       | 3.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 99        | 3%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 95        | 2.87%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 77        | 2.33%   |
| Intel HD Graphics 620                                                                    | 76        | 2.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 75        | 2.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 75        | 2.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 74        | 2.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 74        | 2.24%   |
| Intel UHD Graphics 620                                                                   | 61        | 1.85%   |
| Intel HD Graphics 5500                                                                   | 59        | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 52        | 1.57%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 50        | 1.51%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 1.42%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 46        | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 43        | 1.3%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 1.18%   |
| Intel HD Graphics 500                                                                    | 34        | 1.03%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 34        | 1.03%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 33        | 1%      |
| AMD Renoir                                                                               | 32        | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 28        | 0.85%   |
| Intel HD Graphics 630                                                                    | 27        | 0.82%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 26        | 0.79%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 25        | 0.76%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 24        | 0.73%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 24        | 0.73%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 24        | 0.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 24        | 0.73%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 22        | 0.67%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 21        | 0.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 20        | 0.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 0.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 0.54%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 17        | 0.51%   |
| AMD Lucienne                                                                             | 17        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1495      | 56.39%  |
| 1 x AMD        | 421       | 15.88%  |
| Intel + Nvidia | 325       | 12.26%  |
| 1 x Nvidia     | 185       | 6.98%   |
| Intel + AMD    | 108       | 4.07%   |
| 2 x AMD        | 41        | 1.55%   |
| AMD + Nvidia   | 29        | 1.09%   |
| 1 x SiS        | 25        | 0.94%   |
| 1 x VIA        | 10        | 0.38%   |
| Other          | 7         | 0.26%   |
| 2 x Nvidia     | 5         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2313      | 86.95%  |
| Proprietary | 260       | 9.77%   |
| Unknown     | 87        | 3.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1730      | 64.53%  |
| 0.01-0.5   | 424       | 15.81%  |
| 1.01-2.0   | 233       | 8.69%   |
| 0.51-1.0   | 169       | 6.3%    |
| 3.01-4.0   | 78        | 2.91%   |
| 5.01-6.0   | 19        | 0.71%   |
| 7.01-8.0   | 16        | 0.6%    |
| 2.01-3.0   | 11        | 0.41%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 522       | 19.52%  |
| LG Display              | 393       | 14.7%   |
| Samsung Electronics     | 371       | 13.87%  |
| Chimei Innolux          | 339       | 12.68%  |
| BOE                     | 294       | 10.99%  |
| Chi Mei Optoelectronics | 113       | 4.23%   |
| LG Philips              | 70        | 2.62%   |
| Apple                   | 64        | 2.39%   |
| Lenovo                  | 47        | 1.76%   |
| Dell                    | 40        | 1.5%    |
| Goldstar                | 38        | 1.42%   |
| Sharp                   | 37        | 1.38%   |
| InfoVision              | 31        | 1.16%   |
| PANDA                   | 28        | 1.05%   |
| CPT                     | 20        | 0.75%   |
| Toshiba                 | 17        | 0.64%   |
| Hewlett-Packard         | 17        | 0.64%   |
| HannStar                | 17        | 0.64%   |
| Sony                    | 13        | 0.49%   |
| Acer                    | 13        | 0.49%   |
| Quanta Display          | 11        | 0.41%   |
| Philips                 | 10        | 0.37%   |
| LGD                     | 10        | 0.37%   |
| BenQ                    | 10        | 0.37%   |
| Vizio                   | 9         | 0.34%   |
| InnoLux Display         | 9         | 0.34%   |
| AOC                     | 9         | 0.34%   |
| Seiko/Epson             | 8         | 0.3%    |
| Panasonic               | 8         | 0.3%    |
| Eizo                    | 6         | 0.22%   |
| Iiyama                  | 5         | 0.19%   |
| Ancor Communications    | 5         | 0.19%   |
| Unknown                 | 4         | 0.15%   |
| KDC                     | 4         | 0.15%   |
| IBM                     | 4         | 0.15%   |
| ASUSTek Computer        | 4         | 0.15%   |
| ViewSonic               | 3         | 0.11%   |
| TMX                     | 3         | 0.11%   |
| SLD                     | 3         | 0.11%   |
| SAC                     | 3         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 32        | 1.19%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 23        | 0.85%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 20        | 0.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.67%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 17        | 0.63%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.63%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 16        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 15        | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.56%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.52%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 14        | 0.52%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 14        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.48%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 13        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.44%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 11        | 0.41%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 11        | 0.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.41%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 10        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 10        | 0.37%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 10        | 0.37%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 9         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 9         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.33%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.33%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 8         | 0.3%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 8         | 0.3%    |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 8         | 0.3%    |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch             | 8         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 8         | 0.3%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 8         | 0.3%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 8         | 0.3%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 7         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 309x174mm 14.0-inch    | 7         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 7         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 7         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 1125      | 43.1%   |
| 1920x1080 (FHD)    | 692       | 26.51%  |
| 1280x800 (WXGA)    | 217       | 8.31%   |
| 1600x900 (HD+)     | 171       | 6.55%   |
| 1440x900 (WXGA+)   | 75        | 2.87%   |
| 3840x2160 (4K)     | 50        | 1.92%   |
| 1024x600           | 46        | 1.76%   |
| 1680x1050 (WSXGA+) | 30        | 1.15%   |
| 1920x1200 (WUXGA)  | 29        | 1.11%   |
| 2560x1440 (QHD)    | 21        | 0.8%    |
| 2560x1600          | 20        | 0.77%   |
| 1360x768           | 14        | 0.54%   |
| 1280x1024 (SXGA)   | 14        | 0.54%   |
| 1024x768 (XGA)     | 10        | 0.38%   |
| Unknown            | 9         | 0.34%   |
| 2160x1440          | 8         | 0.31%   |
| 2560x1080          | 7         | 0.27%   |
| 2256x1504          | 7         | 0.27%   |
| 1280x768           | 7         | 0.27%   |
| 3200x1800 (QHD+)   | 6         | 0.23%   |
| 2880x1800          | 6         | 0.23%   |
| 1920x540           | 5         | 0.19%   |
| 3840x2400          | 4         | 0.15%   |
| 1680x945           | 4         | 0.15%   |
| 3840x1080          | 3         | 0.11%   |
| 3440x1440          | 3         | 0.11%   |
| 1400x1050          | 3         | 0.11%   |
| 1024x576           | 3         | 0.11%   |
| 5760x1080          | 2         | 0.08%   |
| 3600x1080          | 2         | 0.08%   |
| 2880x1920          | 2         | 0.08%   |
| 2288x1287          | 2         | 0.08%   |
| 1920x515           | 2         | 0.08%   |
| 5760x2160          | 1         | 0.04%   |
| 4480x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2240x1400          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1188      | 44.48%  |
| 13      | 345       | 12.92%  |
| 14      | 303       | 11.34%  |
| 17      | 233       | 8.72%   |
| 11      | 102       | 3.82%   |
| 12      | 72        | 2.7%    |
| Unknown | 62        | 2.32%   |
| 10      | 56        | 2.1%    |
| 24      | 41        | 1.54%   |
| 27      | 37        | 1.39%   |
| 23      | 30        | 1.12%   |
| 21      | 29        | 1.09%   |
| 18      | 26        | 0.97%   |
| 16      | 17        | 0.64%   |
| 31      | 15        | 0.56%   |
| 34      | 13        | 0.49%   |
| 20      | 12        | 0.45%   |
| 22      | 11        | 0.41%   |
| 19      | 11        | 0.41%   |
| 72      | 9         | 0.34%   |
| 40      | 8         | 0.3%    |
| 84      | 5         | 0.19%   |
| 54      | 5         | 0.19%   |
| 32      | 4         | 0.15%   |
| 8       | 4         | 0.15%   |
| 74      | 3         | 0.11%   |
| 49      | 3         | 0.11%   |
| 25      | 3         | 0.11%   |
| 58      | 2         | 0.07%   |
| 52      | 2         | 0.07%   |
| 47      | 2         | 0.07%   |
| 37      | 2         | 0.07%   |
| 36      | 2         | 0.07%   |
| 29      | 2         | 0.07%   |
| 26      | 2         | 0.07%   |
| 65      | 1         | 0.04%   |
| 64      | 1         | 0.04%   |
| 59      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1647      | 61.89%  |
| 201-300     | 384       | 14.43%  |
| 351-400     | 280       | 10.52%  |
| 501-600     | 105       | 3.95%   |
| 401-500     | 88        | 3.31%   |
| Unknown     | 62        | 2.33%   |
| 601-700     | 21        | 0.79%   |
| 701-800     | 20        | 0.75%   |
| 1001-1500   | 19        | 0.71%   |
| 1501-2000   | 17        | 0.64%   |
| 801-900     | 11        | 0.41%   |
| 101-200     | 4         | 0.15%   |
| 901-1000    | 3         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1994      | 80.44%  |
| 16/10   | 368       | 14.84%  |
| Unknown | 48        | 1.94%   |
| 3/2     | 21        | 0.85%   |
| 4/3     | 19        | 0.77%   |
| 5/4     | 12        | 0.48%   |
| 21/9    | 12        | 0.48%   |
| 32/9    | 2         | 0.08%   |
| 3.73    | 2         | 0.08%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1190      | 44.62%  |
| 81-90          | 534       | 20.02%  |
| 121-130        | 169       | 6.34%   |
| 71-80          | 107       | 4.01%   |
| 51-60          | 102       | 3.82%   |
| 201-250        | 90        | 3.37%   |
| 61-70          | 71        | 2.66%   |
| Unknown        | 62        | 2.32%   |
| 41-50          | 56        | 2.1%    |
| 131-140        | 54        | 2.02%   |
| 301-350        | 38        | 1.42%   |
| 151-200        | 37        | 1.39%   |
| 351-500        | 34        | 1.27%   |
| 141-150        | 34        | 1.27%   |
| More than 1000 | 32        | 1.2%    |
| 501-1000       | 21        | 0.79%   |
| 251-300        | 11        | 0.41%   |
| 91-100         | 11        | 0.41%   |
| 111-120        | 10        | 0.37%   |
| 1-40           | 4         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1178      | 44.93%  |
| 121-160       | 740       | 28.22%  |
| 51-100        | 464       | 17.7%   |
| 161-240       | 109       | 4.16%   |
| Unknown       | 62        | 2.36%   |
| 1-50          | 36        | 1.37%   |
| More than 240 | 33        | 1.26%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2302      | 85.58%  |
| 2     | 275       | 10.22%  |
| 0     | 92        | 3.42%   |
| 3     | 19        | 0.71%   |
| 5     | 1         | 0.04%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1331      | 30.92%  |
| Intel                             | 1089      | 25.3%   |
| Qualcomm Atheros                  | 745       | 17.31%  |
| Broadcom                          | 439       | 10.2%   |
| Broadcom Limited                  | 139       | 3.23%   |
| Marvell Technology Group          | 80        | 1.86%   |
| Ralink                            | 54        | 1.25%   |
| Nvidia                            | 39        | 0.91%   |
| TP-Link                           | 30        | 0.7%    |
| Silicon Integrated Systems [SiS]  | 26        | 0.6%    |
| Ralink Technology                 | 25        | 0.58%   |
| MediaTek                          | 24        | 0.56%   |
| ASIX Electronics                  | 23        | 0.53%   |
| JMicron Technology                | 22        | 0.51%   |
| Samsung Electronics               | 21        | 0.49%   |
| Dell                              | 20        | 0.46%   |
| Xiaomi                            | 16        | 0.37%   |
| Hewlett-Packard                   | 14        | 0.33%   |
| Sierra Wireless                   | 12        | 0.28%   |
| Huawei Technologies               | 11        | 0.26%   |
| DisplayLink                       | 11        | 0.26%   |
| VIA Technologies                  | 9         | 0.21%   |
| Qualcomm Atheros Communications   | 9         | 0.21%   |
| Ericsson Business Mobile Networks | 9         | 0.21%   |
| OPPO Electronics                  | 8         | 0.19%   |
| Edimax Technology                 | 8         | 0.19%   |
| ASUSTek Computer                  | 8         | 0.19%   |
| AMD                               | 8         | 0.19%   |
| NetGear                           | 7         | 0.16%   |
| Qualcomm                          | 6         | 0.14%   |
| Attansic Technology               | 6         | 0.14%   |
| Motorola PCS                      | 5         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.09%   |
| D-Link System                     | 4         | 0.09%   |
| T & A Mobile Phones               | 3         | 0.07%   |
| Linksys                           | 3         | 0.07%   |
| D-Link                            | 3         | 0.07%   |
| Belkin Components                 | 3         | 0.07%   |
| ZyDAS                             | 2         | 0.05%   |
| Micro Star International          | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 657       | 12.83%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 382       | 7.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 136       | 2.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 124       | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 108       | 2.11%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 107       | 2.09%   |
| Intel Wireless 7260                                                     | 103       | 2.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 98        | 1.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 77        | 1.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 70        | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 67        | 1.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 63        | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                           | 62        | 1.21%   |
| Intel Wireless 8265 / 8275                                              | 60        | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 58        | 1.13%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 57        | 1.11%   |
| Intel Wireless 7265                                                     | 56        | 1.09%   |
| Intel Wireless 3165                                                     | 49        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 48        | 0.94%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 48        | 0.94%   |
| Intel WiFi Link 5100                                                    | 45        | 0.88%   |
| Intel Wi-Fi 6 AX200                                                     | 44        | 0.86%   |
| Intel Wireless 8260                                                     | 43        | 0.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 40        | 0.78%   |
| Intel Wi-Fi 6 AX201                                                     | 40        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 37        | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 36        | 0.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 0.66%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 34        | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 33        | 0.64%   |
| Intel Ethernet Connection I217-LM                                       | 33        | 0.64%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 33        | 0.64%   |
| Intel Wireless 3160                                                     | 32        | 0.63%   |
| Intel Ethernet Connection I218-LM                                       | 32        | 0.63%   |
| Intel Centrino Ultimate-N 6300                                          | 32        | 0.63%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 31        | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 31        | 0.61%   |
| Intel 82577LM Gigabit Network Connection                                | 31        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                                | 29        | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 26        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1010      | 36.87%  |
| Qualcomm Atheros                | 631       | 23.04%  |
| Realtek Semiconductor           | 462       | 16.87%  |
| Broadcom                        | 335       | 12.23%  |
| Broadcom Limited                | 95        | 3.47%   |
| Ralink                          | 54        | 1.97%   |
| Ralink Technology               | 25        | 0.91%   |
| TP-Link                         | 24        | 0.88%   |
| MediaTek                        | 21        | 0.77%   |
| Sierra Wireless                 | 12        | 0.44%   |
| Qualcomm Atheros Communications | 9         | 0.33%   |
| Dell                            | 9         | 0.33%   |
| Edimax Technology               | 8         | 0.29%   |
| NetGear                         | 7         | 0.26%   |
| ASUSTek Computer                | 7         | 0.26%   |
| D-Link System                   | 4         | 0.15%   |
| Linksys                         | 3         | 0.11%   |
| Hewlett-Packard                 | 3         | 0.11%   |
| D-Link                          | 3         | 0.11%   |
| Belkin Components               | 3         | 0.11%   |
| ZyDAS                           | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| ZyXEL Communications            | 1         | 0.04%   |
| Xiaomi                          | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Qualcomm                        | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| Lite-On Technology              | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| Fibocom                         | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 136       | 4.92%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 124       | 4.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 108       | 3.91%   |
| Intel Wireless 7260                                                     | 103       | 3.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 98        | 3.55%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 77        | 2.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 70        | 2.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 67        | 2.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 63        | 2.28%   |
| Broadcom BCM43142 802.11b/g/n                                           | 62        | 2.24%   |
| Intel Wireless 8265 / 8275                                              | 60        | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 58        | 2.1%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 57        | 2.06%   |
| Intel Wireless 7265                                                     | 56        | 2.03%   |
| Intel Wireless 3165                                                     | 49        | 1.77%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 48        | 1.74%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 48        | 1.74%   |
| Intel WiFi Link 5100                                                    | 45        | 1.63%   |
| Intel Wi-Fi 6 AX200                                                     | 44        | 1.59%   |
| Intel Wireless 8260                                                     | 43        | 1.56%   |
| Intel Wi-Fi 6 AX201                                                     | 40        | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 37        | 1.34%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 34        | 1.23%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 34        | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 33        | 1.19%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 33        | 1.19%   |
| Intel Wireless 3160                                                     | 32        | 1.16%   |
| Intel Centrino Ultimate-N 6300                                          | 32        | 1.16%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 31        | 1.12%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 26        | 0.94%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 26        | 0.94%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 25        | 0.9%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 24        | 0.87%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 23        | 0.83%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 23        | 0.83%   |
| Intel Centrino Wireless-N 2230                                          | 23        | 0.83%   |
| Intel Centrino Advanced-N 6235                                          | 23        | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 22        | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 21        | 0.76%   |
| Intel Centrino Advanced-N 6200                                          | 21        | 0.76%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1135      | 50.18%  |
| Intel                                  | 421       | 18.61%  |
| Qualcomm Atheros                       | 196       | 8.66%   |
| Broadcom                               | 156       | 6.9%    |
| Marvell Technology Group               | 80        | 3.54%   |
| Broadcom Limited                       | 49        | 2.17%   |
| Nvidia                                 | 39        | 1.72%   |
| Silicon Integrated Systems [SiS]       | 24        | 1.06%   |
| ASIX Electronics                       | 23        | 1.02%   |
| JMicron Technology                     | 22        | 0.97%   |
| Samsung Electronics                    | 21        | 0.93%   |
| Xiaomi                                 | 15        | 0.66%   |
| DisplayLink                            | 11        | 0.49%   |
| VIA Technologies                       | 9         | 0.4%    |
| OPPO Electronics                       | 8         | 0.35%   |
| Huawei Technologies                    | 8         | 0.35%   |
| TP-Link                                | 6         | 0.27%   |
| Attansic Technology                    | 6         | 0.27%   |
| Qualcomm                               | 5         | 0.22%   |
| Motorola PCS                           | 5         | 0.22%   |
| MediaTek                               | 3         | 0.13%   |
| Hewlett-Packard                        | 3         | 0.13%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |
| Davicom Semiconductor                  | 2         | 0.09%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.04%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| Novatel Wireless                       | 1         | 0.04%   |
| Motorola BCS                           | 1         | 0.04%   |
| LG Electronics                         | 1         | 0.04%   |
| Lenovo                                 | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| GoPro                                  | 1         | 0.04%   |
| ASUSTek Computer                       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 657       | 28.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 382       | 16.83%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 107       | 4.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 1.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 36        | 1.59%   |
| Intel Ethernet Connection I217-LM                                 | 33        | 1.45%   |
| Intel Ethernet Connection I218-LM                                 | 32        | 1.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 31        | 1.37%   |
| Intel 82577LM Gigabit Network Connection                          | 31        | 1.37%   |
| Intel 82567LM Gigabit Network Connection                          | 29        | 1.28%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 1.15%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 24        | 1.06%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 1.01%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 22        | 0.97%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 22        | 0.97%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.97%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 20        | 0.88%   |
| Intel 82566MM Gigabit Network Connection                          | 20        | 0.88%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 17        | 0.75%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 17        | 0.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 17        | 0.75%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 16        | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 15        | 0.66%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 15        | 0.66%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.62%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 13        | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 13        | 0.57%   |
| Nvidia MCP67 Ethernet                                             | 13        | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 13        | 0.57%   |
| Intel PRO/100 VE Network Connection                               | 13        | 0.57%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.57%   |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 13        | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 13        | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.53%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 12        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 0.48%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 11        | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2557      | 52.98%  |
| Ethernet | 2184      | 45.25%  |
| Modem    | 80        | 1.66%   |
| Unknown  | 5         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2144      | 78.19%  |
| Ethernet | 597       | 21.77%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2022      | 76.3%   |
| 1     | 508       | 19.17%  |
| 0     | 109       | 4.11%   |
| 3     | 11        | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2108      | 78.66%  |
| Yes  | 572       | 21.34%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 609       | 35.28%  |
| Qualcomm Atheros Communications | 221       | 12.8%   |
| Realtek Semiconductor           | 192       | 11.12%  |
| Broadcom                        | 141       | 8.17%   |
| IMC Networks                    | 84        | 4.87%   |
| Lite-On Technology              | 65        | 3.77%   |
| Dell                            | 64        | 3.71%   |
| Foxconn / Hon Hai               | 61        | 3.53%   |
| Hewlett-Packard                 | 59        | 3.42%   |
| Apple                           | 57        | 3.3%    |
| Toshiba                         | 38        | 2.2%    |
| Cambridge Silicon Radio         | 28        | 1.62%   |
| Ralink                          | 22        | 1.27%   |
| ASUSTek Computer                | 16        | 0.93%   |
| Alps Electric                   | 14        | 0.81%   |
| Realtek                         | 13        | 0.75%   |
| Foxconn International           | 12        | 0.7%    |
| Askey Computer                  | 6         | 0.35%   |
| Ralink Technology               | 5         | 0.29%   |
| Taiyo Yuden                     | 4         | 0.23%   |
| Dynex                           | 3         | 0.17%   |
| Chicony Electronics             | 3         | 0.17%   |
| Qcom                            | 2         | 0.12%   |
| MediaTek                        | 2         | 0.12%   |
| Integrated System Solution      | 2         | 0.12%   |
| TP-Link                         | 1         | 0.06%   |
| Belkin Components               | 1         | 0.06%   |
| Unknown                         | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 324       | 18.75%  |
| Realtek Bluetooth Radio                             | 118       | 6.83%   |
| Qualcomm Atheros  Bluetooth Device                  | 95        | 5.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 73        | 4.22%   |
| Intel AX201 Bluetooth                               | 70        | 4.05%   |
| Realtek  Bluetooth 4.2 Adapter                      | 57        | 3.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 42        | 2.43%   |
| Intel AX200 Bluetooth                               | 42        | 2.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 37        | 2.14%   |
| Apple Bluetooth Host Controller                     | 34        | 1.97%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 33        | 1.91%   |
| IMC Networks Bluetooth Device                       | 32        | 1.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 31        | 1.79%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 28        | 1.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 23        | 1.33%   |
| Ralink RT3290 Bluetooth                             | 22        | 1.27%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 22        | 1.27%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 21        | 1.22%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 20        | 1.16%   |
| IMC Networks Bluetooth Radio                        | 20        | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                    | 20        | 1.16%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 19        | 1.1%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 18        | 1.04%   |
| Dell DW375 Bluetooth Module                         | 18        | 1.04%   |
| Broadcom BCM2045B (BDC-2.1)                         | 18        | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 0.93%   |
| Intel AX210 Bluetooth                               | 14        | 0.81%   |
| Realtek Bluetooth Radio                             | 13        | 0.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 13        | 0.75%   |
| Toshiba Bluetooth Device                            | 12        | 0.69%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 0.69%   |
| IMC Networks Wireless_Device                        | 12        | 0.69%   |
| Foxconn International BCM43142A0 Bluetooth module   | 12        | 0.69%   |
| Dell Wireless 365 Bluetooth                         | 12        | 0.69%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.64%   |
| Lite-On Bluetooth Device                            | 10        | 0.58%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.58%   |
| Toshiba Integrated Bluetooth HCI                    | 9         | 0.52%   |
| Realtek RTL8723B Bluetooth                          | 9         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2084      | 70.24%  |
| AMD                                  | 472       | 15.91%  |
| Nvidia                               | 297       | 10.01%  |
| Silicon Integrated Systems [SiS]     | 28        | 0.94%   |
| VIA Technologies                     | 10        | 0.34%   |
| C-Media Electronics                  | 9         | 0.3%    |
| Generalplus Technology               | 7         | 0.24%   |
| Tenx Technology                      | 6         | 0.2%    |
| Realtek Semiconductor                | 4         | 0.13%   |
| Logitech                             | 4         | 0.13%   |
| Creative Technology                  | 4         | 0.13%   |
| Texas Instruments                    | 3         | 0.1%    |
| SteelSeries ApS                      | 3         | 0.1%    |
| Lenovo                               | 3         | 0.1%    |
| JMTek                                | 3         | 0.1%    |
| GN Netcom                            | 3         | 0.1%    |
| Yamaha                               | 2         | 0.07%   |
| Plantronics                          | 2         | 0.07%   |
| Focusrite-Novation                   | 2         | 0.07%   |
| DCMT Technology                      | 2         | 0.07%   |
| ZOOM                                 | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.03%   |
| Syntek                               | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| Sennheiser Communications            | 1         | 0.03%   |
| SAVITECH                             | 1         | 0.03%   |
| Roland                               | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |
| PreSonus Audio Electronics           | 1         | 0.03%   |
| OPPO Electronics                     | 1         | 0.03%   |
| Kingston Technology                  | 1         | 0.03%   |
| Hewlett-Packard                      | 1         | 0.03%   |
| DSEA A/S                             | 1         | 0.03%   |
| Dell                                 | 1         | 0.03%   |
| Corsair                              | 1         | 0.03%   |
| Conexant Systems                     | 1         | 0.03%   |
| CMX Systems                          | 1         | 0.03%   |
| ASUSTek Computer                     | 1         | 0.03%   |
| AKAI Professional M.I.               | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 252       | 7.02%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 230       | 6.4%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 204       | 5.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 174       | 4.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 152       | 4.23%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 137       | 3.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 137       | 3.81%   |
| Intel 8 Series HD Audio Controller                                                                | 128       | 3.56%   |
| AMD FCH Azalia Controller                                                                         | 125       | 3.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 124       | 3.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 118       | 3.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 85        | 2.37%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 79        | 2.2%    |
| Intel Broadwell-U Audio Controller                                                                | 79        | 2.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 79        | 2.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 71        | 1.98%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 69        | 1.92%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 62        | 1.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 62        | 1.73%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 62        | 1.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 58        | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 55        | 1.53%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 49        | 1.36%   |
| AMD High Definition Audio Controller                                                              | 46        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 45        | 1.25%   |
| Intel Cannon Lake PCH cAVS                                                                        | 45        | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 41        | 1.14%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 40        | 1.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 36        | 1%      |
| Intel CM238 HD Audio Controller                                                                   | 31        | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 30        | 0.84%   |
| AMD Wrestler HDMI Audio                                                                           | 29        | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 27        | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                                 | 25        | 0.7%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 24        | 0.67%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 24        | 0.67%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 23        | 0.64%   |
| Nvidia High Definition Audio Controller                                                           | 22        | 0.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 20        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 18        | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 155       | 24.88%  |
| SK hynix               | 146       | 23.43%  |
| Micron Technology      | 68        | 10.91%  |
| Unknown                | 60        | 9.63%   |
| Kingston               | 48        | 7.7%    |
| Unknown (ABCD)         | 19        | 3.05%   |
| Nanya Technology       | 15        | 2.41%   |
| Crucial                | 15        | 2.41%   |
| Ramaxel Technology     | 14        | 2.25%   |
| Elpida                 | 14        | 2.25%   |
| A-DATA Technology      | 13        | 2.09%   |
| Smart                  | 7         | 1.12%   |
| Qimonda                | 4         | 0.64%   |
| Corsair                | 3         | 0.48%   |
| Transcend              | 2         | 0.32%   |
| Timetec                | 2         | 0.32%   |
| Teikon                 | 2         | 0.32%   |
| Team                   | 2         | 0.32%   |
| SHARETRONIC            | 2         | 0.32%   |
| Patriot                | 2         | 0.32%   |
| High Bridge            | 2         | 0.32%   |
| ff                     | 2         | 0.32%   |
| fef5                   | 2         | 0.32%   |
| 4ea5                   | 2         | 0.32%   |
| Walton Chaintech       | 1         | 0.16%   |
| Unknown (08B5)         | 1         | 0.16%   |
| Unknown (000080B30080) | 1         | 0.16%   |
| Toshiba                | 1         | 0.16%   |
| Strontium              | 1         | 0.16%   |
| Smart Brazil           | 1         | 0.16%   |
| PUSKILL                | 1         | 0.16%   |
| ProMos/Mosel Vitelic   | 1         | 0.16%   |
| Netlist                | 1         | 0.16%   |
| Nayna                  | 1         | 0.16%   |
| Kllisre                | 1         | 0.16%   |
| Kingmax                | 1         | 0.16%   |
| HBS                    | 1         | 0.16%   |
| GSkill                 | 1         | 0.16%   |
| G.Skill                | 1         | 0.16%   |
| Essencore              | 1         | 0.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 17        | 2.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 1.35%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 1.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 1.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 1.35%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 1.05%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 1.05%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 800MT/s             | 6         | 0.9%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.9%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.9%    |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 6         | 0.9%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.75%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.75%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.75%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 4         | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 0.6%    |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 4         | 0.6%    |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.6%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.6%    |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 4         | 0.6%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.6%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.6%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.6%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.6%    |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.6%    |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 4         | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.6%    |
| SK hynix RAM Module 8192MB SODIMM DDR4 2133MT/s                  | 3         | 0.45%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.45%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.45%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 212       | 40.46%  |
| DDR4    | 162       | 30.92%  |
| DDR2    | 63        | 12.02%  |
| LPDDR4  | 34        | 6.49%   |
| SDRAM   | 19        | 3.63%   |
| LPDDR3  | 15        | 2.86%   |
| DRAM    | 6         | 1.15%   |
| DDR     | 5         | 0.95%   |
| Unknown | 5         | 0.95%   |
| DDR5    | 2         | 0.38%   |
| LPDDR5  | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 457       | 88.39%  |
| Row Of Chips | 39        | 7.54%   |
| DIMM         | 11        | 2.13%   |
| Unknown      | 6         | 1.16%   |
| Chip         | 4         | 0.77%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 193       | 32.77%  |
| 8192  | 172       | 29.2%   |
| 2048  | 127       | 21.56%  |
| 1024  | 47        | 7.98%   |
| 16384 | 33        | 5.6%    |
| 512   | 11        | 1.87%   |
| 32768 | 4         | 0.68%   |
| 256   | 2         | 0.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 142       | 24.91%  |
| 2667    | 80        | 14.04%  |
| 3200    | 57        | 10%     |
| 2400    | 47        | 8.25%   |
| 1334    | 38        | 6.67%   |
| 667     | 37        | 6.49%   |
| 1333    | 25        | 4.39%   |
| Unknown | 24        | 4.21%   |
| 2133    | 21        | 3.68%   |
| 1066    | 14        | 2.46%   |
| 800     | 11        | 1.93%   |
| 533     | 10        | 1.75%   |
| 4199    | 9         | 1.58%   |
| 3266    | 9         | 1.58%   |
| 975     | 9         | 1.58%   |
| 4267    | 8         | 1.4%    |
| 2048    | 6         | 1.05%   |
| 1867    | 5         | 0.88%   |
| 1067    | 5         | 0.88%   |
| 8400    | 3         | 0.53%   |
| 400     | 3         | 0.53%   |
| 4800    | 2         | 0.35%   |
| 6400    | 1         | 0.18%   |
| 4266    | 1         | 0.18%   |
| 3733    | 1         | 0.18%   |
| 2933    | 1         | 0.18%   |
| 1639    | 1         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 39.29%  |
| Canon                 | 6         | 21.43%  |
| Seiko Epson           | 4         | 14.29%  |
| Samsung Electronics   | 2         | 7.14%   |
| Brother Industries    | 2         | 7.14%   |
| Zebra                 | 1         | 3.57%   |
| STMicroelectronics    | 1         | 3.57%   |
| Lexmark International | 1         | 3.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series                                 | 2         | 7.14%   |
| HP DeskJet 1110 series                                    | 2         | 7.14%   |
| Zebra ZP 450 Printer                                      | 1         | 3.57%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.57%   |
| Seiko Epson WF-2010 Series                                | 1         | 3.57%   |
| Seiko Epson Printer                                       | 1         | 3.57%   |
| Seiko Epson L3110 Series                                  | 1         | 3.57%   |
| Seiko Epson ET-2810 Series                                | 1         | 3.57%   |
| Samsung M2020 Series                                      | 1         | 3.57%   |
| Samsung CLX-3300 Series                                   | 1         | 3.57%   |
| Lexmark International 2400 series                         | 1         | 3.57%   |
| HP Laserjet P1505                                         | 1         | 3.57%   |
| HP LaserJet 1200                                          | 1         | 3.57%   |
| HP LaserJet 1020                                          | 1         | 3.57%   |
| HP LaserJet 1000                                          | 1         | 3.57%   |
| HP DeskJet 2700 series                                    | 1         | 3.57%   |
| HP DeskJet 2300 series                                    | 1         | 3.57%   |
| HP Deskjet 1510                                           | 1         | 3.57%   |
| Canon TS3100 series                                       | 1         | 3.57%   |
| Canon PIXMA MX490 Series                                  | 1         | 3.57%   |
| Canon PIXMA MX340                                         | 1         | 3.57%   |
| Canon PIXMA MG3600 Series                                 | 1         | 3.57%   |
| Canon PIXMA MG3000 series                                 | 1         | 3.57%   |
| Canon MG2100 series                                       | 1         | 3.57%   |
| Brother MFC-L2730DW series                                | 1         | 3.57%   |
| Brother DCP-T300                                          | 1         | 3.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 60%     |
| Seiko Epson | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 40%     |
| Canon CanoScan LiDE 90                      | 1         | 20%     |
| Canon CanoScan LIDE 25                      | 1         | 20%     |
| Canon CanoScan LiDE 200                     | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 542       | 25.42%  |
| Microdia                               | 206       | 9.66%   |
| Realtek Semiconductor                  | 176       | 8.26%   |
| IMC Networks                           | 168       | 7.88%   |
| Acer                                   | 127       | 5.96%   |
| Sunplus Innovation Technology          | 119       | 5.58%   |
| Suyin                                  | 117       | 5.49%   |
| Cheng Uei Precision Industry (Foxlink) | 99        | 4.64%   |
| Quanta                                 | 87        | 4.08%   |
| Syntek                                 | 54        | 2.53%   |
| Apple                                  | 54        | 2.53%   |
| Silicon Motion                         | 50        | 2.35%   |
| Lite-On Technology                     | 39        | 1.83%   |
| Alcor Micro                            | 38        | 1.78%   |
| Ricoh                                  | 32        | 1.5%    |
| Bison Electronics                      | 22        | 1.03%   |
| Luxvisions Innotech Limited            | 17        | 0.8%    |
| Importek                               | 17        | 0.8%    |
| ALi                                    | 16        | 0.75%   |
| Primax Electronics                     | 14        | 0.66%   |
| Samsung Electronics                    | 13        | 0.61%   |
| USB Camera                             | 11        | 0.52%   |
| Z-Star Microelectronics                | 10        | 0.47%   |
| Logitech                               | 10        | 0.47%   |
| Lenovo                                 | 10        | 0.47%   |
| OmniVision Technologies                | 9         | 0.42%   |
| GEMBIRD                                | 9         | 0.42%   |
| Sonix Technology                       | 8         | 0.38%   |
| SunplusIT                              | 5         | 0.23%   |
| Genesys Logic                          | 5         | 0.23%   |
| Sunplus Technology                     | 4         | 0.19%   |
| Y Media                                | 3         | 0.14%   |
| Intel                                  | 3         | 0.14%   |
| Generalplus Technology                 | 3         | 0.14%   |
| ARC International                      | 3         | 0.14%   |
| YGTek                                  | 2         | 0.09%   |
| Microsoft                              | 2         | 0.09%   |
| LG Electronics                         | 2         | 0.09%   |
| Huawei Technologies                    | 2         | 0.09%   |
| Camera                                 | 2         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 65        | 3.04%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 40        | 1.87%   |
| Microdia Integrated_Webcam_HD                           | 38        | 1.78%   |
| Realtek Integrated_Webcam_HD                            | 36        | 1.68%   |
| Microdia Integrated Webcam                              | 36        | 1.68%   |
| Chicony HP Truevision HD                                | 33        | 1.54%   |
| Acer Lenovo EasyCamera                                  | 30        | 1.4%    |
| Chicony HD WebCam                                       | 29        | 1.36%   |
| Chicony TOSHIBA Web Camera - HD                         | 28        | 1.31%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 25        | 1.17%   |
| Syntek Integrated Camera                                | 24        | 1.12%   |
| Chicony USB 2.0 Camera                                  | 23        | 1.08%   |
| Chicony HP Truevision HD camera                         | 22        | 1.03%   |
| Acer Integrated Camera                                  | 22        | 1.03%   |
| Sunplus Integrated_Webcam_HD                            | 20        | 0.94%   |
| IMC Networks Integrated Camera                          | 20        | 0.94%   |
| Chicony Lenovo EasyCamera                               | 20        | 0.94%   |
| Sunplus HD WebCam                                       | 19        | 0.89%   |
| Realtek Integrated Webcam                               | 19        | 0.89%   |
| Chicony HP HD Webcam                                    | 18        | 0.84%   |
| Chicony EasyCamera                                      | 18        | 0.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 18        | 0.84%   |
| Realtek USB Camera                                      | 17        | 0.8%    |
| Chicony VGA WebCam                                      | 17        | 0.8%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 17        | 0.8%    |
| Suyin HP Truevision HD                                  | 16        | 0.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 15        | 0.7%    |
| Microdia Laptop_Integrated_Webcam_HD                    | 15        | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam                           | 15        | 0.7%    |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.7%    |
| Apple FaceTime HD Camera                                | 15        | 0.7%    |
| Quanta HP Webcam                                        | 14        | 0.66%   |
| Quanta HP TrueVision HD Camera                          | 14        | 0.66%   |
| Microdia Sonix USB 2.0 Camera                           | 14        | 0.66%   |
| Chicony USB2.0 HD UVC WebCam                            | 14        | 0.66%   |
| Chicony HP Webcam                                       | 14        | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.66%   |
| ALi Gateway Webcam                                      | 14        | 0.66%   |
| Alcor Micro USB 2.0 Camera                              | 14        | 0.66%   |
| Samsung Galaxy A5 (MTP)                                 | 13        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 171       | 47.77%  |
| AuthenTec                  | 56        | 15.64%  |
| Upek                       | 32        | 8.94%   |
| Shenzhen Goodix Technology | 32        | 8.94%   |
| Synaptics                  | 23        | 6.42%   |
| STMicroelectronics         | 18        | 5.03%   |
| Elan Microelectronics      | 17        | 4.75%   |
| LighTuning Technology      | 7         | 1.96%   |
| Samsung Electronics        | 1         | 0.28%   |
| Focal-systems.Corp         | 1         | 0.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 38        | 10.61%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 31        | 8.66%   |
| Shenzhen Goodix  Fingerprint Device                                        | 23        | 6.42%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 21        | 5.87%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 20        | 5.59%   |
| STMicroelectronics Fingerprint Reader                                      | 18        | 5.03%   |
| Validity Sensors VFS491                                                    | 17        | 4.75%   |
| AuthenTec AES2810                                                          | 17        | 4.75%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 17        | 4.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 16        | 4.47%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 4.47%   |
| Elan ELAN:ARM-M4                                                           | 9         | 2.51%   |
| AuthenTec AES1600                                                          | 9         | 2.51%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.23%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.23%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.68%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 1.68%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.68%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.4%    |
| Validity Sensors Synaptics WBDI                                            | 5         | 1.4%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 1.4%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 1.4%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.12%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.12%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.12%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 1.12%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.84%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.84%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.56%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.56%   |
| Synaptics WBDI                                                             | 2         | 0.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.56%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.56%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.28%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.28%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.28%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 80        | 52.29%  |
| Alcor Micro                       | 25        | 16.34%  |
| O2 Micro                          | 24        | 15.69%  |
| Lenovo                            | 9         | 5.88%   |
| Upek                              | 7         | 4.58%   |
| Yubico.com                        | 2         | 1.31%   |
| SCM Microsystems                  | 2         | 1.31%   |
| Realtek Semiconductor             | 2         | 1.31%   |
| VASCO Data Security International | 1         | 0.65%   |
| OmniKey                           | 1         | 0.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 39        | 25.32%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 15.58%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 21        | 13.64%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 12.34%  |
| Broadcom 5880                                                                | 17        | 11.04%  |
| Lenovo Integrated Smart Card Reader                                          | 9         | 5.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.55%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 3.25%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.3%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.3%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.3%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.3%    |
| Broadcom 58200                                                               | 2         | 1.3%    |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.65%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.65%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1728      | 64.38%  |
| 1     | 750       | 27.94%  |
| 2     | 190       | 7.08%   |
| 3     | 13        | 0.48%   |
| 4     | 2         | 0.07%   |
| 7     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 351       | 30.79%  |
| Graphics card            | 268       | 23.51%  |
| Chipcard                 | 144       | 12.63%  |
| Net/wireless             | 132       | 11.58%  |
| Multimedia controller    | 72        | 6.32%   |
| Storage                  | 40        | 3.51%   |
| Modem                    | 36        | 3.16%   |
| Bluetooth                | 29        | 2.54%   |
| Sound                    | 14        | 1.23%   |
| Flash memory             | 12        | 1.05%   |
| Camera                   | 12        | 1.05%   |
| Communication controller | 10        | 0.88%   |
| Net/ethernet             | 6         | 0.53%   |
| Card reader              | 5         | 0.44%   |
| Network                  | 3         | 0.26%   |
| Storage/nvme             | 2         | 0.18%   |
| Unclassified device      | 1         | 0.09%   |
| Storage/ide              | 1         | 0.09%   |
| Storage/ata              | 1         | 0.09%   |
| Dvb card                 | 1         | 0.09%   |

