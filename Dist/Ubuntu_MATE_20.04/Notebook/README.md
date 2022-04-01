Ubuntu MATE 20.04 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu MATE 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 346

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Dell          | Precision M4800             | [fd49c10a9f](https://linux-hardware.org/?probe=fd49c10a9f) | May 24, 2021 |
| Lenovo        | ThinkPad X230 23253Z5       | [0af5f89b23](https://linux-hardware.org/?probe=0af5f89b23) | May 22, 2021 |
| Unknown       | Unknown                     | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite C675              | [5225757c73](https://linux-hardware.org/?probe=5225757c73) | May 19, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [96c336b648](https://linux-hardware.org/?probe=96c336b648) | May 15, 2021 |
| Lenovo        | ThinkPad E520 11433KG       | [336659ac3a](https://linux-hardware.org/?probe=336659ac3a) | May 15, 2021 |
| Wortmann      | TERRA_MOBILE_1749           | [47e02d3203](https://linux-hardware.org/?probe=47e02d3203) | May 14, 2021 |
| Toshiba       | Satellite Pro C660          | [d4ed145cfd](https://linux-hardware.org/?probe=d4ed145cfd) | May 14, 2021 |
| Dell          | G7 7588                     | [8ae4bf0bf2](https://linux-hardware.org/?probe=8ae4bf0bf2) | May 10, 2021 |
| HP            | Pavilion                    | [ade11f7a65](https://linux-hardware.org/?probe=ade11f7a65) | May 08, 2021 |
| Cube          | i18-L                       | [77cd23575f](https://linux-hardware.org/?probe=77cd23575f) | May 07, 2021 |
| HP            | Pavilion                    | [e874b8bf1c](https://linux-hardware.org/?probe=e874b8bf1c) | May 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [90d1b76313](https://linux-hardware.org/?probe=90d1b76313) | May 04, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [66c2a37fb9](https://linux-hardware.org/?probe=66c2a37fb9) | May 01, 2021 |
| Lenovo        | ThinkPad X201 Tablet 309... | [30c34c8c01](https://linux-hardware.org/?probe=30c34c8c01) | May 01, 2021 |
| Dell          | G7 7588                     | [1393a855bb](https://linux-hardware.org/?probe=1393a855bb) | Apr 25, 2021 |
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
| HP            | Pavilion g7                 | [6d79297a65](https://linux-hardware.org/?probe=6d79297a65) | Feb 26, 2021 |
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
| Dell          | G7 7588                     | [1006977f89](https://linux-hardware.org/?probe=1006977f89) | Jan 28, 2021 |
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
| HP            | 255 G7 Notebook PC          | [153a36bfa0](https://linux-hardware.org/?probe=153a36bfa0) | Nov 14, 2020 |
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
| HP            | 255 G7 Notebook PC          | [07f3bdda40](https://linux-hardware.org/?probe=07f3bdda40) | Oct 25, 2020 |
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
| HP            | ZBook 14u G6                | [5ffb6aaedb](https://linux-hardware.org/?probe=5ffb6aaedb) | Aug 17, 2020 |
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
| Dell          | XPS L702X                   | [86885b0835](https://linux-hardware.org/?probe=86885b0835) | Aug 04, 2020 |
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
| Toshiba       | Satellite M500              | [96d989965c](https://linux-hardware.org/?probe=96d989965c) | Jun 04, 2020 |
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
| Dell          | Latitude E6400              | [7402a2d316](https://linux-hardware.org/?probe=7402a2d316) | May 16, 2020 |
| Dell          | Latitude E6400              | [9c8f7c7f2c](https://linux-hardware.org/?probe=9c8f7c7f2c) | May 16, 2020 |
| Dell          | Latitude E6400              | [491ea13111](https://linux-hardware.org/?probe=491ea13111) | May 16, 2020 |
| Dell          | Latitude E6400              | [0e2b5d699e](https://linux-hardware.org/?probe=0e2b5d699e) | May 16, 2020 |
| HP            | 250 G1                      | [bc48855d22](https://linux-hardware.org/?probe=bc48855d22) | May 16, 2020 |
| Lenovo        | ThinkPad X240 20AMS08816    | [5581eee295](https://linux-hardware.org/?probe=5581eee295) | May 10, 2020 |
| Dell          | XPS L502X                   | [f095fb06d8](https://linux-hardware.org/?probe=f095fb06d8) | May 09, 2020 |
| HP            | 250 G5 Notebook PC          | [33e1791dd6](https://linux-hardware.org/?probe=33e1791dd6) | May 06, 2020 |
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
| 5.4.0-42-generic     | 25        | 8.87%   |
| 5.4.0-52-generic     | 17        | 6.03%   |
| 5.4.0-47-generic     | 10        | 3.55%   |
| 5.4.0-40-generic     | 10        | 3.55%   |
| 5.4.0-58-generic     | 9         | 3.19%   |
| 5.8.0-50-generic     | 8         | 2.84%   |
| 5.4.0-48-generic     | 8         | 2.84%   |
| 5.4.0-31-generic     | 8         | 2.84%   |
| 5.4.0-65-generic     | 7         | 2.48%   |
| 5.4.0-54-generic     | 7         | 2.48%   |
| 5.4.0-26-generic     | 7         | 2.48%   |
| 5.11.0-40-generic    | 7         | 2.48%   |
| 5.4.0-56-generic     | 6         | 2.13%   |
| 5.4.0-45-generic     | 6         | 2.13%   |
| 5.8.0-59-generic     | 5         | 1.77%   |
| 5.8.0-48-generic     | 5         | 1.77%   |
| 5.8.0-43-generic     | 5         | 1.77%   |
| 5.4.0-81-generic     | 5         | 1.77%   |
| 5.4.0-37-generic     | 5         | 1.77%   |
| 5.4.0-29-generic     | 5         | 1.77%   |
| 5.11.0-38-generic    | 5         | 1.77%   |
| 5.11.0-37-generic    | 5         | 1.77%   |
| 5.8.0-53-generic     | 4         | 1.42%   |
| 5.4.0-91-generic     | 4         | 1.42%   |
| 5.4.0-89-generic     | 4         | 1.42%   |
| 5.4.0-51-generic     | 4         | 1.42%   |
| 5.13.0-30-generic    | 4         | 1.42%   |
| 5.4.0-90-generic     | 3         | 1.06%   |
| 5.4.0-74-generic     | 3         | 1.06%   |
| 5.4.0-73-generic     | 3         | 1.06%   |
| 5.4.0-39-generic     | 3         | 1.06%   |
| 5.4.0-33-generic     | 3         | 1.06%   |
| 5.4.0-28-generic     | 3         | 1.06%   |
| 5.11.0-43-generic    | 3         | 1.06%   |
| 5.11.0-41-generic    | 3         | 1.06%   |
| 5.8.0-63-generic     | 2         | 0.71%   |
| 5.8.0-45-generic     | 2         | 0.71%   |
| 5.8.0-38-generic     | 2         | 0.71%   |
| 5.4.0-80-generic     | 2         | 0.71%   |
| 5.4.0-72-generic     | 2         | 0.71%   |
| 5.4.0-70-generic     | 2         | 0.71%   |
| 5.4.0-67-generic     | 2         | 0.71%   |
| 5.4.0-66-generic     | 2         | 0.71%   |
| 5.4.0-34-generic     | 2         | 0.71%   |
| 5.4.0-14-generic     | 2         | 0.71%   |
| 5.11.0-46-generic    | 2         | 0.71%   |
| 5.9.3-050903-generic | 1         | 0.35%   |
| 5.8.17-rockchip64    | 1         | 0.35%   |
| 5.8.0-52-generic     | 1         | 0.35%   |
| 5.8.0-34-generic     | 1         | 0.35%   |
| 5.8.0-33-generic     | 1         | 0.35%   |
| 5.4.0-99-generic     | 1         | 0.35%   |
| 5.4.0-96-generic     | 1         | 0.35%   |
| 5.4.0-9-generic      | 1         | 0.35%   |
| 5.4.0-88-generic     | 1         | 0.35%   |
| 5.4.0-84-generic     | 1         | 0.35%   |
| 5.4.0-77-generic     | 1         | 0.35%   |
| 5.4.0-7642-generic   | 1         | 0.35%   |
| 5.4.0-64-generic     | 1         | 0.35%   |
| 5.4.0-62-generic     | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 175       | 68.63%  |
| 5.8.0   | 33        | 12.94%  |
| 5.11.0  | 29        | 11.37%  |
| 5.13.0  | 12        | 4.71%   |
| 5.3.0   | 2         | 0.78%   |
| 5.9.3   | 1         | 0.39%   |
| 5.8.17  | 1         | 0.39%   |
| 5.15.6  | 1         | 0.39%   |
| 5.14.0  | 1         | 0.39%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 175       | 68.63%  |
| 5.8     | 34        | 13.33%  |
| 5.11    | 29        | 11.37%  |
| 5.13    | 12        | 4.71%   |
| 5.3     | 2         | 0.78%   |
| 5.9     | 1         | 0.39%   |
| 5.15    | 1         | 0.39%   |
| 5.14    | 1         | 0.39%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 253       | 99.61%  |
| aarch64 | 1         | 0.39%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 248       | 97.64%  |
| Cinnamon   | 2         | 0.79%   |
| X-Cinnamon | 1         | 0.39%   |
| KDE5       | 1         | 0.39%   |
| i3         | 1         | 0.39%   |
| GNOME      | 1         | 0.39%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 248       | 97.64%  |
| Wayland | 3         | 1.18%   |
| Tty     | 3         | 1.18%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 98        | 37.69%  |
| Unknown | 74        | 28.46%  |
| LightDM | 71        | 27.31%  |
| GDM     | 14        | 5.38%   |
| GDM3    | 2         | 0.77%   |
| SDDM    | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 90        | 35.29%  |
| pt_BR   | 27        | 10.59%  |
| fr_FR   | 25        | 9.8%    |
| en_GB   | 17        | 6.67%   |
| de_DE   | 13        | 5.1%    |
| it_IT   | 10        | 3.92%   |
| es_ES   | 10        | 3.92%   |
| ru_RU   | 8         | 3.14%   |
| ru_UA   | 6         | 2.35%   |
| C       | 6         | 2.35%   |
| pl_PL   | 5         | 1.96%   |
| es_AR   | 4         | 1.57%   |
| en_PH   | 3         | 1.18%   |
| de_CH   | 3         | 1.18%   |
| nl_NL   | 2         | 0.78%   |
| en_IN   | 2         | 0.78%   |
| ca_ES   | 2         | 0.78%   |
| zh_TW   | 1         | 0.39%   |
| zh_CN   | 1         | 0.39%   |
| uk_UA   | 1         | 0.39%   |
| sv_SE   | 1         | 0.39%   |
| sk_SK   | 1         | 0.39%   |
| hu_HU   | 1         | 0.39%   |
| fr_CH   | 1         | 0.39%   |
| fr_CA   | 1         | 0.39%   |
| fr_BE   | 1         | 0.39%   |
| fi_FI   | 1         | 0.39%   |
| et_EE   | 1         | 0.39%   |
| es_UY   | 1         | 0.39%   |
| es_PR   | 1         | 0.39%   |
| es_PE   | 1         | 0.39%   |
| es_MX   | 1         | 0.39%   |
| en_NZ   | 1         | 0.39%   |
| en_IE   | 1         | 0.39%   |
| en_CA   | 1         | 0.39%   |
| en_AU   | 1         | 0.39%   |
| da_DK   | 1         | 0.39%   |
| cs_CZ   | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 129       | 50.79%  |
| BIOS | 125       | 49.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 237       | 92.58%  |
| Overlay | 10        | 3.91%   |
| Btrfs   | 3         | 1.17%   |
| Zfs     | 2         | 0.78%   |
| Xfs     | 2         | 0.78%   |
| Ext3    | 2         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 98        | 38.28%  |
| Unknown | 87        | 33.98%  |
| MBR     | 71        | 27.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 228       | 88.37%  |
| Yes       | 30        | 11.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 174       | 68.24%  |
| Yes       | 81        | 31.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 60        | 23.62%  |
| Hewlett-Packard        | 50        | 19.69%  |
| Dell                   | 50        | 19.69%  |
| ASUSTek Computer       | 25        | 9.84%   |
| Acer                   | 18        | 7.09%   |
| Toshiba                | 8         | 3.15%   |
| MSI                    | 7         | 2.76%   |
| Samsung Electronics    | 6         | 2.36%   |
| Sony                   | 3         | 1.18%   |
| Positivo               | 2         | 0.79%   |
| Packard Bell           | 2         | 0.79%   |
| Notebook               | 2         | 0.79%   |
| Medion                 | 2         | 0.79%   |
| GPD                    | 2         | 0.79%   |
| Apple                  | 2         | 0.79%   |
| Unknown                | 2         | 0.79%   |
| Wortmann AG            | 1         | 0.39%   |
| TUXEDO                 | 1         | 0.39%   |
| Teclast                | 1         | 0.39%   |
| System76               | 1         | 0.39%   |
| Star Labs              | 1         | 0.39%   |
| Polaroid               | 1         | 0.39%   |
| Pine Microsystems      | 1         | 0.39%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.39%   |
| Intel                  | 1         | 0.39%   |
| Fujitsu                | 1         | 0.39%   |
| Cube                   | 1         | 0.39%   |
| Chuwi                  | 1         | 0.39%   |
| AMI                    | 1         | 0.39%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Latitude E6420                        | 5         | 1.97%   |
| HP Pavilion dv7                            | 4         | 1.57%   |
| HP Notebook                                | 3         | 1.18%   |
| Dell Precision M4800                       | 3         | 1.18%   |
| Dell Latitude E6410                        | 3         | 1.18%   |
| Unknown                                    | 3         | 1.18%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS        | 2         | 0.79%   |
| HP Pavilion g6                             | 2         | 0.79%   |
| HP EliteBook 8470p                         | 2         | 0.79%   |
| Dell Vostro 3350                           | 2         | 0.79%   |
| Dell Latitude E6430                        | 2         | 0.79%   |
| Dell Inspiron 3421                         | 2         | 0.79%   |
| ASUS ZenBook UX431DA_UM431DA               | 2         | 0.79%   |
| ASUS X553MA                                | 2         | 0.79%   |
| ASUS X541SA                                | 2         | 0.79%   |
| Wortmann AG TERRA_MOBILE_1749              | 1         | 0.39%   |
| TUXEDO InfinityBook Pro 14 Gen6            | 1         | 0.39%   |
| Toshiba Satellite Pro L500                 | 1         | 0.39%   |
| Toshiba Satellite Pro C660                 | 1         | 0.39%   |
| Toshiba Satellite P755                     | 1         | 0.39%   |
| Toshiba Satellite M500                     | 1         | 0.39%   |
| Toshiba Satellite L350D                    | 1         | 0.39%   |
| Toshiba Satellite C675                     | 1         | 0.39%   |
| Toshiba Satellite C665                     | 1         | 0.39%   |
| Toshiba Satellite C660                     | 1         | 0.39%   |
| Teclast F15S                               | 1         | 0.39%   |
| System76 Serval WS                         | 1         | 0.39%   |
| Star Labs LabTop                           | 1         | 0.39%   |
| Sony VPCS12X9E                             | 1         | 0.39%   |
| Sony VPCF1290X                             | 1         | 0.39%   |
| Sony VPCEH1S1E                             | 1         | 0.39%   |
| Samsung SR58P                              | 1         | 0.39%   |
| Samsung R530/R730/R540                     | 1         | 0.39%   |
| Samsung 550P5C/550P7C                      | 1         | 0.39%   |
| Samsung 530U4E/540U4E                      | 1         | 0.39%   |
| Samsung 350V5C/351V5C/3540VC/3440VC        | 1         | 0.39%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.39%   |
| Positivo N8X0EK1                           | 1         | 0.39%   |
| Positivo Mobile                            | 1         | 0.39%   |
| Polaroid MP1464PR001                       | 1         | 0.39%   |
| Pine Microsystems Pine64 Pinebook Pro      | 1         | 0.39%   |
| Packard Bell EasyNote SL65                 | 1         | 0.39%   |
| Packard Bell EasyNote ME69BMP              | 1         | 0.39%   |
| ONE-NETBOOK TECHNOLOGY A1                  | 1         | 0.39%   |
| Notebook W54_W94_W955TU,-T,-C              | 1         | 0.39%   |
| Notebook W310CZ/CZ-T                       | 1         | 0.39%   |
| MSI GV62 8RD                               | 1         | 0.39%   |
| MSI GP72MVR 7RFX                           | 1         | 0.39%   |
| MSI GP72 6QF                               | 1         | 0.39%   |
| MSI GF63 Thin 9SCSR                        | 1         | 0.39%   |
| MSI GE72 7RE                               | 1         | 0.39%   |
| MSI GE60 2OC\2OD\2OE                       | 1         | 0.39%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD              | 1         | 0.39%   |
| Medion X682X                               | 1         | 0.39%   |
| Medion E15302                              | 1         | 0.39%   |
| Lenovo Z51-70 80K6                         | 1         | 0.39%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.39%   |
| Lenovo V570 HuronRiver Platform            | 1         | 0.39%   |
| Lenovo ThinkPad Yoga 260 20FES25400        | 1         | 0.39%   |
| Lenovo ThinkPad X270 20HN0013MX            | 1         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 37        | 14.57%  |
| Dell Latitude             | 19        | 7.48%   |
| HP Pavilion               | 17        | 6.69%   |
| Acer Aspire               | 15        | 5.91%   |
| Lenovo IdeaPad            | 10        | 3.94%   |
| HP EliteBook              | 9         | 3.54%   |
| Toshiba Satellite         | 8         | 3.15%   |
| Dell Precision            | 8         | 3.15%   |
| Dell Inspiron             | 8         | 3.15%   |
| Dell XPS                  | 6         | 2.36%   |
| HP 250                    | 5         | 1.97%   |
| Dell Vostro               | 5         | 1.97%   |
| HP ZBook                  | 4         | 1.57%   |
| HP ProBook                | 4         | 1.57%   |
| ASUS VivoBook             | 4         | 1.57%   |
| HP Notebook               | 3         | 1.18%   |
| Unknown                   | 3         | 1.18%   |
| Packard Bell EasyNote     | 2         | 0.79%   |
| Lenovo ThinkBook          | 2         | 0.79%   |
| Lenovo Legion             | 2         | 0.79%   |
| Lenovo Flex               | 2         | 0.79%   |
| HP Laptop                 | 2         | 0.79%   |
| HP Compaq                 | 2         | 0.79%   |
| Dell Studio               | 2         | 0.79%   |
| ASUS ZenBook              | 2         | 0.79%   |
| ASUS X553MA               | 2         | 0.79%   |
| ASUS X541SA               | 2         | 0.79%   |
| Wortmann AG TERRA         | 1         | 0.39%   |
| TUXEDO InfinityBook       | 1         | 0.39%   |
| Teclast F15S              | 1         | 0.39%   |
| System76 Serval           | 1         | 0.39%   |
| Star Labs LabTop          | 1         | 0.39%   |
| Sony VPCS12X9E            | 1         | 0.39%   |
| Sony VPCF1290X            | 1         | 0.39%   |
| Sony VPCEH1S1E            | 1         | 0.39%   |
| Samsung SR58P             | 1         | 0.39%   |
| Samsung R530              | 1         | 0.39%   |
| Samsung 550P5C            | 1         | 0.39%   |
| Samsung 530U4E            | 1         | 0.39%   |
| Samsung 350V5C            | 1         | 0.39%   |
| Samsung 300E4A            | 1         | 0.39%   |
| Positivo N8X0EK1          | 1         | 0.39%   |
| Positivo Mobile           | 1         | 0.39%   |
| Polaroid MP1464PR001      | 1         | 0.39%   |
| Pine Microsystems Pine64  | 1         | 0.39%   |
| ONE-NETBOOK TECHNOLOGY A1 | 1         | 0.39%   |
| Notebook W54              | 1         | 0.39%   |
| Notebook W310CZ           | 1         | 0.39%   |
| MSI GV62                  | 1         | 0.39%   |
| MSI GP72MVR               | 1         | 0.39%   |
| MSI GP72                  | 1         | 0.39%   |
| MSI GF63                  | 1         | 0.39%   |
| MSI GE72                  | 1         | 0.39%   |
| MSI GE60                  | 1         | 0.39%   |
| MSI CR70                  | 1         | 0.39%   |
| Medion X682X              | 1         | 0.39%   |
| Medion E15302             | 1         | 0.39%   |
| Lenovo Z51-70             | 1         | 0.39%   |
| Lenovo Yoga               | 1         | 0.39%   |
| Lenovo V570               | 1         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 35        | 13.78%  |
| 2019    | 28        | 11.02%  |
| 2012    | 25        | 9.84%   |
| 2015    | 20        | 7.87%   |
| 2018    | 19        | 7.48%   |
| 2013    | 19        | 7.48%   |
| 2020    | 18        | 7.09%   |
| 2016    | 16        | 6.3%    |
| 2014    | 16        | 6.3%    |
| 2010    | 15        | 5.91%   |
| 2008    | 15        | 5.91%   |
| 2017    | 11        | 4.33%   |
| 2021    | 7         | 2.76%   |
| 2009    | 6         | 2.36%   |
| 2007    | 3         | 1.18%   |
| Unknown | 1         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 254       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 227       | 89.02%  |
| Enabled  | 28        | 10.98%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 254       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 74        | 28.79%  |
| 4.01-8.0    | 70        | 27.24%  |
| 8.01-16.0   | 40        | 15.56%  |
| 16.01-24.0  | 36        | 14.01%  |
| 32.01-64.0  | 16        | 6.23%   |
| 2.01-3.0    | 6         | 2.33%   |
| 1.01-2.0    | 6         | 2.33%   |
| 64.01-256.0 | 5         | 1.95%   |
| 24.01-32.0  | 4         | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 102       | 37.78%  |
| 2.01-3.0   | 73        | 27.04%  |
| 4.01-8.0   | 34        | 12.59%  |
| 3.01-4.0   | 32        | 11.85%  |
| 0.51-1.0   | 22        | 8.15%   |
| 8.01-16.0  | 6         | 2.22%   |
| 24.01-32.0 | 1         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 186       | 72.09%  |
| 2      | 62        | 24.03%  |
| 3      | 8         | 3.1%    |
| 4      | 1         | 0.39%   |
| 0      | 1         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 136       | 53.33%  |
| Yes       | 119       | 46.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 222       | 87.4%   |
| No        | 32        | 12.6%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 249       | 97.65%  |
| No        | 6         | 2.35%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 75.1%   |
| No        | 64        | 24.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Brazil      | 34        | 13.33%  |
| USA         | 30        | 11.76%  |
| France      | 28        | 10.98%  |
| Germany     | 22        | 8.63%   |
| UK          | 15        | 5.88%   |
| Spain       | 13        | 5.1%    |
| Italy       | 13        | 5.1%    |
| Russia      | 12        | 4.71%   |
| Ukraine     | 9         | 3.53%   |
| Switzerland | 6         | 2.35%   |
| Netherlands | 6         | 2.35%   |
| Argentina   | 5         | 1.96%   |
| Poland      | 4         | 1.57%   |
| Turkey      | 3         | 1.18%   |
| Norway      | 3         | 1.18%   |
| Indonesia   | 3         | 1.18%   |
| Greece      | 3         | 1.18%   |
| Finland     | 3         | 1.18%   |
| Canada      | 3         | 1.18%   |
| Vietnam     | 2         | 0.78%   |
| Thailand    | 2         | 0.78%   |
| Sweden      | 2         | 0.78%   |
| Portugal    | 2         | 0.78%   |
| Philippines | 2         | 0.78%   |
| Mexico      | 2         | 0.78%   |
| Ireland     | 2         | 0.78%   |
| India       | 2         | 0.78%   |
| Chile       | 2         | 0.78%   |
| Uruguay     | 1         | 0.39%   |
| Taiwan      | 1         | 0.39%   |
| Slovakia    | 1         | 0.39%   |
| RГ©union  | 1         | 0.39%   |
| Puerto Rico | 1         | 0.39%   |
| Peru        | 1         | 0.39%   |
| New Zealand | 1         | 0.39%   |
| Malaysia    | 1         | 0.39%   |
| Luxembourg  | 1         | 0.39%   |
| Kenya       | 1         | 0.39%   |
| Ivory Coast | 1         | 0.39%   |
| Hungary     | 1         | 0.39%   |
| Estonia     | 1         | 0.39%   |
| Ecuador     | 1         | 0.39%   |
| Denmark     | 1         | 0.39%   |
| Czechia     | 1         | 0.39%   |
| Croatia     | 1         | 0.39%   |
| China       | 1         | 0.39%   |
| Belgium     | 1         | 0.39%   |
| Belarus     | 1         | 0.39%   |
| Austria     | 1         | 0.39%   |
| Australia   | 1         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Sao Paulo                  | 9         | 3.44%   |
| Paris                      | 5         | 1.91%   |
| Itatiba                    | 5         | 1.91%   |
| Moscow                     | 4         | 1.53%   |
| Kyiv                       | 4         | 1.53%   |
| Rome                       | 3         | 1.15%   |
| Rio de Janeiro             | 3         | 1.15%   |
| JundiaГ­                 | 3         | 1.15%   |
| Barcelona                  | 3         | 1.15%   |
| Thessaloniki               | 2         | 0.76%   |
| Srednyaya Akhtuba          | 2         | 0.76%   |
| Oslo                       | 2         | 0.76%   |
| Offenbach                  | 2         | 0.76%   |
| Marseille                  | 2         | 0.76%   |
| Manchester                 | 2         | 0.76%   |
| Le Kremlin-Bicetre         | 2         | 0.76%   |
| Ho Chi Minh City           | 2         | 0.76%   |
| Herriman                   | 2         | 0.76%   |
| Evansville                 | 2         | 0.76%   |
| Essen                      | 2         | 0.76%   |
| Durham                     | 2         | 0.76%   |
| Dublin                     | 2         | 0.76%   |
| Berlin                     | 2         | 0.76%   |
| Basel                      | 2         | 0.76%   |
| Ankara                     | 2         | 0.76%   |
| Zapopan                    | 1         | 0.38%   |
| Zagreb                     | 1         | 0.38%   |
| Xining                     | 1         | 0.38%   |
| Willimantic                | 1         | 0.38%   |
| West Babylon               | 1         | 0.38%   |
| Wake Forest                | 1         | 0.38%   |
| ViГ±a del Mar            | 1         | 0.38%   |
| Vigo                       | 1         | 0.38%   |
| Vigneux-sur-Seine          | 1         | 0.38%   |
| Vienna                     | 1         | 0.38%   |
| Vedrin                     | 1         | 0.38%   |
| Valencia                   | 1         | 0.38%   |
| Ulm                        | 1         | 0.38%   |
| Trondheim                  | 1         | 0.38%   |
| Toulouse                   | 1         | 0.38%   |
| Toronto                    | 1         | 0.38%   |
| Thaire                     | 1         | 0.38%   |
| Terlizzi                   | 1         | 0.38%   |
| Tampere                    | 1         | 0.38%   |
| Tainan City                | 1         | 0.38%   |
| SГЈo JosГ© dos Pinhais | 1         | 0.38%   |
| SГЈo JosГ© dos Campos  | 1         | 0.38%   |
| Sydney                     | 1         | 0.38%   |
| Sutton Coldfield           | 1         | 0.38%   |
| Surabaya                   | 1         | 0.38%   |
| Studen                     | 1         | 0.38%   |
| Soto del Real              | 1         | 0.38%   |
| Seville                    | 1         | 0.38%   |
| Sevastopol                 | 1         | 0.38%   |
| Schwanden                  | 1         | 0.38%   |
| Santos                     | 1         | 0.38%   |
| SantarГ©m                | 1         | 0.38%   |
| Salta                      | 1         | 0.38%   |
| Sainte-Adresse             | 1         | 0.38%   |
| Saco                       | 1         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 47        | 52     | 14.83%  |
| WDC                   | 43        | 50     | 13.56%  |
| Samsung Electronics   | 43        | 51     | 13.56%  |
| Toshiba               | 32        | 38     | 10.09%  |
| Kingston              | 24        | 29     | 7.57%   |
| Unknown               | 17        | 20     | 5.36%   |
| SanDisk               | 17        | 22     | 5.36%   |
| Hitachi               | 14        | 15     | 4.42%   |
| SK Hynix              | 10        | 13     | 3.15%   |
| Intel                 | 10        | 12     | 3.15%   |
| Crucial               | 10        | 15     | 3.15%   |
| HGST                  | 5         | 5      | 1.58%   |
| China                 | 5         | 6      | 1.58%   |
| A-DATA Technology     | 5         | 5      | 1.58%   |
| KIOXIA                | 4         | 4      | 1.26%   |
| PNY                   | 3         | 3      | 0.95%   |
| Micron Technology     | 3         | 4      | 0.95%   |
| Fujitsu               | 3         | 3      | 0.95%   |
| Transcend             | 2         | 3      | 0.63%   |
| Silicon Motion        | 2         | 2      | 0.63%   |
| Phison                | 2         | 2      | 0.63%   |
| Patriot               | 2         | 2      | 0.63%   |
| Intenso               | 2         | 2      | 0.63%   |
| Apacer                | 2         | 3      | 0.63%   |
| Vaseky                | 1         | 1      | 0.32%   |
| SMART                 | 1         | 1      | 0.32%   |
| Realtek Semiconductor | 1         | 1      | 0.32%   |
| PLEXTOR               | 1         | 1      | 0.32%   |
| OCZ                   | 1         | 1      | 0.32%   |
| Netac                 | 1         | 1      | 0.32%   |
| LITEONIT              | 1         | 2      | 0.32%   |
| KingSpec              | 1         | 1      | 0.32%   |
| FORESEE               | 1         | 1      | 0.32%   |
| faspeed               | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Kingston SA400S37120G 120GB SSD      | 7         | 2.15%   |
| Toshiba MQ01ABF050 500GB             | 6         | 1.84%   |
| Seagate ST320LT007-9ZV142 320GB      | 6         | 1.84%   |
| Kingston SA400S37240G 240GB SSD      | 6         | 1.84%   |
| Seagate ST1000LM035-1RK172 1TB       | 5         | 1.53%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 1.23%   |
| Toshiba MQ04ABF100 1TB               | 4         | 1.23%   |
| Hitachi HTS545050B9A300 500GB        | 4         | 1.23%   |
| WDC WD10SPZX-21Z10T0 1TB             | 3         | 0.92%   |
| Unknown MMC Card  16GB               | 3         | 0.92%   |
| Seagate ST500LT012-9WS142 500GB      | 3         | 0.92%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 3         | 0.92%   |
| Seagate ST1000LM014-1EJ164 1TB       | 3         | 0.92%   |
| Samsung SSD 860 EVO 500GB            | 3         | 0.92%   |
| Kingston SA400S37480G 480GB SSD      | 3         | 0.92%   |
| Intel SSDPEKNW512G8 512GB            | 3         | 0.92%   |
| Hitachi HTS547564A9E384 640GB        | 3         | 0.92%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 2         | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 0.61%   |
| WDC WD5000BPKT-75PK4T0 500GB         | 2         | 0.61%   |
| WDC WD10SPZX-08Z10 1TB               | 2         | 0.61%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB | 2         | 0.61%   |
| Unknown DA4064  64GB                 | 2         | 0.61%   |
| Transcend TS512GMTS430S 512GB SSD    | 2         | 0.61%   |
| Toshiba MQ01ACF032 320GB             | 2         | 0.61%   |
| Toshiba MQ01ABD100 1TB               | 2         | 0.61%   |
| Toshiba MQ01ABD050 500GB             | 2         | 0.61%   |
| Toshiba MK7559GSXP 752GB             | 2         | 0.61%   |
| Seagate ST9500420AS 500GB            | 2         | 0.61%   |
| Seagate ST9250410AS 250GB            | 2         | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 2         | 0.61%   |
| Seagate ST500LM000-SSHD-8GB          | 2         | 0.61%   |
| Seagate ST2000LM015-2E8174 2TB       | 2         | 0.61%   |
| SanDisk SD6SB2M-512G-1006 512GB SSD  | 2         | 0.61%   |
| Sandisk NVMe SSD Drive 512GB         | 2         | 0.61%   |
| SanDisk DF4064  64GB                 | 2         | 0.61%   |
| Samsung SSD PM830 mSATA 128GB        | 2         | 0.61%   |
| Samsung SSD 860 QVO 1TB              | 2         | 0.61%   |
| Samsung SSD 860 PRO 512GB            | 2         | 0.61%   |
| Samsung SSD 850 EVO 500GB            | 2         | 0.61%   |
| PNY CS900 240GB SSD                  | 2         | 0.61%   |
| Kingston SUV500MS120G 120GB SSD      | 2         | 0.61%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.61%   |
| Fujitsu MHZ2320BH G2 320GB           | 2         | 0.61%   |
| Crucial CT250BX100SSD1 250GB         | 2         | 0.61%   |
| China SSD 120GB                      | 2         | 0.61%   |
| Apacer AS350 512GB SSD               | 2         | 0.61%   |
| WDC WDS250G2X0C-00L350 250GB         | 1         | 0.31%   |
| WDC WDS200T3X0C-00SJG0 2TB           | 1         | 0.31%   |
| WDC WDS120G1G0A-00SS50 120GB SSD     | 1         | 0.31%   |
| WDC WDS100T2G0A-00JH30 1TB SSD       | 1         | 0.31%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.31%   |
| WDC WD7500BPVX-60JC3T0 752GB         | 1         | 0.31%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.31%   |
| WDC WD7500BPVT-75HXZT1 752GB         | 1         | 0.31%   |
| WDC WD7500BPKX-75HPJT0 752GB         | 1         | 0.31%   |
| WDC WD7500BPKT-75PK4T0 752GB         | 1         | 0.31%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 0.31%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 51     | 37.3%   |
| WDC                 | 29        | 34     | 23.02%  |
| Toshiba             | 25        | 31     | 19.84%  |
| Hitachi             | 14        | 15     | 11.11%  |
| HGST                | 5         | 5      | 3.97%   |
| Fujitsu             | 3         | 3      | 2.38%   |
| Samsung Electronics | 2         | 2      | 1.59%   |
| Unknown             | 1         | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 37     | 26.72%  |
| Kingston            | 22        | 27     | 18.97%  |
| SanDisk             | 11        | 15     | 9.48%   |
| Crucial             | 8         | 13     | 6.9%    |
| WDC                 | 6         | 6      | 5.17%   |
| China               | 5         | 6      | 4.31%   |
| A-DATA Technology   | 5         | 5      | 4.31%   |
| Intel               | 4         | 5      | 3.45%   |
| Toshiba             | 3         | 3      | 2.59%   |
| PNY                 | 3         | 3      | 2.59%   |
| Transcend           | 2         | 3      | 1.72%   |
| Intenso             | 2         | 2      | 1.72%   |
| Apacer              | 2         | 3      | 1.72%   |
| Vaseky              | 1         | 1      | 0.86%   |
| SMART               | 1         | 1      | 0.86%   |
| SK Hynix            | 1         | 4      | 0.86%   |
| Seagate             | 1         | 1      | 0.86%   |
| PLEXTOR             | 1         | 1      | 0.86%   |
| Patriot             | 1         | 1      | 0.86%   |
| OCZ                 | 1         | 1      | 0.86%   |
| Netac               | 1         | 1      | 0.86%   |
| Micron Technology   | 1         | 2      | 0.86%   |
| LITEONIT            | 1         | 2      | 0.86%   |
| KingSpec            | 1         | 1      | 0.86%   |
| FORESEE             | 1         | 1      | 0.86%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 121       | 142    | 40.47%  |
| SSD     | 105       | 145    | 35.12%  |
| NVMe    | 57        | 66     | 19.06%  |
| MMC     | 15        | 18     | 5.02%   |
| Unknown | 1         | 1      | 0.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 205       | 280    | 71.93%  |
| NVMe | 57        | 66     | 20%     |
| MMC  | 15        | 18     | 5.26%   |
| SAS  | 8         | 8      | 2.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 153       | 197    | 66.23%  |
| 0.51-1.0   | 67        | 76     | 29%     |
| 1.01-2.0   | 9         | 12     | 3.9%    |
| 3.01-4.0   | 2         | 2      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 84        | 32.31%  |
| 101-250        | 68        | 26.15%  |
| 501-1000       | 41        | 15.77%  |
| 1-20           | 17        | 6.54%   |
| 51-100         | 15        | 5.77%   |
| 1001-2000      | 14        | 5.38%   |
| 21-50          | 10        | 3.85%   |
| 2001-3000      | 6         | 2.31%   |
| More than 3000 | 5         | 1.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 93        | 34.44%  |
| 21-50          | 46        | 17.04%  |
| 101-250        | 43        | 15.93%  |
| 51-100         | 42        | 15.56%  |
| 251-500        | 28        | 10.37%  |
| 501-1000       | 13        | 4.81%   |
| 1001-2000      | 3         | 1.11%   |
| More than 3000 | 1         | 0.37%   |
| 2001-3000      | 1         | 0.37%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT007-9ZV142 320GB   | 4         | 4      | 12.5%   |
| Toshiba MK7559GSXP 752GB          | 2         | 2      | 6.25%   |
| WDC WD7500BPVT-75HXZT1 752GB      | 1         | 1      | 3.13%   |
| WDC WD7500BPKT-75PK4T0 752GB      | 1         | 1      | 3.13%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 3.13%   |
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 2      | 3.13%   |
| WDC WD3200BEVT-60ZCT1 320GB       | 1         | 1      | 3.13%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 3.13%   |
| Vaseky V820/1TB SSD               | 1         | 1      | 3.13%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 3.13%   |
| Toshiba MK5065GSX 500GB           | 1         | 1      | 3.13%   |
| Toshiba MK2555GSX 250GB           | 1         | 1      | 3.13%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 3.13%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 3.13%   |
| Seagate ST9250410AS 250GB         | 1         | 1      | 3.13%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 3.13%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 3.13%   |
| Seagate ST320LT012-9WS14C 320GB   | 1         | 1      | 3.13%   |
| SanDisk SD7SN3Q256G1002 256GB SSD | 1         | 1      | 3.13%   |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 3.13%   |
| OCZ VERTEX450 128GB SSD           | 1         | 1      | 3.13%   |
| Intel SSDSC2KF256H6L 256GB        | 1         | 1      | 3.13%   |
| Hitachi HTS722016K9A300 160GB     | 1         | 1      | 3.13%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 3.13%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 3.13%   |
| Fujitsu MHZ2320BH G1 320GB        | 1         | 1      | 3.13%   |
| China SSD 120GB                   | 1         | 1      | 3.13%   |
| A-DATA Technology SP900 64GB SSD  | 1         | 1      | 3.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 31.25%  |
| WDC                 | 6         | 7      | 18.75%  |
| Toshiba             | 5         | 5      | 15.63%  |
| Hitachi             | 3         | 3      | 9.38%   |
| Vaseky              | 1         | 1      | 3.13%   |
| SanDisk             | 1         | 1      | 3.13%   |
| Samsung Electronics | 1         | 1      | 3.13%   |
| OCZ                 | 1         | 1      | 3.13%   |
| Intel               | 1         | 1      | 3.13%   |
| Fujitsu             | 1         | 1      | 3.13%   |
| China               | 1         | 1      | 3.13%   |
| A-DATA Technology   | 1         | 1      | 3.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 38.46%  |
| WDC                 | 6         | 7      | 23.08%  |
| Toshiba             | 5         | 5      | 19.23%  |
| Hitachi             | 3         | 3      | 11.54%  |
| Samsung Electronics | 1         | 1      | 3.85%   |
| Fujitsu             | 1         | 1      | 3.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 27     | 81.25%  |
| SSD  | 6         | 6      | 18.75%  |

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
| Works    | 140       | 186    | 51.85%  |
| Detected | 98        | 153    | 36.3%   |
| Malfunc  | 32        | 33     | 11.85%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 195       | 69.15%  |
| AMD                              | 28        | 9.93%   |
| Sandisk                          | 13        | 4.61%   |
| Samsung Electronics              | 11        | 3.9%    |
| SK Hynix                         | 9         | 3.19%   |
| Toshiba America Info Systems     | 5         | 1.77%   |
| KIOXIA                           | 4         | 1.42%   |
| Silicon Motion                   | 3         | 1.06%   |
| Silicon Integrated Systems [SiS] | 2         | 0.71%   |
| Phison Electronics               | 2         | 0.71%   |
| Micron/Crucial Technology        | 2         | 0.71%   |
| Micron Technology                | 2         | 0.71%   |
| Kingston Technology Company      | 2         | 0.71%   |
| Union Memory (Shenzhen)          | 1         | 0.35%   |
| Solid State Storage Technology   | 1         | 0.35%   |
| Realtek Semiconductor            | 1         | 0.35%   |
| Nvidia                           | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 9.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 27        | 8.79%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 23        | 7.49%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 17        | 5.54%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 5.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 4.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 3.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 3.26%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 7         | 2.28%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 2.28%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 2.28%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.95%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.95%   |
| Intel SSD 660P Series                                                            | 5         | 1.63%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.63%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.3%    |
| KIOXIA Non-Volatile memory controller                                            | 4         | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.3%    |
| SK Hynix BC511                                                                   | 3         | 0.98%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 3         | 0.98%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.98%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.98%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.98%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 3         | 0.98%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.98%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.65%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.65%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.65%   |
| Sandisk PC SN520 NVMe SSD                                                        | 2         | 0.65%   |
| Samsung NVMe SSD Controller 980                                                  | 2         | 0.65%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                  | 2         | 0.65%   |
| Micron Non-Volatile memory controller                                            | 2         | 0.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 2         | 0.65%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 2         | 0.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 2         | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 2         | 0.65%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.33%   |
| Toshiba America Info Systems NVMe Controller                                     | 1         | 0.33%   |
| Solid State Storage Non-Volatile memory controller                               | 1         | 0.33%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 1         | 0.33%   |
| SK Hynix Non-Volatile memory controller                                          | 1         | 0.33%   |
| SK Hynix Gold P31 SSD                                                            | 1         | 0.33%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 1         | 0.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 1         | 0.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.33%   |
| Realtek RTS5763DL NVMe SSD Controller                                            | 1         | 0.33%   |
| Phison PS5013 E13 NVMe Controller                                                | 1         | 0.33%   |
| Phison E12 NVMe Controller                                                       | 1         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 197       | 67.7%   |
| NVMe | 57        | 19.59%  |
| RAID | 20        | 6.87%   |
| IDE  | 17        | 5.84%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 219       | 86.22%  |
| AMD    | 34        | 13.39%  |
| ARM    | 1         | 0.39%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.97%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.97%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 5         | 1.97%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.57%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 1.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 1.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.57%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 3         | 1.18%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.18%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.18%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 1.18%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 1.18%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 1.18%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.18%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.18%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.18%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1.18%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.18%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.18%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 3         | 1.18%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.18%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.18%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.79%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.79%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.79%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 2         | 0.79%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 2         | 0.79%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.79%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.79%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 2         | 0.79%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.79%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.79%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.79%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.79%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 0.79%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.79%   |
| Intel Core i5-3360M CPU @ 2.80GHz             | 2         | 0.79%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 2         | 0.79%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.79%   |
| Intel Core i5 CPU M 540 @ 2.53GHz             | 2         | 0.79%   |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 2         | 0.79%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.79%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 2         | 0.79%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 2         | 0.79%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 2         | 0.79%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 2         | 0.79%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 2         | 0.79%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 2         | 0.79%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.79%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.79%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 0.79%   |
| AMD A6-6310 APU with AMD Radeon R4 Graphics   | 2         | 0.79%   |
| Intel Xeon CPU E3-1545M v5 @ 2.90GHz          | 1         | 0.39%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 72        | 28.35%  |
| Intel Core i7                  | 67        | 26.38%  |
| Intel Core i3                  | 23        | 9.06%   |
| Intel Core 2 Duo               | 13        | 5.12%   |
| Intel Celeron                  | 12        | 4.72%   |
| Intel Pentium                  | 10        | 3.94%   |
| Other                          | 9         | 3.54%   |
| AMD Ryzen 7                    | 6         | 2.36%   |
| AMD Ryzen 5                    | 5         | 1.97%   |
| AMD A6                         | 4         | 1.57%   |
| Intel Core m3                  | 3         | 1.18%   |
| Intel Atom                     | 3         | 1.18%   |
| AMD A4                         | 3         | 1.18%   |
| Intel Pentium Dual-Core        | 2         | 0.79%   |
| Intel Core M                   | 2         | 0.79%   |
| AMD Ryzen 9                    | 2         | 0.79%   |
| AMD Ryzen 3                    | 2         | 0.79%   |
| AMD A8                         | 2         | 0.79%   |
| Intel Xeon                     | 1         | 0.39%   |
| Intel Pentium Silver           | 1         | 0.39%   |
| Intel Pentium Dual             | 1         | 0.39%   |
| Intel Genuine                  | 1         | 0.39%   |
| Intel Core 2 Extreme           | 1         | 0.39%   |
| Intel Celeron Dual-Core        | 1         | 0.39%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.39%   |
| AMD Ryzen 7 PRO                | 1         | 0.39%   |
| AMD Ryzen 5 PRO                | 1         | 0.39%   |
| AMD Phenom II                  | 1         | 0.39%   |
| AMD E2                         | 1         | 0.39%   |
| AMD E                          | 1         | 0.39%   |
| AMD Athlon X2                  | 1         | 0.39%   |
| AMD Athlon                     | 1         | 0.39%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 147       | 57.87%  |
| 4      | 89        | 35.04%  |
| 6      | 9         | 3.54%   |
| 8      | 7         | 2.76%   |
| 3      | 1         | 0.39%   |
| 1      | 1         | 0.39%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 253       | 99.61%  |
| 2      | 1         | 0.39%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 187       | 73.62%  |
| 1      | 67        | 26.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 254       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 31        | 12.06%  |
| Unknown    | 31        | 12.06%  |
| 0x306a9    | 27        | 10.51%  |
| 0x306d4    | 12        | 4.67%   |
| 0x1067a    | 10        | 3.89%   |
| 0x806ec    | 9         | 3.5%    |
| 0x806e9    | 9         | 3.5%    |
| 0x40651    | 9         | 3.5%    |
| 0x306c3    | 8         | 3.11%   |
| 0x806ea    | 7         | 2.72%   |
| 0x406e3    | 6         | 2.33%   |
| 0x20655    | 6         | 2.33%   |
| 0x20652    | 6         | 2.33%   |
| 0x08108102 | 6         | 2.33%   |
| 0x906ea    | 5         | 1.95%   |
| 0x706e5    | 5         | 1.95%   |
| 0x6fd      | 5         | 1.95%   |
| 0x06006705 | 5         | 1.95%   |
| 0x806c1    | 4         | 1.56%   |
| 0x706a1    | 4         | 1.56%   |
| 0x506e3    | 4         | 1.56%   |
| 0x406c4    | 4         | 1.56%   |
| 0x30678    | 4         | 1.56%   |
| 0x906e9    | 3         | 1.17%   |
| 0x08600106 | 3         | 1.17%   |
| 0x906ed    | 2         | 0.78%   |
| 0x806d1    | 2         | 0.78%   |
| 0x6fa      | 2         | 0.78%   |
| 0x506c9    | 2         | 0.78%   |
| 0x406c3    | 2         | 0.78%   |
| 0x30673    | 2         | 0.78%   |
| 0x106e5    | 2         | 0.78%   |
| 0x10676    | 2         | 0.78%   |
| 0x08108109 | 2         | 0.78%   |
| 0x08101016 | 2         | 0.78%   |
| 0x07030105 | 2         | 0.78%   |
| 0x02000032 | 2         | 0.78%   |
| 0xa0660    | 1         | 0.39%   |
| 0x106ca    | 1         | 0.39%   |
| 0x0a50000c | 1         | 0.39%   |
| 0x0a50000b | 1         | 0.39%   |
| 0x08701013 | 1         | 0.39%   |
| 0x08101007 | 1         | 0.39%   |
| 0x07030104 | 1         | 0.39%   |
| 0x06006704 | 1         | 0.39%   |
| 0x05000119 | 1         | 0.39%   |
| 0x05000029 | 1         | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 42        | 16.54%  |
| SandyBridge     | 35        | 13.78%  |
| IvyBridge       | 29        | 11.42%  |
| Haswell         | 21        | 8.27%   |
| Broadwell       | 15        | 5.91%   |
| Skylake         | 13        | 5.12%   |
| Westmere        | 12        | 4.72%   |
| Silvermont      | 12        | 4.72%   |
| Penryn          | 12        | 4.72%   |
| Zen+            | 8         | 3.15%   |
| IceLake         | 7         | 2.76%   |
| Core            | 7         | 2.76%   |
| Excavator       | 6         | 2.36%   |
| Zen 2           | 4         | 1.57%   |
| TigerLake       | 4         | 1.57%   |
| Puma            | 4         | 1.57%   |
| Goldmont plus   | 4         | 1.57%   |
| Zen 3           | 3         | 1.18%   |
| Zen             | 3         | 1.18%   |
| Nehalem         | 2         | 0.79%   |
| K8 & K10 hybrid | 2         | 0.79%   |
| Goldmont        | 2         | 0.79%   |
| Bobcat          | 2         | 0.79%   |
| Piledriver      | 1         | 0.39%   |
| K10             | 1         | 0.39%   |
| CometLake       | 1         | 0.39%   |
| Bonnell         | 1         | 0.39%   |
| Unknown         | 1         | 0.39%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 199       | 62.78%  |
| Nvidia                           | 64        | 20.19%  |
| AMD                              | 53        | 16.72%  |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 8.92%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 8.62%   |
| Intel HD Graphics 5500                                                                   | 13        | 4%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 3.08%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 3.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 2.77%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.46%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.46%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.46%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.85%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.54%   |
| Intel HD Graphics 530                                                                    | 5         | 1.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.23%   |
| Intel HD Graphics 620                                                                    | 4         | 1.23%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.92%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.92%   |
| Intel HD Graphics 630                                                                    | 3         | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.92%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 3         | 0.92%   |
| AMD Renoir                                                                               | 3         | 0.92%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.92%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.92%   |
| AMD Cezanne                                                                              | 3         | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.62%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.62%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.62%   |
| Nvidia GK104GLM [Quadro K3100M]                                                          | 2         | 0.62%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.62%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.62%   |
| Nvidia GF108GLM [NVS 5200M]                                                              | 2         | 0.62%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.62%   |
| Intel UHD Graphics 615                                                                   | 2         | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.62%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.62%   |
| Intel HD Graphics 5300                                                                   | 2         | 0.62%   |
| Intel HD Graphics 500                                                                    | 2         | 0.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.62%   |
| AMD Lexa [Radeon 540X/550X/630 / RX 640 / E9171 MCM]                                     | 2         | 0.62%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.31%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.31%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 1         | 0.31%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.31%   |
| Nvidia GT218M [NVS 3100M]                                                                | 1         | 0.31%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.31%   |
| Nvidia GT218M [GeForce 310M]                                                             | 1         | 0.31%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.31%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.31%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.31%   |
| Nvidia GM206GLM [Quadro M2200 Mobile]                                                    | 1         | 0.31%   |
| Nvidia GM204GLM [Quadro M3000M]                                                          | 1         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 138       | 54.33%  |
| Intel + Nvidia | 48        | 18.9%   |
| 1 x AMD        | 33        | 12.99%  |
| 1 x Nvidia     | 14        | 5.51%   |
| Intel + AMD    | 13        | 5.12%   |
| 2 x AMD        | 4         | 1.57%   |
| AMD + Nvidia   | 2         | 0.79%   |
| Other          | 1         | 0.39%   |
| 1 x SiS        | 1         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 210       | 82.03%  |
| Proprietary | 36        | 14.06%  |
| Unknown     | 10        | 3.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 173       | 67.84%  |
| 1.01-2.0   | 24        | 9.41%   |
| 0.01-0.5   | 23        | 9.02%   |
| 0.51-1.0   | 17        | 6.67%   |
| 3.01-4.0   | 12        | 4.71%   |
| 2.01-3.0   | 3         | 1.18%   |
| 5.01-6.0   | 2         | 0.78%   |
| 7.01-8.0   | 1         | 0.39%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 58        | 20.49%  |
| LG Display              | 47        | 16.61%  |
| Samsung Electronics     | 41        | 14.49%  |
| Chimei Innolux          | 37        | 13.07%  |
| BOE                     | 22        | 7.77%   |
| Dell                    | 12        | 4.24%   |
| Chi Mei Optoelectronics | 11        | 3.89%   |
| PANDA                   | 6         | 2.12%   |
| Sharp                   | 4         | 1.41%   |
| LG Philips              | 4         | 1.41%   |
| Lenovo                  | 4         | 1.41%   |
| Goldstar                | 4         | 1.41%   |
| Philips                 | 3         | 1.06%   |
| InnoLux Display         | 3         | 1.06%   |
| Hewlett-Packard         | 3         | 1.06%   |
| Apple                   | 3         | 1.06%   |
| Sony                    | 2         | 0.71%   |
| CSO                     | 2         | 0.71%   |
| AOC                     | 2         | 0.71%   |
| Ancor Communications    | 2         | 0.71%   |
| Acer                    | 2         | 0.71%   |
| ___                     | 1         | 0.35%   |
| Vizio                   | 1         | 0.35%   |
| Unknown                 | 1         | 0.35%   |
| Seiko/Epson             | 1         | 0.35%   |
| Optoma                  | 1         | 0.35%   |
| NEC Computers           | 1         | 0.35%   |
| MS_ Nvidia              | 1         | 0.35%   |
| LGD                     | 1         | 0.35%   |
| InfoVision              | 1         | 0.35%   |
| Iiyama                  | 1         | 0.35%   |
| CPT                     | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch     | 6         | 2.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 5         | 1.73%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 1.04%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 1.04%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 3         | 1.04%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 2         | 0.69%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 0.69%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.69%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.69%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.69%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 2         | 0.69%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch          | 2         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 2         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.69%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.69%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.69%   |
| AU Optronics LCD Monitor AUO109E 1600x900 380x210mm 17.1-inch            | 2         | 0.69%   |
| ___ LCD TV ___9000 1360x768                                              | 1         | 0.35%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                      | 1         | 0.35%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.35%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 0.35%   |
| Sony BW8 MS_9001 1600x2560 113x181mm 8.4-inch                            | 1         | 0.35%   |
| Sharp LCD SHP4200 1920x1080 410x230mm 18.5-inch                          | 1         | 0.35%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP148B 3840x2160 294x165mm 13.3-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 0.35%   |
| Seiko/Epson LCD Monitor 1440x900                                         | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM037C 1680x1050 474x296mm 22.0-inch     | 1         | 0.35%   |
| Samsung Electronics SMBX2450L SAM0720 1920x1080 521x293mm 23.5-inch      | 1         | 0.35%   |
| Samsung Electronics SA300/SA350 SAM07D1 1920x1080 477x268mm 21.5-inch    | 1         | 0.35%   |
| Samsung Electronics S23B300 SAM08AE 1680x1050 510x290mm 23.1-inch        | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch    | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4F45 1280x800 331x207mm 15.4-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3441 1366x768 309x174mm 14.0-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch    | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC314B 1680x945 409x230mm 18.5-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3130 1024x600 223x125mm 10.1-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3047 1366x768 277x156mm 12.5-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 340x190mm 15.3-inch    | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch     | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 96        | 36.09%  |
| 1920x1080 (FHD)    | 94        | 35.34%  |
| 1600x900 (HD+)     | 27        | 10.15%  |
| 1280x800 (WXGA)    | 12        | 4.51%   |
| 1440x900 (WXGA+)   | 6         | 2.26%   |
| 2560x1440 (QHD)    | 5         | 1.88%   |
| 1680x1050 (WSXGA+) | 5         | 1.88%   |
| 3840x2160 (4K)     | 4         | 1.5%    |
| 1920x1200 (WUXGA)  | 4         | 1.5%    |
| 3200x1800 (QHD+)   | 2         | 0.75%   |
| 2560x1600          | 2         | 0.75%   |
| 1360x768           | 2         | 0.75%   |
| 3440x1440          | 1         | 0.38%   |
| 2880x1800          | 1         | 0.38%   |
| 2160x1440          | 1         | 0.38%   |
| 1680x945           | 1         | 0.38%   |
| 1600x1200          | 1         | 0.38%   |
| 1400x1050          | 1         | 0.38%   |
| 1024x600           | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 112       | 39.44%  |
| 14      | 36        | 12.68%  |
| 13      | 36        | 12.68%  |
| 17      | 28        | 9.86%   |
| 12      | 11        | 3.87%   |
| 21      | 9         | 3.17%   |
| 23      | 8         | 2.82%   |
| 24      | 6         | 2.11%   |
| 11      | 6         | 2.11%   |
| Unknown | 6         | 2.11%   |
| 27      | 5         | 1.76%   |
| 18      | 5         | 1.76%   |
| 22      | 3         | 1.06%   |
| 10      | 3         | 1.06%   |
| 20      | 2         | 0.7%    |
| 72      | 1         | 0.35%   |
| 49      | 1         | 0.35%   |
| 40      | 1         | 0.35%   |
| 34      | 1         | 0.35%   |
| 29      | 1         | 0.35%   |
| 19      | 1         | 0.35%   |
| 16      | 1         | 0.35%   |
| 8       | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 57.95%  |
| 201-300     | 35        | 12.37%  |
| 351-400     | 34        | 12.01%  |
| 401-500     | 20        | 7.07%   |
| 501-600     | 18        | 6.36%   |
| Unknown     | 6         | 2.12%   |
| 801-900     | 1         | 0.35%   |
| 701-800     | 1         | 0.35%   |
| 601-700     | 1         | 0.35%   |
| 1501-2000   | 1         | 0.35%   |
| 101-200     | 1         | 0.35%   |
| 1001-1500   | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 222       | 86.38%  |
| 16/10   | 25        | 9.73%   |
| 3/2     | 4         | 1.56%   |
| Unknown | 3         | 1.17%   |
| 4/3     | 1         | 0.39%   |
| 21/9    | 1         | 0.39%   |
| 0.62    | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 111       | 39.08%  |
| 81-90          | 58        | 20.42%  |
| 201-250        | 21        | 7.39%   |
| 121-130        | 21        | 7.39%   |
| 71-80          | 14        | 4.93%   |
| 61-70          | 11        | 3.87%   |
| 131-140        | 7         | 2.46%   |
| 51-60          | 6         | 2.11%   |
| Unknown        | 6         | 2.11%   |
| 301-350        | 5         | 1.76%   |
| 151-200        | 5         | 1.76%   |
| 251-300        | 4         | 1.41%   |
| 141-150        | 4         | 1.41%   |
| 41-50          | 3         | 1.06%   |
| More than 1000 | 2         | 0.7%    |
| 351-500        | 2         | 0.7%    |
| 1-40           | 1         | 0.35%   |
| 111-120        | 1         | 0.35%   |
| 501-1000       | 1         | 0.35%   |
| 91-100         | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 103       | 36.79%  |
| 121-160       | 96        | 34.29%  |
| 51-100        | 49        | 17.5%   |
| 161-240       | 16        | 5.71%   |
| More than 240 | 8         | 2.86%   |
| Unknown       | 6         | 2.14%   |
| 1-50          | 2         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 208       | 81.57%  |
| 2     | 37        | 14.51%  |
| 3     | 5         | 1.96%   |
| 0     | 5         | 1.96%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 134       | 33%     |
| Realtek Semiconductor             | 130       | 32.02%  |
| Qualcomm Atheros                  | 70        | 17.24%  |
| Broadcom                          | 27        | 6.65%   |
| Broadcom Limited                  | 11        | 2.71%   |
| Ralink                            | 5         | 1.23%   |
| Marvell Technology Group          | 5         | 1.23%   |
| Sierra Wireless                   | 4         | 0.99%   |
| Ralink Technology                 | 4         | 0.99%   |
| TP-Link                           | 2         | 0.49%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.49%   |
| Ericsson Business Mobile Networks | 2         | 0.49%   |
| Xiaomi                            | 1         | 0.25%   |
| Tenda                             | 1         | 0.25%   |
| Samsung Electronics               | 1         | 0.25%   |
| Qualcomm Atheros Communications   | 1         | 0.25%   |
| NetGear                           | 1         | 0.25%   |
| Lenovo                            | 1         | 0.25%   |
| Hewlett-Packard                   | 1         | 0.25%   |
| FIBOCOM                           | 1         | 0.25%   |
| Dell                              | 1         | 0.25%   |
| Attansic Technology               | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 16.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 6.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 4.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 14        | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 14        | 2.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 2.63%   |
| Intel Wireless 7260                                               | 13        | 2.63%   |
| Intel Wireless 7265                                               | 12        | 2.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 2.22%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 11        | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.82%   |
| Intel Wireless 3165                                               | 9         | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.62%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.62%   |
| Intel Wi-Fi 6 AX200                                               | 8         | 1.62%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 1.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 1.41%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 6         | 1.21%   |
| Intel Centrino Advanced-N 6235                                    | 6         | 1.21%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.01%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.01%   |
| Intel Centrino Ultimate-N 6300                                    | 5         | 1.01%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.01%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.81%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 0.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 0.81%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 4         | 0.81%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 3         | 0.61%   |
| Intel Wireless 8260                                               | 3         | 0.61%   |
| Intel WiFi Link 5100                                              | 3         | 0.61%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 0.61%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.61%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.61%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.61%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter        | 3         | 0.61%   |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 0.61%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.4%    |
| Sierra Wireless EM7345 4G LTE                                     | 2         | 0.4%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 2         | 0.4%    |
| Realtek 802.11ac NIC                                              | 2         | 0.4%    |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.4%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.4%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.4%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.4%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.4%    |
| Intel Wireless-AC 9260                                            | 2         | 0.4%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 2         | 0.4%    |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.4%    |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.4%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.4%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2         | 0.4%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 2         | 0.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 127       | 47.57%  |
| Qualcomm Atheros                | 59        | 22.1%   |
| Realtek Semiconductor           | 30        | 11.24%  |
| Broadcom                        | 20        | 7.49%   |
| Broadcom Limited                | 10        | 3.75%   |
| Ralink                          | 5         | 1.87%   |
| Sierra Wireless                 | 4         | 1.5%    |
| Ralink Technology               | 4         | 1.5%    |
| TP-Link                         | 2         | 0.75%   |
| Tenda                           | 1         | 0.37%   |
| Qualcomm Atheros Communications | 1         | 0.37%   |
| NetGear                         | 1         | 0.37%   |
| Hewlett-Packard                 | 1         | 0.37%   |
| FIBOCOM                         | 1         | 0.37%   |
| Dell                            | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter       | 14        | 5.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                     | 14        | 5.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)   | 13        | 4.87%   |
| Intel Wireless 7260                                              | 13        | 4.87%   |
| Intel Wireless 7265                                              | 12        | 4.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                 | 11        | 4.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter              | 11        | 4.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter       | 9         | 3.37%   |
| Intel Wireless 3165                                              | 9         | 3.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter         | 8         | 3%      |
| Intel Wireless 8265 / 8275                                       | 8         | 3%      |
| Intel Wi-Fi 6 AX200                                              | 8         | 3%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                  | 7         | 2.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                     | 6         | 2.25%   |
| Intel Centrino Advanced-N 6235                                   | 6         | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter       | 5         | 1.87%   |
| Intel Centrino Ultimate-N 6300                                   | 5         | 1.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                  | 4         | 1.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                  | 4         | 1.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                  | 4         | 1.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                | 4         | 1.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                  | 4         | 1.5%    |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                        | 4         | 1.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)   | 3         | 1.12%   |
| Intel Wireless 8260                                              | 3         | 1.12%   |
| Intel WiFi Link 5100                                             | 3         | 1.12%   |
| Intel Wi-Fi 6 AX201                                              | 3         | 1.12%   |
| Intel Centrino Advanced-N 6200                                   | 3         | 1.12%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter       | 3         | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                    | 3         | 1.12%   |
| Sierra Wireless EM7345 4G LTE                                    | 2         | 0.75%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter         | 2         | 0.75%   |
| Realtek 802.11ac NIC                                             | 2         | 0.75%   |
| Ralink RT5370 Wireless Adapter                                   | 2         | 0.75%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                        | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                 | 2         | 0.75%   |
| Intel Wireless-AC 9260                                           | 2         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                   | 2         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection            | 2         | 0.75%   |
| Intel Gemini Lake PCH CNVi WiFi                                  | 2         | 0.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                 | 2         | 0.75%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                    | 2         | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                         | 2         | 0.75%   |
| Broadcom Limited BCM43142 802.11b/g/n                            | 2         | 0.75%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                      | 1         | 0.37%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                            | 1         | 0.37%   |
| Tenda U12                                                        | 1         | 0.37%   |
| Sierra Wireless MC8305 Modem                                     | 1         | 0.37%   |
| Sierra Wireless EM7455                                           | 1         | 0.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter         | 1         | 0.37%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter          | 1         | 0.37%   |
| Realtek RTL8723DE Wireless Network Adapter                       | 1         | 0.37%   |
| Realtek RTL8191SEvB Wireless LAN Controller                      | 1         | 0.37%   |
| Realtek RTL8188EE Wireless Network Adapter                       | 1         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                       | 1         | 0.37%   |
| Realtek RTL8187B Wireless Adapter                                | 1         | 0.37%   |
| Ralink RT5572 Wireless Adapter                                   | 1         | 0.37%   |
| Ralink MT7601U Wireless Adapter                                  | 1         | 0.37%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip] | 1         | 0.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                        | 1         | 0.37%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 124       | 55.36%  |
| Intel                            | 62        | 27.68%  |
| Qualcomm Atheros                 | 16        | 7.14%   |
| Broadcom                         | 9         | 4.02%   |
| Marvell Technology Group         | 5         | 2.23%   |
| Silicon Integrated Systems [SiS] | 2         | 0.89%   |
| Broadcom Limited                 | 2         | 0.89%   |
| Xiaomi                           | 1         | 0.45%   |
| Samsung Electronics              | 1         | 0.45%   |
| Lenovo                           | 1         | 0.45%   |
| Attansic Technology              | 1         | 0.45%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 83        | 36.73%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 14.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 21        | 9.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.98%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 3.54%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.21%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 2.21%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.21%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.33%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.33%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.88%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.88%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.88%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.88%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.88%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.44%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.44%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.44%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.44%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.44%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.44%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.44%   |
| Intel Ethernet Connection (7) I219-V                              | 1         | 0.44%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.44%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.44%   |
| Intel Ethernet Connection (14) I219-LM                            | 1         | 0.44%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.44%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.44%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.44%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.44%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 1         | 0.44%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 1         | 0.44%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.44%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.44%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.44%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 1         | 0.44%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.44%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 249       | 52.75%  |
| Ethernet | 221       | 46.82%  |
| Modem    | 2         | 0.42%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 227       | 62.88%  |
| Ethernet | 133       | 36.84%  |
| Modem    | 1         | 0.28%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 204       | 80%     |
| 1     | 48        | 18.82%  |
| 0     | 2         | 0.78%   |
| 3     | 1         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 222       | 87.06%  |
| Yes  | 33        | 12.94%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 46.94%  |
| Qualcomm Atheros Communications | 27        | 13.78%  |
| Realtek Semiconductor           | 18        | 9.18%   |
| Broadcom                        | 18        | 9.18%   |
| Dell                            | 10        | 5.1%    |
| Lite-On Technology              | 9         | 4.59%   |
| IMC Networks                    | 9         | 4.59%   |
| Foxconn / Hon Hai               | 3         | 1.53%   |
| Cambridge Silicon Radio         | 3         | 1.53%   |
| Ralink Technology               | 2         | 1.02%   |
| ASUSTek Computer                | 2         | 1.02%   |
| Ralink                          | 1         | 0.51%   |
| Foxconn International           | 1         | 0.51%   |
| Apple                           | 1         | 0.51%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 49        | 25%     |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 7.14%   |
| Realtek Bluetooth Radio                             | 10        | 5.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 4.59%   |
| Intel AX201 Bluetooth                               | 8         | 4.08%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 3.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 3.57%   |
| Intel AX200 Bluetooth                               | 7         | 3.57%   |
| IMC Networks Bluetooth Device                       | 7         | 3.57%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 3.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 3.06%   |
| Dell DW375 Bluetooth Module                         | 6         | 3.06%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 2.04%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 2.04%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.53%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.53%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.53%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.53%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.53%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.53%   |
| Realtek RTL8723B Bluetooth                          | 2         | 1.02%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 1.02%   |
| Lite-On Bluetooth Device                            | 2         | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.02%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.02%   |
| Intel Bluetooth Device                              | 2         | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.02%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 2         | 1.02%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.02%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.51%   |
| Ralink CSR BS8510                                   | 1         | 0.51%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.51%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.51%   |
| IMC Networks BCM20702A0                             | 1         | 0.51%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.51%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.51%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.51%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.51%   |
| Broadcom HP Portable Valentine                      | 1         | 0.51%   |
| Broadcom BCM20702A0                                 | 1         | 0.51%   |
| Broadcom BCM2045 Bluetooth                          | 1         | 0.51%   |
| ASUS BT-270 Bluetooth Adapter                       | 1         | 0.51%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.51%   |
| Apple Bluetooth HCI                                 | 1         | 0.51%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 213       | 68.05%  |
| AMD                                            | 41        | 13.1%   |
| Nvidia                                         | 39        | 12.46%  |
| Realtek Semiconductor                          | 3         | 0.96%   |
| Silicon Integrated Systems [SiS]               | 2         | 0.64%   |
| Lenovo                                         | 2         | 0.64%   |
| Sony                                           | 1         | 0.32%   |
| Siemens Information and Communication Products | 1         | 0.32%   |
| Plantronics                                    | 1         | 0.32%   |
| Meizu                                          | 1         | 0.32%   |
| Logitech                                       | 1         | 0.32%   |
| Kingston Technology                            | 1         | 0.32%   |
| GN Netcom                                      | 1         | 0.32%   |
| Generalplus Technology                         | 1         | 0.32%   |
| FiiO Electronics Technology                    | 1         | 0.32%   |
| Corsair                                        | 1         | 0.32%   |
| Conexant Systems                               | 1         | 0.32%   |
| CalDigit                                       | 1         | 0.32%   |
| C-Media Electronics                            | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 8.68%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 8.16%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 6.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 4.47%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 3.95%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 3.95%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 3.68%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 2.89%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 2.63%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 2.37%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 9         | 2.37%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.58%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.58%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.32%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.32%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.05%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.05%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.05%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.05%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.79%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.79%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.79%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.79%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.53%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.53%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 2         | 0.53%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.53%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 2         | 0.53%   |
| Nvidia Audio device                                                                               | 2         | 0.53%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 2         | 0.53%   |
| AMD Wrestler HDMI Audio                                                                           | 2         | 0.53%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.53%   |
| AMD RV620 HDMI Audio [Radeon HD 3450/3470/3550/3570]                                              | 2         | 0.53%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.53%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 1         | 0.26%   |
| Siemens Information and Communication Products optiPoint 500                                      | 1         | 0.26%   |
| Plantronics C320-M                                                                                | 1         | 0.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.26%   |
| Nvidia stereo controller                                                                          | 1         | 0.26%   |
| Nvidia MCP79 High Definition Audio                                                                | 1         | 0.26%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.26%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.26%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 1         | 0.26%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 1         | 0.26%   |
| Meizu HiFi DAC Headphone Amplifier                                                                | 1         | 0.26%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 56        | 25.34%  |
| SK Hynix                                         | 41        | 18.55%  |
| Micron Technology                                | 29        | 13.12%  |
| Kingston                                         | 20        | 9.05%   |
| Unknown                                          | 16        | 7.24%   |
| Crucial                                          | 13        | 5.88%   |
| Elpida                                           | 8         | 3.62%   |
| Ramaxel Technology                               | 6         | 2.71%   |
| Nanya Technology                                 | 6         | 2.71%   |
| Smart                                            | 5         | 2.26%   |
| A-DATA Technology                                | 3         | 1.36%   |
| Unknown (ABCD)                                   | 2         | 0.9%    |
| Teikon                                           | 2         | 0.9%    |
| Patriot                                          | 2         | 0.9%    |
| GOODRAM                                          | 2         | 0.9%    |
| Corsair                                          | 2         | 0.9%    |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.45%   |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.45%   |
| Team                                             | 1         | 0.45%   |
| Qimonda                                          | 1         | 0.45%   |
| Netlist                                          | 1         | 0.45%   |
| G.Skill                                          | 1         | 0.45%   |
| ASint Technology                                 | 1         | 0.45%   |
| Apacer                                           | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s                              | 6         | 2.54%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                                | 5         | 2.12%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s                                 | 5         | 2.12%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                                 | 4         | 1.69%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s                              | 3         | 1.27%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s                              | 3         | 1.27%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                                 | 3         | 1.27%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s                               | 3         | 1.27%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                                        | 2         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                                 | 2         | 0.85%   |
| Unknown RAM Module 2048MB SODIMM DRAM                                                 | 2         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s                   | 2         | 0.85%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s                              | 2         | 0.85%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                                | 2         | 0.85%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s                             | 2         | 0.85%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s                             | 2         | 0.85%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                                | 2         | 0.85%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s                             | 2         | 0.85%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8192MB SODIMM DDR4 3200MT/s                             | 2         | 0.85%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                                 | 2         | 0.85%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s                              | 2         | 0.85%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s                              | 2         | 0.85%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s                                 | 2         | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s                              | 2         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                                 | 2         | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                                 | 2         | 0.85%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s                           | 2         | 0.85%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s                              | 2         | 0.85%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s                              | 2         | 0.85%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                                 | 2         | 0.85%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                                 | 2         | 0.85%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s                         | 2         | 0.85%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s                                 | 2         | 0.85%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                                 | 2         | 0.85%   |
| Crucial RAM CT51264BF160BJ.M8F 4GB SODIMM DDR3 1600MT/s                               | 2         | 0.85%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s                            | 2         | 0.85%   |
| Corsair RAM CMSO4GX3M1A1333C9 4GB SODIMM DDR3 1334MT/s                                | 2         | 0.85%   |
| A-DATA RAM AO1P26KC8T1-BXPS 8GB SODIMM DDR4 2667MT/s                                  | 2         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM LPDDR3 1600MT/s                                      | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1334MT/s                                        | 1         | 0.42%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                                        | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM LPDDR4 2400MT/s                                      | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                                        | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR3                                                 | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                                         | 1         | 0.42%   |
| Unknown RAM Module 2048MB SODIMM 667MT/s                                              | 1         | 0.42%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2400MT/s                                       | 1         | 0.42%   |
| Unknown RAM Module 1536MB SODIMM LPDDR4 2133MT/s                                      | 1         | 0.42%   |
| Unknown RAM Module 1024MB SODIMM DRAM                                                 | 1         | 0.42%   |
| Unknown (0x4D342037305435363633515A332D43463720) RAM Module 2048MB SODIMM DDR 800MT/s | 1         | 0.42%   |
| Unknown (0x36345431323830323045444C322E35433220) RAM Module 1024MB SODIMM DDR 800MT/s | 1         | 0.42%   |
| Teikon RAM TMT251S6FR8C-H9HC 4GB SODIMM DDR3 1333MT/s                                 | 1         | 0.42%   |
| Teikon RAM TML251S6EFR8A-PBHC 4GB SODIMM DDR3 1600MT/s                                | 1         | 0.42%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s                                 | 1         | 0.42%   |
| Smart RAM SH564568FH8NZPHSCR 2048MB SODIMM DDR3 1333MT/s                              | 1         | 0.42%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s                                 | 1         | 0.42%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s                                 | 1         | 0.42%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s                                 | 1         | 0.42%   |
| SK Hynix RAM Module 2048MB SODIMM DDR3 1066MT/s                                       | 1         | 0.42%   |
| SK Hynix RAM Module 2048MB DIMM DDR3 1066MT/s                                         | 1         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 95        | 50.8%   |
| DDR4    | 62        | 33.16%  |
| LPDDR4  | 7         | 3.74%   |
| LPDDR3  | 7         | 3.74%   |
| SDRAM   | 6         | 3.21%   |
| DDR2    | 6         | 3.21%   |
| DRAM    | 2         | 1.07%   |
| DDR     | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 171       | 91.94%  |
| Row Of Chips | 11        | 5.91%   |
| Chip         | 3         | 1.61%   |
| DIMM         | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 84        | 40.78%  |
| 8192  | 58        | 28.16%  |
| 2048  | 38        | 18.45%  |
| 16384 | 16        | 7.77%   |
| 32768 | 5         | 2.43%   |
| 1024  | 4         | 1.94%   |
| 1536  | 1         | 0.49%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 61        | 29.47%  |
| 2667    | 37        | 17.87%  |
| 1334    | 22        | 10.63%  |
| 3200    | 17        | 8.21%   |
| 1333    | 14        | 6.76%   |
| 2400    | 11        | 5.31%   |
| 2133    | 10        | 4.83%   |
| 3266    | 6         | 2.9%    |
| 4199    | 5         | 2.42%   |
| Unknown | 5         | 2.42%   |
| 1067    | 4         | 1.93%   |
| 667     | 4         | 1.93%   |
| 1066    | 3         | 1.45%   |
| 800     | 3         | 1.45%   |
| 4267    | 1         | 0.48%   |
| 2048    | 1         | 0.48%   |
| 1867    | 1         | 0.48%   |
| 975     | 1         | 0.48%   |
| 533     | 1         | 0.48%   |

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
| Chicony Electronics                    | 69        | 30.4%   |
| Acer                                   | 24        | 10.57%  |
| Microdia                               | 22        | 9.69%   |
| Sunplus Innovation Technology          | 17        | 7.49%   |
| IMC Networks                           | 14        | 6.17%   |
| Realtek Semiconductor                  | 11        | 4.85%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.96%   |
| Ricoh                                  | 8         | 3.52%   |
| Quanta                                 | 8         | 3.52%   |
| Suyin                                  | 7         | 3.08%   |
| Silicon Motion                         | 6         | 2.64%   |
| Lite-On Technology                     | 5         | 2.2%    |
| Syntek                                 | 4         | 1.76%   |
| Logitech                               | 4         | 1.76%   |
| Apple                                  | 4         | 1.76%   |
| Alcor Micro                            | 2         | 0.88%   |
| Y Media                                | 1         | 0.44%   |
| Samsung Electronics                    | 1         | 0.44%   |
| Ruision                                | 1         | 0.44%   |
| Primax Electronics                     | 1         | 0.44%   |
| Microsoft                              | 1         | 0.44%   |
| Luxvisions Innotech Limited            | 1         | 0.44%   |
| Lenovo                                 | 1         | 0.44%   |
| Importek                               | 1         | 0.44%   |
| Generalplus Technology                 | 1         | 0.44%   |
| DJKANA1BIFZTDM                         | 1         | 0.44%   |
| DigiTech                               | 1         | 0.44%   |
| Cubeternet                             | 1         | 0.44%   |
| Aveo Technology                        | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 18        | 7.89%   |
| Sunplus Integrated_Webcam_HD                     | 8         | 3.51%   |
| Chicony USB2.0 VGA UVC WebCam                    | 7         | 3.07%   |
| Acer Integrated Camera                           | 7         | 3.07%   |
| Microdia Laptop_Integrated_Webcam_HD             | 6         | 2.63%   |
| Microdia Integrated_Webcam_HD                    | 5         | 2.19%   |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 2.19%   |
| Acer BisonCam, NB Pro                            | 5         | 2.19%   |
| Ricoh HD Webcam                                  | 4         | 1.75%   |
| Chicony HD WebCam                                | 4         | 1.75%   |
| Acer Lenovo EasyCamera                           | 4         | 1.75%   |
| Suyin HP TrueVision HD Integrated Webcam         | 3         | 1.32%   |
| Sunplus Laptop_Integrated_Webcam_FHD             | 3         | 1.32%   |
| Realtek Integrated_Webcam_HD                     | 3         | 1.32%   |
| Quanta HD User Facing                            | 3         | 1.32%   |
| Microdia Integrated Webcam                       | 3         | 1.32%   |
| Lite-On HP HD Camera                             | 3         | 1.32%   |
| Chicony Integrated Camera (1280x720@30)          | 3         | 1.32%   |
| Chicony HP Wide Vision HD Camera                 | 3         | 1.32%   |
| Chicony HP HD Webcam                             | 3         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 3         | 1.32%   |
| Syntek EasyCamera                                | 2         | 0.88%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 2         | 0.88%   |
| Silicon Motion WebCam SC-13HDL11939N             | 2         | 0.88%   |
| Silicon Motion 300k Pixel Camera                 | 2         | 0.88%   |
| Ricoh Sony Visual Communication Camera           | 2         | 0.88%   |
| Ricoh Laptop_Integrated_Webcam_FHD               | 2         | 0.88%   |
| Realtek USB Camera                               | 2         | 0.88%   |
| Realtek Lenovo EasyCamera                        | 2         | 0.88%   |
| Quanta VGA WebCam                                | 2         | 0.88%   |
| Quanta Laptop_Integrated_Webcam_2HDM             | 2         | 0.88%   |
| Microdia Laptop_Integrated_Webcam_2M             | 2         | 0.88%   |
| Microdia Dell Integrated HD Webcam               | 2         | 0.88%   |
| IMC Networks UVC VGA Webcam                      | 2         | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.88%   |
| Chicony USB2.0 UVC WebCam                        | 2         | 0.88%   |
| Chicony Lenovo Integrated Camera (0.3MP)         | 2         | 0.88%   |
| Chicony HP Webcam-101                            | 2         | 0.88%   |
| Chicony HP HD Webcam [Fixed]                     | 2         | 0.88%   |
| Chicony HD WebCam (Acer)                         | 2         | 0.88%   |
| Chicony CNF9055 Toshiba Webcam                   | 2         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) Webcam    | 2         | 0.88%   |
| Apple iPhone 5/5C/5S/6/SE                        | 2         | 0.88%   |
| Acer Lenovo Integrated Webcam                    | 2         | 0.88%   |
| Y Media USB Camera                               | 1         | 0.44%   |
| Syntek USB Video Device                          | 1         | 0.44%   |
| Syntek Integrated Camera                         | 1         | 0.44%   |
| Suyin Sony Visual Communication Camera           | 1         | 0.44%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.44%   |
| Sunplus Laptop_Integrated_Webcam_1.3M            | 1         | 0.44%   |
| Sunplus Integrated_Webcam_FHD                    | 1         | 0.44%   |
| Sunplus HP Universal Camera                      | 1         | 0.44%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.44%   |
| Sunplus HD WebCam                                | 1         | 0.44%   |
| Sunplus Dell Integrated Webcam                   | 1         | 0.44%   |
| Silicon Motion WebCam SCB-1100N                  | 1         | 0.44%   |
| Silicon Motion WebCam SC-10HDP12631N             | 1         | 0.44%   |
| Samsung Galaxy series, misc. (MTP mode)          | 1         | 0.44%   |
| Ruision UVC Camera                               | 1         | 0.44%   |
| Realtek USB2.0 HD UVC WebCam                     | 1         | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 56.1%   |
| Synaptics                  | 9         | 21.95%  |
| Upek                       | 3         | 7.32%   |
| Elan Microelectronics      | 3         | 7.32%   |
| Shenzhen Goodix Technology | 2         | 4.88%   |
| Focal-systems.Corp         | 1         | 2.44%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 4         | 9.76%   |
| Validity Sensors VFS491                                    | 4         | 9.76%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 9.76%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 7.32%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 3         | 7.32%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 4.88%   |
| Validity Sensors Fingerprint scanner                       | 2         | 4.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 4.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.88%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.88%   |
| Elan ELAN:Fingerprint                                      | 2         | 4.88%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.44%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.44%   |
| Validity Sensors Synaptics WBDI                            | 1         | 2.44%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.44%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 2.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.44%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 2.44%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.44%   |
| Unknown                                                    | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 60%     |
| Alcor Micro           | 6         | 17.14%  |
| Upek                  | 2         | 5.71%   |
| O2 Micro              | 2         | 5.71%   |
| Lenovo                | 2         | 5.71%   |
| Gemalto (was Gemplus) | 1         | 2.86%   |
| Advanced Card Systems | 1         | 2.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 20%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 6         | 17.14%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.71%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.71%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.71%   |
| Broadcom 5880                                                                | 2         | 5.71%   |
| Broadcom 58200                                                               | 2         | 5.71%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.86%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 158       | 61.24%  |
| 1     | 80        | 31.01%  |
| 2     | 17        | 6.59%   |
| 8     | 2         | 0.78%   |
| 3     | 1         | 0.39%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 31.78%  |
| Chipcard                 | 33        | 25.58%  |
| Graphics card            | 24        | 18.6%   |
| Storage                  | 8         | 6.2%    |
| Net/wireless             | 7         | 5.43%   |
| Multimedia controller    | 3         | 2.33%   |
| Camera                   | 3         | 2.33%   |
| Bluetooth                | 3         | 2.33%   |
| Sound                    | 2         | 1.55%   |
| Communication controller | 2         | 1.55%   |
| Network                  | 1         | 0.78%   |
| Firewire controller      | 1         | 0.78%   |
| Card reader              | 1         | 0.78%   |

