Ubuntu MATE - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 743

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 3 15IML05 81WR      | [81dced5e0a](https://linux-hardware.org/?probe=81dced5e0a) | Apr 16, 2022 |
| Dell          | Latitude E5530 non-vPro     | [2f865445ce](https://linux-hardware.org/?probe=2f865445ce) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | [d32ffb065a](https://linux-hardware.org/?probe=d32ffb065a) | Apr 14, 2022 |
| Clevo         | W54xEU                      | [7b1c6d8b2e](https://linux-hardware.org/?probe=7b1c6d8b2e) | Apr 14, 2022 |
| Clevo         | W54xEU                      | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Dell          | XPS 15 9500                 | [d873b2d218](https://linux-hardware.org/?probe=d873b2d218) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [52d05bca1d](https://linux-hardware.org/?probe=52d05bca1d) | Apr 13, 2022 |
| Dell          | XPS 13 9380                 | [0897999e8d](https://linux-hardware.org/?probe=0897999e8d) | Apr 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [68e6736cd2](https://linux-hardware.org/?probe=68e6736cd2) | Apr 13, 2022 |
| Samsung       | R505                        | [9ff46a8ca6](https://linux-hardware.org/?probe=9ff46a8ca6) | Apr 13, 2022 |
| Dell          | Latitude E5400              | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| IPASON        | MaxBook P1                  | [d66d062f54](https://linux-hardware.org/?probe=d66d062f54) | Apr 05, 2022 |
| Lenovo        | G700 20251                  | [790d42fec8](https://linux-hardware.org/?probe=790d42fec8) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | [d8166d09e9](https://linux-hardware.org/?probe=d8166d09e9) | Mar 30, 2022 |
| HP            | Pavilion dv7                | [112a1842a0](https://linux-hardware.org/?probe=112a1842a0) | Mar 30, 2022 |
| Toshiba       | Satellite L755D             | [d99ccc2771](https://linux-hardware.org/?probe=d99ccc2771) | Mar 28, 2022 |
| Samsung       | R530/R730/R540              | [186f96a5a1](https://linux-hardware.org/?probe=186f96a5a1) | Mar 27, 2022 |
| Acer          | Aspire 3000                 | [8f647a08f9](https://linux-hardware.org/?probe=8f647a08f9) | Mar 26, 2022 |
| Dell          | Studio 1558                 | [7004b83ddf](https://linux-hardware.org/?probe=7004b83ddf) | Mar 23, 2022 |
| Dell          | Vostro 3350                 | [721a0ea932](https://linux-hardware.org/?probe=721a0ea932) | Mar 21, 2022 |
| ASUSTek       | X541UV                      | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| HP            | Pavilion dv7                | [0eb8ef5cd3](https://linux-hardware.org/?probe=0eb8ef5cd3) | Mar 16, 2022 |
| Dell          | Vostro 3401                 | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| Toshiba       | Satellite P755              | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| ASUSTek       | 1011PX                      | [776d052837](https://linux-hardware.org/?probe=776d052837) | Mar 09, 2022 |
| Packard Be... | EasyNote MH35               | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| Lenovo        | U310                        | [856a65502e](https://linux-hardware.org/?probe=856a65502e) | Feb 28, 2022 |
| ASUSTek       | UX305FA                     | [6618b00369](https://linux-hardware.org/?probe=6618b00369) | Feb 28, 2022 |
| Fujitsu       | LIFEBOOK S752               | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| Acer          | Aspire E1-571G              | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| Lenovo        | ThinkPad T460p 20FW000VU... | [9cbb915f78](https://linux-hardware.org/?probe=9cbb915f78) | Feb 18, 2022 |
| ASUSTek       | X553MA                      | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| Notebook      | NK50S5_SZ                   | [c5a3485d32](https://linux-hardware.org/?probe=c5a3485d32) | Feb 11, 2022 |
| HP            | Pavilion 17                 | [3d6c666b77](https://linux-hardware.org/?probe=3d6c666b77) | Feb 08, 2022 |
| HP            | Notebook                    | [69071da574](https://linux-hardware.org/?probe=69071da574) | Feb 06, 2022 |
| Acer          | Aspire 7735                 | [38d97cd9da](https://linux-hardware.org/?probe=38d97cd9da) | Feb 06, 2022 |
| Dell          | XPS 15 9570                 | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Lenovo        | ThinkPad SL500 27463ZG      | [b746a25ff1](https://linux-hardware.org/?probe=b746a25ff1) | Jan 28, 2022 |
| Dell          | Latitude 3410               | [8f2181125e](https://linux-hardware.org/?probe=8f2181125e) | Jan 27, 2022 |
| Sony          | VPCF13Z1R                   | [7aff0d5c29](https://linux-hardware.org/?probe=7aff0d5c29) | Jan 25, 2022 |
| Fujitsu       | LIFEBOOK U748               | [cad36b0eba](https://linux-hardware.org/?probe=cad36b0eba) | Jan 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [37730388fd](https://linux-hardware.org/?probe=37730388fd) | Jan 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [512b021ab8](https://linux-hardware.org/?probe=512b021ab8) | Jan 19, 2022 |
| Lenovo        | V155-15API 81V5             | [09e824f68b](https://linux-hardware.org/?probe=09e824f68b) | Jan 19, 2022 |
| ASUSTek       | X553MA                      | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| Quanta        | TW8/SW8/DW8 TBD             | [8b2f4ffccd](https://linux-hardware.org/?probe=8b2f4ffccd) | Jan 16, 2022 |
| Dell          | XPS 12 9Q23                 | [3c8e26636b](https://linux-hardware.org/?probe=3c8e26636b) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ae80854830](https://linux-hardware.org/?probe=ae80854830) | Jan 15, 2022 |
| Dell          | Latitude E5400              | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| ASUSTek       | X541SA                      | [4103077e59](https://linux-hardware.org/?probe=4103077e59) | Jan 08, 2022 |
| Fujitsu       | LIFEBOOK E746               | [55ac013e1e](https://linux-hardware.org/?probe=55ac013e1e) | Jan 06, 2022 |
| Fujitsu       | LIFEBOOK U748               | [9eb9340d47](https://linux-hardware.org/?probe=9eb9340d47) | Jan 02, 2022 |
| Lenovo        | Flex 2-14 20404             | [1ddb6e11fb](https://linux-hardware.org/?probe=1ddb6e11fb) | Jan 01, 2022 |
| Acer          | Aspire A515-43              | [82163f143b](https://linux-hardware.org/?probe=82163f143b) | Dec 29, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| Lenovo        | U310                        | [fa57a69141](https://linux-hardware.org/?probe=fa57a69141) | Dec 24, 2021 |
| HP            | Pavilion dv4                | [7152c2fcd9](https://linux-hardware.org/?probe=7152c2fcd9) | Dec 22, 2021 |
| Lenovo        | G580 2189                   | [843f8c04fe](https://linux-hardware.org/?probe=843f8c04fe) | Dec 21, 2021 |
| HP            | ENVY Notebook               | [69b60fabe0](https://linux-hardware.org/?probe=69b60fabe0) | Dec 15, 2021 |
| Acer          | Aspire ES1-523              | [66a8186276](https://linux-hardware.org/?probe=66a8186276) | Dec 15, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | [6d50094df0](https://linux-hardware.org/?probe=6d50094df0) | Dec 11, 2021 |
| Quanta        | TW8/SW8/DW8 TBD             | [43f645de28](https://linux-hardware.org/?probe=43f645de28) | Dec 11, 2021 |
| Unknown       | Unknown                     | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| ASUSTek       | X751BP                      | [e1acc83725](https://linux-hardware.org/?probe=e1acc83725) | Dec 06, 2021 |
| HP            | EliteBook Folio 9480m       | [2cd39490da](https://linux-hardware.org/?probe=2cd39490da) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Dell          | Latitude E6400              | [170f397883](https://linux-hardware.org/?probe=170f397883) | Dec 02, 2021 |
| HP            | EliteBook Folio 9480m       | [3b06bfa748](https://linux-hardware.org/?probe=3b06bfa748) | Dec 01, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [5f2264a472](https://linux-hardware.org/?probe=5f2264a472) | Nov 30, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| Polaroid      | MP1464PR001                 | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| HP            | EliteBook Folio 9480m       | [8b5c3b008f](https://linux-hardware.org/?probe=8b5c3b008f) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | [bf8ac4dc12](https://linux-hardware.org/?probe=bf8ac4dc12) | Nov 24, 2021 |
| Lenovo        | G580 20157                  | [bb170a308c](https://linux-hardware.org/?probe=bb170a308c) | Nov 24, 2021 |
| Dell          | Precision 5560              | [aa3dbdc6bb](https://linux-hardware.org/?probe=aa3dbdc6bb) | Nov 22, 2021 |
| Acer          | TravelMate 5720             | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| HP            | ZBook Fury 17.3 inch G8 ... | [63f392ea8b](https://linux-hardware.org/?probe=63f392ea8b) | Nov 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [3ddad52d21](https://linux-hardware.org/?probe=3ddad52d21) | Nov 16, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [162531d482](https://linux-hardware.org/?probe=162531d482) | Nov 16, 2021 |
| Dell          | Vostro 5568                 | [403ef45f63](https://linux-hardware.org/?probe=403ef45f63) | Nov 15, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | [e881f41269](https://linux-hardware.org/?probe=e881f41269) | Nov 14, 2021 |
| Dell          | Latitude E6410              | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| AMI           | Unknown                     | [d1cd5b09e1](https://linux-hardware.org/?probe=d1cd5b09e1) | Nov 12, 2021 |
| Toshiba       | Satellite C665              | [a136cdd51d](https://linux-hardware.org/?probe=a136cdd51d) | Nov 11, 2021 |
| HP            | ZBook 15                    | [835fb0e921](https://linux-hardware.org/?probe=835fb0e921) | Nov 10, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c8b67f9143](https://linux-hardware.org/?probe=c8b67f9143) | Nov 08, 2021 |
| GPD           | P2 MAX                      | [9adb3fd2eb](https://linux-hardware.org/?probe=9adb3fd2eb) | Nov 02, 2021 |
| AZW           | SEi                         | [6d9a86e769](https://linux-hardware.org/?probe=6d9a86e769) | Nov 02, 2021 |
| MSI           | GE76 Raider 11UG            | [cbbe604f22](https://linux-hardware.org/?probe=cbbe604f22) | Nov 01, 2021 |
| Acer          | Aspire 7750G                | [7eaeae034c](https://linux-hardware.org/?probe=7eaeae034c) | Oct 29, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [10e9f4b604](https://linux-hardware.org/?probe=10e9f4b604) | Oct 27, 2021 |
| Dell          | Precision 7520              | [83df635945](https://linux-hardware.org/?probe=83df635945) | Oct 26, 2021 |
| HP            | Pavilion Notebook           | [cd2454732b](https://linux-hardware.org/?probe=cd2454732b) | Oct 25, 2021 |
| HP            | G70                         | [68fb8430c2](https://linux-hardware.org/?probe=68fb8430c2) | Oct 24, 2021 |
| HP            | G70                         | [3e2c50a321](https://linux-hardware.org/?probe=3e2c50a321) | Oct 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [e82ee9096e](https://linux-hardware.org/?probe=e82ee9096e) | Oct 23, 2021 |
| ASUSTek       | N53SM                       | [3e15c8708a](https://linux-hardware.org/?probe=3e15c8708a) | Oct 23, 2021 |
| Lenovo        | ThinkPad L512 2598A59       | [0bc832bd49](https://linux-hardware.org/?probe=0bc832bd49) | Oct 19, 2021 |
| Notebook      | P17SM-A                     | [34a5253469](https://linux-hardware.org/?probe=34a5253469) | Oct 16, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | [2bc2b5c1d6](https://linux-hardware.org/?probe=2bc2b5c1d6) | Oct 15, 2021 |
| Notebook      | P17SM-A                     | [b4660289b3](https://linux-hardware.org/?probe=b4660289b3) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [36f407c3aa](https://linux-hardware.org/?probe=36f407c3aa) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [1b3b80e104](https://linux-hardware.org/?probe=1b3b80e104) | Oct 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| Dell          | Latitude E6440              | [383edb4c99](https://linux-hardware.org/?probe=383edb4c99) | Oct 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6c0867e544](https://linux-hardware.org/?probe=6c0867e544) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [b566b7f862](https://linux-hardware.org/?probe=b566b7f862) | Oct 13, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [a8e5248d3d](https://linux-hardware.org/?probe=a8e5248d3d) | Oct 13, 2021 |
| ASUSTek       | U36SD                       | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [26453872b1](https://linux-hardware.org/?probe=26453872b1) | Oct 12, 2021 |
| ASUSTek       | N43SL                       | [c5adc8860e](https://linux-hardware.org/?probe=c5adc8860e) | Oct 09, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [044c6efa0d](https://linux-hardware.org/?probe=044c6efa0d) | Oct 08, 2021 |
| Lenovo        | Z51-70 80K6                 | [219e5cd0d5](https://linux-hardware.org/?probe=219e5cd0d5) | Oct 04, 2021 |
| Dell          | Latitude E6440              | [a8884539e7](https://linux-hardware.org/?probe=a8884539e7) | Oct 02, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [b535b99341](https://linux-hardware.org/?probe=b535b99341) | Sep 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [f04c751d60](https://linux-hardware.org/?probe=f04c751d60) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Dell          | Vostro 3350                 | [384af306e6](https://linux-hardware.org/?probe=384af306e6) | Sep 27, 2021 |
| HP            | Laptop 15-db0xxx            | [ed937ed1cd](https://linux-hardware.org/?probe=ed937ed1cd) | Sep 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [2e1581c3b3](https://linux-hardware.org/?probe=2e1581c3b3) | Sep 24, 2021 |
| Entroware     | Aether                      | [c65a69857f](https://linux-hardware.org/?probe=c65a69857f) | Sep 22, 2021 |
| Acer          | Aspire A515-43              | [523fe48a54](https://linux-hardware.org/?probe=523fe48a54) | Sep 19, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | [6e8ca97f4b](https://linux-hardware.org/?probe=6e8ca97f4b) | Sep 14, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | [e0b0d2d509](https://linux-hardware.org/?probe=e0b0d2d509) | Sep 13, 2021 |
| Teclast       | F15S                        | [b6fcd1a34d](https://linux-hardware.org/?probe=b6fcd1a34d) | Sep 13, 2021 |
| Teclast       | F15S                        | [93d4fafebd](https://linux-hardware.org/?probe=93d4fafebd) | Sep 13, 2021 |
| Lenovo        | ThinkPad T420 42361P0       | [24f3d09047](https://linux-hardware.org/?probe=24f3d09047) | Sep 13, 2021 |
| Unknown       | Unknown                     | [6670bba1d8](https://linux-hardware.org/?probe=6670bba1d8) | Sep 13, 2021 |
| Dell          | Vostro 3350                 | [0fdc4bc08a](https://linux-hardware.org/?probe=0fdc4bc08a) | Sep 13, 2021 |
| Dell          | Latitude E7450              | [012bae3aa2](https://linux-hardware.org/?probe=012bae3aa2) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Digibras      | NH4CU53                     | [5f2f500f7a](https://linux-hardware.org/?probe=5f2f500f7a) | Sep 10, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | [d05cb87743](https://linux-hardware.org/?probe=d05cb87743) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | [54c321b6bd](https://linux-hardware.org/?probe=54c321b6bd) | Sep 04, 2021 |
| Lenovo        | ThinkPad T440p 20AN006DU... | [812cc9220c](https://linux-hardware.org/?probe=812cc9220c) | Sep 01, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [5ee9ab86d7](https://linux-hardware.org/?probe=5ee9ab86d7) | Aug 31, 2021 |
| Notebook      | NK50S5_SZ                   | [6cba599e57](https://linux-hardware.org/?probe=6cba599e57) | Aug 27, 2021 |
| Packard Be... | EasyNote SL65               | [934368dd02](https://linux-hardware.org/?probe=934368dd02) | Aug 20, 2021 |
| GPD           | MicroPC                     | [7fa0c4e3c4](https://linux-hardware.org/?probe=7fa0c4e3c4) | Aug 20, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| ASUSTek       | X556UAK                     | [70e369f2ba](https://linux-hardware.org/?probe=70e369f2ba) | Aug 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [635d8e55e7](https://linux-hardware.org/?probe=635d8e55e7) | Aug 17, 2021 |
| HP            | ProBook 445 G7              | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| Acer          | Extensa 5630                | [f32dfbfe2a](https://linux-hardware.org/?probe=f32dfbfe2a) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| Chuwi         | GemiBook Pro                | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [cfe37f86a3](https://linux-hardware.org/?probe=cfe37f86a3) | Aug 12, 2021 |
| Dell          | Latitude E6410              | [976f7c253c](https://linux-hardware.org/?probe=976f7c253c) | Aug 07, 2021 |
| ASUSTek       | X556UAK                     | [399d9ceec5](https://linux-hardware.org/?probe=399d9ceec5) | Aug 06, 2021 |
| Intel         | AMI                         | [c11ff5c3a9](https://linux-hardware.org/?probe=c11ff5c3a9) | Aug 06, 2021 |
| Intel         | AMI                         | [bfe9befd10](https://linux-hardware.org/?probe=bfe9befd10) | Aug 05, 2021 |
| Notebook      | N24_25GU                    | [2e67e53ad7](https://linux-hardware.org/?probe=2e67e53ad7) | Aug 05, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Dell          | Vostro 1520                 | [af01145277](https://linux-hardware.org/?probe=af01145277) | Jul 28, 2021 |
| Clevo         | M720R                       | [a52f0f2d7c](https://linux-hardware.org/?probe=a52f0f2d7c) | Jul 27, 2021 |
| Acer          | Aspire E1-571               | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| HP            | Laptop 15z-ef1xxx           | [d72c30940e](https://linux-hardware.org/?probe=d72c30940e) | Jul 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [49be4c6d59](https://linux-hardware.org/?probe=49be4c6d59) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| HP            | ProBook 450 G3              | [8b355a2630](https://linux-hardware.org/?probe=8b355a2630) | Jul 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| System76      | Galago Pro                  | [c74e5f1cf9](https://linux-hardware.org/?probe=c74e5f1cf9) | Jul 17, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [14ce128e1a](https://linux-hardware.org/?probe=14ce128e1a) | Jul 16, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f656b6c149](https://linux-hardware.org/?probe=f656b6c149) | Jul 16, 2021 |
| Dell          | Studio 1558                 | [d1fad8f698](https://linux-hardware.org/?probe=d1fad8f698) | Jul 16, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| Toshiba       | Satellite C850-BMK          | [d92515e12e](https://linux-hardware.org/?probe=d92515e12e) | Jul 14, 2021 |
| HP            | Pavilion 17                 | [628e42055f](https://linux-hardware.org/?probe=628e42055f) | Jul 12, 2021 |
| FUJITSU CL... | LIFEBOOK E5511              | [4c13b21a8c](https://linux-hardware.org/?probe=4c13b21a8c) | Jul 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [cce6c3a767](https://linux-hardware.org/?probe=cce6c3a767) | Jul 06, 2021 |
| HP            | Laptop 15-db0xxx            | [b6c1f36f1f](https://linux-hardware.org/?probe=b6c1f36f1f) | Jul 04, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| Dell          | Inspiron 3505               | [820725cbbd](https://linux-hardware.org/?probe=820725cbbd) | Jun 30, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [90235ac63a](https://linux-hardware.org/?probe=90235ac63a) | Jun 30, 2021 |
| Notebook      | P17SM-A                     | [dcf91492a2](https://linux-hardware.org/?probe=dcf91492a2) | Jun 29, 2021 |
| HP            | Pavilion g6                 | [3cfb1f50dc](https://linux-hardware.org/?probe=3cfb1f50dc) | Jun 26, 2021 |
| HP            | EliteBook 2560p             | [4b13ffc6ce](https://linux-hardware.org/?probe=4b13ffc6ce) | Jun 26, 2021 |
| HP            | EliteBook 2170p             | [212819389c](https://linux-hardware.org/?probe=212819389c) | Jun 25, 2021 |
| HP            | EliteBook 2560p             | [4fdc27b018](https://linux-hardware.org/?probe=4fdc27b018) | Jun 25, 2021 |
| HP            | Pavilion dv7                | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| Acer          | V7-710                      | [fe9a84f137](https://linux-hardware.org/?probe=fe9a84f137) | Jun 23, 2021 |
| Dell          | Latitude E6400              | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| HP            | ProBook 430 G6              | [7bf43ae0d0](https://linux-hardware.org/?probe=7bf43ae0d0) | Jun 19, 2021 |
| HP            | ProBook 430 G6              | [9a4e288f49](https://linux-hardware.org/?probe=9a4e288f49) | Jun 19, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [32538ae4b8](https://linux-hardware.org/?probe=32538ae4b8) | Jun 17, 2021 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [882855d037](https://linux-hardware.org/?probe=882855d037) | Jun 17, 2021 |
| Dell          | Latitude D520               | [5f08e309ae](https://linux-hardware.org/?probe=5f08e309ae) | Jun 11, 2021 |
| Dell          | Latitude E6510              | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| Acer          | Aspire 7730G                | [4d314b5039](https://linux-hardware.org/?probe=4d314b5039) | Jun 10, 2021 |
| HP            | Pavilion 17                 | [b234c99d47](https://linux-hardware.org/?probe=b234c99d47) | Jun 08, 2021 |
| ASUSTek       | K73SJ                       | [cb0f042995](https://linux-hardware.org/?probe=cb0f042995) | Jun 04, 2021 |
| Dell          | Latitude 7420               | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| HP            | ProBook 450 G6              | [af16143ad8](https://linux-hardware.org/?probe=af16143ad8) | Jun 03, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| HP            | Pavilion g6                 | [0245da9040](https://linux-hardware.org/?probe=0245da9040) | May 31, 2021 |
| Toshiba       | Satellite A200              | [8e44c9edaf](https://linux-hardware.org/?probe=8e44c9edaf) | May 26, 2021 |
| Toshiba       | Satellite A200              | [3a2f765228](https://linux-hardware.org/?probe=3a2f765228) | May 26, 2021 |
| HP            | Pavilion                    | [1fa0cb66b1](https://linux-hardware.org/?probe=1fa0cb66b1) | May 26, 2021 |
| HP            | 635                         | [acff9705ee](https://linux-hardware.org/?probe=acff9705ee) | May 26, 2021 |
| Dell          | G7 7500                     | [65cb46fe46](https://linux-hardware.org/?probe=65cb46fe46) | May 25, 2021 |
| HP            | 635                         | [b96dfdc2fa](https://linux-hardware.org/?probe=b96dfdc2fa) | May 24, 2021 |
| GPD           | MicroPC                     | [2b5550e67e](https://linux-hardware.org/?probe=2b5550e67e) | May 24, 2021 |
| Dell          | Precision M4800             | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Dell          | Precision M4800             | [fd49c10a9f](https://linux-hardware.org/?probe=fd49c10a9f) | May 24, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [ea47dfa580](https://linux-hardware.org/?probe=ea47dfa580) | May 13, 2021 |
| Notebook      | P17SM-A                     | [e39d859a43](https://linux-hardware.org/?probe=e39d859a43) | May 12, 2021 |
| LG Electro... | S460-G.BG31P1               | [6b07e6e09b](https://linux-hardware.org/?probe=6b07e6e09b) | May 12, 2021 |
| Notebook      | P17SM-A                     | [2a8297469f](https://linux-hardware.org/?probe=2a8297469f) | May 11, 2021 |
| Dell          | Precision M4500             | [407d9c0748](https://linux-hardware.org/?probe=407d9c0748) | May 10, 2021 |
| Dell          | G7 7588                     | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | [d0fb43caf0](https://linux-hardware.org/?probe=d0fb43caf0) | May 08, 2021 |
| HP            | Pavilion                    | [ade11f7a65](https://linux-hardware.org/?probe=ade11f7a65) | May 08, 2021 |
| HP            | Pavilion 17                 | [32ea31fd5f](https://linux-hardware.org/?probe=32ea31fd5f) | May 07, 2021 |
| Cube          | i18-L                       | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| HP            | Pavilion                    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |
| HP            | EliteBook 840 G5            | [1eea89f8bb](https://linux-hardware.org/?probe=1eea89f8bb) | May 03, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| HP            | Pavilion 17                 | [7bb6b560e5](https://linux-hardware.org/?probe=7bb6b560e5) | Apr 29, 2021 |
| Dell          | G7 7588                     | [1393a855bb](https://linux-hardware.org/?probe=1393a855bb) | Apr 25, 2021 |
| GPD           | MicroPC                     | [1169a84e36](https://linux-hardware.org/?probe=1169a84e36) | Apr 24, 2021 |
| ONE-NETBOO... | A1                          | [86c38b0aca](https://linux-hardware.org/?probe=86c38b0aca) | Apr 23, 2021 |
| HP            | Pavilion 17                 | [b5353a5537](https://linux-hardware.org/?probe=b5353a5537) | Apr 22, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3835eff7c6](https://linux-hardware.org/?probe=3835eff7c6) | Apr 21, 2021 |
| HP            | Pavilion 17                 | [eb45979ba4](https://linux-hardware.org/?probe=eb45979ba4) | Apr 19, 2021 |
| Dell          | Vostro 1014                 | [84a1787483](https://linux-hardware.org/?probe=84a1787483) | Apr 18, 2021 |
| Packard Be... | EasyNote SB87               | [342ca9babb](https://linux-hardware.org/?probe=342ca9babb) | Apr 15, 2021 |
| Dell          | Inspiron 3480               | [75f43079fb](https://linux-hardware.org/?probe=75f43079fb) | Apr 13, 2021 |
| Dell          | Inspiron 3480               | [dce5f8220a](https://linux-hardware.org/?probe=dce5f8220a) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fb0db0afbd](https://linux-hardware.org/?probe=fb0db0afbd) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [236be7c7e7](https://linux-hardware.org/?probe=236be7c7e7) | Apr 12, 2021 |
| HP            | ProBook 450 G3              | [37502c4abe](https://linux-hardware.org/?probe=37502c4abe) | Apr 12, 2021 |
| HP            | ProBook 450 G3              | [416997431c](https://linux-hardware.org/?probe=416997431c) | Apr 11, 2021 |
| Dell          | Latitude E6410              | [9fc394df40](https://linux-hardware.org/?probe=9fc394df40) | Apr 10, 2021 |
| HP            | Stream Laptop 14-cb0XX      | [a0e1e8da67](https://linux-hardware.org/?probe=a0e1e8da67) | Apr 10, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [33f5b55ba6](https://linux-hardware.org/?probe=33f5b55ba6) | Apr 09, 2021 |
| HP            | Pavilion dv6                | [bf634bb665](https://linux-hardware.org/?probe=bf634bb665) | Apr 09, 2021 |
| HP            | 15                          | [acc9ccddfa](https://linux-hardware.org/?probe=acc9ccddfa) | Apr 08, 2021 |
| HP            | ProBook 4530s               | [91397a0024](https://linux-hardware.org/?probe=91397a0024) | Apr 07, 2021 |
| HP            | ProBook 4530s               | [12a7784eb4](https://linux-hardware.org/?probe=12a7784eb4) | Apr 06, 2021 |
| Dell          | Precision 5550              | [fb83e2c0e0](https://linux-hardware.org/?probe=fb83e2c0e0) | Apr 04, 2021 |
| Dell          | Precision 5550              | [bf3982f88a](https://linux-hardware.org/?probe=bf3982f88a) | Apr 04, 2021 |
| Dell          | Latitude E6410              | [297aaeb4ac](https://linux-hardware.org/?probe=297aaeb4ac) | Apr 03, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fa8acecaa2](https://linux-hardware.org/?probe=fa8acecaa2) | Apr 01, 2021 |
| Dell          | Latitude E7250              | [d88e8eb416](https://linux-hardware.org/?probe=d88e8eb416) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| Dell          | Latitude 7310               | [9f4c2f64a5](https://linux-hardware.org/?probe=9f4c2f64a5) | Mar 30, 2021 |
| Digibras      | NH4CU53                     | [2140003dfe](https://linux-hardware.org/?probe=2140003dfe) | Mar 28, 2021 |
| Digibras      | NH4CU53                     | [f0cd6ca6b4](https://linux-hardware.org/?probe=f0cd6ca6b4) | Mar 28, 2021 |
| Dell          | Latitude E7250              | [d1716d96f2](https://linux-hardware.org/?probe=d1716d96f2) | Mar 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [dc5e67af5a](https://linux-hardware.org/?probe=dc5e67af5a) | Mar 27, 2021 |
| Digibras      | NH4CU53                     | [9c97295bbf](https://linux-hardware.org/?probe=9c97295bbf) | Mar 27, 2021 |
| Digibras      | NH4CU53                     | [da93e6d427](https://linux-hardware.org/?probe=da93e6d427) | Mar 27, 2021 |
| Metabox       | X170SM                      | [eb5af1bbd3](https://linux-hardware.org/?probe=eb5af1bbd3) | Mar 26, 2021 |
| Metabox       | X170SM                      | [544b6cd3d5](https://linux-hardware.org/?probe=544b6cd3d5) | Mar 26, 2021 |
| Acer          | Aspire 4740                 | [3551944dd9](https://linux-hardware.org/?probe=3551944dd9) | Mar 25, 2021 |
| Samsung       | 760XBE                      | [3cacabef7b](https://linux-hardware.org/?probe=3cacabef7b) | Mar 23, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [92bcacad15](https://linux-hardware.org/?probe=92bcacad15) | Mar 22, 2021 |
| Dell          | Latitude E6540              | [fe1f341842](https://linux-hardware.org/?probe=fe1f341842) | Mar 21, 2021 |
| Samsung       | 760XBE                      | [26e28d0645](https://linux-hardware.org/?probe=26e28d0645) | Mar 21, 2021 |
| ASUSTek       | K50IE                       | [cc01498ee9](https://linux-hardware.org/?probe=cc01498ee9) | Mar 18, 2021 |
| MSI           | GF63 Thin 9SCSR             | [f58ddcc3f4](https://linux-hardware.org/?probe=f58ddcc3f4) | Mar 17, 2021 |
| Acer          | Aspire A515-56              | [1919b6a57f](https://linux-hardware.org/?probe=1919b6a57f) | Mar 17, 2021 |
| Sony          | VPCEB1S1E                   | [51c687be6f](https://linux-hardware.org/?probe=51c687be6f) | Mar 12, 2021 |
| Sony          | VPCEB1S1E                   | [528d0ef3a5](https://linux-hardware.org/?probe=528d0ef3a5) | Mar 12, 2021 |
| HP            | Pavilion 17                 | [c74bd609b2](https://linux-hardware.org/?probe=c74bd609b2) | Mar 10, 2021 |
| Sony          | VGN-FZ4000E                 | [fabf3e783d](https://linux-hardware.org/?probe=fabf3e783d) | Mar 07, 2021 |
| ASUSTek       | Z450LA                      | [7bd4f23045](https://linux-hardware.org/?probe=7bd4f23045) | Mar 05, 2021 |
| HP            | Pavilion g7                 | [cc361e0dbf](https://linux-hardware.org/?probe=cc361e0dbf) | Mar 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [efdf3f9098](https://linux-hardware.org/?probe=efdf3f9098) | Mar 02, 2021 |
| Toshiba       | Satellite L350D             | [0286dc8c95](https://linux-hardware.org/?probe=0286dc8c95) | Mar 02, 2021 |
| HP            | Pavilion g7                 | [6d79297a65](https://linux-hardware.org/?probe=6d79297a65) | Feb 26, 2021 |
| HP            | Pavilion g7                 | [41d55a3dd7](https://linux-hardware.org/?probe=41d55a3dd7) | Feb 26, 2021 |
| Lenovo        | ThinkPad W530 24491E8       | [fcf9d9a8d2](https://linux-hardware.org/?probe=fcf9d9a8d2) | Feb 25, 2021 |
| Entroware     | Aether                      | [9e308b1fda](https://linux-hardware.org/?probe=9e308b1fda) | Feb 24, 2021 |
| Dell          | Precision M4800             | [45c92f0ad1](https://linux-hardware.org/?probe=45c92f0ad1) | Feb 22, 2021 |
| HP            | HDX 16                      | [214dc69b28](https://linux-hardware.org/?probe=214dc69b28) | Feb 22, 2021 |
| HP            | Pavilion 17                 | [46033bbdfd](https://linux-hardware.org/?probe=46033bbdfd) | Feb 17, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5bd6c548d2](https://linux-hardware.org/?probe=5bd6c548d2) | Feb 15, 2021 |
| Positivo      | N8X0EK1                     | [c6ac8d6eca](https://linux-hardware.org/?probe=c6ac8d6eca) | Feb 15, 2021 |
| HP            | Unknown                     | [46be5bd9f4](https://linux-hardware.org/?probe=46be5bd9f4) | Feb 12, 2021 |
| Dell          | Latitude E6500              | [75d199bcfd](https://linux-hardware.org/?probe=75d199bcfd) | Feb 12, 2021 |
| Dell          | Latitude E6500              | [200b4ad049](https://linux-hardware.org/?probe=200b4ad049) | Feb 11, 2021 |
| Dell          | Studio 1747                 | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | [952ca96633](https://linux-hardware.org/?probe=952ca96633) | Feb 09, 2021 |
| Notebook      | W310CZ/CZ-T                 | [2b60fc9e91](https://linux-hardware.org/?probe=2b60fc9e91) | Feb 09, 2021 |
| Lenovo        | U310                        | [8e7c82ea87](https://linux-hardware.org/?probe=8e7c82ea87) | Feb 08, 2021 |
| HP            | Unknown                     | [34a482168b](https://linux-hardware.org/?probe=34a482168b) | Feb 08, 2021 |
| Dell          | Latitude E7250              | [2679c5b467](https://linux-hardware.org/?probe=2679c5b467) | Feb 05, 2021 |
| Sony          | VGN-FE41M                   | [c51a776cc5](https://linux-hardware.org/?probe=c51a776cc5) | Feb 02, 2021 |
| Dell          | Latitude E7250              | [1a682cd31e](https://linux-hardware.org/?probe=1a682cd31e) | Feb 02, 2021 |
| Acer          | Aspire ES1-521              | [73b3295031](https://linux-hardware.org/?probe=73b3295031) | Jan 29, 2021 |
| Dell          | Studio 1558                 | [db4ff98658](https://linux-hardware.org/?probe=db4ff98658) | Jan 29, 2021 |
| Dell          | G7 7588                     | [ae6d47978a](https://linux-hardware.org/?probe=ae6d47978a) | Jan 28, 2021 |
| Dell          | G7 7588                     | [1006977f89](https://linux-hardware.org/?probe=1006977f89) | Jan 28, 2021 |
| Unknown       | Unknown                     | [94630b8af9](https://linux-hardware.org/?probe=94630b8af9) | Jan 27, 2021 |
| Unknown       | Unknown                     | [a552c57de7](https://linux-hardware.org/?probe=a552c57de7) | Jan 27, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [4cae7dc78d](https://linux-hardware.org/?probe=4cae7dc78d) | Jan 18, 2021 |
| Lenovo        | IdeaPad Z585 20152          | [b340b7b3aa](https://linux-hardware.org/?probe=b340b7b3aa) | Jan 17, 2021 |
| HP            | 250 G5 Notebook PC          | [f2e3b573f5](https://linux-hardware.org/?probe=f2e3b573f5) | Jan 16, 2021 |
| Lenovo        | G580 20150                  | [cdc7ca6b9f](https://linux-hardware.org/?probe=cdc7ca6b9f) | Jan 15, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [e8b3cf2cbd](https://linux-hardware.org/?probe=e8b3cf2cbd) | Jan 14, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [8117aff9b0](https://linux-hardware.org/?probe=8117aff9b0) | Jan 14, 2021 |
| Medion        | X682X                       | [bf7dbceaa3](https://linux-hardware.org/?probe=bf7dbceaa3) | Jan 13, 2021 |
| HP            | G7000                       | [fe00d6ee90](https://linux-hardware.org/?probe=fe00d6ee90) | Jan 08, 2021 |
| Dell          | XPS 13 9370                 | [1b3b03be98](https://linux-hardware.org/?probe=1b3b03be98) | Jan 07, 2021 |
| HP            | 255 G7 Notebook PC          | [4f385a65db](https://linux-hardware.org/?probe=4f385a65db) | Jan 03, 2021 |
| Samsung       | SR58P                       | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [e253bc608d](https://linux-hardware.org/?probe=e253bc608d) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1483935c23](https://linux-hardware.org/?probe=1483935c23) | Jan 02, 2021 |
| Fujitsu       | LIFEBOOK N532               | [500590cde7](https://linux-hardware.org/?probe=500590cde7) | Jan 02, 2021 |
| Acer          | Aspire E1-532P              | [a1f1287741](https://linux-hardware.org/?probe=a1f1287741) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [30041ef295](https://linux-hardware.org/?probe=30041ef295) | Jan 01, 2021 |
| HP            | Pavilion dv5                | [09608c77d8](https://linux-hardware.org/?probe=09608c77d8) | Dec 31, 2020 |
| Wortmann      | MOBILE 1745                 | [17db63ebf8](https://linux-hardware.org/?probe=17db63ebf8) | Dec 30, 2020 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| ASUSTek       | UX430UAR                    | [8ba49d83a9](https://linux-hardware.org/?probe=8ba49d83a9) | Dec 29, 2020 |
| HP            | Notebook                    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA32VLM    | [cfa92bb7f3](https://linux-hardware.org/?probe=cfa92bb7f3) | Dec 28, 2020 |
| ASUSTek       | X302LA                      | [f5dde37fb9](https://linux-hardware.org/?probe=f5dde37fb9) | Dec 26, 2020 |
| ASUSTek       | X302LA                      | [a35e9f4b28](https://linux-hardware.org/?probe=a35e9f4b28) | Dec 25, 2020 |
| MSI           | GS73 Stealth 8RD            | [b1feda0218](https://linux-hardware.org/?probe=b1feda0218) | Dec 24, 2020 |
| Hannspree     | SN10E100                    | [68af65ef96](https://linux-hardware.org/?probe=68af65ef96) | Dec 24, 2020 |
| ASUSTek       | P50IJ                       | [198588084c](https://linux-hardware.org/?probe=198588084c) | Dec 21, 2020 |
| Dell          | Inspiron 5379               | [908bfee94d](https://linux-hardware.org/?probe=908bfee94d) | Dec 20, 2020 |
| Star Labs     | LabTop                      | [b8c8467e92](https://linux-hardware.org/?probe=b8c8467e92) | Dec 20, 2020 |
| Dell          | XPS 13 9310                 | [f36fe4dd36](https://linux-hardware.org/?probe=f36fe4dd36) | Dec 12, 2020 |
| Dell          | Latitude E6500              | [c12a3f1830](https://linux-hardware.org/?probe=c12a3f1830) | Dec 11, 2020 |
| Toshiba       | Satellite Pro L500          | [d01d9e0d34](https://linux-hardware.org/?probe=d01d9e0d34) | Dec 08, 2020 |
| Lenovo        | ThinkPad X220 429035U       | [94851319ac](https://linux-hardware.org/?probe=94851319ac) | Dec 08, 2020 |
| Dell          | Inspiron 3520               | [be6f5d9f85](https://linux-hardware.org/?probe=be6f5d9f85) | Dec 07, 2020 |
| Acer          | Nitro AN515-54              | [b8cc3d9c2e](https://linux-hardware.org/?probe=b8cc3d9c2e) | Dec 07, 2020 |
| Dell          | Latitude D630               | [475177f3da](https://linux-hardware.org/?probe=475177f3da) | Dec 07, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [5862508036](https://linux-hardware.org/?probe=5862508036) | Dec 06, 2020 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [d4c5036cd3](https://linux-hardware.org/?probe=d4c5036cd3) | Dec 04, 2020 |
| HP            | Pavilion 17                 | [2f04deaf4e](https://linux-hardware.org/?probe=2f04deaf4e) | Dec 03, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [ee0aa7b52f](https://linux-hardware.org/?probe=ee0aa7b52f) | Dec 02, 2020 |
| Dell          | Precision 7710              | [f017e7a0d2](https://linux-hardware.org/?probe=f017e7a0d2) | Nov 30, 2020 |
| ASUSTek       | S550CM                      | [3a186d2a85](https://linux-hardware.org/?probe=3a186d2a85) | Nov 30, 2020 |
| Positivo      | C14RV01                     | [a5d087470e](https://linux-hardware.org/?probe=a5d087470e) | Nov 29, 2020 |
| Acer          | Aspire E5-523               | [cfd9403111](https://linux-hardware.org/?probe=cfd9403111) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Dell          | Latitude E6400              | [a39e2e7fa3](https://linux-hardware.org/?probe=a39e2e7fa3) | Nov 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [19118ea389](https://linux-hardware.org/?probe=19118ea389) | Nov 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [0429ace281](https://linux-hardware.org/?probe=0429ace281) | Nov 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [833a22d4ee](https://linux-hardware.org/?probe=833a22d4ee) | Nov 20, 2020 |
| Dell          | G5 5590                     | [007ad64378](https://linux-hardware.org/?probe=007ad64378) | Nov 20, 2020 |
| Dell          | Latitude E5420              | [dd15ed0da0](https://linux-hardware.org/?probe=dd15ed0da0) | Nov 19, 2020 |
| MSI           | GE75 Raider 10SGS           | [025deb9bbe](https://linux-hardware.org/?probe=025deb9bbe) | Nov 19, 2020 |
| Dell          | G5 5590                     | [e82ed4c1d0](https://linux-hardware.org/?probe=e82ed4c1d0) | Nov 19, 2020 |
| HP            | EliteBook 830 G6            | [c47a2f5f86](https://linux-hardware.org/?probe=c47a2f5f86) | Nov 18, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | [08c8440950](https://linux-hardware.org/?probe=08c8440950) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [968f302807](https://linux-hardware.org/?probe=968f302807) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [2a9231cde8](https://linux-hardware.org/?probe=2a9231cde8) | Nov 17, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [b8e7eedfed](https://linux-hardware.org/?probe=b8e7eedfed) | Nov 17, 2020 |
| Dell          | Latitude E6420              | [3452613a4c](https://linux-hardware.org/?probe=3452613a4c) | Nov 16, 2020 |
| Lenovo        | ThinkPad T490 20N20031US    | [647de7adc7](https://linux-hardware.org/?probe=647de7adc7) | Nov 14, 2020 |
| HP            | 255 G7 Notebook PC          | [153a36bfa0](https://linux-hardware.org/?probe=153a36bfa0) | Nov 14, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | EliteBook Folio 9470m       | [659c1c8745](https://linux-hardware.org/?probe=659c1c8745) | Nov 06, 2020 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [41774e6905](https://linux-hardware.org/?probe=41774e6905) | Nov 06, 2020 |
| HP            | EliteBook 8560w             | [8393d44a56](https://linux-hardware.org/?probe=8393d44a56) | Nov 06, 2020 |
| HP            | EliteBook Folio 9470m       | [248ce84271](https://linux-hardware.org/?probe=248ce84271) | Nov 05, 2020 |
| Dell          | Latitude E6420              | [6cdd815251](https://linux-hardware.org/?probe=6cdd815251) | Nov 04, 2020 |
| Dell          | Latitude E6420              | [10d44f2853](https://linux-hardware.org/?probe=10d44f2853) | Nov 04, 2020 |
| HP            | Pavilion g6                 | [582220fb2f](https://linux-hardware.org/?probe=582220fb2f) | Nov 04, 2020 |
| Acer          | Aspire A314-32              | [686d0b8c4f](https://linux-hardware.org/?probe=686d0b8c4f) | Nov 03, 2020 |
| Dell          | Latitude E6430              | [39ba29b6a3](https://linux-hardware.org/?probe=39ba29b6a3) | Nov 02, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [d9a9dae79a](https://linux-hardware.org/?probe=d9a9dae79a) | Oct 31, 2020 |
| Lenovo        | ThinkPad E520 1143B5G       | [146fc730d7](https://linux-hardware.org/?probe=146fc730d7) | Oct 29, 2020 |
| MSI           | GE72 7RE                    | [f75b251f96](https://linux-hardware.org/?probe=f75b251f96) | Oct 29, 2020 |
| MSI           | GE72 7RE                    | [1a787f6e31](https://linux-hardware.org/?probe=1a787f6e31) | Oct 28, 2020 |
| Acer          | Aspire 5715Z                | [a2fca6b9da](https://linux-hardware.org/?probe=a2fca6b9da) | Oct 26, 2020 |
| Lenovo        | V570 HuronRiver Platform    | [62082c183e](https://linux-hardware.org/?probe=62082c183e) | Oct 26, 2020 |
| ASUSTek       | X751LK                      | [0dad6a22c5](https://linux-hardware.org/?probe=0dad6a22c5) | Oct 26, 2020 |
| HP            | Pavilion dv7                | [59e2fce913](https://linux-hardware.org/?probe=59e2fce913) | Oct 26, 2020 |
| Dell          | Precision M4800             | [2f91204b5e](https://linux-hardware.org/?probe=2f91204b5e) | Oct 26, 2020 |
| HP            | 255 G7 Notebook PC          | [fd598f0888](https://linux-hardware.org/?probe=fd598f0888) | Oct 25, 2020 |
| HP            | 255 G7 Notebook PC          | [07f3bdda40](https://linux-hardware.org/?probe=07f3bdda40) | Oct 25, 2020 |
| Dell          | Latitude E6410              | [1344691841](https://linux-hardware.org/?probe=1344691841) | Oct 21, 2020 |
| Dell          | G3 3590                     | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| Lenovo        | ThinkPad E560 20EV0013MS    | [6a0824824b](https://linux-hardware.org/?probe=6a0824824b) | Oct 20, 2020 |
| Dell          | Latitude E6430              | [67b44ea2b4](https://linux-hardware.org/?probe=67b44ea2b4) | Oct 20, 2020 |
| Fujitsu       | LIFEBOOK N532               | [165eb9dca4](https://linux-hardware.org/?probe=165eb9dca4) | Oct 20, 2020 |
| HP            | Compaq 6730s                | [b8d5fd5eea](https://linux-hardware.org/?probe=b8d5fd5eea) | Oct 19, 2020 |
| HP            | Notebook                    | [669e2e8ce6](https://linux-hardware.org/?probe=669e2e8ce6) | Oct 19, 2020 |
| Lenovo        | G50-80 80R0                 | [51ec4152a2](https://linux-hardware.org/?probe=51ec4152a2) | Oct 19, 2020 |
| ASUSTek       | Strix GL504GS               | [8ad3c543dd](https://linux-hardware.org/?probe=8ad3c543dd) | Oct 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c45c0eb7e4](https://linux-hardware.org/?probe=c45c0eb7e4) | Oct 16, 2020 |
| HP            | ProBook 4430s               | [c816b204bf](https://linux-hardware.org/?probe=c816b204bf) | Oct 15, 2020 |
| Clevo         | M660SE                      | [01a8ac7cd9](https://linux-hardware.org/?probe=01a8ac7cd9) | Oct 14, 2020 |
| Lenovo        | ThinkPad X270 20HN0013MX    | [3dbb81e06d](https://linux-hardware.org/?probe=3dbb81e06d) | Oct 14, 2020 |
| Dell          | Latitude E6420              | [1e2a1974f2](https://linux-hardware.org/?probe=1e2a1974f2) | Oct 08, 2020 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [01948526e2](https://linux-hardware.org/?probe=01948526e2) | Oct 08, 2020 |
| Acer          | Aspire 5715Z                | [e112fe04f3](https://linux-hardware.org/?probe=e112fe04f3) | Oct 08, 2020 |
| Medion        | E15302                      | [957a41b1b5](https://linux-hardware.org/?probe=957a41b1b5) | Oct 07, 2020 |
| HP            | Mini 110-4100               | [12696ba8b9](https://linux-hardware.org/?probe=12696ba8b9) | Oct 07, 2020 |
| Toshiba       | Satellite A135              | [5a5199528f](https://linux-hardware.org/?probe=5a5199528f) | Oct 05, 2020 |
| Toshiba       | Satellite A100              | [93f3a15a9e](https://linux-hardware.org/?probe=93f3a15a9e) | Oct 04, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [28bab55cdf](https://linux-hardware.org/?probe=28bab55cdf) | Oct 02, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | [e2a36190d7](https://linux-hardware.org/?probe=e2a36190d7) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| ASUSTek       | X202E                       | [12592ec3e9](https://linux-hardware.org/?probe=12592ec3e9) | Oct 01, 2020 |
| Lenovo        | IdeaPad S205 Brazos         | [ea76cd71d1](https://linux-hardware.org/?probe=ea76cd71d1) | Sep 30, 2020 |
| Lenovo        | IdeaPad S205 Brazos         | [74a119b0d1](https://linux-hardware.org/?probe=74a119b0d1) | Sep 30, 2020 |
| System76      | Serval WS                   | [7add8e6511](https://linux-hardware.org/?probe=7add8e6511) | Sep 25, 2020 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | [7cf2dda814](https://linux-hardware.org/?probe=7cf2dda814) | Sep 25, 2020 |
| Dell          | Precision M6700             | [1b20609aaa](https://linux-hardware.org/?probe=1b20609aaa) | Sep 25, 2020 |
| HP            | ProBook 440 G5              | [3140b90a75](https://linux-hardware.org/?probe=3140b90a75) | Sep 24, 2020 |
| Sony          | VGN-CR120E                  | [3e989ff916](https://linux-hardware.org/?probe=3e989ff916) | Sep 24, 2020 |
| Lenovo        | ThinkPad Helix 37022B9      | [180e8e870b](https://linux-hardware.org/?probe=180e8e870b) | Sep 20, 2020 |
| Apple         | MacBook4,1                  | [91c2f7bfb9](https://linux-hardware.org/?probe=91c2f7bfb9) | Sep 20, 2020 |
| Medion        | S6417 MD99649               | [ee4e46e9d9](https://linux-hardware.org/?probe=ee4e46e9d9) | Sep 19, 2020 |
| Dell          | Latitude E6410              | [6fa6138bb4](https://linux-hardware.org/?probe=6fa6138bb4) | Sep 18, 2020 |
| Dell          | Latitude E6410              | [8a3b88673f](https://linux-hardware.org/?probe=8a3b88673f) | Sep 17, 2020 |
| ASUSTek       | X202E                       | [e9e1d090a6](https://linux-hardware.org/?probe=e9e1d090a6) | Sep 17, 2020 |
| HP            | ElitePad 1000 G2            | [fd9904b122](https://linux-hardware.org/?probe=fd9904b122) | Sep 17, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [a96ad52bc9](https://linux-hardware.org/?probe=a96ad52bc9) | Sep 16, 2020 |
| Dell          | Latitude E6410              | [8930b7e16f](https://linux-hardware.org/?probe=8930b7e16f) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [299b899172](https://linux-hardware.org/?probe=299b899172) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [b45cb0028d](https://linux-hardware.org/?probe=b45cb0028d) | Sep 16, 2020 |
| HP            | Compaq 8710w (GC124EA#AK... | [dc5006e254](https://linux-hardware.org/?probe=dc5006e254) | Sep 15, 2020 |
| Apple         | MacBook4,1                  | [092f9a6491](https://linux-hardware.org/?probe=092f9a6491) | Sep 15, 2020 |
| HP            | G42                         | [9cb42d6f5f](https://linux-hardware.org/?probe=9cb42d6f5f) | Sep 15, 2020 |
| HP            | G42                         | [72d647e1b9](https://linux-hardware.org/?probe=72d647e1b9) | Sep 15, 2020 |
| NEC Comput... | Versa Premium               | [2ee7fa4da9](https://linux-hardware.org/?probe=2ee7fa4da9) | Sep 14, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [eeb54854f8](https://linux-hardware.org/?probe=eeb54854f8) | Sep 12, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [a8d6bb1865](https://linux-hardware.org/?probe=a8d6bb1865) | Sep 12, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| MSI           | GE73VR 7RF                  | [c236ff381b](https://linux-hardware.org/?probe=c236ff381b) | Sep 10, 2020 |
| MSI           | GE73VR 7RF                  | [f2bcc57dae](https://linux-hardware.org/?probe=f2bcc57dae) | Sep 10, 2020 |
| HP            | Unknown                     | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP            | Compaq 6715s (GR656EA#AB... | [c654e5d5b6](https://linux-hardware.org/?probe=c654e5d5b6) | Sep 10, 2020 |
| Acer          | Aspire A315-42G             | [ab24b14a42](https://linux-hardware.org/?probe=ab24b14a42) | Sep 09, 2020 |
| Acer          | AO532h                      | [c735bd82ba](https://linux-hardware.org/?probe=c735bd82ba) | Sep 08, 2020 |
| Acer          | AO532h                      | [9472d3a1c6](https://linux-hardware.org/?probe=9472d3a1c6) | Sep 08, 2020 |
| Samsung       | 530U4E/540U4E               | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| Dell          | Latitude E6420              | [e3bc793dc3](https://linux-hardware.org/?probe=e3bc793dc3) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [676828b4d4](https://linux-hardware.org/?probe=676828b4d4) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [6057658605](https://linux-hardware.org/?probe=6057658605) | Sep 01, 2020 |
| Dell          | Latitude E6420              | [9b1f1928c7](https://linux-hardware.org/?probe=9b1f1928c7) | Sep 01, 2020 |
| ASUSTek       | X401A1                      | [fe99f61b46](https://linux-hardware.org/?probe=fe99f61b46) | Aug 31, 2020 |
| ASUSTek       | X401A1                      | [3780ed8b61](https://linux-hardware.org/?probe=3780ed8b61) | Aug 31, 2020 |
| Positivo      | Mobile                      | [2249764f28](https://linux-hardware.org/?probe=2249764f28) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [cae373d70b](https://linux-hardware.org/?probe=cae373d70b) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [c77cf6f3fa](https://linux-hardware.org/?probe=c77cf6f3fa) | Aug 30, 2020 |
| Toshiba       | Satellite M500              | [42449081bb](https://linux-hardware.org/?probe=42449081bb) | Aug 29, 2020 |
| Acer          | AOHAPPY                     | [faa38ff55a](https://linux-hardware.org/?probe=faa38ff55a) | Aug 29, 2020 |
| Dell          | Precision 7540              | [093cb64961](https://linux-hardware.org/?probe=093cb64961) | Aug 28, 2020 |
| Lenovo        | ThinkPad Helix 37022B9      | [5c309fab5b](https://linux-hardware.org/?probe=5c309fab5b) | Aug 28, 2020 |
| Lenovo        | ThinkPad Helix 37022B9      | [961629ce0b](https://linux-hardware.org/?probe=961629ce0b) | Aug 28, 2020 |
| Acer          | AOHAPPY                     | [3f5f5a942d](https://linux-hardware.org/?probe=3f5f5a942d) | Aug 23, 2020 |
| HP            | Laptop 14-dq1xxx            | [218b728642](https://linux-hardware.org/?probe=218b728642) | Aug 22, 2020 |
| HP            | 250 G4 Notebook PC          | [97eeff2c12](https://linux-hardware.org/?probe=97eeff2c12) | Aug 22, 2020 |
| Lenovo        | ThinkPad W530 24478K0       | [74fda860f1](https://linux-hardware.org/?probe=74fda860f1) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | [5ffb6aaedb](https://linux-hardware.org/?probe=5ffb6aaedb) | Aug 17, 2020 |
| Toshiba       | IS 1414                     | [dc9617d1c1](https://linux-hardware.org/?probe=dc9617d1c1) | Aug 17, 2020 |
| MSI           | GP72MVR 7RFX                | [39da2f58b5](https://linux-hardware.org/?probe=39da2f58b5) | Aug 16, 2020 |
| Toshiba       | Satellite L655              | [86a1281caa](https://linux-hardware.org/?probe=86a1281caa) | Aug 16, 2020 |
| Dell          | Inspiron 7559               | [021ed0aac6](https://linux-hardware.org/?probe=021ed0aac6) | Aug 16, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0e5e076914](https://linux-hardware.org/?probe=0e5e076914) | Aug 15, 2020 |
| GPD           | MicroPC                     | [bb39ae1b31](https://linux-hardware.org/?probe=bb39ae1b31) | Aug 15, 2020 |
| Sony          | VPCEH1S1E                   | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| HP            | Stream Notebook             | [14b9b28cc6](https://linux-hardware.org/?probe=14b9b28cc6) | Aug 13, 2020 |
| HP            | Stream Notebook             | [3e5ba72fbb](https://linux-hardware.org/?probe=3e5ba72fbb) | Aug 13, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3e086d75b0](https://linux-hardware.org/?probe=3e086d75b0) | Aug 12, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ab576b0cd8](https://linux-hardware.org/?probe=ab576b0cd8) | Aug 12, 2020 |
| ASUSTek       | X71SL                       | [f2da7fe3f0](https://linux-hardware.org/?probe=f2da7fe3f0) | Aug 12, 2020 |
| HP            | ZBook 14u G6                | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [4657a3e758](https://linux-hardware.org/?probe=4657a3e758) | Aug 11, 2020 |
| ASUSTek       | X551MA                      | [f0d47bee93](https://linux-hardware.org/?probe=f0d47bee93) | Aug 11, 2020 |
| Dell          | Studio 1558                 | [96fc1659ad](https://linux-hardware.org/?probe=96fc1659ad) | Aug 06, 2020 |
| TPVAOC        | AA183M                      | [a43f54d1c1](https://linux-hardware.org/?probe=a43f54d1c1) | Aug 06, 2020 |
| TPVAOC        | AA183M                      | [984b29aa0d](https://linux-hardware.org/?probe=984b29aa0d) | Aug 06, 2020 |
| HP            | Pavilion dm1                | [ccb974921b](https://linux-hardware.org/?probe=ccb974921b) | Aug 05, 2020 |
| Toshiba       | Satellite A135              | [876a8beffa](https://linux-hardware.org/?probe=876a8beffa) | Aug 05, 2020 |
| ASUSTek       | X71SL                       | [7bfd99a9bd](https://linux-hardware.org/?probe=7bfd99a9bd) | Aug 05, 2020 |
| Dell          | XPS L702X                   | [86885b0835](https://linux-hardware.org/?probe=86885b0835) | Aug 04, 2020 |
| Fujitsu       | LIFEBOOK N532               | [672b47f6ec](https://linux-hardware.org/?probe=672b47f6ec) | Aug 04, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [806b0f6ffc](https://linux-hardware.org/?probe=806b0f6ffc) | Aug 04, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [03dcb81800](https://linux-hardware.org/?probe=03dcb81800) | Aug 04, 2020 |
| MSI           | GV62 8RD                    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| Dell          | Inspiron 1525               | [ca71666e04](https://linux-hardware.org/?probe=ca71666e04) | Aug 03, 2020 |
| Fujitsu       | LIFEBOOK N532               | [9d39f956c5](https://linux-hardware.org/?probe=9d39f956c5) | Aug 03, 2020 |
| Dell          | Inspiron 3421               | [09aac7d871](https://linux-hardware.org/?probe=09aac7d871) | Aug 01, 2020 |
| Dell          | Precision M4800             | [defc3ac914](https://linux-hardware.org/?probe=defc3ac914) | Aug 01, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [cde144782b](https://linux-hardware.org/?probe=cde144782b) | Jul 30, 2020 |
| Samsung       | 270E5G/270E5U               | [384f0ca64b](https://linux-hardware.org/?probe=384f0ca64b) | Jul 28, 2020 |
| Samsung       | 530U3C/530U4C/532U3C        | [a52cd7499e](https://linux-hardware.org/?probe=a52cd7499e) | Jul 28, 2020 |
| Lenovo        | Flex 2-14D 20376            | [efd445830e](https://linux-hardware.org/?probe=efd445830e) | Jul 27, 2020 |
| Quanta        | TWS                         | [3bc8fdae33](https://linux-hardware.org/?probe=3bc8fdae33) | Jul 27, 2020 |
| Dell          | Inspiron 7520               | [a1ea369f96](https://linux-hardware.org/?probe=a1ea369f96) | Jul 27, 2020 |
| Dell          | Inspiron 3421               | [12424c5a76](https://linux-hardware.org/?probe=12424c5a76) | Jul 25, 2020 |
| Sony          | SVE1511V1EW                 | [52da6c5e47](https://linux-hardware.org/?probe=52da6c5e47) | Jul 24, 2020 |
| HP            | Pavilion g4                 | [a10cfaa6e2](https://linux-hardware.org/?probe=a10cfaa6e2) | Jul 24, 2020 |
| Lenovo        | ThinkPad X300 64771TG       | [55c6de96ef](https://linux-hardware.org/?probe=55c6de96ef) | Jul 24, 2020 |
| HP            | EliteBook 2570p             | [baa26535f9](https://linux-hardware.org/?probe=baa26535f9) | Jul 23, 2020 |
| ASUSTek       | 1015BXO                     | [6521645132](https://linux-hardware.org/?probe=6521645132) | Jul 21, 2020 |
| Acer          | Aspire ES1-523              | [030cf77080](https://linux-hardware.org/?probe=030cf77080) | Jul 20, 2020 |
| Dell          | Vostro 3560                 | [c83b65951c](https://linux-hardware.org/?probe=c83b65951c) | Jul 20, 2020 |
| HP            | ZBook 17 G2                 | [61d82db95d](https://linux-hardware.org/?probe=61d82db95d) | Jul 20, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8e5e5de5c3](https://linux-hardware.org/?probe=8e5e5de5c3) | Jul 20, 2020 |
| Dell          | Inspiron 5570               | [dd83257459](https://linux-hardware.org/?probe=dd83257459) | Jul 20, 2020 |
| Acer          | Aspire ES1-523              | [4d9339959a](https://linux-hardware.org/?probe=4d9339959a) | Jul 20, 2020 |
| HP            | 250 G5 Notebook PC          | [9577cafcf7](https://linux-hardware.org/?probe=9577cafcf7) | Jul 19, 2020 |
| Lenovo        | ThinkPad T490 20N3CTO1WW    | [b6f9682f0b](https://linux-hardware.org/?probe=b6f9682f0b) | Jul 15, 2020 |
| ASUSTek       | X555LJ                      | [5657a6a512](https://linux-hardware.org/?probe=5657a6a512) | Jul 14, 2020 |
| Dell          | G7 7588                     | [8c4a8875bd](https://linux-hardware.org/?probe=8c4a8875bd) | Jul 14, 2020 |
| Dell          | Inspiron 5567               | [9cf2e63283](https://linux-hardware.org/?probe=9cf2e63283) | Jul 14, 2020 |
| Acer          | Aspire E1-522               | [7ff40fb055](https://linux-hardware.org/?probe=7ff40fb055) | Jul 13, 2020 |
| Dell          | G7 7588                     | [aee8398552](https://linux-hardware.org/?probe=aee8398552) | Jul 12, 2020 |
| Lenovo        | Flex 2-14D 20376            | [5d6e43e05a](https://linux-hardware.org/?probe=5d6e43e05a) | Jul 12, 2020 |
| Dell          | G7 7588                     | [3424a96642](https://linux-hardware.org/?probe=3424a96642) | Jul 11, 2020 |
| Sony          | VPCF1290X                   | [f7c7a3ca92](https://linux-hardware.org/?probe=f7c7a3ca92) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [f4dd6bbdec](https://linux-hardware.org/?probe=f4dd6bbdec) | Jul 06, 2020 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [9738f4a503](https://linux-hardware.org/?probe=9738f4a503) | Jul 06, 2020 |
| Lenovo        | ThinkPad 11e 20D9CTO1WW     | [11c17aa062](https://linux-hardware.org/?probe=11c17aa062) | Jul 05, 2020 |
| Acer          | Aspire 7750G                | [f6a31e475d](https://linux-hardware.org/?probe=f6a31e475d) | Jul 05, 2020 |
| HP            | 250 G4                      | [ca40ef5473](https://linux-hardware.org/?probe=ca40ef5473) | Jul 02, 2020 |
| HP            | Pavilion g6                 | [0175164903](https://linux-hardware.org/?probe=0175164903) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| Positivo      | CHT14B                      | [61243d867b](https://linux-hardware.org/?probe=61243d867b) | Jun 29, 2020 |
| Positivo      | CHT14B                      | [880351a699](https://linux-hardware.org/?probe=880351a699) | Jun 29, 2020 |
| HP            | Pavilion g6                 | [efc97f097b](https://linux-hardware.org/?probe=efc97f097b) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [944b66e3ba](https://linux-hardware.org/?probe=944b66e3ba) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [3f58959650](https://linux-hardware.org/?probe=3f58959650) | Jun 24, 2020 |
| Lenovo        | ThinkPad T520 4243RS6       | [881175c7ec](https://linux-hardware.org/?probe=881175c7ec) | Jun 23, 2020 |
| HP            | ProBook 450 G5              | [143bbac73c](https://linux-hardware.org/?probe=143bbac73c) | Jun 23, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [c5a7e2708f](https://linux-hardware.org/?probe=c5a7e2708f) | Jun 22, 2020 |
| ASUSTek       | 1015CX                      | [bca2250456](https://linux-hardware.org/?probe=bca2250456) | Jun 18, 2020 |
| Lenovo        | ThinkPad X240 qqqq          | [04328e30ac](https://linux-hardware.org/?probe=04328e30ac) | Jun 15, 2020 |
| Sony          | VPCF1290X                   | [55652dadf6](https://linux-hardware.org/?probe=55652dadf6) | Jun 15, 2020 |
| ASUSTek       | 1015CX                      | [03528cfeaa](https://linux-hardware.org/?probe=03528cfeaa) | Jun 13, 2020 |
| ASUSTek       | 1015CX                      | [ad3136a30e](https://linux-hardware.org/?probe=ad3136a30e) | Jun 13, 2020 |
| Lenovo        | ThinkPad T430 2349H86       | [5ef2ab445e](https://linux-hardware.org/?probe=5ef2ab445e) | Jun 13, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [5467542c77](https://linux-hardware.org/?probe=5467542c77) | Jun 12, 2020 |
| HP            | Pavilion g6                 | [78f5ccb141](https://linux-hardware.org/?probe=78f5ccb141) | Jun 11, 2020 |
| HP            | EliteBook 2570p             | [280e2933d6](https://linux-hardware.org/?probe=280e2933d6) | Jun 11, 2020 |
| HP            | EliteBook 8760w             | [9e4b33b5fb](https://linux-hardware.org/?probe=9e4b33b5fb) | Jun 07, 2020 |
| Acer          | Nitro AN515-54              | [4c810c7859](https://linux-hardware.org/?probe=4c810c7859) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [35995e9a53](https://linux-hardware.org/?probe=35995e9a53) | Jun 06, 2020 |
| ASUSTek       | X541SA                      | [508fc56922](https://linux-hardware.org/?probe=508fc56922) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [d6bcbe862e](https://linux-hardware.org/?probe=d6bcbe862e) | Jun 05, 2020 |
| ASUSTek       | 1011PX                      | [2db55f1fde](https://linux-hardware.org/?probe=2db55f1fde) | Jun 05, 2020 |
| ASUSTek       | 1011PX                      | [d27bc5f60a](https://linux-hardware.org/?probe=d27bc5f60a) | Jun 05, 2020 |
| HP            | EliteBook 8760w             | [053e492988](https://linux-hardware.org/?probe=053e492988) | Jun 04, 2020 |
| HP            | 250 G4                      | [23b40bc110](https://linux-hardware.org/?probe=23b40bc110) | Jun 04, 2020 |
| Toshiba       | Satellite M500              | [96d989965c](https://linux-hardware.org/?probe=96d989965c) | Jun 04, 2020 |
| HP            | 250 G7 Notebook PC          | [56c24dddd4](https://linux-hardware.org/?probe=56c24dddd4) | May 31, 2020 |
| Lenovo        | ThinkPad X230 2325CL7       | [f6c4ee0c49](https://linux-hardware.org/?probe=f6c4ee0c49) | May 30, 2020 |
| Packard Be... | EasyNote ME69BMP            | [7023dc94da](https://linux-hardware.org/?probe=7023dc94da) | May 28, 2020 |
| Dell          | Precision M6800             | [fac8dbf769](https://linux-hardware.org/?probe=fac8dbf769) | May 28, 2020 |
| Packard Be... | EasyNote ME69BMP            | [17cb4d2a9a](https://linux-hardware.org/?probe=17cb4d2a9a) | May 28, 2020 |
| Dell          | Precision M4800             | [4f404379b5](https://linux-hardware.org/?probe=4f404379b5) | May 27, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| Lenovo        | ThinkPad T480s 20L7001HM... | [8c6c9a5faa](https://linux-hardware.org/?probe=8c6c9a5faa) | May 25, 2020 |
| Dell          | Studio 1558                 | [19baf8204a](https://linux-hardware.org/?probe=19baf8204a) | May 25, 2020 |
| Toshiba       | Satellite M500              | [89bc529650](https://linux-hardware.org/?probe=89bc529650) | May 23, 2020 |
| ASUSTek       | A6Km                        | [f68c00b849](https://linux-hardware.org/?probe=f68c00b849) | May 23, 2020 |
| Sony          | VPCF1290X                   | [6d41a82565](https://linux-hardware.org/?probe=6d41a82565) | May 22, 2020 |
| Sony          | VPCF1290X                   | [e260c25549](https://linux-hardware.org/?probe=e260c25549) | May 20, 2020 |
| Toshiba       | Satellite M115              | [4375f8c26e](https://linux-hardware.org/?probe=4375f8c26e) | May 20, 2020 |
| ASUSTek       | X541SA                      | [af59d45f16](https://linux-hardware.org/?probe=af59d45f16) | May 19, 2020 |
| Dell          | Latitude E6400              | [5575a3dc87](https://linux-hardware.org/?probe=5575a3dc87) | May 17, 2020 |
| eMachines     | eME728                      | [2ef41ed601](https://linux-hardware.org/?probe=2ef41ed601) | May 17, 2020 |
| Dell          | Latitude E6400              | [4ad76f6e55](https://linux-hardware.org/?probe=4ad76f6e55) | May 16, 2020 |
| Dell          | Latitude E6400              | [7402a2d316](https://linux-hardware.org/?probe=7402a2d316) | May 16, 2020 |
| Dell          | Latitude E6400              | [9c8f7c7f2c](https://linux-hardware.org/?probe=9c8f7c7f2c) | May 16, 2020 |
| Dell          | Latitude E6400              | [491ea13111](https://linux-hardware.org/?probe=491ea13111) | May 16, 2020 |
| Dell          | Latitude E6400              | [0e2b5d699e](https://linux-hardware.org/?probe=0e2b5d699e) | May 16, 2020 |
| HP            | 250 G1                      | [bc48855d22](https://linux-hardware.org/?probe=bc48855d22) | May 16, 2020 |
| ASUSTek       | A6R                         | [5336380e70](https://linux-hardware.org/?probe=5336380e70) | May 16, 2020 |
| ASUSTek       | A6R                         | [b8bb81dd95](https://linux-hardware.org/?probe=b8bb81dd95) | May 16, 2020 |
| ASUSTek       | A6R                         | [364f7ae63c](https://linux-hardware.org/?probe=364f7ae63c) | May 16, 2020 |
| ASUSTek       | A6R                         | [6253744b9d](https://linux-hardware.org/?probe=6253744b9d) | May 16, 2020 |
| Toshiba       | PORTEGE R500                | [c71d2cbb71](https://linux-hardware.org/?probe=c71d2cbb71) | May 13, 2020 |
| Lenovo        | ThinkPad X240 20AMS08816    | [5581eee295](https://linux-hardware.org/?probe=5581eee295) | May 10, 2020 |
| Dell          | XPS L502X                   | [f095fb06d8](https://linux-hardware.org/?probe=f095fb06d8) | May 09, 2020 |
| Acer          | Aspire V3-771               | [cff5591c0d](https://linux-hardware.org/?probe=cff5591c0d) | May 09, 2020 |
| Toshiba       | Satellite L655              | [457a9f9299](https://linux-hardware.org/?probe=457a9f9299) | May 08, 2020 |
| HP            | 250 G5 Notebook PC          | [33e1791dd6](https://linux-hardware.org/?probe=33e1791dd6) | May 06, 2020 |
| Dell          | Latitude E5540              | [32f0868b2f](https://linux-hardware.org/?probe=32f0868b2f) | May 04, 2020 |
| Toshiba       | Satellite A200              | [676473fe43](https://linux-hardware.org/?probe=676473fe43) | May 04, 2020 |
| HP            | EliteBook 840 G2            | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Samsung       | 550P5C/550P7C               | [4262f676d3](https://linux-hardware.org/?probe=4262f676d3) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [015ef81b51](https://linux-hardware.org/?probe=015ef81b51) | May 02, 2020 |
| ASUSTek       | G73Sw                       | [d4abec1a93](https://linux-hardware.org/?probe=d4abec1a93) | May 02, 2020 |
| HP            | 250 G5 Notebook PC          | [f986b480ad](https://linux-hardware.org/?probe=f986b480ad) | May 01, 2020 |
| Toshiba       | Satellite L655              | [3973e23d56](https://linux-hardware.org/?probe=3973e23d56) | May 01, 2020 |
| Dell          | Inspiron 3576               | [4dc9474ba1](https://linux-hardware.org/?probe=4dc9474ba1) | Apr 29, 2020 |
| Clevo         | M720R                       | [4f4a5860a1](https://linux-hardware.org/?probe=4f4a5860a1) | Apr 24, 2020 |
| Sony          | VPCS12X9E                   | [3631a4d89d](https://linux-hardware.org/?probe=3631a4d89d) | Apr 24, 2020 |
| EUROCOM       | Sky X4E2G                   | [0e3f208b3c](https://linux-hardware.org/?probe=0e3f208b3c) | Apr 22, 2020 |
| Lenovo        | ThinkPad Helix 37022B9      | [3ad0dfd21f](https://linux-hardware.org/?probe=3ad0dfd21f) | Apr 21, 2020 |
| HP            | Pavilion dm1                | [11b25e60cb](https://linux-hardware.org/?probe=11b25e60cb) | Apr 21, 2020 |
| ASUSTek       | K93SV                       | [8faa290ce8](https://linux-hardware.org/?probe=8faa290ce8) | Apr 20, 2020 |
| ASUSTek       | K93SV                       | [a1ca15a373](https://linux-hardware.org/?probe=a1ca15a373) | Apr 20, 2020 |
| Fujitsu       | LIFEBOOK A514               | [af6eaab269](https://linux-hardware.org/?probe=af6eaab269) | Apr 20, 2020 |
| ASUSTek       | K50C                        | [5ee28e5ccc](https://linux-hardware.org/?probe=5ee28e5ccc) | Apr 19, 2020 |
| ASUSTek       | K50C                        | [a726950b70](https://linux-hardware.org/?probe=a726950b70) | Apr 19, 2020 |
| Lenovo        | ThinkPad T460s 20F9003WM... | [1b1c89732c](https://linux-hardware.org/?probe=1b1c89732c) | Apr 19, 2020 |
| Acer          | Aspire V3-771               | [25f71cbbef](https://linux-hardware.org/?probe=25f71cbbef) | Apr 18, 2020 |
| HP            | ENVY Laptop 17-ce1xxx       | [e8068af7ce](https://linux-hardware.org/?probe=e8068af7ce) | Apr 16, 2020 |
| HP            | EliteBook 755 G5            | [db0ea12ab8](https://linux-hardware.org/?probe=db0ea12ab8) | Apr 16, 2020 |
| HP            | ENVY Laptop 17-ce1xxx       | [495df3af5a](https://linux-hardware.org/?probe=495df3af5a) | Apr 16, 2020 |
| HP            | ENVY Laptop 17-ce1xxx       | [391bf953f4](https://linux-hardware.org/?probe=391bf953f4) | Apr 16, 2020 |
| Dell          | Vostro 5370                 | [85fd1c41fa](https://linux-hardware.org/?probe=85fd1c41fa) | Apr 15, 2020 |
| Toshiba       | Satellite C70D-B            | [8c82f89cbd](https://linux-hardware.org/?probe=8c82f89cbd) | Apr 14, 2020 |
| Lenovo        | G505 20240                  | [93a89841fd](https://linux-hardware.org/?probe=93a89841fd) | Apr 12, 2020 |
| HP            | ENVY Laptop 17-ce1xxx       | [45bfd9ab4c](https://linux-hardware.org/?probe=45bfd9ab4c) | Apr 12, 2020 |
| HP            | ENVY Laptop 17-ce1xxx       | [407cefd33a](https://linux-hardware.org/?probe=407cefd33a) | Apr 12, 2020 |
| ASUSTek       | X751SA                      | [ffa413a7f5](https://linux-hardware.org/?probe=ffa413a7f5) | Apr 11, 2020 |
| Acer          | Aspire E5-573               | [98d193256b](https://linux-hardware.org/?probe=98d193256b) | Apr 10, 2020 |
| Thomson       | NEO14A-4BK64                | [46f8b508df](https://linux-hardware.org/?probe=46f8b508df) | Apr 09, 2020 |
| HP            | Pavilion 17                 | [fdd7fcc88c](https://linux-hardware.org/?probe=fdd7fcc88c) | Apr 09, 2020 |
| HP            | Unknown                     | [80d7bce9f1](https://linux-hardware.org/?probe=80d7bce9f1) | Apr 09, 2020 |
| Quanta        | TWH                         | [427f74a0fd](https://linux-hardware.org/?probe=427f74a0fd) | Apr 08, 2020 |
| TrekStor      | Surfbook A13B               | [cba50e935a](https://linux-hardware.org/?probe=cba50e935a) | Apr 07, 2020 |
| Apple         | MacBookPro8,1               | [1ac68a726e](https://linux-hardware.org/?probe=1ac68a726e) | Apr 06, 2020 |
| Acer          | Aspire V3-771               | [d5ebb6d1d9](https://linux-hardware.org/?probe=d5ebb6d1d9) | Apr 05, 2020 |
| Toshiba       | NB505                       | [934ebfe06b](https://linux-hardware.org/?probe=934ebfe06b) | Apr 05, 2020 |
| Lenovo        | ThinkPad T450 20BUS1KJ1N    | [e038b6f633](https://linux-hardware.org/?probe=e038b6f633) | Apr 05, 2020 |
| Lenovo        | ThinkPad T450 20BUS1KJ1N    | [6935beaa00](https://linux-hardware.org/?probe=6935beaa00) | Apr 05, 2020 |
| Dell          | XPS 13 9360                 | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| BESSTAR Te... | T3 MRD                      | [a5635ffb15](https://linux-hardware.org/?probe=a5635ffb15) | Apr 01, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [9c2eef7d10](https://linux-hardware.org/?probe=9c2eef7d10) | Mar 31, 2020 |
| Dell          | Latitude E6410              | [940c6c76c0](https://linux-hardware.org/?probe=940c6c76c0) | Mar 29, 2020 |
| HP            | 255 G6 Notebook PC          | [083126fc1e](https://linux-hardware.org/?probe=083126fc1e) | Mar 28, 2020 |
| HP            | 255 G6 Notebook PC          | [6a3346f37e](https://linux-hardware.org/?probe=6a3346f37e) | Mar 28, 2020 |
| Toshiba       | Satellite C55-A             | [ee887df152](https://linux-hardware.org/?probe=ee887df152) | Mar 26, 2020 |
| HP            | HDX 16                      | [1477d3f366](https://linux-hardware.org/?probe=1477d3f366) | Mar 26, 2020 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [54f36d8b69](https://linux-hardware.org/?probe=54f36d8b69) | Mar 26, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [154b970640](https://linux-hardware.org/?probe=154b970640) | Mar 25, 2020 |
| Acer          | Aspire A515-52              | [2e77260658](https://linux-hardware.org/?probe=2e77260658) | Mar 25, 2020 |
| HP            | HDX 16                      | [f26cfe6fa1](https://linux-hardware.org/?probe=f26cfe6fa1) | Mar 24, 2020 |
| ARCELIK       | GNB 1150 B1 N2 V1.0         | [632afea697](https://linux-hardware.org/?probe=632afea697) | Mar 23, 2020 |
| Acer          | Aspire ES1-512              | [a2c7011157](https://linux-hardware.org/?probe=a2c7011157) | Mar 23, 2020 |
| HP            | Mini 110-3500               | [9d36830186](https://linux-hardware.org/?probe=9d36830186) | Mar 23, 2020 |
| ASUSTek       | R11CX                       | [680a4502f2](https://linux-hardware.org/?probe=680a4502f2) | Mar 19, 2020 |
| ASUSTek       | R11CX                       | [36a803af0b](https://linux-hardware.org/?probe=36a803af0b) | Mar 19, 2020 |
| Acer          | Aspire 3000                 | [2cee600c99](https://linux-hardware.org/?probe=2cee600c99) | Mar 19, 2020 |
| Acer          | Aspire 3000                 | [e0d7d209a9](https://linux-hardware.org/?probe=e0d7d209a9) | Mar 19, 2020 |
| Acer          | Aspire 4332                 | [1ffe28f950](https://linux-hardware.org/?probe=1ffe28f950) | Mar 19, 2020 |
| Acer          | Aspire 4332                 | [4ef79a9f26](https://linux-hardware.org/?probe=4ef79a9f26) | Mar 19, 2020 |
| Lenovo        | G50-70 20351                | [bb73a70e51](https://linux-hardware.org/?probe=bb73a70e51) | Mar 16, 2020 |
| Notebook      | N2x0WU                      | [e4b2f86e5b](https://linux-hardware.org/?probe=e4b2f86e5b) | Mar 14, 2020 |
| ASUSTek       | K93SV                       | [50730ff19d](https://linux-hardware.org/?probe=50730ff19d) | Mar 13, 2020 |
| TrekStor      | Surfbook A13B               | [73a9d973bd](https://linux-hardware.org/?probe=73a9d973bd) | Mar 10, 2020 |
| HP            | 250 G1                      | [7a7e2dfcee](https://linux-hardware.org/?probe=7a7e2dfcee) | Mar 10, 2020 |
| ASUSTek       | Strix GL504GS               | [e7b1102cc3](https://linux-hardware.org/?probe=e7b1102cc3) | Mar 01, 2020 |
| Acer          | Aspire one 1-431            | [83a3eeaf25](https://linux-hardware.org/?probe=83a3eeaf25) | Feb 28, 2020 |
| Timi          | TM1604                      | [1f8de2b55c](https://linux-hardware.org/?probe=1f8de2b55c) | Feb 27, 2020 |
| Toshiba       | Satellite L350              | [a10e6db465](https://linux-hardware.org/?probe=a10e6db465) | Feb 26, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [ad9b0ebdf6](https://linux-hardware.org/?probe=ad9b0ebdf6) | Feb 25, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [9ffca879a6](https://linux-hardware.org/?probe=9ffca879a6) | Feb 22, 2020 |
| TrekStor      | Surfbook A13B               | [a115d906d1](https://linux-hardware.org/?probe=a115d906d1) | Feb 21, 2020 |
| ASUSTek       | X101CH                      | [b07b5697b1](https://linux-hardware.org/?probe=b07b5697b1) | Feb 18, 2020 |
| Sony          | VPCEL3S1E                   | [a9e404c45b](https://linux-hardware.org/?probe=a9e404c45b) | Feb 17, 2020 |
| Sony          | VPCEL3S1E                   | [c2beb0388e](https://linux-hardware.org/?probe=c2beb0388e) | Feb 17, 2020 |
| Lenovo        | IdeaPad S100c 20194         | [d1a4bff183](https://linux-hardware.org/?probe=d1a4bff183) | Feb 15, 2020 |
| ASUSTek       | S550CM                      | [243f1352f1](https://linux-hardware.org/?probe=243f1352f1) | Feb 13, 2020 |
| Dell          | Precision 5510              | [bab9a0d0c8](https://linux-hardware.org/?probe=bab9a0d0c8) | Feb 11, 2020 |
| Dell          | Precision 5510              | [4c17778c81](https://linux-hardware.org/?probe=4c17778c81) | Feb 05, 2020 |
| HP            | EliteBook 840 G2            | [22d45681c5](https://linux-hardware.org/?probe=22d45681c5) | Feb 03, 2020 |
| Dell          | Latitude E6520              | [8b52e94f25](https://linux-hardware.org/?probe=8b52e94f25) | Feb 01, 2020 |
| Dell          | Latitude E6520              | [3b51e13261](https://linux-hardware.org/?probe=3b51e13261) | Feb 01, 2020 |
| Dell          | Latitude E6520              | [11bf75c240](https://linux-hardware.org/?probe=11bf75c240) | Feb 01, 2020 |
| Lenovo        | IdeaPad Y460                | [ece975c659](https://linux-hardware.org/?probe=ece975c659) | Feb 01, 2020 |
| Lenovo        | IdeaPad Y460                | [1a614a42a8](https://linux-hardware.org/?probe=1a614a42a8) | Jan 30, 2020 |
| HP            | Laptop 15-db0xxx            | [ff69352a6e](https://linux-hardware.org/?probe=ff69352a6e) | Jan 25, 2020 |
| Dell          | Vostro 14-5459              | [826f9b1f68](https://linux-hardware.org/?probe=826f9b1f68) | Jan 11, 2020 |
| TUXEDO        | Unknown                     | [4eef3e4aa5](https://linux-hardware.org/?probe=4eef3e4aa5) | Jan 10, 2020 |
| MSI           | GS65 Stealth 9SF            | [9f88cc48ff](https://linux-hardware.org/?probe=9f88cc48ff) | Jan 09, 2020 |
| HP            | EliteBook 820 G3            | [1b307a97b6](https://linux-hardware.org/?probe=1b307a97b6) | Jan 07, 2020 |
| Acer          | Aspire V3-574G              | [471f9aa9b0](https://linux-hardware.org/?probe=471f9aa9b0) | Jan 02, 2020 |
| Lenovo        | IdeaPad Flex 14 20308       | [d659c7da10](https://linux-hardware.org/?probe=d659c7da10) | Dec 31, 2019 |
| Dell          | Latitude 5400               | [02483447bb](https://linux-hardware.org/?probe=02483447bb) | Dec 31, 2019 |
| Lenovo        | ThinkPad T61 7661BF3        | [3e00eba0be](https://linux-hardware.org/?probe=3e00eba0be) | Dec 26, 2019 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [efc1ac12c7](https://linux-hardware.org/?probe=efc1ac12c7) | Dec 21, 2019 |
| ASUSTek       | UL30A                       | [b7f84b8da0](https://linux-hardware.org/?probe=b7f84b8da0) | Dec 20, 2019 |
| Lenovo        | ThinkPad E565 20EYA007KD    | [c1c9dd614a](https://linux-hardware.org/?probe=c1c9dd614a) | Dec 17, 2019 |
| ASUSTek       | K93SV                       | [2512ed1f69](https://linux-hardware.org/?probe=2512ed1f69) | Dec 16, 2019 |
| HP            | G62                         | [af73595612](https://linux-hardware.org/?probe=af73595612) | Dec 12, 2019 |
| HP            | 2133                        | [99478a8c67](https://linux-hardware.org/?probe=99478a8c67) | Dec 11, 2019 |
| HP            | Pavilion 17                 | [86639b5a92](https://linux-hardware.org/?probe=86639b5a92) | Dec 10, 2019 |
| Lenovo        | ThinkPad T61 7661BF3        | [514c92a80a](https://linux-hardware.org/?probe=514c92a80a) | Dec 09, 2019 |
| HP            | G62                         | [f25def42f4](https://linux-hardware.org/?probe=f25def42f4) | Dec 07, 2019 |
| HP            | G62                         | [7dfa81ce3b](https://linux-hardware.org/?probe=7dfa81ce3b) | Dec 01, 2019 |
| EUROCOM       | Sky X4E2G                   | [e09781da91](https://linux-hardware.org/?probe=e09781da91) | Dec 01, 2019 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [00acf9644c](https://linux-hardware.org/?probe=00acf9644c) | Nov 27, 2019 |
| HP            | Laptop 15-db0xxx            | [e759e2cbde](https://linux-hardware.org/?probe=e759e2cbde) | Nov 27, 2019 |
| HP            | Laptop 15-db0xxx            | [c09c9e58c7](https://linux-hardware.org/?probe=c09c9e58c7) | Nov 27, 2019 |
| HP            | Laptop 15-db0xxx            | [9d98181e17](https://linux-hardware.org/?probe=9d98181e17) | Nov 24, 2019 |
| HP            | Laptop 15-db0xxx            | [5fe044ede7](https://linux-hardware.org/?probe=5fe044ede7) | Nov 24, 2019 |
| Dell          | Inspiron 1545               | [ac96625684](https://linux-hardware.org/?probe=ac96625684) | Nov 24, 2019 |
| HP            | 2133                        | [74fb4a248e](https://linux-hardware.org/?probe=74fb4a248e) | Nov 23, 2019 |
| HP            | 2133                        | [f31b08c736](https://linux-hardware.org/?probe=f31b08c736) | Nov 22, 2019 |
| HP            | 2133                        | [03de86c6e2](https://linux-hardware.org/?probe=03de86c6e2) | Nov 22, 2019 |
| HP            | Pavilion dv7                | [0c8d7641b2](https://linux-hardware.org/?probe=0c8d7641b2) | Nov 21, 2019 |
| ASUSTek       | GL753VD                     | [ba0396ff60](https://linux-hardware.org/?probe=ba0396ff60) | Nov 15, 2019 |
| ASUSTek       | GL553VD                     | [b1e21f6338](https://linux-hardware.org/?probe=b1e21f6338) | Nov 15, 2019 |
| HP            | Laptop 15-db0xxx            | [650415ada9](https://linux-hardware.org/?probe=650415ada9) | Nov 14, 2019 |
| ASUSTek       | K93SV                       | [1b7cf89903](https://linux-hardware.org/?probe=1b7cf89903) | Nov 14, 2019 |
| ASUSTek       | K93SV                       | [b049ed4601](https://linux-hardware.org/?probe=b049ed4601) | Nov 11, 2019 |
| MSI           | GP72 6QF                    | [98dc37dc79](https://linux-hardware.org/?probe=98dc37dc79) | Oct 21, 2019 |
| Acer          | Aspire 7738                 | [8a09011e2b](https://linux-hardware.org/?probe=8a09011e2b) | Oct 12, 2019 |
| Dell          | Latitude E6520              | [c1977c8c10](https://linux-hardware.org/?probe=c1977c8c10) | Sep 10, 2019 |
| HP            | ZBook Studio G3             | [3240076aa6](https://linux-hardware.org/?probe=3240076aa6) | Jul 23, 2019 |
| HP            | ENVY 15                     | [fbc2f0a547](https://linux-hardware.org/?probe=fbc2f0a547) | Jun 06, 2019 |
| Advent        | Roma                        | [36d20501b0](https://linux-hardware.org/?probe=36d20501b0) | Nov 16, 2018 |
| Advent        | Roma                        | [d7e4c674fb](https://linux-hardware.org/?probe=d7e4c674fb) | Nov 13, 2018 |
| Acer          | Aspire V3-571G              | [35070edeb2](https://linux-hardware.org/?probe=35070edeb2) | Oct 21, 2018 |
| Acer          | Aspire V3-571G              | [f6192425ba](https://linux-hardware.org/?probe=f6192425ba) | Oct 18, 2018 |
| Acer          | Aspire V3-571G              | [bdec8b5dd9](https://linux-hardware.org/?probe=bdec8b5dd9) | Oct 18, 2018 |
| Lenovo        | ThinkPad P50s 20FL000EGE    | [d2b988b0c4](https://linux-hardware.org/?probe=d2b988b0c4) | Sep 27, 2018 |
| HP            | Pavilion 15                 | [80d612b4c7](https://linux-hardware.org/?probe=80d612b4c7) | Aug 11, 2018 |
| HP            | Pavilion 15                 | [8a9510ebf5](https://linux-hardware.org/?probe=8a9510ebf5) | Aug 11, 2018 |
| HP            | Pavilion 15                 | [112596a781](https://linux-hardware.org/?probe=112596a781) | Aug 11, 2018 |
| HP            | Pavilion 15                 | [e6bc939345](https://linux-hardware.org/?probe=e6bc939345) | Aug 11, 2018 |
| SECO          | UDOO x86                    | [5278a91530](https://linux-hardware.org/?probe=5278a91530) | Jun 21, 2018 |
| Acer          | TravelMate B113             | [d86dbc4294](https://linux-hardware.org/?probe=d86dbc4294) | Feb 19, 2018 |
| Acer          | Nitro AN515-51              | [51ac6d49f9](https://linux-hardware.org/?probe=51ac6d49f9) | Dec 28, 2017 |
| Acer          | TravelMate P277-MG          | [303cee3407](https://linux-hardware.org/?probe=303cee3407) | Feb 23, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ubuntu MATE 20.04 | 259       | 51.49%  |
| Ubuntu MATE 18.04 | 130       | 25.84%  |
| Ubuntu MATE 20.10 | 26        | 5.17%   |
| Ubuntu MATE 19.10 | 26        | 5.17%   |
| Ubuntu MATE 21.04 | 22        | 4.37%   |
| Ubuntu MATE 21.10 | 21        | 4.17%   |
| Ubuntu MATE 16.04 | 12        | 2.39%   |
| Ubuntu MATE       | 3         | 0.6%    |
| Ubuntu MATE 22.04 | 2         | 0.4%    |
| Ubuntu MATE 19.04 | 1         | 0.2%    |
| Ubuntu MATE 16.10 | 1         | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Ubuntu MATE | 492       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 39        | 6.93%   |
| 5.4.0-52-generic  | 17        | 3.02%   |
| 5.4.0-47-generic  | 16        | 2.84%   |
| 5.4.0-58-generic  | 13        | 2.31%   |
| 5.4.0-48-generic  | 12        | 2.13%   |
| 5.4.0-65-generic  | 11        | 1.95%   |
| 5.4.0-40-generic  | 10        | 1.78%   |
| 5.3.0-42-generic  | 10        | 1.78%   |
| 5.8.0-50-generic  | 9         | 1.6%    |
| 5.4.0-54-generic  | 9         | 1.6%    |
| 5.3.0-40-generic  | 9         | 1.6%    |
| 5.8.0-48-generic  | 8         | 1.42%   |
| 5.4.0-31-generic  | 8         | 1.42%   |
| 5.11.0-37-generic | 8         | 1.42%   |
| 5.4.0-81-generic  | 7         | 1.24%   |
| 5.4.0-56-generic  | 7         | 1.24%   |
| 5.4.0-26-generic  | 7         | 1.24%   |
| 5.3.0-28-generic  | 7         | 1.24%   |
| 5.11.0-40-generic | 7         | 1.24%   |
| 5.8.0-43-generic  | 6         | 1.07%   |
| 5.4.0-45-generic  | 6         | 1.07%   |
| 5.3.0-51-generic  | 6         | 1.07%   |
| 5.3.0-46-generic  | 6         | 1.07%   |
| 5.3.0-45-generic  | 6         | 1.07%   |
| 5.13.0-39-generic | 6         | 1.07%   |
| 5.8.0-59-generic  | 5         | 0.89%   |
| 5.4.0-74-generic  | 5         | 0.89%   |
| 5.4.0-73-generic  | 5         | 0.89%   |
| 5.4.0-51-generic  | 5         | 0.89%   |
| 5.4.0-37-generic  | 5         | 0.89%   |
| 5.4.0-29-generic  | 5         | 0.89%   |
| 5.3.0-62-generic  | 5         | 0.89%   |
| 5.13.0-28-generic | 5         | 0.89%   |
| 5.11.0-41-generic | 5         | 0.89%   |
| 5.11.0-38-generic | 5         | 0.89%   |
| 5.8.0-53-generic  | 4         | 0.71%   |
| 5.8.0-38-generic  | 4         | 0.71%   |
| 5.4.0-91-generic  | 4         | 0.71%   |
| 5.4.0-90-generic  | 4         | 0.71%   |
| 5.4.0-89-generic  | 4         | 0.71%   |
| 5.4.0-70-generic  | 4         | 0.71%   |
| 5.3.0-29-generic  | 4         | 0.71%   |
| 5.13.0-30-generic | 4         | 0.71%   |
| 5.13.0-20-generic | 4         | 0.71%   |
| 5.11.0-22-generic | 4         | 0.71%   |
| 5.11.0-16-generic | 4         | 0.71%   |
| 5.8.0-33-generic  | 3         | 0.53%   |
| 5.8.0-29-generic  | 3         | 0.53%   |
| 5.8.0-25-generic  | 3         | 0.53%   |
| 5.4.0-80-generic  | 3         | 0.53%   |
| 5.4.0-77-generic  | 3         | 0.53%   |
| 5.4.0-72-generic  | 3         | 0.53%   |
| 5.4.0-39-generic  | 3         | 0.53%   |
| 5.4.0-33-generic  | 3         | 0.53%   |
| 5.4.0-28-generic  | 3         | 0.53%   |
| 5.3.0-53-generic  | 3         | 0.53%   |
| 5.3.0-24-generic  | 3         | 0.53%   |
| 5.3.0-23-generic  | 3         | 0.53%   |
| 5.11.0-43-generic | 3         | 0.53%   |
| 5.11.0-31-generic | 3         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 229       | 44.55%  |
| 5.3.0   | 72        | 14.01%  |
| 5.8.0   | 59        | 11.48%  |
| 5.11.0  | 52        | 10.12%  |
| 4.15.0  | 34        | 6.61%   |
| 5.13.0  | 32        | 6.23%   |
| 5.0.0   | 9         | 1.75%   |
| 4.4.0   | 6         | 1.17%   |
| 5.14.0  | 2         | 0.39%   |
| 4.18.0  | 2         | 0.39%   |
| 4.10.0  | 2         | 0.39%   |
| 5.9.3   | 1         | 0.19%   |
| 5.8.17  | 1         | 0.19%   |
| 5.8.16  | 1         | 0.19%   |
| 5.6.4   | 1         | 0.19%   |
| 5.5.8   | 1         | 0.19%   |
| 5.4.2   | 1         | 0.19%   |
| 5.17.1  | 1         | 0.19%   |
| 5.15.6  | 1         | 0.19%   |
| 5.15.34 | 1         | 0.19%   |
| 5.15.0  | 1         | 0.19%   |
| 5.12.3  | 1         | 0.19%   |
| 5.12.14 | 1         | 0.19%   |
| 4.8.0   | 1         | 0.19%   |
| 4.13.0  | 1         | 0.19%   |
| 3.14.79 | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 230       | 44.75%  |
| 5.3     | 72        | 14.01%  |
| 5.8     | 61        | 11.87%  |
| 5.11    | 52        | 10.12%  |
| 4.15    | 34        | 6.61%   |
| 5.13    | 32        | 6.23%   |
| 5.0     | 9         | 1.75%   |
| 4.4     | 6         | 1.17%   |
| 5.15    | 3         | 0.58%   |
| 5.14    | 2         | 0.39%   |
| 5.12    | 2         | 0.39%   |
| 4.18    | 2         | 0.39%   |
| 4.10    | 2         | 0.39%   |
| 5.9     | 1         | 0.19%   |
| 5.6     | 1         | 0.19%   |
| 5.5     | 1         | 0.19%   |
| 5.17    | 1         | 0.19%   |
| 4.8     | 1         | 0.19%   |
| 4.13    | 1         | 0.19%   |
| 3.14    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 449       | 91.26%  |
| i686    | 41        | 8.33%   |
| aarch64 | 2         | 0.41%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 483       | 98.17%  |
| Cinnamon   | 3         | 0.61%   |
| X-Cinnamon | 2         | 0.41%   |
| KDE5       | 2         | 0.41%   |
| i3         | 1         | 0.2%    |
| GNOME      | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 485       | 98.58%  |
| Tty     | 4         | 0.81%   |
| Wayland | 3         | 0.61%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 219       | 43.03%  |
| TDM     | 152       | 29.86%  |
| LightDM | 117       | 22.99%  |
| GDM     | 16        | 3.14%   |
| GDM3    | 3         | 0.59%   |
| SDDM    | 2         | 0.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 177       | 35.69%  |
| pt_BR   | 42        | 8.47%   |
| fr_FR   | 42        | 8.47%   |
| de_DE   | 40        | 8.06%   |
| en_GB   | 29        | 5.85%   |
| it_IT   | 24        | 4.84%   |
| Unknown | 19        | 3.83%   |
| es_ES   | 16        | 3.23%   |
| ru_RU   | 15        | 3.02%   |
| pl_PL   | 7         | 1.41%   |
| C       | 7         | 1.41%   |
| ru_UA   | 6         | 1.21%   |
| es_AR   | 4         | 0.81%   |
| en_IN   | 4         | 0.81%   |
| en_CA   | 4         | 0.81%   |
| en_AU   | 4         | 0.81%   |
| sv_SE   | 3         | 0.6%    |
| nl_NL   | 3         | 0.6%    |
| en_PH   | 3         | 0.6%    |
| de_CH   | 3         | 0.6%    |
| cs_CZ   | 3         | 0.6%    |
| zh_CN   | 2         | 0.4%    |
| fr_CA   | 2         | 0.4%    |
| fr_BE   | 2         | 0.4%    |
| fi_FI   | 2         | 0.4%    |
| es_PE   | 2         | 0.4%    |
| es_MX   | 2         | 0.4%    |
| es_CL   | 2         | 0.4%    |
| en_NZ   | 2         | 0.4%    |
| ca_ES   | 2         | 0.4%    |
| zh_TW   | 1         | 0.2%    |
| uk_UA   | 1         | 0.2%    |
| sk_SK   | 1         | 0.2%    |
| ro_RO   | 1         | 0.2%    |
| pt_PT   | 1         | 0.2%    |
| nl_BE   | 1         | 0.2%    |
| nb_NO   | 1         | 0.2%    |
| hu_HU   | 1         | 0.2%    |
| fr_CH   | 1         | 0.2%    |
| fa_IR   | 1         | 0.2%    |
| et_EE   | 1         | 0.2%    |
| es_VE   | 1         | 0.2%    |
| es_UY   | 1         | 0.2%    |
| es_PR   | 1         | 0.2%    |
| es_GT   | 1         | 0.2%    |
| es_EC   | 1         | 0.2%    |
| en_IL   | 1         | 0.2%    |
| en_IE   | 1         | 0.2%    |
| el_GR   | 1         | 0.2%    |
| de_LU   | 1         | 0.2%    |
| de_AT   | 1         | 0.2%    |
| da_DK   | 1         | 0.2%    |
| bg_BG   | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 268       | 53.92%  |
| EFI  | 229       | 46.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 454       | 91.72%  |
| Overlay | 14        | 2.83%   |
| Zfs     | 8         | 1.62%   |
| Btrfs   | 8         | 1.62%   |
| Unknown | 5         | 1.01%   |
| Xfs     | 3         | 0.61%   |
| Ext3    | 3         | 0.61%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 242       | 48.59%  |
| GPT     | 161       | 32.33%  |
| MBR     | 95        | 19.08%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 445       | 89%     |
| Yes       | 55        | 11%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 343       | 69.01%  |
| Yes       | 154       | 30.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Hewlett-Packard                  | 97        | 19.72%  |
| Lenovo                           | 96        | 19.51%  |
| Dell                             | 81        | 16.46%  |
| ASUSTek Computer                 | 49        | 9.96%   |
| Acer                             | 37        | 7.52%   |
| Toshiba                          | 21        | 4.27%   |
| Samsung Electronics              | 12        | 2.44%   |
| MSI                              | 12        | 2.44%   |
| Sony                             | 10        | 2.03%   |
| Fujitsu                          | 7         | 1.42%   |
| Notebook                         | 6         | 1.22%   |
| Positivo                         | 4         | 0.81%   |
| Packard Bell                     | 4         | 0.81%   |
| Unknown                          | 4         | 0.81%   |
| TUXEDO                           | 3         | 0.61%   |
| Quanta                           | 3         | 0.61%   |
| Clevo                            | 3         | 0.61%   |
| Apple                            | 3         | 0.61%   |
| Wortmann AG                      | 2         | 0.41%   |
| TrekStor                         | 2         | 0.41%   |
| System76                         | 2         | 0.41%   |
| Medion                           | 2         | 0.41%   |
| GPD                              | 2         | 0.41%   |
| Digibras                         | 2         | 0.41%   |
| TPVAOC                           | 1         | 0.2%    |
| Timi                             | 1         | 0.2%    |
| Thomson                          | 1         | 0.2%    |
| Teclast                          | 1         | 0.2%    |
| Star Labs                        | 1         | 0.2%    |
| Semp Toshiba                     | 1         | 0.2%    |
| SECO                             | 1         | 0.2%    |
| Polaroid                         | 1         | 0.2%    |
| Pine Microsystems                | 1         | 0.2%    |
| ONE-NETBOOK TECHNOLOGY           | 1         | 0.2%    |
| NEC Computers                    | 1         | 0.2%    |
| Metabox                          | 1         | 0.2%    |
| LG Electronics                   | 1         | 0.2%    |
| IPASON                           | 1         | 0.2%    |
| Intel                            | 1         | 0.2%    |
| Hannspree                        | 1         | 0.2%    |
| Hampoo                           | 1         | 0.2%    |
| Fujitsu Siemens                  | 1         | 0.2%    |
| FUJITSU CLIENT COMPUTING LIMITED | 1         | 0.2%    |
| EUROCOM                          | 1         | 0.2%    |
| Entroware                        | 1         | 0.2%    |
| eMachines                        | 1         | 0.2%    |
| Cube                             | 1         | 0.2%    |
| Chuwi                            | 1         | 0.2%    |
| AZW                              | 1         | 0.2%    |
| ARCELIK                          | 1         | 0.2%    |
| AMI                              | 1         | 0.2%    |
| Advent                           | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 10        | 2.03%   |
| HP Pavilion g6                      | 5         | 1.02%   |
| HP Pavilion dv7                     | 5         | 1.02%   |
| Dell Latitude E6420                 | 5         | 1.02%   |
| Dell Latitude E6410                 | 5         | 1.02%   |
| HP Notebook                         | 3         | 0.61%   |
| Dell Precision M4800                | 3         | 0.61%   |
| Dell Latitude E6500                 | 3         | 0.61%   |
| TrekStor Surfbook A13B              | 2         | 0.41%   |
| Toshiba Satellite A200              | 2         | 0.41%   |
| Samsung 350V5C/351V5C/3540VC/3440VC | 2         | 0.41%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS | 2         | 0.41%   |
| Lenovo IdeaPad 3 15IIL05 81WE       | 2         | 0.41%   |
| HP Pavilion dm1                     | 2         | 0.41%   |
| HP Pavilion 17                      | 2         | 0.41%   |
| HP EliteBook 8470p                  | 2         | 0.41%   |
| HP EliteBook 840 G2                 | 2         | 0.41%   |
| HP EliteBook 2570p                  | 2         | 0.41%   |
| HP 250 G1                           | 2         | 0.41%   |
| Digibras NH4CU53                    | 2         | 0.41%   |
| Dell Vostro 3350                    | 2         | 0.41%   |
| Dell Studio 1558                    | 2         | 0.41%   |
| Dell Latitude E7250                 | 2         | 0.41%   |
| Dell Latitude E6520                 | 2         | 0.41%   |
| Dell Latitude E6430                 | 2         | 0.41%   |
| Dell Inspiron 3421                  | 2         | 0.41%   |
| ASUS ZenBook UX431DA_UM431DA        | 2         | 0.41%   |
| ASUS X553MA                         | 2         | 0.41%   |
| ASUS X541SA                         | 2         | 0.41%   |
| ASUS 1011PX                         | 2         | 0.41%   |
| Acer Nitro AN515-54                 | 2         | 0.41%   |
| Acer Aspire ES1-523                 | 2         | 0.41%   |
| Acer Aspire 7750G                   | 2         | 0.41%   |
| Acer Aspire 3000                    | 2         | 0.41%   |
| Wortmann AG TERRA_MOBILE_1749       | 1         | 0.2%    |
| Wortmann AG MOBILE 1745             | 1         | 0.2%    |
| TUXEDO Pulse 14 Gen1                | 1         | 0.2%    |
| TUXEDO InfinityBook Pro 14 Gen6     | 1         | 0.2%    |
| TPVAOC AA183M                       | 1         | 0.2%    |
| Toshiba Satellite Pro L500          | 1         | 0.2%    |
| Toshiba Satellite Pro C660          | 1         | 0.2%    |
| Toshiba Satellite P755              | 1         | 0.2%    |
| Toshiba Satellite M500              | 1         | 0.2%    |
| Toshiba Satellite M115              | 1         | 0.2%    |
| Toshiba Satellite L755D             | 1         | 0.2%    |
| Toshiba Satellite L655              | 1         | 0.2%    |
| Toshiba Satellite L350D             | 1         | 0.2%    |
| Toshiba Satellite L350              | 1         | 0.2%    |
| Toshiba Satellite C850-BMK          | 1         | 0.2%    |
| Toshiba Satellite C70D-B            | 1         | 0.2%    |
| Toshiba Satellite C675              | 1         | 0.2%    |
| Toshiba Satellite C665              | 1         | 0.2%    |
| Toshiba Satellite C660              | 1         | 0.2%    |
| Toshiba Satellite C55-A             | 1         | 0.2%    |
| Toshiba Satellite A135              | 1         | 0.2%    |
| Toshiba Satellite A100              | 1         | 0.2%    |
| Toshiba PORTEGE R500                | 1         | 0.2%    |
| Toshiba NB505                       | 1         | 0.2%    |
| Timi TM1604                         | 1         | 0.2%    |
| Thomson NEO14A-4BK64                | 1         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 55        | 11.18%  |
| Dell Latitude         | 33        | 6.71%   |
| HP Pavilion           | 27        | 5.49%   |
| Acer Aspire           | 27        | 5.49%   |
| Lenovo IdeaPad        | 22        | 4.47%   |
| Toshiba Satellite     | 19        | 3.86%   |
| HP EliteBook          | 17        | 3.46%   |
| Dell Inspiron         | 14        | 2.85%   |
| Dell Precision        | 12        | 2.44%   |
| Unknown               | 10        | 2.03%   |
| HP ProBook            | 9         | 1.83%   |
| Dell XPS              | 9         | 1.83%   |
| Fujitsu LIFEBOOK      | 7         | 1.42%   |
| Dell Vostro           | 7         | 1.42%   |
| HP 250                | 6         | 1.22%   |
| HP ZBook              | 5         | 1.02%   |
| HP Laptop             | 5         | 1.02%   |
| ASUS VivoBook         | 5         | 1.02%   |
| Packard Bell EasyNote | 4         | 0.81%   |
| HP Compaq             | 4         | 0.81%   |
| Lenovo Legion         | 3         | 0.61%   |
| Lenovo G580           | 3         | 0.61%   |
| HP Notebook           | 3         | 0.61%   |
| HP ENVY               | 3         | 0.61%   |
| Dell Studio           | 3         | 0.61%   |
| Acer TravelMate       | 3         | 0.61%   |
| Acer Nitro            | 3         | 0.61%   |
| TrekStor Surfbook     | 2         | 0.41%   |
| Samsung 350V5C        | 2         | 0.41%   |
| Lenovo ThinkBook      | 2         | 0.41%   |
| Lenovo Flex           | 2         | 0.41%   |
| HP Stream             | 2         | 0.41%   |
| HP Mini               | 2         | 0.41%   |
| HP 255                | 2         | 0.41%   |
| Digibras NH4CU53      | 2         | 0.41%   |
| ASUS ZenBook          | 2         | 0.41%   |
| ASUS X553MA           | 2         | 0.41%   |
| ASUS X541SA           | 2         | 0.41%   |
| ASUS ROG              | 2         | 0.41%   |
| ASUS 1011PX           | 2         | 0.41%   |
| Wortmann AG TERRA     | 1         | 0.2%    |
| Wortmann AG MOBILE    | 1         | 0.2%    |
| TUXEDO Pulse          | 1         | 0.2%    |
| TUXEDO InfinityBook   | 1         | 0.2%    |
| TPVAOC AA183M         | 1         | 0.2%    |
| Toshiba PORTEGE       | 1         | 0.2%    |
| Toshiba NB505         | 1         | 0.2%    |
| Timi TM1604           | 1         | 0.2%    |
| Thomson NEO14A-4BK64  | 1         | 0.2%    |
| Teclast F15S          | 1         | 0.2%    |
| System76 Serval       | 1         | 0.2%    |
| System76 Galago       | 1         | 0.2%    |
| Star Labs LabTop      | 1         | 0.2%    |
| Sony VPCS12X9E        | 1         | 0.2%    |
| Sony VPCF13Z1R        | 1         | 0.2%    |
| Sony VPCF1290X        | 1         | 0.2%    |
| Sony VPCEL3S1E        | 1         | 0.2%    |
| Sony VPCEH1S1E        | 1         | 0.2%    |
| Sony VPCEB1S1E        | 1         | 0.2%    |
| Sony VGN-FZ4000E      | 1         | 0.2%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 61        | 12.4%   |
| 2012    | 48        | 9.76%   |
| 2019    | 43        | 8.74%   |
| 2013    | 39        | 7.93%   |
| 2020    | 38        | 7.72%   |
| 2018    | 35        | 7.11%   |
| 2008    | 34        | 6.91%   |
| 2010    | 33        | 6.71%   |
| 2015    | 32        | 6.5%    |
| 2017    | 26        | 5.28%   |
| 2016    | 25        | 5.08%   |
| 2014    | 24        | 4.88%   |
| 2009    | 15        | 3.05%   |
| 2007    | 15        | 3.05%   |
| 2021    | 14        | 2.85%   |
| 2006    | 5         | 1.02%   |
| 2005    | 2         | 0.41%   |
| Unknown | 2         | 0.41%   |
| 2003    | 1         | 0.2%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 492       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 448       | 90.51%  |
| Enabled  | 47        | 9.49%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 491       | 99.8%   |
| Yes  | 1         | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 131       | 26.36%  |
| 4.01-8.0    | 127       | 25.55%  |
| 16.01-24.0  | 69        | 13.88%  |
| 8.01-16.0   | 68        | 13.68%  |
| 1.01-2.0    | 39        | 7.85%   |
| 32.01-64.0  | 29        | 5.84%   |
| 2.01-3.0    | 11        | 2.21%   |
| 64.01-256.0 | 9         | 1.81%   |
| 0.51-1.0    | 9         | 1.81%   |
| 24.01-32.0  | 4         | 0.8%    |
| 0.01-0.5    | 1         | 0.2%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 205       | 38.75%  |
| 2.01-3.0   | 124       | 23.44%  |
| 4.01-8.0   | 60        | 11.34%  |
| 0.51-1.0   | 59        | 11.15%  |
| 3.01-4.0   | 58        | 10.96%  |
| 8.01-16.0  | 14        | 2.65%   |
| 0.01-0.5   | 7         | 1.32%   |
| 32.01-64.0 | 1         | 0.19%   |
| 24.01-32.0 | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 358       | 70.89%  |
| 2      | 127       | 25.15%  |
| 3      | 14        | 2.77%   |
| 4      | 3         | 0.59%   |
| 0      | 2         | 0.4%    |
| 5      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 258       | 52.23%  |
| Yes       | 236       | 47.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 428       | 86.99%  |
| No        | 64        | 13.01%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 479       | 97.16%  |
| No        | 14        | 2.84%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 354       | 71.52%  |
| No        | 141       | 28.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 62        | 12.53%  |
| Germany     | 59        | 11.92%  |
| Brazil      | 52        | 10.51%  |
| France      | 47        | 9.49%   |
| Italy       | 28        | 5.66%   |
| UK          | 27        | 5.45%   |
| Spain       | 23        | 4.65%   |
| Russia      | 23        | 4.65%   |
| Ukraine     | 9         | 1.82%   |
| Netherlands | 9         | 1.82%   |
| Switzerland | 8         | 1.62%   |
| Turkey      | 7         | 1.41%   |
| India       | 7         | 1.41%   |
| Canada      | 7         | 1.41%   |
| Poland      | 6         | 1.21%   |
| Belgium     | 6         | 1.21%   |
| Sweden      | 5         | 1.01%   |
| Romania     | 5         | 1.01%   |
| Greece      | 5         | 1.01%   |
| Finland     | 5         | 1.01%   |
| Czechia     | 5         | 1.01%   |
| Argentina   | 5         | 1.01%   |
| Thailand    | 4         | 0.81%   |
| Portugal    | 4         | 0.81%   |
| Norway      | 4         | 0.81%   |
| Mexico      | 4         | 0.81%   |
| Indonesia   | 4         | 0.81%   |
| Chile       | 4         | 0.81%   |
| Australia   | 4         | 0.81%   |
| Philippines | 3         | 0.61%   |
| China       | 3         | 0.61%   |
| Austria     | 3         | 0.61%   |
| Vietnam     | 2         | 0.4%    |
| Venezuela   | 2         | 0.4%    |
| Taiwan      | 2         | 0.4%    |
| South Korea | 2         | 0.4%    |
| Slovakia    | 2         | 0.4%    |
| Peru        | 2         | 0.4%    |
| New Zealand | 2         | 0.4%    |
| Luxembourg  | 2         | 0.4%    |
| Kenya       | 2         | 0.4%    |
| Ireland     | 2         | 0.4%    |
| Ecuador     | 2         | 0.4%    |
| Denmark     | 2         | 0.4%    |
| Croatia     | 2         | 0.4%    |
| Belarus     | 2         | 0.4%    |
| Uruguay     | 1         | 0.2%    |
| Sudan       | 1         | 0.2%    |
| Sri Lanka   | 1         | 0.2%    |
| Serbia      | 1         | 0.2%    |
| RГ©union  | 1         | 0.2%    |
| Puerto Rico | 1         | 0.2%    |
| Montenegro  | 1         | 0.2%    |
| Malaysia    | 1         | 0.2%    |
| Lithuania   | 1         | 0.2%    |
| Latvia      | 1         | 0.2%    |
| Ivory Coast | 1         | 0.2%    |
| Israel      | 1         | 0.2%    |
| Iran        | 1         | 0.2%    |
| Hungary     | 1         | 0.2%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Sao Paulo          | 10        | 1.93%   |
| Paris              | 9         | 1.74%   |
| Moscow             | 7         | 1.35%   |
| Berlin             | 7         | 1.35%   |
| St Petersburg      | 5         | 0.97%   |
| Rome               | 5         | 0.97%   |
| Rio de Janeiro     | 5         | 0.97%   |
| Itatiba            | 5         | 0.97%   |
| Madrid             | 4         | 0.77%   |
| Kyiv               | 4         | 0.77%   |
| Barcelona          | 4         | 0.77%   |
| Vienna             | 3         | 0.58%   |
| Thessaloniki       | 3         | 0.58%   |
| JundiaГ­         | 3         | 0.58%   |
| Essen              | 3         | 0.58%   |
| Ely                | 3         | 0.58%   |
| Bucharest          | 3         | 0.58%   |
| Bengaluru          | 3         | 0.58%   |
| Xining             | 2         | 0.39%   |
| Toulouse           | 2         | 0.39%   |
| Sydney             | 2         | 0.39%   |
| Srednyaya Akhtuba  | 2         | 0.39%   |
| Seoul              | 2         | 0.39%   |
| Santiago           | 2         | 0.39%   |
| Raleigh            | 2         | 0.39%   |
| Quezon City        | 2         | 0.39%   |
| Porto Alegre       | 2         | 0.39%   |
| Philadelphia       | 2         | 0.39%   |
| Oslo               | 2         | 0.39%   |
| Offenbach          | 2         | 0.39%   |
| Nairobi            | 2         | 0.39%   |
| Munich             | 2         | 0.39%   |
| Milan              | 2         | 0.39%   |
| Marseille          | 2         | 0.39%   |
| Manchester         | 2         | 0.39%   |
| Luxembourg         | 2         | 0.39%   |
| Los Angeles        | 2         | 0.39%   |
| London             | 2         | 0.39%   |
| Lisbon             | 2         | 0.39%   |
| Lima               | 2         | 0.39%   |
| Le Kremlin-Bicetre | 2         | 0.39%   |
| Lancaster          | 2         | 0.39%   |
| Krasnodar          | 2         | 0.39%   |
| Ho Chi Minh City   | 2         | 0.39%   |
| Herriman           | 2         | 0.39%   |
| Helsinki           | 2         | 0.39%   |
| Hamburg            | 2         | 0.39%   |
| Evansville         | 2         | 0.39%   |
| Durham             | 2         | 0.39%   |
| Dublin             | 2         | 0.39%   |
| Dresden            | 2         | 0.39%   |
| Cologne            | 2         | 0.39%   |
| Chicago            | 2         | 0.39%   |
| Chennai            | 2         | 0.39%   |
| Bordeaux           | 2         | 0.39%   |
| Bern               | 2         | 0.39%   |
| Basel              | 2         | 0.39%   |
| Ban San Sai        | 2         | 0.39%   |
| Athens             | 2         | 0.39%   |
| Ankara             | 2         | 0.39%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 93        | 119    | 15.25%  |
| Samsung Electronics       | 92        | 120    | 15.08%  |
| WDC                       | 77        | 88     | 12.62%  |
| Toshiba                   | 57        | 73     | 9.34%   |
| Kingston                  | 38        | 45     | 6.23%   |
| Hitachi                   | 35        | 38     | 5.74%   |
| Unknown                   | 34        | 44     | 5.57%   |
| SanDisk                   | 26        | 33     | 4.26%   |
| Crucial                   | 25        | 39     | 4.1%    |
| SK Hynix                  | 22        | 29     | 3.61%   |
| Intel                     | 12        | 16     | 1.97%   |
| Fujitsu                   | 10        | 11     | 1.64%   |
| HGST                      | 9         | 11     | 1.48%   |
| A-DATA Technology         | 8         | 8      | 1.31%   |
| Micron Technology         | 7         | 8      | 1.15%   |
| China                     | 7         | 8      | 1.15%   |
| PNY                       | 6         | 6      | 0.98%   |
| KIOXIA                    | 6         | 6      | 0.98%   |
| Transcend                 | 3         | 7      | 0.49%   |
| SPCC                      | 3         | 6      | 0.49%   |
| Silicon Motion            | 3         | 3      | 0.49%   |
| Phison                    | 3         | 3      | 0.49%   |
| Intenso                   | 3         | 3      | 0.49%   |
| Vaseky                    | 2         | 2      | 0.33%   |
| Patriot                   | 2         | 2      | 0.33%   |
| IBM/Hitachi               | 2         | 2      | 0.33%   |
| FORESEE                   | 2         | 2      | 0.33%   |
| Apacer                    | 2         | 3      | 0.33%   |
| Verbatim                  | 1         | 1      | 0.16%   |
| USB2.0                    | 1         | 1      | 0.16%   |
| Super Talent              | 1         | 1      | 0.16%   |
| Solid State Storage       | 1         | 1      | 0.16%   |
| SMART                     | 1         | 1      | 0.16%   |
| Realtek Semiconductor     | 1         | 1      | 0.16%   |
| PLEXTOR                   | 1         | 1      | 0.16%   |
| OCZ                       | 1         | 1      | 0.16%   |
| Netac                     | 1         | 1      | 0.16%   |
| Micron/Crucial Technology | 1         | 1      | 0.16%   |
| LITEONIT                  | 1         | 2      | 0.16%   |
| LITEON                    | 1         | 1      | 0.16%   |
| LaCie                     | 1         | 1      | 0.16%   |
| KingSpec                  | 1         | 1      | 0.16%   |
| JMicron                   | 1         | 1      | 0.16%   |
| faspeed                   | 1         | 1      | 0.16%   |
| Eluktro                   | 1         | 1      | 0.16%   |
| DREVO                     | 1         | 1      | 0.16%   |
| Corsair                   | 1         | 2      | 0.16%   |
| BLUERAY                   | 1         | 1      | 0.16%   |
| Apricorn                  | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 10        | 1.58%   |
| Seagate ST1000LM035-1RK172 1TB       | 10        | 1.58%   |
| Toshiba MQ01ABF050 500GB             | 9         | 1.42%   |
| Kingston SA400S37240G 240GB SSD      | 9         | 1.42%   |
| Kingston SA400S37120G 120GB SSD      | 8         | 1.26%   |
| Seagate ST500LT012-9WS142 500GB      | 7         | 1.11%   |
| Seagate ST320LT007-9ZV142 320GB      | 7         | 1.11%   |
| Unknown MMC Card  64GB               | 6         | 0.95%   |
| Toshiba MQ01ABD100 1TB               | 6         | 0.95%   |
| Seagate ST500LT012-1DG142 500GB      | 6         | 0.95%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 6         | 0.95%   |
| Samsung SSD 860 EVO 500GB            | 6         | 0.95%   |
| Hitachi HTS545050B9A300 500GB        | 6         | 0.95%   |
| Toshiba MQ04ABF100 1TB               | 5         | 0.79%   |
| Seagate ST9500325AS 500GB            | 5         | 0.79%   |
| Seagate ST1000LM049-2GH172 1TB       | 5         | 0.79%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 5         | 0.79%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 0.63%   |
| Seagate ST2000LM007-1R8174 2TB       | 4         | 0.63%   |
| Samsung SSD 850 EVO 500GB            | 4         | 0.63%   |
| Kingston SV300S37A120G 120GB SSD     | 4         | 0.63%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 0.63%   |
| Hitachi HTS547575A9E384 752GB        | 4         | 0.63%   |
| HGST HTS721010A9E630 1TB             | 4         | 0.63%   |
| Crucial CT250BX100SSD1 250GB         | 4         | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 3         | 0.47%   |
| WDC WD3200BPVT-80JJ5T0 320GB         | 3         | 0.47%   |
| WDC WD10SPZX-21Z10T0 1TB             | 3         | 0.47%   |
| Unknown MMC Card  16GB               | 3         | 0.47%   |
| Unknown MMC Card  128GB              | 3         | 0.47%   |
| Toshiba MQ01ACF032 320GB             | 3         | 0.47%   |
| Toshiba MQ01ABD050 500GB             | 3         | 0.47%   |
| Seagate ST9250410AS 250GB            | 3         | 0.47%   |
| Seagate ST2000LM015-2E8174 2TB       | 3         | 0.47%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 3         | 0.47%   |
| Seagate ST1000LM014-1EJ164 1TB       | 3         | 0.47%   |
| Samsung SSD 860 PRO 512GB            | 3         | 0.47%   |
| PNY CS900 240GB SSD                  | 3         | 0.47%   |
| Intel SSDPEKNW512G8 512GB            | 3         | 0.47%   |
| Hitachi HTS547564A9E384 640GB        | 3         | 0.47%   |
| Hitachi HTS545050A7E380 500GB        | 3         | 0.47%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 0.47%   |
| Hitachi HTS542516K9SA00 160GB        | 3         | 0.47%   |
| Crucial CT750MX300SSD1 752GB         | 3         | 0.47%   |
| Crucial CT500MX500SSD1 500GB         | 3         | 0.47%   |
| China SSD 120GB                      | 3         | 0.47%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.32%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.32%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 2         | 0.32%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 2         | 0.32%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 0.32%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB | 2         | 0.32%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 2         | 0.32%   |
| WDC PC SN520 SDAPNUW-256G-1202 256GB | 2         | 0.32%   |
| Unknown SD/MMC/MS PRO 394GB          | 2         | 0.32%   |
| Unknown MMC Card  4GB                | 2         | 0.32%   |
| Unknown DA4064  64GB                 | 2         | 0.32%   |
| Transcend TS512GMTS430S 512GB SSD    | 2         | 0.32%   |
| Toshiba THNSNJ256G8NY 256GB SSD      | 2         | 0.32%   |
| Toshiba NVMe SSD Drive 512GB         | 2         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 93        | 117    | 36.76%  |
| WDC                 | 53        | 60     | 20.95%  |
| Toshiba             | 44        | 56     | 17.39%  |
| Hitachi             | 35        | 38     | 13.83%  |
| Fujitsu             | 10        | 11     | 3.95%   |
| HGST                | 9         | 11     | 3.56%   |
| Samsung Electronics | 4         | 4      | 1.58%   |
| Unknown             | 2         | 2      | 0.79%   |
| IBM/Hitachi         | 2         | 2      | 0.79%   |
| Apricorn            | 1         | 1      | 0.4%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 59        | 76     | 27.44%  |
| Kingston            | 35        | 42     | 16.28%  |
| Crucial             | 23        | 37     | 10.7%   |
| SanDisk             | 19        | 25     | 8.84%   |
| WDC                 | 10        | 11     | 4.65%   |
| A-DATA Technology   | 8         | 8      | 3.72%   |
| Toshiba             | 6         | 8      | 2.79%   |
| SK Hynix            | 6         | 9      | 2.79%   |
| PNY                 | 6         | 6      | 2.79%   |
| China               | 6         | 7      | 2.79%   |
| Intel               | 5         | 8      | 2.33%   |
| Transcend           | 3         | 7      | 1.4%    |
| SPCC                | 3         | 6      | 1.4%    |
| Intenso             | 3         | 3      | 1.4%    |
| Vaseky              | 2         | 2      | 0.93%   |
| Micron Technology   | 2         | 3      | 0.93%   |
| FORESEE             | 2         | 2      | 0.93%   |
| Apacer              | 2         | 3      | 0.93%   |
| Verbatim            | 1         | 1      | 0.47%   |
| Super Talent        | 1         | 1      | 0.47%   |
| SMART               | 1         | 1      | 0.47%   |
| Seagate             | 1         | 1      | 0.47%   |
| PLEXTOR             | 1         | 1      | 0.47%   |
| Patriot             | 1         | 1      | 0.47%   |
| OCZ                 | 1         | 1      | 0.47%   |
| Netac               | 1         | 1      | 0.47%   |
| LITEONIT            | 1         | 2      | 0.47%   |
| LITEON              | 1         | 1      | 0.47%   |
| KingSpec            | 1         | 1      | 0.47%   |
| JMicron             | 1         | 1      | 0.47%   |
| Eluktro             | 1         | 1      | 0.47%   |
| DREVO               | 1         | 1      | 0.47%   |
| BLUERAY             | 1         | 1      | 0.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 243       | 302    | 41.54%  |
| SSD     | 200       | 279    | 34.19%  |
| NVMe    | 105       | 130    | 17.95%  |
| MMC     | 32        | 42     | 5.47%   |
| Unknown | 5         | 5      | 0.85%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 403       | 571    | 72.88%  |
| NVMe | 105       | 130    | 18.99%  |
| MMC  | 32        | 42     | 5.79%   |
| SAS  | 13        | 15     | 2.35%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 314       | 394    | 71.04%  |
| 0.51-1.0   | 107       | 150    | 24.21%  |
| 1.01-2.0   | 16        | 30     | 3.62%   |
| 3.01-4.0   | 4         | 5      | 0.9%    |
| 4.01-10.0  | 1         | 2      | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 153       | 30.3%   |
| 251-500        | 141       | 27.92%  |
| 501-1000       | 73        | 14.46%  |
| 51-100         | 44        | 8.71%   |
| 1001-2000      | 29        | 5.74%   |
| 1-20           | 28        | 5.54%   |
| 21-50          | 20        | 3.96%   |
| More than 3000 | 9         | 1.78%   |
| 2001-3000      | 8         | 1.58%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 192       | 36.85%  |
| 21-50          | 88        | 16.89%  |
| 101-250        | 79        | 15.16%  |
| 51-100         | 74        | 14.2%   |
| 251-500        | 48        | 9.21%   |
| 501-1000       | 28        | 5.37%   |
| 1001-2000      | 6         | 1.15%   |
| More than 3000 | 3         | 0.58%   |
| 2001-3000      | 3         | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST320LT007-9ZV142 320GB                  | 5         | 5      | 9.8%    |
| Hitachi HTS542516K9SA00 160GB                    | 3         | 3      | 5.88%   |
| Toshiba MK7559GSXP 752GB                         | 2         | 2      | 3.92%   |
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 3.92%   |
| Seagate ST1000LM049-2GH172 1TB                   | 2         | 2      | 3.92%   |
| Hitachi HTS547575A9E384 752GB                    | 2         | 2      | 3.92%   |
| Hitachi HTS545050B9A300 500GB                    | 2         | 2      | 3.92%   |
| WDC WD7500BPVT-75HXZT1 752GB                     | 1         | 1      | 1.96%   |
| WDC WD7500BPVT-22A1YT0 752GB                     | 1         | 1      | 1.96%   |
| WDC WD7500BPKT-75PK4T0 752GB                     | 1         | 1      | 1.96%   |
| WDC WD5000LPVX-22V0TT0 500GB                     | 1         | 1      | 1.96%   |
| WDC WD5000BPKT-75PK4T0 500GB                     | 1         | 2      | 1.96%   |
| WDC WD3200BEVT-60ZCT1 320GB                      | 1         | 1      | 1.96%   |
| WDC WD10JPCX-24UE4T0 1TB                         | 1         | 1      | 1.96%   |
| Vaseky V820/1TB SSD                              | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 1.96%   |
| Toshiba MK5065GSX 500GB                          | 1         | 1      | 1.96%   |
| Toshiba MK2555GSX 250GB                          | 1         | 1      | 1.96%   |
| SK Hynix BC501 HFM256GDJTNG-8310A 256GB          | 1         | 4      | 1.96%   |
| Seagate ST98823AS 80GB                           | 1         | 1      | 1.96%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.96%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 1.96%   |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 1.96%   |
| Seagate ST9250410AS 250GB                        | 1         | 1      | 1.96%   |
| Seagate ST9160821AS 160GB                        | 1         | 1      | 1.96%   |
| Seagate ST320LT012-9WS14C 320GB                  | 1         | 1      | 1.96%   |
| SanDisk SD7SN3Q256G1002 256GB SSD                | 1         | 1      | 1.96%   |
| Samsung Electronics SSD 960 PRO 2TB              | 1         | 4      | 1.96%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 1.96%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 1.96%   |
| OCZ VERTEX450 128GB SSD                          | 1         | 1      | 1.96%   |
| Intel SSDSC2KF256H6L 256GB                       | 1         | 1      | 1.96%   |
| Intel SSDSA2M160G2GN 160GB                       | 1         | 1      | 1.96%   |
| IBM/Hitachi IC25N060ATMR04-0 64GB                | 1         | 1      | 1.96%   |
| Hitachi HTS722016K9A300 160GB                    | 1         | 1      | 1.96%   |
| Fujitsu MHZ2320BH G1 320GB                       | 1         | 1      | 1.96%   |
| Eluktro TRO-SSD7-500GB-PRO                       | 1         | 1      | 1.96%   |
| China SSD 120GB                                  | 1         | 1      | 1.96%   |
| Apricorn SATAWire 6G                             | 1         | 1      | 1.96%   |
| A-DATA Technology SP900 64GB SSD                 | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 31.37%  |
| Hitachi             | 8         | 8      | 15.69%  |
| WDC                 | 7         | 8      | 13.73%  |
| Toshiba             | 5         | 5      | 9.8%    |
| Samsung Electronics | 3         | 6      | 5.88%   |
| Intel               | 2         | 2      | 3.92%   |
| Vaseky              | 1         | 1      | 1.96%   |
| SK Hynix            | 1         | 4      | 1.96%   |
| SanDisk             | 1         | 1      | 1.96%   |
| OCZ                 | 1         | 1      | 1.96%   |
| IBM/Hitachi         | 1         | 1      | 1.96%   |
| Fujitsu             | 1         | 1      | 1.96%   |
| Eluktro             | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| Apricorn            | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 16     | 40%     |
| Hitachi             | 8         | 8      | 20%     |
| WDC                 | 7         | 8      | 17.5%   |
| Toshiba             | 5         | 5      | 12.5%   |
| Samsung Electronics | 1         | 1      | 2.5%    |
| IBM/Hitachi         | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |
| Apricorn            | 1         | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 40        | 41     | 78.43%  |
| SSD  | 9         | 9      | 17.65%  |
| NVMe | 2         | 8      | 3.92%   |

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
| Detected | 259       | 411    | 49.05%  |
| Works    | 218       | 289    | 41.29%  |
| Malfunc  | 51        | 58     | 9.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 368       | 67.65%  |
| AMD                              | 61        | 11.21%  |
| Samsung Electronics              | 32        | 5.88%   |
| Sandisk                          | 20        | 3.68%   |
| SK Hynix                         | 15        | 2.76%   |
| Toshiba America Info Systems     | 9         | 1.65%   |
| Silicon Integrated Systems [SiS] | 8         | 1.47%   |
| Micron Technology                | 5         | 0.92%   |
| Silicon Motion                   | 4         | 0.74%   |
| Phison Electronics               | 4         | 0.74%   |
| KIOXIA                           | 4         | 0.74%   |
| Micron/Crucial Technology        | 3         | 0.55%   |
| Kingston Technology Company      | 3         | 0.55%   |
| VIA Technologies                 | 2         | 0.37%   |
| Solid State Storage Technology   | 2         | 0.37%   |
| Union Memory (Shenzhen)          | 1         | 0.18%   |
| Realtek Semiconductor            | 1         | 0.18%   |
| Nvidia                           | 1         | 0.18%   |
| JMicron Technology               | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 53        | 8.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 47        | 7.89%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 42        | 7.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 30        | 5.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 27        | 4.53%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 20        | 3.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18        | 3.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 18        | 3.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 15        | 2.52%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 2.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 15        | 2.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 14        | 2.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 13        | 2.18%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 1.85%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 1.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 11        | 1.85%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 10        | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 1.51%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 8         | 1.34%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 8         | 1.34%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 7         | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.01%   |
| Intel SSD 660P Series                                                            | 6         | 1.01%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 1.01%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 6         | 1.01%   |
| AMD SB600 IDE                                                                    | 6         | 1.01%   |
| SK Hynix BC511                                                                   | 5         | 0.84%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 5         | 0.84%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 5         | 0.84%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 5         | 0.84%   |
| Micron Non-Volatile memory controller                                            | 5         | 0.84%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 5         | 0.84%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 5         | 0.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 4         | 0.67%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 0.67%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 4         | 0.67%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.67%   |
| KIOXIA Non-Volatile memory controller                                            | 4         | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 0.67%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.67%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 4         | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 4         | 0.67%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 4         | 0.67%   |
| SK Hynix Gold P31 SSD                                                            | 3         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 0.5%    |
| Sandisk PC SN520 NVMe SSD                                                        | 3         | 0.5%    |
| Phison E12 NVMe Controller                                                       | 3         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.5%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 3         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 3         | 0.5%    |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.34%   |
| Toshiba America Info Systems NVMe Controller                                     | 2         | 0.34%   |
| Solid State Storage Non-Volatile memory controller                               | 2         | 0.34%   |
| SK Hynix Non-Volatile memory controller                                          | 2         | 0.34%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 0.34%   |
| Kingston Company Company Non-Volatile memory controller                          | 2         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 377       | 66.26%  |
| NVMe | 104       | 18.28%  |
| IDE  | 57        | 10.02%  |
| RAID | 31        | 5.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 417       | 84.76%  |
| AMD          | 72        | 14.63%  |
| ARM          | 2         | 0.41%   |
| CentaurHauls | 1         | 0.2%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 1.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 1.42%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.42%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 7         | 1.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 1.22%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 1.22%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 1.22%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.02%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 1.02%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 5         | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.02%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 1.02%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.02%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 1.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 5         | 1.02%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.02%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 4         | 0.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.81%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 4         | 0.81%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 4         | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.81%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.81%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.81%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 4         | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.81%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 4         | 0.81%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 4         | 0.81%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 4         | 0.81%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.81%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 3         | 0.61%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.61%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 3         | 0.61%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 0.61%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.61%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.61%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.61%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.61%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.61%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.61%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 3         | 0.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.61%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 0.61%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 3         | 0.61%   |
| Intel Core i3 CPU M 350 @ 2.27GHz             | 3         | 0.61%   |
| Intel Core Duo CPU T2450 @ 2.00GHz            | 3         | 0.61%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 3         | 0.61%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 3         | 0.61%   |
| Intel Celeron CPU 1037U @ 1.80GHz             | 3         | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 3         | 0.61%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 3         | 0.61%   |
| AMD Mobile Sempron Processor 3000+            | 3         | 0.61%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 2         | 0.41%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.41%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 2         | 0.41%   |
| Intel Pentium 3556U @ 1.70GHz                 | 2         | 0.41%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.41%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 2         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 114       | 23.17%  |
| Intel Core i5                  | 112       | 22.76%  |
| Intel Core i3                  | 43        | 8.74%   |
| Intel Celeron                  | 33        | 6.71%   |
| Intel Core 2 Duo               | 28        | 5.69%   |
| Other                          | 19        | 3.86%   |
| Intel Pentium                  | 18        | 3.66%   |
| Intel Atom                     | 17        | 3.46%   |
| AMD Ryzen 5                    | 10        | 2.03%   |
| AMD Ryzen 7                    | 9         | 1.83%   |
| Intel Genuine                  | 7         | 1.42%   |
| AMD A6                         | 6         | 1.22%   |
| Intel Pentium Dual-Core        | 5         | 1.02%   |
| Intel Core i9                  | 5         | 1.02%   |
| AMD A4                         | 5         | 1.02%   |
| AMD Turion 64 X2 Mobile        | 4         | 0.81%   |
| AMD E                          | 4         | 0.81%   |
| AMD Athlon                     | 4         | 0.81%   |
| Intel Pentium Dual             | 3         | 0.61%   |
| Intel Core m3                  | 3         | 0.61%   |
| Intel Core Duo                 | 3         | 0.61%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.61%   |
| AMD Mobile Sempron             | 3         | 0.61%   |
| AMD A10                        | 3         | 0.61%   |
| Intel Xeon                     | 2         | 0.41%   |
| Intel Pentium Silver           | 2         | 0.41%   |
| Intel Pentium M                | 2         | 0.41%   |
| Intel Core M                   | 2         | 0.41%   |
| Intel Core 2                   | 2         | 0.41%   |
| Intel Celeron Dual-Core        | 2         | 0.41%   |
| AMD Ryzen 9                    | 2         | 0.41%   |
| AMD Ryzen 3                    | 2         | 0.41%   |
| AMD E2                         | 2         | 0.41%   |
| AMD E1                         | 2         | 0.41%   |
| AMD C-60                       | 2         | 0.41%   |
| AMD A8                         | 2         | 0.41%   |
| Intel Core 2 Extreme           | 1         | 0.2%    |
| CentaurHauls VIA C7            | 1         | 0.2%    |
| AMD Turion Neo X2              | 1         | 0.2%    |
| AMD Ryzen 7 PRO                | 1         | 0.2%    |
| AMD Ryzen 5 PRO                | 1         | 0.2%    |
| AMD Phenom II                  | 1         | 0.2%    |
| AMD Athlon X2                  | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 287       | 58.22%  |
| 4      | 154       | 31.24%  |
| 1      | 18        | 3.65%   |
| 6      | 17        | 3.45%   |
| 8      | 14        | 2.84%   |
| 10     | 2         | 0.41%   |
| 3      | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 490       | 99.59%  |
| 4      | 1         | 0.2%    |
| 2      | 1         | 0.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 326       | 66.26%  |
| 1      | 166       | 33.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 473       | 96.14%  |
| 32-bit         | 17        | 3.46%   |
| 64-bit         | 1         | 0.2%    |
| Unknown        | 1         | 0.2%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 15.38%  |
| 0x206a7    | 48        | 9.47%   |
| 0x306a9    | 45        | 8.88%   |
| 0x1067a    | 21        | 4.14%   |
| 0x806ec    | 17        | 3.35%   |
| 0x806ea    | 16        | 3.16%   |
| 0x306d4    | 15        | 2.96%   |
| 0x40651    | 14        | 2.76%   |
| 0x306c3    | 12        | 2.37%   |
| 0x806e9    | 11        | 2.17%   |
| 0x6fd      | 11        | 2.17%   |
| 0x20655    | 11        | 2.17%   |
| 0x906ea    | 10        | 1.97%   |
| 0x30678    | 10        | 1.97%   |
| 0x906e9    | 9         | 1.78%   |
| 0x806c1    | 9         | 1.78%   |
| 0x406e3    | 9         | 1.78%   |
| 0x406c4    | 9         | 1.78%   |
| 0x20652    | 9         | 1.78%   |
| 0x106ca    | 8         | 1.58%   |
| 0x706e5    | 7         | 1.38%   |
| 0x706a1    | 7         | 1.38%   |
| 0x08108102 | 7         | 1.38%   |
| 0x506e3    | 6         | 1.18%   |
| 0x10676    | 6         | 1.18%   |
| 0x06006705 | 6         | 1.18%   |
| 0x6ec      | 5         | 0.99%   |
| 0x08108109 | 5         | 0.99%   |
| 0x07030105 | 5         | 0.99%   |
| 0x05000119 | 5         | 0.99%   |
| 0x906ed    | 4         | 0.79%   |
| 0x406c3    | 4         | 0.79%   |
| 0x30661    | 4         | 0.79%   |
| 0x106e5    | 4         | 0.79%   |
| 0x08600106 | 4         | 0.79%   |
| 0xa0652    | 3         | 0.59%   |
| 0x806eb    | 3         | 0.59%   |
| 0x806d1    | 3         | 0.59%   |
| 0x6e8      | 3         | 0.59%   |
| 0x10661    | 3         | 0.59%   |
| 0x08101016 | 3         | 0.59%   |
| 0x06006704 | 3         | 0.59%   |
| 0x02000032 | 3         | 0.59%   |
| 0x6fa      | 2         | 0.39%   |
| 0x506c9    | 2         | 0.39%   |
| 0x30673    | 2         | 0.39%   |
| 0x0a50000c | 2         | 0.39%   |
| 0x0700010f | 2         | 0.39%   |
| 0x05000029 | 2         | 0.39%   |
| 0xa0660    | 1         | 0.2%    |
| 0xa0655    | 1         | 0.2%    |
| 0x706a8    | 1         | 0.2%    |
| 0x6fb      | 1         | 0.2%    |
| 0x6f2      | 1         | 0.2%    |
| 0x6d8      | 1         | 0.2%    |
| 0x695      | 1         | 0.2%    |
| 0x0a50000b | 1         | 0.2%    |
| 0x08701013 | 1         | 0.2%    |
| 0x08600104 | 1         | 0.2%    |
| 0x08600103 | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 79        | 16.06%  |
| SandyBridge     | 58        | 11.79%  |
| IvyBridge       | 52        | 10.57%  |
| Haswell         | 32        | 6.5%    |
| Penryn          | 28        | 5.69%   |
| Silvermont      | 25        | 5.08%   |
| Westmere        | 21        | 4.27%   |
| Skylake         | 20        | 4.07%   |
| Core            | 19        | 3.86%   |
| Broadwell       | 19        | 3.86%   |
| Zen+            | 12        | 2.44%   |
| Bonnell         | 12        | 2.44%   |
| TigerLake       | 10        | 2.03%   |
| P6              | 10        | 2.03%   |
| IceLake         | 10        | 2.03%   |
| Excavator       | 10        | 2.03%   |
| K8 Hammer       | 9         | 1.83%   |
| Zen 2           | 8         | 1.63%   |
| Goldmont plus   | 8         | 1.63%   |
| CometLake       | 7         | 1.42%   |
| Bobcat          | 7         | 1.42%   |
| Puma            | 6         | 1.22%   |
| Zen 3           | 4         | 0.81%   |
| Zen             | 4         | 0.81%   |
| Nehalem         | 4         | 0.81%   |
| K8 & K10 hybrid | 4         | 0.81%   |
| Piledriver      | 3         | 0.61%   |
| Goldmont        | 3         | 0.61%   |
| Unknown         | 3         | 0.61%   |
| K10 Llano       | 2         | 0.41%   |
| Jaguar          | 2         | 0.41%   |
| K10             | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 370       | 61.06%  |
| Nvidia                           | 121       | 19.97%  |
| AMD                              | 107       | 17.66%  |
| Silicon Integrated Systems [SiS] | 6         | 0.99%   |
| VIA Technologies                 | 2         | 0.33%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                      | Notebooks | Percent |
|--------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                           | 51        | 8.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                  | 47        | 7.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                               | 18        | 2.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                                 | 17        | 2.69%   |
| Intel HD Graphics 5500                                                                     | 17        | 2.69%   |
| Intel UHD Graphics 620                                                                     | 16        | 2.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                                           | 16        | 2.53%   |
| Intel Core Processor Integrated Graphics Controller                                        | 15        | 2.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                  | 15        | 2.37%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                                | 14        | 2.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller   | 13        | 2.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                        | 12        | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                               | 12        | 1.9%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                       | 12        | 1.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                        | 11        | 1.74%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                          | 11        | 1.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                  | 10        | 1.58%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                   | 9         | 1.42%   |
| Intel HD Graphics 630                                                                      | 8         | 1.27%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                       | 8         | 1.27%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                    | 8         | 1.27%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller              | 7         | 1.11%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                  | 7         | 1.11%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                                 | 7         | 1.11%   |
| AMD Renoir                                                                                 | 7         | 1.11%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                                 | 6         | 0.95%   |
| Intel HD Graphics 620                                                                      | 6         | 0.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                        | 6         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                    | 5         | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                       | 5         | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                     | 5         | 0.79%   |
| Intel HD Graphics 530                                                                      | 5         | 0.79%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                  | 5         | 0.79%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]              | 5         | 0.79%   |
| AMD RS690M [Radeon Xpress 1200/1250/1270]                                                  | 5         | 0.79%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                          | 4         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                            | 4         | 0.63%   |
| Nvidia GF108M [GeForce GT 540M]                                                            | 4         | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                       | 4         | 0.63%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                            | 4         | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                           | 4         | 0.63%   |
| AMD Cezanne                                                                                | 4         | 0.63%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                                 | 3         | 0.47%   |
| Nvidia GP108M [GeForce MX250]                                                              | 3         | 0.47%   |
| Nvidia GF119M [NVS 4200M]                                                                  | 3         | 0.47%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                            | 3         | 0.47%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                       | 3         | 0.47%   |
| Intel HD Graphics 500                                                                      | 3         | 0.47%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]      | 3         | 0.47%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                               | 3         | 0.47%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                        | 3         | 0.47%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                          | 2         | 0.32%   |
| Silicon Integrated Systems [SiS] 661/741/760 PCI/AGP or 662/761Gx PCIE VGA Display Adapter | 2         | 0.32%   |
| Nvidia GT218M [NVS 3100M]                                                                  | 2         | 0.32%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                    | 2         | 0.32%   |
| Nvidia GP104M [GeForce GTX 1070 Mobile]                                                    | 2         | 0.32%   |
| Nvidia GM108M [GeForce 940M]                                                               | 2         | 0.32%   |
| Nvidia GM108M [GeForce 840M]                                                               | 2         | 0.32%   |
| Nvidia GM107M [GeForce GTX 960M]                                                           | 2         | 0.32%   |
| Nvidia GM107GLM [Quadro M1000M]                                                            | 2         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 259       | 52.64%  |
| Intel + Nvidia | 85        | 17.28%  |
| 1 x AMD        | 68        | 13.82%  |
| 1 x Nvidia     | 31        | 6.3%    |
| Intel + AMD    | 25        | 5.08%   |
| 2 x AMD        | 8         | 1.63%   |
| 1 x SiS        | 6         | 1.22%   |
| AMD + Nvidia   | 5         | 1.02%   |
| Other          | 3         | 0.61%   |
| 1 x VIA        | 2         | 0.41%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 403       | 81.09%  |
| Proprietary | 72        | 14.49%  |
| Unknown     | 22        | 4.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 306       | 61.57%  |
| 1.01-2.0   | 64        | 12.88%  |
| 0.01-0.5   | 55        | 11.07%  |
| 0.51-1.0   | 33        | 6.64%   |
| 3.01-4.0   | 26        | 5.23%   |
| 7.01-8.0   | 6         | 1.21%   |
| 5.01-6.0   | 4         | 0.8%    |
| 2.01-3.0   | 3         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 110       | 20.56%  |
| LG Display              | 83        | 15.51%  |
| Samsung Electronics     | 82        | 15.33%  |
| Chimei Innolux          | 61        | 11.4%   |
| BOE                     | 44        | 8.22%   |
| Chi Mei Optoelectronics | 20        | 3.74%   |
| Dell                    | 17        | 3.18%   |
| Sharp                   | 12        | 2.24%   |
| Hewlett-Packard         | 9         | 1.68%   |
| PANDA                   | 8         | 1.5%    |
| Goldstar                | 8         | 1.5%    |
| LG Philips              | 7         | 1.31%   |
| Lenovo                  | 7         | 1.31%   |
| Sony                    | 5         | 0.93%   |
| Apple                   | 5         | 0.93%   |
| AOC                     | 5         | 0.93%   |
| InfoVision              | 4         | 0.75%   |
| HannStar                | 4         | 0.75%   |
| Acer                    | 4         | 0.75%   |
| ViewSonic               | 3         | 0.56%   |
| Philips                 | 3         | 0.56%   |
| InnoLux Display         | 3         | 0.56%   |
| Unknown                 | 2         | 0.37%   |
| Seiko/Epson             | 2         | 0.37%   |
| LGD                     | 2         | 0.37%   |
| Iiyama                  | 2         | 0.37%   |
| Eizo                    | 2         | 0.37%   |
| CSO                     | 2         | 0.37%   |
| CPT                     | 2         | 0.37%   |
| ASUSTek Computer        | 2         | 0.37%   |
| Ancor Communications    | 2         | 0.37%   |
| ___                     | 1         | 0.19%   |
| Vizio                   | 1         | 0.19%   |
| SKY                     | 1         | 0.19%   |
| Quanta Display          | 1         | 0.19%   |
| Panasonic               | 1         | 0.19%   |
| Optoma                  | 1         | 0.19%   |
| Nvidia                  | 1         | 0.19%   |
| NEC Computers           | 1         | 0.19%   |
| MS_ Nvidia              | 1         | 0.19%   |
| HKC                     | 1         | 0.19%   |
| Fujitsu Siemens         | 1         | 0.19%   |
| Element                 | 1         | 0.19%   |
| BenQ                    | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 10        | 1.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 8         | 1.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 6         | 1.1%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 5         | 0.92%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch               | 4         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 4         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 4         | 0.73%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch      | 3         | 0.55%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch              | 3         | 0.55%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 3         | 0.55%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1747 1920x1080 381x214mm 17.2-inch          | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 3         | 0.55%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 3         | 0.55%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch             | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch             | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO11ED 1920x1080 344x193mm 15.5-inch            | 3         | 0.55%   |
| AU Optronics LCD Monitor AUO109E 1600x900 380x210mm 17.1-inch             | 3         | 0.55%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch     | 2         | 0.37%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch      | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch      | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch      | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch      | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3846 1680x1050 331x207mm 15.4-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch      | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3130 1024x600 223x125mm 10.1-inch      | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch      | 2         | 0.37%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                   | 2         | 0.37%   |
| LGD LCD Monitor 1920x1080                                                 | 2         | 0.37%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch               | 2         | 0.37%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 2         | 0.37%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch              | 2         | 0.37%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch               | 2         | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 2         | 0.37%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 2         | 0.37%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch              | 2         | 0.37%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                  | 2         | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch          | 2         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 2         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x193mm 15.5-inch           | 2         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch           | 2         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch          | 2         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch           | 2         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch  | 2         | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.37%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                     | 2         | 0.37%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 2         | 0.37%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 2         | 0.37%   |
| BOE LCD Monitor BOE05F4 1366x768 277x156mm 12.5-inch                      | 2         | 0.37%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.37%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.37%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch             | 2         | 0.37%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 175       | 34.38%  |
| 1366x768 (WXGA)    | 173       | 33.99%  |
| 1600x900 (HD+)     | 41        | 8.06%   |
| 1280x800 (WXGA)    | 25        | 4.91%   |
| 1440x900 (WXGA+)   | 14        | 2.75%   |
| 1920x1200 (WUXGA)  | 13        | 2.55%   |
| 3840x2160 (4K)     | 11        | 2.16%   |
| 1024x600           | 11        | 2.16%   |
| 2560x1440 (QHD)    | 10        | 1.96%   |
| 1680x1050 (WSXGA+) | 10        | 1.96%   |
| 1360x768           | 5         | 0.98%   |
| 1280x1024 (SXGA)   | 5         | 0.98%   |
| 3440x1440          | 2         | 0.39%   |
| 3200x1800 (QHD+)   | 2         | 0.39%   |
| 2560x1600          | 2         | 0.39%   |
| 1400x1050          | 2         | 0.39%   |
| 3840x1080          | 1         | 0.2%    |
| 2880x1800          | 1         | 0.2%    |
| 2160x1440          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1680x945           | 1         | 0.2%    |
| 1600x1200          | 1         | 0.2%    |
| 1024x768 (XGA)     | 1         | 0.2%    |
| Unknown            | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 208       | 38.95%  |
| 14      | 64        | 11.99%  |
| 13      | 64        | 11.99%  |
| 17      | 55        | 10.3%   |
| 12      | 16        | 3%      |
| 10      | 14        | 2.62%   |
| Unknown | 14        | 2.62%   |
| 24      | 13        | 2.43%   |
| 11      | 13        | 2.43%   |
| 27      | 12        | 2.25%   |
| 23      | 11        | 2.06%   |
| 18      | 11        | 2.06%   |
| 21      | 10        | 1.87%   |
| 22      | 5         | 0.94%   |
| 40      | 4         | 0.75%   |
| 31      | 4         | 0.75%   |
| 20      | 3         | 0.56%   |
| 19      | 3         | 0.56%   |
| 72      | 2         | 0.37%   |
| 34      | 2         | 0.37%   |
| 33      | 2         | 0.37%   |
| 49      | 1         | 0.19%   |
| 29      | 1         | 0.19%   |
| 16      | 1         | 0.19%   |
| 8       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 301       | 56.69%  |
| 201-300     | 71        | 13.37%  |
| 351-400     | 62        | 11.68%  |
| 501-600     | 33        | 6.21%   |
| 401-500     | 31        | 5.84%   |
| Unknown     | 14        | 2.64%   |
| 601-700     | 7         | 1.32%   |
| 801-900     | 4         | 0.75%   |
| 701-800     | 4         | 0.75%   |
| 1501-2000   | 2         | 0.38%   |
| 101-200     | 1         | 0.19%   |
| 1001-1500   | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 403       | 82.58%  |
| 16/10   | 58        | 11.89%  |
| Unknown | 10        | 2.05%   |
| 5/4     | 5         | 1.02%   |
| 4/3     | 4         | 0.82%   |
| 3/2     | 4         | 0.82%   |
| 21/9    | 2         | 0.41%   |
| 32/9    | 1         | 0.2%    |
| 0.62    | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 206       | 38.58%  |
| 81-90          | 101       | 18.91%  |
| 121-130        | 41        | 7.68%   |
| 201-250        | 30        | 5.62%   |
| 71-80          | 25        | 4.68%   |
| 61-70          | 16        | 3%      |
| 41-50          | 14        | 2.62%   |
| 141-150        | 14        | 2.62%   |
| Unknown        | 14        | 2.62%   |
| 51-60          | 13        | 2.43%   |
| 301-350        | 12        | 2.25%   |
| 351-500        | 9         | 1.69%   |
| 151-200        | 9         | 1.69%   |
| 131-140        | 9         | 1.69%   |
| 251-300        | 8         | 1.5%    |
| 501-1000       | 4         | 0.75%   |
| 91-100         | 4         | 0.75%   |
| More than 1000 | 3         | 0.56%   |
| 1-40           | 1         | 0.19%   |
| 111-120        | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 187       | 35.55%  |
| 121-160       | 179       | 34.03%  |
| 51-100        | 105       | 19.96%  |
| 161-240       | 25        | 4.75%   |
| Unknown       | 14        | 2.66%   |
| More than 240 | 11        | 2.09%   |
| 1-50          | 5         | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 397       | 80.2%   |
| 2     | 72        | 14.55%  |
| 0     | 16        | 3.23%   |
| 3     | 10        | 2.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 256       | 32.12%  |
| Intel                             | 245       | 30.74%  |
| Qualcomm Atheros                  | 132       | 16.56%  |
| Broadcom                          | 54        | 6.78%   |
| Broadcom Limited                  | 23        | 2.89%   |
| Marvell Technology Group          | 13        | 1.63%   |
| Ralink                            | 9         | 1.13%   |
| Silicon Integrated Systems [SiS]  | 7         | 0.88%   |
| Sierra Wireless                   | 7         | 0.88%   |
| Ralink Technology                 | 6         | 0.75%   |
| Attansic Technology               | 6         | 0.75%   |
| TP-Link                           | 5         | 0.63%   |
| Ericsson Business Mobile Networks | 4         | 0.5%    |
| Hewlett-Packard                   | 3         | 0.38%   |
| VIA Technologies                  | 2         | 0.25%   |
| MediaTek                          | 2         | 0.25%   |
| JMicron Technology                | 2         | 0.25%   |
| Dell                              | 2         | 0.25%   |
| ASIX Electronics                  | 2         | 0.25%   |
| Xiaomi                            | 1         | 0.13%   |
| U.S. Robotics                     | 1         | 0.13%   |
| U-Blox                            | 1         | 0.13%   |
| Tenda                             | 1         | 0.13%   |
| Samsung Electronics               | 1         | 0.13%   |
| Qualcomm Atheros Communications   | 1         | 0.13%   |
| Qualcomm                          | 1         | 0.13%   |
| Primax Electronics                | 1         | 0.13%   |
| NetGear                           | 1         | 0.13%   |
| Lenovo                            | 1         | 0.13%   |
| Fibocom                           | 1         | 0.13%   |
| dog hunter                        | 1         | 0.13%   |
| DisplayLink                       | 1         | 0.13%   |
| D-Link                            | 1         | 0.13%   |
| Conexant Systems                  | 1         | 0.13%   |
| Belkin Components                 | 1         | 0.13%   |
| ASUSTek Computer                  | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 154       | 15.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 65        | 6.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 30        | 3.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 3%      |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 23        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 21        | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 1.96%   |
| Intel Wireless 7260                                                     | 19        | 1.96%   |
| Intel Wireless 7265                                                     | 18        | 1.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.86%   |
| Intel Wi-Fi 6 AX200                                                     | 16        | 1.65%   |
| Intel Wireless 8265 / 8275                                              | 15        | 1.55%   |
| Intel Wireless 3165                                                     | 15        | 1.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 14        | 1.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.14%   |
| Intel Ethernet Connection I217-LM                                       | 11        | 1.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.93%   |
| Intel Wireless 8260                                                     | 9         | 0.93%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 0.93%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 0.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 0.83%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 8         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                                   | 8         | 0.83%   |
| Intel Centrino Ultimate-N 6300                                          | 8         | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.83%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.72%   |
| Intel 82577LM Gigabit Network Connection                                | 7         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 6         | 0.62%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.62%   |
| Intel Ethernet Connection I218-LM                                       | 6         | 0.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 0.62%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.62%   |
| Attansic AR8152 v2.0 Fast Ethernet                                      | 6         | 0.62%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 5         | 0.52%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.52%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.52%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.52%   |
| Intel Ethernet Connection I219-V                                        | 5         | 0.52%   |
| Intel Centrino Advanced-N 6200                                          | 5         | 0.52%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 0.52%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 4         | 0.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.41%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.41%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 4         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 4         | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.41%   |
| Intel Wireless 3160                                                     | 4         | 0.41%   |
| Intel WiFi Link 5100                                                    | 4         | 0.41%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.41%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.41%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.41%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 0.41%   |
| Broadcom BCM4311 802.11a/b/g                                            | 4         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 235       | 45.81%  |
| Qualcomm Atheros                | 110       | 21.44%  |
| Realtek Semiconductor           | 69        | 13.45%  |
| Broadcom                        | 42        | 8.19%   |
| Broadcom Limited                | 17        | 3.31%   |
| Ralink                          | 9         | 1.75%   |
| Sierra Wireless                 | 7         | 1.36%   |
| Ralink Technology               | 6         | 1.17%   |
| TP-Link                         | 5         | 0.97%   |
| Dell                            | 2         | 0.39%   |
| U.S. Robotics                   | 1         | 0.19%   |
| Tenda                           | 1         | 0.19%   |
| Qualcomm Atheros Communications | 1         | 0.19%   |
| Qualcomm                        | 1         | 0.19%   |
| NetGear                         | 1         | 0.19%   |
| MEDIATEK                        | 1         | 0.19%   |
| Hewlett-Packard                 | 1         | 0.19%   |
| Fibocom                         | 1         | 0.19%   |
| D-Link                          | 1         | 0.19%   |
| Belkin Components               | 1         | 0.19%   |
| ASUSTek Computer                | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 5.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 23        | 4.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 21        | 4.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 19        | 3.7%    |
| Intel Wireless 7260                                                     | 19        | 3.7%    |
| Intel Wireless 7265                                                     | 18        | 3.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 3.5%    |
| Intel Wi-Fi 6 AX200                                                     | 16        | 3.11%   |
| Intel Wireless 8265 / 8275                                              | 15        | 2.92%   |
| Intel Wireless 3165                                                     | 15        | 2.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 2.53%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 12        | 2.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 11        | 2.14%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 1.75%   |
| Intel Wireless 8260                                                     | 9         | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.75%   |
| Intel Centrino Advanced-N 6235                                          | 9         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 8         | 1.56%   |
| Intel Centrino Ultimate-N 6300                                          | 8         | 1.56%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 1.36%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 6         | 1.17%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 1.17%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 0.97%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.97%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.97%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 0.97%   |
| Intel Centrino Advanced-N 6200                                          | 5         | 0.97%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 5         | 0.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 0.78%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 4         | 0.78%   |
| Intel Wireless 3160                                                     | 4         | 0.78%   |
| Intel WiFi Link 5100                                                    | 4         | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.78%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.78%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 0.78%   |
| Broadcom BCM4311 802.11a/b/g                                            | 4         | 0.78%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 3         | 0.58%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 3         | 0.58%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.58%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 0.58%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.58%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 3         | 0.58%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 3         | 0.58%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 3         | 0.58%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.39%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.39%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.39%   |
| Realtek RTL8187 Wireless Adapter                                        | 2         | 0.39%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.39%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.39%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.39%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 234       | 54.04%  |
| Intel                            | 100       | 23.09%  |
| Qualcomm Atheros                 | 40        | 9.24%   |
| Broadcom                         | 16        | 3.7%    |
| Marvell Technology Group         | 13        | 3%      |
| Broadcom Limited                 | 7         | 1.62%   |
| Silicon Integrated Systems [SiS] | 6         | 1.39%   |
| Attansic Technology              | 6         | 1.39%   |
| VIA Technologies                 | 2         | 0.46%   |
| JMicron Technology               | 2         | 0.46%   |
| ASIX Electronics                 | 2         | 0.46%   |
| Xiaomi                           | 1         | 0.23%   |
| Samsung Electronics              | 1         | 0.23%   |
| MediaTek                         | 1         | 0.23%   |
| Lenovo                           | 1         | 0.23%   |
| DisplayLink                      | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 154       | 35.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 65        | 14.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 30        | 6.86%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 14        | 3.2%    |
| Intel Ethernet Connection I217-LM                                              | 11        | 2.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.83%   |
| Intel Ethernet Connection (3) I218-LM                                          | 8         | 1.83%   |
| Intel 82577LM Gigabit Network Connection                                       | 7         | 1.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 6         | 1.37%   |
| Intel Ethernet Connection I218-LM                                              | 6         | 1.37%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 6         | 1.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 5         | 1.14%   |
| Intel Ethernet Connection I219-V                                               | 5         | 1.14%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 4         | 0.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 4         | 0.92%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 0.92%   |
| Intel Ethernet Connection (6) I219-V                                           | 4         | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.69%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 3         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.69%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 0.69%   |
| Intel Ethernet Connection (2) I219-LM                                          | 3         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 0.69%   |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 3         | 0.69%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 2         | 0.46%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 2         | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 2         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.46%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.46%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 2         | 0.46%   |
| Intel PRO/100 VE Network Connection                                            | 2         | 0.46%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.46%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.46%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 2         | 0.46%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 2         | 0.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.23%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 1         | 0.23%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 1         | 0.23%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.23%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.23%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.23%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.23%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.23%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.23%   |
| MediaTek B140DL                                                                | 1         | 0.23%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.23%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.23%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 1         | 0.23%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 1         | 0.23%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 1         | 0.23%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 1         | 0.23%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.23%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.23%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 479       | 52.12%  |
| Ethernet | 426       | 46.35%  |
| Modem    | 14        | 1.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 431       | 65.7%   |
| Ethernet | 223       | 33.99%  |
| Modem    | 2         | 0.3%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 395       | 80.12%  |
| 1     | 88        | 17.85%  |
| 0     | 8         | 1.62%   |
| 3     | 2         | 0.41%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 441       | 88.91%  |
| Yes     | 54        | 10.89%  |
| Unknown | 1         | 0.2%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 168       | 46.67%  |
| Qualcomm Atheros Communications | 39        | 10.83%  |
| Realtek Semiconductor           | 30        | 8.33%   |
| Broadcom                        | 30        | 8.33%   |
| Dell                            | 17        | 4.72%   |
| Lite-On Technology              | 15        | 4.17%   |
| IMC Networks                    | 13        | 3.61%   |
| Foxconn / Hon Hai               | 12        | 3.33%   |
| Cambridge Silicon Radio         | 9         | 2.5%    |
| Hewlett-Packard                 | 8         | 2.22%   |
| Toshiba                         | 3         | 0.83%   |
| Ralink                          | 3         | 0.83%   |
| ASUSTek Computer                | 3         | 0.83%   |
| Ralink Technology               | 2         | 0.56%   |
| Foxconn International           | 2         | 0.56%   |
| Apple                           | 2         | 0.56%   |
| Alps Electric                   | 2         | 0.56%   |
| Qcom                            | 1         | 0.28%   |
| Chicony Electronics             | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 80        | 22.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 29        | 8.06%   |
| Intel Bluetooth Device                                                              | 21        | 5.83%   |
| Realtek Bluetooth Radio                                                             | 15        | 4.17%   |
| Intel AX200 Bluetooth                                                               | 15        | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 12        | 3.33%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 12        | 3.33%   |
| Dell DW375 Bluetooth Module                                                         | 11        | 3.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 10        | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 10        | 2.78%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 9         | 2.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 2.5%    |
| IMC Networks Bluetooth Device                                                       | 8         | 2.22%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 6         | 1.67%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.67%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 1.67%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 6         | 1.67%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 5         | 1.39%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.11%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.11%   |
| Broadcom HP Portable SoftSailing                                                    | 4         | 1.11%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.11%   |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.83%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 0.83%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.56%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.56%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.56%   |
| IMC Networks BCM20702A0                                                             | 2         | 0.56%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.56%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.56%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.56%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 2         | 0.56%   |
| Broadcom HP Portable Valentine                                                      | 2         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.56%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.56%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.28%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.28%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.28%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.28%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.28%   |
| Ralink CSR BS8510                                                                   | 1         | 0.28%   |
| Qcom Broadcom Bluetooth USB                                                         | 1         | 0.28%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.28%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.28%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.28%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.28%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]                                       | 1         | 0.28%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.28%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.28%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.28%   |
| Foxconn / Hon Hai BCM2045A0                                                         | 1         | 0.28%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.28%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 1         | 0.28%   |
| Chicony Bluetooth (RTL8723BE)                                                       | 1         | 0.28%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 1         | 0.28%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 405       | 67.61%  |
| AMD                                            | 84        | 14.02%  |
| Nvidia                                         | 70        | 11.69%  |
| Silicon Integrated Systems [SiS]               | 8         | 1.34%   |
| Realtek Semiconductor                          | 5         | 0.83%   |
| C-Media Electronics                            | 4         | 0.67%   |
| VIA Technologies                               | 2         | 0.33%   |
| Lenovo                                         | 2         | 0.33%   |
| GN Netcom                                      | 2         | 0.33%   |
| Conexant Systems                               | 2         | 0.33%   |
| Sony                                           | 1         | 0.17%   |
| SmartAction                                    | 1         | 0.17%   |
| Siemens Information and Communication Products | 1         | 0.17%   |
| Plantronics                                    | 1         | 0.17%   |
| No brand                                       | 1         | 0.17%   |
| Meizu                                          | 1         | 0.17%   |
| Logitech                                       | 1         | 0.17%   |
| Kingston Technology                            | 1         | 0.17%   |
| JMTek                                          | 1         | 0.17%   |
| Hewlett-Packard                                | 1         | 0.17%   |
| Generalplus Technology                         | 1         | 0.17%   |
| FiiO Electronics Technology                    | 1         | 0.17%   |
| Elite Silicon                                  | 1         | 0.17%   |
| Corsair                                        | 1         | 0.17%   |
| BEHRINGER International                        | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 59        | 8.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 51        | 7.18%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 5.49%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 27        | 3.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 25        | 3.52%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 25        | 3.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 20        | 2.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 2.68%   |
| Intel Broadwell-U Audio Controller                                                                | 19        | 2.68%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 18        | 2.54%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 18        | 2.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 17        | 2.39%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 2.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 2.25%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 2.25%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 2.25%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 1.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 14        | 1.97%   |
| AMD FCH Azalia Controller                                                                         | 14        | 1.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 1.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 1.41%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.27%   |
| Intel CM238 HD Audio Controller                                                                   | 9         | 1.27%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 9         | 1.27%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 1.27%   |
| AMD Kabini HDMI/DP Audio                                                                          | 9         | 1.27%   |
| AMD High Definition Audio Controller                                                              | 9         | 1.27%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 8         | 1.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.13%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 0.99%   |
| AMD Wrestler HDMI Audio                                                                           | 7         | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 6         | 0.85%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 5         | 0.7%    |
| Realtek Semiconductor USB Audio                                                                   | 5         | 0.7%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 5         | 0.7%    |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 4         | 0.56%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.56%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 4         | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.56%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 3         | 0.42%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 3         | 0.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.42%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.42%   |
| Nvidia Audio device                                                                               | 3         | 0.42%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.42%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.42%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.42%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.42%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.42%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 2         | 0.28%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.28%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.28%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.28%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.28%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.28%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 95        | 26.32%  |
| SK Hynix                                         | 71        | 19.67%  |
| Micron Technology                                | 46        | 12.74%  |
| Kingston                                         | 34        | 9.42%   |
| Unknown                                          | 30        | 8.31%   |
| Crucial                                          | 21        | 5.82%   |
| Ramaxel Technology                               | 12        | 3.32%   |
| Nanya Technology                                 | 9         | 2.49%   |
| Elpida                                           | 9         | 2.49%   |
| Smart                                            | 5         | 1.39%   |
| Corsair                                          | 5         | 1.39%   |
| A-DATA Technology                                | 4         | 1.11%   |
| Unknown (ABCD)                                   | 3         | 0.83%   |
| Teikon                                           | 2         | 0.55%   |
| Patriot                                          | 2         | 0.55%   |
| GOODRAM                                          | 2         | 0.55%   |
| G.Skill                                          | 2         | 0.55%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.28%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.28%   |
| Team                                             | 1         | 0.28%   |
| Qimonda                                          | 1         | 0.28%   |
| Netlist                                          | 1         | 0.28%   |
| Neo Forza                                        | 1         | 0.28%   |
| Eluktro                                          | 1         | 0.28%   |
| ASint Technology                                 | 1         | 0.28%   |
| Apacer                                           | 1         | 0.28%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 10        | 2.6%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 1.3%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 1.3%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 5         | 1.3%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 5         | 1.3%    |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 5         | 1.3%    |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s            | 5         | 1.3%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 4         | 1.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 1.04%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 1.04%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 3         | 0.78%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 3         | 0.78%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.78%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.78%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 3         | 0.78%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.78%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 3         | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.78%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 3         | 0.78%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.78%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.78%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 0.78%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s             | 3         | 0.78%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s             | 3         | 0.78%   |
| Unknown RAM Module 512MB SODIMM DDR                                 | 2         | 0.52%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 2         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DRAM                               | 2         | 0.52%   |
| Unknown RAM Module 2048MB SODIMM DDR3                               | 2         | 0.52%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s            | 2         | 0.52%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1066MT/s                     | 2         | 0.52%   |
| SK Hynix RAM Module 16384MB SODIMM DDR4 2133MT/s                    | 2         | 0.52%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.52%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.52%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 0.52%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.52%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.52%   |
| Samsung RAM M471B5773CHS-CF8 2048MB SODIMM DDR3 1067MT/s            | 2         | 0.52%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s            | 2         | 0.52%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s            | 2         | 0.52%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.52%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s               | 2         | 0.52%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 2         | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.52%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 2         | 0.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.52%   |
| Nanya RAM NT4GC64B8HG0NS-CG 4GB SODIMM DDR3 1334MT/s                | 2         | 0.52%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s       | 2         | 0.52%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s               | 2         | 0.52%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16384MB SODIMM DDR4 3200MT/s            | 2         | 0.52%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.52%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 2         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 2         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E! 4096MB SODIMM DDR4 2400MT/s            | 2         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 2         | 0.52%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s               | 2         | 0.52%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s            | 2         | 0.52%   |
| Kingston RAM 99U5469-045.A00LF 4GB SODIMM DDR3 1600MT/s             | 2         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 143       | 46.43%  |
| DDR4    | 114       | 37.01%  |
| DDR2    | 16        | 5.19%   |
| LPDDR3  | 10        | 3.25%   |
| LPDDR4  | 9         | 2.92%   |
| SDRAM   | 7         | 2.27%   |
| DDR     | 5         | 1.62%   |
| DRAM    | 2         | 0.65%   |
| Unknown | 2         | 0.65%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 287       | 92.88%  |
| Row Of Chips | 18        | 5.83%   |
| Chip         | 3         | 0.97%   |
| DIMM         | 1         | 0.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 126       | 37.39%  |
| 8192  | 98        | 29.08%  |
| 2048  | 58        | 17.21%  |
| 16384 | 35        | 10.39%  |
| 1024  | 8         | 2.37%   |
| 32768 | 7         | 2.08%   |
| 512   | 3         | 0.89%   |
| 1536  | 1         | 0.3%    |
| 256   | 1         | 0.3%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 94        | 28.23%  |
| 2667    | 56        | 16.82%  |
| 3200    | 35        | 10.51%  |
| 1334    | 28        | 8.41%   |
| 2400    | 22        | 6.61%   |
| 1333    | 17        | 5.11%   |
| 2133    | 16        | 4.8%    |
| Unknown | 13        | 3.9%    |
| 3266    | 10        | 3%      |
| 667     | 9         | 2.7%    |
| 1067    | 6         | 1.8%    |
| 1066    | 6         | 1.8%    |
| 4199    | 5         | 1.5%    |
| 800     | 5         | 1.5%    |
| 533     | 3         | 0.9%    |
| 4267    | 2         | 0.6%    |
| 2048    | 2         | 0.6%    |
| 975     | 2         | 0.6%    |
| 2933    | 1         | 0.3%    |
| 1867    | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 42.86%  |
| Samsung Electronics | 1         | 14.29%  |
| QinHeng Electronics | 1         | 14.29%  |
| Canon               | 1         | 14.29%  |
| Brother Industries  | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Samsung CLX-8380 Series            | 1         | 14.29%  |
| QinHeng CH340S                     | 1         | 14.29%  |
| HP Deskjet F4500 series            | 1         | 14.29%  |
| HP DeskJet 845c                    | 1         | 14.29%  |
| HP DeskJet 2620 All-in-One Printer | 1         | 14.29%  |
| Canon PIXMA MG2500 Series          | 1         | 14.29%  |
| Brother DCP-7055 scanner/printer   | 1         | 14.29%  |

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


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 50%     |
| Seiko Epson ES-D400 [GT-S80]                     | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 123       | 28.15%  |
| Acer                                   | 48        | 10.98%  |
| Microdia                               | 35        | 8.01%   |
| IMC Networks                           | 30        | 6.86%   |
| Sunplus Innovation Technology          | 26        | 5.95%   |
| Realtek Semiconductor                  | 26        | 5.95%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 4.35%   |
| Suyin                                  | 15        | 3.43%   |
| Ricoh                                  | 14        | 3.2%    |
| Quanta                                 | 14        | 3.2%    |
| Silicon Motion                         | 10        | 2.29%   |
| Logitech                               | 10        | 2.29%   |
| Lite-On Technology                     | 10        | 2.29%   |
| Syntek                                 | 8         | 1.83%   |
| Apple                                  | 7         | 1.6%    |
| Alcor Micro                            | 5         | 1.14%   |
| Luxvisions Innotech Limited            | 4         | 0.92%   |
| Lenovo                                 | 4         | 0.92%   |
| Importek                               | 4         | 0.92%   |
| Samsung Electronics                    | 3         | 0.69%   |
| Primax Electronics                     | 3         | 0.69%   |
| ALi                                    | 3         | 0.69%   |
| Ruision                                | 2         | 0.46%   |
| DigiTech                               | 2         | 0.46%   |
| Z-Star Microelectronics                | 1         | 0.23%   |
| Y Media                                | 1         | 0.23%   |
| U0AS01A-0                              | 1         | 0.23%   |
| Sunplus Technology                     | 1         | 0.23%   |
| Microsoft                              | 1         | 0.23%   |
| Hisense                                | 1         | 0.23%   |
| Generalplus Technology                 | 1         | 0.23%   |
| GEMBIRD                                | 1         | 0.23%   |
| DJKANA1BIELN56                         | 1         | 0.23%   |
| Cubeternet                             | 1         | 0.23%   |
| Aveo Technology                        | 1         | 0.23%   |
| ARC International                      | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 22        | 5.01%   |
| Acer Integrated Camera                              | 14        | 3.19%   |
| Chicony HD Webcam                                   | 10        | 2.28%   |
| Sunplus Integrated_Webcam_HD                        | 9         | 2.05%   |
| Realtek Integrated_Webcam_HD                        | 9         | 2.05%   |
| Microdia Integrated_Webcam_HD                       | 9         | 2.05%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 9         | 2.05%   |
| Chicony USB2.0 VGA UVC WebCam                       | 8         | 1.82%   |
| Chicony USB2.0 Camera                               | 8         | 1.82%   |
| Acer Lenovo EasyCamera                              | 8         | 1.82%   |
| Microdia Laptop_Integrated_Webcam_HD                | 7         | 1.59%   |
| Acer BisonCam, NB Pro                               | 7         | 1.59%   |
| Ricoh HD Webcam                                     | 6         | 1.37%   |
| Realtek USB Camera                                  | 5         | 1.14%   |
| Microdia Integrated Webcam                          | 5         | 1.14%   |
| Chicony USB 2.0 Camera                              | 5         | 1.14%   |
| Suyin HP TrueVision HD Integrated Webcam            | 4         | 0.91%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 4         | 0.91%   |
| Quanta HD User Facing                               | 4         | 0.91%   |
| IMC Networks USB 2.0 UVC VGA WebCam                 | 4         | 0.91%   |
| IMC Networks Integrated Camera                      | 4         | 0.91%   |
| Chicony Integrated Camera (1280x720@30)             | 4         | 0.91%   |
| Chicony HP Truevision HD                            | 4         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 4         | 0.91%   |
| Apple iPhone 5/5C/5S/6/SE                           | 4         | 0.91%   |
| Sunplus HP HD Webcam [Fixed]                        | 3         | 0.68%   |
| Sunplus HD WebCam                                   | 3         | 0.68%   |
| Silicon Motion WebCam SC-13HDL11939N                | 3         | 0.68%   |
| Samsung Galaxy A5 (MTP)                             | 3         | 0.68%   |
| Realtek USB2.0 HD UVC WebCam                        | 3         | 0.68%   |
| Realtek Lenovo EasyCamera                           | 3         | 0.68%   |
| Quanta HP HD Camera                                 | 3         | 0.68%   |
| Primax HP HD Webcam [Fixed]                         | 3         | 0.68%   |
| Lite-On Integrated Camera                           | 3         | 0.68%   |
| Lite-On HP HD Camera                                | 3         | 0.68%   |
| IMC Networks UVC VGA Webcam                         | 3         | 0.68%   |
| IMC Networks Integrated Webcam                      | 3         | 0.68%   |
| Chicony Webcam                                      | 3         | 0.68%   |
| Chicony VGA Webcam                                  | 3         | 0.68%   |
| Chicony Lenovo Integrated Camera (0.3MP)            | 3         | 0.68%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 0.68%   |
| Chicony HP HD Webcam                                | 3         | 0.68%   |
| Chicony FJ Camera                                   | 3         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 0.68%   |
| Acer Lenovo Integrated Webcam                       | 3         | 0.68%   |
| Syntek Integrated Camera                            | 2         | 0.46%   |
| Syntek EasyCamera                                   | 2         | 0.46%   |
| Suyin Sony Visual Communication Camera              | 2         | 0.46%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.46%   |
| Silicon Motion WebCam SCB-1100N                     | 2         | 0.46%   |
| Silicon Motion 300k Pixel Camera                    | 2         | 0.46%   |
| Ruision UVC Camera                                  | 2         | 0.46%   |
| Ricoh Sony Visual Communication Camera              | 2         | 0.46%   |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 2         | 0.46%   |
| Realtek Integrated Webcam                           | 2         | 0.46%   |
| Quanta VGA WebCam                                   | 2         | 0.46%   |
| Quanta Laptop_Integrated_Webcam_2HDM                | 2         | 0.46%   |
| Microdia Laptop_Integrated_Webcam_2M                | 2         | 0.46%   |
| Microdia HP Webcam-101                              | 2         | 0.46%   |
| Microdia Dell Integrated HD Webcam                  | 2         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 41        | 48.24%  |
| Synaptics                  | 16        | 18.82%  |
| Shenzhen Goodix Technology | 7         | 8.24%   |
| Upek                       | 6         | 7.06%   |
| Elan Microelectronics      | 5         | 5.88%   |
| AuthenTec                  | 5         | 5.88%   |
| STMicroelectronics         | 2         | 2.35%   |
| LighTuning Technology      | 2         | 2.35%   |
| Focal-systems.Corp         | 1         | 1.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 7         | 8.24%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 7         | 8.24%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 6         | 7.06%   |
| Validity Sensors VFS491                                    | 5         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 5         | 5.88%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 5         | 5.88%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 4         | 4.71%   |
| Elan ELAN:Fingerprint                                      | 4         | 4.71%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 3         | 3.53%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.53%   |
| Shenzhen Goodix Fingerprint Reader                         | 3         | 3.53%   |
| Shenzhen Goodix FingerPrint                                | 3         | 3.53%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 3         | 3.53%   |
| Unknown                                                    | 3         | 3.53%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 2.35%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 2         | 2.35%   |
| Validity Sensors VFS101 Fingerprint Reader                 | 2         | 2.35%   |
| Validity Sensors Fingerprint scanner                       | 2         | 2.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 2.35%   |
| STMicroelectronics Fingerprint Reader                      | 2         | 2.35%   |
| Validity Sensors Synaptics WBDI                            | 1         | 1.18%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 1.18%   |
| Synaptics WBDI Device                                      | 1         | 1.18%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 1.18%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 1.18%   |
| Shenzhen Goodix  FingerPrint Device                        | 1         | 1.18%   |
| LighTuning Fingerprint Reader                              | 1         | 1.18%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 1         | 1.18%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 1.18%   |
| Elan ELAN:ARM-M4                                           | 1         | 1.18%   |
| AuthenTec AES2810                                          | 1         | 1.18%   |
| AuthenTec AES1600                                          | 1         | 1.18%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 28        | 56%     |
| Alcor Micro           | 10        | 20%     |
| Upek                  | 3         | 6%      |
| O2 Micro              | 3         | 6%      |
| Lenovo                | 3         | 6%      |
| SCM Microsystems      | 1         | 2%      |
| Gemalto (was Gemplus) | 1         | 2%      |
| Advanced Card Systems | 1         | 2%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 28%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 18%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 6%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6%      |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6%      |
| Broadcom 58200                                                               | 3         | 6%      |
| Broadcom 5880                                                                | 2         | 4%      |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 2%      |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2%      |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 315       | 63.25%  |
| 1     | 142       | 28.51%  |
| 2     | 33        | 6.63%   |
| 3     | 6         | 1.2%    |
| 8     | 2         | 0.4%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 85        | 36.17%  |
| Chipcard                 | 46        | 19.57%  |
| Graphics card            | 45        | 19.15%  |
| Storage                  | 11        | 4.68%   |
| Net/wireless             | 11        | 4.68%   |
| Camera                   | 8         | 3.4%    |
| Bluetooth                | 6         | 2.55%   |
| Modem                    | 5         | 2.13%   |
| Multimedia controller    | 4         | 1.7%    |
| Sound                    | 3         | 1.28%   |
| Flash memory             | 3         | 1.28%   |
| Communication controller | 3         | 1.28%   |
| Net/ethernet             | 2         | 0.85%   |
| Network                  | 1         | 0.43%   |
| Firewire controller      | 1         | 0.43%   |
| Card reader              | 1         | 0.43%   |

