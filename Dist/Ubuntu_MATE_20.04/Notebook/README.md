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

Total: 370

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 15                          | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Dell          | Precision 7520              | [b83fea6b96](https://linux-hardware.org/?probe=b83fea6b96) | Sep 14, 2022 |
| ASUSTek       | T100TA                      | [fb4d9c8521](https://linux-hardware.org/?probe=fb4d9c8521) | Sep 02, 2022 |
| Lenovo        | IdeaPad S410p 20296         | [dac943f23a](https://linux-hardware.org/?probe=dac943f23a) | Sep 01, 2022 |
| HP            | Pavilion dv5                | [dd2f0b859b](https://linux-hardware.org/?probe=dd2f0b859b) | Aug 24, 2022 |
| HP            | ProBook 455 G7              | [c563966e9c](https://linux-hardware.org/?probe=c563966e9c) | Aug 06, 2022 |
| Google        | Swanky                      | [f54bdd7887](https://linux-hardware.org/?probe=f54bdd7887) | Aug 04, 2022 |
| Google        | Swanky                      | [daac706167](https://linux-hardware.org/?probe=daac706167) | Aug 02, 2022 |
| HP            | Pavilion g6                 | [b48c146eff](https://linux-hardware.org/?probe=b48c146eff) | Aug 01, 2022 |
| Acer          | Aspire 5050                 | [59d8bb1e10](https://linux-hardware.org/?probe=59d8bb1e10) | Jul 26, 2022 |
| Acer          | Aspire 5050                 | [a8bcc56e78](https://linux-hardware.org/?probe=a8bcc56e78) | Jul 26, 2022 |
| HP            | EliteBook 8570p             | [f4f889fb4e](https://linux-hardware.org/?probe=f4f889fb4e) | Jul 20, 2022 |
| Dell          | Latitude XT                 | [9d9deeace5](https://linux-hardware.org/?probe=9d9deeace5) | Jul 10, 2022 |
| Dell          | Latitude XT                 | [b0a096fb7d](https://linux-hardware.org/?probe=b0a096fb7d) | Jul 10, 2022 |
| MicroByte     | ezbook                      | [0f08faf963](https://linux-hardware.org/?probe=0f08faf963) | Jul 08, 2022 |
| Dell          | XPS 17 9710                 | [f37581d70e](https://linux-hardware.org/?probe=f37581d70e) | Jun 26, 2022 |
| Dell          | XPS 13 9360                 | [73746e5672](https://linux-hardware.org/?probe=73746e5672) | Jun 03, 2022 |
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


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 24        | 7.79%   |
| 5.4.0-52-generic  | 17        | 5.52%   |
| 5.4.0-47-generic  | 10        | 3.25%   |
| 5.4.0-40-generic  | 10        | 3.25%   |
| 5.4.0-58-generic  | 9         | 2.92%   |
| 5.8.0-50-generic  | 8         | 2.6%    |
| 5.4.0-48-generic  | 8         | 2.6%    |
| 5.4.0-31-generic  | 8         | 2.6%    |
| 5.4.0-65-generic  | 7         | 2.27%   |
| 5.4.0-26-generic  | 7         | 2.27%   |
| 5.11.0-40-generic | 7         | 2.27%   |
| 5.4.0-56-generic  | 6         | 1.95%   |
| 5.4.0-54-generic  | 6         | 1.95%   |
| 5.4.0-45-generic  | 6         | 1.95%   |
| 5.11.0-38-generic | 6         | 1.95%   |
| 5.8.0-59-generic  | 5         | 1.62%   |
| 5.8.0-48-generic  | 5         | 1.62%   |
| 5.8.0-43-generic  | 5         | 1.62%   |
| 5.4.0-81-generic  | 5         | 1.62%   |
| 5.4.0-37-generic  | 5         | 1.62%   |
| 5.4.0-29-generic  | 5         | 1.62%   |
| 5.13.0-41-generic | 5         | 1.62%   |
| 5.11.0-37-generic | 5         | 1.62%   |
| 5.8.0-53-generic  | 4         | 1.3%    |
| 5.4.0-91-generic  | 4         | 1.3%    |
| 5.4.0-89-generic  | 4         | 1.3%    |
| 5.4.0-51-generic  | 4         | 1.3%    |
| 5.13.0-39-generic | 4         | 1.3%    |
| 5.13.0-30-generic | 4         | 1.3%    |
| 5.4.0-90-generic  | 3         | 0.97%   |
| 5.4.0-74-generic  | 3         | 0.97%   |
| 5.4.0-73-generic  | 3         | 0.97%   |
| 5.4.0-39-generic  | 3         | 0.97%   |
| 5.4.0-33-generic  | 3         | 0.97%   |
| 5.4.0-28-generic  | 3         | 0.97%   |
| 5.15.0-41-generic | 3         | 0.97%   |
| 5.11.0-43-generic | 3         | 0.97%   |
| 5.11.0-41-generic | 3         | 0.97%   |
| 5.8.0-63-generic  | 2         | 0.65%   |
| 5.8.0-45-generic  | 2         | 0.65%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 177       | 62.54%  |
| 5.8.0   | 33        | 11.66%  |
| 5.11.0  | 30        | 10.6%   |
| 5.13.0  | 26        | 9.19%   |
| 5.15.0  | 7         | 2.47%   |
| 5.14.0  | 3         | 1.06%   |
| 5.3.0   | 2         | 0.71%   |
| 5.9.3   | 1         | 0.35%   |
| 5.8.17  | 1         | 0.35%   |
| 5.15.6  | 1         | 0.35%   |
| 5.15.34 | 1         | 0.35%   |
| 5.15.27 | 1         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 177       | 62.54%  |
| 5.8     | 34        | 12.01%  |
| 5.11    | 30        | 10.6%   |
| 5.13    | 26        | 9.19%   |
| 5.15    | 10        | 3.53%   |
| 5.14    | 3         | 1.06%   |
| 5.3     | 2         | 0.71%   |
| 5.9     | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 279       | 99.64%  |
| aarch64 | 1         | 0.36%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 273       | 97.5%   |
| GNOME      | 2         | 0.71%   |
| Cinnamon   | 2         | 0.71%   |
| X-Cinnamon | 1         | 0.36%   |
| KDE5       | 1         | 0.36%   |
| i3         | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 274       | 97.86%  |
| Wayland | 3         | 1.07%   |
| Tty     | 3         | 1.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| TDM     | 99        | 34.62%  |
| LightDM | 93        | 32.52%  |
| Unknown | 75        | 26.22%  |
| GDM     | 15        | 5.24%   |
| GDM3    | 3         | 1.05%   |
| SDDM    | 1         | 0.35%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 103       | 36.65%  |
| fr_FR   | 29        | 10.32%  |
| pt_BR   | 28        | 9.96%   |
| en_GB   | 17        | 6.05%   |
| de_DE   | 15        | 5.34%   |
| es_ES   | 12        | 4.27%   |
| it_IT   | 11        | 3.91%   |
| ru_RU   | 8         | 2.85%   |
| ru_UA   | 6         | 2.14%   |
| C       | 6         | 2.14%   |
| pl_PL   | 5         | 1.78%   |
| es_AR   | 4         | 1.42%   |
| en_PH   | 3         | 1.07%   |
| en_IN   | 3         | 1.07%   |
| de_CH   | 3         | 1.07%   |
| nl_NL   | 2         | 0.71%   |
| en_CA   | 2         | 0.71%   |
| ca_ES   | 2         | 0.71%   |
| zh_TW   | 1         | 0.36%   |
| zh_CN   | 1         | 0.36%   |
| uk_UA   | 1         | 0.36%   |
| sv_SE   | 1         | 0.36%   |
| sk_SK   | 1         | 0.36%   |
| nl_BE   | 1         | 0.36%   |
| hu_HU   | 1         | 0.36%   |
| fr_CH   | 1         | 0.36%   |
| fr_CA   | 1         | 0.36%   |
| fr_BE   | 1         | 0.36%   |
| fi_FI   | 1         | 0.36%   |
| et_EE   | 1         | 0.36%   |
| es_UY   | 1         | 0.36%   |
| es_PR   | 1         | 0.36%   |
| es_PE   | 1         | 0.36%   |
| es_MX   | 1         | 0.36%   |
| en_NZ   | 1         | 0.36%   |
| en_IE   | 1         | 0.36%   |
| en_AU   | 1         | 0.36%   |
| da_DK   | 1         | 0.36%   |
| cs_CZ   | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 145       | 51.79%  |
| BIOS | 135       | 48.21%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 263       | 93.26%  |
| Overlay | 10        | 3.55%   |
| Btrfs   | 3         | 1.06%   |
| Zfs     | 2         | 0.71%   |
| Xfs     | 2         | 0.71%   |
| Ext3    | 2         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 110       | 39.01%  |
| Unknown | 96        | 34.04%  |
| MBR     | 76        | 26.95%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 251       | 88.07%  |
| Yes       | 34        | 11.93%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 196       | 69.75%  |
| Yes       | 85        | 30.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 60        | 21.43%  |
| Hewlett-Packard        | 58        | 20.71%  |
| Dell                   | 57        | 20.36%  |
| ASUSTek Computer       | 26        | 9.29%   |
| Acer                   | 19        | 6.79%   |
| Toshiba                | 9         | 3.21%   |
| Samsung Electronics    | 7         | 2.5%    |
| MSI                    | 7         | 2.5%    |
| Sony                   | 3         | 1.07%   |
| Medion                 | 3         | 1.07%   |
| Positivo               | 2         | 0.71%   |
| Packard Bell           | 2         | 0.71%   |
| Notebook               | 2         | 0.71%   |
| GPD                    | 2         | 0.71%   |
| Fujitsu                | 2         | 0.71%   |
| Avell High Performance | 2         | 0.71%   |
| Apple                  | 2         | 0.71%   |
| Unknown                | 2         | 0.71%   |
| Wortmann AG            | 1         | 0.36%   |
| TUXEDO                 | 1         | 0.36%   |
| Teclast                | 1         | 0.36%   |
| System76               | 1         | 0.36%   |
| Star Labs              | 1         | 0.36%   |
| Polaroid               | 1         | 0.36%   |
| Pine Microsystems      | 1         | 0.36%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.36%   |
| MicroByte              | 1         | 0.36%   |
| Intel                  | 1         | 0.36%   |
| Google                 | 1         | 0.36%   |
| Cube                   | 1         | 0.36%   |
| Clevo                  | 1         | 0.36%   |
| Chuwi                  | 1         | 0.36%   |
| AMI                    | 1         | 0.36%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Latitude E6420                        | 5         | 1.79%   |
| HP Pavilion dv7                            | 4         | 1.43%   |
| HP Pavilion g6                             | 3         | 1.07%   |
| HP Notebook                                | 3         | 1.07%   |
| Dell Precision M4800                       | 3         | 1.07%   |
| Dell Latitude E6410                        | 3         | 1.07%   |
| Unknown                                    | 3         | 1.07%   |
| Toshiba Satellite C660                     | 2         | 0.71%   |
| HP EliteBook 8470p                         | 2         | 0.71%   |
| HP 15                                      | 2         | 0.71%   |
| Dell XPS 13 9360                           | 2         | 0.71%   |
| Dell Vostro 3350                           | 2         | 0.71%   |
| Dell Precision 7520                        | 2         | 0.71%   |
| Dell Latitude E6430                        | 2         | 0.71%   |
| Dell Inspiron 3421                         | 2         | 0.71%   |
| ASUS ZenBook UX431DA_UM431DA               | 2         | 0.71%   |
| ASUS X553MA                                | 2         | 0.71%   |
| ASUS X541SA                                | 2         | 0.71%   |
| Wortmann AG TERRA_MOBILE_1749              | 1         | 0.36%   |
| TUXEDO InfinityBook Pro 14 Gen6            | 1         | 0.36%   |
| Toshiba Satellite Pro L500                 | 1         | 0.36%   |
| Toshiba Satellite Pro C660                 | 1         | 0.36%   |
| Toshiba Satellite P755                     | 1         | 0.36%   |
| Toshiba Satellite M500                     | 1         | 0.36%   |
| Toshiba Satellite L350D                    | 1         | 0.36%   |
| Toshiba Satellite C675                     | 1         | 0.36%   |
| Toshiba Satellite C665                     | 1         | 0.36%   |
| Teclast F15S                               | 1         | 0.36%   |
| System76 Serval WS                         | 1         | 0.36%   |
| Star Labs LabTop                           | 1         | 0.36%   |
| Sony VPCS12X9E                             | 1         | 0.36%   |
| Sony VPCF1290X                             | 1         | 0.36%   |
| Sony VPCEH1S1E                             | 1         | 0.36%   |
| Samsung SR58P                              | 1         | 0.36%   |
| Samsung R530/R730/R540                     | 1         | 0.36%   |
| Samsung R505                               | 1         | 0.36%   |
| Samsung 550P5C/550P7C                      | 1         | 0.36%   |
| Samsung 530U4E/540U4E                      | 1         | 0.36%   |
| Samsung 350V5C/351V5C/3540VC/3440VC        | 1         | 0.36%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.36%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 37        | 13.21%  |
| Dell Latitude         | 21        | 7.5%    |
| HP Pavilion           | 20        | 7.14%   |
| Acer Aspire           | 16        | 5.71%   |
| Lenovo IdeaPad        | 10        | 3.57%   |
| HP EliteBook          | 10        | 3.57%   |
| Dell Precision        | 10        | 3.57%   |
| Toshiba Satellite     | 9         | 3.21%   |
| Dell Inspiron         | 8         | 2.86%   |
| Dell XPS              | 7         | 2.5%    |
| HP ProBook            | 5         | 1.79%   |
| HP 250                | 5         | 1.79%   |
| Dell Vostro           | 5         | 1.79%   |
| HP ZBook              | 4         | 1.43%   |
| ASUS VivoBook         | 4         | 1.43%   |
| HP Notebook           | 3         | 1.07%   |
| HP Laptop             | 3         | 1.07%   |
| Unknown               | 3         | 1.07%   |
| Packard Bell EasyNote | 2         | 0.71%   |
| Lenovo ThinkBook      | 2         | 0.71%   |
| Lenovo Legion         | 2         | 0.71%   |
| Lenovo Flex           | 2         | 0.71%   |
| HP Compaq             | 2         | 0.71%   |
| HP 15                 | 2         | 0.71%   |
| Fujitsu LIFEBOOK      | 2         | 0.71%   |
| Dell System           | 2         | 0.71%   |
| Dell Studio           | 2         | 0.71%   |
| ASUS ZenBook          | 2         | 0.71%   |
| ASUS X553MA           | 2         | 0.71%   |
| ASUS X541SA           | 2         | 0.71%   |
| Wortmann AG TERRA     | 1         | 0.36%   |
| TUXEDO InfinityBook   | 1         | 0.36%   |
| Teclast F15S          | 1         | 0.36%   |
| System76 Serval       | 1         | 0.36%   |
| Star Labs LabTop      | 1         | 0.36%   |
| Sony VPCS12X9E        | 1         | 0.36%   |
| Sony VPCF1290X        | 1         | 0.36%   |
| Sony VPCEH1S1E        | 1         | 0.36%   |
| Samsung SR58P         | 1         | 0.36%   |
| Samsung R530          | 1         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 36        | 12.86%  |
| 2019    | 28        | 10%     |
| 2012    | 28        | 10%     |
| 2013    | 24        | 8.57%   |
| 2020    | 21        | 7.5%    |
| 2018    | 20        | 7.14%   |
| 2014    | 19        | 6.79%   |
| 2015    | 18        | 6.43%   |
| 2016    | 17        | 6.07%   |
| 2010    | 17        | 6.07%   |
| 2008    | 17        | 6.07%   |
| 2017    | 13        | 4.64%   |
| 2021    | 11        | 3.93%   |
| 2009    | 6         | 2.14%   |
| 2007    | 3         | 1.07%   |
| 2006    | 1         | 0.36%   |
| Unknown | 1         | 0.36%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 280       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 250       | 88.97%  |
| Enabled  | 31        | 11.03%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 279       | 99.64%  |
| Yes  | 1         | 0.36%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 81        | 28.52%  |
| 4.01-8.0    | 74        | 26.06%  |
| 8.01-16.0   | 45        | 15.85%  |
| 16.01-24.0  | 40        | 14.08%  |
| 32.01-64.0  | 18        | 6.34%   |
| 1.01-2.0    | 8         | 2.82%   |
| 2.01-3.0    | 7         | 2.46%   |
| 64.01-256.0 | 7         | 2.46%   |
| 24.01-32.0  | 4         | 1.41%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 116       | 39.06%  |
| 2.01-3.0   | 77        | 25.93%  |
| 3.01-4.0   | 38        | 12.79%  |
| 4.01-8.0   | 36        | 12.12%  |
| 0.51-1.0   | 23        | 7.74%   |
| 8.01-16.0  | 6         | 2.02%   |
| 24.01-32.0 | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 207       | 72.63%  |
| 2      | 68        | 23.86%  |
| 3      | 8         | 2.81%   |
| 4      | 1         | 0.35%   |
| 0      | 1         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 152       | 54.09%  |
| Yes       | 129       | 45.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 241       | 86.07%  |
| No        | 39        | 13.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 275       | 97.52%  |
| No        | 7         | 2.48%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 213       | 75.27%  |
| No        | 70        | 24.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Brazil      | 37        | 13.17%  |
| USA         | 34        | 12.1%   |
| France      | 31        | 11.03%  |
| Germany     | 26        | 9.25%   |
| UK          | 15        | 5.34%   |
| Spain       | 15        | 5.34%   |
| Italy       | 14        | 4.98%   |
| Russia      | 12        | 4.27%   |
| Ukraine     | 9         | 3.2%    |
| Netherlands | 7         | 2.49%   |
| Switzerland | 6         | 2.14%   |
| Indonesia   | 5         | 1.78%   |
| Argentina   | 5         | 1.78%   |
| Poland      | 4         | 1.42%   |
| Canada      | 4         | 1.42%   |
| Turkey      | 3         | 1.07%   |
| Norway      | 3         | 1.07%   |
| India       | 3         | 1.07%   |
| Greece      | 3         | 1.07%   |
| Finland     | 3         | 1.07%   |
| Vietnam     | 2         | 0.71%   |
| Thailand    | 2         | 0.71%   |
| Sweden      | 2         | 0.71%   |
| Portugal    | 2         | 0.71%   |
| Philippines | 2         | 0.71%   |
| Mexico      | 2         | 0.71%   |
| Ireland     | 2         | 0.71%   |
| Denmark     | 2         | 0.71%   |
| Chile       | 2         | 0.71%   |
| Belgium     | 2         | 0.71%   |
| Venezuela   | 1         | 0.36%   |
| Uruguay     | 1         | 0.36%   |
| Taiwan      | 1         | 0.36%   |
| Slovakia    | 1         | 0.36%   |
| Réunion    | 1         | 0.36%   |
| Puerto Rico | 1         | 0.36%   |
| Peru        | 1         | 0.36%   |
| New Zealand | 1         | 0.36%   |
| Morocco     | 1         | 0.36%   |
| Malaysia    | 1         | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Sao Paulo         | 19        | 6.6%    |
| Paris             | 7         | 2.43%   |
| Moscow            | 6         | 2.08%   |
| Kyiv              | 5         | 1.74%   |
| Rome              | 3         | 1.04%   |
| Rio de Janeiro    | 3         | 1.04%   |
| Berlin            | 3         | 1.04%   |
| Barcelona         | 3         | 1.04%   |
| Seville           | 2         | 0.69%   |
| Samara            | 2         | 0.69%   |
| Saint-Cloud       | 2         | 0.69%   |
| Porto Alegre      | 2         | 0.69%   |
| Oslo              | 2         | 0.69%   |
| Marseille         | 2         | 0.69%   |
| Manchester        | 2         | 0.69%   |
| Jakarta           | 2         | 0.69%   |
| Huissen           | 2         | 0.69%   |
| Ho Chi Minh City  | 2         | 0.69%   |
| Gigean            | 2         | 0.69%   |
| Genoa             | 2         | 0.69%   |
| Frankfurt am Main | 2         | 0.69%   |
| Evansville        | 2         | 0.69%   |
| Essen             | 2         | 0.69%   |
| Durham            | 2         | 0.69%   |
| Draper            | 2         | 0.69%   |
| Clichy-sous-Bois  | 2         | 0.69%   |
| Brooklyn          | 2         | 0.69%   |
| Bristol           | 2         | 0.69%   |
| Athens            | 2         | 0.69%   |
| Ankara            | 2         | 0.69%   |
| Amsterdam         | 2         | 0.69%   |
| Akron             | 2         | 0.69%   |
| Zagreb            | 1         | 0.35%   |
| Xining            | 1         | 0.35%   |
| Wolfhagen         | 1         | 0.35%   |
| Willimantic       | 1         | 0.35%   |
| Washington        | 1         | 0.35%   |
| Wake Forest       | 1         | 0.35%   |
| Vlkova            | 1         | 0.35%   |
| Viña del Mar     | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 50        | 55     | 14.33%  |
| Samsung Electronics   | 46        | 53     | 13.18%  |
| WDC                   | 44        | 51     | 12.61%  |
| Toshiba               | 34        | 39     | 9.74%   |
| Kingston              | 27        | 32     | 7.74%   |
| Unknown               | 21        | 23     | 6.02%   |
| SanDisk               | 19        | 23     | 5.44%   |
| Hitachi               | 14        | 16     | 4.01%   |
| SK hynix              | 13        | 16     | 3.72%   |
| Crucial               | 11        | 16     | 3.15%   |
| Intel                 | 10        | 12     | 2.87%   |
| A-DATA Technology     | 7         | 7      | 2.01%   |
| KIOXIA                | 5         | 6      | 1.43%   |
| HGST                  | 5         | 5      | 1.43%   |
| China                 | 5         | 6      | 1.43%   |
| Micron Technology     | 4         | 5      | 1.15%   |
| PNY                   | 3         | 3      | 0.86%   |
| Phison                | 3         | 3      | 0.86%   |
| Fujitsu               | 3         | 3      | 0.86%   |
| Transcend             | 2         | 3      | 0.57%   |
| Silicon Motion        | 2         | 2      | 0.57%   |
| Patriot               | 2         | 2      | 0.57%   |
| KingSpec              | 2         | 2      | 0.57%   |
| Intenso               | 2         | 2      | 0.57%   |
| Apacer                | 2         | 3      | 0.57%   |
| XPG                   | 1         | 1      | 0.29%   |
| Vaseky                | 1         | 1      | 0.29%   |
| Smart                 | 1         | 1      | 0.29%   |
| Realtek Semiconductor | 1         | 1      | 0.29%   |
| Plextor               | 1         | 1      | 0.29%   |
| OCZ                   | 1         | 1      | 0.29%   |
| Netac                 | 1         | 1      | 0.29%   |
| LITEONIT              | 1         | 2      | 0.29%   |
| LITEON                | 1         | 1      | 0.29%   |
| LaCie                 | 1         | 1      | 0.29%   |
| FORESEE               | 1         | 1      | 0.29%   |
| Faspeed               | 1         | 1      | 0.29%   |
| Dogfish               | 1         | 1      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD         | 8         | 2.23%   |
| Kingston SA400S37120G 120GB SSD         | 7         | 1.96%   |
| Toshiba MQ01ABF050 500GB                | 6         | 1.68%   |
| Seagate ST320LT007-9ZV142 320GB         | 6         | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB          | 5         | 1.4%    |
| WDC WD10JPVX-22JC3T0 1TB                | 4         | 1.12%   |
| Toshiba MQ04ABF100 1TB                  | 4         | 1.12%   |
| Hitachi HTS545050B9A300 500GB           | 4         | 1.12%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.84%   |
| Unknown MMC Card  16GB                  | 3         | 0.84%   |
| Seagate ST9500420AS 500GB               | 3         | 0.84%   |
| Seagate ST500LT012-9WS142 500GB         | 3         | 0.84%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 0.84%   |
| Seagate ST1000LM014-1EJ164 1TB          | 3         | 0.84%   |
| Samsung SSD 860 EVO 500GB               | 3         | 0.84%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 0.84%   |
| Intel SSDPEKNW512G8 512GB               | 3         | 0.84%   |
| Hitachi HTS547564A9E384 640GB           | 3         | 0.84%   |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 2         | 0.56%   |
| WDC WDS240G2G0A-00JH30 240GB SSD        | 2         | 0.56%   |
| WDC WD5000BPKT-75PK4T0 500GB            | 2         | 0.56%   |
| WDC WD10SPZX-08Z10 1TB                  | 2         | 0.56%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB    | 2         | 0.56%   |
| Unknown DA4064  64GB                    | 2         | 0.56%   |
| Transcend TS512GMTS430S 512GB SSD       | 2         | 0.56%   |
| Toshiba MQ01ACF032 320GB                | 2         | 0.56%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.56%   |
| Toshiba MQ01ABD050 500GB                | 2         | 0.56%   |
| Toshiba MK7559GSXP 752GB                | 2         | 0.56%   |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.56%   |
| Seagate ST9500325AS 500GB               | 2         | 0.56%   |
| Seagate ST9250410AS 250GB               | 2         | 0.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB     | 2         | 0.56%   |
| Seagate ST500LM000-SSHD-8GB             | 2         | 0.56%   |
| Seagate ST2000LM015-2E8174 2TB          | 2         | 0.56%   |
| SanDisk SD6SB2M-512G-1006 512GB SSD     | 2         | 0.56%   |
| SanDisk NVMe SSD Drive 512GB            | 2         | 0.56%   |
| SanDisk DF4064  64GB                    | 2         | 0.56%   |
| Samsung SSD PM830 mSATA 128GB           | 2         | 0.56%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 50        | 54     | 38.17%  |
| WDC                 | 29        | 34     | 22.14%  |
| Toshiba             | 27        | 32     | 20.61%  |
| Hitachi             | 14        | 16     | 10.69%  |
| HGST                | 5         | 5      | 3.82%   |
| Fujitsu             | 3         | 3      | 2.29%   |
| Samsung Electronics | 2         | 2      | 1.53%   |
| LaCie               | 1         | 1      | 0.76%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 37     | 25.2%   |
| Kingston            | 25        | 30     | 19.69%  |
| SanDisk             | 13        | 16     | 10.24%  |
| Crucial             | 9         | 14     | 7.09%   |
| WDC                 | 6         | 6      | 4.72%   |
| A-DATA Technology   | 6         | 6      | 4.72%   |
| China               | 5         | 6      | 3.94%   |
| Intel               | 4         | 5      | 3.15%   |
| Toshiba             | 3         | 3      | 2.36%   |
| PNY                 | 3         | 3      | 2.36%   |
| Transcend           | 2         | 3      | 1.57%   |
| Micron Technology   | 2         | 3      | 1.57%   |
| KingSpec            | 2         | 2      | 1.57%   |
| Intenso             | 2         | 2      | 1.57%   |
| Apacer              | 2         | 3      | 1.57%   |
| Vaseky              | 1         | 1      | 0.79%   |
| Smart               | 1         | 1      | 0.79%   |
| SK hynix            | 1         | 3      | 0.79%   |
| Seagate             | 1         | 1      | 0.79%   |
| Plextor             | 1         | 1      | 0.79%   |
| Patriot             | 1         | 1      | 0.79%   |
| OCZ                 | 1         | 1      | 0.79%   |
| Netac               | 1         | 1      | 0.79%   |
| LITEONIT            | 1         | 2      | 0.79%   |
| FORESEE             | 1         | 1      | 0.79%   |
| Dogfish             | 1         | 1      | 0.79%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 126       | 147    | 38.41%  |
| SSD     | 116       | 153    | 35.37%  |
| NVMe    | 66        | 78     | 20.12%  |
| MMC     | 19        | 23     | 5.79%   |
| Unknown | 1         | 1      | 0.3%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 220       | 293    | 70.29%  |
| NVMe | 66        | 78     | 21.09%  |
| MMC  | 19        | 23     | 6.07%   |
| SAS  | 8         | 8      | 2.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 168       | 211    | 68.57%  |
| 0.51-1.0   | 65        | 73     | 26.53%  |
| 1.01-2.0   | 10        | 14     | 4.08%   |
| 3.01-4.0   | 2         | 2      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 88        | 30.66%  |
| 101-250        | 79        | 27.53%  |
| 501-1000       | 45        | 15.68%  |
| 1-20           | 18        | 6.27%   |
| 1001-2000      | 17        | 5.92%   |
| 51-100         | 17        | 5.92%   |
| 21-50          | 11        | 3.83%   |
| More than 3000 | 6         | 2.09%   |
| 2001-3000      | 6         | 2.09%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 102       | 34.34%  |
| 51-100         | 51        | 17.17%  |
| 21-50          | 48        | 16.16%  |
| 101-250        | 48        | 16.16%  |
| 251-500        | 28        | 9.43%   |
| 501-1000       | 14        | 4.71%   |
| 1001-2000      | 4         | 1.35%   |
| More than 3000 | 1         | 0.34%   |
| 2001-3000      | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST320LT007-9ZV142 320GB   | 4         | 4      | 11.76%  |
| Toshiba MK7559GSXP 752GB          | 2         | 2      | 5.88%   |
| WDC WD7500BPVT-75HXZT1 752GB      | 1         | 1      | 2.94%   |
| WDC WD7500BPKT-75PK4T0 752GB      | 1         | 1      | 2.94%   |
| WDC WD5000LPVX-22V0TT0 500GB      | 1         | 1      | 2.94%   |
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 2      | 2.94%   |
| WDC WD3200BEVT-60ZCT1 320GB       | 1         | 1      | 2.94%   |
| WDC WD10JPCX-24UE4T0 1TB          | 1         | 1      | 2.94%   |
| Vaseky V820/1TB 1024GB            | 1         | 1      | 2.94%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 2.94%   |
| Toshiba MK5065GSX 500GB           | 1         | 1      | 2.94%   |
| Toshiba MK2565GSXN 250GB          | 1         | 1      | 2.94%   |
| Toshiba MK2555GSX 250GB           | 1         | 1      | 2.94%   |
| Seagate ST9500420AS 500GB         | 1         | 1      | 2.94%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 2.94%   |
| Seagate ST9250410AS 250GB         | 1         | 1      | 2.94%   |
| Seagate ST9160821AS 160GB         | 1         | 1      | 2.94%   |
| Seagate ST500LT012-9WS142 500GB   | 1         | 1      | 2.94%   |
| Seagate ST320LT012-9WS14C 320GB   | 1         | 1      | 2.94%   |
| SanDisk SD7SN3Q256G1002 256GB SSD | 1         | 1      | 2.94%   |
| Samsung Electronics HM160HI 160GB | 1         | 1      | 2.94%   |
| OCZ VERTEX450 128GB SSD           | 1         | 1      | 2.94%   |
| Intel SSDSC2KF256H6L 256GB        | 1         | 1      | 2.94%   |
| Hitachi HTS722016K9A300 160GB     | 1         | 1      | 2.94%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 2.94%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 2.94%   |
| Fujitsu MHZ2320BH G1 320GB        | 1         | 1      | 2.94%   |
| China SSD 120GB                   | 1         | 1      | 2.94%   |
| A-DATA Technology SU650 120GB SSD | 1         | 1      | 2.94%   |
| A-DATA Technology SP900 64GB SSD  | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 29.41%  |
| WDC                 | 6         | 7      | 17.65%  |
| Toshiba             | 6         | 6      | 17.65%  |
| Hitachi             | 3         | 3      | 8.82%   |
| A-DATA Technology   | 2         | 2      | 5.88%   |
| Vaseky              | 1         | 1      | 2.94%   |
| SanDisk             | 1         | 1      | 2.94%   |
| Samsung Electronics | 1         | 1      | 2.94%   |
| OCZ                 | 1         | 1      | 2.94%   |
| Intel               | 1         | 1      | 2.94%   |
| Fujitsu             | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |

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
| HDD  | 27        | 28     | 79.41%  |
| SSD  | 7         | 7      | 20.59%  |

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
| Works    | 156       | 204    | 52%     |
| Detected | 110       | 163    | 36.67%  |
| Malfunc  | 34        | 35     | 11.33%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 212       | 68.39%  |
| AMD                              | 30        | 9.68%   |
| SanDisk                          | 14        | 4.52%   |
| Samsung Electronics              | 13        | 4.19%   |
| SK hynix                         | 11        | 3.55%   |
| Toshiba America Info Systems     | 6         | 1.94%   |
| KIOXIA                           | 4         | 1.29%   |
| Silicon Motion                   | 3         | 0.97%   |
| Phison Electronics               | 3         | 0.97%   |
| Silicon Integrated Systems [SiS] | 2         | 0.65%   |
| Micron/Crucial Technology        | 2         | 0.65%   |
| Micron Technology                | 2         | 0.65%   |
| Kingston Technology Company      | 2         | 0.65%   |
| ADATA Technology                 | 2         | 0.65%   |
| Solid State Storage Technology   | 1         | 0.32%   |
| Realtek Semiconductor            | 1         | 0.32%   |
| Nvidia                           | 1         | 0.32%   |
| Lite-On Technology               | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 31        | 9.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 8.93%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 22        | 6.55%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 18        | 5.36%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 16        | 4.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 15        | 4.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 12        | 3.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 3.57%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 8         | 2.38%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 8         | 2.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.38%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 2.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 7         | 2.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 6         | 1.79%   |
| Intel SSD 660P Series                                                            | 5         | 1.49%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 5         | 1.49%   |
| SK hynix BC511                                                                   | 4         | 1.19%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 1.19%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 4         | 1.19%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 3         | 0.89%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 3         | 0.89%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 3         | 0.89%   |
| Samsung NVMe SSD Controller 980                                                  | 3         | 0.89%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 0.89%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 3         | 0.89%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 3         | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 3         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 3         | 0.89%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 3         | 0.89%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 3         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.89%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 2         | 0.6%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 2         | 0.6%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 0.6%    |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 213       | 66.98%  |
| NVMe | 65        | 20.44%  |
| RAID | 21        | 6.6%    |
| IDE  | 19        | 5.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 244       | 87.14%  |
| AMD    | 35        | 12.5%   |
| ARM    | 1         | 0.36%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.79%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 5         | 1.79%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 5         | 1.79%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 5         | 1.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.43%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.43%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 1.43%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 4         | 1.43%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.43%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 1.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.43%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 1.43%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 3         | 1.07%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.07%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 3         | 1.07%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 3         | 1.07%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.07%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 1.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 1.07%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 1.07%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 3         | 1.07%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.07%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.07%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.71%   |
| Intel Core m3-8100Y CPU @ 1.10GHz             | 2         | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 0.71%   |
| Intel Core i7-7560U CPU @ 2.40GHz             | 2         | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.71%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 2         | 0.71%   |
| Intel Core i7-4900MQ CPU @ 2.80GHz            | 2         | 0.71%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 0.71%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 2         | 0.71%   |
| Intel Core i7-3667U CPU @ 2.00GHz             | 2         | 0.71%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 2         | 0.71%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.71%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 0.71%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.71%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 2         | 0.71%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 78        | 27.86%  |
| Intel Core i7                  | 72        | 25.71%  |
| Intel Core i3                  | 25        | 8.93%   |
| Intel Core 2 Duo               | 14        | 5%      |
| Intel Celeron                  | 14        | 5%      |
| Other                          | 11        | 3.93%   |
| Intel Pentium                  | 11        | 3.93%   |
| AMD Ryzen 7                    | 6         | 2.14%   |
| Intel Atom                     | 5         | 1.79%   |
| AMD Ryzen 5                    | 5         | 1.79%   |
| AMD A6                         | 4         | 1.43%   |
| Intel Pentium Dual-Core        | 3         | 1.07%   |
| Intel Core m3                  | 3         | 1.07%   |
| AMD A4                         | 3         | 1.07%   |
| Intel Xeon                     | 2         | 0.71%   |
| Intel Core M                   | 2         | 0.71%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.71%   |
| AMD Ryzen 9                    | 2         | 0.71%   |
| AMD Ryzen 3                    | 2         | 0.71%   |
| AMD A8                         | 2         | 0.71%   |
| Intel Pentium Silver           | 1         | 0.36%   |
| Intel Pentium Dual             | 1         | 0.36%   |
| Intel Genuine                  | 1         | 0.36%   |
| Intel Core i9                  | 1         | 0.36%   |
| Intel Core 2 Extreme           | 1         | 0.36%   |
| Intel Celeron Dual-Core        | 1         | 0.36%   |
| AMD Turion 64 Mobile           | 1         | 0.36%   |
| AMD Ryzen 7 PRO                | 1         | 0.36%   |
| AMD Ryzen 5 PRO                | 1         | 0.36%   |
| AMD Phenom II                  | 1         | 0.36%   |
| AMD E2                         | 1         | 0.36%   |
| AMD E                          | 1         | 0.36%   |
| AMD Athlon X2                  | 1         | 0.36%   |
| AMD Athlon                     | 1         | 0.36%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 160       | 56.94%  |
| 4      | 97        | 34.52%  |
| 8      | 10        | 3.56%   |
| 6      | 10        | 3.56%   |
| 1      | 3         | 1.07%   |
| 3      | 1         | 0.36%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 279       | 99.64%  |
| 2      | 1         | 0.36%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 205       | 73.21%  |
| 1      | 75        | 26.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 280       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 12.01%  |
| 0x206a7    | 32        | 11.31%  |
| 0x306a9    | 30        | 10.6%   |
| 0x306d4    | 13        | 4.59%   |
| 0x1067a    | 11        | 3.89%   |
| 0x806e9    | 10        | 3.53%   |
| 0x40651    | 10        | 3.53%   |
| 0x806ec    | 9         | 3.18%   |
| 0x306c3    | 9         | 3.18%   |
| 0x806ea    | 7         | 2.47%   |
| 0x20655    | 7         | 2.47%   |
| 0x706e5    | 6         | 2.12%   |
| 0x6fd      | 6         | 2.12%   |
| 0x406e3    | 6         | 2.12%   |
| 0x20652    | 6         | 2.12%   |
| 0x08108102 | 6         | 2.12%   |
| 0x906ea    | 5         | 1.77%   |
| 0x906e9    | 5         | 1.77%   |
| 0x806c1    | 5         | 1.77%   |
| 0x406c4    | 5         | 1.77%   |
| 0x30678    | 5         | 1.77%   |
| 0x706a1    | 4         | 1.41%   |
| 0x506e3    | 4         | 1.41%   |
| 0x06006705 | 4         | 1.41%   |
| 0x806d1    | 3         | 1.06%   |
| 0x30673    | 3         | 1.06%   |
| 0x08600106 | 3         | 1.06%   |
| 0x02000032 | 3         | 1.06%   |
| 0xa0652    | 2         | 0.71%   |
| 0x906ed    | 2         | 0.71%   |
| 0x6fa      | 2         | 0.71%   |
| 0x506c9    | 2         | 0.71%   |
| 0x406c3    | 2         | 0.71%   |
| 0x106e5    | 2         | 0.71%   |
| 0x10676    | 2         | 0.71%   |
| 0x08108109 | 2         | 0.71%   |
| 0x08101016 | 2         | 0.71%   |
| 0x07030105 | 2         | 0.71%   |
| 0xa0660    | 1         | 0.35%   |
| 0x806eb    | 1         | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 46        | 16.43%  |
| SandyBridge     | 36        | 12.86%  |
| IvyBridge       | 32        | 11.43%  |
| Haswell         | 24        | 8.57%   |
| Broadwell       | 16        | 5.71%   |
| Silvermont      | 15        | 5.36%   |
| Westmere        | 13        | 4.64%   |
| Skylake         | 13        | 4.64%   |
| Penryn          | 13        | 4.64%   |
| Icelake         | 10        | 3.57%   |
| Zen+            | 8         | 2.86%   |
| Core            | 8         | 2.86%   |
| TigerLake       | 5         | 1.79%   |
| Excavator       | 5         | 1.79%   |
| Zen 2           | 4         | 1.43%   |
| Puma            | 4         | 1.43%   |
| Goldmont plus   | 4         | 1.43%   |
| Zen 3           | 3         | 1.07%   |
| Zen             | 3         | 1.07%   |
| K8 & K10 hybrid | 3         | 1.07%   |
| Goldmont        | 3         | 1.07%   |
| CometLake       | 3         | 1.07%   |
| Nehalem         | 2         | 0.71%   |
| Bobcat          | 2         | 0.71%   |
| Piledriver      | 1         | 0.36%   |
| K8 Hammer       | 1         | 0.36%   |
| K10             | 1         | 0.36%   |
| Bonnell         | 1         | 0.36%   |
| Unknown         | 1         | 0.36%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 222       | 63.25%  |
| Nvidia                           | 71        | 20.23%  |
| AMD                              | 57        | 16.24%  |
| Silicon Integrated Systems [SiS] | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 31        | 8.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 8.36%   |
| Intel HD Graphics 5500                                                                   | 14        | 3.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 3.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 3.06%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 2.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 2.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 9         | 2.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.51%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 2.23%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.39%   |
| Intel HD Graphics 530                                                                    | 5         | 1.39%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.39%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 1.11%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 1.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1.11%   |
| Intel HD Graphics 630                                                                    | 4         | 1.11%   |
| Intel HD Graphics 620                                                                    | 4         | 1.11%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 1.11%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.11%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.84%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.84%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.84%   |
| Intel HD Graphics 500                                                                    | 3         | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.84%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 0.84%   |
| AMD Renoir                                                                               | 3         | 0.84%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.84%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.84%   |
| AMD Cezanne                                                                              | 3         | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.56%   |
| Nvidia TU117GLM [T1200 Laptop GPU]                                                       | 2         | 0.56%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 153       | 54.64%  |
| Intel + Nvidia | 54        | 19.29%  |
| 1 x AMD        | 35        | 12.5%   |
| 1 x Nvidia     | 15        | 5.36%   |
| Intel + AMD    | 15        | 5.36%   |
| 2 x AMD        | 4         | 1.43%   |
| AMD + Nvidia   | 2         | 0.71%   |
| Other          | 1         | 0.36%   |
| 1 x SiS        | 1         | 0.36%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 232       | 82.27%  |
| Proprietary | 40        | 14.18%  |
| Unknown     | 10        | 3.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 192       | 68.33%  |
| 1.01-2.0   | 25        | 8.9%    |
| 0.01-0.5   | 25        | 8.9%    |
| 0.51-1.0   | 18        | 6.41%   |
| 3.01-4.0   | 14        | 4.98%   |
| 5.01-6.0   | 3         | 1.07%   |
| 2.01-3.0   | 3         | 1.07%   |
| 7.01-8.0   | 1         | 0.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 62        | 19.87%  |
| LG Display              | 53        | 16.99%  |
| Samsung Electronics     | 44        | 14.1%   |
| Chimei Innolux          | 41        | 13.14%  |
| BOE                     | 27        | 8.65%   |
| Dell                    | 12        | 3.85%   |
| Chi Mei Optoelectronics | 12        | 3.85%   |
| PANDA                   | 7         | 2.24%   |
| Sharp                   | 6         | 1.92%   |
| LG Philips              | 4         | 1.28%   |
| Lenovo                  | 4         | 1.28%   |
| Hewlett-Packard         | 4         | 1.28%   |
| Goldstar                | 4         | 1.28%   |
| Philips                 | 3         | 0.96%   |
| InnoLux Display         | 3         | 0.96%   |
| Apple                   | 3         | 0.96%   |
| Sony                    | 2         | 0.64%   |
| Iiyama                  | 2         | 0.64%   |
| CSO                     | 2         | 0.64%   |
| AOC                     | 2         | 0.64%   |
| Ancor Communications    | 2         | 0.64%   |
| Acer                    | 2         | 0.64%   |
| ___                     | 1         | 0.32%   |
| Vizio                   | 1         | 0.32%   |
| Unknown                 | 1         | 0.32%   |
| Seiko/Epson             | 1         | 0.32%   |
| Optoma                  | 1         | 0.32%   |
| NEC Computers           | 1         | 0.32%   |
| MS_ Nvidia              | 1         | 0.32%   |
| Medion                  | 1         | 0.32%   |
| LGD                     | 1         | 0.32%   |
| InfoVision              | 1         | 0.32%   |
| CPT                     | 1         | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch     | 6         | 1.89%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 1.89%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 340x190mm 15.3-inch     | 3         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 3         | 0.94%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.94%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.94%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 3         | 0.94%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 3         | 0.94%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch     | 2         | 0.63%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 2         | 0.63%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.63%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.63%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch             | 2         | 0.63%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 2         | 0.63%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 2         | 0.63%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.63%   |
| Chimei Innolux LCD Monitor CMN1471 1366x768 309x174mm 14.0-inch          | 2         | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 2         | 0.63%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 2         | 0.63%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO63ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO313E 1600x900 309x174mm 14.0-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 2         | 0.63%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 2         | 0.63%   |
| ___ TV ___9000 1360x768                                                  | 1         | 0.31%   |
| Vizio D24f-G1 VIZ1027 1920x1080 527x296mm 23.8-inch                      | 1         | 0.31%   |
| Unknown LCD TV 9000 1360x768 1600x900mm 72.3-inch                        | 1         | 0.31%   |
| Sony LCD Monitor MS_0025 1920x1080 340x190mm 15.3-inch                   | 1         | 0.31%   |
| Sony BW8 MS_9001 2560x1600                                               | 1         | 0.31%   |
| Sharp LCD SHP4200 1920x1080 410x230mm 18.5-inch                          | 1         | 0.31%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.31%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 1         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 107       | 36.39%  |
| 1366x768 (WXGA)    | 104       | 35.37%  |
| 1600x900 (HD+)     | 28        | 9.52%   |
| 1280x800 (WXGA)    | 14        | 4.76%   |
| 1440x900 (WXGA+)   | 7         | 2.38%   |
| 2560x1440 (QHD)    | 6         | 2.04%   |
| 1680x1050 (WSXGA+) | 6         | 2.04%   |
| 1920x1200 (WUXGA)  | 5         | 1.7%    |
| 3840x2160 (4K)     | 4         | 1.36%   |
| 3200x1800 (QHD+)   | 2         | 0.68%   |
| 2560x1600          | 2         | 0.68%   |
| 1360x768           | 2         | 0.68%   |
| 3440x1440          | 1         | 0.34%   |
| 2880x1800          | 1         | 0.34%   |
| 2160x1440          | 1         | 0.34%   |
| 1680x945           | 1         | 0.34%   |
| 1600x1200          | 1         | 0.34%   |
| 1400x1050          | 1         | 0.34%   |
| 1024x600           | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 127       | 40.58%  |
| 13      | 41        | 13.1%   |
| 14      | 39        | 12.46%  |
| 17      | 29        | 9.27%   |
| 12      | 12        | 3.83%   |
| 21      | 9         | 2.88%   |
| 23      | 8         | 2.56%   |
| 24      | 7         | 2.24%   |
| 11      | 7         | 2.24%   |
| Unknown | 6         | 1.92%   |
| 27      | 5         | 1.6%    |
| 18      | 5         | 1.6%    |
| 22      | 4         | 1.28%   |
| 20      | 2         | 0.64%   |
| 19      | 2         | 0.64%   |
| 10      | 2         | 0.64%   |
| 72      | 1         | 0.32%   |
| 49      | 1         | 0.32%   |
| 46      | 1         | 0.32%   |
| 34      | 1         | 0.32%   |
| 31      | 1         | 0.32%   |
| 29      | 1         | 0.32%   |
| 16      | 1         | 0.32%   |
| 8       | 1         | 0.32%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 183       | 58.65%  |
| 201-300     | 40        | 12.82%  |
| 351-400     | 35        | 11.22%  |
| 401-500     | 22        | 7.05%   |
| 501-600     | 19        | 6.09%   |
| Unknown     | 6         | 1.92%   |
| 601-700     | 2         | 0.64%   |
| 1001-1500   | 2         | 0.64%   |
| 701-800     | 1         | 0.32%   |
| 1501-2000   | 1         | 0.32%   |
| 101-200     | 1         | 0.32%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 245       | 85.96%  |
| 16/10   | 30        | 10.53%  |
| 3/2     | 4         | 1.4%    |
| Unknown | 3         | 1.05%   |
| 4/3     | 1         | 0.35%   |
| 21/9    | 1         | 0.35%   |
| 0.62    | 1         | 0.35%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 126       | 40.26%  |
| 81-90          | 62        | 19.81%  |
| 201-250        | 23        | 7.35%   |
| 121-130        | 22        | 7.03%   |
| 71-80          | 18        | 5.75%   |
| 61-70          | 12        | 3.83%   |
| 51-60          | 7         | 2.24%   |
| 131-140        | 7         | 2.24%   |
| 151-200        | 6         | 1.92%   |
| Unknown        | 6         | 1.92%   |
| 301-350        | 5         | 1.6%    |
| 251-300        | 4         | 1.28%   |
| 141-150        | 4         | 1.28%   |
| 351-500        | 3         | 0.96%   |
| More than 1000 | 2         | 0.64%   |
| 41-50          | 2         | 0.64%   |
| 1-40           | 1         | 0.32%   |
| 111-120        | 1         | 0.32%   |
| 501-1000       | 1         | 0.32%   |
| 91-100         | 1         | 0.32%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 113       | 36.57%  |
| 121-160       | 106       | 34.3%   |
| 51-100        | 53        | 17.15%  |
| 161-240       | 20        | 6.47%   |
| More than 240 | 8         | 2.59%   |
| Unknown       | 6         | 1.94%   |
| 1-50          | 3         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 232       | 81.98%  |
| 2     | 41        | 14.49%  |
| 3     | 5         | 1.77%   |
| 0     | 5         | 1.77%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 145       | 32.58%  |
| Realtek Semiconductor             | 142       | 31.91%  |
| Qualcomm Atheros                  | 75        | 16.85%  |
| Broadcom                          | 31        | 6.97%   |
| Broadcom Limited                  | 12        | 2.7%    |
| Ralink                            | 7         | 1.57%   |
| Marvell Technology Group          | 6         | 1.35%   |
| Sierra Wireless                   | 4         | 0.9%    |
| Ralink Technology                 | 4         | 0.9%    |
| Xiaomi                            | 2         | 0.45%   |
| TP-Link                           | 2         | 0.45%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.45%   |
| Ericsson Business Mobile Networks | 2         | 0.45%   |
| Tenda                             | 1         | 0.22%   |
| Samsung Electronics               | 1         | 0.22%   |
| Qualcomm Atheros Communications   | 1         | 0.22%   |
| Qualcomm                          | 1         | 0.22%   |
| NetGear                           | 1         | 0.22%   |
| Lenovo                            | 1         | 0.22%   |
| Hewlett-Packard                   | 1         | 0.22%   |
| FIBOCOM                           | 1         | 0.22%   |
| Dell                              | 1         | 0.22%   |
| Attansic Technology               | 1         | 0.22%   |
| ASIX Electronics                  | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 88        | 16.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 35        | 6.45%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 22        | 4.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 2.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 2.58%   |
| Intel Wireless 7260                                                     | 14        | 2.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 2.39%   |
| Intel Wireless 7265                                                     | 13        | 2.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 2.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 1.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 1.66%   |
| Intel Wireless 8265 / 8275                                              | 9         | 1.66%   |
| Intel Wireless 3165                                                     | 9         | 1.66%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 1.47%   |
| Intel Ethernet Connection I217-LM                                       | 8         | 1.47%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.29%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 1.1%    |
| Intel Centrino Advanced-N 6235                                          | 6         | 1.1%    |
| Intel Ethernet Connection I218-LM                                       | 5         | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                                   | 5         | 0.92%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.92%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.74%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 0.74%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 0.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 0.55%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller               | 3         | 0.55%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 0.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 0.55%   |
| Intel Wireless 8260                                                     | 3         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 137       | 46.76%  |
| Qualcomm Atheros                | 64        | 21.84%  |
| Realtek Semiconductor           | 35        | 11.95%  |
| Broadcom                        | 22        | 7.51%   |
| Broadcom Limited                | 11        | 3.75%   |
| Ralink                          | 7         | 2.39%   |
| Sierra Wireless                 | 4         | 1.37%   |
| Ralink Technology               | 4         | 1.37%   |
| TP-Link                         | 2         | 0.68%   |
| Tenda                           | 1         | 0.34%   |
| Qualcomm Atheros Communications | 1         | 0.34%   |
| Qualcomm                        | 1         | 0.34%   |
| NetGear                         | 1         | 0.34%   |
| Hewlett-Packard                 | 1         | 0.34%   |
| FIBOCOM                         | 1         | 0.34%   |
| Dell                            | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 5.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 14        | 4.78%   |
| Intel Wireless 7260                                                     | 14        | 4.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 4.44%   |
| Intel Wireless 7265                                                     | 13        | 4.44%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 12        | 4.1%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 4.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 10        | 3.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.07%   |
| Intel Wireless 8265 / 8275                                              | 9         | 3.07%   |
| Intel Wireless 3165                                                     | 9         | 3.07%   |
| Intel Wi-Fi 6 AX200                                                     | 8         | 2.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 2.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 2.39%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 6         | 2.05%   |
| Intel Centrino Advanced-N 6235                                          | 6         | 2.05%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.37%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.37%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 4         | 1.37%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.37%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 1.37%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 4         | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 3         | 1.02%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.02%   |
| Intel Wireless 8260                                                     | 3         | 1.02%   |
| Intel WiFi Link 5100                                                    | 3         | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.02%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 3         | 1.02%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.02%   |
| Sierra Wireless EM7345 4G LTE                                           | 2         | 0.68%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.68%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.68%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.68%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 134       | 54.69%  |
| Intel                            | 67        | 27.35%  |
| Qualcomm Atheros                 | 17        | 6.94%   |
| Broadcom                         | 11        | 4.49%   |
| Marvell Technology Group         | 6         | 2.45%   |
| Xiaomi                           | 2         | 0.82%   |
| Silicon Integrated Systems [SiS] | 2         | 0.82%   |
| Broadcom Limited                 | 2         | 0.82%   |
| Samsung Electronics              | 1         | 0.41%   |
| Lenovo                           | 1         | 0.41%   |
| Attansic Technology              | 1         | 0.41%   |
| ASIX Electronics                 | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 35.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 14.11%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 8.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 4.03%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 3.23%   |
| Intel Ethernet Connection I218-LM                                 | 5         | 2.02%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 2.02%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 2.02%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.21%   |
| Intel Ethernet Connection I219-V                                  | 3         | 1.21%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.21%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.81%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.81%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.81%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.81%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.81%   |
| Intel Ethernet Connection (14) I219-LM                            | 2         | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.4%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.4%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.4%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.4%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.4%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.4%    |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.4%    |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller              | 1         | 0.4%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.4%    |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 1         | 0.4%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.4%    |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 1         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 275       | 53.19%  |
| Ethernet | 240       | 46.42%  |
| Modem    | 2         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 226       | 77.13%  |
| Ethernet | 67        | 22.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 223       | 79.08%  |
| 1     | 55        | 19.5%   |
| 0     | 3         | 1.06%   |
| 3     | 1         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 238       | 84.7%   |
| Yes  | 43        | 15.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 100       | 46.3%   |
| Qualcomm Atheros Communications | 28        | 12.96%  |
| Realtek Semiconductor           | 21        | 9.72%   |
| Broadcom                        | 20        | 9.26%   |
| Dell                            | 12        | 5.56%   |
| Lite-On Technology              | 9         | 4.17%   |
| IMC Networks                    | 9         | 4.17%   |
| Foxconn / Hon Hai               | 4         | 1.85%   |
| Cambridge Silicon Radio         | 4         | 1.85%   |
| Ralink                          | 3         | 1.39%   |
| Ralink Technology               | 2         | 0.93%   |
| ASUSTek Computer                | 2         | 0.93%   |
| Foxconn International           | 1         | 0.46%   |
| Apple                           | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 53        | 24.54%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 14        | 6.48%   |
| Intel AX201 Bluetooth                               | 12        | 5.56%   |
| Realtek Bluetooth Radio                             | 10        | 4.63%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 3.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 3.24%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 3.24%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 3.24%   |
| Intel AX200 Bluetooth                               | 7         | 3.24%   |
| IMC Networks Bluetooth Device                       | 7         | 3.24%   |
| Dell DW375 Bluetooth Module                         | 6         | 2.78%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 4         | 1.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.85%   |
| Broadcom HP Portable SoftSailing                    | 4         | 1.85%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 4         | 1.85%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.39%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 1.39%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.39%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.39%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 1.39%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.93%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.93%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.93%   |
| Lite-On Bluetooth Device                            | 2         | 0.93%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.93%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.93%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 2         | 0.93%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.93%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.46%   |
| Ralink CSR BS8510                                   | 1         | 0.46%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.46%   |
| IMC Networks BCM20702A0                             | 1         | 0.46%   |
| Foxconn International BCM43142A0 Bluetooth module   | 1         | 0.46%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.46%   |
| Dell Wireless 370 Bluetooth Mini-card               | 1         | 0.46%   |
| Dell Wireless 365 Bluetooth                         | 1         | 0.46%   |
| Dell Wireless 360 Bluetooth                         | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                         | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel                                          | 236       | 68.41%  |
| AMD                                            | 44        | 12.75%  |
| Nvidia                                         | 43        | 12.46%  |
| Realtek Semiconductor                          | 4         | 1.16%   |
| Silicon Integrated Systems [SiS]               | 2         | 0.58%   |
| Lenovo                                         | 2         | 0.58%   |
| Sony                                           | 1         | 0.29%   |
| Siemens Information and Communication Products | 1         | 0.29%   |
| Plantronics                                    | 1         | 0.29%   |
| No brand                                       | 1         | 0.29%   |
| Meizu                                          | 1         | 0.29%   |
| Logitech                                       | 1         | 0.29%   |
| Kingston Technology                            | 1         | 0.29%   |
| GN Netcom                                      | 1         | 0.29%   |
| Generalplus Technology                         | 1         | 0.29%   |
| FiiO Electronics Technology                    | 1         | 0.29%   |
| Elite Silicon                                  | 1         | 0.29%   |
| Corsair                                        | 1         | 0.29%   |
| Conexant Systems                               | 1         | 0.29%   |
| C-Media Electronics                            | 1         | 0.29%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 35        | 8.41%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 7.93%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 25        | 6.01%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 4.09%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 3.85%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 3.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 15        | 3.61%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 2.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 2.88%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 2.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 11        | 2.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 11        | 2.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 2.4%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.4%    |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 2.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 7         | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.44%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 1.44%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 1.44%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.44%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.2%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 5         | 1.2%    |
| AMD High Definition Audio Controller                                                              | 5         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.2%    |
| Realtek Semiconductor USB Audio                                                                   | 4         | 0.96%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.96%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.96%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.96%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.96%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.72%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 3         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 62        | 24.9%   |
| SK hynix                                         | 46        | 18.47%  |
| Micron Technology                                | 32        | 12.85%  |
| Kingston                                         | 22        | 8.84%   |
| Unknown                                          | 20        | 8.03%   |
| Crucial                                          | 14        | 5.62%   |
| Ramaxel Technology                               | 8         | 3.21%   |
| Elpida                                           | 8         | 3.21%   |
| Nanya Technology                                 | 7         | 2.81%   |
| Smart                                            | 5         | 2.01%   |
| A-DATA Technology                                | 4         | 1.61%   |
| Unknown (ABCD)                                   | 3         | 1.2%    |
| Teikon                                           | 2         | 0.8%    |
| Patriot                                          | 2         | 0.8%    |
| Netlist                                          | 2         | 0.8%    |
| Goodram                                          | 2         | 0.8%    |
| Corsair                                          | 2         | 0.8%    |
| Unknown (0x4D342037305435363633515A332D43463720) | 1         | 0.4%    |
| Unknown (0x36345431323830323045444C322E35433220) | 1         | 0.4%    |
| Toshiba                                          | 1         | 0.4%    |
| Team                                             | 1         | 0.4%    |
| Qimonda                                          | 1         | 0.4%    |
| G.Skill                                          | 1         | 0.4%    |
| ASint Technology                                 | 1         | 0.4%    |
| Apacer                                           | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 2.26%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 2.26%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 5         | 1.89%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 1.51%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 3         | 1.13%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.13%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.13%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.13%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 1.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.13%   |
| Micron RAM MT52L1G32D4PG-093 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 1.13%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s       | 3         | 1.13%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 2         | 0.75%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.75%   |
| Unknown RAM Module 2048MB SODIMM DRAM                            | 2         | 0.75%   |
| Smart RAM SH564128FH8NZPHSCG 4096MB SODIMM DDR3 1334MT/s         | 2         | 0.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.75%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.75%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.75%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 2         | 0.75%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.75%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.75%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.75%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.75%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 2         | 0.75%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 4199MT/s                 | 2         | 0.75%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 2         | 0.75%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.75%   |
| Samsung RAM M471A2K43BB1-CRC 16GB SODIMM DDR4 2400MT/s           | 2         | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.75%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.75%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.75%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.75%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.75%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.75%   |
| Crucial RAM CT51264BF160BJ.M8F 4096MB SODIMM DDR3 1600MT/s       | 2         | 0.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 105       | 50%     |
| DDR4    | 68        | 32.38%  |
| DDR2    | 10        | 4.76%   |
| LPDDR3  | 9         | 4.29%   |
| LPDDR4  | 8         | 3.81%   |
| SDRAM   | 6         | 2.86%   |
| DRAM    | 2         | 0.95%   |
| DDR     | 1         | 0.48%   |
| Unknown | 1         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 191       | 91.39%  |
| Row Of Chips | 14        | 6.7%    |
| Chip         | 3         | 1.44%   |
| DIMM         | 1         | 0.48%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 94        | 40.69%  |
| 8192  | 64        | 27.71%  |
| 2048  | 38        | 16.45%  |
| 16384 | 22        | 9.52%   |
| 32768 | 6         | 2.6%    |
| 1024  | 6         | 2.6%    |
| 1536  | 1         | 0.43%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 71        | 30.87%  |
| 2667    | 39        | 16.96%  |
| 3200    | 21        | 9.13%   |
| 1334    | 21        | 9.13%   |
| 2400    | 13        | 5.65%   |
| 1333    | 13        | 5.65%   |
| 2133    | 12        | 5.22%   |
| Unknown | 7         | 3.04%   |
| 3266    | 6         | 2.61%   |
| 4199    | 5         | 2.17%   |
| 1066    | 5         | 2.17%   |
| 667     | 5         | 2.17%   |
| 1067    | 4         | 1.74%   |
| 800     | 3         | 1.3%    |
| 4267    | 1         | 0.43%   |
| 2048    | 1         | 0.43%   |
| 1867    | 1         | 0.43%   |
| 975     | 1         | 0.43%   |
| 533     | 1         | 0.43%   |

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
| Chicony Electronics                    | 77        | 30.92%  |
| Microdia                               | 26        | 10.44%  |
| Acer                                   | 26        | 10.44%  |
| Sunplus Innovation Technology          | 17        | 6.83%   |
| IMC Networks                           | 14        | 5.62%   |
| Realtek Semiconductor                  | 12        | 4.82%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 4.42%   |
| Quanta                                 | 10        | 4.02%   |
| Ricoh                                  | 8         | 3.21%   |
| Suyin                                  | 7         | 2.81%   |
| Silicon Motion                         | 6         | 2.41%   |
| Syntek                                 | 5         | 2.01%   |
| Lite-On Technology                     | 5         | 2.01%   |
| Logitech                               | 4         | 1.61%   |
| Apple                                  | 4         | 1.61%   |
| Luxvisions Innotech Limited            | 2         | 0.8%    |
| Importek                               | 2         | 0.8%    |
| Alcor Micro                            | 2         | 0.8%    |
| Z-Star Microelectronics                | 1         | 0.4%    |
| Y Media                                | 1         | 0.4%    |
| Samsung Electronics                    | 1         | 0.4%    |
| Ruision                                | 1         | 0.4%    |
| Primax Electronics                     | 1         | 0.4%    |
| Microsoft                              | 1         | 0.4%    |
| Lenovo                                 | 1         | 0.4%    |
| Generalplus Technology                 | 1         | 0.4%    |
| DigiTech                               | 1         | 0.4%    |
| Cubeternet                             | 1         | 0.4%    |
| Aveo Technology                        | 1         | 0.4%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 17        | 6.8%    |
| Sunplus Integrated_Webcam_HD                     | 8         | 3.2%    |
| Microdia Integrated_Webcam_HD                    | 8         | 3.2%    |
| Chicony USB2.0 VGA UVC WebCam                    | 7         | 2.8%    |
| Chicony HD Webcam                                | 6         | 2.4%    |
| Acer Integrated Camera                           | 6         | 2.4%    |
| Acer BisonCam, NB Pro                            | 6         | 2.4%    |
| IMC Networks USB2.0 HD UVC WebCam                | 5         | 2%      |
| Ricoh HD Webcam                                  | 4         | 1.6%    |
| Microdia Laptop_Integrated_Webcam_HD             | 4         | 1.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 4         | 1.6%    |
| Suyin HP TrueVision HD Integrated Webcam         | 3         | 1.2%    |
| Sunplus Laptop_Integrated_Webcam_FHD             | 3         | 1.2%    |
| Realtek Integrated_Webcam_HD                     | 3         | 1.2%    |
| Quanta HD User Facing                            | 3         | 1.2%    |
| Microdia Integrated Webcam                       | 3         | 1.2%    |
| Lite-On HP HD Camera                             | 3         | 1.2%    |
| Chicony Integrated Camera (1280x720@30)          | 3         | 1.2%    |
| Chicony HP Wide Vision HD Camera                 | 3         | 1.2%    |
| Chicony HP HD Webcam                             | 3         | 1.2%    |
| Chicony CNF9055 Toshiba Webcam                   | 3         | 1.2%    |
| Acer Lenovo Integrated Webcam                    | 3         | 1.2%    |
| Acer Lenovo EasyCamera                           | 3         | 1.2%    |
| Syntek EasyCamera                                | 2         | 0.8%    |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 2         | 0.8%    |
| Silicon Motion WebCam SC-13HDL11939N             | 2         | 0.8%    |
| Silicon Motion 300k Pixel Camera                 | 2         | 0.8%    |
| Ricoh Sony Visual Communication Camera           | 2         | 0.8%    |
| Ricoh Laptop_Integrated_Webcam_FHD               | 2         | 0.8%    |
| Realtek USB Camera                               | 2         | 0.8%    |
| Realtek Lenovo EasyCamera                        | 2         | 0.8%    |
| Quanta VGA WebCam                                | 2         | 0.8%    |
| Quanta Laptop_Integrated_Webcam_2HDM             | 2         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_2M             | 2         | 0.8%    |
| Microdia Dell Integrated HD Webcam               | 2         | 0.8%    |
| IMC Networks UVC VGA Webcam                      | 2         | 0.8%    |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 0.8%    |
| Chicony USB2.0 UVC WebCam                        | 2         | 0.8%    |
| Chicony Lenovo Integrated Camera (0.3MP)         | 2         | 0.8%    |
| Chicony HP Webcam-101                            | 2         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 23        | 52.27%  |
| Synaptics                  | 9         | 20.45%  |
| Upek                       | 3         | 6.82%   |
| Shenzhen Goodix Technology | 3         | 6.82%   |
| Elan Microelectronics      | 3         | 6.82%   |
| STMicroelectronics         | 1         | 2.27%   |
| Focal-systems.Corp         | 1         | 2.27%   |
| AuthenTec                  | 1         | 2.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                | 4         | 9.09%   |
| Validity Sensors VFS491                                    | 4         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 4         | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 6.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 3         | 6.82%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor          | 2         | 4.55%   |
| Validity Sensors Fingerprint scanner                       | 2         | 4.55%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 4.55%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                         | 2         | 4.55%   |
| Elan ELAN:Fingerprint                                      | 2         | 4.55%   |
| Validity Sensors VFS471 Fingerprint Reader                 | 1         | 2.27%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.27%   |
| Validity Sensors Synaptics WBDI                            | 1         | 2.27%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 2.27%   |
| Upek TCS5B Fingerprint sensor                              | 1         | 2.27%   |
| Synaptics Metallica MOH Touch Fingerprint Reader           | 1         | 2.27%   |
| STMicroelectronics Fingerprint Reader                      | 1         | 2.27%   |
| Shenzhen Goodix FingerPrint                                | 1         | 2.27%   |
| Focal-systems.Corp FT9201Fingerprint.                      | 1         | 2.27%   |
| Elan ELAN:ARM-M4                                           | 1         | 2.27%   |
| AuthenTec AES2810                                          | 1         | 2.27%   |
| Unknown                                                    | 1         | 2.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 22        | 59.46%  |
| Alcor Micro           | 7         | 18.92%  |
| Upek                  | 2         | 5.41%   |
| O2 Micro              | 2         | 5.41%   |
| Lenovo                | 2         | 5.41%   |
| Gemalto (was Gemplus) | 1         | 2.7%    |
| Advanced Card Systems | 1         | 2.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 27.03%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 18.92%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 7         | 18.92%  |
| Broadcom 5880                                                                | 3         | 8.11%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5.41%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.41%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.41%   |
| Broadcom 58200                                                               | 2         | 5.41%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 2.7%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 173       | 60.7%   |
| 1     | 92        | 32.28%  |
| 2     | 17        | 5.96%   |
| 8     | 2         | 0.7%    |
| 3     | 1         | 0.35%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 30.99%  |
| Chipcard                 | 35        | 24.65%  |
| Graphics card            | 28        | 19.72%  |
| Storage                  | 8         | 5.63%   |
| Net/wireless             | 8         | 5.63%   |
| Bluetooth                | 5         | 3.52%   |
| Multimedia controller    | 3         | 2.11%   |
| Camera                   | 3         | 2.11%   |
| Sound                    | 2         | 1.41%   |
| Communication controller | 2         | 1.41%   |
| Network                  | 1         | 0.7%    |
| Flash memory             | 1         | 0.7%    |
| Firewire controller      | 1         | 0.7%    |
| Card reader              | 1         | 0.7%    |

