Ubuntu MATE 20.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

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

Total: 353

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Fujitsu       | LIFEBOOK E5511              | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| HP            | Stream Laptop 11-ak1xxx     | [2d2044b499](https://linux-hardware.org/?probe=2d2044b499) | May 30, 2022 |
| HP            | Pavilion Power Laptop 15... | [4813c4e0b4](https://linux-hardware.org/?probe=4813c4e0b4) | May 28, 2022 |
| HP            | ProBook 650 G1              | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Medion        | Akoya E6415                 | [32545030d4](https://linux-hardware.org/?probe=32545030d4) | May 16, 2022 |
| Avell High... | A70 MOB                     | [c8900ed973](https://linux-hardware.org/?probe=c8900ed973) | May 15, 2022 |
| Avell High... | A62 LIV                     | [8b912c2c4f](https://linux-hardware.org/?probe=8b912c2c4f) | May 15, 2022 |
| HP            | Laptop 17-by3xxx            | [86c82d9ca0](https://linux-hardware.org/?probe=86c82d9ca0) | May 03, 2022 |
| HP            | Laptop 17-by3xxx            | [a55c5c5c9f](https://linux-hardware.org/?probe=a55c5c5c9f) | May 03, 2022 |
| Toshiba       | Satellite C660              | [f4403056c8](https://linux-hardware.org/?probe=f4403056c8) | Apr 30, 2022 |
| Dell          | Precision 3561              | [26fa0f202c](https://linux-hardware.org/?probe=26fa0f202c) | Apr 20, 2022 |
| Clevo         | W54xEU                      | [cb4036a7dc](https://linux-hardware.org/?probe=cb4036a7dc) | Apr 18, 2022 |
| Dell          | Latitude E5530 non-vPro     | [2f865445ce](https://linux-hardware.org/?probe=2f865445ce) | Apr 14, 2022 |
| Dell          | Latitude E5530 non-vPro     | [d32ffb065a](https://linux-hardware.org/?probe=d32ffb065a) | Apr 14, 2022 |
| Clevo         | W54xEU                      | [0a8ddf1dff](https://linux-hardware.org/?probe=0a8ddf1dff) | Apr 14, 2022 |
| Dell          | XPS 15 9500                 | [d873b2d218](https://linux-hardware.org/?probe=d873b2d218) | Apr 14, 2022 |
| Dell          | XPS 13 9380                 | [0897999e8d](https://linux-hardware.org/?probe=0897999e8d) | Apr 13, 2022 |
| Samsung       | R505                        | [9ff46a8ca6](https://linux-hardware.org/?probe=9ff46a8ca6) | Apr 13, 2022 |
| Dell          | Latitude E5400              | [0ac76c891f](https://linux-hardware.org/?probe=0ac76c891f) | Apr 11, 2022 |
| Lenovo        | G700 20251                  | [790d42fec8](https://linux-hardware.org/?probe=790d42fec8) | Mar 30, 2022 |
| Lenovo        | G700 20251                  | [d8166d09e9](https://linux-hardware.org/?probe=d8166d09e9) | Mar 30, 2022 |
| HP            | Pavilion dv7                | [112a1842a0](https://linux-hardware.org/?probe=112a1842a0) | Mar 30, 2022 |
| Samsung       | R530/R730/R540              | [186f96a5a1](https://linux-hardware.org/?probe=186f96a5a1) | Mar 27, 2022 |
| Dell          | Studio 1558                 | [7004b83ddf](https://linux-hardware.org/?probe=7004b83ddf) | Mar 23, 2022 |
| Dell          | Vostro 3350                 | [721a0ea932](https://linux-hardware.org/?probe=721a0ea932) | Mar 21, 2022 |
| ASUSTek       | X541UV                      | [a23f80c36b](https://linux-hardware.org/?probe=a23f80c36b) | Mar 19, 2022 |
| HP            | Pavilion dv7                | [0eb8ef5cd3](https://linux-hardware.org/?probe=0eb8ef5cd3) | Mar 16, 2022 |
| Dell          | Vostro 3401                 | [225095b10b](https://linux-hardware.org/?probe=225095b10b) | Mar 12, 2022 |
| Toshiba       | Satellite P755              | [ceb8d030e2](https://linux-hardware.org/?probe=ceb8d030e2) | Mar 10, 2022 |
| ASUSTek       | 1011PX                      | [776d052837](https://linux-hardware.org/?probe=776d052837) | Mar 09, 2022 |
| ASUSTek       | UX305FA                     | [6618b00369](https://linux-hardware.org/?probe=6618b00369) | Feb 28, 2022 |
| Fujitsu       | LIFEBOOK S752               | [abb12adccc](https://linux-hardware.org/?probe=abb12adccc) | Feb 26, 2022 |
| Acer          | Aspire E1-571G              | [de462f47a3](https://linux-hardware.org/?probe=de462f47a3) | Feb 24, 2022 |
| Acer          | Aspire E1-571G              | [ac593e3a3a](https://linux-hardware.org/?probe=ac593e3a3a) | Feb 24, 2022 |
| Lenovo        | ThinkPad T460p 20FW000VU... | [9cbb915f78](https://linux-hardware.org/?probe=9cbb915f78) | Feb 18, 2022 |
| ASUSTek       | X553MA                      | [94ebaa5d9b](https://linux-hardware.org/?probe=94ebaa5d9b) | Feb 15, 2022 |
| Acer          | Aspire 7735                 | [38d97cd9da](https://linux-hardware.org/?probe=38d97cd9da) | Feb 06, 2022 |
| Dell          | XPS 15 9570                 | [d1f8ff2cb8](https://linux-hardware.org/?probe=d1f8ff2cb8) | Feb 02, 2022 |
| Dell          | Latitude 3410               | [8f2181125e](https://linux-hardware.org/?probe=8f2181125e) | Jan 27, 2022 |
| ASUSTek       | X553MA                      | [a748bb8955](https://linux-hardware.org/?probe=a748bb8955) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [08613587e8](https://linux-hardware.org/?probe=08613587e8) | Jan 18, 2022 |
| ASUSTek       | X553MA                      | [f5b0fd8e22](https://linux-hardware.org/?probe=f5b0fd8e22) | Jan 18, 2022 |
| Dell          | XPS 12 9Q23                 | [3c8e26636b](https://linux-hardware.org/?probe=3c8e26636b) | Jan 15, 2022 |
| Dell          | Latitude E5400              | [4f72d3dae0](https://linux-hardware.org/?probe=4f72d3dae0) | Jan 09, 2022 |
| ASUSTek       | X541SA                      | [4103077e59](https://linux-hardware.org/?probe=4103077e59) | Jan 08, 2022 |
| Lenovo        | Flex 2-14 20404             | [1ddb6e11fb](https://linux-hardware.org/?probe=1ddb6e11fb) | Jan 01, 2022 |
| Acer          | Aspire A515-43              | [82163f143b](https://linux-hardware.org/?probe=82163f143b) | Dec 29, 2021 |
| Lenovo        | ThinkPad X131e 33722VU      | [c8dc197420](https://linux-hardware.org/?probe=c8dc197420) | Dec 26, 2021 |
| Lenovo        | G580 2189                   | [843f8c04fe](https://linux-hardware.org/?probe=843f8c04fe) | Dec 21, 2021 |
| HP            | ENVY Notebook               | [69b60fabe0](https://linux-hardware.org/?probe=69b60fabe0) | Dec 15, 2021 |
| Acer          | Aspire ES1-523              | [66a8186276](https://linux-hardware.org/?probe=66a8186276) | Dec 15, 2021 |
| Unknown       | Unknown                     | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| HP            | EliteBook Folio 9480m       | [2cd39490da](https://linux-hardware.org/?probe=2cd39490da) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [4f46a6c92a](https://linux-hardware.org/?probe=4f46a6c92a) | Dec 02, 2021 |
| Apple         | MacBookPro9,1               | [1521941a87](https://linux-hardware.org/?probe=1521941a87) | Dec 02, 2021 |
| Dell          | Latitude E6400              | [170f397883](https://linux-hardware.org/?probe=170f397883) | Dec 02, 2021 |
| HP            | EliteBook Folio 9480m       | [3b06bfa748](https://linux-hardware.org/?probe=3b06bfa748) | Dec 01, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [40a204e5f1](https://linux-hardware.org/?probe=40a204e5f1) | Nov 30, 2021 |
| Polaroid      | MP1464PR001                 | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| HP            | EliteBook Folio 9480m       | [8b5c3b008f](https://linux-hardware.org/?probe=8b5c3b008f) | Nov 24, 2021 |
| HP            | EliteBook Folio 9480m       | [bf8ac4dc12](https://linux-hardware.org/?probe=bf8ac4dc12) | Nov 24, 2021 |
| Dell          | Precision 5560              | [aa3dbdc6bb](https://linux-hardware.org/?probe=aa3dbdc6bb) | Nov 22, 2021 |
| Acer          | TravelMate 5720             | [77b5cad080](https://linux-hardware.org/?probe=77b5cad080) | Nov 18, 2021 |
| HP            | ZBook Fury 17.3 inch G8 ... | [63f392ea8b](https://linux-hardware.org/?probe=63f392ea8b) | Nov 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [3ddad52d21](https://linux-hardware.org/?probe=3ddad52d21) | Nov 16, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [162531d482](https://linux-hardware.org/?probe=162531d482) | Nov 16, 2021 |
| Dell          | Vostro 5568                 | [403ef45f63](https://linux-hardware.org/?probe=403ef45f63) | Nov 15, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | [e881f41269](https://linux-hardware.org/?probe=e881f41269) | Nov 14, 2021 |
| AMI           | Unknown                     | [d1cd5b09e1](https://linux-hardware.org/?probe=d1cd5b09e1) | Nov 12, 2021 |
| Toshiba       | Satellite C665              | [a136cdd51d](https://linux-hardware.org/?probe=a136cdd51d) | Nov 11, 2021 |
| HP            | ZBook 15                    | [835fb0e921](https://linux-hardware.org/?probe=835fb0e921) | Nov 10, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c8b67f9143](https://linux-hardware.org/?probe=c8b67f9143) | Nov 08, 2021 |
| GPD           | P2 MAX                      | [9adb3fd2eb](https://linux-hardware.org/?probe=9adb3fd2eb) | Nov 02, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [10e9f4b604](https://linux-hardware.org/?probe=10e9f4b604) | Oct 27, 2021 |
| Dell          | Precision 7520              | [83df635945](https://linux-hardware.org/?probe=83df635945) | Oct 26, 2021 |
| HP            | Pavilion Notebook           | [cd2454732b](https://linux-hardware.org/?probe=cd2454732b) | Oct 25, 2021 |
| Lenovo        | ThinkPad L512 2598A59       | [0bc832bd49](https://linux-hardware.org/?probe=0bc832bd49) | Oct 19, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | [2bc2b5c1d6](https://linux-hardware.org/?probe=2bc2b5c1d6) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [36f407c3aa](https://linux-hardware.org/?probe=36f407c3aa) | Oct 15, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0Q30... | [1b3b80e104](https://linux-hardware.org/?probe=1b3b80e104) | Oct 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [8917a2fc6b](https://linux-hardware.org/?probe=8917a2fc6b) | Oct 15, 2021 |
| HP            | Pavilion Laptop 15-eg0xx... | [3dfc4362d9](https://linux-hardware.org/?probe=3dfc4362d9) | Oct 14, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [b566b7f862](https://linux-hardware.org/?probe=b566b7f862) | Oct 13, 2021 |
| ASUSTek       | U36SD                       | [c426070626](https://linux-hardware.org/?probe=c426070626) | Oct 12, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [26453872b1](https://linux-hardware.org/?probe=26453872b1) | Oct 12, 2021 |
| ASUSTek       | N43SL                       | [c5adc8860e](https://linux-hardware.org/?probe=c5adc8860e) | Oct 09, 2021 |
| Lenovo        | Z51-70 80K6                 | [219e5cd0d5](https://linux-hardware.org/?probe=219e5cd0d5) | Oct 04, 2021 |
| HP            | ProBook 455 G7              | [491cab82de](https://linux-hardware.org/?probe=491cab82de) | Sep 29, 2021 |
| HP            | ProBook 455 G7              | [04ff8f3c32](https://linux-hardware.org/?probe=04ff8f3c32) | Sep 29, 2021 |
| Dell          | Vostro 3350                 | [384af306e6](https://linux-hardware.org/?probe=384af306e6) | Sep 27, 2021 |
| Acer          | Aspire A515-43              | [523fe48a54](https://linux-hardware.org/?probe=523fe48a54) | Sep 19, 2021 |
| Teclast       | F15S                        | [b6fcd1a34d](https://linux-hardware.org/?probe=b6fcd1a34d) | Sep 13, 2021 |
| Teclast       | F15S                        | [93d4fafebd](https://linux-hardware.org/?probe=93d4fafebd) | Sep 13, 2021 |
| Dell          | Vostro 3350                 | [0fdc4bc08a](https://linux-hardware.org/?probe=0fdc4bc08a) | Sep 13, 2021 |
| Dell          | Latitude E7450              | [012bae3aa2](https://linux-hardware.org/?probe=012bae3aa2) | Sep 11, 2021 |
| ASUSTek       | Z550MA                      | [4786139b6b](https://linux-hardware.org/?probe=4786139b6b) | Sep 11, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [812085deb0](https://linux-hardware.org/?probe=812085deb0) | Sep 07, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [5ee9ab86d7](https://linux-hardware.org/?probe=5ee9ab86d7) | Aug 31, 2021 |
| Packard Be... | EasyNote SL65               | [934368dd02](https://linux-hardware.org/?probe=934368dd02) | Aug 20, 2021 |
| Lenovo        | ThinkPad T420 4180PA9       | [17b9828f96](https://linux-hardware.org/?probe=17b9828f96) | Aug 19, 2021 |
| ASUSTek       | X556UAK                     | [70e369f2ba](https://linux-hardware.org/?probe=70e369f2ba) | Aug 19, 2021 |
| Acer          | Extensa 5630                | [f32dfbfe2a](https://linux-hardware.org/?probe=f32dfbfe2a) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| Chuwi         | GemiBook Pro                | [0ffe99b73b](https://linux-hardware.org/?probe=0ffe99b73b) | Aug 14, 2021 |
| ASUSTek       | X556UAK                     | [399d9ceec5](https://linux-hardware.org/?probe=399d9ceec5) | Aug 06, 2021 |
| Intel         | AMI                         | [c11ff5c3a9](https://linux-hardware.org/?probe=c11ff5c3a9) | Aug 06, 2021 |
| Intel         | AMI                         | [bfe9befd10](https://linux-hardware.org/?probe=bfe9befd10) | Aug 05, 2021 |
| Lenovo        | ThinkPad T430s 2356CTO      | [f3d9dd3c21](https://linux-hardware.org/?probe=f3d9dd3c21) | Jul 31, 2021 |
| Acer          | Aspire E1-571               | [561ec14e6b](https://linux-hardware.org/?probe=561ec14e6b) | Jul 25, 2021 |
| Acer          | Aspire E1-571               | [068e66bfae](https://linux-hardware.org/?probe=068e66bfae) | Jul 25, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [49be4c6d59](https://linux-hardware.org/?probe=49be4c6d59) | Jul 23, 2021 |
| Toshiba       | Satellite C660              | [d80d4d487b](https://linux-hardware.org/?probe=d80d4d487b) | Jul 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Dell          | Studio 1558                 | [d1fad8f698](https://linux-hardware.org/?probe=d1fad8f698) | Jul 16, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [9f00795579](https://linux-hardware.org/?probe=9f00795579) | Jul 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [89a5013659](https://linux-hardware.org/?probe=89a5013659) | Jul 09, 2021 |
| Lenovo        | ThinkPad E15 20RES31K00     | [6d359d339e](https://linux-hardware.org/?probe=6d359d339e) | Jul 02, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [90235ac63a](https://linux-hardware.org/?probe=90235ac63a) | Jun 30, 2021 |
| HP            | EliteBook 2170p             | [212819389c](https://linux-hardware.org/?probe=212819389c) | Jun 25, 2021 |
| HP            | Pavilion dv7                | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| Dell          | Latitude E6400              | [547126dd82](https://linux-hardware.org/?probe=547126dd82) | Jun 20, 2021 |
| Dell          | Latitude E6510              | [ee7157e97d](https://linux-hardware.org/?probe=ee7157e97d) | Jun 11, 2021 |
| ASUSTek       | K73SJ                       | [cb0f042995](https://linux-hardware.org/?probe=cb0f042995) | Jun 04, 2021 |
| Dell          | Latitude 7420               | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [59df1ed0f5](https://linux-hardware.org/?probe=59df1ed0f5) | Jun 03, 2021 |
| HP            | Pavilion                    | [1fa0cb66b1](https://linux-hardware.org/?probe=1fa0cb66b1) | May 26, 2021 |
| Dell          | Precision M4800             | [a85ce8a041](https://linux-hardware.org/?probe=a85ce8a041) | May 24, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Dell          | G7 7588                     | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| Cube          | i18-L                       | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| HP            | Pavilion                    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| ONE-NETBOO... | A1                          | [86c38b0aca](https://linux-hardware.org/?probe=86c38b0aca) | Apr 23, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [3835eff7c6](https://linux-hardware.org/?probe=3835eff7c6) | Apr 21, 2021 |
| Dell          | Inspiron 3480               | [75f43079fb](https://linux-hardware.org/?probe=75f43079fb) | Apr 13, 2021 |
| Dell          | Inspiron 3480               | [dce5f8220a](https://linux-hardware.org/?probe=dce5f8220a) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fb0db0afbd](https://linux-hardware.org/?probe=fb0db0afbd) | Apr 13, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [236be7c7e7](https://linux-hardware.org/?probe=236be7c7e7) | Apr 12, 2021 |
| HP            | Pavilion dv6                | [bf634bb665](https://linux-hardware.org/?probe=bf634bb665) | Apr 09, 2021 |
| HP            | 15                          | [acc9ccddfa](https://linux-hardware.org/?probe=acc9ccddfa) | Apr 08, 2021 |
| HP            | ProBook 4530s               | [12a7784eb4](https://linux-hardware.org/?probe=12a7784eb4) | Apr 06, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [fa8acecaa2](https://linux-hardware.org/?probe=fa8acecaa2) | Apr 01, 2021 |
| Dell          | Latitude E7250              | [d88e8eb416](https://linux-hardware.org/?probe=d88e8eb416) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| Dell          | Latitude 7310               | [9f4c2f64a5](https://linux-hardware.org/?probe=9f4c2f64a5) | Mar 30, 2021 |
| Dell          | Latitude E7250              | [d1716d96f2](https://linux-hardware.org/?probe=d1716d96f2) | Mar 28, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [dc5e67af5a](https://linux-hardware.org/?probe=dc5e67af5a) | Mar 27, 2021 |
| Acer          | Aspire 4740                 | [3551944dd9](https://linux-hardware.org/?probe=3551944dd9) | Mar 25, 2021 |
| Samsung       | 760XBE                      | [3cacabef7b](https://linux-hardware.org/?probe=3cacabef7b) | Mar 23, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [92bcacad15](https://linux-hardware.org/?probe=92bcacad15) | Mar 22, 2021 |
| Samsung       | 760XBE                      | [26e28d0645](https://linux-hardware.org/?probe=26e28d0645) | Mar 21, 2021 |
| ASUSTek       | K50IE                       | [cc01498ee9](https://linux-hardware.org/?probe=cc01498ee9) | Mar 18, 2021 |
| MSI           | GF63 Thin 9SCSR             | [f58ddcc3f4](https://linux-hardware.org/?probe=f58ddcc3f4) | Mar 17, 2021 |
| Acer          | Aspire A515-56              | [1919b6a57f](https://linux-hardware.org/?probe=1919b6a57f) | Mar 17, 2021 |
| HP            | Pavilion g7                 | [cc361e0dbf](https://linux-hardware.org/?probe=cc361e0dbf) | Mar 04, 2021 |
| Toshiba       | Satellite L350D             | [0286dc8c95](https://linux-hardware.org/?probe=0286dc8c95) | Mar 02, 2021 |
| HP            | Pavilion g7                 | [41d55a3dd7](https://linux-hardware.org/?probe=41d55a3dd7) | Feb 26, 2021 |
| Dell          | Precision M4800             | [45c92f0ad1](https://linux-hardware.org/?probe=45c92f0ad1) | Feb 22, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [5bd6c548d2](https://linux-hardware.org/?probe=5bd6c548d2) | Feb 15, 2021 |
| Positivo      | N8X0EK1                     | [c6ac8d6eca](https://linux-hardware.org/?probe=c6ac8d6eca) | Feb 15, 2021 |
| Dell          | Latitude E6500              | [75d199bcfd](https://linux-hardware.org/?probe=75d199bcfd) | Feb 12, 2021 |
| Dell          | Studio 1747                 | [4ca3a3577f](https://linux-hardware.org/?probe=4ca3a3577f) | Feb 11, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | [952ca96633](https://linux-hardware.org/?probe=952ca96633) | Feb 09, 2021 |
| Notebook      | W310CZ/CZ-T                 | [2b60fc9e91](https://linux-hardware.org/?probe=2b60fc9e91) | Feb 09, 2021 |
| Acer          | Aspire ES1-521              | [73b3295031](https://linux-hardware.org/?probe=73b3295031) | Jan 29, 2021 |
| Dell          | G7 7588                     | [ae6d47978a](https://linux-hardware.org/?probe=ae6d47978a) | Jan 28, 2021 |
| Lenovo        | ThinkPad W520 4284HP9       | [4cae7dc78d](https://linux-hardware.org/?probe=4cae7dc78d) | Jan 18, 2021 |
| HP            | 250 G5 Notebook PC          | [f2e3b573f5](https://linux-hardware.org/?probe=f2e3b573f5) | Jan 16, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [e8b3cf2cbd](https://linux-hardware.org/?probe=e8b3cf2cbd) | Jan 14, 2021 |
| Lenovo        | ThinkPad E490 20N9001SBR    | [8117aff9b0](https://linux-hardware.org/?probe=8117aff9b0) | Jan 14, 2021 |
| Medion        | X682X                       | [bf7dbceaa3](https://linux-hardware.org/?probe=bf7dbceaa3) | Jan 13, 2021 |
| Dell          | XPS 13 9370                 | [1b3b03be98](https://linux-hardware.org/?probe=1b3b03be98) | Jan 07, 2021 |
| HP            | 255 G7 Notebook PC          | [4f385a65db](https://linux-hardware.org/?probe=4f385a65db) | Jan 03, 2021 |
| Samsung       | SR58P                       | [efbf027f96](https://linux-hardware.org/?probe=efbf027f96) | Jan 03, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [e253bc608d](https://linux-hardware.org/?probe=e253bc608d) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [1483935c23](https://linux-hardware.org/?probe=1483935c23) | Jan 02, 2021 |
| Acer          | Aspire E1-532P              | [a1f1287741](https://linux-hardware.org/?probe=a1f1287741) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [30041ef295](https://linux-hardware.org/?probe=30041ef295) | Jan 01, 2021 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [c38d67b61b](https://linux-hardware.org/?probe=c38d67b61b) | Dec 30, 2020 |
| HP            | Notebook                    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA32VLM    | [cfa92bb7f3](https://linux-hardware.org/?probe=cfa92bb7f3) | Dec 28, 2020 |
| ASUSTek       | X302LA                      | [f5dde37fb9](https://linux-hardware.org/?probe=f5dde37fb9) | Dec 26, 2020 |
| ASUSTek       | X302LA                      | [a35e9f4b28](https://linux-hardware.org/?probe=a35e9f4b28) | Dec 25, 2020 |
| Star Labs     | LabTop                      | [b8c8467e92](https://linux-hardware.org/?probe=b8c8467e92) | Dec 20, 2020 |
| Toshiba       | Satellite Pro L500          | [d01d9e0d34](https://linux-hardware.org/?probe=d01d9e0d34) | Dec 08, 2020 |
| Dell          | Inspiron 3520               | [be6f5d9f85](https://linux-hardware.org/?probe=be6f5d9f85) | Dec 07, 2020 |
| Dell          | Latitude D630               | [475177f3da](https://linux-hardware.org/?probe=475177f3da) | Dec 07, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [5862508036](https://linux-hardware.org/?probe=5862508036) | Dec 06, 2020 |
| HP            | Pavilion 17                 | [2f04deaf4e](https://linux-hardware.org/?probe=2f04deaf4e) | Dec 03, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [ee0aa7b52f](https://linux-hardware.org/?probe=ee0aa7b52f) | Dec 02, 2020 |
| Dell          | Precision 7710              | [f017e7a0d2](https://linux-hardware.org/?probe=f017e7a0d2) | Nov 30, 2020 |
| Acer          | Aspire E5-523               | [cfd9403111](https://linux-hardware.org/?probe=cfd9403111) | Nov 29, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [7249400d79](https://linux-hardware.org/?probe=7249400d79) | Nov 29, 2020 |
| Dell          | Latitude E6400              | [a39e2e7fa3](https://linux-hardware.org/?probe=a39e2e7fa3) | Nov 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [833a22d4ee](https://linux-hardware.org/?probe=833a22d4ee) | Nov 20, 2020 |
| HP            | EliteBook 830 G6            | [c47a2f5f86](https://linux-hardware.org/?probe=c47a2f5f86) | Nov 18, 2020 |
| Pine Micro... | Pine64 Pinebook Pro         | [08c8440950](https://linux-hardware.org/?probe=08c8440950) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [968f302807](https://linux-hardware.org/?probe=968f302807) | Nov 17, 2020 |
| Lenovo        | ThinkPad T440 20B7S2E401    | [2a9231cde8](https://linux-hardware.org/?probe=2a9231cde8) | Nov 17, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [b8e7eedfed](https://linux-hardware.org/?probe=b8e7eedfed) | Nov 17, 2020 |
| Dell          | Latitude E6420              | [3452613a4c](https://linux-hardware.org/?probe=3452613a4c) | Nov 16, 2020 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d7abac1c02](https://linux-hardware.org/?probe=d7abac1c02) | Nov 07, 2020 |
| HP            | EliteBook Folio 9470m       | [659c1c8745](https://linux-hardware.org/?probe=659c1c8745) | Nov 06, 2020 |
| HP            | EliteBook Folio 9470m       | [248ce84271](https://linux-hardware.org/?probe=248ce84271) | Nov 05, 2020 |
| Dell          | Latitude E6420              | [6cdd815251](https://linux-hardware.org/?probe=6cdd815251) | Nov 04, 2020 |
| Dell          | Latitude E6420              | [10d44f2853](https://linux-hardware.org/?probe=10d44f2853) | Nov 04, 2020 |
| Acer          | Aspire A314-32              | [686d0b8c4f](https://linux-hardware.org/?probe=686d0b8c4f) | Nov 03, 2020 |
| Dell          | Latitude E6430              | [39ba29b6a3](https://linux-hardware.org/?probe=39ba29b6a3) | Nov 02, 2020 |
| Notebook      | W54_W94_W955TU,-T,-C        | [d9a9dae79a](https://linux-hardware.org/?probe=d9a9dae79a) | Oct 31, 2020 |
| Lenovo        | ThinkPad E520 1143B5G       | [146fc730d7](https://linux-hardware.org/?probe=146fc730d7) | Oct 29, 2020 |
| MSI           | GE72 7RE                    | [f75b251f96](https://linux-hardware.org/?probe=f75b251f96) | Oct 29, 2020 |
| Acer          | Aspire 5715Z                | [a2fca6b9da](https://linux-hardware.org/?probe=a2fca6b9da) | Oct 26, 2020 |
| Lenovo        | V570 HuronRiver Platform    | [62082c183e](https://linux-hardware.org/?probe=62082c183e) | Oct 26, 2020 |
| ASUSTek       | X751LK                      | [0dad6a22c5](https://linux-hardware.org/?probe=0dad6a22c5) | Oct 26, 2020 |
| HP            | Pavilion dv7                | [59e2fce913](https://linux-hardware.org/?probe=59e2fce913) | Oct 26, 2020 |
| Dell          | Precision M4800             | [2f91204b5e](https://linux-hardware.org/?probe=2f91204b5e) | Oct 26, 2020 |
| HP            | 255 G7 Notebook PC          | [fd598f0888](https://linux-hardware.org/?probe=fd598f0888) | Oct 25, 2020 |
| Dell          | G3 3590                     | [3e9d16279b](https://linux-hardware.org/?probe=3e9d16279b) | Oct 21, 2020 |
| Lenovo        | ThinkPad E560 20EV0013MS    | [6a0824824b](https://linux-hardware.org/?probe=6a0824824b) | Oct 20, 2020 |
| Dell          | Latitude E6430              | [67b44ea2b4](https://linux-hardware.org/?probe=67b44ea2b4) | Oct 20, 2020 |
| HP            | Compaq 6730s                | [b8d5fd5eea](https://linux-hardware.org/?probe=b8d5fd5eea) | Oct 19, 2020 |
| HP            | Notebook                    | [669e2e8ce6](https://linux-hardware.org/?probe=669e2e8ce6) | Oct 19, 2020 |
| Lenovo        | G50-80 80R0                 | [51ec4152a2](https://linux-hardware.org/?probe=51ec4152a2) | Oct 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c45c0eb7e4](https://linux-hardware.org/?probe=c45c0eb7e4) | Oct 16, 2020 |
| HP            | ProBook 4430s               | [c816b204bf](https://linux-hardware.org/?probe=c816b204bf) | Oct 15, 2020 |
| Lenovo        | ThinkPad X270 20HN0013MX    | [3dbb81e06d](https://linux-hardware.org/?probe=3dbb81e06d) | Oct 14, 2020 |
| Dell          | Latitude E6420              | [1e2a1974f2](https://linux-hardware.org/?probe=1e2a1974f2) | Oct 08, 2020 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [01948526e2](https://linux-hardware.org/?probe=01948526e2) | Oct 08, 2020 |
| Acer          | Aspire 5715Z                | [e112fe04f3](https://linux-hardware.org/?probe=e112fe04f3) | Oct 08, 2020 |
| Medion        | E15302                      | [957a41b1b5](https://linux-hardware.org/?probe=957a41b1b5) | Oct 07, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [28bab55cdf](https://linux-hardware.org/?probe=28bab55cdf) | Oct 02, 2020 |
| Lenovo        | ThinkPad X230 2325W5W       | [e2a36190d7](https://linux-hardware.org/?probe=e2a36190d7) | Oct 02, 2020 |
| Acer          | Aspire A314-32              | [a51d2f268d](https://linux-hardware.org/?probe=a51d2f268d) | Oct 02, 2020 |
| System76      | Serval WS                   | [7add8e6511](https://linux-hardware.org/?probe=7add8e6511) | Sep 25, 2020 |
| Dell          | Precision M6700             | [1b20609aaa](https://linux-hardware.org/?probe=1b20609aaa) | Sep 25, 2020 |
| HP            | ProBook 440 G5              | [3140b90a75](https://linux-hardware.org/?probe=3140b90a75) | Sep 24, 2020 |
| Apple         | MacBook4,1                  | [91c2f7bfb9](https://linux-hardware.org/?probe=91c2f7bfb9) | Sep 20, 2020 |
| Dell          | Latitude E6410              | [6fa6138bb4](https://linux-hardware.org/?probe=6fa6138bb4) | Sep 18, 2020 |
| Dell          | Latitude E6410              | [8a3b88673f](https://linux-hardware.org/?probe=8a3b88673f) | Sep 17, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [a96ad52bc9](https://linux-hardware.org/?probe=a96ad52bc9) | Sep 16, 2020 |
| Dell          | Latitude E6410              | [8930b7e16f](https://linux-hardware.org/?probe=8930b7e16f) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [299b899172](https://linux-hardware.org/?probe=299b899172) | Sep 16, 2020 |
| HP            | EliteBook 8470p             | [b45cb0028d](https://linux-hardware.org/?probe=b45cb0028d) | Sep 16, 2020 |
| HP            | Compaq 8710w (GC124EA#AK... | [dc5006e254](https://linux-hardware.org/?probe=dc5006e254) | Sep 15, 2020 |
| Apple         | MacBook4,1                  | [092f9a6491](https://linux-hardware.org/?probe=092f9a6491) | Sep 15, 2020 |
| HP            | G42                         | [9cb42d6f5f](https://linux-hardware.org/?probe=9cb42d6f5f) | Sep 15, 2020 |
| HP            | G42                         | [72d647e1b9](https://linux-hardware.org/?probe=72d647e1b9) | Sep 15, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [956bfaaad9](https://linux-hardware.org/?probe=956bfaaad9) | Sep 11, 2020 |
| Acer          | Aspire A315-42G             | [ab24b14a42](https://linux-hardware.org/?probe=ab24b14a42) | Sep 09, 2020 |
| Samsung       | 530U4E/540U4E               | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| Dell          | Latitude E6420              | [e3bc793dc3](https://linux-hardware.org/?probe=e3bc793dc3) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [676828b4d4](https://linux-hardware.org/?probe=676828b4d4) | Sep 03, 2020 |
| Dell          | Latitude E6420              | [6057658605](https://linux-hardware.org/?probe=6057658605) | Sep 01, 2020 |
| Dell          | Latitude E6420              | [9b1f1928c7](https://linux-hardware.org/?probe=9b1f1928c7) | Sep 01, 2020 |
| Positivo      | Mobile                      | [2249764f28](https://linux-hardware.org/?probe=2249764f28) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [cae373d70b](https://linux-hardware.org/?probe=cae373d70b) | Aug 30, 2020 |
| HP            | Laptop 15-bw0xx             | [c77cf6f3fa](https://linux-hardware.org/?probe=c77cf6f3fa) | Aug 30, 2020 |
| Toshiba       | Satellite M500              | [42449081bb](https://linux-hardware.org/?probe=42449081bb) | Aug 29, 2020 |
| HP            | 250 G4 Notebook PC          | [97eeff2c12](https://linux-hardware.org/?probe=97eeff2c12) | Aug 22, 2020 |
| Lenovo        | ThinkPad W530 24478K0       | [74fda860f1](https://linux-hardware.org/?probe=74fda860f1) | Aug 17, 2020 |
| HP            | ZBook 14u G6                | [ad30c07ac3](https://linux-hardware.org/?probe=ad30c07ac3) | Aug 17, 2020 |
| MSI           | GP72MVR 7RFX                | [39da2f58b5](https://linux-hardware.org/?probe=39da2f58b5) | Aug 16, 2020 |
| Dell          | Inspiron 7559               | [021ed0aac6](https://linux-hardware.org/?probe=021ed0aac6) | Aug 16, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [0e5e076914](https://linux-hardware.org/?probe=0e5e076914) | Aug 15, 2020 |
| GPD           | MicroPC                     | [bb39ae1b31](https://linux-hardware.org/?probe=bb39ae1b31) | Aug 15, 2020 |
| Sony          | VPCEH1S1E                   | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [3e086d75b0](https://linux-hardware.org/?probe=3e086d75b0) | Aug 12, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ab576b0cd8](https://linux-hardware.org/?probe=ab576b0cd8) | Aug 12, 2020 |
| ASUSTek       | X71SL                       | [f2da7fe3f0](https://linux-hardware.org/?probe=f2da7fe3f0) | Aug 12, 2020 |
| HP            | ZBook 14u G6                | [10911e8e46](https://linux-hardware.org/?probe=10911e8e46) | Aug 11, 2020 |
| HP            | Pavilion dm1                | [ccb974921b](https://linux-hardware.org/?probe=ccb974921b) | Aug 05, 2020 |
| ASUSTek       | X71SL                       | [7bfd99a9bd](https://linux-hardware.org/?probe=7bfd99a9bd) | Aug 05, 2020 |
| Dell          | System XPS L702X            | [86885b0835](https://linux-hardware.org/?probe=86885b0835) | Aug 04, 2020 |
| MSI           | GV62 8RD                    | [0b6cd63268](https://linux-hardware.org/?probe=0b6cd63268) | Aug 04, 2020 |
| Dell          | Inspiron 3421               | [09aac7d871](https://linux-hardware.org/?probe=09aac7d871) | Aug 01, 2020 |
| Dell          | Precision M4800             | [defc3ac914](https://linux-hardware.org/?probe=defc3ac914) | Aug 01, 2020 |
| Lenovo        | Flex 2-14D 20376            | [efd445830e](https://linux-hardware.org/?probe=efd445830e) | Jul 27, 2020 |
| Dell          | Inspiron 7520               | [a1ea369f96](https://linux-hardware.org/?probe=a1ea369f96) | Jul 27, 2020 |
| Dell          | Inspiron 3421               | [12424c5a76](https://linux-hardware.org/?probe=12424c5a76) | Jul 25, 2020 |
| HP            | Pavilion g4                 | [a10cfaa6e2](https://linux-hardware.org/?probe=a10cfaa6e2) | Jul 24, 2020 |
| HP            | EliteBook 2570p             | [baa26535f9](https://linux-hardware.org/?probe=baa26535f9) | Jul 23, 2020 |
| Dell          | Vostro 3560                 | [c83b65951c](https://linux-hardware.org/?probe=c83b65951c) | Jul 20, 2020 |
| HP            | ZBook 17 G2                 | [61d82db95d](https://linux-hardware.org/?probe=61d82db95d) | Jul 20, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [8e5e5de5c3](https://linux-hardware.org/?probe=8e5e5de5c3) | Jul 20, 2020 |
| HP            | 250 G5 Notebook PC          | [9577cafcf7](https://linux-hardware.org/?probe=9577cafcf7) | Jul 19, 2020 |
| Lenovo        | ThinkPad T490 20N3CTO1WW    | [b6f9682f0b](https://linux-hardware.org/?probe=b6f9682f0b) | Jul 15, 2020 |
| ASUSTek       | X555LJ                      | [5657a6a512](https://linux-hardware.org/?probe=5657a6a512) | Jul 14, 2020 |
| Dell          | G7 7588                     | [8c4a8875bd](https://linux-hardware.org/?probe=8c4a8875bd) | Jul 14, 2020 |
| Dell          | G7 7588                     | [aee8398552](https://linux-hardware.org/?probe=aee8398552) | Jul 12, 2020 |
| Sony          | VPCF1290X                   | [f7c7a3ca92](https://linux-hardware.org/?probe=f7c7a3ca92) | Jul 08, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [f4dd6bbdec](https://linux-hardware.org/?probe=f4dd6bbdec) | Jul 06, 2020 |
| Lenovo        | ThinkPad 11e 20D9CTO1WW     | [11c17aa062](https://linux-hardware.org/?probe=11c17aa062) | Jul 05, 2020 |
| Acer          | Aspire 7750G                | [f6a31e475d](https://linux-hardware.org/?probe=f6a31e475d) | Jul 05, 2020 |
| HP            | 250 G4                      | [ca40ef5473](https://linux-hardware.org/?probe=ca40ef5473) | Jul 02, 2020 |
| HP            | Pavilion g6                 | [0175164903](https://linux-hardware.org/?probe=0175164903) | Jul 01, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [561adcd20d](https://linux-hardware.org/?probe=561adcd20d) | Jun 30, 2020 |
| HP            | Pavilion g6                 | [efc97f097b](https://linux-hardware.org/?probe=efc97f097b) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [944b66e3ba](https://linux-hardware.org/?probe=944b66e3ba) | Jun 28, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [3f58959650](https://linux-hardware.org/?probe=3f58959650) | Jun 24, 2020 |
| Lenovo        | ThinkPad T520 4243RS6       | [881175c7ec](https://linux-hardware.org/?probe=881175c7ec) | Jun 23, 2020 |
| HP            | ProBook 450 G5              | [143bbac73c](https://linux-hardware.org/?probe=143bbac73c) | Jun 23, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0Y80... | [c5a7e2708f](https://linux-hardware.org/?probe=c5a7e2708f) | Jun 22, 2020 |
| Lenovo        | ThinkPad X240 qqqq          | [04328e30ac](https://linux-hardware.org/?probe=04328e30ac) | Jun 15, 2020 |
| Sony          | VPCF1290X                   | [55652dadf6](https://linux-hardware.org/?probe=55652dadf6) | Jun 15, 2020 |
| Lenovo        | ThinkPad T430 2349H86       | [5ef2ab445e](https://linux-hardware.org/?probe=5ef2ab445e) | Jun 13, 2020 |
| Lenovo        | ThinkPad L430 24681R3       | [5467542c77](https://linux-hardware.org/?probe=5467542c77) | Jun 12, 2020 |
| HP            | Pavilion g6                 | [78f5ccb141](https://linux-hardware.org/?probe=78f5ccb141) | Jun 11, 2020 |
| Acer          | Nitro AN515-54              | [4c810c7859](https://linux-hardware.org/?probe=4c810c7859) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [35995e9a53](https://linux-hardware.org/?probe=35995e9a53) | Jun 06, 2020 |
| ASUSTek       | X541SA                      | [508fc56922](https://linux-hardware.org/?probe=508fc56922) | Jun 06, 2020 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [d6bcbe862e](https://linux-hardware.org/?probe=d6bcbe862e) | Jun 05, 2020 |
| HP            | 250 G7 Notebook PC          | [56c24dddd4](https://linux-hardware.org/?probe=56c24dddd4) | May 31, 2020 |
| Packard Be... | EasyNote ME69BMP            | [7023dc94da](https://linux-hardware.org/?probe=7023dc94da) | May 28, 2020 |
| Dell          | Precision M6800             | [fac8dbf769](https://linux-hardware.org/?probe=fac8dbf769) | May 28, 2020 |
| Packard Be... | EasyNote ME69BMP            | [17cb4d2a9a](https://linux-hardware.org/?probe=17cb4d2a9a) | May 28, 2020 |
| Dell          | Precision M4800             | [4f404379b5](https://linux-hardware.org/?probe=4f404379b5) | May 27, 2020 |
| Lenovo        | ThinkPad T440 20B7S0F100    | [4a1413e289](https://linux-hardware.org/?probe=4a1413e289) | May 26, 2020 |
| Lenovo        | ThinkPad T480s 20L7001HM... | [8c6c9a5faa](https://linux-hardware.org/?probe=8c6c9a5faa) | May 25, 2020 |
| Toshiba       | Satellite M500              | [89bc529650](https://linux-hardware.org/?probe=89bc529650) | May 23, 2020 |
| Sony          | VPCF1290X                   | [6d41a82565](https://linux-hardware.org/?probe=6d41a82565) | May 22, 2020 |
| Sony          | VPCF1290X                   | [e260c25549](https://linux-hardware.org/?probe=e260c25549) | May 20, 2020 |
| ASUSTek       | X541SA                      | [af59d45f16](https://linux-hardware.org/?probe=af59d45f16) | May 19, 2020 |
| Dell          | Latitude E6400              | [5575a3dc87](https://linux-hardware.org/?probe=5575a3dc87) | May 17, 2020 |
| Dell          | Latitude E6400              | [4ad76f6e55](https://linux-hardware.org/?probe=4ad76f6e55) | May 16, 2020 |
| Dell          | Latitude E6400              | [9c8f7c7f2c](https://linux-hardware.org/?probe=9c8f7c7f2c) | May 16, 2020 |
| Dell          | Latitude E6400              | [0e2b5d699e](https://linux-hardware.org/?probe=0e2b5d699e) | May 16, 2020 |
| HP            | 250 G1                      | [bc48855d22](https://linux-hardware.org/?probe=bc48855d22) | May 16, 2020 |
| Lenovo        | ThinkPad X240 20AMS08816    | [5581eee295](https://linux-hardware.org/?probe=5581eee295) | May 10, 2020 |
| Dell          | System XPS L502X            | [f095fb06d8](https://linux-hardware.org/?probe=f095fb06d8) | May 09, 2020 |
| HP            | EliteBook 840 G2            | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Samsung       | 550P5C/550P7C               | [4262f676d3](https://linux-hardware.org/?probe=4262f676d3) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [015ef81b51](https://linux-hardware.org/?probe=015ef81b51) | May 02, 2020 |
| ASUSTek       | G73Sw                       | [d4abec1a93](https://linux-hardware.org/?probe=d4abec1a93) | May 02, 2020 |
| HP            | 250 G5 Notebook PC          | [f986b480ad](https://linux-hardware.org/?probe=f986b480ad) | May 01, 2020 |
| Dell          | Inspiron 3576               | [4dc9474ba1](https://linux-hardware.org/?probe=4dc9474ba1) | Apr 29, 2020 |
| Sony          | VPCS12X9E                   | [3631a4d89d](https://linux-hardware.org/?probe=3631a4d89d) | Apr 24, 2020 |
| Lenovo        | ThinkPad T460s 20F9003WM... | [1b1c89732c](https://linux-hardware.org/?probe=1b1c89732c) | Apr 19, 2020 |
| HP            | EliteBook 755 G5            | [db0ea12ab8](https://linux-hardware.org/?probe=db0ea12ab8) | Apr 16, 2020 |
| Dell          | XPS 13 9360                 | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [154b970640](https://linux-hardware.org/?probe=154b970640) | Mar 25, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [ad9b0ebdf6](https://linux-hardware.org/?probe=ad9b0ebdf6) | Feb 25, 2020 |
| Acer          | Aspire V3-574G              | [471f9aa9b0](https://linux-hardware.org/?probe=471f9aa9b0) | Jan 02, 2020 |
| MSI           | GP72 6QF                    | [98dc37dc79](https://linux-hardware.org/?probe=98dc37dc79) | Oct 21, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.4.0-42-generic     | 24        | 8.14%   |
| 5.4.0-52-generic     | 17        | 5.76%   |
| 5.4.0-47-generic     | 10        | 3.39%   |
| 5.4.0-40-generic     | 10        | 3.39%   |
| 5.4.0-58-generic     | 9         | 3.05%   |
| 5.8.0-50-generic     | 8         | 2.71%   |
| 5.4.0-48-generic     | 8         | 2.71%   |
| 5.4.0-31-generic     | 8         | 2.71%   |
| 5.4.0-65-generic     | 7         | 2.37%   |
| 5.4.0-26-generic     | 7         | 2.37%   |
| 5.11.0-40-generic    | 7         | 2.37%   |
| 5.4.0-56-generic     | 6         | 2.03%   |
| 5.4.0-54-generic     | 6         | 2.03%   |
| 5.4.0-45-generic     | 6         | 2.03%   |
| 5.8.0-59-generic     | 5         | 1.69%   |
| 5.8.0-48-generic     | 5         | 1.69%   |
| 5.8.0-43-generic     | 5         | 1.69%   |
| 5.4.0-81-generic     | 5         | 1.69%   |
| 5.4.0-37-generic     | 5         | 1.69%   |
| 5.4.0-29-generic     | 5         | 1.69%   |
| 5.13.0-41-generic    | 5         | 1.69%   |
| 5.11.0-38-generic    | 5         | 1.69%   |
| 5.11.0-37-generic    | 5         | 1.69%   |
| 5.8.0-53-generic     | 4         | 1.36%   |
| 5.4.0-91-generic     | 4         | 1.36%   |
| 5.4.0-89-generic     | 4         | 1.36%   |
| 5.4.0-51-generic     | 4         | 1.36%   |
| 5.13.0-39-generic    | 4         | 1.36%   |
| 5.13.0-30-generic    | 4         | 1.36%   |
| 5.4.0-90-generic     | 3         | 1.02%   |
| 5.4.0-74-generic     | 3         | 1.02%   |
| 5.4.0-73-generic     | 3         | 1.02%   |
| 5.4.0-39-generic     | 3         | 1.02%   |
| 5.4.0-33-generic     | 3         | 1.02%   |
| 5.4.0-28-generic     | 3         | 1.02%   |
| 5.11.0-43-generic    | 3         | 1.02%   |
| 5.11.0-41-generic    | 3         | 1.02%   |
| 5.8.0-63-generic     | 2         | 0.68%   |
| 5.8.0-45-generic     | 2         | 0.68%   |
| 5.8.0-38-generic     | 2         | 0.68%   |
| 5.4.0-80-generic     | 2         | 0.68%   |
| 5.4.0-72-generic     | 2         | 0.68%   |
| 5.4.0-70-generic     | 2         | 0.68%   |
| 5.4.0-67-generic     | 2         | 0.68%   |
| 5.4.0-66-generic     | 2         | 0.68%   |
| 5.4.0-14-generic     | 2         | 0.68%   |
| 5.13.0-44-generic    | 2         | 0.68%   |
| 5.13.0-40-generic    | 2         | 0.68%   |
| 5.11.0-46-generic    | 2         | 0.68%   |
| 5.9.3-050903-generic | 1         | 0.34%   |
| 5.8.17-rockchip64    | 1         | 0.34%   |
| 5.8.0-52-generic     | 1         | 0.34%   |
| 5.8.0-34-generic     | 1         | 0.34%   |
| 5.8.0-33-generic     | 1         | 0.34%   |
| 5.4.0-99-generic     | 1         | 0.34%   |
| 5.4.0-96-generic     | 1         | 0.34%   |
| 5.4.0-9-generic      | 1         | 0.34%   |
| 5.4.0-88-generic     | 1         | 0.34%   |
| 5.4.0-84-generic     | 1         | 0.34%   |
| 5.4.0-77-generic     | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 175       | 64.81%  |
| 5.8.0   | 33        | 12.22%  |
| 5.11.0  | 29        | 10.74%  |
| 5.13.0  | 24        | 8.89%   |
| 5.14.0  | 3         | 1.11%   |
| 5.3.0   | 2         | 0.74%   |
| 5.9.3   | 1         | 0.37%   |
| 5.8.17  | 1         | 0.37%   |
| 5.15.6  | 1         | 0.37%   |
| 5.15.34 | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 175       | 64.81%  |
| 5.8     | 34        | 12.59%  |
| 5.11    | 29        | 10.74%  |
| 5.13    | 24        | 8.89%   |
| 5.14    | 3         | 1.11%   |
| 5.3     | 2         | 0.74%   |
| 5.15    | 2         | 0.74%   |
| 5.9     | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 267       | 99.63%  |
| aarch64 | 1         | 0.37%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 261       | 97.39%  |
| GNOME      | 2         | 0.75%   |
| Cinnamon   | 2         | 0.75%   |
| X-Cinnamon | 1         | 0.37%   |
| KDE5       | 1         | 0.37%   |
| i3         | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 262       | 97.76%  |
| Wayland | 3         | 1.12%   |
| Tty     | 3         | 1.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 99        | 36.13%  |
| LightDM | 82        | 29.93%  |
| Unknown | 74        | 27.01%  |
| GDM     | 15        | 5.47%   |
| GDM3    | 3         | 1.09%   |
| SDDM    | 1         | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 99        | 36.8%   |
| pt_BR   | 27        | 10.04%  |
| fr_FR   | 27        | 10.04%  |
| en_GB   | 17        | 6.32%   |
| de_DE   | 14        | 5.2%    |
| es_ES   | 11        | 4.09%   |
| it_IT   | 10        | 3.72%   |
| ru_RU   | 8         | 2.97%   |
| ru_UA   | 6         | 2.23%   |
| C       | 6         | 2.23%   |
| pl_PL   | 5         | 1.86%   |
| es_AR   | 4         | 1.49%   |
| en_PH   | 3         | 1.12%   |
| de_CH   | 3         | 1.12%   |
| nl_NL   | 2         | 0.74%   |
| en_IN   | 2         | 0.74%   |
| en_CA   | 2         | 0.74%   |
| ca_ES   | 2         | 0.74%   |
| zh_TW   | 1         | 0.37%   |
| zh_CN   | 1         | 0.37%   |
| uk_UA   | 1         | 0.37%   |
| sv_SE   | 1         | 0.37%   |
| sk_SK   | 1         | 0.37%   |
| hu_HU   | 1         | 0.37%   |
| fr_CH   | 1         | 0.37%   |
| fr_CA   | 1         | 0.37%   |
| fr_BE   | 1         | 0.37%   |
| fi_FI   | 1         | 0.37%   |
| et_EE   | 1         | 0.37%   |
| es_UY   | 1         | 0.37%   |
| es_PR   | 1         | 0.37%   |
| es_PE   | 1         | 0.37%   |
| es_MX   | 1         | 0.37%   |
| en_NZ   | 1         | 0.37%   |
| en_IE   | 1         | 0.37%   |
| en_AU   | 1         | 0.37%   |
| da_DK   | 1         | 0.37%   |
| cs_CZ   | 1         | 0.37%   |
| Unknown | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 139       | 51.87%  |
| BIOS | 129       | 48.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 251       | 92.96%  |
| Overlay | 10        | 3.7%    |
| Btrfs   | 3         | 1.11%   |
| Zfs     | 2         | 0.74%   |
| Xfs     | 2         | 0.74%   |
| Ext3    | 2         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 105       | 38.89%  |
| Unknown | 91        | 33.7%   |
| MBR     | 74        | 27.41%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 240       | 88.24%  |
| Yes       | 32        | 11.76%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 186       | 69.14%  |
| Yes       | 83        | 30.86%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 59        | 22.01%  |
| Hewlett-Packard        | 54        | 20.15%  |
| Dell                   | 54        | 20.15%  |
| ASUSTek Computer       | 25        | 9.33%   |
| Acer                   | 18        | 6.72%   |
| Toshiba                | 9         | 3.36%   |
| Samsung Electronics    | 7         | 2.61%   |
| MSI                    | 7         | 2.61%   |
| Sony                   | 3         | 1.12%   |
| Medion                 | 3         | 1.12%   |
| Positivo               | 2         | 0.75%   |
| Packard Bell           | 2         | 0.75%   |
| Notebook               | 2         | 0.75%   |
| GPD                    | 2         | 0.75%   |
| Fujitsu                | 2         | 0.75%   |
| Avell High Performance | 2         | 0.75%   |
| Apple                  | 2         | 0.75%   |
| Unknown                | 2         | 0.75%   |
| Wortmann AG            | 1         | 0.37%   |
| TUXEDO                 | 1         | 0.37%   |
| Teclast                | 1         | 0.37%   |
| System76               | 1         | 0.37%   |
| Star Labs              | 1         | 0.37%   |
| Polaroid               | 1         | 0.37%   |
| Pine Microsystems      | 1         | 0.37%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.37%   |
| Intel                  | 1         | 0.37%   |
| Cube                   | 1         | 0.37%   |
| Clevo                  | 1         | 0.37%   |
| Chuwi                  | 1         | 0.37%   |
| AMI                    | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Latitude E6420                        | 5         | 1.87%   |
| HP Pavilion dv7                            | 4         | 1.49%   |
| HP Notebook                                | 3         | 1.12%   |
| Dell Precision M4800                       | 3         | 1.12%   |
| Dell Latitude E6410                        | 3         | 1.12%   |
| Unknown                                    | 3         | 1.12%   |
| Toshiba Satellite C660                     | 2         | 0.75%   |
| HP Pavilion g6                             | 2         | 0.75%   |
| HP EliteBook 8470p                         | 2         | 0.75%   |
| Dell Vostro 3350                           | 2         | 0.75%   |
| Dell Latitude E6430                        | 2         | 0.75%   |
| Dell Inspiron 3421                         | 2         | 0.75%   |
| ASUS ZenBook UX431DA_UM431DA               | 2         | 0.75%   |
| ASUS X553MA                                | 2         | 0.75%   |
| ASUS X541SA                                | 2         | 0.75%   |
| Wortmann AG TERRA_MOBILE_1749              | 1         | 0.37%   |
| TUXEDO InfinityBook Pro 14 Gen6            | 1         | 0.37%   |
| Toshiba Satellite Pro L500                 | 1         | 0.37%   |
| Toshiba Satellite Pro C660                 | 1         | 0.37%   |
| Toshiba Satellite P755                     | 1         | 0.37%   |
| Toshiba Satellite M500                     | 1         | 0.37%   |
| Toshiba Satellite L350D                    | 1         | 0.37%   |
| Toshiba Satellite C675                     | 1         | 0.37%   |
| Toshiba Satellite C665                     | 1         | 0.37%   |
| Teclast F15S                               | 1         | 0.37%   |
| System76 Serval WS                         | 1         | 0.37%   |
| Star Labs LabTop                           | 1         | 0.37%   |
| Sony VPCS12X9E                             | 1         | 0.37%   |
| Sony VPCF1290X                             | 1         | 0.37%   |
| Sony VPCEH1S1E                             | 1         | 0.37%   |
| Samsung SR58P                              | 1         | 0.37%   |
| Samsung R530/R730/R540                     | 1         | 0.37%   |
| Samsung R505                               | 1         | 0.37%   |
| Samsung 550P5C/550P7C                      | 1         | 0.37%   |
| Samsung 530U4E/540U4E                      | 1         | 0.37%   |
| Samsung 350V5C/351V5C/3540VC/3440VC        | 1         | 0.37%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.37%   |
| Positivo N8X0EK1                           | 1         | 0.37%   |
| Positivo Mobile                            | 1         | 0.37%   |
| Polaroid MP1464PR001                       | 1         | 0.37%   |
| Pine Microsystems Pine64 Pinebook Pro      | 1         | 0.37%   |
| Packard Bell EasyNote SL65                 | 1         | 0.37%   |
| Packard Bell EasyNote ME69BMP              | 1         | 0.37%   |
| ONE-NETBOOK TECHNOLOGY A1                  | 1         | 0.37%   |
| Notebook W54_W94_W955TU,-T,-C              | 1         | 0.37%   |
| Notebook W310CZ/CZ-T                       | 1         | 0.37%   |
| MSI GV62 8RD                               | 1         | 0.37%   |
| MSI GP72MVR 7RFX                           | 1         | 0.37%   |
| MSI GP72 6QF                               | 1         | 0.37%   |
| MSI GF63 Thin 9SCSR                        | 1         | 0.37%   |
| MSI GE72 7RE                               | 1         | 0.37%   |
| MSI GE60 2OC\2OD\2OE                       | 1         | 0.37%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD              | 1         | 0.37%   |
| Medion X682X                               | 1         | 0.37%   |
| Medion E15302                              | 1         | 0.37%   |
| Medion Akoya E6415                         | 1         | 0.37%   |
| Lenovo Z51-70 80K6                         | 1         | 0.37%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.37%   |
| Lenovo V570 HuronRiver Platform            | 1         | 0.37%   |
| Lenovo ThinkPad Yoga 260 20FES25400        | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 37        | 13.81%  |
| Dell Latitude             | 20        | 7.46%   |
| HP Pavilion               | 18        | 6.72%   |
| Acer Aspire               | 15        | 5.6%    |
| Toshiba Satellite         | 9         | 3.36%   |
| Lenovo IdeaPad            | 9         | 3.36%   |
| HP EliteBook              | 9         | 3.36%   |
| Dell Precision            | 9         | 3.36%   |
| Dell Inspiron             | 8         | 2.99%   |
| Dell XPS                  | 6         | 2.24%   |
| HP ProBook                | 5         | 1.87%   |
| HP 250                    | 5         | 1.87%   |
| Dell Vostro               | 5         | 1.87%   |
| HP ZBook                  | 4         | 1.49%   |
| ASUS VivoBook             | 4         | 1.49%   |
| HP Notebook               | 3         | 1.12%   |
| HP Laptop                 | 3         | 1.12%   |
| Unknown                   | 3         | 1.12%   |
| Packard Bell EasyNote     | 2         | 0.75%   |
| Lenovo ThinkBook          | 2         | 0.75%   |
| Lenovo Legion             | 2         | 0.75%   |
| Lenovo Flex               | 2         | 0.75%   |
| HP Compaq                 | 2         | 0.75%   |
| Fujitsu LIFEBOOK          | 2         | 0.75%   |
| Dell System               | 2         | 0.75%   |
| Dell Studio               | 2         | 0.75%   |
| ASUS ZenBook              | 2         | 0.75%   |
| ASUS X553MA               | 2         | 0.75%   |
| ASUS X541SA               | 2         | 0.75%   |
| Wortmann AG TERRA         | 1         | 0.37%   |
| TUXEDO InfinityBook       | 1         | 0.37%   |
| Teclast F15S              | 1         | 0.37%   |
| System76 Serval           | 1         | 0.37%   |
| Star Labs LabTop          | 1         | 0.37%   |
| Sony VPCS12X9E            | 1         | 0.37%   |
| Sony VPCF1290X            | 1         | 0.37%   |
| Sony VPCEH1S1E            | 1         | 0.37%   |
| Samsung SR58P             | 1         | 0.37%   |
| Samsung R530              | 1         | 0.37%   |
| Samsung R505              | 1         | 0.37%   |
| Samsung 550P5C            | 1         | 0.37%   |
| Samsung 530U4E            | 1         | 0.37%   |
| Samsung 350V5C            | 1         | 0.37%   |
| Samsung 300E4A            | 1         | 0.37%   |
| Positivo N8X0EK1          | 1         | 0.37%   |
| Positivo Mobile           | 1         | 0.37%   |
| Polaroid MP1464PR001      | 1         | 0.37%   |
| Pine Microsystems Pine64  | 1         | 0.37%   |
| ONE-NETBOOK TECHNOLOGY A1 | 1         | 0.37%   |
| Notebook W54              | 1         | 0.37%   |
| Notebook W310CZ           | 1         | 0.37%   |
| MSI GV62                  | 1         | 0.37%   |
| MSI GP72MVR               | 1         | 0.37%   |
| MSI GP72                  | 1         | 0.37%   |
| MSI GF63                  | 1         | 0.37%   |
| MSI GE72                  | 1         | 0.37%   |
| MSI GE60                  | 1         | 0.37%   |
| MSI CR70                  | 1         | 0.37%   |
| Medion X682X              | 1         | 0.37%   |
| Medion E15302             | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 35        | 13.06%  |
| 2019    | 28        | 10.45%  |
| 2012    | 27        | 10.07%  |
| 2020    | 21        | 7.84%   |
| 2013    | 21        | 7.84%   |
| 2018    | 20        | 7.46%   |
| 2015    | 19        | 7.09%   |
| 2014    | 17        | 6.34%   |
| 2016    | 16        | 5.97%   |
| 2010    | 16        | 5.97%   |
| 2008    | 16        | 5.97%   |
| 2017    | 12        | 4.48%   |
| 2021    | 10        | 3.73%   |
| 2009    | 6         | 2.24%   |
| 2007    | 3         | 1.12%   |
| Unknown | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 268       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 238       | 88.48%  |
| Enabled  | 31        | 11.52%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 268       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 76        | 28.04%  |
| 4.01-8.0    | 72        | 26.57%  |
| 8.01-16.0   | 43        | 15.87%  |
| 16.01-24.0  | 39        | 14.39%  |
| 32.01-64.0  | 17        | 6.27%   |
| 64.01-256.0 | 7         | 2.58%   |
| 1.01-2.0    | 7         | 2.58%   |
| 2.01-3.0    | 6         | 2.21%   |
| 24.01-32.0  | 4         | 1.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 110       | 38.6%   |
| 2.01-3.0   | 74        | 25.96%  |
| 3.01-4.0   | 37        | 12.98%  |
| 4.01-8.0   | 35        | 12.28%  |
| 0.51-1.0   | 22        | 7.72%   |
| 8.01-16.0  | 6         | 2.11%   |
| 24.01-32.0 | 1         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 198       | 72.79%  |
| 2      | 64        | 23.53%  |
| 3      | 8         | 2.94%   |
| 4      | 1         | 0.37%   |
| 0      | 1         | 0.37%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 53.53%  |
| Yes       | 125       | 46.47%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 234       | 87.31%  |
| No        | 34        | 12.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 263       | 97.77%  |
| No        | 6         | 2.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 203       | 74.91%  |
| No        | 68        | 25.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Brazil      | 36        | 13.38%  |
| USA         | 32        | 11.9%   |
| France      | 29        | 10.78%  |
| Germany     | 25        | 9.29%   |
| UK          | 15        | 5.58%   |
| Spain       | 14        | 5.2%    |
| Italy       | 13        | 4.83%   |
| Russia      | 12        | 4.46%   |
| Ukraine     | 9         | 3.35%   |
| Netherlands | 7         | 2.6%    |
| Switzerland | 6         | 2.23%   |
| Argentina   | 5         | 1.86%   |
| Poland      | 4         | 1.49%   |
| Canada      | 4         | 1.49%   |
| Turkey      | 3         | 1.12%   |
| Norway      | 3         | 1.12%   |
| Indonesia   | 3         | 1.12%   |
| Greece      | 3         | 1.12%   |
| Finland     | 3         | 1.12%   |
| Vietnam     | 2         | 0.74%   |
| Thailand    | 2         | 0.74%   |
| Sweden      | 2         | 0.74%   |
| Portugal    | 2         | 0.74%   |
| Philippines | 2         | 0.74%   |
| Mexico      | 2         | 0.74%   |
| Ireland     | 2         | 0.74%   |
| India       | 2         | 0.74%   |
| Denmark     | 2         | 0.74%   |
| Chile       | 2         | 0.74%   |
| Venezuela   | 1         | 0.37%   |
| Uruguay     | 1         | 0.37%   |
| Taiwan      | 1         | 0.37%   |
| Slovakia    | 1         | 0.37%   |
| Réunion    | 1         | 0.37%   |
| Puerto Rico | 1         | 0.37%   |
| Peru        | 1         | 0.37%   |
| New Zealand | 1         | 0.37%   |
| Morocco     | 1         | 0.37%   |
| Malaysia    | 1         | 0.37%   |
| Luxembourg  | 1         | 0.37%   |
| Kenya       | 1         | 0.37%   |
| Ivory Coast | 1         | 0.37%   |
| Hungary     | 1         | 0.37%   |
| Estonia     | 1         | 0.37%   |
| Ecuador     | 1         | 0.37%   |
| Czechia     | 1         | 0.37%   |
| Croatia     | 1         | 0.37%   |
| China       | 1         | 0.37%   |
| Belgium     | 1         | 0.37%   |
| Belarus     | 1         | 0.37%   |
| Austria     | 1         | 0.37%   |
| Australia   | 1         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 19        | 6.91%   |
| Paris                 | 6         | 2.18%   |
| Moscow                | 6         | 2.18%   |
| Kyiv                  | 5         | 1.82%   |
| Rome                  | 3         | 1.09%   |
| Rio de Janeiro        | 3         | 1.09%   |
| Berlin                | 3         | 1.09%   |
| Barcelona             | 3         | 1.09%   |
| Seville               | 2         | 0.73%   |
| Samara                | 2         | 0.73%   |
| Saint-Cloud           | 2         | 0.73%   |
| Oslo                  | 2         | 0.73%   |
| Marseille             | 2         | 0.73%   |
| Manchester            | 2         | 0.73%   |
| Huissen               | 2         | 0.73%   |
| Ho Chi Minh City      | 2         | 0.73%   |
| Gigean                | 2         | 0.73%   |
| Genoa                 | 2         | 0.73%   |
| Frankfurt am Main     | 2         | 0.73%   |
| Evansville            | 2         | 0.73%   |
| Essen                 | 2         | 0.73%   |
| Durham                | 2         | 0.73%   |
| Draper                | 2         | 0.73%   |
| Clichy-sous-Bois      | 2         | 0.73%   |
| Brooklyn              | 2         | 0.73%   |
| Bristol               | 2         | 0.73%   |
| Athens                | 2         | 0.73%   |
| Ankara                | 2         | 0.73%   |
| Amsterdam             | 2         | 0.73%   |
| Akron                 | 2         | 0.73%   |
| Zagreb                | 1         | 0.36%   |
| Xining                | 1         | 0.36%   |
| Willimantic           | 1         | 0.36%   |
| Washington            | 1         | 0.36%   |
| Wake Forest           | 1         | 0.36%   |
| Vlkova                | 1         | 0.36%   |
| Viña del Mar         | 1         | 0.36%   |
| Villa Ocampo          | 1         | 0.36%   |
| Vila Velha            | 1         | 0.36%   |
| Vigo                  | 1         | 0.36%   |
| Vigneux-sur-Seine     | 1         | 0.36%   |
| Vienna                | 1         | 0.36%   |
| Valencia              | 1         | 0.36%   |
| Trondheim             | 1         | 0.36%   |
| Toulouse              | 1         | 0.36%   |
| Toronto               | 1         | 0.36%   |
| Thessaloniki          | 1         | 0.36%   |
| Thaire                | 1         | 0.36%   |
| Tampere               | 1         | 0.36%   |
| Tainan City           | 1         | 0.36%   |
| Stutzengrun           | 1         | 0.36%   |
| Springe               | 1         | 0.36%   |
| Spring Arbor          | 1         | 0.36%   |
| Soto del Real         | 1         | 0.36%   |
| Solothurn             | 1         | 0.36%   |
| Sneek                 | 1         | 0.36%   |
| Sevastopol            | 1         | 0.36%   |
| Sao José dos Pinhais | 1         | 0.36%   |
| Sao José dos Campos  | 1         | 0.36%   |
| Sanur                 | 1         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 48        | 53     | 14.41%  |
| Samsung Electronics   | 46        | 53     | 13.81%  |
| WDC                   | 44        | 51     | 13.21%  |
| Toshiba               | 33        | 38     | 9.91%   |
| Kingston              | 26        | 31     | 7.81%   |
| Unknown               | 18        | 20     | 5.41%   |
| SanDisk               | 18        | 22     | 5.41%   |
| Hitachi               | 14        | 16     | 4.2%    |
| SK Hynix              | 11        | 14     | 3.3%    |
| Intel                 | 10        | 12     | 3%      |
| Crucial               | 10        | 15     | 3%      |
| A-DATA Technology     | 6         | 6      | 1.8%    |
| KIOXIA                | 5         | 5      | 1.5%    |
| HGST                  | 5         | 5      | 1.5%    |
| China                 | 5         | 6      | 1.5%    |
| Micron Technology     | 4         | 5      | 1.2%    |
| PNY                   | 3         | 3      | 0.9%    |
| Phison                | 3         | 3      | 0.9%    |
| Fujitsu               | 3         | 3      | 0.9%    |
| Transcend             | 2         | 3      | 0.6%    |
| Silicon Motion        | 2         | 2      | 0.6%    |
| Patriot               | 2         | 2      | 0.6%    |
| Intenso               | 2         | 2      | 0.6%    |
| Apacer                | 2         | 3      | 0.6%    |
| XPG                   | 1         | 1      | 0.3%    |
| Vaseky                | 1         | 1      | 0.3%    |
| SMART                 | 1         | 1      | 0.3%    |
| Realtek Semiconductor | 1         | 1      | 0.3%    |
| PLEXTOR               | 1         | 1      | 0.3%    |
| OCZ                   | 1         | 1      | 0.3%    |
| Netac                 | 1         | 1      | 0.3%    |
| LITEONIT              | 1         | 2      | 0.3%    |
| KingSpec              | 1         | 1      | 0.3%    |
| FORESEE               | 1         | 1      | 0.3%    |
| faspeed               | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD         | 8         | 2.34%   |
| Kingston SA400S37120G 120GB SSD         | 7         | 2.05%   |
| Toshiba MQ01ABF050 500GB                | 6         | 1.75%   |
| Seagate ST320LT007-9ZV142 320GB         | 6         | 1.75%   |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 1.46%   |
| WDC WD10JPVX-22JC3T0 1TB                | 4         | 1.17%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.17%   |
| Hitachi HTS545050B9A300 500GB           | 4         | 1.17%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.88%   |
| Unknown MMC Card  16GB                  | 3         | 0.88%   |
| Seagate ST500LT012-9WS142 500GB         | 3         | 0.88%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 0.88%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.88%   |
| Seagate ST1000LM014-1EJ164 1TB          | 3         | 0.88%   |
| Samsung SSD 860 EVO 500GB               | 3         | 0.88%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.88%   |
| Intel SSDPEKNW512G8 512GB               | 3         | 0.88%   |
| Hitachi HTS547564A9E384 640GB           | 3         | 0.88%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 2         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 2         | 0.58%   |
| WDC WD5000BPKT-75PK4T0 500GB            | 2         | 0.58%   |
| WDC WD10SPZX-08Z10 1TB                  | 2         | 0.58%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB    | 2         | 0.58%   |
| Unknown DA4064  64GB                    | 2         | 0.58%   |
| Transcend TS512GMTS430S 512GB SSD       | 2         | 0.58%   |
| Toshiba MQ01ACF032 320GB                | 2         | 0.58%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.58%   |
| Toshiba MQ01ABD050 500GB                | 2         | 0.58%   |
| Toshiba MK7559GSXP 752GB                | 2         | 0.58%   |
| SK Hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.58%   |
| Seagate ST9500420AS 500GB               | 2         | 0.58%   |
| Seagate ST9500325AS 500GB               | 2         | 0.58%   |
| Seagate ST9250410AS 250GB               | 2         | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 0.58%   |
| Seagate ST500LM000-SSHD-8GB             | 2         | 0.58%   |
| Seagate ST2000LM015-2E8174 2TB          | 2         | 0.58%   |
| SanDisk SD6SB2M-512G-1006 512GB SSD     | 2         | 0.58%   |
| Sandisk NVMe SSD Drive 512GB            | 2         | 0.58%   |
| SanDisk DF4064  64GB                    | 2         | 0.58%   |
| Samsung SSD PM830 mSATA 128GB           | 2         | 0.58%   |
| Samsung SSD 860 QVO 1TB                 | 2         | 0.58%   |
| Samsung SSD 860 PRO 512GB               | 2         | 0.58%   |
| Samsung SSD 850 EVO 500GB               | 2         | 0.58%   |
| Samsung MZ7PD256HAFV-000H7 256GB SSD    | 2         | 0.58%   |
| PNY CS900 240GB SSD                     | 2         | 0.58%   |
| Kingston SUV500MS120G 120GB SSD         | 2         | 0.58%   |
| HGST HTS721010A9E630 1TB                | 2         | 0.58%   |
| Fujitsu MHZ2320BH G2 320GB              | 2         | 0.58%   |
| Crucial CT250BX100SSD1 250GB            | 2         | 0.58%   |
| China SSD 120GB                         | 2         | 0.58%   |
| Apacer AS350 512GB SSD                  | 2         | 0.58%   |
| XPG NVMe SSD Drive 2TB                  | 1         | 0.29%   |
| WDC WDS250G2X0C-00L350 250GB            | 1         | 0.29%   |
| WDC WDS200T3X0C-00SJG0 2TB              | 1         | 0.29%   |
| WDC WDS120G1G0A-00SS50 120GB SSD        | 1         | 0.29%   |
| WDC WDS100T2G0A-00JH30 1TB SSD          | 1         | 0.29%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.29%   |
| WDC WD7500BPVX-60JC3T0 752GB            | 1         | 0.29%   |
| WDC WD7500BPVX-22JC3T0 752GB            | 1         | 0.29%   |
| WDC WD7500BPVT-75HXZT1 752GB            | 1         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 52     | 37.8%   |
| WDC                 | 29        | 34     | 22.83%  |
| Toshiba             | 26        | 31     | 20.47%  |
| Hitachi             | 14        | 16     | 11.02%  |
| HGST                | 5         | 5      | 3.94%   |
| Fujitsu             | 3         | 3      | 2.36%   |
| Samsung Electronics | 2         | 2      | 1.57%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 37     | 26.45%  |
| Kingston            | 24        | 29     | 19.83%  |
| SanDisk             | 12        | 15     | 9.92%   |
| Crucial             | 8         | 13     | 6.61%   |
| WDC                 | 6         | 6      | 4.96%   |
| China               | 5         | 6      | 4.13%   |
| A-DATA Technology   | 5         | 5      | 4.13%   |
| Intel               | 4         | 5      | 3.31%   |
| Toshiba             | 3         | 3      | 2.48%   |
| PNY                 | 3         | 3      | 2.48%   |
| Transcend           | 2         | 3      | 1.65%   |
| Micron Technology   | 2         | 3      | 1.65%   |
| Intenso             | 2         | 2      | 1.65%   |
| Apacer              | 2         | 3      | 1.65%   |
| Vaseky              | 1         | 1      | 0.83%   |
| SMART               | 1         | 1      | 0.83%   |
| SK Hynix            | 1         | 3      | 0.83%   |
| Seagate             | 1         | 1      | 0.83%   |
| PLEXTOR             | 1         | 1      | 0.83%   |
| Patriot             | 1         | 1      | 0.83%   |
| OCZ                 | 1         | 1      | 0.83%   |
| Netac               | 1         | 1      | 0.83%   |
| LITEONIT            | 1         | 2      | 0.83%   |
| KingSpec            | 1         | 1      | 0.83%   |
| FORESEE             | 1         | 1      | 0.83%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 122       | 143    | 38.98%  |
| SSD     | 110       | 147    | 35.14%  |
| NVMe    | 64        | 75     | 20.45%  |
| MMC     | 16        | 19     | 5.11%   |
| Unknown | 1         | 1      | 0.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 212       | 284    | 70.9%   |
| NVMe | 64        | 75     | 21.4%   |
| MMC  | 16        | 19     | 5.35%   |
| SAS  | 7         | 7      | 2.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 160       | 201    | 67.23%  |
| 0.51-1.0   | 67        | 75     | 28.15%  |
| 1.01-2.0   | 8         | 11     | 3.36%   |
| 3.01-4.0   | 2         | 2      | 0.84%   |
| 4.01-10.0  | 1         | 1      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 88        | 32%     |
| 101-250        | 71        | 25.82%  |
| 501-1000       | 45        | 16.36%  |
| 1001-2000      | 17        | 6.18%   |
| 1-20           | 17        | 6.18%   |
| 51-100         | 15        | 5.45%   |
| 21-50          | 11        | 4%      |
| 2001-3000      | 6         | 2.18%   |
| More than 3000 | 5         | 1.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 97        | 34.15%  |
| 21-50          | 47        | 16.55%  |
| 101-250        | 47        | 16.55%  |
| 51-100         | 46        | 16.2%   |
| 251-500        | 28        | 9.86%   |
| 501-1000       | 14        | 4.93%   |
| 1001-2000      | 3         | 1.06%   |
| More than 3000 | 1         | 0.35%   |
| 2001-3000      | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT007-9ZV142 320GB   | 4         | 4      | 12.12%  |
| Toshiba MK7559GSXP 752GB          | 2         | 2      | 6.06%   |
| WDC WD7500BPVT-75HXZT1 752GB      | 1         | 1      | 3.03%   |
| WDC WD7500BPKT-75PK4T0 752GB      | 1         | 1      | 3.03%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 3.03%   |
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 2      | 3.03%   |
| WDC WD3200BEVT-60ZCT1 320GB       | 1         | 1      | 3.03%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 3.03%   |
| Vaseky V820/1TB SSD               | 1         | 1      | 3.03%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 3.03%   |
| Toshiba MK5065GSX 500GB           | 1         | 1      | 3.03%   |
| Toshiba MK2565GSXN 250GB          | 1         | 1      | 3.03%   |
| Toshiba MK2555GSX 250GB           | 1         | 1      | 3.03%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 3.03%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 3.03%   |
| Seagate ST9250410AS 250GB         | 1         | 1      | 3.03%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 3.03%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 3.03%   |
| Seagate ST320LT012-9WS14C 320GB   | 1         | 1      | 3.03%   |
| SanDisk SD7SN3Q256G1002 256GB SSD | 1         | 1      | 3.03%   |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 3.03%   |
| OCZ VERTEX450 128GB SSD           | 1         | 1      | 3.03%   |
| Intel SSDSC2KF256H6L 256GB        | 1         | 1      | 3.03%   |
| Hitachi HTS722016K9A300 160GB     | 1         | 1      | 3.03%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 3.03%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 3.03%   |
| Fujitsu MHZ2320BH G1 320GB        | 1         | 1      | 3.03%   |
| China SSD 120GB                   | 1         | 1      | 3.03%   |
| A-DATA Technology SP900 64GB SSD  | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 30.3%   |
| WDC                 | 6         | 7      | 18.18%  |
| Toshiba             | 6         | 6      | 18.18%  |
| Hitachi             | 3         | 3      | 9.09%   |
| Vaseky              | 1         | 1      | 3.03%   |
| SanDisk             | 1         | 1      | 3.03%   |
| Samsung Electronics | 1         | 1      | 3.03%   |
| OCZ                 | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| Fujitsu             | 1         | 1      | 3.03%   |
| China               | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 37.04%  |
| WDC                 | 6         | 7      | 22.22%  |
| Toshiba             | 6         | 6      | 22.22%  |
| Hitachi             | 3         | 3      | 11.11%  |
| Samsung Electronics | 1         | 1      | 3.7%    |
| Fujitsu             | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 28     | 81.82%  |
| SSD  | 6         | 6      | 18.18%  |

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
| Works    | 150       | 196    | 52.45%  |
| Detected | 103       | 155    | 36.01%  |
| Malfunc  | 33        | 34     | 11.54%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 205       | 68.56%  |
| AMD                              | 28        | 9.36%   |
| Sandisk                          | 14        | 4.68%   |
| Samsung Electronics              | 13        | 4.35%   |
| SK Hynix                         | 10        | 3.34%   |
| Toshiba America Info Systems     | 6         | 2.01%   |
| KIOXIA                           | 4         | 1.34%   |
| Silicon Motion                   | 3         | 1%      |
| Phison Electronics               | 3         | 1%      |
| Silicon Integrated Systems [SiS] | 2         | 0.67%   |
| Micron/Crucial Technology        | 2         | 0.67%   |
| Micron Technology                | 2         | 0.67%   |
| Kingston Technology Company      | 2         | 0.67%   |
| ADATA Technology                 | 2         | 0.67%   |
| Solid State Storage Technology   | 1         | 0.33%   |
| Realtek Semiconductor            | 1         | 0.33%   |
| Nvidia                           | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 9.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 29        | 8.95%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 6.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 18        | 5.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 4.94%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 15        | 4.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 3.7%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 3.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 2.47%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 2.47%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 2.16%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 2.16%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.85%   |
| Intel SSD 660P Series                                                            | 5         | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.54%   |
| SK Hynix BC511                                                                   | 4         | 1.23%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.23%   |
| KIOXIA Non-Volatile memory controller                                            | 4         | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.23%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.93%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 0.93%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.93%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.93%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.93%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.93%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.93%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.93%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 3         | 0.93%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 3         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.93%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.62%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.62%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.62%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.62%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.62%   |
| Phison E12 NVMe Controller                                                       | 2         | 0.62%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 0.62%   |
| Micron Non-Volatile memory controller                                            | 2         | 0.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.62%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.62%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.62%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.62%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.62%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.31%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.31%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.31%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.31%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.31%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.31%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 1         | 0.31%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.31%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.31%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 206       | 67.1%   |
| NVMe | 63        | 20.52%  |
| RAID | 21        | 6.84%   |
| IDE  | 17        | 5.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 233       | 86.94%  |
| AMD    | 34        | 12.69%  |
| ARM    | 1         | 0.37%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.87%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 5         | 1.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.49%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 1.49%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.49%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.49%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 3         | 1.12%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.12%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 1.12%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 1.12%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.12%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.12%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.12%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.12%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 3         | 1.12%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.12%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.12%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.75%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.75%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.75%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 2         | 0.75%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 2         | 0.75%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.75%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.75%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 2         | 0.75%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.75%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.75%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.75%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.75%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 0.75%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.75%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.75%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.75%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.75%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 2         | 0.75%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.75%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 0.75%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.75%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 0.75%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.75%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.75%   |
| Intel 11th Gen Core i7-11850H @ 2.50GHz       | 2         | 0.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.75%   |
| AMD Turion X2 Dual-Core Mobile RM-72          | 2         | 0.75%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.75%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 75        | 27.99%  |
| Intel Core i7                  | 71        | 26.49%  |
| Intel Core i3                  | 23        | 8.58%   |
| Intel Core 2 Duo               | 13        | 4.85%   |
| Intel Celeron                  | 12        | 4.48%   |
| Other                          | 11        | 4.1%    |
| Intel Pentium                  | 11        | 4.1%    |
| AMD Ryzen 7                    | 6         | 2.24%   |
| AMD Ryzen 5                    | 5         | 1.87%   |
| Intel Atom                     | 4         | 1.49%   |
| AMD A6                         | 4         | 1.49%   |
| Intel Pentium Dual-Core        | 3         | 1.12%   |
| Intel Core m3                  | 3         | 1.12%   |
| AMD A4                         | 3         | 1.12%   |
| Intel Core M                   | 2         | 0.75%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.75%   |
| AMD Ryzen 9                    | 2         | 0.75%   |
| AMD Ryzen 3                    | 2         | 0.75%   |
| AMD A8                         | 2         | 0.75%   |
| Intel Xeon                     | 1         | 0.37%   |
| Intel Pentium Silver           | 1         | 0.37%   |
| Intel Pentium Dual             | 1         | 0.37%   |
| Intel Genuine                  | 1         | 0.37%   |
| Intel Core i9                  | 1         | 0.37%   |
| Intel Core 2 Extreme           | 1         | 0.37%   |
| Intel Celeron Dual-Core        | 1         | 0.37%   |
| AMD Ryzen 7 PRO                | 1         | 0.37%   |
| AMD Ryzen 5 PRO                | 1         | 0.37%   |
| AMD Phenom II                  | 1         | 0.37%   |
| AMD E2                         | 1         | 0.37%   |
| AMD E                          | 1         | 0.37%   |
| AMD Athlon X2                  | 1         | 0.37%   |
| AMD Athlon                     | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 151       | 56.13%  |
| 4      | 95        | 35.32%  |
| 8      | 10        | 3.72%   |
| 6      | 10        | 3.72%   |
| 1      | 2         | 0.74%   |
| 3      | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 267       | 99.63%  |
| 2      | 1         | 0.37%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 198       | 73.88%  |
| 1      | 70        | 26.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 268       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 11.81%  |
| 0x206a7    | 31        | 11.44%  |
| 0x306a9    | 29        | 10.7%   |
| 0x306d4    | 13        | 4.8%    |
| 0x1067a    | 11        | 4.06%   |
| 0x806ec    | 9         | 3.32%   |
| 0x806e9    | 9         | 3.32%   |
| 0x40651    | 9         | 3.32%   |
| 0x306c3    | 9         | 3.32%   |
| 0x806ea    | 7         | 2.58%   |
| 0x706e5    | 6         | 2.21%   |
| 0x406e3    | 6         | 2.21%   |
| 0x20655    | 6         | 2.21%   |
| 0x20652    | 6         | 2.21%   |
| 0x08108102 | 6         | 2.21%   |
| 0x906ea    | 5         | 1.85%   |
| 0x806c1    | 5         | 1.85%   |
| 0x6fd      | 5         | 1.85%   |
| 0x406c4    | 5         | 1.85%   |
| 0x906e9    | 4         | 1.48%   |
| 0x706a1    | 4         | 1.48%   |
| 0x506e3    | 4         | 1.48%   |
| 0x30678    | 4         | 1.48%   |
| 0x06006705 | 4         | 1.48%   |
| 0x806d1    | 3         | 1.11%   |
| 0x08600106 | 3         | 1.11%   |
| 0x02000032 | 3         | 1.11%   |
| 0xa0652    | 2         | 0.74%   |
| 0x906ed    | 2         | 0.74%   |
| 0x6fa      | 2         | 0.74%   |
| 0x506c9    | 2         | 0.74%   |
| 0x406c3    | 2         | 0.74%   |
| 0x30673    | 2         | 0.74%   |
| 0x106e5    | 2         | 0.74%   |
| 0x10676    | 2         | 0.74%   |
| 0x08108109 | 2         | 0.74%   |
| 0x08101016 | 2         | 0.74%   |
| 0x07030105 | 2         | 0.74%   |
| 0xa0660    | 1         | 0.37%   |
| 0x806eb    | 1         | 0.37%   |
| 0x106ca    | 1         | 0.37%   |
| 0x0a50000c | 1         | 0.37%   |
| 0x0a50000b | 1         | 0.37%   |
| 0x08701013 | 1         | 0.37%   |
| 0x08101007 | 1         | 0.37%   |
| 0x07030104 | 1         | 0.37%   |
| 0x06006704 | 1         | 0.37%   |
| 0x05000119 | 1         | 0.37%   |
| 0x05000029 | 1         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 44        | 16.42%  |
| SandyBridge     | 35        | 13.06%  |
| IvyBridge       | 31        | 11.57%  |
| Haswell         | 22        | 8.21%   |
| Broadwell       | 16        | 5.97%   |
| Skylake         | 13        | 4.85%   |
| Silvermont      | 13        | 4.85%   |
| Penryn          | 13        | 4.85%   |
| Westmere        | 12        | 4.48%   |
| IceLake         | 10        | 3.73%   |
| Zen+            | 8         | 2.99%   |
| Core            | 7         | 2.61%   |
| TigerLake       | 5         | 1.87%   |
| Excavator       | 5         | 1.87%   |
| Zen 2           | 4         | 1.49%   |
| Puma            | 4         | 1.49%   |
| Goldmont plus   | 4         | 1.49%   |
| Zen 3           | 3         | 1.12%   |
| Zen             | 3         | 1.12%   |
| K8 & K10 hybrid | 3         | 1.12%   |
| CometLake       | 3         | 1.12%   |
| Nehalem         | 2         | 0.75%   |
| Goldmont        | 2         | 0.75%   |
| Bobcat          | 2         | 0.75%   |
| Piledriver      | 1         | 0.37%   |
| K10             | 1         | 0.37%   |
| Bonnell         | 1         | 0.37%   |
| Unknown         | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 212       | 63.1%   |
| Nvidia                           | 69        | 20.54%  |
| AMD                              | 54        | 16.07%  |
| Silicon Integrated Systems [SiS] | 1         | 0.3%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 30        | 8.72%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 8.43%   |
| Intel HD Graphics 5500                                                                   | 14        | 4.07%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 2.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.91%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.91%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 2.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.62%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.33%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.74%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.45%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.45%   |
| Intel HD Graphics 530                                                                    | 5         | 1.45%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.16%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.16%   |
| Intel HD Graphics 630                                                                    | 4         | 1.16%   |
| Intel HD Graphics 620                                                                    | 4         | 1.16%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.87%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.87%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.87%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.87%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 0.87%   |
| AMD Renoir                                                                               | 3         | 0.87%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.87%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.87%   |
| AMD Cezanne                                                                              | 3         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.58%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 2         | 0.58%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.58%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.58%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 2         | 0.58%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.58%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.58%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 0.58%   |
| Intel UHD Graphics 615                                                                   | 2         | 0.58%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.58%   |
| Intel HD Graphics 5300                                                                   | 2         | 0.58%   |
| Intel HD Graphics 500                                                                    | 2         | 0.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 0.58%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.58%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 2         | 0.58%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 2         | 0.58%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.29%   |
| Nvidia TU117M                                                                            | 1         | 0.29%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.29%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.29%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.29%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.29%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.29%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.29%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 146       | 54.48%  |
| Intel + Nvidia | 52        | 19.4%   |
| 1 x AMD        | 33        | 12.31%  |
| 1 x Nvidia     | 15        | 5.6%    |
| Intel + AMD    | 14        | 5.22%   |
| 2 x AMD        | 4         | 1.49%   |
| AMD + Nvidia   | 2         | 0.75%   |
| Other          | 1         | 0.37%   |
| 1 x SiS        | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 221       | 81.85%  |
| Proprietary | 39        | 14.44%  |
| Unknown     | 10        | 3.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 184       | 68.4%   |
| 1.01-2.0   | 24        | 8.92%   |
| 0.01-0.5   | 23        | 8.55%   |
| 0.51-1.0   | 18        | 6.69%   |
| 3.01-4.0   | 13        | 4.83%   |
| 5.01-6.0   | 3         | 1.12%   |
| 2.01-3.0   | 3         | 1.12%   |
| 7.01-8.0   | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 61        | 20.4%   |
| LG Display              | 48        | 16.05%  |
| Samsung Electronics     | 44        | 14.72%  |
| Chimei Innolux          | 40        | 13.38%  |
| BOE                     | 25        | 8.36%   |
| Dell                    | 12        | 4.01%   |
| Chi Mei Optoelectronics | 11        | 3.68%   |
| PANDA                   | 7         | 2.34%   |
| Sharp                   | 5         | 1.67%   |
| LG Philips              | 4         | 1.34%   |
| Lenovo                  | 4         | 1.34%   |
| Goldstar                | 4         | 1.34%   |
| Philips                 | 3         | 1%      |
| InnoLux Display         | 3         | 1%      |
| Hewlett-Packard         | 3         | 1%      |
| Apple                   | 3         | 1%      |
| Sony                    | 2         | 0.67%   |
| CSO                     | 2         | 0.67%   |
| AOC                     | 2         | 0.67%   |
| Ancor Communications    | 2         | 0.67%   |
| Acer                    | 2         | 0.67%   |
| ___                     | 1         | 0.33%   |
| Vizio                   | 1         | 0.33%   |
| Unknown                 | 1         | 0.33%   |
| Seiko/Epson             | 1         | 0.33%   |
| Optoma                  | 1         | 0.33%   |
| NEC Computers           | 1         | 0.33%   |
| MS_ Nvidia              | 1         | 0.33%   |
| Medion                  | 1         | 0.33%   |
| LGD                     | 1         | 0.33%   |
| InfoVision              | 1         | 0.33%   |
| Iiyama                  | 1         | 0.33%   |
| CPT                     | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 6         | 1.97%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 6         | 1.97%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch     | 3         | 0.98%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.98%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.98%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 3         | 0.98%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 344x194mm 15.5-inch     | 2         | 0.66%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.66%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.66%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.66%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.66%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 2         | 0.66%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch          | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.66%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO109E 1600x900 380x210mm 17.1-inch            | 2         | 0.66%   |
| ___ LCDTV16 ___9000 1360x768                                             | 1         | 0.33%   |
| Vizio D32f-E1 VIZ1027 1920x1080 698x392mm 31.5-inch                      | 1         | 0.33%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.33%   |
| Sony Nvidia Defaul t Flat Panel MS_0025 1920x1080 360x200mm 16.2-inch    | 1         | 0.33%   |
| Sony BW8 MS_9001 2560x1600                                               | 1         | 0.33%   |
| Sharp LCD SHP4200 1920x1080 410x230mm 18.5-inch                          | 1         | 0.33%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.33%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 1         | 0.33%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 1         | 0.33%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 0.33%   |
| Seiko/Epson LCD Monitor 1440x900                                         | 1         | 0.33%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 474x296mm 22.0-inch     | 1         | 0.33%   |
| Samsung Electronics SMBX2450L SAM0720 1920x1080 521x293mm 23.5-inch      | 1         | 0.33%   |
| Samsung Electronics SA300/SA350 SAM07D1 1920x1080 477x268mm 21.5-inch    | 1         | 0.33%   |
| Samsung Electronics S23B300 SAM08AE 1680x1050 510x290mm 23.1-inch        | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch    | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3441 1366x768 309x174mm 14.0-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch    | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3130 1024x600 223x125mm 10.1-inch     | 1         | 0.33%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch     | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 101       | 35.82%  |
| 1366x768 (WXGA)    | 100       | 35.46%  |
| 1600x900 (HD+)     | 29        | 10.28%  |
| 1280x800 (WXGA)    | 12        | 4.26%   |
| 2560x1440 (QHD)    | 6         | 2.13%   |
| 1680x1050 (WSXGA+) | 6         | 2.13%   |
| 1440x900 (WXGA+)   | 6         | 2.13%   |
| 1920x1200 (WUXGA)  | 5         | 1.77%   |
| 3840x2160 (4K)     | 4         | 1.42%   |
| 3200x1800 (QHD+)   | 2         | 0.71%   |
| 2560x1600          | 2         | 0.71%   |
| 1360x768           | 2         | 0.71%   |
| 3440x1440          | 1         | 0.35%   |
| 2880x1800          | 1         | 0.35%   |
| 2160x1440          | 1         | 0.35%   |
| 1680x945           | 1         | 0.35%   |
| 1600x1200          | 1         | 0.35%   |
| 1400x1050          | 1         | 0.35%   |
| 1024x600           | 1         | 0.35%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 123       | 41%     |
| 13      | 38        | 12.67%  |
| 14      | 35        | 11.67%  |
| 17      | 29        | 9.67%   |
| 12      | 11        | 3.67%   |
| 21      | 9         | 3%      |
| 23      | 8         | 2.67%   |
| 11      | 7         | 2.33%   |
| 24      | 6         | 2%      |
| Unknown | 6         | 2%      |
| 27      | 5         | 1.67%   |
| 18      | 5         | 1.67%   |
| 22      | 4         | 1.33%   |
| 10      | 3         | 1%      |
| 20      | 2         | 0.67%   |
| 72      | 1         | 0.33%   |
| 49      | 1         | 0.33%   |
| 40      | 1         | 0.33%   |
| 34      | 1         | 0.33%   |
| 31      | 1         | 0.33%   |
| 29      | 1         | 0.33%   |
| 19      | 1         | 0.33%   |
| 16      | 1         | 0.33%   |
| 8       | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 175       | 58.53%  |
| 201-300     | 37        | 12.37%  |
| 351-400     | 35        | 11.71%  |
| 401-500     | 21        | 7.02%   |
| 501-600     | 18        | 6.02%   |
| Unknown     | 6         | 2.01%   |
| 601-700     | 2         | 0.67%   |
| 801-900     | 1         | 0.33%   |
| 701-800     | 1         | 0.33%   |
| 1501-2000   | 1         | 0.33%   |
| 101-200     | 1         | 0.33%   |
| 1001-1500   | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 236       | 86.45%  |
| 16/10   | 27        | 9.89%   |
| 3/2     | 4         | 1.47%   |
| Unknown | 3         | 1.1%    |
| 4/3     | 1         | 0.37%   |
| 21/9    | 1         | 0.37%   |
| 0.62    | 1         | 0.37%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 122       | 40.67%  |
| 81-90          | 58        | 19.33%  |
| 201-250        | 22        | 7.33%   |
| 121-130        | 22        | 7.33%   |
| 71-80          | 15        | 5%      |
| 61-70          | 11        | 3.67%   |
| 51-60          | 7         | 2.33%   |
| 131-140        | 7         | 2.33%   |
| Unknown        | 6         | 2%      |
| 301-350        | 5         | 1.67%   |
| 151-200        | 5         | 1.67%   |
| 251-300        | 4         | 1.33%   |
| 141-150        | 4         | 1.33%   |
| 351-500        | 3         | 1%      |
| 41-50          | 3         | 1%      |
| More than 1000 | 2         | 0.67%   |
| 1-40           | 1         | 0.33%   |
| 111-120        | 1         | 0.33%   |
| 501-1000       | 1         | 0.33%   |
| 91-100         | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 108       | 36.49%  |
| 121-160       | 103       | 34.8%   |
| 51-100        | 51        | 17.23%  |
| 161-240       | 18        | 6.08%   |
| More than 240 | 8         | 2.7%    |
| Unknown       | 6         | 2.03%   |
| 1-50          | 2         | 0.68%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 221       | 81.85%  |
| 2     | 39        | 14.44%  |
| 3     | 5         | 1.85%   |
| 0     | 5         | 1.85%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 142       | 33.18%  |
| Realtek Semiconductor             | 137       | 32.01%  |
| Qualcomm Atheros                  | 71        | 16.59%  |
| Broadcom                          | 30        | 7.01%   |
| Broadcom Limited                  | 11        | 2.57%   |
| Marvell Technology Group          | 6         | 1.4%    |
| Ralink                            | 5         | 1.17%   |
| Sierra Wireless                   | 4         | 0.93%   |
| Ralink Technology                 | 4         | 0.93%   |
| TP-Link                           | 2         | 0.47%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.47%   |
| Ericsson Business Mobile Networks | 2         | 0.47%   |
| Xiaomi                            | 1         | 0.23%   |
| Tenda                             | 1         | 0.23%   |
| Samsung Electronics               | 1         | 0.23%   |
| Qualcomm Atheros Communications   | 1         | 0.23%   |
| Qualcomm                          | 1         | 0.23%   |
| NetGear                           | 1         | 0.23%   |
| Lenovo                            | 1         | 0.23%   |
| Hewlett-Packard                   | 1         | 0.23%   |
| Fibocom                           | 1         | 0.23%   |
| Dell                              | 1         | 0.23%   |
| Attansic Technology               | 1         | 0.23%   |
| ASIX Electronics                  | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 88        | 16.89%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 33        | 6.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 21        | 4.03%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 2.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 2.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 2.5%    |
| Intel Wireless 7265                                                     | 13        | 2.5%    |
| Intel Wireless 7260                                                     | 13        | 2.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 2.3%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 9         | 1.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.73%   |
| Intel Wireless 3165                                                     | 9         | 1.73%   |
| Intel Wireless 8265 / 8275                                              | 8         | 1.54%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.54%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.15%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.15%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.15%   |
| Intel Ethernet Connection I218-LM                                       | 5         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 0.96%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.96%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.96%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.77%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.77%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.77%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 3         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.58%   |
| Intel Wireless 8260                                                     | 3         | 0.58%   |
| Intel WiFi Link 5100                                                    | 3         | 0.58%   |
| Intel Ethernet Connection I219-V                                        | 3         | 0.58%   |
| Intel Ethernet Connection (4) I219-V                                    | 3         | 0.58%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 0.58%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 3         | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 0.58%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 2         | 0.38%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.38%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.38%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.38%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.38%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.38%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.38%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 2         | 0.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.38%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.38%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                 | 2         | 0.38%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.38%   |
| Intel Wireless 3160                                                     | 2         | 0.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 134       | 47.69%  |
| Qualcomm Atheros                | 60        | 21.35%  |
| Realtek Semiconductor           | 33        | 11.74%  |
| Broadcom                        | 22        | 7.83%   |
| Broadcom Limited                | 10        | 3.56%   |
| Ralink                          | 5         | 1.78%   |
| Sierra Wireless                 | 4         | 1.42%   |
| Ralink Technology               | 4         | 1.42%   |
| TP-Link                         | 2         | 0.71%   |
| Tenda                           | 1         | 0.36%   |
| Qualcomm Atheros Communications | 1         | 0.36%   |
| Qualcomm                        | 1         | 0.36%   |
| NetGear                         | 1         | 0.36%   |
| Hewlett-Packard                 | 1         | 0.36%   |
| Fibocom                         | 1         | 0.36%   |
| Dell                            | 1         | 0.36%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 5.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 4.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 4.63%   |
| Intel Wireless 7265                                                     | 13        | 4.63%   |
| Intel Wireless 7260                                                     | 13        | 4.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 4.27%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 3.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.2%    |
| Intel Wireless 3165                                                     | 9         | 3.2%    |
| Intel Wireless 8265 / 8275                                              | 8         | 2.85%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 2.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 2.14%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 2.14%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 2.14%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.42%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.42%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 1.42%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.42%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.42%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 1.42%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.07%   |
| Intel Wireless 8260                                                     | 3         | 1.07%   |
| Intel WiFi Link 5100                                                    | 3         | 1.07%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.07%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 3         | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.07%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.71%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.71%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.71%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.71%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.71%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.71%   |
| Intel Wireless 3160                                                     | 2         | 0.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.71%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.71%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.71%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.71%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 2         | 0.71%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 1         | 0.36%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                   | 1         | 0.36%   |
| Tenda U12                                                               | 1         | 0.36%   |
| Sierra Wireless MC8305 Modem                                            | 1         | 0.36%   |
| Sierra Wireless EM7455                                                  | 1         | 0.36%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 1         | 0.36%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.36%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.36%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 1         | 0.36%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 1         | 0.36%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.36%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.36%   |
| Ralink RT5572 Wireless Adapter                                          | 1         | 0.36%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 130       | 55.08%  |
| Intel                            | 65        | 27.54%  |
| Qualcomm Atheros                 | 16        | 6.78%   |
| Broadcom                         | 10        | 4.24%   |
| Marvell Technology Group         | 6         | 2.54%   |
| Silicon Integrated Systems [SiS] | 2         | 0.85%   |
| Broadcom Limited                 | 2         | 0.85%   |
| Xiaomi                           | 1         | 0.42%   |
| Samsung Electronics              | 1         | 0.42%   |
| Lenovo                           | 1         | 0.42%   |
| Attansic Technology              | 1         | 0.42%   |
| ASIX Electronics                 | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 36.97%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 13.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 8.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.78%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 3.36%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.1%    |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 2.1%    |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.1%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.26%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.26%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.26%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.84%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.84%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.84%   |
| Intel Ethernet Connection (14) I219-LM                            | 2         | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.84%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.42%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.42%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.42%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.42%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.42%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.42%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.42%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.42%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.42%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.42%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.42%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.42%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.42%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.42%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 1         | 0.42%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.42%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.42%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.42%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.42%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.42%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.42%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.42%   |
| ASIX AX88772                                                      | 1         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 263       | 52.81%  |
| Ethernet | 233       | 46.79%  |
| Modem    | 2         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 218       | 77.03%  |
| Ethernet | 65        | 22.97%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 215       | 79.93%  |
| 1     | 51        | 18.96%  |
| 0     | 2         | 0.74%   |
| 3     | 1         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 232       | 86.25%  |
| Yes  | 37        | 13.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 98        | 47.57%  |
| Qualcomm Atheros Communications | 26        | 12.62%  |
| Realtek Semiconductor           | 20        | 9.71%   |
| Broadcom                        | 19        | 9.22%   |
| Dell                            | 11        | 5.34%   |
| Lite-On Technology              | 9         | 4.37%   |
| IMC Networks                    | 9         | 4.37%   |
| Foxconn / Hon Hai               | 4         | 1.94%   |
| Cambridge Silicon Radio         | 3         | 1.46%   |
| Ralink Technology               | 2         | 0.97%   |
| ASUSTek Computer                | 2         | 0.97%   |
| Ralink                          | 1         | 0.49%   |
| Foxconn International           | 1         | 0.49%   |
| Apple                           | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 51        | 24.76%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 6.8%    |
| Intel AX201 Bluetooth                               | 12        | 5.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 4.37%   |
| Realtek Bluetooth Radio                             | 8         | 3.88%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 3.88%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 3.4%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 3.4%    |
| Intel AX200 Bluetooth                               | 7         | 3.4%    |
| IMC Networks Bluetooth Device                       | 7         | 3.4%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 2.91%   |
| Dell DW375 Bluetooth Module                         | 6         | 2.91%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 1.94%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 1.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.46%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.46%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.46%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.46%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.46%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.97%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.97%   |
| Lite-On Bluetooth Device                            | 2         | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.97%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.97%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 2         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.97%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.49%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.49%   |
| Ralink CSR BS8510                                   | 1         | 0.49%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.49%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.49%   |
| IMC Networks BCM20702A0                             | 1         | 0.49%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.49%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.49%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.49%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.49%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.49%   |
| Broadcom HP Portable Valentine                      | 1         | 0.49%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.49%   |
| Broadcom BCM20702A0                                 | 1         | 0.49%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.49%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.49%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.49%   |
| Apple Bluetooth HCI                                 | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 227       | 68.37%  |
| Nvidia                                         | 42        | 12.65%  |
| AMD                                            | 42        | 12.65%  |
| Realtek Semiconductor                          | 3         | 0.9%    |
| Silicon Integrated Systems [SiS]               | 2         | 0.6%    |
| Lenovo                                         | 2         | 0.6%    |
| Sony                                           | 1         | 0.3%    |
| Siemens Information and Communication Products | 1         | 0.3%    |
| Plantronics                                    | 1         | 0.3%    |
| No brand                                       | 1         | 0.3%    |
| Meizu                                          | 1         | 0.3%    |
| Logitech                                       | 1         | 0.3%    |
| Kingston Technology                            | 1         | 0.3%    |
| GuangZhou FiiO Electronics                     | 1         | 0.3%    |
| GN Netcom                                      | 1         | 0.3%    |
| Generalplus Technology                         | 1         | 0.3%    |
| Elite Silicon                                  | 1         | 0.3%    |
| Corsair                                        | 1         | 0.3%    |
| Conexant Systems                               | 1         | 0.3%    |
| C-Media Electronics                            | 1         | 0.3%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 33        | 8.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 8.23%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 5.99%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 4.24%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 3.99%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 3.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 3.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 2.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.49%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.49%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.49%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.49%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.49%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.5%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.5%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.5%    |
| AMD FCH Azalia Controller                                                                         | 6         | 1.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.25%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.25%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1%      |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 1%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1%      |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1%      |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.75%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.75%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.75%   |
| Nvidia Audio device                                                                               | 3         | 0.75%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 3         | 0.75%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.5%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.5%    |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.5%    |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.5%    |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 0.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.5%    |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.5%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.5%    |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 2         | 0.5%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.5%    |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.25%   |
| Siemens Information and Communication Products optiPoint 500                                      | 1         | 0.25%   |
| Plantronics C320-M                                                                                | 1         | 0.25%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.25%   |
| Nvidia stereo controller                                                                          | 1         | 0.25%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.25%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.25%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.25%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 61        | 25.96%  |
| SK Hynix                                         | 43        | 18.3%   |
| Micron Technology                                | 30        | 12.77%  |
| Kingston                                         | 21        | 8.94%   |
| Unknown                                          | 17        | 7.23%   |
| Crucial                                          | 13        | 5.53%   |
| Elpida                                           | 8         | 3.4%    |
| Ramaxel Technology                               | 7         | 2.98%   |
| Nanya Technology                                 | 7         | 2.98%   |
| Smart                                            | 5         | 2.13%   |
| A-DATA Technology                                | 4         | 1.7%    |
| Unknown (ABCD)                                   | 2         | 0.85%   |
| Teikon                                           | 2         | 0.85%   |
| Patriot                                          | 2         | 0.85%   |
| GOODRAM                                          | 2         | 0.85%   |
| Corsair                                          | 2         | 0.85%   |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.43%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.43%   |
| Toshiba                                          | 1         | 0.43%   |
| Team                                             | 1         | 0.43%   |
| Qimonda                                          | 1         | 0.43%   |
| Netlist                                          | 1         | 0.43%   |
| G.Skill                                          | 1         | 0.43%   |
| ASint Technology                                 | 1         | 0.43%   |
| Apacer                                           | 1         | 0.43%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                                 | 6         | 2.4%    |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                                | 5         | 2%      |
| Micron RAM 16KTF1G64HZ-1G6E1 8192MB SODIMM DDR3 1600MT/s                              | 5         | 2%      |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                                 | 4         | 1.6%    |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                                | 3         | 1.2%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                                 | 3         | 1.2%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                                 | 3         | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                                 | 3         | 1.2%    |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s                              | 3         | 1.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                                 | 3         | 1.2%    |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s                            | 3         | 1.2%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                                        | 2         | 0.8%    |
| Unknown RAM Module 4096MB SODIMM DDR3                                                 | 2         | 0.8%    |
| Unknown RAM Module 2048MB SODIMM DRAM                                                 | 2         | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s                        | 2         | 0.8%    |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s                              | 2         | 0.8%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                                | 2         | 0.8%    |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s                             | 2         | 0.8%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s                             | 2         | 0.8%    |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s                            | 2         | 0.8%    |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                                | 2         | 0.8%    |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                                | 2         | 0.8%    |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s                                | 2         | 0.8%    |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                                 | 2         | 0.8%    |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s                                 | 2         | 0.8%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s                                 | 2         | 0.8%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s                                 | 2         | 0.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                                 | 2         | 0.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s                           | 2         | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                                 | 2         | 0.8%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                                 | 2         | 0.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                                 | 2         | 0.8%    |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                                 | 2         | 0.8%    |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s                               | 2         | 0.8%    |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s                         | 2         | 0.8%    |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s                              | 2         | 0.8%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                                 | 2         | 0.8%    |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s                               | 2         | 0.8%    |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s                               | 2         | 0.8%    |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s                                | 2         | 0.8%    |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s                                  | 2         | 0.8%    |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                                      | 1         | 0.4%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                                        | 1         | 0.4%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                                        | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM LPDDR4 2400MT/s                                      | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                                        | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR3                                                 | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                                         | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM DDR2                                                 | 1         | 0.4%    |
| Unknown RAM Module 2048MB SODIMM 667MT/s                                              | 1         | 0.4%    |
| Unknown RAM Module 16384MB SODIMM DDR4 2400MT/s                                       | 1         | 0.4%    |
| Unknown RAM Module 1536MB SODIMM LPDDR4 2133MT/s                                      | 1         | 0.4%    |
| Unknown RAM Module 1024MB SODIMM DRAM                                                 | 1         | 0.4%    |
| Unknown (0x4D342037305435363633515A332D43463720) RAM Module 2048MB SODIMM DDR 800MT/s | 1         | 0.4%    |
| Unknown (0x36345431323830323045444C322E35433220) RAM Module 1024MB SODIMM DDR 800MT/s | 1         | 0.4%    |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s                                     | 1         | 0.4%    |
| Teikon RAM TMT251S6FR8C-H9HC 4GB SODIMM DDR3 1333MT/s                                 | 1         | 0.4%    |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s                                | 1         | 0.4%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s                                 | 1         | 0.4%    |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s                                 | 1         | 0.4%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 100       | 50%     |
| DDR4    | 67        | 33.5%   |
| LPDDR3  | 8         | 4%      |
| DDR2    | 8         | 4%      |
| LPDDR4  | 7         | 3.5%    |
| SDRAM   | 6         | 3%      |
| DRAM    | 2         | 1%      |
| DDR     | 1         | 0.5%    |
| Unknown | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 182       | 91.46%  |
| Row Of Chips | 13        | 6.53%   |
| Chip         | 3         | 1.51%   |
| DIMM         | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 87        | 39.73%  |
| 8192  | 62        | 28.31%  |
| 2048  | 40        | 18.26%  |
| 16384 | 19        | 8.68%   |
| 32768 | 6         | 2.74%   |
| 1024  | 4         | 1.83%   |
| 1536  | 1         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 66        | 30%     |
| 2667    | 39        | 17.73%  |
| 3200    | 21        | 9.55%   |
| 1334    | 21        | 9.55%   |
| 1333    | 14        | 6.36%   |
| 2400    | 11        | 5%      |
| 2133    | 11        | 5%      |
| 3266    | 6         | 2.73%   |
| Unknown | 6         | 2.73%   |
| 4199    | 5         | 2.27%   |
| 1067    | 4         | 1.82%   |
| 1066    | 4         | 1.82%   |
| 667     | 4         | 1.82%   |
| 800     | 3         | 1.36%   |
| 4267    | 1         | 0.45%   |
| 2048    | 1         | 0.45%   |
| 1867    | 1         | 0.45%   |
| 975     | 1         | 0.45%   |
| 533     | 1         | 0.45%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| QinHeng Electronics | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |
| Brother Industries  | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| QinHeng CH340S                   | 1         | 33.33%  |
| Canon PIXMA MG2500 Series        | 1         | 33.33%  |
| Brother DCP-7055 scanner/printer | 1         | 33.33%  |

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
| Chicony Electronics                    | 75        | 31.25%  |
| Microdia                               | 25        | 10.42%  |
| Acer                                   | 25        | 10.42%  |
| Sunplus Innovation Technology          | 17        | 7.08%   |
| IMC Networks                           | 14        | 5.83%   |
| Realtek Semiconductor                  | 10        | 4.17%   |
| Quanta                                 | 10        | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.17%   |
| Ricoh                                  | 8         | 3.33%   |
| Suyin                                  | 7         | 2.92%   |
| Silicon Motion                         | 6         | 2.5%    |
| Lite-On Technology                     | 5         | 2.08%   |
| Syntek                                 | 4         | 1.67%   |
| Logitech                               | 4         | 1.67%   |
| Apple                                  | 4         | 1.67%   |
| Luxvisions Innotech Limited            | 2         | 0.83%   |
| Alcor Micro                            | 2         | 0.83%   |
| Z-Star Microelectronics                | 1         | 0.42%   |
| Y Media                                | 1         | 0.42%   |
| Samsung Electronics                    | 1         | 0.42%   |
| Ruision                                | 1         | 0.42%   |
| Primax Electronics                     | 1         | 0.42%   |
| Microsoft                              | 1         | 0.42%   |
| Lenovo                                 | 1         | 0.42%   |
| Importek                               | 1         | 0.42%   |
| Generalplus Technology                 | 1         | 0.42%   |
| DigiTech                               | 1         | 0.42%   |
| Cubeternet                             | 1         | 0.42%   |
| Aveo Technology                        | 1         | 0.42%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 17        | 7.05%   |
| Sunplus Integrated_Webcam_HD                     | 8         | 3.32%   |
| Microdia Integrated_Webcam_HD                    | 8         | 3.32%   |
| Chicony USB2.0 VGA UVC WebCam                    | 7         | 2.9%    |
| Chicony HD Webcam                                | 6         | 2.49%   |
| Acer Integrated Camera                           | 6         | 2.49%   |
| Acer BisonCam, NB Pro                            | 6         | 2.49%   |
| Microdia Laptop_Integrated_Webcam_HD             | 5         | 2.07%   |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 2.07%   |
| Ricoh HD Webcam                                  | 4         | 1.66%   |
| Suyin HP TrueVision HD Integrated Webcam         | 3         | 1.24%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 3         | 1.24%   |
| Realtek Integrated_Webcam_HD                     | 3         | 1.24%   |
| Quanta HD User Facing                            | 3         | 1.24%   |
| Microdia Integrated Webcam                       | 3         | 1.24%   |
| Lite-On HP HD Camera                             | 3         | 1.24%   |
| Chicony Integrated Camera (1280x720@30)          | 3         | 1.24%   |
| Chicony HP Wide Vision HD Camera                 | 3         | 1.24%   |
| Chicony HP HD Webcam                             | 3         | 1.24%   |
| Chicony CNF9055 Toshiba Webcam                   | 3         | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 3         | 1.24%   |
| Acer Lenovo Integrated Webcam                    | 3         | 1.24%   |
| Acer Lenovo EasyCamera                           | 3         | 1.24%   |
| Syntek EasyCamera                                | 2         | 0.83%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 2         | 0.83%   |
| Silicon Motion WebCam SC-13HDL11939N             | 2         | 0.83%   |
| Silicon Motion 300k Pixel Camera                 | 2         | 0.83%   |
| Ricoh Sony Visual Communication Camera           | 2         | 0.83%   |
| Ricoh Laptop_Integrated_Webcam_FHD               | 2         | 0.83%   |
| Realtek USB Camera                               | 2         | 0.83%   |
| Realtek Lenovo EasyCamera                        | 2         | 0.83%   |
| Quanta VGA WebCam                                | 2         | 0.83%   |
| Quanta Laptop_Integrated_Webcam_2HDM             | 2         | 0.83%   |
| Microdia Laptop_Integrated_Webcam_2M             | 2         | 0.83%   |
| Microdia Dell Integrated HD Webcam               | 2         | 0.83%   |
| IMC Networks UVC VGA Webcam                      | 2         | 0.83%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.83%   |
| Chicony USB2.0 UVC WebCam                        | 2         | 0.83%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 2         | 0.83%   |
| Chicony HP Webcam-101                            | 2         | 0.83%   |
| Chicony HP Webcam                                | 2         | 0.83%   |
| Chicony HP HD Webcam [Fixed]                     | 2         | 0.83%   |
| Chicony HD WebCam (Acer)                         | 2         | 0.83%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 2         | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE                        | 2         | 0.83%   |
| Z-Star Vega USB 2.0 Camera                       | 1         | 0.41%   |
| Y Media USB Camera                               | 1         | 0.41%   |
| Syntek USB Video Device                          | 1         | 0.41%   |
| Syntek Integrated Camera                         | 1         | 0.41%   |
| Suyin Sony Visual Communication Camera           | 1         | 0.41%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.41%   |
| Sunplus Laptop_Integrated_Webcam_1.3M            | 1         | 0.41%   |
| Sunplus Integrated_Webcam_FHD                    | 1         | 0.41%   |
| Sunplus HP Universal Camera                      | 1         | 0.41%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.41%   |
| Sunplus HD WebCam                                | 1         | 0.41%   |
| Sunplus Dell Integrated Webcam                   | 1         | 0.41%   |
| Silicon Motion WebCam SCB-1100N                  | 1         | 0.41%   |
| Silicon Motion WebCam SC-10HDP12631N             | 1         | 0.41%   |
| Samsung Galaxy A5 (MTP)                          | 1         | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 53.49%  |
| Synaptics                  | 9         | 20.93%  |
| Upek                       | 3         | 6.98%   |
| Shenzhen Goodix Technology | 3         | 6.98%   |
| Elan Microelectronics      | 3         | 6.98%   |
| Focal-systems.Corp         | 1         | 2.33%   |
| AuthenTec                  | 1         | 2.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 4         | 9.3%    |
| Validity Sensors VFS491                                    | 4         | 9.3%    |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 9.3%    |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 6.98%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 3         | 6.98%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 4.65%   |
| Validity Sensors Fingerprint scanner                       | 2         | 4.65%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 4.65%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.65%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.65%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.65%   |
| Elan ELAN:Fingerprint                                      | 2         | 4.65%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.33%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                            | 1         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.33%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 2.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.33%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.33%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 2.33%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.33%   |
| AuthenTec AES2810                                          | 1         | 2.33%   |
| Unknown                                                    | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 58.33%  |
| Alcor Micro           | 7         | 19.44%  |
| Upek                  | 2         | 5.56%   |
| O2 Micro              | 2         | 5.56%   |
| Lenovo                | 2         | 5.56%   |
| Gemalto (was Gemplus) | 1         | 2.78%   |
| Advanced Card Systems | 1         | 2.78%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 27.78%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 19.44%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 19.44%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.56%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.56%   |
| Broadcom 5880                                                                | 2         | 5.56%   |
| Broadcom 58200                                                               | 2         | 5.56%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.78%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 168       | 61.76%  |
| 1     | 85        | 31.25%  |
| 2     | 16        | 5.88%   |
| 8     | 2         | 0.74%   |
| 3     | 1         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 43        | 32.33%  |
| Chipcard                 | 34        | 25.56%  |
| Graphics card            | 25        | 18.8%   |
| Storage                  | 8         | 6.02%   |
| Net/wireless             | 7         | 5.26%   |
| Multimedia controller    | 3         | 2.26%   |
| Camera                   | 3         | 2.26%   |
| Bluetooth                | 3         | 2.26%   |
| Sound                    | 2         | 1.5%    |
| Communication controller | 2         | 1.5%    |
| Network                  | 1         | 0.75%   |
| Firewire controller      | 1         | 0.75%   |
| Card reader              | 1         | 0.75%   |

