Ubuntu 21.10 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.10.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3584               | [14630b0a02](https://linux-hardware.org/?probe=14630b0a02) | Feb 01, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [2621c151ec](https://linux-hardware.org/?probe=2621c151ec) | Feb 01, 2022 |
| Lenovo        | Rev B 20YM                  | [83c63da100](https://linux-hardware.org/?probe=83c63da100) | Feb 01, 2022 |
| HP            | 255 G6 Notebook PC          | [302b9789d3](https://linux-hardware.org/?probe=302b9789d3) | Feb 01, 2022 |
| Toshiba       | Satellite C50-A-19T         | [7ea7ab684e](https://linux-hardware.org/?probe=7ea7ab684e) | Feb 01, 2022 |
| Lenovo        | G580 20157                  | [fe6a35d3f8](https://linux-hardware.org/?probe=fe6a35d3f8) | Jan 31, 2022 |
| HP            | ProBook 650 G2              | [1835f9c2d4](https://linux-hardware.org/?probe=1835f9c2d4) | Jan 31, 2022 |
| HP            | ProBook 440 G5              | [0e27902494](https://linux-hardware.org/?probe=0e27902494) | Jan 31, 2022 |
| HP            | 255 G6 Notebook PC          | [3ec8d6dcf6](https://linux-hardware.org/?probe=3ec8d6dcf6) | Jan 31, 2022 |
| HP            | 255 G8 Notebook PC          | [d6a1e99ba7](https://linux-hardware.org/?probe=d6a1e99ba7) | Jan 31, 2022 |
| Apple         | MacBook5,1                  | [dd9f492694](https://linux-hardware.org/?probe=dd9f492694) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | [7c2762f41c](https://linux-hardware.org/?probe=7c2762f41c) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | [2aa45a8d1b](https://linux-hardware.org/?probe=2aa45a8d1b) | Jan 31, 2022 |
| Samsung       | R430/P430/R480              | [b08c9147e6](https://linux-hardware.org/?probe=b08c9147e6) | Jan 31, 2022 |
| HP            | ProBook 440 G5              | [df88db4d1b](https://linux-hardware.org/?probe=df88db4d1b) | Jan 30, 2022 |
| Toshiba       | TECRA R940                  | [c326f16d07](https://linux-hardware.org/?probe=c326f16d07) | Jan 30, 2022 |
| AVITA         | NS14A6                      | [bbf5494b7f](https://linux-hardware.org/?probe=bbf5494b7f) | Jan 30, 2022 |
| AVITA         | NS14A6                      | [5cb93a7ead](https://linux-hardware.org/?probe=5cb93a7ead) | Jan 30, 2022 |
| Lenovo        | ThinkPad X390 20Q1S9RB00    | [9970037d9d](https://linux-hardware.org/?probe=9970037d9d) | Jan 30, 2022 |
| HP            | ProBook 440 G5              | [930aa74ba2](https://linux-hardware.org/?probe=930aa74ba2) | Jan 30, 2022 |
| Acer          | Aspire A515-51              | [d38f4418f9](https://linux-hardware.org/?probe=d38f4418f9) | Jan 30, 2022 |
| Acer          | Aspire A515-51              | [f1987d67dc](https://linux-hardware.org/?probe=f1987d67dc) | Jan 30, 2022 |
| Lenovo        | V130-15IGM 81HL             | [67505d4784](https://linux-hardware.org/?probe=67505d4784) | Jan 30, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [f93eabba88](https://linux-hardware.org/?probe=f93eabba88) | Jan 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [af5eb12b7b](https://linux-hardware.org/?probe=af5eb12b7b) | Jan 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | [c9528e87c0](https://linux-hardware.org/?probe=c9528e87c0) | Jan 29, 2022 |
| Lenovo        | ThinkPad T430 2350B58       | [9c867cc4a8](https://linux-hardware.org/?probe=9c867cc4a8) | Jan 29, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [478d5281bd](https://linux-hardware.org/?probe=478d5281bd) | Jan 29, 2022 |
| MSI           | GF75 Thin 10SDR             | [dadcf8d49c](https://linux-hardware.org/?probe=dadcf8d49c) | Jan 29, 2022 |
| Dell          | XPS 15 9500                 | [b5db02e326](https://linux-hardware.org/?probe=b5db02e326) | Jan 29, 2022 |
| HP            | ProBook 455 G7              | [08b0a66098](https://linux-hardware.org/?probe=08b0a66098) | Jan 29, 2022 |
| Acer          | Aspire V3-772G              | [1e4b8a880e](https://linux-hardware.org/?probe=1e4b8a880e) | Jan 29, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [b1fc771c31](https://linux-hardware.org/?probe=b1fc771c31) | Jan 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [a73b683284](https://linux-hardware.org/?probe=a73b683284) | Jan 28, 2022 |
| Lenovo        | ThinkPad T420 4180ED3       | [b115732b3b](https://linux-hardware.org/?probe=b115732b3b) | Jan 28, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [04a57a90f9](https://linux-hardware.org/?probe=04a57a90f9) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | [85796c8359](https://linux-hardware.org/?probe=85796c8359) | Jan 28, 2022 |
| Dell          | Inspiron 5480               | [59b6841322](https://linux-hardware.org/?probe=59b6841322) | Jan 28, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [23efd3ad0d](https://linux-hardware.org/?probe=23efd3ad0d) | Jan 28, 2022 |
| Acer          | Aspire E5-553G              | [6e72e70430](https://linux-hardware.org/?probe=6e72e70430) | Jan 28, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2309c1e501](https://linux-hardware.org/?probe=2309c1e501) | Jan 28, 2022 |
| ASUSTek       | K50ID                       | [fed48cd01d](https://linux-hardware.org/?probe=fed48cd01d) | Jan 27, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | [32ad79e4bc](https://linux-hardware.org/?probe=32ad79e4bc) | Jan 27, 2022 |
| ASUSTek       | X550WA                      | [e146d6a0f8](https://linux-hardware.org/?probe=e146d6a0f8) | Jan 27, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9c8d4276ff](https://linux-hardware.org/?probe=9c8d4276ff) | Jan 27, 2022 |
| ASUSTek       | X555LD                      | [0665a1599c](https://linux-hardware.org/?probe=0665a1599c) | Jan 26, 2022 |
| Apple         | MacBookPro9,2               | [fb7312d608](https://linux-hardware.org/?probe=fb7312d608) | Jan 26, 2022 |
| Lenovo        | G40-80 80E4                 | [4c27ace709](https://linux-hardware.org/?probe=4c27ace709) | Jan 26, 2022 |
| Lenovo        | V130-15IGM 81HL             | [4a7b39821e](https://linux-hardware.org/?probe=4a7b39821e) | Jan 26, 2022 |
| Clevo         | W76x/M77xCUH                | [48d0efb057](https://linux-hardware.org/?probe=48d0efb057) | Jan 26, 2022 |
| Acer          | Nitro AN515-52              | [34c8096b74](https://linux-hardware.org/?probe=34c8096b74) | Jan 26, 2022 |
| Dell          | Inspiron 5570               | [db63ce439f](https://linux-hardware.org/?probe=db63ce439f) | Jan 26, 2022 |
| Dell          | XPS 15 7590                 | [f31c2dda65](https://linux-hardware.org/?probe=f31c2dda65) | Jan 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [992ccf1855](https://linux-hardware.org/?probe=992ccf1855) | Jan 26, 2022 |
| Samsung       | 935XDB                      | [ef096190b6](https://linux-hardware.org/?probe=ef096190b6) | Jan 26, 2022 |
| Acer          | Aspire A715-42G             | [b585a9d6bb](https://linux-hardware.org/?probe=b585a9d6bb) | Jan 26, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [115b4f412c](https://linux-hardware.org/?probe=115b4f412c) | Jan 25, 2022 |
| Packard Be... | EasyNote TE11BZ             | [1f3f4d2107](https://linux-hardware.org/?probe=1f3f4d2107) | Jan 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eed0593d0a](https://linux-hardware.org/?probe=eed0593d0a) | Jan 25, 2022 |
| Apple         | MacBook5,1                  | [0f6c39f50e](https://linux-hardware.org/?probe=0f6c39f50e) | Jan 25, 2022 |
| Dell          | Latitude E5530 non-vPro     | [16aeee2b77](https://linux-hardware.org/?probe=16aeee2b77) | Jan 24, 2022 |
| Dell          | Latitude E6420              | [027f726453](https://linux-hardware.org/?probe=027f726453) | Jan 24, 2022 |
| Framework     | Laptop                      | [99c660804f](https://linux-hardware.org/?probe=99c660804f) | Jan 24, 2022 |
| HP            | Pavilion 17                 | [d2c545576e](https://linux-hardware.org/?probe=d2c545576e) | Jan 24, 2022 |
| Lenovo        | ThinkPad E590 20NB0058RT    | [0b56eb1e6e](https://linux-hardware.org/?probe=0b56eb1e6e) | Jan 23, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [b59e4cbfef](https://linux-hardware.org/?probe=b59e4cbfef) | Jan 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [de23657e81](https://linux-hardware.org/?probe=de23657e81) | Jan 23, 2022 |
| Positivo      | Q464C                       | [c5fa0e3561](https://linux-hardware.org/?probe=c5fa0e3561) | Jan 23, 2022 |
| ASUSTek       | X450LD                      | [07edc503a1](https://linux-hardware.org/?probe=07edc503a1) | Jan 23, 2022 |
| Lenovo        | ThinkPad 20TDZMS            | [143bc3f79b](https://linux-hardware.org/?probe=143bc3f79b) | Jan 23, 2022 |
| Razer         | Blade 15 Advanced Model ... | [c07445f559](https://linux-hardware.org/?probe=c07445f559) | Jan 23, 2022 |
| Packard Be... | EasyNote TV44HC             | [38fb76e085](https://linux-hardware.org/?probe=38fb76e085) | Jan 23, 2022 |
| MSI           | GL65 Leopard 10SDR          | [db5f5da948](https://linux-hardware.org/?probe=db5f5da948) | Jan 23, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3363e2fdb0](https://linux-hardware.org/?probe=3363e2fdb0) | Jan 23, 2022 |
| Dell          | Latitude 7490               | [fea8be783a](https://linux-hardware.org/?probe=fea8be783a) | Jan 23, 2022 |
| Alienware     | 17 R4                       | [d82171f734](https://linux-hardware.org/?probe=d82171f734) | Jan 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [882dab7b0e](https://linux-hardware.org/?probe=882dab7b0e) | Jan 22, 2022 |
| Notebook      | N13xWU                      | [0d615c6812](https://linux-hardware.org/?probe=0d615c6812) | Jan 22, 2022 |
| Dell          | XPS 13 9305                 | [f5385f201e](https://linux-hardware.org/?probe=f5385f201e) | Jan 22, 2022 |
| Acer          | Swift SF314-43              | [567c5725d5](https://linux-hardware.org/?probe=567c5725d5) | Jan 22, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fa90e37c2d](https://linux-hardware.org/?probe=fa90e37c2d) | Jan 22, 2022 |
| Acer          | Swift SF315-41              | [95afa35615](https://linux-hardware.org/?probe=95afa35615) | Jan 22, 2022 |
| Lenovo        | G50-45 80MQ                 | [6a21be0bff](https://linux-hardware.org/?probe=6a21be0bff) | Jan 22, 2022 |
| Dell          | Studio 1737                 | [d2d85d9b73](https://linux-hardware.org/?probe=d2d85d9b73) | Jan 21, 2022 |
| Lenovo        | G580 2189                   | [3f1adf101d](https://linux-hardware.org/?probe=3f1adf101d) | Jan 21, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | [1d478097a3](https://linux-hardware.org/?probe=1d478097a3) | Jan 21, 2022 |
| Dell          | Precision 5550              | [d918e1f390](https://linux-hardware.org/?probe=d918e1f390) | Jan 21, 2022 |
| NCS-Tech      | ONE1                        | [409bede257](https://linux-hardware.org/?probe=409bede257) | Jan 21, 2022 |
| Dell          | Precision 5550              | [66ccaaa19f](https://linux-hardware.org/?probe=66ccaaa19f) | Jan 20, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [cdda13eba7](https://linux-hardware.org/?probe=cdda13eba7) | Jan 20, 2022 |
| Toshiba       | PORTEGE R930                | [1ee5471d24](https://linux-hardware.org/?probe=1ee5471d24) | Jan 20, 2022 |
| Timi          | A34R                        | [fcf594f19a](https://linux-hardware.org/?probe=fcf594f19a) | Jan 20, 2022 |
| Timi          | A34R                        | [046409a8e2](https://linux-hardware.org/?probe=046409a8e2) | Jan 20, 2022 |
| HUAWEI        | HVY-WXX9                    | [7926e3c998](https://linux-hardware.org/?probe=7926e3c998) | Jan 19, 2022 |
| HP            | Laptop 15s-fq1xxx           | [b48e7b60cd](https://linux-hardware.org/?probe=b48e7b60cd) | Jan 19, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [e5d8911653](https://linux-hardware.org/?probe=e5d8911653) | Jan 19, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [ca34cbdf64](https://linux-hardware.org/?probe=ca34cbdf64) | Jan 19, 2022 |
| HUAWEI        | MateBook X                  | [b8def0a48d](https://linux-hardware.org/?probe=b8def0a48d) | Jan 19, 2022 |
| HP            | EliteBook 1050 G1           | [1bb5cb826f](https://linux-hardware.org/?probe=1bb5cb826f) | Jan 19, 2022 |
| HP            | ProBook 6550b               | [d4ab3277b0](https://linux-hardware.org/?probe=d4ab3277b0) | Jan 19, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [cc39f1fd96](https://linux-hardware.org/?probe=cc39f1fd96) | Jan 18, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [3dc8b324bd](https://linux-hardware.org/?probe=3dc8b324bd) | Jan 18, 2022 |
| Clevo         | W251ESQ/W270ESQ             | [50380c8301](https://linux-hardware.org/?probe=50380c8301) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6fd36db1e0](https://linux-hardware.org/?probe=6fd36db1e0) | Jan 18, 2022 |
| LG Electro... | 16Z90P-K.AAB7U1             | [1cd8321a44](https://linux-hardware.org/?probe=1cd8321a44) | Jan 18, 2022 |
| MSI           | P65 Creator 9SE             | [da7b942050](https://linux-hardware.org/?probe=da7b942050) | Jan 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [ff8f10a4f3](https://linux-hardware.org/?probe=ff8f10a4f3) | Jan 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [4137cdd7e2](https://linux-hardware.org/?probe=4137cdd7e2) | Jan 17, 2022 |
| Dell          | XPS 13 7390                 | [0db509562e](https://linux-hardware.org/?probe=0db509562e) | Jan 17, 2022 |
| HP            | Laptop 15-dy2xxx            | [d3a7880a3c](https://linux-hardware.org/?probe=d3a7880a3c) | Jan 17, 2022 |
| Dell          | Inspiron 1545               | [3017de5307](https://linux-hardware.org/?probe=3017de5307) | Jan 17, 2022 |
| Lenovo        | ThinkPad T530 2359CTO       | [7e133f725e](https://linux-hardware.org/?probe=7e133f725e) | Jan 17, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [7cc691c557](https://linux-hardware.org/?probe=7cc691c557) | Jan 16, 2022 |
| Dell          | Inspiron 3501               | [898eb7ce85](https://linux-hardware.org/?probe=898eb7ce85) | Jan 16, 2022 |
| Acer          | Aspire E5-511               | [c2691bf00b](https://linux-hardware.org/?probe=c2691bf00b) | Jan 16, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [03293e9384](https://linux-hardware.org/?probe=03293e9384) | Jan 16, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [4dd3961675](https://linux-hardware.org/?probe=4dd3961675) | Jan 16, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [a1fffe7c0f](https://linux-hardware.org/?probe=a1fffe7c0f) | Jan 16, 2022 |
| HP            | Notebook                    | [5d45aad44f](https://linux-hardware.org/?probe=5d45aad44f) | Jan 16, 2022 |
| Timi          | A18R                        | [37b8388616](https://linux-hardware.org/?probe=37b8388616) | Jan 16, 2022 |
| Dell          | XPS 17 9710                 | [3417abe371](https://linux-hardware.org/?probe=3417abe371) | Jan 16, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6505        | [4ceae99710](https://linux-hardware.org/?probe=4ceae99710) | Jan 15, 2022 |
| Dell          | XPS 13 9305                 | [d6594c7edb](https://linux-hardware.org/?probe=d6594c7edb) | Jan 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [7b614a5d11](https://linux-hardware.org/?probe=7b614a5d11) | Jan 15, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [e37b97a3e7](https://linux-hardware.org/?probe=e37b97a3e7) | Jan 15, 2022 |
| Toshiba       | Satellite Pro L500          | [987c5a92d0](https://linux-hardware.org/?probe=987c5a92d0) | Jan 15, 2022 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [786f091b04](https://linux-hardware.org/?probe=786f091b04) | Jan 15, 2022 |
| Dell          | XPS 17 9710                 | [3d2a67265f](https://linux-hardware.org/?probe=3d2a67265f) | Jan 15, 2022 |
| Acer          | Aspire E5-553               | [71f81101f2](https://linux-hardware.org/?probe=71f81101f2) | Jan 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4ebb815948](https://linux-hardware.org/?probe=4ebb815948) | Jan 15, 2022 |
| Fujitsu       | LIFEBOOK UH572              | [b6e46bc4f5](https://linux-hardware.org/?probe=b6e46bc4f5) | Jan 15, 2022 |
| Fujitsu       | LIFEBOOK UH572              | [e82910b9d3](https://linux-hardware.org/?probe=e82910b9d3) | Jan 15, 2022 |
| Lenovo        | ThinkPad X240 20AMS4SL00    | [3888a941b9](https://linux-hardware.org/?probe=3888a941b9) | Jan 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [fb4c60c7b1](https://linux-hardware.org/?probe=fb4c60c7b1) | Jan 14, 2022 |
| Dell          | XPS 15 9500                 | [9a887349f4](https://linux-hardware.org/?probe=9a887349f4) | Jan 14, 2022 |
| Unknown       | Unknown                     | [4790b017ca](https://linux-hardware.org/?probe=4790b017ca) | Jan 14, 2022 |
| Lenovo        | ThinkPad X240 20AMS6170H    | [03fc719875](https://linux-hardware.org/?probe=03fc719875) | Jan 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [eee9a2ae45](https://linux-hardware.org/?probe=eee9a2ae45) | Jan 14, 2022 |
| Razer         | Blade 15 Advanced Model ... | [6f992c3b94](https://linux-hardware.org/?probe=6f992c3b94) | Jan 14, 2022 |
| Razer         | Blade 15 Advanced Model ... | [95724a0980](https://linux-hardware.org/?probe=95724a0980) | Jan 14, 2022 |
| Acer          | Predator PH317-52           | [1de1d4e14c](https://linux-hardware.org/?probe=1de1d4e14c) | Jan 14, 2022 |
| MSI           | GT70                        | [ae15bd941d](https://linux-hardware.org/?probe=ae15bd941d) | Jan 13, 2022 |
| Lenovo        | Z50-70 20354                | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEP... | [d57b07dcea](https://linux-hardware.org/?probe=d57b07dcea) | Jan 13, 2022 |
| Acer          | Aspire E5-553               | [622899f837](https://linux-hardware.org/?probe=622899f837) | Jan 13, 2022 |
| Acer          | Aspire E5-553               | [149c0538ca](https://linux-hardware.org/?probe=149c0538ca) | Jan 13, 2022 |
| Lenovo        | ThinkPad T480s 20L8S3FV0... | [78080db667](https://linux-hardware.org/?probe=78080db667) | Jan 13, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de24bac4e8](https://linux-hardware.org/?probe=de24bac4e8) | Jan 13, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [f7ea85c311](https://linux-hardware.org/?probe=f7ea85c311) | Jan 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [cbf786613d](https://linux-hardware.org/?probe=cbf786613d) | Jan 13, 2022 |
| Acer          | Aspire 5750G                | [dd5e1ff4bd](https://linux-hardware.org/?probe=dd5e1ff4bd) | Jan 13, 2022 |
| Dell          | Latitude 5290               | [f1c632a454](https://linux-hardware.org/?probe=f1c632a454) | Jan 12, 2022 |
| Dell          | Inspiron 5570               | [5f41c8e050](https://linux-hardware.org/?probe=5f41c8e050) | Jan 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [97274ab2da](https://linux-hardware.org/?probe=97274ab2da) | Jan 12, 2022 |
| Toshiba       | Satellite NB10t-A-103       | [9111c65725](https://linux-hardware.org/?probe=9111c65725) | Jan 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [7edab0851b](https://linux-hardware.org/?probe=7edab0851b) | Jan 12, 2022 |
| Fujitsu       | LIFEBOOK S782               | [054e0bda78](https://linux-hardware.org/?probe=054e0bda78) | Jan 11, 2022 |
| Unknown       | Unknown                     | [3c853ef1b3](https://linux-hardware.org/?probe=3c853ef1b3) | Jan 11, 2022 |
| Lenovo        | ThinkPad E490 20N8S11G00    | [9db0c57d6e](https://linux-hardware.org/?probe=9db0c57d6e) | Jan 11, 2022 |
| Acer          | Aspire A515-56              | [4b9aea4afc](https://linux-hardware.org/?probe=4b9aea4afc) | Jan 11, 2022 |
| Dell          | Precision 5510              | [4df6b95a0d](https://linux-hardware.org/?probe=4df6b95a0d) | Jan 11, 2022 |
| Dell          | Inspiron 3505               | [85c2838614](https://linux-hardware.org/?probe=85c2838614) | Jan 11, 2022 |
| HP            | EliteBook 8470p             | [55ac557cb2](https://linux-hardware.org/?probe=55ac557cb2) | Jan 11, 2022 |
| Dell          | XPS 13 9300                 | [72c9b73ff1](https://linux-hardware.org/?probe=72c9b73ff1) | Jan 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | [1e31796586](https://linux-hardware.org/?probe=1e31796586) | Jan 10, 2022 |
| MSI           | Prestige 14Evo A11MO        | [bc9be11aa0](https://linux-hardware.org/?probe=bc9be11aa0) | Jan 10, 2022 |
| HP            | 250 G7 Notebook PC          | [0bd99eab19](https://linux-hardware.org/?probe=0bd99eab19) | Jan 10, 2022 |
| Dell          | Inspiron 1720               | [e3e7fc8951](https://linux-hardware.org/?probe=e3e7fc8951) | Jan 10, 2022 |
| HP            | EliteBook 820 G1            | [03c6f51322](https://linux-hardware.org/?probe=03c6f51322) | Jan 09, 2022 |
| HP            | Notebook                    | [66028752f5](https://linux-hardware.org/?probe=66028752f5) | Jan 09, 2022 |
| Acer          | Predator PH317-52           | [d25b20faf0](https://linux-hardware.org/?probe=d25b20faf0) | Jan 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS2... | [9dce7e12db](https://linux-hardware.org/?probe=9dce7e12db) | Jan 08, 2022 |
| Dell          | Latitude 5420 Rugged        | [99d0d37d11](https://linux-hardware.org/?probe=99d0d37d11) | Jan 08, 2022 |
| Lenovo        | ThinkPad E590 20NB001WMC    | [f114fe6200](https://linux-hardware.org/?probe=f114fe6200) | Jan 08, 2022 |
| Dell          | XPS 13 9305                 | [83ccc00b28](https://linux-hardware.org/?probe=83ccc00b28) | Jan 08, 2022 |
| Dell          | Inspiron 1720               | [8c9acc1c52](https://linux-hardware.org/?probe=8c9acc1c52) | Jan 08, 2022 |
| Acer          | Predator PH317-52           | [4596b71283](https://linux-hardware.org/?probe=4596b71283) | Jan 08, 2022 |
| Razer         | Blade                       | [afad6aaa95](https://linux-hardware.org/?probe=afad6aaa95) | Jan 08, 2022 |
| HP            | EliteBook 8540p             | [20b9948e89](https://linux-hardware.org/?probe=20b9948e89) | Jan 08, 2022 |
| HP            | Laptop 15-db1xxx            | [28db094e56](https://linux-hardware.org/?probe=28db094e56) | Jan 08, 2022 |
| HP            | ZBook 15v G5                | [f529eb1829](https://linux-hardware.org/?probe=f529eb1829) | Jan 08, 2022 |
| HP            | ZBook 15v G5                | [5d912e6781](https://linux-hardware.org/?probe=5d912e6781) | Jan 08, 2022 |
| Acer          | Aspire 5750G                | [088c5ba19e](https://linux-hardware.org/?probe=088c5ba19e) | Jan 08, 2022 |
| Acer          | Aspire 5750G                | [b4a8ca7f90](https://linux-hardware.org/?probe=b4a8ca7f90) | Jan 08, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [103f52795a](https://linux-hardware.org/?probe=103f52795a) | Jan 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f85ea7cd3a](https://linux-hardware.org/?probe=f85ea7cd3a) | Jan 07, 2022 |
| Dell          | XPS 15 7590                 | [26bd64900c](https://linux-hardware.org/?probe=26bd64900c) | Jan 07, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [c87cec55bd](https://linux-hardware.org/?probe=c87cec55bd) | Jan 07, 2022 |
| HONOR         | NBR-WAX9                    | [979f80197d](https://linux-hardware.org/?probe=979f80197d) | Jan 07, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [656596c5c0](https://linux-hardware.org/?probe=656596c5c0) | Jan 07, 2022 |
| HP            | EliteBook 2740p             | [eaaa9e2ef5](https://linux-hardware.org/?probe=eaaa9e2ef5) | Jan 07, 2022 |
| HP            | Laptop 15-dw3xxx            | [07acd8ae78](https://linux-hardware.org/?probe=07acd8ae78) | Jan 07, 2022 |
| KOGAN         | KAL11C250SB                 | [a153354498](https://linux-hardware.org/?probe=a153354498) | Jan 07, 2022 |
| Dell          | Inspiron 3585               | [bd035d052c](https://linux-hardware.org/?probe=bd035d052c) | Jan 07, 2022 |
| Dell          | Latitude 5480               | [25e067d7cd](https://linux-hardware.org/?probe=25e067d7cd) | Jan 06, 2022 |
| Dell          | Latitude 5480               | [d53f380ad3](https://linux-hardware.org/?probe=d53f380ad3) | Jan 06, 2022 |
| HP            | ProBook 4510s               | [50904e6b69](https://linux-hardware.org/?probe=50904e6b69) | Jan 06, 2022 |
| Lenovo        | ThinkPad L380 20M6S1VV00    | [bc4fe37053](https://linux-hardware.org/?probe=bc4fe37053) | Jan 06, 2022 |
| Dell          | G7 7700                     | [f02bcbdcfe](https://linux-hardware.org/?probe=f02bcbdcfe) | Jan 06, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [3412915dd0](https://linux-hardware.org/?probe=3412915dd0) | Jan 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [7ff88b76ff](https://linux-hardware.org/?probe=7ff88b76ff) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | [097edea6f9](https://linux-hardware.org/?probe=097edea6f9) | Jan 06, 2022 |
| Toshiba       | PORTEGE R830                | [3b3c03d206](https://linux-hardware.org/?probe=3b3c03d206) | Jan 06, 2022 |
| Lenovo        | G50-80 80L0                 | [1af76e03c5](https://linux-hardware.org/?probe=1af76e03c5) | Jan 06, 2022 |
| Acer          | Aspire A315-42              | [b2d5bf7483](https://linux-hardware.org/?probe=b2d5bf7483) | Jan 06, 2022 |
| Lenovo        | G50-70 20351                | [5467cc6a24](https://linux-hardware.org/?probe=5467cc6a24) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [66c455085b](https://linux-hardware.org/?probe=66c455085b) | Jan 05, 2022 |
| Sony          | VPCF130FD                   | [f83b105795](https://linux-hardware.org/?probe=f83b105795) | Jan 04, 2022 |
| Toshiba       | PORTEGE R830                | [41ed435a4f](https://linux-hardware.org/?probe=41ed435a4f) | Jan 04, 2022 |
| HP            | ProBook 440 G7              | [e5806fd9d0](https://linux-hardware.org/?probe=e5806fd9d0) | Jan 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [4dbb6731ed](https://linux-hardware.org/?probe=4dbb6731ed) | Jan 04, 2022 |
| HP            | EliteBook 2740p             | [339900943a](https://linux-hardware.org/?probe=339900943a) | Jan 04, 2022 |
| Dell          | XPS 13 9380                 | [c3eb7aacda](https://linux-hardware.org/?probe=c3eb7aacda) | Jan 04, 2022 |
| Dell          | XPS 13 9380                 | [52c3af4003](https://linux-hardware.org/?probe=52c3af4003) | Jan 04, 2022 |
| Acer          | Aspire 8730                 | [b2f2a7f746](https://linux-hardware.org/?probe=b2f2a7f746) | Jan 03, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d8b53c12c7](https://linux-hardware.org/?probe=d8b53c12c7) | Jan 03, 2022 |
| Samsung       | 750XBE/730XBE               | [5608016bcb](https://linux-hardware.org/?probe=5608016bcb) | Jan 03, 2022 |
| Medion        | S6421 MD61010               | [88c3c7c11b](https://linux-hardware.org/?probe=88c3c7c11b) | Jan 03, 2022 |
| Sony          | VGN-AR61E                   | [3068c7aa95](https://linux-hardware.org/?probe=3068c7aa95) | Jan 03, 2022 |
| MSI           | GT70 2PC                    | [61a5023d6a](https://linux-hardware.org/?probe=61a5023d6a) | Jan 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [5dd20e2872](https://linux-hardware.org/?probe=5dd20e2872) | Jan 03, 2022 |
| Apple         | MacBookAir7,2               | [4e7a5311a7](https://linux-hardware.org/?probe=4e7a5311a7) | Jan 03, 2022 |
| HP            | Laptop 15-dy2xxx            | [86af58375a](https://linux-hardware.org/?probe=86af58375a) | Jan 03, 2022 |
| Lenovo        | ThinkPad P50 20EQS6J100     | [f366de3acf](https://linux-hardware.org/?probe=f366de3acf) | Jan 03, 2022 |
| Samsung       | NC210/NC110                 | [ccee740b06](https://linux-hardware.org/?probe=ccee740b06) | Jan 02, 2022 |
| HP            | ENVY 17                     | [bd8db07a0a](https://linux-hardware.org/?probe=bd8db07a0a) | Jan 02, 2022 |
| Wortmann      | TERRA_MOBILE_1512/1712      | [014c0d6df9](https://linux-hardware.org/?probe=014c0d6df9) | Jan 02, 2022 |
| Samsung       | NC210/NC110                 | [de9e54be88](https://linux-hardware.org/?probe=de9e54be88) | Jan 02, 2022 |
| HP            | ENVY 17                     | [a140a1a272](https://linux-hardware.org/?probe=a140a1a272) | Jan 02, 2022 |
| Teclast       | F15 Plus                    | [48888c4e5a](https://linux-hardware.org/?probe=48888c4e5a) | Jan 02, 2022 |
| Dell          | XPS 15 7590                 | [3299ab62e8](https://linux-hardware.org/?probe=3299ab62e8) | Jan 02, 2022 |
| ASUSTek       | K52F                        | [3d895c327a](https://linux-hardware.org/?probe=3d895c327a) | Jan 01, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [cbceb1c15b](https://linux-hardware.org/?probe=cbceb1c15b) | Jan 01, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [42b1c43334](https://linux-hardware.org/?probe=42b1c43334) | Jan 01, 2022 |
| ASUSTek       | G550JK                      | [b26b378274](https://linux-hardware.org/?probe=b26b378274) | Jan 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3fc1d4b98d](https://linux-hardware.org/?probe=3fc1d4b98d) | Dec 31, 2021 |
| Samsung       | NC210/NC110                 | [4d26b14130](https://linux-hardware.org/?probe=4d26b14130) | Dec 31, 2021 |
| Samsung       | NC210/NC110                 | [bb92ee12a5](https://linux-hardware.org/?probe=bb92ee12a5) | Dec 31, 2021 |
| HP            | EliteBook 840 G2            | [3e2bf79497](https://linux-hardware.org/?probe=3e2bf79497) | Dec 31, 2021 |
| Lenovo        | ThinkPad T440s 20ARS05V0... | [7c496e685d](https://linux-hardware.org/?probe=7c496e685d) | Dec 31, 2021 |
| Acer          | Aspire 5920                 | [b492dec09b](https://linux-hardware.org/?probe=b492dec09b) | Dec 31, 2021 |
| Dell          | XPS 13 9300                 | [50206d4c03](https://linux-hardware.org/?probe=50206d4c03) | Dec 30, 2021 |
| Medion        | E6224                       | [4ebf65b683](https://linux-hardware.org/?probe=4ebf65b683) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [c14a0f6bed](https://linux-hardware.org/?probe=c14a0f6bed) | Dec 30, 2021 |
| Lenovo        | G40-80 80E4                 | [993fe7cef6](https://linux-hardware.org/?probe=993fe7cef6) | Dec 30, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| Dell          | XPS 17 9710                 | [cf5002d9df](https://linux-hardware.org/?probe=cf5002d9df) | Dec 29, 2021 |
| Lenovo        | V330-14ARR 81B1             | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Acer          | Predator G3-572             | [87dc579598](https://linux-hardware.org/?probe=87dc579598) | Dec 29, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [33b1bcf72f](https://linux-hardware.org/?probe=33b1bcf72f) | Dec 29, 2021 |
| Dell          | G3 3579                     | [873c470afd](https://linux-hardware.org/?probe=873c470afd) | Dec 29, 2021 |
| Dell          | Latitude 5420               | [42e63fd746](https://linux-hardware.org/?probe=42e63fd746) | Dec 29, 2021 |
| Dell          | Inspiron 1720               | [b40685ea7b](https://linux-hardware.org/?probe=b40685ea7b) | Dec 29, 2021 |
| Dell          | Latitude 5420               | [ae4bf2544b](https://linux-hardware.org/?probe=ae4bf2544b) | Dec 29, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [484cb2f9cf](https://linux-hardware.org/?probe=484cb2f9cf) | Dec 29, 2021 |
| HP            | Pavilion g7                 | [751d37e5fd](https://linux-hardware.org/?probe=751d37e5fd) | Dec 29, 2021 |
| Lenovo        | Ducati 5 82ES               | [646ce5947c](https://linux-hardware.org/?probe=646ce5947c) | Dec 28, 2021 |
| HUAWEI        | KLVL-WXX9                   | [88344cd6d3](https://linux-hardware.org/?probe=88344cd6d3) | Dec 28, 2021 |
| Lenovo        | Ducati 5 82ES               | [f53e88bfa4](https://linux-hardware.org/?probe=f53e88bfa4) | Dec 28, 2021 |
| Lenovo        | V330-15IKB 81AX             | [f68615959b](https://linux-hardware.org/?probe=f68615959b) | Dec 28, 2021 |
| Dell          | Latitude 5410               | [0e38439f9e](https://linux-hardware.org/?probe=0e38439f9e) | Dec 28, 2021 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [a4a4581b6d](https://linux-hardware.org/?probe=a4a4581b6d) | Dec 28, 2021 |
| Dell          | Inspiron 5537               | [f29a5f0ecb](https://linux-hardware.org/?probe=f29a5f0ecb) | Dec 28, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [a9e50f6f42](https://linux-hardware.org/?probe=a9e50f6f42) | Dec 28, 2021 |
| Acidanther... | MacBookPro12,1              | [82e00560e5](https://linux-hardware.org/?probe=82e00560e5) | Dec 28, 2021 |
| Dell          | Latitude E7470              | [55e3078baf](https://linux-hardware.org/?probe=55e3078baf) | Dec 28, 2021 |
| Google        | Akemi                       | [b2edfd3821](https://linux-hardware.org/?probe=b2edfd3821) | Dec 28, 2021 |
| HP            | ProBook 6450b               | [3b1bcce13d](https://linux-hardware.org/?probe=3b1bcce13d) | Dec 28, 2021 |
| eMachines     | E525                        | [fd80580005](https://linux-hardware.org/?probe=fd80580005) | Dec 28, 2021 |
| Sony          | VPCEL1E1E                   | [4deb7655c4](https://linux-hardware.org/?probe=4deb7655c4) | Dec 27, 2021 |
| Avell High... | A70 MOB                     | [dac7555e81](https://linux-hardware.org/?probe=dac7555e81) | Dec 27, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [938d24e76e](https://linux-hardware.org/?probe=938d24e76e) | Dec 27, 2021 |
| Acer          | Predator G3-572             | [ea72b1c252](https://linux-hardware.org/?probe=ea72b1c252) | Dec 27, 2021 |
| Acer          | Aspire ES1-132              | [bb6f2edc27](https://linux-hardware.org/?probe=bb6f2edc27) | Dec 27, 2021 |
| MSI           | GL62M 7RDX                  | [3f8cb0706d](https://linux-hardware.org/?probe=3f8cb0706d) | Dec 27, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [6a4ffab5ad](https://linux-hardware.org/?probe=6a4ffab5ad) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | [1b74edca8c](https://linux-hardware.org/?probe=1b74edca8c) | Dec 27, 2021 |
| Sony          | VGN-CS320J                  | [2dbfd6ad98](https://linux-hardware.org/?probe=2dbfd6ad98) | Dec 27, 2021 |
| Dell          | Inspiron 3543               | [30756486fd](https://linux-hardware.org/?probe=30756486fd) | Dec 26, 2021 |
| Dell          | Precision M6700             | [5a31793e53](https://linux-hardware.org/?probe=5a31793e53) | Dec 26, 2021 |
| Acer          | Aspire 5750G                | [052954142f](https://linux-hardware.org/?probe=052954142f) | Dec 26, 2021 |
| ASUSTek       | X550CL                      | [4eb9e6a01b](https://linux-hardware.org/?probe=4eb9e6a01b) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [92f264978e](https://linux-hardware.org/?probe=92f264978e) | Dec 25, 2021 |
| Acer          | Swift SF315-41              | [d94d38f29b](https://linux-hardware.org/?probe=d94d38f29b) | Dec 25, 2021 |
| ASUSTek       | X705NC                      | [c3cdc81bd8](https://linux-hardware.org/?probe=c3cdc81bd8) | Dec 25, 2021 |
| Lenovo        | ThinkPad T14s 20UJ0014FR    | [e7ccf2fa85](https://linux-hardware.org/?probe=e7ccf2fa85) | Dec 25, 2021 |
| eMachines     | E525                        | [fcc3b2a5e3](https://linux-hardware.org/?probe=fcc3b2a5e3) | Dec 25, 2021 |
| eMachines     | E525                        | [e5853e5629](https://linux-hardware.org/?probe=e5853e5629) | Dec 25, 2021 |
| HP            | EliteBook 840 G3            | [d149e3e8cd](https://linux-hardware.org/?probe=d149e3e8cd) | Dec 24, 2021 |
| Dell          | Inspiron N5050              | [df6e5df46d](https://linux-hardware.org/?probe=df6e5df46d) | Dec 24, 2021 |
| Sony          | VPCEA3S1E                   | [15bf845627](https://linux-hardware.org/?probe=15bf845627) | Dec 24, 2021 |
| HP            | EliteBook 840 G2            | [2be9e8fd67](https://linux-hardware.org/?probe=2be9e8fd67) | Dec 23, 2021 |
| HP            | EliteBook 840 G2            | [024febade8](https://linux-hardware.org/?probe=024febade8) | Dec 23, 2021 |
| Dell          | Inspiron 1720               | [6d1e22e244](https://linux-hardware.org/?probe=6d1e22e244) | Dec 23, 2021 |
| HP            | ENVY 17                     | [1601038695](https://linux-hardware.org/?probe=1601038695) | Dec 23, 2021 |
| Samsung       | 700T                        | [dcd96a051e](https://linux-hardware.org/?probe=dcd96a051e) | Dec 23, 2021 |
| HP            | ProBook 6450b               | [da7840b49c](https://linux-hardware.org/?probe=da7840b49c) | Dec 23, 2021 |
| HP            | ProBook 6450b               | [0bad0405df](https://linux-hardware.org/?probe=0bad0405df) | Dec 23, 2021 |
| Apple         | MacBookPro11,1              | [187a32ebb8](https://linux-hardware.org/?probe=187a32ebb8) | Dec 23, 2021 |
| Schenker T... | VIA13                       | [91faaef5d1](https://linux-hardware.org/?probe=91faaef5d1) | Dec 22, 2021 |
| ASUSTek       | TP300LD                     | [b6a5dd1c92](https://linux-hardware.org/?probe=b6a5dd1c92) | Dec 22, 2021 |
| ASUSTek       | TP300LD                     | [7c11fdeeeb](https://linux-hardware.org/?probe=7c11fdeeeb) | Dec 22, 2021 |
| MSI           | GF65 Thin 9SEXR             | [2be4e41c8e](https://linux-hardware.org/?probe=2be4e41c8e) | Dec 22, 2021 |
| HP            | Pavilion g7                 | [68d9fe0608](https://linux-hardware.org/?probe=68d9fe0608) | Dec 22, 2021 |
| Sony          | VGN-CS320J                  | [9f1e770843](https://linux-hardware.org/?probe=9f1e770843) | Dec 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [985fc37716](https://linux-hardware.org/?probe=985fc37716) | Dec 22, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [40282bb1fd](https://linux-hardware.org/?probe=40282bb1fd) | Dec 21, 2021 |
| Dell          | Latitude E6400              | [e09bc74c03](https://linux-hardware.org/?probe=e09bc74c03) | Dec 21, 2021 |
| Dell          | Latitude E6400              | [b4e84b9759](https://linux-hardware.org/?probe=b4e84b9759) | Dec 21, 2021 |
| Sony          | VPCEA3S1E                   | [17a79ba919](https://linux-hardware.org/?probe=17a79ba919) | Dec 21, 2021 |
| Acer          | Swift SF114-34              | [84c382b787](https://linux-hardware.org/?probe=84c382b787) | Dec 21, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [13ec8a9420](https://linux-hardware.org/?probe=13ec8a9420) | Dec 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | [5408a1a82b](https://linux-hardware.org/?probe=5408a1a82b) | Dec 21, 2021 |
| Toshiba       | Satellite C55-B             | [fb0b43fb55](https://linux-hardware.org/?probe=fb0b43fb55) | Dec 21, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [0e34c5b120](https://linux-hardware.org/?probe=0e34c5b120) | Dec 21, 2021 |
| Acer          | Aspire V5-531               | [0a0ee7ecaf](https://linux-hardware.org/?probe=0a0ee7ecaf) | Dec 20, 2021 |
| Dell          | Latitude 5400               | [692bc521a6](https://linux-hardware.org/?probe=692bc521a6) | Dec 20, 2021 |
| Sony          | VGN-CS320J                  | [7143ced3cd](https://linux-hardware.org/?probe=7143ced3cd) | Dec 20, 2021 |
| Dell          | XPS 15 9500                 | [e5592dfde0](https://linux-hardware.org/?probe=e5592dfde0) | Dec 20, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [d14536043e](https://linux-hardware.org/?probe=d14536043e) | Dec 20, 2021 |
| MSI           | GS66 Stealth 11UE           | [ab09d4463d](https://linux-hardware.org/?probe=ab09d4463d) | Dec 20, 2021 |
| Dell          | G15 5510                    | [1209f0844f](https://linux-hardware.org/?probe=1209f0844f) | Dec 20, 2021 |
| Acer          | TravelMate8472TG            | [28362377e3](https://linux-hardware.org/?probe=28362377e3) | Dec 20, 2021 |
| Acer          | Swift SF114-34              | [f7d3352cbc](https://linux-hardware.org/?probe=f7d3352cbc) | Dec 19, 2021 |
| Samsung       | 270E5J/2570EJ               | [a15986fe04](https://linux-hardware.org/?probe=a15986fe04) | Dec 19, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| HUAWEI        | MACH-WX9                    | [033e872459](https://linux-hardware.org/?probe=033e872459) | Dec 19, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [79165f1ffe](https://linux-hardware.org/?probe=79165f1ffe) | Dec 19, 2021 |
| Schenker      | XMG CORE (REN/E21)          | [8fc46b7322](https://linux-hardware.org/?probe=8fc46b7322) | Dec 19, 2021 |
| Samsung       | R430/P430/R480              | [a45bad76ae](https://linux-hardware.org/?probe=a45bad76ae) | Dec 19, 2021 |
| HP            | Pavilion dv7                | [bfc5e45295](https://linux-hardware.org/?probe=bfc5e45295) | Dec 19, 2021 |
| HP            | Pavilion dv7                | [184202cc4e](https://linux-hardware.org/?probe=184202cc4e) | Dec 19, 2021 |
| HP            | Presario CQ61               | [de2053aa1e](https://linux-hardware.org/?probe=de2053aa1e) | Dec 19, 2021 |
| MSI           | GT80 2QC                    | [68b70c6ff9](https://linux-hardware.org/?probe=68b70c6ff9) | Dec 19, 2021 |
| Lenovo        | ThinkPad E495 20NECTO1WW    | [515a90b57b](https://linux-hardware.org/?probe=515a90b57b) | Dec 18, 2021 |
| Fujitsu       | LIFEBOOK S782               | [2fed9ebf97](https://linux-hardware.org/?probe=2fed9ebf97) | Dec 18, 2021 |
| HP            | Pro x2 612 G1 Tablet        | [ec2c4c7d27](https://linux-hardware.org/?probe=ec2c4c7d27) | Dec 18, 2021 |
| Dell          | G15 5510                    | [e5039b3b7d](https://linux-hardware.org/?probe=e5039b3b7d) | Dec 18, 2021 |
| Dell          | Inspiron 5515               | [2e61608393](https://linux-hardware.org/?probe=2e61608393) | Dec 18, 2021 |
| Dell          | Precision 5520              | [2b76ccd66c](https://linux-hardware.org/?probe=2b76ccd66c) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | [36aea8dc19](https://linux-hardware.org/?probe=36aea8dc19) | Dec 18, 2021 |
| MSI           | Katana GF66 11UE            | [56be528067](https://linux-hardware.org/?probe=56be528067) | Dec 18, 2021 |
| Acer          | Swift SF314-51              | [6b157ea1d6](https://linux-hardware.org/?probe=6b157ea1d6) | Dec 18, 2021 |
| Dell          | XPS 15 9500                 | [7bb94e89f6](https://linux-hardware.org/?probe=7bb94e89f6) | Dec 18, 2021 |
| Dell          | 500                         | [b0e7e6d913](https://linux-hardware.org/?probe=b0e7e6d913) | Dec 17, 2021 |
| ASUSTek       | T300CHI                     | [87feb239ae](https://linux-hardware.org/?probe=87feb239ae) | Dec 17, 2021 |
| Apple         | MacBookPro5,5               | [5de20fd13d](https://linux-hardware.org/?probe=5de20fd13d) | Dec 17, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [3f89172d4b](https://linux-hardware.org/?probe=3f89172d4b) | Dec 17, 2021 |
| HUAWEI        | KLVL-WXX9                   | [99473bac5d](https://linux-hardware.org/?probe=99473bac5d) | Dec 17, 2021 |
| Acer          | Aspire A515-56              | [a50b285530](https://linux-hardware.org/?probe=a50b285530) | Dec 17, 2021 |
| Sony          | SVF1521L6EW                 | [64160de19b](https://linux-hardware.org/?probe=64160de19b) | Dec 17, 2021 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [6ac6be1d38](https://linux-hardware.org/?probe=6ac6be1d38) | Dec 17, 2021 |
| Dell          | Latitude 5420 Rugged        | [34eebffb9b](https://linux-hardware.org/?probe=34eebffb9b) | Dec 17, 2021 |
| Dell          | Latitude 7389               | [9c25379d7d](https://linux-hardware.org/?probe=9c25379d7d) | Dec 16, 2021 |
| Dell          | Latitude 5420 Rugged        | [e5337761c4](https://linux-hardware.org/?probe=e5337761c4) | Dec 16, 2021 |
| Alienware     | 17 R5                       | [8a377c49a4](https://linux-hardware.org/?probe=8a377c49a4) | Dec 16, 2021 |
| Fujitsu       | LIFEBOOK E752               | [0b84572cff](https://linux-hardware.org/?probe=0b84572cff) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [6e8ba23594](https://linux-hardware.org/?probe=6e8ba23594) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | [70a9d341b1](https://linux-hardware.org/?probe=70a9d341b1) | Dec 16, 2021 |
| Wortmann      | 1220679_1470212             | [798fc3faee](https://linux-hardware.org/?probe=798fc3faee) | Dec 16, 2021 |
| HP            | EliteBook 840 G6            | [46dab8c74a](https://linux-hardware.org/?probe=46dab8c74a) | Dec 16, 2021 |
| ASUSTek       | X550VX                      | [db3cd6403d](https://linux-hardware.org/?probe=db3cd6403d) | Dec 16, 2021 |
| Acer          | Swift SF314-51              | [3a62e5502b](https://linux-hardware.org/?probe=3a62e5502b) | Dec 15, 2021 |
| Dell          | Vostro 5402                 | [2cc6e5b35b](https://linux-hardware.org/?probe=2cc6e5b35b) | Dec 15, 2021 |
| Dell          | Latitude E6400              | [2936dcb6ab](https://linux-hardware.org/?probe=2936dcb6ab) | Dec 14, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [0705e530b4](https://linux-hardware.org/?probe=0705e530b4) | Dec 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9b89720cb4](https://linux-hardware.org/?probe=9b89720cb4) | Dec 14, 2021 |
| Sony          | VPCF130FD                   | [4ff7ca9b6c](https://linux-hardware.org/?probe=4ff7ca9b6c) | Dec 14, 2021 |
| Lenovo        | ThinkPad T430 2349MMS       | [191acd1645](https://linux-hardware.org/?probe=191acd1645) | Dec 14, 2021 |
| HP            | ProBook 4530s               | [0003fe091b](https://linux-hardware.org/?probe=0003fe091b) | Dec 14, 2021 |
| Lenovo        | V15 G2 ALC 82KD             | [d391c926e7](https://linux-hardware.org/?probe=d391c926e7) | Dec 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a22c6968b8](https://linux-hardware.org/?probe=a22c6968b8) | Dec 13, 2021 |
| Toshiba       | Satellite L755              | [62e66068da](https://linux-hardware.org/?probe=62e66068da) | Dec 13, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [2e8509fb8b](https://linux-hardware.org/?probe=2e8509fb8b) | Dec 12, 2021 |
| HP            | EliteBook 725 G3            | [88a4be9c2e](https://linux-hardware.org/?probe=88a4be9c2e) | Dec 12, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [3228031778](https://linux-hardware.org/?probe=3228031778) | Dec 12, 2021 |
| HP            | ZBook 15 G6                 | [b241f46e61](https://linux-hardware.org/?probe=b241f46e61) | Dec 12, 2021 |
| HP            | Laptop 14-cf0xxx            | [2f4ec869f9](https://linux-hardware.org/?probe=2f4ec869f9) | Dec 12, 2021 |
| Framework     | Laptop                      | [3f9c87fb23](https://linux-hardware.org/?probe=3f9c87fb23) | Dec 12, 2021 |
| Dell          | XPS 17 9700                 | [eef9ef9d60](https://linux-hardware.org/?probe=eef9ef9d60) | Dec 12, 2021 |
| Dell          | Inspiron 3501               | [3b33dbdc6b](https://linux-hardware.org/?probe=3b33dbdc6b) | Dec 12, 2021 |
| Lenovo        | Z50-75 80EC                 | [94bfedf240](https://linux-hardware.org/?probe=94bfedf240) | Dec 11, 2021 |
| Acer          | ConceptD CN315-71P          | [ac834a5768](https://linux-hardware.org/?probe=ac834a5768) | Dec 11, 2021 |
| Dell          | Inspiron 3501               | [61e912c283](https://linux-hardware.org/?probe=61e912c283) | Dec 11, 2021 |
| HP            | ProBook 440 G6              | [b7313134e3](https://linux-hardware.org/?probe=b7313134e3) | Dec 11, 2021 |
| Dell          | Inspiron 3421               | [b18adbf17f](https://linux-hardware.org/?probe=b18adbf17f) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5740d7d60c](https://linux-hardware.org/?probe=5740d7d60c) | Dec 11, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [22eeff89e5](https://linux-hardware.org/?probe=22eeff89e5) | Dec 11, 2021 |
| Dell          | Latitude 7370               | [d2bbf57105](https://linux-hardware.org/?probe=d2bbf57105) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK AH530/HD6          | [232b26315a](https://linux-hardware.org/?probe=232b26315a) | Dec 10, 2021 |
| Toshiba       | PORTEGE A600                | [7a5e987cb3](https://linux-hardware.org/?probe=7a5e987cb3) | Dec 10, 2021 |
| Dell          | Inspiron 13 5310            | [70a974c325](https://linux-hardware.org/?probe=70a974c325) | Dec 10, 2021 |
| Dell          | Latitude 9420               | [5e00e700d4](https://linux-hardware.org/?probe=5e00e700d4) | Dec 10, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [bb53c502d7](https://linux-hardware.org/?probe=bb53c502d7) | Dec 09, 2021 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [45674cbd76](https://linux-hardware.org/?probe=45674cbd76) | Dec 09, 2021 |
| Samsung       | 750XDA                      | [30d61197a1](https://linux-hardware.org/?probe=30d61197a1) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [bb9141f09c](https://linux-hardware.org/?probe=bb9141f09c) | Dec 09, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [b3c42ca2c2](https://linux-hardware.org/?probe=b3c42ca2c2) | Dec 09, 2021 |
| YJKC          | vBOOK Plus RVP7             | [5a0e887e34](https://linux-hardware.org/?probe=5a0e887e34) | Dec 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [e82de9b10d](https://linux-hardware.org/?probe=e82de9b10d) | Dec 09, 2021 |
| Dell          | Inspiron 7472               | [64b7b3a797](https://linux-hardware.org/?probe=64b7b3a797) | Dec 09, 2021 |
| HP            | Pavilion dv6                | [46ad5598d6](https://linux-hardware.org/?probe=46ad5598d6) | Dec 09, 2021 |
| HP            | Pavilion dv6                | [6bc2a41542](https://linux-hardware.org/?probe=6bc2a41542) | Dec 09, 2021 |
| Razer         | Blade 15 Advanced Model ... | [ccc253bb9a](https://linux-hardware.org/?probe=ccc253bb9a) | Dec 08, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [e3be4cf88c](https://linux-hardware.org/?probe=e3be4cf88c) | Dec 08, 2021 |
| Toshiba       | PORTEGE A600                | [2ecaddef09](https://linux-hardware.org/?probe=2ecaddef09) | Dec 08, 2021 |
| Lenovo        | ThinkPad T520 4243CJ2       | [15d1aafe1d](https://linux-hardware.org/?probe=15d1aafe1d) | Dec 08, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [98f25277f5](https://linux-hardware.org/?probe=98f25277f5) | Dec 08, 2021 |
| Avell High... | B.ON                        | [5bfb9e677a](https://linux-hardware.org/?probe=5bfb9e677a) | Dec 07, 2021 |
| Avell High... | B.ON                        | [d2b832ea0a](https://linux-hardware.org/?probe=d2b832ea0a) | Dec 07, 2021 |
| Toshiba       | Satellite Pro L650          | [fd40a9d639](https://linux-hardware.org/?probe=fd40a9d639) | Dec 07, 2021 |
| Dell          | Inspiron 5775               | [60c2ee09f1](https://linux-hardware.org/?probe=60c2ee09f1) | Dec 07, 2021 |
| Dell          | Inspiron 14-3467            | [c53e56384e](https://linux-hardware.org/?probe=c53e56384e) | Dec 07, 2021 |
| Dell          | Latitude E7470              | [06666f541b](https://linux-hardware.org/?probe=06666f541b) | Dec 07, 2021 |
| Lenovo        | ThinkPad T440 20B7S06M00    | [66c0123f35](https://linux-hardware.org/?probe=66c0123f35) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | [d25b1846ff](https://linux-hardware.org/?probe=d25b1846ff) | Dec 07, 2021 |
| Acer          | Aspire E5-511               | [9e8fd519f0](https://linux-hardware.org/?probe=9e8fd519f0) | Dec 07, 2021 |
| Sony          | SVF14211CLB                 | [41bfe6e292](https://linux-hardware.org/?probe=41bfe6e292) | Dec 06, 2021 |
| HP            | Pavilion dv6                | [38e3ffa8ec](https://linux-hardware.org/?probe=38e3ffa8ec) | Dec 06, 2021 |
| HP            | Pavilion dv6                | [c0ecac4d9e](https://linux-hardware.org/?probe=c0ecac4d9e) | Dec 06, 2021 |
| Acer          | Swift SF314-51              | [8d158d2fb2](https://linux-hardware.org/?probe=8d158d2fb2) | Dec 06, 2021 |
| HP            | ENVY dv7                    | [1ab140a424](https://linux-hardware.org/?probe=1ab140a424) | Dec 06, 2021 |
| Dell          | Latitude E6410              | [69e0c044fe](https://linux-hardware.org/?probe=69e0c044fe) | Dec 06, 2021 |
| Packard Be... | EasyNote TJ66               | [8083f4fc11](https://linux-hardware.org/?probe=8083f4fc11) | Dec 06, 2021 |
| Acer          | Swift SF314-43              | [ed43af14cf](https://linux-hardware.org/?probe=ed43af14cf) | Dec 06, 2021 |
| Acer          | Aspire 7715Z                | [8124f61a3f](https://linux-hardware.org/?probe=8124f61a3f) | Dec 06, 2021 |
| Dell          | Venue 11 Pro 7140           | [2cda03e17b](https://linux-hardware.org/?probe=2cda03e17b) | Dec 06, 2021 |
| Dell          | Latitude E6410              | [0b4762f0fd](https://linux-hardware.org/?probe=0b4762f0fd) | Dec 05, 2021 |
| Acer          | Aspire VN7-792G             | [4cbc6b946a](https://linux-hardware.org/?probe=4cbc6b946a) | Dec 05, 2021 |
| HP            | 15 Notebook PC              | [88f8ff50c8](https://linux-hardware.org/?probe=88f8ff50c8) | Dec 05, 2021 |
| ASUSTek       | Vivobook_ASUSLaptop X740... | [9bbc3af34c](https://linux-hardware.org/?probe=9bbc3af34c) | Dec 05, 2021 |
| Google        | Rammus                      | [5cdd87fe56](https://linux-hardware.org/?probe=5cdd87fe56) | Dec 04, 2021 |
| HP            | EliteBook 8460p             | [0dc1338ba5](https://linux-hardware.org/?probe=0dc1338ba5) | Dec 04, 2021 |
| Toshiba       | Satellite C50-A489          | [4d29ea3b9c](https://linux-hardware.org/?probe=4d29ea3b9c) | Dec 04, 2021 |
| Avell High... | B.ON                        | [91a81934ed](https://linux-hardware.org/?probe=91a81934ed) | Dec 04, 2021 |
| ASUSTek       | X505BA                      | [ed64395695](https://linux-hardware.org/?probe=ed64395695) | Dec 04, 2021 |
| Jooyontech... | J3GP Pro                    | [6f13d68344](https://linux-hardware.org/?probe=6f13d68344) | Dec 04, 2021 |
| HP            | ProBook 6450b               | [df1987d444](https://linux-hardware.org/?probe=df1987d444) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [b90a8aa2b6](https://linux-hardware.org/?probe=b90a8aa2b6) | Dec 04, 2021 |
| HP            | 250 G5 Notebook PC          | [c977d7c465](https://linux-hardware.org/?probe=c977d7c465) | Dec 04, 2021 |
| Dell          | Inspiron 5490               | [21da3b7e37](https://linux-hardware.org/?probe=21da3b7e37) | Dec 03, 2021 |
| Acer          | Extensa 5620                | [1f4dcd31db](https://linux-hardware.org/?probe=1f4dcd31db) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [61ace3554b](https://linux-hardware.org/?probe=61ace3554b) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [bedc746ec5](https://linux-hardware.org/?probe=bedc746ec5) | Dec 03, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [65df411fac](https://linux-hardware.org/?probe=65df411fac) | Dec 03, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [2e396ceaf9](https://linux-hardware.org/?probe=2e396ceaf9) | Dec 03, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | [c7cc850f29](https://linux-hardware.org/?probe=c7cc850f29) | Dec 03, 2021 |
| LG Electro... | 16ZD90P-GX5LK               | [901fdc3726](https://linux-hardware.org/?probe=901fdc3726) | Dec 03, 2021 |
| Apple         | MacBookPro12,1              | [48284cb8a5](https://linux-hardware.org/?probe=48284cb8a5) | Dec 02, 2021 |
| Toshiba       | Satellite L655              | [6cf5d39778](https://linux-hardware.org/?probe=6cf5d39778) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | [92068cb097](https://linux-hardware.org/?probe=92068cb097) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | [a77255409f](https://linux-hardware.org/?probe=a77255409f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | [ef02c2fb6c](https://linux-hardware.org/?probe=ef02c2fb6c) | Dec 02, 2021 |
| Apple         | MacBookPro13,3              | [d5c66e036d](https://linux-hardware.org/?probe=d5c66e036d) | Dec 02, 2021 |
| Dell          | XPS 13 9310                 | [fa0051b73b](https://linux-hardware.org/?probe=fa0051b73b) | Dec 02, 2021 |
| Dell          | XPS 17 9710                 | [e34c5d610c](https://linux-hardware.org/?probe=e34c5d610c) | Dec 02, 2021 |
| ASUSTek       | ROG Zephyrus S17 GX703HS... | [32a7506932](https://linux-hardware.org/?probe=32a7506932) | Dec 01, 2021 |
| DukaPC        | Notebook                    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [74b0b6dc77](https://linux-hardware.org/?probe=74b0b6dc77) | Dec 01, 2021 |
| Acer          | Swift SF314-43              | [dc17b5db95](https://linux-hardware.org/?probe=dc17b5db95) | Dec 01, 2021 |
| MSI           | Prestige 15 A11SCS          | [1de5756d09](https://linux-hardware.org/?probe=1de5756d09) | Dec 01, 2021 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [a42ba12bea](https://linux-hardware.org/?probe=a42ba12bea) | Dec 01, 2021 |
| Dell          | Inspiron 5770               | [207ec37d70](https://linux-hardware.org/?probe=207ec37d70) | Dec 01, 2021 |
| HP            | ZBook Fury 15.6 inch G8 ... | [0ebc40df56](https://linux-hardware.org/?probe=0ebc40df56) | Dec 01, 2021 |
| Lenovo        | G500 20236                  | [f61434ecc0](https://linux-hardware.org/?probe=f61434ecc0) | Nov 30, 2021 |
| HP            | ProBook 440 G6              | [c819afbd7a](https://linux-hardware.org/?probe=c819afbd7a) | Nov 30, 2021 |
| HP            | ProBook 440 G6              | [a30cacf7ad](https://linux-hardware.org/?probe=a30cacf7ad) | Nov 30, 2021 |
| Timi          | A35S                        | [dbb600147d](https://linux-hardware.org/?probe=dbb600147d) | Nov 30, 2021 |
| Framework     | Laptop                      | [e5f72bfb66](https://linux-hardware.org/?probe=e5f72bfb66) | Nov 30, 2021 |
| Dell          | Latitude 5420               | [b0f561b8a8](https://linux-hardware.org/?probe=b0f561b8a8) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [29a3dcf41b](https://linux-hardware.org/?probe=29a3dcf41b) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ae6614d6fb](https://linux-hardware.org/?probe=ae6614d6fb) | Nov 29, 2021 |
| Sony          | SVE1713Y1EB                 | [317b686b33](https://linux-hardware.org/?probe=317b686b33) | Nov 29, 2021 |
| Acer          | Aspire 5560                 | [db900fbb00](https://linux-hardware.org/?probe=db900fbb00) | Nov 29, 2021 |
| Acer          | Aspire A315-57G             | [cfc036a421](https://linux-hardware.org/?probe=cfc036a421) | Nov 29, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [c596ffcab5](https://linux-hardware.org/?probe=c596ffcab5) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [3a85954b66](https://linux-hardware.org/?probe=3a85954b66) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [5271c46262](https://linux-hardware.org/?probe=5271c46262) | Nov 29, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [dddc3d3a11](https://linux-hardware.org/?probe=dddc3d3a11) | Nov 29, 2021 |
| Lenovo        | G500 20236                  | [e97bbbd7a9](https://linux-hardware.org/?probe=e97bbbd7a9) | Nov 29, 2021 |
| Panasonic     | CF-19RDRAMGA                | [5aaebfbf19](https://linux-hardware.org/?probe=5aaebfbf19) | Nov 29, 2021 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | [fb633e3cb9](https://linux-hardware.org/?probe=fb633e3cb9) | Nov 29, 2021 |
| Samsung       | R520/R522/R620              | [babd307b08](https://linux-hardware.org/?probe=babd307b08) | Nov 29, 2021 |
| Dell          | Inspiron 15-3567            | [2ae4de7517](https://linux-hardware.org/?probe=2ae4de7517) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [4aa9def017](https://linux-hardware.org/?probe=4aa9def017) | Nov 29, 2021 |
| Acer          | Aspire A515-56              | [b0ed9bece9](https://linux-hardware.org/?probe=b0ed9bece9) | Nov 28, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | [8d962864f8](https://linux-hardware.org/?probe=8d962864f8) | Nov 28, 2021 |
| Lenovo        | G780 2182                   | [2eeaf69158](https://linux-hardware.org/?probe=2eeaf69158) | Nov 28, 2021 |
| Razer         | Blade Stealth               | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [5e38544a06](https://linux-hardware.org/?probe=5e38544a06) | Nov 28, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [1a717e5780](https://linux-hardware.org/?probe=1a717e5780) | Nov 28, 2021 |
| Dell          | XPS 15 9570                 | [ee3aa93d09](https://linux-hardware.org/?probe=ee3aa93d09) | Nov 28, 2021 |
| Acer          | Aspire A315-51              | [397f62191b](https://linux-hardware.org/?probe=397f62191b) | Nov 28, 2021 |
| Apple         | MacBook7,1                  | [22e54de439](https://linux-hardware.org/?probe=22e54de439) | Nov 27, 2021 |
| HP            | ProBook 450 G5              | [dd2b422dd8](https://linux-hardware.org/?probe=dd2b422dd8) | Nov 27, 2021 |
| Acer          | Swift SF314-42              | [c5b8c42409](https://linux-hardware.org/?probe=c5b8c42409) | Nov 27, 2021 |
| PC Special... | X170KM-G                    | [6321e2900b](https://linux-hardware.org/?probe=6321e2900b) | Nov 27, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [f85f2dbd4e](https://linux-hardware.org/?probe=f85f2dbd4e) | Nov 27, 2021 |
| Packard Be... | EasyNote ENLG81BA           | [3fcadd0f73](https://linux-hardware.org/?probe=3fcadd0f73) | Nov 27, 2021 |
| Dell          | Precision 7530              | [2b64eebf55](https://linux-hardware.org/?probe=2b64eebf55) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [f047b9db0a](https://linux-hardware.org/?probe=f047b9db0a) | Nov 27, 2021 |
| HP            | ProBook 4540s               | [d8d17c1820](https://linux-hardware.org/?probe=d8d17c1820) | Nov 27, 2021 |
| Lenovo        | G500 20236                  | [c1dd144b77](https://linux-hardware.org/?probe=c1dd144b77) | Nov 27, 2021 |
| HP            | EliteBook 745 G3            | [92968d4a23](https://linux-hardware.org/?probe=92968d4a23) | Nov 27, 2021 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [50e118bf49](https://linux-hardware.org/?probe=50e118bf49) | Nov 27, 2021 |
| HP            | Laptop 15z-ef2xxx           | [8acaaafb63](https://linux-hardware.org/?probe=8acaaafb63) | Nov 27, 2021 |
| Lenovo        | G780                        | [ffeaa607f9](https://linux-hardware.org/?probe=ffeaa607f9) | Nov 27, 2021 |
| Lenovo        | G780                        | [26ea5410e6](https://linux-hardware.org/?probe=26ea5410e6) | Nov 27, 2021 |
| Dell          | XPS 13 9310                 | [c3abf33b86](https://linux-hardware.org/?probe=c3abf33b86) | Nov 27, 2021 |
| Dell          | XPS 13 9310                 | [87c80403ae](https://linux-hardware.org/?probe=87c80403ae) | Nov 27, 2021 |
| Lenovo        | ThinkPad T510 43494JG       | [3564b21c35](https://linux-hardware.org/?probe=3564b21c35) | Nov 26, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [8a5475fd42](https://linux-hardware.org/?probe=8a5475fd42) | Nov 26, 2021 |
| Dell          | Latitude D830               | [080fac6354](https://linux-hardware.org/?probe=080fac6354) | Nov 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [fbec23b579](https://linux-hardware.org/?probe=fbec23b579) | Nov 26, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [9240ce23bd](https://linux-hardware.org/?probe=9240ce23bd) | Nov 26, 2021 |
| Notebook      | PCX0DX                      | [dd551e6aad](https://linux-hardware.org/?probe=dd551e6aad) | Nov 26, 2021 |
| Apple         | MacBookPro8,1               | [a0b9aec393](https://linux-hardware.org/?probe=a0b9aec393) | Nov 26, 2021 |
| Apple         | MacBookPro8,1               | [62a1aeadc4](https://linux-hardware.org/?probe=62a1aeadc4) | Nov 26, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [5a1e505112](https://linux-hardware.org/?probe=5a1e505112) | Nov 25, 2021 |
| Medion        | P15648                      | [1328e63002](https://linux-hardware.org/?probe=1328e63002) | Nov 25, 2021 |
| Lenovo        | IdeaPad S145-15API 81UT     | [dea62ab6ef](https://linux-hardware.org/?probe=dea62ab6ef) | Nov 25, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [1ec79ee5e6](https://linux-hardware.org/?probe=1ec79ee5e6) | Nov 25, 2021 |
| ASUSTek       | X751LN                      | [2c8e1bfecd](https://linux-hardware.org/?probe=2c8e1bfecd) | Nov 25, 2021 |
| Dell          | Vostro 5402                 | [a10a19ecfb](https://linux-hardware.org/?probe=a10a19ecfb) | Nov 25, 2021 |
| Dell          | Latitude 5520               | [6fae6c9e46](https://linux-hardware.org/?probe=6fae6c9e46) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [806d1fa87a](https://linux-hardware.org/?probe=806d1fa87a) | Nov 25, 2021 |
| Dell          | Inspiron 5593               | [fb416125d9](https://linux-hardware.org/?probe=fb416125d9) | Nov 25, 2021 |
| Jemper        | EZPAD WS_reserve            | [de173db361](https://linux-hardware.org/?probe=de173db361) | Nov 25, 2021 |
| Fujitsu       | LIFEBOOK E751               | [3f1db85e8a](https://linux-hardware.org/?probe=3f1db85e8a) | Nov 25, 2021 |
| Dell          | Latitude 7420               | [648247b3cc](https://linux-hardware.org/?probe=648247b3cc) | Nov 24, 2021 |
| Toshiba       | Satellite Pro C850-1GU      | [46a6f52122](https://linux-hardware.org/?probe=46a6f52122) | Nov 24, 2021 |
| ASUSTek       | UX331UA                     | [7aee71ceed](https://linux-hardware.org/?probe=7aee71ceed) | Nov 24, 2021 |
| Lenovo        | ThinkPad W530 2447GW3       | [893bad1753](https://linux-hardware.org/?probe=893bad1753) | Nov 24, 2021 |
| Chuwi         | GemiBook Pro                | [1dc5d193a3](https://linux-hardware.org/?probe=1dc5d193a3) | Nov 24, 2021 |
| Dell          | XPS 17 9710                 | [c97bbaf0c5](https://linux-hardware.org/?probe=c97bbaf0c5) | Nov 24, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [5632c40eac](https://linux-hardware.org/?probe=5632c40eac) | Nov 24, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | [35508b1562](https://linux-hardware.org/?probe=35508b1562) | Nov 24, 2021 |
| Dell          | Latitude 5421               | [4f39514ffc](https://linux-hardware.org/?probe=4f39514ffc) | Nov 24, 2021 |
| Acer          | Nitro AN515-54              | [bf1ef9f271](https://linux-hardware.org/?probe=bf1ef9f271) | Nov 24, 2021 |
| Dell          | XPS 17 9710                 | [fb1cce8ab4](https://linux-hardware.org/?probe=fb1cce8ab4) | Nov 24, 2021 |
| Dell          | Inspiron 5570               | [774f732180](https://linux-hardware.org/?probe=774f732180) | Nov 24, 2021 |
| Dell          | XPS 15 9560                 | [ed470afd8a](https://linux-hardware.org/?probe=ed470afd8a) | Nov 24, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2fc0deb231](https://linux-hardware.org/?probe=2fc0deb231) | Nov 24, 2021 |
| Dell          | XPS 15 9570                 | [524d775cd9](https://linux-hardware.org/?probe=524d775cd9) | Nov 24, 2021 |
| Dell          | Inspiron 5558               | [772ca16963](https://linux-hardware.org/?probe=772ca16963) | Nov 23, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [30e9ef2236](https://linux-hardware.org/?probe=30e9ef2236) | Nov 23, 2021 |
| HP            | ProBook 440 G7              | [7863ad05f4](https://linux-hardware.org/?probe=7863ad05f4) | Nov 23, 2021 |
| Toshiba       | TECRA R940                  | [778fe1dfcc](https://linux-hardware.org/?probe=778fe1dfcc) | Nov 23, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [35b7ff3a68](https://linux-hardware.org/?probe=35b7ff3a68) | Nov 23, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [ec94d40844](https://linux-hardware.org/?probe=ec94d40844) | Nov 23, 2021 |
| Toshiba       | Satellite C855-1JD          | [9ead13671d](https://linux-hardware.org/?probe=9ead13671d) | Nov 22, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f1620f693d](https://linux-hardware.org/?probe=f1620f693d) | Nov 22, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [d0a08a7a23](https://linux-hardware.org/?probe=d0a08a7a23) | Nov 22, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [507c380abb](https://linux-hardware.org/?probe=507c380abb) | Nov 22, 2021 |
| Lenovo        | ThinkPad T520 4243CJ2       | [418a8830c3](https://linux-hardware.org/?probe=418a8830c3) | Nov 22, 2021 |
| HP            | 550                         | [bbbca1ed06](https://linux-hardware.org/?probe=bbbca1ed06) | Nov 22, 2021 |
| Lenovo        | V145-15AST 81MT             | [941396daf4](https://linux-hardware.org/?probe=941396daf4) | Nov 22, 2021 |
| ASUSTek       | X751LN                      | [50d304e970](https://linux-hardware.org/?probe=50d304e970) | Nov 22, 2021 |
| Dell          | Inspiron 5558               | [bae9fdec30](https://linux-hardware.org/?probe=bae9fdec30) | Nov 22, 2021 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [3964ebaadd](https://linux-hardware.org/?probe=3964ebaadd) | Nov 22, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [61308173d9](https://linux-hardware.org/?probe=61308173d9) | Nov 22, 2021 |
| Exo           | Smart Serie M               | [cbf705cf51](https://linux-hardware.org/?probe=cbf705cf51) | Nov 22, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [af11f87974](https://linux-hardware.org/?probe=af11f87974) | Nov 22, 2021 |
| Dell          | XPS 15 9510                 | [c89373bfad](https://linux-hardware.org/?probe=c89373bfad) | Nov 21, 2021 |
| Apple         | MacBookPro12,1              | [685ef4de17](https://linux-hardware.org/?probe=685ef4de17) | Nov 21, 2021 |
| Dell          | XPS 15 9570                 | [09557621d2](https://linux-hardware.org/?probe=09557621d2) | Nov 21, 2021 |
| Apple         | MacBookPro13,3              | [a5935d753d](https://linux-hardware.org/?probe=a5935d753d) | Nov 21, 2021 |
| Lenovo        | ThinkPad T430 2349DS1       | [1ad2d01280](https://linux-hardware.org/?probe=1ad2d01280) | Nov 21, 2021 |
| Dell          | Inspiron 1545               | [11710ca51d](https://linux-hardware.org/?probe=11710ca51d) | Nov 21, 2021 |
| Dell          | Inspiron 5570               | [d73b7c147b](https://linux-hardware.org/?probe=d73b7c147b) | Nov 21, 2021 |
| ASUSTek       | N751JK                      | [f64a3f1fc2](https://linux-hardware.org/?probe=f64a3f1fc2) | Nov 20, 2021 |
| HP            | ZBook 17                    | [dddc9c534d](https://linux-hardware.org/?probe=dddc9c534d) | Nov 20, 2021 |
| HP            | G62                         | [7659359d92](https://linux-hardware.org/?probe=7659359d92) | Nov 20, 2021 |
| HP            | Unknown                     | [23dc38032d](https://linux-hardware.org/?probe=23dc38032d) | Nov 20, 2021 |
| HP            | G62                         | [5e62f156d2](https://linux-hardware.org/?probe=5e62f156d2) | Nov 20, 2021 |
| Dell          | Latitude E5400              | [062c0d6df1](https://linux-hardware.org/?probe=062c0d6df1) | Nov 20, 2021 |
| Dell          | Inspiron 7577               | [06399f0deb](https://linux-hardware.org/?probe=06399f0deb) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [04fa536869](https://linux-hardware.org/?probe=04fa536869) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [097de81570](https://linux-hardware.org/?probe=097de81570) | Nov 20, 2021 |
| HUAWEI        | KLVL-WXX9                   | [0bccbf892a](https://linux-hardware.org/?probe=0bccbf892a) | Nov 19, 2021 |
| HUAWEI        | KLVL-WXX9                   | [7a4c2319fa](https://linux-hardware.org/?probe=7a4c2319fa) | Nov 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [5825bb233c](https://linux-hardware.org/?probe=5825bb233c) | Nov 19, 2021 |
| HP            | OMEN by Laptop              | [0b8f3a5da9](https://linux-hardware.org/?probe=0b8f3a5da9) | Nov 19, 2021 |
| Dell          | Latitude E4300              | [7bb479a55e](https://linux-hardware.org/?probe=7bb479a55e) | Nov 19, 2021 |
| HP            | OMEN by Laptop              | [dc7136f307](https://linux-hardware.org/?probe=dc7136f307) | Nov 19, 2021 |
| Acer          | Aspire E5-551               | [7ae0f74c7d](https://linux-hardware.org/?probe=7ae0f74c7d) | Nov 19, 2021 |
| HP            | Pavilion Laptop             | [ab2e04130f](https://linux-hardware.org/?probe=ab2e04130f) | Nov 19, 2021 |
| Dell          | Latitude 3510               | [9d4db04732](https://linux-hardware.org/?probe=9d4db04732) | Nov 19, 2021 |
| ASUSTek       | X401A1                      | [fa9b9fa473](https://linux-hardware.org/?probe=fa9b9fa473) | Nov 19, 2021 |
| Sony          | VPCF130FD                   | [e4468538f5](https://linux-hardware.org/?probe=e4468538f5) | Nov 19, 2021 |
| System76      | Gazelle                     | [939b96106b](https://linux-hardware.org/?probe=939b96106b) | Nov 19, 2021 |
| Acer          | Swift SF314-42              | [264bebca57](https://linux-hardware.org/?probe=264bebca57) | Nov 18, 2021 |
| Framework     | Laptop                      | [0d635923b5](https://linux-hardware.org/?probe=0d635923b5) | Nov 18, 2021 |
| HP            | Laptop 14-fq1xxx            | [2d996858ab](https://linux-hardware.org/?probe=2d996858ab) | Nov 18, 2021 |
| Lenovo        | ThinkPad X220 4291CA0       | [94cebfa456](https://linux-hardware.org/?probe=94cebfa456) | Nov 18, 2021 |
| Packard Be... | EasyNote LJ75               | [7ec0fdf75d](https://linux-hardware.org/?probe=7ec0fdf75d) | Nov 18, 2021 |
| Timi          | RedmiBook 16                | [0b9130726c](https://linux-hardware.org/?probe=0b9130726c) | Nov 18, 2021 |
| HP            | ProBook 4510s               | [46c61312c4](https://linux-hardware.org/?probe=46c61312c4) | Nov 18, 2021 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [80168c4938](https://linux-hardware.org/?probe=80168c4938) | Nov 18, 2021 |
| Framework     | Laptop                      | [3772cd7a6e](https://linux-hardware.org/?probe=3772cd7a6e) | Nov 17, 2021 |
| Acer          | TravelMate 6292             | [0acf22106c](https://linux-hardware.org/?probe=0acf22106c) | Nov 17, 2021 |
| Dell          | Latitude 5520               | [e398be8e26](https://linux-hardware.org/?probe=e398be8e26) | Nov 17, 2021 |
| Dell          | XPS 15 9500                 | [a77e5494bf](https://linux-hardware.org/?probe=a77e5494bf) | Nov 17, 2021 |
| Dell          | XPS 15 9500                 | [526d5c7a21](https://linux-hardware.org/?probe=526d5c7a21) | Nov 17, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [30520d2f19](https://linux-hardware.org/?probe=30520d2f19) | Nov 17, 2021 |
| Dell          | XPS 15 9500                 | [be45eea786](https://linux-hardware.org/?probe=be45eea786) | Nov 17, 2021 |
| Dell          | Inspiron 7586               | [188923fc9c](https://linux-hardware.org/?probe=188923fc9c) | Nov 17, 2021 |
| HP            | ProBook 4510s               | [cf53b2e2db](https://linux-hardware.org/?probe=cf53b2e2db) | Nov 17, 2021 |
| Positivo      | Mobile                      | [9b83c09ad3](https://linux-hardware.org/?probe=9b83c09ad3) | Nov 17, 2021 |
| HP            | Laptop 15-db1xxx            | [cd32f937e9](https://linux-hardware.org/?probe=cd32f937e9) | Nov 17, 2021 |
| HP            | ProBook 650 G1              | [07597b6850](https://linux-hardware.org/?probe=07597b6850) | Nov 16, 2021 |
| HP            | ProBook 650 G1              | [21f9af6edb](https://linux-hardware.org/?probe=21f9af6edb) | Nov 16, 2021 |
| Dell          | Latitude E7470              | [0358863974](https://linux-hardware.org/?probe=0358863974) | Nov 16, 2021 |
| HP            | ProBook 4520s               | [1d9f0ec825](https://linux-hardware.org/?probe=1d9f0ec825) | Nov 16, 2021 |
| HP            | ProBook 4520s               | [1fb5221e00](https://linux-hardware.org/?probe=1fb5221e00) | Nov 16, 2021 |
| Medion        | P6630                       | [235a9a3ced](https://linux-hardware.org/?probe=235a9a3ced) | Nov 16, 2021 |
| Apple         | MacBook4,1                  | [f9ee489abd](https://linux-hardware.org/?probe=f9ee489abd) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [72e7bebf84](https://linux-hardware.org/?probe=72e7bebf84) | Nov 16, 2021 |
| ASUSTek       | X540YA                      | [39d8ea222a](https://linux-hardware.org/?probe=39d8ea222a) | Nov 16, 2021 |
| Medion        | Akoya E6240T                | [9f7f0a3a96](https://linux-hardware.org/?probe=9f7f0a3a96) | Nov 16, 2021 |
| HP            | Laptop 15-bs0xx             | [d33bc4ef7c](https://linux-hardware.org/?probe=d33bc4ef7c) | Nov 16, 2021 |
| HP            | Laptop 15-bs0xx             | [048cf14d2f](https://linux-hardware.org/?probe=048cf14d2f) | Nov 16, 2021 |
| HP            | 15                          | [43b117b7a1](https://linux-hardware.org/?probe=43b117b7a1) | Nov 16, 2021 |
| ASUSTek       | X580VD                      | [3c83607d76](https://linux-hardware.org/?probe=3c83607d76) | Nov 16, 2021 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [34fb650910](https://linux-hardware.org/?probe=34fb650910) | Nov 16, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [10a3cb9d12](https://linux-hardware.org/?probe=10a3cb9d12) | Nov 15, 2021 |
| Dell          | XPS 13 9305                 | [efa5ec3ed4](https://linux-hardware.org/?probe=efa5ec3ed4) | Nov 15, 2021 |
| HP            | Pavilion dv5                | [ec4890a33b](https://linux-hardware.org/?probe=ec4890a33b) | Nov 15, 2021 |
| Lenovo        | ThinkPad 25 20K70000MX      | [86d3ea8b6a](https://linux-hardware.org/?probe=86d3ea8b6a) | Nov 15, 2021 |
| HP            | 15                          | [d1c144c887](https://linux-hardware.org/?probe=d1c144c887) | Nov 15, 2021 |
| Dell          | Vostro 3400                 | [f6ba3e3359](https://linux-hardware.org/?probe=f6ba3e3359) | Nov 15, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [f998266e76](https://linux-hardware.org/?probe=f998266e76) | Nov 15, 2021 |
| Acer          | Nitro AN515-54              | [a9d34635cf](https://linux-hardware.org/?probe=a9d34635cf) | Nov 15, 2021 |
| HP            | ProBook 455 G4              | [e7976c31a1](https://linux-hardware.org/?probe=e7976c31a1) | Nov 15, 2021 |
| HP            | Pavilion dv5                | [4ddaeca48c](https://linux-hardware.org/?probe=4ddaeca48c) | Nov 15, 2021 |
| Dell          | Latitude E7440              | [60d06b6cfe](https://linux-hardware.org/?probe=60d06b6cfe) | Nov 15, 2021 |
| ASUSTek       | ROG Zephyrus M16 GU603HM    | [8809001b3c](https://linux-hardware.org/?probe=8809001b3c) | Nov 14, 2021 |
| HP            | EliteBook 835 G8 Noteboo... | [2b9e3a56a5](https://linux-hardware.org/?probe=2b9e3a56a5) | Nov 14, 2021 |
| HP            | Pavilion Notebook           | [d2eb7d0dc2](https://linux-hardware.org/?probe=d2eb7d0dc2) | Nov 14, 2021 |
| Dell          | XPS 13 9310                 | [0f6c2b21cf](https://linux-hardware.org/?probe=0f6c2b21cf) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming FX505DV_TUF50... | [3559f352cf](https://linux-hardware.org/?probe=3559f352cf) | Nov 14, 2021 |
| HP            | ProBook 455 G6              | [2a37f0ed64](https://linux-hardware.org/?probe=2a37f0ed64) | Nov 14, 2021 |
| ASUSTek       | X540SA                      | [1292ab6f15](https://linux-hardware.org/?probe=1292ab6f15) | Nov 14, 2021 |
| Dell          | Latitude E7270              | [b462d15a6b](https://linux-hardware.org/?probe=b462d15a6b) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [b22df8f53d](https://linux-hardware.org/?probe=b22df8f53d) | Nov 14, 2021 |
| Acer          | Aspire E5-553G              | [93d20530a1](https://linux-hardware.org/?probe=93d20530a1) | Nov 14, 2021 |
| Timi          | A35S                        | [68a0b2e6bd](https://linux-hardware.org/?probe=68a0b2e6bd) | Nov 14, 2021 |
| HP            | Pavilion Notebook           | [1b93110fd9](https://linux-hardware.org/?probe=1b93110fd9) | Nov 13, 2021 |
| ASUSTek       | X540SA                      | [463e1f35a9](https://linux-hardware.org/?probe=463e1f35a9) | Nov 13, 2021 |
| HP            | Stream Laptop 14-ax0XX      | [3bd51f200e](https://linux-hardware.org/?probe=3bd51f200e) | Nov 13, 2021 |
| Lenovo        | Yoga710-15ISK 80U0          | [4bbd057aa1](https://linux-hardware.org/?probe=4bbd057aa1) | Nov 13, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [d0f383a016](https://linux-hardware.org/?probe=d0f383a016) | Nov 13, 2021 |
| Apple         | MacBook7,1                  | [b898d5a09c](https://linux-hardware.org/?probe=b898d5a09c) | Nov 13, 2021 |
| Dell          | XPS 13 9310                 | [01c20231f2](https://linux-hardware.org/?probe=01c20231f2) | Nov 13, 2021 |
| HP            | Laptop 14-fq1xxx            | [cc7fba67fd](https://linux-hardware.org/?probe=cc7fba67fd) | Nov 12, 2021 |
| HP            | Pavilion Notebook           | [0d96ccbe28](https://linux-hardware.org/?probe=0d96ccbe28) | Nov 12, 2021 |
| HP            | ProBook 450 G5              | [984b162f45](https://linux-hardware.org/?probe=984b162f45) | Nov 12, 2021 |
| Dell          | XPS 15 9570                 | [abb7877540](https://linux-hardware.org/?probe=abb7877540) | Nov 12, 2021 |
| Dell          | Latitude E6520              | [e795da8420](https://linux-hardware.org/?probe=e795da8420) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9ba065b607](https://linux-hardware.org/?probe=9ba065b607) | Nov 12, 2021 |
| ASUSTek       | N501VW                      | [8701c7e1c8](https://linux-hardware.org/?probe=8701c7e1c8) | Nov 12, 2021 |
| ASUSTek       | N501VW                      | [fe236eaa88](https://linux-hardware.org/?probe=fe236eaa88) | Nov 12, 2021 |
| Acer          | Aspire 5755G                | [23a8df3372](https://linux-hardware.org/?probe=23a8df3372) | Nov 12, 2021 |
| Dell          | Inspiron 15-3573            | [0c659e62e6](https://linux-hardware.org/?probe=0c659e62e6) | Nov 12, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [9d3272960f](https://linux-hardware.org/?probe=9d3272960f) | Nov 12, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [31e2521af4](https://linux-hardware.org/?probe=31e2521af4) | Nov 12, 2021 |
| Acer          | Swift SF315-41              | [744b18ebd1](https://linux-hardware.org/?probe=744b18ebd1) | Nov 12, 2021 |
| HP            | OMEN by Laptop              | [207d9a7985](https://linux-hardware.org/?probe=207d9a7985) | Nov 12, 2021 |
| ASUSTek       | GL553VD                     | [d152d41284](https://linux-hardware.org/?probe=d152d41284) | Nov 12, 2021 |
| Dell          | Latitude E6410              | [08fde74c0e](https://linux-hardware.org/?probe=08fde74c0e) | Nov 12, 2021 |
| Dell          | Precision M4700             | [8d8a2dcc96](https://linux-hardware.org/?probe=8d8a2dcc96) | Nov 12, 2021 |
| Dell          | Inspiron 5570               | [be0e281ff8](https://linux-hardware.org/?probe=be0e281ff8) | Nov 12, 2021 |
| Dell          | XPS 15 9570                 | [7d4e321511](https://linux-hardware.org/?probe=7d4e321511) | Nov 12, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [fdb480d5f4](https://linux-hardware.org/?probe=fdb480d5f4) | Nov 12, 2021 |
| HP            | Pavilion g6                 | [0332d112e9](https://linux-hardware.org/?probe=0332d112e9) | Nov 12, 2021 |
| Dell          | Latitude D630               | [e034675b55](https://linux-hardware.org/?probe=e034675b55) | Nov 12, 2021 |
| Dell          | Latitude D630               | [8227457c3b](https://linux-hardware.org/?probe=8227457c3b) | Nov 12, 2021 |
| HP            | ProBook 455 G6              | [6045aa2b3a](https://linux-hardware.org/?probe=6045aa2b3a) | Nov 12, 2021 |
| Dell          | XPS 15 9570                 | [d22d46f646](https://linux-hardware.org/?probe=d22d46f646) | Nov 11, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [2f75d80207](https://linux-hardware.org/?probe=2f75d80207) | Nov 11, 2021 |
| Lenovo        | ThinkPad Edge E431 62779... | [0d059f1720](https://linux-hardware.org/?probe=0d059f1720) | Nov 11, 2021 |
| Notebook      | P64_HJ,HK1                  | [f15a333240](https://linux-hardware.org/?probe=f15a333240) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | [ace08cf199](https://linux-hardware.org/?probe=ace08cf199) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | [0e31d4b6fa](https://linux-hardware.org/?probe=0e31d4b6fa) | Nov 11, 2021 |
| Packard Be... | EasyNote TE69BM             | [5041e2b272](https://linux-hardware.org/?probe=5041e2b272) | Nov 10, 2021 |
| Dell          | Inspiron 15 7510            | [ba69916825](https://linux-hardware.org/?probe=ba69916825) | Nov 10, 2021 |
| Packard Be... | EasyNote TE69BM             | [fcb5b11b8c](https://linux-hardware.org/?probe=fcb5b11b8c) | Nov 10, 2021 |
| Timi          | A35                         | [f8818e4273](https://linux-hardware.org/?probe=f8818e4273) | Nov 10, 2021 |
| HP            | ProBook x360 11 G5 EE       | [ec64c11055](https://linux-hardware.org/?probe=ec64c11055) | Nov 10, 2021 |
| ASUSTek       | X55A                        | [a55961748f](https://linux-hardware.org/?probe=a55961748f) | Nov 10, 2021 |
| ASUSTek       | X55A                        | [8c59513ced](https://linux-hardware.org/?probe=8c59513ced) | Nov 10, 2021 |
| Dell          | Inspiron 5558               | [c4e563c1ab](https://linux-hardware.org/?probe=c4e563c1ab) | Nov 10, 2021 |
| Sony          | VPCCB25FX                   | [c42c92c898](https://linux-hardware.org/?probe=c42c92c898) | Nov 09, 2021 |
| Lenovo        | ThinkPad L450 20DTCTO1WW    | [ad9b4ec784](https://linux-hardware.org/?probe=ad9b4ec784) | Nov 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [aad3e601ad](https://linux-hardware.org/?probe=aad3e601ad) | Nov 09, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [dd5b331a4c](https://linux-hardware.org/?probe=dd5b331a4c) | Nov 09, 2021 |
| Dell          | Inspiron 1764               | [319a6efc5a](https://linux-hardware.org/?probe=319a6efc5a) | Nov 09, 2021 |
| Dell          | XPS 13 9310                 | [94b138fb37](https://linux-hardware.org/?probe=94b138fb37) | Nov 09, 2021 |
| Dell          | XPS 13 9310                 | [3f47def69d](https://linux-hardware.org/?probe=3f47def69d) | Nov 09, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [94448a14f7](https://linux-hardware.org/?probe=94448a14f7) | Nov 09, 2021 |
| Timi          | A30                         | [63583fcf04](https://linux-hardware.org/?probe=63583fcf04) | Nov 09, 2021 |
| HP            | ProBook 445 G7              | [eecec0bcf8](https://linux-hardware.org/?probe=eecec0bcf8) | Nov 08, 2021 |
| HP            | ProBook 445 G7              | [cb60701cba](https://linux-hardware.org/?probe=cb60701cba) | Nov 08, 2021 |
| Sony          | VPCEL2S1E                   | [00df9cdeb3](https://linux-hardware.org/?probe=00df9cdeb3) | Nov 08, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [76de163bc3](https://linux-hardware.org/?probe=76de163bc3) | Nov 08, 2021 |
| HP            | Pavilion dv7                | [a19e73fd27](https://linux-hardware.org/?probe=a19e73fd27) | Nov 08, 2021 |
| Dell          | XPS 13 9310                 | [0c99cea4ba](https://linux-hardware.org/?probe=0c99cea4ba) | Nov 07, 2021 |
| Notebook      | W54_55SU1,SUW               | [a0e93f5294](https://linux-hardware.org/?probe=a0e93f5294) | Nov 07, 2021 |
| Toshiba       | Satellite Pro S300          | [a9dd74e832](https://linux-hardware.org/?probe=a9dd74e832) | Nov 07, 2021 |
| Acer          | Swift SF314-43              | [8540ada375](https://linux-hardware.org/?probe=8540ada375) | Nov 07, 2021 |
| Jumper        | EZbook                      | [d9f2b0f1b2](https://linux-hardware.org/?probe=d9f2b0f1b2) | Nov 07, 2021 |
| Jumper        | EZbook                      | [2752cc575b](https://linux-hardware.org/?probe=2752cc575b) | Nov 07, 2021 |
| Dell          | Inspiron 5558               | [94c8a2df98](https://linux-hardware.org/?probe=94c8a2df98) | Nov 07, 2021 |
| Dell          | XPS 15 9510                 | [6f9b7bffd1](https://linux-hardware.org/?probe=6f9b7bffd1) | Nov 06, 2021 |
| Dell          | G15 5515                    | [1e5e0ab274](https://linux-hardware.org/?probe=1e5e0ab274) | Nov 06, 2021 |
| Dell          | Inspiron 15-3567            | [630a9144f1](https://linux-hardware.org/?probe=630a9144f1) | Nov 06, 2021 |
| PC Special... | W94_95_97PU                 | [2c6e08bf5d](https://linux-hardware.org/?probe=2c6e08bf5d) | Nov 06, 2021 |
| Toshiba       | Dakar10FW8                  | [ca1da89f22](https://linux-hardware.org/?probe=ca1da89f22) | Nov 06, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [999eb9102a](https://linux-hardware.org/?probe=999eb9102a) | Nov 06, 2021 |
| HP            | ProBook 440 G4              | [e0b2ef1603](https://linux-hardware.org/?probe=e0b2ef1603) | Nov 06, 2021 |
| HUAWEI        | MACHD-WXX9                  | [364fb5b6b7](https://linux-hardware.org/?probe=364fb5b6b7) | Nov 06, 2021 |
| Dell          | Vostro 3478                 | [f88e5eec69](https://linux-hardware.org/?probe=f88e5eec69) | Nov 05, 2021 |
| Dell          | Vostro 3478                 | [8174188077](https://linux-hardware.org/?probe=8174188077) | Nov 05, 2021 |
| HP            | ProBook 430 G4              | [d5ff59ee05](https://linux-hardware.org/?probe=d5ff59ee05) | Nov 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [cf7dc59b1a](https://linux-hardware.org/?probe=cf7dc59b1a) | Nov 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [aad7742ae7](https://linux-hardware.org/?probe=aad7742ae7) | Nov 05, 2021 |
| Dell          | Latitude 7390 2-in-1        | [4b1fcf5e24](https://linux-hardware.org/?probe=4b1fcf5e24) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [966b61331a](https://linux-hardware.org/?probe=966b61331a) | Nov 05, 2021 |
| HP            | Laptop 15-dw3xxx            | [e1c9be9f1d](https://linux-hardware.org/?probe=e1c9be9f1d) | Nov 05, 2021 |
| Dell          | XPS 13 9300                 | [babbbc5e56](https://linux-hardware.org/?probe=babbbc5e56) | Nov 05, 2021 |
| Avell High... | A70 LIV                     | [b4d7b0e021](https://linux-hardware.org/?probe=b4d7b0e021) | Nov 05, 2021 |
| Lenovo        | G40-80 80E4                 | [57b9418a9c](https://linux-hardware.org/?probe=57b9418a9c) | Nov 05, 2021 |
| HP            | EliteBook 8540p             | [048c1d5d30](https://linux-hardware.org/?probe=048c1d5d30) | Nov 05, 2021 |
| HUAWEI        | KLVD-WXX9                   | [b69ad25203](https://linux-hardware.org/?probe=b69ad25203) | Nov 04, 2021 |
| HP            | Laptop 15-dw1xxx            | [07b1660d10](https://linux-hardware.org/?probe=07b1660d10) | Nov 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [701adbe249](https://linux-hardware.org/?probe=701adbe249) | Nov 04, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c221fbfc80](https://linux-hardware.org/?probe=c221fbfc80) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dc8f8db0fd](https://linux-hardware.org/?probe=dc8f8db0fd) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [dc325a808a](https://linux-hardware.org/?probe=dc325a808a) | Nov 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [9fe96f497b](https://linux-hardware.org/?probe=9fe96f497b) | Nov 04, 2021 |
| HUAWEI        | HVY-WXX9                    | [c338e7c775](https://linux-hardware.org/?probe=c338e7c775) | Nov 04, 2021 |
| HP            | ProBook 455 G3              | [ccd4bcc603](https://linux-hardware.org/?probe=ccd4bcc603) | Nov 04, 2021 |
| HP            | EliteBook 8540p             | [c7ca645211](https://linux-hardware.org/?probe=c7ca645211) | Nov 04, 2021 |
| Timi          | TM1701                      | [40dc454159](https://linux-hardware.org/?probe=40dc454159) | Nov 03, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [dbc9c2369a](https://linux-hardware.org/?probe=dbc9c2369a) | Nov 03, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [17339fe912](https://linux-hardware.org/?probe=17339fe912) | Nov 03, 2021 |
| HUAWEI        | HVY-WXX9                    | [fdb3a089a2](https://linux-hardware.org/?probe=fdb3a089a2) | Nov 03, 2021 |
| ASUSTek       | X550VX                      | [5718178f4b](https://linux-hardware.org/?probe=5718178f4b) | Nov 03, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [fe34c12d67](https://linux-hardware.org/?probe=fe34c12d67) | Nov 03, 2021 |
| Samsung       | R530/R730                   | [a62fb59972](https://linux-hardware.org/?probe=a62fb59972) | Nov 03, 2021 |
| MOTILE        | M141                        | [00f4ccf1de](https://linux-hardware.org/?probe=00f4ccf1de) | Nov 03, 2021 |
| Acer          | Swift SF314-42              | [07025c7436](https://linux-hardware.org/?probe=07025c7436) | Nov 02, 2021 |
| Dell          | XPS 15 9500                 | [fc7604b4bc](https://linux-hardware.org/?probe=fc7604b4bc) | Nov 02, 2021 |
| Dell          | XPS 15 9500                 | [7f8efd83d8](https://linux-hardware.org/?probe=7f8efd83d8) | Nov 02, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [f5a1f78297](https://linux-hardware.org/?probe=f5a1f78297) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5158fb179d](https://linux-hardware.org/?probe=5158fb179d) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [3296f4587d](https://linux-hardware.org/?probe=3296f4587d) | Nov 02, 2021 |
| Lenovo        | G40-80 80E4                 | [f89ddc0ebd](https://linux-hardware.org/?probe=f89ddc0ebd) | Nov 02, 2021 |
| HP            | Laptop 14-bs0xx             | [3ab642249c](https://linux-hardware.org/?probe=3ab642249c) | Nov 02, 2021 |
| HP            | OMEN by Laptop              | [d5eda0a4df](https://linux-hardware.org/?probe=d5eda0a4df) | Nov 01, 2021 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [638e01b2f1](https://linux-hardware.org/?probe=638e01b2f1) | Nov 01, 2021 |
| Fujitsu       | LIFEBOOK S751               | [0365e0be95](https://linux-hardware.org/?probe=0365e0be95) | Nov 01, 2021 |
| Toshiba       | Satellite U920T             | [2151ed88f7](https://linux-hardware.org/?probe=2151ed88f7) | Nov 01, 2021 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [fdda57d98e](https://linux-hardware.org/?probe=fdda57d98e) | Nov 01, 2021 |
| ASUSTek       | K52F                        | [34a9f3b662](https://linux-hardware.org/?probe=34a9f3b662) | Nov 01, 2021 |
| Dell          | Inspiron 5570               | [ddb12be458](https://linux-hardware.org/?probe=ddb12be458) | Nov 01, 2021 |
| Lenovo        | V14-ARE 82DQ                | [8948989999](https://linux-hardware.org/?probe=8948989999) | Oct 31, 2021 |
| HP            | Laptop 14-bs0xx             | [93c1d9bd4f](https://linux-hardware.org/?probe=93c1d9bd4f) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [d55ac505b9](https://linux-hardware.org/?probe=d55ac505b9) | Oct 31, 2021 |
| HP            | OMEN by Laptop              | [65a70acf15](https://linux-hardware.org/?probe=65a70acf15) | Oct 31, 2021 |
| Dell          | Inspiron 5558               | [d876caae1e](https://linux-hardware.org/?probe=d876caae1e) | Oct 31, 2021 |
| Apple         | MacBookPro11,1              | [0c24caf245](https://linux-hardware.org/?probe=0c24caf245) | Oct 31, 2021 |
| HP            | Pavilion Notebook           | [9c8bb9558a](https://linux-hardware.org/?probe=9c8bb9558a) | Oct 31, 2021 |
| HP            | Pavilion Laptop 15-cs300    | [bcc27223cc](https://linux-hardware.org/?probe=bcc27223cc) | Oct 31, 2021 |
| HP            | Laptop 14-bs0xx             | [ebc6fe2060](https://linux-hardware.org/?probe=ebc6fe2060) | Oct 31, 2021 |
| Dell          | XPS 15 7590                 | [58e43f0514](https://linux-hardware.org/?probe=58e43f0514) | Oct 31, 2021 |
| Acer          | Swift SF314-43              | [be8229729b](https://linux-hardware.org/?probe=be8229729b) | Oct 31, 2021 |
| HP            | Pavilion dv6                | [2e9d378e76](https://linux-hardware.org/?probe=2e9d378e76) | Oct 31, 2021 |
| Lenovo        | ThinkPad Edge 0578A21       | [570863fd8c](https://linux-hardware.org/?probe=570863fd8c) | Oct 31, 2021 |
| Acer          | Swift SF314-43              | [4881a9a93c](https://linux-hardware.org/?probe=4881a9a93c) | Oct 31, 2021 |
| Lenovo        | ThinkPad T410 2537GH6       | [8b21b7cffe](https://linux-hardware.org/?probe=8b21b7cffe) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ba228b1ed7](https://linux-hardware.org/?probe=ba228b1ed7) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [f7309ef31a](https://linux-hardware.org/?probe=f7309ef31a) | Oct 30, 2021 |
| MSI           | GT75VR 7RF                  | [edd545a455](https://linux-hardware.org/?probe=edd545a455) | Oct 30, 2021 |
| ASUSTek       | N751JK                      | [739623468a](https://linux-hardware.org/?probe=739623468a) | Oct 30, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [47907aec3e](https://linux-hardware.org/?probe=47907aec3e) | Oct 30, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0c865ddf24](https://linux-hardware.org/?probe=0c865ddf24) | Oct 30, 2021 |
| Dell          | Latitude E5570              | [d926705b17](https://linux-hardware.org/?probe=d926705b17) | Oct 30, 2021 |
| Dell          | Latitude E5570              | [b8515cfe6b](https://linux-hardware.org/?probe=b8515cfe6b) | Oct 30, 2021 |
| Dell          | Latitude 5490               | [4efdbaeea5](https://linux-hardware.org/?probe=4efdbaeea5) | Oct 30, 2021 |
| Acer          | Swift SF314-511             | [43faa95812](https://linux-hardware.org/?probe=43faa95812) | Oct 30, 2021 |
| Dell          | XPS 17 9700                 | [5e25d50915](https://linux-hardware.org/?probe=5e25d50915) | Oct 30, 2021 |
| ASUSTek       | TUF Gaming FA506IU_FA506... | [3802a77d98](https://linux-hardware.org/?probe=3802a77d98) | Oct 29, 2021 |
| Dell          | Inspiron 15-3573            | [141148ec26](https://linux-hardware.org/?probe=141148ec26) | Oct 29, 2021 |
| HP            | Laptop 17z-ca300            | [0071faabac](https://linux-hardware.org/?probe=0071faabac) | Oct 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2b4a1a20d9](https://linux-hardware.org/?probe=2b4a1a20d9) | Oct 29, 2021 |
| Lenovo        | V580c 20160                 | [779684e41d](https://linux-hardware.org/?probe=779684e41d) | Oct 29, 2021 |
| Medion        | Akoya E6240T                | [1a0a5790b3](https://linux-hardware.org/?probe=1a0a5790b3) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | [9b5832381a](https://linux-hardware.org/?probe=9b5832381a) | Oct 29, 2021 |
| MSI           | GE62 7RD                    | [95616813e6](https://linux-hardware.org/?probe=95616813e6) | Oct 29, 2021 |
| MSI           | GE62 6QF                    | [1c48df3fa2](https://linux-hardware.org/?probe=1c48df3fa2) | Oct 29, 2021 |
| realme        | RMNBXXXX                    | [70b65bbcf8](https://linux-hardware.org/?probe=70b65bbcf8) | Oct 28, 2021 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [75c43f02bf](https://linux-hardware.org/?probe=75c43f02bf) | Oct 28, 2021 |
| Toshiba       | Satellite C75-B             | [fe77011ed7](https://linux-hardware.org/?probe=fe77011ed7) | Oct 28, 2021 |
| Sony          | SVS1312G3EW                 | [7951439c81](https://linux-hardware.org/?probe=7951439c81) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [9276790a36](https://linux-hardware.org/?probe=9276790a36) | Oct 28, 2021 |
| HP            | ENVY dv6                    | [31ff7dd229](https://linux-hardware.org/?probe=31ff7dd229) | Oct 28, 2021 |
| HP            | ZBook Power G7 Mobile Wo... | [e0d6eafd15](https://linux-hardware.org/?probe=e0d6eafd15) | Oct 28, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [7555bbd3c1](https://linux-hardware.org/?probe=7555bbd3c1) | Oct 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [3377403e20](https://linux-hardware.org/?probe=3377403e20) | Oct 27, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [1b93e3c1c9](https://linux-hardware.org/?probe=1b93e3c1c9) | Oct 27, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [3f7c00c1ef](https://linux-hardware.org/?probe=3f7c00c1ef) | Oct 27, 2021 |
| Dell          | Latitude 5420               | [6eef53ac22](https://linux-hardware.org/?probe=6eef53ac22) | Oct 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| Dell          | Latitude 5420               | [6d4e346031](https://linux-hardware.org/?probe=6d4e346031) | Oct 27, 2021 |
| Dell          | Latitude 5521               | [e40947106a](https://linux-hardware.org/?probe=e40947106a) | Oct 27, 2021 |
| Dell          | Latitude 5521               | [7fed676309](https://linux-hardware.org/?probe=7fed676309) | Oct 27, 2021 |
| Toshiba       | PORTEGE R830                | [6378d53c40](https://linux-hardware.org/?probe=6378d53c40) | Oct 27, 2021 |
| Apple         | MacBook2,1                  | [0346bc764a](https://linux-hardware.org/?probe=0346bc764a) | Oct 27, 2021 |
| Dell          | Inspiron 3595               | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Acer          | Aspire A315-21              | [e179a0974d](https://linux-hardware.org/?probe=e179a0974d) | Oct 27, 2021 |
| Dell          | Inspiron 5558               | [e22971aa36](https://linux-hardware.org/?probe=e22971aa36) | Oct 27, 2021 |
| Dell          | XPS 15 9570                 | [0fa8c3ed0c](https://linux-hardware.org/?probe=0fa8c3ed0c) | Oct 26, 2021 |
| Acer          | Swift SF314-43              | [4c750c8b99](https://linux-hardware.org/?probe=4c750c8b99) | Oct 26, 2021 |
| Direkt-Tek    | DTLAPY133-1                 | [63facc4838](https://linux-hardware.org/?probe=63facc4838) | Oct 26, 2021 |
| Direkt-Tek    | DTLAPY133-1                 | [a2d784b2ea](https://linux-hardware.org/?probe=a2d784b2ea) | Oct 26, 2021 |
| Packard Be... | EasyNote TS11HR             | [1217a94f61](https://linux-hardware.org/?probe=1217a94f61) | Oct 26, 2021 |
| Acer          | Aspire ES1-523              | [59ab566702](https://linux-hardware.org/?probe=59ab566702) | Oct 25, 2021 |
| Acer          | Aspire ES1-523              | [d215eb8353](https://linux-hardware.org/?probe=d215eb8353) | Oct 25, 2021 |
| HP            | Laptop 15-da0xxx            | [f0a8fa5e7a](https://linux-hardware.org/?probe=f0a8fa5e7a) | Oct 25, 2021 |
| Acer          | Swift SF314-56G             | [55a32ef8dc](https://linux-hardware.org/?probe=55a32ef8dc) | Oct 25, 2021 |
| Acer          | Aspire VX5-591G             | [6ad3cf44dc](https://linux-hardware.org/?probe=6ad3cf44dc) | Oct 24, 2021 |
| HP            | Pavilion dv6                | [bf8422ec46](https://linux-hardware.org/?probe=bf8422ec46) | Oct 24, 2021 |
| Samsung       | 530U3C/530U4C               | [07df07de7d](https://linux-hardware.org/?probe=07df07de7d) | Oct 24, 2021 |
| Acer          | Aspire ES1-512              | [aa7dd43b73](https://linux-hardware.org/?probe=aa7dd43b73) | Oct 24, 2021 |
| Acer          | Swift SF314-57              | [b416f8b251](https://linux-hardware.org/?probe=b416f8b251) | Oct 24, 2021 |
| Acer          | Swift SF314-57              | [5cfaf3df18](https://linux-hardware.org/?probe=5cfaf3df18) | Oct 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | [1e9f6f2d44](https://linux-hardware.org/?probe=1e9f6f2d44) | Oct 24, 2021 |
| HP            | ProBook 440 G5              | [508961bc42](https://linux-hardware.org/?probe=508961bc42) | Oct 24, 2021 |
| Acer          | Swift SF314-43              | [5de95b5df3](https://linux-hardware.org/?probe=5de95b5df3) | Oct 23, 2021 |
| HP            | ProBook 440 G5              | [db61c07848](https://linux-hardware.org/?probe=db61c07848) | Oct 23, 2021 |
| Acer          | Swift SF314-43              | [8d0af565c3](https://linux-hardware.org/?probe=8d0af565c3) | Oct 23, 2021 |
| Fujitsu       | LIFEBOOK U772               | [7fab4f85e2](https://linux-hardware.org/?probe=7fab4f85e2) | Oct 23, 2021 |
| HUAWEI        | MACH-WX9                    | [68c01947c9](https://linux-hardware.org/?probe=68c01947c9) | Oct 23, 2021 |
| Dell          | Inspiron 5558               | [bb40091a40](https://linux-hardware.org/?probe=bb40091a40) | Oct 23, 2021 |
| Acer          | Swift SF114-32              | [87697aa300](https://linux-hardware.org/?probe=87697aa300) | Oct 23, 2021 |
| Dell          | Latitude E7470              | [69a251cc1f](https://linux-hardware.org/?probe=69a251cc1f) | Oct 22, 2021 |
| Dell          | Inspiron 15 5501            | [d252623e18](https://linux-hardware.org/?probe=d252623e18) | Oct 22, 2021 |
| Acer          | Swift SF314-43              | [8275d5fa0b](https://linux-hardware.org/?probe=8275d5fa0b) | Oct 22, 2021 |
| HP            | ProBook 450 G5              | [5909be5c82](https://linux-hardware.org/?probe=5909be5c82) | Oct 22, 2021 |
| Sony          | VGN-FW550F                  | [c2b95c9dfa](https://linux-hardware.org/?probe=c2b95c9dfa) | Oct 22, 2021 |
| Clevo         | M740TU(N)/M760TU(N)/W7X0... | [85ccf0afc5](https://linux-hardware.org/?probe=85ccf0afc5) | Oct 22, 2021 |
| HP            | Pavilion g4                 | [3b86797a83](https://linux-hardware.org/?probe=3b86797a83) | Oct 22, 2021 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | [b198944ad7](https://linux-hardware.org/?probe=b198944ad7) | Oct 22, 2021 |
| Dell          | Inspiron 5558               | [6ada321924](https://linux-hardware.org/?probe=6ada321924) | Oct 22, 2021 |
| MSI           | GF63 Thin 9RCX              | [c4768bba2d](https://linux-hardware.org/?probe=c4768bba2d) | Oct 22, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| Toshiba       | PORTEGE R830                | [5d6b560499](https://linux-hardware.org/?probe=5d6b560499) | Oct 22, 2021 |
| MSI           | GF63 Thin 9RCX              | [aa2a33d3f0](https://linux-hardware.org/?probe=aa2a33d3f0) | Oct 21, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [55de21b8b0](https://linux-hardware.org/?probe=55de21b8b0) | Oct 21, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [1b5cd08b30](https://linux-hardware.org/?probe=1b5cd08b30) | Oct 21, 2021 |
| Apple         | MacBookPro12,1              | [271e56e195](https://linux-hardware.org/?probe=271e56e195) | Oct 21, 2021 |
| Apple         | MacBookPro12,1              | [3735576026](https://linux-hardware.org/?probe=3735576026) | Oct 21, 2021 |
| realme        | RMNBXXXX                    | [daa57fd7da](https://linux-hardware.org/?probe=daa57fd7da) | Oct 21, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0004... | [9facbd3d72](https://linux-hardware.org/?probe=9facbd3d72) | Oct 21, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [463b15301d](https://linux-hardware.org/?probe=463b15301d) | Oct 21, 2021 |
| HP            | 15                          | [b01898bb59](https://linux-hardware.org/?probe=b01898bb59) | Oct 21, 2021 |
| MSI           | GP72 2QD                    | [75801b27ae](https://linux-hardware.org/?probe=75801b27ae) | Oct 20, 2021 |
| MSI           | GP72 2QD                    | [bd12b3e948](https://linux-hardware.org/?probe=bd12b3e948) | Oct 20, 2021 |
| HP            | 650                         | [c32592cabb](https://linux-hardware.org/?probe=c32592cabb) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [c86d75dbbb](https://linux-hardware.org/?probe=c86d75dbbb) | Oct 20, 2021 |
| Medion        | E6226                       | [ebc0f3d72b](https://linux-hardware.org/?probe=ebc0f3d72b) | Oct 20, 2021 |
| Acer          | Nitro AN515-43              | [ac5870ab3d](https://linux-hardware.org/?probe=ac5870ab3d) | Oct 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| HUAWEI        | KLVL-WXX9                   | [4517a98ebf](https://linux-hardware.org/?probe=4517a98ebf) | Oct 20, 2021 |
| Apple         | MacBookPro9,2               | [0ec3c548af](https://linux-hardware.org/?probe=0ec3c548af) | Oct 19, 2021 |
| Lenovo        | ThinkPad T590 20N5S4Y100    | [f00be1a69f](https://linux-hardware.org/?probe=f00be1a69f) | Oct 19, 2021 |
| Dell          | Latitude 5400               | [8a880e6565](https://linux-hardware.org/?probe=8a880e6565) | Oct 19, 2021 |
| Dell          | Latitude 5400               | [0a94130eb2](https://linux-hardware.org/?probe=0a94130eb2) | Oct 19, 2021 |
| Lenovo        | ThinkPad T500 22437SG       | [0e26427d3d](https://linux-hardware.org/?probe=0e26427d3d) | Oct 19, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [8e04250418](https://linux-hardware.org/?probe=8e04250418) | Oct 19, 2021 |
| Lenovo        | G505 20240                  | [a878fe1079](https://linux-hardware.org/?probe=a878fe1079) | Oct 19, 2021 |
| Lenovo        | G505 20240                  | [4c254474e3](https://linux-hardware.org/?probe=4c254474e3) | Oct 19, 2021 |
| HUAWEI        | MACHD-WXX9                  | [8563f3786e](https://linux-hardware.org/?probe=8563f3786e) | Oct 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a16f7dac18](https://linux-hardware.org/?probe=a16f7dac18) | Oct 18, 2021 |
| Lenovo        | ThinkPad W530 244759G       | [e80bbd929f](https://linux-hardware.org/?probe=e80bbd929f) | Oct 18, 2021 |
| HP            | Compaq Presario CQ50        | [bb34275819](https://linux-hardware.org/?probe=bb34275819) | Oct 18, 2021 |
| MSI           | GF62 8RC                    | [89d77a3654](https://linux-hardware.org/?probe=89d77a3654) | Oct 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [080c5280d0](https://linux-hardware.org/?probe=080c5280d0) | Oct 17, 2021 |
| Lenovo        | ThinkPad T500 22437SG       | [751041603e](https://linux-hardware.org/?probe=751041603e) | Oct 17, 2021 |
| Dell          | Inspiron 15-3573            | [0eae8a7bf7](https://linux-hardware.org/?probe=0eae8a7bf7) | Oct 17, 2021 |
| ASUSTek       | G72GX                       | [48f6c89377](https://linux-hardware.org/?probe=48f6c89377) | Oct 17, 2021 |
| Dell          | XPS 15 9570                 | [26d1a4225d](https://linux-hardware.org/?probe=26d1a4225d) | Oct 17, 2021 |
| HP            | Pavilion dv6                | [b60dd43240](https://linux-hardware.org/?probe=b60dd43240) | Oct 17, 2021 |
| ASUSTek       | X501A                       | [b3e4d8035d](https://linux-hardware.org/?probe=b3e4d8035d) | Oct 17, 2021 |
| HP            | Laptop 17-by3xxx            | [e16a18bc8b](https://linux-hardware.org/?probe=e16a18bc8b) | Oct 17, 2021 |
| Dell          | Latitude 7490               | [adb96facbb](https://linux-hardware.org/?probe=adb96facbb) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | [87c7c24dcc](https://linux-hardware.org/?probe=87c7c24dcc) | Oct 17, 2021 |
| Acer          | ConceptD CN315-71P          | [50385dde8b](https://linux-hardware.org/?probe=50385dde8b) | Oct 16, 2021 |
| realme        | RMNBXXXX                    | [968a52c56a](https://linux-hardware.org/?probe=968a52c56a) | Oct 16, 2021 |
| HP            | EliteBook 8570w             | [492907a363](https://linux-hardware.org/?probe=492907a363) | Oct 16, 2021 |
| Medion        | E7218                       | [cca261a107](https://linux-hardware.org/?probe=cca261a107) | Oct 16, 2021 |
| Acer          | Extensa 2519                | [5b33aac7c5](https://linux-hardware.org/?probe=5b33aac7c5) | Oct 16, 2021 |
| Toshiba       | Satellite C660              | [c70057c643](https://linux-hardware.org/?probe=c70057c643) | Oct 16, 2021 |
| HUAWEI        | KLVL-WXX9                   | [ff0e6377ee](https://linux-hardware.org/?probe=ff0e6377ee) | Oct 16, 2021 |
| HP            | ZBook 17 G3                 | [11b17af506](https://linux-hardware.org/?probe=11b17af506) | Oct 16, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [c7fc550482](https://linux-hardware.org/?probe=c7fc550482) | Oct 16, 2021 |
| Apple         | MacBookPro12,1              | [4bfee9269a](https://linux-hardware.org/?probe=4bfee9269a) | Oct 16, 2021 |
| Sony          | VPCEB2S1E                   | [b42e7996bf](https://linux-hardware.org/?probe=b42e7996bf) | Oct 15, 2021 |
| Acer          | Aspire 7530G                | [09694e2816](https://linux-hardware.org/?probe=09694e2816) | Oct 15, 2021 |
| Dell          | Inspiron 15-3567            | [a629aeaa1b](https://linux-hardware.org/?probe=a629aeaa1b) | Oct 15, 2021 |
| Lenovo        | B570 1068GEG                | [cb2f8c100b](https://linux-hardware.org/?probe=cb2f8c100b) | Oct 15, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [c6478e67c7](https://linux-hardware.org/?probe=c6478e67c7) | Oct 15, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | [00196d9727](https://linux-hardware.org/?probe=00196d9727) | Oct 15, 2021 |
| Acer          | Aspire A715-75G             | [0d9ad64b08](https://linux-hardware.org/?probe=0d9ad64b08) | Oct 15, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0180... | [11539dc528](https://linux-hardware.org/?probe=11539dc528) | Oct 15, 2021 |
| Acer          | Aspire 7741                 | [2f093c19bf](https://linux-hardware.org/?probe=2f093c19bf) | Oct 15, 2021 |
| Dell          | XPS 13 9300                 | [22029905ac](https://linux-hardware.org/?probe=22029905ac) | Oct 15, 2021 |
| ASUSTek       | GL753VD                     | [a63eee78d3](https://linux-hardware.org/?probe=a63eee78d3) | Oct 14, 2021 |
| Dell          | Latitude E6520              | [b84ef4472b](https://linux-hardware.org/?probe=b84ef4472b) | Oct 14, 2021 |
| Google        | Treeya                      | [82b0964b6d](https://linux-hardware.org/?probe=82b0964b6d) | Oct 14, 2021 |
| Framework     | Laptop                      | [bd65852653](https://linux-hardware.org/?probe=bd65852653) | Oct 14, 2021 |
| Dell          | Latitude E6320              | [e8538ce77d](https://linux-hardware.org/?probe=e8538ce77d) | Oct 12, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [f8d957d29f](https://linux-hardware.org/?probe=f8d957d29f) | Oct 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [954005ca3d](https://linux-hardware.org/?probe=954005ca3d) | Oct 08, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c5495590b](https://linux-hardware.org/?probe=6c5495590b) | Oct 08, 2021 |
| Lenovo        | G570 20079                  | [81875a0613](https://linux-hardware.org/?probe=81875a0613) | Oct 06, 2021 |
| Dell          | XPS 13 7390                 | [66d13e4e24](https://linux-hardware.org/?probe=66d13e4e24) | Oct 03, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [08a44500da](https://linux-hardware.org/?probe=08a44500da) | Oct 03, 2021 |
| Lenovo        | G570 20079                  | [a0cac25f22](https://linux-hardware.org/?probe=a0cac25f22) | Oct 02, 2021 |
| Lenovo        | G570 20079                  | [93f8496968](https://linux-hardware.org/?probe=93f8496968) | Oct 02, 2021 |
| Dell          | XPS 13 7390                 | [c6882f7282](https://linux-hardware.org/?probe=c6882f7282) | Oct 01, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [2b03e34e82](https://linux-hardware.org/?probe=2b03e34e82) | Sep 30, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [1b81ca9e7a](https://linux-hardware.org/?probe=1b81ca9e7a) | Sep 29, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [51b49beb10](https://linux-hardware.org/?probe=51b49beb10) | Sep 28, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [fc93efcead](https://linux-hardware.org/?probe=fc93efcead) | Sep 25, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [8a2d72befe](https://linux-hardware.org/?probe=8a2d72befe) | Sep 24, 2021 |
| TUXEDO        | N7x0WU                      | [10f446b51e](https://linux-hardware.org/?probe=10f446b51e) | Sep 24, 2021 |
| Dell          | Precision 7710              | [fa8e5cdff5](https://linux-hardware.org/?probe=fa8e5cdff5) | Sep 23, 2021 |
| Acer          | Swift SFX14-41G             | [6b06b9e5dd](https://linux-hardware.org/?probe=6b06b9e5dd) | Sep 23, 2021 |
| Apple         | MacBookPro8,1               | [5b337fdb0a](https://linux-hardware.org/?probe=5b337fdb0a) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | [7c806aa7c5](https://linux-hardware.org/?probe=7c806aa7c5) | Sep 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [824a26d7e0](https://linux-hardware.org/?probe=824a26d7e0) | Sep 18, 2021 |
| Dell          | Vostro 3550                 | [1fe8420099](https://linux-hardware.org/?probe=1fe8420099) | Sep 17, 2021 |
| Dell          | Vostro 3550                 | [10f08c1bfd](https://linux-hardware.org/?probe=10f08c1bfd) | Sep 17, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [77d801bf3c](https://linux-hardware.org/?probe=77d801bf3c) | Sep 15, 2021 |
| HP            | ProBook 455 G6              | [8c5aa4304c](https://linux-hardware.org/?probe=8c5aa4304c) | Sep 14, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [c105819db0](https://linux-hardware.org/?probe=c105819db0) | Sep 13, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [04299c1c72](https://linux-hardware.org/?probe=04299c1c72) | Sep 10, 2021 |
| Lenovo        | G570 20079                  | [070f80905a](https://linux-hardware.org/?probe=070f80905a) | Sep 09, 2021 |
| Dell          | XPS 13 9310                 | [ce30239886](https://linux-hardware.org/?probe=ce30239886) | Sep 08, 2021 |
| Lenovo        | ThinkPad T470 20JNS3M500    | [1dcfa059c1](https://linux-hardware.org/?probe=1dcfa059c1) | Sep 07, 2021 |
| Lenovo        | V310-14IKB 80T2             | [9036570a3d](https://linux-hardware.org/?probe=9036570a3d) | Sep 07, 2021 |
| Dell          | XPS 13 9310                 | [a23d662013](https://linux-hardware.org/?probe=a23d662013) | Sep 06, 2021 |
| Lenovo        | G570 20079                  | [92d47c8db5](https://linux-hardware.org/?probe=92d47c8db5) | Sep 05, 2021 |
| Google        | Nautilus                    | [3b25f1b84a](https://linux-hardware.org/?probe=3b25f1b84a) | Sep 05, 2021 |
| Lenovo        | G570 20079                  | [897adf5520](https://linux-hardware.org/?probe=897adf5520) | Sep 04, 2021 |
| Lenovo        | ThinkPad T400 2768WGB       | [a66a6f00e4](https://linux-hardware.org/?probe=a66a6f00e4) | Sep 03, 2021 |
| Lenovo        | V310-14IKB 80T2             | [682d409384](https://linux-hardware.org/?probe=682d409384) | Sep 02, 2021 |
| Dell          | Latitude E6410              | [8b57d50d95](https://linux-hardware.org/?probe=8b57d50d95) | Sep 02, 2021 |
| ASUSTek       | GL753VD                     | [d17c6ba3fc](https://linux-hardware.org/?probe=d17c6ba3fc) | Sep 01, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [cae806f49d](https://linux-hardware.org/?probe=cae806f49d) | Aug 22, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [b8aa2e41d5](https://linux-hardware.org/?probe=b8aa2e41d5) | Aug 16, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [612dda8fba](https://linux-hardware.org/?probe=612dda8fba) | Aug 13, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [1eb6008b88](https://linux-hardware.org/?probe=1eb6008b88) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [808cfab06b](https://linux-hardware.org/?probe=808cfab06b) | Aug 12, 2021 |
| Lenovo        | ThinkPad T510 4484A63       | [c1bcb3451f](https://linux-hardware.org/?probe=c1bcb3451f) | Aug 09, 2021 |
| Lenovo        | ThinkPad T510 4484A63       | [4336b50906](https://linux-hardware.org/?probe=4336b50906) | Aug 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [961031411d](https://linux-hardware.org/?probe=961031411d) | Aug 03, 2021 |
| Lenovo        | ZhaoYang K3-ITL 82E3        | [ee2be4cea9](https://linux-hardware.org/?probe=ee2be4cea9) | Aug 03, 2021 |
| ASUSTek       | GL753VD                     | [eabe6a8723](https://linux-hardware.org/?probe=eabe6a8723) | Jul 31, 2021 |
| Acer          | Aspire 5920                 | [f41defe215](https://linux-hardware.org/?probe=f41defe215) | Jul 31, 2021 |
| Dell          | XPS 13 7390                 | [901bcb991b](https://linux-hardware.org/?probe=901bcb991b) | Jul 31, 2021 |
| Teclast       | F6 Pro                      | [e28004c24b](https://linux-hardware.org/?probe=e28004c24b) | Jul 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f5458b4f56](https://linux-hardware.org/?probe=f5458b4f56) | Jul 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [5ac65f3389](https://linux-hardware.org/?probe=5ac65f3389) | Jul 18, 2021 |
| Lenovo        | Z50-70 20354                | [85aadf8abd](https://linux-hardware.org/?probe=85aadf8abd) | Jul 16, 2021 |
| Lenovo        | Z50-70 20354                | [b2c80f450e](https://linux-hardware.org/?probe=b2c80f450e) | Jul 14, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| Lenovo        | ThinkPad X201 3626FAG       | [259908557b](https://linux-hardware.org/?probe=259908557b) | Jun 28, 2021 |
| Positivo      | H14BT58                     | [51b9ba65e0](https://linux-hardware.org/?probe=51b9ba65e0) | Jun 18, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [4befd5f360](https://linux-hardware.org/?probe=4befd5f360) | Jun 04, 2021 |
| Dell          | XPS 13 9343                 | [4ee08e92ae](https://linux-hardware.org/?probe=4ee08e92ae) | May 18, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                   | Notebooks | Percent |
|---------------------------|-----------|---------|
| 5.13.0-22-generic         | 166       | 22.19%  |
| 5.13.0-21-generic         | 147       | 19.65%  |
| 5.13.0-20-generic         | 107       | 14.3%   |
| 5.13.0-19-generic         | 85        | 11.36%  |
| 5.13.0-27-generic         | 62        | 8.29%   |
| 5.13.0-25-generic         | 44        | 5.88%   |
| 5.13.0-23-generic         | 44        | 5.88%   |
| 5.13.0-16-generic         | 14        | 1.87%   |
| 5.13.0-14-generic         | 8         | 1.07%   |
| 5.13.0-28-generic         | 7         | 0.94%   |
| 5.15.2-051502-generic     | 4         | 0.53%   |
| 5.11.0-20-generic         | 4         | 0.53%   |
| 5.15.0-051500-generic     | 3         | 0.4%    |
| 5.13.0-24-generic         | 3         | 0.4%    |
| 5.15.5-051505-generic     | 2         | 0.27%   |
| 5.15.4-051504-generic     | 2         | 0.27%   |
| 5.15.0-051500rc5-generic  | 2         | 0.27%   |
| 5.13.0-20-lowlatency      | 2         | 0.27%   |
| 5.11.0-40-generic         | 2         | 0.27%   |
| 5.11.0-38-generic         | 2         | 0.27%   |
| 5.11.0-37-generic         | 2         | 0.27%   |
| 5.11.0-25-generic         | 2         | 0.27%   |
| 5.11.0-18-generic         | 2         | 0.27%   |
| 5.16.0-051600rc8-generic  | 1         | 0.13%   |
| 5.16.0-051600rc3-generic  | 1         | 0.13%   |
| 5.16.0-051600rc2-generic  | 1         | 0.13%   |
| 5.16.0-051600rc1-generic  | 1         | 0.13%   |
| 5.15.7-051507-generic     | 1         | 0.13%   |
| 5.15.12-xanmod1           | 1         | 0.13%   |
| 5.15.12-051512-generic    | 1         | 0.13%   |
| 5.15.1-051501-generic     | 1         | 0.13%   |
| 5.15.0-5.4-liquorix-amd64 | 1         | 0.13%   |
| 5.14.17-051417-generic    | 1         | 0.13%   |
| 5.14.14-051414-generic    | 1         | 0.13%   |
| 5.14.13-051413-generic    | 1         | 0.13%   |
| 5.14.11-051411-generic    | 1         | 0.13%   |
| 5.14.0-1005-oem           | 1         | 0.13%   |
| 5.13.6-xanmod2-edge       | 1         | 0.13%   |
| 5.13.4-051304-generic     | 1         | 0.13%   |
| 5.13.2-051302-generic     | 1         | 0.13%   |
| 5.13.11-051311-generic    | 1         | 0.13%   |
| 5.13.0-27-lowlatency      | 1         | 0.13%   |
| 5.13.0-23-lowlatency      | 1         | 0.13%   |
| 5.13.0-21-lowlatency      | 1         | 0.13%   |
| 5.13.0-13-generic         | 1         | 0.13%   |
| 5.12.19-051219-generic    | 1         | 0.13%   |
| 5.11.0-50-generic         | 1         | 0.13%   |
| 5.11.0-41-generic         | 1         | 0.13%   |
| 5.11.0-31-generic         | 1         | 0.13%   |
| 5.11.0-26-generic         | 1         | 0.13%   |
| 5.11.0-22-generic         | 1         | 0.13%   |
| 5.11.0-16-generic         | 1         | 0.13%   |
| 5.10.77-051077-generic    | 1         | 0.13%   |
| 5.10.65-051065-generic    | 1         | 0.13%   |
| 5.10.0-1050-oem           | 1         | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13.0  | 660       | 92.31%  |
| 5.11.0  | 20        | 2.8%    |
| 5.15.0  | 6         | 0.84%   |
| 5.16.0  | 4         | 0.56%   |
| 5.15.2  | 4         | 0.56%   |
| 5.15.5  | 2         | 0.28%   |
| 5.15.4  | 2         | 0.28%   |
| 5.15.12 | 2         | 0.28%   |
| 5.15.7  | 1         | 0.14%   |
| 5.15.1  | 1         | 0.14%   |
| 5.14.17 | 1         | 0.14%   |
| 5.14.14 | 1         | 0.14%   |
| 5.14.13 | 1         | 0.14%   |
| 5.14.11 | 1         | 0.14%   |
| 5.14.0  | 1         | 0.14%   |
| 5.13.6  | 1         | 0.14%   |
| 5.13.4  | 1         | 0.14%   |
| 5.13.2  | 1         | 0.14%   |
| 5.13.11 | 1         | 0.14%   |
| 5.12.19 | 1         | 0.14%   |
| 5.10.77 | 1         | 0.14%   |
| 5.10.65 | 1         | 0.14%   |
| 5.10.0  | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.13    | 664       | 93%     |
| 5.11    | 20        | 2.8%    |
| 5.15    | 17        | 2.38%   |
| 5.14    | 5         | 0.7%    |
| 5.16    | 4         | 0.56%   |
| 5.10    | 3         | 0.42%   |
| 5.12    | 1         | 0.14%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 712       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 653       | 91.58%  |
| Unknown         | 35        | 4.91%   |
| GNOME Flashback | 9         | 1.26%   |
| Unity           | 5         | 0.7%    |
| X-Cinnamon      | 4         | 0.56%   |
| i3              | 2         | 0.28%   |
| Cinnamon        | 2         | 0.28%   |
| ICEWM           | 1         | 0.14%   |
| GNOME Classic   | 1         | 0.14%   |
| Deepin          | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 486       | 67.59%  |
| X11     | 211       | 29.35%  |
| Unknown | 20        | 2.78%   |
| Tty     | 2         | 0.28%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 374       | 52.16%  |
| GDM     | 263       | 36.68%  |
| Unknown | 64        | 8.93%   |
| LightDM | 11        | 1.53%   |
| SDDM    | 3         | 0.42%   |
| TDM     | 1         | 0.14%   |
| Ly      | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 312       | 43.76%  |
| de_DE   | 74        | 10.38%  |
| en_GB   | 54        | 7.57%   |
| fr_FR   | 38        | 5.33%   |
| ru_RU   | 26        | 3.65%   |
| it_IT   | 21        | 2.95%   |
| pt_BR   | 18        | 2.52%   |
| en_IN   | 18        | 2.52%   |
| es_ES   | 17        | 2.38%   |
| en_CA   | 15        | 2.1%    |
| en_AU   | 15        | 2.1%    |
| cs_CZ   | 14        | 1.96%   |
| Unknown | 8         | 1.12%   |
| hu_HU   | 6         | 0.84%   |
| es_MX   | 6         | 0.84%   |
| zh_CN   | 5         | 0.7%    |
| pl_PL   | 5         | 0.7%    |
| de_CH   | 5         | 0.7%    |
| C       | 5         | 0.7%    |
| sv_SE   | 4         | 0.56%   |
| es_CL   | 4         | 0.56%   |
| da_DK   | 4         | 0.56%   |
| tr_TR   | 3         | 0.42%   |
| pt_PT   | 3         | 0.42%   |
| nl_NL   | 3         | 0.42%   |
| es_AR   | 3         | 0.42%   |
| en_NZ   | 3         | 0.42%   |
| ko_KR   | 2         | 0.28%   |
| id_ID   | 2         | 0.28%   |
| fr_CA   | 2         | 0.28%   |
| fi_FI   | 2         | 0.28%   |
| de_AT   | 2         | 0.28%   |
| sl_SI   | 1         | 0.14%   |
| ru_UA   | 1         | 0.14%   |
| ro_RO   | 1         | 0.14%   |
| nl_BE   | 1         | 0.14%   |
| lt_LT   | 1         | 0.14%   |
| es_UY   | 1         | 0.14%   |
| es_PE   | 1         | 0.14%   |
| en_ZM   | 1         | 0.14%   |
| en_ZA   | 1         | 0.14%   |
| en_IL   | 1         | 0.14%   |
| en_IE   | 1         | 0.14%   |
| el_GR   | 1         | 0.14%   |
| de_IT   | 1         | 0.14%   |
| bg_BG   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 406       | 56.47%  |
| EFI  | 313       | 43.53%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 653       | 91.71%  |
| Zfs      | 20        | 2.81%   |
| Overlay  | 19        | 2.67%   |
| Btrfs    | 12        | 1.69%   |
| Ext3     | 3         | 0.42%   |
| Ext2     | 2         | 0.28%   |
| Xfs      | 1         | 0.14%   |
| Reiserfs | 1         | 0.14%   |
| Unknown  | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 429       | 59.92%  |
| GPT     | 272       | 37.99%  |
| MBR     | 15        | 2.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 646       | 90.22%  |
| Yes       | 70        | 9.78%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 431       | 60.28%  |
| Yes       | 284       | 39.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                         | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Lenovo                                       | 150       | 21.07%  |
| Dell                                         | 129       | 18.12%  |
| Hewlett-Packard                              | 121       | 16.99%  |
| Acer                                         | 61        | 8.57%   |
| ASUSTek Computer                             | 59        | 8.29%   |
| MSI                                          | 20        | 2.81%   |
| HUAWEI                                       | 19        | 2.67%   |
| Toshiba                                      | 18        | 2.53%   |
| Apple                                        | 16        | 2.25%   |
| Samsung Electronics                          | 15        | 2.11%   |
| Sony                                         | 13        | 1.83%   |
| Timi                                         | 8         | 1.12%   |
| Medion                                       | 7         | 0.98%   |
| Fujitsu                                      | 7         | 0.98%   |
| Packard Bell                                 | 6         | 0.84%   |
| Razer                                        | 5         | 0.7%    |
| Notebook                                     | 5         | 0.7%    |
| Google                                       | 4         | 0.56%   |
| Avell High Performance                       | 4         | 0.56%   |
| realme                                       | 3         | 0.42%   |
| Positivo                                     | 3         | 0.42%   |
| Framework                                    | 3         | 0.42%   |
| Clevo                                        | 3         | 0.42%   |
| Wortmann AG                                  | 2         | 0.28%   |
| TUXEDO                                       | 2         | 0.28%   |
| Teclast                                      | 2         | 0.28%   |
| PC Specialist                                | 2         | 0.28%   |
| LG Electronics                               | 2         | 0.28%   |
| Fujitsu Siemens                              | 2         | 0.28%   |
| Alienware                                    | 2         | 0.28%   |
| YJKC                                         | 1         | 0.14%   |
| win element                                  | 1         | 0.14%   |
| System76                                     | 1         | 0.14%   |
| Schenker                                     | 1         | 0.14%   |
| Panasonic                                    | 1         | 0.14%   |
| NCS-Tech                                     | 1         | 0.14%   |
| MOTILE                                       | 1         | 0.14%   |
| Jumper                                       | 1         | 0.14%   |
| Jooyontech Computer                          | 1         | 0.14%   |
| Jemper                                       | 1         | 0.14%   |
| HONOR                                        | 1         | 0.14%   |
| Exo                                          | 1         | 0.14%   |
| eMachines                                    | 1         | 0.14%   |
| DukaPC                                       | 1         | 0.14%   |
| Direkt-Tek                                   | 1         | 0.14%   |
| CHUWI Innovation And Technology(ShenZhen)c0. | 1         | 0.14%   |
| AVITA                                        | 1         | 0.14%   |
| Acidanthera                                  | 1         | 0.14%   |
| Unknown                                      | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Dell XPS 13 9310                                      | 6         | 0.84%   |
| Acer Swift SF314-43                                   | 6         | 0.84%   |
| HUAWEI KLVL-WXX9                                      | 5         | 0.7%    |
| HP Pavilion Aero Laptop 13-be0xxx                     | 5         | 0.7%    |
| Dell XPS 15 9570                                      | 5         | 0.7%    |
| Dell XPS 15 9500                                      | 5         | 0.7%    |
| Dell XPS 13 9300                                      | 4         | 0.56%   |
| Dell Inspiron 5570                                    | 4         | 0.56%   |
| realme RMNBXXXX                                       | 3         | 0.42%   |
| HUAWEI HVY-WXX9                                       | 3         | 0.42%   |
| HP Pavilion Notebook                                  | 3         | 0.42%   |
| HP Pavilion dv6                                       | 3         | 0.42%   |
| Framework Laptop                                      | 3         | 0.42%   |
| Dell XPS 15 7590                                      | 3         | 0.42%   |
| Dell XPS 13 9305                                      | 3         | 0.42%   |
| Dell XPS 13 7390                                      | 3         | 0.42%   |
| Dell Latitude E6410                                   | 3         | 0.42%   |
| Dell Latitude 5420                                    | 3         | 0.42%   |
| Dell Inspiron 15-3567                                 | 3         | 0.42%   |
| Apple MacBookPro12,1                                  | 3         | 0.42%   |
| Acer Swift SF314-42                                   | 3         | 0.42%   |
| Acer Aspire A515-56                                   | 3         | 0.42%   |
| Timi A35S                                             | 2         | 0.28%   |
| Samsung R430/P430/R480                                | 2         | 0.28%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 2         | 0.28%   |
| Lenovo Z50-70 20354                                   | 2         | 0.28%   |
| Lenovo ThinkPad T400 2768WGB                          | 2         | 0.28%   |
| Lenovo Legion Y530-15ICH 81FV                         | 2         | 0.28%   |
| Lenovo IdeaPad S340-15API 81NC                        | 2         | 0.28%   |
| Lenovo IdeaPad Flex-14API 81SS                        | 2         | 0.28%   |
| Lenovo IdeaPad 330-15AST 81D6                         | 2         | 0.28%   |
| Lenovo IdeaPad 3 15IIL05 81WE                         | 2         | 0.28%   |
| Lenovo G40-80 80E4                                    | 2         | 0.28%   |
| HUAWEI NBLK-WAX9X                                     | 2         | 0.28%   |
| HUAWEI NBLB-WAX9N                                     | 2         | 0.28%   |
| HUAWEI MACHD-WXX9                                     | 2         | 0.28%   |
| HUAWEI MACH-WX9                                       | 2         | 0.28%   |
| HP ProBook 6450b                                      | 2         | 0.28%   |
| HP ProBook 4510s                                      | 2         | 0.28%   |
| HP ProBook 440 G7                                     | 2         | 0.28%   |
| HP ProBook 440 G6                                     | 2         | 0.28%   |
| HP ProBook 440 G5                                     | 2         | 0.28%   |
| HP Pavilion Gaming Laptop 15-dk0xxx                   | 2         | 0.28%   |
| HP Pavilion dv7                                       | 2         | 0.28%   |
| HP Notebook                                           | 2         | 0.28%   |
| HP Laptop 15s-fq1xxx                                  | 2         | 0.28%   |
| HP Laptop 14-fq1xxx                                   | 2         | 0.28%   |
| HP ENVY 17                                            | 2         | 0.28%   |
| HP EliteBook 8540p                                    | 2         | 0.28%   |
| HP EliteBook 840 G2                                   | 2         | 0.28%   |
| HP 15                                                 | 2         | 0.28%   |
| Dell XPS 17 9710                                      | 2         | 0.28%   |
| Dell XPS 17 9700                                      | 2         | 0.28%   |
| Dell XPS 15 9510                                      | 2         | 0.28%   |
| Dell Latitude E7470                                   | 2         | 0.28%   |
| Dell Latitude E6520                                   | 2         | 0.28%   |
| Dell Latitude E6400                                   | 2         | 0.28%   |
| Dell Latitude 7490                                    | 2         | 0.28%   |
| Dell Latitude 5520                                    | 2         | 0.28%   |
| Dell Inspiron 1545                                    | 2         | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 72        | 10.11%  |
| Dell Latitude               | 40        | 5.62%   |
| Lenovo IdeaPad              | 39        | 5.48%   |
| Dell XPS                    | 38        | 5.34%   |
| Dell Inspiron               | 34        | 4.78%   |
| Acer Aspire                 | 32        | 4.49%   |
| HP ProBook                  | 30        | 4.21%   |
| HP Pavilion                 | 27        | 3.79%   |
| HP EliteBook                | 20        | 2.81%   |
| Acer Swift                  | 19        | 2.67%   |
| HP Laptop                   | 16        | 2.25%   |
| Toshiba Satellite           | 14        | 1.97%   |
| ASUS VivoBook               | 11        | 1.54%   |
| ASUS ROG                    | 10        | 1.4%    |
| Lenovo ThinkBook            | 7         | 0.98%   |
| Fujitsu LIFEBOOK            | 7         | 0.98%   |
| Dell Precision              | 7         | 0.98%   |
| ASUS TUF                    | 7         | 0.98%   |
| Packard Bell EasyNote       | 6         | 0.84%   |
| HP ZBook                    | 6         | 0.84%   |
| Razer Blade                 | 5         | 0.7%    |
| HUAWEI KLVL-WXX9            | 5         | 0.7%    |
| Lenovo Legion               | 4         | 0.56%   |
| HP ENVY                     | 4         | 0.56%   |
| ASUS ZenBook                | 4         | 0.56%   |
| Toshiba PORTEGE             | 3         | 0.42%   |
| realme RMNBXXXX             | 3         | 0.42%   |
| HUAWEI HVY-WXX9             | 3         | 0.42%   |
| HP 15                       | 3         | 0.42%   |
| Framework Laptop            | 3         | 0.42%   |
| Dell Vostro                 | 3         | 0.42%   |
| Apple MacBookPro12          | 3         | 0.42%   |
| Acer Nitro                  | 3         | 0.42%   |
| Timi A35S                   | 2         | 0.28%   |
| Samsung R430                | 2         | 0.28%   |
| MSI Prestige                | 2         | 0.28%   |
| MSI GT70                    | 2         | 0.28%   |
| MSI GE62                    | 2         | 0.28%   |
| Lenovo Z50-70               | 2         | 0.28%   |
| Lenovo G780                 | 2         | 0.28%   |
| Lenovo G580                 | 2         | 0.28%   |
| Lenovo G40-80               | 2         | 0.28%   |
| HUAWEI NBLK-WAX9X           | 2         | 0.28%   |
| HUAWEI NBLB-WAX9N           | 2         | 0.28%   |
| HUAWEI MACHD-WXX9           | 2         | 0.28%   |
| HUAWEI MACH-WX9             | 2         | 0.28%   |
| HP Notebook                 | 2         | 0.28%   |
| HP 255                      | 2         | 0.28%   |
| HP 250                      | 2         | 0.28%   |
| Fujitsu Siemens ESPRIMO     | 2         | 0.28%   |
| Dell G15                    | 2         | 0.28%   |
| Avell High Performance B.ON | 2         | 0.28%   |
| Avell High Performance A70  | 2         | 0.28%   |
| ASUS X550VX                 | 2         | 0.28%   |
| ASUS ASUS                   | 2         | 0.28%   |
| Apple MacBookPro9           | 2         | 0.28%   |
| Apple MacBookPro8           | 2         | 0.28%   |
| Apple MacBookPro11          | 2         | 0.28%   |
| Alienware 17                | 2         | 0.28%   |
| Acer Predator               | 2         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 119       | 16.71%  |
| 2020 | 114       | 16.01%  |
| 2019 | 76        | 10.67%  |
| 2018 | 60        | 8.43%   |
| 2017 | 50        | 7.02%   |
| 2012 | 46        | 6.46%   |
| 2011 | 41        | 5.76%   |
| 2016 | 38        | 5.34%   |
| 2010 | 35        | 4.92%   |
| 2014 | 31        | 4.35%   |
| 2015 | 27        | 3.79%   |
| 2013 | 26        | 3.65%   |
| 2008 | 24        | 3.37%   |
| 2009 | 18        | 2.53%   |
| 2007 | 7         | 0.98%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 712       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 617       | 86.54%  |
| Enabled  | 96        | 13.46%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 708       | 99.44%  |
| Yes  | 4         | 0.56%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 224       | 31.37%  |
| 16.01-24.0  | 133       | 18.63%  |
| 3.01-4.0    | 125       | 17.51%  |
| 8.01-16.0   | 115       | 16.11%  |
| 32.01-64.0  | 73        | 10.22%  |
| 64.01-256.0 | 16        | 2.24%   |
| 1.01-2.0    | 11        | 1.54%   |
| 2.01-3.0    | 9         | 1.26%   |
| 24.01-32.0  | 7         | 0.98%   |
| 0.51-1.0    | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 249       | 33.74%  |
| 2.01-3.0   | 208       | 28.18%  |
| 4.01-8.0   | 134       | 18.16%  |
| 3.01-4.0   | 104       | 14.09%  |
| 8.01-16.0  | 30        | 4.07%   |
| 0.51-1.0   | 10        | 1.36%   |
| 16.01-24.0 | 2         | 0.27%   |
| 24.01-32.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 530       | 74.13%  |
| 2      | 155       | 21.68%  |
| 3      | 24        | 3.36%   |
| 4      | 3         | 0.42%   |
| 0      | 3         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 484       | 67.79%  |
| Yes       | 230       | 32.21%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 521       | 73.07%  |
| No        | 192       | 26.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 703       | 98.74%  |
| No        | 9         | 1.26%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 584       | 81.91%  |
| No        | 129       | 18.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| Germany            | 104       | 14.57%  |
| USA                | 91        | 12.75%  |
| France             | 49        | 6.86%   |
| UK                 | 39        | 5.46%   |
| Russia             | 39        | 5.46%   |
| Italy              | 37        | 5.18%   |
| Brazil             | 24        | 3.36%   |
| India              | 22        | 3.08%   |
| Czechia            | 22        | 3.08%   |
| Spain              | 19        | 2.66%   |
| Canada             | 19        | 2.66%   |
| Ukraine            | 15        | 2.1%    |
| Poland             | 15        | 2.1%    |
| Australia          | 15        | 2.1%    |
| Netherlands        | 13        | 1.82%   |
| Sweden             | 12        | 1.68%   |
| Denmark            | 12        | 1.68%   |
| Switzerland        | 11        | 1.54%   |
| Mexico             | 9         | 1.26%   |
| Romania            | 8         | 1.12%   |
| Hungary            | 8         | 1.12%   |
| Finland            | 8         | 1.12%   |
| Portugal           | 7         | 0.98%   |
| Indonesia          | 7         | 0.98%   |
| Austria            | 7         | 0.98%   |
| Turkey             | 6         | 0.84%   |
| Chile              | 6         | 0.84%   |
| Vietnam            | 4         | 0.56%   |
| South Korea        | 4         | 0.56%   |
| New Zealand        | 4         | 0.56%   |
| Iran               | 4         | 0.56%   |
| China              | 4         | 0.56%   |
| Belgium            | 4         | 0.56%   |
| Tunisia            | 3         | 0.42%   |
| Serbia             | 3         | 0.42%   |
| Pakistan           | 3         | 0.42%   |
| Greece             | 3         | 0.42%   |
| Bulgaria           | 3         | 0.42%   |
| Argentina          | 3         | 0.42%   |
| Uganda             | 2         | 0.28%   |
| UAE                | 2         | 0.28%   |
| Morocco            | 2         | 0.28%   |
| Lebanon            | 2         | 0.28%   |
| Latvia             | 2         | 0.28%   |
| Japan              | 2         | 0.28%   |
| Ireland            | 2         | 0.28%   |
| Guadeloupe         | 2         | 0.28%   |
| Egypt              | 2         | 0.28%   |
| Dominican Republic | 2         | 0.28%   |
| Cyprus             | 2         | 0.28%   |
| Zambia             | 1         | 0.14%   |
| Uzbekistan         | 1         | 0.14%   |
| Uruguay            | 1         | 0.14%   |
| Thailand           | 1         | 0.14%   |
| Tanzania           | 1         | 0.14%   |
| Syria              | 1         | 0.14%   |
| Slovenia           | 1         | 0.14%   |
| Slovakia           | 1         | 0.14%   |
| R?�union           | 1         | 0.14%   |
| Puerto Rico        | 1         | 0.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 14        | 1.93%   |
| Moscow            | 13        | 1.79%   |
| Prague            | 11        | 1.52%   |
| Paris             | 11        | 1.52%   |
| Kyiv              | 8         | 1.1%    |
| Warsaw            | 6         | 0.83%   |
| Milan             | 6         | 0.83%   |
| Vienna            | 5         | 0.69%   |
| S??o Paulo        | 5         | 0.69%   |
| Santiago          | 5         | 0.69%   |
| Munich            | 5         | 0.69%   |
| Helsinki          | 5         | 0.69%   |
| Frankfurt am Main | 5         | 0.69%   |
| Rome              | 4         | 0.55%   |
| Perth             | 4         | 0.55%   |
| Madrid            | 4         | 0.55%   |
| Winterthur        | 3         | 0.41%   |
| Vlasikha          | 3         | 0.41%   |
| Vancouver         | 3         | 0.41%   |
| Turin             | 3         | 0.41%   |
| Toronto           | 3         | 0.41%   |
| Stuttgart         | 3         | 0.41%   |
| Stockholm         | 3         | 0.41%   |
| Samara            | 3         | 0.41%   |
| New York          | 3         | 0.41%   |
| Mexico City       | 3         | 0.41%   |
| London            | 3         | 0.41%   |
| Lisbon            | 3         | 0.41%   |
| Leipzig           | 3         | 0.41%   |
| Lahore            | 3         | 0.41%   |
| Krasnodar         | 3         | 0.41%   |
| Krakow            | 3         | 0.41%   |
| Istanbul          | 3         | 0.41%   |
| Hanoi             | 3         | 0.41%   |
| Frechen           | 3         | 0.41%   |
| Dresden           | 3         | 0.41%   |
| Budapest          | 3         | 0.41%   |
| Bucharest         | 3         | 0.41%   |
| Brescia           | 3         | 0.41%   |
| Auckland          | 3         | 0.41%   |
| Zurich            | 2         | 0.28%   |
| Washington        | 2         | 0.28%   |
| Turku             | 2         | 0.28%   |
| Tehran            | 2         | 0.28%   |
| Tatab??nya        | 2         | 0.28%   |
| Sydney            | 2         | 0.28%   |
| Surabaya          | 2         | 0.28%   |
| St Petersburg     | 2         | 0.28%   |
| Seattle           | 2         | 0.28%   |
| San Jose          | 2         | 0.28%   |
| Sainte-Anne       | 2         | 0.28%   |
| Saarbr??cken      | 2         | 0.28%   |
| Riga              | 2         | 0.28%   |
| Pune              | 2         | 0.28%   |
| Porto Alegre      | 2         | 0.28%   |
| Pilsen            | 2         | 0.28%   |
| Omaha             | 2         | 0.28%   |
| Odense            | 2         | 0.28%   |
| Newtown           | 2         | 0.28%   |
| New Delhi         | 2         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 154       | 180    | 17.64%  |
| WDC                            | 109       | 115    | 12.49%  |
| Seagate                        | 97        | 109    | 11.11%  |
| Toshiba                        | 77        | 81     | 8.82%   |
| SK Hynix                       | 56        | 59     | 6.41%   |
| Sandisk                        | 54        | 59     | 6.19%   |
| Kingston                       | 45        | 52     | 5.15%   |
| Unknown                        | 38        | 42     | 4.35%   |
| Micron Technology              | 25        | 26     | 2.86%   |
| Intel                          | 23        | 27     | 2.63%   |
| HGST                           | 21        | 23     | 2.41%   |
| KIOXIA                         | 20        | 20     | 2.29%   |
| Crucial                        | 20        | 22     | 2.29%   |
| Hitachi                        | 17        | 19     | 1.95%   |
| A-DATA Technology              | 10        | 12     | 1.15%   |
| LITEON                         | 9         | 9      | 1.03%   |
| Phison                         | 8         | 10     | 0.92%   |
| Apple                          | 6         | 9      | 0.69%   |
| Intenso                        | 4         | 4      | 0.46%   |
| YMTC                           | 3         | 3      | 0.34%   |
| SPCC                           | 3         | 4      | 0.34%   |
| Solid State Storage Technology | 3         | 3      | 0.34%   |
| Patriot                        | 3         | 3      | 0.34%   |
| Micron/Crucial Technology      | 3         | 3      | 0.34%   |
| Lite-On                        | 3         | 3      | 0.34%   |
| Lexar                          | 3         | 3      | 0.34%   |
| Fujitsu                        | 3         | 3      | 0.34%   |
| China                          | 3         | 4      | 0.34%   |
| Transcend                      | 2         | 2      | 0.23%   |
| Teclast                        | 2         | 2      | 0.23%   |
| SABRENT                        | 2         | 2      | 0.23%   |
| Realtek                        | 2         | 2      | 0.23%   |
| PNY                            | 2         | 2      | 0.23%   |
| LITEONIT                       | 2         | 2      | 0.23%   |
| JMicron                        | 2         | 2      | 0.23%   |
| Emtec                          | 2         | 2      | 0.23%   |
| Corsair                        | 2         | 3      | 0.23%   |
| ASMT                           | 2         | 2      | 0.23%   |
| ADATA Technology               | 2         | 2      | 0.23%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.11%   |
| XPG                            | 1         | 2      | 0.11%   |
| Verbatim                       | 1         | 1      | 0.11%   |
| ValueTech                      | 1         | 1      | 0.11%   |
| Union Memory                   | 1         | 1      | 0.11%   |
| Team                           | 1         | 1      | 0.11%   |
| SSSTC                          | 1         | 1      | 0.11%   |
| SSK                            | 1         | 1      | 0.11%   |
| SP                             | 1         | 1      | 0.11%   |
| Realtek Semiconductor          | 1         | 1      | 0.11%   |
| PLEXTOR                        | 1         | 1      | 0.11%   |
| OSCOO                          | 1         | 1      | 0.11%   |
| ORTIAL                         | 1         | 1      | 0.11%   |
| OCZ                            | 1         | 1      | 0.11%   |
| Netac                          | 1         | 1      | 0.11%   |
| Lenovo                         | 1         | 1      | 0.11%   |
| LDLC                           | 1         | 1      | 0.11%   |
| KingSpec                       | 1         | 1      | 0.11%   |
| KingDian                       | 1         | 1      | 0.11%   |
| Hoodisk                        | 1         | 1      | 0.11%   |
| HECTRON                        | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 20        | 2.2%    |
| Samsung NVMe SSD Drive 512GB        | 19        | 2.09%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 12        | 1.32%   |
| Toshiba MQ04ABF100 1TB              | 10        | 1.1%    |
| Kingston SA400S37240G 240GB SSD     | 10        | 1.1%    |
| Sandisk NVMe SSD Drive 512GB        | 9         | 0.99%   |
| Sandisk NVMe SSD Drive 256GB        | 8         | 0.88%   |
| Samsung SSD 860 EVO 500GB           | 8         | 0.88%   |
| Unknown MMC Card  64GB              | 7         | 0.77%   |
| Toshiba MQ01ABF050 500GB            | 7         | 0.77%   |
| Toshiba MQ01ABD100 1TB              | 7         | 0.77%   |
| SK Hynix NVMe SSD Drive 1024GB      | 7         | 0.77%   |
| Samsung NVMe SSD Drive 1024GB       | 7         | 0.77%   |
| Toshiba NVMe SSD Drive 512GB        | 6         | 0.66%   |
| Seagate Expansion 1TB               | 6         | 0.66%   |
| Samsung NVMe SSD Drive 256GB        | 6         | 0.66%   |
| Micron NVMe SSD Drive 512GB         | 6         | 0.66%   |
| HGST HTS721010A9E630 1TB            | 6         | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 5         | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB            | 5         | 0.55%   |
| SK Hynix NVMe SSD Drive 512GB       | 5         | 0.55%   |
| Seagate ST9500325AS 500GB           | 5         | 0.55%   |
| Seagate ST2000LM007-1R8174 2TB      | 5         | 0.55%   |
| Kingston OM8PDP3512B-AA1 512GB      | 5         | 0.55%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 4         | 0.44%   |
| WDC WD5000LPCX-24VHAT0 500GB        | 4         | 0.44%   |
| WDC WD10SPZX-21Z10T0 1TB            | 4         | 0.44%   |
| Unknown MMC Card  128GB             | 4         | 0.44%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 4         | 0.44%   |
| SK Hynix PC711 NVMe 512GB           | 4         | 0.44%   |
| SK Hynix HFM001TD3JX013N 1TB        | 4         | 0.44%   |
| Seagate ST9320423AS 320GB           | 4         | 0.44%   |
| Seagate ST2000LM015-2E8174 2TB      | 4         | 0.44%   |
| Sandisk NVMe SSD Drive 1024GB       | 4         | 0.44%   |
| Samsung SSD 970 EVO Plus 1TB        | 4         | 0.44%   |
| Samsung SSD 970 EVO 1TB             | 4         | 0.44%   |
| Samsung SSD 860 EVO 1TB             | 4         | 0.44%   |
| Samsung NVMe SSD Drive 1TB          | 4         | 0.44%   |
| KIOXIA KBG40ZNV512G 512GB           | 4         | 0.44%   |
| Kingston SA400S37480G 480GB SSD     | 4         | 0.44%   |
| HGST HTS541010A9E680 1TB            | 4         | 0.44%   |
| YMTC PC005 512GB                    | 3         | 0.33%   |
| WDC WDS500G2B0C-00PXH0 500GB        | 3         | 0.33%   |
| WDC WD10SPZX-08Z10 1TB              | 3         | 0.33%   |
| Unknown SD32G  32GB                 | 3         | 0.33%   |
| Unknown MMC Card  4GB               | 3         | 0.33%   |
| Toshiba NVMe SSD Drive 1024GB       | 3         | 0.33%   |
| SK Hynix PC401 NVMe 512GB           | 3         | 0.33%   |
| SK Hynix HFM512GDJTNI-82A0A 512GB   | 3         | 0.33%   |
| Seagate ST9250410AS 250GB           | 3         | 0.33%   |
| Seagate ST9250315AS 250GB           | 3         | 0.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 3         | 0.33%   |
| Seagate ST320LT020-9YG142 320GB     | 3         | 0.33%   |
| Seagate ST1000LM049-2GH172 1TB      | 3         | 0.33%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD | 3         | 0.33%   |
| Sandisk NVMe SSD Drive 500GB        | 3         | 0.33%   |
| Sandisk NVMe SSD Drive 1TB          | 3         | 0.33%   |
| Samsung SSD 970 EVO 500GB           | 3         | 0.33%   |
| Samsung SSD 860 EVO 250GB           | 3         | 0.33%   |
| Samsung SSD 850 EVO 500GB           | 3         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 95        | 106    | 39.09%  |
| WDC                 | 58        | 60     | 23.87%  |
| Toshiba             | 44        | 46     | 18.11%  |
| HGST                | 21        | 23     | 8.64%   |
| Hitachi             | 17        | 19     | 7%      |
| Samsung Electronics | 3         | 4      | 1.23%   |
| Fujitsu             | 3         | 3      | 1.23%   |
| Unknown             | 1         | 2      | 0.41%   |
| External            | 1         | 1      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 53        | 55     | 22.65%  |
| Kingston            | 28        | 32     | 11.97%  |
| SanDisk             | 24        | 26     | 10.26%  |
| Crucial             | 17        | 18     | 7.26%   |
| WDC                 | 14        | 14     | 5.98%   |
| Toshiba             | 13        | 13     | 5.56%   |
| Micron Technology   | 8         | 8      | 3.42%   |
| LITEON              | 8         | 8      | 3.42%   |
| SK Hynix            | 7         | 8      | 2.99%   |
| Apple               | 5         | 5      | 2.14%   |
| Intenso             | 4         | 4      | 1.71%   |
| Intel               | 4         | 4      | 1.71%   |
| SPCC                | 3         | 4      | 1.28%   |
| Patriot             | 3         | 3      | 1.28%   |
| Lexar               | 3         | 3      | 1.28%   |
| China               | 3         | 4      | 1.28%   |
| A-DATA Technology   | 3         | 4      | 1.28%   |
| Transcend           | 2         | 2      | 0.85%   |
| Teclast             | 2         | 2      | 0.85%   |
| SABRENT             | 2         | 2      | 0.85%   |
| LITEONIT            | 2         | 2      | 0.85%   |
| Emtec               | 2         | 2      | 0.85%   |
| Corsair             | 2         | 3      | 0.85%   |
| Verbatim            | 1         | 1      | 0.43%   |
| ValueTech           | 1         | 1      | 0.43%   |
| Team                | 1         | 1      | 0.43%   |
| Seagate             | 1         | 1      | 0.43%   |
| PNY                 | 1         | 1      | 0.43%   |
| PLEXTOR             | 1         | 1      | 0.43%   |
| OSCOO               | 1         | 1      | 0.43%   |
| ORTIAL              | 1         | 1      | 0.43%   |
| OCZ                 | 1         | 1      | 0.43%   |
| Netac               | 1         | 1      | 0.43%   |
| LDLC                | 1         | 1      | 0.43%   |
| KingSpec            | 1         | 1      | 0.43%   |
| KingDian            | 1         | 1      | 0.43%   |
| Hoodisk             | 1         | 1      | 0.43%   |
| GOODRAM             | 1         | 1      | 0.43%   |
| Freecom             | 1         | 1      | 0.43%   |
| DRVEO               | 1         | 2      | 0.43%   |
| Dogfish             | 1         | 1      | 0.43%   |
| CT500MX5            | 1         | 1      | 0.43%   |
| ASMT                | 1         | 1      | 0.43%   |
| Apacer              | 1         | 1      | 0.43%   |
| AMD                 | 1         | 2      | 0.43%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 335       | 399    | 39.83%  |
| HDD     | 237       | 264    | 28.18%  |
| SSD     | 223       | 250    | 26.52%  |
| MMC     | 38        | 41     | 4.52%   |
| Unknown | 8         | 10     | 0.95%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 413       | 496    | 50.99%  |
| NVMe | 334       | 395    | 41.23%  |
| MMC  | 38        | 41     | 4.69%   |
| SAS  | 25        | 32     | 3.09%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 292       | 337    | 64.18%  |
| 0.51-1.0   | 142       | 156    | 31.21%  |
| 1.01-2.0   | 19        | 19     | 4.18%   |
| 4.01-10.0  | 2         | 2      | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 221       | 30.65%  |
| 101-250        | 207       | 28.71%  |
| 501-1000       | 114       | 15.81%  |
| 51-100         | 53        | 7.35%   |
| 1001-2000      | 41        | 5.69%   |
| 1-20           | 35        | 4.85%   |
| 21-50          | 22        | 3.05%   |
| 2001-3000      | 12        | 1.66%   |
| Unknown        | 9         | 1.25%   |
| More than 3000 | 7         | 0.97%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 272       | 37.31%  |
| 21-50          | 148       | 20.3%   |
| 51-100         | 109       | 14.95%  |
| 101-250        | 103       | 14.13%  |
| 251-500        | 46        | 6.31%   |
| 501-1000       | 26        | 3.57%   |
| 1001-2000      | 10        | 1.37%   |
| Unknown        | 9         | 1.23%   |
| More than 3000 | 3         | 0.41%   |
| 2001-3000      | 3         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3      | 7.89%   |
| WDC WD5000BEVT-22A0RT0 500GB             | 2         | 2      | 5.26%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD    | 2         | 2      | 5.26%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 3      | 5.26%   |
| LITEON CV8-8E128-HP 128GB SSD            | 2         | 2      | 5.26%   |
| Hitachi HTS543232A7A384 320GB            | 2         | 2      | 5.26%   |
| HGST HTS541010A9E680 1TB                 | 2         | 2      | 5.26%   |
| WDC WD5000BEVT-26A0RT0 500GB             | 1         | 1      | 2.63%   |
| WDC WD10JPVT-08A1YT2 1TB                 | 1         | 1      | 2.63%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 2.63%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD100M 1TB                  | 1         | 1      | 2.63%   |
| Toshiba MK3276GSX 320GB                  | 1         | 1      | 2.63%   |
| SK Hynix PC401 NVMe 512GB                | 1         | 1      | 2.63%   |
| Seagate ST9500325AS 500GB                | 1         | 1      | 2.63%   |
| Seagate ST9250827AS 250GB                | 1         | 1      | 2.63%   |
| Seagate ST500LT012-9WS142 500GB          | 1         | 1      | 2.63%   |
| Seagate ST320LT020-9YG142 320GB          | 1         | 1      | 2.63%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 1      | 2.63%   |
| SanDisk SD7SN3Q-256G-1006 256GB SSD      | 1         | 1      | 2.63%   |
| Kingston SV300S37A120G 120GB SSD         | 1         | 2      | 2.63%   |
| Hitachi HTS725032A9A364 320GB            | 1         | 1      | 2.63%   |
| Hitachi HTS543232L9A300 320GB            | 1         | 1      | 2.63%   |
| HGST HTS725050A7E630 500GB               | 1         | 1      | 2.63%   |
| HGST HTS725032A7E630 320GB               | 1         | 1      | 2.63%   |
| HGST HTS545050A7E680 500GB               | 1         | 1      | 2.63%   |
| Crucial CT1050MX300SSD1 1050GB           | 1         | 1      | 2.63%   |
| Crucial CT1000MX500SSD1 1TB              | 1         | 1      | 2.63%   |
| ASMT 2115 500GB                          | 1         | 1      | 2.63%   |
| A-DATA Technology IM2P33F3A NVMe 256GB   | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 10        | 11     | 26.32%  |
| HGST              | 5         | 5      | 13.16%  |
| WDC               | 4         | 4      | 10.53%  |
| Toshiba           | 4         | 4      | 10.53%  |
| Hitachi           | 4         | 4      | 10.53%  |
| SK Hynix          | 3         | 3      | 7.89%   |
| LITEON            | 2         | 2      | 5.26%   |
| Crucial           | 2         | 2      | 5.26%   |
| SanDisk           | 1         | 1      | 2.63%   |
| Kingston          | 1         | 2      | 2.63%   |
| ASMT              | 1         | 1      | 2.63%   |
| A-DATA Technology | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 10        | 11     | 38.46%  |
| HGST    | 5         | 5      | 19.23%  |
| WDC     | 4         | 4      | 15.38%  |
| Hitachi | 4         | 4      | 15.38%  |
| Toshiba | 3         | 3      | 11.54%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 26        | 27     | 68.42%  |
| SSD  | 10        | 11     | 26.32%  |
| NVMe | 2         | 2      | 5.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZVLB1T0HALR-00000 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 434       | 580    | 57.33%  |
| Works    | 284       | 343    | 37.52%  |
| Malfunc  | 38        | 40     | 5.02%   |
| Failed   | 1         | 1      | 0.13%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 457       | 52.05%  |
| Samsung Electronics            | 106       | 12.07%  |
| AMD                            | 80        | 9.11%   |
| Sandisk                        | 66        | 7.52%   |
| SK Hynix                       | 49        | 5.58%   |
| Toshiba America Info Systems   | 24        | 2.73%   |
| Micron Technology              | 17        | 1.94%   |
| Kingston Technology Company    | 17        | 1.94%   |
| KIOXIA                         | 14        | 1.59%   |
| Phison Electronics             | 10        | 1.14%   |
| ADATA Technology               | 8         | 0.91%   |
| Nvidia                         | 6         | 0.68%   |
| Micron/Crucial Technology      | 5         | 0.57%   |
| Yangtze Memory Technologies    | 4         | 0.46%   |
| Lite-On Technology             | 4         | 0.46%   |
| Solid State Storage Technology | 3         | 0.34%   |
| Realtek Semiconductor          | 2         | 0.23%   |
| Marvell Technology Group       | 2         | 0.23%   |
| ASMedia Technology             | 2         | 0.23%   |
| Lenovo                         | 1         | 0.11%   |
| Apple                          | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 73        | 7.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 50        | 5.38%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 43        | 4.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 42        | 4.52%   |
| Samsung NVMe SSD Controller 980                                                  | 42        | 4.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 41        | 4.41%   |
| Intel Volume Management Device NVMe RAID Controller                              | 37        | 3.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 34        | 3.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 28        | 3.01%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 24        | 2.58%   |
| SK Hynix Gold P31 SSD                                                            | 23        | 2.47%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 21        | 2.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 20        | 2.15%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 18        | 1.94%   |
| Micron Non-Volatile memory controller                                            | 17        | 1.83%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 15        | 1.61%   |
| KIOXIA Non-Volatile memory controller                                            | 14        | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 1.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 14        | 1.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 13        | 1.4%    |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 13        | 1.4%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 13        | 1.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 11        | 1.18%   |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 1.18%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 1.18%   |
| Intel SSD 660P Series                                                            | 10        | 1.08%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 10        | 1.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 10        | 1.08%   |
| SK Hynix Non-Volatile memory controller                                          | 9         | 0.97%   |
| SK Hynix BC511                                                                   | 9         | 0.97%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 0.97%   |
| Sandisk Non-Volatile memory controller                                           | 8         | 0.86%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 8         | 0.86%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 7         | 0.75%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 7         | 0.75%   |
| Sandisk PC SN520 NVMe SSD                                                        | 7         | 0.75%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 7         | 0.75%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 7         | 0.75%   |
| Intel Non-Volatile memory controller                                             | 7         | 0.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 0.75%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 0.75%   |
| ADATA Non-Volatile memory controller                                             | 6         | 0.65%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 5         | 0.54%   |
| Phison PS5013 E13 NVMe Controller                                                | 5         | 0.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 5         | 0.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 0.54%   |
| Yangtze Memory Non-Volatile memory controller                                    | 4         | 0.43%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 4         | 0.43%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 4         | 0.43%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.43%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 4         | 0.43%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 4         | 0.43%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                    | 4         | 0.43%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                    | 4         | 0.43%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.32%   |
| Solid State Storage Non-Volatile memory controller                               | 3         | 0.32%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 459       | 51.23%  |
| NVMe | 331       | 36.94%  |
| RAID | 80        | 8.93%   |
| IDE  | 26        | 2.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 572       | 80.34%  |
| AMD    | 140       | 19.66%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 25        | 3.51%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 18        | 2.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 12        | 1.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 12        | 1.69%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz         | 12        | 1.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 12        | 1.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 10        | 1.4%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 10        | 1.4%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 10        | 1.4%    |
| AMD Ryzen 5 4500U with Radeon Graphics          | 10        | 1.4%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 9         | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 9         | 1.26%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 9         | 1.26%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 9         | 1.26%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 9         | 1.26%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 8         | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 8         | 1.12%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 8         | 1.12%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 8         | 1.12%   |
| Intel Core i7-10875H CPU @ 2.30GHz              | 7         | 0.98%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz              | 7         | 0.98%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 7         | 0.98%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 7         | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 7         | 0.98%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 6         | 0.84%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 6         | 0.84%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 6         | 0.84%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 6         | 0.84%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 6         | 0.84%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 5         | 0.7%    |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 5         | 0.7%    |
| Intel Core i7-4510U CPU @ 2.00GHz               | 5         | 0.7%    |
| Intel Core i7-2620M CPU @ 2.70GHz               | 5         | 0.7%    |
| Intel Core i7-10510U CPU @ 1.80GHz              | 5         | 0.7%    |
| Intel Core i5-9300H CPU @ 2.40GHz               | 5         | 0.7%    |
| Intel Core i5-6300U CPU @ 2.40GHz               | 5         | 0.7%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 5         | 0.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz               | 5         | 0.7%    |
| Intel 11th Gen Core i7-11370H @ 3.30GHz         | 5         | 0.7%    |
| AMD Ryzen 9 5900HS with Radeon Graphics         | 5         | 0.7%    |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 5         | 0.7%    |
| AMD Ryzen 5 4600H with Radeon Graphics          | 5         | 0.7%    |
| Intel Pentium Silver N5000 CPU @ 1.10GHz        | 4         | 0.56%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 4         | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 4         | 0.56%   |
| Intel Core i7-3520M CPU @ 2.90GHz               | 4         | 0.56%   |
| Intel Core i5-8350U CPU @ 1.70GHz               | 4         | 0.56%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 4         | 0.56%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 4         | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 4         | 0.56%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz            | 4         | 0.56%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz            | 4         | 0.56%   |
| Intel 11th Gen Core i5-1145G7 @ 2.60GHz         | 4         | 0.56%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 4         | 0.56%   |
| AMD Ryzen 7 5800U with Radeon Graphics          | 4         | 0.56%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 4         | 0.56%   |
| AMD Ryzen 5 5600U with Radeon Graphics          | 4         | 0.56%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 4         | 0.56%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 4         | 0.56%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 3         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 169       | 23.74%  |
| Intel Core i7                  | 153       | 21.49%  |
| Other                          | 94        | 13.2%   |
| Intel Core i3                  | 49        | 6.88%   |
| AMD Ryzen 5                    | 44        | 6.18%   |
| Intel Celeron                  | 36        | 5.06%   |
| AMD Ryzen 7                    | 34        | 4.78%   |
| Intel Core 2 Duo               | 33        | 4.63%   |
| Intel Pentium                  | 13        | 1.83%   |
| AMD Ryzen 9                    | 9         | 1.26%   |
| Intel Core i9                  | 7         | 0.98%   |
| Intel Pentium Silver           | 6         | 0.84%   |
| AMD Ryzen 7 PRO                | 6         | 0.84%   |
| AMD E2                         | 6         | 0.84%   |
| AMD A10                        | 6         | 0.84%   |
| Intel Pentium Dual-Core        | 5         | 0.7%    |
| AMD Ryzen 3                    | 5         | 0.7%    |
| Intel Atom                     | 4         | 0.56%   |
| AMD A6                         | 4         | 0.56%   |
| Intel Core m3                  | 3         | 0.42%   |
| AMD Ryzen 5 PRO                | 3         | 0.42%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.28%   |
| AMD E1                         | 2         | 0.28%   |
| AMD E                          | 2         | 0.28%   |
| AMD A8                         | 2         | 0.28%   |
| AMD A4                         | 2         | 0.28%   |
| Intel Pentium Dual             | 1         | 0.14%   |
| Intel Core m7                  | 1         | 0.14%   |
| Intel Core M                   | 1         | 0.14%   |
| Intel Core 2                   | 1         | 0.14%   |
| Intel Celeron Dual-Core        | 1         | 0.14%   |
| AMD Sempron                    | 1         | 0.14%   |
| AMD QC                         | 1         | 0.14%   |
| AMD PRO A8                     | 1         | 0.14%   |
| AMD PRO A10                    | 1         | 0.14%   |
| AMD Phenom II                  | 1         | 0.14%   |
| AMD FX                         | 1         | 0.14%   |
| AMD Athlon II Dual-Core        | 1         | 0.14%   |
| AMD Athlon                     | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 297       | 41.71%  |
| 4      | 271       | 38.06%  |
| 6      | 71        | 9.97%   |
| 8      | 67        | 9.41%   |
| 1      | 5         | 0.7%    |
| 3      | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 712       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 566       | 79.49%  |
| 1      | 146       | 20.51%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 712       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 382       | 52.91%  |
| 0x806c1    | 54        | 7.48%   |
| 0x0a50000c | 22        | 3.05%   |
| 0xa0652    | 18        | 2.49%   |
| 0x706e5    | 18        | 2.49%   |
| 0x906ea    | 17        | 2.35%   |
| 0x806ea    | 16        | 2.22%   |
| 0x806ec    | 15        | 2.08%   |
| 0x306a9    | 14        | 1.94%   |
| 0x08600106 | 14        | 1.94%   |
| 0x806d1    | 13        | 1.8%    |
| 0x806e9    | 11        | 1.52%   |
| 0x206a7    | 9         | 1.25%   |
| 0x906e9    | 8         | 1.11%   |
| 0x306d4    | 8         | 1.11%   |
| 0x08608103 | 8         | 1.11%   |
| 0x406e3    | 7         | 0.97%   |
| 0x1067a    | 7         | 0.97%   |
| 0x08608102 | 7         | 0.97%   |
| 0x806eb    | 6         | 0.83%   |
| 0x306c3    | 6         | 0.83%   |
| 0x20655    | 5         | 0.69%   |
| 0x08108102 | 5         | 0.69%   |
| 0x506e3    | 4         | 0.55%   |
| 0x406c4    | 4         | 0.55%   |
| 0x08600102 | 4         | 0.55%   |
| 0x806c2    | 3         | 0.42%   |
| 0x706a8    | 3         | 0.42%   |
| 0x506c9    | 3         | 0.42%   |
| 0x40651    | 3         | 0.42%   |
| 0x08108109 | 3         | 0.42%   |
| 0x906c0    | 2         | 0.28%   |
| 0x706a1    | 2         | 0.28%   |
| 0x406c3    | 2         | 0.28%   |
| 0x20652    | 2         | 0.28%   |
| 0x0a50000b | 2         | 0.28%   |
| 0x06006705 | 2         | 0.28%   |
| 0x0600611a | 2         | 0.28%   |
| 0x906ed    | 1         | 0.14%   |
| 0x30678    | 1         | 0.14%   |
| 0x30673    | 1         | 0.14%   |
| 0x106ca    | 1         | 0.14%   |
| 0x08600104 | 1         | 0.14%   |
| 0x08101007 | 1         | 0.14%   |
| 0x06006704 | 1         | 0.14%   |
| 0x06006118 | 1         | 0.14%   |
| 0x06006113 | 1         | 0.14%   |
| 0x06006110 | 1         | 0.14%   |
| 0x02000032 | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 145       | 20.34%  |
| TigerLake       | 72        | 10.1%   |
| SandyBridge     | 48        | 6.73%   |
| IvyBridge       | 45        | 6.31%   |
| IceLake         | 36        | 5.05%   |
| Penryn          | 35        | 4.91%   |
| Westmere        | 34        | 4.77%   |
| Haswell         | 34        | 4.77%   |
| Skylake         | 29        | 4.07%   |
| Zen 3           | 27        | 3.79%   |
| Zen 2           | 27        | 3.79%   |
| CometLake       | 26        | 3.65%   |
| Unknown         | 26        | 3.65%   |
| Zen+            | 21        | 2.95%   |
| Silvermont      | 20        | 2.81%   |
| Broadwell       | 19        | 2.66%   |
| Excavator       | 16        | 2.24%   |
| Goldmont plus   | 10        | 1.4%    |
| Core            | 8         | 1.12%   |
| Zen             | 6         | 0.84%   |
| Jaguar          | 4         | 0.56%   |
| Goldmont        | 4         | 0.56%   |
| Bobcat          | 4         | 0.56%   |
| Puma            | 3         | 0.42%   |
| K8 & K10 hybrid | 3         | 0.42%   |
| K10 Llano       | 3         | 0.42%   |
| Tremont         | 2         | 0.28%   |
| Steamroller     | 2         | 0.28%   |
| K10             | 2         | 0.28%   |
| Piledriver      | 1         | 0.14%   |
| Bonnell         | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 530       | 57.99%  |
| Nvidia | 210       | 22.98%  |
| AMD    | 174       | 19.04%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 67        | 7.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 44        | 4.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 41        | 4.42%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 35        | 3.77%   |
| Intel UHD Graphics 620                                                                   | 34        | 3.66%   |
| AMD Renoir                                                                               | 27        | 2.91%   |
| AMD Cezanne                                                                              | 26        | 2.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 2.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 22        | 2.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 2.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 21        | 2.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 2.26%   |
| AMD Lucienne                                                                             | 21        | 2.26%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 2.05%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 16        | 1.72%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 16        | 1.72%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 1.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 15        | 1.62%   |
| Intel HD Graphics 620                                                                    | 15        | 1.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 1.62%   |
| Intel HD Graphics 630                                                                    | 14        | 1.51%   |
| Intel HD Graphics 5500                                                                   | 13        | 1.4%    |
| Intel HD Graphics 530                                                                    | 11        | 1.19%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.19%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 1.19%   |
| Nvidia GP108M [GeForce MX150]                                                            | 10        | 1.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 1.08%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 10        | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.97%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 8         | 0.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 0.86%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 7         | 0.75%   |
| Intel Iris Plus Graphics G7                                                              | 7         | 0.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.65%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 6         | 0.65%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 6         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.65%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 0.65%   |
| Nvidia TU117M [GeForce MX450]                                                            | 5         | 0.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.54%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 0.54%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 0.54%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 5         | 0.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 0.54%   |
| Intel Comet Lake UHD Graphics                                                            | 5         | 0.54%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 4         | 0.43%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.43%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 4         | 0.43%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 0.43%   |
| Intel Tiger Lake UHD Graphics                                                            | 4         | 0.43%   |
| Intel HD Graphics 500                                                                    | 4         | 0.43%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.43%   |
| Nvidia TU117M                                                                            | 3         | 0.32%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 0.32%   |
| Nvidia GP108M [GeForce MX250]                                                            | 3         | 0.32%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 345       | 48.46%  |
| Intel + Nvidia | 163       | 22.89%  |
| 1 x AMD        | 130       | 18.26%  |
| 1 x Nvidia     | 29        | 4.07%   |
| Intel + AMD    | 21        | 2.95%   |
| AMD + Nvidia   | 17        | 2.39%   |
| 2 x AMD        | 6         | 0.84%   |
| 2 x Nvidia     | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 583       | 81.42%  |
| Proprietary | 122       | 17.04%  |
| Unknown     | 11        | 1.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 574       | 80.5%   |
| 0.01-0.5   | 58        | 8.13%   |
| 1.01-2.0   | 33        | 4.63%   |
| 3.01-4.0   | 23        | 3.23%   |
| 0.51-1.0   | 12        | 1.68%   |
| 7.01-8.0   | 6         | 0.84%   |
| 5.01-6.0   | 6         | 0.84%   |
| 8.01-16.0  | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 146       | 17.76%  |
| BOE                     | 120       | 14.6%   |
| LG Display              | 114       | 13.87%  |
| Chimei Innolux          | 111       | 13.5%   |
| Samsung Electronics     | 77        | 9.37%   |
| Sharp                   | 45        | 5.47%   |
| Dell                    | 23        | 2.8%    |
| Lenovo                  | 22        | 2.68%   |
| Apple                   | 17        | 2.07%   |
| Chi Mei Optoelectronics | 15        | 1.82%   |
| PANDA                   | 12        | 1.46%   |
| Goldstar                | 12        | 1.46%   |
| Acer                    | 12        | 1.46%   |
| Hewlett-Packard         | 11        | 1.34%   |
| Philips                 | 8         | 0.97%   |
| InfoVision              | 8         | 0.97%   |
| Ancor Communications    | 7         | 0.85%   |
| CSO                     | 6         | 0.73%   |
| BenQ                    | 6         | 0.73%   |
| AOC                     | 6         | 0.73%   |
| LG Philips              | 5         | 0.61%   |
| Sony                    | 4         | 0.49%   |
| Unknown                 | 3         | 0.36%   |
| KDC                     | 3         | 0.36%   |
| Iiyama                  | 3         | 0.36%   |
| JDI                     | 2         | 0.24%   |
| Westinghouse            | 1         | 0.12%   |
| ViewSonic               | 1         | 0.12%   |
| TMX                     | 1         | 0.12%   |
| TIANMA XM               | 1         | 0.12%   |
| TCL                     | 1         | 0.12%   |
| STA                     | 1         | 0.12%   |
| SLD                     | 1         | 0.12%   |
| Seiko/Epson             | 1         | 0.12%   |
| Sceptre Tech            | 1         | 0.12%   |
| Plain Tree Systems      | 1         | 0.12%   |
| NEC Computers           | 1         | 0.12%   |
| MStar                   | 1         | 0.12%   |
| Mi                      | 1         | 0.12%   |
| LLL                     | 1         | 0.12%   |
| KEB                     | 1         | 0.12%   |
| JXC                     | 1         | 0.12%   |
| Hitachi                 | 1         | 0.12%   |
| GDH                     | 1         | 0.12%   |
| DZX                     | 1         | 0.12%   |
| CVT                     | 1         | 0.12%   |
| CPT                     | 1         | 0.12%   |
| CMN                     | 1         | 0.12%   |
| ASUSTek Computer        | 1         | 0.12%   |
| AOpen                   | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.96%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.96%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 8         | 0.96%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.96%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 7         | 0.84%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.72%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 6         | 0.72%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.72%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 5         | 0.6%    |
| Chimei Innolux P140ZKA-BZ1 CMN8C03 2160x1440 296x197mm 14.0-inch         | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 5         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.6%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.6%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                    | 5         | 0.6%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 5         | 0.6%    |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                  | 4         | 0.48%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch    | 4         | 0.48%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch             | 4         | 0.48%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 4         | 0.48%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 4         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.48%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.48%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.48%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 3         | 0.36%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 3         | 0.36%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 3         | 0.36%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 3         | 0.36%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.36%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 3         | 0.36%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 3         | 0.36%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 3         | 0.36%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 3         | 0.36%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 3         | 0.36%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                    | 3         | 0.36%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.36%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 3         | 0.36%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.36%   |
| AU Optronics LCD Monitor AUOA08B 1920x1080 344x193mm 15.5-inch           | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 3         | 0.36%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 3         | 0.36%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                | 2         | 0.24%   |
| Sony Nvidia Defaul SNY05FA 1366x768 290x170mm 13.2-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP14CB 1920x1200 288x180mm 13.4-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.24%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                  | 2         | 0.24%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 797x333mm 34.0-inch        | 2         | 0.24%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 2         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 346       | 44.94%  |
| 1366x768 (WXGA)    | 187       | 24.29%  |
| 1600x900 (HD+)     | 40        | 5.19%   |
| 2560x1440 (QHD)    | 28        | 3.64%   |
| 1280x800 (WXGA)    | 27        | 3.51%   |
| 3840x2160 (4K)     | 26        | 3.38%   |
| 1920x1200 (WUXGA)  | 22        | 2.86%   |
| 2560x1600          | 15        | 1.95%   |
| 1440x900 (WXGA+)   | 14        | 1.82%   |
| 3840x2400          | 12        | 1.56%   |
| 2160x1440          | 12        | 1.56%   |
| 3440x1440          | 8         | 1.04%   |
| 1280x1024 (SXGA)   | 6         | 0.78%   |
| 3456x2160          | 4         | 0.52%   |
| 3000x2000          | 4         | 0.52%   |
| 2880x1800          | 3         | 0.39%   |
| 2256x1504          | 3         | 0.39%   |
| 2288x1287          | 2         | 0.26%   |
| 1680x1050 (WSXGA+) | 2         | 0.26%   |
| 3840x1100          | 1         | 0.13%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 2880x1920          | 1         | 0.13%   |
| 2560x1080          | 1         | 0.13%   |
| 2240x1400          | 1         | 0.13%   |
| 2048x1152          | 1         | 0.13%   |
| 1720x1440          | 1         | 0.13%   |
| 1680x945           | 1         | 0.13%   |
| 1360x768           | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 337       | 41.1%   |
| 13      | 137       | 16.71%  |
| 14      | 109       | 13.29%  |
| 17      | 61        | 7.44%   |
| 27      | 32        | 3.9%    |
| 24      | 28        | 3.41%   |
| 12      | 18        | 2.2%    |
| 23      | 15        | 1.83%   |
| 16      | 11        | 1.34%   |
| 21      | 10        | 1.22%   |
| 19      | 10        | 1.22%   |
| 34      | 8         | 0.98%   |
| 18      | 6         | 0.73%   |
| Unknown | 6         | 0.73%   |
| 32      | 5         | 0.61%   |
| 35      | 3         | 0.37%   |
| 31      | 3         | 0.37%   |
| 28      | 3         | 0.37%   |
| 11      | 3         | 0.37%   |
| 142     | 2         | 0.24%   |
| 25      | 2         | 0.24%   |
| 22      | 2         | 0.24%   |
| 84      | 1         | 0.12%   |
| 72      | 1         | 0.12%   |
| 52      | 1         | 0.12%   |
| 44      | 1         | 0.12%   |
| 40      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 26      | 1         | 0.12%   |
| 20      | 1         | 0.12%   |
| 10      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 497       | 61.13%  |
| 201-300        | 108       | 13.28%  |
| 501-600        | 75        | 9.23%   |
| 351-400        | 73        | 8.98%   |
| 401-500        | 22        | 2.71%   |
| 701-800        | 15        | 1.85%   |
| 601-700        | 8         | 0.98%   |
| Unknown        | 6         | 0.74%   |
| 801-900        | 3         | 0.37%   |
| More than 2000 | 2         | 0.25%   |
| 1501-2000      | 2         | 0.25%   |
| 1001-1500      | 1         | 0.12%   |
| 901-1000       | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 582       | 79.51%  |
| 16/10   | 103       | 14.07%  |
| 3/2     | 21        | 2.87%   |
| 21/9    | 10        | 1.37%   |
| 5/4     | 7         | 0.96%   |
| Unknown | 4         | 0.55%   |
| 1.00    | 2         | 0.27%   |
| 6/5     | 1         | 0.14%   |
| 3.40    | 1         | 0.14%   |
| 2.01    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 338       | 41.27%  |
| 81-90          | 189       | 23.08%  |
| 71-80          | 56        | 6.84%   |
| 121-130        | 51        | 6.23%   |
| 201-250        | 43        | 5.25%   |
| 301-350        | 32        | 3.91%   |
| 351-500        | 23        | 2.81%   |
| 61-70          | 18        | 2.2%    |
| 151-200        | 14        | 1.71%   |
| 251-300        | 10        | 1.22%   |
| 141-150        | 9         | 1.1%    |
| 131-140        | 8         | 0.98%   |
| 111-120        | 7         | 0.85%   |
| Unknown        | 6         | 0.73%   |
| More than 1000 | 5         | 0.61%   |
| 51-60          | 4         | 0.49%   |
| 91-100         | 3         | 0.37%   |
| 501-1000       | 2         | 0.24%   |
| 41-50          | 1         | 0.12%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 329       | 40.67%  |
| 101-120       | 231       | 28.55%  |
| 51-100        | 116       | 14.34%  |
| 161-240       | 82        | 10.14%  |
| More than 240 | 40        | 4.94%   |
| Unknown       | 6         | 0.74%   |
| 1-50          | 5         | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 567       | 79.19%  |
| 2     | 117       | 16.34%  |
| 0     | 19        | 2.65%   |
| 3     | 11        | 1.54%   |
| 6     | 1         | 0.14%   |
| 4     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 409       | 37.01%  |
| Realtek Semiconductor             | 346       | 31.31%  |
| Qualcomm Atheros                  | 151       | 13.67%  |
| Broadcom                          | 50        | 4.52%   |
| MEDIATEK                          | 23        | 2.08%   |
| Broadcom Limited                  | 20        | 1.81%   |
| Marvell Technology Group          | 18        | 1.63%   |
| TP-Link                           | 11        | 1%      |
| Ralink                            | 10        | 0.9%    |
| DisplayLink                       | 9         | 0.81%   |
| Qualcomm                          | 5         | 0.45%   |
| Sierra Wireless                   | 4         | 0.36%   |
| Samsung Electronics               | 4         | 0.36%   |
| Nvidia                            | 4         | 0.36%   |
| Lenovo                            | 4         | 0.36%   |
| Ericsson Business Mobile Networks | 4         | 0.36%   |
| Dell                              | 4         | 0.36%   |
| Xiaomi                            | 3         | 0.27%   |
| Toshiba                           | 3         | 0.27%   |
| Ralink Technology                 | 2         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.18%   |
| Microsoft                         | 2         | 0.18%   |
| JMicron Technology                | 2         | 0.18%   |
| D-Link                            | 2         | 0.18%   |
| ASIX Electronics                  | 2         | 0.18%   |
| Texas Instruments                 | 1         | 0.09%   |
| OPPO Electronics                  | 1         | 0.09%   |
| Motorola PCS                      | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| LG Electronics                    | 1         | 0.09%   |
| Hewlett-Packard                   | 1         | 0.09%   |
| Franklin Wireless                 | 1         | 0.09%   |
| Foxconn / Hon Hai                 | 1         | 0.09%   |
| Fibocom                           | 1         | 0.09%   |
| Edimax Technology                 | 1         | 0.09%   |
| Aquantia                          | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 209       | 16.13%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 52        | 4.01%   |
| Intel Wi-Fi 6 AX201                                               | 52        | 4.01%   |
| Intel Wi-Fi 6 AX200                                               | 46        | 3.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 37        | 2.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 36        | 2.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 27        | 2.08%   |
| Intel Wireless 8265 / 8275                                        | 26        | 2.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 25        | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 23        | 1.77%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 21        | 1.62%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 20        | 1.54%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 19        | 1.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 18        | 1.39%   |
| Intel Wireless 7260                                               | 17        | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 16        | 1.23%   |
| Intel Wireless 7265                                               | 16        | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 15        | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 15        | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 15        | 1.16%   |
| Intel 82577LM Gigabit Network Connection                          | 15        | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 14        | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 13        | 1%      |
| Intel Wireless 8260                                               | 13        | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 13        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 12        | 0.93%   |
| Intel Wireless 3165                                               | 11        | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 11        | 0.85%   |
| Intel Centrino Advanced-N 6200                                    | 10        | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                     | 10        | 0.77%   |
| Intel WiFi Link 5100                                              | 9         | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 8         | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 8         | 0.62%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 8         | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 0.62%   |
| Intel Wireless-AC 9260                                            | 8         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 8         | 0.62%   |
| Intel Centrino Ultimate-N 6300                                    | 8         | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 7         | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 6         | 0.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 6         | 0.46%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 6         | 0.46%   |
| Intel Wireless 3160                                               | 6         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 0.46%   |
| Intel Centrino Wireless-N 2230                                    | 6         | 0.46%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.46%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 5         | 0.39%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 5         | 0.39%   |
| Intel Ethernet Connection (13) I219-V                             | 5         | 0.39%   |
| Intel Ethernet Connection (13) I219-LM                            | 5         | 0.39%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                     | 5         | 0.39%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 5         | 0.39%   |
| DisplayLink LAPDOCK                                               | 5         | 0.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.39%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.31%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 390       | 53.57%  |
| Qualcomm Atheros      | 128       | 17.58%  |
| Realtek Semiconductor | 100       | 13.74%  |
| Broadcom              | 36        | 4.95%   |
| MEDIATEK              | 22        | 3.02%   |
| Broadcom Limited      | 14        | 1.92%   |
| Ralink                | 10        | 1.37%   |
| TP-Link               | 8         | 1.1%    |
| Qualcomm              | 5         | 0.69%   |
| Sierra Wireless       | 4         | 0.55%   |
| Ralink Technology     | 2         | 0.27%   |
| Microsoft             | 2         | 0.27%   |
| Dell                  | 2         | 0.27%   |
| Linksys               | 1         | 0.14%   |
| Hewlett-Packard       | 1         | 0.14%   |
| Fibocom               | 1         | 0.14%   |
| Edimax Technology     | 1         | 0.14%   |
| D-Link                | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 52        | 7.12%   |
| Intel Wi-Fi 6 AX200                                            | 46        | 6.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 37        | 5.07%   |
| Intel Wireless 8265 / 8275                                     | 26        | 3.56%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 25        | 3.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23        | 3.15%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 21        | 2.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 20        | 2.74%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 2.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 18        | 2.47%   |
| Intel Wireless 7260                                            | 17        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 16        | 2.19%   |
| Intel Wireless 7265                                            | 16        | 2.19%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 15        | 2.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 15        | 2.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 15        | 2.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 14        | 1.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 1.78%   |
| Intel Wireless 8260                                            | 13        | 1.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 13        | 1.78%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 12        | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 12        | 1.64%   |
| Intel Wireless 3165                                            | 11        | 1.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 11        | 1.51%   |
| Intel Centrino Advanced-N 6200                                 | 10        | 1.37%   |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 1.37%   |
| Intel WiFi Link 5100                                           | 9         | 1.23%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 8         | 1.1%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 8         | 1.1%    |
| Intel Wireless-AC 9260                                         | 8         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 8         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                 | 8         | 1.1%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 6         | 0.82%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 0.82%   |
| Intel Wireless 3160                                            | 6         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 0.82%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 0.82%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 5         | 0.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 5         | 0.68%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 5         | 0.68%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 5         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 0.55%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.55%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 0.55%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 4         | 0.55%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.55%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.55%   |
| TP-Link 802.11ac WLAN Adapter                                  | 3         | 0.41%   |
| Sierra Wireless MC8305 Modem                                   | 3         | 0.41%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 3         | 0.41%   |
| Realtek Realtek Network controller                             | 3         | 0.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.41%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 3         | 0.41%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 0.41%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 3         | 0.41%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.41%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 302       | 55.01%  |
| Intel                         | 125       | 22.77%  |
| Qualcomm Atheros              | 37        | 6.74%   |
| Broadcom                      | 21        | 3.83%   |
| Marvell Technology Group      | 18        | 3.28%   |
| DisplayLink                   | 9         | 1.64%   |
| Broadcom Limited              | 6         | 1.09%   |
| Samsung Electronics           | 4         | 0.73%   |
| Nvidia                        | 4         | 0.73%   |
| Lenovo                        | 4         | 0.73%   |
| Xiaomi                        | 3         | 0.55%   |
| TP-Link                       | 3         | 0.55%   |
| OnePlus Technology (Shenzhen) | 2         | 0.36%   |
| JMicron Technology            | 2         | 0.36%   |
| ASIX Electronics              | 2         | 0.36%   |
| OPPO Electronics              | 1         | 0.18%   |
| Motorola PCS                  | 1         | 0.18%   |
| MediaTek                      | 1         | 0.18%   |
| LG Electronics                | 1         | 0.18%   |
| Foxconn / Hon Hai             | 1         | 0.18%   |
| D-Link                        | 1         | 0.18%   |
| Aquantia                      | 1         | 0.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 209       | 37.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 52        | 9.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 36        | 6.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 27        | 4.86%   |
| Intel 82577LM Gigabit Network Connection                                       | 15        | 2.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 8         | 1.44%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 1.44%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 1.26%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 6         | 1.08%   |
| Intel Ethernet Connection I219-LM                                              | 6         | 1.08%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 1.08%   |
| Intel Ethernet Connection (13) I219-V                                          | 5         | 0.9%    |
| Intel Ethernet Connection (13) I219-LM                                         | 5         | 0.9%    |
| DisplayLink LAPDOCK                                                            | 5         | 0.9%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 0.9%    |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 0.72%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 4         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                                          | 4         | 0.72%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 0.72%   |
| Intel 82579V Gigabit Network Connection                                        | 4         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 3         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 0.54%   |
| Intel Ethernet Connection (6) I219-V                                           | 3         | 0.54%   |
| DisplayLink Dell Universal Dock D6000                                          | 3         | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.36%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.36%   |
| Realtek Realtek Ethernet controller                                            | 2         | 0.36%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 2         | 0.36%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 2         | 0.36%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.36%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.36%   |
| OnePlus (Shenzhen) EB2103                                                      | 2         | 0.36%   |
| Nvidia MCP79 Ethernet                                                          | 2         | 0.36%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.36%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.36%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.36%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.36%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.36%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.36%   |
| Intel Ethernet Connection I219-V                                               | 2         | 0.36%   |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.36%   |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.36%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 0.36%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 0.36%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.36%   |
| Intel Ethernet Connection (14) I219-LM                                         | 2         | 0.36%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.36%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.36%   |
| Intel Ethernet Connection (10) I219-LM                                         | 2         | 0.36%   |
| Intel 82577LC Gigabit Network Connection                                       | 2         | 0.36%   |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.36%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 2         | 0.36%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                               | 2         | 0.36%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 2         | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 703       | 57.06%  |
| Ethernet | 518       | 42.05%  |
| Modem    | 9         | 0.73%   |
| Unknown  | 2         | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 654       | 65.27%  |
| Ethernet | 346       | 34.53%  |
| Unknown  | 2         | 0.2%    |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 473       | 66.43%  |
| 1     | 228       | 32.02%  |
| 0     | 8         | 1.12%   |
| 3     | 2         | 0.28%   |
| 4     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 514       | 71.59%  |
| Yes  | 204       | 28.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 310       | 52.99%  |
| Realtek Semiconductor           | 57        | 9.74%   |
| Qualcomm Atheros Communications | 55        | 9.4%    |
| Lite-On Technology              | 32        | 5.47%   |
| Broadcom                        | 26        | 4.44%   |
| IMC Networks                    | 25        | 4.27%   |
| Foxconn / Hon Hai               | 17        | 2.91%   |
| Apple                           | 15        | 2.56%   |
| Realtek                         | 10        | 1.71%   |
| Cambridge Silicon Radio         | 8         | 1.37%   |
| Dell                            | 6         | 1.03%   |
| Hewlett-Packard                 | 5         | 0.85%   |
| Toshiba                         | 4         | 0.68%   |
| ASUSTek Computer                | 3         | 0.51%   |
| Alps Electric                   | 3         | 0.51%   |
| Ralink Technology               | 2         | 0.34%   |
| Ralink                          | 2         | 0.34%   |
| Foxconn International           | 2         | 0.34%   |
| Integrated System Solution      | 1         | 0.17%   |
| Chicony Electronics             | 1         | 0.17%   |
| Askey Computer                  | 1         | 0.17%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                | 195       | 33.33%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 40        | 6.84%   |
| Realtek Bluetooth Radio                               | 36        | 6.15%   |
| Intel Bluetooth wireless interface                    | 32        | 5.47%   |
| Qualcomm Atheros  Bluetooth Device                    | 31        | 5.3%    |
| Intel AX210 Bluetooth                                 | 13        | 2.22%   |
| Realtek  Bluetooth 4.2 Adapter                        | 11        | 1.88%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 11        | 1.88%   |
| IMC Networks Wireless_Device                          | 11        | 1.88%   |
| Realtek Bluetooth Radio                               | 10        | 1.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 10        | 1.71%   |
| Apple Bluetooth Host Controller                       | 10        | 1.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 8         | 1.37%   |
| Lite-On Wireless_Device                               | 8         | 1.37%   |
| Lite-On Bluetooth Device                              | 8         | 1.37%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 8         | 1.37%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 8         | 1.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 7         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 7         | 1.2%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 6         | 1.03%   |
| Intel Wireless-AC 3168 Bluetooth                      | 6         | 1.03%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 6         | 1.03%   |
| IMC Networks Bluetooth Radio                          | 6         | 1.03%   |
| Broadcom BCM2045B (BDC-2.1)                           | 6         | 1.03%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 4         | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 4         | 0.68%   |
| IMC Networks Bluetooth Device                         | 4         | 0.68%   |
| HP Broadcom 2070 Bluetooth Combo                      | 4         | 0.68%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth         | 4         | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                    | 4         | 0.68%   |
| Dell DW375 Bluetooth Module                           | 3         | 0.51%   |
| Apple Bluetooth USB Host Controller                   | 3         | 0.51%   |
| Toshiba Integrated Bluetooth HCI                      | 2         | 0.34%   |
| Realtek RTL8821A Bluetooth                            | 2         | 0.34%   |
| Realtek RTL8723B Bluetooth                            | 2         | 0.34%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter          | 2         | 0.34%   |
| Ralink RT3290 Bluetooth                               | 2         | 0.34%   |
| Lite-On Bluetooth Radio                               | 2         | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth                      | 2         | 0.34%   |
| IMC Networks Bluetooth                                | 2         | 0.34%   |
| Foxconn International BCM43142A0 Bluetooth module     | 2         | 0.34%   |
| Foxconn / Hon Hai Wireless_Device                     | 2         | 0.34%   |
| Foxconn / Hon Hai BCM43142A0                          | 2         | 0.34%   |
| Foxconn / Hon Hai BCM20702A0                          | 2         | 0.34%   |
| Broadcom HP Portable SoftSailing                      | 2         | 0.34%   |
| Broadcom BCM43142A0 Bluetooth Device                  | 2         | 0.34%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                  | 2         | 0.34%   |
| Apple Bluetooth HCI                                   | 2         | 0.34%   |
| Alps Electric BCM2046 Bluetooth Device                | 2         | 0.34%   |
| Toshiba Bluetooth Device                              | 1         | 0.17%   |
| Toshiba Askey Bluetooth Module                        | 1         | 0.17%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.17%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device          | 1         | 0.17%   |
| Lite-On BCM43142A0                                    | 1         | 0.17%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.17%   |
| IMC Networks Bluetooth USB Host Controller            | 1         | 0.17%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.17%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1         | 0.17%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device       | 1         | 0.17%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 0.17%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 566       | 64.69%  |
| AMD                               | 151       | 17.26%  |
| Nvidia                            | 109       | 12.46%  |
| Realtek Semiconductor             | 5         | 0.57%   |
| Logitech                          | 5         | 0.57%   |
| C-Media Electronics               | 5         | 0.57%   |
| Lenovo                            | 4         | 0.46%   |
| Sennheiser Communications         | 3         | 0.34%   |
| Hewlett-Packard                   | 3         | 0.34%   |
| GN Netcom                         | 3         | 0.34%   |
| Plantronics                       | 2         | 0.23%   |
| Elitegroup Computer Systems (ECS) | 2         | 0.23%   |
| Dell                              | 2         | 0.23%   |
| Texas Instruments                 | 1         | 0.11%   |
| SteelSeries ApS                   | 1         | 0.11%   |
| SAVITECH                          | 1         | 0.11%   |
| Qualsense                         | 1         | 0.11%   |
| Microsoft                         | 1         | 0.11%   |
| Kingston Technology               | 1         | 0.11%   |
| Google                            | 1         | 0.11%   |
| Generalplus Technology            | 1         | 0.11%   |
| Focusrite-Novation                | 1         | 0.11%   |
| FiiO Electronics Technology       | 1         | 0.11%   |
| Creative Technology               | 1         | 0.11%   |
| Corsair                           | 1         | 0.11%   |
| Conexant Systems                  | 1         | 0.11%   |
| Conexant                          | 1         | 0.11%   |
| Unknown                           | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 95        | 9.06%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 73        | 6.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 72        | 6.86%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 72        | 6.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 56        | 5.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 37        | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 36        | 3.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 34        | 3.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 28        | 2.67%   |
| Intel Comet Lake PCH cAVS                                                                         | 24        | 2.29%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 24        | 2.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 23        | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 23        | 2.19%   |
| Intel 8 Series HD Audio Controller                                                                | 23        | 2.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 21        | 2%      |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 1.81%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 17        | 1.62%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 17        | 1.62%   |
| Nvidia Audio device                                                                               | 15        | 1.43%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 1.43%   |
| AMD FCH Azalia Controller                                                                         | 15        | 1.43%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 15        | 1.43%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 12        | 1.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 1.14%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 11        | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 1.05%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 10        | 0.95%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 10        | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 0.95%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 0.86%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 0.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 0.86%   |
| AMD High Definition Audio Controller                                                              | 9         | 0.86%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 8         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 0.57%   |
| Realtek Semiconductor USB Audio                                                                   | 5         | 0.48%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 5         | 0.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.48%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 4         | 0.38%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 4         | 0.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.38%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 4         | 0.38%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 0.38%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 4         | 0.38%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.29%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.29%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.29%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.29%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.29%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 3         | 0.29%   |
| Hewlett-Packard USB Audio                                                                         | 3         | 0.29%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.29%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 3         | 0.29%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.29%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.29%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.19%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.19%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 131       | 29.37%  |
| SK Hynix            | 90        | 20.18%  |
| Micron Technology   | 81        | 18.16%  |
| Kingston            | 29        | 6.5%    |
| Unknown             | 28        | 6.28%   |
| Crucial             | 28        | 6.28%   |
| Ramaxel Technology  | 12        | 2.69%   |
| A-DATA Technology   | 8         | 1.79%   |
| Nanya Technology    | 6         | 1.35%   |
| G.Skill             | 5         | 1.12%   |
| Corsair             | 5         | 1.12%   |
| Unknown (ABCD)      | 4         | 0.9%    |
| Neo Forza           | 2         | 0.45%   |
| Elpida              | 2         | 0.45%   |
| Unknown             | 2         | 0.45%   |
| V-GeN               | 1         | 0.22%   |
| Transcend           | 1         | 0.22%   |
| Strontium           | 1         | 0.22%   |
| Smart Brazil        | 1         | 0.22%   |
| Smart               | 1         | 0.22%   |
| Sesame              | 1         | 0.22%   |
| Patriot             | 1         | 0.22%   |
| GOODRAM             | 1         | 0.22%   |
| CSX                 | 1         | 0.22%   |
| Avant               | 1         | 0.22%   |
| AMD                 | 1         | 0.22%   |
| 8001000080AD        | 1         | 0.22%   |
| 48spaces            | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 16        | 3.49%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 2.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 2.62%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 10        | 2.18%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 8         | 1.75%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 1.53%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 6         | 1.31%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 1.31%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 1.09%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 1.09%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 5         | 1.09%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.87%   |
| Samsung RAM U6E3S4AA-MGCR 1024MB Row Of Chips LPDDR4 4267MT/s    | 4         | 0.87%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.87%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 0.87%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 4         | 0.87%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 4         | 0.87%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.87%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 4         | 0.87%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 3         | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR3 2400MT/s | 3         | 0.66%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.66%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.66%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 3         | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.66%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 3         | 0.66%   |
| Ramaxel RAM RMSA3260NA78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 3         | 0.66%   |
| Micron RAM MT53E1G32D2NP-046 8GB SODIMM LPDDR4 4266MT/s          | 3         | 0.66%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s            | 3         | 0.66%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s    | 3         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.44%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.44%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.44%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 2         | 0.44%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.44%   |
| SK Hynix RAM HMT451S6MFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.44%   |
| SK Hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 2         | 0.44%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s       | 2         | 0.44%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.44%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.44%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.44%   |
| SK Hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.44%   |
| SK Hynix RAM H9HCNNNCPMMLXR-NEE 8192MB SODIMM LPDDR4 4266MT/s    | 2         | 0.44%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.44%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 2         | 0.44%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                     | 2         | 0.44%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.44%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM 1067MT/s              | 2         | 0.44%   |
| Samsung RAM M471B5273BH1-CF8 4096MB SODIMM DDR3 1067MT/s         | 2         | 0.44%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 243       | 63.61%  |
| DDR3   | 68        | 17.8%   |
| LPDDR4 | 49        | 12.83%  |
| LPDDR3 | 13        | 3.4%    |
| DDR2   | 8         | 2.09%   |
| SDRAM  | 1         | 0.26%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 311       | 80.57%  |
| Row Of Chips | 72        | 18.65%  |
| DIMM         | 1         | 0.26%   |
| Chip         | 1         | 0.26%   |
| Unknown      | 1         | 0.26%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 184       | 44.44%  |
| 4096  | 108       | 26.09%  |
| 16384 | 68        | 16.43%  |
| 2048  | 31        | 7.49%   |
| 32768 | 18        | 4.35%   |
| 1024  | 5         | 1.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 132       | 32.35%  |
| 2667    | 86        | 21.08%  |
| 1600    | 49        | 12.01%  |
| 2400    | 38        | 9.31%   |
| 4267    | 29        | 7.11%   |
| 2133    | 16        | 3.92%   |
| 4266    | 10        | 2.45%   |
| 1867    | 7         | 1.72%   |
| 1334    | 7         | 1.72%   |
| 1333    | 6         | 1.47%   |
| Unknown | 5         | 1.23%   |
| 3733    | 4         | 0.98%   |
| 1067    | 4         | 0.98%   |
| 800     | 3         | 0.74%   |
| 3266    | 2         | 0.49%   |
| 1066    | 2         | 0.49%   |
| 975     | 2         | 0.49%   |
| 667     | 2         | 0.49%   |
| 4199    | 1         | 0.25%   |
| 3000    | 1         | 0.25%   |
| 1776    | 1         | 0.25%   |
| 1200    | 1         | 0.25%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 6         | 66.67%  |
| Hewlett-Packard    | 2         | 22.22%  |
| Seiko Epson        | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Notebooks | Percent |
|------------------------------|-----------|---------|
| Brother DCP-7030             | 2         | 22.22%  |
| Seiko Epson XP-4100 Series   | 1         | 11.11%  |
| HP LaserJet 1010             | 1         | 11.11%  |
| HP ENVY Photo 7800 series    | 1         | 11.11%  |
| Brother MFC-J6945DW          | 1         | 11.11%  |
| Brother MFC Composite Device | 1         | 11.11%  |
| Brother DCP-1600             | 1         | 11.11%  |
| Brother DCP-1510             | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 2         | 66.67%  |
| Seiko Epson | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO] | 1         | 33.33%  |
| Canon CanoScan LiDE 220                           | 1         | 33.33%  |
| Canon CanoScan LiDE 110                           | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 163       | 24.55%  |
| IMC Networks                           | 72        | 10.84%  |
| Microdia                               | 63        | 9.49%   |
| Acer                                   | 57        | 8.58%   |
| Realtek Semiconductor                  | 56        | 8.43%   |
| Quanta                                 | 42        | 6.33%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 4.37%   |
| Sunplus Innovation Technology          | 26        | 3.92%   |
| Lite-On Technology                     | 19        | 2.86%   |
| Syntek                                 | 17        | 2.56%   |
| Suyin                                  | 15        | 2.26%   |
| Luxvisions Innotech Limited            | 13        | 1.96%   |
| Apple                                  | 13        | 1.96%   |
| Ricoh                                  | 10        | 1.51%   |
| Logitech                               | 9         | 1.36%   |
| Silicon Motion                         | 8         | 1.2%    |
| Lenovo                                 | 8         | 1.2%    |
| Alcor Micro                            | 7         | 1.05%   |
| Samsung Electronics                    | 5         | 0.75%   |
| SunplusIT                              | 3         | 0.45%   |
| Z-Star Microelectronics                | 2         | 0.3%    |
| USB2.0 Webcamera                       | 2         | 0.3%    |
| Unknown                                | 2         | 0.3%    |
| Microsoft                              | 2         | 0.3%    |
| Jieli Technology                       | 2         | 0.3%    |
| DJJHFA1BIEW726                         | 2         | 0.3%    |
| DigiTech                               | 2         | 0.3%    |
| Tobii Technology AB                    | 1         | 0.15%   |
| Sunplus Technology                     | 1         | 0.15%   |
| Sonix Technology                       | 1         | 0.15%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.15%   |
| Ruision                                | 1         | 0.15%   |
| Primax Electronics                     | 1         | 0.15%   |
| PC-LM1E                                | 1         | 0.15%   |
| OmniVision Technologies                | 1         | 0.15%   |
| Importek                               | 1         | 0.15%   |
| GenesysLogic Technology                | 1         | 0.15%   |
| Generalplus Technology                 | 1         | 0.15%   |
| Creative Technology                    | 1         | 0.15%   |
| ARC International                      | 1         | 0.15%   |
| ALi                                    | 1         | 0.15%   |
| 8SSC20F27114V1SR0BM1TEX                | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                | 47        | 7.04%   |
| Chicony Integrated Camera                                    | 34        | 5.09%   |
| Realtek Integrated_Webcam_HD                                 | 25        | 3.74%   |
| Chicony HD WebCam                                            | 23        | 3.44%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 22        | 3.29%   |
| IMC Networks Integrated Camera                               | 22        | 3.29%   |
| Acer Integrated Camera                                       | 19        | 2.84%   |
| Quanta HD User Facing                                        | 17        | 2.54%   |
| Chicony HP HD Camera                                         | 11        | 1.65%   |
| Chicony USB 2.0 Camera                                       | 10        | 1.5%    |
| Syntek Integrated Camera                                     | 9         | 1.35%   |
| Sunplus Integrated_Webcam_HD                                 | 9         | 1.35%   |
| Lite-On HP HD Camera                                         | 9         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera             | 9         | 1.35%   |
| Quanta HP HD Camera                                          | 8         | 1.2%    |
| IMC Networks HD Camera                                       | 7         | 1.05%   |
| Realtek Integrated Webcam                                    | 6         | 0.9%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 6         | 0.9%    |
| Acer EasyCamera                                              | 6         | 0.9%    |
| Sunplus FHD Camera Microphone                                | 5         | 0.75%   |
| Samsung Galaxy A5 (MTP)                                      | 5         | 0.75%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 5         | 0.75%   |
| Lite-On Integrated Camera                                    | 5         | 0.75%   |
| Chicony HP Wide Vision HD Camera                             | 5         | 0.75%   |
| Chicony HP Truevision HD                                     | 5         | 0.75%   |
| Chicony EasyCamera                                           | 5         | 0.75%   |
| Acer Lenovo EasyCamera                                       | 5         | 0.75%   |
| Quanta HP TrueVision HD Camera                               | 4         | 0.6%    |
| Lenovo Integrated Webcam                                     | 4         | 0.6%    |
| IMC Networks XiaoMi Webcam                                   | 4         | 0.6%    |
| IMC Networks USB2.0 VGA UVC WebCam                           | 4         | 0.6%    |
| Chicony USB2.0 HD UVC WebCam                                 | 4         | 0.6%    |
| Chicony TOSHIBA Web Camera - HD                              | 4         | 0.6%    |
| Chicony Lenovo EasyCamera                                    | 4         | 0.6%    |
| Chicony HP Truevision HD camera                              | 4         | 0.6%    |
| Chicony HD User Facing                                       | 4         | 0.6%    |
| Apple iPhone 5/5C/5S/6/SE                                    | 4         | 0.6%    |
| Apple FaceTime HD Camera                                     | 4         | 0.6%    |
| Acer SunplusIT Integrated Camera                             | 4         | 0.6%    |
| Acer Lenovo Integrated Webcam                                | 4         | 0.6%    |
| Acer BisonCam,NB Pro                                         | 4         | 0.6%    |
| Syntek Lenovo EasyCamera                                     | 3         | 0.45%   |
| Syntek EasyCamera                                            | 3         | 0.45%   |
| SunplusIT 720p HD Camera                                     | 3         | 0.45%   |
| Ricoh Integrated Webcam                                      | 3         | 0.45%   |
| Realtek USB Camera                                           | 3         | 0.45%   |
| Realtek Laptop Camera                                        | 3         | 0.45%   |
| Quanta VGA WebCam                                            | 3         | 0.45%   |
| Microdia HP Webcam                                           | 3         | 0.45%   |
| Lite-On TOSHIBA Web Camera - HD                              | 3         | 0.45%   |
| Lenovo Integrated Webcam [R5U877]                            | 3         | 0.45%   |
| Chicony VGA Webcam                                           | 3         | 0.45%   |
| Chicony USB2.0 VGA UVC WebCam                                | 3         | 0.45%   |
| Chicony USB 2.0 Webcam Device                                | 3         | 0.45%   |
| Chicony Integrated Camera (1280x720@30)                      | 3         | 0.45%   |
| Chicony HP Webcam [2 MP Macro]                               | 3         | 0.45%   |
| Chicony HP HD Webcam                                         | 3         | 0.45%   |
| Chicony FJ Camera                                            | 3         | 0.45%   |
| Chicony Acer CrystalEye Webcam                               | 3         | 0.45%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 3         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 48        | 30.38%  |
| Validity Sensors           | 43        | 27.22%  |
| Synaptics                  | 38        | 24.05%  |
| LighTuning Technology      | 11        | 6.96%   |
| Upek                       | 8         | 5.06%   |
| AuthenTec                  | 7         | 4.43%   |
| Elan Microelectronics      | 2         | 1.27%   |
| Samsung Electronics        | 1         | 0.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 26        | 16.46%  |
| Shenzhen Goodix FingerPrint                                                | 18        | 11.39%  |
| Unknown                                                                    | 13        | 8.23%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 12        | 7.59%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 6.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 9         | 5.7%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 5.06%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 3.8%    |
| Validity Sensors Fingerprint scanner                                       | 5         | 3.16%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.53%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.53%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 2.53%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 1.9%    |
| Validity Sensors Synaptics WBDI                                            | 3         | 1.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.9%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 1.9%    |
| Validity Sensors VFS491                                                    | 2         | 1.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.27%   |
| Synaptics  WBDI                                                            | 2         | 1.27%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.27%   |
| AuthenTec AES1600                                                          | 2         | 1.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.63%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.63%   |
| Samsung Fingerprint Device                                                 | 1         | 0.63%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.63%   |
| AuthenTec AES2810                                                          | 1         | 0.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 31        | 57.41%  |
| O2 Micro                          | 6         | 11.11%  |
| Lenovo                            | 6         | 11.11%  |
| Alcor Micro                       | 6         | 11.11%  |
| Upek                              | 4         | 7.41%   |
| VASCO Data Security International | 1         | 1.85%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                              | 13        | 24.07%  |
| Broadcom BCM5880 Secure Applications Processor             | 10        | 18.52%  |
| Broadcom 58200                                             | 8         | 14.81%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 6         | 11.11%  |
| Lenovo Integrated Smart Card Reader                        | 6         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 9.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 4         | 7.41%   |
| VASCO Data Security International DIGIPASS 870             | 1         | 1.85%   |
| Alcor Micro Watchdata W 1981                               | 1         | 1.85%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 441       | 61.51%  |
| 1     | 234       | 32.64%  |
| 2     | 37        | 5.16%   |
| 3     | 5         | 0.7%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 154       | 48.43%  |
| Chipcard                 | 55        | 17.3%   |
| Graphics card            | 50        | 15.72%  |
| Net/wireless             | 29        | 9.12%   |
| Multimedia controller    | 9         | 2.83%   |
| Net/ethernet             | 4         | 1.26%   |
| Card reader              | 4         | 1.26%   |
| Storage                  | 3         | 0.94%   |
| Camera                   | 3         | 0.94%   |
| Bluetooth                | 3         | 0.94%   |
| Sound                    | 1         | 0.31%   |
| Modem                    | 1         | 0.31%   |
| Dvb card                 | 1         | 0.31%   |
| Communication controller | 1         | 0.31%   |

